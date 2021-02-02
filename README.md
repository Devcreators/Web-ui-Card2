# 참고 강의
> [OnlineTutorials](https://ibit.ly/dXgo)

# 실행 결과
<img src="https://tinyurl.com/y5j7f3xj" width="800" height="260">

``` css
/* ====== 공통 ====== */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Georgia, serif;
}

:root {
  --color: #26ed93;
}

body {
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  background: var(--color);
}

.container {
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
}

.container .box {
  position: relative;
  width: 250px;
  height: 200px;
  margin: 30px;
  background: var(--color);
  font-size: 2em;
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 15px;
  color: rgba(0, 0, 0, 0.3);
}
```

---

### Card01
<img src="https://tinyurl.com/y29d79o4" width="300" height="260">

```css
.container .box.shadow1 {
  box-shadow: -10px -10px 10px rgba(255, 255, 255, 0.2),
    15px 15px 15px rgba(0, 0, 0, 0.1);
}
```

---

### Card02
<img src="https://tinyurl.com/y5f29rax" width="300" height="260">

```css
.container .box.shadow2 {
  box-shadow: -10px -10px 10px rgba(255, 255, 255, 0.2),
    15px 15px 15px rgba(0, 0, 0, 0.1),
    inset -10px -10px 10px rgba(255, 255, 255, 0.2),
    inset 15px 15px 15px rgba(0, 0, 0, 0.1);
}
```

---

### Card03
<img src="https://tinyurl.com/y4zqwzcm" width="300" height="260">

```css
.container .box.shadow3 {
  box-shadow: inset 4px 4px 5px rgba(255, 255, 255, 0.3),
    inset -4px -4px 5px rgba(0, 0, 0, 0.1), 10px 40px 50px rgba(0, 0, 0, 0.1);
}
```

---

### Card04
<img src="https://tinyurl.com/y49p4bye" width="300" height="260">

```css
.container .box.shadow4 {
  border: 10px solid var(--color);
  box-shadow: -10px -10px 10px rgba(255, 255, 255, 0.2),
    15px 15px 15px rgba(0, 0, 0, 0.1),
    inset -10px -10px 10px rgba(255, 255, 255, 0.2),
    inset 15px 15px 15px rgba(0, 0, 0, 0.1);
}
```

---

## 작성일자 : 2021-02-02
