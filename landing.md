---
title: Databases
layout: post
image: assets/images/databases.jpg
nav-menu: true
---

<!-- Main -->
<div id="main" class="alt">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h1>Databases Narrative</h1>
		</header>

<!-- Content -->
<h2 id="content">Describe the Artifact</h2>
<p>The artifact I chose to demonstrate my skills in databases is the inventory app from my CS-360 course that I completed at the end of October 2022. It is an inventory management system designed as an Android app that manages three databases within the app, the user database, the category database, and the item database. It allows users to have a secure way to access and manage a database intuitively on a mobile device.</p>
<ul class="actions">
	<li><a href="https://github.com/JDSneakers/Android_Inventory_App_NewVersion/blob/master/app/src/main/java/com/zybooks/johnaustininventoryapp/InventoryDatabase.java" class="button special icon fa-github">See Code</a></li>
</ul>
<div class="row">
	<div class="6u 12u$(small)">
		<h3>Justify the Inclusion</h3>
		<p>I selected the Inventory Management Android app to showcase my skills in databases because it shows my ability to work with multiple SQL databases at once at both low-level CRUD operations to more complex aggregation functions. It also demonstrates my ability to work with dynamically changing data in a secure and manageable way. I made several changes to improve the code from both a functional and security standpoint. First I implemented unused code in the getCategories method switch by implementing an option for the user to call any of its cases in the CategoryActivity page of the app via a drop-down menu to sort the categories. I removed an unnecessary semicolon on line 19. I also closed the cursors after use in each method that used them. The most important of all the changes I made though was to encrypt the user passwords using the bcrypt library to hash the user password before storing it in the database instead of as plain text as was done previously. This meant I had to implement the hashing of the password in the addUser method and verify the user input in comparison to the hashed password in the grantUserLogin method using the bcrypt library.</p>
	</div>
	<div class="6u$ 12u$(small)">
		<h3>Reflect on the Process</h3>
		<p>Through the planned enhancements of the Inventory Management app, I learned many valuable skills in problem-solving, security, and working with pre-existing libraries. The most challenging aspect of the enhancement was implementing the bcrypt library as it had limited documentation and was difficult to figure out how to integrate with the artifact. From this though I learned a lot about adding pre-existing libraries from GitHub into a project that I am working on. I learned about the importance of password hashing and how even though a person might not be able to exploit a SQL injection on the database, storing sensitive data such as user passwords as plain text in a database is bad practice and risks exploitation from malicious actors. I learned to problem solve and the importance of thorough documentation as I was on the receiving end of poor documentation and had to do a lot of research that also was not an easy task as would have been either better documentation, clearer comments, or a step-by-step guide on how to use the library and many of the resources I found were only partially useful or did not fit the scenario in how I was trying to use it. I was able to work my way through it regardless and problem-solve the situation so that I was able to implement the solution despite these issues.</p>
	</div>
</div>
	</div>
</section>
</div>