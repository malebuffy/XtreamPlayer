# XtreamPlayer
An Android Auto Media Platform written from the ground up

License and installation can be obtained by using AAEnabler: [https://github.com/malebuffy/AAEnabler](https://github.com/malebuffy/AAEnabler)

# Android Projection user guide

Android Projection shows Xtream Player on your car's head unit, without Android Auto.

## Before you start

- Xtream Player installed on your phone.
- A certificate and private key for your head unit (some cars only accept Android Auto's certificates, google is your friend. This app does not distribute any certificate files)
- For wireless use: the phone paired with the car over Bluetooth. Alternatively USB also works.

## Setup

### 1. Choose Android Projection

1. Open Xtream Player.
2. Go to **Settings > Interface > App Mode**.
3. Select **Android Projection**.

The **Projection setup** screen opens. You can open it again from **Settings > Interface >
Projection setup**.

### 2. Turn off Android Auto

1. On **Projection setup**, tap **Disable Android Auto**.
2. On the page that opens, tap **Disable** (or **Force stop** if Disable is not available).
3. Go back to Xtream Player.

To use Android Auto again, set **App Mode** back to **Android Auto** and enable the Android Auto app.

### 3. Add your certificate

1. On **Projection setup**, tap **Upload certificate files**.
2. Select your certificate and private key (a `.p12` / `.pfx` file, or PEM files).
3. Enter the password if you are asked for one.

The certificate is saved. Tap **Clear certificate** to remove it.

### 4. Allow permissions

Allow the notification, Bluetooth, Wi-Fi and screen recording requests when they appear. The screen
recording request is only used to send the app's sound to the car. Device can be locked. If you dont, Web content and youtube will play sound from the phone.

## Connect

### Wireless

1. Make sure the phone is paired with the car over Bluetooth.
2. Open **Projection setup** on the phone.
3. Start wireless projection on the car.
4. Approve the Wi-Fi request on the phone if it appears.

### USB

1. Plug the phone into the car's USB port.
2. Tap **OK** if the phone asks to allow the connection.

When the connection is ready, Xtream Player appears on the car screen. Leave the phone on the
**Projection setup** screen or lock it with screen off.

## Using it in the car

- Touch the car screen, or use the knob, arrow keys and steering-wheel buttons.
- Tap a text field to type with the on-screen keyboard. Tap anywhere else, or press **Back**, to
  close it.
- Use **Larger** and **Smaller** on **Projection setup** to change the size of the interface.

## Stopping

Tap **Stop** on **Projection setup**, or unplug the phone.

## Buttons on the Projection setup screen

| Button | Use |
| --- | --- |
| Listen for wireless dashboard | Start waiting for the car. |
| Upload certificate files | Add your certificate. |
| Clear certificate | Remove the saved certificate. |
| Copy connection log | Copy the log, for support. |
| Xtream settings | Open the app settings. |
| Disable Android Auto | Open Android Auto's settings page. |
| Stop | End the session. |

## Troubleshooting

| Problem | What to try |
| --- | --- |
| The car does not connect | Check Android Auto is disabled, Bluetooth is on, and the phone is paired with the car. |
| Certificate refused | Use a certificate your head unit accepts. |
| No sound in the car | Tap **Stop**, start again, and allow the screen recording request. |
| Android Auto opens instead | Disable or force stop Android Auto, then reconnect. |
| The keyboard does not appear | Tap the text field. |
| Interface too big or small | Use **Larger** or **Smaller**. |

Still stuck? Tap **Copy connection log** and include it when you ask for help.
