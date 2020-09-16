# ThreeFold NOW

Welcome to the ThreeFold NOW  Wiki.

If you have any input, would like to see additions, or a cool idea, feel free to list an issue [here](https://github.com/threefoldfoundation/info_internet9/issues), and we'll make sure to try and get it in there.

If you need any support please visit [our website](https://www.threefold.io) and use the chat widget in the bottom right of your screen. Our team will answer your questions as soon as possible.


- This wiki will be hosted on: now.threefold.me/io
- The main marketplace is hosted on marketplace.threefold.me/io


### to run locally (to update once new links are available)

- get tfweb from: https://github.com/threebotserver/publishingtools/blob/development/README.md
- download this repo, run: ```run.sh``` which is in root of this repo

### get the documents (content) using git

```bash
mkdir -p ~/code/github/info_threefold_now
cd ~/code/github/info_threefold_now
#git clone https://github.com/threefoldfoundation/info_threefold_now/ -b development
#if you have your ssh key for github and you edit use
git clone git@github.com:threefoldfoundation/info_threefold_now.git -b development
```

### run the server

```bash
cd ~/code/github/threefoldfoundation/info_threefold_now
#will open local browser
run.sh
```

### Editing the wikis

- all md files are under src/docs directory, please make sure you get all your changes there.
