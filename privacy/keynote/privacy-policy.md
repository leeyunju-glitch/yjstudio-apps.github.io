YJ Studio (YJ Lab) · com.keynote.android

# 키노트 · KeyNote  
Privacy Policy

개인정보처리방침 · 갱신일 / Updated: 2026-11-10 · Android 0.9.0–0.9.2

## 1. 앱과 운영자

YJ Studio(YJ Lab)가 제공하는 키노트(KeyNote, Android 패키지 `com.keynote.android`)는 비밀번호와 계정 정보, 보안 메모, 비밀번호 변경 이력·정책·초안을 기기 안의 암호화 금고에 보관하는 앱입니다. 만 18세 이상 사용자를 대상으로 합니다.

## 2. 기기 안에서 처리하는 정보

사용자가 입력한 서비스명, 웹사이트 주소, 로그인 식별자, 비밀번호, 카테고리, 메모, 변경 기록·정책·진행 중인 초안을 암호화해 앱 전용 저장 공간에 보관합니다. 마스터 비밀번호 원문은 저장하지 않습니다. 금고를 열면 앱이 표시·검색·중복 비밀번호 검사를 위해 정보를 메모리에서 처리합니다. 저장 행 수와 암호문 크기 등 일부 구조 정보는 암호화 밖에 남습니다.

자동 잠금 정책, 알림 시각과 마지막 알림 전달 날짜, 생체 인증 설정 등 기기 설정은 별도로 저장합니다. 앱 언어는 Android 앱/기기 언어 설정을 이용합니다. 테마와 글자 크기는 기기 설정을 따릅니다. 키보드·화면 읽기 서비스·운영체제에는 각 제공자의 정책이 적용되므로 신뢰하는 서비스를 사용하세요.

## 3. 서버 전송·광고·분석

0.8.0에는 광고 SDK와 인터넷 권한이 없습니다. 아래 광고 설명은 0.9.0부터 적용됩니다. 금고 기능은 인터넷 없이 사용할 수 있으며, 온라인 회원 가입과 개발자 금고 서버, 자동 클라우드 동기화는 없습니다. 앱은 마스터 비밀번호, 계정·비밀번호·메모·검색어·변경 이력·백업 파일을 광고 요청에 넣지 않습니다. 개발자는 기기의 금고에 원격으로 접근하거나 잊어버린 마스터 비밀번호를 복구할 수 없습니다.

0.9.0은 홈·계정·변경 기록·설정 화면의 작은 하단 배너를 위해 Google AdMob과 User Messaging Platform(UMP)을 사용하며 인터넷에 연결합니다. Google 광고 SDK는 광고 제공·측정·부정행위 방지를 위해 IP 주소(대략적인 위치 추정에 사용될 수 있음), 앱·광고 상호작용, 진단 정보, 앱 세트 ID 등 기기 식별자를 수집·공유할 수 있습니다. 전송은 TLS로 보호됩니다. Android 광고 ID(AD_ID)와 Privacy Sandbox 광고 관련 권한은 앱에서 제외합니다. 광고 ID를 제외해도 다른 SDK 정보 처리가 모두 중단되는 것은 아닙니다.

맞춤형 광고를 요청하지 않으며, UMP가 광고 요청을 허용한 경우에만 SDK를 초기화하고 광고를 요청합니다. 지역과 설정에 따라 필요한 동의 화면을 표시하고, UMP가 요구하는 경우 앱 설정에 ‘광고 개인정보 설정’을 제공합니다. 광고가 없거나 불러오기에 실패해도 금고 기능은 사용할 수 있습니다. 광고를 누르면 금고를 잠그고 Google 또는 광고주의 화면으로 이동할 수 있으며, 해당 서비스의 방침이 적용됩니다. SDK의 정보 보관·처리와 권리 행사는 [Google 개인정보처리방침](https://policies.google.com/privacy) 및 [Google 광고 SDK 데이터 안내](https://developers.google.com/admob/android/privacy/play-data-disclosure)를 참고하세요.

0.9.1부터 Android 13 이상에서 사용자가 허용한 뒤 금고를 열면 Unity Ads가 시작됩니다. 광고는 홈·계정·변경 기록·설정 하단에 표시될 수 있으며 문맥 기반 광고를 요청합니다. 0.9.2에서는 금고 생성 화면에서 광고 데이터 처리 안내를 읽고 선택할 수 있으며, 이후 설정의 ‘광고 개인정보 설정’에서 선택을 변경할 수 있습니다. 기존에 저장한 선택은 업데이트 후에도 적용됩니다. 허용을 철회하면 새 배너 요청이 중지되고 앱을 다시 실행할 때 Unity Ads가 시작되지 않습니다. 동의 여부와 관계없이 금고를 사용할 수 있습니다.

Unity Technologies SF([개인정보 문의](mailto:DPO@unity3d.com))는 광고 제공과 측정, 앱 기능, 부정행위 방지 및 보안을 위해 IP 주소와 IP로 추정한 대략적 위치, 기기 정보와 Unity가 사용하는 식별자, 광고 상호작용 및 진단 정보를 수집하거나 공유할 수 있습니다. 허용 후 광고 SDK가 시작되거나 광고를 불러오고 표시·이용할 때 이 정보는 암호화된 연결로 전송됩니다. Unity의 개인정보처리방침에 따라 미국과 Unity 또는 그 서비스 제공업체가 운영하는 다른 국가에서 처리될 수 있으며, 처리 목적에 필요한 기간과 법률이 허용하거나 요구하는 기간 동안 보관될 수 있습니다.

Unity의 데이터 처리 및 열람·삭제 요청은 [Unity 앱 사용자 개인정보처리방침](https://unity.com/legal/game-player-and-app-user-privacy-policy)과 광고에 제공되는 개인정보 아이콘을 참고하세요. 기기 안의 금고 데이터 삭제 방법은 아래 6절에서 확인할 수 있습니다.

### Unity Ads 데이터 삭제 요청

1. KeyNote에서 Unity 광고의 개인정보 아이콘을 엽니다.
2. 표시되는 Unity 개인정보 안내에서 기기의 광고 데이터를 확인하고, 기존 광고 데이터 삭제를 요청합니다.
3. 아이콘이 표시되지 않으면 [Unity 개인정보처리방침의 권리 행사 및 연락처 안내](https://unity.com/legal/game-player-and-app-user-privacy-policy)를 이용합니다.

Unity는 기기와 연결된 광고 데이터에 대해 요청을 처리하며 신원 확인을 요청할 수 있습니다. 보안 로그의 IP 주소와 법적 의무에 필요한 정보는 Unity 방침에 따라 보관될 수 있습니다. 기기 안에 저장된 금고 데이터는 6절에 따라 직접 삭제할 수 있습니다.

## 4. 생체 인증과 알림

선택적 생체 인증은 Android 인증 창과 Keystore를 사용합니다. 앱은 지문·얼굴 이미지나 생체 원본을 받거나 저장하지 않습니다. 등록 변경 등으로 생체 키를 사용할 수 없으면 마스터 비밀번호를 사용합니다. 생체 인증은 설정에서 끌 수 있습니다.

일일 점검 알림은 사용자가 켜고 필요한 권한을 허용한 경우에만 사용합니다. 알림은 잠긴 금고를 읽지 않으며 계정명이나 비밀번호를 표시하지 않는 일반적인 점검 문구입니다. 기기 설정에서 권한을 철회하거나 앱에서 알림을 끌 수 있습니다.

## 5. 암호화 백업·복원과 외부 서비스

백업은 사용자가 선택한 저장 위치에 별도 복구 비밀번호로 암호화한 파일만 보냅니다. 복구 비밀번호는 앱에 보관하지 않습니다. 클라우드 문서 제공자를 선택하면 해당 제공자가 파일을 업로드·보관하고 파일 이름·크기·시각 등을 처리할 수 있습니다. 제공자의 정책을 확인하고 백업 파일과 복구 비밀번호를 따로 보관하세요.

복원 완료는 현재 기기의 금고 전체를 교체하며 합치지 않습니다. 마스터 비밀번호 변경이나 앱 안의 계정 삭제가 과거 백업·외부 복사본을 자동으로 변경하거나 철회하지는 않습니다. 이미 만든 백업은 해당 저장 위치에서 직접 관리해야 합니다. 마스터 비밀번호를 잊으면 미리 만든 백업과 복구 비밀번호가 필요하며, 이들까지 잃으면 복구할 수 없습니다.

웹사이트 비밀번호 변경 도우미와 개인정보처리방침은 사용자가 선택하면 외부 브라우저를 엽니다. 앱은 비밀번호나 로그인 식별자를 URL extra로 보내지 않습니다. URL 경로나 자유 메모에 비밀을 넣지 마세요. 외부 브라우저·사이트·문서 제공자에는 해당 서비스의 정책이 적용됩니다.

## 6. 보관·삭제와 이용자 통제

기기 정보는 사용자가 계정을 삭제하거나 앱 데이터를 지우거나 앱을 제거할 때까지 보관됩니다. 앱에서 계정을 편집·삭제할 수 있으며 계정 삭제 시 연결된 변경 초안·이력·정책도 삭제합니다. 앱 안의 전체 금고 삭제 메뉴는 현재 제공하지 않습니다. 전체 로컬 데이터는 Android 설정 → 앱 → KeyNote → 저장공간 → 데이터 삭제 또는 앱 제거로 삭제할 수 있습니다. 필요한 백업이 있는지 먼저 확인하세요.

자동 클라우드 백업과 자동 기기 이전은 앱 설정에서 제외합니다. 사용자가 내보낸 백업과 이미 복사한 정보는 별도로 삭제해야 합니다. 플래시·운영체제 기록·외부 복사본의 완전한 소거나 루트/변조 운영체제에 대한 보호는 보장하지 않습니다. 앱 삭제는 개발자에게 보낸 문의 메일이나 외부 제공자가 처리한 정보를 삭제하지 않습니다.

## 7. 문의·웹사이트·변경 안내

문의를 직접 보내면 답변과 후속 대응에 필요한 발신 이메일 주소와 문의 내용을 처리합니다. 목적 달성 후 불필요한 정보를 삭제하며 법령상 보관 의무가 있는 경우에는 해당 기간을 따릅니다. 마스터 비밀번호, 복구 비밀번호, 실제 계정 비밀번호 또는 백업 파일을 문의 메일에 보내지 마세요. 개인정보 관련 문의와 권리 요청도 아래 연락처로 할 수 있습니다.

이 방침은 GitHub에서 공개합니다. 페이지 접속 정보는 [GitHub 개인정보처리방침](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement)에 따라 처리될 수 있습니다. 기능이나 개인정보 처리 방식이 바뀌면 이 페이지와 갱신일을 업데이트하고 필요한 경우 앱에서도 알립니다.

운영자: YJ Studio (YJ Lab)  
지원 및 개인정보 연락처: [yjstudio.apps@gmail.com](mailto:yjstudio.apps@gmail.com)

## 1. App and developer

KeyNote (키노트, Android package `com.keynote.android`), provided by YJ Studio (YJ Lab), keeps accounts, passwords, secure notes, password-change history, policies and pending drafts in an encrypted on-device vault. The app is intended for adults aged 18 and above.

## 2. On-device information

Service names, website addresses, login identifiers, passwords, categories, notes, change history, policies and drafts you enter are encrypted in app-private storage. The master password is not stored in plaintext. While unlocked, information is processed in memory for display, search and duplicate-password checks. Some metadata, including row counts and ciphertext sizes, remains visible outside encryption.

Device preferences, including lock policies, reminder times and the last delivery date, and biometric settings are stored separately. App language uses Android app/device settings; theme and text size follow the device. Keyboards, screen readers and the operating system apply their own policies. Use trusted services.

## 3. Servers, advertising and analytics

Version 0.8.0 has no advertising SDK or Internet permission. The advertising description below applies from 0.9.0. Vault features work offline, without an online account, developer vault server or automatic cloud synchronization. The app never adds master passwords, accounts, passwords, notes, search queries, change history or backup files to advertising requests. The developer cannot remotely access your vault or recover a forgotten master password.

Version 0.9.0 uses Google AdMob and the User Messaging Platform (UMP) for small bottom banners on Home, Accounts, History and Settings and connects to the Internet. For advertising, measurement and fraud prevention, Google's ads SDK may collect and share IP addresses (which can estimate approximate location), app/ad interactions, diagnostics and device identifiers such as app set IDs. Data is encrypted in transit using TLS. The app excludes Android advertising ID (AD_ID) and Privacy Sandbox advertising permissions. Excluding the advertising ID does not stop all other SDK data processing.

The app requests non-personalized ads and initializes the ads SDK and requests ads only when UMP allows it. Required consent forms depend on your region and settings. When UMP requires a privacy options entry point, “Ad privacy choices” is available in app settings. Vault features remain usable if no ad is available or loading fails. Tapping an ad locks the vault and may open Google or an advertiser's page under that service's policies. For Google's retention, processing and rights requests, see the [Google Privacy Policy](https://policies.google.com/privacy) and [ads SDK data disclosure](https://developers.google.com/admob/android/privacy/play-data-disclosure).

Starting with 0.9.1, Unity Ads starts on Android 13 and later once you have allowed banners and opened the vault. Contextual ads can appear at the bottom of Home, Accounts, History and Settings. In 0.9.2, you can review the ad data disclosure and make a choice on the vault creation screen, then change that choice in “Ad privacy choices” in Settings. A saved choice is carried forward on update. Withdrawing permission stops new banner requests and prevents Unity Ads from starting the next time the app is launched. You can use the vault either way.

Unity Technologies SF ([privacy contact](mailto:DPO@unity3d.com)) may collect or share IP addresses and IP-based approximate location, device information and identifiers used by Unity, ad interactions and diagnostic data for ad delivery and measurement, app functionality, fraud prevention and security. After you allow banners, data is sent over an encrypted connection when the advertising SDK starts and when ads are loaded, displayed or interacted with. Under Unity's privacy policy, data may be processed in the United States and other countries where Unity or its service providers operate. Unity may retain it as necessary for those purposes or as permitted or required by applicable law.

For Unity’s processing and requests to access or delete ad data, see the [Unity Game Player and App User Privacy Policy](https://unity.com/legal/game-player-and-app-user-privacy-policy) and the privacy icon where provided in the ad. Section 6 describes how to remove on-device vault data.

### Unity Ads data deletion

1. Open the privacy icon on a Unity ad in KeyNote.
2. Review the device's ad data in the Unity disclosure and use the option to request deletion of historical ad data.
3. If the icon is unavailable, use the rights and contact instructions in the [Unity Game Player and App User Privacy Policy](https://unity.com/legal/game-player-and-app-user-privacy-policy).

Unity handles deletion requests for ad data associated with your device and may verify your identity. IP addresses in security logs and data required by law may be retained under Unity's policy. For data stored in the vault on your device, follow Section 6.

## 4. Biometrics and reminders

Optional biometrics use Android authentication and Keystore. The app receives and stores no fingerprint or face images or raw biometric templates. Use the master password if a biometric key becomes unavailable, including after enrollment changes. You can disable biometrics in Settings.

Daily review reminders are optional and require any applicable permission. They do not read the locked vault and contain general review text without account names or passwords. You can disable reminders or revoke the device notification permission.

## 5. Encrypted backup, restore and external services

Backups send only a file encrypted with a separate recovery password to a location you select. The recovery password is not retained by the app. A selected cloud document provider may upload or retain the file and process its name, size and timing. Review that provider's policy and keep the file and recovery password separately.

A completed restore replaces the entire current vault without merging. Changing the master password or deleting an account does not automatically change or revoke older backups or external copies. Manage exported backups at their storage locations. Recovering from a forgotten master password requires a previously created backup and its recovery password; losing these as well makes recovery impossible.

The website-change guide and this policy open an external browser at your request. The app adds no password or login identifier extras to the URL. Do not put secrets in URL paths or free-text notes. Browsers, websites and document providers apply their own policies.

## 6. Retention, deletion and control

On-device information remains until you delete accounts, clear app data or uninstall the app. You can edit and delete accounts; deletion also removes their linked drafts, history and policies. There is currently no in-app whole-vault deletion menu. Android Settings → Apps → KeyNote → Storage → Clear data, or uninstalling, removes the installation's local data. Check any backup you need first.

Android automatic cloud backup and automatic device transfer are excluded by app configuration. Delete exported backups and copies separately. Complete erasure from flash, operating-system records or external copies, and protection from a rooted or compromised operating system, are not guaranteed. Uninstalling does not delete support emails or information processed by external providers.

## 7. Contact, website and changes

If you contact us, we process your sender email address and message to respond and follow up. We delete information no longer needed after that purpose is fulfilled, subject to any legal retention duties. Do not email master or recovery passwords, real account passwords or backup files. Use the contact below for privacy questions or rights requests.

This policy is published on GitHub. Page visits may be processed under the [GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). We update this page and its revision date when features or data handling change and notify users in the app when needed.

Operator: YJ Studio (YJ Lab)  
Support and privacy contact: [yjstudio.apps@gmail.com](mailto:yjstudio.apps@gmail.com)

[앱별 개인정보처리방침 / Privacy policies](https://yjstudio-apps.github.io/privacy/) · YJ Studio © 2026
