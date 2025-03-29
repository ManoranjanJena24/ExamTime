## display inline simply means jeetne kee requirement hai utnaa hee space capturee karraa hai
## block is covering whole area jooo uskee dayree mein aaraa hai 
## display none uss cheez koo hee gayab karr degaa 


# Default `display` Property in CSS

In CSS, different HTML elements have different default `display` properties. Below is a list of common defaults:

## Block-Level Elements (`display: block;`)

These elements take up the full width available and start on a new line:

- `div`
- `p`
- `h1` to `h6`
- `section`
- `article`
- `header`
- `footer`

## Inline Elements (`display: inline;`)

These elements do not start on a new line and only take up as much width as needed:

- `span`
- `a`
- `strong`
- `em`
- `img` (though it behaves slightly differently)

## Inline-Block Elements (`display: inline-block;`)

These behave like inline elements but can have width and height:

- `button`
- `input`

## Table Elements

Some elements behave like table-related elements by default:

- `table` → `display: table;`
- `tr` → `display: table-row;`
- `td` → `display: table-cell;`

## Overriding Default Display Values

You can always override an element’s default `display` property using CSS. For example:

```css
span {
    display: block;
}
```

This will make a `span` behave like a block element instead of an inline element.  

---

Let me know if you need any modifications! 🚀