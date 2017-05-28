List of Android Tips [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/thanhtoan1196/awesome-android)
======================
A curated list of awesome Android Tips. Feel free to contrubute.

## Other Awesome List
- [awesome-android](https://github.com/thanhtoan1196/awesome-android)
- [awesome-android-ui](https://github.com/thanhtoan1196/awesome-android-ui)
- [awesome-android-libraries](https://github.com/thanhtoan1196/awesome-android-libraries)

## Index

* [Know Your Tools](#know-your-tools)
    * [Android Studio](#android-studio)
    * [Emulator](#emulator)
    * [Vysor](#vysor)
    * [DeskDock](#deskdock)
* [Make better choices while coding](#make-better-choices-while-coding)
* [Tips regarding UI/UX](#tips-regarding-uiux)
* [Tips if you use Kotlin](#tips-if-you-use-kotlin)
* [Extra : Android Libraries built by me](#extra--android-libraries-built-by-me)
* [Translations](#translations)

## Android Studio

### Keyboard shortcuts

  |Description                                                                      |Mac                                                        |Linux/Win
  |---------------------------------------------------------------------------------|-----------------------------------------------------------|----------------------------
  |Open recently edited file                                                        |<kbd>Cmd</kbd>&nbsp;<kbd>Shift</kbd>&nbsp;<kbd>E</kbd>                 |<kbd>Ctrl</kbd>&nbsp;<kbd>Shift</kbd>&nbsp;<kbd>E</kbd>
  |Last Edited Location                                                             |<kbd>Cmd</kbd>&nbsp;<kbd>Shift</kbd>&nbsp;<kbd>Backspace</kbd>         |<kbd>Ctrl</kbd>&nbsp;<kbd>Shift</kbd>&nbsp;<kbd>Backspace</kbd>
  |Refactor This                                                                    |<kbd>Ctrl</kbd>&nbsp;<kbd>T</kbd>                                      |<kbd>Ctrl</kbd>&nbsp;<kbd>Alt</kbd>&nbsp;<kbd>Shift</kbd>&nbsp;<kbd>T</kbd>
  |Multicursor Selection                                                            |<kbd>Ctrl</kbd>&nbsp;<kbd>G</kbd>                                      |<kbd>Alt</kbd>&nbsp;<kbd>J</kbd>
  |Lookup IDE commands / Actions                                                    |<kbd>Cmd</kbd>&nbsp;<kbd>Shift</kbd>&nbsp;<kbd>A</kbd>                 |<kbd>Ctrl</kbd>&nbsp;<kbd>Shift</kbd>&nbsp;<kbd>A</kbd>
  |Open Symbol                                                                      |<kbd>Cmd</kbd>&nbsp;<kbd>Opt</kbd>&nbsp;<kbd>O</kbd>                   |<kbd>Alt</kbd>&nbsp;<kbd>Shift</kbd>&nbsp;<kbd>N</kbd>

  **Complete Keymap Guide :  [MacOSX](https://resources.jetbrains.com/assets/products/intellij-idea/IntelliJIDEA_ReferenceCard_mac.pdf) | [Linux/Win](https://resources.jetbrains.com/assets/products/intellij-idea/IntelliJIDEA_ReferenceCard.pdf)**

### Gradle
Name | Description
--- | ---
[gradle-play-publisher](https://github.com/Triple-T/gradle-play-publisher) | Gradle Plugin to upload your APK and metadata to the Google Play Store
[dexcount-gradle-plugin](https://github.com/KeepSafe/dexcount-gradle-plugin) | A Gradle plugin to report the number of method references in your APK on every build
[maven-android-sdk-deployer](https://github.com/simpligility/maven-android-sdk-deployer) | A tool to install components of the Android SDK into a Maven repository or repository manager to use with the Android Maven Plugin, Gradle and other tools

### Plugins
Name | Description
--- | ---
[android-xml-sorter](https://github.com/roana0229/android-xml-sorter) | Android Studio & IntelliJ Plugin for sort xml by name="xxx"
[android-material-design-icon-generator-plugin](https://github.com/konifar/android-material-design-icon-generator-plugin) | This plugin help you to set material design icon to your project 
[android-selector-chapek](https://github.com/inmite/android-selector-chapek) | Android Studio plugin which automatically generates drawable selectors from appropriately named resources
[android-parcelable-intellij-plugin](https://github.com/mcharmas/android-parcelable-intellij-plugin) | IntelliJ Plugin for Android Parcelable boilerplate code generation 
[adb-idea](https://github.com/pbreault/adb-idea) |  Plugin for Android Studio and Intellij IDEA that speeds up your day to day android development 
[android-butterknife-zelezny](https://github.com/avast/android-butterknife-zelezny) | Android Studio plug-in for generating ButterKnife injections from selected layout XML 
[GsonFormat](https://github.com/zzz40500/GsonFormat) | This is a plugin you can generate Json model from Json String
[CodeGlance](https://github.com/Vektah/CodeGlance) | Intelij IDEA plugin for displaying a code mini-map similar to the one found in Sublime
[ADBWIFI](https://github.com/layerlre/ADBWIFI) | ADBWIFI Android Studio plugin for debug android app over Wi-Fi 
[android-styler](https://github.com/alexzaitsev/android-styler) | Android Studio / IDEA plugin that helps to create styles 
[android-drawable-importer-intellij-plugin](https://github.com/winterDroid/android-drawable-importer-intellij-plugin) | Adds an option to IntelliJ to import drawables in different resolutions from AndroidIcons, own "drawable repos" and scale a certain image down/up to the defined resolutions 
[genymotion](https://plugins.jetbrains.com/plugin/7269-genymotion) | This plugin allows you to create and start Genymotion virtual devices from Android Studio 
[dagger-intellij-plugin](https://github.com/square/dagger-intellij-plugin) | An IntelliJ IDEA plugin for Dagger which provides insight into how injections and providers are used
[gradle-dependencies-helper](https://plugins.jetbrains.com/plugin/7299-gradle-dependencies-helper) | library is searched in Smart Code Completion by Maven repository 
[AndroidProguardPlugin](https://github.com/zhonghanwen/AndroidProguardPlugin) | Android Studio generate proguard codes
[idea-markdown](https://github.com/nicoulaj/idea-markdown) | Markdown language support for IntelliJ IDEA
[idea-multimarkdown](https://github.com/vsch/idea-multimarkdown) | Markdown language support for IntelliJ IDEA
[folding-plugin](https://github.com/dmytrodanylyk/folding-plugin) | Android File Grouping Plugin
[gradle-retrolambda](https://github.com/evant/gradle-retrolambda) | A gradle plugin for getting java lambda support in java 6, 7 and android
[idea-gitignore](https://github.com/hsz/idea-gitignore) | .ignore support plugin for IntelliJ IDEA
[checkstyle-idea](https://github.com/jshiell/checkstyle-idea) | CheckStyle plug-in for IntelliJ IDEA
[permissions-dispatcher-plugin](https://github.com/shiraji/permissions-dispatcher-plugin) | IntelliJ plugin for supporting PermissionsDispatcher
[jetbrains-wakatime](https://github.com/wakatime/jetbrains-wakatime) | IntelliJ IDEA, PyCharm, RubyMine, PhpStorm, AppCode, AndroidStudio, Gogland, Rider, & WebStorm plugin for quantifying your coding
[AndroidWiFiADB](https://github.com/pedrovgs/AndroidWiFiADB) | ntelliJ/AndroidStudio plugin which provides a button to connect your Android device over WiFi to install, run and debug your applications without a USB connected
[AndroidLocalizationer](https://github.com/westlinkin/AndroidLocalizationer) | This is a Android Studio/ IntelliJ IDEA plugin to localize your Android app, translate your string resources automactically 
[KeyPromoter](https://plugins.jetbrains.com/plugin/4455) | The plugin basically will annoy the hell out of you by showing you a big screen overlay with the key combination you should have used, if you used your mouse to execute some command to a level when you basically would start using the key combination just to avoid KeyPromoter annoying you all the time. It also has some useful features, like it will prompt you to create a key binding for a command whenever an action does not have a key binding and you have used it 3 times using your cursor
[String Manipulation](https://plugins.jetbrains.com/plugin/2162) | Provides actions for text manipulation such as Toggle case, encode/decode, sorting
[Sonar Lint](https://plugins.jetbrains.com/plugin/7973) | The plugin that provides on-the-fly feedback to developers on new bugs and quality issues injected into Java, JavaScript and PHP code
[Exynap](https://plugins.jetbrains.com/androidstudio/plugin/8600-exynap) | The plugin which helps you find and implement the code you require in an instant

### Live Templates
  + `newInstance` - Generates the static `newInstance` function inside a Fragment
  + `const` - Define a android style int constant
  + `psf` - public static final
  + `visible` - Set view visibility to VISIBLE
  + `gone` - Set view visibility to GONE
  + `noInstance` - private empty constructor to prohibit instance creation
  
  Comprehensive list of all Live Templates: **[https://github.com/keyboardsurfer/idea-live-templates](https://github.com/keyboardsurfer/idea-live-templates)**
  
### Postfix code completion

  Android Studio/IntelliJ havea special kind of code completion which allows you to write code specific to a field
  + `<expr>.null` will auto complete to `if(<expr> == null)`
  + `<expr>.nootnull` will auto complete to `if(<expr> != null)`
  + `<expr>.var` will auto complete to `T name = <expr>`
  + `<expr>.field` will auto complete to create a global field variable `field = <expr>`
  + `<ArrayExpr>.for` will auto complete to `for(T item : <Arrayexpr>)`
  + `<ArrayExpr>.fori` will auto complete to `for(int i = 0; i < <Arrayexpr>.length; i++)`
  + `<ArrayExpr>.forr` will auto complete to `for(int i = <Arrayexpr>.length - 1; i > 0 ; i--)`

  Complete list of available postfix code completion can be found at: **Settings → Editor → Postfix Templates**
  
## Tools
Name | Repository
--- | ---
[Vysor](http://www.vysor.io/) | This one needs special mention due to how useful it is. It basically is a window to your device i.e it streams and allows you to interact with your physical device on your laptop. Very useful when you are demoing your app during a presentation. You can interact with your physical device and it will be shown right in your laptop screen. It has a paid/free version, paid version is totally worth buying
[DeskDock](https://play.google.com/store/apps/details?id=com.floriandraschbacher.deskdock.free) | It enables you to control your Android device as if it was part of your desktop computer
[simplify](https://github.com/CalebFenton/simplify) | Generic Android Deobfuscator
[jadx](https://github.com/skylot/jadx) | Dex to Java decompiler
[apk2gold](https://github.com/lxdvs/apk2gold) | CLI tool for decompiling Android apps to Java. It does resources! It does Java! Its real easy!
[procyon](https://bitbucket.org/mstrobel/procyon) | Procyon is a suite of Java metaprogramming tools focused on code generation and analysis
[classyshark.com](http://classyshark.com/) |  handy Android and Java executables viewer
[backdoor-apk](https://github.com/dana-at-cp/backdoor-apk) | backdoor-apk is a shell script that simplifies the process of adding a backdoor to any Android APK file. Users of this shell script should have working knowledge of Linux, Bash, Metasploit, Apktool, the Android SDK, smali, etc. This shell script is provided as-is without warranty of any kind and is intended for educational purposes only
[enjarify](https://github.com/Storyyeller/enjarify) | Enjarify is a tool for translating Dalvik bytecode to equivalent Java bytecode. This allows Java analysis tools to analyze Android applications
[dexterity](https://github.com/rchiossi/dexterity) | Dex manipulation library
[android-classyshark](https://github.com/google/android-classyshark) | Executables (apk, multi-dex, jar) browser for Android, Java and Kotlin
[Battery Historian](https://github.com/google/battery-historian) | A tool to analyze battery consumers using Android "bugreport" files
[TinyPNG](https://tinypng.com) | Optimize your images with a perfect balance in quality and file size

## Tips

### Use shrinkResources
  ```gradle
  android {
    ...
    buildTypes {
        release {
            shrinkResources true
            minifyEnabled true
            ...
        }
    }
  }
  ```

+ **[Simulating Android killing your app in the background](https://twitter.com/Jahnold/status/759775495655333888),  run in terminal**
  `adb shell am kill`

+ **Split your apk using gradle when using Native code, do not bundle all of em together and ship!.. coz that will make you evil**

  ```gradle
  defaultConfig {
      ...

      ndk {
        abiFilters "armeabi", "armeabi-v7a", "mips", "x86"
      }
    }

  //Split into platform dependent APK
  splits {
    abi {
      enable true
      reset()
      include 'armeabi', 'armeabi-v7a', 'mips', 'x86' //select ABIs to build APKs for
      universalApk false //generate an additional APK that contains all the ABIs
    }
  }

  // map for the version code
  project.ext.versionCodes = ['armeabi': 1, 'armeabi-v7a': 2, 'mips': 5, 'x86': 8]

  // Rename with proper versioning
  android.applicationVariants.all { variant ->
    // assign different version code for each output
    variant.outputs.each { output ->
      output.versionCodeOverride =
          project.ext.versionCodes.get(output.getFilter(com.android.build.OutputFile.ABI), 0) *
              1000000 +
              android.defaultConfig.versionCode
    }
  }
  ```

+ **To force re-download of dependencies**

  ```gradle
  ./gradlew --refresh-dependencies
  ```
+ **To exclude a certain task from being run by gradle**

  Suppose you want to exclude the task `javaDoc` then use `-x` option followed by the task name, i.e `javaDoc` in this case.

  ```gradle
  ./gradlew clean build -x javaDoc
  ```
+ **To have the each subproject script name match that of the project name**

  Then add this line in settings.gradle

  ```gradle
  rootProject.children.each{
    it.buildFileName = it.name + '.gradle'
  }
  ```

  **[Checkout more gradle tips here](https://github.com/shekhargulati/gradle-tips)**

+ **Use different package name for non-release builds**
  ```gradle
    android {
        buildTypes {
            debug {
                applicationIdSuffix '.debug'
                versionNameSuffix '-DEBUG'
            }

            release {
                // ...
            }
        }
    }
  ```

+ **[If you’re creating a gradient in xml with a part being completely transparent, be really careful when using `@android:color/transparent`](https://android.jlelse.eu/android-dev-tip-3-99da754151ad#.clbqzz3zh)**

+ **[Follow a standard naming convention for your resources](http://jeroenmols.com/blog/2016/03/07/resourcenaming/)**

+ **Make use of custom gradle tasks in your build.gradle files**

  Android uses Gradle as its build system, which actually allows one to make a lot of things easy by creating tasks to automate things.
  [This reddit post enlists a lot of such useful gradle scripts](https://www.reddit.com/r/androiddev/comments/3ig3gm/show_us_your_gradle_tasks)

+ **[Use LeakCanary to detect memory leaks in your app](https://github.com/square/leakcanary)** - Its a memory leak detection library for Android and Java.

+ **Stop a running gradle build process**

    ```bash
    ./gradlew -stop
    ```

+ **Donot include both `jcenter()` & `mavenCentral()` in your `build.gradle` file**

  JCenter is a superset of MavenCentral. [[Ref tweet]](https://twitter.com/molsjeroen/status/791606774210199553)

+ **Clear your gradle cache if you think that bundled support and google play services lib in android sdk are inconsistent**

  + Goto `~/.gradle/caches/` and delete everything inside the `cache` folder.
  + Open SDK Manager and resync all support libs and google play services
  + Next re-sync your project
  + Everything should become consistent and functional.

+ **Setup handy `adb` aliases for your terminal** [[Ref Link]](https://medium.com/@jonfhancock/bash-your-way-to-better-android-development-1169bc3e0424#.8zcc4m5ch)

  Append the below **Aliases** to your `~/.bashrc` or `~/.zshrc` file, save and restart the terminal. Once saved, use them as show in **Usage** column

  |Alias|Usage
  |---|---
  |`alias screenshot="adb exec-out screencap -p > screen-$(date -j "+%s").png"`|`screenshot`
  |`alias startintent="adb devices | tail -n +2 | cut -sf 1 | xargs -I X adb -s X shell am start $1"`|`startintent https://twitter.com/nisrulz`
  |`alias apkinstall="adb devices | tail -n +2 | cut -sf 1 | xargs -I X adb -s X install -r $1"`|`apkinstall ~/Desktop/DemoApp.apk`
  |`alias rmapp="adb devices | tail -n +2 | cut -sf 1 | xargs -I X adb -s X uninstall $1"`|`rmapp com.example.demoapp`
  |`alias clearapp="adb devices | tail -n +2 | cut -sf 1 | xargs -I X adb -s X shell pm clear $1"`|`clearapp com.example.demoapp`

+ **Setup Android Studio to fail build if code contains `//STOPSHIP`** [[Ref Link]](https://www.reddit.com/r/androiddev/comments/5c8b0a/i_know_android_studio_allows_you_to_make_custom/d9uhdzt/)

  To enable the `//STOPSHIP` lint check, in your `build.gradle`

  ```gradle
  android {
  ...
      lintOptions {
          abortOnError true
          fatal 'StopShip'
      }
  }
  ```
  If you have a `//STOPSHIP` comment in your code, this will cause an error to be thrown when a release apk is generated.
  > You can turn on //STOPSHIP highlighting in Android Studio (isn't enabled by default) in
  >
  >  `Preferences` > `Editor` > `Code Style` > `Inspections`.
  >
  > Search for STOPSHIP to find the correct setting.

+ **Use `adb install -g` to grant all permissions listed in the manifest** [[More Info]](https://developer.android.com/studio/command-line/adb.html)

+ **Use [`alfi`](https://github.com/cesarferreira/alfi) to find the gradle dependency statement for a library**

  >Its basically the command line version of [Gradle, Please](gradleplease.appspot.com) which is a web hosted.

  + Run

    ```bash
    alfi name_of_library
    ```
  + Copy the desired library
  + Paste in your build.gradle

+ **Use [`dryrun`](https://github.com/cesarferreira/dryrun) to test a library directly**

  + Just Run

    ```bash
    dryrun REMOTE_GIT_URL
    ```
+ **Output unit tests directly to the console** [[Ref Link]](https://medium.com/@cesarmcferreira/mastering-the-terminal-side-of-android-development-e7520466c521#.1cw4bto7f)

  > A small neat trick to see Android unit tests logging results as they happen in the terminal.

  ```gradle
  android {
      ...
      testOptions.unitTests.all {
        testLogging {
          events 'passed', 'skipped', 'failed', 'standardOut', 'standardError'
          outputs.upToDateWhen { false }
          showStandardStreams = true
        }
      }
    }
  ```

+ **Reduce installed app size with `"android:extractNativeLibs:false"` in `<application>`** [[Ref Link]](https://medium.com/@wkalicinski/smallerapk-part-8-native-libraries-open-from-apk-fc22713861ff#.bajqmlshi)

  > This will essentially prevent the system from creating a second copy of the .so files and fix the System.loadLibrary call so it’s able to find and open native libs straight from the APK, no code changes on your part required.

+ **Selectivily execute a specific method in Android Studio** [[Ref Link]](https://twitter.com/tasomaniac/status/820019068140945408)

	![Image](img/selectiverun.gif)

+ **Did you get one of these Google Play Developer Policy Violation Emails? Worry not, generate a Privacy Policy for your android app** [[Ref ink]](https://medium.com/@ali.muzaffar/did-you-get-one-of-these-google-play-developer-policy-violation-emails-6c529ceb082d#.f10upj3fy)
    + Take a look at [App Privacy Policy Generator](https://app-privacy-policy-generator.firebaseapp.com/), a web app to generate a generic privacy policy for your app.

+ **Define a variable at build time**
  In your `build.gradle` 

  ```gradle
  android{
    defaultConfig {
      ...
      buildConfigField "String", "SERVER_ENDPOINT", '"http://www.myendpoint.com"'
      buildConfigField "int", "FOO", "52"
      buildConfigField "boolean", "LOG", "false"
      ...
    }
  }
  ```
  and then use it in code as `BuildConfig.SERVER_ENDPOINT`, `BuildConfig.FOO`,`BuildConfig.LOG`

+ **Calculate the version code and version name in your `build.gradle` ***manually***, based of version values***
  In your app's `build.gradle` 

  ```gradle
  versionMajor = 0
  versionMinor = 0
  versionPatch = 0
  versionBuild = 1


  verCode = versionMajor * 1000000 + versionMinor * 10000 + versionPatch * 100 + versionBuild
  verName = "${versionMajor}.${versionMinor}.${versionPatch}"

  // Use
  android{
    defaultConfig {
      ...
      versionCode verCode
      versionName verName
      ...
    }
  }
  ```

+ **Calculate the version code and version name in your `build.gradle` ***automatically***, based on git information***
  
  > Note: These functions go specifically inside the app's `build.gradle` and cannot be used with `ext`.

  In your app's `build.gradle` 

  ```gradle
  // Version code is calculated as the number of commits from last commit on master
  def getVersionCode = { ->
    try {
      def code = new ByteArrayOutputStream()
      exec {
        commandLine 'git', 'rev-list', 'HEAD', '--count'
        standardOutput = code
      }
      return Integer.parseInt(code.toString().trim())
    } catch (exception) {
      return "1";
    }
  }

  // Version name is Last Tag Name + No. of commits form last Tag +  short git sha
  def getVersionName = { ->
    try {
      def stdout = new ByteArrayOutputStream()
      exec {
        commandLine 'git', 'describe', '--tags', '--dirty'
        standardOutput = stdout
      }
      return stdout.toString().trim()
    } catch (exception) {
      return "0.0.0.1";
    }
  }

  // Use
  android{
    defaultConfig {
      ...
      versionCode getVersionCode()
      versionName getVersionName()
      ...
    }
  }
  ```

+ **Get the date of build as a variable***
  In your app's `build.gradle` 

  ```gradle
  // Get the date of build
  def getDateOfBuild = { -> // ISO 8601 time format
    return new Date().format("yyyy-MM-dd'T'HH:mm'Z'").toString().trim()
  }

  // then use it as a variable in BuildConfig
  android{
    defaultConfig {
      ...
      buildConfigField "String", "DATE_OF_BUILD", "\"${getDateOfBuild()}\""
    }
  }
  ```

+ **Get the Git SHA as a variable***
  In your app's `build.gradle` 

  ```gradle
  // Get the last Git Short Hash
  def getGitHash = { ->
    def stdout = new ByteArrayOutputStream()
    exec {
      commandLine 'git', 'rev-parse', '--short', 'HEAD'
      standardOutput = stdout
    }
    return stdout.toString().trim()
  }

  // then use it as a variable in BuildConfig
  android{
    defaultConfig {
      ...
      buildConfigField "String", "GIT_SHA", "\"${getGitHash()}\""
    }
  }
  ```
  > Have a look at the [Paperwork Project](https://github.com/zsoltk/paperwork), which generates build info for your Android project without breaking incremental compilation

+ **Activity LifeCycle** [[Ref Link](https://www.bignerdranch.com/blog/android-activity-lifecycle-onStop/)]

  ![diagram](img/activityStateDiagram.jpeg)
  
+ **Tip about `onSaveInstanceState()`**  
  `onSaveInstanceState()` is called **_only when the OS decides to kill the `Activity` instance_**. It will not be called when Activity is explicitly killed i.e User pressed back button or `finish()` is called from code.

+ **[Read about whats in an APK here](http://crushingcode.nisrulz.com/whats-in-the-apk/)**

+ **[Learn about various techniques involved when using ADB](https://android.jlelse.eu/do-you-like-to-adb-fcae3655b9c8)**

+ **[Input some text in an editfield in a running emulator from your keyboard ](http://fragmentedpodcast.com/episodes/77/)**
  
  ```gradle
  adb shell input text "keyboard text"
  ```
+ **Use [`areNotificationsEnabled()`](https://developer.android.com/reference/android/support/v4/app/NotificationManagerCompat.html#areNotificationsEnabled()) from [`NotificationManagerCompat`](https://developer.android.com/reference/android/support/v4/app/NotificationManagerCompat.html#areNotificationsEnabled) to detect whether your users blocked your Notifications** [[Ref Link](https://twitter.com/tasomaniac/status/851888395152392193/photo/1)]

+ **Don't hard-code encryption keys, a simple grep for `"Ljavax/crypto"` reveals them in bytecode** [[Ref Link](https://twitter.com/molsjeroen/status/851708885782204417)]

+ **Intents have a limited payload size (1Mb), don't serialize and attach entire file to it** [[Ref Link](https://twitter.com/molsjeroen/status/851353828905627648)]

+ **Always copy a file before sending it as intent URI. Receiving app could edit it & send a canceled result** [[Ref Link](https://twitter.com/molsjeroen/status/851354820883689473)]

+ **Use `http://` as scheme for app deeplinks, they are more universal & when app not installed drive users to a domain you own** [[Ref Link](https://twitter.com/molsjeroen/status/851349683440111616)]

+ **Use below to display your app launch time** [[Ref Link](https://twitter.com/molsjeroen/status/851367439996784640)]

  ```bash
  adb shell am start -W <packagename>/. <activityname>
  ```

+ **[Use Java 8 features by adding `sourceCompatibility` & `targetCompatibility` to your build.gradle file](https://developer.android.com/studio/preview/features/java8-support.html)**

  ```gradle
  android {
    ...
    compileOptions {
      sourceCompatibility JavaVersion.VERSION_1_8
      targetCompatibility JavaVersion.VERSION_1_8
    }
  }
  ```

+ **[Setup a gradle task to archive apks and proguard files on build, for backup purposes](https://medium.com/pressure-labs/a-new-devs-guide-to-google-play-sanity-4-a-groovy-script-to-save-them-all-456a12672886)**

  ```gradle
  task deployApks(type:Copy) {
      description = "Copies APKs and Proguard mappings to the deploy directory"
      def appName = "<app_name>";
      def versionDir = android.defaultConfig.versionName+"_"+android.defaultConfig.versionCode;

      println("Copies APK and Proguard to " + versionDir)

      from 'build/outputs/mapping/release/'
      include '**/mapping.txt'
      into '../.admin/deploy/' + versionDir
      rename ('mapping.txt', "${versionDir}-mapping.txt")

      from ('.') {
          exclude '**/build', '**/src'
      }

      include '*.apk'
      into '../.admin/deploy/' + versionDir
      rename ('app-release.apk', "${appName}-${versionDir}.apk")
  }
  ```

+ **[Use activity-alias or your launcher icons will disappear when renaming/moving your MainActivity](https://medium.com/@Mauin/the-case-of-disappearing-launcher-icons-657c3663b9d3)**


[<p align="right">Back to Index</p>](#index)
### ***Tips regarding UI/UX***


+ **Motion**
  + Material Design uses real-world metaphors as its foundation. Objects in the real world don't move linearly, they move in curved paths and accelerate and decelerate according to the motion's properties.
  + As such, motion should also use such properties and animate objects so that the motion feels natural rather than forced
  + For example, a car leaving the screen in a movie starts off slowly, then accelerates till it's out of the frame. Similarly, views should be interpolated using classes like AccelerateInterpolator, FastOutSlowInInterpolator, etc. [[More Info]](https://developer.android.com/reference/android/animation/TimeInterpolator.html)

+ **Typography**
    +  While custom typefaces can be used for branding, it is essential to stick to Roboto and Noto if possible, especially for body text, due to their clarity and optimistic nature.
    +  Roboto covers Latin, Greek and Cyrillic extended scripts, with Noto filling in for other language scripts [[More Info]](https://material.google.com/style/typography.html#)
    +  Weight balancing is an important aspect of typography, the fundamental concept of which is that the larger a typeface is, the less its weight should be so that it doesn't appear too thick and balances its weight with smaller typefaces of higher weights
    +  Typography should align to a 4dp baseline grid, and maintain a minimum contrast ratio of 4.5:1 based on luminance values, with a recommended ratio being 7:1.
    +  The ideal reading length for large blocks of text is 40 to 60 characters per line. Anything less is too narrow and anything more is too wide.


+ **Icons**
    + Icons should be designed at 48dp, with 1dp edges, which equates to
        +  48px by 48px at mdpi
        +  72px by 72px at hdpi
        +  96px by 96px at xhdpi
        +  144px by 144px at xxhdpi
        +  192px by 192px at xxxhdpi
    + An additional icon of 512px by 512px should be designed for use on Google Play
    + Material icons, in addition to the base icon, should contain the following important elements
        + 1dp tinted edge at the top
        + 1dp shaded edge at the bottom
        + Contact shadow - a soft shadow around all edges of raised elements
        + Finish - a soft tint to provide surface lighting, fading from upper life to lower right [[More Info]](https://material.google.com/style/icons.html#icons-product-icons)

+ **Ripples**
  + When implementing Ripple Effect use `?attr/selectableItemBackground` instead of `?android:attr` ([Ref](https://twitter.com/pareshmayani/status/772061422729637893))
  + When implementing Ripples contained within the view like Button, use ([Ref](https://twitter.com/pareshmayani/status/772268888931176448))

    ```xml
    android:background="?attr/selectableItemBackground"
    ```
  + When implementing Ripples that extend beyond the view's bounds like ImageView: ([Ref](https://twitter.com/pareshmayani/status/772269413290520576))

    ```xml
    ?attr/selectableItemBackgroundBorderless
    ```


+ **Other Points to Note**
  + Views should be aligned to Material Design's 8dp baseline grid and the keylines when possible. This gives the UI a sense of structure and hierarchy. [[More Info]](https://material.google.com/layout/metrics-keylines.html)
  + If you plan on keeping a reference to any ViewGroup (LinearLayout, FrameLayout, RelativeLayout, etc.), and you don’t want to use any methods specific to this particular type of Layout, keep it as a ViewGroup object. [[More Info]](https://android.jlelse.eu/android-pro-tip-1-443f423b4de6#.pklc9djmc)
  + While picking an accent color (if the brand already has one), pick a color complementary to the primary color so that the contrast is high enough


[<p align="right">Back to Index</p>](#index)
### ***Tips if you use [Kotlin](https://kotlinlang.org/)***

+ **Checkout [From Java to Kotlin](https://fabiomsr.github.io/from-java-to-kotlin/)**

  Cheatsheet when you come from Java to Kotlin. Very nice resource to compare the two languages.



[<p align="right">Back to Index</p>](#index)
### ***Other Resources***

+ [Adhere to the coding guidelines](https://github.com/ribot/android-guidelines/blob/master/project_and_code_guidelines.md)

+ **Listen to podcasts**
  1. [Fragmented](http://fragmentedpodcast.com/)
  2. [Android Developers Backstage](https://androidbackstage.blogspot.in/)

  There are others too, but the above two are the popular ones, you can lookup more using tag `android` on sites offering Podcast Services.

  P.S : I use [Player.fm](https://player.fm/) to listen to these podcasts. They even have an [Android Client](https://play.google.com/store/apps/details?id=fm.player&hl=en), all for FREE.

+ **Checkout [Android Dialogs](https://www.youtube.com/channel/UCMEmNnHT69aZuaOrE-dF6ug/feed)**
  Short byte sized android interview videos with experts.

+ **Checkout [CodePath Android Cliffnotes](https://guides.codepath.com/android)**

   It is the central crowdsourced resource for complete and up-to-date practical Android developer guides for any topic.

+ **[Take care about copyright](http://jeroenmols.com/blog/2016/08/03/copyright/)**

+ **Checkout new android libraries**

  [Android Arsenal](https://android-arsenal.com/) - Android developer portal with tools, libraries, and apps

+ **Checkout android example apps**
  + [Android Examples](https://github.com/nisrulz/android-examples) - Simple basic isolated apps, for budding android devs.
  + [Google Samples](https://github.com/googlesamples) - Various sample apps provided by Google
  + [Google Android Codelabs](https://codelabs.developers.google.com/?cat=Android)
  + [Google Android Codelabs](https://codelabs.developers.google.com/?cat=Android)
  + [QualityMatters](https://github.com/artem-zinnatullin/qualitymatters)
  + [Android-Testing](https://github.com/googlesamples/android-testing)
  + [Espresso-Samples](https://github.com/chiuki/espresso-samples)

+ **[Read the Effective Java by Joshua Bloch](https://www.amazon.ca/Effective-Java-2nd-Joshua-Bloch/dp/0321356683)**
  + [Cheatsheet/Summary](https://github.com/HugoMatilla/Effective-JAVA-Summary)

+ **[Subscribe to Caster.io](https://caster.io/)**

  Bite-sized Android development videos

+ **Bookmark these sites for staying upto date**
  + [Android Developers - Youtube Channel](https://www.youtube.com/user/androiddevelopers/videos)
  + [Android Niceties - UI Showcase](http://androidniceties.tumblr.com/)
  + [Material Design Specs](https://material.google.com/)
  + [Everything About Material Design](https://material.io/)
  + [Platform Version Distribution](https://developer.android.com/about/dashboards/index.html#Platform)
  + [Android Studio Release Notes](https://sites.google.com/a/android.com/tools/recent)
  + [Android Developers Blog](https://android-developers.blogspot.in/)
  + [AndroidDev-Reddit](https://www.reddit.com/r/androiddev)
  + [Github Trending Java Projects](https://github.com/trending?l=java&since=weekly)
  + [Stackoverflow-Android tag](https://stackoverflow.com/questions/tagged/android)
  + [Support Library History](https://developer.android.com/topic/libraries/support-library/revisions.html)
  + [Android Conferences](https://androidstudygroup.github.io/conferences/)
  + [Android Dev Docs](https://developer.android.com/reference/packages.html)
  + [Material Up - DesignShowcase](http://www.material.uplabs.com/)
  + [Dribbble - MaterialDeisgnShowcase](https://dribbble.com/tags/material_design)

+ **[Checkout the Testing guide](https://github.com/ravidsrk/android-testing-guide)**

+ **Use freely available mockable api points**
  + [Mockey](https://github.com/clafonta/Mockey) - A tool for testing application interactions over http, with a focus on testing web services, specifically web applications that consume XML, JSON, and HTML.
  + [JSON Placeholder](http://jsonplaceholder.typicode.com/) - Fake Online REST API for Testing and Prototyping
  + [API Studio](http://apistudio.io/) - a playground for API developers
  + [Mocky](http://www.mocky.io/) - Mock your HTTP responses to test your REST API
  + [Mockbin](http://mockbin.com) - Mockbin allows you to generate custom endpoints to test, mock, and track HTTP requests & responses between libraries, sockets and APIs.

+ **Subscribe to newsletters to stay upto date**
  + [Android Weekly](http://androidweekly.net/) - Free newsletter that helps you to stay cutting-edge with your Android Development
  + [AndroidDevDigest](https://www.androiddevdigest.com/) - A Handcrafted Weekly #AndroidDev Newsletter
  + [Infinium #AndroidSweets](https://androidsweets.ongoodbits.com/) - Fresh news from Droid zone
  + [Kotlin Weekly](http://us12.campaign-archive2.com/home/?u=f39692e245b94f7fb693b6d82&id=93b2272cb6) - Free newsletter to stay uptodate with Kotlin Development

+ **[ADB/Fastboot Tools made available as a separate package by google](https://plus.google.com/+ElliottHughes/posts/U3B6H3Sejvv), download latest version for**
  + [MacOSX](https://dl.google.com/android/repository/platform-tools-latest-darwin.zip)
  + [Linux](
https://dl.google.com/android/repository/platform-tools-latest-linux.zip)
  + [Windows](https://dl.google.com/android/repository/platform-tools-latest-windows.zip)

+ **Some other awesome utility tools**
  + [Android SVG to VectorDrawable](https://inloop.github.io/svg2android/) - One VectorDrawable to rule all screen densities
  + [SQLite Viewer](https://inloop.github.io/sqlite-viewer/) - View sqlite file online
  + [Android 9-patch shadow generator](https://inloop.github.io/shadow4android/) - Tool that makes fully customizable shadows possible
  + [APK method count](https://inloop.github.io/apk-method-count/) - Tool that outputs per-package method counts
  + [Material Palette](https://www.materialpalette.com/) - Easily generate the color pallete based on material design
  + [Color Tool](https://material.io/color/#!/) - Create, share and apply color palettes to your UI
  + [Method Count](http://www.methodscount.com/) - Use this tool to avoid the dreaded 65K method limit of the DEX file format!
  + [Gradle, please](https://gradleplease.appspot.com/) - Lookup dependency reference name to include as your gradle dependencies
  + [jsonschema2pojo](http://www.jsonschema2pojo.org/) - Generate Plain Old Java Objects from JSON or JSON-Schema
  + [Android Asset Studio](http://romannurik.github.io/AndroidAssetStudio/) - A web-based set of tools for generating graphics and other assets that would eventually be in an Android application's res/ directory.
  + [Device Art Generator](https://developer.android.com/distribute/tools/promote/device-art.html) - Quickly wrap app screenshots in device artwork
  + [Google Translator Toolkit](https://translate.google.com/toolkit/list?hl=en#translations/) - Translate strings.xml files to any language and download as XML
  + [ShapeShifter](https://alexjlockwood.github.io/ShapeShifter/) - SVG path morphing animation editor.
  + [App Privacy Policy Generator](https://app-privacy-policy-generator.firebaseapp.com/) - Generate a generic privacy policy for your app for the playstore.
  + [gnirehtet](https://github.com/Genymobile/gnirehtet) - Reverse tethering for Android.

[<p align="right">Back to Index</p>](#index)