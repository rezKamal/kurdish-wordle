# Kurdish Wordle

All code here is adapted from [this](url) open-source Wordle clone.

The list of accepted words consists of all 5-letter words which were used more than once in the Sorani Kurdish Wikipedia. The list of accepted solutions is hand-picked.

If you want to contribute, you could add functionality so that users can input answers directly from the keyboard, instead of by clicking on buttons.

_To Run Locally:_
Clone the repository and perform the following command line actions:

```bash
$ cd wordle
$ npm install
$ npm run start
```

_To build/run docker container:_

```bash
$ docker build -t notwordle .
$ docker run -d -p 3000:3000 notwordle
```

open http://localhost:3000 in browser.
