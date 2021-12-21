---
title: Calendar
author: Ben Rosenberg
toc: false
---

<script type="text/javascript" src="../js/calendar-2.5.js"></script>
<script>
var myCal = new JEC('myCalendarContainer', {
  tableClass: 'styledCalendar',
  firstMonth: 202112,
  // lastMonth: 201010,
  firstDayOfWeek: 2,
  specialDays: [ 1, 7 ],
  linkNewWindow: false,
  weekdays: [
    "Sunday",
    "Monday",
    "Tuesday",
    "Wednesday",
    "Thursday",
    "Friday",
    "Saturday"
  ]
});
myCal.defineEvents(
  [
    // { // EXAMPLE EVENT
    //   eventDate: 20100407,
    //   eventDescription: 'JEC 2.0 Released',
    //   eventLink: 'http://calendar.ilsen.net',
    //   eventLinkTitle: 'A JavaScript Event Calendar'
    // },
    {
      eventDate: 20211231,
      eventDescription: 'New Year\'s Eve',
      eventLink: 'http://google.com'
    },
    { eventDate: 20220101, eventDescription: 'Happy New Year!' }
  ]
);
myCal.showCalendar(202112);
</script>

<div id='myCalendarContainer'></div>