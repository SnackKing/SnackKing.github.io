---
layout: post
title: AuxNet
show_tile: false
---

<div class="box alt">
		<div class="row uniform">
			<div class="4u"><span class="image fit"><img src="assets/images/auxnet_screenshot_1.jpg" alt="" /></span></div>
			<div class="4u"><span class="image fit"><img src="assets/images/auxnet_screenshot_2.jpg" alt="" /></span></div>
			<div class="4u$"><span class="image fit"><img src="assets/images/auxnet_screenshot_3.jpg" alt="" /></span></div>
		</div>
</div>
<section id="one">
		<div class="inner">
			<!-- Content -->
			<h2 id="content">Background</h2>
			<p>AuxNet was built at <a href = "https://hack.osu.edu/2018/"> HackOHI/O 2018</a>, the biggest annual hackathon in Ohio. If you aren't familiar with a hackathon, it is a coding competition where you and your team have about 24 hours (or sometimes more) to design and build some sort of usable project. For our project, we attempted JPMorgan Chase's Disaster Recovery challenge. In particular, we wanted to focus on an application that would be useful in conditions where network connections would be unstable </p>
			<p>AuxNet uses a technology called "mesh networking", which is a sort of ad-hoc wireless network that uses the individual devices on the network as nodes. The data is sent between devices using bluetooth, which does not require internet. The data is broadcasted through the mesh, allowing data to be exchanged over practical distances. The app itself allows you to send messages to anyone else that is currently on the network. Furthermore, we implemented database synchronization between the local and cloud databases, so anyone can get all of the data that has been sent. This is theoretically highly useful for first responders who would use the application to get a better idea of where people are located in the event of a disaster. </p>
		</div>
			<div class="inner">
			<h2>The Team</h2>
		</div>
		<ul class="actions">
					<li><a href="https://www.linkedin.com/in/zachary-allegretti-37ba18154/" class="button special" style = "margin: 1em">Zach Allegretti</a></li>
					<li><a href="https://www.linkedin.com/in/joseph-forsman-5a73a6148/" class="button special" style = "margin: 1em">Joe Forsman</a></li>
					<li><a href="#" class="button special" style="pointer-events: none;" style = "margin: 1em; pointer-events: none;">Sahil Khatri</a></li>
					<li><a href="https://www.linkedin.com/in/jackplank/" class="button special" style = "margin: 1em">Jack Plank</a></li>
		</ul>
</section>
<section class = "spotlights">
		<section>
			<div class = "inner" style = "padding: 1em">
				<h2>Technology Used</h2>
				<ul>
					<li>Android Studio</li>
					<li>Bridgefy</li>
					<li>SQLite</li>
					<li>Firebase</li>
				</ul>
			</div>
		</section>
</section>
<div class="6u$ 12u$(medium)" style="margin: 0 auto;">
	<div class="box alt" style="padding-top: 1em;">
		<div class="row 50% uniform" style="width: auto;margin: 0 auto">
			<div class="3u"><span class="image fit" style="padding-right: 1em"><img src="assets/images/androidstudio.svg" alt="" /></span></div>
			<div class="4u"><span class="image fit" style="padding-right: 1em"><img src="assets/images/Bridgefy.svg" alt="" /></span></div>
			<div class="3u"><span class="image fit" style="padding-right: 1em"><img src="assets/images/SQLite.svg" alt="" /></span></div>
			<div class="2u$"><span class="image fit"><img src="assets/images/firebase2.svg" alt="" /></span></div>
		</div>
	</div>
</div>
<section>
		<div class = "inner">
			<h2> Challenges </h2>
		<dl>
		<dt>Database Synchronization</dt>
			<dd>
				<p>Because we were operating with a global cloud database and a public database for each installation, we had to make sure that people on the network were actually receiving the correct data. To handle this, we needed to ensure that some level of database synchronization was achieved. This was further complicated by the fact that we couldn't trust our network connection, but fortunately for us Firebase had measures built in to make this easier on us.</p>
			</dd>
			<dt>SDK Issues</dt>
			<dd>
				<p>There are a few different libraries for mesh networking out there, and it felt like we tried them all. Eventually we settled on Bridgefy. Although it did technically work, we ran into a lot of bugs and crashes because of this SDK. Granted, we were very unfamiliar with how it works (and we still are), but we had to implement a lot of workarounds to get it working. This was easily one of the biggest time sinks for the project</p>
			</dd>
			<dt>Hackathon Environment</dt>
			<dd>
				<p>We only had 24 hours to put this whole project together, so naturally some of the design decisions were rushed. Furthermore, sleep deprivation eventually took its toll. By the time we got to hour 18, we were pretty wiped out and the bugs were not going away.</p>
			</dd>
		</dl>
		</div>
</section>
<section class = "spotlights">
		<section>
			<div class = "inner" style = "padding: 1em">
				<h2>Results</h2>
				<p>Despite the problems we had, we were still proud of the end product because its the technology behind it is actually unique. We had to give a presentation and demo to a few different sets of judges, who evaluated the app based on several criteria. To our surprise, we actually ended up placing 3rd for "Most Impactful". At an event with 667 hackers competing on various projects, we didn't think we would actually win anything. We had to go up on stage and give a short presentation on our project to a room full of people and receive our prize. At that point, we had been awake for about 30 hours.</p>
				<p>In Spring 2019 we received an invitation to show our product at ShowOHI/O 2019, which is a showcase event for the various projects and startups being built around OSU. Although we weren't interested in going anywhere with the project, it was still a great chance to network and show off what we built. </p>
			</div>
		</section>
</section>
<div class="6u$ 12u$(medium)" style="margin: 0 auto;">
	<div class="box alt" style="padding-top: 1em;">
		<div class = "12u$"> <span class="image fit"><img src="assets/images/hackteam.jpg" alt="" /></span></div>
	</div>
</div>
<p class = "small" style="text-align: center;">
				<i>The team after accepting our prizes at HackOHI/O 2018. <br/>From left to right: Sahil Khatri, Zach Allegretti, Joe Forsman. Not pictured: Jack Plank.</i>
</p>
<div class="6u$ 12u$(medium)" style="margin: 0 auto;">
	<div class="box alt" style="padding-top: 1em;">
		<div class = "12u$"> <span class="image fit"><img src="assets/images/showohio.jpg" alt="" /></span></div>
	</div>
</div>
<p class = "small" style="text-align: center;">
				<i>The team at our ShowOHI/O booth. <br/>From left to right: Joe Forsman, Zach Allegretti, Sahil Khatri. Not pictured: Jack Plank.</i>
</p>