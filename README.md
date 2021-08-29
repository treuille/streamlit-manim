# streamlit-manim
Seeing if I can put together an interactive version of 3b1b's Manim in Streamlit

# Installation

1. I had to install pango with

```sh
sudo apt-get install -y libpango-1.0-0
```

Actually maybe this is what worked:

```sh
sudo apt install libpango1.0-dev pkg-config python3-dev
```

I got this [from here](https://github.com/ManimCommunity/ManimPango#linuxmacos).

### [Next Attempt](https://github.com/openai/gym/issues/366#issuecomment-251731689)

**Didn't work.**

```sh
sudo apt install xorg-dev libglu1-mesa libgl1-mesa-dev xvfb libxinerama1 libxcursor1
```
