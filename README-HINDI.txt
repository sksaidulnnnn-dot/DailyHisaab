DAILY HISAAB ANDROID APP

Is project mein aapka Daily Hisaab HTML app Android WebView app ke andar rakha gaya hai.
Data isi phone ke app storage mein save hota hai. App ka data clear/uninstall karne se pehle Backup lein.

APK banane ka aasaan tareeqa (GitHub se):
1. Is ZIP ko extract karein.
2. GitHub par naya repository banayein.
3. Is folder ki saari files repository mein upload karein.
4. Actions tab kholein aur 'Build Daily Hisaab APK' workflow chalayein.
5. Build complete hone par Daily-Hisaab-APK artifact download karein.
6. ZIP artifact kholkar app-debug.apk phone mein bhejein aur install karein.

Android Studio ho to:
1. Android Studio mein is folder ko Open karein.
2. Gradle sync hone dein.
3. Build > Build Bundle(s) / APK(s) > Build APK(s).
4. app/build/outputs/apk/debug/app-debug.apk milega.

Note: Yeh debug APK hoga. Android install karte waqt 'Install unknown apps' ki permission maang sakta hai.
