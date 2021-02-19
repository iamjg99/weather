[![Build Status](https://img.shields.io/badge/platform-Android-green)](https://www.android.com/) [![API](https://img.shields.io/badge/API-+23-brightgreen)](https://android-arsenal.com/api?level=23) [![API](https://img.shields.io/badge/license-MIT-blue)]()

<img src="http://ismailhakkiaydin.com/wp-content/uploads/2020/04/logo.png" align="center">

# Content
  - [Screenshoots](https://github.com/ihaydinn/weather-app#screenshoots)
  - [Abstract](https://github.com/ihaydinn/weather-app#abstract)
  - [Project Details](https://github.com/ihaydinn/weather-app#projects-details)
  - [Library and Tools](https://github.com/ihaydinn/weather-app#library-and-tools)
  - [How Can I Use](https://github.com/ihaydinn/weather-app#how-can-i-use)
- [Architecture](https://github.com/ihaydinn/weather-app#architecture)
- [Design](https://github.com/ihaydinn/weather-app#desing)
- [Support](https://github.com/ihaydinn/weather-app#support)
- [Contact](https://github.com/ihaydinn/weather-app#contact)
- [License](https://github.com/ihaydinn/weather-app#license)

# About Projects
### Screenshots
<img src="http://ismailhakkiaydin.com/wp-content/uploads/2020/04/weather-app-demo.gif" width="156" height="275">    <img src="http://ismailhakkiaydin.com/wp-content/uploads/2020/04/location.png" width="156" height="275">    <img src="http://ismailhakkiaydin.com/wp-content/uploads/2020/04/days.png" width="156" height="275">    <img src="http://ismailhakkiaydin.com/wp-content/uploads/2020/04/nearby.png" width="156" height="275">    <img src="http://ismailhakkiaydin.com/wp-content/uploads/2020/04/nearby_detail.png" width="156" height="275">


### Project Details
In this weather application construction, I developed using the APIs offered on OpenWeatherMap, when we log in to the application, we first encounter location permission transactions. When the permit processes are positive, we come to the home page first. Information from the location and weather details are shown to us. When we click the daily weather from the Bottom Bar menu options, the 15-day and 3-hour weather data of our location is available. When we click the other option, the weather information of the nearest cities in our location is available. There is a background feature that changes depending on the day and night situation in your location.

### How Can I Use
If you want to use this project, all you have to do is 
```
/util/Constant/
API_KEY = "Your API KEY"
```
you can follow this path and use the API you obtained from OpenWeatherMap.

### Libraries and tools
 - [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel)
 - [LiveData](https://developer.android.com/topic/libraries/architecture/livedata)
 - [DataBinding](https://developer.android.com/topic/libraries/data-binding/)
 - [Navigation](https://developer.android.com/guide/navigation/)
 - [Lifecycle](https://developer.android.com/topic/libraries/architecture/lifecycle)
 - [RxJava](https://github.com/ReactiveX/RxJava)
 - [Retrofit](https://square.github.io/retrofit/)
 - [OkHttp](https://square.github.io/okhttp/)
 - [SimpleLocation](https://github.com/delight-im/Android-SimpleLocation)
 - [Glide](https://github.com/bumptech/glide)

# Architecture
 - [MVVM](https://developer.android.com/jetpack/docs/guide)

# Design
I tried to make the design as good as I could for me :) I tried to be inspired by [Freepik](https://www.freepik.com/) and [Flaticon](https://www.flaticon.com/) sites.

