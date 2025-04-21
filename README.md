# My vimium config
Some customization. Includes tokyo night theme and remapping of tab navigation
## Tokyo Night
For tokyo night them copy `styles.css` into you **CSS for Vimium UI**
## Rebinding
For the rebinding of more vim like naviation of tabs (I mean like in lazyvim) copy and paste below code into **Custom key mappings**

```
unmap J
unmap K
unmap H
unmap L
map J goForward
map K goBack
map H previousTab
map L nextTab
```

## Search engines
For the rebinding of more vim like naviation of tabs (I mean like in lazyvim) copy and paste below code into **Custom key mappings**

```
w: https://www.wikipedia.org/w/index.php?title=Special:Search&search=%s Wikipedia
g: https://www.google.com/search?q=%s Google
l: https://duckduckgo.com/?q=\%s DuckDuckGo
y: https://www.youtube.com/results?search_query=%s Youtube
gm: https://www.google.com/maps?q=%s Google maps
gpt4: https://chat.openai.com/?model=gpt-4o&q=%s
gpt: https://chat.openai.com/?model=o3-mini&q=%s
gpth: https://chat.openai.com/?model=o3-mini-high&q=%s
ds: https://chat.deepseek.com/
pr: https://proxer.me/search?s=search&name=%s&typ=all-anime&tags=&notags=#top
# b: https://www.bing.com/search?q=%s Bing
d: https://duckduckgo.com/?q=%s DuckDuckGo
# az: https://www.amazon.com/s/?field-keywords=%s
# qw: https://www.qwant.com/?q=%s Qwant
```
