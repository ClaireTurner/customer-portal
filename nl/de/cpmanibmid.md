---

copyright:

  years: 1994, 2019

lastupdated: "2019-05-03"

keywords: IBMid accounts, softLayer account, IBM Cloud infrastructure authentication

subcollection: customer-portal
---

{:shortdesc: .shortdesc}
{:screen: .screen}
{:tip: .tip}
{:codeblock: .codeblock}
{:pre: .pre}
{:new_window: target="_blank"}

# IBMid-Konten für {{site.data.keyword.BluSoftlayer_notm}}-Infrastruktur verwenden
{: #customerportal_ibmid}

Die Authentifizierung in der {{site.data.keyword.BluSoftlayer_notm}}-Infrastruktur nutzt jetzt IBMids, um eine einmalige Anmeldung bei {{site.data.keyword.Bluemix_notm}} zu ermöglichen.
{:shortdesc}

Falls Sie ein bestehendes SoftLayer-Konto besitzen, können Sie auf eine IBMid umsteigen. Ein Migrationsassistent hilft Ihnen bei dieser Umstellung. Weitere Informationen finden Sie unter [Zur IBMid wechseln](/docs/account?topic=account-unifyingaccounts#switchtoIBMid).

## Mehrere SoftLayer-Konten einer einzigen IBMid zuordnen
{: #cp_mapmultclinfrto1ibmid}

Sie können einer IBMid mehrere SoftLayer-Konten zuordnen, indem Sie bei der Einrichtung des Kontos eine bestehende E-Mail-Adresse für IBMid verwenden. Einer IBMid kann jeweils nur ein einziger {{site.data.keyword.BluSoftlayer_notm}}-Infrastrukturbenutzer für jedes Konto zugeordnet werden. Die IBMid muss innerhalb jedes SoftLayer-Kontos eindeutig sein. Ein Benutzer mit Zugriff auf mehrere SoftLayer-Konten kann jedoch eine einzige IBMid für den Zugriff auf mehrere SoftLayer-Konten nutzen.

Eine IBMid kann beispielsweise dem Masterbenutzer in den Konten A und B sowie einem weiteren Benutzer in den Konten C und D zugeordnet sein. Eines der dieser IBMid zugeordneten Konten ist das Standardkonto. Normalerweise handelt es sich hierbei um das Konto, das der IBMid zuerst zugeordnet wurde. Sie können mithilfe einer Funktion im Kundenportal für den Kontowechsel ein anderes Konto als Standardkonto festlegen.

![Mehrere SoftLayer-Konten mit einer IBMid](images/ibmid-image.png)

Für einen Benutzer mit IBMid-Zugriff auf mehrere Konten und aktivierter Zwei-Faktor-Authentifizierung (2FA) wird ein Überprüfungscode für die Zwei-Faktor-Authentifizierung benötigt. Dieser Überprüfungscode ist für jedes Konto bei der Kontoanmeldung sowie bei einem Wechsel des Standardkontos erforderlich.
