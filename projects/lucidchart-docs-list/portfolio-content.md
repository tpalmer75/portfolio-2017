# Lucidchart Documents List
![](cover.jpg "Lucidchart Heat Map")
### Project Overview
For my first project at Lucid I was challenged to redesign the Lucidchart Documents page. This page is the central hub for users to create, manage, and share their documents. It receives upwards of 30,000 visits per day, and is often a customer’s first interaction with the product.

**Timeline:** August 2015–October 2015

**Hypothesis:** By optimizing and updating the Documents page, users would be more likely to pay and return to the product.

**Team:** I worked closely with a product manager and engineering lead to scope out timelines and technical requirements. 

**Role:** User research, UI design

### Research
The hypothesis for this project was pretty vague, so it was my job to determine what was wrong with the design and what could be improved. I started by analyzing heat maps.

![Heatmap Analysis](heatmap.jpg)

As the heat map shows, most of the engagement follows an “F” pattern from the top left of the page. The control panel on the right shows almost no engagement. I cross-referenced this knowledge with more exact statistics from Lucid’s usage data. Most of the red items in this spreadsheet are the options from the control panel above.

![Analytics data in Google Sheets](sheets.jpg)

I also took to the phone to interview several users about their experience with this screen. After a brief discussion, it became obvious that most customers were either unaware that the panel existed or did not know what it was for. The insights were clear: users need to do see and organize their document. Everything else was secondary.

### Design
The functionality from the right panel was necessary, just not of primary importance. Because of this, I took inspiration from other products in the market, like Google Drive, to design towards a similar "card" approach. Because the document thumbnail was the most important information on this screen, I sought to bring more functionality to the card itself.

Though the design seems straightforward, this screen of the Lucidchart product is nuanced with many systematic considerations:

- Welcome messaging for new customers
- Error handling and feedback mechanisms (when deleting documents, for examples)
- A robust templating system for creating and sharing template documents
- Sharing and collaboration permissions functionality (like Google Docs)

I wasn't redesigning all of this functionality, but I did have to thoroughly understand it to give proper context and placement within the design.

To begin exploration I looked to exemplars like Google and InVision who had established patterns of card-hovering designs. Knowing functionality could be hidden and revealed, I worked with my product manager and other stakeholders to prioritize that functionality and know what primary actions should call the most attention. Equipped with this information, I presented several options (which are now locked away in an Illustrator file I can't open because I'm a Sketch user 🤷‍♂️).

After several iterations, we landed on the design below. The first image is the original design, and the second is the new design.

![The old design](docs-list-old.jpg "The old design")

![The new design](docs-list-new.jpg "The new design")

The hierarchy of the new design is very clear: a dark header displays navigation, folder structure is seen on the left, and document thumbnails take front and center. The most used functionality (clicking on document thumbnails) takes front and center.

### Prototype
During this project I pushed on my team to add more motion and movement to an otherwise static product. To facilitate this new area of design, I created a sample version of the interface in Codepen with HTML, CSS, and jQuery. This prototype was the topic of discussion in many meetings, and was used heavily by the engineering lead to reference colors, measurements, and timing for animation.

![Prototype in Codepen](codepen.jpg)

### Course Correction
At initial release (10% A/B test), the product manager found that sharing metrics were dropping and recommended we diagnose the problem before moving forward.

The culprit: we obfuscated the sharing functionality with an ambiguous icon, which couldn't compete with a big, round "share" button. So we added words to the icons and saw metrics level back out.

![An update to the design](course-correct.jpg)

### Outcomes
Removing the control panel had side effects, but the overall changes were very positive. The director of Growth at Lucid conducted further analysis of the impact and commented in an email to stakeholders:
> Overall, I am very impressed with the magnitude of the impact of the Docs List refresh and hope that these results provide additional support for further activities of this nature. 

**+15%** change in first payments

**+22%** change in payments per person

**-2%** change in basic tasks

**0%** change in document creation

**+2%** change in documents per user

The analysis also showed the customers were more like to purchase higher, more expensive brackets of the product when they encountered to new design. We attributed this outcome to multiple points:

- A modern, trustworthy aesthetic that appears capable and professional
- An more clear hierarchy and easy-to-understand navigation
- A better focus on what matters most: document thumbnails and organization

### What I Learned

This Documents page is actually shared between two products, Lucidchart and Lucidpress. They are never used simulataneously, but the code and exact design is replicated between the two platforms. While getting buyoff for Lucidchart was usually straightforward (I was embedded into the Chart team), frequently decisions would backfire when applied to Lucidpress.

Stakeholders didn't like the new, darker color palette. The fully-filled background images weren't as useful to their customers as seeing the entire document. Further functionality existed in Lucidpress that wasn't present in Lucidchart, like document analytics. If I had met with and gathered requirements from these stakeholders earlier, the project would have run much more smoothly.

At the end of the day, this was a fun and highly visible project for me to start my career at Lucid.