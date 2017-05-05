---
layout: meta
permalink: /meta
---
# Meta Portal



#### Technology favors the rich

We see the world as fundamentally improved by technology. However, technology does not in itself solve problems. All too often, improvements for the richest facets of society do not reach the poor. Despite the ubiquity of smart phones in the industrialized world, more than 1/2 of the global population does not have even basic access to the Internet. As of 2016, [The International Telephone Union](http://www.itu.int/en/ITU-D/Statistics/Documents/facts/ICTFactsFigures2016.pdf), in it's annual report on the matter, showed that only 48% of the world has access to the Internet. As you might expect, that also falls along traditional lines of class, race, and gender. While 75% of Africans are unconnected to the 'Net, only 21% of Europeans are. Women are 12% more likely to be without access than men. Only 16% of people in less developed countries use the Internet while rural folks are almost twice as likely to be without access when compared to their urban counterparts.

#### Even good intentions reproduce the problem

To solve that, we have to think in ways that are anti-oppressive, intersectional, and explicitly aware of privilege. We can look to projects like One Laptop per Child which, while execcuted with the best of intentions, was unable to solve the crises of poverty. [The World Bank](https://blogs.worldbank.org/impactevaluations/one-laptop-per-child-is-not-improving-reading-or-math-but-are-we-learning-enough-from-these-evaluati) recognizes that despite 10s of millions of distributed laptops, giving children out-of-context technology does not improve their math or reading scores. Certainly, standardized test scores are not the end-all, be-all of education metrics, but they are all we have. The only thing that OLPC did improve was the children's engagement with technology. This is should be obvious--giving children computers makes them more familiar with computers. What it doesn't do, however, is change anything structurally.

### Guidelines


##### Code of Conduct
Racism, sexism, misogyny, transphobia, classism, and all other forms of discrimination will not be tolerated. We will ask you to leave the organization until such time as you apologize, grow up, make amends and check your privilege.

#### Acknowledge your privilege
Do not take it for granted and explain every step. All of the documentation should be cross-platform, with every single step documented. While we seek to be comprehensive in our content, think of articles as short lesson plans whether than encyclopedia articles. The content should explain the technology without getting bogged down in technical details. Avoid the use of idiomatic language as this content will eventually be translated.

#### Each article should stand on its own
Every village, town, and city is different. Do not assume you know what is best for every situation. To that end, all code, technology, and documentation should function by itself. If people need to communicate to loved ones, they do not necessarily need to write documents. If they need to learn about radio waves--they do not necessarily need to know the underlying physics. That does not mean that information should know be available and a part of this wiki. It just means that we should limit the scope of each page or project to something easily digestable. 

#### Style guide and Code Standards
In order to maximize portability, offline usage, and reproducibility we ask that you file these style guides and code standards:

#### Site Design
* Always err on the side of heavy documentation and human-readable code. 
* Use Markdown for all content, html for layouts in the _layouts folder. If you are not familiar with Markdown, use Remarkable (Linux) and MacDown (OS X) to generate the code from an interface similar to Microsoft Word. 
* We will abstract the CSS and site style to the _config.yml in the [root directory of the site](github.com/thenextbilliononline/thenextbillion.online). Generic documentation for jekyll-based websites can be found [here](https://jekyllrb.com/docs/github-pages/) 
* The site styleguide for colors, fonts, and other assets can be found [here](/style-guide) 

#### Site Layout

* Our site has 3 main sections, as well as the default.html main page: meta, wiki and blog.
* There is also a [test section](/test) for meta level page/layout testing. 
* There is a draft section for blogs [here](/blog/draft). As you're building the site, remember to always use relative links "/blog" as opposed to "thenextbillion.online/blog".


#### Meta
* The Meta section hosts this page as well as any other self-referential content. 
* This section is the place for things like finance reports, staff pages, and other corporate-type things.
* It is also the place to document policies and best practices.
* A github account is required to submit pull requests and edits. When there is a **mature**, decentralized solution, we will migrate it there. This is why portability is crucial.
* Workflow tools are important--and githubs are superior to gitlab for the time being.
* Because we aim to reduce the barrier to entry


#### Blog Posts
* The Blog is intened to be a space for complete projects--how to build a raspberry pi radio, how to flash a router, how to make an icon with open source software, etc.  
* All blog posts should be self-contained, including any dependencies and documentation needed to complete the project as a new user of technology. Do not assume any basic level of knowledge. 
* When a particular concept is esoteric, link to its wiki page.
* Blog posts live in the _posts folder of [root directory of the site](github.com/thenextbilliononline). 
*Draft pages lives in a folder called draft and use the draft layout.
*Documentation for jekyll blog posts in general lives [here] (https://jekyllrb.com/docs/frontmatter/). 


#### Wiki Articles
* The current editable wiki lives [here.](https://github.com/thenextbilliononline/thenextbillion.online/wiki). It is then moderated, edited and pushed to the website on an as-needed basis. 
* Wiki articles are for background-information, theory, and esoteric knowledge related to technology.
* Each article must be self-contained, but can certainly use previous topics as background information. Please just link this to background infromation using relative links.
* Because Wikipedia already exists and suffers from problems of jargon and requirements of technical expertise, our content must be understandabe to a new user of technology, who likely doesn't speak English as their first language. Aim for lesson plans rather than encyclopedia entries.
* Avoid idiomatic phrasing and terminology that would make it difficult to translate.


#### Software
* Our software tools live [here.](https://github.com/thenextbilliononline) 
* If you would like to add a tool to the repository, just fork it from another repo or make a new repository for original code.
* Documentation is crucial. To the best your ability, document development processes for Mac OS, Linux, and Windows.
* For software installation, document for **at least** Debian Linux. Windows and Mac users can use a virtual machine, raspberry pi, or remote server to deploy code. 
* If your documentation requires background information, link to it from the [wiki](https://github.com/thenextbilliononline/thenextbillion.online/wiki), the appropriate [blog post](/blog), or write the documentation yourself in a README.
* Always choose to aggregate documentation in the wki or blog sections, as opposed to the README where appropriate.


#### Licenses
* Software, icon, font, and content licenses live [here](/licenses). 
* Because we seek to make our content available for free, we must only use work in the public domain. 
* All original content will be published under the [GPLv3](/licenses/GPLv3.md) license to maximize portability and keep others from profitting of our collective hard work.
* Software, site assets, and other tools must also be open source. Prefer licenses that allow for commercial reuse like [Apache](/licenses/Apache.md) or [MIT](/licenses/MIT.md). The idea here is that users in developing countries can take open-source tools to build their economies and careers. Where commercial reuse is not available, make an explicity note of it on both the licenses page and the software's README.


