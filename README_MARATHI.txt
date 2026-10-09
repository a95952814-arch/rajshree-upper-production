Rajshree Upper Production — Android Studio Project

या ZIP मध्ये Android app चा source project आहे. हा तयार APK नाही.

APP मध्ये:
- Job Card edit/delete
- Cutting आणि Stitching entry
- Model-wise Cutting/Stitching rates
- Worker mobile number
- Stitching Entry मधून नोंद सेव्ह करून WhatsApp हिशोब उघडण्याचा पर्याय
- Model/Size-wise जोड्या आणि रक्कम
- फोनमध्ये स्थानिक डेटा साठवणे

APK तयार करण्यासाठी:
1. संगणकावर Android Studio install करा.
2. हा ZIP Extract करा.
3. Android Studio उघडा → Open → Extract केलेला Rajshree_Upper_Production_Android फोल्डर निवडा.
4. Gradle Sync पूर्ण होऊ द्या. Internet लागेल; Android SDK Platform 35 आणि आवश्यक Gradle plugin download होऊ शकतात.
5. वरच्या menu मध्ये Build → Build Bundle(s) / APK(s) → Build APK(s) निवडा.
6. Build यशस्वी झाल्यावर app/build/outputs/apk/debug/app-debug.apk येथे APK मिळेल.
7. APK मोबाईलवर पाठवा आणि install करा. फोनमध्ये "Install unknown apps" परवानगी द्यावी लागू शकते.

महत्त्वाच्या सूचना:
- हा Android Studio source project आहे; या वातावरणात Android SDK/Gradle उपलब्ध नसल्यामुळे येथे APK compile करून दिलेला नाही.
- हा app सध्या त्याच फोनवरील WebView storage मध्ये data ठेवतो. जुना Chrome prototype मधील data आपोआप या Android app मध्ये येणार नाही.
- App uninstall केल्यास app चा local data हटू शकतो. नियमित Backup वापरा.
- WhatsApp मेसेज तयार होतो; शेवटी Send बटण वापरकर्त्याने दाबायचे आहे.
- अनेक फोनवर एकच data पाहण्यासाठी Cloud/online database नंतर जोडावे लागेल.
