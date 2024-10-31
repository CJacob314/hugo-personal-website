+++
date = '2024-10-30T19:57:41-05:00'
draft = true
title = 'Experimenting With Shortcodes'
summary = "Just testing the waters with Hugo a bit..."
menus = "home"
+++

# Rusty Rust-Rust Rustacians 🦀
```rust
fn main() {
    println!("Hello, World!");
}
```

# Math
{{< katex >}}
$$
    \varphi = \dfrac{1+\sqrt5}{2}= 1.6180339887…
$$

# Chart
{{< chart >}}
type: 'bar',
data: {
  labels: ['Tomato', 'Blueberry', 'Banana', 'Lime', 'Orange'],
  datasets: [{
    label: '# of votes',
    data: [12, 19, 3, 5, 3],
  }]
}
{{< /chart >}}
