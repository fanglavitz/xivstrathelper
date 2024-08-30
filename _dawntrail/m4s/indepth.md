---
layout: default
title: M4S
nav_exclude: true
permalink: /Dawntrail/m4s/indepth/
---
<script>
      const expandElements = shouldExpand => {
        let detailsElements = document.querySelectorAll("details");

        detailsElements = [...detailsElements];

        if (shouldExpand) {
            detailsElements.map(item => item.setAttribute("open", shouldExpand));
        } else {
            detailsElements.map(item => item.removeAttribute("open"));
        }
    };
</script>
<button type="button" name="button" class="btn" onClick="expandElements(true)">Expand All</button> <button type="button" name="button" class="btn" onClick="expandElements(false)">Collapse All</button>
<dl>
  <dt>0:15</dt>
  <dd>
    <font color="Crimson">Wrath of Zeus</font>
  </dd>
  <dt>0:39</dt>
  <dd>
    <details><summary><font size="4" color="LightBlue">Bewitching Flight</font></summary>
      Wicked Thunder will teleport north and start firing lasers from her wings. At the same time 
    </details>
  </dd>
</dl>
