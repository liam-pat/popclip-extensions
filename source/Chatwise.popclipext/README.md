# ChatWise PopClip Extension

A simple PopClip extension to send selected text to the ChatWise app for processing.

## Features

Select any text, click the PopClip menu button, and the ChatWise app will open with your text. You can choose between:

- Default ChatWise processing
- Translate to English (uses the translate2English prompt)

## How It Works

When you select text in any application, PopClip displays a small toolbar. Clicking the ChatWise button will:

1. Capture your selected text
2. Open the ChatWise app
3. Send your text to ChatWise for processing using the specified prompt

## Requirements

- [PopClip](https://www.popclip.app/) must be installed
- [ChatWise app](https://chatwise.app) must be installed
- For translation functionality, you need to have the corresponding prompts set up in ChatWise

## Installation

1. Download the extension file from dir extensions ( or `zip -r ChatWise.popclipextz Chatwise.popclipext | cat`)
2. Double-click the file
3. PopClip will prompt you to install the extension
4. Click "Install"

## Technical Details

This extension uses hardcoded prompt parameters in the URL to ensure proper handling of Chinese text. Testing showed that variable prompt parameters can cause issues with Chinese text transmission. 