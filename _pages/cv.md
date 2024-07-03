---
layout: archive
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div class="download"><a href="/files/cv.pdf">(Download as PDF)</a></div>

<div style="text-align: center;font-weight:bold;"><h1>Michael W. Sances</h1></div>
<div style="text-align: center;"><h2 style="font-weight:normal;">Curriculum Vitae</h2></div>

464 Gladfelter Hall\
1115 Polett Walk\
Philadelphia, PA 19122\
215-204-7796\
[msances@temple.edu](mailto:msances@temple.edu)\
[http://sites.temple.edu/msances](http://sites.temple.edu/msances)

Academic Positions
======
* Temple University, Philadelphia, PA
	* Associate Professor, Department of Political Science, July 2022 -- present
	* Assistant Professor, Department of Political Science, July 2019 -- June 2022

* University of Memphis, Memphis, TN
	* Assistant Professor, Department of Political Science, August 2015 -- July 2019

* Vanderbilt University, Nashville, TN
	* Postdoctoral Fellow, Center for the Study of Democratic Institutions, August 2014 -- August 2015

Education
======
* Ph.D., Political Science, Massachusetts Institute of Technology, 2014
* B.A., Political Science, University of Massachusetts, 2006

Peer-Reviewed Publications
======
  {% for post in site.publications reversed %}
    {% unless post.status %}
      {% include archive-single-publication-cv.html %}
    {% endunless %}
  {% endfor %}

Working Papers
======
{% for post in site.publications reversed %}
  {% if post.status == "workingpaper" %}
    {% include archive-single-workingpaper.html %}
  {% endif %}
{% endfor %}

Other Publications
======
  {% for post in site.publications reversed %}
    {% if post.status %}
      {% unless post.status == "workingpaper" %}
        {% include archive-single-otherpublication-cv.html %}
      {% endunless %}
    {% endif %}
  {% endfor %}

Policy Reports, Opinion Pieces, and Blog Posts
======
  {% for post in site.writings reversed %}
    {% include archive-single-otherpublication-cv.html %}
  {% endfor %}
      
Grants and Awards
======
• Liberal Arts Undergraduate Research Award, Fall 2023

• Liberal Arts Undergraduate Research Award, Summer 2023

• Participant, Causal Inference for Social Impact Lab's Data Challenge, 2022.

• Faculty Fellow, Public Policy Lab, Temple University, 2020-2021.

• William Penn Foundation, “Impacts of State and Local Fiscal Policy Choices in a Time of Great Dislocations”, 2020-2021.

• University of Memphis, Junior Scholar Nominee for Andrew Carnegie Fellows Program, 2018.

• University of Memphis, Michael Harless Faculty Excellence Award, 2018-2019.

• Russell Sage Foundation, Presidential Award, “The Medicaid Expansion's Impact on Partisanship, Repeal Support, and Dyadic Representation” (with Joshua Clinton), 2018-2020.

• University of Memphis, Junior Scholar Nominee for Andrew Carnegie Fellows Program, 2017.

• University of Memphis, Faculty Research Grant, “American City Elections Study,” 2017-2018.

• Smart City Research Fellow of the FedEx Institute of Technology, 2016-2017.

• FedEx Institute of Technology and City of Memphis, Smart Cities Award, “Using New Technologies to Survey Memphis Residents: Identifying and Responding to Local Concerns,” 2016-2017.

• American National Election Study, questions on election predictions selected for inclusion on the 2016 ANES Time Series (with Kai Quek).

• Russell Sage Foundation, Presidential Award, “Policy Making Politics? The Mass Political Impact of Medicaid Expansions” (with Joshua Clinton), 2016-2018.

• Travel Enrichment Grant, College of Arts and Sciences, University of Memphis, 2015.

• Lucian Pye Award for best dissertation in the MIT Department of Political Science, 2015.

• National Science Foundation, Doctoral Dissertation Improvement Grant, 2012. 

• National Science Foundation, Time-sharing Experiments for the Social Sciences (TESS), “Campaign Finance and Citizen Attitudes Toward Government,” 2011.

Teaching
======

* Temple University
{% assign coursesTemple = site.teaching | where:"venue", "Temple University, Department of Political Science" | sort: "title" %}

{% assign coursesTempleTitles = coursesTemple | group_by_exp:"post", "post.title" %}

{% for title in coursesTempleTitles %}
	* {{ title.name }}
{% endfor %}

* University of Memphis
{% assign coursesTemple = site.teaching | where:"venue", "University of Memphis, Department of Political Science" | sort: "title" %}

{% assign coursesTempleTitles = coursesTemple | group_by_exp:"post", "post.title" %}

{% for title in coursesTempleTitles %}
	* {{ title.name }}
{% endfor %}

Paid Consultancies
======
• NBC Universal, Elections Analyst, November 2019-November 2020.

• Data for Progress, Data Analyst, July-November 2019.

• Apperson Crump PLC, Data Analyst, June-July 2016.

Community Outreach
======
• Key Votes Advisor for Pennsylvania, Project Vote Smart, August 2023-present.

Community Presentations
======

• "The 2024 Elections and Beyond." Dissent in America Teach-In, Temple University, February 16, 2024.

• “The Midterm Elections: What Does It All Mean?” Dissent in America Teach-In, Temple University, November 11, 2022.

• “Policy Roundtable - Midterm Elections 2022.” Public Policy Lab, Temple University, October 20, 2022.

• “Local Fiscal Effects of Transitions to State Police Coverage.” Local Government Symposium: Improving Effectiveness and Efficiency in PA Local Government in a Post-COVID World. Local Government Commission of the Pennsylvania General Assembly, October 21, 2021

• “Redistricting 2021.” Dissent in America Teach-In, Temple University, October 22, 2021.

• “Election 2020: Results and Reactions.” Public Policy Lab Panel, Temple University, November 10, 2020.

• “Politics and the Pandemic.” Dissent in America Teach-In, Temple University, September 18, 2020.

• “What's Next in TN Politics?” Tennessee County Services Association, Memphis, TN, November 3, 2017.

Conference and Seminar Presentations
======
• 2024

• Midwestern Political Science Association

• 2023

• American Political Science Association

• Midwestern Political Science Association

• Election Science, Reform, & Administration Conference

• 2022

• American Political Science Association

• Midwestern Political Science Association

• 2021

• “Local Government Symposium: Improving Effectiveness and Efficiency in PA Local Government in a Post-COVID World.” Local Government Commission of the Pennsylvania General Assembly, October 21, 2021 (virtual)

• University of California, Berkeley Research Workshop in American Politics (virtual)

• Columbia University American Politics Speaker Series (virtual)

• Political Institutions and Political Economy (PIPE) Collaborative Local Political Economy Symposium, University of Southern California (virtual)

• 2020

• International City/County Management Association (ICMA) Unite Conference (virtual)

• University of Pennsylvania American Politics Seminar (virtual)

• American Political Science Association

• Southern Political Science Association

• 2019

• Yale University American Politics & Public Policy Workshop

• American Political Science Association

• St. Louis Area Methods Meeting (SLAMM!)

• Midwestern Political Science Association

• University of Copenhagen

• Aarhus University

• 2018

• MIT American Politics Conference

• Midwestern Political Science Association

• First Annual Political Institutions and Political Economy (PIPE) Conference, University of Southern California

• Journal of Health Politics, Policy and Law Special Issue on Health and Political Participation Conference

• 2017

• Russell Sage Foundation/Robert Wood Johnson Foundation Conference on the Effects of the Affordable Care Act

• American Political Science Association

• University of California Berkeley Local Political Economy Conference

• State Politics and Policy Conference

• Midwestern Political Science Association

• Vanderbilt University Urban Political Economy Conference

• Southern Political Science Association

• 2016

• American Political Science Association

• Midwestern Political Science Association

• Southern Political Science Association

• 2014

• Vanderbilt Center for the Study of Democratic Institutions Seminar

• American Political Science Association

• 2013

• American Political Science Association

• Yale American Politics Conference

• University of Michigan/AAAPSS Conference on the Great Recession

• Midwestern Political Science Association

• 2012

• Society for Political Methodology

• Midwestern Political Science Association

• NYU Experimental Political Science Conference

• MIT Political Economy Breakfast

• 2011

• Society for Political Methodology

• Midwestern Political Science Association

Professional Service
======
• Editorial board member, Political Behavior, 2023-

• Section head, “Representation and Electoral Systems,” 2024 Midwestern Political Science Association Annual Meeting

• Reviewer, APSA Spring Centennial Center Research Grants, 2023

• Chair, APSA Federalism and Intergovernmental Relations Section John Kincaid Best Article Award Committee, 2023

• Editorial board member, Journal of Health Politics, Policy, and Law, 2021-

• Executive Committee member, APSA Federalism and Intergovernmental Relations Section, 2020-2022

• Reviewer, Accountable Institutions and Behavior Program, National Science Foundation, 2021

• Committee member, APSA Federalism and Intergovernmental Relations Section Martha Derthick Book Award, 2020

• Committee member, APSA Political Psychology Section Best Paper Award, 2019

• Section chair, “Crime, Policy, & Social Control,” 2018 Midwestern Political Science Association Annual Meeting

• Reviewer: _American Political Science Review_; _American Journal of Political Science_; _American Politics Research_; _British Journal of Political Science_; _Canadian Journal of Political Science_; _Cities_; _Comparative Political Studies_; _Criminal Justice Review_; _Economics & Politics_; _Electoral Studies_; _European Journal of Political Economy_; _Health Affairs_; _International Journal of Public Opinion Research_; _Japanese Journal of Political Science_; _Journal of Behavioral and Experimental Economics_; _Journal of Elections, Public Opinion & Parties_; _Journal of Experimental Political Science_; _Journal of Health Politics, Policy and Law_; _Journal of Politics_; _Journal of Public Economics_; _Journal of Public Policy_; _Journal of Quantitative Description: Digital Media_; _Journal of Race, Ethnicity, and Politics_; _Journal of Urban Affairs_; _Nonprofit and Voluntary Sector Quarterly_; _Party Politics_; _PLOS ONE_; _PS: Political Science & Politics_; _Policy Sciences_; _Policy Studies Journal_; _Political Analysis_; _Political Behavior_; _Political Research Quarterly_; _Political Science Research and Methods_; _Political Studies_; _Politics and Governance_; _Politics & Policy Quarterly_; _Presidential Studies Quarterly_; _Public Opinion Quarterly_; _Publius_; _Quarterly Journal of Political Science_; _Research and Politics_; _Review of Economics and Statistics_; _Social Science Quarterly_; _Sociological Methods and Research_; _Sociological Perspectives_; _State Politics & Policy Quarterly_; _Swiss Political Science Review_; _Urban Affairs Review_

Departmental and University Service
======
• Temple University

• Political Science Graduate Chair, 2024–

• Dissertation Committee Member, Daniel Confalone, 2024–

• Public Policy Lab Advisory Board, 2022–

• American Politics Field Chair, 2022–

• Department Contracts and Tenure Committee, Fall 2022.

• American Politics Comprehensive Exam Committee, Fall 2021.

• American Politics Faculty Search Committee, 2021.

• Masters of Public Policy Advisory Committee, 2020.

• Merit Committee, Department of Political Science, 2020.

• Master's Thesis Committee Member: Megan Beckwith (University of Memphis), 2019–2020.

• University of Memphis

• Master's Thesis Committee Chair: Emily Fulmer, 2018–2019.

• American Politics Faculty Search Committee, 2018.

• Public Policy Faculty Search Committee, 2018.

• Political Theory Faculty Search Committee, 2017.

• Faculty Senate, 2017–2019.

• Coordinator of Graduate Recruitment, 2016–2017.

• Faculty Evaluator, Undergraduate Works in Progress Symposium, 2016.

• Comparative Politics Faculty Search Committee, 2016.

• School of Urban Affairs and Public Policy PhD Program Committee, 2015–2016.

• Master's Thesis Committee Member: Brooke Shannon, 2015–2016.
