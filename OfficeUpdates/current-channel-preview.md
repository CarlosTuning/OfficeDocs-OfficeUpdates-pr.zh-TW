---
title: 版本資訊目前通道 (預覽)
ms.author: anankani
author: anankani
manager: anankani
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為「測試人員 - 慢」對象提供新功能、修正或已知問題的最新清單
ms.openlocfilehash: 712501114acb6e1a14ae8f0c55727ac3e504afe1
ms.sourcegitcommit: ad3ff8ea83a9930956cbb6f30300b0b57d3ef151
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 06/09/2021
ms.locfileid: "52851843"
---
# <a name="release-notes-for-office-current-channel-preview"></a><span data-ttu-id="224d0-103">Office 版本資訊目前通道 (預覽)</span><span class="sxs-lookup"><span data-stu-id="224d0-103">Release Notes for Office Current Channel (Preview)</span></span>

<span data-ttu-id="224d0-104">本文包含 Windows 電腦版之 Word、Excel、PowerPoint、Outlook、Access、Project 與 Teams 目前通道 (預覽) 組建的版本資訊。</span><span class="sxs-lookup"><span data-stu-id="224d0-104">This article contains release notes for Current Channel (Preview) builds of Word, Excel, PowerPoint, Outlook, Access, Project, and Teams for Windows desktop.</span></span> <span data-ttu-id="224d0-105">我們每週都強調有趣的新功能、重要修正，以及我們想讓您知道的重大問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="224d0-106">請注意，我們通常會在一段時間內推出功能 (有時甚至推出修正程式) 至目前通道 (預覽)。</span><span class="sxs-lookup"><span data-stu-id="224d0-106">Note that we often roll out features (and sometimes even fixes) to Current Channel (Preview) over a period of time.</span></span> <span data-ttu-id="224d0-107">這樣可讓我們確保功能都運作順利，然後才推出給更廣泛的對象。</span><span class="sxs-lookup"><span data-stu-id="224d0-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="224d0-108">所以，如果你沒有看到下面描述的項目，不要擔心你最終會得到它。</span><span class="sxs-lookup"><span data-stu-id="224d0-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  


> [!NOTE]
> - <span data-ttu-id="224d0-109">版本資訊發佈日期可能與實際組建發行日期不相符。</span><span class="sxs-lookup"><span data-stu-id="224d0-109">The release notes publication date may not match the actual build release date.</span></span>
> - <span data-ttu-id="224d0-110">Microsoft Teams 功能可能會與最新的目前通道預覽中發行的功能不同，因為它們的發行頻率較高。</span><span class="sxs-lookup"><span data-stu-id="224d0-110">Microsoft Teams features may differ from the latest Current Channel Preview released as they have a more frequent release cadence.</span></span>

[//]: # (DO NOT REMOVE)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

## <a name="version-2106-june-07"></a><span data-ttu-id="224d0-113">版本 2106：6 月 7 日</span><span class="sxs-lookup"><span data-stu-id="224d0-113">Version 2106: June 07</span></span>
<span data-ttu-id="224d0-114">*版本 2106 (組建 14131.20012)*</span><span class="sxs-lookup"><span data-stu-id="224d0-114">*Version 2106 (Build 14131.20012)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-116">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-116">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-117">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-117">Excel</span></span>

- <span data-ttu-id="224d0-118">修正了阻止名稱管理員開啟包含大量隱藏名稱之書籍的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-118">We fixed an issue that prevented the Name Manager from opening books with a large number of hidden names.</span></span>


- <span data-ttu-id="224d0-119">我們已修正填滿大量資料時，影響 VLOOKUP 和 INDEX/MATCH 效能的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-119">We fixed an issue that impacted the performance of VLOOKUP and INDEX/MATCH when filling a large amount of data.</span></span>


- <span data-ttu-id="224d0-120">我們已修正在 RealTimeData 函數參照時，會導致動態陣列無法更新儲存格值的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-120">We fixed an issue that caused Dynamic Arrays to not update cell values when referenced by RealTimeData functions.</span></span>


- <span data-ttu-id="224d0-121">已修正 IME 的 OverType 模式未在字元上輸入，而將字元留在字串結尾的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-121">Fixed an issue where IME's OverType mode was not typing over characters, it left them at the end of the string.</span></span>


- <span data-ttu-id="224d0-122">我們已修正使用凍結窗格時，與使用雙指捲動相關的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-122">We fixed an issue related to two-finger scrolling when using freeze panes.</span></span>


- <span data-ttu-id="224d0-123">我們已修正在大型印表機上列印時，記憶體不足的相關問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-123">We fixed an issue related to out of memory issues when printing on large-format printers.</span></span>


### <a name="outlook"></a><span data-ttu-id="224d0-124">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-124">Outlook</span></span>

- <span data-ttu-id="224d0-125">我們已修正以下問題：在 [僅下載標題] 模式下執行時，使用者看到可行動的訊息在下載後不斷重新整理或回復為標題。</span><span class="sxs-lookup"><span data-stu-id="224d0-125">We fixed an issue that caused users to see actionable messages either constantly refreshing or reverting back to headers after download when running in Download Headers Only mode.</span></span>


- <span data-ttu-id="224d0-126">我們已修正使用者無法在「非商務」授權 Outlook 版本中跨資料夾移動項目的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-126">We fixed an issue where users were unable to move items across folders in "non-business" licensed Outlook versions.</span></span>


- <span data-ttu-id="224d0-127">我們已修正在從存放區移除資料夾時，導致使用者遇到意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-127">We fixed an issue that caused users to experience a unexpected close when removing folders from an archive store.</span></span>


- <span data-ttu-id="224d0-128">我們已修正在載入個人卡片時，導致某些使用者遇到意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-128">We fixed an issue that caused some users to experience a unexpected close when loading person cards.</span></span>


- <span data-ttu-id="224d0-129">我們已修正導致 Outlook 中的人員選擇器針對擁有永久授權的使用者向上展開，而不是向下展開的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-129">We fixed an issue that caused the people picker in Outlook to expand upwards rather than downwards for users with a perpetual license.</span></span>


- <span data-ttu-id="224d0-130">我們已修正導致無法向 Office Perpetual 2021 預覽使用者顯示意見回應選項的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-130">We fixed an issue that caused the feedback option to fail to appear for users of the Office Perpetual 2021 preview.</span></span>


- <span data-ttu-id="224d0-131">已修正導致使用者看到所有寄件備份複本出現在其寄件匣資料夾中的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-131">We fixed an issue that caused users to see copies of all of their sent items appearing in their Outbox folder.</span></span>


- <span data-ttu-id="224d0-132">我們已修正導致自訂網域使用者在將連結貼到電子郵件時，看到權限警告訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-132">We fixed an issue that caused users of custom domains to see a warning message about permissions when pasting a link into an email message.</span></span>


- <span data-ttu-id="224d0-133">我們已新增一個登錄機碼，以停用新會議室尋找工具體驗 (與 Outlook 網頁版相同的體驗)，並啟用具有建議的時間的傳統會議室尋找工具。</span><span class="sxs-lookup"><span data-stu-id="224d0-133">We added a registry key that disables the new Room Finder experience (the same experience as in Outlook for Web) and enables the legacy Room Finder with Suggested Times.</span></span>

    <span data-ttu-id="224d0-134">登錄機碼:</span><span class="sxs-lookup"><span data-stu-id="224d0-134">Registry Key:</span></span>

    ><span data-ttu-id="224d0-135">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar</span><span class="sxs-lookup"><span data-stu-id="224d0-135">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar</span></span> </br>
    > <span data-ttu-id="224d0-136">REG_DWORD “ShowLegacyRoomFinder”</span><span class="sxs-lookup"><span data-stu-id="224d0-136">REG_DWORD “ShowLegacyRoomFinder”</span></span></br></br>
    > <span data-ttu-id="224d0-137">0 (預設值) - 當使用者按一下 [會議室尋找工具] 按鈕以搜尋可用的會議室時，Outlook 會使用新會議室尋找工具 OWA 提供的體驗</span><span class="sxs-lookup"><span data-stu-id="224d0-137">0 (default) - Outlook uses new Room Finder OWA Powered eXperience when user clicks 'Room Finder' button to search for available rooms</span></span>  </br>
    > <span data-ttu-id="224d0-138">1 - Outlook 使用舊版會議室尋找工具 UI 來搜尋可用的會議室</span><span class="sxs-lookup"><span data-stu-id="224d0-138">1 - Outlook uses legacy Room Finder UI to search for available rooms</span></span> </br>


- <span data-ttu-id="224d0-139">我們已修正在其他版本 Windows 中使用大聲朗讀功能時，導致 Word 意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-139">We fixed an issue that caused an expected close when using read aloud with other versions of Windows.</span></span>


- <span data-ttu-id="224d0-140">我們已修正在從存放區移除資料夾時，導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-140">We fixed an issue that caused users to experience a hang when removing folders from an archive store.</span></span>


- <span data-ttu-id="224d0-141">我們已修正在載入個人卡片時，導致某些使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-141">We fixed an issue that caused some users to experience a crash when loading person cards.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="224d0-142">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-142">PowerPoint</span></span>

- <span data-ttu-id="224d0-143">我們已修正在唯讀模式中，會導致無法從演講者備忘稿窗格複製的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-143">We fixed an issue that prevented copying from the speaker notes pane while in Read Only mode.</span></span>


- <span data-ttu-id="224d0-144">我們已修正問題，以確保使用工具列的 [重試儲存] 按鈕儲存的檔案會新增至 [最近的清單]。</span><span class="sxs-lookup"><span data-stu-id="224d0-144">We fixed an issue to ensure that a file saved using the Retry Save button on the bus bar is added to the Recent List.</span></span>


- <span data-ttu-id="224d0-145">修正少數使用者無法使用 [重複使用投影片] 選項的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-145">Fixed an issue where Reuse Slides option was not available for few users.</span></span>


### <a name="project"></a><span data-ttu-id="224d0-146">Project</span><span class="sxs-lookup"><span data-stu-id="224d0-146">Project</span></span>

- <span data-ttu-id="224d0-147">我們已修正手動排程工作上的指派可能會移至不正確日期的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-147">We fixed an issue where assignments on manually scheduled tasks could be moved to an incorrect date.</span></span>


- <span data-ttu-id="224d0-148">我們已修正資源資料庫沒有回應且無法開啟的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-148">We fixed an issue where the resource pool was unresponsive and couldn't be opened.</span></span>


- <span data-ttu-id="224d0-149">我們已修正當您建立使用具有特定日期或時間參數之 ProjectDate */ProjectDur* 函數的自訂欄位公式時，產生錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-149">We fixed an issue where an error was generated if you created a custom field formula that used the ProjectDate */ProjectDur* functions with specific date or time parameters.</span></span>


### <a name="word"></a><span data-ttu-id="224d0-150">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-150">Word</span></span>

- <span data-ttu-id="224d0-151">已修正註解張貼後，暫時呈現空白的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-151">Fixes an issue where a  comment is temporarily blank after posting.</span></span>


- <span data-ttu-id="224d0-152">我們已修正即使在使用者選擇捨棄變更之後，還是顯示另存新檔錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-152">We fixed an issue where a Save As error message was displayed even after a user chose to discard changes.</span></span>


- <span data-ttu-id="224d0-153">我們已修正會使得影像無法在新式註解中張貼的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-153">We fixed an issue that prevented images from being posted in modern comments.</span></span>


- <span data-ttu-id="224d0-154">我們已修正按下 ctrl + shift + @ 等按鍵組合時，不會產生預期的重音符號 (在此案例中為 'å') 的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-154">We fixed an issue where pressing key combinations such as ctrl + shift + @ would not produce the expected accented character( in this case, 'å').</span></span>


- <span data-ttu-id="224d0-155">我們已修正與影像壓縮相關的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-155">We fixed an issue related to image compression.</span></span>


- <span data-ttu-id="224d0-156">我們已修正 [檢閱] 窗格可能會捲動或似乎捲動，但未與選取的註解一致的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-156">We fixed an issue where the Reviewing pane could scroll or appear to scroll but didn't align with selected comment.</span></span>


- <span data-ttu-id="224d0-157">我們已修正將文件匯出為 PDF 時，某些註解未儲存的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-157">We fixed an issue where some comments were not saved when exporting a document to PDF.</span></span>


- <span data-ttu-id="224d0-158">我們已修正在套用 [限制編輯] 時，於文件未受保護的區域中無法編輯新註解的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-158">We fixed an issue that prevented the editing of a new comment in an unprotected area of a document when Restricted Editing is applied.</span></span>


- <span data-ttu-id="224d0-159">我們已修正不需要的捲動動畫相關的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-159">We fixed an issue related to unneeded scrolling animation.</span></span>


- <span data-ttu-id="224d0-160">已修正導致 [註解] 窗格意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-160">Fixed an issue where the comments pane closed unexpectedly.</span></span>


- <span data-ttu-id="224d0-161">我們已修正選取註解時，未強調顯示註解的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-161">We fixed an issue where comments aren't highlighted when selected.</span></span>


- <span data-ttu-id="224d0-162">我們已修正在新建立的註解以外之處按一下時，導致文件中選取範圍無法清除的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-162">We fixed an issue that caused the selection in the document to not be cleared when clicking outside a newly created comment.</span></span>


- <span data-ttu-id="224d0-163">我們已修正若檔案名稱包含 DBSC 字元時，無法將電子郵件附件複製到其他非 Word 應用程式的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-163">We fixed an issue where copying a mail attachment to an application other than Word would fail if the filename included DBCS characters.</span></span>


- <span data-ttu-id="224d0-164">我們已修正在其他版本 Windows 中使用大聲朗讀功能時，導致 Word 意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-164">We fixed an issue that caused an expected close when using read aloud with other versions of Windows.</span></span>


- <span data-ttu-id="224d0-165">修正拼字及文法檢查用畫布內容卡顯示圖示按鈕，但那些按鈕沒有工具提示的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-165">Fixed an issue where canvas contextual cards for spelling and grammar show icon buttons, but those buttons have no tooltips.</span></span>


- <span data-ttu-id="224d0-166">我們已修正導致 [編輯器] 窗格佈景主題與系統佈景主題不一致的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-166">We fixed an issue that was causing a mismatch between the Editor pane theme and the system theme.</span></span>


- <span data-ttu-id="224d0-167">已修正 [編輯器] 窗格無法開啟的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-167">Fixed an issue where the Editor Pane doesn't open.</span></span>


- <span data-ttu-id="224d0-168">已修正在 [編輯器] 中切換至 [拼字類別] 時，相似性波浪線無法消失的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-168">Fixed an issue where similarity squiggles do not dissapear when switching to Spelling category in the Editor.</span></span>


- <span data-ttu-id="224d0-169">我們已修正 Word 有時會在文字周圍顯示不應該出現的框線的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-169">We fixed an issue where Word sometimes displayed a border around text that should not have been there.</span></span>


- <span data-ttu-id="224d0-170">我們已修正當特殊字型旋轉 90 度時，特殊字型的字元間距增加問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-170">We fixed an issue where character spacing increases for specific fonts when rotating them 90 degrees.</span></span>


- <span data-ttu-id="224d0-171">我們已修正當執行巨集時，如果已套用編輯限制，會更新錯誤欄位的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-171">We fixed an issue where the wrong field is getting updated when running a macro if editing restrictions are applied.</span></span>


- <span data-ttu-id="224d0-172">我們已修正多位使用者在共同撰寫時，有時會遺失註解回覆的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-172">We fixed an issue where comment replies were sometimes lost when coauthoring with multiple users.</span></span>


- <span data-ttu-id="224d0-173">我們已修正處理大型文件相關的效能問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-173">We fixed a performance issue related to working with large documents.</span></span>


- <span data-ttu-id="224d0-174">我們已修正部分 Word 檔案因為書籤損毀而無法開啟的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-174">We fixed an issue where some Word files don't open because of corrupt bookmarks.</span></span>


### <a name="office-suite"></a><span data-ttu-id="224d0-175">Office 套件</span><span class="sxs-lookup"><span data-stu-id="224d0-175">Office Suite</span></span>

- <span data-ttu-id="224d0-176">我們已修正 CLP 功能先前導致了自動儲存至 SyncBacked 檔案 (由 OneDrive 同步檔案) 的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-176">We fixed an issue where the CLP feature previously caused unprompted saves to the SyncBacked file (File synced by OneDrive).</span></span>


- <span data-ttu-id="224d0-177">我們已修正使用者無法編輯儲存於 OnPrem 伺服器中的檔案問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-177">We fixed an issue where the user was unable to edit files stored in OnPrem servers.</span></span>


- <span data-ttu-id="224d0-178">已修正開啟 SyncBacked 檔案時出現效能迴歸的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-178">Fixed a performance regression on opening SyncBacked files.</span></span>


- <span data-ttu-id="224d0-179">我們已修正 OneDrive 在確實無合併衝突發生時，顯示合併錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-179">We fixed an issue where OneDrive would display a merge error message when there was indeed no merge conflict.</span></span>


- <span data-ttu-id="224d0-180">我們已修正使用不同帳戶登入可能會導致關機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-180">We fixed an issue where signing in with a different account could result in a shutdown.</span></span>


- <span data-ttu-id="224d0-181">我們已修正 SVG 物件轉換成圖形時 Z 順序的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-181">We fixed an issue related to z-order of SVG objects when converted to shapes.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2105-june-04"></a><span data-ttu-id="224d0-183">版本 2105：6 月 04 日</span><span class="sxs-lookup"><span data-stu-id="224d0-183">Version 2105: June 04</span></span>
<span data-ttu-id="224d0-184">*版本 2105 (組建 14026.20264)*</span><span class="sxs-lookup"><span data-stu-id="224d0-184">*Version 2105 (Build 14026.20264)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-186">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-186">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-187">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-187">Excel</span></span>

- <span data-ttu-id="224d0-188">**資料類型偵測設定：** 在 Excel 中使用Power Query 從未結構化來源匯入資料時，設定資料類型偵測行為</span><span class="sxs-lookup"><span data-stu-id="224d0-188">**Data type detection settings:** Configure the data type detection behavior when importing data from unstructured sources with Power Query in Excel</span></span>

### <a name="word"></a><span data-ttu-id="224d0-189">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-189">Word</span></span>

- <span data-ttu-id="224d0-190">**書寫樣式：** 書寫樣式精選評論是以使用者已選取的正式性等級為依據</span><span class="sxs-lookup"><span data-stu-id="224d0-190">**Writing Styles:** Writing Styles curates critiques based on users' selected formality level</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-193">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-193">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-194">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-194">Excel</span></span>

- <span data-ttu-id="224d0-195">已修正部分使用者在 Excel 增益集清單中顯示額外項目的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-195">We fixed an issue where extra entries appeared in the Excel Add-in list for some users.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2105-june-01"></a><span data-ttu-id="224d0-197">版本 2105：6 月 1 日</span><span class="sxs-lookup"><span data-stu-id="224d0-197">Version 2105: June 01</span></span>
<span data-ttu-id="224d0-198">*版本 2105 (組建 14026.20254)*</span><span class="sxs-lookup"><span data-stu-id="224d0-198">*Version 2105 (Build 14026.20254)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-200">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-200">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-201">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-201">Outlook</span></span>

- <span data-ttu-id="224d0-202">**上次登入/可疑的登入：** Outlook 現在會告知您上次登入帳戶的時間及位置，並警示您是否偵測到任何可疑的登入活動</span><span class="sxs-lookup"><span data-stu-id="224d0-202">**Last Sign In / Suspicious Sign In:** Outlook now tells you when and where you last signed into your account, and alerts you if any suspicious sign-in activity is detected</span></span>

- <span data-ttu-id="224d0-203">**開啟共用行事曆改良功能：** 針對 Office 365 中的共用行事曆，Outlook 可以使用 REST API 更新這些行事曆。</span><span class="sxs-lookup"><span data-stu-id="224d0-203">**Turn on shared calendar improvements:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="224d0-204">開啟預覽，以更快速且更可靠地更新共用行事曆。</span><span class="sxs-lookup"><span data-stu-id="224d0-204">Turn on the preview for faster and more reliable updates to shared calendars.</span></span><br /><span data-ttu-id="224d0-205">在[部落格文章](https://insider.office.com/zh-TW/blog/shared-calendars-improvements-in-outlook-for-windows)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="224d0-205">See details in [blog post](https://insider.office.com/zh-TW/blog/shared-calendars-improvements-in-outlook-for-windows)</span></span>

- <span data-ttu-id="224d0-206">**將電子郵件傳送給大型 DL、外部使用者時，協助工具檢查程式會進行微調：** 我們新增了功能，以在撰寫電子郵件給大量對象、外部使用者等時，透過郵件提示自動收到協助工具違規的提示。這些設定放在輕鬆存取中</span><span class="sxs-lookup"><span data-stu-id="224d0-206">**Accessibility Checker nudge when sending emails to large DL, external users:** We added the functionally to get prompted automatically, through a mailtip, of an accessibility violation while composing an email to large audiences, external users, etc. These settings live in the Ease of Access</span></span><br /><span data-ttu-id="224d0-207">在[部落格文章](https://insider.office.com/zh-TW/blog/sending-accessible-emails-in-outlook-for-windows)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="224d0-207">See details in [blog post](https://insider.office.com/zh-TW/blog/sending-accessible-emails-in-outlook-for-windows)</span></span>

### <a name="visio"></a><span data-ttu-id="224d0-208">Visio</span><span class="sxs-lookup"><span data-stu-id="224d0-208">Visio</span></span>

- <span data-ttu-id="224d0-209">**AWS 樣版和圖形：** 我們現在的樣版包含最新的 AWS 圖形，可協助您建立圖表。</span><span class="sxs-lookup"><span data-stu-id="224d0-209">**AWS stencils and shapes:** We now have stencils with the latest AWS shapes to help you create diagrams.</span></span> [<span data-ttu-id="224d0-210">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-210">Learn more</span></span>](https://support.office.com/article/138206bf-d10f-4583-9f31-885ce706af49)




[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-213">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-213">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-214">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-214">Outlook</span></span>

- <span data-ttu-id="224d0-215">我們已修正與 Outlook 郵件或行事曆檢視互動時，可能會導致意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-215">We fixed an issue that may cause a unexpected close when interacting with Outlook Mail or Calendar Views.</span></span>




[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2105-may-23"></a><span data-ttu-id="224d0-217">版本 2105：5 月 23 日</span><span class="sxs-lookup"><span data-stu-id="224d0-217">Version 2105: May 23</span></span>
<span data-ttu-id="224d0-218">*版本 2105 (組建 14026.20246)*</span><span class="sxs-lookup"><span data-stu-id="224d0-218">*Version 2105 (Build 14026.20246)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-220">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-220">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="224d0-221">Teams</span><span class="sxs-lookup"><span data-stu-id="224d0-221">Teams</span></span>

- <span data-ttu-id="224d0-222">**推出出席資料儀表板檢視**：您不再需要手動下載報告，Teams 現在可讓您按一下儀表板檢視即可檢視所有彙總資料</span><span class="sxs-lookup"><span data-stu-id="224d0-222">**Announcing attendance data dashboard views:** No longer do you need to manually download reports, Teams now allows you to view all aggregated data in a one click dashboard view</span></span>

- <span data-ttu-id="224d0-223">**應用程式的安全性、合規性和資料保護功能：** 對於 Microsoft 365 認證 Teams 應用程式，系統管理員可以在 Teams 系統管理中心應用程式詳細資料頁面的新索引標籤上檢視安全性、合規性和資料保護功能。</span><span class="sxs-lookup"><span data-stu-id="224d0-223">**Security, compliance, and data protection capabilities for apps:** For Microsoft 365 Certified Teams apps, admins can view security, compliance, and data protection capabilities in a new tab on the app's detail page in the Teams Admin Center.</span></span> <span data-ttu-id="224d0-224">此透明度使得 Microsoft 客戶能夠信任其組織中執行的應用程式。</span><span class="sxs-lookup"><span data-stu-id="224d0-224">This transparency gives Microsoft customers trust in the applications that run their organizations.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-227">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-227">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-228">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-228">Outlook</span></span>

- <span data-ttu-id="224d0-229">我們已修正會導致「縮短會議時間」功能的部分指示透過螢幕閱讀程式技術無法使用的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-229">We fixed an issue that caused some instructions for the "Shorten Meetings" feature to be unavailable through screen reader technologies.</span></span>


- <span data-ttu-id="224d0-230">我們已修正會導致某些使用者在載入個人卡片時遇到意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-230">We fixed an issue that caused some users to experience unexpectedly closed when loading person cards.</span></span>


- <span data-ttu-id="224d0-231">我們已新增一個登錄機碼，以停用新會議室尋找工具體驗 (與 Outlook 網頁版相同的體驗)，並啟用具有建議的時間的傳統會議室尋找工具。</span><span class="sxs-lookup"><span data-stu-id="224d0-231">We added a registry key that disables the new Room Finder experience (the same experience as in Outlook for Web) and enables the legacy Room Finder with Suggested Times.</span></span>
    - <span data-ttu-id="224d0-232">登錄機碼:</span><span class="sxs-lookup"><span data-stu-id="224d0-232">Registry Key:</span></span>

        > <span data-ttu-id="224d0-233">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar</span><span class="sxs-lookup"><span data-stu-id="224d0-233">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar</span></span> </br>
        > <span data-ttu-id="224d0-234">REG_DWORD “ShowLegacyRoomFinder”</span><span class="sxs-lookup"><span data-stu-id="224d0-234">REG_DWORD “ShowLegacyRoomFinder”</span></span></br></br>
        > <span data-ttu-id="224d0-235">0 (預設值) - 當使用者按一下 [會議室尋找工具] 按鈕以搜尋可用的會議室時，Outlook 會使用新會議室尋找工具 OWA 提供的體驗</span><span class="sxs-lookup"><span data-stu-id="224d0-235">0 (default) - Outlook uses new Room Finder OWA Powered eXperience when user clicks 'Room Finder' button to search for available rooms</span></span>  </br>
        > <span data-ttu-id="224d0-236">1 - Outlook 使用舊版會議室尋找工具 UI 來搜尋可用的會議室</span><span class="sxs-lookup"><span data-stu-id="224d0-236">1 - Outlook uses legacy Room Finder UI to search for available rooms</span></span> </br>


### <a name="project"></a><span data-ttu-id="224d0-237">Project</span><span class="sxs-lookup"><span data-stu-id="224d0-237">Project</span></span>

- <span data-ttu-id="224d0-238">修正手動排程工作上的指派可能會移至不正確日期的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-238">Fixed an issue where assignments on manually scheduled tasks may be moved to an incorrect date.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2105-may-19"></a><span data-ttu-id="224d0-240">版本 2105：5 月 19 日</span><span class="sxs-lookup"><span data-stu-id="224d0-240">Version 2105: May 19</span></span>
<span data-ttu-id="224d0-241">*版本 2105 (組建 14026.20202)*</span><span class="sxs-lookup"><span data-stu-id="224d0-241">*Version 2105 (Build 14026.20202)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-243">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-243">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="224d0-244">Teams</span><span class="sxs-lookup"><span data-stu-id="224d0-244">Teams</span></span>

- <span data-ttu-id="224d0-245">**Teams 網路研討會與 Dynamics 365 Marketing 整合，以啟用潛在客戶培養：** 利用這項功能，網路研討會召集人可以運用 D365 Marketing 促進與報名者在活動後的參與。</span><span class="sxs-lookup"><span data-stu-id="224d0-245">**Teams Webinars integrate with Dynamics 365 Marketing to enable lead nurturing:** With this feature, webinar organizers can drive post event engagement with registrants by leveraging D365 Marketing.</span></span> <span data-ttu-id="224d0-246">出席者參與資料會與 D365 Marketin 組織同步，並啟用自動化的使用者旅程</span><span class="sxs-lookup"><span data-stu-id="224d0-246">The attendee engagement data syncs with D365 Marketing org and enabled automated user journeys</span></span>

- <span data-ttu-id="224d0-247">**智慧型喇叭：** 智慧型喇叭是 Windows 上 Microsoft Teams 會議室的智慧周邊設備。</span><span class="sxs-lookup"><span data-stu-id="224d0-247">**Intelligent speakers:** Intelligent speakers are intelligent peripherals for Microsoft Teams Rooms on Windows.</span></span> <span data-ttu-id="224d0-248">他們將為會議室中的參與者帶來歸屬於演講者的抄寫，讓出席者能減少記錄筆記的時間，並輕鬆追蹤在會議室中發言的人。</span><span class="sxs-lookup"><span data-stu-id="224d0-248">They will bring speaker attributed transcription for participants in the meeting room, enabling attendees to spend less time note-taking and easily follow along who said what in the room.</span></span>

- <span data-ttu-id="224d0-249">**讓 Teams 使用者能夠透過 Teams 用戶端購買 Teams 應用程式：** Teams 使用者現在可以從 Teams Store 購買 Teams 應用程式訂閱。</span><span class="sxs-lookup"><span data-stu-id="224d0-249">**Enable Teams users to purchase Teams apps through Teams client:** Teams users have now the ability to purchase Teams app subscriptions from the Teams store.</span></span>

- <span data-ttu-id="224d0-250">**使用 Teams 範本建立團隊：** 使用 Teams 中的範本，使用者可在建立新的團隊時從各種可自訂的範本中選擇，協助他們快速開始使用。</span><span class="sxs-lookup"><span data-stu-id="224d0-250">**Create Teams with Team Templates:** With Templates in Teams, users can choose from a variety of customizable templates when creating a new team, helping them get started quickly.</span></span> <span data-ttu-id="224d0-251">IT 系統管理員也可以為其組織建立新的自訂範本，讓他們能標準化團隊結構、預先安裝相關應用程式，以及擴大最佳做法。</span><span class="sxs-lookup"><span data-stu-id="224d0-251">IT Admins can also create custom templates for their organization, allowing them to standardize team structures, preinstall relevant apps, and scale best practices.</span></span> <span data-ttu-id="224d0-252">IT 系統管理員可以選擇要在 Teams 系統管理中心向使用者顯示哪些團隊範本，也可以將 URL 新增到團隊範本中的網站索引標籤，以預先設定網站頁面。</span><span class="sxs-lookup"><span data-stu-id="224d0-252">IT Admins can choose which team templates to show to end users in Teams Admin Center, and also preconfigure website tabs by adding URLs to a website tab in a team template.</span></span>

- <span data-ttu-id="224d0-253">**在 Teams 中使用 PowerPoint Live 的雷射筆和筆跡標註：** 我們引進了虛擬雷射筆和標註，讓簡報者可以有效分享內容，並吸引觀眾注意 PowerPoint 投影片組的某些部分。</span><span class="sxs-lookup"><span data-stu-id="224d0-253">**Use laser pointer and ink annotations in PowerPoint Live in Teams:** We are introducing virtual laser pointer and annotations so presenters can effectively share content and engage their audience by drawing attention to certain sections of the PowerPoint deck.</span></span> <span data-ttu-id="224d0-254">就像在會議室使用實體雷射筆一樣，PowerPoint Live 可讓您有效地指向不同位置，讓觀眾可以輕鬆地跟上投影片上的內容。</span><span class="sxs-lookup"><span data-stu-id="224d0-254">Just as you would use a physical laser point in a room, PowerPoint Live allows you to effectively point at different places so the audience can easily follow along what’s on the slide.</span></span>

- <span data-ttu-id="224d0-255">**Power Automate 流程建議與 1P 團隊範本：** 適用於從 1P 團隊範本所建立之團隊的 Surface Power Automate 流程範本</span><span class="sxs-lookup"><span data-stu-id="224d0-255">**Power Automate flow recommendations with 1P Team Templates:** Surface Power Automate flow templates for teams created from 1P team templates</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-258">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-258">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-259">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-259">Outlook</span></span>

- <span data-ttu-id="224d0-260">我們已修正導致無法向 Office Perpetual 2021 預覽使用者顯示意見回應選項的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-260">We fixed an issue that caused the feedback option unable to appear for users of the Office Perpetual 2021 preview.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2105-may-12"></a><span data-ttu-id="224d0-262">版本 2105：5 月 12 日</span><span class="sxs-lookup"><span data-stu-id="224d0-262">Version 2105: May 12</span></span>
<span data-ttu-id="224d0-263">*版本 2105 (組建 14026.20164)*</span><span class="sxs-lookup"><span data-stu-id="224d0-263">*Version 2105 (Build 14026.20164)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-265">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-265">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="224d0-266">Teams</span><span class="sxs-lookup"><span data-stu-id="224d0-266">Teams</span></span>

- <span data-ttu-id="224d0-267">**在桌面 (或) 瀏覽器 (或) Teams 中預設開啟檔案的使用者喜好設定：** 使用者可以在開啟 Teams 中共用的 Office (Word、Excel 和 Power Point) 檔案時，將預設喜好設定設定為瀏覽器、桌面或 Teams。如果已安裝並啟用最新的 Office 用戶端，就可以選取桌面設定</span><span class="sxs-lookup"><span data-stu-id="224d0-267">**User preference setting to open files by default in Desktop (or) Browser (or) Teams:** Users can set their default preference as Browser, Desktop or Teams when opening Office (Word, Excel, and Power Point) files that are shared in Teams.Desktop setting can be selected if latest Office clients are installed and activated</span></span>

- <span data-ttu-id="224d0-268">**Teams 會議中的報告者與並排模式：** 現在您可以出現在內容旁邊，以提供更吸引人的簡報和消費體驗</span><span class="sxs-lookup"><span data-stu-id="224d0-268">**Reporter and Side-by-Side Mode in Teams meetings:** You can now appear next to your content for a more engaging presentation and consumption experience</span></span>

- <span data-ttu-id="224d0-269">**Teams 網路研討會功能正式發行：** 排程，並使用您用於會議的相同 Teams 應用程式，提供 1，000 人網路研討會！</span><span class="sxs-lookup"><span data-stu-id="224d0-269">**Teams webinar capabilities general availability:** Schedule and deliver 1,000 person webinars with the same Teams app you use for meetings!</span></span> <span data-ttu-id="224d0-270">網路研討會功能支援註冊頁面建立、報名者的電子郵件確認、出席者影片和音訊的主機管理、出席者報告，以及投票、聊天和回應等互動式功能。</span><span class="sxs-lookup"><span data-stu-id="224d0-270">Webinar capabilities support registration page creation, email confirmation for registrants, host management for attendee video and audio, attendee reporting, plus interactive features like polls, chat and reactions.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-273">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-273">Resolved issues</span></span>
### <a name="word"></a><span data-ttu-id="224d0-274">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-274">Word</span></span>

- <span data-ttu-id="224d0-275">修正拼字及文法檢查用畫布內容卡顯示圖示按鈕，但那些按鈕沒有工具提示的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-275">Fixed an issue where canvas contextual cards for spelling and grammar show icon buttons, but those buttons have no tooltips.</span></span>



[//]: # (請勿移除 BUGDETAILS 內容結尾)

## <a name="version-2105-may-07"></a><span data-ttu-id="224d0-277">版本 2105：5 月 7 日</span><span class="sxs-lookup"><span data-stu-id="224d0-277">Version 2105: May 07</span></span>
<span data-ttu-id="224d0-278">*版本 2105 (組建 14026.20138)*</span><span class="sxs-lookup"><span data-stu-id="224d0-278">*Version 2105 (Build 14026.20138)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-280">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-280">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="224d0-281">Teams</span><span class="sxs-lookup"><span data-stu-id="224d0-281">Teams</span></span>

- <span data-ttu-id="224d0-282">**Teams 會議版面配置簡介：** 現在可以覆蓋在內容之上，以擁有更沈浸式的簡報和消費體驗</span><span class="sxs-lookup"><span data-stu-id="224d0-282">**Introducing layouts to Teams meetings:** Now you can appear overlaid ontop of content for a more immersive presentation and consumption experience</span></span>

- <span data-ttu-id="224d0-283">**停用特定出席者的相機：** 會議召集人和簡報者可以在 Teams 會議中停用特定出席者的相機，以確保他們不會在會議中分享視訊。</span><span class="sxs-lookup"><span data-stu-id="224d0-283">**Disable Camera for Specific Attendees:** Meeting Organizers and Presenters can disable the cameras of specific Attendees in a Teams Meeting to make sure they don't share video in the meeting.</span></span>

- <span data-ttu-id="224d0-284">**停用所有出席者的相機：** 會議召集人和簡報者可以在 Teams 會議中停用所有出席者的相機，以確保他們不會在會議中分享視訊。</span><span class="sxs-lookup"><span data-stu-id="224d0-284">**Disable Camera for All Attendees:** Meeting Organizers and Presenters can disable the cameras of all Attendees in a Teams Meeting to make sure they don't share video in the meeting.</span></span>

- <span data-ttu-id="224d0-285">**匿名使用者可以簡報：** 在主持 Teams 即時活動時，我們新增了匿名使用者加入即時活動的能力，因此他們也可以在活動期間進行簡報。</span><span class="sxs-lookup"><span data-stu-id="224d0-285">**Anonymous users can present:** When hosting a Teams live event, we added the ability for an anonymous users to join a Live Event and so that they can also present during the event.</span></span>

- <span data-ttu-id="224d0-286">**以程式化方式管理 Teams 中的標記 - Microsoft Teams 標記 API 現在為公開預覽：** 這組 API 可用來以程式化方式在小組中指派使用者標記，讓標記建立與維護更快速且更容易。</span><span class="sxs-lookup"><span data-stu-id="224d0-286">**Manage tags in Teams programmatically - Microsoft Teams Tags APIs are now in public preview:** This set of APIs can be used to programmatically assign users tags in a team, making tag creation and maintenance faster and easier.</span></span>  <span data-ttu-id="224d0-287">Teams 中的標記可讓使用者快速連絡一組人員，而不需要 @提及或輸入所有人。</span><span class="sxs-lookup"><span data-stu-id="224d0-287">Tags in Teams let users quickly reach a group of people without having to @mention or type out everyone.</span></span> <span data-ttu-id="224d0-288">如需 Teams 中標記的相關資訊，請參閱在 Teams 中使用標記。</span><span class="sxs-lookup"><span data-stu-id="224d0-288">For more information on tag in teams, see Using tags in Teams.</span></span> <span data-ttu-id="224d0-289">使用這些新 API，開發人員可以在小組中 nowCreate 標記，並在小組中指派 usersGet 標記清單及更新 tagsDelete 標記</span><span class="sxs-lookup"><span data-stu-id="224d0-289">Using these new APIs, developers can nowCreate tags in a team and assign usersGet a list of tags in a team Update tagsDelete tags</span></span>

- <span data-ttu-id="224d0-290">**從 PowerPoint 到 Teams 進行簡報：** PowerPoint 應用程式直接透過 PowerPoint Live 將您的投影片展示到 Teams 會議。</span><span class="sxs-lookup"><span data-stu-id="224d0-290">**Present from PowerPoint to Teams:** Present your slides directly from the PowerPoint app to a Teams meeting via PowerPoint Live.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-293">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-293">Resolved issues</span></span>
### <a name="word"></a><span data-ttu-id="224d0-294">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-294">Word</span></span>

- <span data-ttu-id="224d0-295">修正編輯器窗格無法開啟的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-295">Fixes an issue where the Editor Pane doesn't open.</span></span>


### <a name="office-suite"></a><span data-ttu-id="224d0-296">Office 套件</span><span class="sxs-lookup"><span data-stu-id="224d0-296">Office Suite</span></span>

- <span data-ttu-id="224d0-297">RelNotesNotNeeded</span><span class="sxs-lookup"><span data-stu-id="224d0-297">RelNotesNotNeeded</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2105-may-03"></a><span data-ttu-id="224d0-299">版本 2105：5 月 3 日</span><span class="sxs-lookup"><span data-stu-id="224d0-299">Version 2105: May 03</span></span>
<span data-ttu-id="224d0-300">*版本 2105 (組建 14026.20052)*</span><span class="sxs-lookup"><span data-stu-id="224d0-300">*Version 2105 (Build 14026.20052)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-302">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-302">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="224d0-303">Teams</span><span class="sxs-lookup"><span data-stu-id="224d0-303">Teams</span></span>

- <span data-ttu-id="224d0-304">**在會議中同時聚焦多個使用者：** 召集人和簡報者現在可以在會議期間同時聚焦多個參與者。</span><span class="sxs-lookup"><span data-stu-id="224d0-304">**Spotlight multiple users at the same time in a meeting:** Organizers and presenters can now spotlight multiple participants simultaneously during meetings.</span></span> <span data-ttu-id="224d0-305">會議階段會向會議中的每個人顯示這些焦點參與者及其影片或虛擬人偶。</span><span class="sxs-lookup"><span data-stu-id="224d0-305">The meeting stage will show these spotlighted participants, with their videos or avatars, to everyone in the meeting.</span></span>

- <span data-ttu-id="224d0-306">**從 PowerPoint 到 Teams 進行展示：** PowerPoint 應用程式直接透過 PowerPoint Live 將您的幻燈片展示到 Teams 會議。</span><span class="sxs-lookup"><span data-stu-id="224d0-306">**Present from PowerPoint to Teams:** Present your slides directly from the PowerPoint app to a Teams meeting via PowerPoint Live.</span></span>

- <span data-ttu-id="224d0-307">**新的管理標籤體驗和其他增強功能：** Teams 中的標籤可讓使用者快速聯繫一組人員，而不需要 @mention 或輸入所有人。管理標籤體驗現在是一個索引標籤。標籤現在也有描述欄位，因此您可以在標籤中新增更多詳細資料。</span><span class="sxs-lookup"><span data-stu-id="224d0-307">**New manage tag experience and other enhancements:** Tags in Teams let users quickly reach a group of people without having to @mention or type out everyone.The manage tags experience is now a Tab. Tags also now have a description field so that you can add more details to a tag.</span></span> <span data-ttu-id="224d0-308">新的標籤索引標籤將是標籤通知和搜尋標籤的登陸頁面，此網頁也即將推出。</span><span class="sxs-lookup"><span data-stu-id="224d0-308">The new Tags Tab will be the landing page for tag notifications and search for tags, which is also coming soon.</span></span>

- <span data-ttu-id="224d0-309">**智慧型喇叭：** 智慧型喇叭是 Windows 上 Microsoft Teams 會議室的智慧周邊設備。</span><span class="sxs-lookup"><span data-stu-id="224d0-309">**Intelligent Speakers:** Intelligent speakers are intelligent peripherals for Microsoft Teams Rooms on Windows.</span></span> <span data-ttu-id="224d0-310">他們將為會議室中的參與者帶來歸屬於演講者的抄寫，讓出席者能減少記錄筆記的時間，並輕鬆追蹤在會議室中發言的人。</span><span class="sxs-lookup"><span data-stu-id="224d0-310">They will bring speaker attributed transcription for participants in the meeting room, enabling attendees to spend less time note-taking and easily follow along who said what in the room.</span></span>

- <span data-ttu-id="224d0-311">**針對新使用者將預設從 Teams 紫色變更為原生通知：** 原生通知提供許多優點，例如支援控制中心、協助工具、專注輔助模式支援等。目前 Microsoft Teams 中新使用者的預設通知樣式為 Teams 紫色。</span><span class="sxs-lookup"><span data-stu-id="224d0-311">**Changing default to native notification from teams purple for new users:** Native Notifications provide a host of benefits like support for action center, accessibility, support for focus assist mode e.t.c.Currently the default notification style for a new user in Microsoft teams is Teams Purple.</span></span> <span data-ttu-id="224d0-312">變更後，新使用者的預設值會變更為原生通知。</span><span class="sxs-lookup"><span data-stu-id="224d0-312">With this change the default for new user will change to Native Notification.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-315">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-315">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-316">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-316">Excel</span></span>

- <span data-ttu-id="224d0-317">我們修正了在 64 位元 Windows 上使用 32 位元 Office 時導致 Excel 意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-317">We fixed an issue that caused Excel to close unexpectedly when using 32 bit Office on 64 bit Windows.</span></span>


- <span data-ttu-id="224d0-318">我們已修正在 [註解] 窗格中的註解間移動時，會導致 Excel 意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-318">We fixed an issue that caused Excel to close unexpectedly when moving through comments in the Comments pane.</span></span>


- <span data-ttu-id="224d0-319">已修正 Excel 某些自動化增益集無法載入的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-319">Fixed an issue where some automation add-ins for Excel unable to load.</span></span>


- <span data-ttu-id="224d0-320">我們已修正導致 [朗讀程式] 錯誤讀取 [版面設定] 對話方塊中 [頁首/頁尾] 索引標籤上兩個按鈕的内容之問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-320">We fixed an issue that caused Narrator to incorrectly read the properties of two buttons on the Header/Footer tab in the Page Setup dialog box.</span></span>


- <span data-ttu-id="224d0-321">我們已修正導致某些在其他 Office 應用程式中連結的活頁簿在執行更新連結時關閉而不儲存變更的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-321">We fixed an issue that caused some workbooks linked in other Office applications to close without saving changes when running Update Link.</span></span>


- <span data-ttu-id="224d0-322">已修正針對某些使用者流量分析工具箱增益集無法運作的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-322">Fixed an issue where the Analysis ToolPak add-in did not work for some users.</span></span>


- <span data-ttu-id="224d0-323">我們已修正某些檔案偶爾無法以受保護的檢視開啟的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-323">We fixed an issue where some files would occasionally fail to open in Protected View</span></span>


- <span data-ttu-id="224d0-324">我們已修正在使用增益集時，會導致某些語言的日期格式顯示不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-324">We fixed an issue that caused date formatting to be displayed incorrectly in some languages when using add-ins.</span></span>


- <span data-ttu-id="224d0-325">我們已修正造成部分使用者狀態列無法顯示 [準備就緒] 狀態的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-325">We fixed an issue that caused the status bar to not indicate a Ready state for some users.</span></span>


- <span data-ttu-id="224d0-326">我們已進行變更，讓名稱管理員可以在具有大量隱藏名稱的書籍上開啟。</span><span class="sxs-lookup"><span data-stu-id="224d0-326">We made a change to enable the Name Manager to open on books with a large number of hidden names.</span></span>


- <span data-ttu-id="224d0-p115">我們已修正支援舊版 Excel 的回溯相容性的問題。此問題可能會導致於較新版 Excel 中儲存的檔案無法在舊版 Excel 中正確載入，因為自 Office 2007 之後已將 IFERROR 和 XLOOKUP 等函數新增至 Excel。</span><span class="sxs-lookup"><span data-stu-id="224d0-p115">We fixed an issue to support backward compatibility with older versions of Excel. The issue may cause a file that is saved in a more recent version of Excel failed to load properly in older versions of Excel due to  functions such as IFERROR and XLOOKUP added to Excel since Office 2007.</span></span>


- <span data-ttu-id="224d0-329">我們已修正在某些情況下，使用選擇性貼上搭配格式時可能會導致 Excel 意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-329">We fixed an issue which could cause Excel to close unexpectedly when using Paste Special with formats in certain situations.</span></span>


### <a name="outlook"></a><span data-ttu-id="224d0-330">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-330">Outlook</span></span>

- <span data-ttu-id="224d0-331">我們已修正會導致 Outlook 覆寫 OWA 中已設定的焦點收件匣喜好設定問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-331">We fixed an issue that caused Outlook to override the Focused Inbox preferences configured in OWA.</span></span>


- <span data-ttu-id="224d0-332">我們已修正會導致漫遊設定的使用者遇到停止回應的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-332">We fixed an issue that caused users of roaming settings to experience hangs .</span></span>


- <span data-ttu-id="224d0-333">我們已修正在代表另一個使用者進行傳送，並且針對非全域通訊清單的通訊錄進行解析時，會造成名稱解析停用的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-333">We fixed an issue that caused name resolution disabled when sending on behalf of another user and resolving against an address book that is not the Global Address List.</span></span>


- <span data-ttu-id="224d0-334">我們已修正導致某些使用行事曆共用改進功能的使用者在功能窗格中與他們的行事曆互動時發生的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-334">We fixed an issue that caused some users of the calendar sharing improvements feature to experience issues with interacting with their calendar in the navigation pane.</span></span>


- <span data-ttu-id="224d0-335">我們已修正長時間使用高對比模式會導致 Outlook 意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-335">We fixed an issue where using High Contrast mode for extended periods of time would caused Outlook to close unexpectedly.</span></span>


- <span data-ttu-id="224d0-336">我們已修正在 Outlook 中以從右至左語言撰寫郵件時，包括數字的超連結會停用的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-336">We fixed an issue where hyperlinks including digits would be disable when composing a message in Outlook in a right-to-left language.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="224d0-337">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-337">PowerPoint</span></span>

- <span data-ttu-id="224d0-338">我們已修正與連結圖片相關的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-338">Fixes an issue related to linked pictures.</span></span>


### <a name="project"></a><span data-ttu-id="224d0-339">Project</span><span class="sxs-lookup"><span data-stu-id="224d0-339">Project</span></span>

- <span data-ttu-id="224d0-340">我們已修正透過規劃精靈完成的變更不一定會由變更事件擷取的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-340">We fixed an issue where changes done through Planning Wizards weren't always captured by change events.</span></span>


- <span data-ttu-id="224d0-341">我們已修正使用者無法從資源資料庫移除專案的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-341">We fixed an issue where users were unable to remove projects from the resource pool.</span></span>


### <a name="visio"></a><span data-ttu-id="224d0-342">Visio</span><span class="sxs-lookup"><span data-stu-id="224d0-342">Visio</span></span>

- <span data-ttu-id="224d0-343">我們已修正導致 Visio 和新的組建一起意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-343">We fixed an issue which caused Visio closed unexpectedly with recent build.</span></span>


### <a name="word"></a><span data-ttu-id="224d0-344">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-344">Word</span></span>

- <span data-ttu-id="224d0-345">我們已修正在移除超連結後，文字格式仍會保留的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-345">We fixed an issue where text formatting remains after removing hyperlinks.</span></span>


- <span data-ttu-id="224d0-346">我們已修正使用從右至左書寫的語言時，在註解中預留位置文字會被裁剪的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-346">We fixed a issue where placeholder text was clipped in comments when using right-to-left languages.</span></span>


- <span data-ttu-id="224d0-347">我們已修正在依人員篩選後，不會顯示註解的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-347">We fixed an issue where comments are not displayed after filtering by people.</span></span>


- <span data-ttu-id="224d0-348">我們已修正 Word 無法使用 Access 資料庫執行合併列印的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-348">We fixed an issue where Word was unable to perform a Mail Merge with an Access database.</span></span>


- <span data-ttu-id="224d0-349">我們已修正摺疊文件中邊緣的功能，會導致包含可供使用的多個欄位的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-349">We fixed an issue that caused the ability to collapse margins in a document containing multiple columns to be available.</span></span>


- <span data-ttu-id="224d0-350">我們已修正當文件中有註解時，表格儲存格中某些字元無法正確顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-350">We fixed an issue where some characters are not displayed correctly in table cells when there are comments in the document.</span></span>


- <span data-ttu-id="224d0-351">我們已修正在啟用 AIP 增益集的情況下儲存文件時，會發生檔案格式變更的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-351">We fixed an issue where the file format changes occurred when saving documents with the AIP add-in enabled.</span></span>


- <span data-ttu-id="224d0-352">我們已修正在編輯欄位時 Word 會變得沒有回應的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-352">We fixed an issue where Word would become unresponsive when editing fields.</span></span>


- <span data-ttu-id="224d0-353">我們已修正將檔案上傳到 SharePoint Online 之後，敏感度標籤會從 Word 中的檔案消失的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-353">We fixed an issue where the sensitivity label disappears from a file in Word after uploading the file to SharePoint Online.</span></span>


- <span data-ttu-id="224d0-354">我們已修正使用命令 (而不是 CTRL+S 鍵盤快速鍵) 來儲存文件時，系統不會提示使用者儲存文件的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-354">We fixed an issue where users would not be prompted to save documents when using a command (rather than the CTRL+S keyboard shortcut).</span></span>


- <span data-ttu-id="224d0-355">修正使用者登出或將電腦重新開機，導致 Word 在關機時意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-355">Fixes an issue that may caused Word unexpectedly closed when shutting down due to the user logging off or restarting their computer.</span></span>


- <span data-ttu-id="224d0-356">我們已修正在移除超連結後，文字格式設定仍會保留的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-356">We fixed an issue where text formatting remains after removing hyperlinks.</span></span>


### <a name="office-suite"></a><span data-ttu-id="224d0-357">Office 套件</span><span class="sxs-lookup"><span data-stu-id="224d0-357">Office Suite</span></span>

- <span data-ttu-id="224d0-358">我們已修正將註解新增至文件時，會導致 [聽寫] 按鈕對齊不當的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-358">We fixed an issue that caused the Dictation button to be misaligned when adding comments to a document.</span></span>


- <span data-ttu-id="224d0-359">已修正剖析 Emoji 處理的字串時，當讀取超出陣列範圍時，導致應用程式意外關閉的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-359">Fixed an issue when parsing a string for emoji processing that casued application closed unexpectedly when reading outside of the bounds of an array</span></span>


- <span data-ttu-id="224d0-360">我們已修正某些可縮放向量圖形 (SVG) 無法正確轉譯的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-360">We fixed an issue where some Scalable Vector Graphics (SVG) did not render correctly.</span></span>



[//]: # (請勿移除 BUGDETAILS 內容結尾)

## <a name="version-2104-april-28"></a><span data-ttu-id="224d0-362">版本 2104：4 月 28 日</span><span class="sxs-lookup"><span data-stu-id="224d0-362">Version 2104: April 28</span></span>
<span data-ttu-id="224d0-363">*版本 2104 (組建 13929.20296)*</span><span class="sxs-lookup"><span data-stu-id="224d0-363">*Version 2104 (Build 13929.20296)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-365">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-365">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="224d0-366">Teams</span><span class="sxs-lookup"><span data-stu-id="224d0-366">Teams</span></span>

- <span data-ttu-id="224d0-367">**擴大的表情圖示選擇器：** 擴大的表情圖示更新可在 Teams 中提供使用者更多樂趣和表達力。</span><span class="sxs-lookup"><span data-stu-id="224d0-367">**Expanded Emoji Picker:** The expanded emoji update offers people more fun and expressiveness in Teams.</span></span> <span data-ttu-id="224d0-368">它也推出更廣泛的多樣性和呈現方式。</span><span class="sxs-lookup"><span data-stu-id="224d0-368">It also introduces a wider range of diversity and representation.</span></span> <span data-ttu-id="224d0-369">表情圖示集已由 85 個擴充到超過 800 個表情圖示，具有類別選取器、膚色選取器和簡短代碼選擇器。</span><span class="sxs-lookup"><span data-stu-id="224d0-369">The emoji set has expanded from 85 to over 800 emojis, with a category selector, skin tone selector and shortcode picker.</span></span>

- <span data-ttu-id="224d0-370">**Microsoft Teams：修訂會議內共用體驗：** Microsoft Teams 中會議內共用功能的使用者介面已重新設計，以協助簡報者更快速且輕鬆地找到所需的內容。</span><span class="sxs-lookup"><span data-stu-id="224d0-370">**Microsoft Teams: Revised in-meeting Share experience:** The user interface for the in-meeting Share feature in Microsoft Teams has been redesigned to help presenters find their desired content more quickly and easily.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-373">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-373">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-374">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-374">Excel</span></span>

- <span data-ttu-id="224d0-375">修正某些 Excel 自動化增益集無法載入的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-375">Fixed a problem where some automation add-ins for Excel failed to load.</span></span>


### <a name="outlook"></a><span data-ttu-id="224d0-376">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-376">Outlook</span></span>

- <span data-ttu-id="224d0-377">我們已修正會導致漫遊設定的使用者遇到停滯的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-377">We fixed an issue that caused users of roaming settings to experience hangs .</span></span>


### <a name="powerpoint"></a><span data-ttu-id="224d0-378">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-378">PowerPoint</span></span>

- <span data-ttu-id="224d0-379">我們已修正與連結圖片相關的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-379">We fixed an issue related to linked pictures.</span></span>


### <a name="project"></a><span data-ttu-id="224d0-380">Project</span><span class="sxs-lookup"><span data-stu-id="224d0-380">Project</span></span>

- <span data-ttu-id="224d0-381">修正使用者無法從資源資料庫移除專案的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-381">Fixed an issue where users were unable to remove projects from the resource pool.</span></span>


### <a name="word"></a><span data-ttu-id="224d0-382">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-382">Word</span></span>

- <span data-ttu-id="224d0-383">我們對編輯 OLE 物件進行了變更。</span><span class="sxs-lookup"><span data-stu-id="224d0-383">We made a change on editing OLE object.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2104-april-26"></a><span data-ttu-id="224d0-385">版本 2104：4 月 26 日</span><span class="sxs-lookup"><span data-stu-id="224d0-385">Version 2104: April 26</span></span>
<span data-ttu-id="224d0-386">*版本 2104 (組建 13929.20254)*</span><span class="sxs-lookup"><span data-stu-id="224d0-386">*Version 2104 (Build 13929.20254)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-388">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-388">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-389">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-389">Outlook</span></span>

- <span data-ttu-id="224d0-390">**開啟共用行事曆改良功能：** 針對 Office 365 中的共用行事曆，Outlook 可以使用 REST API 更新這些行事曆。</span><span class="sxs-lookup"><span data-stu-id="224d0-390">**Turn on shared calendar improvements:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="224d0-391">開啟預覽，以更快速且更可靠地更新共用行事曆。</span><span class="sxs-lookup"><span data-stu-id="224d0-391">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-394">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-394">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-395">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-395">Excel</span></span>

- <span data-ttu-id="224d0-396">我們已修正某些檔案偶爾無法以受保護的檢視開啟的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-396">We fixed an issue where some files would occasionally fail to open in Protected View</span></span>


### <a name="outlook"></a><span data-ttu-id="224d0-397">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-397">Outlook</span></span>

- <span data-ttu-id="224d0-398">我們已修正會導致 Outlook 覆寫 OWA 中已設定的焦點收件匣喜好設定問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-398">We fixed an issue that caused Outlook to override the Focused Inbox preferences configured in OWA.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2104-april-19"></a><span data-ttu-id="224d0-400">版本 2104：4 月 19 日</span><span class="sxs-lookup"><span data-stu-id="224d0-400">Version 2104: April 19</span></span>
<span data-ttu-id="224d0-401">*版本 2104 (組建 13929.20216)*</span><span class="sxs-lookup"><span data-stu-id="224d0-401">*Version 2104 (Build 13929.20216)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-403">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-403">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-404">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-404">Excel</span></span>

- <span data-ttu-id="224d0-405">**從動態陣列匯入資料**：您現在可以從目前活頁簿中的動態陣列中，匯出、連結及重新整理資料。</span><span class="sxs-lookup"><span data-stu-id="224d0-405">**Import data from dynamic arrays:** You can now import, shape and refresh data from dynamic arrays in the current workbook.</span></span> [<span data-ttu-id="224d0-406">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-406">Learn more</span></span>](https://support.office.com/article/205c6b06-03ba-4151-89a1-87a7eb36e531)

### <a name="outlook"></a><span data-ttu-id="224d0-407">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-407">Outlook</span></span>

- <span data-ttu-id="224d0-408">**改良的行事曆搜尋：** 已改善日曆搜尋功能，其中最大的改良處是更輕鬆地在搜尋結果中尋找下一個系料數列。</span><span class="sxs-lookup"><span data-stu-id="224d0-408">**Improved Calendar Search:** Improvements have been made to Calendar search, largest of which is the ability to more easily find the next occurence of a series in search results.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-411">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-411">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="224d0-412">Access</span><span class="sxs-lookup"><span data-stu-id="224d0-412">Access</span></span>

- <span data-ttu-id="224d0-413">此變更可修正在某些情況下，執行 SQL Server 傳遞查詢時，可能會導致錯誤訊息指出「無效的 Cursor 狀態」的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-413">This change fixes an issue where in some cases running a SQL Server pass through query could result in an error message indicating that there was an "invalid cursor state".</span></span>


- <span data-ttu-id="224d0-414">我們已修正當外部應用程式要求協助工具介面時，它會防止我們關機，直到它們釋出其參考為止的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-414">We fixed an issue when an external application requests an accessibility interface, it will prevent us from shutting down until they release their reference.</span></span>


### <a name="excel"></a><span data-ttu-id="224d0-415">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-415">Excel</span></span>

- <span data-ttu-id="224d0-416">我們已修正會導致無法以公式形式貼上到受保護工作表的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-416">We fixed a problem that was preventing the ability to paste as formulas on a protected sheet.</span></span>


- <span data-ttu-id="224d0-417">我們已修正當檔案儲存為 PDF 文件時，使用 [超連結] 函數所建立的超連結無法運作的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-417">We fixed an issue in which hyperlinks created using the HYPERLINK function would not work if the file was saved as a PDF document.</span></span>


- <span data-ttu-id="224d0-418">我們已修正在公式中使用參照空白範圍加入隱含運算子 (@) 符號，並可能提供不正確結果的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-418">We fixed an issue where an implicit operator (@) symbol would be added to the formula with a reference to an empty range and potentially give the incorrect result.</span></span>


### <a name="outlook"></a><span data-ttu-id="224d0-419">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-419">Outlook</span></span>

- <span data-ttu-id="224d0-420">我們已修正會導致某些使用者在同步處理資料夾階層變更時遇到 Outlook 意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-420">We fixed an issue that caused some users to experience Outlook to close unexpectedly when syncing folder hierarchy changes.</span></span>


- <span data-ttu-id="224d0-421">我們已修正會導致使用者在新增行事曆時，錯誤地看到「這可能需要一些時間」訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-421">We fixed an issue that cause users to erroneously see a "This may take a while" message when adding a calendar.</span></span>


- <span data-ttu-id="224d0-422">我們已修正會導致代理人在新增的行事曆上所建立的會議中顯示為召集人的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-422">We fixed an issue that caused delegates to appear as the organizer of meetings created on newly added calendars.</span></span>  <span data-ttu-id="224d0-423">處於此狀態的會議不會出現在主體的行事曆上。</span><span class="sxs-lookup"><span data-stu-id="224d0-423">Meetings in this state did not appear on the principal's calendar.</span></span>


- <span data-ttu-id="224d0-424">我們已修正會導致使用者在搜尋時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-424">We fixed an issue that caused users to experience a crash when searching.</span></span>


- <span data-ttu-id="224d0-425">我們已修正與搜尋相關的當機問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-425">We fixed a search related crash.</span></span>


- <span data-ttu-id="224d0-426">我們已修正會導致使用者看到簽名意外消失的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-426">We fixed an issue that caused users to see signatures disappear unexpectedly.</span></span>


- <span data-ttu-id="224d0-427">我們已修正可能造成使用者看到正在撰寫的郵件失去 UI 焦點的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-427">We fixed an issue that could cause users to see the message that they are composing losing the UI focus.</span></span>


- <span data-ttu-id="224d0-428">我們已修正會導致 Outlook 覆寫 OWA 中已設定的焦點收件匣喜好設定問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-428">We fixed an issue that caused Outlook to override the Focused Inbox preferences configured in OWA.</span></span>


- <span data-ttu-id="224d0-429">我們已修正會導致雲端設定功能的使用者在新裝置上設定 Outlook 之後，會看到自訂設定遭到預設設定覆寫的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-429">We fixed an issue that caused users of the Cloud Settings feature to see customized settings overridden by default setting after configuring Outlook on a new device.</span></span>


- <span data-ttu-id="224d0-430">我們已修正會導致部分使用者無法存取與次要郵件帳戶相關聯的簽章問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-430">We fixed an issue that caused some people to be unable to access signatures associated with secondary mail accounts.</span></span>


- <span data-ttu-id="224d0-431">我們已修正在代表另一個使用者進行傳送，並且針對非全域通訊清單的通訊錄進行解析時，造成名稱解析失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-431">We fixed an issue that caused name resolution to fail when sending on behalf of another user and resolving against an address book that is not the Global Address List.</span></span>


- <span data-ttu-id="224d0-432">我們已修正在代表另一個使用者進行傳送，並且針對非全域通訊清單的通訊錄進行解析時，造成名稱解析失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-432">We fixed an issue that caused name resolution to fail when sending on behalf of another user and resolving against an address book that is not the Global Address List.</span></span>


### <a name="project"></a><span data-ttu-id="224d0-433">Project</span><span class="sxs-lookup"><span data-stu-id="224d0-433">Project</span></span>

- <span data-ttu-id="224d0-434">已修正如果日期格式為 W4/4，日期選擇器可能會顯示錯誤的日期和年份的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-434">Fixed an issue where if the date format is W4/4, the date picker may show the wrong day and year.</span></span>


### <a name="visio"></a><span data-ttu-id="224d0-435">Visio</span><span class="sxs-lookup"><span data-stu-id="224d0-435">Visio</span></span>

- <span data-ttu-id="224d0-436">修正 Visio 在關閉期間可能會停止運作的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-436">Fixed an issue where Visio could stop working during close.</span></span>


- <span data-ttu-id="224d0-437">修正「搜尋圖形」功能以顯示所有結果</span><span class="sxs-lookup"><span data-stu-id="224d0-437">Fixed "Search Shape" feature to display all the results</span></span>



### <a name="word"></a><span data-ttu-id="224d0-438">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-438">Word</span></span>

- <span data-ttu-id="224d0-p120">在此錯誤中，Office 未遵守特定原則 (在首頁上顯示了一組範本，但它們應該已遭到停用)。透過此修正，將會遵守原則。</span><span class="sxs-lookup"><span data-stu-id="224d0-p120">In this bug, specific policies weren't being honored by Office (a group of templates were being shown on the Home Page when they should have been disabled). With this fix, the policies are being honored.</span></span>


- <span data-ttu-id="224d0-441">共同撰寫文件時，若註解順序變更，不會清除作用中草稿。</span><span class="sxs-lookup"><span data-stu-id="224d0-441">When coauthoring a document, active draft is not cleared when comment order changes.</span></span>


- <span data-ttu-id="224d0-442">修正新式註解中的錯誤，其中標點符號和數字的顯示方式對於某些國際語言是錯誤的。</span><span class="sxs-lookup"><span data-stu-id="224d0-442">Fixed bug in Modern Commenting where punctuation and numbers would show up on the wrong side for some international languages.</span></span>


- <span data-ttu-id="224d0-443">修正 'B' 和 ')' 的組合會自動轉變成戴著墨鏡的表情圖示，且現在仍保留為個別字元的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-443">Fixed an issue where the combination of 'B' and ')' would automatically turn into the sunglass wearing emoji and now remain as the individual characters</span></span>


- <span data-ttu-id="224d0-444">更新在本機儲存的檔案自動儲存圖說文字上的文字。</span><span class="sxs-lookup"><span data-stu-id="224d0-444">Updates text on autosave callout for files saved locally.</span></span>


- <span data-ttu-id="224d0-445">我們已修正在共同撰寫期間的註解問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-445">We fixed an issue with comments during coauthoring.</span></span>


- <span data-ttu-id="224d0-446">我們已修正與註解圖示相關的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-446">We fixed an issue relating to comment icon.</span></span>


- <span data-ttu-id="224d0-447">我們已修正貼上文字中的樣式與複製和貼上的樣式可能不同的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-447">We fixed an issue which copy and paste styles may not be same in pasted text.</span></span>


- <span data-ttu-id="224d0-448">最佳化提供文字預測的條件。</span><span class="sxs-lookup"><span data-stu-id="224d0-448">Optimizes conditions for text predictions to be offered.</span></span>


- <span data-ttu-id="224d0-449">我們已修正與超連結相關的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-449">We fixed an issue relating to hyperlink.</span></span>


- <span data-ttu-id="224d0-450">在閱讀模式中使用深色模式主題時，有些選取的文字無法顯示。</span><span class="sxs-lookup"><span data-stu-id="224d0-450">Some select text not visible when using darkmode theme in reading mode.</span></span>


- <span data-ttu-id="224d0-451">我們已修正 [自動儲存] 中的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-451">We fixed an issue in auto save.</span></span>


- <span data-ttu-id="224d0-452">我們在 Application.OnTime 中修正了可能無法正確觸發的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-452">We made a fix in Application.OnTime where it might not trigger correctly.</span></span>


### <a name="office-suite"></a><span data-ttu-id="224d0-453">Office 套件</span><span class="sxs-lookup"><span data-stu-id="224d0-453">Office Suite</span></span>

- <span data-ttu-id="224d0-454">已修正與文字反覆項目相關的效能問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-454">Fixed a performance issue related to iteration of text.</span></span>


- <span data-ttu-id="224d0-455">已修正在 Office 中支援 GDI+ LineJoinMiterClipped 的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-455">Fixes an issue with support of GDI+ LineJoinMiterClipped in Office.</span></span>


- <span data-ttu-id="224d0-456">此發行版本改善當關鍵字位於文件的第一行時，跨行敏感內容的處理。</span><span class="sxs-lookup"><span data-stu-id="224d0-456">This release improves handling of line-spanning sensitive content when the keyword is on the first line of a document.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2103-april-13"></a><span data-ttu-id="224d0-458">版本 2103：4 月 13 日</span><span class="sxs-lookup"><span data-stu-id="224d0-458">Version 2103: April 13</span></span>
<span data-ttu-id="224d0-459">*版本 2103 (組建 13901.20400)*</span><span class="sxs-lookup"><span data-stu-id="224d0-459">*Version 2103 (Build 13901.20400)*</span></span>

### <a name="feature-updates"></a><span data-ttu-id="224d0-460">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-460">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="224d0-461">Teams</span><span class="sxs-lookup"><span data-stu-id="224d0-461">Teams</span></span>

- <span data-ttu-id="224d0-462">**動態檢視** 動態檢視自動最佳化 Teams 會議中的共用內容和影片參與者。</span><span class="sxs-lookup"><span data-stu-id="224d0-462">**Dynamic view** Dynamic view automatically optimizes shared content and video participants in Teams meetings.</span></span> <span data-ttu-id="224d0-463">新控制項可讓您個人化檢視以滿足您的喜好和需要，例如能够並排顯示共用內容和特定參與者。</span><span class="sxs-lookup"><span data-stu-id="224d0-463">New controls let you personalize the view to suit your preferences and needs, such as the ability to show shared content and specific participants side-by-side.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2103-april-10"></a><span data-ttu-id="224d0-465">版本 2103：4 月 10 日</span><span class="sxs-lookup"><span data-stu-id="224d0-465">Version 2103: April 10</span></span>
<span data-ttu-id="224d0-466">*版本 2103 (組建 13901.20400)*</span><span class="sxs-lookup"><span data-stu-id="224d0-466">*Version 2103 (Build 13901.20400)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-468">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-468">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-469">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-469">Excel</span></span>

- <span data-ttu-id="224d0-470">修正繪製影像時，Word 中的潛在資源爭用問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-470">Fixed a potential resource contention issue in word when drawing an image.</span></span>

### <a name="outlook"></a><span data-ttu-id="224d0-471">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-471">Outlook</span></span>

- <span data-ttu-id="224d0-472">我們已修正會導致使用者在新增行事曆時，錯誤地看到「這可能需要一些時間」訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-472">We fixed an issue that cause users to erroneously see a "This may take a while" message when adding a calendar.</span></span>

- <span data-ttu-id="224d0-473">我們已修正會導致代理人在新增的行事曆上所建立的會議中顯示為召集人的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-473">We fixed an issue that caused delegates to appear as the organizer of meetings created on newly added calendars.</span></span>  <span data-ttu-id="224d0-474">處於此狀態的會議不會出現在主體的行事曆上。</span><span class="sxs-lookup"><span data-stu-id="224d0-474">Meetings in this state did not appear on the principal's calendar.</span></span>

- <span data-ttu-id="224d0-475">修正繪製影像時，Word 中的潛在資源爭用問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-475">Fixed a potential resource contention issue in word when drawing an image.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="224d0-476">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-476">Powerpoint</span></span>

- <span data-ttu-id="224d0-477">修正繪製影像時，Word 中的潛在資源爭用問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-477">Fixed a potential resource contention issue in word when drawing an image.</span></span>

### <a name="word"></a><span data-ttu-id="224d0-478">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-478">Word</span></span>

- <span data-ttu-id="224d0-479">修正繪製影像時，Word 中的潛在資源爭用問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-479">Fixed a potential resource contention issue in word when drawing an image.</span></span>

- <span data-ttu-id="224d0-480">修正在預覽列印時沒有回應的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-480">Fixed a non-responsive issue while in Print preview.</span></span>

- <span data-ttu-id="224d0-481">更新在本機儲存的檔案自動儲存圖說文字上的文字。</span><span class="sxs-lookup"><span data-stu-id="224d0-481">Updates text on autosave callout for files saved locally.</span></span>

### <a name="office-suite"></a><span data-ttu-id="224d0-482">Office 套件</span><span class="sxs-lookup"><span data-stu-id="224d0-482">Office Suite</span></span>

- <span data-ttu-id="224d0-483">修正離線開啟 SyncBacked 檔案，然後於儲存檔案之前，在應用程式中重新命名檔案時重新命名失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-483">Fixed rename failure issue when open a SyncBacked file offline then rename the file in app before saving file.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2103-april-02"></a><span data-ttu-id="224d0-485">版本 2103：4 月 2 日</span><span class="sxs-lookup"><span data-stu-id="224d0-485">Version 2103: April 02</span></span>
<span data-ttu-id="224d0-486">*版本 2103 (組建 13901.20336)*</span><span class="sxs-lookup"><span data-stu-id="224d0-486">*Version 2103 (Build 13901.20336)*</span></span>
* <span data-ttu-id="224d0-487">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="224d0-487">Various bugs and performance fixes.</span></span>

## <a name="version-2103-april-1"></a><span data-ttu-id="224d0-488">版本 2103：4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="224d0-488">Version 2103: April 1</span></span>
<span data-ttu-id="224d0-489">*版本 2103 (組建 13901.20148)*</span><span class="sxs-lookup"><span data-stu-id="224d0-489">*Version 2103 (Build 13901.20148)*</span></span>

### <a name="feature-updates"></a><span data-ttu-id="224d0-490">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-490">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="224d0-491">Teams</span><span class="sxs-lookup"><span data-stu-id="224d0-491">Teams</span></span>

- <span data-ttu-id="224d0-492">**日期/時間格式** 利用此更新，Teams 中的日期/時間格式將會與 Mac 和 Windows 作業系統地區設定相符。</span><span class="sxs-lookup"><span data-stu-id="224d0-492">**Date/Time format** With this update, the date/time formats in Teams will match the Mac and Windows operating system regional settings.</span></span> <span data-ttu-id="224d0-493">之前，Teams 只會以與應用程式語言對應的格式顯示日期/時間。</span><span class="sxs-lookup"><span data-stu-id="224d0-493">Previously, Teams would only show date/time in the format corresponding to the application's language.</span></span> <span data-ttu-id="224d0-494">務必注意，無論作業系統的行事曆設定為何，都只支援西曆。</span><span class="sxs-lookup"><span data-stu-id="224d0-494">It's important to note that only the Gregorian calendar is supported regardless of the operating system's calendar setting.</span></span> 

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2103-march-30"></a><span data-ttu-id="224d0-496">版本 2103：3 月 30 日</span><span class="sxs-lookup"><span data-stu-id="224d0-496">Version 2103: March 30</span></span>
<span data-ttu-id="224d0-497">*版本 2103 (組建 13901.20312)*</span><span class="sxs-lookup"><span data-stu-id="224d0-497">*Version 2103 (Build 13901.20312)*</span></span>
* <span data-ttu-id="224d0-498">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="224d0-498">Various bugs and performance fixes.</span></span>

## <a name="version-2103-march-28"></a><span data-ttu-id="224d0-499">版本 2103：3 月 28 日</span><span class="sxs-lookup"><span data-stu-id="224d0-499">Version 2103: March 28</span></span>
<span data-ttu-id="224d0-500">*版本 2103 (組建 13901.20306)*</span><span class="sxs-lookup"><span data-stu-id="224d0-500">*Version 2103 (Build 13901.20306)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-502">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-502">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-503">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-503">Outlook</span></span>

- <span data-ttu-id="224d0-504">我們已修正導致某些使用者在同步處理資料夾階層變更時遇到 Outlook 意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-504">We fixed an issue that caused some users to experience Outlook to close unexpectedly when syncing folder hierarchy changes.</span></span>


- <span data-ttu-id="224d0-505">我們已修正會導致某些使用者在瀏覽窗格中看到主要和次要行事曆切換位置的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-505">We fixed an issue that caused some users to see their primary and secondary calendar switching places in the Navigation Pane.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2103-march-22"></a><span data-ttu-id="224d0-507">版本 2103：3 月 22 日</span><span class="sxs-lookup"><span data-stu-id="224d0-507">Version 2103: March 22</span></span>
<span data-ttu-id="224d0-508">*版本 2103 (組建 13901.20230)*</span><span class="sxs-lookup"><span data-stu-id="224d0-508">*Version 2103 (Build 13901.20230)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-510">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-510">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-511">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-511">Outlook</span></span>

- <span data-ttu-id="224d0-512">我們已修正會導致使用者看到較預期更多的簽章的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-512">We fixed an issue that caused users to see more signatures than expected.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2103-march-15"></a><span data-ttu-id="224d0-514">版本 2103：3 月 15 日</span><span class="sxs-lookup"><span data-stu-id="224d0-514">Version 2103: March 15</span></span>
<span data-ttu-id="224d0-515">*版本 2103 (組建 13901.20170)*</span><span class="sxs-lookup"><span data-stu-id="224d0-515">*Version 2103 (Build 13901.20170)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-517">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-517">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="224d0-518">Project</span><span class="sxs-lookup"><span data-stu-id="224d0-518">Project</span></span>

- <span data-ttu-id="224d0-519">修正 Visio 在關閉期間可能會停止運作的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-519">Fixed an issue where Visio could stop working during close.</span></span>


### <a name="visio"></a><span data-ttu-id="224d0-520">Visio</span><span class="sxs-lookup"><span data-stu-id="224d0-520">Visio</span></span>

- <span data-ttu-id="224d0-521">修正 Visio 在關閉期間可能會停止運作的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-521">Fixed an issue where Visio could stop working during close.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)
## <a name="version-2103-march-11"></a><span data-ttu-id="224d0-524">版本 2103：3 月 11 日</span><span class="sxs-lookup"><span data-stu-id="224d0-524">Version 2103: March 11</span></span>
<span data-ttu-id="224d0-525">*版本 2103 (組建 13901.20148)*</span><span class="sxs-lookup"><span data-stu-id="224d0-525">*Version 2103 (Build 13901.20148)*</span></span>

### <a name="feature-updates"></a><span data-ttu-id="224d0-526">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-526">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-527">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-527">Excel</span></span>

- <span data-ttu-id="224d0-528">**自動儲存並在敏感性加密文件上進行共同撰寫：** 不要為了安全性而犧牲生產力。</span><span class="sxs-lookup"><span data-stu-id="224d0-528">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="224d0-529">有了 Microsoft 資訊保護，使用敏感度標籤加密的文件現在可以自動儲存，並與他人進行即時共同撰寫，就彷彿文件未加密一樣便利。</span><span class="sxs-lookup"><span data-stu-id="224d0-529">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="224d0-530">需要租用戶選擇加入 (詳細資訊： https://aka.ms/mipcoauth)。</span><span class="sxs-lookup"><span data-stu-id="224d0-530">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>

### <a name="outlook"></a><span data-ttu-id="224d0-531">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-531">Outlook</span></span>

- <span data-ttu-id="224d0-532">**新的會議室和工作區預約體驗：** 會議室預約體驗已更新，透過它我們新增了功能，以讓您也能夠排程個別工作區</span><span class="sxs-lookup"><span data-stu-id="224d0-532">**New conference room and workspace booking experience:** The conference room booking experience has been refreshed, and with it we've added capabilities to allow you to schedule individual workspaces as well</span></span>

### <a name="powerpoint"></a><span data-ttu-id="224d0-533">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-533">PowerPoint</span></span>

- <span data-ttu-id="224d0-534">**自動儲存並在敏感性加密文件上進行共同撰寫：** 不要為了安全性而犧牲生產力。</span><span class="sxs-lookup"><span data-stu-id="224d0-534">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="224d0-535">有了 Microsoft 資訊保護，使用敏感度標籤加密的文件現在可以自動儲存，並與他人進行即時共同撰寫，就彷彿文件未加密一樣便利。</span><span class="sxs-lookup"><span data-stu-id="224d0-535">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="224d0-536">需要租用戶選擇加入 (詳細資訊： https://aka.ms/mipcoauth)。</span><span class="sxs-lookup"><span data-stu-id="224d0-536">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>

### <a name="teams"></a><span data-ttu-id="224d0-537">Teams</span><span class="sxs-lookup"><span data-stu-id="224d0-537">Teams</span></span>

- <span data-ttu-id="224d0-538">**不在辦公室狀態** 設定訊息，讓其他人知道您不在工作狀態或是休假中，因此當他們傳送聊天訊息給您時，您無法回覆。</span><span class="sxs-lookup"><span data-stu-id="224d0-538">**Out of Office status** Set up a message to let others know you're not working or on vacation so you're not available to reply when they send a chat message to you.</span></span> <span data-ttu-id="224d0-539">您的不在辦公室狀態也會與您 Outlook 日曆中的自動回覆同步。</span><span class="sxs-lookup"><span data-stu-id="224d0-539">Your Out of Office status will also sync with Automatic Replies in your Outlook calendar.</span></span>

### <a name="visio"></a><span data-ttu-id="224d0-540">Visio</span><span class="sxs-lookup"><span data-stu-id="224d0-540">Visio</span></span>

- <span data-ttu-id="224d0-541">**Office 圖示有新的外觀：** 產品圖示經過重新設計，以反映簡單、功能強大且智慧型的 Office 體驗。</span><span class="sxs-lookup"><span data-stu-id="224d0-541">**Office icons have a new look:** The product icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span> [<span data-ttu-id="224d0-542">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-542">Learn more</span></span>](https://support.office.com/article/a6cdf19a-b2bd-4be1-9515-d74a37aa59bf)

### <a name="word"></a><span data-ttu-id="224d0-543">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-543">Word</span></span>

- <span data-ttu-id="224d0-544">**Word 文件的深色模式：** 深色模式有助於減輕眼睛疲勞，並可在處理文件時適應對光線的敏感度。</span><span class="sxs-lookup"><span data-stu-id="224d0-544">**Dark Mode for Word documents:** Dark Mode may help reduce eye strain and accommodate light sensitivity while working on your documents.</span></span>

- <span data-ttu-id="224d0-545">**自動儲存並在敏感性加密文件上進行共同撰寫：** 不要為了安全性而犧牲生產力。</span><span class="sxs-lookup"><span data-stu-id="224d0-545">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="224d0-546">有了 Microsoft 資訊保護，使用敏感度標籤加密的文件現在可以自動儲存，並與他人進行即時共同撰寫，就彷彿文件未加密一樣便利。</span><span class="sxs-lookup"><span data-stu-id="224d0-546">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="224d0-547">需要租用戶選擇加入 (詳細資訊： https://aka.ms/mipcoauth)。</span><span class="sxs-lookup"><span data-stu-id="224d0-547">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-550">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-550">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="224d0-551">Access</span><span class="sxs-lookup"><span data-stu-id="224d0-551">Access</span></span>

- <span data-ttu-id="224d0-552">我們已修正移除外部磁碟機時，可能會導致應用程式意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-552">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="224d0-553">我們已修正當外部應用程式要求協助工具介面時，它會防止我們關機，直到它們釋出其參考為止的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-553">We fixed an issue when an external application requests an accessibility interface, it will prevent us from shutting down until they release their reference.</span></span>


### <a name="excel"></a><span data-ttu-id="224d0-554">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-554">Excel</span></span>

- <span data-ttu-id="224d0-555">我們已修正移除外部磁碟機時，可能會導致應用程式意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-555">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="224d0-556">已修正因為無法擷取影像，所以 Excel 有時候會在嘗試顯示「資料類型」卡的時候意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-556">Fixed an issue where Excel would sometimes close unexpectedly when trying to show the Data Types card due to a not being able to retrieve an image.</span></span>


- <span data-ttu-id="224d0-557">已修正在日文字型中使用乘法或除號時，字型會意外改變的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-557">Corrected an issue where the font would change unexpectedly when using a multiplication or divide sign with a Japanese font.</span></span> <span data-ttu-id="224d0-558">我們現在會繼續使用相同的字型 (如果支援該字元)。</span><span class="sxs-lookup"><span data-stu-id="224d0-558">We now continue to use the same font if it supports the character.</span></span>


- <span data-ttu-id="224d0-559">我們已修正會導致使用者無法將 Excel 活頁簿匯出至 PDF 的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-559">We fixed an issue that prevented users from exporting an Excel workbook to PDF.</span></span>


- <span data-ttu-id="224d0-560">我們已修正使用 [貼上連結圖片] 選項時，會導致影像小於預期的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-560">We fixed an issue which caused images to be smaller than expected when using the Paste Linked Picture option.</span></span>


- <span data-ttu-id="224d0-561">我們已修正在共同撰寫的同時複製工作表時，某些格式可能會遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-561">We fixed an issue where some formatting could be lost when copying a sheet while coauthoring.</span></span>


- <span data-ttu-id="224d0-562">我們已修正開啟活頁簿時，會意外顯示某些記事的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-562">We fixed an issue where some notes were unexpectedly shown when opening a workbook.</span></span>


- <span data-ttu-id="224d0-563">我們已修正在儲存為 .xls 或 .xlt 格式時，會導致某些樞紐分析表格式損壞活頁簿的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-563">We fixed an issue that caused some PivotTable formatting to corrupt the workbook when saving to the .xls or .xlt format.</span></span>


### <a name="outlook"></a><span data-ttu-id="224d0-564">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-564">Outlook</span></span>

- <span data-ttu-id="224d0-565">我們已修正移除外部磁碟機時，可能會導致應用程式意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-565">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="224d0-566">我們已修正會導致使用者在建立新群組後看到重複的行事曆群組的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-566">We fixed and issue that caused users to see duplicate calendar groups appearing after creating a new group.</span></span>


- <span data-ttu-id="224d0-567">我們已修正會導致共用行事曆改良功能的使用者無法將行事曆的色彩設定為黃色或褐色的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-567">We fixed an issue that caused users of the Shared Calendar improvements to be unable to set a calendar's color to yellow or brown.</span></span>


- <span data-ttu-id="224d0-568">我們已修正會導致使用者在 Outlook 重新啟動之前，在功能窗格中看不到新增的行事曆顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-568">We fixed a problem that caused users to see newly added calendars fail to appear in the navigation pane until after Outlook had been restarted.</span></span>


- <span data-ttu-id="224d0-569">我們已修正匯出至 CSV 時，會導致非 ASCII 字元匯出錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-569">We fixed an issue that caused non-ASCII characters to export incorrectly when exporting to CSV.</span></span>


- <span data-ttu-id="224d0-570">我們已修正會導致部分使用者無法存取與次要郵件帳戶相關聯的簽章的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-570">We fixed an issue that caused some people to be unable to access signatures associated with secondary mail accounts.</span></span>


- <span data-ttu-id="224d0-571">我們已修正會導致雲端設定功能的使用者在新裝置上設定 Outlook 之後，會看到自訂設定遭到預設設定覆寫的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-571">We fixed an issue that caused users of the Cloud Settings feature to see customized settings overridden by default setting after configuring Outlook on a new device.</span></span>


- <span data-ttu-id="224d0-572">我們已修正會導致使用者看到包含 Unicode 內容的簽章損毀的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-572">We fixed an issue that caused users to see signatures containing unicode content to get damaged.</span></span>


- <span data-ttu-id="224d0-573">我們已修正會導致內嵌翻譯的使用者無法提交意見反應的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-573">We fixed an issue that caused users of inline translation to be unable to submit feedback.</span></span>


- <span data-ttu-id="224d0-574">我們已修正在移除 DRM 保護時會導致使用者看到附件重複的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-574">We fixed an issue that caused users to see attachments getting duplicated when removing DRM protection.</span></span>


- <span data-ttu-id="224d0-575">我們已修正導致使用者在撰寫郵件時無法使用 [檢查名稱] 查詢連絡人群組的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-575">We fixed an issue that caused users to be unable to look up a contact group with Check Names  when composing mail.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="224d0-576">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-576">PowerPoint</span></span>

- <span data-ttu-id="224d0-577">我們已修正移除外部磁碟機時，可能會導致應用程式意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-577">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="224d0-578">我們已修正在 PowerPoint 投影片放映模式中，折線圖中的箭號未如預期顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-578">We fixed an issue where arrows in line charts were not appearing as expected in PowerPoint slideshow mode.</span></span>


- <span data-ttu-id="224d0-579">已修正迴圈動畫和音訊書籤的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-579">Fixes an issue with looping animations and audio bookmarks.</span></span>


### <a name="project"></a><span data-ttu-id="224d0-580">Project</span><span class="sxs-lookup"><span data-stu-id="224d0-580">Project</span></span>

- <span data-ttu-id="224d0-581">修正 Visio 在關閉期間可能會停止運作的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-581">Fixed an issue where Visio could stop working during close.</span></span>


- <span data-ttu-id="224d0-582">我們已修正移除外部磁碟機時，可能會導致應用程式意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-582">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="224d0-583">已修正 100% 完成的工作可能會回復為 99% 完成的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-583">Fixed an issue where a task that are 100% complete may revert back to 99% complete.</span></span>


- <span data-ttu-id="224d0-584">已修正當您執行 JAWS 並且移至任務資訊對話方塊時 Project 意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-584">Fixed an issue where Project may close unexpectedly if you are running JAWS and go to the task information dialog.</span></span>


- <span data-ttu-id="224d0-585">修正此問題：如果指標欄不在第一欄位置，當您剪下摘要任務時，系統不會警告您也會移除子任務。</span><span class="sxs-lookup"><span data-stu-id="224d0-585">Fixed an issue where if the indicator column is not in the first column spot, when you cut a summary task you aren't warned that the subtasks will also be removed.</span></span>


- <span data-ttu-id="224d0-586">修正以下問題：如果使用者在時程表上選取 [將您本身加入至任務] 功能，則建立的工作指派可能不會使用正確的資源可用性單位。</span><span class="sxs-lookup"><span data-stu-id="224d0-586">Fixed an issue where if a user selected the Add Yourself to a Task function on their Timesheet, the correctly resource availability units may not be used on the created assignment.</span></span>


- <span data-ttu-id="224d0-587">已修正從 Project Web App 將專案存到本機檔案時，可能會錯誤建立任務分割的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-587">Fixed an issue where task splits may be wrongly created when saving a project from Project web app to a local file.</span></span> <span data-ttu-id="224d0-588">如果使用非標準工作時間的任務行事曆，就會發生此情況。</span><span class="sxs-lookup"><span data-stu-id="224d0-588">This would happen if a task calendar with non-standard working times was being used.</span></span>


### <a name="publisher"></a><span data-ttu-id="224d0-589">Publisher</span><span class="sxs-lookup"><span data-stu-id="224d0-589">Publisher</span></span>

- <span data-ttu-id="224d0-590">我們已修正移除外部磁碟機時，可能會導致應用程式意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-590">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


### <a name="visio"></a><span data-ttu-id="224d0-591">Visio</span><span class="sxs-lookup"><span data-stu-id="224d0-591">Visio</span></span>

- <span data-ttu-id="224d0-592">修正 Visio 在關閉期間可能會停止運作的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-592">Fixed an issue where Visio could stop working during close.</span></span>


- <span data-ttu-id="224d0-593">我們已修正移除外部磁碟機時，可能會導致應用程式意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-593">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


### <a name="word"></a><span data-ttu-id="224d0-594">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-594">Word</span></span>

- <span data-ttu-id="224d0-595">我們已修正開啟受 Microsoft 資訊保護 (MIP) 標籤保護的檔案時，如果使用者未登錄可存取 MIP 受保護標籤的身分識別，則可能會無限期擱置的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-595">We fixed an issue where opening a file protected with a Microsoft Information Protection (MIP) label can hang indefinitely if the user is not signed in to an identity that has access to the MIP protected label.</span></span> <span data-ttu-id="224d0-596">使用者必須取消開啟以顯示登錄提示，且開啟作業只會在這之後才成功。</span><span class="sxs-lookup"><span data-stu-id="224d0-596">The user is forced to cancel the open to show the sign-in prompt, and the open only succeeds after that point.</span></span> <span data-ttu-id="224d0-597">允許在開啟/下載期間顯示登錄提示，以修正此問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-597">Fixing this issue by allowing the sign-in prompt to be shown during open/download.</span></span>


- <span data-ttu-id="224d0-598">我們已修正移除外部磁碟機時，可能會導致應用程式意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-598">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="224d0-599">我們已修正在新的 Word 註解中使用 [聽寫] 時的問題，[註解] 卡片中的 [聽寫] 按鈕現在可以正確開啟和關閉。</span><span class="sxs-lookup"><span data-stu-id="224d0-599">We fixed an issue when using Dictation in the new Word Commenting, the Dictation button in the Comment card now correctly toggles on and off.</span></span>


- <span data-ttu-id="224d0-600">共同撰寫文件時，若註解順序變更，不會清除作用中草稿。</span><span class="sxs-lookup"><span data-stu-id="224d0-600">When coauthoring a document, active draft is not cleared when comment order changes.</span></span>


- <span data-ttu-id="224d0-601">修正當使用者在文件中進行聽寫時，文字之間沒有插入空格的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-601">Fixed an issue where there was no space being inserted between words when users dictated into their document.</span></span>


- <span data-ttu-id="224d0-602">修正在呈現捲動包含捲動或縮放動畫的圖層相關管線中的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-602">Fixes an issue in the rendering pipeline related to scrolling layers that contain scroll or zoom animations.</span></span>


- <span data-ttu-id="224d0-603">修正對具有 3D 效果的圖示和 SVG 圖形套用色彩的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-603">Fixes an issue with colors applied to icons and SVG graphics with 3D effects.</span></span>


- <span data-ttu-id="224d0-604">我們已修正自動儲存的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-604">We fixed an issue in AutoSave.</span></span>


- <span data-ttu-id="224d0-605">我們已修正註腳中的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-605">We fixed an issue in footnote.</span></span>


- <span data-ttu-id="224d0-606">我們已修正在 RTL 中張貼多行註解時，會導致第 2 行和開始行對齊左邊而非右邊的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-606">We fixed an issue when posting multi-line comments typed in RTL caused the 2nd and onward lines to be aligned to the left instead of the right.</span></span>


- <span data-ttu-id="224d0-607">我們已修正多個註解的對齊問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-607">We fixed an issue with alignment of multiple comments.</span></span>


- <span data-ttu-id="224d0-608">我們已修正 [大聲朗讀] 工作窗格鍵盤快速鍵的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-608">We fixed an issue in Read Aloud task pane keyboard shortcuts.</span></span>


- <span data-ttu-id="224d0-609">我們已修正可能會略過段落的朗讀程式問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-609">We fixed an issue with Narrator which may skips over a paragraph.</span></span>


- <span data-ttu-id="224d0-610">我們已修正拼字檢查會在兩個不同的拼字校正內容功能表之間切換的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-610">We fixed an issue where spell check switched between two different spelling correction context menus.</span></span>


- <span data-ttu-id="224d0-611">我們已修正 RTF 內容控制項的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-611">We fixed an issue with Rich text content controls.</span></span>


- <span data-ttu-id="224d0-612">我們已修正在隱藏段落結尾輸入可能會導致應用程式懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-612">We fixed an issue with typing at the end of a hidden paragraph may result in application hang.</span></span>


- <span data-ttu-id="224d0-613">我們已修正欄位可能有重疊文字的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-613">We fixed an issue where columns might have overlapping text.</span></span>


- <span data-ttu-id="224d0-614">我們已修正與書籤相關的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-614">We fixed an issue relating to bookmark.</span></span>


- <span data-ttu-id="224d0-615">我們已修正解決共同撰寫時衝突的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-615">We fixed an issue in resolving conflicts while in coauthoring.</span></span>


### <a name="office-suite"></a><span data-ttu-id="224d0-616">Office 套件</span><span class="sxs-lookup"><span data-stu-id="224d0-616">Office Suite</span></span>

- <span data-ttu-id="224d0-617">系統現在會按照群組原則設定適當篩選出 OneDrive 位置。</span><span class="sxs-lookup"><span data-stu-id="224d0-617">OneDrive places are now filtered out as appropriate per the group policy setting.</span></span>


- <span data-ttu-id="224d0-618">修正在包含數學方程式的文字內使用朗讀程式時可能發生的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-618">Fixed an issue that could happen when using narrator within text that contains math equations.</span></span>


- <span data-ttu-id="224d0-619">修正與支援在工作階段 0 中執行的 Office 應用程式相關的可靠性問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-619">Fixes a reliability issue related to support of Office apps running in session 0.</span></span>


- <span data-ttu-id="224d0-620">修正與支援在工作階段 0 中執行的 Office 應用程式相關的可靠性問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-620">Fixes a reliability issue related to support of Office apps running in session 0.</span></span>


- <span data-ttu-id="224d0-621">修正載入 EMF 影像時可能會發生的無回應問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-621">Fixes an issue related to unresponsiveness that may occur when loading EMF images.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2102-march-03"></a><span data-ttu-id="224d0-623">版本 2102：3 月 3 日</span><span class="sxs-lookup"><span data-stu-id="224d0-623">Version 2102: March 03</span></span>
<span data-ttu-id="224d0-624">*版本 2102 (組建 13801.20274)*</span><span class="sxs-lookup"><span data-stu-id="224d0-624">*Version 2102 (Build 13801.20274)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-626">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-626">Resolved issues</span></span>
### <a name="word"></a><span data-ttu-id="224d0-627">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-627">Word</span></span>

- <span data-ttu-id="224d0-628">修正佈景主題資訊套用到圖示和 SVG 圖形的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-628">Fixes an issue with theme information applied to icons and SVG graphics.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2102-march-01"></a><span data-ttu-id="224d0-630">版本 2102：3 月 1 日</span><span class="sxs-lookup"><span data-stu-id="224d0-630">Version 2102: March 01</span></span>
<span data-ttu-id="224d0-631">*版本 2102 (組建 13801.20266)*</span><span class="sxs-lookup"><span data-stu-id="224d0-631">*Version 2102 (Build 13801.20266)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-633">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-633">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-634">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-634">Outlook</span></span>

- <span data-ttu-id="224d0-635">**共用至 Teams：** 將 Outlook 的郵件與 Teams 中的某個人員或頻道共用。</span><span class="sxs-lookup"><span data-stu-id="224d0-635">**Share to Teams:** Share messages from Outlook with a person or channel in Teams.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-638">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-638">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-639">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-639">Outlook</span></span>

- <span data-ttu-id="224d0-640">我們已修正會導致使用者在建立新群組後看到重複的行事曆群組的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-640">We fixed and issue that caused users to see duplicate calendar groups appearing after creating a new group.</span></span>


- <span data-ttu-id="224d0-641">我們已修正會導致共用行事曆改良功能的使用者無法將行事曆的色彩設定為黃色或褐色的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-641">We fixed an issue that caused users of the Shared Calendar improvements to be unable to set a calendar's color to yellow or brown.</span></span>


- <span data-ttu-id="224d0-642">我們已修正會導致某些使用者在關閉訊息視窗時遇到應用程式關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-642">We fixed an issue that  caused some users to experience the app to shut down when closing message windows.</span></span>


- <span data-ttu-id="224d0-643">我們已修正會導致使用者看到包含 Unicode 內容的簽章損毀的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-643">We fixed an issue that caused users to see signatures containing unicode content to get damaged.</span></span>


- <span data-ttu-id="224d0-644">我們已修正會導致內嵌翻譯的使用者無法提交意見反應的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-644">We fixed an issue that caused users of inline translation to be unable to submit feedback.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2102-february-21"></a><span data-ttu-id="224d0-646">版本 2102：2 月 21 日</span><span class="sxs-lookup"><span data-stu-id="224d0-646">Version 2102: February 21</span></span>
<span data-ttu-id="224d0-647">*版本 2102 (組建 13801.20182)*</span><span class="sxs-lookup"><span data-stu-id="224d0-647">*Version 2102 (Build 13801.20182)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-649">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-649">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-650">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-650">Outlook</span></span>

- <span data-ttu-id="224d0-651">**使用語音草擬郵件：** 使用新的聽寫工具列、語音命令、自動標點符號等功能來撰寫郵件。</span><span class="sxs-lookup"><span data-stu-id="224d0-651">**Draft messages with your voice:** Use the new dictation toolbar, voice commands, auto-punctuation, and more to compose messages.</span></span>

### <a name="word"></a><span data-ttu-id="224d0-652">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-652">Word</span></span>

- <span data-ttu-id="224d0-653">**使用語音草擬文件：** 使用新的聽寫工具列、語音命令、自動標點符號等功能來草擬文件。</span><span class="sxs-lookup"><span data-stu-id="224d0-653">**Draft documents with your voice:** Use the new dictation toolbar, voice commands and auto-punctuation to draft documents.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-656">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-656">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-657">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-657">Excel</span></span>

- <span data-ttu-id="224d0-658">我們已修正使用 [貼上連結圖片] 選項時，會導致影像小於預期的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-658">We fixed an issue which caused images to bee smaller than expected when using the Paste Linked Picture option.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2102-february-16"></a><span data-ttu-id="224d0-660">版本 2102：2 月 16 日</span><span class="sxs-lookup"><span data-stu-id="224d0-660">Version 2102: February 16</span></span>
<span data-ttu-id="224d0-661">*版本 2102 (組建 13801.20160)*</span><span class="sxs-lookup"><span data-stu-id="224d0-661">*Version 2102 (Build 13801.20160)*</span></span>
* <span data-ttu-id="224d0-662">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="224d0-662">Various bugs and performance fixes.</span></span>

## <a name="version-2102-february-15"></a><span data-ttu-id="224d0-663">版本 2102：2 月 15 日</span><span class="sxs-lookup"><span data-stu-id="224d0-663">Version 2102: February 15</span></span>
<span data-ttu-id="224d0-664">*版本 2102 (組建 13801.20158)*</span><span class="sxs-lookup"><span data-stu-id="224d0-664">*Version 2102 (Build 13801.20158)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-666">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-666">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-667">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-667">Outlook</span></span>

- <span data-ttu-id="224d0-668">**聽寫提供更多語言：** 聽寫現在支援 7 個新的語言：印地文、俄文、波蘭文、葡萄牙文 (葡萄牙)、韓文、泰文、中文 (台灣)</span><span class="sxs-lookup"><span data-stu-id="224d0-668">**Dictation is available in more languages:** Dictation now supports 7 new languages: Hindi, Russian, Polish, Portuguese (Portugal), Korean, Thai, Chinese (Taiwan)</span></span>

### <a name="word"></a><span data-ttu-id="224d0-669">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-669">Word</span></span>

- <span data-ttu-id="224d0-670">**聽寫提供更多語言：** 聽寫現在支援 7 個新的語言：印地文、俄文、波蘭文、葡萄牙文 (葡萄牙)、韓文、泰文、中文 (台灣)</span><span class="sxs-lookup"><span data-stu-id="224d0-670">**Dictation is available in more languages:** Dictation now supports 7 new languages: Hindi, Russian, Polish, Portuguese (Portugal), Korean, Thai, Chinese (Taiwan)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-673">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-673">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-674">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-674">Excel</span></span>

- <span data-ttu-id="224d0-675">我們已修正會導致使用者無法將 Excel 活頁簿匯出至 PDF 的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-675">We fixed an issue that prevented users from exporting an Excel workbook to PDF.</span></span>


### <a name="word"></a><span data-ttu-id="224d0-676">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-676">Word</span></span>

- <span data-ttu-id="224d0-677">我們已修正共同撰寫時衝突的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-677">We fixed an issue in resolving conflicts while in coauthoring.</span></span>



[//]: # (請勿移除 BUGDETAILS 內容結尾)


## <a name="version-2102-february-11"></a><span data-ttu-id="224d0-679">版本 2102：2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="224d0-679">Version 2102: February 11</span></span>
<span data-ttu-id="224d0-680">*版本 2102 (組建 13801.20158)*</span><span class="sxs-lookup"><span data-stu-id="224d0-680">*Version 2102 (Build 13801.20158)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-682">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-682">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="224d0-683">Teams</span><span class="sxs-lookup"><span data-stu-id="224d0-683">Teams</span></span>

- <span data-ttu-id="224d0-684">**Windows 和 Mac 上的 Edge 和 Chrome 瀏覽器上的 2x2 影片** 使用者可以在 Windows 和 Mac 上的 Edge 和 Chrome 瀏覽器中的 Teams 會議中查看最多 4 個參與者的影片。</span><span class="sxs-lookup"><span data-stu-id="224d0-684">**2x2 video on Edge and Chrome browsers on Windows and Mac** Users can see up to 4 participants' video in Teams meetings in Edge and Chrome browsers on Windows and Mac.</span></span> [<span data-ttu-id="224d0-685">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-685">Learn more</span></span>](https://support.microsoft.com/office/using-video-in-microsoft-teams-3647fc29-7b92-4c26-8c2d-8a596904cdae#bkmk_videolayout)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

## <a name="version-2102-february-08"></a><span data-ttu-id="224d0-687">版本 2102：2 月 8 日</span><span class="sxs-lookup"><span data-stu-id="224d0-687">Version 2102: February 08</span></span>
<span data-ttu-id="224d0-688">*版本 2102 (組建 13801.20084)*</span><span class="sxs-lookup"><span data-stu-id="224d0-688">*Version 2102 (Build 13801.20084)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-690">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-690">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-691">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-691">Outlook</span></span>

- <span data-ttu-id="224d0-692">**Microsoft 搜尋支援的撰寫 (收件者/副本/密件副本) 建議**：將人員新增至收件者/副本行，現在會由 Microsoft 搜尋提供支援。</span><span class="sxs-lookup"><span data-stu-id="224d0-692">**Microsoft Search powered compose (To\CC\BCC) suggestions:** Adding people to the To\CC line is now powered by Microsoft Search.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-695">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-695">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="224d0-696">存取</span><span class="sxs-lookup"><span data-stu-id="224d0-696">Access</span></span>

- <span data-ttu-id="224d0-697">您現在會在 Access 中看到已選取的索引標籤。</span><span class="sxs-lookup"><span data-stu-id="224d0-697">You will now see selected tabs clearer in Access.</span></span>


### <a name="excel"></a><span data-ttu-id="224d0-698">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-698">Excel</span></span>

- <span data-ttu-id="224d0-699">修正重新開啟檔案時，使用非連續儲存格範圍的特定圖表無法載入的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-699">Fixes issue where certain charts using discontinuous ranges of cells would not load when files are re-opened.</span></span>


- <span data-ttu-id="224d0-700">修正當使用特定 Windows 安全性漏洞防護設定(SimExec、CallerCheck) 時，Excel 無法正常啟動或關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-700">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use.</span></span>


- <span data-ttu-id="224d0-701">我們已修正選取圖表的資料數列之後，Excel 會停止回應的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-701">We fixed an issue where Excel would stop responding after selecting a data series in a chart.</span></span>


- <span data-ttu-id="224d0-702">我們已修正當您在 [定義名稱] 對話方塊中新增名稱時，Excel 會意外結束的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-702">We fixed an issue where Excel would unexpectedly quit when you added a Name in the Define Name dialog.</span></span>


- <span data-ttu-id="224d0-703">已修正在裁剪作業期間，保持圖片長寬比的相關問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-703">Fixed an issue related to pictures retaining their aspect ratio during a crop operation.</span></span>


### <a name="outlook"></a><span data-ttu-id="224d0-704">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-704">Outlook</span></span>

- <span data-ttu-id="224d0-705">我們已修正會導致郵件在使用者取消選取該選項之後，以數位簽章方式傳送的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-705">We fixed an issue that caused mails to be sent as digitally signed after the user unchecked that option.</span></span>


- <span data-ttu-id="224d0-706">我們已修正會導致加密圖示無法對使用 [僅加密] 選項傳送的電子郵件顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-706">We fixed an issue that caused the encryption icon to fail to display for emails sent using the Encrypt Only option.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="224d0-707">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-707">PowerPoint</span></span>

- <span data-ttu-id="224d0-708">修正與顯示有色彩的表情符號相關的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-708">Fixed an issue related to displaying emojis with color.</span></span>


- <span data-ttu-id="224d0-709">修正在裁剪作業期間，與保持圖片的長寬比相關的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-709">Fixed an issue related to pictures retaining their aspect ratio during a crop operation.</span></span>


### <a name="visio"></a><span data-ttu-id="224d0-710">Visio</span><span class="sxs-lookup"><span data-stu-id="224d0-710">Visio</span></span>

- <span data-ttu-id="224d0-711">現已修正從 CAD 樣板呈現圖形的相關問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-711">This issue on shape rendering from CAD stencils has now been fixed.</span></span> <span data-ttu-id="224d0-712">使用者將在最新組建中看到問題已解決。</span><span class="sxs-lookup"><span data-stu-id="224d0-712">Users will see the issue resolved in the latest build.</span></span>


### <a name="word"></a><span data-ttu-id="224d0-713">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-713">Word</span></span>

- <span data-ttu-id="224d0-714">這會修正在失去網際網路連線一段時間後，會防止即時輸入和目前狀態還原的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-714">This fixes an issue that prevented real-time typing and presence from being restored after losing internet connectivity for a period of time.</span></span>


- <span data-ttu-id="224d0-715">當使用者在註解中選取文字，Word 現在會取消選取在其他註解中選取的文字。</span><span class="sxs-lookup"><span data-stu-id="224d0-715">When a user selects text in a comment, Word now unselects selected text in other comments.</span></span>


- <span data-ttu-id="224d0-716">Word 現在可讓您將註解文字複製到 Excel。</span><span class="sxs-lookup"><span data-stu-id="224d0-716">Word now allows copying comment text into Excel.</span></span>


- <span data-ttu-id="224d0-717">我們已修正執行 VBA 巨集 ExportAsFixedFormat2 失敗，出現說明「簡報 (未知的成員) 不合法值」錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-717">We fixed an issue when running the VBA macro ExportAsFixedFormat2 fails with an error stating "Presentation (unknown member) illegal value".</span></span>


- <span data-ttu-id="224d0-718">已修正在裁剪作業期間，保持圖片長寬比的相關問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-718">Fixed an issue related to pictures retaining their aspect ratio during a crop operation.</span></span>


- <span data-ttu-id="224d0-719">我們已修正註解可能會因連結而被截斷的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-719">We fixed an issue which the comment may be truncated with links.</span></span>


- <span data-ttu-id="224d0-720">我們已修正儲存至 SharePoint Online 的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-720">We fixed an issue in saving to SharePoint Online</span></span>


- <span data-ttu-id="224d0-721">我們已修正將 Word 文件匯出為 PDF 的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-721">We fixed an issue in exporting Word document to PDF.</span></span>


- <span data-ttu-id="224d0-722">我們已修正自動回復的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-722">We fixed an issue with AutoRecover.</span></span>

- <span data-ttu-id="224d0-723">我們已修正當與受 DRM 保護的檔案共同撰寫會發生的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-723">We fixed an issue when coauthoring with DRM protected files</span></span>


### <a name="office-suite"></a><span data-ttu-id="224d0-724">Office 套件</span><span class="sxs-lookup"><span data-stu-id="224d0-724">Office Suite</span></span>

- <span data-ttu-id="224d0-725">修正在 PowerPoint 中以影像形式插入項目符號時，會導致項目符號消失的錯誤。</span><span class="sxs-lookup"><span data-stu-id="224d0-725">Fixing a bug in PowerPoint where inserting bullets as images would result in bullets disappearing.</span></span> <span data-ttu-id="224d0-726">此修正可讓影像更可靠地呈現。</span><span class="sxs-lookup"><span data-stu-id="224d0-726">This fix makes it so they render more reliably.</span></span>

- <span data-ttu-id="224d0-727">已修正 Office 在某些情況下在應該呈現某個已登入帳戶的敏感度標籤時，卻呈現不同已登入帳戶的敏感度標籤的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-727">Fixed an issue where Office would in some circumstances present sensitivity labels for one signed-in account when it should present sensitivity labels for a different signed-in account.</span></span>



[//]: # (請勿移除 BUGDETAILS 內容結尾)

## <a name="version-2101-february-03"></a><span data-ttu-id="224d0-729">版本 2101: 2 月 03 日</span><span class="sxs-lookup"><span data-stu-id="224d0-729">Version 2101: February 03</span></span>
<span data-ttu-id="224d0-730">*版本 2101 (組建 13628.20330)*</span><span class="sxs-lookup"><span data-stu-id="224d0-730">*Version 2101 (Build 13628.20330)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-732">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-732">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-733">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-733">Outlook</span></span>

- <span data-ttu-id="224d0-734">我們已修正在 OWA 中顯示正確預設簽名的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-734">We fixed an issue that caused issues with displaying the correct default signature in OWA.</span></span>


- <span data-ttu-id="224d0-735">我們已修正會導致加密圖示無法對使用 [僅加密] 選項傳送的電子郵件顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-735">We fixed an issue that caused the encryption icon to fail to display on emails sent using the encryption only option.</span></span>



[//]: # (請勿移除 BUGDETAILS 內容結尾)

## <a name="version-2101-february-02"></a><span data-ttu-id="224d0-737">版本 2101：2 月 2 日</span><span class="sxs-lookup"><span data-stu-id="224d0-737">Version 2101: February 02</span></span>
<span data-ttu-id="224d0-738">*版本 2101 (組建 13628.20320)*</span><span class="sxs-lookup"><span data-stu-id="224d0-738">*Version 2101 (Build 13628.20320)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-740">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-740">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-741">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-741">Outlook</span></span>

- <span data-ttu-id="224d0-742">我們已修正會導致雲端設定使用者在更新設定時遇到停止回應的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-742">We fixed an issue that caused Cloud Settings users to experience a hang when updating settings.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2101-january-25"></a><span data-ttu-id="224d0-744">版本 2101：1 月 25 日</span><span class="sxs-lookup"><span data-stu-id="224d0-744">Version 2101: January 25</span></span>
<span data-ttu-id="224d0-745">*版本 2101 (組建 13628.20274)*</span><span class="sxs-lookup"><span data-stu-id="224d0-745">*Version 2101 (Build 13628.20274)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-747">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-747">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-748">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-748">Excel</span></span>

- <span data-ttu-id="224d0-749">**政府客戶：將敏感度標籤套用至您的文件和電子郵件：** 敏感度標籤功能目前可供 GCC 和 GCC-H 環境中的客戶取得。</span><span class="sxs-lookup"><span data-stu-id="224d0-749">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="224d0-750">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-750">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

### <a name="outlook"></a><span data-ttu-id="224d0-751">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-751">Outlook</span></span>

- <span data-ttu-id="224d0-752">**政府客戶：將敏感度標籤套用至您的文件和電子郵件：** 敏感度標籤功能目前可供 GCC 和 GCC-H 環境中的客戶取得。</span><span class="sxs-lookup"><span data-stu-id="224d0-752">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="224d0-753">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-753">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

### <a name="powerpoint"></a><span data-ttu-id="224d0-754">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-754">PowerPoint</span></span>

- <span data-ttu-id="224d0-755">**政府客戶：將敏感度標籤套用至您的文件和電子郵件：** 敏感度標籤功能目前可供 GCC 和 GCC-H 環境中的客戶取得。</span><span class="sxs-lookup"><span data-stu-id="224d0-755">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> <span data-ttu-id="224d0-756">[深入了解](/microsoft-365/compliance/sensitivity-labels)。</span><span class="sxs-lookup"><span data-stu-id="224d0-756">[Learn more](/microsoft-365/compliance/sensitivity-labels).</span></span>


### <a name="word"></a><span data-ttu-id="224d0-757">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-757">Word</span></span>

- <span data-ttu-id="224d0-758">**政府客戶：將敏感度標籤套用至您的文件和電子郵件：** 敏感度標籤功能目前可供 GCC 和 GCC-H 環境中的客戶取得。</span><span class="sxs-lookup"><span data-stu-id="224d0-758">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="224d0-759">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-759">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)


### <a name="resolved-issues"></a><span data-ttu-id="224d0-760">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-760">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-761">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-761">Outlook</span></span>

- <span data-ttu-id="224d0-762">我們修正了導致在其設定檔中具有大型階層的共用或委派信箱的使用者遇到停止回應的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-762">We fixed an issue that caused users that have Shared or Delegated Mailboxes with large hierarchies in their profile to encounter hangs.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)



## <a name="version-2101-january-18"></a><span data-ttu-id="224d0-764">版本 2101：1 月 18 日</span><span class="sxs-lookup"><span data-stu-id="224d0-764">Version 2101: January 18</span></span>
<span data-ttu-id="224d0-765">*版本 2101 (組建 13628.20158)*</span><span class="sxs-lookup"><span data-stu-id="224d0-765">*Version 2101 (Build 13628.20158)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)



[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-769">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-769">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="224d0-770">Project</span><span class="sxs-lookup"><span data-stu-id="224d0-770">Project</span></span>

- <span data-ttu-id="224d0-771">修正在 [團隊規劃] 檢視中工作沒有顯示邊框的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-771">Fixed an issue where borders weren't showing up for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="224d0-772">修正在 [團隊規劃] 檢視中拖放工作不起作用的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-772">Fixed an issue where you drag and drop wasn't working for tasks in the Team Planner view.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2101-january-13"></a><span data-ttu-id="224d0-774">版本 2101：1 月 13 日</span><span class="sxs-lookup"><span data-stu-id="224d0-774">Version 2101: January 13</span></span>
<span data-ttu-id="224d0-775">*版本 2101 (組建 13628.20118)*</span><span class="sxs-lookup"><span data-stu-id="224d0-775">*Version 2101 (Build 13628.20118)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)
### <a name="feature-updates"></a><span data-ttu-id="224d0-777">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-777">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="224d0-778">Teams</span><span class="sxs-lookup"><span data-stu-id="224d0-778">Teams</span></span>
- <span data-ttu-id="224d0-779">**更多主題：** 桌面和網頁用戶端可使用新的主題。</span><span class="sxs-lookup"><span data-stu-id="224d0-779">**More themes:** New themes are now available for desktop and web clients.</span></span>

- <span data-ttu-id="224d0-780">**PPT 共用：** Teams 中的簡報者檢視畫面：當您從 Teams 共用區選取 PowerPoint 檔案之後，系統會自動開啟 [簡報者檢視畫面]。</span><span class="sxs-lookup"><span data-stu-id="224d0-780">**PPT Sharing:** Presenter View in Teams Once you select a PowerPoint file from the Teams Share Tray, Presenter View is opened automatically.</span></span> <span data-ttu-id="224d0-781">您可以查看目前的投影片、投影片附註，以及投影片組中所有投影片的縮圖條，以輕鬆進行臨時的投影片瀏覽。</span><span class="sxs-lookup"><span data-stu-id="224d0-781">You can see the current slide, the slide notes, and a thumbnail strip of all the slides in the deck for easy ad-hoc slide navigation.</span></span> <span data-ttu-id="224d0-782">此檢視完全位於幕後，且由掌控螢幕的簡報者所專有。</span><span class="sxs-lookup"><span data-stu-id="224d0-782">This view is completely behind the scenes, and it’s private to the presenter in control.</span></span> <span data-ttu-id="224d0-783">您的觀眾只能看見您目前的投影片 (以大型紅色方塊醒目提示)，或他們所選擇要瀏覽的投影片 (如果您未鎖定觀眾瀏覽版面)。</span><span class="sxs-lookup"><span data-stu-id="224d0-783">Your audience can only see your current slide (highlighted in the big red box), or the slide that they choose to navigate to (if audience navigation is not locked by you).</span></span> 

- <span data-ttu-id="224d0-784">**在 Mac 上共用桌面或視窗時包含電腦音效** 當您從 Mac 版 Teams 共用桌面或視窗時，現在可以包含電腦的聲音，讓已加入會議的人可以聽到從您的電腦播放的音訊。</span><span class="sxs-lookup"><span data-stu-id="224d0-784">**Include computer sound when desktop or window sharing on Mac** When you share a desktop or window from Teams on Mac, you can now include your computer's sound so people that have joined the meeting can hear the audio playing out of your computer.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)
<br/>

## <a name="version-2101-january-09"></a><span data-ttu-id="224d0-786">版本 2101：1 月 9 日</span><span class="sxs-lookup"><span data-stu-id="224d0-786">Version 2101: January 09</span></span>
<span data-ttu-id="224d0-787">*版本 2101 (組建 13628.20118)*</span><span class="sxs-lookup"><span data-stu-id="224d0-787">*Version 2101 (Build 13628.20118)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-789">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-789">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-790">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-790">Outlook</span></span>

- <span data-ttu-id="224d0-791">**單鍵寫作建議：** 只要按一下，就能套用寫作建議。</span><span class="sxs-lookup"><span data-stu-id="224d0-791">**One-click writing suggestions:** Apply writing suggestions with a single click.</span></span> <span data-ttu-id="224d0-792">編輯器會校正拼字和文法，並提供潤飾寫作的建議。</span><span class="sxs-lookup"><span data-stu-id="224d0-792">Editor corrects spelling and grammar and gives you ideas for refining your writing.</span></span> [<span data-ttu-id="224d0-793">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-793">Learn more</span></span>](https://support.office.com/article/1e72a440-89a6-457c-bd76-cd5cea901dc0)<br /><span data-ttu-id="224d0-794">在[部落格文章](https://insider.office.com/zh-TW/blog/microsoft-editor-gets-an-upgrade)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="224d0-794">See details in [blog post](https://insider.office.com/zh-TW/blog/microsoft-editor-gets-an-upgrade)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-797">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-797">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-798">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-798">Outlook</span></span>

- <span data-ttu-id="224d0-799">我們已修正會導致某些使用者在特定搜尋案例中遇到 Outlook 異常關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-799">We fixed an issue that caused some users to experience Outlook to close unexpectedly in certain search scenarios.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2101-january-07"></a><span data-ttu-id="224d0-801">版本 2101：1 月 7 日</span><span class="sxs-lookup"><span data-stu-id="224d0-801">Version 2101: January 07</span></span>
<span data-ttu-id="224d0-802">*版本 2101 (組建 13628.20030)*</span><span class="sxs-lookup"><span data-stu-id="224d0-802">*Version 2101 (Build 13628.20030)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-804">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-804">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-805">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-805">Excel</span></span>

- <span data-ttu-id="224d0-806">**同時取消隱藏多個工作表：** 不再需要一次取消隱藏一個工作表，可以一次取消隱藏多個隱藏的工作表。</span><span class="sxs-lookup"><span data-stu-id="224d0-806">**Unhide many sheets at the same time:** No need to unhide one sheet at a time anymore -- unhide multiple hidden sheets at once.</span></span> [<span data-ttu-id="224d0-807">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-807">Learn more</span></span>](https://support.office.com/article/69f2701a-21f5-4186-87d7-341a8cf53344)

- <span data-ttu-id="224d0-808">**改善條件式格式設定對話方塊：**[條件式格式設定] 對話方塊現在可以調整大小，且現在您只要按一下就能複製規則。</span><span class="sxs-lookup"><span data-stu-id="224d0-808">**Improved Conditional Formatting dialogs:** Conditional Formatting dialogs are now resizable, and now you can duplicate the rule with a single click.</span></span> [<span data-ttu-id="224d0-809">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-809">Learn more</span></span>](https://support.office.com/article/fed60dfa-1d3f-4e13-9ecb-f1951ff89d7f)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-812">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-812">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-813">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-813">Excel</span></span>

- <span data-ttu-id="224d0-814">修正以下問題：Excel 錯誤地顯示檔案新版本可用的訊息列，並強制使用者將變更儲存到活頁簿的副本中或捨棄變更。</span><span class="sxs-lookup"><span data-stu-id="224d0-814">Fixed an issue where Excel would incorrectly show a message bar that a new version of the file is available and force the user to save their changes in a copy of the workbook or discard their changes.</span></span>


- <span data-ttu-id="224d0-815">修正了 Selection.Parent.Copy 通話后切換分隔符號的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-815">Fixed an issue with switching separators after a Selection.Parent.Copy call.</span></span>


- <span data-ttu-id="224d0-816">對將格式設定樣式套用至樞紐分析表時的效能進行改善。</span><span class="sxs-lookup"><span data-stu-id="224d0-816">Made a performance improvement when applying formatting styles to pivot tables.</span></span>


- <span data-ttu-id="224d0-817">修正在開啟含有 Excel 4.0 巨集的 Excel 增益集檔案時，Excel 可能會停用巨集而不提示的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-817">Fixed an issue where Excel may leave macros disabled without prompting when opening an Excel Add-in file containing Excel 4.0 Macros.</span></span>


- <span data-ttu-id="224d0-818">更新以便在從 Excel 複製圖表並貼上到 Word 中時保留小數點和千位分隔符號設定</span><span class="sxs-lookup"><span data-stu-id="224d0-818">Update so that decimal and thousands separators settings carryover when copying a chart from Excel and pasting into Word</span></span>


- <span data-ttu-id="224d0-819">修正了當開啟具有無效檔案内容 (建立時間、修改時間等) 的 UNC 檔案時，Excel 會意外關閉的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-819">Fixed an issue where Excel would close unexpectedly when opening UNC files that have invalid file attributes (creation time, modified time, etc.)</span></span>


- <span data-ttu-id="224d0-820">修正在使用 STOCKHISTORY 函數時，可能會導致「資源不足」警示的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-820">Fixed an issue which could cause an "out of resources" alert when using the STOCKHISTORY function.</span></span>


- <span data-ttu-id="224d0-821">將 FuzzyClustering DLL 新增至 PQ DLL 清單。</span><span class="sxs-lookup"><span data-stu-id="224d0-821">Added a FuzzyClustering dll to PQ dlls list.</span></span>


- <span data-ttu-id="224d0-822">此變更可解決與變更 SVG 影像的外框顏色相關的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-822">This change addresses an issue related to changing outline colors of SVG images.</span></span>


- <span data-ttu-id="224d0-823">我們已修正 PowerPoint 中內嵌的 Excel 範圍預覽會顯示不正確大小的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-823">We have fixed an issue where Preview of embedded Excel range in PowerPoint shows incorrect size.</span></span>


### <a name="onenote"></a><span data-ttu-id="224d0-824">OneNote</span><span class="sxs-lookup"><span data-stu-id="224d0-824">OneNote</span></span>

- <span data-ttu-id="224d0-825">此變更可解決影響 OneNote 的呈現問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-825">This change addresses a rendering issue affecting OneNote.</span></span>


### <a name="outlook"></a><span data-ttu-id="224d0-826">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-826">Outlook</span></span>

- <span data-ttu-id="224d0-827">我們已修正以下問題：導致使用者無法指定在從 Word 啟動合併列印時允許存取時長，從而導致他們取得過多提示的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-827">We fixed an issue that caused users to be unable to specify how long they wanted to allow access for when starting a mail merge from Word, resulting in them getting excess prompts.</span></span>


- <span data-ttu-id="224d0-828">此變更使得 Outlook 可以利用能夠向使用者隱藏 Exchange Online 封存信箱顯示的 Exchange Server 設定。</span><span class="sxs-lookup"><span data-stu-id="224d0-828">This change enables Outlook to take advantage of an Exchange server setting that suppresses the display of the Exchange Online Archive Mailbox to end users.</span></span>


- <span data-ttu-id="224d0-829">我們已修正會導致 Outlook 對基於兌換增益集的使用者意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-829">We fixed an issue that caused a Outlook to close unexpectedly for users of Redemption based Add-ins.</span></span>


- <span data-ttu-id="224d0-830">我們已修正造成使用者無法選取多個類別進行搜尋的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-830">We fixed and issue that caused users to be unable to select more than one category to search.</span></span>


- <span data-ttu-id="224d0-831">我們已修正當活動是從另一個約會複製而來時，造成部分行事曆項目的開始時間發生意外變更的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-831">We fixed an issue that caused the start time of some calendar items to change unexpectedly when the event is copied from another appointment.</span></span>


- <span data-ttu-id="224d0-832">解決了當純文字 S/MIME 郵件在傳送時發生亂碼的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-832">Addressed an issue that caused plain text S/MIME messages to become garbled when sending.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="224d0-833">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-833">PowerPoint</span></span>

- <span data-ttu-id="224d0-834">此變更可解決合併圖案處理文字時的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-834">This change addresses an issue with Merge Shapes working with text.</span></span>


- <span data-ttu-id="224d0-835">此變更可解決與變更 SVG 影像的外框顏色相關的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-835">This change addresses an issue related to changing outline colors of SVG images.</span></span>


- <span data-ttu-id="224d0-836">此變更解决了在投影片放映中迴圈播放背景影片的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-836">This change addresses an issue with looping background videos playback in Slide Show.</span></span>


- <span data-ttu-id="224d0-837">我們已修正在 QAT 中新增的字型大小命令在更新時自動完成到最近定義的字型大小的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-837">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


### <a name="project"></a><span data-ttu-id="224d0-838">Project</span><span class="sxs-lookup"><span data-stu-id="224d0-838">Project</span></span>

- <span data-ttu-id="224d0-839">修正資源的最大可用量不一定會反映對最大可用量的最新更新的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-839">Fixed an issue where a resource's max units would not always reflect the latest update to max units.</span></span>


### <a name="visio"></a><span data-ttu-id="224d0-840">Visio</span><span class="sxs-lookup"><span data-stu-id="224d0-840">Visio</span></span>

- <span data-ttu-id="224d0-841">此問題是由於最近的迴歸而造成。</span><span class="sxs-lookup"><span data-stu-id="224d0-841">The issue occurred due to a recent regression.</span></span> <span data-ttu-id="224d0-842">我們已解決此問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-842">We have resolved the issue.</span></span> <span data-ttu-id="224d0-843">[另存成網頁] 對話方塊現在會根據使用者的輸入正確填入欄位，且使用者可以將其檔案順暢地儲存為網頁。</span><span class="sxs-lookup"><span data-stu-id="224d0-843">"Save as Web Page" dialog will now have the fields correctly populated as per the user inputs and users can seamlessly save their files as web pages.</span></span>


- <span data-ttu-id="224d0-p144">修正此問題。您現在可以在其他 Office 應用程式 (例如 PowerPoint 和 Word) 中將 Visio 檔案內嵌為物件，並順暢地透過這些應用程式存取檔案。</span><span class="sxs-lookup"><span data-stu-id="224d0-p144">This issue has been fixed. You can now embed Visio files as objects in other Office applications like PowerPoint and Word and seamlessly access them from within these applications.</span></span>


### <a name="word"></a><span data-ttu-id="224d0-846">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-846">Word</span></span>

- <span data-ttu-id="224d0-847">修正使用自訂雜湊設定的電腦，在進入使用 sha512 以外雜湊設定的共同作業工作階段時會發生問題的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-847">Fixed an issue where machines with custom hash settings were running in to issues when they got into a collab session with a hash setting other than sha512.</span></span>


- <span data-ttu-id="224d0-848">此變更可解決與變更 SVG 影像的外框顏色相關的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-848">This change addresses an issue related to changing outline colors of SVG images.</span></span>


- <span data-ttu-id="224d0-849">修正使用 @提及編輯註解文章時的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-849">Fixed an issue when editing commenting post with @mention.</span></span>


- <span data-ttu-id="224d0-850">修正問題以讓新式註解更穩定。</span><span class="sxs-lookup"><span data-stu-id="224d0-850">Fixed an issue to make Modern comments more robust.</span></span>


- <span data-ttu-id="224d0-851">我們已修正有關删除標記為不可編輯的內容控制項中的新式註解的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-851">We fixed an issue around deleting modern comments in a content control that is marked as not editable.</span></span>


- <span data-ttu-id="224d0-852">修正在註解卡片底部輸入文字時的動畫。</span><span class="sxs-lookup"><span data-stu-id="224d0-852">Fix animation when typing on the bottom of a comment card.</span></span>


- <span data-ttu-id="224d0-853">修正註解卡片上的回覆方塊不在畫面上的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-853">Fixes an issue where the reply box on a comment card is off the screen.</span></span>


- <span data-ttu-id="224d0-854">修正頁面頂端顯示的註解卡片問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-854">Fixes an issue with a comment card displaying at top of page.</span></span>


- <span data-ttu-id="224d0-855">修正註解中文字可能不在畫面上的錯誤。</span><span class="sxs-lookup"><span data-stu-id="224d0-855">Fixes bug in comments where text can scroll off screen.</span></span>


- <span data-ttu-id="224d0-856">修正註解窗格中巢狀捲軸的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-856">Fix and issue with nested scrollbars in the comments pane.</span></span>


- <span data-ttu-id="224d0-857">建立新的 Word 執行個體時註解草稿會消失。</span><span class="sxs-lookup"><span data-stu-id="224d0-857">Comment drafts disappears when creating a new Word instance.</span></span>


- <span data-ttu-id="224d0-858">我們已修正將文件儲存為含有隱藏文字的 PDF 時，Word 停滯的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-858">We fixed an issue where Word hangs when saving document to PDF with hidden text.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2012-january-04"></a><span data-ttu-id="224d0-860">版本 2012：1 月 4 日</span><span class="sxs-lookup"><span data-stu-id="224d0-860">Version 2012: January 04</span></span>
<span data-ttu-id="224d0-861">*版本 2012 (組建 13530.20316)*</span><span class="sxs-lookup"><span data-stu-id="224d0-861">*Version 2012 (Build 13530.20316)*</span></span>
* <span data-ttu-id="224d0-862">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="224d0-862">Various bugs and performance fixes.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-864">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-864">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-865">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-865">Excel</span></span>

- <span data-ttu-id="224d0-866">**強制標籤：** 使用者若已設定強制標籤原則，其系統管理員將需要標記其文件和電子郵件。</span><span class="sxs-lookup"><span data-stu-id="224d0-866">**Mandatory Labeling:** Users with the Mandatory Labeling policy set their Admins will be required to label their documents and emails.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="224d0-867">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-867">PowerPoint</span></span>

- <span data-ttu-id="224d0-868">**強制標籤：** 使用者若已設定強制標籤原則，其系統管理員將需要標記其文件和電子郵件。</span><span class="sxs-lookup"><span data-stu-id="224d0-868">**Mandatory Labeling:** Users with the Mandatory Labeling policy set their Admins will be required to label their documents and emails.</span></span>

### <a name="word"></a><span data-ttu-id="224d0-869">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-869">Word</span></span>

- <span data-ttu-id="224d0-870">**強制標籤：** 使用者若已設定強制標籤原則，其系統管理員將需要標記其文件和電子郵件。</span><span class="sxs-lookup"><span data-stu-id="224d0-870">**Mandatory Labeling:** Users with the Mandatory Labeling policy set their Admins will be required to label their documents and emails.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2012-december-28"></a><span data-ttu-id="224d0-872">版本 2012：12 月 28 日</span><span class="sxs-lookup"><span data-stu-id="224d0-872">Version 2012: December 28</span></span>
<span data-ttu-id="224d0-873">*版本 2012 (組建 13530.20264)*</span><span class="sxs-lookup"><span data-stu-id="224d0-873">*Version 2012 (Build 13530.20264)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-875">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-875">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-876">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-876">Outlook</span></span>

- <span data-ttu-id="224d0-877">我們已修正會導致某些客戶在載入行事歷時遇到停滯的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-877">We fixed an issue that caused some customers to encounter a hang while loading their calendars.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2012-december-21"></a><span data-ttu-id="224d0-879">版本 2012：12 月 21 日</span><span class="sxs-lookup"><span data-stu-id="224d0-879">Version 2012: December 21</span></span>
<span data-ttu-id="224d0-880">*版本 2012 (組建 13530.20218)*</span><span class="sxs-lookup"><span data-stu-id="224d0-880">*Version 2012 (Build 13530.20218)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-882">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-882">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-883">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-883">Excel</span></span>

- <span data-ttu-id="224d0-884">**將敏感度標籤的相關稽核資料傳送給 M365 系統管理員：** 當使用者套用、變更或移除其檔案和電子郵件上的靈敏度標籤時，Office 會將稽核資料發送到 M365 稽核後端，供系統管理員查看。</span><span class="sxs-lookup"><span data-stu-id="224d0-884">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="224d0-885">此項幕後功能 (無 UI) 為系統管理員權益。</span><span class="sxs-lookup"><span data-stu-id="224d0-885">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="outlook"></a><span data-ttu-id="224d0-886">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-886">Outlook</span></span>

- <span data-ttu-id="224d0-887">**在連續會議之間置入時間：** 將會議預設為延後 5-10 分鐘開始，讓出席者有時間休息，或前往下一個地點。</span><span class="sxs-lookup"><span data-stu-id="224d0-887">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to start 5-10 min late by default.</span></span> [<span data-ttu-id="224d0-888">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-888">Learn more</span></span>](https://support.office.com/article/be84396a-0903-4e25-b31c-1c99ce0dacf2)

- <span data-ttu-id="224d0-889">**將敏感度標籤的相關稽核資料傳送給 M365 系統管理員：** 當使用者套用、變更或移除其檔案和電子郵件上的靈敏度標籤時，Office 會將稽核資料發送到 M365 稽核後端，供系統管理員查看。</span><span class="sxs-lookup"><span data-stu-id="224d0-889">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="224d0-890">此項幕後功能 (無 UI) 為系統管理員權益。</span><span class="sxs-lookup"><span data-stu-id="224d0-890">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="224d0-891">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-891">PowerPoint</span></span>

- <span data-ttu-id="224d0-892">**將敏感度標籤的相關稽核資料傳送給 M365 系統管理員：** 當使用者套用、變更或移除其檔案和電子郵件上的靈敏度標籤時，Office 會將稽核資料發送到 M365 稽核後端，供系統管理員查看。</span><span class="sxs-lookup"><span data-stu-id="224d0-892">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="224d0-893">此項幕後功能 (無 UI) 為系統管理員權益。</span><span class="sxs-lookup"><span data-stu-id="224d0-893">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="word"></a><span data-ttu-id="224d0-894">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-894">Word</span></span>

- <span data-ttu-id="224d0-895">**將敏感度標籤的相關稽核資料傳送給 M365 系統管理員：** 當使用者套用、變更或移除其檔案和電子郵件上的靈敏度標籤時，Office 會將稽核資料發送到 M365 稽核後端，供系統管理員查看。</span><span class="sxs-lookup"><span data-stu-id="224d0-895">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="224d0-896">此項幕後功能 (無 UI) 為系統管理員權益。</span><span class="sxs-lookup"><span data-stu-id="224d0-896">This is a silent functionality (no UI) for administrator benefit.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-899">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-899">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="224d0-900">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-900">PowerPoint</span></span>

- <span data-ttu-id="224d0-901">我們已修正一個問題，即在 QAT 中新增的字型大小命令在更新時，會自動完成到最接近的已定義字型大小。</span><span class="sxs-lookup"><span data-stu-id="224d0-901">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2012-december-14"></a><span data-ttu-id="224d0-903">版本2012：12 月 14 日</span><span class="sxs-lookup"><span data-stu-id="224d0-903">Version 2012: December 14</span></span>
<span data-ttu-id="224d0-904">*版本 2012 (組建 13530.20144)*</span><span class="sxs-lookup"><span data-stu-id="224d0-904">*Version 2012 (Build 13530.20144)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-906">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-906">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-907">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-907">Outlook</span></span>

- <span data-ttu-id="224d0-908">**雲端中的 Outlook 設定：** 選擇您的 Windows 版 Outlook 設定，例如自動回復、焦點收件匣和隱私權，並在任何電腦上使用這些功能。</span><span class="sxs-lookup"><span data-stu-id="224d0-908">**Your Outlook settings in the cloud:** Choose your Outlook for Windows settings like Automatic Replies, Focused Inbox, and Privacy, and get to them on any PC.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-911">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-911">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="224d0-912">Office 套件</span><span class="sxs-lookup"><span data-stu-id="224d0-912">Office Suite</span></span>

- <span data-ttu-id="224d0-913">優化的二進位大小。</span><span class="sxs-lookup"><span data-stu-id="224d0-913">Optimized binary size.</span></span>


- <span data-ttu-id="224d0-914">Anaheim WebView 目前尚不支援 Windows 資訊保護(WIP)。</span><span class="sxs-lookup"><span data-stu-id="224d0-914">Anaheim WebView does not support Windows Information Protection (WIP) yet.</span></span> <span data-ttu-id="224d0-915">有了此修正程式，Office addin 平臺便會回到處於 WIP 啟用環境中的低層級 WebView。</span><span class="sxs-lookup"><span data-stu-id="224d0-915">With this fix Office addin platform falls back to down level WebView in WIP enabled environment.</span></span> <span data-ttu-id="224d0-916">根據客戶的電腦環境，這可以是 Edge Spartan WebView 或 Trident WebView。</span><span class="sxs-lookup"><span data-stu-id="224d0-916">That can be either Edge Spartan WebView or Trident WebView depending on customer's machine environment.</span></span> <span data-ttu-id="224d0-917">兩個低層級 WebViews 皆支援 WIP。</span><span class="sxs-lookup"><span data-stu-id="224d0-917">Both down level WebViews support WIP.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2012-december-07"></a><span data-ttu-id="224d0-919">版本2012：12 月 7 日</span><span class="sxs-lookup"><span data-stu-id="224d0-919">Version 2012: December 07</span></span>
<span data-ttu-id="224d0-920">*版本 2012 (組建 13530.20064)*</span><span class="sxs-lookup"><span data-stu-id="224d0-920">*Version 2012 (Build 13530.20064)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-922">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-922">Feature updates</span></span>

### <a name="teams"></a><span data-ttu-id="224d0-923">Teams</span><span class="sxs-lookup"><span data-stu-id="224d0-923">Teams</span></span>

- <span data-ttu-id="224d0-924">**Teams 現在支援 Windows 原生通知：** 使用者現在可以選取其偏好的通知傳送方式，即透過 Teams 內建橫幅或 Windows 原生橫幅。</span><span class="sxs-lookup"><span data-stu-id="224d0-924">**Windows Native Notification are now Supported on Teams:** Users can now select their preferred means of notification delivery, either through Teams built-in banners or the Windows native banners.</span></span>


- <span data-ttu-id="224d0-925">**Citrix 與 VMWare VDI 的 Teams 會議 2X2 圖庫檢視：** Teams 用戶端在 VDI 最佳化模式中時，Teams 的 VDI 2x2 圖庫檢視功能會啟用，可讓您在 2x2 圖庫中檢視 Citrix、VMWare 之 VDI 用戶端的最多四個出席者影片。</span><span class="sxs-lookup"><span data-stu-id="224d0-925">**Teams Meetings 2x2 Gallery View in Citrix and VMWare VDI:** Teams on VDI 2x2 Gallery View feature will enable to view up to four attendees videos in 2x2 Gallery View on VDI clients from Citrix, VMWare when Teams client in VDI optimized mode.</span></span>


- <span data-ttu-id="224d0-926">**會議反應：**  會議反應是在會議中互動的新方式。</span><span class="sxs-lookup"><span data-stu-id="224d0-926">**Meeting Reactions:**  Meeting reactions are a new way to interact in meetings.</span></span> <span data-ttu-id="224d0-927">參與者可以傳送以時間列表顯示的反應，其出現的地點為正在共用的內容上，以及有在會議階段上顯示之傳送反應的個人上。</span><span class="sxs-lookup"><span data-stu-id="224d0-927">Participants can send reactions which are shown as a stream on content that is being shared, and on the individual who sent the reaction if they're displayed on the meeting stage.</span></span> 


- <span data-ttu-id="224d0-928">**Web 會議的共聚模式和大型圖庫** 大型圖庫可讓您一次看到最多 49 個其他人員的影片。</span><span class="sxs-lookup"><span data-stu-id="224d0-928">**Together Mode and Large Gallery for Web Meetings** Large Gallery enables you to see the videos of up to 49 other people at once.</span></span> <span data-ttu-id="224d0-929">當至少 10 人開啟相機時，即可使用此選項。</span><span class="sxs-lookup"><span data-stu-id="224d0-929">This option is available when at least ten people have their cameras turned on.</span></span> <span data-ttu-id="224d0-930">共聚模式可讓您感覺與會議中每個人處於相同的共用空間。</span><span class="sxs-lookup"><span data-stu-id="224d0-930">Together mode lets you feel like you're in the same shared space with everyone in the meeting.</span></span> <span data-ttu-id="224d0-931">當會議中至少有五個人時，即可使用共聚模式。</span><span class="sxs-lookup"><span data-stu-id="224d0-931">Together mode is available when there are at least five people in the meeting.</span></span> 


- <span data-ttu-id="224d0-932">**通話合併** 通話合併可讓使用者將其撥打的新通話，或新來電合併到其 1 對 1 或群組通話中。</span><span class="sxs-lookup"><span data-stu-id="224d0-932">**Call Merge** Call Merge allows users to merge a new call they place, or a new incoming call, into their 1-1 or group call.</span></span> <span data-ttu-id="224d0-933">這適用於Teams VOIP 通話和 PSTN 通話。</span><span class="sxs-lookup"><span data-stu-id="224d0-933">This applies to Teams VOIP calls and PSTN calls.</span></span> 


### <a name="visio"></a><span data-ttu-id="224d0-934">Visio</span><span class="sxs-lookup"><span data-stu-id="224d0-934">Visio</span></span>

- <span data-ttu-id="224d0-935">**新 Azure 樣板和圖案：** 我們新增了更多的樣板來協助您建立最新的 Azure 圖表。</span><span class="sxs-lookup"><span data-stu-id="224d0-935">**New Azure stencils and shapes:** We've added many more stencils to help you create up-to-date Azure diagrams.</span></span> [<span data-ttu-id="224d0-936">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-936">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-939">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-939">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-940">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-940">Excel</span></span>

- <span data-ttu-id="224d0-941">我們已修正部分功能區元素未以簡體中文進行當地語系化的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-941">We fixed an issue where some Ribbon elements were not localized in Simplified Chinese.</span></span>


- <span data-ttu-id="224d0-942">我們已修正更新時 Excel 意外終止的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-942">We fixed an issue where Excel terminated unexpectedly when updating.</span></span>


- <span data-ttu-id="224d0-943">我們已修正從 OneDrive 本機同步處理資料夾插入檔案時，[插入物件] 命令沒有顯示正確圖示的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-943">We fixed an issue where the Insert Object command does not show the correct icon when inserting a file from OneDrive local sync folder.</span></span>


- <span data-ttu-id="224d0-944">已修正在覆寫模式下編輯時，使用需要使用 IME 的語言進行編輯時表現不佳的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-944">Fixed an issue where editing in languages that require use of IME would behave poorly when editing in overwrite mode.</span></span>


- <span data-ttu-id="224d0-945">修正此問題：一些使用者在共同撰寫時會錯誤地看到通知他們檔案新版本的訊息列。</span><span class="sxs-lookup"><span data-stu-id="224d0-945">Fixed an issue where some users would incorrectly see a message bar informing them of a new version of a file when coauthoring.</span></span>


- <span data-ttu-id="224d0-946">已修正在公式檢視中複製和貼上資料時 Excel 意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-946">Fixed an issue where Excel would close unexpectedly when copying and pasting data in formula view.</span></span>


- <span data-ttu-id="224d0-947">修正在自動儲存被停用時通知中說明文章的斷開連結。</span><span class="sxs-lookup"><span data-stu-id="224d0-947">Fixed a broken hyperlink to a help article in an alert in case Autosave becomes disabled.</span></span>


- <span data-ttu-id="224d0-948">我們已修正以下問題：當 Excel 以某些語言執行時輸入資料可能導致 Excel 停止運作。</span><span class="sxs-lookup"><span data-stu-id="224d0-948">We fixed an issue where when entering data while Excel is running in certain languages could cause Excel to stop working.</span></span>


- <span data-ttu-id="224d0-949">此變更解决了在方程式中正確顯示字型的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-949">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="224d0-950">這修正了Power Pivot 無法正確導入定位字元分隔的文字檔的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-950">This fixes an issue where Power Pivot wasn't able to correctly import a tab-delimited text file.</span></span>


### <a name="outlook"></a><span data-ttu-id="224d0-951">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-951">Outlook</span></span>

- <span data-ttu-id="224d0-952">我們已修正會導致「收件者:」欄位在工作狀態報告中空白的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-952">We fixed an issue that caused the To: field to be blank in task status reports.</span></span>


- <span data-ttu-id="224d0-953">我們已修正會導致 MailItem.BeforeAttachmentAdd 事件中斷的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-953">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="224d0-954">我們已修正導致使用者在從 Outlook 以外的應用程式傳送 Outlook 郵件時遇到一些問題的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-954">We fixed an issue that was causing users to experience some issues when sending Outlook mail from applications other than Outlook.</span></span>


- <span data-ttu-id="224d0-955">我們已修正會導致 SmartLinks 在儲存至草稿時丟失其格式的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-955">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


- <span data-ttu-id="224d0-956">我們已修正將附件新增到從 zip 檔案開啟的郵件時會失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-956">We fixed and issue where adding an attachment to a message opened from a zip file would fail.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="224d0-957">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-957">PowerPoint</span></span>

- <span data-ttu-id="224d0-958">修正從 Word 到 PowerPoint 複製/貼上方程式時發生的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-958">Fixed an issue with copy/paste of an equation from Word to Powerpoint</span></span>


- <span data-ttu-id="224d0-959">此變更解決筆跡分析期間發生的超時問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-959">This change addresses an issue related to timeouts experienced during ink analysis.</span></span>


- <span data-ttu-id="224d0-960">此變更解決建立動畫 GIF 使用者介面中的語法錯誤。</span><span class="sxs-lookup"><span data-stu-id="224d0-960">This change addresses a grammatical error in the Create an Animated GIF user interface.</span></span>


- <span data-ttu-id="224d0-961">此變更解决對某些幾何圖形套用 [合併圖案] 作業時路徑填充的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-961">This change addresses an issue with path fills when applying Merge Shapes operations with certain geometries.</span></span>


- <span data-ttu-id="224d0-962">此變更解決了在方程式中正確顯示字型的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-962">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="224d0-963">此變更解決了處理載入影片期間可能發生錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-963">This change addresses an issue with handling errors that may occur during video loading.</span></span>


- <span data-ttu-id="224d0-964">我們已修正 Slide.Shapes.AddMediaObject2 會對舊版影片格式 (MPG-1、Mpeg-2) 發生當機的 VBA 問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-964">We fixed a VBA issue where Slide.Shapes.AddMediaObject2 crashing with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="224d0-965">我們已修正一個問題，即未知的共同作者的狀態指示器在有關於共同作者的更多資訊可用時沒有完全重新整理。</span><span class="sxs-lookup"><span data-stu-id="224d0-965">We fixed an issue where an unknown coauthor's presence indicator does not get completely refreshed when more information about the coauthor is available.</span></span>


- <span data-ttu-id="224d0-966">修正當投影片檢視的大小在尺規開啟時被解除引用的 null 指標。</span><span class="sxs-lookup"><span data-stu-id="224d0-966">Fixed a null pointer being dereferenced when slide view is resized with ruler turned on.</span></span>


- <span data-ttu-id="224d0-967">已修正無法正確開啟部分損壞的 PowerPoint 檔案 (即使在文件修復之後) 的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-967">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="project"></a><span data-ttu-id="224d0-968">Project</span><span class="sxs-lookup"><span data-stu-id="224d0-968">Project</span></span>

- <span data-ttu-id="224d0-969">我們已修正預期使用者開啟的專案應已儲存更新的資訊，但發現遺漏更新的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-969">We fixed an issue where users open projects which have supposedly been saved with updated information, but find the updates are is missing.</span></span>


- <span data-ttu-id="224d0-970">我們已修正若交付項目相關聯的 SharePoint 網站已不再存在時，無法刪除交付項目的相依性的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-970">We fixed an issue where you couldn't delete dependencies on the deliverables if the SharePoint site the deliverable was associated with no longer existed.</span></span>


- <span data-ttu-id="224d0-971">修正開啟具有大量資源的專案時所花費的時間很長的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-971">Fixed an issue where opening a project with a lot of resources was taking a long time.</span></span>


- <span data-ttu-id="224d0-972">修正使用者可能會看到多個未指派工作分派與任務相關聯的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-972">Fixed an issue where users may see multiple unassigned assignments associated with a task.</span></span>


- <span data-ttu-id="224d0-973">已修正在大型專案中，輸入任務名稱的速度可能非常緩慢的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-973">Fixed an issue where in large projects it can be very slow to enter a task name.</span></span>


- <span data-ttu-id="224d0-974">已修正如果特定專案在負載的特定部分發生問題，可能會開啟特定專案的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-974">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>


### <a name="word"></a><span data-ttu-id="224d0-975">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-975">Word</span></span>

- <span data-ttu-id="224d0-976">貼上為純文字通常優於貼上為 RTF 文字。</span><span class="sxs-lookup"><span data-stu-id="224d0-976">Paste as plain text is often preferred to pasting as rich text.</span></span> <span data-ttu-id="224d0-977">此快顯功能表修正功能可讓使用者貼上純文字格式。</span><span class="sxs-lookup"><span data-stu-id="224d0-977">This context menu fix allows the user to paste as plain text.</span></span> <span data-ttu-id="224d0-978">否則，使用者必須複製至純文字編輯器 (如 [記事本])，然後從 [記事本] 複製到所要的目標應用程式</span><span class="sxs-lookup"><span data-stu-id="224d0-978">Else the user would have to copy into a plain-text editor like Notepad and then copy from Notepad into the desired target app</span></span>


- <span data-ttu-id="224d0-979">修正從 Word 到 PowerPoint 複製/貼上方程式時發生的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-979">Fixed an issue with copy/paste of an equation from Word to Powerpoint</span></span>


- <span data-ttu-id="224d0-980">此變更解決編輯檔時游標的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-980">This change addresses an issue with the cursor when editing a document.</span></span>


- <span data-ttu-id="224d0-981">我們已修正在縮放圖片時，圖片變得模糊的相關問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-981">We fixed an issue related to pictures becoming blurry while zooming.</span></span>


- <span data-ttu-id="224d0-982">我們已修正長超連結被截斷的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-982">We fixed an issue where long hyperlinks were getting truncated.</span></span>


### <a name="office-suite"></a><span data-ttu-id="224d0-983">Office 套件</span><span class="sxs-lookup"><span data-stu-id="224d0-983">Office Suite</span></span>

- <span data-ttu-id="224d0-984">Office 套件已修復此問題：在某些較舊的版本上安裝較新版的 Office 時，可能會造成功能受損 (例如由於遺失登錄專案而無法使用 Power Query)。</span><span class="sxs-lookup"><span data-stu-id="224d0-984">Office Suite Fixed an issue where installing a newer version of Office over certain older versions can result in impaired functionality (such as being unable to use Power Query) due to missing registry entries.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2011-december-01"></a><span data-ttu-id="224d0-986">版本2011：12 月1 日</span><span class="sxs-lookup"><span data-stu-id="224d0-986">Version 2011: December 01</span></span>
<span data-ttu-id="224d0-987">*版本 2011 (組建 13426.20306)*</span><span class="sxs-lookup"><span data-stu-id="224d0-987">*Version 2011 (Build 13426.20306)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-989">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-989">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-990">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-990">Outlook</span></span>

- <span data-ttu-id="224d0-991">**每個線上會議：** 使用新設定將所有會議預設設定為線上，讓您輕鬆安排線上會議。</span><span class="sxs-lookup"><span data-stu-id="224d0-991">**Every meeting online:** Make it easier to schedule online meetings with a new setting to make all your meetings online by default.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-994">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-994">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-995">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-995">Outlook</span></span>

- <span data-ttu-id="224d0-996">我們已修正會導致某些會議的原始出席者在另一個出席者轉寄會議時收到取消通知的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-996">We fixed an issue that caused the original attendees of some meetings to receive a cancellation when another attendee forwards the meeting.</span></span>


- <span data-ttu-id="224d0-997">我們已修正會導致某些使用者未設定一或多個簽章時，在 [簽名] 下拉式清單中看不到任何簽名的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-997">We fixed an issue that caused some users to see no signatures in the signatures drop down despite having one or more signatures configured.</span></span>


### <a name="project"></a><span data-ttu-id="224d0-998">Project</span><span class="sxs-lookup"><span data-stu-id="224d0-998">Project</span></span>

- <span data-ttu-id="224d0-999">已修正如果特定專案在負載的特定部分發生問題，可能會開啟特定專案的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-999">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2011-november-24"></a><span data-ttu-id="224d0-1001">版本 2011：11 月 24 日</span><span class="sxs-lookup"><span data-stu-id="224d0-1001">Version 2011: November 24</span></span>
<span data-ttu-id="224d0-1002">*版本 2011 (組建 13426.20294)*</span><span class="sxs-lookup"><span data-stu-id="224d0-1002">*Version 2011 (Build 13426.20294)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-1004">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-1004">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="224d0-1005">Office 套件</span><span class="sxs-lookup"><span data-stu-id="224d0-1005">Office Suite</span></span>

- <span data-ttu-id="224d0-1006">修正從 Word 到 PowerPoint 複製/貼上方程式時發生的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1006">Fixed an issue with copy/paste of an equation from Word to Powerpoint</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2011-november-21"></a><span data-ttu-id="224d0-1008">版本 2011：11 月 21 日</span><span class="sxs-lookup"><span data-stu-id="224d0-1008">Version 2011: November 21</span></span>
<span data-ttu-id="224d0-1009">*版本 2011 (組建 13426.20274)*</span><span class="sxs-lookup"><span data-stu-id="224d0-1009">*Version 2011 (Build 13426.20274)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-1011">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-1011">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="224d0-1012">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-1012">PowerPoint</span></span>

- <span data-ttu-id="224d0-1013">**影片庫：** 在應用程式內使用精選的免版稅影片素材庫來提升您的文件</span><span class="sxs-lookup"><span data-stu-id="224d0-1013">**Video Library:** Elevate your documents with a library of curated, royalty-free video footage available in-app</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-1016">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-1016">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-1017">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1017">Outlook</span></span>

- <span data-ttu-id="224d0-1018">我們已修正會導致 MailItem.BeforeAttachmentAdd 事件中斷的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1018">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="224d0-1019">我們新增了一個 RegKey，可讓客戶停用 IDataObject 操作 (例如，拖曳拖放、剪貼簿) 中附件的 FileTime 包含內容。</span><span class="sxs-lookup"><span data-stu-id="224d0-1019">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span> <span data-ttu-id="224d0-1020">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments。</span><span class="sxs-lookup"><span data-stu-id="224d0-1020">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span></span> <span data-ttu-id="224d0-1021">REG_DWORD IncludeFileTimesInDataObject。</span><span class="sxs-lookup"><span data-stu-id="224d0-1021">REG_DWORD IncludeFileTimesInDataObject.</span></span> <span data-ttu-id="224d0-1022">0 = 不包含 filetimes。</span><span class="sxs-lookup"><span data-stu-id="224d0-1022">0 = filetimes are excluded.</span></span> <span data-ttu-id="224d0-1023">1 = (預設) 包含 filetimes</span><span class="sxs-lookup"><span data-stu-id="224d0-1023">1 = (default) filetimes are included</span></span>


- <span data-ttu-id="224d0-1024">我們已修正當回復含有「Azure 資訊保護」保護標籤的郵件時，會導致內嵌影像消失的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1024">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2011-november-18"></a><span data-ttu-id="224d0-1026">版本 2011：11 月 18 日</span><span class="sxs-lookup"><span data-stu-id="224d0-1026">Version 2011: November 18</span></span>
<span data-ttu-id="224d0-1027">*版本 2011 (組建 13426.20250)*</span><span class="sxs-lookup"><span data-stu-id="224d0-1027">*Version 2011 (Build 13426.20250)*</span></span>
* <span data-ttu-id="224d0-1028">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="224d0-1028">Various bugs and performance fixes.</span></span>

## <a name="version-2011-november-16"></a><span data-ttu-id="224d0-1029">版本 2011：10 月 16 日</span><span class="sxs-lookup"><span data-stu-id="224d0-1029">Version 2011: November 16</span></span>
<span data-ttu-id="224d0-1030">*版本 2011 (組建 13426.20234)*</span><span class="sxs-lookup"><span data-stu-id="224d0-1030">*Version 2011 (Build 13426.20234)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-1032">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-1032">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-1033">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1033">Outlook</span></span>

- <span data-ttu-id="224d0-1034">**所有裝置都有相同的簽章：** 在雲端中儲存簽章。</span><span class="sxs-lookup"><span data-stu-id="224d0-1034">**Same signature, all devices:** Your signature is stored in the cloud.</span></span> <span data-ttu-id="224d0-1035">只要建立一次，就能在所有使用 Outlook 的位置使用。</span><span class="sxs-lookup"><span data-stu-id="224d0-1035">Create it once and use it everywhere you use Outlook.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-1038">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-1038">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-1039">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1039">Outlook</span></span>

- <span data-ttu-id="224d0-1040">我們已修正傳送任務中的狀態報表時，導致 [收件者] 欄位為空白的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1040">We fixed an issue that caused the To field to be blank when sending a status report on a task.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="224d0-1041">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-1041">PowerPoint</span></span>

- <span data-ttu-id="224d0-1042">我們已修正 Slide.Shapes.AddMediaObject2 會對舊版影片格式 (MPG-1、Mpeg-2) 發生當機的 VBA 問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1042">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 crashing with legacy video formats (MPG-1,Mpeg-2).</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2011-november-09"></a><span data-ttu-id="224d0-1044">版本 2011：11 月 9 日</span><span class="sxs-lookup"><span data-stu-id="224d0-1044">Version 2011: November 09</span></span>
<span data-ttu-id="224d0-1045">*版本 2011 (組建 13426.20184)*</span><span class="sxs-lookup"><span data-stu-id="224d0-1045">*Version 2011 (Build 13426.20184)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-1047">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-1047">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-1048">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-1048">Excel</span></span>

- <span data-ttu-id="224d0-1049">**從查詢建立 Power Platform 資料流程：** 您現在可以將查詢匯出至 Power Query 範本，以建立新的 Power Platform 資料流程</span><span class="sxs-lookup"><span data-stu-id="224d0-1049">**Create Power Platform dataflows from queries:** You can now export your queries into Power Query templates that can be used to create new Power Platform dataflows</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-1052">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-1052">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="224d0-1053">存取</span><span class="sxs-lookup"><span data-stu-id="224d0-1053">Access</span></span>

- <span data-ttu-id="224d0-1054">修正某些使用者在嘗試從其同步處理的 OneDrive 資料夾匯出査詢時看到「系統資源滿載」錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1054">We fixed an issue where some users were seeing the "system resource exceeded" error when they tried to export a query from their synced OneDrive folder.</span></span>


- <span data-ttu-id="224d0-1055">我們已修正表單視窗之間發生「自動」切換而切換到另一個表單的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1055">We fixed an issue where 'auto'-switching between form windows was switching to another form.</span></span>


- <span data-ttu-id="224d0-1056">我們已修正從非 Office 應用程式使用 DAO 時，會導致應用程式意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1056">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


### <a name="excel"></a><span data-ttu-id="224d0-1057">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-1057">Excel</span></span>

- <span data-ttu-id="224d0-1058">我們已修正啟用 SaveAs 作業與 COM 增益集之後，檔案名稱未變更的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1058">We fixed an issue where Filename was not changing after a SaveAs operation with COM add-ins enabled.</span></span>


- <span data-ttu-id="224d0-1059">修正 Power Pivot 使用 Oracle 資料庫連線時的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1059">Fixed an issue with Power Pivot when using a connection to an Oracle database.</span></span>


- <span data-ttu-id="224d0-1060">我們已修正當 Excel 資料模型中有錯誤的度量定義時，自動儲存會失敗且顯示錯誤/令人誤解的錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1060">We fixed an issue when Auto-Save fails with incorrect/misleading error message when there's a bad measure definition in the Excel data model.</span></span>


- <span data-ttu-id="224d0-1061">我們已修正觸發 MTR 計算和群組原則物件更新 (例如，透過遠端群組原則重新整理) 的處理序時，Excel 異常終止的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1061">We fixed an issue where Excel terminated unexpectedly when the process of MTR calc and Group Policy Object update (e.g. via Remote Group Policy Refresh) was triggered.</span></span>


- <span data-ttu-id="224d0-1062">我們已修正使用者無法直接從 SharePoint 開啟 atomsvc (UTF8+BOM) 檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1062">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="224d0-1063">我們已修正放大和縮小簡報區域會造成縮放選取選框和滑鼠指標之間的間隙的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1063">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


- <span data-ttu-id="224d0-1064">我們已修正將 Excel 活頁簿插入 Word 文件時，Word 似乎停止回應的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1064">We fixed an issue where Word appears to hang when inserting an Excel workbook into a Word document.</span></span>


### <a name="outlook"></a><span data-ttu-id="224d0-1065">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1065">Outlook</span></span>

- <span data-ttu-id="224d0-1066">解決在新增或儲存附件時，會導致 Outlook 偶爾停止運作的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1066">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


- <span data-ttu-id="224d0-p158">我們已修正影像附件的快速列印會導致「Windows 找不到這張圖片。請檢查位置，然後再試一次」錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-p158">We fixed an issue where quick print for image attachments resulted in error, "Windows can't find this picture. Check the location, and then try again".</span></span>


- <span data-ttu-id="224d0-1069">我們已修正會導致某些使用者看到 Outlook 在離線狀態下啟動，直到他們手動選擇線上工作的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1069">We fixed an issue that caused some users to see Outlook start in an Offline state until they manually chose to work online.</span></span>


- <span data-ttu-id="224d0-1070">我們已修正將從會議位置複製的 URL 貼上到其他位置 (例如瀏覽器) 時，URL 的結尾會包含分號的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1070">We fixed an issue when pasting a URL copied from meeting location to somewhere else (such as a browser), the URL contains a semicolon at the end.</span></span>


- <span data-ttu-id="224d0-1071">我們已修正使用者無法在 [基本驗證] 中刪除 Microsoft 365 群組行事曆約會的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1071">We fixed an issue where users were unable to delete appointments in Calendar of Microsoft 365 Groups in Basic Auth.</span></span>


- <span data-ttu-id="224d0-1072">我們已修正載入暱稱快取時啟動 Outlook 失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1072">We fixed an issue where starting Outlook failed while loading nickname cache.</span></span>


- <span data-ttu-id="224d0-1073">我們已修正信箱擁有者無法管理自己行事曆的共用權限的問題，因為該選項呈現灰色停用狀態。</span><span class="sxs-lookup"><span data-stu-id="224d0-1073">We fixed an issue where a mailbox owner wasn't able to manage Shared permission for their own Calendar as the option was greyed out.</span></span>


- <span data-ttu-id="224d0-1074">我們已修正 Outlook 無法使用受限制的權限建立郵件的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1074">We fixed an issue where Outlook was not able to create a message with restricted permission.</span></span>


- <span data-ttu-id="224d0-1075">我們已修正將電子郵件範本儲存為 .OFT 時，會將中文字元變更為問號的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1075">We fixed an issue where saving email templates as .OFT changed Chinese characters to question marks.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="224d0-1076">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-1076">PowerPoint</span></span>

- <span data-ttu-id="224d0-1077">我們已修正放大和縮小簡報會造成縮放選取跑馬燈和滑鼠指標之間間隙的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1077">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


- <span data-ttu-id="224d0-1078">我們已修正 [圖片] 旁的內容預留位置圖示沒有工具提示的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1078">We fixed an issue where in content placeholder icon next to Pictures didn't have a tooltip.</span></span>


- <span data-ttu-id="224d0-1079">我們已修正 pptsx 檔案所顯示的投影片放映之受保護檢視，允許受 IRM 保護的文件螢幕擷取的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1079">We have fixed an issue where Protected view of slide show, shown by pptsx file, allows screen capture of IRM protected document.</span></span>


- <span data-ttu-id="224d0-1080">我們已修正關閉設計窗格時，投影片的格線移位的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1080">We fixed an issue where grid lines were getting shifted from slides when closing design pane.</span></span>


- <span data-ttu-id="224d0-1081">我們已修正將投影片放映複製到次要監視器時，投影片可能會隱藏在其他視窗後面的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1081">We fixed an issue when duplicating slideshow to secondary monitor, the slideshow may hide behind other window.</span></span>


- <span data-ttu-id="224d0-1082">我們已修正投影片在選取項目窗格開啟的情況下停止螢幕錄製後，投影片中的捲軸會自行開始調整的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1082">We fixed an issue where the scroll bar in the slide starts adjusting itself after stopping screen recording with selection pane opened.</span></span>


### <a name="project"></a><span data-ttu-id="224d0-1083">Project</span><span class="sxs-lookup"><span data-stu-id="224d0-1083">Project</span></span>

- <span data-ttu-id="224d0-1084">修正如果 [工作表單] 類型檢視中的延遲變更，ProjectBeforeTaskChagne 事件中的 NewVal 值不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1084">Fixed an issue where the NewVal in the ProjectBeforeTaskChagne event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


- <span data-ttu-id="224d0-1085">我們已修正在開啟以特定方式指定資源分佈的檔案時，Project 可能會意外終止的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1085">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>


- <span data-ttu-id="224d0-1086">修正當您將專案從 PWA 儲存到本機 mpp 檔案時，會針對實際上使用者未變更的資料觸發 ProjectBeforeTaskChangeEvent 的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1086">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="224d0-1087">修正資源預訂依名稱 (而不是 GUID) 搜尋資源時，如果有多個名稱相同的資源，會導致問題的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1087">Fixed an issue where resource engagements searched for a resource by name instead of GUID which would cause issues if there were multiple resources with the same name.</span></span>


- <span data-ttu-id="224d0-1088">已修正如果您在專案網站中有工作清單並將工作清單分組，您將無法快速編輯工作清單的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1088">Fixed an issue where if you have a task list in a project site and group the task list, you will not be able to quick edit the task list.</span></span>


- <span data-ttu-id="224d0-1089">修正如果您透過 CSOM 更新企業資源，可能會遺失資源最大單位。</span><span class="sxs-lookup"><span data-stu-id="224d0-1089">Fixed an issue where if you update an enterprise resource via CSOM, resource max units may be lost.</span></span>


### <a name="word"></a><span data-ttu-id="224d0-1090">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-1090">Word</span></span>

- <span data-ttu-id="224d0-1091">我們已修正放大和縮小簡報區域會造成縮放選取選框和滑鼠指標之間的間隙的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1091">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


- <span data-ttu-id="224d0-1092">我們已修正按一下註解提示時，註解提示不會放大以在檢視中顯示註解卡片的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1092">We fixed an issue where clicking comment hint didn't zoom out to show comment card in view.</span></span>


- <span data-ttu-id="224d0-1093">我們已修正欄位之間的線條可能已移位的版面配置問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1093">We fixed a layout issue which the line between columns might have shifted.</span></span>


- <span data-ttu-id="224d0-1094">我們已修正有時開啟 Word 文件可能會顯示錯誤對話方塊的追蹤修訂問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1094">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>


- <span data-ttu-id="224d0-1095">我們已修正將 Excel 活頁簿插入 Word 文件時，Word 似乎停止回應的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1095">We fixed an issue where Word appears to hang when inserting an Excel workbook into a Word document.</span></span>


- <span data-ttu-id="224d0-1096">我們已修正套用具有浮水印的敏感度標籤時的列印問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1096">We fixed a print issue when sensitivity label with watermarks are applied.</span></span>


### <a name="office-suite"></a><span data-ttu-id="224d0-1097">Office 套件</span><span class="sxs-lookup"><span data-stu-id="224d0-1097">Office Suite</span></span>

- <span data-ttu-id="224d0-1098">我們已修正 Office 部署工具中的一個問題，該問題是，在 Microsoft Office 2007 [Microsoft 應用程式錯誤回報工具] 產品存在的情況下使用 RemoveMSI 功能時設定失敗。</span><span class="sxs-lookup"><span data-stu-id="224d0-1098">We fixed an issue in the Office Deployment Tool where configuration was failing when using the RemoveMSI feature with the Office 2007 "Microsoft Application Error Reporting" product present.</span></span>


- <span data-ttu-id="224d0-1099">我們已修正 SSO API 互動式登入傳回錯誤碼的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1099">We fixed an issue where SSO API interactive Sign-In was returning an error code.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2010-november-06"></a><span data-ttu-id="224d0-1101">版本 2010：11 月 6 日</span><span class="sxs-lookup"><span data-stu-id="224d0-1101">Version 2010: November 06</span></span>
<span data-ttu-id="224d0-1102">*版本 2010 (組建 13328.20356)*</span><span class="sxs-lookup"><span data-stu-id="224d0-1102">*Version 2010 (Build 13328.20356)*</span></span>
* <span data-ttu-id="224d0-1103">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="224d0-1103">Various bugs and performance fixes.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)



[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2010-november-04"></a><span data-ttu-id="224d0-1106">版本 2010：11 月 04 日</span><span class="sxs-lookup"><span data-stu-id="224d0-1106">Version 2010: November 04</span></span>
<span data-ttu-id="224d0-1107">*版本 2010 (組建 13328.20340)*</span><span class="sxs-lookup"><span data-stu-id="224d0-1107">*Version 2010 (Build 13328.20340)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-1109">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-1109">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-1110">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-1110">Excel</span></span>

- <span data-ttu-id="224d0-1111">**SVG 剪貼簿支援：** 您現在可以將 SVG 內容從 Office 貼上協力廠商應用程式。</span><span class="sxs-lookup"><span data-stu-id="224d0-1111">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="224d0-1112">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-1112">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="outlook"></a><span data-ttu-id="224d0-1113">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1113">Outlook</span></span>

- <span data-ttu-id="224d0-1114">**SVG 剪貼簿支援：** 您現在可以將 SVG 內容從 Office 貼上協力廠商應用程式。</span><span class="sxs-lookup"><span data-stu-id="224d0-1114">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="224d0-1115">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-1115">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="powerpoint"></a><span data-ttu-id="224d0-1116">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-1116">PowerPoint</span></span>

- <span data-ttu-id="224d0-1117">**SVG 剪貼簿支援：** 您現在可以將 SVG 內容從 Office 貼上協力廠商應用程式。</span><span class="sxs-lookup"><span data-stu-id="224d0-1117">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="224d0-1118">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-1118">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)<br /><span data-ttu-id="224d0-1119">在[部落格文章](https://insider.office.com/zh-TW/blog/svg-content-office-third-party-apps)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="224d0-1119">See details in [blog post](https://insider.office.com/zh-TW/blog/svg-content-office-third-party-apps)</span></span>

- <span data-ttu-id="224d0-1120">**使用透明背景建立 GIF：** 當匯出成動畫 GIF 時，您可以使用新選項讓背景變透明。</span><span class="sxs-lookup"><span data-stu-id="224d0-1120">**Create GIFs with Transparent Backgrounds:** When exporting to an Animated GIF, a new option will allow you to make the background transparent.</span></span><br /><span data-ttu-id="224d0-1121">在[部落格文章](https://insider.office.com/zh-TW/blog/export-animated-gifs-transparent-backgrounds)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="224d0-1121">See details in [blog post](https://insider.office.com/zh-TW/blog/export-animated-gifs-transparent-backgrounds)</span></span>

- <span data-ttu-id="224d0-1122">**匯出一定範圍內的動畫 GIF** 在匯出成動畫 GIF 時，選取投影片的範圍</span><span class="sxs-lookup"><span data-stu-id="224d0-1122">**Export animated GIF in a range:** Select a range of slides when exporting to animated GIF</span></span>

### <a name="word"></a><span data-ttu-id="224d0-1123">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-1123">Word</span></span>

- <span data-ttu-id="224d0-1124">**SVG 剪貼簿支援：** 您現在可以將 SVG 內容從 Office 貼上協力廠商應用程式。</span><span class="sxs-lookup"><span data-stu-id="224d0-1124">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="224d0-1125">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-1125">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-1128">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-1128">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-1129">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1129">Outlook</span></span>

- <span data-ttu-id="224d0-1130">我們已修正會導致使用者無法將 [編輯器] 權限授與代理人的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1130">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


### <a name="office-suite"></a><span data-ttu-id="224d0-1131">Office 套件</span><span class="sxs-lookup"><span data-stu-id="224d0-1131">Office Suite</span></span>

- <span data-ttu-id="224d0-1132">我們已修正在嘗試儲存已從 syncbacked 檔案轉換為僅限伺服器的檔案時，導致失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1132">We fixed an issue that was causing a failure when trying to save files that have transitioned from syncbacked to server-only.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2010-october-27"></a><span data-ttu-id="224d0-1134">版本 2010：10 月 27 日</span><span class="sxs-lookup"><span data-stu-id="224d0-1134">Version 2010: October 27</span></span>
<span data-ttu-id="224d0-1135">*版本 2010 (組建 13328.20292)*</span><span class="sxs-lookup"><span data-stu-id="224d0-1135">*Version 2010 (Build 13328.20292)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-1139">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-1139">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-1140">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1140">Outlook</span></span>

- <span data-ttu-id="224d0-1141">我們已修正會導致預設不會為使用者開啟雲端設定的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1141">We fixed a n issue that caused Cloud Settings not to be turned on for users by default.</span></span>


- <span data-ttu-id="224d0-1142">我們已修正會導致對使用者簽章的變更無法儲存的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1142">We fixed an issue that caused changes to a user's signature to fail to save.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2010-october-24"></a><span data-ttu-id="224d0-1144">版本 2010：10 月 24 日</span><span class="sxs-lookup"><span data-stu-id="224d0-1144">Version 2010: October 24</span></span>
<span data-ttu-id="224d0-1145">*版本 2010 (組建 13328.20278)*</span><span class="sxs-lookup"><span data-stu-id="224d0-1145">*Version 2010 (Build 13328.20278)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)



[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-1149">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-1149">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-1150">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1150">Outlook</span></span>

- <span data-ttu-id="224d0-1151">我們已修正在回覆或轉寄時，會導致中文郵件標題無法閱讀的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1151">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


- <span data-ttu-id="224d0-1152">我們已修正在儲存為 OFT 檔案時，會導致中文字元變更為問號的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1152">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


### <a name="project"></a><span data-ttu-id="224d0-1153">Project</span><span class="sxs-lookup"><span data-stu-id="224d0-1153">Project</span></span>

- <span data-ttu-id="224d0-1154">修正當您將專案從 PWA 儲存到本機 mpp 檔案時，ProjectBeforeTaskChangeEvent 會對實際上未由使用者變更的資料觸發的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1154">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="224d0-1155">修正如果工作表單類型檢視內的延隔時間變更，ProjectBeforeTaskChange 事件中的 NewVal 不會有正確值的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1155">Fixed an issue where the NewVal in the ProjectBeforeTaskChange event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2010-october-19"></a><span data-ttu-id="224d0-1157">版本 2010：10 月 19 日</span><span class="sxs-lookup"><span data-stu-id="224d0-1157">Version 2010: October 19</span></span>
<span data-ttu-id="224d0-1158">*版本 2010 (組建 13328.20210)*</span><span class="sxs-lookup"><span data-stu-id="224d0-1158">*Version 2010 (Build 13328.20210)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-1160">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-1160">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-1161">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1161">Outlook</span></span>

- <span data-ttu-id="224d0-1162">**撰寫郵件時節省時間：** Outlook 會顯示書寫建議，協助您快速撰寫郵件。</span><span class="sxs-lookup"><span data-stu-id="224d0-1162">**Save time while composing messages:** Outlook shows you writing suggestions that help you compose messages quickly.</span></span> <span data-ttu-id="224d0-1163">若要接受建議，只需使用 Tab 鍵。</span><span class="sxs-lookup"><span data-stu-id="224d0-1163">To accept the suggestion, just use the Tab key.</span></span><br /><span data-ttu-id="224d0-1164">在[部落格文章](https://insider.office.com/zh-TW/blog/text-predictions-in-word-outlook)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="224d0-1164">See details in [blog post](https://insider.office.com/zh-TW/blog/text-predictions-in-word-outlook)</span></span>

- <span data-ttu-id="224d0-1165">**使用內建翻譯工具打破語言障礙：** 不再需要翻譯的增益集！</span><span class="sxs-lookup"><span data-stu-id="224d0-1165">**Break the language barrier with a built-in translator:** Add-ins for translation aren't required anymore!</span></span> <span data-ttu-id="224d0-1166">在電子郵件中，按一下滑鼠右鍵以翻譯特定的文字、片語或整個郵件。</span><span class="sxs-lookup"><span data-stu-id="224d0-1166">In a message, right-click to translate specific words, phrases, or the whole message.</span></span> [<span data-ttu-id="224d0-1167">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-1167">Learn more</span></span>](https://support.office.com/article/287380e4-a56c-48a1-9977-f2dca89ce93f)

- <span data-ttu-id="224d0-1168">**工作的使用者體驗更新：** 工作項目的視覺效果更新</span><span class="sxs-lookup"><span data-stu-id="224d0-1168">**User Experience Updates for Tasks:** A visual refresh of task items</span></span>

### <a name="powerpoint"></a><span data-ttu-id="224d0-1169">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-1169">PowerPoint</span></span>

- <span data-ttu-id="224d0-1170">**使用簡報者教練排練您的簡報：** 獲得可協助吸引對象的項目，例如節奏、過度使用的文字、肢體語言等等的指導。</span><span class="sxs-lookup"><span data-stu-id="224d0-1170">**Practice your presentation with Presenter Coach:** Get coaching on the things that help keep an audience engaged — like pacing, overused words, body language, and more.</span></span> [<span data-ttu-id="224d0-1171">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-1171">Learn more</span></span>](https://support.office.com/article/cd7fc941-5c3b-498c-a225-83ef3f64f07b)

### <a name="word"></a><span data-ttu-id="224d0-1172">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-1172">Word</span></span>

- <span data-ttu-id="224d0-1173">**電腦版 Word 中的 Microsoft 編輯器窗格已更新：** 我們已將電腦版 Word 用戶端中編輯器窗格目前的體驗升級。</span><span class="sxs-lookup"><span data-stu-id="224d0-1173">**Microsoft Editor pane gets an update in Word for desktop:** We have upgraded the current experience with the Editor pane in Word for desktop clients.</span></span>

- <span data-ttu-id="224d0-1174">**單鍵書寫建議：** 只要按一下，就能套用書寫建議。</span><span class="sxs-lookup"><span data-stu-id="224d0-1174">**One-click writing suggestions:** Apply writing suggestions with a single click.</span></span> <span data-ttu-id="224d0-1175">更新的 [編輯器] 窗格讓您輕鬆在建議之間瀏覽。</span><span class="sxs-lookup"><span data-stu-id="224d0-1175">The updated Editor pane makes it easy to navigate between suggestions.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-1178">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-1178">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="224d0-1179">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-1179">PowerPoint</span></span>

- <span data-ttu-id="224d0-1180">這是此問題的修正：當有增益集在接聽 PresentationBeforeClose 事件並隨著事件處理常式檢查 Presentation.Saved 內容時若關閉文件，儲存提示會以迴圈顯示。</span><span class="sxs-lookup"><span data-stu-id="224d0-1180">This is a fix for an issue where the save prompt shows in a loop when closing the document when there is an add-in that listens to PresentationBeforeClose event and checks Presentation.Saved property as a part of the event handler.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2010-october-11"></a><span data-ttu-id="224d0-1182">版本 2010: 10 月 11 日</span><span class="sxs-lookup"><span data-stu-id="224d0-1182">Version 2010: October 11</span></span>
<span data-ttu-id="224d0-1183">*版本 2010 (組建 13328.20154)*</span><span class="sxs-lookup"><span data-stu-id="224d0-1183">*Version 2010 (Build 13328.20154)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-1185">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-1185">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-1186">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-1186">Excel</span></span>

- <span data-ttu-id="224d0-1187">**協助保護您的資料免受惡意檔案的侵害：**[應用程式防護] 可讓您在獨立的容器中讀取、列印和儲存 Office 檔案，協助保護您免受惡意程式碼的侵害。</span><span class="sxs-lookup"><span data-stu-id="224d0-1187">**Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container.</span></span> [<span data-ttu-id="224d0-1188">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-1188">Learn more</span></span>](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)

### <a name="powerpoint"></a><span data-ttu-id="224d0-1189">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-1189">PowerPoint</span></span>

- <span data-ttu-id="224d0-1190">**協助保護您的資料免受惡意檔案的侵害：**[應用程式防護] 可讓您在獨立的容器中讀取、列印和儲存 Office 檔案，協助保護您免受惡意程式碼的侵害。</span><span class="sxs-lookup"><span data-stu-id="224d0-1190">**Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container.</span></span> [<span data-ttu-id="224d0-1191">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-1191">Learn more</span></span>](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)

### <a name="word"></a><span data-ttu-id="224d0-1192">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-1192">Word</span></span>

- <span data-ttu-id="224d0-1193">**協助保護您的資料免受惡意檔案的侵害：**[應用程式防護] 可讓您在獨立的容器中讀取、列印和儲存 Office 檔案，協助保護您免受惡意程式碼的侵害。</span><span class="sxs-lookup"><span data-stu-id="224d0-1193">**Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container.</span></span> [<span data-ttu-id="224d0-1194">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-1194">Learn more</span></span>](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-1197">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-1197">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="224d0-1198">Access</span><span class="sxs-lookup"><span data-stu-id="224d0-1198">Access</span></span>

- <span data-ttu-id="224d0-1199">我們已修正載入儲存的查詢/關聯視窗在捲動時，捲軸位置未正確設定的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1199">We fixed an issue where scrollbar position was not set correctly when loading query/relationship window saved while scrolled.</span></span>


- <span data-ttu-id="224d0-1200">我們已修正 [新增表格] 工作窗格未正確顯示包含 '&' 名稱的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1200">We fixed an issue where Add Table Task Pane was not displaying names containing '&' correctly.</span></span>


### <a name="excel"></a><span data-ttu-id="224d0-1201">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-1201">Excel</span></span>

- <span data-ttu-id="224d0-1202">我們已修正多層次類別的手動間隔在圖表中無法運作的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1202">We fixed an issue where multi-level category manual interval was not working in charts.</span></span>


- <span data-ttu-id="224d0-1203">修正在使用 2D 地圖圖表時，無法使用 VBA 設定系列中最大值、中間值和最小值顏色的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1203">Fixed an issue with 2D Map Charts where using VBA to set the colors for the max, mid, and min values for a series was not working.</span></span>


- <span data-ttu-id="224d0-1204">修正可能會導致「嘗試計算一個或多個公式時，Excel 資源不足」的錯誤問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1204">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="224d0-1205">修正當 Office 語言設定為西班牙文時，其中資料驗證清單可能無法顯示清單中所有項目的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1205">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="224d0-1206">修正在啟用「分頁預覽」時，在含有大量資料的工作表之間切換時，可能會發生明顯延遲的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1206">Fixed an issue where there could be a noticeable delay when switching between worksheets with large amounts of data when 'Page Break Preview' was enabled.</span></span>


- <span data-ttu-id="224d0-1207">我們已修正當新增至用於資料驗證的表格時，並未更新活頁簿中所有工作表選項的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1207">We fixed an issue where adding to a table used for Data Validation did not update options for all sheets in the workbook.</span></span>


- <span data-ttu-id="224d0-1208">我們已修正在重新整理 OLAP 樞紐分析表時，可能會導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1208">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="224d0-1209">修正在使用資料編輯列輸入公式時，某些情況下 ChartSheet 出現當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1209">Fixed an issue where ChartSheet crashed in some cases when a formula is entered through formula bar.</span></span>


- <span data-ttu-id="224d0-1210">我們已修正 Excel 公式列與設備失去連線後無法完全呈現的問題，例如遠端會話的連線/斷線或監視器變更。</span><span class="sxs-lookup"><span data-stu-id="224d0-1210">We fixed an issue where the Excel formula bar would not render completely after connection to a device was lost, such as a remote session connect/disconnect or a monitor change.</span></span>


### <a name="onenote"></a><span data-ttu-id="224d0-1211">OneNote</span><span class="sxs-lookup"><span data-stu-id="224d0-1211">OneNote</span></span>

- <span data-ttu-id="224d0-1212">我們已修正使用者無法從 [外部空間檔案] > [資訊] 的文字方塊中選取及複製筆記本 URL 的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1212">We fixed an issue where a user was unable to select and copy notebook URL from textbox in OutSpace File > Info.</span></span>


- <span data-ttu-id="224d0-1213">我們已修正當您將游標移至筆記本色彩選擇器的綠色上方時，快顯會顯示「紅粉色」的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1213">We fixed an issue when you hover over green color in notebook color selector, the pop up reads "red chalk".</span></span>


- <span data-ttu-id="224d0-1214">我們已修正 OneNote 在自訂主題的畫布中不會採用高對比色彩的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1214">We fixed an issue where OneNote didn't honor High Contrast colors in the canvas for custom themes.</span></span>


### <a name="outlook"></a><span data-ttu-id="224d0-1215">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1215">Outlook</span></span>

- <span data-ttu-id="224d0-1216">已解決當主旨為空白時，會導致傳送的自動產生電子郵件含有空白內文的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1216">Addresses an issue that caused automatically generated emails to be sent with a blank body when the subject is blank.</span></span>


- <span data-ttu-id="224d0-1217">我們已修正資料夾中快取錯誤資料夾 guid 的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1217">We fixed an issue where the wrong folder guid is cached for folders.</span></span>


- <span data-ttu-id="224d0-1218">當使用者將電子郵件地址複製貼上到顯示名稱的 [收件者] 欄位時，電子郵件地址不一定可被正確分析，並導致出現了一個顯示電子郵件地址無效的警告。</span><span class="sxs-lookup"><span data-stu-id="224d0-1218">When a user copy-and-pastes an email address into the recipient field with the display name, the email address wasn't always parsed correctly and caused a warning about an invalid email address to appear.</span></span>  <span data-ttu-id="224d0-1219">已修正此問題，可正確分析名稱和電子郵件地址，因此不會再顯示警告。</span><span class="sxs-lookup"><span data-stu-id="224d0-1219">It's been fixed so the name and email address are parsed correctly so the warning is no longer shown.</span></span>


- <span data-ttu-id="224d0-1220">我們已修正線上共用資料夾未傳回母資料夾名稱的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1220">We fixed an issue where online shared folders did not return parent folder name.</span></span> <span data-ttu-id="224d0-1221">它並非失敗，而是傳回了不正確地移至主要帳戶的空白路徑。</span><span class="sxs-lookup"><span data-stu-id="224d0-1221">Intsead of failing, it returned an empty path which incorrectly went to the primary account.</span></span>


- <span data-ttu-id="224d0-1222">我們已修正傳統附件無法使用 [另存為] 選項的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1222">We fixed an issue where the Save As option was not available for classic attachments.</span></span>


- <span data-ttu-id="224d0-1223">我們已修正讓使用者能在覆寫原則時自訂調整文字的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1223">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


- <span data-ttu-id="224d0-1224">我們已修正從唯讀預覽窗格中重新開啟 [草稿] 之後會開啟 [追蹤修訂] 的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1224">We fixed an issue where track changes turned on after reopening draft from read-only preview pane.</span></span>


- <span data-ttu-id="224d0-1225">我們已修正關閉 [焦點收件匣] 並執行排序之後，電子郵件遭隱藏的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1225">We fixed an issue with emails being hidden after turning Focused Inbox off and doing a sort.</span></span>


- <span data-ttu-id="224d0-1226">我們已修正會導致 Outlook 為啟用雲端設定的使用者建立第二個空白簽名的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1226">We fixed an issue that caused Outlook to create a second empty signature for people who had cloud settings enabled.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="224d0-1227">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-1227">PowerPoint</span></span>

- <span data-ttu-id="224d0-1228">我們已修正 PowerPoint 在匯出為 PDF 時，無法匯出矩形專案符號的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1228">We fixed an issue where PowerPoint was not exporting rectangle bullet points while exporting to PDF.</span></span>


- <span data-ttu-id="224d0-1229">我們已修正 GIF 在編輯器和投影片放映中的動畫只會執行一次的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1229">We fixed an issue where GIF's would animate only once in the editor and slide shows.</span></span>


- <span data-ttu-id="224d0-1230">我們已修正當使用者將來源路徑變更為本機 OneDrive 資料夾時，連結的 Excel 圖表不正確變更為 Excel 工作表的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1230">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


- <span data-ttu-id="224d0-1231">我們已修正若您在最後一張投影片上，且您在按 [結束工作模式] 之後和顯示摘要之前，滑向下一張投影片，則會在 [摘要] 頁面上看到 [結束工作模式] 對話方塊。</span><span class="sxs-lookup"><span data-stu-id="224d0-1231">We fixed an issue that If you are on the last slide and if you swipe to the next slide after pressing 'End Session' and before the summary shows up, the End-Session dialog is visible on the summary page as well.</span></span>


### <a name="project"></a><span data-ttu-id="224d0-1232">Project</span><span class="sxs-lookup"><span data-stu-id="224d0-1232">Project</span></span>

- <span data-ttu-id="224d0-1233">修正了如果您嘗試多次新增同一專案，且將 AttachToSources 設定為 false 時，ConsolidateProjects VBA 方法可能會發生出錯的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1233">Fixed an issue where the ConsolidateProjects VBA method may file if you try to add the same project multiple times and have AttachToSources set to false.</span></span>


- <span data-ttu-id="224d0-1234">修正若您的事件程式碼執行中，並嘗試透過工作 [表單檢視] 進行變更，按一下 [確定] 按鈕可能不會提交變更的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1234">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


- <span data-ttu-id="224d0-1235">修正了如果您嘗試多次新增同一專案，且將 AttachToSources 設定為 false 時，ConsolidateProjects VBA 方法可能會發生出錯的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1235">Fixed an issue where the ConsolidateProjects VBA method may file if you try to add the same project multiple times and have AttachToSources set to false.</span></span>


- <span data-ttu-id="224d0-1236">修正了如果您的自訂欄位包含公式，且正在使用實獲值分析，您可能會發現效能延遲切換檢視並開啟專案/工作詳細資料的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1236">Fixed an issue where if you have custom fields with formulas and are using earned value, you may notice performance delays switching views and opening project/task details.</span></span>


- <span data-ttu-id="224d0-1237">修正了如果您將群組套用到 [資源使用狀況] 或 [工作表] 視圖，然後插入欄位，Project 可能會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1237">Fixed an issue where Project may crash if you apply a group by to the Resource Usage or Sheet view and then insert a column.</span></span>


### <a name="word"></a><span data-ttu-id="224d0-1238">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-1238">Word</span></span>

- <span data-ttu-id="224d0-1239">我們己修正已啟用工作流程檔案的連結無法如預期開啟的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1239">We fixed an issue where links to workflow enabled files were not opening as expected.</span></span>


- <span data-ttu-id="224d0-1240">修正當使用者在點擊追蹤的變更（插入/刪除）時，會彈出註解的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1240">Fixed an issue where a user tapping on a tracked change (insertion/deletion) would bring up a comment pop-out.</span></span>


- <span data-ttu-id="224d0-1241">我們已修正 Word 中刪除註解圖說文字的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1241">We fixed an issue with deleting comment callouts in Word.</span></span>


- <span data-ttu-id="224d0-1242">我們已修正 Outlook 有關將郵件設定為 [不要轉寄] 的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1242">We fixed an issue with Outlook with message set to Do not forward.</span></span>


- <span data-ttu-id="224d0-1243">我們已修正有關儲存含有引文和方程式的 Word 文件問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1243">We fixed an issue with saving Word document that contains citation and equation.</span></span>


- <span data-ttu-id="224d0-1244">我們已修正 [樣式圖庫] 對話方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1244">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="224d0-1245">Office 套件</span><span class="sxs-lookup"><span data-stu-id="224d0-1245">Office Suite</span></span>

- <span data-ttu-id="224d0-p172">當使用者從 Office 在噴墨印表機上列印任何文件/檔案且印表機墨水不足時，即使噴墨印表機並沒有碳粉，也會顯示「碳粉不足」或「無碳粉」訊息。變更訊息以顯示「碳粉/墨水不足」與「碳粉/墨水用完」。</span><span class="sxs-lookup"><span data-stu-id="224d0-p172">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners. Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2009-october-07"></a><span data-ttu-id="224d0-1249">版本 2009：10 月 7 日</span><span class="sxs-lookup"><span data-stu-id="224d0-1249">Version 2009: October 07</span></span>
<span data-ttu-id="224d0-1250">*版本 2009 (組建 13231.20360)*</span><span class="sxs-lookup"><span data-stu-id="224d0-1250">*Version 2009 (Build 13231.20360)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-1252">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-1252">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-1253">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-1253">Excel</span></span>

- <span data-ttu-id="224d0-1254">**使用 Power Query 建立資料類型：** 使用任何資料來源中的 Power Query 建立豐富的資料類型</span><span class="sxs-lookup"><span data-stu-id="224d0-1254">**Create Data Types with Power Query:** Create rich data types with Power Query from any data source</span></span>

### <a name="outlook"></a><span data-ttu-id="224d0-1255">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1255">Outlook</span></span>

- <span data-ttu-id="224d0-1256">**語文法檢查鼎力相助**：Outlook 會在你鍵入時標記文法錯誤，因此你只需按一下就可以套用建議。</span><span class="sxs-lookup"><span data-stu-id="224d0-1256">**Grammar checking's got your back:** Outlook marks grammar errors as you type, so you can apply suggestions with a single click.</span></span> <br /><span data-ttu-id="224d0-1257">在[部落格文章](https://insider.office.com/zh-TW/blog/grammar-and-style-suggestions-available-in-outlook)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="224d0-1257">See details in [blog post](https://insider.office.com/zh-TW/blog/grammar-and-style-suggestions-available-in-outlook)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-1260">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-1260">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-1261">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1261">Outlook</span></span>

- <span data-ttu-id="224d0-1262">解決了搜尋未緩存共用行事曆時導致搜尋不傳回結果的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1262">Addresses an issue that caused Search to return no results when searching uncached shared calendars.</span></span>


- <span data-ttu-id="224d0-1263">解決了導致某些使用者觀察到在離線狀態下意外啟動 Outlook 的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1263">Addresses an issue that caused some users to observe Outlook unexpectedly starting in an offline state.</span></span>


- <span data-ttu-id="224d0-1264">解決了導致代理人在開啟另一個信箱中的共用資料夾時出現錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1264">Addresses an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="224d0-1265">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-1265">PowerPoint</span></span>

- <span data-ttu-id="224d0-1266">解決在受保護的檢視中開啟 PowerPoint 檔案時停用 IRM 保護的問題的安全性問題修正。</span><span class="sxs-lookup"><span data-stu-id="224d0-1266">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


### <a name="office-suite"></a><span data-ttu-id="224d0-1267">Office 套件</span><span class="sxs-lookup"><span data-stu-id="224d0-1267">Office Suite</span></span>

- <span data-ttu-id="224d0-p173">當使用者從 Office 在噴墨印表機上列印任何文件/檔案且印表機墨水不足時，即使噴墨印表機並沒有碳粉，也會顯示「碳粉不足」或「無碳粉」訊息。變更訊息以顯示「碳粉/墨水不足」與「碳粉/墨水用完」。</span><span class="sxs-lookup"><span data-stu-id="224d0-p173">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners. Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2009-september-26"></a><span data-ttu-id="224d0-1271">版本 2009：9 月 26 日</span><span class="sxs-lookup"><span data-stu-id="224d0-1271">Version 2009: September 26</span></span>
<span data-ttu-id="224d0-1272">*版本 2009 (組建 13231.20262)*</span><span class="sxs-lookup"><span data-stu-id="224d0-1272">*Version 2009 (Build 13231.20262)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-1274">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-1274">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-1275">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1275">Outlook</span></span>

- <span data-ttu-id="224d0-1276">已解決當主旨行空白時，會導致傳送的自動產生電子郵件含有空白內文的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1276">Addresses an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


### <a name="project"></a><span data-ttu-id="224d0-1277">Project</span><span class="sxs-lookup"><span data-stu-id="224d0-1277">Project</span></span>

- <span data-ttu-id="224d0-1278">修正若您的事件程式碼執行中，並嘗試透過工作 [表單檢視] 進行變更，按一下 [確定] 按鈕可能不會提交變更的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1278">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2009-september-21"></a><span data-ttu-id="224d0-1280">版本 2009：9 月 21 日</span><span class="sxs-lookup"><span data-stu-id="224d0-1280">Version 2009: September 21</span></span>
<span data-ttu-id="224d0-1281">*版本 2009 (組建 13231.20200)*</span><span class="sxs-lookup"><span data-stu-id="224d0-1281">*Version 2009 (Build 13231.20200)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-1283">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-1283">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="224d0-1284">Access</span><span class="sxs-lookup"><span data-stu-id="224d0-1284">Access</span></span>

- <span data-ttu-id="224d0-1285">**自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。</span><span class="sxs-lookup"><span data-stu-id="224d0-1285">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="224d0-1286">移至 [檔案] > [選項]，然後選取 [Office 佈景主題] 旁邊的 [使用系統設定]。</span><span class="sxs-lookup"><span data-stu-id="224d0-1286">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="224d0-1287">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-1287">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="excel"></a><span data-ttu-id="224d0-1288">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-1288">Excel</span></span>

- <span data-ttu-id="224d0-1289">**將您的 iPhone 相片直接插入 Office：** 來自您手機的 HEIC 圖片現在可無縫地插入 Office。</span><span class="sxs-lookup"><span data-stu-id="224d0-1289">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="224d0-1290">不需要轉換。</span><span class="sxs-lookup"><span data-stu-id="224d0-1290">No conversion required.</span></span><br /><span data-ttu-id="224d0-1291">在[部落格文章](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="224d0-1291">See details in [blog post](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="224d0-1292">**自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。</span><span class="sxs-lookup"><span data-stu-id="224d0-1292">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="224d0-1293">移至 [檔案] > [選項]，然後選取 [Office 佈景主題] 旁邊的 [使用系統設定]。</span><span class="sxs-lookup"><span data-stu-id="224d0-1293">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="224d0-1294">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-1294">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="onenote"></a><span data-ttu-id="224d0-1295">OneNote</span><span class="sxs-lookup"><span data-stu-id="224d0-1295">OneNote</span></span>

- <span data-ttu-id="224d0-1296">**自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。</span><span class="sxs-lookup"><span data-stu-id="224d0-1296">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="224d0-1297">移至 [檔案] > [選項]，然後選取 [Office 佈景主題] 旁邊的 [使用系統設定]。</span><span class="sxs-lookup"><span data-stu-id="224d0-1297">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="224d0-1298">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-1298">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="outlook"></a><span data-ttu-id="224d0-1299">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1299">Outlook</span></span>

- <span data-ttu-id="224d0-1300">**依訊息擁有者刪除交談：** 此功能可讓您依訊息擁有者刪除交談。</span><span class="sxs-lookup"><span data-stu-id="224d0-1300">**Delete conversation by message owner:** This feature allows you to delete a conversation by message owner.</span></span>

- <span data-ttu-id="224d0-1301">**將您的 iPhone 相片直接插入 Office：** 來自您手機的 HEIC 圖片現在可無縫地插入 Office。</span><span class="sxs-lookup"><span data-stu-id="224d0-1301">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="224d0-1302">不需要轉換。</span><span class="sxs-lookup"><span data-stu-id="224d0-1302">No conversion required.</span></span><br /><span data-ttu-id="224d0-1303">在[部落格文章](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="224d0-1303">See details in [blog post](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="224d0-1304">**自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。</span><span class="sxs-lookup"><span data-stu-id="224d0-1304">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="224d0-1305">移至 [檔案] > [選項]，然後選取 [Office 佈景主題] 旁邊的 [使用系統設定]。</span><span class="sxs-lookup"><span data-stu-id="224d0-1305">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="224d0-1306">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-1306">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="powerpoint"></a><span data-ttu-id="224d0-1307">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-1307">PowerPoint</span></span>

- <span data-ttu-id="224d0-1308">**將您的 iPhone 相片直接插入 Office：** 來自您手機的 HEIC 圖片現在可無縫地插入 Office。</span><span class="sxs-lookup"><span data-stu-id="224d0-1308">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="224d0-1309">不需要轉換。</span><span class="sxs-lookup"><span data-stu-id="224d0-1309">No conversion required.</span></span><br /><span data-ttu-id="224d0-1310">在[部落格文章](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="224d0-1310">See details in [blog post](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="224d0-1311">**自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。</span><span class="sxs-lookup"><span data-stu-id="224d0-1311">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="224d0-1312">移至 [檔案] > [選項]，然後選取 [Office 佈景主題] 旁邊的 [使用系統設定]。</span><span class="sxs-lookup"><span data-stu-id="224d0-1312">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="224d0-1313">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-1313">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="project"></a><span data-ttu-id="224d0-1314">Project</span><span class="sxs-lookup"><span data-stu-id="224d0-1314">Project</span></span>

- <span data-ttu-id="224d0-1315">**自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。</span><span class="sxs-lookup"><span data-stu-id="224d0-1315">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="224d0-1316">移至 [檔案] > [選項]，然後選取 [Office 佈景主題] 旁邊的 [使用系統設定]。</span><span class="sxs-lookup"><span data-stu-id="224d0-1316">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="224d0-1317">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-1317">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="publisher"></a><span data-ttu-id="224d0-1318">Publisher</span><span class="sxs-lookup"><span data-stu-id="224d0-1318">Publisher</span></span>

- <span data-ttu-id="224d0-1319">**自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。</span><span class="sxs-lookup"><span data-stu-id="224d0-1319">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="224d0-1320">移至 [檔案] > [選項]，然後選取 [Office 佈景主題] 旁邊的 [使用系統設定]。</span><span class="sxs-lookup"><span data-stu-id="224d0-1320">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="224d0-1321">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-1321">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="visio"></a><span data-ttu-id="224d0-1322">Visio</span><span class="sxs-lookup"><span data-stu-id="224d0-1322">Visio</span></span>

- <span data-ttu-id="224d0-1323">**自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。</span><span class="sxs-lookup"><span data-stu-id="224d0-1323">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="224d0-1324">移至 [檔案] > [選項]，然後選取 [Office 佈景主題] 旁邊的 [使用系統設定]。</span><span class="sxs-lookup"><span data-stu-id="224d0-1324">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="224d0-1325">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-1325">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="word"></a><span data-ttu-id="224d0-1326">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-1326">Word</span></span>

- <span data-ttu-id="224d0-1327">**將您的 iPhone 相片直接插入 Office：** 來自您手機的 HEIC 圖片現在可無縫地插入 Office。</span><span class="sxs-lookup"><span data-stu-id="224d0-1327">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="224d0-1328">不需要轉換。</span><span class="sxs-lookup"><span data-stu-id="224d0-1328">No conversion required.</span></span><br /><span data-ttu-id="224d0-1329">在[部落格文章](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="224d0-1329">See details in [blog post](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="224d0-1330">**自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。</span><span class="sxs-lookup"><span data-stu-id="224d0-1330">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="224d0-1331">移至 [檔案] > [選項]，然後選取 [Office 佈景主題] 旁邊的 [使用系統設定]。</span><span class="sxs-lookup"><span data-stu-id="224d0-1331">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="224d0-1332">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-1332">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-1335">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-1335">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="224d0-1336">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-1336">PowerPoint</span></span>

- <span data-ttu-id="224d0-1337">修正了在包含大量特定資料物件類型 (E2o) 的檔案上導致共同撰寫變慢的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1337">Fixed an issue causing slow coauthoring on files containing large numbers of a certain data object type (E2o).</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2009-september-14"></a><span data-ttu-id="224d0-1339">版本 2009：9 月 14 日</span><span class="sxs-lookup"><span data-stu-id="224d0-1339">Version 2009: September 14</span></span>
<span data-ttu-id="224d0-1340">*版本 2009 (組建 13231.20152)*</span><span class="sxs-lookup"><span data-stu-id="224d0-1340">*Version 2009 (Build 13231.20152)*</span></span>
* <span data-ttu-id="224d0-1341">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="224d0-1341">Various bugs and performance fixes.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2009-september-10"></a><span data-ttu-id="224d0-1344">版本 2009：9 月 10 日</span><span class="sxs-lookup"><span data-stu-id="224d0-1344">Version 2009: September 10</span></span>
<span data-ttu-id="224d0-1345">*版本 2009 (組建 13231.20126)*</span><span class="sxs-lookup"><span data-stu-id="224d0-1345">*Version 2009 (Build 13231.20126)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-1347">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-1347">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="224d0-1348">Access</span><span class="sxs-lookup"><span data-stu-id="224d0-1348">Access</span></span>

- <span data-ttu-id="224d0-1349">此問題現在已解決，您不應該會再遇到當機。</span><span class="sxs-lookup"><span data-stu-id="224d0-1349">This issue has now been resolved and you should no longer experience a crash.</span></span>


- <span data-ttu-id="224d0-1350">我們已修正 ODBC 資料庫的連線對協力廠商應用程式沒有作用的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1350">We fixed an issue where connections to an ODBC database were not working with third party applications.</span></span>


### <a name="excel"></a><span data-ttu-id="224d0-1351">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-1351">Excel</span></span>

- <span data-ttu-id="224d0-1352">我們已修正一個問題, 即如果您開啟包含LET 函數的檔案，它會顯示警示：”我們在您的檔案.xlsx 中發現內容有問題”。</span><span class="sxs-lookup"><span data-stu-id="224d0-1352">We fixed an issue where if you opened a file containing the LET function, it would display the alert:  "We found a problem with content in "your file.xlsx".</span></span> <span data-ttu-id="224d0-1353">您想要我們儘量嘗試復原嗎？</span><span class="sxs-lookup"><span data-stu-id="224d0-1353">Do you want us to try to recover as much as we can?</span></span> <span data-ttu-id="224d0-1354">如果您信任這個活頁簿的來源，請按一下 [是]。</span><span class="sxs-lookup"><span data-stu-id="224d0-1354">If you trust the source of this workbook, click Yes".</span></span>


- <span data-ttu-id="224d0-1355">我們已修正如果用戶鍵入包含括號的公式名稱並通過F1調用了協助，則該特定於公式的說明主題將不會顯示。</span><span class="sxs-lookup"><span data-stu-id="224d0-1355">We fixed an issue where if a user typed a formula name including the parenthesis and invoked help via F1, the help topic specific to that formula would not be displayed.</span></span>


- <span data-ttu-id="224d0-1356">我們已修正使用巨集來設定某個範圍的 FormulaR1C1 屬性時，如果圖表工作表為作用中工作表，則儲存格參考會不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1356">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>


- <span data-ttu-id="224d0-1357">我們已修正使用者無法修改樞紐分析表篩選的問題，因為它已設定為Analysis Services數據庫中不再存在的值。</span><span class="sxs-lookup"><span data-stu-id="224d0-1357">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


- <span data-ttu-id="224d0-1358">修正與 XLAM 增益集參照和具名範圍相關的損毀。</span><span class="sxs-lookup"><span data-stu-id="224d0-1358">Fixed a crash related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="224d0-p188">我們已修正如果使用者將自訂樣式套用至動態陣列，就會收到「您不能只改變一個陣列中的一部分」錯誤的問題。這是已移除的舊版限制。</span><span class="sxs-lookup"><span data-stu-id="224d0-p188">We fixed an issue where if a user applied a custom style to a dynamic array, they would get the error: "You can't change part of an array". This was a legacy restriction that has been removed.</span></span>


- <span data-ttu-id="224d0-1361">修正在還原檔案的舊版本後，指派給按鈕的巨集會中斷的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1361">Fixed an issue where macros assigned to buttons were broken after restoring an older version of the file.</span></span>


- <span data-ttu-id="224d0-1362">我們已修正筆跡會導致 Excel 無法回應的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1362">We fixed an issue where inking could cause Excel to become unresponsive.</span></span>


### <a name="outlook"></a><span data-ttu-id="224d0-1363">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1363">Outlook</span></span>

- <span data-ttu-id="224d0-1364">我們已修正一個問題, 讓您可透過群組政策來啟用/停用預設的登入選項。</span><span class="sxs-lookup"><span data-stu-id="224d0-1364">We fixed an issue which provides more flexibility in enabling / disabling the default logging options via Group Policy.</span></span>


- <span data-ttu-id="224d0-1365">我們已修正電子郵件草稿在助理和經理權限移動時, 寄件者的舊網域名稱仍被保留和顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1365">We fixed an issue where the Legacy Domain Name for an email sender was preserved and displayed after a draft of the email was moved between mailboxes with assistant permissions and manager permissions.</span></span>


- <span data-ttu-id="224d0-1366">修正會導致某些使用者看到 Outlook 在離線狀態中啟動，直到他們手動選擇線上工作為止的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1366">Fixes an issue that caused some users to see Outlook to start in an Offline state until they manually chose to work online.</span></span>


- <span data-ttu-id="224d0-1367">我們已修正在啟用單行功能區（SLR）後，執行 VBA 程式碼 ActiveInspector （"ShowSchedulingPage"）會導致執行階段錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1367">We fixed an issue where running the VBA code ActiveInspector.CommandBars.ExecuteMso("ShowSchedulingPage") after enabling the Single Line Ribbon (SLR) would result in a runtime error.</span></span>


- <span data-ttu-id="224d0-1368">我們已修正一個問題, 即Automatic Replies自動回復對話方塊上的確定和取消按鈕以高解析度 (例如 1750 x 1920) 及較大文字 (例如 175%) 顯示的系統上的錯誤。</span><span class="sxs-lookup"><span data-stu-id="224d0-1368">We fixed an issue where the 'OK' and 'Cancel' buttons on the Automatic Replies dialog would not be visible on a system with a high resolution (such as 1750 x 1920) combined with a large text size (such as 175%).</span></span>


- <span data-ttu-id="224d0-1369">我們修正一個情況, 即將會議請求從空的聯繫人群組發送到另一個聯繫人組會導致當機。</span><span class="sxs-lookup"><span data-stu-id="224d0-1369">We fixed a condition where sending a meeting request from an empty contact group to another contact group would result in a crash.</span></span>


- <span data-ttu-id="224d0-1370">解決會導致使用者在開啟某些很大型電子郵件時會發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1370">Fixes an issue that caused users to experience a crash when opening certain very large emails.</span></span>


- <span data-ttu-id="224d0-1371">我們已修正一個問題, 它使的群組政策要求始終啟用增益集, 則 監視增益集的功能則無法使用，以防止使用者禁用增益集,。</span><span class="sxs-lookup"><span data-stu-id="224d0-1371">We fixed an issue where if Group Policy requires an Add-in to be always enabled, then monitoring add-in's becomes unavailable in order to prevent users from disabling the Add-in.</span></span>


- <span data-ttu-id="224d0-1372">解決一個問題，該問題導致使用者在選擇多個訊息時，能夠傳送 OneNote 所套用的「不可轉寄」原則的電子郵件內容。</span><span class="sxs-lookup"><span data-stu-id="224d0-1372">Addresses an issue that caused users to be able to send email content that had a "Do Not Forward" policy applied to OneNote when selecting more than one message.</span></span>


- <span data-ttu-id="224d0-1373">我們已修正一個問題，使用者現在可以停用 Outlook 的 IRM (資訊版權管理)，而不需要為其餘 Office 應用程式停用它。</span><span class="sxs-lookup"><span data-stu-id="224d0-1373">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>


- <span data-ttu-id="224d0-1374">我們已修正 Active Directory 中的 "otherTelephone" 和 "otherHomePhone" 使用者帳戶屬性未對應到對應的 Outlook LDAP 屬性的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1374">We fixed an issue where the user account attributes in Active Directory for "otherTelephone" and "otherHomePhone" were not mapped to the corresponding Outlook LDAP attributes.</span></span>


- <span data-ttu-id="224d0-1375">此變更解決了在用戶將索引標籤從會議頁面切換到排程小幫手頁面後，會議頁面將繼續顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1375">This change fixes an issue where the Meeting page would continue to be displayed after the user switched tabs from the Meeting page to the Scheduling Assistant page.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="224d0-1376">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-1376">PowerPoint</span></span>

- <span data-ttu-id="224d0-1377">我們已修正使用者在特定情況下看到功能區/標題列未顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1377">We fixed an issue where users were seeing the ribbon/title bar not being displayed under certain conditions.</span></span>


- <span data-ttu-id="224d0-1378">我們已修正啟動 PowerPoint 之後，插入投影片並開啟和關閉批註窗格的問題，縮圖窗格中的投影片會顯示為重疊。</span><span class="sxs-lookup"><span data-stu-id="224d0-1378">We fixed an issue where after booting PowerPoint, inserting a slide and opening and closing the comments pane, the slides in the thumbnail pane displayed as being overlapped.</span></span>


- <span data-ttu-id="224d0-1379">我們已修正插入影片的功能已停用的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1379">We fixed an issue where the functionality to insert a video was disabled.</span></span>


- <span data-ttu-id="224d0-1380">我們已修正影片在投影片放映中無法自動播放的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1380">We fixed an issue where videos were not playing automatically in slideshows.</span></span>


### <a name="project"></a><span data-ttu-id="224d0-1381">Project</span><span class="sxs-lookup"><span data-stu-id="224d0-1381">Project</span></span>

- <span data-ttu-id="224d0-1382">我們已修正如果資源有多個成本費率表的問題，則剩餘成本可能無法被正確計算.</span><span class="sxs-lookup"><span data-stu-id="224d0-1382">We fixed an issue where if a resource has multiple cost rate tables, the remaining cost may not be calculated correctly.</span></span>


- <span data-ttu-id="224d0-1383">我們已修正連結至 SharePoint 工作清單的專案的專案完成日期不會更新的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1383">We fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>


### <a name="visio"></a><span data-ttu-id="224d0-1384">Visio</span><span class="sxs-lookup"><span data-stu-id="224d0-1384">Visio</span></span>

- <span data-ttu-id="224d0-1385">客戶回報文字對齊會在即時預覽時發生當機。</span><span class="sxs-lookup"><span data-stu-id="224d0-1385">Live preview crashes on text alignment reported by customers.</span></span> <span data-ttu-id="224d0-1386">7 月分支所發生最多的當機情況。</span><span class="sxs-lookup"><span data-stu-id="224d0-1386">Top hitting crash of July fork.</span></span>


### <a name="word"></a><span data-ttu-id="224d0-1387">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-1387">Word</span></span>

- <span data-ttu-id="224d0-1388">我們已修正一個問題, 即使用者點擊註解，註解卡將在註解文周圍顯示邊框。</span><span class="sxs-lookup"><span data-stu-id="224d0-1388">We fixed an issue where the Comment card would display a border around the comment text if the user clicked on the comment.</span></span>


- <span data-ttu-id="224d0-1389">我們已修正項目符號圖片無法正確顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1389">We fixed an issue where the bullet picture icon didn't display correctly.</span></span>


- <span data-ttu-id="224d0-1390">我們已修正使用者在選取註解時無法退出頁首/頁尾的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1390">We fixed an issue where the user could not exit the Header/Footer when selecting a comment.</span></span>


- <span data-ttu-id="224d0-1391">我們已修正刪除註解之後 Word 可能會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1391">We fixed an issue where Word could crash after comments were deleted.</span></span>


- <span data-ttu-id="224d0-1392">我們已修正一個問題，即如果使用者建立的評論草稿, 錨定在已包含提交的評論行上，則在SideTrack與提交評論相關的草案則以錯誤的順序排列。</span><span class="sxs-lookup"><span data-stu-id="224d0-1392">We fixed an issue where if a user created a comment draft anchored to a line already containing committed comments, then the draft was arranged in the wrong order relative to the committed comment in the SideTrack.</span></span>


- <span data-ttu-id="224d0-1393">我們已修正一個問題, 即如將文件縮放到160％或更高, 且註解窗格不可見，焦點將不會移至註解窗格。</span><span class="sxs-lookup"><span data-stu-id="224d0-1393">We fixed an issue where the focus would not go to the comment pane if the document was zoomed to 160% or more and the comment pane was not visible.</span></span>


- <span data-ttu-id="224d0-1394">我們已修正一個問題，該問題造成使用者無法看到超出邊界的註解，因為在邊界中無法下拉。</span><span class="sxs-lookup"><span data-stu-id="224d0-1394">We fixed an issue that prevented users from seeing comment threads that exceeded the sidetrack boundary because scrolling through the sidetrack was not working.</span></span>


- <span data-ttu-id="224d0-1395">我們已修正在邊界窗格中，搜尋已解決的註解無法正常運作的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1395">We fixed an issue where searching for resolved comments in the sidetrack pane was not working.</span></span>


- <span data-ttu-id="224d0-1396">我們已修正一個問題，即在多個打開的文件之間切換後，一個文件的註解會顯示在其他打開的文檔上。</span><span class="sxs-lookup"><span data-stu-id="224d0-1396">We fixed an issue where the comments on one document would be displayed on other open documents after switching between the multiple open documents.</span></span>


- <span data-ttu-id="224d0-1397">我們已修正將文件儲存成 HTML 格式時，長連結無法換行的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1397">We fixed an issue where long links were not being wrapped when saving document to HTML format.</span></span>


- <span data-ttu-id="224d0-1398">我們已修正在某些情況下，項目符號無法在電子郵件中正確顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1398">We fixed an issue where in some cases, bullets are not displaying correctly in email.</span></span>


- <span data-ttu-id="224d0-1399">我們已修正 AutoOpen 會在 AutoExec 之前執行的巨集問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1399">We fixed an issue with macros in which AutoOpen runs before AutoExec.</span></span>


### <a name="office-suite"></a><span data-ttu-id="224d0-1400">Office 套件</span><span class="sxs-lookup"><span data-stu-id="224d0-1400">Office Suite</span></span>

- <span data-ttu-id="224d0-1401">我們已修正 Office 部署工具中的一個問題，該問題是，在 Microsoft Office 2007 [Microsoft 應用程式錯誤回報工具] 產品存在的情況下使用 RemoveMSI 功能時設定失敗。</span><span class="sxs-lookup"><span data-stu-id="224d0-1401">We fixed an issue in the Office Deployment Tool where configuration was failing when using the RemoveMSI feature with the Office 2007 "Microsoft Application Error Reporting" product present.</span></span>


- <span data-ttu-id="224d0-1402">我們在 [壓縮圖片] 對話方塊中，修正了某些使用者選取的 DPI 設定無法保留的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1402">We fixed an issue in the Compress Picture dialog where some user-selected DPI settings are not retained.</span></span>


- <span data-ttu-id="224d0-1403">此變更解決 [壓縮圖片] 對話方塊無法保留特定使用者設定的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1403">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-september-04"></a><span data-ttu-id="224d0-1405">版本2008：9月 4日</span><span class="sxs-lookup"><span data-stu-id="224d0-1405">Version 2008: September 04</span></span>
<span data-ttu-id="224d0-1406">*版本 2008 (組建 13127.20378)*</span><span class="sxs-lookup"><span data-stu-id="224d0-1406">*Version 2008 (Build 13127.20378)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-1408">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-1408">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="224d0-1409">Office 套件</span><span class="sxs-lookup"><span data-stu-id="224d0-1409">Office Suite</span></span>

- <span data-ttu-id="224d0-1410">此變更解決 [壓縮圖片] 對話方塊無法保留特定使用者設定的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1410">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-september-02"></a><span data-ttu-id="224d0-1412">版本 2008：9 月 2 日</span><span class="sxs-lookup"><span data-stu-id="224d0-1412">Version 2008: September 02</span></span>
<span data-ttu-id="224d0-1413">*版本 2008 (組建 13127.20360)*</span><span class="sxs-lookup"><span data-stu-id="224d0-1413">*Version 2008 (Build 13127.20360)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-1415">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-1415">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-1416">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-1416">Excel</span></span>

- <span data-ttu-id="224d0-1417">**將圖形另存為圖片：** 只要按幾下，即可將圖形、圖示或其他物件另存成圖片，便於您於任何其他地方使用。</span><span class="sxs-lookup"><span data-stu-id="224d0-1417">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="224d0-1418">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-1418">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="224d0-1419">**使用 Excel 手寫筆進行快速編輯：**[手寫筆工具] 可協助您手寫並快速編輯資料</span><span class="sxs-lookup"><span data-stu-id="224d0-1419">**Make quick edits using the Excel pen:** Pen Tool to help you handwrite and make quick edits to your data</span></span>



[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-1422">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-1422">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-1423">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-1423">Excel</span></span>

- <span data-ttu-id="224d0-1424">修正使用 [複製格式] 時，某些情況下，Excel 可能會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1424">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>


### <a name="word"></a><span data-ttu-id="224d0-1425">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-1425">Word</span></span>

- <span data-ttu-id="224d0-1426">我們已修正基本樣式並未以 [內文樣式] 更新的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1426">We fixed an issue which the base styles are not updated with Normal style.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-august-27"></a><span data-ttu-id="224d0-1428">版本2008：8月27日</span><span class="sxs-lookup"><span data-stu-id="224d0-1428">Version 2008: August 27</span></span>
<span data-ttu-id="224d0-1429">*版本2008（組建13127.20296）*</span><span class="sxs-lookup"><span data-stu-id="224d0-1429">*Version 2008 (Build 13127.20296)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-1433">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-1433">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-1434">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1434">Outlook</span></span>

- <span data-ttu-id="224d0-1435">修正會導致使用者嘗試從次要帳戶建立會議邀請的問題，讓帳戶新增至他們的個人檔案，而不會看到空白的表格: 是欄位而不是其電子郵件地址。</span><span class="sxs-lookup"><span data-stu-id="224d0-1435">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>

- <span data-ttu-id="224d0-1436">修正新增共用信箱之後，導致使用者無法連線至公用資料夾的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1436">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>

- <span data-ttu-id="224d0-1437">修正了當與雲端附件互動時，導致使用者偶爾當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1437">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>

- <span data-ttu-id="224d0-1438">修正編輯收件者時，導致使用者偶爾當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1438">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="224d0-1439">修正會導致使用者在使用壓縮模式時發生異常的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1439">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>

### <a name="word"></a><span data-ttu-id="224d0-1440">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-1440">Word</span></span>

- <span data-ttu-id="224d0-1441">此更改解決了一個問題，即在上一個協同合作的作業後，Microsoft Office 應用程式可能卡在未通知的儲存失敗狀態的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1441">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>

- <span data-ttu-id="224d0-1442">我們已修正整體的 AutoOpen 在 AutoExec 之前執行的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-1442">We fixed an issue where macro AutoOpen runs before AutoExec</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-august-25"></a><span data-ttu-id="224d0-1444">版本 2008：8 月 25 日</span><span class="sxs-lookup"><span data-stu-id="224d0-1444">Version 2008: August 25</span></span>
<span data-ttu-id="224d0-1445">*版本 2008 (組建 13127.20268)*</span><span class="sxs-lookup"><span data-stu-id="224d0-1445">*Version 2008 (Build 13127.20268)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-1447">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-1447">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-1448">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1448">Outlook</span></span>

- <span data-ttu-id="224d0-1449">**依人員搜尋時，收到電子郵件的建議：** 當您在 Outlook 中輸入搜尋字詞時，您會在建議中看到出現最相關的電子郵件。</span><span class="sxs-lookup"><span data-stu-id="224d0-1449">**Receive email suggestions when searching by person.:** As you type your search terms in Outlook you'll receive the most relevant emails surfaced in the suggestions.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-1452">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-1452">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-1453">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1453">Outlook</span></span>

- <span data-ttu-id="224d0-1454">解決會導致使用者在回覆或撰寫新電子郵件時收到下列錯誤的問題：「這個網頁中的某些檔案不存在預期的位置，</span><span class="sxs-lookup"><span data-stu-id="224d0-1454">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="224d0-1455">請問您一定要下載嗎?</span><span class="sxs-lookup"><span data-stu-id="224d0-1455">Do you want to download them anyway?</span></span> <span data-ttu-id="224d0-1456">如果您確定網頁來自信任的來源，請按 [是]」</span><span class="sxs-lookup"><span data-stu-id="224d0-1456">If you’re sure the Web page is from a trusted source, click Yes"</span></span>


### <a name="project"></a><span data-ttu-id="224d0-1457">Project</span><span class="sxs-lookup"><span data-stu-id="224d0-1457">Project</span></span>

- <span data-ttu-id="224d0-1458">修正如果資源中定義了多個成本費率表，其餘成本並不一定都能正確地計算的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1458">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>


### <a name="word"></a><span data-ttu-id="224d0-1459">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-1459">Word</span></span>

- <span data-ttu-id="224d0-1460">解決會導致使用者在回覆或撰寫新電子郵件時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1460">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-august-17"></a><span data-ttu-id="224d0-1462">版本2008：8月17日</span><span class="sxs-lookup"><span data-stu-id="224d0-1462">Version 2008: August 17</span></span>
<span data-ttu-id="224d0-1463">*版本 2008 (組建 13127.20208)*</span><span class="sxs-lookup"><span data-stu-id="224d0-1463">*Version 2008 (Build 13127.20208)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-1465">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-1465">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-1466">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1466">Outlook</span></span>

- <span data-ttu-id="224d0-1467">解決了當代理人在某些情況下遭到拒絕而導致會議無法從經理的行事曆中移除的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1467">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>


- <span data-ttu-id="224d0-1468">解決了導致某些字元集的使用者在將 [智慧型連結] 新增至 SharePoint 檔案時，發現檔案名不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1468">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>


- <span data-ttu-id="224d0-1469">解決了當您從 POP 帳戶刪除4或多個電子郵件時，已選取 [僅下載標題] 選項時，導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1469">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>


- <span data-ttu-id="224d0-1470">解決的問題導致在搜尋控制項中無法顯示滑鼠右鍵功能表。</span><span class="sxs-lookup"><span data-stu-id="224d0-1470">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-august-11"></a><span data-ttu-id="224d0-1472">版本 2008: 8月11日</span><span class="sxs-lookup"><span data-stu-id="224d0-1472">Version 2008: August 11</span></span>
<span data-ttu-id="224d0-1473">*版本 2008 (組建 13127.20164)*</span><span class="sxs-lookup"><span data-stu-id="224d0-1473">*Version 2008 (Build 13127.20164)*</span></span>

<span data-ttu-id="224d0-1474">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="224d0-1474">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-1476">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-1476">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="224d0-1477">Access</span><span class="sxs-lookup"><span data-stu-id="224d0-1477">Access</span></span>

- <span data-ttu-id="224d0-1478">此修正會解決嘗試執行之前會產生「查詢太複雜」錯誤訊息的特定查詢的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1478">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>

- <span data-ttu-id="224d0-1479">如果您已安装 Office 365，您就不需要再安装 [ACE 可再發行引擎]，就能在 Office 生態友善系統外公開 ACE。</span><span class="sxs-lookup"><span data-stu-id="224d0-1479">If you have Office 365 installed, you no longer need to install our ACE Redistributable Engine to expose ACE outside of the Office ecosystem.</span></span> <span data-ttu-id="224d0-1480">因此，如果您使用的是 Office 365，您將不需要 [ACE 可再發行引擎]，也因此不會再遭遇此問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1480">Therefore, for those with Office 365, you will no longer need the ACE Redist Engine, and consequently you should not experience this issue.</span></span>

- <span data-ttu-id="224d0-1481">已解决此問題 - 您現在可以使用 Office 的隨選即用應用程式外的 ODBC 驅動程式。</span><span class="sxs-lookup"><span data-stu-id="224d0-1481">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>

### <a name="excel"></a><span data-ttu-id="224d0-1482">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-1482">Excel</span></span>

- <span data-ttu-id="224d0-1483">我們已修正若圖表數列順序已變更，與該數列對齊的對應核取方塊未隨著該數列重新排序的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1483">We fixed an issue where if the order of a chart series was changed, the corresponding checkbox aligned with the series was not reordered along with the series.</span></span>

- <span data-ttu-id="224d0-1484">嘗試使用 LET () 函數儲存含有公式的檔案時，可能會發生錯誤。</span><span class="sxs-lookup"><span data-stu-id="224d0-1484">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>

- <span data-ttu-id="224d0-1485">我們已修正當透過 VBA 啟用活頁簿的 [ForceFullCalculation] 時，圖表不一會更新的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1485">We fixed an issue where charts were not always updated as expected when "ForceFullCalculation" was enabled via VBA for the workbook.</span></span>

- <span data-ttu-id="224d0-1486">我們已修正具有放射狀漸層填滿的影像複本與原始不符的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1486">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

### <a name="onenote"></a><span data-ttu-id="224d0-1487">OneNote</span><span class="sxs-lookup"><span data-stu-id="224d0-1487">OneNote</span></span>

- <span data-ttu-id="224d0-1488">我們已修正當應用程式視窗調整為小尺寸時，[搜尋] 編輯方塊中的預留位置文字發生溢出的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1488">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>

### <a name="outlook"></a><span data-ttu-id="224d0-1489">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1489">Outlook</span></span>

- <span data-ttu-id="224d0-1490">我們已修正從相同的電子郵件網域在 Outlook 中建立多個設定檔會產生的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1490">We fixed an issue around creating multiple profiles in Outlookfrom the same email domain.</span></span>

- <span data-ttu-id="224d0-1491">解决了導致使用 [共用行事曆改善] 的某些使用者無法查看剛新增的共用行事曆的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1491">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="224d0-1492">解決了導致在 S/MIME 加密郵件的頁首中無法顯示鎖定圖示的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1492">Addressed an issue that caused the lock icon to fail to display in the header of S/MIME encrypted messages.</span></span>

- <span data-ttu-id="224d0-1493">我們已修正，如果未核取 [下載共用資料夾]，共用行事曆會議 [回覆選項] 中缺少 [允許轉寄] 選項的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1493">We fixed an issue where the "Allow Forwarding" option was missing from the shared calendar meeting "Response Options" if Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="224d0-1494">解決了當選取安全性對話方塊上的 [儲存] 選項時，導致使用者無法將 OneDrive 外部的 OneDrive 附件儲存至他們的本機電腦的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1494">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="224d0-1495">我們已修正，即使使用者具有適當的列印權限也會在停用狀態下顯示列印按鈕的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1495">We fixed an issue that would display the print button in a disabled state even though the user had the appropriate print permissions.</span></span>

- <span data-ttu-id="224d0-1496">解決了當以未加密郵件進行傳送時，會導致附件從 S/MIME 郵件中剝離出來的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1496">Addressed an issue that caused attachments to get stripped from S/MIME messages when sending as unencrypted.</span></span>

- <span data-ttu-id="224d0-1497">解決了當純文字 S/MIME 郵件在傳送時發生亂碼的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1497">Addressed an issue that caused plain text S/MIME messages to become garbled when sending.</span></span>

- <span data-ttu-id="224d0-1498">解決了當傳送未加密的 S/MIME 電子郵件時，會導致附件損毀的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1498">Addressed an issue that caused attachments to become corrupted when sending an S/MIME email unencrypted.</span></span>

- <span data-ttu-id="224d0-1499">解決了當寄件者授與 [另存為] 許可權時，會導致收件者無法儲存許可權保護郵件的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1499">Addressed an issue that cause recipients to be unable to save rights protected messages even when the save as permission was granted by the sender.</span></span>

- <span data-ttu-id="224d0-1500">這解決了當使用者從檢查程式視窗回覆受到數位版權管理的郵件，卻沒有所回覆郵件的擁有者權限時，會導致使用者會無法新增簽名的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1500">This fix addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user did not have Owner permissions on the message being replied to.</span></span>

- <span data-ttu-id="224d0-1501">此修正會解決導致 Outlook 無法在 markdown 內容中正確顯示換行符號的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1501">This fix addresses an issue that was causing Outlook to fail to display line breaks properly in markdown content.</span></span>

- <span data-ttu-id="224d0-1502">解決了某些 [進階搜尋] 選項標籤在某些語言中會被截斷的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1502">Addressed an issue that caused the labels for some Advanced Search options to be truncated in some languages.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="224d0-1503">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-1503">PowerPoint</span></span>

- <span data-ttu-id="224d0-1504">我們已修正具有放射狀漸層填滿的影像複本與原始不符的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1504">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

- <span data-ttu-id="224d0-1505">我們已修正 PowerPoint 中的 [表單] 按鈕在不允許存取 Office Store 時不會允許建立表單的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1505">We fixed an issue where the Forms button in PowerPoint did not allow the creation of Forms when access to Office Store was not permitted.</span></span>

### <a name="project"></a><span data-ttu-id="224d0-1506">Project</span><span class="sxs-lookup"><span data-stu-id="224d0-1506">Project</span></span>

- <span data-ttu-id="224d0-1507">我們已修正 [工作委員會] 畫面中列出的工作未與 [指派資源] 對話方塊中的任務同步處理的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1507">We fixed an issue where tasks listed in the Task Board view were not in sync with those in the Assign Resources dialog.</span></span>

- <span data-ttu-id="224d0-1508">我們已修正如果您嘗試從 Project 將 PDF/XPS 儲存至 SharePoint 文件庫，沒有發生任何動作的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1508">We fixed an issue where if you tried to save a PDF/XPS from Project to a SharePoint document library, nothing would happen.</span></span>

- <span data-ttu-id="224d0-1509">我們已修正當您複製並貼上具有多個相關性的工作，並非所有相關性都能正確複製的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1509">We fixed an issue where if you copied & pasted a task that had multiple dependencies, not all dependencies were copied correctly.</span></span>

- <span data-ttu-id="224d0-1510">修正針對 SharePoint 工作清單，第二個索引標籤上的功能區按鈕可能會停用的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1510">Fixed an issue where for a SharePoint tasks list, the ribbon buttons on the second tab may be disabled.</span></span>

### <a name="skype"></a><span data-ttu-id="224d0-1511">Skype</span><span class="sxs-lookup"><span data-stu-id="224d0-1511">Skype</span></span>

- <span data-ttu-id="224d0-1512">將跳舞表情符號膚色變更為中性色彩</span><span class="sxs-lookup"><span data-stu-id="224d0-1512">Changed dancing emoticon skin tone to neutral color</span></span>

### <a name="visio"></a><span data-ttu-id="224d0-1513">Visio</span><span class="sxs-lookup"><span data-stu-id="224d0-1513">Visio</span></span>

- <span data-ttu-id="224d0-1514">在此修正程序完成之後，如果使用者在任何機制 (在此情况下是透過增益集) 停止執行刪除命令，內存便不會洩漏，而且也不會影響整台電腦。</span><span class="sxs-lookup"><span data-stu-id="224d0-1514">After this fix, if the user halted the execution of delete command by any mechanism in between (in this case it was through add-in) the memory won't leak and the whole machine won't be impacted.</span></span>

### <a name="word"></a><span data-ttu-id="224d0-1515">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-1515">Word</span></span>

- <span data-ttu-id="224d0-1516">我們已修正將某些文字及影像貼到 [註解] 方塊之後，Word 停止回應的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1516">We fixed an issue where Word would stop responding after pasting some text and an image in to a comments box.</span></span>

- <span data-ttu-id="224d0-1517">我們已修正具有放射狀漸層填滿的影像複本與原始不符的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1517">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

- <span data-ttu-id="224d0-1518">我們已修正當應用程式視窗調整為小尺寸時，[搜尋] 編輯方塊中的預留位置文字發生溢出的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1518">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>

- <span data-ttu-id="224d0-1519">我們已修正如果新增註解來追蹤變更，將會意外開啟 [修訂] 窗格的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1519">We fixed an issue where if a comment was added to track a change, the revisions pane would unexpectedly open.</span></span>

- <span data-ttu-id="224d0-1520">我們已修正當焦點位於註解文字方塊中時，[編輯器] 命令會被停用的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1520">We fixed an issue where the Editor command was disabled when the focus was in a comment text box.</span></span>

- <span data-ttu-id="224d0-1521">我們已修正當焦點位於註解文字方塊中時，[顯示標記] 命令會被停用的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1521">We fixed an issue where the Show Markup command was disabled when the focus was in a comment text box.</span></span>

- <span data-ttu-id="224d0-1522">我們已修正刪除最後一個註解後，[新增批註] 按鈕停用的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1522">We fixed an issue where the 'New comment' button would be disabled after deleting the last comment.</span></span>

- <span data-ttu-id="224d0-1523">我們已修正 [追蹤修訂] 中的 [特定人員] 選項已停用的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1523">We fixed an issue where the 'Specific People' option for Track Changes was disabled.</span></span>

- <span data-ttu-id="224d0-1524">我們已修正文件連結未透過 [插入] > [連結] 下拉式功能表插入 [註解] 方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1524">We fixed an issue where links to documents were not being inserted to the comments box via the Insert -> Link dropdown.</span></span>

- <span data-ttu-id="224d0-1525">我們已修正了開啟 HTML 檔案時偶爾停止回應的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1525">We fixed an occasional hang while opening HTML files.</span></span>

- <span data-ttu-id="224d0-1526">我們已修正自訂 XML 中的註解狀態在開啟文件時可能會遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1526">We fixed an issue in custom XML where the state of comments may be lost when opening the document.</span></span>

- <span data-ttu-id="224d0-1527">我們已修正 VBA 超連結集合中的超連結計數，在新增包含超連結的影像之後，未正確反覆運算的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1527">We fixed an issue where the hyperlink count in the VBA hyperlinks collection was not iterating correctly after adding an image containing a hyperlink.</span></span>

- <span data-ttu-id="224d0-p193">針對舊版非 Web 服務的 [共用] 窗格，在開啟 [共用] 窗格的情況下關閉文件時，可能會導致當機。現已修正此問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-p193">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash. This is now fixed.</span></span>

- <span data-ttu-id="224d0-1530">我們已修正使用者從工作列開啟新應用程式視窗，並建立新的空白檔時，會造成額外檔案建立的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1530">We fixed an issue where after the user opened a new app window from the taskbar and created a new blank document, additional files were created.</span></span>

- <span data-ttu-id="224d0-1531">我們已修正當使用者在編輯文件，但是許可權遺失時，我們並未通知使用者必須重新驗證的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1531">We fixed an issue where if a user was editing a document but had lost permissions, we were not notifying the user that they had to re-authenticate.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-august-05"></a><span data-ttu-id="224d0-1533">版本 2007：8 月 5 日</span><span class="sxs-lookup"><span data-stu-id="224d0-1533">Version 2007: August 05</span></span>
<span data-ttu-id="224d0-1534">*版本 2007 (組建 13029.20344)*</span><span class="sxs-lookup"><span data-stu-id="224d0-1534">*Version 2007 (Build 13029.20344)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)



[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-1538">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-1538">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-1539">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1539">Outlook</span></span>

- <span data-ttu-id="224d0-1540">解決會導致 Outlook 無法擷取搜尋建議的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1540">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>


- <span data-ttu-id="224d0-1541">解決會導致使用者在擷取角色資訊時有時候會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1541">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>


### <a name="project"></a><span data-ttu-id="224d0-1542">Project</span><span class="sxs-lookup"><span data-stu-id="224d0-1542">Project</span></span>

- <span data-ttu-id="224d0-1543">修正無法開啟已進入錯誤狀態的專案的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1543">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-july-29"></a><span data-ttu-id="224d0-1545">版本 2007：7 月 29 日</span><span class="sxs-lookup"><span data-stu-id="224d0-1545">Version 2007: July 29</span></span>
<span data-ttu-id="224d0-1546">*版本 2007 (組建 13029.20308)*</span><span class="sxs-lookup"><span data-stu-id="224d0-1546">*Version 2007 (Build 13029.20308)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-1548">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-1548">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-1549">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-1549">Excel</span></span>

- <span data-ttu-id="224d0-1550">**使用資料類型從 Power BI 取得組織資料：** 現在，來自 Power BI 的 Excel 資料類型將推出給使用 Office 365 E5/A5 或 Microsoft 365 E5/A5 之組織的測試人員使用。</span><span class="sxs-lookup"><span data-stu-id="224d0-1550">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 E5/A5 or Microsoft 365 E5/A5.</span></span> <span data-ttu-id="224d0-1551">取得您所需的資訊，輕鬆地重新整理，對許多日常工作流程而言至關重要。</span><span class="sxs-lookup"><span data-stu-id="224d0-1551">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="224d0-1552">我們允許您透過 Excel 中的資料類型從 Power BI 存取公司或組織資訊，從而擴充您在試算表中引入連結資訊的能力。</span><span class="sxs-lookup"><span data-stu-id="224d0-1552">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="224d0-1553">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-1553">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="224d0-1554">在[部落格文章](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="224d0-1554">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="224d0-1555">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1555">Outlook</span></span>

- <span data-ttu-id="224d0-1556">**挑選搜尋的位置：** 新的搜尋範圍下拉式清單，可讓您更輕鬆地修改搜尋，並在目前資料夾和目前信箱之間切換。</span><span class="sxs-lookup"><span data-stu-id="224d0-1556">**Pick where to search:** The new search scope drop down allows you to more easily modify your search and switch between Current Folder and Current Mailbox.</span></span> <span data-ttu-id="224d0-1557">感謝每個在 [即將推出] 為 [頂極體驗] 的 新 [搜尋] 提供意見反應的人。</span><span class="sxs-lookup"><span data-stu-id="224d0-1557">Thank you to everyone in Coming Soon who provided feedback on the new Search at Top experience.</span></span> <span data-ttu-id="224d0-1558">因為有這份意見反應，才有這項設計與更新！</span><span class="sxs-lookup"><span data-stu-id="224d0-1558">This design and update came out of that feedback!</span></span>

### <a name="word"></a><span data-ttu-id="224d0-1559">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-1559">Word</span></span>

- <span data-ttu-id="224d0-1560">**以新式註解更輕鬆地進行共同作業：** 新增註解到物件、@提及 同事，並解決註解執行緒，以獲得更佳的共同作業體驗。</span><span class="sxs-lookup"><span data-stu-id="224d0-1560">**Better collaboration with modern comments:** Add comments to objects, @mention colleagues, and resolve comment threads for a better collaboration experience.</span></span> [<span data-ttu-id="224d0-1561">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-1561">Learn more</span></span>](https://support.office.com/article/8d3f868a-867e-4df2-8c68-bf96671641e2)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-1564">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-1564">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-1565">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1565">Outlook</span></span>

- <span data-ttu-id="224d0-1566">解決了導致 CLP 使用者在從受保護的內容切換到未受保護之回復的 [寄件者] 位址時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1566">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>


- <span data-ttu-id="224d0-1567">解決了導致 [排程小幫手] 頁面無法顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1567">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>


- <span data-ttu-id="224d0-1568">解決了事件通知提醒中導致格式設定問題的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1568">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-july-27"></a><span data-ttu-id="224d0-1570">版本 2007：7 月 27 日</span><span class="sxs-lookup"><span data-stu-id="224d0-1570">Version 2007: July 27</span></span>
<span data-ttu-id="224d0-1571">*Version 2007 (組建 13029.20292)*</span><span class="sxs-lookup"><span data-stu-id="224d0-1571">*Version 2007 (Build 13029.20292)*</span></span>
* <span data-ttu-id="224d0-1572">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="224d0-1572">Various bugs and performance fixes.</span></span>

## <a name="version-2007-july-20"></a><span data-ttu-id="224d0-1573">版本 2007：7 月 20 日</span><span class="sxs-lookup"><span data-stu-id="224d0-1573">Version 2007: July 20</span></span>
<span data-ttu-id="224d0-1574">*版本2007 (組建 13029.20236)*</span><span class="sxs-lookup"><span data-stu-id="224d0-1574">*Version 2007 (Build 13029.20236)*</span></span>
* <span data-ttu-id="224d0-1575">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="224d0-1575">Various bugs and performance fixes.</span></span>

## <a name="version-2007-july-15"></a><span data-ttu-id="224d0-1576">版本 2007：7 月 15 日</span><span class="sxs-lookup"><span data-stu-id="224d0-1576">Version 2007: July 15</span></span>
<span data-ttu-id="224d0-1577">*版本 2007 (組建 13029.20200)*</span><span class="sxs-lookup"><span data-stu-id="224d0-1577">*Version 2007 (Build 13029.20200)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-1579">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-1579">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-1580">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-1580">Excel</span></span>

- <span data-ttu-id="224d0-1581">**在 Excel 中製作精美的 Visio 圖表：** 將資料放在工作表上，以建立流程圖或組織圖。</span><span class="sxs-lookup"><span data-stu-id="224d0-1581">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="224d0-1582">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-1582">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-1585">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-1585">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="224d0-1586">Access</span><span class="sxs-lookup"><span data-stu-id="224d0-1586">Access</span></span>

- <span data-ttu-id="224d0-1587">我們已修正在重新整理連結的 SQL 資料表時，連結資料表管理員會提示您輸入主要索引鍵的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1587">We fixed an issue where the linked table manager would prompt a primary key if a linked SQL table was refreshed.</span></span>

- <span data-ttu-id="224d0-1588">我們已修正 [查詢編輯器] 中的查詢捲出畫面的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1588">We fixed an issue where queries in the Query Editor scrolled out of view.</span></span>

- <span data-ttu-id="224d0-1589">我們已修正執行查詢的時間大約比預期完成時間兩倍久的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1589">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

- <span data-ttu-id="224d0-1590">我們已修正導致 Microsoft Access 無法識別連結的 SQL Server 資料表中的識別資料行的問題，這可能會導致不正確地將資料列報告為已刪除。</span><span class="sxs-lookup"><span data-stu-id="224d0-1590">We fixed an issue that caused Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which could cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="224d0-1591">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-1591">Excel</span></span>

- <span data-ttu-id="224d0-1592">我們已修正非 HTTP 或 HTTPS 型 URL 未顯示在 [最近用過的] 清單中的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1592">We fixed an issue where URLs that were not http or https based were not being displayed in the Most Recently Used list.</span></span>

- <span data-ttu-id="224d0-1593">修正在載入含有多張分頁預覽的活頁簿時，可能會發生錯誤或當機問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1593">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>

- <span data-ttu-id="224d0-1594">我們修正以下問題：在特定版本 Excel 中建立的資料模型表格無法在 [表格預覽] 中看到，即使與該表相關聯的查詢尚未編輯。</span><span class="sxs-lookup"><span data-stu-id="224d0-1594">We fixed an issue where data model tables created in certain versions of Excel could not be seen in 'Table Preview' even though the query associated with the table had not been edited.</span></span>

- <span data-ttu-id="224d0-1595">在 [定義名稱\套用名稱] 對話方塊中停用 [忽略相對/絕對] 參照會導致公式無法使用。</span><span class="sxs-lookup"><span data-stu-id="224d0-1595">Ignore Relative/Absolute' references in the Define Name \ Apply Names dialog would cause formulas to not work.</span></span>

- <span data-ttu-id="224d0-1596">我們已修正將活頁簿儲存至 SharePoint/OneDrive 時，會導致自訂功能區索引標籤 CustomUI XML 遭移除的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1596">We fixed an issue where CustomUI XML for a custom ribbon tab was removed when saving a workbook to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="224d0-1597">我們已修正當建議以唯讀方式使用檔案時，活頁簿處於唯讀狀態的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1597">We fixed an issue where workbooks were read-only when the file only had read-only recommended.</span></span>

- <span data-ttu-id="224d0-1598">修正在載入含有多張分頁預覽的活頁簿時，可能會發生錯誤或當機問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1598">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>

- <span data-ttu-id="224d0-1599">我們已修正雷達圖的主要格線無法正確設定格式的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1599">We fixed an issue where the major gridlines of radar charts could not be formatted correctly.</span></span>


- <span data-ttu-id="224d0-1600">我們已修正清除 [進階資料篩選] 可能會遺失表格格式設定的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1600">We fixed an issue where clearing an advanced data filter could lose table formatting.</span></span>


- <span data-ttu-id="224d0-1601">我們已修正嵌入式 PDF 文件的完整路徑顯示在文件標題，而不只是檔案名稱的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1601">We fixed an issue where the full path of an embedded PDF document would show in the document caption rather than just the filename.</span></span>


- <span data-ttu-id="224d0-1602">我們已修正停用 Wolfram 雲端連接器之後，儲存並重新開啟 Excel 活頁簿可能會導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1602">We fixed an issue where after disabling the Wolfram cloud connector and then saving and re-opening an Excel workbook, could result in a crash.</span></span>


- <span data-ttu-id="224d0-1603">我們已修正啟動 Excel 時啟用 [規劃求解] 增益集將導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1603">We fixed an issue where booting Excel with the Solver add-in enabled would result in a crash.</span></span>


### <a name="outlook"></a><span data-ttu-id="224d0-1604">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1604">Outlook</span></span>

- <span data-ttu-id="224d0-1605">我們已修正如果在 [收件者] 行上有超過 130 個收件者，Outlook 會當機的問題，且我們也改善了呈現文字的效能。</span><span class="sxs-lookup"><span data-stu-id="224d0-1605">We fixed an issue where Outlook would hang if there were over 130 recipients on the 'To' line and we also improved the performance of rendering the text.</span></span>


- <span data-ttu-id="224d0-1606">我們已修正以下問題：當使用多個不同解析度的監視器時，輸入法編輯器 (IEM) 視窗會覆蓋透過 IME 輸入的文字。</span><span class="sxs-lookup"><span data-stu-id="224d0-1606">We fixed an issue where the Input Method Editor (IME) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>


- <span data-ttu-id="224d0-1607">我們已修正「待辦事項列」中跨越兩天以上的活動，在後續的所有日期中顯示相同結束時間的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1607">We fixed an issue in the 'To Do Bar' where events that spanned more than two days, displayed the same end time for all subsequent days.</span></span>


- <span data-ttu-id="224d0-1608">解決會導致使用者看到他們透過拖放附件，以複製到其檔案系統所建立附件的建立日期設為 4501 年 1 月 1 日的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1608">Addresses an issue that caused users to see the creation date of attachments that they copied to their file system via drag and drop getting set to January 1, 4501.</span></span>


- <span data-ttu-id="224d0-1609">我們已修正使用者無法使用通訊群組清單中的「傳送為」或「代理傳送者」的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1609">We fixed an issue where users were unable to 'Send As' or 'Send on behalf' of a distribution list.</span></span>


- <span data-ttu-id="224d0-1610">解決在編輯經理行事曆上的現有行事曆約會時，導致代理人收到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1610">Addresses an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>


- <span data-ttu-id="224d0-p198">我們已修正會導致使用者在關閉先前儲存的約會時看到下列錯誤的問題：「項目無法儲存，因為已被其他使用者或已在其他視窗中變更過。您要在預設資料夾為這個項目建立複本?」</span><span class="sxs-lookup"><span data-stu-id="224d0-p198">We fixed an issue that caused users to see the following error when closing an appointment that was previously saved "The item cannot be saved because it was changed by another user or in another window. Do you want to make a copy in the default folder for the item?"</span></span>


- <span data-ttu-id="224d0-1613">解決會導致若「未」核取 [下載共用資料夾]，共用行事曆會議的 [回應選項] 中會遺失 [允許轉寄] 選項的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1613">Addresses an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>


- <span data-ttu-id="224d0-1614">解決選取安全性對話方塊上的 [儲存] 選項時，會導致使用者無法將來自其租用戶外部的 OneDrive 附件儲存至其本機電腦的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1614">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>


- <span data-ttu-id="224d0-1615">我們已修正導致 Outlook 使用者在使用共用行事曆後，在幾分鐘內訊息清單停止更新的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1615">We fixed an issue that caused users of Outlook to see their message list stop updating for several minutes after using shared calendars.</span></span>


- <span data-ttu-id="224d0-1616">我們已修正行事曆提醒無法針對一週內即將到來的會議顯示確切時間的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1616">We fixed an issue that prevented calendar reminders from showing exact times for meetings coming up in less than a week.</span></span> 


- <span data-ttu-id="224d0-1617">我們已修正在郵件中插入影像內嵌，然後將郵件儲存為草稿將會重新調整影像大小的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1617">We fixed an issue where inserting an image inline in a message, then saving the message as a draft would result in a resizing of the image.</span></span>


- <span data-ttu-id="224d0-1618">我們已修正在編輯主旨之後，導致 NDR 郵件的本文從 Unicode 變更為 ASCII 的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1618">We fixed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>


- <span data-ttu-id="224d0-1619">我們已修正迷你行事曆中的日期無法針對日本使用者顯示粗體的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1619">We fixed an issue where dates in the mini calendar failed to display in bold for users in Japan.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="224d0-1620">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-1620">PowerPoint</span></span>

- <span data-ttu-id="224d0-1621">我們已修正在即時共同撰寫工作階段期間，使用者的目前狀態色彩指示器無法在共同撰寫文件庫中重新整理的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1621">We fixed an issue where a user's presence color indicator was not getting refreshed in the co-authoring gallery during a live co-authoring session.</span></span>


- <span data-ttu-id="224d0-1622">我們已修正將 HTML 貼到投影片上的文字區域時，會改為貼上投影片最上方所建立的文字方塊中的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1622">We fixed an issue where pasting HTML to a text area on a slide would instead get pasted into a text box created at the top of the slide.</span></span>


- <span data-ttu-id="224d0-1623">我們已修正在 [簡報者檢視畫面] 中選取所有投影片、使用 Alt+Tab 退出 [簡報者檢視畫面] 並返回投影片放映，然後按一下 [結束放映] 時，將導致未處理例外狀況的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1623">We fixed an issue where selecting all slides in Presenter View, then exiting Presenter View using Alt+Tab and returning to the slide show and clicking 'End Show' would result in an unhandled exception.</span></span>


### <a name="project"></a><span data-ttu-id="224d0-1624">Project</span><span class="sxs-lookup"><span data-stu-id="224d0-1624">Project</span></span>

- <span data-ttu-id="224d0-1625">修正無法將從 Project 將 PDF/XPS 儲存至 SharePoint 文件庫的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1625">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>


- <span data-ttu-id="224d0-1626">修正 URL 以 .com 結尾時，無法從 Project Web App 在 Project 傳統型用戶端開啟專案的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1626">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>


- <span data-ttu-id="224d0-1627">我們已修正 Project 在開啟特定 XML 檔案時可能當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1627">We fixed an issue where Project may crash when opening certain XML files.</span></span>


- <span data-ttu-id="224d0-1628">我們已修正 URL 以 '.com' 結尾時，無法從 Project Web App 在 Project 傳統型用戶端開啟專案的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1628">We fixed an issue where projects couldn't be opened in the Project desktop client from the Project Web App if the URL ended in '.com'.</span></span>


- <span data-ttu-id="224d0-1629">修正問題：如果您貼上具有多個相關性的工作，並不會正確複製所有相關性。</span><span class="sxs-lookup"><span data-stu-id="224d0-1629">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>


- <span data-ttu-id="224d0-1630">修正 [指派資源] 對話方塊中選取的工作與工作面板檢視中所選工作不同的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1630">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>


- <span data-ttu-id="224d0-1631">我們已修正當專案摘要工作，或專案 [開始/工作] 欄位變更時，ProjectBeforeTaskChange 事件無法觸發的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1631">We fixed an issue where the ProjectBeforeTaskChange event didn't fire when there was a change to the project summary task, either the project start/task field.</span></span>


- <span data-ttu-id="224d0-1632">我們已修正以下問題：如果固定工期的任務已 100% 完成，但未指定 [實際完成日期]，則任務的完成 % 將顯示為低於 100%。</span><span class="sxs-lookup"><span data-stu-id="224d0-1632">We fixed an issue where if Fixed Duration tasks are at 100% complete but the Actual Finish is not specified, the Task % Complete would display as less than 100%.</span></span>

- <span data-ttu-id="224d0-1633">我們已修正以下問題：比較基準重設或更新可能會變更時間分段預算成本/工時資源，且比較基準反映不正確的預算值。</span><span class="sxs-lookup"><span data-stu-id="224d0-1633">We fixed an issue where a baseline reset or update could change time-phased budget cost/work resources and the baseline could reflect incorrect budget values.</span></span>


- <span data-ttu-id="224d0-1634">我們已修正政府社群雲端中的 Project Planner 連結已停用的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1634">We fixed an issue where Project Planner links in Government Community Cloud environments had been disabled.</span></span>


- <span data-ttu-id="224d0-1635">我們已修正如果文件庫處於新式模式，您無法從 SharePoint 文件庫開啟 Project 檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1635">We fixed an issue where you couldn't open a Project file from a SharePoint document library if the library was in modern mode.</span></span>


### <a name="word"></a><span data-ttu-id="224d0-1636">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-1636">Word</span></span>

- <span data-ttu-id="224d0-1637">我們已修正使用 Office 功能區中的 [清除格式設定] 按鈕清除 [註解] 窗格中的格式設定時，無法運作的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1637">We fixed an issue where the ability to clear formatting within the Comments pane via the Clear Formatting button in the Office Ribbon was not working.</span></span>


- <span data-ttu-id="224d0-1638">我們已修正將插入可縮放向量圖形 (SVG) 中的文字插入到 Word、Excel 或 PowerPoint 檔案、儲存並關閉檔案，然後重新開啟檔案後，難以辨識的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1638">We fixed an issue where text inserted in a Scalable Vector Graphic (SVG) was illegible after inserting it in a Word, Excel, or PowerPoint file, saving and closing the file, and then re-opening the file.</span></span>


- <span data-ttu-id="224d0-1639">我們已修正當尺規未顯示時變更表格大小，導致在背景中執行其他應用程式開始閃爍的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1639">We fixed an issue where changing the size of a table when the ruler is not displayed caused other applications running in the background to start flashing.</span></span>


- <span data-ttu-id="224d0-1640">我們已修正在共同撰寫模式中，註解回覆有時候不會顯示在 [註解] 窗格中，而是顯示在 [修訂] 窗格中的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1640">We fixed an issue where in co-authoring mode, comment replies would sometimes not show up in the comments pane but would be visible in the revisions pane.</span></span>


- <span data-ttu-id="224d0-1641">我們已修正在共同撰寫模式期間，當發生合併衝突且使用者已選取放棄變更時，我們不再顯示儲存或捨棄變更選項的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1641">We fixed an issue during co-authoring mode when there is a merge conflict and the user has already chosen to discard changes, we no longer display the option to save or discard changes.</span></span>


- <span data-ttu-id="224d0-1642">我們已修正 HTML 超連結色彩無法正確呈現的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1642">We fixed an issue where the HTML hyperlink color was not being rendered correctly.</span></span>


- <span data-ttu-id="224d0-1643">我們已修正以下問題：如果 Word 經常開啟的文件清單多於 50 個，然後儲存並開啟文件後，即使該文件沒有進行任何修訂，也會顯示歷程記錄。</span><span class="sxs-lookup"><span data-stu-id="224d0-1643">We fixed an issue where if Word had a list of more than 50 frequently opened documents, then after saving and opening a document, a revision history would be displayed even though no revisions were made to that document.</span></span>


- <span data-ttu-id="224d0-1644">我們已修正共同撰寫期間的自動儲存問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1644">We fixed in issue with autosave during coauthoring.</span></span>


- <span data-ttu-id="224d0-1645">我們已修正一個問題，當嘗試使用新名稱儲存包含巨集的檔案時，無論使用者輸入什麼名稱，都會導致該檔案以 .docx 副檔名和檔案名稱 'WRO0004.docx' 儲存，進而導致文件無法使用。</span><span class="sxs-lookup"><span data-stu-id="224d0-1645">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with a .docx extension and the filename 'WRO0004.docx', regardless of what the user entered, rendering the document unusable.</span></span>


### <a name="office-suite"></a><span data-ttu-id="224d0-1646">Office 套件</span><span class="sxs-lookup"><span data-stu-id="224d0-1646">Office Suite</span></span>

- <span data-ttu-id="224d0-1647">關閉 Office 檔案時，計時問題可能會導致當機</span><span class="sxs-lookup"><span data-stu-id="224d0-1647">A timing issue could cause a crash when closing office files</span></span>

- <span data-ttu-id="224d0-1648">此問題的修正程式是確保服務正確計算新增的產品。</span><span class="sxs-lookup"><span data-stu-id="224d0-1648">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="224d0-1649">我們已篩選出新增的產品 (確保它們同時存在於新的設定中)，並將它們新增到現有產品發行識別碼的結尾。</span><span class="sxs-lookup"><span data-stu-id="224d0-1649">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-july-09"></a><span data-ttu-id="224d0-1651">版本 2006：7 月 09 日</span><span class="sxs-lookup"><span data-stu-id="224d0-1651">Version 2006: July 09</span></span>
<span data-ttu-id="224d0-1652">*版本 2006 (組建 13001.20384)*</span><span class="sxs-lookup"><span data-stu-id="224d0-1652">*Version 2006 (Build 13001.20384)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-1654">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-1654">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-1655">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-1655">Excel</span></span>

- <span data-ttu-id="224d0-1656">**建立 PDF 連線：** 連線至、匯入、重新整理 PDF 中的資料。</span><span class="sxs-lookup"><span data-stu-id="224d0-1656">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="224d0-1657">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-1657">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="224d0-1658">**建立變數以在公式中使用：** 使用 LET 函數改善效能、可讀性及可組合性。</span><span class="sxs-lookup"><span data-stu-id="224d0-1658">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="224d0-1659">此函數可讓您在新的或現有的公式中建立命名變數。</span><span class="sxs-lookup"><span data-stu-id="224d0-1659">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="224d0-1660">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-1660">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="224d0-1661">在[部落格文章](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="224d0-1661">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

- <span data-ttu-id="224d0-1662">**Excel 中的鍵盤快速鍵：** Excel 升級的鍵盤快速鍵</span><span class="sxs-lookup"><span data-stu-id="224d0-1662">**Keyboard shortcuts in Excel:** Updated keyboard shortcuts for Excel</span></span>

### <a name="outlook"></a><span data-ttu-id="224d0-1663">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1663">Outlook</span></span>

- <span data-ttu-id="224d0-1664">**在 Outlook 中使用 [快速投票] 建立投票：** 輕鬆建立投票，收集投票，並查看電子郵件中的結果 [深入瞭解](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="224d0-1664">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="224d0-1665">**將圖片作為電子郵件的一部分傳送時，讓圖片保持高畫質：** 一個新 Outlook 設定，可讓您在隨著電子郵件內容傳送圖片時限制圖片壓縮</span><span class="sxs-lookup"><span data-stu-id="224d0-1665">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-1668">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-1668">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="224d0-1669">Access</span><span class="sxs-lookup"><span data-stu-id="224d0-1669">Access</span></span>

- <span data-ttu-id="224d0-1670">此問題已解決，您應該能成功地將包含身分識別(例如 [自動編號]) 欄位的連結的 SQL 資料表插入到 Access 中。</span><span class="sxs-lookup"><span data-stu-id="224d0-1670">This issue is resolved, and you should expect to be able to successfully insert linked SQL tables that include an identity (e.g. autonumber) field into Access.</span></span>

### <a name="excel"></a><span data-ttu-id="224d0-1671">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-1671">Excel</span></span>

- <span data-ttu-id="224d0-1672">修正當您從帳戶登出時，嘗試建立資料連線時，可能會發生的當機問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1672">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

### <a name="outlook"></a><span data-ttu-id="224d0-1673">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1673">Outlook</span></span>

- <span data-ttu-id="224d0-1674">解決了當選取安全性對話方塊上的 [儲存] 選項時，導致使用者無法將 OneDrive 外部的 OneDrive 附件儲存至他們的本機電腦的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1674">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="office-suite"></a><span data-ttu-id="224d0-1675">Office 套件</span><span class="sxs-lookup"><span data-stu-id="224d0-1675">Office Suite</span></span>

- <span data-ttu-id="224d0-1676">我們會將新的 AppV51 向後移，以修正先前 AppV51 中的回歸。</span><span class="sxs-lookup"><span data-stu-id="224d0-1676">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="224d0-1677">當您啟用增益集，而登錄 TabProcGrowth 值為 REG_SZ 類型且其值為 "0"時，辦公主機視窗會當機。</span><span class="sxs-lookup"><span data-stu-id="224d0-1677">he office host was crashing in windows, when an add-in is being activated while the registry TabProcGrowth value is REG_SZ type and with value "0".</span></span>  <span data-ttu-id="224d0-1678">這個登錄 TabProcGrowth 值可以在下列4個路徑中的任何一個中： HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main HKEY_CURRENT_USER \Software\Policies\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINE \Software\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINER \Software\Policies\Microsoft\Internet Explorer\Main 此變更將修正此問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1678">That registry TabProcGrowth value can be under any one of 4 paths: HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main HKEY_CURRENT_USER\Software\Policies\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINE\Software\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINER\Software\Policies\Microsoft\Internet Explorer\Main This change would fix this issue.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-june-25"></a><span data-ttu-id="224d0-1680">版本 2006：6 月 25 日</span><span class="sxs-lookup"><span data-stu-id="224d0-1680">Version 2006: June 25</span></span>
<span data-ttu-id="224d0-1681">*版本2006（組建13001.20266）*</span><span class="sxs-lookup"><span data-stu-id="224d0-1681">*Version 2006 (Build 13001.20266)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-1683">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-1683">Feature updates</span></span>
### <a name="visio"></a><span data-ttu-id="224d0-1684">Visio</span><span class="sxs-lookup"><span data-stu-id="224d0-1684">Visio</span></span>

- <span data-ttu-id="224d0-1685">**在 Excel 中製作精美的 Visio 圖表：** 根據工作表上的資料，建立流程圖或組織圖。</span><span class="sxs-lookup"><span data-stu-id="224d0-1685">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart based on data in a worksheet.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-1688">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-1688">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="224d0-1689">Access</span><span class="sxs-lookup"><span data-stu-id="224d0-1689">Access</span></span>

- <span data-ttu-id="224d0-p203">此問題現在已解決。請讓團隊知道您就此程序是否遇到更多問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-p203">This problem is now resolved. Please let the team know if you experience more issues with this process.</span></span>


### <a name="outlook"></a><span data-ttu-id="224d0-1692">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1692">Outlook</span></span>

- <span data-ttu-id="224d0-1693"><span style="display:inline !important;">解決一個問題，該問題導致使用者看到<span>&nbsp;</span></span><span style="box-sizing:border-box;font-family:Calibri, sans-serif;font-size:14.6667px;display:inline !important;">附件的建立日期&nbsp; 他們透過托放方式將該附件複製到其檔案系統&nbsp; 該建立日期設於 4501年1月1日。</span></span><span class="sxs-lookup"><span data-stu-id="224d0-1693"><span style="display:inline !important;">Addresses an issue that caused users to see<span>&nbsp;</span></span><span style="box-sizing:border-box;font-family:Calibri, sans-serif;font-size:14.6667px;display:inline !important;">the creation date of&nbsp; attachments that they copied to their file system via drag and drop getting&nbsp; set to January 1, 4501.</span></span></span><br>


- <span data-ttu-id="224d0-1694"><span style="font-family:&quot;Segoe UI&quot;, system-ui, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, sans-serif;display:inline !important;">解決導致 [共用行事曆] 改善的使用者查看行事曆失敗的問題。</span></span><span class="sxs-lookup"><span data-stu-id="224d0-1694"><span style="font-family:&quot;Segoe UI&quot;, system-ui, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, sans-serif;display:inline !important;">Addresses an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span></span><br>


- <span data-ttu-id="224d0-1695"><span style="display:inline !important;">解決導致使用者看到 Outlook 持續提示他們執行收件匣修復工具的問題。</span></span><span class="sxs-lookup"><span data-stu-id="224d0-1695"><span style="display:inline !important;">Addresses an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span></span><br>


- <span data-ttu-id="224d0-1696"><span style="display:inline !important;">解決導致在[建議功能]中尋找功能沒有結果並未留給使用者選項以提交新功能點子的問題。</span></span><span class="sxs-lookup"><span data-stu-id="224d0-1696"><span style="display:inline !important;">Addresses an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span></span><br>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-june-18"></a><span data-ttu-id="224d0-1698">版本 2006：6 月 18 日</span><span class="sxs-lookup"><span data-stu-id="224d0-1698">Version 2006: June 18</span></span>
<span data-ttu-id="224d0-1699">*版本 2006 (組建 13001.20198)*</span><span class="sxs-lookup"><span data-stu-id="224d0-1699">*Version 2006 (Build 13001.20198)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-1701">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-1701">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-1702">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-1702">Excel</span></span>



- <span data-ttu-id="224d0-1703">**儲存至 [釘選資料夾]：** 釘選您的資料夾可讓您更輕鬆地儲存 Office 檔案，我們收到意見反應，使用者希望能在新檔案儲存時可以在可用的資料夾上有更多控制權。</span><span class="sxs-lookup"><span data-stu-id="224d0-1703">**Save to Pinned Folders:** Pin your folders makes saving Office files easier We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="224d0-1704">我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。</span><span class="sxs-lookup"><span data-stu-id="224d0-1704">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="224d0-1705">這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。</span><span class="sxs-lookup"><span data-stu-id="224d0-1705">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> <br /><span data-ttu-id="224d0-1706">在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="224d0-1706">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="224d0-1707">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-1707">PowerPoint</span></span>

- <span data-ttu-id="224d0-1708">**儲存至 [釘選資料夾]：** 釘選您的資料夾可讓您更輕鬆地儲存 Office 檔案，我們收到意見反應，使用者希望能在新檔案儲存時可以在可用的資料夾上有更多控制權。</span><span class="sxs-lookup"><span data-stu-id="224d0-1708">**Save to Pinned Folders:** Pin your folders makes saving Office files easier We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="224d0-1709">我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。</span><span class="sxs-lookup"><span data-stu-id="224d0-1709">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="224d0-1710">這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。</span><span class="sxs-lookup"><span data-stu-id="224d0-1710">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="224d0-1711">在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="224d0-1711">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="word"></a><span data-ttu-id="224d0-1712">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-1712">Word</span></span>

- <span data-ttu-id="224d0-1713">**儲存至 [釘選資料夾]：** 釘選您的資料夾可讓您更輕鬆地儲存 Office 檔案。我們收到意見反應，使用者希望能在新檔案儲存時可以在可用的資料夾上有更多控制權。</span><span class="sxs-lookup"><span data-stu-id="224d0-1713">**Save to Pinned Folders:** Pin your folders makes saving Office files easierWe received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="224d0-1714">我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。</span><span class="sxs-lookup"><span data-stu-id="224d0-1714">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="224d0-1715">這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。</span><span class="sxs-lookup"><span data-stu-id="224d0-1715">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> <br /><span data-ttu-id="224d0-1716">在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="224d0-1716">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-1719">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-1719">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-1720">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-1720">Excel</span></span>

- <span data-ttu-id="224d0-1721">修正當儲存至 SharePoint/OneDrive 時，會導致自訂功能區索引標籤 CustomUI XML 的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1721">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

### <a name="outlook"></a><span data-ttu-id="224d0-1722">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1722">Outlook</span></span>

- <span data-ttu-id="224d0-1723">解決了啟用雲端設定時，按下 Ctrl + 按一下會造成運作停止的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1723">Addressed an issue that caused Ctrl+click to stop working when cloud settings were enabled.</span></span>

### <a name="project"></a><span data-ttu-id="224d0-1724">專案</span><span class="sxs-lookup"><span data-stu-id="224d0-1724">Project</span></span>

- <span data-ttu-id="224d0-1725">修正當標示為100% 完成之工作錯誤地變更為完成度低於100% 的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1725">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-june-11"></a><span data-ttu-id="224d0-1727">版本 2006：6 月 11 日</span><span class="sxs-lookup"><span data-stu-id="224d0-1727">Version 2006: June 11</span></span>
<span data-ttu-id="224d0-1728">*版本 2006 (組建 13001.20144)*</span><span class="sxs-lookup"><span data-stu-id="224d0-1728">*Version 2006 (Build 13001.20144)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-1730">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-1730">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="224d0-1731">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-1731">PowerPoint</span></span>

- <span data-ttu-id="224d0-1732">**改善的 PowerPoint 中的 Steam 影片效能：** 我們改善了 Microsoft Stream 影片的播放效能，將影片載入時間減至最少，以建立出流暢的觀賞體驗。</span><span class="sxs-lookup"><span data-stu-id="224d0-1732">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="224d0-1733">您可以使用 Microsoft Stream 上您的公司影片來建立更完善的簡報。</span><span class="sxs-lookup"><span data-stu-id="224d0-1733">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

### <a name="word"></a><span data-ttu-id="224d0-1734">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-1734">Word</span></span>

- <span data-ttu-id="224d0-1735">**以向量保留文字：** 現在當您在 Excel、Word 和 PowerPoint 中轉換地圖、圖表和其他 SVG 向量等物件時，您可以保留物件中的文字。</span><span class="sxs-lookup"><span data-stu-id="224d0-1735">**Retain text in vectors:** Now you can retain the text in maps, charts, and other SVG vectors when converting these objects in Excel, Word, and PowerPoint.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-1738">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-1738">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-1739">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-1739">Excel</span></span>

- <span data-ttu-id="224d0-1740">我們已修正在使用 OneDrive 時，Excel 偶爾會關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1740">We fixed an issue where Excel would occasionally shut down when engaging OneDrive.</span></span>

- <span data-ttu-id="224d0-1741">我們已修正圖表座標軸自訂值無法正確套用的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1741">We fixed an issue where custom values on the chart axis would not get applied correctly.</span></span>

- <span data-ttu-id="224d0-1742">我們已修正包含多個含有定義名稱的公式會導致儲存檔案時間加長的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1742">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

- <span data-ttu-id="224d0-1743">我們已修正導致印表機名稱在可用印表機清單中重複的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1743">We fixed an issue that caused printer names to be duplicated in the list of available printers.</span></span>

- <span data-ttu-id="224d0-1744">我們已修正在使用者刪除合併的欄時，造成執行時間增加的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1744">We fixed an issue that resulted in improved performance time for users when they deleted merged columns.</span></span>

- <span data-ttu-id="224d0-1745">我們已修正因為增益集是以字母順序裝載，而不是以使用者指定的順序載入，而造成出現「因為此活頁簿目前有他人進行參考，而無法關閉」的錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1745">We fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="224d0-1746">我們已修正管理 Excel 與部分協力廠商輔助技術應用程式之間的字型時發生記憶體損毀的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1746">We fixed an issue where memory was being corrupted when managing fonts between Excel and some third party assistive technology applications.</span></span>

- <span data-ttu-id="224d0-1747">我們已修正在相同活頁簿中按一下加上書簽的超連結會導致活頁簿隱藏的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1747">We fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="224d0-1748">我們已修正某些複製和貼上的圖表連結使用的是映射磁碟機位址，而不是通用位址的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1748">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="224d0-1749">我們已修正當 Excel 視窗透過 Teams 共用時，使用 Ctrl + Shift + 方向鍵滑動後，Excel 可能會無法回應的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1749">We fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window was shared through Teams.</span></span>

- <span data-ttu-id="224d0-1750">我們已修正當增益集在工作表中詢問含有 noSelect 鎖定的圖形的主項目目時，Excel 會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1750">We fixed an issue where Excel would crash when Add-ins ask for Host Items on worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="224d0-1751">解決了嘗試將樞紐分析表插入圖表時 Excel 可能會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1751">Addressed an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

### <a name="outlook"></a><span data-ttu-id="224d0-1752">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1752">Outlook</span></span>

- <span data-ttu-id="224d0-1753">我們已修正以下問題：當使用多個不同解析度的監視器時，輸入法編輯器 (IEM) 視窗會覆蓋透過 IME 輸入的文字。</span><span class="sxs-lookup"><span data-stu-id="224d0-1753">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="224d0-1754">我們已修正在撰寫新電子郵件訊息時，檢視範本會導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1754">We fixed an issue where viewing a template when composing a new email message would result in a crash.</span></span>

- <span data-ttu-id="224d0-1755">我們已修正在 Outlook 版本 1911之後，使用者無法使用 Exchange 2010 公用資料夾的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1755">We fixed an issue where users were unable to Exchange 2010 public folders after Outlook version 1911.</span></span>

- <span data-ttu-id="224d0-1756">我們已修正 Office 功能區中群組行事曆分類按鈕已停用的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1756">We fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>

- <span data-ttu-id="224d0-1757">解決了 Outlook 無法啟用 [資料遺失保護原則] 提示使用 M365 商務版進階方案並為此服務付款的的使用者之問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1757">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="224d0-1758">已解決導致 Outlook 在某些 Windows 組建上當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1758">Addressed an issue that caused Outlook to crash on some Windows builds.</span></span>

- <span data-ttu-id="224d0-1759">我們已修正使用者無法與來賓使用者共用行事曆的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1759">We fixed an issue where users were unable to share a calendar with a guest user.</span></span>

- <span data-ttu-id="224d0-1760">我們已修正使用者看到將午夜臨界值視為全天事件的行事曆專案的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1760">We fixed an issue where users saw calendar items that spanned the midnight threshold as All day events.</span></span>

- <span data-ttu-id="224d0-1761">我們已修正會導致使用者在高 DPI 監視器上遺失 [線上封存] 摘要的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1761">We fixed an issue that resulted in the Online Archive dropdown in folder properties to be missing for users on high DPI monitors.</span></span>

- <span data-ttu-id="224d0-1762">我們已修正當使用者在資料夾之間移動專案時，BeforeItemMove 事件未正確觸發的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1762">We fixed an issue where the Folder.BeforeItemMove event didn't fire correctly when a user moved items between folders.</span></span>

- <span data-ttu-id="224d0-1763">我們已修正當兩個增益集將按鈕新增到功能區中相同群組時，Outlook 發生當端的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1763">We fixed an issue where Outlook crashed when two add-ins added a button to the same group in the ribbon.</span></span>

- <span data-ttu-id="224d0-1764">我們已修正當處理純文字電子郵件中的超連結時，會導致使用者遇到 Outlook 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1764">We fixed an issue that caused users to experience a crash in Outlook when working with hyperlinks in Plain Text emails.</span></span>

- <span data-ttu-id="224d0-1765">我們已修正會導致 Outlook 無法剖析使用 RFC2231 編碼的長檔名的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1765">We fixed an issue that caused Outlook to be unable to parse long file names encoded with RFC2231.</span></span>

- <span data-ttu-id="224d0-1766">我們已修正會導致 Outlook 使用者在使用螢幕閱讀器時遇到間歇性的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1766">We fixed an issue that was causing Outlook users to experience intermittent hangs when using screen readers.</span></span>

- <span data-ttu-id="224d0-1767">我們已修正具有衝突連絡人的使用者在 Outlook 中遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1767">We fixed an issue that would cause users with conflicting contacts to experience crashes in Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="224d0-1768">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-1768">PowerPoint</span></span>

- <span data-ttu-id="224d0-1769">我們已修正使用表單型驗證開啟伺服器設定的檔案時發生的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1769">We fixed an issue with opening server-configured files with forms-based authentication.</span></span>

- <span data-ttu-id="224d0-1770">我們已修正內嵌圖表/活頁簿的 PowerPoint 檔案可能會導致儲存檔案失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1770">We fixed an issue where PowerPoint files with embedded charts / workbooks could result in failures when saving the file.</span></span>

- <span data-ttu-id="224d0-1771">我們已修正放大和縮小簡報區域會造成縮放選取選框和滑鼠指標之間的間隙的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1771">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

- <span data-ttu-id="224d0-1772">我們已修正使用滑鼠滾輪縮放後，投影片並未居中的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1772">We fixed an issue where slides were not centered after zooming using the mouse wheel.</span></span>

- <span data-ttu-id="224d0-1773">我們已修正使用英文 (瑞士) (QWERTZ) 鍵盤時鍵盤快速鍵和拼字檢查無法正常運作的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1773">We fixed an issue where keyboard shortcuts and spell check wouldn’t function as expected when using an English Switzerland (QWERTZ) keyboard.</span></span>

- <span data-ttu-id="224d0-1774">我們已修正使用者已關閉的註解窗格會自動開啟的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1774">We fixed an issue where a Comment pane that had been closed by the user would re-open automatically.</span></span>

- <span data-ttu-id="224d0-1775">我們已修正某張投影片的投影片編輯工具會在下一張投影片上重疊的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1775">We fixed an issue where the slide editor from one slide would overlap on to the next slide.</span></span>

### <a name="project"></a><span data-ttu-id="224d0-1776">Project</span><span class="sxs-lookup"><span data-stu-id="224d0-1776">Project</span></span>

- <span data-ttu-id="224d0-1777">修正當專案摘要工作-或是專案[開始/工作]欄位有變更時，ProjectBeforeTaskChange 事件不會觸發的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1777">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

- <span data-ttu-id="224d0-1778">修正當標示為100% 完成之工作錯誤地變更為完成度低於100% 的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1778">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

- <span data-ttu-id="224d0-1779">我們已修正在按一下 [選項] 之後 Project 會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1779">We fixed an issue where Project would crash after clicking on Options.</span></span>

- <span data-ttu-id="224d0-1780">我們已修正在刪除母計畫之後，無法刪除或重新指派孤立工作的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1780">We fixed an issue that prevented orphaned tasks from being deleted or re-assigned after their parent plan was deleted.</span></span>

### <a name="visio"></a><span data-ttu-id="224d0-1781">Visio</span><span class="sxs-lookup"><span data-stu-id="224d0-1781">Visio</span></span>

- <span data-ttu-id="224d0-1782">有已修復的依賴代碼迴歸分析。</span><span class="sxs-lookup"><span data-stu-id="224d0-1782">There was regression in dependent code which has been fixed.</span></span> <span data-ttu-id="224d0-1783">現在，影像會在執行于 SharePoint Onprem 上的 Visio 服務中呈現。</span><span class="sxs-lookup"><span data-stu-id="224d0-1783">Now, the images are getting rendered in Visio services running on SharePoint Onprem.</span></span>

### <a name="word"></a><span data-ttu-id="224d0-1784">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-1784">Word</span></span>

- <span data-ttu-id="224d0-1785">我們已修正註解窗格中的時間戳記不是根據系統區域設定時間所建立的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1785">We fixed an issue where timestamps in Comment panes were not based on the system locale time.</span></span>

- <span data-ttu-id="224d0-1786">已解決在 URL 包含查詢元件時，從自訂檔傳遞 (aspx) 開啟 Word 檔的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1786">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>

- <span data-ttu-id="224d0-1787">我們已修正在註解窗格中複製及貼上文字不會顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1787">We fixed an issue where copy and pasting text to a comment pane would not be displayed.</span></span>

- <span data-ttu-id="224d0-1788">我們已修正註解中的超連結無法正常運作的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1788">We fixed an issue where hyperlinks in comments weren’t working.</span></span>

- <span data-ttu-id="224d0-1789">我們已修正放大和縮小簡報區域會造成縮放選取選框和滑鼠指標之間的間隙的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1789">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

- <span data-ttu-id="224d0-1790">我們已修正網頁應用程式與傳統型應用程式之間的註解未同步處理的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1790">We fixed an issue where comments between the web app and the desktop application were not in sync.</span></span>

- <span data-ttu-id="224d0-1791">我們已修正註解提示泡泡在100% 縮放比例中顯示模糊的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1791">We fixed an issue where comment hint bubbles appeared blurry at 100% zoom.</span></span>

- <span data-ttu-id="224d0-1792">我們已修正在空白文件中新增註解卻未執行任何動作的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1792">We fixed an issue where adding a new comment on a blank document wouldn't do anything.</span></span>

- <span data-ttu-id="224d0-1793">我們已修正無法將 HTML 貼入行事曆的 WordMail 的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1793">We fixed an issue where pasting HTML into WordMail for Calendar wasn’t working.</span></span>

- <span data-ttu-id="224d0-1794">我們已修正在共同撰寫的會話中回復批註有時會導致 Word 停滯的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1794">We fixed an issue where replying to a comment in a co-authored session could sometimes cause Word to freeze.</span></span>

- <span data-ttu-id="224d0-1795">我們已修正在含有一百個以上專案的檔中插入或更新索引會導致應用程式當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1795">We fixed an issue where inserting or updating an Index in a document containing more than a hundred entries would result in the application crashing.</span></span>

- <span data-ttu-id="224d0-1796">我們已修正啟用原則 Word 2007 及更新版本的二進位檔案和範本會導致部分共同撰寫案例失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1796">We fixed an issue where enabling policy Word 2007 and later Binary Documents and Templates would cause some co-authoring cases to fail.</span></span>

- <span data-ttu-id="224d0-1797">我們已修正具有自訂 xml 值的檔案在開啟時速度極度緩慢的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1797">We fixed an issue where files with custom xml values opened extremely slowly.</span></span>

- <span data-ttu-id="224d0-1798">我們已修正使用長路徑名稱 (大於32K) 的檔案無法開啟，且未顯示適當的錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1798">We fixed an issue where files with long path names (greater than 32K) would not open and an appropriate error message was not being displayed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="224d0-1799">Office 套件</span><span class="sxs-lookup"><span data-stu-id="224d0-1799">Office Suite</span></span>

- <span data-ttu-id="224d0-1800">我們已經研究並解決了在作業系統關閉後，透過 InTune 進行的 Office 365 專業增強版部署會暫停的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1800">We have investigated and resolved the issue where an Office 365 ProPlus deployment via InTune is paused after an OS shutdown.</span></span>

- <span data-ttu-id="224d0-1801">我們已修正 Microsoft Office 的 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。</span><span class="sxs-lookup"><span data-stu-id="224d0-1801">We fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="224d0-1802">此更新解決了 Microsoft Office 中的一個問題：可能無法在執行時期正確找到 Visual Basic for Applications 專案，這些專案的參照預期透搜尋 PATH 環境變數指定的位置來找到，進而導致VBA 執行時期錯誤。</span><span class="sxs-lookup"><span data-stu-id="224d0-1802">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-june-08"></a><span data-ttu-id="224d0-1804">版本 2005：6 月 08 日</span><span class="sxs-lookup"><span data-stu-id="224d0-1804">Version 2005: June 08</span></span>
<span data-ttu-id="224d0-1805">*版本 2005 (組建 12827.20336)*</span><span class="sxs-lookup"><span data-stu-id="224d0-1805">*Version 2005 (Build 12827.20336)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-1807">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-1807">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="224d0-1808">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-1808">PowerPoint</span></span>

- <span data-ttu-id="224d0-1809">我們已修正取代字型對話方塊中，取代字型下拉清單只會顯示系統中安裝的字型，而不是所安裝的字型的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1809">We have fixed an issue with replace fonts dialog where replace font dropdown only shows fonts within the presentation instead of fonts installed on the system.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-june-04"></a><span data-ttu-id="224d0-1811">版本 2005：6 月 04 日</span><span class="sxs-lookup"><span data-stu-id="224d0-1811">Version 2005: June 04</span></span>
<span data-ttu-id="224d0-1812">*版本 2005 (組建 12827.20320)*</span><span class="sxs-lookup"><span data-stu-id="224d0-1812">*Version 2005 (Build 12827.20320)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-1814">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-1814">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="224d0-1815">Access</span><span class="sxs-lookup"><span data-stu-id="224d0-1815">Access</span></span>

- <span data-ttu-id="224d0-1816">**隨時跟上改變！[日期/時間] 延伸資料類型具有更好的精確度。：** 引進新的和改良的資料類型。</span><span class="sxs-lookup"><span data-stu-id="224d0-1816">**Keep up with the times! The Date/Time Extended data type has better precision.:** Introducing a new and improved data type.</span></span>  <span data-ttu-id="224d0-1817">為加強與 SQL 的語法相容性，並提高包含日期和時間之記錄的詳細資料和層級，我們正在將 DateTime2 資料類型實施到 Access 中。</span><span class="sxs-lookup"><span data-stu-id="224d0-1817">To enhance syntax compatibility with SQL, and to increase accuracy and level of detail in records that include dates and times, we’re implementing the DateTime2 data type into Access.</span></span> <span data-ttu-id="224d0-1818">這個額外的日期與時間資料類型，將會包含更大的日期範圍 (0001-01-01 到 9999-12-31) ，具有更高的指定時間精準度(以納秒取代秒為單位)，讓您可以提供和執行計算。</span><span class="sxs-lookup"><span data-stu-id="224d0-1818">This additional date & time data type will include a larger date range (0001-01-01 through 9999-12-31), with higher-specified time precision (nanoseconds, rather than seconds) that you will be able to provide and perform calculations on.</span></span> <span data-ttu-id="224d0-1819">若要啟用，請選取 [新增欄位] > [日期與時間延長]。</span><span class="sxs-lookup"><span data-stu-id="224d0-1819">To enable, select New field > Date & Time Extended.</span></span> [<span data-ttu-id="224d0-1820">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-1820">Learn more</span></span>](https://support.office.com/article/708c32da-a052-4cc2-9850-9851042e0024)

### <a name="excel"></a><span data-ttu-id="224d0-1821">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-1821">Excel</span></span>

- <span data-ttu-id="224d0-1822">**在 Excel 中建立來自 Power BI 資料的樞紐分析表：** 您可以在 Excel 中建立樞紐分析表，只要按幾下滑鼠，就能連線到儲存在 Power BI 的樞紐分析表。</span><span class="sxs-lookup"><span data-stu-id="224d0-1822">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="224d0-1823"> 如此一來，您就能獲得樞紐分析表和 Power BI 的最佳效果。</span><span class="sxs-lookup"><span data-stu-id="224d0-1823">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="224d0-1824">使用安全 Power BI 資料集的樞紐分析表以計算、摘要及分析資料。</span><span class="sxs-lookup"><span data-stu-id="224d0-1824">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span>

### <a name="outlook"></a><span data-ttu-id="224d0-1825">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1825">Outlook</span></span>

- <span data-ttu-id="224d0-1826">**可讓您從上一個 Outlook 會話中快速重新開啟專案的選項：** 我們新增了一個可快速重新開啟先前 Outlook 會話專案的選項。</span><span class="sxs-lookup"><span data-stu-id="224d0-1826">**Option to quickly reopen items from previous Outlook session:** We added an option to quickly reopen items from a previous Outlook session.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-1829">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-1829">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="224d0-1830">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-1830">PowerPoint</span></span>

- <span data-ttu-id="224d0-1831">這可修正使用者在同一檔案中同時有新版和舊版批註，因此觸發批註的升級而當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1831">This fixes a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>


### <a name="office-suite"></a><span data-ttu-id="224d0-1832">Office 套件</span><span class="sxs-lookup"><span data-stu-id="224d0-1832">Office Suite</span></span>

- <span data-ttu-id="224d0-1833">我們透過設定Bing附加預設安裝驗證設定為true默認，並將MSI返回成功視為安裝成功，而解決了 ValidateInstall 失敗率問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1833">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-may-29"></a><span data-ttu-id="224d0-1835">版本 2005：5 月 29 日</span><span class="sxs-lookup"><span data-stu-id="224d0-1835">Version 2005: May 29</span></span>
<span data-ttu-id="224d0-1836">*版本2005（組建12827.20268）*</span><span class="sxs-lookup"><span data-stu-id="224d0-1836">*Version 2005 (Build 12827.20268)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-1838">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-1838">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="224d0-1839">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-1839">Excel</span></span>

- <span data-ttu-id="224d0-1840">**工作表視圖：** 排序/篩選，同時與其他人在 Excel 電腦版共同作業。</span><span class="sxs-lookup"><span data-stu-id="224d0-1840">**Sheet View:** Sort/filter while collaborating with others in Excel desktop.</span></span>

### <a name="outlook"></a><span data-ttu-id="224d0-1841">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1841">Outlook</span></span>

- <span data-ttu-id="224d0-1842">**新增至 Outlook 快顯通知的其他按鈕：** [快速動作] 按鈕，現在會於在 Windows 10 上執行 Outlook 時顯示在 Outlook 快顯通知中。</span><span class="sxs-lookup"><span data-stu-id="224d0-1842">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-1845">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-1845">Resolved issues</span></span>



### <a name="outlook"></a><span data-ttu-id="224d0-1846">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1846">Outlook</span></span>

- <span data-ttu-id="224d0-1847">解決了導致 Windows 10 伺服器版本的使用者看到警告防毒軟體狀態：無效的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1847">Addressed an issue that caused users of Windows 10 server versions to see the warning  Antivirus status: Invalid.</span></span> <span data-ttu-id="224d0-1848">這個版本的 Windows 支援防毒軟體檢測，但即使已正確安裝防毒軟體，也無法找到防毒軟體。</span><span class="sxs-lookup"><span data-stu-id="224d0-1848">This version of Windows supports antivirus detection, but no antivirus was found despite having anti virus correctly installed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="224d0-1849">Office 套件</span><span class="sxs-lookup"><span data-stu-id="224d0-1849">Office Suite</span></span>

- <span data-ttu-id="224d0-p212">當登錄機碼 HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth 設為零，且正在啟用增益集時，Office 主機會在 Windows 中當機。此變更可修正此問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-p212">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero. This change would fix this issue.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-may-21"></a><span data-ttu-id="224d0-1853">版本 2005：5 月 21 日</span><span class="sxs-lookup"><span data-stu-id="224d0-1853">Version 2005: May 21</span></span>
<span data-ttu-id="224d0-1854">*版本 2005 (組建 12827.20210)*</span><span class="sxs-lookup"><span data-stu-id="224d0-1854">*Version 2005 (Build 12827.20210)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)




[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-1858">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-1858">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-1859">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-1859">Excel</span></span>

- <span data-ttu-id="224d0-1860">修正當 Excel 視窗透過 Teams 共用時，使用 Ctrl + Shift + 方向鍵滑動後，Excel 可能會無法回應的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1860">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>


- <span data-ttu-id="224d0-1861">在某些情況下，按一下同一個活頁簿中某個位置的超連結會導致活頁簿被隱藏。</span><span class="sxs-lookup"><span data-stu-id="224d0-1861">In some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>


### <a name="outlook"></a><span data-ttu-id="224d0-1862">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1862">Outlook</span></span>

- <span data-ttu-id="224d0-1863">已解決有回應/轉寄標註的clp審查活動的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1863">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>


- <span data-ttu-id="224d0-1864">已解決在從系統管理人通知中提交意見反應時，使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1864">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-may-14"></a><span data-ttu-id="224d0-1866">版本 2005：5 月 14 日</span><span class="sxs-lookup"><span data-stu-id="224d0-1866">Version 2005: May 14</span></span>
<span data-ttu-id="224d0-1867">*版本 2005 (組建 12827.20160)*</span><span class="sxs-lookup"><span data-stu-id="224d0-1867">*Version 2005 (Build 12827.20160)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-1869">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-1869">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-1870">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-1870">Excel</span></span>

- <span data-ttu-id="224d0-1871">**[自動套用] 或 [建議敏感度] 標籤：** Office 可以根據偵測到的敏感性內容來推薦或自動套用靈敏度標籤。</span><span class="sxs-lookup"><span data-stu-id="224d0-1871">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="224d0-1872">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-1872">PowerPoint</span></span>

- <span data-ttu-id="224d0-1873">**不需要簡報導覽裝置：有耳塞式耳機就夠了：** 使用您的 Surface Earbuds 控制 PowerPoint 簡報。</span><span class="sxs-lookup"><span data-stu-id="224d0-1873">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="224d0-1874">重要：您必須在 Windows 10 的 Surface 音訊應用程式中配對 Surface Earbuds，才能使用手勢來控制簡報。</span><span class="sxs-lookup"><span data-stu-id="224d0-1874">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="224d0-1875">在此取得 Windows 10 上 Surface 音訊應用程式入門的指示。</span><span class="sxs-lookup"><span data-stu-id="224d0-1875">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="224d0-1876">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-1876">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

- <span data-ttu-id="224d0-1877">**[自動套用] 或 [建議敏感度] 標籤：** Office 可以根據偵測到的敏感性內容來推薦或自動套用靈敏度標籤。</span><span class="sxs-lookup"><span data-stu-id="224d0-1877">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="word"></a><span data-ttu-id="224d0-1878">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-1878">Word</span></span>

- <span data-ttu-id="224d0-1879">**[自動套用] 或 [建議敏感度] 標籤：** Office 可以根據偵測到的敏感性內容來推薦或自動套用靈敏度標籤。</span><span class="sxs-lookup"><span data-stu-id="224d0-1879">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-1882">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-1882">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="224d0-1883">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-1883">Excel</span></span>

- <span data-ttu-id="224d0-1884">已增加搭配圖表使用的 [自訂誤差線] 對話方塊上儲存格參照 [編輯] 控制項的大小。</span><span class="sxs-lookup"><span data-stu-id="224d0-1884">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>

- <span data-ttu-id="224d0-1885">修正圖表資料表無法正確呈現日期座標軸中的值的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1885">Fixed an issue where chart data table could render values in a date axis incorrectly.</span></span>

- <span data-ttu-id="224d0-1886">修正使用 [頁面配置] 或 [分頁預覽] 之後無法停用分頁符號的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1886">Fixed an issue where page breaks could not be disabled after going into Page Layout or Page Break Preview.</span></span>

- <span data-ttu-id="224d0-1887">修正隱藏和取消隱藏具有系列資料的欄之後，圖表線條樣式可能會遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1887">Fixed an issue where chart line styles could be lost after hiding and unhiding columns with series data.</span></span>

- <span data-ttu-id="224d0-1888">修正在已篩選清單中插入欄的時間會比預期更長的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1888">Fixed an issue where inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="224d0-1889">修正列印時表單控制項的核取方塊縮放的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1889">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="224d0-1890">修正當檔案路徑太長時，在檔案重新開啟之後外部連結會停止運作的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1890">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="224d0-1891">在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。</span><span class="sxs-lookup"><span data-stu-id="224d0-1891">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="224d0-1892">在某些情況下，Application.Evaluate (VBA) 無法在使用者定義的函式中運作。</span><span class="sxs-lookup"><span data-stu-id="224d0-1892">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="224d0-1893">在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。</span><span class="sxs-lookup"><span data-stu-id="224d0-1893">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="224d0-1894">此變更會修正設定格式化的條件 (CF) 資訊無法正確儲存到 XLSB 檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1894">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

- <span data-ttu-id="224d0-1895">這項變更修正了即使 LINEST 函式傳回正確的值，圖表趨勢線的 R 平方值 (在強制 y 截距的情況下) 仍然不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1895">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>

- <span data-ttu-id="224d0-1896">此變更修正了自訂圖表趨勢線格式不一定會儲存的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1896">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

- <span data-ttu-id="224d0-1897">當您使用舊版的「共用活頁簿」模式，嘗試為活頁簿的新工作表列出變更時，就會發生當機。</span><span class="sxs-lookup"><span data-stu-id="224d0-1897">A crash could occur when trying to list changes on a new sheet for a workbook using legacy"Shared Workbook" mode.</span></span>

- <span data-ttu-id="224d0-1898">修正啟用 [負值以補色顯示] 選項後，可能無法儲存樞紐分析表中的自訂格式設定的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1898">Fixed the issue where custom formatting in Pivot charts may not be saved when the "Invert if negative" option was enabled.</span></span>

- <span data-ttu-id="224d0-1899">修正如果選取 [負值以補色顯示] 選項，可能無法儲存樞紐分析表中單一資料點的自訂格式設定的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1899">Fixed an issue where custom formatting for a single data point in a Pivot chart was not saved if the "Invert if negative" option was selected.</span></span>

- <span data-ttu-id="224d0-1900">這項變更修正在 CSV 檔案中上傳 '@' 字元時，會導致將 '@' 字元之後的字串轉換成公式的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1900">This change fixes an issue where the '@' character uploaded in a CSV file, would result in the string after the '@' character to be converted to a formula.</span></span>

- <span data-ttu-id="224d0-1901">修正無法正確捨入 SEQUENCE 函數中十進位值的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1901">Fixed an issue where decimal values in the SEQUENCE function were not rounded correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="224d0-1902">OneNote</span><span class="sxs-lookup"><span data-stu-id="224d0-1902">OneNote</span></span>

- <span data-ttu-id="224d0-1903">修正將分行符號儲存為垂直 Tab 的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1903">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="224d0-1904">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1904">Outlook</span></span>

- <span data-ttu-id="224d0-1905">解決會導致使用者無法將個人連絡人群組新增為會議出席者的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1905">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>

- <span data-ttu-id="224d0-1906">修正 Office 功能區中群組行事曆分類按鈕已停用的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1906">Fixed an issue where the categorize button for group calendars in the Office Ribbon was disabled.</span></span>

- <span data-ttu-id="224d0-1907">已解決在 Windows 更新後，開啟儲存在本機的 msg 或 .oft 檔案會導致 Outlook 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1907">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="224d0-1908">修正企業客戶沒有執行或無法使用群組資料夾的問題，該問題會導致 Outlook 顯示「沒有回應」的訊息。</span><span class="sxs-lookup"><span data-stu-id="224d0-1908">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

- <span data-ttu-id="224d0-1909">已解決導致使用者在 Outlook 桌面用戶端中按一下非常長的安全連結時，由於截斷而無法載入的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1909">Addressed an issue that caused very long safelinks that users clicked on in the Outlook Desktop client to fail to load due to truncation.</span></span>

- <span data-ttu-id="224d0-1910">修正當與伺服器同步處理時，名稱中包含 DBCS (雙位元組字元集) 字元的 Outlook 資料夾會間斷消失的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1910">Fixed an issue where Outlook folders with names containing DBCS (Double Byte Character Set) characters would intermittently disappear when synchronizing with the server.</span></span> <span data-ttu-id="224d0-1911">為此，必須為 Outlook 設定 IMAP 帳戶，並在地區設定設定為日文的系統上執行。</span><span class="sxs-lookup"><span data-stu-id="224d0-1911">For this to happen, Outlook had to be configured with an IMAP account and running on a system with the locale set to Japanese.</span></span>

- <span data-ttu-id="224d0-1912">已解決會導致為使用者主要信箱以外的信箱所建立的刪除規則變得無效的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1912">Addressed an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>

- <span data-ttu-id="224d0-1913">已解決在轉寄加密郵件時導致捨棄附件的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1913">Addressed an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

- <span data-ttu-id="224d0-1914">已解決會導致還有 2 個月時間的會議，無法在排程小幫手中顯示會議主題的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1914">Addressed an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>

- <span data-ttu-id="224d0-1915">已解決會導致使用者在轉寄大型 HTML 郵件時，看到郵件內文截斷的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1915">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="224d0-1916">新增透過群組原則強制執行 S/MIME 預設登入設定的功能。</span><span class="sxs-lookup"><span data-stu-id="224d0-1916">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="224d0-1917">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-1917">PowerPoint</span></span>

- <span data-ttu-id="224d0-1918">已修正問題：如果使用者建立了註解，但未張貼就關閉 [註解] 窗格，然後開啟新視窗、瀏覽多張投影片並關閉視窗，最後再開啟原始簡報中的 [註解] 窗格，將導致無法使用草稿註解。</span><span class="sxs-lookup"><span data-stu-id="224d0-1918">Fixed an issue where if a user created a comment without posting it and closed the Comments pane, then opened a new window, navigated through multiple slides and, closed the window, and finally re-opened the Comments pane in the original presentation, the draft comments would not be available.</span></span>

- <span data-ttu-id="224d0-1919">修正了將滑鼠游標移到星號 (\*) 符號，但不會顯示上一次更新文件的日期和使用者姓名。</span><span class="sxs-lookup"><span data-stu-id="224d0-1919">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="project"></a><span data-ttu-id="224d0-1920">Project</span><span class="sxs-lookup"><span data-stu-id="224d0-1920">Project</span></span>

- <span data-ttu-id="224d0-1921">在表單檢視中編輯前置/後續任務資料時，會觸發額外的 ProjectBeforeTaskChange 事件。</span><span class="sxs-lookup"><span data-stu-id="224d0-1921">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="224d0-1922">修正變更連結至 SharePoint 工作清單之專案的面板狀態欄位時，Project 可能當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1922">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>

- <span data-ttu-id="224d0-1923">修正儲存使用舊版 Project 建立的專案時，Project 可能當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1923">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="224d0-1924">修正如果 Project 連線至 Project Web App，且小數分隔符號是逗號，當新增延遲時，TaskDependencies Add 方法會失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1924">Fixed an issue where if Project is connected to Project Web App and the decimal separator is a comma, TaskDependencies Add method fails when Lag is added.</span></span>


### <a name="word"></a><span data-ttu-id="224d0-1925">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-1925">Word</span></span>

- <span data-ttu-id="224d0-1926">修正在 [共同作業] 模式時，在文件中插入註解並不總是成功的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1926">Fixed an issue where inserting comments on a document in collaboration mode would not always work.</span></span>

- <span data-ttu-id="224d0-1927">此變更修正在按一下 @ 提及時，[人員卡片] 會閃動的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1927">This change fixes an issue where the People card would flash if the @ mention was clicked.</span></span>

- <span data-ttu-id="224d0-p215">啟用 [顯示書籤] 選項不會顯示書籤。已修正此問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-p215">Enabling the option "Show bookmarks" would not display bookmarks. This has been fixed.</span></span>

- <span data-ttu-id="224d0-p216">修正在關閉具有草稿註解的文件時，會提示使用者是否要在未儲存草稿註解的情況下關閉文件的問題。取消該提示會關閉文件，而非讓文件保持開啟。</span><span class="sxs-lookup"><span data-stu-id="224d0-p216">Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments. Cancelling the prompt would close the document rather than leaving it open.</span></span>

- <span data-ttu-id="224d0-1932">我們已修正複製及貼上標題的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1932">We fixed an issue in copying and pasting headings.</span></span>

- <span data-ttu-id="224d0-1933">修正翻譯已張貼註解將導致「插入已翻譯的文字失敗」錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1933">Fixed an issue where translating a posted comment would result in the error 'Inserting translated text failed'.</span></span>

- <span data-ttu-id="224d0-1934">此變更修正了下列問題：如果已啟用 [顯示功能變數代碼，而非其值] 選項，則含有超連結的文字可能不會顯示。</span><span class="sxs-lookup"><span data-stu-id="224d0-1934">This change fixes an issue where text with hyperlinks may not display if the option: "Show field codes instead of their values" was enabled.</span></span>

- <span data-ttu-id="224d0-p217">在 Web 檢視/沉浸式閱讀程式中，即使是在檢視中，按一下提示也會捲動到最上方。已修正此問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-p217">In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view. This has been fixed.</span></span>

- <span data-ttu-id="224d0-1937">我們已修正一個問題，當嘗試使用新名稱儲存包含巨集的檔案時，無論使用者輸入什麼名稱，都會導致該檔案以.docx 副檔名和檔案名稱 WRO0004.docx 儲存，進而導致文件無法使用。</span><span class="sxs-lookup"><span data-stu-id="224d0-1937">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with .docx extension and the filename WRO0004.docx, regardless of what the user entered, rendering the document unusable.</span></span>

### <a name="office-suite"></a><span data-ttu-id="224d0-1938">Office 套件</span><span class="sxs-lookup"><span data-stu-id="224d0-1938">Office Suite</span></span>

- <span data-ttu-id="224d0-1939">當使用者收到將他們移至 Teams Only 的原則時，他們仍然可以使用商務版 Skype Outlook 增益集來排程會議。</span><span class="sxs-lookup"><span data-stu-id="224d0-1939">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span>  <span data-ttu-id="224d0-1940">在此更新之後，當客戶端讀取指示用戶為 Teams Only 的策略並進入僅限會議加入模式後，您將不再能用商務版 Skype 安排會議。</span><span class="sxs-lookup"><span data-stu-id="224d0-1940">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span>  <span data-ttu-id="224d0-1941">此外，如果商務版 Skype Outlook 增益集發現商務版 Skype 用戶端處於 [僅限會議加入] 模式，就無法自行啟動。</span><span class="sxs-lookup"><span data-stu-id="224d0-1941">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="224d0-1942">此更新解決了 Microsoft Office 中的一個問題：可能無法在執行時期正確找到 Visual Basic for Applications 專案，這些專案的參照預期透搜尋 PATH 環境變數指定的位置來找到，進而導致VBA 執行時期錯誤。</span><span class="sxs-lookup"><span data-stu-id="224d0-1942">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="224d0-1943">此更新修正了 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。</span><span class="sxs-lookup"><span data-stu-id="224d0-1943">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-may-11"></a><span data-ttu-id="224d0-1945">版本 2004：5 月 11 日</span><span class="sxs-lookup"><span data-stu-id="224d0-1945">Version 2004: May 11</span></span>
<span data-ttu-id="224d0-1946">*版本 2004 (組建 12730.20270)*</span><span class="sxs-lookup"><span data-stu-id="224d0-1946">*Version 2004 (Build 12730.20270)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-1948">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-1948">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-1949">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-1949">Excel</span></span>

- <span data-ttu-id="224d0-1950">**使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦。</span><span class="sxs-lookup"><span data-stu-id="224d0-1950">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="outlook"></a><span data-ttu-id="224d0-1951">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1951">Outlook</span></span>

- <span data-ttu-id="224d0-1952">**電子郵件中的改良連結：** 當您包含檔案的連結時，檔案名會取代 URL。</span><span class="sxs-lookup"><span data-stu-id="224d0-1952">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="224d0-1953">您可以變更權限，讓所有收件者都能存取。</span><span class="sxs-lookup"><span data-stu-id="224d0-1953">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="224d0-1954">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-1954">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)<br /><span data-ttu-id="224d0-1955">在[部落格文章](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="224d0-1955">See details in [blog post](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span></span>

- <span data-ttu-id="224d0-1956">**使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦。</span><span class="sxs-lookup"><span data-stu-id="224d0-1956">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="224d0-1957">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-1957">PowerPoint</span></span>

- <span data-ttu-id="224d0-p220">**使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦。[深入了解](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)</span><span class="sxs-lookup"><span data-stu-id="224d0-p220">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.  [Learn more](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)</span></span>

### <a name="word"></a><span data-ttu-id="224d0-1960">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-1960">Word</span></span>

- <span data-ttu-id="224d0-1961">**使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦。</span><span class="sxs-lookup"><span data-stu-id="224d0-1961">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-1964">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-1964">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-1965">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1965">Outlook</span></span>

- <span data-ttu-id="224d0-1966">解決在顯示快顯通知時，使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1966">Addressed an issue that caused users to experience a crash when displaying toast notifications.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-may-04"></a><span data-ttu-id="224d0-1968">版本 2004：5 月 4 日</span><span class="sxs-lookup"><span data-stu-id="224d0-1968">Version 2004: May 04</span></span>
<span data-ttu-id="224d0-1969">*版本 2004 (組建 12730.20250)*</span><span class="sxs-lookup"><span data-stu-id="224d0-1969">*Version 2004 (Build 12730.20250)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-1971">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-1971">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-1972">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1972">Outlook</span></span>

- <span data-ttu-id="224d0-1973">**更好的結果—瞬間：** 我們更新了搜尋體驗，讓這個版本比以往更聰明、更快速，且更可靠。</span><span class="sxs-lookup"><span data-stu-id="224d0-1973">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="224d0-1974">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-1974">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="224d0-1975">**IT 系統管理員的事件通知：** Microsoft 365 租用戶全域系統管理員和 Office 應用程式系統會在 Windows 版 Outlook 的新右側面板中收到影響其使用者的 Outlook 和 O365 Exchange 事件通知。</span><span class="sxs-lookup"><span data-stu-id="224d0-1975">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="224d0-1976">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-1976">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-1979">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-1979">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="224d0-1980">Office 套件</span><span class="sxs-lookup"><span data-stu-id="224d0-1980">Office Suite</span></span>

- <span data-ttu-id="224d0-1981">此更新修正了 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。</span><span class="sxs-lookup"><span data-stu-id="224d0-1981">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-april-29"></a><span data-ttu-id="224d0-1983">版本 2004：4 月 29 日</span><span class="sxs-lookup"><span data-stu-id="224d0-1983">Version 2004: April 29</span></span>
<span data-ttu-id="224d0-1984">*版本 2004 (組建 12730.20236)*</span><span class="sxs-lookup"><span data-stu-id="224d0-1984">*Version 2004 (Build 12730.20236)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-1986">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-1986">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-1987">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1987">Outlook</span></span>

- <span data-ttu-id="224d0-1988">**協助保護群組中的資料：** 建立群組時所選擇的「敏感度」標籤會套用到群組電子郵件、文件及小組網站。</span><span class="sxs-lookup"><span data-stu-id="224d0-1988">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-1991">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-1991">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-1992">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1992">Outlook</span></span>

- <span data-ttu-id="224d0-1993">解決導致 Outlook 在某些 Windows 組建上當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-1993">Addresses an issue that caused Outlook to crash on some builds of Windows.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-april-25"></a><span data-ttu-id="224d0-1995">版本 2004：4 月 25 日</span><span class="sxs-lookup"><span data-stu-id="224d0-1995">Version 2004: April 25</span></span>
<span data-ttu-id="224d0-1996">*版本 2004 (組建 12730.20206)*</span><span class="sxs-lookup"><span data-stu-id="224d0-1996">*Version 2004 (Build 12730.20206)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-1998">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-1998">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-1999">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-1999">Outlook</span></span>

- <span data-ttu-id="224d0-2000">已解決在 Windows 更新後，開啟儲存在本機的 msg 或 .oft 檔案會導致 Outlook 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2000">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

### <a name="project"></a><span data-ttu-id="224d0-2001">Project</span><span class="sxs-lookup"><span data-stu-id="224d0-2001">Project</span></span>

- <span data-ttu-id="224d0-2002">修正如果您使用的是連線至 Project Web App 的 Project，且小數分隔符號是逗號，當您嘗試將延遲新增至相依性時，TaskDependencies Add 方法會失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2002">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>


### <a name="office-suite"></a><span data-ttu-id="224d0-2003">Office 套件</span><span class="sxs-lookup"><span data-stu-id="224d0-2003">Office Suite</span></span>

- <span data-ttu-id="224d0-2004">此修正可解決同時防止限制存取和保護設有密碼之檔案的錯誤。</span><span class="sxs-lookup"><span data-stu-id="224d0-2004">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-april-21"></a><span data-ttu-id="224d0-2006">版本 2004：4 月 21 日</span><span class="sxs-lookup"><span data-stu-id="224d0-2006">Version 2004: April 21</span></span>
<span data-ttu-id="224d0-2007">版本 2004 (組建 12730.20182)</span><span class="sxs-lookup"><span data-stu-id="224d0-2007">*Version 2004 (Build 12730.20182)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-2009">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-2009">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-2010">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-2010">Outlook</span></span>

- <span data-ttu-id="224d0-2011">解決導致資料夾窗格寬度意外變更的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2011">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="224d0-2012">解決導致使用者在退出 Outlook 時遇到掛斷的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2012">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-april-15"></a><span data-ttu-id="224d0-2014">版本 2004：4 月 15 日</span><span class="sxs-lookup"><span data-stu-id="224d0-2014">Version 2004: April 15</span></span>
<span data-ttu-id="224d0-2015">*版本 2004 (組建 12730.20150)*</span><span class="sxs-lookup"><span data-stu-id="224d0-2015">*Version 2004 (Build 12730.20150)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-2017">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-2017">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-2018">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-2018">Excel</span></span>

- <span data-ttu-id="224d0-2019">**Facebook 連接器支援即將結束：** 於 2020 年 4 月起，Excel 就不再支援使用 Facebook 連接器的外部資料連線。</span><span class="sxs-lookup"><span data-stu-id="224d0-2019">**Facebook connector support is ending:** Starting in April 2020, Excel will no longer support external data connections that use the Facebook connector.</span></span>

### <a name="outlook"></a><span data-ttu-id="224d0-2020">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-2020">Outlook</span></span>

- <span data-ttu-id="224d0-2021">**在 Outlook 中撰寫郵件時有新的選項可停用 @ 提及建議：** 您是否覺得 @ 提及的選擇器很煩人，一點都不好用？</span><span class="sxs-lookup"><span data-stu-id="224d0-2021">**New option to disable @ mention suggestions when composing mail in Outlook:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="224d0-2022">現在您可以視需要將其關閉了。</span><span class="sxs-lookup"><span data-stu-id="224d0-2022">Now you can turn it off if you prefer.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="224d0-2023">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-2023">PowerPoint</span></span>

- <span data-ttu-id="224d0-2024">**在簡報時同步處理變更：** 即使簡報處於投影片放映模式，仍可即時同步處理所做的變更。</span><span class="sxs-lookup"><span data-stu-id="224d0-2024">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="224d0-2025">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-2025">Word</span></span>

- <span data-ttu-id="224d0-2026">**標註私人複本：** 製作共用文件的私人複本，以建立只有您本人能夠看到的手寫筆記。</span><span class="sxs-lookup"><span data-stu-id="224d0-2026">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="224d0-2027">若要開始使用，請移至 [檢視] > [建立私人複本]。</span><span class="sxs-lookup"><span data-stu-id="224d0-2027">Go to View > Create a Private Copy to get started.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-2030">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-2030">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="224d0-2031">Access</span><span class="sxs-lookup"><span data-stu-id="224d0-2031">Access</span></span>

- <span data-ttu-id="224d0-2032">修正工作窗格中表格的重新調整及重新整理問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2032">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

- <span data-ttu-id="224d0-2033">修正國際版 Access 在使用者介面中顯示英文字串的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2033">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="224d0-2034">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-2034">Excel</span></span>

- <span data-ttu-id="224d0-2035">修正在工作表上選取儲存格範圍會導致只選取單一儲存格的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2035">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="224d0-2036">在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。</span><span class="sxs-lookup"><span data-stu-id="224d0-2036">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="224d0-2037">修正在複製含有樞紐分析表的工作表後，會於某些情況下導致 Excel 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2037">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="224d0-2038">在某些情況下，Application.Evaluate (VBA) 無法在使用者定義的函式中運作。</span><span class="sxs-lookup"><span data-stu-id="224d0-2038">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="224d0-2039">修正使用者在以程式設計方式編輯大量儲存格範圍時可能遇到的效能問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2039">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>

- <span data-ttu-id="224d0-2040">修正以日文環境開啟 CSV 檔案時發生的效能問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2040">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

- <span data-ttu-id="224d0-2041">修正插入使用者定義的圖表範本來作為預設值會導致其儲存為直條圖的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2041">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="224d0-2042">修正當基礎資料儲存格沒有標題時，圖表上的資料標籤會以空白顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2042">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="224d0-2043">修正在為含有 X 軸範圍的圖表縮減大小時，可能會導致 Excel 停止回應的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2043">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="224d0-2044">修正已啟用 R1C1 儲存格參照且正在共同撰寫/共用的 Excel 工作表，在將游標移到 [使用者目前狀態] 圖示上方時不會以 R1C1 模式顯示作用中儲存格的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2044">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

- <span data-ttu-id="224d0-2045">此變更解決了處理格式錯誤或無效通訊協定資訊影像時所導致的延遲問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2045">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="224d0-2046">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-2046">Outlook</span></span>

- <span data-ttu-id="224d0-2047">此變更解決了處理格式錯誤或無效通訊協定資訊影像時所導致的延遲問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2047">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="224d0-2048">此變更修正了電子郵件草稿最新變更未更新的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2048">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="224d0-2049">已修正在檔案上按一下滑鼠右鍵並使用「傳送到」功能無法運作的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2049">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="224d0-2050">已解決會導致代理人在不同機器上所看到的共用信箱有不同資料夾階層的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2050">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="224d0-2051">已解決會導致類別有時候會從電子郵件訊息中消失的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2051">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="224d0-2052">已解決在變更機器上的時區時，會導致某些提醒無法觸發的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2052">Addressed an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

- <span data-ttu-id="224d0-2053">已解決在嘗試檢視組織表單的屬性時，會導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2053">Addressed an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="224d0-2054">已修正如果使用者有自訂的 [通訊錄] 搜尋路徑，則 Outlook 的名稱解析範圍會限制為自訂路徑，而不是包括全域通訊清單 (GAL) 的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2054">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="224d0-2055">解決了會讓 [附件工具] 中的 [儲存至雲端] 按鈕不見的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2055">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="224d0-2056">解決了以下問題：當使用者從檢查程式視窗回覆受到數位版權管理的郵件，卻沒有所回覆郵件的擁有者權限時，使用者會無法新增簽名。</span><span class="sxs-lookup"><span data-stu-id="224d0-2056">Addressed an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>

- <span data-ttu-id="224d0-2057">解決了以下問題：使用者無法從網頁位置將其他附件新增到先前建立的會議。</span><span class="sxs-lookup"><span data-stu-id="224d0-2057">Addressed an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

- <span data-ttu-id="224d0-2058">解決將附件新增至郵件或從郵件拖放 (與透過功能表相對) 來儲存附件時，導致檔案的「上次修改」日期更新的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2058">Addressed an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

- <span data-ttu-id="224d0-2059">解決會導致在展開的尋找窗格中按一下 Enter 時無法開始搜尋，而是會要求使用者按一下 [搜尋] 按鈕的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2059">Addressed an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>

- <span data-ttu-id="224d0-2060">已修正在一組傳回的搜尋結果中，依類別結果排序不會顯示類別色彩的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2060">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

- <span data-ttu-id="224d0-2061">修正將 [如果有，顯示使用者的照片] 選項停用時，搜尋不會顯示有關使用者的任何資訊的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2061">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="224d0-2062">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-2062">PowerPoint</span></span>

- <span data-ttu-id="224d0-2063">此變更修正了會導致包含 emojis 的 PowerPoint 檔案在儲存時發生失敗的錯誤。</span><span class="sxs-lookup"><span data-stu-id="224d0-2063">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

- <span data-ttu-id="224d0-2064">此變更修正了在 PowerPoint 或 Word 中呈現內嵌為 OLE 物件的舊版 Excel 圖表時可能不會永遠顯示圖表標題的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2064">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="224d0-2065">我們已修正將文字從 Excel 複製到 PowerPoint 時可能會導致其格式設定發生變更的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2065">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="224d0-2066">此變更修正了使用 [全字拼寫須相符] 來尋找特殊字元時，不一定能正常運作的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2066">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="224d0-2067">Project</span><span class="sxs-lookup"><span data-stu-id="224d0-2067">Project</span></span>

- <span data-ttu-id="224d0-2068">修正無法正確計算摘要工作日期的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2068">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="224d0-2069">修正不先執行 OpenUndoTransaction 方法就不能觸發 OnUndoOrRedo 事件的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2069">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="224d0-2070">修正當使用者按一下 [排程群組] 內 [工作] 功能區中的 [停用] 按鈕時，不會觸發 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) 事件的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2070">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the “Inactivate” button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="224d0-2071">如果您在 [表單類型] 檢視中設定前置任務或後置任務詳細資訊，則 ProjectBeforeTaskChange Visual Basic Applications (VBA) 事件不會一律擷取變更。</span><span class="sxs-lookup"><span data-stu-id="224d0-2071">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="224d0-2072">例如，如果刪除了某個相依性，並在表單上按一下 [確定]，則不會觸發該事件。</span><span class="sxs-lookup"><span data-stu-id="224d0-2072">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="224d0-2073">修正此問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2073">This behavior has been fixed.</span></span>

- <span data-ttu-id="224d0-2074">修正在進行變更 (例如日期變更) 之後，實際工作成本 (ACWP) 的最新值不會顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2074">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="224d0-2075">修正使用「最近使用」(MRU) 功能表開啟專案時，會使用 [讀取/寫入] 存取權開啟專案的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2075">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="224d0-2076">這項變更修正了如果您建立包含開始日期和時間 (但無工期) 的手動工作，則時間表上的時間顯示不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2076">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="224d0-2077">修正使用回曆列印時間表時，會導致列印檢視中略過或重複一個月的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2077">Fixed an issue where printing a timeline using a Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="224d0-2078">這項變更解決了在團隊規劃中使用 GDI 物件時，可能導致 GDI 物件分配過多並產生記憶體不足的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2078">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

- <span data-ttu-id="224d0-2079">修正以下問題：如果執行 'CustomFieldValueListGetItem' 且自訂欄位的查閱資料表不存在，系統會建立一個不應建立的空白查閱資料表。</span><span class="sxs-lookup"><span data-stu-id="224d0-2079">Fixed an issue where if CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

- <span data-ttu-id="224d0-2080">在表單檢視中編輯前置/後續任務資料時，會觸發額外的 ProjectBeforeTaskChange 事件</span><span class="sxs-lookup"><span data-stu-id="224d0-2080">WhenPredecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired</span></span>

- <span data-ttu-id="224d0-2081">修正了當開啟保護實際工作的設定時，使用者無法輸入分時期基準工時的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2081">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="224d0-2082">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-2082">Word</span></span>

- <span data-ttu-id="224d0-2083">此變更修正了將游標懸停在提示上並不會醒目提示其卡片的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2083">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="224d0-2084">此變更修正了以下問題：從 [檢視] 功能表選取多個頁面時，其中的 [註解] 窗格會顯示為空白。</span><span class="sxs-lookup"><span data-stu-id="224d0-2084">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

- <span data-ttu-id="224d0-2085">已修正張貼留言功能停用的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2085">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="224d0-2086">此變更修正了使用套索選取工具時，群組圖形中的文字會暫時消失的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2086">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="224d0-2087">此變更解決了處理格式錯誤或無效通訊協定資訊影像時所導致的延遲問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2087">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="224d0-2088">此變更修正了在 PowerPoint 或 Word 中呈現內嵌為 OLE 物件的舊版 Excel 圖表時可能不會永遠顯示圖表標題的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2088">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="224d0-2089">這項變更解決了帳戶管理員不會分派訊息而導致協力廠商應用程式懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2089">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="224d0-2090">此變更修正了在雙頁檢視中建立註解時，註解錨點不一定會顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2090">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="224d0-2091">修正輸入或編輯備註然後使用 Ctrl+A 時，會導致選取畫布中的文字，而不只是選取備註卡片內文字的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2091">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>

- <span data-ttu-id="224d0-2092">修正如果段落的樣式是連結至清單的樣式上階，則該清單的編號可能會遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2092">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

- <span data-ttu-id="224d0-2093">這項變更修正了目錄會使用文件中未包含的標題樣式進行更新的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2093">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="224d0-2094">我們已修正文件中的文字對齊，在使用 [快速列印] 進行列印之後嘗試進行編輯時變得混亂的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2094">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="224d0-2095">我們已修正將兩份文件合併成一份文件時的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2095">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="224d0-2096">已修正在寄送文件時，儲存在 Word 文件中的數位簽章會被刪除的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2096">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

- <span data-ttu-id="224d0-2097">修正標示的修訂若與方程式有關，在儲存檔案時可能會導致失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2097">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-april-14"></a><span data-ttu-id="224d0-2099">版本 2003：4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="224d0-2099">Version 2003: April 14</span></span>
<span data-ttu-id="224d0-2100">*版本 2003 (組建 12624.20466)*</span><span class="sxs-lookup"><span data-stu-id="224d0-2100">*Version 2003 (Build 12624.20466)*</span></span>

<span data-ttu-id="224d0-2101">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="224d0-2101">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

- <span data-ttu-id="224d0-2103">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="224d0-2103">Various bugs and performance fixes.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2003-april-09"></a><span data-ttu-id="224d0-2105">版本 2003：4 月 9 日</span><span class="sxs-lookup"><span data-stu-id="224d0-2105">Version 2003: April 09</span></span>
<span data-ttu-id="224d0-2106">*版本 2003 (組建 12624.20442)*</span><span class="sxs-lookup"><span data-stu-id="224d0-2106">*Version 2003 (Build 12624.20442)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-2108">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-2108">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-2109">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-2109">Excel</span></span>

- <span data-ttu-id="224d0-2110">**M365 進階版內容選擇器：** 讓您的文件栩栩如生！</span><span class="sxs-lookup"><span data-stu-id="224d0-2110">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="224d0-2111">探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="224d0-2111">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="224d0-2112">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-2112">Outlook</span></span>

- <span data-ttu-id="224d0-2113">**M365 進階版內容選擇器：** 讓您的文件栩栩如生！</span><span class="sxs-lookup"><span data-stu-id="224d0-2113">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="224d0-2114">探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="224d0-2114">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="224d0-2115">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-2115">PowerPoint</span></span>

- <span data-ttu-id="224d0-2116">**M365 進階版內容選擇器：** 讓您的文件栩栩如生！</span><span class="sxs-lookup"><span data-stu-id="224d0-2116">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="224d0-2117">探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="224d0-2117">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="word"></a><span data-ttu-id="224d0-2118">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-2118">Word</span></span>

- <span data-ttu-id="224d0-2119">**M365 進階版內容選擇器：** 讓您的文件栩栩如生！</span><span class="sxs-lookup"><span data-stu-id="224d0-2119">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="224d0-2120">探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="224d0-2120">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)




[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-april-03"></a><span data-ttu-id="224d0-2124">版本 2003：4 月 3 日</span><span class="sxs-lookup"><span data-stu-id="224d0-2124">Version 2003: April 03</span></span>
<span data-ttu-id="224d0-2125">*版本 2003 (組建 12624.20410)*</span><span class="sxs-lookup"><span data-stu-id="224d0-2125">*Version 2003 (Build 12624.20410)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-2127">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-2127">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-2128">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-2128">Excel</span></span>

- <span data-ttu-id="224d0-2129">使用 VBA 應用程式的 Application.Evaluate 在某些情況下，對使用者定義的函數無法運作。</span><span class="sxs-lookup"><span data-stu-id="224d0-2129">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="224d0-2130">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-2130">Outlook</span></span>

- <span data-ttu-id="224d0-2131">解決使用滑鼠上的「X」按鈕時，導致使用者偶爾發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2131">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

### <a name="project"></a><span data-ttu-id="224d0-2132">Project</span><span class="sxs-lookup"><span data-stu-id="224d0-2132">Project</span></span>

- <span data-ttu-id="224d0-2133">在表單檢視中編輯前置/後續任務資料時，會觸發額外的 ProjectBeforeTaskChangeevent。</span><span class="sxs-lookup"><span data-stu-id="224d0-2133">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChangeevent is fired.</span></span>

### <a name="word"></a><span data-ttu-id="224d0-2134">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-2134">Word</span></span>

- <span data-ttu-id="224d0-2135">解決使用滑鼠上的「X」按鈕時，導致使用者偶爾發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2135">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-march-31"></a><span data-ttu-id="224d0-2137">版本 2003：3 月 31 日</span><span class="sxs-lookup"><span data-stu-id="224d0-2137">Version 2003: March 31</span></span>
<span data-ttu-id="224d0-2138">*版本 2003 (組建 12624.20382)*</span><span class="sxs-lookup"><span data-stu-id="224d0-2138">*Version 2003 (Build 12624.20382)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-2140">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-2140">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="224d0-2141">Access</span><span class="sxs-lookup"><span data-stu-id="224d0-2141">Access</span></span>

- <span data-ttu-id="224d0-2142">**「新增資料表」工作窗格：** Access 的全新「新增資料表」工作窗格終於推出！</span><span class="sxs-lookup"><span data-stu-id="224d0-2142">**"Add Tables" Task Pane:** Access's new "Add Tables" Task Pane is finally here!</span></span> <span data-ttu-id="224d0-2143">這項功能可讓您輕鬆選取/多重選取要在查詢視窗中新增/移除的資料表，而不需要瀏覽至查詢和關聯視圖的「顯示資料表」對話方塊。</span><span class="sxs-lookup"><span data-stu-id="224d0-2143">This feature allows you to easily select/multi-select which tables they'd like to add/remove into a query window, without navigating to the "Show Tables" dialog for queries and for relationship view.</span></span> <span data-ttu-id="224d0-2144">這也包含新的「連結」索引標籤，可顯示連結的資料表、可篩選目前清單的搜尋方塊、「拖放」行為及更多功能！</span><span class="sxs-lookup"><span data-stu-id="224d0-2144">This also includes a new "links" tab to display linked tables, a search box to filter the current list, "drag and drop" behavior, and more!</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-2147">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-2147">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="224d0-2148">Project</span><span class="sxs-lookup"><span data-stu-id="224d0-2148">Project</span></span>

- <span data-ttu-id="224d0-2149"><span style="display:inline !important;">修正了當開啟保護實際工作的設定時，使用者無法輸入分時期基準工時的問題。</span></span><span class="sxs-lookup"><span data-stu-id="224d0-2149"><span style="display:inline !important;">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span></span><br>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-march-25"></a><span data-ttu-id="224d0-2151">版本 2003：3 月 25 日</span><span class="sxs-lookup"><span data-stu-id="224d0-2151">Version 2003: March 25</span></span>
<span data-ttu-id="224d0-2152">*版本 2003 (組建 12624.20320)*</span><span class="sxs-lookup"><span data-stu-id="224d0-2152">*Version 2003 (Build 12624.20320)*</span></span>

- <span data-ttu-id="224d0-2153">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="224d0-2153">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-23"></a><span data-ttu-id="224d0-2154">版本 2003：3 月 23 日</span><span class="sxs-lookup"><span data-stu-id="224d0-2154">Version 2003: March 23</span></span>
<span data-ttu-id="224d0-2155">*版本 2003 (組建 12624.20296)*</span><span class="sxs-lookup"><span data-stu-id="224d0-2155">*Version 2003 (Build 12624.20296)*</span></span>

- <span data-ttu-id="224d0-2156">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="224d0-2156">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-21"></a><span data-ttu-id="224d0-2157">版本 2003：3 月 21 日</span><span class="sxs-lookup"><span data-stu-id="224d0-2157">Version 2003: March 21</span></span>
<span data-ttu-id="224d0-2158">*版本 2003 (組建 12624.20276)*</span><span class="sxs-lookup"><span data-stu-id="224d0-2158">*Version 2003 (Build 12624.20276)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-2160">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-2160">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-2161">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-2161">Outlook</span></span>

- <span data-ttu-id="224d0-2162">**加入會議而不需離開您的收件匣：** 不需切換至您的行事曆即可加入線上會議。</span><span class="sxs-lookup"><span data-stu-id="224d0-2162">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="224d0-2163">將行事曆釘選到 [待辦事項] 窗格之後，只要按一下就能加入任何會議。</span><span class="sxs-lookup"><span data-stu-id="224d0-2163">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="224d0-2164">**行事曆新版視覺效果：** 去年，我們提供了全新的郵件體驗，而今年將為您帶來嶄新的行事曆！</span><span class="sxs-lookup"><span data-stu-id="224d0-2164">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar’s turn to get a facelift!</span></span> <span data-ttu-id="224d0-2165">這些更新是全新但令人熟悉的，身為經驗豐富的 Outlook 使用者的您，可以立即上手並更具生產力。</span><span class="sxs-lookup"><span data-stu-id="224d0-2165">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="224d0-2166">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-2166">PowerPoint</span></span>

- <span data-ttu-id="224d0-2167">**在投影片放映期間更新投影片：** 在簡報期間，更新由其他作者變更的投影片。</span><span class="sxs-lookup"><span data-stu-id="224d0-2167">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2003-march-16"></a><span data-ttu-id="224d0-2169">版本 2003：3 月 16 日</span><span class="sxs-lookup"><span data-stu-id="224d0-2169">Version 2003: March 16</span></span>
<span data-ttu-id="224d0-2170">*版本 2003 (組建 12624.20224)*</span><span class="sxs-lookup"><span data-stu-id="224d0-2170">*Version 2003 (Build 12624.20224)*</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-2172">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-2172">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-2173">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-2173">Excel</span></span>

- <span data-ttu-id="224d0-2174">**挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。</span><span class="sxs-lookup"><span data-stu-id="224d0-2174">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="outlook"></a><span data-ttu-id="224d0-2175">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-2175">Outlook</span></span>

- <span data-ttu-id="224d0-2176">**挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。</span><span class="sxs-lookup"><span data-stu-id="224d0-2176">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="224d0-2177">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-2177">PowerPoint</span></span>

- <span data-ttu-id="224d0-2178">**挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。</span><span class="sxs-lookup"><span data-stu-id="224d0-2178">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="word"></a><span data-ttu-id="224d0-2179">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-2179">Word</span></span>

- <span data-ttu-id="224d0-2180">**挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。</span><span class="sxs-lookup"><span data-stu-id="224d0-2180">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="office-suite"></a><span data-ttu-id="224d0-2181">Office 套件</span><span class="sxs-lookup"><span data-stu-id="224d0-2181">Office Suite</span></span>

- <span data-ttu-id="224d0-2182">**索引標籤式窗格：** 現在您可以使用應用程式右側的索引標籤 UI，在多個窗格之間切換。</span><span class="sxs-lookup"><span data-stu-id="224d0-2182">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="224d0-2183">只有當您開啟 2 個以上的窗格時，該 UI 才會顯示。</span><span class="sxs-lookup"><span data-stu-id="224d0-2183">The UI will only be visible when you have 2+ panes open.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-2186">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-2186">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-2187">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-2187">Excel</span></span>

- <span data-ttu-id="224d0-2188">已解決當來源活頁簿關閉時，外部連結無法在填滿時更新的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2188">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

### <a name="outlook"></a><span data-ttu-id="224d0-2189">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-2189">Outlook</span></span>

- <span data-ttu-id="224d0-2190">已解決導致使用者在工作管理員中看到 Outlook 處理序延遲的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2190">Addressed an issue that caused users to see the Outlook process lingering in task manager after exiting.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-march-10"></a><span data-ttu-id="224d0-2192">版本 2003：3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="224d0-2192">Version 2003: March 10</span></span>
<span data-ttu-id="224d0-2193">*版本 2003 (組建 12624.20176)*</span><span class="sxs-lookup"><span data-stu-id="224d0-2193">*Version 2003 (Build 12624.20176)*</span></span>

<span data-ttu-id="224d0-2194">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="224d0-2194">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)
### <a name="feature-updates"></a><span data-ttu-id="224d0-2196">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-2196">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-2197">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-2197">Excel</span></span>
- <span data-ttu-id="224d0-2198">**敏感度標籤**：您現在可以套用組織設定、用來提示您輸入自訂權限的敏感度標籤。</span><span class="sxs-lookup"><span data-stu-id="224d0-2198">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="224d0-2199">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-2199">Learn more</span></span>](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a><span data-ttu-id="224d0-2200">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-2200">PowerPoint</span></span>
- <span data-ttu-id="224d0-2201">**敏感度標籤**：您現在可以套用組織設定、用來提示您輸入自訂權限的敏感度標籤。</span><span class="sxs-lookup"><span data-stu-id="224d0-2201">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="224d0-2202">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-2202">Learn more</span></span>](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a><span data-ttu-id="224d0-2203">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-2203">Word</span></span>
- <span data-ttu-id="224d0-2204">**敏感度標籤**：您現在可以套用組織設定、用來提示您輸入自訂權限的敏感度標籤。</span><span class="sxs-lookup"><span data-stu-id="224d0-2204">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="224d0-2205">深入了解</span><span class="sxs-lookup"><span data-stu-id="224d0-2205">Learn more</span></span>](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)
</br>

### <a name="resolved-issues"></a><span data-ttu-id="224d0-2206">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-2206">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-2207">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-2207">Excel</span></span>

- <span data-ttu-id="224d0-2208">修正 [檔案]\[選項] 對話方塊上的 [確定] 按鈕顯示為灰色停用狀態，但功能並未受影響的外觀問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2208">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="224d0-2209">修正使用者在重新命名樞紐分析表度量值時可能遇到的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2209">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>

- <span data-ttu-id="224d0-2210">修正交叉分析篩選器中的文字在預覽列印中無法正確縮放的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2210">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

- <span data-ttu-id="224d0-2211">已修正使用者在使用 VBA 巨集清除範圍內容時可能遇到的效能問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2211">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="224d0-2212">修正當使用者執行與功能區互動的巨集時，導致 UI 快閃的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2212">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>

- <span data-ttu-id="224d0-2213">修正當檔案中的第一個字為 TABLE 時，CSV 檔案載入錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2213">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>

- <span data-ttu-id="224d0-2214">已修正當您在兩個具有不同縮放比例的活頁簿之間切換時，使用者可能遇到的當機問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2214">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

- <span data-ttu-id="224d0-2215">修正 CUBEVALUE 函數有時會傳回不正確結果的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2215">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="224d0-2216">此變更可解決物件模型中的執行階段錯誤，以及當增益集要求的文件/工作表上的主機項目包含具有 noSelect 鎖定的圖形時，應用程式 (Excel、Word) 的潛在當機。</span><span class="sxs-lookup"><span data-stu-id="224d0-2216">This change addresses a run-time error in the object model and potential crash of the App (Excel, Word) when Add-ins ask for Host Items on documents/worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="224d0-2217">解決導致 Outlook 使用者在同步處理設定時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2217">Addresses an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>



### <a name="outlook"></a><span data-ttu-id="224d0-2218">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-2218">Outlook</span></span>

- <span data-ttu-id="224d0-2219">修正使用 Outlook Web Access 建立規則時不會保存到 Exchange 伺服器，並導致衝突的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2219">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>

- <span data-ttu-id="224d0-2220">解決導致 Outlook 使用者在同步處理設定時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2220">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

- <span data-ttu-id="224d0-2221">修正 Outlook 在深色模式中不會在 [寄件者:] 欄位中顯示下拉式清單的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2221">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>

- <span data-ttu-id="224d0-2222">解決即使已關閉記錄，在某些情況下仍導致 Outlook 異常產生記錄輸出的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2222">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

- <span data-ttu-id="224d0-2223">已解決當持續整夜執行 Outlook 時，導致使用者無法開啟公用資料夾訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2223">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>

- <span data-ttu-id="224d0-2224">已修正在新增 Gmail 帳戶的驗證工作流程中，[權限] 頁面上的 [允許] 和 [拒絕] 按鈕停用的爭用情況。</span><span class="sxs-lookup"><span data-stu-id="224d0-2224">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>

- <span data-ttu-id="224d0-2225">解決導致使用者無法存取 [空閒/忙碌選項] 行事曆權限對話方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2225">Addressed an issue that caused users to lose access to the &quot;Free Busy Options&quot; calendar permissions dialog.</span></span>

- <span data-ttu-id="224d0-2226">修正開啟某些傳送自不同時區的週期性會議執行個體時，可能導致出現警示：「很抱歉，開啟此項目時發生問題」的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2226">Fixed an issue that may result in the alert: &quot;Sorry we're having trouble opening this item&quot; when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="224d0-2227">已解決從該郵件拖放附件後造成使用者無法重新開啟 .msg 檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2227">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="224d0-2228">修正從 Outlook 上傳檔案附件到 OneDrive 後，造成包含括號之附件名稱的檔案名稱被變更。</span><span class="sxs-lookup"><span data-stu-id="224d0-2228">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

- <span data-ttu-id="224d0-2229">解決在其他應用程式中開啟某個檔案時，導致使用者無法透過檔案總管將該檔案附加至郵件訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2229">Addressed an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

- <span data-ttu-id="224d0-2230">解決導致 Outlook 使用者在同步處理設定時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2230">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="224d0-2231">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-2231">PowerPoint</span></span>

- <span data-ttu-id="224d0-2232">修正將滑鼠移至縮圖上時，建議的縮圖閃動的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2232">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="224d0-2233">在某些情況下，這可能會導致 PowerPoint 當機。</span><span class="sxs-lookup"><span data-stu-id="224d0-2233">In some cases this could cause PowerPoint to crash.</span></span>

- <span data-ttu-id="224d0-2234">修正 [檔案]\[選項] 對話方塊上的 [確定] 按鈕顯示為灰色停用狀態，但功能並未受影響的外觀問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2234">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="224d0-2235">修正儲存包含 Excel 圖表的 PowerPoint 或 Word 文件會導致失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2235">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>



### <a name="project"></a><span data-ttu-id="224d0-2236">Project</span><span class="sxs-lookup"><span data-stu-id="224d0-2236">Project</span></span>

- <span data-ttu-id="224d0-2237">修正在將任務標示為完成之後，不正確地將任務完成百分比變更為低於 100% 的值的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2237">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="224d0-2238">修正不先執行 OpenUndoTransaction 方法就不能觸發 OnUndoOrRedo 事件的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2238">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="224d0-2239">修正無法正確計算摘要工作日期的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2239">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

### <a name="visio"></a><span data-ttu-id="224d0-2240">Visio</span><span class="sxs-lookup"><span data-stu-id="224d0-2240">Visio</span></span>

- <span data-ttu-id="224d0-p238">[圖形資訊] 窗格的 [圖案資料] 區段下顯示的詳細資料，與在 Visio 桌面版中開啟該檔案時所顯示的不一致。現已修正此問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-p238">Shape info pane was showing inconsistent details under Shape Data section, with respect to the file when opened in Visio Desktop. It has now been fixed.</span></span>

- <span data-ttu-id="224d0-2243">在 2016 之前版本中匯入的點陣圖，由於某些安全性檢查而未呈現。</span><span class="sxs-lookup"><span data-stu-id="224d0-2243">Bitmaps imported in versions before 2016 were not being rendered due to some security checks.</span></span> <span data-ttu-id="224d0-2244">我們已在 Visio 訂閱中修正此問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2244">We have fixed this issue in Visio Subscription.</span></span>

### <a name="word"></a><span data-ttu-id="224d0-2245">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-2245">Word</span></span>

- <span data-ttu-id="224d0-2246">修正當滑鼠指標暫留在註解卡片上方時，未醒目提示註解卡片的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2246">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>

- <span data-ttu-id="224d0-2247">修正按 Tab 鍵導覽註解卡片時，註解編輯方塊上的焦點無法顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2247">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="224d0-2248">修正 [檔案]\[選項] 對話方塊上的 [確定] 按鈕顯示為灰色停用狀態，但功能並未受影響的外觀問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2248">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="224d0-p240">在使用中的文件共同撰寫工作階段期間，直接在註解卡片中新增影像可能會導致新增標籤。已修正此問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-p240">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag. This issue has been fixed.</span></span>

- <span data-ttu-id="224d0-2251">在方程式中插入控制項 (例如文字內容控制項)，然後儲存再開啟檔案，便會導致內容無法讀取的錯誤。</span><span class="sxs-lookup"><span data-stu-id="224d0-2251">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="224d0-2252">修正將先前使用密碼保護的檔案儲存到雲端儲存空間無法運作的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2252">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

- <span data-ttu-id="224d0-2253">修正受保護無法編輯之文件的比較功能問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2253">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>




### <a name="office-suite"></a><span data-ttu-id="224d0-2254">Office 套件</span><span class="sxs-lookup"><span data-stu-id="224d0-2254">Office Suite</span></span>

- <span data-ttu-id="224d0-2255">當您將 Multichoice/Lookup/Managed-metadata 屬性與 Word/Excel/PowerPoint 文件一起使用並儲存至 SharePoint 文件庫時，這些屬性之前限制為 255 個字元。</span><span class="sxs-lookup"><span data-stu-id="224d0-2255">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="224d0-2256">當這些屬性超過 255 個字元時，這類文件就無法儲存。</span><span class="sxs-lookup"><span data-stu-id="224d0-2256">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="224d0-2257">在此變更中，此限制已增加到 2048 個字元。</span><span class="sxs-lookup"><span data-stu-id="224d0-2257">With this change, this limit has been increased to 2048 characters.</span></span>

- <span data-ttu-id="224d0-2258">修正 Word/Excel/PowerPoint 中的使用者主體名稱 (UPN) 不再區分大小寫，導致在 SharePoint 上使用檔案時較少發生失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2258">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="224d0-2259">修正在 Word/Excel/PowerPoint 中開啟來自相同 SharePoint 文件庫的多個文件時，僅掃描開啟的第一個文件是否符合原則的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2259">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-march-05"></a><span data-ttu-id="224d0-2261">版本 2002：3 月 5 日</span><span class="sxs-lookup"><span data-stu-id="224d0-2261">Version 2002: March 05</span></span>
<span data-ttu-id="224d0-2262">*版本 2002 (組建 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="224d0-2262">*Version 2002 (Build 12527.20278)*</span></span>

- <span data-ttu-id="224d0-2263">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="224d0-2263">Various bugs and performance fixes.</span></span>


## <a name="version-2002-march-04"></a><span data-ttu-id="224d0-2264">版本 2002：3 月 4 日</span><span class="sxs-lookup"><span data-stu-id="224d0-2264">Version 2002: March 04</span></span>
<span data-ttu-id="224d0-2265">*版本 2002 (組建 12527.20264)*</span><span class="sxs-lookup"><span data-stu-id="224d0-2265">*Version 2002 (Build 12527.20264)*</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-2267">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-2267">Resolved issues</span></span>

### <a name="project"></a><span data-ttu-id="224d0-2268">Project</span><span class="sxs-lookup"><span data-stu-id="224d0-2268">Project</span></span>
- <span data-ttu-id="224d0-2269">修正無法正確計算摘要工作日期的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2269">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>


### <a name="office-suite"></a><span data-ttu-id="224d0-2270">Office 套件</span><span class="sxs-lookup"><span data-stu-id="224d0-2270">Office Suite</span></span>
- <span data-ttu-id="224d0-2271">修正在 Word/Excel/PowerPoint 中開啟來自相同 SharePoint 文件庫的多個文件時，僅掃描開啟的第一個文件是否符合原則的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2271">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-march-01"></a><span data-ttu-id="224d0-2273">版本 2002：3 月 1 日</span><span class="sxs-lookup"><span data-stu-id="224d0-2273">Version 2002: March 01</span></span>
<span data-ttu-id="224d0-2274">*版本 2002 (組建 12527.20242)*</span><span class="sxs-lookup"><span data-stu-id="224d0-2274">*Version 2002 (Build 12527.20242)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="224d0-2275">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-2275">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-2276">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-2276">Outlook</span></span>

- <span data-ttu-id="224d0-2277">解決導致協力廠商應用程式無法傳送電子郵件的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2277">Addresses an issue that caused third party applications to be unable to send email.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-february-24"></a><span data-ttu-id="224d0-2279">版本 2002：2 月 24 日</span><span class="sxs-lookup"><span data-stu-id="224d0-2279">Version 2002: February 24</span></span>
<span data-ttu-id="224d0-2280">*版本 2002 (組建 12527.20194)*</span><span class="sxs-lookup"><span data-stu-id="224d0-2280">*Version 2002 (Build 12527.20194)*</span></span>

- <span data-ttu-id="224d0-2281">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="224d0-2281">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-22"></a><span data-ttu-id="224d0-2282">版本 2002：2 月 22 日</span><span class="sxs-lookup"><span data-stu-id="224d0-2282">Version 2002: February 22</span></span>
<span data-ttu-id="224d0-2283">*版本 2002 (組建 12527.20186)*</span><span class="sxs-lookup"><span data-stu-id="224d0-2283">*Version 2002 (Build 12527.20186)*</span></span>

- <span data-ttu-id="224d0-2284">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="224d0-2284">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-21"></a><span data-ttu-id="224d0-2285">版本 2002：2 月 21 日</span><span class="sxs-lookup"><span data-stu-id="224d0-2285">Version 2002: February 21</span></span>
<span data-ttu-id="224d0-2286">*版本 2002 (組建 12527.20174)*</span><span class="sxs-lookup"><span data-stu-id="224d0-2286">*Version 2002 (Build 12527.20174)*</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-2288">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-2288">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="224d0-2289">Access</span><span class="sxs-lookup"><span data-stu-id="224d0-2289">Access</span></span>

- <span data-ttu-id="224d0-2290">**在查詢設計工具、SQL 檢視和關聯視窗中工作時更具生產力：** 在資料表上按一下滑鼠右鍵即可開啟、設計、調整大小及隱藏它。</span><span class="sxs-lookup"><span data-stu-id="224d0-2290">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="224d0-2291">在 SQL 檢視中搜尋及取代文字。</span><span class="sxs-lookup"><span data-stu-id="224d0-2291">Search and replace text in SQL View.</span></span> <span data-ttu-id="224d0-2292">在 [關聯圖] 視窗中選取多個資料表。</span><span class="sxs-lookup"><span data-stu-id="224d0-2292">Select multiple tables in the Relationships window.</span></span>

### <a name="outlook"></a><span data-ttu-id="224d0-2293">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-2293">Outlook</span></span>

- <span data-ttu-id="224d0-2294">**受限 WiFi 網路的新體驗：** 是否曾經加入需要登入網頁的 WiFi 網路呢？</span><span class="sxs-lookup"><span data-stu-id="224d0-2294">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="224d0-2295">Outlook 現在會偵測這項要求並協助您取得連結。</span><span class="sxs-lookup"><span data-stu-id="224d0-2295">Outlook now detects this and helps you get connected.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-2298">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-2298">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="224d0-2299">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-2299">Excel</span></span>

- <div style="box-sizing:border-box;"><span data-ttu-id="224d0-2300">修正 CUBEVALUE 函數有時會傳回不正確結果的問題。&nbsp;<span style="display:inline !important;"></span></span><span class="sxs-lookup"><span data-stu-id="224d0-2300">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.&nbsp;<span style="display:inline !important;"></span></span></span><br>


### <a name="outlook"></a><span data-ttu-id="224d0-2301">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-2301">Outlook</span></span>

- <span data-ttu-id="224d0-2302">解決導致會議的位置欄位中的逗號變成分號的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2302">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>


- <span data-ttu-id="224d0-2303">解決在多個視窗中檢視相同項目時可能會導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2303">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>


- <span data-ttu-id="224d0-2304">解決即使將同步處理滑桿設定為較小的設定，也會導致 Outlook 非預期地同步處理所有郵件的問題。&nbsp;</span><span class="sxs-lookup"><span data-stu-id="224d0-2304">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.&nbsp;</span></span>


- <span data-ttu-id="224d0-2305">解決會導致使用黑色佈景主題的使用者看到 [從]&quot;&quot; 下拉式功能表在白色背景上顯示白色文字的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2305">Addresses an issue that caused users with Black Theme to see the &quot;From&quot; dropdown show white text on a white background.</span></span>


- <span data-ttu-id="224d0-2306"><span style="display:inline !important;">此變更會還原在郵件標頭中檢視多行主旨的功能。</span></span><span class="sxs-lookup"><span data-stu-id="224d0-2306"><span style="display:inline !important;">This change restores the ability to view multi-line subjects in the message header.</span></span></span><br>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-february-18"></a><span data-ttu-id="224d0-2308">版本 2002：2 月 18 日</span><span class="sxs-lookup"><span data-stu-id="224d0-2308">Version 2002: February 18</span></span>
<span data-ttu-id="224d0-2309">*版本 2002 (組建 12527.20138)*</span><span class="sxs-lookup"><span data-stu-id="224d0-2309">*Version 2002 (Build 12527.20138)*</span></span>

## <a name="version-2002-february-11"></a><span data-ttu-id="224d0-2310">版本 2002：2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="224d0-2310">Version 2002: February 11</span></span>
<span data-ttu-id="224d0-2311">*版本 2002 (組建 12527.20092)*</span><span class="sxs-lookup"><span data-stu-id="224d0-2311">*Version 2002 (Build 12527.20092)*</span></span>

<span data-ttu-id="224d0-2312">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="224d0-2312">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="224d0-2314">功能更新</span><span class="sxs-lookup"><span data-stu-id="224d0-2314">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="224d0-2315">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-2315">Outlook</span></span>

- <span data-ttu-id="224d0-2316">**將電子郵件拖曳到您擁有的群組：** 從您的 [收件匣] 拖曳郵件和交談以將它們移動和複製。</span><span class="sxs-lookup"><span data-stu-id="224d0-2316">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="224d0-2317">您拖曳的郵件將會與所有群組成員共用。</span><span class="sxs-lookup"><span data-stu-id="224d0-2317">Messages you drag will be shared with all group members.</span></span>

### <a name="word"></a><span data-ttu-id="224d0-2318">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-2318">Word</span></span>

- <span data-ttu-id="224d0-2319">**其他人更快速看到您的變更：** 共同撰寫增強功能表示，共同作業者可較以往更快速看到您的變更。</span><span class="sxs-lookup"><span data-stu-id="224d0-2319">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

### <a name="office-suite"></a><span data-ttu-id="224d0-2320">Office 套件</span><span class="sxs-lookup"><span data-stu-id="224d0-2320">Office Suite</span></span>

- <span data-ttu-id="224d0-2321">**更清楚的狀態列圖示：** 狀態列圖示現在更容易查看。</span><span class="sxs-lookup"><span data-stu-id="224d0-2321">**Clearer status bar icons:** Status bar icons are now easier to see.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="224d0-2324">解決的問題</span><span class="sxs-lookup"><span data-stu-id="224d0-2324">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="224d0-2325">Access</span><span class="sxs-lookup"><span data-stu-id="224d0-2325">Access</span></span>

- <span data-ttu-id="224d0-2326">Access 範本應不再導致資料庫中的附件欄出現故障。</span><span class="sxs-lookup"><span data-stu-id="224d0-2326">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="224d0-2327">個體化範本後，您現在應該可以將附件欄新增至資料庫。</span><span class="sxs-lookup"><span data-stu-id="224d0-2327">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="224d0-p246">此更新會修正使用 ADODB 的問題。VB 程式碼中的錄製程式物件可能會不正確地報告錯誤。</span><span class="sxs-lookup"><span data-stu-id="224d0-p246">This update fixes an issue where using an ADODB. Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="224d0-2330">此更新修正可能會導致 Microsoft Access 無法識別連結的 SQL Server 資料表中的識別資料行的問題，這可能會導致不正確地將資料列報告為已刪除。</span><span class="sxs-lookup"><span data-stu-id="224d0-2330">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>


### <a name="excel"></a><span data-ttu-id="224d0-2331">Excel</span><span class="sxs-lookup"><span data-stu-id="224d0-2331">Excel</span></span>

- <span data-ttu-id="224d0-2332">修正未顯示操作功能表中的註解命令的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2332">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>


- <span data-ttu-id="224d0-2333">修正以下問題：將文字轉換成具有溢出陣列之儲存格的欄時，某些使用者發生當機。</span><span class="sxs-lookup"><span data-stu-id="224d0-2333">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>


- <span data-ttu-id="224d0-2334">修正使用「資料剖析」搭配動態陣列時，Excel 會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2334">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="224d0-2335">Outlook</span><span class="sxs-lookup"><span data-stu-id="224d0-2335">Outlook</span></span>

- <span data-ttu-id="224d0-2336">修正以月檢視在行事曆中捲動時，無法顯示之前的行事曆活動的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2336">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="224d0-2337">儲存在左側瀏覽窗格 [我的最愛] 的資料夾可能會間歇性消失。</span><span class="sxs-lookup"><span data-stu-id="224d0-2337">Folders saved in 'Favorites' in the left navigation pane may intermittently disappear.</span></span>


- <span data-ttu-id="224d0-2338">已解決導致使用者在指定無效寄件者地址時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2338">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>


- <span data-ttu-id="224d0-2339">已解決導致在某些情況下無法使用相關選項來停用標幟項目醒目提示的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2339">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="224d0-2340">已解決導致使用者在取消帳戶設定時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2340">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>


- <span data-ttu-id="224d0-2341">修正根據保留原則到期的電子郵件會顯示兩個標籤的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2341">Fixed an issue where emails expiring based on a retention policy would display two labels.</span></span> <span data-ttu-id="224d0-2342">其中一個顯示郵件將在一天內過期，另一個則顯示將在兩天內到期。</span><span class="sxs-lookup"><span data-stu-id="224d0-2342">One showing that the mail will expire in one day and another displaying that it will expire in two days.</span></span>


- <span data-ttu-id="224d0-2343">已解決在 Citrix 環境中檢視 30 個以上的行事曆時，導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2343">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="224d0-2344">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="224d0-2344">PowerPoint</span></span>

- <span data-ttu-id="224d0-2345">修正使用 PowerPoint 筆跡動畫時，無法完整轉譯或跳過的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2345">Fixed an issue where Ink may not render completely or get skipped when used in a PowerPoint ink animations.</span></span>

- <span data-ttu-id="224d0-2346">修正關閉檔案之後，如果有任何事件處理常式正在執行，PowerPoint 就不會立即將它從 [簡報] 集合中移除的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2346">Fixed an issue where After closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="224d0-2347">因此，物件模型報告的開啟中簡報數目會不正確，且會防止關閉 PowerPoint。</span><span class="sxs-lookup"><span data-stu-id="224d0-2347">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>


- <span data-ttu-id="224d0-2348">修正具有深色螢光筆色彩的白色文字，在灰階中會以黑色列印的螢光筆問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2348">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>


### <a name="project"></a><span data-ttu-id="224d0-2349">Project</span><span class="sxs-lookup"><span data-stu-id="224d0-2349">Project</span></span>

- <span data-ttu-id="224d0-2350">修正以下問題：固定工期類型的 100% 工作可能會誤將其完成百分比計算為小於 100% 完成。</span><span class="sxs-lookup"><span data-stu-id="224d0-2350">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>


### <a name="word"></a><span data-ttu-id="224d0-2351">Word</span><span class="sxs-lookup"><span data-stu-id="224d0-2351">Word</span></span>

- <span data-ttu-id="224d0-2352">更新和瀏覽目錄時，有時可能會在文件上顯示灰色區域的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2352">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>


- <span data-ttu-id="224d0-2353">修正在已撰寫註解但未張貼，且使用者嘗試儲存檔案的情況下，使用 [瀏覽] 來儲存檔案沒有作用的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2353">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>


- <span data-ttu-id="224d0-2354">已修正在註解卡片之間來回切換時，有時會顯示一開始選取的註解，並將某選取範圍醒目提示的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2354">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>


- <span data-ttu-id="224d0-2355">修正在編輯備註之後將文字設為斜體然後再張貼，斜體格式設定遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2355">Fixed an issue where italics formatting is lost after editing a comment, italicizing the text and then posting it.</span></span>


- <span data-ttu-id="224d0-2356">修正在具有「反轉」頁面色彩的閱讀模式中，備註提示未顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2356">Fixed an issue where comment hint was not visible in read mode with Inverse page color.</span></span>


- <span data-ttu-id="224d0-2357">修正共同撰寫文件時，可能不會保留根註解的草稿版本的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2357">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>


- <span data-ttu-id="224d0-2358">將 SlideTrack 啟用且 [註解] 窗格關閉時，Ctrl+Alt+M 可能無法開啟 [註解] 窗格的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2358">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>


- <span data-ttu-id="224d0-2359">修正在表格中新增 @提及時可能發生錯誤訊息：「文件中的表格已經毀損」的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2359">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>


- <span data-ttu-id="224d0-2360">修正備註內容功能表中的備註命令 (編輯備註、回覆備註、刪除備註、解決備註) 未顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2360">Fixed an issue where comment commands (Edit comment, Reply to comment, Delete comment, Resolve comment) in the comments context menu were not being displayed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="224d0-2361">Office 套件</span><span class="sxs-lookup"><span data-stu-id="224d0-2361">Office Suite</span></span>

- <span data-ttu-id="224d0-2362">解決可能導致挪威耐諾斯克 (nn-no) 校訂工具套件安裝不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2362">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>


- <span data-ttu-id="224d0-2363">此變更解決使用 Intel Integrated GPU 的圖形配接卡報告問題。</span><span class="sxs-lookup"><span data-stu-id="224d0-2363">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)
