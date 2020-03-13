# **Variables**

***Variables are at the core of most—if not all—programming languages that ever existed. A `variable`, broadly speaking, is a storage location paired with an associated
identifier (aka a `variable name`). So a variable is basically made up of a key and a
value, the former being used to retrieve the latter.***

***When applied to Sass, variables give authors the ability to store bits of content so
that they can be reused throughout the stylesheets. This is especially handy for
colors: one can avoid having countless hues of the same color after a long time spent
working on a project. Variables can also be helpful for storing other types of content
such as font lists, maps of breakpoints, and default asset paths—presumably anything
that you may want to use multiple times across the stylesheet, particularly those
that could be updated at a later point.***


***A variable in Sass always starts with a dollar sign ($), whether you are using it for
assignment or retrieval. Directly next to the dollar sign comes the variable name,
which is usually made of latin characters, numbers and dashes, or underscores.
Actually, any character can be used as long as it is escaped if needed.***

![](img/1.png)

***For assignment, the variable name and its value are separated with a colon. Finally,
a semicolon ends the statement (in the SCSS version only):***

```sass

// Variable assignment
$my-variable: 42px;

// Variable usage
.foo {
width: $my-variable;
}
```

![](img/2.png)

## **Data Types**
***All values in Sass, or rather SassScript (the scripting language itself), are associated
to a specific data type. There are seven data types in SassScript:***

1. **string (e.g. "Hello world", kittens)**
1. **number (e.g. 42, 1337px)**
1. **color (e.g. hotpink, rgb(1, 33, 7), #BADA55)**
2. **Jump Start Sass■ list (e.g. (a, b, c), a b c)**
3. **map (e.g. (a: 1, b: 2))**
4. **bool (true or false)**
5. 

***Data types are a way for both Sass and those authoring content to know what kind
of operations and functions can be run on a specific value. As far as I can tell, all
programming languages use some form of typing.***

***For instance, we can perform mathematical operations with numbers and colors
(yes, colors!), but not strings. It is possible to run some specific functions on lists
and maps, but not on booleans and null values.***

***To know the type of a Sass variable, we use the type-of(..) built-in function. It
returns precisely one of the seven aforementioned types.***



## **Strings**
***The string data type has to be the most basic type there is since we use it in our
life so much, even outside of any computer-related activity. A string is nothing more
than a series of characters, such as Hello world!:***
```sass

```
```sass
```
```sass

```
```sass
```
## ****
******
```sass

```
```sass
```

## ****
******
```sass

```
```sass
```

## ****
******
```sass

```
```sass
```

## ****
******
```sass

```
```sass
```

## ****
******
```sass

```
```sass
```

## ****
******
```sass

```
```sass
```

## ****
******
```sass

```
```sass
```

## ****
******
```sass

```
```sass
```

## ****
******
```sass

```
```sass
```

## ****
******
```sass

```
```sass
```

## ****
******
```sass

```
```sass
```