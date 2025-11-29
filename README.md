# Julius' Beauty Parlor Website
A small, elegant static website for **Julius' Beauty Parlor**, featuring four primary pages: **Home**, **Services**, **About**, and **Contact**. Designed as a simple landing/portfolio website showcasing services, brand identity, and user-friendly navigation.
https://donjulio-code.github.io/juliusopioecou.github.io/
## Project Structure

```
.
├── index.html        # Home page
├── services.html     # Services listing page
├── about.html        # About / Team page
├── contact.html      # Contact form + map
│
├── styles/
│   └── style.css     # Main stylesheet
│
├── images/           # Logo, background images, sliders, etc.
│
└── audio/
    └── transition audio.wav   # Page-transition sound effect
```

## How to Open the Project Locally


Double-click any `.html` file (e.g., `index.html`) to load it in your browser.

## Background Images

Each page uses its own background class from `styles/style.css`:

* `.bg-index`
* `.bg-services`
* `.bg-about`
* `.bg-contact`

To change backgrounds, edit the relevant CSS rule and point it to an image inside the `images/` folder.

Main content uses a `.page-panel` wrapper to keep text readable. Adjust opacity in CSS as desired.

## Page Transition Sound

The transition sound file is located at:

```
audio/transition audio.wav
```

Navigation links trigger a small JavaScript function that plays this sound before switching pages.

If the audio does not play:

* Confirm the file path is correct
* Check browser autoplay policies
* Test using a local server via `http://localhost`

## Social Links

SVG icons in the footer contain placeholder `href="#"` attributes. Replace them with your real profile URLs to activate links.

## Favicon Setup

The site currently uses:

```
images/logo.png
```
