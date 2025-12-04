---
layout: default
---
<ul class="skip-links">
	<li><a href="#form">Jump to Form</a></li>
</ul>

{% include masthead.html %} 
<section class="banner">
	<h1>
		Jobs 
	</h1>
	<h2>
		Inquire about hiring one of our fantastic, highly skilled & motivated Graphic Design students. 
	</h2>
</section>
<main role="main" class="jobs-main">
	<h3>
		Hire a Designer 
	</h3>
	<p>
		Students in the Graphic Design program undergo rigorous training in their field. They may even specialize in specific disciplines, such as branding, web development, publication design, user interface design, and more. <em>What we wish for our students is for them to find fulfilling employment in the industry and hope they’ll occasionally provide their services at no cost for the public good.</em> 
	</p>
	<div class="content-box">
		<div class="graphic-box">
			<img alt="" src="{{ site.baseurl }}/svg/ac-graphic-design.svg"> 
		</div>
		<div class="text-box">
			<h3>
				Algonquin Design 
			</h3>
			<p>
				<em>Learn more about Algonquin College’s Graphic Design program.</em> 
			</p>
			<p>
				See what problems our amazing students can help you solve and discover the wonderful things they can produce. 
			</p>
			<a href="/">Read more ➜</a> 
		</div>
	</div>
	<h3>
		Rates 
	</h3>
	<p>
		We’re confident you will find our students’ rates very affordable. In fact, they will be way below usual industry rates. What we want to avoid is having them work for no money, or too little money. <strong>If you’re looking for free graphic design services for a for-profit endeavour, please enquire elsewhere.</strong> 
	</p>
	<div class="content-box">
		<div class="graphic-box">
			<img alt="" src="{{ site.baseurl }}/svg/rgd-square.svg"> 
		</div>
		<div class="text-box">
			<h3>
				Spec Work 
			</h3>
			<p>
				<em>Learn what spec work is and why it’s harmful to our industry</em> 
			</p>
			<p>
				Our students will not work for free—except for non-profits that gives us warm, fuzzy feelings. 
			</p>
			<a href="https://www.rgd.ca/resources/no-spec">Read more ➜</a> 
		</div>
	</div>
	<h3 name="form">
		Submit a job 
	</h3>
	<p>
		Once you submit your information, we will vet it, then distribute it to our students. They will contact you directly, where you can evaluate and choose amongst them as you see fit. Negotiation of rates will be between you and the candidate. 
	</p>
	<p>
		If you do not receive any responses, it's possible their schedules are full. You may reach out to Alain Paradis to enquire. 
	</p>
		<form action="https://formsubmit.co/paradia@algonquincollege.com" method="POST" />
		<fieldset>
			<legend>Identification</legend> 
			<div>
				<label for="name">Name</label> 
				<input id="name" name="Name" required> 
			</div>
			<div>
				<label for="email">Email</label> 
				<input type="email" id="email" name="Email" required> 
			</div>
			<div>
				<label for="tel">Phone</label> 
				<input type="tel" id="tel" name="Phone" required> 
			</div>
			<div>
				<label for="org">Organization name <em>(Optional)</em></label> 
				<input id="org" name="Organization"> 
			</div>
			<div>
				<label for="addr">Address <em>(Optional)</em></label> 
				<input id="addr" name="Address"> 
			</div>
			<div>
				<label for="city">City <em>(Optional)</em></label> 
				<input id="city" name="City"> 
			</div>
			<div>
				<label for="type">You are a…</label> 
				<select id="type" name="Type" required>
					<option value=""></option>
					<option value="Individual">Individual</option>
					<option value="Design firm">Design firm</option>
					<option value="For profit company">For profit company</option>
					<option value="Registered charity">Registered charity</option>
					<option value="Non-profit or not-for-profit">Non-profit or not-for-profit</option>
					<option value="Other">Other</option>
				</select>
			</div>
			<div>
				<label for="seeking">You’re seeking a designer for…</label> 
				<select id="seeking" name="Seeking" required>
					<option value=""></option>
					<option value="A single job">A single job</option>
					<option value="A limited-time contract">A limited-time contract</option>
					<option value="Ongoing part-time work">Ongoing part-time work</option>
					<option value="A full-time position">A full-time position</option>
					<option value="Other">Other, describe below</option>
				</select>
			</div>
		</fieldset>
		<fieldset>
			<legend>Is the work paid?</legend> 
			<div>
				<input type="radio" id="work-paid-yes" name="Paid" value="Yes"> <label for="work-paid-yes">Paid</label> 
				<input type="radio" id="work-paid-no" name="Paid" value="No"> <label for="work-paid-no">Not paid</label> 
			</div>
		</fieldset>
		<fieldset>
			<legend>Description of the work needed</legend> 
			<p>
				(General graphic design, web design, branding, motion video, etc.) 
			</p>
			<textarea id="desc" name="Description" required></textarea>
			<label for="timeframe">Timeframe to complete the work</label> 
			<p>
				(2 weeks, 1 month, 6 months, etc.) 
			</p>
			<input id="timeframe" name="Timeframe" required> 
		</fieldset>
		<fieldset>
			<legend>Application requirements</legend> 
			<p>
				(What information & documents should the applying students send you?) 
			</p>
			<div>
				<input type="checkbox" id="send-resume" name="Resume" value="Yes"> <label for="send-resume">Résumé</label> 
			</div>
			<div>
				<input type="checkbox" id="send-portfolio" name="Portfolio" value="Yes"> <label for="send-portfolio">Portfolio</label> 
			</div>
		</fieldset>
		<input type="hidden" name="_subject" value="Student Employment Opportunity"> 
		<input type="hidden" name="_next" value="https://algonquindesign.ca/jobs/thanks/"> 
		<input type="hidden" name="_format" value="plain"> <small>By providing your contact information, you are granting the Graphic Design program permission to contact you for program-related activities. We mostly wish to invite you to our yearly Grad Show. We will not share your private information.</small> 
		<div>
			<button type="submit">Submit job</button> 
		</div>
	</form>
</main>
{% include footer.html %}