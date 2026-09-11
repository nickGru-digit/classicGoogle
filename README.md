# Classic Google
This is a site designed to mimic the appeareance and useability of google.com based on the first Wayback Machine archive of the homepage after 2000-01-01 https://web.archive.org/web/20000301105534/http://google.com/

Personally, I have it set so my web browser homepage when I open a new window or tab goes to this site. I wanted to make this because I couldn't find any existing sites that did this (and get rid of the ugly modern Google), and I figured it would be pretty simple to create.

The search bar takes you to modern Google, but, just for fun, it takes out the AI Overview in the query to give back some of that old internet feel.

For now, the alternate links on the site path to the Wayback versions, which will result in some shenanigans if you go back and forth. It tries to hide the toolbar at the top, but going between multiple pages will occasionally make it reappear.

Eventually, the plan is to remake all of those pages, but they are just information and unimportant to the main function (unless you want to apply to work at Google 26 years late)

## Firefox configuration

### Setting new window
Note: this will only change your default whenever you open a **new window**, not a new tab. If you want every tab to also be customized, you need to download an extension.

```Hamburger menu > Settings > Home and startup```

Change **Homepage** from ```Firefox Home (Default)``` to ```Custom URls...```

Click ```Choose a specific site```

In the field that says ```Enter address```, paste in ```https://nickgru.codeberg.page/classicGoogle/``` and append yahoo.html if desired

Now, every time you open a new Firefox window, you will be greeted by your classicGoogle page of choice!

### Setting new tabs
If you are uncomfortable downloading an extension, stop here

Go to ```https://addons.mozilla.org/en-US/firefox/addon/new-tab-override/```, click **Add to Firefox**, then click **Add** (checking Allow to run in private windows is optional)

If it does not automatically open, click on the puzzle piece in the top right and then run *New Tab Override*, which will by default take you to the settings page

For settings, change **Option** to **Custom URL**, paste ```https://nickgru.codeberg.page/classicGoogle/``` in the URL field, and click **Save rule**

In order to force Firefox to focus the text on the search bar within the website, scroll down to **Focus** and check the box marked ```Set focus to the web page instead of the address bar```

You may also have to click **Keep changes** when Firefox asks you if you meant to have *New Tab Override* override your new tab.

Now, each new tab you open in the same window will also be classicGoogle!