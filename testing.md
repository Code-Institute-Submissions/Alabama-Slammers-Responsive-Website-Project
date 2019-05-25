#Alabama-Slammers Testing

<a href="">Main ReadMe.md File</a>
<a href="">Alabama Slammers page</a>

#Automated Testing

<ul>
	<li><a href="https://validator.w3.org/">W3C Markup Validation</a> was used to test HTML code.</li>
	<li><a href="https://jigsaw.w3.org/css-validator/">W3C CSS Validation</a> was used to test CSS code.</li>
</ul>

#Client stories testing

Most common path through the website:

Home > About > Media(which allows user to choose to visit images, videos or music) > Tour > Contact
Some pages offer few different possible paths in their call to action buttons:

From Home > Videos
From About > Photos OR Videos to Music

#Testing client stories from UX section of README.md

<ol>
	<li>As an old fan of the band, I want to be able to access tour dates and see the newest gigs first, I want an easy access to buy tickets fast, I also want to be updated about any news regarding the band via email. <ul>
		<li>Separate pages created specifically for booking tickets purposes so a user that arrived with a purpose to check out gigs and purchase tickets can go directly to the place created for this purpose</li>
		<li>Users are encouraged to sign up for the newsletter on the landing page</li>
	</ul></li>
	<li>As a new fan I want to be able to learn more about the band and check out media I haven't seen, heard before and purchase a CD.<ul>
		<li>User can access information of the band in the About page which is displayed in the navigation</li>
		<li>While on the about page user can use call to action buttons to acess video and photo galleries without using navigatio</li>
		<li>User can easily purcase CD as it is one of the first things offered on the landing page as well as they are able to do it on the Music page</li>
	</ul></li>
	<li>As the writter for a music blog I would like to feature a band there fore I need to find a correct person to contact for this purpose.<ul>
		<li>User can access contact forms through Contact page where they are given a choice for two different contact reasons. For this reason user should fill in the form with title "Publicist"</li>
	</ul></li>
	<li>As a person who is organising a wedding party I need to know who is a right person to contact in order tohire this band. <ul>
		<li>User can access contact forms through Contact page where they are given a choice for two different contact reasons. For this reason user should fill in the form with title "Booking Agent"</li>
	</ul></li>
</ol>

#Manual Testing

<h2>Home Page</h2>

Navigation menu

<ul>
	<li>Change the screen size from desktop to tablet and then to mobile  to verify that the navigation bar is responsive and switches from inline to an inline with logo on top and finally to burger icon dropdown menu.</li>
	<li>When resizing navbar checking that all navigation items stay the same and there are no positioning descrepencies.</li>
	<li>Check that drop-down menu from Media navigation item is active in all screen sizes and it's positioning remains unchanged.</li>
	<li>Click on the logo in the navigation bar and verify that it links to the home page.</li>
	<li>Click on each navigation menu item from different pages and verify that they link to the correct pages.</li>
	<li>Hover over all navigatio items to check that they change colour as expected.</li>
	<li>Hover over items on Media drop-down menu to check that they change colour</li>
	<li>Click on Media drop-down items from all the pages to make sure they link to the correct pages.</li>
	<li>Change screen size to small and click burger icon, verify that the menu drops down.</li>
	<li>Repeat verification of functionality and responsiveness on mobile phone and tablet.</li>
</ul>

Hero image (Logo)

<ul>
	<li>Check that Hero image is visable on all the devices</li>
	<li>resize and check that image scales nicely without affecting layout of the page and positioning of other items</li>
</ul>

Hero image (Band members)

<ul>
	<li>Check that Hero image is visable on desktop and resize to make sure it dissapears on mobile devices</li>
	<li>resize image within desktop scale and make sure it resizes without affecting layout of the page and positioning of other items</li>
</ul>

Home Page Video

<ul>
	<li>Resize and check that video is always aligned in the center</li>
	<li>play Video on different devices making sure it works</li>
	<li>Hover over the call to action button under the video to make sure it changes colour</li>
	<li>Click the call to action button under the video to make sure it redirects to correct page</li>
</ul>


Album and buy CD

<ul>
	<li>resze screen and make sure it remains unchanges through the scaling </li>
	<li>Hover over the call to action button under the video to make sure it changes colour</li>
	<li>Click the call to action button under the video to make sure it redirects to external website where user can make a purchase</li>
</ul>

Mailing list form

<ul>
	<li>Scale and make sure form resizes nicelly on all devices</li>
	<li>Press Subscribe button without entering email to make sure it requires it</li>
	<li>Submit the form with entering email</li>
</ul>

Footer

<ul>
	<li>Click on each social media icon to confirm it opens a separate tab for it's link.</li>
	<li>Resize to verify that the footer is responsive and that on mobile devices only 3 social media icons are displayed while on the bigger screens 5 are visable </li>
</ul>


<h2>About Page</h2>

Navigation menu

<ul>
	<li>Repeat verification steps done for navbar on Home page.</li>
	<li>Check if navbar code is same on all html pages.</li>
</ul>

Hero image

<ul>
	<li>Resize to verify that the hero image changes to different design for mobile devices and is not affecting layout of the page</li>
</ul>

Image under the coopy

<ul>
	<li>resize and make sure image is only visable on the desktop view</li>
</ul>

Page content

<ul>
	<li>Resize to make sure that text and background image scales as expected and looks good on all devices</li>
</ul>

Call to action buttons


<ul>
	<li>Hover over each call to action button and check the colour changes.</li>
	<li>Click each call to action button and verify that it links to its relevant correct page.</li>
	<li>Resize to check if call to action buttons spacing responds as expected.</li>
</ul>


Footer

<ul>
	<li>Repeat verification steps done for footer on Home page.</li>
	<li>Check if footer code is same on all html pages.</li>
</ul>


<h2>Media</h2>

<ul>
	<li>Hover over Media on the navigation and make sure drop down shows</li>
	<li>Resize to mobile devices and make sure that Media drop down shows and is positioned apropriatelly on all the screen sizes</li>
	<li>Hover over Media drop-down items and make sure colour changes</li>
	<li>Press each link on Media drop-down list to make sure it redirects to appropriate page</li>
</ul>

#Pictures

Page content

<ul>
	<li>Resize screen and make sure that images scale nicelly from 4 to 2 and to 1 columns depending on screen size</li>
	<li>Hover over each image and make sure that cursor is pointer and image is overlayed with a colour with opacity</li>
	<li>Click on each image to make sure that it enlarges to 100% once clicked</li>
</ul>

Footer

<ul>
	<li>Scroll down the page to make sure that footer is sticky but otherwise identical to the rest of the website</li>
</ul>


<h2>Videos</h2>

Page content

<ul>
	<li>Resize screen and make sure that images scale nicelly from 4 to 2 and to 1 columns depending on screen size</li>
	<li>Click on each video to make sure it works</li>
</ul>

Footer

<ul>
	<li>Scroll down the page to make sure that footer is sticky but otherwise identical to the rest of the website</li>
</ul>

<h2>Music</h2>

<ul>
	<li>Scale and make sure that positioning of the CD image and music player changes from inline to block for mobile devices and that call to action button dissapears on mobile devices</li>
	<li>Hover over call to action button to make sure it changes colour</li>
	<li>Click on to call to action button to make sure it redirects to the external website where user is able to purchase a CD</li>
</ul>


<h2>Tour</h2>

<ul>
	<li>resize and make sure that while the boxes of content remain stacked on top of each other text changes from inline to block for mobile devices</li>
	<li>Press call to action buttons to make sure it opens a new tab with a website where user is able to purchase event tickets</li>
</ul>


<h2>Contact page</h2>

<ul>
	<li>Resize to make sure that forms align the way expected and design remins unchanged</li>
	<li>Hover over "Send" buttons to make sure they change colour the way expected</li>
	<li>Try submitting the form without entering name and/or email and make sure it is requested</li>
	<li>Try submitting the form</li>
</ul>


#Further Testing

<ul>
	<li>Friends and family were asked to check the website on all devices they had and provide opinion on design and functionality</li>
</ul>


