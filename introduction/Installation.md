# Windows
## Minimum Requirements
1. Minimum System Requirements
2. Operating Systems: Windows 7 SP1 or later (64-bit)
3. Disk Space: At least 400 MB.
4. Tools: Flutter depends on these tools being available in your environment.
5. Windows PowerShell 5.0 or newer (this is pre-installed with Windows 10).
6. Install [Git](https://git-scm.com/download/win) for windows
 

### Installing Flutter SDK
Download the latest version of [Flutter SDK ](https://docs.flutter.dev/development/tools/sdk/releases?tab=windows)

Once you download the SDK, it’s time to extract the zip file and move the contained flutter to the desired location for the Flutter SKD.

Installing Flutter to C:\Flutter

Now, locate `flutter_console.bat` inside the `flutter` directory and double-click it to start.

### Path Update
If you want to execute Flutter commands in the regular Windows console, consider the given steps to add Flutter to the `Path` environment variable:
1. Type ‘env’ in the Start Search bar and select – Edit environment variable for your account.
2. Now, check the entry called Path: under User variables.
3. If you don’t find any such entry, append the full path to flutter\bin using; as a separator from existing values.
4. Create a new user variable named `Path` with the full path to `flutter\bin` as its value if you don’t find any entry.

**Whoa!! Congratulations! 🙌 You have successfully installed Flutter on your Windows desktop.**

### Run `flutter doctor`
Now, run the following command from a console window with the Flutter directory in the above path to determine if there are any platform dependencies you need in order to finish the setup:
`C:\flutter> flutter doctor`
With the execution of this command, it will check your environment and display the Flutter installation status. Find out the below results for any additional applications you are required to install or further tasks to complement.

```
[-] Android toolchain - develop for Android devices
- Android SDK at C:\Android\sdk
✗ Android SDK is missing command line tools, [download]https://goo.gl/XxQghQ)

- Try re-installing or updating your Android SDK,
visit [installation]https://flutter.dev/setup/#android-setup) for detailed instructions.
```
**Start coding 
