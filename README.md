- ## https://mirazayic.github.io/test_softab/
- ## link for the second page is attached to the logo - tirgo (on the top of the page)

<br>

- I tried to achieve best match to the design. Reasons where it is not exact:
  - lack of some assets (images for background on both pages, and images for shipped items)
  - lack of the exact fonts
  - for social icons (footer), I used Font Awesome

<br>

- best match is in Chrome

<br>

- There is a lot of px moving to match the design, beside flexible features (flex, grid)
- In a real project, with dynamically created content (from database) it can produce bugs
- Also, in a real project it is considered the best practice, beside this above, to use relative units (rem, em, %, vh...) and unitless values to meet the needs of ever-changing viewport sizes (now, for the purpose of matching the design in pixel sence, I used absolute one: px)

<br>

- In short, reasons to use relative units and flexible values for the display property (but, it can't produce 'px perfect' match with the design) are:
  - best achieved responsive design and less prone to issues
  - quicker rendering (for a slow internet connection and big apps it can be a big difference)
  - code that meet accessibility guidelines
  - clean code, less lines (easy for team collaboration, easy to maintain and scale up project)
