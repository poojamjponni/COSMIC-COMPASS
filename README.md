# Cosmic Compass - Find Stars with Your Phone!
A super fun MIT App Inventor app that turns your phone into a star finder. Point your compass at planets, stars, the sun, or moon – it'll show you exactly where to look!


![image alt](https://github.com/poojamjponni/COSMIC-COMPASS/blob/8a29e9e7ec7c5fa38079c8876c7949204d5efebc/Screenshot%202026-01-31%20015711.png)
![image alt](https://github.com/poojamjponni/COSMIC-COMPASS/blob/66fd43ec36772e4d5ace4bea2580572d5454e32a/Screenshot%202026-01-31%20015727.png)
## 📱 What It Does
### 🧭 Live Compass – Yellow arrow points right to your target

### 🌍 GPS Magic – Uses your location for spot-on directions

### 🪐 Tons of Objects – Planets, bright stars, sun & moon

### 📊 Smart Info – Azimuth, altitude, "visible?" status

### 🎨 Cool Visuals – Spinning compass with N/E/S/W markers

### ⏱️ Real-Time Updates – Works as you turn your phone

## 🌌 What You Can Find
Planets: Mercury, Venus, Mars, Jupiter, Saturn
Bright Stars: Sirius, Vega, Arcturus, Rigel, Betelgeuse, Altair, Aldebaran, Antares, Spica, Pollux, Fomalhaut, Deneb, Regulus, Canopus, Capella
Solar System: ☀️ Sun, 🌙 Moon

## 🚀 How to Use It
Type "mars" (lowercase!) and hit "search"

App grabs your GPS + calls the API

compass appears – rotate till it points straight up


## 🛠️ Super Easy Setup

### 1. Fire up the API
pip install flask flask-cors
python simple_celestial_api.py

### 2. Check it's alive
Open http://localhost:5000/
App Inventor:

Import Cosmic_Compass.aia

Change API URL to your computer's IP (like http://192.168.1.100:5000)

Test with AI Companion app

Option 2: 

Paste simple_celestial_api.py

Hit Run → copy the URL

Update app with that URL

### 🎮 How to Play
text
1. Go outside (GPS needs sky!)
2. Type "jupiter" → Find
3. Turn phone till compass = straight up
4. Look up... there it is! 🎉
Pro Tips:

Wave phone in figure-8 to calibrate compass

Stars = nighttime only

"Visible" = above horizon


![image alt](https://github.com/poojamjponni/COSMIC-COMPASS/blob/66fd43ec36772e4d5ace4bea2580572d5454e32a/Screenshot%202026-01-31%20015846.png)
![image alt](https://github.com/poojamjponni/COSMIC-COMPASS/blob/66fd43ec36772e4d5ace4bea2580572d5454e32a/Screenshot%202026-01-31%20015859.png)
![image alt](https://github.com/poojamjponni/COSMIC-COMPASS/blob/66fd43ec36772e4d5ace4bea2580572d5454e32a/Screenshot%202026-01-31%20015911.png)
![image alt](https://github.com/poojamjponni/COSMIC-COMPASS/blob/66fd43ec36772e4d5ace4bea2580572d5454e32a/Screenshot%202026-01-31%20020056.png)
![image alt](https://github.com/poojamjponni/COSMIC-COMPASS/blob/66fd43ec36772e4d5ace4bea2580572d5454e32a/Screenshot%202026-01-31%20020113.png)
![image alt](https://github.com/poojamjponni/COSMIC-COMPASS/blob/66fd43ec36772e4d5ace4bea2580572d5454e32a/Screenshot%202026-01-31%20020125.png)
![image alt](https://github.com/poojamjponni/COSMIC-COMPASS/blob/66fd43ec36772e4d5ace4bea2580572d5454e32a/Screenshot%202026-01-31%20020150.png)

🧪 Test It Quick
Open api_tester.html in browser → enter API URL → test "mars" at your location.

🔧 API Endpoints 
GET /position?object=mars&lat=10.85&lon=76.27
Returns: {azimuth: 245°, altitude: 30°, status: "Visible"}
