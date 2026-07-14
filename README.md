#Credits
This project is a modified and improved version of MirazMac's Media-Stream-Player project.

Original project: https://github.com/MirazMac/Media-Stream-Player

# Media-Stream-Player

Play HLS and DASH streams on Windows, with support for Clearkey, Widevine, and PlayReady DRM. No CORS issues to worry about. Pass your own `Referer`, `Origin`, `Cookie` `User-Agent` or any other forbidden/custom headers. Think of it as Android's [Network Stream Player (NS Player)](https://play.google.com/store/apps/details?id=com.genuine.leone&hl=en) but for Windows.

![Screenshot of Media Stream Player](https://i.postimg.cc/Dwptzm52/image.png)

## Features

- Plays HLS and DASH streams
- No CORS restrictions
- Allows any custom headers, including forbidden ones
- Supports Clearkey (server/inline), Widevine, and PlayReady DRM
- Enables passing headers to license and certificate servers
- Includes all standard Shaka Player features: adaptive bitrate, multiple resolution options, audio track selection, captions, picture-in-picture
- Lets you override Shaka config with your own JSON object
- Portable app, no installation required, just run it
- Paste cuRL(bash) command or NS Player style URL in the Streaming URL for autocomplete


## Technologies used

- Tauri
- SvelteKit
- Shaka Player
- M3 Svelte
- Tailwind CSS
