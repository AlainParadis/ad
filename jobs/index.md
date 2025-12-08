---
layout: default
title: "Jobs"
description: "Inquire about hiring one of our fantastic, highly skilled & motivated Graphic Design students."
---
<ul class="skip-links">
	<li><a href="#form">Jump to Form</a></li>
</ul>

{% include 01-masthead.html %}
{% include 02-banner.html %} 
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
    	<form class="" action="https://submit-form.com/DrQxZHCef">
		<fieldset>
			<legend>Identification</legend>
			<div>
				<label class="form-label" for="name">Name</label> 
				<input type="text" id="name" name="Name" placeholder="Name" required="">
			</div>
			<div>
				<label class="form-label" for="email">Email</label> 
                <input type="email" id="email" name="E-mail" placeholder="E-mail" required="">
			</div>
			<div>
				<label class="form-label" for="telephone">Phone</label> 
                <input type="telephone" id="tel" name="telephone" placeholder="Telephone">
			</div>
			<div>
				<label class="form-label" for="organization">Organization name <em>(Optional)</em></label> 
                <input type="text" id="organization" name="Organization" placeholder="Organization" required="">
			</div>
			<div>
				<label class="form-label" for="address">Address <em>(Optional)</em></label> 
				<input type="text" id="address" name="Address" placeholder="Address" required="">
			</div>
			<div>
				<label class="form-label" for="city">City <em>(Optional)</em></label> 
				<input type="text" id="city" name="City" placeholder="City">
			</div>
			<div>
				<label class="form-label" for="type">You are a…</label> 
				<select id="org-type" name="Org-Type" required="">
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
				<label class="form-label" for="seeking">You’re seeking a designer for…</label> 
				<select id="seeking" name="Seeking" required="">
					<option value=""></option>
					<option value="A single job">A single job</option>
					<option value="A limited-time contract">A limited-time contract</option>
					<option value="Ongoing part-time work">Ongoing part-time work</option>
					<option value="A full-time position">A full-time position</option>
					<option value="Other">Other, describe below</option>
				</select>
			</div>
		</fieldset>
        <fieldset class="form-work-paid">
          <legend>Is the work paid?</legend> 
          <div class="form-row">
            <label class="radio-option">
              <input type="radio" id="work-paid-yes" name="Paid" value="Yes" checked>
              Yes
            </label>
            <label class="radio-option">
              <input type="radio" id="work-paid-no" name="Paid" value="No">
              No
            </label>
          </div>
        </fieldset>
		<fieldset>
			<legend>Description of the work needed</legend> 
			<div class="form-text">
			General graphic design, web design, branding, motion video, etc.
			</div>
			<textarea id="work-desc" name="Work-Description" required></textarea>
			<label class="form-label" for="timeframe">Timeframe to complete the work (2 weeks, 1 month, 6 months, etc…)</label>
			<input type="text" id="timeframe" name="timeframe" placeholder="Timeframe" required="">
		</fieldset>
		<fieldset class="app-reqs">
			<legend>Application requirements</legend> 
			<div class="form-text">
			What information & documents should the applying students send you?
			</div>
			<div class="form-row">
			<label class="radio-option">
                <input type="checkbox" id="send-resume" name="send-resume" value="Résumé" /> Résumé
                <input type="checkbox" id="send-portfolio" name="send-portfolio" value="Portfolio" /> Portfolio
            </label>
			</div>
		</fieldset>
		<input type="hidden" name="_email.subject" value="Student Employment Opportunity" />
		<input type="hidden" name="_redirect" value="https://algonquindesign.ca/jobs/thanks/"> 
		<small class="">By providing your contact information, you are granting the Graphic Design program permission to contact you for program-related activities. We mostly wish to invite you to our yearly Grad Show. We will not share your private information.</small> 
		<div>
			<button class="" type="submit">Submit</button>
		</div>
		</form>
</main>
{% include 13-footer.html %}