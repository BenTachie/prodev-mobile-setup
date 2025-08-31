# ProDev Mobile App 0x00

## 📱 Objective
This project demonstrates how to set up your first mobile application using the **Expo Router template**.  
You will scaffold a new React Native project with Expo, make a small UI change, run the app on a device, and document the effect of resetting the project.

---

## 🚀 Steps for Scaffolding

### 1. Navigate to the Project Directory
```
cd prodev-mobile-setup
```
### 2. Initialize a New Expo Project

- Run the Expo scaffolding command using the latest Expo Router template:
```
npx create-expo-app@latest .
```
Selected Expo Router + TypeScript template when prompted.

This generated the initial project structure with an app/ directory containing routing files.

### 3. Modify the Home Screen
Open the file:


app/(tabs)/index.tsx
Locate the default Welcome! text and replace it with:

```
<Text>First App Created</Text>
```
This confirms that the app renders correctly after modification.

### 4. Run the Application
Start the development server:

```
npx expo start

```
- iOS: Scan the QR code using the Camera app.

- Android: Scan the QR code using the Expo Go app.

The app loads with the updated text: First App Created.
---
## 🔄 Resetting the Application
### Command
```
npm run reset-project
```
### Observations
- The terminal stops the current Metro bundler process (if running).

- Metro bundler cache is cleared.

- A new development server is started with fresh settings.

- A new QR code is generated for Expo Go.

- When scanned, the app reloads from a clean bundle.

>⚠️ Note: Resetting does not remove source code or dependencies (node_modules). It only clears caches and reloads the project with a fresh state.

---
## 📂 Project Structure (key files)
```
prodev-mobile-app-0x00/
├─ app/
│  ├─ (tabs)/
│  │  └─ index.tsx      ← Home screen (modified)
│  └─ _layout.tsx       ← Tab navigation layout
├─ package.json
├─ README.md
```
---
## ✅ Summary
- Successfully scaffolded an Expo Router project with TypeScript.

- Modified the home screen to display First App Created.

- Ran the application on Expo Go using a QR code.

- Reset the project and observed cache clearing and fresh reload.

This setup forms the foundation for future mobile app development projects.