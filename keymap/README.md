# Remote control

A keymap for use with **Iconbit G-Control** / **Mele F10** remote control

<img src="https://www.photo-online-bh.com/eBay/Product/MELE%20F10%2005.jpg" width="400" title="Mele F10">

Inspired by http://www.olivergast.de/blog/2014/03/09/xbmc-mele-f10-flyair-mouse-fuer-raspbmc-konfigurieren/  
Includes Bugfix for https://trac.kodi.tv/ticket/15670

## Hints

When a mousedrag is recognized, no click event will be fired. So if you move the air mouse and press left button (button in the circle), nothing happens.

#### Solution:  

Add the keymaps for <code>&lt;leftclick&gt;</code> and <code>&lt;rightclick&gt;</code> also to <code>&lt;mousedragend&gt;</code> and <code>&lt;mouserdragend&gt;</code>.

## Libreelec

Put it in <code>/storage/.kodi/userdata/keymaps/</code>
