### webp-converter
A bash script to convert your screenshot assets on Obsidian into .webp file to reduce the size of your vault. It doesn't concern you until you gradually have bigger and bigger assets that could eat your storage space.

This is life saver!

### WARNING
⚠️ Make a backup of your vault just in case. The script deletes your original .png files after converting them and updates all .md links to use .webp instead. It's been safe in my use case, but better be cautious. "ការពារប្រសើរជាងព្យាបាល".

What the script does:
- Converts all .png files in a folder to .webp 
- Deletes the original .png
- Rewrites all links in .md files from .png to .webp

### Usage 
```
git clone https://github.com/chmakorkrich/webp-converter
chmod +x webp_converter.sh
./webp_converter.sh
```

You’ll be prompted to enter:
- The path to your image folder
- The path to your Obsidian vault (where .md files are)

The less size, the more happy!
