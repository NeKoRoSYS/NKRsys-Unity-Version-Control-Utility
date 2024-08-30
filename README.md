# NKRsys-Unity-Version-Control-Utility
This repository aims help with version control for Unity projects.

<br>

## Before You Use
The scripts are to be placed in an Editor folder (Assembly Definition) or otherwise it will not function.

<br>

## Usage
Normally, anyone would have to manually set their project's bundle version in the "Version" field provided by the Editor; however, importing the scripts will add a new field called "Base Version" in the Player Settings. One would now have to manually modify the "Base Version" instead of the "Version" field as the latter is now autogenerated according to the format in the `VersionIncrementer` class.

<br>

### Example
If you set `Base Version` to "1.0.2", `Version` or the actual app bundle version will now be automatically formatted to "1.0.2.MM.DD.YY.BUILDNUMBER" before the build process starts. *The format can be easily modified by tweaking the `VersionIncrementer` class.

<br>

## Why?
This repo simply aims to help developers who use git-based platforms for version control of their Unity project.

<br>

## Sponsorship
I am an aspiring software and game developer that currently do stuff solo, and I need funding to motivate me to do a lot better on my tasks so that I could deliver way better content. Donating is not a must, but it will be immensely cherished and appreciated!

<br>

## Contribution
Something's wrong with the code or you know better workarounds and alternatives? You can either make an issue or a pull request. It will be very much appreciated!
