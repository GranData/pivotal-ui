# Back To Top

## Installation & Usage

#### React
`npm install babel-loader react-svg-loader --save-dev`

`npm install pui-react-back-to-top --save`

`import {BackToTop} from 'pui-react-back-to-top';`

#### CSS Only
`npm install pui-css-back-to-top --save`

## Description

(The extra loaders are for the [Iconography](/react_base_iconography.html) component.)

You can use this component to scroll to the top of a page.

The button will be fixed to the bottom right hand corner of the page.

You can place the link anywhere in your markup, but best practices are either towards the top or bottom of your markup.

## Examples

```jsx
::title=Always Visible Example
<div>
<BackToTop alwaysVisible />
</div>
```

## Props

Property | Required | Type | Default | Description
---------|----------|------|---------|------------
alwaysVisible  | no | Boolen | false | If `alwaysVisible` is not set, the component will only appear after the window has been scrolled.
