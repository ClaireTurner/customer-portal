---

copyright:

  years: 1994, 2019

lastupdated: "2019-01-28"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:tip: .tip}
{:note: .note}
{:screen: .screen}
{:new_window: target="_blank"}


# 進行付款
{: #customerportal_makepayment}

所有 {{site.data.keyword.Bluemix}} 基礎架構計費詳細資料（從發票到付款資訊）都會安全地儲存在客戶入口網站中。如果您的付款方法變更，或信用卡遭到取消或到期，請更新付款資訊以避免產生滯納金。
{:shortdesc}

## 檢視發票
{: #cp_viewinvoice}

在「發票」視窗上，每一張個別發票都是依據發票號碼、日期、發票類型及各種貨幣餘額進行彙總。發票可能是下列任何類型：

<dl>
<dt>新建</dt>
<dd>一系列經常性發票中的第一張發票。</dd>
<dt>經常性</dt>
<dd>在帳戶上已發生數個月的經常性費用的發票。</dd>
<dt>一次性費用</dt>
<dd>各種費用的一次性費用，可能包括超額。</dd>
<dt>額度</dt>
<dd>從 {{site.data.keyword.BluSoftlayer_notm}} 基礎架構到帳戶餘額的額度。</dd>
<dt>退款</dt>
<dd>一次性或經常性費用的費用沖銷。</dd>
</dl>

您也可以檢視帳戶的計費摘要，包括下列資訊：
  * 現行及預估的下次餘額
  * 付款方法
  * 最後一個及下一個循環的發票日期

1. 從功能表按一下**帳戶** > **計費** > **發票**。
2. 您可以在客戶入口網站中檢視發票，或下載發票。

如果您要在客戶入口網站中檢視發票，會針對選取的發票顯示逐項說明的計費項目清單。按一下計費項目行上的任何位置，以檢視其他逐項說明的費用相關詳細資料。如果您已下載發票，則可以根據瀏覽器設定進行檢視。已下載的發票提供每一個計費項目的逐項說明摘要及逐項說明詳細計費。

如果您位於美國以外地區，請使用稱為 [Invoices](http://www.ibm.com/support/customer/invoices){: new_window} ![外部鏈結圖示](../icons/launch-glyph.svg "外部鏈結圖示") 的工具來檢視發票。每個國家/地區的特定步驟列出於 [https://www.ibm.com/support/customer/zz/en/selectcountrylang_invoices.html](https://www.ibm.com/support/customer/zz/en/selectcountrylang_invoices.html){: new_window} ![外部鏈結圖示](../icons/launch-glyph.svg "外部鏈結圖示")。如果您有任何問題，請以 1-866-325-0045 與我們聯絡，並要求存取您的發票。
{: note}

## 新增付款方法
{: #cp_cpmanacctbillpay}

每個 SoftLayer 帳戶都必須有存檔的信用卡，以便每個月自動按發票金額收費。此資訊隨時都必須是最新的，以避免逾期付款；您隨時都可以更新此資訊，確保付款資訊永遠正確。如果存檔的信用卡資訊正確無誤，但您想要對目前的餘額套用替代的付款方式，請參閱[管理計費項目](/docs/customer-portal/cpmanacctbillpay.html#cp_makeonetimepayment)。請使用下列步驟，以在客戶入口網站中新增帳戶的付款方法。

1. 從功能表按一下**帳戶** > **計費** > **付款方法**。
2. 在**帳單地址**區段的每一個欄位中，輸入卡片的必要計費詳細資料。
> **附註：**按一下**使用公司資訊**勾選框，以使用 {{site.data.keyword.BluSoftlayer_notm}} 基礎架構針對帳戶存檔的公司資訊來自動完成欄位。
3. 在**付款資訊**區段的每一個欄位中，輸入信用卡資訊。
4. 按一下**新增信用卡**，以將信用卡新增為每月付款方法。
5. 選擇性地選取**歐盟支援**，確保歐洲的支援團隊處理您的維護及支援問題。如需這個選項的相關資訊，請參閱[設定歐盟支援選項](/docs/customer-portal/cpmanuserprof.html#cp_seteusupported)。

在您新增付款方法之後，SoftLayer 帳戶代表就會處理要求，確保卡片有效性。驗證過的卡片在 24 小時內提供給此帳戶使用。付款方法的狀態變更會透過電子郵件傳送給新增付款方法時所提供的聯絡人。

## 進行一次性付款
{: #cp_makeonetimepayment}

您可以使用 PayPal 帳戶或主要信用卡進行一次性付款，並且可以支付全部或部分餘額的款項。一次性付款詳細資料不會記錄以供未來使用，而且不會修改帳戶的現行每月付款方法。

1. 移至客戶入口網站中的「進行一次性付款」頁面。
 * 從功能表中：移至**帳戶** > **進行付款**。
 * 從「發票」頁面中：按一下**支付餘額**。
2. 在**付款金額**欄位中，輸入付款金額。
3. 如果您要使用 PayPal 付款，請按一下 **PayPal**，並遵循 PayPal 的提示來完成付款。不需要執行任何進一步動作。如果您要使用信用卡付款，請在適當的欄位中輸入**卡號、有效期限及安全碼**。
4. 在**信用卡帳單地址**區段的適當欄位中，輸入計費資訊。
5. 選擇性地選取**歐盟支援**，確保歐洲的支援團隊處理您的維護及支援問題。如需這個選項的相關資訊，請參閱[設定歐盟支援選項](/docs/customer-portal/cpmanuserprof.html#cp_seteusupported)。
6. 按一下**使用信用卡付款**，以開始進行付款。

在開始進行付款之後，即會處理付款。如果付款時發生問題，則在解決問題之前，請遵循 {{site.data.keyword.BluSoftlayer_notm}} 基礎架構或 PayPal 的提示。即會處理付款。會套用金額，並更新現行餘額。
