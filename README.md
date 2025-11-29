#### The SGGG 25th Anniversary Translation Team proudly presents:

# **SEGAGAGA English Translation Patch**

Before we dive into the rest of the README, we must start with a word of thanks.

This effort simply would not have been possible without the members of the Dreamcast-Talk community that started tackling the various technical challenges in 2022. It was they who hacked the main binary, allowing it to leverage ASCII and use the Dreamcast BIOS font, built tools for extracting & re-compressing the textures, built tools for easy text reinsertion, and basically paved the way for a monkey like me to spend my days drawing, translating, and playtesting.

So, with utmost thanks:

<div align="center">
  
**DREAMCAST HACKING HEROES**

**megavolt85** (ASM hacking)</br>
**MadSheep** (custom script tooling)</br>
**VincentNL** (custom texture tooling)</br>
**Derek Pascarella (ateam)** (ASM hacking)</br></div>

Continuing on with the README...no, your eyes aren't playing tricks on you. You’re about to play SEGAGAGA—the fun, quirky, RPG/game development simulator for Sega Dreamcast—in *English*. And you’re in for a truly unique and special experience.

SEGAGAGA was released in March 2001 in Japan. Let’s put this into perspective: just two months earlier, on January 31, 2001, SEGA announced that it was stopping production of Dreamcast consoles and would begin developing software for competitor hardware. It was a massive announcement that made waves across the gaming industry. One of the seminal hardware titans of the past 20 years was bowing out of the hardware race. For SEGA fans, it was a sad day, and the uncertainty about what the future would bring lingered for a long time afterward. (That is, until SEGA started pumping out some seriously awesome games across the Xbox, PS2, and GameCube—many of which are considered classics today.)

Thus, SEGAGAGA was released on a console that was no longer being produced. It would never make it overseas to the North American or European markets. Most SEGA fans would only read about it in gaming magazines of yesteryear (like I did), regaled with stories of a unique RPG with sim-like elements that was packed with SEGA references, inside jokes, and humor. 

As you’ll see, the game is everything its myth proclaims. It’s an earnest love letter to all things SEGA, with the player taking the role of Taro Sega in a quest to vanquish the evil Dogma, its fiendish sub-bosses, and finally put SEGA at the top of the videogame industry after decades of underdog status. While that is the main story thread, the game also has much to say about the challenges of game development and the videogame industry—topics that are arguably as relevant in today’s tumultuous market as they were in 2001. The game leaves all involved in game development with a timeless message:

<div align="center">Dreaming is humanity's last remaining privilege!</br>
It's not truth that paves the way—it's hope!</br>
If you forget that, you can't make games.</br></div>

## Table of Contents
- [Overview](#Overview)
- [Screenshots](#Screenshots)
- [Patching Instructions](#Patching-Instructions)
- [Helpful Tips & Resources](#helpful-tips--resources)
- [Known Issues](#Known-Issues)
- [Team Credits](#Team-Credits)
- [Messages From the Team](#Messages-From-the-Team)

## **Overview**
This patch fully translates SEGAGAGA into English. Our aim was to produce a faithful translation of both the source text and the original art. Care and attention have been paid to even the smallest details—for example, matching the stroke width of the original lettering in textures.

With this in mind, SGGG is a uniquely Japanese game, and we want the verisimilitude to make it feel like you're guiding Taro Sega through his daily life at SoJ and not SoA. Thus, certain things remain in Japanese, like small item textures, or the background billboards in Akihabara. Generally, though, while *you* may be reading English as you play, Taro and most of the characters are Japanese.

You'll encounter many things that are specific to Japanese culture, so rather than shoehorning those into Western concepts, we've translated them as-is. Use it as an opportunity to learn...after all, there's a whole wide internet out there (and hours and hours of video content) for you to learn about topics you may come across in the game.

Savor the experience!

With that said, the following changes have made been to bring the game to English speakers:

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
    <td>Segagaga (セガガガ)</td>
  </tr>
  <tr>
    <td><strong>Localized Title</strong></td>
    <td>SEGAGAGA</td>
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
    <td>15 hours-ish (Main Story)</td>
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
- **DO NOT USE** "v2.000" or "Rev A". Due to minor cut content, the patch was designed around v1.022 and will NOT work with v2.000.

## **Known Issues**

At this time, the only known issue is the spacing of the bluff (aka magic spells) cost in the Battle Mode bluff menu. You will notice that the numbers are a bit wider than the bluff name, and once they get to double-digits, they are indented farther in than the single-digit spell costs. We're still trying to hunt down a way to fix this, but it isn't game-breaking.

## **Extras**




## **Helpful Tips & Resources**

 - Segagaga has multiple endings and a lot of unlockable archive content that's impossible to acquire in a single playthrough. If you intend to see all of it, then expect to play through the game multiple times. If you're not a completionist but do want to see the true ending, then you'll need to acquire 100% market share.
- On your first playthrough, don't stress yourself too much when it comes to acquiring 100% market share. It is possible to achieve, but doing so requires a fair bit of knowledge of how the simulation works, which isn't likely to be quickly mastered by a first-time player. Just enjoy the story and experiment a bit in the game dev simulation to learn what you can, then apply what you learn on a subsequent playthrough if you want to try again for 100%.
- The most important thing to focus on for the first play is to simply keep the company afloat. Make sure that you don't completely run out of money and that your market share never drops all the way to 0%. If you can just survive the three-year SGGG project cycle, then it counts as a "clear," and successfully clearing the game will grant you extra money and other perks on your next playthrough, which will make achieving 100% share much easier.
- Wisely handling the company's finances is what requires the most strategy, as running out of money is what poses the biggest threat of a Game Over to a first-time player. In the very early phases, make sure that you're not spending superfluously and doing things like hiring staff at very high salaries or keeping far more staff on your research bench than what you need. Once you've released a game or two and have hopefully built up a little bit of a financial cushion, you can start spending on extras, such as equipment upgrades to develop your next games more quickly or advertising campaigns to make them sell better.

### Resources

<table>
  <tr>
    <td><strong><a href=https://archive.org/details/sggg-segagaga-perfect-file>SGGG Perfect Guide</a></strong></td>
    <td>Contains a walkthrough of the game, enemy stats, developer interviews and insights, pre-production art, reference explanations, and more.</td>
  </tr>
  <tr>
    <td><strong><a href=https://tcrf.net/Segagaga>SEGAGAGA TCRF Entry</strong></td>
    <td>A collection of interesting content that was cut from the final game but discovered in the game files.</td>
  </tr>
  <tr>
    <td><strong><a href=https://www.huga-studio.com/>HUGA Studio</a></strong></td>
    <td>If you love the vibe of SEGAGAGA, be sure to check out more of producer Tez Okano's work at his newest venture, HUGA Studio.    <br>His latest game, <a href=https://store.steampowered.com/app/3473890/THE_GIRL_FROM_GUNMA_Kai/>The Girl from GUNMA Kai</a>, is a love letter to SHMUPS and the MSX!</td>
  </tr>
</table>

Want to do your own translation of SEGAGAGA? All the tools are now available:

<table>
  <tr>
    <td><strong><a href=https://github.com/9madsheep/sggg_bin_translation2>SGGG_BIN_Translation<strong></td>
    <td>Allows for the updating of game text found in the main binary (1_SGGG.BIN).</td>
  </tr>
  <tr>
    <td><strong><a href=https://github.com/VincentNLOBJ/SGGGE>SGGGE</strong></td>
    <td>Allows for extraction and import of textures.</td>
  </tr>
</table>

## **Team Credits**

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
- Patrick Smith (Sixfortyfive)

**Texture Artists**
- Exxistance
- mr.nobody
- CWM

**Video Editing & Subtitling**
- mr.nobody
- Exxistance

**QA**
- Patrick Smith (Sixfortyfive)
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

**Patrick Smith (Sixfortyfive)**

> If you've never heard of Segagaga, it's a "Sega Simulation" for Dreamcast in which you play the role of a teenager who has been tasked to lead a floundering Sega to market dominance over their rival company Dogma, released at almost the exact same time that the real Sega formally announced their impending exit from the video game console market. It's a pretty unique concept for a video game, but when you consider that a lot of video game premises can be distilled into "young hero on a solo quest of impossible odds," I suppose it'd be more accurate to say that it's a uniquely fresh spin on a tried and true formula.
>
> It's hard to describe SGGG in broad terms. I could say that it's one part business sim, one part industry commentary, one part RPG, and one part anime shitpost, and all of that is true to some extent, but it doesn't get across the appeal. There's also not much to the "game" part of this game. The RPG part doesn't exactly have a ton of depth in strategy or resource management; the development simulation part has more to break down and optimize but becomes rather flowcharty once you do.
>
> Its appeal is laser-focused on those with an appreciation for both Sega and game dev, and not in a memberberries or romanticized way. While the player character himself is a stereotypically idealistic and optimistic hero, there's a level of frankness on display throughout the game that I think does a pretty good job of conveying the mood at the company at the time. It's clear that everybody understood that everything was on fire, but SGGG simultaneously celebrates and jokes about it.
>
> Developers themselves are portrayed as hideous creatures twisted by years of crunch, some of whom have been scapegoated for failed projects and cast aside. A whole chapter is a thinly-veiled Shenmue allegory, portraying a studio that's fallen into chaos over the course of developing their visionary director's monstrously over-budget Ultra Game. Shade is openly thrown on the Saturn's bewildering hardware design in a throwaway comment that you will not pick up on unless you fit *precisely* within this game's extremely narrow target audience.
>
> At the same time, there's plenty of reverence for Sega's body of work and both the people who make and play these games. Most of the games you create in the sim portion are actual Sega games whose info can be viewed in a gallery afterward, not unlike the trophy collection in Super Smash Bros Melee, which came out later that same year. I think it's interesting to compare and contrast how 2001 Nintendo looks toward its legacy versus 2001 Sega. Smash Bros' reverence for its featured properties is typical of Nintendo at large: thorough, polished, and sanitized. Its trophy gallery often serves as a proper museum.
>
> SGGG's game archives, by contrast, are slapdash and jokey, often punctuated by curt remarks from SGGG's sole director instead of more formal prose filtered through corporate editors. My personal favorite of these is the blurb written for the Game Gear title Phantasy Star Adventure. Apparently, Okano had at first confused this game with the Mega Drive Phantasy Star II text adventures, a higher-up caught this error during SGGG's development, and rather than actually correct this blurb to a proper comment about PSA, Okano instead just used this space in SGGG to compliment the person who caught his error. That's how loosely SGGG plays with its material and how much it expects its audience to be in on the joke, but despite that, there's still a genuine appreciation expressed toward the plethora of deep cuts on display.
>
> SGGG feels like a doujin game released by a major publisher. There's a peak "Late Night with David Letterman" level of IDGAF on display in the ways that it disregards presentation and conventions. Okano developed much of the game in secret before making a formal pitch for it to his bosses, who at first brushed him off because nobody thought he was serious. When he insisted, his superiors resisted because they felt that it didn't put Sega in a good light. When Okano further insisted on the grounds that "this will cost less than 0.01 Shenmues," they finally relented. Well, probably due to a mix of that and a "what the hell else do we have to lose" attitude.
>
> I think it's pretty matter-of-fact to argue that no other company would make a game like SGGG, simply because no other company of Sega's stature ever has. Nintendo would never make something this frank and unguarded about its own brand. Sony rarely seems to want to acknowledge anything older than The Last of Us. And by coincidence, Microsoft currently finds themselves in a position where they are also clearly rapidly scaling down their presence in the console market, but I just cannot imagine anyone at that company caring enough about its culture or mission to produce a comparable work.
>
> SGGG is a unique contradiction of a game. It's a work that simultaneously shines a light on an ugly side of game dev while also celebrating the art achieved through that adversity. There's something very human in wearing one's imperfections and failings on their sleeve like this and brandishing it for all the world to see. It's for that reason that I think the game resonates with a very particular subset of Sega fans; it thoroughly embodies the Dreamcast's experimental and niche ethos in a manner that comes across equal parts pride and regret.
>
> I came to this specific project late, after most of the heavy lifting was already done, and my contributions were mostly as a tester and editor. I'm one of presumably very few foreigners who powered through this game to 100% completion 20 years ago without even being able to read it, so I think I was most useful in just breaking the game down to the rest of the team for testing purposes, making sure that specific game mechanics are properly explained and that a number of specific Sega references are properly conveyed. That whole endgame sequence hits different when you don't know that it's coming and can only barely comprehend what's going on, and I only hope that you enjoy it half as much as I did. Hats off to everybody on the translation team for finally checking off a game that heretofore seemed to have been forever cursed to doomed and abandoned projects.
