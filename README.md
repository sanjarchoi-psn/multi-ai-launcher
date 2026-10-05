# multi-ai-launcher

프롬프트를 한 번 입력해 ChatGPT, Claude, Gemini, Perplexity, Grok, Copilot을 열어 주는 안드로이드용 설치형 웹앱(PWA)입니다.

## 배포 (GitHub Pages)

1. 이 저장소에 이 폴더의 파일을 전부 올립니다 (`.nojekyll`, `.well-known` 포함).
2. Settings > Pages > Source: `Deploy from a branch`, 브랜치 `main`, 폴더 `/ (root)` > Save.
3. 1~2분 뒤 https://sanjarchoi-psn.github.io/multi-ai-launcher/ 로 접속됩니다.
4. 휴대폰 Chrome에서 열고 메뉴(⋮) > 앱 설치 / 홈 화면에 추가.

## APK 변환 (선택)

- https://www.pwabuilder.com 에 위 주소를 넣고 Android 패키지를 만들 수 있습니다.
- 주소창 없는 앱(TWA)으로 열리려면 `https://도메인/.well-known/assetlinks.json` 이 도메인 루트에서 열려야 합니다.
  이 저장소는 `/multi-ai-launcher/` 하위 경로라 루트에 둘 수 없습니다. 이 경우 PWABuilder에서
  주소창이 보이는 방식으로 만들어지거나, `sanjarchoi-psn.github.io` 이름의 저장소를 따로 만들어 거기에 올려야 합니다.

## 메모

- 프롬프트와 선택 상태는 휴대폰 브라우저에만 저장됩니다.
- Gemini 앱은 프롬프트 자동 입력을 받지 않아 열린 뒤 붙여넣기가 필요합니다.
