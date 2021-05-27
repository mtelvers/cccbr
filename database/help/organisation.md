---
title: Organisation Help
date: 2016-10-19 18:24:44.000000000 +00:00
author: Andrew Hall
layout: single
xyz_fbap:
- '1'
---
The **Organisation** table is a hierarchical table in that each record (apart from the master - the one for the Central Council itself) points to its parent record.  The initial structure is (e.g.):

Central Council  
Additional Members  
Affiliated Societies  
List of societies  
&#8230;  
Alliances  
List of alliances  
&#8230;  
Committees  
List of committees  
Ex Officio Members  
Life Members  
Ringing Societies  
List of societies  
&#8230;  
University Societies  
List of societies  
&#8230;

In the normal course, it should not be necessary to amend the top layers - only the lists of societies and committees which, from time to time may appear, disappear or need amendment.

<table style="height: 121px; width: 681px;">
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
      Full Name
    </td>
    
    <td style="width: 497.55px;">
      Full (i.e. displayed) name of the organisation layer. 100 characters.
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      Short Name
    </td>
    
    <td style="width: 497.55px;">
      An abbreviated name. This should not be changed once assigned please! It will be used in some of the code to find particular records (as the name could well change over time). Also restricted to the (lowercase) characters a-z, 0-9 and &#8216;-&#8216;
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      Parent
    </td>
    
    <td style="width: 497.55px;">
      Pick one from the list. Unless, of course, this is the master record.
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      Members
    </td>
    
    <td style="width: 497.55px;">
      The number of directly electable members. This should be non-zero for affiliated societies, and Life/Additional/Ex-Officio members and zero for everything else.
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      Can have Roles?
    </td>
    
    <td style="width: 497.55px;">
      If roles can apply to this part of the organisation (e.g. Committee, Officers) then Yes, otherwise No
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      Home Url
    </td>
    
    <td style="width: 497.55px;">
      The Url for the organisation. This must include the http://. Typically for affiliated societies.
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      Contact Email
    </td>
    
    <td style="width: 497.55px;">
      Contact email. Must be a valid email address. Typically for affiliated societies
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      Start Date
    </td>
    
    <td style="width: 497.55px;">
      The date on which this entity came (or comes - it can be in the future) into existence.
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      End Date
    </td>
    
    <td style="width: 497.55px;">
      The date on which this entity ceased (or ceases - it can be in the future) to exist. Once End Date has passed, the record will no longer be visible.
    </td>
  </tr>
</table>

 
