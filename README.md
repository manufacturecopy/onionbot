# The Onion Bot
A cool wasteof.money bot built with Node.js that posts articles from The Onion (a well-regarded, world-renowned reputable news site) on wasteof every day.

## How it works
Basically, once per day, the bot visits The Onion's website (https://theonion.com/latest) and scrapes details about the most recent article (the headline, preview, article link, and post date), creates a nice-looking, well-formatted image (similar to the example below), and posts it to wasteof.money along with the link to the article.!![1699025950279](https://github.com/imadeanaccount1/onionbot/assets/138229538/8a3c188d-57bb-40ac-a66a-56eb478f02b3)


Each day's image is also committed to this repository under the [`images`](/images) folder.

## What does it use
The bot uses Puppeteer, a Chromium-based Node.js library popular for web scraping, to scrape data about The Oniona articles, filters out articles containing profanity using the `bad-words` module, and generates an image using the Puppeteer-based module, `node-html-to-image`.

## License
I created the bot in a couple of hours and wanted to open-source it so that other people could use the code/structure to make other things, such as bots for other news/blog/etc. website, so I licensed it under the MIT license to give as much freedom as possible. :)


