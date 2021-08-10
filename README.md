# Web Accessibility Resources
A list of favorite resources.  Please make an issue or PR to add!

## Introductory materials

This is a place to start if you're not familiar with web accessibility.  It's also a good list of resources to send to your boss, coworker, or vendor if they give you a blank stare when you say something like "keyboard navigability."

  - [Web user stories](https://www.w3.org/WAI/people-use-web/user-stories/): stories about how people with different disabilities use the internet, and the barriers that may affect their experience

  - [Applied accessibility tutorial for developers](https://www.freecodecamp.org/learn/responsive-web-design/applied-accessibility/): practical introduction for writing good HTML

  - [Posters about accessible design](https://ukhomeoffice.github.io/accessibility-posters/posters/accessibility-posters.pdf): short, clear explanations of how to design for a few different groups of users-- great for hanging in an office where people think accessibility is just about screen readers!

  - [Don Norman on accessibility for older adults](https://www.fastcompany.com/90338379/i-wrote-the-book-on-user-friendly-design-what-i-see-today-horrifies-me): the man who coined the term "human centered design" writes about his own experiences

  - [Law blog with recent updates on US legal context](https://www.lflegal.com/2019/10/dominos-comments/): this particular article is about misconceptions with the recent Domino's pizza case

  - [The Web Content Accessibility Guidelines themselves](https://www.w3.org/TR/WCAG21/): I would encourage anyone to read them through at least once.  Even if you don't memorize them, you'll be more likely to get a nagging feeling that you should research implementation methods when you're working on something they cover.
  
  - [A giant list of courses, webinars, educational videos, etc](https://github.com/mgifford/a11y-courses)

## Working with vendors

  - [Accessibility reviews of tools, services, and platforms](https://a11y.reviews/)

  - [What you should ask vendors](http://teachingcommons.cdl.edu/access/procurement_process/demonstration.shtml): an oldie but a goodie

## Checklists

In my experience, checklists are the most effective way to audit your code base and catch bugs.

  - [Easy checks](https://www.w3.org/WAI/test-evaluate/preliminary/): not comprehensive, but a good place to start

  - [Resources for different roles on a team](https://accessibility.digital.gov/): what each member of a web team should be considering in their role

  - [Checklist from 18F](https://accessibility.18f.gov/checklist/)

  - [WebAIM checklist](https://webaim.org/standards/wcag/checklist)

## Manual tools and screen readers

  - [WebAIM guides for screen readers JAWS, NVDA, and VoiceOver](https://webaim.org/articles/#evaluation)

  - [NoCoffee vision impairment simulator Chrome extension](https://medium.com/@chrisquinnr/nocoffee-the-vision-impairment-simulator-you-should-be-using-f81992c1effc)

  - [Color contrast checker](https://webaim.org/resources/contrastchecker/?fcolor=FFFFFF&bcolor=FDD835)

  - [A more in-your-face color contrast checker](https://colorable.jxnblk.com/450100/176dab)

## Automated tools

Automated tools are useful to catch issues that a computer can detect programmatically like color contrast and header level, but [catch only about 70% of accessibility issues](https://accessibility.blog.gov.uk/2017/02/24/what-we-found-when-we-tested-tools-on-the-worlds-least-accessible-webpage/). An automated tool cannot tell you if your content makes sense, if the order in which a user perceives it is helpful, or generally if what you've built is usable.

  - [WAVE - checks a URL you enter](https://wave.webaim.org/)

  - [axe Chrome extension from Deque](https://www.deque.com/axe/)

  - [axe testing engine](https://github.com/dequelabs/axe-core)

  - [jest-axe](https://github.com/nickcolley/jest-axe): for writing jest tests using axe

## Data visualization, maps, and SVG

The text below is an excerpt from an article that I wrote about the basics of web accessibility for data visualization.  You can [read the whole thing at the Data Visualization Society's blog, Nightingale](https://medium.com/nightingale/data-visualization-accessibility-where-are-we-now-and-whats-next-b2c9eeac4e8b).

The Web Content Accessibility Guidelines are limited in scope and do not explicitly address data visualization, other than using charts as an example of something for which you need to provide a text alternative. W3C’s tutorials recommend a short text alternative and a long description, which in their example is a table.

While the standards aren’t clear on the implementation details of charts or maps, they do discuss some of the techniques we use to convey meaning with data:

  - Color (standards 1.4.1, 1.4.3, 1.4.11): Use colors with a high contrast ratio and consider what additional visual cues (like patterns) could differentiate variables. Automated tools can be helpful to detect color contrast. Consider using a browser extension like Colorblinding to check your work.
  
  - Interaction (standards 2.1, 1.4.13, 2.4.3): Users should be able to do anything with a keyboard that they can do with a mouse. For data vis, that might include a tooltip that shows on hover, or a filter that is triggered by a click. If a user navigates through your data visualization with a keyboard, they should be able to do so in an order that makes sense. Users should be able to exit this interaction and not get stuck in a loop.
  
  - Animation (standards 1.2, 2.2, 2.3): Provide alternatives for time-based media. Do not use flashing images. Users should have control over the timing of animations.

## User research resources

Team familiarity with the guidelines, regular internal audits, and automated tools can help you design with accessibility in mind and catch bugs that you are introducing to the code base.  But only user research will tell you if what you're building truly works for everyone.  There are organizations you can pay for help with user research.

  - [The World Institute on Disability](https://wid.org/) does usability research

  - [Fable](https://www.makeitfable.com/) recruits users with disabilities for you and offers accessibility QA
