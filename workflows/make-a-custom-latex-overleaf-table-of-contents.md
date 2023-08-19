# Make a custom LaTeX Overleaf table of contents

#single #typesetting #publish

- [ ] navigate to Thoth and copy the plain text Table of Contents into a Draft
- [ ] copy the LaTeX below and paste into another Draft, and set them side by side
- [ ] copy and paste in chapter and part titles, being sure to LaTeX quotation marks and italics
- [ ] paste into Overleaf, and make sure it is on the right side
- [ ] after going through the full manuscript to fix any errors, add in the page numbers carefully

***

\newpage
\thispagestyle{empty}

\begin{fullwidth}


\vspace*{.1in}

% CONTENTS WORD

{\noindent\fontsize{32}{24}\selectfont\textit{Contents}\par}

% SPACE AFTER CONTENTS

\vspace{.75in}

% INITIAL CHAPTER

\setlength{\parindent}{25pt}
{\fontsize{14}{12}\selectfont{<<chapter>>\hfill ix\par}

% SPACE BETWEEN CHAPTERS

\vspace{.25in}

{\fontsize{14}{12}\selectfont{<<chapter>>\hfill 5\par}

% SPACE BEFORE PART

\vspace{.5in}

% PART

{\noindent\fontsize{20}{24}\selectfont\textit{<<part>>}\par}

% SPACE AFTER PART

\vspace{.25in}

{\fontsize{14}{12}\selectfont{<<chapter>>}\hfill 13\par}

\vspace{.25in}

\end{fullwidth}
