# 🚀 WebhookChat

**WebhookChat** is a modern Android chat application designed to communicate with webhook endpoints. It offers a clean, customizable chat experience with advanced features for productivity, security, and user convenience. The app is built with Jetpack Compose and Material 3, supporting dynamic theming and a responsive UI.

---

## 📸 Screenshots

<img src="https://github.com/user-attachments/assets/98411c1e-bda3-45c9-964d-53e11a214df3" width="250">
<img src="https://github.com/user-attachments/assets/e2c357eb-1c98-4001-84dc-f7bd99d6c3b0" width="250">
<img src="https://github.com/user-attachments/assets/4bff730b-40f7-40d0-836b-e8fd7e5f9b38" width="250">
<img src="https://github.com/user-attachments/assets/92a49ae6-3583-4f4f-b935-628461b3b2d3" width="250">
<img src="https://github.com/user-attachments/assets/335228be-9cf2-4e7f-9a55-fa87b9cbf825" width="250">
<img src="https://github.com/user-attachments/assets/6f1c3772-cd18-4950-8309-aa0694285638" width="250">

---

## ✨ Features

### 💬 Core Chat
- **Send and Receive Messages:** Supports text, images, files, and voice messages.
- **Instant Message Display:** Outgoing messages appear instantly in the chat window, even before server confirmation.
- **🖼️ Image Previews:** View image attachments directly in the chat.
- **🎤 Voice Messages:** Hold the mic button to record and send voice messages; play received audio messages in-app.

### 🗂️ Webhook Profiles
- **Multiple Profiles:** Manage multiple webhook endpoints with unique settings.
- **🔄 Profile Switching:** Instantly switch between profiles; chat history is cleared when switching.
- **📝 Profile Editor:** Add, edit, or delete profiles with fields for name, URL, authentication, and session ID.
- **🔐 Authentication:** Supports None, Bearer Token, and Basic Auth (with separate username and password fields).
- **🆔 Session ID Management:** Auto-generate or manually regenerate session IDs for each profile.

### ⚡ Quick Actions
- **⚡ Profile-Specific Quick Actions:** Save frequently used messages as quick actions for each profile.
- **📋 Quick Action Dialog:** Access and insert quick actions into the message box for easy editing before sending.
- **🛠️ Manage Quick Actions:** Add, edit, or delete quick actions from the profile editor.

### 🎨 UI/UX & Customization
- **🎨 Material 3 Design:** Uses the latest Material 3 components and dynamic color theming (Android 12+).
- **🌓 Theme Selection:** Choose between System, Light, or Dark themes.
- **🖌️ Custom Chat Bubble Colors:** Personalize sent/received bubble and text colors with a color picker.
- **⚠️ Confirmation Dialogs:** Prevent accidental data loss with confirmation prompts for clearing chat or switching profiles.
- **📱 Modern, Responsive Layout:** Optimized for both light and dark modes.

### 🔔 Notifications
- **Smart Notifications:** Receive notifications for new messages only when the app is in the background.
- **👉 Tap to Open:** Tapping a notification brings you directly to the chat.

### 🔒 Permissions & Security
- **🔑 Runtime Permissions:** Handles permissions for notifications, microphone, and file access.
- **📁 File Size Limit:** Prevents sending files larger than 10MB.

---

## 🏁 Getting Started

### Prerequisites
- 🛠️ Android Studio (latest recommended)
- 📱 Android device or emulator (API 21+; dynamic theming on API 31+)

### Building & Running
```sh
git clone https://github.com/yourusername/WebhookChat.git
cd WebhookChat
```
Open the project in Android Studio and click **Run**, or use:
```sh
./gradlew assembleDebug
```

### Permissions
- The app will request permissions for notifications, file access, and microphone as needed.

---

## 🚦 Usage

1. **Add a Webhook Profile:**  
   Go to Settings → Add Profile. Enter the webhook URL and authentication details if needed.
2. **Start Chatting:**  
   Select a profile and begin sending messages. Attach files or record voice messages using the input bar.
3. **Quick Actions:**  
   Tap the "+" button, select "Quick Actions," and choose a saved message to insert it into the input box.
4. **Customize:**  
   Change themes and chat bubble colors in Settings.

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License

[MIT](LICENSE)

---

## 🙏 Acknowledgements

- [Jetpack Compose](https://developer.android.com/jetpack/compose)
- [Material 3](https://m3.material.io/)
- [Coil](https://coil-kt.github.io/coil/) for image loading

---
