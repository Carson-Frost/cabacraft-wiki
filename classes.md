---
title: Classes
permalink: /classes/
intro: >-
  Each player will have a class and one or more specializations alongside their species, chosen at
  the start. There are fifteen classes total, organized by three 'Paths', 'Combat', 'Innovation',
  and 'Creation'. These classes largely work by gating recipes to items within the class that no
  other class has access to. Classes can also grant bonuses or gate entire game mechanics, like a
  combat roll or access to a workstation entirely. Specializations are smaller versions of classes
  that are chosen as secondary roles. Classes under the creation path will get to choose 2
  specializations.
---

<div class="tabs">
<input type="radio" name="tab" id="t1" checked><label for="t1">Combat</label>
<input type="radio" name="tab" id="t2"><label for="t2">Innovation</label>
<input type="radio" name="tab" id="t3"><label for="t3">Creation</label>
<input type="radio" name="tab" id="t4"><label for="t4">Specializations</label>
<div class="group" id="g1">
<p class="groupdesc">Warrior, Ranger, Mage, Paladin, Rogue, Blacksmith and Gunsmith.</p>
<article id="warrior">
  <div class="head">
    <img src="{{ '/icons/warrior.png' | relative_url }}" alt="">
    <div>
      <h2>Warrior</h2>
      <p class="desc">Melee-combat with strong defense. Gates all Warrior class armor sets and gets a melee damage boost.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Warrior Armor</h3><p>Ability to craft all Warrior class armor sets, the Ironclad and Brawler harnesses and the Warrior and Berserker plate above them.</p></div>
    <div><h3>Weapon Master</h3><p>An additional 5% melee damage boost.</p></div>
  </div>
</article>

<article id="ranger">
  <div class="head">
    <img src="{{ '/icons/ranger.png' | relative_url }}" alt="">
    <div>
      <h2>Ranger</h2>
      <p class="desc">Ranged combat at a distance. Rangers gate every ranged weapon in the pack and the two light armor lines made to shoot in, and get a ranged damage boost.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Ranged Weapons</h3><p>Every ranged weapon: longbows, crossbows, muskets and pistols, with the quiver and the auto-fire hook.</p></div>
    <div><h3>Ranger Armor</h3><p>The Archer and Ranger leathers, light enough to shoot in.</p></div>
    <div><h3>Marksman</h3><p>+5% ranged damage.</p></div>
  </div>
</article>

<article id="mage">
  <div class="head">
    <img src="{{ '/icons/mage.png' | relative_url }}" alt="">
    <div>
      <h2>Mage</h2>
      <p class="desc">Spellcasting at a distance. Mages gate every staff, wand and robe across the novice, wizard, arcane, fire and frost schools, and get a spell power boost.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Staves and Wands</h3><p>Every staff and wand, across the novice, wizard, arcane, fire and frost schools.</p></div>
    <div><h3>Mage Robes</h3><p>All Mage class robes: one set per school, plus two that suit any of them.</p></div>
    <div><h3>Arcane Focus</h3><p>+5% spell power.</p></div>
  </div>
</article>

<article id="paladin">
  <div class="head">
    <img src="{{ '/icons/paladin.png' | relative_url }}" alt="">
    <div>
      <h2>Paladin</h2>
      <p class="desc">Healing and holy combat. Paladins gate the monk's workbench and everything made on it, along with the Paladin plate and the Priest robes, and get a healing boost.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Holy Gear</h3><p>The monk's workbench, and the holy wands, staves and kite shields made on it.</p></div>
    <div><h3>Paladin Armor</h3><p>All Paladin class armor sets: the Paladin plate line and the Priest robes beside it.</p></div>
    <div><h3>Laying On Hands</h3><p>+5% healing.</p></div>
  </div>
</article>

<article id="rogue">
  <div class="head">
    <img src="{{ '/icons/rogue.png' | relative_url }}" alt="">
    <div>
      <h2>Rogue</h2>
      <p class="desc">Fast, lightly armored melee. Rogues gate the armor that trades protection for evasion and attack speed, and can combat roll.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Rogue Armor</h3><p>All Rogue class armor sets: the Rogue and Assassin leathers, and the light mail under them.</p></div>
    <div><h3>Combat Roll</h3><p>Performs a combat roll.</p></div>
  </div>
</article>

<article id="blacksmith">
  <div class="head">
    <img src="{{ '/icons/blacksmith.png' | relative_url }}" alt="">
    <div>
      <h2>Blacksmith</h2>
      <p class="desc">Weaponsmithing. Blacksmiths gate the bladed, blunt and reach weapon lines up to the aeternium blades, though vanilla's swords and axes stay open to everyone. Offered under both the Combat and the Creation Path.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Melee Weapons</h3><p>Every bladed, blunt and reach weapon: claymores and daggers, maces and spears, up to the aeternium blades.</p></div>
  </div>
</article>

<article id="gunsmith">
  <div class="head">
    <img src="{{ '/icons/gunsmith.png' | relative_url }}" alt="">
    <div>
      <h2>Gunsmith</h2>
      <p class="desc">Firearms and artillery. Gunsmiths gate every gun and cannon except the muskets, which belong to the Ranger. Offered under both the Combat and the Innovation Path.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Firearms</h3><p>All firearms: the revolver, shotgun, nailgun and blazegun.</p></div>
    <div><h3>Cannonry</h3><p>Every cannon, and the gear that mounts, aims and loads it.</p></div>
  </div>
</article>

</div>
<div class="group" id="g2">
<p class="groupdesc">Engineer, Machinist, Gunsmith, Originator, Alchemist and Enchanter.</p>
<article id="engineer">
  <div class="head">
    <img src="{{ '/icons/engineer.png' | relative_url }}" alt="">
    <div>
      <h2>Engineer</h2>
      <p class="desc">Mechanical automation. Engineers gate all of Create's machinery, from the shafts and gearboxes that carry power to the machines that run on it, but hold no combat bonus of any kind.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Create Machinery</h3><p>All Create machinery: the power train, the processing machines, the automation blocks, and the Engineer's wrench and goggles.</p></div>
  </div>
</article>

<article id="machinist">
  <div class="head">
    <img src="{{ '/icons/machinist.png' | relative_url }}" alt="">
    <div>
      <h2>Machinist</h2>
      <p class="desc">Powered flight. Machinists gate every airship part, though a ship will not move without an Engineer's power train.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Airship Parts</h3><p>Every airship part: the bearings a ship turns on, its propellers, and the pilot's burner and goggles.</p></div>
  </div>
</article>

<article id="gunsmith">
  <div class="head">
    <img src="{{ '/icons/gunsmith.png' | relative_url }}" alt="">
    <div>
      <h2>Gunsmith</h2>
      <p class="desc">Firearms and artillery. Gunsmiths gate every gun and cannon except the muskets, which belong to the Ranger. Offered under both the Combat and the Innovation Path.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Firearms</h3><p>All firearms: the revolver, shotgun, nailgun and blazegun.</p></div>
    <div><h3>Cannonry</h3><p>Every cannon, and the gear that mounts, aims and loads it.</p></div>
  </div>
</article>

<article id="originator">
  <div class="head">
    <img src="{{ '/icons/originator.png' | relative_url }}" alt="">
    <div>
      <h2>Originator</h2>
      <p class="desc">Electrical power. Originators gate Oritech's generators, batteries and wiring, and the frames and cores every Oritech machine is built on.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Oritech Power</h3><p>All generators, batteries and wiring, with the frames and cores that carry every Oritech machine.</p></div>
  </div>
</article>

<article id="alchemist">
  <div class="head">
    <img src="{{ '/icons/alchemist.png' | relative_url }}" alt="">
    <div>
      <h2>Alchemist</h2>
      <p class="desc">Potion brewing. Alchemists gate the brewing stations and the brewing itself, and their own elixirs run longer.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Brewing Stations</h3><p>All brewing stations: the brewing bench, glass cauldron, alchemist's eye and potion shelf.</p></div>
    <div><h3>Potion Mastery</h3><p>Brewing stands and glass cauldrons operate for Alchemists. +10 potion mastery and +10 potion immunity, so their elixirs run longer and hostile ones wear off faster.</p></div>
  </div>
</article>

<article id="enchanter">
  <div class="head">
    <img src="{{ '/icons/enchanter.png' | relative_url }}" alt="">
    <div>
      <h2>Enchanter</h2>
      <p class="desc">Enchanting past the world's limits. Every enchantment in the pack is capped, and an Enchanter goes one level beyond the cap.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Ancient Books</h3><p>The Ancient Book.</p></div>
    <div><h3>Enchant Mastery</h3><p>+1 level on all 33 capped enchantments.</p></div>
  </div>
</article>

</div>
<div class="group" id="g3">
<p class="groupdesc">Builder, Blacksmith, Jeweler and Cook.</p>
<article id="builder">
  <div class="head">
    <img src="{{ '/icons/builder.png' | relative_url }}" alt="">
    <div>
      <h2>Builder</h2>
      <p class="desc">Building at scale. Builders gate the eight workstations that cut every decorative block variant, and reach half a block further to place and break.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Workstations</h3><p>All eight Chipped workstations, and every block variant cut on them.</p></div>
    <div><h3>Long Arm</h3><p>+0.5 blocks of range for placing and breaking. Combat reach is unchanged.</p></div>
  </div>
</article>

<article id="blacksmith">
  <div class="head">
    <img src="{{ '/icons/blacksmith.png' | relative_url }}" alt="">
    <div>
      <h2>Blacksmith</h2>
      <p class="desc">Weaponsmithing. Blacksmiths gate the bladed, blunt and reach weapon lines up to the aeternium blades, though vanilla's swords and axes stay open to everyone. Offered under both the Combat and the Creation Path.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Melee Weapons</h3><p>Every bladed, blunt and reach weapon: claymores and daggers, maces and spears, up to the aeternium blades.</p></div>
  </div>
</article>

<article id="jeweler">
  <div class="head">
    <img src="{{ '/icons/jeweler.png' | relative_url }}" alt="">
    <div>
      <h2>Jeweler</h2>
      <p class="desc">Accessory crafting. Jewelers gate every ring and necklace, worn in accessory slots alongside armor rather than instead of it.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Jewelry</h3><p>The jeweler's kit, and every jade and tanzanite ring and necklace made on it.</p></div>
  </div>
</article>

<article id="cook">
  <div class="head">
    <img src="{{ '/icons/cook.png' | relative_url }}" alt="">
    <div>
      <h2>Cook</h2>
      <p class="desc">Cooking, which carries more weight here than in vanilla because food is what restores health. Cooks gate every prepared dish and every kitchen station it is made on.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Kitchen Stations</h3><p>Every kitchen station, and the pot dishes that carry no recipe of their own.</p></div>
    <div><h3>Prepared Food</h3><p>Every prepared dish: breads and pies, stews and roasts, and the feasts a whole table shares.</p></div>
  </div>
</article>

</div>
<div class="group" id="g4">
<article id="angler">
  <div class="head">
    <img src="{{ '/icons/angler.png' | relative_url }}" alt="">
    <div>
      <h2>Angler</h2>
      <p class="desc">Fishing. Anglers gate every rod, hook and bobber, and the fishing minigame runs easier in their hands.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Rods and Tackle</h3><p>Every rod, hook and bobber, up to the azure crystal rod and the amethyst hook.</p></div>
    <div><h3>Starcatcher Guide</h3><p>The Starcatcher guide, granted on picking the specialization.</p></div>
    <div><h3>Steady Hands</h3><p>The fishing minigame runs easier: the bar drains slower, a miss costs less, score accrues quicker, and a sweet spot lingers.</p></div>
  </div>
</article>

<article id="archaeologist">
  <div class="head">
    <img src="{{ '/icons/archaeologist.png' | relative_url }}" alt="">
    <div>
      <h2>Archaeologist</h2>
      <p class="desc">Excavation. Archaeologists gate the tools both of the pack's digging systems need, and carry no bonus to any stat.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Excavation Tools</h3><p>Every excavation tool: the diamond brush, and the rusty pickaxe and shovel.</p></div>
  </div>
</article>

<article id="bard">
  <div class="head">
    <img src="{{ '/icons/bard.png' | relative_url }}" alt="">
    <div>
      <h2>Bard</h2>
      <p class="desc">Music and recruitment. Bards gate every instrument and hire villagers into service.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Instruments</h3><p>Every instrument: strings, winds, keys and drums.</p></div>
    <div><h3>Recruitment</h3><p>Recruits any villager that has no profession. Trading is unaffected.</p></div>
  </div>
</article>

<article id="brewer">
  <div class="head">
    <img src="{{ '/icons/brewer.png' | relative_url }}" alt="">
    <div>
      <h2>Brewer</h2>
      <p class="desc">Fermenting and brewing drinks, which are separate from the Alchemist's potions. Brewers gate every beer and the fermentation vessel behind the ciders, wines and mead.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Beer</h3><p>The keg, the mug and the hop crop. All twelve beers are brewed in the keg.</p></div>
    <div><h3>Fermentation Vessel</h3><p>The fermentation vessel, and the ciders, wines, mead, pickles and popped maize it turns out.</p></div>
  </div>
</article>

<article id="curator">
  <div class="head">
    <img src="{{ '/icons/curator.png' | relative_url }}" alt="">
    <div>
      <h2>Curator</h2>
      <p class="desc">Recording the world. Curators gate the camera, the bestiary, the antique atlas and the diary, and carry no bonus to any stat.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Records</h3><p>The camera and its film, the bestiary and its analyzer, the antique atlas and the diary.</p></div>
  </div>
</article>

<article id="herbalist">
  <div class="head">
    <img src="{{ '/icons/herbalist.png' | relative_url }}" alt="">
    <div>
      <h2>Herbalist</h2>
      <p class="desc">Growing and preparing herbs. Herbalists gate the hemp crop and everything made from it, along with the remedies that are not potions.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Hemp</h3><p>Every hemp good: the crop, its cloth in every dye colour, and the pipes, joints and brownies it becomes.</p></div>
    <div><h3>Remedies</h3><p>Every remedy: the aura crystal, the two oils, the cleansing concoction and the teas.</p></div>
  </div>
</article>

<article id="shipwright">
  <div class="head">
    <img src="{{ '/icons/shipwright.png' | relative_url }}" alt="">
    <div>
      <h2>Shipwright</h2>
      <p class="desc">Shipbuilding. Shipwrights gate all four ship builders, and carry no bonus to any stat.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Ship Builders</h3><p>All four ship builders: the cog, the caravel, the general and the decorative.</p></div>
  </div>
</article>

<article id="tailor">
  <div class="head">
    <img src="{{ '/icons/tailor.png' | relative_url }}" alt="">
    <div>
      <h2>Tailor</h2>
      <p class="desc">Clothing. Tailors gate the sewing bench and every hat and garment made on it.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Clothing</h3><p>The sewing kit and table, and every hat and garment made on them: hoods and crowns, coats, robes and boots.</p></div>
  </div>
</article>

</div>
</div>
