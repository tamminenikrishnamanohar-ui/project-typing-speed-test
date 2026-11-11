### ⚙️ JavaScript Core Logic & Technical Implementation (Member 3)

The application relies entirely on client-side JavaScript (no external frameworks, databases, or backend servers) to deliver a seamless real-time typing experience.

#### 1. Core Functions & Algorithms
* **Countdown Timer (`setInterval`):** Initializes upon the first keystroke, tracking elapsed time and updating the remaining countdown dynamically every second[cite: 64, 69].
* **Words Per Minute (WPM) Calculation:** Computes speed in real-time using standard formula indexing[cite: 64, 65, 69]:
  $$\text{WPM} = \left(\frac{\text{Correct Characters}}{5}\right) / \text{Time in Minutes}$$
* **Accuracy Tracking:** Compares user input against the target passage character-by-character to calculate percentage accuracy[cite: 64, 69].
* **Dynamic Character Highlighting:** Iterates over the string length to visually flag correct (green) and incorrect (red) keystrokes in real time[cite: 64, 65, 69].

#### 2. Data Persistence (`localStorage`)
* Session history, personal best scores, and past performance metrics are stored locally using browser `localStorage`[cite: 69], allowing users to view their **Personal Leaderboard** and **Previous Test History** across reloads.

#### 3. Testing & Validation Checklist
* Verified timer termination and automatic score locking when time runs out.
* Tested edge cases such as backspace handling, rapid typing, and clearing history.
```[cite: 69]
