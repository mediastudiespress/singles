# Create ePub and Mobi versions

#single #publish

- [ ] Export the individual chapter ePubs on mediastudies.press
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
- [ ] Select ch001.xhtml and other any others; in each case, delete the <img src=…> near the top. Delete any extraneous files.
- [ ] Go back to Calibre, select Convert Book from the toolbar. Under EPUB output on the left menu, change the EPUB to EPUB version 3
- [ ] Export as an ePub
- [ ] Test the ePub in Books
- [ ] Rename the ePub file with the acronym and copy to Working Copy in /ebook/
- [ ] Back in Calibre, Convert as a Mobi file, selecting under the "MOBI output" the option "Do not add TOC to book"
- [ ] Test in Kindle
- [ ] Rename the Mobi file with the acronym and copy to Working Copy in /ebook/
- [ ] Add the ePub and Mobi to the landing page
- [ ] Create a "release" on Github, in the Singles repository. Use the example of previous releases, and attach the three files
- [ ] Change the PDF download and add the buttons for ePub and Mobi on the landing page. Test the downloads.