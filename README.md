# variety bible text

To be used for displaying random verses on the desktop of linux computer that supports the variety application

## How to use (Ubuntu)
Install variety from the terminal 

```bash
sudo add-apt-repository ppa:peterlevi/ppa
sudo apt-get update
sudo apt-get install variety
```

Setting variety
```bash
mkdir ~/.config/variety/pluginconfig/quotes
cd ~/.config/variety/pluginconfig/quotes
git clone <this_repo>
cp variety-bible-text/bibles/* .
rm -rf variety-bible-text
```

Reopen variety and go to the `effects` tab and check the `show random wise quotes on the desktop` check box

![Effects tab](./images/effect.png)
