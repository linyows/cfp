CloudNative Days 2019 in Fukuoka
==

https://cloudnativedays.jp/cndf2019/

Title
--

KubernetesとHashiCorp Vaultで作るCloudNativeな秘密情報管理

Abstract (400 char)
--

Kubernetesの特徴にImmutable Infrastructureがあります。
例えば「コンテナを1度起動したら終了するまでコンテナ内部の状態を変えないこと」をKubernetesがシステムデザインとして期待していて、
不変なコンテナで複雑性を排除をすることで、Kubernetesは、システムのあるべき姿維持する自己修復機能を提供しています。

このように、Kubernetesは新しいアーキテクチャとともに今までにない利便性を私たちに提供してくれますが、
この上で実行されるアプリケーションに必要な秘匿情報や資格情報の扱いもまた変える必要があります。

本セッションでは、秘密情報を統合管理するソフトウェアであるHashiCorp Vaultを使って、
使用者のロールやポリシーの設定など、正しく管理する方法をお話しします。
また、Self HostedなKubernetesとVaultを連携して便利に使用する方法についても合わせてご紹介する予定です。

Meta
--

subject | contet
--- | ---
Category | Architecture Design
Talk Format | Breakout 40minutes
Audience Level | Intermediate
Target | Architect, Developer
Execution Phase | Production
Whether it can be published | All OK
Language | JA
Job | Principal Engineer
Org | GMO Pepabo, Inc.

Bio
--

整備技術と開発力でGMOペパボ技術基盤チームを支え、OCTOPASSやDEWYなど現場の問題を解決するOSSの開発者。
