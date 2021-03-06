title: Getting started with react and canvas via Konva
layout: react_page
---

<div style="text-align: center">
  <img src="https://cloud.githubusercontent.com/assets/1443320/12193428/3bda2fcc-b623-11e5-8319-b1ccfc95eaec.png"/>
</div>

`react-konva` is a JavaScript library for drawing complex canvas graphics using [React](http://facebook.github.io/react/). It provides declarative and reactive bindings to the [Konva Framework](https://konvajs.org/).


[Github Repo](https://github.com/lavrton/react-konva)


An attempt to make [React](http://facebook.github.io/react/) work with the HTML5 canvas library. The goal is to have similar declarative markup as normal React and to have similar data-flow model.

**Currently, `react-konva` is not supported in React Native environment.**

Currently you can use all `Konva` nodes and shapes as React components and all `Konva` events are supported on them in same way.

**Note: you can find a lot of demos and examples of using Konva there: [https://konvajs.org/](https://konvajs.org/). Really, just go there and take a look what Konva can do for you. You will be able to do the same with react-konva too. `Konva` for `react-konva` is like DOM for `React`.**

## Installation

```bash
npm install react-konva konva --save
```

<iframe src="https://codesandbox.io/embed/github/konvajs/site/tree/master/react-demos/basic_demo?hidenavigation=1&view=split&fontsize=10" style="width:100%; height:500px; border:0; border-radius: 4px; overflow:hidden;" sandbox="allow-modals allow-forms allow-popups allow-scripts allow-same-origin"></iframe>


## Comparisons

### react-konva vs react-canvas

[react-canvas](https://github.com/Flipboard/react-canvas) is a completely
different react plugin. It allows you to draw DOM-like objects (images, texts)
on canvas element in very performant way. It is NOT about drawing graphics, but
react-konva is exactly for drawing complex graphics on `<canvas>` element from
React.

### react-konva vs react-art

[react-art](https://github.com/reactjs/react-art) allows you to draw graphics on
a page. It also supports SVG for output. But it has no support of events of
shapes.

### react-konva vs vanilla canvas

Vanilla canvas can is faster because when you use `react-konva` you have two layers of abstractions: (1) `Konva` framework is on top of canvas and (2) `React` is on top of `Konva`. For many applications is performance is still very good. The purpose of `react-konva` is to reduce the complexity of the application and use well-known declarative way for drawing on canvas.

