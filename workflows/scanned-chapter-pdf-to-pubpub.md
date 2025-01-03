# Scanned chapter PDF to PubPub

#chapter #publicdomain #ingestion

- [ ] Obtain the best-quality scan as possible
- [ ] Run OCR with either [Adobe Acrobat Pro](https://acrobat.adobe.com/us/en/acrobat.html) or [Abbyy FineReader](https://pdf.abbyy.com)
- [ ] Open up the OCRd PDF in Adobe Acrobat Pro. Or run the [Extract text PDF Shortcut](https://www.icloud.com/shortcuts/7d29852c83c740079fbb02df350c6d34)
- [ ] From the File menu, select Export --> Text (plain). You will be prompted to save the new file. Note that the export can take a long time
- [ ] The next step is to correct the text. This is easiest to do in Drafts  for iOS or macOS (using Markdown formatting). You can open the text alongside the PDF.
- [ ] Remove any front matter or material from previous chapters: You are just correcting the text for the one chapter
- [ ] Paragraphs are typically broken up, so a first helpful task is to re-combine paragraphs, with the PDF as a guide. The Drafts 'Combine lines' Action is helpful here. Page numbers and any page headers have to be removed, and a full line space should be between each paragraph. 
- [ ] It is a good idea to put in footnote/endnote placeholders, using Markdown syntax—assuming that there are only a handful. (e.g, [^1]). Depending on where the notes actually appear, it is a good idea to format those too (e.g., [^1]: note…)
- [ ] Headers can be set off with an h3 (### ) 
- [ ] Block quotes with the Markdown for block quotes (> )
- [ ] Next, it's best to go back through, paragraph by paragraph, adding any italics (*) or bold (**), using the PDF as guide
- [ ] Next, go paragraph by paragraph, correcting spelling and formatting errors--consulting the PDF as necessary. Delete page numbers and other page header/footer material; if OCR worked well, this can be sped up using find-and-replace.  You may find patterned errors (like double spaces) in the OCR that, likewise, can be fixed with with find-and-replace. 
- [ ] em-dashes are particularly badly OCR'd. sometimes they are eliminated altogether, so need to be added back in.
- [ ] copy and paste the text into a Pages or Word doc, to use the spell check to catch other issues
- [ ] save the text into a text file, with the .md extension
- [ ] Navigate to the Collection on [mediastudies.press Dashboard](https://www.mediastudies.press/dash/overview)
- [ ] Select the Create Pub button in the upper right
- [ ] Using the Import Files button, navigate to the text file, select, and upload
- [ ] Add the author and fix the title
- [ ] There is no need to save or publish; drafts are are saved
- [ ] Add the chapter to Process and move the Kanban to Manager edit