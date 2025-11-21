# PopClip Extensions

This is a plugin developed for [PopClip](https://www.popclip.app/), macOS utility that shows a dialog when you select text.

## Project Purpose

This project aims to develop a PopClip extension that provides the following features:

1. When users select any text, PopClip toolbar displays Mac app-related action buttons.
2. Clicking the button automatically opens the related application and sends the selected text for processing

## Project Structure

```
source/
    ─ Chatwise.popclipext/
        ─ Config.yaml
        ─ README.md

extensions/
    - ChatWise.popclipext
```

## Technical Details

- Developed using PopClip's extension mechanism
- Communicates with related application via **URL Scheme**

## Development Status

- [chatwise](https://raw.githubusercontent.com/liam-pat/popclip-extensions/refs/heads/main/extensions/ChatWise.popclipextz) (done) 