# minigames-fish
HTML code for Blogger or Wordpress

Embeddable Blogspot Mini-Game: Feed the Fish
This project provides a simple and delightful "Feed the Fish" mini-game created with HTML and JavaScript, designed to be easily embedded into any Blogspot post or page.

It offers a light, interactive distraction for your website visitors, perfect for keeping them engaged while they wait for notifications or simply to add a fun element to your blog.

Features
Zero Dependencies: Runs entirely in the browser with no external libraries needed.

Single File: All the code (HTML, CSS, JS) is in one file for easy copy-pasting.

Interactive: Click to drop food and watch the fish swim to eat it.

Responsive: The game canvas automatically resizes to fit its container.

Customizable: Easily change the number of fish, colors, and other parameters.

How to Embed in Blogspot
You can add this game to your blog in just a few steps:

Copy the Code: Open the index.html file in this repository and copy its entire content.

Go to your Blogspot Dashboard: Log in to your Blogspot account.

Create or Edit a Post/Page: You can either create a new post/page or edit an existing one where you want the game to appear.

Switch to HTML View: In the Blogspot editor, find and click the button that switches from "Compose view" to "HTML view". This usually looks like < >.

Paste the Code: Paste the code you copied directly into the HTML editor.

Publish: Save or publish your post/page. The "Feed the Fish" game will now be live on your blog!

Customization
You can easily tweak the game by changing the values in the "Game Configuration" section of the <script> tag in the HTML file.

// --- Game Configuration ---
const FISH_COUNT = 7; // How many fish in the tank
const FOOD_DURATION = 500; // How long food lasts (in frames)
const FISH_SIZE = 15; // Base size of the fish

FISH_COUNT: Change this number to have more or fewer fish in your tank.

FOOD_DURATION: Increase or decrease this to change how long food pellets stay on screen before disappearing.

FISH_SIZE: Adjust the base size of the fish.

Check out our other projects and products at our shop: Atunt Shop

License
This project is open-source and available under the MIT License.
