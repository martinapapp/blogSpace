# BlogSpace

![JS Badge](https://img.shields.io/badge/Learning-JavaScript-yellow)
![API Badge](https://img.shields.io/badge/API-Scrimba-blue)

This is a project I built to practice working with APIs. I learned how to get data from a server and how to send data back using a POST request.

## Index

- [About](#about)
- [Usage](#usage)
- [Development](#development)
- [Contrubution](#contribution)
- [License](#license)

---

## About
BlogSpace is a simple blog dashboard. The main goal was to learn how to:
* Use `fetch()` to get data from an external API.
* Use `method: "POST"` to send new data.
* Dynamically update the page using template literals and `.innerHTML`.

It's currently hooked up to the Scrimba JSONPlaceholder API to simulate a real backend.

## Usage

### Installation
Since this project uses **Vite**, you'll need to install the dependencies first:

1. Clone the repo.
2. Run `npm install` to get Vite set up.
3. Run `npm run dev` to start the local server.
4. Click the link in your terminal (usually http://localhost:5173) to see the blog!

### Commands
I'm using Vite to make development faster. Here are the main scripts I use:

`npm run dev` - Starts the project so I can see changes live.

`npm run build` - Prepares the project for the real world (deployment).

`npm run preview` - Lets me check the build version locally.

## Development

 ### Pre-Requisites: 
 - text editor
 - browser

### File Structure

| No | File Name | What it does |
| ---- | ---------- | ------------- |
|1|index.html|The main UI entry point.|
|2|index.css|Custom styles and layout.|
|3|index.js| The logic for fetching and rendering posts.|

### Build
I used a global array called postsArray to hold the data. When the page loads, I fetch the first 5 posts and then render them to the screen using a for...of loop. It’s a simple way to keep the UI in sync with the data I'm getting back.

## Contribution
1. Found a bug? Open an issue and I'll try to fix it.
2. Advice? If you know a better way to handle the POST request, I'd love to hear it!

### Guideline
I'm trying to keep this as "Vanilla" as possible—no frameworks allowed yet! I want to really understand the basics here.

## License
Feel free to use this for your own practice!  **MIT**  License.

