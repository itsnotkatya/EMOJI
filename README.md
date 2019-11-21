# EMOJI

# According to the following chart:

|Numbers of byte|Bits for code point|First code point|Last code point|Byte 1|Byte 2|Byte 3|Byte 4
|--|--|--|--|--|--|--|--|
|1|7|U+0000|U+007F|0xxxxxxx| | | |
|2|11|U+0080|U+07FF|110xxxxx|10xxxxxx| | |
|3|16|U+0800|U+FFFF|1110xxxx|10xxxxxx|10xxxxxx| |
|4|21|U+10000|U+10FFFF|11110xxxx|10xxxxxx|10xxxxxx|10xxxxxx|
# Emojies can be represent as:
|Emoji|Unicode|Binary|Numbers of byte|
|--|--|--|--|
|😅|U+1F605|11110000:10011111:10011000:10000101|4|
|😊|U+1F60A|11110000:10011111:10011000:10001010|4|
|😝|U+1F61D|11110000:10011111:10011000:10011101|4|
|💖|U+1F498|11110000:10011111:10010010:10010110|4|
|😉|U+1F609|11110000:10011111:10011000:10001001|4|

#Resourses%
1. https://unicode.org/emoji/charts/full-emoji-list.html#1f975
1. https://ru.wikipedia.org/wiki/UTF-8
1. https://www.fileformat.info/info/emoji/list.htm



