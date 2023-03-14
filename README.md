# Branching out the Filetree
### New features for an improved file management experience.
 Arnav Bansal and Adriana Poznanski

The filetree is a central surface of the workspace which has long been under-leveraged to support the workflows of users. As part of our ongoing workspace revamp, we're shipping improvements to make the filetree more usable and powerful. These improvements include:
  1. fixing existing usability issues to make file management seamless
  2. introducing new features to enhance workflows in the workspace

### Clarifying visual hierarchy
We've made some stylistic changes within the filetree to eliminate ambiguity surrounding file and folder hierarchy. Files no longer include a left side gutter, and folders no longer include a caret icon. This way, files and folders at the same hierarchical level are directly aligned. Open folders are now differentiated by an open folder icon, and include a containment line at the left border of their contents.
![hierarchy-fixes](hierarchy-fixes.jpg)
You can also now close folders by simply clicking on their containment line—this makes navigating the filetree much faster and easier, especially from large folders.
![folder-nav](folder-nav.gif)

### Finally, multiselect!
Say goodbye to painstakingly moving file one by one, long-awaited bulk actions are now ready for use in the filetree! In the desktop workspace, simply hold down shift to multiselect files. You can move multiple files at a time by dragging them to your desired location, or perform other bulk actions like open tabs, duplicate, download, and delete from the context menu.

`add desktop demo`

On mobile, open the filetree menu and click 'Select' to enter multiselect mode. From there you can select any number of files in your Repl and perform bulk actions on them.

`add mobile demo`

### Filetree searching and filtering
Previously, file and content search features were only available within the workspace by way of the command bar. Now, we've given the filetree a search bar of its own to increase the discoverability and accessability of these features. Using the filetree search bar, you can search your Repl for specific files or phrases and the results will be rendered directly in the filetree. We've also added a feature that allows you to filter the contents of the filetree by file type to streamline the search process if you are looking for a particular type of file. Spend less time lost in the filetree and more time building something great!

`add demo`

### Sync status
We've added a status indicator to the filetree so that you can tell whether or not your files are synced at any given time. Because Replit relies on internet connection to auto-save your work, if a Repl is disconnected it can interrupt the syncing process. Now, if your Repl is offline or a file is taking a long time to sync, it will be indicated in the status indicator, and files with unsynced changes will be highlighted in the filetree. Otherwise, you'll see the comforting message that all your changes are synced.

`add mock`

We hope you find the new and improved filetree to be much more ergonomic, and that these features help streamline your workflow in the workspace. Stay tuned for many more workspace updates in the near future—until then, happy coding!