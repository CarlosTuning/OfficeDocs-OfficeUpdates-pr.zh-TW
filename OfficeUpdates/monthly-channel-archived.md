---
title: 每月通道版本的封存版本資訊
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為 IT 專業人員提供 Office 365 專業增強版每月通道版本的版本資訊
ms.openlocfilehash: f6cbb8db94f2f3a92ebc98f7c0a45b660f4ca815
ms.sourcegitcommit: 596cdb3423140df0324a952157fbc39ebedc12b9
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/07/2021
ms.locfileid: "52278030"
---
# <a name="archived-release-notes-for-monthly-channel"></a><span data-ttu-id="21411-103">每月通道的封存版本資訊</span><span class="sxs-lookup"><span data-stu-id="21411-103">Archived Release notes for Monthly Channel</span></span>
<span data-ttu-id="21411-104">這些版本資訊可提供 Office 365 專業增強版、Visio Pro for Office 365、Project Online 電腦版用戶端以及 Office 365 商務版的每月通道更新所含新功能和非安全性更新的相關資訊。</span><span class="sxs-lookup"><span data-stu-id="21411-104">These release notes provide information about new features and non-security updates that are included in Monthly Channel updates to Office 365 ProPlus, Visio Pro for Office 365, Project Online Desktop Client and Office 365 Business.</span></span>

 > [!NOTE]
>- <span data-ttu-id="21411-105">我們通常會在一段時間每個月推出功能 (有時甚至推出修正程式)。</span><span class="sxs-lookup"><span data-stu-id="21411-105">We often roll out features (and sometimes even fixes) to Monthly over a period of time.</span></span>  <span data-ttu-id="21411-106">如果您現在沒有看到如下所述的項目，您可以預期它近期會推出。</span><span class="sxs-lookup"><span data-stu-id="21411-106">If you don’t see something described below right away, you can expect it soon.</span></span> [<span data-ttu-id="21411-107">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-107">Learn more</span></span>](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2011-december-21"></a><span data-ttu-id="21411-109">版本 2011：12 月 21 日</span><span class="sxs-lookup"><span data-stu-id="21411-109">Version 2011: December 21</span></span>
<span data-ttu-id="21411-110">*版本 2011 (組建 13426.20404)*</span><span class="sxs-lookup"><span data-stu-id="21411-110">*Version 2011 (Build 13426.20404)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-112">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-112">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="21411-113">Excel</span><span class="sxs-lookup"><span data-stu-id="21411-113">Excel</span></span>

- <span data-ttu-id="21411-114">修正了以下問題：Excel 錯誤地顯示檔案新版本可用的訊息列，並強制使用者將變更儲存到活頁簿的副本中或捨棄變更。</span><span class="sxs-lookup"><span data-stu-id="21411-114">Fixed an issue where Excel would incorrectly show a message bar that a new version of the file is available and force the user to save their changes in a copy of the workbook or discard their changes.</span></span>


- <span data-ttu-id="21411-115">修正當開啟含有 Excel 4.0 巨集的 Excel 增益集檔案時，Excel 可能會在不提示的情況下停用巨集的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-115">Fixed an issue where Excel may leave macros disabled without prompting when opening an Excel Add-in file containing Excel 4.0 Macros.</span></span>


### <a name="office-suite"></a><span data-ttu-id="21411-116">Office 套件</span><span class="sxs-lookup"><span data-stu-id="21411-116">Office Suite</span></span>

- <span data-ttu-id="21411-117">修正當快取中的 URL 與 OneDrive 中的 URL 不相符時，檔案將被開啟為 NOT SyncBacked 的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-117">Fixed an issue of file would be opened as NOT SyncBacked when url from cache and url from OneDrive does NOT match.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2011-december-08"></a><span data-ttu-id="21411-119">版本2011：12月 08 日</span><span class="sxs-lookup"><span data-stu-id="21411-119">Version 2011: December 08</span></span>
<span data-ttu-id="21411-120">*版本 2011 (組建 13426.20332)*</span><span class="sxs-lookup"><span data-stu-id="21411-120">*Version 2011 (Build 13426.20332)*</span></span>

<span data-ttu-id="21411-121">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="21411-121">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-123">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-123">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="21411-124">Office 套件</span><span class="sxs-lookup"><span data-stu-id="21411-124">Office Suite</span></span>

- <span data-ttu-id="21411-125">我們已修正 SaveRequestManagerCam 導致應用程式會關閉，而非回傳錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-125">We fixed an issue where SaveRequestManagerCam was causing the application to close instead of returning an error.</span></span> 




[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2011-december-02"></a><span data-ttu-id="21411-127">版本2011：12 月 02 日</span><span class="sxs-lookup"><span data-stu-id="21411-127">Version 2011: December 02</span></span>
<span data-ttu-id="21411-128">*版本 2011 (組建 13426.20308)*</span><span class="sxs-lookup"><span data-stu-id="21411-128">*Version 2011 (Build 13426.20308)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-130">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-130">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="21411-131">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-131">Outlook</span></span>

- <span data-ttu-id="21411-132">我們已修正會導致某些會議的原始出席者在另一個出席者轉寄會議時收到取消通知的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-132">We fixed an issue that caused the original attendees of some meetings to receive a cancellation when another attendee forwards the meeting.</span></span>


- <span data-ttu-id="21411-133">我們已修正會導致某些使用者未設定一或多個簽章時，在 [簽名] 下拉式清單中看不到任何簽名的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-133">We fixed an issue that caused some users to see no signatures in the signatures drop down despite having one or more signatures configured.</span></span>


### <a name="project"></a><span data-ttu-id="21411-134">Project</span><span class="sxs-lookup"><span data-stu-id="21411-134">Project</span></span>

- <span data-ttu-id="21411-135">已修正如果特定專案在負載的特定部分發生問題，可能會開啟特定專案的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-135">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>


### <a name="office-suite"></a><span data-ttu-id="21411-136">Office 套件</span><span class="sxs-lookup"><span data-stu-id="21411-136">Office Suite</span></span>

- <span data-ttu-id="21411-137">Office 套件已修復此問題：在某些較舊的版本上安裝較新版的 Office 時，可能會造成功能受損 (例如由於遺失登錄專案而無法使用 Power Query)。</span><span class="sxs-lookup"><span data-stu-id="21411-137">Office Suite Fixed an issue where installing a newer version of Office over certain older versions can result in impaired functionality (such as being unable to use Power Query) due to missing registry entries.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2011-november-30"></a><span data-ttu-id="21411-139">版本2011：11 月 30 日</span><span class="sxs-lookup"><span data-stu-id="21411-139">Version 2011: November 30</span></span>
<span data-ttu-id="21411-140">*版本 2011 (組建 13426.20294)*</span><span class="sxs-lookup"><span data-stu-id="21411-140">*Version 2011 (Build 13426.20294)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-142">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-142">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="21411-143">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="21411-143">PowerPoint</span></span>

- <span data-ttu-id="21411-144">修正從 Word 到 PowerPoint 複製/貼上方程式時發生的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-144">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


### <a name="word"></a><span data-ttu-id="21411-145">Word</span><span class="sxs-lookup"><span data-stu-id="21411-145">Word</span></span>

- <span data-ttu-id="21411-146">修正從 Word 到 PowerPoint 複製/貼上方程式時發生的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-146">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


- <span data-ttu-id="21411-147">我們已修正文件樣式會以範本中的其他樣式取代的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-147">We fixed an issue which document styles are replaced with other styles from the template.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2011-november-23"></a><span data-ttu-id="21411-149">版本 2011：11 月 23 日</span><span class="sxs-lookup"><span data-stu-id="21411-149">Version 2011: November 23</span></span>
<span data-ttu-id="21411-150">*版本 2011 (組建 13426.20274)*</span><span class="sxs-lookup"><span data-stu-id="21411-150">*Version 2011 (Build 13426.20274)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="21411-152">功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-152">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="21411-153">Access</span><span class="sxs-lookup"><span data-stu-id="21411-153">Access</span></span>

- <span data-ttu-id="21411-154">**自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。</span><span class="sxs-lookup"><span data-stu-id="21411-154">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="21411-155">移至 [檔案] > [帳戶]，然後在 [Office 佈景主題] 下拉式清單底下，選擇 [使用系統設定]。</span><span class="sxs-lookup"><span data-stu-id="21411-155">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="21411-156">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-156">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="excel"></a><span data-ttu-id="21411-157">Excel</span><span class="sxs-lookup"><span data-stu-id="21411-157">Excel</span></span>

- <span data-ttu-id="21411-158">**SVG 剪貼簿支援：** 您現在可以將 SVG 內容從 Office 貼上協力廠商應用程式。</span><span class="sxs-lookup"><span data-stu-id="21411-158">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="21411-159">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-159">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- <span data-ttu-id="21411-160">**自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。</span><span class="sxs-lookup"><span data-stu-id="21411-160">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="21411-161">移至 [檔案] > [帳戶]，然後在 [Office 佈景主題] 下拉式清單底下，選擇 [使用系統設定]。</span><span class="sxs-lookup"><span data-stu-id="21411-161">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="21411-162">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-162">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

- <span data-ttu-id="21411-163">**在來源查詢之後命名新的工作表：** 將資料載入新工作表時，會根據來源查詢的名稱來為工作表命名。</span><span class="sxs-lookup"><span data-stu-id="21411-163">**Name the new sheet after the source query:** When the data is loaded into the new sheet, the sheet will be named based on the name of the source query.</span></span>

- <span data-ttu-id="21411-164">**使用 [進階對話方塊] 來 [建立資料類型]:** [進階對話方塊] 可讓您手動選取合併您正在建立的 [資料類型] 欄位。</span><span class="sxs-lookup"><span data-stu-id="21411-164">**Use the Advanced Dialog to Create Data Types:** The Advanced Dialog allows you to manually select the columns which combine the Data Type you are creating.</span></span>

### <a name="onenote"></a><span data-ttu-id="21411-165">OneNote</span><span class="sxs-lookup"><span data-stu-id="21411-165">OneNote</span></span>

- <span data-ttu-id="21411-166">**自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。</span><span class="sxs-lookup"><span data-stu-id="21411-166">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="21411-167">移至 [檔案] > [帳戶]，然後在 [Office 佈景主題] 下拉式清單底下，選擇 [使用系統設定]。</span><span class="sxs-lookup"><span data-stu-id="21411-167">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="21411-168">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-168">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="outlook"></a><span data-ttu-id="21411-169">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-169">Outlook</span></span>

- <span data-ttu-id="21411-170">**SVG 剪貼簿支援：** 您現在可以將 SVG 內容從 Office 貼上協力廠商應用程式。</span><span class="sxs-lookup"><span data-stu-id="21411-170">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="21411-171">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-171">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- <span data-ttu-id="21411-172">**自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。</span><span class="sxs-lookup"><span data-stu-id="21411-172">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="21411-173">移至 [檔案] > [Office 帳戶]，然後在 [Office 佈景主題] 下拉式清單底下，選擇 [使用系統設定]。</span><span class="sxs-lookup"><span data-stu-id="21411-173">Go to File > Office Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="21411-174">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-174">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

- <span data-ttu-id="21411-175">**工作的使用者體驗更新：** 工作項目的視覺效果更新。</span><span class="sxs-lookup"><span data-stu-id="21411-175">**User Experience Updates for Tasks:** A visual refresh of task items.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="21411-176">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="21411-176">PowerPoint</span></span>

- <span data-ttu-id="21411-177">**SVG 剪貼簿支援：** 您現在可以將 SVG 內容從 Office 貼上協力廠商應用程式。</span><span class="sxs-lookup"><span data-stu-id="21411-177">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="21411-178">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-178">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)<br /><span data-ttu-id="21411-179">在[部落格文章](https://insider.office.com/zh-TW/blog/svg-content-office-third-party-apps)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="21411-179">See details in [blog post](https://insider.office.com/zh-TW/blog/svg-content-office-third-party-apps)</span></span>

- <span data-ttu-id="21411-180">**使用透明背景建立 GIF：** 當匯出成動畫 GIF 時，您可以使用新選項讓背景變透明。</span><span class="sxs-lookup"><span data-stu-id="21411-180">**Create GIFs with Transparent Backgrounds:** When exporting to an Animated GIF, a new option will allow you to make the background transparent.</span></span><br /><span data-ttu-id="21411-181">在[部落格文章](https://insider.office.com/zh-TW/blog/export-animated-gifs-transparent-backgrounds)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="21411-181">See details in [blog post](https://insider.office.com/zh-TW/blog/export-animated-gifs-transparent-backgrounds)</span></span>

- <span data-ttu-id="21411-182">**自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。</span><span class="sxs-lookup"><span data-stu-id="21411-182">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="21411-183">移至 [檔案] > [帳戶]，然後在 [Office 佈景主題] 下拉式清單底下，選擇 [使用系統設定]。</span><span class="sxs-lookup"><span data-stu-id="21411-183">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="21411-184">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-184">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

- <span data-ttu-id="21411-185">**匯出一系列的動畫 GIF：** 當匯出成動畫 GIF 時，選取一系列投影片。</span><span class="sxs-lookup"><span data-stu-id="21411-185">**Export animated GIF in a range:** Select a range of slides when exporting to animated GIF.</span></span>

- <span data-ttu-id="21411-186">**影片庫：** 使用可在應用程式內取得的精心製作、免費的影片素材庫來提升您的文件</span><span class="sxs-lookup"><span data-stu-id="21411-186">**Video Library:** Elevate your documents with a library of curated, royalty-free video footage available in-app</span></span>

### <a name="project"></a><span data-ttu-id="21411-187">Project</span><span class="sxs-lookup"><span data-stu-id="21411-187">Project</span></span>

- <span data-ttu-id="21411-188">**自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。</span><span class="sxs-lookup"><span data-stu-id="21411-188">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="21411-189">移至 [檔案] > [帳戶]，然後在 [Office 佈景主題] 下拉式清單底下，選擇 [使用系統設定]。</span><span class="sxs-lookup"><span data-stu-id="21411-189">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="21411-190">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-190">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="publisher"></a><span data-ttu-id="21411-191">Publisher</span><span class="sxs-lookup"><span data-stu-id="21411-191">Publisher</span></span>

- <span data-ttu-id="21411-192">**自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。</span><span class="sxs-lookup"><span data-stu-id="21411-192">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="21411-193">移至 [檔案] > [帳戶]，然後在 [Office 佈景主題] 下拉式清單底下，選擇 [使用系統設定]。</span><span class="sxs-lookup"><span data-stu-id="21411-193">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="21411-194">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-194">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="visio"></a><span data-ttu-id="21411-195">Visio</span><span class="sxs-lookup"><span data-stu-id="21411-195">Visio</span></span>

- <span data-ttu-id="21411-196">**自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。</span><span class="sxs-lookup"><span data-stu-id="21411-196">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="21411-197">移至 [檔案] > [帳戶]，然後在 [Office 佈景主題] 下拉式清單底下，選擇 [使用系統設定]。</span><span class="sxs-lookup"><span data-stu-id="21411-197">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="21411-198">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-198">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="word"></a><span data-ttu-id="21411-199">Word</span><span class="sxs-lookup"><span data-stu-id="21411-199">Word</span></span>

- <span data-ttu-id="21411-200">**SVG 剪貼簿支援：** 您現在可以將 SVG 內容從 Office 貼上協力廠商應用程式。</span><span class="sxs-lookup"><span data-stu-id="21411-200">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="21411-201">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-201">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- <span data-ttu-id="21411-202">**自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。</span><span class="sxs-lookup"><span data-stu-id="21411-202">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="21411-203">移至 [檔案] > [帳戶]，然後在 [Office 佈景主題] 下拉式清單底下，選擇 [使用系統設定]。</span><span class="sxs-lookup"><span data-stu-id="21411-203">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="21411-204">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-204">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-207">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-207">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="21411-208">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-208">Outlook</span></span>

- <span data-ttu-id="21411-209">我們已修正在傳送工作的狀態報告時，造成 [收件者] 欄位為空白的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-209">We fixed an issue that caused the To field to be blank when sending a status report on a task.</span></span>


- <span data-ttu-id="21411-210">我們已修正會導致 MailItem.BeforeAttachmentAdd 事件中斷的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-210">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="21411-211">我們新增了一個 RegKey，可讓客戶停用 IDataObject 操作 (例如，拖曳拖放、剪貼簿) 中附件的 FileTime 包含內容。</span><span class="sxs-lookup"><span data-stu-id="21411-211">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="21411-212">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments。</span><span class="sxs-lookup"><span data-stu-id="21411-212">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span></span> <span data-ttu-id="21411-213">REG_DWORD IncludeFileTimesInDataObject。</span><span class="sxs-lookup"><span data-stu-id="21411-213">REG_DWORD IncludeFileTimesInDataObject.</span></span> <span data-ttu-id="21411-214">0 = 不包含 filetimes。</span><span class="sxs-lookup"><span data-stu-id="21411-214">0 = filetimes are excluded.</span></span> <span data-ttu-id="21411-215">1 = (預設) 包含 filetimes。</span><span class="sxs-lookup"><span data-stu-id="21411-215">1 = (default) filetimes are included.</span></span>


- <span data-ttu-id="21411-216">我們已修正當回覆含有「Azure 資訊保護」保護標籤的郵件時，導致內嵌影像消失的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-216">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="21411-217">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="21411-217">PowerPoint</span></span>

- <span data-ttu-id="21411-218">修正 Slide.Shapes.AddMediaObject2 會對舊版影片格式 (MPG-1、Mpeg-2) 發生當機的 VBA 問題。</span><span class="sxs-lookup"><span data-stu-id="21411-218">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 crashing with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="21411-219">我們已修正在複製含有新錄製音訊的投影片後，儲存檔案時發生錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-219">We fixed an issue where there is an error when saving the file after duplicating a slide that contains a newly recorded audio.</span></span>


- <span data-ttu-id="21411-220">已修正無法正確開啟部分損壞的 PowerPoint 檔案 (即使在文件修復之後) 的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-220">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="word"></a><span data-ttu-id="21411-221">Word</span><span class="sxs-lookup"><span data-stu-id="21411-221">Word</span></span>

- <span data-ttu-id="21411-222">已修復影響 Word 的最佳化閘道所暴露的宣告錯誤。</span><span class="sxs-lookup"><span data-stu-id="21411-222">Fixed an assert bug exposed by optimized gates affecting Word.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2010-november-17"></a><span data-ttu-id="21411-224">版本 2010：11 月 17 日</span><span class="sxs-lookup"><span data-stu-id="21411-224">Version 2010: November 17</span></span>
<span data-ttu-id="21411-225">*版本 2010 (組建 13328.20408)*</span><span class="sxs-lookup"><span data-stu-id="21411-225">*Version 2010 (Build 13328.20408)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-227">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-227">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="21411-228">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-228">Outlook</span></span>

- <span data-ttu-id="21411-229">我們已修正會導致 MailItem.BeforeAttachmentAdd 事件中斷的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-229">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="21411-230">我們新增了一個 RegKey，可讓客戶停用 IDataObject 操作 (例如，拖曳拖放、剪貼簿) 中附件的 FileTime 包含內容。</span><span class="sxs-lookup"><span data-stu-id="21411-230">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="21411-231">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments。</span><span class="sxs-lookup"><span data-stu-id="21411-231">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span></span>  <span data-ttu-id="21411-232">REG_DWORD IncludeFileTimesInDataObject。</span><span class="sxs-lookup"><span data-stu-id="21411-232">REG_DWORD IncludeFileTimesInDataObject.</span></span>  <span data-ttu-id="21411-233">0 = 不包含 filetimes。</span><span class="sxs-lookup"><span data-stu-id="21411-233">0 = filetimes are excluded.</span></span>  <span data-ttu-id="21411-234">1 = (預設) 包含 filetimes。</span><span class="sxs-lookup"><span data-stu-id="21411-234">1 = (default) filetimes are included.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="21411-235">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="21411-235">PowerPoint</span></span>

- <span data-ttu-id="21411-236">解決在合併錯誤期間使用 IRM/受保護文件的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-236">Fix to address a an issue when using IRM/protected documents during a merge error.</span></span>


### <a name="visio"></a><span data-ttu-id="21411-237">Visio</span><span class="sxs-lookup"><span data-stu-id="21411-237">Visio</span></span>

- <span data-ttu-id="21411-238">修正使用者將可在自訂 Visio 樣板和內建範本中使用適用於 Office 365 的 Visio 連接器建立直線的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-238">We fixed an issue where users will be able to create straight lines using connectors in Visio for Office 365 for both custom Visio stencils and in-built templates.</span></span>


### <a name="office-suite"></a><span data-ttu-id="21411-239">Office 套件</span><span class="sxs-lookup"><span data-stu-id="21411-239">Office Suite</span></span>

- <span data-ttu-id="21411-240">修正在某些情況下，嘗試執行另存新檔失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-240">Fixed an issue where trying to do a SaveAs would fail in certain scenarios.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2010-november-10"></a><span data-ttu-id="21411-242">版本 2010：11 月 10 日</span><span class="sxs-lookup"><span data-stu-id="21411-242">Version 2010: November 10</span></span>
<span data-ttu-id="21411-243">*版本 2010 (組建 13328.20356)*</span><span class="sxs-lookup"><span data-stu-id="21411-243">*Version 2010 (Build 13328.20356)*</span></span>

<span data-ttu-id="21411-244">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="21411-244">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-246">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-246">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="21411-247">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-247">Outlook</span></span>

- <span data-ttu-id="21411-248">我們已修正會導致使用者無法將 [編輯器] 權限授與代理人的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-248">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


### <a name="office-suite"></a><span data-ttu-id="21411-249">Office 套件</span><span class="sxs-lookup"><span data-stu-id="21411-249">Office Suite</span></span>

- <span data-ttu-id="21411-250">我們已修正在嘗試儲存已從 syncbacked 檔案轉換為僅限伺服器的檔案時，導致失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-250">We fixed an issue that was causing a failure when trying to save files that have transitioned from syncbacked to server-only.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2010-october-27"></a><span data-ttu-id="21411-252">版本 2010：10 月 27 日</span><span class="sxs-lookup"><span data-stu-id="21411-252">Version 2010: October 27</span></span>
<span data-ttu-id="21411-253">*版本 2010 (組建 13328.20292)*</span><span class="sxs-lookup"><span data-stu-id="21411-253">*Version 2010 (Build 13328.20292)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="21411-255">功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-255">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="21411-256">Access</span><span class="sxs-lookup"><span data-stu-id="21411-256">Access</span></span>

- <span data-ttu-id="21411-257">**隨時跟上改變！[日期/時間] 延伸資料類型具有更好的精確度。：** 引進新的和改良的資料類型。</span><span class="sxs-lookup"><span data-stu-id="21411-257">**Keep up with the times! The Date/Time Extended data type has better precision.:** Introducing a new and improved data type.</span></span> <span data-ttu-id="21411-258">為加強與 SQL 的語法相容性，並提高包含日期和時間之記錄的詳細資料和層級，我們正在將 DateTime2 資料類型實施到 Access 中。</span><span class="sxs-lookup"><span data-stu-id="21411-258">To enhance syntax compatibility with SQL, and to increase accuracy and level of detail in records that include dates and times, we’re implementing the DateTime2 data type into Access.</span></span> <span data-ttu-id="21411-259">這個額外的日期與時間資料類型，將會包含更大的日期範圍 (0001-01-01 到 9999-12-31) ，具有更高的指定時間精準度(以納秒取代秒為單位)，讓您可以提供和執行計算。</span><span class="sxs-lookup"><span data-stu-id="21411-259">This additional date & time data type will include a larger date range (0001-01-01 through 9999-12-31), with higher-specified time precision (nanoseconds, rather than seconds) that you will be able to provide and perform calculations on.</span></span> <span data-ttu-id="21411-260">若要啟用，請選取 [新增欄位] > [日期與時間延長]。</span><span class="sxs-lookup"><span data-stu-id="21411-260">To enable, select New field > Date & Time Extended.</span></span> [<span data-ttu-id="21411-261">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-261">Learn more</span></span>](https://support.office.com/article/708c32da-a052-4cc2-9850-9851042e0024)

### <a name="excel"></a><span data-ttu-id="21411-262">Excel</span><span class="sxs-lookup"><span data-stu-id="21411-262">Excel</span></span>

- <span data-ttu-id="21411-263">**使用 Power Query 建立資料類型：** 使用 Power Query 從任何資料來源建立豐富的資料類型。</span><span class="sxs-lookup"><span data-stu-id="21411-263">**Create Data Types with Power Query:** Create rich data types with Power Query from any data source.</span></span> [<span data-ttu-id="21411-264">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-264">Learn more</span></span>](https://support.office.com/article/a465a3b7-3d37-4eb1-a59c-bd3163315308)<br /><span data-ttu-id="21411-265">在[部落格文章](https://techcommunity.microsoft.com/t5/excel-blog/announcing-power-query-data-types/ba-p/1782903)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="21411-265">See details in [blog post](https://techcommunity.microsoft.com/t5/excel-blog/announcing-power-query-data-types/ba-p/1782903)</span></span>

- <span data-ttu-id="21411-266">**將您的 iPhone 相片直接插入 Office：** 來自您手機的 HEIC 圖片現在可無縫地插入 Office。</span><span class="sxs-lookup"><span data-stu-id="21411-266">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="21411-267">不需要轉換。</span><span class="sxs-lookup"><span data-stu-id="21411-267">No conversion required.</span></span><br /><span data-ttu-id="21411-268">在[部落格文章](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="21411-268">See details in [blog post](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="21411-269">**使用動作手寫筆快速編輯：** 您可以使用動作手寫筆直接在儲存格中書寫，以會自動轉換成 Excel 資料的筆跡記下資料。</span><span class="sxs-lookup"><span data-stu-id="21411-269">**Make quick edits using the action pen:** With the action pen, you can write by hand directly in the cells, jot down data with ink that gets automatically converted to Excel data.</span></span>

### <a name="outlook"></a><span data-ttu-id="21411-270">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-270">Outlook</span></span>

- <span data-ttu-id="21411-271">**將您的 iPhone 相片直接插入 Office：** 來自您手機的 HEIC 圖片現在可無縫地插入 Office。</span><span class="sxs-lookup"><span data-stu-id="21411-271">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="21411-272">不需要轉換。</span><span class="sxs-lookup"><span data-stu-id="21411-272">No conversion required.</span></span><br /><span data-ttu-id="21411-273">在[部落格文章](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="21411-273">See details in [blog post](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="21411-274">**文法檢查是您的後盾**：Outlook 會在您輸入時標記文法錯誤，這麼一來，您只需按一下就可以套用建議。</span><span class="sxs-lookup"><span data-stu-id="21411-274">**Grammar checking's got your back:** Outlook marks grammar errors as you type, so you can apply suggestions with a single click.</span></span> [<span data-ttu-id="21411-275">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-275">Learn more</span></span>](https://support.office.com/article/ddbadc42-4637-451d-b3f4-ecf295036fa9)<br /><span data-ttu-id="21411-276">在[部落格文章](https://insider.office.com/zh-TW/blog/grammar-and-style-suggestions-available-in-outlook)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="21411-276">See details in [blog post](https://insider.office.com/zh-TW/blog/grammar-and-style-suggestions-available-in-outlook)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="21411-277">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="21411-277">PowerPoint</span></span>

- <span data-ttu-id="21411-278">**將您的 iPhone 相片直接插入 Office：** 來自您手機的 HEIC 圖片現在可無縫地插入 Office。</span><span class="sxs-lookup"><span data-stu-id="21411-278">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="21411-279">不需要轉換。</span><span class="sxs-lookup"><span data-stu-id="21411-279">No conversion required.</span></span><br /><span data-ttu-id="21411-280">在[部落格文章](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="21411-280">See details in [blog post](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="teams"></a><span data-ttu-id="21411-281">Teams</span><span class="sxs-lookup"><span data-stu-id="21411-281">Teams</span></span>

- <span data-ttu-id="21411-282">**Microsoft Teams 中的範本：** 使用 Teams 中的範本，使用者可在建立新的小組時從各種可自訂的範本中選擇，協助他們快速開始使用。</span><span class="sxs-lookup"><span data-stu-id="21411-282">**Templates in Microsoft Teams:** With Templates in Teams, users can choose from a variety of customizable templates when creating a new team, helping them get started quickly.</span></span> <span data-ttu-id="21411-283">IT 專業人員也可以為其組織建立新的自訂範本，讓他們能標準化小組結構、讓相關應用程式浮現，以及擴大最佳做法。</span><span class="sxs-lookup"><span data-stu-id="21411-283">IT professionals can also create new custom templates for their organization, allowing them to standardize team structures, surface relevant apps, and scale best practices.</span></span>

- <span data-ttu-id="21411-284">**釘選文章：** 此功能可讓使用者將頻道中的任何訊息「釘選」到頻道資訊窗格，使得頻道中所有成員能夠看見。</span><span class="sxs-lookup"><span data-stu-id="21411-284">**Pinned Posts:** This feature allows users to "pin" any message in a channel to the channel info pane for all members of the channel to see.</span></span> <span data-ttu-id="21411-285">擁有頻道存取權的任何成員都能查看釘選的訊息。</span><span class="sxs-lookup"><span data-stu-id="21411-285">Any members who have access to the channel will be able to see pinned messages.</span></span> <span data-ttu-id="21411-286">頻道的任何成員都能釘選任何訊息 (除非透過頻道仲裁設定關閉)。</span><span class="sxs-lookup"><span data-stu-id="21411-286">Any member of a channel will be able to pin any message (unless turned off via channel moderation settings).</span></span>

- <span data-ttu-id="21411-287">**提交至應用程式目錄：** 您會在此畫面左下角看到 [提交至應用程式目錄] 連結。</span><span class="sxs-lookup"><span data-stu-id="21411-287">**Submit to app catalog:** You’ll see a Submit to app catalog link on the lower left of this screen.</span></span> <span data-ttu-id="21411-288">除了 App Studio 和 Visual Studio，它是您可以提交應用程式進行核准的另一個位置。</span><span class="sxs-lookup"><span data-stu-id="21411-288">In addition to App Studio and Visual Studio, it’s another place where you can submit apps for approval.</span></span>

- <span data-ttu-id="21411-289">**在彈出的會議體驗中，使用 Freehand by Invision 做為白板：** 您現在可以在彈出的會議體驗中，於您參與的任何會議中將 Freehand by Invision 應用程式用作白板。</span><span class="sxs-lookup"><span data-stu-id="21411-289">**Use Freehand by Invision to whiteboard in the popped out meeting experience:** You can now use the Freehand by Invision app to whiteboard in any meeting you take in the popped out meeting experience.</span></span> <span data-ttu-id="21411-290">從共用內容匣選取 Freehand 應用程式並安裝它，然後啟動與您的同事的白板工作階段，順暢地開始激發靈感！</span><span class="sxs-lookup"><span data-stu-id="21411-290">Seamlessly start brainstorming by selecting the Freehand app from the share content tray and, installing it, and starting the whiteboarding session with your colleagues!</span></span>

### <a name="word"></a><span data-ttu-id="21411-291">Word</span><span class="sxs-lookup"><span data-stu-id="21411-291">Word</span></span>

- <span data-ttu-id="21411-292">**將您的 iPhone 相片直接插入 Office：** 來自您手機的 HEIC 圖片現在可無縫地插入 Office。</span><span class="sxs-lookup"><span data-stu-id="21411-292">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="21411-293">不需要轉換。</span><span class="sxs-lookup"><span data-stu-id="21411-293">No conversion required.</span></span><br /><span data-ttu-id="21411-294">在[部落格文章](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="21411-294">See details in [blog post](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-297">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-297">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="21411-298">存取</span><span class="sxs-lookup"><span data-stu-id="21411-298">Access</span></span>

- <span data-ttu-id="21411-299">我們已修正從非 Office 應用程式使用 DAO 時，會導致應用程式意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-299">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


### <a name="outlook"></a><span data-ttu-id="21411-300">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-300">Outlook</span></span>

- <span data-ttu-id="21411-301">我們已修正在回覆或轉寄時，會導致中文郵件標題無法閱讀的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-301">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


- <span data-ttu-id="21411-302">我們已修正在儲存為 OFT 檔案時，會導致中文字元變更為問號的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-302">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


- <span data-ttu-id="21411-303">我們已修正會導致 Outlook 為已啟用雲端設定的使用者建立第二個空白簽名的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-303">We fixed an issue that caused Outlook to create a second empty signature for people who had cloud settings enabled.</span></span>


- <span data-ttu-id="21411-304">我們已修正會導致預設不會為使用者開啟雲端設定的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-304">We fixed a n issue that caused Cloud Settings not to be turned on for users by default.</span></span>


- <span data-ttu-id="21411-305">我們已修正會導致對使用者簽章的變更無法儲存的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-305">We fixed an issue that caused changes to a user's signature to fail to save.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="21411-306">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="21411-306">PowerPoint</span></span>

- <span data-ttu-id="21411-307">這是此問題的修正：當有增益集在接聽 PresentationBeforeClose 事件並隨著事件處理常式檢查 Presentation.Saved 內容時若關閉文件，儲存提示會以迴圈顯示。</span><span class="sxs-lookup"><span data-stu-id="21411-307">This is a fix for an issue where the save prompt shows in a loop when closing the document when there is an add-in that listens to PresentationBeforeClose event and checks Presentation.Saved property as a part of the event handler.</span></span>


### <a name="project"></a><span data-ttu-id="21411-308">Project</span><span class="sxs-lookup"><span data-stu-id="21411-308">Project</span></span>

- <span data-ttu-id="21411-309">修正當您將專案從 PWA 儲存到本機 mpp 檔案時，ProjectBeforeTaskChangeEvent 會對實際上未由使用者變更的資料觸發的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-309">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="21411-310">修正 Project 在開啟以特定方式指定資源分佈的檔案時可能會意外終止的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-310">Fixed an issue where Project may terminate unexpectedly when opening files where resource contours were specified in a certain manner.</span></span>


- <span data-ttu-id="21411-311">修正當您將專案從 PWA 儲存到本機 mpp 檔案時，ProjectBeforeTaskChangeEvent 會對實際上未由使用者變更的資料觸發的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-311">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="21411-312">修正如果工作表單類型檢視內的延隔時間變更，ProjectBeforeTaskChange 事件中的 NewVal 不會有正確值的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-312">Fixed an issue where the NewVal in the ProjectBeforeTaskChange event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


### <a name="office-suite"></a><span data-ttu-id="21411-313">Office 套件</span><span class="sxs-lookup"><span data-stu-id="21411-313">Office Suite</span></span>

- <span data-ttu-id="21411-p128">當使用者從 Office 在噴墨印表機上列印任何文件/檔案且印表機墨水不足時，即使噴墨印表機並沒有碳粉，也會顯示「碳粉不足」或「無碳粉」訊息。變更訊息以顯示「碳粉/墨水不足」與「碳粉/墨水用完」。</span><span class="sxs-lookup"><span data-stu-id="21411-p128">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners. Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>

- <span data-ttu-id="21411-316">修正 Microsoft 365 端點資料外洩防護無法在磁碟上分類 Office 文件的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-316">Fixed an issue where Microsoft 365 Endpoint data loss prevention was unable to classify Office documents on disk.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2009-october-21"></a><span data-ttu-id="21411-318">版本 2009：10 月 21 日</span><span class="sxs-lookup"><span data-stu-id="21411-318">Version 2009: October 21</span></span>
<span data-ttu-id="21411-319">*版本 2009 (組建 13231.20418)*</span><span class="sxs-lookup"><span data-stu-id="21411-319">*Version 2009 (Build 13231.20418)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-321">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-321">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="21411-322">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-322">Outlook</span></span>

- <span data-ttu-id="21411-323">我們已修正會導致使用者無法將 [編輯器] 權限授與代理人的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-323">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="21411-324">我們已修正會導致使用者在選取搜尋結果時遇到意外終止的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-324">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="21411-325">我們已修正當回覆或轉寄郵件時，會導致中文郵件標題無法閱讀的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-325">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="21411-326">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="21411-326">PowerPoint</span></span>

- <span data-ttu-id="21411-327">我們已修正 [表單] 內容增益集在插入之後不會呈現，除非使用者按一下另一張投影片讓它顯示才會呈現的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-327">We have fixed an issue where Forms content add-in doesn't render after insertion until user click to another slide to make it show.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2009-october-13"></a><span data-ttu-id="21411-329">版本 2009：10 月 13 日</span><span class="sxs-lookup"><span data-stu-id="21411-329">Version 2009: October 13</span></span>
<span data-ttu-id="21411-330">*版本 2009 (組建 13231.20390)*</span><span class="sxs-lookup"><span data-stu-id="21411-330">*Version 2009 (Build 13231.20390)*</span></span>

<span data-ttu-id="21411-331">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="21411-331">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-333">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-333">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="21411-334">Project</span><span class="sxs-lookup"><span data-stu-id="21411-334">Project</span></span>

- <span data-ttu-id="21411-335">修正 Project 在開啟以特定方式指定資源分佈的檔案時可能會遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-335">Fixed an issue where Project may crash on opening files where resource contours were specified in a certain manner.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2009-october-08"></a><span data-ttu-id="21411-337">版本 2009：10 月 8 日</span><span class="sxs-lookup"><span data-stu-id="21411-337">Version 2009: October 08</span></span>
<span data-ttu-id="21411-338">*版本 2009 (組建 13231.20368)*</span><span class="sxs-lookup"><span data-stu-id="21411-338">*Version 2009 (Build 13231.20368)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-340">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-340">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="21411-341">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-341">Outlook</span></span>

- <span data-ttu-id="21411-342">解決了搜尋未緩存共用行事曆時導致搜尋不傳回結果的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-342">Addresses an issue that caused Search to return no results when searching uncached shared calendars.</span></span>


- <span data-ttu-id="21411-343">解決了導致某些使用者觀察到在離線狀態下意外啟動 Outlook 的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-343">Addresses an issue that caused some users to observe Outlook unexpectedly starting in an offline state.</span></span>


- <span data-ttu-id="21411-344">解決了導致代理人在開啟另一個信箱中的共用資料夾時出現錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-344">Addresses an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="21411-345">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="21411-345">PowerPoint</span></span>

- <span data-ttu-id="21411-346">解決在受保護的檢視中開啟 PowerPoint 檔案時停用 IRM 保護的問題的安全性問題修正。</span><span class="sxs-lookup"><span data-stu-id="21411-346">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


### <a name="office-suite"></a><span data-ttu-id="21411-347">Office 套件</span><span class="sxs-lookup"><span data-stu-id="21411-347">Office Suite</span></span>

- <span data-ttu-id="21411-p129">當使用者從 Office 在噴墨印表機上列印任何文件/檔案且印表機墨水不足時，即使噴墨印表機並沒有碳粉，也會顯示「碳粉不足」或「無碳粉」訊息。變更訊息以顯示「碳粉/墨水不足」與「碳粉/墨水用完」。</span><span class="sxs-lookup"><span data-stu-id="21411-p129">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners. Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2009-september-28"></a><span data-ttu-id="21411-351">版本 200９：9 月 28 日</span><span class="sxs-lookup"><span data-stu-id="21411-351">Version 2009: September 28</span></span>
<span data-ttu-id="21411-352">*版本 2009 (組建 13231.20262)*</span><span class="sxs-lookup"><span data-stu-id="21411-352">*Version 2009 (Build 13231.20262)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="21411-354">功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-354">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="21411-355">Excel</span><span class="sxs-lookup"><span data-stu-id="21411-355">Excel</span></span>

- <span data-ttu-id="21411-356">**將圖形另存為圖片：** 只要按幾下，即可將圖形、圖示或其他物件另存成圖片，便於您於任何其他地方使用。</span><span class="sxs-lookup"><span data-stu-id="21411-356">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="21411-357">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-357">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="21411-358">**使用資料類型從 Power BI 取得組織資料：** 現在，來自 Power BI 的 Excel 資料類型將推出給使用 Office 365 / Microsoft 365 和 Power BI Pro 服務方案的組織測試人員使用。</span><span class="sxs-lookup"><span data-stu-id="21411-358">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 / Microsoft 365 and the Power BI Pro service plan.</span></span> <span data-ttu-id="21411-359">取得您所需的資訊，輕鬆地重新整理，對許多日常工作流程而言至關重要。</span><span class="sxs-lookup"><span data-stu-id="21411-359">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="21411-360">我們允許您透過 Excel 中的資料類型從 Power BI 存取公司或組織資訊，從而擴充您在試算表中引入連結資訊的能力。</span><span class="sxs-lookup"><span data-stu-id="21411-360">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="21411-361">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-361">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="21411-362">在[部落格文章](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="21411-362">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

- <span data-ttu-id="21411-363">**建立變數以在公式中使用：** 使用 LET 函數改善效能、可讀性及可組合性。</span><span class="sxs-lookup"><span data-stu-id="21411-363">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="21411-364">此函數可讓您在新的或現有的公式中建立命名變數。</span><span class="sxs-lookup"><span data-stu-id="21411-364">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="21411-365">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-365">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="21411-366">在[部落格文章](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="21411-366">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="21411-367">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-367">Outlook</span></span>

- <span data-ttu-id="21411-368">**自動開展線上目錄搜尋ive Search:** Enabling auto-expanding Online Archive Search</span><span class="sxs-lookup"><span data-stu-id="21411-368">**Auto-Expanding Online Archive Search:** Enabling auto-expanding Online Archive Search</span></span>

- <span data-ttu-id="21411-369">**Outlook 的新設定檔卡：** Outlook 的新設定檔卡，包括更完善的組織方式，並符合 Outlook Web 卡的樣式。</span><span class="sxs-lookup"><span data-stu-id="21411-369">**New profile card for Outlook:** New profile card for Outlook including a better Organization view and matches the card style of Outlook Web.</span></span>

### <a name="teams"></a><span data-ttu-id="21411-370">Teams</span><span class="sxs-lookup"><span data-stu-id="21411-370">Teams</span></span>

- <span data-ttu-id="21411-371">**在 Microsoft Teams 中共用檔案：** [深入了解](/MicrosoftTeams/sharing-files-in-teams)</span><span class="sxs-lookup"><span data-stu-id="21411-371">**Sharing files in Microsoft Teams:** [Learn more](/MicrosoftTeams/sharing-files-in-teams)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-374">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-374">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="21411-375">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-375">Outlook</span></span>

- <span data-ttu-id="21411-376">已解決當主旨行空白時，會導致傳送的自動產生電子郵件含有空白內文的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-376">Addresses an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="21411-377">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="21411-377">PowerPoint</span></span>

- <span data-ttu-id="21411-378">修正了在包含大量特定資料物件類型 (E2o) 的檔案上導致共同撰寫變慢的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-378">Fixed an issue causing slow coauthoring on files containing large numbers of a certain data object type (E2o).</span></span>


### <a name="project"></a><span data-ttu-id="21411-379">Project</span><span class="sxs-lookup"><span data-stu-id="21411-379">Project</span></span>

- <span data-ttu-id="21411-380">修正若您的事件程式碼執行中，並嘗試透過工作 [表單檢視] 進行變更，按一下 [確定] 按鈕可能不會提交變更的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-380">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


### <a name="word"></a><span data-ttu-id="21411-381">Word</span><span class="sxs-lookup"><span data-stu-id="21411-381">Word</span></span>

- <span data-ttu-id="21411-382">我們已修正 [樣式圖庫] 對話方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-382">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="21411-383">Office 套件</span><span class="sxs-lookup"><span data-stu-id="21411-383">Office Suite</span></span>

- <span data-ttu-id="21411-384">此變更解決 [匯出至動畫 GIF] 功能的問題，其中按一下 [匯出] 按鈕沒有匯出。</span><span class="sxs-lookup"><span data-stu-id="21411-384">This change addresses an issue with Export to Animated GIF feature where clicking on Export button was not exporting.</span></span>


- <span data-ttu-id="21411-385">此變更解決 [壓縮圖片] 對話方塊無法保留特定使用者設定的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-385">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-september-22"></a><span data-ttu-id="21411-387">版本 2008: 9月 22日</span><span class="sxs-lookup"><span data-stu-id="21411-387">Version 2008: September 22</span></span>
<span data-ttu-id="21411-388">*版本 2008 (組建 13127.20508)*</span><span class="sxs-lookup"><span data-stu-id="21411-388">*Version 2008 (Build 13127.20508)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-390">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-390">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="21411-391">Excel</span><span class="sxs-lookup"><span data-stu-id="21411-391">Excel</span></span>

- <span data-ttu-id="21411-392">修正當凍結工作表頂端列之後，Excel 可能會在使用 [快速分析] 時當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-392">Fixed an issue where Excel could crash when using the Quick Analysis after freezing the top row of the sheet.</span></span>


- <span data-ttu-id="21411-393">修正當活頁簿包含使用 IFNA () 的公式時，可能會造成錯誤活頁簿的警告之問題。</span><span class="sxs-lookup"><span data-stu-id="21411-393">Fixed an issue that could cause a warning about a corrupt workbook if it contained formulas using IFNA().</span></span>


### <a name="outlook"></a><span data-ttu-id="21411-394">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-394">Outlook</span></span>

- <span data-ttu-id="21411-395">解決由於按一下角落中的 [X] 而導致使用者無法關閉共用行事曆的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-395">Addresses an issue that caused users to be unable to close shared calendars by clicking on the "X" in the corner.</span></span>


- <span data-ttu-id="21411-396">解決附件上傳的效能問題。</span><span class="sxs-lookup"><span data-stu-id="21411-396">Addresses a performance issue with attachment upload.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="21411-397">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="21411-397">PowerPoint</span></span>

- <span data-ttu-id="21411-398">我們已修正在 PowerPoint 應用程式中導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-398">We have fixed an issue which was causing the crash in PowerPoint app.</span></span>


### <a name="visio"></a><span data-ttu-id="21411-399">Visio</span><span class="sxs-lookup"><span data-stu-id="21411-399">Visio</span></span>

- <span data-ttu-id="21411-400">客戶回報文字對齊會在即時預覽時發生當機。</span><span class="sxs-lookup"><span data-stu-id="21411-400">Live preview crashes on text alignment reported by customers.</span></span> <span data-ttu-id="21411-401">7 月分支所發生最多的當機情況。</span><span class="sxs-lookup"><span data-stu-id="21411-401">Top hitting crash of July fork.</span></span>


### <a name="word"></a><span data-ttu-id="21411-402">Word</span><span class="sxs-lookup"><span data-stu-id="21411-402">Word</span></span>

- <span data-ttu-id="21411-403">我們已修正 [樣式圖庫] 對話方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-403">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="21411-404">Office 套件</span><span class="sxs-lookup"><span data-stu-id="21411-404">Office Suite</span></span>

- <span data-ttu-id="21411-405">修正使用 GIF/動畫 model3D 時導致高 CPU 使用狀況空閒</span><span class="sxs-lookup"><span data-stu-id="21411-405">Fixes high CPU usage on idle with GIF/animated model3D</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-september-09"></a><span data-ttu-id="21411-407">版本 2008：9月 9 日</span><span class="sxs-lookup"><span data-stu-id="21411-407">Version 2008: September 09</span></span>
<span data-ttu-id="21411-408">*版本 2008 (組建 13127.20408)*</span><span class="sxs-lookup"><span data-stu-id="21411-408">*Version 2008 (Build 13127.20408)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-410">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-410">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="21411-411">Access</span><span class="sxs-lookup"><span data-stu-id="21411-411">Access</span></span>

- <span data-ttu-id="21411-412">此變更修正了當啟動縮放框 (Shift + F2) 來編輯文字時，可能會導致 Access 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-412">This change fixes an issue that could cause Access to crash when launching the Zoom box (Shift + F2) to edit text.</span></span>


### <a name="excel"></a><span data-ttu-id="21411-413">Excel</span><span class="sxs-lookup"><span data-stu-id="21411-413">Excel</span></span>

- <span data-ttu-id="21411-414">修正使用 [複製格式] 時，某些情況下，Excel 可能會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-414">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>


### <a name="word"></a><span data-ttu-id="21411-415">Word</span><span class="sxs-lookup"><span data-stu-id="21411-415">Word</span></span>

- <span data-ttu-id="21411-416">我們已修正在調整圖案大小時，使用者可能會遺失內容的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-416">We fixed an issue where the user might lose content when resize a shape.</span></span>


- <span data-ttu-id="21411-417">我們已修正基本樣式未更新為「內文樣式」的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-417">We fixed an issue which the base styles are not updated with Normal style.</span></span>


### <a name="office-suite"></a><span data-ttu-id="21411-418">Office 套件</span><span class="sxs-lookup"><span data-stu-id="21411-418">Office Suite</span></span>

- <span data-ttu-id="21411-419">此變更解決 [壓縮圖片] 對話方塊無法保留特定使用者設定的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-419">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-august-31"></a><span data-ttu-id="21411-421">版本2008：8月31日</span><span class="sxs-lookup"><span data-stu-id="21411-421">Version 2008: August 31</span></span>
<span data-ttu-id="21411-422">*版本2008（組建13127.20296）*</span><span class="sxs-lookup"><span data-stu-id="21411-422">*Version 2008 (Build 13127.20296)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="21411-424">功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-424">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="21411-425">Excel</span><span class="sxs-lookup"><span data-stu-id="21411-425">Excel</span></span>

- <span data-ttu-id="21411-426">**儲存至釘選資料夾：** 釘選資料夾可讓您更輕鬆地儲存 Office 檔案。</span><span class="sxs-lookup"><span data-stu-id="21411-426">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="21411-427">我們收到了意見反應，使用者想更進一步控制儲存新檔案時可用的資料夾。</span><span class="sxs-lookup"><span data-stu-id="21411-427">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="21411-428">我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。</span><span class="sxs-lookup"><span data-stu-id="21411-428">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="21411-429">這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。</span><span class="sxs-lookup"><span data-stu-id="21411-429">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="21411-430">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-430">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="21411-431">在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="21411-431">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="21411-432">**在 Excel 中製作精美的 Visio 圖表：** 將資料放在工作表上，以建立流程圖或組織圖。</span><span class="sxs-lookup"><span data-stu-id="21411-432">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="21411-433">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-433">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="outlook"></a><span data-ttu-id="21411-434">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-434">Outlook</span></span>

- <span data-ttu-id="21411-435">**電子郵件中的改良連結：** 當您包含檔案的連結時，檔案名會取代 URL。</span><span class="sxs-lookup"><span data-stu-id="21411-435">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="21411-436">您可以變更權限，讓所有收件者都能存取。</span><span class="sxs-lookup"><span data-stu-id="21411-436">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="21411-437">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-437">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)<br /><span data-ttu-id="21411-438">在[部落格文章](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="21411-438">See details in [blog post](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span></span>



### <a name="powerpoint"></a><span data-ttu-id="21411-439">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="21411-439">PowerPoint</span></span>

- <span data-ttu-id="21411-440">**儲存至釘選資料夾：** 釘選資料夾可讓您更輕鬆地儲存 Office 檔案。</span><span class="sxs-lookup"><span data-stu-id="21411-440">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="21411-441">我們收到了意見反應，使用者想更進一步控制儲存新檔案時可用的資料夾。</span><span class="sxs-lookup"><span data-stu-id="21411-441">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="21411-442">我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。</span><span class="sxs-lookup"><span data-stu-id="21411-442">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="21411-443">這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。</span><span class="sxs-lookup"><span data-stu-id="21411-443">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="21411-444">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-444">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="21411-445">在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="21411-445">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="teams"></a><span data-ttu-id="21411-446">Teams</span><span class="sxs-lookup"><span data-stu-id="21411-446">Teams</span></span>

- <span data-ttu-id="21411-447">**合併通話：** 合併通話可讓使用者將使用中的 unheld 1-1 撥入另一個1-1 通話或另一個群組通話。</span><span class="sxs-lookup"><span data-stu-id="21411-447">**Call Merge:** Call Merge gives end users the capability to merge their active unheld 1-1 call into another 1-1 call or another group call.</span></span> <span data-ttu-id="21411-448">這適用於Teams VOIP 通話和 PSTN 通話。</span><span class="sxs-lookup"><span data-stu-id="21411-448">This applies to Teams VOIP calls and PSTN calls.</span></span>

- <span data-ttu-id="21411-449">**系統管理員可以針對其第一線工作者設定按班表顯示（上班、下班）：** 系統管理員可以設定其第一線工作者使用以班表為基礎的狀態顯示：上班、忙碌中（到班時可以切換）和下班。</span><span class="sxs-lookup"><span data-stu-id="21411-449">**Admins can configure shift-based presence (On shift, Off shift) for their Firstline workers:** Admins can configure their firstline workers to have shift-based presence states: On shift, Busy (can be toggled when on shift), and Off shift.</span></span>

- <span data-ttu-id="21411-450">**在Teams中使用 Cortana 語音技能：** Teams行動裝置的應用程式的Cortana 語音功能, 可協助使用者僅使用口頭自然語言即可執行會議、通訊與共同協作任務。</span><span class="sxs-lookup"><span data-stu-id="21411-450">**Cortana voice skills in Teams:** Cortana voice skills in Teams mobile app help users perform meeting, communication and collaboration tasks simply using spoken natural language.</span></span> <span data-ttu-id="21411-451">使用者可以在Teams應用程式中點擊麥克風按鈕與Cortana交談, 而且當他們困在家務中或遛狗或一般外出需與某人聯繫時, 可以發出諸如“打電話給Megan”或“對我的下一個會議發送訊息”之類的請求.</span><span class="sxs-lookup"><span data-stu-id="21411-451">Users can speak to Cortana by clicking on the microphone button in Teams app and make requests like “Call Megan” or “Send a message to my next meeting” if they need to connect with someone while juggling household chores or walking the dog or generally on the go.</span></span> <span data-ttu-id="21411-452">使用者只要說「加入我的下一個會議」即可加入會議，或者詢問「我今天早上有什麼事」來檢查行事曆。</span><span class="sxs-lookup"><span data-stu-id="21411-452">Users can join meetings simply by saying “Join my next meeting” or check their calendar by asking “what do I have this morning”.</span></span> <span data-ttu-id="21411-453">在會議或通話中，他們可以從會議主持者的 [溢出] 功能表中調用 Cortana，並執行典型的會議中任務，例如按照姓名或電話號碼（「將 Megan 新增至通話」）、投影片瀏覽（「顯示季度檢閱投影片瀏覽」）或檢視投影片（「移至投影片備忘稿」）。</span><span class="sxs-lookup"><span data-stu-id="21411-453">Once in a meeting or a call, they can invoke Cortana from the overflow menu in the meeting stage and perform typical in-meeting tasks like adding people by name or number (“Add Megan to the call”), deck presentation (“present the quarterly review deck”) or navigating slides (“Go to the appendix slide”).</span></span> <span data-ttu-id="21411-454">該功能還支持其他功能, 如尋找及共享檔案、搜尋，並通常在Teams應用中導航（與約翰聊天，移至我的未讀取活動，請移至我的表述等等）。</span><span class="sxs-lookup"><span data-stu-id="21411-454">Other things that the feature supports are finding and sharing files, search, and generally navigating within the Teams app (“Open my chat with John, Go to my unread activity, Go to my mentions etc.).</span></span> <span data-ttu-id="21411-455">Teams 的Cortana 對Cortana 企業服務來說說符合對 Cortana 企業服務相同的的企業級隱私、安全性和合規性承諾，並反映在 [線上服務條款（OST）](https://www.microsoft.com/licensing/product-licensing/products)中。</span><span class="sxs-lookup"><span data-stu-id="21411-455">Cortana in Teams meets the same enterprise-level privacy, security, and compliance promises for Cortana enterprise services, as reflected in the [Online Services Terms (OST)](https://www.microsoft.com/licensing/product-licensing/products).</span></span>

- <span data-ttu-id="21411-456">**增加群組交談：** Teams新增了群組聊天中可有250個參與者的功能.</span><span class="sxs-lookup"><span data-stu-id="21411-456">**Group chat increase:** Teams added the ability to now have 250 participants in a group chat.</span></span>

- <span data-ttu-id="21411-457">**按 Shift 加上標籤:** 使用這項功能，系統會自動在小組中的 [Shifts app](https://support.microsoft.com/office/get-started-in-shifts-5f3e30d8-1821-4904-be26-c3cd25a497d6#bkmk_openshiftsappdesktop) 應用程式中, 為人員指派符合其行程和班表的標籤。</span><span class="sxs-lookup"><span data-stu-id="21411-457">**Tagging by Shift:** With this feature, people are automatically assigned tags that match their schedule and shift group name in the [Shifts app](https://support.microsoft.com/office/get-started-in-shifts-5f3e30d8-1821-4904-be26-c3cd25a497d6#bkmk_openshiftsappdesktop) in Teams.</span></span>

### <a name="word"></a><span data-ttu-id="21411-458">Word</span><span class="sxs-lookup"><span data-stu-id="21411-458">Word</span></span>

- <span data-ttu-id="21411-459">**儲存至釘選資料夾：** 釘選資料夾可讓您更輕鬆地儲存 Office 檔案。</span><span class="sxs-lookup"><span data-stu-id="21411-459">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="21411-460">我們收到了意見反應，使用者想更進一步控制儲存新檔案時可用的資料夾。</span><span class="sxs-lookup"><span data-stu-id="21411-460">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="21411-461">我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。</span><span class="sxs-lookup"><span data-stu-id="21411-461">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="21411-462">這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。</span><span class="sxs-lookup"><span data-stu-id="21411-462">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="21411-463">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-463">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="21411-464">在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="21411-464">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="office-suite"></a><span data-ttu-id="21411-465">Office 套件</span><span class="sxs-lookup"><span data-stu-id="21411-465">Office Suite</span></span>

- <span data-ttu-id="21411-466">**索引標籤式窗格：** 現在您可以使用應用程式右側的索引標籤 UI，在多個窗格之間切換。</span><span class="sxs-lookup"><span data-stu-id="21411-466">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="21411-467">只有當您開啟 2 個以上的窗格時，該 UI 才會顯示。</span><span class="sxs-lookup"><span data-stu-id="21411-467">The UI will only be visible when you have 2+ panes open.</span></span><br /><span data-ttu-id="21411-468">在[部落格文章](https://blog-insider.office.com/2020/02/20/improved-pane-management/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="21411-468">See details in [blog post](https://blog-insider.office.com/2020/02/20/improved-pane-management/)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-471">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-471">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="21411-472">Access</span><span class="sxs-lookup"><span data-stu-id="21411-472">Access</span></span>

- <span data-ttu-id="21411-473">已解决此問題 - 您現在可以使用 Office 的隨選即用應用程式外的 ODBC 驅動程式。</span><span class="sxs-lookup"><span data-stu-id="21411-473">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>


### <a name="outlook"></a><span data-ttu-id="21411-474">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-474">Outlook</span></span>

- <span data-ttu-id="21411-475">修正會導致使用者嘗試從次要帳戶建立會議邀請的問題，讓帳戶新增至他們的個人檔案，而不會看到空白的表格: 是欄位而不是其電子郵件地址。</span><span class="sxs-lookup"><span data-stu-id="21411-475">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>

- <span data-ttu-id="21411-476">修正新增共用信箱之後，導致使用者無法連線至公用資料夾的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-476">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>

- <span data-ttu-id="21411-477">解決了當代理人在某些情況下遭到拒絕而導致會議無法從經理的行事曆中移除的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-477">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>

- <span data-ttu-id="21411-478">解決了導致使用 Shared Calendar Improvements 的某些使用者無法查看剛新增的共用行事曆的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-478">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="21411-479">修正了當與雲端附件互動時，導致使用者偶爾當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-479">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>

- <span data-ttu-id="21411-480">解決了導致某些字元集的使用者在將 [智慧型連結] 新增至 SharePoint 檔案時，發現檔案名不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-480">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>

- <span data-ttu-id="21411-481">解決會導致使用者在回覆或撰寫新電子郵件時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-481">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>

- <span data-ttu-id="21411-482">解決了當您從 POP 帳戶刪除4或多個電子郵件時，已選取 [僅下載標題] 選項時，導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-482">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>

- <span data-ttu-id="21411-483">解決導致 [排程助理員] 頁面無法顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-483">Addressed an issue that caused some users to see the Scheduling Assistant page fail to display.</span></span>

- <span data-ttu-id="21411-484">修正了編輯收件者時，導致使用者偶爾當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-484">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="21411-485">修正會導致使用者在使用壓縮模式時發生異常的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-485">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>

- <span data-ttu-id="21411-486">解決的問題導致在搜尋控制項中無法顯示滑鼠右鍵功能表。</span><span class="sxs-lookup"><span data-stu-id="21411-486">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>

- <span data-ttu-id="21411-487">解決會導致使用者在回覆或撰寫新電子郵件時收到下列錯誤的問題：「這個網頁中的某些檔案不存在預期的位置，</span><span class="sxs-lookup"><span data-stu-id="21411-487">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="21411-488">請問您一定要下載嗎?</span><span class="sxs-lookup"><span data-stu-id="21411-488">Do you want to download them anyway?</span></span> <span data-ttu-id="21411-489">如果您確定網頁來自信任的來源，請按 [是]」</span><span class="sxs-lookup"><span data-stu-id="21411-489">If you’re sure the Web page is from a trusted source, click Yes"</span></span>


### <a name="project"></a><span data-ttu-id="21411-490">Project</span><span class="sxs-lookup"><span data-stu-id="21411-490">Project</span></span>

- <span data-ttu-id="21411-491">修正「連結至 SharePoint 工作清單的專案的完成日期沒有更新」的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-491">Fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>

- <span data-ttu-id="21411-492">修正如果資源中定義了多個成本費率表，其餘成本並不一定都能正確地計算的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-492">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>

### <a name="skype"></a><span data-ttu-id="21411-493">Skype</span><span class="sxs-lookup"><span data-stu-id="21411-493">Skype</span></span>

- <span data-ttu-id="21411-494">將跳舞表情符號膚色變更為中性色彩.</span><span class="sxs-lookup"><span data-stu-id="21411-494">Changed dancing emoticon skin tone to neutral color.</span></span>

### <a name="word"></a><span data-ttu-id="21411-495">Word</span><span class="sxs-lookup"><span data-stu-id="21411-495">Word</span></span>

- <span data-ttu-id="21411-496">此更改解決了一個問題，即在上一個協同合作的作業後，Microsoft Office 應用程式可能卡在未通知的儲存失敗狀態的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-496">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>

- <span data-ttu-id="21411-497">我們已修正整體的 AutoOpen 在 AutoExec 之前執行的問題</span><span class="sxs-lookup"><span data-stu-id="21411-497">We fixed an issue where macro AutoOpen runs before AutoExec</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-august-25"></a><span data-ttu-id="21411-499">版本 2007：8 月 25 日</span><span class="sxs-lookup"><span data-stu-id="21411-499">Version 2007: August 25</span></span>
<span data-ttu-id="21411-500">*版本 2007 (組建 13029.20460)*</span><span class="sxs-lookup"><span data-stu-id="21411-500">*Version 2007 (Build 13029.20460)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-502">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-502">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="21411-503">Excel</span><span class="sxs-lookup"><span data-stu-id="21411-503">Excel</span></span>

- <span data-ttu-id="21411-504">嘗試使用 LET() 函數儲存含有公式的檔案時發生錯誤。</span><span class="sxs-lookup"><span data-stu-id="21411-504">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>


### <a name="outlook"></a><span data-ttu-id="21411-505">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-505">Outlook</span></span>

- <span data-ttu-id="21411-506">解決了導致某些字元集的使用者在將 [智慧型連結] 新增至 SharePoint 檔案時，發現檔案名不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-506">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>


- <span data-ttu-id="21411-507">解決會導致 Outlook 使用者在精簡檢視中看到瀏覽問題的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-507">Addressed an issue that caused outlook users to see issues with navigation in compact views.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="21411-508">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="21411-508">PowerPoint</span></span>

- <span data-ttu-id="21411-509">我們已修正 PowerPoint 應用程式的當機問題。</span><span class="sxs-lookup"><span data-stu-id="21411-509">We have fixed a crash issue with PowerPoint app.</span></span>


### <a name="word"></a><span data-ttu-id="21411-510">Word</span><span class="sxs-lookup"><span data-stu-id="21411-510">Word</span></span>

- <span data-ttu-id="21411-511">解決會導致使用者在回覆或撰寫新郵件時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-511">Addresses an issue that caused users to experience a crash when replying to or composing new mail.</span></span>


### <a name="office-suite"></a><span data-ttu-id="21411-512">Office 套件</span><span class="sxs-lookup"><span data-stu-id="21411-512">Office Suite</span></span>

- <span data-ttu-id="21411-p143">針對舊版非 Web 服務的 [共用] 窗格，在開啟 [共用] 窗格的情況下關閉文件時，可能會導致當機。現已修正此問題。</span><span class="sxs-lookup"><span data-stu-id="21411-p143">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash. This is now fixed.</span></span>


- <span data-ttu-id="21411-515">我們已修正使用者在特定情況下 (特別是進入或退出簡報者檢視畫面或使用多個監視器) 看到 UI 元素或內容未顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-515">We fixed an issue where users were seeing the UI elements or content not being displayed under certain conditions, in particular with coming in and out of Presenter View or using multiple monitors.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-august-11"></a><span data-ttu-id="21411-517">版本 2007: 8月11日</span><span class="sxs-lookup"><span data-stu-id="21411-517">Version 2007: August 11</span></span>
<span data-ttu-id="21411-518">*版本 2007 (組建 13029.20344)*</span><span class="sxs-lookup"><span data-stu-id="21411-518">*Version 2007 (Build 13029.20344)*</span></span>

<span data-ttu-id="21411-519">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="21411-519">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-521">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-521">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="21411-522">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-522">Outlook</span></span>

- <span data-ttu-id="21411-523">解決會導致 Outlook 無法擷取搜尋建議的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-523">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>


- <span data-ttu-id="21411-524">解決會導致使用者在擷取角色資訊時有時候會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-524">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>


### <a name="project"></a><span data-ttu-id="21411-525">Project</span><span class="sxs-lookup"><span data-stu-id="21411-525">Project</span></span>

- <span data-ttu-id="21411-526">修正無法開啟已進入錯誤狀態的專案的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-526">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-july-30"></a><span data-ttu-id="21411-528">版本 2007：7 月 30 日</span><span class="sxs-lookup"><span data-stu-id="21411-528">Version 2007: July 30</span></span>
<span data-ttu-id="21411-529">*版本 2007 (組建 13029.20308)*</span><span class="sxs-lookup"><span data-stu-id="21411-529">*Version 2007 (Build 13029.20308)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="21411-531">功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-531">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="21411-532">Excel</span><span class="sxs-lookup"><span data-stu-id="21411-532">Excel</span></span>

- <span data-ttu-id="21411-533">**建立 PDF 連線：** 連線至、匯入、重新整理 PDF 中的資料。</span><span class="sxs-lookup"><span data-stu-id="21411-533">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="21411-534">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-534">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="21411-535">**篩選和排序而不干擾其他人：** 您現在可以排序和篩選您的 Excel 檔案，同時與其他人使用工作表檢視進行共同作業。</span><span class="sxs-lookup"><span data-stu-id="21411-535">**Filter and sort without disrupting others:** You can now sort and filter your Excel file while collaborating with others with Sheet View.</span></span> <span data-ttu-id="21411-536">此新功能可防止您在共同撰寫文件時，受到其他使用者的排序和篩選的影響。</span><span class="sxs-lookup"><span data-stu-id="21411-536">This new feature prevents you from being impacted by other user’s sorts and filters while coauthoring the document.</span></span> [<span data-ttu-id="21411-537">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-537">Learn more</span></span>](https://support.office.com/article/0eea3dc5-d7d1-44c5-a953-25ebfbd6c1a6)

- <span data-ttu-id="21411-538">**自動套用或建議敏感度標籤：** Office 可以根據偵測到的敏感性內容來建議或自動套用敏感度標籤。</span><span class="sxs-lookup"><span data-stu-id="21411-538">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

- <span data-ttu-id="21411-539">**在 Excel 中建立來自 Power BI 資料的樞紐分析表：** 您可以在 Excel 中建立樞紐分析表，只要按幾下滑鼠，就能連線到儲存在 Power BI 的樞紐分析表。</span><span class="sxs-lookup"><span data-stu-id="21411-539">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="21411-540"> 如此一來，您就能獲得樞紐分析表和 Power BI 的最佳效果。</span><span class="sxs-lookup"><span data-stu-id="21411-540">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="21411-541">使用安全 Power BI 資料集的樞紐分析表以計算、摘要及分析資料。</span><span class="sxs-lookup"><span data-stu-id="21411-541">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="21411-542">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-542">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)<br /><span data-ttu-id="21411-543">在[部落格文章](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="21411-543">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="21411-544">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-544">Outlook</span></span>

- <span data-ttu-id="21411-545">**在 Outlook 中使用 [快速投票] 建立投票：** 輕鬆建立投票，收集投票，並查看電子郵件中的結果 [深入瞭解](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="21411-545">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="21411-546">**將圖片作為電子郵件的一部分傳送時，讓圖片保持高畫質：** 一個新 Outlook 設定，可讓您在隨著電子郵件內容傳送圖片時限制圖片壓縮</span><span class="sxs-lookup"><span data-stu-id="21411-546">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>

- <span data-ttu-id="21411-547">**快速重新開啟上一個工作階段的項目：** 我們新增了一個選項，可快速重新開啟上一個 Outlook 工作階段的項目。</span><span class="sxs-lookup"><span data-stu-id="21411-547">**Quickly reopen items from previous session:** We added an option to quickly reopen items from a previous Outlook session.</span></span> <span data-ttu-id="21411-548">不管 Outlook 當機或您將其關閉，您現在可以在重新開啟應用程式時快速重新啟動項目。</span><span class="sxs-lookup"><span data-stu-id="21411-548">Whether Outlook crashes or you close it, you’ll now be able to quickly relaunch items when you reopen the app.</span></span> <span data-ttu-id="21411-549">這項功能預設為啟用。</span><span class="sxs-lookup"><span data-stu-id="21411-549">This feature is on by default.</span></span> <span data-ttu-id="21411-550">若要將它關閉，請移至 [選項] > [一般] > [啟動選項]。</span><span class="sxs-lookup"><span data-stu-id="21411-550">To turn it off, go to Options > General > Start up Options.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="21411-551">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="21411-551">PowerPoint</span></span>

- <span data-ttu-id="21411-552">**[自動套用] 或 [建議敏感度] 標籤：** Office 可以根據偵測到的敏感性內容來推薦或自動套用靈敏度標籤。</span><span class="sxs-lookup"><span data-stu-id="21411-552">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="teams"></a><span data-ttu-id="21411-553">Teams</span><span class="sxs-lookup"><span data-stu-id="21411-553">Teams</span></span>

- <span data-ttu-id="21411-554">**新增簡化的通知設定：** 使用者現在可以使用增強的功能，以更簡單的方式管理其通知設定。</span><span class="sxs-lookup"><span data-stu-id="21411-554">**New simplified notification settings:** Users can now manage their notifications settings in a more simplified manner with enhanced functionalities.</span></span>

- <span data-ttu-id="21411-555">**Teams 現在支援 Windows 原生通知：** 使用者現在可以選取其偏好的通知傳送方式，即透過 Teams 內建橫幅或 Windows 原生橫幅。</span><span class="sxs-lookup"><span data-stu-id="21411-555">**Windows Native Notification are now Supported on Teams:** Users can now select their preferred means of notification delivery, either through teams built in banners or the windows native banners.</span></span>

- <span data-ttu-id="21411-556">**頻道資訊窗格：** 選取頻道標頭中的 [頻道資訊] 圖示時，將開啟一個窗格，其中會顯示頻道資訊的摘要，包括頻道描述、最近的參與者和成員清單，以及系統訊息的新首頁。</span><span class="sxs-lookup"><span data-stu-id="21411-556">**Channel Info Pane:** When selecting on the "Channel info" icon in the channel header, a pane will open where you will see a summary of channel information including the channel description, a list of recent contributors and members, as well as the new home for system messages.</span></span>

- <span data-ttu-id="21411-557">**關閉聊天通知的預覽：** 使用者可以變更設定，並管理其聊天通知快顯的預覽。</span><span class="sxs-lookup"><span data-stu-id="21411-557">**Turn off previews for your chat notifications:** Users can change settings and manage previews for their chat notification toasts.</span></span>

- <span data-ttu-id="21411-558">**建議的回覆：** 我們新增了讓 Teams 使用者對其交談具備建議的回覆功能。</span><span class="sxs-lookup"><span data-stu-id="21411-558">**Suggested replies:** We added the ability for Teams users to have a suggested reply to their conversations.</span></span> <span data-ttu-id="21411-559">這些建議會顯示在聊天訊息的底部 (如果已啟用)。</span><span class="sxs-lookup"><span data-stu-id="21411-559">These suggestions will appear at the bottom of a chat message if they are enabled.</span></span> <span data-ttu-id="21411-560">它們能讓您快速輕鬆地回覆訊息！</span><span class="sxs-lookup"><span data-stu-id="21411-560">They make replying to messages quick and easy!</span></span>

### <a name="word"></a><span data-ttu-id="21411-561">Word</span><span class="sxs-lookup"><span data-stu-id="21411-561">Word</span></span>

- <span data-ttu-id="21411-562">**[自動套用] 或 [建議敏感度] 標籤：** Office 可以根據偵測到的敏感性內容來推薦或自動套用靈敏度標籤。</span><span class="sxs-lookup"><span data-stu-id="21411-562">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

- <span data-ttu-id="21411-563">**以向量保留文字：** 現在當您在 Excel、Word 和 PowerPoint 中轉換地圖、圖表和其他 SVG 向量等物件時，您可以保留物件中的文字。</span><span class="sxs-lookup"><span data-stu-id="21411-563">**Retain text in vectors:** Now you can retain the text in maps, charts, and other SVG vectors when converting these objects in Excel, Word, and PowerPoint.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-566">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-566">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="21411-567">Access</span><span class="sxs-lookup"><span data-stu-id="21411-567">Access</span></span>

- <span data-ttu-id="21411-568">此修正會解決嘗試執行之前會產生「查詢太複雜」錯誤訊息的特定查詢的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-568">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex".</span></span>

### <a name="excel"></a><span data-ttu-id="21411-569">Excel</span><span class="sxs-lookup"><span data-stu-id="21411-569">Excel</span></span>

- <span data-ttu-id="21411-570">修正在分頁預覽中載入含有多個工作表的活頁簿時，可能會發生錯誤或當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-570">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>


### <a name="outlook"></a><span data-ttu-id="21411-571">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-571">Outlook</span></span>

- <span data-ttu-id="21411-572">解決會導致 CLP 使用者在回覆時的寄件者地址，從受保護的內容切換到未受保護的內容時會發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-572">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>


- <span data-ttu-id="21411-573">解決會導致若「未」核取 [下載共用資料夾]，共用行事曆會議的 [回應選項] 中會遺失 [允許轉寄] 選項的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-573">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>


- <span data-ttu-id="21411-574">解決在編輯經理行事曆上的現有行事曆約會時，導致代理人收到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-574">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>


- <span data-ttu-id="21411-575">解決了當選取安全性對話方塊上的 [儲存] 選項時，導致使用者無法將 OneDrive 外部的 OneDrive 附件儲存至他們的本機電腦的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-575">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="21411-576">解決導致 [排程助理員] 頁面無法顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-576">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>

- <span data-ttu-id="21411-577">解決事件通知警示中導致格式設定問題的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-577">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>

### <a name="project"></a><span data-ttu-id="21411-578">Project</span><span class="sxs-lookup"><span data-stu-id="21411-578">Project</span></span>

- <span data-ttu-id="21411-579">修正 [指派資源] 對話方塊中選取的工作與工作面板檢視中所選工作不同的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-579">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>

- <span data-ttu-id="21411-580">修正當您貼上的工作具有多個依存性時，無法正確複製所有依存性的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-580">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>

- <span data-ttu-id="21411-581">修正無法將 PDF/XPS 從 Project 儲存至 SharePoint 文件庫的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-581">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>


### <a name="office-suite"></a><span data-ttu-id="21411-582">Office 套件</span><span class="sxs-lookup"><span data-stu-id="21411-582">Office Suite</span></span>

- <span data-ttu-id="21411-583">修正即使完整產品的轉換已完成，也會導致執行階段訊息顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-583">Fixed an issue that caused a runtime message to show even though the transition to the full product is complete.</span></span> <span data-ttu-id="21411-584">此問題的修正程式是確保服務正確計算新增的產品。</span><span class="sxs-lookup"><span data-stu-id="21411-584">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="21411-585">我們已篩選出新增的產品 (確保它們同時存在於新的設定中)，並將它們新增到現有產品發行識別碼的結尾。</span><span class="sxs-lookup"><span data-stu-id="21411-585">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-july-28"></a><span data-ttu-id="21411-587">版本 2006：7 月 28 日</span><span class="sxs-lookup"><span data-stu-id="21411-587">Version 2006: July 28</span></span>
<span data-ttu-id="21411-588">*版本 2006 (組建 13001.20498)*</span><span class="sxs-lookup"><span data-stu-id="21411-588">*Version 2006 (Build 13001.20498)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-590">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-590">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="21411-591">Excel</span><span class="sxs-lookup"><span data-stu-id="21411-591">Excel</span></span>

- <span data-ttu-id="21411-592">修正在分頁預覽中載入含有多個工作表的活頁簿時，可能會發生錯誤或當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-592">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>


### <a name="outlook"></a><span data-ttu-id="21411-593">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-593">Outlook</span></span>

- <span data-ttu-id="21411-594">我們已修正複製和貼上 SVG 影像的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-594">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="word"></a><span data-ttu-id="21411-595">Word</span><span class="sxs-lookup"><span data-stu-id="21411-595">Word</span></span>

- <span data-ttu-id="21411-596">我們已修正複製和貼上 SVG 影像的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-596">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="office-suite"></a><span data-ttu-id="21411-597">Office 套件</span><span class="sxs-lookup"><span data-stu-id="21411-597">Office Suite</span></span>

- <span data-ttu-id="21411-598">關閉 Office 檔案時，計時問題可能會導致當機。</span><span class="sxs-lookup"><span data-stu-id="21411-598">A timing issue could cause a crash when closing office files.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-july-14"></a><span data-ttu-id="21411-600">版本 2006：7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="21411-600">Version 2006: July 14</span></span>
<span data-ttu-id="21411-601">*版本 2006 (組建 13001.20384)*</span><span class="sxs-lookup"><span data-stu-id="21411-601">*Version 2006 (Build 13001.20384)*</span></span>

<span data-ttu-id="21411-602">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="21411-602">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-604">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-604">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="21411-605">Access</span><span class="sxs-lookup"><span data-stu-id="21411-605">Access</span></span>

- <span data-ttu-id="21411-606">解決插入含有身分識別 (例如，自動編號) 欄位的連結 SQL 資料表的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-606">Resolved an issue with inserting linked SQL tables that include an identity (e.g. autonumber) field.</span></span>

### <a name="excel"></a><span data-ttu-id="21411-607">Excel</span><span class="sxs-lookup"><span data-stu-id="21411-607">Excel</span></span>

- <span data-ttu-id="21411-608">自動文件分類可能已對處於唯讀模式的活頁簿發生。</span><span class="sxs-lookup"><span data-stu-id="21411-608">Automatic document classification may have occurred for workbooks that were in read-only mode.</span></span>

- <span data-ttu-id="21411-609">修正若您已從帳戶登出，嘗試建立資料連線時，可能會發生的當機問題。</span><span class="sxs-lookup"><span data-stu-id="21411-609">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

### <a name="onenote"></a><span data-ttu-id="21411-610">OneNote</span><span class="sxs-lookup"><span data-stu-id="21411-610">OneNote</span></span>

- <span data-ttu-id="21411-611">改善共同撰寫狀態的偵測，以降低資源利用率。</span><span class="sxs-lookup"><span data-stu-id="21411-611">Improve detection of co-authoring status to reduce resource utilization.</span></span>

### <a name="outlook"></a><span data-ttu-id="21411-612">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-612">Outlook</span></span>

- <span data-ttu-id="21411-613">解決了當選取安全性對話方塊上的 [儲存] 選項時，導致使用者無法將 OneDrive 外部的 OneDrive 附件儲存至他們的本機電腦的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-613">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="office-suite"></a><span data-ttu-id="21411-614">Office 套件</span><span class="sxs-lookup"><span data-stu-id="21411-614">Office Suite</span></span>

- <span data-ttu-id="21411-615">我們會將新的 AppV51 向後移，以修正先前 AppV51 中的回歸。</span><span class="sxs-lookup"><span data-stu-id="21411-615">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="21411-616">解決在登錄 TabProcGrowth 值為 REG_SZ 類型的情況下啟用增益集時，Windows 中的 Office 主機會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-616">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-june-30"></a><span data-ttu-id="21411-618">版本 2006：6 月 30 日</span><span class="sxs-lookup"><span data-stu-id="21411-618">Version 2006: June 30</span></span>
<span data-ttu-id="21411-619">*版本2006（組建13001.20266）*</span><span class="sxs-lookup"><span data-stu-id="21411-619">*Version 2006 (Build 13001.20266)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="21411-621">功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-621">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="21411-622">Excel</span><span class="sxs-lookup"><span data-stu-id="21411-622">Excel</span></span>

- <span data-ttu-id="21411-623">**較長的檔案名稱：** Windows 桌面版專用 Excel 現在支援使用最多 400 個字元名稱和路徑的 OneDrive/SharePoint 檔案。</span><span class="sxs-lookup"><span data-stu-id="21411-623">**Longer file names:** Excel for Windows desktop now supports OneDrive/SharePoint files with names and paths of up to 400 characters.</span></span>

- <span data-ttu-id="21411-624">**RealTimeData (RTD) 的改進：** 在 Office 365 版本 2002 的每月通道或更新版本中，Excel RealTimeData (RTD) 函數速度比在 Excel 2010 試算表中計算資料還快。</span><span class="sxs-lookup"><span data-stu-id="21411-624">**Realtimedata (RTD) improvements:** In Office 365 version 2002 monthly channel and later, Excel's RealTimeData (RTD) function is much faster than Excel 2010 calculating data in the spreadsheet.</span></span> <span data-ttu-id="21411-625">我們在其基礎記憶體和資料結構中移除了瓶頸，並使其成為安全執行緒，讓它可在多執行緒重新計算 (MTR) 的所有可用執行緒上計算。</span><span class="sxs-lookup"><span data-stu-id="21411-625">We removed bottlenecks in its underlying memory and data structures as well as made it thread-safe to allow  it to be calculated on all available threads of Multithreaded recalculation (MTR).</span></span>

### <a name="outlook"></a><span data-ttu-id="21411-626">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-626">Outlook</span></span>

- <span data-ttu-id="21411-627">**在 Outlook 中撰寫郵件時有新的選項可停用 @ 提及建議：** 您是否覺得 @ 提及的選擇器很煩人，一點都不好用？</span><span class="sxs-lookup"><span data-stu-id="21411-627">**New option to disable @ mention suggestions when composing mail in Outlook:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="21411-628">現在您可以視需要將其關閉了。</span><span class="sxs-lookup"><span data-stu-id="21411-628">Now you can turn it off if you prefer.</span></span><br /><span data-ttu-id="21411-629">在[部落格文章](https://blog-insider.office.com/2020/03/26/feedback-in-action-disable-mentions/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="21411-629">See details in [blog post](https://blog-insider.office.com/2020/03/26/feedback-in-action-disable-mentions/)</span></span>

- <span data-ttu-id="21411-630">**IT 系統管理員的事件通知：** Microsoft 365 租用戶全域系統管理員和 Office 應用程式系統會在 Windows 版 Outlook 的新右側面板中收到影響其使用者的 Outlook 和 O365 Exchange 事件通知。</span><span class="sxs-lookup"><span data-stu-id="21411-630">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="21411-631">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-631">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

- <span data-ttu-id="21411-632">**新增至 Outlook 快顯通知的其他按鈕：**[快速動作] 按鈕現在會於在 Windows 10 上執行 Outlook 時顯示在 Outlook 快顯通知中</span><span class="sxs-lookup"><span data-stu-id="21411-632">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10</span></span>

### <a name="powerpoint"></a><span data-ttu-id="21411-633">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="21411-633">PowerPoint</span></span>

- <span data-ttu-id="21411-634">**改善的 PowerPoint 中的 Steam 影片效能：** 我們改善了 Microsoft Stream 影片的播放效能，將影片載入時間減至最少，以建立出流暢的觀賞體驗。</span><span class="sxs-lookup"><span data-stu-id="21411-634">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="21411-635">您可以在 Microsoft Stream 上使用公司影片來建立更完善的簡報。</span><span class="sxs-lookup"><span data-stu-id="21411-635">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

### <a name="teams"></a><span data-ttu-id="21411-636">Teams</span><span class="sxs-lookup"><span data-stu-id="21411-636">Teams</span></span>

- <span data-ttu-id="21411-637">**針對外部使用者遮罩 PSTN 參與者電話號碼：** 針對為其 Teams 會議啟用音訊會議的客戶，我們會對從組織外部加入的使用者，將 PSTN 參與者的電話號碼遮罩起來。</span><span class="sxs-lookup"><span data-stu-id="21411-637">**PSTN participant phone numbers are masked from external users:** For customers with Audio Conferencing enabled for their Teams meetings, we will mask the PSTN participant's phone number to users who have joined from outside of your organization.</span></span>

- <span data-ttu-id="21411-638">**管理您的頻道通知設定的簡化方式：** 透過團隊和頻道清單或從頻道標頭，使用者只要按一下即可將所有活動開啟或關閉就能快速管理其通知設定，或深入了解自訂以快速設定其偏好的通知排列組合。</span><span class="sxs-lookup"><span data-stu-id="21411-638">**Simplified way to manage your channel notification settings:** Through the teams and channels list or from the channel header, the users can quickly manage their notification settings by turning all activity on or off with a single click or diving deep into custom to set their preferred permutations.</span></span>

- <span data-ttu-id="21411-639">**Walkie Talkie：** 使用按著即可發言即時語音通訊。</span><span class="sxs-lookup"><span data-stu-id="21411-639">**Walkie Talkie:** Instant voice communication using push-to-talk.</span></span>

### <a name="word"></a><span data-ttu-id="21411-640">Word</span><span class="sxs-lookup"><span data-stu-id="21411-640">Word</span></span>

- <span data-ttu-id="21411-641">**螢幕閱讀器的動作確認：** 確認動作是重要的協助工具要求。</span><span class="sxs-lookup"><span data-stu-id="21411-641">**Confirmation of action in screen readers:** Confirmation of action is an important accessibility requirement.</span></span> <span data-ttu-id="21411-642">隨著 Windows 引入新的通知 API 之後，我們現在就能通知螢幕助讀程式使用者的動作成功。</span><span class="sxs-lookup"><span data-stu-id="21411-642">With the introduction of a new Notification API from Windows, we are now able to alert screen reader users about the success of their actions.</span></span> <span data-ttu-id="21411-643">[剪下]、[複製]、[貼上]、[粗體]、[畫底線]、[復原]、[重做]、[自動校正] 和 [自動大小寫] 等功能都已公布給 Win32 Word 的朗讀程式使用者。</span><span class="sxs-lookup"><span data-stu-id="21411-643">Cut, copy, paste, bold, italic, underline, undo, redo, auto corrections, and auto-capitalizations are now all announced to Narrator users in Win32 Word.</span></span> <span data-ttu-id="21411-644">若要啟用此功能，請按 windows + ctrl + enter 以開啟朗讀程式。</span><span class="sxs-lookup"><span data-stu-id="21411-644">To enable this feature, turn on Narrator by pressing windows + ctrl + enter.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-647">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-647">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="21411-648">Access</span><span class="sxs-lookup"><span data-stu-id="21411-648">Access</span></span>

- <span data-ttu-id="21411-649">我們已修正執行查詢的時間大約比預期完成時間兩倍久的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-649">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>


### <a name="excel"></a><span data-ttu-id="21411-650">Excel</span><span class="sxs-lookup"><span data-stu-id="21411-650">Excel</span></span>

- <span data-ttu-id="21411-651">修正當儲存至 SharePoint/OneDrive 時，會導致自訂功能區索引標籤 CustomUI XML 的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-651">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>


### <a name="outlook"></a><span data-ttu-id="21411-652">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-652">Outlook</span></span>

- <span data-ttu-id="21411-653">解決會導致使用者看到他們透過拖放附件，以複製到其檔案系統所建立附件的建立日期設為 4501 年 1 月 1 日的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-653">Addressed an issue that caused users to see the creation date of attachments that they copied to their file system via drag and drop getting set to January 1, 4501.</span></span>

- <span data-ttu-id="21411-654">解決會導致共用行事曆改善功能的使用者看到行事曆失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-654">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>


- <span data-ttu-id="21411-655">解決會導致使用者看到 Outlook 持續提示他們執行收件匣修復工具的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-655">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>


- <span data-ttu-id="21411-656">解決啟用雲端設定時，會造成 Ctrl + 按一下停止運作的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-656">Addressed an issue that caused Ctrl+click to stop working when cloud settings were enabled.</span></span>


- <span data-ttu-id="21411-657">解決會導致在「建議功能」中尋找功能不會傳回結果，因而讓使用者無法選擇提交新功能想法的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-657">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>


### <a name="project"></a><span data-ttu-id="21411-658">Project</span><span class="sxs-lookup"><span data-stu-id="21411-658">Project</span></span>

- <span data-ttu-id="21411-659">修正 URL 以 .com 結尾時，無法從 Project Web App 在 Project 傳統型用戶端開啟專案的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-659">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>


- <span data-ttu-id="21411-660">修正當專案摘要工作-或是專案[開始/工作]欄位有變更時，ProjectBeforeTaskChange 事件不會觸發的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-660">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>


- <span data-ttu-id="21411-661">修正當標示為100% 完成之工作錯誤地變更為完成度低於100% 的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-661">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>


### <a name="word"></a><span data-ttu-id="21411-662">Word</span><span class="sxs-lookup"><span data-stu-id="21411-662">Word</span></span>

- <span data-ttu-id="21411-663">解決 URL 包含查詢元件時，從自訂文件傳遞 (aspx) 開啟 Word 文件的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-663">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-june-24"></a><span data-ttu-id="21411-665">版本 2005：6 月 24 日</span><span class="sxs-lookup"><span data-stu-id="21411-665">Version 2005: June 24</span></span>
<span data-ttu-id="21411-666">*版本 2005 (組建 12827.20470)*</span><span class="sxs-lookup"><span data-stu-id="21411-666">*Version 2005 (Build 12827.20470)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-668">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-668">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="21411-669">存取</span><span class="sxs-lookup"><span data-stu-id="21411-669">Access</span></span>

- <span data-ttu-id="21411-p155">現已修正此錯誤；您應該可以呼叫日期/時間延伸資料類型至您的程式碼，而不會在您的應用程式中遇到任何當機。請讓團隊知道您是否遇到其他問題。</span><span class="sxs-lookup"><span data-stu-id="21411-p155">This bug has now been fixed; you should be able to call the Date/Time Extended data type into your code without experiencing any crash in your app. Please let the team know if you encounter further issues.</span></span>


- <span data-ttu-id="21411-672">現已修正此問題；您現在可以還原為最新的 Access 版本，並使用 DAO/VBA 來管理及編輯十進位資料類型。</span><span class="sxs-lookup"><span data-stu-id="21411-672">This issue has now been fixed; you can now revert back to your most updated Access version, and use DAO/VBA to manage and edit a decimal data type.</span></span> <span data-ttu-id="21411-673">如果您在使用我們的資料類型時遇到任何進一步問題，請讓 Access 團隊知道。</span><span class="sxs-lookup"><span data-stu-id="21411-673">Please let the Access team know if you encounter any further issues with using our data type.</span></span>


### <a name="excel"></a><span data-ttu-id="21411-674">Excel</span><span class="sxs-lookup"><span data-stu-id="21411-674">Excel</span></span>

- <span data-ttu-id="21411-675">修正當儲存至 SharePoint/OneDrive 時，會導致自訂功能區索引標籤 CustomUI XML 的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-675">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>





### <a name="outlook"></a><span data-ttu-id="21411-676">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-676">Outlook</span></span>

- <span data-ttu-id="21411-677">解決了 Outlook 無法啟用 [資料遺失保護原則] 提示使用 M365 商務版進階方案並為此服務付款的的使用者之問題。</span><span class="sxs-lookup"><span data-stu-id="21411-677">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>


- <span data-ttu-id="21411-678">解決會導致使用者看到他們透過拖放附件，以複製到其檔案系統所建立附件的建立日期設為 4501 年 1 月 1 日的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-678">Addressed an issue that caused users to see the creation date of attachments that they copied to their file system via drag and drop getting set to January 1, 4501.</span></span>


- <span data-ttu-id="21411-679">解決會導致使用者在 Outlook 中更新其規則時，看到&quot;此電腦上的規則與 Microsoft Exchange 上的規則不相符&quot;訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-679">Addressed an issue that caused users to see the &quot;The rules on this computer do not match the rules on Microsoft Exchange&quot; message when updating their rules in Outlook.</span></span>


- <span data-ttu-id="21411-680">解決會導致共用行事曆改善功能的使用者看到行事曆失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-680">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>


- <span data-ttu-id="21411-681">解決會導致使用者在某些情況下遇到間歇性懸置和當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-681">Addressed an issue that caused users to experience intermittent hangs and crashes in some scenarios.</span></span>


- <span data-ttu-id="21411-682">解決會導致使用者看到 Outlook 持續提示他們執行收件匣修復工具的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-682">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>


- <span data-ttu-id="21411-683">解決會導致在「建議功能」中尋找功能不會傳回結果，因而讓使用者無法選擇提交新功能想法的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-683">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="21411-684">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="21411-684">PowerPoint</span></span>

- <span data-ttu-id="21411-685">我們已修正建議窗格的當機問題。</span><span class="sxs-lookup"><span data-stu-id="21411-685">We have fixed a crash issue with suggestion pane.</span></span>


### <a name="project"></a><span data-ttu-id="21411-686">Project</span><span class="sxs-lookup"><span data-stu-id="21411-686">Project</span></span>

- <span data-ttu-id="21411-687">修正當標示為100% 完成之工作錯誤地變更為完成度低於100% 的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-687">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

### <a name="word"></a><span data-ttu-id="21411-688">Word</span><span class="sxs-lookup"><span data-stu-id="21411-688">Word</span></span>

- <span data-ttu-id="21411-689">解決會導致從應用程式拖曳部分內容時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-689">Resolved an issue that may have caused a crash when dragging some content from the app.</span></span>


### <a name="office-suite"></a><span data-ttu-id="21411-690">Office 套件</span><span class="sxs-lookup"><span data-stu-id="21411-690">Office Suite</span></span>

- <span data-ttu-id="21411-691">此變更會解決載入和播放動畫內容 (例如 Gif 或3D 模型) 時可能會發生的懸置。</span><span class="sxs-lookup"><span data-stu-id="21411-691">This change addresses potential hangs when loading and playing animated content such as GIFs or 3D models.</span></span>




[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-june-09"></a><span data-ttu-id="21411-693">版本 2005：6 月 9 日</span><span class="sxs-lookup"><span data-stu-id="21411-693">Version 2005: June 09</span></span>
<span data-ttu-id="21411-694">*版本 2005 (組建 12827.20336)*</span><span class="sxs-lookup"><span data-stu-id="21411-694">*Version 2005 (Build 12827.20336)*</span></span>

<span data-ttu-id="21411-695">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="21411-695">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

### <a name="feature-updates"></a><span data-ttu-id="21411-696">功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-696">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="21411-697">Excel</span><span class="sxs-lookup"><span data-stu-id="21411-697">Excel</span></span>

- <span data-ttu-id="21411-698">**[筆跡工具箱] 中的 [套索工具] 和 [橡皮擦]:** 使用繪圖工具時，[筆跡工具箱] 現在提供 [套索工具] 和 [橡皮擦] 功能。</span><span class="sxs-lookup"><span data-stu-id="21411-698">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="21411-699">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="21411-699">PowerPoint</span></span>

- <span data-ttu-id="21411-700">**[筆跡工具箱] 中的 [套索工具] 和 [橡皮擦]:** 使用繪圖工具時，[筆跡工具箱] 現在提供 [套索工具] 和 [橡皮擦] 功能。</span><span class="sxs-lookup"><span data-stu-id="21411-700">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span>

### <a name="word"></a><span data-ttu-id="21411-701">Word</span><span class="sxs-lookup"><span data-stu-id="21411-701">Word</span></span>

- <span data-ttu-id="21411-702">**[筆跡工具箱] 中的 [套索工具] 和 [橡皮擦]:** 使用繪圖工具時，[筆跡工具箱] 現在提供 [套索工具] 和 [橡皮擦] 功能。</span><span class="sxs-lookup"><span data-stu-id="21411-702">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span>




[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-705">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-705">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="21411-706">Excel</span><span class="sxs-lookup"><span data-stu-id="21411-706">Excel</span></span>

- <span data-ttu-id="21411-707">解決嘗試將樞紐分析表插入圖表時 Excel 可能會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-707">Addresses an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="21411-708">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="21411-708">PowerPoint</span></span>

- <span data-ttu-id="21411-709">這可修正使用者在同一檔案中同時有新版和舊版批註，因此觸發批註的升級而當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-709">This fixes a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>

### <a name="project"></a><span data-ttu-id="21411-710">Project</span><span class="sxs-lookup"><span data-stu-id="21411-710">Project</span></span>

- <span data-ttu-id="21411-711">修正當專案摘要工作-或是專案[開始/工作]欄位有變更時，ProjectBeforeTaskChange 事件不會觸發的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-711">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

### <a name="office-suite"></a><span data-ttu-id="21411-712">Office 套件</span><span class="sxs-lookup"><span data-stu-id="21411-712">Office Suite</span></span>

- <span data-ttu-id="21411-713">我們透過設定Bing附加預設安裝驗證設定為true默認，並將MSI返回成功視為安裝成功，而解決了 ValidateInstall 失敗率問題。</span><span class="sxs-lookup"><span data-stu-id="21411-713">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-june-02"></a><span data-ttu-id="21411-715">版本 2005：6 月 2 日</span><span class="sxs-lookup"><span data-stu-id="21411-715">Version 2005: June 02</span></span>
<span data-ttu-id="21411-716">*版本2005（組建12827.20268）*</span><span class="sxs-lookup"><span data-stu-id="21411-716">*Version 2005 (Build 12827.20268)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="21411-718">功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-718">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="21411-719">Excel</span><span class="sxs-lookup"><span data-stu-id="21411-719">Excel</span></span>

- <span data-ttu-id="21411-720">**自動使用新的資料類型**：當您輸入的資料值類似股票或地理位置時，Excel 會將該值轉換為正確的連結資料類型 - 股票或地理位置。</span><span class="sxs-lookup"><span data-stu-id="21411-720">**Automatically use new data types:** When you type a data value that resembles a stock or a geographic location, Excel offers to convert it to the right connected data type - Stocks or Geography.</span></span> [<span data-ttu-id="21411-721">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-721">Learn more</span></span>](https://support.office.com/article/61a33056-9935-484f-8ac8-f1a89e210877)

- <span data-ttu-id="21411-722">**使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦</span><span class="sxs-lookup"><span data-stu-id="21411-722">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier</span></span>

### <a name="outlook"></a><span data-ttu-id="21411-723">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-723">Outlook</span></span>

- <span data-ttu-id="21411-724">**協助保護群組中的資料：** 建立群組時所選擇的「敏感度」標籤會套用到群組電子郵件、文件及小組網站</span><span class="sxs-lookup"><span data-stu-id="21411-724">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites</span></span>

- <span data-ttu-id="21411-725">**更好的結果—瞬間：** 我們更新了搜尋體驗，讓這個版本比以往更聰明、更快速，且更可靠。</span><span class="sxs-lookup"><span data-stu-id="21411-725">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="21411-726">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-726">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="21411-727">**使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦</span><span class="sxs-lookup"><span data-stu-id="21411-727">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier</span></span>

- <span data-ttu-id="21411-728">**行事曆煥然一新：** 查看視覺更新，讓您的行事曆更容易流覽。</span><span class="sxs-lookup"><span data-stu-id="21411-728">**Calendar gets a makeover:** See visual updates that make your calendar easier to scan.</span></span> [<span data-ttu-id="21411-729">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-729">Learn more</span></span>](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br /><span data-ttu-id="21411-730">在[部落格文章](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="21411-730">See details in [blog post](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="21411-731">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="21411-731">PowerPoint</span></span>

- <span data-ttu-id="21411-732">**使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦 [深入了解](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)</span><span class="sxs-lookup"><span data-stu-id="21411-732">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier [Learn more](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)</span></span>

- <span data-ttu-id="21411-733">**在簡報時同步處理變更：** 即使簡報處於投影片放映模式，仍可即時同步處理所做的變更。</span><span class="sxs-lookup"><span data-stu-id="21411-733">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span> [<span data-ttu-id="21411-734">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-734">Learn more</span></span>](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br /><span data-ttu-id="21411-735">在[部落格文章](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="21411-735">See details in [blog post](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span></span>

- <span data-ttu-id="21411-736">**不需要簡報導覽裝置：有耳塞式耳機就夠了：** 使用您的 Surface Earbuds 控制 PowerPoint 簡報。</span><span class="sxs-lookup"><span data-stu-id="21411-736">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="21411-737">運作方式：配對之後，您必須在 PowerPoint 中啟用功能。</span><span class="sxs-lookup"><span data-stu-id="21411-737">How it works:  Once paired, you'll need to enable the feature in PowerPoint.</span></span> <span data-ttu-id="21411-738">按 F5 或選取 [投影片放映] > [從開頭] 開始簡報。</span><span class="sxs-lookup"><span data-stu-id="21411-738">Start a presentation by pressing F5 or selecting Slide Show > From Beginning.</span></span>  <span data-ttu-id="21411-739">在投影片放映中，以滑鼠右鍵按一下投影片，然後在 [Surface Earbuds 設定] 底下，選擇 [使用手勢來控制簡報]。</span><span class="sxs-lookup"><span data-stu-id="21411-739">In Slide Show, right click on the slide and under Surface Earbuds Settings choose Use Gestures to Control Presentation.</span></span>  <span data-ttu-id="21411-740">將記住此設定以用於所有未來的簡報。</span><span class="sxs-lookup"><span data-stu-id="21411-740">This setting will be remembered for all future presentations.</span></span> <span data-ttu-id="21411-741">現在，您可以在左耳機上向前後撥動，以在 [投影片放映] 模式中瀏覽簡報。</span><span class="sxs-lookup"><span data-stu-id="21411-741">You can now can swipe forward and backward on the left earbud to navigate your presentations in Slide Show mode.</span></span>  <span data-ttu-id="21411-742">點兩下以播放或暫停內嵌的影片。</span><span class="sxs-lookup"><span data-stu-id="21411-742">Double tap to play or pause embedded videos.</span></span>  <span data-ttu-id="21411-743">重要：您必須在 Windows 10 的 Surface 音訊應用程式中配對 Surface Earbuds，才能使用手勢來控制簡報。</span><span class="sxs-lookup"><span data-stu-id="21411-743">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="21411-744">在此取得 Windows 10 上 Surface 音訊應用程式入門的指示。</span><span class="sxs-lookup"><span data-stu-id="21411-744">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="21411-745">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-745">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

### <a name="teams"></a><span data-ttu-id="21411-746">Teams</span><span class="sxs-lookup"><span data-stu-id="21411-746">Teams</span></span>

- <span data-ttu-id="21411-747">**對 Teams 會議中視訊版面配置所做的變更：** 在 Teams 會議期間可同時檢視的參與者人數，很快地將從 4 個增加到 9 個。</span><span class="sxs-lookup"><span data-stu-id="21411-747">**Changes to video layout in Teams meetings:** Soon, the number of participants that can be viewed simultaneously during a Teams meeting will increase from 4 to 9.</span></span>

- <span data-ttu-id="21411-748">**在即時活動中包含系統音訊：** 即時活動中的簡報者和製作人，現在可以在即時活動期間共用桌面或視窗螢幕時包含系統音訊。</span><span class="sxs-lookup"><span data-stu-id="21411-748">**Include system audio in live events:** Presenters and producers in live events can now include system audio when sharing a desktop or window screen during the live event.</span></span> <span data-ttu-id="21411-749">這可讓您的使用者聽到您正在共用內容的任何音訊部分。</span><span class="sxs-lookup"><span data-stu-id="21411-749">This will allow your users to hear any audio part of the content you are sharing.</span></span>

- <span data-ttu-id="21411-750">**讓召集人可以變更撥入參與者的大廳設定：** 此設定會控制透過電話撥入的人員是否直接加入會議，或是在大廳中等候，而不論 [自動准許人員] 的設定為何。</span><span class="sxs-lookup"><span data-stu-id="21411-750">**Enable organizers to change lobby settings for dial-in participants:** This setting controls whether people who dial in by phone join the meeting directly or wait in the lobby regardless of the Automatically admit people setting.</span></span>

- <span data-ttu-id="21411-751">**在會議中舉手：** 使用者現在可以在會議中虛擬舉手！</span><span class="sxs-lookup"><span data-stu-id="21411-751">**Raise Your Hand in Meetings:** Users can now raise a virtual hand in a meeting!</span></span> <span data-ttu-id="21411-752">其他參與者會在會議舞台中您的名稱旁和名冊中您的名字旁看到您的舉手。</span><span class="sxs-lookup"><span data-stu-id="21411-752">Other participants will see your raised hand next to your name in the meeting stage and next to your name in the roster.</span></span>

- <span data-ttu-id="21411-753">**自訂會議視訊背景：** 使用視訊會議時，您現在可以選擇要使用的不同靜態背景影像。</span><span class="sxs-lookup"><span data-stu-id="21411-753">**Customize meeting video backgrounds:** When you are meeting with video, you now have the choice of different static background images to use.</span></span> <span data-ttu-id="21411-754">這可讓您顯示此影像，而不是您所在位置的實際背景。</span><span class="sxs-lookup"><span data-stu-id="21411-754">This will let you show this image and not the actual background of where you are sitting.</span></span>

- <span data-ttu-id="21411-755">**新增更多人員至聊天：** 我們現在可以將最多 350 個人新增至單一聊天對話。</span><span class="sxs-lookup"><span data-stu-id="21411-755">**Add more people to chat:** We made it possible to now add up to 350 people to a single chat thread.</span></span>

- <span data-ttu-id="21411-756">**您的活動摘要上設定齒輪：** 使用者現在可以從摘要左側滑軌透過設定齒輪的方式，直接存取活動摘要和通知設定。</span><span class="sxs-lookup"><span data-stu-id="21411-756">**Settings Gear on your Activity Feed:** Users can now directly access activity feed and notification setting from the feed left rail by the means of a settings gear.</span></span>

- <span data-ttu-id="21411-757">**從 Teams 進行中的會議內輕鬆存取會議選項：** 我們讓會議召集人在 Teams 會議一開始，便能更快速且輕鬆地變更簡報者和大廳設定，方法是在參與者窗格中直接提供易於存取的連結。</span><span class="sxs-lookup"><span data-stu-id="21411-757">**Easily access meeting options from within a Teams meeting in progress:** We are making it easier for meeting organizers to quickly and easily change their presenter and lobby settings once a Teams meeting starts by providing an easy to access link directly in the participants pane.</span></span> <span data-ttu-id="21411-758">此新功能將會同時對已排定和「立即開會」會議呈現。</span><span class="sxs-lookup"><span data-stu-id="21411-758">This new functionality will be present for both scheduled and “Meet Now” meetings.</span></span>

- <span data-ttu-id="21411-759">**團隊與頻道分析**：除了團隊分析以外，您現在也可以檢視頻道層級指標和深入資訊。</span><span class="sxs-lookup"><span data-stu-id="21411-759">**Team and channel analytics:** In addition to team analytics, now you can also view channel level metrics and insights.</span></span> <span data-ttu-id="21411-760">我們也將時間週期增加到 90 天，使得您可以分析資料的時間較長。</span><span class="sxs-lookup"><span data-stu-id="21411-760">We've also enhanced the time period to 90 days so you can analyze data for longer periods.</span></span> <span data-ttu-id="21411-761">除此以外，此版本還包含有關小組或頻道的文章、回覆和會議計數的新計量和圖表。</span><span class="sxs-lookup"><span data-stu-id="21411-761">Apart from that, this release also includes new metrics and charts around count of posts, replies and meetings for a team or channel.</span></span>

- <span data-ttu-id="21411-762">**進入/結束宣告：** 我們新增了此功能，讓會議召集人能夠開啟或關閉會議的進入和結束宣告。</span><span class="sxs-lookup"><span data-stu-id="21411-762">**Entry/exit announcements:** We added this feature that lets meeting organizers have the ability to turn on or off entry and exit announcements for a meeting.</span></span>

### <a name="word"></a><span data-ttu-id="21411-763">Word</span><span class="sxs-lookup"><span data-stu-id="21411-763">Word</span></span>

- <span data-ttu-id="21411-764">**解碼縮寫，而不需離開 Word：** 當您遇到縮寫時，Word 會試著根據其他人的使用方式來給予定義。</span><span class="sxs-lookup"><span data-stu-id="21411-764">**Decode acronyms without leaving Word:** When you encounter an acronym, Word will try to define it based on how others use it.</span></span>

- <span data-ttu-id="21411-765">**使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦</span><span class="sxs-lookup"><span data-stu-id="21411-765">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-768">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-768">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="21411-769">Excel</span><span class="sxs-lookup"><span data-stu-id="21411-769">Excel</span></span>

- <span data-ttu-id="21411-770">修正當 Excel 視窗透過 Teams 共用時，使用 Ctrl + Shift + 方向鍵滑動後，Excel 可能會無法回應的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-770">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="21411-771">在某些情況下，按一下同一個活頁簿中某個位置的超連結會導致活頁簿被隱藏。</span><span class="sxs-lookup"><span data-stu-id="21411-771">In some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>

### <a name="outlook"></a><span data-ttu-id="21411-772">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-772">Outlook</span></span>

- <span data-ttu-id="21411-773">已解決有回應/轉寄標註的clp審查活動的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-773">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>

- <span data-ttu-id="21411-774">解決會導致 Windows 10 伺服器版本的使用者看到警告「防毒軟體狀態: 無效」的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-774">Addressed an issue that caused users of Windows 10 server versions to see the warning "Antivirus status: Invalid".</span></span> <span data-ttu-id="21411-775">此版本的 Windows 支援防毒軟體偵測，但即使已正確安裝防毒軟體，也找不到防毒軟體。</span><span class="sxs-lookup"><span data-stu-id="21411-775">This version of Windows supports antivirus detection, but no antivirus was found despite having anti virus correctly installed.</span></span>

- <span data-ttu-id="21411-776">解決從系統管理員通知提交意見反應時，會導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-776">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>

### <a name="skype"></a><span data-ttu-id="21411-777">Skype</span><span class="sxs-lookup"><span data-stu-id="21411-777">Skype</span></span>

- <span data-ttu-id="21411-778">當使用者收到將他們移至 Teams Only 的原則時，他們仍然可以使用商務版 Skype Outlook 增益集來排程會議。</span><span class="sxs-lookup"><span data-stu-id="21411-778">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span> <span data-ttu-id="21411-779">在此更新之後，當客戶端讀取指示用戶為 Teams Only 的策略並進入僅限會議加入模式後，您將不再能用商務版 Skype 安排會議。</span><span class="sxs-lookup"><span data-stu-id="21411-779">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span> <span data-ttu-id="21411-780">此外，如果商務版 Skype Outlook 增益集發現商務版 Skype 用戶端處於 [僅限會議加入] 模式，就無法自行啟動。</span><span class="sxs-lookup"><span data-stu-id="21411-780">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

### <a name="office-suite"></a><span data-ttu-id="21411-781">Office 套件</span><span class="sxs-lookup"><span data-stu-id="21411-781">Office Suite</span></span>

- <span data-ttu-id="21411-782">此更新修正了 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。</span><span class="sxs-lookup"><span data-stu-id="21411-782">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="21411-783">此更新解決了 Microsoft Office 中的一個問題：可能無法在執行時期正確找到 Visual Basic for Applications 專案，這些專案的參照預期透搜尋 PATH 環境變數指定的位置來找到，進而導致VBA 執行時期錯誤。</span><span class="sxs-lookup"><span data-stu-id="21411-783">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="21411-p169">當登錄機碼 HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth 設為零，且正在啟用增益集時，Office 主機會在 Windows 中當機。此變更可修正此問題。</span><span class="sxs-lookup"><span data-stu-id="21411-p169">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero. This change would fix this issue.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-may-21"></a><span data-ttu-id="21411-787">版本 2004：5 月 21 日</span><span class="sxs-lookup"><span data-stu-id="21411-787">Version 2004: May 21</span></span>
<span data-ttu-id="21411-788">*版本 2004 (組建 12730.20352)*</span><span class="sxs-lookup"><span data-stu-id="21411-788">*Version 2004 (Build 12730.20352)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-790">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-790">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="21411-791">Excel</span><span class="sxs-lookup"><span data-stu-id="21411-791">Excel</span></span>

- <span data-ttu-id="21411-792">修正當檔案路徑太長時，在檔案重新開啟之後外部連結會停止運作的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-792">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>


### <a name="outlook"></a><span data-ttu-id="21411-793">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-793">Outlook</span></span>

- <span data-ttu-id="21411-794">已解決在從系統管理人通知中提交意見反應時，使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-794">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>


### <a name="office-suite"></a><span data-ttu-id="21411-795">Office 套件</span><span class="sxs-lookup"><span data-stu-id="21411-795">Office Suite</span></span>

- <span data-ttu-id="21411-796">修正隨選即用會導致偶爾無法更新至最新組建的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-796">Fixed a Click-to-Run issue which was resulting in occasional update failures to the latest builds.</span></span>

- <span data-ttu-id="21411-797">解決 Microsoft Office 中的 Visual Basic for Applications 專案，其具有的參照預期應透過搜尋 PATH 環境變數指定的位置來找到，但在執行時期中可能無法正確找到，導致 VBA 執行時期錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-797">Fixed an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-may-12"></a><span data-ttu-id="21411-799">版本 2004：5 月 12 日</span><span class="sxs-lookup"><span data-stu-id="21411-799">Version 2004: May 12</span></span>
<span data-ttu-id="21411-800">*版本 2004 (組建 12730.20270)*</span><span class="sxs-lookup"><span data-stu-id="21411-800">*Version 2004 (Build 12730.20270)*</span></span>

<span data-ttu-id="21411-801">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="21411-801">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-803">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-803">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="21411-804">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-804">Outlook</span></span>

- <span data-ttu-id="21411-805">解決在顯示快顯通知時，使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-805">Addresses an issue that caused users to experience a crash when displaying toast notifications.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-may-04"></a><span data-ttu-id="21411-807">版本 2004：5 月 4 日</span><span class="sxs-lookup"><span data-stu-id="21411-807">Version 2004: May 04</span></span>
<span data-ttu-id="21411-808">*版本 2004 (組建 12730.20250)*</span><span class="sxs-lookup"><span data-stu-id="21411-808">*Version 2004 (Build 12730.20250)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-810">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-810">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="21411-811">Office 套件</span><span class="sxs-lookup"><span data-stu-id="21411-811">Office Suite</span></span>

- <span data-ttu-id="21411-812">此更新修正了 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。</span><span class="sxs-lookup"><span data-stu-id="21411-812">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-april-29"></a><span data-ttu-id="21411-814">版本 2004：4 月 29 日</span><span class="sxs-lookup"><span data-stu-id="21411-814">Version 2004: April 29</span></span>
<span data-ttu-id="21411-815">*版本 2004 (組建 12730.20236)*</span><span class="sxs-lookup"><span data-stu-id="21411-815">*Version 2004 (Build 12730.20236)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="21411-817">功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-817">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="21411-818">Access</span><span class="sxs-lookup"><span data-stu-id="21411-818">Access</span></span>

- <span data-ttu-id="21411-819">**在查詢設計工具、SQL 檢視和關聯視窗中工作時更具生產力：** 在資料表上按一下滑鼠右鍵即可開啟、設計、調整大小及隱藏它。</span><span class="sxs-lookup"><span data-stu-id="21411-819">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="21411-820">在 SQL 檢視中搜尋及取代文字。</span><span class="sxs-lookup"><span data-stu-id="21411-820">Search and replace text in SQL View.</span></span> <span data-ttu-id="21411-821">在 [關聯圖] 視窗中選取多個資料表。</span><span class="sxs-lookup"><span data-stu-id="21411-821">Select multiple tables in the Relationships window.</span></span>

- <span data-ttu-id="21411-822">**按幾下就能新增資料表：** 使用 [新增資料表] 工作窗格，當您工作時，該窗格會保持開啟狀態，以便將資料表新增至關聯和查詢。</span><span class="sxs-lookup"><span data-stu-id="21411-822">**Add tables with fewer clicks:** Use the Add Tables task pane, which stays open while you work, to add tables to relationships and queries.</span></span> [<span data-ttu-id="21411-823">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-823">Learn more</span></span>](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)


### <a name="excel"></a><span data-ttu-id="21411-824">Excel</span><span class="sxs-lookup"><span data-stu-id="21411-824">Excel</span></span>

- <span data-ttu-id="21411-825">**Facebook 連接器支援即將結束：** 於 2020 年 4 月起，Excel 就不再支援使用 Facebook 連接器的外部資料連線。</span><span class="sxs-lookup"><span data-stu-id="21411-825">**Facebook connector support is ending:** Starting in April 2020, Excel will no longer support external data connections that use the Facebook connector.</span></span>

- <span data-ttu-id="21411-826">**有問題嗎？詢問 Excel**：現在，Excel 構想可讓您提出有關資料的問題，而不需花時間編寫公式 (僅提供英文版)。</span><span class="sxs-lookup"><span data-stu-id="21411-826">**Have a question? Ask Excel:** Now Excel Ideas allows you to ask questions about your data - no need to spend time writing formulas (available in English only).</span></span> [<span data-ttu-id="21411-827">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-827">Learn more</span></span>](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- <span data-ttu-id="21411-828">**讓活頁簿更生動的新影像：** 您可以在活頁簿中使用的數千個免版稅圖庫影像、圖示和貼紙。</span><span class="sxs-lookup"><span data-stu-id="21411-828">**New images to bring your workbooks to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your workbooks.</span></span> <span data-ttu-id="21411-829">移至 [插入] > [圖片] > [圖庫影像] 以開始使用。</span><span class="sxs-lookup"><span data-stu-id="21411-829">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="21411-830">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-830">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

### <a name="outlook"></a><span data-ttu-id="21411-831">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-831">Outlook</span></span>

- <span data-ttu-id="21411-832">**加入會議而不需離開您的收件匣：** 不需切換至您的行事曆即可加入線上會議。</span><span class="sxs-lookup"><span data-stu-id="21411-832">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="21411-833">將行事曆釘選到 [待辦事項] 窗格之後，只要按一下就能加入任何會議。</span><span class="sxs-lookup"><span data-stu-id="21411-833">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span> [<span data-ttu-id="21411-834">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-834">Learn more</span></span>](https://support.office.com/article/d8baa9d5-0645-41b8-9f36-b498a6c36064 )

- <span data-ttu-id="21411-835">**讓郵件更生動的新影像：** 您可以在電子郵件中使用的數千個免版稅圖庫影像、圖示和貼紙。</span><span class="sxs-lookup"><span data-stu-id="21411-835">**New images to bring your messages to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your email messages.</span></span> <span data-ttu-id="21411-836">移至 [插入] > [圖片] > [圖庫影像] 以開始使用。</span><span class="sxs-lookup"><span data-stu-id="21411-836">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="21411-837">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-837">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

- <span data-ttu-id="21411-838">**週期性會議的位置建議支援：** 搜尋會議室，並排定週期性會議。</span><span class="sxs-lookup"><span data-stu-id="21411-838">**Location suggestion support for recurring meeting:** Search for conference rooms with scheduling recurring meetings.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="21411-839">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="21411-839">PowerPoint</span></span>

- <span data-ttu-id="21411-840">**在投影片放映期間更新投影片：** 在簡報期間，更新由其他作者變更的投影片。</span><span class="sxs-lookup"><span data-stu-id="21411-840">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>

- <span data-ttu-id="21411-841">**讓投影片更生動的新影像：** 您可以在投影片中使用的數千個免版稅圖庫影像、圖示和貼紙。</span><span class="sxs-lookup"><span data-stu-id="21411-841">**New images to bring your slides to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your presentations.</span></span> <span data-ttu-id="21411-842">移至 [插入] > [圖片] > [圖庫影像] 以開始使用。</span><span class="sxs-lookup"><span data-stu-id="21411-842">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="21411-843">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-843">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

### <a name="teams"></a><span data-ttu-id="21411-844">Teams</span><span class="sxs-lookup"><span data-stu-id="21411-844">Teams</span></span>

- <span data-ttu-id="21411-845">**增強 Teams 行事曆功能：** 以滑鼠右鍵按一下行事曆中的項目，以展開 RSVP 選項，開始與會議參與者交談，或在會議開始時快速加入會議。</span><span class="sxs-lookup"><span data-stu-id="21411-845">**Improvements to the Teams calendar:** Right-click an item in your calendar to pull up RSVP options, start a chat with meeting participants, or quickly join a meeting when it starts.</span></span> <span data-ttu-id="21411-846">我們也改善了活動排程表單。</span><span class="sxs-lookup"><span data-stu-id="21411-846">We've also made improvements to the event scheduling form.</span></span>

- <span data-ttu-id="21411-847">**抓到你了！：** 建立標籤並將人員指派至標籤，您就可以 @mention 群組、角色、部門等。小組擁有者可以自行嘗試。</span><span class="sxs-lookup"><span data-stu-id="21411-847">**Tag, you're it!:** Create tags and assign people to them so you can @mention a group, role, department, etc. Team owners, try it out for yourselves.</span></span> <span data-ttu-id="21411-848">移至某個小組，選取 [其他選項]、[管理標籤]。</span><span class="sxs-lookup"><span data-stu-id="21411-848">Go to a team, select More options, Manage tags.</span></span>

### <a name="word"></a><span data-ttu-id="21411-849">Word</span><span class="sxs-lookup"><span data-stu-id="21411-849">Word</span></span>

- <span data-ttu-id="21411-850">**讓您的工具方便使用：** 在您的繪圖工具箱中，尋找智慧筆，以便在文字中加入筆跡筆勢。</span><span class="sxs-lookup"><span data-stu-id="21411-850">**Keep your tools handy:** In your drawing toolbox, find the intelligent pen that allows you to add ink gestures to text.</span></span> [<span data-ttu-id="21411-851">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-851">Learn more</span></span>](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

- <span data-ttu-id="21411-852">**讓文件更生動的新影像：** 您可以在文件中使用的數千個免版稅圖庫影像、圖示和貼紙。</span><span class="sxs-lookup"><span data-stu-id="21411-852">**New images to bring your documents to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your documents.</span></span> <span data-ttu-id="21411-853">移至 [插入] > [圖片] > [圖庫影像] 以開始使用。</span><span class="sxs-lookup"><span data-stu-id="21411-853">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="21411-854">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-854">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-857">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-857">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="21411-858">Excel</span><span class="sxs-lookup"><span data-stu-id="21411-858">Excel</span></span>

- <span data-ttu-id="21411-859">在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。</span><span class="sxs-lookup"><span data-stu-id="21411-859">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="21411-860">修正在複製含有樞紐分析表的工作表後，會於某些情況下導致 Excel 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-860">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="21411-861">在某些情況下，Application.Evaluate (VBA) 無法在使用者定義的函式中運作。</span><span class="sxs-lookup"><span data-stu-id="21411-861">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="21411-862">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-862">Outlook</span></span>

- <span data-ttu-id="21411-863">已解決導致資料夾窗格寬度意外變更的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-863">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>


- <span data-ttu-id="21411-864">已解決導致 Outlook 在某些 Windows 組建上當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-864">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>


- <span data-ttu-id="21411-865">已解決在 Windows 更新後，開啟儲存在本機的 msg 或 .oft 檔案會導致 Outlook 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-865">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>


- <span data-ttu-id="21411-866">已解決導致 Outlook 在某些 Windows 組建上當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-866">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>


- <span data-ttu-id="21411-867">已解決導致使用者在退出 Outlook 時遇到掛斷的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-867">Addressed an issue that caused users to experience a hang while exiting Outlook.</span></span>


### <a name="project"></a><span data-ttu-id="21411-868">Project</span><span class="sxs-lookup"><span data-stu-id="21411-868">Project</span></span>

- <span data-ttu-id="21411-869">在表單檢視中編輯前置/後續任務資料時，會觸發額外的 ProjectBeforeTaskChange 事件。</span><span class="sxs-lookup"><span data-stu-id="21411-869">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>


- <span data-ttu-id="21411-870">修正如果您使用的是連線至 Project Web App 的 Project，且小數分隔符號是逗號，當您嘗試將延遲新增至相依性時，TaskDependencies Add 方法會失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-870">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>

### <a name="office-suite"></a><span data-ttu-id="21411-871">Office 套件</span><span class="sxs-lookup"><span data-stu-id="21411-871">Office Suite</span></span>

- <span data-ttu-id="21411-872">已解決同時防止限制存取和保護設有密碼之檔案的錯誤。</span><span class="sxs-lookup"><span data-stu-id="21411-872">Resolved an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-april-15"></a><span data-ttu-id="21411-874">版本 2003：4 月 15 日</span><span class="sxs-lookup"><span data-stu-id="21411-874">Version 2003: April 15</span></span>
<span data-ttu-id="21411-875">*版本 2003 (組建 12624.20466)*</span><span class="sxs-lookup"><span data-stu-id="21411-875">*Version 2003 (Build 12624.20466)*</span></span>
* <span data-ttu-id="21411-876">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="21411-876">Various bugs and performance fixes.</span></span>

## <a name="version-2003-april-14"></a><span data-ttu-id="21411-877">版本 2003：4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="21411-877">Version 2003: April 14</span></span>
<span data-ttu-id="21411-878">*版本 2003 (組建 12624.20442)*</span><span class="sxs-lookup"><span data-stu-id="21411-878">*Version 2003 (Build 12624.20442)*</span></span>

<span data-ttu-id="21411-879">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="21411-879">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-881">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-881">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="21411-882">Excel</span><span class="sxs-lookup"><span data-stu-id="21411-882">Excel</span></span>

- <span data-ttu-id="21411-883">在某些情況下，Application.Evaluate (VBA) 無法在使用者定義的函式中運作。</span><span class="sxs-lookup"><span data-stu-id="21411-883">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="21411-884">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-884">Outlook</span></span>

- <span data-ttu-id="21411-885">解決使用滑鼠上的「X」按鈕時，導致使用者偶爾發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-885">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

### <a name="project"></a><span data-ttu-id="21411-886">Project</span><span class="sxs-lookup"><span data-stu-id="21411-886">Project</span></span>

- <span data-ttu-id="21411-887">在表單檢視中編輯前置/後續任務資料時，會觸發額外的 ProjectBeforeTaskChange 事件。</span><span class="sxs-lookup"><span data-stu-id="21411-887">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

### <a name="word"></a><span data-ttu-id="21411-888">Word</span><span class="sxs-lookup"><span data-stu-id="21411-888">Word</span></span>

- <span data-ttu-id="21411-889">解決使用滑鼠上的「X」按鈕時，導致使用者偶爾發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-889">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-march-31"></a><span data-ttu-id="21411-891">版本 2003：3 月 31 日</span><span class="sxs-lookup"><span data-stu-id="21411-891">Version 2003: March 31</span></span>
<span data-ttu-id="21411-892">*版本 2003 (組建 12624.20382)*</span><span class="sxs-lookup"><span data-stu-id="21411-892">*Version 2003 (Build 12624.20382)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-894">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-894">Resolved issues</span></span>
### <a name="onenote"></a><span data-ttu-id="21411-895">OneNote</span><span class="sxs-lookup"><span data-stu-id="21411-895">OneNote</span></span>

- <span data-ttu-id="21411-896">透過在資訊列中通知使用者有關 Microsoft OneNote 中的暫時調整之資訊，可協助改善在高全球使用狀況時的同步處理與服務可用性。</span><span class="sxs-lookup"><span data-stu-id="21411-896">Inform users through the InfoBar about temporary adjustments in Microsoft OneNote that will help improve sync and service availability during high worldwide usage.</span></span>

### <a name="project"></a><span data-ttu-id="21411-897">Project</span><span class="sxs-lookup"><span data-stu-id="21411-897">Project</span></span>

- <span data-ttu-id="21411-898">修正了當開啟保護實際工作的設定時，使用者無法輸入分時期基準工時的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-898">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-march-25"></a><span data-ttu-id="21411-900">版本 2003：3 月 25 日</span><span class="sxs-lookup"><span data-stu-id="21411-900">Version 2003: March 25</span></span>
<span data-ttu-id="21411-901">*版本 2003 (組建 12624.20320)*</span><span class="sxs-lookup"><span data-stu-id="21411-901">*Version 2003 (Build 12624.20320)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="21411-903">功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-903">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="21411-904">Excel</span><span class="sxs-lookup"><span data-stu-id="21411-904">Excel</span></span>

- <span data-ttu-id="21411-905">**您最愛的 Excel 函數計算速度提升了：** SUMIFS、AVERAGEIFS、COUNTIFS、MAXIFS 和 MINIFS 函數現在比以往更快了。</span><span class="sxs-lookup"><span data-stu-id="21411-905">**Your favorite Excel functions just got faster:** The SUMIFS, AVERAGEIFS, COUNTIFS, MAXIFS, and MINIFS functions are much faster than ever before.</span></span> <span data-ttu-id="21411-906">更快速地前往底線。</span><span class="sxs-lookup"><span data-stu-id="21411-906">Get to the bottom line more quickly.</span></span> <span data-ttu-id="21411-907">立即試用。</span><span class="sxs-lookup"><span data-stu-id="21411-907">Try one now.</span></span>

### <a name="outlook"></a><span data-ttu-id="21411-908">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-908">Outlook</span></span>

- <span data-ttu-id="21411-909">**將電子郵件拖曳到您擁有的群組：** 從您的 [收件匣] 拖曳郵件和交談以將它們移動和複製。</span><span class="sxs-lookup"><span data-stu-id="21411-909">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="21411-910">您拖曳的郵件將會與所有群組成員共用。</span><span class="sxs-lookup"><span data-stu-id="21411-910">Messages you drag will be shared with all group members.</span></span>

- <span data-ttu-id="21411-911">**受限 WiFi 網路的新體驗：** 是否曾經加入需要登入網頁的 WiFi 網路呢？</span><span class="sxs-lookup"><span data-stu-id="21411-911">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="21411-912">Outlook 現在會偵測這項要求並協助您取得連結。</span><span class="sxs-lookup"><span data-stu-id="21411-912">Outlook now detects this and helps you get connected.</span></span>

###<a name="powerpoint"></a><span data-ttu-id="21411-913">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="21411-913">PowerPoint</span></span>

- <span data-ttu-id="21411-914">**註解：** PowerPoint 中新增的註解體驗可讓您快速輕鬆地探索文件並新增註解。</span><span class="sxs-lookup"><span data-stu-id="21411-914">**Comments:** The new commenting experience in PowerPoint allows you to quickly and easily discover and add comments to your documents.</span></span> <span data-ttu-id="21411-915">使用註解錨定、解決、工作、已改進的提及通知等新功能，現代化您的共同作業工作流程。</span><span class="sxs-lookup"><span data-stu-id="21411-915">Modernize your collaboration workflows with new features like comment anchoring, resolve, tasks, improved mention notifications, and much more.</span></span>

### <a name="word"></a><span data-ttu-id="21411-916">Word</span><span class="sxs-lookup"><span data-stu-id="21411-916">Word</span></span>

- <span data-ttu-id="21411-917">**其他人更快速看到您的變更：** 共同撰寫增強功能表示，共同作業者可較以往更快速看到您的變更。</span><span class="sxs-lookup"><span data-stu-id="21411-917">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

### <a name="office-suite"></a><span data-ttu-id="21411-918">Office 套件</span><span class="sxs-lookup"><span data-stu-id="21411-918">Office Suite</span></span>

- <span data-ttu-id="21411-919">**敏感度標籤**：您現在可以套用組織設定、用來提示您輸入自訂權限的敏感度標籤。</span><span class="sxs-lookup"><span data-stu-id="21411-919">**Sensitivity labels:** You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-922">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-922">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="21411-923">Excel</span><span class="sxs-lookup"><span data-stu-id="21411-923">Excel</span></span>

- <span data-ttu-id="21411-924">重複開啟內嵌在 Word 或 PowerPoint 中的活頁簿時，在某些情況下，Excel 會當機。</span><span class="sxs-lookup"><span data-stu-id="21411-924">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="21411-925">解決當來源活頁簿關閉時，外部連結無法在填入時更新的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-925">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

- <span data-ttu-id="21411-926">解決從範本建立圖表時的效能問題。</span><span class="sxs-lookup"><span data-stu-id="21411-926">Addressed a performance issue when creating charts from templates.</span></span>

### <a name="onenote"></a><span data-ttu-id="21411-927">OneNote</span><span class="sxs-lookup"><span data-stu-id="21411-927">OneNote</span></span>

- <span data-ttu-id="21411-928">透過暫時減少新嵌入附件的最大允許尺寸至 50MB，來改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="21411-928">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB.</span></span> <span data-ttu-id="21411-929">對於超過此限制的檔案，使用者可以選擇將檔案上傳到 OneDrive，並將連結插入 OneNote。</span><span class="sxs-lookup"><span data-stu-id="21411-929">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="21411-930">透過暫時調整 OneNote 2016 中的同步處理頻率，來改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="21411-930">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

### <a name="outlook"></a><span data-ttu-id="21411-931">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-931">Outlook</span></span>

- <span data-ttu-id="21411-932">已解決導致使用者在工作管理員中看到 Outlook 處理序延遲的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-932">Addressed an issue that caused users to see the Outlook process lingering in task manager after exiting.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="21411-933">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="21411-933">PowerPoint</span></span>

- <span data-ttu-id="21411-934">已改善複製貼上的案例：將 PowerPoint 投影片中的圖形複製並貼到迴圈中的其他投影片，可能會出現例外狀況而失敗。</span><span class="sxs-lookup"><span data-stu-id="21411-934">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


### <a name="project"></a><span data-ttu-id="21411-935">Project</span><span class="sxs-lookup"><span data-stu-id="21411-935">Project</span></span>

- <span data-ttu-id="21411-936">修正透過 [已停用] 按鈕停用/啟動工作時，ProjectBeforeTaskChange 事件無法偵測的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-936">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="21411-937">修正儲存使用舊版 Project 建立的專案時，Project 可能當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-937">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="21411-938">修正在將任務標示為完成之後，不正確地將任務完成百分比變更為低於 100% 的值的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-938">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="21411-939">修正無法正確計算摘要任務日期的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-939">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-march-10"></a><span data-ttu-id="21411-941">版本 2002：3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="21411-941">Version 2002: March 10</span></span>
<span data-ttu-id="21411-942">*版本 2002 (組建 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="21411-942">*Version 2002 (Build 12527.20278)*</span></span>

<span data-ttu-id="21411-943">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="21411-943">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="21411-945">功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-945">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="21411-946">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="21411-946">PowerPoint</span></span>

- <span data-ttu-id="21411-947">**投影片連結:** 要求同事參與製作您的投影片組，讓他們直接在您需要協助的投影片上開始進行。</span><span class="sxs-lookup"><span data-stu-id="21411-947">**Link to a slide:** Ask a colleague to contribute to your slide deck, and start them directly on the slide you need help with.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-950">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-950">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="21411-951">Project</span><span class="sxs-lookup"><span data-stu-id="21411-951">Project</span></span>

- <span data-ttu-id="21411-952">修正不先執行 OpenUndoTransaction 方法就不能觸發 OnUndoOrRedo 事件的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-952">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-march-01"></a><span data-ttu-id="21411-954">版本 2002：3 月 1 日</span><span class="sxs-lookup"><span data-stu-id="21411-954">Version 2002: March 01</span></span>
<span data-ttu-id="21411-955">*版本 2002 (組建 12527.20242)*</span><span class="sxs-lookup"><span data-stu-id="21411-955">*Version 2002 (Build 12527.20242)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-957">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-957">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="21411-958">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-958">Outlook</span></span>

- <span data-ttu-id="21411-959">解決導致協力廠商應用程式無法傳送電子郵件的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-959">Addresses an issue that caused third party applications to be unable to send email.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-february-25"></a><span data-ttu-id="21411-961">版本 2002：2 月 25 日</span><span class="sxs-lookup"><span data-stu-id="21411-961">Version 2002: February 25</span></span>
<span data-ttu-id="21411-962">*版本 2002 (組建 12527.20194)*</span><span class="sxs-lookup"><span data-stu-id="21411-962">*Version 2002 (Build 12527.20194)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="21411-964">功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-964">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="21411-965">Excel</span><span class="sxs-lookup"><span data-stu-id="21411-965">Excel</span></span>

- <span data-ttu-id="21411-966">**活頁簿統計資料：** 我們會計算儲存格、公式、圖表、表格，這樣您就不需要計算。</span><span class="sxs-lookup"><span data-stu-id="21411-966">**Workbook Statistics:** Cells, formulas, charts, tables... We count them so you don't have to.</span></span>

- <span data-ttu-id="21411-967">**查詢編輯器中的資料分析：** 取得欄位資料的總覽分析、識別錯誤和空白值，查看分佈長條圖等。</span><span class="sxs-lookup"><span data-stu-id="21411-967">**Data Profiling in Query Editor:** Get at-a-glance analysis of the data in your columns, identify error and empty values, see distribution histograms and more.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-970">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-970">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="21411-971">Excel</span><span class="sxs-lookup"><span data-stu-id="21411-971">Excel</span></span>

- <span data-ttu-id="21411-972">修正 CUBEVALUE 函數有時會傳回不正確結果的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-972">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

### <a name="outlook"></a><span data-ttu-id="21411-973">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-973">Outlook</span></span>

- <span data-ttu-id="21411-974">解決導致會議的位置欄位中的逗號變成分號的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-974">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="21411-975">解決在多個視窗中檢視相同項目時可能會導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-975">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="21411-976">已解決導致在某些情況下無法使用相關選項來停用標幟項目醒目提示的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-976">Addresses an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="21411-977">解決即使將同步處理滑桿設定為較小的設定，也會導致 Outlook 非預期地同步處理所有郵件的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-977">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>


- <span data-ttu-id="21411-978">解決會導致使用黑色佈景主題的使用者，看到 [寄件者] 下拉式功能表在白色背景上顯示白色文字的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-978">Addresses an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>


- <span data-ttu-id="21411-979">此變更會還原在郵件標頭中檢視多行主旨的功能。</span><span class="sxs-lookup"><span data-stu-id="21411-979">This change restores the ability to view multi-line subjects in the message header.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2001-february-19"></a><span data-ttu-id="21411-981">版本 2001：2 月 19 日</span><span class="sxs-lookup"><span data-stu-id="21411-981">Version 2001: February 19</span></span>
<span data-ttu-id="21411-982">*版本 2001 (組建 12430.20288)*</span><span class="sxs-lookup"><span data-stu-id="21411-982">*Version 2001 (Build 12430.20288)*</span></span>
* <span data-ttu-id="21411-983">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="21411-983">Various bugs and performance fixes.</span></span>

## <a name="version-2001-february-11"></a><span data-ttu-id="21411-984">版本 2001：2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="21411-984">Version 2001: February 11</span></span>
<span data-ttu-id="21411-985">*版本 2001 (組建 12430.20264)*</span><span class="sxs-lookup"><span data-stu-id="21411-985">*Version 2001 (Build 12430.20264)*</span></span>

<span data-ttu-id="21411-986">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="21411-986">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-988">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-988">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="21411-989">Access</span><span class="sxs-lookup"><span data-stu-id="21411-989">Access</span></span>

- <span data-ttu-id="21411-990">Access 範本應不再導致資料庫中的附件欄出現故障。</span><span class="sxs-lookup"><span data-stu-id="21411-990">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="21411-991">個體化範本後，您現在應該可以將附件欄新增至資料庫。</span><span class="sxs-lookup"><span data-stu-id="21411-991">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

### <a name="excel"></a><span data-ttu-id="21411-992">Excel</span><span class="sxs-lookup"><span data-stu-id="21411-992">Excel</span></span>

- <span data-ttu-id="21411-993">修正未顯示操作功能表中的註解命令的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-993">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="21411-994">修正以下問題：將文字轉換成具有溢出陣列之儲存格的欄時，某些使用者發生當機。</span><span class="sxs-lookup"><span data-stu-id="21411-994">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>


### <a name="outlook"></a><span data-ttu-id="21411-995">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-995">Outlook</span></span>

- <span data-ttu-id="21411-996">解決導致使用者在指定無效寄件者地址時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-996">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>


- <span data-ttu-id="21411-997">解決導致使用者在取消帳戶設定時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-997">Addresses an issue that caused users to experience a crash when canceling account setup.</span></span>


### <a name="project"></a><span data-ttu-id="21411-998">Project</span><span class="sxs-lookup"><span data-stu-id="21411-998">Project</span></span>

- <span data-ttu-id="21411-999">修正以下問題：固定工期類型的 100% 工作可能會誤將其完成百分比計算為小於 100% 完成。</span><span class="sxs-lookup"><span data-stu-id="21411-999">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>


### <a name="office-suite"></a><span data-ttu-id="21411-1000">Office 套件</span><span class="sxs-lookup"><span data-stu-id="21411-1000">Office Suite</span></span>

- <span data-ttu-id="21411-1001">此變更解決使用 Intel Integrated GPU 的圖形配接卡報告問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1001">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2001-january-30"></a><span data-ttu-id="21411-1003">版本 2001：1 月 30 日</span><span class="sxs-lookup"><span data-stu-id="21411-1003">Version 2001: January 30</span></span>
<span data-ttu-id="21411-1004">*版本 2001 (組建 12430.20184)*</span><span class="sxs-lookup"><span data-stu-id="21411-1004">*Version 2001 (Build 12430.20184)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="21411-1006">功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1006">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="21411-1007">Excel</span><span class="sxs-lookup"><span data-stu-id="21411-1007">Excel</span></span>

- <span data-ttu-id="21411-1008">**即時讀取與回覆：** 直接從電子郵件回覆註解和提及，而不需開啟活頁簿。</span><span class="sxs-lookup"><span data-stu-id="21411-1008">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="21411-1009">**向左看，向右看... XLOOKUP 在這裡！：** 一列接著一列，在含有 XLOOKUP 的表格或範圍中尋找您需要的項目。</span><span class="sxs-lookup"><span data-stu-id="21411-1009">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span> [<span data-ttu-id="21411-1010">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1010">Learn more</span></span>](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)

### <a name="outlook"></a><span data-ttu-id="21411-1011">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-1011">Outlook</span></span>

- <span data-ttu-id="21411-1012">**進階群組電子郵件設定：** 此功能可協助使用者自訂要在收件匣中接收/追蹤哪些電子郵件或活動。</span><span class="sxs-lookup"><span data-stu-id="21411-1012">**Advanced group email settings:** This feature helps groups users to customize which emails or events to receive/follow in their inbox.</span></span>

- <span data-ttu-id="21411-1013">**群組命名原則：** 群組命名原則可讓 IT 系統管理員將組織中使用者所建立群組的名稱標準化及管理。</span><span class="sxs-lookup"><span data-stu-id="21411-1013">**Groups Naming policy:** A group naming policy enables the IT admin to standardize and manage the names of groups created by users in the organization.</span></span> <span data-ttu-id="21411-1014">系統管理員可以要求在建立群組時，將特定首碼和尾碼新增至群組的名稱，而且可以封鎖使用特定字詞。</span><span class="sxs-lookup"><span data-stu-id="21411-1014">The admin can require a specific prefix and suffix be added to the name for a group when it's created, and can block specific words from being used.</span></span> <span data-ttu-id="21411-1015">這有助於將群組名稱中使用不當字詞的情況最小化，以及 IT 管理其目錄中群組的表示方式。</span><span class="sxs-lookup"><span data-stu-id="21411-1015">This helps minimize the use of inappropriate words in group names as well as IT manage the representation of groups in their directory.</span></span> <span data-ttu-id="21411-1016">命名原則也可協助部署小組網站的組織根據部門來分類。</span><span class="sxs-lookup"><span data-stu-id="21411-1016">Naming Policy also helps organizations that deploy team sites to categorize them based on department.</span></span>

### <a name="word"></a><span data-ttu-id="21411-1017">Word</span><span class="sxs-lookup"><span data-stu-id="21411-1017">Word</span></span>

- <span data-ttu-id="21411-1018">**更安全的影片體驗：** 安全性增強功能可讓您擁有更安全的線上影片體驗。</span><span class="sxs-lookup"><span data-stu-id="21411-1018">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="21411-1019">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1019">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- <span data-ttu-id="21411-1020">**對筆跡使用套索：**[繪圖] 索引標籤上的 [套索] 工具，可協助您選取使用筆跡繪製的物件。</span><span class="sxs-lookup"><span data-stu-id="21411-1020">**Lasso your ink:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="21411-1021">選取個別筆劃或整個字。</span><span class="sxs-lookup"><span data-stu-id="21411-1021">Select individual strokes, or whole words.</span></span> [<span data-ttu-id="21411-1022">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1022">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)






[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-1025">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-1025">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="21411-1026">Access</span><span class="sxs-lookup"><span data-stu-id="21411-1026">Access</span></span>

- <span data-ttu-id="21411-p191">此更新會修正使用 ADODB 的問題。VB 程式碼中的錄製程式物件可能會不正確地報告錯誤。</span><span class="sxs-lookup"><span data-stu-id="21411-p191">This update fixes an issue where using an ADODB. Recorder object in VB code may incorrectly report an error.</span></span>


- <span data-ttu-id="21411-1029">此更新修正可能會導致 Microsoft Access 無法識別連結的 SQL Server 資料表中的識別資料行的問題，這可能會導致不正確地將資料列報告為已刪除。</span><span class="sxs-lookup"><span data-stu-id="21411-1029">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>


### <a name="excel"></a><span data-ttu-id="21411-1030">Excel</span><span class="sxs-lookup"><span data-stu-id="21411-1030">Excel</span></span>

- <span data-ttu-id="21411-1031">解決重新命名簽名時，使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1031">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>


### <a name="outlook"></a><span data-ttu-id="21411-1032">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-1032">Outlook</span></span>

- <span data-ttu-id="21411-1033">解決重新命名簽名時，使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1033">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1912-january-22"></a><span data-ttu-id="21411-1035">版本 1912：1 月 22 日</span><span class="sxs-lookup"><span data-stu-id="21411-1035">Version 1912: January 22</span></span>
<span data-ttu-id="21411-1036">*版本 1912 (組建 12325.20344)*</span><span class="sxs-lookup"><span data-stu-id="21411-1036">*Version 1912 (Build 12325.20344)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-1038">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-1038">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="21411-1039">Access</span><span class="sxs-lookup"><span data-stu-id="21411-1039">Access</span></span>

- <span data-ttu-id="21411-1040">此更新修正可能會導致 Microsoft Access 無法識別連結的 SQL Server 資料表中的識別資料行的問題，這可能會導致不正確地將資料列報告為已刪除。</span><span class="sxs-lookup"><span data-stu-id="21411-1040">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1912-january-14"></a><span data-ttu-id="21411-1042">版本 1912：1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="21411-1042">Version 1912: January 14</span></span>
<span data-ttu-id="21411-1043">*版本 1912 (組建 12325.20298)*</span><span class="sxs-lookup"><span data-stu-id="21411-1043">*Version 1912 (Build 12325.20298)*</span></span>

<span data-ttu-id="21411-1044">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="21411-1044">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

## <a name="version-1912-january-08"></a><span data-ttu-id="21411-1045">版本 1912：1 月 8 日</span><span class="sxs-lookup"><span data-stu-id="21411-1045">Version 1912: January 08</span></span>
<span data-ttu-id="21411-1046">*版本 1912 (組建 12325.20288)*</span><span class="sxs-lookup"><span data-stu-id="21411-1046">*Version 1912 (Build 12325.20288)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="21411-1048">功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1048">Feature updates</span></span>

### <a name="outlook"></a><span data-ttu-id="21411-1049">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-1049">Outlook</span></span>

- <span data-ttu-id="21411-1050">**傳送可存取的郵件給最需要它的人員：** Outlook 會顯示郵件提示，協助確保將您的內容傳送給偏好可存取內容的使用者時可供其存取</span><span class="sxs-lookup"><span data-stu-id="21411-1050">**Send accessible mail to those who need it most:** Outlook will display a mail tip to help you ensure that your content is accessible when sending to a user who prefers accessible content</span></span>

### <a name="powerpoint"></a><span data-ttu-id="21411-1051">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="21411-1051">PowerPoint</span></span>

- <span data-ttu-id="21411-1052">**最佳化您的簡報：** 協助工具檢查程式可協助您以螢幕閱讀器為中心，在投影片上排列物件。</span><span class="sxs-lookup"><span data-stu-id="21411-1052">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

- <span data-ttu-id="21411-1053">**jiffy 中的 Gif：** 一個投影片、一個圖文框。</span><span class="sxs-lookup"><span data-stu-id="21411-1053">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="21411-1054">在 PowerPoint 中輕鬆建立迴圈 Gif。</span><span class="sxs-lookup"><span data-stu-id="21411-1054">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="21411-1055">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1055">Learn more</span></span>](https://support.office.com/zh-TW/article/a598753e-92de-4f1b-8393-714db4d334b4)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-1058">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-1058">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="21411-1059">Excel</span><span class="sxs-lookup"><span data-stu-id="21411-1059">Excel</span></span>

- <span data-ttu-id="21411-1060">這項變更透過利用軟體轉譯避免特定 Intel 圖形驅動程式發生問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1060">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

### <a name="outlook"></a><span data-ttu-id="21411-1061">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-1061">Outlook</span></span>

- <span data-ttu-id="21411-1062">解決了導致會議位置在清除之後，又會不預期地重新加回會議的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1062">Addressed an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="21411-1063">解決當使用者透過鍵盤快速鍵與信箱資料夾互動時會造成明顯延遲的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1063">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="21411-1064">解決在某些情況下，導致使用者看到電子郵件傳送到與顯示的 SMTP 位址不相符之地址的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1064">Addressed an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="21411-1065">解決在擷取雲端設定時，導致使用者在 Outlook 中遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1065">Addressed an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

### <a name="word"></a><span data-ttu-id="21411-1066">Word</span><span class="sxs-lookup"><span data-stu-id="21411-1066">Word</span></span>

- <span data-ttu-id="21411-1067">建置組塊組合管理可能會顯示無效的通知：「您已經修改樣式、建置組塊」。</span><span class="sxs-lookup"><span data-stu-id="21411-1067">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

### <a name="office-suite"></a><span data-ttu-id="21411-1068">Office 套件</span><span class="sxs-lookup"><span data-stu-id="21411-1068">Office Suite</span></span>

- <span data-ttu-id="21411-1069">解決 Office 更新可能會非預期地從 Office CDN 而不是預期使用的來源 (例如本機或網路共用或 Configuration Manager 提供的位置) 下載檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1069">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

## <a name="version-1911-december-10"></a><span data-ttu-id="21411-1070">版本 1911：12 月 10 日</span><span class="sxs-lookup"><span data-stu-id="21411-1070">Version 1911: December 10</span></span>
<span data-ttu-id="21411-1071">*版本 1911 (組建 12228.20364)*</span><span class="sxs-lookup"><span data-stu-id="21411-1071">*Version 1911 (Build 12228.20364)*</span></span>

<span data-ttu-id="21411-1072">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="21411-1072">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-1074">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-1074">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="21411-1075">Excel</span><span class="sxs-lookup"><span data-stu-id="21411-1075">Excel</span></span>

- <span data-ttu-id="21411-1076">這項變更透過利用軟體轉譯避免特定 Intel 圖形驅動程式發生問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1076">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="21411-1077">我們修正了樞紐分析圖的右鍵功能表，以啟用 [顯示詳細資料] 選項。</span><span class="sxs-lookup"><span data-stu-id="21411-1077">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

### <a name="outlook"></a><span data-ttu-id="21411-1078">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-1078">Outlook</span></span>

- <span data-ttu-id="21411-1079">解決造成網頁增益集存取數位版權管理郵件的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1079">Addresses an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1911-december-03"></a><span data-ttu-id="21411-1081">版本 1911：12 月 3 日</span><span class="sxs-lookup"><span data-stu-id="21411-1081">Version 1911: December 03</span></span>
<span data-ttu-id="21411-1082">*版本 1911 (組建 12228.20332)*</span><span class="sxs-lookup"><span data-stu-id="21411-1082">*Version 1911 (Build 12228.20332)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="21411-1084">功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1084">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="21411-1085">Excel</span><span class="sxs-lookup"><span data-stu-id="21411-1085">Excel</span></span>

- <span data-ttu-id="21411-1086">**輸入會傳回多個值的公式**：現在您可以快速輸入公式來傳回多個值，並且值會自動溢出至相鄰的儲存格。</span><span class="sxs-lookup"><span data-stu-id="21411-1086">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="21411-1087">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1087">Learn more</span></span>](https://support.office.com/article/5c2c9cbb-def8-409a-b380-2fbf91b20aa3)

- <span data-ttu-id="21411-1088">**六個功能強大的函數：** 我們新增了六個新的函數，讓您的試算表功能更強大：FILTER、SORT、SORTBY、UNIQUE、SEQUENCE 和 RANDARRAY。</span><span class="sxs-lookup"><span data-stu-id="21411-1088">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span> [<span data-ttu-id="21411-1089">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1089">Learn more</span></span>](https://support.office.com/article/003df6c7-1dcb-4388-8e2e-0fe77a0887bc)

- <span data-ttu-id="21411-1090">**資料視覺化工具增益集：** 從 Excel 快速建立 Visio 流程圖。</span><span class="sxs-lookup"><span data-stu-id="21411-1090">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="21411-1091">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1091">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="21411-1092">Word</span><span class="sxs-lookup"><span data-stu-id="21411-1092">Word</span></span>

- <span data-ttu-id="21411-1093">**改善共同撰寫：** 改善共同撰寫的體驗，盡可能讓其他人即時收到修改過的內容。</span><span class="sxs-lookup"><span data-stu-id="21411-1093">**Coauthoring improvements:** Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-1096">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-1096">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="21411-1097">Access</span><span class="sxs-lookup"><span data-stu-id="21411-1097">Access</span></span>

- <span data-ttu-id="21411-1098">修正 Microsoft Access 中的「更新查詢」執行時或在 SQL 中使用 UPDATE 陳述式時，可能導致發生錯誤「查詢已損壞」&quot;&quot;的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1098">Fixed an issue in Microsoft Access that may cause the error &quot;Query is Corrupt&quot; when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="21411-1099">Excel</span><span class="sxs-lookup"><span data-stu-id="21411-1099">Excel</span></span>

- <span data-ttu-id="21411-1100">從不受信任的網路共用編輯受保護的檔案時，Excel 可能會發生問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1100">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="21411-1101">解決在未開啟活頁簿時，搜尋最近使用的檔案會造成當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1101">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

### <a name="outlook"></a><span data-ttu-id="21411-1102">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-1102">Outlook</span></span>

- <span data-ttu-id="21411-1103">解決會導致使用者在嘗試從 [帳戶建立] 內容連絡支援服務時，看到具有 [確定]&quot;&quot; 按鈕的空白訊息方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1103">Addressed an issue that caused users to see an empty message box with an &quot;OK&quot; button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="21411-1104">在 2019 年使用巴西時區時，週期性會議和約會以 2020 年的錯誤時段顯示。</span><span class="sxs-lookup"><span data-stu-id="21411-1104">When using the Brazilia time zone in the year 2019, recurring meetings and appointments are displayed in the wrong timeslot for the year 2020.</span></span> <span data-ttu-id="21411-1105">此變更與設定使用巴西時區的用戶端或設定使用該時區的會議和約會相關。</span><span class="sxs-lookup"><span data-stu-id="21411-1105">This change is relevant for clients set in the Brazilia time zone or for meetings and appointments set in that time zone.</span></span> 

- <span data-ttu-id="21411-1106">解決會導致使用者在開啟 [規則] 對話方塊時看到「在這部電腦中建立的規則和 Microsoft Exchange 上的規則衝突」提示的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1106">Addressed an issue that caused users to see a &quot;The rules on this computer do not match the rules on Microsoft Exchange&quot; prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="21411-1107">修正 SMIME 演算法選取的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1107">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="21411-1108">解決會導致會議中的 [位置] 欄位意外更新的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1108">Addressed an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

### <a name="office-suite"></a><span data-ttu-id="21411-1109">Office 套件</span><span class="sxs-lookup"><span data-stu-id="21411-1109">Office Suite</span></span>

- <span data-ttu-id="21411-1110">解決 Office 更新可能會非預期地從 Office CDN 而不是預期使用的來源 (例如本機或網路共用或 Configuration Manager 提供的位置) 下載檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1110">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="21411-1111">修正 ODT 和 GPO 更新期限設定中的問題，在其中，相對期限只有在第一次設定時才會有效，此修正可啟用後續更新的相關期限。</span><span class="sxs-lookup"><span data-stu-id="21411-1111">Fixed an issue in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1910-november-22"></a><span data-ttu-id="21411-1113">版本 1910：11 月 22 日</span><span class="sxs-lookup"><span data-stu-id="21411-1113">Version 1910: November 22</span></span>
<span data-ttu-id="21411-1114">*版本 1910 (組建 12130.20410)*</span><span class="sxs-lookup"><span data-stu-id="21411-1114">*Version 1910 (Build 12130.20410)*</span></span>
* <span data-ttu-id="21411-1115">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="21411-1115">Various bugs and performance fixes.</span></span>

## <a name="version-1910-november-18"></a><span data-ttu-id="21411-1116">版本 1910：11 月 18 日</span><span class="sxs-lookup"><span data-stu-id="21411-1116">Version 1910: November 18</span></span>
<span data-ttu-id="21411-1117">*版本 1910 (組建 12130.20390)*</span><span class="sxs-lookup"><span data-stu-id="21411-1117">*Version 1910 (Build 12130.20390)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-1119">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-1119">Resolved issues</span></span>

### <a name="access"></a><span data-ttu-id="21411-1120">Access</span><span class="sxs-lookup"><span data-stu-id="21411-1120">Access</span></span>

- <span data-ttu-id="21411-1121">已修正執行更新查詢會不正確顯示「查詢損毀」錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1121">Fixed an issue where running an Update query would incorrectly give an error message: "Query is corrupt".</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1910-november-12"></a><span data-ttu-id="21411-1123">版本 1910：11 月 1 2日</span><span class="sxs-lookup"><span data-stu-id="21411-1123">Version 1910: November 12</span></span>
<span data-ttu-id="21411-1124">*版本 1910 (組建 12130.20344)*</span><span class="sxs-lookup"><span data-stu-id="21411-1124">*Version 1910 (Build 12130.20344)*</span></span>

<span data-ttu-id="21411-1125">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="21411-1125">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="21411-1127">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-1127">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="21411-1128">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-1128">Outlook</span></span>

- <span data-ttu-id="21411-1129">解決會導致使用者在會議中看到位置欄位意外變更的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1129">Addressed an issue that caused users to see the location field in meetings change unexpectedly.</span></span>

- <span data-ttu-id="21411-1130">解決會導致使用者在嘗試從 [帳戶建立] 內容連絡支援服務時，看到具有 [確定]&quot;&quot; 按鈕的空白訊息方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1130">Addressed an issue that caused users to see an empty message box with an &quot;OK&quot; button when trying to contact support from the Account Creation context.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1910-october-30"></a><span data-ttu-id="21411-1132">版本 1910：10 月 30 日</span><span class="sxs-lookup"><span data-stu-id="21411-1132">Version 1910: October 30</span></span>
<span data-ttu-id="21411-1133">*版本 1910 (組建 12130.20272)*</span><span class="sxs-lookup"><span data-stu-id="21411-1133">*Version 1910 (Build 12130.20272)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="21411-1134">解決的問題</span><span class="sxs-lookup"><span data-stu-id="21411-1134">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="21411-1135">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-1135">Outlook</span></span>

- <span data-ttu-id="21411-1136">解決會導致在搜尋意見反應體驗中懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1136">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="21411-1138">功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1138">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="21411-1139">Excel</span><span class="sxs-lookup"><span data-stu-id="21411-1139">Excel</span></span>

- <span data-ttu-id="21411-1140">**建立更易於存取的 PDF：** 建立 PDF 檔案，在儲存之前，協助工具檢查程式會指出應該修正的協助工具問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1140">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="21411-1141">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1141">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="21411-1142">**轉換檔案，以提升存取性：** 將您的檔案升級為現代格式，讓所有人更容易存取。</span><span class="sxs-lookup"><span data-stu-id="21411-1142">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="21411-1143">**將敏感度標籤套用至您的文件和電子郵件**：將敏感度標籤套用至您的檔案和電子郵件，使其符合組織的資訊保護原則。</span><span class="sxs-lookup"><span data-stu-id="21411-1143">**Apply sensitivity labels to your documents and emails:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span> [<span data-ttu-id="21411-1144">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1144">Learn more</span></span>](https://aka.ms/officemipdocs)

### <a name="outlook"></a><span data-ttu-id="21411-1145">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-1145">Outlook</span></span>

- <span data-ttu-id="21411-1146">**將敏感度標籤套用至您的文件和電子郵件**：將敏感度標籤套用至您的檔案和電子郵件，使其符合組織的資訊保護原則。</span><span class="sxs-lookup"><span data-stu-id="21411-1146">**Apply sensitivity labels to your documents and emails:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span> [<span data-ttu-id="21411-1147">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1147">Learn more</span></span>](https://aka.ms/officemipdocs)

### <a name="powerpoint"></a><span data-ttu-id="21411-1148">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="21411-1148">PowerPoint</span></span>

- <span data-ttu-id="21411-1149">**建立更易於存取的 PDF：** 建立 PDF 檔案，在儲存之前，協助工具檢查程式會指出應該修正的協助工具問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1149">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="21411-1150">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1150">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="21411-1151">**轉換檔案，以提升存取性：** 將您的檔案升級為現代格式，讓所有人更容易存取。</span><span class="sxs-lookup"><span data-stu-id="21411-1151">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="21411-1152">**將敏感度標籤套用至您的文件和電子郵件**：將敏感度標籤套用至您的檔案和電子郵件，使其符合組織的資訊保護原則。</span><span class="sxs-lookup"><span data-stu-id="21411-1152">**Apply sensitivity labels to your documents and emails:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span> [<span data-ttu-id="21411-1153">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1153">Learn more</span></span>](https://aka.ms/officemipdocs)

### <a name="word"></a><span data-ttu-id="21411-1154">Word</span><span class="sxs-lookup"><span data-stu-id="21411-1154">Word</span></span>

- <span data-ttu-id="21411-1155">**共同撰寫的增強功能**：在具有追蹤修訂的文件中共同撰寫來強化 Word 效能。</span><span class="sxs-lookup"><span data-stu-id="21411-1155">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="21411-1156">**建立更易於存取的 PDF：** 建立 PDF 檔案，在儲存之前，協助工具檢查程式會指出應該修正的協助工具問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1156">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="21411-1157">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1157">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="21411-1158">**轉換檔案，以提升存取性：** 將您的檔案升級為現代格式，讓所有人更容易存取。</span><span class="sxs-lookup"><span data-stu-id="21411-1158">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="21411-1159">**已修正合併 3D 物件所造成的文件損毀問題：** 已修正由合併 3D 物件所造成的文件損毀問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1159">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="21411-1160">**將敏感度標籤套用至您的文件和電子郵件**：將敏感度標籤套用至您的檔案和電子郵件，使其符合組織的資訊保護原則。</span><span class="sxs-lookup"><span data-stu-id="21411-1160">**Apply sensitivity labels to your documents and emails:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span> [<span data-ttu-id="21411-1161">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1161">Learn more</span></span>](https://aka.ms/officemipdocs)

### <a name="office-suite"></a><span data-ttu-id="21411-1162">Office 套件</span><span class="sxs-lookup"><span data-stu-id="21411-1162">Office Suite</span></span>

- <span data-ttu-id="21411-1163">**在現有的 Office 365 專業增強版上安裝 Microsoft Teams：** 從 6 月底開始，Microsoft Teams 將在更新這些安裝時，新增至 Office 365 專業增強版 (和 Office 365 商務版) 的現有安裝中。</span><span class="sxs-lookup"><span data-stu-id="21411-1163">**Install Microsoft Teams on existing installations of Office 365 ProPlus:** Beginning in late June, Microsoft Teams will be included in existing installations of Office 365 ProPlus (and Office 365 Business) upon updates of these installations.</span></span> <span data-ttu-id="21411-1164">新增 Teams 的日期取決於您使用的更新通道。</span><span class="sxs-lookup"><span data-stu-id="21411-1164">The date when Teams will be added depends on which update channel you're using.</span></span> <span data-ttu-id="21411-1165">如需詳細資訊，請參閱隨著 Office 365 專業增強版部署 Microsoft Teams。</span><span class="sxs-lookup"><span data-stu-id="21411-1165">Please refer to Deploy Microsoft Teams with Office 365 ProPlus for additional information.</span></span> [<span data-ttu-id="21411-1166">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1166">Learn More</span></span>](/deployoffice/teams-install)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-1909-october-22"></a><span data-ttu-id="21411-1168">版本 1909：10 月 22 日</span><span class="sxs-lookup"><span data-stu-id="21411-1168">Version 1909: October 22</span></span>
<span data-ttu-id="21411-1169">*版本 1909 (組建 12026.20344)*</span><span class="sxs-lookup"><span data-stu-id="21411-1169">*Version 1909 (Build 12026.20344)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a><span data-ttu-id="21411-1171">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1171">Non-security updates</span></span>
### <a name="project"></a><span data-ttu-id="21411-1172">Project</span><span class="sxs-lookup"><span data-stu-id="21411-1172">Project</span></span>
- <span data-ttu-id="21411-1173">解決開啟唯讀專案時，使用者可能會取得多個訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1173">Resolved an issue where users could get several messages when opening a read-only project.</span></span>

### <a name="office-suite"></a><span data-ttu-id="21411-1174">Office 套件</span><span class="sxs-lookup"><span data-stu-id="21411-1174">Office Suite</span></span>

- <span data-ttu-id="21411-1175">為了保護 Office 客戶的安全性，我們現在專門使用 SHA-2 演算法來簽署 Microsoft Office 更新。</span><span class="sxs-lookup"><span data-stu-id="21411-1175">To protect Office customers’ security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span><br>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


## <a name="october-15"></a><span data-ttu-id="21411-1177">10 月 15 日</span><span class="sxs-lookup"><span data-stu-id="21411-1177">October 15</span></span>

### <a name="non-security-updates"></a><span data-ttu-id="21411-1178">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1178">Non-security updates</span></span>

### <a name="office-suite"></a><span data-ttu-id="21411-1179">Office 套件</span><span class="sxs-lookup"><span data-stu-id="21411-1179">Office Suite</span></span>
- <span data-ttu-id="21411-p205">我們已暫時停用 [雲端儲存] 對話方塊以解決在 2019 年 10 月14 日針對早於 12130.20184 的組建所發佈的儲存問題。這項功能即將重新啟用。</span><span class="sxs-lookup"><span data-stu-id="21411-p205">We have temporarily disabled the Cloud Save dialog to address the saving issue we posted on October 14, 2019 for builds older than 12130.20184. This feature will be re-enabled soon.</span></span>


## <a name="version-1909-october-14"></a><span data-ttu-id="21411-1182">版本 1909：10 月 14 日</span><span class="sxs-lookup"><span data-stu-id="21411-1182">Version 1909: October 14</span></span>
<span data-ttu-id="21411-1183">*版本 1909 (組建 12026.20334)*</span><span class="sxs-lookup"><span data-stu-id="21411-1183">*Version 1909 (Build 12026.20334)*</span></span>

### <a name="non-security-updates"></a><span data-ttu-id="21411-1184">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1184">Non-security updates</span></span>

### <a name="office-suite"></a><span data-ttu-id="21411-1185">Office 套件</span><span class="sxs-lookup"><span data-stu-id="21411-1185">Office Suite</span></span>

- <span data-ttu-id="21411-p206">解決使用者使用早於 12130.20184 的組建時，可能無法儲存 Word、Excel 和 PowerPoint 2019 文件的問題。此問題會影響建立新檔案並在按一下 [儲存] 圖示或按 Ctrl + S 之後帶出 [另存新檔] 對話方塊的使用者。</span><span class="sxs-lookup"><span data-stu-id="21411-p206">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint 2019 documents for builds older than 12130.20184.  This issue affects users that create a new file and bring up the “Save As” dialog after clicking on the Save icon or pressing Ctrl + S.</span></span>


## <a name="version-1909-october-08"></a><span data-ttu-id="21411-1188">版本 1909：10 月 8 日</span><span class="sxs-lookup"><span data-stu-id="21411-1188">Version 1909: October 08</span></span>
<span data-ttu-id="21411-1189">*版本 1909 (組建 12026.20320)*</span><span class="sxs-lookup"><span data-stu-id="21411-1189">*Version 1909 (Build 12026.20320)*</span></span>

<span data-ttu-id="21411-1190">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="21411-1190">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a><span data-ttu-id="21411-1192">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1192">Non-security updates</span></span>

### <a name="outlook"></a><span data-ttu-id="21411-1193">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-1193">Outlook</span></span>

- <span data-ttu-id="21411-1194">已修正 Outlook 中的附件封鎖邏輯也會封鎖 python 附的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1194">Fixed an issue with attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="21411-1195">已解決導致使用者無法開啟某些週期性行事曆項目執行個體的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1195">Addressed an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="21411-1196">已解決導致使用者在 Outlook 處理序中看到記憶體洩漏的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1196">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="21411-1197">已解決導致使用者在建立設定檔時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1197">Addressed an issue that caused users to experience a crash during profile creation.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1909-september-30"></a><span data-ttu-id="21411-1199">版本 1909：9 月 30 日</span><span class="sxs-lookup"><span data-stu-id="21411-1199">Version 1909: September 30</span></span>
<span data-ttu-id="21411-1200">*版本 1909 (組建 12026.20264)*</span><span class="sxs-lookup"><span data-stu-id="21411-1200">*Version 1909 (Build 12026.20264)*</span></span>
* <span data-ttu-id="21411-1201">不同的錯誤 (bug) 和效能修正。</span><span class="sxs-lookup"><span data-stu-id="21411-1201">Various bugs and performance fixes.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="21411-1203">功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1203">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="21411-1204">Access</span><span class="sxs-lookup"><span data-stu-id="21411-1204">Access</span></span>

- <span data-ttu-id="21411-1205">**快速尋找連結資料表：** 新的搜尋方塊可讓您輕鬆尋找連結資料表。</span><span class="sxs-lookup"><span data-stu-id="21411-1205">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="21411-1206">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1206">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="21411-1207">Excel</span><span class="sxs-lookup"><span data-stu-id="21411-1207">Excel</span></span>

- <span data-ttu-id="21411-1208">**更快速共用檔案：** 不需開啟檔案，即可從最近使用清單直接共用您的檔案。</span><span class="sxs-lookup"><span data-stu-id="21411-1208">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

### <a name="outlook"></a><span data-ttu-id="21411-1209">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-1209">Outlook</span></span>

- <span data-ttu-id="21411-1210">**Outlook 中的 [插入連結] 功能表會插入含有租用戶系統管理員所定義的權限的連結：** Outlook 中使用 [插入連結] 所插入的連結，只有具有連結權限的使用者可使用。</span><span class="sxs-lookup"><span data-stu-id="21411-1210">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="21411-1211">這常會造成使用者來回傳送電子郵件，要求對方授與文件的存取權。</span><span class="sxs-lookup"><span data-stu-id="21411-1211">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="21411-1212">我們已更新這項體驗，現在插入的連結將具有由租用戶系統管理員設定的預設權限。</span><span class="sxs-lookup"><span data-stu-id="21411-1212">We've updated this experience so now the link is inserted with the default permission set by the tenant admin.</span></span>

- <span data-ttu-id="21411-1213">**Outlook 視覺更新**：這是 Outlook 核心體驗的視覺更新的一部分，其中更新 [讀取窗格] 和 [檢查] 中的 [郵件訊息] 版面配置。</span><span class="sxs-lookup"><span data-stu-id="21411-1213">**Outlook visual refresh:** This is part of the visual refresh of core experiences in Outlook, updating how mail messages layout in the reading pane and inspector.</span></span>

- <span data-ttu-id="21411-1214">**共用行事曆更新的速度更快：** 針對 Office 365 中的共用行事曆，Outlook 可以使用 REST API 更新這些行事曆。</span><span class="sxs-lookup"><span data-stu-id="21411-1214">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="21411-1215">開啟預覽以更快且更可靠地更新共用行事曆。</span><span class="sxs-lookup"><span data-stu-id="21411-1215">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

- <span data-ttu-id="21411-1216">**在搜尋結果中查看相關郵件：** Outlook 會分析搜尋字詞，然後在搜尋結果的最上方顯示最相關的電子郵件。</span><span class="sxs-lookup"><span data-stu-id="21411-1216">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="21411-1217">您也可以在 [最佳結果] 區段中查看依日期排列順序的所有結果。</span><span class="sxs-lookup"><span data-stu-id="21411-1217">You'll also see all results sorted by date in the Top Results section.</span></span>

- <span data-ttu-id="21411-1218">**傳送郵件給正確的人員：** 只需按一下 [收件者：] 行，然後從 [建議的連絡人] 中選擇。</span><span class="sxs-lookup"><span data-stu-id="21411-1218">**Send the mail to the right person:** Just click the To: line and choose from suggested contacts.</span></span> <span data-ttu-id="21411-1219">圖片和目前狀態指示器可協助您選擇正確的人員。</span><span class="sxs-lookup"><span data-stu-id="21411-1219">A picture and presence indicator helps you choose the right person.</span></span>

- <span data-ttu-id="21411-1220">**抵禦攻擊的進階防護：** 使用 Office 365 進階威脅防護，您會受到保護，不受電子郵件主旨、附加的郵件、簽署的郵件、網路路徑內超連結的攻擊。</span><span class="sxs-lookup"><span data-stu-id="21411-1220">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="21411-1221">**在不同燈光下查看郵件：** 使用太陽/月亮按鈕以在讀取窗格中於淺色和深色背景之間切換。</span><span class="sxs-lookup"><span data-stu-id="21411-1221">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="21411-1222">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1222">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

### <a name="powerpoint"></a><span data-ttu-id="21411-1223">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="21411-1223">PowerPoint</span></span>

- <span data-ttu-id="21411-1224">**將圖例另存成 SVG：** 將圖表、圖形或其他圖例另存成可縮放向量圖形，其可調整大小，且不損失影像品質。</span><span class="sxs-lookup"><span data-stu-id="21411-1224">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="21411-1225">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1225">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="21411-1226">**筆跡重播：** 對筆跡繪圖進行動畫處理，以使其在投影片放映過程中向前或向後重播。</span><span class="sxs-lookup"><span data-stu-id="21411-1226">**Ink-stant replay:** Animate an ink drawing so that it replays forward or backward during your slide show.</span></span> [<span data-ttu-id="21411-1227">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1227">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- <span data-ttu-id="21411-1228">**更快速共用檔案：** 不需開啟檔案，即可從最近使用清單直接共用您的檔案。</span><span class="sxs-lookup"><span data-stu-id="21411-1228">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

### <a name="visio"></a><span data-ttu-id="21411-1229">Visio</span><span class="sxs-lookup"><span data-stu-id="21411-1229">Visio</span></span>

- <span data-ttu-id="21411-1230">**使用 Microsoft Flow 和 Visio 來設計和自動化業務工作流程：** 使用 Visio 來設計工作流程圖，並將它匯出到 Microsoft Flow 以進行自動化。</span><span class="sxs-lookup"><span data-stu-id="21411-1230">**Design and automate business workflows using Microsoft Flow and Visio:** Use Visio to design workflow diagram and export it to Microsoft Flow to automate.</span></span>

### <a name="word"></a><span data-ttu-id="21411-1231">Word</span><span class="sxs-lookup"><span data-stu-id="21411-1231">Word</span></span>

- <span data-ttu-id="21411-1232">**用其他方式表達：** 當您想要以不同方式表達時，「重寫」功能可以幫助您。</span><span class="sxs-lookup"><span data-stu-id="21411-1232">**Say it another way:** When you want to say it differently, Rewrite is there to help.</span></span> <span data-ttu-id="21411-1233">重寫提供其他不同方式來表達您的詞彙。</span><span class="sxs-lookup"><span data-stu-id="21411-1233">Rewrite offers alternatives for finessing your phrases.</span></span>

- <span data-ttu-id="21411-1234">**共同撰寫的增強功能**：增強共同撰寫時的可靠性。</span><span class="sxs-lookup"><span data-stu-id="21411-1234">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="21411-1235">**更快速共用檔案：** 不需開啟檔案，即可從最近使用清單直接共用您的檔案。</span><span class="sxs-lookup"><span data-stu-id="21411-1235">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="21411-1236">**其他人更快速看到您的變更：** 共同撰寫增強功能表示，共同作業者可較以往更快速看到您的變更。</span><span class="sxs-lookup"><span data-stu-id="21411-1236">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a><span data-ttu-id="21411-1239">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1239">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="21411-1240">Excel</span><span class="sxs-lookup"><span data-stu-id="21411-1240">Excel</span></span>

- <div><span data-ttu-id="21411-1241"><span style="background-color:rgb(255, 255, 255);display:inline !important;">解決會導致將超連結貼到一些受保護工作表中的問題。</span></span><span class="sxs-lookup"><span data-stu-id="21411-1241"><span style="background-color:rgb(255, 255, 255);display:inline !important;">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span></span><br></div>


- <div><span data-ttu-id="21411-1242">&nbsp;<span style="font-size:13.3333px;background-color:rgb(255, 255, 255);display:inline !important;">當在增益集管理員中瀏覽時</span>，顯示 16 個以上的增益集。</span><span class="sxs-lookup"><span data-stu-id="21411-1242">Enabled more than 16 add-ins to show&nbsp;<span style="font-size:13.3333px;background-color:rgb(255, 255, 255);display:inline !important;">when browsing in the add-in manager.</span></span></span></div>
- <div><span data-ttu-id="21411-1243">已修正在 Excel 構想功能中，在 Win32 用戶端中按一下 [構想] 按鈕來載入增益集時會發生錯誤的問題。&nbsp;</span><span class="sxs-lookup"><span data-stu-id="21411-1243">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.&nbsp;</span></span></div>

### <a name="outlook"></a><span data-ttu-id="21411-1244">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-1244">Outlook</span></span>

- <div><span data-ttu-id="21411-1245">已解決導致部分安全連結無法顯示簡單動態顯示 URL 的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1245">Addressed an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span></div>


- <span data-ttu-id="21411-1246"><span style="background-color:rgb(255, 255, 255);display:inline !important;">已更新 Outlook 中的附件封鎖邏輯，以同時封鎖 python 附件。</span></span><span class="sxs-lookup"><span data-stu-id="21411-1246"><span style="background-color:rgb(255, 255, 255);display:inline !important;">Updated the attachment blocking logic in Outlook to also block python attachments.</span></span></span>


- <span data-ttu-id="21411-1247"><span style="background-color:rgb(255, 255, 255);display:inline !important;">已解決導致使用者在 Outlook 處理序中看到記憶體洩漏的問題。</span></span><span class="sxs-lookup"><span data-stu-id="21411-1247"><span style="background-color:rgb(255, 255, 255);display:inline !important;">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span></span>

- <span data-ttu-id="21411-1248">我們已修正了檔案可能無法儲存到 WebDAV 位置的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1248">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>


### <a name="office-suite"></a><span data-ttu-id="21411-1249">Office 套件</span><span class="sxs-lookup"><span data-stu-id="21411-1249">Office Suite</span></span>

- <div><p style="margin:0in 0in 0.0001pt;font-size:11pt;font-family:Calibri, sans-serif;"><span data-ttu-id="21411-1250">我們已修正使用者在開啟檔案時會發生的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1250">We fixed an issue users were hitting when opening a file.</span></span></p></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-september-10"></a><span data-ttu-id="21411-1252">版本 1908：9 月 10 日</span><span class="sxs-lookup"><span data-stu-id="21411-1252">Version 1908: September 10</span></span>
<span data-ttu-id="21411-1253">*版本 1908 (組建 11929.20300)*</span><span class="sxs-lookup"><span data-stu-id="21411-1253">*Version 1908 (Build 11929.20300)*</span></span>

<span data-ttu-id="21411-1254">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="21411-1254">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a><span data-ttu-id="21411-1256">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1256">Non-security updates</span></span>
### <a name="outlook"></a><span data-ttu-id="21411-1257">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-1257">Outlook</span></span>

- <span data-ttu-id="21411-1258">修正會導致使用者無法透過螢幕助讀程式存取位置建議的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1258">Fixed an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="21411-1259">修正嘗試擷取使用者的 Outlook 雲端設定時，導致一些使用者遇到驗證錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1259">Fixed an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="21411-1260">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="21411-1260">PowerPoint</span></span>

- <span data-ttu-id="21411-1261">修正還原 PowerPoint 影片控制項的協助工具名稱的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1261">Fixed an issue to restore the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="21411-1262">修正部分動畫無法開始的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1262">Fixed an issue which could prevent some animations from starting.</span></span>

### <a name="word"></a><span data-ttu-id="21411-1263">Word</span><span class="sxs-lookup"><span data-stu-id="21411-1263">Word</span></span>

- <span data-ttu-id="21411-1264">修正嘗試共用儲存在 SharePoint 2016 上的檔案時，導致使用者遇到「很抱歉，發生問題，無法共用」訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1264">Fixed an issue which caused users to get the message "Sorry, something is preventing us from sharing this"  when trying to share files stored on SharePoint 2016.</span></span>

### <a name="office-suite"></a><span data-ttu-id="21411-1265">Office 套件</span><span class="sxs-lookup"><span data-stu-id="21411-1265">Office Suite</span></span>

- <span data-ttu-id="21411-1266">修正大型樹狀檢視失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1266">Fixed an issue where large tree views were failing.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-august-26"></a><span data-ttu-id="21411-1268">版本 1908：8 月 26 日</span><span class="sxs-lookup"><span data-stu-id="21411-1268">Version 1908: August 26</span></span>
<span data-ttu-id="21411-1269">*版本 1908 (組建 11929.20254)*</span><span class="sxs-lookup"><span data-stu-id="21411-1269">*Version 1908 (Build 11929.20254)*</span></span>
* <span data-ttu-id="21411-1270">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="21411-1270">Various bugs and performance fixes.</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="21411-1271">Excel：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1271">Excel: Feature updates</span></span>

- <span data-ttu-id="21411-1272">**勾勒草圖：** 為活頁簿中的 Office 圖形提供隨意的手繪外觀。</span><span class="sxs-lookup"><span data-stu-id="21411-1272">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="21411-1273">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1273">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="21411-1274">**搜尋並享受：** 我們新增了 [搜尋以插入] 圖示，讓您輕鬆找到您要的圖示。</span><span class="sxs-lookup"><span data-stu-id="21411-1274">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="21411-1275">而當您選取時，[插入] 按鈕會告知您已經選取的數量。</span><span class="sxs-lookup"><span data-stu-id="21411-1275">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="21411-1276">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1276">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

- <span data-ttu-id="21411-1277">**專注在待辦事項上：** 選取 [解決] 來摺疊註解，使得開啟中的項目能夠突顯。</span><span class="sxs-lookup"><span data-stu-id="21411-1277">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

### <a name="office-suite-feature-updates"></a><span data-ttu-id="21411-1278">Office 套件：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1278">Office Suite: Feature updates</span></span>

- <span data-ttu-id="21411-1279">**Office 圖示有新的外觀：** Office 圖示經過重新設計，以反映簡單、功能強大且智慧型的 Office 體驗。</span><span class="sxs-lookup"><span data-stu-id="21411-1279">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="21411-1280">Outlook：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1280">Outlook: Feature updates</span></span>

- <span data-ttu-id="21411-1281">**取得位置建議：** 排程約會和會議時，請在 [位置] 中開始輸入，Outlook 會建議會議室、地址，以及其他最近使用的位置。</span><span class="sxs-lookup"><span data-stu-id="21411-1281">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="21411-1282">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1282">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)

- <span data-ttu-id="21411-1283">**搜尋並享受：** 我們新增了 [搜尋以插入] 圖示，讓您輕鬆找到您要的圖示。</span><span class="sxs-lookup"><span data-stu-id="21411-1283">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="21411-1284">而當您選取時，[插入] 按鈕會告知您已經選取的數量。</span><span class="sxs-lookup"><span data-stu-id="21411-1284">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="21411-1285">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1285">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="21411-1286">PowerPoint：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1286">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="21411-1287">**勾勒草圖：** 為簡報中的 Office 圖形提供隨意的手繪外觀。</span><span class="sxs-lookup"><span data-stu-id="21411-1287">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="21411-1288">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1288">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="21411-1289">**搜尋並享受：** 我們新增了 [搜尋以插入] 圖示，讓您輕鬆找到您要的圖示。</span><span class="sxs-lookup"><span data-stu-id="21411-1289">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="21411-1290">而當您選取時，[插入] 按鈕會告知您已經選取的數量。</span><span class="sxs-lookup"><span data-stu-id="21411-1290">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="21411-1291">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1291">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="word-feature-updates"></a><span data-ttu-id="21411-1292">Word：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1292">Word: Feature updates</span></span>

- <span data-ttu-id="21411-1293">**勾勒草圖：** 為文件中的 Office 圖形提供隨意的手繪外觀。</span><span class="sxs-lookup"><span data-stu-id="21411-1293">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="21411-1294">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1294">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="21411-1295">**搜尋並享受：** 我們新增了 [搜尋以插入] 圖示，讓您輕鬆找到您要的圖示。</span><span class="sxs-lookup"><span data-stu-id="21411-1295">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="21411-1296">而當您選取時，[插入] 按鈕會告知您已經選取的數量。</span><span class="sxs-lookup"><span data-stu-id="21411-1296">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="21411-1297">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1297">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

## <a name="version-1907-august-13"></a><span data-ttu-id="21411-1298">版本 1907：8 月 13 日</span><span class="sxs-lookup"><span data-stu-id="21411-1298">Version 1907: August 13</span></span>
<span data-ttu-id="21411-1299">*版本 1907 (組建 11901.20218)*</span><span class="sxs-lookup"><span data-stu-id="21411-1299">*Version 1907 (Build 11901.20218)*</span></span>

<span data-ttu-id="21411-1300">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="21411-1300">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="21411-1301">Excel：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1301">Excel: Non-security updates</span></span>

- <span data-ttu-id="21411-1302">修正在與其他使用者共同撰寫的工作階段中變更樞紐分析表排序的方式，然後重新整理可能觸發的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1302">Fixed an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="21411-1303">Outlook：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1303">Outlook: Non-security updates</span></span>

- <span data-ttu-id="21411-1304">修正使用者將信箱從基本驗證升級為新式驗證後造成錯誤的帳戶與 Outlook 設定檔相關聯的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1304">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

## <a name="version-1907-july-29"></a><span data-ttu-id="21411-1305">版本 1907：7 月 29 日</span><span class="sxs-lookup"><span data-stu-id="21411-1305">Version 1907: July 29</span></span>

<span data-ttu-id="21411-1306">*版本 1907 (組建 11901.20176)*</span><span class="sxs-lookup"><span data-stu-id="21411-1306">*Version 1907 (Build 11901.20176)*</span></span>
* <span data-ttu-id="21411-1307">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="21411-1307">Various bugs and performance fixes.</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="21411-1308">Excel：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1308">Excel: Feature updates</span></span>

- <span data-ttu-id="21411-1309">**不必再來回往返瀏覽器：** 您決定開啟 Office 文件連結的方式：在瀏覽器或 App 中開啟。</span><span class="sxs-lookup"><span data-stu-id="21411-1309">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="21411-1310">**使用 Power Query 的增強功能快速撰寫程式碼：** 使用自動完成和語法色彩快速完成程式碼。</span><span class="sxs-lookup"><span data-stu-id="21411-1310">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="21411-1311">同時輕鬆探索函數、資料行和參數。</span><span class="sxs-lookup"><span data-stu-id="21411-1311">Easily discover functions, columns, and parameters, too.</span></span>

- <span data-ttu-id="21411-1312">**建立地圖圖表：** 此功能是針對使用 Excel 的地理資料類型繪製區域分布圖圖表使用者的增強功能。</span><span class="sxs-lookup"><span data-stu-id="21411-1312">**Create a Map chart:** This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="21411-1313">對使用者的優點是功能之間有更豐富的整合，以及使用者要對應的區域會有更好的精確度。</span><span class="sxs-lookup"><span data-stu-id="21411-1313">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="21411-1314">其他優點包括功能能夠對應城市多邊形。</span><span class="sxs-lookup"><span data-stu-id="21411-1314">Additional benefits include - ability to map city polygons.</span></span> [<span data-ttu-id="21411-1315">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1315">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="21411-1316">**聯結類似欄位上的表格：** 在比較合併表格的欄位時，取得及轉換 (Power Query) 現在具有近似文字比對邏輯 (也稱為模糊比對)。</span><span class="sxs-lookup"><span data-stu-id="21411-1316">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span> [<span data-ttu-id="21411-1317">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1317">Learn more</span></span>](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

### <a name="outlook-feature-updates"></a><span data-ttu-id="21411-1318">Outlook：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1318">Outlook: Feature updates</span></span>

- <span data-ttu-id="21411-1319">**搜尋人員時取得電子郵件建議：** 當您在 [搜尋] 方塊中輸入人員的名稱時，最相關的電子郵件訊息會包括在您的搜尋建議中。</span><span class="sxs-lookup"><span data-stu-id="21411-1319">**Get email suggestions when you search for a person:** When you type a person’s name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span> [<span data-ttu-id="21411-1320">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1320">Learn more</span></span>](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="21411-1321">PowerPoint：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1321">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="21411-1322">**不必再來回往返瀏覽器：** 您決定開啟 Office 文件連結的方式：在瀏覽器或 App 中開啟。</span><span class="sxs-lookup"><span data-stu-id="21411-1322">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="21411-1323">**線上影片有新的首頁：** 將影片儲存至 Microsoft Stream，讓組織中的任何人都看得到。</span><span class="sxs-lookup"><span data-stu-id="21411-1323">**Online videos have a new home:** Save a video to Microsoft Stream so anyone in your organization can see it.</span></span> <span data-ttu-id="21411-1324">插入影片連結，享受檔案大小只有原來一小部分的多媒體簡報。</span><span class="sxs-lookup"><span data-stu-id="21411-1324">Insert the video link and enjoy a multimedia presentation at a fraction of the file size.</span></span> [<span data-ttu-id="21411-1325">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1325">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="21411-1326">**建立地圖圖表：** 此功能是針對使用 Excel 的地理資料類型繪製區域分布圖圖表使用者的增強功能。</span><span class="sxs-lookup"><span data-stu-id="21411-1326">**Create a Map chart:** This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="21411-1327">對使用者的優點是功能之間有更豐富的整合，以及使用者要對應的區域會有更好的精確度。</span><span class="sxs-lookup"><span data-stu-id="21411-1327">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="21411-1328">其他優點包括功能能夠對應城市多邊形。</span><span class="sxs-lookup"><span data-stu-id="21411-1328">Additional benefits include - ability to map city polygons.</span></span> [<span data-ttu-id="21411-1329">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1329">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="21411-1330">**新增投影片標題以讓簡報更易於使用：** 協助工具檢查程式可協助您找出並修正遺失的投影片標題。</span><span class="sxs-lookup"><span data-stu-id="21411-1330">**Add Slide Titles to make your presentations accessible:** Accessibility Checker helps you find and fix missing slide titles.</span></span> [<span data-ttu-id="21411-1331">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1331">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="21411-1332">**[在講義上列印投影片編號] 設定已移至 [列印] 功能表，以易於存取：** 選取講義版面配置時，可在 [列印] > [整頁模式] 下拉式清單中找到它。</span><span class="sxs-lookup"><span data-stu-id="21411-1332">**The setting to Print Slide Numbers in Handouts has been moved to the Print Menu for easier access:**  Find it in the Print > Print Layout dropdown when a Handout layout is selected.</span></span> <span data-ttu-id="21411-1333">這也會使得每個簡報的設定易於切換。</span><span class="sxs-lookup"><span data-stu-id="21411-1333">This also allows the setting to be easily toggled per presentation.</span></span> [<span data-ttu-id="21411-1334">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1334">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

### <a name="word-feature-updates"></a><span data-ttu-id="21411-1335">Word：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1335">Word: Feature updates</span></span>

- <span data-ttu-id="21411-1336">**跟分心說再見：** Mac 中最受歡迎的功能來到 Windows。</span><span class="sxs-lookup"><span data-stu-id="21411-1336">**Say goodbye to distractions:** A favorite Mac feature comes to Windows.</span></span> <span data-ttu-id="21411-1337">切換到 [檢視] 功能表中的 [焦點] 以移除令人分心的事物，讓您更能專注於工作。</span><span class="sxs-lookup"><span data-stu-id="21411-1337">Switch to Focus on the View menu to remove distractions and concentrate on your work.</span></span> [<span data-ttu-id="21411-1338">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1338">Learn more</span></span>](https://support.office.com/article/51af2fb2-194f-424b-ab7e-b65de9ec9292)

- <span data-ttu-id="21411-1339">**不必再來回往返瀏覽器：** 您決定開啟 Office 文件連結的方式：在瀏覽器或 App 中開啟。</span><span class="sxs-lookup"><span data-stu-id="21411-1339">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="21411-1340">**建立地圖圖表：** 此功能是針對使用 Excel 的地理資料類型繪製區域分布圖圖表使用者的增強功能。</span><span class="sxs-lookup"><span data-stu-id="21411-1340">**Create a Map chart:** This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="21411-1341">對使用者的優點是功能之間有更豐富的整合，以及使用者要對應的區域會有更好的精確度。</span><span class="sxs-lookup"><span data-stu-id="21411-1341">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="21411-1342">其他優點包括功能能夠對應城市多邊形。</span><span class="sxs-lookup"><span data-stu-id="21411-1342">Additional benefits include - ability to map city polygons.</span></span> [<span data-ttu-id="21411-1343">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1343">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="21411-1344">**精確橡皮擦：** 從兩個橡皮擦尺寸中選擇，以修正小型筆跡缺陷。</span><span class="sxs-lookup"><span data-stu-id="21411-1344">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="21411-1345">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1345">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

## <a name="version-1906-july-09"></a><span data-ttu-id="21411-1346">版本 1906：7 月 9 日</span><span class="sxs-lookup"><span data-stu-id="21411-1346">Version 1906: July 09</span></span>
<span data-ttu-id="21411-1347">*版本 1906 (組建 11727.20244)*</span><span class="sxs-lookup"><span data-stu-id="21411-1347">*Version 1906 (Build 11727.20244)*</span></span>

<span data-ttu-id="21411-1348">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="21411-1348">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="21411-1349">Outlook：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1349">Outlook: Non-security updates</span></span>

- <span data-ttu-id="21411-1350">解決導致目前的資料夾搜尋間歇性失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1350">Addresses an issue that caused current folder search to intermittently fail.</span></span>

## <a name="version-1906-june-27"></a><span data-ttu-id="21411-1351">版本 1906：6 月 27 日</span><span class="sxs-lookup"><span data-stu-id="21411-1351">Version 1906: June 27</span></span>
<span data-ttu-id="21411-1352">*版本 1906 (組建 11727.20230)*</span><span class="sxs-lookup"><span data-stu-id="21411-1352">*Version 1906 (Build 11727.20230)*</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="21411-1353">Outlook：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1353">Outlook: Non-security updates</span></span>

- <span data-ttu-id="21411-1354">解決導致部分 POP3 使用者查看所有純文字格式電子郵件 (無論設定) 的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1354">Addresses an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span>  <span data-ttu-id="21411-1355">此修正將會還原 HTML 格式郵件的檢視。</span><span class="sxs-lookup"><span data-stu-id="21411-1355">This fix will restore the view of the HTML formatted messages.</span></span>

## <a name="version-1906-june-26"></a><span data-ttu-id="21411-1356">版本 1906：6 月 26 日</span><span class="sxs-lookup"><span data-stu-id="21411-1356">Version 1906: June 26</span></span>
<span data-ttu-id="21411-1357">*版本 1906 (組建 11727.20224)*</span><span class="sxs-lookup"><span data-stu-id="21411-1357">*Version 1906 (Build 11727.20224)*</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="21411-1358">Excel：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1358">Excel: Non-security updates</span></span>

- <span data-ttu-id="21411-1359">已修正 Excel 中，巨集指派給圖形或表單控制項時，可能會顯示不正確的錯誤訊息，或者可能會處理不正確目標範圍的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1359">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>
- <span data-ttu-id="21411-1360">已解決導致表格旁的剪下並貼上作業在與其他人共同撰寫時失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1360">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="21411-1361">Outlook：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1361">Outlook: Non-security updates</span></span>

- <span data-ttu-id="21411-1362">解決導致經理對於代理人是否已經回覆特定會議邀請含混不清的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1362">Addresses an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

## <a name="version-1906-june-24"></a><span data-ttu-id="21411-1363">版本 1906：6 月 24 日</span><span class="sxs-lookup"><span data-stu-id="21411-1363">Version 1906: June 24</span></span>
<span data-ttu-id="21411-1364">*版本 1906 (組建 11727.20210)*</span><span class="sxs-lookup"><span data-stu-id="21411-1364">*Version 1906 (Build 11727.20210)*</span></span>
* <span data-ttu-id="21411-1365">不同的錯誤 (bug) 和效能修正。</span><span class="sxs-lookup"><span data-stu-id="21411-1365">Various bugs and performance fixes.</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="21411-1366">Excel：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1366">Excel: Feature updates</span></span>

- <span data-ttu-id="21411-1367">**觀看工作表生動地呈現：** 插入動畫 3D 圖形，來查看心跳、行星軌道，以及暴龍在工作表內橫衝直撞。</span><span class="sxs-lookup"><span data-stu-id="21411-1367">**Watch your worksheet come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage through the workbook.</span></span> [<span data-ttu-id="21411-1368">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1368">Learn more</span></span>](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

### <a name="outlook-feature-updates"></a><span data-ttu-id="21411-1369">Outlook：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1369">Outlook: Feature updates</span></span>

- <span data-ttu-id="21411-1370">**簡化且也能自訂的功能區：** 輕鬆使用簡化、以單一列方式陳列的常用按鈕。</span><span class="sxs-lookup"><span data-stu-id="21411-1370">**A simplified ribbon that's customizable, too:** Enjoy a streamlined, single row of the most frequently used buttons.</span></span> <span data-ttu-id="21411-1371">輕鬆在傳統與 [簡化] 檢視之間切換，以及釘選/取消釘選命令。</span><span class="sxs-lookup"><span data-stu-id="21411-1371">Easily switch between classic and Simplified views, and pin/unpin commands.</span></span> [<span data-ttu-id="21411-1372">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1372">Learn more</span></span>](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- <span data-ttu-id="21411-1373">**挑選您的最愛動作：** 不使用 [標幟] 和 [刪除] 嗎？</span><span class="sxs-lookup"><span data-stu-id="21411-1373">**Pick your favorite action:** Don't use Flag and Delete?</span></span> <span data-ttu-id="21411-1374">那麼 [封存] 或 [標示為已讀取] 呢？</span><span class="sxs-lookup"><span data-stu-id="21411-1374">How about Archive or Mark as Read?</span></span> <span data-ttu-id="21411-1375">在您最常使用的命令，自訂快速動作功能表。</span><span class="sxs-lookup"><span data-stu-id="21411-1375">Customize the quick action menu with the commands you use most.</span></span>

- <span data-ttu-id="21411-1376">**已改善擁有多個資料夾的信箱共用資料夾同步處理：** Outlook 多年來在同步處理共用信箱時，將其資料夾的數量限制最多為 500 個。</span><span class="sxs-lookup"><span data-stu-id="21411-1376">**Improved shared folder synchronization for mailboxes with many folders:** For years Outlook has been limited to a maximum of 500 folders when synchronizing shared mailboxes.</span></span> <span data-ttu-id="21411-1377">這項變更改善了 Outlook，同步處理時將不會再發生 500 個資料夾的數量限制。</span><span class="sxs-lookup"><span data-stu-id="21411-1377">With this change Outlook has been improved to sync in a way that will no longer encounter this 500 folder limit.</span></span>

- <span data-ttu-id="21411-1378">**焦點收件匣設定在不同裝置之間會保持相同：** 您的焦點收件匣喜好設定現在會儲存在雲端。</span><span class="sxs-lookup"><span data-stu-id="21411-1378">**Focused Inbox settings remain the same across devices:** Your Focused Inbox preferences are now stored in the cloud.</span></span> <span data-ttu-id="21411-1379">這麼一來，當您在任何電腦上使用 Windows 版 Outlook 和 Outlook 網頁版時便可享有相同的體驗。</span><span class="sxs-lookup"><span data-stu-id="21411-1379">Enjoy the same experience when you use Outlook for Windows on any computer and Outlook on the web.</span></span> [<span data-ttu-id="21411-1380">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1380">Learn more</span></span>](https://support.office.com/article/d77a442e-a86c-4bf8-b3dd-5571ae556986)

- <span data-ttu-id="21411-1381">**想要寬鬆或緊密的版面配置？您可自由選擇：** 若您想讓郵件之間能有更多空間，可以採用「緊密間距」；或者，您也可以採用緊密的版面配置，以便查看更多郵件。</span><span class="sxs-lookup"><span data-stu-id="21411-1381">**Relaxed or tighter layout? You choose:** Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

- <span data-ttu-id="21411-1382">**我們已為您更新 Outlook 使用者體驗：** 先前利用「即將推出」提供預覽的簡化體驗，專門設計來幫助您專注於最重要的事物上。</span><span class="sxs-lookup"><span data-stu-id="21411-1382">**We’ve updated the Outlook user experience for you:** A simplified experience, previously available for preview with Coming Soon, designed to help you focus on what matters most.</span></span> [<span data-ttu-id="21411-1383">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1383">Learn more</span></span>](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- <span data-ttu-id="21411-1384">**讓我繪製：** 使用筆跡在圖片上徒手畫或新增繪圖畫布來傳達您的想法。</span><span class="sxs-lookup"><span data-stu-id="21411-1384">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="21411-1385">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1385">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

### <a name="word-feature-updates"></a><span data-ttu-id="21411-1386">Word：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1386">Word: Feature updates</span></span>

- <span data-ttu-id="21411-1387">**共同撰寫：** 厭倦於被包含巨集的文件阻礙了嗎？</span><span class="sxs-lookup"><span data-stu-id="21411-1387">**CoAuthoring:** Tired of being locked out of your document with macros?</span></span> <span data-ttu-id="21411-1388">現在商務用 OneDrive 的 docm 檔案允許同時由多個作者編輯。</span><span class="sxs-lookup"><span data-stu-id="21411-1388">Now your docm files on OneDrive for Business allow simultaneous editing by multiple authors.</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="21411-1389">商務用 Skype：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1389">Skype for Business: Non-security updates</span></span> 

 - <span data-ttu-id="21411-1390">修正當監視器縮放超過 100% 時，在會議中會顯示來自 Polycom CX5500 和相關裝置的所有攝影機串流</span><span class="sxs-lookup"><span data-stu-id="21411-1390">Fix to display all camera streams from Polycom CX5500 and related devices in a meeting when your monitor is scaled more than 100%</span></span>

- <span data-ttu-id="21411-1391">啟用 [在會議中裁剪我的視訊並置中對齊] 設定時，在 4K 監視器上進行的會議可正確裁剪視訊</span><span class="sxs-lookup"><span data-stu-id="21411-1391">Correctly crop video in a meeting on a 4K monitor when the "Crop and Center my video in meetings" setting is enabled</span></span>

- <span data-ttu-id="21411-1392">允許從具有多張網路介面卡的 Windows 10 電腦將檔案傳輸到舊版 Office Communicator 用戶端。</span><span class="sxs-lookup"><span data-stu-id="21411-1392">Allow transferring files to legacy Office Communicator clients from a Windows 10 computer with multiple network adapters.</span></span>

- <span data-ttu-id="21411-1393">改善了商務用 Skype 和 Microsoft Teams 參與者之間的通訊體驗</span><span class="sxs-lookup"><span data-stu-id="21411-1393">Improved experience for communication between Skype for Business and Microsoft Teams participants</span></span>


## <a name="version-1905-june-11"></a><span data-ttu-id="21411-1394">版本 1905：6 月 11 日</span><span class="sxs-lookup"><span data-stu-id="21411-1394">Version 1905: June 11</span></span>
<span data-ttu-id="21411-1395">*版本 1905 (組建 11629.20246)*</span><span class="sxs-lookup"><span data-stu-id="21411-1395">*Version 1905 (Build 11629.20246)*</span></span>
<br/><span data-ttu-id="21411-1396">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="21411-1396">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="21411-1397">Excel：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1397">Excel: Non-security updates</span></span>

- <span data-ttu-id="21411-1398">已解決以下問題：當插入或刪除儲存格時，瀑布圖和漏斗圖無法與表格同步處理。</span><span class="sxs-lookup"><span data-stu-id="21411-1398">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="21411-1399">PowerPoint：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1399">PowerPoint: Non-security updates</span></span>

- <span data-ttu-id="21411-1400">已修正某些增益集會在圖表的圖形周圍擲出未預期錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1400">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

### <a name="visio-non-security-updates"></a><span data-ttu-id="21411-1401">Visio：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1401">Visio: Non-security updates</span></span>

- <span data-ttu-id="21411-1402">有多個圖形無法從 Visio 匯出至 SVG。</span><span class="sxs-lookup"><span data-stu-id="21411-1402">Export to SVG from Visio was not working for a variety of shapes.</span></span>

## <a name="version-1905-june-3"></a><span data-ttu-id="21411-1403">版本 1905：6 月 3 日</span><span class="sxs-lookup"><span data-stu-id="21411-1403">Version 1905: June 3</span></span>
<span data-ttu-id="21411-1404">*版本 1905 (組建 11629.20214)*</span><span class="sxs-lookup"><span data-stu-id="21411-1404">*Version 1905 (Build 11629.20214)*</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="21411-1405">PowerPoint：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1405">PowerPoint: Non-security updates</span></span>

- <span data-ttu-id="21411-1406">已修正某些增益集會在圖表的圖形周圍擲出未預期錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1406">Fixed an issue where some addins would throw unexpected errors around shapes in charts.</span></span>

## <a name="version-1905-may-29"></a><span data-ttu-id="21411-1407">版本 1905：5 月 29 日</span><span class="sxs-lookup"><span data-stu-id="21411-1407">Version 1905: May 29</span></span>
<span data-ttu-id="21411-1408">*版本 1905 (組建 11629.20196)*</span><span class="sxs-lookup"><span data-stu-id="21411-1408">*Version 1905 (Build 11629.20196)*</span></span>

### <a name="access-feature-updates"></a><span data-ttu-id="21411-1409">Access：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1409">Access: Feature updates</span></span>

- <span data-ttu-id="21411-1410">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="21411-1410">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="21411-1411">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="21411-1411">Switching between them has never been easier.</span></span> [<span data-ttu-id="21411-1412">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1412">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="excel-feature-updates"></a><span data-ttu-id="21411-1413">Excel：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1413">Excel: Feature updates</span></span>

- <span data-ttu-id="21411-1414">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="21411-1414">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="21411-1415">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="21411-1415">Switching between them has never been easier.</span></span> [<span data-ttu-id="21411-1416">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1416">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="21411-1417">**即將推出：** 查看 Office 即將推出的新鮮變更，立即試用並給予我們意見反應。</span><span class="sxs-lookup"><span data-stu-id="21411-1417">**Coming Soon:** See what exciting changes are Coming Soon to Office, try them out and give us feedback.</span></span> [<span data-ttu-id="21411-1418">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1418">Learn more</span></span>](https://support.office.com/article/7800e0cf0-812f-475a-80aa-d47376e076f2)

- <span data-ttu-id="21411-1419">**在註解中使用 @Mentions 提及功能，讓共同作業更有效率：** 共同作業變得更容易了！</span><span class="sxs-lookup"><span data-stu-id="21411-1419">**Collaborate more effectively with @Mentions in Comments:** Collaboration just became a whole lot easier!</span></span> <span data-ttu-id="21411-1420">現在您可以在文件註解中 @提及小組成員，而他們會自動收到電子郵件通知，並將他們帶至該文件中。</span><span class="sxs-lookup"><span data-stu-id="21411-1420">Now you can @mention teammates in document comments and they will automatically receive an email notification drawing them into the document.</span></span>

- <span data-ttu-id="21411-1421">**共同撰寫合併增強功能：** 共同撰寫已改善使用條件式格式設定、儲存格樣式、範圍保護、檢視格線和跨工作表剪下/貼上時的合併成功率。</span><span class="sxs-lookup"><span data-stu-id="21411-1421">**Coauthoring merge improvements:** Coauthoring has improved the merge success rate when working with conditional formatting, cell styles, range protection, view gridlines, and cross-sheet cut/paste.</span></span> 

### <a name="outlook"></a><span data-ttu-id="21411-1422">Outlook</span><span class="sxs-lookup"><span data-stu-id="21411-1422">Outlook</span></span>

- <span data-ttu-id="21411-1423">**快速新增帳戶的方式：** 由於帳戶設定已改善，您現在可以更輕鬆地將使用雙因素驗證的 Outlook.com 和 Gmail 帳戶新增到 Outlook。</span><span class="sxs-lookup"><span data-stu-id="21411-1423">**A quicker way to add accounts:** Thanks to account setup improvements, it's easier than ever to add Outlook.com and Gmail accounts that use 2-factor authentication to Outlook.</span></span> [<span data-ttu-id="21411-1424">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1424">Learn more</span></span>](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="21411-1425">PowerPoint：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1425">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="21411-1426">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="21411-1426">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="21411-1427">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="21411-1427">Switching between them has never been easier.</span></span> [<span data-ttu-id="21411-1428">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1428">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="21411-1429">**即時的輔助字幕和翻譯字幕：** 簡報者的文字會自動顯示為畫面上的標題，或翻譯為所選語言的字幕。</span><span class="sxs-lookup"><span data-stu-id="21411-1429">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="21411-1430">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1430">Learn more</span></span>](https://support.office.com/article/d68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="21411-1431">**即將推出：** 查看 Office 即將推出的新鮮變更，立即試用並給予我們意見反應。</span><span class="sxs-lookup"><span data-stu-id="21411-1431">**Coming Soon:** See what exciting changes are Coming Soon to Office, try them out and give us feedback.</span></span> [<span data-ttu-id="21411-1432">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1432">Learn more</span></span>](https://support.office.com/article/7800e0cf0-812f-475a-80aa-d47376e076f2)

- <span data-ttu-id="21411-1433">**在註解中使用 @Mentions 提及功能，讓共同作業更有效率：** 共同作業變得更容易了！</span><span class="sxs-lookup"><span data-stu-id="21411-1433">**Collaborate more effectively with @Mentions in Comments:** Collaboration just became a whole lot easier!</span></span> <span data-ttu-id="21411-1434">現在您可以在文件註解中 @提及小組成員，而他們會自動收到電子郵件通知，並將他們帶至該文件中。</span><span class="sxs-lookup"><span data-stu-id="21411-1434">Now you can @mention teammates in document comments and they will automatically receive an email notification drawing them into the document.</span></span>

### <a name="project-feature-updates"></a><span data-ttu-id="21411-1435">Project：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1435">Project: Feature updates</span></span>

- <span data-ttu-id="21411-1436">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="21411-1436">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="21411-1437">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="21411-1437">Switching between them has never been easier.</span></span> [<span data-ttu-id="21411-1438">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1438">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio-feature-updates"></a><span data-ttu-id="21411-1439">Visio：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1439">Visio: Feature updates</span></span>

- <span data-ttu-id="21411-1440">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="21411-1440">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="21411-1441">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="21411-1441">Switching between them has never been easier.</span></span> [<span data-ttu-id="21411-1442">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1442">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="21411-1443">**匯出成 PDF、PPT 或針對電子郵件訂閱而設定的 Power BI 報表現在也將具備 Visio 視覺效果：** 如果您將 Power BI 報表匯出成 PDF、PPT，或為其設定電子郵件訂閱，Visio 視覺效果將會以這些匯出的格式完美地呈現。</span><span class="sxs-lookup"><span data-stu-id="21411-1443">**Power BI reports exported to PDF, PPT or set up for email subscription will now feature Visio Visual as well:** If you export your Power BI reports to PDF, PPT or set up an email subscription for them, Visio Visual will render in these exported formats seamlessly.</span></span> [<span data-ttu-id="21411-1444">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1444">Learn more</span></span>](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word-feature-updates"></a><span data-ttu-id="21411-1445">Word：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1445">Word: Feature updates</span></span>  

- <span data-ttu-id="21411-1446">**在註解中使用 @Mentions 提及功能，讓共同作業更有效率：** 共同作業變得更容易了！</span><span class="sxs-lookup"><span data-stu-id="21411-1446">**Collaborate more effectively with @Mentions in Comments:** Collaboration just became a whole lot easier!</span></span> <span data-ttu-id="21411-1447">現在您可以在文件註解中 @提及小組成員，而他們會自動收到電子郵件通知，並將他們帶至該文件中。</span><span class="sxs-lookup"><span data-stu-id="21411-1447">Now you can @mention teammates in document comments and they will automatically receive an email notification drawing them into the document.</span></span>

- <span data-ttu-id="21411-1448">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="21411-1448">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="21411-1449">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="21411-1449">Switching between them has never been easier.</span></span> [<span data-ttu-id="21411-1450">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1450">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="21411-1451">**[學習工具] 模式額外支援更多頁面色彩：** Word 中的 [學習工具] 新增更多頁面佈景主題色彩的支援，讓您能夠變更頁面的背景色彩。</span><span class="sxs-lookup"><span data-stu-id="21411-1451">**Learning Tools mode has additional support for more page colors:** Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span>  <span data-ttu-id="21411-1452">許多人在背景全白或全黑時閱讀會有困難，因此我們在 PC 和 Mac 的 Word 中增加了色彩選項。</span><span class="sxs-lookup"><span data-stu-id="21411-1452">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

- <span data-ttu-id="21411-1453">**即將推出：** 查看 Office 即將推出的新鮮變更，立即試用並給予我們意見反應。</span><span class="sxs-lookup"><span data-stu-id="21411-1453">**Coming Soon:** See what exciting changes are Coming Soon to Office, try them out and give us feedback.</span></span> [<span data-ttu-id="21411-1454">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1454">Learn more</span></span>](https://support.office.com/article/7800e0cf0-812f-475a-80aa-d47376e076f2)

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="21411-1455">商務用 Skype：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1455">Skype for Business: Non-security updates</span></span>

- <span data-ttu-id="21411-1456">為商務用 Skype Online 使用者提供選項以停用 [新增相片 - 幫助人們了解您] 上下文提示。</span><span class="sxs-lookup"><span data-stu-id="21411-1456">Provides the option to Skype for Business Online users to disable the "Add your photo - it'll help people get to know you" contextual tip.</span></span> <span data-ttu-id="21411-1457">若要啟用此修正程式，您可以[深入了解](https://support.microsoft.com/help/4503469)。</span><span class="sxs-lookup"><span data-stu-id="21411-1457">To enable this fix, you can [Learn more](https://support.microsoft.com/help/4503469).</span></span>

- <span data-ttu-id="21411-1458">防止在重新啟動商務用 Skype 後，總是啟用第二個響鈴設定。</span><span class="sxs-lookup"><span data-stu-id="21411-1458">Prevents secondary ringer setting from always being enabled after restarting Skype for Business.</span></span> <span data-ttu-id="21411-1459">若要啟用此修正程式，您可以[深入了解](https://support.microsoft.com/help/4503470)。</span><span class="sxs-lookup"><span data-stu-id="21411-1459">To enable this fix, you can [Learn more](https://support.microsoft.com/help/4503470).</span></span>

 - <span data-ttu-id="21411-1460">修正當加入大型會議同時使用 Lync SDK 型應用程式時，商務用 Skype 停止回應的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1460">Fix for an issue that made Skype for Business stop responding when joining a large meeting while also using a Lync SDK-based application.</span></span> <span data-ttu-id="21411-1461">若要啟用此修正程式，您可以[深入了解](https://support.microsoft.com/help/4503472)。</span><span class="sxs-lookup"><span data-stu-id="21411-1461">To enable this fix, you can [Learn more](https://support.microsoft.com/help/4503472).</span></span>

## <a name="version-1904-may-22"></a><span data-ttu-id="21411-1462">版本 1904：5 月 22 日</span><span class="sxs-lookup"><span data-stu-id="21411-1462">Version 1904: May 22</span></span>
<span data-ttu-id="21411-1463">*版本 1904 (組建 11601.20230)*</span><span class="sxs-lookup"><span data-stu-id="21411-1463">*Version 1904 (Build 11601.20230)*</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="21411-1464">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1464">Office Suite: Non-security updates</span></span>

- <span data-ttu-id="21411-1465">這解決了使用者在選取並提交其隱私權等級的選項後，在每次啟動應用程序時都會看到新隱私權提示的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1465">This addresses an issue where users see the new Privacy Prompt on every application launch even after selecting and committing a choice for their privacy level.</span></span>

## <a name="version-1904-may-14"></a><span data-ttu-id="21411-1466">版本 1904：5 月 14 日</span><span class="sxs-lookup"><span data-stu-id="21411-1466">Version 1904: May 14</span></span> 
<span data-ttu-id="21411-1467">*版本 1904 (組建 11601.20204)*</span><span class="sxs-lookup"><span data-stu-id="21411-1467">*Version 1904 (Build 11601.20204)*</span></span>

- <span data-ttu-id="21411-1468">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="21411-1468">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

## <a name="version-1904-may-8"></a><span data-ttu-id="21411-1469">版本 1904：5 月 8 日</span><span class="sxs-lookup"><span data-stu-id="21411-1469">Version 1904: May 8</span></span>
<span data-ttu-id="21411-1470">*版本 1904 (組建 11601.20178)*</span><span class="sxs-lookup"><span data-stu-id="21411-1470">*Version 1904 (Build 11601.20178)*</span></span>

- <span data-ttu-id="21411-1471">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="21411-1471">Various bugs and performances fixes.</span></span>

## <a name="version-1904-april-29"></a><span data-ttu-id="21411-1472">版本 1904：4 月 29 日</span><span class="sxs-lookup"><span data-stu-id="21411-1472">Version 1904: April 29</span></span>
<span data-ttu-id="21411-1473">*版本 1904 (組建 11601.20144)*</span><span class="sxs-lookup"><span data-stu-id="21411-1473">*Version 1904 (Build 11601.20144)*</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="21411-1474">Excel：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1474">Excel: Feature updates</span></span>

- <span data-ttu-id="21411-1475">**快速找到該檔案：** 想要尋找最近使用過的檔案嗎？</span><span class="sxs-lookup"><span data-stu-id="21411-1475">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="21411-1476">只要在 [檔案] > [常用] 頁面的 [搜尋] 方塊中輸入，就能找到所需的檔案。</span><span class="sxs-lookup"><span data-stu-id="21411-1476">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="21411-1477">Outlook：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1477">Outlook: Feature updates</span></span>

- <span data-ttu-id="21411-1478">**將您的 LinkedIn 人際網路連接至 Outlook：** 安全地將您的 LinkedIn 帳戶與 Microsoft 帳戶連結，以直接在人員卡片中查看 LinkedIn 個人資料中的資訊。</span><span class="sxs-lookup"><span data-stu-id="21411-1478">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="21411-1479">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1479">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="21411-1480">PowerPoint：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1480">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="21411-1481">**快速找到該檔案：** 想要尋找最近使用過的檔案嗎？</span><span class="sxs-lookup"><span data-stu-id="21411-1481">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="21411-1482">只要在 [檔案] > [常用] 頁面的 [搜尋] 方塊中輸入，就能找到所需的檔案。</span><span class="sxs-lookup"><span data-stu-id="21411-1482">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="21411-1483">Word：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1483">Word: Feature updates</span></span>

- <span data-ttu-id="21411-1484">**追蹤修訂、註解和即時共同作業的色彩會同步：** 我們產品中的修正現在可確保註解、追蹤修訂及共同作業者的游標會以相同色彩顯示。</span><span class="sxs-lookup"><span data-stu-id="21411-1484">**Colors for Track Changes, Comments and Real-Time Collaboration in Sync:** Fixes in our product now ensure that the comments, track changes and the cursor for a collaborator show up in the same color.</span></span>

- <span data-ttu-id="21411-1485">**快速找到該檔案：** 想要尋找最近使用過的檔案嗎？</span><span class="sxs-lookup"><span data-stu-id="21411-1485">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="21411-1486">只要在 [檔案] > [常用] 頁面的 [搜尋] 方塊中輸入，就能找到所需的檔案。</span><span class="sxs-lookup"><span data-stu-id="21411-1486">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="21411-1487">Visio：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1487">Visio: Feature updates</span></span>

- <span data-ttu-id="21411-1488">**將進度圖表匯出到 Word：** 在 Word 文件中自動新增圖表內容，如圖案和中繼資料。</span><span class="sxs-lookup"><span data-stu-id="21411-1488">**Export process diagrams to Word:** Automatically add diagram content, such as shapes and metadata, to a Word document.</span></span> <span data-ttu-id="21411-1489">然後，自訂文件來建立程序指導方針和操作手冊。</span><span class="sxs-lookup"><span data-stu-id="21411-1489">Then customize the document to create process guidelines and operation manuals.</span></span> [<span data-ttu-id="21411-1490">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1490">Learn more</span></span>](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

### <a name="office-suite-feature-updates"></a><span data-ttu-id="21411-1491">Office 套件：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1491">Office Suite: Feature updates</span></span>

- <span data-ttu-id="21411-1492">**新圖示：** 根據您的意見反應，我們新增了超過 300 個新圖示。</span><span class="sxs-lookup"><span data-stu-id="21411-1492">**New icons:** We've added over 300 new icons based on your feedback.</span></span> <span data-ttu-id="21411-1493">使用功能區 [插入] 索引標籤上的 [圖示] 按鈕，即可以找到它們。</span><span class="sxs-lookup"><span data-stu-id="21411-1493">You'll find them using the Icons button on the Insert tab of the ribbon.</span></span>

- <span data-ttu-id="21411-1494">**隱私權控制：** 用於診斷資料的連線體驗的新增、更新及改良的控制項。</span><span class="sxs-lookup"><span data-stu-id="21411-1494">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> [<span data-ttu-id="21411-1495">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1495">Learn more</span></span>](/DeployOffice/privacy/overview-privacy-controls?toc=%2fdeployoffice%2ftoc.json)

### <a name="outlook-non-security-updates"></a><span data-ttu-id="21411-1496">Outlook：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1496">Outlook: Non-security updates</span></span>

- <span data-ttu-id="21411-1497">修正導致將主旨顯示得極小的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1497">Fixed an issue causing the subject to show extremely small.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="21411-1498">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1498">Office Suite: Non-security updates</span></span>
- <span data-ttu-id="21411-1499">修正不正確地將平假名和漢字中的日本新年號 "Reiwa" (令和) 識別為拼字錯誤或不合文法的運算式的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1499">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="21411-1500">修正以 SYSTEM 身分執行 Proxy 驗證時會封鎖 Office 更新的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1500">Fixed an issue that blocked Office Updates when proxy authentication runs as SYSTEM.</span></span>

## <a name="version-1903-april-23"></a><span data-ttu-id="21411-1501">版本 1903：4 月 23 日</span><span class="sxs-lookup"><span data-stu-id="21411-1501">Version 1903: April 23</span></span>
<span data-ttu-id="21411-1502">版本 1903 (組建 11425.20244)</span><span class="sxs-lookup"><span data-stu-id="21411-1502">*Version 1903 (Build 11425.20244)*</span></span>

- <span data-ttu-id="21411-1503">不同的錯誤 (bug) 和效能修正。</span><span class="sxs-lookup"><span data-stu-id="21411-1503">Various bugs and performances fixes.</span></span>

## <a name="version-1903-april-17"></a><span data-ttu-id="21411-1504">版本 1903：4 月 17 日</span><span class="sxs-lookup"><span data-stu-id="21411-1504">Version 1903: April 17</span></span>
<span data-ttu-id="21411-1505">*版本 1903 (組建 11425.20228)*</span><span class="sxs-lookup"><span data-stu-id="21411-1505">*Version 1903 (Build 11425.20228)*</span></span>

- <span data-ttu-id="21411-1506">不同的錯誤 (bug) 和效能修正。</span><span class="sxs-lookup"><span data-stu-id="21411-1506">Various bugs and performances fixes.</span></span>

## <a name="version-1903-april-16"></a><span data-ttu-id="21411-1507">版本 1903：4 月 16 日</span><span class="sxs-lookup"><span data-stu-id="21411-1507">Version 1903: April 16</span></span>
<span data-ttu-id="21411-1508">*版本 1903 (組建 11425.20218)*</span><span class="sxs-lookup"><span data-stu-id="21411-1508">*Version 1903 (Build 11425.20218)*</span></span>

- <span data-ttu-id="21411-1509">不同的錯誤 (bug) 和效能修正。</span><span class="sxs-lookup"><span data-stu-id="21411-1509">Various bugs and performances fixes.</span></span>

## <a name="version-1903-april-9"></a><span data-ttu-id="21411-1510">版本 1903：4 月 9 日</span><span class="sxs-lookup"><span data-stu-id="21411-1510">Version 1903: April 9</span></span>
<span data-ttu-id="21411-1511">*版本 1903 (組建 11425.20204)*</span><span class="sxs-lookup"><span data-stu-id="21411-1511">*Version 1903 (Build 11425.20204)*</span></span> 

- <span data-ttu-id="21411-1512">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="21411-1512">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="21411-1513">商務用 Skype：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1513">Skype for Business: Non-security updates</span></span>
- <span data-ttu-id="21411-1514">已修正 Lync (商務用 Skype) 中的問題，在其中，當任何線上會議具有 7 位以上參與者時，會議視窗可能會消失。</span><span class="sxs-lookup"><span data-stu-id="21411-1514">Fixed an issue in Lync (Skype for Business) where for any online meeting with more 7+ participants, the meeting window can disappear.</span></span>

## <a name="version-1903-april-01"></a><span data-ttu-id="21411-1515">版本 1903：4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="21411-1515">Version 1903: April 01</span></span>
<span data-ttu-id="21411-1516">*版本 1903 (組建 11425.20202)*</span><span class="sxs-lookup"><span data-stu-id="21411-1516">*Version 1903 (Build 11425.20202)*</span></span> 

### <a name="excel-feature-updates"></a><span data-ttu-id="21411-1517">Excel：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1517">Excel: Feature updates</span></span>

- <span data-ttu-id="21411-1518">**Excel 的深入解析：** 深入分析可為廣泛的使用者帶來價值。</span><span class="sxs-lookup"><span data-stu-id="21411-1518">**Insights in Excel:** Insights provides value to a range of users.</span></span> <span data-ttu-id="21411-1519">深入分析為資料分析提供較柔和的方法，並為其他人提供您的資料的不同觀點。</span><span class="sxs-lookup"><span data-stu-id="21411-1519">Insights provides a softer approach to data analysis and for others it provides a different perspective to your data.</span></span> [<span data-ttu-id="21411-1520">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1520">Learn more</span></span>](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)


- <span data-ttu-id="21411-1521">**提高內容的方便使用性：** 想要讓您的試算表更易於使用嗎？</span><span class="sxs-lookup"><span data-stu-id="21411-1521">**Increase the reach of your content:**  Need to make your spreadsheets accessible?</span></span> <span data-ttu-id="21411-1522">讓協助工具檢查程式來幫助您，您不需要自行處理。</span><span class="sxs-lookup"><span data-stu-id="21411-1522">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="21411-1523">按一下 [校閱] > [檢查協助工具] 試試看這個功能，我們會在狀態列上告訴您需要留意的部分。</span><span class="sxs-lookup"><span data-stu-id="21411-1523">Try it by clicking Review > Check Accessibility and we’ll tell you when we find something you need to look at in the status bar.</span></span>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="21411-1524">PowerPoint：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1524">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="21411-1525">**更順暢的變形** 為圖形命名，進一步控制圖形的轉化效果。</span><span class="sxs-lookup"><span data-stu-id="21411-1525">**Better shapeshifting:**  Name your shapes for more control over how they morph.</span></span> [<span data-ttu-id="21411-1526">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1526">Learn more</span></span>](https://support.office.com/article/9bc7f48ff-f152-4ee8-9081-d3121788024f)

- <span data-ttu-id="21411-1527">**提高內容的方便使用性：** 想要讓您的簡報更易於使用嗎？</span><span class="sxs-lookup"><span data-stu-id="21411-1527">**Increase the reach of your content:**  Need to make your presentations accessible?</span></span> <span data-ttu-id="21411-1528">讓協助工具檢查程式來幫助您，您不需要自行處理。</span><span class="sxs-lookup"><span data-stu-id="21411-1528">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="21411-1529">按一下 [校閱] > [檢查協助工具] 試試看這個功能 – 我們會在狀態列上告訴您需要留意的部分。</span><span class="sxs-lookup"><span data-stu-id="21411-1529">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="21411-p274">**當您可以重複使用時為什麼要重新打造？**  重複使用您所建立的投影片或其他人與您共用的投影片來以節省時間。</span><span class="sxs-lookup"><span data-stu-id="21411-p274">**Why reinvent when you can re-use?**  Save time by re-using slides that you created or that others have shared with you.</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="21411-1532">Excel：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1532">Excel: Non-security updates</span></span>

- <span data-ttu-id="21411-1533">修正 Excel 中合併衝突的問題，此問題會造成提示使用者重新開啟活頁簿以取得變更。</span><span class="sxs-lookup"><span data-stu-id="21411-1533">Fixed a merge conflict issue in Excel  that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="21411-1534">商務用 Skype：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1534">Skype for Business: Non-security updates</span></span>

- <span data-ttu-id="21411-1535">修正因第三方 SfB / Lync SDK 應用程式存在，而導致商務用 Skype 在回應聊天通知時停止回應的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1535">Fix for issue that caused Skype for Business to stop responding when responding to chat notifications if 3rd party SfB/Lync SDK app present.</span></span>
- <span data-ttu-id="21411-1536">修正將特定剪貼簿內容貼到聊天時，應用程式當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1536">Fix for app crash when specific clipboard content is pasted into a chat.</span></span>
- <span data-ttu-id="21411-1537">修正由其中一位通話專員接聽的通話佇列通話的「接受者」資訊無法顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1537">Fix for issue that prevented display of the "accepted by" information for a Call Queue call that's picked up by one of the call agents.</span></span>
- <span data-ttu-id="21411-1538">已修正當 Teams 使用者加入商務用 Skype 會議時，通話圖示隱藏的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1538">Fixed issue that hid call icons when a Teams user joins a Skype for Business meeting.</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="21411-1539">Word：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1539">Word: Feature updates</span></span>

- <span data-ttu-id="21411-1540">**提高內容的方便使用性：** 想要讓您的文件更易於使用嗎？</span><span class="sxs-lookup"><span data-stu-id="21411-1540">**Increase the reach of your content:**  Need to make your documents accessible?</span></span> <span data-ttu-id="21411-1541">讓協助工具檢查程式來幫助您，您不需要自行處理。</span><span class="sxs-lookup"><span data-stu-id="21411-1541">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="21411-1542">按一下 [校閱] > [檢查協助工具] 試試看這個功能 – 我們會在狀態列上告訴您需要留意的部分。</span><span class="sxs-lookup"><span data-stu-id="21411-1542">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

## <a name="version-1902-march-25"></a><span data-ttu-id="21411-1543">版本 1902：3 月 25 日</span><span class="sxs-lookup"><span data-stu-id="21411-1543">Version 1902: March 25</span></span>
<span data-ttu-id="21411-1544">*版本 1902 (組建 11328.20222)*</span><span class="sxs-lookup"><span data-stu-id="21411-1544">*Version 1902 (Build 11328.20222)*</span></span>

- <span data-ttu-id="21411-1545">不同的錯誤 (bug) 和效能修正。</span><span class="sxs-lookup"><span data-stu-id="21411-1545">Various bugs and performances fixes.</span></span>

## <a name="version-1902-march-12"></a><span data-ttu-id="21411-1546">版本 1902：3 月 12 日</span><span class="sxs-lookup"><span data-stu-id="21411-1546">Version 1902: March 12</span></span>
<span data-ttu-id="21411-1547">*版本 1902 (組建 11328.20158)*</span><span class="sxs-lookup"><span data-stu-id="21411-1547">*Version 1902 (Build 11328.20158)*</span></span> 

- <span data-ttu-id="21411-1548">不同的錯誤 (bug) 和效能修正。</span><span class="sxs-lookup"><span data-stu-id="21411-1548">Various bugs and performances fixes.</span></span>

## <a name="version-1902-march-4"></a><span data-ttu-id="21411-1549">版本 1902：3 月 4 日</span><span class="sxs-lookup"><span data-stu-id="21411-1549">Version 1902: March 4</span></span>
<span data-ttu-id="21411-1550">*版本 1902 (組建 11328.20146)*</span><span class="sxs-lookup"><span data-stu-id="21411-1550">*Version 1902 (Build 11328.20146)*</span></span> 

### <a name="access-feature-updates"></a><span data-ttu-id="21411-1551">Access：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1551">Access: Feature updates</span></span>

- <span data-ttu-id="21411-1552">**將索引標籤保留在資料庫物件上：** 能清楚看到使用中的索引標籤、輕鬆拖曳索引標籤來重新排列，只要按一下就能關閉資料庫物件。</span><span class="sxs-lookup"><span data-stu-id="21411-1552">**Keep tabs on your database objects:** Clearly see the active tab, easily drag tabs to rearrange them, and close database objects with just one click.</span></span>
- <span data-ttu-id="21411-p276">**使用更大的空間來縮放：** 加大 [縮放] 方塊、變更字型、記憶縮放。[深入了解](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)</span><span class="sxs-lookup"><span data-stu-id="21411-p276">**Zoom with more room:** Make the Zoom box bigger, change the font, and Zoom remembers it all. [Learn more](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="21411-1555">Excel：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1555">Excel: Feature updates</span></span>

- <span data-ttu-id="21411-p277">**使用 \@ 提及取得他人注意** 在註解中使用 @ 提及功能讓同事知道您需要他們提供建議。[深入了解](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)</span><span class="sxs-lookup"><span data-stu-id="21411-p277">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input. [Learn more](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)</span></span>
- <span data-ttu-id="21411-p278">**更深入地探索您的資料：** 新的 [構想] 按鈕可尋找資料的模式，並使用模式建立更有智慧且個人化的建議。[深入了解](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span><span class="sxs-lookup"><span data-stu-id="21411-p278">**Discover more about your data:** The new Ideas button looks for patterns in your data, and uses them to create intelligent, personalized suggestions. [Learn more](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span></span>
- <span data-ttu-id="21411-1560">**隨時儲存變更：** 將檔案上傳至 OneDrive，確保所有的更新都會自動儲存。</span><span class="sxs-lookup"><span data-stu-id="21411-1560">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>
- <span data-ttu-id="21411-p279">**能在套用篩選時插入 SVG：** Office 使用者現在可以在套用篩選的同時，插入 SVG。[深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="21411-p279">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="21411-1563">Outlook：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1563">Outlook: Feature updates</span></span>

- <span data-ttu-id="21411-p280">**在連續會議之間置入時間：** 將會議預設為提早 5-10 分鐘結束，讓出席者有時間休息，或在前往下一個地點。[深入了解](https://support.office.com/article/Schedule-a-meeting-with-other-people-5C9877BC-AB91-4A7C-99FB-B0B68D7EA94F#BKMK_endmeetingsearly)</span><span class="sxs-lookup"><span data-stu-id="21411-p280">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to end 5-10 minutes early by default. [Learn more](https://support.office.com/article/Schedule-a-meeting-with-other-people-5C9877BC-AB91-4A7C-99FB-B0B68D7EA94F#BKMK_endmeetingsearly)</span></span>
- <span data-ttu-id="21411-p281">**使用「大聲朗讀」聆聽您的電子郵件：** Outlook 可以大聲朗讀您的電子郵件，強調所朗讀的文字。若要開啟 [大聲朗讀]，請移至 [輕鬆存取] 設定。[深入了解](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)</span><span class="sxs-lookup"><span data-stu-id="21411-p281">**Use Read Aloud to listen to your email:** Outlook can read your email aloud, highlighting text as it's read. To turn on Read Aloud, go to the Ease of Access settings. [Learn more](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)</span></span>
- <span data-ttu-id="21411-p282">**能在套用篩選時插入 SVG：** Office 使用者現在可以在套用篩選的同時，插入 SVG。[深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="21411-p282">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="21411-1571">PowerPoint：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1571">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="21411-p283">**輕鬆插入內嵌影片：** 想要在您的投影片中放入 Vimeo 或 YouTube 影片嗎？只要有影片頁面連結即可。[深入了解](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span><span class="sxs-lookup"><span data-stu-id="21411-p283">**Inserting an online video is easier than ever:** Want to put a video from Vimeo or YouTube on your slide? The video page link is all you need. [Learn more](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span></span>
- <span data-ttu-id="21411-p284">**您來計算，格式設定交給我們** 我們能將難懂的手寫數學運算式變更為標準字元。只要選擇 [筆跡轉換數學]，然後選取您的手寫筆記，即可開始使用。[深入了解](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="21411-p284">**You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>
- <span data-ttu-id="21411-1578">**隨時儲存變更：** 將檔案上傳至 OneDrive，確保所有的更新都會自動儲存。</span><span class="sxs-lookup"><span data-stu-id="21411-1578">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>
- <span data-ttu-id="21411-p285">**能在套用篩選時插入 SVG：** Office 使用者現在可以在套用篩選的同時，插入 SVG。[深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="21411-p285">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>
- <span data-ttu-id="21411-1581">**大型檔案現在會以更快速度開啟：** 現在開啟儲存在 OneDrive 或 SharePoint 上的檔案時，會在背景下載影像、影片及其他大型元素。</span><span class="sxs-lookup"><span data-stu-id="21411-1581">**Large files now open faster:** Images, videos, and other large elements now download in the background when opening files stored on OneDrive or SharePoint.</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="21411-1582">Word：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1582">Word: Feature updates</span></span>

- <span data-ttu-id="21411-1583">**隨時儲存變更：** 將檔案上傳至 OneDrive，確保所有的更新都會自動儲存。</span><span class="sxs-lookup"><span data-stu-id="21411-1583">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>
- <span data-ttu-id="21411-p286">**了解自動儲存未開啟的原因！** 在自動儲存功能關閉時按一下 [自動儲存] 開關現在會將顯示一個有用的註標，說明自動儲存關閉的可能原因。造成自動儲存無法運作的唯一原因，就是文件不在 OneDrive 或 SharePoint 上，而我們將一鍵按鈕功能來方便移動文件。</span><span class="sxs-lookup"><span data-stu-id="21411-p286">**Find out why AutoSave isn't on!** Clicking on the AutoSave toggle when it's off will now either display a helpful callout with reasons why AutoSave might be off. In the case where the only reason preventing AutoSave is the fact that the document is not on OneDrive or SharePoint, we will offer to move the document conveniently with one button click!</span></span>
- <span data-ttu-id="21411-p287">**能在套用篩選時插入 SVG：** Office 使用者現在可以在套用篩選的同時，插入 SVG。[深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="21411-p287">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>
 
### <a name="office-suite-feature-updates"></a><span data-ttu-id="21411-1589">Office 套件：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1589">Office Suite: Feature updates</span></span>

- <span data-ttu-id="21411-p288">**安裝 Microsoft Teams：** 在 Office 365 專業增強版的新安裝中，預設會安裝 Microsoft Teams。[深入了解](/DeployOffice/teams-install)</span><span class="sxs-lookup"><span data-stu-id="21411-p288">**Installation of Microsoft Teams:**  Microsoft Teams is installed by default for new installations of Office 365 ProPlus. [Learn More](/DeployOffice/teams-install)</span></span>

## <a name="version-1901-february-12"></a><span data-ttu-id="21411-1592">版本 1901：2 月 12 日</span><span class="sxs-lookup"><span data-stu-id="21411-1592">Version 1901: February 12</span></span>
<span data-ttu-id="21411-1593">*版本 1901 (組建 11231.20174)*</span><span class="sxs-lookup"><span data-stu-id="21411-1593">*Version 1901 (Build 11231.20174)*</span></span> 

<span data-ttu-id="21411-1594">安全性更新列於[此處](microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="21411-1594">Security updates listed [here](microsoft365-apps-security-updates.md)</span></span>

## <a name="version-1901-january-31"></a><span data-ttu-id="21411-1595">版本 1901：1 月 31 日</span><span class="sxs-lookup"><span data-stu-id="21411-1595">Version 1901: January 31</span></span>
<span data-ttu-id="21411-1596">*版本 1901 (組建 11231.20130)*</span><span class="sxs-lookup"><span data-stu-id="21411-1596">*Version 1901 (Build 11231.20130)*</span></span> 

### <a name="excel-feature-updates"></a><span data-ttu-id="21411-1597">Excel：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1597">Excel: Feature updates</span></span>

- <span data-ttu-id="21411-p289">**利用註解共同作業：** 使用內建的回覆方塊，在試算表中進行交談。[深入了解](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)</span><span class="sxs-lookup"><span data-stu-id="21411-p289">**Collaborate with comments:** Keep the conversation going right in your spreadsheet with the built-in reply box. [Learn more](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="21411-1600">Outlook：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1600">Outlook: Feature updates</span></span>

- <span data-ttu-id="21411-p290">**他們會看到您的 meme：** 如果使用文字或靜態影像還不足以清楚表達您的想法，您可以使用動畫 GIF。[深入了解](https://support.office.com/article/114BB251-861F-41CD-B20F-7E7289630C5B)</span><span class="sxs-lookup"><span data-stu-id="21411-p290">**They'll see what you meme:** When text or static images just won't do, use an animated GIF to make your point. [Learn more](https://support.office.com/article/114BB251-861F-41CD-B20F-7E7289630C5B)</span></span>
 
### <a name="visio-feature-updates"></a><span data-ttu-id="21411-1603">Visio：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1603">Visio: Feature updates</span></span>

- <span data-ttu-id="21411-1604">**資料流程圖上的 Double-Take：** 資料視覺化工具流程圖美觀的新版面配置，既清新、簡潔且更易於了解。</span><span class="sxs-lookup"><span data-stu-id="21411-1604">**Double-take on data flowcharts:** Gorgeous new layouts for Data Visualizer flowcharts are clean, crisp, and easy to understand.</span></span> [<span data-ttu-id="21411-1605">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1605">Learn more</span></span>](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)

- <span data-ttu-id="21411-p292">**內建的 Azure 樣板：** 使用數十種 Azure 樣板來設計雲端應用程式或規劃架構。[深入了解](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)</span><span class="sxs-lookup"><span data-stu-id="21411-p292">**Azure stencils built right in:** Design a cloud app or plan an architecture using dozens of Azure stencils. [Learn more](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="21411-1608">Word：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1608">Word: Feature updates</span></span>

- <span data-ttu-id="21411-p293">**為靜態文件注入動人的生命力：** 將文件轉變為在任何裝置上，均具有完美外觀的可互動、易分享的網頁。[深入了解](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span><span class="sxs-lookup"><span data-stu-id="21411-p293">**Take your doc from static to stunning:** Transform your document into an interactive, easy-to-share web page that looks great on any device. [Learn more](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span></span>

### <a name="office-suite-feature-updates"></a><span data-ttu-id="21411-1611">Office 套件：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1611">Office Suite: Feature updates</span></span>

- <span data-ttu-id="21411-p294">**Office 第三方應用程式現在已使用 office.js api 擁有插入 SVG 支援的功能：** 亦稱為 Office 增益集的第三方應用程式現在擁有插入 SVG 的功能。使用者現在可以將個人的 SVG 集合連線至 Office。開發人員現在可以使用 Office.js API 來使用這項功能。</span><span class="sxs-lookup"><span data-stu-id="21411-p294">**Office 3rd Party Applications now have insert SVG support using the office.js api:** 3rd party applications also known as add-ins in Office now have the ability to insert SVG's. Users can now connect their personal collection of SVG's to Office. Developers can use this feature by using the Office.js API.</span></span>


## <a name="version-1812-january-14"></a><span data-ttu-id="21411-1615">版本 1812：1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="21411-1615">Version 1812: January 14</span></span>
<span data-ttu-id="21411-1616">*版本 1812 (組建 11126.20266)*</span><span class="sxs-lookup"><span data-stu-id="21411-1616">*Version 1812 (Build 11126.20266)*</span></span> 

<span data-ttu-id="21411-1617">僅含解決效能問題的非安全性更新。</span><span class="sxs-lookup"><span data-stu-id="21411-1617">Non-security updates only, addressing performance issues.</span></span>

## <a name="version-1812-january-8"></a><span data-ttu-id="21411-1618">版本 1812：1 月 8 日</span><span class="sxs-lookup"><span data-stu-id="21411-1618">Version 1812: January 8</span></span>
<span data-ttu-id="21411-1619">*版本 1812 (組建 11126.20196)*</span><span class="sxs-lookup"><span data-stu-id="21411-1619">*Version 1812 (Build 11126.20196)*</span></span> 

### <a name="project-non-security-updates"></a><span data-ttu-id="21411-1620">Project：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1620">Project: Non-security updates</span></span>
- <span data-ttu-id="21411-1621">已修正以下問題：核取甘特圖的 [要徑]、[落後] 和 [寬限時間] 長條圖樣式後，無法取消核取。</span><span class="sxs-lookup"><span data-stu-id="21411-1621">Fixed an issue where you couldn't uncheck the Critical, Late and Slack bar styles for the Gantt chart after you checked one.</span></span>

## <a name="version-1812-january-3"></a><span data-ttu-id="21411-1622">版本 1812：1 月 3 日</span><span class="sxs-lookup"><span data-stu-id="21411-1622">Version 1812: January 3</span></span>
<span data-ttu-id="21411-1623">*版本 1812 (組建 11126.20188)*</span><span class="sxs-lookup"><span data-stu-id="21411-1623">*Version 1812 (Build 11126.20188)*</span></span> 

### <a name="excel-feature-updates"></a><span data-ttu-id="21411-1624">Excel：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1624">Excel: Feature updates</span></span>

- <span data-ttu-id="21411-p295">**在您工作的同時，持續執行協助工具檢查程式：** 不用一直開啟協助工具檢查程式，仍然可以追蹤文件內是否有協助工具問題。透過狀態列上的指示器 (與拼字檢查類似)，Excel 可在您工作的同時，標示出找到的協助工具問題。</span><span class="sxs-lookup"><span data-stu-id="21411-p295">**Keep accessibility checker running while you work:** Keep track of accessibility issues in your document without needing the accessibility checker always open. Via an indicator in the status bar, much like spellcheck, Excel flags found accessibility issues while you are working.</span></span> 

### <a name="outlook-feature-updates"></a><span data-ttu-id="21411-1627">Outlook：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1627">Outlook: Feature updates</span></span>

- <span data-ttu-id="21411-p296">**集中所有加密選項：** 只要前往 [選項] > [加密]，即可選擇要用來保護電子郵件訊息的方法。[深入了解](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="21411-p296">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="21411-1630">PowerPoint：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1630">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="21411-p297">**運用筆跡製作精彩的投影片：** 將筆跡轉換成標準圖形和文字，然後從 PowerPoint 設計工具吸取智慧的投影片設計概念。[深入了解](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)</span><span class="sxs-lookup"><span data-stu-id="21411-p297">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer. [Learn more](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)</span></span>
- <span data-ttu-id="21411-p298">**在您工作的同時，持續執行協助工具檢查程式：** 不用一直開啟協助工具檢查程式，仍然可以追蹤文件內是否有協助工具問題。透過狀態列上的指示器 (與拼字檢查類似)，PowerPoint 可在您工作的同時，標示出找到的協助工具問題。</span><span class="sxs-lookup"><span data-stu-id="21411-p298">**Keep accessibility checker running while you work:** Keep track of accessibility issues in your document without needing the accessibility checker always open. Via an indicator in the status bar, much like spellcheck, PowerPoint flags found accessibility issues while you are working.</span></span> 

### <a name="word-feature-updates"></a><span data-ttu-id="21411-1635">Word：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1635">Word: Feature updates</span></span>

- <span data-ttu-id="21411-p299">**運用行聚焦，提高理解力：** 毫不費力地逐行瀏覽文件。調整焦點，在檢視畫面中一次放入一行、三行或五行。[深入了解](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="21411-p299">**Improve comprehension with Line Focus:** Move through a document line by line without distractions. Adjust the focus to put one, three, or five lines in view at a time. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>
- <span data-ttu-id="21411-p300">**在您工作的同時，持續執行協助工具檢查程式：** 不用一直開啟協助工具檢查程式，仍然可以追蹤文件內是否有協助工具問題。透過狀態列上的指示器 (與拼字檢查類似)，Word 可在您工作的同時，標示出找到的協助工具問題。</span><span class="sxs-lookup"><span data-stu-id="21411-p300">**Keep accessibility checker running while you work:** Keep track of accessibility issues in your document without needing the accessibility checker always open. Via an indicator in the status bar, much like spellcheck, Word flags found accessibility issues while you are working.</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="21411-1641">Visio：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1641">Visio: Feature updates</span></span>

- <span data-ttu-id="21411-p301">**告別錯誤的 Excel 連結：** 找不到與 Data Visualizer 圖表連結的 Excel 活頁簿嗎？重新連結，就可繼續使用了。[深入了解](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span><span class="sxs-lookup"><span data-stu-id="21411-p301">**Say goodbye to broken Excel links:** Can't find the Excel workbook linked to your Data Visualizer diagram? Relink it, and you're back in business. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span></span>

### <a name="office-suite-feature-updates"></a><span data-ttu-id="21411-1645">Office 套件：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1645">Office Suite: Feature updates</span></span>

- <span data-ttu-id="21411-1646">**新增功能窗格：**[新增功能] 體驗已移至 [說明] 窗格，讓您可以更輕鬆地存取最新更新，並掌握最新消息。</span><span class="sxs-lookup"><span data-stu-id="21411-1646">**What's New Pane:** The What's New experience has moved to the Help Pane, so you can more easily access and stay up to date with our latest updates.</span></span>

## <a name="version-1811-december-11"></a><span data-ttu-id="21411-1647">版本 1811：12 月 11 日</span><span class="sxs-lookup"><span data-stu-id="21411-1647">Version 1811: December 11</span></span>
<span data-ttu-id="21411-1648">*版本 1811 (組建 11029.20108)*</span><span class="sxs-lookup"><span data-stu-id="21411-1648">*Version 1811 (Build 11029.20108)*</span></span> 

 ### <a name="excel-security-updates"></a><span data-ttu-id="21411-1649">Excel：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1649">Excel: Security updates</span></span> 

-   <span data-ttu-id="21411-1650">[CVE-2018-8597](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8597)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1650">[CVE-2018-8597](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8597): Microsoft Excel Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="21411-1651">[CVE-2018-8598](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8598)：Microsoft Excel 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1651">[CVE-2018-8598](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8598): Microsoft Excel Information Disclosure Vulnerability</span></span> 
-   <span data-ttu-id="21411-1652">[CVE-2018-8627](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8627)：Microsoft Excel 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1652">[CVE-2018-8627](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8627): Microsoft Excel Information Disclosure Vulnerability</span></span> 
-   <span data-ttu-id="21411-1653">[CVE-2018-8636](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8636)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1653">[CVE-2018-8636](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8636): Microsoft Excel Remote Code Execution Vulnerability</span></span> 

### <a name="outlook-security-updates"></a><span data-ttu-id="21411-1654">Outlook：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1654">Outlook: Security updates</span></span> 

-   <span data-ttu-id="21411-1655">[CVE-2018-8587](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8587)：Microsoft Outlook 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1655">[CVE-2018-8587](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8587): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 

### <a name="powerpoint-security-updates"></a><span data-ttu-id="21411-1656">PowerPoint：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1656">PowerPoint: Security updates</span></span> 

-   <span data-ttu-id="21411-1657">[CVE-2018-8628](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8628)：Microsoft PowerPoint 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1657">[CVE-2018-8628](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8628): Microsoft PowerPoint Remote Code Execution Vulnerability</span></span> 


## <a name="version-1811-november-27"></a><span data-ttu-id="21411-1658">版本 1811：11 月 27 日</span><span class="sxs-lookup"><span data-stu-id="21411-1658">Version 1811: November 27</span></span>
<span data-ttu-id="21411-1659">*版本 1811 (組建 11029.20079)*</span><span class="sxs-lookup"><span data-stu-id="21411-1659">*Version 1811 (Build 11029.20079)*</span></span> 

### <a name="access-feature-updates"></a><span data-ttu-id="21411-1660">Access：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1660">Access: Feature updates</span></span>

- <span data-ttu-id="21411-p302">**繪製成黑色、繪製成灰色：** 依照您的喜好變更 Access 的外觀。有四個佈景主題可供選擇：彩色、深灰色、黑色或白色。[深入了解](https://support.office.com/article/9d76a8b4-bfff-48a9-b8c8-8e133461bc94)</span><span class="sxs-lookup"><span data-stu-id="21411-p302">**Paint it black, paint it gray:** Change the look of Access as often as you like. Four themes to choose from: Colorful, Dark Gray, Black, or White. [Learn more](https://support.office.com/article/9d76a8b4-bfff-48a9-b8c8-8e133461bc94)</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="21411-1664">Outlook：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1664">Outlook: Feature updates</span></span>

- <span data-ttu-id="21411-p303">**縮放與搖桿：** 選擇要用於所有郵件的預設值，而不用在每次讀取郵件時調整 [縮放]。[深入了解](https://support.office.com/article/56c090bc-e148-44a7-bd06-1290edd38983)</span><span class="sxs-lookup"><span data-stu-id="21411-p303">**Zoom and stick:** Instead of adjusting Zoom each time you read a message, choose a default to use for all your messages.  [Learn more](https://support.office.com/article/56c090bc-e148-44a7-bd06-1290edd38983)</span></span>
- <span data-ttu-id="21411-1667">**在移動郵件時繼續作業：** Outlook 現在會在背景中移動郵件，因此，在資料夾之間移動大量郵件時您可以繼續作業。</span><span class="sxs-lookup"><span data-stu-id="21411-1667">**Keep working while moving messages:** Outlook now moves messages in the background, so you can keep working while moving lots of messages between folders.</span></span>
- <span data-ttu-id="21411-p304">**改善焦點收件匣的開啟和關閉體驗：** 對於沒有使用焦點收件匣的客戶，我們已在所有資料夾的郵件清單中恢復 [未讀取] 索引標籤。我們也新增了以旗標為依據的排序功能，讓您能更輕鬆地找到加上旗標的項目。最後，焦點收件匣有更好的互動搜尋模型：焦點收件匣會保留到使用者開始進行搜尋，然後我們在搜尋完成後顯示「結果」文字為止。</span><span class="sxs-lookup"><span data-stu-id="21411-p304">**Polished the Focused Inbox on and off experiences:** For customers that do not use Focused Inbox, we brought back the Unread tab in the message list across all folders. We also added a sort by Flag to make it easier to find flagged items. Finally, Focused Inbox has a better interaction model with search: Focused Inbox remains until a user starts to search and we show 'Results' text shown after a search completes.</span></span>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="21411-1671">PowerPoint：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1671">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="21411-p305">**在印出的講義上看到投影片編號：** 將投影片編號新增至講義的列印複本。[深入了解](https://support.office.com/article/91c62c83-9032-497c-ab76-cae8f3e1a402)</span><span class="sxs-lookup"><span data-stu-id="21411-p305">**See slide number on printed handouts:** Add slide number to the print copy of your handouts. [Learn more](https://support.office.com/article/91c62c83-9032-497c-ab76-cae8f3e1a402)</span></span>

### <a name="office-suite-feature-updates"></a><span data-ttu-id="21411-1674">Office 套件：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1674">Office Suite: Feature updates</span></span>

- <span data-ttu-id="21411-p306">**利用 [資訊位置] 中新公開的按鈕共用及上傳文件：**[共用]、[將路徑複製到剪貼簿] 及 [開啟檔案位置] 按鈕先前只能在文件儲存路徑後面存取。您現在可以在 [資訊位置] 中清楚地看到這些按鈕！瀏覽至 [檔案] > [資訊] 時通常會看到這些新按鈕。</span><span class="sxs-lookup"><span data-stu-id="21411-p306">**Share and upload your documents with the new exposed buttons in the Info Place:** Previously Share, Copy Path to Clipboard, and Open File Location buttons were only accessible behind the document save path. Now they're buttons you can clearly see in the Info Place! Navigate to File > Info as you normally would to see these new buttons.</span></span>


## <a name="version-1810-november-13"></a><span data-ttu-id="21411-1678">版本 1810：11 月 13 日</span><span class="sxs-lookup"><span data-stu-id="21411-1678">Version 1810: November 13</span></span>
<span data-ttu-id="21411-1679">*版本 1810 (組建 11001.20108)*</span><span class="sxs-lookup"><span data-stu-id="21411-1679">*Version 1810 (Build 11001.20108)*</span></span> 

### <a name="excel-security-updates"></a><span data-ttu-id="21411-1680">Excel：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1680">Excel: Security updates</span></span>

-   <span data-ttu-id="21411-1681">[CVE-2018-8574](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8574)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1681">[CVE-2018-8574](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8574): Microsoft Excel Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="21411-1682">[CVE-2018-8577](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8577)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1682">[CVE-2018-8577](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8577): Microsoft Excel Remote Code Execution Vulnerability</span></span> 

### <a name="outlook-security-updates"></a><span data-ttu-id="21411-1683">Outlook：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1683">Outlook: Security updates</span></span> 

-   <span data-ttu-id="21411-1684">[CVE-2018-8522](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8522)：Microsoft Outlook 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1684">[CVE-2018-8522](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8522): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="21411-1685">[CVE-2018-8524](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8524)：Microsoft Outlook 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1685">[CVE-2018-8524](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8524): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="21411-1686">[CVE-2018-8558](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8558)：Microsoft Outlook 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1686">[CVE-2018-8558](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8558): Microsoft Outlook Information Disclosure Vulnerability</span></span> 
-   <span data-ttu-id="21411-1687">[CVE-2018-8576](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8576)：Microsoft Outlook 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1687">[CVE-2018-8576](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8576): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="21411-1688">[CVE-2018-8579](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8579)：Microsoft Outlook 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1688">[CVE-2018-8579](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8579): Microsoft Outlook Information Disclosure Vulnerability</span></span> 
-   <span data-ttu-id="21411-1689">[CVE-2018-8582](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8582)：Microsoft Outlook 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1689">[CVE-2018-8582](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8582): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 

### <a name="project-security-updates"></a><span data-ttu-id="21411-1690">Project：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1690">Project: Security updates</span></span> 

-   <span data-ttu-id="21411-1691">[CVE-2018-8575](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8575)：Microsoft Project 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1691">[CVE-2018-8575](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8575): Microsoft Project Remote Code Execution Vulnerability</span></span> 

### <a name="word-security-updates"></a><span data-ttu-id="21411-1692">Word：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1692">Word: Security updates</span></span>  

-   <span data-ttu-id="21411-1693">[CVE-2018-8573](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8573)：Microsoft Word 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1693">[CVE-2018-8573](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8573): Microsoft Word Remote Code Execution Vulnerability</span></span> 

### <a name="skype-for-business-security-updates"></a><span data-ttu-id="21411-1694">商務用 Skype：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1694">Skype for Business: Security updates</span></span> 

-   <span data-ttu-id="21411-1695">[CVE-2018-8546](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8546)：Microsoft 商務用 Skype 阻絕服務弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1695">[CVE-2018-8546](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8546): Microsoft Skype for Business Denial of Service Vulnerability</span></span> 

 ### <a name="project-non-security-updates"></a><span data-ttu-id="21411-1696">Project：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1696">Project: Non-security Updates</span></span>

 - <span data-ttu-id="21411-1697">修正此問題：將專案儲存/發佈到 Project Online 時，狀態列不一定會更新至最新狀態。</span><span class="sxs-lookup"><span data-stu-id="21411-1697">Fixed an issue where when saving/publishing a project to Project Online, the status bar was not always updating to show the latest status.</span></span>
 - <span data-ttu-id="21411-1698">修正此問題：如果您使用新的新式體驗 SharePoint 文件庫上的 Project 檔案，「需要取出」和「唯讀」動作沒有正確執行。</span><span class="sxs-lookup"><span data-stu-id="21411-1698">Fixed an issue where if you were working with Project files on a SharePoint document library that was in the new modern experience, the Check-Out Required and Read-Only actions were not being correctly followed.</span></span>


## <a name="version-1810-october-29"></a><span data-ttu-id="21411-1699">版本 1810：10 月 29 日</span><span class="sxs-lookup"><span data-stu-id="21411-1699">Version 1810: October 29</span></span>
<span data-ttu-id="21411-1700">*版本 1810 (組建 11001.20074)*</span><span class="sxs-lookup"><span data-stu-id="21411-1700">*Version 1810 (Build 11001.20074)*</span></span> 

### <a name="excel-feature-updates"></a><span data-ttu-id="21411-1701">Excel：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1701">Excel: Feature updates</span></span> 

- <span data-ttu-id="21411-p307">**使用註解共同作業：** 使用內建的回覆方塊，在試算表中進行交談。[深入了解](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)</span><span class="sxs-lookup"><span data-stu-id="21411-p307">**Collaborate with comments:** Keep the conversation going right in your spreadsheet with the built-in reply box. [Learn more](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)</span></span>
- <span data-ttu-id="21411-p308">**股票報價唾手可得：** 擷取最新的股價、價格變化及其他新的股票資料類型。地理位置也有新的資料類型。[深入了解](https://support.office.com/article/61a33056-9935-484f-8ac8-f1a89e210877)</span><span class="sxs-lookup"><span data-stu-id="21411-p308">**Stock quotes at your fingertips:** Retrieve the latest stock price, change in price, and more with the new Stocks data type. There's a new data type for Geography too. [Learn more](https://support.office.com/article/61a33056-9935-484f-8ac8-f1a89e210877)</span></span>
- <span data-ttu-id="21411-p309">**顯示圖片後面的內容：** 將圖片放在工作表中、挑選您的預設，並觀看透明度變更。就這麼簡單！[深入了解](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span><span class="sxs-lookup"><span data-stu-id="21411-p309">**Reveal what's behind a picture:** Put a picture in a worksheet, pick your preset, and watch the transparency change. That's it! [Learn more](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span></span>
- <span data-ttu-id="21411-p310">**在資料編輯列中輕鬆編輯：** 您現在可以使用 CTRL + A 來選取儲存格或資料編輯列中的文字。另外也改善了 Emoji 和其他複雜字元的支援。[深入了解](https://support.office.com/article/402d8c2a-354c-4690-bacf-1c319c4ec2fb)</span><span class="sxs-lookup"><span data-stu-id="21411-p310">**Easy editing in the formula bar:** You can now use CTRL+A to select text in a cell or the formula bar. There's also improved support for emojis and other complex characters. [Learn more](https://support.office.com/article/402d8c2a-354c-4690-bacf-1c319c4ec2fb)</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="21411-1713">Outlook：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1713">Outlook: Feature updates</span></span> 

- <span data-ttu-id="21411-p311">**排程助理員中的人員建議：** 在您排定會議時查看對要新增之出席者的建議。不再來回切換排程助理員與收件者。[深入了解](https://support.office.com/article/d284c6d9-206e-4926-92b4-5addc0fcbefb)</span><span class="sxs-lookup"><span data-stu-id="21411-p311">**People suggestions in the Scheduling Assistant:** See recommendations for attendees to add when you schedule a meeting. No more switching back and forth between the Scheduling Assistant and the To line. [Learn more](https://support.office.com/article/d284c6d9-206e-4926-92b4-5addc0fcbefb)</span></span>
- <span data-ttu-id="21411-1717">**預留房間更加輕鬆：** 使用多個會議室清單尋找會議室 - 以及切換清單，而不會失去您已選取的會議室。</span><span class="sxs-lookup"><span data-stu-id="21411-1717">**Reserving a room just got easier:** Look for a conference room using more than one room list - and switch lists without losing rooms you've selected.</span></span>
- <span data-ttu-id="21411-p312">**停止看到過去事件的提醒：** 您可以設定行事曆，在事件結束之後自動關閉事件的提醒。[深入了解](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)</span><span class="sxs-lookup"><span data-stu-id="21411-p312">**Stop seeing reminders for past events:** You can set your calendar to automatically dismiss reminders for events after they've ended. [Learn more](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)</span></span>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="21411-1720">PowerPoint：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1720">PowerPoint: Feature updates</span></span> 

- <span data-ttu-id="21411-p313">**顯示圖片後面的內容：** 將圖片放在投影片中、挑選您的預設，並觀看透明度變更。就這麼簡單！[深入了解](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span><span class="sxs-lookup"><span data-stu-id="21411-p313">**Reveal what's behind a picture:** Put a picture on a slide,  pick your preset, and watch the transparency change. That's it! [Learn more](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span></span>
- <span data-ttu-id="21411-p314">**新的校對工具：** 不必對您的文筆沒信心。PowerPoint 現在提供文法及書寫建議。</span><span class="sxs-lookup"><span data-stu-id="21411-p314">**New proofreading tools:** Don't stress about your words. PowerPoint now provides grammar and writing suggestions.</span></span>
- <span data-ttu-id="21411-p315">**您素描，我修飾：** 我們可將手繪文字和形狀變為更精緻的圖表。只需選取您的筆跡線條即可開始。[深入了解](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="21411-p315">**You sketch, we polish:** We change hand-drawn text and shapes into refined diagrams. Just select your ink strokes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="21411-1729">Word：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1729">Word: Feature updates</span></span> 

- <span data-ttu-id="21411-p316">**顯示圖片後面的內容：** 將圖片放在文件中、挑選您的預設，並觀看透明度變更。就這麼簡單！[深入了解](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span><span class="sxs-lookup"><span data-stu-id="21411-p316">**Reveal what's behind a picture:** Put a picture in a document,  pick your preset, and watch the transparency change. That's it! [Learn more](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span></span>
- <span data-ttu-id="21411-p317">**生動地觀看您的文件：** 插入動畫 3D 圖形，來查看心跳、行星軌道，以及暴龍在整個頁面橫衝直撞。[深入了解](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)</span><span class="sxs-lookup"><span data-stu-id="21411-p317">**Watch your documents come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage across the page. [Learn more](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)</span></span>

### <a name="access-feature-updates"></a><span data-ttu-id="21411-1735">Access：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1735">Access: Feature updates</span></span> 
- <span data-ttu-id="21411-p318">**功能區圖示有了嶄新的外觀** 別擔心，一切照舊，而且它們在各種尺寸的螢幕上看起來都很棒。[深入了解](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span><span class="sxs-lookup"><span data-stu-id="21411-p318">**Your ribbon icons have a new look** Don’t worry, everything works the same. Plus, they look great on screens of all sizes. [Learn more](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span></span>

### <a name="publisher-feature-updates"></a><span data-ttu-id="21411-1739">Publisher：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1739">Publisher: Feature updates</span></span> 
- <span data-ttu-id="21411-p319">**功能區圖示有了嶄新的外觀** 別擔心，一切照舊，而且它們在各種尺寸的螢幕上看起來都很棒。[深入了解](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span><span class="sxs-lookup"><span data-stu-id="21411-p319">**Your ribbon icons have a new look** Don’t worry, everything works the same. Plus, they look great on screens of all sizes. [Learn more](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span></span>

### <a name="project-feature-updates"></a><span data-ttu-id="21411-1743">Project：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1743">Project: Feature updates</span></span> 
- <span data-ttu-id="21411-p320">**功能區圖示有了嶄新的外觀** 別擔心，一切照舊，而且它們在各種尺寸的螢幕上看起來都很棒。[深入了解](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span><span class="sxs-lookup"><span data-stu-id="21411-p320">**Your ribbon icons have a new look** Don’t worry, everything works the same. Plus, they look great on screens of all sizes. [Learn more](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="21411-1747">Visio：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1747">Visio: Feature updates</span></span> 
- <span data-ttu-id="21411-p321">**功能區圖示有了嶄新的外觀** 別擔心，一切照舊，而且它們在各種尺寸的螢幕上看起來都很棒。[深入了解](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span><span class="sxs-lookup"><span data-stu-id="21411-p321">**Your ribbon icons have a new look** Don’t worry, everything works the same. Plus, they look great on screens of all sizes. [Learn more](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span></span>


## <a name="version-1809-october-16"></a><span data-ttu-id="21411-1751">版本 1809：10 月 16 日</span><span class="sxs-lookup"><span data-stu-id="21411-1751">Version 1809: October 16</span></span>
<span data-ttu-id="21411-1752">*版本 1809 (組建 10827.20181)*</span><span class="sxs-lookup"><span data-stu-id="21411-1752">*Version 1809 (Build 10827.20181)*</span></span> 

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="21411-1753">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1753">Office suite: Non-Security updates</span></span> 
-  <span data-ttu-id="21411-1754">已修正各種效能問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1754">Fixed various performance issues.</span></span>


## <a name="version-1809-october-9"></a><span data-ttu-id="21411-1755">版本 1809：10 月 9 日</span><span class="sxs-lookup"><span data-stu-id="21411-1755">Version 1809: October 9</span></span>
<span data-ttu-id="21411-1756">*版本 1809 (組建 10827.20150)*</span><span class="sxs-lookup"><span data-stu-id="21411-1756">*Version 1809 (Build 10827.20150)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="21411-1757">Excel：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1757">Excel: Security updates</span></span>
-   <span data-ttu-id="21411-1758">[CVE-2018-8502](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8502)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1758">[CVE-2018-8502](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8502): Microsoft Excel Remote Code Execution Vulnerability</span></span> 

### <a name="outlook-security-updates"></a><span data-ttu-id="21411-1759">Outlook：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1759">Outlook: Security updates</span></span> 
-   <span data-ttu-id="21411-1760">[ADV180026](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/ADV180026)：Microsoft Office 深度防禦更新</span><span class="sxs-lookup"><span data-stu-id="21411-1760">[ADV180026](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/ADV180026): Microsoft Office Defense in Depth Update</span></span> 

### <a name="powerpoint-security-updates"></a><span data-ttu-id="21411-1761">PowerPoint：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1761">PowerPoint: Security updates</span></span> 
-   <span data-ttu-id="21411-1762">[CVE-2018-8501](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8501)：Microsoft PowerPoint 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1762">[CVE-2018-8501](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8501): Microsoft PowerPoint Remote Code Execution Vulnerability</span></span>

### <a name="word-security-updates"></a><span data-ttu-id="21411-1763">Word：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1763">Word: Security updates</span></span> 
-   <span data-ttu-id="21411-1764">[CVE-2018-8504](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8504)：Microsoft Word 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1764">[CVE-2018-8504](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8504): Microsoft Word Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="21411-1765">[ADV180026](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/ADV180026)：Microsoft Office 深度防禦更新</span><span class="sxs-lookup"><span data-stu-id="21411-1765">[ADV180026](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/ADV180026): Microsoft Office Defense in Depth Update</span></span> 

### <a name="office-suite-security-updates"></a><span data-ttu-id="21411-1766">Office 套件：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1766">Office suite: Security updates</span></span> 
-   <span data-ttu-id="21411-1767">[CVE-2018-8432](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8432)：Microsoft Graphics 元件遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1767">[CVE-2018-8432](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8432): Microsoft Graphics Components Remote Code Execution Vulnerability</span></span> 


## <a name="version-1809-september-27"></a><span data-ttu-id="21411-1768">版本 1809：9 月 27 日</span><span class="sxs-lookup"><span data-stu-id="21411-1768">Version 1809: September 27</span></span>
<span data-ttu-id="21411-1769">*版本 1809 (組建 10827.20138)*</span><span class="sxs-lookup"><span data-stu-id="21411-1769">*Version 1809 (Build 10827.20138)*</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="21411-1770">Excel：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1770">Excel: Feature Updates</span></span>
- <span data-ttu-id="21411-p322">**快速查閱** 我們已加速 VLOOKUP、HLOOKUP、MATCH 的計算速度，讓您能更快得到答案。[深入了解](https://support.office.com/article/60f18521-2589-4734-89dd-ba4ee1f6c000)</span><span class="sxs-lookup"><span data-stu-id="21411-p322">**Speedy Lookup** We've turbo-charged your VLOOKUP, HLOOKUP, and MATCH calculations so you can get answers faster. [Learn more](https://support.office.com/article/60f18521-2589-4734-89dd-ba4ee1f6c000)</span></span>
- <span data-ttu-id="21411-p323">**呼叫所有取得與轉換粉絲** 如果您經常使用取得與轉換，您會很高興知道我們已改善資料行來源範例功能。此外，也已改善許多連接器。[深入了解](https://support.office.com/article/ed01ec34-679d-48e7-ba49-bb14c7908f9e)</span><span class="sxs-lookup"><span data-stu-id="21411-p323">**Calling all Get & Transform fans** If you use Get & Transform a lot, you'll be happy to know that the Column From Example feature has been improved. And, many connectors have been improved as well. [Learn more](https://support.office.com/article/ed01ec34-679d-48e7-ba49-bb14c7908f9e)</span></span>
- <span data-ttu-id="21411-p324">**功能區圖示有了嶄新的外觀** 別擔心，一切照舊，而且它們在各種尺寸的螢幕上看起來都很棒。[深入了解](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span><span class="sxs-lookup"><span data-stu-id="21411-p324">**Your ribbon icons have a new look** Don’t worry, everything works the same. Plus, they look great on screens of all sizes. [Learn more](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="21411-1779">Outlook：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1779">Outlook: Feature Updates</span></span>
- <span data-ttu-id="21411-p325">**查看即將推出的功能** 在發行新的使用者體驗之前先行試用，讓我們知道您的想法。[深入了解](https://support.office.com/article/d4b7db49-b4e0-4f98-a0dc-156952e551e2)</span><span class="sxs-lookup"><span data-stu-id="21411-p325">**See what’s Coming Soon** Try out new user experiences before they’re released and let us know what you think. [Learn more](https://support.office.com/article/d4b7db49-b4e0-4f98-a0dc-156952e551e2)</span></span>
- <span data-ttu-id="21411-1782">**查看安全連結背後的 URL：** 安全連結可保護您防範在電子郵件中收到但隱藏原始 URL 的惡意 URL。</span><span class="sxs-lookup"><span data-stu-id="21411-1782">**See the URL behind Safe Links** Safe Links protects you from malicious URLS received in email but they hide the original URL.</span></span> <span data-ttu-id="21411-1783">若要查看原始 URL，請將滑鼠游標移到 URL 上。</span><span class="sxs-lookup"><span data-stu-id="21411-1783">To see the original, hover your mouse over the URL.</span></span> <span data-ttu-id="21411-1784">需要進階威脅防護授權。</span><span class="sxs-lookup"><span data-stu-id="21411-1784">Requires an Advanced Threat Protection license.</span></span> [<span data-ttu-id="21411-1785">深入了解</span><span class="sxs-lookup"><span data-stu-id="21411-1785">Learn more</span></span>](https://products.office.com/exchange/advance-threat-protection)
- <span data-ttu-id="21411-1786">**取得搜尋拼字建議** 在執行搜尋之後，Outlook 將提供拼字更正的建議搜尋查詢。</span><span class="sxs-lookup"><span data-stu-id="21411-1786">**Get search spelling suggestions** After performing a search, Outlook will provide a suggested search query with spelling corrections.</span></span>
- <span data-ttu-id="21411-p327">**功能區圖示有了嶄新的外觀** 別擔心，一切照舊，而且它們在各種尺寸的螢幕上看起來都很棒。[深入了解](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span><span class="sxs-lookup"><span data-stu-id="21411-p327">**Your ribbon icons have a new look** Don’t worry, everything works the same. Plus, they look great on screens of all sizes. [Learn more](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span></span>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="21411-1790">PowerPoint：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1790">PowerPoint: Feature Updates</span></span>
- <span data-ttu-id="21411-p328">**生動地觀看您的投影片** 插入動畫 3D 圖形，來查看心跳、行星軌道，以及暴龍在整個畫面橫衝直撞。[深入了解](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)</span><span class="sxs-lookup"><span data-stu-id="21411-p328">**Watch your slides come alive** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage across the screen.  [Learn more](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)</span></span>
- <span data-ttu-id="21411-p329">**功能區圖示有了嶄新的外觀** 別擔心，一切照舊，而且它們在各種尺寸的螢幕上看起來都很棒。[深入了解](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span><span class="sxs-lookup"><span data-stu-id="21411-p329">**Your ribbon icons have a new look** Don’t worry, everything works the same. Plus, they look great on screens of all sizes. [Learn more](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="21411-1796">Word：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1796">Word: Feature Updates</span></span>
- <span data-ttu-id="21411-p330">**使用 \@mentions 取得其注意** 在註解中使用 @mentions，讓同事知道您何時需要其輸入。[深入了解](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)</span><span class="sxs-lookup"><span data-stu-id="21411-p330">**Get their attention with \@mentions** Use @mentions in comments to let co-workers know when you need their input. [Learn more](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)</span></span>
- <span data-ttu-id="21411-p331">**功能區圖示有了嶄新的外觀** 別擔心，一切照舊，而且它們在各種尺寸的螢幕上看起來都很棒。[深入了解](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span><span class="sxs-lookup"><span data-stu-id="21411-p331">**Your ribbon icons have a new look** Don’t worry, everything works the same. Plus, they look great on screens of all sizes. [Learn more](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span></span>
- <span data-ttu-id="21411-1802">**方程式編輯器轉換程式** 此轉換程式可讓使用者將使用 Microsoft 方程式編輯器建立的方程式轉換為 Office 數學 ML 格式，以啟用編輯。</span><span class="sxs-lookup"><span data-stu-id="21411-1802">**Equation Editor converter** Converter allows users to convert equations created using Microsoft Equation editor to Office Math ML format to enable editing.</span></span>
- <span data-ttu-id="21411-p332">**為靜態文件注入動人的生命力** 將文件轉變為在任何裝置上，均具有完美外觀的可互動、易分享的網頁。[深入了解](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span><span class="sxs-lookup"><span data-stu-id="21411-p332">**Take your doc from static to stunning** Transform your document into an interactive, easy-to-share web page that looks great on any device. [Learn more](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span></span>

## <a name="version-1808-september-11"></a><span data-ttu-id="21411-1805">版本 1808：9 月 11 日</span><span class="sxs-lookup"><span data-stu-id="21411-1805">Version 1808: September 11</span></span>
<span data-ttu-id="21411-1806">*版本 1808 (組建 10730.20102)*</span><span class="sxs-lookup"><span data-stu-id="21411-1806">*Version 1808 (Build 10730.20102)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="21411-1807">Excel：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1807">Excel: Security updates</span></span>
-   <span data-ttu-id="21411-1808">[CVE-2018-8331](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8331)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1808">[CVE-2018-8331](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8331): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="21411-1809">[CVE-2018-8429](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8429)：Microsoft Excel 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1809">[CVE-2018-8429](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8429): Microsoft Excel Information Disclosure Vulnerability</span></span>

### <a name="word-security-updates"></a><span data-ttu-id="21411-1810">Word：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1810">Word: Security updates</span></span>
-   <span data-ttu-id="21411-1811">[CVE-2018-8430](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8430)：Windows PDF 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1811">[CVE-2018-8430](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8430): Word PDF Remote Code Execution Vulnerability</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="21411-1812">Office 套件：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1812">Office suite: Security updates</span></span>
-   <span data-ttu-id="21411-1813">[CVE-2018-8332](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8332)：Win32k 圖形遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1813">[CVE-2018-8332](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8332): Win32k Graphics Remote Code Execution Vulnerability</span></span>


## <a name="version-1808-september-5"></a><span data-ttu-id="21411-1814">版本 1808：9 月 5 日</span><span class="sxs-lookup"><span data-stu-id="21411-1814">Version 1808: September 5</span></span>
<span data-ttu-id="21411-1815">*版本 1808 (組建 10730.20088)*</span><span class="sxs-lookup"><span data-stu-id="21411-1815">*Version 1808 (Build 10730.20088)*</span></span>

### <a name="access-feature-updates"></a><span data-ttu-id="21411-1816">Access：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1816">Access: Feature Updates</span></span>
 - <span data-ttu-id="21411-p333">**重新整理、重新連結或移除連結的資料表** 更新的連結資料表管理員是用於管理所有資料來源與連結資料表的位置。[深入了解](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)</span><span class="sxs-lookup"><span data-stu-id="21411-p333">**Refresh, relink, or remove linked tables** The updated Linked Table Manager is the location for managing all data sources and linked tables. [Learn more](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="21411-1819">Outlook：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1819">Outlook: Feature Updates</span></span>
 - <span data-ttu-id="21411-p334">**關閉會議的轉寄** 防止出席者將您的會議轉寄給其他人。只需移至功能區，按一下 [回應選項] 即可。[深入了解](https://support.office.com/article/5C9877BC-AB91-4A7C-99FB-B0B68D7EA94F)</span><span class="sxs-lookup"><span data-stu-id="21411-p334">**Turn off forwarding for a meeting** Prevent attendees from forwarding your meeting to others. Just go to the ribbon and click Response Options. [Learn more](https://support.office.com/article/5C9877BC-AB91-4A7C-99FB-B0B68D7EA94F)</span></span>
 
### <a name="visio-feature-updates"></a><span data-ttu-id="21411-1823">Visio：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1823">Visio: Feature Updates</span></span>
 - <span data-ttu-id="21411-1824">**在下一個圖表中享受圖示時刻** 從 26 個圖案中挑選，其中的圖示表示分析、藝術、慶典、臉、運動和其他。</span><span class="sxs-lookup"><span data-stu-id="21411-1824">**Enjoy an iconic moment in your next diagram** Pick from 26 new stencils with icons for analytics, arts, celebration, faces, sports, and more.</span></span> 
 - <span data-ttu-id="21411-p335">**從 Visio 圖形建立 Word 文件：** 自動將圖表內容 (包括圖形和中繼資料) 新增至 Word 文件。然後自訂文件以建立程序指導方針和操作手冊。[深入了解](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)</span><span class="sxs-lookup"><span data-stu-id="21411-p335">**Build a Word document out of Visio shapes** Automatically add diagram content, including shapes and metadata, to a Word document. Then customize the document to create process guidelines and operation manuals. [Learn more](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)</span></span>
 - <span data-ttu-id="21411-p336">**Visio 與 Power BI：更好的搭配** 只需按幾下，即可將您的 Visio 圖表轉換成互動式 Power BI 視覺效果。[深入了解](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)</span><span class="sxs-lookup"><span data-stu-id="21411-p336">**Visio and Power BI: Better together** In just a few clicks, turn your Visio diagram into an interactive Power BI visualization. [Learn more](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)</span></span>

 ### <a name="project-feature-updates"></a><span data-ttu-id="21411-1830">Project：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1830">Project: Feature Updates</span></span>
 - <span data-ttu-id="21411-p337">**在工作面板卡片上查看詳細資訊** 當單獨標題不能訴說故事時，請自訂您的工作面板卡片，以顯示所有最重要的詳細資料。[深入了解](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)</span><span class="sxs-lookup"><span data-stu-id="21411-p337">**See more info on Task Board cards** When the title alone doesn’t tell the story, customize your Task Board cards to show all the most important details. [Learn more](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="21411-1833">Excel：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1833">Excel: Non-security updates</span></span>
-  <span data-ttu-id="21411-1834">已修正 Excel 中的問題，其中標示使用者選取以進行複製之儲存格範圍的虛線，並不會消失，而且甚至在後續的使用者作業 (例如貼上) 之後仍會保留在剪貼簿中。</span><span class="sxs-lookup"><span data-stu-id="21411-1834">Fixes an issue in Excel wherein the dotted line marking the range of cells that a user selected for copying does not disappear and remains in clipboard even after a subsequent user operation like paste.</span></span> 

### <a name="outlook-non-security-updates"></a><span data-ttu-id="21411-1835">Outlook：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1835">Outlook: Non-security updates</span></span>
 - <span data-ttu-id="21411-1836">對於一些已設定多個 Exchange 帳戶的使用者，已解決導致「按一下以檢視其他...」連結從搜尋結果清單中遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1836">Addresses an issue that caused the "Click to view more..." link to be missing from the search results list for some users with multiple Exchange accounts configured.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="21411-1837">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1837">Office Suite: Non-security updates</span></span>
 - <span data-ttu-id="21411-1838">已修正導致更新安裝在特定情況下需要很長時間的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1838">Fixed an issue that caused update install to take a long time in certain scenarios.</span></span>
 
### <a name="lync-non-security-updates"></a><span data-ttu-id="21411-1839">Lync：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1839">Lync: Non-security updates</span></span>
 - <span data-ttu-id="21411-1840">已修正阻止在 IM 訊息中顯示表情符號的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1840">Fixes an issue that prevented emoticons in IM messages from being displayed.</span></span> 


## <a name="version-1807-august-14"></a><span data-ttu-id="21411-1841">版本 1807：8 月 14 日</span><span class="sxs-lookup"><span data-stu-id="21411-1841">Version 1807: August 14</span></span>
<span data-ttu-id="21411-1842">*版本 1807 (組建 10325.20118)*</span><span class="sxs-lookup"><span data-stu-id="21411-1842">*Version 1807 (Build 10325.20118)*</span></span>

### <a name="access-security-updates"></a><span data-ttu-id="21411-1843">Access：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1843">Access: Security updates</span></span>
-   <span data-ttu-id="21411-1844">[CVE-2018-8312](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8312)：Microsoft Access 遠端程式碼執行 Use After Free 弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1844">[CVE-2018-8312](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8312): Microsoft Access Remote Code Execution Use After Free Vulnerability</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="21411-1845">Excel：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1845">Excel: Security updates</span></span>
-   <span data-ttu-id="21411-1846">[CVE-2018-8375](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8375)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1846">[CVE-2018-8375](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8375): Microsoft Excel Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="21411-1847">[CVE-2018-8379](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8379)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1847">[CVE-2018-8379](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8379): Microsoft Excel Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="21411-1848">[CVE-2018-8382](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8382)：Microsoft Excel 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1848">[CVE-2018-8382](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8382): Microsoft Excel Information Disclosure Vulnerability</span></span> 

### <a name="outlook-security-updates"></a><span data-ttu-id="21411-1849">Outlook：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1849">Outlook: Security updates</span></span>
-   <span data-ttu-id="21411-1850">[ADV180021](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/ADV180021)：Microsoft Office 深度防禦更新</span><span class="sxs-lookup"><span data-stu-id="21411-1850">[ADV180021](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/ADV180021): Microsoft Office Defense in Depth Update</span></span> 

### <a name="office-suite-security-updates"></a><span data-ttu-id="21411-1851">Office 套件：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1851">Office Suite: Security updates</span></span>
-   <span data-ttu-id="21411-1852">[CVE-2018-8378](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8378)：Microsoft Office 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1852">[CVE-2018-8378](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8378): Microsoft Office Information Disclosure Vulnerability</span></span> 

## <a name="version-1807-july-25"></a><span data-ttu-id="21411-1853">版本 1807：7 月 25 日</span><span class="sxs-lookup"><span data-stu-id="21411-1853">Version 1807: July 25</span></span>
<span data-ttu-id="21411-1854">*版本 1807 (組建 10325.20082)*</span><span class="sxs-lookup"><span data-stu-id="21411-1854">*Version 1807 (Build 10325.20082)*</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="21411-1855">Outlook：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1855">Outlook: Feature updates</span></span>
- <span data-ttu-id="21411-p338">**Outlook 增益集警告：** 有時 Outlook COM 增益集會發生問題，讓其餘 Outlook 功能變慢。這些問題可能是因為以下的事件延遲：在 Outlook 資料夾之間進行切換、新的電子郵件送達、開啟行事曆項目等等。當這類問題發生時，Outlook 會在通知列中顯示警告。</span><span class="sxs-lookup"><span data-stu-id="21411-p338">**Outlook add-in warnings:** Occasionally an Outlook COM add-in can encounter problems that slows down the rest of Outlook. These problems could be due to latency of events such as switching between Outlook folders, arrival of new emails, opening Calendar items, etc. When such issues arise, Outlook will display a warning in the notification bar.</span></span>
- <span data-ttu-id="21411-p339">**從 Outlook 提醒對話方塊加入小組會議：** 當 Outlook 提醒使用者有即將來臨的會議時，如果即將來臨的會議是小組線上會議，則它會顯示 [線上加入] 按鈕。這個動作與從 Outlook [提醒] 對話方塊加入商務用 Skype 會議的體驗類似。</span><span class="sxs-lookup"><span data-stu-id="21411-p339">**Join Teams meetings from the Outlook Reminders dialog:** When Outlook reminds users of an upcoming meeting, it will show a Join Online button if the upcoming meeting is a Teams online meeting. This is similar to the experience of joining a Skype for Business meeting from the Outlook Reminders dialog.</span></span>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="21411-1860">PowerPoint：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1860">PowerPoint: Feature updates</span></span>
 - <span data-ttu-id="21411-p340">**超連結色彩：** 超連結不再只是藍色。套用您喜歡的任何字型色彩。[深入了解](https://support.office.com/article/988ed94c-82e9-4e2c-96a1-7ffd2c382ce8)</span><span class="sxs-lookup"><span data-stu-id="21411-p340">**Hyperlink colors:** Hyperlinks aren't just blue anymore. Apply any font color you like. [Learn more](https://support.office.com/article/988ed94c-82e9-4e2c-96a1-7ffd2c382ce8)</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="21411-1864">Visio：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1864">Visio: Feature updates</span></span>
 - <span data-ttu-id="21411-p341">**從 Visio 圖形建置 Word 文件：** 自動將圖表內容 (包括圖形和中繼資料) 新增至 Word 文件。然後自訂文件以建立程序指導方針和操作手冊。[深入了解](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)</span><span class="sxs-lookup"><span data-stu-id="21411-p341">**Build a Word document out of Visio shapes:** Automatically add diagram content, including shapes and metadata, to a Word document. Then customize the document to create process guidelines and operation manuals. [Learn more](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="21411-1868">Word：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1868">Word: Feature updates</span></span>
 - <span data-ttu-id="21411-1869">**使用 IRM 追蹤修訂：** 您現在可於 Word 中，在不需要完全控制使用權限的受 IRM 保護文件中使用「追蹤修訂」功能。</span><span class="sxs-lookup"><span data-stu-id="21411-1869">**Track changes with IRM:** You can now use the Track Changes feature in Word in IRM-protected documents without requiring the Full Control usage right.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="21411-1870">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1870">Office Suite: Non-security updates</span></span>
 - <span data-ttu-id="21411-1871">修正了防止部分使用者開啟受 IRM 保護的文件和電子郵件 (由其他組織中的人員與他們共用) 的一些問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1871">Fixed a set of issues that prevented some users from opening IRM-protected documents & emails that were shared with them by people in other organizations.</span></span>

## <a name="version-1806-july-17"></a><span data-ttu-id="21411-1872">版本 1806：7 月 17 日</span><span class="sxs-lookup"><span data-stu-id="21411-1872">Version 1806: July 17</span></span>
<span data-ttu-id="21411-1873">*版本 1806 (組建 10228.20134)*</span><span class="sxs-lookup"><span data-stu-id="21411-1873">*Version 1806 (Build 10228.20134)*</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="21411-1874">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1874">Office Suite: Non-security updates</span></span>
 - <span data-ttu-id="21411-1875">修正一些效能問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1875">Fixed some performance issues.</span></span>

## <a name="version-1806-july-10"></a><span data-ttu-id="21411-1876">版本 1806：7 月 10 日</span><span class="sxs-lookup"><span data-stu-id="21411-1876">Version 1806: July 10</span></span>
<span data-ttu-id="21411-1877">*版本 1806 (組建 10228.20104)*</span><span class="sxs-lookup"><span data-stu-id="21411-1877">*Version 1806 (Build 10228.20104)*</span></span>

### <a name="access-security-updates"></a><span data-ttu-id="21411-1878">Access：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1878">Access: Security updates</span></span>
-   <span data-ttu-id="21411-1879">[CVE-2018-8312](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8312)：Microsoft Access 遠端程式碼執行 Use After Free 弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1879">[CVE-2018-8312](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8312): Microsoft Access Remote Code Execution Use After Free Vulnerability</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="21411-1880">Outlook：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1880">Outlook: Security updates</span></span>
-   <span data-ttu-id="21411-1881">[CVE-2018-8310](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8310)：Microsoft Office 竄改弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1881">[CVE-2018-8310](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8310): Microsoft Office Tampering Vulnerability</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="21411-1882">Office 套件：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1882">Office Suite: Security updates</span></span>
-   <span data-ttu-id="21411-1883">[CVE-2018-8281](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8281)：Microsoft Office 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1883">[CVE-2018-8281](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8281): Microsoft Office Remote Code Execution Vulnerability</span></span>

## <a name="version-1806-june-25"></a><span data-ttu-id="21411-1884">版本 1806：6 月 25 日</span><span class="sxs-lookup"><span data-stu-id="21411-1884">Version 1806: June 25</span></span>
<span data-ttu-id="21411-1885">*版本 1806 (組建 10228.20080)*</span><span class="sxs-lookup"><span data-stu-id="21411-1885">*Version 1806 (Build 10228.20080)*</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="21411-1886">Excel：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1886">Excel: Feature updates</span></span>
- <span data-ttu-id="21411-p342">**改善儲存格和資料編輯列編輯：** 您現在可以使用 CTRL + A 來選取儲存格或資料編輯列中的文字。另外也改善了 Emoji 和其他複雜字元的支援。[深入了解](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)</span><span class="sxs-lookup"><span data-stu-id="21411-p342">**Improved cell and formula bar editing:** You can now use CTRL+A to select text in a cell or the formula bar. There's also improved support for emojis and other complex characters.[Learn more](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)</span></span>
- <span data-ttu-id="21411-p343">**改善 SVG 支援：** 您可以將已套用篩選的 SVG 插入。[深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="21411-p343">**Improved SVG support:** You can insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="21411-1891">Outlook：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1891">Outlook: Feature updates</span></span>
- <span data-ttu-id="21411-1892">**定期預設：** 在 [定期約會] 對話方塊中 (「定期範圍」下)，「結束日期」是預設設定 (而非「沒有結束日期」) 及列出的第一個設定，且會設定預設的結束日期。</span><span class="sxs-lookup"><span data-stu-id="21411-1892">**Recurrence default:** In the Appointment Recurrence dialog box (under "Range of recurrence"), “End by” is the default setting (instead of "No end date") and is the first setting listed, and a default end date is set.</span></span>
- <span data-ttu-id="21411-p344">**改善協助工具檢查程式︰** 協助工具檢查程式已更新對國際標準與建議的支援，以使您的郵件更易於存取。[深入了解](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span><span class="sxs-lookup"><span data-stu-id="21411-p344">**Accessibility Checker improvements:** The Accessibility Checker has updated support for international standards and recommendations to make your messages more accessible. [Learn more](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="21411-1895">PowerPoint：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1895">PowerPoint: Feature updates</span></span>
- <span data-ttu-id="21411-p345">**改善 SVG 支援：** 您可以將已套用篩選的 SVG 插入。[深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="21411-p345">**Improved SVG support:** You can insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>
- <span data-ttu-id="21411-p346">**使用手寫筆為投影片撰寫標題：** 使用手寫筆輸入標題，並觀看 PowerPoint 將它轉換成文字。[深入了解](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="21411-p346">**Title your slides with a pen:** Use your pen to ink in a title, and watch PowerPoint convert it to text. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

### <a name="project-feature-updates"></a><span data-ttu-id="21411-1900">Project：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1900">Project: Feature updates</span></span>
 - <span data-ttu-id="21411-p347">**使用最近的儲存位置保持組織：** 專案會保存您已儲存其他專案位置的持續清單。當您準備好要儲存專案時，只需選擇其中一個您最近的儲存位置，就能繼續進行您一天的工作。</span><span class="sxs-lookup"><span data-stu-id="21411-p347">**Stay organized with Recent save locations:** Project keeps a running list of where you've saved other projects. When you're ready to save your project, just choose one of your Recent save locations and get on with your day.</span></span>
 - <span data-ttu-id="21411-p348">**管理短期衝刺的全新方法：** 採取敏捷方式來使用工作面板。隨著專案的發展，請移至 [管理短期衝刺] 來新增或移除短期衝刺。</span><span class="sxs-lookup"><span data-stu-id="21411-p348">**A new way to manage sprints:** Take an agile approach to working with Task Boards. Go to Manage Sprints to add and remove sprints as your project evolves.</span></span>


### <a name="project-non-security-updates"></a><span data-ttu-id="21411-1905">Project：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1905">Project: Non-security updates</span></span>
 - <span data-ttu-id="21411-1906">修正此問題：儲存主專案中的子專案時會發生失敗。</span><span class="sxs-lookup"><span data-stu-id="21411-1906">Fixed an issue where saving sub-projects from master projects would fail.</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="21411-1907">Visio：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1907">Visio: Feature updates</span></span>
 - <span data-ttu-id="21411-1908">**更多樣板、更多圖示、更多選項：** 我們新增了 26 個樣板，包括「分析」、「藝術」、「慶祝」、「表情」、「位置」、「醫療」、「自然」、「人物」、「運動」、「天氣與季節」等等。</span><span class="sxs-lookup"><span data-stu-id="21411-1908">**More stencils, more icons, more choice:** We've added 26 stencils including Analytics, Arts, Celebration, Faces, Location, Medical, Nature, People, Sports, Weather and Seasons, and more.</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="21411-1909">Word：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1909">Word: Feature updates</span></span>
 - <span data-ttu-id="21411-p349">**改善 SVG 支援：** 您可以將已套用篩選的 SVG 插入。[深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="21411-p349">**Improved SVG support:** You can insert SVGs that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>



## <a name="version-1805-june-13"></a><span data-ttu-id="21411-1912">版本 1805：6 月 13 日</span><span class="sxs-lookup"><span data-stu-id="21411-1912">Version 1805: June 13</span></span>
<span data-ttu-id="21411-1913">*版本 1805 (組建 9330.2124)*</span><span class="sxs-lookup"><span data-stu-id="21411-1913">*Version 1805 (Build 9330.2124)*</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="21411-1914">Outlook 非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1914">Outlook Non-security updates</span></span>
 - <span data-ttu-id="21411-1915">修正當應用程式呼叫 MAPI API 時會造成當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1915">Fix an issue where an application calling the MAPI API could result in a crash.</span></span>



## <a name="version-1805-june-12"></a><span data-ttu-id="21411-1916">版本 1805：6 月 12 日</span><span class="sxs-lookup"><span data-stu-id="21411-1916">Version 1805: June 12</span></span>
<span data-ttu-id="21411-1917">*版本 1805 (組建 9330.2118)*</span><span class="sxs-lookup"><span data-stu-id="21411-1917">*Version 1805 (Build 9330.2118)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="21411-1918">Excel：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1918">Excel: Security updates</span></span>
-   <span data-ttu-id="21411-1919">[CVE-2018-8246](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8246)：Microsoft Excel 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1919">[CVE-2018-8246](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8246): Microsoft Excel Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="21411-1920">[CVE-2018-8248](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8248)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1920">[CVE-2018-8248](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8248): Microsoft Excel Remote Code Execution Vulnerability</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="21411-1921">Outlook：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1921">Outlook: Security updates</span></span>
-   <span data-ttu-id="21411-1922">[CVE-2018-8244](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8244)：Microsoft Outlook 提高權限弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1922">[CVE-2018-8244](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8244): Microsoft Outlook Elevation of Privilege Vulnerability</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="21411-1923">Outlook 非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1923">Outlook non-security updates</span></span>

- <span data-ttu-id="21411-1924">修正當應用程式呼叫 MAPI API 時會造成當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1924">Fix an issue where an application calling the MAPI API could result in a crash.</span></span>

### <a name="project-non-security-updates"></a><span data-ttu-id="21411-1925">Project 非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1925">Project Non-security updates</span></span>

- <span data-ttu-id="21411-1926">修正此問題：當您透過主要專案使用子專案時，系統阻止您儲存子專案。</span><span class="sxs-lookup"><span data-stu-id="21411-1926">Fix an issue where you are blocked from saving a sub project when working with them through the context of a master project.</span></span>

## <a name="version-1805-may-24"></a><span data-ttu-id="21411-1927">版本 1805：5 月 24 日</span><span class="sxs-lookup"><span data-stu-id="21411-1927">Version 1805: May 24</span></span>
<span data-ttu-id="21411-1928">*版本 1805 (組建 9330.2087)*</span><span class="sxs-lookup"><span data-stu-id="21411-1928">*Version 1805 (Build 9330.2087)*</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="21411-1929">Outlook 非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1929">Outlook Non-security updates</span></span>
 - <span data-ttu-id="21411-1930">修正 Outlook 在使用 iCloud 增益集時會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1930">Fix an issue where Outlook crashes when using the iCloud add-in.</span></span>
 


## <a name="version-1805-may-23"></a><span data-ttu-id="21411-1931">版本 1805：5 月 23 日</span><span class="sxs-lookup"><span data-stu-id="21411-1931">Version 1805: May 23</span></span>
<span data-ttu-id="21411-1932">*版本 1805 (組建 9330.2078)*</span><span class="sxs-lookup"><span data-stu-id="21411-1932">*Version 1805 (Build 9330.2078)*</span></span>

### <a name="access-feature-updates"></a><span data-ttu-id="21411-1933">Access：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1933">Access: Feature updates</span></span>
 - <span data-ttu-id="21411-p350">**使用新圖表以視覺化方式呈現資料：** 從 11 個圖表中選擇，並將其中一個新增至您的表單和報告，更有效地以視覺化方式呈現資料並進行明智的決策。[深入了解](https://support.office.com/article/1a463106-65d0-4dbb-9d66-4ecb737ea7f7)</span><span class="sxs-lookup"><span data-stu-id="21411-p350">**Visualize data with new charts:** Choose from 11 charts and add one to your forms and reports to better visualize the data and make informed decisions. [Learn more](https://support.office.com/article/1a463106-65d0-4dbb-9d66-4ecb737ea7f7)</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="21411-1936">Excel：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1936">Excel: Feature updates</span></span>
 - <span data-ttu-id="21411-p351">**在編輯時與共同作者交談：** 藉由與共同作者聊天，即可更有效率地共同作業而不需要離開 Excel。請注意，某些地區不提供這項功能。[深入了解](https://support.office.com/article/1ecc6c7f-0b02-4baa-b9d9-c9d67023bedd)</span><span class="sxs-lookup"><span data-stu-id="21411-p351">**Chat with co-authors while you edit:** Collaborate more effectively by chatting with your co-authors without ever leaving Excel. Note that this feature is not available in some regions.[Learn more](https://support.office.com/article/1ecc6c7f-0b02-4baa-b9d9-c9d67023bedd)</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="21411-1939">Outlook：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1939">Outlook: Feature updates</span></span>
 - <span data-ttu-id="21411-p352">**免操作輸入：** 使用您的語音直接聽寫以建立電子郵件。不需輸入。[深入了解](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)</span><span class="sxs-lookup"><span data-stu-id="21411-p352">**Hands free typing:** Use your voice to create emails by simply dictating. No need to type. [Learn more](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)</span></span>
 - <span data-ttu-id="21411-p353">**檢視 3 個時區：** 需要跨時區排程會議嗎？將多個時區新增至您的行事曆，輕鬆查看每個人的時程，並挑選出所有人都可以的時間。[深入了解](https://support.office.com/article/5ab3e10e-5a6c-46af-ab48-156fedf70c04)</span><span class="sxs-lookup"><span data-stu-id="21411-p353">**View 3 time zones:** Need to schedule a meeting across time zones? Add multiple time zones to your calendar to easily see everyone's availability and pick a time that works for all. [Learn more](https://support.office.com/article/5ab3e10e-5a6c-46af-ab48-156fedf70c04)</span></span>
 - <span data-ttu-id="21411-p354">**輕鬆共用行事曆：** 共用行事曆更加簡單，而且從 Outlook Desktop 共用的行事曆現在也可在 Outlook Mobile 中使用。[深入了解](https://support.office.com/article/353ed2c1-3ec5-449d-8c73-6931a0adab88)</span><span class="sxs-lookup"><span data-stu-id="21411-p354">**Calendar sharing made easy:** Sharing your calendars is simpler and calendars shared from Outlook Desktop are now also available in Outlook Mobile. [Learn more](https://support.office.com/article/353ed2c1-3ec5-449d-8c73-6931a0adab88)</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="21411-1948">Outlook：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1948">Outlook: Non-security updates</span></span>
- <span data-ttu-id="21411-1949">將共用行事曆邀請中的用語從「開啟此行事曆」變更為「接受」。</span><span class="sxs-lookup"><span data-stu-id="21411-1949">Change the wording in an invite to share a calendar from “Open this calendar” to “Accept.”</span></span>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="21411-1950">PowerPoint：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1950">PowerPoint: Feature updates</span></span>
 - <span data-ttu-id="21411-p355">**在編輯時與共同作者交談：** 藉由與共同作者聊天，即可更有效率地共同作業而不需要離開 PowerPoint。[深入了解](https://support.office.com/article/1ecc6c7f-0b02-4baa-b9d9-c9d67023bedd)</span><span class="sxs-lookup"><span data-stu-id="21411-p355">**Chat with co-authors while you edit:** Collaborate more effectively by chatting with your co-authors without ever leaving PowerPoint. [Learn more](https://support.office.com/article/1ecc6c7f-0b02-4baa-b9d9-c9d67023bedd)</span></span>
 - <span data-ttu-id="21411-p356">**免操作輸入：** 使用您的語音直接聽寫以建立簡報。不需輸入。[深入了解](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)</span><span class="sxs-lookup"><span data-stu-id="21411-p356">**Hands free typing:** Use your voice to create presentations by simply dictating. No need to type. [Learn more](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)</span></span>
 - <span data-ttu-id="21411-p357">**Microsoft 表單：** 在投影片上進行測驗或問卷。Office 會收集並儲存存儲您的回應。[深入了解](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span><span class="sxs-lookup"><span data-stu-id="21411-p357">**Microsoft Forms:** Put a quiz or survey on a slide. Office collects and stores the responses for you. [Learn more](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span></span>

### <a name="project-non-security-updates"></a><span data-ttu-id="21411-1959">Project：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1959">Project: Non-security updates</span></span>
 - <span data-ttu-id="21411-1960">修正 Project 第一次在 Project Web 應用程式中儲存專案時可能會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-1960">Fix an issue where Project may crash the first time you save a project to Project Web App.</span></span>


### <a name="visio-feature-updates"></a><span data-ttu-id="21411-1961">Visio：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1961">Visio: Feature updates</span></span>
 - <span data-ttu-id="21411-1962">**入門圖表：** 組織圖、腦力激盪和 SDL 範本有新的入門圖表可讓您快速啟動並執行。</span><span class="sxs-lookup"><span data-stu-id="21411-1962">**Starter diagrams:** The Organization Chart, Brainstorming, and SDL templates have new starter diagrams to get you up and running quickly.</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="21411-1963">Word：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1963">Word: Feature updates</span></span>
 - <span data-ttu-id="21411-p358">**在編輯時與共同作者交談：** 藉由與共同作者聊天，即可更有效率地共同作業而不需要離開 Word。[深入了解](https://support.office.com/article/1ecc6c7f-0b02-4baa-b9d9-c9d67023bedd)</span><span class="sxs-lookup"><span data-stu-id="21411-p358">**Chat with co-authors while you edit:** Collaborate more effectively by chatting with your co-authors without ever leaving Word. [Learn more](https://support.office.com/article/1ecc6c7f-0b02-4baa-b9d9-c9d67023bedd)</span></span>
 - <span data-ttu-id="21411-p359">**免操作輸入：** 使用您的語音直接聽寫以建立文件。不需輸入。[深入了解](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)</span><span class="sxs-lookup"><span data-stu-id="21411-p359">**Hands free typing:** Use your voice to create documents by simply dictating. No need to type. [Learn more](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)</span></span>
 - <span data-ttu-id="21411-p360">**編輯當然是使用筆跡編輯：** 使用畫筆透過單一筆劃來分割或加入文字、新增新的一行，或插入文字。[深入了解](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span><span class="sxs-lookup"><span data-stu-id="21411-p360">**Editing comes naturally with Ink Editor:** With a single stroke, split or join words, add a new line, or insert words using your pen. [Learn more](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span></span>



## <a name="version-1804-may-14"></a><span data-ttu-id="21411-1971">版本 1804：5 月 14 日</span><span class="sxs-lookup"><span data-stu-id="21411-1971">Version 1804: May 14</span></span>
<span data-ttu-id="21411-1972">*版本 1804 (組建 9226.2156)*</span><span class="sxs-lookup"><span data-stu-id="21411-1972">*Version 1804 (Build 9226.2156)*</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="21411-1973">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1973">Office suite: Non-security updates</span></span>
- <span data-ttu-id="21411-1974">修正此問題：開啟應用程式時，使用者可能會看到以安全模式啟動的訊息，然後應用程式無法開啟。</span><span class="sxs-lookup"><span data-stu-id="21411-1974">Fix an issue where, when opening an application, the user might see a message about launching in Safe mode and then the application fails to open.</span></span>



## <a name="version-1804-may-8"></a><span data-ttu-id="21411-1975">版本 1804：5 月 8 日</span><span class="sxs-lookup"><span data-stu-id="21411-1975">Version 1804: May 8</span></span>
<span data-ttu-id="21411-1976">*版本 1804 (組建 9226.2126)*</span><span class="sxs-lookup"><span data-stu-id="21411-1976">*Version 1804 (Build 9226.2126)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="21411-1977">Excel：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1977">Excel: Security updates</span></span>
-   <span data-ttu-id="21411-1978">[CVE-2018-8147](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8147)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1978">[CVE-2018-8147](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8147): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="21411-1979">[CVE-2018-8148](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8148)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1979">[CVE-2018-8148](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8148): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="21411-1980">[CVE-2018-8162](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8162)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1980">[CVE-2018-8162](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8162): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="21411-1981">[CVE-2018-8163](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8163)：Microsoft Excel 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1981">[CVE-2018-8163](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8163): Microsoft Excel Information Disclosure Vulnerability</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="21411-1982">Outlook：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1982">Outlook: Security updates</span></span>
-   <span data-ttu-id="21411-1983">[CVE-2018-8150](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8150)：Microsoft Outlook 安全性功能略過的弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1983">[CVE-2018-8150](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8150): Microsoft Outlook Security Feature Bypass Vulnerability</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="21411-1984">Office 套件：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-1984">Office suite: Security updates</span></span>
-   <span data-ttu-id="21411-1985">[CVE-2018-8157](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8157)：Microsoft Office 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1985">[CVE-2018-8157](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8157): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="21411-1986">[CVE-2018-8158](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8158)：Microsoft Office 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-1986">[CVE-2018-8158](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8158): Microsoft Office Remote Code Execution Vulnerability</span></span>


## <a name="version-1804-april-25"></a><span data-ttu-id="21411-1987">版本 1804：4 月 25 日</span><span class="sxs-lookup"><span data-stu-id="21411-1987">Version 1804: April 25</span></span>
<span data-ttu-id="21411-1988">*版本 1804 (組建 9226.2114)*</span><span class="sxs-lookup"><span data-stu-id="21411-1988">*Version 1804 (Build 9226.2114)*</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="21411-1989">Outlook：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1989">Outlook: Feature updates</span></span>
-   <span data-ttu-id="21411-p361">**聽取您的電子郵件：** Outlook 可以大聲念出您的電子郵件，並將所念到的文字醒目提示。[深入了解](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)</span><span class="sxs-lookup"><span data-stu-id="21411-p361">**Listen to your emails:** Outlook can read your email aloud, highlighting text as it's read. [Learn more](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)</span></span>
-   <span data-ttu-id="21411-p362">**絕不錯過任何提醒：** 將提醒設定為在您正在工作的視窗上彈出。否則，Outlook 會在工作列中閃爍，以引起您的注意。[深入了解](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)</span><span class="sxs-lookup"><span data-stu-id="21411-p362">**Never miss a reminder:** Set reminders to pop up over windows you're working in. Otherwise, Outlook will blink in the taskbar to get your attention.[Learn more](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)</span></span>
-   <span data-ttu-id="21411-p363">**將刪除的郵件標示為已讀取：** 您現在可以將任何已刪除的郵件標示為已讀取。請移至 [檔案] \> [選項] \> [郵件] \> [其他] 來選擇使用。</span><span class="sxs-lookup"><span data-stu-id="21411-p363">**Mark deleted items as read:** You can now set any message that you delete as read. Opt in by going to File \> Options \> Mail \> Other.</span></span>
-   <span data-ttu-id="21411-p364">**加密選項：** Office 365 郵件加密使用者可以加密郵件，並將其傳送給組織內外的任何人。建立郵件時，加密選項會出現在 [選項] \> [權限] 底下。 [深入了解](/microsoft-365/compliance/ome)</span><span class="sxs-lookup"><span data-stu-id="21411-p364">**Encrypt option:** Office 365 Message Encryption users can encrypt a message and send it to anyone, inside or outside their organization. Encrypt option appears under Options \> Permissions when creating a message. [Learn more](/microsoft-365/compliance/ome)</span></span>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="21411-1999">PowerPoint：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-1999">PowerPoint: Feature updates</span></span>
-   <span data-ttu-id="21411-p365">**轉換筆跡：** 擷取草草寫下的筆記和繪圖，並將其轉換為可供閱讀的文字和簡潔的圖形，以建立精美的簡報。 [深入了解](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)</span><span class="sxs-lookup"><span data-stu-id="21411-p365">**Convert your ink:** Take scribbled notes and drawings, and convert them into readable text and crisp shapes to create a polished presentation. [Learn more](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)</span></span>

### <a name="project-feature-updates"></a><span data-ttu-id="21411-2002">Project：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-2002">Project: Feature updates</span></span>
-   <span data-ttu-id="21411-2003">**工作面板篩選：** 篩選重要資源或摘要任務，以簡化您的工作面板。</span><span class="sxs-lookup"><span data-stu-id="21411-2003">**Task board filtering:** Streamline your task boards by filtering on key resources or summary tasks.</span></span>
-   <span data-ttu-id="21411-2004">**從工作面板設定完成百分比：** 針對每個資料行選擇完成百分比，然後透過拖放更新工作完成度。</span><span class="sxs-lookup"><span data-stu-id="21411-2004">**Set percent complete from a task board:** Choose a percent complete for each column, and then update task completion with drag-and-drop.</span></span>
-   <span data-ttu-id="21411-2005">**短期衝刺瀏覽：** 從某個短期衝刺檢視切換為另一個檢視，並快速地在短期衝刺之間移動工作。</span><span class="sxs-lookup"><span data-stu-id="21411-2005">**Sprint navigation:** Switch from one sprint view to another, and quickly move tasks between sprints.</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="21411-2006">Word：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-2006">Word: Feature updates</span></span>
-   <span data-ttu-id="21411-2007">**找出相關的校訂問題並加以修正：**[編輯器] 窗格現在會顯示您的文件中所找到的校訂問題概觀，所以焦點會放在修正與您最相關的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-2007">**Find and fix relevant proofing issues:** Editor pane now displays an overview of proofing issues found in your document, so the focus is on fixing the ones that are most relevant to you.</span></span>


## <a name="version-1803-april-11"></a><span data-ttu-id="21411-2008">版本 1803：4 月 11 日</span><span class="sxs-lookup"><span data-stu-id="21411-2008">Version 1803: April 11</span></span>
<span data-ttu-id="21411-2009">*版本 1803 (組建 9126.2152)*</span><span class="sxs-lookup"><span data-stu-id="21411-2009">*Version 1803 (Build 9126.2152)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="21411-2010">Excel：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-2010">Excel: Security updates</span></span>
-   <span data-ttu-id="21411-2011">[CVE-2018-1029](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-1029)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-2011">[CVE-2018-1029](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-1029): Microsoft Excel Remote Code Execution Vulnerability</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="21411-2012">PowerPoint：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-2012">PowerPoint: Non-security updates</span></span>
-   <span data-ttu-id="21411-2013">修正此問題：多個使用者在相同簡報上共同撰寫會導致投影片母片不正確重複。</span><span class="sxs-lookup"><span data-stu-id="21411-2013">Fix an issue where multiple users co-authoring on the same presentation results in an incorrect duplication of slides masters.</span></span>
-   <span data-ttu-id="21411-2014">修正此問題：將儲存在 OneDrive 中的檔案開啟時，結束受保護的檢視時會導致 PowerPoint 當機。</span><span class="sxs-lookup"><span data-stu-id="21411-2014">Fix an issue where opening a file saved on OneDrive results in PowerPoint crashing when exiting Protected View.</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="21411-2015">商務用 Skype：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-2015">Skype for Business: Non-security updates</span></span>
-   <span data-ttu-id="21411-2016">修正與 TLS 1.2 支援相關的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-2016">Fix an issue related to TLS 1.2 support.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="21411-2017">Word：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-2017">Word: Non-security updates</span></span>
-   <span data-ttu-id="21411-2018">修正造成顯示記憶體不足訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="21411-2018">Fix an issue that causes an insufficient memory message to appear.</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="21411-2019">Office 套件：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-2019">Office suite: Security updates</span></span>
-   <span data-ttu-id="21411-2020">[CVE-2018-0950](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0950)：Microsoft Office 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="21411-2020">[CVE-2018-0950](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0950): Microsoft Office Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="21411-2021">[CVE-2018-1026](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-1026)：Microsoft Office 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-2021">[CVE-2018-1026](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-1026): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="21411-2022">[CVE-2018-1030](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-1030)：Microsoft Office 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-2022">[CVE-2018-1030](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-1030): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="21411-p366">**基於安全原因已封鎖 Flash、Silverlight、Shockwave 控制在 Office 中啟動：** 基於安全原因，Windows 上新組建的 Microsoft Office for Office 365 會封鎖 Flash、Silverlight、Shockwave 控制的啟動。請看 [這裡](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Blocking-Flash-Shockwave-Silverlight-controls-from-activating-in/ba-p/191729)和 [這裡](https://support.office.com/article/flash-silverlight-and-shockwave-controls-blocked-in-office-2016-55738f12-a01d-420e-a533-7cef1ff6aeb1)深入了解。</span><span class="sxs-lookup"><span data-stu-id="21411-p366">**Flash, Silverlight and Shockwave controls blocked from activating in Office for security reasons:** For security reasons new builds of Microsoft Office for Office 365 on Windows block activation of Flash, Silverlight, and Shockwave controls.  Learn more [here](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Blocking-Flash-Shockwave-Silverlight-controls-from-activating-in/ba-p/191729) and [here](https://support.office.com/article/flash-silverlight-and-shockwave-controls-blocked-in-office-2016-55738f12-a01d-420e-a533-7cef1ff6aeb1).</span></span>

## <a name="version-1803-march-27"></a><span data-ttu-id="21411-2025">版本 1803：3 月 27 日</span><span class="sxs-lookup"><span data-stu-id="21411-2025">Version 1803: March 27</span></span>
<span data-ttu-id="21411-2026">*版本 1803 (組建 9126.2116)*</span><span class="sxs-lookup"><span data-stu-id="21411-2026">*Version 1803 (Build 9126.2116)*</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="21411-2027">Excel：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-2027">Excel: Feature updates</span></span>
-   <span data-ttu-id="21411-p367">**Microsoft Translator：** 使用 Microsoft Translator 可將單字、片語或句子翻譯成另一種語言。您可以從功能區中的 [校閱] 索引標籤使用此功能。</span><span class="sxs-lookup"><span data-stu-id="21411-p367">**Microsoft Translator:** Translate words, phrases or sentences to another language with Microsoft Translator. You can do this from the Review tab in the ribbon.</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="21411-2030">Excel：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-2030">Excel: Non-security updates</span></span>
-   <span data-ttu-id="21411-2031">修正此問題：快速列印附加至 Outlook 電子郵件的 Excel 活頁簿可能會列印不出來。</span><span class="sxs-lookup"><span data-stu-id="21411-2031">Fix an issue where Quick Print of an Excel workbook attached to an Outlook email may not print.</span></span>
-   <span data-ttu-id="21411-2032">修正此問題：按一下超連結可能會造成 Excel 當機。</span><span class="sxs-lookup"><span data-stu-id="21411-2032">Fix an issue where clicking on a hyperlink may cause Excel to crash.</span></span>
-   <span data-ttu-id="21411-2033">修正此問題：使用 cube 函式會造成 Excel 當機。</span><span class="sxs-lookup"><span data-stu-id="21411-2033">Fix an issue where using cube functions causes Excel to crash.</span></span>

### <a name="onedrive-for-business-non-security-updates"></a><span data-ttu-id="21411-2034">商務用 OneDrive：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-2034">OneDrive for Business: Non-security updates</span></span>
-   <span data-ttu-id="21411-2035">修正此問題：商務用 OneDrive (Groove.exe) 會在 [工作管理員] 中耗用相當於一個 CPU 核心的 CPU (例如，4 核心 CPU 的 25%) 來延長一段時間。</span><span class="sxs-lookup"><span data-stu-id="21411-2035">Fix an issue where OneDrive for Business (Groove.exe) consumes one CPU core’s worth of CPU (for example, 25% on a 4 core CPU) in Task Manager for extended periods of time.</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="21411-2036">Outlook：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-2036">Outlook: Feature updates</span></span>
-   <span data-ttu-id="21411-2037">**密件副本 (Bcc) 警告：** 如果您對先前使用密件副本的郵件選擇 [全部回覆]，將會顯示警告訊息。</span><span class="sxs-lookup"><span data-stu-id="21411-2037">**Blind carbon copy (Bcc) warning:** A warning appears if you choose Reply All to a message that you were Bcc’ed on.</span></span>
-   <span data-ttu-id="21411-p368">**更聰明的 [收件者：] 行：** 當您按一下 [收件者：] 來撰寫郵件時，我們會建議您可能要選擇的收件者。此外，還可以看到收件者相片，讓您知道要傳送的對象是正確的。</span><span class="sxs-lookup"><span data-stu-id="21411-p368">**A smarter To: line:** When you click the To: line to address a message, we suggest recipients you're likely to choose. Plus, you can see their picture, so you know yo’re sending to the right person.</span></span> 

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="21411-2040">PowerPoint：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-2040">PowerPoint: Feature updates</span></span>
-   <span data-ttu-id="21411-p369">**Microsoft Translator：** 使用 Microsoft Translator 可將單字、片語或句子翻譯成另一種語言。您可以從功能區中的 [校閱] 索引標籤使用此功能。</span><span class="sxs-lookup"><span data-stu-id="21411-p369">**Microsoft Translator:** Translate words, phrases or sentences to another language with Microsoft Translator. You can do this from the Review tab in the ribbon.</span></span>
-   <span data-ttu-id="21411-p370">**改善了對高解析度顯示器的支援**：現在，如果您使用多部監視器或筆記型電腦基座，Office 應用程式在每個顯示器上都會順暢清晰地呈現，即使顯示器使用不同的縮放設定亦然。 [深入了解](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)</span><span class="sxs-lookup"><span data-stu-id="21411-p370">**Improved support for high definition displays**: If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings. [Learn more](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="21411-2045">商務用 Skype：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-2045">Skype for Business: Non-security updates</span></span>
-   <span data-ttu-id="21411-2046">修正此問題：在會議中以選取 [Skype 通話] 的方式新增使用者會產生錯誤。</span><span class="sxs-lookup"><span data-stu-id="21411-2046">Fix an issue where adding users by selecting 'Skype Call' in a meeting causes an error.</span></span>
-   <span data-ttu-id="21411-2047">如果已將 Skype 會議室新增為位置，且會議已包含小組會議座標，請移除要求使用者將 Skype 座標新增至會議的提示。</span><span class="sxs-lookup"><span data-stu-id="21411-2047">Remove prompt asking user to add Skype coordinates to a meeting, if a Skype Room is added as the location and the meeting already contains Teams meeting coordinates.</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="21411-2048">Visio：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-2048">Visio: Feature updates</span></span>
-   <span data-ttu-id="21411-p371">**改善了對高解析度顯示器的支援**：現在，如果您使用多部監視器或筆記型電腦基座，Office 應用程式在每個顯示器上都會順暢清晰地呈現，即使顯示器使用不同的縮放設定亦然。 [深入了解](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)</span><span class="sxs-lookup"><span data-stu-id="21411-p371">**Improved support for high definition displays**: If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings. [Learn more](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="21411-2051">Word：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-2051">Word: Feature updates</span></span>
-   <span data-ttu-id="21411-p372">**改善了對高解析度顯示器的支援**：現在，如果您使用多部監視器或筆記型電腦基座，Office 應用程式在每個顯示器上都會順暢清晰地呈現，即使顯示器使用不同的縮放設定亦然。 [深入了解](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)</span><span class="sxs-lookup"><span data-stu-id="21411-p372">**Improved support for high definition displays**: If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings. [Learn more](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)</span></span>


## <a name="version-1802-march-13"></a><span data-ttu-id="21411-2054">版本 1802：3 月 13 日</span><span class="sxs-lookup"><span data-stu-id="21411-2054">Version 1802: March 13</span></span>
<span data-ttu-id="21411-2055">*版本 1802 (組建 9029.2253)*</span><span class="sxs-lookup"><span data-stu-id="21411-2055">*Version 1802 (Build 9029.2253)*</span></span>

### <a name="access-security-updates"></a><span data-ttu-id="21411-2056">Access：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-2056">Access: Security updates</span></span>
-   <span data-ttu-id="21411-2057">[CVE-2018-0903](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0903)：Microsoft Access 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-2057">[CVE-2018-0903](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0903): Microsoft Access Remote Code Execution Vulnerability</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="21411-2058">Excel：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-2058">Excel: Security updates</span></span>
-   <span data-ttu-id="21411-2059">[CVE-2018-0907](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0907)：Microsoft Office Excel 安全性功能略過</span><span class="sxs-lookup"><span data-stu-id="21411-2059">[CVE-2018-0907](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0907): Microsoft Office Excel Security Feature Bypass</span></span>

### <a name="word-security-updates"></a><span data-ttu-id="21411-2060">Word：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-2060">Word: Security updates</span></span>
-   <span data-ttu-id="21411-2061">[CVE-2018-0919](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0919)：Microsoft Office 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="21411-2061">[CVE-2018-0919](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0919): Microsoft Office Information Disclosure Vulnerability</span></span>


## <a name="version-1802-february-26"></a><span data-ttu-id="21411-2062">版本 1802：2 月 26 日</span><span class="sxs-lookup"><span data-stu-id="21411-2062">Version 1802: February 26</span></span>
<span data-ttu-id="21411-2063">*版本 1802 (組建 9029.2167)*</span><span class="sxs-lookup"><span data-stu-id="21411-2063">*Version 1802 (Build 9029.2167)*</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="21411-2064">Outlook：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-2064">Outlook: Feature updates</span></span>
-   <span data-ttu-id="21411-2065">**了解要參與會議的人員：** 即使您不是召集人，也可以看到其他人對於會議邀請的回應。</span><span class="sxs-lookup"><span data-stu-id="21411-2065">**Know who you'll be meeting with:** You can see other people's responses to a meeting request, even if you aren't the organizer.</span></span>
-   <span data-ttu-id="21411-2066">**輕鬆地排序您的電子郵件：** 由於您的意見反應，我們已為不使用 [焦點收件匣] 的使用者，重新加入了郵件清單上方的排序功能和 [未讀取] 篩選器。</span><span class="sxs-lookup"><span data-stu-id="21411-2066">**Sort your email with ease:** Thanks to your feedback, we've brought back sorting above the message list and the Unread filter for people who don't use Focused Inbox.</span></span>

### <a name="project-non-security-updates"></a><span data-ttu-id="21411-2067">Project：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-2067">Project: Non-security updates</span></span>
-   <span data-ttu-id="21411-2068">修正此問題：在工作階段中設定多個基準，會讓 MOD\_DATE 值都設為相同。</span><span class="sxs-lookup"><span data-stu-id="21411-2068">Fix an issue where setting more than one baseline in a session sets the MOD\_DATE value as the same.</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="21411-2069">商務用 Skype：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-2069">Skype for Business: Non-security updates</span></span>
-   <span data-ttu-id="21411-2070">修正此問題：即使 UseLocationForE911Only 設定為 true，也會填入位置。</span><span class="sxs-lookup"><span data-stu-id="21411-2070">Fix an issue where location is populated even when UseLocationForE911Only is set to true.</span></span>
-   <span data-ttu-id="21411-2071">修正此問題：使用名冊中的「使用會議中心呼叫」選項來邀請使用者時，商務用 Skype 會當機。</span><span class="sxs-lookup"><span data-stu-id="21411-2071">Fix an issue where Skype for Business hangs when using the "call using conference center" option to invite users from the roster.</span></span>
-   <span data-ttu-id="21411-2072">修正此問題：建立商務用 Skype 會議時，在終端機伺服器上運行的Outlook 會凍結。</span><span class="sxs-lookup"><span data-stu-id="21411-2072">Fix an issue where Outlook running on terminal server freezes while creating a Skype for Business meeting.</span></span>
-   <span data-ttu-id="21411-2073">將 EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket 的預設值變更為 TRUE。</span><span class="sxs-lookup"><span data-stu-id="21411-2073">Change the default value of EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket to TRUE.</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="21411-2074">Visio：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-2074">Visio: Feature updates</span></span>
-   <span data-ttu-id="21411-p373">**內建資料庫模型圖表：** 使用新的資料庫模型圖表範本，將您的資料庫精確地建模為 Visio 圖表。不需要增益集。</span><span class="sxs-lookup"><span data-stu-id="21411-p373">**Built-in database model diagrams:** Use the new Database Model Diagram template to accurately model your database as a Visio diagram. No add-in required.</span></span>
-   <span data-ttu-id="21411-2077">**更多商用圖表的樣板：** 使用新式圖形，以文氏圖表來比較和對比資料；或繪製循環、矩陣或金字塔圖表來表達您的想法。</span><span class="sxs-lookup"><span data-stu-id="21411-2077">**More stencils for business diagrams:** Using modern shapes, compare and contrast data with a Venn diagram, or draw Cycle, Matrix, or Pyramid diagrams to help tell your story.</span></span>
-   <span data-ttu-id="21411-2078">**讓您的圖表和來源能保持同步：** 當您在 Visio 中編輯 [資料視覺化工具] 圖表時，可以選擇用最新的圖表內容來更新連結的 Excel 來源資料。</span><span class="sxs-lookup"><span data-stu-id="21411-2078">**Keep your diagram and source in sync:** When you edit a Data Visualizer diagram in Visio, you have the option to update the linked Excel source data with the latest diagram content.</span></span>


## <a name="version-1801-february-13"></a><span data-ttu-id="21411-2079">版本 1801：2 月 13 日</span><span class="sxs-lookup"><span data-stu-id="21411-2079">Version 1801: February 13</span></span>
<span data-ttu-id="21411-2080">*版本 1801 (組建 9001.2171)*</span><span class="sxs-lookup"><span data-stu-id="21411-2080">*Version 1801 (Build 9001.2171)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="21411-2081">Excel：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-2081">Excel: Security updates</span></span>
-   <span data-ttu-id="21411-2082">[CVE-2018-0841](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0841)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-2082">[CVE-2018-0841](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0841): Microsoft Excel Remote Code Execution Vulnerability</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="21411-2083">Outlook：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-2083">Outlook: Security updates</span></span>
-   <span data-ttu-id="21411-2084">[CVE-2018-0850](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0850)：Microsoft Outlook 提高權限弱點</span><span class="sxs-lookup"><span data-stu-id="21411-2084">[CVE-2018-0850](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0850): Microsoft Outlook Elevation of Privilege Vulnerability</span></span>
-   <span data-ttu-id="21411-2085">[CVE-2018-0852](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0852)：Microsoft Outlook 記憶體損毀弱點</span><span class="sxs-lookup"><span data-stu-id="21411-2085">[CVE-2018-0852](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0852): Microsoft Outlook Memory Corruption Vulnerability</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="21411-2086">Office 套件：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-2086">Office suite: Security updates</span></span>
-   <span data-ttu-id="21411-2087">[CVE-2018-0851](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0851)：Microsoft Office 記憶體損毀弱點</span><span class="sxs-lookup"><span data-stu-id="21411-2087">[CVE-2018-0851](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0851): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="21411-2088">[CVE-2018-0853](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0853)：Microsoft Office 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="21411-2088">[CVE-2018-0853](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0853): Microsoft Office Information Disclosure Vulnerability</span></span>


## <a name="version-1801-february-7"></a><span data-ttu-id="21411-2089">版本 1801：2 月 7 日</span><span class="sxs-lookup"><span data-stu-id="21411-2089">Version 1801: February 7</span></span>
<span data-ttu-id="21411-2090">*版本 1801 (組建 9001.2144)*</span><span class="sxs-lookup"><span data-stu-id="21411-2090">*Version 1801 (Build 9001.2144)*</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="21411-2091">Excel：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-2091">Excel: Non-security updates</span></span>
-   <span data-ttu-id="21411-2092">修正下列問題：如果您的編輯語言是日文、中文或韓文，則當您嘗試在 [首頁] 索引標籤上選取新字型時，或當編輯時，Excel 可能會凍結。</span><span class="sxs-lookup"><span data-stu-id="21411-2092">Fix an issue where, if your editing language is Japanese, Chinese, or Korean, Excel may freeze when you try to choose a new font on the Home tab or when you edit.</span></span>


## <a name="version-1801-february-1"></a><span data-ttu-id="21411-2093">版本 1801：2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="21411-2093">Version 1801: February 1</span></span>
<span data-ttu-id="21411-2094">*版本 1801 (組建 9001.2138)*</span><span class="sxs-lookup"><span data-stu-id="21411-2094">*Version 1801 (Build 9001.2138)*</span></span>

### <a name="project-non-security-updates"></a><span data-ttu-id="21411-2095">Project：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-2095">Project: Non-security updates</span></span>
-   <span data-ttu-id="21411-2096">修正此問題：將實際工時從 [儲存為共用] 工作階段中移除之後，[實際工時] 仍然顯示在報表中。</span><span class="sxs-lookup"><span data-stu-id="21411-2096">Fix an issue where Actual Work is still shown in the reporting tables after being removed in a Save for Sharing session.</span></span>
-   <span data-ttu-id="21411-2097">修正此問題：在德文版中進行排程時，要使用 [週] 日期格式時會傳回錯誤。</span><span class="sxs-lookup"><span data-stu-id="21411-2097">Fix an issue in the German language version where using a Weeks date format returns an error when scheduling.</span></span>
-   <span data-ttu-id="21411-2098">修正此問題：在編輯 [排程網頁組件] 的完成日期時，工作保持為每天 8 小時，而不是隨著時間分配。</span><span class="sxs-lookup"><span data-stu-id="21411-2098">Fix an issue where, when editing finish dates in Schedule Web Part, tasks stay at 8 hours per day instead of being spread over time.</span></span>
-   <span data-ttu-id="21411-2099">修正此問題：在非預期的位置繪製「進度點形狀」。</span><span class="sxs-lookup"><span data-stu-id="21411-2099">Fix an issue where "Progress point shape" is drawn at an unexpected location.</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="21411-2100">商務用 Skype：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-2100">Skype for Business: Non-security updates</span></span>
-   <span data-ttu-id="21411-2101">修正此問題：當會議處於全螢幕模式時，[其他選項] 和 [邀請其他人] 按鈕會隱藏。</span><span class="sxs-lookup"><span data-stu-id="21411-2101">Fix an issue where "More Options" and "Invite More People" buttons are hidden when a meeting is in full-screen mode.</span></span>
-   <span data-ttu-id="21411-2102">修正此問題：當您想要加入會議時，P2P 音訊撥號視窗或電話會議視窗會變成透明。</span><span class="sxs-lookup"><span data-stu-id="21411-2102">Fix an issue where the P2P audio call window or conference call window becomes transparent when you attempt to join.</span></span>
-   <span data-ttu-id="21411-2103">修正此問題：即將開始的 Skype 會議未顯示在 [會議] 索引標籤。</span><span class="sxs-lookup"><span data-stu-id="21411-2103">Fix an issue where upcoming Skype meetings do not show up in the meetings tab.</span></span>
-   <span data-ttu-id="21411-2104">修正此問題：當商務用 Skype 配置為無音訊加入會議，新增音訊至會議時不會將音訊新增至現有的會議，反而是向使用者本身啟動新的 P2P 撥號。</span><span class="sxs-lookup"><span data-stu-id="21411-2104">Fix an issue where, when Skype for Business is configured to join meetings without audio, adding audio to a meeting initiates a new P2P call to the user itself rather than adding audio to the existing meeting.</span></span>
-   <span data-ttu-id="21411-2105">修正此問題：當使用者按下 Outlook 會議邀請的 [加入 Skype 會議] 連結時，會收到錯誤訊息 [找不到此 Skype 會議]。</span><span class="sxs-lookup"><span data-stu-id="21411-2105">Fix an issue where user receives the error message "We couldn't find this Skype meeting" when clicking 'Join Skype Meeting' link in a meeting request from Outlook.</span></span>


## <a name="version-1712-january-30"></a><span data-ttu-id="21411-2106">版本 1712：1 月 30 日</span><span class="sxs-lookup"><span data-stu-id="21411-2106">Version 1712: January 30</span></span>
<span data-ttu-id="21411-2107">*版本 1712 (組建 8827.2179)*</span><span class="sxs-lookup"><span data-stu-id="21411-2107">*Version 1712 (Build 8827.2179)*</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="21411-2108">Excel：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-2108">Excel: Non-security updates</span></span>
-   <span data-ttu-id="21411-2109">修正此問題：當 Excel 最小化時，開啟活頁簿時捲軸會遺失。</span><span class="sxs-lookup"><span data-stu-id="21411-2109">Fix and issue where the scroll bars are missing when a workbook is opened when Excel is minimized.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="21411-2110">Outlook：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-2110">Outlook: Non-security updates</span></span>
-   <span data-ttu-id="21411-2111">修正此問題：當搜尋範圍限定為 [所有信箱] 時，搜索會失敗並顯示 [找不到相符項目]。</span><span class="sxs-lookup"><span data-stu-id="21411-2111">Fix an issue where search fails with “No matches found” when search is scoped to All Mailboxes.</span></span>


## <a name="version-1712-january-17"></a><span data-ttu-id="21411-2112">版本 1712：1 月 17 日</span><span class="sxs-lookup"><span data-stu-id="21411-2112">Version 1712: January 17</span></span>
<span data-ttu-id="21411-2113">*版本 1712 (組建 8827.2148)*</span><span class="sxs-lookup"><span data-stu-id="21411-2113">*Version 1712 (Build 8827.2148)*</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="21411-2114">Excel：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-2114">Excel: Feature updates</span></span>
-   <span data-ttu-id="21411-2115">**將 SVG 圖示轉換成圖形：** 將所有 SVG 圖片和圖示轉換成 Office 圖形，讓您可以變更其色彩、大小或材質。</span><span class="sxs-lookup"><span data-stu-id="21411-2115">**Convert SVG icons to shapes:** Transform all SVG pictures and icons into Office shapes so you can change their color, size, or texture.</span></span>
-   <span data-ttu-id="21411-2116">**取消選取儲存格：** 在工作表中進行選取，並取消選取不小心按到的儲存格而不必重新開始。</span><span class="sxs-lookup"><span data-stu-id="21411-2116">**Deselect cells:** Make selections in your worksheet and deselect cells that you accidentally clicked without having to start over.</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="21411-2117">Excel：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-2117">Excel: Non-security updates</span></span>
-   <span data-ttu-id="21411-2118">修正此問題：在 [檔案總管] 中的檔案名稱上按兩下以開啟多個活頁簿時，活頁簿參照會失敗。</span><span class="sxs-lookup"><span data-stu-id="21411-2118">Fix an issue where workbook references fail when opening multiple workbooks by double-clicking on the file names in File Explorer.</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="21411-2119">Outlook：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-2119">Outlook: Feature updates</span></span>
-   <span data-ttu-id="21411-2120">**將 SVG 圖示轉換成圖形：** 將所有 SVG 圖片和圖示轉換成 Office 圖形，讓您可以變更其色彩、大小或材質。</span><span class="sxs-lookup"><span data-stu-id="21411-2120">**Convert SVG icons to shapes:** Transform all SVG pictures and icons into Office shapes so you can change their color, size, or texture.</span></span>
-   <span data-ttu-id="21411-2121">**Office 365 群組的改善︰** 您可以在群組訊息上按兩下，開啟其個別視窗，這讓您更加容易閱讀和回覆群組對話。</span><span class="sxs-lookup"><span data-stu-id="21411-2121">**Improvements to Office 365 groups:** It’s easier than ever to read and reply to group conversations because you can double-click on a group message to open it in its own window.</span></span>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="21411-2122">PowerPoint：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-2122">PowerPoint: Feature updates</span></span>
-   <span data-ttu-id="21411-2123">**3D 動畫：** 透過輕輕搖晃或跳躍及旋轉等動畫，讓 3D 模型栩栩如生。</span><span class="sxs-lookup"><span data-stu-id="21411-2123">**3D animations:** Bring your 3D models to life with animations such as swinging gently or jumping and turning.</span></span>
-   <span data-ttu-id="21411-2124">**將 SVG 圖示轉換成圖形：** 將所有 SVG 圖片和圖示轉換成 Office 圖形，讓您可以變更其色彩、大小或材質。</span><span class="sxs-lookup"><span data-stu-id="21411-2124">**Convert SVG icons to shapes:** Transform all SVG pictures and icons into Office shapes so you can change their color, size, or texture.</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="21411-2125">商務用 Skype：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-2125">Skype for Business: Non-security updates</span></span>
-   <span data-ttu-id="21411-2126">在快顯通知 UI 中為撥入的 PSTN 通話新增來電轉接按鈕。</span><span class="sxs-lookup"><span data-stu-id="21411-2126">Add call transfer button in the toast UI for incoming PSTN calls.</span></span>
-   <span data-ttu-id="21411-2127">當 ChatDefaultClient 和 CallDefaultClient 設定至 Teams 時，通知使用者來電與交談正在傳送至 Teams。</span><span class="sxs-lookup"><span data-stu-id="21411-2127">Notify users that calls and chat are being sent to Teams when ChatDefaultClient and CallDefaultClient are set to Teams.</span></span>
-   <span data-ttu-id="21411-2128">當使用者不在會議中並停用商務用 Skype 時，使用者狀態會顯示為 [離線]，且會議加入體驗會設為 [原生有限用戶端]。</span><span class="sxs-lookup"><span data-stu-id="21411-2128">Show user’s presence as Offline when user is not in a meeting and disabled from Skype for Business and meeting join experience is set to Native Limited Client.</span></span>
-   <span data-ttu-id="21411-2129">商務用 Skype 最小化至通知區域時，停用 [開啟] 和 [結束] 以外的所有選項。</span><span class="sxs-lookup"><span data-stu-id="21411-2129">Disable all options except Open and Exit when Skype for Business is minimized to the notification area.</span></span> 
-   <span data-ttu-id="21411-2130">與 Aries 電話配對且啟用 RedirectClient 時，隱藏新來電和對話。</span><span class="sxs-lookup"><span data-stu-id="21411-2130">Suppress new calls and conversations when paired with Aries phones and RedirectClient is enabled.</span></span>
-   <span data-ttu-id="21411-2131">修正此問題：日期格式非美國格式 (mm/dd/yy) 時，在 PChat 中依日期搜尋訊息會失敗。</span><span class="sxs-lookup"><span data-stu-id="21411-2131">Fix an issue where searching messages in PChat by date fails when the date format is other than US format (mm/dd/yy).</span></span>
-   <span data-ttu-id="21411-2132">修正此問題：當 EnableExternalP2PFileTransfer 原則設為 false 時，使用者仍然可以在會議中附加檔案。</span><span class="sxs-lookup"><span data-stu-id="21411-2132">Fix an issue where, when EnableExternalP2PFileTransfer policy is set to false, users are still able to attach files in meetings.</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="21411-2133">Visio：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-2133">Visio: Feature updates</span></span>
-   <span data-ttu-id="21411-p374">**使用 Excel 範本匯出至 Visio 圖表：** 搶先使用 Visio 流程表。在其中一個程序圖 Excel 範本中輸入資料，並匯出至 Visio 以自動建立圖表。需要 Visio Pro for Office 365。</span><span class="sxs-lookup"><span data-stu-id="21411-p374">**Use Excel templates to export to a Visio diagram:** Get a jump on your Visio flowcharts. Enter your data in one of the Process Map Excel templates and export to Visio to create the diagram automatically. Requires Visio Pro for Office 365.</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="21411-2137">Word：功能更新</span><span class="sxs-lookup"><span data-stu-id="21411-2137">Word: Feature updates</span></span>
-   <span data-ttu-id="21411-2138">**將 SVG 圖示轉換成圖形：** 將所有 SVG 圖片和圖示轉換成 Office 圖形，讓您可以變更其色彩、大小或材質。</span><span class="sxs-lookup"><span data-stu-id="21411-2138">**Convert SVG icons to shapes:** Transform all SVG pictures and icons into Office shapes so you can change their color, size, or texture.</span></span>


## <a name="version-1711-january-9"></a><span data-ttu-id="21411-2139">版本 1711：1 月 9 日</span><span class="sxs-lookup"><span data-stu-id="21411-2139">Version 1711: January 9</span></span>
<span data-ttu-id="21411-2140">*版本 1711 (組建 8730.2175)*</span><span class="sxs-lookup"><span data-stu-id="21411-2140">*Version 1711 (Build 8730.2175)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="21411-2141">Excel：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-2141">Excel: Security updates</span></span>
-   <span data-ttu-id="21411-2142">[CVE-2018-0796](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0796)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-2142">[CVE-2018-0796](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0796): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="21411-2143">[Advisory 170021](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/ADV170021)：Microsoft Office 深度防禦更新</span><span class="sxs-lookup"><span data-stu-id="21411-2143">[Advisory 170021](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/ADV170021): Microsoft Office Defense in Depth Update</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="21411-2144">Outlook：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-2144">Outlook: Security updates</span></span>
-   <span data-ttu-id="21411-2145">[CVE-2018-0791](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0791)：Microsoft Outlook 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-2145">[CVE-2018-0791](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0791): Microsoft Outlook Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="21411-2146">[CVE-2018-0793](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0793)：Microsoft Outlook 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-2146">[CVE-2018-0793](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook Remote Code Execution Vulnerability</span></span>

### <a name="word-security-updates"></a><span data-ttu-id="21411-2147">Word：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-2147">Word: Security updates</span></span>
-   <span data-ttu-id="21411-2148">[CVE-2018-0792](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0792)：Microsoft Word 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-2148">[CVE-2018-0792](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0792): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="21411-2149">[CVE-2018-0793](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0793)：Microsoft Outlook 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-2149">[CVE-2018-0793](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="21411-2150">[CVE-2018-0794](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0794)：Microsoft Word 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-2150">[CVE-2018-0794](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0794): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="21411-2151">[CVE-2018-0798](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0798)：Microsoft Office 記憶體損毀弱點</span><span class="sxs-lookup"><span data-stu-id="21411-2151">[CVE-2018-0798](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0798): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="21411-2152">[CVE-2018-0801](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0801)：Microsoft Office 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-2152">[CVE-2018-0801](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0801): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="21411-2153">[CVE-2018-0802](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0802)：Microsoft Office 記憶體損毀弱點</span><span class="sxs-lookup"><span data-stu-id="21411-2153">[CVE-2018-0802](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0802): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="21411-2154">[CVE-2018-0804](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0804)：Microsoft Word 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-2154">[CVE-2018-0804](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0804): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="21411-2155">[CVE-2018-0805](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0805)：Microsoft Word 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-2155">[CVE-2018-0805](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0805): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="21411-2156">[CVE-2018-0806](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0806)：Microsoft Word 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-2156">[CVE-2018-0806](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0806): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="21411-2157">[CVE-2018-0807](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0807)：Microsoft Word 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-2157">[CVE-2018-0807](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0807): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="21411-2158">[CVE-2018-0812](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0812)：Microsoft Word 記憶體損毀弱點</span><span class="sxs-lookup"><span data-stu-id="21411-2158">[CVE-2018-0812](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0812): Microsoft Word Memory Corruption Vulnerability</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="21411-2159">Office 套件：安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-2159">Office suite: Security updates</span></span>
-   <span data-ttu-id="21411-2160">[CVE-2018-0795](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0795)：Microsoft Office 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="21411-2160">[CVE-2018-0795](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0795): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="21411-2161">[Advisory 180003](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/ADV180003)：Microsoft Office 深度防禦更新</span><span class="sxs-lookup"><span data-stu-id="21411-2161">[Advisory 180003](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/ADV180003): Microsoft Office Defense in Depth Update</span></span>


## <a name="version-1711-january-2"></a><span data-ttu-id="21411-2162">版本 1711：1 月 2 日</span><span class="sxs-lookup"><span data-stu-id="21411-2162">Version 1711: January 2</span></span>
<span data-ttu-id="21411-2163">*版本 1711 (組建 8730.2165)*</span><span class="sxs-lookup"><span data-stu-id="21411-2163">*Version 1711 (Build 8730.2165)*</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="21411-2164">Excel：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-2164">Excel: Non-security updates</span></span>
-   <span data-ttu-id="21411-2165">修正此問題：以程式設計方式建立樞紐分析表，接著以程式設計方式重新整理，會造成 Excel 當機。</span><span class="sxs-lookup"><span data-stu-id="21411-2165">Fix an issue where the programmatic creation of a PivotTable followed by a programmatic refresh causes Excel to crash.</span></span>
-   <span data-ttu-id="21411-2166">修正此問題：以程式設計方式呼叫 Workbook.Open() 可能會造成 Excel 當機。</span><span class="sxs-lookup"><span data-stu-id="21411-2166">Fix an issue where programmatically calling Workbook.Open() may cause Excel to crash.</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="21411-2167">PowerPoint：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-2167">PowerPoint: Non-security updates</span></span>
-   <span data-ttu-id="21411-2168">修正此問題：移除文件屬性和個人資訊會造成儲存至 SharePoint 失敗。</span><span class="sxs-lookup"><span data-stu-id="21411-2168">Fix an issue where removing document properties and personal information causes saving to SharePoint to fail.</span></span>

### <a name="project-non-security-updates"></a><span data-ttu-id="21411-2169">Project：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="21411-2169">Project: Non-security updates</span></span>
-   <span data-ttu-id="21411-2170">修正此問題：VBA 程式碼從專案中遺失。</span><span class="sxs-lookup"><span data-stu-id="21411-2170">Fix an issue where VBA code gets lost from projects.</span></span>



> [!NOTE]
> <span data-ttu-id="21411-2171">如果您需要關於使用 Office 的問題協助，建議您將問題張貼在 [Microsoft Answers 論壇](https://answers.microsoft.com/)或[技術社群](https://techcommunity.microsoft.com/)，或連絡[支援](https://support.microsoft.com/contactus)。</span><span class="sxs-lookup"><span data-stu-id="21411-2171">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>
