# MIDI to PT

Ableton Live doesn't write the tempo into the MIDI files it exports, so Pro Tools reads them at 120 BPM.
MIDI to PT adds the right tempo and merges every exported clip into one multitrack MIDI file, ready for Pro Tools.

**Use it:** https://joli-studio.github.io/midi-to-pt/

- Drop the `.mid` files exported from Ableton (one clip per track).
- Enter the set's BPM and time signature, and the bar where each clip started.
- Download one `.mid` with every track and the tempo, then in Pro Tools: File › Import › MIDI, and tick *Import Tempo Map From MIDI File*.

Everything runs in the browser: files are never uploaded, and the page sets no cookies.

Made by [Joli-Studio](https://joli-studio.github.io/a/). If it saved you time: [ko-fi.com/adrienjolijo](https://ko-fi.com/adrienjolijo).
