# PopClip Extension

Extra PopClip extension to send selected text to the ChatWise app for processing.

[Extensions Market](https://www.popclip.app/extensions/x/nhfcp3)

## Features

Select any text, click the PopClip menu button, and the ChatWise app will open with your text. You can choose between:

- Default ChatWise processing
- Translation (uses the transaction prompt)

## How It Works

When you select text in any application, PopClip displays a small toolbar. Clicking the ChatWise button will:

1. Capture your selected text
2. Open the ChatWise app
3. Send your text to ChatWise for processing using the specified prompt

## Requirements

- [PopClip](https://www.popclip.app/) must be installed
- [ChatWise](https://chatwise.app) must be installed
- For translation functionality, you have to setup **prompts** named **transaction** in ChatWise

## How To Pack

- rename the dir to `{PLUGIN-NAME}.popclipext`
- reveal in the Finder and then open  `{PLUGIN-NAME}.popclipext`

## Installation

1. download the extension file from `extensions`
2. unzip `zip -r ChatWise.popclipextz Chatwise.popclipext | cat`
3. open the file
4. click `Install`

## Technical Details

This extension uses hardcoded prompt parameters in the URL to ensure proper handling of Chinese text. Testing showed that variable prompt parameters can cause issues with Chinese text transmission.

- [ChatWise](https://docs.chatwise.app/open-from-other-apps.html)
    - input (Content)
    - prompt (Prompt ID)
    - assistant (Assistant ID)
    - model (AI model)
    - instruction (Instruction)
    - files (multiple files)

### Sample

chatwise://chat/5qvmm882v3?input={popclip text}&prompt=custom-transaction&model=openai-gpt-4o-mini