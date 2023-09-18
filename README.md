## Download the latest release
https://github.com/Tellervo89/yubico-icons/blob/master/releases/aegis-icons.zip

## How can I make icon pack build?

> **Note** \
> This section is only for more technical users that know how to use command line.

*Requirements: [Python version 3 (and up)](https://www.python.org/downloads/) installed.*

First, clone / fork the git repo or [download the repo as ZIP](https://github.com/aegis-icons/aegis-icons/archive/refs/heads/master.zip) (unzip the ZIP file, if you download it as ZIP).

In **Windows**: 
- Go to `/aegis-icons/_compress/` directory
- Open `.3_icon_pack_helper.bat` and press the corresponding number option in front of *"Make the icon pack ZIP"* text.
- After it's done, go back to `/aegis-icons/` directory, there should be icon pack build as `aegis-icons.zip`.

In **other systems**, open terminal in the `/aegis-icons/` directory and execute this command:

```
cd /yubico-icons
chmod +x /home/user/Downloads/yubico-icons/make-pack.py
./make-pack.py gen --output aegis-icons.zip --version YYYYMMDD
```
<sup><i>Replace the</i> <code>YYYYMMDD</code> <i>with version number you want.</i></sup>

After executing command, there should be icon pack build as `aegis-icons.zip`.
