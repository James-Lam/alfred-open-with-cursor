# alfred-open-with-cursor

An Alfred workflow for opening code folders with Cursor, the AI-powered code editor.
![Alfred Open with Cursor Workflow](alfred-open-with-cursor.png)

## Description

This Alfred workflow allows you to quickly open your code folders in Cursor directly from Alfred. It streamlines your development workflow by providing a fast and efficient way to access your projects.

## Installation

1. Download the latest release of the workflow from the [releases page](https://github.com/yourusername/alfred-open-with-cursor/releases).
2. Double-click the downloaded file to install it in Alfred.

## Usage

1. Open Alfred (usually with a keyboard shortcut like `Option + Space`).
2. Type `cursor` followed by a space.
3. Start typing the name of the folder you want to open.
4. Select the desired folder from the list of results.
5. Press `Enter` to open the selected folder in Cursor.

## Configuration

By default, the workflow searches for folders in your home directory. To change the search location:

1. Open Alfred Preferences.
2. Go to the Workflows tab.
3. Find the "Open with Cursor" workflow.
4. Double-click the "File Filter" object.
5. Select the "Scope" tab.
6. Modify the "Search Scope" to change the search path.

## Requirements

- Alfred 4 or later with Powerpack
- Cursor installed on your Mac

## Support

If you encounter any issues or have suggestions for improvements, please open an issue on the [GitHub repository](https://github.com/yourusername/alfred-open-with-cursor/issues).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

This project was inspired by [alfred-open-with-vscode](https://github.com/iamstevendao/alfred-open-with-vscode) by Steven Dao. Thanks for the great work!

## Troubleshooting

### Issue: Alfred and Spotlight Cannot Search Certain Files and Directories

If you encounter a problem where Alfred and Spotlight are unable to search some files and directories, especially after transferring data from an old Mac or restoring from a Time Machine backup, you can try the following solutions:

1. **Rebuild the Spotlight Index:**

   - Follow the instructions provided by Apple to rebuild the Spotlight index: [Rebuild the Spotlight index on your Mac](https://support.apple.com/en-sg/102321).

2. **Use Alfred's Built-in Rebuild Index Feature:**
   - Open Alfred Preferences.
   - Go to the "Advanced" tab.
   - Click on "Rebuild macOS Metadata" to use Alfred's built-in feature to rebuild the index.

These steps should help resolve the issue and restore the search functionality for your files and directories.
![Alfred's Built-in Rebuild Index Feature](rebuild-index.png)
