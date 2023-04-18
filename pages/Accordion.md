---
title: Accordion
permalink: /accordion/
description: ""
---
<!--Notes for you: 

1. Just make sure to copy everything between <li> and </li> for each and every accordion item

 2. For each accordion item, make sure the id is unique e.g.: accordion1, accordion2, e.t.c.

3. Any content in the accordion is to be done within the <p> </p>

4. To understand HTML, refer to a guide here: go.gov.sg/isomer-html-cheatsheet-->

<ul class="jekyllcodex_accordion">
  <li>
    <input id="accordion1" type="checkbox">
    <label for="accordion1">Simple</label>
    <div>
      <p>This is a simple one line item</p>
    </div>
	</li> 
	
  <li>
    <input id="accordion2" type="checkbox">
    <label for="accordion2">Multi-line Block</label>
    <div>
      <p>This is line 1</p>
      <p>This is line 2<br>
        This is line 3</p>
    </div>
  </li>
	
  <li>
    <input id="accordion3" type="checkbox">
    <label for="accordion3">Multi-line Folded</label>
    <div>
      <p>
        This is all going
        to become just one line\\n even though there are multiple lines
      </p>
    </div>
  </li>
	
  <li>
    <input id="accordion4" type="checkbox">
    <label for="accordion4">Ordered List</label>
    <div>
      <ol>
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
      </ol>
    </div>
  </li>
	
  <li>
    <input id="accordion5" type="checkbox">
    <label for="accordion5">Unordered List</label>
    <div>
      <ul>
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
      </ul>
    </div>
  </li>
	
</ul>