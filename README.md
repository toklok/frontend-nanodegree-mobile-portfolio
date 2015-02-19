## Website Performance Optimization portfolio project

Line 518:  //requestAnimationFrame is used for the scrolling. www.html5rocks.com/en/tutorials/speed/scrolling/

//CSS code for the mover, using transform. 

.mover {
  transform: translate3d(0,0,0);
  position: fixed;
  width: 256px;
  z-index: -1;
  transition: all 1s ease-out;
}

//Changed Line 522:  document.getElementsByClassName('.mover'),
