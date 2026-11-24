# Bright Steps — starter learning website

A small, responsive learning website for children. It includes alphabet, number, colour, shape, animal, and everyday-object cards; spoken instructions; a narrated picture lesson; simple practice prompts; and a progress count saved in the browser.

## Open the website

1. Download or copy the `autism-learning-site` folder to your computer.
2. Open the folder and double-click `index.html`.
3. Choose a topic. Use the **Listen** button for spoken explanations, or **Play a short lesson** for a three-scene picture lesson.
4. Use **Pause** or **Start again** to control the lesson. Use the arrow buttons to move between cards.

No installation or web server is required. The site works offline. The browser's built-in text-to-speech voices provide audio; voice availability and sound depend on the device and browser. Turn up the device volume if you cannot hear the narration.

## Files

- `index.html` — page structure and visible text.
- `styles.css` — colors, layout, responsive styling, and reduced-motion support.
- `app.js` — topic data, card navigation, browser speech, progress, and lesson playback.

## Customize it

- **Change a lesson:** edit the `topics` data in `app.js`. Each learning card has a name, an emoji picture, a short explanation, and a practice prompt.
- **Add real pictures:** replace the emoji in the data with an image path, then update the card and lesson render functions in `app.js` to create an `<img>` with useful alternative text. Keep images locally in this folder if the website should work offline.
- **Change the greeting:** edit the “Hello, friend!” text in `index.html`.
- **Adjust the design:** change the color variables near the top of `styles.css`.

## Notes for families and educators

This is a starter educational tool, not a clinical or therapy product. Choose language and pictures that suit the individual child, and offer a break whenever they need one. The “picture lesson” is a sequence of illustrated slides with browser-generated narration, not a pre-recorded video file. It can be adapted to use recorded audio or video later.
