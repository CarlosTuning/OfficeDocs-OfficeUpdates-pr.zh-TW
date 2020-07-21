---
title: Beta 版通道的版本資訊
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為「測試人員 - 快」對象提供關鍵新功能、修正或已知問題的最新清單
ms.openlocfilehash: 12cfa4a285201c2d3839abfd93c5085fa5ea1d13
ms.sourcegitcommit: a58e0b1ff6d1170fabfd95ba7f25e2eb1e4fad0a
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/17/2020
ms.locfileid: "45166711"
---
# <a name="release-notes-for-beta-channel"></a><span data-ttu-id="81f3d-103">Beta 版通道的版本資訊</span><span class="sxs-lookup"><span data-stu-id="81f3d-103">Release Notes for Beta Channel</span></span>

<span data-ttu-id="81f3d-104">本文包含 Word、Excel、PowerPoint、Outlook、Access 和適用於 Windows 電腦的 Project 的 Beta 版通道組建版本資訊。</span><span class="sxs-lookup"><span data-stu-id="81f3d-104">This article contains release notes for Beta Channel builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="81f3d-105">每週，我們都會強調有趣的新功能、重要修正，以及我們想讓您知道的重大問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-105">Every week, we'll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="81f3d-106">請注意，我們通常每隔一段時間會推出 Beta 版通道新功能 (某些時候還有修正)。</span><span class="sxs-lookup"><span data-stu-id="81f3d-106">Note that we often roll out features (and sometimes even fixes) to Beta Channel over a period of time.</span></span> <span data-ttu-id="81f3d-107">這樣可讓我們確保功能都運作順利，然後才推出給更廣泛的對象。</span><span class="sxs-lookup"><span data-stu-id="81f3d-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="81f3d-108">因此，如果您沒有在以下描述的內容中看到某些項目，請不用擔心，您最終還是會看到它。</span><span class="sxs-lookup"><span data-stu-id="81f3d-108">So, if you don't see something described below, don't worry you'll get it eventually.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="81f3d-109">我們會變更 Microsoft 365 應用程式的更新通道，包括新增新的更新通道 (每月企業通道)，並變更現有的更新通道名稱。</span><span class="sxs-lookup"><span data-stu-id="81f3d-109">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="81f3d-110">如需深入了解，[請閱讀本文](https://go.microsoft.com/fwlink/p/?linkid=2127441)。</span><span class="sxs-lookup"><span data-stu-id="81f3d-110">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
> - <span data-ttu-id="81f3d-111">版本資訊會每週發佈，可能是多個組建的編譯。</span><span class="sxs-lookup"><span data-stu-id="81f3d-111">Release notes are posted weekly and may be a compilation of multiple builds.</span></span>
> - <span data-ttu-id="81f3d-112">版本資訊發佈日期可能與實際組建發行日期不相符。</span><span class="sxs-lookup"><span data-stu-id="81f3d-112">The release notes publication date may not match the actual build release date.</span></span>

[//]: # (DO NOT REMOVE)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

## <a name="version-2008-july-17"></a><span data-ttu-id="81f3d-115">版本2008：7月17日</span><span class="sxs-lookup"><span data-stu-id="81f3d-115">Version 2008: July 17</span></span>
<span data-ttu-id="81f3d-116">*版本2008（組建13115.20000）*</span><span class="sxs-lookup"><span data-stu-id="81f3d-116">*Version 2008 (Build 13115.20000)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="81f3d-118">解決的問題</span><span class="sxs-lookup"><span data-stu-id="81f3d-118">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="81f3d-119">Excel</span><span class="sxs-lookup"><span data-stu-id="81f3d-119">Excel</span></span>

- <span data-ttu-id="81f3d-120">我們修正了只要儲存並重新開啟含有隱藏前置字元的樞紐分析表，即會顯示前置字元的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-120">We fixed an issue where any time a pivot chart with hidden leader lines was saved and reopened, the leader lines would become visible.</span></span>

- <span data-ttu-id="81f3d-121">我們修正了當透過 VBA 啟用活頁簿的 [ForceFullCalculation] 時，圖表不一會更新的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-121">We fixed an issue where charts were not always updated as expected when 'ForceFullCalculation' was enabled via VBA for the workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="81f3d-122">Outlook</span><span class="sxs-lookup"><span data-stu-id="81f3d-122">Outlook</span></span>

- <span data-ttu-id="81f3d-123">我們修正了從相同的電子郵件域在 Outlook 中建立多個設定檔會產生的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-123">We fixed an issue around creating multiple profiles in Outlook from the same email domain.</span></span>
- <span data-ttu-id="81f3d-124">解決會導致在 S/MIME 加密郵件的頁首中無法顯示鎖定圖示的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-124">Addresses an issue that caused the lock icon to fail to display in the header of S/MIME encrypted messages.</span></span>
- <span data-ttu-id="81f3d-125">解決當傳送未加密郵件時，會導致附件從 S/MIME 郵件中剝離出來的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-125">Addresses an issue that caused attachments to get stripped from S/MIME messages when sent unencrypted.</span></span>
- <span data-ttu-id="81f3d-126">解決當純文字 S/MIME 郵件在傳送時發生亂碼的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-126">Addresses an issue that caused plain text S/MIME messages to become garbled when sending.</span></span>
- <span data-ttu-id="81f3d-127">解決當傳送未加密的 S/MIME 電子郵件時，會導致附件損毀的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-127">Addresses an issue that caused attachments to become corrupted when sending an S/MIME email unencrypted.</span></span>
- <span data-ttu-id="81f3d-128">解決選取安全性對話方塊上的 [儲存] 選項時，會導致使用者無法將來自其租用戶外部的 OneDrive 附件儲存至其本機電腦的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-128">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the 'Save' option on the security dialog.</span></span>
- <span data-ttu-id="81f3d-129">解決當寄件者授與 [另存為] 許可權時，會導致收件者無法儲存許可權保護郵件的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-129">Addresses an issue that caused recipients to be unable to save rights protected messages even when the save as permission was granted by the sender.</span></span>
- <span data-ttu-id="81f3d-130">解決某些 [進階搜尋] 選項標籤在某些語言中會被截斷的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-130">Addresses an issue that caused the labels for some Advanced Search options to be truncated in some languages.</span></span>

### <a name="project"></a><span data-ttu-id="81f3d-131">Project</span><span class="sxs-lookup"><span data-stu-id="81f3d-131">Project</span></span>

- <span data-ttu-id="81f3d-132">我們修正了 [工作委員會] 畫面中列出的工作未與 [指派資源] 對話方塊中的任務同步處理的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-132">We fixed an issue where tasks listed in the Task Board view were not in sync with those in the Assign Resources dialog.</span></span>
- <span data-ttu-id="81f3d-133">我們修正了當您複製並貼上具有多個相關性的工作，並非所有相關性都能正確複製的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-133">We fixed an issue where if you copied and pasted a task that had multiple dependencies, not all dependencies were copied correctly.</span></span>

### <a name="word"></a><span data-ttu-id="81f3d-134">Word</span><span class="sxs-lookup"><span data-stu-id="81f3d-134">Word</span></span>

- <span data-ttu-id="81f3d-135">我們修正了當焦點位於註解文字方塊中時，[編輯器] 命令會被停用的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-135">We fixed an issue where the 'Editor' command was disabled when the focus was in a comment text box.</span></span>
- <span data-ttu-id="81f3d-136">我們修正了當焦點位於註解文字方塊中時，[顯示標記] 命令會被停用的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-136">We fixed an issue where the 'Show Markup' command was disabled when the focus was in a comment text box.</span></span>
- <span data-ttu-id="81f3d-137">我們修正了自訂 XML 中的註解狀態在開啟文件時可能會遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-137">We fixed an issue in custom XML where the state of comments may be lost when opening the document.</span></span>

### <a name="office-suite"></a><span data-ttu-id="81f3d-138">Office 套件</span><span class="sxs-lookup"><span data-stu-id="81f3d-138">Office Suite</span></span>

- <span data-ttu-id="81f3d-139">我們修正了使用者從工作列開啟新應用程式視窗，並建立新的空白檔時，會造成額外檔案建立的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-139">We fixed an issue where after the user opened a new app window from the taskbar and created a new blank document, additional files were created.</span></span>
- <span data-ttu-id="81f3d-140">我們修正了當使用者在編輯文件，但是許可權遺失時，我們並未通知使用者必須重新驗證的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-140">We fixed an issue where if a user was editing a document but had lost permissions, we were not notifying the user that they had to re-authenticate.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-july-10"></a><span data-ttu-id="81f3d-142">版本 2008：7 月 10 日</span><span class="sxs-lookup"><span data-stu-id="81f3d-142">Version 2008: July 10</span></span>
<span data-ttu-id="81f3d-143">*版本 2008 (組建 13102.20002)*</span><span class="sxs-lookup"><span data-stu-id="81f3d-143">*Version 2008 (Build 13102.20002)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="81f3d-145">解決的問題</span><span class="sxs-lookup"><span data-stu-id="81f3d-145">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="81f3d-146">Outlook</span><span class="sxs-lookup"><span data-stu-id="81f3d-146">Outlook</span></span>

- <span data-ttu-id="81f3d-147">我們已修正，如果未核取 [下載共用資料夾]，共用行事曆會議 [回覆選項] 中缺少 [允許轉寄] 選項的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-147">We fixed an issue where the Allow Forwarding option was missing from the shared calendar meeting "Response Options" if Download shared folder was NOT checked.</span></span>
- <span data-ttu-id="81f3d-148">我們已修正，即使使用者具有適當的列印權限也會在停用狀態下顯示列印按鈕的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-148">We fixed an issue that would display the print button in a disabled state even though the user had the appropriate print permissions.</span></span>

### <a name="project"></a><span data-ttu-id="81f3d-149">Project</span><span class="sxs-lookup"><span data-stu-id="81f3d-149">Project</span></span>

- <span data-ttu-id="81f3d-150">我們已修正如果您嘗試從 Project 將 PDF/XPS 儲存至 SharePoint 文件庫，沒有發生任何動作的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-150">We fixed an issue where if you tried to save a PDF/XPS from Project to a SharePoint document library, nothing would happen.</span></span>

### <a name="word"></a><span data-ttu-id="81f3d-151">Word</span><span class="sxs-lookup"><span data-stu-id="81f3d-151">Word</span></span>

- <span data-ttu-id="81f3d-152">我們已修正將某些文字及影像貼到 [註解] 方塊之後，Word 停止回應的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-152">We fixed an issue where Word would stop responding after pasting some text and an image in to a comments box.</span></span>
- <span data-ttu-id="81f3d-153">我們已修正刪除最後一個註解後，[新增批註] 按鈕停用的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-153">We fixed an issue where the 'New comment' button would be disabled after deleting the last comment.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-july-03"></a><span data-ttu-id="81f3d-155">版本 2007：7 月 3 日</span><span class="sxs-lookup"><span data-stu-id="81f3d-155">Version 2007: July 03</span></span>
<span data-ttu-id="81f3d-156">*版本 2007 (組建 13029.20006)*</span><span class="sxs-lookup"><span data-stu-id="81f3d-156">*Version 2007 (Build 13029.20006)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="81f3d-158">功能更新</span><span class="sxs-lookup"><span data-stu-id="81f3d-158">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="81f3d-159">Outlook</span><span class="sxs-lookup"><span data-stu-id="81f3d-159">Outlook</span></span>

- <span data-ttu-id="81f3d-160">**在 Outlook 中使用 [快速投票] 建立投票：** 輕鬆建立投票，收集投票，並查看電子郵件中的結果 [深入了解](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="81f3d-160">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="81f3d-161">**新的會議室尋找工具：** 依不同功能搜尋會議室。</span><span class="sxs-lookup"><span data-stu-id="81f3d-161">**New room finder:** Search for conference rooms by different capabilities.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="81f3d-164">解決的問題</span><span class="sxs-lookup"><span data-stu-id="81f3d-164">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="81f3d-165">Excel</span><span class="sxs-lookup"><span data-stu-id="81f3d-165">Excel</span></span>

- <span data-ttu-id="81f3d-166">我們修正以下問題：在特定版本 Excel 中建立的資料模型表格無法在 [表格預覽] 中看到，即使與該表相關聯的查詢尚未編輯。</span><span class="sxs-lookup"><span data-stu-id="81f3d-166">We fixed an issue where data model tables created in certain versions of Excel could not be seen in 'Table Preview' even though the query associated with the table had not been edited.</span></span>
- <span data-ttu-id="81f3d-167">我們已修正在 [定義名稱\套用名稱] 對話方塊中停用 [忽略相對/絕對] 參照會導致公式無法使用的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-167">We fixed an issue where disabling 'Ignore Relative/Absolute' references in the Define Name \ Apply Names dialog would cause formulas to not work.</span></span>
- <span data-ttu-id="81f3d-168">我們已修正清除 [進階資料篩選] 可能會遺失表格格式設定的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-168">We fixed an issue where clearing an advanced data filter could lose table formatting.</span></span>
- <span data-ttu-id="81f3d-169">我們已修正嵌入式 PDF 文件的完整路徑顯示在文件標題，而不只是檔案名稱的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-169">We fixed an issue where the full path of an embedded PDF document would show in the document caption rather than just the filename.</span></span>
- <span data-ttu-id="81f3d-170">我們已修正停用 Wolfram 雲端連接器之後，儲存並重新開啟 Excel 活頁簿可能會導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-170">We fixed an issue where after disabling the Wolfram cloud connector and then saving and re-opening an Excel workbook, could result in a crash.</span></span>
- <span data-ttu-id="81f3d-171">我們已修正啟動 Excel 時啟用 [規劃求解] 增益集將導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-171">We fixed an issue where booting Excel with the Solver add-in enabled would result in a crash.</span></span>

### <a name="outlook"></a><span data-ttu-id="81f3d-172">Outlook</span><span class="sxs-lookup"><span data-stu-id="81f3d-172">Outlook</span></span>

- <span data-ttu-id="81f3d-173">我們已修正如果在 [收件者] 行上有超過 130 個收件者，Outlook 會當機的問題，且我們也改善了呈現文字的效能。</span><span class="sxs-lookup"><span data-stu-id="81f3d-173">We fixed an issue where Outlook would hang if there were over 130 recipients on the 'To' line and we also improved the performance of rendering the text.</span></span>
- <span data-ttu-id="81f3d-174">我們已修正「待辦事項列」中跨越兩天以上的活動，在後續的所有日期中顯示相同結束時間的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-174">We fixed an issue in the 'To Do Bar' where events that spanned more than two days, displayed the same end time for all subsequent days.</span></span>
- <span data-ttu-id="81f3d-175">我們已修正導致 Outlook 使用者在使用共用行事曆後，在幾分鐘內訊息清單停止更新的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-175">We fixed an issue that caused users of Outlook to see their message list stop updating for several minutes after using shared calendars.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="81f3d-176">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="81f3d-176">PowerPoint</span></span>

- <span data-ttu-id="81f3d-177">我們已修正將 HTML 貼到投影片上的文字區域時，會改為貼上投影片最上方所建立的文字方塊中的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-177">We fixed an issue where pasting HTML to a text area on a slide would instead get pasted into a text box created at the top of the slide.</span></span>
- <span data-ttu-id="81f3d-178">我們已修正在 [簡報者檢視畫面] 中選取所有投影片、使用 Alt+Tab 退出 [簡報者檢視畫面] 並返回投影片放映，然後按一下 [結束放映] 時，將導致未處理例外狀況的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-178">We fixed an issue where selecting all slides in Presenter View, then exiting Presenter View using Alt+Tab and returning to the slide show and clicking 'End Show' would result in an unhandled exception.</span></span>

### <a name="project"></a><span data-ttu-id="81f3d-179">Project</span><span class="sxs-lookup"><span data-stu-id="81f3d-179">Project</span></span>

- <span data-ttu-id="81f3d-180">我們已修正 Project 在開啟特定 XML 檔案時可能當機的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-180">We fixed an issue where Project may crash when opening certain XML files.</span></span>
- <span data-ttu-id="81f3d-181">我們已修正如果文件庫處於新式模式，您無法從 SharePoint 文件庫開啟 Project 檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-181">We fixed an issue where you couldn't open a Project file from a SharePoint document library if the library was in modern mode.</span></span>
- <span data-ttu-id="81f3d-182">我們已修正 URL 以 '.com' 結尾時，無法從 Project Web App 在 Project 傳統型用戶端開啟專案的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-182">We fixed an issue where projects couldn't be opened in the Project desktop client from the Project Web App if the URL ended in '.com'.</span></span>

### <a name="word"></a><span data-ttu-id="81f3d-183">Word</span><span class="sxs-lookup"><span data-stu-id="81f3d-183">Word</span></span>

- <span data-ttu-id="81f3d-184">我們已修正在共同撰寫模式期間，當發生合併衝突且使用者已選取放棄變更時，我們不再顯示儲存或捨棄變更選項的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-184">We fixed an issue during co-authoring mode when there is a merge conflict and the user has already chosen to discard changes, we no longer display the option to save or discard changes.</span></span>
- <span data-ttu-id="81f3d-185">我們已修正一個問題，當嘗試使用新名稱儲存包含巨集的檔案時，無論使用者輸入什麼名稱，都會導致該檔案以 .docx 副檔名和檔案名稱 'WRO0004.docx' 儲存，進而導致文件無法使用。</span><span class="sxs-lookup"><span data-stu-id="81f3d-185">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with a .docx extension and the filename 'WRO0004.docx', regardless of what the user entered, rendering the document unusable.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-june-26"></a><span data-ttu-id="81f3d-187">版本 2007：6 月 26 日</span><span class="sxs-lookup"><span data-stu-id="81f3d-187">Version 2007: June 26</span></span>
<span data-ttu-id="81f3d-188">*版本 2007 (組建 13020.20004)*</span><span class="sxs-lookup"><span data-stu-id="81f3d-188">*Version 2007 (Build 13020.20004)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="81f3d-190">解決的問題</span><span class="sxs-lookup"><span data-stu-id="81f3d-190">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="81f3d-191">Access</span><span class="sxs-lookup"><span data-stu-id="81f3d-191">Access</span></span>

- <span data-ttu-id="81f3d-192">我們已修正在重新整理連結的 SQL 資料表時，連結資料表管理員會提示您輸入主要索引鍵的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-192">We fixed an issue where the linked table manager would prompt for a primary key if a linked SQL table was refreshed.</span></span>
- <span data-ttu-id="81f3d-193">我們已修正 [查詢編輯器] 中的查詢捲出畫面的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-193">We fixed an issue where queries in the Query Editor scrolled out of view.</span></span>
- <span data-ttu-id="81f3d-194">我們已修正執行查詢的時間大約比預期完成時間兩倍久的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-194">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

### <a name="outlook"></a><span data-ttu-id="81f3d-195">Outlook</span><span class="sxs-lookup"><span data-stu-id="81f3d-195">Outlook</span></span>

- <span data-ttu-id="81f3d-196">我們已修正使用者無法使用通訊群組清單中的「傳送為」或「代理傳送者」的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-196">We fixed an issue where users were unable to 'Send As' or 'Send on behalf' of a distribution list.</span></span>
- <span data-ttu-id="81f3d-197">我們已修正在郵件中插入影像內嵌，然後將郵件儲存為草稿將會重新調整影像大小的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-197">We fixed an issue where inserting an image inline in a message, then saving the message as a draft would result in a resizing of the image.</span></span>
- <span data-ttu-id="81f3d-198">我們已修正在編輯主旨之後，導致 NDR 郵件的本文從 Unicode 變更為 ASCII 的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-198">We fixed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

### <a name="project"></a><span data-ttu-id="81f3d-199">Project</span><span class="sxs-lookup"><span data-stu-id="81f3d-199">Project</span></span>

- <span data-ttu-id="81f3d-200">我們已修正政府社群雲端中的 Project Planner 連結已停用的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-200">We fixed an issue where Project Planner links in Government Community Cloud environments had been disabled.</span></span>

### <a name="office-suite"></a><span data-ttu-id="81f3d-201">Office 套件</span><span class="sxs-lookup"><span data-stu-id="81f3d-201">Office Suite</span></span>

- <span data-ttu-id="81f3d-202">我們已修正將插入可縮放向量圖形 (SVG) 中的文字插入到 Word、Excel 或 PowerPoint 檔案、儲存並關閉檔案，然後重新開啟檔案後，難以辨識的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-202">We fixed an issue where text inserted in a Scalable Vector Graphic (SVG) was illegible after inserting it in a Word, Excel, or PowerPoint file, saving and closing the file, and then re-opening the file.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-june-19"></a><span data-ttu-id="81f3d-204">版本 2007：6 月 19 日</span><span class="sxs-lookup"><span data-stu-id="81f3d-204">Version 2007: June 19</span></span>
<span data-ttu-id="81f3d-205">*版本 2007 (組建 13012.20000)*</span><span class="sxs-lookup"><span data-stu-id="81f3d-205">*Version 2007 (Build 13012.20000)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="81f3d-207">解決的問題</span><span class="sxs-lookup"><span data-stu-id="81f3d-207">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="81f3d-208">Excel</span><span class="sxs-lookup"><span data-stu-id="81f3d-208">Excel</span></span>

- <span data-ttu-id="81f3d-209">我們已修正將活頁簿儲存至 SharePoint/OneDrive 時，會導致自訂功能區索引標籤 CustomUI XML 遭移除的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-209">We fixed an issue where CustomUI XML for a custom ribbon tab was removed when saving a workbook to SharePoint/OneDrive.</span></span>
- <span data-ttu-id="81f3d-210">我們已修正當建議以唯讀方式使用檔案時，活頁簿處於唯讀狀態的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-210">We fixed an issue where workbooks were read-only when the file only had read-only recommended.</span></span>

### <a name="outlook"></a><span data-ttu-id="81f3d-211">Outlook</span><span class="sxs-lookup"><span data-stu-id="81f3d-211">Outlook</span></span>

- <span data-ttu-id="81f3d-212">我們已修正以下問題：當使用多個不同解析度的監視器時，輸入法編輯器 (IEM) 視窗會覆蓋透過 IME 輸入的文字。</span><span class="sxs-lookup"><span data-stu-id="81f3d-212">We fixed an issue where the Input Method Editor (IME) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>
- <span data-ttu-id="81f3d-213">我們已修正導致使用者在關閉先前儲存的約會時看到下列錯誤的問題：「項目無法儲存，因為已被其他使用者或已在其他視窗中變更過。</span><span class="sxs-lookup"><span data-stu-id="81f3d-213">We fixed an issue that caused users to see the following error when closing an appointment that was previously saved: "The item cannot be saved because it was changed by another user or in another window.</span></span> <span data-ttu-id="81f3d-214">您要在預設資料夾為這個項目建立複本?」</span><span class="sxs-lookup"><span data-stu-id="81f3d-214">Do you want to make a copy in the default folder for the item?"</span></span>
- <span data-ttu-id="81f3d-215">我們已修正迷你行事曆中的日期無法針對日本使用者顯示粗體的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-215">We fixed an issue where dates in the mini calendar failed to display in bold for users in Japan.</span></span>
- <span data-ttu-id="81f3d-216">我們已修正行事曆提醒無法針對一週內即將到來的會議顯示確切時間的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-216">We fixed an issue that prevented calendar reminders from showing exact times for meetings coming up in less than a week.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="81f3d-217">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="81f3d-217">PowerPoint</span></span>

- <span data-ttu-id="81f3d-218">我們已修正在即時共同撰寫工作階段期間，使用者的目前狀態色彩指示器無法在共同撰寫文件庫中重新整理的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-218">We fixed an issue where a user's presence color indicator was not getting refreshed in the co-authoring gallery during a live co-authoring session.</span></span>

### <a name="project"></a><span data-ttu-id="81f3d-219">Project</span><span class="sxs-lookup"><span data-stu-id="81f3d-219">Project</span></span>

- <span data-ttu-id="81f3d-220">我們已修正以下問題：如果固定工期的任務已 100% 完成，但未指定 [實際完成日期]，則任務的完成 % 將顯示為低於 100%。</span><span class="sxs-lookup"><span data-stu-id="81f3d-220">We fixed an issue where if Fixed Duration tasks are at 100% complete but the Actual Finish is not specified, the Task % Complete would display as less than 100%.</span></span>

### <a name="word"></a><span data-ttu-id="81f3d-221">Word</span><span class="sxs-lookup"><span data-stu-id="81f3d-221">Word</span></span>

- <span data-ttu-id="81f3d-222">我們已修正 HTML 超連結色彩無法正確呈現的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-222">We fixed an issue where the HTML hyperlink color was not being rendered correctly.</span></span>

### <a name="office-suite"></a><span data-ttu-id="81f3d-223">Office 套件</span><span class="sxs-lookup"><span data-stu-id="81f3d-223">Office Suite</span></span>

- <span data-ttu-id="81f3d-224">我們已修正非 HTTP 或 HTTPS 型 URL 未顯示在 [最近用過的] 清單中的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-224">We fixed an issue where URLs that were not http or https based were not being displayed in the Most Recently Used list.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-june-12"></a><span data-ttu-id="81f3d-226">版本 2007：6 月 12 日</span><span class="sxs-lookup"><span data-stu-id="81f3d-226">Version 2007: June 12</span></span>
<span data-ttu-id="81f3d-227">*版本 2007 (組建 13006.20002)*</span><span class="sxs-lookup"><span data-stu-id="81f3d-227">*Version 2007 (Build 13006.20002)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="81f3d-229">功能更新</span><span class="sxs-lookup"><span data-stu-id="81f3d-229">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="81f3d-230">Excel</span><span class="sxs-lookup"><span data-stu-id="81f3d-230">Excel</span></span>

- <span data-ttu-id="81f3d-231">**使用資料類型從 Power BI 取得組織資料：** 現在，來自 Power BI 的 Excel 資料類型將推出給使用 Office 365 E5/A5 或 Microsoft 365 E5/A5 之組織的測試人員使用。</span><span class="sxs-lookup"><span data-stu-id="81f3d-231">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 E5/A5 or Microsoft 365 E5/A5.</span></span> <span data-ttu-id="81f3d-232">取得您所需的資訊，輕鬆地重新整理，對許多日常工作流程而言至關重要。</span><span class="sxs-lookup"><span data-stu-id="81f3d-232">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="81f3d-233">我們允許您透過 Excel 中的資料類型從 Power BI 存取公司或組織資訊，從而擴充您在試算表中引入連結資訊的能力。</span><span class="sxs-lookup"><span data-stu-id="81f3d-233">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="81f3d-234">深入了解</span><span class="sxs-lookup"><span data-stu-id="81f3d-234">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="81f3d-235">在[部落格文章](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="81f3d-235">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="81f3d-238">解決的問題</span><span class="sxs-lookup"><span data-stu-id="81f3d-238">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="81f3d-239">Access</span><span class="sxs-lookup"><span data-stu-id="81f3d-239">Access</span></span>

- <span data-ttu-id="81f3d-240">我們已修正導致 Microsoft Access 無法識別連結的 SQL Server 資料表中的識別資料行的問題，這可能會導致不正確地將資料列報告為已刪除。</span><span class="sxs-lookup"><span data-stu-id="81f3d-240">We fixed an issue that caused Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which could cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="81f3d-241">Excel</span><span class="sxs-lookup"><span data-stu-id="81f3d-241">Excel</span></span>

- <span data-ttu-id="81f3d-242">我們已修正雷達圖的主要格線無法正確設定格式的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-242">We fixed an issue where the major grid lines of radar charts could not be formatted correctly.</span></span>

### <a name="project"></a><span data-ttu-id="81f3d-243">Project</span><span class="sxs-lookup"><span data-stu-id="81f3d-243">Project</span></span>

- <span data-ttu-id="81f3d-244">我們已修正當專案摘要工作，或專案 [開始/工作] 欄位變更時，ProjectBeforeTaskChange 事件無法觸發的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-244">We fixed an issue where the ProjectBeforeTaskChange event didn't fire when there was a change to the project summary task, either the project start/task field.</span></span>
- <span data-ttu-id="81f3d-245">我們已修正以下問題：比較基準重設或更新可能會變更時間分段預算成本/工時資源，且比較基準反映不正確的預算值。</span><span class="sxs-lookup"><span data-stu-id="81f3d-245">We fixed an issue where a baseline reset or update could change time-phased budget cost/work resources and the baseline could reflect incorrect budget values.</span></span>

### <a name="word"></a><span data-ttu-id="81f3d-246">Word</span><span class="sxs-lookup"><span data-stu-id="81f3d-246">Word</span></span>

- <span data-ttu-id="81f3d-247">我們已修正使用 Office 功能區中的 [清除格式設定] 按鈕清除 [註解] 窗格中的格式設定時，無法運作的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-247">We fixed an issue where the ability to clear formatting within the Comments pane via the Clear Formatting button in the Office Ribbon was not working.</span></span>
- <span data-ttu-id="81f3d-248">我們已修正當尺規未顯示時變更表格大小，導致在背景中執行其他應用程式開始閃爍的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-248">We fixed an issue where changing the size of a table when the ruler is not displayed caused other applications running in the background to start flashing.</span></span>
- <span data-ttu-id="81f3d-249">我們已修正在共同撰寫模式中，註解回覆有時候不會顯示在 [註解] 窗格中，而是顯示在 [修訂] 窗格中的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-249">We fixed an issue where in co-authoring mode, comment replies would sometimes not show up in the comments pane but would be visible in the revisions pane.</span></span>
- <span data-ttu-id="81f3d-250">我們已修正以下問題：如果 Word 經常開啟的文件清單多於 50 個，然後儲存並開啟文件後，即使該文件沒有進行任何修訂，也會顯示歷程記錄。</span><span class="sxs-lookup"><span data-stu-id="81f3d-250">We fixed an issue where if Word had a list of more than 50 frequently opened documents, then after saving and opening a document, a revision history would be displayed even though no revisions were made to that document.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-june-05"></a><span data-ttu-id="81f3d-252">版本 2006：6 月 5 日</span><span class="sxs-lookup"><span data-stu-id="81f3d-252">Version 2006: June 05</span></span>
<span data-ttu-id="81f3d-253">*版本 2006 (組建 13001.20002)*</span><span class="sxs-lookup"><span data-stu-id="81f3d-253">*Version 2006 (Build 13001.20002)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="81f3d-255">功能更新</span><span class="sxs-lookup"><span data-stu-id="81f3d-255">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="81f3d-256">Excel</span><span class="sxs-lookup"><span data-stu-id="81f3d-256">Excel</span></span>

- <span data-ttu-id="81f3d-257">**在 Excel 中進行共同作業時排序/篩選：** 您現在可以在與其他人共同作業時，同時排序和篩選您的 Excel 檔案。</span><span class="sxs-lookup"><span data-stu-id="81f3d-257">**Sort/filter while collaborating in Excel:** You can now sort and filter your Excel file while collaborating with others.</span></span> <span data-ttu-id="81f3d-258">這項新功能可防止您在共同撰寫文件時，受到其他使用者的排序和篩選的影響。</span><span class="sxs-lookup"><span data-stu-id="81f3d-258">This new feature prevents you from being impacted by other user’s sorts and filters while coauthoring the document.</span></span>

- <span data-ttu-id="81f3d-259">**在 Excel 中建立來自 Power BI 資料的樞紐分析表：** 您可以在 Excel 中建立樞紐分析表，只要按幾下滑鼠，就能連線到儲存在 Power BI 的樞紐分析表。</span><span class="sxs-lookup"><span data-stu-id="81f3d-259">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span><span data-ttu-id="81f3d-260"> 如此一來，您就能獲得樞紐分析表和 Power BI 的最佳效果。</span><span class="sxs-lookup"><span data-stu-id="81f3d-260"> Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="81f3d-261">使用安全 Power BI 資料集的樞紐分析表以計算、摘要及分析資料。</span><span class="sxs-lookup"><span data-stu-id="81f3d-261">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="81f3d-262">深入了解</span><span class="sxs-lookup"><span data-stu-id="81f3d-262">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)

### <a name="outlook"></a><span data-ttu-id="81f3d-263">Outlook</span><span class="sxs-lookup"><span data-stu-id="81f3d-263">Outlook</span></span>

- <span data-ttu-id="81f3d-264">**快速重新開啟上一個工作階段的項目：** 我們新增了一個選項，可快速重新開啟上一個 Outlook 工作階段的項目。</span><span class="sxs-lookup"><span data-stu-id="81f3d-264">**Quickly reopen items from previous session:** We added an option to quickly reopen items from a previous Outlook session.</span></span> <span data-ttu-id="81f3d-265">不管 Outlook 當機或您將其關閉，您現在可以在重新開啟應用程式時快速重新啟動項目。</span><span class="sxs-lookup"><span data-stu-id="81f3d-265">Whether Outlook crashes or you close it, you’ll now be able to quickly relaunch items when you reopen the app.</span></span> <span data-ttu-id="81f3d-266">這項功能預設為啟用。</span><span class="sxs-lookup"><span data-stu-id="81f3d-266">This feature is on by default.</span></span> <span data-ttu-id="81f3d-267">若要將它關閉，請移至 [選項] > [一般] > [啟動選項]。</span><span class="sxs-lookup"><span data-stu-id="81f3d-267">To turn it off, go to Options > General > Start up Options.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="81f3d-270">解決的問題</span><span class="sxs-lookup"><span data-stu-id="81f3d-270">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="81f3d-271">Excel</span><span class="sxs-lookup"><span data-stu-id="81f3d-271">Excel</span></span>

- <span data-ttu-id="81f3d-272">我們已修正圖表座標軸上的自訂值無法正確套用的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-272">We fixed an issue where custom values on the chart axis would not get applied correctly.</span></span>
- <span data-ttu-id="81f3d-273">我們已修正包含多個含有定義名稱的公式會導致儲存檔案時間加長的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-273">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

### <a name="outlook"></a><span data-ttu-id="81f3d-274">Outlook</span><span class="sxs-lookup"><span data-stu-id="81f3d-274">Outlook</span></span>

- <span data-ttu-id="81f3d-275">我們已修正以下問題：當使用多個不同解析度的監視器時，輸入法編輯器 (IEM) 視窗會覆蓋透過 IME 輸入的文字。</span><span class="sxs-lookup"><span data-stu-id="81f3d-275">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>
- <span data-ttu-id="81f3d-276">我們已修正在撰寫新電子郵件訊息時，檢視範本會導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-276">We fixed an issue where viewing a template when composing a new email message would result in a crash.</span></span>
- <span data-ttu-id="81f3d-277">我們已修正在 Outlook 版本 1911之後，使用者無法使用 Exchange 2010 公用資料夾的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-277">We fixed an issue where users were unable to Exchange 2010 public folders after Outlook version 1911.</span></span>
- <span data-ttu-id="81f3d-278">我們已修正在 Office 功能區中，群組行事曆的 [分類] 按鈕已停用的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-278">We fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>
- <span data-ttu-id="81f3d-279">我們已修正具有衝突連絡人的使用者在 Outlook 中遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-279">We fixed an issue that would cause users with conflicting contacts to experience crashes in Outlook.</span></span>
- <span data-ttu-id="81f3d-280">我們已修正導致高 DPI 監視器上的使用者遺失資料夾屬性中的 [線上封存] 下拉式功能表的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-280">We fixed an issue that resulted in the Online Archive dropdown in folder properties to be missing for users on high DPI monitors.</span></span>
- <span data-ttu-id="81f3d-281">我們已修正當處理純文字電子郵件中的超連結時，導致使用者遇到 Outlook 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-281">We fixed an issue that caused users to experience a crash in Outlook when working with hyperlinks in Plain Text emails.</span></span>
- <span data-ttu-id="81f3d-282">我們已修正導致 Outlook 無法剖析使用 RFC2231 編碼的長檔名的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-282">We fixed an issue that caused Outlook to be unable to parse long file names encoded with RFC2231.</span></span>
- <span data-ttu-id="81f3d-283">我們已修正導致 Outlook 使用者在使用螢幕助讀程式時遇到間歇性當機的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-283">We fixed an issue that was causing Outlook users to experience intermittent hangs when using screen readers.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="81f3d-284">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="81f3d-284">PowerPoint</span></span>

- <span data-ttu-id="81f3d-285">我們已修正使用表單型驗證開啟伺服器設定的檔案時發生的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-285">We fixed an issue with opening server-configured files with forms-based authentication.</span></span>
- <span data-ttu-id="81f3d-286">我們已修正具有內嵌圖表/活頁簿的 PowerPoint 檔案可能會導致儲存檔案失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-286">We fixed an issue where PowerPoint files with embedded charts / workbooks could result in failures when saving the file.</span></span>
- <span data-ttu-id="81f3d-287">我們已修正使用者關閉的 [註解] 窗格會自動重新開啟的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-287">We fixed an issue where a Comment pane that had been closed by the user would re-open automatically.</span></span>
- <span data-ttu-id="81f3d-288">我們已修正某張投影片的投影片編輯工具會在下一張投影片上重疊的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-288">We fixed an issue where the slide editor from one slide would overlap on to the next slide.</span></span>

### <a name="project"></a><span data-ttu-id="81f3d-289">Project</span><span class="sxs-lookup"><span data-stu-id="81f3d-289">Project</span></span>

- <span data-ttu-id="81f3d-290">我們已修正在刪除孤立工作的父計畫之後，無法刪除或重新指派孤立工作的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-290">We fixed an issue that prevented orphaned tasks from being deleted or re-assigned after their parent plan was deleted.</span></span>

### <a name="word"></a><span data-ttu-id="81f3d-291">Word</span><span class="sxs-lookup"><span data-stu-id="81f3d-291">Word</span></span>

- <span data-ttu-id="81f3d-292">我們已修正 [註解] 窗格中的時間戳記不是根據系統地區設定時間的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-292">We fixed an issue where timestamps in Comment panes were not based on the system locale time.</span></span>
- <span data-ttu-id="81f3d-293">我們已修正網頁應用程式與傳統型應用程式之間的註解未同步處理的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-293">We fixed an issue where comments between the web app and the desktop application were not in sync.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


## <a name="version2006may29"></a><span data-ttu-id="81f3d-295">版本 2006：5 月 29 日</span><span class="sxs-lookup"><span data-stu-id="81f3d-295">Version 2006: May 29</span></span>
<span data-ttu-id="81f3d-296">*版本 2006 (組建 12920.20000)*</span><span class="sxs-lookup"><span data-stu-id="81f3d-296">*Version 2006 (Build 12920.20000)*</span></span>

### <a name="featureupdates"></a><span data-ttu-id="81f3d-297">功能更新</span><span class="sxs-lookup"><span data-stu-id="81f3d-297">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="81f3d-298">Outlook</span><span class="sxs-lookup"><span data-stu-id="81f3d-298">Outlook</span></span>

- <span data-ttu-id="81f3d-299">**新增至 Outlook 快顯通知的其他按鈕：**[快速動作] 按鈕現在會於在 Windows 10 上執行 Outlook 時顯示在 Outlook 快顯通知中。</span><span class="sxs-lookup"><span data-stu-id="81f3d-299">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="81f3d-300">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="81f3d-300">PowerPoint</span></span>

- <span data-ttu-id="81f3d-301">**PowerPoint 中改善的 Steam 影片效能：** 我們改善了 Microsoft Stream 影片的播放效能，將影片載入時間減至最少，以建立流暢的觀賞體驗。</span><span class="sxs-lookup"><span data-stu-id="81f3d-301">**Improved Stream video performance in PowerPoint:** We've made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span>  <span data-ttu-id="81f3d-302">您可以在 Microsoft Stream 上使用公司影片來建立更完善的簡報。</span><span class="sxs-lookup"><span data-stu-id="81f3d-302">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolvedissues"></a><span data-ttu-id="81f3d-305">解決的問題</span><span class="sxs-lookup"><span data-stu-id="81f3d-305">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="81f3d-306">Excel</span><span class="sxs-lookup"><span data-stu-id="81f3d-306">Excel</span></span>

- <span data-ttu-id="81f3d-307">我們已修正在使用 OneDrive 時，Excel 偶爾會關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-307">We fixed an issue where Excel would occasionally shut down when engaging OneDrive.</span></span>
- <span data-ttu-id="81f3d-308">我們已修正在相同活頁簿中按一下加入書籤的超連結會導致活頁簿隱藏的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-308">We fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>
- <span data-ttu-id="81f3d-309">我們已修正某些複製和貼上的圖表連結使用的是映射磁碟機位址，而不是通用位址的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-309">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>
- <span data-ttu-id="81f3d-310">我們已修正當透過 Teams 共用 Excel 視窗時，使用 Ctrl+Shift+方向鍵捲動後，Excel 可能會無法回應的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-310">We fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window was shared through Teams.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="81f3d-311">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="81f3d-311">PowerPoint</span></span>

- <span data-ttu-id="81f3d-312">我們已修正使用滑鼠滾輪縮放後，投影片並未置中的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-312">We fixed an issue where slides were not centered after zooming using the mouse wheel.</span></span>

### <a name="word"></a><span data-ttu-id="81f3d-313">Word</span><span class="sxs-lookup"><span data-stu-id="81f3d-313">Word</span></span>

- <span data-ttu-id="81f3d-314">我們已修正在 [註解] 窗格中複製及貼上文字無法顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-314">We fixed an issue where copy and pasting text to a comment pane would not be displayed.</span></span>
- <span data-ttu-id="81f3d-315">我們已修正註解提示泡泡在100% 縮放比例中顯示模糊的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-315">We fixed an issue where comment hint bubbles appeared blurry at 100% zoom.</span></span>
- <span data-ttu-id="81f3d-316">我們已修正啟用原則 Word 2007 及更新版本的二進位檔案和範本會導致部分共同撰寫案例失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-316">We fixed an issue where enabling policy Word 2007 and later Binary Documents and Templates would cause some co-authoring cases to fail.</span></span>
- <span data-ttu-id="81f3d-317">我們已修正具長路徑名稱 (大於 32K) 的檔案無法開啟，且未顯示適當的錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-317">We fixed an issue where files with long path names (greater than 32K) would not open and an appropriate error message was not being displayed.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


## <a name="version-2006-may-22"></a><span data-ttu-id="81f3d-318">版本 2006：5 月 22 日</span><span class="sxs-lookup"><span data-stu-id="81f3d-318">Version 2006: May 22</span></span>
<span data-ttu-id="81f3d-319">*版本 2006 (組建 12914.20000)*</span><span class="sxs-lookup"><span data-stu-id="81f3d-319">*Version 2006 (Build 12914.20000)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="81f3d-321">功能更新</span><span class="sxs-lookup"><span data-stu-id="81f3d-321">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="81f3d-322">Excel</span><span class="sxs-lookup"><span data-stu-id="81f3d-322">Excel</span></span>

- <span data-ttu-id="81f3d-323">**儲存至釘選資料夾：** 釘選資料夾可讓您更輕鬆地儲存 Office 檔案。</span><span class="sxs-lookup"><span data-stu-id="81f3d-323">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="81f3d-324">我們收到了意見反應，使用者想更進一步控制儲存新檔案時可用的資料夾。</span><span class="sxs-lookup"><span data-stu-id="81f3d-324">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="81f3d-325">我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。</span><span class="sxs-lookup"><span data-stu-id="81f3d-325">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="81f3d-326">這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。</span><span class="sxs-lookup"><span data-stu-id="81f3d-326">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="81f3d-327">在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="81f3d-327">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="81f3d-328">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="81f3d-328">PowerPoint</span></span>

- <span data-ttu-id="81f3d-329">**儲存至釘選資料夾：** 釘選資料夾可讓您更輕鬆地儲存 Office 檔案。</span><span class="sxs-lookup"><span data-stu-id="81f3d-329">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="81f3d-330">我們收到了意見反應，使用者想更進一步控制儲存新檔案時可用的資料夾。</span><span class="sxs-lookup"><span data-stu-id="81f3d-330">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="81f3d-331">我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。</span><span class="sxs-lookup"><span data-stu-id="81f3d-331">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="81f3d-332">這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。</span><span class="sxs-lookup"><span data-stu-id="81f3d-332">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="81f3d-333">在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="81f3d-333">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="word"></a><span data-ttu-id="81f3d-334">Word</span><span class="sxs-lookup"><span data-stu-id="81f3d-334">Word</span></span>

- <span data-ttu-id="81f3d-335">**儲存至釘選資料夾：** 釘選資料夾可讓您更輕鬆地儲存 Office 檔案。</span><span class="sxs-lookup"><span data-stu-id="81f3d-335">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="81f3d-336">我們收到了意見反應，使用者想更進一步控制儲存新檔案時可用的資料夾。</span><span class="sxs-lookup"><span data-stu-id="81f3d-336">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="81f3d-337">我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。</span><span class="sxs-lookup"><span data-stu-id="81f3d-337">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="81f3d-338">這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。</span><span class="sxs-lookup"><span data-stu-id="81f3d-338">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="81f3d-339">在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="81f3d-339">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="81f3d-342">解決的問題</span><span class="sxs-lookup"><span data-stu-id="81f3d-342">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="81f3d-343">Excel</span><span class="sxs-lookup"><span data-stu-id="81f3d-343">Excel</span></span>

- <span data-ttu-id="81f3d-344">我們已修正因為增益集是以字母順序載入，而不是以使用者指定的順序載入，而顯示 [這個活頁簿目前正由其他活頁簿所參考中，不可關閉] 錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-344">We fixed an issue where the error message: “This workbook is currently referenced by another and cannot be closed” would appear because Add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>
- <span data-ttu-id="81f3d-345">我們已修正管理 Excel 與部分協力廠商輔助技術應用程式之間的字型時發生記憶體損毀的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-345">We fixed an issue where memory was being corrupted when managing fonts between Excel and some third party assistive technology applications.</span></span>
- <span data-ttu-id="81f3d-346">我們已修正當增益集要求工作表 (包含使用 noSelect 鎖定的圖形) 上的主機項目時，Excel 可能當機的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-346">We fixed an issue where Excel would crash when Add-ins ask for Host Items on worksheets that contain shapes with noSelect locks.</span></span>

### <a name="outlook"></a><span data-ttu-id="81f3d-347">Outlook</span><span class="sxs-lookup"><span data-stu-id="81f3d-347">Outlook</span></span>

- <span data-ttu-id="81f3d-348">我們已修正當使用者在資料夾之間移動項目時，Folder.BeforeItemMove 事件未正確觸發的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-348">We fixed an issue where the Folder.BeforeItemMove event didn't fire correctly when a user moved items between folders.</span></span>
- <span data-ttu-id="81f3d-349">我們已修正使用者在橫跨午夜臨界值的行事曆項目中看到顯示為 [全天] 事件的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-349">We fixed an issue where users saw calendar items that spanned the midnight threshold as All day events.</span></span>
- <span data-ttu-id="81f3d-350">我們已修正當兩個增益集將按鈕新增到功能區中的相同群組時，Outlook 發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-350">We fixed an issue where Outlook crashed when two Add-ins added a button to the same group in the ribbon.</span></span>
- <span data-ttu-id="81f3d-351">我們已修正使用者無法與來賓使用者共用行事曆的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-351">We fixed an issue where users were unable to share a calendar with a guest user.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="81f3d-352">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="81f3d-352">PowerPoint</span></span>

- <span data-ttu-id="81f3d-353">我們已修正放大和縮小簡報會造成縮放選取跑馬燈和滑鼠指標之間間隙的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-353">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

### <a name="project"></a><span data-ttu-id="81f3d-354">Project</span><span class="sxs-lookup"><span data-stu-id="81f3d-354">Project</span></span>

- <span data-ttu-id="81f3d-355">我們已修正在按一下 [選項] 之後 Project 會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-355">We fixed an issue where Project would crash after clicking on Options.</span></span>

### <a name="word"></a><span data-ttu-id="81f3d-356">Word</span><span class="sxs-lookup"><span data-stu-id="81f3d-356">Word</span></span>

- <span data-ttu-id="81f3d-357">我們已修正註解中的超連結無法正常運作的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-357">We fixed an issue where hyperlinks in comments weren’t working.</span></span>
- <span data-ttu-id="81f3d-358">我們已修正放大和縮小簡報會造成縮放選取跑馬燈和滑鼠指標之間間隙的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-358">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>
- <span data-ttu-id="81f3d-359">我們已修正無法將 HTML 貼入行事曆的 WordMail 的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-359">We fixed an issue where pasting HTML into WordMail for Calendar wasn’t working.</span></span>
- <span data-ttu-id="81f3d-360">我們已修正在共同撰寫工作階段中回覆註解有時會導致 Word 凍結的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-360">We fixed an issue where replying to a comment in a co-authored session could sometimes cause Word to freeze.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-may-15"></a><span data-ttu-id="81f3d-362">版本 2006：5 月 15 日</span><span class="sxs-lookup"><span data-stu-id="81f3d-362">Version 2006: May 15</span></span>
<span data-ttu-id="81f3d-363">*版本 2006 (組建 12905.20000)*</span><span class="sxs-lookup"><span data-stu-id="81f3d-363">*Version 2006 (Build 12905.20000)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="81f3d-365">功能更新</span><span class="sxs-lookup"><span data-stu-id="81f3d-365">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="81f3d-366">Excel</span><span class="sxs-lookup"><span data-stu-id="81f3d-366">Excel</span></span>

- <span data-ttu-id="81f3d-367">**建立 PDF 連線：** 連線至、匯入、重新整理 PDF 中的資料。</span><span class="sxs-lookup"><span data-stu-id="81f3d-367">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="81f3d-368">深入了解</span><span class="sxs-lookup"><span data-stu-id="81f3d-368">Learn more</span></span>](https://support.office.com/article/9967afd8-85ee-4df3-aa06-753bcc1a2724)

### <a name="outlook"></a><span data-ttu-id="81f3d-369">Outlook</span><span class="sxs-lookup"><span data-stu-id="81f3d-369">Outlook</span></span>

- <span data-ttu-id="81f3d-370">**找到您所需的資訊：** 使用資料夾、寄件者、日期、附件資訊等選項來縮小搜尋範圍。</span><span class="sxs-lookup"><span data-stu-id="81f3d-370">**Find just what you need:** Narrow your search with options like folder, sender, date, attachment info, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="81f3d-371">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="81f3d-371">PowerPoint</span></span>

- <span data-ttu-id="81f3d-372">**不需要簡報導覽裝置：有耳塞式耳機就夠了：** 使用您的 Surface Earbuds 控制 PowerPoint 簡報。</span><span class="sxs-lookup"><span data-stu-id="81f3d-372">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="81f3d-373">重要：您必須在 Windows 10 的 Surface 音訊應用程式中配對 Surface Earbuds，才能使用手勢來控制簡報。</span><span class="sxs-lookup"><span data-stu-id="81f3d-373">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="81f3d-374">在此取得 Windows 10 上 Surface 音訊應用程式入門的指示。</span><span class="sxs-lookup"><span data-stu-id="81f3d-374">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="81f3d-375">深入了解</span><span class="sxs-lookup"><span data-stu-id="81f3d-375">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

### <a name="word"></a><span data-ttu-id="81f3d-376">Word</span><span class="sxs-lookup"><span data-stu-id="81f3d-376">Word</span></span>

- <span data-ttu-id="81f3d-377">**[自動套用] 或 [建議敏感度] 標籤：** Office 可以根據偵測到的敏感性內容來推薦或自動套用靈敏度標籤。</span><span class="sxs-lookup"><span data-stu-id="81f3d-377">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="81f3d-380">解決的問題</span><span class="sxs-lookup"><span data-stu-id="81f3d-380">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="81f3d-381">Excel</span><span class="sxs-lookup"><span data-stu-id="81f3d-381">Excel</span></span>
- <span data-ttu-id="81f3d-382">我們已修正在使用者刪除合併的欄時，造成執行時間增加的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-382">We fixed an issue that resulted in improved performance time for users when they deleted merged columns.</span></span>
- <div><span data-ttu-id="81f3d-383">我們已修正導致印表機名稱在可用印表機清單中重複的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-383">We fixed an issue that caused printer names to be duplicated in the list of available printers.</span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="81f3d-384">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="81f3d-384">PowerPoint</span></span>
- <span data-ttu-id="81f3d-385">我們已修正使用英文 (瑞士) (QWERTZ) 鍵盤時鍵盤快速鍵和拼字檢查無法正常運作的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-385">We fixed an issue where keyboard shortcuts and spell check wouldn’t function as expected when using an English Switzerland (QWERTZ) keyboard.</span></span>

### <a name="word"></a><span data-ttu-id="81f3d-386">Word</span><span class="sxs-lookup"><span data-stu-id="81f3d-386">Word</span></span>
- <span data-ttu-id="81f3d-387">我們已修正在空白文件中新增註解卻未執行任何動作的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-387">We fixed an issue where adding a new comment on a blank document wouldn't do anything.</span></span>
- <span data-ttu-id="81f3d-388">我們已修正在含有一百個以上專案的檔中插入或更新索引的問題會導致應用程式當機。</span><span class="sxs-lookup"><span data-stu-id="81f3d-388">We fixed an issue where inserting or updating an Index in a document containing more than a hundred entries would result in the application crashing.</span></span>
- <span data-ttu-id="81f3d-389">我們已修正具有自訂 xml 值的檔案在開啟時速度極度緩慢的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-389">We fixed an issue where files with custom xml values opened extremely slowly.</span></span>

### <a name="office-suite"></a><span data-ttu-id="81f3d-390">Office 套件</span><span class="sxs-lookup"><span data-stu-id="81f3d-390">Office Suite</span></span>
- <span data-ttu-id="81f3d-391">我們已修正 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。</span><span class="sxs-lookup"><span data-stu-id="81f3d-391">We fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-may-08"></a><span data-ttu-id="81f3d-394">版本 2006：5 月 8 日</span><span class="sxs-lookup"><span data-stu-id="81f3d-394">Version 2006: May 08</span></span>
<span data-ttu-id="81f3d-395">*版本 2006 (組建 12829.20000)*</span><span class="sxs-lookup"><span data-stu-id="81f3d-395">*Version 2006 (Build 12829.20000)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="81f3d-397">功能更新</span><span class="sxs-lookup"><span data-stu-id="81f3d-397">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="81f3d-398">Excel</span><span class="sxs-lookup"><span data-stu-id="81f3d-398">Excel</span></span>

- <span data-ttu-id="81f3d-399">**使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦。</span><span class="sxs-lookup"><span data-stu-id="81f3d-399">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="outlook"></a><span data-ttu-id="81f3d-400">Outlook</span><span class="sxs-lookup"><span data-stu-id="81f3d-400">Outlook</span></span>

- <span data-ttu-id="81f3d-401">**更好的結果—瞬間：** 我們更新了搜尋體驗，讓這個版本比以往更聰明、更快速，且更可靠。</span><span class="sxs-lookup"><span data-stu-id="81f3d-401">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="81f3d-402">深入了解</span><span class="sxs-lookup"><span data-stu-id="81f3d-402">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="81f3d-403">**使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦。</span><span class="sxs-lookup"><span data-stu-id="81f3d-403">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="81f3d-404">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="81f3d-404">PowerPoint</span></span>

- <span data-ttu-id="81f3d-405">**使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦。</span><span class="sxs-lookup"><span data-stu-id="81f3d-405">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span> [<span data-ttu-id="81f3d-406">深入了解</span><span class="sxs-lookup"><span data-stu-id="81f3d-406">Learn more</span></span>](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a><span data-ttu-id="81f3d-407">Word</span><span class="sxs-lookup"><span data-stu-id="81f3d-407">Word</span></span>

- <span data-ttu-id="81f3d-408">**使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦。</span><span class="sxs-lookup"><span data-stu-id="81f3d-408">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="81f3d-411">解決的問題</span><span class="sxs-lookup"><span data-stu-id="81f3d-411">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="81f3d-412">Office 套件</span><span class="sxs-lookup"><span data-stu-id="81f3d-412">Office Suite</span></span>

- <span data-ttu-id="81f3d-413">我們已經研究並解決了在作業系統關閉後，透過 InTune 進行的 Office 365 專業增強版部署會暫停的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-413">We have investigated and resolved the issue where an Office 365 ProPlus deployment via InTune is paused after an OS shutdown.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-may-01"></a><span data-ttu-id="81f3d-415">版本 2005：5 月 1 日</span><span class="sxs-lookup"><span data-stu-id="81f3d-415">Version 2005: May 01</span></span>
<span data-ttu-id="81f3d-416">*版本 2005 (組建 12827.20030)*</span><span class="sxs-lookup"><span data-stu-id="81f3d-416">*Version 2005 (Build 12827.20030)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="81f3d-418">功能更新</span><span class="sxs-lookup"><span data-stu-id="81f3d-418">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="81f3d-419">Outlook</span><span class="sxs-lookup"><span data-stu-id="81f3d-419">Outlook</span></span>

- <span data-ttu-id="81f3d-420">**電子郵件中的改良連結：** 當您包含檔案的連結時，檔案名會取代 URL。</span><span class="sxs-lookup"><span data-stu-id="81f3d-420">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="81f3d-421">您可以變更權限，讓所有收件者都能存取。</span><span class="sxs-lookup"><span data-stu-id="81f3d-421">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="81f3d-422">深入了解</span><span class="sxs-lookup"><span data-stu-id="81f3d-422">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="81f3d-425">解決的問題</span><span class="sxs-lookup"><span data-stu-id="81f3d-425">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="81f3d-426">Excel</span><span class="sxs-lookup"><span data-stu-id="81f3d-426">Excel</span></span>

- <span data-ttu-id="81f3d-427">修正圖表資料表無法正確呈現日期座標軸中的值的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-427">Fixed an issue where chart data table could render values in a date axis incorrectly.</span></span>
- <span data-ttu-id="81f3d-428">修正使用 [頁面配置] 或 [分頁預覽] 之後無法停用分頁符號的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-428">Fixed an issue where page breaks could not be disabled after going into Page Layout or Page Break Preview.</span></span>
- <span data-ttu-id="81f3d-429">修正隱藏和取消隱藏具有系列資料的欄之後，圖表線條樣式可能會遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-429">Fixed an issue where chart line styles could be lost after hiding and unhiding columns with series data.</span></span>
- <span data-ttu-id="81f3d-430">在已篩選清單中插入欄的時間會比預期更長。</span><span class="sxs-lookup"><span data-stu-id="81f3d-430">Inserting a column in a filtered list would take longer than expected.</span></span>
- <span data-ttu-id="81f3d-431">當您使用舊版的「共用活頁簿」模式，嘗試為活頁簿的新工作表列出變更時，就會發生當機。</span><span class="sxs-lookup"><span data-stu-id="81f3d-431">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>
- <span data-ttu-id="81f3d-432">修正啟用 [負值以補色顯示] 選項後，可能無法儲存樞紐分析表中的自訂格式設定的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-432">Fixed the issue where custom formatting in Pivot charts may not be saved when the "Invert if negative" option was enabled.</span></span>
- <span data-ttu-id="81f3d-433">修正如果選取 [負值以補色顯示] 選項，可能無法儲存樞紐分析表中單一資料點的自訂格式設定的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-433">Fixed an issue where custom formatting for a single data point in a Pivot chart was not saved if the "Invert if negative" option was selected.</span></span>
- <span data-ttu-id="81f3d-434">這項變更修正在 CSV 檔案中上傳 '@' 字元時，會導致將 '@' 字元之後的字串轉換成公式的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-434">This change fixes an issue where the '@' character uploaded in a CSV file, would result in the string after the '@' character to be converted to a formula.</span></span>
- <span data-ttu-id="81f3d-435">修正無法正確捨入 SEQUENCE 函數中十進位值的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-435">Fixed an issue where decimal values in the SEQUENCE function were not rounded correctly.</span></span>

### <a name="outlook"></a><span data-ttu-id="81f3d-436">Outlook</span><span class="sxs-lookup"><span data-stu-id="81f3d-436">Outlook</span></span>

- <span data-ttu-id="81f3d-437">解決導致使用者在 Outlook 桌面用戶端中按一下非常長的安全連結時，由於截斷而無法載入的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-437">Addresses an issue that caused very long safelinks that users clicked on in the Outlook Desktop client to fail to load due to truncation.</span></span>
- <span data-ttu-id="81f3d-438">修正當與伺服器同步處理時，名稱中包含 DBCS (雙位元組字元集) 字元的 Outlook 資料夾會間斷消失的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-438">Fixed an issue where Outlook folders with names containing DBCS (Double Byte Character Set) characters would intermittently disappear when synchronizing with the server.</span></span> <span data-ttu-id="81f3d-439">為此，必須為 Outlook 設定 IMAP 帳戶，並在地區設定設定為日文的系統上執行。</span><span class="sxs-lookup"><span data-stu-id="81f3d-439">For this to happen, Outlook had to be configured with an IMAP account and running on a system with the locale set to Japanese.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="81f3d-440">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="81f3d-440">PowerPoint</span></span>

- <span data-ttu-id="81f3d-441">已修正問題：如果使用者建立了註解，但未張貼就關閉 [註解] 窗格，然後開啟新視窗、瀏覽多張投影片並關閉視窗，最後再開啟原始簡報中的 [註解] 窗格，將導致無法使用草稿註解。</span><span class="sxs-lookup"><span data-stu-id="81f3d-441">Fixed an issue where if a user created a comment without posting it and closed the Comments pane, then opened a new window, navigated through multiple slides and, closed the window, and finally re-opened the Comments pane in the original presentation, the draft comments would not be available.</span></span>

### <a name="project"></a><span data-ttu-id="81f3d-442">Project</span><span class="sxs-lookup"><span data-stu-id="81f3d-442">Project</span></span>

- <span data-ttu-id="81f3d-443">修正問題：如果 Project 連線至 Project Web App，且小數分隔符號是逗號，當新增延遲時，TaskDependencies Add 方法會失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-443">Fixed an issue where if Project is connected to the Project Web App and the decimal separator is a comma, TaskDependencies Add method fails when Lag is added.</span></span>

### <a name="word"></a><span data-ttu-id="81f3d-444">Word</span><span class="sxs-lookup"><span data-stu-id="81f3d-444">Word</span></span>

- <span data-ttu-id="81f3d-445">修正在 [共同作業] 模式時，在文件中插入註解並不總是成功的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-445">Fixed an issue where inserting comments on a document in collaboration mode would not always work.</span></span>
- <span data-ttu-id="81f3d-446">此變更修正在按一下 @ 提及時，[人員卡片] 會閃動的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-446">This change fixes an issue where the People card would flash if the @ mention was clicked.</span></span>
- <span data-ttu-id="81f3d-447">修正問題：關閉具有草稿註解的文件時，會在不儲存草稿註解的情況下，提示使用者是否要關閉文件。</span><span class="sxs-lookup"><span data-stu-id="81f3d-447">Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments.</span></span> <span data-ttu-id="81f3d-448">取消提示會關閉文件，而不是保持文件開啟。</span><span class="sxs-lookup"><span data-stu-id="81f3d-448">Cancelling the prompt would close the document rather than leaving it open.</span></span>
- <span data-ttu-id="81f3d-449">修正翻譯已張貼註解將導致「插入已翻譯的文字失敗」錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-449">Fixed an issue where translating a posted comment would result in the error "Inserting translated text failed".</span></span>
- <span data-ttu-id="81f3d-450">在 Web 檢視/沉浸式閱讀器中，如果已在檢視中，按一下提示會捲動到最上方。</span><span class="sxs-lookup"><span data-stu-id="81f3d-450">In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view.</span></span> <span data-ttu-id="81f3d-451">已修正這個問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-451">This has been fixed.</span></span>
- <span data-ttu-id="81f3d-452">我們已修正一個問題，當嘗試使用新名稱儲存包含巨集的檔案時，無論使用者輸入什麼名稱，都會導致該檔案以.docx 副檔名和檔案名稱 WRO0004.docx 儲存，進而導致文件無法使用。</span><span class="sxs-lookup"><span data-stu-id="81f3d-452">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with .docx extension and the filename WRO0004.docx, regardless of what the user entered, rendering the document unusable.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


## <a name="version-2005-april-24"></a><span data-ttu-id="81f3d-454">版本 2005：4 月 24 日</span><span class="sxs-lookup"><span data-stu-id="81f3d-454">Version 2005: April 24</span></span>
<span data-ttu-id="81f3d-455">版本 2005 (組建 12816.20006)\*\*</span><span class="sxs-lookup"><span data-stu-id="81f3d-455">*Version 2005 (Build 12816.20006)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="81f3d-457">解決的問題</span><span class="sxs-lookup"><span data-stu-id="81f3d-457">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="81f3d-458">Excel</span><span class="sxs-lookup"><span data-stu-id="81f3d-458">Excel</span></span>
- <span data-ttu-id="81f3d-459">這項變更修正了即使 LINEST 函式傳回正確的值，圖表趨勢線的 R 平方值 (在強制 y 截距的情況下) 仍然不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-459">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>
- <span data-ttu-id="81f3d-460">此變更修正了自訂圖表趨勢線格式不一定會儲存的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-460">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

### <a name="outlook"></a><span data-ttu-id="81f3d-461">Outlook</span><span class="sxs-lookup"><span data-stu-id="81f3d-461">Outlook</span></span>
- <span data-ttu-id="81f3d-462">修正了 Office 功能區中群組行事曆分類按鈕已停用的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-462">Fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>
- <span data-ttu-id="81f3d-463">修正了企業客戶沒有執行或無法使用群組資料夾的問題，該問題會導致 Outlook 顯示「沒有回應」的訊息。</span><span class="sxs-lookup"><span data-stu-id="81f3d-463">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="81f3d-464">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="81f3d-464">PowerPoint</span></span>
- <span data-ttu-id="81f3d-465">修正了將滑鼠游標移到星號 (\*) 符號，但不會顯示上一次更新文件的日期和使用者姓名。</span><span class="sxs-lookup"><span data-stu-id="81f3d-465">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="word"></a><span data-ttu-id="81f3d-466">Word</span><span class="sxs-lookup"><span data-stu-id="81f3d-466">Word</span></span>
- <span data-ttu-id="81f3d-467">啟用「顯示書簽」選項卻不會顯示書簽。</span><span class="sxs-lookup"><span data-stu-id="81f3d-467">Enabling the option "Show bookmarks" would not display bookmarks.</span></span> <span data-ttu-id="81f3d-468">已修正這個問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-468">This has been fixed.</span></span>
- <span data-ttu-id="81f3d-469">此變更修正了下列問題：如果已啟用 [顯示功能變數代碼，而非其值] 選項，則含有超連結的文字可能不會顯示。</span><span class="sxs-lookup"><span data-stu-id="81f3d-469">This change fixes an issue where text with hyperlinks may not display if the option "Show field codes instead of their values" was enabled.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


## <a name="version-2005-april-17"></a><span data-ttu-id="81f3d-471">版本 2005：4 月 17 日</span><span class="sxs-lookup"><span data-stu-id="81f3d-471">Version 2005: April 17</span></span>
<span data-ttu-id="81f3d-472">*版本 2005 (組建 12810.20002)*</span><span class="sxs-lookup"><span data-stu-id="81f3d-472">*Version 2005 (Build 12810.20002)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="81f3d-474">解決的問題</span><span class="sxs-lookup"><span data-stu-id="81f3d-474">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="81f3d-475">Excel</span><span class="sxs-lookup"><span data-stu-id="81f3d-475">Excel</span></span>
- <span data-ttu-id="81f3d-476">已增加搭配圖表使用的 [自訂誤差線] 對話方塊上儲存格參照 [編輯] 控制項的大小。</span><span class="sxs-lookup"><span data-stu-id="81f3d-476">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>
- <span data-ttu-id="81f3d-477">在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。</span><span class="sxs-lookup"><span data-stu-id="81f3d-477">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>
- <span data-ttu-id="81f3d-478">修正列印時表單控制項的核取方塊縮放問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-478">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>
- <span data-ttu-id="81f3d-479">在某些情況下，Application.Evaluate (VBA) 無法在使用者定義的函數中運作。</span><span class="sxs-lookup"><span data-stu-id="81f3d-479">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>
- <span data-ttu-id="81f3d-480">此變更會修正設定格式化的條件 (CF) 資訊無法正確儲存到 XLSB 檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-480">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="81f3d-481">OneNote</span><span class="sxs-lookup"><span data-stu-id="81f3d-481">OneNote</span></span>
- <span data-ttu-id="81f3d-482">修正將分行符號儲存為垂直 Tab 的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-482">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="81f3d-483">Outlook</span><span class="sxs-lookup"><span data-stu-id="81f3d-483">Outlook</span></span>
- <span data-ttu-id="81f3d-484">解決會導致使用者無法將個人連絡人群組新增為會議出席者的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-484">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>
- <span data-ttu-id="81f3d-485">解決會導致還有 2 個月時間的會議，無法在排程小幫手中顯示會議主題的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-485">Addresses an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>
- <span data-ttu-id="81f3d-486">解決會導致使用者在轉寄大型 HTML 郵件時看到郵件內文截斷的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-486">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>
- <span data-ttu-id="81f3d-487">新增透過群組原則強制執行 S/MIME 預設登入設定的功能。</span><span class="sxs-lookup"><span data-stu-id="81f3d-487">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>
- <span data-ttu-id="81f3d-488">解決會導致為使用者主要信箱以外的信箱所建立的刪除規則變得無效的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-488">Addresses an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>
- <span data-ttu-id="81f3d-489">解決在轉寄加密郵件時導致捨棄附件的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-489">Addresses an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

### <a name="project"></a><span data-ttu-id="81f3d-490">Project</span><span class="sxs-lookup"><span data-stu-id="81f3d-490">Project</span></span>
- <span data-ttu-id="81f3d-491">在表單檢視中編輯前置/後續任務資料時，會觸發額外的 ProjectBeforeTaskChange 事件。</span><span class="sxs-lookup"><span data-stu-id="81f3d-491">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>
- <span data-ttu-id="81f3d-492">修正變更連結至 SharePoint 工作清單之專案的面板狀態欄位時，Project 可能當機的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-492">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>
- <span data-ttu-id="81f3d-493">修正儲存使用舊版 Project 建立的專案時，Project 可能當機的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-493">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


## <a name="version-2004-april-10"></a><span data-ttu-id="81f3d-495">版本 2004：4 月 10 日</span><span class="sxs-lookup"><span data-stu-id="81f3d-495">Version 2004: April 10</span></span>
<span data-ttu-id="81f3d-496">*版本 2004 (組建 12730.20024)*</span><span class="sxs-lookup"><span data-stu-id="81f3d-496">*Version 2004 (Build 12730.20024)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="81f3d-498">功能更新</span><span class="sxs-lookup"><span data-stu-id="81f3d-498">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="81f3d-499">Access</span><span class="sxs-lookup"><span data-stu-id="81f3d-499">Access</span></span>

- <span data-ttu-id="81f3d-500">**略過 [顯示資料表] 對話方塊，直接移至工作窗格，以及將資料表新增至關係和查詢的程序簡化：** 只要按一下四個索引標籤、將名稱多重選取、依文字搜尋，並從在您工作時維持開啟的工作窗格拖曳，即可新增資料表和查詢。</span><span class="sxs-lookup"><span data-stu-id="81f3d-500">**Bypass the Show Table dialog box, go directly to a task pane, and streamline adding tables to relationships and queries.:** Add tables and queries by clicking four tabs, multi-selecting names, searching by text, and dragging from a task pane that stays open while you work.</span></span>

### <a name="excel"></a><span data-ttu-id="81f3d-501">Excel</span><span class="sxs-lookup"><span data-stu-id="81f3d-501">Excel</span></span>

- <span data-ttu-id="81f3d-502">**M365 進階版內容選擇器：** 讓您的文件栩栩如生！</span><span class="sxs-lookup"><span data-stu-id="81f3d-502">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="81f3d-503">探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="81f3d-503">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="81f3d-504">Outlook</span><span class="sxs-lookup"><span data-stu-id="81f3d-504">Outlook</span></span>

- <span data-ttu-id="81f3d-505">**M365 進階版內容選擇器：** 讓您的文件栩栩如生！</span><span class="sxs-lookup"><span data-stu-id="81f3d-505">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="81f3d-506">探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="81f3d-506">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="81f3d-507">**將圖片作為電子郵件的一部分傳送時，讓圖片保持高畫質：** 一個新 Outlook 設定，可讓您在隨著電子郵件內容傳送圖片時限制圖片壓縮</span><span class="sxs-lookup"><span data-stu-id="81f3d-507">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>

### <a name="powerpoint"></a><span data-ttu-id="81f3d-508">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="81f3d-508">PowerPoint</span></span>

- <span data-ttu-id="81f3d-509">**M365 進階版內容選擇器：** 讓您的文件栩栩如生！</span><span class="sxs-lookup"><span data-stu-id="81f3d-509">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="81f3d-510">探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="81f3d-510">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="81f3d-511">**在簡報時同步處理變更：** 即使簡報處於投影片放映模式，仍可即時同步處理所做的變更。</span><span class="sxs-lookup"><span data-stu-id="81f3d-511">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="81f3d-512">Word</span><span class="sxs-lookup"><span data-stu-id="81f3d-512">Word</span></span>

- <span data-ttu-id="81f3d-513">**M365 進階版內容選擇器：** 讓您的文件栩栩如生！</span><span class="sxs-lookup"><span data-stu-id="81f3d-513">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="81f3d-514">探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="81f3d-514">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="81f3d-515">**標註私人複本：** 製作共用文件的私人複本，以建立只有您本人能夠看到的手寫筆記。</span><span class="sxs-lookup"><span data-stu-id="81f3d-515">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="81f3d-516">若要開始使用，請移至 [檢視] > [建立私人複本]。</span><span class="sxs-lookup"><span data-stu-id="81f3d-516">Go to View > Create a Private Copy to get started.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="81f3d-519">解決的問題</span><span class="sxs-lookup"><span data-stu-id="81f3d-519">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="81f3d-520">Access</span><span class="sxs-lookup"><span data-stu-id="81f3d-520">Access</span></span>

- <span data-ttu-id="81f3d-521">修正工作窗格中表格的重新調整及重新整理問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-521">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

### <a name="excel"></a><span data-ttu-id="81f3d-522">Excel</span><span class="sxs-lookup"><span data-stu-id="81f3d-522">Excel</span></span>

- <span data-ttu-id="81f3d-523">修正在工作表上選取儲存格範圍會導致只選取單一儲存格的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-523">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="81f3d-524">修正在為含有 X 軸範圍的圖表縮減大小時，可能會導致 Excel 停止回應的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-524">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="81f3d-525">修正插入使用者定義的圖表範本來作為預設值會導致其儲存為直條圖的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-525">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="81f3d-526">修正當基礎資料儲存格沒有標題時，圖表上的資料標籤會以空白顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-526">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="81f3d-527">修正已啟用 R1C1 儲存格參照且正在共同撰寫/共用的 Excel 工作表，在將游標移到 [使用者目前狀態] 圖示上方時不會以 R1C1 模式顯示作用中儲存格的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-527">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="81f3d-528">Outlook</span><span class="sxs-lookup"><span data-stu-id="81f3d-528">Outlook</span></span>

- <span data-ttu-id="81f3d-529">解決會導致類別有時候會從電子郵件訊息中消失的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-529">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="81f3d-530">解決會導致代理人在不同機器上所看到的共用信箱有不同資料夾階層的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-530">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="81f3d-531">解決在嘗試檢視組織表單的屬性時，會導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-531">Addresses an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="81f3d-532">解決在變更機器上的時區時，會導致某些提醒無法觸發的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-532">Addresses an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="81f3d-533">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="81f3d-533">PowerPoint</span></span>

- <span data-ttu-id="81f3d-534">此變更修正了在 PowerPoint 或 Word 中呈現內嵌為 OLE 物件的舊版 Excel 圖表時可能不會永遠顯示圖表標題的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-534">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="81f3d-535">我們已修正將文字從 Excel 複製到 PowerPoint 時可能會導致其格式設定發生變更的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-535">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="81f3d-536">此變更修正了使用 [全字拼寫須相符] 來尋找特殊字元時，不一定能正常運作的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-536">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="81f3d-537">Project</span><span class="sxs-lookup"><span data-stu-id="81f3d-537">Project</span></span>

- <span data-ttu-id="81f3d-538">修正了當開啟保護實際工作的設定時，使用者無法輸入分時期基準工時的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-538">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="81f3d-539">Word</span><span class="sxs-lookup"><span data-stu-id="81f3d-539">Word</span></span>

- <span data-ttu-id="81f3d-540">此變更修正了將游標暫留在提示上不會醒目提示其卡片的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-540">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="81f3d-541">此變更修正了使用套索選取工具時，群組圖形中的文字會暫時消失的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-541">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="81f3d-542">此變更修正了在 PowerPoint 或 Word 中呈現內嵌為 OLE 物件的舊版 Excel 圖表時可能不會永遠顯示圖表標題的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-542">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="81f3d-543">此變更修正了在雙頁檢視中建立註解時，註解錨點不一定會顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-543">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="81f3d-544">修正如果段落的樣式是連結至清單的樣式上階，則該清單的編號可能會遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-544">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-march-27"></a><span data-ttu-id="81f3d-546">版本 2004：3 月 27 日</span><span class="sxs-lookup"><span data-stu-id="81f3d-546">Version 2004: March 27</span></span>
<span data-ttu-id="81f3d-547">*版本 2004 (組建 12718.20010)*</span><span class="sxs-lookup"><span data-stu-id="81f3d-547">*Version 2004 (Build 12718.20010)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="81f3d-549">功能更新</span><span class="sxs-lookup"><span data-stu-id="81f3d-549">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="81f3d-550">Outlook</span><span class="sxs-lookup"><span data-stu-id="81f3d-550">Outlook</span></span>

- <span data-ttu-id="81f3d-551">**在撰寫郵件時有新的選項可停用 @ 提及建議：** 您是否覺得 @ 提及的選擇器很煩人，一點都不好用？</span><span class="sxs-lookup"><span data-stu-id="81f3d-551">**New option to disable @ mention suggestions when composing mail:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="81f3d-552">現在您可以視需要將其關閉了。</span><span class="sxs-lookup"><span data-stu-id="81f3d-552">Now you can turn it off if you prefer.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="81f3d-555">解決的問題</span><span class="sxs-lookup"><span data-stu-id="81f3d-555">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="81f3d-556">Outlook</span><span class="sxs-lookup"><span data-stu-id="81f3d-556">Outlook</span></span>
- <span data-ttu-id="81f3d-557">解決了會讓 [附件工具] 中的 [儲存至雲端] 按鈕不見的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-557">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>
- <span data-ttu-id="81f3d-558">解決了以下問題：當使用者從檢查程式視窗回覆受到數位版權管理的郵件，卻沒有所回覆郵件的擁有者權限時，使用者會無法新增簽名。</span><span class="sxs-lookup"><span data-stu-id="81f3d-558">Addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>
- <span data-ttu-id="81f3d-559">解決了以下問題：使用者無法從網頁位置將其他附件新增到先前建立的會議。</span><span class="sxs-lookup"><span data-stu-id="81f3d-559">Addresses an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="81f3d-560">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="81f3d-560">PowerPoint</span></span>
- <span data-ttu-id="81f3d-561">此變更修正了會導致包含 emojis 的 PowerPoint 檔案在儲存時發生失敗的錯誤。</span><span class="sxs-lookup"><span data-stu-id="81f3d-561">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

### <a name="project"></a><span data-ttu-id="81f3d-562">Project</span><span class="sxs-lookup"><span data-stu-id="81f3d-562">Project</span></span>
- <span data-ttu-id="81f3d-563">修正了以下問題：如果執行 ' CustomFieldValueListGetItem' 且自訂欄位的查閱資料表不存在，系統會建立一個不應建立的空白查閱資料表。</span><span class="sxs-lookup"><span data-stu-id="81f3d-563">Fixed an issue where if 'CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

### <a name="word"></a><span data-ttu-id="81f3d-564">Word</span><span class="sxs-lookup"><span data-stu-id="81f3d-564">Word</span></span>
- <span data-ttu-id="81f3d-565">此變更修正了以下問題：從 [檢視] 功能表選取多個頁面時，其中的 [註解] 窗格會顯示為空白。</span><span class="sxs-lookup"><span data-stu-id="81f3d-565">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-march-20"></a><span data-ttu-id="81f3d-567">版本 2004：3 月 20 日</span><span class="sxs-lookup"><span data-stu-id="81f3d-567">Version 2004: March 20</span></span>
<span data-ttu-id="81f3d-568">*版本 2004 (組建 12711.20000)*</span><span class="sxs-lookup"><span data-stu-id="81f3d-568">*Version 2004 (Build 12711.20000)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="81f3d-570">功能更新</span><span class="sxs-lookup"><span data-stu-id="81f3d-570">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="81f3d-571">Outlook</span><span class="sxs-lookup"><span data-stu-id="81f3d-571">Outlook</span></span>

- <span data-ttu-id="81f3d-572">**行事曆新版視覺效果：** 去年，我們提供了全新的郵件體驗，而今年將為您帶來嶄新的行事曆！</span><span class="sxs-lookup"><span data-stu-id="81f3d-572">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar's turn to get a facelift!</span></span> <span data-ttu-id="81f3d-573">有幾項更新是新穎卻令人孰悉的，您是經驗豐富的 Outlook 使用者，可以立即使用並提高生產力。</span><span class="sxs-lookup"><span data-stu-id="81f3d-573">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

- <span data-ttu-id="81f3d-574">**協助保護群組中的資料：** 建立群組時所選擇的「敏感度」標籤會套用到群組電子郵件、文件及小組網站</span><span class="sxs-lookup"><span data-stu-id="81f3d-574">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites</span></span>

### <a name="powerpoint"></a><span data-ttu-id="81f3d-575">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="81f3d-575">PowerPoint</span></span>

- <span data-ttu-id="81f3d-576">**在投影片放映期間更新投影片：** 在簡報期間，更新由其他作者變更的投影片。</span><span class="sxs-lookup"><span data-stu-id="81f3d-576">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="81f3d-579">解決的問題</span><span class="sxs-lookup"><span data-stu-id="81f3d-579">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="81f3d-580">Excel</span><span class="sxs-lookup"><span data-stu-id="81f3d-580">Excel</span></span>

- <span data-ttu-id="81f3d-581">此變更解決了處理格式錯誤或無效通訊協定資訊影像時所導致的延遲問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-581">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="81f3d-582">Outlook</span><span class="sxs-lookup"><span data-stu-id="81f3d-582">Outlook</span></span>

- <span data-ttu-id="81f3d-583">此變更解決了處理格式錯誤或無效通訊協定資訊影像時所導致的延遲問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-583">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="81f3d-584">此變更修正了電子郵件草稿最新變更未更新的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-584">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="81f3d-585">已修正在檔案上按一下滑鼠右鍵並使用「傳送到」功能無法運作的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-585">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="81f3d-586">已修正如果使用者有自訂的 [通訊錄] 搜尋路徑，則 Outlook 的名稱解析範圍會限制為自訂路徑，而不是包括全域通訊清單 (GAL) 的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-586">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="81f3d-587">已修正在一組傳回的搜尋結果中，依類別結果排序不會顯示類別色彩的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-587">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

### <a name="project"></a><span data-ttu-id="81f3d-588">Project</span><span class="sxs-lookup"><span data-stu-id="81f3d-588">Project</span></span>

- <span data-ttu-id="81f3d-589">已修正當使用者按一下 [排程群組] 內 [工作] 功能區中的 [停用] 按鈕時，不會觸發 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) 事件的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-589">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the "Inactivate" button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="81f3d-590">如果您在 [表單類型] 檢視中設定前置任務或後置任務詳細資訊，則 ProjectBeforeTaskChange Visual Basic Applications (VBA) 事件不會一律擷取變更。</span><span class="sxs-lookup"><span data-stu-id="81f3d-590">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="81f3d-591">例如，如果刪除了某個相依性，並在表單上按一下 [確定]，則不會觸發該事件。</span><span class="sxs-lookup"><span data-stu-id="81f3d-591">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="81f3d-592">已修正此問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-592">This behavior has been fixed.</span></span>

- <span data-ttu-id="81f3d-593">已修正在進行變更 (例如日期變更) 之後，實際工作成本 (ACWP) 的最新值不會顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-593">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="81f3d-594">已修正使用「最近使用」(MRU) 功能表開啟專案時，會使用 [讀取/寫入] 存取權開啟專案的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-594">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="81f3d-595">這項變更修正了如果您建立包含開始日期和時間 (但無工期) 的手動工作，則時間表上的時間顯示不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-595">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="81f3d-596">已修正使用回曆列印時間表時，會導致列印檢視中略過或重複一個月的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-596">Fixed an issue where printing a timeline using Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="81f3d-597">這項變更解決了在團隊規劃中使用 GDI 物件時，可能導致 GDI 物件分配過多並產生記憶體不足的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-597">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

### <a name="word"></a><span data-ttu-id="81f3d-598">Word</span><span class="sxs-lookup"><span data-stu-id="81f3d-598">Word</span></span>

- <span data-ttu-id="81f3d-599">已修正張貼留言功能停用的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-599">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="81f3d-600">此變更解決了處理格式錯誤或無效通訊協定資訊影像時所導致的延遲問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-600">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="81f3d-601">這項變更解決了帳戶管理員不會分派訊息而導致協力廠商應用程式懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-601">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="81f3d-602">這項變更修正了目錄會使用文件中未包含的標題樣式進行更新的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-602">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="81f3d-603">已修正在寄送文件時，儲存在 Word 文件中的數位簽章會被刪除的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-603">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-march-13"></a><span data-ttu-id="81f3d-605">版本 2004：3 月 13 日</span><span class="sxs-lookup"><span data-stu-id="81f3d-605">Version 2004: March 13</span></span>
<span data-ttu-id="81f3d-606">*版本 2004 (組建 12703.20010)*</span><span class="sxs-lookup"><span data-stu-id="81f3d-606">*Version 2004 (Build 12703.20010)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="81f3d-608">功能更新</span><span class="sxs-lookup"><span data-stu-id="81f3d-608">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="81f3d-609">Excel</span><span class="sxs-lookup"><span data-stu-id="81f3d-609">Excel</span></span>
- <span data-ttu-id="81f3d-610">**敏感度標籤**：您現在可以套用組織設定、用來提示您輸入自訂權限的敏感度標籤。</span><span class="sxs-lookup"><span data-stu-id="81f3d-610">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="81f3d-611">深入了解</span><span class="sxs-lookup"><span data-stu-id="81f3d-611">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a><span data-ttu-id="81f3d-612">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="81f3d-612">PowerPoint</span></span>
- <span data-ttu-id="81f3d-613">**敏感度標籤**：您現在可以套用組織設定、用來提示您輸入自訂權限的敏感度標籤。</span><span class="sxs-lookup"><span data-stu-id="81f3d-613">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="81f3d-614">深入了解</span><span class="sxs-lookup"><span data-stu-id="81f3d-614">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a><span data-ttu-id="81f3d-615">Word</span><span class="sxs-lookup"><span data-stu-id="81f3d-615">Word</span></span>
- <span data-ttu-id="81f3d-616">**敏感度標籤**：您現在可以套用組織設定、用來提示您輸入自訂權限的敏感度標籤。</span><span class="sxs-lookup"><span data-stu-id="81f3d-616">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="81f3d-617">深入了解</span><span class="sxs-lookup"><span data-stu-id="81f3d-617">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="81f3d-620">解決的問題</span><span class="sxs-lookup"><span data-stu-id="81f3d-620">Resolved issues</span></span>

### <a name="access"></a><span data-ttu-id="81f3d-621">Access</span><span class="sxs-lookup"><span data-stu-id="81f3d-621">Access</span></span>
- <span data-ttu-id="81f3d-622">修正國際版 Access 在使用者介面中顯示英文字串的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-622">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="81f3d-623">Excel</span><span class="sxs-lookup"><span data-stu-id="81f3d-623">Excel</span></span>
- <span data-ttu-id="81f3d-624">修正使用者在以程式設計方式編輯大量儲存格範圍時可能遇到的效能問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-624">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>
- <span data-ttu-id="81f3d-625">修正以日文環境開啟 CSV 檔案時發生的效能問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-625">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

### <a name="outlook"></a><span data-ttu-id="81f3d-626">Outlook</span><span class="sxs-lookup"><span data-stu-id="81f3d-626">Outlook</span></span>
- <span data-ttu-id="81f3d-627">解決將附件新增至郵件或從郵件拖放 (與透過功能表相對) 來儲存附件時，導致檔案的「上次修改」日期更新的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-627">Addresses an issue that caused the "Last Modified"; date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>
- <span data-ttu-id="81f3d-628">解決會導致在展開的尋找窗格中按一下 Enter 時無法開始搜尋，而是會要求使用者按一下 [搜尋] 按鈕的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-628">Addresses an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>
- <span data-ttu-id="81f3d-629">修正將 [如果有，顯示使用者的照片] 選項停用時，搜尋不會顯示有關使用者的任何資訊的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-629">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>

### <a name="project"></a><span data-ttu-id="81f3d-630">Project</span><span class="sxs-lookup"><span data-stu-id="81f3d-630">Project</span></span>
- <span data-ttu-id="81f3d-631">修正無法正確計算摘要工作日期的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-631">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>
- <span data-ttu-id="81f3d-632">修正不先執行 OpenUndoTransaction 方法就不能觸發 OnUndoOrRedo 事件的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-632">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="81f3d-633">Word</span><span class="sxs-lookup"><span data-stu-id="81f3d-633">Word</span></span>
- <span data-ttu-id="81f3d-634">修正輸入或編輯備註然後使用 Ctrl+A 時，會導致選取畫布中的文字，而不只是選取備註卡片內文字的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-634">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>
- <span data-ttu-id="81f3d-635">我們已修正文件中的文字對齊，在使用 [快速列印] 進行列印之後嘗試進行編輯時變得混亂的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-635">We fixed an issue in which the alignment of words in a document gets scrambled when tried to edit after printing using Quick Print.</span></span>
- <span data-ttu-id="81f3d-636">我們已修正將兩份文件合併成一份文件時的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-636">We fixed an issue when merging two documents into one document.</span></span>
- <span data-ttu-id="81f3d-637">修正標示的修訂若與方程式有關，在儲存檔案時可能會導致失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-637">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-march-06"></a><span data-ttu-id="81f3d-639">版本 2003：3 月 6 日</span><span class="sxs-lookup"><span data-stu-id="81f3d-639">Version 2003: March 06</span></span>
<span data-ttu-id="81f3d-640">*版本 2003 (組建 12624.20086)*</span><span class="sxs-lookup"><span data-stu-id="81f3d-640">*Version 2003 (Build 12624.20086)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="81f3d-642">解決的問題</span><span class="sxs-lookup"><span data-stu-id="81f3d-642">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="81f3d-643">Outlook</span><span class="sxs-lookup"><span data-stu-id="81f3d-643">Outlook</span></span>

- <span data-ttu-id="81f3d-644">修正使用 Outlook Web Access 建立規則時不會保存到 Exchange 伺服器，並導致衝突的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-644">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>
- <span data-ttu-id="81f3d-645">修正 Outlook 在深色模式中不會在 [寄件者:] 欄位中顯示下拉式清單的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-645">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>
- <span data-ttu-id="81f3d-646">解決在其他應用程式中開啟某個檔案時，導致使用者無法透過檔案總管將該檔案附加至郵件訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-646">Addresses an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="81f3d-647">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="81f3d-647">PowerPoint</span></span>

- <span data-ttu-id="81f3d-648">修正將滑鼠移至縮圖上時，建議的縮圖閃動的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-648">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="81f3d-649">在某些情況下，這可能會導致 PowerPoint 當機。</span><span class="sxs-lookup"><span data-stu-id="81f3d-649">In some cases this could cause PowerPoint to crash.</span></span>

### <a name="word"></a><span data-ttu-id="81f3d-650">Word</span><span class="sxs-lookup"><span data-stu-id="81f3d-650">Word</span></span>

- <span data-ttu-id="81f3d-651">修正受保護無法編輯之文件的比較功能問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-651">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

### <a name="office-suite"></a><span data-ttu-id="81f3d-652">Office 套件</span><span class="sxs-lookup"><span data-stu-id="81f3d-652">Office Suite</span></span>

- <span data-ttu-id="81f3d-653">修正 Word/Excel/PowerPoint 中的使用者主體名稱 (UPN) 不再區分大小寫，導致在 SharePoint 上使用檔案時較少發生失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-653">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="81f3d-654">修正 [檔案]\[選項] 對話方塊上的 [確定] 按鈕顯示為灰色停用狀態，但功能並未受影響的外觀問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-654">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog was being displayed as grayed out but functionality was not impacted.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

## <a name="version-2003-february-28"></a><span data-ttu-id="81f3d-657">版本 2003：2 月 28 日</span><span class="sxs-lookup"><span data-stu-id="81f3d-657">Version 2003: February 28</span></span>
<span data-ttu-id="81f3d-658">*版本 2003 (組建 12619.20002)*</span><span class="sxs-lookup"><span data-stu-id="81f3d-658">*Version 2003 (Build 12619.20002)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="81f3d-660">功能更新</span><span class="sxs-lookup"><span data-stu-id="81f3d-660">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="81f3d-661">Outlook</span><span class="sxs-lookup"><span data-stu-id="81f3d-661">Outlook</span></span>

- <span data-ttu-id="81f3d-662">**IT 系統管理員的事件通知：** Microsoft 365 租用戶全域系統管理員和 Office 應用程式系統會在 Windows 版 Outlook 的新右側面板中收到影響其使用者的 Outlook 和 O365 Exchange 事件通知。</span><span class="sxs-lookup"><span data-stu-id="81f3d-662">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="81f3d-663">深入了解</span><span class="sxs-lookup"><span data-stu-id="81f3d-663">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

### <a name="powerpoint"></a><span data-ttu-id="81f3d-664">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="81f3d-664">PowerPoint</span></span>

- <span data-ttu-id="81f3d-665">**改善筆跡轉換圖形圖表製作體驗：** 繪製更完善的圖表，並將它轉換成您可處理的 Office 物件。[深入了解](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span><span class="sxs-lookup"><span data-stu-id="81f3d-665">**Improved ink to shape diagramming experience:** Draw better diagrams and have it convert so office object you can manipulate [Learn more](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="81f3d-668">解決的問題</span><span class="sxs-lookup"><span data-stu-id="81f3d-668">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="81f3d-669">Excel</span><span class="sxs-lookup"><span data-stu-id="81f3d-669">Excel</span></span>

- <span data-ttu-id="81f3d-670">已修正交叉分析篩選器中的文字在預覽列印中無法正確縮放的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-670">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

### <a name="outlook"></a><span data-ttu-id="81f3d-671">Outlook</span><span class="sxs-lookup"><span data-stu-id="81f3d-671">Outlook</span></span>

- <span data-ttu-id="81f3d-672">解決將附件新增至郵件或從郵件拖放 (與透過功能表相對) 來儲存附件時，導致檔案的「上次修改」日期更新的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-672">Addresses an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

### <a name="word"></a><span data-ttu-id="81f3d-673">Word</span><span class="sxs-lookup"><span data-stu-id="81f3d-673">Word</span></span>

- <span data-ttu-id="81f3d-674">修正按 Tab 鍵導覽註解卡片時，註解編輯方塊上的焦點無法顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-674">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="81f3d-675">在方程式中插入控制項 (例如文字內容控制項)，然後儲存再開啟檔案，便會導致內容無法讀取的錯誤。</span><span class="sxs-lookup"><span data-stu-id="81f3d-675">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="81f3d-676">修正將先前使用密碼保護的檔案儲存到雲端儲存空間無法運作的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-676">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

### <a name="office-suite"></a><span data-ttu-id="81f3d-677">Office 套件</span><span class="sxs-lookup"><span data-stu-id="81f3d-677">Office Suite</span></span>

- <span data-ttu-id="81f3d-678">修正在 Word/Excel/PowerPoint 中開啟來自相同 SharePoint 文件庫的多個文件時，僅掃描開啟的第一個文件是否符合原則的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-678">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-february-21"></a><span data-ttu-id="81f3d-680">版本 2003：2 月 21 日</span><span class="sxs-lookup"><span data-stu-id="81f3d-680">Version 2003: February 21</span></span>
<span data-ttu-id="81f3d-681">*版本 2003 (組建 12615.20000)*</span><span class="sxs-lookup"><span data-stu-id="81f3d-681">*Version 2003 (Build 12615.20000)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="81f3d-683">功能更新</span><span class="sxs-lookup"><span data-stu-id="81f3d-683">Feature updates</span></span>
### <a name="office-suite"></a><span data-ttu-id="81f3d-684">Office 套件</span><span class="sxs-lookup"><span data-stu-id="81f3d-684">Office Suite</span></span>

- <span data-ttu-id="81f3d-685">**挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。</span><span class="sxs-lookup"><span data-stu-id="81f3d-685">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="81f3d-688">解決的問題</span><span class="sxs-lookup"><span data-stu-id="81f3d-688">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="81f3d-689">Excel</span><span class="sxs-lookup"><span data-stu-id="81f3d-689">Excel</span></span>
- <span data-ttu-id="81f3d-690">已修正使用者在重新命名樞紐分析表度量值時可能遇到的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-690">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>
- <span data-ttu-id="81f3d-691">已修正使用者在使用 VBA 巨集清除範圍內容時可能遇到的效能問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-691">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>
- <span data-ttu-id="81f3d-692">已修正當使用者執行與功能區互動的巨集時，導致 UI 快閃的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-692">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>
- <span data-ttu-id="81f3d-693">已修正當檔案中的第一個字為 TABLE 時，CSV 檔案載入錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-693">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>
- <span data-ttu-id="81f3d-694">已修正當您在兩個具有不同縮放比例的活頁簿之間切換時，使用者可能遇到的當機問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-694">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

### <a name="outlook"></a><span data-ttu-id="81f3d-695">Outlook</span><span class="sxs-lookup"><span data-stu-id="81f3d-695">Outlook</span></span>
- <span data-ttu-id="81f3d-696">已解決當持續整夜執行 Outlook 時，導致使用者無法開啟公用資料夾訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-696">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>
- <span data-ttu-id="81f3d-697">已修正在新增 Gmail 帳戶的驗證工作流程中，[權限] 頁面上的 [允許] 和 [拒絕] 按鈕停用的爭用情況。</span><span class="sxs-lookup"><span data-stu-id="81f3d-697">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>
- <span data-ttu-id="81f3d-698">已解決即使已關閉記錄，在某些情況下仍導致 Outlook 異常產生記錄輸出的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-698">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

### <a name="word"></a><span data-ttu-id="81f3d-699">Word</span><span class="sxs-lookup"><span data-stu-id="81f3d-699">Word</span></span>
- <span data-ttu-id="81f3d-700">已修正當滑鼠指標暫留在註解卡片上方時，未醒目提示註解卡片的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-700">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>
- <span data-ttu-id="81f3d-701">在使用中的文件共同撰寫工作階段中，直接在註解卡片中新增影像可能會導致新增標籤。</span><span class="sxs-lookup"><span data-stu-id="81f3d-701">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="81f3d-702">我們已修正此問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-702">This issue has been fixed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="81f3d-703">Office 套件</span><span class="sxs-lookup"><span data-stu-id="81f3d-703">Office Suite</span></span>
- <span data-ttu-id="81f3d-704">當您將 Multichoice/Lookup/Managed-metadata 屬性與 Word/Excel/PowerPoint 文件一起使用並儲存至 SharePoint 文件庫時，這些屬性之前限制為 255 個字元。</span><span class="sxs-lookup"><span data-stu-id="81f3d-704">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="81f3d-705">當這些屬性超過 255 個字元時，這類文件就無法儲存。</span><span class="sxs-lookup"><span data-stu-id="81f3d-705">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="81f3d-706">在此變更中，此限制已增加到 2048 個字元。</span><span class="sxs-lookup"><span data-stu-id="81f3d-706">With this change, this limit has been increased to 2048 characters.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-february-14"></a><span data-ttu-id="81f3d-708">版本 2003：2 月 14 日</span><span class="sxs-lookup"><span data-stu-id="81f3d-708">Version 2003: February 14</span></span>
<span data-ttu-id="81f3d-709">*版本 2003 (組建 12607.20000)*</span><span class="sxs-lookup"><span data-stu-id="81f3d-709">*Version 2003 (Build 12607.20000)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="81f3d-711">功能更新</span><span class="sxs-lookup"><span data-stu-id="81f3d-711">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="81f3d-712">Outlook</span><span class="sxs-lookup"><span data-stu-id="81f3d-712">Outlook</span></span>

- <span data-ttu-id="81f3d-713">**受限 WiFi 網路的新體驗：** 是否曾經加入需要登入網頁的 WiFi 網路呢？</span><span class="sxs-lookup"><span data-stu-id="81f3d-713">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="81f3d-714">Outlook 現在會偵測這項要求並協助您取得連結。</span><span class="sxs-lookup"><span data-stu-id="81f3d-714">Outlook now detects this and helps you get connected.</span></span>

### <a name="word"></a><span data-ttu-id="81f3d-715">Word</span><span class="sxs-lookup"><span data-stu-id="81f3d-715">Word</span></span>

- <span data-ttu-id="81f3d-716">**在繪圖工具箱中找到筆跡編輯器：** 選取 [繪圖]，然後選擇 [筆跡編輯器] 手寫筆以使用手指或數位筆編輯文件。</span><span class="sxs-lookup"><span data-stu-id="81f3d-716">**Find Ink Editor in your drawing toolbox:** Select Draw and then choose the Ink Editor pen to edit your document with your finger or a digital pen.</span></span> [<span data-ttu-id="81f3d-717">深入了解</span><span class="sxs-lookup"><span data-stu-id="81f3d-717">Learn more</span></span>](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

### <a name="office-suite"></a><span data-ttu-id="81f3d-718">Office 套件</span><span class="sxs-lookup"><span data-stu-id="81f3d-718">Office Suite</span></span>

- <span data-ttu-id="81f3d-719">**更清楚的狀態列圖示：** 狀態列圖示現在更容易查看</span><span class="sxs-lookup"><span data-stu-id="81f3d-719">**Clearer status bar icons:** Status bar icons are now easier to see</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="81f3d-722">解決的問題</span><span class="sxs-lookup"><span data-stu-id="81f3d-722">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="81f3d-723">Outlook</span><span class="sxs-lookup"><span data-stu-id="81f3d-723">Outlook</span></span>

- <span data-ttu-id="81f3d-724">已解決導致使用者無法存取「空閒/忙碌選項」行事曆權限對話方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-724">Addressed an issue that caused users to lose access to the "Free Busy Options" calendar permissions dialog.</span></span>

- <span data-ttu-id="81f3d-725">修正了開啟某些從不同時區傳送的週期性會議執行個體時，可能會導致出現警示：「很抱歉，無法開啟這此項目」的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-725">Fixed an issue that may result in the alert: "Sorry we're having trouble opening this item" when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="81f3d-726">已解決從該郵件拖放附件後造成使用者無法重新開啟 .msg 檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-726">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="81f3d-727">修正從 Outlook 上傳檔案附件到 OneDrive 後，造成包含括號之附件名稱的檔案名稱被變更。</span><span class="sxs-lookup"><span data-stu-id="81f3d-727">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="81f3d-728">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="81f3d-728">PowerPoint</span></span>

- <span data-ttu-id="81f3d-729">修正儲存包含 Excel 圖表的 PowerPoint 或 Word 文件會導致失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-729">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>

### <a name="word"></a><span data-ttu-id="81f3d-730">Word</span><span class="sxs-lookup"><span data-stu-id="81f3d-730">Word</span></span>

- <span data-ttu-id="81f3d-731">修正文件中的圖片在匯出成 PDF 後，會失去透明度的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-731">Fixed an issue where pictures in documents lose transparency when exported to PDF.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-february-07"></a><span data-ttu-id="81f3d-733">版本 2002：2 月 7 日</span><span class="sxs-lookup"><span data-stu-id="81f3d-733">Version 2002: February 07</span></span>
<span data-ttu-id="81f3d-734">*版本 2002 (組建 12527.20040)*</span><span class="sxs-lookup"><span data-stu-id="81f3d-734">*Version 2002 (Build 12527.20040)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="81f3d-736">功能更新</span><span class="sxs-lookup"><span data-stu-id="81f3d-736">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="81f3d-737">Access</span><span class="sxs-lookup"><span data-stu-id="81f3d-737">Access</span></span>

- <span data-ttu-id="81f3d-738">**在查詢設計工具、SQL 檢視和關聯視窗中工作時更具生產力：** 在資料表上按一下滑鼠右鍵即可開啟、設計、調整大小及隱藏它。</span><span class="sxs-lookup"><span data-stu-id="81f3d-738">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="81f3d-739">在 SQL 檢視中搜尋及取代文字。</span><span class="sxs-lookup"><span data-stu-id="81f3d-739">Search and replace text in SQL View.</span></span> <span data-ttu-id="81f3d-740">在 [關聯圖] 視窗中選取多個資料表。</span><span class="sxs-lookup"><span data-stu-id="81f3d-740">Select multiple tables in the Relationships window.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="81f3d-743">解決的問題</span><span class="sxs-lookup"><span data-stu-id="81f3d-743">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="81f3d-744">Access</span><span class="sxs-lookup"><span data-stu-id="81f3d-744">Access</span></span>

- <span data-ttu-id="81f3d-745">此更新會修正使用 ADODB 的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-745">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="81f3d-746">VB 程式碼中的記錄器物件可能會不正確地報告錯誤。</span><span class="sxs-lookup"><span data-stu-id="81f3d-746">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="81f3d-747">此更新修正可能會導致 Microsoft Access 無法識別連結的 SQL Server 資料表中的識別資料行的問題，這可能會導致不正確地將資料列報告為已刪除。</span><span class="sxs-lookup"><span data-stu-id="81f3d-747">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="81f3d-748">Excel</span><span class="sxs-lookup"><span data-stu-id="81f3d-748">Excel</span></span>

- <span data-ttu-id="81f3d-749">修正使用「資料剖析」搭配動態陣列時，Excel 會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-749">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="81f3d-750">Outlook</span><span class="sxs-lookup"><span data-stu-id="81f3d-750">Outlook</span></span>

- <span data-ttu-id="81f3d-751">修正以月檢視在行事曆中捲動時，無法顯示之前的行事曆活動的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-751">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="81f3d-752">解決在 Citrix 環境中檢視 30 個以上的行事曆時，導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-752">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="81f3d-753">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="81f3d-753">PowerPoint</span></span>

- <span data-ttu-id="81f3d-754">修正關閉檔案之後，如果有任何事件處理常式正在執行，PowerPoint 就不會立即將它從 [簡報] 集合中移除的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-754">Fixed an issue where after closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="81f3d-755">因此，物件模型報告的開啟中簡報數目會不正確，且會防止關閉 PowerPoint。</span><span class="sxs-lookup"><span data-stu-id="81f3d-755">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>

- <span data-ttu-id="81f3d-756">修正具有深色螢光筆色彩的白色文字，在灰階中會以黑色列印的螢光筆問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-756">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="81f3d-757">Word</span><span class="sxs-lookup"><span data-stu-id="81f3d-757">Word</span></span>

- <span data-ttu-id="81f3d-758">更新和瀏覽目錄時，有時可能會在文件上顯示灰色區域的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-758">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>

- <span data-ttu-id="81f3d-759">修正共同撰寫文件時，可能不會保留根註解的草稿版本的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-759">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>

- <span data-ttu-id="81f3d-760">已修正在註解卡片之間來回切換時，有時會顯示一開始選取的註解，並將某選取範圍醒目提示的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-760">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>

- <span data-ttu-id="81f3d-761">修正在已撰寫註解但未張貼，且使用者嘗試儲存檔案的情況下，使用 [瀏覽] 來儲存檔案沒有作用的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-761">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>

- <span data-ttu-id="81f3d-762">將 SlideTrack 啟用且 [註解] 窗格關閉時，Ctrl+Alt+M 可能無法開啟 [註解] 窗格的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-762">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>

- <span data-ttu-id="81f3d-763">修正在表格中新增 @提及時可能發生錯誤訊息：「文件中的表格已經毀損」的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-763">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>

### <a name="office-suite"></a><span data-ttu-id="81f3d-764">Office 套件</span><span class="sxs-lookup"><span data-stu-id="81f3d-764">Office Suite</span></span>

- <span data-ttu-id="81f3d-765">解決可能導致挪威耐諾斯克 (nn-no) 校訂工具套件安裝不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="81f3d-765">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


[//]: # (DO NOT MODIFY ADMIN CENTER METADATA CONTENT START)
[//]: # (|Win32 |DevMain |測試人員 | | 16.0.13115.20000 | 版本-2008-7月-17 |)
[//]: # (|Win32|DevMain|Insiders| |16.0.13102.20002|version-2008-july-10|)
[//]: # (DO NOT MODIFY ADMIN CENTER METADATA CONTENT END)
