# personal website
personal portfolio + technical blog built with hugo.
hugo theme: *hugo-xmin* by yihui xie

## quick commands

deploy dev server:

```bash
hugo server
```

compile static site:

```bash
hugo
```
---


## where stuff goes

### creating a new blog post

create:

```txt
content/posts/
```

example:

```txt
content/posts/dx12-week-1.md
```

---

### images

place in:

```txt
static/images/
```

access in markdown:

```md
![dx12 screenshot](/images/dx12-swapchain.png)
```

---

### modify website layout / html

(this will override theme behavior)
edit:

```txt
layouts/
```

---

### site configuration

edit:

```txt
hugo.toml
```

used for:
- site title
- menus
- theme
- social links
- base url
- params

---

### theme styling

usually lives inside:

```txt
themes/
```

try to override in:

```txt
layouts/
```

instead of modifying theme files directly.

this will make updates easier.

---

## notes to future me

- `public/` is generated; don't manually edit it.
- `content/` = actual writing/content.
- `layouts/` = html customization.
- `static/` = files copied directly.
- `themes/` = theme internals.
- if something looks visually broken, check `layouts/` first.
