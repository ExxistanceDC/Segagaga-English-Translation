#### The SGGG 25th Anniversary Translation Team proudly presents:

# **Segagaga English Translation Patch**

Before we dive into the rest of the README, we must start with a word of thanks.

This effort simply would not have been possible without the members of the Dreamcast-Talk community that started tackling the various technical challenges in 2022. It was they who hacked the main binary, allowing it to leverage ASCII and use the Dreamcast BIOS font, built tools for extracting & re-compressing the textures, built tools for easy text reinsertion, and basically paved the way for a monkey like me to spend my days drawing, translating, and playtesting.

So, with utmost thanks:

<div align="center">
  
**DREAMCAST HACKING HEROES**

**megavolt85** (ASM hacking)</br>
**MadSheep** (custom script tooling)</br>
**VincentNL** (custom texture tooling)</br>
**Derek Pascarella (ateam)** (ASM hacking)</br></div>

Continuing on with the README...no, your eyes aren't playing tricks on you. You’re about to play Segagaga—the fun, quirky, RPG/game development simulator for Sega Dreamcast—in *English*. And you’re in for a truly unique and special experience.

Segagaga was released in March 2001 in Japan. Let’s put this into perspective: just two months earlier, on January 31, 2001, Sega announced that it was stopping production of Dreamcast consoles and would begin developing software for competitor hardware. It was a massive announcement that made waves across the gaming industry. One of the seminal hardware titans of the past 20 years was bowing out of the hardware race. For SEGA fans, it was a sad day, and the uncertainty about what the future would bring lingered for a long time afterward. (That is, until Sega started pumping out some seriously awesome games across the Xbox, PS2, and GameCube—many of which are considered classics today.)

Thus, Segagaga was released on a console that was no longer being produced. It would never make it overseas to the North American or European markets. Most Sega fans would only read about it in gaming magazines of yesteryear (like I did), regaled with stories of a unique RPG with sim-like elements that was packed with Sega references, inside jokes, and humor. 

As you’ll see, the game is everything its myth proclaims. It’s an earnest love letter to all things SEGA, with the player taking the role of Taro Sega in a quest to vanquish the evil Dogma, its fiendish sub-bosses, and finally put Sega at the top of the videogame industry after decades of underdog status. While that’s the main story thread, the game also has much to say about the challenges of game development and the videogame industry—topics that are arguably as relevant in today’s tumultuous market as they were in 2001. The game leaves all involved in game development with a timeless message:

<div align="center">Dreaming is humanity's last remaining privilege!</br>
It's not truth that paves the way—it's hope!</br>
If you forget that, you can't make games.</br></div>

## Table of Contents
- [Overview](#Overview)
- [Screenshots](#Screenshots)
- [Patching Instructions](#Patching-Instructions)
- [Known Issues](#Known-Issues)
- [Credits](#Credits)
- [Messages From the Team](#Messages-From-the-Team)

## **Overview**
This patch fully translates Segagaga into English. Our aim was to produce a faithful translation of both the source text and the original art. Care and attention have been paid to even the smallest details—for example, matching the stroke width of the original lettering in textures.

With this in mind, SGGG is a uniquely Japanese game, and we want the verisimilitude to make it feel like you're helping Taro Sega work for SoJ rather than SoA. Thus, certain things remain in Japanese, like small item textures, or the background signage in Akihabara. Generally, though, while *you* may be reading English as you play, Taro and most of the characters are Japanese.

You'll encounter many things that are specific to Japanese culture, so rather than shoehorning those into Western concepts, we've translated them as-is. Use it as an opportunity to learn... after all, unlike the ’90s, there's a whole internet available (and hours and hours of video content) for you to learn about something you may see in the game.

Savor the experience!

All that said, the following changes have made been to bring the game to English speakers:

- All in-game dialogue translated
- All chapter dialogue translated
- All cutscenes subtitled in English
- End credits translated
- All in-game UI textures redrawn in English
- Title Screen/Options/Save/Load screens redrawn in English
- All VMU save and application metadata translated in Dreamcast's BIOS menu save manager
- 25th Anniversary celebration added to opening splash screen
- New 25th Anniversary VMU icon during gameplay
- Original instruction manual translated and redrawn in faithful style to the original

## **Screenshots**

<!-- Row 1 -->
<p>
  <img src="Images/TAROMARU-250818-142700.png" width="500"/>
  <img src="Images/TAROMARU-250818-142640.png" width="500"/>
</p>

## **About the Game**

<table>
  <tr>
    <td><strong>Original Title</strong></td>
    <td>Segagaga (セガガガ) (SGGG)</td>
  </tr>
  <tr>
    <td><strong>Localized Title</strong></td>
    <td>Segagaga</td>
  </tr>
  <tr>
    <td><strong>Developer</strong></td>
    <td>Hitmaker Co., Ltd. / Thunder Stone Japan, Inc.</td>
  </tr>
  <tr>
    <td><strong>Publisher</strong></td>
    <td>SEGA</td>
  </tr>
    <tr>
    <td><strong>Original Release Date</strong></td>
    <td>2001-03-29</td>
  </tr>
  <tr>
    <td><strong>Supported Peripherals</strong></td>
    <td>Controller, VMU, VGA Box</td>
  </tr>
  <tr>
    <td><strong>Average Time to Completion</strong></td>
    <td>12 hours</td>
  </tr>
</table>



## **Patching Instructions**

Grab your original SGGG discs off the shelf! The patch is offered in two flavors: a Universal Dreamcast Patcher .DCP file and an xdelta .xdelta file. 

### Option 1: Universal Dreamcast Patcher

1. Download [Universal Dreamcast Patcher](https://github.com/DerekPascarella/UniversalDreamcastPatcher) (if you don't already have it)
2. Unzip patch bundle
3. Open xxx'**
4. After it opens, click **xxxx**
5. Next click **xxxxx**

### Option 2: xdelta

**--> Important! <--**
- Tested with <kbd>SGGG - Segagaga v1.022 (2001)(Sega)(JP)(!)</kbd> and <kbd>SGGG - Segagaga (Japan)</kbd>
- **DO NOT USE** "v2.000" or "Rev A". Due to cut content and minor changes, the patch was designed around v1.022 and will NOT work with v2.000.

## **Known Issues**

At this time, the only known issue is the spacing of the bluff (aka magic spells) cost in the Battle Mode bluff menu. You will notice that the numbers are a bit wider than the bluff name, and once they get to double-digits, they are indented farther in than the single-digit spell costs. We're still trying to hunt down a way to fix this, but it isn't game-breaking.

## **Extras**




## **Helpful Tips & Resources**

- Segagaga is meant to be played multiple times. I suggest just enjoying the experience your first time through. You likely won't get to the later chapters in your first playthrough; the game encourages you to develop more games to boost market share before they open up.
- Similarly, don't expect to unlock all Archive materials in your first playthrough. If you hit 100% market share, a special mode opens up that will help you complete the Archives.

Below are some resources that may assist you as you play through Segagaga:

<table>
  <tr>
    <td><strong><a href=https://archive.org/details/sggg-segagaga-perfect-file>SGGG Perfect Guide</a></strong></td>
    <td>Contains a walkthrough of the game, stats, developer interviews and insights, pre-production art, and more.</td>
  </tr>
  <tr>
    <td><strong>Localized Title</strong></td>
    <td>SEGAGAGA</td>
  </tr>  
</table>


## **Credits**

**Romhacking / Tooling**
- megavolt85
- MadSheep
- VincentNL
- Derek Pascarella (ateam)

**Translation / Review**
- Exxistance
- LostinLoc
- TeDNeo

**Editors**
- LewisJFC
- Sixfortyfive

**Texture Artists**
- Exxistance
- mr.nobody
- CWM

**Video Editing & Subtitling**
- mr.nobody
- Exxistance

**QA**
- Sixfortyfive
- Exxistance
- zeed64

**Manual**
- Exxistance

**My Deepest Thanks**

- My SGGG teammates: seriously, you all are amazing and it has been a joy to work with you!
- Tez Okano and the original development team (for putting your heart, soul, and time into making a unique game that has entranced a fanbase for 25 years.) 
- The Price of Reason (who doesn’t know me at all, but whose dedication to the Samurai Shodown RPG translation shows that passion and willpower can make all the difference in a project. Thank you for bringing SSRPG to English and fulfilling a 20+ year dream of mine to play it.)

## **Messages From the Team**

**Exxistance**
> Test

