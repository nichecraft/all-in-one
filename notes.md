# Chrome custom profile
chrome.exe --user-data-dir=c:\foo

# Firefox custom profile
firefox.exe -P foo -no-remote

# Firefox about:config
```
# https://support.mozilla.org/en-US/kb/how-stop-firefox-making-automatic-connections
browser.compactmode.show : true
dom.event.contextmenu.enabled : false
dom.popup_allowed_events : dblclick
geo.enabled : false
network.prefetch-next : false
network.captive-portal-service.enabled : false
network.connectivity-service.enabled : false
```
