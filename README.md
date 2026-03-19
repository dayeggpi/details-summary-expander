# details-summary-expander
Obsidian plugin that will parse the details-summary html tags

# How to install
1. Create a `details-toggle` folder inside `\.obsidian\plugins\`
2. Copy the `main.js`, `manifest.json`, and `styles.css` inside it
3. Restart obsidian
4. Go to Settings > Community plugins > Toggle on `Details Toggle` from the installed plugins list
5. ...
6. Profit

# How to use
Whenever you will paste a content that has the following details-summary format:
```
<details>
<summary>Summary of what is below</summary>
Any sentence and markdown stuff

*   This is a text
*   This is a text
*   This is a text
</details>
```
It will be converted to the following (and look better): 
```
> [!NOTE]+ Summary of what is below
> Any sentence and markdown stuff
> 
> *   This is a text
> *   This is a text
> *   This is a text

```
