
Use schematic to add Angular Material

```
ng add @angular/material
```

- Choose a prebuilt theme name, or "custom" for a custom theme: **Indigo/Pink**
- Set up global Angular Material typography styles? **Yes**
- Set up browser animations for Angular Material? **Yes**

```
ng g module shared
```

```
ng g module shared/material
```

Remove CommonModule import and from the imports array.
Remove *declarations* and *imports* arrays.
Add an *exports* array.

Import 

`import {MatButtonModule} from '@angular/material/button';`

Add MatButtonModule to *exports* array.

```js
exports: [
  MatButtonModule
]
````

Import MaterialModule into SharedModule and add to imports and exports arrays.

Import SharedModule into SharedModule and add to imports and exports arrays.



I

