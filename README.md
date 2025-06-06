# Piped

[![AGPL v3](https://shields.io/badge/License-AGPL%20v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0.en.html)
[![Matrix](https://img.shields.io/matrix/piped:matrix.org)](https://matrix.to/#/#piped:matrix.org)
[![Lemmy](https://img.shields.io/lemmy/piped%40feddit.rocks)](https://feddit.rocks/c/piped)
[![Registered Users](https://pipedapi.kavin.rocks/registered/badge)](https://piped.video/register)
[![IPFS Build](https://github.com/TeamPiped/Piped/actions/workflows/ipfs-build.yml/badge.svg)](https://piped-ipfs.kavin.rocks/)
[![GitHub Repo stars](https://img.shields.io/github/stars/TeamPiped/Piped-Frontend?style=social)](https://github.com/TeamPiped/Piped/stargazers)
[![GitHub last commit](https://img.shields.io/github/last-commit/TeamPiped/Piped-Frontend)](https://github.com/TeamPiped/Piped/commits)
[![Translation status](https://hosted.weblate.org/widgets/piped/-/frontend/svg-badge.svg)](https://hosted.weblate.org/projects/piped/frontend/)

An open-source alternative frontend for YouTube which is efficient by design.

A list of public instances can be found at the documentation [here](https://github.com/TeamPiped/documentation/blob/main/content/docs/public-instances/index.md).

# The Problem

YouTube has an extremely invasive privacy policy which relies on using user data in unethical ways. You give them a lot of data - ranging from ideas, music taste, content, political opinions, and much more than you think.

By using Piped, you can freely watch and listen to content without the fear of prying eyes watching everything you are doing.

## Features:

**User Features**

-   [x] No Ads
-   [x] No Tracking
-   [x] Lightweight on server and client
-   [x] Infinite Scrolling
-   [x] Light/Dark themes
-   [x] Login
-   [x] Feeds
-   [x] Playlists
-   [x] Integration with [SponsorBlock](https://github.com/ajayyy/SponsorBlock)
-   [x] Integration with [LBRY](https://lbry.com/) for streaming
-   [x] Integration with [Return YouTube Dislike](https://returnyoutubedislike.com/) via [RYD-Proxy](https://github.com/TeamPiped/RYD-Proxy)
-   [x] 4K support
-   [x] No connections to Google's servers
-   [x] Playing just audio
-   [x] PWA support
-   [x] Locally saved Preferences
-   [x] [Available in many languages](src/locales), thanks to [our translators](https://hosted.weblate.org/projects/piped/frontend/)
-   [x] Embedded video support
-   [x] No age restriction
-   [x] Bypasses Geo restrictions if possible through a federated network

**Technical Features**

-   [x] Multi-region load-balancing
-   [x] Performant by design, designed to handle 1000s of users concurrently
-   [x] Does not use official YouTube APIs
-   [x] Uses [NewPipeExtractor](https://github.com/TeamNewPipe/NewPipeExtractor) to extract information
-   [x] Public [JSON API](https://docs.piped.video/docs/api-documentation/)
-   [x] Federated protocol on Matrix to let instances collaborate with each other

## Having trouble?
If you have any general questions regarding how Piped works or trouble setting up your own instance, please consult the following public chat rooms and documentation for help. Please use these platforms exclusively for such cases and do NOT open an issue.

### Public Chat Rooms/Communities

-   You can join us via Matrix at [#piped](https://matrix.to/#/#piped:matrix.org).
-   You can join us on Lemmy on the [!piped@feddit.rocks](https://feddit.rocks/c/piped) community.

### Self-Hosting

See https://docs.piped.video/docs/self-hosting/ for more details.

The source code of the documentation website is available at https://github.com/TeamPiped/Documentation.

### Documentation

The documentation can be found at https://docs.piped.video (accessible via IPNS as well).

The API specification is located at https://github.com/TeamPiped/OpenAPI.

## Extensions

To redirect all YouTube links to Piped, you are highly recommended to use either [Piped-Redirects](https://github.com/TeamPiped/Piped-Redirects), [Libredirect](https://github.com/libredirect/libredirect) or [Predirect](https://github.com/libreom/predirect).

## Contributing

### Translations

You can help by translating the project to a language you speak at https://hosted.weblate.org/projects/piped/frontend/

### Mirrors

-   Cloudflare Pages - [cf.piped.video](https://cf.piped.video/)
-   Vercel - [vc.piped.video](https://vc.piped.video/)
-   Render - [re.piped.video](https://re.piped.video/)
-   Fleek - [fl.piped.video](https://fl.piped.video/)
-   DigitalOcean - [do.piped.video](https://do.piped.video/)
-   Netlify - [nf.piped.video](https://nf.piped.video/)
-   Azure - [az.piped.video](https://az.piped.video/)

### Forking, and contributing

-   Fork the repository on GitHub: https://github.com/TeamPiped/Piped/fork
-   Create your feature branch: `git checkout -b my-awesome-feature`
-   Stage your files `git add .`
-   Commit your changes `git commit -am 'Add awesome new feature'`
-   Push to the branch `git push origin my-awesome-feature`
-   Create a new pull request: https://github.com/TeamPiped/Piped/compare

### Development Setup

```
pnpm install
```

### Compiles and hot-reloads for development

```
pnpm dev
```

You can now make changes and view then in realtime!

## Donations

Donations (to Kavin) can be made at:

-   bc1qhq8zjxmu405nvp37njj6zv3s980zg400pu9jfe (BTC)
-   0x1D77D4cfB1a947514241bcf19B1F04738495e2fD (ETH)
-   84wyyeGTrg4U1daJufi78bAFrBQgdRhmxJZvgYv8dAFeFVwkJaBEmw5C7fNniUM9n4jfrz3NeG32Agxtp7JNAcCUFPACfwA (XMR, aka Monero)
-   nano_1ngejzydncche4rdua3iebhj7sa95pw5geq4pb8phugtjf3tku933ktjb4pq (Nano)
-   XpzgouDTKCUuE8a92XqjX9b43gKL8oLihw (Dash)

FIAT donations can be made at:

- https://liberapay.com/kavin (Initial author)
- https://liberapay.com/Bnyro (Project maintainer)

Contributions in any other form are also welcomed.

# Made with Piped

**Mobile/desktop apps**
-   [LibreTube](https://github.com/Libre-tube/LibreTube) - Alternative frontend for YouTube for Android.
-   [Yattee](https://github.com/yattee/yattee) - Alternative frontend for YouTube for MacOS / iOS.
-   [YTDLnis](https://github.com/deniscerri/ytdlnis) - Video and audio downloader for Android that uses Piped to update formats.
-   [Pipeline](https://gitlab.com/schmiddi-on-mobile/pipeline) - Alternative frontend for YouTube for Linux.
-   [PlasmaTube](https://apps.kde.org/plasmatube/) - Alternative frontend for YouTube for Linux.
-   [Harmony Music](https://github.com/anandnet/Harmony-Music) - YouTube Music alternative for Android/Windows/Debian, built with Flutter that supports piped linking for playlists.


**Web apps**
-   [Hyperpipe](https://codeberg.org/Hyperpipe/Hyperpipe) - Alternative privacy respecting front-end for YouTube Music.
-   [ytify](https://github.com/n-ce/ytify) - Complementary audio streaming frontend for YouTube & YouTube Music. 
-   [Piped-Material](https://github.com/mmjee/Piped-Material) - Fork of Piped, focusing on better performance and a more usable design.
-   [Musicale](https://github.com/Bellisario/musicale) - Alternative frontend for YouTube Music with style.


**Not Under Active Development**
-   [PsTube](https://github.com/prateekmedia/pstube) - Watch and download videos without ads on Android, Linux, Windows, iOS, and Mac OSX.
-   [VibeYou](https://github.com/you-apps/VibeYou) - Privacy focused music player for Android supporting playback via Piped. 
-   [conduit](https://github.com/ai25/conduit) - Alternative frontend for YouTube, with a modern player and watch together capabilities.
-   [DeskVideo](https://github.com/malisipi/DeskVideo) - Desktop styled, customizable alternative frontend for YouTube.
-   [ReacTube](https://github.com/NeeRaj-2401/ReacTube) - Privacy friendly & distraction free YouTube frontend.
-   [vidyodl](https://github.com/MrKovar/vidyodl) - Simple API to download videos from YouTube, using Piped.
-   [Piped Addon for Kodi](https://github.com/syhlx/plugin.video.piped) - Kodi plugin for Piped.

## YourKit

![](https://www.yourkit.com/images/yklogo.png)

YourKit has given an open source license for their profiler, greatly simplifying the profiling of Piped's performance.

YourKit supports open source projects with its full-featured Java Profiler.
YourKit, LLC is the creator of [YourKit Java Profiler](https://www.yourkit.com/java/profiler/)
and [YourKit .NET Profiler](https://www.yourkit.com/.net/profiler/),
innovative and intelligent tools for profiling Java and .NET applications.
