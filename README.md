## Bounty Hunter Mod 1.2

Original mod by Salamandre.
Reworked and adapted for ERA 3 by PerryR.

The Bounty Hunter Mod creates a new weekly hunt. A specific creature becomes the current bounty, and every defeated target contributes to your reward. Return to town to collect your payment and any additional rewards you earned.

----------------------------------------------------------------------------------------------------------------------
HOW IT WORKS
----------------------------------------------------------------------------------------------------------------------

- A new bounty creature is selected every Monday.
- The target includes its normal and upgraded forms.
- The first town visit of the week shows the current bounty and its reward potential.
- Hunt the target anywhere on the adventure map.
- Open the Bounty Hunter window from the GEM town button or by right-clicking the Town Hall to hand in your bounty.
- Gold is paid for every valid kill. The final payout also grows with game time.
- The first successful hand-in by each player each week can award persistent bounty tokens. Later hand-ins during the same week still pay gold but do not award more tokens.
- Use the dedicated icons in Janice's office to view statistics, hand in kills, exchange tokens, or reroll the shared weekly target.

----------------------------------------------------------------------------------------------------------------------
EARLY-GAME SCALING
----------------------------------------------------------------------------------------------------------------------

The bounty system starts gently. During the first weeks, only lower-level creatures can become targets. Higher-level creatures gradually enter the bounty pool as the game progresses.

Stronger bounty creatures improve both the gold value per kill and the chance to receive additional rewards.

From week 10 onward, games using the Third Upgrade Mod have a small chance to generate an Elite Bounty. Elite targets include especially powerful neutral creatures and final TUM town upgrades.

----------------------------------------------------------------------------------------------------------------------
HUNTER RANKS
----------------------------------------------------------------------------------------------------------------------

Each player's first successful hand-in of a week counts as one completed contract:

- 1 contract: Novice Hunter
- 4 contracts: Skilled Hunter
- 10 contracts: Master Hunter
- 20 contracts: Legendary Hunter

Rank bonuses are:

- Novice Hunter: +5% bounty gold and unlocks rerolling.
- Skilled Hunter: +10% bounty gold, +1 token on the first weekly hand-in, and a 25% reroll discount.
- Master Hunter: +15% bounty gold, +1 token, a 50% reroll discount, and +5 reward value for token calculation.
- Legendary Hunter: +25% bounty gold, +2 tokens, free rerolls, and +5 reward value for token calculation.

The listed bonuses are totals for each rank rather than cumulative values. Gold bonuses apply to the creature-dependent part of the bounty.

Click the framed portrait of the woman in Janice's office to open the rank overview. Promotion messages also show the bonuses of your new rank.

----------------------------------------------------------------------------------------------------------------------
BOUNTY TOKENS AND ADDITIONAL REWARDS
----------------------------------------------------------------------------------------------------------------------

Gold is always paid immediately. Bounty tokens are stored separately for every player until they are exchanged. One token is spent per exchange, and an active hero must be visiting the town to receive the reward.

Four reward profiles influence the random reward category:

- Supplies: favors resources
- ACM Rewards: favors Advanced Classes bonuses and is available only while ACM is active
- Treasure Hunt: favors artifacts
- Training and Knowledge: favors primary skills, experience, and spells

Possible rewards include:

- Resources
- Primary skills
- Experience
- Artifacts
- Spells
- Special bonuses when the Advanced Classes Mod is active

If no valid reward can be generated, the token is preserved.

----------------------------------------------------------------------------------------------------------------------
REROLLING AND STATISTICS
----------------------------------------------------------------------------------------------------------------------

Rerolling becomes available after reaching Novice Hunter rank. It changes the target for every player, can be used only once per week, and is blocked after any player has defeated a bounty creature.

The statistics page tracks separately for every player:

- Completed contracts and current hunter rank
- Defeated bounty creatures
- Gold earned from bounties
- Total and currently stored bounty tokens
- Completed Elite Bounties

----------------------------------------------------------------------------------------------------------------------
CONFIGURATION
----------------------------------------------------------------------------------------------------------------------

The configuration window offers Modest, Standard, and Generous contracts. These settings control bounty payments and the combat bonus received by bounty creatures. The maximum payout is 30,000, 40,000, or 50,000 Gold per game month respectively.

Advanced users can adjust the selected contract, individual reward weights and the four token-exchange profiles in `Lang/configuration.json`. A contract confirmed in game is stored in `Runtime/bounty config.ini` and takes precedence. Delete the INI to apply a changed JSON contract default again.

The following values are intended for balancing:

- Bounty_Reward_Creature_Level_0 through Bounty_Reward_Creature_Level_8: gold paid per defeated creature level.
- Bounty_Reward_per_month: monthly scaling added to the final gold payout.
- Bounty_Reward_Weight_*: relative weights of individual rewards.
- Bounty_Profile_*_Weight_*: category weights used by the four token-exchange profiles.

The creature-level gold values and monthly gold scaling remain in `Data\s\Bounty Haunter Mod.erm` because they are complete balance tables rather than simple configuration switches.

----------------------------------------------------------------------------------------------------------------------
COMPATIBILITY
----------------------------------------------------------------------------------------------------------------------

- Built for ERA 3.
- Requires Era Erm Framework and Game Enhancement Mod.
- Compatible with the Third Upgrade Mod.
- Advanced Classes Mod is optional; when present, additional ACM-specific rewards can be included.
- Includes English and Russian interface text.

----------------------------------------------------------------------------------------------------------------------
LATEST CHANGELOG
----------------------------------------------------------------------------------------------------------------------

2026-09-17 Release (1.2) by PerryR
- Added hunter ranks with gold and token bonuses, a rank overview, and promotion details.
- Added stored bounty tokens with four reward profiles and personal hunting statistics.
- Added configurable contracts and weekly target rerolls with rank-based discounts.
- Added Elite Bounties for powerful creatures when Third Upgrade Mod is active.
- Updated Janice's office and added Russian interface text.

2025-06-08 Release (1.1) by PerryR
- Early weeks now use only low-level bounty targets.
- Reduced early-game experience rewards.

2024-11-02 Release (1.0) by PerryR
- Initial ERA 3 rework and new reward system.
- Added Third Upgrade Mod compatibility and code improvements.

----------------------------------------------------------------------------------------------------------------------
FEEDBACK
----------------------------------------------------------------------------------------------------------------------

For feedback and bug reports, join the HoMM 3.5 ERA Mods Discord server:
https://discord.gg/hCTMfVq6w5
