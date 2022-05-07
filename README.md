# djbb-magantenna
The Maggie is a simple device for listening to electromagnetic radiation in the world around you. Hold it up to your phone, computer, router, or anything with electricity to hear some interesteding buzzes, bleeps, and the occasional radio or walkie-talkie signal. Similar to the Priezor LOM.

## Tools Needed
- 3D Printer
- Soldering Iron + Solder
* Allen wrench for M3 Bolts
* Hot glue gun (Not strictly necessary, but good to have)
* Some all purpose glue or resin (hot glue, super glue, modpodge, resin, etc.)

## Parts List
* 3D printer filament (PETG or PLA) ~ 55 grams
	* Download models [here](https://www.printables.com/model/188988-djbb-maggie-passive-magloop-antenna-for-sound-desi)
* 10 M3 Nuts (8-32)
* 10 M3 Bolts
* 1 Aux jack [STX-3000](https://www.digikey.com/en/products/detail/kycon-inc/STX-3000/9975995)
	* Note: I created my model to fit this just exactly. You'll have to modify it if you use a part with different dimensions.
* Magnet Wire*
	* I suggest [32 AWG](https://www.amazon.com/dp/B07J9PM312?psc=1&ref=ppx_yo2ov_dt_b_product_details)


**\*Note on Magnet Wire**
I tested with a few gauges, and I suggest 32 AWG. I would not go larger than ~30 AWG, but go as small as you'd like.

**Larger** (lower AWG number) = Fewer coils, but easier to work with
**Smaller** = More coils, but the tiny wire can get annoying to work with

See the Audio Examples section at the bottom for a comparison of the sound.

## Assembly
1. 3D print the top and bottom piece. I used PETG and a 0.6mm nozzle, but anything should work. 
	1. #dttodo - add links to buy the kit
2. Cut 2 pieces of wire, about ~15 cm is good. 
3. Solder these wires to the L and R pins on your aux jack
	1. These are the 2 pins at the bottom of the jack. The single pin in the middle is ground, and we don't need it.
	2. [IMG_30667@0 5x|300](https://user-images.githubusercontent.com/47721204/167274122-dc783fa4-09a3-498e-87e6-2adce316a21b.jpg)
.5x

4. Pop the aux connecter in it's home, and route the wires like so. 

	3. ![[IMG_30669@0.5x.jpg|300]]


6. Snap on the other shell and screw it together.
	
	2. ![[IMG_30668@0.5x.jpg|300]]


8. Wind the magnet wire around the shell. You want the 2 ends to end up by the 2 aux jack wires.
	1. Note this little channel that you can use at the end of the coil to get the wire down to the aux wires. 
	
	3. ![[IMG_30666@0.5x.jpg|300]]


8. Use a small piece of sandpaper to sand off the coating on the 2 ends of the magnet wire
	
	2. ![[IMG_3066@0.5x.jpg|300]]


10. Cut the aux jack wires to length, and strip the ends. Twist each around one of the magnet wire ends, and solder. It's good to add some heat shrink tube, but it probably doesn't really matter.
	
	2. ![[IMG_30664@0.5x.jpg|300]]


12. Use shove the soldered wires into the space within the shell. Secure with hot glue.
13. Apply hot glue, resin, superglue, or whatever to the outside of the wire windings to hold everything in place.
14. Plug in your aux cord and ya good to go - plug it into a pre-amp -> audio recording device if you can, but it also seems to work by plugging straight into something like a Zoom H1 and turning the gain up hella.

	1. ![[IMG_30663@0.5x.jpg|300]]
	2. ![[IMG_30662@0.5x.jpg|300]]


## Things to listen to
- Wifi router
- 3d Printer
- Laptop 
- Smartwatch
- Telephone poles
	- Have heard conversations of unknonw origin while messing aroiund near one of htese
- Anything using electricity. 

## Audio Examples
I recorded audio from 4 antenna designs in the table below. I have a sample of the same source for each: holding it by my router, sweeping it around my macbook, and holding my phone in the middle of it while opening apps, scrolling around. They were all recorded into my Zoom H1n with NO pre-amp, and the gain knob set to 7/10. They were all normalized before uploaded, but otherwise not processed.

The last test is a frankenstein coil made up of what I had left of a few different spools.

| AWG   | Turns | Audio                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| ----- | ----- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 24    | 50   | [Router](https://soundcloud.com/tbl_records/24-awg-50-turn-router?in=tbl_records/sets/djbb-maggie-antenna-audio-examples&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing), [Laptop](https://soundcloud.com/tbl_records/24-awg-50-turn-router-laptop?in=tbl_records/sets/djbb-maggie-antenna-audio-examples&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing), [Phone](https://soundcloud.com/tbl_records/24-awg-50-turn-router-iphone?in=tbl_records/sets/djbb-maggie-antenna-audio-examples&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing) |
| 30    | 300   | [Router](https://soundcloud.com/tbl_records/30-awg-300-turn-router?in=tbl_records/sets/djbb-maggie-antenna-audio-examples&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing), [Laptop](https://soundcloud.com/tbl_records/30-awg-300-turn-laptop?in=tbl_records/sets/djbb-maggie-antenna-audio-examples&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing), [Phone](https://soundcloud.com/tbl_records/30-awg-300-turn-iphone?in=tbl_records/sets/djbb-maggie-antenna-audio-examples&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| 36    | 500    | [Router](https://soundcloud.com/tbl_records/36-awg-500-turn-router?in=tbl_records/sets/djbb-maggie-antenna-audio-examples&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing), [Laptop](https://soundcloud.com/tbl_records/36-awg-500-turn-laptop?in=tbl_records/sets/djbb-maggie-antenna-audio-examples&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing), [Phone](https://soundcloud.com/tbl_records/36-awg-500-turn-iphone?in=tbl_records/sets/djbb-maggie-antenna-audio-examples&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| 36 + 32 + 30 | ~700  | [Router](https://soundcloud.com/tbl_records/36-32-30-awg-700-turn-router?in=tbl_records/sets/djbb-maggie-antenna-audio-examples&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing), [Laptop](https://soundcloud.com/tbl_records/36-32-30-awg-700-turn-laptop?in=tbl_records/sets/djbb-maggie-antenna-audio-examples&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing), [Phone](https://soundcloud.com/tbl_records/36-awg-500-turn-iphone?in=tbl_records/sets/djbb-maggie-antenna-audio-examples&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |

You can download full quality files (24bit, 96khz) [here](https://drive.google.com/drive/folders/1w1TxuPjWD8JwOcv8hpStXqV5O0cpeXMa?usp=sharing)
A super simple demo track with [more examples](https://soundcloud.com/tbl_records/djbb-emag-sample-pack)
A free sample pack with sounds from these is [here](https://www.djbajablast.com/sample-pack/emagsfx1)

## Further Reading

https://en.wikipedia.org/wiki/Loop_antenna
