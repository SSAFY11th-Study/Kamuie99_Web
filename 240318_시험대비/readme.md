# Web 시험 대비

### HTML CSS

- HTML : Hyper Text Markup Language
- CSS

```css
p span {
	color : red;
} /* <p> 안에 있는 모든 <span>을 선택 */

p > span {
	color : blue;
} /* <p> 한 단계 아래 자식들 중 <span>만 선택 */
```

<aside>
💡 명시도 순서 : !important → Inline 스타일 → (ID, class, 요소 선택자 순서) → 코드 선언 순서

</aside>

- block 타입: 한 줄 전체를 차지, width, height 역시 지정 가능
- Inline 타입: 수직 방향으로 다른 요소를 밀 수 없음, 수평 방향으로는 가능, width, height 지정 불가능

### BootStrap

- **margin & padding in BootStrap** ex) mt - 5

| Property   | Sides          | Size       |
| ---------- | -------------- | ---------- |
| m(margin)  | t(top)         | 0          |
| p(padding) | b(bottom)      | 1(4px)     |
|            | s(left)        | 2(8px)     |
|            | e(right)       | 3(16px)    |
|            | y(top, bottom) | 4(24px)    |
|            | x(left, right) | 5(48px)    |
|            | “ ”(4 sides)   | auto(auto) |
- 그 외 자주 쓰는 BootStrap

| CSS                      | BootStrap Class        |
| ------------------------ | ---------------------- |
| display: flex;           | d-flex                 |
| flex-direction: row;     | flex-row               |
| flex-direction: column;  | flex-column            |
| justify-content: center; | justify-content-center |
| align-items: center;     | align-items-center     |
- Grid System