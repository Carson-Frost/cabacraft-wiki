---
title: Classes
permalink: /classes/
intro: >-
  Each player has a class and a specialization alongside their race, all chosen at the start.
  There are fifteen classes in total, organized by three Paths: Combat, Innovation, and Creation.
  These classes largely work by gating recipes to items within the class that no other class has
  access to. Classes can also grant bonuses or gate entire game mechanics, like a combat roll or
  access to a workstation entirely. Specializations are smaller versions of classes that are
  chosen as secondary roles.
---

<div class="tabs">
<input type="radio" name="tab" id="t1" checked><label for="t1">Combat</label>
<input type="radio" name="tab" id="t2"><label for="t2">Innovation</label>
<input type="radio" name="tab" id="t3"><label for="t3">Creation</label>
<input type="radio" name="tab" id="t4"><label for="t4">Specializations</label>
<div class="group" id="g1">
<p class="groupdesc">The fighting Path. Its seven Classes craft the weapons and armor a fight is won with, and five of them carry a combat bonus of their own. Warrior, Ranger, Mage, Paladin, Rogue, Blacksmith and Gunsmith.</p>
<article id="warrior">
  <div class="head">
    <img src="{{ '/icons/warrior.png' | relative_url }}" alt="">
    <div>
      <h2>Warrior</h2>
      <p class="desc">Melee combat with strong defense. Gates the heaviest armor in the class tree and carries a melee damage bonus.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Warplate</h3><p>Ability to craft the Warrior class plate sets, the Warrior and the Berserker.</p></div>
    <div><h3>Field Harness</h3><p>Ability to craft the two starter harnesses, the Ironclad and the Brawler. The Ironclad trades movement speed for its extra plate.</p></div>
    <div><h3>Weapon Master</h3><p>An additional 5% melee damage with any weapon.</p></div>
  </div>
</article>

<article id="ranger">
  <div class="head">
    <img src="{{ '/icons/ranger.png' | relative_url }}" alt="">
    <div>
      <h2>Ranger</h2>
      <p class="desc">Ranged combat at a distance. Gates every bow, crossbow and musket in the class tree along with the light ranged armor, and carries a ranged damage bonus.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Bows and Crossbows</h3><p>Ability to craft every bow and crossbow in the class tree, including the royal and composite longbows, the mechanic shortbow, and the heavy and rapid crossbows.</p></div>
    <div><h3>Black Powder</h3><p>Ability to craft the black powder weapons, the muskets, pistols and blunderbuss, along with the cartridges and upgrade template they need.</p></div>
    <div><h3>Ranged Leathers</h3><p>Ability to craft the Ranger class light armor sets, the Archer and the Ranger.</p></div>
    <div><h3>Field Kit</h3><p>Ability to craft the field kit, the quiver and the auto-fire hook.</p></div>
    <div><h3>Marksman</h3><p>An additional 5% damage from any bow or crossbow.</p></div>
  </div>
</article>

<article id="mage">
  <div class="head">
    <img src="{{ '/icons/mage.png' | relative_url }}" alt="">
    <div>
      <h2>Mage</h2>
      <p class="desc">Spellcasting at a distance. Gates every staff, wand and school robe in the class tree, and carries a spell power bonus.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Staves</h3><p>Ability to craft every staff, in the wizard, arcane, fire and frost schools.</p></div>
    <div><h3>Wands</h3><p>Ability to craft every wand, in the novice, arcane, fire and frost schools.</p></div>
    <div><h3>School Robes</h3><p>Ability to craft the school robes, in arcane, fire and frost.</p></div>
    <div><h3>Wizard's Robes</h3><p>Ability to craft the two general robes, the Wizard Robe and the Immersive Robe.</p></div>
    <div><h3>Arcane Focus</h3><p>An additional 5% spell power.</p></div>
  </div>
</article>

<article id="paladin">
  <div class="head">
    <img src="{{ '/icons/paladin.png' | relative_url }}" alt="">
    <div>
      <h2>Paladin</h2>
      <p class="desc">Healing and holy combat. Gates the pack's healing gear, its shields and two armor lines, and carries a healing bonus. It is the one Class with a workbench of its own.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>The Monk's Workbench</h3><p>Ability to craft the monk's workbench, which every other piece of Paladin gear is made on.</p></div>
    <div><h3>Holy Arms</h3><p>Ability to craft the holy wands and staves, and the acolyte wand beneath them.</p></div>
    <div><h3>Kite Shields</h3><p>Ability to craft kite shields, in iron, gold and diamond.</p></div>
    <div><h3>Consecrated Plate</h3><p>Ability to craft the Paladin class plate sets, the Paladin, Crusader, Justicar and Divine.</p></div>
    <div><h3>Vestments</h3><p>Ability to craft the Priest class robes, the Priest and the Prior.</p></div>
    <div><h3>Laying On Hands</h3><p>An additional 5% healing.</p></div>
  </div>
</article>

<article id="rogue">
  <div class="head">
    <img src="{{ '/icons/rogue.png' | relative_url }}" alt="">
    <div>
      <h2>Rogue</h2>
      <p class="desc">Fast, lightly armored melee. Gates the light armor line, which trades protection for evasion and attack speed, and is the only Class that can combat roll.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Shadowweave</h3><p>Ability to craft the Rogue class light armor sets, the Rogue and the Assassin.</p></div>
    <div><h3>Light Mail</h3><p>Ability to craft the light mail pieces, in iron, gold and diamond.</p></div>
    <div><h3>Combat Roll</h3><p>The ability to combat roll, which no other Class has at all.</p></div>
  </div>
</article>

<article id="blacksmith">
  <div class="head">
    <img src="{{ '/icons/blacksmith.png' | relative_url }}" alt="">
    <div>
      <h2>Blacksmith</h2>
      <p class="desc">Weaponsmithing. Gates every melee weapon in the class tree, so every other Class buys its blades from a Blacksmith. Offered under both the Combat and the Creation Path.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Rare Steel</h3><p>Ability to craft the rarest blades, the aeternium and ruby daggers and the unique longsword.</p></div>
    <div><h3>Blades</h3><p>Ability to craft the bladed weapons, including claymores, daggers, glaives and sickles, in iron, gold and diamond.</p></div>
    <div><h3>Blunt Arms</h3><p>Ability to craft the blunt weapons, including maces, great hammers and double axes, in iron, gold and diamond.</p></div>
    <div><h3>Reach Weapons</h3><p>Ability to craft the reach weapons, the spears, in flint, iron, gold and diamond.</p></div>
  </div>
</article>

<article id="gunsmith">
  <div class="head">
    <img src="{{ '/icons/gunsmith.png' | relative_url }}" alt="">
    <div>
      <h2>Gunsmith</h2>
      <p class="desc">Firearms and artillery. Gates every gun and cannon in the class tree except the muskets, which belong to the Ranger. Offered under both the Combat and the Innovation Path.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Firearms</h3><p>Ability to craft the firearms, the revolver, shotgun, nailgun and blazegun.</p></div>
    <div><h3>Cannonry</h3><p>Ability to craft the cannon and the gear that works it, the mount, carriage, loader and drill, and the autocannon barrel.</p></div>
  </div>
</article>

</div>
<div class="group" id="g2">
<p class="groupdesc">The technology Path. Its six Classes craft the machinery, firearms, potions and enchanting the rest of the pack runs on. Engineer, Machinist, Gunsmith, Originator, Alchemist and Enchanter.</p>
<article id="engineer">
  <div class="head">
    <img src="{{ '/icons/engineer.png' | relative_url }}" alt="">
    <div>
      <h2>Engineer</h2>
      <p class="desc">Mechanical automation. Gates Create's machinery, so every powered contraption in the pack starts with an Engineer.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>The Engineer's Own</h3><p>Ability to craft the Engineer's own tools, the wrench, the goggles and the schematic table.</p></div>
    <div><h3>Kinetics</h3><p>Ability to craft the power train, including water wheels, hand cranks, gearboxes, gearshifts, clutches, belts and encased fans.</p></div>
    <div><h3>Processing</h3><p>Ability to craft the processing machines, including millstones, basins, mixers, presses, saws, drills and blaze burners.</p></div>
    <div><h3>Automation</h3><p>Ability to craft the automation blocks, including deployers, depots, mechanical arms and pistons.</p></div>
  </div>
</article>

<article id="machinist">
  <div class="head">
    <img src="{{ '/icons/machinist.png' | relative_url }}" alt="">
    <div>
      <h2>Machinist</h2>
      <p class="desc">Powered flight. Gates the parts an airship is built from, so no other Class can get one off the ground.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Bearings</h3><p>Ability to craft the bearings an airship turns on, the propeller bearing and the gyroscopic propeller bearing.</p></div>
    <div><h3>Propellers</h3><p>Ability to craft the propellers, in wood, andesite and smart.</p></div>
    <div><h3>Flight Kit</h3><p>Ability to craft the pilot's gear, the adjustable burner and the aviator's goggles.</p></div>
  </div>
</article>

<article id="gunsmith">
  <div class="head">
    <img src="{{ '/icons/gunsmith.png' | relative_url }}" alt="">
    <div>
      <h2>Gunsmith</h2>
      <p class="desc">Firearms and artillery. Gates every gun and cannon in the class tree except the muskets, which belong to the Ranger. Offered under both the Combat and the Innovation Path.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Firearms</h3><p>Ability to craft the firearms, the revolver, shotgun, nailgun and blazegun.</p></div>
    <div><h3>Cannonry</h3><p>Ability to craft the cannon and the gear that works it, the mount, carriage, loader and drill, and the autocannon barrel.</p></div>
  </div>
</article>

<article id="originator">
  <div class="head">
    <img src="{{ '/icons/originator.png' | relative_url }}" alt="">
    <div>
      <h2>Originator</h2>
      <p class="desc">Electrical power. Gates Oritech's generation and storage, so every electrically powered machine in the pack starts with an Originator.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Generation</h3><p>Ability to craft the generators, the basic, bio and fuel generators and the big solar panel.</p></div>
    <div><h3>Storage and Transfer</h3><p>Ability to craft the power storage and wiring, the basic and advanced batteries and the energy pipe.</p></div>
    <div><h3>Machine Bodies</h3><p>Ability to craft the machine bodies every Oritech machine is built on, the machine frame and the machine core.</p></div>
  </div>
</article>

<article id="alchemist">
  <div class="head">
    <img src="{{ '/icons/alchemist.png' | relative_url }}" alt="">
    <div>
      <h2>Alchemist</h2>
      <p class="desc">Potion brewing. The only Class that can brew at all, so every potion in the world was made by an Alchemist, and its own elixirs run longer in its hands.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>The Elixir Bench</h3><p>Ability to craft the brewing bench and its fittings, the glass cauldron, the alchemist's eye and the potion shelf.</p></div>
    <div><h3>The Only Brewer</h3><p>The ability to use a brewing stand or a glass cauldron, which no other Class has at all. An Alchemist's own elixirs also last longer, and a hostile one thrown at them wears off faster.</p></div>
  </div>
</article>

<article id="enchanter">
  <div class="head">
    <img src="{{ '/icons/enchanter.png' | relative_url }}" alt="">
    <div>
      <h2>Enchanter</h2>
      <p class="desc">Enchanting past the world's limits. Every enchantment in the pack is capped, and an Enchanter is the only Class that reaches a level beyond the cap.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Enchant Mastery</h3><p>An additional level on every one of the 33 capped enchantments.</p></div>
    <div><h3>Ancient Books</h3><p>Ability to craft the Ancient Book.</p></div>
  </div>
</article>

</div>
<div class="group" id="g3">
<p class="groupdesc">The making Path. Its four Classes craft the pack's blocks, blades, jewelry and food. Builder, Blacksmith, Jeweler and Cook.</p>
<article id="builder">
  <div class="head">
    <img src="{{ '/icons/builder.png' | relative_url }}" alt="">
    <div>
      <h2>Builder</h2>
      <p class="desc">Building at scale. Gates the workstations that carve every decorative block variant in the pack, and reaches further to place and break.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Workstations</h3><p>Ability to craft the eight Chipped workstations, and through them every block variant they carve.</p></div>
    <div><h3>Long Arm</h3><p>An additional half block of reach for placing and breaking. Combat reach is unchanged.</p></div>
  </div>
</article>

<article id="blacksmith">
  <div class="head">
    <img src="{{ '/icons/blacksmith.png' | relative_url }}" alt="">
    <div>
      <h2>Blacksmith</h2>
      <p class="desc">Weaponsmithing. Gates every melee weapon in the class tree, so every other Class buys its blades from a Blacksmith. Offered under both the Combat and the Creation Path.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Rare Steel</h3><p>Ability to craft the rarest blades, the aeternium and ruby daggers and the unique longsword.</p></div>
    <div><h3>Blades</h3><p>Ability to craft the bladed weapons, including claymores, daggers, glaives and sickles, in iron, gold and diamond.</p></div>
    <div><h3>Blunt Arms</h3><p>Ability to craft the blunt weapons, including maces, great hammers and double axes, in iron, gold and diamond.</p></div>
    <div><h3>Reach Weapons</h3><p>Ability to craft the reach weapons, the spears, in flint, iron, gold and diamond.</p></div>
  </div>
</article>

<article id="jeweler">
  <div class="head">
    <img src="{{ '/icons/jeweler.png' | relative_url }}" alt="">
    <div>
      <h2>Jeweler</h2>
      <p class="desc">Accessory crafting. Gates the pack's rings and necklaces, which are worn in accessory slots alongside armor rather than instead of it.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>The Kit</h3><p>Ability to craft the jeweler's kit, which every ring and necklace is made on.</p></div>
    <div><h3>Rings</h3><p>Ability to craft the rings, in jade and tanzanite.</p></div>
    <div><h3>Necklaces</h3><p>Ability to craft the necklaces, in jade and tanzanite.</p></div>
  </div>
</article>

<article id="cook">
  <div class="head">
    <img src="{{ '/icons/cook.png' | relative_url }}" alt="">
    <div>
      <h2>Cook</h2>
      <p class="desc">Cooking, which matters more here than in vanilla because food is how you heal. Gates every prepared dish in the pack and the kitchen stations the rest of the pack's cooking runs through.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>The Kitchen</h3><p>Ability to craft the kitchen stations, the gristmill, fermentation vessel, cooking pot, skillet, stove and cutting board. Any dish made on one of them is a Cook's, whether or not it has a recipe of its own.</p></div>
    <div><h3>Baking</h3><p>Ability to craft the baked goods, including pies, tarts, cakes and bread, from the shepherd's pie to the sponge cake.</p></div>
    <div><h3>Sweets</h3><p>Ability to craft the sweets, including candies, candied fruit, cookies and the melon popsicle.</p></div>
    <div><h3>Preserves and Drinks</h3><p>Ability to craft the preserves and drinks, including the compote cups, the brewed teas, milk and melon juice.</p></div>
    <div><h3>Dishes</h3><p>Ability to craft the prepared dishes, including stews, medleys, chows, salads, sandwiches, rolls and roasts, and the feasts a whole table eats from.</p></div>
  </div>
</article>

</div>
<div class="group" id="g4">
<article id="angler">
  <div class="head">
    <img src="{{ '/icons/angler.png' | relative_url }}" alt="">
    <div>
      <h2>Angler</h2>
      <p class="desc">Fishing. Gates the pack's rods and tackle, and makes the fishing minigame easier to land.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Rods</h3><p>Ability to craft the fishing rods, the bamboo and the azure crystal.</p></div>
    <div><h3>Tackle</h3><p>Ability to craft the tackle, the copper and amethyst hooks and the bobber.</p></div>
    <div><h3>The Guide</h3><p>The Starcatcher guide, granted when the Specialization is chosen.</p></div>
    <div><h3>Steady Hands</h3><p>An easier fishing minigame: the catch bar drains slower, a miss costs less, the score comes quicker, and a sweet spot lingers.</p></div>
  </div>
</article>

<article id="archaeologist">
  <div class="head">
    <img src="{{ '/icons/archaeologist.png' | relative_url }}" alt="">
    <div>
      <h2>Archaeologist</h2>
      <p class="desc">Excavation. Gates the tools both of the pack's digging systems need, so no one else can work a dig site.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Excavation Tools</h3><p>Ability to craft the excavation tools, the diamond brush and the rusty pickaxe and shovel.</p></div>
  </div>
</article>

<article id="bard">
  <div class="head">
    <img src="{{ '/icons/bard.png' | relative_url }}" alt="">
    <div>
      <h2>Bard</h2>
      <p class="desc">Music and recruitment. Gates every instrument in the pack, and is the only role a villager will follow.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Instruments</h3><p>Ability to craft every instrument, including the lute, flute, trumpet, vielle, piano, handpan, bagpipe, didgeridoo, ender bass, triangle and tiny drum.</p></div>
    <div><h3>Recruitment</h3><p>The ability to recruit villagers, which no other Specialization has at all. A villager with no profession follows a Bard alone; trading stays open to everyone.</p></div>
  </div>
</article>

<article id="brewer">
  <div class="head">
    <img src="{{ '/icons/brewer.png' | relative_url }}" alt="">
    <div>
      <h2>Brewer</h2>
      <p class="desc">Fermenting and brewing drinks, which is separate from the Alchemist's potion brewing. Gates every beer in the pack and the vessel every cider, wine and mead comes out of.</p>
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
      <p class="desc">Recording the world. Gates the pack's cameras and record-keeping items, so a Curator is how a server documents what it finds.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Photography</h3><p>Ability to craft the camera and its black-and-white film.</p></div>
    <div><h3>Field Notes</h3><p>Ability to craft the record-keeping items, the bestiary and its analyzer, the antique atlas and the diary.</p></div>
  </div>
</article>

<article id="herbalist">
  <div class="head">
    <img src="{{ '/icons/herbalist.png' | relative_url }}" alt="">
    <div>
      <h2>Herbalist</h2>
      <p class="desc">Growing and preparing herbs. Gates the hemp crop and everything made from it, along with the pack's non-potion remedies.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Hemp and Cloth</h3><p>Ability to craft the hemp goods, the crop, its seeds and crates, and burlap and woven cloth in every dye colour.</p></div>
    <div><h3>Preparations</h3><p>Ability to craft what the crop becomes, including pipes, bongs, joints and brownies.</p></div>
    <div><h3>Remedies</h3><p>Ability to craft the remedies, the aura crystal, cleansing concoction, empowering and focusing oils, and the two teas.</p></div>
  </div>
</article>

<article id="shipwright">
  <div class="head">
    <img src="{{ '/icons/shipwright.png' | relative_url }}" alt="">
    <div>
      <h2>Shipwright</h2>
      <p class="desc">Shipbuilding. Gates the ship builders, so every sailing vessel in the pack is laid down by a Shipwright.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>Ship Builders</h3><p>Ability to craft the ship builders, the cog, caravel and general builders, and the decorative builder.</p></div>
  </div>
</article>

<article id="tailor">
  <div class="head">
    <img src="{{ '/icons/tailor.png' | relative_url }}" alt="">
    <div>
      <h2>Tailor</h2>
      <p class="desc">Clothing. Gates the sewing bench and every hat and garment made on it.</p>
    </div>
  </div>
  <div class="pow">
    <div><h3>The Sewing Bench</h3><p>Ability to craft the sewing kit and the sewing table, which every other piece is made on.</p></div>
    <div><h3>Hats</h3><p>Ability to craft the headwear, including hats, crowns, hoods and masks.</p></div>
    <div><h3>Garments</h3><p>Ability to craft the garments, including robes, coats, aprons, shirts, trousers, scarves, sandals and boots.</p></div>
  </div>
</article>

</div>
</div>
