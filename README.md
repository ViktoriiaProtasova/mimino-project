# teams-project-17
Task:

Develop a multi-page website for the company "Mimino".

The layout is responsive, except for mobile devices. Breakpoints:
- mobile: fluid layout, becomes responsive at 375px;
- tablet: 768px;
- desktop: 1440px

Ensure valid markup (https://validator.w3.org/, https://validator.w3.org/unicorn/).

Maintain semantic structure according to HTML5 standards.

Include font-face for font integration.

Optimize vector and raster graphics sizes.

Ensure support for displaying images on retina screens.

Optimize image loading.

Add a favicon display for the page.

Project Structure:

Main Page
Header (common for all pages)
Hero
About a complex
Restaurant’s details
Welcome to a complex
Hotel’s details
Location & contacts

Footer (common for all pages)

Restaurant Page
Hero
About a kitchen
Restaurant menu

Hotel Page
Hero
Double Luxury Room
Triple Room
Four-seater Room

Room Page
Hero
Amenities

Book a Room Modal window
Book a Table Modal window
Prices per Room Modal window

Main Page
Header
The header contains navigation, logo, and a list of social media links (in tablet and desktop versions).
The company's logo (name) is implemented as a link that returns the user to the Main Page.
Navigation should be implemented as a list of elements, each containing a link to the corresponding page.
Social media links should open the respective third-party resource in a separate tab.
The navigation menu on mobile and tablet versions is displayed as a sliding side panel. The menu is fixed and its height matches the viewport height. The menu includes links that lead to the respective pages.

Hero
"Mimino" - page title.
The "Book a table" button should open the Book a Table Modal window.
The "Book a room" button should open the Book a Room Modal window.

About a complex
The section has no visible title. It should have a hidden title for crawlers.
"Restaurant-hotel complex" and "Business class hotel" are subheadings.
The section includes images of the complex, which should be implemented as content.

Restaurant's details
"Restaurant" - section title.
The section includes a slider with content images of the restaurant.
The "Book a table" button should open the Book a Table Modal window.
The "View the menu" button should be implemented as a link that leads the user to the Restaurant Page.

Welcome to a complex
"Welcome to the epitome of luxury and comfort" - section title.
The section includes an image of the complex, which should be implemented as content.

Hotel's details
"Hotel" - section title.
The "Book a room" button should open the Book a Room Modal window.
The "View rooms" button should be implemented as a link that leads the user to the Hotel Page.

Location & contacts
"Location" - section title.
Includes a list of contact phone numbers for feedback and the address with a content image of the map.

Footer
The company's logo (name) should be implemented as a link that returns the user to the Main Page.
Links from the list should lead to the respective pages.
Social media links should open the respective third-party resource in a separate tab.

Restaurant Page
Hero
"Restaurant" - page title.
The "Book a table" button should open the Book a Table Modal window.
The "View a menu" button should be implemented as an anchor link that leads to the respective section of the page.
The section includes a slider with content images of the restaurant.

About a kitchen
The section has no visible title. It should have a hidden title for crawlers.
The section includes images of food preparation, which should be implemented as content.

Restaurant menu
"Restaurant menu" - section title.
The restaurant menu content should be implemented using the <ul> tag as a list of elements, including sub-items.
The "Book a Table" button should open the Book a Table Modal window.

Hotel Page
Hero
"Hotel" - page title.
The "Book a Room" button should open the Book a Room Modal window.
The "View prices" button should open the Prices per Room Modal window.
The section includes a slider with content images of the hotel.

Double Luxury Room
"Double Luxury Room" - section title.
The section includes images of the hotel room, which should be implemented as content.
The "More details" button should be implemented as a link that leads the user to the Room Page.
The "View prices" button should open the Prices per Room Modal window.

Triple Room
"Triple Room" - section title.
The section includes images of the hotel room, which should be implemented as content.
The "More details" button should be implemented as a link that leads the user to the Room Page.
The "View prices" button should open the Prices per Room Modal window.

Four-seater Room
"Four-seater Room" - section title.
The section includes images of the hotel room, which should be implemented as content.
The "More details" button should be implemented as a link that leads the user to the Room Page.
The "View prices" button should open the Prices per Room Modal window.

Room Page
Hero
"Double Luxury Room" - page title.
The section includes a slider with content images.
The "View prices" button should open the Prices per Room Modal window.

Amenities
The section has no visible title. It should have a hidden title for crawlers.
The hotel room amenities should be categorized and implemented using the <ul> tag as a list of elements, including sub-items.
The "Book a Room" button should open the Prices per Room Modal window.

Book a Room Modal window
"Book a Room" - section title.
The room booking form includes elements such as <input> and <select> (for which minimal data validation should be added using the pattern attribute), and a "Make a reservation" button. The up/down arrows for <select> should be implemented as pseudo-elements.
The "Make a reservation" button with the submit type should close the modal window.

Book a Table Modal window
"Book a Table" - section title.
The table reservation form includes elements such as <input> and <select> (for which minimal data validation should be added using the pattern attribute), and a "Make a reservation" button. 
The "Make a reservation" button with the submit type should close the modal window.

Prices per Room Modal window
"Prices per Room" - section title.
The form includes elements such as <input> and <select> (for which minimal data validation should be added using the pattern attribute), and a "Make a reservation" button. 
The "Make a reservation" button with the submit type should close the modal window.

*The presence of sliders is NOT MANDATORY and can be implemented by the team if desired and time permits.
