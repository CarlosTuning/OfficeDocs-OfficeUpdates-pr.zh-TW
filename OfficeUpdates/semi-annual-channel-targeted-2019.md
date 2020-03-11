---
title: 2019 年半年通道 (已設定目標) 版本的版本資訊
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為 IT 專業人員提供 2019 年 Office 365 專業增強版半年通道 (已設定目標) 版本的版本資訊
ms.openlocfilehash: 2384ed54f8e18e89981cdd875d46bfd9ba7e95a5
ms.sourcegitcommit: 59f243dfec169ff246cd68ca7f796fde696e2981
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 03/06/2020
ms.locfileid: "42549324"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2019"></a><span data-ttu-id="a8c82-103">2019 年半年通道 (已設定目標) 版本的版本資訊</span><span class="sxs-lookup"><span data-stu-id="a8c82-103">Release notes for Semi-Annual Channel (Targeted) releases in 2019</span></span>

<span data-ttu-id="a8c82-104">這些版本資訊可提供 2019 年 Office 365 專業增強版、Visio Pro for Office 365、Project Online 電腦版用戶端以及 Office 365 商務版的半年通道 (已設定目標) 更新所含新功能和非安全性更新的相關資訊。</span><span class="sxs-lookup"><span data-stu-id="a8c82-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Channel (Targeted) updates to Office 365 ProPlus in 2019, Visio Pro for Office 365, Project Online Desktop Client and Office 365 Business.</span></span>

> [!NOTE]
> - <span data-ttu-id="a8c82-105">我們通常會在一段時間內推出功能 (有時甚至推出修正程式) 至半年通道 (已設定目標)。</span><span class="sxs-lookup"><span data-stu-id="a8c82-105">We often roll out features (and sometimes even fixes) to Semi-Annual Channel (Targeted) over a period of time.</span></span> <span data-ttu-id="a8c82-106">如果您現在沒有看到如下所述的項目，您可以預期它近期會推出。</span><span class="sxs-lookup"><span data-stu-id="a8c82-106">If you don’t see something described below right away, you can expect it soon.</span></span> [<span data-ttu-id="a8c82-107">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-107">Learn more</span></span>](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516?ui=en-US&rs=en-US&ad=US)
> - <span data-ttu-id="a8c82-108">從版本 1902 開始，Microsoft Teams 會包含在半年通道 (已設定目標) 的全新安裝中。</span><span class="sxs-lookup"><span data-stu-id="a8c82-108">Microsoft Teams is included in new installations of Semi-Annual Channel(Targeted), starting with Version 1902.</span></span> <span data-ttu-id="a8c82-109">將 Teams 更新至版本 1908 或更新版本時，即會將 Teams 新增至半年通道 (已設定目標) 的現有安裝中。</span><span class="sxs-lookup"><span data-stu-id="a8c82-109">Teams will be added to existing installations of Semi-Annual Channel(Targeted) when those are updated to Version 1908 or later.</span></span> <span data-ttu-id="a8c82-110">如需詳細資訊，請參閱[使用 Office 365 專業增強版部署 Microsoft Teams](https://docs.microsoft.com/DeployOffice/teams-install)。</span><span class="sxs-lookup"><span data-stu-id="a8c82-110">For more information, see [Deploy Microsoft Teams with Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/teams-install).</span></span>

## <a name="version-1908-december-10"></a><span data-ttu-id="a8c82-111">版本 1908：12 月 10 日</span><span class="sxs-lookup"><span data-stu-id="a8c82-111">Version 1908: December 10</span></span>
<span data-ttu-id="a8c82-112">*版本 1908 (組建 11929.20516)*</span><span class="sxs-lookup"><span data-stu-id="a8c82-112">*Version 1908 (Build 11929.20516)*</span></span>

<span data-ttu-id="a8c82-113">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="a8c82-113">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="a8c82-115">解決的問題</span><span class="sxs-lookup"><span data-stu-id="a8c82-115">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="a8c82-116">Access</span><span class="sxs-lookup"><span data-stu-id="a8c82-116">Access</span></span>

- <span data-ttu-id="a8c82-117">已修正包含參照遠端桌面 (例如 SQL Server 桌面) 的聯集查詢可能造成 Access 關閉並重新啟動的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-117">Fixed an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="a8c82-118">已修正彙總 (例如 Sum) 可能會將結果截斷成整數值的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-118">Fixed an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

### <a name="excel"></a><span data-ttu-id="a8c82-119">Excel</span><span class="sxs-lookup"><span data-stu-id="a8c82-119">Excel</span></span>

- <span data-ttu-id="a8c82-120">已解決捲動後選取儲存格時，可能導致選取錯誤儲存格的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-120">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="a8c82-121">我們已修正當 OLAP 樞紐分析表的篩選條件設定為已從 cube 移除的值時會發生的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-121">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="a8c82-122">這項變更透過利用軟體轉譯避免特定 Intel 圖形驅動程式發生問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-122">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="a8c82-123">已解決 Lookup 函數可能會傳回錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-123">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="a8c82-124">已大幅改善刪除有合併儲存格之欄的效能。</span><span class="sxs-lookup"><span data-stu-id="a8c82-124">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="a8c82-125">已解決造成執行階段錯誤啟動最小化視窗的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-125">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

### <a name="outlook"></a><span data-ttu-id="a8c82-126">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8c82-126">Outlook</span></span>

- <span data-ttu-id="a8c82-127">已修正 SMIME 演算法選取的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-127">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="a8c82-128">解決會導致使用者在開啟 [規則] 對話方塊時看到「在這部電腦中建立的規則和 Microsoft Exchange 上的規則衝突」提示的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-128">Addressed an issue that caused users to see a &quot;The rules on this computer do not match the rules on Microsoft Exchange&quot; prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="a8c82-129">已解決造成網頁增益集在不該存取數位版權管理郵件時進行存取的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-129">Addressed an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

### <a name="word"></a><span data-ttu-id="a8c82-130">Word</span><span class="sxs-lookup"><span data-stu-id="a8c82-130">Word</span></span>

- <span data-ttu-id="a8c82-131">我們已修正追蹤修訂有時候會進入無限迴圈的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-131">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a8c82-132">Office 套件</span><span class="sxs-lookup"><span data-stu-id="a8c82-132">Office Suite</span></span>

- <span data-ttu-id="a8c82-133">已修正 PowerPoint 中半形片假名字元在垂直文字方塊中無法正確旋轉的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-133">Fixed an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

- <span data-ttu-id="a8c82-134">解決 Office 更新可能會非預期地從 Office CDN 而不是預期使用的來源 (例如本機或網路共用或 Configuration Manager 提供的位置) 下載檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-134">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="a8c82-135">為了保護 Office 客戶的安全性，我們現在專門使用 SHA-2 演算法來簽署 Microsoft Office 更新。</span><span class="sxs-lookup"><span data-stu-id="a8c82-135">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-november-22"></a><span data-ttu-id="a8c82-137">版本 1908：11 月 22 日</span><span class="sxs-lookup"><span data-stu-id="a8c82-137">Version 1908: November 22</span></span>
<span data-ttu-id="a8c82-138">*版本 1908 (組建 11929.20494)*</span><span class="sxs-lookup"><span data-stu-id="a8c82-138">*Version 1908 (Build 11929.20494)*</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="a8c82-140">解決的問題</span><span class="sxs-lookup"><span data-stu-id="a8c82-140">Resolved issues</span></span>

### <a name="access"></a><span data-ttu-id="a8c82-141">Access</span><span class="sxs-lookup"><span data-stu-id="a8c82-141">Access</span></span>

- <span data-ttu-id="a8c82-142">已修正執行更新查詢會不正確顯示「查詢損毀」錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-142">Fixed an issue where running an Update query would incorrectly give an error message: "Query is corrupt".</span></span>

### <a name="excel"></a><span data-ttu-id="a8c82-143">Excel</span><span class="sxs-lookup"><span data-stu-id="a8c82-143">Excel</span></span>

- <span data-ttu-id="a8c82-144">當檔案具備大量設定格式化的條件時，按一下 [字型色彩] 按鈕時出現的效能緩慢問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-144">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="a8c82-145">我們已修正預覽列印中的列印範圍不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-145">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="a8c82-146">從不受信任的網路共用編輯受保護的檔案時，Excel 可能會發生問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-146">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="a8c82-147">解決在未開啟活頁簿時，搜尋最近使用的檔案會造成當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-147">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

### <a name="outlook"></a><span data-ttu-id="a8c82-148">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8c82-148">Outlook</span></span>

- <span data-ttu-id="a8c82-149">解決會導致使用者在嘗試從 [帳戶建立] 內容連絡支援服務時，看到具有 [確定]&quot;&quot; 按鈕的空白訊息方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-149">Addressed an issue that caused users to see an empty message box with an &quot;OK&quot; button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="a8c82-150">進行一項變更，可讓系統管理員啟用一個原則，以在自動探索驗證提示中較 UPN 優先使用所提供的帳戶電子郵件。</span><span class="sxs-lookup"><span data-stu-id="a8c82-150">Made a change that allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="a8c82-151">依預設，自動探索會優先於帳戶 UPN (如果有的話)。</span><span class="sxs-lookup"><span data-stu-id="a8c82-151">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="a8c82-152">解決會導致使用者看到針對新式群組的搜尋失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-152">Addressed an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="a8c82-153">解決會導致使用者嘗試從「未接的交談」&quot;&quot;建立規則時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-153">Addressed an issue that caused users to experience a crash when attempting to create a rule from a &quot;Missed Conversation&quot; message.</span></span>

- <span data-ttu-id="a8c82-154">解決會導致使用者看到針對新式群組的搜尋失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-154">Addresses an issue that caused users to see search failing against Modern Groups.</span></span>

### <a name="word"></a><span data-ttu-id="a8c82-155">Word</span><span class="sxs-lookup"><span data-stu-id="a8c82-155">Word</span></span>

- <span data-ttu-id="a8c82-156">我們已修正了當列印到 Deskjet 印表機時，可能會導致縮放比例問題的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-156">We fixed an issue which could have caused scaling issues when printing to Deskjet printers.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a8c82-157">Office 套件</span><span class="sxs-lookup"><span data-stu-id="a8c82-157">Office Suite</span></span>

- <span data-ttu-id="a8c82-158">修正會在嘗試進行「線上展示」時防止 PowerPoint 使用者遇到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-158">Fixed an issue to prevent PowerPoint users from running into error when trying to Present Online.</span></span>

- <span data-ttu-id="a8c82-159">改善有關登錄完整性的 Office 更新程序的可靠性。</span><span class="sxs-lookup"><span data-stu-id="a8c82-159">Improved reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="a8c82-160">更正可能會在計量網路上意外封鎖更新的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-160">Corrected an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="a8c82-161">修正 ODT 和 GPO 更新期限設定中的問題，在其中，相對期限只有在第一次設定時才會有效，此修正可啟用後續更新的相關期限。</span><span class="sxs-lookup"><span data-stu-id="a8c82-161">Fixed an issue in ODT and GPO Updae Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-november-12"></a><span data-ttu-id="a8c82-163">版本 1908：11 月 12 日</span><span class="sxs-lookup"><span data-stu-id="a8c82-163">Version 1908: November 12</span></span>
<span data-ttu-id="a8c82-164">*版本 1908 (組建 11929.20436)*</span><span class="sxs-lookup"><span data-stu-id="a8c82-164">*Version 1908 (Build 11929.20436)*</span></span>

<span data-ttu-id="a8c82-165">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="a8c82-165">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="a8c82-167">解決的問題</span><span class="sxs-lookup"><span data-stu-id="a8c82-167">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="a8c82-168">Excel</span><span class="sxs-lookup"><span data-stu-id="a8c82-168">Excel</span></span>

- <span data-ttu-id="a8c82-169">修正以校正使用圖表範本插入圖表時，預覽中使用的色彩。</span><span class="sxs-lookup"><span data-stu-id="a8c82-169">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>
- <span data-ttu-id="a8c82-170">我們已修正當變更系列集合時，可能會導致散佈折線圖無法正確呈現的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-170">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span>
- <span data-ttu-id="a8c82-171">解決使用執行中巨集變更自訂屬性時，會導致共同撰寫中斷的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-171">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>
- <span data-ttu-id="a8c82-172">我們解決了非同步使用者定義函數造成的效能問題，導致它們同步執行。</span><span class="sxs-lookup"><span data-stu-id="a8c82-172">We resolved an performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>
- <span data-ttu-id="a8c82-173">我們已大幅提升依色彩篩選的效能。</span><span class="sxs-lookup"><span data-stu-id="a8c82-173">We have significantly improved the performance of filtering by color.</span></span>
- <span data-ttu-id="a8c82-174">解決在目前的 Office 版本中開啟在舊版 Office 中建立的活頁簿時，可能導致 Excel 懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-174">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>
- <span data-ttu-id="a8c82-175">來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。</span><span class="sxs-lookup"><span data-stu-id="a8c82-175">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

### <a name="outlook"></a><span data-ttu-id="a8c82-176">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8c82-176">Outlook</span></span>

- <span data-ttu-id="a8c82-177">來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。</span><span class="sxs-lookup"><span data-stu-id="a8c82-177">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>
- <span data-ttu-id="a8c82-178">解決當使用者將項目從其主要行事曆複製到群組行事曆時，造成使用者遇到權限錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-178">Addressed an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>
- <span data-ttu-id="a8c82-179">解決會導致非常長時間的 Outlook 工作階段記憶體流失的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-179">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>
- <span data-ttu-id="a8c82-180">解決會導致使用者在與特定安全連結互動時在 Outlook 中遇到失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-180">Addressed an issue that would cause users to experience a failure in Outlook when interacting with certain safelinks.</span></span>
- <span data-ttu-id="a8c82-181">解決會導致使用者在處理某些自動探索回應時遇到失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-181">Addressed an issue that caused users to experience a failure when processing some AutoDiscover responses.</span></span>
- <span data-ttu-id="a8c82-182">解決導致某些使用者在新增次要 Exchange 帳戶時看到建立了重複的特殊資料夾的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-182">Addressed an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>
- <span data-ttu-id="a8c82-183">解決會導致在搜尋意見反應體驗中懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-183">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8c82-184">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8c82-184">PowerPoint</span></span>

- <span data-ttu-id="a8c82-185">來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。</span><span class="sxs-lookup"><span data-stu-id="a8c82-185">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span></div>
- <span data-ttu-id="a8c82-186">可靠性修正：修正第三方增益集可能會造成 PowerPoint 失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-186">Reliability fix: Fixed an issue where third party add-in might cause PowerPoint to fail.</span></span>

### <a name="project"></a><span data-ttu-id="a8c82-187">Project</span><span class="sxs-lookup"><span data-stu-id="a8c82-187">Project</span></span>

- <span data-ttu-id="a8c82-188">修正 [全部撫平] 命令無法正確解決資源過度分配的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-188">Fixed an issue where the Level All command wasn't properly resolving a resource overallocation.</span></span>
- <span data-ttu-id="a8c82-189">修正當您有作業中有零個工作的指派時，可能無法將作業標示為完成且永遠會顯示為 99% 的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-189">Fixed an issue where if you have an assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>
- <span data-ttu-id="a8c82-190">發現在開啟唯讀專案時，使用者可能會收到數個訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-190">Identified an issue where users could get several messages when opening a read-only project.</span></span>

### <a name="word"></a><span data-ttu-id="a8c82-191">Word</span><span class="sxs-lookup"><span data-stu-id="a8c82-191">Word</span></span>

- <span data-ttu-id="a8c82-192">來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。</span><span class="sxs-lookup"><span data-stu-id="a8c82-192">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>
- <span data-ttu-id="a8c82-193">修正應用程式可能在關機時懸置的各種問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-193">Fixed various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="a8c82-194">同時修正特定增益集相關失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-194">Also fixed certain add-in related failures.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a8c82-195">Office 套件</span><span class="sxs-lookup"><span data-stu-id="a8c82-195">Office Suite</span></span>

- <span data-ttu-id="a8c82-196">解決第三方外掛程式中與文字方塊/圖案自動調整屬性相關的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-196">Addressed issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="october-15"></a><span data-ttu-id="a8c82-198">10 月 15 日</span><span class="sxs-lookup"><span data-stu-id="a8c82-198">October 15</span></span>

### <a name="non-security-updates"></a><span data-ttu-id="a8c82-199">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-199">Non-security updates</span></span>

### <a name="office-suite"></a><span data-ttu-id="a8c82-200">Office 套件</span><span class="sxs-lookup"><span data-stu-id="a8c82-200">Office Suite</span></span>
- <span data-ttu-id="a8c82-201">我們已暫時停用 [雲端儲存] 對話方塊以解決在 2019 年 10 月14 日針對早於 16.0.11929.20396 的組建所發佈的儲存問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-201">We have temporarily disabled the Cloud Save dialog to address the saving issue we posted on October 14, 2019 for builds older than 16.0.11929.20396.</span></span> <span data-ttu-id="a8c82-202">這項功能即將重新啟用。</span><span class="sxs-lookup"><span data-stu-id="a8c82-202">This feature will be re-enabled soon.</span></span>

## <a name="version-1908-october-14"></a><span data-ttu-id="a8c82-203">版本 1908：10 月 14 日</span><span class="sxs-lookup"><span data-stu-id="a8c82-203">Version 1908: October 14</span></span>
<span data-ttu-id="a8c82-204">*版本 1908 (組建 11929.20396)*</span><span class="sxs-lookup"><span data-stu-id="a8c82-204">*Version 1908 (Build 11929.20396)*</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a><span data-ttu-id="a8c82-206">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-206">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="a8c82-207">Excel</span><span class="sxs-lookup"><span data-stu-id="a8c82-207">Excel</span></span>

- <div><span data-ttu-id="a8c82-208">解決「尋找及取代」在找到第一個項目後，對話方塊中的焦點位置變更的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-208">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span></div>

### <a name="office-suite"></a><span data-ttu-id="a8c82-209">Office 套件</span><span class="sxs-lookup"><span data-stu-id="a8c82-209">Office Suite</span></span>

- <span data-ttu-id="a8c82-210">解決使用者使用早於 16.0.11929.20396 的組建時，可能無法儲存 Word、Excel 和 PowerPoint 2019 文件的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-210">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint 2019 documents for builds older than 16.0.11929.20396.</span></span>  <span data-ttu-id="a8c82-211">此問題會影響建立新檔案並在按一下 [儲存] 圖示或按 Ctrl + S 之後帶出 [另存新檔] 對話方塊的使用者。</span><span class="sxs-lookup"><span data-stu-id="a8c82-211">This issue affects users that create a new file and bring up the “Save As” dialog after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="a8c82-212">解決在某些情況下，Office 快速鍵可能會在更新後消失的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-212">Resolved an issue where in certain circumstances, Office shortcuts may disappear following an update.</span></span>  <span data-ttu-id="a8c82-213">此更新可改善發佈 Office 快速鍵時的可靠性。</span><span class="sxs-lookup"><span data-stu-id="a8c82-213">This update improves reliability when publishing of Office shortcuts.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-october-08"></a><span data-ttu-id="a8c82-215">版本 1908：10 月 8 日</span><span class="sxs-lookup"><span data-stu-id="a8c82-215">Version 1908: October 08</span></span>
<span data-ttu-id="a8c82-216">*版本 1908 (組建 11929.20388)*</span><span class="sxs-lookup"><span data-stu-id="a8c82-216">*Version 1908 (Build 11929.20388)*</span></span>

<span data-ttu-id="a8c82-217">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="a8c82-217">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a><span data-ttu-id="a8c82-219">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-219">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="a8c82-220">Excel</span><span class="sxs-lookup"><span data-stu-id="a8c82-220">Excel</span></span>

- <span data-ttu-id="a8c82-221">已解決會導致將超連結貼到一些受保護工作表中的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-221">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="a8c82-222">已修正當在增益集管理員中瀏覽時，顯示 16 個以上的增益集的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-222">Fixed an issue to enable more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="a8c82-223">已修正在 Excel 構想功能中，在 Win32 用戶端中按一下 [構想] 按鈕來載入增益集時會發生錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-223">Fixed issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span>

### <a name="outlook"></a><span data-ttu-id="a8c82-224">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8c82-224">Outlook</span></span>

- <span data-ttu-id="a8c82-225">已解決導致部分安全連結無法顯示簡單動態顯示 URL 的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-225">Addressed an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="a8c82-226">已更新 Outlook 中的附件封鎖邏輯，以同時封鎖 python 附件。</span><span class="sxs-lookup"><span data-stu-id="a8c82-226">Updated the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="a8c82-227">已解決導致使用者在 Outlook 處理序中看到記憶體洩漏的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-227">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8c82-228">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8c82-228">PowerPoint</span></span>

- <span data-ttu-id="a8c82-229">已修正在 PowerPoint 共同撰寫和離線編輯的工作階段中可能會導致資料遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-229">Fixed an issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a8c82-230">Office 套件</span><span class="sxs-lookup"><span data-stu-id="a8c82-230">Office Suite</span></span>

- <span data-ttu-id="a8c82-231">已修正使用者在開啟檔案時可能會遇到的當機問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-231">Fixed an issue for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="a8c82-232">已修正 Backstage 的 [資訊位置] 平板未顯示協助工具資訊的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-232">Fixed an issue where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="a8c82-233">已改善透過恢復之前可能已中斷的下載，下載 Office 更新時的可靠性。</span><span class="sxs-lookup"><span data-stu-id="a8c82-233">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="a8c82-234">為了保護 Office 客戶的安全性，我們現在專門使用 SHA-2 演算法來簽署 Microsoft Office 更新。</span><span class="sxs-lookup"><span data-stu-id="a8c82-234">To protect Office customer’s security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-september-10"></a><span data-ttu-id="a8c82-236">版本 1908：9 月 10 日</span><span class="sxs-lookup"><span data-stu-id="a8c82-236">Version 1908: September 10</span></span>
<span data-ttu-id="a8c82-237">*版本 1908 (組建 11929.20300)*</span><span class="sxs-lookup"><span data-stu-id="a8c82-237">*Version 1908 (Build 11929.20300)*</span></span>

<span data-ttu-id="a8c82-238">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="a8c82-238">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="a8c82-240">功能更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-240">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="a8c82-241">Access</span><span class="sxs-lookup"><span data-stu-id="a8c82-241">Access</span></span>

- <span data-ttu-id="a8c82-242">**使用更大的空間來縮放：** 加大 [縮放] 方塊、變更字型、記憶縮放。</span><span class="sxs-lookup"><span data-stu-id="a8c82-242">**Zoom with more room:** Make the Zoom box bigger, change the font, and Zoom remembers it all.</span></span> [<span data-ttu-id="a8c82-243">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-243">Learn more</span></span>](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

- <span data-ttu-id="a8c82-244">**將索引標籤保留在資料庫物件上：** 能清楚看到使用中的索引標籤、輕鬆拖曳索引標籤來重新排列，只要按一下就能關閉資料庫物件。</span><span class="sxs-lookup"><span data-stu-id="a8c82-244">**Keep tabs on your database objects:** Clearly see the active tab, easily drag tabs to rearrange them, and close database objects with just one click.</span></span>

- <span data-ttu-id="a8c82-245">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="a8c82-245">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="a8c82-246">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="a8c82-246">Switching between them has never been easier.</span></span> [<span data-ttu-id="a8c82-247">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-247">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="excel"></a><span data-ttu-id="a8c82-248">Excel</span><span class="sxs-lookup"><span data-stu-id="a8c82-248">Excel</span></span>

- <span data-ttu-id="a8c82-p110">**更深入地探索您的資料：** 新的 [構想] 按鈕可尋找資料的模式，並使用模式建立更有智慧且個人化的建議。[深入了解](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span><span class="sxs-lookup"><span data-stu-id="a8c82-p110">**Discover more about your data:** The new Ideas button looks for patterns in your data, and uses them to create intelligent, personalized suggestions. [Learn more](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span></span>

- <span data-ttu-id="a8c82-251">**快速找到該檔案：** 想要尋找最近使用過的檔案嗎？</span><span class="sxs-lookup"><span data-stu-id="a8c82-251">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="a8c82-252">只要在 [檔案] > [常用] 頁面的 [搜尋] 方塊中輸入，就能找到所需的檔案。</span><span class="sxs-lookup"><span data-stu-id="a8c82-252">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="a8c82-253">**增加您內容的覆蓋面：** 想要讓您的簡報更易於使用嗎？</span><span class="sxs-lookup"><span data-stu-id="a8c82-253">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="a8c82-254">讓協助工具檢查程式來幫助您，您不需要自行處理。</span><span class="sxs-lookup"><span data-stu-id="a8c82-254">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="a8c82-255">按一下 [校閱] > [檢查協助工具] 試試看這個功能 – 我們會在狀態列上告訴您需要留意的部分。</span><span class="sxs-lookup"><span data-stu-id="a8c82-255">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="a8c82-256">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="a8c82-256">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="a8c82-257">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="a8c82-257">Switching between them has never been easier.</span></span> [<span data-ttu-id="a8c82-258">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-258">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="a8c82-259">**觀看工作表生動地呈現：** 插入動畫 3D 圖形，來查看心跳、行星軌道，以及暴龍在工作表內橫衝直撞。</span><span class="sxs-lookup"><span data-stu-id="a8c82-259">**Watch your worksheet come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage through the workbook.</span></span> [<span data-ttu-id="a8c82-260">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-260">Learn more</span></span>](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- <span data-ttu-id="a8c82-261">**共同作業變得更容易：** 共同撰寫的增強功能代表的是使用條件式格式設定、儲存格樣式等等時，您的變更會與共同作業者的變更順暢地合併。</span><span class="sxs-lookup"><span data-stu-id="a8c82-261">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>

- <span data-ttu-id="a8c82-262">**聯結類似欄位上的表格：** 在比較合併表格的欄位時，取得及轉換 (Power Query) 現在具有近似文字比對邏輯 (也稱為模糊比對)。</span><span class="sxs-lookup"><span data-stu-id="a8c82-262">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span> [<span data-ttu-id="a8c82-263">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-263">Learn more</span></span>](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- <span data-ttu-id="a8c82-264">**使用 Power Query 的增強功能快速撰寫程式碼：** 使用自動完成和語法色彩快速完成程式碼。</span><span class="sxs-lookup"><span data-stu-id="a8c82-264">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="a8c82-265">同時輕鬆探索函數、資料行和參數。</span><span class="sxs-lookup"><span data-stu-id="a8c82-265">Easily discover functions, columns, and parameters, too.</span></span>

### <a name="outlook"></a><span data-ttu-id="a8c82-266">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8c82-266">Outlook</span></span>

- <span data-ttu-id="a8c82-267">**在移動郵件時繼續作業：** Outlook 現在會在背景中移動郵件，因此，在資料夾之間移動大量郵件時您可以繼續作業。</span><span class="sxs-lookup"><span data-stu-id="a8c82-267">**Keep working while moving messages:** Outlook now moves messages in the background, so you can keep working while moving lots of messages between folders.</span></span>

- <span data-ttu-id="a8c82-268">**在連續會議之間置入時間：** 將會議預設為提早 5-10 分鐘結束，讓出席者有時間休息，或在前往下一個地點。</span><span class="sxs-lookup"><span data-stu-id="a8c82-268">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to end 5-10 minutes early by default.</span></span>

- <span data-ttu-id="a8c82-p117">**他們會看到您的 meme：** 如果使用文字或靜態影像還不足以清楚表達您的想法，您可以使用動畫 GIF。[深入了解](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span><span class="sxs-lookup"><span data-stu-id="a8c82-p117">**They'll see what you meme:** When text or static images just won't do, use an animated GIF to make your point. [Learn more](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span></span>

- <span data-ttu-id="a8c82-271">**我們已為您更新 Outlook 使用者體驗：** 先前利用「即將推出」提供預覽的簡化體驗，專門設計來幫助您專注於最重要的事物上。</span><span class="sxs-lookup"><span data-stu-id="a8c82-271">**We’ve updated the Outlook user experience for you:** A simplified experience, previously available for preview with Coming Soon, designed to help you focus on what matters most.</span></span> [<span data-ttu-id="a8c82-272">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-272">Learn more</span></span>](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- <span data-ttu-id="a8c82-273">**想要寬鬆或緊密的版面配置？您可自由選擇：** 若您想讓項目之間能有更多空間，可以採用「緊密間距」；或者，您也可以採用緊密的版面配置，以便查看更多項目。</span><span class="sxs-lookup"><span data-stu-id="a8c82-273">**Relaxed or tighter layout? You choose:** Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

- <span data-ttu-id="a8c82-274">**簡化且也能自訂的功能區：** 輕鬆使用簡化、以單一列方式陳列的常用按鈕。</span><span class="sxs-lookup"><span data-stu-id="a8c82-274">**A simplified ribbon that's customizable, too:** Enjoy a streamlined, single row of the most frequently used buttons.</span></span> <span data-ttu-id="a8c82-275">輕鬆在傳統與 [簡化] 檢視之間切換，以及釘選/取消釘選命令。</span><span class="sxs-lookup"><span data-stu-id="a8c82-275">Easily switch between classic and Simplified views, and pin/unpin commands.</span></span> [<span data-ttu-id="a8c82-276">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-276">Learn more</span></span>](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- <span data-ttu-id="a8c82-277">**更快速新增帳戶的方式：** 由於帳戶設定已改善，您現在可以更輕鬆地將使用雙因素驗證的 Outlook.com 和 Gmail 帳戶新增到 Outlook。</span><span class="sxs-lookup"><span data-stu-id="a8c82-277">**A quicker way to add accounts:** Thanks to account setup improvements, it's easier than ever to add Outlook.com and Gmail accounts that use 2-factor authentication to Outlook.</span></span> [<span data-ttu-id="a8c82-278">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-278">Learn more</span></span>](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- <span data-ttu-id="a8c82-279">**挑選您的最愛動作：** 不使用 [標幟] 和 [刪除] 嗎？</span><span class="sxs-lookup"><span data-stu-id="a8c82-279">**Pick your favorite action:** Don't use Flag and Delete?</span></span> <span data-ttu-id="a8c82-280">那麼 [封存] 或 [標示為已讀取] 呢？</span><span class="sxs-lookup"><span data-stu-id="a8c82-280">How about Archive or Mark as Read?</span></span> <span data-ttu-id="a8c82-281">自訂快速動作功能表，加上您最常使用的命令。</span><span class="sxs-lookup"><span data-stu-id="a8c82-281">Customize the quick action menu with the commands you use most.</span></span>

- <span data-ttu-id="a8c82-282">**不再受限於同步處理限制：** Outlook 的增強功能指出資料夾限制已不存在，因此您可以開始將您的共用信箱同步處理。</span><span class="sxs-lookup"><span data-stu-id="a8c82-282">**Say goodbye to sync limits:** Outlook improvements mean the folder limit is gone so go ahead and synchronize your shared mailboxes.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8c82-283">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8c82-283">PowerPoint</span></span>

- <span data-ttu-id="a8c82-p122">**透過測驗或問卷詢問聽眾：** 在投影片上進行測驗或問卷。Office 會收集並儲存存儲您的回應。[深入了解](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span><span class="sxs-lookup"><span data-stu-id="a8c82-p122">**Ask your audience with a quiz or survey:** Put a quiz or survey on a slide. Office collects and stores the responses for you. [Learn more](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span></span>

- <span data-ttu-id="a8c82-287">**快速找到該檔案：** 想要尋找最近使用過的檔案嗎？</span><span class="sxs-lookup"><span data-stu-id="a8c82-287">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="a8c82-288">只要在 [檔案] > [常用] 頁面的 [搜尋] 方塊中輸入，就能找到所需的檔案。</span><span class="sxs-lookup"><span data-stu-id="a8c82-288">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="a8c82-289">**增加您內容的覆蓋面：** 想要讓您的簡報更易於使用嗎？</span><span class="sxs-lookup"><span data-stu-id="a8c82-289">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="a8c82-290">讓協助工具檢查程式來幫助您，您不需要自行處理。</span><span class="sxs-lookup"><span data-stu-id="a8c82-290">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="a8c82-291">按一下 [校閱] > [檢查協助工具] 試試看這個功能 – 我們會在狀態列上告訴您需要留意的部分。</span><span class="sxs-lookup"><span data-stu-id="a8c82-291">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="a8c82-292">**隨時儲存變更：** 將檔案上傳至 OneDrive，確保所有的更新都會自動儲存。</span><span class="sxs-lookup"><span data-stu-id="a8c82-292">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="a8c82-p125">**輕鬆插入內嵌影片：** 想要在您的投影片中放入 Vimeo 或 YouTube 影片嗎？只要有影片頁面連結即可。[深入了解](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span><span class="sxs-lookup"><span data-stu-id="a8c82-p125">**Inserting an online video is easier than ever:** Want to put a video from Vimeo or YouTube on your slide? The video page link is all you need. [Learn more](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span></span>

- <span data-ttu-id="a8c82-296">**較佳變形效果：** 命名您的圖形以便加強掌控其轉化方式。</span><span class="sxs-lookup"><span data-stu-id="a8c82-296">**Better shapeshifting:** Name your shapes for more control over how they morph.</span></span> [<span data-ttu-id="a8c82-297">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-297">Learn more</span></span>](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- <span data-ttu-id="a8c82-298">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="a8c82-298">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="a8c82-299">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="a8c82-299">Switching between them has never been easier.</span></span> [<span data-ttu-id="a8c82-300">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-300">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="a8c82-301">**線上影片有新的首頁：** 將影片儲存至 Microsoft Stream，讓組織中的任何人都看得到。</span><span class="sxs-lookup"><span data-stu-id="a8c82-301">**Online videos have a new home:** Save a video to Microsoft Stream so anyone in your organization can see it.</span></span> <span data-ttu-id="a8c82-302">插入影片連結，享受檔案大小只有原來一小部分的多媒體簡報。</span><span class="sxs-lookup"><span data-stu-id="a8c82-302">Insert the video link and enjoy a multimedia presentation at a fraction of the file size.</span></span> [<span data-ttu-id="a8c82-303">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-303">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

### <a name="project"></a><span data-ttu-id="a8c82-304">Project</span><span class="sxs-lookup"><span data-stu-id="a8c82-304">Project</span></span>

- <span data-ttu-id="a8c82-305">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="a8c82-305">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="a8c82-306">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="a8c82-306">Switching between them has never been easier.</span></span> [<span data-ttu-id="a8c82-307">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-307">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a><span data-ttu-id="a8c82-308">Visio</span><span class="sxs-lookup"><span data-stu-id="a8c82-308">Visio</span></span>

- <span data-ttu-id="a8c82-p130">**告別錯誤的 Excel 連結：** 找不到與 Data Visualizer 圖表連結的 Excel 活頁簿嗎？重新連結，就可繼續使用了。[深入了解](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span><span class="sxs-lookup"><span data-stu-id="a8c82-p130">**Say goodbye to broken Excel links:** Can't find the Excel workbook linked to your Data Visualizer diagram? Relink it, and you're back in business. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span></span>

- <span data-ttu-id="a8c82-312">**內建的 Azure 樣板：** 使用數十種 Azure 樣板來設計雲端應用程式或規劃架構。</span><span class="sxs-lookup"><span data-stu-id="a8c82-312">**Azure stencils built right in:** Design a cloud app or plan an architecture using dozens of Azure stencils.</span></span> [<span data-ttu-id="a8c82-313">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-313">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- <span data-ttu-id="a8c82-314">**資料流程圖上的 Double-Take：** 資料視覺化工具流程圖美觀的新版面配置，既清新、簡潔且更易於了解。</span><span class="sxs-lookup"><span data-stu-id="a8c82-314">**Double-take on data flowcharts:** Gorgeous new layouts for Data Visualizer flowcharts are clean, crisp, and easy to understand.</span></span> <span data-ttu-id="a8c82-315">按一下 [設計] 索引標籤來取得選項。</span><span class="sxs-lookup"><span data-stu-id="a8c82-315">Click the Design tab for options.</span></span>

- <span data-ttu-id="a8c82-316">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="a8c82-316">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="a8c82-317">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="a8c82-317">Switching between them has never been easier.</span></span> [<span data-ttu-id="a8c82-318">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-318">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="a8c82-319">**將進度圖表匯出到 Word：** 在 Word 文件中自動新增圖表內容，如圖案和中繼資料。</span><span class="sxs-lookup"><span data-stu-id="a8c82-319">**Export process diagrams to Word:** Automatically add diagram content, such as shapes and metadata, to a Word document.</span></span> <span data-ttu-id="a8c82-320">然後，自訂文件來建立程序指導方針和操作手冊。</span><span class="sxs-lookup"><span data-stu-id="a8c82-320">Then customize the document to create process guidelines and operation manuals.</span></span> [<span data-ttu-id="a8c82-321">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-321">Learn more</span></span>](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- <span data-ttu-id="a8c82-322">**從 Power BI 匯出 Visio 視覺效果：** 當匯出 Power BI 報表為 PDF 或 PowerPoint 等檔案時，Power BI Visio 視覺效果會正常顯示。</span><span class="sxs-lookup"><span data-stu-id="a8c82-322">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span> [<span data-ttu-id="a8c82-323">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-323">Learn more</span></span>](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a><span data-ttu-id="a8c82-324">Word</span><span class="sxs-lookup"><span data-stu-id="a8c82-324">Word</span></span>

- <span data-ttu-id="a8c82-p136">**編輯當然是使用筆跡編輯：** 使用畫筆透過單一筆劃來分割或加入文字、新增新的一行，或插入文字。[深入了解](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span><span class="sxs-lookup"><span data-stu-id="a8c82-p136">**Editing comes naturally with Ink Editor:** With a single stroke, split or join words, add a new line, or insert words using your pen. [Learn more](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span></span>

- <span data-ttu-id="a8c82-p137">**為靜態文件注入動人的生命力：** 將文件轉變為在任何裝置上，均具有完美外觀的可互動、易分享的網頁。[深入了解](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span><span class="sxs-lookup"><span data-stu-id="a8c82-p137">**Take your doc from static to stunning:** Transform your document into an interactive, easy-to-share web page that looks great on any device. [Learn more](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span></span>

- <span data-ttu-id="a8c82-329">**使用 \@提及功能取得他人注意：** 在註解中使用 @提及功能，讓其他人知道您需要他們提供建議。</span><span class="sxs-lookup"><span data-stu-id="a8c82-329">**Get Their Attention with \@Mentions:** Use @mentions in comments to let others know when you need their input.</span></span> [<span data-ttu-id="a8c82-330">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-330">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="a8c82-p139">**運用行聚焦，提高理解力：** 毫不費力地逐行瀏覽文件。調整焦點，在檢視畫面中一次放入一行、三行或五行。[深入了解](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="a8c82-p139">**Improve comprehension with Line Focus:** Move through a document line by line without distractions. Adjust the focus to put one, three, or five lines in view at a time. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>

- <span data-ttu-id="a8c82-334">**快速找到該檔案：** 想要尋找最近使用過的檔案嗎？</span><span class="sxs-lookup"><span data-stu-id="a8c82-334">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="a8c82-335">只要在 [檔案] > [常用] 頁面的 [搜尋] 方塊中輸入，就能找到所需的檔案。</span><span class="sxs-lookup"><span data-stu-id="a8c82-335">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="a8c82-336">**隨時儲存變更：** 將檔案上傳至 OneDrive，確保所有的更新都會自動儲存。</span><span class="sxs-lookup"><span data-stu-id="a8c82-336">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="a8c82-337">**增加您內容的覆蓋面：** 想要讓您的文件更易於使用嗎？</span><span class="sxs-lookup"><span data-stu-id="a8c82-337">**Increase the reach of your content:** Need to make your documents accessible?</span></span> <span data-ttu-id="a8c82-338">讓協助工具檢查程式來幫助您，您不需要自行處理。</span><span class="sxs-lookup"><span data-stu-id="a8c82-338">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="a8c82-339">按一下 [校閱] > [檢查協助工具] 試試看這個功能 – 我們會在狀態列上告訴您需要留意的部分。</span><span class="sxs-lookup"><span data-stu-id="a8c82-339">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="a8c82-340">**[學習工具] 模式額外支援更多頁面色彩：** Word 中的 [學習工具] 新增更多頁面佈景主題色彩的支援，讓您能夠變更頁面的背景色彩。</span><span class="sxs-lookup"><span data-stu-id="a8c82-340">**Learning Tools mode has additional support for more page colors:** Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span> <span data-ttu-id="a8c82-341">許多人在背景全白或全黑時閱讀會有困難，因此我們在 PC 和 Mac 的 Word 中增加了色彩選項。</span><span class="sxs-lookup"><span data-stu-id="a8c82-341">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

- <span data-ttu-id="a8c82-342">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="a8c82-342">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="a8c82-343">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="a8c82-343">Switching between them has never been easier.</span></span> [<span data-ttu-id="a8c82-344">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-344">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="a8c82-345">**跟分心說再見：** Mac 中最受歡迎的功能來到 Windows。</span><span class="sxs-lookup"><span data-stu-id="a8c82-345">**Say goodbye to distractions:** A favorite Mac feature comes to Windows.</span></span> <span data-ttu-id="a8c82-346">切換到 [檢視] 功能表中的 [焦點] 以移除令人分心的事物，讓您更能專注於工作。</span><span class="sxs-lookup"><span data-stu-id="a8c82-346">Switch to Focus on the View menu to remove distractions and concentrate on your work.</span></span> [<span data-ttu-id="a8c82-347">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-347">Learn more</span></span>](https://support.office.com/article/51af2fb2-194f-424b-ab7e-b65de9ec9292)

### <a name="office-suite"></a><span data-ttu-id="a8c82-348">Office 套件</span><span class="sxs-lookup"><span data-stu-id="a8c82-348">Office Suite</span></span>

- <span data-ttu-id="a8c82-349">**安裝 Microsoft Teams：** 我們已將 Teams 新增至 Office 365 專業增強版的現有安裝。</span><span class="sxs-lookup"><span data-stu-id="a8c82-349">**Installation of Microsoft Teams:** Teams is added to existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="a8c82-350">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-350">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/teams-install)

- <span data-ttu-id="a8c82-351">**隨時儲存變更：** 將檔案上傳至 OneDrive，確保所有的更新都會自動儲存。</span><span class="sxs-lookup"><span data-stu-id="a8c82-351">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="a8c82-352">**隱私權控制：** 用於診斷資料和連線體驗的新增、更新及改良的控制項。</span><span class="sxs-lookup"><span data-stu-id="a8c82-352">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> [<span data-ttu-id="a8c82-353">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-353">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

- <span data-ttu-id="a8c82-354">**Office 圖示有新的外觀：** Office 圖示經過重新設計，以反映簡單、功能強大且智慧型的 Office 體驗。</span><span class="sxs-lookup"><span data-stu-id="a8c82-354">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

- <span data-ttu-id="a8c82-355">**安裝 Microsoft Teams：** 在 Office 365 專業增強版的現有安裝中，預設會安裝 Microsoft Teams。</span><span class="sxs-lookup"><span data-stu-id="a8c82-355">**Installation of Microsoft Teams:** Microsoft Teams is installed by default for existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="a8c82-356">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-356">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/teams-install)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a><span data-ttu-id="a8c82-359">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-359">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="a8c82-360">Excel</span><span class="sxs-lookup"><span data-stu-id="a8c82-360">Excel</span></span>

- <span data-ttu-id="a8c82-361">修正在 Excel 中指派給圖形或表單控制項的巨集可能顯示不正確的錯誤訊息，或者可能會處理不正確目標範圍的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-361">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="a8c82-362">修正在與其他使用者共同撰寫的工作階段中變更樞紐分析表排序的方式，然後重新整理它可能導致失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-362">Fixed an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could cause it to fail.</span></span>

- <span data-ttu-id="a8c82-363">修正插入或刪除儲存格時，瀑布圖和漏斗圖無法與表格同步處理的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-363">Fixed an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="a8c82-364">修正 Excel 中合併衝突的問題，此問題會造成提示使用者重新開啟活頁簿以取得變更。</span><span class="sxs-lookup"><span data-stu-id="a8c82-364">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="a8c82-365">修正會導致表格旁的剪下並貼上作業在與其他人共同撰寫時失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-365">Fixed an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

### <a name="outlook"></a><span data-ttu-id="a8c82-366">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8c82-366">Outlook</span></span>

- <span data-ttu-id="a8c82-367">修正使用者將信箱從基本驗證升級為新式驗證後，造成將錯誤的帳戶與其 Outlook 設定檔相關聯的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-367">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="a8c82-368">修正會導致部分 POP3 使用者看到所有電子郵件皆為純文字格式 (無論設定為何) 的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-368">Fixed an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="a8c82-369">此修正將會還原 HTML 格式郵件的檢視。</span><span class="sxs-lookup"><span data-stu-id="a8c82-369">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="a8c82-370">修正會導致使用者無法透過螢幕助讀程式存取位置建議的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-370">Fixed an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="a8c82-371">修正嘗試擷取使用者的 Outlook 雲端設定時，導致一些使用者遇到驗證錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-371">Fixed an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="a8c82-372">修正會導致經理對於代理人是否已經回覆特定會議邀請含混不清的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-372">Fixed an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="a8c82-373">修正會導致 Outlook 使用者在特定案例中停滯在「需要密碼」狀態的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-373">Fixed an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="a8c82-374">修正會導致目前的資料夾搜尋間歇性失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-374">Fixed an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="a8c82-375">修正以下問題：使用者看到該會議的會議室可用時間之外的會議室建議。</span><span class="sxs-lookup"><span data-stu-id="a8c82-375">Fixed an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="a8c82-376">修正導致使用者看到「找不到此檔案」錯誤的暫時服務問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-376">Fixed temporary service issue that caused users to see the error "Cannot find this file.</span></span> <span data-ttu-id="a8c82-377">使用雲端附件時，請確認路徑和檔案名稱正確。</span><span class="sxs-lookup"><span data-stu-id="a8c82-377">Verify the path and file name are correct" when using cloud attachments.</span></span> [<span data-ttu-id="a8c82-378">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-378">Learn More</span></span>](https://support.office.com/article/outlook-unable-to-attach-onedrive-or-sharepoint-files-to-emails-136951bb-60dc-478a-b916-6ee39e62c37a)

- <span data-ttu-id="a8c82-379">修正會導致使用者看到從 Outlook 上傳至 OneDrive 或 SharePoint 檔案其檔案名稱已變更，其中的數個字元由底線取代的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-379">Fixed an issue that caused users to see uploaded files from Outlook to OneDrive or Sharepoint have the file name changed where several characters replaced by underscores.</span></span>

- <span data-ttu-id="a8c82-380">修正非英文使用者的郵件中，主旨列會相當小的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-380">Fixed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="a8c82-381">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8c82-381">PowerPoint</span></span>

- <span data-ttu-id="a8c82-382">修正某些增益集會在圖表的圖形周圍擲出未預期錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-382">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="a8c82-383">修正還原 PowerPoint 影片控制項的協助工具名稱的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-383">Fixed an issue to restore the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="a8c82-384">修正部分動畫無法開始的問題</span><span class="sxs-lookup"><span data-stu-id="a8c82-384">Fixed an issue which could prevent some animations from starting</span></span>

### <a name="project"></a><span data-ttu-id="a8c82-385">Project</span><span class="sxs-lookup"><span data-stu-id="a8c82-385">Project</span></span>

- <span data-ttu-id="a8c82-386">修正讓 Windows 7 上的使用者能夠從 Project Web App 和 SharePoint 網站開啟專案的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-386">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>


### <a name="visio"></a><span data-ttu-id="a8c82-387">Visio</span><span class="sxs-lookup"><span data-stu-id="a8c82-387">Visio</span></span>

- <span data-ttu-id="a8c82-388">有多個圖形無法從 Visio 匯出至 SVG。</span><span class="sxs-lookup"><span data-stu-id="a8c82-388">Export to SVG from Visio was not working for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="a8c82-389">Word</span><span class="sxs-lookup"><span data-stu-id="a8c82-389">Word</span></span>

- <span data-ttu-id="a8c82-390">修正在 Word 文件上與其他人共同作業時，使用者會遇到錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-390">Fixed an issue where users would get error messages while collaborating with others on a Word document.</span></span>

- <span data-ttu-id="a8c82-391">修正嘗試共用儲存在 SharePoint 2016 上的檔案時，導致使用者遇到「很抱歉，發生問題，無法共用」訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-391">Fixed an issue which caused users to get the message "Sorry, something is preventing us from sharing this"  when trying to share files stored on SharePoint 2016.</span></span>


### <a name="office-suite"></a><span data-ttu-id="a8c82-392">Office 套件</span><span class="sxs-lookup"><span data-stu-id="a8c82-392">Office Suite</span></span>

- <span data-ttu-id="a8c82-393">修正在某些情況下，同步處理引擎備份的 SharePoint 檔案可能會顯示「已儲存」但實際上未儲存任何變更的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-393">Fixed an issue where in some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes.</span></span>

- <span data-ttu-id="a8c82-394">修正大型樹狀檢視失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-394">Fixed an issue where large tree views were failing.</span></span>

- <span data-ttu-id="a8c82-395">修正不正確地將平假名和漢字中的日本新年號 "Reiwa" (令和) 識別為拼字錯誤或不合文法的運算式的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-395">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-august-13"></a><span data-ttu-id="a8c82-397">版本 1902：8 月 13 日</span><span class="sxs-lookup"><span data-stu-id="a8c82-397">Version 1902: August 13</span></span>
<span data-ttu-id="a8c82-398">*版本 1902 (組建 11328.20392)*</span><span class="sxs-lookup"><span data-stu-id="a8c82-398">*Version 1902 (Build 11328.20392)*</span></span>

<span data-ttu-id="a8c82-399">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="a8c82-399">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="a8c82-400">Excel：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-400">Excel: Non-security updates</span></span>
- <span data-ttu-id="a8c82-401">修正清除篩選圖示同時對表格中已篩選和未篩選交叉分析篩選器顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-401">Fixed an issue where the clear filter icon was shown for both filtered and unfiltered Slicers in tables.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="a8c82-402">Outlook：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-402">Outlook: Non-security updates</span></span>
- <span data-ttu-id="a8c82-403">修正使用者將信箱從基本驗證升級為新式驗證後，造成關聯的帳戶錯誤的問題</span><span class="sxs-lookup"><span data-stu-id="a8c82-403">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="a8c82-404">PowerPoint：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-404">PowerPoint: Non-security updates</span></span>
- <span data-ttu-id="a8c82-405">修正與其他使用者就文件共同作業時，應用程式可能會意外終止的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-405">Fixed an issue where the application could unexpectedly terminate while collaborating on a document with other users.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="a8c82-406">Word：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-406">Word: Non-security updates</span></span>
- <span data-ttu-id="a8c82-407">修正 VBA 更新欄位很緩慢的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-407">Fixed an issue which VBA updating fields were slow.</span></span>
- <span data-ttu-id="a8c82-408">修正開啟部分 DOC 檔案時，出現提示說明檔案已損毀的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-408">Fixed in issue when opening some DOC file, it says it is corrupt.</span></span>
- <span data-ttu-id="a8c82-409">修正與其他使用者就文件共同作業時，應用程式可能會意外終止的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-409">Fixed an issue where the application could unexpectedly terminate while collaborating on a document with other users.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="a8c82-410">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-410">Office Suite: Non-security updates</span></span>
- <span data-ttu-id="a8c82-411">修正設定 API 在某些案例下無法在 Office JavaScript 程式庫運作的問題 [深入了解](https://support.microsoft.com/help/4475551/august-6-2019-update-for-office-2016-kb4475551)</span><span class="sxs-lookup"><span data-stu-id="a8c82-411">Fixed an issue in which Setting API doesn't work in the Office JavaScript library in certain scenarios [Learn More](https://support.microsoft.com/help/4475551/august-6-2019-update-for-office-2016-kb4475551)</span></span>

## <a name="version-1902-july-09"></a><span data-ttu-id="a8c82-412">版本 1902：7 月 9 日</span><span class="sxs-lookup"><span data-stu-id="a8c82-412">Version 1902: July 09</span></span>
<span data-ttu-id="a8c82-413">*版本 1902 (組建 11328.20368)*</span><span class="sxs-lookup"><span data-stu-id="a8c82-413">*Version 1902 (Build 11328.20368)*</span></span>

<span data-ttu-id="a8c82-414">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="a8c82-414">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>


### <a name="excel-non-security-updates"></a><span data-ttu-id="a8c82-415">Excel：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-415">Excel: Non-security updates</span></span>
- <span data-ttu-id="a8c82-416">修正刪除篩選過的 Excel 資料列非常緩慢的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-416">Fixed extreme slowness Issue in deleting filtered excel rows.</span></span>
- <span data-ttu-id="a8c82-417">修正以兩根手指捲動會導致灰色矩形繪製超出工作表範圍，並且讓 Excel 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-417">Fixed two finger scrolling causes grey rectangles to be drawn over worksheet and Excel to hang.</span></span>


### <a name="outlook-non-security-updates"></a><span data-ttu-id="a8c82-418">Outlook：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-418">Outlook: Non-security updates</span></span>
- <span data-ttu-id="a8c82-419">解決導致使用者有時會看見 Outlook 插入英文拼音字母，而不是讓輸入法候選視窗保持開啟以選取中文字的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-419">Addresses an issue that caused users to occasionally see Outlook inserting English pinyin letters rather than keeping the IME candidate window open to allow the selection of Chinese words.</span></span>
- <span data-ttu-id="a8c82-420">解決導致使用者看到針對排程的會議建議的會議室卻沒有可預約時間的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-420">Addresses an issue that caused users to see rooms being suggested for meetings that were scheduled outside of that room's availability.</span></span>
- <span data-ttu-id="a8c82-421">解決導致使用者嘗試開啟會議系列的例外狀況卻開啟主要系列的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-421">Addresses an issue that caused users attempting to open an exception to a meeting series to instead open the master series.</span></span>
- <span data-ttu-id="a8c82-422">解決導致使用者在 [刪除的郵件] 資料夾中看到郵件到期日期計算錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-422">Addresses an issue that caused users to see expiry dates being calculated incorrectly for items in Deleted Items folder.</span></span>


### <a name="teams-non-security-updates"></a><span data-ttu-id="a8c82-423">Teams：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-423">Teams: Non-security updates</span></span>

- <span data-ttu-id="a8c82-424">Teams 安裝程式在安裝完成後，現在有 [原則] 可關閉自動啟動。</span><span class="sxs-lookup"><span data-stu-id="a8c82-424">Teams installer has now available Policy to turn off auto-launch after installation is completed.</span></span>


### <a name="visio-non-security-updates"></a><span data-ttu-id="a8c82-425">Visio：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-425">Visio: Non-security updates</span></span>

- <span data-ttu-id="a8c82-426">解決適用於 Visio 的 ActiveX 解決方案無法搭配 Office 365 運作的相關問題，會以一個說明找不到 riched20.dll 的錯誤訊息表示。</span><span class="sxs-lookup"><span data-stu-id="a8c82-426">Addresses issue related to ActiveX solutions for Visio not working with Office 365, expressed as an error message stating that riched20.dll can't be found.</span></span>


### <a name="word--non-security-updates"></a><span data-ttu-id="a8c82-427">Word：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-427">Word:  Non-security updates</span></span>

- <span data-ttu-id="a8c82-428">修正停用範本搜尋列的 GPO 設定</span><span class="sxs-lookup"><span data-stu-id="a8c82-428">Fixed GPO setting to disable template search bar</span></span>
- <span data-ttu-id="a8c82-429">修正使用者在離線後又編輯僅限伺服器才有的文件而可能遺失某些變更的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-429">Fixed an issue where users could lose some of their changes after being offline and editing a document that was server-only.</span></span>
- <span data-ttu-id="a8c82-430">改善啟用 [文件的快速組件] 摘要資訊時的效能</span><span class="sxs-lookup"><span data-stu-id="a8c82-430">Improved performance when enabling Quick Parts for Document properties</span></span>
- <span data-ttu-id="a8c82-431">修正從伺服器第一次下載修訂可能會失敗的問題</span><span class="sxs-lookup"><span data-stu-id="a8c82-431">Fixed an issue where first download revision from the server might fail</span></span>


### <a name="office-suite--non-security-updates"></a><span data-ttu-id="a8c82-432">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-432">Office Suite:  Non-security updates</span></span>

- <span data-ttu-id="a8c82-433">解決安裝其他 Office 產品或語言套件後，使用共用電腦啟用的裝置可能會意外還原為使用者啟用的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-433">Addressed an issue where devices using shared computer activation may unexpectedly revert to user-based activation upon installation of additional Office products or language packs.</span></span>
- <span data-ttu-id="a8c82-434">修正以 SYSTEM 身分執行 proxy 驗證時會封鎖 Office 更新的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-434">Fixed an issue that blocked Office Updates when proxy authentication runs as SYSTEM.</span></span>
- <span data-ttu-id="a8c82-435">修正以解決使用者設定檔變更後，Office 增益集消失的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-435">Fixes to address Office add-ins disappearing on user profile changes.</span></span>


## <a name="version-1902-june-11"></a><span data-ttu-id="a8c82-436">版本 1902：6 月 11 日</span><span class="sxs-lookup"><span data-stu-id="a8c82-436">Version 1902: June 11</span></span>
<span data-ttu-id="a8c82-437">*版本 1902 (組建 11328.20318)*</span><span class="sxs-lookup"><span data-stu-id="a8c82-437">*Version 1902 (Build 11328.20318)*</span></span>
<br/><span data-ttu-id="a8c82-438">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="a8c82-438">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="a8c82-439">Excel：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-439">Excel: Non-security updates</span></span>
 - <span data-ttu-id="a8c82-440">已解決將包含 XML 對應的檔案儲存為 PDF 時導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-440">Resolved an issue that caused a crash when saving a file containing an XML map to PDF.</span></span>
 - <span data-ttu-id="a8c82-441">已解決在載入包含無效工作表名稱之活頁簿時，導致外部連結遭到刪除的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-441">Resolved an issue that caused external links to be removed when workbooks containing invalid sheet names are loaded.</span></span>
 - <span data-ttu-id="a8c82-442">已修正在 Excel 中使用相機工具可能會造成試算表當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-442">Fixed an issue where using the Camera tool in Excel could cause the spreadsheet to hang.</span></span>
 - <span data-ttu-id="a8c82-443">已解決以下問題：當插入或刪除儲存格時，瀑布圖和漏斗圖無法與表格同步處理。</span><span class="sxs-lookup"><span data-stu-id="a8c82-443">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>
 - <span data-ttu-id="a8c82-444">已解決以下問題：在工作表計算期間使用依賴表格之另一個工作表上的陣列公式重新計算資料表格時，發生當機。</span><span class="sxs-lookup"><span data-stu-id="a8c82-444">Resolved a crash when a data table is recalculated during Worksheet Calculate with an array formula on another sheet depending on the table.</span></span> 
 - <span data-ttu-id="a8c82-445">已解決以下問題：未先簽出檔案，無法從 SharePoint 開啟受密碼保護的活頁簿。</span><span class="sxs-lookup"><span data-stu-id="a8c82-445">Resolved an issue that prevented password protected workbooks from being opened from SharePoint without checking out file first.</span></span>
 - <span data-ttu-id="a8c82-446">已進行變更，確保在共用或切換自動儲存時，處理 BeforeSave 事件。</span><span class="sxs-lookup"><span data-stu-id="a8c82-446">A change was made to ensure the BeforeSave event is handled when sharing or toggling AutoSave.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="a8c82-447">Outlook：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-447">Outlook: Non-security updates</span></span>
 - <span data-ttu-id="a8c82-448">已解決在「群組依據」中新增第二個條件後，客戶的工作似乎會消息的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-448">Addressed an issue that caused customers to see their tasks seem to disappear when adding a 2nd condition to "Group by".</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="a8c82-449">Word：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-449">Word: Non-security updates</span></span>
 - <span data-ttu-id="a8c82-450">已修正以下問題：共用目前正在共同作業的文件時，會產生具 .asd 副檔名的附件。</span><span class="sxs-lookup"><span data-stu-id="a8c82-450">Fixed when sharing a document which is currently being collaborated upon the document produces attachment with .asd extension.</span></span>
 - <span data-ttu-id="a8c82-451">已修正註解被歸因於隨機作者的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-451">Fixed an issue with comments get attributed to random authors.</span></span>
 - <span data-ttu-id="a8c82-452">已修正在簽出文件時，簽章遭到移除的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-452">Fixed an issue in the remove signature when checking out a document.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="a8c82-453">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-453">Office Suite: Non-security updates</span></span>
 - <span data-ttu-id="a8c82-454">此修正在「復原」動作後，VBA 的錯誤形狀填入狀態錯誤。</span><span class="sxs-lookup"><span data-stu-id="a8c82-454">This fixed a bug in VBA reporting incorrect shape fill state after an "undo" action.</span></span>


## <a name="version-1902-may-14"></a><span data-ttu-id="a8c82-455">版本 1902：5 月 14 日</span><span class="sxs-lookup"><span data-stu-id="a8c82-455">Version 1902: May 14</span></span>
<span data-ttu-id="a8c82-456">*版本 1902 (組建 11328.20286)*</span><span class="sxs-lookup"><span data-stu-id="a8c82-456">*Version 1902 (Build 11328.20286)*</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="a8c82-457">Excel：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-457">Excel: Non-security updates</span></span>
 -  <span data-ttu-id="a8c82-458">已修正在 Excel 中使用相機工具可能會造成試算表當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-458">Fixed an issue where using the Camera tool in Excel could cause the spreadsheet to hang.</span></span>
 - <span data-ttu-id="a8c82-459">已修正在帶有圖表工作表的非使用中視窗中使用滑鼠滾輪時導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-459">An issue that caused a crash when using the mouse scroll wheel on an in-active window with a chart sheet was fixed.</span></span>
 - <span data-ttu-id="a8c82-460">將試算表匯入 SharePoint 時發生「未預期錯誤」訊息的問題已解決。</span><span class="sxs-lookup"><span data-stu-id="a8c82-460">A problem that caused an "Unexpected Error" message to appear when importing a spreadsheet in SharePoint has been resolved.</span></span>
 - <span data-ttu-id="a8c82-461">在開啟包含使用其規則名稱和自訂檢視的條件式格式設定的活頁簿時導致 Excel 當機的問題已解決。</span><span class="sxs-lookup"><span data-stu-id="a8c82-461">A problem that caused Excel to crash when opening a workbook containing conditional formatting that uses a Name for its rule and a custom view is applied has been resolved.</span></span>
 - <span data-ttu-id="a8c82-462">巨集用於驗證資料的公式若長於 255 個字元可能會產生執行階段錯誤。</span><span class="sxs-lookup"><span data-stu-id="a8c82-462">Macros using data validation with formulas longer than 255 characters may have produced run-time errors.</span></span> <span data-ttu-id="a8c82-463">此問題現已修正。</span><span class="sxs-lookup"><span data-stu-id="a8c82-463">This issue has now been corrected.</span></span>
 - <span data-ttu-id="a8c82-464">發生問題，導致包含連結至其他活頁簿之樞紐分析表的檔案載入速度緩慢。</span><span class="sxs-lookup"><span data-stu-id="a8c82-464">A problem which caused files containing PivotTables linked to other workbooks to load slowly.</span></span> <span data-ttu-id="a8c82-465">此問題已解決。</span><span class="sxs-lookup"><span data-stu-id="a8c82-465">This issue has been resolved.</span></span>
 - <span data-ttu-id="a8c82-466">開啟 HTML 檔案時收到「檔案格式與副檔名不符」錯誤的問題已解決。</span><span class="sxs-lookup"><span data-stu-id="a8c82-466">An issue with opening HTML files and receiving a "file format and extension do not match" error has been resolved.</span></span>
 - <span data-ttu-id="a8c82-467">已進行變更，以解決在非使用中視窗滾動滑鼠滾輪的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-467">A change has been made to resolve issues with mouse-wheel scrolling on inactive windows.</span></span>  

### <a name="outlook-non-security-updates"></a><span data-ttu-id="a8c82-468">Outlook：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-468">Outlook: Non-security updates</span></span>
 - <span data-ttu-id="a8c82-469">解決造成客戶無法編輯所移轉項目上某些欄位的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-469">Addresses an issue that caused customers to be unable to edit some fields on items that had been migrated.</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="a8c82-470">PowerPoint：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-470">PowerPoint: Non-Security updates</span></span>
- <span data-ttu-id="a8c82-471">已修正在罕見的情況下，PowerPoint 停止將使用者的變更上傳到雲端的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-471">Fixed an issue that PowerPoint stops uploading user changes to the cloud in rare situations.</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="a8c82-472">商務用 Skype：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-472">Skype for Business: Non-security updates</span></span>
 - <span data-ttu-id="a8c82-473">已修正 Lync (商務用 Skype) 中的問題，在其中，當任何線上會議具有 7 位以上參與者時，會議視窗可能會消失。</span><span class="sxs-lookup"><span data-stu-id="a8c82-473">Fixed an issue in Lync (Skype for Business) where for any online meeting with more 7+ participants, the meeting window can disappear.</span></span>
 - <span data-ttu-id="a8c82-474">使用用來登入其他 Office 應用程式的認證來登入商務用 Skype。</span><span class="sxs-lookup"><span data-stu-id="a8c82-474">Sign into Skype for Business with credentials used to sign into another Office application.</span></span>
 - <span data-ttu-id="a8c82-475">隨著共用電腦啟用安裝時，正確地啟用商務用 Skype 應用程式。</span><span class="sxs-lookup"><span data-stu-id="a8c82-475">Properly activate the Skype for Business app when installed with shared computer activation.</span></span>

### <a name="visio-non-security-updates"></a><span data-ttu-id="a8c82-476">Visio：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-476">Visio: Non-security updates</span></span>
 - <span data-ttu-id="a8c82-477">已修正第三方解決方案利用停用動態 DPI 功能來擴充 Visio，造成損毀視窗階層問題的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-477">Fixed an issue which was causing broken window hierarchy issues for 3rd party solutions extending Visio by disabling Dynamic DPI feature.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="a8c82-478">Word：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-478">Word: Non-Security updates</span></span>
 - <span data-ttu-id="a8c82-479">已修正編輯 SharePoint 新增的相關人員可能會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-479">Fixed an issue where editing a Related Person added by SharePoint could crash.</span></span>
 - <span data-ttu-id="a8c82-480">已修正 Word 啟動時出現的「無法載入資源」對話方塊。</span><span class="sxs-lookup"><span data-stu-id="a8c82-480">Fixed where the "Failed to load resource" dialog when Word launches.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="a8c82-481">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-481">Office Suite: Non-security updates</span></span>
 - <span data-ttu-id="a8c82-482">此修正程式可修正無法將檔案儲存到 Apache WebDAV 資料夾的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-482">This is a fix for an issue where files cannot be saved to Apache WebDAV folders.</span></span>
 - <span data-ttu-id="a8c82-483">修正 Office 在客戶開啟某些雲端儲存檔案時會意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-483">Fixes an issue where Office closes abruptly when customers open some cloud-stored files.</span></span>
 - <span data-ttu-id="a8c82-484">修正不正確地將平假名和漢字中的日本新年號 "Reiwa" (令和) 識別為拼字錯誤或不合文法的運算式的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-484">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>
 - <span data-ttu-id="a8c82-485">已修正似乎為 Windows 10 上的許多使用者清除最近使用的檔案清單的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-485">Fixed an issue where the recent files list appeared to have been cleared for many users on Windows 10.</span></span>
 - <span data-ttu-id="a8c82-486">已修正即使已有系統管理員觸發的更新進行中，仍導致使用者看到 Office 更新業務列的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-486">Fixed an issue that caused an end-user to see an Office Update business bar, even though there is an Admin-triggered update in progress.</span></span>
 - <span data-ttu-id="a8c82-487">已修正與間歇性的空白登入提示相關的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-487">Fixed an issues related to intermittent blank sign-in prompts.</span></span>
 

## <a name="version-1902-april-9"></a><span data-ttu-id="a8c82-488">版本 1902：4 月 9 日</span><span class="sxs-lookup"><span data-stu-id="a8c82-488">Version 1902: April 9</span></span>
<span data-ttu-id="a8c82-489">*版本 1902 (組建 11328.20230)*</span><span class="sxs-lookup"><span data-stu-id="a8c82-489">*Version 1902 (Build 11328.20230)*</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="a8c82-490">Excel：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-490">Excel: Non-Security updates</span></span>

- <span data-ttu-id="a8c82-491">解決了當儲存格中包含的公式結尾為定義的名稱時，按下 Tab 鍵不會移至下一個儲存格的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-491">Resolved an issue where pressing the Tab key would not move to the next cell when in a cell containing a formula ending in a defined name.</span></span>
- <span data-ttu-id="a8c82-492">解決了儲存格格式設定導致檔案大小不必要地增加的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-492">Resolved an issue where cell formatting was causing the file size to grow unnecessarily.</span></span>
- <span data-ttu-id="a8c82-493">解決了在活頁簿之間剪下並貼上樞紐分析表可能導致貼上資料，但沒有您正與其共同作業的其他人的樞紐分析表的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-493">Resolved an issue where cutting and pasting a PivotTable between workbooks may result in the data being pasted, without a PivotTable for others you are collaborating with.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="a8c82-494">Outlook：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-494">Outlook: Non-Security updates</span></span>

- <span data-ttu-id="a8c82-495">已修正當系統工作列停留在螢幕左側或頂部時，視窗無法顯示在正確位置的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-495">Fixed an issue in which windows would not appear in the correct location when the system task bar was kept at the left or top of the screen.</span></span>
- <span data-ttu-id="a8c82-496">解決了在連絡人卡片上載入圖片時導致客戶遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-496">Addresses an issue that caused customers to experience a crash when loading pictures on the contact card.</span></span>
- <span data-ttu-id="a8c82-497">解決了導致某些客戶在啟動 Office 應用程式時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-497">Addresses an issue that caused some customers to experience crashes when starting office applications.</span></span>
- <span data-ttu-id="a8c82-498">已修正當系統工作列停留在螢幕左側或頂部時，視窗無法顯示在正確位置的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-498">Fixed an issue in which windows would not appear in the correct location when the system task bar was kept at the left or top of the screen.</span></span>
- <span data-ttu-id="a8c82-499">解決造成客戶無法編輯所移轉項目上某些欄位的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-499">Addresses an issue that caused customers to be unable to edit some fields on items that had been migrated.</span></span>

### <a name="visio-non-security-updates"></a><span data-ttu-id="a8c82-500">Visio：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-500">Visio: Non-Security updates</span></span>

- <span data-ttu-id="a8c82-501">已修正第三方解決方案利用停用動態 DPI 功能來擴充 Visio，造成損毀視窗階層問題的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-501">Fixed an issue which was causing broken window hierarchy issues for 3rd party solutions extending Visio by disabling the Dynamic DPI feature.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="a8c82-502">Word：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-502">Word: Non-Security updates</span></span>

- <span data-ttu-id="a8c82-503">如果檔案以唯讀模式開啟，然後您從 [資訊] 窗格中按一下 [另存新檔]，修正問題以便顯示儲存 UI。</span><span class="sxs-lookup"><span data-stu-id="a8c82-503">If a file is opened in read-only mode and you click 'Save As' from the 'Info' pane, fixes issue so that the save UI is displayed.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="a8c82-504">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-504">Office Suite: Non-security updates</span></span>

- <span data-ttu-id="a8c82-505">已修正部分 Office 更新未使用傳遞最佳化對等快取的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-505">Fixed an issue where parts of an Office update do not use Delivery Optimization peer caching.</span></span> [<span data-ttu-id="a8c82-506">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-506">Learn more</span></span>](https://docs.microsoft.com/windows/deployment/update/waas-delivery-optimization)
- <span data-ttu-id="a8c82-507">修正如果使用 Office 部署工具安裝 Office，並發生大小寫不相符時，可能導致移除產品或未啟用的錯誤。</span><span class="sxs-lookup"><span data-stu-id="a8c82-507">Fix to a bug that could lead to products being removed or not activated if Office was installed using the Office Deployment Tool and there was a case mis-match.</span></span>
- <span data-ttu-id="a8c82-508">已修正導致 Windows 10 (版本 1803 或更高版本) 裝置上出現過多登入提示的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-508">Fixed an issue which was causing excessive sign-in prompts on Windows 10 (version 1803 or later) devices.</span></span>
- <span data-ttu-id="a8c82-509">已修正下載連結圖片時，造成懸置的迴歸。</span><span class="sxs-lookup"><span data-stu-id="a8c82-509">Fixed regression that causes hangs when downloading linked pictures.</span></span>
- <span data-ttu-id="a8c82-510">已修正在 Word、Excel、PowerPoint 貼上大型 EMF 檔案的模糊問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-510">Fixed blurriness of large EMF files pasted in Word, Excel, PowerPoint.</span></span>
- <span data-ttu-id="a8c82-511">已修正版本歷程記錄剖析邏輯時，在少數情況下導致文件以唯讀模式開啟的錯誤 (bug)。</span><span class="sxs-lookup"><span data-stu-id="a8c82-511">Fixed the bug in version history parsing logic that in few cases caused the documents to be opened in read-only.</span></span>

## <a name="version-1902-march-12"></a><span data-ttu-id="a8c82-512">版本 1902：3 月 12 日</span><span class="sxs-lookup"><span data-stu-id="a8c82-512">Version 1902: March 12</span></span>
<span data-ttu-id="a8c82-513">*版本 1902 (組建 11328.20158)*</span><span class="sxs-lookup"><span data-stu-id="a8c82-513">*Version 1902 (Build 11328.20158)*</span></span>

### <a name="access-feature-updates"></a><span data-ttu-id="a8c82-514">Access：功能更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-514">Access: Feature updates</span></span>

- <span data-ttu-id="a8c82-515">**重新整理、重新連結或移除連結的資料表** 更新的連結資料表管理員是用於管理所有資料來源與連結資料表的位置。</span><span class="sxs-lookup"><span data-stu-id="a8c82-515">**Refresh, relink, or remove linked tables:** The updated Linked Table Manager is the location for managing all data sources and linked tables.</span></span> [<span data-ttu-id="a8c82-516">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-516">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)
- <span data-ttu-id="a8c82-p154">**繪製成黑色、繪製成灰色：** 依照您的喜好變更 Access 的外觀。有四個佈景主題可供選擇：彩色、深灰色、黑色或白色。[深入了解](https://support.office.com/article/9d76a8b4-bfff-48a9-b8c8-8e133461bc94)</span><span class="sxs-lookup"><span data-stu-id="a8c82-p154">**Paint it black, paint it gray:** Change the look of Access as often as you like. Four themes to choose from: Colorful, Dark Gray, Black, or White. [Learn more](https://support.office.com/article/9d76a8b4-bfff-48a9-b8c8-8e133461bc94)</span></span>
- <span data-ttu-id="a8c82-520">**Office 擁有新的外觀：** Office應用程式現在擁有更簡單、更方便使用的現代化圖示，而功能區也更新了視覺效果，能強調顯示 Office 應用程式中的豐富共同作業功能。</span><span class="sxs-lookup"><span data-stu-id="a8c82-520">**Office has a new look:**  Office apps now have modern icons that are simpler and more accessible, and the ribbon has updated visuals that highlight the rich collaboration features available in Office apps.</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="a8c82-521">Excel：功能更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-521">Excel: Feature updates</span></span>

- <span data-ttu-id="a8c82-522">**更快速地開始**：新設計的 [開始頁面] 會將您最近開啟的文件放在最前面並置中。</span><span class="sxs-lookup"><span data-stu-id="a8c82-522">**Get a faster start** The newly designed Start Page puts your recently opened documents front and center.</span></span> <span data-ttu-id="a8c82-523">按幾下便能取得檔案，並從這裡直接開啟 [帳戶] 設定或 [選項]。</span><span class="sxs-lookup"><span data-stu-id="a8c82-523">Get to files in fewer clicks, and open Account settings or Options right from here.</span></span>
- <span data-ttu-id="a8c82-524">**使用註解共同作業：** 使用內建的回覆方塊試保持試算表中的交談正確。</span><span class="sxs-lookup"><span data-stu-id="a8c82-524">**Collaborate with comments:** Keep the conversation going right in your spreadsheet with the built-in reply box.</span></span> [<span data-ttu-id="a8c82-525">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-525">Learn more</span></span>](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)
- <span data-ttu-id="a8c82-526">**功能區圖示有了嶄新的外觀：** 別擔心，功能一切如常。</span><span class="sxs-lookup"><span data-stu-id="a8c82-526">**Your ribbon icons have a new look:** Don’t worry, everything works the same.</span></span> <span data-ttu-id="a8c82-527">此外，它們在各種尺寸的螢幕上看起來很棒。</span><span class="sxs-lookup"><span data-stu-id="a8c82-527">Plus, they look great on screens of all sizes.</span></span> [<span data-ttu-id="a8c82-528">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-528">Learn more</span></span>](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- <span data-ttu-id="a8c82-p158">**能在套用篩選時插入 SVG：** Office 使用者現在可以在套用篩選的同時，插入 SVG。[深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="a8c82-p158">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>
- <span data-ttu-id="a8c82-p159">**顯示圖片後面的內容：** 將圖片放在工作表中、挑選您的預設，並觀看透明度變更。就這麼簡單！[深入了解](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span><span class="sxs-lookup"><span data-stu-id="a8c82-p159">**Reveal what's behind a picture:** Put a picture in a worksheet, pick your preset, and watch the transparency change. That's it! [Learn more](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span></span>
- <span data-ttu-id="a8c82-534">**呼叫所有「取得與轉換」粉絲：** 如果您經常使用「取得與轉換」，您會很高興知道我們已改善資料行來源範例功能。</span><span class="sxs-lookup"><span data-stu-id="a8c82-534">**Calling all Get & Transform fans:** If you use Get & Transform a lot, you'll be happy to know that the Column From Example feature has been improved.</span></span> <span data-ttu-id="a8c82-535">此外，也已改善許多連接器。</span><span class="sxs-lookup"><span data-stu-id="a8c82-535">And, many connectors have been improved as well.</span></span> [<span data-ttu-id="a8c82-536">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-536">Learn more</span></span>](https://support.office.com/article/ed01ec34-679d-48e7-ba49-bb14c7908f9e)
- <span data-ttu-id="a8c82-537">**改善了對高解析度顯示器的支援**：現在，如果您使用多部監視器或筆記型電腦基座，Office 應用程式在每個顯示器上都會順暢清晰地呈現，即使顯示器使用不同的縮放設定亦然。</span><span class="sxs-lookup"><span data-stu-id="a8c82-537">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings.</span></span> [<span data-ttu-id="a8c82-538">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-538">Learn more</span></span>](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- <span data-ttu-id="a8c82-539">**快速查閱** 我們已加速 VLOOKUP、HLOOKUP 和 MATCH 的計算速度，讓您能更快得到答案。</span><span class="sxs-lookup"><span data-stu-id="a8c82-539">**Speedy Lookup** We've turbo-charged your VLOOKUP, HLOOKUP, and MATCH calculations so you can get answers faster.</span></span> [<span data-ttu-id="a8c82-540">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-540">Learn more</span></span>](https://support.office.com/article/60f18521-2589-4734-89dd-ba4ee1f6c000)

### <a name="outlook-feature-updates"></a><span data-ttu-id="a8c82-541">Outlook：功能更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-541">Outlook: Feature updates</span></span>

- <span data-ttu-id="a8c82-p163">**使用「大聲朗讀」聆聽您的電子郵件：** Outlook 可以大聲朗讀您的電子郵件，強調所朗讀的文字。若要開啟 [大聲朗讀]，請移至 [輕鬆存取] 設定。[深入了解](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)</span><span class="sxs-lookup"><span data-stu-id="a8c82-p163">**Use Read Aloud to listen to your email:** Outlook can read your email aloud, highlighting text as it's read. To turn on Read Aloud, go to the Ease of Access settings. [Learn more](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)</span></span>
- <span data-ttu-id="a8c82-545">**免用手輸入：** 您有麥克風嗎？</span><span class="sxs-lookup"><span data-stu-id="a8c82-545">**Type hands-free:** Got a microphone?</span></span> <span data-ttu-id="a8c82-546">按一下 [聽寫] 並看看 Outlook 如何在您說話的同時輸入您說話的內容。</span><span class="sxs-lookup"><span data-stu-id="a8c82-546">Click Dictate and watch Outlook type while you talk.</span></span> [<span data-ttu-id="a8c82-547">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-547">Learn more</span></span>](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- <span data-ttu-id="a8c82-548">**功能區圖示有了嶄新的外觀：** 別擔心，功能一切如常。</span><span class="sxs-lookup"><span data-stu-id="a8c82-548">**Your ribbon icons have a new look:** Don’t worry, everything works the same.</span></span> <span data-ttu-id="a8c82-549">此外，它們在各種尺寸的螢幕上看起來很棒。</span><span class="sxs-lookup"><span data-stu-id="a8c82-549">Plus, they look great on screens of all sizes.</span></span> [<span data-ttu-id="a8c82-550">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-550">Learn more</span></span>](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- <span data-ttu-id="a8c82-551">**在經 SMIME 加密和簽署的電子郵件中，預設封鎖外部內容的下載：** 由於 SMIME 通訊協定中存在漏洞，Outlook 將封鎖在已通過 SMIME 加密或簽署的郵件上下載外部內容。</span><span class="sxs-lookup"><span data-stu-id="a8c82-551">**Block download of external content by default in SMIME encrypted and signed emails:** Due to a vulnerability in the SMIME protocol - Outlook will block download of external content on messages that have been encrypted or signed over SMIME.</span></span> <span data-ttu-id="a8c82-552">使用者無法透過 Outlook UI 的按下動作下載外部內容，藉此防止安全性漏洞。</span><span class="sxs-lookup"><span data-stu-id="a8c82-552">Users will not be able to single-click download external content through Outlook UI to protect from the security vulnerability.</span></span> <span data-ttu-id="a8c82-553">[選項] 對話方塊中有一個新選項，可讓使用者回復為舊行為。</span><span class="sxs-lookup"><span data-stu-id="a8c82-553">There is a new option in the Options dialog to allow for users to revert to old behavior.</span></span>
- <span data-ttu-id="a8c82-554">**關閉會議轉寄功能：** 防止出席者將您的會議轉寄給其他人。</span><span class="sxs-lookup"><span data-stu-id="a8c82-554">**Turn off forwarding for a meeting:** Prevent attendees from forwarding your meeting to others.</span></span> <span data-ttu-id="a8c82-555">只需移至功能區，按一下 [回應選項] 即可。</span><span class="sxs-lookup"><span data-stu-id="a8c82-555">Just go to the ribbon and click Response Options.</span></span> [<span data-ttu-id="a8c82-556">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-556">Learn more</span></span>](https://support.office.com/article/5C9877BC-AB91-4A7C-99FB-B0B68D7EA94F)
- <span data-ttu-id="a8c82-p168">**排程助理員中的人員建議：** 在您排定會議時查看對要新增之出席者的建議。不再來回切換排程助理員與收件者。[深入了解](https://support.office.com/article/d284c6d9-206e-4926-92b4-5addc0fcbefb)</span><span class="sxs-lookup"><span data-stu-id="a8c82-p168">**People suggestions in the Scheduling Assistant:** See recommendations for attendees to add when you schedule a meeting. No more switching back and forth between the Scheduling Assistant and the To line. [Learn more](https://support.office.com/article/d284c6d9-206e-4926-92b4-5addc0fcbefb)</span></span>
- <span data-ttu-id="a8c82-560">**預留房間更加輕鬆：** 使用多個會議室清單尋找會議室 - 以及切換清單，而不會失去您已選取的會議室。</span><span class="sxs-lookup"><span data-stu-id="a8c82-560">**Reserving a room just got easier:** Look for a conference room using more than one room list - and switch lists without losing rooms you've selected.</span></span>
- <span data-ttu-id="a8c82-p169">**循環範圍的新預設值：** 在 [週期設定] 對話方塊中，循環範圍之前的預設值為 [沒有結束日期]。雖然這有助於建立長時間執行的週期性系列，但在一段時間之後可能會發生損壞。我們正將 [週期設定] 對話方塊的預設值更新為 [結束於]，這樣我們的預設值就會符合行事曆操作的建議最佳做法。</span><span class="sxs-lookup"><span data-stu-id="a8c82-p169">**New default for range of recurrence:** For the Recurrence dialog, the range of recurrence used to default for "No end date". This facilitated the creation of long-running recurring series, which can become corrupted over time. We are updating the default for the Recurrence dialog to "End by", such that our default value matches recommended best practices for calendaring.</span></span>
- <span data-ttu-id="a8c82-p170">**從 Outlook 提醒對話方塊加入小組會議：** 當 Outlook 提醒使用者有即將來臨的會議時，如果即將來臨的會議是小組線上會議，則它會顯示 [線上加入] 按鈕。這個動作與從 Outlook [提醒] 對話方塊加入商務用 Skype 會議的體驗類似。</span><span class="sxs-lookup"><span data-stu-id="a8c82-p170">**Join Teams meetings from the Outlook Reminders dialog:** When Outlook reminds users of an upcoming meeting, it will show a Join Online button if the upcoming meeting is a Teams online meeting. This is similar to the experience of joining a Skype for Business meeting from the Outlook Reminders dialog.</span></span>
- <span data-ttu-id="a8c82-566">**停止看到過去事件的提醒：** 您可以設定行事曆，以在事件結束之後自動關閉事件的提醒。</span><span class="sxs-lookup"><span data-stu-id="a8c82-566">**Stop seeing reminders for past events:** You can set your calendar to automatically dismiss reminders for events after they've ended.</span></span> [<span data-ttu-id="a8c82-567">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-567">Learn more</span></span>](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)
- <span data-ttu-id="a8c82-568">**查看安全連結背後的 URL：** 安全連結可保護您防範在電子郵件中收到但隱藏原始 URL 的惡意 URL。</span><span class="sxs-lookup"><span data-stu-id="a8c82-568">**See the URL behind Safe Links:** Safe Links protects you from malicious URLS received in email but they hide the original URL.</span></span> <span data-ttu-id="a8c82-569">若要查看原始 URL，請將滑鼠游標移到 URL 上。</span><span class="sxs-lookup"><span data-stu-id="a8c82-569">To see the original, hover your mouse over the URL.</span></span> <span data-ttu-id="a8c82-570">需要進階威脅防護授權。</span><span class="sxs-lookup"><span data-stu-id="a8c82-570">Requires an Advanced Threat Protection license.</span></span> [<span data-ttu-id="a8c82-571">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-571">Learn more</span></span>](https://products.office.com/exchange/advance-threat-protection)
- <span data-ttu-id="a8c82-572">**縮放與搖桿：** 選擇要用於所有郵件的預設值，而不用在每次讀取郵件時調整 [縮放]。</span><span class="sxs-lookup"><span data-stu-id="a8c82-572">**Zoom and stick:** Instead of adjusting Zoom each time you read a message, choose a default to use for all your messages.</span></span> [<span data-ttu-id="a8c82-573">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-573">Learn more</span></span>](https://support.office.com/article/56c090bc-e148-44a7-bd06-1290edd38983)
- <span data-ttu-id="a8c82-574">**郵件加密：僅加密 IRM 原則：**[選項] > [權限] 功能表上的全新僅加密選項，供 Office 365 郵件加密使用者使用。</span><span class="sxs-lookup"><span data-stu-id="a8c82-574">**Message Encryption: encrypt-only IRM policy:** New encrypt-only option appears in the Options > Permissions menu for Office 365 Message Encryption users.</span></span> <span data-ttu-id="a8c82-575">這個選項可讓您加密郵件，並將郵件傳送給組織內外的任何人。</span><span class="sxs-lookup"><span data-stu-id="a8c82-575">This option allows you to encrypt a message and send it to anyone, inside or outside your organization.</span></span>
- <span data-ttu-id="a8c82-576">**當您被列於密件副本時，顯示提醒：** 當您不小心回覆所有人，而將自己列於密件副本時，密件副本資訊提示會顯示提醒。</span><span class="sxs-lookup"><span data-stu-id="a8c82-576">**Warning when you've been BCC'ed:** The BCC infotip will warn you before you accidentally reply all to a mail that you've been blind carbon copied on.</span></span>
- <span data-ttu-id="a8c82-577">**更智慧的 [收件者:] 行：** 當您按一下 [收件者:] 行來撰寫郵件時，我們會建議您可能要選擇的收件者。</span><span class="sxs-lookup"><span data-stu-id="a8c82-577">**A smarter To: line:** When you click the To: line to address a message, we suggest recipients you're likely to choose.</span></span> <span data-ttu-id="a8c82-578">此外，還可以看到收件者的相片，讓您知道要傳送的對象是正確的。</span><span class="sxs-lookup"><span data-stu-id="a8c82-578">Plus, you can see their picture, so you know yo’re sending to the right person.</span></span> [<span data-ttu-id="a8c82-579">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-579">Learn more</span></span>](https://support.office.com/article/147208AF-CA8E-4CDF-B71F-77BA81A54069)
- <span data-ttu-id="a8c82-p176">**能在套用篩選時插入 SVG：** Office 使用者現在可以在套用篩選的同時，插入 SVG。[深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="a8c82-p176">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>
- <span data-ttu-id="a8c82-582">**改善了對高解析度顯示器的支援**：現在，如果您使用多部監視器或筆記型電腦基座，Office 應用程式在每個顯示器上都會順暢清晰地呈現，即使顯示器使用不同的縮放設定亦然。</span><span class="sxs-lookup"><span data-stu-id="a8c82-582">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings.</span></span> [<span data-ttu-id="a8c82-583">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-583">Learn more</span></span>](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="a8c82-584">PowerPoint：功能更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-584">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="a8c82-585">**更快速地開始**：新設計的 [開始頁面] 會將您最近開啟的文件放在最前面並置中。</span><span class="sxs-lookup"><span data-stu-id="a8c82-585">**Get a faster start** The newly designed Start Page puts your recently opened documents front and center.</span></span> <span data-ttu-id="a8c82-586">按幾下便能取得檔案，並從這裡直接開啟 [帳戶] 設定或 [選項]。</span><span class="sxs-lookup"><span data-stu-id="a8c82-586">Get to files in fewer clicks, and open Account settings or Options right from here.</span></span>
- <span data-ttu-id="a8c82-587">**免用手輸入：** 您有麥克風嗎？</span><span class="sxs-lookup"><span data-stu-id="a8c82-587">**Type hands-free:** Got a microphone?</span></span> <span data-ttu-id="a8c82-588">按一下 [聽寫] 並看看 PowerPoint 如何在您說話的同時輸入您說話的內容。</span><span class="sxs-lookup"><span data-stu-id="a8c82-588">Click Dictate and watch PowerPoint type while you talk.</span></span> [<span data-ttu-id="a8c82-589">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-589">Learn more</span></span>](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- <span data-ttu-id="a8c82-590">**功能區圖示有了嶄新的外觀：** 別擔心，功能一切如常。</span><span class="sxs-lookup"><span data-stu-id="a8c82-590">**Your ribbon icons have a new look:** Don’t worry, everything works the same.</span></span> <span data-ttu-id="a8c82-591">此外，它們在各種尺寸的螢幕上看起來很棒。</span><span class="sxs-lookup"><span data-stu-id="a8c82-591">Plus, they look great on screens of all sizes.</span></span> [<span data-ttu-id="a8c82-592">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-592">Learn more</span></span>](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- <span data-ttu-id="a8c82-593">**改善了對高解析度顯示器的支援**：現在，如果您使用多部監視器或筆記型電腦基座，Office 應用程式在每個顯示器上都會順暢清晰地呈現，即使顯示器使用不同的縮放設定亦然。</span><span class="sxs-lookup"><span data-stu-id="a8c82-593">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings.</span></span> [<span data-ttu-id="a8c82-594">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-594">Learn more</span></span>](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- <span data-ttu-id="a8c82-595">**色彩生動的超連結：** 超連結不再只是藍色的。</span><span class="sxs-lookup"><span data-stu-id="a8c82-595">**Hyperlinks in living color:** Hyperlinks aren't just blue anymore.</span></span> <span data-ttu-id="a8c82-596">您可以套用您喜歡的任何字型色彩。</span><span class="sxs-lookup"><span data-stu-id="a8c82-596">Apply any font color you like.</span></span> [<span data-ttu-id="a8c82-597">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-597">Learn more</span></span>](https://support.office.com/article/988ed94c-82e9-4e2c-96a1-7ffd2c382ce8)
- <span data-ttu-id="a8c82-598">**生動地觀看您的投影片：** 插入動畫 3D 圖形，來查看心跳、行星軌道，以及暴龍在整個畫面橫衝直撞。</span><span class="sxs-lookup"><span data-stu-id="a8c82-598">**Watch your slides come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage across the screen.</span></span> [<span data-ttu-id="a8c82-599">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-599">Learn more</span></span>](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)
- <span data-ttu-id="a8c82-p184">**您素描，我修飾：** 我們可將手繪文字和形狀變為更精緻的圖表。只需選取您的筆跡線條即可開始。[深入了解](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="a8c82-p184">**You sketch, we polish:** We change hand-drawn text and shapes into refined diagrams. Just select your ink strokes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>
- <span data-ttu-id="a8c82-p185">**顯示圖片後面的內容：** 將圖片放在工作表中、挑選您的預設，並觀看透明度變更。就這麼簡單！[深入了解](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span><span class="sxs-lookup"><span data-stu-id="a8c82-p185">**Reveal what's behind a picture:** Put a picture in a worksheet, pick your preset, and watch the transparency change. That's it! [Learn more](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span></span>
- <span data-ttu-id="a8c82-606">**運用筆跡製作精彩的投影片：** 將筆跡轉換成標準圖形和文字，然後從 PowerPoint 設計工具吸取智慧的投影片設計概念。</span><span class="sxs-lookup"><span data-stu-id="a8c82-606">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="a8c82-607">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-607">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)
- <span data-ttu-id="a8c82-608">**發佈到 Microsoft Stream：** 透過使用 Microsoft Stream，在組織內更安全地以影片形式共用簡報。</span><span class="sxs-lookup"><span data-stu-id="a8c82-608">**Publish to Microsoft Stream:** Share a presentation as a video more securely within your organization by using Microsoft Stream.</span></span> [<span data-ttu-id="a8c82-609">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-609">Learn more</span></span>](https://support.office.com/article/c140551f-cb37-4818-b5d4-3e30815c3e83)
- <span data-ttu-id="a8c82-610">**匯出為 4K 影片：** 您現在可以在將簡報匯出為影片時選取 4K 解析度。</span><span class="sxs-lookup"><span data-stu-id="a8c82-610">**Export to 4K video:** When you export a presentation to video, 4K resolution is now an option.</span></span>  [<span data-ttu-id="a8c82-611">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-611">Learn more</span></span>](https://support.office.com/article/c140551f-cb37-4818-b5d4-3e30815c3e83)
- <span data-ttu-id="a8c82-p189">**能在套用篩選時插入 SVG：** Office 使用者現在可以在套用篩選的同時，插入 SVG。[深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="a8c82-p189">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>
- <span data-ttu-id="a8c82-614">**大型檔案現在會以更快速度開啟：** 現在開啟儲存在 OneDrive 或 SharePoint 上的檔案時，會在背景下載影像、影片及其他大型元素。</span><span class="sxs-lookup"><span data-stu-id="a8c82-614">**Large files now open faster:** Images, videos, and other large elements now download in the background when opening files stored on OneDrive or SharePoint.</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="a8c82-615">Word：功能更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-615">Word: Feature updates</span></span>

- <span data-ttu-id="a8c82-616">**更快速地開始**：新設計的 [開始頁面] 會將您最近開啟的文件放在最前面並置中。</span><span class="sxs-lookup"><span data-stu-id="a8c82-616">**Get a faster start** The newly designed Start Page puts your recently opened documents front and center.</span></span> <span data-ttu-id="a8c82-617">按幾下便能取得檔案，並從這裡直接開啟 [帳戶] 設定或 [選項]。</span><span class="sxs-lookup"><span data-stu-id="a8c82-617">Get to files in fewer clicks, and open Account settings or Options right from here.</span></span>
- <span data-ttu-id="a8c82-618">**免用手輸入：** 您有麥克風嗎？</span><span class="sxs-lookup"><span data-stu-id="a8c82-618">**Type hands-free:** Got a microphone?</span></span> <span data-ttu-id="a8c82-619">按一下 [聽寫] 並看看 Word 如何在您說話的同時輸入您說話的內容。</span><span class="sxs-lookup"><span data-stu-id="a8c82-619">Click Dictate and watch Word type while you talk.</span></span> [<span data-ttu-id="a8c82-620">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-620">Learn more</span></span>](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- <span data-ttu-id="a8c82-p192">**生動地觀看您的文件：** 插入動畫 3D 圖形，來查看心跳、行星軌道，以及暴龍在整個頁面橫衝直撞。[深入了解](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)</span><span class="sxs-lookup"><span data-stu-id="a8c82-p192">**Watch your documents come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage across the page. [Learn more](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)</span></span>
- <span data-ttu-id="a8c82-623">**功能區圖示有了嶄新的外觀：** 別擔心，功能一切如常。</span><span class="sxs-lookup"><span data-stu-id="a8c82-623">**Your ribbon icons have a new look:** Don’t worry, everything works the same.</span></span> <span data-ttu-id="a8c82-624">此外，它們在各種尺寸的螢幕上看起來很棒。</span><span class="sxs-lookup"><span data-stu-id="a8c82-624">Plus, they look great on screens of all sizes.</span></span> [<span data-ttu-id="a8c82-625">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-625">Learn more</span></span>](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- <span data-ttu-id="a8c82-p194">**顯示圖片後面的內容：** 將圖片放在工作表中、挑選您的預設，並觀看透明度變更。就這麼簡單！[深入了解](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span><span class="sxs-lookup"><span data-stu-id="a8c82-p194">**Reveal what's behind a picture:** Put a picture in a worksheet, pick your preset, and watch the transparency change. That's it! [Learn more](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span></span>
- <span data-ttu-id="a8c82-p195">**能在套用篩選時插入 SVG：** Office 使用者現在可以在套用篩選的同時，插入 SVG。[深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="a8c82-p195">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>
- <span data-ttu-id="a8c82-631">**改善了對高解析度顯示器的支援**：現在，如果您使用多部監視器或筆記型電腦基座，Office 應用程式在每個顯示器上都會順暢清晰地呈現，即使顯示器使用不同的縮放設定亦然。</span><span class="sxs-lookup"><span data-stu-id="a8c82-631">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings.</span></span> [<span data-ttu-id="a8c82-632">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-632">Learn more</span></span>](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- <span data-ttu-id="a8c82-p197">**利用 LinkedIn 的協助撰寫最佳簡歷或履歷表：** 利用簡歷小幫手，查看特定角色的工作經驗、建議的技能以及其他資訊。 [深入了解](https://support.office.com/article/444ff6f0-ef74-4a9c-9091-ffd7a9d1917a)</span><span class="sxs-lookup"><span data-stu-id="a8c82-p197">**Write your best resume or CV with help from LinkedIn:** With Resume Assistant, see work experiences, suggested skills, and more for a given role. [Learn more](https://support.office.com/article/444ff6f0-ef74-4a9c-9091-ffd7a9d1917a)</span></span>

### <a name="project-feature-updates"></a><span data-ttu-id="a8c82-635">Project：功能更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-635">Project: Feature updates</span></span>

- <span data-ttu-id="a8c82-636">**在工作面板卡片上查看詳細資訊：** 當標題本身無法陳述完整故事時，請自訂您的工作面板卡片，以顯示所有最重要的詳細資料。</span><span class="sxs-lookup"><span data-stu-id="a8c82-636">**See more info on Task Board cards:** When the title alone doesn’t tell the story, customize your Task Board cards to show all the most important details.</span></span> [<span data-ttu-id="a8c82-637">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-637">Learn more</span></span>](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)
- <span data-ttu-id="a8c82-638">**Office 擁有新的外觀：** Office應用程式現在擁有更簡單、更方便使用的現代化圖示，而功能區也更新了視覺效果，能強調顯示 Office 應用程式中的豐富共同作業功能。</span><span class="sxs-lookup"><span data-stu-id="a8c82-638">**Office has a new look:**  Office apps now have modern icons that are simpler and more accessible, and the ribbon has updated visuals that highlight the rich collaboration features available in Office apps.</span></span>

### <a name="publisher-feature-updates"></a><span data-ttu-id="a8c82-639">Publisher：功能更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-639">Publisher: Feature updates</span></span>

- <span data-ttu-id="a8c82-640">**Office 擁有新的外觀：** Office應用程式現在擁有更簡單、更方便使用的現代化圖示，而功能區也更新了視覺效果，能強調顯示 Office 應用程式中的豐富共同作業功能。</span><span class="sxs-lookup"><span data-stu-id="a8c82-640">**Office has a new look:**  Office apps now have modern icons that are simpler and more accessible, and the ribbon has updated visuals that highlight the rich collaboration features available in Office apps.</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="a8c82-641">Visio：功能更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-641">Visio: Feature updates</span></span>

- <span data-ttu-id="a8c82-642">**在下一個圖表中享受圖示時刻：** 有 26 個全新的圖示樣板供您挑選，其中包含分析、藝術、慶典、臉部、運動和其他圖示。</span><span class="sxs-lookup"><span data-stu-id="a8c82-642">**Enjoy an iconic moment in your next diagram:** Pick from 26 new stencils with icons for analytics, arts, celebration, faces, sports, and more.</span></span>
- <span data-ttu-id="a8c82-643">**Office 擁有新的外觀：** Office應用程式現在擁有更簡單、更方便使用的現代化圖示，而功能區也更新了視覺效果，能強調顯示 Office 應用程式中的豐富共同作業功能。</span><span class="sxs-lookup"><span data-stu-id="a8c82-643">**Office has a new look:**  Office apps now have modern icons that are simpler and more accessible, and the ribbon has updated visuals that highlight the rich collaboration features available in Office apps.</span></span>

### <a name="office-suite-feature-updates"></a><span data-ttu-id="a8c82-644">Office 套件：功能更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-644">Office Suite: Feature updates</span></span>

- <span data-ttu-id="a8c82-p199">**Office 第三方應用程式現在已使用 office.js api 擁有插入 SVG 支援的功能：** 亦稱為 Office 增益集的第三方應用程式現在擁有插入 SVG 的功能。使用者現在可以將個人的 SVG 集合連線至 Office。開發人員現在可以使用 Office.js API 來使用這項功能。</span><span class="sxs-lookup"><span data-stu-id="a8c82-p199">**Office 3rd Party Applications now have insert SVG support using the office.js api:** 3rd party applications also known as add-ins in Office now have the ability to insert SVG's. Users can now connect their personal collection of SVG's to Office. Developers can use this feature by using the Office.js API.</span></span>
- <span data-ttu-id="a8c82-648">**安裝 Microsoft Teams：** 在 Office 365 專業增強版的現有安裝中，預設會安裝 Microsoft Teams。</span><span class="sxs-lookup"><span data-stu-id="a8c82-648">**Installation of Microsoft Teams:**  Microsoft Teams is installed by default for existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="a8c82-649">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-649">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/teams-install)

### <a name="skype-for-business-feature-updates"></a><span data-ttu-id="a8c82-650">商務用 Skype：功能更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-650">Skype for Business: Feature updates</span></span>

- <span data-ttu-id="a8c82-651">**改善了對高解析度顯示器的支援**：現在，如果您使用多部監視器或筆記型電腦基座，Office 應用程式在每個顯示器上都會順暢清晰地呈現，即使顯示器使用不同的縮放設定亦然。</span><span class="sxs-lookup"><span data-stu-id="a8c82-651">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings.</span></span> [<span data-ttu-id="a8c82-652">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-652">Learn more</span></span>](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="teams-feature-updates"></a><span data-ttu-id="a8c82-653">Teams：功能更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-653">Teams: Feature updates</span></span>

- <span data-ttu-id="a8c82-654">**改善了對高解析度顯示器的支援**：現在，如果您使用多部監視器或筆記型電腦基座，Office 應用程式在每個顯示器上都會順暢清晰地呈現，即使顯示器使用不同的縮放設定亦然。</span><span class="sxs-lookup"><span data-stu-id="a8c82-654">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings.</span></span> [<span data-ttu-id="a8c82-655">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8c82-655">Learn more</span></span>](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

## <a name="version-1808-february-12"></a><span data-ttu-id="a8c82-656">版本 1808：2 月 12 日</span><span class="sxs-lookup"><span data-stu-id="a8c82-656">Version 1808: February 12</span></span>
<span data-ttu-id="a8c82-657">*版本 1808 (組建 10730.20280)*</span><span class="sxs-lookup"><span data-stu-id="a8c82-657">*Version 1808 (Build 10730.20280)*</span></span> 

### <a name="access-non-security-updates"></a><span data-ttu-id="a8c82-658">Access：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-658">Access: Non-Security updates</span></span> 

- <span data-ttu-id="a8c82-659">這個更新將新日本時代的支援新增至 Access。</span><span class="sxs-lookup"><span data-stu-id="a8c82-659">This update adds support for new Japanese eras to Access.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="a8c82-660">Outlook：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-660">Outlook: Non-Security updates</span></span> 

- <span data-ttu-id="a8c82-661">解決嘗試管理規則時，因參照不再存在資料夾的規則而導致使用者看見錯誤訊息或看見用戶端規則無法執行的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-661">Addresses an issue that caused users with rules that refer to a folder that no longer exist to see an error when trying to manage rules and to see client-side rules fail to run.</span></span>
- <span data-ttu-id="a8c82-662">解決因快取的委派信箱導致使用者在無法預測的時間間隔遇到頻繁的當機問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-662">Addresses an issue that caused users with cached delegate mailboxes to encounter frequent hangs at unpredictable intervals.</span></span>
- <span data-ttu-id="a8c82-663">解決因為會議結束時間設定為隔天午夜而導致全天會議在某些檢視中比原訂多橫跨一天的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-663">Addresses an issue that caused All Day Meetings to appear to span one more day than intended in some views due to the end time of the meeting being set to midnight of the following day.</span></span>
- <span data-ttu-id="a8c82-664">修正參考日本時代建立新約會或會議時發生的當機問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-664">Fixed a hang when creating new appointments or meetings that reference Japanese eras.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="a8c82-665">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-665">Office Suite: Non-security updates</span></span>

- <span data-ttu-id="a8c82-666">修正使用 [O365 Office 集中式部署](https://docs.microsoft.com/office/dev/add-ins/publish/centralized-deployment)部署的增益集發生凍結且無法使用的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-666">Fixed issue where Add-ins, deployed using [O365 Office centralized deployment](https://docs.microsoft.com/office/dev/add-ins/publish/centralized-deployment), were freezing and unusable.</span></span>


## <a name="version-1808-january-8"></a><span data-ttu-id="a8c82-667">版本 1808：1 月 8 日</span><span class="sxs-lookup"><span data-stu-id="a8c82-667">Version 1808: January 8</span></span>
<span data-ttu-id="a8c82-668">版本 1808 (組建 10730.20264)\*\*</span><span class="sxs-lookup"><span data-stu-id="a8c82-668">*Version 1808 (Build 10730.20264)*</span></span> 

### <a name="outlook-non-security-updates"></a><span data-ttu-id="a8c82-669">Outlook：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-669">Outlook: Non-security updates</span></span> 

- <span data-ttu-id="a8c82-670">修正導致使用者遇到行事曆同步處理錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="a8c82-670">Fixed an issue that caused users to experience calendar synchronization errors.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="a8c82-671">Word：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="a8c82-671">Word: Non-security updates</span></span>

- <span data-ttu-id="a8c82-672">改善開啟效能。</span><span class="sxs-lookup"><span data-stu-id="a8c82-672">Improve open performance.</span></span>


> [!NOTE]
> <span data-ttu-id="a8c82-673">如果您需要關於使用 Office 的問題協助，建議您將問題張貼在 [Microsoft Answers 論壇](https://answers.microsoft.com/)或[技術社群](https://techcommunity.microsoft.com/)，或連絡[支援](https://support.microsoft.com/contactus)。</span><span class="sxs-lookup"><span data-stu-id="a8c82-673">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>
