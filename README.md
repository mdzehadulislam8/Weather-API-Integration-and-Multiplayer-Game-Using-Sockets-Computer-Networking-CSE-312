# Weather Application & Multiplayer Tic-Tac-Toe Game

This project demonstrates two interactive applications implemented in Java:

1. **Weather Application** – Fetches real-time weather data from an online API for a user-specified city.
2. **Multiplayer Tic-Tac-Toe Game** – Allows two players to play Tic-Tac-Toe over a network using client-server socket communication.

Both projects emphasize networking, real-time updates, GUI interaction, and user-friendly experiences.

---

## 🗂️ Flowcharts

### Weather Application Flowchart

![Weather Flowchart](https://drive.google.com/uc?export=view&id=1_GBk2Z52QvTSyHdJncZ-4A-sGOa-TFX8)

### Tic-Tac-Toe Game Flowchart

![Tic-Tac-Toe Flowchart](https://drive.google.com/uc?export=view&id=1XAXYBNZgR_dYYRRZ9BOo5d1ZDi-gojEJ)  

---

## 📸 Demo Preview

### Weather Application

![Weather Application Screenshot](https://drive.google.com/uc?export=view&id=1Konf8B9c2OYEwjBYt916R_3385wZTSMZ)

### Multiplayer Tic-Tac-Toe Game

![Multiplayer Tic‑Tac‑Toe Game](https://drive.google.com/uc?export=view&id=1DZ97gLk6NBJNiViifWVl8E6TmJK1uuoN)

### Winner Screen  
![Winner Screen](https://drive.google.com/uc?export=view&id=1lk-YGs3sP_eIDopmMUvtiGWORdBOTPav)

---

## 🚀 Features

### Weather Application

* Input city name to fetch real-time weather data
* Displays temperature, humidity, and general conditions
* Handles invalid inputs and API errors gracefully

### Multiplayer Tic-Tac-Toe Game

* Two-player networked gameplay
* Real-time board updates and move validation
* Winner detection and draw handling
* Synchronization of moves between clients

---

## 🛠️ Tools & Technologies

* **Programming Language:** Java
* **GUI:** Swing
* **Networking:** Java Sockets
* **API Integration:** OpenWeatherMap API
* **IDE:** NetBeans

---

## 📁 Project Structure

```
project/
├─ WeatherApp/
│  ├─ Main.java
│  ├─ WeatherGUI.java
│  └─ APIHandler.java
├─ TicTacToeGame/
│  ├─ Server.java
│  ├─ Client.java
│  └─ GameGUI.java
├─ resources/
│  └─ images/
├─ README.md
└─ requirements.txt (if any)
```

---

## 📚 Installation & Setup

1. Ensure **Java JDK** is installed on your system.
2. Clone the repository:

   ```bash
   git clone <repository-url>
   ```
3. Open the project in your preferred Java IDE (NetBeans/Eclipse).
4. For Weather Application, configure your **OpenWeatherMap API key** in `APIHandler.java`.
5. Compile and run the applications:

   ```bash
   java Main.java        # Weather App
   java Server.java      # Tic-Tac-Toe Server
   java Client.java      # Tic-Tac-Toe Client
   ```

---

## 🧠 How to Use

### Weather Application

1. Open the app.
2. Enter a city name in the input field.
3. Click **Fetch Weather** to display temperature, humidity, and conditions.

### Tic-Tac-Toe Game

1. Start the server (`Server.java`).
2. Connect two clients (`Client.java`) to the server.
3. Players take turns making moves.
4. Game board updates in real-time, displaying winner or draw messages.

---

## 🔧 Implementation Details

### Weather Application

* **Input Handling:** GUI input for city name.
* **API Request:** GET request using Java’s `HttpURLConnection`.
* **Data Parsing:** Extract JSON data to display weather details.
* **Output Handling:** Displays results in GUI.

### Tic-Tac-Toe Game

* **Server:** Manages game state, validates moves, and broadcasts updates.
* **Client:** Displays the game board and interacts with the server for real-time moves.
* **Gameplay:** Validates moves, updates board, and determines the winner/draw.

---

## 📊 Results & Performance

* Weather Application fetches accurate real-time weather data.
* Tic-Tac-Toe game synchronizes moves between clients efficiently.
* GUI interfaces are responsive and user-friendly.
* Tested for API failures, invalid inputs, and network interruptions.

---

## ⚠️ Limitations

### Weather Application

* Relies on internet and API availability.
* Advanced weather queries are not supported.

### Tic-Tac-Toe Game

* Limited to 2 players.
* Server must be restarted for a new game session.

---

## 🌟 Future Work

### Weather Application

* Graphical visualization of weather data.
* Enhanced error handling for invalid inputs and network issues.

### Tic-Tac-Toe Game

* Support reconnecting clients during ongoing sessions.
* Extend to multiple players or AI opponents.

---

## 👨‍💻 Authors

* Md. Zehadul Islam
* Md. Abdullah Al Moin

---

## 📄 License

MIT License
