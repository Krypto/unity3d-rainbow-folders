# Unity3D Rainbow Folders

Have you ever thought about highlighting often used project folders? This simple but colorful asset allows you to do that!

With "Rainbow Folders" you can set custom icon for any folder in unity project browser:

![Browser window example](https://raw.githubusercontent.com/PhannGor/phanngor.github.io/master/RainbowFolders/v0.2.1_01.png)

## Configuring folder icons

From the main menu select **Edit -> Rainbow Folders Settings**, then take a look at the Inspector.

There is reorderable list with few predefined "folder" items. You can modify existing items, remove them using "-" button or add new ones by clicking "+" button below.

![Rainbow folders inspector](https://raw.githubusercontent.com/PhannGor/phanngor.github.io/master/RainbowFolders/v0.2.1_02.png)


You can assign a custom icon to the folder using:
* Folder **Name** - name of the folder you want to change the icon for. Icon will be applied to all folders with the same name
* or folder **Path** - icon will be applied to a single folder. The path format: `Assets/SomeFolder/YourFolder`

Then you need to specify actually icons:
* **Small Icon** - your custom icon for the left panel of the project browser (16x16 px)
* **Large Icon**  - your custom icon for the right panel of the project browser (64x64 px)

Your changes will be applied next time when the project browser will retrieve the focus.

## Quick Colorize

You can also quickly colorize folders from context menu. To do so, right click on the folder in project browser, then select Rainbow **Folders -> Colorize -> Color**. Changes will be aplied immediately.

To reset the folder icon to default one, select **Rainbow Folders -> Colorize -> Revert to Default** from the same context menu.

![Rainbow folders inspector](https://raw.githubusercontent.com/PhannGor/phanngor.github.io/master/RainbowFolders/v0.2.1_03.png)

**Please Note:**

If you’re using “Two Column Layout” mode, then **perform colorizing on the folder in the right column** of the project view. Doing this from the left colum currently is not possible due to internal API limitations.
