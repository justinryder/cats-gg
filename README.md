[![forthebadge](https://forthebadge.com/images/badges/contains-cat-gifs.svg)](https://forthebadge.com)
# cats-gg
[Cats.gg](https://cats.gg/) - Serving you sweet cat pics using intentionally bad code since 2018!

# Query Parameters
Settings can be configured using query parameters for viewing in other apps such as OBS.

Example usage:
https://cats.gg/?streamModeEnabled=true&displayMode=DISPLAY_MODE_GIFS&slideshowDelay=2

Options:
* `displayMode=<DISPLAY_MODE_GIFS|DISPLAY_MODE_PICTURES>`
    * Sets the display mode to show cat gifs (default) or cat pictures
    * E.G. `cats.gg?displayMode=DISPLAY_MODE_PICTURES`
* `slideshowDelay=<number>`
    * Sets the delay between images in seconds (default 2)
    * E.G. `cats.gg?slideshowDelay=5`
* `streamModeEnabled=true`
    * Enables stream mode, removing all UI elements besides the images
* `theme=dark`
   * Enables the dark theme
