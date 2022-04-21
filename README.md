# Learning Web Components

Just one of the things I'm learning. https://github.com/hchiam/learning

Web components can be used with any framework.

Open WC has a project/component starter, similar to [`create-react-app`](https://github.com/hchiam/learning-reactjs):

```sh
npm init @open-wc
# can generate/update a component or project, with nice recommendations/suggestions
```

## You can make your own custom web component from scratch with native browser JS:

```js
class AppDrawer extends HTMLElement {...}
window.customElements.define('app-drawer', AppDrawer);

// Or use an anonymous class if you don't want a named constructor in current scope.
window.customElements.define('app-drawer', class extends HTMLElement {...});
```

You may want to get started faster though, instead of making web components from scratch, so you may want to try things like LitElement.

## Demos:

Wired elements example: https://codepen.io/hchiam/pen/BaBXvqK

Model-viewer example: https://codepen.io/hchiam/pen/yLBmZLK

## Resources:

Wired elements example: https://github.com/wiredjs/wired-elements

Model-viewer example: https://github.com/GoogleWebComponents/model-viewer

Make your own custom web component: https://developers.google.com/web/fundamentals/web-components/customelements

More info on web components: https://developers.google.com/web/fundamentals/web-components

Video intro on web components: https://www.youtube.com/watch?v=YBwgkr_Sbx0

7 Web Component Tricks: https://daverupert.com/2022/04/7-web-component-tricks

## Shadow DOM:

https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_shadow_DOM

https://github.com/hchiam/learning-shadow-dom/blob/master/README.md
