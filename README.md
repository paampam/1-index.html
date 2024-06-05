# 1-index.html
function setup() {
  createCanvas(600,600);
  background("white")
}

function dfuraw() {
  stroke("yellow");
  fill("orange");
  
  
  if (mouseIsPressed) {
    rect(mouseX, mouseY, 5, 5);
  }
}
