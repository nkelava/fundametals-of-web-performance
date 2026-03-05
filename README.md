# Fundamentals of Web Performance Workshop

Example Online store **Developer Stickers Online** for the Fundamentals of Web Performance Workshop.

## Getting Started

This is a webserver built on NodeJS and Express that servers plain HTML, CSS, JavaScript and Images. You need to have **Node ~20.0** to run this project.

1. Install Dependencies `npm install`
2. Launch the Dev Server `npm start`
3. Open the website at <http://localhost:3000/>

For demonstration purposes, the website is also hosted:

- In Amsterdam at <http://eu.devstickers.shop:3000/>
- In Amsterdam with HTTP/3 at <https://eu.devstickers.shop/>
- Global CDN at <https://www.devstickers.shop/>

### Instructor Setup

To do deploys, you need to create the `.env` file from the `.env.template`. You'll also need to enable execute on the script, `chmod +x ./tools/deploy.sh`
