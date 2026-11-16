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

Swipe between four pages:

- **Drive**: shift lights, gear, revs, speed, drive mode, oil and coolant, and a panel (see below).
- **Warm-up**: oil and coolant coming up to temperature.
- **G-force**: the g-meter and your peaks. Hold a finger still on it to reset the peaks.
- **Tires**: pressures and temperatures, when the car reports them.

Tap the **G** for Options; every Options page has a **Dash** button back. Tap the gear on Drive to step through your favourite themes.

### Themes

Options > **Theme**. Tap a card to switch at once, star the ones you like, and pick colours on the Theme card where a theme has them. **Follows the look** sets the car's ambient light to match the theme.

Each theme styles the centre screen, the cluster and the HUD together. Cards marked **FULL** draw the whole cluster, the middle included. The others replace the dials on both sides and leave the middle for the map, the logo or lyrics.

| Theme | Style | Whole cluster |
| --- | --- | --- |
| M Style, GT, Digital '84, Sim Racing, Lumen, Pixel, Vector | Sports, race, retro digital, sim racing, glow, pixel art, vector lines | No |
| Desktop '98, Pocket, Heist, Arcade, Pod '04, iDrive CCC | A 90s desktop, a pocket console, a getaway, a coin-op racer, a music player, the first iDrive | No |
| Tuner, Vinyl | 90s tuner dials; the music first (artwork, lyrics, a turntable speedometer) | No |
| GT3, E46, Jet, Group C, Agent, Synthwave | A GT3 race dash, the E46's orange dials, a fighter jet, an 80s endurance racer, a spy car's gadget dashboard, an 80s neon night drive | Yes, switchable |
| Apex, Dials, RPG, Blueprint | A modern sport cluster, five classic gauges, a role-playing game's menu, an engineering drawing | Always |

Some themes have a Drive page of their own:

- **GT3** is a lap timer: tap the LAP column as you cross the line each lap to see your lap times and how far ahead or behind your best you are. From a standstill it also times 0-60 mph (0-100 km/h), the quarter mile and 60-0 braking.
- **RPG** has a minimap of a made-up world (not GPS): your car moves across it as you drive and turns as you corner.
- **Blueprint** draws the g-forces as a free body diagram, your session's records as a parts list, and oil, water and fuel in section.
- **Synthwave** is a night drive: your records as an arcade's high scores (tap the session to restart it), the road ahead rolling by at your speed with a wireframe car leaning into the corners, and a neon g-force ring.
- **Agent** is a mission briefing: your records as a mission log, the g-forces as a blip on a sweeping threat radar, and the car's systems with a status line (ALL CLEAR, SHIFT!, or a warning).
- **Vinyl** is the song playing on your phone: artwork, synced lyrics or a visualizer, and the song's progress bar.
- **E46** puts the panel in its right air vent; a tap on its hazard switch steps through your favourites.

### The panel

On Options, **Panel** steps Drive's panel between the **G-meter**, **Music** (what your phone is playing, with artwork) and your **Logo**.

### Cluster & HUD

Options > **Cluster & HUD** sets what the instrument cluster and the HUD show. These need the Cluster renderer tool, version 0.5.1 or newer.

**Cluster (the middle of the cluster):**

- **Auto**: directions during a route, G's TV or G's Music when they play there, otherwise the logo.
- **Logo**, **Music** (lyrics) or **Map** (Waze) all the time.
- **Stock**: the car's own.

**HUD:**

- **Auto**: the map during a route, lyrics while a song plays, otherwise your theme.
- **Theme**, **Music**, **Map** or **Stock** all the time.

**Switches at the top:**

- **Theme dials**: your theme's dials on the cluster. Off gives the car's own dials back.
- **Beside the car's HUD**: draws your HUD smaller, next to the car's own instead of over it.
- **Full cluster** (GT3, E46, Jet, Group C, Agent and Synthwave only): on draws the whole cluster; off leaves the middle for your Cluster pick.

Good to know:

- While a whole-cluster theme shows, the middle is the theme's: no map, logo, lyrics or G's TV there, and Waze's map is switched off.
- With theme dials on, the car's speed-limit sign and cruise-control readout under the speedometer are covered. Turn Theme dials off to see them.
- Nothing is drawn on the cluster or the HUD while the car switches on or off; it comes back a few seconds after.
- If a theme makes the cluster restart twice, G's Dash goes back to the car's own dials and says so on this page. **Refresh cluster** (on Help) or another theme tries again.

### Other options

- **Driving**: your redline and shift point, the temperatures Warm-up counts as ready, the fuel tank size, the G-meter's scale, and a reset for your session's peaks.
- **Units**: mph or km/h, °F or °C, and psi, bar or kPa. **Show gear in Drive** shows D3 instead of D when the car reports the gear.
- **Logo**: the logo on the home-screen widget, the cluster and Drive's panel. Use the G mark or send your own GIF from your phone (Send a GIF, scan the code). You can set a logo for everything, per drive mode or per theme.

### Help

- The QR code opens this guide.
- **Refresh cluster** remakes the logo, dials and HUD if they are stuck, blank or wrong.
- **Reset HUD guard**, **Restart renderer** and **Restart head unit** fix a stuck cluster or HUD. Each asks first and needs the **G's Helper** tool from the same Store source.
- **Reset options** puts every G's Dash option back to its default. Your GIFs stay.
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
- **The HUD went back to the car's own and stays there** (Help says the renderer turned the HUD off). Use **Reset HUD guard** on Help (with G's Helper), or update the Cluster renderer from the Store.
- **No lyrics or artwork in G's Music.** The car has to be online.
- **No picture in G's TV.** It plays only while parked.
- **Phone mirroring asks for G's TV Mirroring.** Install it from `sl0w-apps/gs-apps`, then open Phone again.
