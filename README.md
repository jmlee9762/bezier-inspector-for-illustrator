# 🟠 Bézier Inspector  

![Overview](overview.png)

Bézier Inspector is a CEP extension for Adobe Illustrator that visualizes Bézier geometry directly on the artboard.  
Bézier Inspector는 Adobe Illustrator에서 선택한 벡터/텍스트의 Bézier 구조를 아트보드 위에 직접 표시해주는 CEP 확장입니다.

---

## ✨ Features / 주요 기능

Bézier Inspector can draw:  
Bézier Inspector는 아래 항목을 표시할 수 있습니다.

- Anchor points / 앵커 포인트
- Bézier handles / Bézier 핸들
- Handle connector lines / 핸들 연결선
- Baseline guide / 베이스라인 가이드
- x-height guide / x-height 가이드
- Cap height guide / Cap height 가이드
- Ascent guide / 어센트 가이드
- Descent guide / 디센트 가이드
- Live overlay layer inside Illustrator / Illustrator 내부 라이브 오버레이 레이어

---

## 📦 Download / 다운로드

### ✅ Recommended download / 권장 다운로드

Please download the ZIP from **Releases → Assets**.  
반드시 **Releases → Assets**에서 ZIP 파일을 다운로드하세요.

Download page / 다운로드 페이지:

```text
https://github.com/jmlee9762/bezier-inspector-for-illustrator/releases/latest
```

Direct ZIP download / ZIP 직접 다운로드:

```text
https://github.com/jmlee9762/bezier-inspector-for-illustrator/releases/latest/download/BezierInspector_Free_Distribution.zip
```

Download this file / 아래 파일을 다운로드하세요:

```text
BezierInspector_Free_Distribution.zip
```

### ⚠️ Do not use the green Code button / 초록색 Code 버튼 사용 금지

Do **not** use:  
아래 방식은 사용하지 마세요:

```text
Code → Download ZIP
```

GitHub’s green **Code → Download ZIP** button downloads the whole repository, not the installer package directly.  
GitHub의 초록색 **Code → Download ZIP** 버튼은 설치 패키지가 아니라 저장소 전체를 다운로드합니다.

That can create a folder structure that does not match the installation guide.  
이 경우 폴더 구조가 설치 안내와 달라져 설치가 실패할 수 있습니다.

Use **Releases → Assets → BezierInspector_Free_Distribution.zip** instead.  
반드시 **Releases → Assets → BezierInspector_Free_Distribution.zip**에서 다운로드하세요.

---

## 🧰 Package contents / 패키지 구성

After unzipping `BezierInspector_Free_Distribution.zip`, the folder should contain:  
`BezierInspector_Free_Distribution.zip` 압축을 풀면 아래 항목이 들어 있어야 합니다.

```text
BezierInspector_Free_Distribution/
├── com.ju.bezierinspector/
│   ├── CSXS/
│   │   └── manifest.xml
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── main.js
│   ├── jsx/
│   │   └── host.jsx
│   ├── lib/
│   │   ├── CSInterface.js
│   │   └── opentype.min.js
│   └── index.html
├── install.sh
├── repair.sh
├── uninstall.sh
├── diagnostics.sh
├── install_windows.bat
├── repair_windows.bat
├── uninstall_windows.bat
├── diagnostics_windows.bat
├── scripts/
│   ├── build_zxp_self_signed.sh
│   └── install_zxp_with_upia.sh
├── tools/
│   └── PLACE_ZXPSignCmd_HERE.txt
├── zxp_out/
│   └── ZXP_OUTPUT_GOES_HERE.txt
├── zxp_source_com.ju.bezierinspector.zip
├── CHECKSUMS.txt
├── VERSION.txt
└── README.md
```

---

## ✅ Compatibility / 호환성

Expected compatibility:  
지원 예상 버전:

```text
Adobe Illustrator 2022–2026
```

Tested environment:  
테스트 환경:

```text
Adobe Illustrator 2026
macOS
Apple Silicon
```

Windows installation scripts are included for Windows 11 users.  
Windows 11 사용자를 위한 설치 스크립트도 포함되어 있습니다.

---

## 🚀 Recommended installation / 권장 설치 방법

Use the installer script for your operating system.  
사용 중인 운영체제에 맞는 설치 스크립트를 사용하세요.

---

# macOS installation / macOS 설치

## Step 1 / 1단계

Quit Adobe Illustrator completely.  
Adobe Illustrator를 완전히 종료하세요.

## Step 2 / 2단계

Unzip the downloaded file.  
다운로드한 ZIP 파일의 압축을 푸세요.

## Step 3 / 3단계

Open Terminal and go to the unzipped folder.  
Terminal을 열고 압축을 푼 폴더로 이동하세요.

Example / 예시:

```bash
cd ~/Downloads/BezierInspector_Free_Distribution
```

If your unzipped folder has a different name, drag that folder into Terminal after typing `cd `.  
압축을 푼 폴더명이 다르면, Terminal에 `cd `를 입력한 뒤 폴더를 드래그해 넣으세요.

## Step 4 / 4단계

Run the installer.  
설치 스크립트를 실행하세요.

```bash
bash install.sh
```

## Step 5 / 5단계

Restart Illustrator.  
Illustrator를 다시 실행하세요.

## Step 6 / 6단계

Open Bézier Inspector from:  
아래 메뉴에서 Bézier Inspector를 여세요.

English UI / 영어 UI:

```text
Window → Extensions (Legacy) → Bézier Inspector
```

Korean UI / 한글 UI:

```text
창 → 확장 기능(레거시) → Bézier Inspector
```

In Illustrator 2022, the menu may appear as:  
Illustrator 2022에서는 아래처럼 보일 수 있습니다.

```text
Window → Extensions → Bézier Inspector
창 → 확장 기능 → Bézier Inspector
```

---

# Windows installation / Windows 설치

## Step 1 / 1단계

Quit Adobe Illustrator completely.  
Adobe Illustrator를 완전히 종료하세요.

## Step 2 / 2단계

Unzip the downloaded file.  
다운로드한 ZIP 파일의 압축을 푸세요.

## Step 3 / 3단계

Open the unzipped folder.  
압축을 푼 폴더를 여세요.

## Step 4 / 4단계

Double-click:  
아래 파일을 더블클릭하세요.

```text
install_windows.bat
```

Do **not** run it as Administrator.  
관리자 권한으로 실행하지 마세요.

The installer uses your user CEP folder:  
설치 파일은 사용자 CEP 폴더를 사용합니다.

```text
%APPDATA%\Adobe\CEP\extensions\com.ju.bezierinspector
```

## Step 5 / 5단계

Restart Illustrator.  
Illustrator를 다시 실행하세요.

## Step 6 / 6단계

Open Bézier Inspector from:  
아래 메뉴에서 Bézier Inspector를 여세요.

Illustrator 2022:

```text
Window → Extensions → Bézier Inspector
창 → 확장 기능 → Bézier Inspector
```

Illustrator 2023–2026:

```text
Window → Extensions (Legacy) → Bézier Inspector
창 → 확장 기능(레거시) → Bézier Inspector
```

---

## 🩶 Gray panel fix / 회색 패널 복구

If the panel opens as a blank gray window, quit Illustrator first.  
패널이 빈 회색 화면으로 열리면 먼저 Illustrator를 종료하세요.

### macOS

Run:  
아래를 실행하세요.

```bash
bash repair.sh
```

### Windows

Double-click:  
아래 파일을 더블클릭하세요.

```text
repair_windows.bat
```

After the repair finishes, restart Illustrator and open Bézier Inspector again.  
복구가 끝나면 Illustrator를 다시 실행하고 Bézier Inspector를 다시 여세요.

The repair script will:  
복구 스크립트는 아래 작업을 자동으로 처리합니다.

- Re-enable CEP PlayerDebugMode / CEP PlayerDebugMode 재설정
- Remove macOS quarantine attributes / macOS quarantine 속성 제거
- Fix file permissions / 파일 권한 수정
- Clear CEP cache / CEP 캐시 삭제
- Print duplicate extension folders / 중복 설치 폴더 출력

---

## 🧪 Diagnostics / 진단 로그

If installation still fails, run the diagnostics script.  
설치 후에도 문제가 있으면 진단 스크립트를 실행하세요.

### macOS

```bash
bash diagnostics.sh
```

### Windows

Double-click:  
아래 파일을 더블클릭하세요.

```text
diagnostics_windows.bat
```

The script creates a diagnostic log that can be sent for troubleshooting.  
문제 확인용 진단 로그가 생성됩니다.

The log usually includes:  
로그에는 보통 아래 정보가 포함됩니다.

- OS version / 운영체제 버전
- CEP extension folder paths / CEP 확장 폴더 경로
- Duplicate installation check / 중복 설치 확인
- PlayerDebugMode values / PlayerDebugMode 값
- File permissions / 파일 권한
- Quarantine attributes on macOS / macOS quarantine 속성
- CEP cache status / CEP 캐시 상태

---

## 🗑 Uninstall / 제거

To uninstall Bézier Inspector, quit Illustrator first.  
Bézier Inspector를 제거하려면 먼저 Illustrator를 종료하세요.

### macOS

```bash
bash uninstall.sh
```

### Windows

Double-click:  
아래 파일을 더블클릭하세요.

```text
uninstall_windows.bat
```

This removes the installed extension folder from the CEP extensions folder.  
설치된 CEP 확장 폴더를 제거합니다.

macOS install path:  
macOS 설치 경로:

```text
~/Library/Application Support/Adobe/CEP/extensions/com.ju.bezierinspector
```

Windows install path:  
Windows 설치 경로:

```text
%APPDATA%\Adobe\CEP\extensions\com.ju.bezierinspector
```

---

## 🧩 Optional ZXP workflow / 선택 사항: ZXP 방식

This package includes scripts for creating a self-signed ZXP package.  
이 패키지에는 self-signed ZXP 패키지를 만들 수 있는 스크립트가 포함되어 있습니다.

This is optional. Most users should use the standard installer:  
이 방식은 선택 사항입니다. 대부분의 사용자는 일반 설치 방식을 사용하면 됩니다.

```text
macOS: bash install.sh
Windows: install_windows.bat
```

---

### 1. Prepare ZXPSignCmd / ZXPSignCmd 준비

Adobe `ZXPSignCmd` is not included.  
Adobe `ZXPSignCmd` 실행 파일은 포함되어 있지 않습니다.

Place the executable here:  
실행 파일을 아래 위치에 넣으세요.

```text
tools/ZXPSignCmd
```

Then make it executable on macOS:  
macOS에서는 실행 권한을 부여하세요.

```bash
chmod +x tools/ZXPSignCmd
```

---

### 2. Build self-signed ZXP / self-signed ZXP 생성

Run:  
아래를 실행하세요.

```bash
bash scripts/build_zxp_self_signed.sh
```

If successful, the ZXP file will be created here:  
성공하면 아래 위치에 ZXP 파일이 생성됩니다.

```text
zxp_out/bezier_inspector.zxp
```

---

### 3. Install ZXP with ZXPInstaller / ZXPInstaller로 설치

1. Quit Illustrator.  
   Illustrator를 종료하세요.

2. Open ZXPInstaller.  
   ZXPInstaller를 여세요.

3. Drag this file into ZXPInstaller:  
   아래 파일을 ZXPInstaller에 드래그하세요.

```text
zxp_out/bezier_inspector.zxp
```

4. Restart Illustrator.  
   Illustrator를 다시 실행하세요.

5. Open Bézier Inspector from:  
   아래 메뉴에서 여세요.

```text
Window → Extensions (Legacy) → Bézier Inspector
창 → 확장 기능(레거시) → Bézier Inspector
```

---

### 4. Install ZXP with Adobe UPIA / Adobe UPIA로 설치

If you prefer Adobe UPIA, run:  
Adobe UPIA를 사용하려면 아래를 실행하세요.

```bash
bash scripts/install_zxp_with_upia.sh
```

The script looks for Adobe Unified Plugin Installer Agent in the standard Creative Cloud Desktop path.  
이 스크립트는 Creative Cloud Desktop에 포함된 Adobe Unified Plugin Installer Agent의 기본 경로를 사용합니다.

---

## 🛠 Manual install reference / 수동 설치 참고

If you need to install manually, copy this folder:  
수동 설치가 필요하면 아래 폴더를 복사하세요.

```text
com.ju.bezierinspector
```

To the CEP extensions folder.  
CEP 확장 폴더로 복사하세요.

### macOS

```text
~/Library/Application Support/Adobe/CEP/extensions/
```

Final path:  
최종 경로:

```text
~/Library/Application Support/Adobe/CEP/extensions/com.ju.bezierinspector
```

Then run:  
그 다음 아래를 실행하세요.

```bash
defaults write com.adobe.CSXS.11 PlayerDebugMode 1
defaults write com.adobe.CSXS.12 PlayerDebugMode 1
defaults write com.adobe.CSXS.13 PlayerDebugMode 1

EXT="$HOME/Library/Application Support/Adobe/CEP/extensions/com.ju.bezierinspector"
xattr -dr com.apple.quarantine "$EXT"
chmod -R u+rwX "$EXT"
rm -rf "$HOME/Library/Caches/CSXS/cep_cache"
```

### Windows

```text
%APPDATA%\Adobe\CEP\extensions\
```

Final path:  
최종 경로:

```text
%APPDATA%\Adobe\CEP\extensions\com.ju.bezierinspector
```

The Windows installer script handles the registry settings automatically.  
Windows 설치 스크립트는 필요한 레지스트리 설정을 자동으로 처리합니다.

---

## ❓ Troubleshooting / 문제 해결

### The extension does not appear / 확장이 메뉴에 보이지 않음

First, make sure Illustrator was restarted after installation.  
먼저 설치 후 Illustrator를 다시 시작했는지 확인하세요.

Then run the repair script.  
그 다음 복구 스크립트를 실행하세요.

macOS:

```bash
bash repair.sh
```

Windows:

```text
repair_windows.bat
```

Then check:  
그 다음 아래 메뉴를 확인하세요.

```text
Window → Extensions (Legacy)
창 → 확장 기능(레거시)
```

In Illustrator 2022:  
Illustrator 2022에서는:

```text
Window → Extensions
창 → 확장 기능
```

---

### The panel is gray / 패널이 회색으로 뜸

Run the repair script.  
복구 스크립트를 실행하세요.

macOS:

```bash
bash repair.sh
```

Windows:

```text
repair_windows.bat
```

If it is still gray, run diagnostics.  
그래도 회색이면 진단 스크립트를 실행하세요.

macOS:

```bash
bash diagnostics.sh
```

Windows:

```text
diagnostics_windows.bat
```

Send the generated log for troubleshooting.  
생성된 로그를 문제 확인용으로 전달하세요.

---

### Browser opens index.html but Illustrator is gray / 브라우저에서는 열리지만 Illustrator에서는 회색

This usually means the issue is in the local CEP runtime environment, not the HTML file itself.  
이 경우는 보통 HTML 자체 문제가 아니라 로컬 CEP 런타임 환경 문제입니다.

Run the repair script and restart Illustrator.  
복구 스크립트를 실행한 뒤 Illustrator를 다시 시작하세요.

---

### `defaults: command not found`

This means you are running the macOS installer command in the wrong environment.  
이 메시지는 macOS용 설치 명령을 잘못된 환경에서 실행하고 있다는 뜻입니다.

If you are on Windows, do not run:  
Windows 사용자는 아래 명령을 실행하지 마세요.

```bash
bash install.sh
```

Instead, double-click:  
대신 아래 파일을 더블클릭하세요.

```text
install_windows.bat
```

If you are on macOS, use the built-in Terminal app.  
macOS 사용자는 기본 Terminal 앱에서 실행하세요.

---

## 🌐 Korean Illustrator UI / 한글판 Illustrator 안내

Bézier Inspector is expected to work with Korean Illustrator UI.  
Bézier Inspector는 한글판 Illustrator에서도 작동하도록 구성되어 있습니다.

The menu name may differ slightly depending on Illustrator version.  
Illustrator 버전에 따라 메뉴명이 조금 다를 수 있습니다.

English UI:  
영어 UI:

```text
Window → Extensions (Legacy) → Bézier Inspector
```

Korean UI:  
한글 UI:

```text
창 → 확장 기능(레거시) → Bézier Inspector
```

Illustrator 2022 may show:  
Illustrator 2022에서는 아래처럼 보일 수 있습니다.

```text
Window → Extensions → Bézier Inspector
창 → 확장 기능 → Bézier Inspector
```

---

## ⚠️ Notes / 참고

This is a free distribution build.  
이 버전은 무료 배포용 빌드입니다.

It is not a notarized macOS app installer.  
macOS notarized 앱 설치기가 아닙니다.

The previous `.app` installer approach could trigger macOS Gatekeeper warnings unless signed with an Apple Developer ID and notarized.  
기존 `.app` 설치기 방식은 Apple Developer ID로 서명/노타라이즈하지 않으면 macOS Gatekeeper 경고가 뜰 수 있습니다.

For this reason, this build uses script-based installation instead.  
그래서 이번 빌드는 스크립트 기반 설치 방식을 사용합니다.

Recommended install method:  
권장 설치 방식:

```text
macOS: bash install.sh
Windows: install_windows.bat
```

Gray panel repair:  
회색 패널 복구:

```text
macOS: bash repair.sh
Windows: repair_windows.bat
```

---

## 🧾 Version / 버전

```text
Bézier Inspector v1.0.2
Free Distribution Build
CEP Extension for Adobe Illustrator
```

---

## 🔗 Links / 링크

Repository / 저장소:

```text
https://github.com/jmlee9762/bezier-inspector-for-illustrator
```

Latest release / 최신 릴리즈:

```text
https://github.com/jmlee9762/bezier-inspector-for-illustrator/releases/latest
```

Direct download / 직접 다운로드:

```text
https://github.com/jmlee9762/bezier-inspector-for-illustrator/releases/latest/download/BezierInspector_Free_Distribution.zip
```
