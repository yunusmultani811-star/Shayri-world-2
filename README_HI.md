# Shayari World — Android project

यह एक शुरुआती Android Studio प्रोजेक्ट है। इसमें बिना इंटरनेट के चलने वाली नमूना शायरी, category filter, language filter, Copy, Share और Favorites शामिल हैं।

## ऐप में अभी शामिल
- Love, Sad, Funny, Attitude, Friendship, Life, Motivation, Romantic, Family, Birthday, Breakup, Nature, Festival, Urdu, English
- Hindi, English और Urdu की नमूना शायरी
- Copy / Share / Favorites
- कोई विज्ञापन या analytics SDK नहीं

## APK बनाने के लिए
1. कंप्यूटर पर Android Studio इंस्टॉल करें।
2. Android Studio में **Open** चुनें और इस फ़ोल्डर `ShayariWorld` को खोलें।
3. Gradle sync पूरा होने दें। जरूरत पड़ने पर Android SDK Platform 35 और compatible JDK इंस्टॉल करें।
4. मोबाइल को USB debugging के साथ जोड़कर Run करें, या **Build > Build APK(s)** चुनें।
5. Play Store पर प्रकाशित करने के लिए APK नहीं, सामान्यतः signed Android App Bundle (AAB) चाहिए। Android Studio में **Build > Generate Signed Bundle / APK > Android App Bundle** चुनें और अपनी signing key सुरक्षित रखें।

## जरूरी बातें
- यह source project है, पहले से बना हुआ APK/AAB नहीं।
- इस वातावरण में Android SDK/Gradle build नहीं चलाया गया है; इसलिए इसे Android Studio में sync और test करना जरूरी है।
- Play Store पर प्रकाशित करने के लिए Google Play developer account, current Play Console requirements, privacy/data safety declarations, store listing, screenshots, app icon और signed AAB की जरूरत हो सकती है।
- यह शुरुआती संस्करण है। Shayari collection को और बढ़ाया जा सकता है; सभी भाषाओं में अभी पूरा संग्रह नहीं है।
