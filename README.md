# Gym Website


[Deployed Project](https://fene20.github.io/gym-website/index.html)


The website here was designed to be simple and non fussy. The gallery images top centre shows two guys giving a high five. When attending a gym class one needs to form mini teams to go through the equipment for e.g. HIIT or TABATA classes.
Mutual support and motivation increases class enjoyment an increseases health outcomes.
There are also those who discuss equipment avaliable at a gym. The top left gallery image was provided to support this.



 
## UX
 
Most Gym users are researching classes and availability during a busy day at work. They want instant access to information with little clicking and scrolling.
This website has a clear Classes page with a Contact Us page. Most Gym Website users are already attending a gym and just want to know some basic details.

- The site's users are gym members and potential members, who want to know more about the gym and its procedures.
- The gym is interested in attracting and retaining members.
- As a Gym user 99% of the time I just want to know what time the classes were on and which classes are available.
- As a Gym provider the gallery section provides welcoming images of the Gym.
- The website promotes the image of a professional well run Gym.
- The Contact Us section allows users to contact the gym as regards membership or class availability.


[Home Page](assets/wireframes/gym_website_home.pdf)
This is the landing page with a hero image.
This page contains the Menu items.
All pages including the home page will have a fixed header and footer.
The header will be setup in thirds. See Phone where the Gym Icon is followed by Home over Gallery and Classes over Contact Us.
See Desktop where the footer is also setup in thirds.
See Phone were the footer is shown in two rows. This may be changed to three rows depending on the font size.
The Icon wil contain the Name of the gym (Gym Website).
The name of the Gym (not displayed in the wireframe) may also be included above the Menu bar so that the Desktop does not look too basic.


[Classes Page](assets/wireframes/gym_website_classes.pdf)
The classes page is the most important page for new and existing members.
This is the one page that will be used the most.
Classes can be pay as you go or free to members with certain membership packages.
The timetable on the Tablet will likely be a squeezed version of the Desktop timetable.
A squashed and wrapped Desktop timetable will not work on the Phone.
The Phone wireframe shows two Desktop columns, one for the Times and one for the Days of the week.
This however does not look well.
The Phone will need a format of it's own with the Day of the week followed by columns with headings of Times and Classes.
Coding this will be a challenge and will likely require a library perhaps Bootstrap4.
The timetable will need to be scrolled up/down.
There is a gap in the footer where the table is visable.
The footer format will be coded to prevent this.


[Contact Page](assets/wireframes/gym_website_contact.pdf)
The Contact page has details of how to contact the gym, a map to help locate the gym and a contact form so that one can submit queries when one is e.g. at work.
Most new users will simply just need to ring or email the Gym regarding classes or membership or to figure out where it is by looking at the map.
Both existing and new members may wish to book a session with a particular instructor or enquire about the exercises in various casses etc.
The Phone Contact page is shown without the fixed footer.


[Gallery page](assets/wireframes/gym_website_gallery.pdf)
The Gallery page has images from the Gym to entice new members to join. These images may highlight particular equipment that the Gym has.
The Desktop may look nicer if the images are in thirds, i.e. three columns instead of two as shown in the wireframe.


## Features
 
### Existing Features
- Feature 1 - The landing page is a simple page with a Hero Image and the relevant Gym Links.
- Feature 2 - The Classes page allows users to see when the classes are scheduled.
- Feature 3 - The Contact Us gives contact details with a map to help users to locate the Gym.
- Feature 4 - The Contact Us page also allows users to input their detail and contact the Gym for feedback on their queries.
- Feature 5 - The Gallery page has images of the Gym to attract new members.


### Features Left to Implement
- Another feature idea would be to add a page with membership options with prices.


## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.




- [Balsamiq Wireframes](https://balsamiq.com/wireframes/desktop/)
    - This project used **Balsamiq Wireframes** to generate the wireframes for this project.

- [Icons](https://fontawesome.com/)
    - This project used free **Fontawesome** icons.
    - The icons uses were, the child icon, facebook icon and instagram icon.

- [CSS-TRICKS](https://css-tricks.com/complete-guide-table-element)
    - This project used code from **CSS-TRICKS** to support debug by enabling a table border.
    - This was used for debug only as Bootstrap was used to generate the Classes table.

- [Bootstrap](https://getbootstrap.com/)
    - This project used a table from **Bootstrap** to generate the classes table.


## Testing

Home Page
- Home page works as expected.
- The Gym Icon and menu change colour with a hover.
- The Active page is highlighted.
- The page is responsive.
- The social media icons open new pages - for every Gym Website page.
- [Home page on a Desktop](assets/testing/Home.JPG)
- [Home page on an iphone](assets/testing/Home_iphone_X.JPG)
- During the Githup deployment it was observed that the images did not load.
- The alt did not work as expected for the Hero Image.
- [Home page on an iphone](assets/testing/iphone_home_alt.JPG) To be Fixed.


Classes
- The classes page works well in desktop.
- It can be moved left and right on an iphone.
- The Active page is highlighted.
- It hovever does not scroll down correctly for an iphone. To be Fixed.
- The solid line under the menu does not remain fixed under the menu with scrolling. To be Fixed.
- [Classes page on a Desktop](assets/testing/Classes.JPG)
- [Classes page on an iphone](assets/testing/Classes_iphone_X.JPG)


Gallery
- The Active page is highlighted.
- The gallery page works well in a desktop. It scrolls up and down.
- The gallery page changes to 2 columns for an ipad.
- The gallery page changes to 1 columns for an iphone.
- [Gallery page on a Desktop](assets/testing/Gallery.JPG)
- [Gallery page on an iphone](assets/testing/Gallery_iphone_X.JPG)
- During the Githup deployment it was observed that the images did not load.
- The alt did work as expected for the Gallery Images. To be Fixed.
- [Home page on an iphone](assets/testing/iphone_gallery_alt.JPG) 


Contact Us
- The Contact Us page looks ok on desktop.
- The Active page is highlighted.
- There is a slight misalignment to the right for the First Name box. To be Fixed.
- All form fields must be filled before a form is submit.
- A valid email address must be entered before a form is submit.
- The ful page scrolls up/down on an iphone.
- The solid line under the menu does not remain fixed under the menu with scrolling. To be Fixed.
- [Contact Us page on a Desktop](assets/testing/Contact_Us.JPG)
- [Contact Us page on an iphone](assets/testing/Contact_iphone_X.JPG)
- [Completed Form Acknowledgement](assets/testing/Form.JPG)


The code was also configured for 1396px screens. These images are not detailed above.
The code works ok with the exception of the "To be Fixed" items as detailed.


## UX Testing


The site's users are gym members and potential members, who want to know more about the gym and its procedures.
- This requirement has been addressed with a clear easily found timetable.
- A Contact Us section also allows for any additional queries.


The gym is interested in attracting and retaining members.
- The sites classes time table attracts and retains members.
- New members will see the wide range of classes available.
- Existing members will be happy finding the classes in an efficient manner and not get dissatisfied with the Gym.
- The gallery section attracts new members as does the map with the location of the Gym.


As a Gym user 99% of the time I just want to know what time the classes were on and which classes are available.
- The Classes section is very easy to find.


As a Gym provider the gallery section provides welcoming images of the Gym.
- the gallery has some good images of the Gym.


The website promotes the image of a professional well run Gym.
- An efficient and non fussy website will attract new menbers who would otherwise timeout trying to navigate a complicated website.


The Contact Us section allows users to contact the gym as regards membership or class availability.
- The Contact Us Section makes sure that users complete all fields before submission enabling good customer communication and Gym feedback.



## Code Validation results.

- [style.css](assets/code_validation/W3C_CSS_Validator_results_for_style_css_CSS_level_3_+_SVG.pdf)
- [index.html](assets/code_validation/Showing_results_for_uploaded_file_index_html_Nu_Html_Checker.pdf)
- [classes.html](assets/code_validation/Showing_results_for_uploaded_file_classes_html_Nu_Html_Checker.pdf)
- [gallery.html](assets/code_validation/Showing_results_for_uploaded_file_gallery_html_Nu_Html_Checker.pdf) No need for a heading on a gallery page.
- [contact.html](assets/code_validation/Showing_results_for_uploaded_file_contact_html_Nu_Html_Checker.pdf)



## Deployment

During deployment the web page would not open. The images were changed to all lower case to fix this.
When the Gym Website did open the images would not load.
The path to the images in both Gitpod and Github have been changed to point to use the full Gitpod URL so that and additional README changes etc. will not break Githup.


[Deployed Project](https://fene20.github.io/gym-website/index.html)


## Credits

### Content

### Media
- The photos used in this site were obtained from https://stock.adobe.com/ie/


### Acknowledgements

- Inspiration for this project was received from https://planethealthlimerick.ie/ .
- The format of the planet health limerick site has some similarities to Code Institute Student Mini Project with Bootstrap 4.
- The format of this README file came from the Code Institute.
- The template for this project is the Code Institute student template for Gitpod.
- The correct menu left to right order on both desktop and iphone X can from https://stackoverflow.com/
- The Gallery page was 100% copy and paste from Code Institute Love Running Lesson.
- The hero image alt text solution came from https://www.davidmacd.com/blog/alternate-text-for-css-background-images.html
- Excellence Ilesanmi provided mentor support and feedback on the Gym Website pages.


### Challenges



index.html
- Lato font weight of 300 seemed difficult to see on the desktop.
- Looks better darkened with font weight of 500 but then cannot go darker with a hover.
- The underscore is used to highlight the active page so experimenting with not using this feature twice by using for hover too.
- Changing font to bold worked ok with a 300 font weight but with a font weight of 500 the letters got bigger and moved the menu items 
on the left of the hover even more left.
- Tried increasing the letter spacing to fix this menu "wobble" but this did not work.
- Using h6 made the text clear but bold did not highlight a hover.
- Changing colour to red works ok.


Menu Bar and Contact sections.
- Contact section div's were moving up between icon and menu items.
- Tried inline on every element in both menu bar and contact section.
- Fixed with a clear of both previous floats.


Contact sections
- Right section was below other two.
- use contact-sections > div{ display: inline-block; } to fix. As used by Blue and Orange boxes during lessons.


Blank Line
- Was expecting "h3" to give a blank line of text with a carriage return.
- Block element "p" also did not give a blank line with a carriage return.
- Blank space is ignored by HTML. White text on a white background seems too complicated.
- Coders Coffeehouse lesson used "br" which was a carriage return in the middle of an address.


Gap
- Gap between middle and right contact sections. Inspecting code did not highlight any stray padding.
- Gap was due to 1% left over from giving 33% to each of the three sections.
- Changed mid section to 34% wide.


Facebook and Instagram Icons
- Facebook and Instagram Icons not visible on the right of the screen.
- Contact section background set to Red, Green and Orange during page development.
- Body set to left and right 10px margin.
- Footer is inside body.
- Footer had margin on left but none on right.
- Looking at Google Inspect Element.
- The footer was starting on the left but was overflowing to the right.
- The footer left section was also to the right, i.e. not aligning with the contact details section above.
- The footer sections seemed to getting set as a percentage of the full page width not the page width less the margins.
- Changed left and right body margin to 1%.
- Changed footer width to 98%.
- This is a workaround. With more time this can be debugged more.
- Later on the body margins were removed so that the footer background could be the full width of the page.
- In hindsight this probably ties in with "Margins" below.


Note
- The Home page has "just" a hero image in the center.
- The Contact page had 3 sections across the page, the same as the footer.
- This is why the contact page (labelled as index.html) was debugged first.


Social Media Icons
- The social media icons in the footer were appearing above the footer.
- The footer has two sections top and bottom.
- The "window" was being applied to the top section only.
- The fix was to set the bottom section fixed to the bottom and the top section set relative to it.   


Menu items
- When floating the menu items to the left they appear in reverse order with home on the bottom.
- This is due to the previous workaround where they are listed in reverse order in the HTML.
- Google search gives:
- Float:right reverses order of spans - Stack Overflowstackoverflow.com › questions › floatright-reverses-ord...
- 16 answers
- 28 Mar 2012 — The general solution to this problem is either to reverse the order of the right floated elements in the HTML, or wrap them in a containing element and float that to the right instead. Yes, this can be done with your exact markup.
- Use solution of wrapping in a containing element.
- Menu list items are no longer floeted to the right.
- Menu items are inside menu id which is now floated to the right.


Classes Table
- Went down multiple avenues until the classes table was styled.
- It needs the headings at the top and side to be highlighted.
- It also needs a box around the table.
- A major challenge was getting the column widths to work out as intended.
- The solution was to make sure that all the columns had the same styles when inspected on a mobile device.
- Viewing the collapsed columns with red text supported the debug.
- But in the end a Bootstrap solutipn was used.


Header Height
- Could not get header height to auto scale with its contents.
- Used fixed heights instead.


Footer Icons
- Took a good hour to display the icons on their own with respect to the correct background.
- The Off white icon had an off white bar on the top and the bottom.
- Used google inspect to figure out that the icon had the correct background but that the anchor was off white.
- It was a challenge to target the anchor with CSS.
- For debug the icon was removed and replaced with text.
- A simple specificity seemed to work best (#social-media a {background-color: #555555; }) and (#social-media a {text-decoration: none; }) 
- With off white background the font awesome Icons were put back into the HTML.


Margins
- Set the header and footer heights to fit the height of their contents.
- One would expect containers to contain what they are wrapping with an auto command or something like that and not default to a zero height.
- Increasing the padding on the contact form for e.g. first name makes the container bigger.
- One would expect padding to squeeze the contents of a container and not to make the container bigger.
- But adding up the #message width of 88% with two paddings of 3% each with two margins of 3% each works out = 100%.

Alt text
- It was a challenge to include the Hero Image as a background with the URL listed in the HTML not CSS.
- This was needed to support "alt" text as is done with the gallery images.
- A solution was found online.
- [blog](https://www.davidmacd.com/blog/alternate-text-for-css-background-images.html)


Classes table
- Added bootstrap before local styling in classes page but header and footer styling were adjusted on the classes page w.r.t. other pages.
- Used Google inspect on header.
- Added fontweight of 600 to h2 to force h2 fontweight.
- Used Google inspect on footer.
- index.html footer is 105px high whereas classes.html footer is 65px high.
- Footer was set to 85px in CSS.
- 85px + 10px + 10px = 105px in index.html page.
- 85px - 10px - 10px = 65px in classes.html page.
- Did not find the cause.
- Put bootstrap on every html page.
- I guess the learning is to add boorstrap earlier in the development.


Menu wobble
- The Menu wobbles a little when going through the menu.
- Home and Gallery have a scroll bar.
- Classes and Contact Us do not.
- So changing from a page with a scroll bar to one without is causing the menu wobble.


Correct commits
- Some commits did not update the repository correctly.
- It took until the last day to figure this out.
- There can be more than one terminal open in Gitpod.
- Commits from sub folder terminals e.g. the css folder does not add all files - as expected.
- Commits from gitpod/workspace/gym-website do update all sub folders and files.


### Revision history
Commit Messages as detailed below.



Initial commit
- 9th February 2021
- Created GitHub project from Code Institute template.
- Copied (in GitHub) this README file from Code Institute Example README.md template.
- Opened GitHub project in GitPod.
- Started README Acknowledgements.
- Created project folder structure with index.html and style.css files.


Add Wireframes
- 14th February 2021
- Created Wireframes with Balsamiq Wireframes.
- Added to wireframes directory in assets directory.
- Updated README UX section.


Add index.html Menu
- 17th February 2021
 - Added menu items.
 - Added footer items.


Start Middle section
- 20th February 2021
- Mid section of home (hero image) and contact us (contact left, middle and right) both added to index.html.
- Hero image section is commented out when contact us is being worked on etc.
- Supports working on one HTML file until the very end when index.html will be saved as other html files.
- Insert temporary hero image from Love Running lesson.
- Started Contact section.


Start Contact section
- 22nd February 2021
- Add contact details on L.H.S.
- Add map in middle.
- Add form on R.H.S. Needs to be styled.


Start Footer Section
- 22nd February 2021
- Move map section to the right. This supports one background image behind contact details and contact form if needed.
- Align Footer with Contact section above.


Start classes.html
- 24nd February 2021
- Styling of index.html with contact.html code nearly completed.
- Started timetable in classes.html.


Add Classes Table
- 24nd February 2021
- Added table for classes.


Style Mods
- 26th February 2021
- Added border under header.
- Reduced height of Icon and GYM WEBSITE for Iphone X.
- Moved social media icons from fourth div to right of 3rd div.
- Removed off white icon background.


Configure Pages
 - 28th February 2021
 - Completed index.html page.
 - Copied index.html to contact.html. Note that the index.html page has been used to debug the "Contact Us" page.
 - Setup index.html as landing page with hero image.
 - Copied index.html for gallery.html and classes.html.
 - Changed classes page to use bootstrap table.
 - Added images to images folder.
 - Tweaked Gym Website look and feel based on tutor feedback.


Updated Readme
- 28th February 2021
- Updated Readme


Updated Readme 2
- 28th February 2021
- Updated Readme to include a validation file and see what it looks like in Github.


Updated Readme 3
- 28th February 2021
- Updated Readme to include a reformatted validation file and see what it looks like in Github.


Updated Readme 4
- 28th February 2021
- Readme Work In Progress.


Updated Readme 5
- 28th February 2021
- Add test images.


Updated Readme 6
- 28th February 2021
- Add last 2 test images again


Updated Readme 7
- 28th February 2021
- Added testing updates.


Updated Readme 8
- 28th February 2021
- Added UX testing updates.


Rename images
- 28th February 2021
- Changed images to all lower case.
- Updates style.css for Hero Image and gallery.html for gallery images.


Debug image path for Github
- 28th February 2021
- add ./assets etc.


Debug image path for Github 2
- 28th February 2021
- debug paths


Debug paths
- 28th February 2021
- adding full html path


Debug paths 2
- 28th February 2021
- adding full html path to hero image


Update README Deployment
- 28th February 2021
- Updated readme.


Add deployed project link
- 28th February 2021
- Add link to deployed project


Change lang
- 28th February 2021
- Changed lang="en-US"


Add submitted Form Image
- 28th February 2021
- Add submitted Form Image