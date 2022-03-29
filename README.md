# memo2html
A Python script to convert Samsung .memo (S-memo) files to HTML, and import the associated media

## How to use
1. Download the memo2html file, and set permission to run it as a program
2. Download all memos you want from an android device
3. Store them im a folder of their own (_folder-with-memos_)
4. Create an empty folder for memos converted to HTML
5. Run `./memo2html folder-with-memos folder-for-converted-memos`
6. You can now import from within Notable as Markdown, if you want to edit :-)

## NOTES:
- All media files go into a _folder-with-memos_/media subfolder, so they must have different filenames. This is normally the case with pictures.
- Emoji characters (stored by Android as "surrogate pairs") are processed to appear as standard UTF-8 single characters.

Please let me know if you find a bug. :-)
