# CartonLocator V2.1

Android application for locating archive cartons.

## GitHub Actions build from a phone

1. Upload the CONTENTS of this folder to the ROOT of your GitHub repository.
2. Make sure these files are visible at repository root:
   - settings.gradle.kts
   - build.gradle.kts
   - app/build.gradle.kts
   - .github/workflows/build-apk.yml
3. Open Actions.
4. Select "Build CartonLocator APK".
5. Press "Run workflow".
6. After a successful build, open the run and download the artifact "CartonLocator-APK".

The workflow installs Gradle 8.9 directly and does not require gradlew or gradle-wrapper.jar.
