---

copyright:

  years: 1994, 2019

lastupdated: "2019-06-20"

keywords: IBM Cloud user, user name, portal account, cp FAQs 


subcollection: customer-portal

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:tip: .tip}
{:screen: .screen}
{:new_window: target="_blank"}
{:faq: data-hd-content-type='faq'}


# 常見問題 (FAQ)
{: #bicpfaq}

## 我在 IBM Cloud 主控台中的哪處可以找到我的 SoftLayer 資源？
{: #softlayer-resources}
{: faq}

先前命名為 SoftLayer，現在稱為 IBM Cloud 標準基礎架構。
要檢視裝置、儲存空間、網路、安全和服務，請按一下**功能表圖示** ![功能表圖示](../icons/icon_hamburger.svg) > **標準基礎架構**。您還可以透過按一下**功能表圖示** ![功能表圖示](../icons/icon_hamburger.svg) > **資源清單**來檢視資源清單中的裝置和儲存空間項目。

## 我的支援問題單在哪裡？ 
{: #softlayer-support-tickets}
{: faq}

現在，問題單在 IBM Cloud 中稱為案例。要存取支援案例，請移至**支援** > **管理案例**。

如果您無法檢視案例，請嘗試按一下**檢視保存案例**。如果您仍舊無法檢視案例，說明您可能沒有所需許可權。請求帳戶擁有者將您新增到支援案例存取群組。有關相關資訊，請參閱 [SoftLayer 帳戶許可權](https://test.cloud.ibm.com/docs/iam?topic=iam-migrated_permissions)。 

## 如何擷取客戶入口網站的認證？
{: #bicp_retcreds}
{: faq}

如果您使用 IBM ID 進行鑑別，則當您第一次下訂單或將您新增為帳戶的使用者時，您會收到一封電子郵件，內含開始使用 IBM ID 的鏈結。如果遺失或忘記您的使用者名稱或密碼，請前往 [IBM ID 設定檔 ![外部鏈結圖示](../icons/launch-glyph.svg)](https://www.ibm.com/account/profile){:new_window}，並重設或回復密碼。系統將提示您輸入特定資訊（這可能包括建立安全問題的回答）。

如果您未使用 IBM ID 進行鑑別，則當您第一次下訂單或將您新增為[客戶入口網站 ![外部鏈結圖示](../icons/launch-glyph.svg)](https://control.softlayer.com/){:new_window} 帳戶的使用者時，會收到一封電子郵件，內含您的使用者名稱及起始密碼，以在客戶入口網站中開始使用。請務必在第一次登入之後變更密碼，方法是編輯使用者設定檔。

如果您在登入之後忘記密碼，請使用客戶入口網站登入畫面上所提供的**忘記密碼**特性。系統將提示您輸入特定資訊（這包括您在設定使用者設定檔時指定的一組安全問題）。

如果您忘記使用者名稱，請聯絡可擷取使用者名稱的帳戶管理者或主要使用者。如果您是帳戶上的管理者或主要使用者，請與支援中心聯絡以取得額外的協助。

## 何謂 IBM ID？
{: #bicp_whatisibmid}
{: faq}

新的帳戶需要 IBM ID 才能進行鑑別。現有帳戶會繼續使用 SoftLayer 使用者名稱及密碼進行鑑別，直到您可以執行移轉工具來切換至 IBM ID。您 SoftLayer 帳戶的主要使用者接著會具有在該相同帳戶內新增其他使用者的權限。 

## 如何鏈結現有 SoftLayer 帳戶？
{: #bicp_linkbmxacct}
{: faq}

如果您是 SoftLayer 帳戶上的主要使用者，請登入客戶入口網站，然後按一下標頭中的**鏈結帳戶**。如需相關資訊，請參閱[鏈結 IBM ID 使用者帳戶](/docs/account?topic=account-unifyingaccounts#unifyingaccounts)。

## 我必須是現有 {{site.data.keyword.Bluemix_notm}} 使用者才能鏈結帳戶嗎？
{: #bicp_bmxusertolink}
{: faq}

否，您可以建立新的 {{site.data.keyword.Bluemix_notm}} 帳戶，也可以鏈結現有的 {{site.data.keyword.Bluemix_notm}} 精簡或隨收隨付制帳戶。

## 雙因子鑑別如何運作？
{: #bicp_2fa}
{: faq}

不會影響位於帳戶層次的雙因子鑑別 (2FA) 配置。2FA 不是依據 IBM ID；它仍是根據帳戶。如果 IBM ID 與許多帳戶相關聯，而且您在帳戶之間切換，則每次切換至需要 2FA 的不同帳戶時都必須確認身分。即使前一個帳戶及新的帳戶都已配置相同的雙因子鑑別機制時也是如此。

如需含 2FA 的 IBM ID 的相關資訊，請參閱[已鏈結帳戶中的多因子鑑別使用](/docs/account?topic=account-unifyingaccounts#2fa)。

## 誰可以鏈結帳戶？
{: #bicp_wholinkaccts}
{: faq}

只有 {{site.data.keyword.BluSoftlayer_notm}} 基礎架構主要使用者才能鏈結 SoftLayer 及 {{site.data.keyword.Bluemix_notm}} 帳戶。主要使用者的電子郵件也必須與所鏈結 {{site.data.keyword.Bluemix_notm}} 帳戶的主要擁有者相關聯。

## 將使用什麼來登入每一個主控台？
{: #bicp_logineachport}
{: faq}

會鏈結您的帳戶計費，而且您可以輕鬆地在 SoftLayer 與 {{site.data.keyword.Bluemix_notm}} 帳戶之間移動，但您的帳戶身分仍然不同。

* 如果您的帳戶未使用 IBM ID 進行鑑別，請繼續將 SoftLayer ID 用於 SoftLayer 產品及服務，並將 IBM ID 用於 {{site.data.keyword.Bluemix_notm}} 產品及服務。

* 如果您的帳戶使用 IBM ID 進行鑑別，則會使用 IBM ID 來存取 SoftLayer 及 {{site.data.keyword.Bluemix_notm}} 帳戶。

## 我嘗試使用 SoftLayer 使用者名稱登入時，為什麼收到錯誤？
{: #bicp_SLloginerror}
{: faq}

在您切換至 IBM ID 之後，如果使用 {{site.data.keyword.BluSoftlayer_notm}} 基礎架構使用者名稱來登入客戶入口網站，則會顯示「提供的登入認證無效」錯誤。在您切換至 IBM ID 之後，就無法再使用 {{site.data.keyword.BluSoftlayer_notm}} 基礎架構使用者名稱來登入客戶入口網站。您必須按一下「帳戶登入」對話框中的**使用 IBM ID 登入**。

## 我嘗試使用 IBM ID 登入時，為什麼收到錯誤？
{: #bicp_IBMidloginerror}
{: faq}

使用 IBM ID 進行登入時，會顯示「無法辨識此 IBM ID 或電子郵件」錯誤。請確定您輸入的是完整電子郵件位址。也請確定您不是使用 {{site.data.keyword.BluSoftlayer_notm}} 基礎架構使用者名稱。

## {{site.data.keyword.BluSoftlayer_notm}} 基礎架構團隊成員可以存取我的已鏈結帳戶嗎？
{: #bicp_linkgiveteamaccess}
{: faq}

您必須邀請他們加入 {{site.data.keyword.Bluemix_notm}}。在 {{site.data.keyword.Bluemix_notm}} 主控台中，按一下**管理** > **帳戶** > **使用者**。選取資源群組之後，您可以新增 {{site.data.keyword.BluSoftlayer_notm}} 基礎架構團隊成員。您可能需要先登入客戶入口網站，才能傳送邀請。{{site.data.keyword.Bluemix_notm}} 會取得 {{site.data.keyword.BluSoftlayer_notm}} 基礎架構使用者清單，然後，您可以選取要邀請加入 {{site.data.keyword.Bluemix_notm}} 帳戶的使用者。

## 完成切換至 IBM ID 的電子郵件在哪裡？
{: #bicp_ibmidswitchemail}
{: faq}

如果您已遵循切換至 IBM ID 的精靈，但未收到電子郵件，則可能是需要數分鐘到數小時的時間才會寄送含登錄碼的電子郵件給您。您可以回到客戶入口網站中的**編輯使用者設定檔**頁面，然後按一下**重新傳送電子郵件**以重試。

## 我具有我帳戶的完整 root 存取權嗎？
{: #bicp_fullrootaccaccess}
{: faq}

主要使用者及具有管理者許可權的使用者都會有客戶入口網站及 API 上帳戶的完整 root 存取權。沒有管理者許可權的使用者，其可存取性是由具有管理者角色的使用者所控制。管理者可以利用[編輯使用者設定檔](/docs/customer-portal?topic=customer-portal-cp_edituserprofile#cp_edituserprofile)，從客戶入口網站更新這些許可權。若沒有管理者許可權，您可以按一下使用者名稱，在客戶入口網站中編輯使用者設定檔。

## 我可以鏈結 {{site.data.keyword.Bluemix_notm}} 訂閱帳戶嗎？
{: #bicp_linkbmxsubacct}
{: faq}

{{site.data.keyword.Bluemix_notm}} 中的所有已鏈結帳戶都必須是「精簡」或「隨收隨付制」帳戶。 

## 如何解除鏈結帳戶？
{: #bicp_unlinkacct}
{: faq}

帳戶在鏈結之後，即無法解除鏈結。


## 何謂公司設定檔以及可以在哪裏找到它？
{: #bicp_whatfindcompprof}
{: faq}

公司設定檔就是建立帳戶時所提交的資訊，包括公司的主要聯絡人，以及公司名稱、地址及電話號碼。這項資訊的使用原因眾多，應該隨時保持為最新。若要檢視您帳戶的公司設定檔，或要求變更，請參閱[更新公司設定檔](/docs/customer-portal?topic=customer-portal-cp_updateprofile#cp_updateprofile)。

## 在哪裏可以找到我的裝置及軟體密碼？
{: #bicp_devswpw}
{: faq}

裝置及軟體密碼儲存在客戶入口網站內的兩個位置。若要擷取裝置認證（包括 {{site.data.keyword.baremetal_short}} 及 {{site.data.keyword.virtualmachinesshort}} 的 root 或管理使用者名稱及密碼），請參閱[在 Snapshot 視圖中與裝置互動](/docs/vsi?topic=virtual-servers-interacting-with-a-device-in-snapshot-view#interacting-with-a-device-in-snapshot-view)。若要快速檢視及擷取使用客戶入口網站手動追蹤的軟體認證，請參閱[管理裝置存取權](/docs/vsi?topic=virtual-servers-managing-device-access#managing-device-access)。

## 如何保持 Web 資料同步？
{: #bicp_webdatasync}
{: faq}

雖然您負責維護實際伺服器之間的資料一致性，但是 {{site.data.keyword.BluSoftlayer_full}} 提供您可用來同步化而不會產生使用費用的專用網路。

## 何謂事件管理系統？
{: #bicp_whatisems}
{: faq}

「事件管理系統」是一個工具集，可最佳化 {{site.data.keyword.BluSoftlayer_full}} 與使用者共用有關非計劃性基礎架構問題及即將到來的計劃性維護事件的資訊的方式。它會使用已設定目標的訂閱型電子郵件警示，讓這些突發事件共用所發生事件的類型。它會將整體事件影響以及進行中非計劃性突發事件 (UIP) 現行狀態的詳細資料提供給已訂閱使用者。

## 可以取消裝置嗎？
{: #bicp_candev}
{: faq}

您隨時可以透過客戶入口網站來取消裝置。如需完成取消要求的相關資訊，請參閱[取消裝置](/docs/vsi?topic=virtual-servers-managing-virtual-servers#managing-virtual-servers)。
