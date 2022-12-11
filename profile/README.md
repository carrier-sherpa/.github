### 프로젝트 주제
당신의 여행을 무거운 짐에서 해방시켜주는 앱입니다.

### 타겟층
저희 프로젝트는 다음과 같은 사람들을 위해 만들어졌습니다.
* 짐 걱정 없이 여행을 하고 싶은 사람들
* 자신의 일상 (ex. 출/퇴근길, 출장 등) 에서 주변에 있는 짐을 옮겨주고 돈을 소소하게 벌고 싶은 사람들

### 다운로드 전 사전 준비사항
저희 앱을 다운 받기 위해서는 아래의 있는 개발 도구들을 다운받아야 합니다.
* Git - [Git 다운로드](https://git-scm.com/downloads)
* Flutter - [Flutter 다운로드](https://docs.flutter.dev/get-started/install)
* Android Studio - [Android studio 다운로드](https://developer.android.com/studio?gclid=Cj0KCQiAnNacBhDvARIsABnDa69Cn0aaU6apzzZifQpmJQM6KHK8pEEXppVxDwRDyOIygTAtoF3zw3EaAlT_EALw_wcB&gclsrc=aw.ds)

### 다운로드 방법
1. 먼저 [프론트엔드 Repository](https://github.com/carrier-sherpa/Sherpa_Front-End)를 git clone 한다.
```
git clone https://github.com/carrier-sherpa/Sherpa_Front-End.git
```

2. 다운받은 폴더를 Android Studio로 엽니다.

3. 다운받은 폴더 내에 lib/key.dart의 KEY값을 자신의 Google Map API Key로 설정한다.
Google Map API Key는 [공식문서](https://developers.google.com/maps/get-started)를 참조한다.
   
```
static String KEY = 'YOUR_GOOGLE_MAP_API_KEY';
```

4. 핸드폰을 컴퓨터와 무선 혹은 usb 디버깅을 통해 연결한 후 lib/main.dart를 실행해 다운받습니다.

### 관련 문서
* [프론트엔드](https://github.com/carrier-sherpa/Sherpa_Front-End)
* [백엔드](https://github.com/carrier-sherpa/Sherpa)



<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
