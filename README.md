<!DOCTYPE html>
<html>
	<head>
		<title>Boost Pedals</title>
		<link href="data:image/x-icon;base64,AAABAAEAEBAAAAAAAABoBQAAFgAAACgAAAAQAAAAIAAAAAEACAAAAAAAAAEAAAAAAAAAAAAAAAEAAAAAAAAAAAAArsfbABgVHwDe7vgALCo2ACYmMQAnJjEAo77UAGpziAA+O0gAzuf0AJ2UawAJBQsA0Of0AL25fgBMTl0ArcPXALDK3AAQDRYAjKG8AOn2+wAoJjIAvdXmAOz2+wB6h6MAtJaPAOPt9ADGyc4AzuXzACQiLgAgHikAKikzAFxicAA0M0AAISAsAB8dJAAsKzYApHRkACgnMQDP5fQAMzE+ACYjLAAWFB0A0OLsAKvF3ADR6PQAqsLUAEdDTQC9s7MAutPmAB4dJQAIBAkArMTXAC0rNwCgrMAAKCcyAJmqvgCXWlQA0uj1AJ22zgCgts4AUlFYAAgECgCsxNgA0ObzACknMwDAvIIAv9bnAMG8ggDn8voAs83gAJivygAnJTEAp77RAL3Q4ADS5vQAHx8qAMTd7QArKjQArMPUANXp9ADr8/gAVVJfAMO+hgBcXGQA0+fyALKKdADQ5vUApL/YAKNxYADi4+QAR0dWAMnY4wAHAwcALCo1ALbO3wBmancA0+XwACooMwDT5/MAxsbMAMri8QAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAWhEQLAAAAAAAAAAAAABfW0k0LgcAAAAAAAAAAAA/ARNGOEFNOwAAAAAAAAAaT2UiNxUmSEMAAAAAAAAAAF5iQQZISBUXGAAAAAAAAAAhQTcVHR4CKFgAAAAAAAAAAE4yHwQkFlwxCAAAAAAAAAA1XiBAWQoNV0cAAAAAAAAAABwnOS0bYTAPZAAAAAAAAAAlOitWY1VKEjwAAAAAAAAAA1AZFFQpIz5FAAAAAAAAAABLKgUzDF1CYAAAAAAAAAAAAEwzDj1ECTYAAAAAAAAAAABTCy9SAAAAAAAAAAAAAAAAAFEAAAAAAAAAAP//AAD4fwAA4H8AAMA/AACAPwAAwB8AAMAfAADgDwAA4A8AAPAHAADwBwAA8AcAAPgHAAD8BwAA/D8AAP7/AAA=" rel="icon" type="image/x-icon" />
	</head>
    <style>
    	body {font-family: Trebuchet MS;}
		h4 {text-align: center;}
		div {
		    margin-left: 100px;
		    margin-right: 100px;
		}
    </style>
	<body style="background-color:lightyellow;">
	    <div>
		<h1>Boost Pedals</h1>
		<h2>The basic technology behind Boost Pedals and step-by-step guide on how to build one</h2>
		<h3>Version 1.0 - Brandon Goltz-Lovelace</h3>

		<br/><br/>

		<font size="5">Introduction</font>

		<p>Most people have heard of a boost pedal before, and the name itself is pretty self explanatory, however most guitarists don't know how they work. For those of you who don't know what they are, imagine you have an amp where the volume can go up to 10 and your guitar sounds pretty good. Now imagine for a second the possibilty that you could reach the elusive "11" and perhaps give your guitar an even beefier tone. Sounds too good to be true right? Well in the most basic explanation possible, a boost pedal is a pedal that amplifies the output signal of your guitar so that you can reach that louder volume as well as a litte bite to your overall sound without adding any unwanted distortion. So how does it work?<p/>

		<p style="text-align:center;"><img src="https://upload.wikimedia.org/wikipedia/en/0/06/Spinal_Tap_-_Up_to_Eleven.jpg" alt="The Elusive 11" style="width:450px;height:300px;">

		<h4>The Elusive "11"</h4>

		<p/>

		<font size="5">The Electronics Behind the Pedal</font>

		<p>Below I have included a basic wiring diagram of a boost pedal. There are no resistor or capacitor values in order to increase the simplicity of the design and allow us to focus on whats going on.<p/>

		<p style="text-align:center;"><img src="http://imgur.com/qZVcjxU.png" alt="Basic Boost Pedal Schematic" style="">		

		<h4>Basic Boost Pedal Schematic</h4>
        
        <p/>

		<p>In order to understand what is going on in this circuit, let's start with the signal coming from the guitar. As the signal from the guitar travels the wire and into our boost pedal it picks up impurities and extra noise, essentially becoming a blend of AC and DC signals. If we were to simply boost this signal we would end up with a lot of extra hum and unwanted noise. In order to combat that we need to filter out the DC signal and amplify the AC signal.<p/>

		<p>Looking at our schematic we notice at the first junction consists of a capacitor (C2) and resistor (R3) in parallel. C2 acts as a filter, letting in AC, but blocking DC, which flows freely through R3 to ground. On a side note , in order for the AC signal to not flow to ground with DC we must R3 extremely large. Next, our current reaches a junction consisting of two resistors (R1 and R4) and the base of a transistor (referenced by the letter B). R1 and R4 act as a voltage divider for the 9V battery, sending some voltage to the base of the transistor and acts as a reference. As our current flows through the transistor it is amplified by battery, flowing up  9V battery. Based on our basic understanding of amplification we can assume this is our voltage source that amplifies our guitar signal (much like how an amplifier uses power from the wall outlet to amplify our guitar). In order o further understand<p/>
    </div>
	</body>
</html>
