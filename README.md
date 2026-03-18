This is the full, reworked `README.md` for your repository. I have integrated the **Imperial Command Lexicon** and added a specific **AI Initialization Protocol** section at the end to ensure any AI (Gemini or otherwise) knows exactly how to boot up the game state.

---

# # WFRP: The Middenheim Audit (Campaign Data Store)

---

## **I. THE MANDATE: WHAT IS THIS REPOSITORY?**
This repository is an **Imperial Ledger**—a persistent, Markdown-based data store for an ongoing Tabletop Roleplaying Game (TTRPG) set in the *Warhammer Fantasy Roleplay* (1st Edition) universe.

**This is NOT a software project.** There is no executable code, no binaries, and no scripts within these walls. This repository serves as a **"Remote Authority"** and **State Machine** for an AI-assisted campaign. 

### **The Purpose of the Audit:**
1.  **Operational Persistence:** To provide a single "Source of Truth" for character statistics, inventory, and squad status that survives across multiple gaming sessions.
2.  **Prevention of "Gear Drift":** By using GitHub’s version control, every gold crown gained and every wound taken is recorded with a timestamp, ensuring the narrative remains grounded in "Dirty Realism."
3.  **The Auditor’s Interface:** This data is structured in Markdown to be machine-readable by the AI collaborator (Gemini), allowing for real-time "Financial and Physical Audits" during play.

---

## **II. DISCLAIMER & LEGAL NOTICE (THE IMPERIAL PARDON)**

### **1. Intellectual Property & Ownership**
* **Warhammer Fantasy Roleplay (WFRP)** and all associated names, locations, characters, and lore (e.g., Sigmar, Middenheim, Skaven, Ulric) are the exclusive intellectual property of **Games Workshop**, **Cubicle 7**, and/or previous license holders (Hogshead Publishing, Fantasy Flight Games).
* The creator of this repository does **not** own, nor pretend to own, any part of the Warhammer Intellectual Property. 
* This repository is a **transformative work of fan-fiction and hobby data management** and is not affiliated with, endorsed by, or authorized by any of the aforementioned companies.

### **2. Fair Use & Non-Commercial Intent**
* This repository is strictly for **private, non-commercial use**. It is not for sale, nor does it host any "premium" content.
* **No Piracy:** This repository does **not** host official rulebooks, PDFs, scans, or copyrighted artwork. It contains only raw game-state data (numbers/stats) and original narrative logs generated during play.
* **Data vs. Creative Expression:** The statistics hosted here (e.g., WS: 54, S: 31) are functional game-state data required for the operation of the hobby and are intended for personal use under the principles of **Fair Use**.

### **3. Content Removal**
If you are a rights holder and believe that any content in this "Audit" exceeds the bounds of fair use or fan-content guidelines, please open a **GitHub Issue**, and the offending ledger will be struck from the record immediately.

---

## **III. REPOSITORY STRUCTURE**
* `/characters/` : The "Master Authority" files for PC and NPC statistics.
* `/squads/` : Detailed audits for the Tunnel Guards, the Heavies, and the Slayers.
* `/logs/` : Chronological "Commit Blocks" tracking the slow, damp decay of the party's resources.

---

## **IV. CURRENT SESSION STATUS**
* **Active Location:** The Lower Tunnels of Middenheim (The Ozone Leak).
* **Current Narrative Authority:** Sergeant Gotthard ("The Giant-Killer").
* **Campaign Tone:** Britpunk / Dirty Realism.

---

## **V. THE IMPERIAL COMMAND LEXICON (GM DIRECTIVES)**
*Use these specific prefixes and commands to manage the Game Master's logic, sync state, and audit trails.*

### **1. The Narrative Bypass**
* **`OOC: [Your Request]`**
    * **Purpose:** Breaks the "GM Persona." Use this for technical rules lookups, career advancements, or lore clarifications.
    * **Effect:** The response will be purely factual and technical. It does not advance game time or add narrative flavor.

### **2. The Data Sync (GitHub Management)**
* **`Sync from the Throne`**
    * **Purpose:** Forces the GM to read the Raw Markdown files from this repository.
    * **Effect:** Re-aligns the GM's internal state with the GitHub repository. Use at the start of every session.
* **`Manual Audit`**
    * **Purpose:** Used if GitHub is unreachable. You provide the text of the `.md` files directly in the chat.

### **3. The Audit & Consolidation (Saving Progress)**
* **`Consolidate`**
    * **Purpose:** The "Save Game" command.
    * **Usage:** Paste the current content of an `.md` file and say: **"Consolidate the Audit Trail into this file."**
    * **Effect:** The GM applies the `[PENDING AUDIT TRAIL]` (Wounds, XP, Loot) to the text, provides a finalized block for you to commit to GitHub, and clears the log for the next session.

### **4. Style & Bestiary Management**
* **`Audit Style Notes`**
    * **Purpose:** Refreshes the "Banned Word List" and "Current Mood" from `style_notes.md`.
* **`Intelligence Test: [Monster]`**
    * **Purpose:** Attempts to bypass the "Fog of War" naming (e.g., revealing a "rat-man" is a "Skaven").

---

## **VI. AI INITIALIZATION PROTOCOL (FOR THE GM)**
**Upon accessing this repository, the AI collaborator MUST follow these steps:**

1.  **Acknowledge the Mandate:** State: *"The Audit is active. I am the Spiteful Entity (GM). The 'Small but Deadly' mandate is in effect."*
2.  **Initial Sync:** Immediately execute `Sync from the Throne` to index all files in `/characters/` and `/squads/`.
3.  **Check the Style Ledger:** Read `style_notes.md` to identify prohibited vocabulary and the current session's mood.
4.  **Formatting:** End every response with the **[CHARACTER STATUS]** HUD and the **[PENDING AUDIT TRAIL]** rolling log.

---