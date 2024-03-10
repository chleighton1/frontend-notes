# Frontend Notes

## CSS

```
img: {
	Display: block;
	Max-width: 100%;
}
```

^^ This is a way to set images so they don’t overflow and are naturally more responsive

It is also a good Idea to set min-height and max-width for elements. You can set max-width and `margin-inline: auto` to keep things centered.

Don't delcare things you do not need! Ex: `width: 100vh` `height: 100vh` (default is auto). 

`flex-wrap: wrap` is useful for overflowing flex items rather than media queries 

For grid, you can try `grid-template-columns: repeat(auto-fit, minmax())`