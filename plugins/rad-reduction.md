---
layout: default
title: Item Radiation Reduction
---

# Item Radiation Reduction

This tool helps calculate the amount of radiation reduction an item has. It
shows the radiation cost for each bonus, and then the total reduction as
compared to the total radiation cost it should have vs the radiation the item
actually has.

[Download Here]({{ site.baseurl }}/public/downloads/GW2_Item_Rad_Cut.xml)

The output is color coded for the Rad Cut line. The first percentage is the
radiation discount the item has compared to the total radiation cost the item
should have for all bonus's. It is colored based on how much reduction the item
of the given rarity and quality should have. Yellow means the item is within
the normal range of reduction. Green means the item has a higher radiation
reduciton than other items of that rarity/quality normally have. Red means the
item has a lower radiation reduction than other items. Red is usually an
indicator of a missing bonus from the plugin, or a possible bug in the item
generation code on the mud.

For items in the correct ranges, the 2nd percentage (available) is displayed.
This tells you that for its given rarity/quality how good a rad cut you got, and
not just how good overall the item is. It shows different colors based on how
high in its given range the item received a bonus for. You can see the bonus
ranges for each rarity/quality combination in the following chart:

||Common|Uncommon|Rare|
|---|---|---|---|
Magical|-5% to 10%|10% to 25%|25% to 40%
Legendary|2% to 17%|17% to 32%|32% to 44%
Mythical|9% to 24%|24% to 39%|36% to 48%
Relic|16% to 31%|31% to 43%|40% to 50%
Artifact|23% to 38%|35% to 47%|40% to 50%

Example Output:

<!-- Produced by MUSHclient v 5.03 - www.mushclient.com -->
<pre style="background-color: black;"><code><font size="2" face="Courier New, FixedSys, Lucida Console, Courier New, Courier"><font color="#C0C0C0">You examine a gold </font><font color="#FF00FF"><u>ring</u></font><font color="#C0C0C0"> of hitting.
-------------------------------------------------------------------------------
Rumour has it that the first ring was crafted to represent the Serpent itself,
and indeed, many rings possess magical powers.  Even the plainest rings with no
apparent magical aura have been known to win love and bind friendships.
-------------------------------------------------------------------------------
</font><font color="#FFFFFF">Skill type</font><font color="#C0C0C0"> : Improvised (no associated Mastery talent).
</font><font color="#FFFFFF">Usage</font><font color="#C0C0C0">      : Worn, or </font><font color="#FFFFFF">wield</font><font color="#C0C0C0">ed as an improvised weapon, but cannot be thrown.
</font><font color="#FFFFFF">Size/reach</font><font color="#C0C0C0"> : Adds </font><font color="#FF0000">zero</font><font color="#C0C0C0"> encumbrance, and has a melee reach of </font><font color="#00FFFF">zero</font><font color="#C0C0C0"> feet.
</font><font color="#FFFFFF">Material</font><font color="#C0C0C0">   : Gold with 55% durability.
</font><font color="#FFFFFF">Techniques</font><font color="#C0C0C0"> : 2 (0 mounted, 0 style-specific and 1 behind the scenes).
-------------------------------------------------------------------------------
</font><font color="#FFFFFF">Condition</font><font color="#C0C0C0">  : </font><font color="#00FFFF">Fifty</font><font color="#C0C0C0"> (out of </font><font color="#00FFFF">fifty</font><font color="#C0C0C0">).
</font><font color="#FFFFFF">Attack</font><font color="#C0C0C0">     : </font><font color="#00FFFF">+0</font><font color="#C0C0C0"> (</font><font color="#00FFFF">+0</font><font color="#C0C0C0">, </font><font color="#0000FF">+0</font><font color="#C0C0C0">, </font><font color="#FF00FF">+0</font><font color="#C0C0C0"> or </font><font color="#FF0000">+0</font><font color="#C0C0C0"> depending on condition).
</font><font color="#FFFFFF">Defence</font><font color="#C0C0C0">    : </font><font color="#00FFFF">+0</font><font color="#C0C0C0"> (</font><font color="#00FFFF">+0</font><font color="#C0C0C0">, </font><font color="#0000FF">+0</font><font color="#C0C0C0">, </font><font color="#FF00FF">+0</font><font color="#C0C0C0"> or </font><font color="#FF0000">+0</font><font color="#C0C0C0"> depending on condition).
</font><font color="#FFFFFF">Damage</font><font color="#C0C0C0">     : </font><font color="#00FFFF">+0</font><font color="#C0C0C0"> (</font><font color="#00FFFF">+0</font><font color="#C0C0C0">, </font><font color="#0000FF">+0</font><font color="#C0C0C0">, </font><font color="#FF00FF">+0</font><font color="#C0C0C0"> or </font><font color="#FF0000">+0</font><font color="#C0C0C0"> depending on condition).
</font><font color="#FFFFFF">Cooldown</font><font color="#C0C0C0">   : </font><font color="#00FFFF">4</font><font color="#C0C0C0">, </font><font color="#0000FF">4</font><font color="#C0C0C0">, </font><font color="#FF00FF">5</font><font color="#C0C0C0"> or </font><font color="#FF0000">5</font><font color="#C0C0C0"> seconds, depending on wielders encumbrance.
</font><font color="#FFFFFF">Layer</font><font color="#C0C0C0">      : Underwear.
-------------------------------------------------------------------------------
</font><font color="#FFFFFF">Magic type</font><font color="#C0C0C0"> : A common mythical item with 749 points of radiation.
</font><font color="#FFFFFF">Bonus      </font><font color="#C0C0C0">: +99 to Attack</font><font color="#0080FF"> </font><font color="#C0C0C0">(</font><font color="#008000">495</font><font color="#C0C0C0"> Radiation)
</font><font color="#FFFFFF">Bonus      </font><font color="#C0C0C0">: +18 to Damage</font><font color="#0080FF"> </font><font color="#C0C0C0">(</font><font color="#008000">180</font><font color="#C0C0C0"> Radiation)
</font><font color="#FFFFFF">Bonus      </font><font color="#C0C0C0">: +7 to Mettle</font><font color="#0080FF"> </font><font color="#C0C0C0">(</font><font color="#008000">280</font><font color="#C0C0C0"> Radiation)
</font><font color="#FFFFFF">Rad Cut    </font><font color="#C0C0C0">: </font><font color="#FFFF00">21.57</font><font color="#C0C0C0">% Reduction (</font><font color="#00FFFF">83.33</font><font color="#C0C0C0">% avail)
-------------------------------------------------------------------------------

You examine a pair of copper </font><font color="#FF00FF"><u>battle bracers</u></font><font color="#C0C0C0"> of armour.
-------------------------------------------------------------------------------
These heavy spiked bracers can be strapped to your arms, although they also
extend down the back of your hands, protecting both locations from damage.
-------------------------------------------------------------------------------
</font><font color="#FFFFFF">Skill type</font><font color="#C0C0C0"> : Improvised (no associated Mastery talent).
</font><font color="#FFFFFF">Usage</font><font color="#C0C0C0">      : Worn, or </font><font color="#FFFFFF">wield</font><font color="#C0C0C0">ed as an improvised weapon, but cannot be thrown.
</font><font color="#FFFFFF">Size/reach</font><font color="#C0C0C0"> : Adds </font><font color="#FF0000">three</font><font color="#C0C0C0"> encumbrance, and has a melee reach of </font><font color="#00FFFF">zero</font><font color="#C0C0C0"> feet.
</font><font color="#FFFFFF">Material</font><font color="#C0C0C0">   : Copper with 60% durability.
</font><font color="#FFFFFF">Techniques</font><font color="#C0C0C0"> : 4 (0 mounted, 0 style-specific and 1 behind the scenes).
</font><font color="#FFFFFF">Special</font><font color="#C0C0C0">    : This item is classified as heavy armour.
-------------------------------------------------------------------------------
</font><font color="#FFFFFF">Condition</font><font color="#C0C0C0">  : </font><font color="#00FFFF">Two hundred</font><font color="#C0C0C0"> (out of </font><font color="#00FFFF">two hundred</font><font color="#C0C0C0">).
</font><font color="#FFFFFF">Attack</font><font color="#C0C0C0">     : </font><font color="#00FFFF">+0</font><font color="#C0C0C0"> (</font><font color="#00FFFF">+0</font><font color="#C0C0C0">, </font><font color="#0000FF">+0</font><font color="#C0C0C0">, </font><font color="#FF00FF">+0</font><font color="#C0C0C0"> or </font><font color="#FF0000">+0</font><font color="#C0C0C0"> depending on condition).
</font><font color="#FFFFFF">Defence</font><font color="#C0C0C0">    : </font><font color="#00FFFF">+0</font><font color="#C0C0C0"> (</font><font color="#00FFFF">+0</font><font color="#C0C0C0">, </font><font color="#0000FF">+0</font><font color="#C0C0C0">, </font><font color="#FF00FF">+0</font><font color="#C0C0C0"> or </font><font color="#FF0000">+0</font><font color="#C0C0C0"> depending on condition).
</font><font color="#FFFFFF">Damage</font><font color="#C0C0C0">     : </font><font color="#00FFFF">+0</font><font color="#C0C0C0"> (</font><font color="#00FFFF">+0</font><font color="#C0C0C0">, </font><font color="#0000FF">+0</font><font color="#C0C0C0">, </font><font color="#FF00FF">+0</font><font color="#C0C0C0"> or </font><font color="#FF0000">+0</font><font color="#C0C0C0"> depending on condition).
</font><font color="#FFFFFF">Cooldown</font><font color="#C0C0C0">   : </font><font color="#00FFFF">4</font><font color="#C0C0C0">, </font><font color="#0000FF">4</font><font color="#C0C0C0">, </font><font color="#FF00FF">5</font><font color="#C0C0C0"> or </font><font color="#FF0000">5</font><font color="#C0C0C0"> seconds, depending on wielders encumbrance.
</font><font color="#FFFFFF">Layer</font><font color="#C0C0C0">      : Protective.
</font><font color="#FFFFFF">Protects</font><font color="#C0C0C0">   : Arms and hands.
</font><font color="#FFFFFF">Soak/Absorb</font><font color="#C0C0C0">: </font><font color="#00FFFF">20</font><font color="#C0C0C0">%/</font><font color="#00FFFF">1</font><font color="#C0C0C0"> cut, </font><font color="#00FFFF">20</font><font color="#C0C0C0">%/</font><font color="#00FFFF">1</font><font color="#C0C0C0"> stab, </font><font color="#00FFFF">20</font><font color="#C0C0C0">%/</font><font color="#00FFFF">1</font><font color="#C0C0C0"> crush and </font><font color="#00FFFF">0</font><font color="#C0C0C0">%/</font><font color="#00FFFF">0</font><font color="#C0C0C0"> poison.
</font><font color="#FFFFFF">Soak/Absorb</font><font color="#C0C0C0">: </font><font color="#00FFFF">0</font><font color="#C0C0C0">%/</font><font color="#00FFFF">0</font><font color="#C0C0C0"> heat, </font><font color="#00FFFF">0</font><font color="#C0C0C0">%/</font><font color="#00FFFF">0</font><font color="#C0C0C0"> cold, </font><font color="#00FFFF">0</font><font color="#C0C0C0">%/</font><font color="#00FFFF">0</font><font color="#C0C0C0"> shock and </font><font color="#00FFFF">15</font><font color="#C0C0C0">%/</font><font color="#00FFFF">0</font><font color="#C0C0C0"> mental.
-------------------------------------------------------------------------------
</font><font color="#FFFFFF">Magic type</font><font color="#C0C0C0"> : A common magical item with 62 points of radiation.
</font><font color="#FFFFFF">Bonus      </font><font color="#C0C0C0">: +2 to Speed</font><font color="#0080FF"> </font><font color="#C0C0C0">(</font><font color="#008000">24</font><font color="#C0C0C0"> Radiation)
</font><font color="#FFFFFF">Bonus      </font><font color="#C0C0C0">: 4% armour to all locations vs physical damage</font><font color="#0080FF"> </font><font color="#C0C0C0">(</font><font color="#008000">40</font><font color="#C0C0C0"> Radiation)
</font><font color="#FFFFFF">Rad Cut    </font><font color="#C0C0C0">: </font><font color="#FFFF00">3.12</font><font color="#C0C0C0">% Reduction (</font><font color="#0000FF">50.00</font><font color="#C0C0C0">% avail)
-------------------------------------------------------------------------------
</font></font></code></pre>
