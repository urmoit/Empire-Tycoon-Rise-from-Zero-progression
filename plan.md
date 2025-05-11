# Empire Tycoon: Rise from Zero - Progression

## Phase 1: Core Tycoon Gameplay

- [ ] **Basic Tycoon Framework**  
  Create the basic structure of the tycoon: a working base, droppers, and buttons to purchase. The player will be able to interact with the tycoon’s core mechanics, such as generating resources and buying upgrades.

  **Note**: Buttons will be purchased using a ProximityPrompt instead of collision-based interactions. Players will need to approach the button and trigger the prompt to purchase it.

- [ ] **Save System (DataStore for Tycoon Progress and Money)**  
  Implement Roblox DataStore to save the player's progress, including their money, items purchased, and current tycoon state. The save system should store and load all essential game data for a seamless experience when players rejoin.

- [ ] **Money Generation & Button Purchasing**  
  The game should allow players to generate money passively via droppers and manually through purchasing buttons. Each button should increase the progression of the tycoon and be purchasable for increasing amounts of money.

- [ ] **Rebirth System with Multipliers**  
  Implement the rebirth system where players can restart their tycoon for a permanent boost in production, money, or efficiency. The multiplier can be applied to resources, button purchases, or other systems.

- [ ] **Rebirth-only Upgrades (Locked Until Rebirth)**  
  Certain upgrades or features should be locked behind the rebirth system. These should not be available to players until they have reached a specific rebirth level.

- [ ] **Button Tracker (X / Y Upgrades Bought)**  
  Track the number of buttons that the player has bought and display it in the UI. This tracker will help players know their progression and motivate them to complete their tycoon.

## Phase 2: UI & Progress Tracking

- [ ] **Main UI Panel with:**
  - [ ] **Money Display**  
    Show the player's current money in a visible and easily accessible part of the screen.
  - [ ] **Shop**  
    Display the shop with available buttons, upgrades, and other purchasable items. Allow players to buy items directly from the shop.
  - [ ] **Settings**  
    Include in-game settings for volume, graphics, and performance options.
  - [ ] **Stats/Progress Tab**  
    Display the player's progression with stats like how many upgrades they've purchased, how many upgrades are left, and their current money.

- [ ] **Tycoon Progress Bar with %**  
  Show a progress bar to indicate the player’s completion in building their tycoon. This will also give players an idea of how far they are from unlocking new upgrades or achieving new milestones.

- [ ] **Show Buttons Left to Buy (X/Y)**  
  Display a counter showing how many buttons (upgrades) are left to buy in the current stage of the tycoon.

- [ ] **Rebirth Button Appears at 100%**  
  Once the player has completed all upgrades, show the rebirth button. This button should allow the player to restart their progress for a reward, such as a multiplier or permanent upgrade.

- [ ] **Map Leaderboard Showing Top Players**  
  Implement a leaderboard on the map or in the UI that shows the top players in terms of money, rebirths, or overall progression.

## Phase 3: Developer Products & Monetization

- [ ] **Small Cash Pack (10 Robux, 5–10% of Remaining Upgrades)**  
  Allows players to buy a small cash pack to help them purchase some of the remaining upgrades. The pack should be balanced so it gives a reasonable amount of help for early progress.

- [ ] **Medium Cash Pack (50 Robux, 15–20% of Remaining Upgrades)**  
  A medium-sized cash pack for players who need more money to continue progressing, especially in the mid-game phase.

- [ ] **Big Cash Pack (199 Robux, 40–50% of Remaining Upgrades)**  
  The largest cash pack, designed to give a significant boost to players who need help with late-game progression. It should be carefully priced to reflect the value of the upgrades.

- [ ] **Dynamic Calculation of Remaining Upgrade Value**  
  The developer products should be dynamically adjusted based on the player's progression. The cost of the products should scale with the amount of progress the player has made in the tycoon.

## Phase 4: Badges & Rewards

|**Checked**|**Badge Name**|**Play Requirement**|**What You Unlock**|**Prize**|**Description**|
|-----------|--------------|--------------------|-------------------|---------|---------------|
|No|Welcome|On First Join|nothing|$500|Welcomes new players with a small bonus and a hidden starter tag.|
|No|1-Hour Tycoon|Play for 1 Hour|[New Tycoon] Chat Tag|$1,000|Rewards new players for staying an hour with a title and a cash bonus.|
|No|5-Hour Tycoon|Play for 5 Hours|[Active Tycoon] Chat Tag|$5,000|Encourages mid-term play with a boost and recognition in chat.|
|No|10-Hour Tycoon|Play for 10 Hours|[Pro Tycoon] Chat Tag|$15,000|Recognizes committed players with a higher-tier tag and bonus.|
|No|24-Hour Legend|Play for 24 Hours|[Legendary Tycoon] + Special Trail|$50,000|Honors long-term dedication with a trail effect and prestigious tag.|
|No|50-Hour Maniac|Play for 50 Hours|[Tycoon Maniac] + Exclusive Hat|$100,000|A rare badge for elite grinders, includes a unique wearable cosmetic.|
|No|Meet the Developer|Interact with Dev In-Game|[Met The Dev] Chat Tag + Effect|$5,000|For special interactions with the dev during events or live visits.|
|No|Rebirther I|Complete 1st Rebirth|[Fresh Start] Chat Tag|$5,000|For players who restart and progress past their first rebirth.|
|No|Rebirther II|Complete 2nd Rebirth|[Prestiged Tycoon] Chat Tag|$25,000|Recognition for double rebirthers, showing progress and dedication.|
|No|Rebirther III|Complete 3rd Rebirth|[Ultimate Tycoon] + Character Skin|$100,000|Grants an exclusive skin and elite tag for advanced tycoon players.|

## Phase 5: Chat Tags & Customization

- [ ] **Chat Tag System Using ChatService**  
  Use Roblox’s `ChatService` to create a dynamic chat tag system that automatically displays the correct tag based on the player’s progress or badges.

- [ ] **Unlock Tags from Badge Rewards**  
  Players will earn unique chat tags after completing specific milestones such as achieving certain playtimes, rebirthing, or completing challenges.

- [ ] **Store Unlocked Tags in Player Data**  
  All unlocked tags should be stored in the player’s data and applied whenever they enter the game.

- [ ] **Settings GUI to Switch Between Unlocked Tags**  
  Allow players to access their tags in the settings menu and change which tag is displayed next to their name in the chat.

- [ ] **Tags Display in Chat Next to Player Name**  
  Display the unlocked tags in the player’s name on the leaderboard and in the chat so that other players can see their achievements.

## Phase 6: Extras & Polish

- [ ] **Special Trails and Auras for Badges (Optional Cosmetic Effects)**  
  Offer special cosmetic rewards like trails or auras for certain badges, adding a unique visual element to players who reach special milestones.

- [ ] **Exclusive Cosmetic Unlocks from Rebirths or Playtime**  
  Unlock cosmetics like skins, hats, or auras based on the player’s rebirths or playtime.

- [ ] **Polish UI, Animations, and Sound**  
  Add finishing touches to the UI, including animations for buttons, money generation, and upgrades. Enhance the sound effects to match the feel of the game.

- [ ] **Test with Friends Before Release**  
  Before making the game public, test the tycoon thoroughly with a group of players to ensure it works smoothly.

- [ ] **Add Badge Scripts and Reward Triggers**  
  Implement the logic to track playtime and milestones to trigger badge rewards and achievements.

- [ ] **Publish with Attractive Icon & Thumbnails**  
  Once the game is complete, publish it with high-quality icons and thumbnails to attract players.
