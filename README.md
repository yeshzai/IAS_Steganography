# Who Killed Who 🔍🕵️‍♂️

A story-driven, interactive murder mystery web game where players analyze digital clues to uncover the killer.

## 🕹️ About the Game
This game invites players to explore the contents of a fictional victim’s computer. Players must examine files, solve puzzles, and uncover clues hidden across folders, images, and videos—some using steganography and digital forensics-inspired techniques.

## 🛠 Technologies
- HTML / CSS / JS
- Bootstrap
- Image/Audio Steganography
- Google Drive for file hosting
- Git version control

## 📁 Project Structure
├── index.html            # Main landing page
├── scene.html            # Scene-specific page
├── screen.html           # Screen-specific page
├── audio/                # Background music and sound effects
├── img/                  # Game visuals and clues
├── log/                  # Logs and evidence files
├── person/               # Character visuals
├── video/                # Glitched footage and evidence
└── README.md             # Project documentation

## 🗂️ Key Folders
- Suspect Profiles
- Evidence Folder
- Encrypted Logs
- Glitched Media
- Puzzle-locked Clues

## 🧠 Gameplay Highlights
🔓 Solve password-protected and PIN-protected modals to reveal key evidence
🖼️ Discover hidden data inside images and videos
🧬 Trace DNA and activity logs
💻 Piece together the truth from misleading files

## 🔗 How to Play
Open the main `index.html` in your browser and start investigating.

Step-by-Step to Win:
1. Start at index.html: The game introduces the mystery. Begin by exploring the premise.

2. Explore scene.html:
    - Interact with Vincent’s Laptop: Unlock it using image steganography (find and piece together the hidden PIN).
    - Untitled Folder: Find the password to unlock the folder on the victim's computer.
    - Evidence Folder: Watch the video clue to uncover more information.
    - Pending Analysis Folder: Use steganography to extract hidden clues from images and videos.

3. Go to screen.html: Use the found passwords to access the terminal interface and unlock the final log, which will reveal the identity of the victim.

4. Final Clue: Use the video steganography clues to piece together the information about the killer and solve the mystery.

5. End Goal:
    - Find the Victim: Unlock and access the log to identify the victim.
    - Find the Killer: Combine the hidden clues found in the video steganography to uncover the killer.

## 🖱️ Interactive Elements
- 🔍 **Clickable Clues** — fingerprints, id card, crumpled paper
- 🧩 **PIN Modal Puzzle** — enter a discovered 9-digit PIN to unlock Vincent's laptop
- 🎥 **Media Folder** — contain audio/image steganography clues

## 🎮 Tips
- Some files are **meant to mislead you**.
- Not all clues are in plain sight. Dig deep. Think like a hacker 🧠.