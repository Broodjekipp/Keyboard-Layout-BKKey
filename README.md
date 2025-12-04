# BKKey Keyboard Layout

A modified US-International keyboard layout for Windows that makes typing dead keys easier while keeping accents accessible.

## Features

In the standard US-International layout, keys like `'`, `"`, `` ` ``, `~`, and `^` are "dead keys" that modify the next character you type. This layout moves those dead key functions to **Alt Gr** combinations, making the keys behave normally by default.

**Examples:**
- Type `é` by pressing **Alt Gr + '** then **e**
- Type `'` by simply pressing the **'** key (no need for space or double-press)

This gives you easy access to accented characters while keeping standard punctuation quick to type.

## Installation

1. Download and install [Microsoft Keyboard Layout Creator (MSKLC)](https://www.microsoft.com/en-us/download/details.aspx?id=102134)
2. Open the `.klc` file with **Ctrl + O** in MSKLC
3. Go to **Project > Build DLL and Setup Package**
4. Navigate to the generated `setup` folder
5. Run `setup.exe`
6. The keyboard layout will now be available in Windows Settings under **Time & Language > Language > Keyboard**
