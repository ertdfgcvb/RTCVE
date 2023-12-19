# RTCVE
**Real Time Canvas Video Exporter** (from OpenSea)  
This page loads a collection info through OpenSea’s API, displays it trough an iframe and records a video stream of the canvas.  
It’s meant to be used locally.  

NOTE: this works only if same-origin policy is disabled in browser.
- Safari  
Settings > Developer > Disable cross-origin restrictions
- Chrome (macOS)  
Close all sessions and them run:  
`open -na "Google Chrome" --args --user-data-dir=/tmp/temporary-chrome-profile-dir --disable-web-security --disable-site-isolation-trials`
- FireFox  
  TODO