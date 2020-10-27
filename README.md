# My First README

Repo explaining README.md


~
## Steps to install on local computer
1. Go to [repo](https://github.com/zfinnan/tic-tac-toe) on Github profile
2. `fork` and `clone` repo
3. Clone to local machine
```text
git clone https://github.com/zfinnan/tic-tac-toe.git
```
4. Go to `tic-tac-toe` directory
5. Open `index.html` in browser
```text
open index.html
```

```javascript
function selectWinnerBoxes(b1,b2,b3){
    b1.classList.add("win");
    b2.classList.add("win");
    b3.classList.add("win");
    turn.innerHTML = b1.innerHTML + " Won!";
    turn.style.fontSize = "40px";
}
```

```css
.container .box{float: left;
                width: 100px;
                height: 100px;
                border: 1px solid black;
                transition: all .25s ease-in-out;
                font-family: sans-serif; 
                font-size: 85px;
                text-align: center;
                line-height: 100px; 
                cursor: pointer;
              }
```

```html
<div class="container" id="main">
    <span id="turn">Play</span>
    <div class="box" id="box1"></div>
    <div class="box" id="box2"></div>
    <div class="box" id="box3"></div>
    <div class="box" id="box4"></div>
    <div class="box" id="box5"></div>
    <div class="box" id="box6"></div>
    <div class="box" id="box7"></div>
    <div class="box" id="box8"></div>
    <div class="box" id="box9"></div>
</div>
```

| Functions            | Description |
| -----------          | ----------- |
| `selectWinnerBoxes()`| Determines boxes selected that result in win |
| `replay()`           | Allows play again button after game end |
| `getWinner()`        | Determines winner through all possible combinations |