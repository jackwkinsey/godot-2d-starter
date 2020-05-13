# Godot 2D Pixel Art Starter Project

## 🤨 What is this?

Just like the project name says, this is a starter project for working in 2D with pixel art in the Godot Engine.

## 🤔 Why?

I was tired of always needing to set various project settings when creating a new, pixel art based, 2D project in the Godot engine. So I've set up this project with the common settings I need for working on 2D pixel art games. I thought maybe someone else might find it useful to have as a starting point if they work mostly in pixel art like us!

## 🎁 So what's in it?

Not a ton since it is a bare-bones starter project. It's meant to allow you to fire it up and get to work without mucking about with a bunch of project settings.

Here's is what I added:

- **Git Ignore file**: This is a dead simple ignore file that just adds common directories/files for Godot projects. It was created by [gitignore.io](https://www.gitignore.io).
- **A pixel art icon**: instead of the regular one, you'll see a 32x32 pixel art icon based on the Godot mascot. This will allow you to see that the pixels are sharp for your assets.
- **Default import settings**: I setup the texture import settings to default to *2D Pixel*. I think this should carry over if you download this repo since it is a project setting. If this doesn't work (i.e. you start importing your own pixel art and it looks blurry), you can change this in the *Import* tab of the editor (next to the *Scene* tab by default). Simply click on *Preset* -> *2D Pixel* and then the **Reimport** button. Then click on *Preset* -> *Set as Default for 'Texture'*.
- **Basic World scene**: this scene just displays the pixel art icon in the center of the screen. It is also located in the *Scenes* folder to hopefully encourage project organization. 😉
- **Project settings**: I changed quite a few project settings. Here they are:
  - **Application -> Run -> Main Scene**: set to the world scene created
  - **Display -> Window**
    - *Width*: 320
    - *Height*: 180
    - *Test Width*: 1280
    - *Test Height*: 720
  - **Display -> Stretch**
    - *Mode*: viewport
    - *Aspect*: keep
  - **Rendering -> Quality -> 2d**
    - *Use Pixel Snap*: true
  - **Input Map**: I set up some input mappings as well.
    - For the directional inputs (*ui_up*, *ui_down*, *ui_left*, & *ui_right*), I added the Left Joystick Axis so your gamepad's left stick works for directional input (not sure why this isn't set by default since the D-Pad is setup by default 🤷‍♀️).
    - I also mapped **Z** to *ui_accept*, **C** to *ui_select*, and **X** to *ui_cancel*. These are just personal preference mappings. Feel free to change these to suit your needs for your project!

**Resolution**: I set up the target resolution to be **320x180** because that is usually the resolution I aim for when working on pixel art based projects. I probably wouldn't push it much higher than this. Also, you can probably set the Test width and height to **1920x1080** if you're working on a 4K display.

## 👩‍💻 Contributing

If you have any settings that you like to have setup by default when working on pixel art games, let me know! I may be convinced to add it to this base project! 😉


🍻 Cheers & Happy Coding! 💖

## 🎯 Changelog

- **13 May 2020**: Updated the display stretch mode to `viewport` and turned on pixel snap per suggestion from Twitter discussion.
