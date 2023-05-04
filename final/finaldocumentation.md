# final documentation

hello rachel. every day i stray further and further from what i understand about music, technology, life, code, and cycles

there is little i have to document because this performance is MINIMAL. *MINIMAL*, RACHEL, AS IN, LIKE 7 LINES OF ITTY BITTY CODE AND A GAL AND A GUITAR. frankly i have no idea how to rehearse this other than blaring tidalcycles through my speakers and just singin' along to it, so that's about all the rehearsal it's gonna get. hooking it up and stuff? no. the mic/guitar doesn't have to be processed through anything so... i think it's okay ............. ?

so, first: the song. (excluding the code) guitar and vocals, it's called Classroom Roadkill. it has existed for some time now, about two years. i wrote it finishing up my freshman year at berklee. (subject matter hint) so having this song in mind, knowing it pretty well, that made it easy to tackle tidalcycles and try to essentially make myself a live backing track. hardest thing: tempo/meter. discovered that that basically does not exist in tidalcycles, perhaps not ideal for backing a song, but. I Tried.

for the livecode part, this is basically the setup:

```
setcps (40/120)

d1 $ n "1" # s "pebbles" # shape sine # gain 0.4
d2 $ scramble 3 $ n "[1 | ~ | 2 | 3 ]" # s "crow"
d3 $ n "1 1 1" # s "reverbkick"
d4 $ n "2 1 3 3 4 6 5 9 7" # s "flick" # gain 0.9 # squiz
d5 $ n "2 1" # s "seawolf" # shape sine
d6 $ n "2 1" # s "outdoor"
```

there will probably be more added by next thursday, but these are the bones of the backing. my plan is also, for the outro, to very quickly delete all lines of code except the first one with one snazzy hand gesture.

basically, i plan to type up these few lines of code, once it's all there, i start singing and playing guitar, and then i delete all lines of code except the first ambiencey one, and thats the show.
