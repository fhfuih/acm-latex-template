# ACM LaTeX Template

This is the template for my ACM HCI-community submissions.

## Tips

The `anonymous` document class argument will automatically hide \author & \shortauthor.
There is no need to redefine them to dummy values.
- Inline secret infomation can be wrapped in \anon{Secret}. They will be masked when `anonymous`
- Larger secret portions can be wrapped in `\begin{anonsuppress}`
- The entire `ack`(nowledgment) section will also be hidden
- Other config can be wrapped in `\if@ACM@anonymous \else \fi`
- Refer to the acmart doc for more details

## Useful Links

- Submission general info & checklists:
  - https://www.acm.org/publications/authors/submissions
- ACM LaTeX best practices
  - https://www.acm.org/publications/taps/latex-best-practices
- ACM LaTeX package documentation (PDF)
  -  https://portalparts.acm.org/hippo/latex_templates/acmart.pdf
- List of approved LaTeX packages
  - https://www.acm.org/publications/taps/accepted-latex-packages
- Official Overleaf template
  - https://www.overleaf.com/gallery/tagged/acm-official#.WOuOk2e1taQ
- The ACM Publishing System (TAPS) best practices
  - https://www.acm.org/publications/taps/taps-best-practices