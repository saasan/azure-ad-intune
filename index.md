---
marp: true
title: Azure AD と Microsoft Intune
theme: s2
headingDivider: 2
paginate: true
---

# <!-- fit --> Azure AD と<br>Microsoft Intune

<!-- _class: lead -->
<!-- _backgroundImage: url(https://marp.app/assets/hero-background.jpg) -->


## Azure AD とは？

- クラウドベースの認証サービス
- オンプレミスの Active Directory とは完全に別のもの


## Azure AD でできること

- ユーザー管理
- グループ管理
- 権限管理
- シングルサインオン (SSO)
  - マイクロソフトや他社サービスと連携
    - Microsoft 365
    - Power Automate など


## Azure AD でできないこと

<!-- _class: first-child-center -->

PC のポリシー管理
↓
後述の Microsoft Intune にてデバイスを管理


## シングルサインオン (SSO)

<!-- _class: first-child-center -->

Azure AD の アカウントで Windows 10 へログイン
↓
Microsoft 365 など
各種サービスへ自動でログイン


## Azure AD Connect

オンプレミスの AD から Azure AD へ同期
- ユーザー
- パスワード
- グループ


## Microsoft 365 (Office)

- Azure AD のユーザーに対してライセンスを割り当て
- グループへライセンスを割り当てることも可能


## Microsoft Intune とは？

- モバイルデバイス管理 (MDM)
- モバイルアプリケーション管理 (MAM)
- クラウドベースのサービス


## Microsoft Intune の対応 OS

- Windows
- Mac
- Android
- iOS


## Microsoft Intune でできること



## Microsoft Intune でできないこと



## Microsoft Intune の制限

- デバイスは1ユーザーあたり15台まで



## 参考文献

- ひと目でわかるAzure Active Directory 第3版
  https://www.amazon.co.jp/dp/4822286592/
- ひと目でわかるIntune 改訂新版
  https://www.amazon.co.jp/dp/4296080008/


## 終わり

<!-- _class: lead -->
