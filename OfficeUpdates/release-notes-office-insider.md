---
title: Office 測試人員的版本資訊
ms.author: andrewmo
author: v-almuzz
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為「測試人員 - 快」對象提供關鍵新功能、修正或已知問題的最新清單
ms.openlocfilehash: 38f26f551be55a7817a993108f598c6a6a9ecdb5
ms.sourcegitcommit: fdc89a96b2ab35af2f08654ef28117dec7657443
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/24/2020
ms.locfileid: "43804904"
---
# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="c493b-103">Office 測試人員的版本資訊</span><span class="sxs-lookup"><span data-stu-id="c493b-103">Release Notes for Office Insiders</span></span>

<span data-ttu-id="c493b-104">本文包含 Windows 電腦版 Word、Excel、PowerPoint、Outlook、Access 和 Project 測試人員組建的版本資訊。</span><span class="sxs-lookup"><span data-stu-id="c493b-104">This article contains release notes for Insider builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="c493b-105">我們每週都會強調有趣的新功能、重要修正，以及我們想讓您知道的重大問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-105">Every week, we'll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="c493b-106">請注意，我們在一段時間內會經常推出新功能 (某些時候還有修正) 給測試人員。</span><span class="sxs-lookup"><span data-stu-id="c493b-106">Note that we often roll out features (and sometimes even fixes) to Insiders over a period of time.</span></span> <span data-ttu-id="c493b-107">這樣可讓我們確保功能都運作順利，然後才推出給更廣泛的對象。</span><span class="sxs-lookup"><span data-stu-id="c493b-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="c493b-108">因此，如果您沒有在以下描述的內容中看到某些項目，請不用擔心，您最終還是會看到它。</span><span class="sxs-lookup"><span data-stu-id="c493b-108">So, if you don't see something described below, don't worry you'll get it eventually.</span></span>  

> [!NOTE]
> - <span data-ttu-id="c493b-109">版本資訊會每週發佈，可能是多個組建的編譯。</span><span class="sxs-lookup"><span data-stu-id="c493b-109">Release notes are posted weekly and may be a compilation of multiple builds.</span></span>
> - <span data-ttu-id="c493b-110">版本資訊發佈日期可能與實際組建發行日期不相符。</span><span class="sxs-lookup"><span data-stu-id="c493b-110">The release notes publication date may not match the actual build release date.</span></span>

[//]: # (DO NOT REMOVE)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-april-24"></a><span data-ttu-id="c493b-113">版本 2005：4 月 24 日</span><span class="sxs-lookup"><span data-stu-id="c493b-113">Version 2005: April 24</span></span>
<span data-ttu-id="c493b-114">版本 2005 (組建 12816.20006)\*\*</span><span class="sxs-lookup"><span data-stu-id="c493b-114">*Version 2005 (Build 12816.20006)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="c493b-118">解決的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-118">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c493b-119">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-119">Excel</span></span>
- <span data-ttu-id="c493b-120">這項變更修正了即使 LINEST 函式傳回正確的值，圖表趨勢線的 R 平方值 (在強制 y 截距的情況下) 仍然不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-120">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>
- <span data-ttu-id="c493b-121">此變更修正了自訂圖表趨勢線格式不一定會儲存的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-121">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-122">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-122">Outlook</span></span>
- <span data-ttu-id="c493b-123">修正了 Office 功能區中群組行事曆分類按鈕已停用的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-123">Fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>
- <span data-ttu-id="c493b-124">修正了企業客戶沒有執行或無法使用群組資料夾的問題，該問題會導致 Outlook 顯示「沒有回應」的訊息。</span><span class="sxs-lookup"><span data-stu-id="c493b-124">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-125">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-125">PowerPoint</span></span>
- <span data-ttu-id="c493b-126">修正了將滑鼠游標移到星號 (\*) 符號，但不會顯示上一次更新文件的日期和使用者姓名。</span><span class="sxs-lookup"><span data-stu-id="c493b-126">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="word"></a><span data-ttu-id="c493b-127">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-127">Word</span></span>
- <span data-ttu-id="c493b-128">啟用「顯示書簽」選項卻不會顯示書簽。</span><span class="sxs-lookup"><span data-stu-id="c493b-128">Enabling the option "Show bookmarks" would not display bookmarks.</span></span> <span data-ttu-id="c493b-129">已修正這個問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-129">This has been fixed.</span></span>
- <span data-ttu-id="c493b-130">此變更修正了下列問題：如果已啟用 [顯示功能變數代碼，而非其值] 選項，則含有超連結的文字可能不會顯示。</span><span class="sxs-lookup"><span data-stu-id="c493b-130">This change fixes an issue where text with hyperlinks may not display if the option "Show field codes instead of their values" was enabled.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-april-17"></a><span data-ttu-id="c493b-132">版本 2005：4 月 17 日</span><span class="sxs-lookup"><span data-stu-id="c493b-132">Version 2005: April 17</span></span>
<span data-ttu-id="c493b-133">*版本 2005 (組建 12810.20002)*</span><span class="sxs-lookup"><span data-stu-id="c493b-133">*Version 2005 (Build 12810.20002)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="c493b-135">解決的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-135">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c493b-136">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-136">Excel</span></span>
- <span data-ttu-id="c493b-137">已增加搭配圖表使用的 [自訂誤差線] 對話方塊上儲存格參照 [編輯] 控制項的大小。</span><span class="sxs-lookup"><span data-stu-id="c493b-137">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>
- <span data-ttu-id="c493b-138">在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。</span><span class="sxs-lookup"><span data-stu-id="c493b-138">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>
- <span data-ttu-id="c493b-139">修正列印時表單控制項的核取方塊縮放問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-139">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>
- <span data-ttu-id="c493b-140">在某些情況下，Application.Evaluate (VBA) 無法在使用者定義的函數中運作。</span><span class="sxs-lookup"><span data-stu-id="c493b-140">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>
- <span data-ttu-id="c493b-141">此變更會修正設定格式化的條件 (CF) 資訊無法正確儲存到 XLSB 檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-141">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="c493b-142">OneNote</span><span class="sxs-lookup"><span data-stu-id="c493b-142">OneNote</span></span>
- <span data-ttu-id="c493b-143">修正將分行符號儲存為垂直 Tab 的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-143">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-144">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-144">Outlook</span></span>
- <span data-ttu-id="c493b-145">解決會導致使用者無法將個人連絡人群組新增為會議出席者的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-145">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>
- <span data-ttu-id="c493b-146">解決會導致還有 2 個月時間的會議，無法在排程小幫手中顯示會議主題的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-146">Addresses an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>
- <span data-ttu-id="c493b-147">解決會導致使用者在轉寄大型 HTML 郵件時看到郵件內文截斷的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-147">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>
- <span data-ttu-id="c493b-148">新增透過群組原則強制執行 S/MIME 預設登入設定的功能。</span><span class="sxs-lookup"><span data-stu-id="c493b-148">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>
- <span data-ttu-id="c493b-149">解決會導致為使用者主要信箱以外的信箱所建立的刪除規則變得無效的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-149">Addresses an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>
- <span data-ttu-id="c493b-150">解決在轉寄加密郵件時導致捨棄附件的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-150">Addresses an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

### <a name="project"></a><span data-ttu-id="c493b-151">Project</span><span class="sxs-lookup"><span data-stu-id="c493b-151">Project</span></span>
- <span data-ttu-id="c493b-152">在表單檢視中編輯前置/後續任務資料時，會觸發額外的 ProjectBeforeTaskChange 事件。</span><span class="sxs-lookup"><span data-stu-id="c493b-152">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>
- <span data-ttu-id="c493b-153">修正變更連結至 SharePoint 工作清單之專案的面板狀態欄位時，Project 可能當機的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-153">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>
- <span data-ttu-id="c493b-154">修正儲存使用舊版 Project 建立的專案時，Project 可能當機的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-154">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-april-10"></a><span data-ttu-id="c493b-156">版本 2004：4 月 10 日</span><span class="sxs-lookup"><span data-stu-id="c493b-156">Version 2004: April 10</span></span>
<span data-ttu-id="c493b-157">*版本 2004 (組建 12730.20024)*</span><span class="sxs-lookup"><span data-stu-id="c493b-157">*Version 2004 (Build 12730.20024)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="c493b-159">功能更新</span><span class="sxs-lookup"><span data-stu-id="c493b-159">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="c493b-160">Access</span><span class="sxs-lookup"><span data-stu-id="c493b-160">Access</span></span>

- <span data-ttu-id="c493b-161">**略過 [顯示資料表] 對話方塊，直接移至工作窗格，以及將資料表新增至關係和查詢的程序簡化：** 只要按一下四個索引標籤、將名稱多重選取、依文字搜尋，並從在您工作時維持開啟的工作窗格拖曳，即可新增資料表和查詢。</span><span class="sxs-lookup"><span data-stu-id="c493b-161">**Bypass the Show Table dialog box, go directly to a task pane, and streamline adding tables to relationships and queries.:** Add tables and queries by clicking four tabs, multi-selecting names, searching by text, and dragging from a task pane that stays open while you work.</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-162">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-162">Excel</span></span>

- <span data-ttu-id="c493b-163">**M365 進階版內容選擇器：** 讓您的文件栩栩如生！</span><span class="sxs-lookup"><span data-stu-id="c493b-163">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="c493b-164">探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="c493b-164">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-165">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-165">Outlook</span></span>

- <span data-ttu-id="c493b-166">**M365 進階版內容選擇器：** 讓您的文件栩栩如生！</span><span class="sxs-lookup"><span data-stu-id="c493b-166">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="c493b-167">探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="c493b-167">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="c493b-168">**將圖片作為電子郵件的一部分傳送時，讓圖片保持高畫質：** 一個新 Outlook 設定，可讓您在隨著電子郵件內容傳送圖片時限制圖片壓縮</span><span class="sxs-lookup"><span data-stu-id="c493b-168">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-169">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-169">PowerPoint</span></span>

- <span data-ttu-id="c493b-170">**M365 進階版內容選擇器：** 讓您的文件栩栩如生！</span><span class="sxs-lookup"><span data-stu-id="c493b-170">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="c493b-171">探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="c493b-171">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="c493b-172">**在簡報時同步處理變更：** 即使簡報處於投影片放映模式，仍可即時同步處理所做的變更。</span><span class="sxs-lookup"><span data-stu-id="c493b-172">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="c493b-173">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-173">Word</span></span>

- <span data-ttu-id="c493b-174">**M365 進階版內容選擇器：** 讓您的文件栩栩如生！</span><span class="sxs-lookup"><span data-stu-id="c493b-174">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="c493b-175">探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="c493b-175">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="c493b-176">**標註私人複本：** 製作共用文件的私人複本，以建立只有您本人能夠看到的手寫筆記。</span><span class="sxs-lookup"><span data-stu-id="c493b-176">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="c493b-177">若要開始使用，請移至 [檢視] > [建立私人複本]。</span><span class="sxs-lookup"><span data-stu-id="c493b-177">Go to View > Create a Private Copy to get started.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="c493b-180">解決的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-180">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="c493b-181">Access</span><span class="sxs-lookup"><span data-stu-id="c493b-181">Access</span></span>

- <span data-ttu-id="c493b-182">修正工作窗格中表格的重新調整及重新整理問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-182">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-183">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-183">Excel</span></span>

- <span data-ttu-id="c493b-184">修正在工作表上選取儲存格範圍會導致只選取單一儲存格的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-184">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="c493b-185">修正在為含有 X 軸範圍的圖表縮減大小時，可能會導致 Excel 停止回應的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-185">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="c493b-186">修正插入使用者定義的圖表範本來作為預設值會導致其儲存為直條圖的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-186">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="c493b-187">修正當基礎資料儲存格沒有標題時，圖表上的資料標籤會以空白顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-187">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="c493b-188">修正已啟用 R1C1 儲存格參照且正在共同撰寫/共用的 Excel 工作表，在將游標移到 [使用者目前狀態] 圖示上方時不會以 R1C1 模式顯示作用中儲存格的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-188">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-189">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-189">Outlook</span></span>

- <span data-ttu-id="c493b-190">解決會導致類別有時候會從電子郵件訊息中消失的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-190">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="c493b-191">解決會導致代理人在不同機器上所看到的共用信箱有不同資料夾階層的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-191">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="c493b-192">解決在嘗試檢視組織表單的屬性時，會導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-192">Addresses an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="c493b-193">解決在變更機器上的時區時，會導致某些提醒無法觸發的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-193">Addresses an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-194">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-194">PowerPoint</span></span>

- <span data-ttu-id="c493b-195">此變更修正了在 PowerPoint 或 Word 中呈現內嵌為 OLE 物件的舊版 Excel 圖表時可能不會永遠顯示圖表標題的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-195">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="c493b-196">我們已修正將文字從 Excel 複製到 PowerPoint 時可能會導致其格式設定發生變更的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-196">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="c493b-197">此變更修正了使用 [全字拼寫須相符] 來尋找特殊字元時，不一定能正常運作的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-197">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="c493b-198">Project</span><span class="sxs-lookup"><span data-stu-id="c493b-198">Project</span></span>

- <span data-ttu-id="c493b-199">修正了當開啟保護實際工作的設定時，使用者無法輸入分時期基準工時的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-199">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="c493b-200">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-200">Word</span></span>

- <span data-ttu-id="c493b-201">此變更修正了將游標暫留在提示上不會醒目提示其卡片的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-201">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="c493b-202">此變更修正了使用套索選取工具時，群組圖形中的文字會暫時消失的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-202">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="c493b-203">此變更修正了在 PowerPoint 或 Word 中呈現內嵌為 OLE 物件的舊版 Excel 圖表時可能不會永遠顯示圖表標題的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-203">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="c493b-204">此變更修正了在雙頁檢視中建立註解時，註解錨點不一定會顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-204">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="c493b-205">修正如果段落的樣式是連結至清單的樣式上階，則該清單的編號可能會遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-205">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-march-27"></a><span data-ttu-id="c493b-207">版本 2004：3 月 27 日</span><span class="sxs-lookup"><span data-stu-id="c493b-207">Version 2004: March 27</span></span>
<span data-ttu-id="c493b-208">*版本 2004 (組建 12718.20010)*</span><span class="sxs-lookup"><span data-stu-id="c493b-208">*Version 2004 (Build 12718.20010)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="c493b-210">功能更新</span><span class="sxs-lookup"><span data-stu-id="c493b-210">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="c493b-211">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-211">Outlook</span></span>

- <span data-ttu-id="c493b-212">**在撰寫郵件時有新的選項可停用 @ 提及建議：** 您是否覺得 @ 提及的選擇器很煩人，一點都不好用？</span><span class="sxs-lookup"><span data-stu-id="c493b-212">**New option to disable @ mention suggestions when composing mail:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="c493b-213">現在您可以視需要將其關閉了。</span><span class="sxs-lookup"><span data-stu-id="c493b-213">Now you can turn it off if you prefer.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="c493b-216">解決的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-216">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="c493b-217">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-217">Outlook</span></span>
- <span data-ttu-id="c493b-218">解決了會讓 [附件工具] 中的 [儲存至雲端] 按鈕不見的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-218">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>
- <span data-ttu-id="c493b-219">解決了以下問題：當使用者從檢查程式視窗回覆受到數位版權管理的郵件，卻沒有所回覆郵件的擁有者權限時，使用者會無法新增簽名。</span><span class="sxs-lookup"><span data-stu-id="c493b-219">Addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>
- <span data-ttu-id="c493b-220">解決了以下問題：使用者無法從網頁位置將其他附件新增到先前建立的會議。</span><span class="sxs-lookup"><span data-stu-id="c493b-220">Addresses an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-221">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-221">PowerPoint</span></span>
- <span data-ttu-id="c493b-222">此變更修正了會導致包含 emojis 的 PowerPoint 檔案在儲存時發生失敗的錯誤。</span><span class="sxs-lookup"><span data-stu-id="c493b-222">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

### <a name="project"></a><span data-ttu-id="c493b-223">Project</span><span class="sxs-lookup"><span data-stu-id="c493b-223">Project</span></span>
- <span data-ttu-id="c493b-224">修正了以下問題：如果執行 ' CustomFieldValueListGetItem' 且自訂欄位的查閱資料表不存在，系統會建立一個不應建立的空白查閱資料表。</span><span class="sxs-lookup"><span data-stu-id="c493b-224">Fixed an issue where if 'CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

### <a name="word"></a><span data-ttu-id="c493b-225">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-225">Word</span></span>
- <span data-ttu-id="c493b-226">此變更修正了以下問題：從 [檢視] 功能表選取多個頁面時，其中的 [註解] 窗格會顯示為空白。</span><span class="sxs-lookup"><span data-stu-id="c493b-226">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-march-20"></a><span data-ttu-id="c493b-228">版本 2004：3 月 20 日</span><span class="sxs-lookup"><span data-stu-id="c493b-228">Version 2004: March 20</span></span>
<span data-ttu-id="c493b-229">*版本 2004 (組建 12711.20000)*</span><span class="sxs-lookup"><span data-stu-id="c493b-229">*Version 2004 (Build 12711.20000)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="c493b-231">功能更新</span><span class="sxs-lookup"><span data-stu-id="c493b-231">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="c493b-232">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-232">Outlook</span></span>

- <span data-ttu-id="c493b-233">**行事曆新版視覺效果：** 去年，我們提供了全新的郵件體驗，而今年將為您帶來嶄新的行事曆！</span><span class="sxs-lookup"><span data-stu-id="c493b-233">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar's turn to get a facelift!</span></span> <span data-ttu-id="c493b-234">有幾項更新是新穎卻令人孰悉的，您是經驗豐富的 Outlook 使用者，可以立即使用並提高生產力。</span><span class="sxs-lookup"><span data-stu-id="c493b-234">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

- <span data-ttu-id="c493b-235">**協助保護群組中的資料：** 建立群組時所選擇的「敏感度」標籤會套用到群組電子郵件、文件及小組網站</span><span class="sxs-lookup"><span data-stu-id="c493b-235">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-236">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-236">PowerPoint</span></span>

- <span data-ttu-id="c493b-237">**在投影片放映期間更新投影片：** 在簡報期間，更新由其他作者變更的投影片。</span><span class="sxs-lookup"><span data-stu-id="c493b-237">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="c493b-240">解決的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-240">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c493b-241">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-241">Excel</span></span>

- <span data-ttu-id="c493b-242">此變更解決了處理格式錯誤或無效通訊協定資訊影像時所導致的延遲問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-242">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-243">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-243">Outlook</span></span>

- <span data-ttu-id="c493b-244">此變更解決了處理格式錯誤或無效通訊協定資訊影像時所導致的延遲問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-244">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="c493b-245">此變更修正了電子郵件草稿最新變更未更新的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-245">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="c493b-246">已修正在檔案上按一下滑鼠右鍵並使用「傳送到」功能無法運作的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-246">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="c493b-247">已修正如果使用者有自訂的 [通訊錄] 搜尋路徑，則 Outlook 的名稱解析範圍會限制為自訂路徑，而不是包括全域通訊清單 (GAL) 的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-247">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="c493b-248">已修正在一組傳回的搜尋結果中，依類別結果排序不會顯示類別色彩的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-248">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

### <a name="project"></a><span data-ttu-id="c493b-249">Project</span><span class="sxs-lookup"><span data-stu-id="c493b-249">Project</span></span>

- <span data-ttu-id="c493b-250">已修正當使用者按一下 [排程群組] 內 [工作] 功能區中的 [停用] 按鈕時，不會觸發 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) 事件的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-250">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the "Inactivate" button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="c493b-251">如果您在 [表單類型] 檢視中設定前置任務或後置任務詳細資訊，則 ProjectBeforeTaskChange Visual Basic Applications (VBA) 事件不會一律擷取變更。</span><span class="sxs-lookup"><span data-stu-id="c493b-251">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="c493b-252">例如，如果刪除了某個相依性，並在表單上按一下 [確定]，則不會觸發該事件。</span><span class="sxs-lookup"><span data-stu-id="c493b-252">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="c493b-253">已修正此問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-253">This behavior has been fixed.</span></span>

- <span data-ttu-id="c493b-254">已修正在進行變更 (例如日期變更) 之後，實際工作成本 (ACWP) 的最新值不會顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-254">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="c493b-255">已修正使用「最近使用」(MRU) 功能表開啟專案時，會使用 [讀取/寫入] 存取權開啟專案的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-255">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="c493b-256">這項變更修正了如果您建立包含開始日期和時間 (但無工期) 的手動工作，則時間表上的時間顯示不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-256">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="c493b-257">已修正使用回曆列印時間表時，會導致列印檢視中略過或重複一個月的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-257">Fixed an issue where printing a timeline using Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="c493b-258">這項變更解決了在團隊規劃中使用 GDI 物件時，可能導致 GDI 物件分配過多並產生記憶體不足的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-258">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

### <a name="word"></a><span data-ttu-id="c493b-259">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-259">Word</span></span>

- <span data-ttu-id="c493b-260">已修正張貼留言功能停用的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-260">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="c493b-261">此變更解決了處理格式錯誤或無效通訊協定資訊影像時所導致的延遲問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-261">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="c493b-262">這項變更解決了帳戶管理員不會分派訊息而導致協力廠商應用程式懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-262">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="c493b-263">這項變更修正了目錄會使用文件中未包含的標題樣式進行更新的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-263">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="c493b-264">已修正在寄送文件時，儲存在 Word 文件中的數位簽章會被刪除的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-264">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-march-13"></a><span data-ttu-id="c493b-266">版本 2004：3 月 13 日</span><span class="sxs-lookup"><span data-stu-id="c493b-266">Version 2004: March 13</span></span>
<span data-ttu-id="c493b-267">*版本 2004 (組建 12703.20010)*</span><span class="sxs-lookup"><span data-stu-id="c493b-267">*Version 2004 (Build 12703.20010)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="c493b-269">功能更新</span><span class="sxs-lookup"><span data-stu-id="c493b-269">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-270">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-270">Excel</span></span>
- <span data-ttu-id="c493b-271">**敏感度標籤**：您現在可以套用組織設定、用來提示您輸入自訂權限的敏感度標籤。</span><span class="sxs-lookup"><span data-stu-id="c493b-271">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="c493b-272">深入了解</span><span class="sxs-lookup"><span data-stu-id="c493b-272">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a><span data-ttu-id="c493b-273">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-273">PowerPoint</span></span>
- <span data-ttu-id="c493b-274">**敏感度標籤**：您現在可以套用組織設定、用來提示您輸入自訂權限的敏感度標籤。</span><span class="sxs-lookup"><span data-stu-id="c493b-274">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="c493b-275">深入了解</span><span class="sxs-lookup"><span data-stu-id="c493b-275">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a><span data-ttu-id="c493b-276">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-276">Word</span></span>
- <span data-ttu-id="c493b-277">**敏感度標籤**：您現在可以套用組織設定、用來提示您輸入自訂權限的敏感度標籤。</span><span class="sxs-lookup"><span data-stu-id="c493b-277">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="c493b-278">深入了解</span><span class="sxs-lookup"><span data-stu-id="c493b-278">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="c493b-281">解決的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-281">Resolved issues</span></span>

### <a name="access"></a><span data-ttu-id="c493b-282">Access</span><span class="sxs-lookup"><span data-stu-id="c493b-282">Access</span></span>
- <span data-ttu-id="c493b-283">修正國際版 Access 在使用者介面中顯示英文字串的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-283">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-284">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-284">Excel</span></span>
- <span data-ttu-id="c493b-285">修正使用者在以程式設計方式編輯大量儲存格範圍時可能遇到的效能問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-285">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>
- <span data-ttu-id="c493b-286">修正以日文環境開啟 CSV 檔案時發生的效能問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-286">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-287">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-287">Outlook</span></span>
- <span data-ttu-id="c493b-288">解決將附件新增至郵件或從郵件拖放 (與透過功能表相對) 來儲存附件時，導致檔案的「上次修改」日期更新的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-288">Addresses an issue that caused the "Last Modified"; date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>
- <span data-ttu-id="c493b-289">解決會導致在展開的尋找窗格中按一下 Enter 時無法開始搜尋，而是會要求使用者按一下 [搜尋] 按鈕的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-289">Addresses an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>
- <span data-ttu-id="c493b-290">修正將 [如果有，顯示使用者的照片] 選項停用時，搜尋不會顯示有關使用者的任何資訊的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-290">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>

### <a name="project"></a><span data-ttu-id="c493b-291">Project</span><span class="sxs-lookup"><span data-stu-id="c493b-291">Project</span></span>
- <span data-ttu-id="c493b-292">修正無法正確計算摘要工作日期的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-292">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>
- <span data-ttu-id="c493b-293">修正不先執行 OpenUndoTransaction 方法就不能觸發 OnUndoOrRedo 事件的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-293">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="c493b-294">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-294">Word</span></span>
- <span data-ttu-id="c493b-295">修正輸入或編輯備註然後使用 Ctrl+A 時，會導致選取畫布中的文字，而不只是選取備註卡片內文字的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-295">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>
- <span data-ttu-id="c493b-296">我們已修正文件中的文字對齊，在使用 [快速列印] 進行列印之後嘗試進行編輯時變得混亂的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-296">We fixed an issue in which the alignment of words in a document gets scrambled when tried to edit after printing using Quick Print.</span></span>
- <span data-ttu-id="c493b-297">我們已修正將兩份文件合併成一份文件時的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-297">We fixed an issue when merging two documents into one document.</span></span>
- <span data-ttu-id="c493b-298">修正標示的修訂若與方程式有關，在儲存檔案時可能會導致失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-298">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-march-06"></a><span data-ttu-id="c493b-300">版本 2003：3 月 6 日</span><span class="sxs-lookup"><span data-stu-id="c493b-300">Version 2003: March 06</span></span>
<span data-ttu-id="c493b-301">*版本 2003 (組建 12624.20086)*</span><span class="sxs-lookup"><span data-stu-id="c493b-301">*Version 2003 (Build 12624.20086)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="c493b-303">解決的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-303">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="c493b-304">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-304">Outlook</span></span>

- <span data-ttu-id="c493b-305">修正使用 Outlook Web Access 建立規則時不會保存到 Exchange 伺服器，並導致衝突的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-305">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>
- <span data-ttu-id="c493b-306">修正 Outlook 在深色模式中不會在 [寄件者:] 欄位中顯示下拉式清單的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-306">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>
- <span data-ttu-id="c493b-307">解決在其他應用程式中開啟某個檔案時，導致使用者無法透過檔案總管將該檔案附加至郵件訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-307">Addresses an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-308">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-308">PowerPoint</span></span>

- <span data-ttu-id="c493b-309">修正將滑鼠移至縮圖上時，建議的縮圖閃動的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-309">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="c493b-310">在某些情況下，這可能會導致 PowerPoint 當機。</span><span class="sxs-lookup"><span data-stu-id="c493b-310">In some cases this could cause PowerPoint to crash.</span></span>

### <a name="word"></a><span data-ttu-id="c493b-311">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-311">Word</span></span>

- <span data-ttu-id="c493b-312">修正受保護無法編輯之文件的比較功能問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-312">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c493b-313">Office 套件</span><span class="sxs-lookup"><span data-stu-id="c493b-313">Office Suite</span></span>

- <span data-ttu-id="c493b-314">修正 Word/Excel/PowerPoint 中的使用者主體名稱 (UPN) 不再區分大小寫，導致在 SharePoint 上使用檔案時較少發生失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-314">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="c493b-315">修正 [檔案]\[選項] 對話方塊上的 [確定] 按鈕顯示為灰色停用狀態，但功能並未受影響的外觀問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-315">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog was being displayed as grayed out but functionality was not impacted.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

## <a name="version-2003-february-28"></a><span data-ttu-id="c493b-318">版本 2003：2 月 28 日</span><span class="sxs-lookup"><span data-stu-id="c493b-318">Version 2003: February 28</span></span>
<span data-ttu-id="c493b-319">*版本 2003 (組建 12619.20002)*</span><span class="sxs-lookup"><span data-stu-id="c493b-319">*Version 2003 (Build 12619.20002)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="c493b-321">功能更新</span><span class="sxs-lookup"><span data-stu-id="c493b-321">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="c493b-322">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-322">Outlook</span></span>

- <span data-ttu-id="c493b-323">**IT 系統管理員的事件通知：** Microsoft 365 租用戶全域系統管理員和 Office 應用程式系統會在 Windows 版 Outlook 的新右側面板中收到影響其使用者的 Outlook 和 O365 Exchange 事件通知。</span><span class="sxs-lookup"><span data-stu-id="c493b-323">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-324">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-324">PowerPoint</span></span>

- <span data-ttu-id="c493b-325">**改善筆跡轉換圖形圖表製作體驗：** 繪製更完善的圖表，並將它轉換成您可處理的 Office 物件。[深入了解](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span><span class="sxs-lookup"><span data-stu-id="c493b-325">**Improved ink to shape diagramming experience:** Draw better diagrams and have it convert so office object you can manipulate [Learn more](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="c493b-328">解決的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-328">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c493b-329">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-329">Excel</span></span>

- <span data-ttu-id="c493b-330">已修正交叉分析篩選器中的文字在預覽列印中無法正確縮放的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-330">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-331">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-331">Outlook</span></span>

- <span data-ttu-id="c493b-332">解決將附件新增至郵件或從郵件拖放 (與透過功能表相對) 來儲存附件時，導致檔案的「上次修改」日期更新的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-332">Addresses an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

### <a name="word"></a><span data-ttu-id="c493b-333">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-333">Word</span></span>

- <span data-ttu-id="c493b-334">修正按 Tab 鍵導覽註解卡片時，註解編輯方塊上的焦點無法顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-334">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="c493b-335">在方程式中插入控制項 (例如文字內容控制項)，然後儲存再開啟檔案，便會導致內容無法讀取的錯誤。</span><span class="sxs-lookup"><span data-stu-id="c493b-335">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="c493b-336">修正將先前使用密碼保護的檔案儲存到雲端儲存空間無法運作的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-336">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c493b-337">Office 套件</span><span class="sxs-lookup"><span data-stu-id="c493b-337">Office Suite</span></span>

- <span data-ttu-id="c493b-338">修正在 Word/Excel/PowerPoint 中開啟來自相同 SharePoint 文件庫的多個文件時，僅掃描開啟的第一個文件是否符合原則的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-338">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-february-21"></a><span data-ttu-id="c493b-340">版本 2003：2 月 21 日</span><span class="sxs-lookup"><span data-stu-id="c493b-340">Version 2003: February 21</span></span>
<span data-ttu-id="c493b-341">*版本 2003 (組建 12615.20000)*</span><span class="sxs-lookup"><span data-stu-id="c493b-341">*Version 2003 (Build 12615.20000)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="c493b-343">功能更新</span><span class="sxs-lookup"><span data-stu-id="c493b-343">Feature updates</span></span>
### <a name="office-suite"></a><span data-ttu-id="c493b-344">Office 套件</span><span class="sxs-lookup"><span data-stu-id="c493b-344">Office Suite</span></span>

- <span data-ttu-id="c493b-345">**挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。</span><span class="sxs-lookup"><span data-stu-id="c493b-345">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="c493b-348">解決的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-348">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-349">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-349">Excel</span></span>
- <span data-ttu-id="c493b-350">已修正使用者在重新命名樞紐分析表度量值時可能遇到的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-350">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>
- <span data-ttu-id="c493b-351">已修正使用者在使用 VBA 巨集清除範圍內容時可能遇到的效能問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-351">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>
- <span data-ttu-id="c493b-352">已修正當使用者執行與功能區互動的巨集時，導致 UI 快閃的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-352">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>
- <span data-ttu-id="c493b-353">已修正當檔案中的第一個字為 TABLE 時，CSV 檔案載入錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-353">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>
- <span data-ttu-id="c493b-354">已修正當您在兩個具有不同縮放比例的活頁簿之間切換時，使用者可能遇到的當機問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-354">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-355">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-355">Outlook</span></span>
- <span data-ttu-id="c493b-356">已解決當持續整夜執行 Outlook 時，導致使用者無法開啟公用資料夾訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-356">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>
- <span data-ttu-id="c493b-357">已修正在新增 Gmail 帳戶的驗證工作流程中，[權限] 頁面上的 [允許] 和 [拒絕] 按鈕停用的爭用情況。</span><span class="sxs-lookup"><span data-stu-id="c493b-357">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>
- <span data-ttu-id="c493b-358">已解決即使已關閉記錄，在某些情況下仍導致 Outlook 異常產生記錄輸出的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-358">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

### <a name="word"></a><span data-ttu-id="c493b-359">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-359">Word</span></span>
- <span data-ttu-id="c493b-360">已修正當滑鼠指標暫留在註解卡片上方時，未醒目提示註解卡片的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-360">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>
- <span data-ttu-id="c493b-361">在使用中的文件共同撰寫工作階段中，直接在註解卡片中新增影像可能會導致新增標籤。</span><span class="sxs-lookup"><span data-stu-id="c493b-361">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="c493b-362">我們已修正此問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-362">This issue has been fixed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c493b-363">Office 套件</span><span class="sxs-lookup"><span data-stu-id="c493b-363">Office Suite</span></span>
- <span data-ttu-id="c493b-364">當您將 Multichoice/Lookup/Managed-metadata 屬性與 Word/Excel/PowerPoint 文件一起使用並儲存至 SharePoint 文件庫時，這些屬性之前限制為 255 個字元。</span><span class="sxs-lookup"><span data-stu-id="c493b-364">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="c493b-365">當這些屬性超過 255 個字元時，這類文件就無法儲存。</span><span class="sxs-lookup"><span data-stu-id="c493b-365">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="c493b-366">在此變更中，此限制已增加到 2048 個字元。</span><span class="sxs-lookup"><span data-stu-id="c493b-366">With this change, this limit has been increased to 2048 characters.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-february-14"></a><span data-ttu-id="c493b-368">版本 2003：2 月 14 日</span><span class="sxs-lookup"><span data-stu-id="c493b-368">Version 2003: February 14</span></span>
<span data-ttu-id="c493b-369">*版本 2003 (組建 12607.20000)*</span><span class="sxs-lookup"><span data-stu-id="c493b-369">*Version 2003 (Build 12607.20000)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="c493b-371">功能更新</span><span class="sxs-lookup"><span data-stu-id="c493b-371">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="c493b-372">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-372">Outlook</span></span>

- <span data-ttu-id="c493b-373">**受限 WiFi 網路的新體驗：** 是否曾經加入需要登入網頁的 WiFi 網路呢？</span><span class="sxs-lookup"><span data-stu-id="c493b-373">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="c493b-374">Outlook 現在會偵測這項要求並協助您取得連結。</span><span class="sxs-lookup"><span data-stu-id="c493b-374">Outlook now detects this and helps you get connected.</span></span>

### <a name="word"></a><span data-ttu-id="c493b-375">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-375">Word</span></span>

- <span data-ttu-id="c493b-376">**在繪圖工具箱中找到筆跡編輯器：** 選取 [繪圖]，然後選擇 [筆跡編輯器] 手寫筆以使用手指或數位筆編輯文件。</span><span class="sxs-lookup"><span data-stu-id="c493b-376">**Find Ink Editor in your drawing toolbox:** Select Draw and then choose the Ink Editor pen to edit your document with your finger or a digital pen.</span></span> [<span data-ttu-id="c493b-377">深入了解</span><span class="sxs-lookup"><span data-stu-id="c493b-377">Learn more</span></span>](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

### <a name="office-suite"></a><span data-ttu-id="c493b-378">Office 套件</span><span class="sxs-lookup"><span data-stu-id="c493b-378">Office Suite</span></span>

- <span data-ttu-id="c493b-379">**更清楚的狀態列圖示：** 狀態列圖示現在更容易查看</span><span class="sxs-lookup"><span data-stu-id="c493b-379">**Clearer status bar icons:** Status bar icons are now easier to see</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="c493b-382">解決的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-382">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="c493b-383">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-383">Outlook</span></span>

- <span data-ttu-id="c493b-384">已解決導致使用者無法存取「空閒/忙碌選項」行事曆權限對話方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-384">Addressed an issue that caused users to lose access to the "Free Busy Options" calendar permissions dialog.</span></span>

- <span data-ttu-id="c493b-385">修正了開啟某些從不同時區傳送的週期性會議執行個體時，可能會導致出現警示：「很抱歉，無法開啟這此項目」的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-385">Fixed an issue that may result in the alert: "Sorry we're having trouble opening this item" when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="c493b-386">已解決從該郵件拖放附件後造成使用者無法重新開啟 .msg 檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-386">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="c493b-387">修正從 Outlook 上傳檔案附件到 OneDrive 後，造成包含括號之附件名稱的檔案名稱被變更。</span><span class="sxs-lookup"><span data-stu-id="c493b-387">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-388">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-388">PowerPoint</span></span>

- <span data-ttu-id="c493b-389">修正儲存包含 Excel 圖表的 PowerPoint 或 Word 文件會導致失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-389">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>

### <a name="word"></a><span data-ttu-id="c493b-390">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-390">Word</span></span>

- <span data-ttu-id="c493b-391">修正文件中的圖片在匯出成 PDF 後，會失去透明度的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-391">Fixed an issue where pictures in documents lose transparency when exported to PDF.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-february-07"></a><span data-ttu-id="c493b-393">版本 2002：2 月 7 日</span><span class="sxs-lookup"><span data-stu-id="c493b-393">Version 2002: February 07</span></span>
<span data-ttu-id="c493b-394">*版本 2002 (組建 12527.20040)*</span><span class="sxs-lookup"><span data-stu-id="c493b-394">*Version 2002 (Build 12527.20040)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="c493b-396">功能更新</span><span class="sxs-lookup"><span data-stu-id="c493b-396">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="c493b-397">Access</span><span class="sxs-lookup"><span data-stu-id="c493b-397">Access</span></span>

- <span data-ttu-id="c493b-398">**在查詢設計工具、SQL 檢視和關聯視窗中工作時更具生產力：** 在資料表上按一下滑鼠右鍵即可開啟、設計、調整大小及隱藏它。</span><span class="sxs-lookup"><span data-stu-id="c493b-398">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="c493b-399">在 SQL 檢視中搜尋及取代文字。</span><span class="sxs-lookup"><span data-stu-id="c493b-399">Search and replace text in SQL View.</span></span> <span data-ttu-id="c493b-400">在 [關聯圖] 視窗中選取多個資料表。</span><span class="sxs-lookup"><span data-stu-id="c493b-400">Select multiple tables in the Relationships window.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="c493b-403">解決的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-403">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="c493b-404">Access</span><span class="sxs-lookup"><span data-stu-id="c493b-404">Access</span></span>

- <span data-ttu-id="c493b-405">此更新會修正使用 ADODB 的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-405">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="c493b-406">VB 程式碼中的記錄器物件可能會不正確地報告錯誤。</span><span class="sxs-lookup"><span data-stu-id="c493b-406">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="c493b-407">此更新修正可能會導致 Microsoft Access 無法識別連結的 SQL Server 資料表中的識別資料行的問題，這可能會導致不正確地將資料列報告為已刪除。</span><span class="sxs-lookup"><span data-stu-id="c493b-407">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-408">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-408">Excel</span></span>

- <span data-ttu-id="c493b-409">修正使用「資料剖析」搭配動態陣列時，Excel 會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-409">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-410">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-410">Outlook</span></span>

- <span data-ttu-id="c493b-411">修正以月檢視在行事曆中捲動時，無法顯示之前的行事曆活動的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-411">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="c493b-412">解決在 Citrix 環境中檢視 30 個以上的行事曆時，導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-412">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-413">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-413">PowerPoint</span></span>

- <span data-ttu-id="c493b-414">修正關閉檔案之後，如果有任何事件處理常式正在執行，PowerPoint 就不會立即將它從 [簡報] 集合中移除的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-414">Fixed an issue where after closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="c493b-415">因此，物件模型報告的開啟中簡報數目會不正確，且會防止關閉 PowerPoint。</span><span class="sxs-lookup"><span data-stu-id="c493b-415">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>

- <span data-ttu-id="c493b-416">修正具有深色螢光筆色彩的白色文字，在灰階中會以黑色列印的螢光筆問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-416">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="c493b-417">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-417">Word</span></span>

- <span data-ttu-id="c493b-418">更新和瀏覽目錄時，有時可能會在文件上顯示灰色區域的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-418">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>

- <span data-ttu-id="c493b-419">修正共同撰寫文件時，可能不會保留根註解的草稿版本的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-419">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>

- <span data-ttu-id="c493b-420">已修正在註解卡片之間來回切換時，有時會顯示一開始選取的註解，並將某選取範圍醒目提示的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-420">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>

- <span data-ttu-id="c493b-421">修正在已撰寫註解但未張貼，且使用者嘗試儲存檔案的情況下，使用 [瀏覽] 來儲存檔案沒有作用的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-421">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>

- <span data-ttu-id="c493b-422">將 SlideTrack 啟用且 [註解] 窗格關閉時，Ctrl+Alt+M 可能無法開啟 [註解] 窗格的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-422">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>

- <span data-ttu-id="c493b-423">修正在表格中新增 @提及時可能發生錯誤訊息：「文件中的表格已經毀損」的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-423">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c493b-424">Office 套件</span><span class="sxs-lookup"><span data-stu-id="c493b-424">Office Suite</span></span>

- <span data-ttu-id="c493b-425">解決可能導致挪威耐諾斯克 (nn-no) 校訂工具套件安裝不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-425">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-january-31"></a><span data-ttu-id="c493b-427">版本 2002：1 月 31 日</span><span class="sxs-lookup"><span data-stu-id="c493b-427">Version 2002: January 31</span></span>
<span data-ttu-id="c493b-428">*版本 2002 (組建 12513.20010)*</span><span class="sxs-lookup"><span data-stu-id="c493b-428">*Version 2002 (Build 12513.20010)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="c493b-430">功能更新</span><span class="sxs-lookup"><span data-stu-id="c493b-430">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="c493b-431">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-431">Excel</span></span>

- <span data-ttu-id="c493b-432">**即時讀取與回覆：** 直接從電子郵件回覆註解和提及，而不需開啟活頁簿。</span><span class="sxs-lookup"><span data-stu-id="c493b-432">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="c493b-433">**查詢編輯器中的資料分析：** 取得欄位資料的概覽分析、識別錯誤和空白值，查看分佈長條圖等。</span><span class="sxs-lookup"><span data-stu-id="c493b-433">**Data Profiling in Query Editor:** Get-a-glance analysis of the data in your columns, identify error and empty values, see distribution histograms and more.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="c493b-436">解決的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-436">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="c493b-437">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-437">Outlook</span></span>

- <span data-ttu-id="c493b-438">修正根據保留原則到期的電子郵件會顯示兩個標籤的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-438">Fixed an issue where emails expiring based on a retention policy would display two labels.</span></span> <span data-ttu-id="c493b-439">其中一個顯示郵件將在一天內過期，另一個則顯示將在兩天內到期。</span><span class="sxs-lookup"><span data-stu-id="c493b-439">One showing that the mail will expire in one day and another displaying that it will expire in two days.</span></span>

### <a name="word"></a><span data-ttu-id="c493b-440">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-440">Word</span></span>

- <span data-ttu-id="c493b-441">修正在具有「反轉」頁面色彩的閱讀模式中，備註提示未顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-441">Fixed an issue where comment hint was not visible in read mode with &quot;Inverse&quot; page color.</span></span>

- <span data-ttu-id="c493b-442">修正在編輯備註之後將文字設為斜體然後再張貼，斜體格式設定遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-442">Fixed an issue where italics formatting is lost after editing a comment, italicizing the text and then posting it.</span></span>

- <span data-ttu-id="c493b-443">修正備註內容功能表中的備註命令 (編輯備註、回覆備註、刪除備註、解決備註) 未顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-443">Fixed an issue where comment commands (Edit comment, Reply to comment, Delete comment, Resolve comment) in the comments context menu were not being displayed.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-january-17"></a><span data-ttu-id="c493b-445">版本 2002：1 月 17 日</span><span class="sxs-lookup"><span data-stu-id="c493b-445">Version 2002: January 17</span></span>
<span data-ttu-id="c493b-446">*版本 2002 (組建 12508.20000)*</span><span class="sxs-lookup"><span data-stu-id="c493b-446">*Version 2002 (Build 12508.20000)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="c493b-448">功能更新</span><span class="sxs-lookup"><span data-stu-id="c493b-448">Feature updates</span></span>
### <a name="word"></a><span data-ttu-id="c493b-449">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-449">Word</span></span>

- <span data-ttu-id="c493b-450">**提及和註解通知電子郵件目前包含預覽：** 提及和註解的電子郵件通知現在包含註解文字的預覽，以及該註解所參照的內容。</span><span class="sxs-lookup"><span data-stu-id="c493b-450">**Mention & comment notification emails now contain previews:** Email notifications for mentions & comments will now include previews of the comment text and context for what it is referring to.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="c493b-453">解決的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-453">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c493b-454">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-454">Excel</span></span>

- <span data-ttu-id="c493b-455">在某些情況下，協助工具檢查程式不會顯示圖案​​建議的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-455">In some cases, the Accessibility checker would not show the recommendations for shapes.</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-456">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-456">Outlook</span></span>

- <span data-ttu-id="c493b-457">儲存在左側瀏覽窗格 [我的最愛] 的資料夾可能會間歇性消失。</span><span class="sxs-lookup"><span data-stu-id="c493b-457">Folders saved in 'Favorites' in the left navigation pane may intermittently disappear.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-458">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-458">PowerPoint</span></span>

- <span data-ttu-id="c493b-459">已修正使用 PowerPoint 筆跡動畫時，無法完整轉譯或跳過的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-459">Fixed an issue where Ink may not render completely or get skipped when used in a PowerPoint ink animations.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2001-january-10"></a><span data-ttu-id="c493b-461">版本 2001：1 月 10 日</span><span class="sxs-lookup"><span data-stu-id="c493b-461">Version 2001: January 10</span></span>
<span data-ttu-id="c493b-462">*版本 2001 (組建 12430.20000)*</span><span class="sxs-lookup"><span data-stu-id="c493b-462">*Version 2001 (Build 12430.20000)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="c493b-464">功能更新</span><span class="sxs-lookup"><span data-stu-id="c493b-464">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="c493b-465">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-465">Excel</span></span>
- <span data-ttu-id="c493b-466">**將圖形另存為圖片：** 只要按幾下，即可將圖形、圖示或其他物件另存成圖片，便於您於任何其他地方使用。</span><span class="sxs-lookup"><span data-stu-id="c493b-466">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="c493b-467">深入了解</span><span class="sxs-lookup"><span data-stu-id="c493b-467">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

### <a name="outlook"></a><span data-ttu-id="c493b-468">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-468">Outlook</span></span>
- <span data-ttu-id="c493b-469">**使用者現在可以將 Word/Excel/Outlook 中的物件另存為 Windows 的圖片：** 如同在 PowerPoint 中已具有的功能，使用者現在可以將 Word、Excel 和 Outlook 中的物件另存為圖片。</span><span class="sxs-lookup"><span data-stu-id="c493b-469">**User can now save objects in Word/Excel/Outlook as a picture for Windows.:** With the ability already seen in PowerPoint, users can now save objects in Word, Excel and Outlook as a picture.</span></span> <span data-ttu-id="c493b-470">物件包括圖形、圖示、圖片及其他內容！</span><span class="sxs-lookup"><span data-stu-id="c493b-470">Objects include shapes, icons, pictures, and more!</span></span> <span data-ttu-id="c493b-471">此功能只要按滑鼠右鍵的功能表就能存取。</span><span class="sxs-lookup"><span data-stu-id="c493b-471">This can be accessed through the right-click menu.</span></span>

### <a name="word"></a><span data-ttu-id="c493b-472">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-472">Word</span></span>
- <span data-ttu-id="c493b-473">**只要在 Word 中繪製圖形即可輕鬆選取筆跡：** [繪圖] 索引標籤上的 [套索] 工具可協助您選取使用筆跡繪製的物件。</span><span class="sxs-lookup"><span data-stu-id="c493b-473">**Easily select ink in Word by drawing a shape around it.:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="c493b-474">選取個別筆劃或整個字。</span><span class="sxs-lookup"><span data-stu-id="c493b-474">Select individual strokes, or whole words.</span></span> <span data-ttu-id="c493b-475">當您有大量筆跡但只想要使用其中一部分時，這功能尤其方便。</span><span class="sxs-lookup"><span data-stu-id="c493b-475">It's handy when you have lots of ink and you only want to work with some of it.</span></span> [<span data-ttu-id="c493b-476">深入了解</span><span class="sxs-lookup"><span data-stu-id="c493b-476">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="c493b-477">**將圖形另存為圖片：** 只要按幾下，即可將圖形、圖示或其他物件另存成圖片，便於您於任何其他地方使用。</span><span class="sxs-lookup"><span data-stu-id="c493b-477">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="c493b-478">深入了解</span><span class="sxs-lookup"><span data-stu-id="c493b-478">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="c493b-481">解決的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-481">Resolved issues</span></span>
### <a name="onenote"></a><span data-ttu-id="c493b-482">OneNote</span><span class="sxs-lookup"><span data-stu-id="c493b-482">OneNote</span></span>
- <span data-ttu-id="c493b-483">100% 解析度時，頁面索引標籤可能會顯得太小並過於接近。</span><span class="sxs-lookup"><span data-stu-id="c493b-483">Page tabs may appear too small and close together at 100% resolution.</span></span>

### <a name="word"></a><span data-ttu-id="c493b-484">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-484">Word</span></span>
- <span data-ttu-id="c493b-485">在大量的註解組合中，刪除接近註解清單結尾附近的註解，可能會導致窗格捲動到最上方。</span><span class="sxs-lookup"><span data-stu-id="c493b-485">In a large set of comments, deleting a comment near the end of the list of comments may result in the pane scrolling all the way to the top.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2001-january-03"></a><span data-ttu-id="c493b-487">版本 2001：1 月 3 日</span><span class="sxs-lookup"><span data-stu-id="c493b-487">Version 2001: January 03</span></span>
<span data-ttu-id="c493b-488">*版本 2001 (組建 12425.20000)*</span><span class="sxs-lookup"><span data-stu-id="c493b-488">*Version 2001 (Build 12425.20000)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="c493b-490">解決的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-490">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-491">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-491">Excel</span></span>
- <span data-ttu-id="c493b-492">有些框線在 A4 大小的紙張上可能無法如預期列印。</span><span class="sxs-lookup"><span data-stu-id="c493b-492">Some border lines may not print as expected on A4 size paper.</span></span>
- <span data-ttu-id="c493b-493">使用 VBA 將影像新增到工作表圖表物件的頁首/頁尾可能會導致錯誤。</span><span class="sxs-lookup"><span data-stu-id="c493b-493">Adding an image to the header/footer of a chart object on a sheet using VBA may result in an error.</span></span>
- <span data-ttu-id="c493b-494">設定圖表座標軸格式時，標籤之間的間隔限制為 255。</span><span class="sxs-lookup"><span data-stu-id="c493b-494">When formatting a chart axis, the interval between labels was limited to 255.</span></span>
- <span data-ttu-id="c493b-495">已修正嘗試重新整理 XML 查詢 (資料來源 URL 遭截斷) 時發生錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-495">Fixed an issue where an error would occur trying to refresh an XML query in which the URL to the datasource was being truncated.</span></span>
- <span data-ttu-id="c493b-496">活頁簿統計資料會報告所有開啟的活頁簿 (包括個人巨集活頁簿) 中的巨集計數。</span><span class="sxs-lookup"><span data-stu-id="c493b-496">Workbook Statistics would report a macro count from all open workbooks, including the personal macro workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-497">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-497">Outlook</span></span>
- <span data-ttu-id="c493b-498">切換資料夾可能會導致郵件清單/郵件預覽中「快閃」短暫的空白。</span><span class="sxs-lookup"><span data-stu-id="c493b-498">Switching folders may result in a brief white 'flash' in the mail list / mail preview.</span></span> <span data-ttu-id="c493b-499">此行為在深色模式中更明顯。</span><span class="sxs-lookup"><span data-stu-id="c493b-499">This behavior was more pronounced in dark mode.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-500">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-500">PowerPoint</span></span>
- <span data-ttu-id="c493b-501">已修正呼叫 Shape.Paste 方法會導致貼上的圖形置於焦點下的物件模型問題。&nbsp;</span><span class="sxs-lookup"><span data-stu-id="c493b-501">Fixed an Object Model issue where calling Shape.Paste method would result in the pasted shape receiving focus.&nbsp;</span></span>
- <span data-ttu-id="c493b-502">已改善複製貼上案例：&nbsp;以程式設計方式從 PowerPoint 投影片複製圖形，並將其貼到循環播放中的另一張投影片會失敗並發生異常錯誤。&nbsp;</span><span class="sxs-lookup"><span data-stu-id="c493b-502">Improved a copy-paste scenario:&nbsp;Progamatically copying a shape from a PowerPoint slide and pasting it to another slide in a loop could fail with an exception error.&nbsp;</span></span>
- <span data-ttu-id="c493b-503">折疊及展開節標頭後，投影片節標頭的動畫無法正確呈現。</span><span class="sxs-lookup"><span data-stu-id="c493b-503">Animation in the section headers of slides would not render properly after collapsing and expanding section headers.</span></span>

### <a name="project"></a><span data-ttu-id="c493b-504">Project</span><span class="sxs-lookup"><span data-stu-id="c493b-504">Project</span></span>
- <span data-ttu-id="c493b-505">已修正文字換行在任務和資源使用狀況檢視中無法正常運作的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-505">Fixed an issue where text wrapping wasn't working in the task and resource usage views.</span></span>
- <span data-ttu-id="c493b-506">已修正如果某資源有多個成本比率，則工作分派的成本值可能不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-506">Fixed an issue where if a resource has more than one cost rate, cost value on assignments may not be correct.</span></span>

### <a name="word"></a><span data-ttu-id="c493b-507">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-507">Word</span></span>
- <span data-ttu-id="c493b-508">在方程式中插入控制項 (例如文字內容控制項)，然後儲存再開啟檔案，便會導致內容無法讀取的錯誤。</span><span class="sxs-lookup"><span data-stu-id="c493b-508">Inserting a control (such as a Text Content Control) in an equation, then saving and opening the file would result in an un-readable content error.</span></span>
- <span data-ttu-id="c493b-509">共同撰寫時，Word 電腦版可能不會顯示使用 Word Online 新增註解的功能。</span><span class="sxs-lookup"><span data-stu-id="c493b-509">When co-authoring, adding a comment using Word online may not appear in Word desktop.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c493b-510">Office 套件</span><span class="sxs-lookup"><span data-stu-id="c493b-510">Office Suite</span></span>
- <span data-ttu-id="c493b-511">嘗試在只有一個授權的情況下變更授權時，不再顯示有效授權的錯誤到期日。</span><span class="sxs-lookup"><span data-stu-id="c493b-511">Removed showing an erroneous expiry date of the valid license when trying to change license with only one license.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2001-december-13"></a><span data-ttu-id="c493b-513">版本 2001：12 月 13 日</span><span class="sxs-lookup"><span data-stu-id="c493b-513">Version 2001: December 13</span></span>
<span data-ttu-id="c493b-514">*版本 2001 (組建 12410.20000)*</span><span class="sxs-lookup"><span data-stu-id="c493b-514">*Version 2001 (Build 12410.20000)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="c493b-516">功能更新</span><span class="sxs-lookup"><span data-stu-id="c493b-516">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="c493b-517">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-517">Outlook</span></span>

- <span data-ttu-id="c493b-518">**將電子郵件拖曳到您擁有的群組：** 從您的 [收件匣] 拖曳郵件和交談以將它們移動和複製。</span><span class="sxs-lookup"><span data-stu-id="c493b-518">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="c493b-519">您拖曳的郵件將會與所有群組成員共用。</span><span class="sxs-lookup"><span data-stu-id="c493b-519">Messages you drag will be shared with all group members.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="c493b-522">解決的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-522">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="c493b-523">Access</span><span class="sxs-lookup"><span data-stu-id="c493b-523">Access</span></span>
- <span data-ttu-id="c493b-524">執行可參考連結之 ODBC 資料表且包含 Order By 子句的聯集查詢，會導致 64 位元 Access 當機。</span><span class="sxs-lookup"><span data-stu-id="c493b-524">Executing a union query that references linked ODBC table(s) and contains an Order By clause crashes 64 bit Access.</span></span>
- <span data-ttu-id="c493b-525">Access (O365) 中由聯集查詢的資料匯合可能會導致小數資料的截斷。</span><span class="sxs-lookup"><span data-stu-id="c493b-525">Summing of data from union queries in Access (O365) may result in truncation of decimal data.</span></span>
- <span data-ttu-id="c493b-526">ACE 的 COM 介面並未公開於 Office 應用程式的外部使用。</span><span class="sxs-lookup"><span data-stu-id="c493b-526">COM Interfaces for ACE are not exposed for use outside of Office applications.</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-527">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-527">Excel</span></span>
- <span data-ttu-id="c493b-528">無法執行插入3D 模型 (動態或靜態)，且嘗試 [另存成圖片]。</span><span class="sxs-lookup"><span data-stu-id="c493b-528">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>
- <span data-ttu-id="c493b-529">從 Backstage 啟動意見反應的 Shortkey (Alt+Ctrl + 7/8) 與 AZERTY 鍵盤 (Alt-Gr + 7/8) 有衝突。</span><span class="sxs-lookup"><span data-stu-id="c493b-529">The shortkey (Alt+Ctrl + 7/8)  to launch feedback from backstage is in conflict with AZERTY keyboards (Alt-Gr + 7/8).</span></span> <span data-ttu-id="c493b-530">影響：使用者可能無法使用下列字元，例如：'\'。</span><span class="sxs-lookup"><span data-stu-id="c493b-530">Impact: users may not be able to use some characters such as: '\'.</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-531">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-531">Outlook</span></span>
- <span data-ttu-id="c493b-532">解決導致電子郵件傳送到收件者錯誤地址的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-532">Addresses an issue that caused email to be sent to the wrong address for the recipient.</span></span>
- <span data-ttu-id="c493b-533">解決了導致 Outlook 不正確地允許使用者具有信箱的 &quot;[讀取]&quot; 存取權，而變更郵件之讀取/未讀取狀態的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-533">Addresses an issue that caused Outlook to incorrectly allow users with &quot;read&quot; access to a mailbox to change the read/unread state of a message.</span></span>
- <span data-ttu-id="c493b-534">網站上安全性憑證的撤銷無法由 [產品支援] 重新製造。</span><span class="sxs-lookup"><span data-stu-id="c493b-534">The revocation of the security certificate on the web site is not re-producible by Product Support.</span></span> <span data-ttu-id="c493b-535">需要新增 [記錄] 以協助根本解決問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-535">Logging needs to be added to help root cause the issue.</span></span>
- <span data-ttu-id="c493b-536">解決導致使用者看到同步處理失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-536">Addresses an issue that caused users to see synchronization failures.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-537">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-537">PowerPoint</span></span>
- <span data-ttu-id="c493b-538">無法執行插入3D 模型 (動態或靜態)，且嘗試 [另存成圖片]。</span><span class="sxs-lookup"><span data-stu-id="c493b-538">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>

### <a name="project"></a><span data-ttu-id="c493b-539">Project</span><span class="sxs-lookup"><span data-stu-id="c493b-539">Project</span></span>
- <span data-ttu-id="c493b-540">[工作] 不會在 [手動排程的子工作] 彙總中計算。</span><span class="sxs-lookup"><span data-stu-id="c493b-540">Task work is not calculated in Summary roll-up for manually scheduled child tasks.</span></span>
- <span data-ttu-id="c493b-541">嘗試儲存伺服器架構專案時，從 [功能區] 按鈕叫用的 Project VBA 程式碼可能無法使用。</span><span class="sxs-lookup"><span data-stu-id="c493b-541">Project VBA Code invoked from a Ribbon button may not work when trying to save server-based Projects.</span></span>
- <span data-ttu-id="c493b-542">除非 Project 已在執行，從 SharePoint 文件庫中開啟專案檔案會顯示錯誤，且檔案無法開啟。</span><span class="sxs-lookup"><span data-stu-id="c493b-542">Unless Project is already running, opening Project files from a SharePoint document library displays an error and the file will not open.</span></span>

### <a name="word"></a><span data-ttu-id="c493b-543">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-543">Word</span></span>
- <span data-ttu-id="c493b-544">儲存現有檔案可能會無法執行。</span><span class="sxs-lookup"><span data-stu-id="c493b-544">Saving existing files may not work.</span></span>
- <span data-ttu-id="c493b-545">在 [拼字及文法檢查編輯器] 視窗中使用方向鍵可能會導致間歇性閃爍。</span><span class="sxs-lookup"><span data-stu-id="c493b-545">Using arrow keys in the Spelling and Grammar editor window may result in intermittent flickering.</span></span>
- <span data-ttu-id="c493b-546">解決待處理時，相關註解可能不會轉換成指向註解。</span><span class="sxs-lookup"><span data-stu-id="c493b-546">When resolving a follow-up, associated comments may not convert to point comments.</span></span>
- <span data-ttu-id="c493b-547">無法執行插入3D 模型 (動態或靜態)，且嘗試 [另存成圖片]。</span><span class="sxs-lookup"><span data-stu-id="c493b-547">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c493b-548">Office 套件</span><span class="sxs-lookup"><span data-stu-id="c493b-548">Office Suite</span></span>
- <span data-ttu-id="c493b-549">修正了 Office 更新訊息不以預期語言顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-549">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="c493b-550">自此以後，Office 更新訊息會正確符合 Windows 顯示語言。</span><span class="sxs-lookup"><span data-stu-id="c493b-550">Going forward, Office update messages will correctly match the Windows display language.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1912-december-06"></a><span data-ttu-id="c493b-552">版本 1912：12 月 06 日</span><span class="sxs-lookup"><span data-stu-id="c493b-552">Version 1912: December 06</span></span>
<span data-ttu-id="c493b-553">*版本 1912 (組建 12325.20012)*</span><span class="sxs-lookup"><span data-stu-id="c493b-553">*Version 1912 (Build 12325.20012)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="c493b-555">功能更新</span><span class="sxs-lookup"><span data-stu-id="c493b-555">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="c493b-556">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-556">Outlook</span></span>

- <span data-ttu-id="c493b-557">**進階群組電子郵件設定：** 此功能可協助使用者自訂要在收件匣中接收/追蹤哪些電子郵件或活動。</span><span class="sxs-lookup"><span data-stu-id="c493b-557">**Advanced group email settings:** This feature helps groups users to customize which emails or events to receive/follow in their inbox.</span></span>

- <span data-ttu-id="c493b-558">**群組命名原則：** 群組命名原則可讓 IT 系統管理員將組織中使用者所建立群組的名稱標準化及管理。</span><span class="sxs-lookup"><span data-stu-id="c493b-558">**Groups Naming policy:** A group naming policy enables the IT admin to standardize and manage the names of groups created by users in the organization.</span></span> <span data-ttu-id="c493b-559">系統管理員可以要求在建立群組時，將特定首碼和尾碼新增至群組的名稱，而且可以封鎖使用特定字詞。</span><span class="sxs-lookup"><span data-stu-id="c493b-559">The admin can require a specific prefix and suffix be added to the name for a group when it's created, and can block specific words from being used.</span></span> <span data-ttu-id="c493b-560">這有助於將群組名稱中使用不當字詞的情況最小化，以及 IT 管理其目錄中群組的表示方式。</span><span class="sxs-lookup"><span data-stu-id="c493b-560">This helps minimize the use of inappropriate words in group names as well as IT manage the representation of groups in their directory.</span></span> <span data-ttu-id="c493b-561">命名原則也可協助部署小組網站的組織根據部門來分類。</span><span class="sxs-lookup"><span data-stu-id="c493b-561">Naming Policy also helps organizations that deploy team sites to categorize them based on department.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c493b-562">Office 套件</span><span class="sxs-lookup"><span data-stu-id="c493b-562">Office Suite</span></span>

- <span data-ttu-id="c493b-563">**索引標籤式窗格：** 現在您可以使用應用程式右側的索引標籤 UI，在多個窗格之間切換。</span><span class="sxs-lookup"><span data-stu-id="c493b-563">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="c493b-564">只有當您開啟 2 個以上的窗格時，該 UI 才會顯示。</span><span class="sxs-lookup"><span data-stu-id="c493b-564">The UI will only be visible when you have 2+ panes open.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="c493b-567">解決的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-567">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c493b-568">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-568">Excel</span></span>
- <span data-ttu-id="c493b-569">使用者在使用某些非英文字元集的情況下，儲存變更時可能會遇到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-569">Users may encounter an error when saving changes while using some non-English character sets.</span></span>
- <span data-ttu-id="c493b-570">使用者在存取隱藏的命名範圍時可能會發生錯誤。</span><span class="sxs-lookup"><span data-stu-id="c493b-570">Users may encounter an error when accessing a hidden named range.</span></span>
- <span data-ttu-id="c493b-571">停用使用 4K 解析度的硬體圖形加速的情況下，可能會在捲動時發生延遲儲存格呈現的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-571">Disabling hardware graphics acceleration with 4K resolution may result in delayed rendering of cells when scrolling around.</span></span>
- <span data-ttu-id="c493b-572">清除與儲存格界限重疊的長型公式，可能仍舊會跨儲存格界限顯示出來。</span><span class="sxs-lookup"><span data-stu-id="c493b-572">Clearing a long formula that overlaps a cell boundary may still display across the cell boundary.</span></span>
- <span data-ttu-id="c493b-573">解決了開啟內嵌活頁簿時，功能區自訂無法載入的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-573">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>
- <span data-ttu-id="c493b-574">邊界下拉式功能表可能無法正確呈現。</span><span class="sxs-lookup"><span data-stu-id="c493b-574">Margin dropdown menu may not render correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="c493b-575">OneNote</span><span class="sxs-lookup"><span data-stu-id="c493b-575">OneNote</span></span>
- <span data-ttu-id="c493b-576">OneNote 可能無法透過「會議記事」Outlook 增益集開啟。</span><span class="sxs-lookup"><span data-stu-id="c493b-576">OneNote may not open via the 'Meeting Notes' Outlook add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-577">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-577">Outlook</span></span>
- <span data-ttu-id="c493b-578">保留原則標籤可能會將保留時間顯示於括弧中。</span><span class="sxs-lookup"><span data-stu-id="c493b-578">Retention policy labels may display the retention time period in parenthesis.</span></span>
- <span data-ttu-id="c493b-579">空格可能會顯示於日文語言套件的連絡人卡片中。</span><span class="sxs-lookup"><span data-stu-id="c493b-579">Blank spaces may appear in Contact cards with Japanese language pack.</span></span>
- <span data-ttu-id="c493b-580">內嵌插入至 Outlook 電子郵件訊息中的影像有時候會改變大小。</span><span class="sxs-lookup"><span data-stu-id="c493b-580">Images inserted inline to Outlook e-mail messages can sometimes get resized.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-581">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-581">PowerPoint</span></span>
- <span data-ttu-id="c493b-582">如果使用者雲端檔案的投影片上有兩個 (或多個) 不同的影片，影片影像可正確呈現，但是當使用者按一下每一個檔案來播放時，影片內容會是相同的。</span><span class="sxs-lookup"><span data-stu-id="c493b-582">If a user has two (or more) different videos on a slide in a cloud file, the video images are rendered correctly, but when the user clicks on each one to play, the video content is the same.</span></span>
- <span data-ttu-id="c493b-583">在某些情況下，使用觸控裝置進行捲動將無法運作。</span><span class="sxs-lookup"><span data-stu-id="c493b-583">In some cases, scrolling with touch devices will not work.</span></span>
- <span data-ttu-id="c493b-584">邊界下拉式功能表可能無法正確呈現。</span><span class="sxs-lookup"><span data-stu-id="c493b-584">Margin dropdown menu may not render correctly.</span></span>
- <span data-ttu-id="c493b-585">Office 應用程式之間的安全性連結可能無法啟動連結的應用程式。</span><span class="sxs-lookup"><span data-stu-id="c493b-585">Safelinks from one Office application to another may not launch the linked application.</span></span>

### <a name="project"></a><span data-ttu-id="c493b-586">Project</span><span class="sxs-lookup"><span data-stu-id="c493b-586">Project</span></span>
- <span data-ttu-id="c493b-587">當您使用 [比較專案] 功能時，Project 可能會當機。</span><span class="sxs-lookup"><span data-stu-id="c493b-587">Project may crash when you use the Compare Projects feature.</span></span>
- <span data-ttu-id="c493b-588">如果您在 [深色] 模式中，當您移至含有過度分配資源之工作上的工作檢查面板時，將無法讀取資料表。</span><span class="sxs-lookup"><span data-stu-id="c493b-588">If you are in Dark mode, when you go to the task inspector panel on a task with an over allocated resource, you are unable to read the table.</span></span>
- <span data-ttu-id="c493b-589">將沒有作業的任務進行進位設定為 1 天。</span><span class="sxs-lookup"><span data-stu-id="c493b-589">Setting effort on tasks that have no assignments are rounded to 1 day.</span></span>

### <a name="word"></a><span data-ttu-id="c493b-590">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-590">Word</span></span>
- <span data-ttu-id="c493b-591">在特定條件下，完成合併列印之後儲存的檔案可能無法使用。</span><span class="sxs-lookup"><span data-stu-id="c493b-591">Saving a file after doing a mail merge may not work under certain conditions.</span></span>
- <span data-ttu-id="c493b-592">建置組塊召集人可能會顯示不正確通知：&quot;您已修改過樣式、建置組塊&quot;。</span><span class="sxs-lookup"><span data-stu-id="c493b-592">Building blocks organizer may display an invalid alert: &quot;You have modified styles, building blocks&quot;.</span></span>
- <span data-ttu-id="c493b-593">使用複製/貼上時，有時會重新載入註解窗格。</span><span class="sxs-lookup"><span data-stu-id="c493b-593">Comment pane sometimes gets reloaded when using copy/paste.</span></span>
- <span data-ttu-id="c493b-594">註解有時不會以正確的順序貼上。</span><span class="sxs-lookup"><span data-stu-id="c493b-594">Comments are sometimes not pasted in the correct order.</span></span>
- <span data-ttu-id="c493b-595">將含有自訂樣式的多層級清單範本套用至現有的文件時，可能在特定條件下不會保留該樣式。</span><span class="sxs-lookup"><span data-stu-id="c493b-595">Applying a template consisting of a multi-level list with custom styles to existing documents may not preserve the style under certain conditions.</span></span>
- <span data-ttu-id="c493b-596">調整分割螢幕邊界的大小可能會造成其他的分割螢幕。</span><span class="sxs-lookup"><span data-stu-id="c493b-596">Resizing a split screen border may introduce an additional split screen.</span></span>
- <span data-ttu-id="c493b-597">邊界下拉式功能表可能無法正確呈現。</span><span class="sxs-lookup"><span data-stu-id="c493b-597">Margin dropdown menu may not render correctly.</span></span>
- <span data-ttu-id="c493b-598">@提及註解卡中的使用者可能會顯示 JSON。</span><span class="sxs-lookup"><span data-stu-id="c493b-598">At-mentioning a user in a comment card may show JSON.</span></span>
- <span data-ttu-id="c493b-599">Office 應用程式之間的安全性連結可能無法啟動連結的應用程式。</span><span class="sxs-lookup"><span data-stu-id="c493b-599">Safelinks from one Office application to another may not launch the linked application.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c493b-600">Office 套件</span><span class="sxs-lookup"><span data-stu-id="c493b-600">Office Suite</span></span>
- <span data-ttu-id="c493b-601">針對日文產品，帳戶使用者的姓名可能會以錯誤的順序出現。</span><span class="sxs-lookup"><span data-stu-id="c493b-601">For Japanese based products, account user first name, last name may appear in incorrect order.</span></span>
- <span data-ttu-id="c493b-602">將滑鼠指標暫留於註解上方時，可能會在註解周圍顯示文字方塊外框的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-602">Hovering a mouse pointer over comments may display a textbox outline around the comment.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1912-november-15"></a><span data-ttu-id="c493b-604">版本 1912：11 月 15 日</span><span class="sxs-lookup"><span data-stu-id="c493b-604">Version 1912: November 15</span></span>
<span data-ttu-id="c493b-605">*版本1912 (組建 12307.20000)*</span><span class="sxs-lookup"><span data-stu-id="c493b-605">*Version 1912 (Build 12307.20000)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="c493b-607">功能更新</span><span class="sxs-lookup"><span data-stu-id="c493b-607">Feature updates</span></span>
### <a name="insights-services"></a><span data-ttu-id="c493b-608">深入解析服務</span><span class="sxs-lookup"><span data-stu-id="c493b-608">Insights Services</span></span>
- <span data-ttu-id="c493b-609">**Excel 構想中的自然語言查詢：** Excel 構想的新功能，詢問關於您資料的自然語言問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-609">**Natural Language Queries in Ideas in Excel:** Excel Ideas's new capability to ask a natural language question about your data.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="c493b-612">解決的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-612">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c493b-613">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-613">Excel</span></span>
- <span data-ttu-id="c493b-614">某些當地語系化版本的 [文字到欄] 功能可能會失敗。</span><span class="sxs-lookup"><span data-stu-id="c493b-614">Text to Column functionality may fail for some localizations.</span></span>
- <span data-ttu-id="c493b-615">編輯儲存格中的動態陣列公式可能會導致文字在儲存格邊界以外對齊。</span><span class="sxs-lookup"><span data-stu-id="c493b-615">Editing dynamic array formulas within a cell may result in text being aligned outside of the boundary of the cell.</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-616">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-616">Outlook</span></span>
- <span data-ttu-id="c493b-617">新增透過群組原則強制執行 S/MIME 設定的功能。</span><span class="sxs-lookup"><span data-stu-id="c493b-617">Added the ability to enforce S/MIME configuration via group policy.</span></span>
- <span data-ttu-id="c493b-618">內嵌影像可能會比預期小。</span><span class="sxs-lookup"><span data-stu-id="c493b-618">Embedded images may appear smaller than expected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-619">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-619">PowerPoint</span></span>
- <span data-ttu-id="c493b-620">當您將焦點移出文字後，游標可能會消失。</span><span class="sxs-lookup"><span data-stu-id="c493b-620">Cursor may disappear after moving focus from text.</span></span>

### <a name="project"></a><span data-ttu-id="c493b-621">Project</span><span class="sxs-lookup"><span data-stu-id="c493b-621">Project</span></span>
- <span data-ttu-id="c493b-622">使用者可能會遇到授權錯誤。</span><span class="sxs-lookup"><span data-stu-id="c493b-622">Users may experience an error regarding licensing.</span></span>
- <span data-ttu-id="c493b-623">日期選擇器中的 [今日] 按鈕有時候可能會設定不正確的日期。</span><span class="sxs-lookup"><span data-stu-id="c493b-623">The Today button in the date picker may sometimes set the incorrect date.</span></span>

### <a name="word"></a><span data-ttu-id="c493b-624">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-624">Word</span></span>
- <span data-ttu-id="c493b-625">以滑鼠右鍵按一下有時不會選取整個字詞。</span><span class="sxs-lookup"><span data-stu-id="c493b-625">Right-clicking can sometimes not result in selecting the whole word.</span></span>
- <span data-ttu-id="c493b-626">轉換成建議格式之後，游標在物件內可能仍處於使用中狀態。</span><span class="sxs-lookup"><span data-stu-id="c493b-626">The cursor may remain active within an object after converting to a suggested format.</span></span>
- <span data-ttu-id="c493b-627">訊息中的影像在某些情況下可能會不正確的縮放。</span><span class="sxs-lookup"><span data-stu-id="c493b-627">Images in messages may be incorrectly scaled in some scenarios.</span></span>
- <span data-ttu-id="c493b-628">某些主題可能會導致難以判斷所選取的註解。</span><span class="sxs-lookup"><span data-stu-id="c493b-628">Some themes may make it difficult to determine which comment is selected.</span></span>
- <span data-ttu-id="c493b-629">選取註解提示之後，在窗格切換器中隱藏時，現在會顯示新式註解窗格。</span><span class="sxs-lookup"><span data-stu-id="c493b-629">Selecting a comment hint should now show the modern comments pane when hidden in pane switcher.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c493b-630">Office 套件</span><span class="sxs-lookup"><span data-stu-id="c493b-630">Office Suite</span></span>
- <span data-ttu-id="c493b-631">回覆註解可能會導致文字方塊垂直延伸到窗格的邊緣以外。</span><span class="sxs-lookup"><span data-stu-id="c493b-631">Replying to a comment may cause the textbox to expand vertically beyond the edge of the pane.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1912-november-08"></a><span data-ttu-id="c493b-633">版本 1912：11 月 8 日</span><span class="sxs-lookup"><span data-stu-id="c493b-633">Version 1912: November 08</span></span>
<span data-ttu-id="c493b-634">*版本 1912 (組建 12231.20000)*</span><span class="sxs-lookup"><span data-stu-id="c493b-634">*Version 1912 (Build 12231.20000)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="c493b-636">功能更新</span><span class="sxs-lookup"><span data-stu-id="c493b-636">Feature updates</span></span>
### <a name="user-lifecycle"></a><span data-ttu-id="c493b-637">使用者生命週期</span><span class="sxs-lookup"><span data-stu-id="c493b-637">User Lifecycle</span></span>
- <span data-ttu-id="c493b-638">**AFO 啟用的經驗改進：** 對客戶啟用新電腦隨附的 Office 時，所會看到的畫面進行更新。</span><span class="sxs-lookup"><span data-stu-id="c493b-638">**Experience improvements for AFO activation:** Updates to the screens customers see when activating Office that comes bundled with their new PC.</span></span>

### <a name="word"></a><span data-ttu-id="c493b-639">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-639">Word</span></span>
- <span data-ttu-id="c493b-640">**Word 中的全新和改良的線上影片體驗：** 全新和更安全的線上影片體驗，可協助您在 Word 中插入新的影片並播放現有影片。</span><span class="sxs-lookup"><span data-stu-id="c493b-640">**New and improved online video experience in Word:** New and more secure online video experience to help you insert new videos and play existing videos in Word.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="c493b-643">解決的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-643">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="c493b-644">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-644">Outlook</span></span>
- <span data-ttu-id="c493b-645">與跨資料夾內容有關的間歇性損毀。</span><span class="sxs-lookup"><span data-stu-id="c493b-645">Intermittent crash involving cross folder content.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c493b-646">Office 套件</span><span class="sxs-lookup"><span data-stu-id="c493b-646">Office Suite</span></span>
- <span data-ttu-id="c493b-647">將圖表從 Excel 貼上至 PowerPoint 可能會造成圖表的大小縮小。</span><span class="sxs-lookup"><span data-stu-id="c493b-647">Pasting a chart from Excel to PowerPoint can reduce the size of the chart.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1911-november-01"></a><span data-ttu-id="c493b-649">版本 1911：11 月 1 日</span><span class="sxs-lookup"><span data-stu-id="c493b-649">Version 1911: November 01</span></span>
<span data-ttu-id="c493b-650">*版本 1911 (組建 12228.20020)*</span><span class="sxs-lookup"><span data-stu-id="c493b-650">*Version 1911 (Build 12228.20020)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="c493b-652">功能更新</span><span class="sxs-lookup"><span data-stu-id="c493b-652">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="c493b-653">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-653">Excel</span></span>
- <span data-ttu-id="c493b-654">**將內容與 SVG 物件一起顯示！：** 在 Office 中轉換地圖、圖表和其他 SVG 向量等物件時，現在您可以保留物件中的文字。</span><span class="sxs-lookup"><span data-stu-id="c493b-654">**Bring the context along with your SVG objects!:** Now you can retain the text in maps, chart and other SVG vectors when converting these objects in Office.</span></span>

- <span data-ttu-id="c493b-655">**拿起 Surface 手寫筆時查看手寫筆選項：** 當您在 Word、Excel 或 PowerPoint 中先拿起 Surface 手寫筆時，[繪圖] 索引標籤將會啟動，讓您輕鬆地選取畫筆色彩。</span><span class="sxs-lookup"><span data-stu-id="c493b-655">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-656">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-656">PowerPoint</span></span>
- <span data-ttu-id="c493b-657">**將內容與 SVG 物件一起顯示！：** 在 Office 中轉換地圖、圖表和其他 SVG 向量等物件時，現在您可以保留物件中的文字。</span><span class="sxs-lookup"><span data-stu-id="c493b-657">**Bring the context along with your SVG objects!:** Now you can retain the text in maps, chart and other SVG vectors when converting these objects in Office.</span></span>

- <span data-ttu-id="c493b-658">**拿起 Surface 手寫筆時查看手寫筆選項：** 當您在 Word、Excel 或 PowerPoint 中先拿起 Surface 手寫筆時，[繪圖] 索引標籤將會啟動，讓您輕鬆地選取畫筆色彩。</span><span class="sxs-lookup"><span data-stu-id="c493b-658">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

### <a name="visio"></a><span data-ttu-id="c493b-659">Visio</span><span class="sxs-lookup"><span data-stu-id="c493b-659">Visio</span></span>
- <span data-ttu-id="c493b-660">**在 Excel 中製作精美的 Visio 圖表：** 在 Excel 中快速且輕鬆地將資料呈現為精美的 Visio 圖表。</span><span class="sxs-lookup"><span data-stu-id="c493b-660">**Make polished Visio diagrams in Excel:** Quickly and easily visualize your data into polished Visio diagrams within Excel.</span></span> <span data-ttu-id="c493b-661">[深入了解](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)。</span><span class="sxs-lookup"><span data-stu-id="c493b-661">[Learn more](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c).</span></span>

### <a name="word"></a><span data-ttu-id="c493b-662">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-662">Word</span></span>
- <span data-ttu-id="c493b-663">**拿起 Surface 手寫筆時查看手寫筆選項：** 當您在 Word、Excel 或 PowerPoint 中先拿起 Surface 手寫筆時，[繪圖] 索引標籤將會啟動，讓您輕鬆地選取畫筆色彩。</span><span class="sxs-lookup"><span data-stu-id="c493b-663">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

- <span data-ttu-id="c493b-664">**改善共同撰寫：** 改善共同撰寫的體驗，盡可能讓其他人即時收到修改過的內容。</span><span class="sxs-lookup"><span data-stu-id="c493b-664">**Coauthoring improvements:** Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

- <span data-ttu-id="c493b-665">**其他人更快速看到您的變更：** 共同撰寫增強功能表示，共同作業者可較以往更快速看到您的變更。</span><span class="sxs-lookup"><span data-stu-id="c493b-665">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="c493b-668">解決的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-668">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c493b-669">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-669">Excel</span></span>
- <span data-ttu-id="c493b-670">解決從不受信任的網路共用編輯受保護的檔案時，Excel 可能會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-670">Resolved an issue where Excel may crash when editing a protected file from an untrusted network share.</span></span>
- <span data-ttu-id="c493b-671">解決在刪除含有的走勢圖參考另一個資料表中資料的資料表時，會導致重新開啟檔案時，將檔案識別為已損毀的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-671">Resolved an issue where deleting sheets containing sparklines referencing data on another sheet could cause the file to be identified as corrupted when re-opened.</span></span>
- <span data-ttu-id="c493b-672">解決當您將報表篩選隨著其餘的樞紐分析表一起轉換，以用於 SQL 表格式伺服器的查詢時，可能會遇到結果不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-672">Resolved an Issue where you may get incorrect results when converting report filters along with the rest of the PivotTable for queries to SQL tabular servers.</span></span>
- <span data-ttu-id="c493b-673">同時使用朗讀程式和放大鏡，可能會導致當機。</span><span class="sxs-lookup"><span data-stu-id="c493b-673">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="c493b-674">同時使用朗讀程式和放大鏡，可能會導致當機。</span><span class="sxs-lookup"><span data-stu-id="c493b-674">Using Narrator and Magnifier at the same time may result in a crash.</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-675">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-675">Outlook</span></span>
- <span data-ttu-id="c493b-676">轉寄的電子郵件可能會遺失內嵌的影像。</span><span class="sxs-lookup"><span data-stu-id="c493b-676">A forwarded e-mail may be missing embedded images.</span></span>
- <span data-ttu-id="c493b-677">會議室尋找工具可能會對可用的會議室顯示 &quot;[無]&quot;。</span><span class="sxs-lookup"><span data-stu-id="c493b-677">Room Finder tool may be displaying &quot;None&quot; for available rooms.</span></span>
- <span data-ttu-id="c493b-678">使用者可能無法建立具有嚴格租用戶限制的 Outlook 設定檔。</span><span class="sxs-lookup"><span data-stu-id="c493b-678">Users may not be able to create Outlook profiles with strict tenant restriction.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-679">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-679">PowerPoint</span></span>
- <span data-ttu-id="c493b-680">同時使用朗讀程式和放大鏡，可能會導致當機。</span><span class="sxs-lookup"><span data-stu-id="c493b-680">Using Narrator and Magnifier at the same time may result in a crash.</span></span>

### <a name="project"></a><span data-ttu-id="c493b-681">Project</span><span class="sxs-lookup"><span data-stu-id="c493b-681">Project</span></span>
- <span data-ttu-id="c493b-682">使用者無法將工作標示為已完成，並將它設為 99%。</span><span class="sxs-lookup"><span data-stu-id="c493b-682">User is unable to mark a task as complete, and it gets set to 99%.</span></span>
- <span data-ttu-id="c493b-683">資源撫平無法解決資源過度分派問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-683">Overallocations are not resolved by leveling.</span></span>

### <a name="word"></a><span data-ttu-id="c493b-684">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-684">Word</span></span>
- <span data-ttu-id="c493b-685">同時使用朗讀程式和放大鏡，可能會導致當機。</span><span class="sxs-lookup"><span data-stu-id="c493b-685">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="c493b-686">開啟舊版文件，然後移至 [資訊] 索引標籤會導致當機。</span><span class="sxs-lookup"><span data-stu-id="c493b-686">Opening legacy documents and then going to the Info tab can cause a crash.</span></span>
- <span data-ttu-id="c493b-687">內容功能表中未顯示校訂建議。</span><span class="sxs-lookup"><span data-stu-id="c493b-687">Proofing suggestins are not displaying in contextual menus.</span></span>
- <span data-ttu-id="c493b-688">對註解套用不正確的內容原則。</span><span class="sxs-lookup"><span data-stu-id="c493b-688">Content policies are being incorrectly applied to comments.</span></span>
- <span data-ttu-id="c493b-689">以深色文字編寫的舊版註解在深色模式中不會顯示。</span><span class="sxs-lookup"><span data-stu-id="c493b-689">Legacy comments written with dark text is not visible in Dark Mode.</span></span>
- <span data-ttu-id="c493b-690">使用韓文/英文自動校正時，可能出現不正確的字元。</span><span class="sxs-lookup"><span data-stu-id="c493b-690">Incorrect characters may appear when using Korean/English autocorrect.</span></span>
- <span data-ttu-id="c493b-691">在應優先套用較高的原則標籤前，可能已套用了較低的原則標籤。</span><span class="sxs-lookup"><span data-stu-id="c493b-691">Lower policy labels may be applied when a higher policy label should have taken priority.</span></span>
- <span data-ttu-id="c493b-692">來自 Outlook 郵件中的 cid: 影像連結&nbsp;現在能在要求時成功中斷。</span><span class="sxs-lookup"><span data-stu-id="c493b-692">The links of cid: images from Outlook messages&nbsp;can now be successfully broken when requested.</span></span>
- <span data-ttu-id="c493b-693">同時使用朗讀程式和放大鏡，可能會導致當機。</span><span class="sxs-lookup"><span data-stu-id="c493b-693">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="c493b-694">從瀏覽窗格搜尋可能會失敗。</span><span class="sxs-lookup"><span data-stu-id="c493b-694">Searching from the Navigation pane may fail.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c493b-695">Office 套件</span><span class="sxs-lookup"><span data-stu-id="c493b-695">Office Suite</span></span>
- <span data-ttu-id="c493b-696">某些繪圖可能不會在預覽或投影片放映中顯示。</span><span class="sxs-lookup"><span data-stu-id="c493b-696">Some drawings may not display in preview or slide shows.</span></span>
- <span data-ttu-id="c493b-697">在垂直文字方塊中，部分片假名字元可能無法正確顯示。</span><span class="sxs-lookup"><span data-stu-id="c493b-697">Some katakana characters may display incorrectly in a vertical text box.</span></span>
- <span data-ttu-id="c493b-698">嘗試將檔案儲存到已中斷連線的網路共用時可能會導致當機。</span><span class="sxs-lookup"><span data-stu-id="c493b-698">Attempting to save a file to a disconnected network share may result in a crash.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1911-october-25"></a><span data-ttu-id="c493b-700">版本 1911：10 月 25 日</span><span class="sxs-lookup"><span data-stu-id="c493b-700">Version 1911: October 25</span></span>
<span data-ttu-id="c493b-701">*版本 1911 (組建 12215.20006)*</span><span class="sxs-lookup"><span data-stu-id="c493b-701">*Version 1911 (Build 12215.20006)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="c493b-703">功能更新</span><span class="sxs-lookup"><span data-stu-id="c493b-703">Feature updates</span></span>
### <a name="visio"></a><span data-ttu-id="c493b-704">Visio</span><span class="sxs-lookup"><span data-stu-id="c493b-704">Visio</span></span>

- <span data-ttu-id="c493b-705">**在 Excel 中製作精美的 Visio 圖表：** 在 Excel 中快速且輕鬆地將資料呈現為精美的 Visio 圖表。</span><span class="sxs-lookup"><span data-stu-id="c493b-705">**Make polished Visio diagrams in Excel:** Quickly and easily visualize your data into polished Visio diagrams within Excel.</span></span> [<span data-ttu-id="c493b-706">深入了解</span><span class="sxs-lookup"><span data-stu-id="c493b-706">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="c493b-707">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-707">Word</span></span>

- <span data-ttu-id="c493b-708">**改善共同撰寫：** 改善共同撰寫的體驗，盡可能讓其他人即時收到修改過的內容。</span><span class="sxs-lookup"><span data-stu-id="c493b-708">**Coauthoring improvements:** Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

- <span data-ttu-id="c493b-709">**其他人更快速看到您的變更：** 共同撰寫增強功能表示，共同作業者可較以往更快速看到您的變更。</span><span class="sxs-lookup"><span data-stu-id="c493b-709">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="c493b-712">解決的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-712">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="c493b-713">Access</span><span class="sxs-lookup"><span data-stu-id="c493b-713">Access</span></span>

- <div><span data-ttu-id="c493b-714"><span>記錄計數可能不正確</span></span><span class="sxs-lookup"><span data-stu-id="c493b-714"><span>The record count could be incorrect</span></span></span></div>


### <a name="excel"></a><span data-ttu-id="c493b-715">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-715">Excel</span></span>

- <div><span data-ttu-id="c493b-716"><span>我們已大幅改善刪除合併儲存格的資料行的效能</span></span><span class="sxs-lookup"><span data-stu-id="c493b-716"><span>We significantly improved the performance of deleting columns with merged cells</span></span></span></div>


- <div><span data-ttu-id="c493b-717"><span>可能已防止使用者以 Office 365 Excel 活頁簿格式儲存</span></span><span class="sxs-lookup"><span data-stu-id="c493b-717"><span>Users could be prevented from saving in Office 365 Excel Workbook format</span></span></span></div>


- <div><span data-ttu-id="c493b-718"><span>核取方塊無法正確呈現</span></span><span class="sxs-lookup"><span data-stu-id="c493b-718"><span>Checkboxes could not render correctly</span></span></span></div>


- <div><span data-ttu-id="c493b-719"><span>無法儲存對圖表大小的變更</span></span><span class="sxs-lookup"><span data-stu-id="c493b-719"><span>Changes to a chart size could not be saved</span></span></span></div>


- <div><span data-ttu-id="c493b-720"><span>某些 VBA 函數會針對新的圖表類型傳回錯誤</span></span><span class="sxs-lookup"><span data-stu-id="c493b-720"><span>Some VBA functions would return an error on new chart types</span></span></span></div>


- <div><span data-ttu-id="c493b-721"><span>[選取資料來源] 對話方塊上的部分欄位並未區分大小寫</span></span><span class="sxs-lookup"><span data-stu-id="c493b-721"><span>Select Data Source dialogs were not case sensitive for some fields</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="c493b-722">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-722">PowerPoint</span></span>

- <div><span data-ttu-id="c493b-723"><span>無法儲存對圖表大小的變更</span></span><span class="sxs-lookup"><span data-stu-id="c493b-723"><span>Changes to a chart size could not be saved</span></span></span></div>


### <a name="publisher"></a><span data-ttu-id="c493b-724">Publisher</span><span class="sxs-lookup"><span data-stu-id="c493b-724">Publisher</span></span>

- <div><span data-ttu-id="c493b-725"><span>圖形可能會顯示在圖形框線以外</span></span><span class="sxs-lookup"><span data-stu-id="c493b-725"><span>Shapes could appear outside of the graphics border</span></span></span></div>


### <a name="word"></a><span data-ttu-id="c493b-726">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-726">Word</span></span>

- <div><span data-ttu-id="c493b-727"><span>圖形可能會顯示在圖形框線以外</span></span><span class="sxs-lookup"><span data-stu-id="c493b-727"><span>Shapes could appear outside of the graphics border</span></span></span></div>


- <div><span data-ttu-id="c493b-728"><span>醒目提示文字可能很困難</span></span><span class="sxs-lookup"><span data-stu-id="c493b-728"><span>Highlighting text could be challenging</span></span></span></div>


- <div><span data-ttu-id="c493b-729"><span>可能已防止使用者在編輯器中瀏覽個別項目</span></span><span class="sxs-lookup"><span data-stu-id="c493b-729"><span>A user could be prevented from navigating to an individual item in the editor</span></span></span></div>


- <div><span data-ttu-id="c493b-730"><span>可能不會將文法或拼寫錯誤醒目提示</span></span><span class="sxs-lookup"><span data-stu-id="c493b-730"><span>Grammar or spelling errors might not be highlighted</span></span></span></div>


- <div><span data-ttu-id="c493b-731"><span>無法儲存對圖表大小的變更</span></span><span class="sxs-lookup"><span data-stu-id="c493b-731"><span>Changes to a chart size could not be saved</span></span></span></div>


- <div><span data-ttu-id="c493b-732"><span>將格式設定套用到 @ 提及之後，可能會防止開啟連絡人卡片</span></span><span class="sxs-lookup"><span data-stu-id="c493b-732"><span>A contact card could be prevented from opening after apply formatting to an @ mention</span></span></span></div>


- <div><span data-ttu-id="c493b-733"><span>已解決使用者無法儲存 Word、Excel 和 PowerPoint 文件的問題。&nbsp;此問題會影響建立新檔案並在按一下 [儲存] 圖示或按 Ctrl + S 之後帶出 [另存成模型對話方塊]&quot;&quot; 選項的使用者。</span></span><span class="sxs-lookup"><span data-stu-id="c493b-733"><span>Resolvedan issue where users may be unable to save Word, Excel, and PowerPoint documents.&nbsp; This issue affects users that create a new file and bring up the &quot;Save as Model Dialog&quot; option after clicking on the Save icon or pressing Ctrl + S.</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="c493b-734">Office 套件</span><span class="sxs-lookup"><span data-stu-id="c493b-734">Office Suite</span></span>

- <div><span data-ttu-id="c493b-735"><span>在 Windows 7 上使用圖形時的效能問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-735"><span>Performance issue when using Shapes on Windows 7</span></span></span></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1911-october-18"></a><span data-ttu-id="c493b-737">版本 1911：10 月 18 日</span><span class="sxs-lookup"><span data-stu-id="c493b-737">Version 1911: October 18</span></span>
<span data-ttu-id="c493b-738">*版本 1911 (組建 12209.20010)*</span><span class="sxs-lookup"><span data-stu-id="c493b-738">*Version 1911 (Build 12209.20010)*</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="c493b-740">功能更新</span><span class="sxs-lookup"><span data-stu-id="c493b-740">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="c493b-741">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-741">Outlook</span></span>

- <span data-ttu-id="c493b-742">**傳送可存取的郵件給最需要它的人員：** Outlook 會顯示郵件提示，協助確保將您的內容傳送給偏好可存取內容的使用者時可供其存取</span><span class="sxs-lookup"><span data-stu-id="c493b-742">**Send accessible mail to those who need it most:** Outlook will display a mail tip to help you ensure that your content is accessible when sending to a user who prefers accessible content</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-743">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-743">PowerPoint</span></span>

- <span data-ttu-id="c493b-744">**最佳化您的簡報：** 協助工具檢查程式可協助您以螢幕閱讀器為中心，在投影片上排列物件。</span><span class="sxs-lookup"><span data-stu-id="c493b-744">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c493b-745">Office 套件</span><span class="sxs-lookup"><span data-stu-id="c493b-745">Office Suite</span></span>

- <span data-ttu-id="c493b-746">**上傳中心將由需要注意的檔案體驗取代：**「上傳中心」將由會顯示在 Office 應用程式的 [檔案] > [開啟] 下的「需要注意的檔案」體驗取代。</span><span class="sxs-lookup"><span data-stu-id="c493b-746">**The Upload Center is being replaced by the Files Needing Attention experience:** The Upload Center is being replaced by the Files Needing Attention experience that will show up inside the Office applications under File > Open.</span></span> <span data-ttu-id="c493b-747">相較於上傳中心，此新體驗更為現代化、整合且更不具侵入性。</span><span class="sxs-lookup"><span data-stu-id="c493b-747">This new experience is more modern, integrated, and less intrusive compared to the Upload Center.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a><span data-ttu-id="c493b-750">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="c493b-750">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="c493b-751">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-751">Excel</span></span>

- <div><span data-ttu-id="c493b-752"><span>解決使用自動調整來調整列高時，核取方塊控制項可能收縮的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-752"><span>Resolved an issue where check box controls could shrink when using autofit to adjust row height</span></span></span></div>


- <div><span data-ttu-id="c493b-753"><span>解決捲動後選取儲存格時，可能導致選取錯誤的儲存格的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-753"><span>Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="c493b-754">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-754">Outlook</span></span>

- <div><span data-ttu-id="c493b-755"><span>發現簽署具有數位簽署附件的電子郵件時，可能導致數位簽章遭到破壞的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-755"><span>Identified an issue which could cause digital signatures to become broken when signing an e-mail with a digitally signed attachment</span></span></span></div>


- <div><span data-ttu-id="c493b-756"><span>發現在將長檔名拖放至郵件內文時，長檔名遭到截斷的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-756"><span>Identified an issue where long filenames were truncated after draging and droping to the message body</span></span></span></div>


- <div><span data-ttu-id="c493b-757">發現當功能區設定為自動隱藏時，搜尋方塊可能消失的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-757">Identified an issue where the search box could disappear when the ribbon is set to hide automatically</span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="c493b-758">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-758">PowerPoint</span></span>

- <div><span data-ttu-id="c493b-759"><span>發現投影片預覽的長寬比未正確鎖定/解除鎖定的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-759"><span>Identified an issuewhere aspect ratio for the slide preview was not being properly locked/unlocked</span></span></span></div>

### <a name="project"></a><span data-ttu-id="c493b-760">Project</span><span class="sxs-lookup"><span data-stu-id="c493b-760">Project</span></span>

- <div><span data-ttu-id="c493b-761">發現在執行更新工作時，若輸入記事，可能不會保留記事的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-761">Identified an issue where notes might not persist if entered while doing update tasks</span></span><br></div>


- <div><span data-ttu-id="c493b-762">發現檔案可能遭某個使用者鎖定，但不會在錯誤訊息中顯示任何使用者名稱的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-762">Identified an issue where a file could be locked by a user, but no username would be displayed in the error message</span></span></div>


- <div><span data-ttu-id="c493b-763"><span>發現在開啟唯讀專案時，使用者可能會收到數個訊息的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-763"><span>Identified an issue where users could get several messages when opening a read-only project</span></span></span></div>


### <a name="word"></a><span data-ttu-id="c493b-764">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-764">Word</span></span>

- <div><span data-ttu-id="c493b-765"><span>發現使用螢幕閱讀器檢視註解時的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-765"><span>Identified an issue when viewing comments while using a screen reader</span></span></span></div>


- <div><span data-ttu-id="c493b-766"><span>發現將某些評論錯誤地識別為拼寫或文法評論的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-766"><span>Identified an issue where some critiques were misidentified as being spelling or grammar critiques</span></span></span></div>


- <div><span data-ttu-id="c493b-767"><span>發現新留言對話方塊有時候未取得焦點的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-767"><span>Identified an issue where a new comment dialog could sometimes not obtain focus</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="c493b-768">Office 套件</span><span class="sxs-lookup"><span data-stu-id="c493b-768">Office Suite</span></span>

- <div><span data-ttu-id="c493b-769"><span>我們已修正了&quot;另一個安裝正在進行中&quot;的不正確錯誤訊息，可能導致無法升級的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-769"><span>We fixed an issue where an upgrade could be prevented by a incorrect error message of &quot;Another install in progress&quot;</span></span></span></div>

- <div><span data-ttu-id="c493b-770"><span>發現可能會影響從本機資源同步至雲端資源的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-770"><span>Identified an issue which could affect syncing from a local resource to a cloud resource</span></span></span></div>

- <div><span data-ttu-id="c493b-771"><span>發現歡迎訊息含有無效連結的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-771"><span>Identified an issue where a welcome message contained an invalid link</span></span></span></div>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1910-october-11"></a><span data-ttu-id="c493b-773">版本 1910：10 月 11 日</span><span class="sxs-lookup"><span data-stu-id="c493b-773">Version 1910: October 11</span></span>
<span data-ttu-id="c493b-774">*版本 1910 (組建 12130.20112)*</span><span class="sxs-lookup"><span data-stu-id="c493b-774">*Version 1910 (Build 12130.20112)*</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)
[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)
[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a><span data-ttu-id="c493b-778">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="c493b-778">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="c493b-779">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-779">Excel</span></span>

- <div><span data-ttu-id="c493b-780">解決從 OneDrive 以物件形式插入檔案的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-780">Resolved an issue in inserting files as object from OneDrive</span></span></div>


- <div><span data-ttu-id="c493b-781">解決無法將超連結格式正確套用至部分內容的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-781">Resolved an issue where the hyperlink format could not be properly applied to some content</span></span></div>


- <div><span data-ttu-id="c493b-782">解決含有結構化絕對參考的公式可能無法正確調整的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-782">Resolved an issue where formulas containing structured absolute references may be adjusted incorrectly</span></span></div>


- <div><span data-ttu-id="c493b-783">解決在目前的 Office 版本中開啟在舊版 Office 中建立的活頁簿時，可能導致 Excel 懸置的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-783">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office</span></span></div>


- <div><span data-ttu-id="c493b-784">解決從 Excel 複製的內容，在貼上到其他 Office 應用程式時，可能無法正確顯示的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-784">Resolved an issue where content copied from Excel could appear incorrect when pasted into other Office applications</span></span></div>


- <div><span data-ttu-id="c493b-785">修正以校正使用圖表範本插入圖表時，預覽中使用的色彩</span><span class="sxs-lookup"><span data-stu-id="c493b-785">Fix to correct colors used in previews when inserting charts using chart templates</span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="c493b-786">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-786">PowerPoint</span></span>

- <div><span data-ttu-id="c493b-787">已發現 ARC 裝置在 AirSpace WinComp 下執行時，可能會遺失連線的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-787">Identified an issue where ARC Devices could lose connection when running under AirSpace WinComp</span></span></div>


### <a name="word"></a><span data-ttu-id="c493b-788">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-788">Word</span></span>

- <div><span data-ttu-id="c493b-789">解決從 OneDrive 以物件形式插入檔案的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-789">Resolved an issue in inserting files as object from OneDrive</span></span></div>


- <div><span data-ttu-id="c493b-790">改善復原步驟，以<span>修正會導致從電子郵件執行緒中刪除圖形內容的問題。&nbsp;</span></span><span class="sxs-lookup"><span data-stu-id="c493b-790">Improved our recovery steps to f<span>ix an issue that caused graphical content to get deleted from email threads.&nbsp;</span></span></span></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1910-october-04"></a><span data-ttu-id="c493b-792">版本 1910：10 月 4 日</span><span class="sxs-lookup"><span data-stu-id="c493b-792">Version 1910: October 04</span></span>
<span data-ttu-id="c493b-793">*版本 1910 (組建 12126.20000)*</span><span class="sxs-lookup"><span data-stu-id="c493b-793">*Version 1910 (Build 12126.20000)*</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="c493b-795">功能更新</span><span class="sxs-lookup"><span data-stu-id="c493b-795">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="c493b-796">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-796">Excel</span></span>

- <span data-ttu-id="c493b-797">**資料視覺化工具增益集：** 從 Excel 快速建立 Visio 流程圖。</span><span class="sxs-lookup"><span data-stu-id="c493b-797">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="c493b-798">深入了解</span><span class="sxs-lookup"><span data-stu-id="c493b-798">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a><span data-ttu-id="c493b-801">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="c493b-801">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="c493b-802">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-802">Excel</span></span>

- <div><span data-ttu-id="c493b-803"><span>我們已修正 [預覽列印] 中的列印範圍不正確的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-803"><span>We fixed an issue where the print area in print preview was not correct</span></span></span></div>


- <div><span data-ttu-id="c493b-804"><span>我們已修正可能會讓樞紐分析表在共同撰寫工作階段期間無法重新整理的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-804"><span>We fixed an issue which could have prevented pivot tables from being refreshed during a co-authoring session</span></span></span></div>


### <a name="access"></a><span data-ttu-id="c493b-805">Access</span><span class="sxs-lookup"><span data-stu-id="c493b-805">Access</span></span>

- <div><span data-ttu-id="c493b-806">我們已修正當使用共用資料庫時，使用者可能收到&quot;不一致的狀態&quot;錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-806">We fixed an issue where users could receive an &quot;inconsistent state&quot; error when using a shared database.</span></span></div>


### <a name="outlook"></a><span data-ttu-id="c493b-807">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-807">Outlook</span></span>

- <div><span data-ttu-id="c493b-808"><span>我們已修正導致郵件資料夾重複的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-808"><span>We fixed an issue which could have caused duplication of mail folders</span></span></span></div>


- <div><span data-ttu-id="c493b-809"><span>我們已修正當嘗試傳送 s/MIME 加密電子郵件時，可能會導致錯誤訊息的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-809"><span>We fixed an issue which could have caused an incorrect error message when attempting to send s/MIME encrypted e-mail</span></span></span></div>


- <div><span data-ttu-id="c493b-810"><span>我們已修正當使用者收到來自 Skype 的「未接的交談」訊息時，有時可能會導致當機的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-810"><span>We fixed an issue which could sometimes result in a crash when a user receives a 'Missed Conversation' message from Skype</span></span></span></div>


- <div><span data-ttu-id="c493b-811"><span>我們已修正可能會造成記憶體洩漏的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-811"><span>We fixed an issue which could have resulted in a memory leak</span></span></span></div>


- <div><span data-ttu-id="c493b-812"><span>我們已修正當儲存為草稿時，可能會導致寄件者名稱變更的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-812"><span>We fixed an issue which could have caused the senders name to change when saved as a draft</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="c493b-813">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-813">PowerPoint</span></span>

- <div><span></span></div><span data-ttu-id="c493b-814">我們已修正以下問題：在您將文字貼到投影片母片和投影片版面配置上的頁首/頁尾/投影片編號預留位置之後，造成 TextRanges 損壞</span><span class="sxs-lookup"><span data-stu-id="c493b-814">We fixed an issue which could cause TextRanges to become broken after pasting text into the header/footer/slide number placeholders on slide master and slide layout</span></span>


- <div><span></span></div><span data-ttu-id="c493b-815">我們已修正在使用超連結貼上文字時，無法建立超連結的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-815">We fixed an issue which prevented hyperlink from being created when pasting text with hyperlink</span></span>


- <div><span data-ttu-id="c493b-816">我們已修正造成統計資料無法正常運作的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-816">We fixed an issue which would prevent statistics from working correctly</span></span></div>


### <a name="word"></a><span data-ttu-id="c493b-817">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-817">Word</span></span>

- <div><span data-ttu-id="c493b-818"><span>我們已修正未確認字型色彩的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-818"><span>We fixed an issue where font colors were not being committed</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="c493b-819">Office 套件</span><span class="sxs-lookup"><span data-stu-id="c493b-819">Office Suite</span></span>

- <div><span data-ttu-id="c493b-820">我們已修正在停用功能後，可能會提供版本歷程記錄的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-820">We fixed an issue which could offer version history when that feature was disabled</span></span></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1910-september-27"></a><span data-ttu-id="c493b-822">版本 1910：9 月 27 日</span><span class="sxs-lookup"><span data-stu-id="c493b-822">Version 1910: September 27</span></span>
<span data-ttu-id="c493b-823">*版本：1910 (組建 12119.20000)*</span><span class="sxs-lookup"><span data-stu-id="c493b-823">*Version 1910 (Build 12119.20000)*</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)
[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)
[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a><span data-ttu-id="c493b-827">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="c493b-827">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="c493b-828">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-828">Excel</span></span>

- <div><span data-ttu-id="c493b-829"><span>我們已修正當變更系列集合時，可能會導致散佈折線圖無法正確呈現的問題。</span></span><span class="sxs-lookup"><span data-stu-id="c493b-829"><span>We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="c493b-830">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-830">Outlook</span></span>

- <div><span data-ttu-id="c493b-831"><span>我們已修正了當與共享行事曆資料夾互動時，可能會報告權限錯誤的問題。</span></span><span class="sxs-lookup"><span data-stu-id="c493b-831"><span>We fixed an issue which could have reported permission errors when interacting with shared calendar folders</span></span></span></div>


- <div><span data-ttu-id="c493b-832"><span>我們已修正了使用者可能會無法新增附件至行事曆的問題。</span></span><span class="sxs-lookup"><span data-stu-id="c493b-832"><span>We fixed an issue which could have prevented users from adding attachments to calendars</span></span></span></div>


- <div><span data-ttu-id="c493b-833"><span>我們已修正了當回覆數位簽章的郵件時，導致顯示錯誤訊息的問題。</span></span><span class="sxs-lookup"><span data-stu-id="c493b-833"><span>We fixed an issue which caused error messages to display when replying to a digitally signed message</span></span></span></div>


### <a name="word"></a><span data-ttu-id="c493b-834">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-834">Word</span></span>

- <div><span data-ttu-id="c493b-835"><span>我們已修正列印到 Deskjet 印表機時，可能會導致縮放問題的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-835"><span>We fixed an issue which could have caused scaling issues when printing to Deskjet printers</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="c493b-836">Office 套件</span><span class="sxs-lookup"><span data-stu-id="c493b-836">Office Suite</span></span>

- <div><span data-ttu-id="c493b-837"><span>我們已修正中等粗體文字樣式不正確的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-837"><span>We fixed an issue where medium bold text could be incorrectly styled</span></span></span></div>


- <div><span data-ttu-id="c493b-838"><span>我們已修正當關閉具有擱置上傳的檔案時，使用者收到不正確錯誤訊息的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-838"><span>We fixed an issue where a user could be given an incorrect error message when closing a file with a pending upload</span></span></span></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1910-september-20"></a><span data-ttu-id="c493b-840">版本 1910：9 月 20 日</span><span class="sxs-lookup"><span data-stu-id="c493b-840">Version 1910: September 20</span></span>
<span data-ttu-id="c493b-841">*版本：1910 (組建 12112.20000)*</span><span class="sxs-lookup"><span data-stu-id="c493b-841">*Version 1910 (Build 12112.20000)*</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a><span data-ttu-id="c493b-845">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="c493b-845">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="c493b-846">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-846">Excel</span></span>

- <div><span data-ttu-id="c493b-847"><span>我們已修正 Excel 有時候會在啟動時發生懸置的問題。</span></span><span class="sxs-lookup"><span data-stu-id="c493b-847"><span>We fixed an issue where Excel could sometimes hang at launch</span></span></span></div>

### <a name="outlook"></a><span data-ttu-id="c493b-848">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-848">Outlook</span></span>

- <div><span data-ttu-id="c493b-849"><span>我們大幅改善了當有大量會議室可供選擇時，會議室選取的效能。</span></span><span class="sxs-lookup"><span data-stu-id="c493b-849"><span>We significantly improved the performance of room selection when there are a large number of rooms available</span></span></span></div>


- <div><span data-ttu-id="c493b-850"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">我們已修正在 Office 365.中移轉至新式驗證時，擁有 Outlook 多個信箱的客戶無法進行信箱同步處理的問題。</span></span><span class="sxs-lookup"><span data-stu-id="c493b-850"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">We fixed an issue that can prevent mailbox sync for customers with multiple mailboxes in Outlook when migrating to modern authentication in Office 365.</span></span></span><br></div>


- <div><span data-ttu-id="c493b-851"><span>我們已修正簽章標籤中某些字元不會顯示在下拉式功能表中的問題。</span></span><span class="sxs-lookup"><span data-stu-id="c493b-851"><span>We fixed an issue where some characters in signature labels would not display in the dropdown menu</span></span></span></div>


### <a name="project"></a><span data-ttu-id="c493b-852">Project</span><span class="sxs-lookup"><span data-stu-id="c493b-852">Project</span></span>

- <div><span data-ttu-id="c493b-853"><span>我們修正了使用本機資源取代企業資源時，可能會導致當機的問題。</span></span><span class="sxs-lookup"><span data-stu-id="c493b-853"><span>We fixed an issue which could cause a crash when replacing an enterprise resource with a local resource</span></span></span></div>


### <a name="word"></a><span data-ttu-id="c493b-854">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-854">Word</span></span>

- <div><span data-ttu-id="c493b-855"><span>我們已修正 [草稿模式] 中可能會導致同步捲動無法正常運作的問題。</span></span><span class="sxs-lookup"><span data-stu-id="c493b-855"><span>We fixed an issue which could prevent synchronous scrolling from working properly in draft view</span></span></span></div>


- <div><span data-ttu-id="c493b-856">我們已修正第一次儲存文件後可能導致 [工具提示] 無法正確顯示的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-856">We fixed an issue which could prevent Tool Tips from displaying properly after saving a document for the first time</span></span></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1910-september-13"></a><span data-ttu-id="c493b-858">版本 1910：9 月 13 日</span><span class="sxs-lookup"><span data-stu-id="c493b-858">Version 1910: September 13</span></span>
<span data-ttu-id="c493b-859">*版本 1910 (組建 12105.20000)*</span><span class="sxs-lookup"><span data-stu-id="c493b-859">*Version 1910 (Build 12105.20000)*</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a><span data-ttu-id="c493b-861">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="c493b-861">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="c493b-862">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-862">Excel</span></span>

- <div><span data-ttu-id="c493b-863"><span>我們已修正使用者在部分受保護的工作表中無法貼上超連結的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-863"><span>We fixed an issue which could prevent a user from pasting hyperlinks in some protected sheets</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="c493b-864">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-864">Outlook</span></span>

- <div><span data-ttu-id="c493b-865"><span>我們已修正 UI 可能停滯在精簡檢視中的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-865"><span>We fixed an issue where the UI could get stuck in a compact view</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="c493b-866">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-866">PowerPoint</span></span>

- <div><span data-ttu-id="c493b-867"><span>我們已修正使用者可能會在列印為 PDF 時發生錯誤的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-867"><span>We fixed an issue where a user could experience an error upon printing to PDF</span></span></span></div>


### <a name="project"></a><span data-ttu-id="c493b-868">Project</span><span class="sxs-lookup"><span data-stu-id="c493b-868">Project</span></span>

- <div><span data-ttu-id="c493b-869"><span>我們已修正在摘要任務上<span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">變更工時值時，如果已啟用受保護的工作則可能會造成當機的問題</span></span></span><span class="sxs-lookup"><span data-stu-id="c493b-869"><span>We fixed an issue where <span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">changes to a work value on a summary task could cause a crash if protected work is enabled</span></span></span></span></div>


- <span data-ttu-id="c493b-870"><font size=2 style="background-color:rgb(255, 255, 255);">我們已修正可能會禁止將事件同步處理到企業行事曆功能的問題</font></span><span class="sxs-lookup"><span data-stu-id="c493b-870"><font size=2 style="background-color:rgb(255, 255, 255);">We fixed an issue which could inhibit the ability to sync events with enterprise calendars</font></span></span>


### <a name="office-suite"></a><span data-ttu-id="c493b-871">Office 套件</span><span class="sxs-lookup"><span data-stu-id="c493b-871">Office Suite</span></span>

- <div><span data-ttu-id="c493b-872"><span>我們已修正可能會導致重複警告以捨棄本機檔案版本的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-872"><span>We fixed an issue which could cause a repeated warning to discard local versions of a file</span></span></span></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1910-september-06"></a><span data-ttu-id="c493b-874">版本 1910：9 月 6 日</span><span class="sxs-lookup"><span data-stu-id="c493b-874">Version 1910: September 06</span></span>
<span data-ttu-id="c493b-875">*版本 1910 (組建 12030.20004)*</span><span class="sxs-lookup"><span data-stu-id="c493b-875">*Version 1910 (Build 12030.20004)*</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="c493b-877">功能更新</span><span class="sxs-lookup"><span data-stu-id="c493b-877">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="c493b-878">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-878">Excel</span></span>

- <span data-ttu-id="c493b-879">**準備、設定、繪圖：** 抓取 Surface 手寫筆之後, 您就可以開始繪製。</span><span class="sxs-lookup"><span data-stu-id="c493b-879">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="c493b-880">深入了解</span><span class="sxs-lookup"><span data-stu-id="c493b-880">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="powerpoint"></a><span data-ttu-id="c493b-881">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-881">PowerPoint</span></span>

- <span data-ttu-id="c493b-882">**準備、設定、繪圖：** 抓取 Surface 手寫筆之後, 您就可以開始繪製。</span><span class="sxs-lookup"><span data-stu-id="c493b-882">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="c493b-883">深入了解</span><span class="sxs-lookup"><span data-stu-id="c493b-883">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="word"></a><span data-ttu-id="c493b-884">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-884">Word</span></span>

- <span data-ttu-id="c493b-885">**準備、設定、繪圖：** 抓取 Surface 手寫筆之後, 您就可以開始繪製。</span><span class="sxs-lookup"><span data-stu-id="c493b-885">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="c493b-886">深入了解</span><span class="sxs-lookup"><span data-stu-id="c493b-886">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a><span data-ttu-id="c493b-889">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="c493b-889">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="c493b-890">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-890">Excel</span></span>

- <div><span data-ttu-id="c493b-891"><span>我們已修正可能會導致功能區中的字型名稱與正在使用的字型不同的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-891"><span>We fixed an issue which could cause the font name in the ribbon to be different from the font being used</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="c493b-892">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-892">Outlook</span></span>

- <div><span data-ttu-id="c493b-893"><span>我們已修正當 Internet Explorer 中的受限制網站停用受保護模式時，可能會導致 Outlook 不適當的資源消耗的問題。</span></span><span class="sxs-lookup"><span data-stu-id="c493b-893"><span>We fixed an issue that could result in inappropriate resource consumption by Outlook when Protected Mode is disabled for Restricted Sites in Internet Explorer</span></span></span></div>


- <div><span data-ttu-id="c493b-894"><span>我們已修正當貼上 ANSI 原始碼的文字時, 有時可能會導致顯示 Unicode 字元的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-894"><span>We fixed an issue which could sometimes cause Unicode characters to appear when pasting text from an ANSI source</span></span></span></div>


- <div><span data-ttu-id="c493b-895"><span>我們已修正有些使用者在群組排程檢視中會不正確地顯示為離線的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-895"><span>We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span></span></div>


### <a name="word"></a><span data-ttu-id="c493b-896">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-896">Word</span></span>

- <div><span data-ttu-id="c493b-897"><span>我們已修正表格格式設定可能遺失的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-897"><span>We fixed an issue where table formatting could be lost</span></span></span></div>


- <div><span data-ttu-id="c493b-898"><span>我們已修正導致 Ctrl+V 鍵盤快速鍵中斷的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-898"><span>We fixed an issue which could break the ctrl+v keyboard shortcut</span></span></span></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1909-august-30"></a><span data-ttu-id="c493b-900">版本 1909：8 月 30 日</span><span class="sxs-lookup"><span data-stu-id="c493b-900">Version 1909: August 30</span></span>
<span data-ttu-id="c493b-901">*版本 1909 (組建 12026.20000)*</span><span class="sxs-lookup"><span data-stu-id="c493b-901">*Version 1909 (Build 12026.20000)*</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="c493b-903">功能更新</span><span class="sxs-lookup"><span data-stu-id="c493b-903">Feature updates</span></span>

### <a name="access"></a><span data-ttu-id="c493b-904">Access</span><span class="sxs-lookup"><span data-stu-id="c493b-904">Access</span></span>

- <span data-ttu-id="c493b-905">**快速尋找連結資料表：** 新的搜尋方塊可讓您輕鬆尋找連結資料表。</span><span class="sxs-lookup"><span data-stu-id="c493b-905">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-906">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-906">PowerPoint</span></span>

- <span data-ttu-id="c493b-907">**將圖例另存成 SVG：** 將圖表、圖形或其他圖例另存成可縮放向量圖形，其可調整大小，且不損失影像品質。</span><span class="sxs-lookup"><span data-stu-id="c493b-907">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="c493b-908">深入了解</span><span class="sxs-lookup"><span data-stu-id="c493b-908">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a><span data-ttu-id="c493b-911">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="c493b-911">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="c493b-912">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-912">Excel</span></span>

- <div><span data-ttu-id="c493b-913"><span>我們已修正&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">敏感度</span>的 keytip &nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">與其他 keytip 相衝突的問題。</span></span></span><span class="sxs-lookup"><span data-stu-id="c493b-913"><span>We fixed an issue where the keytip for&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">Sensitivity </span>was&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">conflicting with another keytip.</span></span></span></span></div>

- <div><span data-ttu-id="c493b-914"><span>我們已修正在嘗試儲存的同時使用共用活頁簿時所發生的問題。</span></span><span class="sxs-lookup"><span data-stu-id="c493b-914"><span>We fixed an issue that occurred while working on a shared workbook when trying to save.</span></span></span></div>

- <div><span data-ttu-id="c493b-915"><span>我們已修正 Excel 只列出位於「\Excel\Add-in Manager」登錄值中前 16 個增益集的問題。<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></span><span class="sxs-lookup"><span data-stu-id="c493b-915"><span>We fixed an issue where Excel only lists the first 16 addins located in the '\Excel\Add-in Manager' registry values.<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></span></span></div>


- <div><span data-ttu-id="c493b-916"><span>我們已修正 Frequency 函數會傳回不正確結果的問題。</span></span><span class="sxs-lookup"><span data-stu-id="c493b-916"><span>We fixed an issue where the function Frequency() returns incorrect results.</span></span></span></div>


- <div><span data-ttu-id="c493b-917"><span>我們已大幅提升透過色彩篩選的效能。</span></span><span class="sxs-lookup"><span data-stu-id="c493b-917"><span>We have significantly improved the performance of filtering by color.</span></span></span></div>


- <div><span data-ttu-id="c493b-918"><span>我們已修正 Surface 使用者移動滑鼠可能解譯為按一下滑鼠事件的問題。</span></span><span class="sxs-lookup"><span data-stu-id="c493b-918"><span>We fixed an issue for Surface users where moving the mouse could be interpreted as a mouse click event.</span></span></span></div>


- <div><span data-ttu-id="c493b-919"><span>我們已修正在 [尋找/取代] 對話方塊中鍵盤無法瀏覽的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-919"><span>We fixed an issue which prevented keyboard navigation in the Find/Replace dialog</span></span></span></div>


- <div><span data-ttu-id="c493b-920"><span>我們已修正某些字型名稱無法正確顯示的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-920"><span>We fixed an issue where the name of some fonts were not displayed correctly</span></span></span></div>


- <div><span data-ttu-id="c493b-921"><span>我們已修正 CSV 無法顯示為支援的檔案類型的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-921"><span>We fixed an issue which prevented CSV from appearing as a supported file type</span></span></span></div>


### <a name="access"></a><span data-ttu-id="c493b-922">Access</span><span class="sxs-lookup"><span data-stu-id="c493b-922">Access</span></span>

- <div><span data-ttu-id="c493b-923">我們已修正當使用共用資料庫時，使用者可能收到&quot;不一致的狀態&quot;錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-923">We fixed an issue where users could receive an &quot;inconsistent state&quot; error when using a shared database.</span></span></div>


- <div><span data-ttu-id="c493b-924"><span>我們已修正可能導致日期選擇器在不該出現時出現的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-924"><span>We fixed an issue which could cause the date picker to appear when it shouldn't</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="c493b-925">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-925">Outlook</span></span>

- <div><span data-ttu-id="c493b-926"><span>我們已修正部分 POP3 使用者無法顯示 HTML 內容的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-926"><span>We fixed an issue which prevented HTML content from appearing for some POP3 users</span></span></span></div>


- <div><span data-ttu-id="c493b-927"><span>我們已修正在無法使用的環境中工作時，從連絡人卡片的溢位功能表移除非功能性「Planner」連結的問題。</span></span><span class="sxs-lookup"><span data-stu-id="c493b-927"><span>We fixed an issue to remove non-functional 'Planner' link from the overflow menu in the contact card when working in environments where it is not available.</span></span></span></div>

### <a name="onenote"></a><span data-ttu-id="c493b-928">OneNote</span><span class="sxs-lookup"><span data-stu-id="c493b-928">OneNote</span></span>

- <div><span data-ttu-id="c493b-929"><span>我們已修正 &nbsp;OneNote 背景同步處理有時候會竊取焦點的問題。</span></span><span class="sxs-lookup"><span data-stu-id="c493b-929"><span>We fixed an issue where&nbsp;OneNote background sync was sometimes stealing focus.</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="c493b-930">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-930">PowerPoint</span></span>

- <div><span data-ttu-id="c493b-931"><span>我們已修正會影響 3D 盤旋的旋轉方向的問題。</span></span><span class="sxs-lookup"><span data-stu-id="c493b-931"><span>We fixed an issue which would affect the rotation orientation of a 3D Turntable.</span></span></span></div>

- <div><span data-ttu-id="c493b-932"><span>我們已修正如果超連結包含特殊字元便無法運作的問題。</span></span><span class="sxs-lookup"><span data-stu-id="c493b-932"><span>We fixed an issue which prevented some hyperlinks from working if they contained special characters.</span></span></span></div>

- <div><span data-ttu-id="c493b-933"><span>我們已修正會造成的同時開啟多個註解窗格的問題。</span></span><span class="sxs-lookup"><span data-stu-id="c493b-933"><span>We fixed an issue which caused multiple comment panes to open at the same time.</span></span></span></div>

### <a name="project"></a><span data-ttu-id="c493b-934">Project</span><span class="sxs-lookup"><span data-stu-id="c493b-934">Project</span></span>

- <div><span data-ttu-id="c493b-935"><span>我們已修正在列印團隊規劃檢視之後可能會導致當機的問題。</span></span><span class="sxs-lookup"><span data-stu-id="c493b-935"><span>We fixed an issue which could sometimes cause a crash after printing a Team Planner view.</span></span></span></div>

### <a name="word"></a><span data-ttu-id="c493b-936">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-936">Word</span></span>

- <div><span data-ttu-id="c493b-937">我們已<span>修正直排文字方塊中多位元組字元在閱讀檢視中顯示重疊的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-937">We f<span>ixed an issue where multi-byte characters in vertical text box are shown overlapped in reading view.</span></span><br></span></div>

- <div><span data-ttu-id="c493b-938"><span>我們&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">已修正當使用者在增益集中採取動作時，找不到日文明信片和賀卡相關增益集資源的問題。</span></span></span><span class="sxs-lookup"><span data-stu-id="c493b-938"><span>We&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">fixed an issue where Japanese post card and greeting card related addin resources are not found when the user takes action in the addin wizard.</span></span></span></span></div>

- <div><span data-ttu-id="c493b-939"><span>我們已修正在受保護的檢視中的標題列使用者介面會造成問題的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-939"><span>We fixed an issue which could cause issues with the Title Bar User Interface when in Protected View</span></span></span></div>

### <a name="office-suite"></a><span data-ttu-id="c493b-940">Office 套件</span><span class="sxs-lookup"><span data-stu-id="c493b-940">Office Suite</span></span>

- <div><span data-ttu-id="c493b-941"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"> 我們已修正當您在含有一般圖形和連接器圖形的選擇上變更圖形時的損毀檔案問題。</span></span></span><span class="sxs-lookup"><span data-stu-id="c493b-941"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"> We fixed a corrupt file issue when you Change Shape on a selection that contains both a normal shape and a connector shape.</span></span></span></span></div>

- <div><span data-ttu-id="c493b-942"><span>我們已修正<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">從多個外部顯示器使用固定/解除固定時會造成問題的問題。</span></span></span><span class="sxs-lookup"><span data-stu-id="c493b-942"><span>We fixed an issue that <span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">caused a problem in applications when using dock/undock from multiple external displays. </span></span></span></span></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="august-23-2019br"></a><span data-ttu-id="c493b-944">**2019 年 8 月 23 日**</span><span class="sxs-lookup"><span data-stu-id="c493b-944">**August 23, 2019**</span></span><br/>
<span data-ttu-id="c493b-945">版本 1909 (組建 12015.20004)</span><span class="sxs-lookup"><span data-stu-id="c493b-945">Version 1909 (Build 12015.20004)</span></span><br/>



## <a name="non-security-updates"></a><span data-ttu-id="c493b-946">非安全性更新：</span><span class="sxs-lookup"><span data-stu-id="c493b-946">Non-security updates:</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-947">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-947">Excel</span></span>

- <div><span data-ttu-id="c493b-948"><span>我們已大幅改善刪除合併儲存格的資料行的效能</span></span><span class="sxs-lookup"><span data-stu-id="c493b-948"><span>We significantly improved the performance of deleting columns with merged cells</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="c493b-949">Office 套件</span><span class="sxs-lookup"><span data-stu-id="c493b-949">Office Suite</span></span>

- <div><span data-ttu-id="c493b-950"><span>我們已修正在瀏覽器中檢視時，部分的 Unicode 字元可能會無法顯示的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-950"><span>We fixed an issue which could prevent some Unicode characters from being displayed when viewed in a browser</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="c493b-951">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-951">Outlook</span></span>

- <div><span data-ttu-id="c493b-952"><span>我們已修正可能會無法儲存檔案到 WebDAV 的位置的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-952"><span>We fixed an issue which could have prevented files from being saved to a WebDAV location</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="c493b-953">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-953">PowerPoint</span></span>

- <div><span data-ttu-id="c493b-954"><span>我們已修正當使用者點擊一個註解，但可能是另一個註解被選取的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-954"><span>We fixed an issue where a user would click on one comment, but another comment would be selected</span></span></span></div>





## <a name="august-16-2019br"></a><span data-ttu-id="c493b-955">**2019 年 8 月 16 日**</span><span class="sxs-lookup"><span data-stu-id="c493b-955">**August 16, 2019**</span></span><br/>
<span data-ttu-id="c493b-956">版本 1909 (組建 12013.20000)</span><span class="sxs-lookup"><span data-stu-id="c493b-956">Version 1909 (Build 12013.20000)</span></span><br/>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="c493b-957">PowerPoint 功能更新：</span><span class="sxs-lookup"><span data-stu-id="c493b-957">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="c493b-958">**列印講義上的投影片編號：** 投影片編號會自動包含在講義上。</span><span class="sxs-lookup"><span data-stu-id="c493b-958">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="c493b-959">由您決定將其保留或關閉。</span><span class="sxs-lookup"><span data-stu-id="c493b-959">Leave them on, turn them off, it's all up to you.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="c493b-960">非安全性更新：</span><span class="sxs-lookup"><span data-stu-id="c493b-960">Non-security updates:</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-961">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-961">Excel</span></span>

- <div><span data-ttu-id="c493b-962"><span>我們已修正可能會導致 AutoSave 自動開啟的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-962"><span>We fixed an issue which could cause AutoSave to become enabled</span></span></span></div>


- <div><span data-ttu-id="c493b-963">我們已修正可能會導致不正確計算儲存格高度的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-963">We fixed an issue which could result in cell heights being measured inaccurately</span></span></div>


### <a name="office-suite"></a><span data-ttu-id="c493b-964">Office 套件</span><span class="sxs-lookup"><span data-stu-id="c493b-964">Office Suite</span></span>

- <div><span data-ttu-id="c493b-965"><span>我們已修正了一個問題，將能大幅改善註解功能的效能</span></span><span class="sxs-lookup"><span data-stu-id="c493b-965"><span>We fixed an issue which significantly improves the performance of the Comments feature</span></span></span></div>


- <div><span data-ttu-id="c493b-966"><span>我們已修正搜尋時使用方向鍵可能會造成當機的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-966"><span>We fixed an issue which could cause a crash when using arrow keys while in search</span></span></span></div>


- <div><span data-ttu-id="c493b-967"><span>我們已修正如果將 @ 符號放在特定字元後，可能會無法使用 @ 提及的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-967"><span>We fixed an issue which could prevent an @ mention if the @ symbol was placed after certain characters</span></span></span></div>


- <div><span data-ttu-id="c493b-968"><span>我們已修正在刪除 @ 提及時，可能會導致當機的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-968"><span>We fixed an issue which could sometimes cause a crash when deleting @ mentions</span></span></span></div>


- <div><span data-ttu-id="c493b-969"><span>我們已修正無法在註解卡正確顯示 Emoji 的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-969"><span>We fixed an issue which prevented emojis from displaying correctly in comment cards</span></span></span></div>


- <div><span data-ttu-id="c493b-970"><span>我們已修正使用中​的​剪貼簿​​有時可能會導致當機的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-970"><span>We fixed an issue with Active Clipboard which could sometimes result in a crash</span></span></span></div>


- <div><span data-ttu-id="c493b-971"><span>我們已修正可能會導致快速存取工具列按鈕停止運作的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-971"><span>We fixed an issue which could cause the Quick Access Toolbar buttons to stop working</span></span></span></div>


- <div><span data-ttu-id="c493b-972"><span>我們已修正無法讓文件格式設定預覽切換到背景的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-972"><span>We fixed an issue which could prevent the Document Formatting Preview from switching to the background</span></span></span></div>

### <a name="onenote"></a><span data-ttu-id="c493b-973">OneNote</span><span class="sxs-lookup"><span data-stu-id="c493b-973">OneNote</span></span>

- <span data-ttu-id="c493b-974">我們已修正當 Office 佈景主題設為黑色，區段下拉式清單中的區段名稱顯示為空白的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-974">We fixed an issue where the names of sections appear blank in the section dropdown list when Office Theme is set to Black.</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-975">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-975">Outlook</span></span>

- <div><span data-ttu-id="c493b-976"><span>我們已修正在傳送​​事件時可能會導致 Outlook 重複獲取和失去焦點的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-976"><span>We fixed an issue with Send Events which could cause Outlook to repeatedly gain and lose focus</span></span></span></div>


- <div><span data-ttu-id="c493b-977"><span>我們已修正無法從工作資料夾的捷徑張貼回覆的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-977"><span>We fixed an issue which prevented the Post Reply to Folder shortcut from working</span></span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="c493b-978">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-978">PowerPoint</span></span>

- <div><span data-ttu-id="c493b-979"><span>我們已修正受保護的檢視有時候可能會在合作時造成問題的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-979"><span>We fixed an issue with Protected View which could sometimes cause problems when collaborating</span></span></span></div>


- <div><span data-ttu-id="c493b-980"><span>我們已修正可能無法正確顯示註解窗格中工作的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-980"><span>We fixed an issue which could prevent tasks in comment panes from displaying properly</span></span></span></div>


- <div><span data-ttu-id="c493b-981"><span>我們已修正插入新投影片時可能會造成當機的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-981"><span>We fixed an issue which could cause a crash when inserting new slides</span></span></span></div>


### <a name="user-lifecycle"></a><span data-ttu-id="c493b-982">使用者生命週期</span><span class="sxs-lookup"><span data-stu-id="c493b-982">User Lifecycle</span></span>

- <div><span data-ttu-id="c493b-983"><span>我們已修正有時候可能會導致訂閱功能消失的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-983"><span>We fixed an issue which could sometimes result in subscription features disappearing</span></span></span></div>


### <a name="word"></a><span data-ttu-id="c493b-984">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-984">Word</span></span>

- <div><span data-ttu-id="c493b-985"><span>我們已修正如果超連結包含特定字元，則超連結可能會中斷的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-985"><span>We fixed an issue where hyperlinks could be broken if the hyperlink contained certain characters</span></span></span></div>


- <div><span data-ttu-id="c493b-986"><span>我們已修正在檢視影像註解時，影像可能會調整至不正確大小的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-986"><span>We fixed an issue where images could be improperly sized when viewing a comment for that image</span></span></span></div>


- <div><span data-ttu-id="c493b-987"><span>我們已修正項目符號清單下拉式功能表有時可能會導致當機的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-987"><span>We fixed an issue with the Bullet List drop down menu which could sometimes result in a crash</span></span></span></div>





## <a name="august-09-2019br"></a><span data-ttu-id="c493b-988">**2019 年 8 月 9 日**</span><span class="sxs-lookup"><span data-stu-id="c493b-988">**August 09, 2019**</span></span><br/>
<span data-ttu-id="c493b-989">版本 1909 (組建 12001.20000)</span><span class="sxs-lookup"><span data-stu-id="c493b-989">Version 1909 (Build 12001.20000)</span></span><br/>

### <a name="excel-feature-updates"></a><span data-ttu-id="c493b-990">Excel 功能更新：</span><span class="sxs-lookup"><span data-stu-id="c493b-990">Excel Feature updates:</span></span>

- <span data-ttu-id="c493b-991">**共同作業變得更容易：** 共同撰寫的增強功能表示，使用條件式格式設定、儲存格樣式等等時，您的變更會與共同作業者的變更順暢地合併。</span><span class="sxs-lookup"><span data-stu-id="c493b-991">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>


- <span data-ttu-id="c493b-992">**搜尋並享受：** 我們對插入圖示新增了搜尋，讓您易於找到您要的圖示。</span><span class="sxs-lookup"><span data-stu-id="c493b-992">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="c493b-993">而當您選取時，[插入] 按鈕會告知您已經選取的數量。</span><span class="sxs-lookup"><span data-stu-id="c493b-993">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="office-suite-feature-updates"></a><span data-ttu-id="c493b-994">Office 套件功能更新：</span><span class="sxs-lookup"><span data-stu-id="c493b-994">Office Suite Feature updates:</span></span>

- <span data-ttu-id="c493b-995">**新的 Office 應用程式圖示：** 重新設計的應用程式圖示，可反映簡單、功能強大且智慧型的 Office 體驗</span><span class="sxs-lookup"><span data-stu-id="c493b-995">**New Office app icons:** Redesigned app icons to reflect the simple, powerful, and intelligent experiences of Office</span></span>


### <a name="outlook-feature-updates"></a><span data-ttu-id="c493b-996">Outlook 功能更新：</span><span class="sxs-lookup"><span data-stu-id="c493b-996">Outlook Feature updates:</span></span>

- <span data-ttu-id="c493b-997">**抵禦攻擊的進階防護：** 使用 Office 365 進階威脅防護，您會受到保護，不受電子郵件主旨、附加的郵件、簽署的郵件、網路路徑內超連結的攻擊。</span><span class="sxs-lookup"><span data-stu-id="c493b-997">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>


- <span data-ttu-id="c493b-998">**搜尋並享受：** 我們對插入圖示新增了搜尋，讓您易於找到您要的圖示。</span><span class="sxs-lookup"><span data-stu-id="c493b-998">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="c493b-999">而當您選取時，[插入] 按鈕會告知您已經選取的數量。</span><span class="sxs-lookup"><span data-stu-id="c493b-999">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="c493b-1000">PowerPoint 功能更新：</span><span class="sxs-lookup"><span data-stu-id="c493b-1000">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="c493b-1001">**搜尋並享受：** 我們對插入圖示新增了搜尋，讓您易於找到您要的圖示。</span><span class="sxs-lookup"><span data-stu-id="c493b-1001">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="c493b-1002">而當您選取時，[插入] 按鈕會告知您已經選取的數量。</span><span class="sxs-lookup"><span data-stu-id="c493b-1002">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="word-feature-updates"></a><span data-ttu-id="c493b-1003">Word 功能更新：</span><span class="sxs-lookup"><span data-stu-id="c493b-1003">Word Feature updates:</span></span>

- <span data-ttu-id="c493b-1004">**其他人更快速看到您的變更：** 共同撰寫增強功能表示，共同作業者可較以往更快速看到您的變更。</span><span class="sxs-lookup"><span data-stu-id="c493b-1004">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>


- <span data-ttu-id="c493b-1005">**搜尋並享受：** 我們對插入圖示新增了搜尋，讓您易於找到您要的圖示。</span><span class="sxs-lookup"><span data-stu-id="c493b-1005">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="c493b-1006">而當您選取時，[插入] 按鈕會告知您已經選取的數量。</span><span class="sxs-lookup"><span data-stu-id="c493b-1006">And when you're selecting, the Insert button tells you how many you've picked.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="c493b-1007">非安全性更新：</span><span class="sxs-lookup"><span data-stu-id="c493b-1007">Non-security updates:</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-1008">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-1008">Outlook</span></span>

- <div><span data-ttu-id="c493b-1009"><span>我們已修正會導致會議收件者在取消會議後收到兩次通知的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-1009"><span>We fixed an issue which caused meeting recipients to receive two notifications after a meeting was cancelled</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="c493b-1010">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-1010">PowerPoint</span></span>

- <div><span data-ttu-id="c493b-1011"><span>我們已修正當使用者對圖形與圖示選取 [無外框] 或 [無填滿] 時會導致損毀的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-1011"><span>We fixed an issue which could cause a crash when the user selected No Outline or No Fill for Shapes and Icons</span></span></span></div>





## <a name="august-02-2019br"></a><span data-ttu-id="c493b-1012">**2019 年 8 月 2 日**</span><span class="sxs-lookup"><span data-stu-id="c493b-1012">**August 02, 2019**</span></span><br/>
<span data-ttu-id="c493b-1013">版本 1908 (組建 11929.20002)</span><span class="sxs-lookup"><span data-stu-id="c493b-1013">Version 1908 (Build 11929.20002)</span></span><br/>

### <a name="excel-feature-updates"></a><span data-ttu-id="c493b-1014">Excel 功能更新：</span><span class="sxs-lookup"><span data-stu-id="c493b-1014">Excel Feature updates:</span></span>

- <span data-ttu-id="c493b-1015">**轉換檔案，以改善協助工具功能：** 將您的檔案升級為現代格式，讓所有人更容易存取。</span><span class="sxs-lookup"><span data-stu-id="c493b-1015">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="c493b-1016">**將敏感度標籤套用至您的文件**：將敏感度標籤套用至您的檔案和電子郵件，使其符合貴組織的資訊保護原則。</span><span class="sxs-lookup"><span data-stu-id="c493b-1016">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="outlook-feature-updates"></a><span data-ttu-id="c493b-1017">Outlook 功能更新：</span><span class="sxs-lookup"><span data-stu-id="c493b-1017">Outlook Feature updates:</span></span>

- <span data-ttu-id="c493b-1018">**將敏感度標籤套用至您的文件**：將敏感度標籤套用至您的檔案和電子郵件，使其符合貴組織的資訊保護原則。</span><span class="sxs-lookup"><span data-stu-id="c493b-1018">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="c493b-1019">PowerPoint 功能更新：</span><span class="sxs-lookup"><span data-stu-id="c493b-1019">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="c493b-1020">**轉換檔案，以改善協助工具功能：** 將您的檔案升級為現代格式，讓所有人更容易存取。</span><span class="sxs-lookup"><span data-stu-id="c493b-1020">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="c493b-1021">**將敏感度標籤套用至您的文件**：將敏感度標籤套用至您的檔案和電子郵件，使其符合貴組織的資訊保護原則。</span><span class="sxs-lookup"><span data-stu-id="c493b-1021">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="word-feature-updates"></a><span data-ttu-id="c493b-1022">Word 功能更新：</span><span class="sxs-lookup"><span data-stu-id="c493b-1022">Word Feature updates:</span></span>

- <span data-ttu-id="c493b-1023">**轉換檔案，以改善協助工具功能：** 將您的檔案升級為現代格式，讓所有人更容易存取。</span><span class="sxs-lookup"><span data-stu-id="c493b-1023">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="c493b-1024">**用其他方式表達：** 當您想要以不同方式表達時，「重寫」功能可以幫助您。</span><span class="sxs-lookup"><span data-stu-id="c493b-1024">**Say it another way:** When you want to say it differently, Rewrite is there to help.</span></span> <span data-ttu-id="c493b-1025">重寫提供其他不同方式來表達您的詞彙。</span><span class="sxs-lookup"><span data-stu-id="c493b-1025">Rewrite offers alternatives for finessing your phrases.</span></span>


- <span data-ttu-id="c493b-1026">**將敏感度標籤套用至您的文件**：將敏感度標籤套用至您的檔案和電子郵件，使其符合貴組織的資訊保護原則。</span><span class="sxs-lookup"><span data-stu-id="c493b-1026">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="c493b-1027">非安全性更新：</span><span class="sxs-lookup"><span data-stu-id="c493b-1027">Non-security updates:</span></span>

### <a name="access"></a><span data-ttu-id="c493b-1028">Access</span><span class="sxs-lookup"><span data-stu-id="c493b-1028">Access</span></span>
- <span data-ttu-id="c493b-1029">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1029">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-1030">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-1030">Excel</span></span>

- <div><span data-ttu-id="c493b-1031"><span>我們已修正了列印至 PDF 時，&quot;重複所有標籤&quot;看起來像已套用的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-1031"><span>We fixed an issue which made it appear as though &quot;repeat all labels&quot; was applied when printing to a PDF</span></span></span></div>

### <a name="office-suite"></a><span data-ttu-id="c493b-1032">Office 套件</span><span class="sxs-lookup"><span data-stu-id="c493b-1032">Office Suite</span></span>

- <div><span data-ttu-id="c493b-1033"><span>我們已修正了使用者可能無法從桌面開啟文件的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-1033"><span>We fixed an issue which could have prevented users from opening a document from the desktop</span></span></span></div>

- <div><span data-ttu-id="c493b-1034"><span>我們已修正了&quot;另一個安裝正在進行中&quot;的不正確錯誤訊息，可能導致無法升級的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-1034"><span>We fixed an issue where an upgrade could be prevented by a incorrect error message of &quot;Another install in progress&quot;</span></span></span></div>

- <div><span data-ttu-id="c493b-1035"><span>我們已修正了安全性更新安裝後，使用者可能會看到錯誤訊息的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-1035"><span>We fixed an issue where a user could see error messages when security updates are installed</span></span></span></div>

- <div><span data-ttu-id="c493b-1036"><span>我們已修正了可能會造成游標消失的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-1036"><span>We fixed an issue which could cause the cursor to disappear</span></span></span></div>

- <div><span data-ttu-id="c493b-1037"><span>我們已修正了使用者可能預設前往 [繪圖] 索引標籤而不是 [常用] 索引標籤的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-1037"><span>We fixed an issue where a user could be defaulted to the draw tab instead of the home tab</span></span></span></div>

- <div><span data-ttu-id="c493b-1038"><span>我們已修正了大型樹狀檢視可能會導致當機的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-1038"><span>We fixed an issue where large tree views could result in a crash</span></span></span></div>

### <a name="outlook"></a><span data-ttu-id="c493b-1039">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-1039">Outlook</span></span>

- <div></div><span data-ttu-id="c493b-1040"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">我們已修正了可能導致系統重複提示輸入密碼的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-1040"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">We fixed an issue that can cause repeated password prompts</span></span></span>

- <div><span data-ttu-id="c493b-1041"><span>我們已修正了可能無法正確查詢電子郵件地址的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-1041"><span>We fixed an issue which could prevent an email address from being queried correctly</span></span></span></div>

- <div><span data-ttu-id="c493b-1042"><span>我們已修正了可能導致使用者無法開啟由舊版 Outlook 建立之行事曆項目的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-1042"><span>We fixed an issue which could prevent users from opening calendar items created by legacy versions of Outlook</span></span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="c493b-1043">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-1043">PowerPoint</span></span>

- <div><span data-ttu-id="c493b-1044"><span>我們已修正了部分動畫無法開始的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-1044"><span>We fixed an issue which could prevent some animations from starting</span></span></span></div>

### <a name="project"></a><span data-ttu-id="c493b-1045">Project</span><span class="sxs-lookup"><span data-stu-id="c493b-1045">Project</span></span>
- <span data-ttu-id="c493b-1046">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1046">Various performance and stability fixes</span></span>

### <a name="word"></a><span data-ttu-id="c493b-1047">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-1047">Word</span></span>

- <div><span data-ttu-id="c493b-1048"><span>我們已修正了註解的回覆以錯誤順序顯示的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-1048"><span>We fixed an issue where replies to comments could appear out of order</span></span></span></div>

- <div><span data-ttu-id="c493b-1049"><span>我們已修正了在某些情況下，會顯示提示而非顯示註解的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-1049"><span>We fixed an issue where in some situations, hints would be displayed instead of comments</span></span></span></div>

- <div><span data-ttu-id="c493b-1050"><span>我們已修正了當使用者嘗試新增註解時，可能會顯示 [修訂窗格] 的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-1050"><span>We fixed an issue where the Revisions Pane could display when the user tried to add a new comment</span></span></span></div>

- <div><span data-ttu-id="c493b-1051"><span>我們已修正了可能無法顯示 [復原] 下拉式清單的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-1051"><span>We fixed an issue which could prevent the undo dropdown list from appearing</span></span></span></div>

- <div><span data-ttu-id="c493b-1052"><span>我們已修正了有時無法新增註解的問題</span></span><span class="sxs-lookup"><span data-stu-id="c493b-1052"><span>We fixed an issue which could prevent comments from being added</span></span></span></div>


## <a name="july-26-2019"></a><span data-ttu-id="c493b-1053">2019 年 7 月 26 日</span><span class="sxs-lookup"><span data-stu-id="c493b-1053">July 26, 2019</span></span>
<span data-ttu-id="c493b-1054">版本 1908 (組建 11916.20000)</span><span class="sxs-lookup"><span data-stu-id="c493b-1054">Version 1908 (build 11916.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="c493b-1055">新功能：</span><span class="sxs-lookup"><span data-stu-id="c493b-1055">What's New:</span></span>

### <a name="word-excel-powerpoint"></a><span data-ttu-id="c493b-1056">Word、Excel、PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-1056">Word, Excel, PowerPoint</span></span>

#### <a name="create-more-accessible-pdfs"></a><span data-ttu-id="c493b-1057">建立更易於存取的 PDF</span><span class="sxs-lookup"><span data-stu-id="c493b-1057">Create more accessible PDFs</span></span>

<span data-ttu-id="c493b-1058">建立 PDF 檔案，然後協助工具檢查程式會指出在儲存之前應該修正的協助工具問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-1058">Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="c493b-1059">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="c493b-1059">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="c493b-1060">全部</span><span class="sxs-lookup"><span data-stu-id="c493b-1060">All</span></span>

- <span data-ttu-id="c493b-1061">我們修正了 Office 更新後 Office 文件類型關聯和圖示有時會中斷的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1061">We fixed an issue where file type association and icons for Office could sometimes break after an Office Update</span></span>

### <a name="word"></a><span data-ttu-id="c493b-1062">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-1062">Word</span></span> 
- <span data-ttu-id="c493b-1063">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1063">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-1064">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-1064">Excel</span></span>
- <span data-ttu-id="c493b-1065">我們修正了移動圖表有時會導致當機的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1065">We fixed an issue where moving a chart could sometimes result in a crash</span></span>
- <span data-ttu-id="c493b-1066">我們修正了在更改圖表類型後從 Chart 物件獲取 Workbook 物件有時會導致錯誤的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1066">We fixed an issue where to get Workbook object from Chart object after changing chart types could sometimes result in an error</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-1067">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-1067">PowerPoint</span></span>
- <span data-ttu-id="c493b-1068">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1068">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-1069">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-1069">Outlook</span></span>
- <span data-ttu-id="c493b-1070">我們修正了在簡化版的功能區中，停用的控制項有時不會呈現灰色的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1070">We fixed an issue where in simplified ribbon, a disabled control could sometimes not be greyed out in the ribbon</span></span>

### <a name="access"></a><span data-ttu-id="c493b-1071">Access</span><span class="sxs-lookup"><span data-stu-id="c493b-1071">Access</span></span>
- <span data-ttu-id="c493b-1072">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1072">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="c493b-1073">Project</span><span class="sxs-lookup"><span data-stu-id="c493b-1073">Project</span></span>
- <span data-ttu-id="c493b-1074">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1074">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-19-2019"></a><span data-ttu-id="c493b-1075">2019 年 7 月 19 日</span><span class="sxs-lookup"><span data-stu-id="c493b-1075">July 19, 2019</span></span>
<span data-ttu-id="c493b-1076">版本 1908 (組建 11911.20000)</span><span class="sxs-lookup"><span data-stu-id="c493b-1076">Version 1908 (build 11911.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="c493b-1077">新功能：</span><span class="sxs-lookup"><span data-stu-id="c493b-1077">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="c493b-1078">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-1078">Word</span></span>

#### <a name="learn-what-acronyms-mean-when-you-read-in-word-online"></a><span data-ttu-id="c493b-1079">了解在 Word Online 中閱讀時，縮略字代表的意義</span><span class="sxs-lookup"><span data-stu-id="c493b-1079">Learn what Acronyms mean when you read in Word Online</span></span>

<span data-ttu-id="c493b-1080">當您遇到縮略字時，我們會嘗試使用組織的資料來定義縮略字。</span><span class="sxs-lookup"><span data-stu-id="c493b-1080">When you encounter an Acronym, we'll try to define it using data from within your organization.</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="c493b-1081">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="c493b-1081">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="c493b-1082">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-1082">Word</span></span> 
- <span data-ttu-id="c493b-1083">我們已修正 BookMarkEnd 標記遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-1083">We fixed an issue which BookMarkEnd tag was missing.</span></span>
- <span data-ttu-id="c493b-1084">我們已修正字型選項會在使用者輸入特殊字元時變更的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-1084">We fixed an issue where the font selection could change while the user was typing special characters</span></span>
- <span data-ttu-id="c493b-1085">我們已修正有時候可能會造成新註解卡片有空白回覆的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-1085">We fixed an issue which could sometimes cause blank replies to a new comment card</span></span>
- <span data-ttu-id="c493b-1086">我們已修正共用電子郵件時可能會造成格式遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-1086">We fixed an issue which could cause formatting to be lost when sharing an email</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-1087">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-1087">Excel</span></span>
- <span data-ttu-id="c493b-1088">我們已修正大範圍的陣列有時可能會造成當機的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-1088">We fixed an issue where an array with a large range could sometimes cause a crash</span></span>
- <span data-ttu-id="c493b-1089">我們已大幅改善從篩選範圍複製資料的效能。</span><span class="sxs-lookup"><span data-stu-id="c493b-1089">We significantly improved the performance of copying data from filtered ranges</span></span>
- <span data-ttu-id="c493b-1090">我們已修正如果檔案名稱包含特殊字元便無法開啟某些檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-1090">We fixed an issue which prevented some files from opening if the filenames contained special characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-1091">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-1091">PowerPoint</span></span>
- <span data-ttu-id="c493b-1092">我們已修正 PowerPoint 中預設未選取新建區段的區段名稱問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-1092">We fixed an issue where section name was not selected by default for newly created section in PowerPoint.</span></span>
- <span data-ttu-id="c493b-1093">我們已修正使用 4:3 顯示器時 UI 變得難以使用的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-1093">We fixed an issue which could cause the UI to become difficult to use when using a 4:3 display</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-1094">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-1094">Outlook</span></span>
- <span data-ttu-id="c493b-1095">我們已修正無法列出可用會議室的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-1095">We fixed an issue which could prevent available rooms from being listed</span></span>
- <span data-ttu-id="c493b-1096">我們已修正部分 POP3 使用者無法使用 HTML 格式的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-1096">We fixed an issue which prevented HTML formatting for some POP3 users</span></span>

### <a name="access"></a><span data-ttu-id="c493b-1097">Access</span><span class="sxs-lookup"><span data-stu-id="c493b-1097">Access</span></span>
- <span data-ttu-id="c493b-1098">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1098">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="c493b-1099">Project</span><span class="sxs-lookup"><span data-stu-id="c493b-1099">Project</span></span>
- <span data-ttu-id="c493b-1100">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1100">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-12-2019"></a><span data-ttu-id="c493b-1101">2019 年 7 月 12 日</span><span class="sxs-lookup"><span data-stu-id="c493b-1101">July 12, 2019</span></span>
<span data-ttu-id="c493b-1102">版本 1907 (組建 11901.20038)</span><span class="sxs-lookup"><span data-stu-id="c493b-1102">Version 1907 (build 11901.20038)</span></span>

## <a name="whats-new"></a><span data-ttu-id="c493b-1103">新功能：</span><span class="sxs-lookup"><span data-stu-id="c493b-1103">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-1104">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-1104">PowerPoint</span></span>
 
#### <a name="use-ink-replay-in-your-presentations"></a><span data-ttu-id="c493b-1105">在簡報中使用筆跡重播</span><span class="sxs-lookup"><span data-stu-id="c493b-1105">Use ink replay in your presentations</span></span>
 
<span data-ttu-id="c493b-1106">套用 PowerPoint 的筆跡重播動畫，使簡報的表達和溝通更加生動。</span><span class="sxs-lookup"><span data-stu-id="c493b-1106">Apply a replay animation for ink in PowerPoint to express and communicate more in presentations.</span></span> 

## <a name="notable-fixes"></a><span data-ttu-id="c493b-1107">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="c493b-1107">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="c493b-1108">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-1108">Word</span></span> 
- <span data-ttu-id="c493b-1109">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1109">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-1110">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-1110">Excel</span></span>
- <span data-ttu-id="c493b-1111">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1111">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-1112">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-1112">PowerPoint</span></span>
- <span data-ttu-id="c493b-1113">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1113">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-1114">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-1114">Outlook</span></span>
- <span data-ttu-id="c493b-1115">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1115">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="c493b-1116">Access</span><span class="sxs-lookup"><span data-stu-id="c493b-1116">Access</span></span>
- <span data-ttu-id="c493b-1117">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1117">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="c493b-1118">Project</span><span class="sxs-lookup"><span data-stu-id="c493b-1118">Project</span></span>
- <span data-ttu-id="c493b-1119">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1119">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-5-2019"></a><span data-ttu-id="c493b-1120">2019 年 7 月 5 日</span><span class="sxs-lookup"><span data-stu-id="c493b-1120">July 5, 2019</span></span>
<span data-ttu-id="c493b-1121">版本 1907 (組建 11901.20018)</span><span class="sxs-lookup"><span data-stu-id="c493b-1121">Version 1907 (build 11901.20018)</span></span>

## <a name="whats-new"></a><span data-ttu-id="c493b-1122">新功能：</span><span class="sxs-lookup"><span data-stu-id="c493b-1122">What's New:</span></span>

### <a name="word-excel-powerpoint"></a><span data-ttu-id="c493b-1123">Word、Excel、PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-1123">Word, Excel, PowerPoint</span></span>

#### <a name="sketchy-shapes"></a><span data-ttu-id="c493b-1124">素描形狀！</span><span class="sxs-lookup"><span data-stu-id="c493b-1124">Sketchy Shapes!</span></span>

<span data-ttu-id="c493b-1125">仍在編寫簡報的草稿嗎？</span><span class="sxs-lookup"><span data-stu-id="c493b-1125">In the middle of drafting a presentation?</span></span> <span data-ttu-id="c493b-1126">套用素描樣式來顯示您仍在處理文件。</span><span class="sxs-lookup"><span data-stu-id="c493b-1126">Apply the sketchy style to show that you're still working on it.</span></span> <span data-ttu-id="c493b-1127">此功能可在不將物件轉換成自由格式、手繪形狀的情況下，為您的物件賦與個人風格。</span><span class="sxs-lookup"><span data-stu-id="c493b-1127">It gives a personal touch to your objects without turning it into a free form, hand-drawn shapes.</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-1128">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-1128">Excel</span></span>

- <span data-ttu-id="c493b-1129">**更快速共用檔案**：不需開啟檔案，即可從最近使用清單直接共用您的檔案。</span><span class="sxs-lookup"><span data-stu-id="c493b-1129">**Faster file sharing**: Share your documents right from the recently used list without having to open the file.</span></span>
### <a name="powerpoint"></a><span data-ttu-id="c493b-1130">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-1130">PowerPoint</span></span>

- <span data-ttu-id="c493b-1131">**[在講義上列印投影片編號] 設定已移至 [列印] 功能表，以易於存取：** 選取講義版面配置時，可在 [列印] > [整頁模式] 下拉式清單中找到它。</span><span class="sxs-lookup"><span data-stu-id="c493b-1131">**The setting to Print Slide Numbers in Handouts has been moved to the Print Menu for easier access:**  Find it in the Print > Print Layout dropdown when a Handout layout is selected.</span></span> <span data-ttu-id="c493b-1132">這也會使得每個簡報的設定易於切換。</span><span class="sxs-lookup"><span data-stu-id="c493b-1132">This also allows the setting to be easily toggled per presentation.</span></span> [<span data-ttu-id="c493b-1133">深入了解</span><span class="sxs-lookup"><span data-stu-id="c493b-1133">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="c493b-1134">**更快速共用檔案：** 不需開啟檔案，即可從最近使用清單直接共用您的檔案。</span><span class="sxs-lookup"><span data-stu-id="c493b-1134">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

### <a name="word"></a><span data-ttu-id="c493b-1135">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-1135">Word</span></span>

- <span data-ttu-id="c493b-1136">**更快速共用檔案：** 不需開啟檔案，即可從最近使用清單直接共用您的檔案。</span><span class="sxs-lookup"><span data-stu-id="c493b-1136">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="c493b-1137">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="c493b-1137">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="c493b-1138">全部</span><span class="sxs-lookup"><span data-stu-id="c493b-1138">All</span></span>
- <span data-ttu-id="c493b-1139">我們已大幅提高功能區 KeyTip 的效能</span><span class="sxs-lookup"><span data-stu-id="c493b-1139">We significantly improved the performance of Ribbon KeyTips</span></span>
- <span data-ttu-id="c493b-1140">我們已修正無法正常顯示 [查看即將推出的新功能] 方塊的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1140">We fixed an issue which prevented the "See what's coming soon" dialog from being displayed properly</span></span>
- <span data-ttu-id="c493b-1141">我們已修正可能會導致共同撰寫圖庫飛出視窗中的相片排列錯誤的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1141">We fixed an issue which could cause Photos to be misaligned in the Co-auth Gallery flyout</span></span>

### <a name="word"></a><span data-ttu-id="c493b-1142">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-1142">Word</span></span> 
- <span data-ttu-id="c493b-1143">我們已修正有時無法加入新註解的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1143">We fixed an issue which could sometimes prevent new comments from being added</span></span>
- <span data-ttu-id="c493b-1144">我們已修正表格有時可能會造成當機的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1144">We fixed an issue where tables could sometimes cause a crash</span></span>
- <span data-ttu-id="c493b-1145">我們已修正無效的資料有時可能會新增至合併列印結尾的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1145">We fixed an issue where invalid data could sometimes be added to the end of a mail merge</span></span>
- <span data-ttu-id="c493b-1146">我們已修正可能會導致不正確呈現部分 LaTeX 方程式的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1146">We fixed an issue which could cause some LaTeX equations to render incorrectly</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-1147">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-1147">Excel</span></span>
- <span data-ttu-id="c493b-1148">我們已修正變更圖表類型有時可能會導致執行階段例外狀況的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1148">We fixed an issue where changing chart types could sometimes result in a runtime exception</span></span>
- <span data-ttu-id="c493b-1149">我們已修正開啟多個視窗時會顯示不正確功能區的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1149">We fixed an issue where the incorrect ribbon could be displayed when multiple windows were open</span></span>
- <span data-ttu-id="c493b-1150">我們已修正巨集開啟活頁簿的第二個執行個體時可能會造成錯誤的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1150">We fixed an issue which could cause an error when a macro opened a second instance of a workbook</span></span>
- <span data-ttu-id="c493b-1151">我們已修正開啟或建立活頁簿，或切換使用不同的活頁簿時可能會造成當機的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1151">We fixed an issue which could cause a crash when opening or creating a workbook, or switching between workbooks</span></span>
- <span data-ttu-id="c493b-1152">我們已修正使用者無法在 Teams 中開啟透過 Word 建立之 PDF 的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1152">We fixed an issue preventing users from opening a PDF created from Word in Teams</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-1153">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-1153">PowerPoint</span></span>
- <span data-ttu-id="c493b-1154">我們已修正匯出成 PDF 時會降低圖表品質的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1154">We fixed an issue which would degrade the quality of a chart when exported to a pdf</span></span>
- <span data-ttu-id="c493b-1155">我們已修正工具提示無法顯示到達中心之距離的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1155">We fixed an issue which prevented a tooltip indicating the distance to center from displaying</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-1156">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-1156">Outlook</span></span>
- <span data-ttu-id="c493b-1157">我們已修正有時可能會導致 [磁碟已滿] 錯誤訊息無法顯示的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1157">We fixed an issue which could sometimes prevent a Disk Full error to be displayed</span></span>
- <span data-ttu-id="c493b-1158">我們已修正更新會議邀請時可能會導致附件重複的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1158">We fixed an issue which could cause attachments to become duplicated when updating a meeting request</span></span>

### <a name="access"></a><span data-ttu-id="c493b-1159">Access</span><span class="sxs-lookup"><span data-stu-id="c493b-1159">Access</span></span>
- <span data-ttu-id="c493b-1160">我們已修正某些查詢無法傳回大整數值的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1160">We fixed an issue which prevented some queries from returning large integer values</span></span>
- <span data-ttu-id="c493b-1161">我們已修正可能會引起 SQL 文字方塊無法編輯的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1161">We fixed an issue which could make the sql textbox uneditable</span></span>
- <span data-ttu-id="c493b-1162">我們已修正工具提示可能難以在某些高 DPI 顯示器上查看的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1162">We fixed an issue where tooltips could be difficult to see on some High DPI displays</span></span>

### <a name="project"></a><span data-ttu-id="c493b-1163">Project</span><span class="sxs-lookup"><span data-stu-id="c493b-1163">Project</span></span>
- <span data-ttu-id="c493b-1164">我們已修正在新工作中可能會導致旗標值無法編輯的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1164">We fixed an issue which could cause flag values to become uneditable in new tasks</span></span>
- <span data-ttu-id="c493b-1165">我們已修正可能導致狀態更新在 [工作分派] 和 [任務] 上不正確地設定 [實際開始日期] 的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1165">We fixed an issue which could cause a status update to improperly set Actual Start Date on Assignments and Tasks</span></span>
- <span data-ttu-id="c493b-1166">我們已修正可能會導致部分資源錯誤顯示為過度分派的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1166">We fixed an issue which could cause some resources to incorreclty appear overallocated</span></span>
- <span data-ttu-id="c493b-1167">我們已修正新增延隔時間、小數點分隔符號是逗號，以及連線至伺服器時，工作相依性新增方法可能會出錯的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1167">We fixed an issue where the TaskDependencies Add method could fail when Lag is added, the decimal separator is a comma, and when connected to a server</span></span>
- <span data-ttu-id="c493b-1168">我們已修正透過 CSOM 更新本機自訂欄位的查閱表格值可能會損毀 PCS 的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1168">We fixed an issue where updating local custom field lookup table values via CSOM could crash PCS</span></span>
- <span data-ttu-id="c493b-1169">我們已修正總工時值示內如果含有小數點時將不正確顯示的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1169">We fixed an issue where the total work values may appear incorrect if they contain a decimal</span></span>

</BR></BR>

## <a name="june-28-2019"></a><span data-ttu-id="c493b-1170">2019 年 6 月 28 日</span><span class="sxs-lookup"><span data-stu-id="c493b-1170">June 28, 2019</span></span>
<span data-ttu-id="c493b-1171">版本 1907 (組建 11819.20002)</span><span class="sxs-lookup"><span data-stu-id="c493b-1171">Version 1907 (build 11819.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="c493b-1172">新功能：</span><span class="sxs-lookup"><span data-stu-id="c493b-1172">What's New:</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-1173">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-1173">Excel</span></span>

- <span data-ttu-id="c493b-1174">**使用 Power Query 的增強功能快速撰寫程式碼：** 使用自動完成和語法色彩快速完成程式碼。</span><span class="sxs-lookup"><span data-stu-id="c493b-1174">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="c493b-1175">同時輕鬆探索函數、資料行和參數</span><span class="sxs-lookup"><span data-stu-id="c493b-1175">Easily discover functions, columns, and parameters, too</span></span>

- <span data-ttu-id="c493b-1176">**聯結類似欄位上的表格：** 在比較合併表格的欄位時，取得及轉換 (Power Query) 現在具有近似文字比對邏輯 (也稱為模糊比對)。</span><span class="sxs-lookup"><span data-stu-id="c493b-1176">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span>

### <a name="word"></a><span data-ttu-id="c493b-1177">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-1177">Word</span></span>

- <span data-ttu-id="c493b-1178">**共同撰寫的增強功能**：增強共同撰寫時的可靠性。</span><span class="sxs-lookup"><span data-stu-id="c493b-1178">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>
 
### <a name="word-excel-powerpoint-and-visio"></a><span data-ttu-id="c493b-1179">Word、Excel、PowerPoint 和 Visio</span><span class="sxs-lookup"><span data-stu-id="c493b-1179">Word, Excel, PowerPoint, and Visio</span></span>

#### <a name="recommended-documents"></a><span data-ttu-id="c493b-1180">建譯的文件</span><span class="sxs-lookup"><span data-stu-id="c493b-1180">Recommended Documents</span></span>

<span data-ttu-id="c493b-1181">透過建議您的相關活動尋找文件。</span><span class="sxs-lookup"><span data-stu-id="c493b-1181">Find documents with relevant activity recommended to you.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="c493b-1182">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="c493b-1182">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="c493b-1183">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-1183">Word</span></span> 
- <span data-ttu-id="c493b-1184">我們已修正可能會導致有些 .DOC 檔案無法開啟的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1184">We fixed an issue which could prevent some .DOC files from opening</span></span>
- <span data-ttu-id="c493b-1185">我們已修正可能會導致註解無法正確載入的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1185">We fixed an issue which could have prevented comments from loading properly</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-1186">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-1186">Excel</span></span>
- <span data-ttu-id="c493b-1187">我們已改善 Power Query 的效能</span><span class="sxs-lookup"><span data-stu-id="c493b-1187">We improved the performance of Power Queries</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-1188">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-1188">PowerPoint</span></span>
- <span data-ttu-id="c493b-1189">我們已修正在 Surface 裝置上使用手寫筆可能會導致螢幕閃爍的相關問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1189">We fixed an issue related to using a pen on a Surface device which could cause the screen to flicker</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-1190">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-1190">Outlook</span></span>
- <span data-ttu-id="c493b-1191">我們已修正將約會轉換成會議時可能會變更約會的空閒/忙碌狀態問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1191">We fixed an issue which could change the free/busy status of an appointment when converted to a meeting</span></span>
- <span data-ttu-id="c493b-1192">我們已修正電子郵件有臨時範本的保護時會顯示錯誤範本和描述的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1192">We fixed an issue where the wrong template and description would be displayed when an e-mail was protected with an ad-hoc template</span></span>

### <a name="access"></a><span data-ttu-id="c493b-1193">Access</span><span class="sxs-lookup"><span data-stu-id="c493b-1193">Access</span></span>
- <span data-ttu-id="c493b-1194">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1194">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="c493b-1195">Project</span><span class="sxs-lookup"><span data-stu-id="c493b-1195">Project</span></span>
- <span data-ttu-id="c493b-1196">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1196">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-21-2019"></a><span data-ttu-id="c493b-1197">2019 年 6 月 21 日</span><span class="sxs-lookup"><span data-stu-id="c493b-1197">June 21, 2019</span></span>
<span data-ttu-id="c493b-1198">版本 1907 (組建 11815.20002)</span><span class="sxs-lookup"><span data-stu-id="c493b-1198">Version 1907 (build 11815.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="c493b-1199">新功能：</span><span class="sxs-lookup"><span data-stu-id="c493b-1199">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-1200">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-1200">Outlook</span></span>

#### <a name="dark-mode-for-black-theme-in-outlook-desktop"></a><span data-ttu-id="c493b-1201">Outlook 電腦版中用於黑色佈景主題的深色模式</span><span class="sxs-lookup"><span data-stu-id="c493b-1201">Dark Mode for Black Theme in Outlook Desktop</span></span>

<span data-ttu-id="c493b-1202">使用深色模式時，黑色佈景主題中的使用者現在也會在讀取電子郵件時看到讀取窗格具有深色背景，並在撰寫電子郵件時擁有深色背景的撰寫體驗。</span><span class="sxs-lookup"><span data-stu-id="c493b-1202">With dark mode, users in black theme will now also see the reading pane with a dark background when reading emails, and the compose experience with a dark background when writing emails.</span></span> <span data-ttu-id="c493b-1203">如果使用者想要預覽郵件在淺色背景下的外觀，在讀取窗格或功能區中有太陽/月亮切換。</span><span class="sxs-lookup"><span data-stu-id="c493b-1203">There is a sun/moon toggle on the reading pane and in the ribbon in case users want to preview what the message looks like with a light background instead.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="c493b-1204">開始使用：</span><span class="sxs-lookup"><span data-stu-id="c493b-1204">Getting Started:</span></span>

1. <span data-ttu-id="c493b-1205">開啟黑色佈景主題，深色模式預設就會處於開啟狀態。</span><span class="sxs-lookup"><span data-stu-id="c493b-1205">Turn on black theme and dark mode will be on by default.</span></span>
2. <span data-ttu-id="c493b-1206">使用月亮/太陽切換 (在讀取窗格和功能區中) 可為不在深色模式的使用者預覽郵件的外觀</span><span class="sxs-lookup"><span data-stu-id="c493b-1206">Use the moon/sun toggle (in the reading pane and in the ribbon) to preview what the message looks like for users not in dark mode</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="c493b-1207">可嘗試使用的案例</span><span class="sxs-lookup"><span data-stu-id="c493b-1207">Scenarios to Try</span></span>

1. <span data-ttu-id="c493b-1208">在深色模式中讀取電子郵件。</span><span class="sxs-lookup"><span data-stu-id="c493b-1208">Read emails in dark mode.</span></span> <span data-ttu-id="c493b-1209">如果您無法讀取某些項目，請使用讀取窗格中的太陽切換來切換為淺色背景。</span><span class="sxs-lookup"><span data-stu-id="c493b-1209">If you are unable to read something, use the sun toggle in the Reading Pane to switch to a light background.</span></span> 
2. <span data-ttu-id="c493b-1210">在深色模式中撰寫電子郵件。</span><span class="sxs-lookup"><span data-stu-id="c493b-1210">Compose emails in dark mode.</span></span> <span data-ttu-id="c493b-1211">使用功能區中的太陽切換，預覽您的郵件使用淺色背景時的外觀。</span><span class="sxs-lookup"><span data-stu-id="c493b-1211">Preview what your message will look like with a light background by using the sun toggle in the ribbon.</span></span> 

<span data-ttu-id="c493b-1212">如果您遇到未正確顯示的任何電子郵件，請將其 (當作附件) 傳送到 OutlookDarkModeFail@service.microsoft.com</span><span class="sxs-lookup"><span data-stu-id="c493b-1212">If you encounter any emails that don't render properly, please send them (as an attachment) to OutlookDarkModeFail@service.microsoft.com</span></span>

#### <a name="get-location-suggestions"></a><span data-ttu-id="c493b-1213">取得位置建議</span><span class="sxs-lookup"><span data-stu-id="c493b-1213">Get location suggestions</span></span>

<span data-ttu-id="c493b-1214">開始輸入，Outlook 就會尋找符合的位置。</span><span class="sxs-lookup"><span data-stu-id="c493b-1214">Start typing and Outlook will look for matching locations.</span></span>

<span data-ttu-id="c493b-1215">建立約會和會議時，這適用於 [位置] 欄位。</span><span class="sxs-lookup"><span data-stu-id="c493b-1215">This applies to the Location field when creating Appointments and Meetings.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="c493b-1216">開始使用：</span><span class="sxs-lookup"><span data-stu-id="c493b-1216">Getting Started:</span></span>

- <span data-ttu-id="c493b-1217">在 Outlook 中的 O365 或 Outlook.com 行事曆上，建立約會或會議。</span><span class="sxs-lookup"><span data-stu-id="c493b-1217">Create an Appointment or Meeting on an O365 or Outlook.com calendar in Outlook.</span></span> 
- <span data-ttu-id="c493b-1218">按一下 [位置] 欄位，然後開始輸入…</span><span class="sxs-lookup"><span data-stu-id="c493b-1218">Click into the Location field and start typing…</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="c493b-1219">可嘗試使用的案例</span><span class="sxs-lookup"><span data-stu-id="c493b-1219">Scenarios to Try</span></span>

<span data-ttu-id="c493b-1220">當您將會議室加入至會議時，按一下 [位置] 欄位，而不是使用會議室尋找工具增益集或通訊錄。</span><span class="sxs-lookup"><span data-stu-id="c493b-1220">When adding a conference room to a meeting, click into Location field, rather than using Room Finder add-in or Address Book.</span></span>
<span data-ttu-id="c493b-1221">若是在公共場所 (如餐廳、咖啡廳，甚至是牙醫診所) 的實體位置進行會議，請嘗試使用新的選擇器找到確切的位置。</span><span class="sxs-lookup"><span data-stu-id="c493b-1221">For appointments at a physical place with a public location - like a restaurant, coffee shop, or even your dentist's office - try finding the exact location using the new picker.</span></span> <span data-ttu-id="c493b-1222">如此一來，您將可以在該離開時，收到 Outlook Mobile 的通知。</span><span class="sxs-lookup"><span data-stu-id="c493b-1222">This way, you'll be able to get notified on Outlook Mobile when it's time to leave.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="c493b-1223">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="c493b-1223">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="c493b-1224">全部</span><span class="sxs-lookup"><span data-stu-id="c493b-1224">All</span></span>
- <span data-ttu-id="c493b-1225">我們已修正在離線時會導致搜尋方塊啟用的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1225">We fixed an issue which would keep the Search Box enabled while offline</span></span>

### <a name="word"></a><span data-ttu-id="c493b-1226">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-1226">Word</span></span> 
- <span data-ttu-id="c493b-1227">我們已修正有時候可能難以查看鍵盤焦點的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1227">We fixed an issue where keyboard focus could sometimes be difficult to see</span></span>
- <span data-ttu-id="c493b-1228">我們已修正貼到新文件的文字，有時候文字對齊可能會不正確的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1228">We fixed an issue where text pasted into a new document could sometimes have the wrong text alignment</span></span>
- <span data-ttu-id="c493b-1229">我們已修正將使用者的電腦暫停之後，可能防止部分使用者儲存變更的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1229">We fixed an issue which could prevent some users from saving changes after suspending their computer</span></span>
- <span data-ttu-id="c493b-1230">我們已修正在某些情況下會列印整份文件，而非所選範圍的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1230">We fixed an issue where in certain cases an entire document would be printed instead of the selected range</span></span>
- <span data-ttu-id="c493b-1231">我們已修正可能會讓註解在較小型的顯示器上難以閱讀的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1231">We fixed an issue which could make comments difficult to read on smaller displays</span></span>
- <span data-ttu-id="c493b-1232">我們已修正擷取到裝置時可能會造成當機的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1232">We fixed an issue which could cause a crash when capturing to a device</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-1233">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-1233">Excel</span></span>
- <span data-ttu-id="c493b-1234">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1234">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-1235">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-1235">PowerPoint</span></span>
- <span data-ttu-id="c493b-1236">我們已修正有時候可能難以查看鍵盤焦點的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1236">We fixed an issue where keyboard focus could sometimes be difficult to see</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-1237">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-1237">Outlook</span></span>
- <span data-ttu-id="c493b-1238">我們已修正不正確地將未啟用的增益集顯示為已啟用的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-1238">We fixed an issue which could incorrectly display an add-in as being enabled when it was not.</span></span>
- <span data-ttu-id="c493b-1239">我們已修正會在有大量原則時，使得客戶無法檢視所有保留原則的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1239">We fixed an issue which would prevent a customer from viewing all retention policies if there were a large number of them</span></span>

### <a name="access"></a><span data-ttu-id="c493b-1240">Access</span><span class="sxs-lookup"><span data-stu-id="c493b-1240">Access</span></span>
- <span data-ttu-id="c493b-1241">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1241">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="c493b-1242">Project</span><span class="sxs-lookup"><span data-stu-id="c493b-1242">Project</span></span>
- <span data-ttu-id="c493b-1243">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1243">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-14-2019"></a><span data-ttu-id="c493b-1244">2019 年 6 月 14 日</span><span class="sxs-lookup"><span data-stu-id="c493b-1244">June 14, 2019</span></span>
<span data-ttu-id="c493b-1245">版本 1907 (組建 11807.20000)</span><span class="sxs-lookup"><span data-stu-id="c493b-1245">Version 1907 (build 11807.20000)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="c493b-1246">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="c493b-1246">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="c493b-1247">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-1247">Word</span></span> 
- <span data-ttu-id="c493b-1248">我們已修正了儲存到 OneDrive 時，使用者可能無法登入的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1248">We fixed an issue which could prevent a user from signing in when saving to OneDrive</span></span>
- <span data-ttu-id="c493b-1249">我們已修正了使用者可能無法變更限制存取模式中之 SharePoint 內容的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1249">We fixed an issue where a user could be prevented from changing SharePoint properties while in restricted access mode</span></span>
- <span data-ttu-id="c493b-1250">我們已修正了調整邊界時，可能會變更頁首及頁尾內容的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1250">We fixed an issue where header and footer content could change when adjusting margins</span></span>
- <span data-ttu-id="c493b-1251">我們已修正了切換成網頁檢視時，格式設定可能會中斷的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1251">We fixed an issue where formatting could break when switching to web view</span></span>
- <span data-ttu-id="c493b-1252">我們已修正了從 SharePoint 開啟時，使用者無法使用自訂欄位的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1252">We fixed an issue which could prevent a user from using custom fields when opened from SharePoint</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-1253">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-1253">Excel</span></span>
- <span data-ttu-id="c493b-1254">我們已修正了刪除篩選集之資料列時的效能問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1254">We fixed a performance issue when deleting rows of a filtered set</span></span>
- <span data-ttu-id="c493b-1255">我們已修正了有時可能會造成滑鼠在受保護檢視模式中閃爍的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1255">We fixed an issue which could sometimes cause the mouse to flicker in protected view</span></span>
- <span data-ttu-id="c493b-1256">我們修正了刪除系列時，可能會導致當機的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1256">We fixed an issue which could have caused a crash when deleting a series</span></span>
- <span data-ttu-id="c493b-1257">我們已修正了某些使用者即使在沒有提供的情況下，仍舊有新增版本歷程記錄之選項的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1257">We fixed an issue where some users would have the option to add version history when that was not available</span></span>
- <span data-ttu-id="c493b-1258">我們已修正了使用試算表比較工具時，可能導致例外狀況的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1258">We fixed an issue which could have caused an exception when using the Spreadsheet Compare tool</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-1259">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-1259">PowerPoint</span></span>
- <span data-ttu-id="c493b-1260">我們已修正了按一下連結到 SharePoint 時，可能會發生當機的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1260">We fixed an issue where a crash could occur when clicking a link to SharePoint</span></span>
- <span data-ttu-id="c493b-1261">我們已修正了使用 Surface 手寫筆輸入時，可能將使用者切換到下一個頁面的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1261">We fixed an issue which could switch the user to the next page while typing using a Surface Pen</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-1262">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-1262">Outlook</span></span>
- <span data-ttu-id="c493b-1263">我們已修正了在某些情況下 [收件者] 欄位大於正常的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1263">We fixed an issue where in some cases the To field was larger than normal</span></span>

### <a name="access"></a><span data-ttu-id="c493b-1264">Access</span><span class="sxs-lookup"><span data-stu-id="c493b-1264">Access</span></span>
- <span data-ttu-id="c493b-1265">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1265">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="c493b-1266">Project</span><span class="sxs-lookup"><span data-stu-id="c493b-1266">Project</span></span>
- <span data-ttu-id="c493b-1267">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1267">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-7-2019"></a><span data-ttu-id="c493b-1268">2019 年 6 月 7 日</span><span class="sxs-lookup"><span data-stu-id="c493b-1268">June 7, 2019</span></span>
<span data-ttu-id="c493b-1269">版本 1907 (組建 11727.20064)</span><span class="sxs-lookup"><span data-stu-id="c493b-1269">Version 1907 (build 11727.20064)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="c493b-1270">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="c493b-1270">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="c493b-1271">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-1271">Word</span></span> 
- <span data-ttu-id="c493b-1272">我們已修正當 Word 中的自動校正設定為使句中的第一個字母均為大寫時，偶爾會當機的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1272">We fixed an issue where Word could sometimes crash when autocorrect was set to capitalize the first letter of a sentence</span></span>
- <span data-ttu-id="c493b-1273">我們已改善在 SharePoint 上編輯文件時的效能。</span><span class="sxs-lookup"><span data-stu-id="c493b-1273">We improved performance when editing a document on SharePoint</span></span>
- <span data-ttu-id="c493b-1274">我們已修正在 Adobe Illustrator 中所建立之向量影像無法正確顯示的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1274">We fixed an issue where vector-based images created in Adobe Illustrator would not display correctly</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-1275">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-1275">Excel</span></span>
- <span data-ttu-id="c493b-1276">我們已修正錄製巨集時，排序欄位有時未正確設定的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1276">We fixed an issue where sorting fields were sometimes not set correctly when recording a macro</span></span>
- <span data-ttu-id="c493b-1277">我們已修正重新計算陣列公式期間導致停止回應或當機的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1277">We fixed an issue that causes hang or crash during recalculation of an array formula</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-1278">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-1278">PowerPoint</span></span>
- <span data-ttu-id="c493b-1279">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1279">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-1280">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-1280">Outlook</span></span>
- <span data-ttu-id="c493b-1281">我們已修正內嵌附件有時未正確縮放的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1281">We fixed an issue where inline attachments would sometimes be incorrectly scaled</span></span>

### <a name="access"></a><span data-ttu-id="c493b-1282">Access</span><span class="sxs-lookup"><span data-stu-id="c493b-1282">Access</span></span>
- <span data-ttu-id="c493b-1283">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1283">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="c493b-1284">Project</span><span class="sxs-lookup"><span data-stu-id="c493b-1284">Project</span></span>
- <span data-ttu-id="c493b-1285">我們已修正固定工期的時程表有時會變更工作分派完成日期的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1285">We fixed an issue where timesheets on a fixed duration could sometimes change the assignment finish date</span></span>
- <span data-ttu-id="c493b-1286">我們已修正從舊版本中開啟專案時顯示的完成百分比值可能有誤的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1286">We fixed an issue where Percentage Complete values could be wrong when opening a project from an earlier version</span></span>

</BR></BR>

## <a name="may-31-2019"></a><span data-ttu-id="c493b-1287">2019 年 5 月 31 日</span><span class="sxs-lookup"><span data-stu-id="c493b-1287">May 31, 2019</span></span>
<span data-ttu-id="c493b-1288">版本 1906 (組建 11722.20008)</span><span class="sxs-lookup"><span data-stu-id="c493b-1288">Version 1906 (build 11722.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="c493b-1289">新功能：</span><span class="sxs-lookup"><span data-stu-id="c493b-1289">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-1290">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-1290">Outlook</span></span>

#### <a name="dialog-for-contacting-support-now-is-dockable-and-appears-on-the-right"></a><span data-ttu-id="c493b-1291">[連絡支援人員] 對話方塊現在可停駐，且會顯示在右側</span><span class="sxs-lookup"><span data-stu-id="c493b-1291">Dialog for Contacting Support now is dockable and appears on the right</span></span>

<span data-ttu-id="c493b-1292">用於 [連絡支援人員] 的對話方塊現在會顯示在右側窗格中，並且會以停駐視窗形式開始。</span><span class="sxs-lookup"><span data-stu-id="c493b-1292">The dialog used for Contacting support will now appear in a pane on the right and will start off as a docked window.</span></span>

#### <a name="ink-in-your-email"></a><span data-ttu-id="c493b-1293">在您的電子郵件中使用筆跡！</span><span class="sxs-lookup"><span data-stu-id="c493b-1293">Ink in Your Email!</span></span>

<span data-ttu-id="c493b-1294">您現在可以在您的 Outlook 電子郵件中繪製圖片並加上註釋。</span><span class="sxs-lookup"><span data-stu-id="c493b-1294">You can now draw and annotate pictures in your Outlook emails.</span></span>

### <a name="word"></a><span data-ttu-id="c493b-1295">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-1295">Word</span></span>

#### <a name="open-document-links-in-word"></a><span data-ttu-id="c493b-1296">在 Word 中開啟文件連結</span><span class="sxs-lookup"><span data-stu-id="c493b-1296">Open document links in Word</span></span>

<span data-ttu-id="c493b-1297">當您在 Office 中按一下文件連結時，您可以更新您的喜好設定，以預設在 Word App 中開啟該連結。</span><span class="sxs-lookup"><span data-stu-id="c493b-1297">When you click a document link in Office, you can update your preference to open in the Word app by default.</span></span>  <span data-ttu-id="c493b-1298">若要更新您的喜好設定，請移至 [檔案] -> [選項] -> [進階] -> [連結處理]。</span><span class="sxs-lookup"><span data-stu-id="c493b-1298">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="c493b-1299">深入了解：https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="c493b-1299">Learn more: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="c493b-1300">開始使用：</span><span class="sxs-lookup"><span data-stu-id="c493b-1300">Getting Started:</span></span>

<span data-ttu-id="c493b-1301">此功能將預設為關閉。</span><span class="sxs-lookup"><span data-stu-id="c493b-1301">Feature will default to off.</span></span> <span data-ttu-id="c493b-1302">使用者可以透過 [選項] -> [進階] -> [連結處理] 設定來開啟它，也可以在 Win32 WXP 應用程式帶他們進行選擇加入體驗時選擇加入。</span><span class="sxs-lookup"><span data-stu-id="c493b-1302">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="c493b-1303">當使用者按一下透過 Outlook/Word/PowerPoint/Excel 儲存在 OneDrive/商務用 OneDrive/SharePoint 上的 Word/PowerPoint/Excel 檔案時，這些連結依預設會在適當的 Office 應用程式中 (而非瀏覽器中) 開啟。</span><span class="sxs-lookup"><span data-stu-id="c493b-1303">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="c493b-1304">若要變更此預設值，使用者可以更新 Outlook/Word/Excel/PowerPoint 中的下列設定：</span><span class="sxs-lookup"><span data-stu-id="c493b-1304">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="c493b-1305">[檔案] -> [選項] -> [進階] -> [連結處理]</span><span class="sxs-lookup"><span data-stu-id="c493b-1305">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="c493b-1306">此設定會在 Outlook/Word/PowerPoint/Excel 之間共用，而且可以在任一應用程式中設定。</span><span class="sxs-lookup"><span data-stu-id="c493b-1306">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="c493b-1307">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="c493b-1307">Scenarios to Try:</span></span>

<span data-ttu-id="c493b-1308">若要觸發選擇加入體驗 - 從 Outlook/Word/PowerPoint/Excel 開啟儲存在 OneDrive/SharePoint 中 Word 文件的連結 - 按一下 [在來自 Office Online 的用戶端中開啟] - 在 30 天內執行此動作兩次。</span><span class="sxs-lookup"><span data-stu-id="c493b-1308">To trigger the opt-in experience - Open a link tot a Word document stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="c493b-1309">在您選擇加入之後，依預設會在 Win32 應用程式中啟動連結。</span><span class="sxs-lookup"><span data-stu-id="c493b-1309">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-1310">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-1310">PowerPoint</span></span>

#### <a name="open-presentation-links-in-powerpoint"></a><span data-ttu-id="c493b-1311">在 PowerPoint 中開啟簡報連結</span><span class="sxs-lookup"><span data-stu-id="c493b-1311">Open presentation links in PowerPoint</span></span>

<span data-ttu-id="c493b-1312">當您在 Office 中按一下連結連結時，您可以更新您的喜好設定，以預設在 PowerPoint App 中開啟該連結。</span><span class="sxs-lookup"><span data-stu-id="c493b-1312">When you click a presentation link in Office, you can update your preference to open in the PowerPoint app by default.</span></span> <span data-ttu-id="c493b-1313">若要更新您的喜好設定，請移至 [檔案] -> [選項] -> [進階] -> [連結處理]。</span><span class="sxs-lookup"><span data-stu-id="c493b-1313">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="c493b-1314">深入了解：https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="c493b-1314">Learn more: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="c493b-1315">開始使用：</span><span class="sxs-lookup"><span data-stu-id="c493b-1315">Getting Started:</span></span>

<span data-ttu-id="c493b-1316">此功能將預設為關閉。</span><span class="sxs-lookup"><span data-stu-id="c493b-1316">Feature will default to off.</span></span> <span data-ttu-id="c493b-1317">使用者可以透過 [選項] -> [進階] -> [連結處理] 設定來開啟它，也可以在 Win32 WXP 應用程式帶他們進行選擇加入體驗時選擇加入。</span><span class="sxs-lookup"><span data-stu-id="c493b-1317">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="c493b-1318">當使用者按一下透過 Outlook/Word/PowerPoint/Excel 儲存在 OneDrive/商務用 OneDrive/SharePoint 上的 Word/PowerPoint/Excel 檔案時，這些連結依預設會在適當的 Office 應用程式中 (而非瀏覽器中) 開啟。</span><span class="sxs-lookup"><span data-stu-id="c493b-1318">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="c493b-1319">若要變更此預設值，使用者可以更新 Outlook/Word/Excel/PowerPoint 中的下列設定：</span><span class="sxs-lookup"><span data-stu-id="c493b-1319">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="c493b-1320">[檔案] -> [選項] -> [進階] -> [連結處理]</span><span class="sxs-lookup"><span data-stu-id="c493b-1320">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="c493b-1321">此設定會在 Outlook/Word/PowerPoint/Excel 之間共用，而且可以在任一應用程式中設定。</span><span class="sxs-lookup"><span data-stu-id="c493b-1321">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="c493b-1322">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="c493b-1322">Scenarios to Try:</span></span>

<span data-ttu-id="c493b-1323">若要觸發選擇加入體驗 - 從 Outlook/Word/PowerPoint/Excel 開啟儲存在 OneDrive/SharePoint 中 PowerPoint 簡報的連結 - 按一下 [在來自 Office Online 的用戶端中開啟] - 在 30 天內執行此動作兩次。</span><span class="sxs-lookup"><span data-stu-id="c493b-1323">To trigger the opt-in experience - Open a link to a PowerPoint presentation stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="c493b-1324">在您選擇加入之後，依預設會在 Win32 應用程式中啟動連結。</span><span class="sxs-lookup"><span data-stu-id="c493b-1324">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-1325">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-1325">Excel</span></span>

#### <a name="open-workbook-links-in-excel"></a><span data-ttu-id="c493b-1326">在 Excel 中開啟活頁簿連結</span><span class="sxs-lookup"><span data-stu-id="c493b-1326">Open workbook links in Excel</span></span>

<span data-ttu-id="c493b-1327">當您在 Office 中按一下活頁簿連結時，您可以更新您的喜好設定，以預設在 Excel App 中開啟該連結。</span><span class="sxs-lookup"><span data-stu-id="c493b-1327">When you click a workbook link in Office, you can update your preference to open in the Excel app by default.</span></span> <span data-ttu-id="c493b-1328">若要更新您的喜好設定，請移至 [檔案] -> [選項] -> [進階] -> [連結處理]。</span><span class="sxs-lookup"><span data-stu-id="c493b-1328">To update your preference, go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="c493b-1329">深入了解：https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="c493b-1329">Learn More: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="c493b-1330">開始使用：</span><span class="sxs-lookup"><span data-stu-id="c493b-1330">Getting Started:</span></span>

<span data-ttu-id="c493b-1331">此功能將預設為關閉。</span><span class="sxs-lookup"><span data-stu-id="c493b-1331">Feature will default to off.</span></span> <span data-ttu-id="c493b-1332">使用者可以透過 [選項] -> [進階] -> [連結處理] 設定來開啟它，也可以在 Win32 WXP 應用程式帶他們進行選擇加入體驗時選擇加入。</span><span class="sxs-lookup"><span data-stu-id="c493b-1332">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="c493b-1333">當使用者按一下透過 Outlook/Word/PowerPoint/Excel 儲存在 OneDrive/商務用 OneDrive/SharePoint 上的 Word/PowerPoint/Excel 檔案時，這些連結依預設會在適當的 Office 應用程式中 (而非瀏覽器中) 開啟。</span><span class="sxs-lookup"><span data-stu-id="c493b-1333">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="c493b-1334">若要變更此預設值，使用者可以更新 Outlook/Word/Excel/PowerPoint 中的下列設定：</span><span class="sxs-lookup"><span data-stu-id="c493b-1334">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="c493b-1335">[檔案] -> [選項] -> [進階] -> [連結處理]</span><span class="sxs-lookup"><span data-stu-id="c493b-1335">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="c493b-1336">此設定會在 Outlook/Word/PowerPoint/Excel 之間共用，而且可以在任一應用程式中設定。</span><span class="sxs-lookup"><span data-stu-id="c493b-1336">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="c493b-1337">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="c493b-1337">Scenarios to Try:</span></span>

<span data-ttu-id="c493b-1338">若要觸發選擇加入體驗 - 從 Outlook/Word/PowerPoint/Excel 開啟儲存在 OneDrive/SharePoint 中 Excel 活頁簿的連結 - 按一下 [在來自 Office Online 的用戶端中開啟] - 在 30 天內執行此動作兩次。</span><span class="sxs-lookup"><span data-stu-id="c493b-1338">To trigger the opt-in experience - Open a link to an Excel workbook stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="c493b-1339">在您選擇加入之後，依預設會在 Win32 應用程式中啟動連結。</span><span class="sxs-lookup"><span data-stu-id="c493b-1339">After you opt-in, links will launch in the Win32 apps by default.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="c493b-1340">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="c493b-1340">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="c493b-1341">全部</span><span class="sxs-lookup"><span data-stu-id="c493b-1341">All</span></span>
- <span data-ttu-id="c493b-1342">我們已修正即使在已停用自動儲存的情況下，檔案有時會自動儲存的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1342">We fixed an issue where files could sometimes be auto-saved even when auto-save was disabled</span></span>

### <a name="word"></a><span data-ttu-id="c493b-1343">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-1343">Word</span></span> 
- <span data-ttu-id="c493b-1344">我們已修正可能會導致部分使用者無法儲存至 SharePoint 的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1344">We fixed an issue which may have prevented some users from saving to SharePoint</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-1345">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-1345">Excel</span></span>
- <span data-ttu-id="c493b-1346">我們已修正可能對非作用中篩選器顯示不正確圖示的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-1346">We fixed an issue where an incorrect icon could be displayed for inactive filters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-1347">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-1347">PowerPoint</span></span>
- <span data-ttu-id="c493b-1348">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1348">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-1349">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-1349">Outlook</span></span>
- <span data-ttu-id="c493b-1350">我們已修正有些使用者在群組排程檢視中會不正確地顯示為離線的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1350">We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span>
- <span data-ttu-id="c493b-1351">我們已修正可能會防止 SafeLink 剖析包含尾端空格 URL 的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1351">We fixed an issue which prevented SafeLink from parsing a URL with a trailing space</span></span>
- <span data-ttu-id="c493b-1352">我們已修正會議室在非工作時間外顯示為可用的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1352">We fixed an issue where rooms were displayed as available outside of non-working hours</span></span>

### <a name="access"></a><span data-ttu-id="c493b-1353">Access</span><span class="sxs-lookup"><span data-stu-id="c493b-1353">Access</span></span>
- <span data-ttu-id="c493b-1354">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1354">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="c493b-1355">Project</span><span class="sxs-lookup"><span data-stu-id="c493b-1355">Project</span></span>
- <span data-ttu-id="c493b-1356">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1356">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-24-2019"></a><span data-ttu-id="c493b-1357">2019 年 5 月 24 日</span><span class="sxs-lookup"><span data-stu-id="c493b-1357">May 24, 2019</span></span>
<span data-ttu-id="c493b-1358">版本 1906 (組建 11715.20002)</span><span class="sxs-lookup"><span data-stu-id="c493b-1358">Version 1906 (build 11715.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="c493b-1359">新功能：</span><span class="sxs-lookup"><span data-stu-id="c493b-1359">What's New:</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="c493b-1360">使用者體驗更新</span><span class="sxs-lookup"><span data-stu-id="c493b-1360">User Experience Updates</span></span>

<span data-ttu-id="c493b-1361">[即將推出] 中的更新現已發佈，其中包括簡化功能區、資料夾窗格的新版視覺效果、郵件清單，以及讀取窗格。</span><span class="sxs-lookup"><span data-stu-id="c493b-1361">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="c493b-1362">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="c493b-1362">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="c493b-1363">全部</span><span class="sxs-lookup"><span data-stu-id="c493b-1363">All</span></span>

- <span data-ttu-id="c493b-1364">我們已修正 [聊天] 窗格無法顯示的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1364">We fixed an issue where the Chat Pane would not display</span></span>

### <a name="word"></a><span data-ttu-id="c493b-1365">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-1365">Word</span></span> 
- <span data-ttu-id="c493b-1366">我們已修正在某些情況下 Word 無法為文法錯誤正確醒目提示文字的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1366">We fixed an issue where in some cases Word could incorrectly highlight text for grammatical errors</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-1367">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-1367">Excel</span></span>
- <span data-ttu-id="c493b-1368">我們已修正 [圖表項目] 使用不正確圖示的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1368">We fixed an issue where an incorrect icon was used in for Chart Elements</span></span>
- <span data-ttu-id="c493b-1369">我們已修正開啟同樣的活頁簿時，可能會啟動 VBA 指令碼中不正確活頁簿的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1369">We fixed an issue where the incorrect workbook could be activated in a VBA script when the same book was already open</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-1370">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-1370">PowerPoint</span></span>
- <span data-ttu-id="c493b-1371">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1371">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-1372">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-1372">Outlook</span></span>
- <span data-ttu-id="c493b-1373">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1373">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="c493b-1374">Access</span><span class="sxs-lookup"><span data-stu-id="c493b-1374">Access</span></span>
- <span data-ttu-id="c493b-1375">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1375">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="c493b-1376">Project</span><span class="sxs-lookup"><span data-stu-id="c493b-1376">Project</span></span>
- <span data-ttu-id="c493b-1377">我們已修正 Project 在切換工作列後可能會當機的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1377">We fixed an issue where Project could crash after switching to the taskbar</span></span>

</BR></BR>

## <a name="may-17-2019"></a><span data-ttu-id="c493b-1378">2019 年 5 月 17 日</span><span class="sxs-lookup"><span data-stu-id="c493b-1378">May 17, 2019</span></span>
<span data-ttu-id="c493b-1379">版本 1906 (組建 11708.20006)</span><span class="sxs-lookup"><span data-stu-id="c493b-1379">Version 1906 (build 11708.20006)</span></span>

## <a name="whats-new"></a><span data-ttu-id="c493b-1380">新功能：</span><span class="sxs-lookup"><span data-stu-id="c493b-1380">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-1381">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-1381">Outlook</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="c493b-1382">使用者體驗更新</span><span class="sxs-lookup"><span data-stu-id="c493b-1382">User Experience Updates</span></span>

<span data-ttu-id="c493b-1383">[即將推出] 中的更新現已發佈，其中包括簡化功能區、資料夾窗格的新版視覺效果、郵件清單，以及讀取窗格。</span><span class="sxs-lookup"><span data-stu-id="c493b-1383">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="c493b-1384">開始使用：</span><span class="sxs-lookup"><span data-stu-id="c493b-1384">Getting Started:</span></span>

<span data-ttu-id="c493b-1385">這些變更會成為新的預設 UI。自 12 月中旬起，即可透過 [即將推出] 開關切換使用這套 UI，協助您徹底發揮生產力</span><span class="sxs-lookup"><span data-stu-id="c493b-1385">These change will be part of the new default UI; it has been available behind the Coming Soon switch since mid Dec for 100% prod</span></span>

#### <a name="customizable-simplified-ribbon"></a><span data-ttu-id="c493b-1386">自訂簡化功能區</span><span class="sxs-lookup"><span data-stu-id="c493b-1386">Customizable Simplified Ribbon</span></span>

<span data-ttu-id="c493b-1387">提供輕鬆自訂功能，方便在傳統與 [簡化] 檢視之間切換，以及釘選/取消釘選命令。</span><span class="sxs-lookup"><span data-stu-id="c493b-1387">Easily customizable to switch between classic and Simplified views and pin/unpin commands.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="c493b-1388">開始使用：</span><span class="sxs-lookup"><span data-stu-id="c493b-1388">Getting Started:</span></span>

<span data-ttu-id="c493b-1389">使用者可以使用簡化功能區，方法是開啟 [即將推出] (在一開始)，然後按一下功能區中的＞形箭號，即可在傳統的多行功能區與新式的簡化單行功能區之間切換。</span><span class="sxs-lookup"><span data-stu-id="c493b-1389">Users can get to the simplified ribbon by turning on Coming Soon (initially) and clicking the chevron in the ribbon to toggle between the classic multi-line ribbon and the new simplified single-line ribbon.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="c493b-1390">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="c493b-1390">Scenarios to Try:</span></span>

<span data-ttu-id="c493b-1391">從傳統功能區切換到簡化功能區</span><span class="sxs-lookup"><span data-stu-id="c493b-1391">Switch from Classic ribbon to Simplified ribbon</span></span>

#### <a name="pick-your-favorite-action"></a><span data-ttu-id="c493b-1392">挑選您的最愛動作</span><span class="sxs-lookup"><span data-stu-id="c493b-1392">Pick your favorite action</span></span>

<span data-ttu-id="c493b-1393">不使用 [標幟] 和 [刪除] 嗎？</span><span class="sxs-lookup"><span data-stu-id="c493b-1393">Don't use Flag and Delete?</span></span> <span data-ttu-id="c493b-1394">那麼 [封存] 或 [標示為已讀取] 呢？</span><span class="sxs-lookup"><span data-stu-id="c493b-1394">How about Archive or Mark as Read?</span></span> <span data-ttu-id="c493b-1395">自訂快速動作功能表，加上您最常使用的命令。</span><span class="sxs-lookup"><span data-stu-id="c493b-1395">Customize the quick action menu with the commands you use most.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="c493b-1396">開始使用：</span><span class="sxs-lookup"><span data-stu-id="c493b-1396">Getting Started:</span></span>

<span data-ttu-id="c493b-1397">若要選取 [快速動作]，請以滑鼠右鍵按一下郵件清單中的 [電子郵件]，以顯示內容功能表。</span><span class="sxs-lookup"><span data-stu-id="c493b-1397">To select your Quick Actions, right click on an email in the message list to bring up the Context Menu.</span></span> <span data-ttu-id="c493b-1398">然後按一下 [設定快速動作...]</span><span class="sxs-lookup"><span data-stu-id="c493b-1398">Then click "Set Quick Actions..."</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="c493b-1399">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="c493b-1399">Scenarios to Try:</span></span>

<span data-ttu-id="c493b-1400">將 [標幟] 和 [刪除] 的預設值變更為 [封存]、[移動]、[標示為已讀取] 或 [無]，以便清除郵件清單</span><span class="sxs-lookup"><span data-stu-id="c493b-1400">Change the defaults from flag and delete to either archive, move,  mark as read, or none for a cleaner message list</span></span>

#### <a name="relaxed-or-tighter-layout-you-choose"></a><span data-ttu-id="c493b-1401">寬鬆或緊密的版面配置？</span><span class="sxs-lookup"><span data-stu-id="c493b-1401">Relaxed or tighter layout?</span></span> <span data-ttu-id="c493b-1402">由您選擇</span><span class="sxs-lookup"><span data-stu-id="c493b-1402">You choose</span></span>

<span data-ttu-id="c493b-1403">若您想讓郵件之間能有更多空間，可以採用「緊密間距」；或者，您也可以採用緊密的版面配置，以便查看更多郵件。</span><span class="sxs-lookup"><span data-stu-id="c493b-1403">Use Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="c493b-1404">開始使用：</span><span class="sxs-lookup"><span data-stu-id="c493b-1404">Getting Started:</span></span>

<span data-ttu-id="c493b-1405">前往 [檢視] 索引標籤，勾選 [更緊密的間距] 核取方塊。若是使用傳統功能區，該核取方塊位於「郵件」群組內；若是使用簡化功能區，則是位於「目前檢視」設定當中</span><span class="sxs-lookup"><span data-stu-id="c493b-1405">View tab, use tighter spacing checkbox - in Messages group for classic ribbon, Current View settings for simplified ribbon</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="c493b-1406">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="c493b-1406">Scenarios to Try:</span></span>

<span data-ttu-id="c493b-1407">使用 Outlook 在未啟用設定的情況下分類及撰寫電子郵件。</span><span class="sxs-lookup"><span data-stu-id="c493b-1407">Use Outlook to triage and write email with and without the setting enabled.</span></span> <span data-ttu-id="c493b-1408">如果開啟 [使用更緊密的間距]，即可讓每個頁面能夠容納得下更多郵件，並讓撰寫表單的控制項更為簡潔。</span><span class="sxs-lookup"><span data-stu-id="c493b-1408">With Use tighter spacing on, more messages fit per page, and controls on the compose forms are more streamlined.</span></span>

#### <a name="dedupe-mru-entries-when-using-the-onedrive-sync-client"></a><span data-ttu-id="c493b-1409">使用 OneDrive 同步處理用戶端時的刪除重複資料 MRU 項目</span><span class="sxs-lookup"><span data-stu-id="c493b-1409">Dedupe MRU entries when using the Onedrive sync client</span></span>

<span data-ttu-id="c493b-1410">透過刪除重複資料 MRU 項目，改善 OneDrive 同步處理用戶端與雲端附件的整合度並加快附加速度，讓其速度足以媲美同步處理資料的複製行為</span><span class="sxs-lookup"><span data-stu-id="c493b-1410">Enable better integration with onedrive sync client with cloud attachments by deduping the mru entries and to enable faster attach as copy behavior for synchronized data</span></span>

##### <a name="getting-started"></a><span data-ttu-id="c493b-1411">開始使用：</span><span class="sxs-lookup"><span data-stu-id="c493b-1411">Getting Started:</span></span>

<span data-ttu-id="c493b-1412">若您使用的是 OneDrive 同步處理用戶端，將再也看不到「附加檔案 MRU」的檔案重複項目。</span><span class="sxs-lookup"><span data-stu-id="c493b-1412">If you use the OneDrive sync client, you will no longer see file duplicates in the Attach File MRU.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="c493b-1413">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="c493b-1413">Scenarios to Try:</span></span>

<span data-ttu-id="c493b-1414">啟用 OneDrive 同步處理用戶端，並使用 Outlook 電腦版的 [附加檔案] 功能表</span><span class="sxs-lookup"><span data-stu-id="c493b-1414">Enable the OneDrive sync client and use the Attach File menu in Outlook Desktop</span></span>

#### <a name="improved-shared-folder-synchronization-for-mailboxes-with-many-folders"></a><span data-ttu-id="c493b-1415">已改善擁有多個資料夾的信箱共用資料夾同步處理</span><span class="sxs-lookup"><span data-stu-id="c493b-1415">Improved shared folder synchronization for mailboxes with many folders</span></span>

<span data-ttu-id="c493b-1416">Outlook 多年來在同步共用信箱時，其資料夾的數量限制最多為 500 個。</span><span class="sxs-lookup"><span data-stu-id="c493b-1416">For years Outlook has been limited to a maximum of 500 folders when synchronizing shared mailboxes.</span></span> <span data-ttu-id="c493b-1417">透過這項變更已讓 Outlook 獲得改善，您在同步時將不會再遇到這 500 個資料夾的數量限制。</span><span class="sxs-lookup"><span data-stu-id="c493b-1417">With this change Outlook has been improved to sync in a way that will no longer encounter this 500 folder limit.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="c493b-1418">開始使用：</span><span class="sxs-lookup"><span data-stu-id="c493b-1418">Getting Started:</span></span>

<span data-ttu-id="c493b-1419">在信箱中新增 1000 個資料夾、讓其他人存取信箱、新增「其他人」的 Outlook 設定檔，然後確認同步處理是否可正常運作。</span><span class="sxs-lookup"><span data-stu-id="c493b-1419">Create 1000 folders in a mailbox, give someone else access to the mailbox, create an Outlook profile for the "someone else" and verify that sync works.</span></span>

### <a name="word"></a><span data-ttu-id="c493b-1420">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-1420">Word</span></span>

#### <a name="erase-just-a-little-bit"></a><span data-ttu-id="c493b-1421">小面積清除</span><span class="sxs-lookup"><span data-stu-id="c493b-1421">Erase just a little bit</span></span>

##### <a name="getting-started"></a><span data-ttu-id="c493b-1422">開始使用：</span><span class="sxs-lookup"><span data-stu-id="c493b-1422">Getting Started:</span></span>

<span data-ttu-id="c493b-1423">前往 [繪圖] 索引標籤。選取 [橡皮擦] 下拉式清單。</span><span class="sxs-lookup"><span data-stu-id="c493b-1423">Go to the Draw Tab. Select the Eraser dropdown.</span></span> <span data-ttu-id="c493b-1424">選擇 [小型橡皮擦] 或 [中型橡皮擦]。</span><span class="sxs-lookup"><span data-stu-id="c493b-1424">Choose Small Eraser or Medium Eraser.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="c493b-1425">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="c493b-1425">Scenarios to Try:</span></span>

<span data-ttu-id="c493b-1426">前往 [繪圖] 索引標籤。選取畫筆。</span><span class="sxs-lookup"><span data-stu-id="c493b-1426">Go to the Draw Tab. Select a pen.</span></span> <span data-ttu-id="c493b-1427">畫出一道筆跡線條。</span><span class="sxs-lookup"><span data-stu-id="c493b-1427">Draw an ink stroke.</span></span> <span data-ttu-id="c493b-1428">選取 [橡皮擦] 下拉式清單。</span><span class="sxs-lookup"><span data-stu-id="c493b-1428">Select the Eraser dropdown.</span></span> <span data-ttu-id="c493b-1429">選擇 [小型橡皮擦] 或 [中型橡皮擦]。</span><span class="sxs-lookup"><span data-stu-id="c493b-1429">Choose Small Eraser or Medium Eraser.</span></span> <span data-ttu-id="c493b-1430">清除一小塊的筆跡線條。</span><span class="sxs-lookup"><span data-stu-id="c493b-1430">Erase just bits of the ink stroke.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="c493b-1431">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="c493b-1431">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="c493b-1432">全部</span><span class="sxs-lookup"><span data-stu-id="c493b-1432">All</span></span> 
- <span data-ttu-id="c493b-1433">我們已修正可能會導致部分使用者無法儲存成 PDF 的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1433">We fixed an issue which could prevent some users from saving as PDF</span></span>
- <span data-ttu-id="c493b-1434">我們已修正可能會影響使用者在 32 位元系統上儲存大型檔案的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1434">We fixed an issue which could impact users saving large files on a 32-bit system</span></span>

### <a name="word"></a><span data-ttu-id="c493b-1435">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-1435">Word</span></span> 
- <span data-ttu-id="c493b-1436">我們已大幅改善 [聽寫] 功能的反應能力</span><span class="sxs-lookup"><span data-stu-id="c493b-1436">We significantly improved the responsiveness of the dictation feature</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-1437">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-1437">Excel</span></span>
- <span data-ttu-id="c493b-1438">我們已修正按兩下事件在觸控式螢幕裝置上可能會失靈的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1438">We fixed an issue where double-click events could fail on touch screen devices</span></span>
- <span data-ttu-id="c493b-1439">我們已修正可能會導致部分使用者無法編輯 VBA 巨集的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1439">We fixed an issue which could prevent some users from being able to edit VBA macros</span></span>
- <span data-ttu-id="c493b-1440">我們已修正使用交叉分析篩選器時可能會影響效能的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1440">We fixed an issue which could impact performance when using slicers</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-1441">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-1441">PowerPoint</span></span>
- <span data-ttu-id="c493b-1442">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1442">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-1443">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-1443">Outlook</span></span>
- <span data-ttu-id="c493b-1444">我們已修正從所選範本中會出現錯誤範本的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1444">We fixed an issue where the wrong template could be displayed from what was selected</span></span>

### <a name="access"></a><span data-ttu-id="c493b-1445">Access</span><span class="sxs-lookup"><span data-stu-id="c493b-1445">Access</span></span>
- <span data-ttu-id="c493b-1446">我們已修正在使用縮放建立器顯示完整 RTF 格式時，可能難以閱讀的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1446">We fixed an issue where using the zoom builder to display long rich text, could be hard to read</span></span>

### <a name="project"></a><span data-ttu-id="c493b-1447">Project</span><span class="sxs-lookup"><span data-stu-id="c493b-1447">Project</span></span>
- <span data-ttu-id="c493b-1448">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1448">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-10-2019"></a><span data-ttu-id="c493b-1449">2019 年 5 月 10 日</span><span class="sxs-lookup"><span data-stu-id="c493b-1449">May 10, 2019</span></span>
<span data-ttu-id="c493b-1450">版本 1906 (組建 11702.20000)</span><span class="sxs-lookup"><span data-stu-id="c493b-1450">Version 1906 (build 11702.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="c493b-1451">新功能：</span><span class="sxs-lookup"><span data-stu-id="c493b-1451">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-1452">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-1452">Outlook</span></span>

<span data-ttu-id="c493b-1453">**在螢幕上容納更多郵件：** 選取 [檢視] > [使用更緊密的間距] 來調整郵件之間的間距。</span><span class="sxs-lookup"><span data-stu-id="c493b-1453">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="c493b-1454">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="c493b-1454">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="c493b-1455">全部</span><span class="sxs-lookup"><span data-stu-id="c493b-1455">All</span></span>
- <span data-ttu-id="c493b-1456">我們已修正 [另存新檔] 對話方塊顯示不正確路徑的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1456">We fixed an issue where the Save As dialog could display the incorrect path</span></span>

### <a name="word"></a><span data-ttu-id="c493b-1457">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-1457">Word</span></span> 
- <span data-ttu-id="c493b-1458">我們已修正有些「告訴我」選項無法插入的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1458">We fixed an issue where some selections from Tell Me would not get inserted</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-1459">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-1459">Excel</span></span>
- <span data-ttu-id="c493b-1460">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1460">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-1461">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-1461">PowerPoint</span></span>
- <span data-ttu-id="c493b-1462">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1462">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-1463">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-1463">Outlook</span></span>
- <span data-ttu-id="c493b-1464">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1464">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="c493b-1465">Access</span><span class="sxs-lookup"><span data-stu-id="c493b-1465">Access</span></span>
- <span data-ttu-id="c493b-1466">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1466">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="c493b-1467">Project</span><span class="sxs-lookup"><span data-stu-id="c493b-1467">Project</span></span>
- <span data-ttu-id="c493b-1468">我們已修正任務識別碼需要醒目提示才能看見的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1468">We fixed an issue where Task ID's could require highlighting to see</span></span>

</BR></BR>

## <a name="may-3-2019"></a><span data-ttu-id="c493b-1469">2019 年 5 月 3 日</span><span class="sxs-lookup"><span data-stu-id="c493b-1469">May 3, 2019</span></span>
<span data-ttu-id="c493b-1470">版本 1906 (組建 11629.20008)</span><span class="sxs-lookup"><span data-stu-id="c493b-1470">Version 1906 (build 11629.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="c493b-1471">新功能：</span><span class="sxs-lookup"><span data-stu-id="c493b-1471">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-1472">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-1472">Outlook</span></span>

<span data-ttu-id="c493b-1473">**集中所有加密選項：** 只要前往 [選項] > [加密]，即可選擇要用來保護電子郵件訊息的方法。</span><span class="sxs-lookup"><span data-stu-id="c493b-1473">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="c493b-1474">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="c493b-1474">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="c493b-1475">全部</span><span class="sxs-lookup"><span data-stu-id="c493b-1475">All</span></span>
- <span data-ttu-id="c493b-1476">我們已修正有些使用者使用商務用 OneDrive 同步處理時遇到的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1476">We fixed an issue where some users would experience problems syncing with OneDrive for Business</span></span>

### <a name="word"></a><span data-ttu-id="c493b-1477">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-1477">Word</span></span> 
- <span data-ttu-id="c493b-1478">我們已修正在某些情況下，Word 會花很長時間啟動的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1478">We fixed an issue where in some cases Word would take a long time to start</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-1479">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-1479">Excel</span></span>
- <span data-ttu-id="c493b-1480">我們已修正升級至較新版 Excel 後活頁簿的外部連結有時會被移除的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1480">We fixed an issue where external links were sometimes removed from workbooks after upgrading to a newer version of Excel</span></span>
- <span data-ttu-id="c493b-1481">我們已修正有些使用者可能會遇到無法在新活頁簿中選取儲存格的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1481">We fixed an issue where some users could experience difficulty selecting cells in a new workbook</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-1482">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-1482">PowerPoint</span></span>
- <span data-ttu-id="c493b-1483">我們已修正將繪圖轉換成文字時字型大小不一致的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1483">We fixed an issue where font sizes were not consistant when converting drawings to text</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-1484">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-1484">Outlook</span></span>
- <span data-ttu-id="c493b-1485">我們已修正從 .VCF 檔案儲存連絡人可能會導致空白欄位的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1485">We fixed an issue where saving a contact from a .VCF file could result in empty fields</span></span>
- <span data-ttu-id="c493b-1486">我們已修正即使郵件已寄出卻仍卡在寄件匣資料夾的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1486">We fixed an issue where a message could get stuck in the outbox folder even though it had been sent</span></span>
- <span data-ttu-id="c493b-1487">我們已修正檢視 DRM 訊息時 Outlook 可能會當機的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1487">We fixed an issue where Outlook could crash when viewing a DRM message</span></span>

### <a name="access"></a><span data-ttu-id="c493b-1488">Access</span><span class="sxs-lookup"><span data-stu-id="c493b-1488">Access</span></span>
- <span data-ttu-id="c493b-1489">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1489">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="c493b-1490">Project</span><span class="sxs-lookup"><span data-stu-id="c493b-1490">Project</span></span>
- <span data-ttu-id="c493b-1491">我們已修正編輯器會從中文切換為英文的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1491">We fixed an issue where the editor would switch from Chinese to English</span></span>
- <span data-ttu-id="c493b-1492">我們已修正主專案的已發佈複本中出現未發佈工作的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1492">We fixed an issue where unpublished tasks could appear in the published copy of a master project</span></span>

</BR></BR>

## <a name="april-26-2019"></a><span data-ttu-id="c493b-1493">2019 年 4 月 26 日</span><span class="sxs-lookup"><span data-stu-id="c493b-1493">April 26, 2019</span></span>
<span data-ttu-id="c493b-1494">版本 1905 (組建 11617.20002)</span><span class="sxs-lookup"><span data-stu-id="c493b-1494">Version 1905 (build 11617.20002)</span></span>

## <a name="new-features"></a><span data-ttu-id="c493b-1495">新功能</span><span class="sxs-lookup"><span data-stu-id="c493b-1495">New Features</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-1496">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-1496">Outlook</span></span>

<span data-ttu-id="c493b-1497">**共用行事曆更新的速度更快：** 針對 Office 365 中的共用行事曆，Outlook 可以使用 REST API 更新這些行事曆。</span><span class="sxs-lookup"><span data-stu-id="c493b-1497">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="c493b-1498">開啟預覽以更快且更可靠地更新共用行事曆。</span><span class="sxs-lookup"><span data-stu-id="c493b-1498">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-1499">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-1499">Excel</span></span>

#### <a name="coauthoring-improvements"></a><span data-ttu-id="c493b-1500">共同撰寫的增強功能</span><span class="sxs-lookup"><span data-stu-id="c493b-1500">Coauthoring improvements</span></span>

<span data-ttu-id="c493b-1501">改善共同撰寫的體驗，盡可能讓其他人即時收到修改過的內容。</span><span class="sxs-lookup"><span data-stu-id="c493b-1501">Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

### <a name="visio"></a><span data-ttu-id="c493b-1502">Visio</span><span class="sxs-lookup"><span data-stu-id="c493b-1502">Visio</span></span>

- <span data-ttu-id="c493b-1503">**從 Power BI 匯出 Visio 視覺效果：** 當匯出 Power BI 報表為 PDF 或 PowerPoint 等更多檔案時，Power BI Visio 視覺效果會正常顯示。</span><span class="sxs-lookup"><span data-stu-id="c493b-1503">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="c493b-1504">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="c493b-1504">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="c493b-1505">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-1505">Word</span></span> 
- <span data-ttu-id="c493b-1506">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1506">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-1507">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-1507">Excel</span></span>
- <span data-ttu-id="c493b-1508">我們已修正 Solver 巨集無法執行的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1508">We fixed an issue where Solver macros would fail to run</span></span>
- <span data-ttu-id="c493b-1509">我們已修正阻止 Excel 檔案匯入到 SharePoint 的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1509">We fixed an issue which could prevent Excel files from being imported into SharePoint</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-1510">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-1510">PowerPoint</span></span>
- <span data-ttu-id="c493b-1511">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1511">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-1512">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-1512">Outlook</span></span>
- <span data-ttu-id="c493b-1513">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1513">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="c493b-1514">Access</span><span class="sxs-lookup"><span data-stu-id="c493b-1514">Access</span></span>
- <span data-ttu-id="c493b-1515">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1515">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="c493b-1516">Project</span><span class="sxs-lookup"><span data-stu-id="c493b-1516">Project</span></span>
- <span data-ttu-id="c493b-1517">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1517">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-19-2019"></a><span data-ttu-id="c493b-1518">2019 年 4 月 19 日</span><span class="sxs-lookup"><span data-stu-id="c493b-1518">April 19, 2019</span></span>
<span data-ttu-id="c493b-1519">版本 1905 (組建 11609.20002)</span><span class="sxs-lookup"><span data-stu-id="c493b-1519">Version 1905 (build 11609.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="c493b-1520">新功能：</span><span class="sxs-lookup"><span data-stu-id="c493b-1520">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-1521">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-1521">Outlook</span></span>

<span data-ttu-id="c493b-1522">**搜尋人員時取得電子郵件建議：** 當您在 [搜尋] 方塊中輸入人員的名稱時，最相關的電子郵件訊息會包括在您的搜尋建議中。</span><span class="sxs-lookup"><span data-stu-id="c493b-1522">**Get email suggestions when you search for a person:** When you type a person's name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-1523">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-1523">Excel</span></span>

#### <a name="improved-filled-maps-experience-using-data-types"></a><span data-ttu-id="c493b-1524">使用資料類型改善區域分布圖體驗</span><span class="sxs-lookup"><span data-stu-id="c493b-1524">Improved Filled Maps experience using Data Types</span></span>

<span data-ttu-id="c493b-1525">此功能是針對使用 Excel 的地理資料類型繪製區域分布圖圖表使用者的增強功能。</span><span class="sxs-lookup"><span data-stu-id="c493b-1525">This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="c493b-1526">對使用者的優點是功能之間有更豐富的整合，以及使用者要對應的區域會有更好的精確度。</span><span class="sxs-lookup"><span data-stu-id="c493b-1526">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="c493b-1527">其他優點包括功能能夠對應城市多邊形。</span><span class="sxs-lookup"><span data-stu-id="c493b-1527">Additional benefits include - ability to map city polygons.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="c493b-1528">開始使用：</span><span class="sxs-lookup"><span data-stu-id="c493b-1528">Getting Started:</span></span>

- <span data-ttu-id="c493b-1529">此功能是 Excel 內現有功能的增強功能。</span><span class="sxs-lookup"><span data-stu-id="c493b-1529">This feature is an improvement to the existing features within Excel.</span></span> <span data-ttu-id="c493b-1530">若要使用增強功能，請將位置轉換為豐富的實體，並使用區域分布圖繪製。</span><span class="sxs-lookup"><span data-stu-id="c493b-1530">To use the improvement - convert locations into Rich Entities and plot with Filled Maps.</span></span> 

##### <a name="scenarios-to-try"></a><span data-ttu-id="c493b-1531">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="c493b-1531">Scenarios to Try:</span></span>

- <span data-ttu-id="c493b-1532">使用者可以嘗試對應城市、省/市、縣/市、國家/地區和郵遞區號。</span><span class="sxs-lookup"><span data-stu-id="c493b-1532">Users can try mapping cities, states, counties, countries and zip codes.</span></span> 


## <a name="notable-fixes"></a><span data-ttu-id="c493b-1533">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="c493b-1533">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="c493b-1534">所有應用程式</span><span class="sxs-lookup"><span data-stu-id="c493b-1534">All Applications</span></span>
- <span data-ttu-id="c493b-1535">我們已修正每當應用程式啟動時會顯示 [初次執行] 對話方塊的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1535">We fixed an issue where the First Run dialog would display whenever an application was launched</span></span>
- <span data-ttu-id="c493b-1536">我們已修正 [另存新檔] 對話方塊中 SharePoint 連結可能遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-1536">We fixed an issue where a SharePoint link in the "save as" dialog could be missing.</span></span>
- <span data-ttu-id="c493b-1537">我們已修正使用者錯誤地看到 [立即修復] 對話方塊的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1537">We fixed an issue where users would incorrectly see a "Repair Now" dialog</span></span>

### <a name="word"></a><span data-ttu-id="c493b-1538">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-1538">Word</span></span> 
- <span data-ttu-id="c493b-1539">我們已修正某些使用者在要求字型時，可能會收到記憶體或磁碟空間不足錯誤的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1539">We fixed an issue where some users could receive an error for insufficient memory or disk space when requesting a font</span></span>
- <span data-ttu-id="c493b-1540">我們已修正視窗從 [註解] 窗格切換時，焦點可能會遺失的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1540">We fixed an issue where a window could lose focus when switching from the comments pane</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-1541">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-1541">Excel</span></span>
- <span data-ttu-id="c493b-1542">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1542">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-1543">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-1543">PowerPoint</span></span>
- <span data-ttu-id="c493b-1544">我們已修正會妨礙調整商標圖形大小的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1544">We fixed an issue preventing the resizing of branded shapes</span></span>
- <span data-ttu-id="c493b-1545">我們已修正在受保護的檢視模式中開啟檔案時，PowerPoint 會當機的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1545">We fixed an issue where PowerPoint could crash when opening a file in protected view mode</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-1546">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-1546">Outlook</span></span>
- <span data-ttu-id="c493b-1547">我們已修正會防礙一些使用者選取中文文字的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1547">We fixed an issue which prevented some users from selecting Chinese words</span></span>
- <span data-ttu-id="c493b-1548">我們已修正未正確計算到期日的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1548">We fixed an issue where expiry dates were not calculated correctly</span></span>

### <a name="access"></a><span data-ttu-id="c493b-1549">Access</span><span class="sxs-lookup"><span data-stu-id="c493b-1549">Access</span></span>
- <span data-ttu-id="c493b-1550">我們已修正會防礙一些使用者使用巨集建立器的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1550">We fixed an issue which prevented some users from using the Macro Builder</span></span>
- <span data-ttu-id="c493b-1551">我們已修正列印報表只會列印第一頁的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1551">We fixed an issue where printing a report would only print the first page</span></span>
- <span data-ttu-id="c493b-1552">我們已修正將游標移到超連結上時，應用程式會當機的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1552">We fixed an issue where the application could crash when hovering over a hyperlink</span></span>
- <span data-ttu-id="c493b-1553">我們已修正使用關聯性檢視檢視時，造成某些項目在螢幕上消失的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1553">We fixed an issue which caused some items to appear off screen when using relationships view</span></span>

### <a name="project"></a><span data-ttu-id="c493b-1554">Project</span><span class="sxs-lookup"><span data-stu-id="c493b-1554">Project</span></span>
- <span data-ttu-id="c493b-1555">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1555">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-12-2019"></a><span data-ttu-id="c493b-1556">2019 年 4 月 12 日</span><span class="sxs-lookup"><span data-stu-id="c493b-1556">April 12, 2019</span></span>
<span data-ttu-id="c493b-1557">版本 1905 (組建 11601.20042)</span><span class="sxs-lookup"><span data-stu-id="c493b-1557">Version 1905 (build 11601.20042)</span></span>

## <a name="whats-new"></a><span data-ttu-id="c493b-1558">新功能：</span><span class="sxs-lookup"><span data-stu-id="c493b-1558">What's New:</span></span>

### <a name="access"></a><span data-ttu-id="c493b-1559">Access</span><span class="sxs-lookup"><span data-stu-id="c493b-1559">Access</span></span>

#### <a name="get-smart-with-microsoft-graph"></a><span data-ttu-id="c493b-1560">充分發揮 Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="c493b-1560">Get smart with Microsoft Graph</span></span>

<span data-ttu-id="c493b-1561">使用智慧型技術匯入或連結到智慧型資料，並重新打造您的桌面資料庫。</span><span class="sxs-lookup"><span data-stu-id="c493b-1561">Import or link to intelligent data and reinvent your desktop database with Intelligent Technology.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="c493b-1562">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="c493b-1562">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="c493b-1563">所有應用程式</span><span class="sxs-lookup"><span data-stu-id="c493b-1563">All Applications</span></span>
 - <span data-ttu-id="c493b-1564">我們已修正會防止使用者將檔案儲存到雲端位置的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1564">We fixed an issue which prevented some users from saving files to cloud locations</span></span>
 - <span data-ttu-id="c493b-1565">我們已修正可能從功能區開啟錯誤窗格的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1565">We fixed an issue where the wrong pane could open from the ribbon</span></span>

### <a name="word"></a><span data-ttu-id="c493b-1566">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-1566">Word</span></span> 
- <span data-ttu-id="c493b-1567">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1567">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-1568">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-1568">Excel</span></span>
- <span data-ttu-id="c493b-1569">我們已修正當活頁簿不包含連結資料類型時，使用者會看到連結資料類型之錯誤訊息的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1569">We fixed an issue where users would see an error message for linked data types when the workbook did not contain linked data types</span></span>
- <span data-ttu-id="c493b-1570">我們已修正在本機與線上檢視 Word 文件時，文件中的 URL 連結可能變更的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1570">We fixed an issue where URL links within a Word document could change when viewed locally vs. online</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-1571">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-1571">PowerPoint</span></span>
- <span data-ttu-id="c493b-1572">我們已修正應用程式可能會在從 [動畫] 索引標籤復原變更之後當機的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1572">We fixed an issue where the application could crash after undoing changes from the animations tab</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-1573">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-1573">Outlook</span></span>
- <span data-ttu-id="c493b-1574">我們已修正會防止一些使用者修改公用資料夾中連絡人 [備註] 欄位的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1574">We fixed an issue which prevented some users from modifying the Notes field for contacts in a Public Folder</span></span>
- <span data-ttu-id="c493b-1575">我們已修正到期日與刪除日期之間可能發生衝突的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1575">We fixed an issue where a conflict could occur between expiration dates and deletion dates</span></span>

### <a name="access"></a><span data-ttu-id="c493b-1576">Access</span><span class="sxs-lookup"><span data-stu-id="c493b-1576">Access</span></span>
- <span data-ttu-id="c493b-1577">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1577">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="c493b-1578">Project</span><span class="sxs-lookup"><span data-stu-id="c493b-1578">Project</span></span>
- <span data-ttu-id="c493b-1579">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1579">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-5-2019"></a><span data-ttu-id="c493b-1580">2019 年 4 月 5 日</span><span class="sxs-lookup"><span data-stu-id="c493b-1580">April 5, 2019</span></span>
<span data-ttu-id="c493b-1581">版本 1904 (組建 11527.20014)</span><span class="sxs-lookup"><span data-stu-id="c493b-1581">Version 1904 (build 11527.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="c493b-1582">新功能：</span><span class="sxs-lookup"><span data-stu-id="c493b-1582">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-1583">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-1583">Outlook</span></span>

#### <a name="outlook-for-windows--set-and-share-your-focused-inbox-settings"></a><span data-ttu-id="c493b-1584">Windows 版 Outlook：設定並共用您的 [焦點收件匣] 設定</span><span class="sxs-lookup"><span data-stu-id="c493b-1584">Outlook for Windows:  set and share your Focused Inbox settings</span></span>

<span data-ttu-id="c493b-1585">[焦點收件匣] 喜好設定會儲存在雲端內，因此當您在任何電腦上使用 Windows 版 Outlook 和 Outlook 網頁版時，都可以取得相同的一致體驗。</span><span class="sxs-lookup"><span data-stu-id="c493b-1585">Your Focused Inbox preferences are stored in the cloud so you can enjoy the same consistent experience when using Outlook for Windows and Outlook on the web on any computer.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="c493b-1586">開始使用：</span><span class="sxs-lookup"><span data-stu-id="c493b-1586">Getting Started:</span></span>

<span data-ttu-id="c493b-1587">在 [檔案] > [選項] > [一般] 索引標籤下，還有一個名為 [將我的 Outlook 設定儲存在雲端中] 的新喜好設定。</span><span class="sxs-lookup"><span data-stu-id="c493b-1587">Under File > Options > General tab, there is a new preference for 'Store my Outlook settings in the cloud'.</span></span> <span data-ttu-id="c493b-1588">使用者需要核取方塊，才能讓他們的 [焦點收件匣] 設定漫遊到其他電腦的 Outlook 安裝和 OWA。</span><span class="sxs-lookup"><span data-stu-id="c493b-1588">Users will need to check the box to enable their Focused Inbox setting to roam to other Desktop Outlook installations and OWA.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="c493b-1589">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="c493b-1589">Scenarios to Try:</span></span>

<span data-ttu-id="c493b-1590">在已開啟雲端設定喜好設定的電腦上變更 [焦點收件匣]。</span><span class="sxs-lookup"><span data-stu-id="c493b-1590">Change Focused Inbox on the machine that has cloud settings preference turned on.</span></span> <span data-ttu-id="c493b-1591">瀏覽至 OWA，然後查看那裡也同樣套用了喜好設定。</span><span class="sxs-lookup"><span data-stu-id="c493b-1591">Navigate to OWA and see the preference applied there as well.</span></span> <span data-ttu-id="c493b-1592">在 OWA 變更 [焦點收件匣]，然後啟動電腦版 Outlook 查看已反映喜好設定。</span><span class="sxs-lookup"><span data-stu-id="c493b-1592">Change Focused Inbox in OWA and start Desktop Outlook to see the preference reflected.</span></span>

### <a name="word"></a><span data-ttu-id="c493b-1593">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-1593">Word</span></span>

#### <a name="learning-tools-mode-has-additional-support-for-more-page-colors"></a><span data-ttu-id="c493b-1594">[學習工具] 模式額外支援更多頁面色彩</span><span class="sxs-lookup"><span data-stu-id="c493b-1594">Learning Tools mode has additional support for more page colors</span></span>

<span data-ttu-id="c493b-1595">Word 中的 [學習工具] 新增更多頁面佈景主題色彩的支援，讓您能夠變更頁面的背景色彩。</span><span class="sxs-lookup"><span data-stu-id="c493b-1595">Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span>  <span data-ttu-id="c493b-1596">許多人在背景全白或全黑時閱讀會有困難，因此我們在 PC 版和 Mac 版 Word 中擴大了色彩選項。</span><span class="sxs-lookup"><span data-stu-id="c493b-1596">Many people have challenges reading with an all-white or all-black background, so we've expanded the choice of colors in Word on PC and Mac.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="c493b-1597">快速入門：</span><span class="sxs-lookup"><span data-stu-id="c493b-1597">Getting Started:</span></span>

<span data-ttu-id="c493b-1598">若要試用，請移至 [檢視] 索引標籤，選擇 [學習工具]，然後選擇 [頁面色彩]。</span><span class="sxs-lookup"><span data-stu-id="c493b-1598">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="c493b-1599">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="c493b-1599">Scenarios to Try:</span></span>

<span data-ttu-id="c493b-1600">若要試用，請移至 [檢視] 索引標籤，選擇 [學習工具]，然後選擇 [頁面色彩]。</span><span class="sxs-lookup"><span data-stu-id="c493b-1600">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-1601">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-1601">Excel</span></span>

#### <a name="elevate-creativity-with-animated-3d-models"></a><span data-ttu-id="c493b-1602">以具備動畫效果的 3D 模型提高創意</span><span class="sxs-lookup"><span data-stu-id="c493b-1602">Elevate Creativity with Animated 3D Models</span></span>

<span data-ttu-id="c493b-1603">Office 現在支援動畫模型，這類模型能在編輯器中播放，讓您的試算表更生動！</span><span class="sxs-lookup"><span data-stu-id="c493b-1603">Office now supports animated models, which will playback in the editor so you can bring your sheets to life!</span></span>

#### <a name="getting-started"></a><span data-ttu-id="c493b-1604">開始使用：</span><span class="sxs-lookup"><span data-stu-id="c493b-1604">Getting Started:</span></span>

1. <span data-ttu-id="c493b-1605">開啟 Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-1605">Open Excel</span></span>
2. <span data-ttu-id="c493b-1606">插入具備動畫效果的 3D 模型 (很快會進到 Remix，但現在請在此位置存取動畫模型：\\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span><span class="sxs-lookup"><span data-stu-id="c493b-1606">Insert an animated 3D Model (coming to Remix soon, but for now, access animated models here: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span></span>
3. <span data-ttu-id="c493b-1607">動畫模型會在編輯器中播放！</span><span class="sxs-lookup"><span data-stu-id="c493b-1607">The animated model will play in the editor!</span></span> <span data-ttu-id="c493b-1608">[檢查投影片放映] 模式 - 動畫模型也會在那裡播放！</span><span class="sxs-lookup"><span data-stu-id="c493b-1608">Check Slideshow mode - it will play there too!</span></span>
4. <span data-ttu-id="c493b-1609">在 3D 格式功能區中，探索模型中更多的動畫場景</span><span class="sxs-lookup"><span data-stu-id="c493b-1609">In the 3D Format Ribbon, explore more animation scenes in the model</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="c493b-1610">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="c493b-1610">Scenarios to Try:</span></span>

1. <span data-ttu-id="c493b-1611">插入動畫模型，然後看它在編輯器中播放</span><span class="sxs-lookup"><span data-stu-id="c493b-1611">Insert an animated model and watch it play in the editor</span></span>
2. <span data-ttu-id="c493b-1612">透過 3D 格式功能區中的 [場景庫]，探索動畫模型中可用的動畫場景</span><span class="sxs-lookup"><span data-stu-id="c493b-1612">Explore the animation scenes available in the animated model via the Scenes Gallery, available in the 3D Format Ribbon</span></span>
3. <span data-ttu-id="c493b-1613">透過功能區、浮動工具列或空格鍵輕鬆地播放/暫停動畫</span><span class="sxs-lookup"><span data-stu-id="c493b-1613">Easily play/pause the animation via the ribbon, floatie or space bar</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="c493b-1614">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="c493b-1614">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="c493b-1615">所有應用程式</span><span class="sxs-lookup"><span data-stu-id="c493b-1615">All Applications</span></span>
- <span data-ttu-id="c493b-1616">我們已修正 Excel 的內容功能表中會出現錯誤應用程式圖示的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1616">We fixed an issue where the incorrect app icon could appear for Excel in contextual menus</span></span>
- <span data-ttu-id="c493b-1617">我們已修正在安裝更新之後 [檔案功能表] 按鈕會消失的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1617">We fixed an issue where the File Menu button could disappear after installing an update</span></span>
- <span data-ttu-id="c493b-1618">我們已修正會變更您的使用者授權的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1618">We fixed an issue which could change your user license</span></span>

### <a name="word"></a><span data-ttu-id="c493b-1619">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-1619">Word</span></span> 
- <span data-ttu-id="c493b-1620">我們已修正文字在特定縮放比例中無法正常顯示的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1620">We fixed an issue where text would not render correctly at certain zoom levels</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-1621">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-1621">Excel</span></span>
- <span data-ttu-id="c493b-1622">我們已修正使用者在進行編輯之後未收到儲存活頁簿提示的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1622">We fixed an issue where users would not be prompted to save a workbook after making edits</span></span>
- <span data-ttu-id="c493b-1623">我們已修正當使用者共用活頁簿時未觸發 BeforeSave 事件的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-1623">We fixed an issue where a BeforeSave event would not be triggered if the user shared the workbook.</span></span>
- <span data-ttu-id="c493b-1624">我們已修正將欄的大小重新調整為小於 6 像素會擲回不正確錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-1624">We fixed an issue where resizing a column to fewer than 6 pixels could throw an incorrect error message.</span></span>
- <span data-ttu-id="c493b-1625">我們已修正 Excel 忽略 Application.Visible 旗標的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1625">We fixed an issue where Excel would ignore the Application.Visible flag</span></span>
- <span data-ttu-id="c493b-1626">我們已修正追蹤箭號保留在非作用中凍結窗格的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1626">We fixed an issue where trace arrows would remain on non-active frozen panes</span></span>
- <span data-ttu-id="c493b-1627">我們已修正在開啟活頁簿時日期和貨幣儲存格格式會變更的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1627">We fixed an issue where cell formatting of dates an currency could change when opening a workbook</span></span>
- <span data-ttu-id="c493b-1628">我們已修正工具提示會意外移動的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1628">We fixed an issue where tooltips would move unexpectedly</span></span>
- <span data-ttu-id="c493b-1629">我們已修正 Power Query 編輯器的當地語系化問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1629">We fixed localization issues for the Power Query editor</span></span>
- <span data-ttu-id="c493b-1630">我們已修正在透過電子郵件傳送時活頁簿附件會遭到移除的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1630">We fixed an issue where a workbook would be removed as an attachment when sending via e-mail</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-1631">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-1631">PowerPoint</span></span>
- <span data-ttu-id="c493b-1632">我們已修正複製圖形會比預期還要久的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1632">We fixed an issue where copying shapes would take longer than expected</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-1633">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-1633">Outlook</span></span>
- <span data-ttu-id="c493b-1634">我們已修正在使用繪圖工具時 Outlook 可能會當機的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1634">We fixed an issue where Outlook could crash while using the drawing tool</span></span>
- <span data-ttu-id="c493b-1635">我們已修正當撰寫 html 電子郵件時的當地語系化問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1635">We fixed a localization issue when composing html e-mails</span></span>
- <span data-ttu-id="c493b-1636">我們已修正使用者在選取下面窗格時會遇到困難的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1636">We fixed an issue where the user would have difficulty in selecting the lower pane</span></span>

### <a name="access"></a><span data-ttu-id="c493b-1637">Access</span><span class="sxs-lookup"><span data-stu-id="c493b-1637">Access</span></span>
- <span data-ttu-id="c493b-1638">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1638">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="c493b-1639">Project</span><span class="sxs-lookup"><span data-stu-id="c493b-1639">Project</span></span>
- <span data-ttu-id="c493b-1640">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1640">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-22-2019"></a><span data-ttu-id="c493b-1641">2019 年 3 月 22 日</span><span class="sxs-lookup"><span data-stu-id="c493b-1641">March 22, 2019</span></span>
<span data-ttu-id="c493b-1642">版本 1904 (組建 11514.20004)</span><span class="sxs-lookup"><span data-stu-id="c493b-1642">Version 1904 (build 11514.20004)</span></span>

## <a name="new-features"></a><span data-ttu-id="c493b-1643">新功能</span><span class="sxs-lookup"><span data-stu-id="c493b-1643">New Features</span></span>

- <span data-ttu-id="c493b-1644">**隱私權控制：** 用於診斷資料和連線體驗的新增、更新及改良的控制項。</span><span class="sxs-lookup"><span data-stu-id="c493b-1644">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> <span data-ttu-id="c493b-1645">深入了解 <https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json></span><span class="sxs-lookup"><span data-stu-id="c493b-1645">Learn more <https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json></span></span>

- <span data-ttu-id="c493b-1646">**Office 圖示有新的外觀：** Office 圖示經過重新設計，以反映簡單、功能強大且智慧型的 Office 體驗。</span><span class="sxs-lookup"><span data-stu-id="c493b-1646">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="c493b-1647">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="c493b-1647">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="c493b-1648">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-1648">Word</span></span> 
- <span data-ttu-id="c493b-1649">我們已修正 UI 經常會顯示「正在檢查變更」的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1649">We fixed an issue where the UI would constantly display "Checking for Changes"</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-1650">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-1650">Excel</span></span>
- <span data-ttu-id="c493b-1651">我們已修正應用程式可能在移動工作表之後當機的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1651">We fixed an issue where the application could crash after moving a worksheet</span></span>
- <span data-ttu-id="c493b-1652">我們已修正應用程式可能在儲存為 PDF 之後當機的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1652">We fixed an issue where the application could crash after saving as a PDF</span></span>
- <span data-ttu-id="c493b-1653">我們已修正儲存對話方塊不會接受某些韓文字元的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1653">We fixed an issue where the save dialog would not accept some Korean characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-1654">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-1654">PowerPoint</span></span>
- <span data-ttu-id="c493b-1655">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1655">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-1656">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-1656">Outlook</span></span>
- <span data-ttu-id="c493b-1657">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1657">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="c493b-1658">Access</span><span class="sxs-lookup"><span data-stu-id="c493b-1658">Access</span></span>
- <span data-ttu-id="c493b-1659">我們已修正 Access 中對 Access 建立額外捷徑的錯誤訊息</span><span class="sxs-lookup"><span data-stu-id="c493b-1659">We fixed the error message in Access where an extra shortcut to Access was created</span></span>
- <span data-ttu-id="c493b-1660">我們已修正來自連結 SharePoint 的資料無法正確顯示的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1660">We fixed an issue where data from a linked SharePoint would display incorrectly</span></span>

### <a name="project"></a><span data-ttu-id="c493b-1661">Project</span><span class="sxs-lookup"><span data-stu-id="c493b-1661">Project</span></span>
- <span data-ttu-id="c493b-1662">我們已修正語言設定會從中文切換為英文的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1662">We fixed an issue where the language settings would switch from Chinese to English</span></span>
- <span data-ttu-id="c493b-1663">我們已修正應用程式可能在同步處理到 SharePoint 時當機的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1663">We fixed an issue where the application could crash when synching to SharePoint</span></span>

</BR></BR>

## <a name="march-15-2019"></a><span data-ttu-id="c493b-1664">2019 年 3 月 15 日</span><span class="sxs-lookup"><span data-stu-id="c493b-1664">March 15, 2019</span></span>
<span data-ttu-id="c493b-1665">版本 1904 (組建 11504.20000)</span><span class="sxs-lookup"><span data-stu-id="c493b-1665">Version 1904 (build 11504.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="c493b-1666">新功能：</span><span class="sxs-lookup"><span data-stu-id="c493b-1666">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="c493b-1667">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-1667">Word</span></span>

#### <a name="focus-mode"></a><span data-ttu-id="c493b-1668">焦點模式</span><span class="sxs-lookup"><span data-stu-id="c493b-1668">Focus Mode</span></span>

<span data-ttu-id="c493b-1669">切換到 [檢視] 功能表中的 [焦點] 以移除令人分心的事物，讓您更能專注於工作。</span><span class="sxs-lookup"><span data-stu-id="c493b-1669">Switch to Focus on the View menu to remove distractions and concentrate on your work.</span></span> <span data-ttu-id="c493b-1670">僅供 Office 365 訂閱者使用。</span><span class="sxs-lookup"><span data-stu-id="c493b-1670">For Office 365 subscribers only.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="c493b-1671">開始使用：</span><span class="sxs-lookup"><span data-stu-id="c493b-1671">Getting Started:</span></span>

<span data-ttu-id="c493b-1672">[檢視] 索引標籤 功能區狀態列中的 [焦點] 按鈕 [焦點] 按鈕</span><span class="sxs-lookup"><span data-stu-id="c493b-1672">View tab "Focus" Button in the Ribbon Status Bar "Focus" Button</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="c493b-1673">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="c493b-1673">Scenarios to Try:</span></span>

<span data-ttu-id="c493b-1674">進入焦點模式，享受專注的體驗</span><span class="sxs-lookup"><span data-stu-id="c493b-1674">Enter Focus Mode and experience the Focused Experience</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="c493b-1675">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="c493b-1675">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="c493b-1676">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-1676">Word</span></span> 
- <span data-ttu-id="c493b-1677">我們已修正以 PDF 格式儲存文件時，文件中影像的 DPI 會不正確的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1677">We fixed an issue where images in a document saved as a PDF would have the incorrect DPI</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-1678">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-1678">Excel</span></span>
- <span data-ttu-id="c493b-1679">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1679">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-1680">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-1680">PowerPoint</span></span>
- <span data-ttu-id="c493b-1681">我們已修正註解窗格無法正確開啟或關閉的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1681">We fixed an issue where the comments pane would not open or close properly</span></span>
- <span data-ttu-id="c493b-1682">我們已修正應用程式會在刪除影片時當機的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1682">We fixed an issue where the application could crash when deleting a video</span></span>
- <span data-ttu-id="c493b-1683">我們已修正於某些情況下應用程式會無法啟動的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1683">We fixed an issue where in some instances the application would fail to launch</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-1684">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-1684">Outlook</span></span>
- <span data-ttu-id="c493b-1685">我們已修正以日文檢視時讀信回條不正確的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1685">We fixed an issue where read receipts were incorrect when viewed in Japanese</span></span>

### <a name="access"></a><span data-ttu-id="c493b-1686">Access</span><span class="sxs-lookup"><span data-stu-id="c493b-1686">Access</span></span>
- <span data-ttu-id="c493b-1687">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1687">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="c493b-1688">Project</span><span class="sxs-lookup"><span data-stu-id="c493b-1688">Project</span></span>
- <span data-ttu-id="c493b-1689">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1689">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-8-2019"></a><span data-ttu-id="c493b-1690">2019 年 3 月 8 日</span><span class="sxs-lookup"><span data-stu-id="c493b-1690">March 8, 2019</span></span> 
<span data-ttu-id="c493b-1691">版本 1903 (組建 11425.20036)</span><span class="sxs-lookup"><span data-stu-id="c493b-1691">Version 1903 (build 11425.20036)</span></span>

## <a name="whats-new"></a><span data-ttu-id="c493b-1692">新功能：</span><span class="sxs-lookup"><span data-stu-id="c493b-1692">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="c493b-1693">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-1693">Word</span></span>

### <a name="find-what-youre-looking-for-with-microsoft-search"></a><span data-ttu-id="c493b-1694">使用 Microsoft Search 尋找您要的內容</span><span class="sxs-lookup"><span data-stu-id="c493b-1694">Find What You're Looking For with Microsoft Search</span></span>

<span data-ttu-id="c493b-1695">您可以使用 Microsoft Search 找到所有檔案、動作、人員，協助您完成工作所需。</span><span class="sxs-lookup"><span data-stu-id="c493b-1695">With Microsoft Search, you can find all the files, actions, people, and help you need to get work done.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="c493b-1696">開始使用：</span><span class="sxs-lookup"><span data-stu-id="c493b-1696">Getting Started:</span></span>

- <span data-ttu-id="c493b-1697">這個功能在標題中的 UI 上方強調顯示。</span><span class="sxs-lookup"><span data-stu-id="c493b-1697">The feature is prominently displayed on top of the UI in the header.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="c493b-1698">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="c493b-1698">Scenarios to Try:</span></span>

- <span data-ttu-id="c493b-1699">搜尋某間大學、最近使用過的文件或搜尋最常用的功能區命令</span><span class="sxs-lookup"><span data-stu-id="c493b-1699">Search for a college, a recent document or search for the ribbon commands you use most often</span></span>
- <span data-ttu-id="c493b-1700">尋找某個主題或主旨並取得更多相關資訊</span><span class="sxs-lookup"><span data-stu-id="c493b-1700">Look up a topic or subject to get more information on it</span></span>
- 
#### <a name="coauthoring"></a><span data-ttu-id="c493b-1701">共同撰寫</span><span class="sxs-lookup"><span data-stu-id="c493b-1701">CoAuthoring</span></span>

<span data-ttu-id="c493b-1702">厭倦於被包含巨集的文件阻礙了嗎？</span><span class="sxs-lookup"><span data-stu-id="c493b-1702">Tired of being locked out of your document with macros?</span></span> <span data-ttu-id="c493b-1703">現在商務用 OneDrive 的 docm 檔案允許同時由多個作者編輯。</span><span class="sxs-lookup"><span data-stu-id="c493b-1703">Now your docm files on OneDrive for Business allow simultaneous editing by multiple authors.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="c493b-1704">開始使用：</span><span class="sxs-lookup"><span data-stu-id="c493b-1704">Getting Started:</span></span>

<span data-ttu-id="c493b-1705">使用者在 UI 中不需要按下任何按鈕，就能存取這項功能。</span><span class="sxs-lookup"><span data-stu-id="c493b-1705">The user doesn't need to press any buttons in the UI to access this feature.</span></span> <span data-ttu-id="c493b-1706">商務用 OneDrive 的 docm 檔案預設已啟用此功能。</span><span class="sxs-lookup"><span data-stu-id="c493b-1706">It is enabled by default on OneDrive for Business docm files.</span></span>
<span data-ttu-id="c493b-1707">因此，使用者應該將 docm 檔案儲存至商務用 OneDrive 試用看看。</span><span class="sxs-lookup"><span data-stu-id="c493b-1707">So, the user should save a docm file to OneDrive for Business to try it out.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="c493b-1708">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="c493b-1708">Scenarios to Try:</span></span>

<span data-ttu-id="c493b-1709">在商務用 OneDrive 建立 docm 檔案、與同事共用並且共同作業！</span><span class="sxs-lookup"><span data-stu-id="c493b-1709">Create a docm file on OneDrive for Business, share it with your colleagues, and collaborate!</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="c493b-1710">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="c493b-1710">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="c493b-1711">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-1711">Word</span></span> 
- <span data-ttu-id="c493b-1712">我們已修正在 [選項] 中按下 ESC 鍵時發生的當機問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1712">We fixed a crashing issue that occurred when pressing 'ESC' while in Options</span></span>
- <span data-ttu-id="c493b-1713">我們已修正回覆註解時發生的當機問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1713">We fixed a crashing issue that occurred when replying to comments</span></span>
- <span data-ttu-id="c493b-1714">我們已修正從 Word 到 PowerPoint Online 的複製與貼上問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1714">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-1715">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-1715">Excel</span></span>
- <span data-ttu-id="c493b-1716">我們已修正當受保護的文件和可編輯的文件在開啟時複製 Excel 儲存格導致高 CPU 使用率的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1716">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-1717">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-1717">PowerPoint</span></span>
- <span data-ttu-id="c493b-1718">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1718">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-1719">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-1719">Outlook</span></span>
- <span data-ttu-id="c493b-1720">我們已修正 Outlook 搜尋未依所選時間順序排序的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1720">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="c493b-1721">我們已修正 [開啟此工作] 工作流程功能區按鈕無法回應特定電子郵件的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1721">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="c493b-1722">我們已修正使用者在 [會議室尋找工具] 中選取可用的會議室後，Outlook 無法清除內部部署會議室的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1722">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="c493b-1723">Access</span><span class="sxs-lookup"><span data-stu-id="c493b-1723">Access</span></span>
- <span data-ttu-id="c493b-1724">我們已修正已儲存的匯入/匯出對話方塊在深色佈景主題中有白色文字在白色背景的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1724">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="c493b-1725">我們已修正使用者在表格設計中無法針對 [文字方塊] 的 [是/否] 欄位設定 DisplayControl 屬性的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1725">We fixed an issue where users could not set the DisplayControl property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="c493b-1726">Project</span><span class="sxs-lookup"><span data-stu-id="c493b-1726">Project</span></span>
- <span data-ttu-id="c493b-1727">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1727">Various performance and stability fixes</span></span>


## <a name="march-1-2019"></a><span data-ttu-id="c493b-1728">2019 年 3 月 1 日</span><span class="sxs-lookup"><span data-stu-id="c493b-1728">March 1, 2019</span></span> 
<span data-ttu-id="c493b-1729">版本 1903 (組建 11414.20014)</span><span class="sxs-lookup"><span data-stu-id="c493b-1729">Version 1903 (build 11414.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="c493b-1730">新功能</span><span class="sxs-lookup"><span data-stu-id="c493b-1730">What's New</span></span>

### <a name="word"></a><span data-ttu-id="c493b-1731">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-1731">Word</span></span>

#### <a name="colors-for-track-changes-comments-and-real-time-collaboration-in-sync"></a><span data-ttu-id="c493b-1732">追蹤修訂、註解和即時共同作業的色彩會同步</span><span class="sxs-lookup"><span data-stu-id="c493b-1732">Colors for Track Changes, Comments and Real-Time Collaboration in Sync</span></span>

<span data-ttu-id="c493b-1733">我們產品中的修正現在可確保註解、追蹤修訂及共同作業者的游標會以相同色彩顯示。</span><span class="sxs-lookup"><span data-stu-id="c493b-1733">Fixes in our product now ensure that the comments, track changes and the cursor for a collaborator show up in the same color.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="c493b-1734">開始使用：</span><span class="sxs-lookup"><span data-stu-id="c493b-1734">Getting Started:</span></span>

<span data-ttu-id="c493b-1735">開啟其他人已開啟的 SharePoint 或 OneDrive 文件。</span><span class="sxs-lookup"><span data-stu-id="c493b-1735">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="c493b-1736">確認使用者的追蹤修訂和註解色彩符合該使用者游標的色彩。</span><span class="sxs-lookup"><span data-stu-id="c493b-1736">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="c493b-1737">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="c493b-1737">Scenarios to Try:</span></span>

<span data-ttu-id="c493b-1738">開啟其他人已開啟的 SharePoint 或 OneDrive 文件。</span><span class="sxs-lookup"><span data-stu-id="c493b-1738">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="c493b-1739">確認使用者的追蹤修訂和註解色彩符合該使用者游標的色彩。</span><span class="sxs-lookup"><span data-stu-id="c493b-1739">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="c493b-1740">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="c493b-1740">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="c493b-1741">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-1741">Word</span></span> 
- <span data-ttu-id="c493b-1742">我們已修正在 [選項] 中按下 ESC 鍵時發生的當機問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1742">We fixed a crashing issue that occurred when pressing 'ESC' while in Options</span></span>
- <span data-ttu-id="c493b-1743">我們已修正從 Word 到 PowerPoint Online 的複製與貼上問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1743">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-1744">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-1744">Excel</span></span>
- <span data-ttu-id="c493b-1745">我們已修正當受保護的文件和可編輯的文件在開啟時複製 Excel 儲存格導致高 CPU 使用率的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1745">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-1746">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-1746">PowerPoint</span></span>
- <span data-ttu-id="c493b-1747">我們已修正在 PowerPoint 中使用 @提及的投影片圖像大小問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1747">We fixed an issue with slide image size when using @Mentions in PowerPoint</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-1748">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-1748">Outlook</span></span>
- <span data-ttu-id="c493b-1749">我們已修正 Outlook 搜尋未依所選時間順序排序的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1749">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="c493b-1750">我們已修正 [開啟此工作] 工作流程功能區按鈕無法回應特定電子郵件的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1750">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="c493b-1751">我們已修正使用者在 [會議室尋找工具] 中選取可用的會議室後，Outlook 無法清除內部部署會議室的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1751">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="c493b-1752">Access</span><span class="sxs-lookup"><span data-stu-id="c493b-1752">Access</span></span>
- <span data-ttu-id="c493b-1753">我們已更新確認使用資料來源重新連結資料表時顯示的提示文字</span><span class="sxs-lookup"><span data-stu-id="c493b-1753">We updated the prompt text that showed when confirming the relinking tables with a datasource</span></span>
- <span data-ttu-id="c493b-1754">我們已修正已儲存的匯入/匯出對話方塊在深色佈景主題中有白色文字在白色背景的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1754">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="c493b-1755">我們已修正使用者在表格設計中無法針對 [文字方塊] 的 [是/否] 欄位設定 [顯示控制項] 屬性的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1755">We fixed an issue where users could not set the Display Control property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="c493b-1756">Project</span><span class="sxs-lookup"><span data-stu-id="c493b-1756">Project</span></span>
- <span data-ttu-id="c493b-1757">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1757">Various performance and stability fixes</span></span>

</BR></BR>



## <a name="february-15-2019"></a><span data-ttu-id="c493b-1758">2019 年 2 月 15 日</span><span class="sxs-lookup"><span data-stu-id="c493b-1758">February 15, 2019</span></span> 
<span data-ttu-id="c493b-1759">版本 1903 (組建 11310.20016)</span><span class="sxs-lookup"><span data-stu-id="c493b-1759">Version 1903 (build 11310.20016)</span></span>

## <a name="whats-new"></a><span data-ttu-id="c493b-1760">新功能：</span><span class="sxs-lookup"><span data-stu-id="c493b-1760">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-1761">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-1761">PowerPoint</span></span>


### <a name="morph-transition-enhancements---morph-by-name"></a><span data-ttu-id="c493b-1762">轉化轉場增強效果 - 依名稱轉化</span><span class="sxs-lookup"><span data-stu-id="c493b-1762">Morph Transition Enhancements - Morph by Name</span></span>

<span data-ttu-id="c493b-1763">選取要轉化的圖形</span><span class="sxs-lookup"><span data-stu-id="c493b-1763">Specify the shapes you want to morph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="c493b-1764">開始使用：</span><span class="sxs-lookup"><span data-stu-id="c493b-1764">Getting Started:</span></span>

- <span data-ttu-id="c493b-1765">若要使轉化將兩個物件視為同一個物件，使用者可以使用 [選取窗格] 重新命名圖形。</span><span class="sxs-lookup"><span data-stu-id="c493b-1765">To get Morph to treat two objects as the same object, the user can rename the shapes using the Selection Pane.</span></span>
- <span data-ttu-id="c493b-1766">名稱前面必須加上「!!」</span><span class="sxs-lookup"><span data-stu-id="c493b-1766">The name must be prefaced with "!!"</span></span> <span data-ttu-id="c493b-1767">(兩個半形驚嘆號)，轉化才能用來覆寫預設比對行為，例如「!!名稱」</span><span class="sxs-lookup"><span data-stu-id="c493b-1767">(two exclamation points) for Morph to use it to override our default matching behavior, e.g. "!!Name"</span></span>
- <span data-ttu-id="c493b-1768">使用者可以繼續將圖形重新命名為不是以「!!」為開頭的任何名稱</span><span class="sxs-lookup"><span data-stu-id="c493b-1768">Users can continue to rename shapes with any name that doesn't start with "!!"</span></span> <span data-ttu-id="c493b-1769">不必擔心會變更轉化的運作方式</span><span class="sxs-lookup"><span data-stu-id="c493b-1769">without worrying that it will change the way Morph works</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="c493b-1770">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="c493b-1770">Scenarios to Try:</span></span>

- <span data-ttu-id="c493b-1771">在投影片中插入圖形，讓我們假設是矩形</span><span class="sxs-lookup"><span data-stu-id="c493b-1771">Insert a Shape in a slide, let's say Rectangle</span></span>
- <span data-ttu-id="c493b-1772">建立新投影片</span><span class="sxs-lookup"><span data-stu-id="c493b-1772">Create a new slide</span></span>
- <span data-ttu-id="c493b-1773">在第 2 張投影片中插入不同的圖形，讓我們假設是三角形</span><span class="sxs-lookup"><span data-stu-id="c493b-1773">Insert a different shape in the 2nd slide, let's say Triangle</span></span>
- <span data-ttu-id="c493b-1774">開啟 [選取窗格]，將投影片 1 中的矩形重新命名為「!!圖形」，將投影片 2 中的三角形重新命名為「!!圖形」</span><span class="sxs-lookup"><span data-stu-id="c493b-1774">Open SelectionPane, rename the Rectangle in slide 1 to "!!shape", and rename the Triangle in slide 2 to "!!shape"</span></span>
- <span data-ttu-id="c493b-1775">將 [轉化] 套用至第 2 張投影片</span><span class="sxs-lookup"><span data-stu-id="c493b-1775">Apply Morph on the 2nd slide</span></span>

</BR>

### <a name="morph-transition-enhancements---smartart"></a><span data-ttu-id="c493b-1776">轉化轉場增強效果 - SmartArt</span><span class="sxs-lookup"><span data-stu-id="c493b-1776">Morph Transition Enhancements - SmartArt</span></span>

<span data-ttu-id="c493b-1777">轉場更順暢的 SmartArt 轉化</span><span class="sxs-lookup"><span data-stu-id="c493b-1777">SmartArt morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="c493b-1778">開始使用：</span><span class="sxs-lookup"><span data-stu-id="c493b-1778">Getting Started:</span></span>

<span data-ttu-id="c493b-1779">您使用 SmartArt 的方式與轉化相同</span><span class="sxs-lookup"><span data-stu-id="c493b-1779">Use Morph the same way you would with SmartArt</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="c493b-1780">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="c493b-1780">Scenarios to Try:</span></span>

- <span data-ttu-id="c493b-1781">在投影片中插入 SmartArt</span><span class="sxs-lookup"><span data-stu-id="c493b-1781">Insert a SmartArt in a slide</span></span>
- <span data-ttu-id="c493b-1782">複製投影片</span><span class="sxs-lookup"><span data-stu-id="c493b-1782">Duplicate the Slide</span></span>
- <span data-ttu-id="c493b-1783">在複製的投影片上調整大小/變更/移動 SmartArt</span><span class="sxs-lookup"><span data-stu-id="c493b-1783">Resize/Change/Move the SmartArt on the duplicated slide</span></span>
- <span data-ttu-id="c493b-1784">在複製的投影片上套用 [轉化]</span><span class="sxs-lookup"><span data-stu-id="c493b-1784">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="morph-transition-enhancements---tables"></a><span data-ttu-id="c493b-1785">轉化轉場增強效果 - 表格​​</span><span class="sxs-lookup"><span data-stu-id="c493b-1785">Morph Transition Enhancements - Tables</span></span>

<span data-ttu-id="c493b-1786">轉場更順暢的表格轉化</span><span class="sxs-lookup"><span data-stu-id="c493b-1786">Tables morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="c493b-1787">開始使用：</span><span class="sxs-lookup"><span data-stu-id="c493b-1787">Getting Started:</span></span>
<span data-ttu-id="c493b-1788">您使用表格的方式與轉化相同</span><span class="sxs-lookup"><span data-stu-id="c493b-1788">Use Morph the same way you would with tables</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="c493b-1789">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="c493b-1789">Scenarios to Try:</span></span>

- <span data-ttu-id="c493b-1790">在投影片中插入表格</span><span class="sxs-lookup"><span data-stu-id="c493b-1790">Insert a Table in a slide</span></span>
- <span data-ttu-id="c493b-1791">複製投影片</span><span class="sxs-lookup"><span data-stu-id="c493b-1791">Duplicate the slide</span></span>
- <span data-ttu-id="c493b-1792">在複製的投影片上調整大小/變更/移動表格</span><span class="sxs-lookup"><span data-stu-id="c493b-1792">Resize/Change/Move the Table on the duplicated slide</span></span>
- <span data-ttu-id="c493b-1793">在複製的投影片上套用 [轉化]</span><span class="sxs-lookup"><span data-stu-id="c493b-1793">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a><span data-ttu-id="c493b-1794">Word、Excel、PowerPoint、OneNote、Access、Project、Publisher 和 Visio</span><span class="sxs-lookup"><span data-stu-id="c493b-1794">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span></span>

### <a name="seamlessly-switch-between-accounts"></a><span data-ttu-id="c493b-1795">在不同帳戶之間順暢切換</span><span class="sxs-lookup"><span data-stu-id="c493b-1795">Seamlessly Switch Between Accounts</span></span>

<span data-ttu-id="c493b-1796">全新的帳戶管理員會在同一個地方顯示您所有的工作和個人帳戶，讓您能控制在其間切換。</span><span class="sxs-lookup"><span data-stu-id="c493b-1796">The new account manager shows all of your work and personal accounts in one place, and puts you in control of switching between them.</span></span> <span data-ttu-id="c493b-1797">這項更新的經驗能清楚知道您的登入方法，因此您現在不需要先登出或處理複雜的對話方塊就可以切換工作和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="c493b-1797">This updated experience makes it clear how you're logged in, and now you can toggle between work and personal accounts without having to sign out first or deal with complex dialogs.</span></span>


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a><span data-ttu-id="c493b-1799">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="c493b-1799">Scenarios to Try:</span></span>
- <span data-ttu-id="c493b-1800">在不同的帳戶之間切換</span><span class="sxs-lookup"><span data-stu-id="c493b-1800">Switch between accounts</span></span>
- <span data-ttu-id="c493b-1801">新增帳戶 [附註：您可能想要先移至 [檔案] | [帳戶] | [已連線服務]，移除任何已連線至工作帳戶的個人服務或是反向服務]</span><span class="sxs-lookup"><span data-stu-id="c493b-1801">Add a new account [Note: you may want to first go to File | Account | Connected Services and remove any personal services connected to work accounts or vice versa]</span></span>
- <span data-ttu-id="c493b-1802">登出帳戶</span><span class="sxs-lookup"><span data-stu-id="c493b-1802">Sign out from an account</span></span>
</BR>

## <a name="notable-fixes"></a><span data-ttu-id="c493b-1803">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="c493b-1803">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="c493b-1804">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-1804">Word</span></span> 
- <span data-ttu-id="c493b-1805">我們已修正表格和影像的內容預覽問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1805">We fixed an issue with context preview for tables & images</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-1806">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-1806">Excel</span></span>
- <span data-ttu-id="c493b-1807">我們已修正在黑色佈景主題中，自動篩選的搜尋欄位中文字是白色的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1807">We fixed an issue where text in autofilter Search field is white in Black theme</span></span>
- <span data-ttu-id="c493b-1808">我們已修正新 Office 增益集的同意 UI 問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1808">We fixed a consent UI issue with New Office Add-in</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-1809">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-1809">PowerPoint</span></span>
- <span data-ttu-id="c493b-1810">我們已修正在膝上型電腦或平板電腦上進行投影片簡報時自動延伸顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="c493b-1810">We fixed an issue with automatically extending display when presenting SlideShows on laptops or tablets.</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-1811">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-1811">Outlook</span></span>
- <span data-ttu-id="c493b-1812">我們已修正 [傳送至 OneNote] 按鈕的顯示問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1812">We fixed an issue with the Send to OneNote button display</span></span>

### <a name="access"></a><span data-ttu-id="c493b-1813">Access</span><span class="sxs-lookup"><span data-stu-id="c493b-1813">Access</span></span>
- <span data-ttu-id="c493b-1814">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1814">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="c493b-1815">Project</span><span class="sxs-lookup"><span data-stu-id="c493b-1815">Project</span></span>
- <span data-ttu-id="c493b-1816">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1816">Various performance and stability fixes</span></span>


</BR></BR>
## <a name="february-11-2019"></a><span data-ttu-id="c493b-1817">2019 年 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="c493b-1817">February 11, 2019</span></span>
<span data-ttu-id="c493b-1818">版本 1903 (組建 11330.20014)</span><span class="sxs-lookup"><span data-stu-id="c493b-1818">Version 1903 (build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="c493b-1819">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="c493b-1819">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="c493b-1820">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-1820">Word</span></span> 
- <span data-ttu-id="c493b-1821">我們已修正某些自訂樣式無法套用至線上 Word 的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1821">We fixed an issue where some customized styles could not be applied to word online</span></span>
- <span data-ttu-id="c493b-1822">我們已修正 Word 中豐富物件的內容預覽問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1822">We fixed Context Preview issues with rich objects in Word</span></span>
- <span data-ttu-id="c493b-1823">我們已修正貼上清單會導致 Word 當機的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1823">We fixed an issue where pasting lists  would result in Word crashing</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-1824">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-1824">Excel</span></span>
- <span data-ttu-id="c493b-1825">我們已修正無貨幣符號時，數字格式後的附加空白不再顯示的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1825">We fixed an issue where appended spaces after number formats are no longer showing when there is no currency symbol</span></span>
- <span data-ttu-id="c493b-1826">我們已修正自動偵測股票的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1826">We fixed an issue with auto detect for stocks</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-1827">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-1827">PowerPoint</span></span>
- <span data-ttu-id="c493b-1828">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1828">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-1829">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-1829">Outlook</span></span>
- <span data-ttu-id="c493b-1830">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1830">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="c493b-1831">Access</span><span class="sxs-lookup"><span data-stu-id="c493b-1831">Access</span></span>
- <span data-ttu-id="c493b-1832">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1832">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="c493b-1833">Project</span><span class="sxs-lookup"><span data-stu-id="c493b-1833">Project</span></span>
- <span data-ttu-id="c493b-1834">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1834">Various performance and stability fixes</span></span>

</BR></BR>


## <a name="february-1-2019"></a><span data-ttu-id="c493b-1835">2019 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="c493b-1835">February 1, 2019</span></span> 
<span data-ttu-id="c493b-1836">版本 1902 (組建 11326.20000)</span><span class="sxs-lookup"><span data-stu-id="c493b-1836">Version 1902 (build 11326.20000)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="c493b-1837">值得注意的修正</span><span class="sxs-lookup"><span data-stu-id="c493b-1837">Notable Fixes</span></span>

### <a name="word"></a><span data-ttu-id="c493b-1838">Word</span><span class="sxs-lookup"><span data-stu-id="c493b-1838">Word</span></span> 
- <span data-ttu-id="c493b-1839">我們已修正內嵌 Excel 表格中調整儲存格大小的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1839">We fixed an issue with resizing cells in an embedded Excel table</span></span>
- <span data-ttu-id="c493b-1840">我們已修正繪圖畫布中複製/貼上圖形的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1840">We fixed an issue with copy/paste of shapes in a Drawing Canvas</span></span>

### <a name="excel"></a><span data-ttu-id="c493b-1841">Excel</span><span class="sxs-lookup"><span data-stu-id="c493b-1841">Excel</span></span>
- <span data-ttu-id="c493b-1842">我們已修正從 Excel Web App 開啟檔案的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1842">We fixed an issue with opening files from the Excel Web app</span></span>
- <span data-ttu-id="c493b-1843">我們已修正因為檔名大小造成 CSV 檔案儲存為 XLSX 失敗的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1843">We fixed an issue where saving a CSV file as .XLSX was failing due to file name size</span></span>
- <span data-ttu-id="c493b-1844">我們已修正快顯功能表顯示快顯功能表選項的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1844">We fixed the context menu to display the context menu options</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c493b-1845">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c493b-1845">PowerPoint</span></span>
- <span data-ttu-id="c493b-1846">我們已修正使用者無法使用鍵盤快速鍵 ctrl+alt+7/ctrl+alt+8 輸入方括號的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1846">We fixed an issued where users were unable to use the keyboard shortcut ctrl+alt+7/ctrl+alt+8 to enter square brackets</span></span>
- <span data-ttu-id="c493b-1847">我們已修正將本機影片插入至 PPT 會減少 'C' 磁碟機磁碟空間的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1847">We fixed an issue where inserting a local video into the PPT would reduce the 'C' drive disk space</span></span>
- <span data-ttu-id="c493b-1848">我們已修正 [發佈至 Microsoft Stream] 按鈕無法向某些使用者顯示的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1848">We fixed the Publish to Microsoft Stream button which was not displaying to some users</span></span>

### <a name="outlook"></a><span data-ttu-id="c493b-1849">Outlook</span><span class="sxs-lookup"><span data-stu-id="c493b-1849">Outlook</span></span>
- <span data-ttu-id="c493b-1850">我們已修正行事曆中工作檢視無法正確顯示工作主旨的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1850">We fixed an issue where the task view in calendar was  not correctly showing the task subject</span></span>

### <a name="access"></a><span data-ttu-id="c493b-1851">Access</span><span class="sxs-lookup"><span data-stu-id="c493b-1851">Access</span></span>
- <span data-ttu-id="c493b-1852">我們已修正圖表的縮放比例的問題</span><span class="sxs-lookup"><span data-stu-id="c493b-1852">We fixed a scaling issue with charts</span></span>

### <a name="project"></a><span data-ttu-id="c493b-1853">Project</span><span class="sxs-lookup"><span data-stu-id="c493b-1853">Project</span></span>
- <span data-ttu-id="c493b-1854">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="c493b-1854">Various performance and stability fixes</span></span>
