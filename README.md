# Testarino

A manga reader for Android phones and tablets, with **Testarino Hub**, a companion app for Windows PCs. These are test builds. Thanks for trying them!

**Download:** open **[Releases](https://github.com/Rinoversal/Testarino/releases/latest)** and get the files for your devices.

## Phone or tablet (Android 11 or newer)

1. On the device, download **Testarino-….apk** from Releases and open it.
2. If Android asks, let your browser install apps, then tap **Install**.
3. Open Testarino. Tap **Sources**, then **Grant access**, so it can read your manga folder.
4. Put your manga in the **Testarino** folder on the device's internal storage, one folder per series. Then tap **Rescan**.

```
Testarino/
  Dragon Ball Z/
    Dragon Ball Z v01.cbz
    Dragon Ball Z v02.zip
  One Piece/
    Chapter 001/          <- a folder of images works too
      001.jpg
      002.jpg
```

- **Files that work:** `.cbz` and `.zip` files, and folders of JPG, PNG, WebP, GIF, AVIF or BMP images. Other files are ignored.
- **Page order:** pages follow the file names, so numbered names (`001.jpg`, `002.jpg`, …) work best.

## PC (Windows 10 or 11)

1. Download **Testarino-Hub-Setup.exe** from Releases and run it.
2. Windows may say **"Windows protected your PC"**, because test builds aren't signed. Click **More info**, then **Run anyway**, then **Install**.
3. Testarino Hub opens in its own window. In **Settings**, choose the folder your manga is in. It uses the same layout as above.
4. If Windows Firewall asks, allow it on **Private networks**.

## Connect the two

1. Keep the phone or tablet on the same Wi-Fi as the PC, with Testarino Hub open.
2. In Testarino, tap **PC**. Your PC shows up by itself: tap it.
3. On the PC, click **Allow**. Both screens show the same 4-digit number.

Once they're connected, you can:

- get manga from the PC, or send the device's manga to the PC
- read on the PC, under **Library** in Testarino Hub
- keep your place: stop reading on one, and the other opens at the same page

## Good to know

- **Panel mode** (reading panel by panel) only works on volumes that went through the panel detector, and the detector isn't part of this test build. Page mode works on everything.
- Closing Testarino Hub's window keeps it running in the tray, near the clock. Right-click its icon to quit.
- The phone and the PC talk to each other directly over your Wi-Fi. Nothing goes to the internet.

## Found a problem?

Open an **[issue](https://github.com/Rinoversal/Testarino/issues)**, or message whoever sent you this link. Say which device you used, what you tapped, and what happened. Screenshots help a lot.
