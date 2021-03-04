---
title: "Meerelementar"
permalink: /units/Sea Elemental/
excerpt: "Era of Chaos Einheiten. Einheiten. Era of Chaos Dieser im endlosen Wasser geborene Geist der Tiefe beherrscht die Macht des Meeres und setzt sie ein, um seine Feinde zu vernichten."
unitID: 9903
last_modified_at: 2021-03-04
locale: de
ref: "Meerelementar"
toc: true
---
## General information
 **Beschreibung:** Dieser im endlosen Wasser geborene Geist der Tiefe beherrscht die Macht des Meeres und setzt sie ein, um seine Feinde zu vernichten.

 **Klasse:** [Zauberer](/units/Unit Class Caster/)

 **Klasse Beschreibung:** Da sie die Geheimnisse der Magie beherrschen, haben Zauberer-Einheiten eine höhere Magieresistenz.

 **Fraktion:** [Bucht](/units/Faction Cove/)

 **Race:** Die Tiefsee

 **Members:** [x9](/units/Unit Member x9/)

 **Rank:** [R](/units/Unit Rank R/)

 **Starts:** [<i class="fas fa-star"/>](/units/Star 1/)

 **Short description:** Verlangsamungs-Kontrolle.

 **Position :** Starke Kontrolle in der Schlacht. Schwächt Gegner durchgehend.

 **Recommend:** Mächtige Massenkontrolle, großartige Heilung.

## Grundwerte
 **Base HP: 1446.0**

 **Base ATK: 201.8**

 **Unit Upgrade:** [Unit EXP Upgrade cost per Level](/units/UnitUpgradeEXPPerLevel/)

  |          Grade      |   <i class="fas fa-fan"/>   | <i class="fas fa-shield-alt"/> |    <i class="fas fa-heart"/>   |
  |:--------------------|:--------:|:--------:|:--------:|
  | Grün | 100.9 | 3.25 | 1084.5 |
  | Blau | 201.8 | 6.5 | 2169.0 |
  | Blau +1 | 302.7 | 9.75 | 3253.5 |
  | Blau +2 | 423.78 | 13.65 | 4554.9 |
  | Lila | 544.86 | 17.55 | 5856.3 |
  | Lila +1 | 665.94 | 21.45 | 7157.7 |
  | Lila +2 | 807.2 | 26.0 | 8676.0 |
  | Lila +3 | 948.46 | 30.55 | 10194.3 |
  | Orange | 1089.72 | 35.1 | 11712.6 |
  | Orange +1 | 1251.16 | 40.3 | 13447.8 |
  | Orange +2 | 1412.6 | 45.5 | 15183.0 |
  | Orange +3 | 1574.04 | 50.7 | 16918.2 |
  | Orange +4 | 1735.48 | 55.9 | 18653.4 |
  | Orange +5 | 1977.64 | 63.7 | 21256.2 |
  | Rot | 2300.52 | 74.1 | 24726.6 |

  |          Stars      |  Extra ATK |  ATK Speed | Extra DEF |    Extra HP   | 
  |:--------------------|:----------:|:----------:|:---------:|:-------------:|
  | **1x** <i class="fas fa-star"/> | 20.18 | 0.4 | 1.3 | 144.6 |
  | **2x** <i class="fas fa-star"/> | 24.216 | 0.42 | 1.87 | 173.52 |
  | **3x** <i class="fas fa-star"/> | 28.252 | 0.44 | 2.43 | 202.44 |
  | **4x** <i class="fas fa-star"/> | 32.288 | 0.46 | 3.0 | 231.36 |
  | **5x** <i class="fas fa-star"/> | 36.324 | 0.48 | 3.56 | 260.28 |
  | **6x** <i class="fas fa-star"/> | 40.36 | 0.5 | 4.13 | 289.2 |

## Ausrüstung

  |  Ausrüstung  |  Basic stat 1 | Basic stat 2 | 
  |:-------------|:-------------:|:------------:|
  | [Ewige Träne](/equipment/Ewige Träne/) | **ANG** | **ABW** | 
  | [Kern des Wasserelementars](/equipment/Kern des Wasserelementars/) | **LP** | **ABW** | 
  | [Wellenstrom](/equipment/Wellenstrom/) | **ANG** | **ABW** | 
  | [Wirbelnarbe](/equipment/Wirbelnarbe/) | **LP** | **ABW** | 

## Exklusiv

 **Name:** [Arkangesang](/Exclusive/Sea Elemental Arcane Chant/) 

 **Is Open:** - 

 **Item to Rangaufstieg:** -

 **Skin:** -


## Empfohlene Heilige Embleme

* [Aksoe-Token](/Emblem/Aksoe Token/) (Neutral)
* [Gebrochene Prophez.](/Emblem/Broken Prophecy/) (Böse)
* [Neid](/Emblem/Jealousy/) (Chaos)

## Kombinationsinfo

* [Verlangsamung](/combination/Verlangsamung/) 


## Skills
 <form id="form">
  <label>Skill level: <input type="number" id="level" name="level" placeholder="Skill level" min="1" max="19" value="15"/><br/></label>
  <label style="display:none;">Unit Attack: <input type="number" id="atk" name="atk" placeholder="Attack" min="1" max="999999" value="100000"/><br/></label>
  <label style="display:none;">Unit level: <input type="number" id="unitlevel" name="unitlevel" placeholder="Unit Level" min="1" max="120" value="100"/><br/></label>
  <button type="submit">Calculate SKILLs</button>
  <p id="log"></p>
  </form>
### Ultimative Fähigkeit: Zeitspirale
 **Beschreibung:** <span style="color: #645252;font-size:20px">Der Meerelementar erzeugt alle 30 Sek. für 10 Sek. einen Strudel am Boden, der das Angriffstempo aller gegnerischen Einheiten in Reichweite jede Sekunde um </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str1"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> reduziert. Der Strudel fügt gegnerischen Einheiten im Wirkungsbereich </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str2"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> Schaden zu, wenn er verschwindet.</span><span style="color: black">

### Gewöhnliche Fähigkeit 1 : Geschenk der Flut
 **Beschreibung:** <span style="color: #645252;font-size:20px">Sobald er das Schlachtfeld betritt, erzeugt der Meerelementar einen </span><span style="color: black"><span style="color: #48b946;font-size:20px">&lt;Eisschild&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px"> für verbündete Einheiten in seinem Weg. Der Meereselementar </span><span style="color: black"><span style="color: #48b946;font-size:20px">„verlangsamt“</span><span style="color: black"><span style="color: #645252;font-size:20px"> Angreifer. Der Schild bleibt </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str3"></span></span><span style="color: black"><span style="color: #645252;font-size:20px"> Sek. bestehen.</span><span style="color: black">

### Gewöhnliche Fähigkeit 2 : Ritual der Gezeiten
 **Beschreibung:** <span style="color: #645252;font-size:20px">Zu Beginn der Schlacht erzeugt der Meerelementar einen Kreis, der seine LP um <span style="color: #48b946;font-size:20px"><span id="str4"></span> %</span><span style="color: black"> erhöht. Die Heilung gegnerischer Einheiten wird während des ganzen Kampfes alle 2 Sek. um 1 % reduziert.</span><span style="color: black">

### Gewöhnliche Fähigkeit 3 : Abgrundkäfig
 **Beschreibung:** <span style="color: #645252;font-size:20px">Der Meerelementar beschwört alle 20 Sek. ein Wasserverlies, das 1 zufällige gegnerische Einheit in der hinteren Reihe packt; diese kann weder angreifen noch Fähigkeiten wirken. Das Wasserverlies bleibt </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str5"></span></span><span style="color: black"><span style="color: #645252;font-size:20px"> Sek. lang bestehen.</span><span style="color: black">

### Fraktions-Spezialfähigkeit I : Ruhiger Körper
 **Beschreibung:** <span style="color: #645252;font-size:20px">Bucht-Einheiten sind Stürme gewöhnt; ihre LP werden erhöht um </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str6"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px">, und sie haben eine Wahrscheinlichkeit von 40 %, „Betäubung“ zu widerstehen, solange sie ein Heiliges Emblem ausgerüstet haben.</span><span style="color: black">

### Fraktions-Spezialfähigkeit II : Piratenoffensive
 **Beschreibung:** <span style="color: #645252;font-size:20px">Bucht-Einheiten sind geübt im Krieg auf hoher See. Wenn sie gegen Einheiten kämpfen, die nicht zur Bucht gehören, wird ihr Schaden um </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str7"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px"> erhöht.</span><span style="color: black">

  <script language="JavaScript">
  function skillCalc(event) {
    var LEVEL = document.getElementById('level').value;
    var ATK = document.getElementById('atk').value;
    var TLEVEL = document.getElementById('unitlevel').value;
    let str7 = "(LEVEL*1+5)"
    let str5 = "(LEVEL*0.1+3)"
    let str6 = "(LEVEL*1+5)"
    let str3 = "(LEVEL*1+15)"
    let str4 = "(LEVEL*1+14)"
    let str1 = "(LEVEL*0.5+0.5)"
    let str2 = "((LEVEL*10+60))"
    let res="ERR";
    try {
     res = eval(str7); document.getElementById('str7').textContent = res;
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

* **Bucht**  (Bucht-Kader)
* **Magie**  (Zauberer-Kader)

### Heldenbonus
* [Dracon](/heroes/Dracon/)  ->   Spezialität:<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Cassanbel](/heroes/Cassanbel/)  ->   Spezialität:<i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 

## Talent

* Angriff
* LP
* Angriffstempo
* Magieresistenz


## Awaking
### Awaking Details
 **Is it possible right now?** NO

 **Awaking Name:** Gezeitenelementar

 **Awaking Beschreibung:** Lichtet den Anker und setzt die Segel! Reißt alles in Stücke! Plündert und erobert alles! Verwandelt die Meere in einen Spielplatz!

### Awaking Tasks
 1. <span style="color: #3c2a1e;font-size:18px">Setze Naga und mindestens </span><span style="color: #1ca216;font-size:18px">3</span><span style="color: #3c2a1e;font-size:18px"> Turm-Einheiten ein, um die Stufe Kämpe oder höher von Drachenutopia </span><span style="color: #1ca216;font-size:18px">1</span><span style="color: #3c2a1e;font-size:18px"> Mal zu bestehen. (Überfälle zählen nicht für die Mission.)</span>

 2. <span style="color: #3c2a1e;font-size:18px">Sammle </span><span style="color: #1ca216;font-size:18px">2</span><span style="color: #3c2a1e;font-size:18px"> Ausrüstungsteile im Gildenabenteuer.</span>

 3. <span style="color: #3c2a1e;font-size:18px">Sammle </span><span style="color: #1ca216;font-size:18px">100</span><span style="color: #3c2a1e;font-size:18px"> Nagakönigin-Seelen im Untergrund: Stufen 17-2 und 17-4.</span>

 4. <span style="color: #3c2a1e;font-size:18px">Setze Naga ein, um </span><span style="color: #1ca216;font-size:18px">1</span><span style="color: #3c2a1e;font-size:18px"> Meisterduell-Kampf zu gewinnen.</span>

## Awaken Skills

### 1st Skill (or 2nd): Blutroter Tanz
 **Beschreibung:** <span style="color: #48b946;font-size:18px">&lt;Klingentanz&gt;</span><span style="color: #645252;font-size:18px">Wenn Klingentanz aktiv gewirkt wird, werden Angriffstempo und Lebensentzug der Naga 20 Sek. lang um 30 % erhöht.</span>

### 2nd Skill (or 1st): Scharfer Klingentanz
 **Beschreibung:** <span style="color: #48b946;font-size:18px">&lt;Klingentanz&gt;</span><span style="color: #645252;font-size:18px">Der Fähigkeitenschaden wird auf 200 % des Schadens der vorherigen Fähigkeit erhöht; alle Einheiten in Reichweite erleiden Schaden.</span>

### 3rd Skill (or 4th): Klinge des Willens
 **Beschreibung:** <span style="color: #48b946;font-size:18px">&lt;Klingenkönigin&gt;</span><span style="color: #645252;font-size:18px">Der Bonuseffekt erhöht sich auf 150 % des Effekts der vorherigen Fähigkeit.</span>

### 4th Skill (or 3rd): Wahnsinnige Klinge
 **Beschreibung:** <span style="color: #48b946;font-size:18px">&lt;Klingenkönigin&gt;</span><span style="color: #645252;font-size:18px">Kritischer Treffer und Kritischer Schaden bieten der Naga einen Bonus und erhöhen den Effekt auf 200 % der vorherigen Fähigkeit.</span>

### 5th Skill (or 6th): Magische Haut
 **Beschreibung:** <span style="color: #48b946;font-size:18px">&lt;Magisches Erwachen&gt;</span><span style="color: #645252;font-size:18px">Gewährt 3 Sek. lang Immunität gegen Zauberschaden.</span>

### 6th Skill (or 5th): Magiedurchdrungene Klinge
 **Beschreibung:** <span style="color: #48b946;font-size:18px">&lt;Magisches Erwachen&gt;</span><span style="color: #645252;font-size:18px">Gewährt der Einheit 6 Sek. lang 30 % Bonusschaden.</span>

## Technical info
 **runart:** 0

 **summon:** 1

 **defshow:** 4.0

 **fly:** haiyuansu

 **flyspeed:** 300

 **atkfly:** 1

 **Rush:** 3

 **Speedattack:** 60

 **Attack Show:** 6.0

 **Attack Area:** 230

 **Attack Range:** 300

 **Attack Speed Show:** 4.0

 **Defense Show:** 4.0

 **Score:** 501

 **HP Show:** 6

 **disrdcvol:** 40

 **Dead Type:** 1

 **s:** 2

 **label1:** 13

 **speedmove:** 80

 **posclass:** 5

 **talk1:** Niemand kann meine Lanze brechen!

 **talk2:** Nur die Toten stellen sich mir!

 **talk3:** Ich kämpfe wacker um Heimat und Vaterland!

