# PowerAutomate JSON Action Renamer

This project is a web-based tool for renaming actions within a JSON definition used in PowerAutomate. It allows users to load JSON, rename actions individually or in bulk, and copy the updated JSON to the clipboard.
The page is available at: [https://lucashahne.github.io/PA-Formatter-JSON/](https://lucashahne.github.io/PA-Formatter-JSON/)

## Demo

![image](https://github.com/LucasHahne/PowerAutomateJSONFormatter/assets/63300977/dc52453f-4566-41b5-89f6-22e793694f2e)

## Features

- **Load Actions:** Load JSON data to extract and display action names.
- **Rename Actions:** Rename individual actions or update all actions at once.
- **Copy to Clipboard:** Copy the updated JSON to the clipboard with a single click.
- **Success Notification:** Display a success popup notification when the JSON is copied to the clipboard.

## Usage

### Get your scope
1. move zour code inside a scope inside zour PowerAutomate Flow.
2. Copy the scope to your clipboard and paste it inside the input textarea

### Load Actions

1. Paste your JSON into the "Paste your JSON here" textarea.
2. Click the "Load Actions" button to display a list of actions extracted from the JSON.

### Rename Actions

- **Rename Single Action:**
  1. Enter the new name in the text field next to the action you want to rename.
  2. Click the "Rename Single" button to update the action name in the JSON.

- **Update All Actions:**
  1. Enter the new names for all actions in their respective text fields.
  2. Click the "Update All" button to update all action names in the JSON.

### Copy Updated JSON

1. Click the "Copy JSON to Clipboard" button to copy the updated JSON to the clipboard.
2. A success popup notification will appear at the top of the page, confirming the JSON has been copied.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/json-action-renamer.git
