# CineWave — मोबाइल से APK बनाने के चरण

1. इस ZIP को फोन में extract करें.
2. किसी Android IDE में extracted `CineWave` project खोलें.
3. Gradle sync पूरा होने दें. पहली बार dependencies डाउनलोड होने में समय लग सकता है.
4. `app` module चुनें.
5. `assembleDebug` चलाएँ.
6. APK: `app/build/outputs/apk/debug/app-debug.apk`

इस project में custom debug keystore की जरूरत नहीं है. इसलिए पहले वाले `debugConfig` signing error को हटा दिया गया है.

**Google AI Studio का “Install via USB” इस्तेमाल न करें** — वह computer से connected Android phone के लिए है.
