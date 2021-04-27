---
title: "Gnoll"
permalink: /units/Gnoll/
excerpt: "Era of Chaos Gnoll. Gnoll Einheiten. Gnollkrieger. Era of Chaos Eine wilde Kreatur, die in den Sümpfen haust. Sie umzingelt mit Vorliebe in Überzahl einzelne oder schwache Beute."
unitID: 801
last_modified_at: 2021-04-27
locale: de
ref: "Gnoll"
toc: true
---
  ![Gnoll](/images/u/ti_langren.jpg)

## General information
 **Beschreibung:** Eine wilde Kreatur, die in den Sümpfen haust. Sie umzingelt mit Vorliebe in Überzahl einzelne oder schwache Beute.

 **Klasse:** [Offensiv](/de/units/Unit Class Offense/)

 **Klasse Beschreibung:** Offensiv-Einheiten können den Rüstungswert ihrer Ziele senken. Der Effekt ist nicht stapelbar.

 **Fraktion:** [Festung](/de/units/Faction Fortress/)

 **Race:** Bestienmeister

 **Members:** [x9](/de/units/Unit Member x9/)

 **Rang:** [R](/de/units/Unit Rank R/)

 **Starts:** [<i class="fas fa-star"/>](/de/units/Star 1/)

 **Unit Soul:** [Gnoll](/ItemsDE/unt_253/)

 **Short description:** Nahkampf-DPS. Betäubt.

 **Position :** Betäubt Feinde und verursacht massiven Schaden. Angriff steigt gegen die Einheit mit den wenigsten verbleibenden LP.

 **Recommend:** Kreaturen mit niedriger Gesundheit und hohem Angriff. Extrem mächtig, wenn du daran denkst, sie schnell zu heilen.

## Grundwerte
 **Base HP: 761.0**

 **Base ATK: 84.4**

 **Unit Upgrade:** [Unit EXP Upgrade cost per Level](/units/UnitUpgradeEXPPerLevel/)

  |          Grade      |   <i class="fas fa-fan"/>   | <i class="fas fa-shield-alt"/> |    <i class="fas fa-heart"/>   |
  |:--------------------|:--------:|:--------:|:--------:|
  | Grün | 42.2 | 4.5 | 570.75 |
  | Blau | 84.4 | 9.0 | 1141.5 |
  | Blau +1 | 126.6 | 13.5 | 1712.25 |
  | Blau +2 | 177.24 | 18.9 | 2397.15 |
  | Lila | 227.88 | 24.3 | 3082.05 |
  | Lila +1 | 278.52 | 29.7 | 3766.95 |
  | Lila +2 | 337.6 | 36.0 | 4566.0 |
  | Lila +3 | 396.68 | 42.3 | 5365.05 |
  | Orange | 455.76 | 48.6 | 6164.1 |
  | Orange +1 | 523.28 | 55.8 | 7077.3 |
  | Orange +2 | 590.8 | 63.0 | 7990.5 |
  | Orange +3 | 658.32 | 70.2 | 8903.7 |
  | Orange +4 | 725.84 | 77.4 | 9816.9 |
  | Orange +5 | 827.12 | 88.2 | 11186.7 |
  | Rot | 962.16 | 102.6 | 13013.1 |

  |          Stars      |  Extra ATK |  ATK Speed | Extra DEF |    Extra HP   | 
  |:--------------------|:----------:|:----------:|:---------:|:-------------:|
  | **1x** <i class="fas fa-star"/> | 8.44 | 0.5 | 1.8 | 76.1 |
  | **2x** <i class="fas fa-star"/> | 10.128 | 0.53 | 2.39 | 91.32 |
  | **3x** <i class="fas fa-star"/> | 11.816 | 0.55 | 2.98 | 106.54 |
  | **4x** <i class="fas fa-star"/> | 13.504 | 0.58 | 3.57 | 121.76 |
  | **5x** <i class="fas fa-star"/> | 15.192 | 0.6 | 4.16 | 136.98 |
  | **6x** <i class="fas fa-star"/> | 16.88 | 0.63 | 4.75 | 152.2 |

## Ausrüstung

  | I | Ausrüstung  |  Basic stat 1 | Basic stat 2 | 
  |:-:|:-------------|:-------------:|:------------:|
  | ![Werwolfmachete](/images/e/e_8011.png) | [Werwolfmachete](/de/equipment/Werewolf's Machete/) | **ANG** | **ABW** | 
  | ![Werwolf-Turmschild](/images/e/e_8012.png) | [Werwolf-Turmschild](/de/equipment/Werewolf's Square Shield/) | **LP** | **ABW** | 
  | ![Werwolfkette](/images/e/e_8013.png) | [Werwolfkette](/de/equipment/Werewolf's Chain/) | **ANG** | **ABW** | 
  | ![Werwolf-Panzerhandschuhe](/images/e/e_8014.png) | [Werwolf-Panzerhandschuhe](/de/equipment/Werewolf's Gauntlets/) | **LP** | **ABW** | 

## Exklusiv

 **Name:** [Schwert](/de/Exclusive/Gnoll Sword/) 

 **Is Open:** - 

 **Item to Rangaufstieg:** [Schwert-Token](/ItemsDE/con_912/)

 **Skin:** -


## Empfohlene Heilige Embleme

* [Greifenflügel](/de/Emblem/Griffin Wings/) (Rechtschaffen)
* [Das Urteil der Väter](/de/Emblem/The Judgment of Fathers/) (Neutral)
* [Hochmut](/de/Emblem/Arrogance/) (Chaos)

## Kombinationsinfo

  none

## Skills
 <form id="form">
  <label>Skill level: <input type="number" id="level" name="level" placeholder="Skill level" min="1" max="19" value="15"/><br/></label>
  <label>Unit Attack: <input type="number" id="atk" name="atk" placeholder="Attack" min="1" max="999999" value="100000"/><br/></label>
  <label style="display:none;">Unit level: <input type="number" id="unitlevel" name="unitlevel" placeholder="Unit Level" min="1" max="120" value="100"/><br/></label>
  <button type="submit">Calculate SKILLs</button>
  <p id="log"></p>
  </form>
### Ultimative Fähigkeit: Kettenschlag
 **Beschreibung:** <span style="color: #645252;font-size:20px">Der Gnoll fügt einem Ziel </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str1"></span></span><span style="color: black"><span style="color: #645252;font-size:20px"> Schaden zu und </span><span style="color: black"><span style="color: #48b946;font-size:20px">„betäubt“</span><span style="color: black"><span style="color: #645252;font-size:20px"> es 3 Sek. lang.</span><span style="color: black">

### Gewöhnliche Fähigkeit 1 : Primitive Wildnis
 **Beschreibung:** <span style="color: #645252;font-size:20px">Erhöht den ANG des Gnoll um </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str2"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> und sein Angriffstempo um </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str3"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px">.</span><span style="color: black">

### Gewöhnliche Fähigkeit 2 : Seuchensucher
 **Beschreibung:** <span style="color: #645252;font-size:20px">Der Schaden des Gnolls wird erhöht um </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str4"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> und zusätzlich um 5 % pro Debuff auf dem Ziel, bis 5 Stapel.</span><span style="color: black">

### Gewöhnliche Fähigkeit 3 : Hinrichtung
 **Beschreibung:** <span style="color: #645252;font-size:20px">Bei Angriffen auf eine Einheit, die weniger als 30 % ihrer LP hat, steigt der ANG des Gnoll um </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str5"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px">.</span><span style="color: black">

### Fraktions-Spezialfähigkeit I : Seuchenangriff
 **Beschreibung:** <span style="color: #645252;font-size:20px">Festung-Einheiten sind gut darin, die Seuche zu verbreiten. Ihr Schaden wird erhöht um </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str6"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> gegen Einheiten, die unter „Seuche“ leiden.</span><span style="color: black">

### Fraktions-Spezialfähigkeit II : Erhöhte Vitalität
 **Beschreibung:** <span style="color: #645252;font-size:20px">Burg-Einheiten sind geübt in der Heilung auf dem Schlachtfeld; ihre LP-Regeneration wird erhöht – sie stellen alle 3 Sek. </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str7"></span></span><span style="color: black"><span style="color: #645252;font-size:20px"> LP wieder her –, und sie erhalten </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str8"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> Lebensentzug.</span><span style="color: black">

  <script language="JavaScript">
  function skillCalc(event) {
    var LEVEL = document.getElementById('level').value;
    var ATK = document.getElementById('atk').value;
    var TLEVEL = document.getElementById('unitlevel').value;
    let str7 = "(LEVEL*300+2000)"
    let str8 = "(LEVEL*0.3+1)"
    let str5 = "LEVEL*4+26"
    let str6 = "(LEVEL*1+7)"
    let str3 = "LEVEL*0.6+2.4"
    let str4 = "LEVEL*1+4"
    let str1 = "((LEVEL*30+420))*0.01*ATK"
    let str2 = "LEVEL*1.5+13.5"
    let res="ERR";
    try {
     res = eval(str7); document.getElementById('str7').textContent = res;
     res = eval(str8); document.getElementById('str8').textContent = res;
     res = eval(str5); document.getElementById('str5').textContent = res;
     res = eval(str6); document.getElementById('str6').textContent = res;
     res = eval(str3); document.getElementById('str3').textContent = res;
     res = eval(str4); document.getElementById('str4').textContent = res;
     res = eval(str1); document.getElementById('str1').textContent = res;
     res = eval(str2); document.getElementById('str2').textContent = res;
    } catch (e) { log.textContent = "Issue with calculation!";}
    if (event!=null)
      event.preventDefault();
  }
  const form = document.getElementById('form');
  const log = document.getElementById('log');
  form.addEventListener('submit', skillCalc);
  window.onload = skillCalc;
  </script>
## Relevanz
### Kaderverbindung

* **Festung**  (Festung-Kader)
* **Offensiv**  (Offensiv-Kader)
* **R**  (R)

### Heldenbonus
* [Kendal](/de/heroes/Kendal/)  ->   Spezialität:<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Tazar](/de/heroes/Tazar/)  ->   Spezialität:<i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 

## Talent

* Angriff
* LP
* Schaden (Einheit)
* Magieresistenz

 **Talentverbesserung:** [Offensiv-Talenttrank](/ItemsDE/con_786/)


## Awaking

  ![Gnollkrieger](/images/u/tia_langren.jpg)

### Awaking Details
 **Is it possible right now?** YES

 **Awaking Name:** Gnollkrieger

 **Awaking Beschreibung:** Diese blassen Bestien unter dem Mondlicht sind furchtlose Krieger des Sumpflandes. Sie stellen die höchste Soldatenelite der Gnoll-Klans dar und kämpfen für die Befreiung des Festungsvolkes.

### Awaking Tasks
 1. <span style="color: #876741;font-size:18px">Setze einen Gnoll und mindestens </span><span style="color: #1ca216;font-size:18px">3</span><span style="color: #876741;font-size:18px"> Festung-Einheiten ein, um </span><span style="color: #1ca216;font-size:18px">1.000</span><span style="color: #876741;font-size:18px"> Zwerge einmal in der Zwergenschatzkammer zu töten. (Durchmärsche zählen nicht für die Mission.)</span>

 2. <span style="color: #876741;font-size:18px">Töte </span><span style="color: #1ca216;font-size:18px">5</span><span style="color: #876741;font-size:18px"> Monster im Gildenabenteuer.</span>

 3. <span style="color: #876741;font-size:18px">Sammle </span><span style="color: #1ca216;font-size:18px">100</span><span style="color: #876741;font-size:18px"> Gnollkrieger-Seelen im Untergrund: Stufen 14-2 and 14-4.</span>

 4. <span style="color: #876741;font-size:18px">Setze einen Gnoll und </span><span style="color: #1ca216;font-size:18px">3</span><span style="color: #876741;font-size:18px"> Festung-Einheiten ein, um 3 Kämpfe in der Kampagne zu gewinnen. (Durchmärsche zählen nicht für die Mission.)</span>

## Awaken Skills

### 1st Skill (or 2nd): Kettenschlag
 **Beschreibung:** <span style="color: #48b946;font-size:18px">&lt;Kettenschlag&gt;</span><span style="color: #645252;font-size:18px"> Fügt der Zieleinheit zusätzlichen Schaden in Höhe von 400 % des eigenen ANG zu.</span>

### 2nd Skill (or 1st): Kettenpeinigen
 **Beschreibung:** <span style="color: #48b946;font-size:18px">&lt;Kettenschlag&gt;</span><span style="color: #645252;font-size:18px"> Verlängert die Wirkungsdauer des Betäubungseffekts der Fähigkeit auf 5 Sek.</span>

### 3rd Skill (or 4th): Ruf der Wildnis
 **Beschreibung:** <span style="color: #48b946;font-size:18px">&lt;Primitive Wildnis&gt;</span><span style="color: #645252;font-size:18px"> Erhöht die Durchdringung um 100. Dieser Effekt wird gegen mit Betäubung belegte Gegner verdoppelt.</span>

### 4th Skill (or 3rd): Ruf des Ungezähmten
 **Beschreibung:** <span style="color: #48b946;font-size:18px">&lt;Primitive Wildnis&gt;</span><span style="color: #645252;font-size:18px"> Erhöht den Krit. Gesamt-SCHD um 15 %. Dieser Effekt wird gegen mit Seuche belegte Gegner verdoppelt.</span>

### 5th Skill (or 6th): Garantierte Tötung
 **Beschreibung:** <span style="color: #48b946;font-size:18px">&lt;Hinrichtung&gt;</span><span style="color: #645252;font-size:18px"> Erhöht im Kampf gegen Einheiten, deren LP unter 60 % liegen, den eigenen Krit. Treffer um 250.</span>

### 6th Skill (or 5th): Durchbrechen
 **Beschreibung:** <span style="color: #48b946;font-size:18px">&lt;Hinrichtung&gt;</span><span style="color: #645252;font-size:18px"> Erhöht im Kampf gegen Einheiten, deren LP unter 60 % liegen, den eigenen SCHD (Einheit) um 20 %.</span>

## Technical info
 **runart:** 1

 **summon:** 1

 **defshow:** 1.0

 **Rush:** 1

 **Speedattack:** 120

 **Attack Show:** 1.0

 **Attack Area:** 80

 **Attack Range:** 300

 **Attack Speed Show:** 1.0

 **Defense Show:** 1.0

 **Score:** 501

 **HP Show:** 1

 **disrdcvol:** 40

 **Dead Type:** 1

 **s:** 1

 **label1:** 12

 **speedmove:** 100

 **posclass:** 1

 **talk1:** Niemand kann meine Lanze brechen!

 **talk2:** Nur die Toten stellen sich mir!

 **talk3:** Ich kämpfe wacker um Heimat und Vaterland!

