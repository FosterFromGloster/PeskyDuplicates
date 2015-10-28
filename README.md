Duplicate Erasor

##Libraries used and acknowledgements

I used a couple of fantastic libraries that do some super cool stuff.
[Echo Nest Api] I used to look up information about an audio file missing its meta info.
Here is a link to its page: [releases](https://github.com/echonest/pyechonest/releases)
I've included it in the project file but you do need to include a developer API key that you can get
here: [developer.echonest.com](http://developer.echonest.com).
All credit to Echo Nest and their glorious API. Their license is in the root of this project

The other library used is EyeD3. They have some code that accesses the meta data information
for a large range of audio files. Super usefull stuff.
Here is their page [EyeD3] http://eyed3.nicfit.net/
Again I've included all the neccessary files in this repo but
all credit to the team at EyeD3.

Follow setup for further instructions.

##Setup

* **Get an API key** - to use the Echo Nest API you need an Echo Nest API key.  You can get one for free at [developer.echonest.com](http://developer.echonest.com).
* **Set the API** key - change ECHO_NEST_API_KEY variable in "EraseDuplicates.py"
```python
    from pyechonest import config
    config.ECHO_NEST_API_KEY="YOUR API KEY"
```

* **Call Setups**

Run python setup.py INSTALL on the root directory
and under echonest-codegen/pyechnest

* **Try it out!**

Run "EraseDuplicates.py" in the root directory with your music you want to erase duplicates for in the "Music" Folder


Note: With the nature comes the disclaimer that I'm not responsible for the loss or damage of any data that may incur with 
the use of this program.

-![alt text](http://i.imgur.com/AwZaBCr.gif "Cat")
