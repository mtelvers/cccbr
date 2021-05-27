---
title: Members Help
date: 2016-10-19 22:55:43.000000000 +00:00
author: Andrew Hall
layout: single
xyz_fbap:
- '1'
---
The **Members** dataset defines people who are actual members of Council (or perform a service such as a Consultant to a committee). When adding a new member, all fields are available for input. Otherwise the form is displayed read-only with buttons **CHANGE ASSIGNMENT** and **CHANGE DETAILS** which will unlock appropriate fields.

<table style="height: 121px; width: 681px;">
  <tr style="height: 24px;">
    <td style="width: 167.083px; height: 24px;">
      <strong>Label</strong>
    </td>
    
    <td style="width: 495.917px; height: 24px;">
      <strong>Details</strong>
    </td>
  </tr>
  
  <tr style="height: 24px;">
    <td style="width: 167.083px; height: 24px;">
      Society
    </td>
    
    <td style="width: 495.917px; height: 24px;">
      Society (or other Organisation entity) the person has been elected to
    </td>
  </tr>
  
  <tr style="height: 24px;">
    <td style="width: 167.083px; height: 24px;">
      Member
    </td>
    
    <td style="width: 495.917px; height: 24px;">
      The person who has been elected. For Change Assignment, the current member will be excluded from the list.
    </td>
  </tr>
  
  <tr style="height: 24px;">
    <td style="width: 167.083px; height: 24px;">
      Start Date
    </td>
    
    <td style="width: 495.917px; height: 24px;">
      The date the member was elected or appointed to Council (ADD/CHANGE DETAILS)
    </td>
  </tr>
  
  <tr style="height: 24px;">
    <td style="width: 167.083px; height: 24px;">
      Change Date
    </td>
    
    <td style="width: 495.917px; height: 24px;">
      This is displayed in place of Start Date for change assignment. The date will be used as End Date for the original member, and Start Date for the new member.
    </td>
  </tr>
  
  <tr style="height: 24px;">
    <td style="width: 167.083px; height: 24px;">
      End Date
    </td>
    
    <td style="width: 495.917px; height: 24px;">
      The date the member ceased (or ceases) to be a member of Council
    </td>
  </tr>
</table>

Note. Currently there is no validation against concurrency of Start/End date, so these must be entered with care!

The typical operation is where an existing member is replaced by a new one. First of all, make sure the member exists in the People section, taking care not to duplicate an entry. Then click on the existing member in the list, and then the CHANGE ASSIGNMENT button. Find the replacement member in the list, enter the changeover date (usually the date of the next meeting), and then UPDATE.

Where membership has ceased, and no replacement is available, select CHANGE DETAILS, and set the End Date - usually to the date of next meeting, but may need to be to the date of resignation. When the replacement member becomes available, this person will need to be added in using NEW ITEM (once the People section has been populated).

Occasionally a member will cease to be a member of one association, but get elected for another. This will require END DATE to be set for the current association, and then add back in as NEW ITEM (or CHANGE ASSIGNMENT) for the new one. This will create a new record for the current member. Any committee membership (Role Assignment) should also be moved over to the new member.
