# BookMyShow-Movie-Rating-Interest-Tool
A lightweight Node.js web tool that uses Puppeteer to instantly fetch movie ratings and interest counts from BookMyShow.

Built using **Express.js** for the server and **Puppeteer** for headless browser scraping.

## ✨ Features

- 🔍 **Google Search Integration:** Searches Google specifically for BookMyshow links to ensure accurate results.
- ⭐ **Rating Scraper:** Fetches the movie's rating out of 10 along with the total vote count.
- ❤️ **Interest Tracker:** Fetches the number of people interested in the movie on BookMyShow.
- 🚀 **Optimized Scraping:** Blocks images, stylesheets, and fonts during the Puppeteer session to make scraping lightning fast.
- 🛡️ **Anti-Bot Evasion:** Uses custom User-Agents and hides the `webdriver` property to prevent basic bot detection.
- 🎨 **Clean Web UI:** Simple, responsive interface to search and view results instantly.

## 🛠️ Tech Stack

- **Backend:** Node.js, Express.js
- **Web Scraping:** Puppeteer (Headless Chrome)
- **Frontend:** HTML5, CSS3 (Inline)

## 🚀 Getting Started

### Prerequisites
Make sure you have [Node.js](https://nodejs.org/) installed on your machine.

