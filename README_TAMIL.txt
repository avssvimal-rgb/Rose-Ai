JARVIS Tamil PWA - அமைக்கும் வழிகாட்டி

கோப்புகள்:
- index.html: உங்கள் JARVIS HTML app
- manifest.webmanifest: app பெயர், icon, install அமைப்புகள்
- sw.js: offline app shell cache
- icons/: app icons

முக்கியம்:
PWA install ஆக HTTPS website தேவை. file:// மூலம் HTML-ஐ நேரடியாகத் திறந்தால் Install வேலை செய்யாது.

படிகள்:
1. ZIP-ஐ extract செய்யவும்.
2. எல்லா கோப்புகளையும் ஒரே folder அமைப்பில் HTTPS static hosting-ல் publish செய்யவும்.
3. கிடைக்கும் website URL-ஐ Android Chrome-ல் திறக்கவும்.
4. Chrome மூன்று புள்ளிகள் > Install app அல்லது Add to Home screen தேர்வு செய்யவும்.
5. Voice button பயன்படுத்தும்போது microphone permission கொடுக்கவும்.

குறிப்புகள்:
- முதல் முறை online-ல் திறந்த பிறகு app shell offline-ல் திறக்கலாம்.
- Speech recognition-க்கு internet மற்றும் browser support தேவைப்படலாம்.
- இப்போதைய version-ல் நேரம், தேதி, battery, Google, YouTube போன்ற built-in commands மட்டுமே உள்ளன; generative AI இன்னும் இணைக்கப்படவில்லை.
- தனிப்பட்ட AI API key-ஐ HTML/JavaScript-ல் நேரடியாக வைக்க வேண்டாம்.
