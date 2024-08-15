---
layout: default
title: m1s
nav_exclude: true
permalink: /dawntrail/m1sindepth/
---
// Reference the toggle link
const xa = document.getElementById('expAll');

// Register link on click event
xa.addEventListener('click', function(e) {

  /* Toggle the two classes that represent "state"
  || determined when link is clicked
  */
  e.currentTarget.classList.toggle('exp');
  e.currentTarget.classList.toggle('col');

  // Collect all <details> into a NodeList
  const details = document.querySelectorAll('details');

  /* Convert NodeList into an array then iterate
  || through it...
  */
  Array.from(details).forEach(function(obj, idx) {

    /* If the link has the class .exp...
    || make each <detail>'s open attribute true
    */
    if (e.currentTarget.classList.contains('exp')) {
      obj.open = true;
      // Otherwise remove [open]
    } else {
      obj.removeAttribute('open');
    }

  });

}, false);

<a href='#/' id='expAll' class='col'>Expand All</a>
<dl>
  <dt>0:08</dt>
  <dd>
    <details><summary>Quadruple Crossing</summary>
      Black Cat will target the closest 4 players with a cone aoe twice. the baited cones apply a slashing vuln debuff which will result in death if hit by 2, so the party will have to divide into 2 sets of 4 players to bait. after both sets of cones, she will follow by again sending 2 sets of 4 cone aoes, first where the first set were baited, then where the second set were. simply stand away from where the first set were baited, then move if necessary to avoid the 2nd set.
    </details>
  </dd>
  <dt>0:27</dt>
  <dd>
    <details><summary><font color="blue">Biscuit Maker</font></summary>
      2 hit tankbuster with vuln.
    </details>
  </dd>
  <dt>0:52</dt>
  <dd>
    <details><summary>One-Two Paw</summary>
      Black Cat which will cleave one half of the arena, then the other, telegraphed by the glowing claws at her sides. she will then spawn 2 clones, who will repeat the same set of cleaves as the boss. this will leave a small pizza slice of the arena safe. start there, then dodge through the boss to the pizza slice on the opposite side. as you dodge to the second safe spot, Black Cat will start casting either quadruple swipe or double swipe, signifying a support/dps pair stack, or a light party stack on healers, respectively.
    </details>
  </dd>
  <dt>1:35</dt>
  <dd>
    <details><summary>Leaping Quadruple Crossing</summary>
      Black Cat will tether left or right, and shortly after will jump to the position tethered and repeat the first mechanic’s baited cleaves. this time, on the second non-targeted cleave, she will repeat either dps/support pairs or light party stacks, whichever was cast during the clones.
    </details>
  </dd>
  <dt>1:57</dt>
  <dd>
    <font color="red">Bloody Scratch</font>
  </dd>
  <dt>2:16</dt>
  <dd>
    <details><summary>Mouser</summary>
      Black Cat will start indicating aoes on various tiles around the arena. each tile will be hit once, and all but 4 will be hit twice. when a tile is hit once, it cracks, then when hit again, will break and fall, leaving a hole. dodge onto a tile after it gets hit, and make sure you end up on a tile that wont be hit a second time. the final safe tiles will form a zigzag pattern through the middle. 4 tiles will reform whole, leaving either 2 rows or 2 columns safe.
    </details>
  </dd>
  <dt>2:26-3:30</dt>
  <dd>
    <details><summary>Mouser 1 Phase</summary>
      Copycat will spawn an add either north or west, whichever is the end of the safe squares. this add will perform one of 2 attacks, repeated 4 times, on each of either all supports or all dps. each attack will happen twice. one player will be marked with a paw mark over their head to indicate who is being targeted. regardless of which attack the clone is charging, when it hits the targeted player, it will also hit all tiles in a vertical and horizontal line of the player, doing small damage and unsurvivable knockback to anyone hit (you can anti-knockback this if desired). if the add raises her glowing left arm, she will slam down and damage the tile the targeted player is standing on. if the tile was already cracked, it will fall through and the player will die. if the add crouches down and her right arm glows, the targeted player will be knocked into the air and forward one tile’s worth of distance. when that player lands, the tile they land on will be damaged, and will fall through if already cracked.
    </details>
  </dd>
  <dt>3:38</dt>
  <dd>
    <details><summary><font color="cyan">Biscuit Maker</font></summary>
      2 hit tankbuster with vuln.
    </details>
  </dd>
  <dt>3:50</dt>
  <dd>
    <details><summary>Platform Reform</summary>
      Black Cat will start reforming the outside edge tiles and charging a knockback. this knockback cannot be prevented, but can be cancelled with a movement skill. 4 tiles will be forming faster, a pair each on opposite corners. get knocked into one of those corners, then spread out to resolve the spread aoes on each player after.
    </details>
  </dd>
  <dt></dt>
  <dd>
    <details><summary>title</summary>
    </details>
  </dd>
  <dt></dt>
  <dd>
    <details><summary>title</summary>
    </details>
  </dd>
  <dt></dt>
  <dd>
    <details><summary>title</summary>
    </details>
  </dd>
  <dt></dt>
  <dd>
    <details><summary>title</summary>
    </details>
  </dd>
  <dt></dt>
  <dd>
    <details><summary>title</summary>
    </details>
  </dd>
  <dt></dt>
  <dd>
    <details><summary>title</summary>
    </details>
  </dd>
  <dt></dt>
  <dd>
    <details><summary>title</summary>
    </details>
  </dd>
  <dt></dt>
  <dd>
    <details><summary>title</summary>
    </details>
  </dd>
  <dt></dt>
  <dd>
    <details><summary>title</summary>
    </details>
  </dd>
  <dt></dt>
  <dd>
    <details><summary>title</summary>
    </details>
  </dd>
  <dt></dt>
  <dd>
    <details><summary>title</summary>
    </details>
  </dd>
  <dt></dt>
  <dd>
    <details><summary>title</summary>
    </details>
  </dd>
  <dt></dt>
  <dd>
    <details><summary>title</summary>
    </details>
  </dd>
  <dt></dt>
  <dd>
    <details><summary>title</summary>
    </details>
  </dd>
  <dt></dt>
  <dd>
    <details><summary>title</summary>
    </details>
  </dd>
  <dt></dt>
  <dd>
    <details><summary>title</summary>
    </details>
  </dd>
</dl>
