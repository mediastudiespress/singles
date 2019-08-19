# Workflow for Public Domain Works

1. Create a watermark according to this template:

> Excerpts from Chapter XII ("The Self") appear as William James. "The Self (1892)." In *Social Media & the Self: An Open Access Reader* 1.0, edited by Jefferson Pooley. Bethlehem, PA: mediastudies.press, 2019. https://doi.org/10.21428/3f8575cb.2a4b8bf4

>Credit for scan: Internet Archive, contributor: Emmanuel - University of Toronto, 2006 upload, https://archive.org/details/psychologybriefe00willuoft

>This watermark and the highlights can be removed using standard PDF tools.

2. Take a screenshot of cover, if a full book, and add to the Front Matter

* Title the jpg lastname-year-title-page.jpg
* Use centered logo

3. Every excerpt, add something like this: Excerpt from James Rorty. Our Master’s Voice: Advertising. New York: John Day Company, 1934: v–viii.

4. Save each excerpt into Github folder

5. Create a header/preview 1200px to 800px for each chapter: rorty-1200-800

6. Create a title page image: rorty-front



# Adding a new chapter

* Create a new pub in PubPub with the name of the chapter
    * Add the preview image (1200x800) and select for Header too
    * In attribution, replace your name with author's name, and select "List on byline"
    * In Collections, add to relevant collection and place in order; also make sure order is correct on page
* Add PDF to Transmit /masters-voice/
    * Normally, include cover page and TOC
    * Save to /pdfs
    * Add to transmit
* Copy the text in Drafts into a new Draft
* Markdownify it (with footnotes in separate draft)
    * combine lines
    * check for italics and em-dashes
    * search and replace "-  "
    * search and replace "  "
    * shift to iA Writer and do smart quotes
    * export as Markdown
* Import to PubPub
    * add any footnotes
    * read over for errors
    * add in superscript italics "First chapter of ..." [in Chicago] + "PDF | ORIGINAL PDF" at top and bottom
        * scheme: https://mediastudies.press/masters-voice/5-rorty-1934-chapter-one-msp.pdf | replace msp with original
    * add horizontal lines to break up sections
    * add footnote list at the bottom
    * merge into public and mint a DOI
* Download the Markdown and LaTeX versions from the Mac; md to /markdown and LaTeX can stay
* Open LaTeX in Kodex
    * remove the italicized header and footer
    * remove other extraneous latex
    * add \marginnote{\href{https://doi.org/10.21428/3f8575cb.6124a94d}{doi} | \href{https://mediastudies.press/masters-voice/1-rorty-1934-front-matter-original.pdf}{original pdf}}
  
* Copy and paste into Overleaf
* Check against pdf
* Export pdf
    * Save to working copy as rorty-1934-our-masters-voice-msp.pdf
    * Upload with transmit
    * Using PDF Viewer, select just the relevant parts (title + info page)
    * Uplod with transmit
    * Upload as featured download
    

    
    
    
    