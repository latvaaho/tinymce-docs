## allow_unsafe_link_target

By default all links with a `target` of *_blank* will get a `rel` attribute of `noopener noreferrer`. This will disable access to the `window.opener` object from a child tab/window that will open on click. If this is not something you care about, you can disable this option, by setting it to *false*. Although **we do not recommend** you to do so!

**Type:** `Boolean`

**Default Value:** `false`

**Possible Values:** `true`, `false`

##### Example

```js
tinymce.init({
  selector: 'textarea',
  allow_unsafe_link_target: true
});
```
