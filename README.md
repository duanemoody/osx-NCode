# osx-NCode
Simple Finder services to encode and unencode selected text files. 

If you have text files with have Japanese characters in them that appear like "ÉÇÉfÉãÇ≈Ç∑ÅB", it's because the file has no character encoding to tell OS X (and text editors) that they're Shift-JIS encoded. While it's possible to open the file, tell your text editor to reopen it using Shift-JIS and resave it / save it to another file, this destroys the original file creation/modification metadata (among others). Since this attribute isn't actually stored inside the file itself, but as metadata, these Finder services allow you to change the encoding without disrupting the file itself.

Bear in mind that transferring these files to a non-OS X file system or archiving them with 'clear Mac metadata' as an option will remove this attribute.
