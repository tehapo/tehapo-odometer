# &lt;tehapo-odometer&gt;

Simple odometer style animated number display as a Polymer-based web component.

<img src="https://raw.githubusercontent.com/tehapo/tehapo-odometer/master/screenshot.gif" width="434" alt="Screenshot of tehapo-odometer" />

## Installation
```bash
bower install tehapo-odometer --save
```

## Usage
```html
<style is="custom-style">
  /* Use the --tehapo-odometer-digit mixin to apply styles to individual digits. */
  tehapo-odometer {
    --tehapo-odometer-digit: {
      background: #333;
      color: #fff;
      border-radius: 4px;
      padding: 0 0.2em;
    }
  }
</style>

<tehapo-odometer value="1523294"></tehapo-odometer>
```

## Development
Use ```polyserve``` during development as instructed in [Create a reusable element](https://www.polymer-project.org/1.0/docs/start/reusableelements.html) article.
