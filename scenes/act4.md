# act4

```
SceneSetup.act4();
publish("SAVE_GAME", ["act4"]);
Game.FORCE_CANT_SKIP = true;
```

(...5001)

```
publish("set_how_many_prompts", [1]);
Game.FORCE_CANT_SKIP = false;
Game.CLICK_TO_ADVANCE = true;
```

n3: (automatisch gespeichert)

```
Game.clearText();
Game.FORCE_CANT_SKIP = true;
```

(...1001)

```
var hong_frame = _.INJURED ? 9 : 0;
publish("act4", ["hong_walks_in",hong_frame]);
sfx("grass_step1", {volume:0.1});
```

(...666)

```
publish("act4", ["hong_walks_in", "next"]);
sfx("grass_step2", {volume:0.2});
```

(...666)

```
publish("act4", ["hong_walks_in", "next"]);
sfx("grass_step1", {volume:0.25});
```

(...666)

```
publish("act4", ["hong_walks_in", "next"]);
sfx("grass_step2", {volume:0.3});
```

(...666)

```
publish("act4", ["hong_walks_in", "next"]);
sfx("grass_step1", {volume:0.35});
```

(...1667)

```
publish("act4", ["hong_walks_in", "next"]);
sfx("grass_step2", {volume:0.35});
```

(...666)

```
publish("act4", ["hong_walks_in", "next"]);
sfx("grass_step1", {volume:0.35});
```

(...666)

```
publish("act4", ["hong_walks_in", "next"]);
sfx("grass_step2", {volume:0.35});
```

(...1333)

```
publish("act4", ["hong_walks_in", "next"]);
sfx("grass_step1", {volume:0.20});
```

(...167)

```
publish("act4_hong_sits");
```

(...66)

```
publish("act4", ["hong_transition", "next"]);
sfx("squeak");
```

(...133)

`publish("act4", ["hong_transition", "next"]);`

(...1333)

```
publish("act4", ["hong_transition", "next"]);
sfx("rustle");
```

(...333)

`publish("act4", ["hong_transition", "next"]);`

(...1001)

```
publish("act4", ["hong_transition", "next"]);
```

(...333)

```
publish("act4", ["hong_transition", 9]);
sfx("sandwich");
```

(...333)

`publish("act4", ["hong_transition", 10]);`

(...333)

`publish("act4", ["hong_transition", 9]);`

(...333)

`publish("act4", ["hong_transition", 10]);`

(...333)

`publish("act4", ["hong_transition", 9]);`

(...333)

`publish("act4", ["hong_transition", 10]);`

(...333)

`publish("act4", ["hong_transition", "next"]);`

(...1466)

`publish("act4-out-1");`

(...201)

`publish("act4", ["hong_transition", "next"]);`

(...99)

`publish("act4", ["hong_transition", "next"]);`

(...99)

`publish("act4", ["hong_transition", "next"]);`

(...99)

`publish("act4", ["hong_transition", "next"]);`

(...99)

`publish("act4", ["hong_transition", "next"]);`

(...99)

`publish("act4", ["hong_transition", "next"]);`

(...99)

`publish("act4", ["hong_transition", "next"]);`

(...99)

`publish("act4", ["hong_transition", "next"]);`

(...99)

`publish("act4", ["hong_transition", "next"]);`

(...99)

```
publish("act4-show-chars");
Game.FORCE_CANT_SKIP = false;
```

(...901)

`hong({body:"sigh_1"})`

(...601)

```
hong({body:"sigh_2"});
bb({eyes:"look_down"});
```

h: *seufz*

```
hong({body:"hold", eyes:"normal", mouth:"normal"});
bb({eyes:"normal"});
```

h: Also was zur ^Hölle^ war die Moral von dieser Geschichte?

`hong({body:"one_up", eyes:"annoyed"})`

h: Was haben wir bitte *gelernt*? Ich *war* dumm, meine "Freunde" haben mich benutzt und verdammt, wir sind fast *gestorben*.

`hong({body:"normal", eyes:"normal"})`

{{if _.INJURED}}
[Von der KKH-Rechnung ganz abgesehen.](#act4a_bill)
{{/if}}

{{if !_.INJURED}}
[Ja, vom Leberschaden mal ganz abgesehen.](#act4a_liver)
{{/if}}

[Ja, das *war* das Worst-Case Szenario.](#act4a_worst)

[Ja, ich hatte recht.](#act4a_right)

# act4a_bill

`hong({eyes:"annoyed_l", mouth:"narrow"});`

h: Richtig. Ich glaub' meine Versicherung deckt Dummheit nicht mit ab.

`hong({eyes:"annoyed", mouth:"normal"});`

b: Und dennoch... wir haben überlebt!

`hong({eyes:"normal"});`

h: ?

(#act4b)

# act4a_liver

`bb({eyes:"normal_d"});`

b: Wir haben definitiv ein paar Jährchen von unserer Lebenserwartung gestrichen...

`bb({eyes:"surprise"});`

b: Aber zumindest *haben* wir noch eine Lebenserwartung! Wir haben überlebt!

```
hong({eyes:"surprise"});
bb({eyes:"normal"});
```

h: ?

(#act4b)

# act4a_worst

`bb({eyes:"normal_d"});`

b: Und dennoch...

h: Hm?

`bb({eyes:"surprise"});`

b: Wir haben überlebt!

(#act4b)

# act4a_right

`bb({eyes:"normal_d"});`

b: Aber... du hattest auch recht.

`hong({eyes:"surprise"});`

h: Hm?

`bb({eyes:"normal"});`

b: Ich *habe* zu oft Alarm geschlagen. Und bei einer *richtigen* Gefahr, hast du mir - verständlicherweise - nicht mehr geglaubt.

`bb({eyes:"surprise_r"});`

b: Und dennoch, wir haben überlebt!

(#act4b)

# act4b

```
bb({eyes:"normal", mouth:"normal"});
hong({eyes:"normal", mouth:"normal"});
```

b: Trotz allem, sind wir immernoch hier.

`hong({eyes:"suspect"});`

{{if _.INJURED}}
h: Du wirkst ziemlich ruhig, wenn man bedenkt, dass wir gerade eine Nahtoderfahrung hatten.
{{/if}}

{{if !_.INJURED}}
h: Du wirkst ziemlich ruhig, wenn man bedenkt, dass wir gerade eine *Supernah*toderfahrung hatten.
{{/if}}

```
hong({eyes:"normal"});
bb({eyes:"annoyed_d", mouth:"narrow"});
```

b: Naja, im Vergleich macht es alles andere weniger beunruhigend. Es hat mich auch ins Grübeln gebracht...

`bb({eyes:"normal", mouth:"normal"});`

b: Gegen dich anzukämpfen ist schlecht, weil es dich nicht beschützt...

h: Aber gegen dich anzukämfen ist *auch* schlecht, weil du dann bloß lauter brüllst...

`bb({eyes:"normal_r"})`

b: Vielleicht...

`bb({eyes:"normal"})`

h: Vielleicht müssen wir gar nicht gegeneinander kämpfen.

```
Game.FORCE_CANT_SKIP = true;
Game.clearText();
```

(...301)

`publish("smash",[0]);`

(...2001)

```
publish("smash",[1]);
sfx("smash_glass");
```

(...2601)

```
publish("smash",[2]);
bb({eyes:"normal", mouth:"normal"});
hong({eyes:"normal", mouth:"normal"});
```

(...2001)

`Game.FORCE_CANT_SKIP = false;`

(#act4b_2)

# act4b_2

```
music('dontfight',{fade:5, volume:0.6});
bb({eyes:"annoyed_d"});
```

b: Ich bin kein großer böser Wolf. Aber ich bin auch kein Wachwolf.

`bb({eyes:"sad_d"})`

b: Ich bin ein mitgenommener Straßenhund.

`bb({eyes:"sad"})`

b: Wir haben übles Zeug erlebt. Vielleicht Trauma oder Vernachlässigung. Deshalb überreagiere ich manchmal und mach':

```
sfx("yaps", {volume:0.6});
bb({body:"yap_1"});
Game.FORCE_CANT_SKIP = true;
Game.WORDS_HEIGHT_BOTTOM = 215;
Game.FORCE_TEXT_DURATION = 90;
Game.FORCE_NO_VOICE = true;
```

b: KLÄFF KLÄFF KLÄFF KLÄFF KLÄFF KLÄFF

(...1884)

```
Game.WORDS_HEIGHT_BOTTOM = -1;
Game.FORCE_CANT_SKIP = false;
bb({body:"normal", mouth:"scream", eyes:"scream_sad"});
```

b: Aber ich *will* kein feiger Hund sein! Ich will dich beschützen! Ich will ein guter Hund sein!

`bb({eyes:"sad", mouth:"normal"});`

b: Mensch... wirst du helfen, diesen Wolf zu zähmen?

`hong({eyes:"sad"})`

h: Ich... Ich werd's versuchen.

`hong({eyes:"normal_l", body:"chin", mouth:"narrow"})`

h: Okay. Gesunde Beziehungen mit Emotionen. Beziehnungen brauchen Kommunikation. Also, lass uns kommunizieren.

`hong({eyes:"normal", body:"hands_1", mouth:"normal"})`

h: Die nächsten fünf Minuten werden super kitschig klingen, aber wie sagt man nicht so schön...

h: "Let's fake it 'til we make it."

```
hong({body:"hands_2", mouth:"normal"});
```

h: Lieber Kopf-Wolf... wie fühlst *du* dich?

n2: INSGESAMT GENUTZTE ÄNGSTE:

n2: *VERLETZT* {{_.attack_harm_total}}, *UNGELIEBT* {{_.attack_alone_total}}, *SCHLECHTER MENSCH* {{_.attack_bad_total}}

n2: ÜBER WELCHE ANGST WILLST DU ALS ERSTES REDEN? (DU KANNST DIE ANDEREN DANACH NEHMEN)

```
_.a4_fears_discussed = 0;
_.num_thanks = 0;
hong({body:"normal"});
bb({eyes:"normal"});
```

[Ich hab' Angst, verletzt zu werden.](#act4_harm)

[Ich hab' Angst, allein zu bleiben.](#act4_alone)

[Ich hab' Angst, ein schlechter Mensch zu sein.](#act4_bad)

# act4_harm

```
_.a4_talked_about_harm = true;
_.a4_fears_discussed += 1;
```

`bb({eyes:"normal_d"})`

b: Ich will dein Bedürfnis für körperliche Unversehrtheit schützen,

`bb({eyes:"sad_d"})`

b: Aber die *ganze Welt* wirkt so gefährlich. So voller Tragik und Bösem.

`bb({eyes:"sad"})`

{{if _.a4_fears_discussed==1}}
b: Ich weiß nicht, *ich* hab' genug gesagt. Was meinst *du*, Mensch?
{{/if}}

{{if _.a4_fears_discussed==2}}
b: Wieder zurück zu dir, Mensch. Was denkst du?
{{/if}}

{{if _.a4_fears_discussed==3}}
b: Irgendwelche Zusätze, Mensch?
{{/if}}

`Game.OVERRIDE_CHOICE_SPEAKER = "h"`

[Richtig. Also lass uns gegenseitig schützen.](#act4_harm_skills)

[Lass uns *mehr* Gefahren aussetzen.](#act4_harm_exposure)

[Danke.](#act4_thanks) `_.thanks_for = "körperliches Wohlbefinden";`

# act4_harm_skills

`bb({eyes:"look_down", body:"paw"})`

b: Aber... wie? Ich habe Fangzähne und Klauen, aber ich bin nur eine Metapher.

```
bb({ body:"normal", eyes:"normal" });
hong({ body:"one_up", eyes:"surprise" });
```

h: Wir könnten Selbstverteidigung lernen? Einer Gruppe beitreten, die sich gegenseitig in Schutz nehmen?

h: Oder generell unsere Gesundheit und unsere persönlichen Grenzen verbessern?

```
bb({ eyes:"annoyed_r" });
hong({ body:"normal", eyes:"normal" });
```

b: Vielleicht, aber...

[Wo sollen wir denn anfangen?](#act4_harm_skills_start)

[Was, wenn sie immer noch nicht funktionieren?](#act4_harm_skills_work)

[Was, wenn wir's mit "Sicherheit" übertreiben?](#act4_harm_skills_overboard)

# act4_harm_skills_start

`bb({ eyes:"sad_d" })`

b: Es gibt so viel zu tun, so viel, das wir an uns verbessern müssen. Wo soll man da bloß *anfangen*?

`hong({ body:"shrug", eyes:"surprise" })`

h: Wir fangen genau jetzt an.

`bb({ eyes:"normal", mouth:"narrow" })`

b: Hä?

```
bb({ body:"normal", mouth:"normal" });
hong({ body:"normal", mouth:"normal", eyes:"normal"});
```

h: Wir fangen genau jetzt an, gut zu kommunizieren.

h: Das wird uns helfen, Gefahren besser zu erkennen, mit weniger falschen Treffern,

`hong({ eyes:"surprise" });`

h: Und *das* wird uns helfen, uns vor Leid zu schützen!

`hong({ eyes:"normal", mouth:"normal" });`

h: Deswegen: Das *ist* Selbstverteidigungs-Training.

`bb({ eyes:"normal_r" })`

b: Hm. Ich hab' ja mehr sowas erwartet:

```
Game.FORCE_CANT_SKIP = true;
Game.clearText();
hong({ eyes:"sad", mouth:"smile" });
bb({ body:"karate_1" });
sfx("hiya");
```

(...1001)

`Game.FORCE_CANT_SKIP = false;`

(#act4_something_else)

# act4_harm_skills_work

`bb({ eyes:"normal" });`

h: Stimmt, es gibt keinen Weg, uns zu 100% zu schützen...

`hong({ body:"one_up" });`

h: Aber selbst eine 1%ige Verbesserung ist immernoch etwas wert, richtig?

```
bb({ eyes:"annoyed" });
hong({ normal:"one_up" });
```

b: Du siehst das Glas nicht als 99% leer, sondern als 1% voll?

`bb({ eyes:"normal" });`

h: Was einiges wert ist, wenn du in der Wüste gestrandet bist.

`bb({ eyes:"closed" });`

b: Tja. Hopp hopp, also.

(#act4_something_else)

# act4_harm_skills_overboard

`bb({ body:"chest", eyes:"annoyed" })`

b: Ich mein', du hast meine Warnungen nur ignoriert, weil *ich* übertrieben auf Sicherheit gepocht habe!

`bb({ body:"normal", eyes:"normal" })`

h: Nee, du hast recht. Wir sollten Sicherheit in Maßen halten. Alles in Maßen.

`bb({ eyes:"suspect" })`

b: Bitte, *ALLES* in Maßen?

`hong({ eyes:"annoyed" })`

h: *Eine gemäßigte Anzahl an Sachen* in Maßen.

```
bb({ eyes:"closed" });
hong({ eyes:"normal" });
```

b: Danke, dass du deine Aussagen rekursiv in sich widerspruchsfrei machst.

(#act4_something_else)


# act4_harm_exposure

`bb({ mouth:"scream_talk", eyes:"scream", MOUTH_LOCK:true });`

b: *WAS*

```
bb({ mouth:"narrow", eyes:"suspect" });
hong({ body:"one_up" });
```

h: Ich mein', lass uns sagen, ein Hund hat Angst vor Donner.

`hong({ body:"hands_1" });`

h: Ein Trick Trainer benutzen, ist eine Aufzeichnung von Donner mit geringer Lautstärke abzuspielen-

h: dann geben sie dem Hund ein Leckerchen, wenn er ruhig bleibt.

`hong({ body:"hands_2" });`

h: Über mehrere Tage hinweg erhöht der Trainer die Lautstärke-

h: immer ein bisschen mehr, bis der Hund seine Angst vor Donner überwunden hat.

```
hong({ body:"normal", eyes:"surprise" });
bb({ mouth:"normal", eyes:"normal" });
```

h: Das nennt sich Konfrontationstherapie!

`hong({ body:"point", eyes:"normal" });`

h: Da du ein Hund bist, sollte es auch für dich funktionieren, richtig?

h: Alle Säugetiere haben die selbe Kampf-oder-Flucht-Reaktion.

`hong({ body:"normal" });`

[Was, wenn wir *zu sehr* desensibilisiert werden?](#act4_harm_exposure_overboard)

[Was passiert dann bei einer *echten* Gefahr?](#act4_harm_exposure_hurt)

[Ich bin ein Wolf, kein Hund.](#act4_harm_exposure_dog) `bb({ eyes:"suspect" })`

# act4_harm_exposure_dog

h: Und ich zeig dir Güte und Geduld bis wir dich zu einem süßen kleinen Welpen gezähmt haben.

`bb({ MOUTH_LOCK:true })`

b: ...

`bb({ eyes:"sad", mouth:"smile" })`

b: Och wie süß.

(#act4_something_else)

# act4_harm_exposure_overboard

`bb({ eyes:"annoyed" })`

b: Wie haben *gerade* erst gesehen, was passiert wenn du dich deiner Angst verschließt-

b: du begiebst dich *tatsächlich* in gefährliche Situationen.

`bb({ eyes:"angry_r", body:"one_up" })`

b: Und nebenbei, werden wir durch *zu viel* Desensibilisierung nicht zu Psychopathen?

`bb({ mouth:"scream", eyes:"scream", body:"two_up" })`

b: Bald schon geben wir uns selbst Leckerchen währen wir Snuff-Mord-Pornos schauen!

`hong({ eyes:"annoyed" })`

h: Ich... denke es gibt einen feinen Unterschied zwischen dem da und Donner.

`bb({ body:"normal", mouth:"normal", eyes:"suspect" })`

b: Aber *wo genau*, Mensch? *Wo genau?!*

`hong({ eyes:"surprise", body:"one_up" })`

h: Ich weiß es nicht. Aber *du* kannst mir helfen!

`hong({ eyes:"normal", body:"normal" })`

h: Wir diskutieren und erarbeiten gemeinsam, wo diese Grenze liegt.

`bb({ body:"paw", mouth:"narrow", eyes:"closed" })`

b: Okay. Aber ich hab keine opponierbare Daumen, also musst du das Zeichnen übernehmen.

(#act4_something_else)

# act4_harm_exposure_hurt

`bb({ body:"two_up", eyes:"angry_r" })`

{{if _.INJURED}}
b: Zum Beispiel: Wir sind von 'nem verdammten *Dach* gesprungen!
{{/if}}

{{if !_.INJURED}}
b: Zum Beispiel: Wir sind fast von 'nem verdammten *Dach* gesprungen!
{{/if}}

```
hong({ eyes:"annoyed" });
bb({ body:"normal", eyes:"annoyed" });
```

h: Nee, du hast recht. Man *kann* zu weit gehen.

`hong({ eyes:"normal" });`

h: Aber das ist es ja, wenn wir's mit Konfrontationstherapie versuchen, fangen wir klein an-

h: und machen kleine Schritte nach vorne.

h: Kurz bevor wir *tatsächlich* in Gefahr geraten, hören wir auf.

`bb({ eyes:"annoyed_r", mouth:"narrow" });`

b: Hm ja, ich zieh' die Grenze zwischen lauten Donner hören und mit 'nem hohen Aluhut im Gewitter zu stehen.

(#act4_something_else)

# act4_thanks

`_.num_thanks += 1`

{{if _.num_thanks==1}}
(#act4_thanks_1)
{{/if}}

{{if _.num_thanks==2}}
(#act4_thanks_2)
{{/if}}

{{if _.num_thanks==3}}
(#act4_thanks_3)
{{/if}}

# act4_thanks_1

`bb({ MOUTH_LOCK:true })`

b: ...

`bb({ eyes:"annoyed" })`

b: Warte, keine Argumente für oder gegen meine Gefühle? Nur... "Danke"?

`hong({ eyes:"surprise", body:"shrug" })`

h: Ja! Danke, dass du dich um mein {{_.thanks_for}} sorgst.

```
bb({ eyes:"closed_annoyed", MOUTH_LOCK:true });
hong({ eyes:"normal", body:"normal" });
```

b: ...

h: Alles gut?

`bb({ eyes:"super_sad", mouth:"narrow" });`

b: Du hast noch nie vorher *danke* zu mir gesagt.

`hong({ mouth:"smile" });`

h: Och, du großer flauschig-wuscheliger Panikwolf.

(#act4_something_else)

# act4_thanks_2

h: Selbst wenn du überreagierst, schätze ich, dass du dich um mein {{_.thanks_for}} sorgst.

`bb({ eyes:"annoyed" })`

b: Warte... du wiederholst nicht einfach nur "Danke", um nicht über diese Ängste reden zu müssen, oder?

```
bb({ eyes:"normal" });
hong({ eyes:"annoyed", body:"chin" });
```

h: Naja, sowas ist kompliziert und ich hab' nicht immer 'ne Antwort parat.

`hong({ eyes:"annoyed_l", body:"one_up" })`

h: Es ist ja nicht so, als ob ich 'ne Liste von 3 vorgefertigten Dialog-Antworten hätte.

`hong({ eyes:"normal", mouth:"smile", body:"normal" })`

h: Aber für den Moment kann ich zumindest Danke sagen.

b: Gut, dann danke auch dir, dass du mir so geduldig zuhörst.

`bb({ eyes:"closed" });`

b: Du kleines haarloses Fleisch-Säugetier.

(#act4_something_else)

# act4_thanks_3

h: Selbst wenn mich dein Kläffen ängstigt, versuchst du lediglich mein {{_.thanks_for}} zu bewahren.

`bb({ eyes:"smile_r" });`

b: Okay, wenn du mir weiter so schmeichelst, wird das Internet ein paar komische Gedanken zu uns haben.

```
bb({ eyes:"smile" });
hong({ eyes:"annoyed" });
```

h: Komm schon, ich bin nur ein verletzlicher junger Mensch, böser Wolf. Was ist das schlimmste, das p--

`hong({ eyes:"normal", body:"point" });`

h: Wobei, beantworte das nicht.

(#act4_something_else)




# act4_alone

```
_.a4_talked_about_alone = true;
_.a4_fears_discussed += 1;
```

`bb({ eyes:"sad_d" });`

b: Ich will sicher gehen, dass du diesen innigen menschlichen Bedarf nach Zugehörigkeit erfüllen kannst...

`bb({ eyes:"sad_u" });`

b: Aber ich mach' mir Sorgen, dass wenn uns jemand kennen lernen würde-

b: also das *echte* uns - dass wir alle einschüchtern würden.

`bb({ eyes:"sad" });`

{{if _.a4_fears_discussed==1}}
b: Ich weiß nicht, *ich* habe genug gesagt. Was meinst *du*, Mensch?
{{/if}}

{{if _.a4_fears_discussed==2}}
b: Nochmal zurück zu dir, Mensch. Was sagst du?
{{/if}}

{{if _.a4_fears_discussed==3}}
b: Was denkst du, Mensch?
{{/if}}

`Game.OVERRIDE_CHOICE_SPEAKER = "h"`

[Ja, lass uns an unserem Sozialleben arbeiten.](#act4_alone_skills)

[Ich glaub' Leute mögen uns. Probieren wir's?](#act4_alone_experiment)

[Danke.](#act4_thanks) `_.thanks_for = "Zugehörigkeitsgefühl";`

# act4_alone_skills

```
bb({ eyes:"normal" });
hong({ body:"chin" });
```

h: Wir könnten Sachen trainieren, wie Fragen-Stellen, Zuhören und Mitfühlen, Offen-und-verwundbar-Sein, usw.?

`hong({ eyes:"normal_l" });`

h: Oder uns bessere soziale Angewohnheiten anlegen-

h: wie Zeit mit Freunden einplanen oder zu regelmäßigen Treffen gehen?

`hong({ body:"one_up" });`

h: Wir könnten auch lernen, besser mit Zurückweisung umzugehen.

`hong({ eyes:"normal" });`

h: Oder zu lernen, wann Leute, die uns *nicht* zurückweisen, einfach nur müde oder grundsätzlich grummelig sind.

```
hong({ body:"normal" });
bb({ eyes:"annoyed_r" });
```

b: Das sind viele Möglichkeiten. Aber "soziale Fähigkeiten lernen"...

[Ist das nicht *manipulativ?*](#act4_alone_skills_manipulative)

[Macht uns das nicht *manipulierbarer?*](#act4_alone_skills_manipulated)

[Was, wenn wir trotzdem versagen?](#act4_alone_skills_fail)

# act4_alone_skills_manipulative

`bb({ eyes:"suspect" });`

b: Sind Serienmörder, die die Emotionen ihrer Opfer lesen können, nicht super "empathisch"?

`bb({ eyes:"annoyed" });`

b: Hat Charles Manson nicht viele Freunde und Einfluss?

`hong({ eyes:"annoyed", body:"chin" });`

h: Nein, du hast recht.

h: "Soziale Fähigkeiten" bedeuten nichts, wenn wir nicht ernsthaft an Leuten *interessiert* sind.

`hong({ body:"normal" });`

h: Also im Prinzip einfach "sei kein ^Arsch^".

`bb({ eyes:"annoyed", mouth:"smile" });`

b: Das ist ein extrem motivierender Poster-Spruch.

`hong({ body:"shrug", mouth:"narrow" });`

h: “Sei Kein ^Arsch^™”

(#act4_something_else)

# act4_alone_skills_manipulated

`bb({ eyes:"angry" })`

b: Wir hol'n uns 'ne Fußmatte auf der steht "Bitte und Danke, dass ihr eure Füße an uns abtretet!"

`bb({ mouth:"scream", eyes:"scream" })`

b: Wir kriechen den Leuten so sehr in den ^Arsch^, dass wir oben wieder rauskommen!

```
bb({ mouth:"normal", eyes:"normal" });
hong( body:"chin" });
```

h: Nee, du hast recht. "Soziale Fähigkeiten" können sich nur darum drehen, anderen zu gefallen.

h: Es muss auch darum gehen, *Grenzen* zu setzen.

`hong( body:"one_up" });`

h: Wir können andere nicht in unsere Wohnung einladen, wenn wir unsere Wohnung keine Wände hat.

```
hong( eyes:"angry", mouth:"narrow" });
bb( eyes:"annoyed", mouth:"smile" });
```

h: Also... bzgl. dem ^Arsch^kriech-Bild, das ich jetzt im Kopf hab'... *Igitt??*

(#act4_something_else)

# act4_alone_skills_fail

`bb({ eyes:"annoyed" });`

h: Vielleicht scheitern wir. Tatsächlich *werden* wir scheitern.

```
bb({ eyes:"normal" });
hong({ eyes:"surprise", body:"shrug" });
```

h: Und das ist in Ordnung! Scheitern ist der erste Schritt, um etwas neues zu lernen!

`hong({ body:"normal", eyes:"normal" });`

h: Also lass uns zusammen voran scheitern, okay?

`bb({ eyes:"normal_r" });`

b: Sicher. Ich nehm' an... im schlimmsten Fall, ziehen wir in 'ne andere Stadt und holen uns 'ne neue Identität.

`bb({ eyes:"normal" });`

h: Ja, ich denke, dass kostet heutzutage nur ein bis zwei Bitcoins.

(#act4_something_else)

# act4_alone_experiment

```
hong({ body:"one_up" });
bb({ eyes:"normal" });
```

h: Wir könnten ein paar Experimente versuchen!

`hong({ body:"chin" });`

h: Wir könnten einen Freund anschreiben, um abzuhängen, uns mit 'nem alten Kumpel wiederverbinden, oder einfach nur mit einem Barista schnacken.

`hong({ body:"normal" });`

h: Ich denke wir werden herausfinden, dass wir sympathischer sind, als wir vermuten.

`bb({ eyes:"annoyed" });`

[Was, wenn das kleine, billige "Siege" sind?](#act4_alone_experiment_cheap)

[Was, wenn das andere Leute belastet?](#act4_alone_experiment_burden)

[Aber Small Talk passt nicht zu *uns*!](#act4_alone_experiment_real_us)

# act4_alone_experiment_real_us

`bb({ eyes:"sad" });`

b: Wenn wir ein schmallippiges Lächeln aufsetzen, werden wir nie wirklich mir jemandem anknüpfen,

`bb({ eyes:"super_sad" });`

b: *Aber*, wenn wir uns öffnen werden andere unser ganzes kaputtes Inneres sehen können!

`hong({body:"chin", mouth:"narrow", MOUTH_LOCK:true})`

h: ...

```
hong({body:"normal", mouth:"normal"});
bb({eyes:"normal"});
```

h: Roll dich auf den Rücken.

b: Was.

`hong({body:"hands_1"})`

h: Wenn Hunde Liebe und Vertrauen zeigne wollen, machen sie sich verwundbar, indem sie ihren Bauch zeigen.

`hong({body:"one_up"})`

h: Vielleicht sind wir *noch* nicht sicher genug, um uns zu verwundbar zu machen, aber mit genug Training,

`hong({body:"normal", eyes:"surprise"})`

h: können wir eines Tages Leuten das echte uns zeigen - total fertig, total menschlich.

```
hong({eyes:"normal"});
bb({ eyes:"super_sad", mouth:"smile", body:"chest" });
```

b: Ich roll' mich auf den Rücken, wenn du mir ein Leckerchen gibst.

`bb({ eyes:"normal", mouth:"normal" });`

h: Nein.

(#act4_something_else)


# act4_alone_experiment_cheap

b: "Hi" zu einem Barista zu sagen, ist nicht gerade 'ne Goldmedallien-Leistung in den olympischen Nachtfalter-Spielen.

```
hong({ body:"point", eyes:"surprise" });
bb({ eyes:"normal" });
```

h: Es ist für *uns!*

`hong({ body:"one_up", eyes:"annoyed" });`

h: In der Sozial-Arena, sind wir nicht 'mal Federgewichte, wir sind mehr so... Quarkgewichte.

`hong({ body:"normal", eyes:"normal" });`

h: Wenn wir mit kleinen, billigen Siegen anfangen müssen, ist das halt so.

h: Man muss den ersten Schritt machen, bevor man den 1000sten macht.

b: Oh ja! Vielleicht können wir, nachdem wir "Hi" gesagt haben, weiter machen mit...

`bb({ body:"two_up", mouth:"smile", eyes:"smile_u" });`

b: *"Was geht?"*

`hong({ body:"shrug", mouth:"smile", eyes:"surprise_l" });`

h: *"Nicht viel!"*

(#act4_something_else)

# act4_alone_experiment_burden

`bb({ eyes:"suspect_r" })`

b: Vielleicht will der Barista einfach nur verdammten Kaffee machen-

b: und nicht zu einem *Sozialexperiment* werden, um zu beweisen, wie sehr unsere sozialen Fähigkeiten abstinken.

`bb({ eyes:"annoyed" })`

h: Naja, wenn sich herausstellt, dass wir nur eine *Belastung* sind...

```
hong({ eyes:"surprise" });
bb({ eyes:"normal" });
```

h: Ist es das auch gut zu wissen!

`hong({ eyes:"normal" });`

h: Wir können dann zumindest lernen, Leute proaktiv zu fragen, womit sie einverstanden sind,-

h: und herausfinden, wo die Grenzen von anderen liegen.

```
hong({ eyes:"annoyed_l", mouth:"narrow" });
bb({ eyes:"annoyed", mouth:"smile" });
```

h: Weißt du, dieser ganze "zwischenmenschliche Fähigkeiten"-^Scheiß^ aus Beratungs-Broschüren.

(#act4_something_else)



# act4_bad

```
_.a4_talked_about_bad = true;
_.a4_fears_discussed += 1;
```

`bb({ eyes:"annoyed_r" })`

b: Ich will deine moralischen Bedürfnisse schützen, die dich antreiben, ein besserer Mensch zu sein,

`bb({ eyes:"sad_d" })`

b: aber es fühlt sich einfach an, als wären wir tief drinnen so grundlegend... kaputt.

`bb({ body:"two_up", eyes:"angry" })`

{{if _.INJURED}}
b: Und sag mir nicht, dass wir *nicht* kaputt sind. Wir sind von einem *Dach* gesprungen.
{{/if}}

{{if !_.INJURED}}
b: Und sag mir nicht, dass wir *nicht* kaputt sind. Wir sind fast von einem *Dach* gesprungen.
{{/if}}

`bb({ body:"normal", eyes:"sad" })`

{{if _.a4_fears_discussed==1}}
b: Ich weiß nicht, *ich* hab schon genug gesagt. Was meinst *du*, Mensch?
{{/if}}

{{if _.a4_fears_discussed==2}}
b: Nochmal zurück zu dir, Mensch. Was denkst du?
{{/if}}

{{if _.a4_fears_discussed==3}}
b: Woran denkst du gerade, Mensch?
{{/if}}

`Game.OVERRIDE_CHOICE_SPEAKER = "h"`

[Ist halt so. Lass es uns richten.](#act4_bad_fix)

[Ist halt so. Lass es uns akzeptieren.](#act4_bad_accept)

[Danke.](#act4_thanks) `_.thanks_for = "moralisches Wohl";`

# act4_bad_fix

```
bb({eyes:"normal"});
hong({body:"chin"});
```

h: Wir könnten langsam, nach und nach bessere Angewohnheiten ansammeln-

h: unser Leben mehr mit dem vereinigen, was wir wertschätzen,

`hong({body:"one_up"});`

h: Und falls nötig, könnten wir professionelle Hilfe holen - von 'nem Therapeuthen oder Ratgeber.

`hong({body:"normal"});`

h: Es gibt Möglichkeiten uns zu richten.

[Was, wenn wir nicht alles fixen?](#act4_bad_fix_cant)

[Was, wenn wir *zu viel* fixen?](#act4_bad_fix_too_much)

[Wir können uns das nicht leisten.](#act4_bad_fix_afford)

# act4_bad_fix_cant

`hong({eyes:"annoyed"});`

h: Naja, ich nehm' an du hast recht.

h: Wir können nicht alles reparieren.

`bb({mouth:"scream", eyes:"scream_sad"});`

b: Ahhh ich wusste es, wir werden immer kaputt sein!

`hong({eyes:"surprise"});`

h: Aber wir können zumindest *weniger* kaputt sein.

```
bb({mouth:"normal", eyes:"annoyed"});
hong({eyes:"sad", mouth:"smile"});
```

h: Narben heilen mit der Zeit, aber sie gehen nie ganz weg.

h: Und das ist okay.

`bb({eyes:"annoyed_r"});`

b: Ich nehm' an, du hast recht. Und noch dazu-

```
Game.FORCE_TEXT_Y = 460;
Game.clearText();
publish("act4-sexy", [true]);
```

b: sind Narben *sexy.*

```
Game.FORCE_TEXT_Y = -1;
Game.clearText();
publish("act4-sexy", [false]);
bb({body:"chest", mouth:"smile_talk", MOUTH_LOCK:true, eyes:"sexy"}, 0);
hong({eyes:"normal", mouth:"normal"}, 0);
```

h: Bitte mach das nicht.

(#act4_something_else)

# act4_bad_fix_too_much

`bb({ eyes:"angry_d" })`

b: Es fühlt sich krank an, das zuzugeben, aber... ein Teil von mir *will* diese Störung haben.

`bb({ eyes:"angry" })`

b: Ich meine, ganze ohne - werden wir nicht *langweilig* sein?

`bb({ eyes:"sad_r", body:"one_up" })`

b: Ohne die Störung, wird unsere Kunst nicht abgestanden und fad?

`bb({ eyes:"sad_u", body:"two_up" })`

b: Ohne die Störung, werden wir nicht die Verbindung zu unseren Freunden verlieren, denen es genauso geht?

`bb({ eyes:"sad", body:"chest" })`

b: Wenn wir immer zufrieden mit dem Leben sind, werden wir nicht aufhören, großartige Dinge zu machen?

`hong({ MOUTH_LOCK:true })`

h: ...

h: Wenn wir sogar Angst davor haben... keine Angst mehr zu haben...

h: Ich glaube, dann werden wir immer vor irgendwas Angst haben.

`bb({ eyes:"smile_u", body:"normal", mouth:"smile" })`

b: Oh, stimmt. Puh! Was für eine Erleichterung!

(#act4_something_else)

# act4_bad_fix_afford

`bb({ body:"one_up", eyes:"sexy", mouth:"normal" })`

b: "Herr Doktor, ich habe Angst, dass ich 100$/h bezahle-

b: nur um Sie fragen zu hören *wie fühlt sich das an?*"

`bb({ body:"paw", eyes:"closed", mouth:"narrow" })`

b: "Hm-okay. Und wie fühlt sich das an?"

```
bb({ body:"normal", eyes:"normal", mouth:"normal" });
hong({ eyes:"sad" });
```

h: Nee du, das ist 'ne total angemessene Sorge.

`hong({ eyes:"annoyed", mouth:"sad" });`

h: Und es ist wirklich ^scheiße^, dass geistige Gesundheitsversorgung für viele Leute nicht bezahlbar ist.

`hong({ eyes:"normal", mouth:"normal" });`

h: Trotzdem, es gibt ein paar kostenlose Optionen:

`hong({ body:"chin" })`

h: Selbsthilfegruppen, Online-Therapie, Studenten- und gemeinnützige Gesundheits-Zentren...

`hong({ body:"hands_1" })`

h: Angewohnheiten wie Meditieren, gut Schlafen, regelmäßig mit Freunden quatschen, neue Sachen lernen...

`hong({ body:"hands_2" })`

h: In 'ne Bibliothek gehen, um Arbeitsbücher für evidenzbasierte Psychotherapie auszuleihen...

`hong({ body:"one_up" })`

h: Es gibt 'ne ganze List von Resourcen am Ende dieses Spiels!

```
hong({ body:"normal" });
bb({ eyes:"annoyed", mouth:"narrow" });
```

b: Naja *die* vierte Wand hat ja nicht lang gestanden.

`hong({ body:"point" });`

h: Einige Dinge sind wichtiger, als narrative Konventionen. Geistige Gesundheit zum Beispiel.

(#act4_something_else)


# act4_bad_accept

```
bb({ eyes:"normal" });
hong({ eyes:"normal_l", body:"one_up", mouth:"narrow" });
```

h: Ich meine, das ist, was Therapeuthen sagen, oder? Akzeptier' all deine Emotionen, sogar die negativen?

```
bb({ eyes:"annoyed" });
hong({ eyes:"normal", body:"normal", mouth:"normal" });
```

b: Warte.

["Akzeptieren" wie in *aufgeben*?](#act4_bad_accept_give_up)

["Akzeptieren" wie in *gutheißen*?](#act4_bad_accept_approve)

["Akzeptieren" wie in *wörtlich nehmen*?](#act4_bad_accept_literally)

# act4_bad_accept_give_up

`bb({ eyes:"angry", body:"one_up" });`

b: Denkst du, Martin Luther King hätte gesagt, "Leute wir können nicht vorne im Bus sitzen, lasst es uns einfach *akzeptieren*"?

`bb({ eyes:"angry_r", body:"two_up" });`

b: Warum denkt die Selbsthilfe-Industrie, 'ne weiße Flagge zu schwenken wär' irgend eine *tiefgründige Weisheit?*

`bb({ eyes:"annoyed", body:"normal" });`

h: Ich denke Therapeuthen meinen schlechte Sachen "akzeptieren", wie in anerkennen, dass sie existieren und schwer zu ändern sind,

h: aber nicht notwendigerweise den Einsatz zum Ändern fallen zu lassen.

`bb({ eyes:"suspect" });`

b: Dann sollen Therapeuthen *anerkennen* sagen, nicht *akzeptieren*.

`hong({ body:"chin", eyes:"annoyed" });`

h: Ja, wenn ich so drüber nachdenke, "akzeptieren" ist irgendwie verwirrend.

`bb({ eyes:"closed", mouth:"narrow" });`

b: Naja, ich *erkenne das an*.

(#act4_something_else)

# act4_bad_accept_approve

`bb({ eyes:"angry" });`

b: Ich mein', ist es *gut*, dass wir kaputt sind, oder wie? Nein!

`bb({ eyes:"angry_r", body:"one_up" });`

b: Alle diese verdammten Hollywood Drehbuchautoren, die geistige Krankheiten romantisieren sind voller Mist!

`bb({ eyes:"angry", body:"two_up" });`

b: Eine geistige Störung zu haben ist ^scheiße^! Es raubt Leuten ihr *Leben*! Warum sollten wir das "akzeptieren"?!

`bb({ body:"normal" });`

h: Ich denke Therapeuten meinen "akzeptieren" wie in "sei geduldig mit ihnen".

```
hong({ body:"one_up" });
bb({ eyes:"normal" });
```

h: So wie, wenn du dich Treibsand abrackerst, rauszukommen, sinkst du nur noch schneller-

h: und die Lösung ist sich geduldig flach hinzulegen,

`hong({ eyes:"surprise" });`

{{if _.INJURED}}
h: Gegen dich zu kämpfen, meine Angst, hat mich dazu gebracht, von einem Dach zu springen.
{{/if}}

{{if !_.INJURED}}
h: Gegen dich zu kämpfen, meine Angst, hat mich fast dazu gebracht, von einem Dach zu springen.
{{/if}}

`hong({ body:"normal", eyes:"normal" });`

h: Stattdessen ist die Lösung das zu machen, was wir gerade tun-

h: nicht kämpfen, sondern geduldig mit einander zu sein.

`bb({ eyes:"annoyed" });`

b: Dann sollten sie *das* sagen, statt irgendein problematisches Wort wie "akzeptieren".

`hong({ body:"chin", eyes:"annoyed" });`

h: Hm ja, wenn ich so drüber nachdenke, "akzeptieren" ist irgendwie ^scheiße^.

`bb({ eyes:"closed_annoyed", mouth:"narrow" });`

b: Ich akzeptiere "akzeptieren" nicht.

(#act4_something_else)

# act4_bad_accept_literally

`bb({ eyes:"sad", body:"one_up" });`

b: Aber wir *wissen* das bereits, du solltest mich nicht beim Wort nehmen!

`bb({ eyes:"sad_u", body:"two_up" });`

b: Das ganze *Problem* ist ja, dass ich dir helfen will, aber so schlecht mit Worten bin!

`bb({ eyes:"sad", body:"normal" });`

h: Ich denke Therapeuthen meinen seine Emotionen "akzeptieren" wie in "bekämpf oder ignorier sie nicht".

`hong({ eyes:"surprise", body:"one_up" });`

h: Dir zuzuhören, *mit* dir zu arbeiten, aber nicht alles was du sagst, 100% wörtlich zu nehmen.

```
hong({ eyes:"normal", body:"normal" });
bb({ eyes:"annoyed", mouth:"normal" });`
```

b: Dann sollten Therapeuthen *das* sagen, statt irgendein verwirrendes Wort wie "akzeptieren".

`hong({ body:"chin", eyes:"annoyed" });`

h: Ich nehm' an, die sind auch ziemlich schlecht mit Worten.

(#act4_something_else)




# act4_something_else

```
bb({ body:"normal", mouth:"normal", eyes:"normal" });
hong({ body:"normal", mouth:"normal", eyes:"normal" });
```

{{if _.a4_fears_discussed==1}}
h: Wie auch immer, irgend was anderes, worüber du reden willst?
{{/if}}

{{if _.a4_fears_discussed==2}}
h: Also, liegt dir irgendwas anderes schwer auf dem Herzen?
{{/if}}

{{if _.a4_fears_discussed==3}}
(#act4_something_else_2)
{{/if}}

{{if _.a4_talked_about_harm!=true}}
[Ich hab' Angst, verletzt zu werden.](#act4_harm)
{{/if}}

{{if _.a4_talked_about_alone!=true}}
[Ich hab' Angst, allein zu bleiben.](#act4_alone)
{{/if}}

{{if _.a4_talked_about_bad!=true}}
[Ich hab' Angst, *schlecht* zu sein.](#act4_bad)
{{/if}}

[Ne, es ist erst mal genug.](#act4c_prelude)

# act4_something_else_2

h: Okay, ich denke wir haben erstmal über alle unsere Ängste geredet.

b: Ja, es gibt nur drei Ängste.

h: Jo, ganz genau drei.

b: Praktisch.

(#act4c)

# act4c_prelude

h: Gutes Gespräch, Partner.

(#act4c)

# act4c

```
Game.clearText();
music(null,{fade:3});
bb({body:"normal", eyes:"normal", mouth:"normal", MOUTH_LOCK:true},0);
hong({body:"normal", eyes:"normal", mouth:"normal"},0);
```

b: ...

`hong({MOUTH_LOCK:true},0)`

h: ...

`bb({eyes:"annoyed_d"})`

b: Das hier ist nicht irgendein *Spiel*, weißt du.

`bb({eyes:"angry_d", body:"one_up"})`

b: Eine gesunde Beziehung zu seinen Emotionen aufzubauen ist nicht so einfach, wie Knöpfe zu drücken.

`bb({eyes:"sad", body:"normal"})`

b: *Können* wir wirklich miteinander auskommen?

b: *Können* wir zusammenarbeiten, als Team?

`hong({eyes:"sad", body:"one_up"})`

h: Naja,

```
hong({eyes:"surprise_l"});
bb({eyes:"normal"});
```

a: E-entschuldigung...

```
Game.clearText();
publish("act4-in-2");
music('campus', {volume:0.5, fade:1});
```

(...2101)

(#act4d)

# act4d

`Game.WORDS_HEIGHT_BOTTOM = 221;`

`publish("act4", ["alshire", 0]);`

a: W-wü-würde es dir etwas ausmachen, wenn ich mich zum Essen zu dir setze?

`publish("act4", ["alshire", 1]);`

{{if _.TOP_FEAR=="harm"}}
s: *Das* ist dein Schwarm? Warum sitzt der alleine wie ein Psycho Serienmörder?
{{/if}}

{{if _.TOP_FEAR=="alone"}}
s: Hast du gerade wirklich deinen Schwarm gefragt, ob wir neben ihm sitzen können?

s: Weißt du, wie *bedürftig* wir klingen?!
{{/if}}

{{if _.TOP_FEAR=="bad"}}
s: *Das* ist dein Schwarm? Wir haben seine Ruhe und Frieden gestört! Wir sind so eine Belastung!
{{/if}}

`publish("act4", ["alshire", 2]);`

a: I- Ich meine- es, es ist okay wenn nicht, ich wollte nur...

`publish("act4", ["alshire", 3]);`

`Game.OVERRIDE_CHOICE_SPEAKER = "h2"`

[Warte, warst du nicht auf der Party?](#act4d_recognition) `publish("act4", ["hong_to_alshire",1])`

[Ja, natürlich! Setz dich.](#act4d_yes) `publish("act4", ["hong_to_alshire",2])`

[Sorry, ich brauch' gerade Zeit alleine.](#act4d_no) `publish("act4", ["hong_to_alshire",8])`

# act4d_recognition

`publish("act4", ["hong_to_alshire",2]);`

h2: Ja du warst auf der Couch! Bei der ersten Party wo ich war...

`publish("act4", ["hong_to_alshire",10]);`

{{if _.a2_ending=="fight"}}
h2: Wo ich eine Panikattacke hatte und die Gastgeberin geschlagen habe.
{{/if}}

{{if _.a2_ending=="flight"}}
h2: Wo ich eine Panikattacke hatte und heulend rausgelaufen bin.
{{/if}}

```
publish("act4", ["hong_to_alshire", 0]);
publish("act4", ["bb_to_alshire", _.INJURED ? 3 : 1]);
```

b: Warte, Mensch. Wir machen sie unbehaglich.

```
publish("act4", ["hong_to_alshire", 3]);
publish("act4", ["bb_to_alshire", _.INJURED ? 2 : 0]);
```

h2: Oh, ich will dich nicht in Verlegenheit bringen!

`publish("act4", ["hong_to_alshire",4]);`

h2: Ich erinner' mich nur an ein freundliches Gesicht, das ist alles.

```
publish("act4", ["hong_to_alshire",5]);
publish("act4", ["alshire", 4]);
```

{{if _.TOP_FEAR=="harm"}}
s: AHHHHH ICH WUSSTE ES! ER IST EIN GEFÄHRLICHER PANIK-GETRIEBENER PSYCHO!
{{/if}}

{{if _.TOP_FEAR=="alone"}}
s: AAHHH DER ERSTE EINDRUCH VON UNS IST "HAT MEIN TRAUMA MITBEKOMMEN"! DAS HEISST ER HASST UNS!
{{/if}}

{{if _.TOP_FEAR=="bad"}}
s: AAAAHH WIR HABEN IHN AN EIN SCHLIMMES EREIGNIS ERINNERT! UNSERE BLOSSE ANWESENHEIT VERLETZT!
{{/if}}

(#act4e)

# act4d_yes

```
publish("act4", ["hong_to_alshire", 5]);
publish("act4", ["bb_to_alshire", _.INJURED ? 3 : 1]);
```

b: Warte, Mensch. Sie scheint unbehaglich.

```
publish("act4", ["hong_to_alshire", 6]);
publish("act4", ["bb_to_alshire", _.INJURED ? 2 : 0]);
```

h2: Hey, ich will dir natürlich keinen Druck machen!

`publish("act4", ["hong_to_alshire", 4]);`

h2: Ich sag bloß, du kannst hier gerne sitzen, wenn du willst.

```
publish("act4", ["hong_to_alshire", 5]);
publish("act4", ["alshire", 4]);
```

{{if _.TOP_FEAR=="harm"}}
s: ER IST *ZU* FREUNDLICH! WIE TED BUNDY, DER SERIENMÖRDER!
{{/if}}

{{if _.TOP_FEAR=="alone"}}
s: DER IST NUR HÖFLICH! NIEMAND WILL *WIRKLICH* IN UNSERER NÄHE SEIN!
{{/if}}

{{if _.TOP_FEAR=="bad"}}
s: AHHH WIR MACHEN ANDERE IMMER PEINLICH! WIR SIND SO EIN SCHANDFLECK!
{{/if}}

(#act4e)

# act4d_no

```
publish("act4", ["hong_to_alshire", 9]);
publish("act4", ["bb_to_alshire", _.INJURED ? 3 : 1]);
```

b: Warte mal, Mensch - wir machen es unangenehm für sie.

```
publish("act4", ["hong_to_alshire", 3]);
publish("act4", ["bb_to_alshire", _.INJURED ? 2 : 0]);
```

h2: Oh, ich will nicht unhöflich sein!

`publish("act4", ["hong_to_alshire", 6]);`

h2: Ich brauche gerade nur ein bisschen Zeit, meine Emotionen zu sortieren. Bitte nimm es nicht persönlich.

```
publish("act4", ["hong_to_alshire", 7]);
publish("act4", ["alshire", 4]);
```

{{if _.TOP_FEAR=="harm"}}
s: WELCHE KRANKEN, PERVERSEN GEDANKEN MUSS DER SORTIEREN?! WELCHE DUNKLEN GELÜSTE HAT DIESER PSYCHO?!
{{/if}}

{{if _.TOP_FEAR=="alone"}}
s: WIR WURDEN PERSÖNLICH ZURÜCKGEWIESEN! WIR WERDEN NIE GELIEBT WERDEN!
{{/if}}

{{if _.TOP_FEAR=="bad"}}
s: WIR HABEN EINEN EMOTIONALEN PROZESS UNTERBROCHEN! JETZT WIRD ER FÜR IMMER TRAUMATISIERT SEIN UND NUR WEGEN UNS!
{{/if}}

(#act4e)

# act4e

```
Game.WORDS_HEIGHT_BOTTOM = 195;
publish("act4", ["alshire", 6]);
```

s: LAUF LAUF LAUF LAUF LAUF LAUF LAUF LAUF LUAF LAUF LAUF LAUF

```
Game.clearText();
publish("act4", ["hong_to_alshire", 0]);
publish("act4", ["alshire", 10]);
sfx("pop");
```

(...1001)

```
publish("act4", ["alshire", 11]);
sfx("alshire_run");
```

(...2601)

```
publish("act4-out-3");
Game.WORDS_HEIGHT_BOTTOM = -1; /* reset */
```

(...1201)

`publish("act4-jumpcut-hong");`

h: Huch. Das war seltsam. Ich frag' mich, was in ihrem Kopf abgegangen ist.

`publish("act4", ["hong_closer", 2]);`

h: Wie auch immer, was hast du gesagt?

```
publish("act4", ["hong_closer", 1]);
publish("act4", ["bb_closer", 6]);
```

b: Ähm, ich hab's vergessen. Irgendwas über Teams und Arbeit?

```
publish("act4", ["bb_closer", 0]);
publish("act4", ["hong_closer", 3]);
```

h: ¯\_(ツ)_/¯

```
publish("act4", ["hong_closer", 1]);
publish("act4", ["bb_closer", 4]);
```

b: Man sagt, man sollte "Frieden mit seinen Emotionen machen", als wären seine Emotionen *Kriegsverbrecher*.

`publish("act4", ["bb_closer", 7]);`

b: Aber ich will, dass wir *mehr* machen, als bloß Frieden zu schließen!

b: Ich will, dass wir uns *verbünden!*

`publish("act4", ["bb_closer", 3]);`

b: Ich will ein guter Wachhund sein. So wie Hunger und Durst bereits Alarm-Signale für deine körperlichen Bedürfnisse sind,

`publish("act4", ["bb_closer", 8]);`

b: will ich dein Alarm für *psychologische* Bedürfnisse sein - deine Bedürfnisse für Sicherheit, Zugehörigkeit, Güte.

`publish("act4", ["bb_closer", 1]);`

b: Aber... ich bin schlecht in meinem Job, also brauche ich dich, um mich zu trainieren.

`publish("act4", ["bb_closer", 4]);`

b: Ich bin weder "immer richtig", noch "immer irrational". Ich versuche einfach... mein Bestes. Also bitte,

`publish("act4", ["bb_closer", 30]);`

b: Hilf mir, dir zu helfen!

`publish("act4", ["bb_closer", 6]);`

b: Obwohl, einem alten Hund neue Tricks beizubringen wird *eine Weile* dauern. Vielleicht *Jahre.*

`publish("act4", ["bb_closer", 3]);`

b: Und manchmal werde ich rückfällig werden und in alte Angewohnheiten rutschen.

`publish("act4", ["bb_closer", 2]);`

b: Ich werde Schatten anbellen. Ich werde dich mit Worten einschüchtern.

b: Ich werde dir vielleicht sogar Bilder von... Dingen zeigen.

`publish("act4", ["bb_closer", 9]);`

b: Es tut mir Leid! Ich bin ein mitgenommener Straßenhund! Mitgenommene Hunde ^kack^en dir manchmal auf's Bett!

`publish("act4", ["bb_closer", 4]);`

b: Aber wenn du geduldig mit mir bist... und einfach bei mir sitzen bleibst...

`publish("act4", ["bb_closer", 8]);`

b: Vielleicht kannst du diesen Wolf zähmen.

`publish("act4", ["bb_closer", 0]);`

`Game.clearText();`

(...1000)

`Game.OVERRIDE_CHOICE_SPEAKER = "h"`

[Guter Hund.](#act4f-pat-bb) `Game.OVERRIDE_CHOICE_SPEAKER = "h"; publish("act4", ["hong_closer", 2]);`

`Game.OVERRIDE_CHOICE_SPEAKER = "b"`

[Guter Mensch.](#act4f-pat-hong) `Game.OVERRIDE_CHOICE_SPEAKER = "b"; publish("act4", ["bb_closer", 8]);`

# act4f-pat-hong

```
Game.clearText();
publish("hide_tabs");
Game.FORCE_CANT_SKIP = true;
music(null,{fade:0.5});
sfx("youbothwin");
```

```
publish("act4", ["hong_closer", 4]);
publish("act4", ["bb_closer", 13]);
```

(...501)

`publish("act4", ["bb_closer", 14]);`

(...501)

`publish("act4", ["bb_closer", 13]);`

(...501)

`publish("act4", ["bb_closer", 14]);`

(...501)

`publish("act4", ["bb_closer", 13]);`

(...501)

`publish("act4", ["bb_closer", 14]);`

(...6501)

`publish("act4", ["bb_closer", 15]);`

(...1001)

(#act4f)

# act4f-pat-bb

```
Game.clearText();
publish("hide_tabs");
Game.FORCE_CANT_SKIP = true;
music(null,{fade:0.5});
sfx("youbothwin");
```

```
publish("act4", ["hong_closer", 4]);
publish("act4", ["bb_closer", 10]);
```

(...501)

`publish("act4", ["bb_closer", 11]);`

(...501)

`publish("act4", ["bb_closer", 10]);`

(...501)

`publish("act4", ["bb_closer", 11]);`

(...501)

`publish("act4", ["bb_closer", 10]);`

(...501)

`publish("act4", ["bb_closer", 11]);`

(...6501)

`publish("act4", ["bb_closer", 12]);`

(...1001)

(#act4f)

# act4f

```
Game.FORCE_CANT_SKIP = false;
publish("act4", ["bb_closer", 16]);
publish("act4", ["hong_closer", 5]);
```

{{if _.fifteencigs}}
b: AAAAA DU ISST IMMER NOCH ALLEINE FÜNFZEHN ZIGARETTEN AAAAA
{{/if}}

{{if _.parasite}}
b: AAAAA DU BIST IMMER NOCH NICHT PRODUKTIV BEIM ESSEN WIR SIND GESELLSCHAFTS-PARASITEN AAAAA
{{/if}}

{{if _.whitebread}}
b: AAAAA DU ISST IMMER MEHR WEISSBROT AAAAA
{{/if}}

```
publish("act4", ["bb_closer", 18]);
publish("act4", ["hong_closer", 6]);
sfx("yaps", {volume:0.6});
Game.FORCE_CANT_SKIP = true;
Game.WORDS_HEIGHT_BOTTOM = 205;
Game.FORCE_TEXT_DURATION = 90;
Game.FORCE_NO_VOICE = true;
```

b: KLÄFF KLÄFF KLÄFF KLÄFF

(#credits)
