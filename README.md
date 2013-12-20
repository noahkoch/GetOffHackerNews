GetOffHackerNews
================

I love Hacker News. Almost a little too much. This little chrome extension allows you to kick your habit. Navigating to news.ycombinator.com will automatically redirect you to a random Wikipedia article. 

### Editing
To change what sites redirect, just edit the manifest file.

```
"matches": ["https://news.ycombinator.com/"]
```

To make it redirect Facebook:

```
"matches": ["https://facebook.com/"]
```

To make it redirect multiple sites:

```
"matches": ["https://news.ycombinator.com/","http://walmart.com/"]
```

### Installing
In the Google Chrome preferences, check "Developer Mode", click "Load unpacked extension..." and select the folder containing this repo. 

That's it!
