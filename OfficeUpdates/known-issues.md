---
title: Office 365 專業增強版的已知問題
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: RelNotes_ProPlus
description: 提供 Office 365 專業增強版已知問題的相關資訊
ms.openlocfilehash: 721c9a600b079b3214fa798a39a8ed728c89de93
ms.sourcegitcommit: 7c1759a0e733ade767da00175afc1c43e8d07e3a
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 11/15/2019
ms.locfileid: "38640822"
---
# <a name="office-365-proplus-known-issues"></a><span data-ttu-id="eb97b-103">Office 365 專業增強版的已知問題</span><span class="sxs-lookup"><span data-stu-id="eb97b-103">Office 365 ProPlus Known Issues</span></span>

<span data-ttu-id="eb97b-104">這些已知問題可提供 2019 年 Office 365 專業增強版、Visio Pro for Office 365、Project Online 電腦版用戶端以及 Office 365 商務版的每月通道更新、SACT 與 SAC 更新所含的非安全性更新的相關資訊。</span><span class="sxs-lookup"><span data-stu-id="eb97b-104">These known issues provide information about non-security updates that are included in Monthly Channel, SACT and SAC updates to Office 365 ProPlus in 2019, Visio Pro for Office 365, Project Online Desktop Client and Office 365 Business.</span></span>

<span data-ttu-id="eb97b-105">下表提供目前進行中的問題和已解決的問題摘要。</span><span class="sxs-lookup"><span data-stu-id="eb97b-105">This table offers a summary of current active issues and those issues that have been resolved.</span></span>  <span data-ttu-id="eb97b-106">我們會以正在調查的重大問題來更新下表。</span><span class="sxs-lookup"><span data-stu-id="eb97b-106">We will update the table below with significant issues we are investigating.</span></span>

> [!NOTE]
>- <span data-ttu-id="eb97b-107">這個清單並不全面。</span><span class="sxs-lookup"><span data-stu-id="eb97b-107">This list is not comprehensive.</span></span>
>- <span data-ttu-id="eb97b-108">如果您在顯示為已解決的通道以外的通道中遇到問題，您可以預期問題很快會解決。</span><span class="sxs-lookup"><span data-stu-id="eb97b-108">If you are experiencing an issue in a channel other than the channel shown as resolved, you can expect resolution soon.</span></span> [<span data-ttu-id="eb97b-109">深入了解</span><span class="sxs-lookup"><span data-stu-id="eb97b-109">Learn more</span></span>](https://docs.microsoft.com/zh-TW/DeployOffice/overview-of-update-channels-for-office-365-proplus#BKMK_SAC)
>- <span data-ttu-id="eb97b-110">解決的問題也會記載在其相關的通道頁面上。</span><span class="sxs-lookup"><span data-stu-id="eb97b-110">Resolved issues are documented in their respective channel pages as well.</span></span>

<br>

### <a name="last-updated-november-12-2019"></a><span data-ttu-id="eb97b-111">上次更新：2019 年 11 月 12 日</span><span class="sxs-lookup"><span data-stu-id="eb97b-111">Last Updated November 12, 2019</span></span>

### <a name="excel"></a><span data-ttu-id="eb97b-112">Excel</span><span class="sxs-lookup"><span data-stu-id="eb97b-112">Excel</span></span>

- <span data-ttu-id="eb97b-113">使用自動調整來調整列高時，核取方塊控制項可能收縮。</span><span class="sxs-lookup"><span data-stu-id="eb97b-113">Resolved an issue where check box controls could shrink when using autofit to adjust row height</span></span><br><br><span data-ttu-id="eb97b-114">**調查中**：每月、SACT</span><span class="sxs-lookup"><span data-stu-id="eb97b-114">**Investigating**: Monthly, SACT</span></span>

- <span data-ttu-id="eb97b-115">非同步使用者定義函數造成的效能問題，導致它們同步執行。</span><span class="sxs-lookup"><span data-stu-id="eb97b-115">We resolved an performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span><br><br><span data-ttu-id="eb97b-116">**已解決**：SACT 版本 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="eb97b-116">**Resolved**: SACT Version 1908 (11929.20436)</span></span> 

- <span data-ttu-id="eb97b-117">可能已防止使用者以 Office 365 Excel 活頁簿格式儲存</span><span class="sxs-lookup"><span data-stu-id="eb97b-117">Users could be prevented from saving in Office 365 Excel Workbook format.</span></span><br><br><span data-ttu-id="eb97b-118">**已解決**：SACT 版本 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="eb97b-118">**Resolved**: SACT Version 1908 (11929.20436)</span></span>


- <span data-ttu-id="eb97b-119">當檔案具備大量設定格式化的條件時，按一下 [字型色彩] 按鈕時會出現的效能問題。</span><span class="sxs-lookup"><span data-stu-id="eb97b-119">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span><br><br><span data-ttu-id="eb97b-120">**已解決**：SACT 版本 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="eb97b-120">**Resolved**: SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="eb97b-121">已大幅改善刪除有合併儲存格之欄的效能。</span><span class="sxs-lookup"><span data-stu-id="eb97b-121">Significant improvements to the performance of deleting columns with merged cells</span></span><br><br><span data-ttu-id="eb97b-122">**調查中**：SACT</span><span class="sxs-lookup"><span data-stu-id="eb97b-122">**Investigating**: SACT</span></span><br><span data-ttu-id="eb97b-123">**已解決**：每月版本 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="eb97b-123">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="eb97b-124">當您將報表篩選隨著其餘的樞紐分析表一起轉換，以用於 SQL 表格式伺服器的查詢時，會遇到結果不正確。</span><span class="sxs-lookup"><span data-stu-id="eb97b-124">Resolved an Issue where you may get incorrect results when converting report filters along with the rest of the PivotTable for queries to SQL tabular servers.</span></span><br><br><span data-ttu-id="eb97b-125">**調查中**：每月</span><span class="sxs-lookup"><span data-stu-id="eb97b-125">**Investigating**: Monthly</span></span>

- <span data-ttu-id="eb97b-126">修正以校正使用圖表範本插入圖表時，預覽中使用的色彩</span><span class="sxs-lookup"><span data-stu-id="eb97b-126">Fix to correct colors used in previews when inserting charts using chart templates</span></span><br><br><span data-ttu-id="eb97b-127">**已解決**：每月版本 1910 (12130.20272)、SACT 版本 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="eb97b-127">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436)</span></span>


- <span data-ttu-id="eb97b-128">發現從 OneDrive 以物件形式插入檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="eb97b-128">Identified an issue in inserting files as object from OneDrive.</span></span><br><br> <span data-ttu-id="eb97b-129">**已解決**：每月版本 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="eb97b-129">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="eb97b-130">發現在目前的 Office 版本中開啟在舊版 Office 中建立的活頁簿時，可能導致 Excel 懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="eb97b-130">Identified an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span><br><br>
<span data-ttu-id="eb97b-131">**已解決**：每月版本 1910 (12130.20272)、SACT 版本 1908 (11929.20436)、SAC 版本 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="eb97b-131">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436), SAC Version 1902 (11328.20468)</span></span>

- <span data-ttu-id="eb97b-132">發現在刪除某個範圍之後，可能會導致輸入的值延遲顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="eb97b-132">Identified an issue that was causing delays in displaying typed values after deleting a range.</span></span><br><br>
<span data-ttu-id="eb97b-133">**已解決**：SAC 版本 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="eb97b-133">**Resolved**: SAC Version 1902 (11328.20468)</span></span>

- <span data-ttu-id="eb97b-134">發現捲動後選取儲存格時，可能導致選取錯誤的儲存格的問題。</span><span class="sxs-lookup"><span data-stu-id="eb97b-134">Identified an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span><br><br>
<span data-ttu-id="eb97b-135">**調查中**：SACT</span><span class="sxs-lookup"><span data-stu-id="eb97b-135">**Investigating**: SACT</span></span> <br><span data-ttu-id="eb97b-136">**已解決**：每月版本 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="eb97b-136">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="eb97b-137">發現當變更系列集合時，可能會導致散佈折線圖無法正確呈現的問題。</span><span class="sxs-lookup"><span data-stu-id="eb97b-137">Identified an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span><br><br>
<span data-ttu-id="eb97b-138">**已解決**：每月版本 1910 (12130.20272)、SACT 版本 1908 (11929.20300)</span><span class="sxs-lookup"><span data-stu-id="eb97b-138">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20300)</span></span>

### <a name="outlook"></a><span data-ttu-id="eb97b-139">Outlook</span><span class="sxs-lookup"><span data-stu-id="eb97b-139">Outlook</span></span>

- <span data-ttu-id="eb97b-140">發現導致某些使用者在新增次要 Exchange 帳戶時看到建立了重複的特殊資料夾的問題。</span><span class="sxs-lookup"><span data-stu-id="eb97b-140">Identified an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span><br><br>
<span data-ttu-id="eb97b-141">**已解決**：每月版本 1910 (12130.20272)、SACT 版本 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="eb97b-141">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="eb97b-142">發現可能導致造成記憶體流失的問題。</span><span class="sxs-lookup"><span data-stu-id="eb97b-142">Identified an issue which could have resulted in a memory leak.</span></span> <br><br>
<span data-ttu-id="eb97b-143">**已解決**：每月版本 1910 (12130.20272)、SACT 版本 1908 (11929.20388)、SAC 版本 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="eb97b-143">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20388), SAC Version 1902 (11328.20468)</span></span>

- <span data-ttu-id="eb97b-144">解決導致某些使用者在新增次要 Exchange 帳戶時看到建立了重複的特殊資料夾的問題。</span><span class="sxs-lookup"><span data-stu-id="eb97b-144">Addresses an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span><br><br>
<span data-ttu-id="eb97b-145">**已解決**：每月版本 1910 (12130.20272)、SACT 版本 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="eb97b-145">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="eb97b-146">發現當使用者收到 Skype「未接的交談」訊息時，有時可能會導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="eb97b-146">Identified an issue which could sometimes result in a crash when a user receives a 'Missed Conversation' message from Skype.</span></span><br><br>
<span data-ttu-id="eb97b-147">**已解決**：每月版本 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="eb97b-147">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="eb97b-148">發現在已啟用 DisableBGSave 的電腦上開啟附件時，導致使用者收到一般「作業失敗」錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="eb97b-148">Identified an issue that caused Users to receive a generic ""operation failed"" error when opening an attachment on a machine where DisableBGSave is enabled.</span></span><br><br>
<span data-ttu-id="eb97b-149">**已解決**：每月版本 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="eb97b-149">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="eb97b-150">發現 cid: 影像 (Outlook 電子郵件影像) 連結無法中斷的問題。</span><span class="sxs-lookup"><span data-stu-id="eb97b-150">Identified an issue with the links of cid: images (Outlook email-based images) were not able to be broken.</span></span><br><br>
<span data-ttu-id="eb97b-151">**已解決**：SACT 版本 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="eb97b-151">**Resolved**: SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="eb97b-152">發現當嘗試傳送 s/MIME 加密電子郵件時，可能會導致不正確錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="eb97b-152">Identified an issue which could have caused an incorrect error message when attempting to send s/MIME encrypted e-mail.</span></span><br><br><span data-ttu-id="eb97b-153">**已解決**：每月版本 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="eb97b-153">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="eb97b-154">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="eb97b-154">PowerPoint</span></span>

- <span data-ttu-id="eb97b-155">在垂直文字方塊中，部分片假名字元可能無法正確顯示。</span><span class="sxs-lookup"><span data-stu-id="eb97b-155">Some katakana characters may display incorrectly in a vertical text box.</span></span><br><br>
<span data-ttu-id="eb97b-156">**調查中**：每月</span><span class="sxs-lookup"><span data-stu-id="eb97b-156">**Investigating**: Monthly</span></span>

- <span data-ttu-id="eb97b-157">發現在貼上具有超連結的文字時，無法建立超連結的問題。</span><span class="sxs-lookup"><span data-stu-id="eb97b-157">Identified an issue which prevented hyperlink from being created when pasting text with hyperlink.</span></span> <br><br><span data-ttu-id="eb97b-158">**已解決**：每月版本 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="eb97b-158">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="eb97b-159">發現將文字貼到投影片母片和投影片版面配置的頁首/頁尾/投影片編號預留位置之後，可能導致 TextRanges 中斷的問題。</span><span class="sxs-lookup"><span data-stu-id="eb97b-159">Identified an issue which could cause TextRanges to become broken after pasting text into the header/footer/slide number placeholders on slide master and slide layout.</span></span> <br><br><span data-ttu-id="eb97b-160">**已解決**：每月版本 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="eb97b-160">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="eb97b-161">發現 Win7 上的效能問題，其中，於所有應用程式中從功能區插入圖案庫時，大約需要 4 秒鐘的時間才會顯示。</span><span class="sxs-lookup"><span data-stu-id="eb97b-161">Identified a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span><br>
<br><span data-ttu-id="eb97b-162">**已解決**：每月版本 1910 (12130.20272)、SACT 版本 1908 (11929.20396)、SAC 版本 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="eb97b-162">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20396), SAC Version 1902 (11328.20468)</span></span>

### <a name="project"></a><span data-ttu-id="eb97b-163">Project</span><span class="sxs-lookup"><span data-stu-id="eb97b-163">Project</span></span>

- <span data-ttu-id="eb97b-164">當您有作業中有零個工作的指派時，可能無法將作業標示為完成且永遠會顯示為 99%。</span><span class="sxs-lookup"><span data-stu-id="eb97b-164">Fixed an issue where if you have an assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span><br><br>
<span data-ttu-id="eb97b-165">**調查中**：每月</span><span class="sxs-lookup"><span data-stu-id="eb97b-165">**Investigating**: Monthly</span></span><br>
<span data-ttu-id="eb97b-166">**已解決**：SACT 版本 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="eb97b-166">**Resolved**: SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="eb97b-167">資源撫平無法解決資源過度分派問題</span><span class="sxs-lookup"><span data-stu-id="eb97b-167">Overallocations are not resolved by leveling</span></span><br><br>
<span data-ttu-id="eb97b-168">**調查中**：每月</span><span class="sxs-lookup"><span data-stu-id="eb97b-168">**Investigating**: Monthly</span></span>

- <span data-ttu-id="eb97b-169">發現在開啟唯讀專案時，使用者可能會收到數個訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="eb97b-169">Identified an issue where users could get several messages when opening a read-only project.</span></span><br><br>
<span data-ttu-id="eb97b-170">**已解決**：每月版本 1910 (12130.20344)、SACT 版本 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="eb97b-170">**Resolved**: Monthly Version 1910 (12130.20344), SACT Version 1908 (11929.20436)</span></span>

### <a name="word"></a><span data-ttu-id="eb97b-171">Word</span><span class="sxs-lookup"><span data-stu-id="eb97b-171">Word</span></span>

- <span data-ttu-id="eb97b-172">從瀏覽窗格搜尋可能會失敗</span><span class="sxs-lookup"><span data-stu-id="eb97b-172">Searching from the Navigation pane may fail.</span></span><br><br>
<span data-ttu-id="eb97b-173">**調查中**：每月</span><span class="sxs-lookup"><span data-stu-id="eb97b-173">**Investigating**: Monthly</span></span>

- <span data-ttu-id="eb97b-174">發現從 OneDrive 以物件形式插入檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="eb97b-174">Identified an issue in inserting files as object from OneDrive.</span></span><br><br> <span data-ttu-id="eb97b-175">**已解決**：每月版本 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="eb97b-175">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

### <a name="office-suite"></a><span data-ttu-id="eb97b-176">Office 套件</span><span class="sxs-lookup"><span data-stu-id="eb97b-176">Office Suite</span></span>
- <span data-ttu-id="eb97b-177">嘗試將檔案儲存到已中斷連線的網路共用時可能會導致問題
**調查中**：每月</span><span class="sxs-lookup"><span data-stu-id="eb97b-177">Attempting to save a file to a disconnected network share may result in a filure.</span></span>



<br>
<br>

> [!NOTE]
> <span data-ttu-id="eb97b-178">如果您需要關於使用 Office 的問題協助，建議您將問題張貼在 [Microsoft Answers 論壇](https://answers.microsoft.com/)或[技術社群](https://techcommunity.microsoft.com/)，或連絡[支援](https://support.microsoft.com/contactus)。</span><span class="sxs-lookup"><span data-stu-id="eb97b-178">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>
