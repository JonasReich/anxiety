# act1

```
SceneSetup.act1();
```

(...300)

n: UND DAS IST SEINE ANGST

n: _DU_ BIST DIE ANGST

{{if window.localStorage.continueChapter=="replay"}}
(#act1_replay)
{{/if}}

{{if window.localStorage.continueChapter!="replay"}}
(#act1_normal)
{{/if}}



# act1_replay

`hong({mouth:"0_neutral", eyes:"0_neutral"})`

h: Oh hey! Wir sind wieder hier?

`hong({eyes:"0_neutral"})`

n: DEINE AUFGABE IST, DEINEN MENSCHEN VOR *GEFAHR* ZU SCHÜTZEN

`bb({eyes:"look", mouth:"small_lock"})`

n: TATSÄCHLICH BRINGST DU IHN DURCH DEN SPIEL-NEUSTART IN *AKUTE GEFAHR*

n: SCHNELL, WARN IHN!

```
sfx("squeak");
bb({body:"squeeze_talk"});
hong({body:"0_squeeze"});
```

b: Mensch! Hör zu, wir sind in Gefahr! Der Spieler...

[...wird uns wieder quälen!](#act1_replay_torture)

[...wird kein anderes Ende finden!](#act1_replay_alternate)

[...wird ludonarrative Dissonanz erfahren!](#act1_replay_dissonance)

# act1_replay_torture

```
window.HACK_REPLAY = JSON.parse(localStorage.act4);
bb({body:"normal", mouth:"normal", eyes:"fear"});
hong({body:"0_sammich"});
```

{{if window.HACK_REPLAY.act1_ending=="fight"}}
b: Er wird uns dazu bringen, uns zusammenzurollen und zu weinen!
{{/if}}

{{if window.HACK_REPLAY.act1_ending=="flight"}}
b: Er wird dich wegen einer Panikattacke dein Handy kaputt machen lassen!
{{/if}}

{{if window.HACK_REPLAY.a2_ending=="fight"}}
b: Er wird uns *NICHT* die Gastgeberin der Party schlagen lassen!
{{/if}}

{{if window.HACK_REPLAY.a2_ending=="flight"}}
b: Er wird uns den Antihelden, die sympathische Gastgeberin der Party schlagen lassen!
{{/if}}

{{if window.HACK_REPLAY.a3_ending=="jump"}}
h: Naja vielleicht springen wir dieses Mal wenigstens nicht vom D--
{{/if}}

{{if window.HACK_REPLAY.a3_ending=="walkaway"}}
b: ER WIRD UNS VOM DACH SPRINGEN LASSEN.
{{/if}}

`bb({body:"fear"});`

b: ALL DIESE SCHRECKLICHEN SACHEN WERDEN UNS PASSIEREN, UND DANN--

(#act1_replay_end)


#act1_replay_alternate

```
bb({body:"normal", mouth:"normal", eyes:"fear"});
hong({body:"0_sammich"});
```

h: Klar, die Geschichte als *Ganzes* bleibt gleich, aber jedes Kapitel hat Zwei mögliche Enden und es gibt alle möglichen Dialog Opti--

`bb({body:"fear"});`

b: Der Spieler wird enttäuscht sein, seinen Browser Tab schließen, unsere Software löschen und dann--

(#act1_replay_end)


# act1_replay_dissonance

```
bb({body:"normal", mouth:"normal", eyes:"fear"});
hong({body:"0_sammich"});
```

h: Eine öbszöne was-bitte?

`bb({eyes:"normal"});`

b: Die Handlung ging darum dass du *ENTSCHEIDEN* kannst, dich gesund mit deiner Angst auseinanderzusetzen,

`bb({eyes:"normal_right"});`

b: Aber wenn bei einer Wiederholung die gleiche Geschichte kommt, impliziert das doch, dass deine *ENTSCHEIDUNGEN* egal sind,

`bb({eyes:"narrow_eyebrow"});`

b: Was ein Wiederspruch zwischen der Kernaussage des Spiels und den Spielmechaniken ist,

`bb({eyes:"fear"});`

b: Wodurch sich das Gebilde dieser Narrative in Luft auflöst,

`bb({body:"fear"});`

b: Und dann werden wir--

(#act1_replay_end)


# act1_replay_end

`bb({body:"panic"})`

b: STEEEEEERRRBBBEEEEEEN

```
bb({body:"normal", mouth:"normal", eyes:"normal"});
Game.clearText();
```

(...1001)

```
bb({body:"laugh"});
hong({body:"laugh"});
Game.clearText();
sfx("laugh");
```

(...5001)

```
bb({body:"normal", mouth:"normal", eyes:"normal"});
hong({body:"0_sammich"});
```

h: Okay, versetzen wir uns wieder in die Rolle.

```
Game.clearText();
```

n4: (LASS _DEINE_ ANGST BLA BLA BLA ÄHNLICH ZU DEM WAS _DEINE_ ANGST BLA BLA DU KENNST DEN DREH)

```
sfx("squeak");
hong({body:"0_squeeze"});
bb({body:"squeeze"});
```

(#act1_normal_choice)



# act1_normal

`hong({mouth:"0_neutral", eyes:"0_annoyed"})`

h: Oh gut, mein Wolf ist zurück. Faaaaantastisch.

`hong({eyes:"0_neutral"})`

n: DEINE AUFGABE IST, DEINEN MENSCHEN VOR *GEFAHR* ZU SCHÜTZEN

`bb({eyes:"look", mouth:"small_lock"})`

n: TATSÄCHLICH BRINGT IHN DIESES SANDWICH JETZT GERADE IN *GEFAHR*

n: SCHNELL, WARN IHN!

```
sfx("squeak");
bb({body:"squeeze_talk"});
hong({body:"0_squeeze"});
```

b: Mensch! Hör zu, wir sind in Gefahr! Die Gefahr ist...

`bb({body:"squeeze"})`

n4: (LASS _DEINER_ ANGST FREIEN LAUF! WÄHLE DAS, WAS _DEINE_ ANGST DIR AM EHESTEN SAGEN WÜRDE)

(#act1_normal_choice)

# act1_normal_choice

[Wir essen alleine zu Mittag! Schon wieder!](#act1a_alone) `bb({body:"squeeze_talk"})`

[Wir sind so unproduktiv beim Essen!](#act1a_productive) `bb({body:"squeeze_talk"})`

[Dieses Weißbrot ist schlecht für uns!](#act1a_bread) `bb({body:"squeeze_talk"})`

# act1a_alone

```
bb({body:"normal", mouth:"small", eyes:"narrow"});
hong({body:"0_sammich"});
```

b: Wusstest du nicht, dass Einsamkeit deine Lebensdauer genauso senkt, wie 15 Zigaretten am Tag zu rauchen?-

`Game.OVERRIDE_TEXT_SPEED = 2;`

`bb({mouth:"normal", eyes:"normal_right"})`

b: (Holt-Lunstad 2010, PLoS Medicine)

`hong({eyes:"0_annoyed"})`

h: Äh, danke für die Quellenangabe, aber--

`Game.OVERRIDE_TEXT_SPEED = 2;`

`bb({body:"fear", mouth:"normal", eyes:"fear"})`

b: Was heißt, wenn wir nicht *jetzt gleich* mit irgendwem abhängen, werden wir-

`bb({body:"panic"})`

b: STEEEEEERRRBBBEEEEEEN

```
bb({body:"normal", mouth:"normal", eyes:"normal"});
hong({mouth:"0_shock", eyes:"0_shock"});
attack("18p", "alone");
publish("hp_show");
```

(...2500)

`_.fifteencigs = true`

n: DU HAST *ANGST NICHT GELIEBT ZU WERDEN* BENUTZT

(#act1b)

# act1a_productive

```
bb({body:"normal", mouth:"small", eyes:"normal"});
hong({body:"0_sammich"});
```

b: Hol deinen Laptop raus und mach dich an die Arbeit!

`hong({eyes:"0_annoyed"})`

h: Ähm, ich würde jetzt ungern Brösel in meine Tastatu--

```
bb({mouth:"normal", eyes:"fear"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Wenn wir nichts zur Gesellschaft beitragen, sind wir Sozialparasiten!

b: Die Gesellschft wird zum Gesellschafts-Arzt gehen, um Medizin gegen ihre Sozialparasiten zu holen und dann werden wir-

```
bb({body:"panic", mouth:"normal", eyes:"fear"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: STEEEEEERRRBBBEEEEEEN

```
bb({body:"normal", mouth:"normal", eyes:"normal"});
hong({mouth:"0_shock", eyes:"0_shock"});
attack("18p", "bad");
publish("hp_show");
```

(...2500)

`_.parasite = true`

n: DU HAST *ANGST EIN SCHLECHTER MENSCH ZU SEIN* BENUTZT

(#act1b)

# act1a_bread

```
bb({body:"normal", mouth:"normal", eyes:"fear"});
hong({body:"0_sammich", eyes:"0_annoyed"});
```

h: Wurden diese Studien reproduz--

```
bb({body:"fear", mouth:"normal", eyes:"fear"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Verarbeiteter Weizen treibt deinen Blutzucker in die Höhe und dann müssen sie uns alle Glieder amputieren und dann werden wir-

`bb({body:"panic"})`

b: STEEEEEERRRBBBEEEEEEN

```
bb({body:"normal", mouth:"normal", eyes:"normal"});
hong({mouth:"0_shock", eyes:"0_shock"});
attack("18p", "harm");
publish("hp_show");
```

(...2500)

`_.whitebread = true`

n: DU HAST *ANGST VERLETZT ZU WERDEN* BENUTZT

(#act1b)

# act1b

n: DAS WAR SUPER EFFEKTIV

`bb({mouth:"smile", eyes:"smile"});`

b: Siehst du, Mensch? Ich bin dein treuer Wachwolf!

`bb({body:"pride_talk"});`

b: Vertrau auf deinen Bauch! Deine Gefühle sind immer richtig!

`bb({body:"pride"});`

n: BRING DIE ENERGIELEISTE VON DEINEM MENSCHEN AUF NULL

n: BESCHÜTZE SEINE KÖRPERLICHEN + SOZIALEN + MORALISCHEN BEDÜRFNISSE MIT:

n: ANGST *VERLETZT* ZU WERDEN #harm#

n: ANGST *NICHT GELIEBT* ZU WERDEN #alone#

n: UND ANGST EIN *SCHLECHTER MENSCH* ZU SEIN #bad#

`Game.OVERRIDE_TEXT_SPEED = 1.25;`

n4: (PROFI-TIP: NIMM DIE OPTIONEN, DIE DEINE PERSÖNLICHEN TIEFSTEN, DUNKELSTEN ÄNGSTE AUSLÖSEN)

h: ...

```
hong({body:"putaway"});
sfx("rustle");
bb({body:"normal", mouth:"normal", eyes:"normal"});
```

(...1000)

`Game.OVERRIDE_TEXT_SPEED = 1.5;`

h: weißt du was, vielleicht sollte ich mal auf mein Handy schauen.

```
sfx("rustle2");
hong({body:"phone1", mouth:"neutral", eyes:"neutral"})
```

n: BESCHÜTZE DEINEN MENSCHEN

n: VOR DER WELT. VOR ANDEREN MENSCHEN. VOR SICH SELBST.

n: VIEL GLÜCK

(...500)

`Game.clearText()`

(...500)

(#act1c)

# act1c

`music('battle', {volume:0.5})`

n: ERSTE RUNDE: *UND LOS!*

`bb({body:"normal", mouth:"normal", eyes:"normal"});`

h: Ha. In meinem Facebook Verlauf steht, dass dieses Wochenende eine Party ist.

`bb({eyes:"uncertain"});`

b: Schmeißt diese Spinnerin nicht *jedes* Wochenende eine Party?

`bb({eyes:"uncertain_right"});`

b: Was für eine innere Leere will die denn füllen? Die muss ja total kaputt sein!

`hong({eyes:"surprise"});`

h: Außerdem hab ich 'ne Einladung?

`bb({eyes:"fear", mouth:"normal"});`

b: Na dann!

[Sag ja, oder wir sterben vor Einsamkeit!](#act1c_loner)

[Sag nein, da gibt's gefährliche Drogen!](#act1c_drugs)

[Ignorier's. Wir verderben eh nur den Spaß.](#act1c_sad)

# act1c_loner

{{if _.fifteencigs}}
b: Fünfzehn Zigaretten am Tag, Mensch! Fünfzehn!
{{/if}}

{{if !_.fifteencigs}}
`Game.OVERRIDE_TEXT_SPEED = 1.5;`
{{/if}}

{{if !_.fifteencigs}}
b: Dann wird niemand zu unserer Beerdigung kommen. Sie werden unsere Asche ins Meer werfen, wir werden von einem Wal gegessen
{{/if}}

{{if !_.fifteencigs}}
b: und dann werden wir WAL-KACKE!
{{/if}}

{{if !_.fifteencigs}} `_.whalepoop = true` {{/if}}

(...500)

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "alone");
```

(...2500)

`bb({eyes:"normal"});`

{{if !_.fifteencigs}}
b: Also ja, wir sollten zu der Party gehen!
{{/if}}

{{if _.parasite}}
b: Aber bring deinen Laptop mit damit wir arbeiten können, du Sozialparasit.
{{/if}}

{{if _.whitebread}}
b: Aber nur, wenn's da kein WEISSBROT gibt
{{/if}}

`hong({mouth:"anger", eyes:"anger"});`

h: GOTT. Wenn du dann die Klappe hälst, na gut.

h: Ich sag zu.

{{if _.whalepoop}}
b: Mensch, Wal-Kacke! Wal-Kacke!
{{/if}}

`_.partyinvite="yes"`

(#act1d)

# act1c_drugs

`bb({mouth:"small", eyes:"fear"});`

{{if _.whitebread}}
b: oder noch schlimmer... WEISSBROT
{{/if}}

{{if _.whitebread}}
`Game.OVERRIDE_TEXT_SPEED = 1.5;`
{{/if}}

{{if _.whitebread}}
b: Wir werden 'ne Überdosis an so viel Meth und Weißbrot haben - die werden unsere fette Leiche gar nicht in den Verbrennungs-Ofen krigen!
{{/if}}

{{if !_.whitebread}}
b: Wir werden 'ne Überdosis an so vielen Drogen haben, dass der Leichenbestatter sich wundert, warum unser Körper schon *vorbalsamiert* ist.
{{/if}}

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "harm");
```

(...2500)

{{if _.parasite}}
b: Außerdem kannst du eh nicht Party machen. Wir müssen arbeiten, oder wir werden zu einem schrecklichen Sozialparasiten!
{{/if}}

`hong({mouth:"anger", eyes:"anger"});`

h: GOTT. Wenn du die Klappe hälst, na gut.

h: Ich sag ab.

`_.partyinvite="no"`

(#act1d)

# act1c_sad

`bb({eyes:"uncertain_right", mouth:"normal"});`

`Game.OVERRIDE_TEXT_SPEED = 1.5;`

{{if _.fifteencigs}}
b: Alles was wir je machen, ist in 'ner Ecke zu darüber zu heulen, dass Einsamkeit so tötlich wie 15 Zigaretten am Tag ist.
{{/if}}

{{if _.parasite}}
b: Bei Parties machen wir uns eh die ganze Zeit nur Sorgen, wie wir woanders produktiv sein könnten.
{{/if}}

{{if _.whitebread}}
b: Wir machen uns doch eh den ganzen Tag nur Sorgen, dass uns unsere schlechte Ernährung umbringen wird.
{{/if}}

```
bb({mouth:"normal", eyes:"normal"});
hong({mouth:"neutral", eyes:"lookaway"});
```

h: Mensch, ich frag' mich warum.

`hong({eyes:"neutral"});`

`Game.OVERRIDE_TEXT_SPEED = 1.5;`

b: Also, wenn wir hingehen, fühlt sie sich schlecht, aber wenn wir ihre Einladung ablehnen, genauso!

`bb({body:"fear", eyes:"fear"});`

`Game.OVERRIDE_TEXT_SPEED = 1.5;`

b: WIR VERDERBEN JEDEM STÄNDIG DIE LAUNE. WIR SOLLTEN UNS SCHLECHT FÜHLEN

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "bad");
```

(...2500)

`hong({mouth:"anger", eyes:"anger"});`

h: Uff. Wenn du die Klappe hälst, na gut.

h: Ich werd' die Einladung ignorieren.

`_.partyinvite="ignore"`

(#act1d)

# act1d

```
bb({body:"normal", mouth:"normal", eyes:"normal"});
hong({mouth:"neutral", eyes:"annoyed"});
```

h: Wie auch immer. Facebook ist zu stressig. Ich brauch' was ruhigeres, was nicht so beklemmend ist.

`hong({eyes:"neutral"});`

h: Was gibt's neues auf Twitter?

`bb({eyes:"look"});`

[Diese grauenhaften Nachrichten!](#act1d_news)

[Geht's in dem Tweet heimlich um *uns?*](#act1d_subtweet)

[Ein GIF von 'ner Katze, die Milch trinkt](#act1d_milk)


# act1d_news

```
bb({eyes:"pained1"});
music(null, {fade:2});
```

b: Gott, es fühlt sich an, als geht die Welt unter, oder?

```
bb({eyes:"pained2"});
hong({mouth:"sad", eyes:"sad"});
```

b: Es fühlt sich an, als wär alles vorbei, als ob alles stirbt. Wir sind dem Untergang geweiht und können nichts dagegen tun.

```
Game.OVERRIDE_TEXT_SPEED = 0.5;
bb({mouth:"shut"});
```

b: ...

`bb({mouth:"smile", eyes:"smile"});`

b: Lass uns das retweeten!

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "harm");
```

(...2500)

`_.badnews=true`

```
music('battle', {volume:0.5});
hong({mouth:"anger", eyes:"anger"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: Okay ich werd's retweeten, aber bitte sei still!

`hong({mouth:"neutral", eyes:"annoyed"});`

h: ^Scheiß^ drauf, lass uns Snapchat anschauen.

(#act1e)


# act1d_subtweet

`bb({eyes:"fear"});`

b: Das ist ein Subtweet! Ein heimtückischer, feiger Subtweet!

`hong({eyes:"annoyed"});`

h: Ist es wahrscheinlich nicht?

`bb({eyes:"narrow", mouth:"small"});`

b: aber was wenn sie alle hinter unserem Rücken über uns reden

h: Machen sie ni---

`bb({body:"fear", eyes:"fear", mouth:"normal"});`

b: HINTER UNSEREM RÜCKEN

`hong({eyes:"sad", mouth:"sad"});`

h: Ich denk n--

`bb({eyes:"narrow", mouth:"small"});`

b: aber *was, wenn*

h: S--

`bb({eyes:"narrow_eyebrow"});`

b: *was, wenn*

```
Game.OVERRIDE_TEXT_SPEED = 0.5;
hong({mouth:"shut"});
```

h: ...

(...1000)

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "alone");
```

(...2500)

`_.subtweet=true`

```
hong({mouth:"anger", eyes:"annoyed"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
```

h: o-KAY, probier'n wir Snapchat.

(#act1e)

# act1d_milk

`hong({mouth:"smile", eyes:"neutral"});`

h: Ha, ja das ist niedlich. Jemand hat's gerade retweetet, ich de--

```
hong({mouth:"shock", eyes:"shock"});
bb({body:"scream"});
Game.OVERRIDE_TEXT_SPEED = 1.8;
```

b: KATZEN KÖNNEN KEINE MILCH VERDAUEN UND WIR GRAUSAMEN MENSCHEN VERGNÜGEN UNS AN TIERQUÄLEREI

```
bb({body:"normal", mouth:"normal", eyes:"fear"});
attack("18p", "bad");
```

(...2500)


`_.catmilk=true`

```
hong({mouth:"anger", eyes:"annoyed"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
```

h: o-KAY, probier'n wir Snapchat.

(#act1e)

# act1e

`hong({mouth:"neutral", eyes:"neutral"});`

h: Ha, Fotos von gestern Abend. Also *so* sind diese wöchentlichen Parties.

{{if _.partyinvite=="yes"}} (#act1e_said_yes) {{/if}}

{{if _.partyinvite=="no"}} (#act1e_said_no) {{/if}}

{{if _.partyinvite=="ignore"}} (#act1e_said_ignore) {{/if}}

# act1e_said_yes

`hong({mouth:"sad", eyes:"annoyed"});`

h. Uff, sieht so vollgestopft aus, da wär' mir total unwohl.

h: Vielleicht hätt' ich lieber nicht zusagen sollen?

```
hong({mouth:"neutral", eyes:"neutral"});
bb({mouth:"normal", eyes:"normal"});
```

[Sollen wir doch absagen? Wie ein Arsch?!](#act1e_yes_dontchange)

[Sag lieber ab! Es ist viel zu voll!](#act1e_yes_changetono)

{{if _.subtweet}}
[Jo, der hat uns echt ge-subtweetet.](#act1e_ignore_subtweet)
{{/if}}

{{if _.badnews}}
[Warte, wir haben das retweetet, ohne es zu fact-checken.](#act1e_ignore_factcheck)
{{/if}}

{{if (!_.subtweet && !_.badnews)}}
[Weißt du, dass du echt 'ne schlechte Körperhaltung hast?](#act1e_ignore_posture)
{{/if}}

# act1e_yes_dontchange

```
bb({eyes:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Sie hat darauf gezählt, dass wir kommen und jetzt verraten wir ihr Vertrauen? Willst du alleine sterben?!

{{if _.fifteencigs}}
b: FÜNFZEHN. ZIGARETTEN.
{{/if}}

{{if _.whalepoop}}
b: WAL. KACKE.
{{/if}}

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "alone");
```

(...2500)

```
hong({mouth:"anger", eyes:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: Halt die Schnauze, ich sag nicht mehr ab!

(#act1f)

# act1e_yes_changetono

```
bb({eyes:"fear"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Hast du nie was von 'ner Massenpanik gehört?

```
bb({body:"fear", mouth:"small", eyes:"narrow"});
hong({eyes:"sad", mouth:"sad"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: 2003 hat ein Nachtclub in Rhode Island gebrannt und wegen der Panik ham' die Leute die Ausgänge verstopft und 100 Leute sind tödlich verbrannt-

```
bb({body:"normal", mouth:"normal", eyes:"fear"});
hong({mouth:"shock"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: WILLST DU, DASS UNS DAS PASSIERT-

```
bb({body:"scream"});
Game.OVERRIDE_TEXT_SPEED = 2.5;
```

b: SAG AB SAG AB SAG AB SAG AB SAG AB SAG AB SAG AB SAG AB SAG A-


```
bb({body:"normal", eyes:"fear", mouth:"normal"});
hong({mouth:"shock", eyes:"shock"});
attack("18p", "harm");
```

(...2500)

```
hong({eyes:"anger", mouth:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: Halt' die Schnauze, ich sag' ja schon ab! Gott!

(#act1f)

# act1e_said_no

`hong({mouth:"sad", eyes:"sad"});`

h: Hm... das sieht echt spaßig aus.

h: Vielleicht hätte ich die Einladung nicht ausschlagen sollen?

`bb({mouth:"normal", eyes:"normal"});`

[Sollen wir doch zusagen? Wie ein Arsch?!](#act1e_no_dontchange)

[Sag doch zu! Stirb nicht allein!](#act1e_no_changetoyes)

{{if _.subtweet}}
[Jo, der hat uns definitiv ge-subtweetet.](#act1e_ignore_subtweet)
{{/if}}

{{if _.badnews}}
[Warte, wir haben das retweetet, ohne es zu fact-checken.](#act1e_ignore_factcheck)
{{/if}}

{{if (!_.subtweet && !_.badnews)}}
[Weißt du, dass du echt 'ne schlechte Körperhaltung hast?](#act1e_ignore_posture)
{{/if}}

# act1e_no_dontchange

`bb({eyes:"anger"})`

b: Jeder hat auf uns gezählt!

b: ...dass wir sie alleine lassen und sie eine coole Party ohne ein wiederwärtigen {{if _.whitebread}}Weißbrot-kauenden {{/if}} Creep wie uns ha--


```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "bad");
```

(...2500)

```
bb({body:"normal", eyes:"uncertain", mouth:"normal"});
hong({mouth:"anger", eyes:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: Halt die Schauze, ich bleib bei 'nem nein!

(#act1f)

# act1e_no_changetoyes

```
bb({body:"fear", eyes:"fear", mouth:"normal"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Chronische Einsamkeit erhöht den Kortison-Spiegel sowie das Risiko für Herz-Kreislauf Erkrankungen und Schlaganfälle!

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "harm");
```

(...2500)

{{if _.fifteencigs}}
b: FÜNFZEHN. ZIGARETTEN.
{{/if}}

```
bb({body:"normal", eyes:"normal", mouth:"normal"});
hong({mouth:"anger", eyes:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: Halt die Schnauze, ich sage ja schon zu! Gott!

(#act1f)

# act1e_ignore_subtweet

```
bb({eyes:"fear", mouth:"small"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: All unsere zweifelhaften Tweets fallen auf uns zurück!

```
bb({body:"fear", eyes:"fear", mouth:"normal"});
Game.OVERRIDE_TEXT_SPEED = 1.7;
```

b: Dafür prangern sie uns an und zieh'n uns mit einem Seil zu Pferde die Daten-Autobahn runter!

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "alone");
```

(...2500)

```
bb({body:"normal", eyes:"normal", mouth:"normal"});
hong({mouth:"anger", eyes:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: Warum bist du so?!

(#act1f)

# act1e_ignore_factcheck

```
bb({eyes:"fear"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Wir verbreiten Unwahrheiten! Wir zerstören das Vertrauen in die freie Presse!

```
bb({body:"scream"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Wir sind der Grund weshalb Faschismus aus den Ruinen der Demokratie aufsteigt!

```
bb({body:"normal", eyes:"anger"});
hong({mouth:"shock", eyes:"shock"});
attack("18p", "bad");
```

(...2500)

```
hong({mouth:"anger", eyes:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
_.factcheck = true;
```

h: Warum bist du so?!

(#act1f)

# act1e_ignore_posture

```
bb({eyes:"fear"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Willst du eine Breze als Rückgrat haben?! Hör auf dich so über den Bildschirm zu buckeln!

```
bb({body:"meta"});
```

b: Das heißt du auch.

```
bb({body:"normal", mouth:"normal"});
hong({mouth:"shock", eyes:"shock"});
attack("18p", "harm");
```

(...2500)

```
bb({body:"normal", eyes:"normal", mouth:"normal"});
hong({mouth:"anger", eyes:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: Warum bist du so?!

(#act1f)

# act1e_said_ignore

`hong({mouth:"sad", eyes:"sad"});`

h: Hm... das sieht echt spaßig aus.

h: Vielleicht hätte ich die Einladung doch nicht ignorieren sollen?

`bb({mouth:"normal", eyes:"normal"});`

[Bleib dabei, wir sind Spaßbremsen.](#act1e_ignore_continue)

[Wobei, sag ja.](#act1e_ignore_changetoyes)

[Wobei, sag nein.](#act1e_ignore_changetono)

# act1e_ignore_continue

`hong({eyes:"annoyed"});`

h: Es ist irgendwie unhöflich sie zu ignorieren, oder?

`bb({eyes:"normal_right"});`

b: Naja andere Leute ignorieren *uns* immer, also

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "alone");
```

(...2500)

`bb({eyes:"normal"});`

b: also lass uns sagen, wir sind quitt.

(#act1f)

# act1e_ignore_changetoyes

`hong({eyes:"surprise", mouth:"smile"});`

h: Du... lässt mich Spaß haben?

b: Naja, ich mein, Einsamkeit *kann* uns umbringen.

`hong({eyes:"neutral", mouth:"neutral"});`

(#act1e_no_changetoyes)

# act1e_ignore_changetono

`bb({eyes:"narrow"});`

b: Es ist zu voll. Menschenmengen sind gefährlich.

(#act1e_yes_changetono)


# act1f

```
hong({mouth:"neutral", eyes:"neutral"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
```

h: Wie auch immer. Neue Tinder-Notification.

`bb({eyes:"uncertain"})`

b: Was, diese Aufreißer-App?

`hong({eyes:"annoyed"})`

h: Das ist keine Aufreißer-App, nur eine neue Art neue Leute kennenzu--

`bb({eyes:"narrow"})`

b: Das ist 'ne Aufreißer-App.

```
hong({eyes:"surprise", mouth:"smile"});
bb({eyes:"normal"});
```

h: Oh, ich hab' ein Match! Die sieht Süß aus!

```
bb({eyes:"narrow_eyebrow"});
hong({eyes:"sad", mouth:"anger"})
```

h: Bitte ruinier das nicht für m--

```
bb({body:"panic"});
Game.OVERRIDE_TEXT_SPEED = 2.0;
```

b: GEFAHR GEFAHR GEFAHR GEFAHR GEFAHR GEFAHR

`bb({body:"fear", eyes:"fear", mouth:"normal"})`

[Wir werden von anderen *ausgenutzt*.](#act1f_used_by_others)

[Wir *nutzen* andere Leute *aus*.](#act1f_using_others)

[DEIN MATCH IST EINE SERIENMÖRDERIN](#act1f_killer)

# act1f_used_by_others

`bb({body:"point_crotch", eyes:"normal", mouth:"normal"})`

b: Wahllose One-Night-Stands füllen vielleicht das Loch da unten,

b: aber sie füllen garantiert nie das Loch...

`bb({body:"point_heart", eyes:"pretty", mouth:"small"})`

b: *hier*.

(...1000)

```
bb({body:"normal", mouth:"normal", eyes:"fear"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Der Punkt ist, WIR WERDEN ALLEINE STERBEN

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "alone");
```

(...2500)

`_.hookuphole=true`

(#act1g)

# act1f_using_others

`bb({eyes:"narrow", mouth:"small"})`

b: Denkst du, die Genitalien anderer Leute sind Pokémon, die wir sammeln müssen?

```
bb({body:"sing", eyes:"pretty", mouth:"shut"});
music("pokemon");
Game.clearText();
Game.FORCE_CANT_SKIP = true;
```

```
Game.FORCE_TEXT_DURATION = 1000;
Game.FORCE_NO_VOICE = true;
```

b: ♫ (Pokémon Titelsong)-

(...5600)

```
bb({mouth:"normal"});
Game.FORCE_TEXT_DURATION = 2400;
```

b: ♫ Ich will den Allergrößten ham'-

(...500)

```
bb({eyes:"narrow", mouth:"small"});
Game.FORCE_TEXT_DURATION = 2100;
```

b: ♫ Wie keiner je vor mir-

(...1500)

```
bb({eyes:"pretty"});
Game.FORCE_TEXT_DURATION = 2300;
```

b: ♫ Ganz allein turn' ich sie an-

(...500)

```
bb({eyes:"fear", mouth:"normal"});
Game.FORCE_TEXT_DURATION = 2000;
```

b: ♫ ich bin ein wilder Stier!-

(...1000)

```
bb({eyes:"smile", mouth:"smile"});
Game.FORCE_TEXT_DURATION = 1000;
```

b: ♫ ^FICK^-MARATHON! Komm leg sie-

```
Game.FORCE_CANT_SKIP = false;
Game.clearText();
music(false);
bb({body:"normal", mouth:"normal", eyes:"normal"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Der Punkt ist, wir sind ein manipulatives Ekel.

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "bad");
```

(...2500)

`_.pokemon=true`

(#act1g)

# act1f_killer

`Game.OVERRIDE_TEXT_SPEED = 1.5;`

{{if _.whitebread}}
b: Sie wird dich in einem Brunnen gefangen halten und dich mit Weißbrot mästen, damit sie deine Haut wie einen Anzug tragen kann!
{{/if}}

{{if _.parasite}}
b: Sie wird dich mit einer Eieruhr niederknüppeln und sagen "DU HÄTTEST PRODUKTIVER SEIN MÜSSEN, DU PARASIT"
{{/if}}

{{if !_.whitebread && !_.parasite}}
b: Sie wird dein Fleisch zu blutigem Konfetti zerreißen, deine Eingeweide zu Luftschlagen machen und dein Blut in einen Punsch mixen!
{{/if}}

{{if !_.whitebread && !_.parasite}}
b: Was ist DAS für eine Party Einladung?!
{{/if}}

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "harm");
```

(...2500)

`_.serialkiller=true`

(#act1g)

# act1g

```
bb({body:"normal", mouth:"normal", eyes:"look"});
hong({body:"2_tired"});
Game.OVERRIDE_TEXT_SPEED = 0.5;
music(false);
```

h: ...

(...500)

h: Ich bin so müde von diesem Spiel.

(...700)

`Game.OVERRIDE_TEXT_SPEED = 1.5;`

h:
{{if _.fifteencigs}}"Einsamkeit wird uns umbringen"... {{/if}}
{{if _.parasite}}"wir sind ein Gesellschafts-Parasit"... {{/if}}
{{if _.whitebread}}"iss das nicht, das bringt uns um"... {{/if}}
{{if _.subtweet}}"sie reden hinter unserem Rücken"... {{/if}}
{{if _.badnews}}"die Welt geht unter"... {{/if}}
{{if _.hookuphole}}"wir sterben alleine"... {{/if}}
{{if _.serialkiller}}"sie ist eine Serienmörderin"... {{/if}}
{{if _.catmilk}}"Katzen können keine Milch verdauen"... {{/if}}
{{if _.pokemon}}eine ^beschissene^ Song-Parodie... {{/if}}

h: Ich will einfach nur mein Leben leben.

h: Ich will einfach nur frei sein, von all diesem... Schmerz.

`bb({eyes:"look_sad"});`

b: Hey... Mensch..

`Game.OVERRIDE_TEXT_SPEED = 0.5;`

b: Alles wird gut.

(...600)

`bb({body:"point_heart", eyes:"look_sad_smile", mouth:"smile"});`

b: Als dein treuer Wachwolf werde ich immer nach Gefahr Ausschau halten und mein Bestes tun, dich zu beschützen.

`bb({body:"normal", eyes:"look_sad", mouth:"smile"});`

b: Ich versprech's dir.

(...600)

```
bb({body:"normal", eyes:"normal", mouth:"normal"});
hong({body:"phone1", eyes:"neutral", mouth:"neutral"});
```

h: Letzte App. Instagram. Was gibt's hier?

`hong({eyes:"sad"});`

h: Es sind... mehr Party-Bilder.

`hong({mouth:"sad"});`

h: Jeder sieht so glücklich aus. Sorgenfrei. Unbeschwert.

`hong({mouth:"anger"});`

h: Gott, warum kann ich nicht so wie die sein? Warum kann ich nicht einfach *normal* sein?

`bb({eyes:"normal_right"});`

b: Apropos, wegen der Party dieses Wochenende. Das ist meine ENDGÜLTIGE Entscheidung:

`bb({eyes:"normal"});`

[Wir sollten hingehen.](#act1g_go) `Game.OVERRIDE_CHOICE_LINE=true`

[Wir sollten nicht hingehen.](#act1g_dont) `Game.OVERRIDE_CHOICE_LINE=true`

# act1g_go

`_.act1g = "go"`

(#act1h)

# act1g_dont

`_.act1g = "dont"`

(#act1h)

# act1h

b: Wir sollt--

```
bb({eyes:"wat", mouth:"small"});
hong({body:"2_fuck"});
```

h: *^FICK^.*

`hong({body:"2_you"});`

h: DICH.

(...500)

b: w-

(...1500)

`bb({eyes:"wat_2"});`

b: wa-?

`hong({body:"phone1", eyes:"anger", mouth:"anger"});`

h: Ich werde die Einladung zu der Party ANNEHMEN,

{{if _.act1g=="go"}}
h: NICHT weil du willst, dass ich gehe, sondern weil *ICH* es will.
{{/if}}

{{if _.act1g=="dont"}}
h: Gerade WEIL du nicht willst, dass ich hingehe.
{{/if}}

```
hong({body:"putaway"});
sfx("rustle");
```

h: Du kannst mich NICHT kontrollieren.

```
sfx("rustle2");
hong({body:"0_sammich", eyes:"0_annoyed", mouth:"0_neutral"});
```

h: Also, entschuldige mich, während ich ich dieses schmackhafte Sandwich in ^gottverdammter^ Ruhe genieße.

`hong({body:"2_sammich_eat"});`

(...601)

```
sfx("sandwich");
hong({body:"2_sammich_eaten", eyes:"0_lookaway", mouth:"0_chew1"})
```

(...601)

```
bb({body:"normal", eyes:"uncertain", mouth:"shut"});
Game.OVERRIDE_TEXT_SPEED = 0.5;
```

b: ...

```
bb({eyes:"normal_right"});
Game.OVERRIDE_TEXT_SPEED = 1;
```

b: ...

```
bb({eyes:"fear"});
Game.OVERRIDE_TEXT_SPEED = 4;
```

b: ..................

(...500)

`bb({mouth:"normal"});`

[AHHHH WIR WERDEN STERBEN](#act1h_death) `Game.OVERRIDE_CHOICE_LINE = true;`

[AHHHH JEDER HASST UNS](#act1h_loneliness) `Game.OVERRIDE_CHOICE_LINE = true;`

[AHHHH WIR SIND SCHRECKLICHE MENSCHEN](#act1h_worthless) `Game.OVERRIDE_CHOICE_LINE = true;`

# act1h_death

```
bb({body:"fear"});
Game.OVERRIDE_TEXT_SPEED = 3;
```

b: AHHHH WIR WERDEN STERBEN AAAAAAHHHHHHH

```
hong({body:"3_defeated1"});
attack("100p", "harm");
```

(...2500)

(#act1i)

# act1h_loneliness

```
bb({body:"fear"});
Game.OVERRIDE_TEXT_SPEED = 3;
```

b: AHHHH JEDER HASST UNS AAAAAAHHHHHHH

```
hong({body:"3_defeated1"});
attack("100p", "alone");
```

(...2500)

(#act1i)

# act1h_worthless

```
bb({body:"fear"});
Game.OVERRIDE_TEXT_SPEED = 3;
```

b: AHHHH WIR SIND SCHRECKLICHE MENSCHEN AAAAAAHHHHHHH

```
hong({body:"3_defeated1"});
attack("100p", "bad");
```

(...2500)

(#act1i)

# act1i

```
bb({mouth:"smile_lock", eyes:"smile", body:"normal"});
music('battle', {volume:0.5});
```

n: GLÜCKWUNSCH

(...500)

n: DU HAST ALLE BEDÜRFNISSE DEINES MENSCHEN ERFOLGREICH BESCHÜTZT

n: SIEH DOCH WIE DANKBAR ER IST!

(...500)

n: JETZT, DA SEINE ENERGIE VERBRAUCHT IST, KANNST DU SEIN HANDELN DIREKT KONTROLLIEREN


`bb({mouth:"smile", eyes:"normal"});`

n: WÄHL DEINEN LETZTEN ZUG

`bb({mouth:"small_lock", eyes:"fear"});`

n: *MACH IHN FERTIG*

[{KÄMPFE: Bestraf dein nerviges Handy!}](#act1i_phone) `Game.OVERRIDE_CHOICE_LINE=true`

[{FLIEHE: Roll dich zusammen und fang an zu heulen!}](#act1i_cry) `Game.OVERRIDE_CHOICE_LINE=true`

# act1i_phone

`bb({mouth:"normal", eyes:"narrow"})`

b: Dein Handy hat bei dir eine Panikattacke ausgelöst!

`bb({eyes:"anger"})`

b: Zuckerberg und Co missbrauchen deine geistige Gesundheit als Risikokapital!

```
bb({body:"fear", eyes:"fear"});
hong({body:"3_defeated2"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Bestraf' dein Handy! Mach's kaputt! Zerstör' es!

```
Game.OVERRIDE_TEXT_SPEED = 2.5;
bb({body:"flail"});
hong({body:"3_defeated3"});
_.act1_ending = "fight";
```

b: BRICH'S KAPUTT BRICH'S KAPUTT BRICH'S KAPUTT BRICH'S KAPUTT BRICH'S KAPUTT BRICH'S KAPUTT BRICH'S KAPUTT BRICH'S KAPUTT BRICH'S KA--

(#act1j)

# act1i_cry

`bb({eyes:"fear", mouth:"normal"})`

b: Die ganze Welt ist voller Gefahren!

```
bb({body:"fear"});
hong({body:"3_defeated2"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Mach es wie das Gürteltier! Kugel dich zur Selbstverteidigung ein!

```
Game.OVERRIDE_TEXT_SPEED = 2.5;
bb({body:"flail"});
hong({body:"3_defeated3"});
_.act1_ending = "flight";
```

b: ROLL DICH ZUSAMMEN UND HEUL ROLL DICH ZUSAMMEN UND HEUL ROLL DICH ZUSAMMEN UND HEUL ROL--

(#act1j)

# act1j

`SceneSetup.act1_outro()`
