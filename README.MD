# Creative Coding 筆記

[老師筆記CH1](https://course.creativecoding.in/note/chap/1)
作業使用OPEN PROCESSING製作
最後才會教怎麼匯出

1. 什麼是Creative Coding
2. `p5.js`基礎 [老師筆記](https://course.creativecoding.in/note/chap/2)
3. 圖形繪製 [老師筆記](https://course.creativecoding.in/note/chap/3)
4. 變數與資料 [老師筆記](https://course.creativecoding.in/note/chap/4)
5. 迴圈與互動 [老師筆記](https://course.creativecoding.in/note/chap/5)
6. 添增色彩 [老師筆記](https://course.creativecoding.in/note/chap/6)
7. 進階繪圖 - 畫布操作與編織複雜圖形[老師筆記](https://course.creativecoding.in/note/chap/7)
8. 函數與物件互動 [老師筆記](https://course.creativecoding.in/note/chap/8)
9. 韻律、隨機性與噪聲 - 詩意與自然模擬 [老師筆記](https://course.creativecoding.in/note/chap/9)
10. 網頁元素(DOM) [老師筆記](https://course.creativecoding.in/note/chap/10)
11. 物件導向與向量 - Class 粒子系統 [老師筆記](https://course.creativecoding.in/note/chap/11)
12. 媒體 - 影像、聲音與影片的整合與拆解 [老師筆記](https://course.creativecoding.in/note/chap/12)
13. 使用者影音互動 - 即時串流聲音與影片 [老師筆記](https://course.creativecoding.in/note/chap/13)
14. 資料視覺化與API [老師筆記](https://course.creativecoding.in/note/chap/14)
15. 發表作品 - 輸出與使用至不同平台 [老師筆記](https://course.creativecoding.in/note/chap/15)
16. 後續路線與工具介紹 - OF / Unreal / Unity / TD [老師筆記](https://course.creativecoding.in/note/chap/16)

## `p5.js`
跟Arduino, unity很像

```js
function setup() {
	createCanvas(500, 500);
	background(100);
}

function draw() {
	rect(mouseX, mouseY, 40, 20);
}

```


> 其中 `draw()` rate 是 `120/秒`


# 2020 WEB review

> 重拾互動設計開發技能

## HTML Review


---
# 2020 06 - Processing with Arduino play video

利用開關選擇需要播放的影片
相關教學
[Processing 控制 燈泡](https://www.youtube.com/watch?v=7iMMUO0J3h4)