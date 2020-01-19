# beltpack
A loose assortment of mixins I've found useful.



## Setup
Beltpack needs the following:

### Breakpoints

A number of Beltpack functions generate CSS that includes breakpoints. Beltpack needs the breakpoints to be contained in a Sass map, 
as follows:

```
$breakpoints: (
	"small": 40em,
	"medium": 55em,
	"large": 70em
);
```

The map must be called `$breakpoints`. The labels and specific breakpoints are up to you, and you can specify as many or little as you need.
