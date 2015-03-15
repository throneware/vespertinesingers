---
layout: page
title: Contact
permalink: /contact/
---

Contact us to make an enquiry about a booking

<form action="https://getsimpleform.com/messages?form_api_token=e4e5d27ff91190711fda2fc13fc75ef4" method="post">
  	<!-- the redirect_to is optional, the form will redirect to the referrer on submission -->
	<input type='hidden' name='redirect_to' value='{{ "thankyou/" | prepend: site.url }}' />

	<div class='row'>
		<div class='col-md-6'>
			<div class="form-group">
				<label for="nameInput">Name</label>
				<input type="text" class="form-control" name="nameInput" placeholder="Enter your name" required>
			</div>
			<div class="form-group">
				<label for="emailInput">Email address</label>
				<input type="email" class="form-control" name="emailInput" placeholder="Enter email" required>
			</div>
			<div class="form-group">
				<label for="eventTypeInput">Event Type</label>
				<input type="text" class="form-control" name="eventTypeInput" placeholder="Enter event type">
			</div>
		</div>
		<div class='col-md-6'>
			<div class="form-group">
				<label for="performanceLengthInput">Performance Length</label>
				<input type="text" class="form-control" name="performanceLengthInput" placeholder="Enter your performance length">
			</div>
			<div class="form-group">
				<label for="bookingDateInput">Performance Date</label>
				<input type="date" class="form-control" name="bookingDateInput">
			</div>
		</div>
	</div>

	<div class='row' style='margin-top:15px; margin-bottom:25px;'>
		<div class='col-md-12'>
			<label for="extraInformation">Genres of Music</label><br/>
			<label class="checkbox-inline">
			  <input type="checkbox" name="musicalTheatreGenre" value="true"> Musical Theatre
			</label>
			<label class="checkbox-inline">
			  <input type="checkbox" name="popGenre" value="true"> Pop
			</label>
			<label class="checkbox-inline">
			  <input type="checkbox" name="ratPackGenre" value="true"> Rat Pack
			</label>
			<label class="checkbox-inline">
			  <input type="checkbox" name="motownGenre" value="true"> Motown
			</label>
			<label class="checkbox-inline">
			  <input type="checkbox" name="60sGenre" value="true"> 60's
			</label>
			<label class="checkbox-inline">
			  <input type="checkbox" name="70sGenre" value="true"> 70's
			</label>
			<label class="checkbox-inline">
			  <input type="checkbox" name="80sGenre" value="true"> 80's
			</label>
			<label class="checkbox-inline">
			  <input type="checkbox" name="IndieGenre" value="true"> Indie
			</label>
			<label class="checkbox-inline">
			  <input type="checkbox" name="SwingGenre" value="true"> Swing
			</label>
		</div>
	</div>

	<div class='row'>
		<div class='col-md-12'>
			<label for="extraInformation">Any Additional Information</label>
			<textarea name="extraInformation" class="form-control" rows="5"></textarea>
		</div>
	</div>

	<button type="submit" style="margin-top:25px;" class="center-block btn btn-primary btn-lg">Submit</button>

</form>
