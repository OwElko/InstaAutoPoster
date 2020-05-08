# InstaAutoPoster

Allows you to post photos regularly from a local folder

## How to run
Run the script
```
python start_posting.py
```

## Settings
- photos are stored in _pics_ folder ( set the folder in line 23 )
- name of the photo should look like "#-Caption-text.jpg"
-- # (number) determines posts ordering
-- "Caption-text" will be used to search for a description file in the same folder with the name "Caption-text.txt"
-- If the description file is not found "Caption-text" is what you will see under your photo in IG (eg. "Caption text")
-- Only _jpg_ files are processed
- list of posted photos stored in _posted.txt_ (in order not to post one photo several times)
- frequency of posting is determined by
```
timeout = 24*60*60 # 24 hours
```

___
