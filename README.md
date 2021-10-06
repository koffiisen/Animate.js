# ![](src/small.png) Animate.js 
**Every feedback is welcome!**

[![GitHub Version](https://img.shields.io/github/release/Animate.js/Animate.js.svg?style=for-the-badge)](https://github.com/koffiisen/Animate.js/releases)
[![Github Star](https://img.shields.io/github/stars/Animate.js/Animate.js.svg?style=for-the-badge)](https://github.com/koffiisen/Animate.js/stargazers)
[![Github Fork](https://img.shields.io/github/forks/Animate.js/Animate.js.svg?style=for-the-badge)](https://github.com/koffiisen/Animate.js/network/members)
[![License](https://img.shields.io/github/license/Animate.js/Animate.js.svg?style=for-the-badge)](https://github.com/koffiisen/Animate.js/blob/master/LICENSE)

`animate.js` is a simple javascript library to animate any html element


## Demo
[Animate.js DEMO ***](https://koffiisen.github.io/Animate.js/)


## Installation

Download animate.min.js in dist folder:

```bash
$ dist/animate.min.js
```

## Usage

To use Animate.js in your website, simply drop the javascript into your document's `<body>`

```html
<body>
  <div id="domElement"></div>
  <!-- -->
  <script src="dist/animate.min.js"></script>
</body>
```

or use with jquery

```html
<body>
  <!-- -->
  <script src="https://code.jquery.com/jquery-3.4.1.min.js"></script>
  <script src="dist/animate.min.js"></script>
</body>
```

### Available Animator (89)

| bounce | flash | pulse | headShake | wobble | jello | bounceIn | bounceInDown | bounceInLeft | bounceInRight | bounceInUp | bounceOut | bounceOutDown | bounceOutUp | fadeIn | fadeInDown | fadeInDownBig | fadeInLeft | fadeInLeftBig | fadeInRight | fadeInRightBig | fadeInUp | fadeInUpBig | fadeOutDown | fadeOutDownBig | fadeOutLeftBig | fadeOutRightBig | fadeOutUp | fadeOutUpBig | flipInX | flipInY | flipOutX | flipOutY | lightSpeedIn | lightSpeedOut | rotateIn | rotateInDownLeft | rotateInDownRight | rotateInUpLeft | rotateInUpRight | rotateOut | rotateOutDownLeft | rotateOutDownRight | rotateOutUpLeft | rotateOutUpRight | jackInTheBox | rollIn | rollOut | zoomInDown | zoomInLeft | zoomInRight | zoomInUp | zoomOutDown | zoomOutLeft | zoomOutRight | zoomOutUp | slideInDown | slideInLeft | slideInRight | slideInUp | slideOutDown | slideOutLeft | slideOutRight | slideOutUp | heartBeat | rollOutRight | rollOutLeft | rubberBand | zoomOut | zoomIn | fadeOut | fadeOutRight | fadeOutLeft | fadeOutTop | fadeOutBottom | horizontalFlip | verticalFlip | bounceOutBottom | bounceOutTop | bounceOutLeft | bounceOutRight | rotateClockwise | rotateAntiClockwise | tada | moveIn | moveOut | swing | shake | hinge |
| ------ | ----- | ----- | --------- | ------ | ----- | -------- | ------------ | ------------ | ------------- | ---------- | --------- | ------------- | ----------- | ------ | ---------- | ------------- | ---------- | ------------- | ----------- | -------------- | -------- | ----------- | ----------- | -------------- | -------------- | --------------- | --------- | ------------ | ------- | ------- | -------- | -------- | ------------ | ------------- | -------- | ---------------- | ----------------- | -------------- | --------------- | --------- | ----------------- | ------------------ | --------------- | ---------------- | ------------ | ------ | ------- | ---------- | ---------- | ----------- | -------- | ----------- | ----------- | ------------ | --------- | ----------- | ----------- | ------------ | --------- | ------------ | ------------ | ------------- | ---------- | --------- | ------------ | ----------- | ---------- | ------- | ------ | ------- | ------------ | ----------- | ---------- | ------------- | -------------- | ------------ | --------------- | ------------ | ------------- | -------------- | --------------- | ------------------- | ---- | ------ | ------- | ----- | ----- | ----- |
| bounce | flash | pulse | headShake | wobble | jello | bounceIn | bounceInDown | bounceInLeft | bounceInRight | bounceInUp | bounceOut | bounceOutDown | bounceOutUp | fadeIn | fadeInDown | fadeInDownBig | fadeInLeft | fadeInLeftBig | fadeInRight | fadeInRightBig | fadeInUp | fadeInUpBig | fadeOutDown | fadeOutDownBig | fadeOutLeftBig | fadeOutRightBig | fadeOutUp | fadeOutUpBig | flipInX | flipInY | flipOutX | flipOutY | lightSpeedIn | lightSpeedOut | rotateIn | rotateInDownLeft | rotateInDownRight | rotateInUpLeft | rotateInUpRight | rotateOut | rotateOutDownLeft | rotateOutDownRight | rotateOutUpLeft | rotateOutUpRight | jackInTheBox | rollIn | rollOut | zoomInDown | zoomInLeft | zoomInRight | zoomInUp | zoomOutDown | zoomOutLeft | zoomOutRight | zoomOutUp | slideInDown | slideInLeft | slideInRight | slideInUp | slideOutDown | slideOutLeft | slideOutRight | slideOutUp | heartBeat | rollOutRight | rollOutLeft | rubberBand | zoomOut | zoomIn | fadeOut | fadeOutRight | fadeOutLeft | fadeOutTop | fadeOutBottom | horizontalFlip | verticalFlip | bounceOutBottom | bounceOutTop | bounceOutLeft | bounceOutRight | rotateClockwise | rotateAntiClockwise | tada | moveIn | moveOut | swing | shake | hinge |

Example:

```javascript
let domElement = document.getElementById("elementId");
domElement.bounce();
```

It's possible to change the duration of your animations :

```javascript
let domElement = document.querySelector("element");
domElement.bounce(700);
```

## Usage with jQuery:
```javascript
$(".button").flash();
// $(".button").flash(900);
// $(".button")[2].flash();
$("#domElement").jello();
```

## License

Animate.js is licensed under the MIT license. (https://opensource.org/licenses/MIT)

## Author
[koffiisen](https://github.com/koffiisen)


