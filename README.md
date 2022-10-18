Launch Darkly FlapPyBird
===============

![](https://raw.githubusercontent.com/ecointet/LDBird/master/ext/homepage.png)

A FUN PYTHON Flappy Bird Clone made using [python-pygame][pygame]

Setup (as tested on MacOS)
---------------------------

1. Install Python 3.x (recommended) 2.x from [here](https://www.python.org/download/releases/) (Or use your preffered package manager)

1. Install [pipenv]

1. _Optional_: Install PyGame 1.9.x from [here](http://www.pygame.org/download.shtml)

   On MacOS, pipenv will install PyGame, please check how to install on your Linux/Windows machines

1. Clone the repository:

   ```bash
   $ git clone https://github.com/ecointet/LDBird
   ```

   or download as zip and extract.
   
1. In the root directory, open **flappy.py**

	Line 13, add your own LAUNCH DARKLY API KEY
   ```
   APIKEY = "sdk-XXXX"
   ```
   
   In your Lauch Darkly Project, you need 3 Flags
   - key: **background** (true/false)
   - key: **bird-color** (yellow, red, blue)
   - key: **henri-mode** (true/false)
   

1. In the root directory run

   ```bash
   $ pipenv install
   $ pipenv run python flappy.py
   ```

1. Use <kbd>&uarr;</kbd> or <kbd>Space</kbd> key to play and <kbd>Esc</kbd> to close the game.


Demo
----------

![](https://raw.githubusercontent.com/ecointet/LDBird/master/ext/video.png)[https://drive.google.com/file/d/18logBRtY0vPch0M-xhBNxZIWpAPgeRqs/view?usp=sharing](https://drive.google.com/file/d/18logBRtY0vPch0M-xhBNxZIWpAPgeRqs/view?usp=sharing)



[pygame]: http://www.pygame.org
[pipenv]: https://pipenv.readthedocs.io/en/latest/
