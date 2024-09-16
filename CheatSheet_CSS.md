# CSS Selector Cheat Sheat

## Basic Selectors

### Universal Selector
```css
* {
  /* Applies to all elements */
}
```

### Type Selector
```css
p {
  /* Applies to all <p> elements */
}
```

### Class Selector
```css
.classname {
  /* Applies to all elements with the specified class */
}

.container {
  /* Applies to all elements with class "container" */
}
```

### ID Selector
```css
#idname {
  /* Applies to the element with the specified ID */
}

#header {
  /* Applies to the element with ID "header" */
}
```

### Attribute Selector
```css
[attribute="value"] {
  /* Applies to elements with a specific attribute value */
}

input[type="text"] {
  /* Applies to all <input> elements with type "text" */
}
```

### Descendant Selector
```css
ancestor descendant {
  /* Applies to all descendant elements of a specific ancestor */
}

div p {
  /* Applies to all <p> elements inside a <div> */
}
```

### Child Selector
```css
parent > child {
  /* Applies to direct children of a specific parent */
}

ul > li {
  /* Applies to all <li> elements that are direct children of <ul> */
}
```