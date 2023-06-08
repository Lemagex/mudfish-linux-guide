# Running mudfish in linux
A guide on how to set up and run mudfish on linux. Their website documentation is outdated.

## **Installation:**
To install Mudfish on Linux:
Download [here](https://mudfish.net/download)
take note of the version #.#.#

Open terminal
```
cd ~/Downloads
sudo chmod +x mudfish-#.#.#-linux-x86_64.sh
```
Note: You can usually skip chmod but for some reason my linux install had issues until I did this, and it doesn't hurt to include.
(Make sure to replace #.#.# with the version, for example, mudfish-5.7.3-linux-x86_64.sh )

```
sudo ./mudfish-#.#.#-linux-x86_64.sh
```
That's it, you're installed.

## **Usage:**
```
sudo /opt/mudfish/#.#.#/bin/mudrun 
```
replacing #.#.# with your version # to start the program.


If you've forgotten your version # at any time, run 
```
ls -l /opt/mudfish/
```
after installation and you should see numbered folders.

## **Configuration:**
While running, check your chosen Desktop Environment's tray area for a running icon (sometimes this glitches out and is blank, so look for a blank, red cross, missing symbol, etc) and it should provide you with the IP/Port to open mudfish config in your browser, for me it was 127.0.0.1:8383 
You can add the games or programs you wish to use by "Equipping them as items"
You can modify the connection methods by clicking "Manage Item" next to your program, I recommend changing Node > Advanced Mode and setting the first node to the closest to you, and the second to the one closest to the service you wish to use. For example, when playing FFXIV ( Final Fantasy XIV ) on a Japanese Data Centre from Australia, you would set the first one to Sydney and the second one to Tokyo.
