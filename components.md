# GuruLab Components

All CSS rulesets can be found in the `main.css` file.

## Introduction

### Component

These are regular `html` tags that require additionla class attributes to specify their appearance.

Here are some general attributes that apply to all components.

For alignment, which adjusts the component position within the container.
```
justify-center
justify-left
justify-right
```

### Container

All components are wrapped in a `gurulab-component-container` div which is mainly for spacing (done on the container) and alignment (done on the child).

```html
<div class="gurulab-component-container --attributes--">
  <!-- Component Here -->
</div>
```

Attributes
```md
margin-top-1rem
margin-bottom-1rem
```

## Buttons

GuruLab buttons are pill-shaped and are defined by the `gurulab-button` CSS class.

The button component applied on an `anchor` element.
```html
<a class="gurulab-button --attributes--">Sign Up Now</a>
```

The button component on a `button` element.
```html
<button class="gurulab-button --attributes--">Sign Up Now</button>
```

Attributes:
```
bg-dark
bg-light
size-default
size-large
color-orange
color-teal
```