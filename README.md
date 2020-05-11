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

Automated tools are useful to catch issues that a computer can detect programmatically like color contrast and header level, but [catch only about 30% of accessibility issues](https://accessibility.blog.gov.uk/2017/02/24/what-we-found-when-we-tested-tools-on-the-worlds-least-accessible-webpage/).

  - [WAVE - checks a URL you enter](https://wave.webaim.org/)

  - [axe Chrome extension from Deque](https://www.deque.com/axe/)

  - [axe testing engine](https://github.com/dequelabs/axe-core)

  - [jest-axe](https://github.com/nickcolley/jest-axe): for writing jest tests using axe

## Data visualization, maps, and SVG

Currently, W3C's recommendation for charts is to include a short text alternative and a long description.

Anyone who has worked in data visualization knows that we are technically capable of so much more. Interactive charts made with scalable vector graphics (SVG) can support features like keyboard navigability and labels for screenreaders. A few individuals and libraries have begun to explore and implement accessible features for some use cases.

## User research resources

Team familiarity with the guidelines, regular internal audits, and automated tools can help you design with accessibility in mind and catch bugs that you are introducing to the code base.  But only user research will tell you if what you're building truly works for everyone.  There are organizations you can pay for help with user research.

  - [The World Institute on Disability](https://wid.org/) does usability research

  - [Fable](https://www.makeitfable.com/) recruits users with disabilities for you and offers accessibility QA
