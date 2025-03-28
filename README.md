# PopClip Extension Project

This is a plugin project developed for [PopClip](https://www.popclip.app/), a macOS utility that shows a popup menu when you select text.

## Project Purpose

This project aims to develop a PopClip extension that provides the following features:

1. When users select any text, PopClip toolbar displays Mac app-related action buttons
2. Clicking the button automatically opens the related application and sends the selected text for processing

## Project Structure

```
source/Chatwise.popclipext/
├── Config.yaml     
└── README.md        

extensions/
├── ChatWise.popclipext  # download to install
```

## Technical Details

- Developed using PopClip's extension mechanism
- Communicates with related application via URL Scheme

## Development Status

The project is currently in development
- chatwise (done, can be customed)