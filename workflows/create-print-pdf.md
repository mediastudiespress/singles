# Create print PDF

#single #distribution #typesetting

- [ ] navigate to [Overleaf](https://www.overleaf.com/project)
- [ ] duplicate the main LaTeX file, and append "-print" to its name
- [ ] copy the text below into the document’s header, and follow instructions
- [ ] export the PDF and open in Acrobat, with the two page view enabled. Note any verso/recto issues, and then go back to Overleaf and insert or delete blank pages 
- [ ] open the file in Acrobat, but make sure in Properties that standard units have been changed to mm
- [ ] go to Print Production in the right-hand sidebar, then Preflight, then the tool icon
- [ ] open the edit for "Scale pages to specified size" to 177 229; make sure is “Scale pages” selected on next screen; save and re-open
- [ ] run “Scale pages to specified size” again, but this time edit and switch to “scale page content only”, selecting 90% and relative to “Center of page”
- [ ] save file as hyphenated-print-isbn-body.pdf to /pdfs/print-on-demand in Working Copy 

## To add to the header

% For print version
    %1. change document class \documentclass[twoside,symmetric,nobib,justified]
    %2. remove DOIs and comment out \hypersetup above      
    %3. Uncomment out the \geometry below
    %4. Go through the front matter; may need to use mix of, and movcing around, \begin{fullwidth} and \newgeometry \restoregeometry
    %5. Go through page by page, fixing footnotes, chapter titles, widows, etc.
    %6. If there are "Parts," make sure that they appear on the right hand side
    %7. If TOC is manual, check each start page
    %8. Export and look over, and shift back to the Create print PDF workflow

 \geometry{
  % showframe,
   paperwidth=8.5in,
   paperheight=11in,
   left=0.93in,
   right=0.6in,
   top=.62in,
    bottom=.62in,
    includemp,
   includehead,
  % The text width and height are calculated automatically.
 }