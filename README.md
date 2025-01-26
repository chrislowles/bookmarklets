# bookmarklets
Bookmarklets I've made (Issues welcomed)

## What are bookmarklets?
Bookmarklets are small pieces of javascript that execute a function within the space of a href tag or bookmark element, to add this to your bookmarks simply drag and drop the one you want onto the space where the bookmarks are located.

## Ones I've made:

```
javascript:window.location.host='www.youtube.com'??(()=>{location.href=`https://web.archive.org/web/2/http://wayback-fakeurl.archive.org/yt/${new URL(window.location.href).searchParams.get('v')}`})
```
Attempts to scan Wayback for the direct MP4 archived from YouTube.

----

```text
javascript:window.open(`steam://openurl/${window.location.href}`,'_top')
```
Opens the currently open url in the Steam client, usually only intended for Steam related pages.

----

```text
javascript:(function(){document.querySelectorAll('video[disablepictureinpicture]')[0].removeAttribute('disablepictureinpicture')})()
```
PiP is disabled on the player on Disney+, use this to enable it.