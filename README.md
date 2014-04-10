#Watch LESS
Mozilla Firefox plugin for compiling LESS files on-the-fly.


##Requirements: 
- Mozilla Firefox 3.6 or later. 
- Nothing else. You don't have to install node.js, ruby, AIR... Just only Firefox.


###What is LESS?
Less is an easier way to write and organize your CSS (Style-sheets). [Learn more](http://lesscss.org/)



##To install from the source:
1. Go to src folder.
2. Create zip archive containing all src/\* files.
3. Rename .zip to .xpi (change extension)
4. Open xpi file in Mozilla Firefox. It will prompt for add-on installation. This add-on doesn't require restart Firefox.


##To run:
1. Open Tools -> Add-ons -> Watch LESS -> Options.
2. Enter one or several files you want to compile. For example
   >C:\www\bootstrap\less\bootstrap.less
   >C:\www\my_variables.less
   >C:\www\my_styles.less

    This version doesn't support folders. Use `dir /b/s *.less` or `ls -1 /path/to/less` to get list of files.
3. Enter output filename for compiled CSS.
4. Press "Run Watcher" to compile on-the-fly  or "Compile" to compile just once.



##Similar projects:
- WinLess 
- Koala 
- SimpLESS 
