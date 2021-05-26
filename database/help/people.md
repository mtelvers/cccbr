---
id: 6330
title: People Help
date: 2016-10-19T19:28:57+00:00
author: Andrew Hall
layout: single
guid: http:///?page_id=6330
wp_featherlight_disable:
  - ""
xyz_fbap:
  - "1"
---
The **People** dataset defines people, together with their contact details. There are actually two underlying tables (person and address) but that should not be of any direct concern.

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
      Title
    </td>
    
    <td style="width: 497.55px;">
      Title (e.g. Sir). Mr, Mrs, Miss etc should not normally be used
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      Forename(s)
    </td>
    
    <td style="width: 497.55px;">
      Forename(s) (preferred - or initials) separated by space
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      Surname
    </td>
    
    <td style="width: 497.55px;">
      Surname. This is a separate field for sorting
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      Honours etc
    </td>
    
    <td style="width: 497.55px;">
      Enter any honours, qualifications that should appear after the name (currently only relevant to biographical data).
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      Distinct ID
    </td>
    
    <td style="width: 497.55px;">
      This is used to distinguish two people with identical names in the pull down lists. It is not visible externally.
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      Change of Name
    </td>
    
    <td style="width: 497.55px;">
      Selecting No will cause the existing record in the Name table to be updated (if there are any changes). Selecting Yes will add a new record to the Name table (so the person can be found under their old name - although this feature is not currently implemented). Note that both records will be displayed in the listing of members - the current one marked as Pref(erred).
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      Address
    </td>
    
    <td style="width: 497.55px;">
      The full address, excluding post/zip code.
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      Country
    </td>
    
    <td style="width: 497.55px;">
      The country [currently missing - oops]
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      Post/Zip code
    </td>
    
    <td style="width: 497.55px;">
      Post code. Held separately as it may come in useful this way (!)
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      Address Visible
    </td>
    
    <td style="width: 497.55px;">
      If YES the address will be visible to all - otherwise only to privileged users (i.e. with CCCBR Read Members Data)
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      Upload New Image
    </td>
    
    <td style="width: 497.55px;">
      Use this to upload an image of the person. Currently used only for Officers and selected Committees. This should be an image file (i.e. jpg or .gif) less than 256Kb.
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      Email
    </td>
    
    <td style="width: 497.55px;">
      Email address. Just one is to be preferred - separate with &#8216;;&apos; if needed.
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      Email Visible
    </td>
    
    <td style="width: 497.55px;">
      If YES the email address will be visible to all - otherwise only to privileged users (i.e. with CCCBR Read Members Data)
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      Phone Number(s)
    </td>
    
    <td style="width: 497.55px;">
      Phone number. Just one is to be preferred - separate with &#8216;;&apos; if needed.
    </td>
  </tr>
  
  <tr>
    <td style="width: 167.45px;">
      Phone Visible
    </td>
    
    <td style="width: 497.55px;">
      If YES the phone numner will be visible to all - otherwise only to privileged users (i.e. with CCCBR Read Members Data)
    </td>
  </tr>
</table>

 
