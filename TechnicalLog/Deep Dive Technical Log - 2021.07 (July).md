# 20210719

1. (Semantics) Add basic semantics for **AskForName**-type dialogue;
2. (Syntactics, User Interface) Complete draft for path-based sentence pattern builder; Partially replace existing Data-Table based sentence pattern detection (from Player input) with `SentencePatternBuilder` approach.
3. (User Interface) Allow basic arbitary name input.

![Pattern Builder](https://github.com/Charles-Zhang-Deep-Dive/Deep-Dive-Dev-Central/blob/4163bec9249938c03840fdad7061ce5f4a9644c4/images/Screenshot2021071901.png)

![What's Your Name](https://github.com/Charles-Zhang-Deep-Dive/Deep-Dive-Dev-Central/blob/4163bec9249938c03840fdad7061ce5f4a9644c4/images/Screenshot2021071902.png)

![Name Input](https://github.com/Charles-Zhang-Deep-Dive/Deep-Dive-Dev-Central/blob/main/Screenshots/20210719_03.png)

# 20210720

1. (Gameplay) Add RoleSimulation Actor Component; (Semantics) Add details to Bar Tender behavior, allow "ice-breaking" talk;
2. (Code Architecture) Split PatternHandler into PatternHandler and PatternReactor for responsibility division between internal and external state updates;

# 20210721

1. (Semantics) Add basic semantics for "Are you from the neighbourhood?".

# 20210722

1. (Code Management) Refactor code for CommonConversationDialogue base to allow re-using of shared *whole sentence parsing logic* - this is useful in two occasions: 1) SimpleMultiPart PatternHandler; 2) Automatic parsing for "article-like" writings e.g. diaries and emails (not implemented yet but will be added later).
2. (Gameplay) Augment Bar Tender behavior: add speeches, add basic movement.
3. (User Interface) Three improvements: 1) Chat bubble chat display and rendering fix; 2) Test update bottome-panel chat log scroll lines and add details regarding who is speaking to whom; 3) Update floating chat bubble locator to follow the last person speaking to us (*still buggy*).

![Chat Bubble Display](https://github.com/Charles-Zhang-Deep-Dive/Deep-Dive-Dev-Central/blob/a685e003addb940f7f93b1c68a4c67e5025dc194/Screenshots/20210722_01.jpg)

![Chat Log Rolling Panel](https://github.com/Charles-Zhang-Deep-Dive/Deep-Dive-Dev-Central/blob/a685e003addb940f7f93b1c68a4c67e5025dc194/Screenshots/20210722_02.png)

![Chat Locator](https://github.com/Charles-Zhang-Deep-Dive/Deep-Dive-Dev-Central/blob/a685e003addb940f7f93b1c68a4c67e5025dc194/Screenshots/20210722_03.png)

# 20210723

1. (System) Test and fix bug with Pattern Builder;
2. (Semantics) Minor update/addition to greetings parsing.
3. (GUI) Work on basic *Full Info menu* for **Visitor Mode** (and in this case for Doris Place minigame) - add speech log display.

![Speech Log](https://github.com/Charles-Zhang-Deep-Dive/Deep-Dive-Dev-Central/blob/main/Screenshots/20210723_01.png)

# 20210724

1. (Feature, Semantics, NPC) Add Emoji display for NPCs. (Notice players can't input emojis yet - but *this might be a desired user interface feature*: allow players to input from selection certain emojis as a means of expressing emotions; This feature is not urgent so will be implemented much later)

![NPC Emoji](https://github.com/Charles-Zhang-Deep-Dive/Deep-Dive-Dev-Central/blob/main/Screenshots/20210724_01.png)