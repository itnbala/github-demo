# Arc Design Systems
---------
Arc Design system defines visual guidelines for other properties to consume. The pages that will be created on .com properties will be following the style guide from the design systems.


# Scope of the document:
---------
Creating new pages through A/B testing for the designs supplied which is inline with style guide in Arc Design Systems. The styles specific to buttons, headings, paragraphs, grids with pre-defined classes are pulled only for the A/B testing.


# How the files are imported to A/B testing?
---------
Currently, it's a manual import. Extracted the files from Arc Design Systems common folder and merged the common files into a single file and page specific styles are added through additional files as per the requirement.

For eg: grid.css, global.css, heading.css are extracted, merged to a single file and home page specific styles are added through homepage.css.


# Files that are imported:
---------
arc-global.css\
breakpoint.scss\
button.scss\
color.scss\
font.scss\
grid.scss\
tokens.scss

and supporting font, token files.

# Break points that are supported with this Design System:
---------
It's a mobile first approach, below are the break points\
0 - 575px\
577px - 767px\
768px - 1023px\
1024px - 1365px\
1366px - 1679px\
above 1680px

# List of components/items and design elements inheritted from Arc Design Systems:
---------
Button components - \
Headers - H1 - H6\
Paragraph or Eye brow text with - pre-defined font sizes using class font-size-eyebrow-small, font-size-eyebrow-large, font-size-body-xsmall, small, medium, large as per respective breakpoints.
