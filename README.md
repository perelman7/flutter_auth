# flutter_auth

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.


###CREATE FIREBASE APP

1. Create project 
2. Add android app
    - get package name (project directory -> android -> app -> src -> main -> AndroidManifest.xml -> 2-d line)
    - create the name for android application
    - call command (gradlew signingReport) in project/android app in cmd and get SHA1:
    
    Variant: debug
    Config: debug
    Store: C:\Users\User\.android\debug.keystore
    Alias: AndroidDebugKey
    MD5: value
    SHA1: value
    SHA-256: value
    Valid until: 29 ш■ы  2050 у.
    
3. Put file 'google-services.json' to project/android/app
4. Add dependencies
5. Check that project was created successfully
