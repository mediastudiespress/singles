# Scanned chapter PDF to PubPub

#chapter #publicdomain #ingestion


- [ ] Obtain the best-quality scan as possible
- [ ] Run OCR with either [Adobe Acrobat Pro](https://acrobat.adobe.com/us/en/acrobat.html) or [Abbyy FineReader](https://pdf.abbyy.com)
- [ ] Open up the OCRd PDF in Adobe Acrobat Pro
- [ ] From the File menu, select Export --> Rich Text. You will be prompted to save the new file. Note that the export can take a long time
- [ ] Begin the chapter-by-chapter ingestion process. From here on out, each step presumes that you have (1) copied out a single chapter's worth of text from the exported document; and (2) paste into a new saved document, named for the chapter. 
- [ ] The next step is to correct the text. This can be done either in Word/Pages or in a text editor (using Markdown formatting). Open up Word or a text editor side-by-side with the PDF. 
- [ ] Go paragraph by paragraph, correcting spelling and formatting errors--consulting the PDF as necessary. Delete page numbers and other page header/footer material; if OCR worked well, this can be sped up using find-and-replace.  You may find patterned errors (like double spaces) in the OCR that, likewise, can be fixed with with find-and-replace.
- [ ] Make sure that there aren't any hidden linebreaks in paragraphs by triple clicking each paragraph. 
- [ ] Keep an eye out for bold, italics, and underline, as well as capitalization and "small" capitalization. Do not worry about the typeface or fontsize of the body text. For headers, use the built-in Word styles for Header 1, Header 2, etc., or the Markdown equivalents. 
