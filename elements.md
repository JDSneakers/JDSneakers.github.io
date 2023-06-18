---
layout: page
title: Software Design and Engineering
image: assets/images/softwaredesign.jpg
nav-menu: true
---

<!-- Main -->
<div id="main" class="alt">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h1>Software Design and Engineering Narrative</h1>
		</header>

<!-- Content -->
<h2 id="content">Describe the Artifact</h2>
<p>The artifact I chose for the software design and engineering part is an Android inventory management app. It requires the user to create a login that allows them to access the inventory app. Once logged in the user has multiple categories in which they can store various inventory items. The app allows the user to create, edit, and delete categories and items once inside each category. I initially created it in my CS-360 course in October of 2022.</p>
<ul class="actions">
	<li><a href="https://github.com/JDSneakers/Android_Inventory_App_NewVersion" class="button special icon fa-github">See Code</a></li>
</ul>
<div class="row">
	<div class="6u 12u$(small)">
		<h3>Justify the Inclusion</h3>
		<p>The reason I chose this artifact to include in my ePortfolio is it demonstrates three skills, my ability to develop an Android app, proficiency in Java as well as object-oriented programming, and my ability to code using XML. Through these three key skills, I also can demonstrate my ability to handle both frontend and backend development. I made many improvements to my original design to improve not only the overall functionality but to improve the overall aesthetic as well. As for aesthetics, I changed the category grid layout to have a span of three columns instead of two to increase the overall real estate available to display categories on a single page without the need for the user to have to scroll through categories while still keeping the logic to allow for the user to scroll through them if needed. I changed the background to have a more minimalistic look and added the background to all of the app layouts instead of just some of them to keep a cohesive design and feel for the app. I made text labels bold to increase visibility and make it easier to read. I changed the color palette used for the cards used to display the categories to better match the colors used in the app. I made a small adjustment to the overall layout bringing it up toward the top of the screen so that it looked more centered toward the top than centered on the whole screen. I also changed the logo to a more professional-looking design instead of the previous design which had a clip art look to it. As for the functionality, I created a separate registration page that the user can only access once when first setting up the app to prevent unauthorized access to the app as was possible with the previous design. I added key listeners to both the LoginActivity and NewUserActivity to prevent the user from creating a new line in the EditText fields when the user presses enter on the keyboard. I added checks to the SaveButtonClick to prevent the user from adding items without filling in all of the text fields. I added toasts to present to the user after they decide rather or not to approve SMS permissions displaying to them their choice in case they are unsure or accidentally choose the wrong choice. I also cleaned up some of the code that needed improvements such as in the CategoryActivity file line 65, where I opted to simplify an if-else statement by instead negating the original if statement parameters so that I could move the logic from the else statement into the if statement and removed the else statement altogether. I also removed functions and imports that were unused relating to the toggle visibility function that is no longer needed and an unused action bar import and function in the ItemEditActivity.</p>
	</div>
	<div class="6u$ 12u$(small)">
		<h3>Reflect on the Process</h3>
		<p>The biggest challenge I faced initially was getting reacquainted with the many aspects of the app, all of the files, and how they interact but after spending a bit of time working with it and reviewing some documentation I was up to full speed and able to pick up momentum to enhance the app. The biggest takeaway I learned from creating and improving the Andriod app was the importance of regular practice using the skills I have learned in my software and engineering degree makes a huge difference in my ability to pick up not only where I left off on an older project but how this will be key in my future career endeavors as I will face code that I did not develop and will have to catch up to speed with code I have not worked on before.</p>
	</div>
</div>
	</div>
</section>
</div>
