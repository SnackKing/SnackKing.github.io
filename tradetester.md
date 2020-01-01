---
layout: post
title: TradeTester
show_tile: false
---

<div class="box alt">
		<div class="row uniform">
			<div class="4u"><span class="image fit"><img src="assets/images/tradetester_mobile_screenshot_1.jpg" alt="" /></span></div>
			<div class="4u"><span class="image fit"><img src="assets/images/tradetester_web_dark.png" alt="" /></span></div>
			<div class="4u$"><span class="image fit"><img src="assets/images/tradetester_web_dark_home.png" alt="" /></span></div>
		</div>
</div>

<section id="one">
		<div class="inner">
			<!-- Content -->
			<h2 id="content">Background</h2>
			<p>After I graduated from OSU in 2019, I had a few months before I could start, so I decided to build something bigger than anything I had done in the past. My main goal was to utilize my experience with firebase to develop something cross-platform between mobile and web. ALthough I was working with a lot of familiar technologies, I still wanted to learn something new in the process, so I decided to learn a new web framework. I also wanted to work with a variety of different APIs to make the app seem as realistic as possible.  </p>

            <p>I drew a lot of inspiration from Robinhood when I was designing the UX for this application. I loved the clean, modern style as well as the after-hours dark mode feature (which I even incorporated into TradeTester for web). Partway through the development process, I decided to pivot the focus towards education by adding a teachers dashboard. </p>
		</div>
</section>

<section class = "spotlights">
    <section>
        <div class = "inner" style = "padding: 1em">
            <h2>Technology Used</h2>
            <ul>
                <li>Android Studio</li>
                <li>Firebase</li>
                <li>Django</li>
                <li>Heroku</li>
            </ul>
        </div>
    </section>
</section>

<div class="6u$ 12u$(medium)" style="margin: 0 auto;">
	<div class="box alt" style="padding-top: 1em;">
		<div class="row 50% uniform" style="width: auto;margin: 0 auto">
			<div class="3u"><span class="image fit" style="padding-right: 1em"><img src="assets/images/androidstudio.svg" alt="" /></span></div>
			<div class="3u"><span class="image fit" style="padding-right: 1em"><img src="assets/images/django.svg" alt="" /></span></div>
			<div class="3u"><span class="image fit" style="padding-right: 1em"><img src="assets/images/firebase2.svg" alt="" /></span></div>
			<div class="3u$"><span class="image fit"><img src="assets/images/heroku.svg" alt="" /></span></div>
		</div>
	</div>
</div>

<section>
		<div class = "inner">
			<h2> Challenges </h2>
		<dl>
		<dt>Learning Python and Django</dt>
			<dd>
				<p>There is always a technical barrier to overcome when learning a new language. There is an even bigger barrier when learning a new web framework in the process. It took me a while to get used to the framework, but fortunately there are a lot of great online resources for learning Django. I used a video series on YouTube, which can be found <a href="https://www.youtube.com/watch?v=UmljXZIypDc&list=PL-osiE80TeTtoQCKZ03TU5fNfx2UY6U4p">Here</a> . </p>
			</dd>
			<dt>Database Cross Compatibility</dt>
			<dd>
				<p>By utilizing Firebase's web and mobile compatibility, I was able to make the mobile and web applications completely compatible so users can log onto both platforms with the same account. Of course, this was no easy task. I used a Firebase wrapper called Pyrebase to make it easier to use Pyrebase on the web side.</p>
			</dd>
			<dt>Leveraging APIs</dt>
			<dd>
				<p>I utilized several APIs in order to acquire the realtime data that runs TradeTester. In order to acquire all of the data that is available to the user, I had to asynchronously pull from several different APIs in order to provide the comprehensive market data that makes TradeTester practical. I had to setup these API calls on both the Android and Django apps.</p>
			</dd>
		</dl>
		</div>
</section>

<section class = "spotlights">
		<section>
			<div class = "inner" style = "padding: 1em">
				<h2>Results</h2>
				<p>Both TradeTester web and TradeTester for Android are deployed and currently functional. The web app is hosted on Heroku and the Android app is available on Google Play.</p>
				<ul class="actions"> 
					<li><a href="http://tradetester.herokuapp.com/" class="button">Website</a></li>
					<li><a href="https://play.google.com/store/apps/details?id=com.zachary.alleg.tradetester&hl=us" class="button special">Download on Google Play</a></li>
				</ul>		
			</div>
		</section>
	</section>