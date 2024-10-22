<h1 align="center" style="color: #4A90E2; font-family: Arial, sans-serif;">
  BLEShark Nano Firmware 📶
</h1>

![alt text](https://github.com/grdashark/BLEShark/blob/main/Images/BLEShark%20Nano%20Main%20Image.png?raw=true)

<p align="center" style="font-family: Arial, sans-serif; font-size: 18px;">
 <i> This project uses the BLEShark Nano development board (based on the ESP-32) to create a versatile tool for spamming Bluetooth Low Energy (BLE) and Wi-Fi networks with a sleek OLED interface.</i>
</p>

## <span style="color: #E67E22;">Updating 🛠️</span>

<p style="font-family: Arial, sans-serif;">
  ⚙️ <strong>To update your BLEShark, follow these steps:</strong>
</p>
<ol style="font-family: Arial, sans-serif;">
  <li>Open the settings menu on your BLEShark</li>
  <li>Select "Update"</li>
  <li>Everything will be completed for you!</li>
</ol>
<p style="font-family: Arial, sans-serif; font-style: italic;">
  *If you are not near your Wi-Fi network, the update will not work.*
</p>

## <span style="color: #27AE60;">Features 🚀</span>

<h3><strong>💻 Pentesting</strong></h3>
<ul style="font-family: Arial, sans-serif;">
  <li><strong>Bluetooth Low Energy (BLE) Spamming</strong>: Floods devices with spoofed BLE advertisements.</li>
  <ul style="font-family: Arial, sans-serif;">
    <li>Android spam,</li>
    <li>Windows spam,</li>
    <li>iOS spam,</li>
    <li>Samsung spam,</li>
    <li>and Spam All.</li>
  </ul>
  <li><strong>Wi-Fi Network Spamming</strong>: Spams hundreds of Wi-Fi networks with beacon packets, including:</li>
  <ul style="font-family: Arial, sans-serif;">
    <li>Rickrolls</li>
    <li>Random networks</li>
    <li>Funny networks</li>
    <li>Duplicate networks</li>
  </ul>
  <li><strong>Targeted Wi-Fi Network Spamming</strong>: Spams hundreds of the <strong>same</strong> Wi-Fi networks with beacon packets.</li>
  <li><strong>Wi-Fi Deauth Attack</strong>: Deauthenticates (kicks out) devices off a 2.4Ghz Wi-Fi network.</li>
  <li><strong>Wi-Fi Captive Portals</strong>: Create any captive portal of any HTML code. By default, it is a fake Gooooo (gle) login. This takes user-submitted passwords and saves them onto the device.</li>
  <li><strong>Bad-BT</strong>: Inject custom scripts to devices with Bluetooth.</li>
</ul>
<h3><strong>📝 Apps</strong></h3>
<ul style="font-family: Arial, sans-serif;">
  <li><strong>TikTok Scroller</strong>: Connects to your phone and will execute various functions for TikTok depending on what button you press.</li>
  <li><strong>Stopwatch</strong>: A simple stopwatch. Press [L] to reset, [S] to pause/unpause.</li>
  <li><strong>TxtViewer</strong>: View and scroll through custom text files for notes, presentations, and documentation. Supports smooth scrolling, word wrapping, and a built-in scroll bar for easy navigation.</li>
</ul>
<h3><strong>🎮 Games</strong></h3>
<ul style="font-family: Arial, sans-serif;">
  <li><strong>Flappy Bird</strong>: Fly through the pipes!</li>
  <li><strong>Space Invaders</strong>: Shoot down your enemies!</li>
  <li><strong>Pong w/AI</strong>: Try to defeat the pong AI! (unlimited ATM)</li>
  <li><strong>Breakout</strong>: Try to destroy all the blocks!</li>
</ul>
<h3><strong>⚙️ Settings</strong></h3>
<ul style="font-family: Arial, sans-serif;">
  <li><strong>Brightness</strong>: Customize your BLEShark's brightness</li>
  <li><strong>Manual Update</strong>: Manually update your device through the air.</li>
  <li><strong>Extra Settings Mode</strong>: Features include:</li>
  <ul style="font-family: Arial, sans-serif;">
    <li><strong>Change Wi-Fi Network</strong>: Change the Wi-Fi network needed for OTA updates</li>
    <li><strong>Enable/Disable Emergency Mode</strong>: Hold L+R together for 500 ms to open flappy bird anywhere in the device, just in case.</li>
    <li><strong>BLESpam Delay</strong>: Change the delay per packet in BLESpam.</li>
    <li><strong>Max Targeted Networks</strong>: Change how much targeted networks you want to create (the more, the slower they create).</li>
    <li><strong>Deauth Delay</strong>: Change the delay per packet in the deauth attack.</li>
    <li><strong>Evil Portal SSID Name</strong>: Change the Evil Portal SSID Name.</li>
    <li><strong>Get Evil Portal Creds</strong>: Get the saved credentials you recieved with Evil Portal.</li>
    <li><strong>Clear Evil Portal Creds</strong>: Clear the saved credentials you recieved with Evil Portal.</li>
    <li><strong>Check and Update</strong>: Check for updates, and update with BLEShark.</li>
    <li><strong>Enable/Disable Automatic Updates</strong>: Enable or disable auto updates. Will decrease boot time by a tiny bit.</li>
    <li><strong>Change BadBT Name</strong>: Change the BadBT device name.</li>
    <li><strong>BadBT File</strong>: Upload your duckyscript file here.</li>
    <li><strong>TxtViewer File</strong>: Upload your .txt file here.</li>
    <li><strong>Amazing UI</strong>: An amazing, modern UI with transitions and an extra dark mode on the settings page.</li>
  </ul>
</ul>
<h3><strong>😎 Other Features</strong></h3>
<ul style="font-family: Arial, sans-serif;">
  <li><strong>Emergency Mode</strong>: Hold L+R together for 500 ms to open flappy bird anywhere in the device, just in case.</li>
  <li><strong>Automatic Updates</strong>: Auto OTA updates.</li>
  <li><strong>SPIFFS System</strong>: Saves and stores almost every little configuration on the device to SPIFFS.</li>
  <li><strong>A bunch of bitmaps</strong>: Includes a bunch of bitmaps to perfect your experience in the menu.</li>
</ul>

## <span style="color: #9B59B6;">Upcoming Features 🎉</span>

<ul style="font-family: Arial, sans-serif;">
  <li><strong>Handshake Capture</strong>: Save handshakes onto a PCAP file to crack Wi-Fi passwords</li>
  <li><strong>PC Info</strong>: Connect via BLE to monitor your CPU, GPU, Memory and more—perfect for keeping an eye on your hardware while gaming or working.</li>
  <li><strong>Add some More Games</strong>: T-rex game (no internet game), racing/drifting game, ect...</li>
  <li><strong>BadUSB</strong>: Run custom BadUSB scripts (not guarenteed w/the chip on the BLEShark Nano).</li>
  <li><strong>Mini Programmable Keypad</strong>: Control shortcuts, custom keys, emojis, and others in the tiny device (you can choose ~8 different commands to your choice).</li>
  <li><strong>Captive Portal Credential Detector</strong>: When you connect your BLEShark to a hotspot or a Wi-Fi network, The Evil Portal will check if the creds are valid as the user is typing it in. We will provide different services (FB, Google, X, ect).</li>
  <li><strong>Extreme Emergency Mode</strong>: Sets gaming menu as default menu. To unlock the real menu, open a game and press a combo of buttons (or pin). This is so if people ask "what is this device?" you can say "a mini gaming device".</li>
  <li><strong>Timers</strong>: Choose from many presets, or your own custom creations.</li>
  <li><strong>Song Switcher</strong>: Connect to any device, and control the music playing (previous, next, pause, ect)!</li>
  <li><strong>Duino-Coin Mining</strong>: Mine Duino-Coin on your BLEShark.</li>
  <li><strong>Custom Apps</strong>: Create custom applications for BLEShark.</li>
</ul>

<h2 align="center" style="color: #E74C3C; font-family: Arial, sans-serif;">
  WARNING‼️
</h2>
<p align="center" style="color: #E74C3C; font-family: Arial, sans-serif; font-weight: bold;">
  <strong>Warning:</strong> This device is intended solely for security purposes. It is designed to help identify and fix vulnerabilities in BLE and Wi-Fi networks. Unauthorized use for hacking or any other malicious activity is illegal and strictly prohibited. We (the team of BLEShark) are not responsible for any misuse of this device.
</p>

<h3 align="center">
Kickstarter Campaign Launching Soon!
</h3>
