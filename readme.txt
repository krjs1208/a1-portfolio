Readme for Kexin Chen - IN4MATX 133 A1
Email: kexinc22@uci.edu

Starter repository: https://github.com/uci-inf-133/a1-portfolio
Student fork: https://github.com/krjs1208/a1-portfolio
Reviewed starter revision: 018a712023a2ce4755bf1ad41b2a60aea93c4c15
This README follows the starter's seven numbered items.

1. Assignment points completed
==============================
Provisional self-assessment: 10/10. No bonus point is claimed.
README: 1/1; basic HTML: 2/2; basic CSS: 1/1; advanced features: 1/1;
responsive implementation: 2/2; three validation checks: 1/1;
embracing the spirit of the assignment: 2/2 (subject to the grader's judgment).
The responsiveness score reflects the implemented layouts and static layout
review, not a completed Chrome device-emulation test. A final Chrome review
on the student's computer is recommended before submission.

2. Features included
====================
(a) Basic HTML content
- Three local project-cover images with descriptive alt attributes.
- A single h1, section h2 headings, project h3 headings, and brief h4 headings.
- Meaningful paragraphs describing the portfolio and its three projects.
- An external link to https://www.informatics.uci.edu/.
- Semantic header, nav, main, section, article, aside, figure, figcaption,
  details, summary, and footer elements.
- Real ul/ol lists, descriptive navigation links, and a keyboard skip link.
This is one portfolio page; additional pages are not required for the rubric.

(b) Basic CSS styling
- Padding, margins, readable line heights, and constrained line lengths.
- An original warm off-white, forest green, and muted project-cover palette.
- Serif heading and sans-serif body font stacks, each with system fallbacks.
  No custom downloadable font or Bootstrap is claimed.
- Hover and visible keyboard-focus styling; distinct spacing and type sizes.

(c) Advanced features
- A responsive navigation bar and a two-column introduction with an aside.
- A featured project and a wrapping project layout using Grid/Flexbox.
- An accessible two-column data table with multiple rows, a caption, thead,
  tbody, scope, and explicit id/headers associations for row/column headers.
- Descendant, direct-child, and adjacent-sibling selectors, such as
  .tags > li, .about-copy p + p, and .details-content p + h4.
- Three native details/summary controls for expanding project briefs.
  These are supplementary to the required advanced features.

Responsive layout details
- A fluid container has a maximum desktop width of 1120px.
- At 1000px and below, type and spacing become smaller.
- At 760px and below, the introduction, featured project, and About section
  use one column; the project cards also become full-width.
- At 430px and below, the navigation and calls to action wrap naturally.
- Images use max-width: 100% and height: auto; table text wraps in two columns.
- Font sizes predominantly use rem and preserve browser text-size controls.
- Reading order and all project content are preserved on small screens.
- Reduced-motion preferences disable animated anchor scrolling.
- Print styles provide a readable, simplified layout.
Static renders were inspected at 1440px, 768px, and 390px. Text overflow was
checked in the static renderer. This renderer is not Google Chrome and does
not reproduce every browser layout or native details behavior. Chrome device
emulation, keyboard interaction, and 200% zoom should receive a final review.

3. Accessibility warnings and errors
====================================
No known or likely errors were ignored. The initial AChecker table warning
was resolved by adding explicit header associations. Image alt text was
also shortened. The remaining 61 items are potential/manual-review prompts.

Their rationale, grouped by topic:
1. Images (checks 178, 16, 8, 14, 251, 11): covers illustrate each project's
   subject, so concise descriptive alt text is appropriate. They are not
   interactive controls, charts, or unique instructions. The essential
   project information is in nearby HTML text, not available only inside
   an image. Generic cover labels are illustrative copy. Color is not the
   sole means of conveying a decision or status. Separate long descriptions
   are unnecessary for these simple illustrations.
2. Direction and language (checks 271, 270, 110): portfolio prose is English
   and html declares lang="en". There are no right-to-left passages or other
   language paragraphs requiring direction marks or language overrides.
3. Lists and sensory descriptions (checks 248, 250): navigation, topics,
   and the design lens use semantic lists. Instructions do not depend on
   identifying only a color, shape, or position.
4. Table prompts (checks 242, 111, 231, 230, 137): the table maps interests
   to questions and is not used for page layout. Its caption describes this
   purpose, its row/column headers are linked explicitly, and thead/tbody
   identify groups. There are no column groups or totals needing colgroup
   or tfoot. An obsolete HTML table summary attribute was not added.
5. Navigation and titles (checks 28, 262, 54, 19, 184): a skip link precedes
   the navigation, nav has an accessible label, the title identifies the
   person and portfolio, and links describe their destinations. A separate
   site map is unnecessary for a single page with section-anchor navigation.
6. Headings (checks 42-45): heading levels mark the introduction, sections,
   individual projects, and subsections rather than serving as generic
   visual formatting containers.
7. Consistency and quotations (checks 276, 131): a single navigation bar
   maintains its order at all breakpoints. There are no long quotations
   requiring blockquote markup.

Foreground/background combinations used for the ordinary HTML body text
were calculated against a minimum 4.5:1 contrast ratio and passed. Decorative
arrows and the monogram are hidden from assistive technology where redundant.
Native links and disclosure controls remain keyboard-operable by design;
visible focus outlines are provided. A manual screen-reader and keyboard
session was not performed during this assisted preparation.

Validation evidence
Only index.html is a portfolio page, so there is one screenshot per category:
- valid-html-index.jpg: live W3C Nu Html Checker result. No errors or warnings.
- valid-css-index.jpg: live W3C CSS Validation Service result for styles.css.
  CSS level 3 + SVG; congratulations/no errors found.
- valid-accessibility-index.jpg: live AChecker result against WCAG 2.0 AA.
  Known Problems: 0; Likely Problems: 0; Potential Problems: 61.
The JPG files are actual browser screenshots, not recreated result cards.
Raw service responses and the analyzed input are retained in validation/.
The .txt reports contain response source and are not additional portfolio pages.
For AChecker's markup mode, the external stylesheet was embedded unchanged
in a checker-only copy. The actual portfolio still uses external styles.css.
This allows the checker to read the CSS without needing a public site URL.
Results identify problems that automated tools can detect; they are not a
claim that every aspect of accessibility has been manually certified.

4. Time spent, in hours
======================
Approximately 1.75 hours for the initial AI-assisted preparation, starter
review, implementation, and validation. This estimate excludes the later
account-connection and unsuccessful fork attempt, and the student's
subsequent personal review or editing. Add personal time if applicable.

5. Online resources and generative AI use
========================================
- https://validator.w3.org/nu/
- https://jigsaw.w3.org/css-validator/
- https://jigsaw.w3.org/css-validator/api.html
- https://github.com/validator/validator/wiki/Service-%C2%BB-HTTP-interface
- https://achecks.org/achecker/
- https://www.w3.org/WAI/tutorials/page-structure/
- https://wave.webaim.org/extension/
Course materials supplied for this preparation:
- W1_L2_Sep29.pdf: HTML structure, semantics, accessibility, and selectors.
- W2_L2_Oct1_CSS.pdf: external CSS, box model, fonts, and advanced selectors.
No online portfolio template, framework, stock photograph, or icon library
was copied. The SVG covers and favicon were authored for this portfolio.
- https://github.com/uci-inf-133/a1-portfolio
  Consulted its index.html and seven-item readme.txt starter directly.

Generative AI queries and assistance:
- The student supplied the assignment and two lecture PDFs, and asked:
  "ok啊你现在把这个作业写一下，需要我提供什么尽管说".
- ChatGPT/Codex used that request to produce an initial responsive portfolio
  with HTML/CSS, project copy, original SVG concept covers, navigation,
  a header-associated data table, and native disclosure controls.
- ChatGPT/Codex checked local paths and source structure, calculated text
  contrast, submitted code to the validation services, collected their
  genuine browser screenshots, and drafted warning rationales.
- After the student supplied the starter URL, ChatGPT/Codex compared its two
  files with this implementation and reorganized this README accordingly.
- ChatGPT/Codex generated and edited draft code directly. No separate IDE
  AI code-completion extension was used in this preparation session.

6. Classmates or other people consulted
======================================
No classmates or other individuals were identified in this preparation
session. Add anyone consulted outside this session if applicable.
ChatGPT/Codex assisted with layout, draft copy, HTML/CSS/SVG authoring,
validation, and packaging. The student should review and understand the code.

7. Running the code and other notes
==================================
Extract the entire ZIP and open index.html in a web browser. Keep styles.css
and images/ alongside it. There is no build step, package installation,
JavaScript dependency, CDN, or font download. All local file references use
relative paths. The only external page link is the UCI Informatics website.

Repository setup
- The supplied starter contains only index.html and readme.txt. These root
  filenames are preserved; styles.css, images/, and validation evidence
  are added for this portfolio.
- The starter's placeholder page is replaced by the portfolio implementation.
  Its README questionnaire is answered above.
- The student fork is https://github.com/krjs1208/a1-portfolio, with master
  as its default branch. GitHub confirms its parent is the course starter.
  The portfolio files and validation evidence are included in that fork.

Content and authorship
- This is a newly prepared, AI-assisted portfolio draft for this assignment.
  It is not a reused earlier website or a copied online portfolio template.
- Project covers are original concept illustrations labeled as such, not
  screenshots of completed products or evidence of measured outcomes.
- Project copy is based on the supplied project context. It does not assert
  invented results, user counts, or individual team contributions.
- The student confirmed kexinc22@uci.edu for the assignment README.
  A resume and additional profile links were not supplied.
- The website does not need to be published to meet the stated assignment.
- Extra personal time, consultations outside this session, and the final
  Chrome review remain for the student to confirm before submission.
