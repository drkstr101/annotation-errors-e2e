# Stackbit MUI Next.js Starter

A simple starting point for a Stackbit project that includes support for [MUI](https://mui.com/).

## Features

This is meant to be a simple test of annotations validation and reporting system.



## List of erata

1. Header
    - Missing title annotation
    - `navLinks` should be `.navLinks`
2. Footer
    - Incorrect parent field path (missing `:footer` at the end)

Result: (0.2.27)

```
error: Found 22 annotation errors
error: AnnotationError: Field path navLinks not found or does not match content schema (/html/body[1]/div[1]/div[1]/div[1]/header[1]/div[1]/nav[1])
error: AnnotationError: Field path header.0 not found or does not match content schema (/html/body[1]/div[1]/div[1]/div[1]/header[1]/div[1]/nav[1]/a[1])
error: AnnotationError: Field path header.0.url not found or does not match content schema (/html/body[1]/div[1]/div[1]/div[1]/header[1]/div[1]/nav[1]/a[1])
error: AnnotationError: Field path header.label not found or does not match content schema (src/components/atoms/Link.tsx:18)
error: AnnotationError: Field path header.1 not found or does not match content schema (/html/body[1]/div[1]/div[1]/div[1]/header[1]/div[1]/nav[1]/a[2])
error: AnnotationError: Field path header.1.url not found or does not match content schema (/html/body[1]/div[1]/div[1]/div[1]/header[1]/div[1]/nav[1]/a[2])
error: AnnotationError: Field path header.label not found or does not match content schema (src/components/atoms/Link.tsx:18)
error: AnnotationError: Field path header.2 not found or does not match content schema (/html/body[1]/div[1]/div[1]/div[1]/header[1]/div[1]/nav[1]/a[3])
error: AnnotationError: Field path header.2.url not found or does not match content schema (/html/body[1]/div[1]/div[1]/div[1]/header[1]/div[1]/nav[1]/a[3])
error: AnnotationError: Field path header.label not found or does not match content schema (src/components/atoms/Link.tsx:18)
error: AnnotationError: Field path content/data/config.json not found or does not match content schema (/html/body[1]/div[1]/div[1]/div[1]/footer[1])
error: AnnotationError: Field path navLinks not found or does not match content schema (/html/body[1]/div[1]/div[1]/div[1]/footer[1]/nav[1])
error: AnnotationError: Field path 0 not found or does not match content schema (/html/body[1]/div[1]/div[1]/div[1]/footer[1]/nav[1]/a[1])
error: AnnotationError: Field path 0.url not found or does not match content schema (/html/body[1]/div[1]/div[1]/div[1]/footer[1]/nav[1]/a[1])
error: AnnotationError: Field path label not found or does not match content schema (src/components/atoms/Link.tsx:18)
error: AnnotationError: Field path 1 not found or does not match content schema (/html/body[1]/div[1]/div[1]/div[1]/footer[1]/nav[1]/a[2])
error: AnnotationError: Field path 1.url not found or does not match content schema (/html/body[1]/div[1]/div[1]/div[1]/footer[1]/nav[1]/a[2])
error: AnnotationError: Field path label not found or does not match content schema (src/components/atoms/Link.tsx:18)
error: AnnotationError: Field path 2 not found or does not match content schema (/html/body[1]/div[1]/div[1]/div[1]/footer[1]/nav[1]/a[3])
error: AnnotationError: Field path 2.url not found or does not match content schema (/html/body[1]/div[1]/div[1]/div[1]/footer[1]/nav[1]/a[3])
error: AnnotationError: Field path label not found or does not match content schema (src/components/atoms/Link.tsx:18)
error: AnnotationError: Field path copyrightText not found or does not match content schema (src/components/atoms/Markdown.tsx:9)
```

Result: (0.2.28)

```
error: Found 22 annotation errors
error: AnnotationError: Field path navLinks not found or does not match content schema (/html/body[1]/div[1]/div[1]/div[1]/header[1]/div[1]/nav[1])
error: AnnotationError: Field path header.0 not found or does not match content schema (/html/body[1]/div[1]/div[1]/div[1]/header[1]/div[1]/nav[1]/a[1])
error: AnnotationError: Field path header.0.url not found or does not match content schema (/html/body[1]/div[1]/div[1]/div[1]/header[1]/div[1]/nav[1]/a[1])
error: AnnotationError: Field path header.label not found or does not match content schema (src/components/atoms/Link.tsx:18)
error: AnnotationError: Field path header.1 not found or does not match content schema (/html/body[1]/div[1]/div[1]/div[1]/header[1]/div[1]/nav[1]/a[2])
error: AnnotationError: Field path header.1.url not found or does not match content schema (/html/body[1]/div[1]/div[1]/div[1]/header[1]/div[1]/nav[1]/a[2])
error: AnnotationError: Field path header.label not found or does not match content schema (src/components/atoms/Link.tsx:18)
error: AnnotationError: Field path header.2 not found or does not match content schema (/html/body[1]/div[1]/div[1]/div[1]/header[1]/div[1]/nav[1]/a[3])
error: AnnotationError: Field path header.2.url not found or does not match content schema (/html/body[1]/div[1]/div[1]/div[1]/header[1]/div[1]/nav[1]/a[3])
error: AnnotationError: Field path header.label not found or does not match content schema (src/components/atoms/Link.tsx:18)
error: AnnotationError: Field path content/data/config.json not found or does not match content schema (/html/body[1]/div[1]/div[1]/div[1]/footer[1])
error: AnnotationError: Field path navLinks not found or does not match content schema (/html/body[1]/div[1]/div[1]/div[1]/footer[1]/nav[1])
error: AnnotationError: Field path 0 not found or does not match content schema (/html/body[1]/div[1]/div[1]/div[1]/footer[1]/nav[1]/a[1])
error: AnnotationError: Field path 0.url not found or does not match content schema (/html/body[1]/div[1]/div[1]/div[1]/footer[1]/nav[1]/a[1])
error: AnnotationError: Field path label not found or does not match content schema (src/components/atoms/Link.tsx:18)
error: AnnotationError: Field path 1 not found or does not match content schema (/html/body[1]/div[1]/div[1]/div[1]/footer[1]/nav[1]/a[2])
error: AnnotationError: Field path 1.url not found or does not match content schema (/html/body[1]/div[1]/div[1]/div[1]/footer[1]/nav[1]/a[2])
error: AnnotationError: Field path label not found or does not match content schema (src/components/atoms/Link.tsx:18)
error: AnnotationError: Field path 2 not found or does not match content schema (/html/body[1]/div[1]/div[1]/div[1]/footer[1]/nav[1]/a[3])
error: AnnotationError: Field path 2.url not found or does not match content schema (/html/body[1]/div[1]/div[1]/div[1]/footer[1]/nav[1]/a[3])
error: AnnotationError: Field path label not found or does not match content schema (src/components/atoms/Link.tsx:18)
error: AnnotationError: Field path copyrightText not found or does not match content schema (src/components/atoms/Markdown.tsx:9)
```