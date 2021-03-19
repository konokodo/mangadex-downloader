# mangadex-downloader
This repository is a fork that focuses primarily on the mangadex-downloader userscript.

## mangadex-downloader.user.js (API v2)
A userscript to add a download-button to mangadex-chapters. [Install](https://github.com/konokodo/mangadex-downloader/raw/master/mangadex-downloader.user.js) 

You can find its settings [here](https://mangadex.com/settings)

#### Changes

- Archive filename
- Image filename
- Updated to use MangaDex API v2

## delete-all-chapters-of-user.js
This deletes all chapters of a user on the current page. After pasting it into the browser-console it will ask you which user's chapters you want to nuke. You will need to fill in the url of the user. Your user-url will be the default. Make sure you do have the permissions to delete them.

## mangadex-bulk-cover-uploader.user.js
A userscript to add bulk cover upload to mangadex. It will use the first number in the filename as Volume.  
  
## mangadex-mangaupdates_rating.user.js
A userscript which automatically fetches the rating of the current manga from mangaupdates and injects it into the current page. [Install](https://github.com/xicelord/mangadex-scripts/raw/master/mangadex-mangaupdates_rating.user.js)

## mangadex-uploader.sh
A primitive bash-script to upload a single chapter to mangadex. For help how to use it, simply execute it without arguments.
An improved version for bulk-uploads written in NodeJS can be found [here](https://github.com/xicelord/mangadex-bulkuploader).
