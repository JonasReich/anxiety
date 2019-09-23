# act2

`SceneSetup.act2();`

{{if _.badnews && !_.factcheck}}
(#act2-preamble-news1)
{{/if}}

{{if _.badnews && _.factcheck}}
(#act2-preamble-news2)
{{/if}}

{{if _.catmilk}}
(#act2-preamble-cat)
{{/if}}

(#act2-preamble-tinder)


# act2-preamble-news1

```
publish("act2",["dee",3]);
```

s: Aber hast du diesen "Artikel" über dieses schreckliche Ereignis irgendwo *gesehen*?

```
publish("act2",["dee",2]);
publish("act2",["party_hong","next"]);
```

h2: H-hi...

```
publish("act2",["party_hunter",1]);
publish("act2",["party_hong","next"]);
publish("act2",["dum",3]);
```

a: Gott ich hasse die Nachrichten. Ist doch alles Sensationsmacherei und Clickbait.

```
publish("act2",["dum",2]);
publish("act2",["party_hong","next"]);
```

h2: N... nette Party...

```
publish("act2",["party_hong","next"]);
publish("act2",["party_hunter",0]);
publish("act2",["dee",1]);
```

s: Schon, aber die folgen ja auch nur Anreizeh von außen. Das *wahre* Problem sind Leute, die das anklicken.

```
publish("act2",["dee",3]);
```

s: Wer würde so eine schreckliche Nachricht retweeten und dafür sorgen, dass sich alle seine Freunde schlecht fühlen?

```
publish("act2",["party_hunter",1]);
publish("act2",["dee",2]);
publish("act2",["dum",3]);
```

a: Boah, ist wirklich so.

(#act2-preamble-end)


# act2-preamble-news2

```
publish("act2",["dee",3]);
```

s: Aber hast du *gesehen*, wie dieser "Nachrichtenbericht" viral gegangen ist?

```
publish("act2",["dee",2]);
publish("act2",["party_hong","next"]);
```

h2: H-hi...

```
publish("act2",["party_hunter",1]);
publish("act2",["party_hong","next"]);
publish("act2",["dum",3]);
```

a: Ja, was für ein Fake. Wer würde da drauf reinfallen und das auch noch retweeten?

```
publish("act2",["dum",2]);
publish("act2",["party_hong","next"]);
```

h2: N... nette Party...

```
publish("act2",["party_hong","next"]);
publish("act2",["party_hunter",0]);
publish("act2",["dee",3]);
```

s: Ernsthaft Alter. Ich mein - hallo - mal zu googlen, ob da was dran ist, kann ja wohl nicht schwer sein.

```
publish("act2",["party_hunter",1]);
publish("act2",["dee",2]);
publish("act2",["dum",3]);
```

a: Boah, ist wirklich so.

(#act2-preamble-end)


# act2-preamble-cat

```
publish("act2",["dee",3]);
```

s: Wie schon gesagt, die Meme-Industrie nutzt Katzen nur aus.

```
publish("act2",["dee",2]);
publish("act2",["party_hong","next"]);
```

h2: H-hi...

```
publish("act2",["party_hunter",1]);
publish("act2",["party_hong","next"]);
publish("act2",["dum",1]);
```

a: Willst du diese Behauptung weiter ausführen?

```
publish("act2",["dum",0]);
publish("act2",["party_hong","next"]);
```

h2: n... nette Party...

```
publish("act2",["party_hong","next"]);
publish("act2",["party_hunter",0]);
publish("act2",["dee",1]);
```

s: Also, ich hab gestern 'n Retweet gesehen, ein GIF von 'ner Katze, die Milch trinkt.

```
publish("act2",["dee",3]);
```

s: Und Katzen können den ^Scheiß^ nicht verdauen! Wer würde solche *Tierquälerei* retweeten?

```
publish("act2",["party_hunter",1]);
publish("act2",["dee",2]);
publish("act2",["dum",3]);
```

a: Boah, ist echt so.

(#act2-preamble-end)


# act2-preamble-tinder

```
publish("act2",["dee",1]);
```

s: Also naja, er hat jedenfalls nie geantwortet!

```
publish("act2",["dee",0]);
publish("act2",["party_hong","next"]);
```

h2: H-hi...

```
publish("act2",["party_hunter",1]);
publish("act2",["party_hong","next"]);
publish("act2",["dum",1]);
```

a: Und das, obwohl ihr euch auf Tinder gegenseitig gematcht habt?

```
publish("act2",["dum",0]);
publish("act2",["party_hong","next"]);
```

h2: n... nette Party...

```
publish("act2",["party_hong","next"]);
```

{{if _.serialkiller}}
(#act2-preamble-serialkiller)
{{/if}}

{{if _.hookuphole}}
(#act2-preamble-hookuphole)
{{/if}}

{{if _.pokemon}}
(#act2-preamble-pokemon)
{{/if}}

# act2-preamble-serialkiller

```
publish("act2",["party_hunter",0]);
publish("act2",["dee",3]);
```

s: Ja, ich weiß auch nicht! Was, denkt der sich etwa, dass ich 'n *Serienmörder* bin, oder was? Sowas von paranoid.

```
publish("act2",["party_hunter",1]);
publish("act2",["dee",2]);
publish("act2",["dum",3]);
```

a: Boah, ist echt so.

(#act2-preamble-end)


# act2-preamble-hookuphole

```
publish("act2",["party_hunter",0]);
publish("act2",["dee",3]);
```

s: Ja, ich weiß auch nicht! Vielleicht denkt er bei ner flotten Nummer lernt er niemanden kennen?

s: Der soll mal aufhören so prüde zu sein! Offener im Kopf und im Bett!

```
publish("act2",["party_hunter",1]);
publish("act2",["dee",2]);
publish("act2",["dum",3]);
```

a: Boah, ist echt so.

(#act2-preamble-end)


# act2-preamble-pokemon

```
publish("act2",["party_hunter",0]);
publish("act2",["dee",3]);
```

s: Ja, ich weiß auch nicht! Er war zwar nicht so scharf, aber's wär' schon ein guter Fang gewesen!

```
publish("act2",["party_hunter",1]);
publish("act2",["dee",2]);
publish("act2",["dum",3]);
```

a: Komm' und schnapp' sie dir!™

(#act2-preamble-end)


# act2-preamble-end

```
Game.clearText();
publish("act2-out-1");
music(null, {fade:1});
```

(...3000)

```
music('battle', {volume:0.5});
publish("hp_show");
bb({body:"normal", mouth:"normal", eyes:"normal"});
```

n: ROUND TWO: *FIGHT!*
n: ZWEITE RUNDE: *UND LOS!*

[Oh Gott, sie hassen uns alle!](#act2a_social)

[Hast du die Rothaarige *angegafft?*](#act2a_perv)

[Hey, lass uns über den Sinn des Lebens reden.](#act2a_meaning)

# act2a_social

`bb({eyes:"sad"})`

b: Wir ziehen die Stimmung der ganzen Party runter, wenn wir wie'n nasser Sack in der Ecke rumhängen!

`bb({eyes:"shock", body:"two_up"})`

b: Wir sind so ein Stimmungskiller! Vorsätzliche Stimmungs-Mörder!

`bb({eyes:"normal", body:"normal"})`

b: Mensch, wir müssen *jetzt* verschwinden, bevor--

```
_.a2_first_danger = 'social';
_.a2_attack_1 = "alone";
```

(#act2b)

# act2a_perv

`bb({eyes:"suspect"})`

b: Die ist viel attraktiver, als wir - was heißt, wenn wir sie bloß *ansehen*, dann--

`bb({eyes:"shock", body:"two_up"})`

b: SIND WIR WIEDERLICH

`bb({body:"normal"})`

b: Wir sind so wiederliche, böse, schlechte, schreckliche, perv--

```
_.a2_first_danger = 'perv';
_.a2_attack_1 = "bad";
```

(#act2b)

# act2a_meaning

`bb({body:"one_up", eyes:"normal_r"})`

b: Am Ende des Tages - können wir überhaupt irgendwas machen, das ne Rolle spielt?

`bb({body:"normal", eyes:"sad"})`

b: Irgendwas zur Menscheit beitragen? Alle großen Werke vergehen wie in Ozymandias. Liebe? Der Tod trennt einen immer.

`bb({eyes:"sad_r"})`

b: Und es gibt so viel Tod! *Wir* werden sterben. *Alle, die wir lieben* werden sterben.

`bb({eyes:"shock", body:"two_up"})`

b: Zum Teufle, der zweite Satz der Thermodynamik besagt, dass sogar unser *Universum* sterben wird!

`bb({eyes:"suspect", body:"normal"})`

b: Oh, "der Tod macht das Leben umso schöner"? Das ist wie zu sagen, dass Sklaverei gut ist, weil wir dann unsere Freiheit mehr wertschätzen!

`bb({body:"one_up"})`

b: Oh, "du musst deine eigene Bedeutung finden"? Das ist doch genau, was Verschwörungstheoretiker machen!

`bb({eyes:"shock", body:"two_up"})`

b: Das Leben hat keine Bedeutung, genauso wie der Tod. Selbst *Bedeutung* hat keine Bedeutung! Was soll eine sterbliche Seele--

```
_.a2_first_danger = 'meaning';
_.a2_attack_1 = "bad";
```

(#act2b)

# act2b

`bb({eyes:"normal", mouth:"normal", body:"normal", MOUTH_LOCK:true})`

b: ...

`bb({eyes:"suspect"})`

b: Öhm... kannst du mich hören, Mensch?

`bb({eyes:"normal", MOUTH_LOCK:true})`

b: ...

`bb({eyes:"shock", mouth:"small_talk", body:"chest", MOUTH_LOCK:true})`

b: *NACH LUFT SCHNAPP*

`bb({mouth:"small_talk"})`

b: ICH MUSS DICH WARNEN!...

[Die soziale Gefahr *nimmt zu*!](#act2b_louder)

{{if _.a2_first_danger=="social"}}
[Eine *andere* soziale Gefahr!](#act2b_different_social)
{{/if}}

{{if _.a2_first_danger=="perv" || _.a2_first_danger=="meaning"}}
[Eine *andere* moralische Gefahr!](#act2b_different_moral)
{{/if}}

[Du ignorierst die Gefahr! Das ist gefährlich!](#act2b_ignore)

# act2b_louder

`_.a2_first_choice = "louder"`

{{if _.a2_first_danger=="social"}}
(#act2b_louder_social)
{{/if}}

{{if _.a2_first_danger=="perv"}}
(#act2b_louder_perv)
{{/if}}

{{if _.a2_first_danger=="meaning"}}
(#act2b_louder_meaning)
{{/if}}

# act2b_louder_social

`bb({eyes:"shock", body:"two_up", mouth:"normal"})`

b: EMOTIONEN STECKEN AN! ALSO, WENN DU SIE NICHT RAUSLÄSST, WIRST ALLE MIT DEINER KRANKHEIT ANSTECKEN!

b: Du wirst eine tödliche Welle von NASSER SACK SYNDROM verbreitden

`bb({eyes:"suspect", body:"normal", mouth:"normal"})`

b: Wir müssen hier raus und für immer in Quarantäne in nem kleinen Raum mit Netflix und Lieferessen!

```
_.a2_second_danger = 'netflix';
_.a2_attack_2 = "alone";
_.a2_hoodie_callback = "eine Quarantäne";
```

(#act2c)

# act2b_louder_perv

`bb({eyes:"suspect", body:"two_up", mouth:"normal"})`

b: SEI KEIN EKEL. DAS IST GEGEN DAS GESETZ!

`bb({eyes:"judge", body:"judge_1", mouth:"normal"})`

(...201)

```
bb({body:"judge_2"}, 0);
sfx("gravel");
```

(...168)

`bb({body:"judge_1"}, 0)`

(...168)

`bb({body:"judge_2"}, 0)`

(...168)

`bb({body:"judge_1"}, 0)`

(...501)

b: Ekel Gesetz, Abschnitt 64,5: (1) Jede Person, die (a) diese kräftigen Schultern, oder (b) diesen Knackarsch auscheckt, (2) ist absofort

`bb({eyes:"shock", body:"two_up", mouth:"normal"})`

b: "EIN FETTER, EKELHAFTER, DRECKIGER PERVERSLING"

```
_.a2_second_danger = 'law';
_.a2_attack_2 = "bad";
_.a2_hoodie_callback = "das Gesetz";
```

(#act2c)

# act2b_louder_meaning

`bb({body:"two_up", mouth:"normal", eyes:"shock"})`

b: Also eigentlich kannst du selbst wenn du einen noblen Zweck für dein Leben findest *immer noch* alles ver^kacken^!

`bb({body:"normal", mouth:"normal", eyes:"normal"})`

b: Alfred Nobel wollte Weltfrieden und Kulturverständigung - also hat er das Reisen einfacher gemacht.

`bb({eyes:"normal_r"})`

b: Weil er schnell und günstig Zugtunnel bauen wollte, hat er ein neues Material namens "Dynamit" erfunden...

`bb({body:"one_up", eyes:"normal"})`

b: was im ersten Weltkrieg MILLIONEN VON MENSCHEN UMGEBRACHT HAT

`bb({body:"two_up", eyes:"shock"})`

b: DAS IST DER SCHMETTERLINGS-EFFEKT, MENSCH! WIE VIELE LEUTE BRINGST DU GERADE AUSVERSEHEN UM

```
_.a2_second_danger = 'butterfly';
_.a2_attack_2 = "bad";
_.a2_hoodie_callback = "den ersten Weltkrieg";
```

(#act2c)

# act2b_different_social

`_.a2_first_choice = "different"`

`bb({eyes:"normal_r", body:"point", mouth:"normal"})`

b: Naja, weißt du was eigentlich noch schlimmer wär, als dass dich niemand mag? Wenn dich *jeder* mag.

`bb({body:"one_up", eyes:"suspect", mouth:"normal"})`

b: Das hieße nämlich, einer von *diesen* hedonistischen Partytieren zu werden.

`bb({body:"normal", mouth:"small"})`

b: Ein oberflächliches Leben mit oberflächlichen Freunden, die dich auch nur oberflächlich kennen!

`bb({body:"two_up", eyes:"shock", mouth:"normal"})`

b: Mensch, wir müssen von diesen Vergnügungs-Zombies abhauen, bevor sie uns verwandeln!

```
_.a2_second_danger = 'zombies';
_.a2_attack_2 = "alone";
_.a2_hoodie_callback = "Zombies";
```

(#act2c)

# act2b_different_moral

`_.a2_first_choice = "different"`

`bb({body:"two_up", eyes:"shock", mouth:"normal"})`

b: Menschen sterben in Hungersnöten und Genoziden *jetzt gerade* und wir machen Party!

`bb({body:"point", eyes:"closed", mouth:"small"})`

b: Wie eine Weise Frau einst gesagt hat: "das Einzige was für den Triumph des Bösen nötig ist, ist dass die Guten nichts machen".

`bb({body:"two_up", eyes:"shock", mouth:"normal"})`

b: WIR MACHEN NICHTS.

`bb({mouth:"small"})`

b: WENN WIR PARTY MACHEN, HELFEN WIR *HITLER*.

```
_.a2_second_danger = 'hitler';
_.a2_attack_2 = "bad";
_.a2_hoodie_callback = "Hitler";
```

(#act2c)

# act2b_ignore

`_.a2_first_choice = "ignore"`

`bb({body:"normal", mouth:"normal", eyes:"suspect"})`

b: denkst du dass du sicher bist, nur weil du die Batterien aus dem Rauchmelder genommen hast?

`bb({eyes:"suspect_r"})`

b: Du wirst das Gift nicht mal riechen! Du wirst einfach nur schläfrig werden und dann--

`bb({body:"scream_c_1"})`

b: STEEEEEERRRBBBEEEEEEN

```
_.a2_second_danger = 'ignore';
_.a2_attack_2 = "harm";
_.a2_hoodie_callback = "Kohlenstoffmonoxid";
```

(#act2c)

# act2c

```
hong({body:"ignore_sweat"});
bb({eyes:"normal", mouth:"normal", body:"normal", MOUTH_LOCK:true});
```

b: ...

`bb({eyes:"happy", mouth:"smile", body:"chest"})`

b: Oh Gott sei Dank, Mensch, ich glaub du kannst mich wieder hören!

`bb({eyes:"closed", body:"point"})`

b: ICH MUSS DICH WARNEN...

{{if _.a2_first_choice=="louder"}}
[Vor der *gleichen, eskalierenden* Gefahr!](#act2c_louder)
{{/if}}

{{if _.a2_first_choice!="louder"}}
[Vor der *gleichen, eskalierenden* Gefahr!](#act2c_louder)
{{/if}}

{{if _.a2_first_danger=="social"}}
[Vor einer *anderen* sozialen Gefahr!](#act2c_different_social)
{{/if}}

{{if _.a2_first_danger=="perv" || _.a2_first_danger=="meaning"}}
[Vor einer *anderen* moralischen Gefahr!](#act2c_different_moral)
{{/if}}

[Hast du vor dem Trinken den Punsch überprüft?](#act2c_punch)

#act2c_louder

{{if _.a2_second_danger=="netflix"}}
(#act2c_louder_netflix)
{{/if}}

{{if _.a2_second_danger=="law"}}
(#act2c_louder_law)
{{/if}}

{{if _.a2_second_danger=="butterfly"}}
(#act2c_louder_butterfly)
{{/if}}

{{if _.a2_second_danger=="zombies"}}
(#act2c_louder_zombies)
{{/if}}

{{if _.a2_second_danger=="hitler"}}
(#act2c_louder_hitler)
{{/if}}

{{if _.a2_second_danger=="ignore"}}
(#act2c_louder_ignore)
{{/if}}

# act2c_louder_netflix

`bb({body:"normal", mouth:"normal", eyes:"shock"})`

b: Also eigentlich ist eine Netflix/Lieferessen Quarantäne nicht sicher genug! Wir würden immer noch den Lieferjungen anstecken!

`bb({body:"one_up", mouth:"small"})`

b: Wir müssen in den Yukon in Kanada ziehen und uns das Essen per Drohne liefern lassen!

`bb({body:"two_up", mouth:"normal"})`

b: Und dann müssen sie die Drohne sterilisieren, um von unseren FEUCHTER SACK KEIMEN zu reinigen

`_.a2_attack_3 = "alone";`

`_.a2_hoodie_callback = "eine Quarantäne";`

(#act2d)

# act2c_louder_law

`bb({eyes:"judge", body:"judge_1", mouth:"normal"})`

(...201)

```
bb({body:"judge_2"}, 0);
sfx("gravel");
```

(...168)

`bb({body:"judge_1"}, 0)`

(...168)

`bb({body:"judge_2"}, 0)`

(...168)

`bb({body:"judge_1"}, 0)`

(...501)

b: DER DRECKIGE PERVERSLING soll zu 72 Stunden in einem dieser mittelalterlichen Bloßstellungs-Apparaten verurteilt werden

b: außer er *steht* hiemlich auf sowas

`bb({body:"scream_a_1"})`

b: weil er ein FETTER, EKELHAFTER, DRECKIGER PERVERSLING ist

`_.a2_attack_3 = "bad";`

`_.a2_hoodie_callback = "das Gesetz";`

(#act2d)

# act2c_louder_butterfly

`bb({body:"normal", mouth:"small", eyes:"suspect"})`

b: SCHMETTERLINGS EFFEKT! Du benutzt gerade einen nichtkompostierbaren Plastikbecher?

`bb({body:"two_up", mouth:"normal", eyes:"shock"})`

b: ZACK, EIN ERDRUTSCH LÄSST GIFT AUSLAUFEN UND TÖTET EIN KIND

`bb({body:"normal", mouth:"small", eyes:"suspect"})`

B. Du schwitzt und dein Herz schlägt bis zum Hals?

`bb({body:"scream_a_1"})`

b: ZACK, DU TREIBST UNSER GESUNDHEITSYSTEM IN DIE PLEITE UND MILLIONEN STERBEN

`_.a2_attack_3 = "bad";`

`_.a2_hoodie_callback = "den Schmetterlings-Effekt";`

(#act2d)

# act2c_louder_zombies

`bb({body:"normal", mouth:"small", eyes:"angry"})`

b: Die Vergnügungs-Zombies werden auf dich zustolpern während sie vor sich hinmurmeln,

`bb({body:"normal", mouth:"normal", eyes:"shock"})`

b: LIIIIIKES. LIIIIIIIIIIKES.

`bb({body:"scream_a_1"})`

b: Dann werden sie dich BEISSEN und dich in ein HIRNLOSEN IDIOTEN verwandeln!

`_.a2_attack_3 = "bad";`

`_.a2_hoodie_callback = "Zombies";`

(#act2d)

# act2c_louder_hitler

`bb({body:"scream_a_1"})`

b: DIE NAZIS MARSCHIEREN GERADE WIEDER IM STECHSCHRITT DURCH DIE STRASSEN

`bb({body:"one_up", mouth:"smile", eyes:"happy"})`

b: Und sagen sich, *Schön, dass die Gutmenschen mit sowas wie 'Entspannen' und 'Selbstpflege' beschäftigt sind!*

`bb({body:"point", mouth:"smile", eyes:"happy_r"})`

b: *Dann übernehmten wir jetzt mal wieder die Kontrolle!*

`_.a2_attack_3 = "bad";`

`_.a2_hoodie_callback = "Hitler";`

(#act2d)

# act2c_louder_ignore

`bb({body:"normal", mouth:"normal", eyes:"normal_r"})`

b: Wenn ich so drüber nachdenke, *wissen wir überhaupt*, ob dieses Gebäude eine Rauchmelder hat?!

`bb({body:"two_up", mouth:"small", eyes:"normal"})`

b: Was wenn wir *JETZT GERADE* alle vergiftet werden?

`bb({body:"scream_a_1"})`

b: WIR WÜRDEN NICHTMAL MERKEN, DASS WIR TOT SIND. WIR WÜRDEN EINFACH AUFHÖREN ZU EXISTIEREN.
b: FÜR IMMER UND IMMER UND IMMER UND IMM--

`_.a2_attack_3 = "harm";`

`_.a2_hoodie_callback = "Kohlenstoffmonoxid";`

(#act2d)

# act2c_different_social

`bb({body:"normal", mouth:"normal", eyes:"sad"})`

b: Was wenn wir einfach *von Grund auf unfähig* sind, je geliebt zu werden, oder jemanden zu lieben?

`bb({body:"normal", mouth:"small", eyes:"sad_r"})`

b: Was wenn etwas vor langer Zeit nicht reparierbar in uns kaputt gegangen ist?
b: Oder noch schlimmer: Vielleicht was es nie in uns?

`bb({body:"scream_a_1"})`

b: AHH WIR SIND KAPUTT! SO KAPUTT SO KAPUTT SO KAPP--

`_.a2_attack_3 = "alone";`

(#act2d)

# act2c_different_moral

`bb({body:"normal", mouth:"normal", eyes:"normal"})`

b: Was wenn wir einfach *von Grund auf verdorben* sind?

`bb({body:"one_up", eyes:"sad"})`

b: Andere haben vielleicht einen Drang, Gutes zu tun, aber wir machen gute Sachen wenn überhaupt nur aus Scham.

`bb({body:"normal", mouth:"small", eyes:"sad_r"})`

b: Was, wenn es in unserer Natur liegt, anderen wehzutun und wir gar nicht anders *können*, als anderen zur Last zu fallen?

`bb({body:"scream_a_1"})`

b: AHH WIR SIND KAPUTT! SO KAPUTT SO KAPUTT SO KAPP--

`_.a2_attack_3 = "bad";`

(#act2d)

# act2c_punch

`bb({body:"normal", mouth:"normal", eyes:"normal"})`

b: Ich bin nicht irrational. Es *gibt* Leute, die Drogen in den Punsch mischen. Das gibt's tatsächlich und es kommt vor.

`bb({eyes:"suspect"})`

b: Mensch, hast du Kopfschmerzen? Sind deine Glieder taub? Ich glaube wir sterben.

`bb({body:"scream_a_1"})`

b: AHHH WIR STERBEN! WIR STERBEN WIR STERBEN WIR STER--

`_.a2_attack_3 = "harm";`

`_.a2_hoodie_callback = "Punsch-Schüsseln";`

(#act2d)

# act2d

```
bb({body:"normal", mouth:"normal", eyes:"normal"});
hong({body:"attacked"});
attack("20p", _.a2_attack_1);
```

(...401)

```
hong({body:"attacked_2"});
attack("20p", _.a2_attack_2);
```

(...401)

```
hong({body:"attacked_3"});
attack("20p", _.a2_attack_3);
```

(...1001)

h: SCH^EISSSSEEE^!

H: SCH^EISSE^ SCH^EISSE^ SCH^EISSE^ *SCH^EISSSSEEE^*

`bb({body:"two_up", mouth:"smile", eyes:"happy"});`

b: Hurra, Mensch! Ich bin so glücklich, dass du mich wieder hören kannst!

`bb({body:"normal", mouth:"small", eyes:"sad"})`

b: Warum hast du mich ignoriert?

`hong({body:"facepalm"})`

h: VERF^ICKTE^ SCH^EISSE^, du Vollidiot.

`hong({body:"facepalm_2"})`

h: Kennst du diese Indianer-Geschichte?

h: "Du hast zwei Wölfe in dir. Der eine ist Hoffnung, der andere Angst. Welcher Wolf gewinnt? Der, den du fütterst."

```
hong({body:"facepalm_3"});
bb({eyes:"normal"});
```

h: Ich hab versucht dich *verhungern* zu lassen, du sadistisches ^Arschloch^!

`hong({body:"smile", mouth:"smile"})`

h: Sch^eiß^ drauf, ich versuchs stattdessen mit positiver Selbstbestätigung

h: *Ich werde geliebt. Ich bin gut. Ich bin schlau. Ich bin schön. Ich bin besonders.*

`bb({eyes:"suspect"});`

[Menschenskind, das ist so narzistisch!](#act2d_narcissist)

[Solche Übungen wurden *wiederlegt*...](#act2d_disproven)

[*Indianer*... *Ein Topf*?!](#act2d_racist)

# act2d_disproven

`bb({body:"point", mouth:"normal", eyes:"closed"})`

b: Tatsächlich geht sowas für Leute mit geringem Selbstwertgefühl gerne *nach hinten los*!

`bb({body:"one_up", mouth:"small", eyes:"normal"})`

b: Das war ne gut durchdachte Studie - zufällige Kontrollgruppen, anonymisierte Daten, usw.

`bb({body:"two_up", mouth:"small", eyes:"normal_r"})`

b: Das Ergebnis: Wenn du vorher schon geringen Selbstwert hattest, zieht positive Selbstbestätigung deine Laune nur *noch weiter* runter!

`bb({body:"point", mouth:"normal", eyes:"closed"})`

b: Wood 2009, Psychological Science. Schau auf Google Scholar nach, Mensch,

`bb({body:"scream_b_1"})`

b: UND HÖR AUF UNWISSENSCHAFTLICHE FAKE NEWS ZU VERBREITEN

```
hong({body:"attacked"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
attack("10p", "bad");
```

(...2500)

(#act2e)

# act2d_narcissist

`bb({body:"normal", mouth:"normal", eyes:"normal"})`

b: Du *musst* deine eigenen Fehler demütig eingestehen, um als Mensch zu wachsen!

`bb({body:"two_up", eyes:"suspect"})`

b: Du kannst nicht einfach Luferfrischer in nem Raum mit Schimmel rumsprühen! Einfach den Teppich drüber kehren macht's langfrisitg nur schlimmer.

`bb({body:"chest", mouth:"smile", eyes:"closed"})`

b: Gott sei Dank kann ich dich als dein treuer Wachwolf auf solche Makel aufmerksam machen. Und jetzt gerade ist es-

`bb({body:"scream_b_1"})`

b: ALLES. ALLES IST FALSCH

```
hong({body:"attacked"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
attack("10p", "bad");
```

(...2500)

(#act2e)

# act2d_racist

`bb({body:"normal", mouth:"normal", eyes:"suspect"})`

b: Amerikanische Ureinwohner sind *echte Menschen*, nicht irgendwelche "edlen Wilden", die du erwähnen kannst, nur damit deine Kalendersprüche *exotischer* wirken.

`bb({eyes:"suspect_r"})`

b: Du reduzierst individuelle Menschen und komplexe Kulturen zu Abziehbildchen! Das ist "gut gemeinter Rassismus"!

`bb({body:"scream_b_1"})`

b: HÖR AUF RASSISTISCH ZU SEIN, DU NEIDISCHER IDIOT

```
hong({body:"attacked"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
attack("10p", "bad");
```

(...2500)

(#act2e)

# act2e

h: SCH^EISSEVERDAMM^T.

`hong({body:"yell", mouth:"yell"})`

h: Weißt du was? Du bist *irrational*.

h: Die Emotionen von jedem sind irrational! Erst recht Angst!

`hong({body:"facepalm_2"})`

h: Du bist ein unnützes evolutionäres Überbleibsel, wie mein Blinddarm oder Weisheitszähne!

`hong({body:"yell", mouth:"yell"})`

h: Himmel, diese ganze Wolf-Metapher ist so dumm! Du bist nur ein Haufen an chemischen Stoffen in meinem Kopf.

`hong({body:"cross", mouth:"cross"})`

h: Also warum sollte ich einem wertlosen, irrationalen, nicht-existenten Stück ^Scheiße^ wie dir überhaupt zuhören?!

`bb({eyes:"sad", MOUTH_LOCK:true})`

b: ...

[Herrgott, Mensch. Das ist echt verletzend.](#act2e_hurtful)

[Ich bin ein Gefühl. Gefühle sind berechtigt.](#act2e_valid)

[Mensch, wir sind *beide* bloß chemische Stoffe."](#act2e_rational)

# act2e_hurtful

`bb({body:"chest"})`

b: Ich bin ein *Teil* von dir, weißt du? Wenn du das sagst, tust du dir *selbst* weh.

`bb({body:"scream_a_1"})`

b: Warum tust du dir selbst weh, Mensch? HÖR AUF DAMIT.

```
music(null);
hong({body:"attacked"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
attack("10p", "harm");
```

(...2500)

(#act2f)

# act2e_rational

`bb({body:"normal", mouth:"normal", eyes:"normal_r"});`

b: Deine tieflegenste Motivation ist Dopamin, deine beste Freude ist Serotonin.

`bb({body:"one_up"});`

b: Deine Erinnerungen sind Synapsen-Verbindungen und dein Verstand besteht aus Störungs-anfälligen elektrischen Signalen.

`bb({eyes:"normal", body:"normal"});`

b: Also wenn *ich* irrational bin, nur weil ich "nur chemische Stoffe" bin... dann heißt das *du bist irrational*!

`bb({body:"two_up", eyes:"shock"});`

b: Und wenn wir *beide* irrational sind, dann werden wir *nie* herausfinden, wie man erfüllt und glücklich ist!

`bb({body:"scream_a_1"})`

b: AHHH WIR SIND SO KAPUTT! SO KAPUTT SO KAPUTT SO KAPPUTT--

```
music(null);
hong({body:"attacked"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
attack("10p", "bad");
```

(...2500)

(#act2f)

# act2e_valid

`bb({body:"normal", mouth:"normal", eyes:"suspect"});`

b: Warte mal... "die" sagen, dass alle Gefühle wichtig sind, dass du immer deine Emotionen akzeptieren solltest.

`bb({eyes:"suspect_r"});`

b: Aber "die" sagen auch, dass Emotionen irrational sind, dass du ihnen nicht vertrauen darfst.

`bb({eyes:"angry"});`

b: Oh mein Gott, "die" haben uns die ganze Zeit angelogen!

`bb({body:"scream_a_1"})`

b: "DIE" HABEN UNS WIEDERSPRÜCHE EINGETRICHTERT, DAMIT WIR AUF DIE SELBSTHILFE INDUSTRIE ANGEWIESEN SIND

```
music(null);
hong({body:"attacked"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
attack("10p", "harm");
```

(...2500)

(#act2f)

# act2f

`hong({body:"defeated", MOUTH_LOCK:true});`

h: ...

h: Ich hasse das. Gott es tut so weh, Ich *hasse* das.

h: Ich kann dich nicht besänftigen. Ich kann dich nicht ignorieren. Ich kann dich nicht bekämpfen.

`bb({eyes:"suspect"});`

h: Egal, was ich mache, ich kann dich nicht loswerd--

`bb({body:"cry_1"});`

b: Naja, vielleicht *SOLLST* DU MICH GAR NICHT LOSWERDEN.

`bb({body:"cry_2"});`

b: Was denkst du, wie *ich* mich fühle, Mensch?!

`bb({body:"cry_4", mouth:"cry", eyes:"cry"})`

b: Ich versuche mein Bestes, dein treuer Wachwolf zu sein, aber du siehst mich nur als Großen Bösen Wolf!

b: Also versuch ich noch *viel mehr*, dich auf Gefahren aufmerksam zu machen. *Größere* Gefahren! *Andere* Gefahren!

`bb({eyes:"cry_2"})`

b: Aber egal, wie sehr ich versuche, dich zu beschützen, du denkst *immer noch*, dass ich dein Feind bin!

`bb({body:"cry_5"});`

b: Was mach ich denn falsch?!

`bb({body:"cry_2"});`

b: Ich *weiß* ich schlechte Arbeit leiste. Aber ich *bemühe mich*, Mensch!

`bb({body:"cry_3"});`

b: ...ich bemüh' mich ja.

`bb({body:"cry_6", mouth:"right", eyes:"cry_r_1"});`

b: Du musst meinen Warnungen gar keine Beachtung schenken, oder mir zustimmen, oder mich irgendwie *mögen*.

`bb({eyes:"cry_r_2"});`

b: Es ist nur... ich will nur, dass du etwas geduldig mit mir bist.

`bb({eyes:"cry_r_3"});`

b: Ich will nur, dass du ein Weilchen neben mir sitzt, anstatt dich sofort wegzudrehen und--

```
bb({eyes:"cry_r_4"});
hong({body:"listen"});
```

r: Hey.

```
hong({body:"look"});
Game.clearText();
publish("act2-in-2");
publish("hp_hide");
music('party1', {volume:0.4, fade:2});
```

(...2000)

```
publish("act2",["party_hunter",2]);
Game.WORDS_HEIGHT_BOTTOM = 230;
```

r: Sieht so aus, als ob du ganz schön mit dir selbst kämpfst, Kindchen.

```
publish("act2",["party_hunter",3]);
publish("act2",["party_hong",13]);
```

h2: War es so offensichtlich?

```
publish("act2",["party_hunter",4]);
publish("act2",["party_hong",14]);
```

r: Naja, du hast, ähm, irgendwas über {{_.a2_hoodie_callback}} oder so in deine Kapuze gemurmelt.

```
publish("act2",["party_hunter",13]);
publish("act2",["party_hong",15]);
sfx("rustle", {volume:0.6});
setTimeout(function(){
	publish("act2",["party_hong",16]);
	sfx("concrete_step3", {volume:0.6});
},401);
setTimeout(function(){
	publish("act2",["party_hong",17]);
	sfx("concrete_step4", {volume:0.6});
},801);
```

h2: Oh Gott, ich bin so ein Durcheinander.

```
publish("act2",["party_hunter",7]);
publish("act2",["party_hong",18]);
sfx("squeak");
```

r: Hey. Du bist nicht alleine, mein Freund. Angstgefühle sind super häufig.

```
publish("act2",["party_hunter",5]);
publish("act2",["party_hong",19]);
```

{{if _.act1_ending=="fight"}}
r: Zum Kuckuck, erst gestern hab ich gehört, dass jemand auf dem Kampus in 'ner Nervenattacke sein Handy kaputt gemacht hat!
{{/if}}

{{if _.act1_ending=="flight"}}
r: Zum Kuckuck, erst gestern hab ich gehört, dass sich jemanda uf dem Kampus wie ein Güreltier zusammengerollt hat und in aller Öffentlichkeit losgeflennt hat!
{{/if}}

```
publish("act2",["party_hunter",2]);
```

r: Hör zu: Ich weiß, wie es ist, so ein Tier im Kopf zu haben.

```
publish("act2",["party_hunter",8]);
```

r: Wir *alle* kennen das. Das ist der Grund, warum ich jedes Wochenende diese Parties schmeiße: Damit wir unsere Sorgen - dieses Tier - vergessen können.

```
publish("act2",["party_hunter",9]);
publish("act2",["party_hong",20]);
```

h2: aber meine Angst...

```
publish("act2",["party_hunter",2]);
publish("act2",["party_hong",21]);
```

r: Mach dir keine Sorgen, Kindchen. Ich war auch wie du. Aber ich hab' nen praktischen kleinen Trick gefunden, der die negative Stimme dauerhaft ausgeschaltet hat...

```
publish("act2",["party_hunter",3]);
Game.clearText();
music(null, {fade:1});
```

(...2001)

```
publish("act2",["party_hunter",10]);
publish("act2",["party_hong",22]);
sfx("rustle");
```

(...2501)

```
publish("act2",["party_hunter",10]);
publish("act2",["party_hong",23]);
sfx("rustle2");
```

(...1001)

```
publish("act2",["party_hunter",11]);
```

r: Mein eigener Spezialmix. Ist 'n bisschen stärker als... naja, irgendwas legales, wenn ich ehrlich bin.

```
publish("act2",["party_hunter",12]);
publish("act2",["party_hong",24]);
```

r: Hoch die Gläser, Schnucki!

```
hong({body:"hold"});
bb({body:"normal", mouth:"small", eyes:"wat"});
Game.clearText();
Game.WORDS_HEIGHT_BOTTOM = -1;
publish("act2-out-3");
publish("hp_show");
```

(...3500)

[Oh mein Gott.](#act2g_1) `Game.OVERRIDE_CHOICE_LINE=true`

[Das ist 'ne schlechte Bewältigungsstrategie.](#act2g_2) `Game.OVERRIDE_CHOICE_LINE=true`

[Nimm keine Drinks von Fremden an.](#act2g_3) `Game.OVERRIDE_CHOICE_LINE=true`

# act2g_1

b: O--

(#act2g)

# act2g_2

b: D--

(#act2g)

# act2g_3

b: N--

(#act2g)

# act2g

```
hong({body:"drink"});
bb({body:"attacked"});
attackBB("40p", "harm");
```

(...2000)

```
hong({body:"forward", mouth:"forward"});
bb({body:"frazzled", mouth:"frazzled", eyes:"frazzled"});
```

h: Hmm, was für ein exquisites Armoa!

h: Ein vollmundiger Geschmack von "blend deine Gedanken aus", mit nem leichten Abgang von "fühl nie wieder irgendwas"!

b: Das ist schlecht Mensch. Das ist wirklich, wirklich schlecht.

[Das ist *genau* wie Sucht startet](#act2h_opt1) `Game.OVERRIDE_CHOICE_LINE=true`

[Ich *wusste*, die Gastgeberin ist total fertig!](#act2h_opt3) `Game.OVERRIDE_CHOICE_LINE=true`

[Außerdem, da könnte sonst-was drin sein!](#act2h_opt2) `Game.OVERRIDE_CHOICE_LINE=true`


# act2h_opt1

b: Das ist *gena*--

(#act2h)

# act2h_opt2

b: Außerdem, da könnte s--

(#act2h)

# act2h_opt3

b: Ich *wusste*, di--

(#act2h)

# act2h

```
hong({body:"drink"});
bb({body:"attacked"});
attackBB("40p", "harm");
```

(...2000)

```
hong({body:"back", mouth:"back"});
bb({body:"panicked", mouth:"panicked", eyes:"panicked"});
```

h: Lecker! *Und* günstiger als Psycho-Therapie!

b: MENSCH BITTE HÖR AUF

h: Hahaha!

h: Und was willst *du* dagegen machen, A^rschloch^?

b: Es tut mir so leid, Mensch.

b: Ich werde meinen SPEZIAL-ANGRIFF benutzen müssen

```
bb({body:"special_a"});
music('battle', {volume:0.5});
```

`Game.OVERRIDE_CHOICE_SPEAKER = "fear_harm"`

[](#act2h_attack) `_.SPECIAL_ATTACK="harm"; Game.OVERRIDE_CHOICE_LINE=true`

`Game.OVERRIDE_CHOICE_SPEAKER = "fear_alone"`

[](#act2h_attack) `_.SPECIAL_ATTACK="alone"; Game.OVERRIDE_CHOICE_LINE=true`

`Game.OVERRIDE_CHOICE_SPEAKER = "fear_bad"`

[](#act2h_attack) `_.SPECIAL_ATTACK="bad"; Game.OVERRIDE_CHOICE_LINE=true`

# act2h_attack

```
bb({body:"special_b_1"});
hong({body:"forward", mouth:"forward"});
sfx("charging");
```

h: Was ist das für'n Sch^eiß^?

h: Du willst mir noch mehr dumme *Wörter* zukleffen, um mich--

```
bb({body:"special_c"});
sfx("hadouken");
```

(...901)

(#act2i)

# act2i

```
publish("hide_tabs");
publish("show_special_attack");
Game.FORCE_CANT_SKIP = true;
music(null);
stopAllSounds();
```

(...5000)

```
publish("show_tabs");
hong({ body:"final", mouth:"final" });
bb({ body:"normal", mouth:"normal", eyes:"sad" });
attack("100p", _.SPECIAL_ATTACK);
Game.FORCE_CANT_SKIP = false;
setTimeout(function(){
	publish("remove_special_attack");
},30);
```

(...2500)

h: WAS ZUR ^HÖLLE^ WAR DAS

b: Es tut mir leid. Ich musste dir die Konsequenzen zeigen.

{{if _.SPECIAL_ATTACK=="harm"}}
h: ICH KONNTE MEINE EIGENE LEICHE *SEHEN*. ICH KONNTE *SPÜREN* TATSÄCHLICH TOT ZU SEIN.
{{/if}}

{{if _.SPECIAL_ATTACK=="alone"}}
h: ICH KONNTE *SEHEN* WIE MICH JEDER ANGEWIEDERT ANSIEHT. ICH KONNTE ALLES *HÖREN*, WAS SIE GESAGT HABEN.
{{/if}}

{{if _.SPECIAL_ATTACK=="bad"}}
h: ICH KONNTE DAS KNACKEN VON RIPPEN *HÖREN*. ICH KONNTE DEN GESCHMACK VON BLUT IN DER LUFT *SCHMECKEN*.
{{/if}}

b: Es tut mir Leid, Mensch.

n: *MACH IHN FERTIG*

[{KÄMPFE: Schlag die Gastgeberin.}](#act2j_fight) `Game.OVERRIDE_CHOICE_LINE=true`

[{FLIEHE: Lass uns hier abhauen.}](#act2j_flight) `Game.OVERRIDE_CHOICE_LINE=true`

# act2j_fight

`bb({ eyes:"angry" });`

b: Diese Psychopathin hat dich nur ausgenutzt.

b: Die wollte dich verderben und dich so fertig machen, wie sie selbst ist!

`bb({ body:"yell_angry_1" });`

b: Schlag die Kuh! Schlag ihr in die verdammte Birne!

`bb({ body:"final_1" });`

b: SCHLAG SIE SCHLAG SIE SCHLAG SIE SCHLAG SIE SCHLAG SIE SCHLAG SIE SCHLAG SIE SCHLAG SI-

`_.a2_ending = "fight";`

(#act2k)

# act2j_flight

b: Ich *wusste*, dass all diese Party-Leute zutiefst verstört sein müssen. Die betäuben alle ihren Schmerz mit schrecklichen Sachen!

`bb({ body:"yell_1" });`

b: Und sie legen dich rein, dass du das auch machst! Die verderben dich! Wir müssen hier raus!

`bb({ body:"final_1" });`

b: HAU AB HAU AB HAU AB HAU AB HAU AB HAU AB HAU AB HAU AB HAU AB HAU AB HAU AB HA--

`_.a2_ending = "flight";`

(#act2k)

# act2k

```
Game.clearText();
publish("act2-in-4");
publish("hp_hide");
music('party1', {volume:0.6, fade:1.5});
```

(...2001)

```
publish("act2",["party_hong",26]);
sfx("slide");
```

(...1001)

```
publish("act2",["party_hunter",14]);
Game.WORDS_HEIGHT_BOTTOM = 230;
```

r: Geht's dir gut Kind?

`publish("act2",["party_hunter",13]);`

{{if _.a2_ending=="fight"}}
(#act2k_fight)
{{/if}}

{{if _.a2_ending=="flight"}}
(#act2k_flight)
{{/if}}

# act2k_fight

```
Game.clearText();
publish("act2",["party_hunter",21]);
publish("act2",["party_hong",33]);
music(null);
sfx("hit");
```

(...1000)

```
sfx("record_scratch");
publish("act2",["party_hunter",22]);
publish("act2",["party_hong",34]);
publish("act2",["dee",6]);
publish("act2",["dum",6]);
```

r: D-du...

```
publish("act2",["party_hunter",23]);
publish("act2",["party_hong",35]);
publish("act2",["dee",5]);
publish("act2",["dum",5]);
music('party1', {volume:0.6, fade:6});
```

r: bist *abgedreht*.

r: Ich mag das. Komm nächstes Wochenende auf meine Party, Süßer.

```
publish("act2",["party_hunter",19]);
publish("act2",["party_hong",36]);
```

h2: ok bye, ciao, adios, au revoir

r: Das Tier mag heute gewonnen haben, aber wenn du wieder kommst, mix ich dir was noch stärkeres!

h2: sayōnara, auf wiedersehen, zài jiàn, shalom

r: Du und ich, Kind, wir zeigen dem Vieh wer das Sagen hat!

(#act2k_end)

# act2k_flight

`publish("act2",["party_hong",36]);`

h2: ok sorry, ich muss abhauen

`publish("act2",["party_hunter",16]);`

r: ^Verdammt^. Das Tier hat heute gewonnen, wie?

`publish("act2",["party_hunter",15]);`

h2: Nein nein, es ist nur so, ähm, ich lauf morgen 'nen Marathon. Bruder muss los.

`publish("act2",["party_hunter",19]);`

r: Komm nächste Woche zu meiner Partie, Süßer. Dann mix ich dir was noch stärkeres.

h2: ok danke mus los los los los

r: Du und ich, Kind, wir zeigen dem Vieh schon wer das Sagen hat!

(#act2k_end)

# act2k_end

```
Game.clearText();
publish("act2-out-5");
publish("act2-outro", ["end1"]);
music("hum", {fade:2, volume:0.6});
Game.WORDS_HEIGHT_BOTTOM = -1;
```

(...2500)

```
publish("act2", ["act2_end",2]);
sfx("whoosh");
```

(...1000)

b: Mensch! Bist du in Ordnung?!

```
publish("act2", ["act2_end","next"]);
```

b: Wow, das war *knapp.* Wir hätten wirklich fast--

```
Game.clearText();
publish("act2", ["act2_end","next"]);
music(null);
sfx("squeak");
```

(...1500)

```
publish("act2", ["act2_end","next"]);
sfx("hit");
```

(...1000)

h: Ich werd nächstes Wochenende auf die Party gehen.

h: Nächstes Mal, wenn wir kämpfen, werd' ich dich nicht einfach nur *schlagen*...

h: Ich werd' dich ver^fickt^-noch-mal *umbringen*.

```
Game.clearText();
publish("act2", ["act2_end","next"]);
sfx("concrete_step1");
````

(...901)

```
publish("act2", ["act2_end","next"]);
sfx("concrete_step2", {volume:0.8});
```

(...901)

```
publish("act2", ["act2_end","next"]);
sfx("concrete_step3", {volume:0.5});
```

(...901)

`sfx("concrete_step4", {volume:0.25});`

(...3000)

`_.INTERMISSION_STAGE = 2;`

(#intermission)