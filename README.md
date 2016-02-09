# osx-NCode
Simple Finder services to encode and unencode selected text files. 

If you have text files with have Japanese characters in them that appear like "ÉÇÉfÉãÇ≈Ç∑ÅB" instead of "モデルです", it's because the file has no character encoding to tell OS X (and text editors) that it's Shift-JIS encoded. While it's possible to open the file, tell your text editor to reopen it using Shift-JIS and resave it / save it to another file, this destroys the original file metadata. Since the encoding attribute isn't actually stored inside the file itself, but as metadata, these Finder services allow you to change the encoding without disrupting the file itself.

Because it's OS X (HFS+) metadata, it will be lost when archived if you have Mac metadata disabled (e.g. .DS_Store files).

Grab a usable copy from [Releases](../../releases).
