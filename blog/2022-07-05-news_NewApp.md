---
slug: 2022-07-05-news_NewApp
title: 2022 年 7 月 5 日(火) 新規ユーザシステムが新しくなりました
tags:
  - news
authros:
  - oogasawara
  - akatsumata
date: 2022-07-05
---

- 利用登録申請フォームの URL はこちらです。=><a href="https://sc-account.ddbj.nig.ac.jp/application/registration">利用登録申請</a>
- 申請についての説明はこちらです。=>[ユーザ登録・変更申請](/application/registration)



<table>
<tr>
<td valign="top">

初期画面

![](new_registration_JP.png)

</td>
<td valign="top">

ログイン後の最初の画面

![](login_JP.png)

</td>
</tr>
</table>


- ユーザ登録がより簡単になりました。
- 新規ユーザ登録申請フォームで、SSH 公開鍵の登録ができるようになりました。
  - これまでの手順では、新規ユーザ登録申請後、おおよそ 1 週間程度でアカウント登録証を受け取り、ユーザご自身でログインした後に SSH 公開鍵の登録を行う 2 段階方式でした。
  - しかし今後は、新規ユーザ登録申請フォームの中で SSH 公開鍵の登録も行うことができます。
- 年度末更新が容易になりました。
  - すべての項目を 1 つ 1 つ手入力する必要がなくなり、PubMedID を入力するだけで論文情報が取得・自動入力できるようになります。


### 注意事項

- 公開鍵などの設定直後は `gw2.ddbj.nig.ac.jp` からログインして頂けますようお願いします。
    - 現在、新しいユーザ登録システムへの移行作業を行っております。そのため、新しいゲートウェイ `gw2.ddbj.nig.ac.jp` への公開鍵登録については即時設定が反映されますが、古い方のゲートウェイ `gw.ddbj.nig.ac.jp` へ設定が反映されるまでに１日程度かかります。次回の定期メンテナンス（12 月）の際に、古いゲートウェイにも即時設定が反映されるようシステムを改修する予定です。
- `sc2.ddbj.nig.ac.jp` サーバは閉鎖しました。



