# 🧊 fantaIPICS

[![Event](https://img.shields.io/badge/Event-IPICS_2026_Banff-blue)](https://www.ipics2026.org/)
![Deployment](https://img.shields.io/badge/Deployment-GitHub_Pages-success)

**fantaIPICS** is a fantasy-league web game designed for the IPICS 2026 conference in Banff! 

Given that fabulous things seem to happen at every IPICS edition, **fantaIPICS** was created to keep track of them. Every colleague taking part in the conference can be both a player and a participant: depending on their actions during the week, they can earn or lose points. Participants select a team of colleagues, and the person whose team scores the most points by the end of the week wins.

Clearly, fantaIPICS can adapt to any conference or event.

---

## 🎮 How to Play

### 0. Initiating Everything
**The administrator** shall initiate a **cloud database (in our case, JSONBIN.io was used) and edit the code** to add all the colleagues that want to participate in the game. Then, it shall create a WhatsApp group or equivalent for the colleagues  to report the bonuses and maluses hey will witness during the event. 
 
### 1. Set Up & Draft Your Roster
* **Claim your identity:** select your player identity from the header dropdown and click the 🔑 to bind your identity to your device.
* **The budget:** you have a maximum budget of **30 Giuliani** (or whatever name you want to assign to your coins) to spend on your team.
* **Roster size:** head over to the **✏️ ROSTER** tab and pick **1 to 3 colleagues** from the available categories. (Note: You are not required to pick 3 players or spend your entire budget).
* **Lock it in:** once you are satisfied with your draft, click **"Lock Roster 🔒"** to permanently seal your choices into the real-time cloud database.

### 2. The Rules of the Game
* Check the **📜 LISTS** tab for the official catalog of actions that trigger a *bonus* (✨) or a *malus* (⚠️).
* **Reporting:** If you spot a colleague performing an action from the list, signal it by sending a message or picture to the official WhatsApp Group.
* **Proof is required:** to be considered valid, your report must be accompanied by a picture, a video, or a verifying statement from at least one other colleague (a witness). 

### 3. Track the Leaderboard
Check the **📊 LEADERBOARD** tab to see live standings. The leaderboard is updated in real-time as the admin awards or deducts points based on verified reports.

## 🏆 The Prize
Aside from the ultimate glory of winning fantaIPICS, the people participating to the game shall discuss the prize for the winner (beer is always a good idea 🍺).

---

## 💻 Technical Features
* **Real-time cloud sync:** the application utilizes a live backend cloud database to synchronize roster locks, user identities, and live leaderboard point adjustments instantly.
* **admin console:** a built-in, passcode-protected **🎛️ Admin Dashboard** allows the game master to award points, deduct penalties, and maintain an immutable Event Log History.
* **Reactive UI:** built as a modern, reactive single-page application (SPA) using mustache-style templating, perfectly tailored for mobile-friendly use during the conference.
