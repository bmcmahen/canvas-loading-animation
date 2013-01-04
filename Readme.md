
# canvas_loading_animation

  a canvas loading animation component

## Installation

    $ component install bmcmahen/canvas-loading-animation

## API

   ```javascript
   var spinner = require(bmcmahen-canvas-loading-animation);
   var loading = spinner({
      color: '130, 170, 60',
      width: 100,
      height: 100, 
      number: 12,
      radius: 10,
      dotRadius: 2
   });

   var wrapper = document.getElementById('myspinner');
   wrapper.appendChild(loading.canvas);
   ```
   
## License

  MIT
