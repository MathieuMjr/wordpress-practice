# PORTFOLIO - WORDPRESS PROJECT - UPDATED : 2026-09-02

In order to practice website creation with Wordpress, I imagined this project : a wordpress website for a fictional scientific culture association.

In this readme file, I will keep track of my tasks, reflections, designs and overviews of my work.

IA is used as a mentor. I intentionally chosen not to generate code with it so I can learn by practice and build strong knowledge, skill and understanding of concepts and languages. 

## TO-DO List
- Identify the many contents to display (pages names, forms, calendars, shop...) and imagine the hierarchy of pages
	- Do a wireframe to anticipate UX (nav bar, side bars, and other element dispositions)
		- Figma mock up with graphic identity, layout, page sequences...
- Develop the interface with css, html, JS
	- php use ?
	- get familiar with Wordpress features
- Implement modules  (calendar, blog/news feed, online payment)

## PROBLEMATIC :
The association evolve in the field of scientific culture and popularization. It has many activities to promote to different publics : 
- Current exhibitions
- On site workshops 
- Events such as conferences, science festivals, scientific live shows...
- Itinerant resources : light exhibitions, workshops
- Media resources : tutorials, articles, podcasts, vidéos
- Online ticketing service
- Practical information
- Institutional contents : for press and medias, partners and potential clients, sponsoring and patronage, researchers

I might consider not to implement pages that would require a proper architecture with back-end and database in the context of this specific exercice. 
## DESIGNS
### Interface - Lists of contents :
Theses lists of contents helps to anticipate the kind of contents of the website, ordered by topic or section.
It is more a list of content than a hierarchy. Final hierarchy will be decided later. 

| Section/Topic                                                       | Elements                                                                                                                                                                                  |
| ------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **To determine**                                                    | - Search icon<br>- Cookies consent<br>- Accessibility mode<br>- Press page (footer ? - pro)<br>- Job opportunities (footer ? - pro)<br>- Newsletter(s!)                                   |
| **Header**                                                          | - Name of the structure/baner<br>- Navigation bar                                                                                                                                         |
| **Footer**                                                          | - Contacts<br>- Financers logos (- instutional)<br>- Terms and conditions (CGU/CGV)<br>- Legal notices (mentions légales)<br>- RGPD<br>- Social medias logos and links                    |
| **About us**                                                        | - Presentation & missions<br>- Association Bureau (- instutional)<br>- Teams<br>- Financiers, sponsors and partners (- instutional)<br>- Activity reports (- instutional)<br>- Job offers |
| **Landing page**                                                    | - Current exhibitions<br>- Events programmation<br>- Workshops<br>- News feed                                                                                                             |
| **Media ressources**                                                | - Explore by topic<br>- Explore by media type<br>- Latest                                                                                                                                 |
| **Practical information**                                           | - Contacts<br>- Opening hours<br>- Access to the muséum and facilities (parkings, public transports)<br>- Prices                                                                          |
| **Itinerant resources (pro - schools, libraries, leisure centers)** | - Itinerant exhibitions (light)<br>- Itinerant exhibitions (heavy)<br>- Itinerant workshops<br>- Itinerant planetarium<br>- Itinerant educational cases                                   |
| **Support / get involved**                                          | - Volunteer's opportunities/contributions/programs <br>- Membership<br>- Donations                                                                                                        |
| **Ticketing service/booking**                                       | - Choose an offer and a time slot (if concerned)                                                                                                                                          |
| **Pro/sponsor space**                                               | - Programs<br>- Space rent and facilities                                                                                                                                                 |

### Interface - Moodboard/Benchmark

| Structure                    | Link                                                         | Notes - desktop version                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | Notes - mobile version                                                                                                                                                                                                                                                                                                   |
| ---------------------------- | ------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Espace des sciences (Rennes) | https://www.espace-sciences.org/                             | - Landing screen : access to a specific site program<br>- Then, current exhibitions, latest news<br>- Entries by publics (Familly, Groups, Students, Teachers, Press...)<br>- Uses sections and then cards + navigation bar<br>- The landing page gives an easy overview of every topic in the nav bar and quick access - redundant with nav bar but ok ? A bit long to scroll but gives two way to reach information in few clicks                                                                                                                                                                                               |                                                                                                                                                                                                                                                                                                                          |
| DRAEC BFC                    | https://draeac.region-academique-bourgogne-franche-comte.fr/ | - Not a scientific culture center but still similar missions and contents<br>- Wordpress website<br>- Carousel block<br>- 4 latest news and then link to "all news"<br>- The landing page gives a quick overview of main nav bar topics<br>- Use mostly bullet lists in pages but ok with professional public target                                                                                                                                                                                                                                                                                                              |                                                                                                                                                                                                                                                                                                                          |
| La Rotonde                   | https://www.larotonde-sciences.com/                          | - A lot a different way to navigate (pro corner in top right, nav bar, huge footer with a mix a legal information, pratical information and sections for professionals) - not fond of it<br>- No section names on the landing page<br>- Patchwork of cards of different sizes with current activities and some topic they want to zoom on<br>- Navigation bar speaks mainly to professionals. I think I'd prefer on entry for professionals instead of many entries in the nav bar.                                                                                                                                               | - Responsive works well (better)<br>- Still a bit too much text in cartels of cards + footer is too big imo<br>                                                                                                                                                                                                          |
| La Casemate                  | https://lacasemate.fr/                                       | - Another system of cards. The biggest one is a carousel dedicated to last information but navigation is not very clear. Other cards are zooms on specific aspects. <br>- Cards got labels, easiest to read than a low opacity cartel on top of the picture<br>- ==Nav bar is dedicated to public content==. ==Pro section is clearly separated==. (I like it)<br>- ==Not too much scroll, not too much elements==                                                                                                                                                                                                                | - Too much space on the main card/carousel.<br>- Medias format is more desktop compatible than ideal for smartphones.<br>- Menu is not very friendly - a lot of entries > small text, grey and white, does'nt take all width                                                                                             |
| Cap-sciences                 | https://cap-sciences.net/                                    | - A big banner takes almost all the screen on the landing page. carousel giving current informations, nav bar juste below, beautiful (but carousel are not clear so you can notice it by chance)<br>- Ticketing service juste below the nav bar<br>- Then "current activites with 2 entries" - simple but efficient<br>- A plan invite to discover the many spaces and activities onsite<br>- Multiple footers but very tidy ; from up to down : about, socials, newsletter, institutional informations, financiers logos, legal informations<br>- On entry for professionals<br>- A bit too much information on the landing page | - Nav bar is still there with icons and no text - not fond of it<br>- Can't see the menu icons but it's there<br>- Current activities with horizontal scroll on the section /!\<br>- Logo above the picture on the landing screen - works well<br>- Menu takes all width with a cross to quit the screen few entries<br> |
### Interface - Final decisions : hierarchy, display, styles

#### - Hierarchy:
Landing page - banner w/ current exhibitions, nav bar, then latest news
	Current offers
		Exhibitions
		Workshops
		Events
	Practical informations
		Opening hours
		Prices
		Access
		PMR
		Groups
		Amenities
	Ressources
		Articles (typology of kind of articles)
		Podcasts
		Videos
		Games
	Ticketing service
Floating element on every pages (will it be readable by vocal assistants ?)
	Accessibility icon
	Cookies consent icon
	Language
Header
	Search bar
Footer
	Socials icons
	Newsletter(s)
	Pro content navigation : You are... (schools, teachers, press, pros)
		Teachers
		Professionals
		Press
	Address, contacts, about us (nav)
		About us (missions, values)
		Association bureau
		Teams
		Job opportunities
		Get involved (Volunteering, Membership)
	Financiers and sponsors logos
	Legal informations

#### Styles by content/element

#### General information styles :
| Information         | Style                                                                          |
| ------------------- | ------------------------------------------------------------------------------ |
| Title               | Black, caps                                                                    |
| Section Title       | Bold                                                                           |
| Body text           | Regular                                                                        |
| Links               | Bleu, underligned<br>- hover : coloured texte background<br>- visited : purple |
| Highlighted         | Yellow text background (if contrast ok)<br>Italic, Bold <br>Sérif ?            |
| Subtitle            | ?                                                                              |
| Quote               | Block                                                                          |
| Special information | Insert                                                                         |
## QUALITY 

- Responsive - adopt mobile first
- Accessibility - keyboard navigation, contrast, screen readers compatible, aria labels if necessary
- Good SEO, looks for good practices to improve SEO for AI
- Aesthetic in prevailing trend