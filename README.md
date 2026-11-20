# Accessibility Conformance and Inclusive Quality Build
CSS and HTML for Module 5: Deliverable: Accessibility Conformance and Inclusive Quality Build

# Test Scope
I tested all four of my pages: my home page, my work page, my resume page, and my contact page. I tested my home page because it is the first thing that my users will see, and I want them to be able to understand what this website is about right away. I tested my work page and my resume page because they involve grid displays that present important information. Users need to be able to see and comprehend the images on my work page, and the information on my resume page. I tested my contact page because I wanted to ensure that potential clients and / or employers would be able to reach me. This page features two important links, and I want to make sure that these links display correctly and do not break.

# Semantic Structure
## Native HTML: Tested using WC3 Validation
### Findings:
   + Index page: "Section Lacks Heading" warnings for lines 25, 26, and 35.
   + Spelling errors across all pages due to filler text, which will be replaced.

## Page Titles: Manually Tested
Checked all four page titles to make sure that they made sense and appeared in tabs across two browsers (Firefox and Chrome), as well as in the DevTools and inspection window.
### Findings: 
   + Index Page: None. (In final version, title should be changed to title of website.)
   + Work Page: None.
   + Resume Page: None. 
   + Contact Page: None.

## Landmarks: Tested using Silktide
Used the "landmarks" check to ensure that all page parts had the correct landmarks.
### Findings:
  + Index Page: None.
  + Work Page: None.
  + Resume Page: None.
  + Contact Page: None.

## Headings: Manually tested. (WC3 Validation Outline Viewing)
Used the WC3 Validator to view an outline of all pages and confirm that the headings were correct.
### Findings:
  + Index Page: None.
  + Work Page: None.
  + Resume Page: None.
  + Contact Page: None.
  
## Links: Manually tested. 
Opened links in two browsers (Chrome and Firefox) to make sure that they opened correctly and without breaking.
### Findings: 
   + Index Page: None.
   + Work Page: Must add links to images so that they open in a new tab.
   + Resume Page: None.
   + Contact Page: Must Replace Email Link with actual Mailto Link instead of website link.

## Accessible Names: Tested using WC3 Validator and Silktide
Used WC3 Validator to scan for errors, and ran an Accessibility Check in Silktide to catch labeling issues. I used the screen reading feature to see how the content of the website flowed.
### Findings:
   + Index Page: Nav lacks accessible text.
   + Work Page: Nav lacks accessible text.
   + Resume Page: Nav lacks accessible text.
   + Contact Page: Nav lacks accessible text.

# Keyboard and Focus
### Keyboard focus: Manually tested.
Navigated the pages in Firefox and Chrome with tab, shift + tab, and enter.
  ## Findings:
  + Index Page: None.
  + Work Page: None.
  + Resume Page: None.
  + Contact Page: None.

## Focus order: Tested in Silktide.
Used the focus order check in Silktide to ensure the focus order was correct, and accurately reflected by the keyboard focus.
### Findings:
  + Index Page: None.
  + Work Page: None.
  + Resume Page: None.
  + Contact Page: None.

## Focus visibility: Manually tested.
Used mouse and keyboard to navigate website, ensuring that all links and buttons reacted in the intended way in both Firefox and Chrome.
### Findings:
  + Index Page: None.
  + Work Page: None.
  + Resume Page: None.
  + Contact Page: None.

## Skip links/current page states: Manually tested.
Tested current page states by clicking between pages, and making sure that each page's button changed color when that page was navigated to in both Firefox and Chrome.
### Findings:
  Current page states are working correctly. No skip links are included in this website.

## Keyboard traps: Manually tested.
Navigated the pages in Firefox and Chrome with tab, shift + tab, and enter.
### Findings:
  + Index Page: None.
  + Work Page: None.
  + Resume Page: None.
  + Contact Page: None.

## Zoom / Reflow and Text Spacing: Manually tested.
Tested all four pages at 250px, 750px, and 1080px breakpoints and up to 200% Zoom. I performed these tests in two different browsers (Firefox and Chrome) and tested all available screen sizes in Silktide,     to get a full picture of how my website functions.
### Findings:
  + Index Page: None.
  + Work Page: None.
  + Resume Page: None.
  + Contact Page: None.

## Contrast: Used Silktide Accessibility Checker.
Ran an Accessibility check in Silktide.
### Findings:
   + All four pages had a contrast error, stemming from my selected green accent color.

# Media, motion, and alternatives 
## Image purpose: Manually tested.
Reviewed HTML to ensure that all images are either contained in a <picture> tag, an <img> tag, <svg> tag, or a <figure> tag depending on their function.
### Findings:
  + Index Page: None.
  + Work Page: None.
  + Resume Page: None.
  + Contact Page: None.
  
## Alt text: Checked alt text in Silktide
I ran Silktide's alt text check, and then manually reviewed my HTML to make sure that all of my images had alt text.
### Findings:
 + Index Page: None.
 + Work Page: None.
 + Resume Page: None.
 + Contact Page: None.
  
## SVG labels: Used the Silktide screen reader feature to see if my SVGs were labelled in any way.
### Findings:
 + Index Page: N / A.
 + Work Page: N / A.
 + Resume Page: N / A.
 + Contact Page: My SVGs were not labelled (The screen reader skips them) They are decorative images, and do not need alt text.

## Fallback links: Manually tested.
The only fallback links I have are font fallbacks. I tested my font fallbacks by deliberately changing my font rules so that my "font-family" property could not identify my chosen font and was forced to default to the fallback.
### Findings:
 + While I was performing this test, I realized that, while my fallbacks are working, there is something wrong with my @font-face property, because my fallback fonts are appearing instead of my chosen fonts      across all four pages. 

# Screen reader or accessibility-tree sampling: 
I performed screen reader sampling on my Work Page, because I want all users to be able to understand and comprehend my work. I used Silktide to listen to the pages captions. 
sample at least one page or component and document what was checked and what the limits of that sample are.

# Remediation log: 
See .txt file.
document at least five findings with issue, evidence, impact, priority, fix, and retest result.

# Conformance summary: 

summarize what appears to conform, what was fixed, what remains limited, and what should be checked again before final release.

# AI Disclosure:
I did not use AI to complete this assignment.

