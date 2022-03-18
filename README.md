# Vanced (Sleep, brother)

This repo contains, (Thanks to [speedie](https://twitter.com/spdgmr) for archive.org and torrent links)
- [GitHub Vanced Repository](https://archive.org/details/yt-vanced)
- [API and Binaries](https://archive.org/details/vanced-api)
- [API and Binaries Torrent](https://anonfiles.com/Bcf5aaObx1/Vanced_torrent) (The same is available in `torrent-files` folder ([_here_](https://github.com/pixincreate/Vanced/tree/main/torrent-files)))
  
[Or, you can download any files from [_**here**_](https://archive.org/download/vanced-youtube/)]

## Vanced Manager [v2.6.2](https://github.com/pixincreate/Vanced/releases/download/1.0/vanced-manager-v2.6.2.apk) Changelogs:
- Fixed root installer for some users
- App now checks for Magisk and displays an error message if it's not detected
- Various optimizations

## Vanced (v17.03.38)
- [com.google.android.youtube](https://github.com/pixincreate/Vanced/releases/download/1.0/YouTube_com.google.android.youtube_17.03.38.apks) (**This version requirs root**)
- [com.vanced.android.youtube](https://github.com/pixincreate/Vanced/releases/download/1.0/com.vanced.android.youtube_17.03.38-1527248320_2arch_72lang_b5e983d50a4af4ba9cf9dbe09b368bad_apkmirror.com.apkm) (**This version requirs MicroG to Login**)

[**NOTE:** User should install _Split APK Installer_(popularly known as SAI) to install YouTube APKs]

## Vanced Music (v4.64.51)
- [com.google.android.apps.youtube.music](https://github.com/pixincreate/Vanced/releases/download/1.0/com.google.android.apps.youtube.music-v4.64.51.apk) (**This version requirs root**)
- [com.vanced.android.apps.youtube.music](https://github.com/pixincreate/Vanced/releases/download/1.0/com.vanced.android.apps.youtube.music-v4.64.51.apk) (**This version requirs MicroG to Login**)

## Vanced Alternatives
For more revision updates, check [_here_](https://gist.github.com/SkyyySi/1b621c7c20ae7e0865a8ac428156c1cf#file-youtube-vanced-alternatives-md).  
Credits to @[SkyyySi](https://github.com/SkyyySi) for Alternatives list as the same is reproduced here.
#### NONE OF THESE CLIENTS ARE VERIFIED BY ME FOR SECURITY OR ANYTHING ELSE! USE AT YOUR OWN RISK!

These are the current alternatives (with links when possible):
- [NewPipe](https://github.com/TeamNewPipe/NewPipe/releases) (which you should have either way for youtube-dl/yt-dlp integration)
  - [NewPipe fork by polymorphicshade](https://github.com/polymorphicshade/NewPipe), which includes SponsorBlock support.
- [LibreTube](https://github.com/libre-tube/LibreTube/releases) (still in early beta)
- A web browser with [uBlock Origin](https://github.com/gorhill/uBlock) (or another ad-blocker; [Enhancer for YouTube](https://www.mrfdev.com/enhancer-for-youtube) has one build-in, but uBlock is universal and more powerfull, in addition to allowing to also remove non-advertisement parts of the website, like the top shelf with recommended tags / search querries), [Enhancer for YouTube](https://www.mrfdev.com/enhancer-for-youtube), [SponsorBlock](https://github.com/ajayyy/SponsorBlock) and [Return YouTube Dislike](https://www.returnyoutubedislike.com/). These all work on both desktop Firefox and Chrome, but on mobile, you'll need to install an add-on compatible fork (source code alteration) of them, like [IceRaven](https://github.com/fork-maintainers/iceraven-browser) for Firefox or [KiwiBrowser](https://kiwibrowser.com/), then install the addons from their respective adddon store. Depending on the browser, you'll additionally need to install a user script for background playber. Alternatively, the [Brave](https://brave.com/) browser supports background playback OOTB (needs to be enabled; see coment by @dmdotin) and a build in ad-blocker, but no extension / add-on support.
- YouTube Pink (I have no legit link yet)
- YouTube++ (iOS) (I have no legit link yet)
- [uYouPlus](https://github.com/qnblackcat/uYouPlus) (iOS), a modded version of the official iOS app (arguably the most feature-complete alternative to Vanced).
- [SkyTube](https://github.com/SkyTubeTeam/SkyTube/releases)
- [MusicPiped (F-Droid; YT Music alt.)](https://github.com/deep-gaurav/MusicPiped/releases)
- A stand-alone ad-blocker like [AdAway](https://github.com/AdAway/AdAway/releases) (requires root to work fully, but a no-root DNS mode is also available), but this will only work
- [VueTube](https://github.com/Frontesque/VueTube), a very new client.
- [SmartTubeNext](https://github.com/yuliskov/SmartTubeNext), an ad-free YouTube TV client (Android TV only).
- [SongTube](https://github.com/SongTube/SongTube-App), a YT client for music.
- [YMusic](https://ymusic.io/), a small and simple YT music client with low data consumption.
- [PureTuber](https://www.puretuber.com/), appears to be a fully featured alternative to the official app. **I have not tested not installed this one, because it appears extremely sketchy to me, [their FAQ](https://www.puretuber.com/faq) contains lots of red flags (in my opinion).**
- [Invidious](https://invidious.io/), an alternative, self-hosted YouTube front-end.
- [DVD](https://f-droid.org/de/packages/org.yausername.dvd/), an Android front-end for [yt-dlp](https://github.com/yt-dlp/yt-dlp) (an extremely powerful downloader with support for hundreds of sites).

If you want to save videos offline using scripting, you can use [yt-dlp](https://github.com/yt-dlp/yt-dlp) running in [Termux](https://github.com/termux/termux-app) (run `pkg install -y python; python -m pip install yt-dlp` to install it).

Also, there's [xManager-Spotify](https://github.com/xManager-v2/xManager-Spotify/releases) for... Spotify, as a replacement for Vanced Music. I would advise you to not use this with a premium account though, since ad blockers are a TOS violation and can get your account suspended. That won't really matter in practice if you just use throw-away accounts though (I'm not a lawyer, so don't quote me on that).

As for what I think are the best ones: Either NewPipe (has some nice features like support for other platforms like SoundCloud and a complete downloader) or the Web version with add-ons (which will give you the most complete experience, including login).

Some things that may or may not work are most popular video players, but they won't allow discovery (except for possibly Kodi)

Finally a pro-tip: If you want to **download videos from any YT app**, you can install NewPipe and share the link to the video to it from the share-menu. Then you can select to always download when sharing to NewPipe.

If you want a copy on Discord or you know another App I should add, just DM me 👌

(created by @!SkyyySi#1859 / @SkyyySi)
  
  
  
# DISCLAIMER:
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS ORIMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHERLIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS INTHE SOFTWARE.
