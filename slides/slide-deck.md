---
title: "Demo"
description: "Demo POLIMI Marp Template"
class: invert
_class:
  - invert
  - lead
footer: Date | Author Name | Presentation Title
_footer: ""
paginate: true
theme: polimi
_paginate: false
marp: true
---

# POLIMI Marp Slides Template

Chair of Media Technology
Politecnico di Milano

Author Name

---

## Outline

- Marp Header
- Light Theme
- Bullet Points
- Tables
- Images
- Code
- References

---

## Marp Header

```yml
title: Demo
description: Demo POLIMI Marp Template
class: invert                               # Dark theme all slides (remove to use light theme)
_class:                                     # First slide
  - invert                                  # Dark theme for title slide
  - lead                                    # Title slide style
footer: Presentation Title | Author Name    # Slide footer
_footer: ""                                 # No footer on title slide
paginate: true                              # Page numbers
_paginate: false                            # No page numbers on title slide
marp: true                                  # Nice preview for the VS Code extension
```

---

<!-- _class: lead -->
<!-- _footer: "" -->
<!-- _paginate: "" -->

# Light Theme

---

<!-- _class: -->

# Light Theme Slide

---

## Bullet Points

- Show all
- at once
* or one
* by one

---

## Tables

| Header | Header |
| ------ | ------ |
| Text   | Text   |

---

## Images

![](./images/POLIMI_logo_white.svg)

---

## Background Images

- Full Size

![bg right](./images/POLIMI_logo_white.svg)

---

## Background Images Customized

- 60% slide width
- 80% image size

![bg right:60% 80%](./images/POLIMI_logo_white.svg)

---

## Code

```cpp
#include <iostream>

int main(int /*argc*/, char** /*argv*/)
{
    std::cout << "Code with syntax highlighting!" << std::endl;

    return EXIT_SUCCESS;
}

```

---

## References

- [Get Started](https://github.com/marp-team/marp)
- [Documentation](https://marpit.marp.app/)
- [CLI](https://github.com/marp-team/marp-cli)
