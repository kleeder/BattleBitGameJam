# Grundlgendes

Im code Editor:

dofile("game.lua")

Wiki mit nützlichen Kram:
https://github.com/nesbox/TIC-80/wiki

Link zu BotB: https://battleofthebits.org/arena/Entry/Katzu/29526/

Link zur Tic-Seite: https://tic.computer/play?cart=646

## Steuerung 
- Arrows L/R: Move
- Arrow up: Jump
- Arrow down: Sneak
- D: Throw Wool
- D + Sneak: Pull wool (near wool)
- R: Reset Screen
- R (hold): Reset Level

# Notizen und Struktur

## Sprites:
- #000: blank
- #001 - #079: solid
- #080 - #111: half-solid
- #112 - #223: decoration / background
- #224 - #255: special-event-sprites
- #256 - #271: cat stuff
- #272 - #276: wool stuff
- #277 - #511: Logo etc.

## World Map:
- 01: preLevelOne
- 2-5: Level 1
- 9: preLevelTwo
- 10-14: Level 2
- 17: preLevelThree
- 18-22: Level 3
- 25: preLevelFour
- 26-30: Level 4
- 33: preLevelFive
- 34-39: Level 5
- 42: Music Box
- 49: Debug
- 6,7,8,15,16,23,24,31,32,40,41,43-48,50-62: unused
- 63: Controls & Game Done
- 64: Main Screen

## Level:
- 01: Basic Tutorial
- 02: Basic mit Kakteen (Übergang zur Höhle)
- 03: Höhle (erst Dirt, dann Cavern) (anspruchsvoller)
- 04: knifflig mit Lava usw (Höhle)
- 05: brutal schwer (Castle)

## SFX:
- 00: Lead (Pulse 1)
- 01: Lead (Pulse 1) Pitch Slide Up
- 02: Saw
- 03: Hat
- 04: Kick
- 05: Arp058
- 06: Arp047
- 07: Arp049
- 08: Arp058 fade
- 09: Arp038
- 10: Arp039
- 11: Arp036
- 12: Arp039 fade
- 13: Triangle
- 14: Square
- 15: Lead (Pulse 1) Vibrato
- 16: Lead (Pulse 1) Vibrato fade
- 17: Crash
- 18: RevCrash
- 19: Snare
- 20: Throw Wool
- 21: Pull Wool
- 22: Jump
- 23: Player under map
- 24: Wool under map
- 25: Reset Complete

## Music:
Track 00:
- Pattern 01	Beginning1
- Pattern 02	Beginning2
- Pattern 03	Lead1
- Pattern 04	Arps1
- Pattern 05	Arps2
- Pattern 06	Bass1
- Pattern 07	Bass2
- Pattern 08	Triangle1
- Pattern 09	Lead2
- Pattern 10	Noise1
- Pattern 11	Bass3
- Pattern 12	Triangle2
- Pattern 13	Bass4
- Pattern 14	Triangle3
- Pattern 15	SquareLead1
- Pattern 16	SquareLead2
- Pattern 17	SquareLead3
- Pattern 18	TriangleBridge1
- Pattern 19	SquareBridge1
- Pattern 20	SawBridge1
- Pattern 21	NoiseBridge1
- Pattern 22	TriangleBridge2
- Pattern 23	SquareBridge3
- Pattern 24	SawBridge4
- Pattern 25	SawBridge5
- Pattern 26	Beginning3
- Pattern 27	Beginning4

Track 01:
- Pattern 28	Beginning1
- Pattern 29	Beginning2
- Pattern 30	Beginning3
- Pattern 31	Beginning4
- Pattern 32	TriBass
- Pattern 33	BeginningTriEnd + Snare
- Pattern 34	Crash
- Pattern 35	Noise1
- Pattern 36	Snare
- Pattern 37	Lead1
- Pattern 38	Lead2
- Pattern 39	Lead3
- Pattern 40	Lead4
- Pattern 41	Lead4b
- Pattern 42	BassFade
- Pattern 43	LeadFade

Track 02:
- Pattern 44	Bass1
- Pattern 45	Noise1
- Pattern 46	Tri+Bass1
- Pattern 47	Noise2
- Pattern 49	Tri+Bass2
- Pattern 51	Tri+Bass3
- Pattern 52	Lead1
- Pattern 53	Tri+Bass4
- Pattern 54	Lead2

Track 03:
- Pattern 03	Lead1
- Pattern 06	Bass1
- Pattern 07	Bass2
- Pattern 09	Lead2
- Pattern 10	Noise1
- Pattern 11	Bass3
- Pattern 13	Bass4
- Pattern 15	SquareLead1
- Pattern 17	SquareLead3
- Pattern 34	Crash
- Pattern 36	Snare
- Pattern 44	Bass1
- Pattern 24	SawBridge4
- Pattern 39	Lead3
- Pattern 40	Lead4
- Pattern 41	Lead4b
- Pattern 51	Tri+Bass3

Track 04:
- Pattern 48	Fanfare1
- Pattern 50	Noise1
- Pattern 55	Bass1
- Pattern 56	TriangleRiseUp

Track 05:
- Pattern 57	Lead
- Pattern 58	Lead
- Pattern 59	Tri
- Pattern 60	Bass
