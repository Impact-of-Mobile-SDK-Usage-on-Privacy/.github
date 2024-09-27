# The Impact of Mobile SDK Usage on Privacy and Data Protection

This is the artifact respository to our publication `The Impact of Mobile SDK Usage on Privacy and Data Protection` accepted at PETS'25.
If you find this code helpful or the paper relevant to your work please cite us using the following bibtex

```
@inproceedings{PETS:Koch:2025,
 title={The Impact of Default Mobile SDK Usage on Privacy and Data Protection},
 author={Koch, Simon and Karl, Manuel and Kirchner, Robin and Wessels, Malte and Paschke, Anne and Johns, Martin},
 booktitle={Privacy Enhancing Technologies Symposium (PETS)},
 year={2025},
}
```

## Contents

During our research, we developed ten Android and iOS applications utilizing 5 different analytics and advertising SDKs.
We measured the traffic of those default implementations using the [scala-appanalyzer]() and analyzed the collected traffic using the [scala-plotalyzed]().
Both tools are constantly developed and managed using [their own org]().
For instructions on how to conduct measurements and analysis using the tools refer to that org.

This organization contains the [measurement]() and [analysis]() specific plugins as well as the code of our sample applications in separate repositories for the differen SDKs and OS.
While each code compiles we replaced the identifiers used for each SDK with placeholders as those are tied to us personally.
Thus, to successfully run the apps you have to create your own account.
Furthermore, developing and deploying iOS applications requires an Apple Developer Account and Apple hardware to run the corresponding development tools.
Due to those hindrances we only provide the code as is and only inquire for the `available` artifact level.

## Analytics Apps

| SDK  | Android | iOS |
|------|---------|-----|
|   | [repo]()  | [repo]()  |
|   | [repo]()  | [repo]()  |
|   | [repo]()  | [repo]()  |
|   | [repo]()  | [repo]()  |
|   | [repo]()  | [repo]()  |

## Advertisement Apps

| SDK  | Android | iOS |
|------|---------|-----|
| Unity3d  | [repo](https://github.com/Impact-of-Mobile-SDK-Usage-on-Privacy/Unity3DAds-android)  | [repo](https://github.com/Impact-of-Mobile-SDK-Usage-on-Privacy/Unity3DAds-ios)  |
| FacebookAds  | [repo](https://github.com/Impact-of-Mobile-SDK-Usage-on-Privacy/FacebookAds-android)  | [repo](https://github.com/Impact-of-Mobile-SDK-Usage-on-Privacy/FacebookAds-ios)  |
| AdMob  | [repo](https://github.com/Impact-of-Mobile-SDK-Usage-on-Privacy/AdMob-android)  | [repo](https://github.com/Impact-of-Mobile-SDK-Usage-on-Privacy/AdMob-ios)  |
| Vungle  | [repo](https://github.com/Impact-of-Mobile-SDK-Usage-on-Privacy/Vungle-android)  | [repo](https://github.com/Impact-of-Mobile-SDK-Usage-on-Privacy/Vungle-ios)  |
| AppLovin  | [repo](https://github.com/Impact-of-Mobile-SDK-Usage-on-Privacy/AppLovin-android)  | [repo](https://github.com/Impact-of-Mobile-SDK-Usage-on-Privacy/AppLovin-ios)  |
