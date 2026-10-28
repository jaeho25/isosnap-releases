# isoSnap releases

Windows installer for **isoSnap**, piping isometrics with accurate cut lengths.
This repository only hosts the installer. The source code is not public.

- Website and web app: https://isosnap.onorform.com/
- User guide: https://isosnap.onorform.com/guide/
- Tutorials: https://www.youtube.com/@isoSnapApp

## Download

**[Download the latest installer (isoSnap-setup.exe)](https://github.com/jaeho25/isosnap-releases/releases/latest/download/isoSnap-setup.exe)**

Earlier versions and release notes: [Releases](https://github.com/jaeho25/isosnap-releases/releases)

## What's included

One installer, and you choose what to install:

| Component | Installed to |
|---|---|
| isoSnap desktop app | `%LocalAppData%\Programs\isoSnap`, with desktop and Start menu shortcuts |
| Revit add-in for Revit 2021–2027 | `%AppData%\Autodesk\Revit\Addins\<year>` |

Revit versions found on your computer are selected automatically.

## Requirements

- Windows 10 or 11, 64-bit
- No administrator rights needed. isoSnap is installed for the current user only.
- No .NET installation needed. The runtime is included.

## Installing

1. Download `isoSnap-setup.exe` and run it.
2. **Windows protected your PC**: the installer is not code-signed yet, so Windows SmartScreen may show this warning. Click **More info**, then **Run anyway**.
3. Choose the app and the Revit versions, then finish the setup.
4. **Revit**: the first time Revit starts with the add-in, it asks whether to load an add-in that is not signed. Click **Always Load**. The **isoSnap** tab then appears on the ribbon.

Close isoSnap and Revit before installing a new version. The new version installs over the old one.

## Uninstalling

Open **Settings > Apps > Installed apps**, find **isoSnap** and uninstall it.
This removes the app, the shortcuts and the isoSnap add-in files. Your projects, catalogs and other Revit add-ins are kept.

## Contact

Questions or feedback: isosnap@onorform.com

---

## 한국어

isoSnap Windows 설치 파일을 받는 곳입니다. 소스 코드는 공개하지 않습니다.

- **[최신 설치 파일 받기(isoSnap-setup.exe)](https://github.com/jaeho25/isosnap-releases/releases/latest/download/isoSnap-setup.exe)**
- 설치 파일 하나로 **데스크톱 앱**과 **Revit 애드인(2021–2027)** 을 설치합니다. 설치할 때 원하는 것만 고를 수 있습니다.
- Windows 10/11 64비트. 관리자 권한과 .NET 설치는 필요 없습니다.
- "Windows의 PC 보호" 창이 뜨면 **추가 정보** → **실행**을 누르세요. 아직 코드 서명을 하지 않아 뜨는 경고입니다.
- Revit 을 처음 실행할 때 서명 없는 애드인을 불러올지 물으면 **Always Load**를 누르세요.
- 제거: **설정 > 앱 > 설치된 앱**에서 isoSnap 을 제거합니다. 프로젝트와 카탈로그는 지워지지 않습니다.
- 사용 가이드: https://isosnap.onorform.com/ko/guide/
- 문의: isosnap@onorform.com
