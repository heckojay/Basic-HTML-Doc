## Troubleshooting

| Issue | Cause | Solution |
|------|-------|----------|
| Images not showing | Incorrect file path or file name mismatch | Ensure the [file path](glossary.md#file-path) matches exactly. Check that the image is inside your project folder, the file name matches (including capitalization), and the `src=` attribute has no extra spaces. |
| Live Server not working | Extension not installed or file not saved | Install the **Live Server** extension by **Ritwick Dey** in VS Code. Then save your file and right-click `index.html`, and select **Open with Live Server**. |
| Changes not appearing | File not saved or browser not refreshed | **Press** `Ctrl + S` to save your file. If the page does not update, refresh your browser. |
| Cannot find my folder | File location unknown | Open **File Explorer**, use the search bar in the top-right, and search for your folder name. Once found, right-click it and select **Open File Location**. |
| CSS not applying | CSS file not linked or incorrect selector | Ensure your CSS file is linked using `<link rel="stylesheet" href="style.css">`. Check that the file name matches and that your selector (e.g., `h1`, `.class`) is correct. |