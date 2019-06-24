---

copyright:

  years: 1994, 2019

lastupdated: "2019-06-10"

keywords: identity provider, IBM Cloud infrastructure, single sign-on  

subcollection: customer-portal

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:tip: .tip}
{:screen: .screen}
{:new_window: target="_blank"}


# Single Sign-on konfigurieren
{: #customerportal_confssoserv}

Wenn Sie Masterbenutzer eines Kontos sind oder einen Verwaltungszugriff auf das Konto besitzen, können Sie das Single Sign-on konfigurieren. Die Konfiguration des Single Sign-on für die {{site.data.keyword.BluSoftlayer_full}}-Infrastruktur ist ein aus zwei Schritten bestehender Prozess. Zuerst wählen Sie Ihren Identitätsprovider aus und konfigurieren ihn. Anschließend konfigurieren Sie die {{site.data.keyword.BluSoftlayer_notm}}-Infrastruktur für den Empfang der Authentifizierungsanforderung von Ihrem Identitätsprovider.
{:shortdesc}

## Identitätsprovider auswählen und konfigurieren
{: #cp_setupidprov}

Falls Sie noch keinen Identitätsprovider verwenden, wählen Sie zunächst einen Provider aus und konfigurieren Sie ihn. Bei {{site.data.keyword.BluSoftlayer_notm}} können Sie die folgenden Identitätsprovider verwenden:
* Ping Identity&reg;
* OneLogin&trade;
* IBM&reg; Cloud Security Enforcer
* IBM Cloud Identity Services
Weitere Informationen erhalten Sie vom zuständigen Vertriebsbeauftragten für {{site.data.keyword.BluSoftlayer_notm}}-Infrastruktur.

Falls Ihr Identitätsprovider noch nicht konfiguriert ist, können Sie sich bei Fragen oder Problemen an den Support Ihres Identitätsproviders wenden. Außerdem können Sie auch die folgenden allgemeinen Schritte zur Konfiguration Ihres Identitätsproviders ausführen:
1. Bereiten Sie die Umgebung für Ihren Identitätsprovider vor, indem Sie die ausführbare Datei herunterladen und installieren.
2. Konfigurieren Sie Ihren Identitätsprovider für die Verwendung bei der {{site.data.keyword.BluSoftlayer_notm}}-Authentifizierung.

## {{site.data.keyword.BluSoftlayer_notm}}-Infrastruktur für Single Sing-on konfigurieren
{: #cp_setupsso}

Sie müssen die folgenden erforderlichen Felder der Metadaten gemäß Security Assertion Markup Language&trade; (SAML&trade;) 2.0 aus Ihrem Identitätsprovider extrahieren, damit sie bei {{site.data.keyword.BluSoftlayer_notm}} verwendet werden können.
<dl>
<dt>Entitäts-ID</dt>
<dd>Die Entitäts-ID des Identitätsproviders.</dd>
<dt>URL für Single Sign-on</dt>
<dd>Der Endpunkt des Identitätsproviders für das Single Sign-on (SSO).</dd>
<dt>Zertifikat</dt>
<dd>Das Zertifikat des Identitätsproviders, das zum Signieren von Anforderungen verwendet wird.</dd>
</dl>

Das folgende Feld ist optional:
<dl>
<dt>Zertifikatsfingerabdruck</dt>
<dd>Der Fingerabdruck des Zertifikats. Dieses Feld kann anstelle des vollständigen Zertifikats verwendet werden.</dd>
</dl>

Führen Sie die folgenden Schritte aus, um die {{site.data.keyword.BluSoftlayer_notm}}-Infrastruktur für den Empfang der Authentifizierungsanforderung von Ihrem Identitätsprovider zu konfigurieren:
1. Melden Sie sich bei Ihrem Identitätsprovider an, wenn Sie noch nicht angemeldet sind, und suchen Sie nach der Seite für die **SAML-Konfiguration**. Notieren Sie sich die folgenden Informationen:
  * Entitäts-ID
  * URL für Single Sign-on
  * Zertifikat (Zertifikatsanforderungen variieren je nach Identitätsprovider)
2. Melden Sie sich bei der {{site.data.keyword.BluSoftlayer_notm}}-Infrastruktur als Masterbenutzer mit dem Namen und dem Kennwort des Masterbenutzers an, als der Sie Ihr SoftLayer-Konto erstellt haben.
3. Klicken Sie auf **Konto** > **Verwalten** > **SAML-Authentifizierung**.
4. Geben Sie die Metadaten für den **Identitätsprovider** ein.
5. Klicken Sie auf **Speichern**.
6. Klicken Sie auf **Konto** > **Verwalten** > **SAML-Authentifizierung**.
7. Klicken Sie auf **XML-Konfiguration herunterladen**, um die Metadaten für den Service-Provider herunterzuladen oder die Informationen zu notieren.
8. Verwenden Sie die Metadaten für den **Service-Provider**, um Ihren Identitätsprovider entsprechend den Anweisungen Ihres Identitätsproviders zu konfigurieren.  

Sie können sich unter Verwendung Ihrer föderierten (eingebundenen) ID bei der {{site.data.keyword.BluSoftlayer_notm}}-Infrastruktur anmelden. Weitere Informationen zu föderierten IDs finden Sie in [Bei {{site.data.keyword.Bluemix_notm}} registrieren](/docs/account?topic=account-signup).
