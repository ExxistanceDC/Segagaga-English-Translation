<div align="center"><strong>The SGGG Translation Team proudly presents</strong></div>

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/3fdf7d98-c9f7-48be-9d77-e9c467fea1f2">
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/user-attachments/assets/a4e4db4d-efde-4b14-8472-9d5adaf45f90">
  <img alt="SGGG 25th Anniversary Logo" src="https://github.com/user-attachments/assets/a4e4db4d-efde-4b14-8472-9d5adaf45f90" width="700">
</picture>
</div>
<br>
<br>

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
1. [Overview](#Overview)
1. [About the Game](#About-the-Game)
1. [Screenshots](#Screenshots)
1. [Patching Instructions](#Patching-Instructions)
1. [Extras](#Extras)
1. [Helpful Tips & Resources](#Helpful-Tips--Resources)
1. [Known Issues](#Known-Issues)
1. [Team Credits](#Team-Credits)
1. [Messages From the Team](#Messages-From-the-Team)
1. [AI Notice](#AI-Notice)
1. [Reporting Issues](#Reporting-Issues)

## **Overview**
This patch fully translates SEGAGAGA into English. Our aim was to produce a faithful translation of both the source text and the original art. Care and attention have been paid to even the smallest details—for example, like matching the stroke width of the original lettering in various textures.

With this in mind, SGGG is a uniquely Japanese game, and we want the verisimilitude to make it feel like you're guiding Taro Sega through his daily life at SoJ and not SoA. Thus, certain things remain in Japanese, like small item textures, or the background billboards in Akihabara. Generally, though, while *you* may be reading English as you play, Taro and most of the characters are Japanese.

You'll encounter many things that are specific to Japanese culture, so rather than shoehorning those into Western concepts, we've translated them as-is. Use it as an opportunity to learn...after all, there's a whole wide internet out there (and hours and hours of video content) for you to learn about topics you may come across in the game.

Savor the experience!

With that said, the following changes have made been to bring the game to English speakers:

- All in-game dialogue translated
- All chapter dialogue translated
- All cutscenes subtitled in English
- End credits translated
- All 500+ in-game UI textures redrawn in English
- Title Screen/Options/Chapter Interstitial screens redrawn in English
- All VMU save and application metadata translated in Dreamcast's BIOS menu save manager
- 25th Anniversary celebration added to opening splash screen
- New 25th Anniversary VMU icon during gameplay
- Original instruction manual translated and redrawn in faithful style to the original

## **About the Game**

<div align="center">
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
</div>

## **Screenshots**

<div align="center">
<!-- Row 1 -->
<p>
  <img src="https://github.com/user-attachments/assets/9fd1ba5d-f831-4622-a516-c68865e4438b" width="500"/>
  <img src="https://github.com/user-attachments/assets/f9b6805e-4ba6-4bec-a243-5ed6b7841be9" width="500"/>
</p>
<!-- Row 2 -->
<p>
  <img src="https://github.com/user-attachments/assets/88947cfc-bcf5-419e-8bc4-cf9d583a8b37" width="500"/>
  <img src="https://github.com/user-attachments/assets/826ab780-fc58-45c0-b642-fed2b45e7716" width="500"/>
</p>
<!-- Row 3 -->
<p>
  <img src="https://github.com/user-attachments/assets/88e0d6af-0c6e-415b-a9e6-9f6a47698ef1" width="500"/>
  <img src="https://github.com/user-attachments/assets/8ff55afa-6c1a-4a6e-a63c-b210eb0066e6" width="500"/>
</p>
<!-- Row 4 -->
<p>
  <img src="https://github.com/user-attachments/assets/7a49b160-32dd-48fb-ad6a-f72a961dd49b" width="500"/>
  <img src="https://github.com/user-attachments/assets/286f9e0c-ce02-4697-84ad-0891832dd6fb" width="500"/>
</p>
</div>


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
- **DO NOT USE** "v2.000" or "Rev A". Due to minor cut content, the patch was designed around v1.022 and will **NOT** work with v2.000.

## **Extras**

<table>
  <tr>
    <td><strong><a href=https://drive.google.com/file/d/1hrho1FihtNJyj3ZNnAJfHPTK5VFardF4/view?usp=drive_link>SEGAGAGA Instruction Manual</a></strong></td>
    <td>A complete recreation of the Japanese instruction manual that came with the game.</td>
  </tr>
  <tr>
    <td><strong><a href=https://drive.google.com/file/d/11eq7V604YsSefWKNfcdR4zhCaAuWkZas/view?usp=sharing>SGGG Papercraft</a></strong></td>
    <td>Originally hosted on Hitmaker's website, the SGGG papercraft lets you build your own SEGA consoles from paper.</td> 
  </tr>
</table>

## **Helpful Tips & Resources**

### **Helpful Tips**

 - All currency in SEGAGAGA is denominated in yen (¥). Once your development budgets become sufficiently large, you'll start to encounter number formats that have no direct equivalent in English. For example, Japanese uses 万 to represent “10,000,” and 億 to represent “100,000,000.” The closest English analogues would be something like “K” for thousand or “MM” for million, but there’s no true one-to-one match.
Since we don’t have access to the game’s source code, tracing and converting every internal calculation into an English-style numbering system wasn’t feasible. Instead, we created a simple letter-based notation to help you interpret yen amounts. For example, if you see a value such as 10T200¥, that corresponds to 100,200 yen. So, remember:

<div align="center">
<table>
<tr>
  <td><strong>T</strong></td>
  <td>10,000 ¥</td>
</tr>
<tr>
  <td><strong>M</strong></td>
  <td>100,000,000 ¥</td>
</tr>
</table>
</div>
 
 - SEGAGAGA has multiple endings and a lot of unlockable archive content that's impossible to acquire in a single playthrough. If you intend to see all of it, then expect to play through the game multiple times. If you're not a completionist but do want to see the true ending, then you'll need to acquire 100% market share. (c/o Sixfortyfive)
- On your first playthrough, don't stress yourself too much when it comes to acquiring 100% market share. It is possible to achieve, but doing so requires a fair bit of knowledge of how the simulation works, which isn't likely to be quickly mastered by a first-time player. Just enjoy the story and experiment a bit in the game dev simulation to learn what you can, then apply what you learn on a subsequent playthrough if you want to try again for 100%. (c/o Sixfortyfive)
- The most important thing to focus on for the first play is to simply keep the company afloat. Make sure that you don't completely run out of money and that your market share never drops all the way to 0%. If you can just survive the three-year SGGG project cycle, then it counts as a "clear," and successfully clearing the game will grant you extra money and other perks on your next playthrough, which will make achieving 100% share much easier. (c/o Sixfortyfive)
- Wisely handling the company's finances is what requires the most strategy, as running out of money is what poses the biggest threat of a Game Over to a first-time player. In the very early phases, make sure that you're not spending superfluously and doing things like hiring staff at very high salaries or keeping far more staff on your research bench than what you need. Once you've released a game or two and have hopefully built up a little bit of a financial cushion, you can start spending on extras, such as equipment upgrades to develop your next games more quickly or advertising campaigns to make them sell better. (c/o Sixfortyfive)

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
    <td><strong><a href=https://github.com/9madsheep/SGGG_MES/releases/tag/main)>SGGG_MES</strong></td>
    <td>Allows for updating text found in SGGG's MES files (pre and post-chapter dialogue scenes).</td>
  </tr>
  <tr>
    <td><strong><a href=https://github.com/VincentNLOBJ/SGGGE>SGGGE</strong></td>
    <td>Allows for extraction and reinsertion of SGGG's textures.</td>
  </tr>
  
      
</table>

## **Known Issues**
<img align="right" width="275" src="https://github.com/user-attachments/assets/f553e417-1ba1-4a74-a330-888f0dd31c7e" />
At this time, the only known issue is the spacing of the bluff (i.e., magic spell) costs in the Battle Mode bluff menu. Once the spell cost is double digits, they are indented farther left than the single digit spell costs. We're still searching for a way to fix this, but it isn’t game-breaking.

<br>
<br>
<br>
<br>
<br>
<br>

## **Team Credits**

**Project Lead**
- Exxistance

**Romhacking / Tooling**
- megavolt85
- MadSheep
- <a href=https://www.patreon.com/VincentNL>VincentNL</a>
- <a href=https://dreamcastforever.com/>Derek Pascarella (ateam)</a>

**Translation / Review**
- Exxistance
- <a href=https://lostinlocalization.com/>LostinLoc</a>
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

**Manual Recreation**
- Exxistance

**My Deepest Thanks**

- **My SGGG teammates** (seriously, you all are amazing and it has been a joy to work with you!)
- **Tez Okano and the original development team** (for putting your heart, soul, and time into making a unique game that has entranced a fanbase for 25 years.) 
- **MoriyaMug** (who doesn’t know me at all, but whose dedication to the Samurai Shodown RPG translation shows that passion and willpower can make all the difference in a project. Thank you for bringing SSRPG to English and fulfilling a 20+ year dream of mine to play it.)
- **Those Who Came Before** (A huge thank you to those who came before and paved the way with all the Segagaga artifacts that they left on the Internet. The 1 Ross and the SGGG Open Source Translation project, Prof_Rev and kinsukeJP of GameFAQs with their guides).
  
## **Messages From the Team**

**Exxistance**
> I’ve been a SEGA fan since I was a kid. Though my first video game console may have been an NES, I still vividly remember first experiencing Altered Beast on the Genesis at my friend’s house. The Genesis was such a step up from the NES, the games so *cool*, that it led me to buying my first SEGA console–the Game Gear (the only one I could afford, and which I bought via layaway at Kmart). 
> 
> Many years later, when the Model 1 and 2 boards were wowing me at the arcades during my formative teenage years, the Saturn arrived with the enticing promise of bringing those arcade experiences to the home. I was exactly the kind of buyer SEGA wanted: someone not burned by their previous hardware flops, the 32X and Sega CD. The Saturn represented the beautiful 32-bit future in my eyes and “arcade perfect” Virtua Cop at home. I had a lot of love for Saturn–and still do. (Thanks to the vibrant translation community, I find myself enjoying it even more these days, thanks to previously Japanese-only games receiving English translations.)
> 
> With this historical context in mind, every few years I’d do some googling about the latest news of a Segagaga translation. Over a holiday break in December 2024, I found myself reading through a thread about Segagaga on Dreamcast-Talk. Somewhere between the hopeful posts and despairing ones, there were a few individuals talking about things like *tools* and *data extraction*. One of these individuals posted a texture extraction tool, and in my boredom, I decided to download it and take a quick look at Segagaga’s textures.
> 
> And that decision right there–just a small, random moment of boredom–is a key reason why you’re playing Segagaga in English right now.
> 
> You see, while my day job is *not* in graphic design, I studied it in high school and college, and so I like to spend my free time making game covers for SteamGridDB and such. When I started looking through SGGG’s textures, I realized that the game had an enormous amount of text baked into the textures, much of it as user interface elements. All the primary actions of the player, for example, are drawn into the UI rather than being simple text elements that can be updated in the game files. Merely translating the game text alone would not provide a player with the context they need to comfortably play the game in English. 
> 
> I decided to do a test. I would edit one of the textures in Photoshop, and use Flycast’s texture replacement feature to insert it into the game. And lo and behold, it worked beautifully. I was looking at an English-readable texture in Segagaga! This, however, was only the first step in what would be a year-long journey.
> 
> I started extracting all the textures and figuring out which needed translation. My thought was, I’ve got my 25 year-old Photoshop skills, I like using them in my spare time, so this should be a therapeutic hobbyist project. And at the very least, I’ll remove at least one barrier for anyone else in the future that may want to tackle the rest of the game. I looked at the list of 500+ textures and started pulling a few of the core ones to get started.
> 
> While the prospect seemed daunting, I was enjoying the work. And a funny thing happened along the way. As I started posting regular updates in Dreamcast-Talk, people started reaching out to me. One of those people was mr.nobody, who immediately jumped in to help redrawing the textures. mr.nobody also spun up a Discord server and started connecting the key players together. Translators jumped in. Playtesters. This translation became a worldwide effort, with people across the globe working together to finally bring Segagaga to English-speaking audiences.
> 
> For all the bad the Internet has wrought, it’s projects like these that renew my faith in it. No one had to help out. For some Dreamcast hackers, RPGs aren’t even their favorite genre. But they helped nonetheless, perhaps because they love the Dreamcast, or they love the challenge, or they love gaming. Whatever the reason, they put their faith in me — some random stranger on an Internet forum — to help get this project to the finish line.
> And so, nearly every day since January, I’ve been working on SGGG. It’s a little bittersweet that the project is coming to an end, as it’s been a source of great joy for the past year. It’s given me a motivation I didn’t know I needed, helped push my design skills farther, and helped me crack ROM hacking concepts that I had always struggled to learn. Though it's coming to a close, I’m excited to see the fans who have clamored to play SGGG in English for so long finally get to enjoy it in the same way I have throughout the past year. The game is better than I had expected before starting this project; it’s so much deeper and more nuanced than the “SEGA references game” I anticipated, and I hope you discover the same.

**Derek Pascarella (ateam)**
<blockquote>
<p>Segagaga has something of a sordid history in the fan translation scene. At least two separate groups have made sincere (public) attempts to develop a full English localization patch over the years, though of course neither saw the project through to completion.</p>
<p>For a while now, there’s been a thread on the Dreamcast-Talk.com forums where several of us have shared technical bits and pieces about Segagaga in order to amass and preserve such knowledge should any group decide to tackle patching it. Collectively, we had native ASCII support (including a half-width font tile spacing hack), tools to extract/rebuild archives using custom compression, as well as a text extractor/rebuilder.</p>
<p>It might be worth noting that I myself considered endeavoring to lead this project myself once or twice, but I stopped myself for a number of reasons beyond the scope of this write-up.</p>
<p>Though at some point along the way, Exxistance saw what was available to him and decided he would do something about it. Once his project started gaining some momentum, Mr. Nobody reached out to see if I could potentially assist with things like hacking or tool writing. While many of you might know me for the many English translation patches I’ve developed for the Dreamcast (and other platforms) over the years, my free time as of writing this message is at an all-time low. As a result, not only was there zero chance of me leading this project, but I felt the odds of me being able to contribute anything meaningful to it were quite low too.</p>
<p>That assumption turned out to be untrue, however.</p>
<p>While I may have done a lot less for this project than I’d have liked, I’m happy that I was able to contribute a few key things that helped the patch finally see a release…</p>

<ul>
  <li>
    <strong>Ability to edit font glyphs</strong><br>
    One of the biggest challenges this game presented to prospective patch developers has been its use of the BIOS font. See, rather than the game bundling in its own font sheet in some format that hackers can easily write tools to edit (e.g., insert their own Latin alphabet glyphs), Segagaga speaks directly to the Dreamcast’s BIOS when it comes time to render text on screen. After megavolt85 did all of the assembly hacking to force the game to interpret ASCII-encoded text and then pull from the ASCII section of the BIOS font (rather than Shift-JIS), I started poking around a bit to see how it all worked.

What I discovered is that the game actually copies the entirety of the BIOS font into RAM pretty near the location where the game executable ends! So, I disabled the assembly code that performed this copy, then also disabled the code that null’d out that portion of RAM before doing the copy. I then appended the BIOS font to the end of the game executable, and just like that, the font data was precisely where the game expected it to be, and it could be modified! This came in handy a number of times as font glyphs needed tweaking for optimal appearance.
  </li>
</ul>
<ul>
  <li>
    <strong>Ability to expand available space for executable-embedded text strings</strong><br>
    After the modifications to the font system described above, I realized that we now had tons of free space in the game executable. Why, or how? Well, because only a fraction of all of that BIOS font data (i.e., ASCII) was actually being used, the rest of that space could be repurposed (i.e., where Shift-JIS once was).

Because of this, I was able to give the team a giant, static place in memory where the game’s many, many executable-embedded text strings could now be safely written. If not for this hack, there’d be not nearly enough room to store the translated versions of those strings, resulting in a much poorer quality presentation.
  </li>
</ul>

All of that being said, the real credit belongs to Exxistance and the rest of the team who worked so tirelessly to see their vision through to completion.
While this English translation patch release for Segagaga isn’t absolutely perfect, it’s very, very good, and there’s a saying: don’t let perfect be the enemy of good.
There are a few minor text alignment issues here and there, as well as a limitation for maximum number of characters printed per line in a dialogue box. I’d love to carve out a whole bunch of free time someday in the future to fix all of these, but honestly the prospect of doing such isn’t great.
Until then, from the bottom of my heart, I want to thank the Segagaga translation patch team, and I hope all of you, the players, enjoy experiencing it in English for the very first time.

</blockquote>

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

## **AI Notice**

Due to the importance of SEGAGAGA to the fan translation community, I think it’s important to disclose where AI was used in the development of this translation patch.

What I call the “playtesting translation” — a base translation that allowed the artists and playtesters to get started early and understand what they were working on — was developed using a combination of DeepL and ChatGPT 4o/4.5. That translation then went through a substantial, months-long **human** translator review. I think the end product doesn’t feel “machine-translated,” but that’s ultimately for you, the player, to decide.

For the purists, we’re also offering the tools used to develop the translation, so if you are a translator who wants to do your very own translation of SEGAGAGA, you now have the means to do so! Check out the [Resources](#resources) section to get them.

The beauty of the fan translation community is that people are always refining and developing new translations and giving them back to the community. Go forth and prosper!


## **Reporting Issues**

While the patch has been thoroughly tested for months and months, the universe loves a good joke, and stuff always gets through. Please report typos, mispellings, text overruns, and the like by [submitting a new issue](https://github.com/ExxistanceDC/Segagaga-English-Translation/issues/new) to this repo. 

