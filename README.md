# obelisk-playground

## 알아둬야 할 것

### Coordinate System

기존의 2D 좌표계는 아래와 같이 정의된다.

![image](https://user-images.githubusercontent.com/23455736/114571643-cbf66880-9cb1-11eb-94d5-831a6e6abce8.png)

obelisk.js에서의 isometric 3D 좌표계는 다음과 같이 정의되며,

![image](https://user-images.githubusercontent.com/23455736/114572424-6f477d80-9cb2-11eb-9941-f4a9bf586f34.png)

```javascript
const p3d = new obelisk.Point3D(40, 40, 40);
```

해당 코드에 대한 렌더링 결과는 아래와 같다.

![image](https://user-images.githubusercontent.com/23455736/114572477-7c646c80-9cb2-11eb-9466-cce0309cba52.png)

```javascript
const point = new obelisk.Point(200, 200);
```

처럼 Point 메서드를 사용할 시 전체 픽셀 뷰를 어디에 배치할지에 대한 설정이 가능하다.
