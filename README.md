# Twitter Emoji URL List

[日本語](README_ja.md)

Twitter uses images to display emoji. While this mechanism gives Twitter a sophisticated look, it also makes it difficult to get emoji from browser extensions and other sources.

This repository is an unofficial mapping table of Twitter Emoji (Twemoji) and their image URLs. By checking the src attribute of the Twitter img element from browser extensions, etc., and comparing it to this table, you can easily find out what kind of emoji it is.

This repository is current as of August 23, 2021 (JST).

## Files in this Repository

|File|Content|
|:--|:--|
|src/emoji.txt|This is a list of emojis, one emoji per line. No escaping. Also, some of them are duplicated.|
|src/url.txt|This is a list of URLs for emoji images, with one URL per line. Also, some of them are duplicated.|
|dist/twitter-emoji-url-list.json|This is the main body of the correspondence table. This is a JSON file with the image URL as the key and the corresponding emoji as the value.|
