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
ms.openlocfilehash: cbb7abb985eccb0e7ee8669812ff4b9837565377
ms.sourcegitcommit: 67f8d4a8655b95abc51fc6a81ff7142baf2194d4
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/11/2020
ms.locfileid: "47449546"
---
# <a name="release-notes-for-office-current-channel-preview"></a><span data-ttu-id="a8166-103">Office 版本資訊目前通道 (預覽)</span><span class="sxs-lookup"><span data-stu-id="a8166-103">Release Notes for Office Current Channel (Preview)</span></span>

<span data-ttu-id="a8166-104">本文包含 Windows 電腦版 Word、Excel、PowerPoint、Outlook、Access 和 Project 目前通道 (預覽) 組建的版本資訊。</span><span class="sxs-lookup"><span data-stu-id="a8166-104">This article contains release notes for Current Channel (Preview) builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="a8166-105">我們每週都強調有趣的新功能、重要修正，以及我們想讓您知道的重大問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="a8166-106">請注意，我們通常會在一段時間內推出功能 (有時甚至推出修正程式) 至目前通道 (預覽)。</span><span class="sxs-lookup"><span data-stu-id="a8166-106">Note that we often roll out features (and sometimes even fixes) to Current Channel (Preview) over a period of time.</span></span> <span data-ttu-id="a8166-107">這樣可讓我們確保功能都運作順利，然後才推出給更廣泛的對象。</span><span class="sxs-lookup"><span data-stu-id="a8166-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="a8166-108">所以，如果你沒有看到下面描述的項目，不要擔心你最終會得到它。</span><span class="sxs-lookup"><span data-stu-id="a8166-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="a8166-109">我們會變更 Microsoft 365 應用程式的更新通道，包括新增新的更新通道 (每月企業通道)，並變更現有的更新通道名稱。</span><span class="sxs-lookup"><span data-stu-id="a8166-109">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="a8166-110">如需深入了解，[請閱讀本文](https://go.microsoft.com/fwlink/p/?linkid=2127441)。</span><span class="sxs-lookup"><span data-stu-id="a8166-110">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
> - <span data-ttu-id="a8166-111">版本資訊發佈日期可能與實際組建發行日期不相符。</span><span class="sxs-lookup"><span data-stu-id="a8166-111">The release notes publication date may not match the actual build release date.</span></span>

[//]: # (DO NOT REMOVE)

## <a name="version-2009-september-10"></a><span data-ttu-id="a8166-113">版本 2009：9 月 10 日</span><span class="sxs-lookup"><span data-stu-id="a8166-113">Version 2009: September 10</span></span>
<span data-ttu-id="a8166-114">*版本 2009 (組建 13231.20126)*</span><span class="sxs-lookup"><span data-stu-id="a8166-114">*Version 2009 (Build 13231.20126)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="a8166-116">解決的問題</span><span class="sxs-lookup"><span data-stu-id="a8166-116">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="a8166-117">Access</span><span class="sxs-lookup"><span data-stu-id="a8166-117">Access</span></span>

- <span data-ttu-id="a8166-118">此問題現在已解決，您不應該會再遇到當機。</span><span class="sxs-lookup"><span data-stu-id="a8166-118">This issue has now been resolved and you should no longer experience a crash.</span></span>


- <span data-ttu-id="a8166-119">我們已修正 ODBC 資料庫的連線對協力廠商應用程式沒有作用的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-119">We fixed an issue where connections to an ODBC database were not working with third party applications.</span></span>


### <a name="excel"></a><span data-ttu-id="a8166-120">Excel</span><span class="sxs-lookup"><span data-stu-id="a8166-120">Excel</span></span>

- <span data-ttu-id="a8166-121">我們修正了一個問題, 即如果您開啟包含LET 函數的檔案，它會顯示警示：”我們在您的檔案.xlsx 中發現內容有問題”。</span><span class="sxs-lookup"><span data-stu-id="a8166-121">We fixed an issue where if you opened a file containing the LET function, it would display the alert:  "We found a problem with content in "your file.xlsx".</span></span> <span data-ttu-id="a8166-122">您想要我們儘量嘗試復原嗎？</span><span class="sxs-lookup"><span data-stu-id="a8166-122">Do you want us to try to recover as much as we can?</span></span> <span data-ttu-id="a8166-123">如果您信任這個活頁簿的來源，請按一下 [是]。</span><span class="sxs-lookup"><span data-stu-id="a8166-123">If you trust the source of this workbook, click Yes".</span></span>


- <span data-ttu-id="a8166-124">我們修復了如果用戶鍵入包含括號的公式名稱並通過F1調用了協助，則該特定於公式的說明主題將不會顯示。</span><span class="sxs-lookup"><span data-stu-id="a8166-124">We fixed an issue where if a user typed a formula name including the parenthesis and invoked help via F1, the help topic specific to that formula would not be displayed.</span></span>


- <span data-ttu-id="a8166-125">我們已修正使用巨集來設定某個範圍的 FormulaR1C1 屬性時，如果圖表工作表為作用中工作表，則儲存格參考會不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-125">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>


- <span data-ttu-id="a8166-126">我們修正了使用者無法修改樞紐分析表篩選的問題，因為它已設定為Analysis Services數據庫中不再存在的值。</span><span class="sxs-lookup"><span data-stu-id="a8166-126">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


- <span data-ttu-id="a8166-127">修正與 XLAM 增益集參照和具名範圍相關的損毀。</span><span class="sxs-lookup"><span data-stu-id="a8166-127">Fixed a crash related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="a8166-128">我們修正了一個問題: 如果使用者將自訂樣式套用至動態陣列, 他們則會收到錯誤提示：「您無法變更陣列的一部分」。</span><span class="sxs-lookup"><span data-stu-id="a8166-128">We fixed an issue where if a user applied a custom style to a dynamic array, they would get the error: "You can't change part of an array".</span></span> <span data-ttu-id="a8166-129">這是舊版限制，已移除。</span><span class="sxs-lookup"><span data-stu-id="a8166-129">This was a legacy restriction that has been removed.</span></span>


- <span data-ttu-id="a8166-130">修正在還原檔案的舊版本後，指派給按鈕的巨集會中斷的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-130">Fixed an issue where macros assigned to buttons were broken after restoring an older version of the file.</span></span>


- <span data-ttu-id="a8166-131">我們已修正筆跡會導致 Excel 無法回應的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-131">We fixed an issue where inking could cause Excel to become unresponsive.</span></span>


### <a name="outlook"></a><span data-ttu-id="a8166-132">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-132">Outlook</span></span>

- <span data-ttu-id="a8166-133">我們修正了一個問題, 讓您可透過群組政策來啟用/停用預設的登入選項。</span><span class="sxs-lookup"><span data-stu-id="a8166-133">We fixed an issue which provides more flexibility in enabling / disabling the default logging options via Group Policy.</span></span>


- <span data-ttu-id="a8166-134">我們修正了電子郵件草稿在助理和經理權限移動時, 寄件者的舊網域名稱仍被保留和顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-134">We fixed an issue where the Legacy Domain Name for an email sender was preserved and displayed after a draft of the email was moved between mailboxes with assistant permissions and manager permissions.</span></span>


- <span data-ttu-id="a8166-135">修正會導致某些使用者看到 Outlook 在離線狀態中啟動，直到他們手動選擇線上工作為止的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-135">Fixes an issue that caused some users to see Outlook to start in an Offline state until they manually chose to work online.</span></span>


- <span data-ttu-id="a8166-136">我們已修正在啟用單行功能區（SLR）後，執行 VBA 程式碼 ActiveInspector （"ShowSchedulingPage"）會導致執行階段錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-136">We fixed an issue where running the VBA code ActiveInspector.CommandBars.ExecuteMso("ShowSchedulingPage") after enabling the Single Line Ribbon (SLR) would result in a runtime error.</span></span>


- <span data-ttu-id="a8166-137">我們修正了一個問題, 即Automatic Replies自動回復對話方塊上的確定和取消按鈕以高解析度（例如 1750 x 1920）及較大文字（例如175%）顯示的系統上的錯誤。</span><span class="sxs-lookup"><span data-stu-id="a8166-137">We fixed an issue where the 'OK' and 'Cancel' buttons on the Automatic Replies dialog would not be visible on a system with a high resolution (such as 1750 x 1920) combined with a large text size (such as 175%).</span></span>


- <span data-ttu-id="a8166-138">我們修正一個情況, 即將會議請求從空的聯繫人群組發送到另一個聯繫人組會導致當機。</span><span class="sxs-lookup"><span data-stu-id="a8166-138">We fixed a condition where sending a meeting request from an empty contact group to another contact group would result in a crash.</span></span>


- <span data-ttu-id="a8166-139">解決會導致使用者在開啟某些很大型電子郵件時會發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-139">Fixes an issue that caused users to experience a crash when opening certain very large emails.</span></span>


- <span data-ttu-id="a8166-140">我們修正了一個問題, 它使的群組政策要求始終啟用增益集, 則 監視增益集的功能則無法使用，以防止使用者禁用增益集,。</span><span class="sxs-lookup"><span data-stu-id="a8166-140">We fixed an issue where if Group Policy requires an Add-in to be always enabled, then monitoring add-in's becomes unavailable in order to prevent users from disabling the Add-in.</span></span>


- <span data-ttu-id="a8166-141">解決一個問題，該問題導致使用者在選擇多個訊息時，能夠傳送 OneNote 所套用的「不可轉寄」原則的電子郵件內容。</span><span class="sxs-lookup"><span data-stu-id="a8166-141">Addresses an issue that caused users to be able to send email content that had a "Do Not Forward" policy applied to OneNote when selecting more than one message.</span></span>


- <span data-ttu-id="a8166-142">我們已修正一個問題，使用者現在可以停用 Outlook 的 IRM (資訊版權管理)，而不需要為其餘 Office 應用程式停用它。</span><span class="sxs-lookup"><span data-stu-id="a8166-142">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>


- <span data-ttu-id="a8166-143">我們修正了 Active Directory 中的 "otherTelephone" 和 "otherHomePhone" 使用者帳戶屬性未對應到對應的 Outlook LDAP 屬性的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-143">We fixed an issue where the user account attributes in Active Directory for "otherTelephone" and "otherHomePhone" were not mapped to the corresponding Outlook LDAP attributes.</span></span>


- <span data-ttu-id="a8166-144">此變更解決了在用戶將索引標籤從會議頁面切換到排程小幫手頁面後，會議頁面將繼續顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-144">This change fixes an issue where the Meeting page would continue to be displayed after the user switched tabs from the Meeting page to the Scheduling Assistant page.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="a8166-145">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8166-145">PowerPoint</span></span>

- <span data-ttu-id="a8166-146">我們修正了使用者在特定情況下看到功能區/標題列未顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-146">We fixed an issue where users were seeing the ribbon/title bar not being displayed under certain conditions.</span></span>


- <span data-ttu-id="a8166-147">我們已修正啟動 PowerPoint 之後，插入投影片並開啟和關閉批註窗格的問題，縮圖窗格中的投影片會顯示為重疊。</span><span class="sxs-lookup"><span data-stu-id="a8166-147">We fixed an issue where after booting PowerPoint, inserting a slide and opening and closing the comments pane, the slides in the thumbnail pane displayed as being overlapped.</span></span>


- <span data-ttu-id="a8166-148">我們已修正插入影片的功能已停用的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-148">We fixed an issue where the functionality to insert a video was disabled.</span></span>


- <span data-ttu-id="a8166-149">我們已修正影片在投影片放映中無法自動播放的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-149">We fixed an issue where videos were not playing automatically in slideshows.</span></span>


### <a name="project"></a><span data-ttu-id="a8166-150">Project</span><span class="sxs-lookup"><span data-stu-id="a8166-150">Project</span></span>

- <span data-ttu-id="a8166-151">我們修正了如果資源有多個成本費率表的問題，則剩餘成本可能無法被正確計算.</span><span class="sxs-lookup"><span data-stu-id="a8166-151">We fixed an issue where if a resource has multiple cost rate tables, the remaining cost may not be calculated correctly.</span></span>


- <span data-ttu-id="a8166-152">我們已修正連結至 SharePoint 工作清單的專案的專案完成日期不會更新的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-152">We fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>


### <a name="visio"></a><span data-ttu-id="a8166-153">Visio</span><span class="sxs-lookup"><span data-stu-id="a8166-153">Visio</span></span>

- <span data-ttu-id="a8166-154">客戶回報文字對齊會在即時預覽時發生當機。</span><span class="sxs-lookup"><span data-stu-id="a8166-154">Live preview crashes on text alignment reported by customers.</span></span> <span data-ttu-id="a8166-155">7 月分支所發生最多的當機情況。</span><span class="sxs-lookup"><span data-stu-id="a8166-155">Top hitting crash of July fork.</span></span>


### <a name="word"></a><span data-ttu-id="a8166-156">Word</span><span class="sxs-lookup"><span data-stu-id="a8166-156">Word</span></span>

- <span data-ttu-id="a8166-157">我們修正了一個問題, 即使用者點擊註解，註解卡將在註解文周圍顯示邊框。</span><span class="sxs-lookup"><span data-stu-id="a8166-157">We fixed an issue where the Comment card would display a border around the comment text if the user clicked on the comment.</span></span>


- <span data-ttu-id="a8166-158">我們已修正項目符號圖片無法正確顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-158">We fixed an issue where the bullet picture icon didn't display correctly.</span></span>


- <span data-ttu-id="a8166-159">我們已修正使用者在選取註解時無法退出頁首/頁尾的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-159">We fixed an issue where the user could not exit the Header/Footer when selecting a comment.</span></span>


- <span data-ttu-id="a8166-160">我們已修正刪除註解之後 Word 可能會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-160">We fixed an issue where Word could crash after comments were deleted.</span></span>


- <span data-ttu-id="a8166-161">我們修復了一個問題，即如果使用者建立的評論草稿, 錨定在已包含提交的評論行上，則在SideTrack與提交評論相關的草案則以錯誤的順序排列。</span><span class="sxs-lookup"><span data-stu-id="a8166-161">We fixed an issue where if a user created a comment draft anchored to a line already containing committed comments, then the draft was arranged in the wrong order relative to the committed comment in the SideTrack.</span></span>


- <span data-ttu-id="a8166-162">我們修正了一個問題, 即如將文件縮放到160％或更高, 且註解窗格不可見，焦點將不會移至註解窗格。</span><span class="sxs-lookup"><span data-stu-id="a8166-162">We fixed an issue where the focus would not go to the comment pane if the document was zoomed to 160% or more and the comment pane was not visible.</span></span>


- <span data-ttu-id="a8166-163">我們已修正一個問題，該問題造成使用者無法看到超出邊界的註解，因為在邊界中無法下拉。</span><span class="sxs-lookup"><span data-stu-id="a8166-163">We fixed an issue that prevented users from seeing comment threads that exceeded the sidetrack boundary because scrolling through the sidetrack was not working.</span></span>


- <span data-ttu-id="a8166-164">我們修正了在邊界窗格中，搜尋已解決的註解無法正常運作的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-164">We fixed an issue where searching for resolved comments in the sidetrack pane was not working.</span></span>


- <span data-ttu-id="a8166-165">我們修復了一個問題，即在多個打開的文件之間切換後，一個文件的註解會顯示在其他打開的文檔上。</span><span class="sxs-lookup"><span data-stu-id="a8166-165">We fixed an issue where the comments on one document would be displayed on other open documents after switching between the multiple open documents.</span></span>


- <span data-ttu-id="a8166-166">我們已修正將文件儲存成 HTML 格式時，長連結無法換行的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-166">We fixed an issue where long links were not being wrapped when saving document to HTML format.</span></span>


- <span data-ttu-id="a8166-167">我們已修正在某些情況下，項目符號無法在電子郵件中正確顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-167">We fixed an issue where in some cases, bullets are not displaying correctly in email.</span></span>


- <span data-ttu-id="a8166-168">我們已修正 AutoOpen 會在 AutoExec 之前執行的巨集問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-168">We fixed an issue with macros in which AutoOpen runs before AutoExec.</span></span>


### <a name="office-suite"></a><span data-ttu-id="a8166-169">Office 套件</span><span class="sxs-lookup"><span data-stu-id="a8166-169">Office Suite</span></span>

- <span data-ttu-id="a8166-170">我們修正了 Office 部署工具中的一個問題，該問題是，在 Microsoft Office 2007 [Microsoft 應用程式錯誤回報工具] 產品存在的情況下使用 RemoveMSI 功能時設定失敗。</span><span class="sxs-lookup"><span data-stu-id="a8166-170">We fixed an issue in the Office Deployment Tool where configuration was failing when using the RemoveMSI feature with the Office 2007 "Microsoft Application Error Reporting" product present.</span></span>


- <span data-ttu-id="a8166-171">我們在 [壓縮圖片] 對話方塊中，修正了某些使用者選取的 DPI 設定無法保留的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-171">We fixed an issue in the Compress Picture dialog where some user-selected DPI settings are not retained.</span></span>


- <span data-ttu-id="a8166-172">此變更解決 [壓縮圖片] 對話方塊無法保留特定使用者設定的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-172">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-september-04"></a><span data-ttu-id="a8166-174">版本2008：9月 4日</span><span class="sxs-lookup"><span data-stu-id="a8166-174">Version 2008: September 04</span></span>
<span data-ttu-id="a8166-175">*版本2008（組建13127.20378）*</span><span class="sxs-lookup"><span data-stu-id="a8166-175">*Version 2008 (Build 13127.20378)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="a8166-177">解決的問題</span><span class="sxs-lookup"><span data-stu-id="a8166-177">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="a8166-178">Office 套件</span><span class="sxs-lookup"><span data-stu-id="a8166-178">Office Suite</span></span>

- <span data-ttu-id="a8166-179">此變更解決 [壓縮圖片] 對話方塊無法保留特定使用者設定的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-179">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-september-02"></a><span data-ttu-id="a8166-181">版本 2008：9 月 2 日</span><span class="sxs-lookup"><span data-stu-id="a8166-181">Version 2008: September 02</span></span>
<span data-ttu-id="a8166-182">*版本2008（組建13127.20360）*</span><span class="sxs-lookup"><span data-stu-id="a8166-182">*Version 2008 (Build 13127.20360)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="a8166-184">功能更新</span><span class="sxs-lookup"><span data-stu-id="a8166-184">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a8166-185">Excel</span><span class="sxs-lookup"><span data-stu-id="a8166-185">Excel</span></span>

- <span data-ttu-id="a8166-186">**將圖形另存為圖片：** 只要按幾下，即可將圖形、圖示或其他物件另存成圖片，便於您於任何其他地方使用。</span><span class="sxs-lookup"><span data-stu-id="a8166-186">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="a8166-187">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8166-187">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="a8166-188">**使用 Excel 手寫筆進行快速編輯：**[手寫筆工具] 可協助您手寫並快速編輯資料</span><span class="sxs-lookup"><span data-stu-id="a8166-188">**Make quick edits using the Excel pen:** Pen Tool to help you handwrite and make quick edits to your data</span></span>



[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="a8166-191">解決的問題</span><span class="sxs-lookup"><span data-stu-id="a8166-191">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a8166-192">Excel</span><span class="sxs-lookup"><span data-stu-id="a8166-192">Excel</span></span>

- <span data-ttu-id="a8166-193">已修正使用 [複製格式] 時，某些情況下，Excel 可能會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-193">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>


### <a name="word"></a><span data-ttu-id="a8166-194">Word</span><span class="sxs-lookup"><span data-stu-id="a8166-194">Word</span></span>

- <span data-ttu-id="a8166-195">我們已修正基本樣式並未以 [內文樣式] 更新的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-195">We fixed an issue which the base styles are not updated with Normal style.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-august-27"></a><span data-ttu-id="a8166-197">版本2008：8月27日</span><span class="sxs-lookup"><span data-stu-id="a8166-197">Version 2008: August 27</span></span>
<span data-ttu-id="a8166-198">*版本2008（組建13127.20296）*</span><span class="sxs-lookup"><span data-stu-id="a8166-198">*Version 2008 (Build 13127.20296)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="a8166-202">解決的問題</span><span class="sxs-lookup"><span data-stu-id="a8166-202">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="a8166-203">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-203">Outlook</span></span>

- <span data-ttu-id="a8166-204">修正導致使用者嘗試從次要帳戶建立會議邀請的問題，讓帳戶新增至他們的個人檔案，而不會看到空白的表格: 是欄位而不是其電子郵件地址。</span><span class="sxs-lookup"><span data-stu-id="a8166-204">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>

- <span data-ttu-id="a8166-205">修正了新增共用信箱之後，導致使用者無法連線至公用資料夾的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-205">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>

- <span data-ttu-id="a8166-206">修正了當與雲端附件互動時，導致使用者偶爾當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-206">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>

- <span data-ttu-id="a8166-207">修正了編輯收件者時，導致使用者偶爾當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-207">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="a8166-208">修正導致使用者在使用壓縮模式時發生異常的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-208">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>

### <a name="word"></a><span data-ttu-id="a8166-209">Word</span><span class="sxs-lookup"><span data-stu-id="a8166-209">Word</span></span>

- <span data-ttu-id="a8166-210">此更改解決了一個問題，即在上一個協同合作的作業後，Microsoft Office 應用程式可能卡在未通知的儲存失敗狀態的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-210">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>

- <span data-ttu-id="a8166-211">我們已修正整體的 AutoOpen 在 AutoExec 之前執行的問題</span><span class="sxs-lookup"><span data-stu-id="a8166-211">We fixed an issue where macro AutoOpen runs before AutoExec</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-august-25"></a><span data-ttu-id="a8166-213">版本 2008：8 月 25 日</span><span class="sxs-lookup"><span data-stu-id="a8166-213">Version 2008: August 25</span></span>
<span data-ttu-id="a8166-214">*版本 2008 (組建 13127.20268)*</span><span class="sxs-lookup"><span data-stu-id="a8166-214">*Version 2008 (Build 13127.20268)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="a8166-216">功能更新</span><span class="sxs-lookup"><span data-stu-id="a8166-216">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a8166-217">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-217">Outlook</span></span>

- <span data-ttu-id="a8166-218">**依人員搜尋時，收到電子郵件的建議：** 當您在 Outlook 中輸入搜尋字詞時，您會在建議中看到出現最相關的電子郵件。</span><span class="sxs-lookup"><span data-stu-id="a8166-218">**Receive email suggestions when searching by person.:** As you type your search terms in Outlook you'll receive the most relevant emails surfaced in the suggestions.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="a8166-221">解決的問題</span><span class="sxs-lookup"><span data-stu-id="a8166-221">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="a8166-222">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-222">Outlook</span></span>

- <span data-ttu-id="a8166-223">解決會導致使用者在回覆或撰寫新電子郵件時收到下列錯誤的問題：「這個網頁中的某些檔案不存在預期的位置，</span><span class="sxs-lookup"><span data-stu-id="a8166-223">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="a8166-224">請問您一定要下載嗎?</span><span class="sxs-lookup"><span data-stu-id="a8166-224">Do you want to download them anyway?</span></span> <span data-ttu-id="a8166-225">如果您確定網頁來自信任的來源，請按 [是]」</span><span class="sxs-lookup"><span data-stu-id="a8166-225">If you’re sure the Web page is from a trusted source, click Yes"</span></span>


### <a name="project"></a><span data-ttu-id="a8166-226">Project</span><span class="sxs-lookup"><span data-stu-id="a8166-226">Project</span></span>

- <span data-ttu-id="a8166-227">修正如果資源中定義了多個成本費率表，其餘成本並不一定都能正確地計算的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-227">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>


### <a name="word"></a><span data-ttu-id="a8166-228">Word</span><span class="sxs-lookup"><span data-stu-id="a8166-228">Word</span></span>

- <span data-ttu-id="a8166-229">解決會導致使用者在回覆或撰寫新電子郵件時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-229">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-august-17"></a><span data-ttu-id="a8166-231">版本2008：8月17日</span><span class="sxs-lookup"><span data-stu-id="a8166-231">Version 2008: August 17</span></span>
<span data-ttu-id="a8166-232">*版本2008（組建13127.20208）*</span><span class="sxs-lookup"><span data-stu-id="a8166-232">*Version 2008 (Build 13127.20208)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="a8166-234">解決的問題</span><span class="sxs-lookup"><span data-stu-id="a8166-234">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="a8166-235">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-235">Outlook</span></span>

- <span data-ttu-id="a8166-236">解決了當代理人在某些情況下遭到拒絕而導致會議無法從經理的行事曆中移除的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-236">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>


- <span data-ttu-id="a8166-237">解決了導致某些字元集的使用者在將 [智慧型連結] 新增至 SharePoint 檔案時，發現檔案名不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-237">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>


- <span data-ttu-id="a8166-238">解決了當您從 POP 帳戶刪除4或多個電子郵件時，已選取 [僅下載標題] 選項時，導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-238">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>


- <span data-ttu-id="a8166-239">解決的問題導致在搜尋控制項中無法顯示滑鼠右鍵功能表。</span><span class="sxs-lookup"><span data-stu-id="a8166-239">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>



[//]: # (請勿移除 BUGDETAILS 內容尾)

## <a name="version-2008-august-11"></a><span data-ttu-id="a8166-241">版本 2008: 8月11日</span><span class="sxs-lookup"><span data-stu-id="a8166-241">Version 2008: August 11</span></span>
<span data-ttu-id="a8166-242">*版本2008（組建13127.20164）*</span><span class="sxs-lookup"><span data-stu-id="a8166-242">*Version 2008 (Build 13127.20164)*</span></span>

<span data-ttu-id="a8166-243">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="a8166-243">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="a8166-245">解決的問題</span><span class="sxs-lookup"><span data-stu-id="a8166-245">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="a8166-246">Access</span><span class="sxs-lookup"><span data-stu-id="a8166-246">Access</span></span>

- <span data-ttu-id="a8166-247">此修正會解決嘗試執行之前會產生「查詢太複雜」錯誤訊息的特定查詢的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-247">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>

- <span data-ttu-id="a8166-248">如果您已安装 Office 365，您就不需要再安装 [ACE 可再發行引擎]，就能在 Office 生態友善系統外公開 ACE。</span><span class="sxs-lookup"><span data-stu-id="a8166-248">If you have Office 365 installed, you no longer need to install our ACE Redistributable Engine to expose ACE outside of the Office ecosystem.</span></span> <span data-ttu-id="a8166-249">因此，如果您使用的是 Office 365，您將不需要 [ACE 可再發行引擎]，也因此不會再遭遇此問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-249">Therefore, for those with Office 365, you will no longer need the ACE Redist Engine, and consequently you should not experience this issue.</span></span>

- <span data-ttu-id="a8166-250">已解决此問題 - 您現在可以使用 Office 的隨選即用應用程式外的 ODBC 驅動程式。</span><span class="sxs-lookup"><span data-stu-id="a8166-250">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>

### <a name="excel"></a><span data-ttu-id="a8166-251">Excel</span><span class="sxs-lookup"><span data-stu-id="a8166-251">Excel</span></span>

- <span data-ttu-id="a8166-252">我們已修正若圖表數列順序已變更，與該數列對齊的對應核取方塊未隨著該數列重新排序的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-252">We fixed an issue where if the order of a chart series was changed, the corresponding checkbox aligned with the series was not reordered along with the series.</span></span>

- <span data-ttu-id="a8166-253">嘗試使用 LET () 函數儲存含有公式的檔案時，可能會發生錯誤。</span><span class="sxs-lookup"><span data-stu-id="a8166-253">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>

- <span data-ttu-id="a8166-254">我們修正了當透過 VBA 啟用活頁簿的 [ForceFullCalculation] 時，圖表不一會更新的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-254">We fixed an issue where charts were not always updated as expected when "ForceFullCalculation" was enabled via VBA for the workbook.</span></span>

- <span data-ttu-id="a8166-255">我們已修正具有放射狀漸層填滿的影像複本與原始不符的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-255">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

### <a name="onenote"></a><span data-ttu-id="a8166-256">OneNote</span><span class="sxs-lookup"><span data-stu-id="a8166-256">OneNote</span></span>

- <span data-ttu-id="a8166-257">我們修正了當應用程式視窗調整為小尺寸時，[搜尋] 編輯方塊中的預留位置文字發生溢出的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-257">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>

### <a name="outlook"></a><span data-ttu-id="a8166-258">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-258">Outlook</span></span>

- <span data-ttu-id="a8166-259">我們修正了從相同的電子郵件網域在 Outlook 中建立多個設定檔會產生的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-259">We fixed an issue around creating multiple profiles in Outlookfrom the same email domain.</span></span>

- <span data-ttu-id="a8166-260">解决了導致使用 [共用行事曆改善] 的某些使用者無法查看剛新增的共用行事曆的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-260">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="a8166-261">解決了導致在 S/MIME 加密郵件的頁首中無法顯示鎖定圖示的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-261">Addressed an issue that caused the lock icon to fail to display in the header of S/MIME encrypted messages.</span></span>

- <span data-ttu-id="a8166-262">我們已修正，如果未核取 [下載共用資料夾]，共用行事曆會議 [回覆選項] 中缺少 [允許轉寄] 選項的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-262">We fixed an issue where the "Allow Forwarding" option was missing from the shared calendar meeting "Response Options" if Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="a8166-263">解決了當選取安全性對話方塊上的 [儲存] 選項時，導致使用者無法將 OneDrive 外部的 OneDrive 附件儲存至他們的本機電腦的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-263">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="a8166-264">我們已修正，即使使用者具有適當的列印權限也會在停用狀態下顯示列印按鈕的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-264">We fixed an issue that would display the print button in a disabled state even though the user had the appropriate print permissions.</span></span>

- <span data-ttu-id="a8166-265">解決了當以未加密郵件進行傳送時，會導致附件從 S/MIME 郵件中剝離出來的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-265">Addressed an issue that caused attachments to get stripped from S/MIME messages when sending as unencrypted.</span></span>

- <span data-ttu-id="a8166-266">解決了當純文字 S/MIME 郵件在傳送時發生亂碼的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-266">Addressed an issue that caused plain text S/MIME messages to become garbled when sending.</span></span>

- <span data-ttu-id="a8166-267">解決了當傳送未加密的 S/MIME 電子郵件時，會導致附件損毀的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-267">Addressed an issue that caused attachments to become corrupted when sending an S/MIME email unencrypted.</span></span>

- <span data-ttu-id="a8166-268">解決了當寄件者授與 [另存為] 許可權時，會導致收件者無法儲存許可權保護郵件的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-268">Addressed an issue that cause recipients to be unable to save rights protected messages even when the save as permission was granted by the sender.</span></span>

- <span data-ttu-id="a8166-269">這解決了當使用者從檢查程式視窗回覆受到數位版權管理的郵件，卻沒有所回覆郵件的擁有者權限時，會導致使用者會無法新增簽名的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-269">This fix addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user did not have Owner permissions on the message being replied to.</span></span>

- <span data-ttu-id="a8166-270">此修正會解決導致 Outlook 無法在 markdown 內容中正確顯示換行符號的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-270">This fix addresses an issue that was causing Outlook to fail to display line breaks properly in markdown content.</span></span>

- <span data-ttu-id="a8166-271">解決了某些 [進階搜尋] 選項標籤在某些語言中會被截斷的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-271">Addressed an issue that caused the labels for some Advanced Search options to be truncated in some languages.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8166-272">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8166-272">PowerPoint</span></span>

- <span data-ttu-id="a8166-273">我們已修正具有放射狀漸層填滿的影像複本與原始不符的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-273">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

- <span data-ttu-id="a8166-274">我們已修正 PowerPoint 中的 [表單] 按鈕在不允許存取 Office Store 時不會允許建立表單的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-274">We fixed an issue where the Forms button in PowerPoint did not allow the creation of Forms when access to Office Store was not permitted.</span></span>

### <a name="project"></a><span data-ttu-id="a8166-275">Project</span><span class="sxs-lookup"><span data-stu-id="a8166-275">Project</span></span>

- <span data-ttu-id="a8166-276">我們修正了 [工作委員會] 畫面中列出的工作未與 [指派資源] 對話方塊中的任務同步處理的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-276">We fixed an issue where tasks listed in the Task Board view were not in sync with those in the Assign Resources dialog.</span></span>

- <span data-ttu-id="a8166-277">我們修正了如果您嘗試從 Project 將 PDF/XPS 儲存至 SharePoint 文件庫，沒有發生任何動作的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-277">We fixed an issue where if you tried to save a PDF/XPS from Project to a SharePoint document library, nothing would happen.</span></span>

- <span data-ttu-id="a8166-278">我們修正了當您複製並貼上具有多個相關性的工作，並非所有相關性都能正確複製的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-278">We fixed an issue where if you copied & pasted a task that had multiple dependencies, not all dependencies were copied correctly.</span></span>

- <span data-ttu-id="a8166-279">已修正針對 SharePoint 工作清單，第二個索引標籤上的功能區按鈕可能會停用的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-279">Fixed an issue where for a SharePoint tasks list, the ribbon buttons on the second tab may be disabled.</span></span>

### <a name="skype"></a><span data-ttu-id="a8166-280">Skype</span><span class="sxs-lookup"><span data-stu-id="a8166-280">Skype</span></span>

- <span data-ttu-id="a8166-281">將跳舞表情符號膚色變更為中性色彩</span><span class="sxs-lookup"><span data-stu-id="a8166-281">Changed dancing emoticon skin tone to neutral color</span></span>

### <a name="visio"></a><span data-ttu-id="a8166-282">Visio</span><span class="sxs-lookup"><span data-stu-id="a8166-282">Visio</span></span>

- <span data-ttu-id="a8166-283">在此修正程序完成之后，如果使用者在任何機制（在此情况下是透過增益集）停止執行刪除命令，內存便不會泄漏，而且也不會影響整台電腦。</span><span class="sxs-lookup"><span data-stu-id="a8166-283">After this fix, if the user halted the execution of delete command by any mechanism in between (in this case it was through add-in) the memory won't leak and the whole machine won't be impacted.</span></span>

### <a name="word"></a><span data-ttu-id="a8166-284">Word</span><span class="sxs-lookup"><span data-stu-id="a8166-284">Word</span></span>

- <span data-ttu-id="a8166-285">我們已修正將某些文字及影像貼到 [註解] 方塊之後，Word 停止回應的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-285">We fixed an issue where Word would stop responding after pasting some text and an image in to a comments box.</span></span>

- <span data-ttu-id="a8166-286">我們已修正具有放射狀漸層填滿的影像複本與原始不符的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-286">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

- <span data-ttu-id="a8166-287">我們修正了當應用程式視窗調整為小尺寸時，[搜尋] 編輯方塊中的預留位置文字發生溢出的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-287">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>

- <span data-ttu-id="a8166-288">我們已修正如果新增註解來追蹤變更，將會意外開啟 [修訂] 窗格的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-288">We fixed an issue where if a comment was added to track a change, the revisions pane would unexpectedly open.</span></span>

- <span data-ttu-id="a8166-289">我們修正了當焦點位於註解文字方塊中時，[編輯器] 命令會被停用的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-289">We fixed an issue where the Editor command was disabled when the focus was in a comment text box.</span></span>

- <span data-ttu-id="a8166-290">我們修正了當焦點位於註解文字方塊中時，[顯示標記] 命令會被停用的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-290">We fixed an issue where the Show Markup command was disabled when the focus was in a comment text box.</span></span>

- <span data-ttu-id="a8166-291">我們已修正刪除最後一個註解後，[新增批註] 按鈕停用的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-291">We fixed an issue where the 'New comment' button would be disabled after deleting the last comment.</span></span>

- <span data-ttu-id="a8166-292">我們已修正 [追蹤修訂] 中的 [特定人員] 選項已停用的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-292">We fixed an issue where the 'Specific People' option for Track Changes was disabled.</span></span>

- <span data-ttu-id="a8166-293">我們已修正文件連結未透過 [插入] > [連結] 下拉式功能表插入 [註解] 方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-293">We fixed an issue where links to documents were not being inserted to the comments box via the Insert -> Link dropdown.</span></span>

- <span data-ttu-id="a8166-294">我們已修正了開啟 HTML 檔案時偶爾停止回應的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-294">We fixed an occasional hang while opening HTML files.</span></span>

- <span data-ttu-id="a8166-295">我們修正了自訂 XML 中的註解狀態在開啟文件時可能會遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-295">We fixed an issue in custom XML where the state of comments may be lost when opening the document.</span></span>

- <span data-ttu-id="a8166-296">我們已修正 VBA 超連結集合中的超連結計數，在新增包含超連結的影像之後，未正確反覆運算的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-296">We fixed an issue where the hyperlink count in the VBA hyperlinks collection was not iterating correctly after adding an image containing a hyperlink.</span></span>

- <span data-ttu-id="a8166-297">針對舊版非網頁服務的 [共用] 窗格，在開啟 [共用] 窗格下關閉文件時，可能會導致當機。</span><span class="sxs-lookup"><span data-stu-id="a8166-297">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash.</span></span> <span data-ttu-id="a8166-298">這個問題現在已經修正。</span><span class="sxs-lookup"><span data-stu-id="a8166-298">This is now fixed.</span></span>

- <span data-ttu-id="a8166-299">我們修正了使用者從工作列開啟新應用程式視窗，並建立新的空白檔時，會造成額外檔案建立的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-299">We fixed an issue where after the user opened a new app window from the taskbar and created a new blank document, additional files were created.</span></span>

- <span data-ttu-id="a8166-300">我們修正了當使用者在編輯文件，但是許可權遺失時，我們並未通知使用者必須重新驗證的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-300">We fixed an issue where if a user was editing a document but had lost permissions, we were not notifying the user that they had to re-authenticate.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-august-05"></a><span data-ttu-id="a8166-302">版本 2007：8 月 5 日</span><span class="sxs-lookup"><span data-stu-id="a8166-302">Version 2007: August 05</span></span>
<span data-ttu-id="a8166-303">*版本 2007 (組建 13029.20344)*</span><span class="sxs-lookup"><span data-stu-id="a8166-303">*Version 2007 (Build 13029.20344)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)



[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="a8166-307">解決的問題</span><span class="sxs-lookup"><span data-stu-id="a8166-307">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="a8166-308">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-308">Outlook</span></span>

- <span data-ttu-id="a8166-309">解決會導致 Outlook 無法擷取搜尋建議的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-309">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>


- <span data-ttu-id="a8166-310">解決會導致使用者在擷取角色資訊時有時候會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-310">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>


### <a name="project"></a><span data-ttu-id="a8166-311">Project</span><span class="sxs-lookup"><span data-stu-id="a8166-311">Project</span></span>

- <span data-ttu-id="a8166-312">修正無法開啟已進入錯誤狀態的專案的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-312">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-july-29"></a><span data-ttu-id="a8166-314">版本 2007：7 月 29 日</span><span class="sxs-lookup"><span data-stu-id="a8166-314">Version 2007: July 29</span></span>
<span data-ttu-id="a8166-315">*版本 2007 (組建 13029.20308)*</span><span class="sxs-lookup"><span data-stu-id="a8166-315">*Version 2007 (Build 13029.20308)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="a8166-317">功能更新</span><span class="sxs-lookup"><span data-stu-id="a8166-317">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a8166-318">Excel</span><span class="sxs-lookup"><span data-stu-id="a8166-318">Excel</span></span>

- <span data-ttu-id="a8166-319">**使用資料類型從 Power BI 取得組織資料：** 現在，來自 Power BI 的 Excel 資料類型將推出給使用 Office 365 E5/A5 或 Microsoft 365 E5/A5 之組織的測試人員使用。</span><span class="sxs-lookup"><span data-stu-id="a8166-319">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 E5/A5 or Microsoft 365 E5/A5.</span></span> <span data-ttu-id="a8166-320">取得您所需的資訊，輕鬆地重新整理，對許多日常工作流程而言至關重要。</span><span class="sxs-lookup"><span data-stu-id="a8166-320">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="a8166-321">我們允許您透過 Excel 中的資料類型從 Power BI 存取公司或組織資訊，從而擴充您在試算表中引入連結資訊的能力。</span><span class="sxs-lookup"><span data-stu-id="a8166-321">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="a8166-322">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8166-322">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="a8166-323">在[部落格文章](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="a8166-323">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="a8166-324">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-324">Outlook</span></span>

- <span data-ttu-id="a8166-325">**挑選搜尋的位置：** 新的搜尋範圍下拉式清單，可讓您更輕鬆地修改搜尋，並在目前資料夾和目前信箱之間切換。</span><span class="sxs-lookup"><span data-stu-id="a8166-325">**Pick where to search:** The new search scope drop down allows you to more easily modify your search and switch between Current Folder and Current Mailbox.</span></span> <span data-ttu-id="a8166-326">感謝每個在 [即將推出] 為 [頂極體驗] 的 新 [搜尋] 提供意見反應的人。</span><span class="sxs-lookup"><span data-stu-id="a8166-326">Thank you to everyone in Coming Soon who provided feedback on the new Search at Top experience.</span></span> <span data-ttu-id="a8166-327">因為有這份意見反應，才有這項設計與更新！</span><span class="sxs-lookup"><span data-stu-id="a8166-327">This design and update came out of that feedback!</span></span>

### <a name="word"></a><span data-ttu-id="a8166-328">Word</span><span class="sxs-lookup"><span data-stu-id="a8166-328">Word</span></span>

- <span data-ttu-id="a8166-329">**以新式註解更輕鬆地進行共同作業：** 新增註解到物件、@提及 同事，並解決註解執行緒，以獲得更佳的共同作業體驗。</span><span class="sxs-lookup"><span data-stu-id="a8166-329">**Better collaboration with modern comments:** Add comments to objects, @mention colleagues, and resolve comment threads for a better collaboration experience.</span></span> [<span data-ttu-id="a8166-330">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8166-330">Learn more</span></span>](https://support.office.com/article/8d3f868a-867e-4df2-8c68-bf96671641e2)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="a8166-333">解決的問題</span><span class="sxs-lookup"><span data-stu-id="a8166-333">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="a8166-334">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-334">Outlook</span></span>

- <span data-ttu-id="a8166-335">解決了導致 CLP 使用者在從受保護的內容切換到未受保護之回復的 [寄件者] 位址時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-335">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>


- <span data-ttu-id="a8166-336">解決了導致 [排程小幫手] 頁面無法顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-336">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>


- <span data-ttu-id="a8166-337">解決了事件通知提醒中導致格式設定問題的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-337">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-july-27"></a><span data-ttu-id="a8166-339">版本 2007：7 月 27 日</span><span class="sxs-lookup"><span data-stu-id="a8166-339">Version 2007: July 27</span></span>
<span data-ttu-id="a8166-340">*Version 2007 (組建 13029.20292)*</span><span class="sxs-lookup"><span data-stu-id="a8166-340">*Version 2007 (Build 13029.20292)*</span></span>
* <span data-ttu-id="a8166-341">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="a8166-341">Various bugs and performance fixes.</span></span>

## <a name="version-2007-july-20"></a><span data-ttu-id="a8166-342">版本 2007：7 月 20 日</span><span class="sxs-lookup"><span data-stu-id="a8166-342">Version 2007: July 20</span></span>
<span data-ttu-id="a8166-343">*版本2007 (組建 13029.20236)*</span><span class="sxs-lookup"><span data-stu-id="a8166-343">*Version 2007 (Build 13029.20236)*</span></span>
* <span data-ttu-id="a8166-344">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="a8166-344">Various bugs and performance fixes.</span></span>

## <a name="version-2007-july-15"></a><span data-ttu-id="a8166-345">版本 2007：7 月 15 日</span><span class="sxs-lookup"><span data-stu-id="a8166-345">Version 2007: July 15</span></span>
<span data-ttu-id="a8166-346">*版本 2007 (組建 13029.20200)*</span><span class="sxs-lookup"><span data-stu-id="a8166-346">*Version 2007 (Build 13029.20200)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="a8166-348">功能更新</span><span class="sxs-lookup"><span data-stu-id="a8166-348">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a8166-349">Excel</span><span class="sxs-lookup"><span data-stu-id="a8166-349">Excel</span></span>

- <span data-ttu-id="a8166-350">**在 Excel 中製作精美的 Visio 圖表：** 將資料放在工作表上，以建立流程圖或組織圖。</span><span class="sxs-lookup"><span data-stu-id="a8166-350">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="a8166-351">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8166-351">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="a8166-354">解決的問題</span><span class="sxs-lookup"><span data-stu-id="a8166-354">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="a8166-355">Access</span><span class="sxs-lookup"><span data-stu-id="a8166-355">Access</span></span>

- <span data-ttu-id="a8166-356">我們已修正在重新整理連結的 SQL 資料表時，連結資料表管理員會提示您輸入主要索引鍵的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-356">We fixed an issue where the linked table manager would prompt a primary key if a linked SQL table was refreshed.</span></span>

- <span data-ttu-id="a8166-357">我們已修正 [查詢編輯器] 中的查詢捲出畫面的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-357">We fixed an issue where queries in the Query Editor scrolled out of view.</span></span>

- <span data-ttu-id="a8166-358">我們已修正執行查詢的時間大約比預期完成時間兩倍久的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-358">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

- <span data-ttu-id="a8166-359">我們已修正導致 Microsoft Access 無法識別連結的 SQL Server 資料表中的識別資料行的問題，這可能會導致不正確地將資料列報告為已刪除。</span><span class="sxs-lookup"><span data-stu-id="a8166-359">We fixed an issue that caused Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which could cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="a8166-360">Excel</span><span class="sxs-lookup"><span data-stu-id="a8166-360">Excel</span></span>

- <span data-ttu-id="a8166-361">我們已修正非 HTTP 或 HTTPS 型 URL 未顯示在 [最近用過的] 清單中的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-361">We fixed an issue where URLs that were not http or https based were not being displayed in the Most Recently Used list.</span></span>

- <span data-ttu-id="a8166-362">已修正在載入含有多張分頁預覽的活頁簿時，可能會發生錯誤或當機問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-362">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>

- <span data-ttu-id="a8166-363">我們修正以下問題：在特定版本 Excel 中建立的資料模型表格無法在 [表格預覽] 中看到，即使與該表相關聯的查詢尚未編輯。</span><span class="sxs-lookup"><span data-stu-id="a8166-363">We fixed an issue where data model tables created in certain versions of Excel could not be seen in 'Table Preview' even though the query associated with the table had not been edited.</span></span>

- <span data-ttu-id="a8166-364">在 [定義名稱\套用名稱] 對話方塊中停用 [忽略相對/絕對] 參照會導致公式無法使用。</span><span class="sxs-lookup"><span data-stu-id="a8166-364">Ignore Relative/Absolute' references in the Define Name \ Apply Names dialog would cause formulas to not work.</span></span>

- <span data-ttu-id="a8166-365">我們已修正將活頁簿儲存至 SharePoint/OneDrive 時，會導致自訂功能區索引標籤 CustomUI XML 遭移除的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-365">We fixed an issue where CustomUI XML for a custom ribbon tab was removed when saving a workbook to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="a8166-366">我們已修正當建議以唯讀方式使用檔案時，活頁簿處於唯讀狀態的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-366">We fixed an issue where workbooks were read-only when the file only had read-only recommended.</span></span>

- <span data-ttu-id="a8166-367">已修正在載入含有多張分頁預覽的活頁簿時，可能會發生錯誤或當機問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-367">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>

- <span data-ttu-id="a8166-368">我們已修正雷達圖的主要格線無法正確設定格式的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-368">We fixed an issue where the major gridlines of radar charts could not be formatted correctly.</span></span>


- <span data-ttu-id="a8166-369">我們已修正清除 [進階資料篩選] 可能會遺失表格格式設定的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-369">We fixed an issue where clearing an advanced data filter could lose table formatting.</span></span>


- <span data-ttu-id="a8166-370">我們已修正嵌入式 PDF 文件的完整路徑顯示在文件標題，而不只是檔案名稱的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-370">We fixed an issue where the full path of an embedded PDF document would show in the document caption rather than just the filename.</span></span>


- <span data-ttu-id="a8166-371">我們已修正停用 Wolfram 雲端連接器之後，儲存並重新開啟 Excel 活頁簿可能會導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-371">We fixed an issue where after disabling the Wolfram cloud connector and then saving and re-opening an Excel workbook, could result in a crash.</span></span>


- <span data-ttu-id="a8166-372">我們已修正啟動 Excel 時啟用 [規劃求解] 增益集將導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-372">We fixed an issue where booting Excel with the Solver add-in enabled would result in a crash.</span></span>


### <a name="outlook"></a><span data-ttu-id="a8166-373">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-373">Outlook</span></span>

- <span data-ttu-id="a8166-374">我們已修正如果在 [收件者] 行上有超過 130 個收件者，Outlook 會當機的問題，且我們也改善了呈現文字的效能。</span><span class="sxs-lookup"><span data-stu-id="a8166-374">We fixed an issue where Outlook would hang if there were over 130 recipients on the 'To' line and we also improved the performance of rendering the text.</span></span>


- <span data-ttu-id="a8166-375">我們已修正以下問題：當使用多個不同解析度的監視器時，輸入法編輯器 (IEM) 視窗會覆蓋透過 IME 輸入的文字。</span><span class="sxs-lookup"><span data-stu-id="a8166-375">We fixed an issue where the Input Method Editor (IME) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>


- <span data-ttu-id="a8166-376">我們已修正「待辦事項列」中跨越兩天以上的活動，在後續的所有日期中顯示相同結束時間的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-376">We fixed an issue in the 'To Do Bar' where events that spanned more than two days, displayed the same end time for all subsequent days.</span></span>


- <span data-ttu-id="a8166-377">解決會導致使用者看到他們透過拖放附件，以複製到其檔案系統所建立附件的建立日期設為 4501 年 1 月 1 日的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-377">Addresses an issue that caused users to see the creation date of attachments that they copied to their file system via drag and drop getting set to January 1, 4501.</span></span>


- <span data-ttu-id="a8166-378">我們已修正使用者無法使用通訊群組清單中的「傳送為」或「代理傳送者」的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-378">We fixed an issue where users were unable to 'Send As' or 'Send on behalf' of a distribution list.</span></span>


- <span data-ttu-id="a8166-379">解決在編輯經理行事曆上的現有行事曆約會時，導致代理人收到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-379">Addresses an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>


- <span data-ttu-id="a8166-380">我們已修正導致使用者在關閉先前儲存的約會時看到下列錯誤的問題：「項目無法儲存，因為已被其他使用者或已在其他視窗中變更過。</span><span class="sxs-lookup"><span data-stu-id="a8166-380">We fixed an issue that caused users to see the following error when closing an appointment that was previously saved "The item cannot be saved because it was changed by another user or in another window.</span></span> <span data-ttu-id="a8166-381">您要在預設資料夾為這個項目建立複本?」</span><span class="sxs-lookup"><span data-stu-id="a8166-381">Do you want to make a copy in the default folder for the item?"</span></span>


- <span data-ttu-id="a8166-382">解決會導致若「未」核取 [下載共用資料夾]，共用行事曆會議的 [回應選項] 中會遺失 [允許轉寄] 選項的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-382">Addresses an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>


- <span data-ttu-id="a8166-383">解決選取安全性對話方塊上的 [儲存] 選項時，會導致使用者無法將來自其租用戶外部的 OneDrive 附件儲存至其本機電腦的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-383">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>


- <span data-ttu-id="a8166-384">我們已修正導致 Outlook 使用者在使用共用行事曆後，在幾分鐘內訊息清單停止更新的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-384">We fixed an issue that caused users of Outlook to see their message list stop updating for several minutes after using shared calendars.</span></span>


- <span data-ttu-id="a8166-385">我們已修正行事曆提醒無法針對一週內即將到來的會議顯示確切時間的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-385">We fixed an issue that prevented calendar reminders from showing exact times for meetings coming up in less than a week.</span></span> 


- <span data-ttu-id="a8166-386">我們已修正在郵件中插入影像內嵌，然後將郵件儲存為草稿將會重新調整影像大小的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-386">We fixed an issue where inserting an image inline in a message, then saving the message as a draft would result in a resizing of the image.</span></span>


- <span data-ttu-id="a8166-387">我們已修正在編輯主旨之後，導致 NDR 郵件的本文從 Unicode 變更為 ASCII 的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-387">We fixed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>


- <span data-ttu-id="a8166-388">我們已修正迷你行事曆中的日期無法針對日本使用者顯示粗體的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-388">We fixed an issue where dates in the mini calendar failed to display in bold for users in Japan.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="a8166-389">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8166-389">PowerPoint</span></span>

- <span data-ttu-id="a8166-390">我們已修正在即時共同撰寫工作階段期間，使用者的目前狀態色彩指示器無法在共同撰寫文件庫中重新整理的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-390">We fixed an issue where a user's presence color indicator was not getting refreshed in the co-authoring gallery during a live co-authoring session.</span></span>


- <span data-ttu-id="a8166-391">我們已修正將 HTML 貼到投影片上的文字區域時，會改為貼上投影片最上方所建立的文字方塊中的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-391">We fixed an issue where pasting HTML to a text area on a slide would instead get pasted into a text box created at the top of the slide.</span></span>


- <span data-ttu-id="a8166-392">我們已修正在 [簡報者檢視畫面] 中選取所有投影片、使用 Alt+Tab 退出 [簡報者檢視畫面] 並返回投影片放映，然後按一下 [結束放映] 時，將導致未處理例外狀況的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-392">We fixed an issue where selecting all slides in Presenter View, then exiting Presenter View using Alt+Tab and returning to the slide show and clicking 'End Show' would result in an unhandled exception.</span></span>


### <a name="project"></a><span data-ttu-id="a8166-393">Project</span><span class="sxs-lookup"><span data-stu-id="a8166-393">Project</span></span>

- <span data-ttu-id="a8166-394">已修正無法將從 Project 將 PDF/XPS 儲存至 SharePoint 文件庫的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-394">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>


- <span data-ttu-id="a8166-395">修正 URL 以 .com 結尾時，無法從 Project Web App 在 Project 傳統型用戶端開啟專案的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-395">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>


- <span data-ttu-id="a8166-396">我們已修正 Project 在開啟特定 XML 檔案時可能當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-396">We fixed an issue where Project may crash when opening certain XML files.</span></span>


- <span data-ttu-id="a8166-397">我們已修正 URL 以 '.com' 結尾時，無法從 Project Web App 在 Project 傳統型用戶端開啟專案的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-397">We fixed an issue where projects couldn't be opened in the Project desktop client from the Project Web App if the URL ended in '.com'.</span></span>


- <span data-ttu-id="a8166-398">已修正問題：如果您貼上具有多個相關性的工作，並不會正確複製所有相關性。</span><span class="sxs-lookup"><span data-stu-id="a8166-398">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>


- <span data-ttu-id="a8166-399">已修正 [指派資源] 對話方塊中選取的工作與工作面板檢視中所選工作不同的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-399">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>


- <span data-ttu-id="a8166-400">我們已修正當專案摘要工作，或專案 [開始/工作] 欄位變更時，ProjectBeforeTaskChange 事件無法觸發的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-400">We fixed an issue where the ProjectBeforeTaskChange event didn't fire when there was a change to the project summary task, either the project start/task field.</span></span>


- <span data-ttu-id="a8166-401">我們已修正以下問題：如果固定工期的任務已 100% 完成，但未指定 [實際完成日期]，則任務的完成 % 將顯示為低於 100%。</span><span class="sxs-lookup"><span data-stu-id="a8166-401">We fixed an issue where if Fixed Duration tasks are at 100% complete but the Actual Finish is not specified, the Task % Complete would display as less than 100%.</span></span>

- <span data-ttu-id="a8166-402">我們已修正以下問題：比較基準重設或更新可能會變更時間分段預算成本/工時資源，且比較基準反映不正確的預算值。</span><span class="sxs-lookup"><span data-stu-id="a8166-402">We fixed an issue where a baseline reset or update could change time-phased budget cost/work resources and the baseline could reflect incorrect budget values.</span></span>


- <span data-ttu-id="a8166-403">我們已修正政府社群雲端中的 Project Planner 連結已停用的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-403">We fixed an issue where Project Planner links in Government Community Cloud environments had been disabled.</span></span>


- <span data-ttu-id="a8166-404">我們已修正如果文件庫處於新式模式，您無法從 SharePoint 文件庫開啟 Project 檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-404">We fixed an issue where you couldn't open a Project file from a SharePoint document library if the library was in modern mode.</span></span>


### <a name="word"></a><span data-ttu-id="a8166-405">Word</span><span class="sxs-lookup"><span data-stu-id="a8166-405">Word</span></span>

- <span data-ttu-id="a8166-406">我們已修正使用 Office 功能區中的 [清除格式設定] 按鈕清除 [註解] 窗格中的格式設定時，無法運作的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-406">We fixed an issue where the ability to clear formatting within the Comments pane via the Clear Formatting button in the Office Ribbon was not working.</span></span>


- <span data-ttu-id="a8166-407">我們已修正將插入可縮放向量圖形 (SVG) 中的文字插入到 Word、Excel 或 PowerPoint 檔案、儲存並關閉檔案，然後重新開啟檔案後，難以辨識的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-407">We fixed an issue where text inserted in a Scalable Vector Graphic (SVG) was illegible after inserting it in a Word, Excel, or PowerPoint file, saving and closing the file, and then re-opening the file.</span></span>


- <span data-ttu-id="a8166-408">我們已修正當尺規未顯示時變更表格大小，導致在背景中執行其他應用程式開始閃爍的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-408">We fixed an issue where changing the size of a table when the ruler is not displayed caused other applications running in the background to start flashing.</span></span>


- <span data-ttu-id="a8166-409">我們已修正在共同撰寫模式中，註解回覆有時候不會顯示在 [註解] 窗格中，而是顯示在 [修訂] 窗格中的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-409">We fixed an issue where in co-authoring mode, comment replies would sometimes not show up in the comments pane but would be visible in the revisions pane.</span></span>


- <span data-ttu-id="a8166-410">我們已修正在共同撰寫模式期間，當發生合併衝突且使用者已選取放棄變更時，我們不再顯示儲存或捨棄變更選項的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-410">We fixed an issue during co-authoring mode when there is a merge conflict and the user has already chosen to discard changes, we no longer display the option to save or discard changes.</span></span>


- <span data-ttu-id="a8166-411">我們已修正 HTML 超連結色彩無法正確呈現的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-411">We fixed an issue where the HTML hyperlink color was not being rendered correctly.</span></span>


- <span data-ttu-id="a8166-412">我們已修正以下問題：如果 Word 經常開啟的文件清單多於 50 個，然後儲存並開啟文件後，即使該文件沒有進行任何修訂，也會顯示歷程記錄。</span><span class="sxs-lookup"><span data-stu-id="a8166-412">We fixed an issue where if Word had a list of more than 50 frequently opened documents, then after saving and opening a document, a revision history would be displayed even though no revisions were made to that document.</span></span>


- <span data-ttu-id="a8166-413">我們已修正共同撰寫期間的自動儲存問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-413">We fixed in issue with autosave during coauthoring.</span></span>


- <span data-ttu-id="a8166-414">我們已修正一個問題，當嘗試使用新名稱儲存包含巨集的檔案時，無論使用者輸入什麼名稱，都會導致該檔案以 .docx 副檔名和檔案名稱 'WRO0004.docx' 儲存，進而導致文件無法使用。</span><span class="sxs-lookup"><span data-stu-id="a8166-414">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with a .docx extension and the filename 'WRO0004.docx', regardless of what the user entered, rendering the document unusable.</span></span>


### <a name="office-suite"></a><span data-ttu-id="a8166-415">Office 套件</span><span class="sxs-lookup"><span data-stu-id="a8166-415">Office Suite</span></span>

- <span data-ttu-id="a8166-416">關閉 Office 檔案時，計時問題可能會導致當機</span><span class="sxs-lookup"><span data-stu-id="a8166-416">A timing issue could cause a crash when closing office files</span></span>

- <span data-ttu-id="a8166-417">此問題的修正程式是確保服務正確計算新增的產品。</span><span class="sxs-lookup"><span data-stu-id="a8166-417">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="a8166-418">我們已篩選出新增的產品 (確保它們同時存在於新的設定中)，並將它們新增到現有產品發行識別碼的結尾。</span><span class="sxs-lookup"><span data-stu-id="a8166-418">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-july-09"></a><span data-ttu-id="a8166-420">版本 2006：7 月 09 日</span><span class="sxs-lookup"><span data-stu-id="a8166-420">Version 2006: July 09</span></span>
<span data-ttu-id="a8166-421">*版本2006（組建13001.20384）*</span><span class="sxs-lookup"><span data-stu-id="a8166-421">*Version 2006 (Build 13001.20384)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="a8166-423">功能更新</span><span class="sxs-lookup"><span data-stu-id="a8166-423">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a8166-424">Excel</span><span class="sxs-lookup"><span data-stu-id="a8166-424">Excel</span></span>

- <span data-ttu-id="a8166-425">**建立 PDF 連線：** 連線至、匯入、重新整理 PDF 中的資料。</span><span class="sxs-lookup"><span data-stu-id="a8166-425">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="a8166-426">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8166-426">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="a8166-427">**建立變數以在公式中使用：** 使用 LET 函數改善效能、可讀性及可組合性。</span><span class="sxs-lookup"><span data-stu-id="a8166-427">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="a8166-428">此函數可讓您在新的或現有的公式中建立命名變數。</span><span class="sxs-lookup"><span data-stu-id="a8166-428">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="a8166-429">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8166-429">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="a8166-430">在[部落格文章](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="a8166-430">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

- <span data-ttu-id="a8166-431">**Excel 中的鍵盤快速鍵：** Excel 升級的鍵盤快速鍵</span><span class="sxs-lookup"><span data-stu-id="a8166-431">**Keyboard shortcuts in Excel:** Updated keyboard shortcuts for Excel</span></span>

### <a name="outlook"></a><span data-ttu-id="a8166-432">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-432">Outlook</span></span>

- <span data-ttu-id="a8166-433">**在 Outlook 中使用 [快速投票] 建立投票：** 輕鬆建立投票，收集投票，並查看電子郵件中的結果 [深入瞭解](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="a8166-433">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="a8166-434">**將圖片作為電子郵件的一部分傳送時，讓圖片保持高畫質：** 一個新 Outlook 設定，可讓您在隨著電子郵件內容傳送圖片時限制圖片壓縮</span><span class="sxs-lookup"><span data-stu-id="a8166-434">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="a8166-437">解決的問題</span><span class="sxs-lookup"><span data-stu-id="a8166-437">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="a8166-438">Access</span><span class="sxs-lookup"><span data-stu-id="a8166-438">Access</span></span>

- <span data-ttu-id="a8166-439">此問題已解決，您應該能成功地將包含身分識別(例如 [自動編號]) 欄位的連結的 SQL 資料表插入到 Access 中。</span><span class="sxs-lookup"><span data-stu-id="a8166-439">This issue is resolved, and you should expect to be able to successfully insert linked SQL tables that include an identity (e.g. autonumber) field into Access.</span></span>

### <a name="excel"></a><span data-ttu-id="a8166-440">Excel</span><span class="sxs-lookup"><span data-stu-id="a8166-440">Excel</span></span>

- <span data-ttu-id="a8166-441">已修正當您從帳戶登出時，嘗試建立資料連線時，可能會發生的當機問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-441">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

### <a name="outlook"></a><span data-ttu-id="a8166-442">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-442">Outlook</span></span>

- <span data-ttu-id="a8166-443">解決了當選取安全性對話方塊上的 [儲存] 選項時，導致使用者無法將 OneDrive 外部的 OneDrive 附件儲存至他們的本機電腦的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-443">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a8166-444">Office 套件</span><span class="sxs-lookup"><span data-stu-id="a8166-444">Office Suite</span></span>

- <span data-ttu-id="a8166-445">我們會將新的 AppV51 向後移，以修正先前 AppV51 中的回歸。</span><span class="sxs-lookup"><span data-stu-id="a8166-445">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="a8166-446">當您啟用增益集，而登錄 TabProcGrowth 值為 REG_SZ 類型且其值為 "0"時，辦公主機視窗會當機。</span><span class="sxs-lookup"><span data-stu-id="a8166-446">he office host was crashing in windows, when an add-in is being activated while the registry TabProcGrowth value is REG_SZ type and with value "0".</span></span>  <span data-ttu-id="a8166-447">這個登錄 TabProcGrowth 值可以在下列4個路徑中的任何一個中： HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main HKEY_CURRENT_USER \Software\Policies\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINE \Software\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINER \Software\Policies\Microsoft\Internet Explorer\Main 此變更將修正此問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-447">That registry TabProcGrowth value can be under any one of 4 paths: HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main HKEY_CURRENT_USER\Software\Policies\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINE\Software\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINER\Software\Policies\Microsoft\Internet Explorer\Main This change would fix this issue.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-june-25"></a><span data-ttu-id="a8166-449">版本 2006：6 月 25 日</span><span class="sxs-lookup"><span data-stu-id="a8166-449">Version 2006: June 25</span></span>
<span data-ttu-id="a8166-450">*版本2006（組建13001.20266）*</span><span class="sxs-lookup"><span data-stu-id="a8166-450">*Version 2006 (Build 13001.20266)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="a8166-452">功能更新</span><span class="sxs-lookup"><span data-stu-id="a8166-452">Feature updates</span></span>
### <a name="visio"></a><span data-ttu-id="a8166-453">Visio</span><span class="sxs-lookup"><span data-stu-id="a8166-453">Visio</span></span>

- <span data-ttu-id="a8166-454">**在 Excel 中製作精美的 Visio 圖表：** 根據工作表上的資料，建立流程圖或組織圖。</span><span class="sxs-lookup"><span data-stu-id="a8166-454">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart based on data in a worksheet.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="a8166-457">解決的問題</span><span class="sxs-lookup"><span data-stu-id="a8166-457">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="a8166-458">Access</span><span class="sxs-lookup"><span data-stu-id="a8166-458">Access</span></span>

- <span data-ttu-id="a8166-459">這個問題已解決。</span><span class="sxs-lookup"><span data-stu-id="a8166-459">This problem is now resolved.</span></span> <span data-ttu-id="a8166-460">如果您在此流程中遇到更多問題，請告知小組。</span><span class="sxs-lookup"><span data-stu-id="a8166-460">Please let the team know if you experience more issues with this process.</span></span>


### <a name="outlook"></a><span data-ttu-id="a8166-461">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-461">Outlook</span></span>

- <span data-ttu-id="a8166-462"><span style="display:inline !important;">解決一個問題，該問題導致使用者看到<span>&nbsp;</span></span><span style="box-sizing:border-box;font-family:Calibri, sans-serif;font-size:14.6667px;display:inline !important;">附件的建立日期&nbsp; 他們透過托放方式將該附件複製到其檔案系統&nbsp; 該建立日期設於 4501年1月1日。</span></span><span class="sxs-lookup"><span data-stu-id="a8166-462"><span style="display:inline !important;">Addresses an issue that caused users to see<span>&nbsp;</span></span><span style="box-sizing:border-box;font-family:Calibri, sans-serif;font-size:14.6667px;display:inline !important;">the creation date of&nbsp; attachments that they copied to their file system via drag and drop getting&nbsp; set to January 1, 4501.</span></span></span><br>


- <span data-ttu-id="a8166-463"><span style="font-family:&quot;Segoe UI&quot;, system-ui, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, sans-serif;display:inline !important;">解決導致 [共用行事曆] 改善的使用者查看行事曆失敗的問題。</span></span><span class="sxs-lookup"><span data-stu-id="a8166-463"><span style="font-family:&quot;Segoe UI&quot;, system-ui, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, sans-serif;display:inline !important;">Addresses an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span></span><br>


- <span data-ttu-id="a8166-464"><span style="display:inline !important;">解決導致使用者看到 Outlook 持續提示他們執行收件匣修復工具的問題。</span></span><span class="sxs-lookup"><span data-stu-id="a8166-464"><span style="display:inline !important;">Addresses an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span></span><br>


- <span data-ttu-id="a8166-465"><span style="display:inline !important;">解決導致在[建議功能]中尋找功能沒有結果並未留給使用者選項以提交新功能點子的問題。</span></span><span class="sxs-lookup"><span data-stu-id="a8166-465"><span style="display:inline !important;">Addresses an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span></span><br>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-june-18"></a><span data-ttu-id="a8166-467">版本 2006：6 月 18 日</span><span class="sxs-lookup"><span data-stu-id="a8166-467">Version 2006: June 18</span></span>
<span data-ttu-id="a8166-468">*版本2006（組建13001.20198）*</span><span class="sxs-lookup"><span data-stu-id="a8166-468">*Version 2006 (Build 13001.20198)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="a8166-470">功能更新</span><span class="sxs-lookup"><span data-stu-id="a8166-470">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a8166-471">Excel</span><span class="sxs-lookup"><span data-stu-id="a8166-471">Excel</span></span>



- <span data-ttu-id="a8166-472">**儲存至 [釘選資料夾]：** 釘選您的資料夾可讓您更輕鬆地儲存 Office 檔案，我們收到意見反應，使用者希望能在新檔案儲存時可以在可用的資料夾上有更多控制權。</span><span class="sxs-lookup"><span data-stu-id="a8166-472">**Save to Pinned Folders:** Pin your folders makes saving Office files easier We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="a8166-473">我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。</span><span class="sxs-lookup"><span data-stu-id="a8166-473">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="a8166-474">這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。</span><span class="sxs-lookup"><span data-stu-id="a8166-474">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> <br /><span data-ttu-id="a8166-475">在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="a8166-475">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8166-476">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8166-476">PowerPoint</span></span>

- <span data-ttu-id="a8166-477">**儲存至 [釘選資料夾]：** 釘選您的資料夾可讓您更輕鬆地儲存 Office 檔案，我們收到意見反應，使用者希望能在新檔案儲存時可以在可用的資料夾上有更多控制權。</span><span class="sxs-lookup"><span data-stu-id="a8166-477">**Save to Pinned Folders:** Pin your folders makes saving Office files easier We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="a8166-478">我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。</span><span class="sxs-lookup"><span data-stu-id="a8166-478">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="a8166-479">這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。</span><span class="sxs-lookup"><span data-stu-id="a8166-479">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="a8166-480">在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="a8166-480">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="word"></a><span data-ttu-id="a8166-481">Word</span><span class="sxs-lookup"><span data-stu-id="a8166-481">Word</span></span>

- <span data-ttu-id="a8166-482">**儲存至 [釘選資料夾]：** 釘選您的資料夾可讓您更輕鬆地儲存 Office 檔案。我們收到意見反應，使用者希望能在新檔案儲存時可以在可用的資料夾上有更多控制權。</span><span class="sxs-lookup"><span data-stu-id="a8166-482">**Save to Pinned Folders:** Pin your folders makes saving Office files easierWe received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="a8166-483">我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。</span><span class="sxs-lookup"><span data-stu-id="a8166-483">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="a8166-484">這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。</span><span class="sxs-lookup"><span data-stu-id="a8166-484">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> <br /><span data-ttu-id="a8166-485">在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="a8166-485">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="a8166-488">解決的問題</span><span class="sxs-lookup"><span data-stu-id="a8166-488">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a8166-489">Excel</span><span class="sxs-lookup"><span data-stu-id="a8166-489">Excel</span></span>

- <span data-ttu-id="a8166-490">已修正當儲存至 SharePoint/OneDrive 時，會導致自訂功能區索引標籤 CustomUI XML 的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-490">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

### <a name="outlook"></a><span data-ttu-id="a8166-491">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-491">Outlook</span></span>

- <span data-ttu-id="a8166-492">解決了啟用雲端設定時，按下 Ctrl + 按一下會造成運作停止的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-492">Addressed an issue that caused Ctrl+click to stop working when cloud settings were enabled.</span></span>

### <a name="project"></a><span data-ttu-id="a8166-493">專案</span><span class="sxs-lookup"><span data-stu-id="a8166-493">Project</span></span>

- <span data-ttu-id="a8166-494">已修正當標示為100% 完成之工作錯誤地變更為完成度低於100% 的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-494">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-june-11"></a><span data-ttu-id="a8166-496">版本 2006：6 月 11 日</span><span class="sxs-lookup"><span data-stu-id="a8166-496">Version 2006: June 11</span></span>
<span data-ttu-id="a8166-497">*版本2006（組建13001.20144）*</span><span class="sxs-lookup"><span data-stu-id="a8166-497">*Version 2006 (Build 13001.20144)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="a8166-499">功能更新</span><span class="sxs-lookup"><span data-stu-id="a8166-499">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="a8166-500">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8166-500">PowerPoint</span></span>

- <span data-ttu-id="a8166-501">**改善的 PowerPoint 中的 Steam 影片效能：** 我們改善了 Microsoft Stream 影片的播放效能，將影片載入時間減至最少，以建立出流暢的觀賞體驗。</span><span class="sxs-lookup"><span data-stu-id="a8166-501">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="a8166-502">您可以使用 Microsoft Stream 上您的公司影片來建立更完善的簡報。</span><span class="sxs-lookup"><span data-stu-id="a8166-502">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

### <a name="word"></a><span data-ttu-id="a8166-503">Word</span><span class="sxs-lookup"><span data-stu-id="a8166-503">Word</span></span>

- <span data-ttu-id="a8166-504">**以向量保留文字：** 現在當您在 Excel、Word 和 PowerPoint 中轉換地圖、圖表和其他 SVG 向量等物件時，您可以保留物件中的文字。</span><span class="sxs-lookup"><span data-stu-id="a8166-504">**Retain text in vectors:** Now you can retain the text in maps, charts, and other SVG vectors when converting these objects in Excel, Word, and PowerPoint.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="a8166-507">解決的問題</span><span class="sxs-lookup"><span data-stu-id="a8166-507">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a8166-508">Excel</span><span class="sxs-lookup"><span data-stu-id="a8166-508">Excel</span></span>

- <span data-ttu-id="a8166-509">我們修正了在使用 OneDrive 時，Excel 偶爾會關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-509">We fixed an issue where Excel would occasionally shut down when engaging OneDrive.</span></span>

- <span data-ttu-id="a8166-510">我們修正了圖表座標軸自訂值無法正確套用的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-510">We fixed an issue where custom values on the chart axis would not get applied correctly.</span></span>

- <span data-ttu-id="a8166-511">我們修正了包含多個含有定義名稱的公式會導致儲存檔案時間加長的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-511">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

- <span data-ttu-id="a8166-512">我們修正了導致印表機名稱在可用印表機清單中重複的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-512">We fixed an issue that caused printer names to be duplicated in the list of available printers.</span></span>

- <span data-ttu-id="a8166-513">我們修正了在使用者刪除合併的欄時，造成執行時間增加的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-513">We fixed an issue that resulted in improved performance time for users when they deleted merged columns.</span></span>

- <span data-ttu-id="a8166-514">我們修正了因為增益集是以字母順序裝載，而不是以使用者指定的順序載入，而造成出現「因為此活頁簿目前有他人進行參考，而無法關閉」的錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-514">We fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="a8166-515">我們修正了管理 Excel 與部分協力廠商輔助技術應用程式之間的字型時發生記憶體損毀的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-515">We fixed an issue where memory was being corrupted when managing fonts between Excel and some third party assistive technology applications.</span></span>

- <span data-ttu-id="a8166-516">我們修正了在相同活頁簿中按一下加上書簽的超連結會導致活頁簿隱藏的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-516">We fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="a8166-517">我們已修正某些複製和貼上的圖表連結使用的是映射磁碟機位址，而不是通用位址的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-517">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="a8166-518">我們修正了當 Excel 視窗透過 Teams 共用時，使用 Ctrl + Shift + 方向鍵滑動後，Excel 可能會無法回應的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-518">We fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window was shared through Teams.</span></span>

- <span data-ttu-id="a8166-519">我們修正了當增益集在工作表中詢問含有 noSelect 鎖定的圖形的主項目目時，Excel 會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-519">We fixed an issue where Excel would crash when Add-ins ask for Host Items on worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="a8166-520">解決了嘗試將樞紐分析表插入圖表時 Excel 可能會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-520">Addressed an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

### <a name="outlook"></a><span data-ttu-id="a8166-521">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-521">Outlook</span></span>

- <span data-ttu-id="a8166-522">我們已修正以下問題：當使用多個不同解析度的監視器時，輸入法編輯器 (IEM) 視窗會覆蓋透過 IME 輸入的文字。</span><span class="sxs-lookup"><span data-stu-id="a8166-522">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="a8166-523">我們已修正在撰寫新電子郵件訊息時，檢視範本會導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-523">We fixed an issue where viewing a template when composing a new email message would result in a crash.</span></span>

- <span data-ttu-id="a8166-524">我們已修正在 Outlook 版本 1911之後，使用者無法使用 Exchange 2010 公用資料夾的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-524">We fixed an issue where users were unable to Exchange 2010 public folders after Outlook version 1911.</span></span>

- <span data-ttu-id="a8166-525">我們修正了 Office 功能區中群組行事曆分類按鈕已停用的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-525">We fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>

- <span data-ttu-id="a8166-526">解決了 Outlook 無法啟用 [資料遺失保護原則] 提示使用 M365 商務版進階方案並為此服務付款的的使用者之問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-526">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="a8166-527">已解決導致 Outlook 在某些 Windows 組建上當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-527">Addressed an issue that caused Outlook to crash on some Windows builds.</span></span>

- <span data-ttu-id="a8166-528">我們修正了使用者無法與來賓使用者共用行事曆的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-528">We fixed an issue where users were unable to share a calendar with a guest user.</span></span>

- <span data-ttu-id="a8166-529">我們修正了使用者看到將午夜臨界值視為全天事件的行事曆專案的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-529">We fixed an issue where users saw calendar items that spanned the midnight threshold as All day events.</span></span>

- <span data-ttu-id="a8166-530">我們修正了導致使用者在高 DPI 監視器上遺失 [線上封存] 摘要的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-530">We fixed an issue that resulted in the Online Archive dropdown in folder properties to be missing for users on high DPI monitors.</span></span>

- <span data-ttu-id="a8166-531">我們修正了當使用者在資料夾之間移動專案時，BeforeItemMove 事件未正確觸發的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-531">We fixed an issue where the Folder.BeforeItemMove event didn't fire correctly when a user moved items between folders.</span></span>

- <span data-ttu-id="a8166-532">我們修正了當兩個增益集將按鈕新增到功能區中相同群組時，Outlook 發生當端的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-532">We fixed an issue where Outlook crashed when two add-ins added a button to the same group in the ribbon.</span></span>

- <span data-ttu-id="a8166-533">我們修正了當處理純文字電子郵件中的超連結時，會導致使用者遇到 Outlook 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-533">We fixed an issue that caused users to experience a crash in Outlook when working with hyperlinks in Plain Text emails.</span></span>

- <span data-ttu-id="a8166-534">我們已修正導致 Outlook 無法剖析使用 RFC2231 編碼的長檔名的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-534">We fixed an issue that caused Outlook to be unable to parse long file names encoded with RFC2231.</span></span>

- <span data-ttu-id="a8166-535">我們修正了導致 Outlook 使用者在使用螢幕閱讀器時遇到間歇性的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-535">We fixed an issue that was causing Outlook users to experience intermittent hangs when using screen readers.</span></span>

- <span data-ttu-id="a8166-536">我們修正了會造成具有衝突連絡人的使用者在 Outlook 中遭遇當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-536">We fixed an issue that would cause users with conflicting contacts to experience crashes in Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8166-537">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8166-537">PowerPoint</span></span>

- <span data-ttu-id="a8166-538">我們已修正使用表單型驗證開啟伺服器設定的檔案時發生的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-538">We fixed an issue with opening server-configured files with forms-based authentication.</span></span>

- <span data-ttu-id="a8166-539">我們修正了內嵌圖表/活頁簿的 PowerPoint 檔案可能會導致儲存檔案失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-539">We fixed an issue where PowerPoint files with embedded charts / workbooks could result in failures when saving the file.</span></span>

- <span data-ttu-id="a8166-540">我們修正了放大和縮小簡報區域會造成縮放選取選框和滑鼠指標之間的間隙的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-540">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

- <span data-ttu-id="a8166-541">我們修正了使用滑鼠滾輪縮放後，投影片並未居中的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-541">We fixed an issue where slides were not centered after zooming using the mouse wheel.</span></span>

- <span data-ttu-id="a8166-542">我們已修正使用英文 (瑞士) (QWERTZ) 鍵盤時鍵盤快速鍵和拼字檢查無法正常運作的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-542">We fixed an issue where keyboard shortcuts and spell check wouldn’t function as expected when using an English Switzerland (QWERTZ) keyboard.</span></span>

- <span data-ttu-id="a8166-543">我們修正了使用者已關閉的批註窗格會自動開啟的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-543">We fixed an issue where a Comment pane that had been closed by the user would re-open automatically.</span></span>

- <span data-ttu-id="a8166-544">我們已修正某張投影片的投影片編輯工具會在下一張投影片上重疊的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-544">We fixed an issue where the slide editor from one slide would overlap on to the next slide.</span></span>

### <a name="project"></a><span data-ttu-id="a8166-545">專案</span><span class="sxs-lookup"><span data-stu-id="a8166-545">Project</span></span>

- <span data-ttu-id="a8166-546">已修正當專案摘要工作-或是專案[開始/工作]欄位有變更時，ProjectBeforeTaskChange 事件不會觸發的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-546">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

- <span data-ttu-id="a8166-547">已修正當標示為100% 完成之工作錯誤地變更為完成度低於100% 的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-547">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

- <span data-ttu-id="a8166-548">我們修正了在按一下 [選項] 之後 Project 會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-548">We fixed an issue where Project would crash after clicking on Options.</span></span>

- <span data-ttu-id="a8166-549">我們修正了在刪除母計畫之後，無法刪除或重新指派孤立工作的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-549">We fixed an issue that prevented orphaned tasks from being deleted or re-assigned after their parent plan was deleted.</span></span>

### <a name="visio"></a><span data-ttu-id="a8166-550">Visio</span><span class="sxs-lookup"><span data-stu-id="a8166-550">Visio</span></span>

- <span data-ttu-id="a8166-551">有已修復的依賴代碼迴歸分析。</span><span class="sxs-lookup"><span data-stu-id="a8166-551">There was regression in dependent code which has been fixed.</span></span> <span data-ttu-id="a8166-552">現在，影像會在執行于 SharePoint Onprem 上的 Visio 服務中呈現。</span><span class="sxs-lookup"><span data-stu-id="a8166-552">Now, the images are getting rendered in Visio services running on SharePoint Onprem.</span></span>

### <a name="word"></a><span data-ttu-id="a8166-553">Word</span><span class="sxs-lookup"><span data-stu-id="a8166-553">Word</span></span>

- <span data-ttu-id="a8166-554">我們修正了批註窗格中的時間戳記不是根據系統區域設定時間所建立的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-554">We fixed an issue where timestamps in Comment panes were not based on the system locale time.</span></span>

- <span data-ttu-id="a8166-555">已解決在 URL 包含查詢元件時，從自訂檔傳遞（aspx）開啟 Word 檔的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-555">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>

- <span data-ttu-id="a8166-556">我們修正了在批註窗格中複製及貼上文字不會顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-556">We fixed an issue where copy and pasting text to a comment pane would not be displayed.</span></span>

- <span data-ttu-id="a8166-557">我們修正了批註中的超連結無法正常運作的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-557">We fixed an issue where hyperlinks in comments weren’t working.</span></span>

- <span data-ttu-id="a8166-558">我們修正了放大和縮小簡報區域會造成縮放選取選框和滑鼠指標之間的間隙的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-558">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

- <span data-ttu-id="a8166-559">我們修正了網頁應用程式與傳統型應用程式之間的批註未同步處理的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-559">We fixed an issue where comments between the web app and the desktop application were not in sync.</span></span>

- <span data-ttu-id="a8166-560">我們修正了批註提示泡泡在100% 縮放比例中顯示模糊的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-560">We fixed an issue where comment hint bubbles appeared blurry at 100% zoom.</span></span>

- <span data-ttu-id="a8166-561">我們已修正在空白文件中新增註解卻未執行任何動作的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-561">We fixed an issue where adding a new comment on a blank document wouldn't do anything.</span></span>

- <span data-ttu-id="a8166-562">我們修正了無法將 HTML 貼入行事曆的 WordMail 的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-562">We fixed an issue where pasting HTML into WordMail for Calendar wasn’t working.</span></span>

- <span data-ttu-id="a8166-563">我們修正了在共同撰寫的會話中回復批註有時會導致 Word 停滯的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-563">We fixed an issue where replying to a comment in a co-authored session could sometimes cause Word to freeze.</span></span>

- <span data-ttu-id="a8166-564">我們修正了在含有一百個以上專案的檔中插入或更新索引會導致應用程式當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-564">We fixed an issue where inserting or updating an Index in a document containing more than a hundred entries would result in the application crashing.</span></span>

- <span data-ttu-id="a8166-565">我們修正了啟用原則 Word 2007 及更新版本的二進位檔案和範本會導致部分共同撰寫案例失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-565">We fixed an issue where enabling policy Word 2007 and later Binary Documents and Templates would cause some co-authoring cases to fail.</span></span>

- <span data-ttu-id="a8166-566">我們修正了具有自訂 xml 值的檔案在開啟時速度極度緩慢的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-566">We fixed an issue where files with custom xml values opened extremely slowly.</span></span>

- <span data-ttu-id="a8166-567">我們修正了使用長路徑名稱（大於32K）的檔案無法開啟，且未顯示適當的錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-567">We fixed an issue where files with long path names (greater than 32K) would not open and an appropriate error message was not being displayed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a8166-568">Office 套件</span><span class="sxs-lookup"><span data-stu-id="a8166-568">Office Suite</span></span>

- <span data-ttu-id="a8166-569">我們已經研究並解決了在作業系統關閉後，透過 InTune 進行的 Office 365 專業增強版部署會暫停的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-569">We have investigated and resolved the issue where an Office 365 ProPlus deployment via InTune is paused after an OS shutdown.</span></span>

- <span data-ttu-id="a8166-570">我們修正了 Microsoft Office 的 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。</span><span class="sxs-lookup"><span data-stu-id="a8166-570">We fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="a8166-571">此更新解決了 Microsoft Office 中的一個問題：可能無法在執行時期正確找到 Visual Basic for Applications 專案，這些專案的參照預期透搜尋 PATH 環境變數指定的位置來找到，進而導致VBA 執行時期錯誤。</span><span class="sxs-lookup"><span data-stu-id="a8166-571">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-june-08"></a><span data-ttu-id="a8166-573">版本 2005：6 月 08 日</span><span class="sxs-lookup"><span data-stu-id="a8166-573">Version 2005: June 08</span></span>
<span data-ttu-id="a8166-574">*版本2005（組建12827.20336）*</span><span class="sxs-lookup"><span data-stu-id="a8166-574">*Version 2005 (Build 12827.20336)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="a8166-576">解決的問題</span><span class="sxs-lookup"><span data-stu-id="a8166-576">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="a8166-577">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8166-577">PowerPoint</span></span>

- <span data-ttu-id="a8166-578">我們修正了取代字型對話方塊中，取代字型下拉清單只會顯示系統中安裝的字型，而不是所安裝的字型的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-578">We have fixed an issue with replace fonts dialog where replace font dropdown only shows fonts within the presentation instead of fonts installed on the system.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-june-04"></a><span data-ttu-id="a8166-580">版本 2005：6 月 04 日</span><span class="sxs-lookup"><span data-stu-id="a8166-580">Version 2005: June 04</span></span>
<span data-ttu-id="a8166-581">*版本2005（組建12827.20320）*</span><span class="sxs-lookup"><span data-stu-id="a8166-581">*Version 2005 (Build 12827.20320)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="a8166-583">功能更新</span><span class="sxs-lookup"><span data-stu-id="a8166-583">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="a8166-584">Access</span><span class="sxs-lookup"><span data-stu-id="a8166-584">Access</span></span>

- <span data-ttu-id="a8166-585">**隨時跟上改變！[日期/時間] 延伸資料類型具有更好的精確度。：** 引進新的和改良的資料類型。</span><span class="sxs-lookup"><span data-stu-id="a8166-585">**Keep up with the times! The Date/Time Extended data type has better precision.:** Introducing a new and improved data type.</span></span>  <span data-ttu-id="a8166-586">為加強與 SQL 的語法相容性，並提高包含日期和時間之記錄的詳細資料和層級，我們正在將 DateTime2 資料類型實施到 Access 中。</span><span class="sxs-lookup"><span data-stu-id="a8166-586">To enhance syntax compatibility with SQL, and to increase accuracy and level of detail in records that include dates and times, we’re implementing the DateTime2 data type into Access.</span></span> <span data-ttu-id="a8166-587">這個額外的日期與時間資料類型，將會包含更大的日期範圍（0001-01-01 到9999-12-31），具有更高的指定時間精準度(以納秒取代秒為單位)，讓您可以提供和執行計算。</span><span class="sxs-lookup"><span data-stu-id="a8166-587">This additional date & time data type will include a larger date range (0001-01-01 through 9999-12-31), with higher-specified time precision (nanoseconds, rather than seconds) that you will be able to provide and perform calculations on.</span></span> <span data-ttu-id="a8166-588">若要啟用，請選取 [新增欄位] > [日期與時間延長]。</span><span class="sxs-lookup"><span data-stu-id="a8166-588">To enable, select New field > Date & Time Extended.</span></span> [<span data-ttu-id="a8166-589">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8166-589">Learn more</span></span>](https://support.office.com/article/708c32da-a052-4cc2-9850-9851042e0024)

### <a name="excel"></a><span data-ttu-id="a8166-590">Excel</span><span class="sxs-lookup"><span data-stu-id="a8166-590">Excel</span></span>

- <span data-ttu-id="a8166-591">**在 Excel 中建立來自 Power BI 資料的樞紐分析表：** 您可以在 Excel 中建立樞紐分析表，只要按幾下滑鼠，就能連線到儲存在 Power BI 的樞紐分析表。</span><span class="sxs-lookup"><span data-stu-id="a8166-591">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span><span data-ttu-id="a8166-592"> 如此一來，您就能獲得樞紐分析表和 Power BI 的最佳效果。</span><span class="sxs-lookup"><span data-stu-id="a8166-592"> Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="a8166-593">使用安全 Power BI 資料集的樞紐分析表以計算、摘要及分析資料。</span><span class="sxs-lookup"><span data-stu-id="a8166-593">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span>

### <a name="outlook"></a><span data-ttu-id="a8166-594">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-594">Outlook</span></span>

- <span data-ttu-id="a8166-595">**可讓您從上一個 Outlook 會話中快速重新開啟專案的選項：** 我們新增了一個可快速重新開啟先前 Outlook 會話專案的選項。</span><span class="sxs-lookup"><span data-stu-id="a8166-595">**Option to quickly reopen items from previous Outlook session:** We added an option to quickly reopen items from a previous Outlook session.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="a8166-598">解決的問題</span><span class="sxs-lookup"><span data-stu-id="a8166-598">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="a8166-599">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8166-599">PowerPoint</span></span>

- <span data-ttu-id="a8166-600">這可修正使用者在同一檔案中同時有新版和舊版批註，因此觸發批註的升級而當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-600">This fixes a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>


### <a name="office-suite"></a><span data-ttu-id="a8166-601">Office 套件</span><span class="sxs-lookup"><span data-stu-id="a8166-601">Office Suite</span></span>

- <span data-ttu-id="a8166-602">我們透過設定Bing附加預設安裝驗證設定為true默認，並將MSI返回成功視為安裝成功，而解決了 ValidateInstall 失敗率問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-602">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-may-29"></a><span data-ttu-id="a8166-604">版本 2005：5 月 29 日</span><span class="sxs-lookup"><span data-stu-id="a8166-604">Version 2005: May 29</span></span>
<span data-ttu-id="a8166-605">*版本2005（組建12827.20268）*</span><span class="sxs-lookup"><span data-stu-id="a8166-605">*Version 2005 (Build 12827.20268)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="a8166-607">功能更新</span><span class="sxs-lookup"><span data-stu-id="a8166-607">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="a8166-608">Excel</span><span class="sxs-lookup"><span data-stu-id="a8166-608">Excel</span></span>

- <span data-ttu-id="a8166-609">**工作表視圖：** 排序/篩選，同時與其他人在 Excel 電腦版共同作業。</span><span class="sxs-lookup"><span data-stu-id="a8166-609">**Sheet View:** Sort/filter while collaborating with others in Excel desktop.</span></span>

### <a name="outlook"></a><span data-ttu-id="a8166-610">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-610">Outlook</span></span>

- <span data-ttu-id="a8166-611">**新增至 Outlook 快顯通知的其他按鈕：** [快速動作] 按鈕，現在會於在 Windows 10 上執行 Outlook 時顯示在 Outlook 快顯通知中。</span><span class="sxs-lookup"><span data-stu-id="a8166-611">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="a8166-614">解決的問題</span><span class="sxs-lookup"><span data-stu-id="a8166-614">Resolved issues</span></span>



### <a name="outlook"></a><span data-ttu-id="a8166-615">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-615">Outlook</span></span>

- <span data-ttu-id="a8166-616">解決了導致 Windows 10 伺服器版本的使用者看到警告防毒軟體狀態：無效的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-616">Addressed an issue that caused users of Windows 10 server versions to see the warning  Antivirus status: Invalid.</span></span> <span data-ttu-id="a8166-617">這個版本的 Windows 支援防毒軟體檢測，但即使已正確安裝防毒軟體，也無法找到防毒軟體。</span><span class="sxs-lookup"><span data-stu-id="a8166-617">This version of Windows supports antivirus detection, but no antivirus was found despite having anti virus correctly installed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a8166-618">Office 套件</span><span class="sxs-lookup"><span data-stu-id="a8166-618">Office Suite</span></span>

- <span data-ttu-id="a8166-619">當您啟用增益集，而登錄金鑰 HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth 被設為零時，辦公主機視窗會當機。</span><span class="sxs-lookup"><span data-stu-id="a8166-619">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="a8166-620">這變更將修正此問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-620">This change would fix this issue.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-may-21"></a><span data-ttu-id="a8166-622">版本 2005：5 月 21 日</span><span class="sxs-lookup"><span data-stu-id="a8166-622">Version 2005: May 21</span></span>
<span data-ttu-id="a8166-623">*版本2005（組建12827.20210）*</span><span class="sxs-lookup"><span data-stu-id="a8166-623">*Version 2005 (Build 12827.20210)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)




[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="a8166-627">解決的問題</span><span class="sxs-lookup"><span data-stu-id="a8166-627">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a8166-628">Excel</span><span class="sxs-lookup"><span data-stu-id="a8166-628">Excel</span></span>

- <span data-ttu-id="a8166-629">已修正當 Excel 視窗透過 Teams 共用時，使用 Ctrl + Shift + 方向鍵滑動後，Excel 可能會無法回應的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-629">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>


- <span data-ttu-id="a8166-630">在某些情況下，按一下同一個活頁簿中某個位置的超連結會導致活頁簿被隱藏。</span><span class="sxs-lookup"><span data-stu-id="a8166-630">In some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>


### <a name="outlook"></a><span data-ttu-id="a8166-631">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-631">Outlook</span></span>

- <span data-ttu-id="a8166-632">已解決有回應/轉寄標註的clp審查活動的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-632">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>


- <span data-ttu-id="a8166-633">已解決在從系統管理人通知中提交意見反應時，使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-633">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-may-14"></a><span data-ttu-id="a8166-635">版本 2005：5 月 14 日</span><span class="sxs-lookup"><span data-stu-id="a8166-635">Version 2005: May 14</span></span>
<span data-ttu-id="a8166-636">*版本2005（組建12827.20160）*</span><span class="sxs-lookup"><span data-stu-id="a8166-636">*Version 2005 (Build 12827.20160)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="a8166-638">功能更新</span><span class="sxs-lookup"><span data-stu-id="a8166-638">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a8166-639">Excel</span><span class="sxs-lookup"><span data-stu-id="a8166-639">Excel</span></span>

- <span data-ttu-id="a8166-640">**[自動套用] 或 [建議敏感度] 標籤：** Office 可以根據偵測到的敏感性內容來推薦或自動套用靈敏度標籤。</span><span class="sxs-lookup"><span data-stu-id="a8166-640">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8166-641">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8166-641">PowerPoint</span></span>

- <span data-ttu-id="a8166-642">**不需要簡報導覽裝置：有耳塞式耳機就夠了：** 使用您的 Surface Earbuds 控制 PowerPoint 簡報。</span><span class="sxs-lookup"><span data-stu-id="a8166-642">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="a8166-643">重要：您必須在 Windows 10 的 Surface 音訊應用程式中配對 Surface Earbuds，才能使用手勢來控制簡報。</span><span class="sxs-lookup"><span data-stu-id="a8166-643">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="a8166-644">在此取得 Windows 10 上 Surface 音訊應用程式入門的指示。</span><span class="sxs-lookup"><span data-stu-id="a8166-644">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="a8166-645">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8166-645">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

- <span data-ttu-id="a8166-646">**[自動套用] 或 [建議敏感度] 標籤：** Office 可以根據偵測到的敏感性內容來推薦或自動套用靈敏度標籤。</span><span class="sxs-lookup"><span data-stu-id="a8166-646">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="word"></a><span data-ttu-id="a8166-647">Word</span><span class="sxs-lookup"><span data-stu-id="a8166-647">Word</span></span>

- <span data-ttu-id="a8166-648">**[自動套用] 或 [建議敏感度] 標籤：** Office 可以根據偵測到的敏感性內容來推薦或自動套用靈敏度標籤。</span><span class="sxs-lookup"><span data-stu-id="a8166-648">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="a8166-651">解決的問題</span><span class="sxs-lookup"><span data-stu-id="a8166-651">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="a8166-652">Excel</span><span class="sxs-lookup"><span data-stu-id="a8166-652">Excel</span></span>

- <span data-ttu-id="a8166-653">已增加搭配圖表使用的 [自訂誤差線] 對話方塊上儲存格參照 [編輯] 控制項的大小。</span><span class="sxs-lookup"><span data-stu-id="a8166-653">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>

- <span data-ttu-id="a8166-654">修正圖表資料表無法正確呈現日期座標軸中的值的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-654">Fixed an issue where chart data table could render values in a date axis incorrectly.</span></span>

- <span data-ttu-id="a8166-655">修正使用 [頁面配置] 或 [分頁預覽] 之後無法停用分頁符號的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-655">Fixed an issue where page breaks could not be disabled after going into Page Layout or Page Break Preview.</span></span>

- <span data-ttu-id="a8166-656">修正隱藏和取消隱藏具有系列資料的欄之後，圖表線條樣式可能會遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-656">Fixed an issue where chart line styles could be lost after hiding and unhiding columns with series data.</span></span>

- <span data-ttu-id="a8166-657">已修正在已篩選清單中插入欄的時間會比預期更長的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-657">Fixed an issue where inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="a8166-658">已修正列印時表單控制項的核取方塊縮放的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-658">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="a8166-659">已修正當檔案路徑太長時，在檔案重新開啟之後外部連結會停止運作的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-659">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="a8166-660">在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。</span><span class="sxs-lookup"><span data-stu-id="a8166-660">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="a8166-661">在某些情況下，Application.Evaluate (VBA) 無法在使用者定義的函式中運作。</span><span class="sxs-lookup"><span data-stu-id="a8166-661">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="a8166-662">在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。</span><span class="sxs-lookup"><span data-stu-id="a8166-662">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="a8166-663">此變更會修正設定格式化的條件 (CF) 資訊無法正確儲存到 XLSB 檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-663">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

- <span data-ttu-id="a8166-664">這項變更修正了即使 LINEST 函式傳回正確的值，圖表趨勢線的 R 平方值 (在強制 y 截距的情況下) 仍然不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-664">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>

- <span data-ttu-id="a8166-665">此變更修正了自訂圖表趨勢線格式不一定會儲存的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-665">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

- <span data-ttu-id="a8166-666">當您使用舊版的「共用活頁簿」模式，嘗試為活頁簿的新工作表列出變更時，就會發生當機。</span><span class="sxs-lookup"><span data-stu-id="a8166-666">A crash could occur when trying to list changes on a new sheet for a workbook using legacy"Shared Workbook" mode.</span></span>

- <span data-ttu-id="a8166-667">修正啟用 [負值以補色顯示] 選項後，可能無法儲存樞紐分析表中的自訂格式設定的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-667">Fixed the issue where custom formatting in Pivot charts may not be saved when the "Invert if negative" option was enabled.</span></span>

- <span data-ttu-id="a8166-668">修正如果選取 [負值以補色顯示] 選項，可能無法儲存樞紐分析表中單一資料點的自訂格式設定的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-668">Fixed an issue where custom formatting for a single data point in a Pivot chart was not saved if the "Invert if negative" option was selected.</span></span>

- <span data-ttu-id="a8166-669">這項變更修正在 CSV 檔案中上傳 '@' 字元時，會導致將 '@' 字元之後的字串轉換成公式的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-669">This change fixes an issue where the '@' character uploaded in a CSV file, would result in the string after the '@' character to be converted to a formula.</span></span>

- <span data-ttu-id="a8166-670">修正無法正確捨入 SEQUENCE 函數中十進位值的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-670">Fixed an issue where decimal values in the SEQUENCE function were not rounded correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="a8166-671">OneNote</span><span class="sxs-lookup"><span data-stu-id="a8166-671">OneNote</span></span>

- <span data-ttu-id="a8166-672">修正將分行符號儲存為垂直 Tab 的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-672">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="a8166-673">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-673">Outlook</span></span>

- <span data-ttu-id="a8166-674">解決會導致使用者無法將個人連絡人群組新增為會議出席者的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-674">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>

- <span data-ttu-id="a8166-675">已修正 Office 功能區中群組行事曆分類按鈕已停用的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-675">Fixed an issue where the categorize button for group calendars in the Office Ribbon was disabled.</span></span>

- <span data-ttu-id="a8166-676">已解決在 Windows 更新後，開啟儲存在本機的 msg 或 .oft 檔案會導致 Outlook 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-676">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="a8166-677">已修正企業客戶沒有執行或無法使用群組資料夾的問題，該問題會導致 Outlook 顯示「沒有回應」的訊息。</span><span class="sxs-lookup"><span data-stu-id="a8166-677">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

- <span data-ttu-id="a8166-678">已解決導致使用者在 Outlook 桌面用戶端中按一下非常長的安全連結時，由於截斷而無法載入的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-678">Addressed an issue that caused very long safelinks that users clicked on in the Outlook Desktop client to fail to load due to truncation.</span></span>

- <span data-ttu-id="a8166-679">修正當與伺服器同步處理時，名稱中包含 DBCS (雙位元組字元集) 字元的 Outlook 資料夾會間斷消失的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-679">Fixed an issue where Outlook folders with names containing DBCS (Double Byte Character Set) characters would intermittently disappear when synchronizing with the server.</span></span> <span data-ttu-id="a8166-680">為此，必須為 Outlook 設定 IMAP 帳戶，並在地區設定設定為日文的系統上執行。</span><span class="sxs-lookup"><span data-stu-id="a8166-680">For this to happen, Outlook had to be configured with an IMAP account and running on a system with the locale set to Japanese.</span></span>

- <span data-ttu-id="a8166-681">已解決會導致為使用者主要信箱以外的信箱所建立的刪除規則變得無效的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-681">Addressed an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>

- <span data-ttu-id="a8166-682">已解決在轉寄加密郵件時導致捨棄附件的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-682">Addressed an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

- <span data-ttu-id="a8166-683">已解決會導致還有 2 個月時間的會議，無法在排程小幫手中顯示會議主題的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-683">Addressed an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>

- <span data-ttu-id="a8166-684">已解決會導致使用者在轉寄大型 HTML 郵件時，看到郵件內文截斷的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-684">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="a8166-685">新增透過群組原則強制執行 S/MIME 預設登入設定的功能。</span><span class="sxs-lookup"><span data-stu-id="a8166-685">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8166-686">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8166-686">PowerPoint</span></span>

- <span data-ttu-id="a8166-687">已修正問題：如果使用者建立了註解，但未張貼就關閉 [註解] 窗格，然後開啟新視窗、瀏覽多張投影片並關閉視窗，最後再開啟原始簡報中的 [註解] 窗格，將導致無法使用草稿註解。</span><span class="sxs-lookup"><span data-stu-id="a8166-687">Fixed an issue where if a user created a comment without posting it and closed the Comments pane, then opened a new window, navigated through multiple slides and, closed the window, and finally re-opened the Comments pane in the original presentation, the draft comments would not be available.</span></span>

- <span data-ttu-id="a8166-688">修正了將滑鼠游標移到星號 (\*) 符號，但不會顯示上一次更新文件的日期和使用者姓名。</span><span class="sxs-lookup"><span data-stu-id="a8166-688">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="project"></a><span data-ttu-id="a8166-689">Project</span><span class="sxs-lookup"><span data-stu-id="a8166-689">Project</span></span>

- <span data-ttu-id="a8166-690">在表單檢視中編輯前置/後續任務資料時，會觸發額外的 ProjectBeforeTaskChange 事件。</span><span class="sxs-lookup"><span data-stu-id="a8166-690">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="a8166-691">修正變更連結至 SharePoint 工作清單之專案的面板狀態欄位時，Project 可能當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-691">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>

- <span data-ttu-id="a8166-692">修正儲存使用舊版 Project 建立的專案時，Project 可能當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-692">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="a8166-693">已修正如果 Project 連線至 Project Web App，且小數分隔符號是逗號，當新增延遲時，TaskDependencies Add 方法會失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-693">Fixed an issue where if Project is connected to Project Web App and the decimal separator is a comma, TaskDependencies Add method fails when Lag is added.</span></span>


### <a name="word"></a><span data-ttu-id="a8166-694">Word</span><span class="sxs-lookup"><span data-stu-id="a8166-694">Word</span></span>

- <span data-ttu-id="a8166-695">修正在 [共同作業] 模式時，在文件中插入註解並不總是成功的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-695">Fixed an issue where inserting comments on a document in collaboration mode would not always work.</span></span>

- <span data-ttu-id="a8166-696">此變更修正在按一下 @ 提及時，[人員卡片] 會閃動的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-696">This change fixes an issue where the People card would flash if the @ mention was clicked.</span></span>

- <span data-ttu-id="a8166-697">啟用「顯示書簽」選項卻不會顯示書簽。</span><span class="sxs-lookup"><span data-stu-id="a8166-697">Enabling the option "Show bookmarks" would not display bookmarks.</span></span> <span data-ttu-id="a8166-698">已修正這個問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-698">This has been fixed.</span></span>

- <span data-ttu-id="a8166-699">修正問題：關閉具有草稿註解的文件時，會在不儲存草稿註解的情況下，提示使用者是否要關閉文件。</span><span class="sxs-lookup"><span data-stu-id="a8166-699">Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments.</span></span> <span data-ttu-id="a8166-700">取消提示會關閉文件，而不是保持文件開啟。</span><span class="sxs-lookup"><span data-stu-id="a8166-700">Cancelling the prompt would close the document rather than leaving it open.</span></span>

- <span data-ttu-id="a8166-701">我們修正了複製及貼上標題的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-701">We fixed an issue in copying and pasting headings.</span></span>

- <span data-ttu-id="a8166-702">已修正翻譯已張貼註解將導致「插入已翻譯的文字失敗」錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-702">Fixed an issue where translating a posted comment would result in the error 'Inserting translated text failed'.</span></span>

- <span data-ttu-id="a8166-703">此變更修正了下列問題：如果已啟用 [顯示功能變數代碼，而非其值] 選項，則含有超連結的文字可能不會顯示。</span><span class="sxs-lookup"><span data-stu-id="a8166-703">This change fixes an issue where text with hyperlinks may not display if the option: "Show field codes instead of their values" was enabled.</span></span>

- <span data-ttu-id="a8166-704">在 Web 檢視/沉浸式閱讀器中，如果已在檢視中，按一下提示會捲動到最上方。</span><span class="sxs-lookup"><span data-stu-id="a8166-704">In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view.</span></span> <span data-ttu-id="a8166-705">已修正這個問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-705">This has been fixed.</span></span>

- <span data-ttu-id="a8166-706">我們已修正一個問題，當嘗試使用新名稱儲存包含巨集的檔案時，無論使用者輸入什麼名稱，都會導致該檔案以.docx 副檔名和檔案名稱 WRO0004.docx 儲存，進而導致文件無法使用。</span><span class="sxs-lookup"><span data-stu-id="a8166-706">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with .docx extension and the filename WRO0004.docx, regardless of what the user entered, rendering the document unusable.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a8166-707">Office 套件</span><span class="sxs-lookup"><span data-stu-id="a8166-707">Office Suite</span></span>

- <span data-ttu-id="a8166-708">當使用者收到將他們移至 Teams Only 的原則時，他們仍然可以使用商務版 Skype Outlook 增益集來排程會議。</span><span class="sxs-lookup"><span data-stu-id="a8166-708">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span>  <span data-ttu-id="a8166-709">在此更新之後，當客戶端讀取指示用戶為 Teams Only 的策略並進入僅限會議加入模式後，您將不再能用商務版 Skype 安排會議。</span><span class="sxs-lookup"><span data-stu-id="a8166-709">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span>  <span data-ttu-id="a8166-710">此外，如果商務版 Skype Outlook 增益集發現商務版 Skype 用戶端處於 [僅限會議加入] 模式，就無法自行啟動。</span><span class="sxs-lookup"><span data-stu-id="a8166-710">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="a8166-711">此更新解決了 Microsoft Office 中的一個問題：可能無法在執行時期正確找到 Visual Basic for Applications 專案，這些專案的參照預期透搜尋 PATH 環境變數指定的位置來找到，進而導致VBA 執行時期錯誤。</span><span class="sxs-lookup"><span data-stu-id="a8166-711">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="a8166-712">此更新修正了 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。</span><span class="sxs-lookup"><span data-stu-id="a8166-712">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-may-11"></a><span data-ttu-id="a8166-714">版本 2004：5 月 11 日</span><span class="sxs-lookup"><span data-stu-id="a8166-714">Version 2004: May 11</span></span>
<span data-ttu-id="a8166-715">*版本 2004 (組建 12730.20270)*</span><span class="sxs-lookup"><span data-stu-id="a8166-715">*Version 2004 (Build 12730.20270)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="a8166-717">功能更新</span><span class="sxs-lookup"><span data-stu-id="a8166-717">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a8166-718">Excel</span><span class="sxs-lookup"><span data-stu-id="a8166-718">Excel</span></span>

- <span data-ttu-id="a8166-719">**使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦。</span><span class="sxs-lookup"><span data-stu-id="a8166-719">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="outlook"></a><span data-ttu-id="a8166-720">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-720">Outlook</span></span>

- <span data-ttu-id="a8166-721">**電子郵件中的改良連結：** 當您包含檔案的連結時，檔案名會取代 URL。</span><span class="sxs-lookup"><span data-stu-id="a8166-721">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="a8166-722">您可以變更權限，讓所有收件者都能存取。</span><span class="sxs-lookup"><span data-stu-id="a8166-722">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="a8166-723">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8166-723">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)<br /><span data-ttu-id="a8166-724">在[部落格文章](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="a8166-724">See details in [blog post](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span></span>

- <span data-ttu-id="a8166-725">**使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦。</span><span class="sxs-lookup"><span data-stu-id="a8166-725">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8166-726">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8166-726">PowerPoint</span></span>

- <span data-ttu-id="a8166-727">**使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦。</span><span class="sxs-lookup"><span data-stu-id="a8166-727">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>  [<span data-ttu-id="a8166-728">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8166-728">Learn more</span></span>](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a><span data-ttu-id="a8166-729">Word</span><span class="sxs-lookup"><span data-stu-id="a8166-729">Word</span></span>

- <span data-ttu-id="a8166-730">**使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦。</span><span class="sxs-lookup"><span data-stu-id="a8166-730">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="a8166-733">解決的問題</span><span class="sxs-lookup"><span data-stu-id="a8166-733">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="a8166-734">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-734">Outlook</span></span>

- <span data-ttu-id="a8166-735">解決在顯示快顯通知時，使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-735">Addressed an issue that caused users to experience a crash when displaying toast notifications.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-may-04"></a><span data-ttu-id="a8166-737">版本 2004：5 月 4 日</span><span class="sxs-lookup"><span data-stu-id="a8166-737">Version 2004: May 04</span></span>
<span data-ttu-id="a8166-738">*版本 2004 (組建 12730.20250)*</span><span class="sxs-lookup"><span data-stu-id="a8166-738">*Version 2004 (Build 12730.20250)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="a8166-740">功能更新</span><span class="sxs-lookup"><span data-stu-id="a8166-740">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a8166-741">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-741">Outlook</span></span>

- <span data-ttu-id="a8166-742">**更好的結果—瞬間：** 我們更新了搜尋體驗，讓這個版本比以往更聰明、更快速，且更可靠。</span><span class="sxs-lookup"><span data-stu-id="a8166-742">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="a8166-743">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8166-743">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="a8166-744">**IT 系統管理員的事件通知：** Microsoft 365 租用戶全域系統管理員和 Office 應用程式系統會在 Windows 版 Outlook 的新右側面板中收到影響其使用者的 Outlook 和 O365 Exchange 事件通知。</span><span class="sxs-lookup"><span data-stu-id="a8166-744">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="a8166-745">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8166-745">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="a8166-748">解決的問題</span><span class="sxs-lookup"><span data-stu-id="a8166-748">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="a8166-749">Office 套件</span><span class="sxs-lookup"><span data-stu-id="a8166-749">Office Suite</span></span>

- <span data-ttu-id="a8166-750">此更新修正了 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。</span><span class="sxs-lookup"><span data-stu-id="a8166-750">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-april-29"></a><span data-ttu-id="a8166-752">版本 2004：4 月 29 日</span><span class="sxs-lookup"><span data-stu-id="a8166-752">Version 2004: April 29</span></span>
<span data-ttu-id="a8166-753">*版本 2004 (組建 12730.20236)*</span><span class="sxs-lookup"><span data-stu-id="a8166-753">*Version 2004 (Build 12730.20236)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="a8166-755">功能更新</span><span class="sxs-lookup"><span data-stu-id="a8166-755">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a8166-756">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-756">Outlook</span></span>

- <span data-ttu-id="a8166-757">**協助保護群組中的資料：** 建立群組時所選擇的「敏感度」標籤會套用到群組電子郵件、文件及小組網站。</span><span class="sxs-lookup"><span data-stu-id="a8166-757">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="a8166-760">解決的問題</span><span class="sxs-lookup"><span data-stu-id="a8166-760">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="a8166-761">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-761">Outlook</span></span>

- <span data-ttu-id="a8166-762">解決導致 Outlook 在某些 Windows 組建上當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-762">Addresses an issue that caused Outlook to crash on some builds of Windows.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-april-25"></a><span data-ttu-id="a8166-764">版本 2004：4 月 25 日</span><span class="sxs-lookup"><span data-stu-id="a8166-764">Version 2004: April 25</span></span>
<span data-ttu-id="a8166-765">*版本 2004 (組建 12730.20206)*</span><span class="sxs-lookup"><span data-stu-id="a8166-765">*Version 2004 (Build 12730.20206)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="a8166-767">解決的問題</span><span class="sxs-lookup"><span data-stu-id="a8166-767">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="a8166-768">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-768">Outlook</span></span>

- <span data-ttu-id="a8166-769">已解決在 Windows 更新後，開啟儲存在本機的 msg 或 .oft 檔案會導致 Outlook 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-769">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

### <a name="project"></a><span data-ttu-id="a8166-770">Project</span><span class="sxs-lookup"><span data-stu-id="a8166-770">Project</span></span>

- <span data-ttu-id="a8166-771">已修正如果您使用的是連線至 Project Web App 的 Project，且小數分隔符號是逗號，當您嘗試將延遲新增至相依性時，TaskDependencies Add 方法會失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-771">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>


### <a name="office-suite"></a><span data-ttu-id="a8166-772">Office 套件</span><span class="sxs-lookup"><span data-stu-id="a8166-772">Office Suite</span></span>

- <span data-ttu-id="a8166-773">此修正可解決同時防止限制存取和保護設有密碼之檔案的錯誤。</span><span class="sxs-lookup"><span data-stu-id="a8166-773">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-april-21"></a><span data-ttu-id="a8166-775">版本 2004：4 月 21 日</span><span class="sxs-lookup"><span data-stu-id="a8166-775">Version 2004: April 21</span></span>
<span data-ttu-id="a8166-776">版本 2004 (組建 12730.20182)\*\*</span><span class="sxs-lookup"><span data-stu-id="a8166-776">*Version 2004 (Build 12730.20182)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="a8166-778">解決的問題</span><span class="sxs-lookup"><span data-stu-id="a8166-778">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="a8166-779">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-779">Outlook</span></span>

- <span data-ttu-id="a8166-780">解決導致資料夾窗格寬度意外變更的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-780">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="a8166-781">解決導致使用者在退出 Outlook 時遇到掛斷的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-781">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-april-15"></a><span data-ttu-id="a8166-783">版本 2004：4 月 15 日</span><span class="sxs-lookup"><span data-stu-id="a8166-783">Version 2004: April 15</span></span>
<span data-ttu-id="a8166-784">*版本 2004 (組建 12730.20150)*</span><span class="sxs-lookup"><span data-stu-id="a8166-784">*Version 2004 (Build 12730.20150)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="a8166-786">功能更新</span><span class="sxs-lookup"><span data-stu-id="a8166-786">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a8166-787">Excel</span><span class="sxs-lookup"><span data-stu-id="a8166-787">Excel</span></span>

- <span data-ttu-id="a8166-788">**Facebook 連接器支援即將結束：** 於 2020 年 4 月起，Excel 就不再支援使用 Facebook 連接器的外部資料連線。</span><span class="sxs-lookup"><span data-stu-id="a8166-788">**Facebook connector support is ending:** Starting in April 2020, Excel will no longer support external data connections that use the Facebook connector.</span></span>

### <a name="outlook"></a><span data-ttu-id="a8166-789">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-789">Outlook</span></span>

- <span data-ttu-id="a8166-790">**在 Outlook 中撰寫郵件時有新的選項可停用 @ 提及建議：** 您是否覺得 @ 提及的選擇器很煩人，一點都不好用？</span><span class="sxs-lookup"><span data-stu-id="a8166-790">**New option to disable @ mention suggestions when composing mail in Outlook:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="a8166-791">現在您可以視需要將其關閉了。</span><span class="sxs-lookup"><span data-stu-id="a8166-791">Now you can turn it off if you prefer.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8166-792">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8166-792">PowerPoint</span></span>

- <span data-ttu-id="a8166-793">**在簡報時同步處理變更：** 即使簡報處於投影片放映模式，仍可即時同步處理所做的變更。</span><span class="sxs-lookup"><span data-stu-id="a8166-793">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="a8166-794">Word</span><span class="sxs-lookup"><span data-stu-id="a8166-794">Word</span></span>

- <span data-ttu-id="a8166-795">**標註私人複本：** 製作共用文件的私人複本，以建立只有您本人能夠看到的手寫筆記。</span><span class="sxs-lookup"><span data-stu-id="a8166-795">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="a8166-796">若要開始使用，請移至 [檢視] > [建立私人複本]。</span><span class="sxs-lookup"><span data-stu-id="a8166-796">Go to View > Create a Private Copy to get started.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="a8166-799">解決的問題</span><span class="sxs-lookup"><span data-stu-id="a8166-799">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="a8166-800">Access</span><span class="sxs-lookup"><span data-stu-id="a8166-800">Access</span></span>

- <span data-ttu-id="a8166-801">已修正工作窗格中表格的重新調整及重新整理問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-801">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

- <span data-ttu-id="a8166-802">修正國際版 Access 在使用者介面中顯示英文字串的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-802">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="a8166-803">Excel</span><span class="sxs-lookup"><span data-stu-id="a8166-803">Excel</span></span>

- <span data-ttu-id="a8166-804">已修正在工作表上選取儲存格範圍會導致只選取單一儲存格的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-804">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="a8166-805">在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。</span><span class="sxs-lookup"><span data-stu-id="a8166-805">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="a8166-806">已修正在複製含有樞紐分析表的工作表後，會於某些情況下導致 Excel 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-806">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="a8166-807">在某些情況下，Application.Evaluate (VBA) 無法在使用者定義的函式中運作。</span><span class="sxs-lookup"><span data-stu-id="a8166-807">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="a8166-808">修正使用者在以程式設計方式編輯大量儲存格範圍時可能遇到的效能問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-808">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>

- <span data-ttu-id="a8166-809">修正以日文環境開啟 CSV 檔案時發生的效能問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-809">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

- <span data-ttu-id="a8166-810">已修正插入使用者定義的圖表範本來作為預設值會導致其儲存為直條圖的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-810">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="a8166-811">已修正當基礎資料儲存格沒有標題時，圖表上的資料標籤會以空白顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-811">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="a8166-812">已修正在為含有 X 軸範圍的圖表縮減大小時，可能會導致 Excel 停止回應的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-812">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="a8166-813">已修正已啟用 R1C1 儲存格參照且正在共同撰寫/共用的 Excel 工作表，在將游標移到 [使用者目前狀態] 圖示上方時不會以 R1C1 模式顯示作用中儲存格的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-813">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

- <span data-ttu-id="a8166-814">此變更解決了處理格式錯誤或無效通訊協定資訊影像時所導致的延遲問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-814">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="a8166-815">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-815">Outlook</span></span>

- <span data-ttu-id="a8166-816">此變更解決了處理格式錯誤或無效通訊協定資訊影像時所導致的延遲問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-816">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="a8166-817">此變更修正了電子郵件草稿最新變更未更新的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-817">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="a8166-818">已修正在檔案上按一下滑鼠右鍵並使用「傳送到」功能無法運作的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-818">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="a8166-819">已解決會導致代理人在不同機器上所看到的共用信箱有不同資料夾階層的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-819">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="a8166-820">已解決會導致類別有時候會從電子郵件訊息中消失的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-820">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="a8166-821">已解決在變更機器上的時區時，會導致某些提醒無法觸發的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-821">Addressed an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

- <span data-ttu-id="a8166-822">已解決在嘗試檢視組織表單的屬性時，會導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-822">Addressed an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="a8166-823">已修正如果使用者有自訂的 [通訊錄] 搜尋路徑，則 Outlook 的名稱解析範圍會限制為自訂路徑，而不是包括全域通訊清單 (GAL) 的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-823">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="a8166-824">解決了會讓 [附件工具] 中的 [儲存至雲端] 按鈕不見的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-824">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="a8166-825">解決了以下問題：當使用者從檢查程式視窗回覆受到數位版權管理的郵件，卻沒有所回覆郵件的擁有者權限時，使用者會無法新增簽名。</span><span class="sxs-lookup"><span data-stu-id="a8166-825">Addressed an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>

- <span data-ttu-id="a8166-826">解決了以下問題：使用者無法從網頁位置將其他附件新增到先前建立的會議。</span><span class="sxs-lookup"><span data-stu-id="a8166-826">Addressed an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

- <span data-ttu-id="a8166-827">解決將附件新增至郵件或從郵件拖放 (與透過功能表相對) 來儲存附件時，導致檔案的「上次修改」日期更新的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-827">Addressed an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

- <span data-ttu-id="a8166-828">解決會導致在展開的尋找窗格中按一下 Enter 時無法開始搜尋，而是會要求使用者按一下 [搜尋] 按鈕的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-828">Addressed an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>

- <span data-ttu-id="a8166-829">已修正在一組傳回的搜尋結果中，依類別結果排序不會顯示類別色彩的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-829">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

- <span data-ttu-id="a8166-830">修正將 [如果有，顯示使用者的照片] 選項停用時，搜尋不會顯示有關使用者的任何資訊的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-830">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="a8166-831">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8166-831">PowerPoint</span></span>

- <span data-ttu-id="a8166-832">此變更修正了會導致包含 emojis 的 PowerPoint 檔案在儲存時發生失敗的錯誤。</span><span class="sxs-lookup"><span data-stu-id="a8166-832">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

- <span data-ttu-id="a8166-833">此變更修正了在 PowerPoint 或 Word 中呈現內嵌為 OLE 物件的舊版 Excel 圖表時可能不會永遠顯示圖表標題的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-833">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="a8166-834">我們已修正將文字從 Excel 複製到 PowerPoint 時可能會導致其格式設定發生變更的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-834">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="a8166-835">此變更修正了使用 [全字拼寫須相符] 來尋找特殊字元時，不一定能正常運作的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-835">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="a8166-836">Project</span><span class="sxs-lookup"><span data-stu-id="a8166-836">Project</span></span>

- <span data-ttu-id="a8166-837">修正無法正確計算摘要工作日期的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-837">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="a8166-838">修正不先執行 OpenUndoTransaction 方法就不能觸發 OnUndoOrRedo 事件的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-838">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="a8166-839">已修正當使用者按一下 [排程群組] 內 [工作] 功能區中的 [停用] 按鈕時，不會觸發 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) 事件的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-839">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the “Inactivate” button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="a8166-840">如果您在 [表單類型] 檢視中設定前置任務或後置任務詳細資訊，則 ProjectBeforeTaskChange Visual Basic Applications (VBA) 事件不會一律擷取變更。</span><span class="sxs-lookup"><span data-stu-id="a8166-840">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="a8166-841">例如，如果刪除了某個相依性，並在表單上按一下 [確定]，則不會觸發該事件。</span><span class="sxs-lookup"><span data-stu-id="a8166-841">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="a8166-842">已修正此問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-842">This behavior has been fixed.</span></span>

- <span data-ttu-id="a8166-843">已修正在進行變更 (例如日期變更) 之後，實際工作成本 (ACWP) 的最新值不會顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-843">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="a8166-844">已修正使用「最近使用」(MRU) 功能表開啟專案時，會使用 [讀取/寫入] 存取權開啟專案的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-844">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="a8166-845">這項變更修正了如果您建立包含開始日期和時間 (但無工期) 的手動工作，則時間表上的時間顯示不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-845">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="a8166-846">已修正使用回曆列印時間表時，會導致列印檢視中略過或重複一個月的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-846">Fixed an issue where printing a timeline using a Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="a8166-847">這項變更解決了在團隊規劃中使用 GDI 物件時，可能導致 GDI 物件分配過多並產生記憶體不足的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-847">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

- <span data-ttu-id="a8166-848">修正了以下問題：如果執行 'CustomFieldValueListGetItem' 且自訂欄位的查閱資料表不存在，系統會建立一個不應建立的空白查閱資料表。</span><span class="sxs-lookup"><span data-stu-id="a8166-848">Fixed an issue where if CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

- <span data-ttu-id="a8166-849">在表單檢視中編輯前置/後續任務資料時，會觸發額外的 ProjectBeforeTaskChange 事件</span><span class="sxs-lookup"><span data-stu-id="a8166-849">WhenPredecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired</span></span>

- <span data-ttu-id="a8166-850">修正了當開啟保護實際工作的設定時，使用者無法輸入分時期基準工時的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-850">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="a8166-851">Word</span><span class="sxs-lookup"><span data-stu-id="a8166-851">Word</span></span>

- <span data-ttu-id="a8166-852">此變更修正了將游標懸停在提示上並不會醒目提示其卡片的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-852">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="a8166-853">此變更修正了以下問題：從 [檢視] 功能表選取多個頁面時，其中的 [註解] 窗格會顯示為空白。</span><span class="sxs-lookup"><span data-stu-id="a8166-853">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

- <span data-ttu-id="a8166-854">已修正張貼留言功能停用的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-854">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="a8166-855">此變更修正了使用套索選取工具時，群組圖形中的文字會暫時消失的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-855">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="a8166-856">此變更解決了處理格式錯誤或無效通訊協定資訊影像時所導致的延遲問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-856">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="a8166-857">此變更修正了在 PowerPoint 或 Word 中呈現內嵌為 OLE 物件的舊版 Excel 圖表時可能不會永遠顯示圖表標題的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-857">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="a8166-858">這項變更解決了帳戶管理員不會分派訊息而導致協力廠商應用程式懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-858">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="a8166-859">此變更修正了在雙頁檢視中建立註解時，註解錨點不一定會顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-859">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="a8166-860">修正輸入或編輯備註然後使用 Ctrl+A 時，會導致選取畫布中的文字，而不只是選取備註卡片內文字的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-860">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>

- <span data-ttu-id="a8166-861">已修正如果段落的樣式是連結至清單的樣式上階，則該清單的編號可能會遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-861">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

- <span data-ttu-id="a8166-862">這項變更修正了目錄會使用文件中未包含的標題樣式進行更新的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-862">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="a8166-863">我們已修正文件中的文字對齊，在使用 [快速列印] 進行列印之後嘗試進行編輯時變得混亂的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-863">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="a8166-864">我們已修正將兩份文件合併成一份文件時的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-864">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="a8166-865">已修正在寄送文件時，儲存在 Word 文件中的數位簽章會被刪除的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-865">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

- <span data-ttu-id="a8166-866">修正標示的修訂若與方程式有關，在儲存檔案時可能會導致失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-866">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-april-14"></a><span data-ttu-id="a8166-868">版本 2003：4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="a8166-868">Version 2003: April 14</span></span>
<span data-ttu-id="a8166-869">*版本 2003 (組建 12624.20466)*</span><span class="sxs-lookup"><span data-stu-id="a8166-869">*Version 2003 (Build 12624.20466)*</span></span>

<span data-ttu-id="a8166-870">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="a8166-870">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

- <span data-ttu-id="a8166-872">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="a8166-872">Various bugs and performance fixes.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2003-april-09"></a><span data-ttu-id="a8166-874">版本 2003：4 月 9 日</span><span class="sxs-lookup"><span data-stu-id="a8166-874">Version 2003: April 09</span></span>
<span data-ttu-id="a8166-875">*版本 2003 (組建 12624.20442)*</span><span class="sxs-lookup"><span data-stu-id="a8166-875">*Version 2003 (Build 12624.20442)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="a8166-877">功能更新</span><span class="sxs-lookup"><span data-stu-id="a8166-877">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a8166-878">Excel</span><span class="sxs-lookup"><span data-stu-id="a8166-878">Excel</span></span>

- <span data-ttu-id="a8166-879">**M365 進階版內容選擇器：** 讓您的文件栩栩如生！</span><span class="sxs-lookup"><span data-stu-id="a8166-879">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="a8166-880">探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="a8166-880">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="a8166-881">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-881">Outlook</span></span>

- <span data-ttu-id="a8166-882">**M365 進階版內容選擇器：** 讓您的文件栩栩如生！</span><span class="sxs-lookup"><span data-stu-id="a8166-882">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="a8166-883">探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="a8166-883">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8166-884">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8166-884">PowerPoint</span></span>

- <span data-ttu-id="a8166-885">**M365 進階版內容選擇器：** 讓您的文件栩栩如生！</span><span class="sxs-lookup"><span data-stu-id="a8166-885">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="a8166-886">探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="a8166-886">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="word"></a><span data-ttu-id="a8166-887">Word</span><span class="sxs-lookup"><span data-stu-id="a8166-887">Word</span></span>

- <span data-ttu-id="a8166-888">**M365 進階版內容選擇器：** 讓您的文件栩栩如生！</span><span class="sxs-lookup"><span data-stu-id="a8166-888">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="a8166-889">探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="a8166-889">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)




[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-april-03"></a><span data-ttu-id="a8166-893">版本 2003：4 月 3 日</span><span class="sxs-lookup"><span data-stu-id="a8166-893">Version 2003: April 03</span></span>
<span data-ttu-id="a8166-894">*版本 2003 (組建 12624.20410)*</span><span class="sxs-lookup"><span data-stu-id="a8166-894">*Version 2003 (Build 12624.20410)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="a8166-896">解決的問題</span><span class="sxs-lookup"><span data-stu-id="a8166-896">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a8166-897">Excel</span><span class="sxs-lookup"><span data-stu-id="a8166-897">Excel</span></span>

- <span data-ttu-id="a8166-898">使用 VBA 應用程式的 Application.Evaluate 在某些情況下，對使用者定義的函數無法運作。</span><span class="sxs-lookup"><span data-stu-id="a8166-898">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="a8166-899">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-899">Outlook</span></span>

- <span data-ttu-id="a8166-900">解決使用滑鼠上的「X」按鈕時，導致使用者偶爾發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-900">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

### <a name="project"></a><span data-ttu-id="a8166-901">Project</span><span class="sxs-lookup"><span data-stu-id="a8166-901">Project</span></span>

- <span data-ttu-id="a8166-902">在表單檢視中編輯前置/後續任務資料時，會觸發額外的 ProjectBeforeTaskChangeevent。</span><span class="sxs-lookup"><span data-stu-id="a8166-902">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChangeevent is fired.</span></span>

### <a name="word"></a><span data-ttu-id="a8166-903">Word</span><span class="sxs-lookup"><span data-stu-id="a8166-903">Word</span></span>

- <span data-ttu-id="a8166-904">解決使用滑鼠上的「X」按鈕時，導致使用者偶爾發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-904">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-march-31"></a><span data-ttu-id="a8166-906">版本 2003：3 月 31 日</span><span class="sxs-lookup"><span data-stu-id="a8166-906">Version 2003: March 31</span></span>
<span data-ttu-id="a8166-907">*版本 2003 (組建 12624.20382)*</span><span class="sxs-lookup"><span data-stu-id="a8166-907">*Version 2003 (Build 12624.20382)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="a8166-909">功能更新</span><span class="sxs-lookup"><span data-stu-id="a8166-909">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="a8166-910">Access</span><span class="sxs-lookup"><span data-stu-id="a8166-910">Access</span></span>

- <span data-ttu-id="a8166-911">**「新增資料表」工作窗格：** Access 的全新「新增資料表」工作窗格終於推出！</span><span class="sxs-lookup"><span data-stu-id="a8166-911">**"Add Tables" Task Pane:** Access's new "Add Tables" Task Pane is finally here!</span></span> <span data-ttu-id="a8166-912">這項功能可讓您輕鬆選取/多重選取要在查詢視窗中新增/移除的資料表，而不需要瀏覽至查詢和關聯視圖的「顯示資料表」對話方塊。</span><span class="sxs-lookup"><span data-stu-id="a8166-912">This feature allows you to easily select/multi-select which tables they'd like to add/remove into a query window, without navigating to the "Show Tables" dialog for queries and for relationship view.</span></span> <span data-ttu-id="a8166-913">這也包含新的「連結」索引標籤，可顯示連結的資料表、可篩選目前清單的搜尋方塊、「拖放」行為及更多功能！</span><span class="sxs-lookup"><span data-stu-id="a8166-913">This also includes a new "links" tab to display linked tables, a search box to filter the current list, "drag and drop" behavior, and more!</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="a8166-916">解決的問題</span><span class="sxs-lookup"><span data-stu-id="a8166-916">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="a8166-917">Project</span><span class="sxs-lookup"><span data-stu-id="a8166-917">Project</span></span>

- <span data-ttu-id="a8166-918"><span style="display:inline !important;">修正了當開啟保護實際工作的設定時，使用者無法輸入分時期基準工時的問題。</span></span><span class="sxs-lookup"><span data-stu-id="a8166-918"><span style="display:inline !important;">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span></span><br>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-march-25"></a><span data-ttu-id="a8166-920">版本 2003：3 月 25 日</span><span class="sxs-lookup"><span data-stu-id="a8166-920">Version 2003: March 25</span></span>
<span data-ttu-id="a8166-921">*版本 2003 (組建 12624.20320)*</span><span class="sxs-lookup"><span data-stu-id="a8166-921">*Version 2003 (Build 12624.20320)*</span></span>

- <span data-ttu-id="a8166-922">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="a8166-922">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-23"></a><span data-ttu-id="a8166-923">版本 2003：3 月 23 日</span><span class="sxs-lookup"><span data-stu-id="a8166-923">Version 2003: March 23</span></span>
<span data-ttu-id="a8166-924">*版本 2003 (組建 12624.20296)*</span><span class="sxs-lookup"><span data-stu-id="a8166-924">*Version 2003 (Build 12624.20296)*</span></span>

- <span data-ttu-id="a8166-925">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="a8166-925">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-21"></a><span data-ttu-id="a8166-926">版本 2003：3 月 21 日</span><span class="sxs-lookup"><span data-stu-id="a8166-926">Version 2003: March 21</span></span>
<span data-ttu-id="a8166-927">*版本 2003 (組建 12624.20276)*</span><span class="sxs-lookup"><span data-stu-id="a8166-927">*Version 2003 (Build 12624.20276)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="a8166-929">功能更新</span><span class="sxs-lookup"><span data-stu-id="a8166-929">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a8166-930">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-930">Outlook</span></span>

- <span data-ttu-id="a8166-931">**加入會議而不需離開您的收件匣：** 不需切換至您的行事曆即可加入線上會議。</span><span class="sxs-lookup"><span data-stu-id="a8166-931">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="a8166-932">將行事曆釘選到 [待辦事項] 窗格之後，只要按一下就能加入任何會議。</span><span class="sxs-lookup"><span data-stu-id="a8166-932">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="a8166-933">**行事曆新版視覺效果：** 去年，我們提供了全新的郵件體驗，而今年將為您帶來嶄新的行事曆！</span><span class="sxs-lookup"><span data-stu-id="a8166-933">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar’s turn to get a facelift!</span></span> <span data-ttu-id="a8166-934">這些更新是全新但令人熟悉的，身為經驗豐富的 Outlook 使用者的您，可以立即上手並更具生產力。</span><span class="sxs-lookup"><span data-stu-id="a8166-934">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8166-935">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8166-935">PowerPoint</span></span>

- <span data-ttu-id="a8166-936">**在投影片放映期間更新投影片：** 在簡報期間，更新由其他作者變更的投影片。</span><span class="sxs-lookup"><span data-stu-id="a8166-936">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2003-march-16"></a><span data-ttu-id="a8166-938">版本 2003：3 月 16 日</span><span class="sxs-lookup"><span data-stu-id="a8166-938">Version 2003: March 16</span></span>
<span data-ttu-id="a8166-939">*版本 2003 (組建 12624.20224)*</span><span class="sxs-lookup"><span data-stu-id="a8166-939">*Version 2003 (Build 12624.20224)*</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="a8166-941">功能更新</span><span class="sxs-lookup"><span data-stu-id="a8166-941">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a8166-942">Excel</span><span class="sxs-lookup"><span data-stu-id="a8166-942">Excel</span></span>

- <span data-ttu-id="a8166-943">**挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。</span><span class="sxs-lookup"><span data-stu-id="a8166-943">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="outlook"></a><span data-ttu-id="a8166-944">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-944">Outlook</span></span>

- <span data-ttu-id="a8166-945">**挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。</span><span class="sxs-lookup"><span data-stu-id="a8166-945">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8166-946">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8166-946">PowerPoint</span></span>

- <span data-ttu-id="a8166-947">**挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。</span><span class="sxs-lookup"><span data-stu-id="a8166-947">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="word"></a><span data-ttu-id="a8166-948">Word</span><span class="sxs-lookup"><span data-stu-id="a8166-948">Word</span></span>

- <span data-ttu-id="a8166-949">**挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。</span><span class="sxs-lookup"><span data-stu-id="a8166-949">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a8166-950">Office 套件</span><span class="sxs-lookup"><span data-stu-id="a8166-950">Office Suite</span></span>

- <span data-ttu-id="a8166-951">**索引標籤式窗格：** 現在您可以使用應用程式右側的索引標籤 UI，在多個窗格之間切換。</span><span class="sxs-lookup"><span data-stu-id="a8166-951">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="a8166-952">只有當您開啟 2 個以上的窗格時，該 UI 才會顯示。</span><span class="sxs-lookup"><span data-stu-id="a8166-952">The UI will only be visible when you have 2+ panes open.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="a8166-955">解決的問題</span><span class="sxs-lookup"><span data-stu-id="a8166-955">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a8166-956">Excel</span><span class="sxs-lookup"><span data-stu-id="a8166-956">Excel</span></span>

- <span data-ttu-id="a8166-957">已解決當來源活頁簿關閉時，外部連結無法在填滿時更新的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-957">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

### <a name="outlook"></a><span data-ttu-id="a8166-958">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-958">Outlook</span></span>

- <span data-ttu-id="a8166-959">已解決導致使用者在工作管理員中看到 Outlook 處理序延遲的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-959">Addressed an issue that caused users to see the Outlook process lingering in task manager after exiting.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-march-10"></a><span data-ttu-id="a8166-961">版本 2003：3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="a8166-961">Version 2003: March 10</span></span>
<span data-ttu-id="a8166-962">*版本 2003 (組建 12624.20176)*</span><span class="sxs-lookup"><span data-stu-id="a8166-962">*Version 2003 (Build 12624.20176)*</span></span>

<span data-ttu-id="a8166-963">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="a8166-963">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)
### <a name="feature-updates"></a><span data-ttu-id="a8166-965">功能更新</span><span class="sxs-lookup"><span data-stu-id="a8166-965">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a8166-966">Excel</span><span class="sxs-lookup"><span data-stu-id="a8166-966">Excel</span></span>
- <span data-ttu-id="a8166-967">**敏感度標籤**：您現在可以套用組織設定、用來提示您輸入自訂權限的敏感度標籤。</span><span class="sxs-lookup"><span data-stu-id="a8166-967">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="a8166-968">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8166-968">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a><span data-ttu-id="a8166-969">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8166-969">PowerPoint</span></span>
- <span data-ttu-id="a8166-970">**敏感度標籤**：您現在可以套用組織設定、用來提示您輸入自訂權限的敏感度標籤。</span><span class="sxs-lookup"><span data-stu-id="a8166-970">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="a8166-971">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8166-971">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a><span data-ttu-id="a8166-972">Word</span><span class="sxs-lookup"><span data-stu-id="a8166-972">Word</span></span>
- <span data-ttu-id="a8166-973">**敏感度標籤**：您現在可以套用組織設定、用來提示您輸入自訂權限的敏感度標籤。</span><span class="sxs-lookup"><span data-stu-id="a8166-973">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="a8166-974">深入了解</span><span class="sxs-lookup"><span data-stu-id="a8166-974">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)
</br>

### <a name="resolved-issues"></a><span data-ttu-id="a8166-975">解決的問題</span><span class="sxs-lookup"><span data-stu-id="a8166-975">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a8166-976">Excel</span><span class="sxs-lookup"><span data-stu-id="a8166-976">Excel</span></span>

- <span data-ttu-id="a8166-977">修正 [檔案]\[選項] 對話方塊上的 [確定] 按鈕顯示為灰色停用狀態，但功能並未受影響的外觀問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-977">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="a8166-978">修正使用者在重新命名樞紐分析表度量值時可能遇到的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-978">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>

- <span data-ttu-id="a8166-979">修正交叉分析篩選器中的文字在預覽列印中無法正確縮放的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-979">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

- <span data-ttu-id="a8166-980">已修正使用者在使用 VBA 巨集清除範圍內容時可能遇到的效能問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-980">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="a8166-981">已修正當使用者執行與功能區互動的巨集時，導致 UI 快閃的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-981">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>

- <span data-ttu-id="a8166-982">已修正當檔案中的第一個字為 TABLE 時，CSV 檔案載入錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-982">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>

- <span data-ttu-id="a8166-983">已修正當您在兩個具有不同縮放比例的活頁簿之間切換時，使用者可能遇到的當機問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-983">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

- <span data-ttu-id="a8166-984">修正 CUBEVALUE 函數有時會傳回不正確結果的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-984">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="a8166-985">此變更可解決物件模型中的執行階段錯誤，以及當增益集要求的文件/工作表上的主機項目包含具有 noSelect 鎖定的圖形時，應用程式 (Excel、Word) 的潛在當機。</span><span class="sxs-lookup"><span data-stu-id="a8166-985">This change addresses a run-time error in the object model and potential crash of the App (Excel, Word) when Add-ins ask for Host Items on documents/worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="a8166-986">解決導致 Outlook 使用者在同步處理設定時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-986">Addresses an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>



### <a name="outlook"></a><span data-ttu-id="a8166-987">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-987">Outlook</span></span>

- <span data-ttu-id="a8166-988">修正使用 Outlook Web Access 建立規則時不會保存到 Exchange 伺服器，並導致衝突的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-988">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>

- <span data-ttu-id="a8166-989">解決導致 Outlook 使用者在同步處理設定時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-989">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

- <span data-ttu-id="a8166-990">修正 Outlook 在深色模式中不會在 [寄件者:] 欄位中顯示下拉式清單的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-990">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>

- <span data-ttu-id="a8166-991">解決即使已關閉記錄，在某些情況下仍導致 Outlook 異常產生記錄輸出的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-991">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

- <span data-ttu-id="a8166-992">已解決當持續整夜執行 Outlook 時，導致使用者無法開啟公用資料夾訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-992">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>

- <span data-ttu-id="a8166-993">已修正在新增 Gmail 帳戶的驗證工作流程中，[權限] 頁面上的 [允許] 和 [拒絕] 按鈕停用的爭用情況。</span><span class="sxs-lookup"><span data-stu-id="a8166-993">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>

- <span data-ttu-id="a8166-994">解決導致使用者無法存取 [空閒/忙碌選項] 行事曆權限對話方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-994">Addressed an issue that caused users to lose access to the &quot;Free Busy Options&quot; calendar permissions dialog.</span></span>

- <span data-ttu-id="a8166-995">修正開啟某些傳送自不同時區的週期性會議執行個體時，可能導致出現警示：「很抱歉，開啟此項目時發生問題」的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-995">Fixed an issue that may result in the alert: &quot;Sorry we're having trouble opening this item&quot; when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="a8166-996">已解決從該郵件拖放附件後造成使用者無法重新開啟 .msg 檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-996">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="a8166-997">修正從 Outlook 上傳檔案附件到 OneDrive 後，造成包含括號之附件名稱的檔案名稱被變更。</span><span class="sxs-lookup"><span data-stu-id="a8166-997">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

- <span data-ttu-id="a8166-998">解決在其他應用程式中開啟某個檔案時，導致使用者無法透過檔案總管將該檔案附加至郵件訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-998">Addressed an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

- <span data-ttu-id="a8166-999">解決導致 Outlook 使用者在同步處理設定時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-999">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8166-1000">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8166-1000">PowerPoint</span></span>

- <span data-ttu-id="a8166-1001">修正將滑鼠移至縮圖上時，建議的縮圖閃動的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1001">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="a8166-1002">在某些情況下，這可能會導致 PowerPoint 當機。</span><span class="sxs-lookup"><span data-stu-id="a8166-1002">In some cases this could cause PowerPoint to crash.</span></span>

- <span data-ttu-id="a8166-1003">修正 [檔案]\[選項] 對話方塊上的 [確定] 按鈕顯示為灰色停用狀態，但功能並未受影響的外觀問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1003">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="a8166-1004">修正儲存包含 Excel 圖表的 PowerPoint 或 Word 文件會導致失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1004">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>



### <a name="project"></a><span data-ttu-id="a8166-1005">Project</span><span class="sxs-lookup"><span data-stu-id="a8166-1005">Project</span></span>

- <span data-ttu-id="a8166-1006">修正在將任務標示為完成之後，不正確地將任務完成百分比變更為低於 100% 的值的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1006">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="a8166-1007">修正不先執行 OpenUndoTransaction 方法就不能觸發 OnUndoOrRedo 事件的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1007">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="a8166-1008">修正無法正確計算摘要工作日期的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1008">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

### <a name="visio"></a><span data-ttu-id="a8166-1009">Visio</span><span class="sxs-lookup"><span data-stu-id="a8166-1009">Visio</span></span>

- <span data-ttu-id="a8166-1010">[圖形資訊] 窗格的 [圖案資料] 區段下顯示的詳細資料，與在 Visio 桌面版中開啟該檔案時所顯示的不一致。</span><span class="sxs-lookup"><span data-stu-id="a8166-1010">Shape info pane was showing inconsistent details under Shape Data section, with respect to the file when opened in Visio Desktop.</span></span> <span data-ttu-id="a8166-1011">已修正此問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1011">It has now been fixed.</span></span>

- <span data-ttu-id="a8166-1012">在 2016 之前版本中匯入的點陣圖，由於某些安全性檢查而未呈現。</span><span class="sxs-lookup"><span data-stu-id="a8166-1012">Bitmaps imported in versions before 2016 were not being rendered due to some security checks.</span></span> <span data-ttu-id="a8166-1013">我們已在 Visio 訂閱中修正此問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1013">We have fixed this issue in Visio Subscription.</span></span>

### <a name="word"></a><span data-ttu-id="a8166-1014">Word</span><span class="sxs-lookup"><span data-stu-id="a8166-1014">Word</span></span>

- <span data-ttu-id="a8166-1015">已修正當滑鼠指標暫留在註解卡片上方時，未醒目提示註解卡片的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1015">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>

- <span data-ttu-id="a8166-1016">修正按 Tab 鍵導覽註解卡片時，註解編輯方塊上的焦點無法顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1016">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="a8166-1017">修正 [檔案]\[選項] 對話方塊上的 [確定] 按鈕顯示為灰色停用狀態，但功能並未受影響的外觀問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1017">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="a8166-1018">在使用中的文件共同撰寫工作階段中，直接在註解卡片中新增影像可能會導致新增標籤。</span><span class="sxs-lookup"><span data-stu-id="a8166-1018">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="a8166-1019">我們已修正此問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1019">This issue has been fixed.</span></span>

- <span data-ttu-id="a8166-1020">在方程式中插入控制項 (例如文字內容控制項)，然後儲存再開啟檔案，便會導致內容無法讀取的錯誤。</span><span class="sxs-lookup"><span data-stu-id="a8166-1020">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="a8166-1021">修正將先前使用密碼保護的檔案儲存到雲端儲存空間無法運作的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1021">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

- <span data-ttu-id="a8166-1022">修正受保護無法編輯之文件的比較功能問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1022">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>




### <a name="office-suite"></a><span data-ttu-id="a8166-1023">Office 套件</span><span class="sxs-lookup"><span data-stu-id="a8166-1023">Office Suite</span></span>

- <span data-ttu-id="a8166-1024">當您將 Multichoice/Lookup/Managed-metadata 屬性與 Word/Excel/PowerPoint 文件一起使用並儲存至 SharePoint 文件庫時，這些屬性之前限制為 255 個字元。</span><span class="sxs-lookup"><span data-stu-id="a8166-1024">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="a8166-1025">當這些屬性超過 255 個字元時，這類文件就無法儲存。</span><span class="sxs-lookup"><span data-stu-id="a8166-1025">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="a8166-1026">在此變更中，此限制已增加到 2048 個字元。</span><span class="sxs-lookup"><span data-stu-id="a8166-1026">With this change, this limit has been increased to 2048 characters.</span></span>

- <span data-ttu-id="a8166-1027">修正 Word/Excel/PowerPoint 中的使用者主體名稱 (UPN) 不再區分大小寫，導致在 SharePoint 上使用檔案時較少發生失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1027">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="a8166-1028">修正在 Word/Excel/PowerPoint 中開啟來自相同 SharePoint 文件庫的多個文件時，僅掃描開啟的第一個文件是否符合原則的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1028">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-march-05"></a><span data-ttu-id="a8166-1030">版本 2002：3 月 5 日</span><span class="sxs-lookup"><span data-stu-id="a8166-1030">Version 2002: March 05</span></span>
<span data-ttu-id="a8166-1031">*版本 2002 (組建 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="a8166-1031">*Version 2002 (Build 12527.20278)*</span></span>

- <span data-ttu-id="a8166-1032">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="a8166-1032">Various bugs and performance fixes.</span></span>


## <a name="version-2002-march-04"></a><span data-ttu-id="a8166-1033">版本 2002：3 月 4 日</span><span class="sxs-lookup"><span data-stu-id="a8166-1033">Version 2002: March 04</span></span>
<span data-ttu-id="a8166-1034">*版本 2002 (組建 12527.20264)*</span><span class="sxs-lookup"><span data-stu-id="a8166-1034">*Version 2002 (Build 12527.20264)*</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="a8166-1036">解決的問題</span><span class="sxs-lookup"><span data-stu-id="a8166-1036">Resolved issues</span></span>

### <a name="project"></a><span data-ttu-id="a8166-1037">Project</span><span class="sxs-lookup"><span data-stu-id="a8166-1037">Project</span></span>
- <span data-ttu-id="a8166-1038">修正無法正確計算摘要工作日期的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1038">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>


### <a name="office-suite"></a><span data-ttu-id="a8166-1039">Office 套件</span><span class="sxs-lookup"><span data-stu-id="a8166-1039">Office Suite</span></span>
- <span data-ttu-id="a8166-1040">修正在 Word/Excel/PowerPoint 中開啟來自相同 SharePoint 文件庫的多個文件時，僅掃描開啟的第一個文件是否符合原則的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1040">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-march-01"></a><span data-ttu-id="a8166-1042">版本 2002：3 月 1 日</span><span class="sxs-lookup"><span data-stu-id="a8166-1042">Version 2002: March 01</span></span>
<span data-ttu-id="a8166-1043">*版本 2002 (組建 12527.20242)*</span><span class="sxs-lookup"><span data-stu-id="a8166-1043">*Version 2002 (Build 12527.20242)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="a8166-1044">解決的問題</span><span class="sxs-lookup"><span data-stu-id="a8166-1044">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="a8166-1045">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-1045">Outlook</span></span>

- <span data-ttu-id="a8166-1046">解決導致協力廠商應用程式無法傳送電子郵件的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1046">Addresses an issue that caused third party applications to be unable to send email.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-february-24"></a><span data-ttu-id="a8166-1048">版本 2002：2 月 24 日</span><span class="sxs-lookup"><span data-stu-id="a8166-1048">Version 2002: February 24</span></span>
<span data-ttu-id="a8166-1049">*版本 2002 (組建 12527.20194)*</span><span class="sxs-lookup"><span data-stu-id="a8166-1049">*Version 2002 (Build 12527.20194)*</span></span>

- <span data-ttu-id="a8166-1050">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="a8166-1050">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-22"></a><span data-ttu-id="a8166-1051">版本 2002：2 月 22 日</span><span class="sxs-lookup"><span data-stu-id="a8166-1051">Version 2002: February 22</span></span>
<span data-ttu-id="a8166-1052">*版本 2002 (組建 12527.20186)*</span><span class="sxs-lookup"><span data-stu-id="a8166-1052">*Version 2002 (Build 12527.20186)*</span></span>

- <span data-ttu-id="a8166-1053">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="a8166-1053">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-21"></a><span data-ttu-id="a8166-1054">版本 2002：2 月 21 日</span><span class="sxs-lookup"><span data-stu-id="a8166-1054">Version 2002: February 21</span></span>
<span data-ttu-id="a8166-1055">*版本 2002 (組建 12527.20174)*</span><span class="sxs-lookup"><span data-stu-id="a8166-1055">*Version 2002 (Build 12527.20174)*</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="a8166-1057">功能更新</span><span class="sxs-lookup"><span data-stu-id="a8166-1057">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="a8166-1058">Access</span><span class="sxs-lookup"><span data-stu-id="a8166-1058">Access</span></span>

- <span data-ttu-id="a8166-1059">**在查詢設計工具、SQL 檢視和關聯視窗中工作時更具生產力：** 在資料表上按一下滑鼠右鍵即可開啟、設計、調整大小及隱藏它。</span><span class="sxs-lookup"><span data-stu-id="a8166-1059">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="a8166-1060">在 SQL 檢視中搜尋及取代文字。</span><span class="sxs-lookup"><span data-stu-id="a8166-1060">Search and replace text in SQL View.</span></span> <span data-ttu-id="a8166-1061">在 [關聯圖] 視窗中選取多個資料表。</span><span class="sxs-lookup"><span data-stu-id="a8166-1061">Select multiple tables in the Relationships window.</span></span>

### <a name="outlook"></a><span data-ttu-id="a8166-1062">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-1062">Outlook</span></span>

- <span data-ttu-id="a8166-1063">**受限 WiFi 網路的新體驗：** 是否曾經加入需要登入網頁的 WiFi 網路呢？</span><span class="sxs-lookup"><span data-stu-id="a8166-1063">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="a8166-1064">Outlook 現在會偵測這項要求並協助您取得連結。</span><span class="sxs-lookup"><span data-stu-id="a8166-1064">Outlook now detects this and helps you get connected.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="a8166-1067">解決的問題</span><span class="sxs-lookup"><span data-stu-id="a8166-1067">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a8166-1068">Excel</span><span class="sxs-lookup"><span data-stu-id="a8166-1068">Excel</span></span>

- <div style="box-sizing:border-box;"><span data-ttu-id="a8166-1069">修正 CUBEVALUE 函數有時會傳回不正確結果的問題。&nbsp;<span style="display:inline !important;"></span></span><span class="sxs-lookup"><span data-stu-id="a8166-1069">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.&nbsp;<span style="display:inline !important;"></span></span></span><br>


### <a name="outlook"></a><span data-ttu-id="a8166-1070">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-1070">Outlook</span></span>

- <span data-ttu-id="a8166-1071">解決導致會議的位置欄位中的逗號變成分號的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1071">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>


- <span data-ttu-id="a8166-1072">解決在多個視窗中檢視相同項目時可能會導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1072">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>


- <span data-ttu-id="a8166-1073">解決即使將同步處理滑桿設定為較小的設定，也會導致 Outlook 非預期地同步處理所有郵件的問題。&nbsp;</span><span class="sxs-lookup"><span data-stu-id="a8166-1073">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.&nbsp;</span></span>


- <span data-ttu-id="a8166-1074">解決會導致使用黑色佈景主題的使用者看到 [從]&quot;&quot; 下拉式功能表在白色背景上顯示白色文字的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1074">Addresses an issue that caused users with Black Theme to see the &quot;From&quot; dropdown show white text on a white background.</span></span>


- <span data-ttu-id="a8166-1075"><span style="display:inline !important;">此變更會還原在郵件標頭中檢視多行主旨的功能。</span></span><span class="sxs-lookup"><span data-stu-id="a8166-1075"><span style="display:inline !important;">This change restores the ability to view multi-line subjects in the message header.</span></span></span><br>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-february-18"></a><span data-ttu-id="a8166-1077">版本 2002：2 月 18 日</span><span class="sxs-lookup"><span data-stu-id="a8166-1077">Version 2002: February 18</span></span>
<span data-ttu-id="a8166-1078">*版本 2002 (組建 12527.20138)*</span><span class="sxs-lookup"><span data-stu-id="a8166-1078">*Version 2002 (Build 12527.20138)*</span></span>

## <a name="version-2002-february-11"></a><span data-ttu-id="a8166-1079">版本 2002：2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="a8166-1079">Version 2002: February 11</span></span>
<span data-ttu-id="a8166-1080">*版本 2002 (組建 12527.20092)*</span><span class="sxs-lookup"><span data-stu-id="a8166-1080">*Version 2002 (Build 12527.20092)*</span></span>

<span data-ttu-id="a8166-1081">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="a8166-1081">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="a8166-1083">功能更新</span><span class="sxs-lookup"><span data-stu-id="a8166-1083">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a8166-1084">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-1084">Outlook</span></span>

- <span data-ttu-id="a8166-1085">**將電子郵件拖曳到您擁有的群組：** 從您的 [收件匣] 拖曳郵件和交談以將它們移動和複製。</span><span class="sxs-lookup"><span data-stu-id="a8166-1085">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="a8166-1086">您拖曳的郵件將會與所有群組成員共用。</span><span class="sxs-lookup"><span data-stu-id="a8166-1086">Messages you drag will be shared with all group members.</span></span>

### <a name="word"></a><span data-ttu-id="a8166-1087">Word</span><span class="sxs-lookup"><span data-stu-id="a8166-1087">Word</span></span>

- <span data-ttu-id="a8166-1088">**其他人更快速看到您的變更：** 共同撰寫增強功能表示，共同作業者可較以往更快速看到您的變更。</span><span class="sxs-lookup"><span data-stu-id="a8166-1088">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a8166-1089">Office 套件</span><span class="sxs-lookup"><span data-stu-id="a8166-1089">Office Suite</span></span>

- <span data-ttu-id="a8166-1090">**更清楚的狀態列圖示：** 狀態列圖示現在更容易查看。</span><span class="sxs-lookup"><span data-stu-id="a8166-1090">**Clearer status bar icons:** Status bar icons are now easier to see.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="a8166-1093">解決的問題</span><span class="sxs-lookup"><span data-stu-id="a8166-1093">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="a8166-1094">Access</span><span class="sxs-lookup"><span data-stu-id="a8166-1094">Access</span></span>

- <span data-ttu-id="a8166-1095">Access 範本應不再導致資料庫中的附件欄出現故障。</span><span class="sxs-lookup"><span data-stu-id="a8166-1095">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="a8166-1096">個體化範本後，您現在應該可以將附件欄新增至資料庫。</span><span class="sxs-lookup"><span data-stu-id="a8166-1096">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="a8166-1097">此更新會修正使用 ADODB 的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1097">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="a8166-1098">VB 程式碼中的記錄器物件可能會不正確地報告錯誤。</span><span class="sxs-lookup"><span data-stu-id="a8166-1098">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="a8166-1099">此更新修正可能會導致 Microsoft Access 無法識別連結的 SQL Server 資料表中的識別資料行的問題，這可能會導致不正確地將資料列報告為已刪除。</span><span class="sxs-lookup"><span data-stu-id="a8166-1099">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>


### <a name="excel"></a><span data-ttu-id="a8166-1100">Excel</span><span class="sxs-lookup"><span data-stu-id="a8166-1100">Excel</span></span>

- <span data-ttu-id="a8166-1101">已修正未顯示操作功能表中的註解命令的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1101">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>


- <span data-ttu-id="a8166-1102">已修正以下問題：將文字轉換成具有溢出陣列之儲存格的欄時，某些使用者發生當機。</span><span class="sxs-lookup"><span data-stu-id="a8166-1102">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>


- <span data-ttu-id="a8166-1103">修正使用「資料剖析」搭配動態陣列時，Excel 會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1103">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="a8166-1104">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8166-1104">Outlook</span></span>

- <span data-ttu-id="a8166-1105">修正以月檢視在行事曆中捲動時，無法顯示之前的行事曆活動的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1105">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="a8166-1106">儲存在左側瀏覽窗格 [我的最愛] 的資料夾可能會間歇性消失。</span><span class="sxs-lookup"><span data-stu-id="a8166-1106">Folders saved in 'Favorites' in the left navigation pane may intermittently disappear.</span></span>


- <span data-ttu-id="a8166-1107">已解決導致使用者在指定無效寄件者地址時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1107">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>


- <span data-ttu-id="a8166-1108">已解決導致在某些情況下無法使用相關選項來停用標幟項目醒目提示的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1108">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="a8166-1109">已解決導致使用者在取消帳戶設定時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1109">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>


- <span data-ttu-id="a8166-1110">修正根據保留原則到期的電子郵件會顯示兩個標籤的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1110">Fixed an issue where emails expiring based on a retention policy would display two labels.</span></span> <span data-ttu-id="a8166-1111">其中一個顯示郵件將在一天內過期，另一個則顯示將在兩天內到期。</span><span class="sxs-lookup"><span data-stu-id="a8166-1111">One showing that the mail will expire in one day and another displaying that it will expire in two days.</span></span>


- <span data-ttu-id="a8166-1112">已解決在 Citrix 環境中檢視 30 個以上的行事曆時，導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1112">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="a8166-1113">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8166-1113">PowerPoint</span></span>

- <span data-ttu-id="a8166-1114">已修正使用 PowerPoint 筆跡動畫時，無法完整轉譯或跳過的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1114">Fixed an issue where Ink may not render completely or get skipped when used in a PowerPoint ink animations.</span></span>

- <span data-ttu-id="a8166-1115">已修正關閉檔案之後，如果有任何事件處理常式正在執行，PowerPoint 就不會立即將它從 [簡報] 集合中移除的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1115">Fixed an issue where After closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="a8166-1116">因此，物件模型報告的開啟中簡報數目會不正確，且會防止關閉 PowerPoint。</span><span class="sxs-lookup"><span data-stu-id="a8166-1116">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>


- <span data-ttu-id="a8166-1117">修正具有深色螢光筆色彩的白色文字，在灰階中會以黑色列印的螢光筆問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1117">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>


### <a name="project"></a><span data-ttu-id="a8166-1118">Project</span><span class="sxs-lookup"><span data-stu-id="a8166-1118">Project</span></span>

- <span data-ttu-id="a8166-1119">已修正以下問題：固定工期類型的 100% 工作可能會誤將其完成百分比計算為小於 100% 完成。</span><span class="sxs-lookup"><span data-stu-id="a8166-1119">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>


### <a name="word"></a><span data-ttu-id="a8166-1120">Word</span><span class="sxs-lookup"><span data-stu-id="a8166-1120">Word</span></span>

- <span data-ttu-id="a8166-1121">更新和瀏覽目錄時，有時可能會在文件上顯示灰色區域的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1121">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>


- <span data-ttu-id="a8166-1122">修正在已撰寫註解但未張貼，且使用者嘗試儲存檔案的情況下，使用 [瀏覽] 來儲存檔案沒有作用的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1122">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>


- <span data-ttu-id="a8166-1123">已修正在註解卡片之間來回切換時，有時會顯示一開始選取的註解，並將某選取範圍醒目提示的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1123">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>


- <span data-ttu-id="a8166-1124">已修正在編輯備註之後將文字設為斜體然後再張貼，斜體格式設定遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1124">Fixed an issue where italics formatting is lost after editing a comment, italicizing the text and then posting it.</span></span>


- <span data-ttu-id="a8166-1125">已修正在具有「反轉」頁面色彩的閱讀模式中，備註提示未顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1125">Fixed an issue where comment hint was not visible in read mode with Inverse page color.</span></span>


- <span data-ttu-id="a8166-1126">已修正共同撰寫文件時，可能不會保留根註解的草稿版本的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1126">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>


- <span data-ttu-id="a8166-1127">將 SlideTrack 啟用且 [註解] 窗格關閉時，Ctrl+Alt+M 可能無法開啟 [註解] 窗格的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1127">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>


- <span data-ttu-id="a8166-1128">修正在表格中新增 @提及時可能發生錯誤訊息：「文件中的表格已經毀損」的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1128">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>


- <span data-ttu-id="a8166-1129">修正備註內容功能表中的備註命令 (編輯備註、回覆備註、刪除備註、解決備註) 未顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1129">Fixed an issue where comment commands (Edit comment, Reply to comment, Delete comment, Resolve comment) in the comments context menu were not being displayed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="a8166-1130">Office 套件</span><span class="sxs-lookup"><span data-stu-id="a8166-1130">Office Suite</span></span>

- <span data-ttu-id="a8166-1131">解決可能導致挪威耐諾斯克 (nn-no) 校訂工具套件安裝不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1131">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>


- <span data-ttu-id="a8166-1132">此變更解決使用 Intel Integrated GPU 的圖形配接卡報告問題。</span><span class="sxs-lookup"><span data-stu-id="a8166-1132">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

