#  Very Simple Flexbox Notes

## Turn on Flexbox

```css
.container {
  display: flex;
}
```

---

## Row or Column

```css
.container {
  flex-direction: row; /* left to right */
  /* or */
  flex-direction: column; /* top to bottom */
}
```

---

## Center Items

```css
.container {
  display: flex;
  justify-content: center; /* left/right */
  align-items: center; /* up/down */
}
```

---

## Space Between Items

```css
.container {
  display: flex;
  justify-content: space-between;
}
```

---

## Make Items Equal Size

```css
.item {
  flex: 1;
}
```

---

## Allow Wrapping

```css
.container {
  display: flex;
  flex-wrap: wrap;
}
```

---

#  Remember

- `display: flex;` → start flexbox
- `justify-content` → main direction
- `align-items` → other direction
- `flex: 1;` → equal space
