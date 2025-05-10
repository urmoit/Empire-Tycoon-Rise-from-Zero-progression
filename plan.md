# Empire Tycoon: Rise from Zero - Progression

## Phase 1: Core Tycoon Gameplay

- [ ] **Basic Tycoon Framework**  
  Create the basic structure of the tycoon: a working base, droppers, and buttons to purchase. The player will be able to interact with the tycoon’s core mechanics, such as generating resources and buying upgrades.

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

- [ ] **Welcome (on join)**  
  Reward players who join the game with a small bonus (e.g., $500) and a non-visible tag. This is to welcome them and get them started.

- [ ] **1-Hour Tycoon – [New Tycoon]**  
  Players who play for 1 hour will receive a badge, +$1,000, and the [New Tycoon] tag.

- [ ] **5-Hour Tycoon – [Active Tycoon]**  
  For playing for 5 hours, players will earn $5,000 and the [Active Tycoon] tag, signaling they’re a committed player.

- [ ] **10-Hour Tycoon – [Pro Tycoon]**  
  Reward players who spend 10 hours in-game with $15,000 and the [Pro Tycoon] tag.

- [ ] **24-Hour Legend – [Legendary Tycoon]**  
  After 24 hours of playtime, players will earn $50,000 and unlock a special trail as a badge reward.

- [ ] **50-Hour Maniac – [Tycoon Maniac]**  
  A special reward for players who reach 50 hours of gameplay. They will receive $100,000 and an exclusive hat.

- [ ] **Meet the Developer – [Met The Dev]**  
  Players who interact with the developer (via a special event or in-game interaction) will earn $5,000 and an effect tied to the [Met The Dev] tag.

- [ ] **Rebirther I – [Fresh Start]**  
  After the first rebirth, players get $5,000 and unlock the [Fresh Start] tag.

- [ ] **Rebirther II – [Prestiged Tycoon]**  
  After the second rebirth, players will earn $25,000 and unlock the [Prestiged Tycoon] tag.

- [ ] **Rebirther III – [Ultimate Tycoon]**  
  After the third rebirth, players will get $100,000 and unlock an exclusive skin for their character.

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
