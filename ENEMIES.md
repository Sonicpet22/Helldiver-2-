# ข้อมูลศัตรู Helldivers 2

ทะเบียนหน่วยศัตรูทุกฝ่าย: พลังชีวิต ขนาด ดาเมจที่ทำใส่เรา ประเภทดาเมจ และระดับความยากต่ำสุดที่เจอ
ดึงจาก [Helldivers Wiki](https://helldivers.wiki.gg/wiki/Enemies) เมื่อ 5 ตุลาคม 2026 รวม **87** หน่วย

ตัวเลขเปลี่ยนตามแพตช์ ถ้าค่าในเกมไม่ตรงกับตารางนี้ ให้ยึดค่าในเกมเป็นหลัก
ข้อมูลชุดเดียวกันอยู่ใน [`data/enemies.json`](data/enemies.json) และข้อมูลอาวุธอยู่ใน [WEAPONS.md](WEAPONS.md)

## วิธีอ่านตาราง

- **พลังชีวิต** คือค่าหลักของตัว บางหน่วยมีค่าแยกตามส่วน (เช่น ตัวถัง/ป้อมปืน) หรือเปลี่ยนตามความยาก
- **ขนาด** ใช้ระดับของวิกิ: เล็ก (0), กลาง (1), ใหญ่ (2), มหึมา (3), หนักพิเศษ (4)
- **ดาเมจ** คือดาเมจที่หน่วยนั้นทำใส่ Helldiver แยกตามท่าโจมตี คั่นด้วย `;`
- **ความยากต่ำสุด** คือระดับความยากแรกที่หน่วยนี้เริ่มโผล่ (1 Trivial ถึง 10 Super Helldive)
- **ตัวคูณธาตุ** แสดงเฉพาะหน่วยที่วิกิระบุว่ารับดาเมจไฟ/อาร์ก/กรด/แก๊สต่างจากปกติ
- ส่วนที่หุ้มเกราะต้องใช้อาวุธที่ค่า AP สูงพอ ดูตารางเจาะเกราะใน [WEAPONS.md](WEAPONS.md#ระดับเจาะเกราะ)

## สรุปจำนวน

| ฝ่าย | จำนวนหน่วย |
| --- | ---: |
| เทอร์มินิด (แมลง) | 30 |
| ออโตมาตอน (หุ่นยนต์) | 37 |
| อิลลูมิเนต (หมึก) | 16 |
| ซูเปอร์เอิร์ธ (ฝ่ายเดียวกัน) | 4 |

## เทอร์มินิด (แมลง)

แมลงที่หลุดจากฟาร์ม Element-710 โจมตีด้วยการรุมเข้าประชิดและพ่นกรดระยะไกล

### กองกำลังหลัก

| ชื่อ | พลังชีวิต | ขนาด | ดาเมจที่ทำใส่เรา | ประเภทดาเมจ | ความยากต่ำสุด | ตัวคูณธาตุ |
| --- | --- | --- | --- | --- | --- | --- |
| [Scavenger](https://helldivers.wiki.gg/wiki/Scavenger) | 60 | เล็ก | 40 Slash | Melee | 1 Trivial | — |
| [Bile Spitter](https://helldivers.wiki.gg/wiki/Bile_Spitter) | 60 | เล็ก | 15 Bile Spit + 3/s Acid Burn (4s); 85 Death Explosion + 3/s Acid Burn (4s) | Acid | 1 Trivial | — |
| [Pouncer](https://helldivers.wiki.gg/wiki/Pouncer) | 60 | เล็ก | 40 Slash | Melee | 2 Easy | — |
| [Hunter](https://helldivers.wiki.gg/wiki/Hunter) | 130 - Medium & Below; 160 - Challenging & Above | เล็ก | 35 Slash; 35 Pounce; 30 Tongue / 3/s Tongue, Acid Burn (4s) | Melee; Acid | 2 Easy | — |
| [Shrieker](https://helldivers.wiki.gg/wiki/Shrieker) | — | เล็ก | 50 Dive; 40 Ragdoll | Melee | 4 Challenging | — |
| [Warrior](https://helldivers.wiki.gg/wiki/Warrior) | 250 - Medium & Below; 325 - Challenging & Above | กลาง | 55 Slash | Melee | 1 Trivial | — |
| [Bile Warrior](https://helldivers.wiki.gg/wiki/Bile_Warrior) | 325 | กลาง | 55 Slash; 85 Death Explosion + 3/s Acid Burn (4s) | Melee; Acid | 4 Challenging | — |
| [Alpha Warrior](https://helldivers.wiki.gg/wiki/Alpha_Warrior) | 325 | กลาง | 55 Slash | Melee | 8 Impossible | — |
| [Hive Guard](https://helldivers.wiki.gg/wiki/Hive_Guard) | 500 | กลาง | 55 Slash | Melee | 2 Easy | — |
| [Nursing Spewer](https://helldivers.wiki.gg/wiki/Nursing_Spewer) | 750 | กลาง | 50/s Putrid Regurgitation + 3/s Acid Burn (4s); 300 Death Rupture + 3/s Acid Burn (4s); 55 Slash | Acid; Melee | 3 Medium | — |
| [Bile Spewer](https://helldivers.wiki.gg/wiki/Bile_Spewer) | 750 | กลาง | 55 Slash; 50 Bile Regurgitation + 3/s Acid Burn (4s); 500 Bile Bombard Direct + 200 Area of Effect; 300 Death + 3/s Acid Burn (4s) | Melee; Ballistic; Acid; Explosion | 3 Medium | — |
| [Brood Commander](https://helldivers.wiki.gg/wiki/Brood_Commander) | 800 | ใหญ่ | 70 Bull Rush; 55 Slash | Melee | 1 Trivial | — |
| [Alpha Commander](https://helldivers.wiki.gg/wiki/Alpha_Commander) | 1,000 | ใหญ่ | 70 Primal Rush; 55 Slash | Melee | 8 Impossible | — |
| [Stalker](https://helldivers.wiki.gg/wiki/Stalker) | 800 | ใหญ่ | 35 Barbed Tongue; 50 Impaling Strike | Melee | 4 Challenging | — |
| [Charger](https://helldivers.wiki.gg/wiki/Charger) | 2,400 | ใหญ่ | 350 Stomp; 90 Trample; 30 End Charge | Melee | 4 Challenging | — |
| [Spore Charger](https://helldivers.wiki.gg/wiki/Spore_Charger) | 2,400 | ใหญ่ | 350 Stomp; 90 Trample; 30 End Charge; 300 Death Explosion + 3/s Acid Burn (4s) | Melee; Acid | 7 Suicide Mission | — |
| [Charger Behemoth](https://helldivers.wiki.gg/wiki/Charger_Behemoth) | 3,000 | ใหญ่ | 350 Stomp; 90 Trample; 30 End Charge | Melee | 3 Medium | — |
| [Impaler](https://helldivers.wiki.gg/wiki/Impaler) | 4,000 | ใหญ่ | 350 Stomp; 35 Tentacle Impact; 150 Tentacle Impact | Melee; Explosion | 5 Hard | — |
| [Bile Titan](https://helldivers.wiki.gg/wiki/Bile_Titan) | 6,500 | มหึมา | 60 Bile Spew + 3/s Acid Burn (4s) + 85 Area of Effect + 3/s Acid Burn (4s); 1000 Stomp + 0 Area of Effect | Acid; Melee | 4 Challenging | — |
| [Dragonroach](https://helldivers.wiki.gg/wiki/Dragonroach) | 6,500 | มหึมา | Fire Breath + 100 Burn DPS; X Area of Effect Burn / X/s Area of Effect Fire | Fire | 5 Hard | — |
| [Hive Lord](https://helldivers.wiki.gg/wiki/Hive_Lord) | 150,000 | มหึมา | 25 Burrow; 50 Surfacing + 20 Area of Effect; 100 Body Slam; 80 Bile Rain + 50 Area of Effect; 100 Rock Impact + 50 Area of Effect | Melee; Acid; Explosion | 7 Suicide Mission | — |

- **Scavenger** — The lowliest of Terminids, slow and weak, but capable of attracting nearby bug breaches.
- **Bile Spitter** — One of the smallest Terminids, but still deadly with its ranged acid spit.
- **Pouncer** — Agile Terminids that are able to leap great distances to attack Helldivers.
- **Hunter** — Stealthy Terminids engaging in ambush tactics, able to leap great distances and slow Helldivers with their tongue.
- **Shrieker** — Flying Terminids specialized in hit-and-run tactics.
- **Warrior** — Medium sized Terminid adept in close-quarters combat.
- **Bile Warrior** — A mutated variant of the Warrior that explodes upon death.
- **Alpha Warrior** — A faster and deadlier variant of the Warrior. Spawned by Alpha Commanders.
- **Hive Guard** — A variant of the Warrior with medium armor covering its head and legs.
- **Nursing Spewer** — A sluggish, medium armored Terminid that can spew corrosive bile over a wide area.
- **Bile Spewer** — An armored variant of the Nursing Spewer capable of launching Bile mortars.
- **Brood Commander** — Leadership-class Terminid capable of coordinating attacks and deploying reinforcements.
- **Alpha Commander** — A heavier variant of the Brood Commander, capable of calling in Alpha Warriors.
- **Stalker** — A specialized Terminid capable of turning partially invisible and ambushing Helldivers. Spawns from Stalker Lairs.
- **Charger** — Fast-moving Terminid specialized in charging attacks. Covered head to claw in heavy armor.
- **Spore Charger** — A Charger variant that creates a thick fog and a massive explosion on death.
- **Charger Behemoth** — A Charger variant with even more durable armor.
- **Impaler** — Heavily armored Terminid that uses large, bladed tentacles to disrupt Helldiver movements.
- **Bile Titan** — Massive Terminid with a potent bile attack, stomp attacks, and heavy armor.
- **Dragonroach** — Massive flying Terminid with a potent fire breath attack and heavy armor.
- **Hive Lord** — Gigantic Terminid capable of traversing underground, expelling bile and crushing targets with its body weight.

### สายพันธุ์ Predator

| ชื่อ | พลังชีวิต | ขนาด | ดาเมจที่ทำใส่เรา | ประเภทดาเมจ | ความยากต่ำสุด | ตัวคูณธาตุ |
| --- | --- | --- | --- | --- | --- | --- |
| [Predator Hunter](https://helldivers.wiki.gg/wiki/Predator_Hunter) | 175 | เล็ก | 35 Slash; 35 Pounce; 30 Tongue / 3/s Tongue, Acid Burn (4s); 50 Reflux / 3/s Spit, Acid Burn (4s) | Melee; Acid | 2 Easy | — |
| [Predator Stalker](https://helldivers.wiki.gg/wiki/Predator_Stalker) | 650 | ใหญ่ | 55 Slash | Melee | 4 Challenging | — |

- **Predator Hunter** — A mutated variant of the Hunter that is significantly more aggressive, capable of cloaking, and can spew bile.
- **Predator Stalker** — A mutated, more aggressive variant of the Stalker that is unable to cloak but spawns as a regular part of patrols.

### สายพันธุ์ Spore Burst

| ชื่อ | พลังชีวิต | ขนาด | ดาเมจที่ทำใส่เรา | ประเภทดาเมจ | ความยากต่ำสุด | ตัวคูณธาตุ |
| --- | --- | --- | --- | --- | --- | --- |
| [Spore Burst Scavenger](https://helldivers.wiki.gg/wiki/Spore_Burst_Scavenger) | 60 | เล็ก | 40 Slash; 25 Death 3/s Death, Acid Burn (4s) | Melee; Acid; Explosion | 2 Easy | — |
| [Spore Burst Hunter](https://helldivers.wiki.gg/wiki/Spore_Burst_Hunter) | 160 | เล็ก | 35 Slash; 35 Pounce; 30 Tongue / 3/s Tongue, Acid Burn (4s); 35 Mycotic Death / 3/s Death, Acid Burn (4s) | Melee; Acid; Explosion | 2 Easy | — |
| [Spore Burst Warrior](https://helldivers.wiki.gg/wiki/Spore_Burst_Warrior) | 325 | กลาง | 55 Slash; 50 Mycotic Death / 3/s Death, Acid Burn (4s) | Melee; Acid | 2 Easy | — |
| [Spore Burst Bile Titan](https://helldivers.wiki.gg/wiki/Spore_Burst_Bile_Titan) | 7,000 | มหึมา | 35 Mycotic Surge + 15 Area of Effect; 1000 Stomp + 0 Area of Effect; 75 Death Throes + 3/s Death, Acid Burn (4s) | Acid; Melee; Explosion | 5 Hard | — |

- **Spore Burst Scavenger** — A mutated variant of the Scavenger that explodes into a deadly spore cloud upon death.
- **Spore Burst Hunter** — A mutated variant of the Hunter that explodes into a deadly spore cloud upon death.
- **Spore Burst Warrior** — A mutated variant of the Warrior that explodes into a deadly spore cloud upon death.
- **Spore Burst Bile Titan** — A mutated variant of the Bile Titan with a potent bile spew capable of buffing nearby enemies.

### สายพันธุ์ Rupture

| ชื่อ | พลังชีวิต | ขนาด | ดาเมจที่ทำใส่เรา | ประเภทดาเมจ | ความยากต่ำสุด | ตัวคูณธาตุ |
| --- | --- | --- | --- | --- | --- | --- |
| [Rupture Warrior](https://helldivers.wiki.gg/wiki/Rupture_Warrior) | 250 | กลาง | 55 Slash/Unburrow | Melee | 6 Extreme | — |
| [Rupture Spewer](https://helldivers.wiki.gg/wiki/Rupture_Spewer) | 750 | กลาง | 35 Bile Globules + 50+100/s Bile Spew + 3/s Acid Burn (4s); 800 Bile Bomb / 200 Area of Effect; 300 Death Explosion + 3/s Acid Burn (4s) + 55 Slash | Acid; Melee; Ballistic | 6 Extreme | — |
| [Rupture Charger](https://helldivers.wiki.gg/wiki/Rupture_Charger) | 2,400 | ใหญ่ | 350 Emerging Explosion; 350 Stomp; 90 Trample; 30 End Charge | Explosion; Melee | 6 Extreme | — |

- **Rupture Warrior** — A burrowing variant of the Warrior.
- **Rupture Spewer** — A burrowing variant of the Bile Spewer.
- **Rupture Charger** — A burrowing variant of the Charger.

## ออโตมาตอน (หุ่นยนต์)

ทายาทของไซบอร์กที่ต้องการแยกตัวจากซูเปอร์เอิร์ธ ใช้ทหารราบหุ้มเกราะ ยานรบ และสิ่งก่อสร้างสนับสนุนอย่างปืนครก

### กองกำลังหลัก

| ชื่อ | พลังชีวิต | ขนาด | ดาเมจที่ทำใส่เรา | ประเภทดาเมจ | ความยากต่ำสุด | ตัวคูณธาตุ |
| --- | --- | --- | --- | --- | --- | --- |
| [Trooper](https://helldivers.wiki.gg/wiki/Trooper) | 125 | เล็ก | 35 Fusion SMG; 200 Grenade; 35 Steel Fist Punch | Ballistic; Explosion; Melee | 1 Trivial | — |
| [Brawler](https://helldivers.wiki.gg/wiki/Brawler) | 125 | เล็ก | 60 Heat Blade Slash; 200 Grenade | Melee; Explosion | 1 Trivial | — |
| [Commissar](https://helldivers.wiki.gg/wiki/Commissar) | 125 | เล็ก | 35 Fusion Pistol; 200 Grenade; 60 Heat Blade Slash | Ballistic; Explosion; Melee | 1 Trivial | — |
| [Rocket Raider](https://helldivers.wiki.gg/wiki/Rocket_Raider) | 125 | เล็ก | 70 Rocket Blast; 200 Grenade; 30 Rocket Impact; 35 Steel Fist Punch | Explosion; Ballistic; Melee | 2 Easy | — |
| [Assault Raider](https://helldivers.wiki.gg/wiki/Assault_Raider) | 125 | เล็ก | 35 Fusion Pistol; 200 Grenade; 130 Jetpack Explosion / 100/s (3s) Jetpack Explosion; 60 Heat Blade Slash | Ballistic; Explosion; Fire; Melee | 1 Trivial | — |
| [Marauder](https://helldivers.wiki.gg/wiki/Marauder) | 125 | เล็ก | 35 Fusion SMG; 200 Grenade; 35 Steel Fist Punch | Ballistic; Explosion; Melee | 5 Hard | — |
| [MG Raider](https://helldivers.wiki.gg/wiki/MG_Raider) | 125 | เล็ก | 35 Light Fusion Repeater; 200 Grenade; 130 Backpack / 100/s (3s) Backpack; 35 Steel Fist Punch | Ballistic; Explosion; Fire; Melee | 2 Easy | — |
| [Berserker](https://helldivers.wiki.gg/wiki/Berserker) | 750 | กลาง | 80 Meatsaw Slash; 100 Stomp | Melee | 2 Easy | — |
| [Devastator](https://helldivers.wiki.gg/wiki/Devastator) | 750 | กลาง | 35 Fusion Assault Cannon; 80 Reinforced Fist Punch; 100 Stomp | Ballistic; Melee | 2 Easy | — |
| [Rocket Devastator](https://helldivers.wiki.gg/wiki/Rocket_Devastator) | 750 | กลาง | 35 Fusion Arm Cannon; 70 Rocket Blast / 30 Rocket Impact; 80 Reinforced Fist Punch; 100 Stomp | Ballistic; Explosion; Melee | 1 Trivial | — |
| [Heavy Devastator](https://helldivers.wiki.gg/wiki/Heavy_Devastator) | 750 | กลาง | 35 Fusion Repeater; 80 Reinforced Fist Punch; 100 Stomp | Ballistic; Melee | 1 Trivial | — |
| [Scout Strider](https://helldivers.wiki.gg/wiki/Scout_Strider) | 500 | ใหญ่ | 60 Fusion Heavy Repeater; 100 Stomp | Ballistic; Melee | 3 Medium | — |
| [Reinforced Scout Strider](https://helldivers.wiki.gg/wiki/Reinforced_Scout_Strider) | 500 | ใหญ่ | 60 Heavy Fusion Repeater; 400 Rocket Blast / 30 Rocket Impact; 100 Stomp | Ballistic; Explosion; Melee | 8 Impossible | — |
| [Hulk Obliterator](https://helldivers.wiki.gg/wiki/Hulk_Obliterator) | 1,800 | ใหญ่ | 70 Rocket Blast / 30 Rocket Impact; 200 Weapon Swing; 200 Vertical Slam; 100 Heavy Stomp | Explosion; Ballistic; Melee | 3 Medium | — |
| [Hulk Scorcher](https://helldivers.wiki.gg/wiki/Hulk_Scorcher) | 1,800 | ใหญ่ | 60 DPS Heavy Flamethrower / 100 Burn DPS; 100 Reactor Meltdown Explosion; 200 Rotary Saw; 200 Vertical Slam; 100 Heavy Stomp | Fire; Explosion; Melee | 4 Challenging | — |
| [Hulk Bruiser](https://helldivers.wiki.gg/wiki/Hulk_Bruiser) | 1,800 | ใหญ่ | 60 Fusion Autocannon / 30 Rocket Impact + 70 Rocket Splash; 150 Vent Explosion; 100 Death Explosion; 65 Rocket Arm Swing; 200 Cannon Arm Swing; 200 Vertical Slam; 100 Heavy Stomp | Ballistic; Explosion; Melee | 4 Challenging | — |
| [War Strider](https://helldivers.wiki.gg/wiki/War_Strider) | 3,500 | ใหญ่ | 80 Fusion Culverin Impact / 65 Fusion Culverin Blast; 200 Grenade Explosion; 350 Stomp | Ballistic; Explosion | 6 Extreme | — |
| [Annihilator Tank](https://helldivers.wiki.gg/wiki/Annihilator_Tank) | 4,000 (Hull Main); 2,100 (Turret Main) | ใหญ่ | 35 Coaxial Fusion Cycler; 60 Hull Heavy Fusion Repeater; 1500 Fusion Battle Cannon Impact / 100 Fusion Cannon Blast; 100 Turret Explosion; 1 Death Explosion | Ballistic; Explosion | 3 Medium | — |
| [Shredder Tank](https://helldivers.wiki.gg/wiki/Shredder_Tank) | 4,000 (Main); 2,100 (Turret) | ใหญ่ | 60 Quad Heavy Fusion Cyclers; 1 Death Explosion | Ballistic; Explosion | 3 Medium | — |
| [Barrager Tank](https://helldivers.wiki.gg/wiki/Barrager_Tank) | 4,000 (Main); 2,100 (Turret) | ใหญ่ | 30 Ballistic Rocket Impact / 400 Ballistic Rocket Blast; 100 Turret Death; 1 Death Explosion | Explosion | 7 Suicide Mission | — |
| [Gunship](https://helldivers.wiki.gg/wiki/Gunship) | 950 | ใหญ่ | 65 Heavy Fusion Cycler; 70 Rocket Blast / 30 Rocket Impact; 100 Death Explosion | Ballistic; Explosion | 5 Hard | — |
| [Dropship](https://helldivers.wiki.gg/wiki/Dropship) | 3,500 | มหึมา | — | — | 1 Trivial | — |
| [Factory Strider](https://helldivers.wiki.gg/wiki/Factory_Strider) | 10,000 | มหึมา | 35 Fusion Gatling Guns; 1500 Repeater Cannon Impact / 100 Repeater Cannon Blast; 300 Death | Ballistic; Explosion | 4 Challenging | — |

- **Trooper** — Light Automaton unit armed with a fusion SMG and explosive grenades.
- **Brawler** — Light Automaton unit armed with twin heated blades that specializes in close-quarters combat.
- **Commissar** — Light Automaton squad leader armed with a sidearm and heat blade for versatile offensive options.
- **Rocket Raider** — Light Automaton unit armed with a rocket launcher.
- **Assault Raider** — Light Automaton unit armed with a fusion pistol, a blade, and a jetpack.
- **Marauder** — Reinforced Automaton unit armed with a fusion rifle and explosive grenades.
- **MG Raider** — Reinforced Automaton unit armed with a fusion machine gun, explosive grenades, and a volatile backpack with a tendency to explode.
- **Berserker** — Durable Automaton unit armed with dual chainsaws that specialize in close-quarters combat.
- **Devastator** — Medium-armored Automaton unit armed with fusion assault cannons.
- **Rocket Devastator** — Devastator variant armed with fusion arm cannons and shoulder-mounted rocket launchers, capable of hitting Helldivers behind cover.
- **Heavy Devastator** — Devastator variant armed with a fusion machine gun and a large shield, capable of suppressing Helldivers and blocking incoming fire.
- **Scout Strider** — Armored Automaton recon walker, armed with a heavy fusion repeater and manned by a single Trooper shielded from small arms fire from the front.
- **Reinforced Scout Strider** — A reinforced variant of the Scout Strider armed with rockets and armor surrounding the entire pilot.
- **Hulk Obliterator** — Large, heavily armored Automaton unit armed with dual rocket launchers.
- **Hulk Scorcher** — Hulk variant armed with a heavy flamethrower and large sawblade, specializing in close-quarters combat.
- **Hulk Bruiser** — Hulk variant equipped with a burst rocket launcher and fusion autocannon.
- **War Strider** — Heavily armored Automaton walker unit armed with Heavy Fusion Repeaters and explosive grenade launchers.
- **Annihilator Tank** — Tank-armored Automaton unit armed with fusion machine guns and a large cannon.
- **Shredder Tank** — Tank variant armed with a quad-linked heavy fusion cycler turret.
- **Barrager Tank** — Tank variant armed with a large missile array capable of direct & mortar fire.
- **Gunship** — Medium-armored flying Automaton unit armed with fusion machine guns and rockets.
- **Dropship** — Unarmed Automaton ship that drops in fellow Automaton units in response to a Bot Drop flare.
- **Factory Strider** — Massive Automaton quad-walker, armed with twin fusion gatling guns and a large burst-cannon. Capable of creating and deploying squads of Devastators.

### Jet Brigade

| ชื่อ | พลังชีวิต | ขนาด | ดาเมจที่ทำใส่เรา | ประเภทดาเมจ | ความยากต่ำสุด | ตัวคูณธาตุ |
| --- | --- | --- | --- | --- | --- | --- |
| [Jet Brigade Commissar](https://helldivers.wiki.gg/wiki/Jet_Brigade_Commissar) | 125 | เล็ก | 35 Fusion Pistol; 200 Grenade; 130 Jetpack Explosion / 100/s (3s) Jetpack Explosion; 60 Heat Blade Slash | Ballistic; Explosion; Fire; Melee | 1 Trivial | — |
| [Jet Brigade Trooper](https://helldivers.wiki.gg/wiki/Jet_Brigade_Trooper) | 125 | เล็ก | 35 Fusion SMG; 200 Grenade; 130 Jetpack Explosion / 100/s (3s) Jetpack Explosion; 35 Steel Fist Punch | Ballistic; Explosion; Fire; Melee | 3 Medium | — |
| [Jet Brigade MG Raider](https://helldivers.wiki.gg/wiki/Jet_Brigade_MG_Raider) | 125 | เล็ก | 35 Light Fusion Repeater; 200 Grenade; 130 Jetpack Explosion / 100/s (3s) Jetpack Explosion; 35 Steel Fist Punch | Ballistic; Explosion; Fire; Melee | 2 Easy | — |
| [Jet Brigade Devastator](https://helldivers.wiki.gg/wiki/Jet_Brigade_Devastator) | 750 | กลาง | 35 Fusion Assault Cannon; 130 Jetpack Explosion / 100/s (3s) Jetpack Explosion; 80 Reinforced Fist Punch; 100 Stomp | Ballistic; Explosion; Fire; Melee | — | — |
| [Jet Brigade Hulk Scorcher](https://helldivers.wiki.gg/wiki/Jet_Brigade_Hulk_Scorcher) | 1,800 | ใหญ่ | 60 DPS Heavy Flamethrower / 100 Burn DPS; 500 Heavy Jump Pack Explosion / 100/s (3s) Jetpack Explosion; 100 Death Explosion; 200 Rotary Saw; 200 Vertical Slam; 100 Heavy Stomp | Fire; Melee | 4 Challenging | — |
| [Jet Brigade Hulk Bruiser](https://helldivers.wiki.gg/wiki/Jet_Brigade_Hulk_Bruiser) | 1,800 | ใหญ่ | 60 Fusion Autocannon; 30 Rocket Impact + 70 Rocket Splash; 500 Heavy Jump Pack Explosion / 100/s (3s) Jetpack Explosion; 100 Death Explosion; 65 Rocket Arm Swing; 200 Cannon Arm Swing; 100 Vertical Slam; 100 Heavy Stomp | Ballistic; Explosion; Fire; Melee | 4 Challenging | — |

- **Jet Brigade Commissar** — Commissar variant equipped with a jetpack for leaping large distances.
- **Jet Brigade Trooper** — Trooper variant equipped with a jetpack for leaping large distances.
- **Jet Brigade MG Raider** — MG Raider variant equipped with a jetpack for leaping large distances.
- **Jet Brigade Devastator** — Devastator variant equipped with a jetpack for leaping large distances.
- **Jet Brigade Hulk Scorcher** — A variant of the Hulk Scorcher equipped with a large jetpack, allowing them to leap great distances.
- **Jet Brigade Hulk Bruiser** — A variant of the Hulk Bruiser equipped with a large jetpack, allowing them to leap great distances.

### Incineration Corps

| ชื่อ | พลังชีวิต | ขนาด | ดาเมจที่ทำใส่เรา | ประเภทดาเมจ | ความยากต่ำสุด | ตัวคูณธาตุ |
| --- | --- | --- | --- | --- | --- | --- |
| [Pyro Trooper](https://helldivers.wiki.gg/wiki/Pyro_Trooper) | — | เล็ก | 60 DPS Portable Flamer; 400 Fuel Tank Explosion; 300 White Phosphorus Grenade / 100 Burn DPS (3s); 35 Steel Fist Punch | Fire; Explosion; Melee | 1 Trivial | — |
| [Incendiary Rocket Raider](https://helldivers.wiki.gg/wiki/Incendiary_Rocket_Raider) | 125 | เล็ก | 80 Portable Fusion Cannon Impact / 50 Portable Fusion Cannon Blast; 300 White Phosphorus Grenade / 100 Burn DPS (3s); 35 Steel Fist Punch | Ballistic; Explosion; Fire; Melee | 1 Trivial | — |
| [Incendiary MG Devastator](https://helldivers.wiki.gg/wiki/Incendiary_MG_Devastator) | 750 | กลาง | 30 Fusion Conflagrator / 100 DPS Burn (3s); 80 Reinforced Fist Punch; 100 Stomp | Ballistic; Fire; Melee | 3 Medium | — |
| [Conflagration Devastator](https://helldivers.wiki.gg/wiki/Conflagration_Devastator) | 750 | กลาง | 300(12 x 25 pellets) Conflagration Scattergun / 100 Burn DPS (3s); 80 Reinforced Fist Punch; 100 Stomp | Ballistic; Fire; Melee | 1 Trivial | — |
| [Hulk Firebomber](https://helldivers.wiki.gg/wiki/Hulk_Firebomber) | 1,800 | ใหญ่ | 0 Rotary Phosphorus Launcher Impact / 300 Rotary Phosphorus Launcher Blast; 60 DPS Heavy Flamethrower / 100 Burn DPS (3s) Fire; 150 Vent Explosion; 100 Death Explosion; 200 Flamer Arm Swing; 200 Launcher Arm Swing; 200 Vertical Slam; 100 Heavy Stomp | Ballistic; Explosion; Fire; Melee | 4 Challenging | — |

- **Pyro Trooper** — Reinforced Automaton unit equipped with a flamethrower and a backpack-mounted fuel tank.
- **Incendiary Rocket Raider** — Light Automaton unit armed with a specialized rocket launcher.
- **Incendiary MG Devastator** — Heavy Devastator variant with a slower-firing incendiary fusion machine gun.
- **Conflagration Devastator** — Devastator variant armed with an incendiary fusion shotgun and a large shield, capable of suppressing Helldivers and blocking incoming fire.
- **Hulk Firebomber** — Hulk variant equipped with a large flamethrower and incendiary grenade launcher.

### Cyborg Legion

| ชื่อ | พลังชีวิต | ขนาด | ดาเมจที่ทำใส่เรา | ประเภทดาเมจ | ความยากต่ำสุด | ตัวคูณธาตุ |
| --- | --- | --- | --- | --- | --- | --- |
| [Radical](https://helldivers.wiki.gg/wiki/Radical) | 750 | กลาง | 100 (10 x 10 pellets) Plasma Scattergun; 60 Augmented Punch; 50 Techno-Martial Arts | Ballistic; Melee | 1 Trivial | — |
| [Agitator](https://helldivers.wiki.gg/wiki/Agitator) | 750 | กลาง | 45 Plasma Charger; 65 Plasma Charger Overcharge Impact / 30 Plasma Charger Overcharge Explosion; 200 Grenade; 60 Augmented Punch; 50 Techno-Martial Arts | Ballistic; Melee; Explosion | 1 Trivial | — |
| [Vox Engine](https://helldivers.wiki.gg/wiki/Vox_Engine) | 9,000 | มหึมา | 20 Plasma Duster Miniguns; 80 Plasma Macro-Culverin Impact / 50 Plasma Macro-Culverin Blast; 30 Icarus Missile Launcher Impact / 250 Icarus Missile Launcher Explosion | Ballistic; Explosion | 7 Suicide Mission | — |

- **Radical** — Cybernetically enhanced human soldiers equipped with a heavy shotgun and "techno-martial arts."
- **Agitator** — Cyborg field commanders, able to take direct command of their Automaton underlings.
- **Vox Engine** — Massive Cyborg Mech equipped with heavy fusion cannons, a missile array, and gatling guns.

## อิลลูมิเนต (หมึก)

เผ่าพันธุ์โบราณที่กลับมาแก้แค้น ใช้โล่พลังงาน เจ็ตแพ็ก อาวุธพลาสมา และโดรน

### กองกำลังหลัก

| ชื่อ | พลังชีวิต | ขนาด | ดาเมจที่ทำใส่เรา | ประเภทดาเมจ | ความยากต่ำสุด | ตัวคูณธาตุ |
| --- | --- | --- | --- | --- | --- | --- |
| [Voteless](https://helldivers.wiki.gg/wiki/Voteless) | 100 (Light); 130 (Medium); 160 (Heavy) | เล็ก | 25 Swipe and Claw | Melee | 1 Trivial | — |
| [Watcher](https://helldivers.wiki.gg/wiki/Watcher) | 600 | กลาง | 30 Tesla Discharge; 300 Crashing Impact; 80 Death Explosion | Arc; Explosion | 1 Trivial | — |
| [Overseer](https://helldivers.wiki.gg/wiki/Overseer) | 600 | กลาง | 75 Staff Swing; 40 Plasma Projectile; 30 Plasma Burst | Melee; Ballistic; Explosion | 1 Trivial | — |
| [Elevated Overseer](https://helldivers.wiki.gg/wiki/Elevated_Overseer) | 450 | กลาง | 35 Plasma Storm Rifle; 200 Plasma Detonator; 150 Jetpack Detonation | Ballistic; Explosion | 3 Medium | — |
| [Crescent Overseer](https://helldivers.wiki.gg/wiki/Crescent_Overseer) | 600 | กลาง | 40 Plasma Bolt Impact / 75 Plasma Bolt Blast; 60 Armoured Fist Punch | Ballistic; Explosion; Melee | 3 Medium | — |
| [Fleshmob](https://helldivers.wiki.gg/wiki/Fleshmob) | 5,000 | ใหญ่ | 50 Flail; 30 Initial Charge Impact | Melee | 1 Trivial | อาร์ก ×1.8 |
| [Harvester](https://helldivers.wiki.gg/wiki/Harvester) | 3,000 | ใหญ่ | 1,400-1,800 DPS Disintegration Beamer + 100/s(3s) Beam Burn; 60 Tesla Ripper | Laser; Arc | 3 Medium | — |
| [Stingray](https://helldivers.wiki.gg/wiki/Stingray) | 800 | ใหญ่ | 50 Plasma Destructor Impact / 125 Plasma Destructor Blast; 100 Crash and Burn; 300 Death Explosion | Ballistic; Explosion | — | — |
| [Warp Ship](https://helldivers.wiki.gg/wiki/Warp_Ship) | 3,500 | มหึมา | — | None | 1 Trivial | — |
| [Leviathan](https://helldivers.wiki.gg/wiki/Leviathan) | 15,000 | มหึมา | 400 DPS Disintegration Culverin + 100 DPS(3s) Beam Burn; 250 Plasma Bomb | Laser; Explosion | 8 Impossible | — |
| [Illuminate Overship](https://helldivers.wiki.gg/wiki/Illuminate_Overship) | 18,001 | มหึมา | — | — | 1 Trivial | — |

- **Voteless** — An Agile skirmisher unit that attacks in hordes.
- **Watcher** — Flying drone equipped with arc weaponry and the ability to call for reinforcements.
- **Overseer** — Elite unit equipped with an energy shield and a deadly lance capable of launching an explosive projectile, usually accompanies hordes of Voteless.
- **Elevated Overseer** — Elite unit equipped with automatic plasma rifles and jet-packs, usually accompanies hordes of Voteless.
- **Crescent Overseer** — Elite unit equipped with a large plasma cannon, capable of direct & mortar fire, usually accompanies hordes of Voteless.
- **Fleshmob** — An amalgamation of Voteless corpses, this large Illuminate unit specializes in close-quarters combat and charges at Helldivers to attack.
- **Harvester** — Massive autonomous tripod with an energy shield and a large laser weapon. Can also use arc weaponry in close quarters.
- **Stingray** — Flying Illuminate unit that deploys strafing runs against Helldivers, dealing massive damage over a large area.
- **Warp Ship** — Transport aircraft used for deploying reinforcements for the Illuminate.
- **Leviathan** — Tank-armored flying Illuminate unit, armed with large beam cannons and bomb bays.
- **Illuminate Overship** — Unarmed host ships, these units act as command centers for Illuminate ground forces.

### Appropriators

| ชื่อ | พลังชีวิต | ขนาด | ดาเมจที่ทำใส่เรา | ประเภทดาเมจ | ความยากต่ำสุด | ตัวคูณธาตุ |
| --- | --- | --- | --- | --- | --- | --- |
| [Veracitor](https://helldivers.wiki.gg/wiki/Veracitor) | 3,000 | — | 75 Clawed Swipe; 300 Sundering Slam; 70 Shouldered Ram | Melee | 4 Challenging | — |
| [Gatekeeper](https://helldivers.wiki.gg/wiki/Gatekeeper) | 2,500 | — | 110 Plasma Starcannon Charged Shot / 60 Plasma Starcannon Charged Blast; 30 Plasma Starcannon Volley Shot / 20 Plasma Starcannon Volley Blast; 35 Plasma Starcannon Bludgeon | Ballistic; Explosion; Melee | 4 Challenging | — |
| [Obtruder](https://helldivers.wiki.gg/wiki/Obtruder) | 400 | — | 35 Plasma Torch; 300 Crashing Impact; 80 Death Explosion | Ballistic; Explosion | 1 Trivial | — |

- **Veracitor** — A piloted Illuminate war machine, with arm-like appendages.
- **Gatekeeper** — A piloted Illuminate war machine, with plasma guns and increased armor.
- **Obtruder** — Swarming drones that fire plasma projectiles and travel in groups. A variation of the watcher.

### Vote Snatchers

| ชื่อ | พลังชีวิต | ขนาด | ดาเมจที่ทำใส่เรา | ประเภทดาเมจ | ความยากต่ำสุด | ตัวคูณธาตุ |
| --- | --- | --- | --- | --- | --- | --- |
| [Wretch](https://helldivers.wiki.gg/wiki/Wretch) | 450 | กลาง | 50 Blade Protrusion / 25 Swiping Hand | Melee | 1 Trivial | — |
| [Crusher](https://helldivers.wiki.gg/wiki/Crusher) | 6,000 | ใหญ่ | 200 Heavy Cudgel / 50 Ground Quake; Cudgel + Ground Quake Explosion | Melee; Explosion | 4 Challenging | — |

- **Wretch** — Former Super Earth citizens twisted beyond recognition into ravenous predators as violent as they are nimble.
- **Crusher** — Ungainly flesh amalgamations that wield massive metallic clubs and are capable of regenerating tissue damage.

## ซูเปอร์เอิร์ธ (ฝ่ายเดียวกัน)

พลเมืองและทหารฝ่ายเดียวกัน ไม่โจมตีเรา แต่โดนลูกหลงจากเราได้

### พลเมืองและทหาร

| ชื่อ | พลังชีวิต | ขนาด | ดาเมจที่ทำใส่เรา | ประเภทดาเมจ | ความยากต่ำสุด | ตัวคูณธาตุ |
| --- | --- | --- | --- | --- | --- | --- |
| [Civilian](https://helldivers.wiki.gg/wiki/Civilian) | 70 | เล็ก | — | — | 1 Trivial | — |
| [SEAF Soldier](https://helldivers.wiki.gg/wiki/SEAF_Soldier) | 150 | เล็ก | — | Ballistic; Explosion | 1 Trivial | — |
| [Helldiver](https://helldivers.wiki.gg/wiki/Helldiver) | 125 | เล็ก | — | Everything | 1 Trivial | แก๊ส ×1.3 |

- **Civilian** — Unarmed Super Earth citizens, mostly found running away from danger.
- **SEAF Soldier** — Lightly-armored Super Earth ground troops, variously armed with assault rifles, SMGs, machine guns, expendable anti-tank launchers, and explosive grenades.
- **Helldiver** — Super Earth's elite fighting force, these units can be equipped with a variety of weapons, stratagems, and employ a variety of tactics.

### ยานพาหนะ

| ชื่อ | พลังชีวิต | ขนาด | ดาเมจที่ทำใส่เรา | ประเภทดาเมจ | ความยากต่ำสุด | ตัวคูณธาตุ |
| --- | --- | --- | --- | --- | --- | --- |
| [Ground All-Terrain Extraction Rig (GATER)](https://helldivers.wiki.gg/wiki/Ground_All-Terrain_Extraction_Rig_%28GATER%29) | 12,000 | ใหญ่ | — | — | — | — |

- **Ground All-Terrain Extraction Rig (GATER)** — An armed truck with mounted drill, designed for mobile substance extraction.
