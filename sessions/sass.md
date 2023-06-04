# Sass
Sass is a preprocessor scripting language that is interpreted or compiled into Cascading Style Sheets. Why learning Sass? It lets you use variables, mathematical operations, mixins, loops, functions, imports, and other interesting functionalities that make writing CSS much more powerful.

Official website: [Sass - Syntactically Awesome Stylesheet](https://sass-lang.com)

## Goal of learning
By completing this tutorial, you will be able to understand:
- Sass basics
- Sass variable
- Sass nest
- Sass import
- Sass mixin
- Sass extend
- Sass calculations

## Learning materials
### Learn Sass
Watch below Video to understand the basics of Sass:

[![Sass Crash Course](https://img.youtube.com/vi/Zz6eOVaaelI/0.jpg)](https://www.youtube.com/watch?v=Zz6eOVaaelI)

We extracted the key takeaways of the above tutorial and summarized them below:

#### Basics
- Two syntax, Sass: nesting syntax, SCSS: CSS like syntax
- Sass compiler compiles Sass/SCSS into regular CSS

#### Features
- Variable
```scss
$primaryBtn: rgb(56, 146, 142) ;

header button {
	background: $primaryBtn;
}
```

- Nest
```scss
$primaryBtn: rgb(56, 146, 142) ;

header button {
	background: $primaryBtn;
}
```

- Import
```scss
# _header.scss

@import "./header";
```

- Mixin
```scss
# _header.scss

@import "./header";

```

- Extend
```scss
# _header.scss

@import "./header";
```

- Calculations
```scss
header {
	width: 100% - 20%;
}
```