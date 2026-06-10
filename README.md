# Y2K Love Bug Protocol 💖💾

A cute, retro, Windows 98/Y2K-themed interactive website to ask your crush out on a date! Built with pure HTML, CSS, and vanilla JavaScript. 

Check out the live site here: https://abdrash12.github.io/Ask_Out_Your_Date/

## ✨ Features
* **Millennial Pink Aesthetic:** Custom pixel-art SVG graphics, grid backgrounds, and classic Windows dialogue boxes.
* **The "Unclickable" No Button:** The 'No' button runs away from the cursor and has a 15% chance to "explode" with a retro 8-bit sound effect.
* **Celebration Mode:** Clicking 'Yes' triggers a retro chime and a shower of hot pink/white pixel confetti and hearts.
* **Interactive Scheduler:** Lets them pick a date and the "vibe" (e.g., Fine Dine, KFC in Formal Wear).
* **Itinerary Export:** Generates and downloads a custom `.txt` file with the final date details.
* **Background Music:** Plays your favorite local `.mp3` track the moment they interact with the page!

## 🛠️ How to Customize for Yourself

If you want to fork this and use it for your own date, here is how to set it up:

1. **Clone or Download** this repository.
2. **Add your own music:** * Find an `.mp3` file of the song you want to play.
   * Rename it to `eyes.mp3` (or whatever you like).
   * Place it in the exact same folder as the `index.html` file.
   * Open `index.html` and update the `<source>` tag near the top to match your file name:
     ```html
     <source src="eyes.mp3" type="audio/mpeg">
     ```
3. **Change the Vibes:** * Search `index.html` for the `<select id="activityPicker">` tag and change the `<option>` tags to whatever date ideas you want!


