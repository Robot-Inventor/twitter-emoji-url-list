# Twitter Emoji URL List

[日本語](README_ja.md)

**!!IMPORTANT!!**

This repository is deprecated and will no longer be maintained. You can convert Twemoji URL to emoji by using simple script like [Robot-Inventor/spam-tweets-compressor](https://github.com/Robot-Inventor/spam-tweets-compressor/blob/39fb8e5cd58f3782148f6510f15e7d79cc80be6d/src/ts/main/emoji.ts).

----------

Twitter uses images to display emoji. While this mechanism gives Twitter a sophisticated look, it also makes it difficult to get emoji from browser extensions and other sources.

This repository is an unofficial mapping table of Twitter Emoji (Twemoji) and their image URLs. By checking the src attribute of the Twitter img element from browser extensions, etc., and comparing it to this table, you can easily find out what kind of emoji it is.

This repository is current as of August 23, 2021 (JST).

## Files in this Repository

| File                             | Content                                                                                                                                        |
| :------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------- |
| src/emoji.txt                    | This is a list of emojis, one emoji per line. No escaping. Also, some of them are duplicated.                                                  |
| src/url.txt                      | This is a list of URLs for emoji images, with one URL per line. Also, some of them are duplicated.                                             |
| dist/twitter-emoji-url-list.json | This is the main body of the correspondence table. This is a JSON file with the image URL as the key and the corresponding emoji as the value. |
