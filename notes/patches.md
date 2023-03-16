stack [
s "coffee*6" # n (irand 39) # speed (0.7) # gain (0.6),
fast 28 $ s "rave*3" # n (irand 8) # speed (0.7) # gain (0.8) # silence,
s "reverbkick" # speed (0.9),
s "coins" # speed (-1.0),
s "speech" # n (irand 16) # speed 2.1
] # silence


osc(60,-0.015,0.3).diff(osc(60,0.08).rotate(Math.PI/2))
 .modulateScale(noise(3.5,0.25).modulateScale(osc(15).rotate(()=>Math.sin(time/2))),0.6)
 .color(1,0.5,0.4).contrast(1.4)
 .add(src(o0).modulate(o0,.04),.6)
 .invert().brightness(0.1).contrast(1.2)
 .modulateScale(osc(2),-0.2)
 .out()

 .add(o0,0.5)
