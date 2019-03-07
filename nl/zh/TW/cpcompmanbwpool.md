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


# 最佳化頻寬用量
{: #cp_manbdwpool}

從全球 IBM Cloud 資料中心出埠傳輸的公用資料網路資料流量，都會被評量計算出埠頻寬費用。費用取決於傳輸資料的資源所在處、送出的資料量，以及您購買 IBM Cloud 產品而符合資格的任何頻寬分配。
{:shortdesc} 

客戶可以將伺服器的所有頻寬全部「儲存 (pooling)」至「頻寬儲存區」，使頻寬的利用達到最佳化。頻寬儲存區中伺服器的頻寬超額會加總為一個，所有伺服器總頻寬超出所有伺服器總配置頻寬的情況下才會計算超額，而不是在個別伺服器層次計量。
 

儲存區定義列出如下表： 

|儲存區|位置|
| ------------- |:-------------:|
| USA    |DAL01  <br/><br/>DAL02<br/><br/>DAL04<br/><br/>DAL07  <br/><br/>DAL09  <br/><br/>DAL10  <br/><br/>DAL12  <br/><br/>DAL13  <br/><br/>HOU02  <br/><br/>MON01  <br/><br/>SEA01  <br/><br/>SJC01  <br/><br/>SJC03  <br/><br/>SJC04<br/><br/>TOR01  <br/><br/>WDC01  <br/><br/>WDC04  <br/><br/>WDC06  <br/><br/>WDC07  |
|阿姆斯特丹及倫敦|AMS01  <br/><br/>AMS03  <br/><br/>LON01<br/><br/>LON02  <br/><br/>LON04<br/><br/>LON05<br/><br/>LON06<br/><br/>PAR01  |
|澳大利亞|MEL01  <br/><br/>SYD01  <br/><br/>SYD04<br/><br/>SYD05 |
|巴西|SAO01  |
| 法蘭克福 |FRA02  <br/><br/>FRA04<br/><br/>FRA05 |
|印度|CHE01  |
|義大利|MIL01  |
|南韓|SEO01  | 
|墨西哥|MEX01  | 
|挪威|OSL01  | 
|新加坡、香港及東京|HKG02  <br/><br/>SNG01  <br/><br/>TOK02  <br/><br/>TOK04<br/><br/>TOK05 |
{:caption="表 1. 儲存區定義" caption-side="top"}


## 修改頻寬儲存區
{: #cp_modbdwpool}

建立頻寬儲存區之後，如果您是授權使用者，則隨時都可以存取儲存區。您可以存取頻寬儲存區來檢視與儲存區相關聯的裝置、將裝置新增至儲存區，或從儲存區移除裝置。請使用下列步驟，以存取儲存區：

1. 使用唯一的認證來登入客戶入口網站。
2. 從功能表中，選取**網路** > **頻寬** > **儲存區**，以存取「頻寬儲存區」視窗。
3. 按一下**儲存區名稱**，以存取儲存區。即會顯示每一個與儲存區相關聯的裝置。
4. 從**修改**標籤中，您可以重新命名儲存區、新增裝置，或從儲存區移除裝置：
  * 若要重新命名儲存區，請在具有現行儲存區名稱的欄位中輸入新的儲存區名稱。
  * 若要將裝置新增至儲存區，請從**新增伺服器**清單選取裝置名稱，然後按一下**選取**。
  * 若要從儲存區移除裝置，請從**移除伺服器**清單選取裝置，然後按一下**選取**。
5. 按一下**修改機架**。
6. 按一下**檢視所有頻寬儲存區**鏈結，以回到「頻寬儲存區」視窗。
