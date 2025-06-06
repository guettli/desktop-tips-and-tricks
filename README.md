# Desktop tips and tricks

This page is for everybody working with a desktop computer. If you are a software developer, then please have a look at [my guidelines](https://github.com/guettli/programming-guidelines)

Although mobile interfaces are very important. I prefer a desktop PC/Laptop for daily **work**. In spare time I use my mobile phone more than my desktop PC/Laptop.

I think mobile interfaces are overrated at the moment. It is like the [Pork cycle](https://en.wikipedia.org/wiki/Pork_cycle) mobile interfaces are the current hype. Some years later people will re-invent keyboard focused application. Hypes come and go and come and go....

## Monitor
Reduce brightness. In most cases the screen is too bright.

## Copy+Paste History

A clipboard manager is a great tool. Don't ask me why only a few people use one.

[CopyQ](https://github.com/hluk/CopyQ) work on Linux, Windows, Mac.

Here is a nice [introduction](https://itsfoss.com/copyq-clipboard-manager/)

I map it to ctrl+alt-v.

## Chrome / Chromium

[Chrome is my new desktop](https://github.com/guettli/chrome-is-my-desktop)

### Chrome Shortcuts

https://support.google.com/chrome/answer/157179

* Ctrl + t: new tab. Then autocomplete in address bar.
* Ctrl + Shift + t: Reopen previously closed tabs in the order they were closed
* Ctrl + number-of-tab: Jump to numbered tab
* Ctrl + f: Open the Find Bar to search the current page    
* Ctrl + Shift + j: Open Developer Tools    
* F11: Turn full-screen mode on or off    
* Ctrl and +: Make everything on the page bigger    
* Ctrl-l: Jump to the address bar (for searching a term or going to a previous page)
* Alt + Left arrow:  Open the previous page from your browsing history in the current tab
* ctrl-h: History
* ctrl-w: Close current tab.
* shift+esc: Taskmanager

### Native GUI vs Chrome

Native GUI? No, if I want to work from a different device, then I don't have the files from the local drive. Yes, I could sync them, but for me in the browser (Software as a Service) is easier.  

### Pinned Tabs

From right to left: Calendar, Chat, Mail, Docs, Translator

### Long press back button

History: The title says a lot (for example in Gmail: Access one of the last mails)

### Bookmarks are dead, autocomplete in the address bar is king

I need to open a lot of different tools daily. In the past I used bookmarks, but this does not make
sense any more.

The autocomplete in the chrome address bar is fine. You just need to remember some part of the URL or 
the title of the page you want to open.

### History (ctrl-h)

I use ctrl-h several times per week. It gives my fast access to the pages which I visited in the past.


### Chrome Extensions

#### Chrome Extension "Copy Title and Url as Markdown Style"

Often I need to send an URL via Slack, Zulip or an other system which supports Markdown.

This extension is handy: It copies the current URL and page title as Markdownlink in the format `[page title](url)`.

[Copy Title and Url as Markdown Style - Chrome Web Store](https://chromewebstore.google.com/detail/copy-title-and-url-as-mar/fpmbiocnfbjpajgeaicmnjnnokmkehil)

The default short-cut (ctrl-shift-c) did not work for me, so I configured it to ctrl-shift-l (L ~> Link).

#### Chrome Extension "Tab Modifier"

https://github.com/furybee/chrome-tab-modifier

For example you have two Google Docs as pinned tabs. One doc for the planing (simple personal issue tracking), and a second where you write down what you did (aka "Log"). Both show the same icon. But you want to see a difference. This extensions lets you modify the icon easily. It is open source.

#### Chrome Extension "Quick Tabs"

[Quick Tabs](https://chrome.google.com/webstore/detail/quick-tabs/jnjfeinjfmenlddahdjdmgpbokiacbbb): A keyboard centric most recently used (MRU) ordered tab list plugin with search and switch functionality (inspired by IntelliJ IDEA). 

On Linux you can map the short-cut to ctrl-e (like in PyCharm) via [chrome://extensions/shortcuts](chrome://extensions/shortcuts). See [issue 305](https://github.com/babyman/quick-tabs-chrome-extension/issues/305)

Option "Keep last searched string in search box". I guess you want this to be "off". Right-click on icon right to the chrome address bar. Then Options, then "Keep last searched string in search box".

Option "Jump to previous tab on close of any tab (Tip: use to close tabs in reverse order, aka. undo your mess)" is handy. Usually you press ctrl-t to open a new tab. Then you do you work in this tab. If you close this tab (for example with ctrl-w), then you get back to the tab which had the focus before you pressed ctrl-t. That's the most obvious thing, and I don't understand why this is not the default of chrome.

### One laptop, two chrome profiles (personal, business)

See profile image right to the URL in chrome.

## GSuite

# GSuite Calendar

I like to view four days at once.

## Slack

I use the web version of slack.

* Action on message: Remind me about this ... tomorrow.
* Direct Messages / Slackbot. n-days-later-method works. Nice
* Shortcuts: https://slack.com/intl/en-de/help/articles/201374536-Slack-keyboard-shortcuts
* Some of my questions which are not solved yet: [webapps.stackexchange.com user:guettli [slack]](https://webapps.stackexchange.com/search?q=user%3A95624+%5Bslack%5D)

Goal: Use the chat without touching the mouse. Shortcuts I use:
* F6: moves to the next section
* Alt-left-arrow, Alt-right-arrow: move

* ctrl-k: goto channel or contact
* Alt + Left arrow (Chrome shortcut): Open the previous page from your browsing history in the current tab

Config:

* I prefer that "Enter" starts a new line. "Enter" should not send the message. See "Preferences > Advanced > When writing a message, press Enter to…"
* Don't ask me why direct messages are not sorted by "most recently" by default. Click on "⋮" and then "sort" ...

Use "dnd" (do not disturb) if you are on vacation or sick. If you have guidelines in your company, I would try to add this to the guidelines. It does not scale, if everybody should remember who is currently on vacation and who is available.

### Slack: Focused walk through the last messages in "Threads".

* Click on "Threads" (upper left corner)
* Press TAB until the latest (upper) message in "Threads" gets highlighted with a blue box.
* Now you can press arrow-down/up to walk through the messages step-by-step.

I prefer this to scrolling, since the blue box helps you to keep the focus.


## Typing with ten fingers

It makes typing much easier.

Free Web app to learn it: https://www.tipp10.com/

## Keyboard

I love the Lenovo track point with extra grip. 

I used [sandpaper stuck on Trackpoint](https://github.com/guettli/programming-guidelines/blob/master/sandpaper-glued-on-track-point.jpg) to 
get the extra grip.

But be careful: this can scratch the display if the display touches the sandpaper if you close the lid.

That's why I use an external USB Lenovo-Keyboard at the moment. Not perfect yet, please tell me if you have an idea how get maximum grip
on a track point!

There are 3D printed super low profile caps. See [reddit thread "More grip for the trackpoint?"](https://www.reddit.com/r/thinkpad/comments/qkzffd/more_grip_for_the_trackpoint_cap/)

BTW, scrolling is fast via middle-mouse-button-click and moving the track point.

## Drawing on Screenshots

* https://www.tldraw.com/

## Terminal

For the terminal (linux command line windows) I like to ues ctrl-c and ctrl-v for copy and paste.

Unfortunately the default is different. By default ctrl-c means interrupt the current process.

Likely this is easy to change in Gnome.

# ActivityWatch

At work we use a commercial application to track our activity. I use this tool manually: If I start to work
on something I press a button and to finish time tracking I press again.

From time to time I forget to start or stop.

That's why I use the open source tool [ActivityWatch](https://activitywatch.net/) to track everything I do automatically.
This way it is easy to find the point in time where I started/stopped to work.

# Screencasts

On Linux the tool Kazam works fine. But you should use webm output, since the mp4 output does not work in Firefox.

# DVD transcoding

[Handbrake](https://handbrake.fr/), an easy to use native GUI to transcode DVDs.

Sometimes you need [makemkv](https://www.makemkv.com/) to transcode.

# Putting Images/Text on PDF

[Xournal++](https://xournalpp.github.io/)

> Xournal++ (/ˌzɚnl̟ˌplʌsˈplʌs/) is an open-source and cross-platform note-taking software that is fast, flexible, and functional. A modern rewrite and a more feature-rich version of the wonderful Xournal program.

Available on MacOS, Windows, and Linux


# More

* [Thomas WOL: Working out Loud](https://github.com/guettli/wol)
* [Ten Flying Fingers (improve touch typing)](https://github.com/guettli/ten-flying-fingers)

