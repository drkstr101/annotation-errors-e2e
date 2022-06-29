# Stackbit MUI Next.js Starter

A simple starting point for a Stackbit project that includes support for [MUI](https://mui.com/).

## Getting started

0. Ensure `node --version` is 14.x and `npm --version` is 6.x

1. checkout the project and install node_modules:

   ```sh
   git checkout --recurse-submodules https://github.com/stackbit/annotation-errors-e2e.git
   cd annotation-errors-e2e
   yarn
   ```

   (if yarn cannot be found, first run `npm i -g yarn`)

2. Open up two command-line prompts in this directory.
   a. In the first one run `yarn dev`
   b. In the second terminal run `yarn stackbit-dev`

This will open Stackbit in your browser in local dev mode. Refer to the second
command line for reported annotation errors. If this command is run in vscode or WebStorm then the sourcemap links will be navigable.

## List of errata

1. Header
   - Missing title annotation
   - `navLinks` should be `.navLinks`
2. Footer
   - Incorrect parent field path (missing `:footer` at the end)

### Original Output

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

