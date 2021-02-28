# Gym Website

One or two paragraphs providing an overview of your project.

Essentially, this part is your sales pitch.
 
## UX
 
Use this section to provide insight into your UX process, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

In particular, as part of this section we recommend that you provide a list of User Stories, with the following general structure:
- As a user type, I want to perform an action, so that I can achieve a goal.

This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of the design process. These files should themselves either be included as a pdf file in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser.





[Home Page](assets/wireframes/gym_website_home.pdf)
    
This is the landing page with a hero image.
This page ontains the Menu items.
All pages including the home page wil  have a fixed header and footer.
The header will be setup in thirds. See Phone where the Gym Icon is followed by Home over Gallery and Classes over contact us.
See Desktop where the footer is also setup in thirds.
See Phone were the footer is shown in two rows. This may be changed to three rows depending on the font size.
The Icon wil contain the Name of the gym.
The name of the gym (not displayed in the wireframe) may also be included above the Menu bar so that the Desktop does not look too basic.



[Classes Page](assets/wireframes/gym_website_classes.pdf)

The classes page is the most important page for new and existing members.
This is the one page that will be used the most.
Classes can be pay as you go and free to members with certain membership packages.
The timetable on the Tablet will likely be a squeezed version of the Desktop timetable.
A squashed and wrapped Desktop timetable will not work on the Phone.
The Phone wireframe shows two Desktop columns, one for the Times and one for the Days of the week.
This however does not look well.
The Phone will need a format of it's owm with the Day of the week followed by columns with headings of Times and Classes.
Coding this will be a challenge and will likely require a library perhaps Bootstrap4.
The timetable will need to be scrolled up/down.
There is a gap in the footer where the table is visable.
The footer format will be coded to prevent this.



[Contact Page](assets/wireframes/gym_website_contact.pdf)

The Contact page has details of how to contact the gym, a map to help locate the gym and a contact for so that one can submit queries when one is e.g. at work.
Most new users will simply just need to ring or email the Gym or figure out where it is on the map.
Both existing and new members may wish to book a session with a particular instructor or enquire about the exercises in various casses etc.
The Phone Contact page is shown without the fixed footer.



[Gallery page](assets/wireframes/gym_website_gallery.pdf)

The Gallery page has images from the Gym to entice new mwmbers to join. These images may highlight particular equipment that the Gym has.
The Desktop may look nicer if the images were in thirds, i.e. three across instead of two as shown in the wireframe.


## Features

In this section, you should go over the different parts of your project, and describe each in a sentence or so.
 
### Existing Features
- Feature 1 - allows users X to achieve Y, by having them fill out Z
- ...

For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement
- Another feature idea

## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation.


- [Balsamiq Wireframes](https://balsamiq.com/wireframes/desktop/)
    - This project used **Balsamiq Wireframes** to generate the wireframes for this project.

- [Icons](https://fontawesome.com/)
    - This project used free **Fontawesome** icons.
    - The icons were, the child icon, facebook icon and instagram icon.

- [CSS-TRICKS](https://css-tricks.com/complete-guide-table-element)
    - This project used code from **CSS-TRICKS** to support debug by enabling a table border.
    - The border can not be used in the final render.





## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.


## Credits

### Content
- The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)

### Media
- The photos used in this site were obtained from ...

### Acknowledgements

- Inspiration for this project was received from https://planethealthlimerick.ie/ .
The format of the planet health limerick site has some similarities to Code Institute Student Mini Project with Bootstrap 4.
- The format of this README file came from the Code Institute.
- The template for this project is the Code Institute student template for Gitpod.
- The Gallery was 100% copy and paste from Code Institute Love Running Lesson.


### Revision history
Initial commit (commit message)
- 9th February 2021
- Created GitHub project from Code Institute template.
- Copied in GitHub this README file from Code Institute Example README.md template.
- Opened GitHub project in GitPod.
- Started README Acknowledgements.
- Created project folder structure with index.html and style.css files.

Add Wireframes (commit message)
- 14th February 2021
- Created Wireframes with Balsamiq Wireframes.
- Added to wireframes directory in assets directory.
- Updated README UX section.

Add index.html Menu (commit message)
- 17th February 2021
 - Added menu items.
 - Added footer items.

Start Middle section (commit message)
- 20th February 2021
- Mid section of home (hero image) and contact us (contact left, middle and right) both added to index.html.
- Hero image section is commented out when contact us is being worked on etc.
- Supports working on one HTML file until the very end when index.html will be saved as other html files.
- Insert temporary hero image from Love Running lesson.
- Started Contact section.

Start Contact section (commit message)
- 22nd February 2021
- Add contact details on L.H.S.
- Add map in middle.
- Add form on R.H.S. Needs to be styled.

Start Footer Section (commit message)
- 22nd February 2021
- Move map section to the right. This supports one background image behind contact details and contact form.
- Align Footer with Contact section above.

Start classes.html (commit message)
- 24nd February 2021
- Styling of index.html with contact.html code nearly completed.
- Started timetable in classes.html.

Add Classes Table (commit message)
- 24nd February 2021
- Added table for classes.

Style Mods
- 26th February 2021
- Added border under header.
- Reduced height of Icon and GYM WEBSITE for Iphone X.
- Moved social media icons from fourth div to right of 3rd div.
- Removed off white icon background.

Challenges

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
- Was expecting <h3> </h3> to give a blank line of text with a carriage return.
- Block element <p> </p> also did not give a blank line with a carriage return.
- Blank space is ignored by HTML. White text on a white background seems too complicated.
- Coders Coffeehouse lesson used <br> which was a carriage return in the middle of an address.

Gap
- Gap between middle and right sections. Inspecting code did not highlight any stray padding.
- Gap was due to 1% left over from giving 33% to each of the three sections.
- Changed mid section to 34% wide.

Facebook and Instagram Icons not visible on the right of the screen.
- Contact section background set to Red, Green and Orange during page development.
- Body set to left and right 10px margin.
- Footer is inside body.
- Footer had margin on left but none on right.
- Looking at Google Inspect Element.
- The footer was starting on the left but was overflowing to the right.
- The footer left section was also to the right of the contact details section above.
- The footer sections seemed to getting set as a percentage of the full page width not the page width less the margins.
- Changed left and right body margin to 1%.
- Changed footer width to 98%.
- This is a workaround. With more time this can be debugged more.
- Later on the body margins were removed so that the footer background could be the full width of the page.

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
- Vieving the collapsed columns with red text supported the debug.

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



TBD's
- Fix pdf links in MD above.
- fix fonts.
- Change icon?
- Fix reverse order menu so index.html does not need to be reversed.
- Add blank line.
- Remove underscore from Social media icons.







![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

Welcome fene20,

This is the Code Institute student template for Gitpod. We have preinstalled all of the tools you need to get started. You can safely delete this README.md file, or change it for your own project. Please do read it at least once, though! It contains some important information about Gitpod and the extensions we use.

## Gitpod Reminders

To run a frontend (HTML, CSS, Javascript only) application in Gitpod, in the terminal, type:

`python3 -m http.server`

A blue button should appear to click: *Make Public*,

Another blue button should appear to click: *Open Browser*.

To run a backend Python file, type `python3 app.py`, if your Python file is named `app.py` of course.

A blue button should appear to click: *Make Public*,

Another blue button should appear to click: *Open Browser*.

In Gitpod you have superuser security privileges by default. Therefore you do not need to use the `sudo` (superuser do) command in the bash terminal in any of the lessons.

## Updates Since The Instructional Video

We continually tweak and adjust this template to help give you the best experience. Here is the version history:

**October 21 2020:** Versions of the HTMLHint, Prettier, Bootstrap4 CDN and Auto Close extensions updated. The Python extension needs to stay the same version for now.

**October 08 2020:** Additional large Gitpod files (`core.mongo*` and `core.python*`) are now hidden in the Explorer, and have been added to the `.gitignore` by default.

**September 22 2020:** Gitpod occasionally creates large `core.Microsoft` files. These are now hidden in the Explorer. A `.gitignore` file has been created to make sure these files will not be committed, along with other common files.

**April 16 2020:** The template now automatically installs MySQL instead of relying on the Gitpod MySQL image. The message about a Python linter not being installed has been dealt with, and the set-up files are now hidden in the Gitpod file explorer.

**April 13 2020:** Added the _Prettier_ code beautifier extension instead of the code formatter built-in to Gitpod.

**February 2020:** The initialisation files now _do not_ auto-delete. They will remain in your project. You can safely ignore them. They just make sure that your workspace is configured correctly each time you open it. It will also prevent the Gitpod configuration popup from appearing.

**December 2019:** Added Eventyret's Bootstrap 4 extension. Type `!bscdn` in a HTML file to add the Bootstrap boilerplate. Check out the <a href="https://github.com/Eventyret/vscode-bcdn" target="_blank">README.md file at the official repo</a> for more options.

--------

Happy coding!
