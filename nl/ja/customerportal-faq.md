---

copyright:

  years: 1994, 2019

lastupdated: "2019-05-06"

keywords: IBM Cloud user, user name, portal account, cp FAQs 


subcollection: customer-portal

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:tip: .tip}
{:screen: .screen}
{:new_window: target="_blank"}
{:faq: data-hd-content-type='faq'}


# FAQ
{: #bicpfaq}

## カスタマー・ポータルの自分の資格情報を取得するには、どのようにすればよいですか?
{: #bicp_retcreds}
{: faq}

認証に IBMid を使用する場合は、初めて注文したとき、またはアカウントにユーザーとして追加されたときに、IBMid を使用して開始するためのリンクが入った E メールを受け取ります。 ユーザー名またはパスワードを紛失したり忘れたりした場合は、[IBMid のプロファイル ![外部リンク・アイコン](../icons/launch-glyph.svg)](https://www.ibm.com/account/profile){:new_window} に移動して、パスワードをリセットするか、復旧してください。 特定の情報の入力が求められます。これには、セキュリティーのための質問に対する回答の作成が含まれる場合もあります。

認証に IBMid を使用しない場合は、初めて注文したとき、または[カスタマー・ポータル ![外部リンク・アイコン](../icons/launch-glyph.svg)](https://control.softlayer.com/){:new_window} のアカウントにユーザーとして追加されたときに、カスタマー・ポータルで作業を開始するためのユーザー名と初期パスワードが入った E メールを受け取ります。 初めてログインしたら必ず、ユーザー・プロファイルを編集してパスワードを変更してください。

ログイン後にパスワードを忘れた場合は、カスタマー・ポータルのログイン画面にある**「パスワードを忘れた場合」**の機能を使用します。 ユーザー・プロファイルのセットアップ時に指定した一連のセキュリティーのための質問など、特定の情報の入力を求めるプロンプトが出されます。

ユーザー名を忘れた場合は、ユーザー名を取得できる、アカウント管理者またはマスター・ユーザーに問い合わせてください。 自分がアカウントの管理者またはマスター・ユーザーである場合は、サポートに連絡して支援を受けてください。

## IBMid とは何ですか?
{: #bicp_whatisibmid}
{: faq}

新規アカウントには、認証のために IBMid が必要です。 既存アカウントは、マイグレーション・ツールを実行して IBMid に切り替えるまで、SoftLayer のユーザー名とパスワードを引き続き認証に使用します。 SoftLayer アカウントにはマスター・ユーザーが含まれます。マスター・ユーザーには、同一アカウント内のユーザーを追加する権限があります。 

## 既存の SoftLayer アカウントをリンクするには、どのようにすればよいですか?
{: #bicp_linkbmxacct}
{: faq}

SoftLayer アカウントのマスター・ユーザーである場合は、カスタマー・ポータルにログインし、ヘッダーにある**「アカウントのリンク (Link an account)」**をクリックします。 詳しくは、[IBMid ユーザー・アカウントのリンク](/docs/account?topic=account-unifyingaccounts#unifyingaccounts)を参照してください。

## アカウントにリンクするには、既存の {{site.data.keyword.Bluemix_notm}} ユーザーである必要がありますか?
{: #bicp_bmxusertolink}
{: faq}

いいえ。新規の {{site.data.keyword.Bluemix_notm}} アカウントを作成するか、既存の {{site.data.keyword.Bluemix_notm}}  Lite アカウントまたは従量課金アカウントとしてリンクできます。

## 2 要素認証はどのように機能しますか?
{: #bicp_2fa}
{: faq}

アカウント・レベルで 2 要素認証 (2FA) 構成に影響は全くありません。 2FA は IBMid 単位ではありません。従来どおり、アカウント単位です。 IBMid が多くのアカウントに関連付けられていて、アカウント間で切り替えを行う場合、2FA を必要とする別のアカウントに切り替えるたびに ID を確認する必要があります。 これは、前のアカウントと新しいアカウントが両方とも同じ 2FA メカニズムを使用して構成されている場合でも同じです。

2FA を使用した IBMid について詳しくは、[リンクされたアカウントでの多要素認証の使用法](/docs/account?topic=account-unifyingaccounts#2fa)を参照してください。

## アカウントをリンクできるのは誰ですか?
{: #bicp_wholinkaccts}
{: faq}

SoftLayer アカウントと {{site.data.keyword.Bluemix_notm}} アカウントをリンクできるのは、{{site.data.keyword.BluSoftlayer_notm}} インフラストラクチャー・マスター・ユーザーだけです。 マスター・ユーザーの E メールが、リンクされる {{site.data.keyword.Bluemix_notm}} アカウントの基本所有者に関連付けられることも必要です。

## 何を使用して各コンソールにログインしますか?
{: #bicp_logineachport}
{: faq}

アカウントの請求処理はリンクされ、SoftLayer アカウントと {{site.data.keyword.Bluemix_notm}} アカウントの間を簡単に移動できますが、アカウント ID は別々のままです。

* アカウントが認証に IBMid を使用しない場合は、引き続き、SoftLayer の製品およびサービスには SoftLayer ID を使用し、{{site.data.keyword.Bluemix_notm}} の製品およびサービスには IBMid を使用します。

* アカウントが認証に IBMid を使用する場合は、IBMid を使用して SoftLayer アカウントと {{site.data.keyword.Bluemix_notm}} アカウントの両方にアクセスします。

## SoftLayer ユーザー名でログインしようとするとエラーが表示されるのはなぜですか?
{: #bicp_SLloginerror}
{: faq}

IBMid に切り替えた後、{{site.data.keyword.BluSoftlayer_notm}} インフラストラクチャー・ユーザー名でカスタマー・ポータルにログインすると、「無効なログイン資格情報が提供されました」のエラーが表示されます。 IBMid に切り替えた後は、{{site.data.keyword.BluSoftlayer_notm}} インフラストラクチャー・ユーザー名でカスタマー・ポータルにログインできなくなります。 必ず、「アカウントのログイン」ダイアログで**「IBMid でログイン」**をクリックしてください。

## IBMid でログインしようとするとエラーが表示されるのはなぜですか?
{: #bicp_IBMidloginerror}
{: faq}

IBMid でログインすると、「この IBMid または E メールを認識できません」のエラーが表示されます。 完全修飾 E メール・アドレスを入力していることを確認してください。 また、{{site.data.keyword.BluSoftlayer_notm}} インフラストラクチャー・ユーザー名を使用していないことも確認してください。

## {{site.data.keyword.BluSoftlayer_notm}} インフラストラクチャーのチーム・メンバーは、私のリンクされたアカウントにアクセスできますか?
{: #bicp_linkgiveteamaccess}
{: faq}

チーム・メンバーを {{site.data.keyword.Bluemix_notm}} に招待する必要があります。 {{site.data.keyword.Bluemix_notm}} コンソールで、**「管理」** > **「アカウント」** > **「ユーザー」**をクリックします。 リソース・グループを選択した後、{{site.data.keyword.BluSoftlayer_notm}} インフラストラクチャーのチーム・メンバーを追加できます。 招待を送信するには、その前にカスタマー・ポータルへのログインが必要な場合があります。 {{site.data.keyword.Bluemix_notm}} は {{site.data.keyword.BluSoftlayer_notm}} インフラストラクチャー・ユーザーのリストを取得します。その後、{{site.data.keyword.Bluemix_notm}} アカウントに招待するユーザーを選択できます。

## IBMid への切り替え完了の E メールはどこにありますか?
{: #bicp_ibmidswitchemail}
{: faq}

ウィザードに従って IBMid に切り替えを行って、E メールを受け取っていない場合、登録コードを含む E メールが送信されるまで、数分から数時間かかることがあります。 カスタマー・ポータルの**「ユーザー・プロファイルの編集」**ページに戻って**「E メールの再送」**をクリックし、再試行することが可能です。

## 自分のアカウントには、すべての root アクセス権限がありますか?
{: #bicp_fullrootaccaccess}
{: faq}

マスター・ユーザーと、管理者許可を持つユーザーは、カスタマー・ポータルおよび API でアカウントに対してすべての root アクセス権限を持っています。 管理者許可を持たないユーザーは、管理役割を持つユーザーの制御に従ったアクセス権限を持ちます。 管理者は[ユーザー・プロファイルの編集](/docs/customer-portal?topic=customer-portal-cp_edituserprofile#cp_edituserprofile)によって、カスタマー・ポータルからこれらの許可を更新できます。 管理者許可がなくても、自分のユーザー名をクリックすることによって、カスタマー・ポータルで自分のユーザー・プロファイルを編集できます。

## {{site.data.keyword.Bluemix_notm}} サブスクリプション・アカウントをリンクできますか?
{: #bicp_linkbmxsubacct}
{: faq}

{{site.data.keyword.Bluemix_notm}} でリンクされるアカウントはすべて、ライトまたは従量課金 (PAYG) アカウントでなければなりません。 

## アカウントをリンク解除するにはどうすればいいですか?
{: #bicp_unlinkacct}
{: faq}

リンクされたアカウントをリンク解除することはできません。


## 会社のプロファイルとは何ですか? どこで確認できますか?
{: #bicp_whatfindcompprof}
{: faq}

会社のプロファイルは、アカウント作成時に送信した情報です。会社名、住所、電話番号とともに、会社の主要な連絡先が含まれています。 この情報は、さまざまな理由で使用されるため、常に最新の状態に保つ必要があります。 アカウントの会社のプロファイルを表示する場合、または変更を依頼する場合は、[会社プロファイルの更新](/docs/customer-portal?topic=customer-portal-cp_updateprofile#cp_updateprofile) を参照してください。

## デバイスとソフトウェアのパスワードはどこにありますか?
{: #bicp_devswpw}
{: faq}

デバイスとソフトウェアのパスワードは、カスタマー・ポータル内の 2 つの場所に保管されています。 {{site.data.keyword.baremetal_short}} と {{site.data.keyword.virtualmachinesshort}} の両方の root ユーザーまたは管理ユーザーのユーザー名とパスワードなど、デバイスの資格情報を取得するには、[スナップショット・ビュー内でのデバイスの操作
](/docs/vsi?topic=virtual-servers-interacting-with-a-device-in-snapshot-view#interacting-with-a-device-in-snapshot-view)を参照してください。 カスタマー・ポータルを使用して手動で追跡されたソフトウェア資格情報を迅速に表示および取得するには、[デバイス・アクセスの管理](/docs/vsi?topic=virtual-servers-managing-device-access#managing-device-access)を参照してください。

## Web データの同期を維持するには、どのようにすればよいですか?
{: #bicp_webdatasync}
{: faq}

実サーバー間のデータ整合性の維持はお客様の責任ですが、{{site.data.keyword.BluSoftlayer_full}} では、使用料金が発生せずに同期に使用できるプライベート・ネットワークが提供されています。

## Event Management System とは何ですか?
{: #bicp_whatisems}
{: faq}

Event Management System は、インフラストラクチャーの計画外の問題と近く予定されているメンテナンス・イベントについて、{{site.data.keyword.BluSoftlayer_full}} がユーザーと情報を共有する方法を最適化するツール・セットです。 こうしたインシデントに関して、ターゲットを特定したサブスクリプション・ベースの E メール・アラートを使用して、発生したイベント・タイプを共有します。 イベントの全体的な影響と、進行中の計画外インシデント (UIP) の現行状況に関する詳細をサブスクライブ・ユーザーに提供します。

## デバイスをキャンセルできますか?
{: #bicp_candev}
{: faq}

デバイスのキャンセルは、カスタマー・ポータルでいつでも行えます。 キャンセル要求の実行について詳しくは、[デバイスのキャンセル](/docs/vsi?topic=virtual-servers-managing-virtual-servers#managing-virtual-servers)に関する箇所を参照してください。
