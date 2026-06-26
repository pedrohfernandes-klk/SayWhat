# SayWhat

**two men wait for something. allegedly.**

**SayWhat** is a two-minute browser-based audiovisual installation about waiting, social performance, failed banter, semantic collapse, and the strange violence of two overdressed men having too much time to fill.

Two random men stand in a liminal event-space. Something may be about to happen. Nobody has defined what. They wait, talk, waste time, joke, misunderstand each other, briefly get along, sometimes become philosophical, sometimes become ridiculous, and sometimes fight because the conversation has nowhere else to go.

The piece loops automatically. Each run is slightly different.

---

## Concept

SayWhat is not a game. It is a short generative HTML/canvas/audio experience.

The central situation is simple:

> two men wait for something. allegedly.

From that premise, the installation builds a rotating absurdist exchange: idle chatter, Beckett-like delay, Boris Vian-style object-world nonsense, internet-debate humiliation, office-life exhaustion, strange insults, and sudden brawls.

The men are not heroic characters. They are placeholders, witnesses, colleagues, opponents, clowns, adults, children, metaphors, and possibly just two suits trying to survive a pause.

---

## Runtime

* Duration: approximately **2 minutes**
* Ending screen appears after the run
* A restart countdown begins
* The piece automatically restarts after **10 seconds**
* Each restart regenerates timing, dialogue, fight placement, visual interruptions, and sound accents

---

## Interaction

The user starts the piece with the on-screen start button.

After that, the experience is mostly autonomous.

Controls may include:

* **Start**
* **Mute / unmute**
* Automatic restart countdown

The piece is designed for browser playback and should work on desktop and mobile, though desktop/headphones are recommended.

---

## Audio Direction

The sound is designed as an environmental headphone experience rather than a conventional soundtrack.

Main layers:

* **Environmental Rhodes / spybreak layer** — always present, spatial, slightly musical, behaving like strange room-tone
* **Bass pulse** — bodily, low, addictive, but not a full beat track
* **Muffled robot / spoken-word layer** — voices coming and going like interference
* **Kalimba accents** — comic/friendly glints during lighter moments
* **Distress voice layer** — emotional pressure during serious or compromised lines
* **Hardcore ambient layer** — fight pressure, escalation, and late chaos
* **Divebomb / squelch effects** — transitions, comic drops, brawl entrances
* **Muffled drums** — reserved for peak moments, both good and bad

The intended listening experience is unstable but pleasurable: environmental, funny, tense, and rhythmic without becoming a normal song.

Headphones are recommended.

---

## Visual Direction

The visual world is a liminal stage or waiting room with cosmic pressure.

Key visual elements:

* Two suited men
* Large expressive heads
* Animal-like head morphs
* A central event / eye / cosmic witness
* Drones and surveillance-like movement
* Speech bubbles and text fragments
* Random visual bursts during fights
* Redacted brawl overlays
* Glitch and pressure effects
* A final reset screen

The men should feel like drawn figures, not generic stick figures. Their heads, faces, eyes, mouths, posture, ties, shoes, and gestures carry much of the piece.

---

## Dialogue Tone

The dialogue should feel:

* absurd
* clipped
* dry
* funny
* occasionally cruel
* sometimes weirdly warm
* sometimes existentially serious
* never over-explained

The piece uses several dialogue modes:

* waiting / killing time
* friendly banter
* pointless small talk
* surreal object-world jokes
* Beckett-like delay logic
* Boris Vian-style poetic absurdity
* internet-debate humiliation
* office-life exhaustion
* brawl insults
* philosophical nonsense
* sudden sincerity

Example lines:

> Nothing is happening.
> Not true. We are noticing it.

> We could leave.
> Yes.
> Are we leaving?
> No.

> You are being defeated by your own sentence.

> Calm down, no need to crash out, mfer.

> The chair is breathing again.
> Good. One of us should.

> What are we waiting for?
> A gentleman with the head of a conclusion.

> My bank account is doing minimalism without my consent.

> You make the void look furnished.

---

## Brawls

Fights should feel random but narratively earned.

A fight may happen:

* in the middle
* late in the run
* almost immediately, as a cold open
* after a joke goes wrong
* after a debate line humiliates one of them
* after a philosophical question becomes too compromised

During brawls, expletives and fragments appear around the characters rather than in fixed positions.

Examples:

* **STFU**
* **MFER**
* **NO SHOT**
* **MOUTH BREATHER**
* **PREMISE ONE**
* **CATEGORY ERROR**
* **PANIC MERCHANT**
* **GIBBERATING**
* **VICTORY LAP**
* **WHAT CIRCLE**
* **CRASH-OUT WARNING**

The brawl is comic, unstable, and partly redacted. It should remain readable as physical conflict without becoming realistic violence.

---

## Technical Notes

The project is built as a standalone HTML file using:

* HTML
* CSS
* JavaScript
* Canvas API
* Web Audio API
* embedded audio samples

No build process is required.

To run locally:

```bash
open index.html
```

or use a simple local server:

```bash
python3 -m http.server
```

Then open:

```text
http://localhost:8000
```

A local server is recommended for more reliable browser audio behaviour.

---

## Browser Notes

Modern browsers require a user gesture before audio can begin. The start button is therefore necessary.

Recommended:

* Chrome / Chromium
* Edge
* Firefox
* desktop browser
* headphones

Mobile should be supported, but performance depends on device power and browser audio handling.

---

## Final Polish Priorities

Before calling the piece final, check:

* Start button works reliably
* Audio starts after user interaction
* Mute/unmute works
* Auto-restart works
* Countdown is visible
* Dialogue is readable on desktop and mobile
* Speech bubbles do not cover the whole image
* Fight timing randomises
* Expletive bursts randomise
* Some runs start calmly
* Some runs start strangely
* Some runs can begin with a fight
* Heads are large and expressive
* No unwanted Frankenstein-style forms remain
* Sound feels environmental on headphones
* Bass is audible but not destructive
* Drums hit peaks without becoming a full beat
* Comic moments feel lighter
* Fight moments feel chaotic
* Serious moments feel thicker and more uncomfortable

---

## Credits

**SayWhat** is an audiovisual HTML installation by **HrM**.

Created through iterative development using human direction, generative coding, audio sampling, and successive refinement across AI-assisted tools.

---

## Status

Work in progress.

The current direction is clear: make the piece sharper, funnier, more replayable, more visually designed, and more satisfying on headphones, while preserving the central absurdity:

Two men wait.
Something may happen.
Nobody knows what.
They continue anyway.
