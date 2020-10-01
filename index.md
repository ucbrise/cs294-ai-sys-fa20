---
layout: default
---


# Conversations with Thought Leaders in Technology (CS198-100)

* **When**: Tuesdays from 5:00 to 6:00 PM (PST)
* **Where**: Zoom! (Attendance Required)
* **Instructors**: [Vik Singh](https://www.linkedin.com/in/viksingh1/) and [Joseph E. Gonzalez](https://eecs.berkeley.edu/~jegonzal)
   * **Office Hours:** Gonzalez office hours are thursdays from 2:00 to 3:00 on zoom.


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

### Calendar with Zoom Links

<iframe src="https://calendar.google.com/calendar/embed?height=600&amp;wkst=1&amp;bgcolor=%237986CB&amp;ctz=America%2FLos_Angeles&amp;src=Y19jcnVydWNjZXZkYnFndXJvYzlhNXB1MTI1Y0Bncm91cC5jYWxlbmRhci5nb29nbGUuY29t&amp;color=%23711a76&amp;showNav=1&amp;showTitle=0&amp;mode=AGENDA&amp;showTabs=1&amp;showPrint=0&amp;showCalendars=0&amp;showTz=1" style="border:solid 1px #777" width="800" height="600" frameborder="0" scrolling="no"></iframe>


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
<center><a href="#week_2" style="color:white">2</a></center> 
</td>
<th id="counter_09/08/20_1"> 09/08/20 (5:00PM) </th>

<td markdown="1">
## [Joseph E. Gonzalez](https://eecs.berkeley.edu/~jegonzal), Asst. Professor UC Berkeley

Joseph is an Assistant Professor at UC Berkeley and a co-director of the UC Berkeley RISELab, a large research group backed by the NSF and a consortium of leading international industrial sponsors. He is a recipient of the NSF Early CAREER Award for his work on prediction serving systems and co-PI on the NSF Expedition Award for the RISE Lab. Before joining UC Berkeley, Joseph co-founded Turi to develop tools for data scientists based on his PhD thesis and he later sold Turi to Apple. His research is focused on the intersection of machine learning and systems and covers a broad range of areas including the design of efficient neural networks and systems for graph analytics, prediction serving, and serverless computing with applications in computer vision, natural language processing, and robotics. He has made significant contributions to the design of efficient neural networks to reduce computation and enable meta-learning. His work on both graph systems and prediction serving systems helped define their respective disciplines. His research produced multiple significant software artifacts including the GraphLab, PowerGraph and GraphX graph processing systems, the Opaque secure analytics system, the Clipper prediction serving system, as well as the RLlib, Tune, and Modin libraries for reinforcement learning, hyperparameter search, and distributed data processing respectively. These systems are widely used and have become standard parts of commercial offerings. Joseph helped establish the machine learning systems community and has served on the program committee for many of the top-tier conferences in machine learning and computer systems and was an editor for the IEEE data-engineering bulletin. Joseph launched and co-organized the MLSys workshop series for the past 10 years. This workshop series helped establish the MLSys research community and the new MLSys conference.



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


