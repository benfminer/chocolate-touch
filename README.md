# The Chocolate Touch

Classroom pages for a 3rd-4th grade reading group working through *The Chocolate Touch* by Patrick Skene Catling. Everything runs in a web browser, so it works on a smart screen, a laptop, or a projector.

**Open it here: https://benfminer.github.io/chocolate-touch/**

| Page | What it is | Link |
|---|---|---|
| Do You Have the Chocolate Touch? | Ch 6 walk-up station with one Makey Makey | [Open](https://benfminer.github.io/chocolate-touch/chocolate-touch-test.html) |
| Chocolate Touch Lab | Ch 6 Makey Makey games for up to 6 players | [Open](https://benfminer.github.io/chocolate-touch/ch6-makey-makey.html) |
| Story Recap | Chapter recap slideshow with a spoiler gate | [Open](https://benfminer.github.io/chocolate-touch/chocolate-touch-recap.html) |
| Chapter 3 Lesson | Presentation deck with speaker notes | [Open](https://benfminer.github.io/chocolate-touch/ch3-presentation.html) |
| Chapter 3 Packet | Printable materials | [Open](https://benfminer.github.io/chocolate-touch/ch3-packet.html) |

## Do You Have the Chocolate Touch?

One Makey Makey sits at the front of the room. Each person walks up, puts one hand on a foil "magic star," and touches a foil coin with the other hand. The screen builds suspense, then shows whether they have the chocolate touch. It works for students. The teacher secretly makes it fizzle for teachers.

### What you need

- 1 Makey Makey plugged into the device running the browser (the smart screen itself, or the laptop connected to it)
- 1 foil coin (the touch coin)
- 1 foil star, big enough for a flat hand (the magic star)
- 2 small foil strips for your secret pads, plus 1 more for your own ground
- Alligator clips and tape

### Wiring

| Makey Makey | Goes to | Who touches it |
|---|---|---|
| **Space** | The foil coin | Students and teachers |
| **Earth** | Under the magic star (tape the wire down so it's hidden) | Everyone, with their other hand |
| **Left arrow** | Secret pad 1: fizzle | Teacher only |
| **Click** | Secret pad 2: next person | Teacher only |
| **Earth** (a second Earth hole) | A foil strip by your secret pads | Teacher only |

Your secret pads only work while you're touching your own ground strip, the same way students need the star. Make sure every clip touches bare foil, not tape.

### Running it

1. Open the [test page](https://benfminer.github.io/chocolate-touch/chocolate-touch-test.html) and tap the screen once so it listens to the Makey Makey.
2. Tap again (or press Enter) to start.
3. A student walks up: hand on the star, touch the coin. They get the chocolate touch.
4. A teacher is coming up? **Before** they touch, press your Left pad (or T on the keyboard). The tiny dot in the bottom-right corner turns into a hollow ring. Their touch will fizzle.
5. The result stays on screen until you press your Click pad (or Enter, or tap the screen). Then the next person comes up.
6. The fizzle only lasts one turn, so the next person gets the chocolate touch unless you press Left again.

### Controls

| Action | Makey Makey | Keyboard / screen |
|---|---|---|
| Touch (the student's turn) | Space coin (Up, Down, Right also work) | Space |
| Make the next touch fizzle (press again to cancel) | Left pad | T or Left arrow |
| Next person | Click pad | Enter, or tap the screen |
| Show/hide the teacher key card | | H (don't press it while the class is watching) |
| Sound on/off | | M |
| Fullscreen | | F |

**Your secret signal:** the tiny dot in the bottom-right corner. A solid dot means it will work. A hollow ring means it will fizzle.

### Troubleshooting

- **"Click anywhere so the coin works" covers the screen:** the page lost focus. Tap it once.
- **Touching the coin does nothing:** the person needs their other hand flat on the star. Check that the Earth clip is touching bare foil.
- **It jumped to the next person early:** someone tapped the smart screen while a result was showing. That's harmless. It just goes back to the waiting screen.
- **No sound:** tap the page once (browsers block sound until you interact), and check that M didn't mute it.

Always do a test run before class. Foil and alligator clips can be finicky.

## Updating the site

Push changes to the `main` branch and GitHub Pages updates in about a minute. The book PDF and transcript are kept out of this repo on purpose (see `.gitignore`).
