# Setting Up and Testing the Mobile Development Environment

## 🎯 Objective
Mobile development demands more computational resources compared to web development. To ensure a smooth development experience, we will be using the **Expo Framework** for React Native, which simplifies mobile app development and testing.

This setup ensures you can **develop, test, and iterate** on mobile apps efficiently without needing expensive hardware or complex emulator configurations.

---

## ✅ Prerequisites
Before starting, make sure you already have the following installed:

- [Node.js LTS](https://nodejs.org/en/)  
- [Visual Studio Code](https://code.visualstudio.com/) (recommended IDE)  
- A compatible operating system (**macOS, Linux, or Windows**)  

---

## 📱 Installing Expo Go on the Device
Unlike web development, mobile development often requires device emulators, which can be resource-heavy. Instead, we’ll use **Expo Go** to run and test apps directly on the **physical device**.

### Why Expo Go?
- Eliminates the need for high-end machines or complex emulator setups.  
- Works seamlessly with **both iOS and Android**.  
- Provides a cost-effective and fast way to test apps on real devices.  

### Steps to Install Expo Go
1. Visit the official Expo Go page: [https://expo.dev/go](https://expo.dev/go)  
2. Select the **latest SDK version**.  
3. Install Expo Go on the device:  
   - **Android:** [Download from Google Play Store](https://play.google.com/store/apps/details?id=host.exp.exponent)  
   - **iOS:** [Download from Apple App Store](https://apps.apple.com/app/expo-go/id982107779)  
4. Open the **Expo Go** app on the device.  
5. Create a new account or log in with an existing one.  

---

## ⚠️ Common Challenges & How to Overcome Them

- **Network Connectivity Issues**  
  Ensure the phone and development machine are on the **same Wi-Fi network**, otherwise the Expo server won’t connect.  

- **Firewall/Antivirus Blocking**  
  Some firewalls may block Expo’s connection. Allow Expo through the firewall if needed.  

- **Outdated Expo Go App**  
  Always update Expo Go to match the **latest Expo SDK version** used in the project.  

- **Performance on Older Devices**  
  While Expo Go runs on most devices, older hardware may experience slow loading. In such cases, consider using a lightweight project setup during development.  

---

## 🚀 Next Steps
With Expo Go installed and the environment set up, we’re ready to:
- Create a new Expo project  
- Start the development server (`npx expo start`)  
- Scan the QR code with Expo Go to run the app instantly on the device  

This workflow ensures a **smooth and resource-friendly mobile development experience**.
