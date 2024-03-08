# MacOS-Dropover-Reverse-Image-Search
This project functions as a "Reverse Image Searcher" to work with the macOS app Dropover by [Damir Tursunovic](https://damir.me/).

You can add it as [Custom Script](https://dropoverapp.com/kb/application-scripts) to Dropover.

## What does it do?
1. It takes the file path of the inputted image.
2. The image is then uploaded to [tmpfiles](https://tmpfiles.org) to generate a temporary url.
3. This temporary url is used to search for the image with Google Lens.
4. Then the results are displayed in a Safari tab.
