# Mitthu's Varnmala

A 90-second hand-drawn, cut-paper collage film that teaches the Hindi alphabet (हिंदी वर्णमाला):
all 13 swar (vowels, including अं and अः) and 37 vyanjan (33 consonants plus क्ष त्र ज्ञ श्र).

**Watch it live:** https://akashgoyal.github.io/claude-experiments/JS-Codes/hindi-varnmala/

- Pure JavaScript on a `<canvas>`: no libraries, images, or audio files
- Each letter is read aloud ("क से कमल") with the browser's Hindi text-to-speech voice, if the device has one
- Music is synthesized live with the Web Audio API: tanpura drone, keherwa on tabla, santoor
- Controls: play/pause (or Space), restart, mute music, voice on/off, and a clickable progress bar

Open `index.html` in a browser and press **Play with sound**. Chrome and Edge usually include a Hindi voice; on macOS it's the system voice Lekha.
