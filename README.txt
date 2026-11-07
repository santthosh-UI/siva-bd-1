FRIENDLY BIRTHDAY WEBSITE

1. Extract this ZIP.
2. Keep the assets folder beside index.html.
3. Open index.html in a modern browser, or upload the complete folder to a static web host.

Included:
- Two supplied section photographs and the supplied portrait
- Combined two-minute audio
- Manual play controls for the two voice-message segments
- 25-click flower bouquet interaction
- Portrait with falling petals
- Birth-time entry interpreted as India Standard Time (IST)
- Hidden Google Forms response submission attempt
- Live age counter and butterfly animation
- Selected friendly birthday message

Important implementation notes:
- Browser autoplay restrictions mean the visitor must press Play for audio.
- Google Forms hidden submission is best-effort and must be tested against the live form. Google may block cross-origin or automated submission; the website cannot read Google's confirmation from a hidden iframe.
- For the exact age to be accurate, the birth-time input is interpreted as IST (UTC+05:30), and the current time is taken from the visitor's device.
- The bouquet advances one flower per click/tap. The 25th click opens the portrait surprise.
