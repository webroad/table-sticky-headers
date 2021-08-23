# table sticky headers
Sticky headers that works (horizontally &amp; vertically) - CSS only

Try demo on https://webroad.pl/demo/table-sticky-headers/ 

## vertical scroll - horizontal sticky header

```css
table thead th {
    position: sticky;
    top: 0;
    z-index: 10;
    box-shadow: 0 1px 3px rgba(0, 0, 0, 0.2);
}
```

![vertical scroll - horizontal sticky header](https://github.com/webroad/table-sticky-headers/blob/main/sticky-horizontal-table-header.gif?raw=true)

## horizontal scroll - vertical sticky header

```css
table tbody th[scope=row] {
    position: sticky;
    left: 0;
    z-index: 9;
    box-shadow: 1px 0 3px rgba(0, 0, 0, 0.2);
}
```

![horizontal scroll - vertical sticky header](https://raw.githubusercontent.com/webroad/table-sticky-headers/main/sticky-vertical-table-header.gif?raw=true)

## Can I use?
[Yes.](https://caniuse.com/css-sticky)
