---
Title: 'Go'
Description: 'Go (also referred to as Golang) is an open-source compiled programming language that was designed at Google and released to the public in 2012.'
Codecademy Hub Page: 'https://www.codecademy.com/catalog/language/go'
CatalogContent:
  - 'learn-go'
  - 'paths/computer-science'
---

**Go** (also referred to as "Golang") is an open-source compiled programming language that was designed at Google by Robert Griesemer, Rob Pike, and Ken Thompson. It had its initial release for the public in 2012.

Go features known concepts such as static typing, memory safety, garbage collection, and more. It was originally designed to write high performance networking and infrastructure-relevant systems. Nowadays, it's used for [cloud-based](https://www.codecademy.com/resources/docs/general/cloud-computing) or server-side apps, DevOps, [Artificial Intelligence (AI)](https://www.codecademy.com/resources/docs/general/artificial-intelligence), [Data Science](https://www.codecademy.com/resources/docs/general/data-science), and more. Go is known for its readability, simplicity, shallow learning curve, and great performance.

It may seem not much to worry about a string but to use them well requires understanding not only how they work, but also the difference between a byte, a character, and a rune, the difference between Unicode and UTF-8, the difference between a string and a string literal, and other even more subtle distinctions.

In Go, strings are nothing but a read-only slice of bytes. Each and every character is represented by one or more byte in UTF-8 encoding.
Because of this, it can support any language in the world.

Strings with ` (backticks)` are called Raw String Literals and can span to multiple lines and and can contain anything except `backticks `
```
const s = `First line
Second line`
fmt.Println(s)
```
```
Output
First line
Second line
```

Raw string literals, delimited by backticks (back quotes), are interpreted literally. They can contain line breaks, and backslashes have no special meaning.

