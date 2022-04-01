# css-responsive-settings
Readme for 🎨⚙ CSS Responsive Settings.

## GET STARTED 🚀

### ROOT.CSS

#### *

Add margin, padding in 0 with box-sizing in border-box.

```css
  * {
      margin: 0;
      padding: 0;
          -webkit-box-sizing: border-box;
      box-sizing: border-box;
          -webkit-padding-start: 0px;
  }
```

#### Html & body

Add margin, padding in 0 with width and height in 100%, with this you can use height of 100% in your containers.

```css
  html,
  body {
      margin: 0;
      padding: 0;
      width: 100%;
      height: 100%;
      position: relative;
  }
```

#### Html

Scroll smooth & friendly :)

```css
  html{
      scroll-behavior: smooth;
  }
```

#### Body

Body with position relative and overflow-x hidden for responsive mode and does not allow horizontal side scrolling.

```css
  body{
      position: relative;
      overflow-x: hidden !important;
  }
```

#### Body > div

All div tags inside the body do not allow horizontal side scrolling.

```css
  body > div {
      overflow: hidden !important;
  }
```

#### Body > section

All section tags inside the body do not allow horizontal side scrolling.

```css
  body > section {
      overflow: hidden !important;
  }
```
