# Simple AI Functions for Excel

This add-in enables you to use AI functions directly within Excel cells.

## Installation

1. Open Excel.
2. Select **Home** > **Add-ins**, then select **More Settings**.
3. On the **Office Add-ins** dialog, select **Upload My Add-in**.
4. **Browse** to the add-in `manifest.xml` file, and then select **Upload**.

### See also

[Sideload Office Add-ins to Office on the web](https://learn.microsoft.com/en-us/office/dev/add-ins/testing/sideload-office-add-ins-for-testing)


## How to Use

1. Select **Simple AI Functions for Excel**, then select **Settings**
2. Enter the required prompt and parameters.
3. Use AI_* like the followings.
   - `=AI_AZURE("test")`
   - `=AI_OPENAI("tell me" & A1)`
   - `=AI_GEMINI("tell me" & A1 & " and " & A2)`
   - `=AI_CLAUDE("hello")`
   - ...

## ☕ Support

If you find this add-in useful, consider supporting me:
[Buy me a coffee ☕](https://coff.ee/1junh)
