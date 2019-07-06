# Smart Mirror
Smart mirror for Raspberry pi B model 1 inspired by HackerShackOffical project that can be found on https://github.com/HackerShackOfficial

## Setup

Clone repository
```
https://github.com/vilmarfonseca/smartmirror.git
```
```
cd smartmirror
```

Delete previously cache for Spotify API
```
sudo rm .cache-vilmarfonseca
```

### Install dependencies 
Get pip from https://pip.pypa.io/en/stable/installing/) and install dependencies

```
sudo pip install -r requirements.txt
```
```
sudo apt-get install python-imaging-tk
```

Install spotipy

```
git clone https://github.com/plamere/spotipy.git
```
```
cd spotipy
```
```
python setup.py install
```

You can also install it using pip
```
pip install spotipy
```

### Get Spotify API credentials
Go to https://developer.spotify.com/dashboard/ and create a new apllication

Set your Redirect URL to https://google.com/ on your application settings

Put your Client ID and Secret ID in the begining of smartimirror.py

Run the program
```
python smartmirror.py
```