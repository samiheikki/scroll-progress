scroll-progress
===============

![Screenshot](demo.png)

The Scroll Progress is a Polymer-based element providing a progress bar to top of the document to show to user how much content is still left.

See a [live demo](#).

## Getting Started

### Installation
```bash
bower install scroll-progress --save
```

### Usage
```html
<scroll-progress></scroll-progress>

<!-- Custom styling -->
<style is="custom-style">
    scroll-progress {
      --scroll-progress-color: #e91e63;
      --scroll-background-color: #e0e0e0;
    }
</style>
```

### Development
Use ```polyserve``` during development as instructed in [Create a reusable element](https://www.polymer-project.org/1.0/docs/start/reusableelements.html) article.
