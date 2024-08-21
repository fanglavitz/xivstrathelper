---
layout: default
title: M2S
nav_exclude: true
permalink: /dawntrail/m2s/indepth/
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
  <dt>0:10</dt>
  <dd>
    <font size="4" color="Crimson">Call Me Honey</font>
  </dd>
  <dt>0:17</dt>
  <dd>
    <details><summary><font size="4" color="LightBlue">Drop/Splash of Venom</font></summary>
      Drop will store a pair stack for later, Splash will store a spread.
    </details>
  </dd>
  <dt>0:28</dt>
  <dd>
    <details><summary><font size="4" color="LightBlue">Honey Beeline/Tempting Twist</font></summary>
      Honey Beeline will cast a line aoe the width of the boss hitbox, followed by 8 circle aoes on the sides, leaving a safe line down the center.
Tempting Twist will be a donut aoe first, followed by a different set of circles leaving space on each intercard safe.
Resolve the stored spread or pair stack here.
    </details>
  </dd>
  <dt>0:39</dt>
  <dd>
    <details><summary><font size="4" color="LightBlue">Drop/Splash of Venom</font></summary>
      Drop will store a pair stack for later, Splash will store a spread.
      This Drop or Spread will always be the opposite of the first.
    </details>
  </dd>
  <dt>0:47</dt>
  <dd>
    <details><summary><font size="4" color="LightBlue">Honey Beeline/Tempting Twist</font></summary>
      Honey Beeline will cast a line aoe the width of the boss hitbox, followed by 8 circle aoes on the sides, leaving a safe line down the center.
Tempting Twist will be a donut aoe first, followed by a different set of circles leaving space on each intercard safe.
Resolve the stored spread or pair stack here.
      This will always be the opposite aoe as the first one.
    </details>
  </dd>
  <dt>0:59</dt>
  <dd>
    <details><summary><font size="4" color="DodgerBlue">Killer Sting/Stinging Slash</font></summary>
      Killer Sting is a tank stack, Stinging Slash is a conal cleave on first and second aggro.
    </details>
  </dd>
  <dt>1:12</dt>
  <dd>
    <details><summary><font size="4" color="Crimson">Honey B. Live: 1st Beat</font></summary>
      Hard hitting raidwide that also distributes 8 hearts randomly among all players. you will receive a debuff that acts as a dot and scales with the number of hearts collected. Getting hit by anything during this phase will increase your number of hearts, and if you acquire 4, you will take a lot of damage and be stunned for a few seconds, and the boss will heal 1% hp and receive a permanent stacking damage up buff.
    </details>
  </dd>
  <dt>1:28</dt>
  <dd>
    <details><summary><font size="4" color="LightBlue">Center/Outerstage Combo</font></summary>
      Centerstage and Outerstage are the same 3 sets of aoes, just reversed. the first will always be a set of either cardinal cones with a donut or intercard cones with a point-blank. the middle will always be a large cross aoe towards cardinals, and the last will always be the opposite of the first. center starts with the donut/cardinal cones, and outer starts with the point blank/intercard cones.
    </details>
  </dd>
  <dt>1:42</dt>
  <dd>
    <details><summary><font size="4" color="LightBlue">Love Me Tender(Towers)</font></summary>
      Towers will start spawning in random configurations, at 3 possible distances from the boss. the closest at the edge of her hitbox, the middle at just inside max melee, and the furthest at the wall. soaking a tower will give that player a heart, and an unsoaked tower will give raidwide damage and give everyone a heart. 11 total towers will spawn.
    </details>
  </dd>
  <dt>2:16</dt>
  <dd>
    <details><summary><font size="4" color="LightBlue">Loveseeker</font></summary>
      There will be a point blank aoe, then hearts will start floating away from the boss in a fixed triple swirl pattern, and hearts will start floating in from the outside of the arena towards random players.
    </details>
  </dd>
  <dt>2:30</dt>
  <dd>
    <details><summary><font size="4" color="MediumSeaGreen">Love Me Tender(stack)</font></summary>
      Hearts will stop spawning and a stack marker will appear on a random player with the least number of hearts. This stack will do a small amount of damage to up to 4 players and distribute 4 hearts to players who soak it.
    </details>
  </dd>
  <dt>2:49</dt>
  <dd>
    <details><summary><font size="4" color="LightBlue">Center/Outerstage Combo</font></summary>
      Centerstage and Outerstage are the same 3 sets of aoes, just reversed. the first will always be a set of either cardinal cones with a donut or intercard cones with a point-blank. the middle will always be a large cross aoe towards cardinals, and the last will always be the opposite of the first. center starts with the donut/cardinal cones, and outer starts with the point blank/intercard cones.
    </details>
  </dd>
  <dt>3:07</dt>
  <dd>
    <details><summary><font size="4" color="Crimson">Honey B. Finale</font></summary>
      Large raidwide damage signaling the end of the beat phase.
    </details>
  </dd>
  <dt>3:21</dt>
  <dd>
    <details><summary><font size="4" color="DodgerBlue">Killer Sting/Stinging Slash</font></summary>
      Killer Sting is a tank stack, Stinging Slash is a conal cleave on first and second aggro.
    </details>
  </dd>
  <dt>3:29-4:00</dt>
  <dd>
    <details><summary><font size="4" color="LightBlue">Alarm Pheromones 1</font></summary>
      Adds will start spawning around the arena and pointing arrows at random players, alternating all supports and all dps, until 16 have been baited.
    </details>
  </dd>
  <dt>4:07</dt>
  <dd>
    <details><summary><font size="4" color="Crimson">Honey B. Live: 2nd Beat</font></summary>
      Raidwide that gives 2 supports and 2 dps one heart each. Getting hit by anything during this phase will increase your number of hearts, and if you acquire 4, you will take a lot of damage and be stunned for a few seconds, and the boss will heal 1% hp and receive a permanent stacking damage up buff.
    </details>
  </dd>
  <dt>4:22</dt>
  <dd>
    <details><summary><font size="4" color="LightBlue">Drop of/Spread Love</font></summary>
      Drop will store a pair stack for later, Spread will store a spread.
    </details>
  </dd>
  <dt>4:32</dt>
  <dd>
    <details><summary><font size="4" color="MediumSeaGreen">Love Me Tender</font></summary>
      2 people with 0 hearts will start baiting large circle aoes underneath them, then after the 3rd one, 2 of them will get a stack marker. these can safely be stacked, as they do light damage, and the 8 hearts collectively will be split the same either way. at the same time, a 1 heart dps and a 1 heart support will recieve a spread aoe that will give a heart when hit, and 2 towers will spawn. the 2 one hearts will without a spread will need to take these.
    </details>
  </dd>
  <dt>4:56</dt>
  <dd>
    <details><summary><font size="4" color="LightBlue">Honey Beeline/Tempting Twist</font></summary>
      Honey Beeline will cast a line aoe the width of the boss hitbox, followed by 8 circle aoes on the sides, leaving a safe line down the center.
Tempting Twist will be a donut aoe first, followed by a different set of circles leaving space on each intercard safe.
Resolve the stored spread or pair stack here.
    </details>
  </dd>
  <dt>5:10</dt>
  <dd>
    <details><summary><font size="4" color="Crimson">Honey B. Finale</font></summary>
      Large raidwide damage signaling the end of the beat phase.
    </details>
  </dd>
  <dt>5:33-6:07</dt>
  <dd>
    <details><summary><font size="4" color="LightBlue">Alarm Pheromones 2</font></summary>
      This time, 4 adds will spawn and shoot arrows diagonally equidistant from one another, leaving a square safe area center, and 4 safe squares on the outside. after each set of lines go off, the lines shift, koving the outer safe zones and making the center square smaller. This happens 6 times total. On the first through fourth sets, 1 support and 1 dps will get a red marker indicating they will be hit by an aoe and drop a poison puddle. This aoe gives a vuln to ensure you cannot be hit by 2 of them. On the sixth set, one support and one dps will be targeted for a stack marker.
    </details>
  </dd>
  <dt>6:16</dt>
  <dd>
    <details><summary><font size="4" color="DodgerBlue">Killer Sting/Stinging Slash</font></summary>
      Killer Sting is a tank stack, Stinging Slash is a conal cleave on first and second aggro.
    </details>
  </dd>
  <dt>6:28</dt>
  <dd>
    <details><summary><font size="4" color="LightBlue">Honey Beeline/Tempting Twist</font></summary>
      Honey Beeline will cast a line aoe the width of the boss hitbox, followed by 8 circle aoes on the sides, leaving a safe line down the center.
Tempting Twist will be a donut aoe first, followed by a different set of circles leaving space on each intercard safe.
Resolve the stored spread or pair stack here.
    </details>
  </dd>
  <dt>6:46</dt>
  <dd>
    <details><summary><font size="4" color="Crimson">Honey B. Live: 3rd Beat</font></summary>
      Raidwide will give out no hearts this time, but everyone will receive a debuff all supports and all dps each receiving one with the same timer on it. when this debuff expires, it will explode into a large aoe that gives the debuff player a heart and does significant damage to anyone close by.
    </details>
  </dd>
  <dt>6:59</dt>
  <dd>
    <details><summary><font size="4" color="LightBlue">Drop of/Spread Love</font></summary>
      Drop will store a pair stack for later, Splash will store a spread.
    </details>
  </dd>
  <dt>7:08</dt>
  <dd>
    <details><summary><font size="4" color="LightBlue">Center/Outerstage Combo</font></summary>
      Centerstage and Outerstage are the same 3 sets of aoes, just reversed. the first will always be a set of either cardinal cones with a donut or intercard cones with a point-blank. the middle will always be a large cross aoe towards cardinals, and the last will always be the opposite of the first. center starts with the donut/cardinal cones, and outer starts with the point blank/intercard cones.
    </details>
  </dd>
  <dt>7:18</dt>
  <dd>
    <details><summary><font size="4" color="Orange">Big Burst</font></summary>
      The first set of debuffs will expire here, and 4 towers will spawn in either a vertical or horizontal rectangle shape. The towers must be soaked a few seconds after the aoes go off.
    </details>
  </dd>
  <dt>7:27</dt>
  <dd>
    <details><summary><font size="4" color="LightBlue">Center/Outerstage Combo</font></summary>
      Centerstage and Outerstage are the same 3 sets of aoes, just reversed. the first will always be a set of either cardinal cones with a donut or intercard cones with a point-blank. the middle will always be a large cross aoe towards cardinals, and the last will always be the opposite of the first. center starts with the donut/cardinal cones, and outer starts with the point blank/intercard cones.
    </details>
  </dd>
  <dt>7:39</dt>
  <dd>
    <details><summary><font size="4" color="Orange">Big Burst</font></summary>
      The second set of debuffs will expire here, and 4 towers will spawn in either a vertical or horizontal rectangle shape. The towers must be soaked a few seconds after the aoes go off.
    </details>
  </dd>
  <dt>7:52</dt>
  <dd>
    <details><summary><font size="4" color="LightBlue">Honey Beeline/Tempting Twist</font></summary>
      Honey Beeline will cast a line aoe the width of the boss hitbox, followed by 8 circle aoes on the sides, leaving a safe line down the center.
Tempting Twist will be a donut aoe first, followed by a different set of circles leaving space on each intercard safe.
Resolve the stored spread or pair stack here.
    </details>
  </dd>
  <dt>8:04</dt>
  <dd>
    <details><summary><font size="4" color="Crimson">Honey B. Finale</font></summary>
      Large raidwide damage signaling the end of the beat phase.
    </details>
  </dd>
  <dt>0:59</dt>
  <dd>
    <details><summary><font size="4" color="DodgerBlue">Killer Sting/Stinging Slash</font></summary>
      Killer Sting is a tank stack, Stinging Slash is a conal cleave on first and second aggro.
    </details>
  </dd>
  <dt>8:31</dt>
  <dd>
    <details><summary><font size="4" color="Crimson">Rotten Heart</font></summary>
      Huge raidwide that will give every player one of 2 debuffs, with 4 possible timers of each. if these debuffs are allowed to expire, those players will immediately die. when 2 players with opposite debuffs get close enough, the debuffs cleanse themselves and do raidwide damage (note that you can cleanse with a dead body if a player dies before they should cleanse). the raidwide from a cleansed debuff pair also applies a 6 second magic vuln that will lead to a wipe if it is still on when another pair is cleansed or when the boss does her raidwide. these debuffs must be cleansed before the timer hits 4 seconds or the vuln will not fall off before the next raidwide.
    </details>
  </dd>
  <dt>8:43~</dt>
  <dd>
    <details><summary><font size="4" color="Crimson">Big Burst</font></summary>
      First set of cleanses, time is an approximation.
    </details>
  </dd>
  <dt>8:51</dt>
  <dd><font size="4" color="Crimson">Call Me Honey</font>
  </dd>
  <dt>8:57~</dt>
  <dd>
    <details><summary><font size="4" color="Crimson">Big Burst</font></summary>
      Second set of cleanses, time is an approximation.
    </details>
  </dd>
  <dt>9:09</dt>
  <dd><font size="4" color="Crimson">Call Me Honey</font>
  </dd>
  <dt>9:16~</dt>
  <dd>
    <details><summary><font size="4" color="Crimson">Big Burst</font></summary>
      Third set of cleanses, time is an approximation.
    </details>
  </dd>
  <dt>9:26</dt>
  <dd><font size="4" color="Crimson">Call Me Honey</font>
  </dd>
  <dt>9:35~</dt>
  <dd>
    <details><summary><font size="4" color="Crimson">Big Burst</font></summary>
      Last set of cleanses, time is an approximation.
    </details>
  </dd>
  <dt>9:43</dt>
  <dd><font size="4" color="Crimson">Call Me Honey</font>
  </dd>
  <dt>10:03</dt>
  <dd>
    <details><summary><font size="4" color="Crimson">Sheer Heart Attack</font></summary>
      Every player will receive 4 hearts and be stunned, the boss will heal 8% and get 8 stacks of damage up. this effectively serves as her enrage.
    </details>
  </dd>
  <dt>10:05</dt>
  <dd>
    <font size="4" color="DarkRed">Honey B. Finale</font>
  </dd>
</dl>
