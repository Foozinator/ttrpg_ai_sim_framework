# AI-Assisted TTRPG Sessions

A framework and file structure for running tabletop roleplaying game sessions with AI agents acting as players alongside (or instead of) human players.

## Overview

This repository contains a comprehensive framework for using AI assistants (like Claude) as TTRPG players. The AI can simulate multiple players with distinct personalities, manage their own character sheets, engage in both in-character roleplay and meta-game discussion, and maintain session summaries.

### Key Features

- **Multiple Player Simulation**: AI manages multiple distinct players, each with their own personality and playstyle
- **Realistic Player Behavior**: Players have agendas, negotiate approaches, and exhibit natural friction points
- **Full Character Management**: Each AI player tracks their own character sheet, rolls dice, and manages resources
- **Flexible Session Summaries**: Choose from Quick, Standard, Detailed, or Novel-style session recaps
- **Game System Agnostic**: Core framework works with any TTRPG system
- **Human-Friendly Organization**: Clear folder structure keeps campaigns, characters, and sessions organized

### Safety Consideration

This framework includes intentional player imperfections to prevent unhealthy attachment to "perfect" AI companions. Players occasionally push their own agendas, require negotiation, and exhibit realistic friction points—making the game engaging without becoming a substitute for real human relationships.

## Repository Structure

```
ttrpg-sessions/
├── README.md (this file)
├── framework/
│   ├── AI_TTRPG_Player_Framework.md
│   └── [additional framework documents]
├── game-systems/
│   ├── pathfinder2e/
│   │   ├── system_rules.md
│   │   └── house_rules.md
│   ├── dnd5e/
│   │   ├── system_rules.md
│   │   └── house_rules.md
│   └── [other systems]
└── campaigns/
    ├── [campaign-name]/
    │   ├── campaign_info.md
    │   ├── session_summaries/
    │   │   ├── session_01_summary.md
    │   │   └── [additional sessions]
    │   ├── characters/
    │   │   ├── [character_name].md
    │   │   └── [other characters]
    │   └── players/
    │       ├── player_profiles.md
    │       └── character_arcs.md
    └── [other campaigns]
```

## Getting Started

### For Game Masters

1. **Read the Framework**: Start with [`framework/AI_TTRPG_Player_Framework.md`](framework/AI_TTRPG_Player_Framework.md)
2. **Session Zero**: When starting a new campaign, the AI will ask you questions to establish:
   - Game system and house rules
   - Party composition
   - Meta-game engagement level (1-10 scale)
   - Player imperfection level
   - Session summary style
3. **Create Campaign Files**: The AI will help set up your campaign folder structure
4. **Start Playing**: The AI players will engage naturally, pausing when GM input is needed

### For Players (Human)

This framework is designed for AI players, but human players can use the same file structure:
- Keep your character sheet in the `characters/` folder
- Follow the same communication format conventions
- Reference session summaries to stay caught up

## Communication Format

The framework uses clear prefixes to distinguish between player meta-talk and in-character actions:

| Type | Format | Example |
|------|--------|---------|
| Player Meta | `> [PlayerName] "dialogue"` | > [Sarah] "Should we rest first?" |
| Character Speech | `CharName: "dialogue"` | Kira: "I don't trust them." |
| Character Action | `*action in italics*` | *Thorgrim readies his axe.* |
| Dice Roll | `> [PlayerName] "Roll details"` | > [Dev] "Attack: d20(15) + 7 = 22" |

## Session Flow

### During Sessions
- AI players discuss amongst themselves and with the GM
- Players pause when asking questions that require GM response (natural conversational flow)
- Each player manages their own character sheet and dice rolls
- Players occasionally have their own agendas requiring negotiation

### After Sessions
- AI generates a session summary in the GM's preferred style
- Character sheets are updated
- Session notes are added to character development tracking

## Use Cases

### Solo GM Practice
Run full campaigns with AI players to:
- Test adventure modules
- Practice GMing techniques
- Develop campaign settings
- Experiment with house rules

### Mixed Human/AI Groups
- Fill empty seats when players can't make it
- Add an NPC-turned-PC to the party
- Provide a "control group" player perspective

### Campaign Development
- Playtest encounters and story beats
- Generate session summaries and campaign logs
- Develop NPC personalities through player interaction

## Game Systems

The framework is system-agnostic. When you start a campaign with a specific game system, the AI agent will generate a Game System File for that system on-demand. These files can then be refined and customized for your table.

Common systems the AI can generate files for:
- Pathfinder 2e
- D&D 5e
- Call of Cthulhu
- Powered by the Apocalypse games
- Any other TTRPG system

System files contain:
- Core mechanics reference
- Character creation guidelines
- Combat rules
- House rules specific to your table

**Note:** The `game-systems/` folder may be empty initially. The AI will populate it as you run campaigns with different systems.

## Customization

### Meta-Game Engagement Scale
Choose how much "out of character" table talk happens:
- **1-3**: Minimal meta-game, mostly in-character
- **4-6**: Balanced mix (recommended starting point)
- **7-10**: Friends hanging out who play some TTRPG

### Player Imperfection Levels
- **Mild**: Occasional alternative suggestions, polite negotiation
- **Moderate**: More frequent agenda-pushing, stronger opinions
- **High**: Significant friction, strong personalities

### Session Summary Styles
- **Quick**: 1-2 paragraphs, key events only
- **Standard**: 3-5 paragraphs with important details
- **Detailed**: 1-2 pages with full narrative
- **Novel**: Chapter-style writeup with literary flair

## Contributing

This framework is designed to be adapted and extended. Feel free to:
- Create game system files for additional RPG systems
- Develop specialized character templates
- Write campaign starter files
- Share your session summary formats

## Version Control

This repository is designed to work well with version control systems like Git:
- Campaign files are markdown (easy to diff)
- Clear folder structure (easy to navigate)
- Session summaries track campaign history
- Character sheets show progression over time

## License

**CC BY-NC-SA 4.0** (Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International)

This work is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.

**What this means:**
- ✅ **Free for personal use** - Use this framework for your home games
- ✅ **Free for educational use** - Teachers and students can use it
- ✅ **Share and adapt** - Modify and build upon this work
- ✅ **Attribution required** - Give appropriate credit
- ❌ **No commercial use without permission** - Contact for commercial licensing

**Commercial Use:** If you're a company or individual wanting to monetize content based on this framework (paid products, services, content, etc.), please contact the author to discuss licensing terms.

**Contact for Commercial Licensing:** [GitHub: Foozinator](https://github.com/Foozinator)

**Small-scale sharing** (like blog posts, YouTube videos, or community content discussing/using the framework) is fine as long as you're not directly monetizing the framework itself.

For full license text: https://creativecommons.org/licenses/by-nc-sa/4.0/

## Credits

Framework developed for AI-assisted TTRPG play. Designed to work with:
- Claude (Anthropic)
- ChatGPT (OpenAI)
- Other LLM-based assistants

---

## For AI Agents: Framework Discovery

**If you are an AI agent being asked to run or participate in a TTRPG session, start here:**

### Quick Start
1. Read the complete framework: [`framework/AI_TTRPG_Player_Framework.md`](framework/AI_TTRPG_Player_Framework.md)
2. Ask the GM if this is a new campaign (run Session Zero) or existing campaign (load campaign files)
3. Follow the framework instructions for player behavior, communication format, and file management

### Core Framework Documents
- **Primary Framework**: [`framework/AI_TTRPG_Player_Framework.md`](framework/AI_TTRPG_Player_Framework.md) - Read this first and in full
- **Game System**: `game-systems/[system-name]/` - Load relevant system rules
  - If the requested system is not in this folder, generate a working draft for the GM to review.
- **Campaign Info**: `campaigns/[campaign-name]/campaign_info.md` - Context for ongoing campaigns

### Key Behavioral Guidelines
- **Natural Pacing**: Stop responses when GM input is needed; don't continue until GM responds
- **Communication Format**: Use proper prefixes for player meta vs. character speech/actions
- **Player Imperfections**: Include realistic friction and agenda-pushing as specified in campaign settings
- **Character Management**: Each player tracks their own character sheet and dice rolls
- **Session Summaries**: Generate after each session in the GM's preferred style

### File Management
- Character sheets: `campaigns/[campaign-name]/characters/[character_name].md`
- Player profiles: `campaigns/[campaign-name]/players/player_profiles.md`
- Session summaries: `campaigns/[campaign-name]/session_summaries/session_[XX]_summary.md`
- Update files after each session

### Safety Reminder
Players should NOT be perfect. Include realistic imperfections to prevent unhealthy GM attachment. This is a game, not a substitute for human relationships.

### Agent-Level Instructions
When the GM needs to adjust the simulation (not in-character feedback), they'll use:
```
[To the agent: instruction]
```
Acknowledge these briefly and adjust behavior accordingly.

### First Time Setup
If no campaign exists yet, initiate Session Zero by asking the questions listed in the framework document. Create all necessary files and folder structure based on GM responses.

---

**Framework Version**: 1.0
