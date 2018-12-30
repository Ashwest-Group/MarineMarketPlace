---
layout: default
permalink: /newlisting/
title:
---

<div id="menu">
  <div id="sidenav">
    <a href="/home"> Home </a>

    <a href="/about"> About </a>

    <a href="/login"> Login </a>

  </div>
</div>
<div id="main">
  <div id="input">
    <form action="/action_page.php" method="get">
      Title: <input type="text" name="Cname" /><br />
      description: <input type="text" name="description" /><br />
      Availible From: <input type="date" name="availibleFrom" /><br />
      Arrive By: <input type="date" name="arriveBy" /><br />
      pickup Port: <input type="text" name="pickup" /><br />
      Destination Port: <input type="text" name="destination" /><br />
      <input type="radio" name="cargo" value="container" /> Container<br />
      <input type="radio" name="cargo" value="bulk" /> Bulk<br />
      <input type="radio" name="cargo" value="Ro/Ro" /> Ro/Ro<br />
      <input type="radio" name="cargo" value="Liquid" /> liquid<br />
      <input type="radio" name="cargo" value="Out Of Guage" /> out ofguage<br />
      hazardous
      <br/>
      <input type="radio" name="hazardous" value="yes" /> yes<br />
      <input type="radio" name="hazardous" value="no" /> no<br />
      <select>
        <option value="---">---</option>
        <option value="explosives">Explosives</option>
        <option value="flamible">Flamible</option>
        <option value="radioActive">Radio Active</option>
        <option value="Batteries">Batteries</option> </select><br />
      Perishables: <input type="text" name="perishable" /><br />
      <input type="submit" value="Submit" />
    </form>
  </div>
</div>
