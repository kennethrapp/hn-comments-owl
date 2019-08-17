# HN Comments Owl

![](icons/thumbnail.gif)

A browser extension which draws the rest of the friendly owl for Hacker News comment threads to make them actually followable over time, by automatically highlighting new comments and showing which items have new comments, plus various other UX tweaks.

* [Install Chrome Extension]()
* [Install Firefox Add-on]()
* [Install as a user script](https://greasyfork.org/en/scripts/18066-hn-comment-trees) (requires a [user script manager](https://greasyfork.org/en#home-step-1))

## Features

- Show new comment counts since your last visit on item list pages
- Highlight new comments and collapse comment trees which don't contain any new comments when you revisit an item's comments
- Manual highlighting of recent comments when new comments can't automatically be highlighted

## Other Tweaks

- Add an "upvoted" link to the header to make it easier to get back to previously visited stories, using upvote as a bookmark (default: on)
- Toggle display of "reply" links below comments to make more room for comments on the screen (default: off)

## Screenshots

### Item list page with new comment counts

![](screenshots/item_list.png)

### Automatic new comment highlighting & collapsing

![](screenshots/auto_highlight_new.png)

### Mid-thread view of new comment highlighting & collapsing

![](screenshots/new_comment_highlighting.png)

### Manual highlighting of recent comments

![](screenshots/highlight_past_comments.png)

### Toggling display of reply links

![](screenshots/toggle_reply_links.png)

## Options

| Firefox | Chrome |
|:-------:|:------:|
| ![](screenshots/options_firefox.png) | ![](screenshots/options_chrome.png) |

### Automatically highlight new comments

_Default: enabled_

Always highlight new comments and collapse old comments when you visit an item's comments - if disabled, this will only happen if you use the "X New" link on an item page, otherwise you will have to manually use the checkboxes at the top of the screen to highlight new comments 

### Add upvoted link to header

_Default: enabled_

Adds an "upvoted" link to the site's top navigation so you can more easily get back to the comment threads on items you've recently upvoted.

### Hide reply links under comments

_Default: disabled_

Hides reply links in comment threads to allow more vertical space for comments.

This option can also be toggled while viewing an item's comments threads, using the browser's context menu:

![](screenshots/toggle_reply_links_context_menu_chrome.png)

## Icon Attribution

[Surprised owl stroke icon](https://www.vexels.com/vectors/preview/153933/surprised-owl-stroke-icon) | designed by Vexels