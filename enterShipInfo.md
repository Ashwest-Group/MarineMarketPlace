---
layout: default
permalink: /shiplisting/
title: New Ship Listing
---

<div id="menu">
  <div id="sidenav">
    <a href="/"> Home </a>

    <a href="/about"> About </a>

    <a href="/login"> Login </a>

  </div>
</div>
<div class="main">
 <div id="input">
   <form action="/action_page.php" method="get">
     Ship Name: <input type="text" name="Sname" /><br />
     Company: <input type="text" name="Cname" /><br />
     Flag: <input type="text" name="Flag" /><br />
     IMO Number: <input type="integer" name="IMO" /><br />
     Tonnage: <input type="integer" name="tonnage" /><br />
     <select>
       <option value="Bulk">Bulk</option>
       <option value="Container">Container</option>
       <option value="General">General</option>
       <option value="Ro/Ro">Ro/Ro</option>
       <option value="Tanker">Tanker</option> </select>
       <br />
       Length: <input type="text" name="length" /><br />
       Width: <input type="text" name="width" /><br />
       Draft: <input type="text" name="draft" /><br />
       <input type="submit" value="Submit" />
   </form>
 </div>
</div>
