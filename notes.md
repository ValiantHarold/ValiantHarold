## css

The svg element is not able to change between color for light and dark bc it is and img not svg.

I could use

```
background: none;
filter: invert(100%);
```

This will invert the image.

---

I could just load the images from [devicon](https://devicon.dev/) and use simple animations like transforms on the whole image and not the elements themselves.

---

css selectors that do not work as expected

```
gap: 5px;
```

```
svg:nth-child(n+1):nth-child(-n+10) {
   padding-bottom: 10px;
}
```
