## polyhaven-hdri-downloader
This script uses the [polyhaven API](https://github.com/Poly-Haven/Public-API) to download HDRI images by category, resolution and extention.
The images are stored in folders per resolution.

# Usage
Installing python requests module:
```bash
pip3 install requests
```
```bash
# refer to the polyhaven website for available resolutions, categories and extentions
python3 downloader.py <resolution> <category> <extention>
```
