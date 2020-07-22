---
title: 2020年的半年期企業通道（預覽版）發行記錄
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為 IT 專業人員提供 2020 年 Microsoft 365 Apps 半年通道 (已設定目標) 版本的版本資訊
ms.openlocfilehash: 28b78e3952867cb55b2b91e9e6d9d8d5f2e35063
ms.sourcegitcommit: 6f79e3c3948db4d7ae1c6dfc855970551d3b1678
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/20/2020
ms.locfileid: "45187583"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-preview-releases-in-2020"></a><span data-ttu-id="d9fbb-103">2020年的半年期企業通道（預覽版）發行記錄</span><span class="sxs-lookup"><span data-stu-id="d9fbb-103">Release notes for Semi-Annual Enterprise Channel (Preview) releases in 2020</span></span>

<span data-ttu-id="d9fbb-104">這些版本資訊提供新功能和非安全性更新的相關資訊，這些功能和非安全性更新包含在 2020 年 Microsoft 365 Apps 企業版、Microsoft 365 Apps 商務版，以及 Project 和 Visio 版的傳統型應用程式訂閱版本的半年企業通道 (預覽) 更新。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel (Preview) updates in 2020 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="d9fbb-105">我們會變更 Microsoft 365 應用程式的更新通道，包括新增新的更新通道 (每月企業通道)，並變更現有的更新通道名稱。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="d9fbb-106">如需深入了解，[請閱讀本文](https://go.microsoft.com/fwlink/p/?linkid=2127441)。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-106">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>


## <a name="version-2002-july-14"></a><span data-ttu-id="d9fbb-107">版本 2002：7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="d9fbb-107">Version 2002: July 14</span></span>
<span data-ttu-id="d9fbb-108">*版本 2002 (組建 12527.20880)*</span><span class="sxs-lookup"><span data-stu-id="d9fbb-108">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="d9fbb-109">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="d9fbb-109">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="d9fbb-111">解決的問題</span><span class="sxs-lookup"><span data-stu-id="d9fbb-111">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d9fbb-112">Excel</span><span class="sxs-lookup"><span data-stu-id="d9fbb-112">Excel</span></span>

- <span data-ttu-id="d9fbb-113">加速載入本機 OneDrive 資料夾中的檔案。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-113">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="d9fbb-114">已修正當儲存至 SharePoint/OneDrive 時，會導致自訂功能區索引標籤 CustomUI XML 的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-114">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="d9fbb-115">修正因為增益集是以字母順序載入，而不是以使用者指定的順序載入，而顯示 [這個活頁簿目前正由其他活頁簿所參考中，不可關閉] 錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-115">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="d9fbb-116">修正按一下已開啟活頁簿中某個位置的超連結時，活頁簿可能會隱藏的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-116">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="d9fbb-117">我們已修正某些複製和貼上的圖表連結使用的是映射磁碟機位址，而不是通用位址的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-117">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="d9fbb-118">改善刪除具有合併儲存格的欄時的效能。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-118">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="d9fbb-119">修正 [列印] 對話方塊的印表機清單中，印表機名稱可能會重複的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-119">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="d9fbb-120">我們已修正包含多個含有定義名稱的公式會導致儲存檔案時間加長的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-120">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>


### <a name="outlook"></a><span data-ttu-id="d9fbb-121">Outlook</span><span class="sxs-lookup"><span data-stu-id="d9fbb-121">Outlook</span></span>

- <span data-ttu-id="d9fbb-122">我們已修正以下問題：當使用多個不同解析度的監視器時，輸入法編輯器 (IEM) 視窗會覆蓋透過 IME 輸入的文字。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-122">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="d9fbb-123">解決會導致週期性約會或會議在接近時區定義變更時於錯誤的時間顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-123">Addressed an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="d9fbb-124">解決會導致使用者在 Outlook 中更新其規則時，看到 [此電腦上的規則與 Microsoft Exchange 上的規則不相符] 訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-124">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="d9fbb-125">解決會導致若「未」核取 [下載共用資料夾]，共用行事曆會議的 [回應選項] 中會遺失 [允許轉寄] 選項的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-125">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="d9fbb-126">已解決會導致類別有時候會從電子郵件訊息中消失的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-126">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="d9fbb-127">已解決會導致代理人在不同機器上所看到的共用信箱有不同資料夾階層的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-127">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="d9fbb-128">解決在編輯經理行事曆上的現有行事曆約會時，導致代理人收到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-128">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="d9fbb-129">解決在編輯主旨之後，會導致 NDR 訊息的本文從 Unicode 變更為 ASCII 的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-129">Addressed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="d9fbb-130">解決當兩個增益集將一個按鈕新增到相同功能區群組時，會導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-130">Addressed an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="d9fbb-131">解決了導致使用者無法將電子郵件傳送到個人通訊群組清單的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-131">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="d9fbb-132">解決當租用戶預設權限設定為「任何人」時，會導致無法將連結新增至具有正確租用戶預設權限的電子郵件的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-132">Addressed an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as"anyone".</span></span>

- <span data-ttu-id="d9fbb-133">解決了當選取安全性對話方塊上的 [儲存] 選項時，導致使用者無法將 OneDrive 外部的 OneDrive 附件儲存至他們的本機電腦的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-133">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="word"></a><span data-ttu-id="d9fbb-134">Word</span><span class="sxs-lookup"><span data-stu-id="d9fbb-134">Word</span></span>

- <span data-ttu-id="d9fbb-135">我們已修正啟用原則 FileBlick\Word2007Files 時共同編輯中的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-135">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="d9fbb-136">我們已修正新增已重新命名之查閱欄位時，Word QuickPart 無法使用的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-136">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="d9fbb-137">Office 套件</span><span class="sxs-lookup"><span data-stu-id="d9fbb-137">Office Suite</span></span>

- <span data-ttu-id="d9fbb-138">修正當共同撰寫大型 PowerPoint 檔案時，使用者可能會遇到過度網路和 CPU 使用量的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-138">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="d9fbb-139">我們會將新的 AppV51 向後移，以修正先前 AppV51 中的回歸。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-139">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="d9fbb-140">解決在登錄 TabProcGrowth 值為 REG_SZ 類型的情況下啟用增益集時，Windows 中的 Office 主機會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-140">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-june-09"></a><span data-ttu-id="d9fbb-142">版本 2002: 6 月 09日</span><span class="sxs-lookup"><span data-stu-id="d9fbb-142">Version 2002: June 09</span></span>
<span data-ttu-id="d9fbb-143">*版本2002（組建12527.20720）*</span><span class="sxs-lookup"><span data-stu-id="d9fbb-143">*Version 2002 (Build 12527.20720)*</span></span>

<span data-ttu-id="d9fbb-144">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="d9fbb-144">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="d9fbb-146">解決的問題</span><span class="sxs-lookup"><span data-stu-id="d9fbb-146">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d9fbb-147">Excel</span><span class="sxs-lookup"><span data-stu-id="d9fbb-147">Excel</span></span>

- <span data-ttu-id="d9fbb-148">已修正當檔案路徑太長時，在檔案重新開啟之後外部連結會停止運作的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-148">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="d9fbb-149">已修正當 Excel 視窗透過 Teams 共用時，使用 Ctrl + Shift + 方向鍵滑動後，Excel 可能會無法回應的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-149">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="d9fbb-150">已修正列印時表單控制項的核取方塊縮放的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-150">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="d9fbb-151">當您使用舊版的「共用活頁簿」模式，嘗試為活頁簿的新工作表列出變更時，就會發生當機。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-151">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="d9fbb-152">在已篩選清單中插入欄的時間會比預期更長。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-152">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="d9fbb-153">已修正開始公式的 @ 符號會被視為隱式交集運算子的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-153">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

### <a name="outlook"></a><span data-ttu-id="d9fbb-154">Outlook</span><span class="sxs-lookup"><span data-stu-id="d9fbb-154">Outlook</span></span>

- <span data-ttu-id="d9fbb-155">可透過原 Teams 客戶直接啟用加入 Teams 會議。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-155">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="d9fbb-156">解決了 Outlook 無法啟用 [資料遺失保護原則] 提示使用 M365 商務版進階方案並為此服務付款的的使用者之問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-156">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="d9fbb-157">解決了導致瀏覽器模擬設置錯誤的用戶無法完成 Gmail 身分驗證提示的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-157">Addressed an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="d9fbb-158">解決了導致伺服器作業系統上的 Outlook 使用者看到「防病毒處理狀態：無效」的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-158">Addressed an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="d9fbb-159">這個版本的 Windows 支援防毒軟體檢測，但即使已適當設定防毒軟體，也無法找到防毒軟體。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-159">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

### <a name="word"></a><span data-ttu-id="d9fbb-160">Word</span><span class="sxs-lookup"><span data-stu-id="d9fbb-160">Word</span></span>

- <span data-ttu-id="d9fbb-161">我們已修正文件中的文字對齊，在使用 [快速列印] 進行列印之後嘗試進行編輯時變得混亂的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-161">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

### <a name="office-suite"></a><span data-ttu-id="d9fbb-162">Office 套件</span><span class="sxs-lookup"><span data-stu-id="d9fbb-162">Office Suite</span></span>

- <span data-ttu-id="d9fbb-163">我們將後台中的頻道名稱更新為2020年1月 Fork 的新通道名稱，解決了此問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-163">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="d9fbb-164">我們已修正此問題，如果裝置受政策管理，將不會調用 DMS 聽眾 API。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-164">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="d9fbb-165">已解決在單一交易中新增和移除應用程式時，未完成移除的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-165">Resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="d9fbb-166">當您啟用增益集，而登錄金鑰 HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth 被設為零時，辦公主機視窗會當機。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-166">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="d9fbb-167">這變更將修正此問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-167">This change would fix this issue.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-may-12"></a><span data-ttu-id="d9fbb-169">版本 2002：5 月 12 日</span><span class="sxs-lookup"><span data-stu-id="d9fbb-169">Version 2002: May 12</span></span>
<span data-ttu-id="d9fbb-170">*版本 2002 (組建 12527.20612)*</span><span class="sxs-lookup"><span data-stu-id="d9fbb-170">*Version 2002 (Build 12527.20612)*</span></span>

<span data-ttu-id="d9fbb-171">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="d9fbb-171">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="d9fbb-173">解決的問題</span><span class="sxs-lookup"><span data-stu-id="d9fbb-173">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="d9fbb-174">Excel</span><span class="sxs-lookup"><span data-stu-id="d9fbb-174">Excel</span></span>

- <span data-ttu-id="d9fbb-175">開啟含有許多其他活頁簿 (尤其是含有隱藏視窗) 參照的活頁簿時，速度比預期慢。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-175">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="d9fbb-176">在某些情況下，開啟 CSV 檔案所花費的時間超過預期。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-176">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="d9fbb-177">在某些情況下，當您切換不同縮放比例的活頁簿時，Excel 可能會當機。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-177">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="d9fbb-178">已修正 VBA 將值寫入範圍時，速度比預期慢的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-178">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="d9fbb-179">從有色彩篩選的欄複製的資料有時候無法正確貼上。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-179">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="d9fbb-180">已修正在複製含有樞紐分析表的工作表後，會於某些情況下導致 Excel 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-180">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="d9fbb-181">在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-181">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="d9fbb-182">已解決在儲存並重新開啟檔案時，圖表軸上的 "Value Crosses At" 屬性發生意外變更的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-182">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="d9fbb-183">使用 Range.Value 和 Range.Value2 (VBA) 會導致公式以動態陣列的形式輸入。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-183">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

### <a name="onenote"></a><span data-ttu-id="d9fbb-184">OneNote</span><span class="sxs-lookup"><span data-stu-id="d9fbb-184">OneNote</span></span>

- <span data-ttu-id="d9fbb-185">對通知進行本地化，讓使用者可以了解更多 OneNote 使用者體驗中正在採取的臨時措施的資訊，以改善同步處理和服務穩定性。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-185">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="d9fbb-186">顯示通知，讓使用者可以了解更多 OneNote 使用者體驗中正在採取的臨時措施的資訊，以改善同步處理和服務穩定性。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-186">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="d9fbb-187">在 OneNote 2016 中暫時降低版本歷程記錄頁面的數目和同步處理頻率，以改善同步處理與服務穩定性。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-187">Improved sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="d9fbb-188">透過暫時停用 OneNote 2016 中的資源回收筒，來改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-188">Improved sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="d9fbb-189">當使用者嘗試刪除通常會傳送到 [資源回收筒] 的資料時，系統會詢問使用者是否希望保留或永久刪除資料。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-189">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="d9fbb-190">透過暫時調整 OneNote 2016 中的同步處理頻率，來改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-190">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="d9fbb-191">暫時延遲下載線上筆記本中內嵌的檔案和影像，直到使用者瀏覽至 OneNote 2016 中的頁面，以改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-191">Improved sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="d9fbb-192">透過暫時停用 OneNote 2016 中的應用程式內視訊錄製，來改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-192">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="d9fbb-193">本機筆記本不受這個值的影響。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-193">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="d9fbb-194">透過暫時將 OneNote 2016 中新嵌入附件的最大允許大小減少為 50MB，來改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-194">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="d9fbb-195">對於超過此限制的檔案，使用者可以選擇將檔案上傳到 OneDrive，並將連結插入 OneNote。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-195">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

### <a name="outlook"></a><span data-ttu-id="d9fbb-196">Outlook</span><span class="sxs-lookup"><span data-stu-id="d9fbb-196">Outlook</span></span>

- <span data-ttu-id="d9fbb-197">已解決導致資料夾窗格寬度意外變更的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-197">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="d9fbb-198">解決以下問題：Windows 更新之後，使用者開啟 .msg 和 .oft 檔案時遇到當機。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-198">Addressed an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="d9fbb-199">解決會導致使用者在轉寄大型 HTML 郵件時，看到郵件內文截斷的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-199">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="d9fbb-200">此更新修正在查看或撰寫郵件時，Microsoft Outlook 未顯示目前的敏感度標籤的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-200">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="d9fbb-201">解決了導致使用者無法將電子郵件傳送到個人通訊群組清單的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-201">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d9fbb-202">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d9fbb-202">PowerPoint</span></span>

- <span data-ttu-id="d9fbb-203">已修正以下問題：當開啟的檔案複本具有增強式註解時，為使用者轉送正確的訊息。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-203">Fixed an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="word"></a><span data-ttu-id="d9fbb-204">Word</span><span class="sxs-lookup"><span data-stu-id="d9fbb-204">Word</span></span>

- <span data-ttu-id="d9fbb-205">解決了 Access 和 Publisher 因所安裝的語言而無法正常啟動的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-205">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>

- <span data-ttu-id="d9fbb-206">修正受保護無法編輯之文件的比較功能問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-206">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="d9fbb-207">我們已修正將兩份文件合併成一份文件時的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-207">We fixed an issue when merging 2 documents into one document.</span></span>

### <a name="office-suite"></a><span data-ttu-id="d9fbb-208">Office 套件</span><span class="sxs-lookup"><span data-stu-id="d9fbb-208">Office Suite</span></span>

- <span data-ttu-id="d9fbb-209">此修正解決了當檔案已在用戶端中進行快取時，Project 應用程式不應封鎖網路。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-209">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>

- <span data-ttu-id="d9fbb-210">我們已解決內部作業在失敗時擲出例外狀況，而不是記錄和繼續進行的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-210">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="d9fbb-211">受影響的使用者將不會再無法收到更新。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-211">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="d9fbb-212">這項變更可確保草繪大綱可在功能區中正常運作。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-212">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="d9fbb-213">已修正使用一些特定 proxy 設定時，從內部部署位置開啟檔案時發生的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-213">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="d9fbb-214">此更新修正了 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-214">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="d9fbb-215">此更新解決了 Microsoft Office 中的一個問題：可能無法在執行時期正確找到 Visual Basic for Applications 專案，這些專案的參照預期透搜尋 PATH 環境變數指定的位置來找到，進而導致VBA 執行時期錯誤。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-215">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="d9fbb-216">此更新解決了 Microsoft Word 中的一個問題：如果標籤原則套用了頁首或頁尾或浮水印，那麼在套用敏感度標籤時，插入長度超過 255 個字元的文字後續將無法透過變更或刪除標籤來識別和刪除。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-216">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

- <span data-ttu-id="d9fbb-217">修正問題，可在 Office 遞交工作階段期間消除當機，並改善使用者體驗中的可靠性。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-217">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>  

- <span data-ttu-id="d9fbb-218">這個錯誤會更新增強的設定服務 (ECS) url 端點。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-218">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="d9fbb-219">呼叫這個較新的端點，可從 ECS 進行提取獲得更高的成功率。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-219">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-april-14"></a><span data-ttu-id="d9fbb-221">版本 2002：4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="d9fbb-221">Version 2002: April 14</span></span>
<span data-ttu-id="d9fbb-222">*版本 2002 (組建 12527.20442)*</span><span class="sxs-lookup"><span data-stu-id="d9fbb-222">*Version 2002 (Build 12527.20442)*</span></span>

<span data-ttu-id="d9fbb-223">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="d9fbb-223">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


### <a name="feature-updates"></a><span data-ttu-id="d9fbb-224">功能更新</span><span class="sxs-lookup"><span data-stu-id="d9fbb-224">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="d9fbb-225">Excel</span><span class="sxs-lookup"><span data-stu-id="d9fbb-225">Excel</span></span>

- <span data-ttu-id="d9fbb-226">**輸入會傳回多個值的公式：** 快速輸入公式來傳回多個值，並且值會自動溢出至相鄰的儲存格。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-226">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="d9fbb-227">深入了解</span><span class="sxs-lookup"><span data-stu-id="d9fbb-227">Learn more</span></span>](https://support.microsoft.com/en-us/office/new-array-functions-003df6c7-1dcb-4388-8e2e-0fe77a0887bc?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="d9fbb-228">**六個功能強大的函數：** 我們新增了六個新的函數，讓您的試算表功能更強大：FILTER、SORT、SORTBY、UNIQUE、SEQUENCE 和 RANDARRAY。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-228">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span>  [<span data-ttu-id="d9fbb-229">深入了解</span><span class="sxs-lookup"><span data-stu-id="d9fbb-229">Learn more</span></span>](https://support.microsoft.com/en-us/office/easier-array-formulas-5c2c9cbb-def8-409a-b380-2fbf91b20aa3?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="d9fbb-230">**向左看，向右看... XLOOKUP 在這裡！：** 一列接著一列，在含有 XLOOKUP 的表格或範圍中尋找您需要的項目。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-230">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span>  [<span data-ttu-id="d9fbb-231">深入了解</span><span class="sxs-lookup"><span data-stu-id="d9fbb-231">Learn more</span></span>](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="d9fbb-233">解決的問題</span><span class="sxs-lookup"><span data-stu-id="d9fbb-233">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d9fbb-234">Excel</span><span class="sxs-lookup"><span data-stu-id="d9fbb-234">Excel</span></span>

- <span data-ttu-id="d9fbb-235">重複開啟內嵌在 Word 或 PowerPoint 中的活頁簿時，在某些情況下，Excel 會當機。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-235">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="d9fbb-236">儲存為 CSV 檔案時，在某些情況下，Excel 會將所有欄合併成單一欄。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-236">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="d9fbb-237">在受保護工作表中的範圍使用 Range.ClearContents 可能會比預期花的時間更長。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-237">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="d9fbb-238">修正了在 [預覽列印] 中顯示表單控制項時的文字縮放比例問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-238">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="d9fbb-239">與功能區互動的 VBA 宏可能會意外以 ScreenUpdating 設定為 True 執行。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-239">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="d9fbb-240">解決了當來源活頁簿關閉時，外部連結無法在填滿時 (向下填滿、跨表填滿等) 更新的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-240">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is closed.</span></span>

- <span data-ttu-id="d9fbb-241">在某些情況下，使用 VBA 的 Application.Evaluate 對使用者定義的函數無法運作。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-241">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="d9fbb-242">解決從範本建立圖表時的效能問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-242">Addressed a performance issue when creating charts from templates.</span></span>


### <a name="outlook"></a><span data-ttu-id="d9fbb-243">Outlook</span><span class="sxs-lookup"><span data-stu-id="d9fbb-243">Outlook</span></span>

- <span data-ttu-id="d9fbb-244">解決了在某些情況下，[群組] 標題會意外展開的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-244">Addressed an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="d9fbb-245">解決了導致使用者在選取特定搜尋結果時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-245">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="d9fbb-246">解決了使用滑鼠上的 X 按鈕時，導致使用者偶爾發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-246">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="d9fbb-247">解決了會讓 [附件工具] 中的 [儲存至雲端] 按鈕不見的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-247">Addressed an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d9fbb-248">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d9fbb-248">PowerPoint</span></span>

- <span data-ttu-id="d9fbb-249">已改善複製貼上的案例：將 PowerPoint 投影片中的圖形複製並貼到迴圈中的其他投影片，可能會出現例外狀況而失敗。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-249">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


### <a name="project"></a><span data-ttu-id="d9fbb-250">Project</span><span class="sxs-lookup"><span data-stu-id="d9fbb-250">Project</span></span>

- <span data-ttu-id="d9fbb-251">修正了儲存使用舊版 [專案] 建立的專案時，[專案] 可能當機的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-251">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="d9fbb-252">修正了透過 [已停用] 按鈕停用/啟動工作時，ProjectBeforeTaskChange 事件無法偵測的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-252">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

### <a name="word"></a><span data-ttu-id="d9fbb-253">Word</span><span class="sxs-lookup"><span data-stu-id="d9fbb-253">Word</span></span>

- <span data-ttu-id="d9fbb-254">解決了使用滑鼠上的 X 按鈕時，導致使用者偶爾發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-254">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="d9fbb-255">我們修正了表格中最適文字大小的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-255">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="d9fbb-256">我們修正了插入水平線無法更短並置中的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-256">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-march-10"></a><span data-ttu-id="d9fbb-258">版本 2002：3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="d9fbb-258">Version 2002: March 10</span></span>
<span data-ttu-id="d9fbb-259">*版本 2002 (組建 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="d9fbb-259">*Version 2002 (Build 12527.20278)*</span></span>

<span data-ttu-id="d9fbb-260">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="d9fbb-260">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="d9fbb-262">功能更新</span><span class="sxs-lookup"><span data-stu-id="d9fbb-262">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="d9fbb-263">Access</span><span class="sxs-lookup"><span data-stu-id="d9fbb-263">Access</span></span>

- <span data-ttu-id="d9fbb-264">**快速尋找連結資料表：** 新的搜尋方塊可讓您輕鬆尋找連結資料表。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-264">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="d9fbb-265">深入了解</span><span class="sxs-lookup"><span data-stu-id="d9fbb-265">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="d9fbb-266">Excel</span><span class="sxs-lookup"><span data-stu-id="d9fbb-266">Excel</span></span>

- <span data-ttu-id="d9fbb-267">**使用 \@提及取得他人注意：** 在註解中使用 @提及功能，讓同事知道您需要他們提供建議。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-267">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="d9fbb-268">深入了解</span><span class="sxs-lookup"><span data-stu-id="d9fbb-268">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="d9fbb-269">**找到您要尋找的項目：** 搜尋命令、人員、檔案、相片、網頁文章等。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-269">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="d9fbb-270">深入了解</span><span class="sxs-lookup"><span data-stu-id="d9fbb-270">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- <span data-ttu-id="d9fbb-271">**勾勒草圖：** 為活頁簿中的 Office 圖形提供隨意的手繪外觀。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-271">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="d9fbb-272">深入了解</span><span class="sxs-lookup"><span data-stu-id="d9fbb-272">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="d9fbb-273">**更快速共用檔案：** 不需開啟檔案，即可從最近使用清單直接共用您的檔案。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-273">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="d9fbb-274">**不必再來回往返瀏覽器：** 您決定開啟 Office 文件連結的方式：在瀏覽器或應用程式中開啟。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-274">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="d9fbb-275">**專注在待辦事項上：** 選取 [解決] 來摺疊註解，使得開啟中的項目能夠突顯。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-275">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="d9fbb-276">**建立更易於存取的 PDF：** 建立 PDF 檔案，在儲存之前，協助工具檢查程式會指出應該修正的協助工具問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-276">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="d9fbb-277">深入了解</span><span class="sxs-lookup"><span data-stu-id="d9fbb-277">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="d9fbb-278">**轉換檔案，以提升存取性：** 將您的檔案升級為現代格式，讓所有人更容易存取。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-278">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="d9fbb-279">**資料視覺化工具增益集：** 從 Excel 快速建立 Visio 流程圖。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-279">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="d9fbb-280">深入了解</span><span class="sxs-lookup"><span data-stu-id="d9fbb-280">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="d9fbb-281">**即時讀取與回覆：** 直接從電子郵件回覆註解和提及，而不需開啟活頁簿。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-281">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="d9fbb-282">**在活頁簿上取得統計資料：** 活頁簿統計資料提供活頁簿內容的概觀，協助您更輕鬆地探索其內容。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-282">**Get stats on your workbook:** Workbook Statistics provides an overview of the content of a workbook, to help you more easily discover its contents.</span></span>

- <span data-ttu-id="d9fbb-283">**符合您情境的更多圖示：** 我們新增了超過 300 個新圖示。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-283">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="d9fbb-284">其位置：[插入] > [圖示]。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-284">Find them at Insert > Icons.</span></span> [<span data-ttu-id="d9fbb-285">深入了解</span><span class="sxs-lookup"><span data-stu-id="d9fbb-285">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="outlook"></a><span data-ttu-id="d9fbb-286">Outlook</span><span class="sxs-lookup"><span data-stu-id="d9fbb-286">Outlook</span></span>

- <span data-ttu-id="d9fbb-287">**將您的 LinkedIn 人際網路連接至 Outlook：** 安全地將您的 LinkedIn 帳戶與 Microsoft 帳戶連結，以直接在人員卡片中查看 LinkedIn 個人資料中的資訊。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-287">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="d9fbb-288">深入了解</span><span class="sxs-lookup"><span data-stu-id="d9fbb-288">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="d9fbb-p120">**集中所有加密選項：** 只要前往 [選項] > [加密]，即可選擇要用來保護電子郵件訊息的方法。[深入了解](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="d9fbb-p120">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="d9fbb-291">**Outlook 中的 [插入連結] 功能表會插入含有租用戶系統管理員所定義的權限的連結：** Outlook 中使用 [插入連結] 所插入的連結，只有具有連結權限的使用者可使用。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-291">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="d9fbb-292">這常會造成使用者來回傳送電子郵件，要求對方授與文件的存取權。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-292">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="d9fbb-293">我們已更新這項體驗，現在插入的連結將具有由租用戶系統管理員設定的預設權限。針對 MSIT，這是「組織可以編輯」，使得以此方式收到共用連結的所有內部使用者將可以存取它。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-293">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="d9fbb-294">**具有拼字問題或錯字的搜尋：** 即使您的拼寫不相符，Outlook 也會找到您要尋找的內容。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-294">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="d9fbb-295">**網路釣魚郵件很容易找到：** 垃圾郵件和網路釣魚訊息的外觀不同，因此您可以從收件匣輕鬆找出並加以清除。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-295">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="d9fbb-296">**抵禦攻擊的進階防護：** 使用 Office 365 進階威脅防護，您會受到保護，不受電子郵件主旨、附加的郵件、簽署的郵件、網路路徑內超連結的攻擊。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-296">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="d9fbb-297">**讓我繪製：** 使用筆跡在圖片上徒手畫或新增繪圖畫布來傳達您的想法。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-297">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="d9fbb-298">深入了解</span><span class="sxs-lookup"><span data-stu-id="d9fbb-298">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="d9fbb-299">**在搜尋結果中查看相關郵件：** Outlook 會分析搜尋字詞，然後在搜尋結果的最上方顯示最相關的電子郵件。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-299">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="d9fbb-300">您也可以在 [最佳結果] 區段中查看依日期排列順序的所有結果。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-300">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="d9fbb-301">深入了解</span><span class="sxs-lookup"><span data-stu-id="d9fbb-301">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

- <span data-ttu-id="d9fbb-302">**取得位置建議：** 排程約會和會議時，請在 [位置] 中開始輸入，Outlook 會建議會議室、地址，以及其他最近使用的位置。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-302">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="d9fbb-303">深入了解</span><span class="sxs-lookup"><span data-stu-id="d9fbb-303">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)

- <span data-ttu-id="d9fbb-304">**在螢幕上容納更多郵件：** 選取 [檢視] > [使用更緊密的間距] 來調整郵件之間的間距。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-304">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="d9fbb-305">深入了解</span><span class="sxs-lookup"><span data-stu-id="d9fbb-305">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="d9fbb-306">**在不同燈光下查看郵件：** 使用太陽/月亮按鈕以在讀取窗格中於淺色和深色背景之間切換。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-306">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="d9fbb-307">深入了解</span><span class="sxs-lookup"><span data-stu-id="d9fbb-307">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="d9fbb-308">**符合您情境的更多圖示：** 我們新增了超過 300 個新圖示。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-308">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="d9fbb-309">其位置：[插入] > [圖示]。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-309">Find them at Insert > Icons.</span></span> [<span data-ttu-id="d9fbb-310">深入了解</span><span class="sxs-lookup"><span data-stu-id="d9fbb-310">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="powerpoint"></a><span data-ttu-id="d9fbb-311">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d9fbb-311">PowerPoint</span></span>

- <span data-ttu-id="d9fbb-312">**在 PowerPoint 中快速即時共同作業：** 在 PowerPoint 中快速即時共同作業</span><span class="sxs-lookup"><span data-stu-id="d9fbb-312">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="d9fbb-313">**新的校對工具：** 不著重您的文字。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-313">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="d9fbb-314">PowerPoint 現在提供文法及書寫建議。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-314">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="d9fbb-315">深入了解</span><span class="sxs-lookup"><span data-stu-id="d9fbb-315">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="d9fbb-316">**即時的輔助字幕和翻譯字幕：** 簡報者的文字會自動顯示為畫面上的標題，或翻譯為所選語言的字幕。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-316">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="d9fbb-317">深入了解</span><span class="sxs-lookup"><span data-stu-id="d9fbb-317">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="d9fbb-p130">**您來計算，格式設定交給我們**我們能將難懂的手寫數學運算式變更為標準字元。只要選擇 [筆跡轉換數學]，然後選取您的手寫筆記，即可開始使用。[深入了解](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="d9fbb-p130">**You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

- <span data-ttu-id="d9fbb-321">**尋找您要尋找的項目：** 使用搜尋方塊來尋找文字、命令、說明等。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-321">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="d9fbb-322">深入了解</span><span class="sxs-lookup"><span data-stu-id="d9fbb-322">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="d9fbb-323">**尋找並修正遺失的投影片標題：** 投影片標題可為您的企劃加分，並讓所有功能的使用者都能存取投影片。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-323">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="d9fbb-324">協助工具檢查程式會顯示缺少標題的地方，這樣您就可以快速新增標題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-324">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="d9fbb-325">深入了解</span><span class="sxs-lookup"><span data-stu-id="d9fbb-325">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="d9fbb-326">**勾勒草圖：** 為簡報中的 Office 圖形提供隨意的手繪外觀。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-326">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="d9fbb-327">深入了解</span><span class="sxs-lookup"><span data-stu-id="d9fbb-327">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="d9fbb-328">**更快速共用檔案：** 不需開啟檔案，即可從最近使用清單直接共用您的檔案。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-328">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="d9fbb-329">**不必再來回往返瀏覽器：** 您決定開啟 Office 文件連結的方式：在瀏覽器或應用程式中開啟。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-329">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="d9fbb-330">**將圖例另存成 SVG：** 將圖表、圖形或其他圖例另存成可縮放向量圖形，其可調整大小，且不損失影像品質。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-330">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="d9fbb-331">深入了解</span><span class="sxs-lookup"><span data-stu-id="d9fbb-331">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="d9fbb-332">**列印講義上的投影片編號：** 投影片編號會自動包含在講義上。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-332">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="d9fbb-333">由您決定將其保留或關閉。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-333">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="d9fbb-334">深入了解</span><span class="sxs-lookup"><span data-stu-id="d9fbb-334">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="d9fbb-335">**筆跡立即重播：** 當您在投影片上進行手寫時，套用重播動畫可在投影片放映期間重播真實手繪的筆跡。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-335">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="d9fbb-336">深入了解</span><span class="sxs-lookup"><span data-stu-id="d9fbb-336">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- <span data-ttu-id="d9fbb-337">**建立更易於存取的 PDF：** 建立 PDF 檔案，在儲存之前，協助工具檢查程式會指出應該修正的協助工具問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-337">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

- <span data-ttu-id="d9fbb-338">**全方位最佳化您的簡報：** 協助工具檢查程式可協助您以螢幕閱讀器為中心，在投影片上排列物件。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-338">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

- <span data-ttu-id="d9fbb-339">**轉換檔案以增強協助工具功能：** 將您的檔案升級為現代格式，讓所有人更容易存取。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-339">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="d9fbb-340">**更安全的影片體驗：** 安全性增強功能可讓您擁有更安全的線上影片體驗。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-340">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="d9fbb-341">**當您可以重複使用時為什麼要重新打造？** 重複使用您所建立的投影片或其他人與您共用的投影片來以節省時間。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-341">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="d9fbb-342">深入了解</span><span class="sxs-lookup"><span data-stu-id="d9fbb-342">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

- <span data-ttu-id="d9fbb-343">**在 Office 365 的 PowerPoint 中將手寫筆跡變更為圖形、文字或數學：** 從任意格式的筆跡變成 Office 圖形、文字，或以幾個筆劃變成數學運算式。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-343">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="d9fbb-344">深入了解</span><span class="sxs-lookup"><span data-stu-id="d9fbb-344">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="d9fbb-345">**運用筆跡製作精彩的投影片：** 將筆跡轉換成標準圖形和文字，然後從 PowerPoint 設計工具吸取智慧的投影片設計概念。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-345">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="d9fbb-346">深入了解</span><span class="sxs-lookup"><span data-stu-id="d9fbb-346">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- <span data-ttu-id="d9fbb-347">**符合您情境的更多圖示：** 我們新增了超過 300 個新圖示。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-347">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="d9fbb-348">其位置：[插入] > [圖示]。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-348">Find them at Insert > Icons.</span></span> [<span data-ttu-id="d9fbb-349">深入了解</span><span class="sxs-lookup"><span data-stu-id="d9fbb-349">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="visio"></a><span data-ttu-id="d9fbb-350">Visio</span><span class="sxs-lookup"><span data-stu-id="d9fbb-350">Visio</span></span>

- <span data-ttu-id="d9fbb-351">**回到犯罪場景：** 在犯罪場景調查範本中使用新的證據、室內、室外樣板，重建犯罪場景的細節。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-351">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

- <span data-ttu-id="d9fbb-352">**在 Excel 中製作精美的 Visio 圖表：** 將資料放在工作表上，以建立流程圖或組織圖。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-352">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="d9fbb-353">深入了解</span><span class="sxs-lookup"><span data-stu-id="d9fbb-353">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="d9fbb-354">Word</span><span class="sxs-lookup"><span data-stu-id="d9fbb-354">Word</span></span>

- <span data-ttu-id="d9fbb-355">**簡歷編輯器加入 LinkedIn 簡歷小幫手：** 簡歷編輯器提供特別為簡歷量身打造的文法和樣式檢查選項，讓您的寫作更準確且更專業。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-355">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="d9fbb-356">**修正合併 3D 物件所造成的文件損毀問題：** 修正合併 3D 物件所造成的文件損毀問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-356">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="d9fbb-357">**尋找您要尋找的項目：** 使用搜尋方塊來尋找文字、命令、說明等。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-357">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="d9fbb-358">深入了解</span><span class="sxs-lookup"><span data-stu-id="d9fbb-358">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="d9fbb-359">**在生動色彩中進行共同作業：** 註解和變更都依參與者加上色彩標示，讓您可以輕鬆查看您的共同作業者。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-359">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="d9fbb-360">**共同編輯啟用巨集的文件：** 將 docm 檔案儲存在商務用 OneDrive，並與共同作業者即時編輯。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-360">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

- <span data-ttu-id="d9fbb-361">**共同撰寫的增強功能**：在具有追蹤修訂的文件中共同撰寫來強化 Word 效能。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-361">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="d9fbb-362">**符合您情境的更多圖示：** 我們新增了超過 300 個新圖示。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-362">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="d9fbb-363">其位置：[插入] > [圖示]。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-363">Find them at Insert > Icons.</span></span> [<span data-ttu-id="d9fbb-364">深入了解</span><span class="sxs-lookup"><span data-stu-id="d9fbb-364">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="d9fbb-365">**其他人更快速看到您的變更：** 共同撰寫增強功能表示，共同作業者可較以往更快速看到您的變更。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-365">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="d9fbb-366">**勾勒草圖：** 為文件中的 Office 圖形提供隨意的手繪外觀。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-366">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="d9fbb-367">深入了解</span><span class="sxs-lookup"><span data-stu-id="d9fbb-367">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="d9fbb-368">**精確橡皮擦：** 從兩個橡皮擦尺寸中選擇，以修正小型筆跡缺陷。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-368">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="d9fbb-369">深入了解</span><span class="sxs-lookup"><span data-stu-id="d9fbb-369">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="d9fbb-370">**更快速共用檔案：** 不需開啟檔案，即可從最近使用清單直接共用您的檔案。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-370">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="d9fbb-371">**不必再來回往返瀏覽器：** 您決定開啟 Office 文件連結的方式：在瀏覽器或應用程式中開啟。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-371">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="d9fbb-372">深入了解</span><span class="sxs-lookup"><span data-stu-id="d9fbb-372">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="d9fbb-373">**共同撰寫的增強功能**：增強共同撰寫時的可靠性。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-373">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="d9fbb-374">**建立更易於存取的 PDF：** 建立 PDF 檔案，在儲存之前，協助工具檢查程式會指出應該修正的協助工具問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-374">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="d9fbb-375">深入了解</span><span class="sxs-lookup"><span data-stu-id="d9fbb-375">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="d9fbb-376">**轉換檔案，以改善協助工具功能：** 將您的檔案升級為現代格式，讓所有人更容易存取。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-376">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="d9fbb-377">**更安全的影片體驗：** 安全性增強功能可讓您擁有更安全的線上影片體驗。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-377">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="d9fbb-378">深入了解</span><span class="sxs-lookup"><span data-stu-id="d9fbb-378">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)





[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="d9fbb-381">解決的問題</span><span class="sxs-lookup"><span data-stu-id="d9fbb-381">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="d9fbb-382">Access</span><span class="sxs-lookup"><span data-stu-id="d9fbb-382">Access</span></span>

- <span data-ttu-id="d9fbb-383">此更新可修正 Microsoft Access 中的「更新查詢」執行時或在 SQL 中使用 UPDATE 陳述式時，可能導致發生錯誤「查詢已損壞」&quot;&quot;的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-383">This update fixes an issue in Microsoft Access that may cause the error &quot;Query is Corrupt&quot; when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

- <span data-ttu-id="d9fbb-384">此更新修正可能會導致 Microsoft Access 無法識別連結的 SQL Server 資料表中的識別資料行的問題，這可能會導致不正確地將資料列報告為已刪除。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-384">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="d9fbb-385">此更新會修正使用 ADODB 的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-385">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="d9fbb-386">VB 程式碼中的記錄器物件可能會不正確地報告錯誤。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-386">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="d9fbb-387">Access 範本應不再導致資料庫中的附件欄出現故障。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-387">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="d9fbb-388">個體化範本後，您現在應該可以將附件欄新增至資料庫。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-388">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

### <a name="excel"></a><span data-ttu-id="d9fbb-389">Excel</span><span class="sxs-lookup"><span data-stu-id="d9fbb-389">Excel</span></span>

- <span data-ttu-id="d9fbb-390">解決重新命名簽名時，使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-390">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="d9fbb-391">這項變更透過利用軟體轉譯來避免特定 Intel 圖形驅動程式的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-391">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="d9fbb-392">修正對具有溢出陣列之儲存格進行資料剖析的轉換時，導致某些使用者發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-392">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="d9fbb-393">此更新可修正導致資料編輯列以預期不同的字型顯示文字的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-393">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="d9fbb-394">[資料剖析] 功能對某些地區設定可能會失敗。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-394">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="d9fbb-395">使用者在存取隱藏的命名範圍時可能會遇到錯誤。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-395">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="d9fbb-396">使用者在使用某些非英文字元集的情況下，儲存變更時可能會遇到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-396">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="d9fbb-397">解決捲動後選取儲存格時，可能導致選取錯誤儲存格的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-397">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="d9fbb-398">從不受信任的網路共用編輯受保護的檔案時，Excel 可能會發生問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-398">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="d9fbb-399">某些當地語系化版本的 [資料剖析] 功能可能會失敗。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-399">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="d9fbb-400">使用者在存取隱藏的命名範圍時可能會遇到錯誤。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-400">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="d9fbb-401">使用者在使用某些非英文字元集的情況下，儲存變更時可能會遇到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-401">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="d9fbb-402">修正某些使用者使用內嵌和連結化物件 (OLE) 時可能發生的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-402">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="d9fbb-403">我們修正了樞紐分析圖的右鍵功能表，以啟用 [顯示詳細資料] 選項。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-403">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="d9fbb-404">解決在未開啟活頁簿時，搜尋最近使用的檔案會造成當機的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-404">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="d9fbb-405">修正當活頁簿中有外部連結時，有些使用者可能會遇到多個彈出式視窗的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-405">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="d9fbb-406">修正操作功能表中未顯示註解命令的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-406">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="d9fbb-407">解決開啟內嵌活頁簿時，功能區自訂無法載入的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-407">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="d9fbb-408">修正 CUBEVALUE 函數有時會傳回不正確結果的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-408">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

### <a name="outlook"></a><span data-ttu-id="d9fbb-409">Outlook</span><span class="sxs-lookup"><span data-stu-id="d9fbb-409">Outlook</span></span>

- <span data-ttu-id="d9fbb-410">已解決導致在搜尋意見反應體驗中懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-410">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="d9fbb-411">解決在擷取雲端設定時，導致使用者在 Outlook 中遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-411">Addressed an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="d9fbb-412">解決導致搜尋方塊在高 DPI 模式中未正確對齊的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-412">Addressed an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="d9fbb-413">解決導致使用者在 Outlook 處理序中看到記憶體流失的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-413">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="d9fbb-414">解決在某些情況下，導致使用者看到電子郵件傳送到與顯示的 SMTP 位址不相符之地址的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-414">Addressed an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="d9fbb-415">此變更會還原在郵件標頭中檢視多行主旨的功能。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-415">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="d9fbb-416">我們已修正會防止將檔案儲存到 WebDAV 位置的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-416">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="d9fbb-417">修正 SMIME 演算法選取的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-417">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="d9fbb-418">解決導致協力廠商應用程式無法傳送電子郵件的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-418">Addressed an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="d9fbb-419">解決會導致使用者在嘗試從 [帳戶建立] 內容連絡支援服務時，看到具有 [確定]&quot;&quot; 按鈕的空白訊息方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-419">Addressed an issue that caused users to see an empty message box with an &quot;OK&quot; button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="d9fbb-420">解決導致使用者在建立設定檔時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-420">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="d9fbb-421">解決即使將同步處理滑桿設定為較小的設定，也會導致 Outlook 非預期地同步處理所有郵件的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-421">Addressed an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="d9fbb-422">解決導致使用黑色佈景主題的使用者看到 [寄件者]&quot;&quot; 下拉式清單在白色背景上顯示白色文字的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-422">Addressed an issue that caused users with Black Theme to see the &quot;From&quot; dropdown show white text on a white background.</span></span>

- <span data-ttu-id="d9fbb-423">解決導致使用者在取消帳戶設定時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-423">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="d9fbb-424">解決重新命名簽名時，使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-424">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="d9fbb-425">解決導致在某些情況下，用來停用標幟項目醒目提示的選項無法使用的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-425">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="d9fbb-426">解決會導致使用者在開啟 [規則] 對話方塊時看到「在這部電腦中建立的規則和 Microsoft Exchange 上的規則衝突」提示的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-426">Addressed an issue that caused users to see a &quot;The rules on this computer do not match the rules on Microsoft Exchange&quot; prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="d9fbb-427">解決導致使用者在指定無效寄件者地址時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-427">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="d9fbb-428">解決導致非常長時間的 Outlook 工作階段記憶體流失的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-428">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="d9fbb-429">解決在多個視窗中檢視相同項目時可能會導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-429">Addressed an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="d9fbb-430">解決當使用者透過鍵盤快速鍵與信箱資料夾互動時，導致明顯延遲的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-430">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="d9fbb-431">解決導致使用者無法開啟某些週期性行事曆項目執行個體的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-431">Addressed an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="d9fbb-432">解決導致使用 Exchange 2010 伺服器上信箱的使用者在將附件新增至行事曆項目時遇到問題的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-432">Addressed an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="d9fbb-433">解決導致使用者在回覆數位簽章的郵件時發生問題的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-433">Addressed an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="d9fbb-434">解決會導致會議中的 [位置] 欄位意外更新的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-434">Addressed an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="d9fbb-435">解決導致會議的位置欄位中的逗號變成分號的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-435">Addressed an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="d9fbb-436">解決導致會議位置在清除之後，又會不預期地重新加回會議的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-436">Addressed an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="d9fbb-437">解決與在巴西時區中設定的會議和約會相關的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-437">Addressed issues relating to meetings and appointments set in the Brazilia time zone.</span></span>

- <span data-ttu-id="d9fbb-438">解決當您關閉協助工具檢查程式窗格之後按 &quot;S&quot; 鍵時，導致使用者看到郵件意外傳送的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-438">Addressed an issue that caused users to see mails unexpectedly send when pressing the &quot;S&quot; key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="d9fbb-439">這會更新 Outlook 中的附件封鎖邏輯，以同時封鎖 Python 附件。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-439">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="d9fbb-440">解決導致網頁增益集存取數位版權管理郵件的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-440">Addressed an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="d9fbb-441">解決導致使用者在建立設定檔時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-441">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="d9fbb-442">解決重新命名簽名時，使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-442">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d9fbb-443">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d9fbb-443">PowerPoint</span></span>

- <span data-ttu-id="d9fbb-444">我們已修正 Shape.Paste 方法的問題：當使用者使用 Shape.Paste 方法複製並貼上圖形時，它會將選取範圍變更為貼上的圖形。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-444">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="d9fbb-445">解決在舊版 PPT 註解中使用操作功能表時可能發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-445">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

### <a name="project"></a><span data-ttu-id="d9fbb-446">Project</span><span class="sxs-lookup"><span data-stu-id="d9fbb-446">Project</span></span>

- <span data-ttu-id="d9fbb-447">發現在開啟唯讀專案時，使用者可能會收到數個訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-447">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="d9fbb-448">修正固定工期類型的 100% 工作可能會誤將其完成百分比計算為小於 100% 完成的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-448">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

- <span data-ttu-id="d9fbb-449">修正無法正確計算摘要工作日期的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-449">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="d9fbb-450">修正不先執行 OpenUndoTransaction 方法就不能觸發 OnUndoOrRedo 事件的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-450">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="d9fbb-451">Word</span><span class="sxs-lookup"><span data-stu-id="d9fbb-451">Word</span></span>

- <span data-ttu-id="d9fbb-452">我們已修正在某些情況下，儲存現有檔案永遠會導致出現 [另存新檔] 對話方塊且檔案永遠不會儲存的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-452">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="d9fbb-453">建置組塊召集人可能會顯示不正確通知：&quot;您已修改過樣式、建置組塊&quot;。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-453">Building blocks organizer may display an invalid alert: &quot;You have modified styles, building blocks&quot;.</span></span>

### <a name="office-suite"></a><span data-ttu-id="d9fbb-454">Office 套件</span><span class="sxs-lookup"><span data-stu-id="d9fbb-454">Office Suite</span></span>

- <span data-ttu-id="d9fbb-455">此變更可解決轉譯某些含有資料標記的散佈圖緩慢的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-455">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="d9fbb-456">此變更可解決所報告使用 Intel 整合式 GPU 圖形配接卡的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-456">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="d9fbb-457">修正相對期限只有在第一次設定時才會有效的 ODT 和 GPO 更新期限設定中的錯誤，此修正可啟用後續更新的相關期限。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-457">Fixed a bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="d9fbb-458">解決 Office 更新可能會非預期地從 Office CDN 而不是預期使用的來源 (例如本機或網路共用或 Configuration Manager 提供的位置) 下載檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-458">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="d9fbb-459">修正在 Word/Excel/PowerPoint 中開啟來自相同 SharePoint 文件庫的多個文件時，僅掃描開啟的第一個文件是否符合原則的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-459">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-february-11"></a><span data-ttu-id="d9fbb-461">版本 1908：2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="d9fbb-461">Version 1908: February 11</span></span>
<span data-ttu-id="d9fbb-462">*版本 1908 (組建 11929.20606)*</span><span class="sxs-lookup"><span data-stu-id="d9fbb-462">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="d9fbb-463">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="d9fbb-463">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="d9fbb-465">解決的問題</span><span class="sxs-lookup"><span data-stu-id="d9fbb-465">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d9fbb-466">Excel</span><span class="sxs-lookup"><span data-stu-id="d9fbb-466">Excel</span></span>

- <span data-ttu-id="d9fbb-467">此更新已修正使用 VBA 將影像新增到圖表的頁首/頁尾時發生錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-467">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="d9fbb-468">已修正在預覽列印或列印時群組方塊控制項的框線無法顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-468">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="d9fbb-469">使用者在使用某些非英文字元集的情況下，儲存變更時可能會遇到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-469">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="d9fbb-470">已修正圖表標題中影像檔案大小在儲存包含圖表的活頁簿時增加的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-470">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="d9fbb-471">已修正以下問題：將選取範圍與交互參照的活頁簿保持同步時，導致交互參照的活頁簿中的 DBCS 字元損毀。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-471">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="d9fbb-472">已解決使用自動調整來調整列高時，核取方塊可能收縮的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-472">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="d9fbb-473">Outlook</span><span class="sxs-lookup"><span data-stu-id="d9fbb-473">Outlook</span></span>

- <span data-ttu-id="d9fbb-474">已解決導致使用者在指定無效寄件者地址時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-474">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="d9fbb-475">已解決導致使用者處理衝突郵件時同步失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-475">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="d9fbb-476">已解決導致使用者在啟動 Outlook 時，「正在載入設定檔」畫面時停滯的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-476">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="d9fbb-477">已解決導致使用者在變更檢視時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-477">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="d9fbb-478">已解決在 Citrix 環境中檢視 30 個以上的行事曆時，導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-478">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="d9fbb-479">[此處](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)是記錄舊版問題的個別 KB。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-479">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="d9fbb-480">已解決以下問題：使用者將共用行事曆資料夾同步到 OST 時發生問題，這導致嘗試與這些資料夾互動時發生權限錯誤。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-480">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="d9fbb-481">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d9fbb-481">PowerPoint</span></span>

- <span data-ttu-id="d9fbb-482">已改善複製貼上的案例，即將 PowerPoint 投影片中的圖形複製並貼到其他投影片可能會因為異常而失敗。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-482">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="d9fbb-483">已修正導致共同作業使用者之間效能較低的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-483">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="d9fbb-484">已修正以下問題：當檔案以漸進式開啟時，若其中一個投影片包含多個內嵌媒體串流可能會發生問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-484">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="d9fbb-485">已修正以下問題：首次啟動 PowerPoint 時，不受信任的增益集可能不會顯示安全性警告訊息列。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-485">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="d9fbb-486">Project</span><span class="sxs-lookup"><span data-stu-id="d9fbb-486">Project</span></span>

- <span data-ttu-id="d9fbb-487">已修正以下問題：由於基準行事曆變更時未更新資源行事曆，而導致時程表和專案計劃之間的實際工作可能不同。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-487">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="d9fbb-488">Word</span><span class="sxs-lookup"><span data-stu-id="d9fbb-488">Word</span></span>

- <span data-ttu-id="d9fbb-489">已從遭取代的 API 移除，以修正 Word 的當機問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-489">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="d9fbb-490">Office 套件</span><span class="sxs-lookup"><span data-stu-id="d9fbb-490">Office Suite</span></span>

- <span data-ttu-id="d9fbb-491">此變更解決開啟損毀的檔案時正確呈現影像的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-491">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-january-14"></a><span data-ttu-id="d9fbb-493">版本 1908：1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="d9fbb-493">Version 1908: January 14</span></span>
<span data-ttu-id="d9fbb-494">*版本 1908 (組建 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="d9fbb-494">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="d9fbb-495">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="d9fbb-495">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="d9fbb-497">解決的問題</span><span class="sxs-lookup"><span data-stu-id="d9fbb-497">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d9fbb-498">Excel</span><span class="sxs-lookup"><span data-stu-id="d9fbb-498">Excel</span></span>

- <span data-ttu-id="d9fbb-499">文件標題的荷蘭文按鍵提示已變更為 Alt-G。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-499">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="d9fbb-500">解決了開啟內嵌活頁簿時，功能區自訂無法載入的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-500">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="d9fbb-501">發生您無法從增益集開啟的 WPF (Windows Presentation Foundation) 表單的下拉式方塊選取項目的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-501">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="d9fbb-502">Outlook</span><span class="sxs-lookup"><span data-stu-id="d9fbb-502">Outlook</span></span>

- <span data-ttu-id="d9fbb-503">解決當使用者透過鍵盤快速鍵與信箱資料夾互動時會造成明顯延遲的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-503">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="d9fbb-504">解決使用其他寄件者時導致無法顯示原則提示的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-504">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="d9fbb-505">解決了導致使用者在更新目前狀態資訊時遇到間歇性當機的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-505">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d9fbb-506">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d9fbb-506">PowerPoint</span></span>

- <span data-ttu-id="d9fbb-507">我們已修正將投影片從一個簡報複製到另一個簡報時可能會造成母片重複的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-507">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>
- <span data-ttu-id="d9fbb-508">如果在不支援的版本中開啟含有新的新式註解的檔案，將會顯示黃色警告</span><span class="sxs-lookup"><span data-stu-id="d9fbb-508">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

### <a name="office-suite"></a><span data-ttu-id="d9fbb-509">Office 套件</span><span class="sxs-lookup"><span data-stu-id="d9fbb-509">Office Suite</span></span>

- <span data-ttu-id="d9fbb-510">修正了 Office 更新訊息不以預期語言顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-510">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="d9fbb-511">自此以後，Office 更新訊息會正確符合 Windows 顯示語言。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-511">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="d9fbb-512">解決在某些情況下，如果使用者不是系統管理員且系統帳戶沒有網路連線，將無法套用更新的問題。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-512">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

> [!NOTE]
> <span data-ttu-id="d9fbb-514">如果您需要關於使用 Office 的問題協助，建議您將問題張貼在 [Microsoft Answers 論壇](https://answers.microsoft.com/)或[技術社群](https://techcommunity.microsoft.com/)，或連絡[支援](https://support.microsoft.com/contactus)。</span><span class="sxs-lookup"><span data-stu-id="d9fbb-514">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (DO NOT MODIFY ADMIN CENTER METADATA CONTENT START)
[//]: # (|Win32|FRDC|測試人員| |16.0.12527.20880|version-2002-july-14|)
[//]: # (DO NOT MODIFY ADMIN CENTER METADATA CONTENT END)
