# Bacularis themes

This repository contains color themes for the Bacularis web interface and
the Bacularis API panel.

The files in this repository are part of Bacularis.

## Installation

### Step 1 - select theme

In the directories with the ``theme-`` prefix you can find Bacularis themes,
one theme per one directory.

Find the directory with theme you want to install.

### Step 2 - install theme

Copy the selected theme files to Bacularis. The command form can be the following:

```
cp ./theme-{SELECTED_THEME_NAME}/* {PROJECT_DIR}/htdocs/themes/Baculum-v2/
```

where:

 * ``{SELECTED_THEME_NAME}`` - is the theme name
 * ``{PROJECT_DIR}`` - is the main Bacularis directory.

If you installed Bacularis using binary packages, for example for the theme
named ``Lumberjack's dram`` this is the following command:

```
cp ./theme-lumberjacks-dream/* /usr/share/bacularis/htdocs/themes/Baculum-v2/
```

### Step 3 - refresh page

Refresh the web interface page to see the result. We recommend to use for that
the ``CTRL+SHIFT+R`` keyboard shortcut which refreshes the page with clearing the
web browser page cache.

