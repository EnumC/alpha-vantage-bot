# AlphaVantage Bot

Collects data on intraday statistics and stores locally.

Developed by [Ben Cuan](https://github.com/dbqeo), [Alexey Kolechkin](https://github.com/kuxxe), and [Eric Qian](https://github.com/enumc)

## Running locally

You need your own AlphaVantage API key to use this bot! Create a file `key.txt` containing only your key in the root directory.

Data is saved in folders named after the date, i.e. `yyyy-mm-dd` within the parent folder `src/data`.

To run, simply `npm i` then `npm start`.

For development using nodemon, run `npm run develop`.