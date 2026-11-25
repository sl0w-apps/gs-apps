# G's Apps

Three apps for the car's centre screen: **G's Dash** (your driver display, on the screen, the instrument cluster and the HUD), **G's Music** (what's playing, with lyrics) and **G's TV** (video while parked). This page is static: it does not send or store anything.

## Install

In the Store, add the source `sl0w-apps/gs-apps`, then install **G's Dash**, **G's Music** and **G's TV**.

Two free tools from the same source add more:

- **Cluster renderer**: needed for anything in the instrument cluster or the HUD.
- **G's TV Mirroring**: needed to mirror your phone in G's TV.

## Activate

One order code unlocks all three apps on one car. It does not expire, and the apps work without a connection once activated.

1. Turn on your phone's hotspot so the car is online.
2. Open any of the apps. Until it is licensed, the activation screen fills the screen and reads the car's VIN by itself.
3. Type your order code (XXXX-XXXX) and press **Activate**.

The other two apps use the same license. Your code is on the activation code page linked from your order confirmation (it asks for the order number and the email or phone you used). A Garage + Apps code works; a Garage-only code does not.

## G's Dash

### The dash

Swipe between five pages (G's Dash opens on Drive):

- **Favourites** (left of Drive): up to eight of your favourite themes. Tap one to switch to it, or tap the **+** box to add the theme on now. The **x** on a card takes it off.
- **Drive**: shift lights, gear, revs, speed, drive mode, oil and coolant, and a panel (see below).
- **Warm-up**: oil and coolant coming up to temperature.
- **G-force**: the g-meter and your peaks. Hold a finger still on it to reset the peaks.
- **Tires**: pressures and temperatures, when the car reports them.

Tap the **G** for Options; every Options page has a **Dash** button back. Tap the gear on Drive to step through your favourite themes.

### Themes

Options > **Theme**. Tap a card to switch at once, star the ones you like (eight at most), and pick colours on the Theme card where a theme has them. Under **Ambient light**, the car's ambient light takes the theme's colour: it's on for every theme unless you turn it off. **Change with theme** switches it on or off for the theme on now. It's kept per theme, and per colour where a theme has colours (Colors in blue can have one, Colors in red another, or none). Where it's off, the car keeps its own colour. Step **Colour** with − and +: **Theme colour** (the theme's own, or the colour you picked where a theme has colours; a white or silver one gives white), Red, Orange, Amber, Yellow, Green, Cyan, Blue, Violet, Pink or White, then BMW's twelve numbered colours. The named colours go to the lights exactly, at the brightness your car uses; on a car whose lights don't answer, only BMW's numbered colours are offered. **Multi-colour** (off by default) gives each part of the cabin its own colour from the theme while Theme colour is picked: the dash in the theme's colour, and the doors, the centre console and the footwells in the theme's other colours (M Style: light blue, red and white). A theme with one colour stays that colour everywhere.

Ambient config and IterioDev's Ambient Light can stay installed. If one of them is also setting a colour, the two apps may take turns, and an amber note appears beside **Ambient light**. Tap it for what to change in that app: in Ambient config, tap **Original colour** on its Colour tab, and on its Driving modes tab for each mode that has its own colour; in IterioDev's app, turn its colour and drive-mode colours off.

**Driving modes** (on the Theme page, off by default) gives each driving mode its own theme and colour: Colors in blue for Comfort and red for Sport, say. Comfort, Eco Pro, Sport, Sport+ and Individual are always listed, and any other mode once the car reports it. Turn it on, then tap a mode (**Tap to save**) to give it the theme on now, or just pick a theme while driving in a mode and it's kept for that mode. The theme changes once a mode has been on for 2 seconds, so stepping through the modes doesn't flick the cluster through each one. A mode with no theme keeps whatever is on.

Each theme styles the centre screen, the cluster and the HUD together. Cards marked **FULL** draw the whole cluster, the middle included. The others replace the dials on both sides and leave the middle for the map, the logo or lyrics.

| Theme | Style | Whole cluster |
| --- | --- | --- |
| Colors | The car's own stock dials, in one of eight colours | No |
| M Style, GT, Digital '84, Sim Racing, Lumen, Pixel, Vector | Sports, race, retro digital, sim racing, glow, pixel art, vector lines | No |
| Desktop '98, Pocket, Heist, Arcade, Pod '04, iDrive CCC | A 90s desktop, a pocket console, a getaway, a coin-op racer, a music player, the first iDrive | No |
| Tuner, Vinyl | 90s tuner dials; the music first (artwork, lyrics, a turntable speedometer) | No |
| GT3, E46, Jet, Group C, Agent, Synthwave | A GT3 race dash, the E46's orange dials, a fighter jet, an 80s endurance racer, a spy car's gadget dashboard, an 80s neon night drive | Yes, switchable |
| Apex, Dials, RPG, Blueprint | A modern sport cluster, five classic gauges, a role-playing game's menu, an engineering drawing | Always |
| Prototype, Touring, MCF1, E30, MCF1R | Race dashes after real ones: a prototype's boxed display, a touring car's white LCD, an endurance car's amber LCD, a late-80s analog cluster, a steering-wheel LCD with shift lights | Always |

Some themes have a Drive page of their own:

- **GT3** is a lap timer: tap the LAP column as you cross the line each lap to see your lap times and how far ahead or behind your best you are. From a standstill it also times 0-60 mph (0-100 km/h), the quarter mile and 60-0 braking.
- **RPG** has a minimap of a made-up world (not GPS): your car moves across it as you drive and turns as you corner.
- **Blueprint** draws the g-forces as a free body diagram, your session's records as a parts list, and oil, water and fuel in section.
- **Synthwave** is a night drive: your records as an arcade's high scores (tap the session to restart it), the road ahead rolling by at your speed with a wireframe car leaning into the corners, and a neon g-force ring.
- **Agent** is a mission briefing: your records as a mission log, the g-forces as a blip on a sweeping threat radar, and the car's systems with a status line (ALL CLEAR, SHIFT!, or a warning).
- **Vinyl** is the song playing on your phone: artwork, synced lyrics or a visualizer, and the song's progress bar.
- **Prototype, Touring, MCF1 and MCF1R** show your records (tap the session to restart it), the look's own instrument (a rev trace, a big session timer, a speed trace, or big shift lights) and the G-meter.
- **E46 and E30** show the car's two centre air vents and put the panel in the right one; a tap on the hazard switch between them steps through your favourites.

### The panel

On Options, **Panel** steps Drive's panel between the **G-meter**, **Music** (what your phone is playing, with artwork) and your **Logo**.

### Cluster & HUD

Options > **Cluster & HUD** sets what the instrument cluster and the HUD show. These need the Cluster renderer tool, version 0.5.1 or newer.

**Cluster (the middle of the cluster):**

- **Auto**: directions during a route, G's TV or G's Music when they play there, otherwise the logo.
- **Logo**, **Music** (lyrics) or **Map** (Maps on cluster: needs the Maps on cluster tool) all the time.
- **Stock**: the car's own.

**HUD:**

- **Auto**: the map during a route, lyrics while a song plays, otherwise your theme.
- **Theme**, **Music**, **Map** or **Stock** all the time.

**Switches at the top:**

- **Theme dials**: your theme's dials on the cluster. Off gives the car's own dials back.
- **Beside the car's HUD**: draws your HUD smaller, next to the car's own instead of over it.
- **Full cluster** (GT3, E46, Jet, Group C, Agent and Synthwave only): on draws the whole cluster; off leaves the middle for your Cluster pick.

**Switches at the bottom:**

- **Stay on in other apps** (on by default): keeps your theme's dials and HUD showing while you use another app, for as long as the head unit keeps G's Dash running. Off, the car's own come back a few seconds after you leave G's Dash.
- **Cluster sensor fix** (off by default): turn it on if your car has a driver-attention sensor (a camera) over the top middle of the cluster (some M3 and M4 models do). Every whole-cluster theme then draws smaller, clear of the camera as you see it from the driver's seat, and its background still fills the cluster.
- **Cover AUTO H icons** (off by default): every theme leaves two small see-through boxes at the top right of the cluster, where the car shows its AUTO H and light icons. On, the theme's background covers them, so you no longer see those two icons.
- **Small map** (off by default): on the themes drawn like the car's own dials (Colors, M Style and the others), the map in the middle is as wide as in the car's own layout. On, it goes back to the narrower window.
- **The BC button** on the end of the indicator stalk steps through the Cluster picks above (Auto, Logo, Music, Map, Stock), skipping any that can't show right now. Press it a few times quickly to jump ahead: the cluster changes once, about a second after your last press.

Good to know:

- While a whole-cluster theme shows, the middle is the theme's: no map, logo, lyrics or G's TV there, and the map is switched off.
- With theme dials on, the car's speed-limit sign and cruise-control readout under the speedometer are covered. Turn Theme dials off to see them.
- With a split theme (the map in the middle), the map's edges fade softly into the dials, and the car's messages under the map, such as a seat belt or door warning, stay visible. On the themes drawn like the car's own dials (Colors, M Style and the others), the map is as wide as in the car's own layout, with the speed and gear over its edges.
- Every theme's dials show the drive mode. On the themes drawn like the car's own dials (Colors, M Style, GT, Digital and the others), it's under the gear's line, and the car's own small fuel and oil gauges stay showing.
- Nothing is drawn on the cluster or the HUD while the car switches on or off; it comes back a few seconds after.
- If a theme makes the cluster restart twice, G's Dash goes back to the car's own dials and says so on this page. **Refresh cluster** (on Help), another theme, or an update of G's Dash tries again.

### Other options

- **Driving**: your redline and shift point, the temperatures Warm-up counts as ready, the fuel tank size, the G-meter's scale, and a reset for your session's peaks.
- **Units**: mph or km/h, °F or °C, and psi, bar or kPa. **Show gear in Drive** shows D3 instead of D when the car reports the gear. **Time zone**: Car uses the car's own zone; Set lets you pick a UTC offset with − and + if your themes' clocks show the wrong time.
- **Logo**: the logo on the home-screen widget, the cluster and Drive's panel. Default is the G mark in your theme's style.
  - **Use** picks **One logo**, **Per drive mode** or **Per theme**. Below it there's a tile for the main logo and each drive mode (the same modes as Theme > Driving modes) or this theme. Each tile says what it shows, and **Now** marks the one that's live.
  - Tap a tile to see it in the preview. The buttons under the tiles act on it: **Upload** (scan the code with your phone and pick a GIF or any picture; a photo is sent as a still), **Show default** / **Show mine** for the main logo, **Remove**, and **Examples** (Stage 1 to 3 for Comfort, Sport and Sport+).
  - A tile without its own logo uses the main one. Your uploads share 10 MB (the preview's last line shows how much they use), and a GIF over 1.5 MB keeps fewer frames at the same pace. If one won't fit, remove one you no longer use and try again.

### Help

- The QR code opens this guide.
- **Cluster report** (above the QR code) turns it into a report of what the cluster did: your cluster settings, the renderer's state and the cluster's recent log lines. Scan each code with your phone (tap the code for the next one) and send the text if the cluster ever crashed. It holds no VIN or address.
- **Refresh cluster** remakes the logo, dials and HUD if they are stuck, blank or wrong.
- **Reset HUD guard**, **Restart renderer** and **Restart head unit** fix a stuck cluster or HUD. Each asks first and needs the **G's Helper** tool from the same Store source.
- Your settings, favourites and last theme are kept through updates. With **G's Helper** installed they also come back if you remove G's Dash and install it again. If Help says *Settings not backed up*, install G's Helper.
- **Reset options** puts every G's Dash option back to its default. Your logo GIFs and pictures stay.
- **Remote logs** are sent only after a crash, or when you tap Send logs now, and only while they are turned on.

## G's Music

Full screen, the music the car is playing from your phone (CarPlay, Android Auto, Bluetooth or USB): large artwork, synced lyrics or a visualizer, and the song's progress. Control the music from your phone, the steering wheel or the car's media screen; where the car allows it, drag the bar to move within the song. Artwork and lyrics need the car online.

Tap the **G** for Settings:

- **Show**: Lyrics (else a visualizer), Visualizer, or Nothing.
- **Cluster (map area)**: Lyrics and visualizer, Visualizer only, or Off.
- **Cluster & HUD size**: Small, Medium or Large.
- **HUD**: Lyrics or Off.

## G's TV

Experimental. Video plays on the centre screen only while the car is parked.

- **Spelunkr**: channels of programmes. Guide lists what's on.
- **Your sources**: a direct MP4 (H.264) link sent from your phone with **Add source** (scan the code). Hold a source to rename, change or remove it.
- **Cluster** and **HUD** buttons put the picture there, parked only.
- **Settings**: frame rate, what happens after driving (resume or jump to what's on), and sound (experimental, on by default).

### Phone mirroring

Needs the **G's TV Mirroring** tool. Open G's TV and tap **Phone** (iPhone), **Cast** (Android or a direct MP4) or **YouTube**. For an iPhone:

1. Keep the car on your iPhone's Personal Hotspot.
2. On the iPhone: Control Centre, Screen Mirroring, then **G's TV**.
3. Type the code the car shows.
4. For sound, choose the car's Bluetooth as the iPhone's audio output.

**Stop** turns the receiver off. **Picture** chooses the centre screen, the instrument cluster or the HUD.

## If something is wrong

- **The code is not recognised.** Enter all eight characters. After too many tries, wait a few minutes.
- **No connection on the activation screen.** Turn the phone's hotspot on, then press Activate.
- **The code is already on another car.** A code is for one car. Reply to your order email to have it moved.
- **The license is not active.** That follows a refund or a chargeback.
- **The cluster or HUD is stuck, blank or wrong.** G's Dash > Help > **Refresh cluster**.
- **G's Dash isn't full screen** (the car's title bar shows above it, with a dark band under it). If Help says another copy of G's Dash is on the unit, tap that note: restart the head unit, and if it's still there, remove G's Dash in the Store and install it again. If it then starts with no settings, it reads them from the other copy while that copy is there.
- **The HUD went back to the car's own and stays there** (Help says the renderer turned the HUD off). Use **Reset HUD guard** on Help (with G's Helper), or update the Cluster renderer from the Store.
- **No lyrics or artwork in G's Music.** The car has to be online.
- **No picture in G's TV.** It plays only while parked.
- **Phone mirroring asks for G's TV Mirroring.** Install it from `sl0w-apps/gs-apps`, then open Phone again.
- **The phone's picture dropped.** The Phone page says why. Pick **G's TV** in Screen Mirroring on the iPhone again. To watch a video, start Screen Mirroring first and play it in the app, rather than using the app's own AirPlay button.
