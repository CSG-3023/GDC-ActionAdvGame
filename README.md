# 🧭 Action Adventure Game - GDC Assignment Sheet

###### 🎮 Game Design Challenge | ⚙️ Game Development | ⏱️ TIMELINE: 2-3 Weeks

## 📖 Overview

For this **Game Design Challenge**, you will design and develop a **Prototype (Draft)** of an Action-Adventure game that demonstrates the intended player experience through approximately **1–2 minutes of fun, playable gameplay** while meeting the design and technical requirements provided in the challenge documentation.

> [!Important]
> Review and follow the **[Game Design Challenge Guidelines](https://csg-utulsa.github.io/csg-assignments/game-design-challenges/index.html)** before beginning development.

---

## **📋 Project Requirements**

The following requirements establish the creative direction, intended player experience, and technical expectations for the project. Your team will develop its own game concept and determine how these requirements are incorporated into the design.

### **Creative & Design Requirements**

| Category                    | Description                                                                                                                                                      |
| --------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Genre / Style**           | Action-Adventure                                                                                                                                                 |
| **Platform**                | Web (Unity WebGL build)                                                                                                                                          |
| **Target Audience**         | Ages 10–16 (middle school to early high school), who enjoy casual action and adventure games.                                                                    |
| **Player Motivation**       | Exploration, mastery, and excitement.                                                                                                                            |
| **Player Experience Goals** | Players should explore varied environments, tackle challenges that test their skills, and experience fast-paced, surprising moments that keep gameplay exciting. |
| **Gameplay**                | Combine action-based gameplay with exploration, puzzles, and interactive challenges.                                                                             |
| **Levels**                  | At least two playable levels or zones that demonstrate different environments, objectives, or challenges.                                                        |

### **Technical Requirements**

| System                         | Requirements                                                                                           |
| ------------------------------ | ------------------------------------------------------------------------------------------------------ |
| **Player Controller**          | Implement scripted player controls using Unity's New Input System.                                     |
| **NPCs / Interactive Objects** | Include at least one type of NPC, enemy, or interactive element with behavior.                         |
| **Object Spawning**            | Instantiate objects dynamically using scripts.                                                         |
| **Object Pooling**             | Implement object pooling for repeated objects such as projectiles, pickups, or other reusable objects. |
| **Game Manager / Singleton**   | Manage game states, including Playing, Paused, and GameOver.                                           |
| **Scene Management**           | Implement transitions between levels and menus using Unity's SceneManager.                             |
| **Menus & UI**                 | Use UI Toolkit to implement a main menu, pause menu, and HUD.                                          |
| **Action / Event Systems**     | Use the Observer pattern to manage interactions and state changes between game objects.                |
| **Optimization & Performance** | Use efficient physics, object pooling, and update calls to maintain performance.                       |
| **Collaboration**              | Every team member must contribute code to a distinct gameplay feature or system.                       |

> [!IMPORTANT]\
> **Team Collaboration**
>
> Every team member must take responsibility for developing a distinct gameplay feature or technical system. Teams should identify these responsibilities during planning and document individual contributions throughout development.

---

## **📝 Assignment Instructions**

### **1. Review the Project Requirements**

Review the creative, design, and technical requirements established for this challenge.

Your team should understand the expectations before beginning concept development. These requirements establish the boundaries of the project but do not prescribe a specific game, story, setting, or gameplay concept.

---

### **2. Brainstorm a Game Concept**

As a team, brainstorm and develop an original **Action-Adventure game concept** that combines exploration, puzzles, and action.

The game should provide opportunities for players to explore environments, interact with the world, overcome challenges, and progress through meaningful gameplay objectives.

As you develop your concept, focus on the following two dimensions of the **PLAYER Framework**:

| Dimension                     | Guiding Question                                                                                                              |
| ----------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| **P — Player Identification** | Who is the player? What role do they take on in the game, and what makes them interesting to play?                            |
| **L — Layered Interaction**   | How does the player interact with the game? What actions, mechanics, puzzles, and challenges make up the gameplay experience? |

These dimensions should guide the game's concept, creative direction, and design decisions throughout development.

---

### **3. Create a Player Persona**

Create a **Player Persona** that represents the intended audience for the game.

1. Complete the Player Persona Form in **Harvey**.
2. A PDF copy of the completed persona will be emailed to you.
3. Include the completed PDF as part of your Project Wiki documentation.

The persona should describe the type of player the game is designed for, including their characteristics, motivations, and preferences. Use it to help guide decisions about the game's atmosphere, gameplay, interactions, and overall experience.

---

### **4. Document the Project in the GitHub Wiki**

Maintain and update your **Project Wiki** throughout development to document the game's concept, design, gameplay, and technical implementation.

The Wiki should provide a clear overview of the game and explain how its major gameplay systems, level designs, quests, puzzles, and interactive elements work.

#### **Required Project Documentation**

| Document                                                                                                                     | Description                                                                                  |
| ---------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| **Concept Document**| Establishes the game's concept, premise, setting, theme, and creative direction.             |
| **Player Persona(s)**| Defines the target audience, including player characteristics, motivations, and preferences. |
| **Game Brief**   | Establishes the game's goals, requirements, scope, and overall design direction.             |
| **Quest & Puzzle Design** | Describes the quests, puzzles, objectives, and interactive challenges within the game.       |
| **Technical Brief**         | Defines the technical requirements, development tools, systems, and implementation approach. |
|**Asset Inventory**      | Tracks the assets used in the project, including their sources, purpose, and implementation. |

> [!IMPORTANT]\
> **Project Wiki Documentation Guidelines**
>
> - **Templates Provided:** Each Wiki page already includes a template with guidance and prompts to help complete the documentation.
> - **Relevant Content:** Review the provided template and remove any sections, prompts, or content that are not applicable to the project or your responsibilities.
> - **Writing Style:** Write documentation in **third person**, as if communicating with the game's development or publishing teams. Documentation should describe the game, its design, and its requirements rather than address the reader directly.
> - **External Assets:** Save any external files you want to include in your Wiki, such as the Player Persona PDF, reference images, or diagrams, in the appropriate `docs/` or `docs/imgs/` folder in the root of your project repository. Link to these files from the relevant Wiki pages.
> - **Keep It Updated:** Maintain the Project Wiki throughout development so it accurately reflects the game's design and implementation.

---
### 5. Track Your Progress Using GitHub Issues

Use **GitHub Issues** to track your assigned tasks and document your progress throughout development.

Create a new GitHub Issue for each task you are assigned or take responsibility for. Use the issue to record updates during each work session so the team can track progress, identify challenges, and stay informed about ongoing work.

For each work session, provide an update that includes:

- **Progress:** Describe the progress made on the task since the last update.
- **Slowdowns / Setbacks:** Identify any challenges or obstacles encountered while working on the task.
- **Completed:** List the portions of the task that have been fully finished or delivered.
- **Plans:** Outline your plans for the upcoming week, including any adjustments based on setbacks or new insights.
- **Images:** When applicable, include screenshots or images that illustrate the progress made on the task.

> [!WARNING]
> **Project Participation**
> Your GitHub Issues and weekly progress updates will be used to evaluate your participation and contributions to the project. Consistently documenting your work is an expected part of your responsibility as a team member.

---

### 6. Build and Publish the Game

1. Create and test a **WebGL build** of your completed game. Ensure the game loads, plays correctly, and provides the intended player experience.

2. Publish your WebGL build to **itch.io** so the game can be played directly in a web browser.
   - Follow the **[Upload to Itch.io Tutorial](https://csg-utulsa.github.io/csg-assignments/tutorials/itch-io/TU-Itch-io-Submission.html)** for the required upload and configuration process.
     
3. **Add your team members as itch.io contributors.**
   - After uploading your game to itch.io, follow the **[Adding Itch.io Contributors Tutorial](../../tutorials/itch-io/TU-Itch-io-Contributors.md)**.
   - Make sure all members of your development team are properly credited as contributors.

---

### 7. Submit Your Project

Submit the following URLs through Harvey:

- **itch.io:** URL to your publicly accessible, playable game.
- **GitHub Repository:** URL to your project repository.
- **GitHub Wiki:** URL to your Project Wiki.

Your GitHub Wiki must include:

- Completed **Creative Direction** section of the Concept Document.
- **Core Gameplay** documentation.
- **Gameplay Loop** flowchart.
- **Objects & Entities** documentation.
- Completed **Asset List**.
- **Class Diagram**.

> [!WARNING]
> **Your project cannot be graded if it is not accessible.**
>
> Your GitHub repository and Wiki must be in the **course organization**, and your itch.io game must be **publicly accessible and playable**.

---

#### Final Check 📋

Before submitting, make sure the following project deliverables are complete:
- [ ] Is my GitHub repository and Wiki in the **course organization**?
- [ ] Does my game demonstrate approximately **1–2 minutes of playable gameplay**?
- [ ] Is my game's theme, presentation, and gameplay appropriate for the intended target audience?
- [ ] Does my game provide a clear and engaging core gameplay loop?
- [ ] **GitHub Wiki:** All required documentation is complete, updated, and reflects the final game.
- [ ] **GitHub Issues:** All assigned tasks have been documented, completed, and their issues closed.
- [ ] **WebGL Build:** A final WebGL build has been created and tested.
- [ ] **itch.io Publication:** The final game is uploaded, publicly accessible, and playable on itch.io.
- [ ] Have I submitted my game to the **Playtest Game Jam**?
- [ ] Have we added all team members as **itch.io contributors**?
- [ ] Do all submitted URLs work and provide the required access?


