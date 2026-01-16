# 🐈 PETKIT Cat Food Stats for Tidbyt / [Tronbyt Server](https://github.com/tronbyt/server)

⚠️ I currently use the script via HomeAssistant with [TidbytAssistant](https://github.com/savdagod/TidbytAssistant) for automations. I have not yet released it in the Tidbyt Community.

😺 Needs this awesome HACS Integration to work: [home-assistant-petkit]9https://github.com/RobertD502/home-assistant-petkit) 
    Optional: Setup Helper Entity in HA for better usage.

This Pixlet applet shows recent usage statistics from your automatic feeder (e.g. Fresh Element Gemini):

- Choose Device Name
- Choose Informations to Show
- Choose Cat Pixel Art
- Upload Custom Pixel Art for Your Cats (20x16px Base64.decode())

## Preview

![Pixlet Preview](preview.gif)

## Setup

### 1. Setup Petkit HACS and follow the instructions
Install HACS on your HA Instance. Install Petkit HACS. Follow Setup Instructions there.

### 2. Setup TidbytAssistan HACS (easiest way to send custom .star to yout Tidbyt Device locally)
Install TidbytAssistan HACS. Follow Setup Instructions there.

### 3. Setup Script in HA to run cat_food_stats.star

### 4. Setup Automation in HA to trigger Display
