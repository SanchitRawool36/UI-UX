# Labrador Walking Loader (CSS-only)

CSS-only loader: a friendly light-brown Labrador walking.

## How to preview locally

Open `index.html` in your browser.

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



## Customization

- Size: adjust `--size` in `:root`.
- Colors: tweak `--dog`, `--dog-shade`, `--nose`, `--eye`.
- Speed: change animation durations for `paceFront`, `paceBack`, `tailWag`, and `headBob`.

## License

Public domain / no attribution required.
