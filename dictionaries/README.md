# CrossInk Dictionaries

Prepared [StarDict](https://en.wikipedia.org/wiki/StarDict) dictionaries for use with CrossInk. The initial collection contains a few English dictionaries that have been tested with CrossInk.

If the dictionary you need is not here, prepare it with [Inky's dictionary tools](https://inky.crossink.dev/#dictionary-tools).

## Downloading

Choose either option:

- Download an individual `.zip` file from the `English/` directory.
- Clone this repository to get every dictionary:

  ```bash
  git clone <repository-url>
  ```

After downloading a ZIP, extract it on your computer before copying the dictionary folder to the SD card.

## Installing on an SD card

1. Extract the dictionary ZIP on your computer.
2. Copy the extracted dictionary folder to one of these directories on the
   CrossInk SD card:
   - `/.dictionaries/` (checked first), or
   - `/dictionaries/`
3. Eject the SD card, insert it in the device, and open **Settings -> Dictionary** to choose the dictionary.

If only one dictionary is present and no dictionary has been selected before, CrossInk selects it automatically. Select **None** in **Settings -> Dictionary** to deselect the current dictionary.
