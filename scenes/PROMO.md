# intro

`SceneSetup.intro();`

# intro-play-button

(...51)

[PLAY!](#intro-start) `publish("intro-to-game-1"); Game.OVERRIDE_CHOICE_LINE=true;`

# intro-start

(...500)

`clearText()`

n3: Also, bevor wir anfangen, wie würdest *du* gerne lesen?

`publish("show_options_bottom")`

# intro-start-2

n3: So, jetzt lass uns mit unserer Geschichte beginnen...

```
publish("hide_tabs");
clearText();
```

(...1000)

`publish("intro-to-game-2")`

n2: DAS IST EIN MENSCH

(...600)

`clearText()`

(...300)

`publish("intro-to-game-3")`

# act1

```
SceneSetup.act1();
publish("hide_tabs");
music('battle', {volume:0.5});
```

(...300)

n: UND DAS IST DIE ANGST VON DEM MENSCH

n: _DU_ BIST DIE ANGST

(#act1_normal)


# act1_normal

```
hong({body:"putaway"});
sfx("rustle");
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: Nö. Nein, nada, hör' gar nicht zu. Muss mein Handy checken.

```
sfx("rustle2");
hong({body:"phone1", mouth:"neutral", eyes:"neutral"})
```

n: DEIN JOB IST DEINEN MENSCHEN VOR *GEFAHR* ZU BESCHÜTZEN

`bb({eyes:"look", mouth:"small_lock", body:"fear"})`

b: Huch! Du scrollst auf Twitter um dein Leben! Schon wieder!

```
bb({eyes:"normal", mouth:"normal", body:"normal"});
hong({eyes:"annoyed"});
```

h: Ja, ich frage mich, warum ich micht nicht öfter einfach hinsetze und meinen Gedanken lausche.

`hong({eyes:"neutral"});`

n: SCHNELL, WARN IHN WEGEN EINER *GEFAHR!*

```
bb({eyes:"look"});
```

[Oh nein, schau dir diese schreckliche Nachricht an!](#act1d_news)

[Oh nein, geht dieser Tweet heimlich um *uns?*](#act1d_subtweet)

[Hey, ein GIF von einer Katze, die Milch trinkt](#act1d_milk)

# act1d_milk

`hong({mouth:"smile", eyes:"surprise"});`

h: Heh, ja das ist süß, ich--

```
hong({mouth:"shock", eyes:"shock"});
bb({body:"scream"});
Game.OVERRIDE_TEXT_SPEED = 1.8;
```

b: KATZEN KÖNNEN KEINE MILCH VERDAUEN UND WIR SIND SCHRECKLICHE MENSCHEN, DIE TIERQUÄLEREI GUT FINDEN

(...200)

```
bb({body:"normal", mouth:"normal", eyes:"fear"});
attack("20p", "bad");
publish("hp_show");
```



