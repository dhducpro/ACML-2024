---
permalink: /index.html
classes: wide

title: The 16th Asian Conference on Machine Learning
header:
  overlay_color: "#000"
  overlay_filter: ".35"
  overlay_image: /assets/images/Hanoi2-1652338755-3632-1652338809.jpg
#   overlay_image: /assets/images/vietnam1.png
  actions:
    - label: "Explore Vietnam"
      url: logistic/explore/
    - label: "Registration"
      url: registration/information/
    # - label: "Call for Tutorials"
    #   url: calls/tutorial/
  caption:
excerpt: ACML 2024 offers a premier international platform for researchers in Machine Learning and related disciplines to exchange innovative ideas, share progress, and showcase achievements. The conference will be held in person from December 5-8, 2024, in Hanoi, Vietnam.


news:
  max_items: 3
---

# News

{% include news.html max_items=page.news.max_items %}

# Important Dates

<div class="events">

<div class="article-container">
	<div class="article">
	<h2>Conference Track Dates</h2>

{% include track_events.html track=site.data.tracks.conference %}


</div>


<div class="article">
	<h2>Journal Track Dates</h2>

<div style="overflow-x:auto;"> <!-- Responsive table -->
	<table>
		<thead>
			<tr>
				<th>Date</th>
				<th>Event</th>
			</tr>
		</thead>
		<tbody>
			
			
			<tr class="date" data-event-track="Journal Track Dates" data-event-name="Submission deadline" data-event-date="2024-05-29T23:59:59-07:00">
				<td>
					
					29 May 2024
				</td>
				<td>
					Submission deadline

				</td>
			</tr>
			
			<tr class="date" data-event-track="Journal Track Dates" data-event-name="1st round review results (accept, minor revision, or reject)" data-event-date="2024-07-31T23:59:59-07:00">
				<td>
					
					Late July 2024
				</td>
				<td>
					1st round review results (accept, minor revision, or reject)

				</td>
			</tr>
			
			<tr class="date" data-event-track="Journal Track Dates" data-event-name="Revised manuscript submission deadline (for minor revision papers)" data-event-date="2024-08-15T23:59:59-07:00">
				<td>
					
					Mid August 2024
				</td>
				<td>
					Revised manuscript submission deadline (for minor revision papers)

				</td>
			</tr>
			
			<tr class="date" data-event-track="Journal Track Dates" data-event-name="Acceptance notification" data-event-date="2024-09-04T23:59:59-07:00">
				<td>
					
					04 September 2024
				</td>
				<td>
					Acceptance notification

				</td>
			</tr>
			
			<tr class="date" data-event-track="Journal Track Dates" data-event-name="Camera-ready submission deadline" >
				<td>
					
					<s> 29 September 2024 </s>
				</td>
				<td>
					<s> Camera-ready submission deadline </s>

				</td>
			</tr>

			<tr class="date" data-event-track="Journal Track Dates" data-event-name="Camera-ready submission" data-event-date="2024-09-04T23:59:59-07:00">
				<td>
					
					<strong> December 2024 </strong>
				</td>
				<td>
					<strong> Camera-ready submission after presentation at the conference </strong>

				</td>
			</tr>
			
		</tbody>
	</table>
</div>

<script id="track_events_journal-track-dates" type="application/json">
{"name":"Journal Track Dates","id":0,"dates":[{"date":"2024-05-29T23:59:59-07:00","name":"Submission deadline"},{"date":"2024-07-31T23:59:59-07:00","name":"1st round review results (accept, minor revision, or reject)"},{"date":"2024-08-15T23:59:59-07:00","name":"Revised manuscript submission deadline (for minor revision papers)"},{"date":"2024-09-04T23:59:59-07:00","name":"Acceptance notification"},{"date":"2024-09-29T23:59:59-07:00","name":"Camera-ready submission deadline"}]}
</script>
<script type="text/javascript">
	document.addEventListener('DOMContentLoaded', function() {
		var value = JSON.parse(document.getElementById("track_events_journal-track-dates").innerHTML);
		var tracks = { "Journal Track Dates": value };
	   	var dates = split_dates(tracks);

		// Strikethrough expired row
		for (var i = 0; i < dates['expired'].length; i++) {
			get_event_elem('.date', dates['expired'][i]).setAttribute("style", "color: gray;text-decoration: line-through;");
		}
		// Bold current row
		for (var i = 0; i < dates['current'].length; i++) {
			get_event_elem('.date', dates['current'][i]).setAttribute("style", "font-weight:bold;");
		}
	}, false);
</script>





</div>

<div class="article">
	<h2>Tutorials Dates</h2>

{% include track_events.html track=site.data.tracks.tutorial %}
</div>

<div class="article">
	<h2>Workshops Dates</h2>

{% include track_events.html track=site.data.tracks.workshops %}
</div>

</div>
</div>


# Why Vietnam?
* A South-East Asia's fastest developing economy.
* A growing interest in AI both in academia and industry
* ACML held in Vietnam last in 2014 in Nha Trang.
