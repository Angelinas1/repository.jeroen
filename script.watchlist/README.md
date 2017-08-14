# script.watchlist
Script to provide watchlist functionality in Kodi library view, lists the next unwatched episodes or resumable movies.

### Information for skin developers

Include the following in your addon.xml:
```
<import addon="script.watchlist" version="0.0.1"/>
```

Use with:
```
<onclick>ActivateWindow(video,plugin://script.watchlist?type=[type],return)</onclick>
```

Where type is one of the following:
-   movies
-   episodes


### Credits
This script was created by Unfledged. Script is based upon service.library.data.provider, itself based upon service.skin.widgets.
