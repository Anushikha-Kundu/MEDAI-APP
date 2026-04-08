# 🏥 MedAI — AI-Powered Medical Assistant for Android

> A smart Android application that helps users check symptoms, find nearby doctors, get medical guidance, and track their health history — all in one place.

---

## 📱 Screenshots

> _Add your screenshots here_

---

## ✨ Features

### 🔍 Symptom Checker
- Select from common symptom chips or type custom symptoms
- AI-powered analysis generates a structured diagnosis report
- Results include **disease prediction**, **confidence score**, **severity level**, and **personalized recommendations**
- Colour-coded severity indicators (🔴 High / 🟡 Moderate / 🟢 Low)

### 👨‍⚕️ Find Doctor
- Browse a curated list of doctors with specialization, rating, and distance
- Search for doctors by name or specialty
- Seamlessly navigate from a diagnosis result to a relevant specialist

### 💬 Medical Support
- Enter any medical concern or condition to receive structured guidance
- AI-generated advice with actionable steps and monitoring tips
- Built-in disclaimer for responsible use

### 📋 Health History
- Tabbed view of past **Consultations**, **Prescriptions**, and **Reports**
- Organised with ViewPager2 + TabLayout for a smooth browsing experience

### 👤 User Profile
- Editable profile with name and photo
- Set profile picture from **Camera** or **Gallery**
- Data persisted locally via SharedPreferences
---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Language | Java |
| UI Framework | Android XML Layouts |
| Material Design | Material Components 1.13.0 |
| Navigation | Activity-based with Intents |
| Data Persistence | SharedPreferences |
| Lists & Grids | RecyclerView + CardView |
| Paged Views | ViewPager2 + TabLayoutMediator |
| Build System | Gradle (Kotlin DSL) |

---

## ⚙️ Requirements

- **Android Studio** Hedgehog or newer
- **Min SDK:** Android 7.0 (API 24)
- **Target SDK:** Android 16 (API 36)
- **Java** 11

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/Anushikha-Kundu/MEDAI-APP.git
```

### 2. Open in Android Studio
`File → Open → Select the MEDAI-APP folder`

### 3. Sync Gradle
Android Studio will automatically sync dependencies. Wait for the build to complete.

### 4. Run the app
Connect an Android device or start an emulator, then click **Run ▶**

---

## 🔐 Permissions

| Permission | Purpose |
|---|---|
| `CAMERA` | Capture profile photo |
| `READ_MEDIA_IMAGES` | Pick profile photo from gallery (Android 13+) |
| `READ_EXTERNAL_STORAGE` | Pick profile photo from gallery (Android 12 and below) |

---

## 🗺️ App Flow

```
Splash Screen
    └── Login / Sign Up
            └── Dashboard
                    ├── Symptom Checker → Loading → Result → Find Doctor
                    ├── Find Doctor
                    ├── Medical Support
                    └── Health History (Consultations / Prescriptions / Reports)
```

---

## 🔮 Roadmap

- [ ] Integrate a real AI/ML backend for symptom prediction
- [ ] Connect to a live doctor database / maps API
- [ ] Add push notifications for health reminders
- [ ] Implement Firebase authentication and cloud sync
- [ ] Dark mode support

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork this repository
2. Create a feature branch: `git checkout -b feature/your-feature-name`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Open a Pull Request

---

## 👩‍💻 Author

**Anushikha Kundu**  
[GitHub](https://github.com/Anushikha-Kundu)

---

> ⚠️ **Disclaimer:** MedAI is intended for informational purposes only and does not constitute medical advice. Always consult a qualified healthcare professional for diagnosis and treatment.
