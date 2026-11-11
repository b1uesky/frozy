# Frozy ❄️ 冰雪魔法

A wave-to-freeze motion game for little kids — **for one child or two playing together**. Play it at **https://b1uesky.github.io/frozy/**

一个给小朋友玩的"挥手冰冻"体感小游戏，一个孩子或两个孩子一起都可以玩。

## How to play / 怎么玩

- **Camera (best)** — open in Chrome on a laptop/tablet with a camera, choose 📷, stand 1.5–3 m away, and cast the screen to the TV (HDMI or AirPlay).
  - Wave over things to freeze them · fast wave = ice shards · **both hands up = blizzard** · **clap = ice shockwave**
  - Two people can play together
  - **The mirror finds them** — the laptop does not have to be aimed: the picture re-frames itself around the child, or around both children (centred, and big enough that their arms reach every bubble and the 🏠), see below.
  - **Kids drive it themselves** — the home screen is a hall of eight floating bubbles: hold a hand on a bubble for a moment to enter that game (and on 🎨 to bring a drawing to life, see below); in a game, hold a hand on the 🏠 in the top-right corner for 2 s to come back. Wardrobe, photo “continue” and “done” buttons work the same way. If the camera was allowed before, it opens as soon as the page loads. Settings live behind ⚙️ 家长设置.
- **Mouse / touch** — move to freeze, click/tap = homing ice magic, double-click = blizzard
- **TV browser (LG webOS etc.)** — arrow keys + OK = homing ice magic, color keys = blizzard

## The mirror finds them / 🔍 自动对准孩子

The camera sees a whole room; a small child is a small part of it — off to one side, low in the picture (a laptop looks *up* at her), far away. But everything she can touch is laid out for the screen. So the picture is re-framed around her.

- **Centred and sized for her arms.** Her shoulders become about 10 % of the screen width in games (arms then span almost half the screen from one spot; a raised hand reaches the 🏠, a lowered one the rooftops). Zoom is at most 2.2×, and nothing changes if she is already well placed.
- **One child or two.** With two children of about the same size (sisters of different heights) the picture is framed for both: centred between them, sized for their average, the taller one's head kept in. A grown-up next to them (much bigger) is kept in the picture but does not decide the framing.
- **Each scene has its own framing.** In the hall her face sits in the free band under the bubbles and she stands in her kingdom; freeze dance / freeze hug / freeze my home leave more room around her; when the wardrobe or a photo is up the picture comes closer and she slides so that a raised hand reaches the top row and a hand at waist height the “done / continue” button.
- **Few, slow moves.** The picture moves when it first finds her, when the scene changes, when someone walks into / out of the picture, or when she has really moved away for a couple of seconds — a step to the side to reach a bubble is not followed. It never moves while she is choosing something, during a photo countdown, or while she holds still as an ice statue; once the real room has ice on it, it only moves to keep her from dropping out of the picture.
- **Everybody stays in.** With two people the picture widens to hold both (it waits a few seconds before tightening again — a hug looks like someone leaving). Nobody for 6 s → the whole room again.
- **In the hall her own buttons move beside her** (👗 left · 📷 🎬 right, at arm height) instead of bottom-centre, where idle hands hang. And a hand hanging by her side no longer chooses anything: it has to be lifted to about her waist or held out to the side.
- The run's little camera window follows her too. A clap is now measured against her own body, not the camera picture, so it also works from far away.
- ⚙️ 家长设置 → “🔍 自动对准孩子” turns the framing off (picture and buttons are then where they were before; the hanging-hand rule and the body-relative clap stay). `__ice.FR.log` in the console lists when and why the picture moved. Tunables: `FR_GAME` / `FR_ROOM` / `FR_HALL` / `FR_PANEL` = [size, height], `FR_MAX`, `FR_HOLD`.

## Modes / 模式

| | |
|---|---|
| 🗺️ 冰雪大冒险 Ice Adventure | Fire imps → frozen town → the Fire King boss → build an ice castle |
| 🤗 冰冻抱抱 Freeze Hug | Wave or point = freeze: the animals she rescued, **and the people standing next to her**. A hug = the ice melts — to thaw dad she has to walk over and put her arms round him. Five thaws fill the hearts; the last hug becomes a photo for the album. For the whole family, nobody can lose |
| 💃 冰雕舞会 Freeze Dance | Music plays = dance; music stops = hold still and ice climbs up her body until she is an ice statue — click, a photo. Five statues make a photo strip for the album. Whole body, two can play, nobody can lose |
| 🏃‍♀️ 冰雪奔跑 Snow Run | Endless street: run in place to run, wave left/right to freeze houses, freeze fire imps and rivers that block the way, jump over obstacles. Rescue trapped animals (they run along with you), sled downhill every 500 m (lean to steer), Fire King boss every 500 m, power-ups (👢 speed boots, 💎 big ice crystal, 🧲 star magnet), day/night and weather, and two players side by side when two people are on camera (each princess wears that child’s clothes colour, copies her arms, and has a matching heart over her in the camera window) |
| 🔥 冻住小火怪 | Endless fire-imp freezing (watch for golden ones!) |
| 🏘️ 冰封小镇 | Turn the town into ice |
| ⛄ 堆雪人 | Catch snowflakes to build snowmen |
| ❄️ 冰封我家 Freeze Home | **Freeze the real room in the camera.** Where her hand goes, the real sofa, wall and shelves turn to ice, and the ice creeps on along their edges. People stay warm. Whole room frozen = indoor snow and a photo. (Mouse / TV: this bubble is 画冰花 — paint frost, hold still to grow ice flowers.) |

Towns come in three themes (village, harbor with a freezing sea, forest with mushroom houses).

## Freeze my home / 冰封我家

Every other game freezes things the game drew. This one freezes **her real living room** — the thing she already pretends to do.

- **Wave = ice.** Where her hand goes, the real picture from the camera turns to ice: it keeps its own shapes, light and dark, so the frozen sofa is still her sofa. Frost outlines the real edges, and the ice **creeps on by itself**, fastest along the edges of the furniture.
- **People are not frozen.** She (and anyone the camera recognises) stays warm and in colour inside the frozen room. A hand hanging at her side does nothing — she has to lift it or wave.
- **Far corners**: a fast wave throws an ice bolt that freezes the spot where it lands; both hands up = a blizzard that starts ice in several new places; holding a hand still grows an ice flower and a big bloom of ice. And once a patch is frozen the ice never quite stops — it finishes the room by itself in about 80 s even if she only watches.
- **Icicles** grow down from the top of the screen where the ceiling is frozen; a little house in the top-left corner fills with ice to show how much of her home is done (no numbers to read).
- **Whole room frozen** → it snows indoors, a band of light slides over the ice, 3-2-1 and a photo of her in her frozen home goes into 📷 相册. Then the ice melts from the top and the next round freezes in a new colour (blue → teal → violet). 🧽 melts it right away.
- Needs the camera picture ("🪞 显示我自己" on). On a computer that turns out to be slow at it, the ice is drawn at half resolution automatically.

## Freeze hug / 冰冻抱抱

Every other game is her and the screen. This one is her and **the people next to her** — and it ends in a real hug.

- **Freeze the animals.** Two of the animals she rescued stand beside her. A hand on one (or an arm stretched out towards it) freezes it into an ice block, and a heart starts beating over it: *hug me*.
- **A hug melts the ice.** Both arms round the block (or one warm hand resting on it for a moment) — it thaws, hearts fly, one of the five hearts at the top fills, and the animal hops round to her other side.
- **Freeze dad.** When someone else is in the picture next to her: stretch an arm out towards them and **a stream of ice flies from her hand** — or touch them, or throw ice bolts with a fast wave — and ice climbs from the floor up their body until they are frozen, with a heart beating over their head. Grown-ups can freeze her too.
- **Only a hug thaws a person.** The game cannot do it for her: she has to walk over and hug them (the camera sees two people become one). No hug? The ice melts by itself after about 10 s — no heart, nobody is stuck.
- **Five hearts** → the picture taken at the last hug (a hug with a person is kept over a hug with an animal) goes into 📷 相册 with a heart frame.
- Snowy shows both moves without a word: a wave, then arms closing round a little ice block that turns into a heart.
- Stand side by side, not one behind the other — from the camera, someone right behind her looks like someone hugging her, so nothing is frozen then.
- Mouse / touch / TV remote: click an animal twice (or wiggle over it) = freeze, click again (or rest on it) = hug. Animals only; no photo without the camera.

## Freeze dance / 冰雕舞会

Every other game is "wave a hand at a target". This one is her whole body, and it turns the idea around: **she** is the one who gets frozen.

- **Music plays → dance.** Party lights swing with the beat, Snowy dances beside her, and the animals she rescued hop along — they hop when she moves and stop when she stops. Dancing earns stars.
- **Music stops → freeze!** The room turns cold, Snowy becomes an ice block at once (that is the cue — no reading needed), and while she holds still **ice climbs from the floor up her body**. Wiggle and it slides back down a little; it never fails, and after 10 s it forms anyway.
- **Ice statue → click.** When the ice is over her head she is a statue: a photo of the pose pops up and flies into the strip at the top.
- **Five statues** → the five photos become one keepsake picture, saved in 📷 相册 (save it as a JPG from there).
- Two children each get their own ice — the one who holds still freezes first, and then the ice comes for the other one too. Grown-ups can join.
- It only needs to know "moving or not", so it is forgiving of rough tracking. Mouse / touch / TV remote: moving the pointer (or pressing keys) = dancing, resting = freezing; no photos without the camera.

## Snowy the snow buddy / 雪团团

A five-year-old can't read the hint text, so a little snow buddy **shows** her instead of telling her — and never talks:

- In the hall it floats beside her and **copies her arms** (she raises a hand, it raises a hand). Wave a hand over it and it spins and giggles.
- If she hasn't picked a game after a few seconds, it flies to a bubble and **holds its own hand on it** — the same white ring fills, the bubble wiggles — then comes back and waves: your turn.
- When a game or an adventure level starts it **acts out the move**: wave to freeze, hold a hand on a house, reach up to catch, run in place, wave left / right, jump, lean on the sled, hold a hand on 🏠 to go home.
- If she stops and nothing happens for ~11 s, it comes back and shows the one move she needs right now (e.g. *jump* when an obstacle blocks the road).

Camera mode only for the coaching; switch it off with 🤍 雪团团 in 家长设置.

## Her ice kingdom / 我的冰雪王国

The bottom of the hall is the child's own kingdom, and it remembers what she did: every finished adventure adds an **ice castle**, every frozen town an **ice house**, every snowman she builds stands there, every **rescued animal** moves in and wanders about, and every 30 stars grows a **crystal tree**. New things pop in one by one when she comes back from a game. Empty spots show a dashed outline with the bubble icon of the game that fills them. Everything reacts to a hand (or mouse/finger): animals hop, crystal trees ring like a xylophone, the castle sets off fireworks. Saved in this browser only.

## Drawings come alive / 🎨 画的小伙伴活了

Everything else in the game was drawn by the game. Here the child draws a friend **on paper**, holds the sheet up to the computer — and it comes off the paper, comes alive, and moves into her kingdom.

- **How.** Hold a hand on **🎨 画画** in the hall (next to the wardrobe). The screen becomes a patient mirror with a dashed frame; Snowy holds up a little drawing of its own to show what to do. Hold the sheet up a step or two from the camera: its outline lights up, **3-2-1**, a flash — the drawing is cut out like a sticker (white edge, the paper's shadows and the lamp's colour taken out), turns round to face her, and hops. *“✨ 活啦！”*
- **It waits.** Nothing happens until a drawing shows up, however long the drawing takes. One child or two: each sister brings her own sheet (two sheets in view are taken one after the other), and the same drawing is only taken once per visit. About 14 s after the last one the game goes back to the hall by itself.
- **Where the friends go.** They live in the kingdom (rocking and hopping at the front, a little bigger than the animals; touch one: a heart and its own little voice; they are tucked in at night like everyone else). The two newest come to the **freeze dance** and are the ones to freeze and hug in **freeze hug** — one each for two sisters. Up to 8 are kept; the oldest goes home when a ninth arrives.
- **How it finds a sheet.** No new recognition of the child: the finder looks for *something bright that was not in the room a moment ago, four-sided, with something drawn inside it* (so a pale wall, a white sofa or a picture on the wall are not sheets). A blank sheet is refused; a sheet too far away gets “closer”, one pressed against the lens gets “a step back”. A white T-shirt with a print is told apart when the camera sees her shoulders and hips inside the patch.
- **For grown-ups (when it is not found):** **📸** top right (or the space bar) takes whatever is inside the dashed frame after 3-2-1 — a page coloured in edge to edge, dark paper or a toy becomes a little framed card instead of a cut-out; **🖼️** takes a photo from a file. Without a camera (mouse / touch / phone) 🎨 shows one big “choose a photo of a drawing” button — on a phone that is its camera.
- **Privacy.** The cut-outs are small pictures kept in this browser only (`localStorage` `iceMagicFriends`), never uploaded. ⚙️ 家长设置 lists them: tap one to send it home.
- Works best with white paper and thick markers / crayons. Not on TV browsers (no camera, no files).
- Tunables: `DR_BIG` (how much of the picture the sheet must fill), `DR_NEW` (how different from the remembered room), `DR_INK`, `DR_SAT`, `DR_KEEP` (8), `DR_SHOW` (length of the “alive” moment). Code: `drFindPaper` / `drCut` (pure pixel functions), `drScan`, `drTake`, `drAlive`, `updateDraw`, `drawDrawBack` / `drawDrawFront`, `drFriendDraw`.

## The rainbow hunt / 🌈 彩虹寻宝

Every other game keeps the children in front of the screen. This one sends them away from it.

- In the hall, choose **🌈 寻宝** (next to 🎨; key `0`). Snowy looks at the room for two seconds, then asks for a **colour** — a big gem of that colour (things of that colour drift through it, for children who cannot read "red"), the edge of the screen glows in it, and one band of an empty rainbow over the room lights up.
- The children go and find **something of that colour** anywhere at home — a toy, a cup, a sock — and hold it up a step or two from the camera. It is frozen into an **ice gem** (a little picture of the real thing inside), its colour shoots up into the rainbow, 3 stars. Any colour the rainbow still needs counts, not only the one asked for — the little sister may bring whatever she likes.
- All the colours (3 to 5) = **a rainbow**: a photo under it goes into the album, and the rainbow moves into the kingdom, over the castle hill.
- It never times out (they may be gone for minutes) and nothing can be lost. It needs **no pose at all** — carrying a thing to the screen is something a two-year-old can do — and it works the same for one child or two.
- **How it sees**: eight times a second it looks at a 160×90 copy of the camera picture for six colours (red, yellow, green, blue, purple, pink — the warm band of orange / brown / skin / wood is left out on purpose). Before it asks, it notes which colours the room already has and where, and what the children are wearing; it asks for colours the room does not have, and "found" = a **new** patch of that colour, big enough (about a 12 cm toy at 1.5 m), for a third of a second. A face is never a find.
- **Grown-ups**: **📸** (or the space bar) = "that counts" — whatever is in the middle of the screen becomes the gem; **⏭️** (or `X`) = "we have nothing in that colour, ask for another". Bright, solid-coloured things about the size of a hand or bigger are found best.
- Only with the camera (there is no mouse or TV version). The gems are not kept; the photo is (in this browser, like every photo).
- Checked on **real photographs** this time, not only drawn pictures: 70 real living rooms and 56 real coloured objects from the COCO photo set, with the camera's exposure and white balance wandering — see the project notes for the numbers. Still **not** checked with the real camera, the real room and the real children.

## Good night, Ice Kingdom / 晚安，冰雪王国

Games are built to keep a child playing. This part helps her **stop** — and makes stopping something she does herself, not something that is done to her.

- **A grown-up decides when**: click 🌙 (top right, camera mode) or press **N**, or pick a play time (10 / 15 / 20 / 30 min) in ⚙️ 家长设置.
- **A sleepy moon rises** over whatever she is playing and the screen slowly dims — "a little more, then good night". Snowy yawns and stretches. (About 40 s on the timer, 12 s when a grown-up asks; ask again = right now. A dance or the last adventure level may finish first.)
- **The hall turns to night.** The game bubbles are gone; every animal, house, snowman, crystal tree and castle in her kingdom has a little light. **She touches a light, it goes out, and the one inside falls asleep** — each one plays the next note of a lullaby.
- It can't be failed and it always finishes: Snowy shows how on the first one and keeps tucking them in whenever she pauses.
- **Both hands up → the aurora** (tap the sky or Space without a camera; it lights by itself after a while). Then everyone sleeps, Snowy puts on a nightcap, the screen dims, and there is nothing left to do. A small line tells the grown-up how long she played.
- **A little longer?** Hold "☀️ 再玩一会儿" at the bottom (or press N). With a play time set, that gives 5 more minutes.
- **Next time the page opens, the kingdom wakes up** — a sunrise, and everyone hops awake one after another.

## The magic movie / 🎬 魔法电影

Everything she does in the games happens once and is gone. This keeps it — and gives the best part of the day to the moment she stops.

- **It records by itself.** While she plays with the camera on, the game quietly holds on to the last few seconds. When something good happens — a blizzard, an ice statue, a hug, the whole home frozen, a level won — those seconds become a clip (at most 12 are kept, the best ones from each game).
- **Bedtime premiere.** In the good-night ritual, once she has lit the aurora, "today's movie" plays in the night sky: a title card, up to six clips of *her* doing magic, a music-box tune, an end card with today's stars (about half a minute). Then everyone sleeps. No clips → bedtime goes exactly as before.
- **Any time, from the hall**: hold a hand on "🎬 电影" (it appears once there is a clip). Snowy sits beside the screen and watches too; a hand on 🏠 (top right) or Esc closes it, and it closes by itself at the end.
- **For grown-ups: "💾 保存视频"** (bottom left while the movie plays, or "🎬 保存今天的电影" under the sleeping kingdom) saves it as a 1280×720 video file (MP4 where the browser can, otherwise WebM) to send to family.
- **Private**: the clips live only in this browser (IndexedDB), nothing is uploaded, only the latest day is kept, and "🎬 魔法电影" in ⚙️ 家长设置 switches it off and deletes them. Camera mode only — nothing is recorded with mouse / touch / TV.

## The play report & the helping hand / 📋 试玩报告 · 🪄 帮一把

Every feature above was built and checked in a headless browser with a pretend camera — never with the real camera, the real TV and real children. So the game now **measures real play itself**.

- **It counts, while they play**: can she choose a bubble with her hand (chosen / "nearly" / helped), who starts the games and who goes back to the hall (her hand, or a grown-up's click), frames per second, how often the pose model looks, how much of the time it sees someone, how big she is in the picture and where she ends up on the screen after the picture has framed her, how much the tracked points tremble, how close a hand ever comes to the 🏠, and per game: time, stars, how often Snowy had to come back because she had stopped; freeze dance (how long until a statue, how often the 10 s limit was needed, how much she "moves" while holding still), freeze hug (hugs recognised vs. ice that thawed alone), freeze my home, drawings (taken automatically vs. by the grown-up's 📸), the movie, the framing moves, good night. And any error the page hit.
- **Numbers only** — counts and averages, no pictures, no sound. They stay in this browser (`localStorage` `iceMagicReport`, the last 4 sittings) and go nowhere by themselves.
- **⚙️ 家长设置 → 📋 试玩报告** (also on the sleeping screen after good night): a few plain lines of what stands out (✅ / ⚠️ — "maybe", not a verdict), the full report as text, **Copy** (paste it to Claude, who uses it in the next round instead of guessing), **Share** where the browser has it, and **QR to my phone**: the whole report is packed into the page's own address (`#r=…`, deflate + base64) and shown as a QR code; the phone opens the same page, which shows the report with Copy / Share. Nothing passes through a server.
- **🪄 The helping hand**: when the ring on a bubble / button / 🏠 got well on its way (35 %) and her hand slipped off, that is a near miss. Two near misses on the same thing in a row and it **helps**: it grows and glows gold, reaches twice as far for her hand, fills 30 % faster and forgives a wobble (the ring drains three times slower). It goes back to normal when she has chosen it, or about 12 s after she stops trying. A hand just passing by is never a near miss.
- Code: `RP` / `rp(key)` / `rpV(key, value)` (the counters, sprinkled through the code), `rpFrame` / `rpPose` (per frame / per look of the pose model), `rpText` / `rpNotes` (the report), `qrMake` (QR encoder, byte mode, level L — checked bit for bit against a reference library), `rpPack` / `rpUnpack`; the helping hand lives in `updateDwell` (`DW_NEAR`, `DW_MEM`, `DW_HELP`, `.help`).

## Extras

- 👑 **Dress-up** — with the camera on, she wears an ice crown and a cape that flows *behind* her
- 👗 **Wardrobe** — stars are saved across sessions and unlock 6 cape colors and 4 crowns
- 📸 **Photo booth** — 3-2-1 photo with crown & cape (press P or the 📸 button); a champion photo is taken automatically after the adventure. Photos stay in this browser and can be saved as JPG

Pose tracking uses [MediaPipe Pose Landmarker](https://developers.google.com/mediapipe) in the browser; video never leaves the device. Everything is a single `index.html`.
