---
publish: true
draft: "false"
created: 2026-07-15T02:19:08.393-05:00
modified: 2026-07-31T05:06:08.571-05:00
published: 2026-07-31T05:06:08.571-05:00
tags:
  - VRChat
---

> [!warn] This page is a work in progress.

When uploading an avatar to VRChat, there's tons of resources all over YouTube and the web for creating your perfect virtual persona. However, if you want your own world; maybe something more customized than the [80+ bedrooms](https://vrclist.com/?type=search\&tags=bedroom\&sort=recent) you find on a basic search. A few people have asked me for help building worlds, or where I find tools to get started.

> [!caution] A few things to keep in mind before we get started;
>
> - _I am entirely self-taught._
> - _I haven't touched blender._

I have heard that making world for VRChat does basically make you a level/game designer.
I haven't spread my wings outside of the VRCSDK so I'll let you know.

## 📖 Other Guides

Listen, I'm terrible at writing. Here's a collection of guides I know about/have used

- https://wiki.virtualabs.cloud/guide-hub - Should be fairly up to date

> [!NOTE] _"The only way to begin is by beginning..."_
> A great place to start is [this YouTube Playlist by Iconoclass](https://www.youtube.com/playlist?list=PLPdWkxUSZ65Fp6ICrU7mIq1znAfPwMhNZ), and his video tutorials.
> They are a bit older, and before VRChat required Creator Companion.
>
> Unfortunately, the more advanced tutorials are locked behind his [Patreon](https://www.patreon.com/iconoclass). I just subscribed long enough to see the Bakery tutorial, I might go back because I see he's added a lot more.

---

## 🤔 Things to Consider

- Building an indoor space is much easier.
- Blocking out spaces then add detail https://x.com/Swiftdeath918/status/2068721412286849105
  - Forces you to 'trust the process'
- [[Interior Design]] Principals

## 📋 Project Setup

Instead of VRChat Creator Companion, I use [ALCOM/vrc-get](https://vrc-get.anatawa12.com/en/alcom/), the open source alternative. It seems to run a bit faster, with more quality of life additions, like being able to enable multiple packages at the same time. You're still able to click "Add to VCC" links in your browser too!

#### Using ALCOM 📦

##### Adding Packages

- VPM Mirror https://vpmm.dev/#/

* VRChat Creator Companion? Nah, use ALCOM!
* Add VPM Mirror
* Build a 'world template' (make in github?)'
* Needed packages
  - Audiolink (Autolink)
  - Poiyomi
  - VrcMarker or QVPen or the new one?
  - AutoCertify Copyright
  - Light Volumes (needs Bakery)
* Neat Packages
  - Photo Frame Manager
* Purchase Bakery, it's on sale a lot
* Probuilder

#### Setup in Unity 🎮

Admittedly, there is _ONE_ paid asset you will probably need to get. [Bakery](https://assetstore.unity.com/packages/tools/level-design/bakery-gpu-lightmapper-122218) is a NVIDIA GPU Light-mapper that makes well lit worlds possible. Try to catch it on sale, as it tends to be 50% off (~\$27.50 USD)

Very recently z3y released [glim](https://github.com/z3y/glim), which is an alternative open source light mapper, but I haven't tried it yet.

## 👨‍💻 Using Unity

> [!error] **Back up your project!** I know it can be a slow process; but I try to run a backup before I get started for the day.

- To keep a sense of scale, it helps to have a stand-in object for the height of the user. I use these [Editor markers](https://tsunamoo.booth.pm/items/3092199) that are already tagged as "EditorOnly", so they don't end up in the final upload. I put one at the spawn, and then any gathering spaces like in front of video players.

#### Building with Probuilder 📐

Block out the spaces you want first, focus on details later.

#### Adding Prefabs 🛋️

###### Finding Prefabs and Models 👀

[[Sourcing World Assets]]

#### Shaders/Materials

https://github.com/MochiesCode/Mochies-Unity-Shaders/releases

#### Udon Scripts

> [!hint] Play mode isn't working?
> Most of the time, it's network IDs. Use the Open NID window to resolve these conflicts.

### Baking lights with Bakery 💡

### Post Processing 🪟

### Little Details

- I like to make 'cosy' spaces feel lived in
- Worlds now have contacts! What will happen if someone sprays something with a water gun??

## 📈 Optimizing Your World

### Download Size

- Font Baker https://mametarovv.booth.pm/items/8528124

### Frames per Second

Resources:

- https://orels.sh/p/tools/

Misc:

- Let's be glad we don't have to [make maps in Valve's HAMMER](https://www.youtube.com/watch?v=aZZRTxdinbU)
- People have opinions on ScreenFX https://bsky.app/profile/babyjack.bsky.social/post/3mmrlsfcayc2q
  ![[_imgs/sticker_vid_coffee.png|150]]
