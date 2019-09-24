# act3

```
SceneSetup.act3();
Game.WORDS_HEIGHT_BOTTOM = 205;
sfx("cheers");
```

r: Prost!

```
publish("act3",["roofhunter",1]);
publish("act3",["roofhong",1]);
sfx("drinking");
```

(...4001)

```
publish("act3-alpha", ["dizzyhunter",1]);
publish("act3-alpha", ["dizzyhong",1]);
publish("act3",["roofhunter",3]);
publish("act3",["roofhong",3]);
```

h2: *Ah* das ist genau das Richtige.

```
publish("act3",["roofhunter",2]);
publish("act3",["roofhong",2]);
```

R: Weißt du, Kind...

```
publish("act3",["roofhunter",3]);
publish("act3",["roofhong",6]);
```

h2: Genauer gesagt, ist das genau das Richtige für meine Amygdala.

```
publish("act3",["roofhunter",8]);
publish("act3",["roofhong",5]);
```

r: Du erinnerst mich an mich selbst, als ich jünger war.

r: Damals hab ich mich selbst noch von dem Tier in meinem Kopf fertig machen lassen.

```
publish("act3",["roofhunter",9]);
publish("act3",["roofhong",2]);
```

r: Ich bin so dankbar, dass ich was davon weitergeben kann.

r: Lass mich dir zeigen, wie du das Biest genauso besiegen kannst, wie ich meins

```
publish("act3",["roofhunter",2]);
```

r: Hey, kurze Frage: Wahrheit oder Pfl--

```
publish("act3",["roofhunter",3]);
publish("act3",["roofhong",7]);
publish("act3-alpha", ["dizzyhong",0]);
```

h2: PFLICHT!

```
publish("act3-alpha", ["dizzyhong",1]);
publish("act3",["roofhunter",10]);
publish("act3",["roofhong",2]);
```

r: Haha! Gut.

```
publish("act3",["roofhunter",21]);
publish("act3",["roofhong",4]);
```

r: Ok. Siehst du diesen baybyblauen Swimmingpool da unten?

```
publish("act3-alpha", ["dizzyhong",0]);
publish("act3",["roofhunter",11]);
publish("act3",["roofhong",9]);
```

h2: Ja? Sechs Stockwerke weiter unten?

```
publish("act3",["roofhunter",10]);
publish("act3",["roofhong",8]);
```

r: Spring rein.

```
publish("act3",["roofhunter",11]);
publish("act3",["roofhong",10]);
```

h2: ...

```
publish("act3",["roofhong",11]);
```

h2: Warte, was?

```
publish("act3",["roofhong",10]);
publish("act3",["roofhunter",2]);
```

r: Das Tier hat angefangen zu heulen, oder nicht?

```
publish("act3",["roofhunter",23]);
```

R: *Oh neeein es ist gefährlich, mach es niiiicht.*

```
publish("act3",["roofhunter",22]);
```

r: Aber das ist genau, warum wir todesmutigen Nervenkitzel brauchen! Party Hard! Carpe diem! Zieh ne Line aus nem N^uttenarsch^, #YOLO!

```
publish("act3",["roofhunter",10]);
```

r: Zeig diesem Tier, dass sein Rumgezicke uns 'n feuchten Dreck schert! Spring rein.

```
publish("act3",["roofhunter",11]);
publish("act3",["roofhong",13]);
```

h2: Ähm, aber manchmal, äh... hat Angst seine Berechtigung...

```
publish("act3",["roofhunter",5]);
publish("act3",["roofhong",12]);
music(null, {fade:2});
```

r: ...

```
publish("act3-alpha", ["dizzyhunter",0]);
publish("act3",["roofhunter",6]);
publish("act3",["dd",1]);
```

r: Sorry, bist du wirklich auf Achtsamkeits-Masche reingefallen, dass es *gut* sein soll, wenn man sich schlecht fühlt?

```
publish("act3",["roofhunter",17]);
```

r: Freude ist das Gegenteil Schmerzen. Also kannst du Freude ^scheiße^-nochmal hernehmen, um den Schmerz zu bekämpfen!

```
publish("act3",["roofhunter",18]);
```

r: Wie kann es sein, dass diese Silicon Valley Pseudo-Buddhisten den ^Scheiß'^ nicht erkennen?!

```
publish("act3",["roofhunter",6]);
```

r: Kind, ich weiß, dass *du* weißt, dass dieses Tier Leute wie uns *verletzt*.

r: Es *foltert* Leute wie uns.

```
publish("act3",["roofhunter",19]);
```

r: Es ist nicht unser Freund. Es ist ein tollwütiges Biest, das entweder *eingeschläfert* werden muss,

```
publish("act3",["roofhunter",20]);
```

r: Oder eine *Kugel in den Kopf verdient*.

```
publish("act3",["roofhunter",27]);
```

r: Oder du lässt es einfach gewinnen.

```
publish("act3",["roofhunter",31]);
publish("act3",["roofhong",14]);
publish("act3",["dd",2]);
```

h2: Nein. Du liegst falsch.

```
publish("act3",["roofhunter",13]);
publish("act3",["roofhong",15]);
music('battle_dark', {volume:1.0}, function(){
	music('battle_dark_loop');
});
```

h2: Ich werde es nicht gewinnen lassen.

```
publish("act3",["roofhunter",25]);
publish("act3-alpha", ["roofhong",0]);
publish("act3-alpha", ["transition",1]);
publish("act3",["dd",6]);
```

r: ^Scheiße^ ja! Ich glaub an dich, Schätzchen! Bring es um! <3

(#act3a)



# act3a

```
Game.clearText();
publish("act3-out");
Game.WORDS_HEIGHT_BOTTOM = -1; /* reset */
_.act3_bb_body = 1;
```

(...1500)

```
publish("hp_show");
```

b: nein nein nein nein nein nein

n: DIESES KAPITEL HAT ZWEI MÖGLICHE ENDEN. EINES DAVON IST *SEHR, SEHR SCHLECHT.*

b: NEIN NEIN NEIN NEIN NEIN NEIN NEIN NEIN NEIN

n: WÄHLE WEISE. BESCHÜTZE DEINEN MENSCHEN

`bb({ eyes:"oh_crap", mouth:"normal_talk", MOUTH_LOCK:true });`

b: AAAAAAAAAAAAAAAAAA

`bb({ mouth:"normal" });`

n: VIEL GRLÜCK

```
Game.clearText();
bb({ eyes:"start" });
```

[Mensch, du könntest hier tatsächlich STERBEN!](#act3a_harm) `Game.OVERRIDE_CHOICE_LINE=true`

[Das ist dumm und selbstzerstörerisch!](#act3a_bad) `Game.OVERRIDE_CHOICE_LINE=true`

[Diese Spinner sind nicht wirklich deine Freunde!](#act3a_alone) `Game.OVERRIDE_CHOICE_LINE=true`

# act3a_harm

`bb({ MOUTH_LOCK:true, mouth:"normal_talk" });`

b: M--

(#act3a_after)

# act3a_alone

`bb({ MOUTH_LOCK:true, mouth:"normal_talk" });`

b: D--

(#act3a_after)

# act3a_bad

`bb({ MOUTH_LOCK:true, mouth:"normal_talk" });`

b: D--

(#act3a_after)

# act3a_after

```
hong({body:"drink"});
bb({body:"attacked"});
attackBB("32p");
_.act3_bb_body++;
```

(...2000)

```
hong({ body:"normal" });
bb({ body:"normal_"+_.act3_bb_body, mouth:"normal", eyes:"normal" });
```

h: Weißt du, ich hätte dir ja geglaubt... wenn du das nicht schon 1000-mal versucht hättest.

h: Du hast zu oft falsch Alarm geschlagen.

```
bb({ eyes:"sad" });
```

`Game.OVERRIDE_CHOICE_SPEAKER = "fear_harm"`

[](#act3_fork) `_.SPECIAL_ATTACK="harm"; Game.OVERRIDE_CHOICE_LINE=true`

`Game.OVERRIDE_CHOICE_SPEAKER = "fear_alone"`

[](#act3_fork) `_.SPECIAL_ATTACK="alone"; Game.OVERRIDE_CHOICE_LINE=true`

`Game.OVERRIDE_CHOICE_SPEAKER = "fear_bad"`

[](#act3_fork) `_.SPECIAL_ATTACK="bad"; Game.OVERRIDE_CHOICE_LINE=true`


# act3_fork

```
Game.clearText();
bb({body:"special_attack"});
sfx("charging");
Game.FORCE_CANT_SKIP = true;
```

(...1001)

```
Game.FORCE_CANT_SKIP = false;
hong({body:"drink"});
bb({body:"attacked"});
attackBB("32p");
_.act3_bb_body++;
```

(...2000)

```
hong({ body:"normal" });
bb({ body:"normal_"+_.act3_bb_body, mouth:"normal", eyes:"normal" });
```

h: Das hast du auch schon versucht.

b: Mensch, bitte...

`hong({ eyes:"look_right" });`

h: Oh, es es *tut mir leid*, dass Pharma-Konzerne meine Selbstverschreibung nicht toll finden.

h: Hör zu ^Arschloch^, wir haben *alle* Möglichkeiten, dich verdammt noch mal Schweigen zu lassen.

`hong({ body:"look_up", eyes:"look_up" });`

h: Manche Leute stürzen sich geradezu in Arbeit.

`hong({ body:"look_down", eyes:"look_down" });`

h: Manche Leute stürzen sich in Sex, Drogen, oder das Aktualisieren ihrer Facebook-Timeline.

`hong({ body:"normal", eyes:"look_right" });`

h: Manche Leute stürzen sich in Beziehungen mit anderen.

`hong({ eyes:"angry" });`

h: Und ich stürz mich halt in diesen Swimming Pool.

[Du bist betrunken und das ist SECHS STOCKWERKE TIEF](#act3_bad_1_harm)

[Verdammt, so dankst du mir?!](#act3_bad_1_insult) `bb({eyes:"angry"});`

[Okay, ich geb's zu. Ich hab ver^kackt^.](#act3_good_1) `bb({mouth:"sorry", eyes:"sorry_down"});`

# act3_bad_1_harm

b: Selbst, wenn du im Wasser landest, die Oberflächenspannung wird deine Rippen brechen und dir *mindestens* eine Kopferschütterung geben!

h: Phhh.

```
hong({body:"drink"});
bb({body:"attacked"});
attackBB("32p");
_.act3_bb_body++;
```

(...2000)

```
hong({ body:"normal", mouth:"angry", eyes:"angry" });
bb({ body:"normal_"+_.act3_bb_body, mouth:"normal", eyes:"normal" });
```

h: Ich hab ein YouTube Video von 'nem Russen gesehen, der das gemacht hat.

(#act3_bad_2)

# act3_bad_1_insult

`hong({ eyes:"look_right" });`

h: Ich- Bitte was, ich soll dir *danken?!*

`bb({ eyes:"angry" });`

b: Das ist genau warum ich *existiere!* Weil man Menschen nicht vertrauen kann, auf sich selbst aufzupassen!

b: Ich hab' mein ganzes Leben lang versucht, deinen dummen Arsch zu beschützen und jetzt willst du einfach--

```
hong({body:"drink"});
bb({body:"attacked"});
attackBB("32p");
_.act3_bb_body++;
```

(...2000)

```
hong({ body:"normal", mouth:"angry", eyes:"angry" });
bb({ body:"normal_"+_.act3_bb_body, mouth:"normal", eyes:"normal" });
```

(#act3_bad_2)

# act3_good_1

`hong({ body:"laugh_1" })``

h: ha.

`hong({ body:"laugh_2" })``

h: hahahaha

`hong({ body:"laugh_3" })``

h: HAHAHAHAHAHA

```
bb({ eyes:"sorry"});
hong({ body:"yell_1", mouth:"yell", eyes:"blank" });
```

h: Oh, WOW. Das ist die größte ver^fickte^ Untertreibung des Jahrhunderts!

`hong({ body:"yell_2" });`

h: Ja, du verfaulter blutbedeckter Haufen ^Scheiße^! Du hast sowas von ver^kackt^!

`hong({ body:"normal", mouth:"angry", eyes:"angry" });`

h: Irgendwelche anderen Anmerkungen, du Blitzmerker?

[Dich an mir zu rächen, ist nicht die Lösung!](#act3_good_1_fail_revenge) `bb({ body:"normal_"+_.act3_bb_body, mouth:"normal", eyes:"normal" });`

[Dieses Mal hab ich *tatsächlich* recht!](#act3_good_1_fail_harm) `bb({ body:"normal_"+_.act3_bb_body, mouth:"normal", eyes:"normal" });`

[Ich hab' dir wehgetan.](#act3_good_2a)


# act3_good_1_fail_revenge

b: Du musst ein gesunderes Verhätnis zu deinen Emotionen haben. Statt sie zu unterdr--

```
hong({body:"drink"});
bb({body:"attacked"});
attackBB("32p");
_.act3_bb_body++;
```

(...2000)

```
hong({ body:"normal", mouth:"angry", eyes:"angry" });
bb({ body:"normal_"+_.act3_bb_body, mouth:"normal", eyes:"normal" });
```

(#act3_bad_2)



# act3_good_1_fail_harm

b: Also bitte, nimm die Flasche runter und lass uns--

```
hong({body:"drink"});
bb({body:"attacked"});
attackBB("32p");
_.act3_bb_body++;
```

(...2000)

```
hong({ body:"normal", mouth:"angry", eyes:"angry" });
bb({ body:"normal_"+_.act3_bb_body, mouth:"normal", eyes:"normal" });
```

(#act3_bad_2)




# act3_bad_2

`bb({ eyes:"sad" });`

b: Bitte... mach es nicht...

h: Deine Energieleiste da sieht furchtbar leer aus, Wolf.

h: Wenn ich du wär', würd' ich mir meine nächsten Worte sehr gut überlegen.

`bb({ eyes:"normal" });`

[Gut. Ich hör' auf dich zu beschützen.](#act3_bad_2_jump) `bb({ mouth:"ignore", eyes:"ignore" });`

[Ich hab' die ganze Zeit recht gehabt.](#act3_bad_2_right)

[Es tut mir leid.](#act3_good_2b) `bb({mouth:"sorry", eyes:"sorry_down"});`


# act3_bad_2_jump

b: So, spring doch. Kümmert mich doch nicht.

`hong({ eyes:"look_right", mouth:"normal", MOUTH_LOCK:true });`

h: ...

```
hong({ eyes:"less_angry", mouth:"normal" });
bb({ eyes:"ignore_oh_crap" });
```

h: Okay dann. Und hopp.

```
bb({ mouth:"normal", eyes:"oh_crap" });
Game.OVERRIDE_TEXT_SPEED = 2;
```

b: WARTE NEIN DAS SOLLTE UMGEKEHRTE PSYCHOLOGIE SEIN DU SOLLTEST DAS *GEGENTEIL*--

(#act3_bad_3)



# act3_bad_2_right

`bb({ eyes:"angry" });`

b: Du bringst dich gerade *aktiv* in Gefahr. Deine sogenannten *Freunde* benutzen dich. Und *du* benutzt deine sogenannten Freunde.

`bb({ eyes:"sad" });`

b: Also bitte, Mensch... warum glaubst du mir nicht?!

h: Weil du *mir* nie geglaubt hast.

(#act3_bad_3)


# act3_bad_2_terrible

`bb({ eyes:"angry" });`

b: Andere Wachwölfe haben Menschen, die sich tatsächlich Zeit nehmen, sie geduldig zu trainieren, mit ihnen gemeinsam *lernen*,

b: anstatt ihre Wachwölfe zu hassen, weil sie einen beschützen wollen!

b: Also, warum kannst du nicht einfach--

`bb({ eyes:"normal" });`

h: Be^schissenste^ Antwort aller Zeiten.

(#act3_bad_3)



# act3_bad_3

```
music(null);
hong({body:"drink"});
bb({body:"attacked"});
publish("bb_STOP_VIBRATING");
attackBB("100p");
```

(...2000)

```
hong({ body:"normal", mouth:"normal", eyes:"normal" });
bb({ body:"dead" });
```

(...999)

h: *"Das einzige, was du fürchten musst, ist das Leben selbst."*

`hong({ body:"look_up", mouth:"happy", eyes:"blank" });`

h: *"Don't worry, be happy!"*

`hong({ body:"normal", mouth:"normal", eyes:"normal" });`

h: All die weisen Leute unserer Zeit sind sich einig:

h: negative Emotionen sind *schlecht!*

`hong({ eyes:"less_angry" });`

h: *Ach echt?* Heißen sie deshalb vielleicht *negativ?!*

b: Mensch... bitte...

`hong({ eyes:"normal" });`

h: Vor 'ner Weile hab' ich gesagt: “Ich will einfach von all diesem Schmerz befreit sein.”

h: Mein Wunsch wurde erfüllt. Ich fühle weder Schmerz, noch Unbehagen, noch Angst...

h: Ich fühle rein gar nichts mehr.

`_.a3_ending = "jump";`

(#act3_end)



# act3_good_2a

`bb({mouth:"sorry", eyes:"sorry_down"});`

b: Ich war so versessen damit, sicherzugehen, dass dir nichts wehtut, dass ich nicht realisiert habe--

b: dass *Ich* deine Schmerzen verursacht habe.

```
bb({ eyes:"sorry"});
hong({ body:"yell_2", mouth:"yell", eyes:"blank" });
```

H: KEIN. SCH^EISS^.

`hong({ body:"yell_1" });`

h: ^GOTTVERDAMMT^. Hast du wirklich so lang gebraucht, um das endlich rauszufinden?!

`hong({ body:"cry", mouth:"cry", eyes:"blank" });`

h: Du hättest uns so viele Sorgen ersparen können, du großer flauchiger Dumkopf.

h: Warum hast du das bloß nicht früher kapiert?...

`_.apologized_for_hurt = true;`

(#act3_good_2q)



# act3_good_2b

`hong({ body:"normal", mouth:"angry", eyes:"look_right" });`

h: ...es tut dir *leid.*

`hong({ eyes:"angry", MOUTH_LOCK:true });`

h: ...

h: *Was* tut dir leid?

(#act3_good_2q)


# act3_good_2q

`bb({mouth:"sorry", eyes:"sorry"});`

{{if _.apologized_for_hurt}}
(#act3_good_2q_already_apologized)
{{/if}}

{{if !_.apologized_for_hurt}}
(#act3_good_2q_not_already_apologized)
{{/if}}


# act3_good_2q_already_apologized

`hong({ body:"normal", mouth:"angry", eyes:"less_angry" });`

[Ich war ein schlechter Beschützer.](#act3_good_3_protector)

[Ich hab' dich nicht respektiert.](#act3_good_3_respect)

[Es tut mir leid.](#act3_good_4)


# act3_good_2q_not_already_apologized

`hong({ body:"normal", mouth:"angry", eyes:"angry" }, 0);`

[Ich hab' einen schrecklichen Menschen!](#act3_bad_2_terrible) `bb({mouth:"normal", eyes:"normal"})`

[Ich hab' dich nicht respektiert.](#act3_good_3_respect)

[Ich hab' dir wehgetan.](#act3_good_3_hurt)



# act3_good_3_protector

`bb({eyes:"sorry_down"});`

b: Es ist meine Pflicht, dich vor *echter* Gefahr zu warnen, aber ich hab Autos und Briefträger angebellt.

`bb({eyes:"sorry_up"});`

b: Ich hab Schatten angebellt. So viel gebellt. 

`bb({eyes:"sorry"});`

b: Es macht nur Sinn, wenn du mir einen Maulkorb anlegen willst.

`bb({eyes:"sorry_down"});`

b: Es tut mir leid.

(#act3_good_4)



# act3_good_3_respect

`bb({eyes:"sorry_down"});`

b: Ich hätte *dein* treuer Wachhund sein sollen, aber ich hab' mich verhalten, als müsstest du *mir* gehorchen.

`bb({eyes:"sorry_up"});`

b: Es gibt einen Unterschied zwischen einem Beschützer und einem Gefängniswärter und ich hab's zu weit getrieben.

`bb({eyes:"sorry_down"});`

b: Es tut mir leid.

(#act3_good_4)



# act3_good_3_hurt

`bb({eyes:"sorry_down"});`

b: Ich war so versessen darauf, dich davor zu bewahren, verletzt zu werden, dass ich nie realisiert habe, dass *ich* dich verletzt habe

`bb({eyes:"sorry_up"});`

b: Ich war ein schlechter Hund.

`bb({eyes:"sorry_down"});`

b: Es tut mir leid.

(#act3_good_4)


# act3_good_4

```
music(null,{fade:3});
hong({ eyes:"less_angry", MOUTH_LOCK:true },0);
```

h: ...

```
hong({ body:"stop", mouth:"stop", eyes:"blank" });
```

h: Ja, naja, das hier war eh ne Dumme Idee.

h. Ich hab' das nur gemacht, um dich fertig zu machen, und, naja, ich hab' dich fertig gemacht

h: Lass uns einfach sagen, dieses Mal haben wir Gleichstand, okay?

```
bb({ mouth:"sorry", eyes:"sorry" });
bb({ MOUTH_LOCK:true });
```

b: ...

b: Okay.

h: Okay.

n: *GLEICHSTAND*

`_.a3_ending = "walkaway";`

(#act3_end)









# act3_end

```
Game.clearText();
publish("act3-in");
publish("hp_hide");
Game.FORCE_CANT_SKIP = true;
```

{{if _.a3_ending=="walkaway"}}
(#act3_walkaway)
{{/if}}

{{if _.a3_ending=="jump"}}
(#act3_jump)
{{/if}}






# act3_walkaway

```
publish("start-walkaway-anim");
Game.WORDS_HEIGHT_BOTTOM = 205;
```

(...3501)

```
sfx("bottle_toss");
publish('hong-next');
publish("act3",["roofhunter",7]);
```

(...667)

```
publish("act3",["dd",4]);
publish("act3",["roofhunter",26]);
publish('hong-next');
sfx("concrete_step1");
```

(...667)

```
publish('hong-next');
sfx("concrete_step2");
```

(...667)

```
publish('hong-next');
publish("act3",["roofhunter",27]);
```

`Game.FORCE_CANT_SKIP = false;`

r: Oh, *komm schon*. Nach allem, was dieses Tier dir angetan hat, *gibst du einfach auf?*

r: Was ist falsch, Kind? Hast du *Angst?*

```
publish('hong-next');
publish("act3",["roofhunter",26]);
```

h2: Ja.

h2: Ich habe Angst.

`publish('hong-next')`

h2: Und das ist okay!

`publish('hong-next')`

h2: Es ist okay, Angst zu haben.

`publish('hong-next')`

(...500)

```
Game.clearText();
Game.FORCE_CANT_SKIP = true;
```

(...1167)

```
publish('hong-next');
```

(...833)

```
publish('hong-next');
sfx("rustle2");
```

(...1333)

```
publish('hong-next');
publish("act3",["dd",5]);
publish("act3",["roofhunter",31]);
sfx("concrete_step4");
```

(...667)

```
publish('hong-next');
sfx("concrete_step1");
```

(...667)

```
publish('hong-next');
sfx("door");
```

(...1333)

```
publish('hong-next');
sfx("concrete_step2");
```

(...501)

```
publish('hong-next');
Game.FORCE_CANT_SKIP = false;
sfx("lock_door");
publish("act3",["roofhunter",32]);
```

(...2001)

```
publish("act3",["roofhunter",33]);
```

r: Hat der gerade die Tür abgeschlossen?

```
Game.clearAll();
_.INJURED = false;
Game.WORDS_HEIGHT_BOTTOM = -1;
```

(...2000)

(#act4)




# act3_jump

```
publish("start-jump-anim");
Game.FORCE_TEXT_Y = 300;
```

(...2001)

```
publish('hong-next');
sfx("bottle_toss");
```

(...833)

```
sfx("concrete_step1");
sfx("claps");
publish('hong-next');
publish("act3",["dd",4]);
publish("act3",["roofhunter",28]);
```
(...125)

`publish("act3",["roofhunter",29]);`

(...125)

`publish("act3",["roofhunter",28]);`

(...125)

`publish("act3",["roofhunter",29]);`

(...125)

```
sfx("concrete_step2");
publish('hong-next');
publish("act3",["roofhunter",28]);
```

(...125)

`publish("act3",["roofhunter",29]);`

(...125)

`publish("act3",["roofhunter",28]);`

(...125)

`publish("act3",["roofhunter",29]);`

(...125)

```
sfx("concrete_step3");
publish('hong-next');
publish("act3",["dd",5]);
publish("act3",["roofhunter",34]);
```

(...1167)

```
sfx("rustle2");
publish('hong-next');
```

(...1001)

`publish('hong-next')`

b: nein...

(...501)

`Game.clearText();`

`publish('hong-next')`

(...1333)

```
sfx("quack");
publish('hong-next');
```

(...1333)

`publish('hong-next')`

b: nein nein nein

(...501)

`Game.clearText();`

`publish('hong-next')`

(...2001)

```
sfx("rustle2");
publish('hong-next')
```

(...501)

```
sfx("concrete_step1");
publish('hong-next');
publish("act3",["dd",4]);
publish("act3",["roofhunter",30]);
```

(...167)

```
sfx("concrete_step2");
publish('hong-next');
```

(...167)

```
sfx("concrete_step3");
publish('hong-next');
publish("act3",["dd",2]);
publish("act3",["roofhunter",15]);
```

(...167)

```
sfx("bottle_slip");
publish('hong-next');
publish("act3",["dd",3]);
publish("act3",["roofhunter",16]);
```

(...833)

```
sfx("rustle");
publish('hong-next');
```

(...167)

`publish('hong-next')`

(...167)

```
publish('hong-next');
Game.FORCE_TEXT_Y = 325;
Game.OVERRIDE_FONT_SIZE = 50;
```

b: NEIN!

(...400)

```
Game.WORDS_HEIGHT_BOTTOM = -1;
Game.FORCE_TEXT_Y = -1;
Game.clearText();
publish("act4-injury-show");
publish("hide_tabs");
```

(...2000)

```
sfx("hospital1");
publish("act4-injury", [1]);
```

(...4000)

```
stopAllSounds();
publish("act4-injury", [0]);
```

(...2000)

```
sfx("hospital2");
publish("act4-injury", [2]);
```

(...4000)

```
stopAllSounds();
publish("act4-injury", [0]);
```

(...2000)

```
sfx("hospital3");
publish("act4-injury", [3]);
```

(...8000)

```
stopAllSounds();
publish("act4-injury", [0]);
```

(...5500)

`_.INJURED = true;`

(#act4)
