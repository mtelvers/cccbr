---
title: Record Peals
date: 2016-11-17 16:50:54.000000000 +00:00
author: Andrew Hall
layout: single
xyz_fbap:
- '1'
---
**Record Peals** are held in two underlying tables (+ one reference table), maintained by a single form. The data originates from that displayed on the original CCCBR site, which lacks structure and consistency. It is hoped that this can be improved over the course of time.

The list of record peals shows sufficient information for the peal to be identified. Click on the ID to go to the detail page (or NEW ITEM to create a new peal). This allows the following data to be entered.

<table>
  <tr>
    <td style="width: 167.45px;">
      <strong>Label</strong>
    </td>
    
    <td style="width: 497.55px;">
      <strong>Details</strong>
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      Method
    </td>
    
    <td style="width: 497.55px;">
      This should be the method name <em>without</em> the stage name (Minor, Major etc) or (for Spliced) the number of methods. These will be appended by the system for display.
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      Standard Method
    </td>
    
    <td style="width: 497.55px;">
      If YES the peal will be included in the &#8216;Standard Methods&apos; page.
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      Stage
    </td>
    
    <td style="width: 497.55px;">
      Minimus to Twenty-Two currently catered for. For a new stage, this will need to be added into the relevant table by a Database Administrator.
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      Changes
    </td>
    
    <td style="width: 497.55px;">
      Number of changes rung. This can be null as the length of some earlier peals is not known, otherwise a minimum value of 5000.
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      Date
    </td>
    
    <td style="width: 497.55px;">
      The date rung (or started). This is used to sort peals into date order. There was one peal (40320 Bob Major) which went over two dates in the summary. As this was not displayed as such in the detail pages, this subtle piece of information is not missing. Maybe it should go in a note to the peal?
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      Methods
    </td>
    
    <td style="width: 497.55px;">
      Number of methods (for spliced). Will default to 1 (even for principles).
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      Principles
    </td>
    
    <td style="width: 497.55px;">
       Number of principles (for spliced). If methods+principles > 1 then (e.g.) &#8216;(1m/1v)&apos; will be displayed after the method name.
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      All-the-work
    </td>
    
    <td style="width: 497.55px;">
       if YES &#8216;All the work&apos;/'(atw&apos;) will be displayed
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      Category
    </td>
    
    <td style="width: 497.55px;">
      First Peal, Record Length, Surpassed Record or Other
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      In Hand
    </td>
    
    <td style="width: 497.55px;">
      YES if a hand bell peal
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      Location
    </td>
    
    <td style="width: 497.55px;">
      Location of the method (e.g. Tower/County or as appropriate for handbell peals)
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      RW Ref
    </td>
    
    <td style="width: 497.55px;">
      Ringing World Reference. [TODO. There is also provision for a bellboard reference, but this is currently disabled]
    </td>
  </tr>
</table>

Detail Pages Information is displayed on the Detail Pages.

<table>
  <tr>
    <td style="width: 167.45px;">
      Enable Details Page
    </td>
    
    <td style="width: 497.55px;">
      If YES, then a link to a details page is enabled in the summary page
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      Society
    </td>
    
    <td style="width: 497.55px;">
       Society rung for
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      Tower
    </td>
    
    <td style="width: 497.55px;">
      Tower (or location for handbells)
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      Time
    </td>
    
    <td style="width: 497.55px;">
      Time for the peal. Format is h[h]:mm
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      Composer
    </td>
    
    <td style="width: 497.55px;">
      Name of composer.
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      1 to 16
    </td>
    
    <td style="width: 497.55px;">
      Ringer. For handbells 1 will display as 1-2, 2 as 3-4 etc in the display ed page
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      Footnote
    </td>
    
    <td style="width: 497.55px;">
      Any footnote to the peal. Free format.
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      Umpires
    </td>
    
    <td style="width: 497.55px;">
      One per line please
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      Composition
    </td>
    
    <td style="width: 497.55px;">
      Composition. Free format text. This is best pasted in from a separate document. On the display page it will be free format text.
    </td>
  </tr>
</table>

The Record Peal pages are all displayed using a single short-code ([[cccbr\_sc\_record_peals]]), with current pages as per the current site. However, as this is now pulled from a database, the peals form a single list ordered by method, stage and number of changes.

The short code has several optional parameters which control what is displayed.

<table>
  <tr>
    <td style="width: 167.45px;">
      inhand
    </td>
    
    <td style="width: 497.55px;">
      TRUE: Include handbell peals only<br />FALSE: Include tower bell peals only<br />NULL (default): Include both
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      include
    </td>
    
    <td style="width: 497.55px;">
      A list of categories to be included. Default is &#8216;first, surpassed, long&apos;.<br />The other category is &#8216;other&apos;.
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      standard
    </td>
    
    <td style="width: 497.55px;">
      TRUE: Include standard methods only<br />FALSE: Exclude standard methods<br />NULL (default): Include all methods
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      stagefr
    </td>
    
    <td style="width: 497.55px;">
      The lowest stage to include (default is 0), e.g. 4 for minimus, 12 for maximums Spliced caters/royal is 9.5!
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      stageto
    </td>
    
    <td style="width: 497.55px;">
      The highest stage to include (default is 99). Currently this goes up to 22.
    </td>
  </tr>
</table>
