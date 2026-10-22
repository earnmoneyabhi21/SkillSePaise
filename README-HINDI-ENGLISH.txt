SkillSePaise Android source project (Hindi + English)
======================================================
This ZIP contains source files and an automated cloud-build workflow. It is NOT an APK yet.

Build using only your phone:
1. Sign in/create a GitHub account.
2. Create a repository named skillsepaisa-android.
3. Upload the CONTENTS of this ZIP (not the ZIP itself), including the .github/workflows folder.
4. Open the repository's Actions tab and enable Actions if prompted.
5. Run "Build SkillSePaise Android APK", or push files to the main branch.
6. When the workflow finishes successfully, open its run and download the artifact named SkillSePaise-debug-apk.
7. Extract that downloaded artifact ZIP; it contains app-debug.apk.
8. Install it on your Android phone only if you trust the build. Android may ask permission to install from your browser/file manager.

This first build is a testing APK. Samples/progress/income are stored locally; there are no accounts, real job listings, or payments. A Play Store release needs release signing, testing, privacy disclosures and a Google Play developer account. Never share passwords, OTPs, GitHub tokens, or signing keys.
If the build fails, copy the error lines from Actions and send them here.
