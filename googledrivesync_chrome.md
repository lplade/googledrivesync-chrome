# What is googledrivesync\_chrome? #

**googledrivesync\_chrome** is a Windows Script to open Google Chrome on a double-click of Google Doucments file in Google Drive directory.

With Windows Explorer in directory of Google Drive, **googledrivesync-chrome** forces the use of Google Chrome on a double click of a Google Document.

# Install googledrivesync\_chrome #

Consult the Wiki page [How to install googledrivesync\_chrome](install.md).

# A few questions #

## Why not setting Google Chrome as default browser? ##

Many intranet application were designed for only one browser, to reduce the cost of testing, maintenance and to be compatible with enterprise settings.

For this reason, some professional intranet environment requires the use of one specific browser and this is the default browser. **googledrivesync-chrome** helps you get around this.

## Why use Google Chrome and not an other browser for Google Document? ##

Google Drive and the Google Document files working good with many browsers.
However, the offline documents are only available with Google Chrome. That is the role of **googledrivesync-chrome** to allow you to use Chrome when it is not setup by default.

# Tests in progress... #

  * Windows 7 64 bits
  * Windows XP 32 bits
  * Later: Windows Vista

# Detail #

  * Use json2.js library of Douglas Crockford from https://github.com/douglascrockford/JSON-js. Others details on JSON: http://www.json.org/js.html