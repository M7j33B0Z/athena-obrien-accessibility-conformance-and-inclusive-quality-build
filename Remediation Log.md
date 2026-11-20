Remediation Log



**Finding 1 :** Index Page - A warning. "Section lacks heading" (Line 25, Line 26). Line 25 opens the hero-wrap section, and line 26 opens the actual hero section. According to the error note, these sections can be turned into divs, or have headings added to them.



**Evidence**: According to this MDN article (**https://developer.mozilla.org/en-US/docs/Learn\_web\_development/Core/Structuring\_content/Headings\_and\_paragraphs#:\~:text=Giving%20content%20structure,-Let%27s%20jump%20straight%20in)**



"A common navigation technique for users of screen reading software is to quickly jump from heading to heading in order to determine the content of the page. Because of this, it is important to not skip one or more heading levels."



**Impact:** Because lines 25 and 26 contain two sections back to back, this has the possibility to create confusion for users accessing the website with screen readers. 



**Priority:** High Priority, because it creates an accessibility issue and makes it difficult for all users to access the website's content.



**Fix:** I am adding an h2 to the hero-wrap section. The h2 says "Hi there!", indicating to users that there is going to be a transition/introduction. I also changed the hero section to a div, because it only contains an image, and therefore does not need a heading.



**Retest Result:** A header appeared on my page, resolving the WC3 Validation Error. This change did not break my layout.



**+++++**



**Finding 2 :** All Pages - Nav lacks accessible text. The nav section on all four of my pages lacks an aria-label.



**Evidence:** According to this MDN article (**https://developer.mozilla.org/en-US/docs/Web/Accessibility/Guides/Understanding\_WCAG/Text\_labels\_and\_names**)



"If an element is intended for users to interact with it, it should have a label. Interactive elements include links (<a>), form elements, buttons, and any element that has a handler for mouse or keyboard events."



**Impact:** This impacts users with assistive technology, because items without accessible names may be confusing or unclear for users with screen readers.



**Priority:** High Priority, because it creates an accessibility issue and might make it difficult for users with screen readers to navigate the website.



**Fix:** I placed role and aria label tags inside my <nav>.



**Retest Result:** The error did not resolve. Instead, a warning appeared in my WC3 validator that adding a role and an aria-label was unnecessary. I removed the modification. This area is subject to further testing, and the error has been deferred.



**+++++**



**Finding 3 :** All Pages - contrast error with green accent color. Silktide has noted that my green navigation buttons fail their contrast check when paired with white text, generating a ratio of 2.24:1 / 3:1.



**Evidence:** According to this MDN article **(https://developer.mozilla.org/en-US/docs/Web/Accessibility/Guides/Understanding\_WCAG/Perceivable/Color\_contrast)**



**"**The color contrast between background and foreground content (that is, usually text) should be great enough to ensure legibility." 



**Impact:** This issue impacts a portion of users who might be visually impaired or color blind. It affects their ability to navigate the website itself.



**Priority:** High priority. This issue prevents users from navigating my website.



**Fix:** I changed the text color of my nav links from --background-color to --text-color.



**Retest Result:** A new test generated a ratio of 7.52 : 1, a passing ratio.



**+++++**



**Finding 4 :** @font-face functioning incorrectly. My fallback fonts are appearing instead of my chosen fonts.



**Evidence:** This MDN Article () contains an example of a @font-face stack: 

@font-face {

&#x20; font-family: "zantrokeregular";

&#x20; src: url("fonts/zantroke-webfont.woff2") format("woff2");

&#x20; font-weight: normal;

&#x20; font-style: normal;

&#x20; font-display: swap;

}



I believe the issue here is my missing format element in the src.



**Impact:** This is potentially concerning when it comes to my layout and reflow choices. Because the font being displayed does not accurately reflect the font that should be displayed, it may break my layout.



**Priority:** Low priority. It does not affect the legibility of my website.



**Fix:** I added the format property to my src.



**Retest Result:** This did not remediate the issue. I removed the format property, and tried adding and removing other properties, such as font-display, and font-style. These fixes failed. This issue has been deferred, and is subject to further testing.



**+++++**



**Finding 5 :** Index Page - A warning. "Section lacks heading" (Line 35). The section containing information about me is not labeled with a heading, so screen readers will skip directly from my image to reading content with no transition.



**Evidence**: According to this MDN article (**https://developer.mozilla.org/en-US/docs/Learn\_web\_development/Core/Structuring\_content/Headings\_and\_paragraphs#:\~:text=Giving%20content%20structure,-Let%27s%20jump%20straight%20in)**



"A common navigation technique for users of screen reading software is to quickly jump from heading to heading in order to determine the content of the page. Because of this, it is important to not skip one or more heading levels."



**Impact:** This might cause confusion for users with screen readers, because it makes the content on my index page difficult to follow.



**Priority:** High priority. It causes an accessibility issue and impedes users' ability to understand the content of my website.



**Fix:** I added an h2 called "About Me" to the section, so that screen readers can transition between the two sections of content more smoothly.



**Retest Result:** A header appeared on my page, resolving the WC3 Validation Error. This change created a formatting issue, which will have to be addressed.

