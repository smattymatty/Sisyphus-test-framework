# 🪨 Sisyphus Test Framework
*A Narrative RPG Test Framework for Dopamine-Driven Development*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Greek Mythology](https://img.shields.io/badge/Powered%20by-Greek%20Mythology-blue.svg)](https://en.wikipedia.org/wiki/Sisyphus)
[![Existential Dread](https://img.shields.io/badge/Existential%20Dread-Included-purple.svg)](#)
[![Camus Approved](https://img.shields.io/badge/Camus-Approved-black.svg)](#)

> *"One must imagine Sisyphus coding."* - What Camus would say if he were a developer

## What is This Madness?

**The Sisyphus Test Framework** is the world's first **Narrative RPG Test Framework** that transforms the eternal struggle of testing into an epic mythological journey. Instead of dreading test failures, you'll find yourself addicted to the dopamine rush of leveling up, unlocking achievements, and uncovering the dark, beautiful story of Sisyphus and Daedalus building the Labyrinth.

Does YOUR test framework double as a Narrative RPG? **Mine does.**

## 🎭 The Philosophy: Dopamine-Driven Development (DDD)

Testing is traditionally the most tedious part of development. But what if we could transform this Sisyphean task into something genuinely fun and rewarding? 

The Sisyphus Test Framework gamifies testing through:
- **🎮 XP and Leveling System**: Every test gives you experience points
- **🏆 Achievement System**: 50+ mythologically-themed achievements to unlock
- **📜 Epic Story Mode**: A 50-level narrative that unfolds as you level up
- **🏛️ Labyrinth Exploration**: Each test is Sisyphus alone, exploring the maze of his own code
- **🌟 Combo System**: Chain successful tests for massive XP multipliers
- **📊 Persistent Progress**: Your journey is saved across all sessions

## 🏛️ The Epic Story

Hidden within the framework is an untold story—a 5-act Greek tragedy told through 50 fragments:

- **Act I: The New Curse** *(Levels 1-10)* - Sisyphus meets Daedalus
- **Act II: The Labyrinth's Nature** *(Levels 11-20)* - The true purpose unfolds  
- **Act III: The Cracks Appear** *(Levels 21-30)* - Characters break under strain
- **Act IV: Inescapable Truths** *(Levels 31-40)* - Secrets are revealed
- **Act V: The Eternal Cycle** *(Levels 41-50)* - Acceptance of the absurd

Each level unlocks one story fragment. Inspired by Greek Mythology and the works of Albert Camus; "The Myth of Sisyphus", and "The Guest". 

> "🏛️ THE ARRIVAL - You are brought to a high tower in the palace of Knossos. A man with haunted eyes introduces himself as Daedalus. 'King Minos has a task for us,' he says. 'A glorious, eternal task.'" - The First Line


## 🚀 Features That Will Ruin Your Productivity

### 🎮 Complete RPG Experience
- **Experience Points**: Earn XP for every passing test
- **Leveling System**: 50 levels with exponential XP requirements
- **Achievement System**: Over 50 achievements with historical significance
- **Combo Multipliers**: Chain victories for massive XP bonuses
- **Streak Tracking**: Maintain winning streaks across sessions

### 📊 Obsessive Progress Tracking
- **Sisyphus Archive**: Like `.git` but for your eternal struggle
- **Historical Analysis**: Track improvement trends over time
- **Performance Metrics**: Speed optimizations earn bonus XP
- **Lifetime Statistics**: Your `sisyphus.legend` file tracks everything
- **Daily Milestones**: Special achievements that reset daily

### 🏛️ Mythological Immersion
- **Time-Aware Greetings**: Different messages for dawn, noon, dusk, midnight
- **Seasonal Variations**: Story changes with the seasons
- **Greek Historical Events**: Special messages on historical dates
- **Character Development**: Sisyphus and Daedalus evolve throughout the story
- **Act-Aware Test Narration**: Individual test messages change based on story progression

### 🎯 Smart Test Management
- **Failure Analysis**: Detailed breakdowns of what went wrong
- **Motivational Recovery**: Inspirational quotes when you fail
- **Smart Retry Logic**: Framework learns from your patterns
- **Bulk Test Orchestration**: Run entire test suites with epic summaries

## 📱 Installation *(Current Implementation)*

> **Note**: This is an early-stage project with ambitious goals! Currently implemented as a C testing framework with extensive mythological theming.

### Quick Start (C Language)
```bash
# Clone the framework
git clone https://github.com/your-org/sisyphus-test-framework.git
cd sisyphus-test-framework

# Copy the header to your project
cp sisyphus.h /path/to/your/project/

# Start your eternal journey
./run_tests.sh
```

### Using in Your Tests
```c
#include "sisyphus.h"

int test_string_operations(void) {
    TEST_SUITE_START("String Operations - Navigating the Labyrinth");
    
    RUN_TEST(test_string_concatenation);
    RUN_TEST(test_string_length);
    RUN_TEST(test_string_comparison);
    
    TEST_SUITE_END();
}

int test_string_concatenation(void) {
    char result[100];
    strcpy(result, "Hello");
    strcat(result, " World");
    
    TEST_ASSERT(strcmp(result, "Hello World") == 0, "Found the correct path through the string maze");
    TEST_ASSERT(strlen(result) == 11, "Measured the corridor's true length");
    
    return 1; // Another passage conquered!
}
```

## 🎮 Sample Output

```
🏛️ LABYRINTH EXPLORATION: String Operations - Navigating the Labyrinth
════════════════════════════════════════════════════════
🔥 Sisyphus ventures deeper into the maze of logic!
💭 Each test reveals another secret of the architect's design

🚶 SISYPHUS EXPLORES: test_string_concatenation
🧠 INNER VOICE: Found the correct path through the string maze (+10 XP)
🧠 REALIZATION: Measured the corridor's true length (+13 XP)
✨ PASSAGE CONQUERED: test_string_concatenation (0.000023s)
   🗣️ 'Even in this prison, I find patterns. Beauty. Purpose.' -Sisyphus

🏆 ACHIEVEMENT UNLOCKED: First Blood! +7 XP
   First understanding of the maze's logic - the mind awakens!

🌟 LEVEL UP! Welcome to Level 2!
✨ Your comprehension of the Labyrinth deepens!

🪨 THE FIRST COMMIT
Daedalus unrolls a vast, impossibly complex blueprint. 'Your curse has been... 
updated, Sisyphus. The gods grew bored of the boulder. Minos, however, has a use for your persistence.'
```

## 🚧 Current Status & TODO

**What's Implemented:**
- ✅ Complete C testing framework with gamification
- ✅ 50-level story progression system
- ✅ 50+ achievements with historical context
- ✅ XP system with combo multipliers
- ✅ Progress tracking and archiving
- ✅ Time-aware mythological greetings
- ✅ Seasonal story variations

**Major TODOs:**
- [ ] **Multi-Language Support**: Python, JavaScript, Rust adapters
- [ ] **Story JSON Extraction**: Move hardcoded stories to configurable files
- [ ] **Act-Aware Test Messages**: Test narration changes based on story progress
- [ ] **Modular Architecture**: Break monolithic shell script into components
- [ ] **Web Dashboard**: Visual progress tracking and story viewer
- [ ] **Community Features**: Shared achievements and leaderboards
- [ ] **Educational Content**: Enhanced mythology and philosophy integration
- [ ] **Template System**: Easy test generation and project setup
- [ ] **CI/CD Integration**: GitHub Actions, GitLab CI support
- [ ] **Package Managers**: npm, pip, cargo packages

**Current Architecture:**
```
ASCIIGame/                    # Current implementation
├── run_tests.sh              # 3000-line monolithic orchestrator
├── tests.h                   # C testing macros and gamification
├── test_*.c                  # Example test files
└── .sisyphus/                # Progress data and archives
```

**Planned Architecture:**
```
sisyphus-test-framework/      # Future modular design
├── sisyphus.sh               # Main orchestrator
├── core/                     # Modular shell components
├── languages/                # Language-specific adapters
├── stories/                  # JSON story data
├── themes/                   # Customizable mythological themes
└── web/                      # Dashboard and visualization
```

## 🏗️ Architecture Vision

The framework consists of multiple layers:

### 🧠 Shell Orchestrator (`run_tests.sh`)
- Story progression and narrative management
- XP calculation and level progression
- Achievement tracking and unlocking
- Historical analysis and trend detection
- Session management and progress archiving

### 🔧 Language Adapters *(Planned)*
- **C**: `sisyphus.h` - Macro-based test assertions *(Current)*
- **Python**: `sisyphus.py` - Decorator-based testing *(TODO)*
- **JavaScript**: `sisyphus.js` - Framework integration *(TODO)*
- **Rust**: `sisyphus.rs` - Trait-based testing *(TODO)*

### 💾 Persistence Layer
- `.sisyphus/` - Archive directory (like `.git`)
- `sisyphus.legend` - Lifetime statistics and story progress
- Session archives with timestamp-based naming
- Achievement progress and unlock history

## 🏆 Achievement Examples

The framework includes over 50 achievements with historical significance:

- **🥇 First Blood** (7 XP) - First understanding of the maze's logic
- **⚔️ Spartan Warrior** (300 XP) - 500+ XP, 10+ combo, zero defeats
- **🐍 Hydra Slayer** (9 XP) - Overcome failures and still triumph
- **⚡ Zeus's Lightning** (9 XP) - Complete tests in under 0.5ms
- **👑 Philosopher King** (99 XP) - Ultimate mastery achievement
- **🔥 Divine Perfection** (144 XP) - 50+ tests, zero failures, sub-5ms

Each achievement teaches Greek history and mythology while you code.

## 📊 Progress Tracking

```
🎯 15,847 Project XP [███████░░░░░░░░░░░░░] 3,247/12,500 (Level 8)
💰 Session XP: 2,847 | 🧪 From Tests: 1,205 | 🔥 From Combos: 892 | 🏆 From Achievements: 750

📈 Recent trend: 🚀 ASCENDING TRAJECTORY - 4 consecutive improvements!
🏛️ Total Runs: 127 | 💎 Perfect Runs: 23 (18.1%) | ⚡ Peak Efficiency: 1,247x
```

## 🎭 The MIDAS Toolchain

Sisyphus is the **S** in the **MIDAS Toolchain** - a suite of mythologically-themed development tools:

- **M** - **Metis**: Smart code linter (Wisdom) *(Planned)*
- **I** - **Ixion**: Performance profiler (Watching hubris) *(Planned)*
- **D** - **Daedalus**: Core utility library (Master builder) *(In Development)*
- **A** - **Archimedes**: 2D game framework that can compile to WebAssembly (Genius of geometry) *(In Development)*
- **S** - **Sisyphus**: Gamified test framework (Legend of perseverance) *(Current)*

*"Turns all your C code into gold, so it can run on the web."*

## 🎪 Community & Goals

This project represents a unique intersection of:
- **Software Testing** - Making tests actually enjoyable
- **Greek Mythology** - Educational and immersive theming
- **Existential Philosophy** - Camus, absurdism, and the meaning of work
- **Game Design** - RPG mechanics applied to development tools
- **Developer Education** - Getting people excited about programming

### Educational Mission
One of the core goals is **teaching tech literacy** through gamification. By making programming tools feel like RPG adventures, we can:
- Lower the barrier to entry for new developers
- Make learning programming addictive instead of tedious
- Teach mythology, philosophy, and history alongside coding
- Create positive associations with testing and code quality

### Join the Eternal Struggle
- 🐘 **Mastodon**: Follow [@smattymatty@techhub.social](https://techhub.social/@smattymatty) for updates
- 🐛 **Issues**: Report bugs (they're just new challenges to overcome)
- 🎭 **Discussions**: Share your story progress and achievements
- 📖 **Wiki**: Contribute to mythology and philosophy documentation

## 🤔 Philosophy & Inspiration

This framework draws inspiration from:
- **Albert Camus** - *The Myth of Sisyphus* and absurdist philosophy
- **Greek Mythology** - The eternal struggle and heroic perseverance  
- **Game Design** - RPG progression systems and narrative rewards
- **Developer Experience** - Making necessary tasks genuinely enjoyable
- **Educational Psychology** - Dopamine-driven learning and engagement

> *"The struggle itself toward the heights is enough to fill a man's heart."* - Albert Camus

In the Sisyphus Test Framework, we embrace the absurd nature of endless testing and transform it into a source of meaning, growth, and genuine joy.

## 📜 License

MIT License - Because even eternal punishment should be open source.

---

**The boulder awaits. Will you push it to legendary status?** 🪨
