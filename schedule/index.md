<link rel="stylesheet" href="{{baseUrl}}/css/main.css">
<link rel="stylesheet" href="{{baseUrl}}/css/schedule.css">

<include src="../common/header.md" />

<div class="website-content">
<panel header=":calendar: Tutorial Schedule" expandable no-close>
  <include src="overview/tutorialSchedule.md"/>
</panel>
<include src="overview/index.html" name="For all weeks" dynamic />
<include src="week1/index.html" name="Week 1 [Jan 15]" dynamic />
<include src="week2/index.md" name=":exclamation: Week 2 [Jan 22]" dynamic />
<panel header=":exclamation: Week 3 [Jan 29]" expanded no-close>
<include src="week3/index.md"/> 
</panel>
<include src="week4/index.md" name=":exclamation: Week 4 [Feb 5]" dynamic />
<include src="week5/index.md" name="Week 5 [Feb 12]" dynamic />
<include src="week6/index.html" name="Week 6 [Feb 19]" dynamic />
<include src="week7/index.html" name="Week 7 [Mar 5]" dynamic />
<include src="week8/index.html" name="Week 8 [Mar 12]" dynamic />
<include src="week9/index.html" name="Week 9 [Mar 19]" dynamic />
<include src="week10/index.html" name="Week 10 [Mar 26]" dynamic />
<include src="week11/index.html" name="Week 11 [Apr 2]" dynamic />
<include src="week12/index.html" name="Week 12 [Apr 9]" dynamic />
<include src="week13/index.html" name="Week 13 [Apr 16]" dynamic />
</div>

