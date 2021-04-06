# SCSS Utils

A compact bundle of SCSS helpers covering breakpoints, vendor prefixing, z-index maps, typography sizing, and intrinsic ratios.

## Install
```sh
npm install scss-utils
```

## Usage
```scss
@import "scss/index";

.card {
  @include breakpoint(medium) {
    @include text-size(body, medium);
  }
}
```

## Included
- `mixins/_mixin--breakpoints.scss`
- `mixins/_mixin--vendor.scss`
- `mixins/_mixin--z-index.scss`
- `mixins/_mixin--typography.scss`
- `libs/_tools.scss`

## License
See `LICENSE`.
