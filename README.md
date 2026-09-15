
<p align="center">
  <img 
    src="https://github.com/user-attachments/assets/d2fd37ce-dec5-4719-856a-5dfa93f6a3fb"
    alt="Sloth Machine. Spin, Relax, Have Fun"
    width="500"
  >
</p>

<h1 align="center">🦥 One Armed Bandit </h1>
<p align="center"><em>SPIN · RELAX · HAVE FUN</em></p>

A tiny command-line slot machine, built by following this [YouTube tutorial](https://www.youtube.com/watch?v=th4OBktqK1I) — because apparently the best way to learn Python is to build a mini casino first.

> 🦥 **No money on the line. Just code, bugs, and good times.**
> The ₹ is fake, the sloth is chill, and the only real risk here is a typo.

---

## 📌 How It Works

1. Deposit some pretend money
2. Pick how many lines to bet on (1–3)
3. Pick your bet per line
4. Hit enter to spin
5. Match all 3 symbols in a row = you win
6. Keep spinning till you quit or go broke

Slow spins, big vibes. No PhD required.

---

## 🎯 The Symbols

**GOOD SLOTHS. GOOD TIMES.**

| Symbol | Shows up | Pays |
|--------|----------|------|
| A | Rarely | 5× bet |
| B | Sometimes | 4× bet |
| C | Often | 3× bet |
| D | Basically always | 2× bet |

Rare symbols pay more, common ones pay less. Classic slot-machine logic, minus the flashing lights and the crying.

**Winner? Maybe. Fun? Always.**

---

## 💻 What It Looks Like

```
What would you like to deposite? ₹100
Enter the number of lines to bet on (1-3)? 2
What amount would you like to bet on each line? ₹10

C | D | C
D | B | B
A | C | D

You won ₹0
Current balance is ₹80
```

Yep. Lost ₹20 and got nothing. Even the sloth on the poster looks unbothered.

---

## 🚀 Run It

```bash
git clone https://github.com/Amhatre-15/one-armed-bandit.git
cd one-armed-bandit
python main.py
```

No installs, no dependencies. Just Python and vibes.

---

## 🧠 What You'll Learn

Nothing fancy — just the real basics, stitched together into something that actually runs:

- **Functions** to keep the code from turning into spaghetti
- **Dictionaries** to store symbol odds and payouts
- **\`random.choice()\`** to spin the reels
- **Input validation** so the game doesn't crash the moment someone types "banana"
- **Passing variables into functions** instead of using globals everywhere

Good code, good mood. That's genuinely all a beginner needs to get this working — everything else is just polish.

---

## ⚠️ What It Doesn't Do (Yet)

No GUI, no sound, no saved balance, no diagonal wins. It's a learning project, not a Vegas launch.

## 🔮 Ideas to Try Next

Diagonal lines, colors, sound effects, saved high scores, unit tests — pick one and go break something.

*Just one more spin, right?*

---

## 🙌 Credits

Built by following this tutorial: [Learn Python With This ONE Project! (YouTube)](https://www.youtube.com/watch?v=th4OBktqK1I)

All credit for the original idea and teaching goes there — this repo is just me typing along, occasionally breaking things, and apparently adopting a sloth mascot along the way.

---

## 📄 License

For learning. Play responsibly (with fake money).
