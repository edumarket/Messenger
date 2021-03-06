[![I am available for hire](http://relatedcode.com/github/header10.png)](http://relatedcode.com)

## OVERVIEW

This is a native iOS Messenger app, with audio/video calls and realtime chat conversations (full offline support).

---

<img src="http://relatedcode.com/screen/chat01.png" width="290">.<img src="http://relatedcode.com/screen/call1.png" width="290">.<img src="http://relatedcode.com/screen/chats2.png" width="290">
<img src="http://relatedcode.com/screen/settings2.png" width="290">.<img src="http://relatedcode.com/screen/calls.png" width="290">.<img src="http://relatedcode.com/screen/chat07.png" width="290">

---

## ADDITIONAL FEATURES
#### These features are only available as a custom development.

- Block users
- Login with SMS
- Forward messages
- Mute push notifications
- Home screen quick actions
- Status message for Group actions

## [PREMIUM FEATURES](http://relatedcode.com/premium)
#### You can purchase the Premium version [here](http://relatedcode.com/premium).

- Video call (in-app video calling over data connection)
- Audio call (in-app audio calling over data connection)
- Message queue (creating new messages while offline)
- User last active (or currently online) status info
- Switch between multiple accounts
- Spotlight search for users
- Media download network settings (Wi-Fi, Cellular or Manual)
- Cache settings for media messages (automatic/manual cleanup)
- Auto save media option
- Media message re-download option
- Dynamic password generation
- Full source code is available for all features

## KEY FEATURES

- Firebase backend (full realtime actions)
- Realm local database (full offline availability)
- AES-256 encryption
- Address Book contact sync (similar to WhatsApp)

## FEATURES

- Live chat between multiple devices
- Group chat functionality
- Private chat functionality
- Push notification support
- No backend programming is needed
- Native and easy to customize user interface
- Login with Email
- Login with Facebook
- Login with Google
- Sending text messages
- Sending pictures
- Sending videos
- Sending audio messages
- Sending current location
- Sending stickers
- Sending large emojis
- MD5 checksum for media messages
- Media file local cache
- Load earlier messages
- Typing indicator
- Message delivery receipt
- Message read receipt
- On-screen audio recording
- Save picture messages to device
- Save video messages to device
- Save audio messages to device
- Delete read and unread messages
- Realtime recent view for ongoing chats
- Archived conversation view for archived chats
- All media view for chat media files
- Picture view for multiple pictures
- Map view for shared locations
- Basic Settings view included
- Basic Profile view for users
- Edit Profile view for changing user details
- Onboarding view on signup
- Group details view for groups
- Wallpaper backgrounds for Chat view
- Call history view
- Privacy Policy view
- Terms of Service view
- Picture, video and audio upload progress indicator
- Video length limit possibility
- Copy and paste text messages
- Arbitrary message sizes
- Send/Receive sound effects
- Deployment target: iOS 9.3+
- Supported devices: iPhone 4S/5/5C/5S/5SE/6/6 Plus/6S/6S Plus/7/7 Plus

---

<img src="http://relatedcode.com/screen/groups.png" width="290">.<img src="http://relatedcode.com/screen/settings_switch.png" width="290">.<img src="http://relatedcode.com/screen/chat09.png" width="290">
<img src="http://relatedcode.com/screen/settings_cache.png" width="290">.<img src="http://relatedcode.com/screen/chat04.png" width="290">.<img src="http://relatedcode.com/screen/settings_archive1.png" width="290">

---

## REQUIREMENTS

- Xcode 8.1+
- iOS 9.3+
- ARC

## INSTALLATION

**1.,** Run `pod install` first (the CocoaPods Frameworks and Libraries are not included in the repo). If you haven't used CocoaPods before, you can get started [here](https://guides.cocoapods.org/using/getting-started.html). You might prefer to use the [CocoaPods app](https://cocoapods.org/app) instead of the command line tool.

**2.,** Create an account at [Firebase](https://firebase.google.com) and set up your [sign-in methods](https://firebase.google.com/docs/auth).

**3.,** Download `GoogleService-Info.plist` from Firebase and replace the existing file in your Xcode project.

**4.,** Replace the `FIREBASE_STORAGE` define value in `AppConstant.h`.

**5.,** For using push notification feature, create an account at [OneSignal](https://onesignal.com) and replace the `ONESIGNAL_APPID` define value in `AppConstant.h`. You will also need to [configure](https://documentation.onesignal.com/docs/generating-an-ios-push-certificate) your certificate details.

**6.,** For using audio and video call features, create an account at [Sinch](https://www.sinch.com) and replace the `SINCH_KEY` and `SINCH_SECRET` define values in `AppConstant.h`. You will also need to [configure](https://www.sinch.com/tutorials/ios8-apps-and-pushkit) your VoIP certificate details.

**7.,** For using Phone login, you will also need to have valid `SINCH_KEY` and `SINCH_SECRET` define values in `AppConstant.h`.

**8.,** For using Facebook login, register your app at [Facebook](https://developers.facebook.com/apps) and replace the existing account details in `Info.plist`. You can find some additional info about the configuration [here](https://developers.facebook.com/docs/ios/getting-started#xcode).

**9.,** For Google login configuration, check the *Implement Google Sign-In* section [here](https://firebase.google.com/docs/auth/ios/google-signin#2_implement_google_sign-in).

**10.,** Crashlytics is also added to the project. The installation details can be found [here](https://fabric.io/kits/ios/crashlytics/install). 

---

<img src="http://relatedcode.com/screen/chat05.png" width="290">.<img src="http://relatedcode.com/screen/chat12.png" width="290">.<img src="http://relatedcode.com/screen/chat06.png" width="290">
<img src="http://relatedcode.com/screen/profile2.png" width="290">.<img src="http://relatedcode.com/screen/chat08.png" width="290">.<img src="http://relatedcode.com/screen/chats3.png" width="290">

---

## CONTACT

Do you have any questions or idea? My email is: info@relatedcode.com or you can find some more info at [relatedcode.com](http://relatedcode.com)

## LICENSE

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

---

<img src="http://relatedcode.com/screen/people.png" width="290">.<img src="http://relatedcode.com/screen/call2.png" width="290">.<img src="http://relatedcode.com/screen/settings1.png" width="290">
<img src="http://relatedcode.com/screen/group.png" width="290">.<img src="http://relatedcode.com/screen/chat10.png" width="290">.<img src="http://relatedcode.com/screen/profile1.png" width="290">
<img src="http://relatedcode.com/screen/allmedia.png" width="290">.<img src="http://relatedcode.com/screen/picture1.png" width="290">.<img src="http://relatedcode.com/screen/settings_status1.png" width="290">
