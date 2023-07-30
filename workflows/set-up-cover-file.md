# Create ePub version

#single #publish #marketing

- [ ] Export the individual chapter ePubs on mediastudies.press
- [ ] If you do not have a Front Matter Pub, you will need to create a temporary one, based on [Liberty and the News](https://www.mediastudies.press/pub/mzxa3wgv/release/4). Erase the PDF links at top and bottom, and do not include Contents. Export as a ePub, and make sure it is included
- [ ] Upload one of the chapters to [this ePub validatior](https://www.ebookit.com/tools/bp/Bo/eBookIt/epub-validator). Copy and paste any issues below
- [ ] Navigate to Calibre on the Mac, and import chapters
- [ ] Export a jpg cover into /Shorcuts, and rename cover.jgp
- [ ] Highlight chapters, and select EpubMerge from the toolbar. Be sure to order the chapters in the popover
- [ ] In the metadata popover, upload cover.jpg
- [ ] Fill in the Title and Series (if applicable)
- [ ] In the Tags fields, add the BIC Subjects, without acronym codes, separated by commas
- [ ] In the Ids field, add eISBN as isbn:(no hyphens),doi:(no http), and add the Published date and Publisher
- [ ] In the Comments field, paste the long description, and save
- [ ] Select Edit Book in the toolbar; delete title_page.x html and any others like text/title_page.x html
- [ ] Select ch001.xhtml and other any others; in each case, delete the <img src=…> near the top. (This may not be there). Delete any extraneous files.
- [ ] Using the TOC on the top bar, eliminate any sub-headers and check the top-level chapter ones
- [ ] Go back to Calibre, select Convert Book from the toolbar. Under EPUB output on the left menu, change the EPUB to EPUB version 3
- [ ] Export as an ePub
- [ ] Test the ePub in Books and Kindle
- [ ] Rename the ePub file with the acronym and copy to Working Copy in /ebook/
- [ ] Create a “release” on Github, in the Singles repository. Use the example of previous releases, and attach the two files
- [ ] Change the PDF download and add the buttons for ePub on the landing page. Test the downloads.
- [ ] Navigate to Toth, and add a Publication under ePub, with the landing page url and the direct Github links entered; do the same with the PDF