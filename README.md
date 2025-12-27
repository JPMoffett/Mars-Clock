A browser-based Mars clock showing the current SOL and Mars Coordinated Time (MTC) 
in a retro 1970s NASA console style, complete with amber phosphor glow, and CRT scanlines.  
Runs entirely in the browser.

- Mars Sol Date (MSD): The clock calculates the current sol (Martian day) from UTC. This is the standard used by NASA and JPL for missions on Mars.

- Mars Coordinated Time (MTC): The fractional part of the sol is converted into a 24-hour format, like Earth time but scaled to Mars.

- Length of a sol: 1 Martian sol = 24 hours, 39 minutes, 35.244 seconds. The clock accounts for this so MTC runs slightly slower than Earth time.

- SOL counter: The displayed SOL number is the integer part of MSD, essentially counting how many sols have passed since a fixed reference date.

So every second of the Mars clock corresponds to about 1.0275 Earth seconds, keeping it synchronized with actual Martian time.

Open marsclock.png to see what it looks like. 

Works best in Firefox browser. 
