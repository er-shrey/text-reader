# Text Reader

A minimal single-page HTML tool that lets you pick a local file and read its text contents directly in the browser (no upload, no server) using the File API and `FileReader`.

## Tech stack

- Plain HTML + inline JavaScript (no dependencies, no build step)

## Files

- `import.html` — the entire app: a file picker input and a `<textarea>` that gets filled with the selected file's text content

## Running

No installation needed — just open the file in a browser:

```bash
open import.html
```

Click "Specify a file", choose any text file, and its contents will appear in the textarea below.
