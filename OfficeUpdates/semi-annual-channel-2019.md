---
title: 2019 年半年通道版本的版本資訊
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為 IT 專業人員提供 2019 年 Office 365 專業增強版半年通道版本的版本資訊
ms.openlocfilehash: c79cdc9a9c11f12acfaeab511cd27f234ceda0eb
ms.sourcegitcommit: 4027fcf35a0e3da959e83179d798c0981c4a0000
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 11/14/2019
ms.locfileid: "38402439"
---
# <a name="release-notes-for-semi-annual-channel-releases-in-2019"></a><span data-ttu-id="94c5b-103">2019 年半年通道版本的版本資訊</span><span class="sxs-lookup"><span data-stu-id="94c5b-103">Release notes for Semi-Annual Channel releases in 2019</span></span>

<span data-ttu-id="94c5b-104">這些版本資訊可提供 2019 年 Office 365 專業增強版、Visio Pro for Office 365、Project Online 電腦版用戶端以及 Office 365 商務版的半年通道更新所含新功能和非安全性更新的相關資訊。</span><span class="sxs-lookup"><span data-stu-id="94c5b-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Channel updates to Office 365 ProPlus in 2019, Visio Pro for Office 365, Project Online Desktop Client and Office 365 Business.</span></span>

> [!NOTE]
> - <span data-ttu-id="94c5b-105">我們通常會在一段時間內推出功能 (有時甚至推出修正程式) 至半年通道。</span><span class="sxs-lookup"><span data-stu-id="94c5b-105">We often roll out features (and sometimes even fixes) to Semi-Annual Channel over a period of time.</span></span> <span data-ttu-id="94c5b-106">如果您現在沒有看到如下所述的項目，您可以預期它近期會推出。</span><span class="sxs-lookup"><span data-stu-id="94c5b-106">If you don’t see something described below right away, you can expect it soon.</span></span> [<span data-ttu-id="94c5b-107">深入了解</span><span class="sxs-lookup"><span data-stu-id="94c5b-107">Learn more</span></span>](https://support.office.com/en-us/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516?ui=en-US&rs=en-US&ad=US)
> - <span data-ttu-id="94c5b-108">當使用者在半年通道上，從 Office 入口網站下載並安裝 Office 365 到 Windows 10 上時，OneNote 2016 依預設不會包括在其中。</span><span class="sxs-lookup"><span data-stu-id="94c5b-108">OneNote 2016 will not be included by default when a user on the Semi-Annual Channel downloads and installs Office 365 on Windows 10 from the Office Portal.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-november-12"></a><span data-ttu-id="94c5b-110">版本 1902：11 月 12 日</span><span class="sxs-lookup"><span data-stu-id="94c5b-110">Version 1902: November 12</span></span>
<span data-ttu-id="94c5b-111">*版本 1902 (組建 11328.20468)*</span><span class="sxs-lookup"><span data-stu-id="94c5b-111">*Version 1902 (Build 11328.20468)*</span></span>

<span data-ttu-id="94c5b-112">安全性更新列於[此處](https://docs.microsoft.com/zh-TW/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="94c5b-112">Security updates listed [here](https://docs.microsoft.com/zh-TW/officeupdates/office365-proplus-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="94c5b-114">解決的問題</span><span class="sxs-lookup"><span data-stu-id="94c5b-114">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="94c5b-115">Excel</span><span class="sxs-lookup"><span data-stu-id="94c5b-115">Excel</span></span>

- <span data-ttu-id="94c5b-116">解決在刪除某個範圍之後，可能會導致輸入的值延遲顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-116">Resolved an issue that was causing delays in displaying typed values after deleting a range.</span></span>
- <span data-ttu-id="94c5b-117">解決在目前的 Office 版本中開啟在舊版 Office 中建立的活頁簿時，可能導致 Excel 懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-117">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

### <a name="outlook"></a><span data-ttu-id="94c5b-118">Outlook</span><span class="sxs-lookup"><span data-stu-id="94c5b-118">Outlook</span></span>

- <span data-ttu-id="94c5b-119">解決啟用快顯通知時，導致使用者注意到記憶體流失的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-119">Addressed an issue that caused users to observe memory leaks when toast notifications were enabled.</span></span>
- <span data-ttu-id="94c5b-120">解決會導致客戶注意到 Outlook 中的記憶體流失的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-120">Addressed and issue that caused customers to notice a memory leak in Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="94c5b-121">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="94c5b-121">PowerPoint</span></span>

- <span data-ttu-id="94c5b-122">可靠性修正：修正第三方增益集可能會造成 PowerPoint 失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-122">Reliability fix: Fixed an issue where third party add-in might cause PowerPoint to fail.</span></span>

### <a name="office-suite"></a><span data-ttu-id="94c5b-123">Office 套件</span><span class="sxs-lookup"><span data-stu-id="94c5b-123">Office Suite</span></span>

- <span data-ttu-id="94c5b-124">修正 Win7 上的效能問題，其中，於所有應用程式中從功能區插入圖案庫時，大約需要 4 秒鐘的時間才會顯示。</span><span class="sxs-lookup"><span data-stu-id="94c5b-124">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>
- <span data-ttu-id="94c5b-125">修正 [開始功能表] 快速鍵和 Office 副檔名會在更新之後意外消失的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-125">Fixed an issue where Start Menu shortcuts and Office file extensions would unexpectedly disappear following an update.</span></span>
- <span data-ttu-id="94c5b-126">為了保護 Office 客戶的安全性，我們現在專門使用 SHA-2 演算法來簽署 Microsoft Office 更新。</span><span class="sxs-lookup"><span data-stu-id="94c5b-126">To protect Office customers’ security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1808-november-12"></a><span data-ttu-id="94c5b-128">版本 1808：11 月 12 日</span><span class="sxs-lookup"><span data-stu-id="94c5b-128">Version 1808: November 12</span></span>
<span data-ttu-id="94c5b-129">*版本 1808 (組建 10730.20416)*</span><span class="sxs-lookup"><span data-stu-id="94c5b-129">*Version 1808 (Build 10730.20416)*</span></span>

<span data-ttu-id="94c5b-130">安全性更新列於[此處](https://docs.microsoft.com/zh-TW/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="94c5b-130">Security updates listed [here](https://docs.microsoft.com/zh-TW/officeupdates/office365-proplus-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="94c5b-132">解決的問題</span><span class="sxs-lookup"><span data-stu-id="94c5b-132">Resolved issues</span></span>

### <a name="outlook"></a><span data-ttu-id="94c5b-133">Outlook</span><span class="sxs-lookup"><span data-stu-id="94c5b-133">Outlook</span></span>

- <span data-ttu-id="94c5b-134">解決會導致將 [要離線保留的郵件] 設定為 [全部] 以外的使用者，在將同步處理視窗外部的項目從本機存放區移至 Exchange Online 信箱時，會看到資料遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-134">Addresses an issue that caused users with a "mail to keep offline setting" of anything other than "All" to see data loss when moving items outside of the sync window from a local store to Exchange Online mailbox.</span></span>

### <a name="office-suite"></a><span data-ttu-id="94c5b-135">Office 套件</span><span class="sxs-lookup"><span data-stu-id="94c5b-135">Office Suite</span></span>

- <span data-ttu-id="94c5b-136">為了保護 Office 客戶的安全性，我們現在專門使用 SHA-2 演算法來簽署 Microsoft Office 更新。</span><span class="sxs-lookup"><span data-stu-id="94c5b-136">To protect Office customers’ security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-october-08"></a><span data-ttu-id="94c5b-138">版本 1902：10 月 8 日</span><span class="sxs-lookup"><span data-stu-id="94c5b-138">Version 1902: October 08</span></span>
<span data-ttu-id="94c5b-139">*版本 1902 (組建 11328.20438)*</span><span class="sxs-lookup"><span data-stu-id="94c5b-139">*Version 1902 (Build 11328.20438)*</span></span>

<span data-ttu-id="94c5b-140">安全性更新列於[此處](https://docs.microsoft.com/zh-TW/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="94c5b-140">Security updates listed [here](https://docs.microsoft.com/zh-TW/officeupdates/office365-proplus-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a><span data-ttu-id="94c5b-142">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-142">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="94c5b-143">Excel</span><span class="sxs-lookup"><span data-stu-id="94c5b-143">Excel</span></span>

- <span data-ttu-id="94c5b-144">已解決會導致將超連結貼到一些受保護工作表中的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-144">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

### <a name="project"></a><span data-ttu-id="94c5b-145">Project</span><span class="sxs-lookup"><span data-stu-id="94c5b-145">Project</span></span>

- <span data-ttu-id="94c5b-146">已修正無法在下列情況中建立 XPS 檔案的 PDF 的問題：</span><span class="sxs-lookup"><span data-stu-id="94c5b-146">Fixed an issue when the PDF of XPS file is not created in the following scenario:</span></span></div><ul><li><span data-ttu-id="94c5b-147">開啟專案。</span><span class="sxs-lookup"><span data-stu-id="94c5b-147">You open a project.</span></span></li><li><span data-ttu-id="94c5b-148">按一下 [檔案] 功能表、按一下 [匯出]、然後按一下 [建立 PDF/XPS] <b></b>按鈕。</span><span class="sxs-lookup"><span data-stu-id="94c5b-148">You click the File menu, click Export and click the<b> Create PDF/XPS</b> button.</span></span></li><li><span data-ttu-id="94c5b-149">在 [瀏覽] 對話方塊中、輸入檔案名稱、然後按一下 [確定]。</span><span class="sxs-lookup"><span data-stu-id="94c5b-149">Within the Browse dialog box, you enter a file name and click OK.</span></span></li></ul>

### <a name="word"></a><span data-ttu-id="94c5b-150">Word</span><span class="sxs-lookup"><span data-stu-id="94c5b-150">Word</span></span>

- <span data-ttu-id="94c5b-151">已修正 Windows 目前組建的 JAWS 在使用 Caps + 向右鍵時無法讀出字詞的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-151">Fixed an issue where JAWS on Windows current builds won't announce words when using Caps + Right arrow.</span></span>

### <a name="office-suite"></a><span data-ttu-id="94c5b-152">Office 套件</span><span class="sxs-lookup"><span data-stu-id="94c5b-152">Office Suite</span></span>

- <span data-ttu-id="94c5b-153">使用者現在可以儲存由 OneDrive 同步處理用戶端同步處理的 Office 檔案，但缺少必要的屬性。</span><span class="sxs-lookup"><span data-stu-id="94c5b-153">Users will now be able to save Office files synced by the OneDrive sync client with missing required properties.</span></span> <span data-ttu-id="94c5b-154">透過移至 [檔案 > 資訊]，可繼續在文件 Backstage 中查看和編輯文件內容。</span><span class="sxs-lookup"><span data-stu-id="94c5b-154">The document properties will continue to be available for viewing and editing through the document backstage by going to File>Info.</span></span> <span data-ttu-id="94c5b-155">這項變更導致效能提升。</span><span class="sxs-lookup"><span data-stu-id="94c5b-155">This change will lead to performance improvements.</span></span>

- <span data-ttu-id="94c5b-156">已修正 [修正我的帳戶]&quot;&quot; 通知未在登入成功之後消失的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-156">Fixed an issue where &quot;Fix my account&quot; notification does not disappear after signing-in successfully.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1808-october-08"></a><span data-ttu-id="94c5b-158">版本 1808：10 月 8 日</span><span class="sxs-lookup"><span data-stu-id="94c5b-158">Version 1808: October 08</span></span>
<span data-ttu-id="94c5b-159">*版本 1808 (組建 10730.20386)*</span><span class="sxs-lookup"><span data-stu-id="94c5b-159">*Version 1808 (Build 10730.20386)*</span></span>

<span data-ttu-id="94c5b-160">安全性更新列於[此處](https://docs.microsoft.com/zh-TW/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="94c5b-160">Security updates listed [here](https://docs.microsoft.com/zh-TW/officeupdates/office365-proplus-security-updates)</span></span>

## <a name="version-1902-september-10"></a><span data-ttu-id="94c5b-161">版本 1902：9 月 10 日</span><span class="sxs-lookup"><span data-stu-id="94c5b-161">Version 1902: September 10</span></span>
<span data-ttu-id="94c5b-162">*版本 1902 (組建 11328.20420)*</span><span class="sxs-lookup"><span data-stu-id="94c5b-162">*Version 1902 (Build 11328.20420)*</span></span>

<span data-ttu-id="94c5b-163">安全性更新列於[此處](https://docs.microsoft.com/zh-TW/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="94c5b-163">Security updates listed [here](https://docs.microsoft.com/zh-TW/officeupdates/office365-proplus-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a><span data-ttu-id="94c5b-165">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-165">Non-security updates</span></span>
### <a name="access"></a><span data-ttu-id="94c5b-166">Access</span><span class="sxs-lookup"><span data-stu-id="94c5b-166">Access</span></span>

- <span data-ttu-id="94c5b-167">修正會導致 Microsoft Access 中特定查詢執行速度較舊版組建中更慢的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-167">Fixed an issue that caused certain queries in Microsoft Access to run more slowly than in previous builds.</span></span>

### <a name="outlook"></a><span data-ttu-id="94c5b-168">Outlook</span><span class="sxs-lookup"><span data-stu-id="94c5b-168">Outlook</span></span>

- <span data-ttu-id="94c5b-169">修正導致使用者看到「找不到此檔案」錯誤的暫時服務問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-169">Fixed temporary service issue that caused users to see the error "Cannot find this file.</span></span> <span data-ttu-id="94c5b-170">使用雲端附件時，請確認路徑和檔案名正確。</span><span class="sxs-lookup"><span data-stu-id="94c5b-170">Verify the path and file name are correct" when using cloud attachments.</span></span> [<span data-ttu-id="94c5b-171">深入了解</span><span class="sxs-lookup"><span data-stu-id="94c5b-171">Learn more</span></span>](https://support.office.com/zh-TW/article/outlook-unable-to-attach-onedrive-or-sharepoint-files-to-emails-136951bb-60dc-478a-b916-6ee39e62c37a)

- <span data-ttu-id="94c5b-172">修正會導致使用者看到從 Outlook 上傳至 OneDrive 或 SharePoint 檔案其檔案名稱已變更，其中的數個字元由底線取代的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-172">Fixed an issue that caused users to see uploaded files from Outlook to OneDrive or Sharepoint have the file name changed where several characters replaced by underscores.</span></span>

### <a name="word"></a><span data-ttu-id="94c5b-173">Word</span><span class="sxs-lookup"><span data-stu-id="94c5b-173">Word</span></span>

- <span data-ttu-id="94c5b-174">修正在 Word 文件上與其他人共同作業時，使用者會遇到錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-174">Fixed an issue where users would get error messages while collaborating with others on a Word document.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1808-september-10"></a><span data-ttu-id="94c5b-176">版本 1808：9 月 10 日</span><span class="sxs-lookup"><span data-stu-id="94c5b-176">Version 1808: September 10</span></span>
<span data-ttu-id="94c5b-177">*版本 1808 (組建 10730.20380)*</span><span class="sxs-lookup"><span data-stu-id="94c5b-177">*Version 1808 (Build 10730.20380)*</span></span>

<span data-ttu-id="94c5b-178">安全性更新列於[此處](https://docs.microsoft.com/zh-TW/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="94c5b-178">Security updates listed [here](https://docs.microsoft.com/zh-TW/officeupdates/office365-proplus-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a><span data-ttu-id="94c5b-180">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-180">Non-security updates</span></span>
### <a name="access"></a><span data-ttu-id="94c5b-181">Access</span><span class="sxs-lookup"><span data-stu-id="94c5b-181">Access</span></span>

- <span data-ttu-id="94c5b-182">修正會導致 Microsoft Access 中特定查詢執行速度較舊版組建中更慢的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-182">Fixed an issue that caused certain queries in Microsoft Access to run more slowly than in previous builds.</span></span>

## <a name="version-1902-august-13"></a><span data-ttu-id="94c5b-183">版本 1902：8 月 13 日</span><span class="sxs-lookup"><span data-stu-id="94c5b-183">Version 1902: August 13</span></span>
<span data-ttu-id="94c5b-184">*版本 1902 (組建 11328.20392)*</span><span class="sxs-lookup"><span data-stu-id="94c5b-184">*Version 1902 (Build 11328.20392)*</span></span>

<span data-ttu-id="94c5b-185">安全性更新列於[此處](https://docs.microsoft.com/zh-TW/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="94c5b-185">Security updates listed [here](https://docs.microsoft.com/zh-TW/officeupdates/office365-proplus-security-updates)</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="94c5b-186">Excel：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-186">Excel: Non-security updates</span></span>
- <span data-ttu-id="94c5b-187">修正清除篩選圖示同時對表格中已篩選和未篩選交叉分析篩選器顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-187">Fixed an issue where the clear filter icon was shown for both filtered and unfiltered Slicers in tables.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="94c5b-188">Outlook：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-188">Outlook: Non-security updates</span></span>
- <span data-ttu-id="94c5b-189">修正使用者將信箱從基本驗證升級為新式驗證後，造成關聯的帳戶錯誤的問題</span><span class="sxs-lookup"><span data-stu-id="94c5b-189">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="94c5b-190">PowerPoint：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-190">PowerPoint: Non-security updates</span></span>
- <span data-ttu-id="94c5b-191">修正與其他使用者就文件共同作業時，應用程式可能會意外終止的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-191">Fixed an issue where the application could unexpectedly terminate while collaborating on a document with other users.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="94c5b-192">Word：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-192">Word: Non-security updates</span></span>
- <span data-ttu-id="94c5b-193">修正 VBA 更新欄位很緩慢的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-193">Fixed an issue which VBA updating fields were slow.</span></span>
- <span data-ttu-id="94c5b-194">修正開啟部分 DOC 檔案時，出現提示說明檔案已損毀的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-194">Fixed in issue when opening some DOC file, it says it is corrupt.</span></span>
- <span data-ttu-id="94c5b-195">修正與其他使用者就文件共同作業時，應用程式可能會意外終止的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-195">Fixed an issue where the application could unexpectedly terminate while collaborating on a document with other users.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="94c5b-196">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-196">Office Suite: Non-security updates</span></span>
- <span data-ttu-id="94c5b-197">修正設定 API 在某些案例下無法在 Office JavaScript 程式庫運作的問題 [深入了解](https://support.microsoft.com/zh-TW/help/4475551/august-6-2019-update-for-office-2016-kb4475551)</span><span class="sxs-lookup"><span data-stu-id="94c5b-197">Fixed an issue in which Setting API doesn't work in the Office JavaScript library in certain scenarios [Learn More](https://support.microsoft.com/zh-TW/help/4475551/august-6-2019-update-for-office-2016-kb4475551)</span></span>

## <a name="version-1808-august-13"></a><span data-ttu-id="94c5b-198">版本 1808：8 月 13 日</span><span class="sxs-lookup"><span data-stu-id="94c5b-198">Version 1808 August 13</span></span>
<span data-ttu-id="94c5b-199">*版本 1808 (組建 10730.20370)*</span><span class="sxs-lookup"><span data-stu-id="94c5b-199">*Version 1808 (Build 10730.20370)*</span></span>

<span data-ttu-id="94c5b-200">安全性更新列於[此處](https://docs.microsoft.com/zh-TW/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="94c5b-200">Security updates listed [here](https://docs.microsoft.com/zh-TW/officeupdates/office365-proplus-security-updates)</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="94c5b-201">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-201">Office Suite: Non-security updates</span></span>
- <span data-ttu-id="94c5b-202">修正設定 API 在某些案例下無法在 Office JavaScript 程式庫運作的問題 [深入了解](https://support.microsoft.com/zh-TW/help/4475551/august-6-2019-update-for-office-2016-kb4475551)</span><span class="sxs-lookup"><span data-stu-id="94c5b-202">Fixed an issue in which Setting API doesn't work in the Office JavaScript library in certain scenarios [Learn More](https://support.microsoft.com/zh-TW/help/4475551/august-6-2019-update-for-office-2016-kb4475551)</span></span>


## <a name="version-1803-august-13"></a><span data-ttu-id="94c5b-203">版本 1803：8 月 13 日</span><span class="sxs-lookup"><span data-stu-id="94c5b-203">Version 1803 August 13</span></span>
<span data-ttu-id="94c5b-204">*版本 1803 (組建 9126.2432)*</span><span class="sxs-lookup"><span data-stu-id="94c5b-204">*Version 1803 (Build 9126.2432)*</span></span>

<span data-ttu-id="94c5b-205">安全性更新列於[此處](https://docs.microsoft.com/zh-TW/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="94c5b-205">Security updates listed [here](https://docs.microsoft.com/zh-TW/officeupdates/office365-proplus-security-updates)</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="94c5b-206">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-206">Office Suite: Non-security updates</span></span>
- <span data-ttu-id="94c5b-207">修正設定 API 在某些案例下無法在 Office JavaScript 程式庫運作的問題 [深入了解](https://support.microsoft.com/zh-TW/help/4475551/august-6-2019-update-for-office-2016-kb4475551)</span><span class="sxs-lookup"><span data-stu-id="94c5b-207">Fixed an issue in which Setting API doesn't work in the Office JavaScript library in certain scenarios [Learn More](https://support.microsoft.com/zh-TW/help/4475551/august-6-2019-update-for-office-2016-kb4475551)</span></span>


## <a name="version-1902-july-09"></a><span data-ttu-id="94c5b-208">版本 1902：7 月 9 日</span><span class="sxs-lookup"><span data-stu-id="94c5b-208">Version 1902: July 09</span></span>
<span data-ttu-id="94c5b-209">*版本 1902 (組建 11328.20368)*</span><span class="sxs-lookup"><span data-stu-id="94c5b-209">*Version 1902 (Build 11328.20368)*</span></span>
<br/><span data-ttu-id="94c5b-210">安全性更新列於[此處](https://docs.microsoft.com/zh-TW/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="94c5b-210">Security updates listed [here](https://docs.microsoft.com/zh-TW/officeupdates/office365-proplus-security-updates)</span></span>


### <a name="access-feature-updates"></a><span data-ttu-id="94c5b-211">Access：功能更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-211">Access: Feature updates</span></span>

- <span data-ttu-id="94c5b-212">**重新整理、重新連結或移除連結的資料表** 更新的連結資料表管理員是用於管理所有資料來源與連結資料表的位置。</span><span class="sxs-lookup"><span data-stu-id="94c5b-212">**Refresh, relink, or remove linked tables:** The updated Linked Table Manager is the location for managing all data sources and linked tables.</span></span> [<span data-ttu-id="94c5b-213">深入了解</span><span class="sxs-lookup"><span data-stu-id="94c5b-213">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)
- <span data-ttu-id="94c5b-p105">**繪製成黑色、繪製成灰色：** 依照您的喜好變更 Access 的外觀。有四個佈景主題可供選擇：彩色、深灰色、黑色或白色。[深入了解](https://support.office.com/article/9d76a8b4-bfff-48a9-b8c8-8e133461bc94)</span><span class="sxs-lookup"><span data-stu-id="94c5b-p105">**Paint it black, paint it gray:** Change the look of Access as often as you like. Four themes to choose from: Colorful, Dark Gray, Black, or White. [Learn more](https://support.office.com/article/9d76a8b4-bfff-48a9-b8c8-8e133461bc94)</span></span>
- <span data-ttu-id="94c5b-217">**Office 擁有新的外觀：** Office應用程式現在擁有更簡單、更方便使用的現代化圖示，而功能區也更新了視覺效果，能強調顯示 Office 應用程式中的豐富共同作業功能。</span><span class="sxs-lookup"><span data-stu-id="94c5b-217">**Office has a new look:**  Office apps now have modern icons that are simpler and more accessible, and the ribbon has updated visuals that highlight the rich collaboration features available in Office apps.</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="94c5b-218">Excel：功能更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-218">Excel: Feature updates</span></span>

- <span data-ttu-id="94c5b-219">**更快速地開始**：新設計的 [開始頁面] 會將您最近開啟的文件放在最前面並置中。</span><span class="sxs-lookup"><span data-stu-id="94c5b-219">**Get a faster start** The newly designed Start Page puts your recently opened documents front and center.</span></span> <span data-ttu-id="94c5b-220">按幾下便能取得檔案，並從這裡直接開啟 [帳戶] 設定或 [選項]。</span><span class="sxs-lookup"><span data-stu-id="94c5b-220">Get to files in fewer clicks, and open Account settings or Options right from here.</span></span>
- <span data-ttu-id="94c5b-221">**使用註解共同作業：** 使用內建的回覆方塊試保持試算表中的交談正確。</span><span class="sxs-lookup"><span data-stu-id="94c5b-221">**Collaborate with comments:** Keep the conversation going right in your spreadsheet with the built-in reply box.</span></span> [<span data-ttu-id="94c5b-222">深入了解</span><span class="sxs-lookup"><span data-stu-id="94c5b-222">Learn more</span></span>](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)
- <span data-ttu-id="94c5b-223">**功能區圖示有了嶄新的外觀：** 別擔心，功能一切如常。</span><span class="sxs-lookup"><span data-stu-id="94c5b-223">**Your ribbon icons have a new look:** Don’t worry, everything works the same.</span></span> <span data-ttu-id="94c5b-224">此外，它們在各種尺寸的螢幕上看起來很棒。</span><span class="sxs-lookup"><span data-stu-id="94c5b-224">Plus, they look great on screens of all sizes.</span></span> [<span data-ttu-id="94c5b-225">深入了解</span><span class="sxs-lookup"><span data-stu-id="94c5b-225">Learn more</span></span>](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- <span data-ttu-id="94c5b-p109">**能在套用篩選時插入 SVG：** Office 使用者現在可以在套用篩選的同時，插入 SVG。[深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="94c5b-p109">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>
- <span data-ttu-id="94c5b-p110">**顯示圖片後面的內容：** 將圖片放在工作表中、挑選您的預設，並觀看透明度變更。就這麼簡單！[深入了解](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span><span class="sxs-lookup"><span data-stu-id="94c5b-p110">**Reveal what's behind a picture:** Put a picture in a worksheet, pick your preset, and watch the transparency change. That's it! [Learn more](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span></span>
- <span data-ttu-id="94c5b-231">**呼叫所有「取得與轉換」粉絲：** 如果您經常使用「取得與轉換」，您會很高興知道我們已改善資料行來源範例功能。</span><span class="sxs-lookup"><span data-stu-id="94c5b-231">**Calling all Get & Transform fans:** If you use Get & Transform a lot, you'll be happy to know that the Column From Example feature has been improved.</span></span> <span data-ttu-id="94c5b-232">此外，也已改善許多連接器。</span><span class="sxs-lookup"><span data-stu-id="94c5b-232">And, many connectors have been improved as well.</span></span> [<span data-ttu-id="94c5b-233">深入了解</span><span class="sxs-lookup"><span data-stu-id="94c5b-233">Learn more</span></span>](https://support.office.com/article/ed01ec34-679d-48e7-ba49-bb14c7908f9e)
- <span data-ttu-id="94c5b-234">**改善了對高解析度顯示器的支援**：現在，如果您使用多部監視器或筆記型電腦基座，Office 應用程式在每個顯示器上都會順暢清晰地呈現，即使顯示器使用不同的縮放設定亦然。</span><span class="sxs-lookup"><span data-stu-id="94c5b-234">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings.</span></span> [<span data-ttu-id="94c5b-235">深入了解</span><span class="sxs-lookup"><span data-stu-id="94c5b-235">Learn more</span></span>](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- <span data-ttu-id="94c5b-236">**快速查閱** 我們已加速 VLOOKUP、HLOOKUP 和 MATCH 的計算速度，讓您能更快得到答案。</span><span class="sxs-lookup"><span data-stu-id="94c5b-236">**Speedy Lookup** We've turbo-charged your VLOOKUP, HLOOKUP, and MATCH calculations so you can get answers faster.</span></span> [<span data-ttu-id="94c5b-237">深入了解</span><span class="sxs-lookup"><span data-stu-id="94c5b-237">Learn more</span></span>](https://support.office.com/article/60f18521-2589-4734-89dd-ba4ee1f6c000)

### <a name="outlook-feature-updates"></a><span data-ttu-id="94c5b-238">Outlook：功能更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-238">Outlook: Feature updates</span></span>

- <span data-ttu-id="94c5b-p114">**使用「大聲朗讀」聆聽您的電子郵件：** Outlook 可以大聲朗讀您的電子郵件，強調所朗讀的文字。若要開啟 [大聲朗讀]，請移至 [輕鬆存取] 設定。[深入了解](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)</span><span class="sxs-lookup"><span data-stu-id="94c5b-p114">**Use Read Aloud to listen to your email:** Outlook can read your email aloud, highlighting text as it's read. To turn on Read Aloud, go to the Ease of Access settings. [Learn more](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)</span></span>
- <span data-ttu-id="94c5b-242">**免用手輸入：** 您有麥克風嗎？</span><span class="sxs-lookup"><span data-stu-id="94c5b-242">**Type hands-free:** Got a microphone?</span></span> <span data-ttu-id="94c5b-243">按一下 [聽寫] 並看看 Outlook 如何在您說話的同時輸入您說話的內容。</span><span class="sxs-lookup"><span data-stu-id="94c5b-243">Click Dictate and watch Outlook type while you talk.</span></span> [<span data-ttu-id="94c5b-244">深入了解</span><span class="sxs-lookup"><span data-stu-id="94c5b-244">Learn more</span></span>](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- <span data-ttu-id="94c5b-245">**功能區圖示有了嶄新的外觀：** 別擔心，功能一切如常。</span><span class="sxs-lookup"><span data-stu-id="94c5b-245">**Your ribbon icons have a new look:** Don’t worry, everything works the same.</span></span> <span data-ttu-id="94c5b-246">此外，它們在各種尺寸的螢幕上看起來很棒。</span><span class="sxs-lookup"><span data-stu-id="94c5b-246">Plus, they look great on screens of all sizes.</span></span> [<span data-ttu-id="94c5b-247">深入了解</span><span class="sxs-lookup"><span data-stu-id="94c5b-247">Learn more</span></span>](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- <span data-ttu-id="94c5b-248">**在經 SMIME 加密和簽署的電子郵件中，預設封鎖外部內容的下載：** 由於 SMIME 通訊協定中存在漏洞，Outlook 將封鎖在已通過 SMIME 加密或簽署的郵件上下載外部內容。</span><span class="sxs-lookup"><span data-stu-id="94c5b-248">**Block download of external content by default in SMIME encrypted and signed emails:** Due to a vulnerability in the SMIME protocol - Outlook will block download of external content on messages that have been encrypted or signed over SMIME.</span></span> <span data-ttu-id="94c5b-249">使用者無法透過 Outlook UI 的按下動作下載外部內容，藉此防止安全性漏洞。</span><span class="sxs-lookup"><span data-stu-id="94c5b-249">Users will not be able to single-click download external content through Outlook UI to protect from the security vulnerability.</span></span> <span data-ttu-id="94c5b-250">[選項] 對話方塊中有一個新選項，可讓使用者回復為舊行為。</span><span class="sxs-lookup"><span data-stu-id="94c5b-250">There is a new option in the Options dialog to allow for users to revert to old behavior.</span></span>
- <span data-ttu-id="94c5b-251">**關閉會議轉寄功能：** 防止出席者將您的會議轉寄給其他人。</span><span class="sxs-lookup"><span data-stu-id="94c5b-251">**Turn off forwarding for a meeting:** Prevent attendees from forwarding your meeting to others.</span></span> <span data-ttu-id="94c5b-252">只需移至功能區，按一下 [回應選項] 即可。</span><span class="sxs-lookup"><span data-stu-id="94c5b-252">Just go to the ribbon and click Response Options.</span></span> [<span data-ttu-id="94c5b-253">深入了解</span><span class="sxs-lookup"><span data-stu-id="94c5b-253">Learn more</span></span>](https://support.office.com/article/5C9877BC-AB91-4A7C-99FB-B0B68D7EA94F)
- <span data-ttu-id="94c5b-p119">**排程助理員中的人員建議：** 在您排定會議時查看對要新增之出席者的建議。不再來回切換排程助理員與收件者。[深入了解](https://support.office.com/article/d284c6d9-206e-4926-92b4-5addc0fcbefb)</span><span class="sxs-lookup"><span data-stu-id="94c5b-p119">**People suggestions in the Scheduling Assistant:** See recommendations for attendees to add when you schedule a meeting. No more switching back and forth between the Scheduling Assistant and the To line. [Learn more](https://support.office.com/article/d284c6d9-206e-4926-92b4-5addc0fcbefb)</span></span>
- <span data-ttu-id="94c5b-257">**預留房間更加輕鬆：** 使用多個會議室清單尋找會議室 - 以及切換清單，而不會失去您已選取的會議室。</span><span class="sxs-lookup"><span data-stu-id="94c5b-257">**Reserving a room just got easier:** Look for a conference room using more than one room list - and switch lists without losing rooms you've selected.</span></span>
- <span data-ttu-id="94c5b-p120">**循環範圍的新預設值：** 在 [週期設定] 對話方塊中，循環範圍之前的預設值為 [沒有結束日期]。雖然這有助於建立長時間執行的週期性系列，但在一段時間之後可能會發生損壞。我們正將 [週期設定] 對話方塊的預設值更新為 [結束於]，這樣我們的預設值就會符合行事曆操作的建議最佳做法。</span><span class="sxs-lookup"><span data-stu-id="94c5b-p120">**New default for range of recurrence:** For the Recurrence dialog, the range of recurrence used to default for "No end date". This facilitated the creation of long-running recurring series, which can become corrupted over time. We are updating the default for the Recurrence dialog to "End by", such that our default value matches recommended best practices for calendaring.</span></span>
- <span data-ttu-id="94c5b-p121">**從 Outlook 提醒對話方塊加入小組會議：** 當 Outlook 提醒使用者有即將來臨的會議時，如果即將來臨的會議是小組線上會議，則它會顯示 [線上加入] 按鈕。這個動作與從 Outlook [提醒] 對話方塊加入商務用 Skype 會議的體驗類似。</span><span class="sxs-lookup"><span data-stu-id="94c5b-p121">**Join Teams meetings from the Outlook Reminders dialog:** When Outlook reminds users of an upcoming meeting, it will show a Join Online button if the upcoming meeting is a Teams online meeting. This is similar to the experience of joining a Skype for Business meeting from the Outlook Reminders dialog.</span></span>
- <span data-ttu-id="94c5b-263">**停止看到過去事件的提醒：** 您可以設定行事曆，以在事件結束之後自動關閉事件的提醒。</span><span class="sxs-lookup"><span data-stu-id="94c5b-263">**Stop seeing reminders for past events:** You can set your calendar to automatically dismiss reminders for events after they've ended.</span></span> [<span data-ttu-id="94c5b-264">深入了解</span><span class="sxs-lookup"><span data-stu-id="94c5b-264">Learn more</span></span>](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)
- <span data-ttu-id="94c5b-265">**查看安全連結背後的 URL：** 安全連結可保護您防範在電子郵件中收到但隱藏原始 URL 的惡意 URL。</span><span class="sxs-lookup"><span data-stu-id="94c5b-265">**See the URL behind Safe Links:** Safe Links protects you from malicious URLS received in email but they hide the original URL.</span></span> <span data-ttu-id="94c5b-266">若要查看原始 URL，請將滑鼠游標移到 URL 上。</span><span class="sxs-lookup"><span data-stu-id="94c5b-266">To see the original, hover your mouse over the URL.</span></span> <span data-ttu-id="94c5b-267">需要進階威脅防護授權。</span><span class="sxs-lookup"><span data-stu-id="94c5b-267">Requires an Advanced Threat Protection license.</span></span> [<span data-ttu-id="94c5b-268">深入了解</span><span class="sxs-lookup"><span data-stu-id="94c5b-268">Learn more</span></span>](https://products.office.com/zh-TW/exchange/advance-threat-protection)
- <span data-ttu-id="94c5b-269">**縮放與搖桿：** 選擇要用於所有郵件的預設值，而不用在每次讀取郵件時調整 [縮放]。</span><span class="sxs-lookup"><span data-stu-id="94c5b-269">**Zoom and stick:** Instead of adjusting Zoom each time you read a message, choose a default to use for all your messages.</span></span> [<span data-ttu-id="94c5b-270">深入了解</span><span class="sxs-lookup"><span data-stu-id="94c5b-270">Learn more</span></span>](https://support.office.com/article/56c090bc-e148-44a7-bd06-1290edd38983)
- <span data-ttu-id="94c5b-271">**郵件加密：僅加密 IRM 原則：**[選項] > [權限] 功能表上的全新僅加密選項，供 Office 365 郵件加密使用者使用。</span><span class="sxs-lookup"><span data-stu-id="94c5b-271">**Message Encryption: encrypt-only IRM policy:** New encrypt-only option appears in the Options > Permissions menu for Office 365 Message Encryption users.</span></span> <span data-ttu-id="94c5b-272">這個選項可讓您加密郵件，並將郵件傳送給組織內外的任何人。</span><span class="sxs-lookup"><span data-stu-id="94c5b-272">This option allows you to encrypt a message and send it to anyone, inside or outside your organization.</span></span>
- <span data-ttu-id="94c5b-273">**當您被列於密件副本時，顯示提醒：** 當您不小心回覆所有人，而將自己列於密件副本時，密件副本資訊提示會顯示提醒。</span><span class="sxs-lookup"><span data-stu-id="94c5b-273">**Warning when you've been BCC'ed:** The BCC infotip will warn you before you accidentally reply all to a mail that you've been blind carbon copied on.</span></span>
- <span data-ttu-id="94c5b-274">**更智慧的 [收件者:] 行：** 當您按一下 [收件者:] 行來撰寫郵件時，我們會建議您可能要選擇的收件者。</span><span class="sxs-lookup"><span data-stu-id="94c5b-274">**A smarter To: line:** When you click the To: line to address a message, we suggest recipients you're likely to choose.</span></span> <span data-ttu-id="94c5b-275">此外，還可以看到收件者的相片，讓您知道要傳送的對象是正確的。</span><span class="sxs-lookup"><span data-stu-id="94c5b-275">Plus, you can see their picture, so you know yo’re sending to the right person.</span></span> [<span data-ttu-id="94c5b-276">深入了解</span><span class="sxs-lookup"><span data-stu-id="94c5b-276">Learn more</span></span>](https://support.office.com/article/147208AF-CA8E-4CDF-B71F-77BA81A54069)
- <span data-ttu-id="94c5b-p127">**能在套用篩選時插入 SVG：** Office 使用者現在可以在套用篩選的同時，插入 SVG。[深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="94c5b-p127">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>
- <span data-ttu-id="94c5b-279">**改善了對高解析度顯示器的支援**：現在，如果您使用多部監視器或筆記型電腦基座，Office 應用程式在每個顯示器上都會順暢清晰地呈現，即使顯示器使用不同的縮放設定亦然。</span><span class="sxs-lookup"><span data-stu-id="94c5b-279">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings.</span></span> [<span data-ttu-id="94c5b-280">深入了解</span><span class="sxs-lookup"><span data-stu-id="94c5b-280">Learn more</span></span>](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="94c5b-281">PowerPoint：功能更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-281">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="94c5b-282">**更快速地開始**：新設計的 [開始頁面] 會將您最近開啟的文件放在最前面並置中。</span><span class="sxs-lookup"><span data-stu-id="94c5b-282">**Get a faster start** The newly designed Start Page puts your recently opened documents front and center.</span></span> <span data-ttu-id="94c5b-283">按幾下便能取得檔案，並從這裡直接開啟 [帳戶] 設定或 [選項]。</span><span class="sxs-lookup"><span data-stu-id="94c5b-283">Get to files in fewer clicks, and open Account settings or Options right from here.</span></span>
- <span data-ttu-id="94c5b-284">**免用手輸入：** 您有麥克風嗎？</span><span class="sxs-lookup"><span data-stu-id="94c5b-284">**Type hands-free:** Got a microphone?</span></span> <span data-ttu-id="94c5b-285">按一下 [聽寫] 並看看 PowerPoint 如何在您說話的同時輸入您說話的內容。</span><span class="sxs-lookup"><span data-stu-id="94c5b-285">Click Dictate and watch PowerPoint type while you talk.</span></span> [<span data-ttu-id="94c5b-286">深入了解</span><span class="sxs-lookup"><span data-stu-id="94c5b-286">Learn more</span></span>](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- <span data-ttu-id="94c5b-287">**功能區圖示有了嶄新的外觀：** 別擔心，功能一切如常。</span><span class="sxs-lookup"><span data-stu-id="94c5b-287">**Your ribbon icons have a new look:** Don’t worry, everything works the same.</span></span> <span data-ttu-id="94c5b-288">此外，它們在各種尺寸的螢幕上看起來很棒。</span><span class="sxs-lookup"><span data-stu-id="94c5b-288">Plus, they look great on screens of all sizes.</span></span> [<span data-ttu-id="94c5b-289">深入了解</span><span class="sxs-lookup"><span data-stu-id="94c5b-289">Learn more</span></span>](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- <span data-ttu-id="94c5b-290">**改善了對高解析度顯示器的支援**：現在，如果您使用多部監視器或筆記型電腦基座，Office 應用程式在每個顯示器上都會順暢清晰地呈現，即使顯示器使用不同的縮放設定亦然。</span><span class="sxs-lookup"><span data-stu-id="94c5b-290">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings.</span></span> [<span data-ttu-id="94c5b-291">深入了解</span><span class="sxs-lookup"><span data-stu-id="94c5b-291">Learn more</span></span>](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- <span data-ttu-id="94c5b-292">**色彩生動的超連結：** 超連結不再只是藍色的。</span><span class="sxs-lookup"><span data-stu-id="94c5b-292">**Hyperlinks in living color:** Hyperlinks aren't just blue anymore.</span></span> <span data-ttu-id="94c5b-293">您可以套用您喜歡的任何字型色彩。</span><span class="sxs-lookup"><span data-stu-id="94c5b-293">Apply any font color you like.</span></span> [<span data-ttu-id="94c5b-294">深入了解</span><span class="sxs-lookup"><span data-stu-id="94c5b-294">Learn more</span></span>](https://support.office.com/article/988ed94c-82e9-4e2c-96a1-7ffd2c382ce8)
- <span data-ttu-id="94c5b-295">**生動地觀看您的投影片：** 插入動畫 3D 圖形，來查看心跳、行星軌道，以及暴龍在整個畫面橫衝直撞。</span><span class="sxs-lookup"><span data-stu-id="94c5b-295">**Watch your slides come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage across the screen.</span></span> [<span data-ttu-id="94c5b-296">深入了解</span><span class="sxs-lookup"><span data-stu-id="94c5b-296">Learn more</span></span>](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)
- <span data-ttu-id="94c5b-p135">**您素描，我修飾：** 我們可將手繪文字和形狀變為更精緻的圖表。只需選取您的筆跡線條即可開始。[深入了解](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="94c5b-p135">**You sketch, we polish:** We change hand-drawn text and shapes into refined diagrams. Just select your ink strokes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>
- <span data-ttu-id="94c5b-p136">**顯示圖片後面的內容：** 將圖片放在工作表中、挑選您的預設，並觀看透明度變更。就這麼簡單！[深入了解](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span><span class="sxs-lookup"><span data-stu-id="94c5b-p136">**Reveal what's behind a picture:** Put a picture in a worksheet, pick your preset, and watch the transparency change. That's it! [Learn more](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span></span>
- <span data-ttu-id="94c5b-303">**運用筆跡製作精彩的投影片：** 將筆跡轉換成標準圖形和文字，然後從 PowerPoint 設計工具吸取智慧的投影片設計概念。</span><span class="sxs-lookup"><span data-stu-id="94c5b-303">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="94c5b-304">深入了解</span><span class="sxs-lookup"><span data-stu-id="94c5b-304">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)
- <span data-ttu-id="94c5b-305">**發佈到 Microsoft Stream：** 透過使用 Microsoft Stream，在組織內更安全地以影片形式共用簡報。</span><span class="sxs-lookup"><span data-stu-id="94c5b-305">**Publish to Microsoft Stream:** Share a presentation as a video more securely within your organization by using Microsoft Stream.</span></span> [<span data-ttu-id="94c5b-306">深入了解</span><span class="sxs-lookup"><span data-stu-id="94c5b-306">Learn more</span></span>](https://support.office.com/article/c140551f-cb37-4818-b5d4-3e30815c3e83)
- <span data-ttu-id="94c5b-307">**匯出為 4K 影片：** 您現在可以在將簡報匯出為影片時選取 4K 解析度。</span><span class="sxs-lookup"><span data-stu-id="94c5b-307">**Export to 4K video:** When you export a presentation to video, 4K resolution is now an option.</span></span>  [<span data-ttu-id="94c5b-308">深入了解</span><span class="sxs-lookup"><span data-stu-id="94c5b-308">Learn more</span></span>](https://support.office.com/article/c140551f-cb37-4818-b5d4-3e30815c3e83)
- <span data-ttu-id="94c5b-p140">**能在套用篩選時插入 SVG：** Office 使用者現在可以在套用篩選的同時，插入 SVG。[深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="94c5b-p140">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>
- <span data-ttu-id="94c5b-311">**大型檔案現在會以更快速度開啟：** 現在開啟儲存在 OneDrive 或 SharePoint 上的檔案時，會在背景下載影像、影片及其他大型元素。</span><span class="sxs-lookup"><span data-stu-id="94c5b-311">**Large files now open faster:** Images, videos, and other large elements now download in the background when opening files stored on OneDrive or SharePoint.</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="94c5b-312">Word：功能更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-312">Word: Feature updates</span></span>

- <span data-ttu-id="94c5b-313">**更快速地開始**：新設計的 [開始頁面] 會將您最近開啟的文件放在最前面並置中。</span><span class="sxs-lookup"><span data-stu-id="94c5b-313">**Get a faster start** The newly designed Start Page puts your recently opened documents front and center.</span></span> <span data-ttu-id="94c5b-314">按幾下便能取得檔案，並從這裡直接開啟 [帳戶] 設定或 [選項]。</span><span class="sxs-lookup"><span data-stu-id="94c5b-314">Get to files in fewer clicks, and open Account settings or Options right from here.</span></span>
- <span data-ttu-id="94c5b-315">**免用手輸入：** 您有麥克風嗎？</span><span class="sxs-lookup"><span data-stu-id="94c5b-315">**Type hands-free:** Got a microphone?</span></span> <span data-ttu-id="94c5b-316">按一下 [聽寫] 並看看 Word 如何在您說話的同時輸入您說話的內容。</span><span class="sxs-lookup"><span data-stu-id="94c5b-316">Click Dictate and watch Word type while you talk.</span></span> [<span data-ttu-id="94c5b-317">深入了解</span><span class="sxs-lookup"><span data-stu-id="94c5b-317">Learn more</span></span>](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- <span data-ttu-id="94c5b-p143">**生動地觀看您的文件：** 插入動畫 3D 圖形，來查看心跳、行星軌道，以及暴龍在整個頁面橫衝直撞。[深入了解](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)</span><span class="sxs-lookup"><span data-stu-id="94c5b-p143">**Watch your documents come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage across the page. [Learn more](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)</span></span>
- <span data-ttu-id="94c5b-320">**功能區圖示有了嶄新的外觀：** 別擔心，功能一切如常。</span><span class="sxs-lookup"><span data-stu-id="94c5b-320">**Your ribbon icons have a new look:** Don’t worry, everything works the same.</span></span> <span data-ttu-id="94c5b-321">此外，它們在各種尺寸的螢幕上看起來很棒。</span><span class="sxs-lookup"><span data-stu-id="94c5b-321">Plus, they look great on screens of all sizes.</span></span> [<span data-ttu-id="94c5b-322">深入了解</span><span class="sxs-lookup"><span data-stu-id="94c5b-322">Learn more</span></span>](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- <span data-ttu-id="94c5b-p145">**顯示圖片後面的內容：** 將圖片放在工作表中、挑選您的預設，並觀看透明度變更。就這麼簡單！[深入了解](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span><span class="sxs-lookup"><span data-stu-id="94c5b-p145">**Reveal what's behind a picture:** Put a picture in a worksheet, pick your preset, and watch the transparency change. That's it! [Learn more](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span></span>
- <span data-ttu-id="94c5b-p146">**能在套用篩選時插入 SVG：** Office 使用者現在可以在套用篩選的同時，插入 SVG。[深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="94c5b-p146">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>
- <span data-ttu-id="94c5b-328">**改善了對高解析度顯示器的支援**：現在，如果您使用多部監視器或筆記型電腦基座，Office 應用程式在每個顯示器上都會順暢清晰地呈現，即使顯示器使用不同的縮放設定亦然。</span><span class="sxs-lookup"><span data-stu-id="94c5b-328">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings.</span></span> [<span data-ttu-id="94c5b-329">深入了解</span><span class="sxs-lookup"><span data-stu-id="94c5b-329">Learn more</span></span>](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- <span data-ttu-id="94c5b-p148">**利用 LinkedIn 的協助撰寫最佳簡歷或履歷表：** 利用簡歷小幫手，查看特定角色的工作經驗、建議的技能以及其他資訊。 [深入了解](https://support.office.com/article/444ff6f0-ef74-4a9c-9091-ffd7a9d1917a)</span><span class="sxs-lookup"><span data-stu-id="94c5b-p148">**Write your best resume or CV with help from LinkedIn:** With Resume Assistant, see work experiences, suggested skills, and more for a given role. [Learn more](https://support.office.com/article/444ff6f0-ef74-4a9c-9091-ffd7a9d1917a)</span></span>

### <a name="project-feature-updates"></a><span data-ttu-id="94c5b-332">Project：功能更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-332">Project: Feature updates</span></span>

- <span data-ttu-id="94c5b-333">**在工作面板卡片上查看詳細資訊：** 當標題本身無法陳述完整故事時，請自訂您的工作面板卡片，以顯示所有最重要的詳細資料。</span><span class="sxs-lookup"><span data-stu-id="94c5b-333">**See more info on Task Board cards:** When the title alone doesn’t tell the story, customize your Task Board cards to show all the most important details.</span></span> [<span data-ttu-id="94c5b-334">深入了解</span><span class="sxs-lookup"><span data-stu-id="94c5b-334">Learn more</span></span>](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)
- <span data-ttu-id="94c5b-335">**Office 擁有新的外觀：** Office應用程式現在擁有更簡單、更方便使用的現代化圖示，而功能區也更新了視覺效果，能強調顯示 Office 應用程式中的豐富共同作業功能。</span><span class="sxs-lookup"><span data-stu-id="94c5b-335">**Office has a new look:**  Office apps now have modern icons that are simpler and more accessible, and the ribbon has updated visuals that highlight the rich collaboration features available in Office apps.</span></span>

### <a name="publisher-feature-updates"></a><span data-ttu-id="94c5b-336">Publisher：功能更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-336">Publisher: Feature updates</span></span>

- <span data-ttu-id="94c5b-337">**Office 擁有新的外觀：** Office應用程式現在擁有更簡單、更方便使用的現代化圖示，而功能區也更新了視覺效果，能強調顯示 Office 應用程式中的豐富共同作業功能。</span><span class="sxs-lookup"><span data-stu-id="94c5b-337">**Office has a new look:**  Office apps now have modern icons that are simpler and more accessible, and the ribbon has updated visuals that highlight the rich collaboration features available in Office apps.</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="94c5b-338">Visio：功能更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-338">Visio: Feature updates</span></span>

- <span data-ttu-id="94c5b-339">**在下一個圖表中享受圖示時刻：** 有 26 個全新的圖示樣板供您挑選，其中包含分析、藝術、慶典、臉部、運動和其他圖示。</span><span class="sxs-lookup"><span data-stu-id="94c5b-339">**Enjoy an iconic moment in your next diagram:** Pick from 26 new stencils with icons for analytics, arts, celebration, faces, sports, and more.</span></span>
- <span data-ttu-id="94c5b-340">**Office 擁有新的外觀：** Office應用程式現在擁有更簡單、更方便使用的現代化圖示，而功能區也更新了視覺效果，能強調顯示 Office 應用程式中的豐富共同作業功能。</span><span class="sxs-lookup"><span data-stu-id="94c5b-340">**Office has a new look:**  Office apps now have modern icons that are simpler and more accessible, and the ribbon has updated visuals that highlight the rich collaboration features available in Office apps.</span></span>

### <a name="office-suite-feature-updates"></a><span data-ttu-id="94c5b-341">Office 套件：功能更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-341">Office Suite: Feature updates</span></span>

- <span data-ttu-id="94c5b-p150">**Office 第三方應用程式現在已使用 office.js api 擁有插入 SVG 支援的功能：** 亦稱為 Office 增益集的第三方應用程式現在擁有插入 SVG 的功能。使用者現在可以將個人的 SVG 集合連線至 Office。開發人員現在可以使用 Office.js API 來使用這項功能。</span><span class="sxs-lookup"><span data-stu-id="94c5b-p150">**Office 3rd Party Applications now have insert SVG support using the office.js api:** 3rd party applications also known as add-ins in Office now have the ability to insert SVG's. Users can now connect their personal collection of SVG's to Office. Developers can use this feature by using the Office.js API.</span></span>
- <span data-ttu-id="94c5b-345">**安裝 Microsoft Teams：** 在 Office 365 專業增強版的新安裝中，預設會安裝 Microsoft Teams。</span><span class="sxs-lookup"><span data-stu-id="94c5b-345">**Installation of Microsoft Teams:**  Microsoft Teams is installed by default for NEW installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="94c5b-346">深入了解</span><span class="sxs-lookup"><span data-stu-id="94c5b-346">Learn more</span></span>](https://docs.microsoft.com/zh-TW/DeployOffice/teams-install)

### <a name="skype-for-business-feature-updates"></a><span data-ttu-id="94c5b-347">商務用 Skype：功能更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-347">Skype for Business: Feature updates</span></span>

- <span data-ttu-id="94c5b-348">**改善了對高解析度顯示器的支援**：現在，如果您使用多部監視器或筆記型電腦基座，Office 應用程式在每個顯示器上都會順暢清晰地呈現，即使顯示器使用不同的縮放設定亦然。</span><span class="sxs-lookup"><span data-stu-id="94c5b-348">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings.</span></span> [<span data-ttu-id="94c5b-349">深入了解</span><span class="sxs-lookup"><span data-stu-id="94c5b-349">Learn more</span></span>](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)


### <a name="excel-non-security-updates"></a><span data-ttu-id="94c5b-350">Excel：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-350">Excel: Non-security updates</span></span>

- <span data-ttu-id="94c5b-351">已解決將包含 XML 對應的檔案儲存為 PDF 時導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-351">Resolved an issue that caused a crash when saving a file containing an XML map to PDF.</span></span>
- <span data-ttu-id="94c5b-352">已解決在載入包含無效工作表名稱之活頁簿時，導致外部連結遭到刪除的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-352">Resolved an issue that caused external links to be removed when workbooks containing invalid sheet names are loaded.</span></span>
- <span data-ttu-id="94c5b-353">已修正在 Excel 中使用相機工具可能會造成試算表當機的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-353">Fixed an issue where using the Camera tool in Excel could cause the spreadsheet to hang.</span></span>
- <span data-ttu-id="94c5b-354">已解決當插入或刪除儲存格時，瀑布圖和漏斗圖無法與表格同步處理的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-354">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>
- <span data-ttu-id="94c5b-355">已解決在工作表計算期間，使用依賴表格之另一個工作表上的陣列公式重新計算資料表格的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-355">Resolved an issue when a data table is recalculated during Worksheet Calculate with an array formula on another sheet depending on the table.</span></span> 
- <span data-ttu-id="94c5b-356">已解決未先簽出檔案，無法從 SharePoint 開啟受密碼保護的活頁簿的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-356">Resolved an issue that prevented password protected workbooks from being opened from SharePoint without checking out file first.</span></span>
- <span data-ttu-id="94c5b-357">已進行變更，確保在共用或切換自動儲存時，處理 BeforeSave 事件。</span><span class="sxs-lookup"><span data-stu-id="94c5b-357">A change was made to ensure the BeforeSave event is handled when sharing or toggling AutoSave.</span></span> 
- <span data-ttu-id="94c5b-358">已修正在帶有圖表工作表的非使用中視窗中使用滑鼠滾輪的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-358">An issue using the mouse scroll wheel on an in-active window with a chart sheet was fixed.</span></span>
- <span data-ttu-id="94c5b-359">已解決將試算表匯入 SharePoint 時發生「未預期錯誤」訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-359">A problem that caused an "Unexpected Error" message to appear when importing a spreadsheet in SharePoint has been resolved.</span></span>
- <span data-ttu-id="94c5b-360">已解決在開啟包含使用其規則名稱和自訂檢視的條件式格式設定的活頁簿的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-360">A problem that opening a workbook containing conditional formatting that uses a Name for its rule and a custom view is applied has been resolved.</span></span>
- <span data-ttu-id="94c5b-361">巨集用於驗證資料的公式若長於 255 個字元可能會產生執行階段錯誤。</span><span class="sxs-lookup"><span data-stu-id="94c5b-361">Macros using data validation with formulas longer than 255 characters may have produced run-time errors.</span></span> <span data-ttu-id="94c5b-362">此問題現已修正。</span><span class="sxs-lookup"><span data-stu-id="94c5b-362">This issue has now been corrected.</span></span>
- <span data-ttu-id="94c5b-363">發生問題，導致包含連結至其他活頁簿之樞紐分析表的檔案載入速度緩慢。</span><span class="sxs-lookup"><span data-stu-id="94c5b-363">A problem which caused files containing PivotTables linked to other workbooks to load slowly.</span></span> <span data-ttu-id="94c5b-364">此問題已解決。</span><span class="sxs-lookup"><span data-stu-id="94c5b-364">This issue has been resolved.</span></span>
- <span data-ttu-id="94c5b-365">開啟 HTML 檔案時收到「檔案格式與副檔名不符」錯誤的問題已解決。</span><span class="sxs-lookup"><span data-stu-id="94c5b-365">An issue with opening HTML files and receiving a "file format and extension do not match" error has been resolved.</span></span>
- <span data-ttu-id="94c5b-366">已進行變更，以解決在非使用中視窗滾動滑鼠滾輪的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-366">A change has been made to resolve issues with mouse-wheel scrolling on inactive windows.</span></span>
- <span data-ttu-id="94c5b-367">解決了當儲存格中包含的公式結尾為定義的名稱時，按下 Tab 鍵不會移至下一個儲存格的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-367">Resolved an issue where pressing the Tab key would not move to the next cell when in a cell containing a formula ending in a defined name.</span></span>
- <span data-ttu-id="94c5b-368">解決了儲存格格式設定導致檔案大小不必要地增加的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-368">Resolved an issue where cell formatting was causing the file size to grow unnecessarily.</span></span>
- <span data-ttu-id="94c5b-369">解決了在活頁簿之間剪下並貼上樞紐分析表可能導致貼上資料，但沒有您正與其共同作業的其他人的樞紐分析表的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-369">Resolved an issue where cutting and pasting a PivotTable between workbooks may result in the data being pasted, without a PivotTable for others you are collaborating with.</span></span>


### <a name="outlook-non-security-updates"></a><span data-ttu-id="94c5b-370">Outlook：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-370">Outlook: Non-security updates</span></span>

- <span data-ttu-id="94c5b-371">已解決在「群組依據」中新增第二個條件後，客戶的工作似乎會消失的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-371">Addressed an issue that caused customers to see their tasks seem to disappear when adding a 2nd condition to "Group by".</span></span>
- <span data-ttu-id="94c5b-372">解決了造成客戶無法編輯所移轉項目上某些欄位的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-372">Addresses an issue that caused customers to be unable to edit some fields on items that had been migrated.</span></span>
- <span data-ttu-id="94c5b-373">已修正當系統工作列停留在螢幕左側或頂部時，視窗無法顯示在正確位置的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-373">Fixed an issue in which windows would not appear in the correct location when the system task bar was kept at the left or top of the screen.</span></span>
- <span data-ttu-id="94c5b-374">解決了在連絡人卡片上載入圖片時導致客戶遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-374">Addresses an issue that caused customers to experience a crash when loading pictures on the contact card.</span></span>
- <span data-ttu-id="94c5b-375">解決了導致某些客戶在啟動 Office 應用程式時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-375">Addresses an issue that caused some customers to experience crashes when starting office applications.</span></span>
- <span data-ttu-id="94c5b-376">已修正當系統工作列停留在螢幕左側或頂部時，視窗無法顯示在正確位置的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-376">Fixed an issue in which windows would not appear in the correct location when the system task bar was kept at the left or top of the screen.</span></span>
- <span data-ttu-id="94c5b-377">解決了造成客戶無法編輯所移轉項目上某些欄位的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-377">Addresses an issue that caused customers to be unable to edit some fields on items that had been migrated.</span></span>


### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="94c5b-378">PowerPoint：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-378">PowerPoint: Non-Security updates</span></span>

- <span data-ttu-id="94c5b-379">已修正在罕見的情況下，PowerPoint 停止將使用者的變更上傳到雲端的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-379">Fixed an issue that PowerPoint stops uploading user changes to the cloud in rare situations.</span></span>


### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="94c5b-380">商務用 Skype：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-380">Skype for Business: Non-security updates</span></span>

- <span data-ttu-id="94c5b-381">已修正 Lync (商務用 Skype) 中的問題，在其中，當任何線上會議具有 7 位以上參與者時，會議視窗可能會消失。</span><span class="sxs-lookup"><span data-stu-id="94c5b-381">Fixed an issue in Lync (Skype for Business) where for any online meeting with more 7+ participants, the meeting window can disappear.</span></span>
- <span data-ttu-id="94c5b-382">使用用來登入其他 Office 應用程式的認證來登入商務用 Skype。</span><span class="sxs-lookup"><span data-stu-id="94c5b-382">Sign into Skype for Business with credentials used to sign into another Office application.</span></span>
- <span data-ttu-id="94c5b-383">隨著共用電腦啟用安裝時，正確地啟用商務用 Skype 應用程式。</span><span class="sxs-lookup"><span data-stu-id="94c5b-383">Properly activate the Skype for Business app when installed with shared computer activation.</span></span>


### <a name="visio-non-security-updates"></a><span data-ttu-id="94c5b-384">Visio：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-384">Visio: Non-security updates</span></span>

- <span data-ttu-id="94c5b-385">已修正第三方解決方案利用停用動態 DPI 功能來擴充 Visio，造成損毀視窗階層問題的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-385">Fixed an issue which was causing broken window hierarchy issues for 3rd party solutions extending Visio by disabling Dynamic DPI feature.</span></span>


### <a name="word-non-security-updates"></a><span data-ttu-id="94c5b-386">Word：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-386">Word: Non-security updates</span></span>

 - <span data-ttu-id="94c5b-387">已修正以下問題：共用目前正在共同作業的文件時，會產生具 .asd 副檔名的附件。</span><span class="sxs-lookup"><span data-stu-id="94c5b-387">Fixed when sharing a document which is currently being collaborated upon the document produces attachment with .asd extension.</span></span>
 - <span data-ttu-id="94c5b-388">已修正註解被歸因於隨機作者的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-388">Fixed an issue with comments get attributed to random authors.</span></span>
 - <span data-ttu-id="94c5b-389">已修正在簽出文件時，簽章遭到移除的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-389">Fixed an issue in the remove signature when checking out a document.</span></span>
 - <span data-ttu-id="94c5b-390">已修正編輯 SharePoint 新增的相關人員可能會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-390">Fixed an issue where editing a Related Person added by SharePoint could crash.</span></span>
 - <span data-ttu-id="94c5b-391">已修正 Word 啟動時出現的「無法載入資源」對話方塊。</span><span class="sxs-lookup"><span data-stu-id="94c5b-391">Fixed where the "Failed to load resource" dialog when Word launches.</span></span>
 - <span data-ttu-id="94c5b-392">如果檔案以唯讀模式開啟，然後您從 [資訊] 窗格中按一下 [另存新檔]，修正問題以便顯示儲存 UI。</span><span class="sxs-lookup"><span data-stu-id="94c5b-392">If a file is opened in read-only mode and you click 'Save As' from the 'Info' pane, fixes issue so that the save UI is displayed.</span></span>


### <a name="office-suite-non-security-updates"></a><span data-ttu-id="94c5b-393">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-393">Office Suite: Non-security updates</span></span>

 - <span data-ttu-id="94c5b-394">此修正在「復原」動作後，VBA 報告不正確的圖案填滿狀態的錯誤。</span><span class="sxs-lookup"><span data-stu-id="94c5b-394">This fixed a bug in VBA reporting incorrect shape fill state after an "undo" action.</span></span>
 - <span data-ttu-id="94c5b-395">此修正程式可修正無法將檔案儲存到 Apache WebDAV 資料夾的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-395">This is a fix for an issue where files cannot be saved to Apache WebDAV folders.</span></span>
 - <span data-ttu-id="94c5b-396">修正 Office 在客戶開啟某些雲端儲存檔案時會意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-396">Fixes an issue where Office closes abruptly when customers open some cloud-stored files.</span></span>
 - <span data-ttu-id="94c5b-397">修正不正確地將平假名和漢字中的日本新年號 "Reiwa" (令和) 識別為拼字錯誤或不合文法的運算式的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-397">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>
 - <span data-ttu-id="94c5b-398">已修正似乎為 Windows 10 上的許多使用者清除最近使用的檔案清單的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-398">Fixed an issue where the recent files list appeared to have been cleared for many users on Windows 10.</span></span>
 - <span data-ttu-id="94c5b-399">已修正即使已有系統管理員觸發的更新進行中，仍導致使用者看到 Office 更新業務列的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-399">Fixed an issue that caused an end-user to see an Office Update business bar, even though there is an Admin-triggered update in progress.</span></span>
 - <span data-ttu-id="94c5b-400">已修正與間歇性的空白登入提示相關的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-400">Fixed an issues related to intermittent blank sign-in prompts.</span></span>
 - <span data-ttu-id="94c5b-401">已修正部分 Office 更新未使用傳遞最佳化對等快取的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-401">Fixed an issue where parts of an Office update do not use Delivery Optimization peer caching.</span></span> [<span data-ttu-id="94c5b-402">深入了解</span><span class="sxs-lookup"><span data-stu-id="94c5b-402">Learn more</span></span>]("https://docs.microsoft.com/en-us/windows/deployment/update/waas-delivery-optimization)
- <span data-ttu-id="94c5b-403">修正如果使用 Office 部署工具安裝 Office，並發生大小寫不相符時，可能導致移除產品或未啟用的錯誤。</span><span class="sxs-lookup"><span data-stu-id="94c5b-403">Fix to a bug that could lead to products being removed or not activated if Office was installed using the Office Deployment Tool and there was a case mis-match.</span></span>
- <span data-ttu-id="94c5b-404">已修正導致 Windows 10 (版本 1803 或更高版本) 裝置上出現過多登入提示的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-404">Fixed an issue which was causing excessive sign-in prompts on Windows 10 (version 1803 or later) devices.</span></span>
- <span data-ttu-id="94c5b-405">已修正下載連結圖片時，造成懸置的迴歸。</span><span class="sxs-lookup"><span data-stu-id="94c5b-405">Fixed regression that causes hangs when downloading linked pictures.</span></span>
- <span data-ttu-id="94c5b-406">已修正在 Word、Excel、PowerPoint 貼上大型 EMF 檔案的模糊問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-406">Fixed blurriness of large EMF files pasted in Word, Excel, PowerPoint.</span></span>
- <span data-ttu-id="94c5b-407">已修正版本歷程記錄剖析邏輯時，在少數情況下導致文件以唯讀模式開啟的錯誤 (bug)。</span><span class="sxs-lookup"><span data-stu-id="94c5b-407">Fixed the bug in version history parsing logic that in few cases caused the documents to be opened in read-only.</span></span>


## <a name="version-1808-july-09"></a><span data-ttu-id="94c5b-408">版本 1808：7 月 9 日</span><span class="sxs-lookup"><span data-stu-id="94c5b-408">Version 1808: July 09</span></span>
<span data-ttu-id="94c5b-409">*版本 1808 (組建 10730.20360)*</span><span class="sxs-lookup"><span data-stu-id="94c5b-409">*Version 1808 (Build 10730.20360)*</span></span>
<br/><span data-ttu-id="94c5b-410">安全性更新列於[此處](https://docs.microsoft.com/zh-TW/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="94c5b-410">Security updates listed [here](https://docs.microsoft.com/zh-TW/officeupdates/office365-proplus-security-updates)</span></span>


### <a name="word-non-security-updates"></a><span data-ttu-id="94c5b-411">Word：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-411">Word: Non-Security updates</span></span>

- <span data-ttu-id="94c5b-412">已改善啟用快速組件文件摘要資訊時的效能。</span><span class="sxs-lookup"><span data-stu-id="94c5b-412">Improved performance when enabling Quick Parts for Document properties.</span></span>
- <span data-ttu-id="94c5b-413">已修正在簽出檔案時，簽章遭到移除的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-413">Fixed an issue about remove signature when checking out a file.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="94c5b-414">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-414">Office Suite: Non-Security updates</span></span>

- <span data-ttu-id="94c5b-415">已修正會影響在虛擬化 Windows 上執行 Office 應用程式的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-415">Fixed an issue affecting Office applications running on virtualized Windows.</span></span>


## <a name="version-1803-july-09"></a><span data-ttu-id="94c5b-416">版本 1803：7 月 9 日</span><span class="sxs-lookup"><span data-stu-id="94c5b-416">Version 1803: July 09</span></span>
<span data-ttu-id="94c5b-417">*版本 1803 (組建 9126.2428)*</span><span class="sxs-lookup"><span data-stu-id="94c5b-417">*Version 1803 (Build 9126.2428)*</span></span>
<br/><span data-ttu-id="94c5b-418">安全性更新列於[此處](https://docs.microsoft.com/zh-TW/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="94c5b-418">Security updates listed [here](https://docs.microsoft.com/zh-TW/officeupdates/office365-proplus-security-updates)</span></span>


## <a name="version-1808-june-11"></a><span data-ttu-id="94c5b-419">版本 1808：6 月 11 日</span><span class="sxs-lookup"><span data-stu-id="94c5b-419">Version 1808: June 11</span></span>
<span data-ttu-id="94c5b-420">*版本 1808 (組建 10730.20348)*</span><span class="sxs-lookup"><span data-stu-id="94c5b-420">*Version 1808 (Build 10730.20348)*</span></span>
<br/><span data-ttu-id="94c5b-421">安全性更新列於[此處](https://docs.microsoft.com/zh-TW/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="94c5b-421">Security updates listed [here](https://docs.microsoft.com/zh-TW/officeupdates/office365-proplus-security-updates)</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="94c5b-422">Word：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-422">Word: Non-Security updates</span></span>
 - <span data-ttu-id="94c5b-423">已修正在簽出檔案時，簽章遭到移除的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-423">Fixed an issue about remove signature when checking out a file.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="94c5b-424">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-424">Office Suite: Non-security updates</span></span>
 - <span data-ttu-id="94c5b-425">已修正在虛擬化 Windows 上執行 Office 應用程式可能會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-425">Fixed an issue that could crash Office applications running on virtualized Windows.</span></span>

## <a name="version-1803-june-11"></a><span data-ttu-id="94c5b-426">版本 1803：6 月 11 日</span><span class="sxs-lookup"><span data-stu-id="94c5b-426">Version 1803: June 11</span></span>
<span data-ttu-id="94c5b-427">*版本 1803 (組建 9126.2388)*</span><span class="sxs-lookup"><span data-stu-id="94c5b-427">*Version 1803 (Build 9126.2388)*</span></span>
<br/><span data-ttu-id="94c5b-428">安全性更新列於[此處](https://docs.microsoft.com/zh-TW/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="94c5b-428">Security updates listed [here](https://docs.microsoft.com/zh-TW/officeupdates/office365-proplus-security-updates)</span></span> 

## <a name="version-1808-may-14"></a><span data-ttu-id="94c5b-429">版本 1808：5 月 14 日</span><span class="sxs-lookup"><span data-stu-id="94c5b-429">Version 1808: May 14</span></span>
<span data-ttu-id="94c5b-430">*版本 1808 (組建 10730.20344)*</span><span class="sxs-lookup"><span data-stu-id="94c5b-430">*Version 1808 (Build 10730.20344)*</span></span>   

### <a name="outlook-non-security-updates"></a><span data-ttu-id="94c5b-431">Outlook：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-431">Outlook: Non-security updates</span></span>
 - <span data-ttu-id="94c5b-432">解決了造成客戶無法編輯所移轉項目上某些欄位的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-432">Addresses an issue that caused customers to be unable to edit some fields on items that had been migrated.</span></span>

### <a name="visio-non-security-updates"></a><span data-ttu-id="94c5b-433">Visio：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-433">Visio: Non-security updates</span></span>
 - <span data-ttu-id="94c5b-434">已修正第三方解決方案利用停用動態 DPI 功能來擴充 Visio，造成損毀視窗階層問題的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-434">Fixed an issue which was causing broken window hierarchy issues for 3rd party solutions extending Visio by disabling Dynamic DPI feature.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="94c5b-435">Word：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-435">Word: Non-Security updates</span></span>
 - <span data-ttu-id="94c5b-436">已修正編輯 SharePoint 新增的相關人員可能會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-436">Fixed an issue where editing a Related Person added by SharePoint could crash.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="94c5b-437">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-437">Office Suite: Non-security updates</span></span>
 - <span data-ttu-id="94c5b-438">修正不正確地將平假名和漢字中的日本新年號 "Reiwa" (令和) 識別為拼字錯誤或不合文法的運算式的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-438">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>
  
## <a name="version-1803-may-14"></a><span data-ttu-id="94c5b-439">版本 1803：5 月 14 日</span><span class="sxs-lookup"><span data-stu-id="94c5b-439">Version 1803: May 14</span></span>
<span data-ttu-id="94c5b-440">*版本 1803 (組建 9126.2387)*</span><span class="sxs-lookup"><span data-stu-id="94c5b-440">*Version 1803 (Build 9126.2387)*</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="94c5b-441">Outlook：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-441">Outlook: Non-security updates</span></span>
 - <span data-ttu-id="94c5b-442">解決了造成客戶無法編輯所移轉項目上某些欄位的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-442">Addresses an issue that caused customers to be unable to edit some fields on items that had been migrated.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="94c5b-443">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-443">Office Suite: Non-security updates</span></span>
 - <span data-ttu-id="94c5b-444">修正不正確地將平假名和漢字中的日本新年號 "Reiwa" (令和) 識別為拼字錯誤或不合文法的運算式的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-444">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

## <a name="version-1808-april-9"></a><span data-ttu-id="94c5b-445">版本 1808：4 月 9 日</span><span class="sxs-lookup"><span data-stu-id="94c5b-445">Version 1808: April 9</span></span>
<span data-ttu-id="94c5b-446">*版本 1808 (組建 10730.20334)*</span><span class="sxs-lookup"><span data-stu-id="94c5b-446">*Version 1808 (Build 10730.20334)*</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="94c5b-447">商務用 Skype：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-447">Skype for Business: Non-security updates</span></span>
- <span data-ttu-id="94c5b-448">已修正 Lync (商務用 Skype) 中的問題，在其中，當任何線上會議具有 7 位以上參與者時，會議視窗可能會消失。</span><span class="sxs-lookup"><span data-stu-id="94c5b-448">Fixed an issue in Lync (Skype for Business) where for any online meeting with more 7+ participants, the meeting window can disappear.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="94c5b-449">Word：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-449">Word: Non-Security updates</span></span>

- <span data-ttu-id="94c5b-450">已修正使用者可在 IE 或 Edge 以匿名方式開啟文件的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-450">Fixed an issue where the user can open documents anonymously in IE or Edge.</span></span>
- <span data-ttu-id="94c5b-451">已修正問題：將文字強調顯示色彩格式設定套用至任何 Word 文檔頁首/頁腳 PAGE 和/或 NUMPAGES 功能變數後，將欄位呈現為黑色而不是套用的文字強調顯示色彩。</span><span class="sxs-lookup"><span data-stu-id="94c5b-451">Fixed an issue where text highlight color formatting applied to any Word document header/footer PAGE and/or NUMPAGES field renders the field as black instead of the applied text highlight color.</span></span>
- <span data-ttu-id="94c5b-452">我們為日本新時代新增了 Word 日語明信片精靈增益集的支援。</span><span class="sxs-lookup"><span data-stu-id="94c5b-452">We added support to Word Japanese postcard wizard add-in for the Japanese new era.</span></span> 

## <a name="version-1803-april-9"></a><span data-ttu-id="94c5b-453">版本 1803：4 月 9 日</span><span class="sxs-lookup"><span data-stu-id="94c5b-453">Version 1803: April 9</span></span>
- <span data-ttu-id="94c5b-454">安全性更新列於[此處](office365-proplus-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="94c5b-454">Security updates listed [here](office365-proplus-security-updates.md)</span></span>

## <a name="version-1808-march-12"></a><span data-ttu-id="94c5b-455">版本 1808：3 月 12 日</span><span class="sxs-lookup"><span data-stu-id="94c5b-455">Version 1808: March 12</span></span>
<span data-ttu-id="94c5b-456">*版本 1808 (組建 10730.20304)*</span><span class="sxs-lookup"><span data-stu-id="94c5b-456">*Version 1808 (Build 10730.20304)*</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="94c5b-457">Word：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-457">Word: Non-Security updates</span></span>

- <span data-ttu-id="94c5b-458">修正 VBA 傳回不正確頁碼的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-458">Fixed an issue when VBA returns incorrect page number.</span></span>
- <span data-ttu-id="94c5b-459">改善儲存在本機檔案的時間。</span><span class="sxs-lookup"><span data-stu-id="94c5b-459">Improve time to save on local Word file.</span></span> 

### <a name="outlook-non-security-updates"></a><span data-ttu-id="94c5b-460">Outlook：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-460">Outlook: Non-Security updates</span></span>

- <span data-ttu-id="94c5b-461">提供 regkey 以停用 Office 365 [郵件加密] 功能表的 [僅加密] 選項。</span><span class="sxs-lookup"><span data-stu-id="94c5b-461">Provided regkey to disable the "Encrypt Only" option in the Office 365 Message Encryption menu.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="94c5b-462">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-462">Office Suite: Non-Security updates</span></span>

- <span data-ttu-id="94c5b-463">已修正 Office 更新在嘗試下載時有時會卡住的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-463">Fixed an issue where Office update may get stuck for some time trying to download.</span></span>

## <a name="version-1803-march-12"></a><span data-ttu-id="94c5b-464">版本 1803：3 月 12 日</span><span class="sxs-lookup"><span data-stu-id="94c5b-464">Version 1803: March 12</span></span> 
- <span data-ttu-id="94c5b-465">安全性更新列於[此處](office365-proplus-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="94c5b-465">Security updates listed [here](office365-proplus-security-updates.md)</span></span>

## <a name="version-1808-february-12"></a><span data-ttu-id="94c5b-466">版本 1808：2 月 12 日</span><span class="sxs-lookup"><span data-stu-id="94c5b-466">Version 1808: February 12</span></span>
<span data-ttu-id="94c5b-467">*版本 1808 (組建 10730.20280)*</span><span class="sxs-lookup"><span data-stu-id="94c5b-467">*Version 1808 (Build 10730.20280)*</span></span>

### <a name="access-non-security-updates"></a><span data-ttu-id="94c5b-468">Access：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-468">Access: Non-Security updates</span></span> 

- <span data-ttu-id="94c5b-469">這個更新將新日本時代的支援新增至 Access。</span><span class="sxs-lookup"><span data-stu-id="94c5b-469">This update adds support for new Japanese eras to Access.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="94c5b-470">Outlook：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-470">Outlook: Non-Security updates</span></span> 

- <span data-ttu-id="94c5b-p156">解決嘗試管理規則時，因參照不再存在資料夾的規則而導致使用者 1. 看見錯誤訊息以及 2. 看見用戶端規則無法執行的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-p156">Addresses an issue that caused users with rules that refer to a folder that no longer exist to 1. See an error when trying to manage rules and 2. See client-side rules fail to run.</span></span>
- <span data-ttu-id="94c5b-474">解決因快取的委派信箱導致使用者在無法預測的時間間隔遇到頻繁的當機問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-474">Addresses an issue that caused users with cached delegate mailboxes to encounter frequent hangs at unpredictable intervals.</span></span>
- <span data-ttu-id="94c5b-475">解決因為會議結束時間設定為隔天午夜而導致全天會議在某些檢視中比原訂多橫跨一天的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-475">Addresses an issue that caused All Day Meetings to appear to span one more day than intended in some views due to the end time of the meeting being set to midnight of the following day.</span></span>
- <span data-ttu-id="94c5b-476">修正參考日本時代建立新約會或會議時發生的當機問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-476">Fixed a hang when creating new appointments or meetings that reference Japanese eras.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="94c5b-477">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-477">Office Suite: Non-security updates</span></span>

- <span data-ttu-id="94c5b-478">修正使用 [O365 Office 集中式部署](https://docs.microsoft.com/zh-TW/office/dev/add-ins/publish/centralized-deployment)部署的增益集發生凍結且無法使用的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-478">Fixed issue where Add-ins, deployed using [O365 Office centralized deployment](https://docs.microsoft.com/zh-TW/office/dev/add-ins/publish/centralized-deployment), were freezing and unusable.</span></span>


## <a name="version-1803-february-12"></a><span data-ttu-id="94c5b-479">版本 1803：2 月 12 日</span><span class="sxs-lookup"><span data-stu-id="94c5b-479">Version 1803: February 12</span></span>
<span data-ttu-id="94c5b-480">*版本 1803 (組建 9126.2356)*</span><span class="sxs-lookup"><span data-stu-id="94c5b-480">*Version 1803 (Build 9126.2356)*</span></span>

<span data-ttu-id="94c5b-481">*這是從 2018 年 7 月以來提供的半年通道版本。這個版本會繼續受到支援並會收到安全性更新，直到 2019 年 9 月為止。不過，目前已提供新的半年通道版本 — 版本 1808 (組建 10730.20280) — 其中包含了新功能、安全性更新和非安全性更新。*</span><span class="sxs-lookup"><span data-stu-id="94c5b-481">*This is the Semi-Annual Channel release that's been available since July 2018. It will continue to be supported and receive security updates until September 2019. But, a new Semi-Annual Channel release is now available — Version 1808 (Build 10730.20280) — which contains new features, security updates, and non-security updates.*</span></span>

### <a name="access-non-security-updates"></a><span data-ttu-id="94c5b-482">Access：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-482">Access: Non-Security updates</span></span> 

- <span data-ttu-id="94c5b-483">這個更新將新日本時代的支援新增至 Access。</span><span class="sxs-lookup"><span data-stu-id="94c5b-483">This update adds support for new Japanese eras to Access.</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="94c5b-484">Excel：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-484">Excel: Non-Security updates</span></span> 

- <span data-ttu-id="94c5b-485">這個更新將新日本時代的支援新增至 Excel。</span><span class="sxs-lookup"><span data-stu-id="94c5b-485">This update adds support for new Japanese eras to Excel.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="94c5b-486">Outlook：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-486">Outlook: Non-Security updates</span></span>

- <span data-ttu-id="94c5b-487">修正參考日本時代建立新約會或會議時發生的當機問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-487">Fixed a hang when creating new appointments or meetings that reference Japanese eras.</span></span>

### <a name="project-non-security-updates"></a><span data-ttu-id="94c5b-488">Project：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-488">Project: Non-Security updates</span></span>
- <span data-ttu-id="94c5b-489">這個更新將新日本時代的支援新增至 Project</span><span class="sxs-lookup"><span data-stu-id="94c5b-489">This update adds support for new Japanese eras to Project</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="94c5b-490">Word：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-490">Word: Non-Security updates</span></span>

- <span data-ttu-id="94c5b-491">這個更新將新日本時代的支援新增至 Word。</span><span class="sxs-lookup"><span data-stu-id="94c5b-491">This update adds support for new Japanese eras to Word.</span></span>

### <a name="visio-non-security-updates"></a><span data-ttu-id="94c5b-492">Visio：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-492">Visio: Non-Security updates</span></span>

- <span data-ttu-id="94c5b-493">這個更新將新日本時代的支援新增至 Visio。</span><span class="sxs-lookup"><span data-stu-id="94c5b-493">This update adds support for new Japanese eras to Visio.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="94c5b-494">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-494">Office Suite: Non-security updates</span></span>

- <span data-ttu-id="94c5b-495">修正使用 [O365 Office 集中式部署](https://docs.microsoft.com/zh-TW/office/dev/add-ins/publish/centralized-deployment)部署的增益集發生凍結且無法使用的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-495">Fixed issue where Add-ins, deployed using [O365 Office centralized deployment](https://docs.microsoft.com/zh-TW/office/dev/add-ins/publish/centralized-deployment), were freezing and unusable.</span></span>

## <a name="version-1708-february-12"></a><span data-ttu-id="94c5b-496">版本 1708：2 月 12 日</span><span class="sxs-lookup"><span data-stu-id="94c5b-496">Version 1708: February 12</span></span>
<span data-ttu-id="94c5b-497">*版本 1708 (組建 8431.2372)*</span><span class="sxs-lookup"><span data-stu-id="94c5b-497">*Version 1708 (Build 8431.2372)*</span></span>

<span data-ttu-id="94c5b-498">*這是自從 2018 年 1 月以來提供的半年通道版本。它會繼續受到支援並接收安全性更新，直到 2019 年 3 月為止。不過，目前已提供新的半年通道版本 — 版本 1808 (組建 10730.20280) — 其中包含了新功能、安全性更新和非安全性更新。*</span><span class="sxs-lookup"><span data-stu-id="94c5b-498">*This is the Semi-Annual Channel release that's been available since January 2018. It will continue to be supported and receive security updates until March 2019. But, a new Semi-Annual Channel release is now available — Version 1808 (Build 10730.20280) — which contains new features, security updates, and non-security updates.*</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="94c5b-499">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-499">Office Suite: Non-security updates</span></span>

- <span data-ttu-id="94c5b-500">修正使用 [O365 Office 集中式部署](https://docs.microsoft.com/zh-TW/office/dev/add-ins/publish/centralized-deployment)部署的增益集發生凍結且無法使用的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-500">Fixed issue where Add-ins, deployed using [O365 Office centralized deployment](https://docs.microsoft.com/zh-TW/office/dev/add-ins/publish/centralized-deployment), were freezing and unusable.</span></span>


## <a name="version-1808-january-8"></a><span data-ttu-id="94c5b-501">版本 1808：1 月 8 日</span><span class="sxs-lookup"><span data-stu-id="94c5b-501">Version 1808: January 8</span></span>
<span data-ttu-id="94c5b-502">版本 1808 (組建 10730.20264)\*\*</span><span class="sxs-lookup"><span data-stu-id="94c5b-502">*Version 1808 (Build 10730.20264)*</span></span>

### <a name="access-feature-updates"></a><span data-ttu-id="94c5b-503">Access：功能更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-503">Access: Feature Updates</span></span>

 - <span data-ttu-id="94c5b-p157">**使用新圖表以視覺化方式呈現資料：** 從 11 個圖表中選擇，並將其中一個新增至您的表單和報告，更有效地以視覺化方式呈現資料並進行明智的決策。[深入了解](https://support.office.com/article/1a463106-65d0-4dbb-9d66-4ecb737ea7f7)</span><span class="sxs-lookup"><span data-stu-id="94c5b-p157">**Visualize data with new charts:** Choose from 11 charts and add one to your forms and reports to better visualize the data and make informed decisions. [Learn more](https://support.office.com/article/1a463106-65d0-4dbb-9d66-4ecb737ea7f7)</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="94c5b-506">Excel：功能更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-506">Excel: Feature updates</span></span>
 - <span data-ttu-id="94c5b-p158">**共同作業編輯：** 在您的活頁簿中與他人同時作業。[深入了解](https://support.office.com/article/7152aa8b-b791-414c-a3bb-3024e46fb104)</span><span class="sxs-lookup"><span data-stu-id="94c5b-p158">**Collaborative editing:** Work with others at the same time in your workbook. [Learn more](https://support.office.com/article/7152aa8b-b791-414c-a3bb-3024e46fb104)</span></span>
 - <span data-ttu-id="94c5b-p159">**現在已預設啟用雲端檔案的自動儲存：** 這項改變代表使用者再也無須擔心儲存在 OneDrive 或 SharePoint Online 上的文件變更會遺失。變更將會自動儲存在雲端，使用者再也不需要按下 Ctrl + S 鍵或 [儲存] 按鈕。但使用者必須了解這項動作改變，以防意外變更文件。使用者可以用畫面頂端的 [自動儲存] 切換開關來停用自動儲存。建議您通知使用者這項近期改變，並提供有關這項 Office 365 全新功能的使用教學。[深入了解自動儲存](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) 以及[深入了解 IT 系統管理員須知的自動儲存相關內容](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)</span><span class="sxs-lookup"><span data-stu-id="94c5b-p159">**AutoSave for cloud files is now enabled by default:** This change means users won’t have to worry about losing their changes in documents stored on OneDrive or SharePoint Online. Changes will be saved in the cloud automatically, and users will no longer have to explicitly press Ctrl + S or the Save button. However, they will have to understand this change in behavior so they don’t make accidental changes to documents. Note that users can turn off AutoSave using the AutoSave toggle at the top of the screen. We recommend that you notify your users about this upcoming change and educate them about how to best take advantage of this new feature in Office 365. [Learn more about AutoSave](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) and [Learn more about what IT admins should know about AutoSave](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)</span></span>
- <span data-ttu-id="94c5b-p160">**改善儲存格和資料編輯列編輯：** 您現在可以使用 CTRL + A 來選取儲存格或資料編輯列中的文字。另外也改善了 Emoji 和其他複雜字元的支援。[深入了解](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)</span><span class="sxs-lookup"><span data-stu-id="94c5b-p160">**Improved cell and formula bar editing:** You can now use CTRL+A to select text in a cell or the formula bar. There's also improved support for emojis and other complex characters. [Learn more](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)</span></span>
- <span data-ttu-id="94c5b-p161">**改善協助工具檢查程式︰** 協助工具檢查程式已更新，現可支援國際標準並提供讓活頁簿更易於使用的建議。[深入了解](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span><span class="sxs-lookup"><span data-stu-id="94c5b-p161">**Accessibility Checker improvements:** The Accessibility Checker has updated support for international standards and recommendations to make your workbooks more accessible. [Learn more](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span></span>
- <span data-ttu-id="94c5b-p162">**避免不想要的編輯：** 設定您的活頁簿開啟為唯讀，以避免意外變更。移至 [檔案 > 資訊 > 保護活頁簿 > 一律以唯讀開啟]</span><span class="sxs-lookup"><span data-stu-id="94c5b-p162">**Avoid unwanted edits:** Set your workbooks to open as read-only to prevent accidental changes. Go to File > Info > Protect Workbook > Always Open Read-Only</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="94c5b-522">Excel：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-522">Excel: Non-Security updates</span></span> 

- <span data-ttu-id="94c5b-523">已修正此問題：在共同撰寫工作階段中，當另一位使用者對交叉分析篩選器中的資料套用資料行篩選後，交叉分析篩選器未正確更新。</span><span class="sxs-lookup"><span data-stu-id="94c5b-523">Fixed an issue in coauthoring sessions where a slicer is not properly updated after another user applies a column filter to the data in that slicer.</span></span>
- <span data-ttu-id="94c5b-524">已修正此問題：在共同撰寫工作階段中，當其中一位使用者清除交叉分析篩選器的說明文字時，會導致共同撰寫工作階段中的另一位使用者遇到 Excel 損毀。</span><span class="sxs-lookup"><span data-stu-id="94c5b-524">Fixed an issue in a coauthoring session where one of the users clears the caption for a slicer and this causes another user in the coauthoring session to experience an Excel crash.</span></span>
- <span data-ttu-id="94c5b-525">已修正此問題：建立多個繫結至相同資料行的表格交叉分析篩選器時可能發生損毀，並刪除該行資料。</span><span class="sxs-lookup"><span data-stu-id="94c5b-525">Fixed possible crash when creating multiple table slicers bound to the same column of data and then deleting that column of data.</span></span>
- <span data-ttu-id="94c5b-526">已修正此問題：關閉自動調整欄寬的選項後，Excel 有時在重新整理儲存格中有換行文字的已篩選查詢資料表時會發生損毀。</span><span class="sxs-lookup"><span data-stu-id="94c5b-526">Fixed an issue where Excel would sometimes crash while refreshing a filtered query table that contains wrapped text in cells when the option to automatically adjust column widths was off.</span></span>
- <span data-ttu-id="94c5b-527">已修正此問題：儲存在 Excel 2007 中的交叉分析篩選器若在較新版的 Excel 中開啟，且交叉分析篩選器中顯示的項目有變更，則可能觸發損毀。</span><span class="sxs-lookup"><span data-stu-id="94c5b-527">Fixed an issue where slicers saved in Excel 2007 can trigger a crash when opened in newer versions of Excel if the number of items shown in the slicer changes.</span></span>
- <span data-ttu-id="94c5b-528">引入 [取得診斷] 按鈕的支援，可簡化支援要求的調查。</span><span class="sxs-lookup"><span data-stu-id="94c5b-528">Introduces support for the Get Diagnostics button to simplify the investigation of support requests.</span></span>
- <span data-ttu-id="94c5b-529">修正了在某些組建/版本中未出現 Power Pivot 的錯誤。</span><span class="sxs-lookup"><span data-stu-id="94c5b-529">Fixed a bug where Power Pivot did not appear in some builds/versions.</span></span>
- <span data-ttu-id="94c5b-530">修正以下的 Excel 問題：當使用者將滑鼠停留在具有多個定義名稱的活頁簿中的格式選項上，Excel 可能無反應，而且即使在格式選項中停用了即時預覽，Excel 也可能在快速分析工具中無反應。</span><span class="sxs-lookup"><span data-stu-id="94c5b-530">Fixed the issue in Excel wherein Excel may become unresponsive when the user hovers over formatting options in a workbook with many defined names, and where Excel may become unresponsive in the Quick Analysis tool even when Live Preview was disabled in options.</span></span>
- <span data-ttu-id="94c5b-p163">我們目前正在調查，當 Excel 應用程式視窗從一個桌面移動到另一個桌面時，效能降低的問題。 同時，如果您發現到這種效能降低的問題，請試試在「檔案選項」對話方塊裡的「一般」索引標籤中將「當使用多個顯示器時」設定為「相容性最佳化」。</span><span class="sxs-lookup"><span data-stu-id="94c5b-p163">We are currently investigating slow performance when moving the Excel Application Window from one desktop to another. In the meantime, if you do notice this slowness then a work around to consider is to select "Optimize for compatibility" for "When using multiple displays" in the "General" tab in the File Options dialog.</span></span>
- <span data-ttu-id="94c5b-533">已修正此問題：從原儲存格變更圖表來源資料時 Excel 可能會損毀。</span><span class="sxs-lookup"><span data-stu-id="94c5b-533">Fixed an issue where Excel may crash when changing a chart's source data from its original set of cells.</span></span>
- <span data-ttu-id="94c5b-534">已修正此問題：即使已設定 FullCalcOnLoad 屬性，開啟時也可能不會算。</span><span class="sxs-lookup"><span data-stu-id="94c5b-534">Fixed an issue where recalculation may not happen on open even if the FullCalcOnLoad property is set.</span></span>  
- <span data-ttu-id="94c5b-535">已修正此問題：在日期儲存格格式使用日本紀元日曆時顯示錯誤年份。</span><span class="sxs-lookup"><span data-stu-id="94c5b-535">Fixed an issue where the wrong year is shown when Japanese Era calendar is used in date cell format.</span></span>
- <span data-ttu-id="94c5b-p164">當資料匯入 Excel 資料模型中，負值或零的輸入值會造成錯誤。此修正會將此類的值匯入為零。</span><span class="sxs-lookup"><span data-stu-id="94c5b-p164">When importing data into the Excel Data Model, incoming values of negative zero would result in an error.  The fix imports such values as zero.</span></span>
- <span data-ttu-id="94c5b-538">已修正此問題：Excel 樞紐分析表中的群組 (或取消群組) 作業有時候會觸發當機。</span><span class="sxs-lookup"><span data-stu-id="94c5b-538">Fixed an issue where a group (or ungroup) operation in an Excel PivotTable could sometimes trigger a crash.</span></span>
- <span data-ttu-id="94c5b-539">已修正此問題：在圖表上動作可能會造成 Excel 當機。</span><span class="sxs-lookup"><span data-stu-id="94c5b-539">Fixed an issue where charting actions could cause Excel to crash.</span></span>
- <span data-ttu-id="94c5b-540">已修正此問題：部分使用者不小心停用 Power View 增益集。</span><span class="sxs-lookup"><span data-stu-id="94c5b-540">Fixed an issue where the Power View add-in is inadvertently disabled for some users.</span></span>
- <span data-ttu-id="94c5b-541">已修正此問題：在文件復原期間建立的暫時自動復原檔案永遠不會清除。</span><span class="sxs-lookup"><span data-stu-id="94c5b-541">Fixed an issue where temporary auto-recovery files created during document recovery are never cleaned up.</span></span>
- <span data-ttu-id="94c5b-542">已修正此問題：在嘗試與受保護 Workbook 中的文字檔建立新連線時，收到「Workbook 受到保護，且無法變更」錯誤訊息。</span><span class="sxs-lookup"><span data-stu-id="94c5b-542">Fixed an issue where attempting to make a new connection to a text file in a protected workbook results in getting a "Workbook is protected and cannot be changed" error message.</span></span>
- <span data-ttu-id="94c5b-543">已修正此問題：快速列印附加至 Outlook 電子郵件的 Excel 活頁簿可能會列印不出來。</span><span class="sxs-lookup"><span data-stu-id="94c5b-543">Fixed an issue where Quick Print of an Excel workbook attached to an Outlook email may not print.</span></span>
- <span data-ttu-id="94c5b-544">已修正此問題：按一下超連結可能會造成 Excel 當機。</span><span class="sxs-lookup"><span data-stu-id="94c5b-544">Fixed an issue where clicking on a hyperlink may cause Excel to crash.</span></span>
- <span data-ttu-id="94c5b-545">已修正此問題：使用 cube 函式會造成 Excel 當機。</span><span class="sxs-lookup"><span data-stu-id="94c5b-545">Fixed an issue where using cube functions causes Excel to crash.</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="94c5b-546">Outlook：功能更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-546">Outlook: Feature updates</span></span>
 - <span data-ttu-id="94c5b-p165">**改善協助工具檢查程式︰** 協助工具檢查程式已更新對國際標準與建議的支援，以使您的郵件更易於存取。[深入了解](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span><span class="sxs-lookup"><span data-stu-id="94c5b-p165">**Accessibility Checker improvements:** The Accessibility Checker has updated support for international standards and recommendations to make your messages more accessible. [Learn more](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span></span>
 - <span data-ttu-id="94c5b-p166">**從設定檔選擇器管理設定檔：** 如果您習慣在 Outlook 啟動時使用設定檔選擇器，現在不用去 [控制台] 也能進行變更。建立及刪除設定檔、變更設定，全都能在 [設定檔選擇器] 一次搞定。</span><span class="sxs-lookup"><span data-stu-id="94c5b-p166">**Manage Profiles from the Profile Picker:** If you use the Profile Picker when Outlook starts up, you can now make changes without going to the control panel. Create and delete profiles, change settings, all from the Profile Picker.</span></span>
- <span data-ttu-id="94c5b-551">**內建的協助工具：** 在圖片上新增替代文字，即可讓每個人存取相關訊息。</span><span class="sxs-lookup"><span data-stu-id="94c5b-551">**Accessibility built right in:** Make your messages accessible to everyone by adding descriptive alt text to your images.</span></span>
- <span data-ttu-id="94c5b-p167">**Outlook 增益集警告：** 有時 Outlook COM 增益集會發生問題，讓其餘 Outlook 功能變慢。這些問題可能是因為以下的事件延遲：在 Outlook 資料夾之間進行切換、新的電子郵件送達、開啟行事曆項目等等。當這類問題發生時，Outlook 會在通知列中顯示警告。</span><span class="sxs-lookup"><span data-stu-id="94c5b-p167">**Outlook add-in warnings:** Occasionally an Outlook COM add-in can encounter problems that slows down the rest of Outlook. These problems could be due to latency of events such as switching between Outlook folders, arrival of new emails, opening Calendar items, etc. When such issues arise, Outlook will display a warning in the notification bar.</span></span>
- <span data-ttu-id="94c5b-554">**知道誰是與會者：** 即使您不是召集人，也可以看到其他人對於會議邀請的回應。</span><span class="sxs-lookup"><span data-stu-id="94c5b-554">**Know who you'll be meeting with:** You can see other people's responses to a meeting request, even if you aren't the organizer.</span></span>
- <span data-ttu-id="94c5b-p168">**絕不錯過任何提醒：** 將提醒設定為在使用中視窗上彈出。若未設定，Outlook 會在工作列中閃爍，以引起您的注意。[深入了解](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)</span><span class="sxs-lookup"><span data-stu-id="94c5b-p168">**Never miss a reminder:** Set reminders to pop up over windows you're working in. Otherwise, Outlook will blink in the taskbar to get your attention. [Learn more](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)</span></span>
- <span data-ttu-id="94c5b-p169">**將刪除的郵件標示為已讀取：** 您現在可以將任何已刪除的郵件標示為已讀取。請移至 [檔案] \> [選項] \> [郵件] \> [其他] 來選擇使用。</span><span class="sxs-lookup"><span data-stu-id="94c5b-p169">**Mark deleted items as read:** You can now set any message that you delete as read. Opt in by going to File \> Options \> Mail \> Other.</span></span>
- <span data-ttu-id="94c5b-p170">**檢視三個時區：** 需要跨時區排程會議嗎？將多個時區新增至行事曆，方便檢視所有人員的空檔，並挑選出所有人都可行的時間。[深入了解](https://support.office.com/article/5ab3e10e-5a6c-46af-ab48-156fedf70c04)</span><span class="sxs-lookup"><span data-stu-id="94c5b-p170">**View three time zones:** Need to schedule a meeting across time zones? Add multiple time zones to your calendar to easily see everyone's availability and pick a time that works for all. [Learn more](https://support.office.com/article/5ab3e10e-5a6c-46af-ab48-156fedf70c04)</span></span>
- <span data-ttu-id="94c5b-p171">**改善建立群組的使用者體驗：** 我們已改善建立群組的使用者體驗，讓它更具現代化。[深入了解](https://support.office.com/article/04d0c9cf-6864-423c-a380-4fa858f27102)</span><span class="sxs-lookup"><span data-stu-id="94c5b-p171">**Refined user experience for creating a group:** We have refined the user experience for the create group to make it look more modern and clutter-free. [Learn more](https://support.office.com/article/04d0c9cf-6864-423c-a380-4fa858f27102)</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="94c5b-565">Outlook：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-565">Outlook: Non-Security updates</span></span>
- <span data-ttu-id="94c5b-566">修正導致使用者遇到行事曆同步處理錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-566">Fixed an issue that caused users to experience calendar synchronization errors.</span></span>
- <span data-ttu-id="94c5b-567">已修正使用者啟動 [管理規則及通知] 對話方塊時看到錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-567">Fixed an issue that caused users to see an error when launching the "Manage Rules and Alerts" dialog.</span></span>
- <span data-ttu-id="94c5b-568">已修正此問題：使用者使用計量付費連線時，無法透過 DirectAccess 連線到他們的信箱。</span><span class="sxs-lookup"><span data-stu-id="94c5b-568">Fixed an issue that caused users to be unable to connect to their mailboxes over DirectAccess when using a metered connection.</span></span>
- <span data-ttu-id="94c5b-569">已修正此問題：使用者會看到儲存在公用資料夾中的可用文件錯誤地在「受保護的檢視」中開啟。</span><span class="sxs-lookup"><span data-stu-id="94c5b-569">Fixed an issue that caused users to see free docs stored in Public Folders erroneously open in "Protected View".</span></span>
- <span data-ttu-id="94c5b-570">已修正此問題：使用者轉寄具有內嵌附件的項目時，會看到非預期的附件。</span><span class="sxs-lookup"><span data-stu-id="94c5b-570">Fixed an issue that caused users to see unexpected attachments when forwarding items with inline attachments.</span></span>
- <span data-ttu-id="94c5b-571">已修正 OFT 檔案在作為附件傳送後，呈現效果不良的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-571">Fixed an issue that caused OFT files to render poorly after being sent as an attachment.</span></span>
- <span data-ttu-id="94c5b-572">已修正此問題：部分增益集使用者在將會議新增至共用行事曆時遇到損毀問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-572">Fixed an issue that caused some add in users to experience crashes when adding a meeting to a shared calendar.</span></span>
- <span data-ttu-id="94c5b-573">已修正此問題：使用者開啟交談歷程記錄資料夾時遇到當機問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-573">Fixed an issue that caused users to experience hangs when opening the Conversation History folder.</span></span>
- <span data-ttu-id="94c5b-574">已修正此問題：如果將系統語言切換為日文，並在載入 Outlook 時嘗試輸入 VBA IDE 時，畫面會凍結。</span><span class="sxs-lookup"><span data-stu-id="94c5b-574">Fixed an issue where if you switch the system language to Japanese and attempt to type Japanese characters into the VBA IDE when loaded within Outlook, it freezes.</span></span>
- <span data-ttu-id="94c5b-575">已修正此問題：切換到 [寄件匣] 或 [寄件備份] 資料夾造成 Outlook 損毀。</span><span class="sxs-lookup"><span data-stu-id="94c5b-575">Fixed an issue where switching to the Outbox or Sent Items folder causes Outlook to crash.</span></span>
- <span data-ttu-id="94c5b-576">已修正此問題：會議內文或附件變更時所有出席者收到會議更新，而非傳送會議更新給選擇性的出席者。</span><span class="sxs-lookup"><span data-stu-id="94c5b-576">Fixed an issue where all attendees receive meeting updates when the meeting body or attachments change, instead of sending a meeting update to the attendees being optional.</span></span>
- <span data-ttu-id="94c5b-577">已修正此問題：因為使用者代理程式字串中的變更，造成使用者無法連線到 EWS 及 REST 端點。</span><span class="sxs-lookup"><span data-stu-id="94c5b-577">Fixed an issue that causes users to be unable to connect to EWS and REST endpoints because of a change in the User-Agent string.</span></span>
- <span data-ttu-id="94c5b-578">已修正此問題：出席者的會議位置更新是顯示舊的位置而不是新的位置。</span><span class="sxs-lookup"><span data-stu-id="94c5b-578">Fixed an issue where a meeting location update to attendees shows the old location instead of the new location.</span></span>
- <span data-ttu-id="94c5b-579">已修正此問題：使用者在預覽讀取窗格中的附件時，會看到錯誤。</span><span class="sxs-lookup"><span data-stu-id="94c5b-579">Fixed an issue where the user sees an error when previewing an attachment in the reading pane.</span></span>
- <span data-ttu-id="94c5b-580">已修正此問題：當使用者在撰寫電子郵件時，解決電子郵件地址的顯示名稱會使 Outlook 當機。</span><span class="sxs-lookup"><span data-stu-id="94c5b-580">Fixed an issue where Outlook crashes when resolving display names to email addresses when the user is composing an email.</span></span>
- <span data-ttu-id="94c5b-581">已修正此問題：有些使用者未收到其租用戶系統管理員已啟用的支援功能。</span><span class="sxs-lookup"><span data-stu-id="94c5b-581">Fixed an issue where some users don't receive support features that have been enabled by their tenant admin.</span></span>

### <a name="onenote-non-security-updates"></a><span data-ttu-id="94c5b-582">OneNote：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-582">OneNote: Non-security updates</span></span> 

- <span data-ttu-id="94c5b-583">修正了可能發生的穩定性問題，包括同步處理和瀏覽至刪除的部分。</span><span class="sxs-lookup"><span data-stu-id="94c5b-583">Fixed a stability issue that can occur involving sync and navigating to a deleted section.</span></span>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="94c5b-584">PowerPoint：功能更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-584">PowerPoint: Feature updates</span></span> 
- <span data-ttu-id="94c5b-p172">**現在已預設啟用雲端檔案的自動儲存：** 這項改變代表使用者再也無須擔心儲存在 OneDrive 或 SharePoint Online 上的文件變更會遺失。變更將會自動儲存在雲端，使用者再也不需要按下 Ctrl + S 鍵或 [儲存] 按鈕。但使用者必須了解這項動作改變，以防意外變更簡報。使用者可以用畫面頂端的 [自動儲存] 切換開關來停用自動儲存。建議您通知使用者這項近期改變，並提供有關這項 Office 365 全新功能的使用教學。[深入了解自動儲存](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) 以及[深入了解 IT 系統管理員須知的自動儲存相關內容](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)</span><span class="sxs-lookup"><span data-stu-id="94c5b-p172">**AutoSave for cloud files is now enabled by default:** This change means users won’t have to worry about losing their changes in documents stored on OneDrive or SharePoint Online. Changes will be saved in the cloud automatically, and users will no longer have to explicitly press Ctrl + S or the Save button. However, they will have to understand this change in behavior so they don’t make accidental changes to presentations. Note that users can turn off AutoSave using the AutoSave toggle at the top of the screen. We recommend that you notify your users about this upcoming change and educate them about how to best take advantage of this new feature in Office 365. [Learn more about AutoSave](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) and [Learn more about what IT admins should know about AutoSave](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)</span></span>
- <span data-ttu-id="94c5b-p173">**改善儲存格和資料編輯列編輯：** 您現在可以使用 CTRL + A 來選取儲存格或資料編輯列中的文字。另外也改善了 Emoji 和其他複雜字元的支援。[深入了解](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)</span><span class="sxs-lookup"><span data-stu-id="94c5b-p173">**Improved cell and formula bar editing:** You can now use CTRL+A to select text in a cell or the formula bar. There's also improved support for emojis and other complex characters. [Learn more](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)</span></span>
- <span data-ttu-id="94c5b-p174">**轉換筆跡：** 擷取草草寫下的筆記和繪圖，並將其轉換為可供閱讀的文字和簡潔的圖形，以建立精美的簡報。 [深入了解](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)</span><span class="sxs-lookup"><span data-stu-id="94c5b-p174">**Convert your ink:** Take scribbled notes and drawings, and convert them into readable text and crisp shapes to create a polished presentation. [Learn more](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)</span></span>
- <span data-ttu-id="94c5b-p175">**改善 SVG 支援：** 您可以將已套用篩選的 SVG 插入。[深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="94c5b-p175">**Improved SVG support:** You can insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>
- <span data-ttu-id="94c5b-p176">**使用手寫筆為投影片撰寫標題：** 使用手寫筆輸入標題，並觀看 PowerPoint 將它轉換成文字。[深入了解](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="94c5b-p176">**Title your slides with a pen:** Use your pen to ink in a title, and watch PowerPoint convert it to text. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>
- <span data-ttu-id="94c5b-p177">**避免不想要的編輯：** 設定您的活頁簿開啟為唯讀，以避免意外變更。移至 [檔案 > 資訊 > 保護活頁簿 > 一律以唯讀開啟]</span><span class="sxs-lookup"><span data-stu-id="94c5b-p177">**Avoid unwanted edits:** Set your workbooks to open as read-only to prevent accidental changes. Go to File > Info > Protect Workbook > Always Open Read-Only</span></span>
- <span data-ttu-id="94c5b-p178">**改善協助工具檢查程式︰** 協助工具檢查程式已更新對國際標準與建議的支援，以使您的簡報更易於存取。[深入了解](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span><span class="sxs-lookup"><span data-stu-id="94c5b-p178">**Accessibility Checker improvements:** The Accessibility Checker has updated support for international standards and recommendations to make your presentations more accessible. [Learn more](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span></span>


### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="94c5b-604">PowerPoint：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-604">PowerPoint: Non-Security updates</span></span>
- <span data-ttu-id="94c5b-605">修正了使用 ActiveX 內容來儲存文件時，可能造成文件損毀的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-605">Fixed an issue of potential file corruptions when saving files with ActiveX content.</span></span>
- <span data-ttu-id="94c5b-606">已修正此問題：表格以粗框線錯誤編譯。</span><span class="sxs-lookup"><span data-stu-id="94c5b-606">Fixed an issue where tables are rendered incorrectly with thick borders.</span></span>
- <span data-ttu-id="94c5b-607">已修正此問題：當變更 Shape.Visibile 屬性時可能會造成當機。</span><span class="sxs-lookup"><span data-stu-id="94c5b-607">Fixed an issue where a potential crash could occur when changing the Shape.Visibile property.</span></span>
- <span data-ttu-id="94c5b-608">已修正此問題：共同撰寫文件中的變更無法合併。</span><span class="sxs-lookup"><span data-stu-id="94c5b-608">Fixed an issue where changes in co-authored documents fail to merge.</span></span>
- <span data-ttu-id="94c5b-609">已修正此問題：包含 ActiveX 控制項的文件會造成共同撰寫失敗。</span><span class="sxs-lookup"><span data-stu-id="94c5b-609">Fixed an issue where documents containing ActiveX controls would cause co-authoring to fail.</span></span>
- <span data-ttu-id="94c5b-610">已修正此問題：在圖形中使用拼字校正時會造成 PowerPoint 當機。</span><span class="sxs-lookup"><span data-stu-id="94c5b-610">Fixed an issue where spelling correction in shapes causes PowerPoint to crash.</span></span>
- <span data-ttu-id="94c5b-611">已修正此問題：PowerPoint 在從 SharePoint Online 開啟檔案時損毀。</span><span class="sxs-lookup"><span data-stu-id="94c5b-611">Fixed an issue where PowerPoint crashes when opening a file from SharePoint Online.</span></span>
- <span data-ttu-id="94c5b-612">已修正此問題：開啟 [自動儲存] 時，[復原] 窗格不正確地顯示。</span><span class="sxs-lookup"><span data-stu-id="94c5b-612">Fixed an issue where the Recovery Pane incorrectly appears when AutoSave is on.</span></span>
- <span data-ttu-id="94c5b-613">已修正此問題：未顯示登入，使得使用者無法存取檔案。</span><span class="sxs-lookup"><span data-stu-id="94c5b-613">Fixed an issue where sign-in isn't shown preventing a user from accessing a file.</span></span>
- <span data-ttu-id="94c5b-614">已修正此問題：多個使用者在相同簡報上共同撰寫會導致投影片母片不正確重複。</span><span class="sxs-lookup"><span data-stu-id="94c5b-614">Fixed an issue where multiple users co-authoring on the same presentation results in an incorrect duplication of slides masters.</span></span>
- <span data-ttu-id="94c5b-615">已修正此問題：將儲存在 OneDrive 中的檔案開啟時，結束受保護的檢視時會導致 PowerPoint 當機。</span><span class="sxs-lookup"><span data-stu-id="94c5b-615">Fixed an issue where opening a file saved on OneDrive results in PowerPoint crashing when exiting Protected View.</span></span>

### <a name="project-feature-updates"></a><span data-ttu-id="94c5b-616">Project：功能更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-616">Project: Feature updates</span></span> 
- <span data-ttu-id="94c5b-617">**短期衝刺管理：** 快速新增、 更新或刪除敏捷短期衝刺。</span><span class="sxs-lookup"><span data-stu-id="94c5b-617">**Sprint management:** Quickly add, update, or delete agile sprints.</span></span>
- <span data-ttu-id="94c5b-618">**工作面板篩選：** 篩選重要資源或摘要任務，以簡化您的工作面板。</span><span class="sxs-lookup"><span data-stu-id="94c5b-618">**Task board filtering:** Streamline your task boards by filtering on key resources or summary tasks.</span></span>
- <span data-ttu-id="94c5b-619">**從工作面板設定完成百分比：** 針對每個資料行選擇完成百分比，然後透過拖放更新工作完成度。</span><span class="sxs-lookup"><span data-stu-id="94c5b-619">**Set percent complete from a task board:** Choose a percent complete for each column, and then update task completion with drag-and-drop.</span></span>
- <span data-ttu-id="94c5b-620">**短期衝刺瀏覽：** 從某個短期衝刺檢視切換到另一個檢視，並快速地在短期衝刺之間移動工作。</span><span class="sxs-lookup"><span data-stu-id="94c5b-620">**Sprint navigation:** Switch from one sprint view to another, and quickly move tasks between sprints.</span></span>
- <span data-ttu-id="94c5b-p179">**管理短期衝刺的全新方法：** 採取敏捷方式來使用工作面板。隨著專案的發展，請移至 [管理短期衝刺] 來新增或移除短期衝刺。</span><span class="sxs-lookup"><span data-stu-id="94c5b-p179">**A new way to manage sprints:** Take an agile approach to working with Task Boards. Go to Manage Sprints to add and remove sprints as your project evolves.</span></span>
- <span data-ttu-id="94c5b-p180">**使用最近的儲存位置保持組織：** 專案會保存您已儲存其他專案位置的持續清單。當您準備好要儲存專案時，只需選擇其中一個您最近的儲存位置，就能繼續進行您一天的工作。</span><span class="sxs-lookup"><span data-stu-id="94c5b-p180">**Stay organized with Recent save locations:** Project keeps a running list of where you've saved other projects. When you're ready to save your project, just choose one of your Recent save locations and get on with your day.</span></span>

### <a name="project-non-security-updates"></a><span data-ttu-id="94c5b-625">Project：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-625">Project: Non-Security updates</span></span>

- <span data-ttu-id="94c5b-626">已修正在專案中支援新委內瑞拉貨幣的相關問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-626">Fixed an issue around supporting a new Venezuelan currency in Project.</span></span>
- <span data-ttu-id="94c5b-627">已修正此問題：專案若使用連線到外部監視器的介面 Surface 4，可能會停止回應。</span><span class="sxs-lookup"><span data-stu-id="94c5b-627">Fixed an issue where Project may hang when using a Surface 4 that is connected to an external monitor.</span></span>
- <span data-ttu-id="94c5b-628">已修正此問題：將專案儲存為 XML 格式時，專案可能會損毀。</span><span class="sxs-lookup"><span data-stu-id="94c5b-628">Fixed an issue where Project may crash when saving the project to the XML format.</span></span>
- <span data-ttu-id="94c5b-629">已修正此問題：企業資源自訂欄位可能會在編輯資源的行事曆後遭到刪除。</span><span class="sxs-lookup"><span data-stu-id="94c5b-629">Fixed an issue where enterprise resource custom fields may be deleted after editing a resource's calendar.</span></span>
- <span data-ttu-id="94c5b-630">已修正此問題：使用者搜尋韓文的顯示名稱時會遇到損毀問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-630">Fixed an issue that caused users to experience crashes when searching for Korean display names.</span></span>
- <span data-ttu-id="94c5b-631">已修正此問題：當您透過主要專案使用子專案時，系統阻止您儲存子專案。</span><span class="sxs-lookup"><span data-stu-id="94c5b-631">Fixed an issue where you are blocked from saving a sub project when working with them through the context of a master project.</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="94c5b-632">Word：功能更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-632">Word: Feature updates</span></span>
- <span data-ttu-id="94c5b-p181">**現在已預設啟用雲端檔案的自動儲存：** 這項改變代表使用者再也無須擔心儲存在 OneDrive 或 SharePoint Online 上的文件變更會遺失。變更將會自動儲存在雲端，使用者再也不需要按下 Ctrl + S 鍵或 [儲存] 按鈕。但使用者必須了解這項動作改變，以防意外變更簡報。使用者可以用畫面頂端的 [自動儲存] 切換開關來停用自動儲存。建議您通知使用者這項近期改變，並提供有關這項 Office 365 全新功能的使用教學。[深入了解自動儲存](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) 以及[深入了解 IT 系統管理員須知的自動儲存相關內容](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)</span><span class="sxs-lookup"><span data-stu-id="94c5b-p181">**AutoSave for cloud files is now enabled by default:** This change means users won’t have to worry about losing their changes in documents stored on OneDrive or SharePoint Online. Changes will be saved in the cloud automatically, and users will no longer have to explicitly press Ctrl + S or the Save button. However, they will have to understand this change in behavior so they don’t make accidental changes to presentations. Note that users can turn off AutoSave using the AutoSave toggle at the top of the screen. We recommend that you notify your users about this upcoming change and educate them about how to best take advantage of this new feature in Office 365. [Learn more about AutoSave](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) and [Learn more about what IT admins should know about AutoSave](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)</span></span>
- <span data-ttu-id="94c5b-p182">**改善協助工具檢查程式︰** 協助工具檢查程式已更新對國際標準與建議的支援，以使您的文件更易於存取。[深入了解](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span><span class="sxs-lookup"><span data-stu-id="94c5b-p182">**Accessibility Checker improvements:** The Accessibility Checker has updated support for international standards and recommendations to make your documents more accessible. [Learn more](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span></span>
- <span data-ttu-id="94c5b-p183">**改善 SVG 支援：** 您可以將已套用篩選的 SVG 插入。[深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="94c5b-p183">**Improved SVG support:** You can insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="94c5b-643">Word：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-643">Word: Non-Security updates</span></span>
- <span data-ttu-id="94c5b-644">修正造成顯示記憶體不足訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-644">Fix an issue that causes an insufficient memory message to appear.</span></span>
- <span data-ttu-id="94c5b-645">修正了防止部分使用者開啟受 IRM 保護的文件和電子郵件 (由其他組織中的人員與他們共用) 的一些問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-645">Fixed a set of issues that prevented some users from opening IRM-protected documents & emails that were shared with them by people in other organizations.</span></span>
- <span data-ttu-id="94c5b-646">修正一些效能問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-646">Fixed some performance issues.</span></span>
- <span data-ttu-id="94c5b-647">改善開啟效能。</span><span class="sxs-lookup"><span data-stu-id="94c5b-647">Improve open performance.</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="94c5b-648">商務用 Skype：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-648">Skype for Business: Non-security updates</span></span>
- <span data-ttu-id="94c5b-p184">修正與 TLS 1.2 支援相關的問題。(附註：這是 4 月 10 日的資訊曾經提及的同一個修正。但在這裡，它變成 9 月彙總套件的一部分，並且再被提及一次。)</span><span class="sxs-lookup"><span data-stu-id="94c5b-p184">Fix an issue related to TLS 1.2 support. (Note: This is the same fix that was mentioned in the April 10 notes and is mentioned here again as part of the September rollup.)</span></span>
- <span data-ttu-id="94c5b-651">修正此問題：在會議中以選取 [Skype 通話] 的方式新增使用者會產生錯誤。</span><span class="sxs-lookup"><span data-stu-id="94c5b-651">Fix an issue where adding users by selecting 'Skype Call' in a meeting causes an error.</span></span>
- <span data-ttu-id="94c5b-652">如果已將 Skype 會議室新增為位置，且會議已包含小組會議座標，請移除要求使用者將 Skype 座標新增至會議的提示。</span><span class="sxs-lookup"><span data-stu-id="94c5b-652">Remove prompt asking user to add Skype coordinates to a meeting, if a Skype Room is added as the location and the meeting already contains Teams meeting coordinates.</span></span>
- <span data-ttu-id="94c5b-653">修正此問題：即使 UseLocationForE911Only 設定為 true，也會填入位置。</span><span class="sxs-lookup"><span data-stu-id="94c5b-653">Fix an issue where location is populated even when UseLocationForE911Only is set to true.</span></span>
- <span data-ttu-id="94c5b-654">修正此問題：使用名冊中的「使用會議中心呼叫」選項來邀請使用者時，商務用 Skype 會當機。</span><span class="sxs-lookup"><span data-stu-id="94c5b-654">Fix an issue where Skype for Business hangs when using the "call using conference center" option to invite users from the roster.</span></span>
- <span data-ttu-id="94c5b-655">修正此問題：建立商務用 Skype 會議時，在終端機伺服器上運行的Outlook 會凍結。</span><span class="sxs-lookup"><span data-stu-id="94c5b-655">Fix an issue where Outlook running on terminal server freezes while creating a Skype for Business meeting.</span></span>
- <span data-ttu-id="94c5b-656">將 EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket 的預設值變更為 TRUE。</span><span class="sxs-lookup"><span data-stu-id="94c5b-656">Change the default value of EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket to TRUE.</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="94c5b-657">Visio：功能更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-657">Visio: Feature updates</span></span>
- <span data-ttu-id="94c5b-658">**讓您的圖表和來源能保持同步：** 當您在 Visio 中編輯 [資料視覺化工具] 圖表時，可以選擇用最新的圖表內容來更新連結的 Excel 來源資料。</span><span class="sxs-lookup"><span data-stu-id="94c5b-658">**Keep your diagram and source in sync:** When you edit a Data Visualizer diagram in Visio, you have the option to update the linked Excel source data with the latest diagram content.</span></span>
- <span data-ttu-id="94c5b-659">**資料視覺化工具稽核範本：** 從 Excel 匯入內容，並建立金融交易、庫存管理等稽核圖表。</span><span class="sxs-lookup"><span data-stu-id="94c5b-659">**Data Visualizer audit template:** Import content from Excel and create audit diagrams for financial transactions, inventory management, and more.</span></span>
- <span data-ttu-id="94c5b-660">**入門圖表：** 組織圖、腦力激盪和 SDL 範本有新的入門圖表可讓您快速啟動並執行。</span><span class="sxs-lookup"><span data-stu-id="94c5b-660">**Starter diagrams:** The Organization Chart, Brainstorming, and SDL templates have new starter diagrams to get you up and running quickly.</span></span>
- <span data-ttu-id="94c5b-p185">**從 Visio 圖形建立 Word 文件：** 自動將圖表內容 (包括圖形和中繼資料) 新增至 Word 文件。然後自訂文件以建立程序指導方針和操作手冊。[深入了解](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)</span><span class="sxs-lookup"><span data-stu-id="94c5b-p185">**Build a Word document out of Visio shapes** Automatically add diagram content, including shapes and metadata, to a Word document. Then customize the document to create process guidelines and operation manuals. [Learn more](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)</span></span>

### <a name="office-suite-security-update"></a><span data-ttu-id="94c5b-664">Office 套件：安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-664">Office Suite: Security update</span></span>

- <span data-ttu-id="94c5b-p186">**基於安全原因已封鎖 Flash、Silverlight、Shockwave 控制在 Office 中啟動：** 基於安全原因，Windows 上新組建的 Microsoft Office for Office 365 會封鎖 Flash、Silverlight、Shockwave 控制的啟動。請看[這裡](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Blocking-Flash-Shockwave-Silverlight-controls-from-activating-in/ba-p/191729)和[這裡](https://support.office.com/en-us/article/flash-silverlight-and-shockwave-controls-blocked-in-office-2016-55738f12-a01d-420e-a533-7cef1ff6aeb1?ui=en-US&rs=en-US&ad=US)深入了解。</span><span class="sxs-lookup"><span data-stu-id="94c5b-p186">**Flash, Silverlight and Shockwave controls blocked from activating in Office for security reasons:** For security reasons new builds of Microsoft Office for Office 365 on Windows block activation of Flash, Silverlight, and Shockwave controls. Learn more [here](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Blocking-Flash-Shockwave-Silverlight-controls-from-activating-in/ba-p/191729) and [here](https://support.office.com/en-us/article/flash-silverlight-and-shockwave-controls-blocked-in-office-2016-55738f12-a01d-420e-a533-7cef1ff6aeb1?ui=en-US&rs=en-US&ad=US).</span></span>
 
### <a name="office-suite-non-security-updates"></a><span data-ttu-id="94c5b-667">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-667">Office Suite: Non-Security updates</span></span>
- <span data-ttu-id="94c5b-668">已修正導致更新安裝在特定情況下需要很長時間的問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-668">Fixed an issue that caused update install to take a long time in certain scenarios.</span></span>
- <span data-ttu-id="94c5b-669">修正此問題：開啟應用程式時，使用者可能會看到以安全模式啟動的訊息，然後應用程式無法開啟。</span><span class="sxs-lookup"><span data-stu-id="94c5b-669">Fix an issue where, when opening an application, the user might see a message about launching in Safe mode and then the application fails to open.</span></span>
- <span data-ttu-id="94c5b-670">修正一些效能問題。</span><span class="sxs-lookup"><span data-stu-id="94c5b-670">Fixed some performance issues.</span></span>


## <a name="version-1803-january-8"></a><span data-ttu-id="94c5b-671">版本 1803：1 月 8 日</span><span class="sxs-lookup"><span data-stu-id="94c5b-671">Version 1803: January 8</span></span>
<span data-ttu-id="94c5b-672">版本 1803 (組建 9126.2351)\*\*</span><span class="sxs-lookup"><span data-stu-id="94c5b-672">*Version 1803 (Build 9126.2351)*</span></span>

<span data-ttu-id="94c5b-673">這是從 2018 年 7 月以來提供的半年通道版本。這個版本會繼續受到支援並會收到安全性更新，直到 2019 年 9 月為止。不過，目前已提供新的半年通道版本 — 版本 1808 — 其中包含了新功能、安全性更新和非安全性更新。\*\*</span><span class="sxs-lookup"><span data-stu-id="94c5b-673">*This is the Semi-Annual Channel release that's been available since July 2018. It will continue to be supported and receive security updates until September 2019. But, a new Semi-Annual Channel release is now available — Version 1808 — which contains new features, security updates, and non-security updates.*</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="94c5b-674">PowerPoint：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="94c5b-674">PowerPoint: Non-Security updates</span></span>
- <span data-ttu-id="94c5b-675">修正問題，確保 LinkedIn 選項在 各 Office 應用程式之間的一致性。</span><span class="sxs-lookup"><span data-stu-id="94c5b-675">Fixed an issue to ensure feature parity of the LinkedIn option between Office applications.</span></span>


> [!NOTE]
> <span data-ttu-id="94c5b-676">如果您需要關於使用 Office 的問題協助，建議您將問題張貼在 [Microsoft Answers 論壇](https://answers.microsoft.com/)或[技術社群](https://techcommunity.microsoft.com/)，或連絡[支援](https://support.microsoft.com/contactus)。</span><span class="sxs-lookup"><span data-stu-id="94c5b-676">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>