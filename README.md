# Star Voyager: The Titan Signal

A realistic-physics space adventure that runs in the browser. It is plain HTML, CSS and JavaScript with no libraries, and was made as a holiday assignment.

**Story:** in 2087 a coded signal is detected coming from Saturn's moon Titan. You are the captain of the survey ship Voyager-7. Collect four decoding fragments from Mars, Ceres, Jupiter and Saturn, then fly to Titan and decide what to do with what you find.

## Controls
**Touch (phone):**
- Touch and drag on the **left side** of the screen to use the joystick. The ship turns to point where you drag, and burns when you push the stick further out.
- **LASER**, **BRAKE** (auto-slows you to match your target's speed) and **E** (land, scan or shield) are buttons on the right.

**Keyboard:** arrows/WASD to turn and burn, Space = laser, S = match speed, E = land/scan/shield.

Follow the yellow arrow and the radar (top right) to find your objective.

## Realistic features
- **Newtonian flight:** no air drag. You keep your speed until you burn against it.
- **Gravity:** the Sun and every planet pull on your ship (a = GM / r²).
- **Kepler orbits:** planets orbit the Sun and Titan orbits Saturn, with closer worlds moving faster.
- **Limited resources:** fuel, oxygen and hull. Plan your burns.
- **Landing rules:** you must match the planet's speed (under about 38 km/s relative) or you crash.
- **Real facts:** each world shows true science facts (Olympus Mons, Saturn's rings, Ceres' salt deposits...).
- **Hazards:** the Sun's heat, an asteroid belt you can mine for ice, oxygen and scrap, space raiders, solar flares.
- **Story choices:** a distress beacon (rescue, salvage or ignore) and three different endings at Titan.

## Run it
Open `index.html` in any browser. In Acode, tap the Play button in the top bar.

`classic.html` is the original arcade shooter version.

## Tech
HTML5 Canvas, vanilla JavaScript, Pointer Events for touch and mouse, `localStorage` for the best score.
