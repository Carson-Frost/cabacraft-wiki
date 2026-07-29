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
    <div><h3>Warrior Armor</h3><p>Ability to craft all Warrior class armor sets, including the Warrior and Berserker plate and the Ironclad and Brawler harnesses beneath them.</p></div>
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
    <div><h3>Ranged Weapons</h3><p>Ability to craft all ranged weapons and their gear, including the royal and composite longbows, the mechanic shortbow, the heavy and rapid crossbows, the muskets, pistols and blunderbuss, and the quiver and auto-fire hook.</p></div>
    <div><h3>Ranger Armor</h3><p>Ability to craft all Ranger class armor sets, including the Archer and the Ranger.</p></div>
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
    <div><h3>Staves and Wands</h3><p>Ability to craft all staves and wands, including the novice, wizard, arcane, fire and frost schools.</p></div>
    <div><h3>Mage Robes</h3><p>Ability to craft all Mage class robes, including the arcane, fire and frost school robes and the Wizard and Immersive robes.</p></div>
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
    <div><h3>Holy Gear</h3><p>Ability to craft all Paladin gear, including the monk's workbench everything else is made on, the holy wands and staves, the acolyte wand, and kite shields in iron, gold and diamond.</p></div>
    <div><h3>Paladin Armor</h3><p>Ability to craft all Paladin class armor sets, including the Paladin, Crusader, Justicar and Divine plate and the Priest and Prior robes.</p></div>
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
    <div><h3>Rogue Armor</h3><p>Ability to craft all Rogue class armor sets, including the Rogue and Assassin leathers and light mail in iron, gold and diamond.</p></div>
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
    <div><h3>Melee Weapons</h3><p>Ability to craft all melee weapons, including claymores, daggers, glaives, sickles, maces, great hammers, double axes and spears in flint, iron, gold and diamond, up to the aeternium and ruby daggers and the unique longsword.</p></div>
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
    <div><h3>Create Machinery</h3><p>Ability to craft all Create machinery, including the power train of water wheels, gearboxes, clutches and belts, the processing machines of millstones, mixers, presses and saws, the automation blocks of deployers, depots and mechanical arms, and the Engineer's own wrench, goggles and schematic table.</p></div>
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
    <div><h3>Airship Parts</h3><p>Ability to craft all airship parts, including the propeller and gyroscopic propeller bearings, the wood, andesite and smart propellers, and the pilot's adjustable burner and aviator's goggles.</p></div>
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
    <div><h3>Oritech Power</h3><p>Ability to craft all Oritech generation and storage, including the basic, bio and fuel generators, the big solar panel, the basic and advanced batteries, the energy pipe, and the machine frame and core every Oritech machine is built on.</p></div>
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
    <div><h3>Brewing Stations</h3><p>Ability to craft all brewing stations, including the brewing bench, the glass cauldron, the alchemist's eye and the potion shelf.</p></div>
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
      <p class="desc">Building at scale. Gates all decorative block variants and the workstations that carve them, and gets a building reach boost.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Workstations</h3><p>Ability to craft all Chipped workstations, and through them every decorative block variant they carve.</p></div>
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
    <div><h3>Melee Weapons</h3><p>Ability to craft all melee weapons, including claymores, daggers, glaives, sickles, maces, great hammers, double axes and spears in flint, iron, gold and diamond, up to the aeternium and ruby daggers and the unique longsword.</p></div>
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
    <div><h3>Jewelry</h3><p>Ability to craft all rings and necklaces in jade and tanzanite, along with the jeweler's kit they are made on.</p></div>
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
    <div><h3>Kitchen Stations</h3><p>Ability to craft all kitchen stations, including the gristmill, cooking pot, skillet, stove and cutting board. Any dish made on one of them is a Cook's, whether or not it has a recipe of its own.</p></div>
    <div><h3>Prepared Food</h3><p>Ability to craft all prepared food, including pies, tarts, cakes and bread, candies and cookies, compotes, teas and juices, and the stews, salads, sandwiches, roasts and whole-table feasts.</p></div>
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
    <div><h3>Rods and Tackle</h3><p>Ability to craft all fishing gear, including the bamboo and azure crystal rods, the copper and amethyst hooks and the bobber.</p></div>
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
    <div><h3>Beer</h3><p>Ability to craft the keg and mug and to grow hops. Every beer is brewed in the keg and nowhere else, so all twelve follow it.</p></div>
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
    <div><h3>Records</h3><p>Ability to craft all record-keeping gear, including the camera and its black-and-white film, the bestiary and its analyzer, the antique atlas and the diary.</p></div>
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
    <div><h3>Hemp</h3><p>Ability to craft all hemp goods, including the crop, its seeds and crates, burlap and woven cloth in every dye colour, and the pipes, bongs, joints and brownies made from it.</p></div>
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
    <div><h3>Clothing</h3><p>Ability to craft all clothing, including hats, crowns, hoods and masks, and robes, coats, aprons, shirts, trousers, scarves and boots, along with the sewing kit and table they are made on.</p></div>
  </div>
</article>

</div>
</div>
