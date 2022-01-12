---
title: The Orange County Scottish Rite News
volume: 8
number: 1
date: January 2022

# Articles
articles:
    - path: "./personal-representative.md"
    - path: "./venerable-master.md"
    - path: "./wise-master.md"
    - path: "./commander.md"
    - path: "./master-of-kadosh.md"
    - path: "./senior-warden.md"
    - path: "./general-secretary.md"

# Calendar information
calendar-entries:
    - date: Monday, January 3, 2022
      event: Stated Meeting
      location: Anaheim Demolay Center
      time: 6:30pm
      notes: No meal following meeting

    - date: Monday, January 10, 2022
      event: Master Craftsman Study Group
      location: Online Zoom meeting
      time: 5:00pm

    - date: Sunday, January 16, 2022
      event: Installation of Officers
      location: Anaheim Demolay Center
      time: 2:00pm
      notes: Officers must arrive by noon for practice and photos /
        Ceremony at 2:00pm followed by a meal
---

{{% article "./personal-representative.md" %}}
<!-- or do it this way, with front-matter -->
{{% article $.Page.Params.articles[0] %}} 
<!-- obvs not the correct syntax -->

<!-- Pass the calendar-entries to the calendar shortcode -->
{{% calendar $Page.Params.calendar-entries %}}

{{% article "./venerable-master.md" %}}
<!-- or do it this way, with front-matter -->
{{% article $.Page.Params.articles[1] %}} 
<!-- etc... -->

{{% obituary %}}

{{% article "./wise-master.md" %}}

{{% website-ad %}}

{{% article "./commander.md" %}}

{{% article "./master-of-kadosh.md" %}}

{{% article "./clc-update.md" %}}

{{% clc-masthead %}}

{{% article "./senior-warden.md" %}}

{{% article "./general-secretary.md" %}}

{{% article "./editor" %}}

{{% officers %}}

{{% website-ads %}}

