# luci-theme-design

**luci-theme-design** is a secondary development based on [luci-theme-neobird](https://github.com/thinktip/luci-theme-neobird), applicable for lede For Lean's OpenWRT Only [lede](https://github.com/coolsnowwolf/lede)

- Fixed background whitening issue in package installation prompt
- Optimized menu scaling
- Optimized icon display for network port down status
- Optimized logo display
- Added status icons for various devices
- Changed logo display to font "OpenWrt", supports displaying hostname as logo
- Fixed display bugs in some plugins
- Fixed vssr status bar
- Fixed many bugs
- Fixed compatibility styles for some plugins
- Fixed aliyundrive-webdav styling
- Fixed abnormal display of vssr in iOS/iPadOS WebApp mode
- Fixed openclash plugin showing `env(safe-area-inset-bottom) = 0` in iOS/iPadOS WebApp mode
- Optimized menu hover action recognition
- Supports luci-app-wizard menu
- Update header box-shadow style
- Update uci-change overflow
- Fix nlbw component
- Added QSDK/QWRT wizard and iStore menu icon fonts

## Main Features

- Optimized for mobile devices, especially suitable as a WebApp on phones
- Modified and optimized many plugin displays, complete icon set for visual consistency
- Simple login interface, bottom navigation bar, app-like immersive experience
- Supports dark mode, adapts to system auto-switching

## How to Experience the WebApp

- Open the management interface in a mobile browser (iOS/iPadOS) and add it to the home screen
- For full immersive experience (no browser navigation, no address bar), use an SSL certificate. Please apply for a domain and certificate, install and enable it
- Without SSL, due to security reasons, iOS/iPadOS will show the browser's top menu bar when opening new pages

## PS

- Resource interface icons are not fully complete. If you can draw, PRs are welcome—but please keep icon colors and style consistent
- Bugs are welcome via issues
- Theme colors are personal preferences and may not suit everyone—color suggestions are welcome

## Manual Compilation
<pre><code>
git clone https://github.com/gngpp/luci-theme-design.git package/luci-theme-design make menuconfig # choose LUCI->Theme->Luci-theme-design
make V=s</code></pre>
