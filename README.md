# SCSS BEM Support

This extension adds TextMate scope to BEM element and modifier which can be useful in syntax highlighting.

![screenshot](https://raw.githubusercontent.com/joloyonaha/scss-bem-support/master/assets/screenshot-v0.0.5.png)

## BEM – Block Element Modifier

```scss
.block {
  &__element {} // bem.support.element.scss
  &--modifier {} // bem.support.modifier.scss
}
```

More info about BEM [here](http://getbem.com/).

## TextMate Scope

Go to `Keyboard Shortcuts` then search for `Developer: Inspect TM Scopes`.

## Changelog

**v0.0.6**
- Preserve ampersand tokenization
- Capture dash, underscore, letters and numbers only

**v0.0.5**
- Add `entity.other.attribute-name.class.css` as fallback scope

**v0.0.4**
- Add `bem.support.element.scss` scope
- Add `bem.support.modifier.scss` scope

**v0.0.3**
- Initial release

## Feedback

For comments, questions and suggestions, go [here](https://github.com/joloyonaha/scss-bem-support/issues).

## Contributors

- Danny McGee - [@dannymcgee](https://github.com/dannymcgee)

## License

© 2019 [Jolo Yonaha](https://github.com/joloyonaha)  
[MIT License](https://github.com/joloyonaha/scss-bem-support/blob/master/LICENSE)
