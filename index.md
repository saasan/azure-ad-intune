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

PC のポリシー管理はできない
↓
後述の Microsoft Intune にてデバイスを管理


## Azure AD Connect

オンプレミスの AD から Azure AD へ同期

- ユーザー
- パスワード
- グループ

### ハイブリッド Azure AD

PC がオンプレミスの AD と Azure AD 両方に参加した状態


## Microsoft 365 Apps for business

- Office アプリだけが利用可能
- Azure AD のユーザーに対してライセンスを割り当て


## Azure AD のエディション

- Free (無償)
- Office 365 アプリ (Office 365 に付属)
- Premium P1
- Premium P2


## Azure AD 有償版の機能 (主なもの)

- 条件付きアクセス (P1 以上)
  例 : アクセス元の IP アドレス制限
- リスクベースの条件付きアクセス (P2)
  例 : いつもと違う国からアクセスされたらリスクが高い
- モバイルデバイス管理 (MDM) への自動登録 (P1 以上)
  → Azure AD 参加した PC を自動で Intune へ登録可能


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

- ゼロタッチキッティング


## Microsoft Intune でできないこと



## Microsoft Intune 有償版の機能



## Microsoft Intune の制限

- デバイスは1ユーザーあたり15台まで



## 参考文献

- ひと目でわかるAzure Active Directory 第3版
  https://www.amazon.co.jp/dp/4822286592/
- ひと目でわかるIntune 改訂新版
  https://www.amazon.co.jp/dp/4296080008/


## 終わり

<!-- _class: lead -->
