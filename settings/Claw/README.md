# Claw

Best Version: CrazyHook - <https://captainclaw.net/en/downloads.html>

## FAQ - Files

All Files can be found on the iso of the game cd - `.FEZ` and `.REZ` are localized. So a **german** disc is required for german sfx and text.

### What is `.FEZ` ?

**Movie** files for claw

### What is `.REZ` ?

**Ressource** files for claw - contains sprite, animation and text.

### What is `.SF2` ?

**Midi** files for claw - used for background music in combination of a synthesizer e.g. qsynth on linux - not localized

## Music for Claw

<https://docs.google.com/document/d/18cRRIteJDQn-CBmRg6dTErAG0EIQwiTElpupEn6HLs4/edit?tab=t.0>

If you want music you need to use a synthesizer like QSynth. Extract the CLAW.SF2 File from the Iso and put it into the folder:

1. Install the flatpak version:

```sh
flatpak install qsynth
```

2.Run flatpak

```sh
flatpak run org.rncbc.qsynth
```

3.Add the Music

![setup](image.png)

4.Edit the settings so that it aligns to the screenshot
![screenshot](image-1.png)

5.Add the Soundfile

![soundfile](image-2.png)

6. Start the game - you should hear music in the levels

## How to get the Soundfile

The soundfile can be extracted from the claw cd image

the file is called `CLAW.SF2`
