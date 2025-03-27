# ChatWise PopClip Extension Project

This is a plugin project developed for [PopClip](https://www.popclip.app/), a macOS utility that shows a popup menu when you select text.

## Project Purpose

This project aims to develop a PopClip extension that provides the following features:

1. When users select any text, PopClip toolbar displays ChatWise-related action buttons
2. Clicking the button automatically opens the ChatWise application and sends the selected text for processing

## Project Structure

```
chatwise-hybrid.popclipext/
├── Config.yaml      # Extension configuration file
└── README.md        # Documentation
```

## Technical Details

- Developed using PopClip's extension mechanism
- Communicates with ChatWise application via URL Scheme
- Uses hardcoded prompt parameters to ensure proper Chinese text transmission

## Development Status

The project is currently in development, focusing on:
- Ensuring proper handling of Chinese text
- Optimizing user experience