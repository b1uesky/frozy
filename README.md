# Frozy ❄️ 冰雪魔法

A wave-to-freeze motion game for little kids. Play it at **https://b1uesky.github.io/frozy/**

一个给小朋友玩的"挥手冰冻"体感小游戏。

## How to play / 怎么玩

- **Camera (best)** — open in Chrome on a laptop/tablet with a camera, choose 📷, stand 1.5–3 m away, and cast the screen to the TV (HDMI or AirPlay).
  - Wave over things to freeze them · fast wave = ice shards · **both hands up = blizzard** · **clap = ice shockwave**
  - Two people can play together
  - **Kids drive it themselves** — the home screen is a hall of floating bubbles: hold a hand on a bubble for a moment to enter that game; in a game, hold a hand on the 🏠 in the top-right corner for 2 s to come back. Wardrobe, photo “continue” and “done” buttons work the same way. If the camera was allowed before, it opens as soon as the page loads. Settings live behind ⚙️ 家长设置.
- **Mouse / touch** — move to freeze, click/tap = homing ice magic, double-click = blizzard
- **TV browser (LG webOS etc.)** — arrow keys + OK = homing ice magic, color keys = blizzard

## Modes / 模式

| | |
|---|---|
| 🗺️ 冰雪大冒险 Ice Adventure | Fire imps → frozen town → the Fire King boss → build an ice castle |
| 🏃‍♀️ 冰雪奔跑 Snow Run | Endless street: run in place to run, wave left/right to freeze houses, freeze fire imps and rivers that block the way, jump over obstacles. Rescue trapped animals (they run along with you), sled downhill every 500 m (lean to steer), Fire King boss every 500 m, power-ups (👢 speed boots, 💎 big ice crystal, 🧲 star magnet), day/night and weather, and two players side by side when two people are on camera (each princess wears that child’s clothes colour, copies her arms, and has a matching heart over her in the camera window) |
| 🔥 冻住小火怪 | Endless fire-imp freezing (watch for golden ones!) |
| 🏘️ 冰封小镇 | Turn the town into ice |
| ⛄ 堆雪人 | Catch snowflakes to build snowmen |
| ❄️ 画冰花 | Paint frost; hold still to grow ice flowers |

Towns come in three themes (village, harbor with a freezing sea, forest with mushroom houses).

## Snowy the snow buddy / 雪团团

A five-year-old can't read the hint text, so a little snow buddy **shows** her instead of telling her — and never talks:

- In the hall it floats beside her and **copies her arms** (she raises a hand, it raises a hand). Wave a hand over it and it spins and giggles.
- If she hasn't picked a game after a few seconds, it flies to a bubble and **holds its own hand on it** — the same white ring fills, the bubble wiggles — then comes back and waves: your turn.
- When a game or an adventure level starts it **acts out the move**: wave to freeze, hold a hand on a house, reach up to catch, run in place, wave left / right, jump, lean on the sled, hold a hand on 🏠 to go home.
- If she stops and nothing happens for ~11 s, it comes back and shows the one move she needs right now (e.g. *jump* when an obstacle blocks the road).

Camera mode only for the coaching; switch it off with 🤍 雪团团 in 家长设置.

## Her ice kingdom / 我的冰雪王国

The bottom of the hall is the child's own kingdom, and it remembers what she did: every finished adventure adds an **ice castle**, every frozen town an **ice house**, every snowman she builds stands there, every **rescued animal** moves in and wanders about, and every 30 stars grows a **crystal tree**. New things pop in one by one when she comes back from a game. Empty spots show a dashed outline with the bubble icon of the game that fills them. Everything reacts to a hand (or mouse/finger): animals hop, crystal trees ring like a xylophone, the castle sets off fireworks. Saved in this browser only.

## Extras

- 👑 **Dress-up** — with the camera on, she wears an ice crown and a cape that flows *behind* her
- 👗 **Wardrobe** — stars are saved across sessions and unlock 6 cape colors and 4 crowns
- 📸 **Photo booth** — 3-2-1 photo with crown & cape (press P or the 📸 button); a champion photo is taken automatically after the adventure. Photos stay in this browser and can be saved as JPG

Pose tracking uses [MediaPipe Pose Landmarker](https://developers.google.com/mediapipe) in the browser; video never leaves the device. Everything is a single `index.html`.
