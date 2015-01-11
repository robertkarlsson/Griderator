# Griderator

## About
A simple grid-generator for SASS

## Using
@import "griderator/griderator"

The griderator takes 3 arguments, prefix, number of columns, left margin

Example without prefix:

```
@include griderator("", 12, 20);
```

Example with prefix:

```
@include griderator("mobile", 12, 20);
```

Example in media query

```
@media screen and (min-width: 768px) {
@include griderator("tablet", 12, 20);
}
```
