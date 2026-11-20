Remediation Log



**Finding 1 :** Index Page - A warning. "Section lacks heading" (Line 25, Line 26). Line 25 opens the hero-wrap section, and line 26 opens the actual hero section. According to the error note, these sections can be turned into divs, or have headings added to them.



**Evidence**: According to this MDN article (**https://developer.mozilla.org/en-US/docs/Learn\_web\_development/Core/Structuring\_content/Headings\_and\_paragraphs#:\~:text=Giving%20content%20structure,-Let%27s%20jump%20straight%20in)**



"A common navigation technique for users of screen reading software is to quickly jump from heading to heading in order to determine the content of the page. Because of this, it is important to not skip one or more heading levels."



**Impact:** Because lines 25 and 26 contain two sections back to back, this has the possibility to create confusion for  users accessing the website with screen readers. 



**Priority:** High Priority, because it creates an accessibility issue and makes it difficult for all users to access the website's content.



**Fix:** I am adding an h2 to the hero-wrap section. The h2 says "Hi there!", indicating to users that there is going to be a transition/introduction. I also changed the hero section to a div, because it only contains an image, and therefore does not need a heading.



**Retest Result:** A header appeared on my page, resolving the WC3 Validation Error. This change did not break my layout.



**Finding 2 :** All Pages - Nav lacks accessible text.

**Evidence:**

**Impact:**

**Priority:**

**Fix:**

**Retest Result:**



**Finding 3 :** All Pages - contrast error with green accent color.

**Evidence:**

**Impact:**

**Priority:**

**Fix:**

**Retest Result:**



**Finding 4 :** @font-face functioning incorrectly. My fallback fonts are appearing instead of my chosen fonts.

**Evidence:**

**Impact:**

**Priority:**

**Fix:**

**Retest Result:**



**Finding 5 :** Index Page - A warning. "Section lacks heading" (Line 36).

**Evidence:**

**Impact:**

**Priority:**

**Fix:**

**Retest Result:**





