
# 創作一個滑鼠畫筆

點擊`mouseIsPressed`的時候更改狀態

```js
function setup() {
	createCanvas(600, 600);
	background("#519D9E");
}

function draw() {
	background(100, 2);
	// stroke(255,0,0);
	// strokeWeight(20);
	
	if(mouseIsPressed){
		fill(mouseX, mouseY, frameCount);
		ellipse(mouseX, mouseY, 70, 70);
		
	}else{
		fill(frameCount, mouseX, mouseY);
		rect(mouseX, mouseY, 80, 80);
	}
	//print(frameCount);
	
}
```
