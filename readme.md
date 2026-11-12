# G's Apps

G's Dash, G's Music and G's TV for the car's centre screen. This page is static: it does not send or store anything.

## Install

In the Store, add the source `sl0w-apps/gs-apps`, then install:

- **G's Dash**
- **G's Music**
- **G's TV**

Pictures in the instrument cluster and the HUD need the Cluster renderer tool. Phone mirroring needs **G's TV Mirroring** from this same source (G's TV asks for it by that name).

## Activate

One order code unlocks all three apps. The license does not expire. A refund or a chargeback is what turns it off. The apps keep working with no connection.

The activation screen shows a QR code for the shop, a place to type the code from the receipt, and Refresh. Enter the code in any one of the three. When it says licensed, leave the app and open it again: the features start on the next open. The other two apps on the same car use that license too.

## G's Dash

Swipe between **Drive**, **Warm-up**, **G-force** and **Tires**. Tap the **G** for Options. Every Options page has a Dash button back to the dash.

- **Drive:** shift lights, gear, rpm, speed, drive mode, oil and coolant. The right-hand panel is the G-meter, the music on your phone, or your logo.
- **G-force:** hold a finger still on it to reset the session peaks.
- **Tires:** pressures and temperatures when the car reports them.
- **Theme:** the looks (M Style, GT, Digital '84, Sim Racing, Lumen, Pixel, Vector, Desktop '98, Pocket, Heist, Arcade, Pod '04, iDrive CCC, E46, Apex). Tap a card to switch at once. Star a look, then tap the gear on Drive to step through the favourites. Some looks have colours on the Theme card. **Follows the look** sets the ambient light to one of the car's 12 colours for that look. Default leaves the car's colour alone.
- **Panel:** one tap steps Drive's panel: G-meter, Music, Logo.
- **Cluster & HUD:** what the cluster's centre shows (Auto, Logo, Music, Map, Stock) and the HUD (Auto, Theme, Music, Map, Stock). **Theme dials** puts your look's dials on the cluster. **Beside the car's HUD** draws yours smaller, on the right, next to the car's own. Stock on both, with theme dials off, puts them back. Theme dials together with a HUD need Cluster renderer 0.5.1 or newer. Map is Waze.
- **Engine & warm-up:** redline, the shift point, Max rpm (Auto follows the redline), and the oil and coolant temperatures Warm-up counts as ready.
- **Gauges & session:** Max speed (Auto, or a fixed top), oil and coolant as gauges or a warming-up line, the fuel tank size, the G-meter scale, and a reset for the session peaks.
- **Units:** mph or km/h, °F or °C, psi, bar or kPa. **Show gear in Drive:** Off keeps D; On shows the gear (D3) when the car reports it.
- **Logo:** the home-screen widget, the cluster, and Drive's panel. Default is the G mark. **My GIF** is one you send from your phone: Send a GIF, scan the code, pick a GIF, then Use this GIF on the car. **Logo for:** Everything, Drive mode (Comfort, Sport, Sport+ and any mode the car reports), or Each theme. An empty slot plays the main logo.
- **Help:** this guide (the QR code), **Refresh cluster** (remakes the logo, dials and HUD if they are stuck, blank or wrong), and remote logs. Logs are sent only after a crash, or when you tap Send logs now, and only when that is turned on.

## G's Music

Full screen, the music the car is playing from your phone: CarPlay, Android Auto, Bluetooth or USB. Large artwork, synced lyrics or a visualizer, and the song's progress. There are no play buttons. Use your phone, the steering wheel, or the car's media screen. Where the car allows it, drag the bar to move within the song. Nothing playing shows that, not a made-up song. Artwork and lyrics need the car online.

Tap the **G** for Settings. A tap steps each one:

- **Show:** Lyrics (else visualizer), Visualizer, or Nothing.
- **Cluster (map area):** Lyrics + visualizer, Visualizer only, or Off. G's Dash's Cluster pick can take this area.
- **Cluster & HUD size:** Small, Medium or Large.
- **HUD:** Lyrics or Off.

The home-screen widget shows the artwork, title and progress while something plays, or the G's Music mark when it does not.

## G's TV

Experimental. The picture plays on the centre screen only while the car is parked. If it is not, the screen says video is available when parked.

Home is a row of tiles: **Spelunkr** (channels of programmes), **Phone** (your iPhone's screen), any MP4 links you added, and **Add source**. The **G** opens Settings.

- **Spelunkr:** Play, then channel up and channel down. Guide lists what is on. **After driving:** Resume where I stopped, or Jump to what's on now.
- **Your sources:** a direct MP4 (H.264) link sent from your phone. Add source shows a QR code and a 6-digit code. The car checks the link before it can be saved. Hold a source to rename it, send a new link, or remove it.
- **Settings:** At most (GPU video) in frames per second, After driving, and Sound. Sound is experimental and on by default (the car's speakers). Tap Sound for the sound check, including Test sound.
- **Cluster** and **HUD** buttons on the picture, parked only. A guided route gives the cluster back to the directions.

## Phone mirroring

Needs the **G's TV Mirroring** tool from this same Store source. Open G's TV, tap **Phone**, and while that page is up:

1. Keep the car on your iPhone's Personal Hotspot (the same way G's TV gets online).
2. On the iPhone: Control Centre, Screen Mirroring, then **G's TV**.
3. Type the code this page shows.
4. For sound, choose the car's Bluetooth as the iPhone's audio output.

The picture is shown when the car is parked.

## If something is wrong

- **The code is not recognised.** Enter the full code from the receipt. Too many tries asks you to wait, then tap Refresh.
- **No connection on the activation screen.** A license you already entered stays. Refresh when you are online again.
- **It says the license is not active.** That is a refund or a chargeback. A new code is a new order.
- **The code worked but you still see the activation screen.** Leave the app and open it again.
- **Cluster or HUD is stuck, blank or wrong.** G's Dash, Help, Refresh cluster. Theme dials and a HUD together need Cluster renderer 0.5.1 or newer.
- **G's Music has no lyrics or artwork.** The car has to be online. The song still shows from what the car is playing.
- **G's TV will not show a picture.** It plays only while parked. The screen says so when it is not.
- **Phone says to install G's TV Mirroring.** Install that tool from `sl0w-apps/gs-apps`, then open Phone again.
- **Phone says the receiver is not answering.** Restart the car, then open Phone again.
