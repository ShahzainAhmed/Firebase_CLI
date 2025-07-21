# Firebase CLI Setup - Flutter
Run these in your terminal to install CLI

<pre>curl -sL https://firebase.tools | bash</pre>
<pre>firebase login</pre>
<pre>dart pub global activate flutterfire_cli</pre>
<pre>flutterfire configure</pre>
<pre>flutter pub add firebase_core</pre>
<pre>flutterfire configure</pre>
<pre>WidgetsFlutterBinding.ensureInitialized();
await Firebase.initializeApp(options: DefaultFirebaseOptions.currentPlatform);
runApp(const MyApp());</pre>

For iOS:
- open iOS folder in Xcode, and then go to -> Runner -> Minimum Deployments iOS 13

For Android:
- open android/app/build.gradle -> defaultConfig -> minSdk 30 or something
