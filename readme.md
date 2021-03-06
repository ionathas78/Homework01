# 01 HTML CSS Git: Code Refactor
> I refactored the web site for a marketing company to clean it up and provide SEO

The web page for Horiseon Social Solution Services looked great, but it had a broken link 
and needed some work at the code level. I made sure the site performed as it should and 
ran an optimization pass to get everything shipshape for SEO.

## User Story

```
AS A marketing agency
THEY WANT a codebase that follows accessibility standards
SO THAT their site is optimized for search engines
```

## Design Values

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Changes
1. Changed the page title to add description.
2. Added ID to repair broken link.
3. Added alt-descriptions for images and made image tags self-closing.
4. Renamed &lt;div&gt; blocks to leverage HTML5 semantical groupings.
5. Fixed misleading Header levels.
6. Added viewport support for mobile devices.
7. Removed IDs that duplicated new semantical groupings and renamed confusing IDs.
8. Made 'Gill Sans' the default body font and removed 5 duplicate definitions while preserving existing formatting.
9. Changed Nav bar to inline-flex display to correct placement on mobile devices.
10. Consolidated duplicate classes and streamlined CSS selectors.
11. Updated page copyright.

## Screenshot
![Webpage screenshot](horiseon_screenshot.jpg)
