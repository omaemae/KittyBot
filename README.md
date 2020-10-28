# Kitty Bot
These are the sources of Kitty Bot, a discontinued project of mine.

## Note
I will NOT be accepting pull requests, I'm no longer interested in maintaining the bot.

## Contributors
### Programmers
 - omame (me) - Main Programmer
 - KittyLe - Lead Programmer

### FFmpeg magicians
 - dengr1065 - made FFmpeg command line switches for `k.mutalaugh`

## How to set this up?
To run Kitty Bot, you need:
 - Python 3.8+ (or lower, idk)
 - pip
 - Chrome/Chromium (with chromedriver)
 - ImageMagick
 - possibly something else, i forgot (tell me in the Issues tab if i'm missing smth pls)

Install the dependencies:
```sh
$ pip3 install -r requirements.txt
```

Create `config.py` in the root directory with the following content:
```py
token = "YOUR_TOKEN_HERE"
prefix = "k."
shards = 1
```
You can change the prefix.

Now, run `main.py`:
```sh
$ python3 ./main.py
```

# Where is Flex's source code?
I still have to dig it out.

# Updates
Last updated: 2020-10-28

## 2020-10-28
Initial upload.