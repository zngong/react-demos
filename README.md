This is a simple demos of React.js.

## How to use

First copy the demos into your disk.

```bash
$ git clone https://github.com/zngong/react-demos.git
```

Then play with the source files under the repo's demo* directories.

## HTML Template

```html
<!DOCTYPE html>
<html>
  <head>
    <script src="../build/react.js"></script>
    <script src="../build/react-dom.js"></script>
    <script src="../build/browser.min.js"></script>
  </head>
  <body>
    <div id="example"></div>
    <script type="text/babel">

      // ** Our code goes here! **

    </script>
  </body>
</html>
```
Attention, you have to use `<script type="text/babel">` to indicate JSX codes, and include `browser.min.js`, which is a [browser version](https://babeljs.io/docs/usage/browser/) of Babel and could be get inside a [babel-core@5](https://www.npmjs.com/package/babel-core) npm release, to actually perform the transformation in the browser.

Before v0.14, React use `JSTransform.js` to translate `<script type="text/jsx">`. It has been deprecated ([more info](https://facebook.github.io/react/blog/2015/06/12/deprecating-jstransform-and-react-tools.html)).
