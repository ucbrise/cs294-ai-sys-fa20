---
layout: default
---


# Conversations with Thought Leaders in Technology (CS198-100)

* **When**: Tuesdays from 5:00 to 6:00 PM (PST)
* **Where**: Zoom! (Attendance Required)
* **Instructors**: [Vik Singh](https://www.linkedin.com/in/viksingh1/) and [Joseph E. Gonzalez](https://eecs.berkeley.edu/~jegonzal)
   * **Office Hours:** Gonzalez office hours are thursdays from 4:00 to 5:00 on zoom.


## Course Description

This interactive seminar class will connect a select group of Berkeley students with thought leaders at major technology companies and venture capital firms.  Each week will be organized around a short set of readings related to the speaker’s background followed by a live zoom session with that speaker.  Students will participate in an interactive slack discussion and generate questions to ask each speaker.  Students will learn about how new technology is funded and developed as well as trends in the industry.  They will also have the opportunity to meet face-to-face with CXOs, VC partners, and top research scientists from around the world and learn about their career paths.  This is also an amazing opportunity to network with leaders in the technology world.


### Confirmed Speakers 

* [Steven Newhouse](https://www.bloomberg.com/profile/person/4664315): Co-President of [Advance Publications](https://en.wikipedia.org/wiki/Advance_Publications) which owns directly and through various subsidiaries, the Discovery Channel, Condé Nast, Wired, Lycos, Angelfire, Tripod, and is the majority shareholder in Reddit.
* [Henry Schuck](https://www.linkedin.com/in/hschuck/): CEO / Co-Founder at ZoomInfo (just took public - hottest IPO of the year by far)
* [Sanjay Poonen](https://www.vmware.com/company/leadership/sanjay-poonen.html): COO of VMware, former President of SAP
* [Mamoon Hamid](https://www.kleinerperkins.com/people/mamoon-hamid/): Lead GP at Kleiner Perkins, early investor in Slack and Box
* [Archana Agrawal](https://www.linkedin.com/in/archana-agrawal/): CMO of Airtable, head of enterprise at Atlassian, on the boards of Zendesk and MongoDB
* [Hilary Mason](https://hilarymason.com/): General manager of ML at Cloudera (acquired her startup), Chief Scientist at bitly, board of Anita Borg
* [Nick Caldwell](https://www.linkedin.com/in/nickcaldwell/): VP Engineering at Twitter, CPO at Looker (acquired by Google for $2.6B), board of /dev/color

## Course Syllabus 

A full list of speakers is coming soon.

<!-- This is a tentative schedule.  Specific readings are subject to change as new material is published.
 -->
<a href="#today"> Jump to Today </a>

<table class="table table-striped syllabus">
<thead>
   <tr>
      <th style="width: 5%"> Week </th>
      <th style="width: 10%"> Date and Time </th>
      <th style="width: 85%"> Speaker </th>
   </tr>
</thead>
<tbody>




<tr>
<td style="background:gray; color:white; font-size:16pt; vertical-align:middle;" id="week_1"> 
<center><a href="#week_1" style="color:white">1</a></center> 
</td>
<th id="counter_09/01/20_1"> 09/01/20 (5:00PM) </th>

<td markdown="1">
## Introduction and Course Overview

This lecture will be an overview of the class, requirements, and an introduction to the course format as well as a conversation with the instructors.

</td>
</tr>




<tr>
<td style="background:gray; color:white; font-size:16pt; vertical-align:middle;" id="week_1"> 
<center><a href="#week_1" style="color:white">1</a></center> 
</td>
<th id="counter_09/08/20_1"> 09/08/20 (5:00PM) </th>

<td markdown="1">
## Joseph E. Gonzalez

Joseph will talk about his career spanning academia and industry and what he sees as big trends in Machine Learning and Data Science and how to get involved.

<div class="reading">
<div class="required_reading" markdown="1">
* [SysML: The New Frontier of Machine Learning Systems](https://arxiv.org/abs/1904.03257)
* [A Few Useful Things to Know About Machine Learning](https://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf)
</div>

<div class="optional_reading" markdown="1">
* [How to read a paper](https://web.stanford.edu/class/ee384m/Handouts/HowtoReadPaper.pdf) provides some pretty good advice on how to read papers effectively.
</div>
</div>


</td>
</tr>




</tbody>
</table>




## Grading

This 2-unit class is only offered with P/NP grading and grades will be assessed based on attendance and participation in weekly zoom meetings.










<script type="text/javascript">


var current_date = new Date();
var rows = document.getElementsByTagName("th");
var finished =  false;
for (var i = 1; i < rows.length && !finished; i++) {
   var r = rows[i];
   if (r.id.startsWith("counter_")) {
      var fields = r.id.split("_")
      var week_div_id = "week_" + fields[2]
      var lecture_date = new Date(fields[1] + " 23:59:00")
      if (current_date <= lecture_date) {
         finished = true;
         r.style.background = "orange"
         r.style.color = "black"
         var week_td = document.getElementById(week_div_id)
         week_td.style.background = "#043361"
         week_td.style.color = "white"
         var anchor = document.createElement("div")
         anchor.setAttribute("id", "today")
         week_td.prepend(anchor)
      }
   }
}

$(".reading").each(function(ind, elem) {
   var optional_reading = $(elem).find(".optional_reading");
   if(optional_reading.length == 1) {
      optional_reading = optional_reading[0];
      optional_reading.setAttribute("id", "optional_reading_" + ind);
      var button = document.createElement("button");
      button.setAttribute("class", "btn btn-primary btn-sm");
      button.setAttribute("type", "button");
      button.setAttribute("data-toggle", "collapse");
      button.setAttribute("data-target", "#optional_reading_" + ind);
      button.setAttribute("aria-expanded", "false");
      button.setAttribute("aria-controls", "#optional_reading_" + ind);
      optional_reading.setAttribute("class", "optional_reading_no_heading collapse")
      button.innerHTML = "Additional Optional Reading";
      optional_reading.before(button)
   }

})


$(".details").each(function(ind, elem) {
      elem.setAttribute("id", "details_" + ind);
      var button = document.createElement("button");
      button.setAttribute("class", "btn btn-primary btn-sm");
      button.setAttribute("type", "button");
      button.setAttribute("data-toggle", "collapse");
      button.setAttribute("data-target", "#details_" + ind);
      button.setAttribute("aria-expanded", "false");
      button.setAttribute("aria-controls", "#details_" + ind);
      elem.setAttribute("class", "details_no_heading collapse")
      button.innerHTML = "Detailed Description";
      elem.before(button)
   })

</script>


