# [BTS](https://scherrer-txt.github.io/bts/)

BTS (Behind the Screens) is a blog by scherrer.txt (Kevin Wulfric Scherrer). Originaly created in June of 2020, migrated to Github Pages in March of 2024.

## To-do
- [] Finish bts-18!
- [] Redesign "Citace"
- [] Upload images for bts-01, bts-02 and bts-03

## Backlog/Ongoing
- [] Simplify the code
- [] Fix the lazy load script
- [] Make the website even more accessible 
- [] Make the images smaller (*jekyll-assets/jekyll-compress-images/image-optim*)
- [] Hardcode that the default theme is DARK

- [] TOC: Final Form
    - Bar under menu — Actual headline | [TOC icon] ← dropdown with all headlines (*levels 1-3*)
- [] MENU: Final Form
    - Desktop
        - Menu item 1 — Menu item 2 — Menu item 3 | [Gear icon] ← dropdown with "Theme [ Dark | Light ]" & "Font size [ - | + | ↺ ]"
    - Mobile
        - Menu item 1 — Menu item 2 — Menu item 3 — "Theme [ Dark | Light ]" — "Font size [ - | + | ↺ ]"

## Did
- [x] Redesign "Credits"
- [x] Redesign TOC
- [x] Fix some mobile issues
    - [x] Disable :hover
    - [x] Disable menu scroll
    - [x] Make the footer responsive
    - [x] Smaller H2 in older ↔ new post navigation
    - [x] Make the footnotes a bit smaller
    - [x] Change the padding of ul li & ol li
- [x] Make the footer nicer
    - [x] Redesign static pages "o-autorovi" (*also change the url/permalink*), "o-blogu"
        - [x] Unify the yamls and clear the css lingo for the "columns.scss" so its not a hot mess (*kinda*)
- [x] Define more fallback fonts
- [x] Fix some things in the mobile version (*make the menu nav thumb friendly, resize some headers*)
- [x] Add a footer
    - [x] Maybe add some contacts like :mailto and stuff
        - [x] Obfuscate said :mailto with plugin "jekyll-email-protect" (*kudos to [@vwochnik](https://github.com/vwochnik/jekyll-email-protect)!*)
- [x] Add a fancy parallax for the post bg (*and fixed the menu scroll so it looks a bit nicer*)
- [x] Redesign the older ↔ new post navigation
- [x] Fix the disappearing menu on the index page (*what one element set to "position: absolute" can do, huh*)
- [x] Find out how to change the default "↩" icon of footnotes to something else, so I don't have to resort to CSS trickery
- [x] Write a script which adds a "↑" after headings, which acts as an anchor to the TOC element
- [x] Make the colors more accessible
- [x] Design a nicer TOC
- [x] Change design of the post index (*bg = background of the whole element; post info above; glass effect*)
- [x] Declutter the whole repo (*mainly /_layouts and /_includes*)
- [x] Share my theme toggle icons
- [x] Change the default theme toggle icon to a set of my own
- [x] Let ESC key cancel the lightbox
- [x] Add redirect to all posts and shorten the URLs
- [x] Moved all javascripts into a separate folder (*/assets/js/*)
- [x] Changed how a block of code/inline code looks
- [x] Decide if the gallery description uses "⁂" or "∴" as markers (*it’s the ⁂*)
- [x] Add description to the gallery items
- [x] Add a lightbox to the gallery
- [x] Create a working gallery css
- [x] Integrate a lazy load script
- [x] Streamline the css (*using css variables and mixin*)
- [x] Make the RSS work better (*tried to use Feedburner, but the generated xml from "[jekyll-feed](https://github.com/jekyll/jekyll-feed)" works just fine, for now*)
- [x] Update thumbnails (*I hope for the last time*) (*lol, as if*)
- [x] Main favicon is now an svg ([thanks to an article by Antoine B.](https://medium.com/swlh/are-you-using-svg-favicons-yet-a-guide-for-modern-browsers-836a6aace3df)); other favicons are hi-res; minimized the need for excesive amount of different icons
- [x] Make the 404 a bit nicer
- [x] Add yaml published boolean
- [x] Add & fix hover for backgrounds
- [x] Add post backgrounds
- [x] Rework the post header design
- [x] Rework page layout
- [x] Remove unused css & make it more readable
- [x] Add RSS feed
- [x] Add site language & timezone
- [x] Revise the file structure ("moved 404", "home", "o-blogu" and "o-mne" to "_pages"; moved "thumbs" and "bg" from "assets" to "images")
- [x] Add post thumbnails
- [x] Reformat articles (add footnotes, add TOC liquid tags, add images)
- [x] Create gallery css
- [x] Migrate all Medium posts here
- [x] Add progress bar for posts
- [x] Create new layouts for the website
- [x] Edit the main css file (typography, colors, responsivity)
- [x] Find a theme
- [x] Set up Github Pages and Jekyll