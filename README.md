# css
1. Tạo progress bar circle
-html :
  <div class='w'>
  <div class='i'> 40%</div>
</div>
-css : 
.i {
  
  position: absolute;
  top: 0px;
  left: 0px;
  width: 100px;
  height: 100px;
  border-radius: 50%;
  background-color: red;
  clip: rect(0px, 120px, 50px, 50px);
}
.w {
  position: relative;
  width: 500px;
  height: 500px;
}
