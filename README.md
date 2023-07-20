# bookmarklets
Bookmarklets I've made (Issues welcomed)

## What are bookmarklets?
Bookmarklets are small pieces of javascript that execute a function within the space of a href tag or bookmark element, to add this to your bookmarks simply drag and drop the one you want onto the space where the bookmarks are located.

## Ones I've made:
<h3><a href="javascript:location.href=`https://web.archive.org/web/2/http://wayback-fakeurl.archive.org/yt/${new URL(window.location.href).searchParams.get('v')}`">Wayback YT Video MP4</a></h3>
Attempts to scan Wayback for the direct MP4 archived from YouTube.

<h3><a href="javascript:window.location=`steam://openurl/${window.location.href}`">Open in Steam</a></h3>
Opens the currently open url in the Steam client, usually only intended for Steam related pages.

<h3><a href="javascript:(function(){document.querySelectorAll('video[disablepictureinpicture]')[0].removeAttribute('disablepictureinpicture')})()">PiP Disney+ Player</a></h3>
PiP is disabled on the player on Disney+, use this to enable it.