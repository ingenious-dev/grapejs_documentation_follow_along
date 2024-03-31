`getting_started/11_theming.html` was used as the starting/reference code for files in `modules/components_and_js`. This is because it has because its editor allows viewing of `traits`.

To understand why the relevant code snippets have been moved to the editor definition. See the disclaimer presented in https://grapesjs.com/docs/modules/Components.html#define-custom-component-type

```sh
const myNewComponentTypes = editor => {
  editor.DomComponents.addType(/* API for component type definition */);
};

const editor = grapesjs.init({
  container : '#gjs',
  // ...
  plugins: [ myNewComponentTypes ],
});
```

The snippets have been left in their spots as in the documentation but commented out in favour of the pattern mentioned above