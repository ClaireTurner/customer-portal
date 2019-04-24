---

copyright:

  years: 1994, 2019

lastupdated: "2019-02-25"

keywords: bandwidth pool, bandwidth usage, Add Servers list, optimizing badwidth 

subcollection: customer-portal 

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:tip: .tip}
{:screen: .screen}
{:new_window: target="_blank"}


# 処理能力使用量の最適化
{: #cp_manbdwpool}

世界中の IBM Cloud データ・センターからアウトバウンドに転送される公衆データ網トラフィックでは、アウトバウンド帯域幅料金が請求されます。 この料金は、データを転送しているリソースがある場所、転送されるデータの量、および購入した IBM Cloud 製品の対象となる帯域幅の割り当てによって決まります。 
{:shortdesc} 

お客様は、サーバーのすべての帯域幅をまとめて 1 つの帯域幅プールに「プーリング」することにより、帯域幅使用量を最適化できます。 帯域幅プール内のサーバーの帯域幅超過分は全体で合計されますが、超過分が計算されるのは、すべてのサーバーの帯域幅の合計が、個別のサーバー・レベルでの計量に対して、すべてのサーバーの割り当て済み帯域幅の合計を超える場合のみです。 

以下の表にプール定義をリストします。 

| プール      | 場所          |
| ------------- |:-------------:|
| USA    | DAL01<br/><br/>DAL02<br/><br/>DAL04<br/><br/>DAL07<br/><br/>DAL09<br/><br/>DAL10<br/><br/>DAL12<br/><br/>DAL13<br/><br/>HOU02<br/><br/>MON01<br/><br/>SEA01<br/><br/>SJC01<br/><br/>SJC03<br/><br/>SJC04<br/><br/>TOR01<br/><br/>WDC01<br/><br/>WDC04<br/><br/>WDC06<br/><br/>WDC07|
| アムステルダムおよびロンドン | AMS01<br/><br/>AMS03<br/><br/>LON01<br/><br/>LON02<br/><br/>LON04<br/><br/>LON05<br/><br/>LON06<br/><br/>PAR01 |
| オーストラリア | MEL01<br/><br/>SYD01<br/><br/>SYD04<br/><br/>SYD05 |
| ブラジル | SAO01 |
| フランクフルト | FRA02<br/><br/>FRA04<br/><br/>FRA05 |
| インド | CHE01 |
| イタリア | MIL01 |
| 韓国 | SEO01 | 
| メキシコ | MEX01 | 
| ノルウェー | OSL01 | 
| シンガポール、香港、および東京 | HKG02<br/><br/>SNG01<br/><br/>TOK02<br/><br/>TOK04<br/><br/>TOK05 |
{:caption="表 1. プーリング定義" caption-side="top"}


## 処理能力プールの変更
{: #cp_modbdwpool}

処理能力プールが作成された後、許可されたユーザーはいつでもそのプールにアクセスできます。 処理能力プールにアクセスすることによって、プールに関連付けられたデバイスの表示、プールへのデバイスの追加、またはプールからのデバイスの削除を行うことができます。 プールにアクセスするには、以下の手順を使用します。

1. 固有の資格情報を使用してカスタマー・ポータルにログインします。
2. メニューから**「ネットワーク (Network)」** > **「処理能力 (Bandwidth)」** > **「プール (Pools)」**を選択して、「処理能力プール (Bandwidth Pools)」ウィンドウにアクセスします。
3. **プール名**をクリックしてプールにアクセスします。 プールに関連付けられた各デバイスが表示されます。
4. **「変更 (Modify)」**タブで、プールの名前変更、デバイスの追加、またはプールからのデバイスの削除を行うことができます。
  * プールの名前を変更するには、現行のプール名があるフィールドに新しいプール名を入力します。
  * プールにデバイスを追加するには、**「サーバーの追加 (Add Servers)」**リストからデバイス名を選択し、**「選択 (Select)」**をクリックします。
  * プールからデバイスを削除するには、**「サーバーの削除 (Remove Servers)」**リストからデバイスを選択し、**「選択 (Select)」**をクリックします。
5. **「ラックの変更 (Modify Rack)」**をクリックします。
6. **「すべての処理能力プールの表示 (View All Bandwidth Pools)」**リンクをクリックして「処理能力プール (Bandwidth Pools)」ウィンドウに戻ります。
