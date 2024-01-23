## Download the latest release
https://github.com/Tellervo89/yubico-icons/blob/master/releases/yubico-icons.zip

## How can I make icon pack build?

> **Note** \
> This section is only for more technical users that know how to use command line.

*Requirements: [Python version 3 (and up)](https://www.python.org/downloads/) installed.*

```
git clone https://github.com/Tellervo89/yubico-icons
cd ~/yubico-icons
chmod +x /home/user/yubico-icons/make-pack.py
./make-pack.py gen --output yubico-icons.zip --version YYYYMMDD
```
<sup><i>Replace the</i> <code>YYYYMMDD</code> <i>with version number you want.</i></sup>

After executing command, there should be icon pack build as `aegis-icons.zip`.
