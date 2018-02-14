---
title: "hello_world"
date: 2018-02-13T22:36:43+11:00
draft: true
---

This is my example post where I can test the styling for a bunch of HTML elements.

```rust
func main() {
	println!("Testing some rust code highlighting");
}
```

```html
<section id="main">
  <div>
    <h1 id="title">{{ .Title }}</h1>
    {{ range .Data.Pages }}
      {{ .Render "summary"}}
    {{ end }}
  </div>
</section>
```

Some final text.