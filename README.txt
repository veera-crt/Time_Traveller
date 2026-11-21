Phone upload steps (GitHub app not needed, use Chrome):
1. Unzip this file using the Files app (tap the zip > Extract).
2. Chrome > github.com > sign up / log in > menu (3 dots) > turn ON "Desktop site".
3. New repository > any name > Create.
4. "uploading an existing file" > choose index.html, package.json, capacitor.config.json > Commit.
5. Add file > Create new file. In the name box type exactly:  .github/workflows/build.yml
   Open build.yml (from this zip) in any text viewer, copy ALL, paste it in the big box > Commit.
6. Actions tab > wait for "Build APK" to finish > download artifact > install app-debug.apk.
