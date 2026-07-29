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
    <div><h3>Warplate</h3><p>Ability to craft all Warrior class plate armor sets, including the Warrior and the Berserker.</p></div>
    <div><h3>Field Harness</h3><p>Ability to craft all Warrior class starter harnesses, including the Ironclad and the Brawler. The Ironclad trades movement speed for its extra plate.</p></div>
    <div><h3>Weapon Master</h3><p>An additional 5% melee damage boost.</p></div>
  </div>
</article>

<article id="ranger">
  <div class="head">
    <img src="{{ '/icons/ranger.png' | relative_url }}" alt="">
    <div>
      <h2>Ranger</h2>
      <p class="desc">Ranged combat at a distance. Gates all bows, crossbows, black powder weapons and Ranger class armor sets, and gets a ranged damage boost.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Bows and Crossbows</h3><p>Ability to craft all bows and crossbows, including the royal and composite longbows, the mechanic shortbow, and the heavy and rapid crossbows.</p></div>
    <div><h3>Black Powder</h3><p>Ability to craft all black powder weapons, including the muskets, pistols and blunderbuss, along with their cartridges and upgrade template.</p></div>
    <div><h3>Ranged Leathers</h3><p>Ability to craft all Ranger class light armor sets, including the Archer and the Ranger.</p></div>
    <div><h3>Field Kit</h3><p>Ability to craft all Ranger field gear, including the field kit, the quiver and the auto-fire hook.</p></div>
    <div><h3>Marksman</h3><p>An additional 5% ranged damage boost with any bow or crossbow.</p></div>
  </div>
</article>

<article id="mage">
  <div class="head">
    <img src="{{ '/icons/mage.png' | relative_url }}" alt="">
    <div>
      <h2>Mage</h2>
      <p class="desc">Spellcasting at a distance. Gates all staves, wands and school robes, and gets a spell power boost.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Staves</h3><p>Ability to craft all staves, including the wizard, arcane, fire and frost schools.</p></div>
    <div><h3>Wands</h3><p>Ability to craft all wands, including the novice, arcane, fire and frost schools.</p></div>
    <div><h3>School Robes</h3><p>Ability to craft all school robes, including arcane, fire and frost.</p></div>
    <div><h3>Wizard's Robes</h3><p>Ability to craft all general robes, including the Wizard Robe and the Immersive Robe.</p></div>
    <div><h3>Arcane Focus</h3><p>An additional 5% spell power boost.</p></div>
  </div>
</article>

<article id="paladin">
  <div class="head">
    <img src="{{ '/icons/paladin.png' | relative_url }}" alt="">
    <div>
      <h2>Paladin</h2>
      <p class="desc">Healing and holy combat. Gates all healing gear, shields and Paladin class armor sets, and gets a healing boost. The only class with a workstation of its own.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>The Monk's Workbench</h3><p>Ability to craft the monk's workbench, which all other Paladin gear is made on.</p></div>
    <div><h3>Holy Arms</h3><p>Ability to craft all holy weapons, including the holy wands and staves and the acolyte wand beneath them.</p></div>
    <div><h3>Kite Shields</h3><p>Ability to craft all kite shields, including iron, gold and diamond.</p></div>
    <div><h3>Consecrated Plate</h3><p>Ability to craft all Paladin class plate armor sets, including the Paladin, Crusader, Justicar and Divine.</p></div>
    <div><h3>Vestments</h3><p>Ability to craft all Priest class robes, including the Priest and the Prior.</p></div>
    <div><h3>Laying On Hands</h3><p>An additional 5% healing boost.</p></div>
  </div>
</article>

<article id="rogue">
  <div class="head">
    <img src="{{ '/icons/rogue.png' | relative_url }}" alt="">
    <div>
      <h2>Rogue</h2>
      <p class="desc">Fast, lightly armored melee. Gates all Rogue class armor sets, which trade protection for evasion and attack speed, and gets the combat roll.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Shadowweave</h3><p>Ability to craft all Rogue class light armor sets, including the Rogue and the Assassin.</p></div>
    <div><h3>Light Mail</h3><p>Ability to craft all light mail pieces, including iron, gold and diamond.</p></div>
    <div><h3>Combat Roll</h3><p>The ability to combat roll, which no other class has.</p></div>
  </div>
</article>

<article id="blacksmith">
  <div class="head">
    <img src="{{ '/icons/blacksmith.png' | relative_url }}" alt="">
    <div>
      <h2>Blacksmith</h2>
      <p class="desc">Weaponsmithing. Gates all bladed, blunt and reach weapons, so every other class buys its weapons from a Blacksmith. Offered under both the Combat and the Creation Path.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Rare Steel</h3><p>Ability to craft all rare blades, including the aeternium and ruby daggers and the unique longsword.</p></div>
    <div><h3>Blades</h3><p>Ability to craft all bladed weapons, including claymores, daggers, glaives and sickles in iron, gold and diamond.</p></div>
    <div><h3>Blunt Arms</h3><p>Ability to craft all blunt weapons, including maces, great hammers and double axes in iron, gold and diamond.</p></div>
    <div><h3>Reach Weapons</h3><p>Ability to craft all reach weapons, including spears in flint, iron, gold and diamond.</p></div>
  </div>
</article>

<article id="gunsmith">
  <div class="head">
    <img src="{{ '/icons/gunsmith.png' | relative_url }}" alt="">
    <div>
      <h2>Gunsmith</h2>
      <p class="desc">Firearms and artillery. Gates all guns and cannons except the muskets, which belong to the Ranger. Offered under both the Combat and the Innovation Path.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Firearms</h3><p>Ability to craft all firearms, including the revolver, shotgun, nailgun and blazegun.</p></div>
    <div><h3>Cannonry</h3><p>Ability to craft all cannons and the gear that works them, including the mount, carriage, loader, drill and autocannon barrel.</p></div>
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
      <p class="desc">Mechanical automation. Gates all Create machinery, so every powered contraption in the pack starts with an Engineer.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>The Engineer's Own</h3><p>Ability to craft all Engineer tools, including the wrench, the goggles and the schematic table.</p></div>
    <div><h3>Kinetics</h3><p>Ability to craft all power train parts, including water wheels, hand cranks, gearboxes, gearshifts, clutches, belts and encased fans.</p></div>
    <div><h3>Processing</h3><p>Ability to craft all processing machines, including millstones, basins, mixers, presses, saws, drills and blaze burners.</p></div>
    <div><h3>Automation</h3><p>Ability to craft all automation blocks, including deployers, depots, mechanical arms and pistons.</p></div>
  </div>
</article>

<article id="machinist">
  <div class="head">
    <img src="{{ '/icons/machinist.png' | relative_url }}" alt="">
    <div>
      <h2>Machinist</h2>
      <p class="desc">Powered flight. Gates all airship parts, so no other class can get one off the ground.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Bearings</h3><p>Ability to craft all airship bearings, including the propeller bearing and the gyroscopic propeller bearing.</p></div>
    <div><h3>Propellers</h3><p>Ability to craft all propellers, including wood, andesite and smart.</p></div>
    <div><h3>Flight Kit</h3><p>Ability to craft all pilot's gear, including the adjustable burner and the aviator's goggles.</p></div>
  </div>
</article>

<article id="gunsmith">
  <div class="head">
    <img src="{{ '/icons/gunsmith.png' | relative_url }}" alt="">
    <div>
      <h2>Gunsmith</h2>
      <p class="desc">Firearms and artillery. Gates all guns and cannons except the muskets, which belong to the Ranger. Offered under both the Combat and the Innovation Path.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Firearms</h3><p>Ability to craft all firearms, including the revolver, shotgun, nailgun and blazegun.</p></div>
    <div><h3>Cannonry</h3><p>Ability to craft all cannons and the gear that works them, including the mount, carriage, loader, drill and autocannon barrel.</p></div>
  </div>
</article>

<article id="originator">
  <div class="head">
    <img src="{{ '/icons/originator.png' | relative_url }}" alt="">
    <div>
      <h2>Originator</h2>
      <p class="desc">Electrical power. Gates all Oritech generation and storage, so every electrically powered machine in the pack starts with an Originator.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Generation</h3><p>Ability to craft all generators, including the basic, bio and fuel generators and the big solar panel.</p></div>
    <div><h3>Storage and Transfer</h3><p>Ability to craft all power storage and wiring, including the basic and advanced batteries and the energy pipe.</p></div>
    <div><h3>Machine Bodies</h3><p>Ability to craft all machine bodies, including the machine frame and the machine core, which every Oritech machine is built on.</p></div>
  </div>
</article>

<article id="alchemist">
  <div class="head">
    <img src="{{ '/icons/alchemist.png' | relative_url }}" alt="">
    <div>
      <h2>Alchemist</h2>
      <p class="desc">Potion brewing. Gates all brewing stations and the brewing mechanic entirely, so every potion in the world was made by an Alchemist.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>The Elixir Bench</h3><p>Ability to craft all brewing stations, including the brewing bench, the glass cauldron, the alchemist's eye and the potion shelf.</p></div>
    <div><h3>The Only Brewer</h3><p>The ability to use a brewing stand or a glass cauldron, which no other class has. An Alchemist's own elixirs also last longer, and a hostile one thrown at them wears off faster.</p></div>
  </div>
</article>

<article id="enchanter">
  <div class="head">
    <img src="{{ '/icons/enchanter.png' | relative_url }}" alt="">
    <div>
      <h2>Enchanter</h2>
      <p class="desc">Enchanting past the world's limits. Gates the Ancient Book and gets an enchantment level past the cap every other class is held to.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Enchant Mastery</h3><p>An additional level on all 33 capped enchantments.</p></div>
    <div><h3>Ancient Books</h3><p>Ability to craft the Ancient Book.</p></div>
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
      <p class="desc">Building at scale. Gates all decorative block variants and the workstations that carve them, and gets a building reach boost.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Workstations</h3><p>Ability to craft all Chipped workstations, and through them every block variant they carve.</p></div>
    <div><h3>Long Arm</h3><p>An additional half block of reach for placing and breaking. Combat reach is unchanged.</p></div>
  </div>
</article>

<article id="blacksmith">
  <div class="head">
    <img src="{{ '/icons/blacksmith.png' | relative_url }}" alt="">
    <div>
      <h2>Blacksmith</h2>
      <p class="desc">Weaponsmithing. Gates all bladed, blunt and reach weapons, so every other class buys its weapons from a Blacksmith. Offered under both the Combat and the Creation Path.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Rare Steel</h3><p>Ability to craft all rare blades, including the aeternium and ruby daggers and the unique longsword.</p></div>
    <div><h3>Blades</h3><p>Ability to craft all bladed weapons, including claymores, daggers, glaives and sickles in iron, gold and diamond.</p></div>
    <div><h3>Blunt Arms</h3><p>Ability to craft all blunt weapons, including maces, great hammers and double axes in iron, gold and diamond.</p></div>
    <div><h3>Reach Weapons</h3><p>Ability to craft all reach weapons, including spears in flint, iron, gold and diamond.</p></div>
  </div>
</article>

<article id="jeweler">
  <div class="head">
    <img src="{{ '/icons/jeweler.png' | relative_url }}" alt="">
    <div>
      <h2>Jeweler</h2>
      <p class="desc">Accessory crafting. Gates all rings and necklaces, which are worn in accessory slots alongside armor rather than instead of it.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>The Kit</h3><p>Ability to craft the jeweler's kit, which all rings and necklaces are made on.</p></div>
    <div><h3>Rings</h3><p>Ability to craft all rings, including jade and tanzanite.</p></div>
    <div><h3>Necklaces</h3><p>Ability to craft all necklaces, including jade and tanzanite.</p></div>
  </div>
</article>

<article id="cook">
  <div class="head">
    <img src="{{ '/icons/cook.png' | relative_url }}" alt="">
    <div>
      <h2>Cook</h2>
      <p class="desc">Cooking, which matters more here than in vanilla because food is how you heal. Gates all prepared dishes and the kitchen stations the rest of the pack's cooking runs through.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>The Kitchen</h3><p>Ability to craft all kitchen stations, including the gristmill, cooking pot, skillet, stove and cutting board. Any dish made on one of them is a Cook's, whether or not it has a recipe of its own.</p></div>
    <div><h3>Baking</h3><p>Ability to craft all baked goods, including pies, tarts, cakes and bread, from the shepherd's pie to the sponge cake.</p></div>
    <div><h3>Sweets</h3><p>Ability to craft all sweets, including candies, candied fruit, cookies and the melon popsicle.</p></div>
    <div><h3>Preserves and Drinks</h3><p>Ability to craft all preserves and drinks, including the compote cups, the brewed teas, milk and melon juice.</p></div>
    <div><h3>Dishes</h3><p>Ability to craft all prepared dishes, including stews, medleys, chows, salads, sandwiches, rolls and roasts, and the feasts a whole table eats from.</p></div>
  </div>
</article>

</div>
<div class="group" id="g4">
<article id="angler">
  <div class="head">
    <img src="{{ '/icons/angler.png' | relative_url }}" alt="">
    <div>
      <h2>Angler</h2>
      <p class="desc">Fishing. Gates all rods and tackle, and gets an easier fishing minigame.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Rods</h3><p>Ability to craft all fishing rods, including the bamboo and the azure crystal.</p></div>
    <div><h3>Tackle</h3><p>Ability to craft all tackle, including the copper and amethyst hooks and the bobber.</p></div>
    <div><h3>The Guide</h3><p>The Starcatcher guide, granted when the specialization is chosen.</p></div>
    <div><h3>Steady Hands</h3><p>An easier fishing minigame: the catch bar drains slower, a miss costs less, the score comes quicker, and a sweet spot lingers.</p></div>
  </div>
</article>

<article id="archaeologist">
  <div class="head">
    <img src="{{ '/icons/archaeologist.png' | relative_url }}" alt="">
    <div>
      <h2>Archaeologist</h2>
      <p class="desc">Excavation. Gates all excavation tools, so no one else can work a dig site.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Excavation Tools</h3><p>Ability to craft all excavation tools, including the diamond brush and the rusty pickaxe and shovel.</p></div>
  </div>
</article>

<article id="bard">
  <div class="head">
    <img src="{{ '/icons/bard.png' | relative_url }}" alt="">
    <div>
      <h2>Bard</h2>
      <p class="desc">Music and recruitment. Gates all instruments and villager recruitment, so only a Bard can put a villager to work.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Instruments</h3><p>Ability to craft all instruments, including the lute, flute, trumpet, vielle, piano, handpan, bagpipe, didgeridoo, ender bass, triangle and tiny drum.</p></div>
    <div><h3>Recruitment</h3><p>The ability to recruit villagers, which no other specialization has. A villager with no profession follows a Bard alone; trading stays open to everyone.</p></div>
  </div>
</article>

<article id="brewer">
  <div class="head">
    <img src="{{ '/icons/brewer.png' | relative_url }}" alt="">
    <div>
      <h2>Brewer</h2>
      <p class="desc">Fermenting and brewing drinks, which is separate from the Alchemist's potion brewing. Gates all beers and the vessel every cider, wine and mead comes out of.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>The Keg</h3><p>Ability to craft the keg and the mug. Every beer is brewed in the keg and nowhere else, so all twelve follow it.</p></div>
    <div><h3>Hops</h3><p>Ability to craft hop seeds, and to grow the crop they produce on the underside of a block.</p></div>
    <div><h3>The Fermentation Vessel</h3><p>Ability to craft the fermentation vessel, which the three ciders, the two wines, the mead, both pickles and the popped maize all come out of.</p></div>
  </div>
</article>

<article id="curator">
  <div class="head">
    <img src="{{ '/icons/curator.png' | relative_url }}" alt="">
    <div>
      <h2>Curator</h2>
      <p class="desc">Recording the world. Gates all cameras and record-keeping items, so a Curator is how a server documents what it finds.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Photography</h3><p>Ability to craft all photography gear, including the camera and its black-and-white film.</p></div>
    <div><h3>Field Notes</h3><p>Ability to craft all record-keeping items, including the bestiary and its analyzer, the antique atlas and the diary.</p></div>
  </div>
</article>

<article id="herbalist">
  <div class="head">
    <img src="{{ '/icons/herbalist.png' | relative_url }}" alt="">
    <div>
      <h2>Herbalist</h2>
      <p class="desc">Growing and preparing herbs. Gates the hemp crop and everything made from it, along with all non-potion remedies.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Hemp and Cloth</h3><p>Ability to craft all hemp goods, including the crop, its seeds and crates, and burlap and woven cloth in every dye colour.</p></div>
    <div><h3>Preparations</h3><p>Ability to craft all hemp preparations, including pipes, bongs, joints and brownies.</p></div>
    <div><h3>Remedies</h3><p>Ability to craft all remedies, including the aura crystal, cleansing concoction, empowering and focusing oils, and the two teas.</p></div>
  </div>
</article>

<article id="shipwright">
  <div class="head">
    <img src="{{ '/icons/shipwright.png' | relative_url }}" alt="">
    <div>
      <h2>Shipwright</h2>
      <p class="desc">Shipbuilding. Gates all ship builders, so every sailing vessel in the pack is laid down by a Shipwright.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Ship Builders</h3><p>Ability to craft all ship builders, including the cog, caravel, general and decorative builders.</p></div>
  </div>
</article>

<article id="tailor">
  <div class="head">
    <img src="{{ '/icons/tailor.png' | relative_url }}" alt="">
    <div>
      <h2>Tailor</h2>
      <p class="desc">Clothing. Gates the sewing bench and all hats and garments made on it.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>The Sewing Bench</h3><p>Ability to craft the sewing kit and the sewing table, which all other pieces are made on.</p></div>
    <div><h3>Hats</h3><p>Ability to craft all headwear, including hats, crowns, hoods and masks.</p></div>
    <div><h3>Garments</h3><p>Ability to craft all garments, including robes, coats, aprons, shirts, trousers, scarves, sandals and boots.</p></div>
  </div>
</article>

</div>
</div>
