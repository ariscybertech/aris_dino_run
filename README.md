# Dino Run

A 2D infinite side scroller made using [Flame](https://flame-engine.org/) engine.

## Demo
 
![Menu](branding/menu.gif)

![Jump](branding/jump.gif)

![Hit](branding/hit.gif)

## Build steps

```bash
# Clone this project
$ git clone https://github.com/ufrshubham/dino_run

# Access
$ cd dino_run

# Install dependencies
$ flutter pub get

# Run the project (Make sure that a virtual or physical device is connected first)
$ flutter run

# The will start the game on any connected device.
```

## Supported platforms

- Android
- iOS
- Windows (without audio)

## Why the code is so different than the YouTube series?

Everything went great and in about 7 weeks I wrapped up the series (actual game completed way sooner than the series). The original game and the YouTube series was made using version 0.28 of Flame (probably latest at that time). But little did I know that Flame was under massive development preparing for the 1.0 release.

I suspected that my videos were going to get outdated pretty soon with newer versions of Flame. My plan to deal with this was to keep updating this repository with latest changes from Flame, so that new viewers of the series don't get stuck with a code that won't even build. But things got much worst after Flutter went null-safe. I tried migrating this project to null-safety and latest version of Flame multiple times. But I always ended up introducing a lot of bugs in the game.

It was not like this is a very big project and a lot of people are follow it. I was easier to leave this repository in a broken state. But personally, I've been through the frustration of trying to learn something new, spending hours and hours watching some tutorial series only to find out at the end that it is completely outdated. Remaking the whole YouTube series is a big undertaking (which I am not prepared for). But rewriting this game again wasn't that big of a deal. So finally I decided to rewrite the whole thing from scratch (almost), keeping the original code on a separate branch. Surprising it took me only few hours to get it up and running.

## Games inspired from Dino Run

This list might not contain all the project that are inspired from Dino Run, but these are the ones that I know of. If you want to add your game here or know of a game that should be featured here, feel free to open a pull request or send me the required details.

