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
      <p class="desc">Ranged combat at a distance. Gates every ranged weapon and the light armor you shoot in, and gets a ranged damage boost.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Ranged Weapons</h3><p>Ability to craft every ranged weapon, longbows and crossbows through muskets and pistols, plus the quiver and auto-fire hook.</p></div>
    <div><h3>Ranger Armor</h3><p>Ability to craft the Archer and Ranger leathers, light enough to shoot in.</p></div>
    <div><h3>Marksman</h3><p>An additional 5% ranged damage boost.</p></div>
  </div>
</article>

<article id="mage">
  <div class="head">
    <img src="{{ '/icons/mage.png' | relative_url }}" alt="">
    <div>
      <h2>Mage</h2>
      <p class="desc">Spellcasting at a distance. Gates the staves, wands and robes of all four magic schools, and gets a spell power boost.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Staves and Wands</h3><p>Ability to craft every staff and wand, across the novice, wizard, arcane, fire and frost schools.</p></div>
    <div><h3>Mage Robes</h3><p>Ability to craft all Mage class robes, one set per school plus two that suit any of them.</p></div>
    <div><h3>Arcane Focus</h3><p>An additional 5% spell power boost.</p></div>
  </div>
</article>

<article id="paladin">
  <div class="head">
    <img src="{{ '/icons/paladin.png' | relative_url }}" alt="">
    <div>
      <h2>Paladin</h2>
      <p class="desc">Healing and holy combat. Gates the healing gear and the Paladin armor lines, and gets a healing boost. The only class with its own workstation.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Holy Gear</h3><p>Ability to craft the monk's workbench, where you make the holy wands, staves and kite shields.</p></div>
    <div><h3>Paladin Armor</h3><p>Ability to craft all Paladin class armor sets, the Paladin plate line and the Priest robes beside it.</p></div>
    <div><h3>Laying On Hands</h3><p>An additional 5% healing boost.</p></div>
  </div>
</article>

<article id="rogue">
  <div class="head">
    <img src="{{ '/icons/rogue.png' | relative_url }}" alt="">
    <div>
      <h2>Rogue</h2>
      <p class="desc">Fast, lightly armored melee. Gates the armor that trades protection for evasion and attack speed, and gets the combat roll.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Rogue Armor</h3><p>Ability to craft all Rogue class armor sets, the Rogue and Assassin leathers and the light mail under them.</p></div>
    <div><h3>Combat Roll</h3><p>The ability to combat roll. No other class has it.</p></div>
  </div>
</article>

<article id="blacksmith">
  <div class="head">
    <img src="{{ '/icons/blacksmith.png' | relative_url }}" alt="">
    <div>
      <h2>Blacksmith</h2>
      <p class="desc">Weaponsmithing. Gates every bladed, blunt and reach weapon, so every other class comes to a Blacksmith for one. Offered under both the Combat and the Creation Path.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Melee Weapons</h3><p>Ability to craft every bladed, blunt and reach weapon, claymores and daggers through maces and spears, up to the aeternium blades.</p></div>
  </div>
</article>

<article id="gunsmith">
  <div class="head">
    <img src="{{ '/icons/gunsmith.png' | relative_url }}" alt="">
    <div>
      <h2>Gunsmith</h2>
      <p class="desc">Firearms and artillery. Gates every gun and cannon but the muskets, which belong to the Ranger. Offered under both the Combat and the Innovation Path.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Firearms</h3><p>Ability to craft all firearms, the revolver, shotgun, nailgun and blazegun.</p></div>
    <div><h3>Cannonry</h3><p>Ability to craft every cannon and the gear that mounts, aims and loads it.</p></div>
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
      <p class="desc">Mechanical automation. Gates all Create machinery, so no one else builds a powered contraption.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Create Machinery</h3><p>Ability to craft all Create machinery, the power train, the processing machines and the automation blocks, plus the Engineer's wrench and goggles.</p></div>
  </div>
</article>

<article id="machinist">
  <div class="head">
    <img src="{{ '/icons/machinist.png' | relative_url }}" alt="">
    <div>
      <h2>Machinist</h2>
      <p class="desc">Powered flight. Gates every airship part, so no one else gets a ship off the ground.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Airship Parts</h3><p>Ability to craft every airship part, the bearings a ship turns on, its propellers, and the pilot's burner and goggles.</p></div>
  </div>
</article>

<article id="gunsmith">
  <div class="head">
    <img src="{{ '/icons/gunsmith.png' | relative_url }}" alt="">
    <div>
      <h2>Gunsmith</h2>
      <p class="desc">Firearms and artillery. Gates every gun and cannon but the muskets, which belong to the Ranger. Offered under both the Combat and the Innovation Path.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Firearms</h3><p>Ability to craft all firearms, the revolver, shotgun, nailgun and blazegun.</p></div>
    <div><h3>Cannonry</h3><p>Ability to craft every cannon and the gear that mounts, aims and loads it.</p></div>
  </div>
</article>

<article id="originator">
  <div class="head">
    <img src="{{ '/icons/originator.png' | relative_url }}" alt="">
    <div>
      <h2>Originator</h2>
      <p class="desc">Electrical power. Gates Oritech's generators and batteries, so no one else powers a machine.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Oritech Power</h3><p>Ability to craft all generators, batteries and wiring, plus the frames and cores that carry every Oritech machine.</p></div>
  </div>
</article>

<article id="alchemist">
  <div class="head">
    <img src="{{ '/icons/alchemist.png' | relative_url }}" alt="">
    <div>
      <h2>Alchemist</h2>
      <p class="desc">Potion brewing. Gates brewing itself, so only an Alchemist makes potions.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Brewing Stations</h3><p>Ability to craft all brewing stations, the brewing bench, glass cauldron, alchemist's eye and potion shelf.</p></div>
    <div><h3>The Only Brewer</h3><p>The ability to use a brewing stand or glass cauldron. No other class can. Your own elixirs last longer, and hostile ones wear off faster.</p></div>
  </div>
</article>

<article id="enchanter">
  <div class="head">
    <img src="{{ '/icons/enchanter.png' | relative_url }}" alt="">
    <div>
      <h2>Enchanter</h2>
      <p class="desc">Enchanting past the world's limits. Every enchantment in the pack is capped, and only an Enchanter goes a level past it.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Ancient Books</h3><p>Ability to craft the Ancient Book.</p></div>
    <div><h3>Enchant Mastery</h3><p>An additional level on all 33 capped enchantments.</p></div>
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
      <p class="desc">Building at scale. Gates the workstations that cut every decorative block, and gets extra reach.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Workstations</h3><p>Ability to craft all eight Chipped workstations, and to cut every block variant they hold.</p></div>
    <div><h3>Long Arm</h3><p>An additional half block of reach for placing and breaking. Combat reach is unchanged.</p></div>
  </div>
</article>

<article id="blacksmith">
  <div class="head">
    <img src="{{ '/icons/blacksmith.png' | relative_url }}" alt="">
    <div>
      <h2>Blacksmith</h2>
      <p class="desc">Weaponsmithing. Gates every bladed, blunt and reach weapon, so every other class comes to a Blacksmith for one. Offered under both the Combat and the Creation Path.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Melee Weapons</h3><p>Ability to craft every bladed, blunt and reach weapon, claymores and daggers through maces and spears, up to the aeternium blades.</p></div>
  </div>
</article>

<article id="jeweler">
  <div class="head">
    <img src="{{ '/icons/jeweler.png' | relative_url }}" alt="">
    <div>
      <h2>Jeweler</h2>
      <p class="desc">Accessory crafting. Gates every ring and necklace, which you wear alongside armor rather than instead of it.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Jewelry</h3><p>Ability to craft the jeweler's kit, and every ring and necklace you make on it, in jade and tanzanite.</p></div>
  </div>
</article>

<article id="cook">
  <div class="head">
    <img src="{{ '/icons/cook.png' | relative_url }}" alt="">
    <div>
      <h2>Cook</h2>
      <p class="desc">Cooking, which matters more here than in vanilla because food is how you heal. Gates every prepared dish and the kitchen you cook it in.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Kitchen Stations</h3><p>Ability to craft every kitchen station, and to cook the dishes that carry no recipe of their own.</p></div>
    <div><h3>Prepared Food</h3><p>Ability to craft every prepared dish, breads and pies through stews, roasts and the feasts a whole table shares.</p></div>
  </div>
</article>

</div>
<div class="group" id="g4">
<article id="angler">
  <div class="head">
    <img src="{{ '/icons/angler.png' | relative_url }}" alt="">
    <div>
      <h2>Angler</h2>
      <p class="desc">Fishing. Gates every rod and hook, and gets an easier catch.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Rods and Tackle</h3><p>Ability to craft every rod, hook and bobber, up to the azure crystal rod and the amethyst hook.</p></div>
    <div><h3>The Guide</h3><p>The Starcatcher guide, which you receive when you pick the specialization.</p></div>
    <div><h3>Steady Hands</h3><p>An easier fishing minigame: the bar drains slower, a miss costs less, the score comes quicker, and a sweet spot lingers.</p></div>
  </div>
</article>

<article id="archaeologist">
  <div class="head">
    <img src="{{ '/icons/archaeologist.png' | relative_url }}" alt="">
    <div>
      <h2>Archaeologist</h2>
      <p class="desc">Excavation. Gates the tools both digging systems need, so only an Archaeologist works a dig site.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Excavation Tools</h3><p>Ability to craft every excavation tool, the diamond brush and the rusty pickaxe and shovel.</p></div>
  </div>
</article>

<article id="bard">
  <div class="head">
    <img src="{{ '/icons/bard.png' | relative_url }}" alt="">
    <div>
      <h2>Bard</h2>
      <p class="desc">Music and recruitment. Gates every instrument, and only a Bard puts a villager to work.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Instruments</h3><p>Ability to craft every instrument, strings, winds, keys and drums alike.</p></div>
    <div><h3>Recruitment</h3><p>The ability to recruit villagers. No other specialization has it. You hire any villager without a profession, and everyone still trades.</p></div>
  </div>
</article>

<article id="brewer">
  <div class="head">
    <img src="{{ '/icons/brewer.png' | relative_url }}" alt="">
    <div>
      <h2>Brewer</h2>
      <p class="desc">Fermenting and brewing drinks, separate from the Alchemist's potions. Gates every beer and the vessel that turns out the ciders, wines and mead.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Beer</h3><p>Ability to craft the keg and mug and to grow hops. The keg brews all twelve beers and nothing else does.</p></div>
    <div><h3>The Fermentation Vessel</h3><p>Ability to craft the fermentation vessel, which turns out the ciders, wines, mead, pickles and popped maize.</p></div>
  </div>
</article>

<article id="curator">
  <div class="head">
    <img src="{{ '/icons/curator.png' | relative_url }}" alt="">
    <div>
      <h2>Curator</h2>
      <p class="desc">Recording the world. Gates the cameras and the records, so only a Curator documents what the server finds.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Records</h3><p>Ability to craft the camera and its film, the bestiary and its analyzer, the antique atlas and the diary.</p></div>
  </div>
</article>

<article id="herbalist">
  <div class="head">
    <img src="{{ '/icons/herbalist.png' | relative_url }}" alt="">
    <div>
      <h2>Herbalist</h2>
      <p class="desc">Growing and preparing herbs. Gates the hemp crop and everything you make from it, plus the remedies that are not potions.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Hemp</h3><p>Ability to craft every hemp good, the crop, its cloth in every dye colour, and the pipes, joints and brownies it becomes.</p></div>
    <div><h3>Remedies</h3><p>Ability to craft every remedy, the aura crystal, the two oils, the cleansing concoction and the teas.</p></div>
  </div>
</article>

<article id="shipwright">
  <div class="head">
    <img src="{{ '/icons/shipwright.png' | relative_url }}" alt="">
    <div>
      <h2>Shipwright</h2>
      <p class="desc">Shipbuilding. Gates the ship builders, so only a Shipwright lays down a vessel.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Ship Builders</h3><p>Ability to craft all four ship builders, the cog, caravel, general and decorative.</p></div>
  </div>
</article>

<article id="tailor">
  <div class="head">
    <img src="{{ '/icons/tailor.png' | relative_url }}" alt="">
    <div>
      <h2>Tailor</h2>
      <p class="desc">Clothing. Gates the sewing bench and every hat and garment you make on it.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Clothing</h3><p>Ability to craft the sewing kit and table, and every hat and garment you make on them, hoods and crowns through coats, robes and boots.</p></div>
  </div>
</article>

</div>
</div>
