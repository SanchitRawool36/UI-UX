# Labrador Walking Loader (CSS-only)

CSS-only loader: a friendly light-brown Labrador walking.

## How to preview locally

Open `index.html` in your browser.

## How to submit to uiverse.io

1. Go to https://uiverse.io/ and sign in.
2. Click Create (+) and choose a component type (Loader / Animated Icon).
3. In the HTML field, paste only the inner loader markup:

```html
<div class="loader">
  <div class="dog" role="img" aria-label="Walking labrador">
    <div class="dog-body">
      <div class="tail"></div>
      <div class="leg front left"></div>
      <div class="leg front right"></div>
      <div class="leg back left"></div>
      <div class="leg back right"></div>
    </div>
    <div class="dog-head">
      <div class="ear"></div>
      <div class="snout">
        <div class="nose"></div>
        <div class="tongue"></div>
      </div>
      <div class="eye"></div>
    </div>
  </div>
  <div class="ground">
    <span></span><span></span><span></span><span></span>
  </div>
</div>
```

4. In the CSS field, paste everything from `style.css`. Uiverse uses its own preview container, so page-level styles won’t leak.
5. Add a Title (e.g., "Labrador walking loader"), Description, and Tags (loader, dog, labrador, css, animation).
6. Submit. Optionally add a cover screenshot.

## Customization

- Size: adjust `--size` in `:root`.
- Colors: tweak `--dog`, `--dog-shade`, `--nose`, `--eye`.
- Speed: change animation durations for `paceFront`, `paceBack`, `tailWag`, and `headBob`.

## License

Public domain / no attribution required.
