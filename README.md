# Slitscan-Type #
=============

Illustrator scripts to generate type

For more info & results: [Slitscan Type Generator](http://jk-keller.com/slitscan-type-generator/)

And feel free to send me results/issues!

* * * *

### If you'd like to try this on your computer: ###

**Pre-requisites:**

- Adobe Illustrator (this version only tested on CS6)
- Some patience (amount depends on size of font collection)
- Acceptance that this may produce an error and not work for you the first time

**How to use the Slitscan type generator (as verbosely as I can think):**

1. Download & extract the archive. Archive contains: Read me, a javascript file (.jsx), two AppleScript files (.scpt & .applescript) and an actions file (.aia).
2. Open Illustrator
3. Open the `Actions` palette
4. In the `Actions` palette, open the dropdown menu and select `Load Actions...`.
5. Navigate to the actions file titled `Slitscan_Type.aia` and select it. You should now have an action set titled `Slitscan` with an action titled `ssIntersect`.
6. Go to the `File` Menu and choose `Scripts` >> `Other Scripts...`
7. Navigate to the javascript file titled `Slitscan_Type.jsx` and select it.
8. **Wait...**
9. When an alert pops up telling you how many fonts Illustrator thinks you have, click `OK`
10. There will be two files that remain open in Illustrator; Go to the `View` menu and select `Preview` for both documents.
11. Go to the `File` Menu and choose `Scripts` >> `Other Scripts...`
12. Navigate to the AppleScript file titled `Slitscan_Type.scpt` and select it.
13. **Wait...**
14. There may be a few letters that do not get sliced because the pathfinder tool produced "no results". These should OK to delete.
15. Save the files. Always save your files. The default location these files were saved in is your home folder
