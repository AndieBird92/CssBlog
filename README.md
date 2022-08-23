# CssBlog - Mafalda

This is a CSS Project

## HTML DOM Tree

DOM Tree representation

```
html
+-- body
    +-- header
        +-- h1
        +-- svg
        +-- nav
            +-- ul
                +-- li (*3) [article, grid, contacts]
                    +-- a [#link-to-section]

    +-- main
        +-- article
            +-- h2 [lorem]
            +-- fig
                +-- img
                +-- figcaption
            +-- p [blog text]

        +-- aside
            +-- article (*3) [wrapped in link]
                +-- a [link_to_blog]
                    +-- title
                    +-- img

    +-- footer
        +-- ul [contact] (*4)
            +-- li > a > svg [fb]
            +-- li > a > svg [insta]
            +-- li > a > svg [twitter]
            +-- li > a > svg [email]
        +-- p [copyright]
```

## Other stuff
