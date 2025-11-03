## ⚙️ Project Setup

The **Smart Travel Alarm** app is built using Flutter’s **Canvas Framework** for smooth, cross-platform compatibility on both **Android** and **iOS** devices.

### 🧩 Framework
- **Canvas Framework (Flutter):** Ensures consistent UI rendering and performance across platforms.

### 💾 State & Data Persistence
- **shared_preferences:** Used to store user data locally such as:
  - Saved location  
  - Onboarding completion status  
  - Configured alarms  

### 📍 Location Services
- **geolocator:** Accesses device GPS to fetch and manage the user’s **current** or **home** location.

### ⏰ Alarm Scheduling
- **flutter_local_notifications** and **timezone:**  
  Work together to schedule alarms accurately based on the user’s **local time zone**, even when traveling.

  
  **First Onboarding page**\
![Output](https://github.com/Mahfuz64/softvence_task/blob/main/Screenshot/ss%201.png))\
 **Second Onboarding page**\
![Output](https://github.com/Mahfuz64/softvence_task/blob/main/Screenshot/ss%202.png))\
 **Third Onboarding page**\
![Output](https://github.com/Mahfuz64/softvence_task/blob/main/Screenshot/ss%203.png))\
 **First location page**\
![Output](https://github.com/Mahfuz64/softvence_task/blob/main/Screenshot/ss%204.png))\
 **Alarm page**\
![Output](https://github.com/Mahfuz64/softvence_task/blob/main/Screenshot/ss%205.png))\








### 🚀 Running the Project

To set up and run the app locally, follow these steps:

```bash
# 1️⃣ Clone the repository
git clone [Your Repository URL Here]
cd smart_travel_alarm



# 2️⃣ Install dependencies
flutter pub get

# 3️⃣ Run the app
flutter run
