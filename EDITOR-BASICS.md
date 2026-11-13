# GameBean Studio editor basics

Every GameBean Studio tutorial uses the same handful of editor actions over and over: start a game, set up a scene, place an object, type its position, add and remove beans, change bean settings, add a rule, draw or import a sprite, and playtest. This chapter shows each one with a picture of exactly where to click. The game tutorials point back here, so you only need to learn each action once.

The red boxes and numbers in each picture match the numbered steps under it.

---

## 1. Switch to BUILD mode

GameBean Studio opens in PLAY mode, which plays the current game. To edit:

![The PLAY and BUILD switch](images/editor/01-build-button.png)

1. Click **BUILD** at the top left of the editor panel. The editor opens. Click **PLAY** (to its left) at any time to play your game, and **BUILD** to come back.

## 2. Start a new game

![The FILE menu with New Game highlighted](images/editor/02-file-new.png)

1. Click **FILE** at the top left, then **New Game…**. (The **NEW** button at the left end of the editor toolbar does the same.)

![The New Game window with EMPTY GAME highlighted](images/editor/03-new-empty.png)

1. Click **EMPTY GAME**. You get one 320 × 240 scene with a ground strip and a hero. The other 37 cards are sorted onto shelves: **Full games** opens the finished example games (the tutorials ask you to open one of those for comparison), and the genre shelves hold 24 small starter games, explained in **[the template pack](template-pack.md)**. Type in the search box to find one by name, genre or control.

## 3. The parts of the editor

![The whole editor with its seven areas numbered](images/editor/04-overview.png)

1. **Toolbox** (left). Three tabs: **OBJECTS** (things you place on the map), **ACTIONS** and **COLLISIONS** (behavior beans you attach to a selected object).
2. **Scene bar** (above the map). The scene list, name and size, **PLAY ALL**, **MAP**, **FIND**, the scene tabs, **+ NEW SCENE**, **LEVEL SETTINGS** and **BACKGROUND & GRAPHICS**.
3. **Map** (middle). Your scene. Click an object to select it, drag it to move it.
4. **Object Inspector** (right). Everything about the selected object: name, sprite, position, size, beans and rules.
5. **Editor toolbar** (top). File buttons (New, Open, Save, Export, Game), Undo and Redo, the creative tools (AI Builder, Music, Audio, Scene Studio, Entity Studio, Variables, Dialogue) and the test tools (Check, Debug). See step 19.
6. **Map toolbar** (just above the map). Select, Brush, Paint, Pan, Snap, View zoom, Fit and Screen size. See step 19.
7. **PLAY / BUILD** switch.

## 4. Name and size a scene

![The scene name, W and H boxes](images/editor/05-scene-name-size.png)

1. Click in the **scene name** box (the second box in the scene bar, after the LEVEL list), select the old name and type the new one.
2. Click in **W** (width in pixels) and type the width. One screen is 320 wide.
3. Click in **H** (height in pixels) and type the height. One screen is 240 tall.

Press **Tab** or click somewhere else after typing a number so the editor takes it.

## 5. Scene settings: camera, palette, sky, weather and intro

![LEVEL SETTINGS and the scene settings it shows](images/editor/06-scene-settings.png)

1. Click **LEVEL SETTINGS** in the scene bar. The settings open under it (click it again to hide them).
2. **CAMERA**: open the list and pick **Follow player** (scrolls with the hero), **Snap rooms** (one 320 × 240 room at a time) or **Fixed**. The X and Y boxes beside it set where a fixed camera points.
3. **CARRY HEALTH+SCORE**: tick this box so the hero keeps hearts and score when arriving in this scene from another one.
4. **PALETTE**: the four colours this scene draws with. Your own palettes appear here after you make them (step 7).
5. **SKY**: the backdrop behind everything.
6. **HORIZON**: the silhouette layer (city, hills, none…).
7. **WEATHER**: particles such as fireflies, snow, rain or embers.
8. **INTRO**: the banner text shown when the scene starts. Click in the box and type.

## 6. Add a second scene and switch between scenes

![The scene tabs and + NEW SCENE](images/editor/07-scene-tabs.png)

1. Each scene has a tab (**01 …**, **02 …**). Click a tab to edit that scene.
2. Click **+ NEW SCENE** to add a scene. It opens as the new current tab; name and size it as in step 4.

## 7. Make your own palette

![Scene Studio with MAKE OR EDIT PALETTES highlighted](images/editor/08-scene-studio.png)

1. Click **SCENE STUDIO** in the editor toolbar (or **BACKGROUND & GRAPHICS** in the scene bar), then click **MAKE OR EDIT PALETTES…** under the palette swatches.

![The palette window with Classic selected and COPY highlighted](images/editor/09-palette-copy.png)

1. Under **BUILT IN**, click any palette (for example **Classic**).
2. Click **COPY**. A copy appears under **YOUR PALETTES** and is selected.

![Editing the copied palette](images/editor/10-palette-edit.png)

1. **NAME**: select the text and type the palette's name.
2. to 5. Click each colour square (**Ink**, **Dark**, **Light**, **Paper**). Your system colour picker opens. Type the hex code from the tutorial (for example `#1b2a24`) into its hex field and close the picker. On a Mac, the hex field is under the sliders tab (choose **RGB Sliders**); in Chrome it is the box under the colour area. The hex code shows next to each square so you can check it.
3. Click **USE FOR THIS LEVEL** to use the selected palette for the current scene.

**FROM IMAGE…** makes a palette from a picture, and **Preview in grayscale** checks that the four shades stay easy to tell apart.

Close the window with **×**, then click **DONE · EDIT SCENE MAP** to leave Scene Studio. You can also pick a palette for a scene later from the **PALETTE** list (step 5).

## 8. Place an object

![The Toolbox with OBJECTS and Checkpoint highlighted](images/editor/11-toolbox-pick.png)

1. Click the **OBJECTS** tab in the Toolbox.
2. Click the kind of object you want, for example **Checkpoint**.

![Clicking the map to place the object](images/editor/12-map-click.png)

3. Click the map where the object should go. It does not have to be exact; you type the exact position next (step 9).

![The DONE button and the Select tool](images/editor/12b-done.png)

4. The editor stays in placing mode, so **every further click on the map places another one**. When you have placed what you need, click **DONE** in the bar under the map (or **Select** in the map toolbar, or press **Esc**).

If you placed one too many, click **UNDO** in the editor toolbar or press **Ctrl+Z** (**⌘Z** on a Mac).

## 9. Name an object and type its position and size

Click the object on the map to select it (or find it with **FIND**, step 17). The Object Inspector shows it.

![The top of the Object Inspector](images/editor/13-inspector-top.png)

1. **Name**: click the name, select it and type the new name. The tutorials give every object a name so you can find it again.
2. **SPRITE** opens the sprite editor (step 15).
3. **SAVE ENTITY** saves this object, beans and sprite included, to your Toolbox (step 16).
4. **Duplicate** makes a copy next to it.
5. **Delete** removes it (the **Delete** key does the same).
6. to 9. **X**, **Y**, **W**, **H**: click each box, select the number and type the new one. X and Y are the top-left corner in pixels, W and H the width and height.

When a tutorial writes `x 64, y 120, w 12 × h 16` (or `64, 120, 12 × 16`), type 64 in X, 120 in Y, 12 in W and 16 in H.

## 10. Bean cards: turn off, reorder, remove and change settings

Each bean attached to an object is a card in the inspector under **ATTACHED BEANS**.

![A bean card with its controls numbered](images/editor/14-block-card.png)

1. **On/off switch.** Click the coloured square to switch the bean off (it goes grey) or back on. A switched-off bean does nothing until a rule or chest switches it on.
2. The bean's name and a one-line summary of its settings.
3. **?** opens the bean's help: what it does, when to use it, and a tip.
4. **Reset** puts every setting back to its default. It only appears once you change a setting.
5. **Copy** the bean (you can paste it on another object with the paste button next to ADD ACTION).
6. **Move up** and 7. **Move down**. Beans run top to bottom; when a tutorial says "move it to the top", click the up arrow until it is first.
7. **×** removes the bean from the object. Tutorials say "remove Gravity" for this.
8. **Settings.** Type numbers into the boxes and pick choices from the lists. Tutorials write these as `Setting = value`, using the names shown here (for example `Top speed = 88`).

## 11. Add a bean

Beans come in two groups: **ACTION** beans do something every frame or when a key is pressed (move, shoot, wander…), **COLLISION** beans react when something touches the object (damage, dialogue, pickups…). The tutorials say which group each bean is in.

![The ADD ACTION button](images/editor/17a-add-action.png)

1. With the object selected, click **ADD ACTION** (or **ADD COLLISION**) in the inspector.

![Searching the action beans and the + on Key input](images/editor/17b-add-action.png)

2. The Toolbox switches to that tab. Click the **search box** and type part of the bean name.
3. Click the bean's card (or the **+** on it). It is added at the bottom of the object's beans.

The same steps with ADD COLLISION, searching for "Dialogue" (here on a Checkpoint, because Dialogue box is meant for objects the hero walks up to, not for the hero):

![The ADD COLLISION button](images/editor/15a-add-collision.png)

![Searching the collision beans for Dialogue box](images/editor/15b-add-collision.png)

If the bean you want is not in the list, look at the bottom of the Toolbox under **NOT FOR …** (beans that usually suit a different kind of object) and **ALSO IN COLLISIONS / ACTIONS** (the bean is in the other tab: click **SWITCH TAB**).

## 12. Dialogue text

When an object has a **Dialogue box** bean, text boxes appear at the top of the inspector.

![The dialogue boxes and + LINE](images/editor/16-dialogue.png)

1. Click the **DIALOGUE** box and type the first line.
2. Each extra line has its own box (**LINE 2**, **LINE 3**…). The **×** beside a line removes it.
3. Click **+ LINE** to add another line box.
4. The Dialogue box bean's settings: **Pause while open** (pause the game or keep playing) and **Show for** (seconds per line).

Tick **ASK A QUESTION** to end the conversation with a two-answer question; the answer is stored in a variable.

## 13. Beans that run other beans (Key input, Timer)

Some beans hold other beans inside them. **Key input** runs its beans when a key is pressed; **Timer** runs them on a timer.

![A Key input card with its RUN THESE BEANS area](images/editor/18-key-input.png)

1. The bean's own settings, for example **Key** (which keyboard key) and **Trigger mode**.
2. **RUN THESE BEANS** lists the beans inside it. Each has its own on/off switch, arrows and **×**, like a normal card.
3. Open **Add a bean to run…** and pick a bean to put inside. Its settings appear in its card.

## 14. Rules (WHEN … DO …)

Rules make things happen on events, for example "when the game starts, hide me". Rules are in the inspector's advanced view.

![The ADVANCED button and ADD LOGIC RULE](images/editor/19-advanced.png)

1. Click **ADVANCED** at the top right of the inspector. It changes to **SIMPLE**; click that to go back to the normal view. (In the normal view, an object with rules shows "1 LOGIC RULE ATTACHED · EDIT LOGIC"; clicking that also opens the advanced view.)
2. Scroll down to **ADVANCED TAGS & VISUAL LOGIC** and click **ADD LOGIC RULE**.

![A rule card with WHEN, TARGET, IF and DO](images/editor/20-rule-card.png)

1. **ON**: the rule's on/off switch. **NOTE** beside it adds a reminder for yourself.
2. **WHEN**: the event, for example `onStart` (the scene starts), `onCollision` (the hero touches it), `onDestroy`, `onState`. A new rule starts with `onCollision`.
3. **TARGET**: who the actions apply to, usually `self`. The **×** at the end of this row deletes the rule.
4. **IF**: an extra condition; leave it at `always` unless the tutorial says otherwise. The list uses plain names: **state is** (this object's state is…), **other has tag** (the thing touching it has the tag…), **hero nearby**, **variable compare** and so on. When you pick one, a **VALUE** box appears beside it; type the state, tag or number there. Tick **SECOND CONDITION** to add an AND condition.
5. **DO**: the action list. Pick the action (for example **Show / hide**) and fill in the box beside it (for example **hide**). A new rule starts with "Give score 100"; change it to what the tutorial says.
6. **ADD ACTION** adds another action to the same rule. **FIND…** next to it searches every action by name.

**[Rules and logic](rules-and-logic.md)** teaches rules step by step. Tutorials write rules on one line, for example `WHEN onStart · TARGET self · DO Show / hide (hide)`. That means: WHEN = onStart, TARGET = self, IF = always, first action = Show / hide, its value = hide.

## 15. Sprites: import or draw

![The sprite editor with its controls numbered](images/editor/21-sprite-editor.png)

Click **SPRITE** in the inspector (step 9) to open the sprite editor.

1. **SIZE**: pick 16 × 16 (or the size the tutorial gives).
2. Drawing tools (**PENCIL**, **ERASER**, **FILL**, **LINE**, **RECT**, **PICKER**) and, under them, the four palette colours. Click a colour, then draw.
3. The drawing grid. Click or drag to paint pixels.
4. The animation tabs. **IDLE** is the standing animation. Every new sprite has **IDLE** and **MOVE**. To add another animation (for example `jump` or `open`), type its name in the **New: pick or type a name** box under the tabs (the list suggests the names the engine plays) and click **+ ADD**. In this tutorial series that is written **+ ADD** `jump`. The box above it renames the open animation, and **DELETE** removes it.
5. **IMPORT PNG / SHEET** loads a picture into the current animation. Every tutorial comes with ready-made sprite files in its `sprites` folder: pick the animation tab, click IMPORT PNG / SHEET and choose the file with the same name (for example `sprites/wren/move.png`). A file with several frames side by side becomes several frames.
6. **SAVE SPRITE** saves and closes. Closing with **×** throws your changes away.

On the right, **FRAME TIME** sets the seconds per frame, **LOOP** repeats the animation, and **DUPLICATE FRAME** adds a frame to draw. For objects bigger than the sprite (a wall, water), set **ON BIG OBJECTS = Repeat as tiles** so the picture repeats instead of stretching.

## 16. Save an object as an entity and place copies

When several objects are the same (three bats, five signs), set one up completely, then save it as an entity.

![SAVE ENTITY in the inspector](images/editor/23a-save-entity.png)

1. Select the finished object and click **SAVE ENTITY**.

![The saved entity under MY ENTITIES](images/editor/23b-my-entities.png)

2. It appears in the Toolbox (OBJECTS tab) under **MY ENTITIES**. Click it, then click the map to place a copy with the same beans and sprite. Give each copy its own name and position.

You can also copy and paste: select an object, press **Ctrl+C** then **Ctrl+V** (**⌘C**, **⌘V** on a Mac), and type the copy's new X and Y.

## 17. Find an object

![The FIND button](images/editor/25b-find-button.png)

1. Click **FIND** at the right end of the scene bar (or press **/**).

![The Find window](images/editor/25-find.png)

1. Type part of a name, a kind or a bean name. The window also shows how full each scene is (objects and size).
2. Click a result. The editor switches to its scene, scrolls the map to it and selects it.

## 18. Paint walls quickly with the Brush

![The Brush tool and a brick painted on the map](images/editor/24-brush.png)

1. Click **Brush** in the map toolbar, then click **Brick** (or **Platform**) in the Toolbox. The Brush only paints these two kinds.
2. Drag a rectangle on the map. One object fills the rectangle, rounded to the **SNAP** grid, and it is selected.
3. The Brush switches itself off after each rectangle, so click **Brush** again before you drag the next piece.

Then click each piece and fix its exact X, Y, W, H in the inspector. The Brush never paints in the top 16 px of a scene (the HUD strip), so a piece that starts at y = 0 must be typed in.

**Paint** (next to Brush) is the free-hand version: drag across the map to fill 16 px cells with terrain, right-drag to erase. Painted cells join the pieces they touch and copy their look, so painting beside rock makes more rock. Press **Esc** to stop painting. The tutorials type exact positions, so they use the Brush or typed numbers instead.

## 19. The toolbars

The **editor toolbar** across the top holds everything that works on the whole game:

![The editor toolbar with its four groups numbered](images/editor/22b-app-toolbar.png)

1. **FILE**: **NEW** game, **OPEN**, **SAVE**, **EXPORT** the cartridge (`.json`) and **GAME** (export a playable `.html` file).
2. **EDIT**: **UNDO** (Ctrl/⌘+Z) and **REDO** (Ctrl/⌘+Shift+Z).
3. **CREATE**: **AI BUILDER** (describe a change and let the AI build it, with your own API key), **MUSIC** (write songs on a note grid), **AUDIO** (import sound files), **SCENE STUDIO**, **ENTITY STUDIO**, **VARIABLES** and **DIALOGUE** (every line of text in the game).
4. **TEST**: **CHECK** (looks for problems and previews the export) and **DEBUG** (pause, step frames and watch variables while playing).

The **map toolbar** just above the map holds the tools for the map itself:

![The map toolbar](images/editor/22-toolbar.png)

1. **Select**: click to select, drag to move.
2. **Brush**: paint objects by dragging (step 18).
3. **Paint**: paint terrain cells (step 18).
4. **Pan**: drag to scroll the map. Holding **Space** while dragging does the same with any tool.
5. **SNAP**: objects you drag snap to this grid (8 or 16 px). Typed positions are never snapped.
6. **VIEW**: zoom the map out (67%, 50%, 33% or 25%) so big scenes fit. Ctrl/⌘ + mouse wheel zooms too.
7. **Fit**: picks the zoom that shows the whole scene.
8. **SCREEN**: how big the whole editor screen is on the page.

Right-click the map for more: **Playtest from here**, copy, cut, duplicate and delete, flip and turn, and the layer order.

## 20. Playtest

![PLAY and PLAY ALL](images/editor/27-play.png)

1. **PLAY** in the PLAY / BUILD switch (or **Ctrl+Enter** / **⌘+Enter**) plays the scene you are editing.
2. **PLAY ALL** in the scene bar plays the game from its first scene.

In the game, **E** returns to the editor, **Enter** pauses and **R** restarts.

## 21. Save your work

![FILE > Save As…](images/editor/26a-file-saveas.png)

1. Click **FILE**, then **Save As…** the first time (afterwards **SAVE** in the toolbar, or Ctrl/⌘+S).

![The Save your game window](images/editor/26b-save-dialog.png)

1. Type a name for your game.
2. **Save in My Games** keeps it in GameBean Studio (open it again with FILE > Open…).
3. **Save to a file…** saves a `.json` file you can keep, back up or share. In the desktop app, Save always writes to a file on your computer.

Save after every part of a tutorial.
