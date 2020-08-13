---
title: 版本資訊目前通道 (預覽)
ms.author: anankani
author: v-lislo
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為「測試人員 - 慢」對象提供關鍵新功能、修正或已知問題的最新清單
ms.openlocfilehash: 1af6025eea51fcf6d231796b453eca1aac0f9cf3
ms.sourcegitcommit: 4fd6ebb878e4a30e416064d9c434c66dfc48fd47
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 08/11/2020
ms.locfileid: "46634849"
---
# <a name="release-notes-for-office-current-channel-preview"></a><span data-ttu-id="7856c-103">Office 版本資訊目前通道 (預覽)</span><span class="sxs-lookup"><span data-stu-id="7856c-103">Release Notes for Office Current Channel (Preview)</span></span>

<span data-ttu-id="7856c-104">本文包含 Windows 電腦版 Word、Excel、PowerPoint、Outlook、Access 和 Project 目前通道 (預覽) 組建的版本資訊。</span><span class="sxs-lookup"><span data-stu-id="7856c-104">This article contains release notes for Current Channel (Preview) builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="7856c-105">我們每週都強調有趣的新功能、重要修正，以及我們想讓您知道的重大問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="7856c-106">請注意，我們通常會在一段時間內推出功能 (有時甚至推出修正程式) 至目前通道 (預覽)。</span><span class="sxs-lookup"><span data-stu-id="7856c-106">Note that we often roll out features (and sometimes even fixes) to Current Channel (Preview) over a period of time.</span></span> <span data-ttu-id="7856c-107">這樣可讓我們確保功能都運作順利，然後才推出給更廣泛的對象。</span><span class="sxs-lookup"><span data-stu-id="7856c-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="7856c-108">所以，如果你沒有看到下面描述的項目，不要擔心你最終會得到它。</span><span class="sxs-lookup"><span data-stu-id="7856c-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="7856c-109">我們會變更 Microsoft 365 應用程式的更新通道，包括新增新的更新通道 (每月企業通道)，並變更現有的更新通道名稱。</span><span class="sxs-lookup"><span data-stu-id="7856c-109">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="7856c-110">如需深入了解，[請閱讀本文](https://go.microsoft.com/fwlink/p/?linkid=2127441)。</span><span class="sxs-lookup"><span data-stu-id="7856c-110">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
> - <span data-ttu-id="7856c-111">版本資訊發佈日期可能與實際組建發行日期不相符。</span><span class="sxs-lookup"><span data-stu-id="7856c-111">The release notes publication date may not match the actual build release date.</span></span>

[//]: # (DO NOT REMOVE)

## <a name="version-2008-august-11"></a><span data-ttu-id="7856c-113">版本 2008: 8月11日</span><span class="sxs-lookup"><span data-stu-id="7856c-113">Version 2008: August 11</span></span>
<span data-ttu-id="7856c-114">*版本2008（组建13127.20164）*</span><span class="sxs-lookup"><span data-stu-id="7856c-114">*Version 2008 (Build 13127.20164)*</span></span>

<span data-ttu-id="7856c-115">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="7856c-115">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="7856c-117">解決的問題</span><span class="sxs-lookup"><span data-stu-id="7856c-117">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="7856c-118">Access</span><span class="sxs-lookup"><span data-stu-id="7856c-118">Access</span></span>

- <span data-ttu-id="7856c-119">此修正會解決嘗試執行之前會產生「查詢太複雜」錯誤訊息的特定查詢的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-119">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>

- <span data-ttu-id="7856c-120">如果您已安装 Office 365，您就不需要再安装 [ACE 可再發行引擎]，就能在 Office 生態友善系統外公開 ACE。</span><span class="sxs-lookup"><span data-stu-id="7856c-120">If you have Office 365 installed, you no longer need to install our ACE Redistributable Engine to expose ACE outside of the Office ecosystem.</span></span> <span data-ttu-id="7856c-121">因此，如果您使用的是 Office 365，您將不需要 [ACE 可再發行引擎]，也因此不會再遭遇此問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-121">Therefore, for those with Office 365, you will no longer need the ACE Redist Engine, and consequently you should not experience this issue.</span></span>

- <span data-ttu-id="7856c-122">已解决此問題 - 您現在可以使用 Office 的隨選即用應用程式外的 ODBC 驅動程式。</span><span class="sxs-lookup"><span data-stu-id="7856c-122">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>

### <a name="excel"></a><span data-ttu-id="7856c-123">Excel</span><span class="sxs-lookup"><span data-stu-id="7856c-123">Excel</span></span>

- <span data-ttu-id="7856c-124">我們已修正若圖表數列順序已變更，與該數列對齊的對應核取方塊未隨著該數列重新排序的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-124">We fixed an issue where if the order of a chart series was changed, the corresponding checkbox aligned with the series was not reordered along with the series.</span></span>

- <span data-ttu-id="7856c-125">嘗試使用 LET () 函數儲存含有公式的檔案時，可能會發生錯誤。</span><span class="sxs-lookup"><span data-stu-id="7856c-125">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>

- <span data-ttu-id="7856c-126">我們修正了當透過 VBA 啟用活頁簿的 [ForceFullCalculation] 時，圖表不一會更新的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-126">We fixed an issue where charts were not always updated as expected when "ForceFullCalculation" was enabled via VBA for the workbook.</span></span>

- <span data-ttu-id="7856c-127">我們已修正具有放射狀漸層填滿的影像複本與原始不符的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-127">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

### <a name="onenote"></a><span data-ttu-id="7856c-128">OneNote</span><span class="sxs-lookup"><span data-stu-id="7856c-128">OneNote</span></span>

- <span data-ttu-id="7856c-129">我們修正了當應用程式視窗調整為小尺寸時，[搜尋] 編輯方塊中的預留位置文字發生溢出的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-129">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>

### <a name="outlook"></a><span data-ttu-id="7856c-130">Outlook</span><span class="sxs-lookup"><span data-stu-id="7856c-130">Outlook</span></span>

- <span data-ttu-id="7856c-131">我們修正了從相同的電子郵件網域在 Outlook 中建立多個設定檔會產生的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-131">We fixed an issue around creating multiple profiles in Outlookfrom the same email domain.</span></span>

- <span data-ttu-id="7856c-132">解决了導致使用 [共用行事曆改善] 的某些使用者無法查看剛新增的共用行事曆的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-132">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="7856c-133">解決了導致在 S/MIME 加密郵件的頁首中無法顯示鎖定圖示的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-133">Addressed an issue that caused the lock icon to fail to display in the header of S/MIME encrypted messages.</span></span>

- <span data-ttu-id="7856c-134">我們已修正，如果未核取 [下載共用資料夾]，共用行事曆會議 [回覆選項] 中缺少 [允許轉寄] 選項的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-134">We fixed an issue where the "Allow Forwarding" option was missing from the shared calendar meeting "Response Options" if Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="7856c-135">解決了當選取安全性對話方塊上的 [儲存] 選項時，導致使用者無法將 OneDrive 外部的 OneDrive 附件儲存至他們的本機電腦的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-135">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="7856c-136">我們已修正，即使使用者具有適當的列印權限也會在停用狀態下顯示列印按鈕的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-136">We fixed an issue that would display the print button in a disabled state even though the user had the appropriate print permissions.</span></span>

- <span data-ttu-id="7856c-137">解決了當以未加密郵件進行傳送時，會導致附件從 S/MIME 郵件中剝離出來的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-137">Addressed an issue that caused attachments to get stripped from S/MIME messages when sending as unencrypted.</span></span>

- <span data-ttu-id="7856c-138">解決了當純文字 S/MIME 郵件在傳送時發生亂碼的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-138">Addressed an issue that caused plain text S/MIME messages to become garbled when sending.</span></span>

- <span data-ttu-id="7856c-139">解決了當傳送未加密的 S/MIME 電子郵件時，會導致附件損毀的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-139">Addressed an issue that caused attachments to become corrupted when sending an S/MIME email unencrypted.</span></span>

- <span data-ttu-id="7856c-140">解決了當寄件者授與 [另存為] 許可權時，會導致收件者無法儲存許可權保護郵件的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-140">Addressed an issue that cause recipients to be unable to save rights protected messages even when the save as permission was granted by the sender.</span></span>

- <span data-ttu-id="7856c-141">這解決了當使用者從檢查程式視窗回覆受到數位版權管理的郵件，卻沒有所回覆郵件的擁有者權限時，會導致使用者會無法新增簽名的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-141">This fix addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user did not have Owner permissions on the message being replied to.</span></span>

- <span data-ttu-id="7856c-142">此修正會解決導致 Outlook 無法在 markdown 內容中正確顯示換行符號的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-142">This fix addresses an issue that was causing Outlook to fail to display line breaks properly in markdown content.</span></span>

- <span data-ttu-id="7856c-143">解決了某些 [進階搜尋] 選項標籤在某些語言中會被截斷的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-143">Addressed an issue that caused the labels for some Advanced Search options to be truncated in some languages.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7856c-144">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7856c-144">PowerPoint</span></span>

- <span data-ttu-id="7856c-145">我們已修正具有放射狀漸層填滿的影像複本與原始不符的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-145">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

- <span data-ttu-id="7856c-146">我們已修正 PowerPoint 中的 [表單] 按鈕在不允許存取 Office Store 時不會允許建立表單的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-146">We fixed an issue where the Forms button in PowerPoint did not allow the creation of Forms when access to Office Store was not permitted.</span></span>

### <a name="project"></a><span data-ttu-id="7856c-147">Project</span><span class="sxs-lookup"><span data-stu-id="7856c-147">Project</span></span>

- <span data-ttu-id="7856c-148">我們修正了 [工作委員會] 畫面中列出的工作未與 [指派資源] 對話方塊中的任務同步處理的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-148">We fixed an issue where tasks listed in the Task Board view were not in sync with those in the Assign Resources dialog.</span></span>

- <span data-ttu-id="7856c-149">我們修正了如果您嘗試從 Project 將 PDF/XPS 儲存至 SharePoint 文件庫，沒有發生任何動作的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-149">We fixed an issue where if you tried to save a PDF/XPS from Project to a SharePoint document library, nothing would happen.</span></span>

- <span data-ttu-id="7856c-150">我們修正了當您複製並貼上具有多個相關性的工作，並非所有相關性都能正確複製的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-150">We fixed an issue where if you copied & pasted a task that had multiple dependencies, not all dependencies were copied correctly.</span></span>

- <span data-ttu-id="7856c-151">已修正針對 SharePoint 工作清單，第二個索引標籤上的功能區按鈕可能會停用的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-151">Fixed an issue where for a SharePoint tasks list, the ribbon buttons on the second tab may be disabled.</span></span>

### <a name="skype"></a><span data-ttu-id="7856c-152">Skype</span><span class="sxs-lookup"><span data-stu-id="7856c-152">Skype</span></span>

- <span data-ttu-id="7856c-153">將跳舞表情符號膚色變更為中性色彩</span><span class="sxs-lookup"><span data-stu-id="7856c-153">Changed dancing emoticon skin tone to neutral color</span></span>

### <a name="visio"></a><span data-ttu-id="7856c-154">Visio</span><span class="sxs-lookup"><span data-stu-id="7856c-154">Visio</span></span>

- <span data-ttu-id="7856c-155">在此修正程序完成之后，如果使用者在任何機制（在此情况下是透過增益集）停止執行刪除命令，內存便不會泄漏，而且也不會影響整台電腦。</span><span class="sxs-lookup"><span data-stu-id="7856c-155">After this fix, if the user halted the execution of delete command by any mechanism in between (in this case it was through add-in) the memory won't leak and the whole machine won't be impacted.</span></span>

### <a name="word"></a><span data-ttu-id="7856c-156">Word</span><span class="sxs-lookup"><span data-stu-id="7856c-156">Word</span></span>

- <span data-ttu-id="7856c-157">我們已修正將某些文字及影像貼到 [註解] 方塊之後，Word 停止回應的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-157">We fixed an issue where Word would stop responding after pasting some text and an image in to a comments box.</span></span>

- <span data-ttu-id="7856c-158">我們已修正具有放射狀漸層填滿的影像複本與原始不符的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-158">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

- <span data-ttu-id="7856c-159">我們修正了當應用程式視窗調整為小尺寸時，[搜尋] 編輯方塊中的預留位置文字發生溢出的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-159">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>

- <span data-ttu-id="7856c-160">我們已修正如果新增註解來追蹤變更，將會意外開啟 [修訂] 窗格的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-160">We fixed an issue where if a comment was added to track a change, the revisions pane would unexpectedly open.</span></span>

- <span data-ttu-id="7856c-161">我們修正了當焦點位於註解文字方塊中時，[編輯器] 命令會被停用的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-161">We fixed an issue where the Editor command was disabled when the focus was in a comment text box.</span></span>

- <span data-ttu-id="7856c-162">我們修正了當焦點位於註解文字方塊中時，[顯示標記] 命令會被停用的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-162">We fixed an issue where the Show Markup command was disabled when the focus was in a comment text box.</span></span>

- <span data-ttu-id="7856c-163">我們已修正刪除最後一個註解後，[新增批註] 按鈕停用的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-163">We fixed an issue where the 'New comment' button would be disabled after deleting the last comment.</span></span>

- <span data-ttu-id="7856c-164">我們已修正 [追蹤修訂] 中的 [特定人員] 選項已停用的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-164">We fixed an issue where the 'Specific People' option for Track Changes was disabled.</span></span>

- <span data-ttu-id="7856c-165">我們已修正文件連結未透過 [插入] > [連結] 下拉式功能表插入 [註解] 方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-165">We fixed an issue where links to documents were not being inserted to the comments box via the Insert -> Link dropdown.</span></span>

- <span data-ttu-id="7856c-166">我們已修正了開啟 HTML 檔案時偶爾停止回應的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-166">We fixed an occasional hang while opening HTML files.</span></span>

- <span data-ttu-id="7856c-167">我們修正了自訂 XML 中的註解狀態在開啟文件時可能會遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-167">We fixed an issue in custom XML where the state of comments may be lost when opening the document.</span></span>

- <span data-ttu-id="7856c-168">我們已修正 VBA 超連結集合中的超連結計數，在新增包含超連結的影像之後，未正確反覆運算的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-168">We fixed an issue where the hyperlink count in the VBA hyperlinks collection was not iterating correctly after adding an image containing a hyperlink.</span></span>

- <span data-ttu-id="7856c-169">針對舊版非網頁服務的 [共用] 窗格，在開啟 [共用] 窗格下關閉文件時，可能會導致當機。</span><span class="sxs-lookup"><span data-stu-id="7856c-169">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash.</span></span> <span data-ttu-id="7856c-170">這個問題現在已經修正。</span><span class="sxs-lookup"><span data-stu-id="7856c-170">This is now fixed.</span></span>

- <span data-ttu-id="7856c-171">我們修正了使用者從工作列開啟新應用程式視窗，並建立新的空白檔時，會造成額外檔案建立的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-171">We fixed an issue where after the user opened a new app window from the taskbar and created a new blank document, additional files were created.</span></span>

- <span data-ttu-id="7856c-172">我們修正了當使用者在編輯文件，但是許可權遺失時，我們並未通知使用者必須重新驗證的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-172">We fixed an issue where if a user was editing a document but had lost permissions, we were not notifying the user that they had to re-authenticate.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-august-05"></a><span data-ttu-id="7856c-174">版本 2007：8 月 5 日</span><span class="sxs-lookup"><span data-stu-id="7856c-174">Version 2007: August 05</span></span>
<span data-ttu-id="7856c-175">*版本 2007 (組建 13029.20344)*</span><span class="sxs-lookup"><span data-stu-id="7856c-175">*Version 2007 (Build 13029.20344)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)



[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="7856c-179">解決的問題</span><span class="sxs-lookup"><span data-stu-id="7856c-179">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="7856c-180">Outlook</span><span class="sxs-lookup"><span data-stu-id="7856c-180">Outlook</span></span>

- <span data-ttu-id="7856c-181">解決會導致 Outlook 無法擷取搜尋建議的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-181">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>


- <span data-ttu-id="7856c-182">解決會導致使用者在擷取角色資訊時有時候會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-182">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>


### <a name="project"></a><span data-ttu-id="7856c-183">Project</span><span class="sxs-lookup"><span data-stu-id="7856c-183">Project</span></span>

- <span data-ttu-id="7856c-184">修正無法開啟已進入錯誤狀態的專案的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-184">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-july-29"></a><span data-ttu-id="7856c-186">版本 2007：7 月 29 日</span><span class="sxs-lookup"><span data-stu-id="7856c-186">Version 2007: July 29</span></span>
<span data-ttu-id="7856c-187">*版本 2007 (組建 13029.20308)*</span><span class="sxs-lookup"><span data-stu-id="7856c-187">*Version 2007 (Build 13029.20308)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="7856c-189">功能更新</span><span class="sxs-lookup"><span data-stu-id="7856c-189">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="7856c-190">Excel</span><span class="sxs-lookup"><span data-stu-id="7856c-190">Excel</span></span>

- <span data-ttu-id="7856c-191">**使用資料類型從 Power BI 取得組織資料：** 現在，來自 Power BI 的 Excel 資料類型將推出給使用 Office 365 E5/A5 或 Microsoft 365 E5/A5 之組織的測試人員使用。</span><span class="sxs-lookup"><span data-stu-id="7856c-191">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 E5/A5 or Microsoft 365 E5/A5.</span></span> <span data-ttu-id="7856c-192">取得您所需的資訊，輕鬆地重新整理，對許多日常工作流程而言至關重要。</span><span class="sxs-lookup"><span data-stu-id="7856c-192">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="7856c-193">我們允許您透過 Excel 中的資料類型從 Power BI 存取公司或組織資訊，從而擴充您在試算表中引入連結資訊的能力。</span><span class="sxs-lookup"><span data-stu-id="7856c-193">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="7856c-194">深入了解</span><span class="sxs-lookup"><span data-stu-id="7856c-194">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="7856c-195">在[部落格文章](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="7856c-195">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="7856c-196">Outlook</span><span class="sxs-lookup"><span data-stu-id="7856c-196">Outlook</span></span>

- <span data-ttu-id="7856c-197">**挑選搜尋的位置：** 新的搜尋範圍下拉式清單，可讓您更輕鬆地修改搜尋，並在目前資料夾和目前信箱之間切換。</span><span class="sxs-lookup"><span data-stu-id="7856c-197">**Pick where to search:** The new search scope drop down allows you to more easily modify your search and switch between Current Folder and Current Mailbox.</span></span> <span data-ttu-id="7856c-198">感謝每個在 [即將推出] 為 [頂極體驗] 的 新 [搜尋] 提供意見反應的人。</span><span class="sxs-lookup"><span data-stu-id="7856c-198">Thank you to everyone in Coming Soon who provided feedback on the new Search at Top experience.</span></span> <span data-ttu-id="7856c-199">因為有這份意見反應，才有這項設計與更新！</span><span class="sxs-lookup"><span data-stu-id="7856c-199">This design and update came out of that feedback!</span></span>

### <a name="word"></a><span data-ttu-id="7856c-200">Word</span><span class="sxs-lookup"><span data-stu-id="7856c-200">Word</span></span>

- <span data-ttu-id="7856c-201">**以新式註解更輕鬆地進行共同作業：** 新增註解到物件、@提及 同事，並解決註解執行緒，以獲得更佳的共同作業體驗。</span><span class="sxs-lookup"><span data-stu-id="7856c-201">**Better collaboration with modern comments:** Add comments to objects, @mention colleagues, and resolve comment threads for a better collaboration experience.</span></span> [<span data-ttu-id="7856c-202">深入了解</span><span class="sxs-lookup"><span data-stu-id="7856c-202">Learn more</span></span>](https://support.office.com/article/8d3f868a-867e-4df2-8c68-bf96671641e2)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="7856c-205">解決的問題</span><span class="sxs-lookup"><span data-stu-id="7856c-205">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="7856c-206">Outlook</span><span class="sxs-lookup"><span data-stu-id="7856c-206">Outlook</span></span>

- <span data-ttu-id="7856c-207">解決了導致 CLP 使用者在從受保護的內容切換到未受保護之回復的 [寄件者] 位址時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-207">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>


- <span data-ttu-id="7856c-208">解決了導致 [排程小幫手] 頁面無法顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-208">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>


- <span data-ttu-id="7856c-209">解決了事件通知提醒中導致格式設定問題的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-209">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-july-27"></a><span data-ttu-id="7856c-211">版本 2007：7 月 27 日</span><span class="sxs-lookup"><span data-stu-id="7856c-211">Version 2007: July 27</span></span>
<span data-ttu-id="7856c-212">*Version 2007 (組建 13029.20292)*</span><span class="sxs-lookup"><span data-stu-id="7856c-212">*Version 2007 (Build 13029.20292)*</span></span>
* <span data-ttu-id="7856c-213">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="7856c-213">Various bugs and performance fixes.</span></span>

## <a name="version-2007-july-20"></a><span data-ttu-id="7856c-214">版本 2007：7 月 20 日</span><span class="sxs-lookup"><span data-stu-id="7856c-214">Version 2007: July 20</span></span>
<span data-ttu-id="7856c-215">*版本2007 (組建 13029.20236)*</span><span class="sxs-lookup"><span data-stu-id="7856c-215">*Version 2007 (Build 13029.20236)*</span></span>
* <span data-ttu-id="7856c-216">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="7856c-216">Various bugs and performance fixes.</span></span>

## <a name="version-2007-july-15"></a><span data-ttu-id="7856c-217">版本 2007：7 月 15 日</span><span class="sxs-lookup"><span data-stu-id="7856c-217">Version 2007: July 15</span></span>
<span data-ttu-id="7856c-218">*版本 2007 (組建 13029.20200)*</span><span class="sxs-lookup"><span data-stu-id="7856c-218">*Version 2007 (Build 13029.20200)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="7856c-220">功能更新</span><span class="sxs-lookup"><span data-stu-id="7856c-220">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="7856c-221">Excel</span><span class="sxs-lookup"><span data-stu-id="7856c-221">Excel</span></span>

- <span data-ttu-id="7856c-222">**在 Excel 中製作精美的 Visio 圖表：** 將資料放在工作表上，以建立流程圖或組織圖。</span><span class="sxs-lookup"><span data-stu-id="7856c-222">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="7856c-223">深入了解</span><span class="sxs-lookup"><span data-stu-id="7856c-223">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="7856c-226">解決的問題</span><span class="sxs-lookup"><span data-stu-id="7856c-226">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="7856c-227">Access</span><span class="sxs-lookup"><span data-stu-id="7856c-227">Access</span></span>

- <span data-ttu-id="7856c-228">我們已修正在重新整理連結的 SQL 資料表時，連結資料表管理員會提示您輸入主要索引鍵的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-228">We fixed an issue where the linked table manager would prompt a primary key if a linked SQL table was refreshed.</span></span>

- <span data-ttu-id="7856c-229">我們已修正 [查詢編輯器] 中的查詢捲出畫面的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-229">We fixed an issue where queries in the Query Editor scrolled out of view.</span></span>

- <span data-ttu-id="7856c-230">我們已修正執行查詢的時間大約比預期完成時間兩倍久的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-230">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

- <span data-ttu-id="7856c-231">我們已修正導致 Microsoft Access 無法識別連結的 SQL Server 資料表中的識別資料行的問題，這可能會導致不正確地將資料列報告為已刪除。</span><span class="sxs-lookup"><span data-stu-id="7856c-231">We fixed an issue that caused Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which could cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="7856c-232">Excel</span><span class="sxs-lookup"><span data-stu-id="7856c-232">Excel</span></span>

- <span data-ttu-id="7856c-233">我們已修正非 HTTP 或 HTTPS 型 URL 未顯示在 [最近用過的] 清單中的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-233">We fixed an issue where URLs that were not http or https based were not being displayed in the Most Recently Used list.</span></span>

- <span data-ttu-id="7856c-234">已修正在載入含有多張分頁預覽的活頁簿時，可能會發生錯誤或當機問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-234">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>

- <span data-ttu-id="7856c-235">我們修正以下問題：在特定版本 Excel 中建立的資料模型表格無法在 [表格預覽] 中看到，即使與該表相關聯的查詢尚未編輯。</span><span class="sxs-lookup"><span data-stu-id="7856c-235">We fixed an issue where data model tables created in certain versions of Excel could not be seen in 'Table Preview' even though the query associated with the table had not been edited.</span></span>

- <span data-ttu-id="7856c-236">在 [定義名稱\套用名稱] 對話方塊中停用 [忽略相對/絕對] 參照會導致公式無法使用。</span><span class="sxs-lookup"><span data-stu-id="7856c-236">Ignore Relative/Absolute' references in the Define Name \ Apply Names dialog would cause formulas to not work.</span></span>

- <span data-ttu-id="7856c-237">我們已修正將活頁簿儲存至 SharePoint/OneDrive 時，會導致自訂功能區索引標籤 CustomUI XML 遭移除的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-237">We fixed an issue where CustomUI XML for a custom ribbon tab was removed when saving a workbook to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="7856c-238">我們已修正當建議以唯讀方式使用檔案時，活頁簿處於唯讀狀態的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-238">We fixed an issue where workbooks were read-only when the file only had read-only recommended.</span></span>

- <span data-ttu-id="7856c-239">已修正在載入含有多張分頁預覽的活頁簿時，可能會發生錯誤或當機問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-239">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>

- <span data-ttu-id="7856c-240">我們已修正雷達圖的主要格線無法正確設定格式的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-240">We fixed an issue where the major gridlines of radar charts could not be formatted correctly.</span></span>


- <span data-ttu-id="7856c-241">我們已修正清除 [進階資料篩選] 可能會遺失表格格式設定的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-241">We fixed an issue where clearing an advanced data filter could lose table formatting.</span></span>


- <span data-ttu-id="7856c-242">我們已修正嵌入式 PDF 文件的完整路徑顯示在文件標題，而不只是檔案名稱的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-242">We fixed an issue where the full path of an embedded PDF document would show in the document caption rather than just the filename.</span></span>


- <span data-ttu-id="7856c-243">我們已修正停用 Wolfram 雲端連接器之後，儲存並重新開啟 Excel 活頁簿可能會導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-243">We fixed an issue where after disabling the Wolfram cloud connector and then saving and re-opening an Excel workbook, could result in a crash.</span></span>


- <span data-ttu-id="7856c-244">我們已修正啟動 Excel 時啟用 [規劃求解] 增益集將導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-244">We fixed an issue where booting Excel with the Solver add-in enabled would result in a crash.</span></span>


### <a name="outlook"></a><span data-ttu-id="7856c-245">Outlook</span><span class="sxs-lookup"><span data-stu-id="7856c-245">Outlook</span></span>

- <span data-ttu-id="7856c-246">我們已修正如果在 [收件者] 行上有超過 130 個收件者，Outlook 會當機的問題，且我們也改善了呈現文字的效能。</span><span class="sxs-lookup"><span data-stu-id="7856c-246">We fixed an issue where Outlook would hang if there were over 130 recipients on the 'To' line and we also improved the performance of rendering the text.</span></span>


- <span data-ttu-id="7856c-247">我們已修正以下問題：當使用多個不同解析度的監視器時，輸入法編輯器 (IEM) 視窗會覆蓋透過 IME 輸入的文字。</span><span class="sxs-lookup"><span data-stu-id="7856c-247">We fixed an issue where the Input Method Editor (IME) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>


- <span data-ttu-id="7856c-248">我們已修正「待辦事項列」中跨越兩天以上的活動，在後續的所有日期中顯示相同結束時間的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-248">We fixed an issue in the 'To Do Bar' where events that spanned more than two days, displayed the same end time for all subsequent days.</span></span>


- <span data-ttu-id="7856c-249">解決會導致使用者看到他們透過拖放附件，以複製到其檔案系統所建立附件的建立日期設為 4501 年 1 月 1 日的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-249">Addresses an issue that caused users to see the creation date of attachments that they copied to their file system via drag and drop getting set to January 1, 4501.</span></span>


- <span data-ttu-id="7856c-250">我們已修正使用者無法使用通訊群組清單中的「傳送為」或「代理傳送者」的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-250">We fixed an issue where users were unable to 'Send As' or 'Send on behalf' of a distribution list.</span></span>


- <span data-ttu-id="7856c-251">解決在編輯經理行事曆上的現有行事曆約會時，導致代理人收到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-251">Addresses an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>


- <span data-ttu-id="7856c-252">我們已修正導致使用者在關閉先前儲存的約會時看到下列錯誤的問題：「項目無法儲存，因為已被其他使用者或已在其他視窗中變更過。</span><span class="sxs-lookup"><span data-stu-id="7856c-252">We fixed an issue that caused users to see the following error when closing an appointment that was previously saved "The item cannot be saved because it was changed by another user or in another window.</span></span> <span data-ttu-id="7856c-253">您要在預設資料夾為這個項目建立複本?」</span><span class="sxs-lookup"><span data-stu-id="7856c-253">Do you want to make a copy in the default folder for the item?"</span></span>


- <span data-ttu-id="7856c-254">解決會導致若「未」核取 [下載共用資料夾]，共用行事曆會議的 [回應選項] 中會遺失 [允許轉寄] 選項的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-254">Addresses an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>


- <span data-ttu-id="7856c-255">解決選取安全性對話方塊上的 [儲存] 選項時，會導致使用者無法將來自其租用戶外部的 OneDrive 附件儲存至其本機電腦的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-255">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>


- <span data-ttu-id="7856c-256">我們已修正導致 Outlook 使用者在使用共用行事曆後，在幾分鐘內訊息清單停止更新的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-256">We fixed an issue that caused users of Outlook to see their message list stop updating for several minutes after using shared calendars.</span></span>


- <span data-ttu-id="7856c-257">我們已修正行事曆提醒無法針對一週內即將到來的會議顯示確切時間的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-257">We fixed an issue that prevented calendar reminders from showing exact times for meetings coming up in less than a week.</span></span> 


- <span data-ttu-id="7856c-258">我們已修正在郵件中插入影像內嵌，然後將郵件儲存為草稿將會重新調整影像大小的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-258">We fixed an issue where inserting an image inline in a message, then saving the message as a draft would result in a resizing of the image.</span></span>


- <span data-ttu-id="7856c-259">我們已修正在編輯主旨之後，導致 NDR 郵件的本文從 Unicode 變更為 ASCII 的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-259">We fixed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>


- <span data-ttu-id="7856c-260">我們已修正迷你行事曆中的日期無法針對日本使用者顯示粗體的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-260">We fixed an issue where dates in the mini calendar failed to display in bold for users in Japan.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="7856c-261">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7856c-261">PowerPoint</span></span>

- <span data-ttu-id="7856c-262">我們已修正在即時共同撰寫工作階段期間，使用者的目前狀態色彩指示器無法在共同撰寫文件庫中重新整理的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-262">We fixed an issue where a user's presence color indicator was not getting refreshed in the co-authoring gallery during a live co-authoring session.</span></span>


- <span data-ttu-id="7856c-263">我們已修正將 HTML 貼到投影片上的文字區域時，會改為貼上投影片最上方所建立的文字方塊中的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-263">We fixed an issue where pasting HTML to a text area on a slide would instead get pasted into a text box created at the top of the slide.</span></span>


- <span data-ttu-id="7856c-264">我們已修正在 [簡報者檢視畫面] 中選取所有投影片、使用 Alt+Tab 退出 [簡報者檢視畫面] 並返回投影片放映，然後按一下 [結束放映] 時，將導致未處理例外狀況的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-264">We fixed an issue where selecting all slides in Presenter View, then exiting Presenter View using Alt+Tab and returning to the slide show and clicking 'End Show' would result in an unhandled exception.</span></span>


### <a name="project"></a><span data-ttu-id="7856c-265">Project</span><span class="sxs-lookup"><span data-stu-id="7856c-265">Project</span></span>

- <span data-ttu-id="7856c-266">已修正無法將從 Project 將 PDF/XPS 儲存至 SharePoint 文件庫的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-266">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>


- <span data-ttu-id="7856c-267">修正 URL 以 .com 結尾時，無法從 Project Web App 在 Project 傳統型用戶端開啟專案的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-267">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>


- <span data-ttu-id="7856c-268">我們已修正 Project 在開啟特定 XML 檔案時可能當機的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-268">We fixed an issue where Project may crash when opening certain XML files.</span></span>


- <span data-ttu-id="7856c-269">我們已修正 URL 以 '.com' 結尾時，無法從 Project Web App 在 Project 傳統型用戶端開啟專案的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-269">We fixed an issue where projects couldn't be opened in the Project desktop client from the Project Web App if the URL ended in '.com'.</span></span>


- <span data-ttu-id="7856c-270">已修正問題：如果您貼上具有多個相關性的工作，並不會正確複製所有相關性。</span><span class="sxs-lookup"><span data-stu-id="7856c-270">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>


- <span data-ttu-id="7856c-271">已修正 [指派資源] 對話方塊中選取的工作與工作面板檢視中所選工作不同的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-271">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>


- <span data-ttu-id="7856c-272">我們已修正當專案摘要工作，或專案 [開始/工作] 欄位變更時，ProjectBeforeTaskChange 事件無法觸發的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-272">We fixed an issue where the ProjectBeforeTaskChange event didn't fire when there was a change to the project summary task, either the project start/task field.</span></span>


- <span data-ttu-id="7856c-273">我們已修正以下問題：如果固定工期的任務已 100% 完成，但未指定 [實際完成日期]，則任務的完成 % 將顯示為低於 100%。</span><span class="sxs-lookup"><span data-stu-id="7856c-273">We fixed an issue where if Fixed Duration tasks are at 100% complete but the Actual Finish is not specified, the Task % Complete would display as less than 100%.</span></span>

- <span data-ttu-id="7856c-274">我們已修正以下問題：比較基準重設或更新可能會變更時間分段預算成本/工時資源，且比較基準反映不正確的預算值。</span><span class="sxs-lookup"><span data-stu-id="7856c-274">We fixed an issue where a baseline reset or update could change time-phased budget cost/work resources and the baseline could reflect incorrect budget values.</span></span>


- <span data-ttu-id="7856c-275">我們已修正政府社群雲端中的 Project Planner 連結已停用的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-275">We fixed an issue where Project Planner links in Government Community Cloud environments had been disabled.</span></span>


- <span data-ttu-id="7856c-276">我們已修正如果文件庫處於新式模式，您無法從 SharePoint 文件庫開啟 Project 檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-276">We fixed an issue where you couldn't open a Project file from a SharePoint document library if the library was in modern mode.</span></span>


### <a name="word"></a><span data-ttu-id="7856c-277">Word</span><span class="sxs-lookup"><span data-stu-id="7856c-277">Word</span></span>

- <span data-ttu-id="7856c-278">我們已修正使用 Office 功能區中的 [清除格式設定] 按鈕清除 [註解] 窗格中的格式設定時，無法運作的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-278">We fixed an issue where the ability to clear formatting within the Comments pane via the Clear Formatting button in the Office Ribbon was not working.</span></span>


- <span data-ttu-id="7856c-279">我們已修正將插入可縮放向量圖形 (SVG) 中的文字插入到 Word、Excel 或 PowerPoint 檔案、儲存並關閉檔案，然後重新開啟檔案後，難以辨識的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-279">We fixed an issue where text inserted in a Scalable Vector Graphic (SVG) was illegible after inserting it in a Word, Excel, or PowerPoint file, saving and closing the file, and then re-opening the file.</span></span>


- <span data-ttu-id="7856c-280">我們已修正當尺規未顯示時變更表格大小，導致在背景中執行其他應用程式開始閃爍的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-280">We fixed an issue where changing the size of a table when the ruler is not displayed caused other applications running in the background to start flashing.</span></span>


- <span data-ttu-id="7856c-281">我們已修正在共同撰寫模式中，註解回覆有時候不會顯示在 [註解] 窗格中，而是顯示在 [修訂] 窗格中的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-281">We fixed an issue where in co-authoring mode, comment replies would sometimes not show up in the comments pane but would be visible in the revisions pane.</span></span>


- <span data-ttu-id="7856c-282">我們已修正在共同撰寫模式期間，當發生合併衝突且使用者已選取放棄變更時，我們不再顯示儲存或捨棄變更選項的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-282">We fixed an issue during co-authoring mode when there is a merge conflict and the user has already chosen to discard changes, we no longer display the option to save or discard changes.</span></span>


- <span data-ttu-id="7856c-283">我們已修正 HTML 超連結色彩無法正確呈現的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-283">We fixed an issue where the HTML hyperlink color was not being rendered correctly.</span></span>


- <span data-ttu-id="7856c-284">我們已修正以下問題：如果 Word 經常開啟的文件清單多於 50 個，然後儲存並開啟文件後，即使該文件沒有進行任何修訂，也會顯示歷程記錄。</span><span class="sxs-lookup"><span data-stu-id="7856c-284">We fixed an issue where if Word had a list of more than 50 frequently opened documents, then after saving and opening a document, a revision history would be displayed even though no revisions were made to that document.</span></span>


- <span data-ttu-id="7856c-285">我們已修正共同撰寫期間的自動儲存問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-285">We fixed in issue with autosave during coauthoring.</span></span>


- <span data-ttu-id="7856c-286">我們已修正一個問題，當嘗試使用新名稱儲存包含巨集的檔案時，無論使用者輸入什麼名稱，都會導致該檔案以 .docx 副檔名和檔案名稱 'WRO0004.docx' 儲存，進而導致文件無法使用。</span><span class="sxs-lookup"><span data-stu-id="7856c-286">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with a .docx extension and the filename 'WRO0004.docx', regardless of what the user entered, rendering the document unusable.</span></span>


### <a name="office-suite"></a><span data-ttu-id="7856c-287">Office 套件</span><span class="sxs-lookup"><span data-stu-id="7856c-287">Office Suite</span></span>

- <span data-ttu-id="7856c-288">關閉 Office 檔案時，計時問題可能會導致當機</span><span class="sxs-lookup"><span data-stu-id="7856c-288">A timing issue could cause a crash when closing office files</span></span>

- <span data-ttu-id="7856c-289">此問題的修正程式是確保服務正確計算新增的產品。</span><span class="sxs-lookup"><span data-stu-id="7856c-289">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="7856c-290">我們已篩選出新增的產品 (確保它們同時存在於新的設定中)，並將它們新增到現有產品發行識別碼的結尾。</span><span class="sxs-lookup"><span data-stu-id="7856c-290">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-july-09"></a><span data-ttu-id="7856c-292">版本 2006：7 月 09 日</span><span class="sxs-lookup"><span data-stu-id="7856c-292">Version 2006: July 09</span></span>
<span data-ttu-id="7856c-293">*版本2006（組建13001.20384）*</span><span class="sxs-lookup"><span data-stu-id="7856c-293">*Version 2006 (Build 13001.20384)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="7856c-295">功能更新</span><span class="sxs-lookup"><span data-stu-id="7856c-295">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="7856c-296">Excel</span><span class="sxs-lookup"><span data-stu-id="7856c-296">Excel</span></span>

- <span data-ttu-id="7856c-297">**建立 PDF 連線：** 連線至、匯入、重新整理 PDF 中的資料。</span><span class="sxs-lookup"><span data-stu-id="7856c-297">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="7856c-298">深入了解</span><span class="sxs-lookup"><span data-stu-id="7856c-298">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="7856c-299">**建立變數以在公式中使用：** 使用 LET 函數改善效能、可讀性及可組合性。</span><span class="sxs-lookup"><span data-stu-id="7856c-299">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="7856c-300">此函數可讓您在新的或現有的公式中建立命名變數。</span><span class="sxs-lookup"><span data-stu-id="7856c-300">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="7856c-301">深入了解</span><span class="sxs-lookup"><span data-stu-id="7856c-301">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="7856c-302">在[部落格文章](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="7856c-302">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

- <span data-ttu-id="7856c-303">**Excel 中的鍵盤快速鍵：** Excel 升級的鍵盤快速鍵</span><span class="sxs-lookup"><span data-stu-id="7856c-303">**Keyboard shortcuts in Excel:** Updated keyboard shortcuts for Excel</span></span>

### <a name="outlook"></a><span data-ttu-id="7856c-304">Outlook</span><span class="sxs-lookup"><span data-stu-id="7856c-304">Outlook</span></span>

- <span data-ttu-id="7856c-305">**在 Outlook 中使用 [快速投票] 建立投票：** 輕鬆建立投票，收集投票，並查看電子郵件中的結果 [深入瞭解](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="7856c-305">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="7856c-306">**將圖片作為電子郵件的一部分傳送時，讓圖片保持高畫質：** 一個新 Outlook 設定，可讓您在隨著電子郵件內容傳送圖片時限制圖片壓縮</span><span class="sxs-lookup"><span data-stu-id="7856c-306">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="7856c-309">解決的問題</span><span class="sxs-lookup"><span data-stu-id="7856c-309">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="7856c-310">Access</span><span class="sxs-lookup"><span data-stu-id="7856c-310">Access</span></span>

- <span data-ttu-id="7856c-311">此問題已解決，您應該能成功地將包含身分識別(例如 [自動編號]) 欄位的連結的 SQL 資料表插入到 Access 中。</span><span class="sxs-lookup"><span data-stu-id="7856c-311">This issue is resolved, and you should expect to be able to successfully insert linked SQL tables that include an identity (e.g. autonumber) field into Access.</span></span>

### <a name="excel"></a><span data-ttu-id="7856c-312">Excel</span><span class="sxs-lookup"><span data-stu-id="7856c-312">Excel</span></span>

- <span data-ttu-id="7856c-313">已修正當您從帳戶登出時，嘗試建立資料連線時，可能會發生的當機問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-313">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

### <a name="outlook"></a><span data-ttu-id="7856c-314">Outlook</span><span class="sxs-lookup"><span data-stu-id="7856c-314">Outlook</span></span>

- <span data-ttu-id="7856c-315">解決了當選取安全性對話方塊上的 [儲存] 選項時，導致使用者無法將 OneDrive 外部的 OneDrive 附件儲存至他們的本機電腦的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-315">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="office-suite"></a><span data-ttu-id="7856c-316">Office 套件</span><span class="sxs-lookup"><span data-stu-id="7856c-316">Office Suite</span></span>

- <span data-ttu-id="7856c-317">我們會將新的 AppV51 向後移，以修正先前 AppV51 中的回歸。</span><span class="sxs-lookup"><span data-stu-id="7856c-317">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="7856c-318">當您啟用增益集，而登錄 TabProcGrowth 值為 REG_SZ 類型且其值為 "0"時，辦公主機視窗會當機。</span><span class="sxs-lookup"><span data-stu-id="7856c-318">he office host was crashing in windows, when an add-in is being activated while the registry TabProcGrowth value is REG_SZ type and with value "0".</span></span>  <span data-ttu-id="7856c-319">這個登錄 TabProcGrowth 值可以在下列4個路徑中的任何一個中： HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main HKEY_CURRENT_USER \Software\Policies\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINE \Software\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINER \Software\Policies\Microsoft\Internet Explorer\Main 此變更將修正此問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-319">That registry TabProcGrowth value can be under any one of 4 paths: HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main HKEY_CURRENT_USER\Software\Policies\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINE\Software\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINER\Software\Policies\Microsoft\Internet Explorer\Main This change would fix this issue.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-june-25"></a><span data-ttu-id="7856c-321">版本 2006：6 月 25 日</span><span class="sxs-lookup"><span data-stu-id="7856c-321">Version 2006: June 25</span></span>
<span data-ttu-id="7856c-322">*版本2006（組建13001.20266）*</span><span class="sxs-lookup"><span data-stu-id="7856c-322">*Version 2006 (Build 13001.20266)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="7856c-324">功能更新</span><span class="sxs-lookup"><span data-stu-id="7856c-324">Feature updates</span></span>
### <a name="visio"></a><span data-ttu-id="7856c-325">Visio</span><span class="sxs-lookup"><span data-stu-id="7856c-325">Visio</span></span>

- <span data-ttu-id="7856c-326">**在 Excel 中製作精美的 Visio 圖表：** 根據工作表上的資料，建立流程圖或組織圖。</span><span class="sxs-lookup"><span data-stu-id="7856c-326">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart based on data in a worksheet.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="7856c-329">解決的問題</span><span class="sxs-lookup"><span data-stu-id="7856c-329">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="7856c-330">Access</span><span class="sxs-lookup"><span data-stu-id="7856c-330">Access</span></span>

- <span data-ttu-id="7856c-331">這個問題已解決。</span><span class="sxs-lookup"><span data-stu-id="7856c-331">This problem is now resolved.</span></span> <span data-ttu-id="7856c-332">如果您在此流程中遇到更多問題，請告知小組。</span><span class="sxs-lookup"><span data-stu-id="7856c-332">Please let the team know if you experience more issues with this process.</span></span>


### <a name="outlook"></a><span data-ttu-id="7856c-333">Outlook</span><span class="sxs-lookup"><span data-stu-id="7856c-333">Outlook</span></span>

- <span data-ttu-id="7856c-334"><span style="display:inline !important;">解決一個問題，該問題導致使用者看到<span>&nbsp;</span></span><span style="box-sizing:border-box;font-family:Calibri, sans-serif;font-size:14.6667px;display:inline !important;">附件的建立日期&nbsp; 他們透過托放方式將該附件複製到其檔案系統&nbsp; 該建立日期設於 4501年1月1日。</span></span><span class="sxs-lookup"><span data-stu-id="7856c-334"><span style="display:inline !important;">Addresses an issue that caused users to see<span>&nbsp;</span></span><span style="box-sizing:border-box;font-family:Calibri, sans-serif;font-size:14.6667px;display:inline !important;">the creation date of&nbsp; attachments that they copied to their file system via drag and drop getting&nbsp; set to January 1, 4501.</span></span></span><br>


- <span data-ttu-id="7856c-335"><span style="font-family:&quot;Segoe UI&quot;, system-ui, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, sans-serif;display:inline !important;">解決導致 [共用行事曆] 改善的使用者查看行事曆失敗的問題。</span></span><span class="sxs-lookup"><span data-stu-id="7856c-335"><span style="font-family:&quot;Segoe UI&quot;, system-ui, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, sans-serif;display:inline !important;">Addresses an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span></span><br>


- <span data-ttu-id="7856c-336"><span style="display:inline !important;">解決導致使用者看到 Outlook 持續提示他們執行收件匣修復工具的問題。</span></span><span class="sxs-lookup"><span data-stu-id="7856c-336"><span style="display:inline !important;">Addresses an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span></span><br>


- <span data-ttu-id="7856c-337"><span style="display:inline !important;">解決導致在[建議功能]中尋找功能沒有結果並未留給使用者選項以提交新功能點子的問題。</span></span><span class="sxs-lookup"><span data-stu-id="7856c-337"><span style="display:inline !important;">Addresses an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span></span><br>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-june-18"></a><span data-ttu-id="7856c-339">版本 2006：6 月 18 日</span><span class="sxs-lookup"><span data-stu-id="7856c-339">Version 2006: June 18</span></span>
<span data-ttu-id="7856c-340">*版本2006（組建13001.20198）*</span><span class="sxs-lookup"><span data-stu-id="7856c-340">*Version 2006 (Build 13001.20198)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="7856c-342">功能更新</span><span class="sxs-lookup"><span data-stu-id="7856c-342">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="7856c-343">Excel</span><span class="sxs-lookup"><span data-stu-id="7856c-343">Excel</span></span>



- <span data-ttu-id="7856c-344">**儲存至 [釘選資料夾]：** 釘選您的資料夾可讓您更輕鬆地儲存 Office 檔案，我們收到意見反應，使用者希望能在新檔案儲存時可以在可用的資料夾上有更多控制權。</span><span class="sxs-lookup"><span data-stu-id="7856c-344">**Save to Pinned Folders:** Pin your folders makes saving Office files easier We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="7856c-345">我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。</span><span class="sxs-lookup"><span data-stu-id="7856c-345">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="7856c-346">這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。</span><span class="sxs-lookup"><span data-stu-id="7856c-346">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> <br /><span data-ttu-id="7856c-347">在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="7856c-347">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7856c-348">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7856c-348">PowerPoint</span></span>

- <span data-ttu-id="7856c-349">**儲存至 [釘選資料夾]：** 釘選您的資料夾可讓您更輕鬆地儲存 Office 檔案，我們收到意見反應，使用者希望能在新檔案儲存時可以在可用的資料夾上有更多控制權。</span><span class="sxs-lookup"><span data-stu-id="7856c-349">**Save to Pinned Folders:** Pin your folders makes saving Office files easier We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="7856c-350">我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。</span><span class="sxs-lookup"><span data-stu-id="7856c-350">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="7856c-351">這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。</span><span class="sxs-lookup"><span data-stu-id="7856c-351">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="7856c-352">在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="7856c-352">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="word"></a><span data-ttu-id="7856c-353">Word</span><span class="sxs-lookup"><span data-stu-id="7856c-353">Word</span></span>

- <span data-ttu-id="7856c-354">**儲存至 [釘選資料夾]：** 釘選您的資料夾可讓您更輕鬆地儲存 Office 檔案。我們收到意見反應，使用者希望能在新檔案儲存時可以在可用的資料夾上有更多控制權。</span><span class="sxs-lookup"><span data-stu-id="7856c-354">**Save to Pinned Folders:** Pin your folders makes saving Office files easierWe received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="7856c-355">我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。</span><span class="sxs-lookup"><span data-stu-id="7856c-355">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="7856c-356">這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。</span><span class="sxs-lookup"><span data-stu-id="7856c-356">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> <br /><span data-ttu-id="7856c-357">在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="7856c-357">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="7856c-360">解決的問題</span><span class="sxs-lookup"><span data-stu-id="7856c-360">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="7856c-361">Excel</span><span class="sxs-lookup"><span data-stu-id="7856c-361">Excel</span></span>

- <span data-ttu-id="7856c-362">已修正當儲存至 SharePoint/OneDrive 時，會導致自訂功能區索引標籤 CustomUI XML 的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-362">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

### <a name="outlook"></a><span data-ttu-id="7856c-363">Outlook</span><span class="sxs-lookup"><span data-stu-id="7856c-363">Outlook</span></span>

- <span data-ttu-id="7856c-364">解決了啟用雲端設定時，按下 Ctrl + 按一下會造成運作停止的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-364">Addressed an issue that caused Ctrl+click to stop working when cloud settings were enabled.</span></span>

### <a name="project"></a><span data-ttu-id="7856c-365">專案</span><span class="sxs-lookup"><span data-stu-id="7856c-365">Project</span></span>

- <span data-ttu-id="7856c-366">已修正當標示為100% 完成之工作錯誤地變更為完成度低於100% 的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-366">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-june-11"></a><span data-ttu-id="7856c-368">版本 2006：6 月 11 日</span><span class="sxs-lookup"><span data-stu-id="7856c-368">Version 2006: June 11</span></span>
<span data-ttu-id="7856c-369">*版本2006（組建13001.20144）*</span><span class="sxs-lookup"><span data-stu-id="7856c-369">*Version 2006 (Build 13001.20144)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="7856c-371">功能更新</span><span class="sxs-lookup"><span data-stu-id="7856c-371">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="7856c-372">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7856c-372">PowerPoint</span></span>

- <span data-ttu-id="7856c-373">**改善的 PowerPoint 中的 Steam 影片效能：** 我們改善了 Microsoft Stream 影片的播放效能，將影片載入時間減至最少，以建立出流暢的觀賞體驗。</span><span class="sxs-lookup"><span data-stu-id="7856c-373">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="7856c-374">您可以使用 Microsoft Stream 上您的公司影片來建立更完善的簡報。</span><span class="sxs-lookup"><span data-stu-id="7856c-374">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

### <a name="word"></a><span data-ttu-id="7856c-375">Word</span><span class="sxs-lookup"><span data-stu-id="7856c-375">Word</span></span>

- <span data-ttu-id="7856c-376">**以向量保留文字：** 現在當您在 Excel、Word 和 PowerPoint 中轉換地圖、圖表和其他 SVG 向量等物件時，您可以保留物件中的文字。</span><span class="sxs-lookup"><span data-stu-id="7856c-376">**Retain text in vectors:** Now you can retain the text in maps, charts, and other SVG vectors when converting these objects in Excel, Word, and PowerPoint.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="7856c-379">解決的問題</span><span class="sxs-lookup"><span data-stu-id="7856c-379">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="7856c-380">Excel</span><span class="sxs-lookup"><span data-stu-id="7856c-380">Excel</span></span>

- <span data-ttu-id="7856c-381">我們修正了在使用 OneDrive 時，Excel 偶爾會關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-381">We fixed an issue where Excel would occasionally shut down when engaging OneDrive.</span></span>

- <span data-ttu-id="7856c-382">我們修正了圖表座標軸自訂值無法正確套用的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-382">We fixed an issue where custom values on the chart axis would not get applied correctly.</span></span>

- <span data-ttu-id="7856c-383">我們修正了包含多個含有定義名稱的公式會導致儲存檔案時間加長的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-383">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

- <span data-ttu-id="7856c-384">我們修正了導致印表機名稱在可用印表機清單中重複的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-384">We fixed an issue that caused printer names to be duplicated in the list of available printers.</span></span>

- <span data-ttu-id="7856c-385">我們修正了在使用者刪除合併的欄時，造成執行時間增加的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-385">We fixed an issue that resulted in improved performance time for users when they deleted merged columns.</span></span>

- <span data-ttu-id="7856c-386">我們修正了因為增益集是以字母順序裝載，而不是以使用者指定的順序載入，而造成出現「因為此活頁簿目前有他人進行參考，而無法關閉」的錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-386">We fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="7856c-387">我們修正了管理 Excel 與部分協力廠商輔助技術應用程式之間的字型時發生記憶體損毀的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-387">We fixed an issue where memory was being corrupted when managing fonts between Excel and some third party assistive technology applications.</span></span>

- <span data-ttu-id="7856c-388">我們修正了在相同活頁簿中按一下加上書簽的超連結會導致活頁簿隱藏的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-388">We fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="7856c-389">我們已修正某些複製和貼上的圖表連結使用的是映射磁碟機位址，而不是通用位址的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-389">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="7856c-390">我們修正了當 Excel 視窗透過 Teams 共用時，使用 Ctrl + Shift + 方向鍵滑動後，Excel 可能會無法回應的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-390">We fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window was shared through Teams.</span></span>

- <span data-ttu-id="7856c-391">我們修正了當增益集在工作表中詢問含有 noSelect 鎖定的圖形的主項目目時，Excel 會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-391">We fixed an issue where Excel would crash when Add-ins ask for Host Items on worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="7856c-392">解決了嘗試將樞紐分析表插入圖表時 Excel 可能會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-392">Addressed an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

### <a name="outlook"></a><span data-ttu-id="7856c-393">Outlook</span><span class="sxs-lookup"><span data-stu-id="7856c-393">Outlook</span></span>

- <span data-ttu-id="7856c-394">我們已修正以下問題：當使用多個不同解析度的監視器時，輸入法編輯器 (IEM) 視窗會覆蓋透過 IME 輸入的文字。</span><span class="sxs-lookup"><span data-stu-id="7856c-394">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="7856c-395">我們已修正在撰寫新電子郵件訊息時，檢視範本會導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-395">We fixed an issue where viewing a template when composing a new email message would result in a crash.</span></span>

- <span data-ttu-id="7856c-396">我們已修正在 Outlook 版本 1911之後，使用者無法使用 Exchange 2010 公用資料夾的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-396">We fixed an issue where users were unable to Exchange 2010 public folders after Outlook version 1911.</span></span>

- <span data-ttu-id="7856c-397">我們修正了 Office 功能區中群組行事曆分類按鈕已停用的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-397">We fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>

- <span data-ttu-id="7856c-398">解決了 Outlook 無法啟用 [資料遺失保護原則] 提示使用 M365 商務版進階方案並為此服務付款的的使用者之問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-398">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="7856c-399">已解決導致 Outlook 在某些 Windows 組建上當機的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-399">Addressed an issue that caused Outlook to crash on some Windows builds.</span></span>

- <span data-ttu-id="7856c-400">我們修正了使用者無法與來賓使用者共用行事曆的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-400">We fixed an issue where users were unable to share a calendar with a guest user.</span></span>

- <span data-ttu-id="7856c-401">我們修正了使用者看到將午夜臨界值視為全天事件的行事曆專案的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-401">We fixed an issue where users saw calendar items that spanned the midnight threshold as All day events.</span></span>

- <span data-ttu-id="7856c-402">我們修正了導致使用者在高 DPI 監視器上遺失 [線上封存] 摘要的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-402">We fixed an issue that resulted in the Online Archive dropdown in folder properties to be missing for users on high DPI monitors.</span></span>

- <span data-ttu-id="7856c-403">我們修正了當使用者在資料夾之間移動專案時，BeforeItemMove 事件未正確觸發的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-403">We fixed an issue where the Folder.BeforeItemMove event didn't fire correctly when a user moved items between folders.</span></span>

- <span data-ttu-id="7856c-404">我們修正了當兩個增益集將按鈕新增到功能區中相同群組時，Outlook 發生當端的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-404">We fixed an issue where Outlook crashed when two add-ins added a button to the same group in the ribbon.</span></span>

- <span data-ttu-id="7856c-405">我們修正了當處理純文字電子郵件中的超連結時，會導致使用者遇到 Outlook 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-405">We fixed an issue that caused users to experience a crash in Outlook when working with hyperlinks in Plain Text emails.</span></span>

- <span data-ttu-id="7856c-406">我們已修正導致 Outlook 無法剖析使用 RFC2231 編碼的長檔名的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-406">We fixed an issue that caused Outlook to be unable to parse long file names encoded with RFC2231.</span></span>

- <span data-ttu-id="7856c-407">我們修正了導致 Outlook 使用者在使用螢幕閱讀器時遇到間歇性的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-407">We fixed an issue that was causing Outlook users to experience intermittent hangs when using screen readers.</span></span>

- <span data-ttu-id="7856c-408">我們修正了會造成具有衝突連絡人的使用者在 Outlook 中遭遇當機的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-408">We fixed an issue that would cause users with conflicting contacts to experience crashes in Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7856c-409">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7856c-409">PowerPoint</span></span>

- <span data-ttu-id="7856c-410">我們已修正使用表單型驗證開啟伺服器設定的檔案時發生的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-410">We fixed an issue with opening server-configured files with forms-based authentication.</span></span>

- <span data-ttu-id="7856c-411">我們修正了內嵌圖表/活頁簿的 PowerPoint 檔案可能會導致儲存檔案失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-411">We fixed an issue where PowerPoint files with embedded charts / workbooks could result in failures when saving the file.</span></span>

- <span data-ttu-id="7856c-412">我們修正了放大和縮小簡報區域會造成縮放選取選框和滑鼠指標之間的間隙的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-412">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

- <span data-ttu-id="7856c-413">我們修正了使用滑鼠滾輪縮放後，投影片並未居中的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-413">We fixed an issue where slides were not centered after zooming using the mouse wheel.</span></span>

- <span data-ttu-id="7856c-414">我們已修正使用英文 (瑞士) (QWERTZ) 鍵盤時鍵盤快速鍵和拼字檢查無法正常運作的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-414">We fixed an issue where keyboard shortcuts and spell check wouldn’t function as expected when using an English Switzerland (QWERTZ) keyboard.</span></span>

- <span data-ttu-id="7856c-415">我們修正了使用者已關閉的批註窗格會自動開啟的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-415">We fixed an issue where a Comment pane that had been closed by the user would re-open automatically.</span></span>

- <span data-ttu-id="7856c-416">我們已修正某張投影片的投影片編輯工具會在下一張投影片上重疊的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-416">We fixed an issue where the slide editor from one slide would overlap on to the next slide.</span></span>

### <a name="project"></a><span data-ttu-id="7856c-417">專案</span><span class="sxs-lookup"><span data-stu-id="7856c-417">Project</span></span>

- <span data-ttu-id="7856c-418">已修正當專案摘要工作-或是專案[開始/工作]欄位有變更時，ProjectBeforeTaskChange 事件不會觸發的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-418">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

- <span data-ttu-id="7856c-419">已修正當標示為100% 完成之工作錯誤地變更為完成度低於100% 的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-419">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

- <span data-ttu-id="7856c-420">我們修正了在按一下 [選項] 之後 Project 會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-420">We fixed an issue where Project would crash after clicking on Options.</span></span>

- <span data-ttu-id="7856c-421">我們修正了在刪除母計畫之後，無法刪除或重新指派孤立工作的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-421">We fixed an issue that prevented orphaned tasks from being deleted or re-assigned after their parent plan was deleted.</span></span>

### <a name="visio"></a><span data-ttu-id="7856c-422">Visio</span><span class="sxs-lookup"><span data-stu-id="7856c-422">Visio</span></span>

- <span data-ttu-id="7856c-423">有已修復的依賴代碼迴歸分析。</span><span class="sxs-lookup"><span data-stu-id="7856c-423">There was regression in dependent code which has been fixed.</span></span> <span data-ttu-id="7856c-424">現在，影像會在執行于 SharePoint Onprem 上的 Visio 服務中呈現。</span><span class="sxs-lookup"><span data-stu-id="7856c-424">Now, the images are getting rendered in Visio services running on SharePoint Onprem.</span></span>

### <a name="word"></a><span data-ttu-id="7856c-425">Word</span><span class="sxs-lookup"><span data-stu-id="7856c-425">Word</span></span>

- <span data-ttu-id="7856c-426">我們修正了批註窗格中的時間戳記不是根據系統區域設定時間所建立的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-426">We fixed an issue where timestamps in Comment panes were not based on the system locale time.</span></span>

- <span data-ttu-id="7856c-427">已解決在 URL 包含查詢元件時，從自訂檔傳遞（aspx）開啟 Word 檔的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-427">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>

- <span data-ttu-id="7856c-428">我們修正了在批註窗格中複製及貼上文字不會顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-428">We fixed an issue where copy and pasting text to a comment pane would not be displayed.</span></span>

- <span data-ttu-id="7856c-429">我們修正了批註中的超連結無法正常運作的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-429">We fixed an issue where hyperlinks in comments weren’t working.</span></span>

- <span data-ttu-id="7856c-430">我們修正了放大和縮小簡報區域會造成縮放選取選框和滑鼠指標之間的間隙的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-430">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

- <span data-ttu-id="7856c-431">我們修正了網頁應用程式與傳統型應用程式之間的批註未同步處理的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-431">We fixed an issue where comments between the web app and the desktop application were not in sync.</span></span>

- <span data-ttu-id="7856c-432">我們修正了批註提示泡泡在100% 縮放比例中顯示模糊的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-432">We fixed an issue where comment hint bubbles appeared blurry at 100% zoom.</span></span>

- <span data-ttu-id="7856c-433">我們已修正在空白文件中新增註解卻未執行任何動作的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-433">We fixed an issue where adding a new comment on a blank document wouldn't do anything.</span></span>

- <span data-ttu-id="7856c-434">我們修正了無法將 HTML 貼入行事曆的 WordMail 的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-434">We fixed an issue where pasting HTML into WordMail for Calendar wasn’t working.</span></span>

- <span data-ttu-id="7856c-435">我們修正了在共同撰寫的會話中回復批註有時會導致 Word 停滯的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-435">We fixed an issue where replying to a comment in a co-authored session could sometimes cause Word to freeze.</span></span>

- <span data-ttu-id="7856c-436">我們修正了在含有一百個以上專案的檔中插入或更新索引會導致應用程式當機的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-436">We fixed an issue where inserting or updating an Index in a document containing more than a hundred entries would result in the application crashing.</span></span>

- <span data-ttu-id="7856c-437">我們修正了啟用原則 Word 2007 及更新版本的二進位檔案和範本會導致部分共同撰寫案例失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-437">We fixed an issue where enabling policy Word 2007 and later Binary Documents and Templates would cause some co-authoring cases to fail.</span></span>

- <span data-ttu-id="7856c-438">我們修正了具有自訂 xml 值的檔案在開啟時速度極度緩慢的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-438">We fixed an issue where files with custom xml values opened extremely slowly.</span></span>

- <span data-ttu-id="7856c-439">我們修正了使用長路徑名稱（大於32K）的檔案無法開啟，且未顯示適當的錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-439">We fixed an issue where files with long path names (greater than 32K) would not open and an appropriate error message was not being displayed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="7856c-440">Office 套件</span><span class="sxs-lookup"><span data-stu-id="7856c-440">Office Suite</span></span>

- <span data-ttu-id="7856c-441">我們已經研究並解決了在作業系統關閉後，透過 InTune 進行的 Office 365 專業增強版部署會暫停的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-441">We have investigated and resolved the issue where an Office 365 ProPlus deployment via InTune is paused after an OS shutdown.</span></span>

- <span data-ttu-id="7856c-442">我們修正了 Microsoft Office 的 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。</span><span class="sxs-lookup"><span data-stu-id="7856c-442">We fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="7856c-443">此更新解決了 Microsoft Office 中的一個問題：可能無法在執行時期正確找到 Visual Basic for Applications 專案，這些專案的參照預期透搜尋 PATH 環境變數指定的位置來找到，進而導致VBA 執行時期錯誤。</span><span class="sxs-lookup"><span data-stu-id="7856c-443">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-june-08"></a><span data-ttu-id="7856c-445">版本 2005：6 月 08 日</span><span class="sxs-lookup"><span data-stu-id="7856c-445">Version 2005: June 08</span></span>
<span data-ttu-id="7856c-446">*版本2005（組建12827.20336）*</span><span class="sxs-lookup"><span data-stu-id="7856c-446">*Version 2005 (Build 12827.20336)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="7856c-448">解決的問題</span><span class="sxs-lookup"><span data-stu-id="7856c-448">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="7856c-449">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7856c-449">PowerPoint</span></span>

- <span data-ttu-id="7856c-450">我們修正了取代字型對話方塊中，取代字型下拉清單只會顯示系統中安裝的字型，而不是所安裝的字型的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-450">We have fixed an issue with replace fonts dialog where replace font dropdown only shows fonts within the presentation instead of fonts installed on the system.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-june-04"></a><span data-ttu-id="7856c-452">版本 2005：6 月 04 日</span><span class="sxs-lookup"><span data-stu-id="7856c-452">Version 2005: June 04</span></span>
<span data-ttu-id="7856c-453">*版本2005（組建12827.20320）*</span><span class="sxs-lookup"><span data-stu-id="7856c-453">*Version 2005 (Build 12827.20320)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="7856c-455">功能更新</span><span class="sxs-lookup"><span data-stu-id="7856c-455">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="7856c-456">Access</span><span class="sxs-lookup"><span data-stu-id="7856c-456">Access</span></span>

- <span data-ttu-id="7856c-457">**隨時跟上改變！[日期/時間] 延伸資料類型具有更好的精確度。：** 引進新的和改良的資料類型。</span><span class="sxs-lookup"><span data-stu-id="7856c-457">**Keep up with the times! The Date/Time Extended data type has better precision.:** Introducing a new and improved data type.</span></span>  <span data-ttu-id="7856c-458">為加強與 SQL 的語法相容性，並提高包含日期和時間之記錄的詳細資料和層級，我們正在將 DateTime2 資料類型實施到 Access 中。</span><span class="sxs-lookup"><span data-stu-id="7856c-458">To enhance syntax compatibility with SQL, and to increase accuracy and level of detail in records that include dates and times, we’re implementing the DateTime2 data type into Access.</span></span> <span data-ttu-id="7856c-459">這個額外的日期與時間資料類型，將會包含更大的日期範圍（0001-01-01 到9999-12-31），具有更高的指定時間精準度(以納秒取代秒為單位)，讓您可以提供和執行計算。</span><span class="sxs-lookup"><span data-stu-id="7856c-459">This additional date & time data type will include a larger date range (0001-01-01 through 9999-12-31), with higher-specified time precision (nanoseconds, rather than seconds) that you will be able to provide and perform calculations on.</span></span> <span data-ttu-id="7856c-460">若要啟用，請選取 [新增欄位] > [日期與時間延長]。</span><span class="sxs-lookup"><span data-stu-id="7856c-460">To enable, select New field > Date & Time Extended.</span></span> [<span data-ttu-id="7856c-461">深入了解</span><span class="sxs-lookup"><span data-stu-id="7856c-461">Learn more</span></span>](https://support.office.com/article/708c32da-a052-4cc2-9850-9851042e0024)

### <a name="excel"></a><span data-ttu-id="7856c-462">Excel</span><span class="sxs-lookup"><span data-stu-id="7856c-462">Excel</span></span>

- <span data-ttu-id="7856c-463">**在 Excel 中建立來自 Power BI 資料的樞紐分析表：** 您可以在 Excel 中建立樞紐分析表，只要按幾下滑鼠，就能連線到儲存在 Power BI 的樞紐分析表。</span><span class="sxs-lookup"><span data-stu-id="7856c-463">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span><span data-ttu-id="7856c-464"> 如此一來，您就能獲得樞紐分析表和 Power BI 的最佳效果。</span><span class="sxs-lookup"><span data-stu-id="7856c-464"> Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="7856c-465">使用安全 Power BI 資料集的樞紐分析表以計算、摘要及分析資料。</span><span class="sxs-lookup"><span data-stu-id="7856c-465">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span>

### <a name="outlook"></a><span data-ttu-id="7856c-466">Outlook</span><span class="sxs-lookup"><span data-stu-id="7856c-466">Outlook</span></span>

- <span data-ttu-id="7856c-467">**可讓您從上一個 Outlook 會話中快速重新開啟專案的選項：** 我們新增了一個可快速重新開啟先前 Outlook 會話專案的選項。</span><span class="sxs-lookup"><span data-stu-id="7856c-467">**Option to quickly reopen items from previous Outlook session:** We added an option to quickly reopen items from a previous Outlook session.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="7856c-470">解決的問題</span><span class="sxs-lookup"><span data-stu-id="7856c-470">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="7856c-471">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7856c-471">PowerPoint</span></span>

- <span data-ttu-id="7856c-472">這可修正使用者在同一檔案中同時有新版和舊版批註，因此觸發批註的升級而當機的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-472">This fixes a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>


### <a name="office-suite"></a><span data-ttu-id="7856c-473">Office 套件</span><span class="sxs-lookup"><span data-stu-id="7856c-473">Office Suite</span></span>

- <span data-ttu-id="7856c-474">我們透過設定Bing附加預設安裝驗證設定為true默認，並將MSI返回成功視為安裝成功，而解決了 ValidateInstall 失敗率問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-474">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-may-29"></a><span data-ttu-id="7856c-476">版本 2005：5 月 29 日</span><span class="sxs-lookup"><span data-stu-id="7856c-476">Version 2005: May 29</span></span>
<span data-ttu-id="7856c-477">*版本2005（組建12827.20268）*</span><span class="sxs-lookup"><span data-stu-id="7856c-477">*Version 2005 (Build 12827.20268)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="7856c-479">功能更新</span><span class="sxs-lookup"><span data-stu-id="7856c-479">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="7856c-480">Excel</span><span class="sxs-lookup"><span data-stu-id="7856c-480">Excel</span></span>

- <span data-ttu-id="7856c-481">**工作表視圖：** 排序/篩選，同時與其他人在 Excel 電腦版共同作業。</span><span class="sxs-lookup"><span data-stu-id="7856c-481">**Sheet View:** Sort/filter while collaborating with others in Excel desktop.</span></span>

### <a name="outlook"></a><span data-ttu-id="7856c-482">Outlook</span><span class="sxs-lookup"><span data-stu-id="7856c-482">Outlook</span></span>

- <span data-ttu-id="7856c-483">**新增至 Outlook 快顯通知的其他按鈕：** [快速動作] 按鈕，現在會於在 Windows 10 上執行 Outlook 時顯示在 Outlook 快顯通知中。</span><span class="sxs-lookup"><span data-stu-id="7856c-483">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="7856c-486">解決的問題</span><span class="sxs-lookup"><span data-stu-id="7856c-486">Resolved issues</span></span>



### <a name="outlook"></a><span data-ttu-id="7856c-487">Outlook</span><span class="sxs-lookup"><span data-stu-id="7856c-487">Outlook</span></span>

- <span data-ttu-id="7856c-488">解決了導致 Windows 10 伺服器版本的使用者看到警告防毒軟體狀態：無效的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-488">Addressed an issue that caused users of Windows 10 server versions to see the warning  Antivirus status: Invalid.</span></span> <span data-ttu-id="7856c-489">這個版本的 Windows 支援防毒軟體檢測，但即使已正確安裝防毒軟體，也無法找到防毒軟體。</span><span class="sxs-lookup"><span data-stu-id="7856c-489">This version of Windows supports antivirus detection, but no antivirus was found despite having anti virus correctly installed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="7856c-490">Office 套件</span><span class="sxs-lookup"><span data-stu-id="7856c-490">Office Suite</span></span>

- <span data-ttu-id="7856c-491">當您啟用增益集，而登錄金鑰 HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth 被設為零時，辦公主機視窗會當機。</span><span class="sxs-lookup"><span data-stu-id="7856c-491">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="7856c-492">這變更將修正此問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-492">This change would fix this issue.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-may-21"></a><span data-ttu-id="7856c-494">版本 2005：5 月 21 日</span><span class="sxs-lookup"><span data-stu-id="7856c-494">Version 2005: May 21</span></span>
<span data-ttu-id="7856c-495">*版本2005（組建12827.20210）*</span><span class="sxs-lookup"><span data-stu-id="7856c-495">*Version 2005 (Build 12827.20210)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)




[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="7856c-499">解決的問題</span><span class="sxs-lookup"><span data-stu-id="7856c-499">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="7856c-500">Excel</span><span class="sxs-lookup"><span data-stu-id="7856c-500">Excel</span></span>

- <span data-ttu-id="7856c-501">已修正當 Excel 視窗透過 Teams 共用時，使用 Ctrl + Shift + 方向鍵滑動後，Excel 可能會無法回應的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-501">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>


- <span data-ttu-id="7856c-502">在某些情況下，按一下同一個活頁簿中某個位置的超連結會導致活頁簿被隱藏。</span><span class="sxs-lookup"><span data-stu-id="7856c-502">In some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>


### <a name="outlook"></a><span data-ttu-id="7856c-503">Outlook</span><span class="sxs-lookup"><span data-stu-id="7856c-503">Outlook</span></span>

- <span data-ttu-id="7856c-504">已解決有回應/轉寄標註的clp審查活動的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-504">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>


- <span data-ttu-id="7856c-505">已解決在從系統管理人通知中提交意見反應時，使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-505">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-may-14"></a><span data-ttu-id="7856c-507">版本 2005：5 月 14 日</span><span class="sxs-lookup"><span data-stu-id="7856c-507">Version 2005: May 14</span></span>
<span data-ttu-id="7856c-508">*版本2005（組建12827.20160）*</span><span class="sxs-lookup"><span data-stu-id="7856c-508">*Version 2005 (Build 12827.20160)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="7856c-510">功能更新</span><span class="sxs-lookup"><span data-stu-id="7856c-510">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="7856c-511">Excel</span><span class="sxs-lookup"><span data-stu-id="7856c-511">Excel</span></span>

- <span data-ttu-id="7856c-512">**[自動套用] 或 [建議敏感度] 標籤：** Office 可以根據偵測到的敏感性內容來推薦或自動套用靈敏度標籤。</span><span class="sxs-lookup"><span data-stu-id="7856c-512">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7856c-513">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7856c-513">PowerPoint</span></span>

- <span data-ttu-id="7856c-514">**不需要簡報導覽裝置：有耳塞式耳機就夠了：** 使用您的 Surface Earbuds 控制 PowerPoint 簡報。</span><span class="sxs-lookup"><span data-stu-id="7856c-514">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="7856c-515">重要：您必須在 Windows 10 的 Surface 音訊應用程式中配對 Surface Earbuds，才能使用手勢來控制簡報。</span><span class="sxs-lookup"><span data-stu-id="7856c-515">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="7856c-516">在此取得 Windows 10 上 Surface 音訊應用程式入門的指示。</span><span class="sxs-lookup"><span data-stu-id="7856c-516">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="7856c-517">深入了解</span><span class="sxs-lookup"><span data-stu-id="7856c-517">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

- <span data-ttu-id="7856c-518">**[自動套用] 或 [建議敏感度] 標籤：** Office 可以根據偵測到的敏感性內容來推薦或自動套用靈敏度標籤。</span><span class="sxs-lookup"><span data-stu-id="7856c-518">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="word"></a><span data-ttu-id="7856c-519">Word</span><span class="sxs-lookup"><span data-stu-id="7856c-519">Word</span></span>

- <span data-ttu-id="7856c-520">**[自動套用] 或 [建議敏感度] 標籤：** Office 可以根據偵測到的敏感性內容來推薦或自動套用靈敏度標籤。</span><span class="sxs-lookup"><span data-stu-id="7856c-520">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="7856c-523">解決的問題</span><span class="sxs-lookup"><span data-stu-id="7856c-523">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="7856c-524">Excel</span><span class="sxs-lookup"><span data-stu-id="7856c-524">Excel</span></span>

- <span data-ttu-id="7856c-525">已增加搭配圖表使用的 [自訂誤差線] 對話方塊上儲存格參照 [編輯] 控制項的大小。</span><span class="sxs-lookup"><span data-stu-id="7856c-525">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>

- <span data-ttu-id="7856c-526">修正圖表資料表無法正確呈現日期座標軸中的值的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-526">Fixed an issue where chart data table could render values in a date axis incorrectly.</span></span>

- <span data-ttu-id="7856c-527">修正使用 [頁面配置] 或 [分頁預覽] 之後無法停用分頁符號的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-527">Fixed an issue where page breaks could not be disabled after going into Page Layout or Page Break Preview.</span></span>

- <span data-ttu-id="7856c-528">修正隱藏和取消隱藏具有系列資料的欄之後，圖表線條樣式可能會遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-528">Fixed an issue where chart line styles could be lost after hiding and unhiding columns with series data.</span></span>

- <span data-ttu-id="7856c-529">已修正在已篩選清單中插入欄的時間會比預期更長的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-529">Fixed an issue where inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="7856c-530">已修正列印時表單控制項的核取方塊縮放的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-530">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="7856c-531">已修正當檔案路徑太長時，在檔案重新開啟之後外部連結會停止運作的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-531">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="7856c-532">在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。</span><span class="sxs-lookup"><span data-stu-id="7856c-532">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="7856c-533">在某些情況下，Application.Evaluate (VBA) 無法在使用者定義的函數中運作。</span><span class="sxs-lookup"><span data-stu-id="7856c-533">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="7856c-534">在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。</span><span class="sxs-lookup"><span data-stu-id="7856c-534">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="7856c-535">此變更會修正設定格式化的條件 (CF) 資訊無法正確儲存到 XLSB 檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-535">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

- <span data-ttu-id="7856c-536">這項變更修正了即使 LINEST 函式傳回正確的值，圖表趨勢線的 R 平方值 (在強制 y 截距的情況下) 仍然不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-536">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>

- <span data-ttu-id="7856c-537">此變更修正了自訂圖表趨勢線格式不一定會儲存的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-537">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

- <span data-ttu-id="7856c-538">當您使用舊版的「共用活頁簿」模式，嘗試為活頁簿的新工作表列出變更時，就會發生當機。</span><span class="sxs-lookup"><span data-stu-id="7856c-538">A crash could occur when trying to list changes on a new sheet for a workbook using legacy"Shared Workbook" mode.</span></span>

- <span data-ttu-id="7856c-539">修正啟用 [負值以補色顯示] 選項後，可能無法儲存樞紐分析表中的自訂格式設定的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-539">Fixed the issue where custom formatting in Pivot charts may not be saved when the "Invert if negative" option was enabled.</span></span>

- <span data-ttu-id="7856c-540">修正如果選取 [負值以補色顯示] 選項，可能無法儲存樞紐分析表中單一資料點的自訂格式設定的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-540">Fixed an issue where custom formatting for a single data point in a Pivot chart was not saved if the "Invert if negative" option was selected.</span></span>

- <span data-ttu-id="7856c-541">這項變更修正在 CSV 檔案中上傳 '@' 字元時，會導致將 '@' 字元之後的字串轉換成公式的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-541">This change fixes an issue where the '@' character uploaded in a CSV file, would result in the string after the '@' character to be converted to a formula.</span></span>

- <span data-ttu-id="7856c-542">修正無法正確捨入 SEQUENCE 函數中十進位值的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-542">Fixed an issue where decimal values in the SEQUENCE function were not rounded correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="7856c-543">OneNote</span><span class="sxs-lookup"><span data-stu-id="7856c-543">OneNote</span></span>

- <span data-ttu-id="7856c-544">修正將分行符號儲存為垂直 Tab 的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-544">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="7856c-545">Outlook</span><span class="sxs-lookup"><span data-stu-id="7856c-545">Outlook</span></span>

- <span data-ttu-id="7856c-546">解決會導致使用者無法將個人連絡人群組新增為會議出席者的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-546">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>

- <span data-ttu-id="7856c-547">已修正 Office 功能區中群組行事曆分類按鈕已停用的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-547">Fixed an issue where the categorize button for group calendars in the Office Ribbon was disabled.</span></span>

- <span data-ttu-id="7856c-548">已解決在 Windows 更新後，開啟儲存在本機的 msg 或 .oft 檔案會導致 Outlook 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-548">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="7856c-549">已修正企業客戶沒有執行或無法使用群組資料夾的問題，該問題會導致 Outlook 顯示「沒有回應」的訊息。</span><span class="sxs-lookup"><span data-stu-id="7856c-549">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

- <span data-ttu-id="7856c-550">已解決導致使用者在 Outlook 桌面用戶端中按一下非常長的安全連結時，由於截斷而無法載入的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-550">Addressed an issue that caused very long safelinks that users clicked on in the Outlook Desktop client to fail to load due to truncation.</span></span>

- <span data-ttu-id="7856c-551">修正當與伺服器同步處理時，名稱中包含 DBCS (雙位元組字元集) 字元的 Outlook 資料夾會間斷消失的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-551">Fixed an issue where Outlook folders with names containing DBCS (Double Byte Character Set) characters would intermittently disappear when synchronizing with the server.</span></span> <span data-ttu-id="7856c-552">為此，必須為 Outlook 設定 IMAP 帳戶，並在地區設定設定為日文的系統上執行。</span><span class="sxs-lookup"><span data-stu-id="7856c-552">For this to happen, Outlook had to be configured with an IMAP account and running on a system with the locale set to Japanese.</span></span>

- <span data-ttu-id="7856c-553">已解決會導致為使用者主要信箱以外的信箱所建立的刪除規則變得無效的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-553">Addressed an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>

- <span data-ttu-id="7856c-554">已解決在轉寄加密郵件時導致捨棄附件的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-554">Addressed an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

- <span data-ttu-id="7856c-555">已解決會導致還有 2 個月時間的會議，無法在排程小幫手中顯示會議主題的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-555">Addressed an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>

- <span data-ttu-id="7856c-556">已解決會導致使用者在轉寄大型 HTML 郵件時，看到郵件內文截斷的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-556">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="7856c-557">新增透過群組原則強制執行 S/MIME 預設登入設定的功能。</span><span class="sxs-lookup"><span data-stu-id="7856c-557">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7856c-558">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7856c-558">PowerPoint</span></span>

- <span data-ttu-id="7856c-559">已修正問題：如果使用者建立了註解，但未張貼就關閉 [註解] 窗格，然後開啟新視窗、瀏覽多張投影片並關閉視窗，最後再開啟原始簡報中的 [註解] 窗格，將導致無法使用草稿註解。</span><span class="sxs-lookup"><span data-stu-id="7856c-559">Fixed an issue where if a user created a comment without posting it and closed the Comments pane, then opened a new window, navigated through multiple slides and, closed the window, and finally re-opened the Comments pane in the original presentation, the draft comments would not be available.</span></span>

- <span data-ttu-id="7856c-560">修正了將滑鼠游標移到星號 (\*) 符號，但不會顯示上一次更新文件的日期和使用者姓名。</span><span class="sxs-lookup"><span data-stu-id="7856c-560">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="project"></a><span data-ttu-id="7856c-561">Project</span><span class="sxs-lookup"><span data-stu-id="7856c-561">Project</span></span>

- <span data-ttu-id="7856c-562">在表單檢視中編輯前置/後續任務資料時，會觸發額外的 ProjectBeforeTaskChange 事件。</span><span class="sxs-lookup"><span data-stu-id="7856c-562">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="7856c-563">修正變更連結至 SharePoint 工作清單之專案的面板狀態欄位時，Project 可能當機的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-563">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>

- <span data-ttu-id="7856c-564">修正儲存使用舊版 Project 建立的專案時，Project 可能當機的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-564">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="7856c-565">已修正如果 Project 連線至 Project Web App，且小數分隔符號是逗號，當新增延遲時，TaskDependencies Add 方法會失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-565">Fixed an issue where if Project is connected to Project Web App and the decimal separator is a comma, TaskDependencies Add method fails when Lag is added.</span></span>


### <a name="word"></a><span data-ttu-id="7856c-566">Word</span><span class="sxs-lookup"><span data-stu-id="7856c-566">Word</span></span>

- <span data-ttu-id="7856c-567">修正在 [共同作業] 模式時，在文件中插入註解並不總是成功的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-567">Fixed an issue where inserting comments on a document in collaboration mode would not always work.</span></span>

- <span data-ttu-id="7856c-568">此變更修正在按一下 @ 提及時，[人員卡片] 會閃動的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-568">This change fixes an issue where the People card would flash if the @ mention was clicked.</span></span>

- <span data-ttu-id="7856c-569">啟用「顯示書簽」選項卻不會顯示書簽。</span><span class="sxs-lookup"><span data-stu-id="7856c-569">Enabling the option "Show bookmarks" would not display bookmarks.</span></span> <span data-ttu-id="7856c-570">已修正這個問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-570">This has been fixed.</span></span>

- <span data-ttu-id="7856c-571">修正問題：關閉具有草稿註解的文件時，會在不儲存草稿註解的情況下，提示使用者是否要關閉文件。</span><span class="sxs-lookup"><span data-stu-id="7856c-571">Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments.</span></span> <span data-ttu-id="7856c-572">取消提示會關閉文件，而不是保持文件開啟。</span><span class="sxs-lookup"><span data-stu-id="7856c-572">Cancelling the prompt would close the document rather than leaving it open.</span></span>

- <span data-ttu-id="7856c-573">我們修正了複製及貼上標題的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-573">We fixed an issue in copying and pasting headings.</span></span>

- <span data-ttu-id="7856c-574">已修正翻譯已張貼註解將導致「插入已翻譯的文字失敗」錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-574">Fixed an issue where translating a posted comment would result in the error 'Inserting translated text failed'.</span></span>

- <span data-ttu-id="7856c-575">此變更修正了下列問題：如果已啟用 [顯示功能變數代碼，而非其值] 選項，則含有超連結的文字可能不會顯示。</span><span class="sxs-lookup"><span data-stu-id="7856c-575">This change fixes an issue where text with hyperlinks may not display if the option: "Show field codes instead of their values" was enabled.</span></span>

- <span data-ttu-id="7856c-576">在 Web 檢視/沉浸式閱讀器中，如果已在檢視中，按一下提示會捲動到最上方。</span><span class="sxs-lookup"><span data-stu-id="7856c-576">In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view.</span></span> <span data-ttu-id="7856c-577">已修正這個問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-577">This has been fixed.</span></span>

- <span data-ttu-id="7856c-578">我們已修正一個問題，當嘗試使用新名稱儲存包含巨集的檔案時，無論使用者輸入什麼名稱，都會導致該檔案以.docx 副檔名和檔案名稱 WRO0004.docx 儲存，進而導致文件無法使用。</span><span class="sxs-lookup"><span data-stu-id="7856c-578">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with .docx extension and the filename WRO0004.docx, regardless of what the user entered, rendering the document unusable.</span></span>

### <a name="office-suite"></a><span data-ttu-id="7856c-579">Office 套件</span><span class="sxs-lookup"><span data-stu-id="7856c-579">Office Suite</span></span>

- <span data-ttu-id="7856c-580">當使用者收到將他們移至 Teams Only 的原則時，他們仍然可以使用商務版 Skype Outlook 增益集來排程會議。</span><span class="sxs-lookup"><span data-stu-id="7856c-580">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span>  <span data-ttu-id="7856c-581">在此更新之後，當客戶端讀取指示用戶為 Teams Only 的策略並進入僅限會議加入模式後，您將不再能用商務版 Skype 安排會議。</span><span class="sxs-lookup"><span data-stu-id="7856c-581">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span>  <span data-ttu-id="7856c-582">此外，如果商務版 Skype Outlook 增益集發現商務版 Skype 用戶端處於 [僅限會議加入] 模式，就無法自行啟動。</span><span class="sxs-lookup"><span data-stu-id="7856c-582">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="7856c-583">此更新解決了 Microsoft Office 中的一個問題：可能無法在執行時期正確找到 Visual Basic for Applications 專案，這些專案的參照預期透搜尋 PATH 環境變數指定的位置來找到，進而導致VBA 執行時期錯誤。</span><span class="sxs-lookup"><span data-stu-id="7856c-583">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="7856c-584">此更新修正了 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。</span><span class="sxs-lookup"><span data-stu-id="7856c-584">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-may-11"></a><span data-ttu-id="7856c-586">版本 2004：5 月 11 日</span><span class="sxs-lookup"><span data-stu-id="7856c-586">Version 2004: May 11</span></span>
<span data-ttu-id="7856c-587">*版本 2004 (組建 12730.20270)*</span><span class="sxs-lookup"><span data-stu-id="7856c-587">*Version 2004 (Build 12730.20270)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="7856c-589">功能更新</span><span class="sxs-lookup"><span data-stu-id="7856c-589">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="7856c-590">Excel</span><span class="sxs-lookup"><span data-stu-id="7856c-590">Excel</span></span>

- <span data-ttu-id="7856c-591">**使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦。</span><span class="sxs-lookup"><span data-stu-id="7856c-591">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="outlook"></a><span data-ttu-id="7856c-592">Outlook</span><span class="sxs-lookup"><span data-stu-id="7856c-592">Outlook</span></span>

- <span data-ttu-id="7856c-593">**電子郵件中的改良連結：** 當您包含檔案的連結時，檔案名會取代 URL。</span><span class="sxs-lookup"><span data-stu-id="7856c-593">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="7856c-594">您可以變更權限，讓所有收件者都能存取。</span><span class="sxs-lookup"><span data-stu-id="7856c-594">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="7856c-595">深入了解</span><span class="sxs-lookup"><span data-stu-id="7856c-595">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)<br /><span data-ttu-id="7856c-596">在[部落格文章](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="7856c-596">See details in [blog post](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span></span>

- <span data-ttu-id="7856c-597">**使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦。</span><span class="sxs-lookup"><span data-stu-id="7856c-597">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7856c-598">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7856c-598">PowerPoint</span></span>

- <span data-ttu-id="7856c-599">**使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦。</span><span class="sxs-lookup"><span data-stu-id="7856c-599">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>  [<span data-ttu-id="7856c-600">深入了解</span><span class="sxs-lookup"><span data-stu-id="7856c-600">Learn more</span></span>](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a><span data-ttu-id="7856c-601">Word</span><span class="sxs-lookup"><span data-stu-id="7856c-601">Word</span></span>

- <span data-ttu-id="7856c-602">**使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦。</span><span class="sxs-lookup"><span data-stu-id="7856c-602">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="7856c-605">解決的問題</span><span class="sxs-lookup"><span data-stu-id="7856c-605">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="7856c-606">Outlook</span><span class="sxs-lookup"><span data-stu-id="7856c-606">Outlook</span></span>

- <span data-ttu-id="7856c-607">解決在顯示快顯通知時，使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-607">Addressed an issue that caused users to experience a crash when displaying toast notifications.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-may-04"></a><span data-ttu-id="7856c-609">版本 2004：5 月 4 日</span><span class="sxs-lookup"><span data-stu-id="7856c-609">Version 2004: May 04</span></span>
<span data-ttu-id="7856c-610">*版本 2004 (組建 12730.20250)*</span><span class="sxs-lookup"><span data-stu-id="7856c-610">*Version 2004 (Build 12730.20250)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="7856c-612">功能更新</span><span class="sxs-lookup"><span data-stu-id="7856c-612">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="7856c-613">Outlook</span><span class="sxs-lookup"><span data-stu-id="7856c-613">Outlook</span></span>

- <span data-ttu-id="7856c-614">**更好的結果—瞬間：** 我們更新了搜尋體驗，讓這個版本比以往更聰明、更快速，且更可靠。</span><span class="sxs-lookup"><span data-stu-id="7856c-614">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="7856c-615">深入了解</span><span class="sxs-lookup"><span data-stu-id="7856c-615">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="7856c-616">**IT 系統管理員的事件通知：** Microsoft 365 租用戶全域系統管理員和 Office 應用程式系統會在 Windows 版 Outlook 的新右側面板中收到影響其使用者的 Outlook 和 O365 Exchange 事件通知。</span><span class="sxs-lookup"><span data-stu-id="7856c-616">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="7856c-617">深入了解</span><span class="sxs-lookup"><span data-stu-id="7856c-617">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="7856c-620">解決的問題</span><span class="sxs-lookup"><span data-stu-id="7856c-620">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="7856c-621">Office 套件</span><span class="sxs-lookup"><span data-stu-id="7856c-621">Office Suite</span></span>

- <span data-ttu-id="7856c-622">此更新修正了 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。</span><span class="sxs-lookup"><span data-stu-id="7856c-622">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-april-29"></a><span data-ttu-id="7856c-624">版本 2004：4 月 29 日</span><span class="sxs-lookup"><span data-stu-id="7856c-624">Version 2004: April 29</span></span>
<span data-ttu-id="7856c-625">*版本 2004 (組建 12730.20236)*</span><span class="sxs-lookup"><span data-stu-id="7856c-625">*Version 2004 (Build 12730.20236)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="7856c-627">功能更新</span><span class="sxs-lookup"><span data-stu-id="7856c-627">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="7856c-628">Outlook</span><span class="sxs-lookup"><span data-stu-id="7856c-628">Outlook</span></span>

- <span data-ttu-id="7856c-629">**協助保護群組中的資料：** 建立群組時所選擇的「敏感度」標籤會套用到群組電子郵件、文件及小組網站。</span><span class="sxs-lookup"><span data-stu-id="7856c-629">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="7856c-632">解決的問題</span><span class="sxs-lookup"><span data-stu-id="7856c-632">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="7856c-633">Outlook</span><span class="sxs-lookup"><span data-stu-id="7856c-633">Outlook</span></span>

- <span data-ttu-id="7856c-634">解決導致 Outlook 在某些 Windows 組建上當機的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-634">Addresses an issue that caused Outlook to crash on some builds of Windows.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-april-25"></a><span data-ttu-id="7856c-636">版本 2004：4 月 25 日</span><span class="sxs-lookup"><span data-stu-id="7856c-636">Version 2004: April 25</span></span>
<span data-ttu-id="7856c-637">*版本 2004 (組建 12730.20206)*</span><span class="sxs-lookup"><span data-stu-id="7856c-637">*Version 2004 (Build 12730.20206)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="7856c-639">解決的問題</span><span class="sxs-lookup"><span data-stu-id="7856c-639">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="7856c-640">Outlook</span><span class="sxs-lookup"><span data-stu-id="7856c-640">Outlook</span></span>

- <span data-ttu-id="7856c-641">已解決在 Windows 更新後，開啟儲存在本機的 msg 或 .oft 檔案會導致 Outlook 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-641">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

### <a name="project"></a><span data-ttu-id="7856c-642">Project</span><span class="sxs-lookup"><span data-stu-id="7856c-642">Project</span></span>

- <span data-ttu-id="7856c-643">已修正如果您使用的是連線至 Project Web App 的 Project，且小數分隔符號是逗號，當您嘗試將延遲新增至相依性時，TaskDependencies Add 方法會失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-643">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>


### <a name="office-suite"></a><span data-ttu-id="7856c-644">Office 套件</span><span class="sxs-lookup"><span data-stu-id="7856c-644">Office Suite</span></span>

- <span data-ttu-id="7856c-645">此修正可解決同時防止限制存取和保護設有密碼之檔案的錯誤。</span><span class="sxs-lookup"><span data-stu-id="7856c-645">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-april-21"></a><span data-ttu-id="7856c-647">版本 2004：4 月 21 日</span><span class="sxs-lookup"><span data-stu-id="7856c-647">Version 2004: April 21</span></span>
<span data-ttu-id="7856c-648">版本 2004 (組建 12730.20182)\*\*</span><span class="sxs-lookup"><span data-stu-id="7856c-648">*Version 2004 (Build 12730.20182)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="7856c-650">解決的問題</span><span class="sxs-lookup"><span data-stu-id="7856c-650">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="7856c-651">Outlook</span><span class="sxs-lookup"><span data-stu-id="7856c-651">Outlook</span></span>

- <span data-ttu-id="7856c-652">解決導致資料夾窗格寬度意外變更的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-652">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="7856c-653">解決導致使用者在退出 Outlook 時遇到掛斷的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-653">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-april-15"></a><span data-ttu-id="7856c-655">版本 2004：4 月 15 日</span><span class="sxs-lookup"><span data-stu-id="7856c-655">Version 2004: April 15</span></span>
<span data-ttu-id="7856c-656">*版本 2004 (組建 12730.20150)*</span><span class="sxs-lookup"><span data-stu-id="7856c-656">*Version 2004 (Build 12730.20150)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="7856c-658">功能更新</span><span class="sxs-lookup"><span data-stu-id="7856c-658">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="7856c-659">Excel</span><span class="sxs-lookup"><span data-stu-id="7856c-659">Excel</span></span>

- <span data-ttu-id="7856c-660">**Facebook 連接器支援即將結束：** 於 2020 年 4 月起，Excel 就不再支援使用 Facebook 連接器的外部資料連線。</span><span class="sxs-lookup"><span data-stu-id="7856c-660">**Facebook connector support is ending:** Starting in April 2020, Excel will no longer support external data connections that use the Facebook connector.</span></span>

### <a name="outlook"></a><span data-ttu-id="7856c-661">Outlook</span><span class="sxs-lookup"><span data-stu-id="7856c-661">Outlook</span></span>

- <span data-ttu-id="7856c-662">**在 Outlook 中撰寫郵件時有新的選項可停用 @ 提及建議：** 您是否覺得 @ 提及的選擇器很煩人，一點都不好用？</span><span class="sxs-lookup"><span data-stu-id="7856c-662">**New option to disable @ mention suggestions when composing mail in Outlook:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="7856c-663">現在您可以視需要將其關閉了。</span><span class="sxs-lookup"><span data-stu-id="7856c-663">Now you can turn it off if you prefer.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7856c-664">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7856c-664">PowerPoint</span></span>

- <span data-ttu-id="7856c-665">**在簡報時同步處理變更：** 即使簡報處於投影片放映模式，仍可即時同步處理所做的變更。</span><span class="sxs-lookup"><span data-stu-id="7856c-665">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="7856c-666">Word</span><span class="sxs-lookup"><span data-stu-id="7856c-666">Word</span></span>

- <span data-ttu-id="7856c-667">**標註私人複本：** 製作共用文件的私人複本，以建立只有您本人能夠看到的手寫筆記。</span><span class="sxs-lookup"><span data-stu-id="7856c-667">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="7856c-668">若要開始使用，請移至 [檢視] > [建立私人複本]。</span><span class="sxs-lookup"><span data-stu-id="7856c-668">Go to View > Create a Private Copy to get started.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="7856c-671">解決的問題</span><span class="sxs-lookup"><span data-stu-id="7856c-671">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="7856c-672">Access</span><span class="sxs-lookup"><span data-stu-id="7856c-672">Access</span></span>

- <span data-ttu-id="7856c-673">已修正工作窗格中表格的重新調整及重新整理問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-673">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

- <span data-ttu-id="7856c-674">修正國際版 Access 在使用者介面中顯示英文字串的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-674">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="7856c-675">Excel</span><span class="sxs-lookup"><span data-stu-id="7856c-675">Excel</span></span>

- <span data-ttu-id="7856c-676">已修正在工作表上選取儲存格範圍會導致只選取單一儲存格的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-676">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="7856c-677">在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。</span><span class="sxs-lookup"><span data-stu-id="7856c-677">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="7856c-678">已修正在複製含有樞紐分析表的工作表後，會於某些情況下導致 Excel 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-678">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="7856c-679">在某些情況下，Application.Evaluate (VBA) 無法在使用者定義的函式中運作。</span><span class="sxs-lookup"><span data-stu-id="7856c-679">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="7856c-680">修正使用者在以程式設計方式編輯大量儲存格範圍時可能遇到的效能問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-680">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>

- <span data-ttu-id="7856c-681">修正以日文環境開啟 CSV 檔案時發生的效能問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-681">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

- <span data-ttu-id="7856c-682">已修正插入使用者定義的圖表範本來作為預設值會導致其儲存為直條圖的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-682">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="7856c-683">已修正當基礎資料儲存格沒有標題時，圖表上的資料標籤會以空白顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-683">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="7856c-684">已修正在為含有 X 軸範圍的圖表縮減大小時，可能會導致 Excel 停止回應的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-684">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="7856c-685">已修正已啟用 R1C1 儲存格參照且正在共同撰寫/共用的 Excel 工作表，在將游標移到 [使用者目前狀態] 圖示上方時不會以 R1C1 模式顯示作用中儲存格的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-685">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

- <span data-ttu-id="7856c-686">此變更解決了處理格式錯誤或無效通訊協定資訊影像時所導致的延遲問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-686">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="7856c-687">Outlook</span><span class="sxs-lookup"><span data-stu-id="7856c-687">Outlook</span></span>

- <span data-ttu-id="7856c-688">此變更解決了處理格式錯誤或無效通訊協定資訊影像時所導致的延遲問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-688">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="7856c-689">此變更修正了電子郵件草稿最新變更未更新的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-689">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="7856c-690">已修正在檔案上按一下滑鼠右鍵並使用「傳送到」功能無法運作的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-690">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="7856c-691">已解決會導致代理人在不同機器上所看到的共用信箱有不同資料夾階層的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-691">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="7856c-692">已解決會導致類別有時候會從電子郵件訊息中消失的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-692">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="7856c-693">已解決在變更機器上的時區時，會導致某些提醒無法觸發的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-693">Addressed an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

- <span data-ttu-id="7856c-694">已解決在嘗試檢視組織表單的屬性時，會導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-694">Addressed an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="7856c-695">已修正如果使用者有自訂的 [通訊錄] 搜尋路徑，則 Outlook 的名稱解析範圍會限制為自訂路徑，而不是包括全域通訊清單 (GAL) 的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-695">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="7856c-696">解決了會讓 [附件工具] 中的 [儲存至雲端] 按鈕不見的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-696">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="7856c-697">解決了以下問題：當使用者從檢查程式視窗回覆受到數位版權管理的郵件，卻沒有所回覆郵件的擁有者權限時，使用者會無法新增簽名。</span><span class="sxs-lookup"><span data-stu-id="7856c-697">Addressed an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>

- <span data-ttu-id="7856c-698">解決了以下問題：使用者無法從網頁位置將其他附件新增到先前建立的會議。</span><span class="sxs-lookup"><span data-stu-id="7856c-698">Addressed an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

- <span data-ttu-id="7856c-699">解決將附件新增至郵件或從郵件拖放 (與透過功能表相對) 來儲存附件時，導致檔案的「上次修改」日期更新的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-699">Addressed an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

- <span data-ttu-id="7856c-700">解決會導致在展開的尋找窗格中按一下 Enter 時無法開始搜尋，而是會要求使用者按一下 [搜尋] 按鈕的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-700">Addressed an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>

- <span data-ttu-id="7856c-701">已修正在一組傳回的搜尋結果中，依類別結果排序不會顯示類別色彩的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-701">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

- <span data-ttu-id="7856c-702">修正將 [如果有，顯示使用者的照片] 選項停用時，搜尋不會顯示有關使用者的任何資訊的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-702">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="7856c-703">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7856c-703">PowerPoint</span></span>

- <span data-ttu-id="7856c-704">此變更修正了會導致包含 emojis 的 PowerPoint 檔案在儲存時發生失敗的錯誤。</span><span class="sxs-lookup"><span data-stu-id="7856c-704">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

- <span data-ttu-id="7856c-705">此變更修正了在 PowerPoint 或 Word 中呈現內嵌為 OLE 物件的舊版 Excel 圖表時可能不會永遠顯示圖表標題的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-705">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="7856c-706">我們已修正將文字從 Excel 複製到 PowerPoint 時可能會導致其格式設定發生變更的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-706">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="7856c-707">此變更修正了使用 [全字拼寫須相符] 來尋找特殊字元時，不一定能正常運作的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-707">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="7856c-708">Project</span><span class="sxs-lookup"><span data-stu-id="7856c-708">Project</span></span>

- <span data-ttu-id="7856c-709">修正無法正確計算摘要工作日期的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-709">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="7856c-710">修正不先執行 OpenUndoTransaction 方法就不能觸發 OnUndoOrRedo 事件的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-710">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="7856c-711">已修正當使用者按一下 [排程群組] 內 [工作] 功能區中的 [停用] 按鈕時，不會觸發 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) 事件的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-711">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the “Inactivate” button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="7856c-712">如果您在 [表單類型] 檢視中設定前置任務或後置任務詳細資訊，則 ProjectBeforeTaskChange Visual Basic Applications (VBA) 事件不會一律擷取變更。</span><span class="sxs-lookup"><span data-stu-id="7856c-712">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="7856c-713">例如，如果刪除了某個相依性，並在表單上按一下 [確定]，則不會觸發該事件。</span><span class="sxs-lookup"><span data-stu-id="7856c-713">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="7856c-714">已修正此問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-714">This behavior has been fixed.</span></span>

- <span data-ttu-id="7856c-715">已修正在進行變更 (例如日期變更) 之後，實際工作成本 (ACWP) 的最新值不會顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-715">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="7856c-716">已修正使用「最近使用」(MRU) 功能表開啟專案時，會使用 [讀取/寫入] 存取權開啟專案的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-716">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="7856c-717">這項變更修正了如果您建立包含開始日期和時間 (但無工期) 的手動工作，則時間表上的時間顯示不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-717">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="7856c-718">已修正使用回曆列印時間表時，會導致列印檢視中略過或重複一個月的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-718">Fixed an issue where printing a timeline using a Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="7856c-719">這項變更解決了在團隊規劃中使用 GDI 物件時，可能導致 GDI 物件分配過多並產生記憶體不足的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-719">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

- <span data-ttu-id="7856c-720">修正了以下問題：如果執行 'CustomFieldValueListGetItem' 且自訂欄位的查閱資料表不存在，系統會建立一個不應建立的空白查閱資料表。</span><span class="sxs-lookup"><span data-stu-id="7856c-720">Fixed an issue where if CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

- <span data-ttu-id="7856c-721">在表單檢視中編輯前置/後續任務資料時，會觸發額外的 ProjectBeforeTaskChange 事件</span><span class="sxs-lookup"><span data-stu-id="7856c-721">WhenPredecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired</span></span>

- <span data-ttu-id="7856c-722">修正了當開啟保護實際工作的設定時，使用者無法輸入分時期基準工時的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-722">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="7856c-723">Word</span><span class="sxs-lookup"><span data-stu-id="7856c-723">Word</span></span>

- <span data-ttu-id="7856c-724">此變更修正了將游標懸停在提示上並不會醒目提示其卡片的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-724">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="7856c-725">此變更修正了以下問題：從 [檢視] 功能表選取多個頁面時，其中的 [註解] 窗格會顯示為空白。</span><span class="sxs-lookup"><span data-stu-id="7856c-725">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

- <span data-ttu-id="7856c-726">已修正張貼留言功能停用的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-726">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="7856c-727">此變更修正了使用套索選取工具時，群組圖形中的文字會暫時消失的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-727">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="7856c-728">此變更解決了處理格式錯誤或無效通訊協定資訊影像時所導致的延遲問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-728">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="7856c-729">此變更修正了在 PowerPoint 或 Word 中呈現內嵌為 OLE 物件的舊版 Excel 圖表時可能不會永遠顯示圖表標題的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-729">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="7856c-730">這項變更解決了帳戶管理員不會分派訊息而導致協力廠商應用程式懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-730">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="7856c-731">此變更修正了在雙頁檢視中建立註解時，註解錨點不一定會顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-731">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="7856c-732">修正輸入或編輯備註然後使用 Ctrl+A 時，會導致選取畫布中的文字，而不只是選取備註卡片內文字的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-732">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>

- <span data-ttu-id="7856c-733">已修正如果段落的樣式是連結至清單的樣式上階，則該清單的編號可能會遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-733">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

- <span data-ttu-id="7856c-734">這項變更修正了目錄會使用文件中未包含的標題樣式進行更新的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-734">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="7856c-735">我們已修正文件中的文字對齊，在使用 [快速列印] 進行列印之後嘗試進行編輯時變得混亂的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-735">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="7856c-736">我們已修正將兩份文件合併成一份文件時的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-736">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="7856c-737">已修正在寄送文件時，儲存在 Word 文件中的數位簽章會被刪除的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-737">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

- <span data-ttu-id="7856c-738">修正標示的修訂若與方程式有關，在儲存檔案時可能會導致失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-738">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-april-14"></a><span data-ttu-id="7856c-740">版本 2003：4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="7856c-740">Version 2003: April 14</span></span>
<span data-ttu-id="7856c-741">*版本 2003 (組建 12624.20466)*</span><span class="sxs-lookup"><span data-stu-id="7856c-741">*Version 2003 (Build 12624.20466)*</span></span>

<span data-ttu-id="7856c-742">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="7856c-742">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

- <span data-ttu-id="7856c-744">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="7856c-744">Various bugs and performance fixes.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2003-april-09"></a><span data-ttu-id="7856c-746">版本 2003：4 月 9 日</span><span class="sxs-lookup"><span data-stu-id="7856c-746">Version 2003: April 09</span></span>
<span data-ttu-id="7856c-747">*版本 2003 (組建 12624.20442)*</span><span class="sxs-lookup"><span data-stu-id="7856c-747">*Version 2003 (Build 12624.20442)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="7856c-749">功能更新</span><span class="sxs-lookup"><span data-stu-id="7856c-749">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="7856c-750">Excel</span><span class="sxs-lookup"><span data-stu-id="7856c-750">Excel</span></span>

- <span data-ttu-id="7856c-751">**M365 進階版內容選擇器：** 讓您的文件栩栩如生！</span><span class="sxs-lookup"><span data-stu-id="7856c-751">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="7856c-752">探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="7856c-752">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="7856c-753">Outlook</span><span class="sxs-lookup"><span data-stu-id="7856c-753">Outlook</span></span>

- <span data-ttu-id="7856c-754">**M365 進階版內容選擇器：** 讓您的文件栩栩如生！</span><span class="sxs-lookup"><span data-stu-id="7856c-754">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="7856c-755">探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="7856c-755">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7856c-756">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7856c-756">PowerPoint</span></span>

- <span data-ttu-id="7856c-757">**M365 進階版內容選擇器：** 讓您的文件栩栩如生！</span><span class="sxs-lookup"><span data-stu-id="7856c-757">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="7856c-758">探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="7856c-758">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="word"></a><span data-ttu-id="7856c-759">Word</span><span class="sxs-lookup"><span data-stu-id="7856c-759">Word</span></span>

- <span data-ttu-id="7856c-760">**M365 進階版內容選擇器：** 讓您的文件栩栩如生！</span><span class="sxs-lookup"><span data-stu-id="7856c-760">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="7856c-761">探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="7856c-761">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)




[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-april-03"></a><span data-ttu-id="7856c-765">版本 2003：4 月 3 日</span><span class="sxs-lookup"><span data-stu-id="7856c-765">Version 2003: April 03</span></span>
<span data-ttu-id="7856c-766">*版本 2003 (組建 12624.20410)*</span><span class="sxs-lookup"><span data-stu-id="7856c-766">*Version 2003 (Build 12624.20410)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="7856c-768">解決的問題</span><span class="sxs-lookup"><span data-stu-id="7856c-768">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="7856c-769">Excel</span><span class="sxs-lookup"><span data-stu-id="7856c-769">Excel</span></span>

- <span data-ttu-id="7856c-770">使用 VBA 應用程式的 Application.Evaluate 在某些情況下，對使用者定義的函數無法運作。</span><span class="sxs-lookup"><span data-stu-id="7856c-770">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="7856c-771">Outlook</span><span class="sxs-lookup"><span data-stu-id="7856c-771">Outlook</span></span>

- <span data-ttu-id="7856c-772">解決使用滑鼠上的「X」按鈕時，導致使用者偶爾發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-772">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

### <a name="project"></a><span data-ttu-id="7856c-773">Project</span><span class="sxs-lookup"><span data-stu-id="7856c-773">Project</span></span>

- <span data-ttu-id="7856c-774">在表單檢視中編輯前置/後續任務資料時，會觸發額外的 ProjectBeforeTaskChangeevent。</span><span class="sxs-lookup"><span data-stu-id="7856c-774">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChangeevent is fired.</span></span>

### <a name="word"></a><span data-ttu-id="7856c-775">Word</span><span class="sxs-lookup"><span data-stu-id="7856c-775">Word</span></span>

- <span data-ttu-id="7856c-776">解決使用滑鼠上的「X」按鈕時，導致使用者偶爾發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-776">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-march-31"></a><span data-ttu-id="7856c-778">版本 2003：3 月 31 日</span><span class="sxs-lookup"><span data-stu-id="7856c-778">Version 2003: March 31</span></span>
<span data-ttu-id="7856c-779">*版本 2003 (組建 12624.20382)*</span><span class="sxs-lookup"><span data-stu-id="7856c-779">*Version 2003 (Build 12624.20382)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="7856c-781">功能更新</span><span class="sxs-lookup"><span data-stu-id="7856c-781">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="7856c-782">Access</span><span class="sxs-lookup"><span data-stu-id="7856c-782">Access</span></span>

- <span data-ttu-id="7856c-783">**「新增資料表」工作窗格：** Access 的全新「新增資料表」工作窗格終於推出！</span><span class="sxs-lookup"><span data-stu-id="7856c-783">**"Add Tables" Task Pane:** Access's new "Add Tables" Task Pane is finally here!</span></span> <span data-ttu-id="7856c-784">這項功能可讓您輕鬆選取/多重選取要在查詢視窗中新增/移除的資料表，而不需要瀏覽至查詢和關聯視圖的「顯示資料表」對話方塊。</span><span class="sxs-lookup"><span data-stu-id="7856c-784">This feature allows you to easily select/multi-select which tables they'd like to add/remove into a query window, without navigating to the "Show Tables" dialog for queries and for relationship view.</span></span> <span data-ttu-id="7856c-785">這也包含新的「連結」索引標籤，可顯示連結的資料表、可篩選目前清單的搜尋方塊、「拖放」行為及更多功能！</span><span class="sxs-lookup"><span data-stu-id="7856c-785">This also includes a new "links" tab to display linked tables, a search box to filter the current list, "drag and drop" behavior, and more!</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="7856c-788">解決的問題</span><span class="sxs-lookup"><span data-stu-id="7856c-788">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="7856c-789">Project</span><span class="sxs-lookup"><span data-stu-id="7856c-789">Project</span></span>

- <span data-ttu-id="7856c-790"><span style="display:inline !important;">修正了當開啟保護實際工作的設定時，使用者無法輸入分時期基準工時的問題。</span></span><span class="sxs-lookup"><span data-stu-id="7856c-790"><span style="display:inline !important;">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span></span><br>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-march-25"></a><span data-ttu-id="7856c-792">版本 2003：3 月 25 日</span><span class="sxs-lookup"><span data-stu-id="7856c-792">Version 2003: March 25</span></span>
<span data-ttu-id="7856c-793">*版本 2003 (組建 12624.20320)*</span><span class="sxs-lookup"><span data-stu-id="7856c-793">*Version 2003 (Build 12624.20320)*</span></span>

- <span data-ttu-id="7856c-794">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="7856c-794">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-23"></a><span data-ttu-id="7856c-795">版本 2003：3 月 23 日</span><span class="sxs-lookup"><span data-stu-id="7856c-795">Version 2003: March 23</span></span>
<span data-ttu-id="7856c-796">*版本 2003 (組建 12624.20296)*</span><span class="sxs-lookup"><span data-stu-id="7856c-796">*Version 2003 (Build 12624.20296)*</span></span>

- <span data-ttu-id="7856c-797">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="7856c-797">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-21"></a><span data-ttu-id="7856c-798">版本 2003：3 月 21 日</span><span class="sxs-lookup"><span data-stu-id="7856c-798">Version 2003: March 21</span></span>
<span data-ttu-id="7856c-799">*版本 2003 (組建 12624.20276)*</span><span class="sxs-lookup"><span data-stu-id="7856c-799">*Version 2003 (Build 12624.20276)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="7856c-801">功能更新</span><span class="sxs-lookup"><span data-stu-id="7856c-801">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="7856c-802">Outlook</span><span class="sxs-lookup"><span data-stu-id="7856c-802">Outlook</span></span>

- <span data-ttu-id="7856c-803">**加入會議而不需離開您的收件匣：** 不需切換至您的行事曆即可加入線上會議。</span><span class="sxs-lookup"><span data-stu-id="7856c-803">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="7856c-804">將行事曆釘選到 [待辦事項] 窗格之後，只要按一下就能加入任何會議。</span><span class="sxs-lookup"><span data-stu-id="7856c-804">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="7856c-805">**行事曆新版視覺效果：** 去年，我們提供了全新的郵件體驗，而今年將為您帶來嶄新的行事曆！</span><span class="sxs-lookup"><span data-stu-id="7856c-805">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar’s turn to get a facelift!</span></span> <span data-ttu-id="7856c-806">這些更新是全新但令人熟悉的，身為經驗豐富的 Outlook 使用者的您，可以立即上手並更具生產力。</span><span class="sxs-lookup"><span data-stu-id="7856c-806">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7856c-807">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7856c-807">PowerPoint</span></span>

- <span data-ttu-id="7856c-808">**在投影片放映期間更新投影片：** 在簡報期間，更新由其他作者變更的投影片。</span><span class="sxs-lookup"><span data-stu-id="7856c-808">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2003-march-16"></a><span data-ttu-id="7856c-810">版本 2003：3 月 16 日</span><span class="sxs-lookup"><span data-stu-id="7856c-810">Version 2003: March 16</span></span>
<span data-ttu-id="7856c-811">*版本 2003 (組建 12624.20224)*</span><span class="sxs-lookup"><span data-stu-id="7856c-811">*Version 2003 (Build 12624.20224)*</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="7856c-813">功能更新</span><span class="sxs-lookup"><span data-stu-id="7856c-813">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="7856c-814">Excel</span><span class="sxs-lookup"><span data-stu-id="7856c-814">Excel</span></span>

- <span data-ttu-id="7856c-815">**挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。</span><span class="sxs-lookup"><span data-stu-id="7856c-815">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="outlook"></a><span data-ttu-id="7856c-816">Outlook</span><span class="sxs-lookup"><span data-stu-id="7856c-816">Outlook</span></span>

- <span data-ttu-id="7856c-817">**挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。</span><span class="sxs-lookup"><span data-stu-id="7856c-817">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7856c-818">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7856c-818">PowerPoint</span></span>

- <span data-ttu-id="7856c-819">**挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。</span><span class="sxs-lookup"><span data-stu-id="7856c-819">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="word"></a><span data-ttu-id="7856c-820">Word</span><span class="sxs-lookup"><span data-stu-id="7856c-820">Word</span></span>

- <span data-ttu-id="7856c-821">**挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。</span><span class="sxs-lookup"><span data-stu-id="7856c-821">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="office-suite"></a><span data-ttu-id="7856c-822">Office 套件</span><span class="sxs-lookup"><span data-stu-id="7856c-822">Office Suite</span></span>

- <span data-ttu-id="7856c-823">**索引標籤式窗格：** 現在您可以使用應用程式右側的索引標籤 UI，在多個窗格之間切換。</span><span class="sxs-lookup"><span data-stu-id="7856c-823">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="7856c-824">只有當您開啟 2 個以上的窗格時，該 UI 才會顯示。</span><span class="sxs-lookup"><span data-stu-id="7856c-824">The UI will only be visible when you have 2+ panes open.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="7856c-827">解決的問題</span><span class="sxs-lookup"><span data-stu-id="7856c-827">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="7856c-828">Excel</span><span class="sxs-lookup"><span data-stu-id="7856c-828">Excel</span></span>

- <span data-ttu-id="7856c-829">已解決當來源活頁簿關閉時，外部連結無法在填滿時更新的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-829">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

### <a name="outlook"></a><span data-ttu-id="7856c-830">Outlook</span><span class="sxs-lookup"><span data-stu-id="7856c-830">Outlook</span></span>

- <span data-ttu-id="7856c-831">已解決導致使用者在工作管理員中看到 Outlook 處理序延遲的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-831">Addressed an issue that caused users to see the Outlook process lingering in task manager after exiting.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-march-10"></a><span data-ttu-id="7856c-833">版本 2003：3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="7856c-833">Version 2003: March 10</span></span>
<span data-ttu-id="7856c-834">*版本 2003 (組建 12624.20176)*</span><span class="sxs-lookup"><span data-stu-id="7856c-834">*Version 2003 (Build 12624.20176)*</span></span>

<span data-ttu-id="7856c-835">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="7856c-835">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)
### <a name="feature-updates"></a><span data-ttu-id="7856c-837">功能更新</span><span class="sxs-lookup"><span data-stu-id="7856c-837">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="7856c-838">Excel</span><span class="sxs-lookup"><span data-stu-id="7856c-838">Excel</span></span>
- <span data-ttu-id="7856c-839">**敏感度標籤**：您現在可以套用組織設定、用來提示您輸入自訂權限的敏感度標籤。</span><span class="sxs-lookup"><span data-stu-id="7856c-839">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="7856c-840">深入了解</span><span class="sxs-lookup"><span data-stu-id="7856c-840">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a><span data-ttu-id="7856c-841">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7856c-841">PowerPoint</span></span>
- <span data-ttu-id="7856c-842">**敏感度標籤**：您現在可以套用組織設定、用來提示您輸入自訂權限的敏感度標籤。</span><span class="sxs-lookup"><span data-stu-id="7856c-842">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="7856c-843">深入了解</span><span class="sxs-lookup"><span data-stu-id="7856c-843">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a><span data-ttu-id="7856c-844">Word</span><span class="sxs-lookup"><span data-stu-id="7856c-844">Word</span></span>
- <span data-ttu-id="7856c-845">**敏感度標籤**：您現在可以套用組織設定、用來提示您輸入自訂權限的敏感度標籤。</span><span class="sxs-lookup"><span data-stu-id="7856c-845">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="7856c-846">深入了解</span><span class="sxs-lookup"><span data-stu-id="7856c-846">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)
</br>

### <a name="resolved-issues"></a><span data-ttu-id="7856c-847">解決的問題</span><span class="sxs-lookup"><span data-stu-id="7856c-847">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="7856c-848">Excel</span><span class="sxs-lookup"><span data-stu-id="7856c-848">Excel</span></span>

- <span data-ttu-id="7856c-849">修正 [檔案]\[選項] 對話方塊上的 [確定] 按鈕顯示為灰色停用狀態，但功能並未受影響的外觀問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-849">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="7856c-850">修正使用者在重新命名樞紐分析表度量值時可能遇到的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-850">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>

- <span data-ttu-id="7856c-851">修正交叉分析篩選器中的文字在預覽列印中無法正確縮放的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-851">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

- <span data-ttu-id="7856c-852">已修正使用者在使用 VBA 巨集清除範圍內容時可能遇到的效能問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-852">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="7856c-853">已修正當使用者執行與功能區互動的巨集時，導致 UI 快閃的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-853">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>

- <span data-ttu-id="7856c-854">已修正當檔案中的第一個字為 TABLE 時，CSV 檔案載入錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-854">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>

- <span data-ttu-id="7856c-855">已修正當您在兩個具有不同縮放比例的活頁簿之間切換時，使用者可能遇到的當機問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-855">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

- <span data-ttu-id="7856c-856">修正 CUBEVALUE 函數有時會傳回不正確結果的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-856">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="7856c-857">此變更可解決物件模型中的執行階段錯誤，以及當增益集要求的文件/工作表上的主機項目包含具有 noSelect 鎖定的圖形時，應用程式 (Excel、Word) 的潛在當機。</span><span class="sxs-lookup"><span data-stu-id="7856c-857">This change addresses a run-time error in the object model and potential crash of the App (Excel, Word) when Add-ins ask for Host Items on documents/worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="7856c-858">解決導致 Outlook 使用者在同步處理設定時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-858">Addresses an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>



### <a name="outlook"></a><span data-ttu-id="7856c-859">Outlook</span><span class="sxs-lookup"><span data-stu-id="7856c-859">Outlook</span></span>

- <span data-ttu-id="7856c-860">修正使用 Outlook Web Access 建立規則時不會保存到 Exchange 伺服器，並導致衝突的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-860">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>

- <span data-ttu-id="7856c-861">解決導致 Outlook 使用者在同步處理設定時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-861">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

- <span data-ttu-id="7856c-862">修正 Outlook 在深色模式中不會在 [寄件者:] 欄位中顯示下拉式清單的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-862">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>

- <span data-ttu-id="7856c-863">解決即使已關閉記錄，在某些情況下仍導致 Outlook 異常產生記錄輸出的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-863">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

- <span data-ttu-id="7856c-864">已解決當持續整夜執行 Outlook 時，導致使用者無法開啟公用資料夾訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-864">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>

- <span data-ttu-id="7856c-865">已修正在新增 Gmail 帳戶的驗證工作流程中，[權限] 頁面上的 [允許] 和 [拒絕] 按鈕停用的爭用情況。</span><span class="sxs-lookup"><span data-stu-id="7856c-865">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>

- <span data-ttu-id="7856c-866">解決導致使用者無法存取 [空閒/忙碌選項] 行事曆權限對話方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-866">Addressed an issue that caused users to lose access to the &quot;Free Busy Options&quot; calendar permissions dialog.</span></span>

- <span data-ttu-id="7856c-867">修正開啟某些傳送自不同時區的週期性會議執行個體時，可能導致出現警示：「很抱歉，開啟此項目時發生問題」的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-867">Fixed an issue that may result in the alert: &quot;Sorry we're having trouble opening this item&quot; when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="7856c-868">已解決從該郵件拖放附件後造成使用者無法重新開啟 .msg 檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-868">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="7856c-869">修正從 Outlook 上傳檔案附件到 OneDrive 後，造成包含括號之附件名稱的檔案名稱被變更。</span><span class="sxs-lookup"><span data-stu-id="7856c-869">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

- <span data-ttu-id="7856c-870">解決在其他應用程式中開啟某個檔案時，導致使用者無法透過檔案總管將該檔案附加至郵件訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-870">Addressed an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

- <span data-ttu-id="7856c-871">解決導致 Outlook 使用者在同步處理設定時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-871">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7856c-872">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7856c-872">PowerPoint</span></span>

- <span data-ttu-id="7856c-873">修正將滑鼠移至縮圖上時，建議的縮圖閃動的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-873">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="7856c-874">在某些情況下，這可能會導致 PowerPoint 當機。</span><span class="sxs-lookup"><span data-stu-id="7856c-874">In some cases this could cause PowerPoint to crash.</span></span>

- <span data-ttu-id="7856c-875">修正 [檔案]\[選項] 對話方塊上的 [確定] 按鈕顯示為灰色停用狀態，但功能並未受影響的外觀問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-875">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="7856c-876">修正儲存包含 Excel 圖表的 PowerPoint 或 Word 文件會導致失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-876">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>



### <a name="project"></a><span data-ttu-id="7856c-877">Project</span><span class="sxs-lookup"><span data-stu-id="7856c-877">Project</span></span>

- <span data-ttu-id="7856c-878">修正在將任務標示為完成之後，不正確地將任務完成百分比變更為低於 100% 的值的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-878">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="7856c-879">修正不先執行 OpenUndoTransaction 方法就不能觸發 OnUndoOrRedo 事件的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-879">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="7856c-880">修正無法正確計算摘要工作日期的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-880">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

### <a name="visio"></a><span data-ttu-id="7856c-881">Visio</span><span class="sxs-lookup"><span data-stu-id="7856c-881">Visio</span></span>

- <span data-ttu-id="7856c-882">[圖形資訊] 窗格的 [圖案資料] 區段下顯示的詳細資料，與在 Visio 桌面版中開啟該檔案時所顯示的不一致。</span><span class="sxs-lookup"><span data-stu-id="7856c-882">Shape info pane was showing inconsistent details under Shape Data section, with respect to the file when opened in Visio Desktop.</span></span> <span data-ttu-id="7856c-883">已修正此問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-883">It has now been fixed.</span></span>

- <span data-ttu-id="7856c-884">在 2016 之前版本中匯入的點陣圖，由於某些安全性檢查而未呈現。</span><span class="sxs-lookup"><span data-stu-id="7856c-884">Bitmaps imported in versions before 2016 were not being rendered due to some security checks.</span></span> <span data-ttu-id="7856c-885">我們已在 Visio 訂閱中修正此問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-885">We have fixed this issue in Visio Subscription.</span></span>

### <a name="word"></a><span data-ttu-id="7856c-886">Word</span><span class="sxs-lookup"><span data-stu-id="7856c-886">Word</span></span>

- <span data-ttu-id="7856c-887">已修正當滑鼠指標暫留在註解卡片上方時，未醒目提示註解卡片的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-887">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>

- <span data-ttu-id="7856c-888">修正按 Tab 鍵導覽註解卡片時，註解編輯方塊上的焦點無法顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-888">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="7856c-889">修正 [檔案]\[選項] 對話方塊上的 [確定] 按鈕顯示為灰色停用狀態，但功能並未受影響的外觀問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-889">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="7856c-890">在使用中的文件共同撰寫工作階段中，直接在註解卡片中新增影像可能會導致新增標籤。</span><span class="sxs-lookup"><span data-stu-id="7856c-890">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="7856c-891">我們已修正此問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-891">This issue has been fixed.</span></span>

- <span data-ttu-id="7856c-892">在方程式中插入控制項 (例如文字內容控制項)，然後儲存再開啟檔案，便會導致內容無法讀取的錯誤。</span><span class="sxs-lookup"><span data-stu-id="7856c-892">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="7856c-893">修正將先前使用密碼保護的檔案儲存到雲端儲存空間無法運作的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-893">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

- <span data-ttu-id="7856c-894">修正受保護無法編輯之文件的比較功能問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-894">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>




### <a name="office-suite"></a><span data-ttu-id="7856c-895">Office 套件</span><span class="sxs-lookup"><span data-stu-id="7856c-895">Office Suite</span></span>

- <span data-ttu-id="7856c-896">當您將 Multichoice/Lookup/Managed-metadata 屬性與 Word/Excel/PowerPoint 文件一起使用並儲存至 SharePoint 文件庫時，這些屬性之前限制為 255 個字元。</span><span class="sxs-lookup"><span data-stu-id="7856c-896">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="7856c-897">當這些屬性超過 255 個字元時，這類文件就無法儲存。</span><span class="sxs-lookup"><span data-stu-id="7856c-897">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="7856c-898">在此變更中，此限制已增加到 2048 個字元。</span><span class="sxs-lookup"><span data-stu-id="7856c-898">With this change, this limit has been increased to 2048 characters.</span></span>

- <span data-ttu-id="7856c-899">修正 Word/Excel/PowerPoint 中的使用者主體名稱 (UPN) 不再區分大小寫，導致在 SharePoint 上使用檔案時較少發生失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-899">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="7856c-900">修正在 Word/Excel/PowerPoint 中開啟來自相同 SharePoint 文件庫的多個文件時，僅掃描開啟的第一個文件是否符合原則的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-900">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-march-05"></a><span data-ttu-id="7856c-902">版本 2002：3 月 5 日</span><span class="sxs-lookup"><span data-stu-id="7856c-902">Version 2002: March 05</span></span>
<span data-ttu-id="7856c-903">*版本 2002 (組建 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="7856c-903">*Version 2002 (Build 12527.20278)*</span></span>

- <span data-ttu-id="7856c-904">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="7856c-904">Various bugs and performance fixes.</span></span>


## <a name="version-2002-march-04"></a><span data-ttu-id="7856c-905">版本 2002：3 月 4 日</span><span class="sxs-lookup"><span data-stu-id="7856c-905">Version 2002: March 04</span></span>
<span data-ttu-id="7856c-906">*版本 2002 (組建 12527.20264)*</span><span class="sxs-lookup"><span data-stu-id="7856c-906">*Version 2002 (Build 12527.20264)*</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="7856c-908">解決的問題</span><span class="sxs-lookup"><span data-stu-id="7856c-908">Resolved issues</span></span>

### <a name="project"></a><span data-ttu-id="7856c-909">Project</span><span class="sxs-lookup"><span data-stu-id="7856c-909">Project</span></span>
- <span data-ttu-id="7856c-910">修正無法正確計算摘要工作日期的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-910">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>


### <a name="office-suite"></a><span data-ttu-id="7856c-911">Office 套件</span><span class="sxs-lookup"><span data-stu-id="7856c-911">Office Suite</span></span>
- <span data-ttu-id="7856c-912">修正在 Word/Excel/PowerPoint 中開啟來自相同 SharePoint 文件庫的多個文件時，僅掃描開啟的第一個文件是否符合原則的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-912">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-march-01"></a><span data-ttu-id="7856c-914">版本 2002：3 月 1 日</span><span class="sxs-lookup"><span data-stu-id="7856c-914">Version 2002: March 01</span></span>
<span data-ttu-id="7856c-915">*版本 2002 (組建 12527.20242)*</span><span class="sxs-lookup"><span data-stu-id="7856c-915">*Version 2002 (Build 12527.20242)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="7856c-916">解決的問題</span><span class="sxs-lookup"><span data-stu-id="7856c-916">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="7856c-917">Outlook</span><span class="sxs-lookup"><span data-stu-id="7856c-917">Outlook</span></span>

- <span data-ttu-id="7856c-918">解決導致協力廠商應用程式無法傳送電子郵件的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-918">Addresses an issue that caused third party applications to be unable to send email.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-february-24"></a><span data-ttu-id="7856c-920">版本 2002：2 月 24 日</span><span class="sxs-lookup"><span data-stu-id="7856c-920">Version 2002: February 24</span></span>
<span data-ttu-id="7856c-921">*版本 2002 (組建 12527.20194)*</span><span class="sxs-lookup"><span data-stu-id="7856c-921">*Version 2002 (Build 12527.20194)*</span></span>

- <span data-ttu-id="7856c-922">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="7856c-922">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-22"></a><span data-ttu-id="7856c-923">版本 2002：2 月 22 日</span><span class="sxs-lookup"><span data-stu-id="7856c-923">Version 2002: February 22</span></span>
<span data-ttu-id="7856c-924">*版本 2002 (組建 12527.20186)*</span><span class="sxs-lookup"><span data-stu-id="7856c-924">*Version 2002 (Build 12527.20186)*</span></span>

- <span data-ttu-id="7856c-925">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="7856c-925">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-21"></a><span data-ttu-id="7856c-926">版本 2002：2 月 21 日</span><span class="sxs-lookup"><span data-stu-id="7856c-926">Version 2002: February 21</span></span>
<span data-ttu-id="7856c-927">*版本 2002 (組建 12527.20174)*</span><span class="sxs-lookup"><span data-stu-id="7856c-927">*Version 2002 (Build 12527.20174)*</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="7856c-929">功能更新</span><span class="sxs-lookup"><span data-stu-id="7856c-929">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="7856c-930">Access</span><span class="sxs-lookup"><span data-stu-id="7856c-930">Access</span></span>

- <span data-ttu-id="7856c-931">**在查詢設計工具、SQL 檢視和關聯視窗中工作時更具生產力：** 在資料表上按一下滑鼠右鍵即可開啟、設計、調整大小及隱藏它。</span><span class="sxs-lookup"><span data-stu-id="7856c-931">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="7856c-932">在 SQL 檢視中搜尋及取代文字。</span><span class="sxs-lookup"><span data-stu-id="7856c-932">Search and replace text in SQL View.</span></span> <span data-ttu-id="7856c-933">在 [關聯圖] 視窗中選取多個資料表。</span><span class="sxs-lookup"><span data-stu-id="7856c-933">Select multiple tables in the Relationships window.</span></span>

### <a name="outlook"></a><span data-ttu-id="7856c-934">Outlook</span><span class="sxs-lookup"><span data-stu-id="7856c-934">Outlook</span></span>

- <span data-ttu-id="7856c-935">**受限 WiFi 網路的新體驗：** 是否曾經加入需要登入網頁的 WiFi 網路呢？</span><span class="sxs-lookup"><span data-stu-id="7856c-935">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="7856c-936">Outlook 現在會偵測這項要求並協助您取得連結。</span><span class="sxs-lookup"><span data-stu-id="7856c-936">Outlook now detects this and helps you get connected.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="7856c-939">解決的問題</span><span class="sxs-lookup"><span data-stu-id="7856c-939">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="7856c-940">Excel</span><span class="sxs-lookup"><span data-stu-id="7856c-940">Excel</span></span>

- <div style="box-sizing:border-box;"><span data-ttu-id="7856c-941">修正 CUBEVALUE 函數有時會傳回不正確結果的問題。&nbsp;<span style="display:inline !important;"></span></span><span class="sxs-lookup"><span data-stu-id="7856c-941">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.&nbsp;<span style="display:inline !important;"></span></span></span><br>


### <a name="outlook"></a><span data-ttu-id="7856c-942">Outlook</span><span class="sxs-lookup"><span data-stu-id="7856c-942">Outlook</span></span>

- <span data-ttu-id="7856c-943">解決導致會議的位置欄位中的逗號變成分號的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-943">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>


- <span data-ttu-id="7856c-944">解決在多個視窗中檢視相同項目時可能會導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-944">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>


- <span data-ttu-id="7856c-945">解決即使將同步處理滑桿設定為較小的設定，也會導致 Outlook 非預期地同步處理所有郵件的問題。&nbsp;</span><span class="sxs-lookup"><span data-stu-id="7856c-945">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.&nbsp;</span></span>


- <span data-ttu-id="7856c-946">解決會導致使用黑色佈景主題的使用者看到 [從]&quot;&quot; 下拉式功能表在白色背景上顯示白色文字的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-946">Addresses an issue that caused users with Black Theme to see the &quot;From&quot; dropdown show white text on a white background.</span></span>


- <span data-ttu-id="7856c-947"><span style="display:inline !important;">此變更會還原在郵件標頭中檢視多行主旨的功能。</span></span><span class="sxs-lookup"><span data-stu-id="7856c-947"><span style="display:inline !important;">This change restores the ability to view multi-line subjects in the message header.</span></span></span><br>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-february-18"></a><span data-ttu-id="7856c-949">版本 2002：2 月 18 日</span><span class="sxs-lookup"><span data-stu-id="7856c-949">Version 2002: February 18</span></span>
<span data-ttu-id="7856c-950">*版本 2002 (組建 12527.20138)*</span><span class="sxs-lookup"><span data-stu-id="7856c-950">*Version 2002 (Build 12527.20138)*</span></span>

## <a name="version-2002-february-11"></a><span data-ttu-id="7856c-951">版本 2002：2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="7856c-951">Version 2002: February 11</span></span>
<span data-ttu-id="7856c-952">*版本 2002 (組建 12527.20092)*</span><span class="sxs-lookup"><span data-stu-id="7856c-952">*Version 2002 (Build 12527.20092)*</span></span>

<span data-ttu-id="7856c-953">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="7856c-953">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="7856c-955">功能更新</span><span class="sxs-lookup"><span data-stu-id="7856c-955">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="7856c-956">Outlook</span><span class="sxs-lookup"><span data-stu-id="7856c-956">Outlook</span></span>

- <span data-ttu-id="7856c-957">**將電子郵件拖曳到您擁有的群組：** 從您的 [收件匣] 拖曳郵件和交談以將它們移動和複製。</span><span class="sxs-lookup"><span data-stu-id="7856c-957">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="7856c-958">您拖曳的郵件將會與所有群組成員共用。</span><span class="sxs-lookup"><span data-stu-id="7856c-958">Messages you drag will be shared with all group members.</span></span>

### <a name="word"></a><span data-ttu-id="7856c-959">Word</span><span class="sxs-lookup"><span data-stu-id="7856c-959">Word</span></span>

- <span data-ttu-id="7856c-960">**其他人更快速看到您的變更：** 共同撰寫增強功能表示，共同作業者可較以往更快速看到您的變更。</span><span class="sxs-lookup"><span data-stu-id="7856c-960">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

### <a name="office-suite"></a><span data-ttu-id="7856c-961">Office 套件</span><span class="sxs-lookup"><span data-stu-id="7856c-961">Office Suite</span></span>

- <span data-ttu-id="7856c-962">**更清楚的狀態列圖示：** 狀態列圖示現在更容易查看。</span><span class="sxs-lookup"><span data-stu-id="7856c-962">**Clearer status bar icons:** Status bar icons are now easier to see.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="7856c-965">解決的問題</span><span class="sxs-lookup"><span data-stu-id="7856c-965">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="7856c-966">Access</span><span class="sxs-lookup"><span data-stu-id="7856c-966">Access</span></span>

- <span data-ttu-id="7856c-967">Access 範本應不再導致資料庫中的附件欄出現故障。</span><span class="sxs-lookup"><span data-stu-id="7856c-967">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="7856c-968">個體化範本後，您現在應該可以將附件欄新增至資料庫。</span><span class="sxs-lookup"><span data-stu-id="7856c-968">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="7856c-969">此更新會修正使用 ADODB 的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-969">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="7856c-970">VB 程式碼中的記錄器物件可能會不正確地報告錯誤。</span><span class="sxs-lookup"><span data-stu-id="7856c-970">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="7856c-971">此更新修正可能會導致 Microsoft Access 無法識別連結的 SQL Server 資料表中的識別資料行的問題，這可能會導致不正確地將資料列報告為已刪除。</span><span class="sxs-lookup"><span data-stu-id="7856c-971">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>


### <a name="excel"></a><span data-ttu-id="7856c-972">Excel</span><span class="sxs-lookup"><span data-stu-id="7856c-972">Excel</span></span>

- <span data-ttu-id="7856c-973">已修正未顯示操作功能表中的註解命令的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-973">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>


- <span data-ttu-id="7856c-974">已修正以下問題：將文字轉換成具有溢出陣列之儲存格的欄時，某些使用者發生當機。</span><span class="sxs-lookup"><span data-stu-id="7856c-974">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>


- <span data-ttu-id="7856c-975">修正使用「資料剖析」搭配動態陣列時，Excel 會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-975">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="7856c-976">Outlook</span><span class="sxs-lookup"><span data-stu-id="7856c-976">Outlook</span></span>

- <span data-ttu-id="7856c-977">修正以月檢視在行事曆中捲動時，無法顯示之前的行事曆活動的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-977">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="7856c-978">儲存在左側瀏覽窗格 [我的最愛] 的資料夾可能會間歇性消失。</span><span class="sxs-lookup"><span data-stu-id="7856c-978">Folders saved in 'Favorites' in the left navigation pane may intermittently disappear.</span></span>


- <span data-ttu-id="7856c-979">已解決導致使用者在指定無效寄件者地址時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-979">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>


- <span data-ttu-id="7856c-980">已解決導致在某些情況下無法使用相關選項來停用標幟項目醒目提示的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-980">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="7856c-981">已解決導致使用者在取消帳戶設定時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-981">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>


- <span data-ttu-id="7856c-982">修正根據保留原則到期的電子郵件會顯示兩個標籤的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-982">Fixed an issue where emails expiring based on a retention policy would display two labels.</span></span> <span data-ttu-id="7856c-983">其中一個顯示郵件將在一天內過期，另一個則顯示將在兩天內到期。</span><span class="sxs-lookup"><span data-stu-id="7856c-983">One showing that the mail will expire in one day and another displaying that it will expire in two days.</span></span>


- <span data-ttu-id="7856c-984">已解決在 Citrix 環境中檢視 30 個以上的行事曆時，導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-984">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="7856c-985">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7856c-985">PowerPoint</span></span>

- <span data-ttu-id="7856c-986">已修正使用 PowerPoint 筆跡動畫時，無法完整轉譯或跳過的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-986">Fixed an issue where Ink may not render completely or get skipped when used in a PowerPoint ink animations.</span></span>

- <span data-ttu-id="7856c-987">已修正關閉檔案之後，如果有任何事件處理常式正在執行，PowerPoint 就不會立即將它從 [簡報] 集合中移除的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-987">Fixed an issue where After closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="7856c-988">因此，物件模型報告的開啟中簡報數目會不正確，且會防止關閉 PowerPoint。</span><span class="sxs-lookup"><span data-stu-id="7856c-988">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>


- <span data-ttu-id="7856c-989">修正具有深色螢光筆色彩的白色文字，在灰階中會以黑色列印的螢光筆問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-989">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>


### <a name="project"></a><span data-ttu-id="7856c-990">Project</span><span class="sxs-lookup"><span data-stu-id="7856c-990">Project</span></span>

- <span data-ttu-id="7856c-991">已修正以下問題：固定工期類型的 100% 工作可能會誤將其完成百分比計算為小於 100% 完成。</span><span class="sxs-lookup"><span data-stu-id="7856c-991">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>


### <a name="word"></a><span data-ttu-id="7856c-992">Word</span><span class="sxs-lookup"><span data-stu-id="7856c-992">Word</span></span>

- <span data-ttu-id="7856c-993">更新和瀏覽目錄時，有時可能會在文件上顯示灰色區域的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-993">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>


- <span data-ttu-id="7856c-994">修正在已撰寫註解但未張貼，且使用者嘗試儲存檔案的情況下，使用 [瀏覽] 來儲存檔案沒有作用的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-994">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>


- <span data-ttu-id="7856c-995">已修正在註解卡片之間來回切換時，有時會顯示一開始選取的註解，並將某選取範圍醒目提示的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-995">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>


- <span data-ttu-id="7856c-996">已修正在編輯備註之後將文字設為斜體然後再張貼，斜體格式設定遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-996">Fixed an issue where italics formatting is lost after editing a comment, italicizing the text and then posting it.</span></span>


- <span data-ttu-id="7856c-997">已修正在具有「反轉」頁面色彩的閱讀模式中，備註提示未顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-997">Fixed an issue where comment hint was not visible in read mode with Inverse page color.</span></span>


- <span data-ttu-id="7856c-998">已修正共同撰寫文件時，可能不會保留根註解的草稿版本的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-998">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>


- <span data-ttu-id="7856c-999">將 SlideTrack 啟用且 [註解] 窗格關閉時，Ctrl+Alt+M 可能無法開啟 [註解] 窗格的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-999">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>


- <span data-ttu-id="7856c-1000">修正在表格中新增 @提及時可能發生錯誤訊息：「文件中的表格已經毀損」的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-1000">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>


- <span data-ttu-id="7856c-1001">修正備註內容功能表中的備註命令 (編輯備註、回覆備註、刪除備註、解決備註) 未顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-1001">Fixed an issue where comment commands (Edit comment, Reply to comment, Delete comment, Resolve comment) in the comments context menu were not being displayed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="7856c-1002">Office 套件</span><span class="sxs-lookup"><span data-stu-id="7856c-1002">Office Suite</span></span>

- <span data-ttu-id="7856c-1003">解決可能導致挪威耐諾斯克 (nn-no) 校訂工具套件安裝不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-1003">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>


- <span data-ttu-id="7856c-1004">此變更解決使用 Intel Integrated GPU 的圖形配接卡報告問題。</span><span class="sxs-lookup"><span data-stu-id="7856c-1004">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

