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
ms.openlocfilehash: 3ab0d2f47e3efb78f305e175b2ad8bc07f6fad98
ms.sourcegitcommit: 33869248c8872c2d7dc27c265f5ba50bd1598d3f
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/17/2020
ms.locfileid: "43548160"
---
# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="9c296-103">Office 測試人員的版本資訊</span><span class="sxs-lookup"><span data-stu-id="9c296-103">Release Notes for Office Insiders</span></span>

<span data-ttu-id="9c296-104">本文包含 Windows 電腦版 Word、Excel、PowerPoint、Outlook、Access 和 Project 測試人員組建的版本資訊。</span><span class="sxs-lookup"><span data-stu-id="9c296-104">This article contains release notes for Insider builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="9c296-105">我們每週都會強調有趣的新功能、重要修正，以及我們想讓您知道的重大問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-105">Every week, we'll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="9c296-106">請注意，我們在一段時間內會經常推出新功能 (某些時候還有修正) 給測試人員。</span><span class="sxs-lookup"><span data-stu-id="9c296-106">Note that we often roll out features (and sometimes even fixes) to Insiders over a period of time.</span></span> <span data-ttu-id="9c296-107">這樣可讓我們確保功能都運作順利，然後才推出給更廣泛的對象。</span><span class="sxs-lookup"><span data-stu-id="9c296-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="9c296-108">因此，如果您沒有在以下描述的內容中看到某些項目，請不用擔心，您最終還是會看到它。</span><span class="sxs-lookup"><span data-stu-id="9c296-108">So, if you don't see something described below, don't worry you'll get it eventually.</span></span>  

> [!NOTE]
> - <span data-ttu-id="9c296-109">版本資訊會每週發佈，可能是多個組建的編譯。</span><span class="sxs-lookup"><span data-stu-id="9c296-109">Release notes are posted weekly and may be a compilation of multiple builds.</span></span>
> - <span data-ttu-id="9c296-110">版本資訊發佈日期可能與實際組建發行日期不相符。</span><span class="sxs-lookup"><span data-stu-id="9c296-110">The release notes publication date may not match the actual build release date.</span></span>
> - <span data-ttu-id="9c296-111">現有 Office 365 專業增強版安裝上的 Microsoft Teams - 從 6 月底開始，Microsoft Teams 將在更新這些安裝時，新增至 Office 365 專業增強版的 (和 Office 365 商務版) 的現有安裝中。</span><span class="sxs-lookup"><span data-stu-id="9c296-111">Microsoft Teams on existing installations of Office 365 ProPlus - Beginning in late June, Microsoft Teams will be included in existing installations of Office 365 ProPlus (and Office 365 Business) upon updates of these installations.</span></span> <span data-ttu-id="9c296-112">新增 Teams 的日期取決於您使用的更新通道。</span><span class="sxs-lookup"><span data-stu-id="9c296-112">The date when Teams will be added depends on which update channel you're using.</span></span> <span data-ttu-id="9c296-113">如需詳細資訊，請參閱[隨著 Office 365 專業增強版部署 Microsoft Teams](https://docs.microsoft.com/deployoffice/teams-install)。</span><span class="sxs-lookup"><span data-stu-id="9c296-113">Please refer to [Deploy Microsoft Teams with Office 365 ProPlus](https://docs.microsoft.com/deployoffice/teams-install) for additional information.</span></span>

[//]: # (DO NOT REMOVE)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-april-17"></a><span data-ttu-id="9c296-116">版本 2005：4 月 17 日</span><span class="sxs-lookup"><span data-stu-id="9c296-116">Version 2005: April 17</span></span>
<span data-ttu-id="9c296-117">*版本 2005 (組建 12810.20002)*</span><span class="sxs-lookup"><span data-stu-id="9c296-117">*Version 2005 (Build 12810.20002)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="9c296-119">解決的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-119">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="9c296-120">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-120">Excel</span></span>
- <span data-ttu-id="9c296-121">已增加搭配圖表使用的 [自訂誤差線] 對話方塊上儲存格參照 [編輯] 控制項的大小。</span><span class="sxs-lookup"><span data-stu-id="9c296-121">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>
- <span data-ttu-id="9c296-122">在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。</span><span class="sxs-lookup"><span data-stu-id="9c296-122">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>
- <span data-ttu-id="9c296-123">修正列印時表單控制項的核取方塊縮放問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-123">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>
- <span data-ttu-id="9c296-124">在某些情況下，Application.Evaluate (VBA) 無法在使用者定義的函數中運作。</span><span class="sxs-lookup"><span data-stu-id="9c296-124">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>
- <span data-ttu-id="9c296-125">此變更會修正設定格式化的條件 (CF) 資訊無法正確儲存到 XLSB 檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-125">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="9c296-126">OneNote</span><span class="sxs-lookup"><span data-stu-id="9c296-126">OneNote</span></span>
- <span data-ttu-id="9c296-127">修正將分行符號儲存為垂直 Tab 的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-127">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-128">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-128">Outlook</span></span>
- <span data-ttu-id="9c296-129">解決會導致使用者無法將個人連絡人群組新增為會議出席者的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-129">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>
- <span data-ttu-id="9c296-130">解決會導致還有 2 個月時間的會議，無法在排程小幫手中顯示會議主題的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-130">Addresses an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>
- <span data-ttu-id="9c296-131">解決會導致使用者在轉寄大型 HTML 郵件時看到郵件內文截斷的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-131">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>
- <span data-ttu-id="9c296-132">新增透過群組原則強制執行 S/MIME 預設登入設定的功能。</span><span class="sxs-lookup"><span data-stu-id="9c296-132">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>
- <span data-ttu-id="9c296-133">解決會導致為使用者主要信箱以外的信箱所建立的刪除規則變得無效的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-133">Addresses an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>
- <span data-ttu-id="9c296-134">解決在轉寄加密郵件時導致捨棄附件的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-134">Addresses an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

### <a name="project"></a><span data-ttu-id="9c296-135">Project</span><span class="sxs-lookup"><span data-stu-id="9c296-135">Project</span></span>
- <span data-ttu-id="9c296-136">在表單檢視中編輯前置/後續任務資料時，會觸發額外的 ProjectBeforeTaskChange 事件。</span><span class="sxs-lookup"><span data-stu-id="9c296-136">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>
- <span data-ttu-id="9c296-137">修正變更連結至 SharePoint 工作清單之專案的面板狀態欄位時，Project 可能當機的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-137">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>
- <span data-ttu-id="9c296-138">修正儲存使用舊版 Project 建立的專案時，Project 可能當機的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-138">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-april-10"></a><span data-ttu-id="9c296-140">版本 2004：4 月 10 日</span><span class="sxs-lookup"><span data-stu-id="9c296-140">Version 2004: April 10</span></span>
<span data-ttu-id="9c296-141">*版本 2004 (組建 12730.20024)*</span><span class="sxs-lookup"><span data-stu-id="9c296-141">*Version 2004 (Build 12730.20024)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="9c296-143">功能更新</span><span class="sxs-lookup"><span data-stu-id="9c296-143">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="9c296-144">Access</span><span class="sxs-lookup"><span data-stu-id="9c296-144">Access</span></span>

- <span data-ttu-id="9c296-145">**略過 [顯示資料表] 對話方塊，直接移至工作窗格，以及將資料表新增至關係和查詢的程序簡化：** 只要按一下四個索引標籤、將名稱多重選取、依文字搜尋，並從在您工作時維持開啟的工作窗格拖曳，即可新增資料表和查詢。</span><span class="sxs-lookup"><span data-stu-id="9c296-145">**Bypass the Show Table dialog box, go directly to a task pane, and streamline adding tables to relationships and queries.:** Add tables and queries by clicking four tabs, multi-selecting names, searching by text, and dragging from a task pane that stays open while you work.</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-146">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-146">Excel</span></span>

- <span data-ttu-id="9c296-147">**M365 進階版內容選擇器：** 讓您的文件栩栩如生！</span><span class="sxs-lookup"><span data-stu-id="9c296-147">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="9c296-148">探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="9c296-148">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-149">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-149">Outlook</span></span>

- <span data-ttu-id="9c296-150">**M365 進階版內容選擇器：** 讓您的文件栩栩如生！</span><span class="sxs-lookup"><span data-stu-id="9c296-150">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="9c296-151">探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="9c296-151">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="9c296-152">**將圖片作為電子郵件的一部分傳送時，讓圖片保持高畫質：** 一個新 Outlook 設定，可讓您在隨著電子郵件內容傳送圖片時限制圖片壓縮</span><span class="sxs-lookup"><span data-stu-id="9c296-152">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-153">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-153">PowerPoint</span></span>

- <span data-ttu-id="9c296-154">**M365 進階版內容選擇器：** 讓您的文件栩栩如生！</span><span class="sxs-lookup"><span data-stu-id="9c296-154">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="9c296-155">探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="9c296-155">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="9c296-156">**在簡報時同步處理變更：** 即使簡報處於投影片放映模式，仍可即時同步處理所做的變更。</span><span class="sxs-lookup"><span data-stu-id="9c296-156">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="9c296-157">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-157">Word</span></span>

- <span data-ttu-id="9c296-158">**M365 進階版內容選擇器：** 讓您的文件栩栩如生！</span><span class="sxs-lookup"><span data-stu-id="9c296-158">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="9c296-159">探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="9c296-159">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="9c296-160">**標註私人複本：** 製作共用文件的私人複本，以建立只有您本人能夠看到的手寫筆記。</span><span class="sxs-lookup"><span data-stu-id="9c296-160">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="9c296-161">若要開始使用，請移至 [檢視] > [建立私人複本]。</span><span class="sxs-lookup"><span data-stu-id="9c296-161">Go to View > Create a Private Copy to get started.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="9c296-164">解決的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-164">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="9c296-165">Access</span><span class="sxs-lookup"><span data-stu-id="9c296-165">Access</span></span>

- <span data-ttu-id="9c296-166">修正工作窗格中表格的重新調整及重新整理問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-166">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-167">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-167">Excel</span></span>

- <span data-ttu-id="9c296-168">修正在工作表上選取儲存格範圍會導致只選取單一儲存格的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-168">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="9c296-169">修正在為含有 X 軸範圍的圖表縮減大小時，可能會導致 Excel 停止回應的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-169">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="9c296-170">修正插入使用者定義的圖表範本來作為預設值會導致其儲存為直條圖的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-170">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="9c296-171">修正當基礎資料儲存格沒有標題時，圖表上的資料標籤會以空白顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-171">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="9c296-172">修正已啟用 R1C1 儲存格參照且正在共同撰寫/共用的 Excel 工作表，在將游標移到 [使用者目前狀態] 圖示上方時不會以 R1C1 模式顯示作用中儲存格的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-172">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-173">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-173">Outlook</span></span>

- <span data-ttu-id="9c296-174">解決會導致類別有時候會從電子郵件訊息中消失的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-174">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="9c296-175">解決會導致代理人在不同機器上所看到的共用信箱有不同資料夾階層的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-175">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="9c296-176">解決在嘗試檢視組織表單的屬性時，會導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-176">Addresses an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="9c296-177">解決在變更機器上的時區時，會導致某些提醒無法觸發的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-177">Addresses an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-178">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-178">PowerPoint</span></span>

- <span data-ttu-id="9c296-179">此變更修正了在 PowerPoint 或 Word 中呈現內嵌為 OLE 物件的舊版 Excel 圖表時可能不會永遠顯示圖表標題的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-179">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="9c296-180">我們已修正將文字從 Excel 複製到 PowerPoint 時可能會導致其格式設定發生變更的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-180">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="9c296-181">此變更修正了使用 [全字拼寫須相符] 來尋找特殊字元時，不一定能正常運作的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-181">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="9c296-182">Project</span><span class="sxs-lookup"><span data-stu-id="9c296-182">Project</span></span>

- <span data-ttu-id="9c296-183">修正了當開啟保護實際工作的設定時，使用者無法輸入分時期基準工時的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-183">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="9c296-184">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-184">Word</span></span>

- <span data-ttu-id="9c296-185">此變更修正了將游標暫留在提示上不會醒目提示其卡片的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-185">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="9c296-186">此變更修正了使用套索選取工具時，群組圖形中的文字會暫時消失的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-186">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="9c296-187">此變更修正了在 PowerPoint 或 Word 中呈現內嵌為 OLE 物件的舊版 Excel 圖表時可能不會永遠顯示圖表標題的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-187">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="9c296-188">此變更修正了在雙頁檢視中建立註解時，註解錨點不一定會顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-188">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="9c296-189">修正如果段落的樣式是連結至清單的樣式上階，則該清單的編號可能會遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-189">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-march-27"></a><span data-ttu-id="9c296-191">版本 2004：3 月 27 日</span><span class="sxs-lookup"><span data-stu-id="9c296-191">Version 2004: March 27</span></span>
<span data-ttu-id="9c296-192">*版本 2004 (組建 12718.20010)*</span><span class="sxs-lookup"><span data-stu-id="9c296-192">*Version 2004 (Build 12718.20010)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="9c296-194">功能更新</span><span class="sxs-lookup"><span data-stu-id="9c296-194">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="9c296-195">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-195">Outlook</span></span>

- <span data-ttu-id="9c296-196">**在撰寫郵件時有新的選項可停用 @ 提及建議：** 您是否覺得 @ 提及的選擇器很煩人，一點都不好用？</span><span class="sxs-lookup"><span data-stu-id="9c296-196">**New option to disable @ mention suggestions when composing mail:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="9c296-197">現在您可以視需要將其關閉了。</span><span class="sxs-lookup"><span data-stu-id="9c296-197">Now you can turn it off if you prefer.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="9c296-200">解決的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-200">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="9c296-201">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-201">Outlook</span></span>
- <span data-ttu-id="9c296-202">解決了會讓 [附件工具] 中的 [儲存至雲端] 按鈕不見的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-202">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>
- <span data-ttu-id="9c296-203">解決了以下問題：當使用者從檢查程式視窗回覆受到數位版權管理的郵件，卻沒有所回覆郵件的擁有者權限時，使用者會無法新增簽名。</span><span class="sxs-lookup"><span data-stu-id="9c296-203">Addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>
- <span data-ttu-id="9c296-204">解決了以下問題：使用者無法從網頁位置將其他附件新增到先前建立的會議。</span><span class="sxs-lookup"><span data-stu-id="9c296-204">Addresses an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-205">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-205">PowerPoint</span></span>
- <span data-ttu-id="9c296-206">此變更修正了會導致包含 emojis 的 PowerPoint 檔案在儲存時發生失敗的錯誤。</span><span class="sxs-lookup"><span data-stu-id="9c296-206">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

### <a name="project"></a><span data-ttu-id="9c296-207">Project</span><span class="sxs-lookup"><span data-stu-id="9c296-207">Project</span></span>
- <span data-ttu-id="9c296-208">修正了以下問題：如果執行 ' CustomFieldValueListGetItem' 且自訂欄位的查閱資料表不存在，系統會建立一個不應建立的空白查閱資料表。</span><span class="sxs-lookup"><span data-stu-id="9c296-208">Fixed an issue where if 'CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

### <a name="word"></a><span data-ttu-id="9c296-209">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-209">Word</span></span>
- <span data-ttu-id="9c296-210">此變更修正了以下問題：從 [檢視] 功能表選取多個頁面時，其中的 [註解] 窗格會顯示為空白。</span><span class="sxs-lookup"><span data-stu-id="9c296-210">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-march-20"></a><span data-ttu-id="9c296-212">版本 2004：3 月 20 日</span><span class="sxs-lookup"><span data-stu-id="9c296-212">Version 2004: March 20</span></span>
<span data-ttu-id="9c296-213">*版本 2004 (組建 12711.20000)*</span><span class="sxs-lookup"><span data-stu-id="9c296-213">*Version 2004 (Build 12711.20000)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="9c296-215">功能更新</span><span class="sxs-lookup"><span data-stu-id="9c296-215">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="9c296-216">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-216">Outlook</span></span>

- <span data-ttu-id="9c296-217">**行事曆新版視覺效果：** 去年，我們提供了全新的郵件體驗，而今年將為您帶來嶄新的行事曆！</span><span class="sxs-lookup"><span data-stu-id="9c296-217">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar's turn to get a facelift!</span></span> <span data-ttu-id="9c296-218">有幾項更新是新穎卻令人孰悉的，您是經驗豐富的 Outlook 使用者，可以立即使用並提高生產力。</span><span class="sxs-lookup"><span data-stu-id="9c296-218">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

- <span data-ttu-id="9c296-219">**協助保護群組中的資料：** 建立群組時所選擇的「敏感度」標籤會套用到群組電子郵件、文件及小組網站</span><span class="sxs-lookup"><span data-stu-id="9c296-219">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-220">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-220">PowerPoint</span></span>

- <span data-ttu-id="9c296-221">**在投影片放映期間更新投影片：** 在簡報期間，更新由其他作者變更的投影片。</span><span class="sxs-lookup"><span data-stu-id="9c296-221">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="9c296-224">解決的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-224">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="9c296-225">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-225">Excel</span></span>

- <span data-ttu-id="9c296-226">此變更解決了處理格式錯誤或無效通訊協定資訊影像時所導致的延遲問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-226">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-227">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-227">Outlook</span></span>

- <span data-ttu-id="9c296-228">此變更解決了處理格式錯誤或無效通訊協定資訊影像時所導致的延遲問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-228">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="9c296-229">此變更修正了電子郵件草稿最新變更未更新的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-229">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="9c296-230">已修正在檔案上按一下滑鼠右鍵並使用「傳送到」功能無法運作的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-230">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="9c296-231">已修正如果使用者有自訂的 [通訊錄] 搜尋路徑，則 Outlook 的名稱解析範圍會限制為自訂路徑，而不是包括全域通訊清單 (GAL) 的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-231">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="9c296-232">已修正在一組傳回的搜尋結果中，依類別結果排序不會顯示類別色彩的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-232">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

### <a name="project"></a><span data-ttu-id="9c296-233">Project</span><span class="sxs-lookup"><span data-stu-id="9c296-233">Project</span></span>

- <span data-ttu-id="9c296-234">已修正當使用者按一下 [排程群組] 內 [工作] 功能區中的 [停用] 按鈕時，不會觸發 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) 事件的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-234">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the "Inactivate" button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="9c296-235">如果您在 [表單類型] 檢視中設定前置任務或後置任務詳細資訊，則 ProjectBeforeTaskChange Visual Basic Applications (VBA) 事件不會一律擷取變更。</span><span class="sxs-lookup"><span data-stu-id="9c296-235">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="9c296-236">例如，如果刪除了某個相依性，並在表單上按一下 [確定]，則不會觸發該事件。</span><span class="sxs-lookup"><span data-stu-id="9c296-236">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="9c296-237">已修正此問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-237">This behavior has been fixed.</span></span>

- <span data-ttu-id="9c296-238">已修正在進行變更 (例如日期變更) 之後，實際工作成本 (ACWP) 的最新值不會顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-238">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="9c296-239">已修正使用「最近使用」(MRU) 功能表開啟專案時，會使用 [讀取/寫入] 存取權開啟專案的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-239">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="9c296-240">這項變更修正了如果您建立包含開始日期和時間 (但無工期) 的手動工作，則時間表上的時間顯示不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-240">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="9c296-241">已修正使用回曆列印時間表時，會導致列印檢視中略過或重複一個月的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-241">Fixed an issue where printing a timeline using Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="9c296-242">這項變更解決了在團隊規劃中使用 GDI 物件時，可能導致 GDI 物件分配過多並產生記憶體不足的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-242">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

### <a name="word"></a><span data-ttu-id="9c296-243">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-243">Word</span></span>

- <span data-ttu-id="9c296-244">已修正張貼留言功能停用的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-244">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="9c296-245">此變更解決了處理格式錯誤或無效通訊協定資訊影像時所導致的延遲問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-245">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="9c296-246">這項變更解決了帳戶管理員不會分派訊息而導致協力廠商應用程式懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-246">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="9c296-247">這項變更修正了目錄會使用文件中未包含的標題樣式進行更新的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-247">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="9c296-248">已修正在寄送文件時，儲存在 Word 文件中的數位簽章會被刪除的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-248">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-march-13"></a><span data-ttu-id="9c296-250">版本 2004：3 月 13 日</span><span class="sxs-lookup"><span data-stu-id="9c296-250">Version 2004: March 13</span></span>
<span data-ttu-id="9c296-251">*版本 2004 (組建 12703.20010)*</span><span class="sxs-lookup"><span data-stu-id="9c296-251">*Version 2004 (Build 12703.20010)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="9c296-253">功能更新</span><span class="sxs-lookup"><span data-stu-id="9c296-253">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-254">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-254">Excel</span></span>
- <span data-ttu-id="9c296-255">**敏感度標籤**：您現在可以套用組織設定、用來提示您輸入自訂權限的敏感度標籤。</span><span class="sxs-lookup"><span data-stu-id="9c296-255">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="9c296-256">深入了解</span><span class="sxs-lookup"><span data-stu-id="9c296-256">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a><span data-ttu-id="9c296-257">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-257">PowerPoint</span></span>
- <span data-ttu-id="9c296-258">**敏感度標籤**：您現在可以套用組織設定、用來提示您輸入自訂權限的敏感度標籤。</span><span class="sxs-lookup"><span data-stu-id="9c296-258">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="9c296-259">深入了解</span><span class="sxs-lookup"><span data-stu-id="9c296-259">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a><span data-ttu-id="9c296-260">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-260">Word</span></span>
- <span data-ttu-id="9c296-261">**敏感度標籤**：您現在可以套用組織設定、用來提示您輸入自訂權限的敏感度標籤。</span><span class="sxs-lookup"><span data-stu-id="9c296-261">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="9c296-262">深入了解</span><span class="sxs-lookup"><span data-stu-id="9c296-262">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="9c296-265">解決的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-265">Resolved issues</span></span>

### <a name="access"></a><span data-ttu-id="9c296-266">Access</span><span class="sxs-lookup"><span data-stu-id="9c296-266">Access</span></span>
- <span data-ttu-id="9c296-267">修正國際版 Access 在使用者介面中顯示英文字串的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-267">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-268">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-268">Excel</span></span>
- <span data-ttu-id="9c296-269">修正使用者在以程式設計方式編輯大量儲存格範圍時可能遇到的效能問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-269">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>
- <span data-ttu-id="9c296-270">修正以日文環境開啟 CSV 檔案時發生的效能問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-270">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-271">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-271">Outlook</span></span>
- <span data-ttu-id="9c296-272">解決將附件新增至郵件或從郵件拖放 (與透過功能表相對) 來儲存附件時，導致檔案的「上次修改」日期更新的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-272">Addresses an issue that caused the "Last Modified"; date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>
- <span data-ttu-id="9c296-273">解決會導致在展開的尋找窗格中按一下 Enter 時無法開始搜尋，而是會要求使用者按一下 [搜尋] 按鈕的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-273">Addresses an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>
- <span data-ttu-id="9c296-274">修正將 [如果有，顯示使用者的照片] 選項停用時，搜尋不會顯示有關使用者的任何資訊的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-274">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>

### <a name="project"></a><span data-ttu-id="9c296-275">Project</span><span class="sxs-lookup"><span data-stu-id="9c296-275">Project</span></span>
- <span data-ttu-id="9c296-276">修正無法正確計算摘要工作日期的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-276">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>
- <span data-ttu-id="9c296-277">修正不先執行 OpenUndoTransaction 方法就不能觸發 OnUndoOrRedo 事件的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-277">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="9c296-278">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-278">Word</span></span>
- <span data-ttu-id="9c296-279">修正輸入或編輯備註然後使用 Ctrl+A 時，會導致選取畫布中的文字，而不只是選取備註卡片內文字的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-279">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>
- <span data-ttu-id="9c296-280">我們已修正文件中的文字對齊，在使用 [快速列印] 進行列印之後嘗試進行編輯時變得混亂的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-280">We fixed an issue in which the alignment of words in a document gets scrambled when tried to edit after printing using Quick Print.</span></span>
- <span data-ttu-id="9c296-281">我們已修正將兩份文件合併成一份文件時的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-281">We fixed an issue when merging two documents into one document.</span></span>
- <span data-ttu-id="9c296-282">修正標示的修訂若與方程式有關，在儲存檔案時可能會導致失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-282">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-march-06"></a><span data-ttu-id="9c296-284">版本 2003：3 月 6 日</span><span class="sxs-lookup"><span data-stu-id="9c296-284">Version 2003: March 06</span></span>
<span data-ttu-id="9c296-285">*版本 2003 (組建 12624.20086)*</span><span class="sxs-lookup"><span data-stu-id="9c296-285">*Version 2003 (Build 12624.20086)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="9c296-287">解決的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-287">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="9c296-288">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-288">Outlook</span></span>

- <span data-ttu-id="9c296-289">修正使用 Outlook Web Access 建立規則時不會保存到 Exchange 伺服器，並導致衝突的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-289">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>
- <span data-ttu-id="9c296-290">修正 Outlook 在深色模式中不會在 [寄件者:] 欄位中顯示下拉式清單的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-290">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>
- <span data-ttu-id="9c296-291">解決在其他應用程式中開啟某個檔案時，導致使用者無法透過檔案總管將該檔案附加至郵件訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-291">Addresses an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-292">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-292">PowerPoint</span></span>

- <span data-ttu-id="9c296-293">修正將滑鼠移至縮圖上時，建議的縮圖閃動的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-293">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="9c296-294">在某些情況下，這可能會導致 PowerPoint 當機。</span><span class="sxs-lookup"><span data-stu-id="9c296-294">In some cases this could cause PowerPoint to crash.</span></span>

### <a name="word"></a><span data-ttu-id="9c296-295">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-295">Word</span></span>

- <span data-ttu-id="9c296-296">修正受保護無法編輯之文件的比較功能問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-296">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

### <a name="office-suite"></a><span data-ttu-id="9c296-297">Office 套件</span><span class="sxs-lookup"><span data-stu-id="9c296-297">Office Suite</span></span>

- <span data-ttu-id="9c296-298">修正 Word/Excel/PowerPoint 中的使用者主體名稱 (UPN) 不再區分大小寫，導致在 SharePoint 上使用檔案時較少發生失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-298">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="9c296-299">修正 [檔案]\[選項] 對話方塊上的 [確定] 按鈕顯示為灰色停用狀態，但功能並未受影響的外觀問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-299">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog was being displayed as grayed out but functionality was not impacted.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

## <a name="version-2003-february-28"></a><span data-ttu-id="9c296-302">版本 2003：2 月 28 日</span><span class="sxs-lookup"><span data-stu-id="9c296-302">Version 2003: February 28</span></span>
<span data-ttu-id="9c296-303">*版本 2003 (組建 12619.20002)*</span><span class="sxs-lookup"><span data-stu-id="9c296-303">*Version 2003 (Build 12619.20002)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="9c296-305">功能更新</span><span class="sxs-lookup"><span data-stu-id="9c296-305">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="9c296-306">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-306">Outlook</span></span>

- <span data-ttu-id="9c296-307">**IT 系統管理員的事件通知：** Microsoft 365 租用戶全域系統管理員和 Office 應用程式系統會在 Windows 版 Outlook 的新右側面板中收到影響其使用者的 Outlook 和 O365 Exchange 事件通知。</span><span class="sxs-lookup"><span data-stu-id="9c296-307">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-308">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-308">PowerPoint</span></span>

- <span data-ttu-id="9c296-309">**改善筆跡轉換圖形圖表製作體驗：** 繪製更完善的圖表，並將它轉換成您可處理的 Office 物件。[深入了解](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span><span class="sxs-lookup"><span data-stu-id="9c296-309">**Improved ink to shape diagramming experience:** Draw better diagrams and have it convert so office object you can manipulate [Learn more](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="9c296-312">解決的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-312">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="9c296-313">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-313">Excel</span></span>

- <span data-ttu-id="9c296-314">已修正交叉分析篩選器中的文字在預覽列印中無法正確縮放的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-314">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-315">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-315">Outlook</span></span>

- <span data-ttu-id="9c296-316">解決將附件新增至郵件或從郵件拖放 (與透過功能表相對) 來儲存附件時，導致檔案的「上次修改」日期更新的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-316">Addresses an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

### <a name="word"></a><span data-ttu-id="9c296-317">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-317">Word</span></span>

- <span data-ttu-id="9c296-318">修正按 Tab 鍵導覽註解卡片時，註解編輯方塊上的焦點無法顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-318">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="9c296-319">在方程式中插入控制項 (例如文字內容控制項)，然後儲存再開啟檔案，便會導致內容無法讀取的錯誤。</span><span class="sxs-lookup"><span data-stu-id="9c296-319">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="9c296-320">修正將先前使用密碼保護的檔案儲存到雲端儲存空間無法運作的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-320">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

### <a name="office-suite"></a><span data-ttu-id="9c296-321">Office 套件</span><span class="sxs-lookup"><span data-stu-id="9c296-321">Office Suite</span></span>

- <span data-ttu-id="9c296-322">修正在 Word/Excel/PowerPoint 中開啟來自相同 SharePoint 文件庫的多個文件時，僅掃描開啟的第一個文件是否符合原則的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-322">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-february-21"></a><span data-ttu-id="9c296-324">版本 2003：2 月 21 日</span><span class="sxs-lookup"><span data-stu-id="9c296-324">Version 2003: February 21</span></span>
<span data-ttu-id="9c296-325">*版本 2003 (組建 12615.20000)*</span><span class="sxs-lookup"><span data-stu-id="9c296-325">*Version 2003 (Build 12615.20000)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="9c296-327">功能更新</span><span class="sxs-lookup"><span data-stu-id="9c296-327">Feature updates</span></span>
### <a name="office-suite"></a><span data-ttu-id="9c296-328">Office 套件</span><span class="sxs-lookup"><span data-stu-id="9c296-328">Office Suite</span></span>

- <span data-ttu-id="9c296-329">**挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。</span><span class="sxs-lookup"><span data-stu-id="9c296-329">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="9c296-332">解決的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-332">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-333">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-333">Excel</span></span>
- <span data-ttu-id="9c296-334">已修正使用者在重新命名樞紐分析表度量值時可能遇到的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-334">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>
- <span data-ttu-id="9c296-335">已修正使用者在使用 VBA 巨集清除範圍內容時可能遇到的效能問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-335">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>
- <span data-ttu-id="9c296-336">已修正當使用者執行與功能區互動的巨集時，導致 UI 快閃的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-336">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>
- <span data-ttu-id="9c296-337">已修正當檔案中的第一個字為 TABLE 時，CSV 檔案載入錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-337">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>
- <span data-ttu-id="9c296-338">已修正當您在兩個具有不同縮放比例的活頁簿之間切換時，使用者可能遇到的當機問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-338">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-339">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-339">Outlook</span></span>
- <span data-ttu-id="9c296-340">已解決當持續整夜執行 Outlook 時，導致使用者無法開啟公用資料夾訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-340">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>
- <span data-ttu-id="9c296-341">已修正在新增 Gmail 帳戶的驗證工作流程中，[權限] 頁面上的 [允許] 和 [拒絕] 按鈕停用的爭用情況。</span><span class="sxs-lookup"><span data-stu-id="9c296-341">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>
- <span data-ttu-id="9c296-342">已解決即使已關閉記錄，在某些情況下仍導致 Outlook 異常產生記錄輸出的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-342">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

### <a name="word"></a><span data-ttu-id="9c296-343">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-343">Word</span></span>
- <span data-ttu-id="9c296-344">已修正當滑鼠指標暫留在註解卡片上方時，未醒目提示註解卡片的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-344">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>
- <span data-ttu-id="9c296-345">在使用中的文件共同撰寫工作階段中，直接在註解卡片中新增影像可能會導致新增標籤。</span><span class="sxs-lookup"><span data-stu-id="9c296-345">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="9c296-346">我們已修正此問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-346">This issue has been fixed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="9c296-347">Office 套件</span><span class="sxs-lookup"><span data-stu-id="9c296-347">Office Suite</span></span>
- <span data-ttu-id="9c296-348">當您將 Multichoice/Lookup/Managed-metadata 屬性與 Word/Excel/PowerPoint 文件一起使用並儲存至 SharePoint 文件庫時，這些屬性之前限制為 255 個字元。</span><span class="sxs-lookup"><span data-stu-id="9c296-348">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="9c296-349">當這些屬性超過 255 個字元時，這類文件就無法儲存。</span><span class="sxs-lookup"><span data-stu-id="9c296-349">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="9c296-350">在此變更中，此限制已增加到 2048 個字元。</span><span class="sxs-lookup"><span data-stu-id="9c296-350">With this change, this limit has been increased to 2048 characters.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-february-14"></a><span data-ttu-id="9c296-352">版本 2003：2 月 14 日</span><span class="sxs-lookup"><span data-stu-id="9c296-352">Version 2003: February 14</span></span>
<span data-ttu-id="9c296-353">*版本 2003 (組建 12607.20000)*</span><span class="sxs-lookup"><span data-stu-id="9c296-353">*Version 2003 (Build 12607.20000)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="9c296-355">功能更新</span><span class="sxs-lookup"><span data-stu-id="9c296-355">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="9c296-356">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-356">Outlook</span></span>

- <span data-ttu-id="9c296-357">**受限 WiFi 網路的新體驗：** 是否曾經加入需要登入網頁的 WiFi 網路呢？</span><span class="sxs-lookup"><span data-stu-id="9c296-357">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="9c296-358">Outlook 現在會偵測這項要求並協助您取得連結。</span><span class="sxs-lookup"><span data-stu-id="9c296-358">Outlook now detects this and helps you get connected.</span></span>

### <a name="word"></a><span data-ttu-id="9c296-359">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-359">Word</span></span>

- <span data-ttu-id="9c296-360">**在繪圖工具箱中找到筆跡編輯器：** 選取 [繪圖]，然後選擇 [筆跡編輯器] 手寫筆以使用手指或數位筆編輯文件。</span><span class="sxs-lookup"><span data-stu-id="9c296-360">**Find Ink Editor in your drawing toolbox:** Select Draw and then choose the Ink Editor pen to edit your document with your finger or a digital pen.</span></span> [<span data-ttu-id="9c296-361">深入了解</span><span class="sxs-lookup"><span data-stu-id="9c296-361">Learn more</span></span>](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

### <a name="office-suite"></a><span data-ttu-id="9c296-362">Office 套件</span><span class="sxs-lookup"><span data-stu-id="9c296-362">Office Suite</span></span>

- <span data-ttu-id="9c296-363">**更清楚的狀態列圖示：** 狀態列圖示現在更容易查看</span><span class="sxs-lookup"><span data-stu-id="9c296-363">**Clearer status bar icons:** Status bar icons are now easier to see</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="9c296-366">解決的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-366">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="9c296-367">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-367">Outlook</span></span>

- <span data-ttu-id="9c296-368">已解決導致使用者無法存取「空閒/忙碌選項」行事曆權限對話方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-368">Addressed an issue that caused users to lose access to the "Free Busy Options" calendar permissions dialog.</span></span>

- <span data-ttu-id="9c296-369">修正了開啟某些從不同時區傳送的週期性會議執行個體時，可能會導致出現警示：「很抱歉，無法開啟這此項目」的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-369">Fixed an issue that may result in the alert: "Sorry we're having trouble opening this item" when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="9c296-370">已解決從該郵件拖放附件後造成使用者無法重新開啟 .msg 檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-370">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="9c296-371">修正從 Outlook 上傳檔案附件到 OneDrive 後，造成包含括號之附件名稱的檔案名稱被變更。</span><span class="sxs-lookup"><span data-stu-id="9c296-371">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-372">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-372">PowerPoint</span></span>

- <span data-ttu-id="9c296-373">修正儲存包含 Excel 圖表的 PowerPoint 或 Word 文件會導致失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-373">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>

### <a name="word"></a><span data-ttu-id="9c296-374">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-374">Word</span></span>

- <span data-ttu-id="9c296-375">修正文件中的圖片在匯出成 PDF 後，會失去透明度的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-375">Fixed an issue where pictures in documents lose transparency when exported to PDF.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-february-07"></a><span data-ttu-id="9c296-377">版本 2002：2 月 7 日</span><span class="sxs-lookup"><span data-stu-id="9c296-377">Version 2002: February 07</span></span>
<span data-ttu-id="9c296-378">*版本 2002 (組建 12527.20040)*</span><span class="sxs-lookup"><span data-stu-id="9c296-378">*Version 2002 (Build 12527.20040)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="9c296-380">功能更新</span><span class="sxs-lookup"><span data-stu-id="9c296-380">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="9c296-381">Access</span><span class="sxs-lookup"><span data-stu-id="9c296-381">Access</span></span>

- <span data-ttu-id="9c296-382">**在查詢設計工具、SQL 檢視和關聯視窗中工作時更具生產力：** 在資料表上按一下滑鼠右鍵即可開啟、設計、調整大小及隱藏它。</span><span class="sxs-lookup"><span data-stu-id="9c296-382">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="9c296-383">在 SQL 檢視中搜尋及取代文字。</span><span class="sxs-lookup"><span data-stu-id="9c296-383">Search and replace text in SQL View.</span></span> <span data-ttu-id="9c296-384">在 [關聯圖] 視窗中選取多個資料表。</span><span class="sxs-lookup"><span data-stu-id="9c296-384">Select multiple tables in the Relationships window.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="9c296-387">解決的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-387">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="9c296-388">Access</span><span class="sxs-lookup"><span data-stu-id="9c296-388">Access</span></span>

- <span data-ttu-id="9c296-389">此更新會修正使用 ADODB 的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-389">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="9c296-390">VB 程式碼中的記錄器物件可能會不正確地報告錯誤。</span><span class="sxs-lookup"><span data-stu-id="9c296-390">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="9c296-391">此更新修正可能會導致 Microsoft Access 無法識別連結的 SQL Server 資料表中的識別資料行的問題，這可能會導致不正確地將資料列報告為已刪除。</span><span class="sxs-lookup"><span data-stu-id="9c296-391">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-392">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-392">Excel</span></span>

- <span data-ttu-id="9c296-393">修正使用「資料剖析」搭配動態陣列時，Excel 會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-393">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-394">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-394">Outlook</span></span>

- <span data-ttu-id="9c296-395">修正以月檢視在行事曆中捲動時，無法顯示之前的行事曆活動的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-395">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="9c296-396">解決在 Citrix 環境中檢視 30 個以上的行事曆時，導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-396">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-397">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-397">PowerPoint</span></span>

- <span data-ttu-id="9c296-398">修正關閉檔案之後，如果有任何事件處理常式正在執行，PowerPoint 就不會立即將它從 [簡報] 集合中移除的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-398">Fixed an issue where after closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="9c296-399">因此，物件模型報告的開啟中簡報數目會不正確，且會防止關閉 PowerPoint。</span><span class="sxs-lookup"><span data-stu-id="9c296-399">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>

- <span data-ttu-id="9c296-400">修正具有深色螢光筆色彩的白色文字，在灰階中會以黑色列印的螢光筆問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-400">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="9c296-401">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-401">Word</span></span>

- <span data-ttu-id="9c296-402">更新和瀏覽目錄時，有時可能會在文件上顯示灰色區域的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-402">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>

- <span data-ttu-id="9c296-403">修正共同撰寫文件時，可能不會保留根註解的草稿版本的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-403">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>

- <span data-ttu-id="9c296-404">已修正在註解卡片之間來回切換時，有時會顯示一開始選取的註解，並將某選取範圍醒目提示的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-404">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>

- <span data-ttu-id="9c296-405">修正在已撰寫註解但未張貼，且使用者嘗試儲存檔案的情況下，使用 [瀏覽] 來儲存檔案沒有作用的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-405">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>

- <span data-ttu-id="9c296-406">將 SlideTrack 啟用且 [註解] 窗格關閉時，Ctrl+Alt+M 可能無法開啟 [註解] 窗格的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-406">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>

- <span data-ttu-id="9c296-407">修正在表格中新增 @提及時可能發生錯誤訊息：「文件中的表格已經毀損」的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-407">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>

### <a name="office-suite"></a><span data-ttu-id="9c296-408">Office 套件</span><span class="sxs-lookup"><span data-stu-id="9c296-408">Office Suite</span></span>

- <span data-ttu-id="9c296-409">解決可能導致挪威耐諾斯克 (nn-no) 校訂工具套件安裝不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-409">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-january-31"></a><span data-ttu-id="9c296-411">版本 2002：1 月 31 日</span><span class="sxs-lookup"><span data-stu-id="9c296-411">Version 2002: January 31</span></span>
<span data-ttu-id="9c296-412">*版本 2002 (組建 12513.20010)*</span><span class="sxs-lookup"><span data-stu-id="9c296-412">*Version 2002 (Build 12513.20010)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="9c296-414">功能更新</span><span class="sxs-lookup"><span data-stu-id="9c296-414">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="9c296-415">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-415">Excel</span></span>

- <span data-ttu-id="9c296-416">**即時讀取與回覆：** 直接從電子郵件回覆註解和提及，而不需開啟活頁簿。</span><span class="sxs-lookup"><span data-stu-id="9c296-416">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="9c296-417">**查詢編輯器中的資料分析：** 取得欄位資料的概覽分析、識別錯誤和空白值，查看分佈長條圖等。</span><span class="sxs-lookup"><span data-stu-id="9c296-417">**Data Profiling in Query Editor:** Get-a-glance analysis of the data in your columns, identify error and empty values, see distribution histograms and more.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="9c296-420">解決的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-420">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="9c296-421">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-421">Outlook</span></span>

- <span data-ttu-id="9c296-422">修正根據保留原則到期的電子郵件會顯示兩個標籤的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-422">Fixed an issue where emails expiring based on a retention policy would display two labels.</span></span> <span data-ttu-id="9c296-423">其中一個顯示郵件將在一天內過期，另一個則顯示將在兩天內到期。</span><span class="sxs-lookup"><span data-stu-id="9c296-423">One showing that the mail will expire in one day and another displaying that it will expire in two days.</span></span>

### <a name="word"></a><span data-ttu-id="9c296-424">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-424">Word</span></span>

- <span data-ttu-id="9c296-425">修正在具有「反轉」頁面色彩的閱讀模式中，備註提示未顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-425">Fixed an issue where comment hint was not visible in read mode with &quot;Inverse&quot; page color.</span></span>

- <span data-ttu-id="9c296-426">修正在編輯備註之後將文字設為斜體然後再張貼，斜體格式設定遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-426">Fixed an issue where italics formatting is lost after editing a comment, italicizing the text and then posting it.</span></span>

- <span data-ttu-id="9c296-427">修正備註內容功能表中的備註命令 (編輯備註、回覆備註、刪除備註、解決備註) 未顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-427">Fixed an issue where comment commands (Edit comment, Reply to comment, Delete comment, Resolve comment) in the comments context menu were not being displayed.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-january-17"></a><span data-ttu-id="9c296-429">版本 2002：1 月 17 日</span><span class="sxs-lookup"><span data-stu-id="9c296-429">Version 2002: January 17</span></span>
<span data-ttu-id="9c296-430">*版本 2002 (組建 12508.20000)*</span><span class="sxs-lookup"><span data-stu-id="9c296-430">*Version 2002 (Build 12508.20000)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="9c296-432">功能更新</span><span class="sxs-lookup"><span data-stu-id="9c296-432">Feature updates</span></span>
### <a name="word"></a><span data-ttu-id="9c296-433">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-433">Word</span></span>

- <span data-ttu-id="9c296-434">**提及和註解通知電子郵件目前包含預覽：** 提及和註解的電子郵件通知現在包含註解文字的預覽，以及該註解所參照的內容。</span><span class="sxs-lookup"><span data-stu-id="9c296-434">**Mention & comment notification emails now contain previews:** Email notifications for mentions & comments will now include previews of the comment text and context for what it is referring to.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="9c296-437">解決的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-437">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="9c296-438">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-438">Excel</span></span>

- <span data-ttu-id="9c296-439">在某些情況下，協助工具檢查程式不會顯示圖案​​建議的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-439">In some cases, the Accessibility checker would not show the recommendations for shapes.</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-440">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-440">Outlook</span></span>

- <span data-ttu-id="9c296-441">儲存在左側瀏覽窗格 [我的最愛] 的資料夾可能會間歇性消失。</span><span class="sxs-lookup"><span data-stu-id="9c296-441">Folders saved in 'Favorites' in the left navigation pane may intermittently disappear.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-442">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-442">PowerPoint</span></span>

- <span data-ttu-id="9c296-443">已修正使用 PowerPoint 筆跡動畫時，無法完整轉譯或跳過的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-443">Fixed an issue where Ink may not render completely or get skipped when used in a PowerPoint ink animations.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2001-january-10"></a><span data-ttu-id="9c296-445">版本 2001：1 月 10 日</span><span class="sxs-lookup"><span data-stu-id="9c296-445">Version 2001: January 10</span></span>
<span data-ttu-id="9c296-446">*版本 2001 (組建 12430.20000)*</span><span class="sxs-lookup"><span data-stu-id="9c296-446">*Version 2001 (Build 12430.20000)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="9c296-448">功能更新</span><span class="sxs-lookup"><span data-stu-id="9c296-448">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="9c296-449">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-449">Excel</span></span>
- <span data-ttu-id="9c296-450">**將圖形另存為圖片：** 只要按幾下，即可將圖形、圖示或其他物件另存成圖片，便於您於任何其他地方使用。</span><span class="sxs-lookup"><span data-stu-id="9c296-450">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="9c296-451">深入了解</span><span class="sxs-lookup"><span data-stu-id="9c296-451">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

### <a name="outlook"></a><span data-ttu-id="9c296-452">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-452">Outlook</span></span>
- <span data-ttu-id="9c296-453">**使用者現在可以將 Word/Excel/Outlook 中的物件另存為 Windows 的圖片：** 如同在 PowerPoint 中已具有的功能，使用者現在可以將 Word、Excel 和 Outlook 中的物件另存為圖片。</span><span class="sxs-lookup"><span data-stu-id="9c296-453">**User can now save objects in Word/Excel/Outlook as a picture for Windows.:** With the ability already seen in PowerPoint, users can now save objects in Word, Excel and Outlook as a picture.</span></span> <span data-ttu-id="9c296-454">物件包括圖形、圖示、圖片及其他內容！</span><span class="sxs-lookup"><span data-stu-id="9c296-454">Objects include shapes, icons, pictures, and more!</span></span> <span data-ttu-id="9c296-455">此功能只要按滑鼠右鍵的功能表就能存取。</span><span class="sxs-lookup"><span data-stu-id="9c296-455">This can be accessed through the right-click menu.</span></span>

### <a name="word"></a><span data-ttu-id="9c296-456">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-456">Word</span></span>
- <span data-ttu-id="9c296-457">**只要在 Word 中繪製圖形即可輕鬆選取筆跡：** [繪圖] 索引標籤上的 [套索] 工具可協助您選取使用筆跡繪製的物件。</span><span class="sxs-lookup"><span data-stu-id="9c296-457">**Easily select ink in Word by drawing a shape around it.:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="9c296-458">選取個別筆劃或整個字。</span><span class="sxs-lookup"><span data-stu-id="9c296-458">Select individual strokes, or whole words.</span></span> <span data-ttu-id="9c296-459">當您有大量筆跡但只想要使用其中一部分時，這功能尤其方便。</span><span class="sxs-lookup"><span data-stu-id="9c296-459">It's handy when you have lots of ink and you only want to work with some of it.</span></span> [<span data-ttu-id="9c296-460">深入了解</span><span class="sxs-lookup"><span data-stu-id="9c296-460">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="9c296-461">**將圖形另存為圖片：** 只要按幾下，即可將圖形、圖示或其他物件另存成圖片，便於您於任何其他地方使用。</span><span class="sxs-lookup"><span data-stu-id="9c296-461">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="9c296-462">深入了解</span><span class="sxs-lookup"><span data-stu-id="9c296-462">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="9c296-465">解決的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-465">Resolved issues</span></span>
### <a name="onenote"></a><span data-ttu-id="9c296-466">OneNote</span><span class="sxs-lookup"><span data-stu-id="9c296-466">OneNote</span></span>
- <span data-ttu-id="9c296-467">100% 解析度時，頁面索引標籤可能會顯得太小並過於接近。</span><span class="sxs-lookup"><span data-stu-id="9c296-467">Page tabs may appear too small and close together at 100% resolution.</span></span>

### <a name="word"></a><span data-ttu-id="9c296-468">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-468">Word</span></span>
- <span data-ttu-id="9c296-469">在大量的註解組合中，刪除接近註解清單結尾附近的註解，可能會導致窗格捲動到最上方。</span><span class="sxs-lookup"><span data-stu-id="9c296-469">In a large set of comments, deleting a comment near the end of the list of comments may result in the pane scrolling all the way to the top.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2001-january-03"></a><span data-ttu-id="9c296-471">版本 2001：1 月 3 日</span><span class="sxs-lookup"><span data-stu-id="9c296-471">Version 2001: January 03</span></span>
<span data-ttu-id="9c296-472">*版本 2001 (組建 12425.20000)*</span><span class="sxs-lookup"><span data-stu-id="9c296-472">*Version 2001 (Build 12425.20000)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="9c296-474">解決的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-474">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-475">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-475">Excel</span></span>
- <span data-ttu-id="9c296-476">有些框線在 A4 大小的紙張上可能無法如預期列印。</span><span class="sxs-lookup"><span data-stu-id="9c296-476">Some border lines may not print as expected on A4 size paper.</span></span>
- <span data-ttu-id="9c296-477">使用 VBA 將影像新增到工作表圖表物件的頁首/頁尾可能會導致錯誤。</span><span class="sxs-lookup"><span data-stu-id="9c296-477">Adding an image to the header/footer of a chart object on a sheet using VBA may result in an error.</span></span>
- <span data-ttu-id="9c296-478">設定圖表座標軸格式時，標籤之間的間隔限制為 255。</span><span class="sxs-lookup"><span data-stu-id="9c296-478">When formatting a chart axis, the interval between labels was limited to 255.</span></span>
- <span data-ttu-id="9c296-479">已修正嘗試重新整理 XML 查詢 (資料來源 URL 遭截斷) 時發生錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-479">Fixed an issue where an error would occur trying to refresh an XML query in which the URL to the datasource was being truncated.</span></span>
- <span data-ttu-id="9c296-480">活頁簿統計資料會報告所有開啟的活頁簿 (包括個人巨集活頁簿) 中的巨集計數。</span><span class="sxs-lookup"><span data-stu-id="9c296-480">Workbook Statistics would report a macro count from all open workbooks, including the personal macro workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-481">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-481">Outlook</span></span>
- <span data-ttu-id="9c296-482">切換資料夾可能會導致郵件清單/郵件預覽中「快閃」短暫的空白。</span><span class="sxs-lookup"><span data-stu-id="9c296-482">Switching folders may result in a brief white 'flash' in the mail list / mail preview.</span></span> <span data-ttu-id="9c296-483">此行為在深色模式中更明顯。</span><span class="sxs-lookup"><span data-stu-id="9c296-483">This behavior was more pronounced in dark mode.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-484">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-484">PowerPoint</span></span>
- <span data-ttu-id="9c296-485">已修正呼叫 Shape.Paste 方法會導致貼上的圖形置於焦點下的物件模型問題。&nbsp;</span><span class="sxs-lookup"><span data-stu-id="9c296-485">Fixed an Object Model issue where calling Shape.Paste method would result in the pasted shape receiving focus.&nbsp;</span></span>
- <span data-ttu-id="9c296-486">已改善複製貼上案例：&nbsp;以程式設計方式從 PowerPoint 投影片複製圖形，並將其貼到循環播放中的另一張投影片會失敗並發生異常錯誤。&nbsp;</span><span class="sxs-lookup"><span data-stu-id="9c296-486">Improved a copy-paste scenario:&nbsp;Progamatically copying a shape from a PowerPoint slide and pasting it to another slide in a loop could fail with an exception error.&nbsp;</span></span>
- <span data-ttu-id="9c296-487">折疊及展開節標頭後，投影片節標頭的動畫無法正確呈現。</span><span class="sxs-lookup"><span data-stu-id="9c296-487">Animation in the section headers of slides would not render properly after collapsing and expanding section headers.</span></span>

### <a name="project"></a><span data-ttu-id="9c296-488">Project</span><span class="sxs-lookup"><span data-stu-id="9c296-488">Project</span></span>
- <span data-ttu-id="9c296-489">已修正文字換行在任務和資源使用狀況檢視中無法正常運作的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-489">Fixed an issue where text wrapping wasn't working in the task and resource usage views.</span></span>
- <span data-ttu-id="9c296-490">已修正如果某資源有多個成本比率，則工作分派的成本值可能不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-490">Fixed an issue where if a resource has more than one cost rate, cost value on assignments may not be correct.</span></span>

### <a name="word"></a><span data-ttu-id="9c296-491">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-491">Word</span></span>
- <span data-ttu-id="9c296-492">在方程式中插入控制項 (例如文字內容控制項)，然後儲存再開啟檔案，便會導致內容無法讀取的錯誤。</span><span class="sxs-lookup"><span data-stu-id="9c296-492">Inserting a control (such as a Text Content Control) in an equation, then saving and opening the file would result in an un-readable content error.</span></span>
- <span data-ttu-id="9c296-493">共同撰寫時，Word 電腦版可能不會顯示使用 Word Online 新增註解的功能。</span><span class="sxs-lookup"><span data-stu-id="9c296-493">When co-authoring, adding a comment using Word online may not appear in Word desktop.</span></span>

### <a name="office-suite"></a><span data-ttu-id="9c296-494">Office 套件</span><span class="sxs-lookup"><span data-stu-id="9c296-494">Office Suite</span></span>
- <span data-ttu-id="9c296-495">嘗試在只有一個授權的情況下變更授權時，不再顯示有效授權的錯誤到期日。</span><span class="sxs-lookup"><span data-stu-id="9c296-495">Removed showing an erroneous expiry date of the valid license when trying to change license with only one license.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2001-december-13"></a><span data-ttu-id="9c296-497">版本 2001：12 月 13 日</span><span class="sxs-lookup"><span data-stu-id="9c296-497">Version 2001: December 13</span></span>
<span data-ttu-id="9c296-498">*版本 2001 (組建 12410.20000)*</span><span class="sxs-lookup"><span data-stu-id="9c296-498">*Version 2001 (Build 12410.20000)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="9c296-500">功能更新</span><span class="sxs-lookup"><span data-stu-id="9c296-500">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="9c296-501">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-501">Outlook</span></span>

- <span data-ttu-id="9c296-502">**將電子郵件拖曳到您擁有的群組：** 從您的 [收件匣] 拖曳郵件和交談以將它們移動和複製。</span><span class="sxs-lookup"><span data-stu-id="9c296-502">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="9c296-503">您拖曳的郵件將會與所有群組成員共用。</span><span class="sxs-lookup"><span data-stu-id="9c296-503">Messages you drag will be shared with all group members.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="9c296-506">解決的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-506">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="9c296-507">Access</span><span class="sxs-lookup"><span data-stu-id="9c296-507">Access</span></span>
- <span data-ttu-id="9c296-508">執行可參考連結之 ODBC 資料表且包含 Order By 子句的聯集查詢，會導致 64 位元 Access 當機。</span><span class="sxs-lookup"><span data-stu-id="9c296-508">Executing a union query that references linked ODBC table(s) and contains an Order By clause crashes 64 bit Access.</span></span>
- <span data-ttu-id="9c296-509">Access (O365) 中由聯集查詢的資料匯合可能會導致小數資料的截斷。</span><span class="sxs-lookup"><span data-stu-id="9c296-509">Summing of data from union queries in Access (O365) may result in truncation of decimal data.</span></span>
- <span data-ttu-id="9c296-510">ACE 的 COM 介面並未公開於 Office 應用程式的外部使用。</span><span class="sxs-lookup"><span data-stu-id="9c296-510">COM Interfaces for ACE are not exposed for use outside of Office applications.</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-511">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-511">Excel</span></span>
- <span data-ttu-id="9c296-512">無法執行插入3D 模型 (動態或靜態)，且嘗試 [另存成圖片]。</span><span class="sxs-lookup"><span data-stu-id="9c296-512">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>
- <span data-ttu-id="9c296-513">從 Backstage 啟動意見反應的 Shortkey (Alt+Ctrl + 7/8) 與 AZERTY 鍵盤 (Alt-Gr + 7/8) 有衝突。</span><span class="sxs-lookup"><span data-stu-id="9c296-513">The shortkey (Alt+Ctrl + 7/8)  to launch feedback from backstage is in conflict with AZERTY keyboards (Alt-Gr + 7/8).</span></span> <span data-ttu-id="9c296-514">影響：使用者可能無法使用下列字元，例如：'\'。</span><span class="sxs-lookup"><span data-stu-id="9c296-514">Impact: users may not be able to use some characters such as: '\'.</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-515">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-515">Outlook</span></span>
- <span data-ttu-id="9c296-516">解決導致電子郵件傳送到收件者錯誤地址的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-516">Addresses an issue that caused email to be sent to the wrong address for the recipient.</span></span>
- <span data-ttu-id="9c296-517">解決了導致 Outlook 不正確地允許使用者具有信箱的 &quot;[讀取]&quot; 存取權，而變更郵件之讀取/未讀取狀態的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-517">Addresses an issue that caused Outlook to incorrectly allow users with &quot;read&quot; access to a mailbox to change the read/unread state of a message.</span></span>
- <span data-ttu-id="9c296-518">網站上安全性憑證的撤銷無法由 [產品支援] 重新製造。</span><span class="sxs-lookup"><span data-stu-id="9c296-518">The revocation of the security certificate on the web site is not re-producible by Product Support.</span></span> <span data-ttu-id="9c296-519">需要新增 [記錄] 以協助根本解決問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-519">Logging needs to be added to help root cause the issue.</span></span>
- <span data-ttu-id="9c296-520">解決導致使用者看到同步處理失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-520">Addresses an issue that caused users to see synchronization failures.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-521">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-521">PowerPoint</span></span>
- <span data-ttu-id="9c296-522">無法執行插入3D 模型 (動態或靜態)，且嘗試 [另存成圖片]。</span><span class="sxs-lookup"><span data-stu-id="9c296-522">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>

### <a name="project"></a><span data-ttu-id="9c296-523">Project</span><span class="sxs-lookup"><span data-stu-id="9c296-523">Project</span></span>
- <span data-ttu-id="9c296-524">[工作] 不會在 [手動排程的子工作] 彙總中計算。</span><span class="sxs-lookup"><span data-stu-id="9c296-524">Task work is not calculated in Summary roll-up for manually scheduled child tasks.</span></span>
- <span data-ttu-id="9c296-525">嘗試儲存伺服器架構專案時，從 [功能區] 按鈕叫用的 Project VBA 程式碼可能無法使用。</span><span class="sxs-lookup"><span data-stu-id="9c296-525">Project VBA Code invoked from a Ribbon button may not work when trying to save server-based Projects.</span></span>
- <span data-ttu-id="9c296-526">除非 Project 已在執行，從 SharePoint 文件庫中開啟專案檔案會顯示錯誤，且檔案無法開啟。</span><span class="sxs-lookup"><span data-stu-id="9c296-526">Unless Project is already running, opening Project files from a SharePoint document library displays an error and the file will not open.</span></span>

### <a name="word"></a><span data-ttu-id="9c296-527">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-527">Word</span></span>
- <span data-ttu-id="9c296-528">儲存現有檔案可能會無法執行。</span><span class="sxs-lookup"><span data-stu-id="9c296-528">Saving existing files may not work.</span></span>
- <span data-ttu-id="9c296-529">在 [拼字及文法檢查編輯器] 視窗中使用方向鍵可能會導致間歇性閃爍。</span><span class="sxs-lookup"><span data-stu-id="9c296-529">Using arrow keys in the Spelling and Grammar editor window may result in intermittent flickering.</span></span>
- <span data-ttu-id="9c296-530">解決待處理時，相關註解可能不會轉換成指向註解。</span><span class="sxs-lookup"><span data-stu-id="9c296-530">When resolving a follow-up, associated comments may not convert to point comments.</span></span>
- <span data-ttu-id="9c296-531">無法執行插入3D 模型 (動態或靜態)，且嘗試 [另存成圖片]。</span><span class="sxs-lookup"><span data-stu-id="9c296-531">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>

### <a name="office-suite"></a><span data-ttu-id="9c296-532">Office 套件</span><span class="sxs-lookup"><span data-stu-id="9c296-532">Office Suite</span></span>
- <span data-ttu-id="9c296-533">修正了 Office 更新訊息不以預期語言顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-533">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="9c296-534">自此以後，Office 更新訊息會正確符合 Windows 顯示語言。</span><span class="sxs-lookup"><span data-stu-id="9c296-534">Going forward, Office update messages will correctly match the Windows display language.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1912-december-06"></a><span data-ttu-id="9c296-536">版本 1912：12 月 06 日</span><span class="sxs-lookup"><span data-stu-id="9c296-536">Version 1912: December 06</span></span>
<span data-ttu-id="9c296-537">*版本 1912 (組建 12325.20012)*</span><span class="sxs-lookup"><span data-stu-id="9c296-537">*Version 1912 (Build 12325.20012)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="9c296-539">功能更新</span><span class="sxs-lookup"><span data-stu-id="9c296-539">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="9c296-540">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-540">Outlook</span></span>

- <span data-ttu-id="9c296-541">**進階群組電子郵件設定：** 此功能可協助使用者自訂要在收件匣中接收/追蹤哪些電子郵件或活動。</span><span class="sxs-lookup"><span data-stu-id="9c296-541">**Advanced group email settings:** This feature helps groups users to customize which emails or events to receive/follow in their inbox.</span></span>

- <span data-ttu-id="9c296-542">**群組命名原則：** 群組命名原則可讓 IT 系統管理員將組織中使用者所建立群組的名稱標準化及管理。</span><span class="sxs-lookup"><span data-stu-id="9c296-542">**Groups Naming policy:** A group naming policy enables the IT admin to standardize and manage the names of groups created by users in the organization.</span></span> <span data-ttu-id="9c296-543">系統管理員可以要求在建立群組時，將特定首碼和尾碼新增至群組的名稱，而且可以封鎖使用特定字詞。</span><span class="sxs-lookup"><span data-stu-id="9c296-543">The admin can require a specific prefix and suffix be added to the name for a group when it's created, and can block specific words from being used.</span></span> <span data-ttu-id="9c296-544">這有助於將群組名稱中使用不當字詞的情況最小化，以及 IT 管理其目錄中群組的表示方式。</span><span class="sxs-lookup"><span data-stu-id="9c296-544">This helps minimize the use of inappropriate words in group names as well as IT manage the representation of groups in their directory.</span></span> <span data-ttu-id="9c296-545">命名原則也可協助部署小組網站的組織根據部門來分類。</span><span class="sxs-lookup"><span data-stu-id="9c296-545">Naming Policy also helps organizations that deploy team sites to categorize them based on department.</span></span>

### <a name="office-suite"></a><span data-ttu-id="9c296-546">Office 套件</span><span class="sxs-lookup"><span data-stu-id="9c296-546">Office Suite</span></span>

- <span data-ttu-id="9c296-547">**索引標籤式窗格：** 現在您可以使用應用程式右側的索引標籤 UI，在多個窗格之間切換。</span><span class="sxs-lookup"><span data-stu-id="9c296-547">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="9c296-548">只有當您開啟 2 個以上的窗格時，該 UI 才會顯示。</span><span class="sxs-lookup"><span data-stu-id="9c296-548">The UI will only be visible when you have 2+ panes open.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="9c296-551">解決的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-551">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="9c296-552">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-552">Excel</span></span>
- <span data-ttu-id="9c296-553">使用者在使用某些非英文字元集的情況下，儲存變更時可能會遇到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-553">Users may encounter an error when saving changes while using some non-English character sets.</span></span>
- <span data-ttu-id="9c296-554">使用者在存取隱藏的命名範圍時可能會發生錯誤。</span><span class="sxs-lookup"><span data-stu-id="9c296-554">Users may encounter an error when accessing a hidden named range.</span></span>
- <span data-ttu-id="9c296-555">停用使用 4K 解析度的硬體圖形加速的情況下，可能會在捲動時發生延遲儲存格呈現的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-555">Disabling hardware graphics acceleration with 4K resolution may result in delayed rendering of cells when scrolling around.</span></span>
- <span data-ttu-id="9c296-556">清除與儲存格界限重疊的長型公式，可能仍舊會跨儲存格界限顯示出來。</span><span class="sxs-lookup"><span data-stu-id="9c296-556">Clearing a long formula that overlaps a cell boundary may still display across the cell boundary.</span></span>
- <span data-ttu-id="9c296-557">解決了開啟內嵌活頁簿時，功能區自訂無法載入的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-557">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>
- <span data-ttu-id="9c296-558">邊界下拉式功能表可能無法正確呈現。</span><span class="sxs-lookup"><span data-stu-id="9c296-558">Margin dropdown menu may not render correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="9c296-559">OneNote</span><span class="sxs-lookup"><span data-stu-id="9c296-559">OneNote</span></span>
- <span data-ttu-id="9c296-560">OneNote 可能無法透過「會議記事」Outlook 增益集開啟。</span><span class="sxs-lookup"><span data-stu-id="9c296-560">OneNote may not open via the 'Meeting Notes' Outlook add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-561">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-561">Outlook</span></span>
- <span data-ttu-id="9c296-562">保留原則標籤可能會將保留時間顯示於括弧中。</span><span class="sxs-lookup"><span data-stu-id="9c296-562">Retention policy labels may display the retention time period in parenthesis.</span></span>
- <span data-ttu-id="9c296-563">空格可能會顯示於日文語言套件的連絡人卡片中。</span><span class="sxs-lookup"><span data-stu-id="9c296-563">Blank spaces may appear in Contact cards with Japanese language pack.</span></span>
- <span data-ttu-id="9c296-564">內嵌插入至 Outlook 電子郵件訊息中的影像有時候會改變大小。</span><span class="sxs-lookup"><span data-stu-id="9c296-564">Images inserted inline to Outlook e-mail messages can sometimes get resized.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-565">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-565">PowerPoint</span></span>
- <span data-ttu-id="9c296-566">如果使用者雲端檔案的投影片上有兩個 (或多個) 不同的影片，影片影像可正確呈現，但是當使用者按一下每一個檔案來播放時，影片內容會是相同的。</span><span class="sxs-lookup"><span data-stu-id="9c296-566">If a user has two (or more) different videos on a slide in a cloud file, the video images are rendered correctly, but when the user clicks on each one to play, the video content is the same.</span></span>
- <span data-ttu-id="9c296-567">在某些情況下，使用觸控裝置進行捲動將無法運作。</span><span class="sxs-lookup"><span data-stu-id="9c296-567">In some cases, scrolling with touch devices will not work.</span></span>
- <span data-ttu-id="9c296-568">邊界下拉式功能表可能無法正確呈現。</span><span class="sxs-lookup"><span data-stu-id="9c296-568">Margin dropdown menu may not render correctly.</span></span>
- <span data-ttu-id="9c296-569">Office 應用程式之間的安全性連結可能無法啟動連結的應用程式。</span><span class="sxs-lookup"><span data-stu-id="9c296-569">Safelinks from one Office application to another may not launch the linked application.</span></span>

### <a name="project"></a><span data-ttu-id="9c296-570">Project</span><span class="sxs-lookup"><span data-stu-id="9c296-570">Project</span></span>
- <span data-ttu-id="9c296-571">當您使用 [比較專案] 功能時，Project 可能會當機。</span><span class="sxs-lookup"><span data-stu-id="9c296-571">Project may crash when you use the Compare Projects feature.</span></span>
- <span data-ttu-id="9c296-572">如果您在 [深色] 模式中，當您移至含有過度分配資源之工作上的工作檢查面板時，將無法讀取資料表。</span><span class="sxs-lookup"><span data-stu-id="9c296-572">If you are in Dark mode, when you go to the task inspector panel on a task with an over allocated resource, you are unable to read the table.</span></span>
- <span data-ttu-id="9c296-573">將沒有作業的任務進行進位設定為 1 天。</span><span class="sxs-lookup"><span data-stu-id="9c296-573">Setting effort on tasks that have no assignments are rounded to 1 day.</span></span>

### <a name="word"></a><span data-ttu-id="9c296-574">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-574">Word</span></span>
- <span data-ttu-id="9c296-575">在特定條件下，完成合併列印之後儲存的檔案可能無法使用。</span><span class="sxs-lookup"><span data-stu-id="9c296-575">Saving a file after doing a mail merge may not work under certain conditions.</span></span>
- <span data-ttu-id="9c296-576">建置組塊召集人可能會顯示不正確通知：&quot;您已修改過樣式、建置組塊&quot;。</span><span class="sxs-lookup"><span data-stu-id="9c296-576">Building blocks organizer may display an invalid alert: &quot;You have modified styles, building blocks&quot;.</span></span>
- <span data-ttu-id="9c296-577">使用複製/貼上時，有時會重新載入註解窗格。</span><span class="sxs-lookup"><span data-stu-id="9c296-577">Comment pane sometimes gets reloaded when using copy/paste.</span></span>
- <span data-ttu-id="9c296-578">註解有時不會以正確的順序貼上。</span><span class="sxs-lookup"><span data-stu-id="9c296-578">Comments are sometimes not pasted in the correct order.</span></span>
- <span data-ttu-id="9c296-579">將含有自訂樣式的多層級清單範本套用至現有的文件時，可能在特定條件下不會保留該樣式。</span><span class="sxs-lookup"><span data-stu-id="9c296-579">Applying a template consisting of a multi-level list with custom styles to existing documents may not preserve the style under certain conditions.</span></span>
- <span data-ttu-id="9c296-580">調整分割螢幕邊界的大小可能會造成其他的分割螢幕。</span><span class="sxs-lookup"><span data-stu-id="9c296-580">Resizing a split screen border may introduce an additional split screen.</span></span>
- <span data-ttu-id="9c296-581">邊界下拉式功能表可能無法正確呈現。</span><span class="sxs-lookup"><span data-stu-id="9c296-581">Margin dropdown menu may not render correctly.</span></span>
- <span data-ttu-id="9c296-582">@提及註解卡中的使用者可能會顯示 JSON。</span><span class="sxs-lookup"><span data-stu-id="9c296-582">At-mentioning a user in a comment card may show JSON.</span></span>
- <span data-ttu-id="9c296-583">Office 應用程式之間的安全性連結可能無法啟動連結的應用程式。</span><span class="sxs-lookup"><span data-stu-id="9c296-583">Safelinks from one Office application to another may not launch the linked application.</span></span>

### <a name="office-suite"></a><span data-ttu-id="9c296-584">Office 套件</span><span class="sxs-lookup"><span data-stu-id="9c296-584">Office Suite</span></span>
- <span data-ttu-id="9c296-585">針對日文產品，帳戶使用者的姓名可能會以錯誤的順序出現。</span><span class="sxs-lookup"><span data-stu-id="9c296-585">For Japanese based products, account user first name, last name may appear in incorrect order.</span></span>
- <span data-ttu-id="9c296-586">將滑鼠指標暫留於註解上方時，可能會在註解周圍顯示文字方塊外框的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-586">Hovering a mouse pointer over comments may display a textbox outline around the comment.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1912-november-15"></a><span data-ttu-id="9c296-588">版本 1912：11 月 15 日</span><span class="sxs-lookup"><span data-stu-id="9c296-588">Version 1912: November 15</span></span>
<span data-ttu-id="9c296-589">*版本1912 (組建 12307.20000)*</span><span class="sxs-lookup"><span data-stu-id="9c296-589">*Version 1912 (Build 12307.20000)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="9c296-591">功能更新</span><span class="sxs-lookup"><span data-stu-id="9c296-591">Feature updates</span></span>
### <a name="insights-services"></a><span data-ttu-id="9c296-592">深入解析服務</span><span class="sxs-lookup"><span data-stu-id="9c296-592">Insights Services</span></span>
- <span data-ttu-id="9c296-593">**Excel 構想中的自然語言查詢：** Excel 構想的新功能，詢問關於您資料的自然語言問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-593">**Natural Language Queries in Ideas in Excel:** Excel Ideas's new capability to ask a natural language question about your data.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="9c296-596">解決的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-596">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="9c296-597">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-597">Excel</span></span>
- <span data-ttu-id="9c296-598">某些當地語系化版本的 [文字到欄] 功能可能會失敗。</span><span class="sxs-lookup"><span data-stu-id="9c296-598">Text to Column functionality may fail for some localizations.</span></span>
- <span data-ttu-id="9c296-599">編輯儲存格中的動態陣列公式可能會導致文字在儲存格邊界以外對齊。</span><span class="sxs-lookup"><span data-stu-id="9c296-599">Editing dynamic array formulas within a cell may result in text being aligned outside of the boundary of the cell.</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-600">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-600">Outlook</span></span>
- <span data-ttu-id="9c296-601">新增透過群組原則強制執行 S/MIME 設定的功能。</span><span class="sxs-lookup"><span data-stu-id="9c296-601">Added the ability to enforce S/MIME configuration via group policy.</span></span>
- <span data-ttu-id="9c296-602">內嵌影像可能會比預期小。</span><span class="sxs-lookup"><span data-stu-id="9c296-602">Embedded images may appear smaller than expected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-603">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-603">PowerPoint</span></span>
- <span data-ttu-id="9c296-604">當您將焦點移出文字後，游標可能會消失。</span><span class="sxs-lookup"><span data-stu-id="9c296-604">Cursor may disappear after moving focus from text.</span></span>

### <a name="project"></a><span data-ttu-id="9c296-605">Project</span><span class="sxs-lookup"><span data-stu-id="9c296-605">Project</span></span>
- <span data-ttu-id="9c296-606">使用者可能會遇到授權錯誤。</span><span class="sxs-lookup"><span data-stu-id="9c296-606">Users may experience an error regarding licensing.</span></span>
- <span data-ttu-id="9c296-607">日期選擇器中的 [今日] 按鈕有時候可能會設定不正確的日期。</span><span class="sxs-lookup"><span data-stu-id="9c296-607">The Today button in the date picker may sometimes set the incorrect date.</span></span>

### <a name="word"></a><span data-ttu-id="9c296-608">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-608">Word</span></span>
- <span data-ttu-id="9c296-609">以滑鼠右鍵按一下有時不會選取整個字詞。</span><span class="sxs-lookup"><span data-stu-id="9c296-609">Right-clicking can sometimes not result in selecting the whole word.</span></span>
- <span data-ttu-id="9c296-610">轉換成建議格式之後，游標在物件內可能仍處於使用中狀態。</span><span class="sxs-lookup"><span data-stu-id="9c296-610">The cursor may remain active within an object after converting to a suggested format.</span></span>
- <span data-ttu-id="9c296-611">訊息中的影像在某些情況下可能會不正確的縮放。</span><span class="sxs-lookup"><span data-stu-id="9c296-611">Images in messages may be incorrectly scaled in some scenarios.</span></span>
- <span data-ttu-id="9c296-612">某些主題可能會導致難以判斷所選取的註解。</span><span class="sxs-lookup"><span data-stu-id="9c296-612">Some themes may make it difficult to determine which comment is selected.</span></span>
- <span data-ttu-id="9c296-613">選取註解提示之後，在窗格切換器中隱藏時，現在會顯示新式註解窗格。</span><span class="sxs-lookup"><span data-stu-id="9c296-613">Selecting a comment hint should now show the modern comments pane when hidden in pane switcher.</span></span>

### <a name="office-suite"></a><span data-ttu-id="9c296-614">Office 套件</span><span class="sxs-lookup"><span data-stu-id="9c296-614">Office Suite</span></span>
- <span data-ttu-id="9c296-615">回覆註解可能會導致文字方塊垂直延伸到窗格的邊緣以外。</span><span class="sxs-lookup"><span data-stu-id="9c296-615">Replying to a comment may cause the textbox to expand vertically beyond the edge of the pane.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1912-november-08"></a><span data-ttu-id="9c296-617">版本 1912：11 月 8 日</span><span class="sxs-lookup"><span data-stu-id="9c296-617">Version 1912: November 08</span></span>
<span data-ttu-id="9c296-618">*版本 1912 (組建 12231.20000)*</span><span class="sxs-lookup"><span data-stu-id="9c296-618">*Version 1912 (Build 12231.20000)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="9c296-620">功能更新</span><span class="sxs-lookup"><span data-stu-id="9c296-620">Feature updates</span></span>
### <a name="user-lifecycle"></a><span data-ttu-id="9c296-621">使用者生命週期</span><span class="sxs-lookup"><span data-stu-id="9c296-621">User Lifecycle</span></span>
- <span data-ttu-id="9c296-622">**AFO 啟用的經驗改進：** 對客戶啟用新電腦隨附的 Office 時，所會看到的畫面進行更新。</span><span class="sxs-lookup"><span data-stu-id="9c296-622">**Experience improvements for AFO activation:** Updates to the screens customers see when activating Office that comes bundled with their new PC.</span></span>

### <a name="word"></a><span data-ttu-id="9c296-623">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-623">Word</span></span>
- <span data-ttu-id="9c296-624">**Word 中的全新和改良的線上影片體驗：** 全新和更安全的線上影片體驗，可協助您在 Word 中插入新的影片並播放現有影片。</span><span class="sxs-lookup"><span data-stu-id="9c296-624">**New and improved online video experience in Word:** New and more secure online video experience to help you insert new videos and play existing videos in Word.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="9c296-627">解決的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-627">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="9c296-628">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-628">Outlook</span></span>
- <span data-ttu-id="9c296-629">與跨資料夾內容有關的間歇性損毀。</span><span class="sxs-lookup"><span data-stu-id="9c296-629">Intermittent crash involving cross folder content.</span></span>

### <a name="office-suite"></a><span data-ttu-id="9c296-630">Office 套件</span><span class="sxs-lookup"><span data-stu-id="9c296-630">Office Suite</span></span>
- <span data-ttu-id="9c296-631">將圖表從 Excel 貼上至 PowerPoint 可能會造成圖表的大小縮小。</span><span class="sxs-lookup"><span data-stu-id="9c296-631">Pasting a chart from Excel to PowerPoint can reduce the size of the chart.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1911-november-01"></a><span data-ttu-id="9c296-633">版本 1911：11 月 1 日</span><span class="sxs-lookup"><span data-stu-id="9c296-633">Version 1911: November 01</span></span>
<span data-ttu-id="9c296-634">*版本 1911 (組建 12228.20020)*</span><span class="sxs-lookup"><span data-stu-id="9c296-634">*Version 1911 (Build 12228.20020)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="9c296-636">功能更新</span><span class="sxs-lookup"><span data-stu-id="9c296-636">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="9c296-637">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-637">Excel</span></span>
- <span data-ttu-id="9c296-638">**將內容與 SVG 物件一起顯示！：** 在 Office 中轉換地圖、圖表和其他 SVG 向量等物件時，現在您可以保留物件中的文字。</span><span class="sxs-lookup"><span data-stu-id="9c296-638">**Bring the context along with your SVG objects!:** Now you can retain the text in maps, chart and other SVG vectors when converting these objects in Office.</span></span>

- <span data-ttu-id="9c296-639">**拿起 Surface 手寫筆時查看手寫筆選項：** 當您在 Word、Excel 或 PowerPoint 中先拿起 Surface 手寫筆時，[繪圖] 索引標籤將會啟動，讓您輕鬆地選取畫筆色彩。</span><span class="sxs-lookup"><span data-stu-id="9c296-639">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-640">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-640">PowerPoint</span></span>
- <span data-ttu-id="9c296-641">**將內容與 SVG 物件一起顯示！：** 在 Office 中轉換地圖、圖表和其他 SVG 向量等物件時，現在您可以保留物件中的文字。</span><span class="sxs-lookup"><span data-stu-id="9c296-641">**Bring the context along with your SVG objects!:** Now you can retain the text in maps, chart and other SVG vectors when converting these objects in Office.</span></span>

- <span data-ttu-id="9c296-642">**拿起 Surface 手寫筆時查看手寫筆選項：** 當您在 Word、Excel 或 PowerPoint 中先拿起 Surface 手寫筆時，[繪圖] 索引標籤將會啟動，讓您輕鬆地選取畫筆色彩。</span><span class="sxs-lookup"><span data-stu-id="9c296-642">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

### <a name="visio"></a><span data-ttu-id="9c296-643">Visio</span><span class="sxs-lookup"><span data-stu-id="9c296-643">Visio</span></span>
- <span data-ttu-id="9c296-644">**在 Excel 中製作精美的 Visio 圖表：** 在 Excel 中快速且輕鬆地將資料呈現為精美的 Visio 圖表。</span><span class="sxs-lookup"><span data-stu-id="9c296-644">**Make polished Visio diagrams in Excel:** Quickly and easily visualize your data into polished Visio diagrams within Excel.</span></span> <span data-ttu-id="9c296-645">[深入了解](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)。</span><span class="sxs-lookup"><span data-stu-id="9c296-645">[Learn more](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c).</span></span>

### <a name="word"></a><span data-ttu-id="9c296-646">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-646">Word</span></span>
- <span data-ttu-id="9c296-647">**拿起 Surface 手寫筆時查看手寫筆選項：** 當您在 Word、Excel 或 PowerPoint 中先拿起 Surface 手寫筆時，[繪圖] 索引標籤將會啟動，讓您輕鬆地選取畫筆色彩。</span><span class="sxs-lookup"><span data-stu-id="9c296-647">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

- <span data-ttu-id="9c296-648">**改善共同撰寫：** 改善共同撰寫的體驗，盡可能讓其他人即時收到修改過的內容。</span><span class="sxs-lookup"><span data-stu-id="9c296-648">**Coauthoring improvements:** Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

- <span data-ttu-id="9c296-649">**其他人更快速看到您的變更：** 共同撰寫增強功能表示，共同作業者可較以往更快速看到您的變更。</span><span class="sxs-lookup"><span data-stu-id="9c296-649">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="9c296-652">解決的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-652">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="9c296-653">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-653">Excel</span></span>
- <span data-ttu-id="9c296-654">解決從不受信任的網路共用編輯受保護的檔案時，Excel 可能會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-654">Resolved an issue where Excel may crash when editing a protected file from an untrusted network share.</span></span>
- <span data-ttu-id="9c296-655">解決在刪除含有的走勢圖參考另一個資料表中資料的資料表時，會導致重新開啟檔案時，將檔案識別為已損毀的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-655">Resolved an issue where deleting sheets containing sparklines referencing data on another sheet could cause the file to be identified as corrupted when re-opened.</span></span>
- <span data-ttu-id="9c296-656">解決當您將報表篩選隨著其餘的樞紐分析表一起轉換，以用於 SQL 表格式伺服器的查詢時，可能會遇到結果不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-656">Resolved an Issue where you may get incorrect results when converting report filters along with the rest of the PivotTable for queries to SQL tabular servers.</span></span>
- <span data-ttu-id="9c296-657">同時使用朗讀程式和放大鏡，可能會導致當機。</span><span class="sxs-lookup"><span data-stu-id="9c296-657">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="9c296-658">同時使用朗讀程式和放大鏡，可能會導致當機。</span><span class="sxs-lookup"><span data-stu-id="9c296-658">Using Narrator and Magnifier at the same time may result in a crash.</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-659">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-659">Outlook</span></span>
- <span data-ttu-id="9c296-660">轉寄的電子郵件可能會遺失內嵌的影像。</span><span class="sxs-lookup"><span data-stu-id="9c296-660">A forwarded e-mail may be missing embedded images.</span></span>
- <span data-ttu-id="9c296-661">會議室尋找工具可能會對可用的會議室顯示 &quot;[無]&quot;。</span><span class="sxs-lookup"><span data-stu-id="9c296-661">Room Finder tool may be displaying &quot;None&quot; for available rooms.</span></span>
- <span data-ttu-id="9c296-662">使用者可能無法建立具有嚴格租用戶限制的 Outlook 設定檔。</span><span class="sxs-lookup"><span data-stu-id="9c296-662">Users may not be able to create Outlook profiles with strict tenant restriction.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-663">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-663">PowerPoint</span></span>
- <span data-ttu-id="9c296-664">同時使用朗讀程式和放大鏡，可能會導致當機。</span><span class="sxs-lookup"><span data-stu-id="9c296-664">Using Narrator and Magnifier at the same time may result in a crash.</span></span>

### <a name="project"></a><span data-ttu-id="9c296-665">Project</span><span class="sxs-lookup"><span data-stu-id="9c296-665">Project</span></span>
- <span data-ttu-id="9c296-666">使用者無法將工作標示為已完成，並將它設為 99%。</span><span class="sxs-lookup"><span data-stu-id="9c296-666">User is unable to mark a task as complete, and it gets set to 99%.</span></span>
- <span data-ttu-id="9c296-667">資源撫平無法解決資源過度分派問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-667">Overallocations are not resolved by leveling.</span></span>

### <a name="word"></a><span data-ttu-id="9c296-668">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-668">Word</span></span>
- <span data-ttu-id="9c296-669">同時使用朗讀程式和放大鏡，可能會導致當機。</span><span class="sxs-lookup"><span data-stu-id="9c296-669">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="9c296-670">開啟舊版文件，然後移至 [資訊] 索引標籤會導致當機。</span><span class="sxs-lookup"><span data-stu-id="9c296-670">Opening legacy documents and then going to the Info tab can cause a crash.</span></span>
- <span data-ttu-id="9c296-671">內容功能表中未顯示校訂建議。</span><span class="sxs-lookup"><span data-stu-id="9c296-671">Proofing suggestins are not displaying in contextual menus.</span></span>
- <span data-ttu-id="9c296-672">對註解套用不正確的內容原則。</span><span class="sxs-lookup"><span data-stu-id="9c296-672">Content policies are being incorrectly applied to comments.</span></span>
- <span data-ttu-id="9c296-673">以深色文字編寫的舊版註解在深色模式中不會顯示。</span><span class="sxs-lookup"><span data-stu-id="9c296-673">Legacy comments written with dark text is not visible in Dark Mode.</span></span>
- <span data-ttu-id="9c296-674">使用韓文/英文自動校正時，可能出現不正確的字元。</span><span class="sxs-lookup"><span data-stu-id="9c296-674">Incorrect characters may appear when using Korean/English autocorrect.</span></span>
- <span data-ttu-id="9c296-675">在應優先套用較高的原則標籤前，可能已套用了較低的原則標籤。</span><span class="sxs-lookup"><span data-stu-id="9c296-675">Lower policy labels may be applied when a higher policy label should have taken priority.</span></span>
- <span data-ttu-id="9c296-676">來自 Outlook 郵件中的 cid: 影像連結&nbsp;現在能在要求時成功中斷。</span><span class="sxs-lookup"><span data-stu-id="9c296-676">The links of cid: images from Outlook messages&nbsp;can now be successfully broken when requested.</span></span>
- <span data-ttu-id="9c296-677">同時使用朗讀程式和放大鏡，可能會導致當機。</span><span class="sxs-lookup"><span data-stu-id="9c296-677">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="9c296-678">從瀏覽窗格搜尋可能會失敗。</span><span class="sxs-lookup"><span data-stu-id="9c296-678">Searching from the Navigation pane may fail.</span></span>

### <a name="office-suite"></a><span data-ttu-id="9c296-679">Office 套件</span><span class="sxs-lookup"><span data-stu-id="9c296-679">Office Suite</span></span>
- <span data-ttu-id="9c296-680">某些繪圖可能不會在預覽或投影片放映中顯示。</span><span class="sxs-lookup"><span data-stu-id="9c296-680">Some drawings may not display in preview or slide shows.</span></span>
- <span data-ttu-id="9c296-681">在垂直文字方塊中，部分片假名字元可能無法正確顯示。</span><span class="sxs-lookup"><span data-stu-id="9c296-681">Some katakana characters may display incorrectly in a vertical text box.</span></span>
- <span data-ttu-id="9c296-682">嘗試將檔案儲存到已中斷連線的網路共用時可能會導致當機。</span><span class="sxs-lookup"><span data-stu-id="9c296-682">Attempting to save a file to a disconnected network share may result in a crash.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1911-october-25"></a><span data-ttu-id="9c296-684">版本 1911：10 月 25 日</span><span class="sxs-lookup"><span data-stu-id="9c296-684">Version 1911: October 25</span></span>
<span data-ttu-id="9c296-685">*版本 1911 (組建 12215.20006)*</span><span class="sxs-lookup"><span data-stu-id="9c296-685">*Version 1911 (Build 12215.20006)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="9c296-687">功能更新</span><span class="sxs-lookup"><span data-stu-id="9c296-687">Feature updates</span></span>
### <a name="visio"></a><span data-ttu-id="9c296-688">Visio</span><span class="sxs-lookup"><span data-stu-id="9c296-688">Visio</span></span>

- <span data-ttu-id="9c296-689">**在 Excel 中製作精美的 Visio 圖表：** 在 Excel 中快速且輕鬆地將資料呈現為精美的 Visio 圖表。</span><span class="sxs-lookup"><span data-stu-id="9c296-689">**Make polished Visio diagrams in Excel:** Quickly and easily visualize your data into polished Visio diagrams within Excel.</span></span> [<span data-ttu-id="9c296-690">深入了解</span><span class="sxs-lookup"><span data-stu-id="9c296-690">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="9c296-691">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-691">Word</span></span>

- <span data-ttu-id="9c296-692">**改善共同撰寫：** 改善共同撰寫的體驗，盡可能讓其他人即時收到修改過的內容。</span><span class="sxs-lookup"><span data-stu-id="9c296-692">**Coauthoring improvements:** Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

- <span data-ttu-id="9c296-693">**其他人更快速看到您的變更：** 共同撰寫增強功能表示，共同作業者可較以往更快速看到您的變更。</span><span class="sxs-lookup"><span data-stu-id="9c296-693">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="9c296-696">解決的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-696">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="9c296-697">Access</span><span class="sxs-lookup"><span data-stu-id="9c296-697">Access</span></span>

- <div><span data-ttu-id="9c296-698"><span>記錄計數可能不正確</span></span><span class="sxs-lookup"><span data-stu-id="9c296-698"><span>The record count could be incorrect</span></span></span></div>


### <a name="excel"></a><span data-ttu-id="9c296-699">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-699">Excel</span></span>

- <div><span data-ttu-id="9c296-700"><span>我們已大幅改善刪除合併儲存格的資料行的效能</span></span><span class="sxs-lookup"><span data-stu-id="9c296-700"><span>We significantly improved the performance of deleting columns with merged cells</span></span></span></div>


- <div><span data-ttu-id="9c296-701"><span>可能已防止使用者以 Office 365 Excel 活頁簿格式儲存</span></span><span class="sxs-lookup"><span data-stu-id="9c296-701"><span>Users could be prevented from saving in Office 365 Excel Workbook format</span></span></span></div>


- <div><span data-ttu-id="9c296-702"><span>核取方塊無法正確呈現</span></span><span class="sxs-lookup"><span data-stu-id="9c296-702"><span>Checkboxes could not render correctly</span></span></span></div>


- <div><span data-ttu-id="9c296-703"><span>無法儲存對圖表大小的變更</span></span><span class="sxs-lookup"><span data-stu-id="9c296-703"><span>Changes to a chart size could not be saved</span></span></span></div>


- <div><span data-ttu-id="9c296-704"><span>某些 VBA 函數會針對新的圖表類型傳回錯誤</span></span><span class="sxs-lookup"><span data-stu-id="9c296-704"><span>Some VBA functions would return an error on new chart types</span></span></span></div>


- <div><span data-ttu-id="9c296-705"><span>[選取資料來源] 對話方塊上的部分欄位並未區分大小寫</span></span><span class="sxs-lookup"><span data-stu-id="9c296-705"><span>Select Data Source dialogs were not case sensitive for some fields</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="9c296-706">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-706">PowerPoint</span></span>

- <div><span data-ttu-id="9c296-707"><span>無法儲存對圖表大小的變更</span></span><span class="sxs-lookup"><span data-stu-id="9c296-707"><span>Changes to a chart size could not be saved</span></span></span></div>


### <a name="publisher"></a><span data-ttu-id="9c296-708">Publisher</span><span class="sxs-lookup"><span data-stu-id="9c296-708">Publisher</span></span>

- <div><span data-ttu-id="9c296-709"><span>圖形可能會顯示在圖形框線以外</span></span><span class="sxs-lookup"><span data-stu-id="9c296-709"><span>Shapes could appear outside of the graphics border</span></span></span></div>


### <a name="word"></a><span data-ttu-id="9c296-710">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-710">Word</span></span>

- <div><span data-ttu-id="9c296-711"><span>圖形可能會顯示在圖形框線以外</span></span><span class="sxs-lookup"><span data-stu-id="9c296-711"><span>Shapes could appear outside of the graphics border</span></span></span></div>


- <div><span data-ttu-id="9c296-712"><span>醒目提示文字可能很困難</span></span><span class="sxs-lookup"><span data-stu-id="9c296-712"><span>Highlighting text could be challenging</span></span></span></div>


- <div><span data-ttu-id="9c296-713"><span>可能已防止使用者在編輯器中瀏覽個別項目</span></span><span class="sxs-lookup"><span data-stu-id="9c296-713"><span>A user could be prevented from navigating to an individual item in the editor</span></span></span></div>


- <div><span data-ttu-id="9c296-714"><span>可能不會將文法或拼寫錯誤醒目提示</span></span><span class="sxs-lookup"><span data-stu-id="9c296-714"><span>Grammar or spelling errors might not be highlighted</span></span></span></div>


- <div><span data-ttu-id="9c296-715"><span>無法儲存對圖表大小的變更</span></span><span class="sxs-lookup"><span data-stu-id="9c296-715"><span>Changes to a chart size could not be saved</span></span></span></div>


- <div><span data-ttu-id="9c296-716"><span>將格式設定套用到 @ 提及之後，可能會防止開啟連絡人卡片</span></span><span class="sxs-lookup"><span data-stu-id="9c296-716"><span>A contact card could be prevented from opening after apply formatting to an @ mention</span></span></span></div>


- <div><span data-ttu-id="9c296-717"><span>已解決使用者無法儲存 Word、Excel 和 PowerPoint 文件的問題。&nbsp;此問題會影響建立新檔案並在按一下 [儲存] 圖示或按 Ctrl + S 之後帶出 [另存成模型對話方塊]&quot;&quot; 選項的使用者。</span></span><span class="sxs-lookup"><span data-stu-id="9c296-717"><span>Resolvedan issue where users may be unable to save Word, Excel, and PowerPoint documents.&nbsp; This issue affects users that create a new file and bring up the &quot;Save as Model Dialog&quot; option after clicking on the Save icon or pressing Ctrl + S.</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="9c296-718">Office 套件</span><span class="sxs-lookup"><span data-stu-id="9c296-718">Office Suite</span></span>

- <div><span data-ttu-id="9c296-719"><span>在 Windows 7 上使用圖形時的效能問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-719"><span>Performance issue when using Shapes on Windows 7</span></span></span></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1911-october-18"></a><span data-ttu-id="9c296-721">版本 1911：10 月 18 日</span><span class="sxs-lookup"><span data-stu-id="9c296-721">Version 1911: October 18</span></span>
<span data-ttu-id="9c296-722">*版本 1911 (組建 12209.20010)*</span><span class="sxs-lookup"><span data-stu-id="9c296-722">*Version 1911 (Build 12209.20010)*</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="9c296-724">功能更新</span><span class="sxs-lookup"><span data-stu-id="9c296-724">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="9c296-725">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-725">Outlook</span></span>

- <span data-ttu-id="9c296-726">**傳送可存取的郵件給最需要它的人員：** Outlook 會顯示郵件提示，協助確保將您的內容傳送給偏好可存取內容的使用者時可供其存取</span><span class="sxs-lookup"><span data-stu-id="9c296-726">**Send accessible mail to those who need it most:** Outlook will display a mail tip to help you ensure that your content is accessible when sending to a user who prefers accessible content</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-727">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-727">PowerPoint</span></span>

- <span data-ttu-id="9c296-728">**最佳化您的簡報：** 協助工具檢查程式可協助您以螢幕閱讀器為中心，在投影片上排列物件。</span><span class="sxs-lookup"><span data-stu-id="9c296-728">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

### <a name="office-suite"></a><span data-ttu-id="9c296-729">Office 套件</span><span class="sxs-lookup"><span data-stu-id="9c296-729">Office Suite</span></span>

- <span data-ttu-id="9c296-730">**上傳中心將由需要注意的檔案體驗取代：**「上傳中心」將由會顯示在 Office 應用程式的 [檔案] > [開啟] 下的「需要注意的檔案」體驗取代。</span><span class="sxs-lookup"><span data-stu-id="9c296-730">**The Upload Center is being replaced by the Files Needing Attention experience:** The Upload Center is being replaced by the Files Needing Attention experience that will show up inside the Office applications under File > Open.</span></span> <span data-ttu-id="9c296-731">相較於上傳中心，此新體驗更為現代化、整合且更不具侵入性。</span><span class="sxs-lookup"><span data-stu-id="9c296-731">This new experience is more modern, integrated, and less intrusive compared to the Upload Center.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a><span data-ttu-id="9c296-734">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="9c296-734">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="9c296-735">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-735">Excel</span></span>

- <div><span data-ttu-id="9c296-736"><span>解決使用自動調整來調整列高時，核取方塊控制項可能收縮的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-736"><span>Resolved an issue where check box controls could shrink when using autofit to adjust row height</span></span></span></div>


- <div><span data-ttu-id="9c296-737"><span>解決捲動後選取儲存格時，可能導致選取錯誤的儲存格的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-737"><span>Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="9c296-738">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-738">Outlook</span></span>

- <div><span data-ttu-id="9c296-739"><span>發現簽署具有數位簽署附件的電子郵件時，可能導致數位簽章遭到破壞的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-739"><span>Identified an issue which could cause digital signatures to become broken when signing an e-mail with a digitally signed attachment</span></span></span></div>


- <div><span data-ttu-id="9c296-740"><span>發現在將長檔名拖放至郵件內文時，長檔名遭到截斷的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-740"><span>Identified an issue where long filenames were truncated after draging and droping to the message body</span></span></span></div>


- <div><span data-ttu-id="9c296-741">發現當功能區設定為自動隱藏時，搜尋方塊可能消失的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-741">Identified an issue where the search box could disappear when the ribbon is set to hide automatically</span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="9c296-742">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-742">PowerPoint</span></span>

- <div><span data-ttu-id="9c296-743"><span>發現投影片預覽的長寬比未正確鎖定/解除鎖定的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-743"><span>Identified an issuewhere aspect ratio for the slide preview was not being properly locked/unlocked</span></span></span></div>

### <a name="project"></a><span data-ttu-id="9c296-744">Project</span><span class="sxs-lookup"><span data-stu-id="9c296-744">Project</span></span>

- <div><span data-ttu-id="9c296-745">發現在執行更新工作時，若輸入記事，可能不會保留記事的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-745">Identified an issue where notes might not persist if entered while doing update tasks</span></span><br></div>


- <div><span data-ttu-id="9c296-746">發現檔案可能遭某個使用者鎖定，但不會在錯誤訊息中顯示任何使用者名稱的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-746">Identified an issue where a file could be locked by a user, but no username would be displayed in the error message</span></span></div>


- <div><span data-ttu-id="9c296-747"><span>發現在開啟唯讀專案時，使用者可能會收到數個訊息的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-747"><span>Identified an issue where users could get several messages when opening a read-only project</span></span></span></div>


### <a name="word"></a><span data-ttu-id="9c296-748">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-748">Word</span></span>

- <div><span data-ttu-id="9c296-749"><span>發現使用螢幕閱讀器檢視註解時的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-749"><span>Identified an issue when viewing comments while using a screen reader</span></span></span></div>


- <div><span data-ttu-id="9c296-750"><span>發現將某些評論錯誤地識別為拼寫或文法評論的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-750"><span>Identified an issue where some critiques were misidentified as being spelling or grammar critiques</span></span></span></div>


- <div><span data-ttu-id="9c296-751"><span>發現新留言對話方塊有時候未取得焦點的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-751"><span>Identified an issue where a new comment dialog could sometimes not obtain focus</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="9c296-752">Office 套件</span><span class="sxs-lookup"><span data-stu-id="9c296-752">Office Suite</span></span>

- <div><span data-ttu-id="9c296-753"><span>我們已修正了&quot;另一個安裝正在進行中&quot;的不正確錯誤訊息，可能導致無法升級的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-753"><span>We fixed an issue where an upgrade could be prevented by a incorrect error message of &quot;Another install in progress&quot;</span></span></span></div>

- <div><span data-ttu-id="9c296-754"><span>發現可能會影響從本機資源同步至雲端資源的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-754"><span>Identified an issue which could affect syncing from a local resource to a cloud resource</span></span></span></div>

- <div><span data-ttu-id="9c296-755"><span>發現歡迎訊息含有無效連結的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-755"><span>Identified an issue where a welcome message contained an invalid link</span></span></span></div>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1910-october-11"></a><span data-ttu-id="9c296-757">版本 1910：10 月 11 日</span><span class="sxs-lookup"><span data-stu-id="9c296-757">Version 1910: October 11</span></span>
<span data-ttu-id="9c296-758">*版本 1910 (組建 12130.20112)*</span><span class="sxs-lookup"><span data-stu-id="9c296-758">*Version 1910 (Build 12130.20112)*</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)
[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)
[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a><span data-ttu-id="9c296-762">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="9c296-762">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="9c296-763">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-763">Excel</span></span>

- <div><span data-ttu-id="9c296-764">解決從 OneDrive 以物件形式插入檔案的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-764">Resolved an issue in inserting files as object from OneDrive</span></span></div>


- <div><span data-ttu-id="9c296-765">解決無法將超連結格式正確套用至部分內容的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-765">Resolved an issue where the hyperlink format could not be properly applied to some content</span></span></div>


- <div><span data-ttu-id="9c296-766">解決含有結構化絕對參考的公式可能無法正確調整的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-766">Resolved an issue where formulas containing structured absolute references may be adjusted incorrectly</span></span></div>


- <div><span data-ttu-id="9c296-767">解決在目前的 Office 版本中開啟在舊版 Office 中建立的活頁簿時，可能導致 Excel 懸置的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-767">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office</span></span></div>


- <div><span data-ttu-id="9c296-768">解決從 Excel 複製的內容，在貼上到其他 Office 應用程式時，可能無法正確顯示的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-768">Resolved an issue where content copied from Excel could appear incorrect when pasted into other Office applications</span></span></div>


- <div><span data-ttu-id="9c296-769">修正以校正使用圖表範本插入圖表時，預覽中使用的色彩</span><span class="sxs-lookup"><span data-stu-id="9c296-769">Fix to correct colors used in previews when inserting charts using chart templates</span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="9c296-770">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-770">PowerPoint</span></span>

- <div><span data-ttu-id="9c296-771">已發現 ARC 裝置在 AirSpace WinComp 下執行時，可能會遺失連線的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-771">Identified an issue where ARC Devices could lose connection when running under AirSpace WinComp</span></span></div>


### <a name="word"></a><span data-ttu-id="9c296-772">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-772">Word</span></span>

- <div><span data-ttu-id="9c296-773">解決從 OneDrive 以物件形式插入檔案的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-773">Resolved an issue in inserting files as object from OneDrive</span></span></div>


- <div><span data-ttu-id="9c296-774">改善復原步驟，以<span>修正會導致從電子郵件執行緒中刪除圖形內容的問題。&nbsp;</span></span><span class="sxs-lookup"><span data-stu-id="9c296-774">Improved our recovery steps to f<span>ix an issue that caused graphical content to get deleted from email threads.&nbsp;</span></span></span></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1910-october-04"></a><span data-ttu-id="9c296-776">版本 1910：10 月 4 日</span><span class="sxs-lookup"><span data-stu-id="9c296-776">Version 1910: October 04</span></span>
<span data-ttu-id="9c296-777">*版本 1910 (組建 12126.20000)*</span><span class="sxs-lookup"><span data-stu-id="9c296-777">*Version 1910 (Build 12126.20000)*</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="9c296-779">功能更新</span><span class="sxs-lookup"><span data-stu-id="9c296-779">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="9c296-780">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-780">Excel</span></span>

- <span data-ttu-id="9c296-781">**資料視覺化工具增益集：** 從 Excel 快速建立 Visio 流程圖。</span><span class="sxs-lookup"><span data-stu-id="9c296-781">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="9c296-782">深入了解</span><span class="sxs-lookup"><span data-stu-id="9c296-782">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a><span data-ttu-id="9c296-785">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="9c296-785">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="9c296-786">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-786">Excel</span></span>

- <div><span data-ttu-id="9c296-787"><span>我們已修正 [預覽列印] 中的列印範圍不正確的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-787"><span>We fixed an issue where the print area in print preview was not correct</span></span></span></div>


- <div><span data-ttu-id="9c296-788"><span>我們已修正可能會讓樞紐分析表在共同撰寫工作階段期間無法重新整理的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-788"><span>We fixed an issue which could have prevented pivot tables from being refreshed during a co-authoring session</span></span></span></div>


### <a name="access"></a><span data-ttu-id="9c296-789">Access</span><span class="sxs-lookup"><span data-stu-id="9c296-789">Access</span></span>

- <div><span data-ttu-id="9c296-790">我們已修正當使用共用資料庫時，使用者可能收到&quot;不一致的狀態&quot;錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-790">We fixed an issue where users could receive an &quot;inconsistent state&quot; error when using a shared database.</span></span></div>


### <a name="outlook"></a><span data-ttu-id="9c296-791">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-791">Outlook</span></span>

- <div><span data-ttu-id="9c296-792"><span>我們已修正導致郵件資料夾重複的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-792"><span>We fixed an issue which could have caused duplication of mail folders</span></span></span></div>


- <div><span data-ttu-id="9c296-793"><span>我們已修正當嘗試傳送 s/MIME 加密電子郵件時，可能會導致錯誤訊息的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-793"><span>We fixed an issue which could have caused an incorrect error message when attempting to send s/MIME encrypted e-mail</span></span></span></div>


- <div><span data-ttu-id="9c296-794"><span>我們已修正當使用者收到來自 Skype 的「未接的交談」訊息時，有時可能會導致當機的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-794"><span>We fixed an issue which could sometimes result in a crash when a user receives a 'Missed Conversation' message from Skype</span></span></span></div>


- <div><span data-ttu-id="9c296-795"><span>我們已修正可能會造成記憶體洩漏的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-795"><span>We fixed an issue which could have resulted in a memory leak</span></span></span></div>


- <div><span data-ttu-id="9c296-796"><span>我們已修正當儲存為草稿時，可能會導致寄件者名稱變更的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-796"><span>We fixed an issue which could have caused the senders name to change when saved as a draft</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="9c296-797">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-797">PowerPoint</span></span>

- <div><span></span></div><span data-ttu-id="9c296-798">我們已修正以下問題：在您將文字貼到投影片母片和投影片版面配置上的頁首/頁尾/投影片編號預留位置之後，造成 TextRanges 損壞</span><span class="sxs-lookup"><span data-stu-id="9c296-798">We fixed an issue which could cause TextRanges to become broken after pasting text into the header/footer/slide number placeholders on slide master and slide layout</span></span>


- <div><span></span></div><span data-ttu-id="9c296-799">我們已修正在使用超連結貼上文字時，無法建立超連結的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-799">We fixed an issue which prevented hyperlink from being created when pasting text with hyperlink</span></span>


- <div><span data-ttu-id="9c296-800">我們已修正造成統計資料無法正常運作的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-800">We fixed an issue which would prevent statistics from working correctly</span></span></div>


### <a name="word"></a><span data-ttu-id="9c296-801">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-801">Word</span></span>

- <div><span data-ttu-id="9c296-802"><span>我們已修正未確認字型色彩的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-802"><span>We fixed an issue where font colors were not being committed</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="9c296-803">Office 套件</span><span class="sxs-lookup"><span data-stu-id="9c296-803">Office Suite</span></span>

- <div><span data-ttu-id="9c296-804">我們已修正在停用功能後，可能會提供版本歷程記錄的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-804">We fixed an issue which could offer version history when that feature was disabled</span></span></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1910-september-27"></a><span data-ttu-id="9c296-806">版本 1910：9 月 27 日</span><span class="sxs-lookup"><span data-stu-id="9c296-806">Version 1910: September 27</span></span>
<span data-ttu-id="9c296-807">*版本：1910 (組建 12119.20000)*</span><span class="sxs-lookup"><span data-stu-id="9c296-807">*Version 1910 (Build 12119.20000)*</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)
[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)
[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a><span data-ttu-id="9c296-811">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="9c296-811">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="9c296-812">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-812">Excel</span></span>

- <div><span data-ttu-id="9c296-813"><span>我們已修正當變更系列集合時，可能會導致散佈折線圖無法正確呈現的問題。</span></span><span class="sxs-lookup"><span data-stu-id="9c296-813"><span>We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="9c296-814">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-814">Outlook</span></span>

- <div><span data-ttu-id="9c296-815"><span>我們已修正了當與共享行事曆資料夾互動時，可能會報告權限錯誤的問題。</span></span><span class="sxs-lookup"><span data-stu-id="9c296-815"><span>We fixed an issue which could have reported permission errors when interacting with shared calendar folders</span></span></span></div>


- <div><span data-ttu-id="9c296-816"><span>我們已修正了使用者可能會無法新增附件至行事曆的問題。</span></span><span class="sxs-lookup"><span data-stu-id="9c296-816"><span>We fixed an issue which could have prevented users from adding attachments to calendars</span></span></span></div>


- <div><span data-ttu-id="9c296-817"><span>我們已修正了當回覆數位簽章的郵件時，導致顯示錯誤訊息的問題。</span></span><span class="sxs-lookup"><span data-stu-id="9c296-817"><span>We fixed an issue which caused error messages to display when replying to a digitally signed message</span></span></span></div>


### <a name="word"></a><span data-ttu-id="9c296-818">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-818">Word</span></span>

- <div><span data-ttu-id="9c296-819"><span>我們已修正列印到 Deskjet 印表機時，可能會導致縮放問題的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-819"><span>We fixed an issue which could have caused scaling issues when printing to Deskjet printers</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="9c296-820">Office 套件</span><span class="sxs-lookup"><span data-stu-id="9c296-820">Office Suite</span></span>

- <div><span data-ttu-id="9c296-821"><span>我們已修正中等粗體文字樣式不正確的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-821"><span>We fixed an issue where medium bold text could be incorrectly styled</span></span></span></div>


- <div><span data-ttu-id="9c296-822"><span>我們已修正當關閉具有擱置上傳的檔案時，使用者收到不正確錯誤訊息的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-822"><span>We fixed an issue where a user could be given an incorrect error message when closing a file with a pending upload</span></span></span></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1910-september-20"></a><span data-ttu-id="9c296-824">版本 1910：9 月 20 日</span><span class="sxs-lookup"><span data-stu-id="9c296-824">Version 1910: September 20</span></span>
<span data-ttu-id="9c296-825">*版本：1910 (組建 12112.20000)*</span><span class="sxs-lookup"><span data-stu-id="9c296-825">*Version 1910 (Build 12112.20000)*</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a><span data-ttu-id="9c296-829">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="9c296-829">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="9c296-830">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-830">Excel</span></span>

- <div><span data-ttu-id="9c296-831"><span>我們已修正 Excel 有時候會在啟動時發生懸置的問題。</span></span><span class="sxs-lookup"><span data-stu-id="9c296-831"><span>We fixed an issue where Excel could sometimes hang at launch</span></span></span></div>

### <a name="outlook"></a><span data-ttu-id="9c296-832">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-832">Outlook</span></span>

- <div><span data-ttu-id="9c296-833"><span>我們大幅改善了當有大量會議室可供選擇時，會議室選取的效能。</span></span><span class="sxs-lookup"><span data-stu-id="9c296-833"><span>We significantly improved the performance of room selection when there are a large number of rooms available</span></span></span></div>


- <div><span data-ttu-id="9c296-834"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">我們已修正在 Office 365.中移轉至新式驗證時，擁有 Outlook 多個信箱的客戶無法進行信箱同步處理的問題。</span></span><span class="sxs-lookup"><span data-stu-id="9c296-834"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">We fixed an issue that can prevent mailbox sync for customers with multiple mailboxes in Outlook when migrating to modern authentication in Office 365.</span></span></span><br></div>


- <div><span data-ttu-id="9c296-835"><span>我們已修正簽章標籤中某些字元不會顯示在下拉式功能表中的問題。</span></span><span class="sxs-lookup"><span data-stu-id="9c296-835"><span>We fixed an issue where some characters in signature labels would not display in the dropdown menu</span></span></span></div>


### <a name="project"></a><span data-ttu-id="9c296-836">Project</span><span class="sxs-lookup"><span data-stu-id="9c296-836">Project</span></span>

- <div><span data-ttu-id="9c296-837"><span>我們修正了使用本機資源取代企業資源時，可能會導致當機的問題。</span></span><span class="sxs-lookup"><span data-stu-id="9c296-837"><span>We fixed an issue which could cause a crash when replacing an enterprise resource with a local resource</span></span></span></div>


### <a name="word"></a><span data-ttu-id="9c296-838">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-838">Word</span></span>

- <div><span data-ttu-id="9c296-839"><span>我們已修正 [草稿模式] 中可能會導致同步捲動無法正常運作的問題。</span></span><span class="sxs-lookup"><span data-stu-id="9c296-839"><span>We fixed an issue which could prevent synchronous scrolling from working properly in draft view</span></span></span></div>


- <div><span data-ttu-id="9c296-840">我們已修正第一次儲存文件後可能導致 [工具提示] 無法正確顯示的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-840">We fixed an issue which could prevent Tool Tips from displaying properly after saving a document for the first time</span></span></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1910-september-13"></a><span data-ttu-id="9c296-842">版本 1910：9 月 13 日</span><span class="sxs-lookup"><span data-stu-id="9c296-842">Version 1910: September 13</span></span>
<span data-ttu-id="9c296-843">*版本 1910 (組建 12105.20000)*</span><span class="sxs-lookup"><span data-stu-id="9c296-843">*Version 1910 (Build 12105.20000)*</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a><span data-ttu-id="9c296-845">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="9c296-845">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="9c296-846">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-846">Excel</span></span>

- <div><span data-ttu-id="9c296-847"><span>我們已修正使用者在部分受保護的工作表中無法貼上超連結的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-847"><span>We fixed an issue which could prevent a user from pasting hyperlinks in some protected sheets</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="9c296-848">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-848">Outlook</span></span>

- <div><span data-ttu-id="9c296-849"><span>我們已修正 UI 可能停滯在精簡檢視中的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-849"><span>We fixed an issue where the UI could get stuck in a compact view</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="9c296-850">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-850">PowerPoint</span></span>

- <div><span data-ttu-id="9c296-851"><span>我們已修正使用者可能會在列印為 PDF 時發生錯誤的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-851"><span>We fixed an issue where a user could experience an error upon printing to PDF</span></span></span></div>


### <a name="project"></a><span data-ttu-id="9c296-852">Project</span><span class="sxs-lookup"><span data-stu-id="9c296-852">Project</span></span>

- <div><span data-ttu-id="9c296-853"><span>我們已修正在摘要任務上<span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">變更工時值時，如果已啟用受保護的工作則可能會造成當機的問題</span></span></span><span class="sxs-lookup"><span data-stu-id="9c296-853"><span>We fixed an issue where <span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">changes to a work value on a summary task could cause a crash if protected work is enabled</span></span></span></span></div>


- <span data-ttu-id="9c296-854"><font size=2 style="background-color:rgb(255, 255, 255);">我們已修正可能會禁止將事件同步處理到企業行事曆功能的問題</font></span><span class="sxs-lookup"><span data-stu-id="9c296-854"><font size=2 style="background-color:rgb(255, 255, 255);">We fixed an issue which could inhibit the ability to sync events with enterprise calendars</font></span></span>


### <a name="office-suite"></a><span data-ttu-id="9c296-855">Office 套件</span><span class="sxs-lookup"><span data-stu-id="9c296-855">Office Suite</span></span>

- <div><span data-ttu-id="9c296-856"><span>我們已修正可能會導致重複警告以捨棄本機檔案版本的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-856"><span>We fixed an issue which could cause a repeated warning to discard local versions of a file</span></span></span></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1910-september-06"></a><span data-ttu-id="9c296-858">版本 1910：9 月 6 日</span><span class="sxs-lookup"><span data-stu-id="9c296-858">Version 1910: September 06</span></span>
<span data-ttu-id="9c296-859">*版本 1910 (組建 12030.20004)*</span><span class="sxs-lookup"><span data-stu-id="9c296-859">*Version 1910 (Build 12030.20004)*</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="9c296-861">功能更新</span><span class="sxs-lookup"><span data-stu-id="9c296-861">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="9c296-862">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-862">Excel</span></span>

- <span data-ttu-id="9c296-863">**準備、設定、繪圖：** 抓取 Surface 手寫筆之後, 您就可以開始繪製。</span><span class="sxs-lookup"><span data-stu-id="9c296-863">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="9c296-864">深入了解</span><span class="sxs-lookup"><span data-stu-id="9c296-864">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="powerpoint"></a><span data-ttu-id="9c296-865">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-865">PowerPoint</span></span>

- <span data-ttu-id="9c296-866">**準備、設定、繪圖：** 抓取 Surface 手寫筆之後, 您就可以開始繪製。</span><span class="sxs-lookup"><span data-stu-id="9c296-866">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="9c296-867">深入了解</span><span class="sxs-lookup"><span data-stu-id="9c296-867">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="word"></a><span data-ttu-id="9c296-868">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-868">Word</span></span>

- <span data-ttu-id="9c296-869">**準備、設定、繪圖：** 抓取 Surface 手寫筆之後, 您就可以開始繪製。</span><span class="sxs-lookup"><span data-stu-id="9c296-869">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="9c296-870">深入了解</span><span class="sxs-lookup"><span data-stu-id="9c296-870">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a><span data-ttu-id="9c296-873">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="9c296-873">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="9c296-874">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-874">Excel</span></span>

- <div><span data-ttu-id="9c296-875"><span>我們已修正可能會導致功能區中的字型名稱與正在使用的字型不同的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-875"><span>We fixed an issue which could cause the font name in the ribbon to be different from the font being used</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="9c296-876">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-876">Outlook</span></span>

- <div><span data-ttu-id="9c296-877"><span>我們已修正當 Internet Explorer 中的受限制網站停用受保護模式時，可能會導致 Outlook 不適當的資源消耗的問題。</span></span><span class="sxs-lookup"><span data-stu-id="9c296-877"><span>We fixed an issue that could result in inappropriate resource consumption by Outlook when Protected Mode is disabled for Restricted Sites in Internet Explorer</span></span></span></div>


- <div><span data-ttu-id="9c296-878"><span>我們已修正當貼上 ANSI 原始碼的文字時, 有時可能會導致顯示 Unicode 字元的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-878"><span>We fixed an issue which could sometimes cause Unicode characters to appear when pasting text from an ANSI source</span></span></span></div>


- <div><span data-ttu-id="9c296-879"><span>我們已修正有些使用者在群組排程檢視中會不正確地顯示為離線的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-879"><span>We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span></span></div>


### <a name="word"></a><span data-ttu-id="9c296-880">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-880">Word</span></span>

- <div><span data-ttu-id="9c296-881"><span>我們已修正表格格式設定可能遺失的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-881"><span>We fixed an issue where table formatting could be lost</span></span></span></div>


- <div><span data-ttu-id="9c296-882"><span>我們已修正導致 Ctrl+V 鍵盤快速鍵中斷的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-882"><span>We fixed an issue which could break the ctrl+v keyboard shortcut</span></span></span></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1909-august-30"></a><span data-ttu-id="9c296-884">版本 1909：8 月 30 日</span><span class="sxs-lookup"><span data-stu-id="9c296-884">Version 1909: August 30</span></span>
<span data-ttu-id="9c296-885">*版本 1909 (組建 12026.20000)*</span><span class="sxs-lookup"><span data-stu-id="9c296-885">*Version 1909 (Build 12026.20000)*</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="9c296-887">功能更新</span><span class="sxs-lookup"><span data-stu-id="9c296-887">Feature updates</span></span>

### <a name="access"></a><span data-ttu-id="9c296-888">Access</span><span class="sxs-lookup"><span data-stu-id="9c296-888">Access</span></span>

- <span data-ttu-id="9c296-889">**快速尋找連結資料表：** 新的搜尋方塊可讓您輕鬆尋找連結資料表。</span><span class="sxs-lookup"><span data-stu-id="9c296-889">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-890">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-890">PowerPoint</span></span>

- <span data-ttu-id="9c296-891">**將圖例另存成 SVG：** 將圖表、圖形或其他圖例另存成可縮放向量圖形，其可調整大小，且不損失影像品質。</span><span class="sxs-lookup"><span data-stu-id="9c296-891">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="9c296-892">深入了解</span><span class="sxs-lookup"><span data-stu-id="9c296-892">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a><span data-ttu-id="9c296-895">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="9c296-895">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="9c296-896">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-896">Excel</span></span>

- <div><span data-ttu-id="9c296-897"><span>我們已修正&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">敏感度</span>的 keytip &nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">與其他 keytip 相衝突的問題。</span></span></span><span class="sxs-lookup"><span data-stu-id="9c296-897"><span>We fixed an issue where the keytip for&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">Sensitivity </span>was&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">conflicting with another keytip.</span></span></span></span></div>

- <div><span data-ttu-id="9c296-898"><span>我們已修正在嘗試儲存的同時使用共用活頁簿時所發生的問題。</span></span><span class="sxs-lookup"><span data-stu-id="9c296-898"><span>We fixed an issue that occurred while working on a shared workbook when trying to save.</span></span></span></div>

- <div><span data-ttu-id="9c296-899"><span>我們已修正 Excel 只列出位於「\Excel\Add-in Manager」登錄值中前 16 個增益集的問題。<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></span><span class="sxs-lookup"><span data-stu-id="9c296-899"><span>We fixed an issue where Excel only lists the first 16 addins located in the '\Excel\Add-in Manager' registry values.<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></span></span></div>


- <div><span data-ttu-id="9c296-900"><span>我們已修正 Frequency 函數會傳回不正確結果的問題。</span></span><span class="sxs-lookup"><span data-stu-id="9c296-900"><span>We fixed an issue where the function Frequency() returns incorrect results.</span></span></span></div>


- <div><span data-ttu-id="9c296-901"><span>我們已大幅提升透過色彩篩選的效能。</span></span><span class="sxs-lookup"><span data-stu-id="9c296-901"><span>We have significantly improved the performance of filtering by color.</span></span></span></div>


- <div><span data-ttu-id="9c296-902"><span>我們已修正 Surface 使用者移動滑鼠可能解譯為按一下滑鼠事件的問題。</span></span><span class="sxs-lookup"><span data-stu-id="9c296-902"><span>We fixed an issue for Surface users where moving the mouse could be interpreted as a mouse click event.</span></span></span></div>


- <div><span data-ttu-id="9c296-903"><span>我們已修正在 [尋找/取代] 對話方塊中鍵盤無法瀏覽的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-903"><span>We fixed an issue which prevented keyboard navigation in the Find/Replace dialog</span></span></span></div>


- <div><span data-ttu-id="9c296-904"><span>我們已修正某些字型名稱無法正確顯示的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-904"><span>We fixed an issue where the name of some fonts were not displayed correctly</span></span></span></div>


- <div><span data-ttu-id="9c296-905"><span>我們已修正 CSV 無法顯示為支援的檔案類型的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-905"><span>We fixed an issue which prevented CSV from appearing as a supported file type</span></span></span></div>


### <a name="access"></a><span data-ttu-id="9c296-906">Access</span><span class="sxs-lookup"><span data-stu-id="9c296-906">Access</span></span>

- <div><span data-ttu-id="9c296-907">我們已修正當使用共用資料庫時，使用者可能收到&quot;不一致的狀態&quot;錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-907">We fixed an issue where users could receive an &quot;inconsistent state&quot; error when using a shared database.</span></span></div>


- <div><span data-ttu-id="9c296-908"><span>我們已修正可能導致日期選擇器在不該出現時出現的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-908"><span>We fixed an issue which could cause the date picker to appear when it shouldn't</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="9c296-909">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-909">Outlook</span></span>

- <div><span data-ttu-id="9c296-910"><span>我們已修正部分 POP3 使用者無法顯示 HTML 內容的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-910"><span>We fixed an issue which prevented HTML content from appearing for some POP3 users</span></span></span></div>


- <div><span data-ttu-id="9c296-911"><span>我們已修正在無法使用的環境中工作時，從連絡人卡片的溢位功能表移除非功能性「Planner」連結的問題。</span></span><span class="sxs-lookup"><span data-stu-id="9c296-911"><span>We fixed an issue to remove non-functional 'Planner' link from the overflow menu in the contact card when working in environments where it is not available.</span></span></span></div>

### <a name="onenote"></a><span data-ttu-id="9c296-912">OneNote</span><span class="sxs-lookup"><span data-stu-id="9c296-912">OneNote</span></span>

- <div><span data-ttu-id="9c296-913"><span>我們已修正 &nbsp;OneNote 背景同步處理有時候會竊取焦點的問題。</span></span><span class="sxs-lookup"><span data-stu-id="9c296-913"><span>We fixed an issue where&nbsp;OneNote background sync was sometimes stealing focus.</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="9c296-914">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-914">PowerPoint</span></span>

- <div><span data-ttu-id="9c296-915"><span>我們已修正會影響 3D 盤旋的旋轉方向的問題。</span></span><span class="sxs-lookup"><span data-stu-id="9c296-915"><span>We fixed an issue which would affect the rotation orientation of a 3D Turntable.</span></span></span></div>

- <div><span data-ttu-id="9c296-916"><span>我們已修正如果超連結包含特殊字元便無法運作的問題。</span></span><span class="sxs-lookup"><span data-stu-id="9c296-916"><span>We fixed an issue which prevented some hyperlinks from working if they contained special characters.</span></span></span></div>

- <div><span data-ttu-id="9c296-917"><span>我們已修正會造成的同時開啟多個註解窗格的問題。</span></span><span class="sxs-lookup"><span data-stu-id="9c296-917"><span>We fixed an issue which caused multiple comment panes to open at the same time.</span></span></span></div>

### <a name="project"></a><span data-ttu-id="9c296-918">Project</span><span class="sxs-lookup"><span data-stu-id="9c296-918">Project</span></span>

- <div><span data-ttu-id="9c296-919"><span>我們已修正在列印團隊規劃檢視之後可能會導致當機的問題。</span></span><span class="sxs-lookup"><span data-stu-id="9c296-919"><span>We fixed an issue which could sometimes cause a crash after printing a Team Planner view.</span></span></span></div>

### <a name="word"></a><span data-ttu-id="9c296-920">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-920">Word</span></span>

- <div><span data-ttu-id="9c296-921">我們已<span>修正直排文字方塊中多位元組字元在閱讀檢視中顯示重疊的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-921">We f<span>ixed an issue where multi-byte characters in vertical text box are shown overlapped in reading view.</span></span><br></span></div>

- <div><span data-ttu-id="9c296-922"><span>我們&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">已修正當使用者在增益集中採取動作時，找不到日文明信片和賀卡相關增益集資源的問題。</span></span></span><span class="sxs-lookup"><span data-stu-id="9c296-922"><span>We&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">fixed an issue where Japanese post card and greeting card related addin resources are not found when the user takes action in the addin wizard.</span></span></span></span></div>

- <div><span data-ttu-id="9c296-923"><span>我們已修正在受保護的檢視中的標題列使用者介面會造成問題的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-923"><span>We fixed an issue which could cause issues with the Title Bar User Interface when in Protected View</span></span></span></div>

### <a name="office-suite"></a><span data-ttu-id="9c296-924">Office 套件</span><span class="sxs-lookup"><span data-stu-id="9c296-924">Office Suite</span></span>

- <div><span data-ttu-id="9c296-925"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"> 我們已修正當您在含有一般圖形和連接器圖形的選擇上變更圖形時的損毀檔案問題。</span></span></span><span class="sxs-lookup"><span data-stu-id="9c296-925"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"> We fixed a corrupt file issue when you Change Shape on a selection that contains both a normal shape and a connector shape.</span></span></span></span></div>

- <div><span data-ttu-id="9c296-926"><span>我們已修正<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">從多個外部顯示器使用固定/解除固定時會造成問題的問題。</span></span></span><span class="sxs-lookup"><span data-stu-id="9c296-926"><span>We fixed an issue that <span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">caused a problem in applications when using dock/undock from multiple external displays. </span></span></span></span></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="august-23-2019br"></a><span data-ttu-id="9c296-928">**2019 年 8 月 23 日**</span><span class="sxs-lookup"><span data-stu-id="9c296-928">**August 23, 2019**</span></span><br/>
<span data-ttu-id="9c296-929">版本 1909 (組建 12015.20004)</span><span class="sxs-lookup"><span data-stu-id="9c296-929">Version 1909 (Build 12015.20004)</span></span><br/>



## <a name="non-security-updates"></a><span data-ttu-id="9c296-930">非安全性更新：</span><span class="sxs-lookup"><span data-stu-id="9c296-930">Non-security updates:</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-931">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-931">Excel</span></span>

- <div><span data-ttu-id="9c296-932"><span>我們已大幅改善刪除合併儲存格的資料行的效能</span></span><span class="sxs-lookup"><span data-stu-id="9c296-932"><span>We significantly improved the performance of deleting columns with merged cells</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="9c296-933">Office 套件</span><span class="sxs-lookup"><span data-stu-id="9c296-933">Office Suite</span></span>

- <div><span data-ttu-id="9c296-934"><span>我們已修正在瀏覽器中檢視時，部分的 Unicode 字元可能會無法顯示的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-934"><span>We fixed an issue which could prevent some Unicode characters from being displayed when viewed in a browser</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="9c296-935">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-935">Outlook</span></span>

- <div><span data-ttu-id="9c296-936"><span>我們已修正可能會無法儲存檔案到 WebDAV 的位置的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-936"><span>We fixed an issue which could have prevented files from being saved to a WebDAV location</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="9c296-937">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-937">PowerPoint</span></span>

- <div><span data-ttu-id="9c296-938"><span>我們已修正當使用者點擊一個註解，但可能是另一個註解被選取的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-938"><span>We fixed an issue where a user would click on one comment, but another comment would be selected</span></span></span></div>





## <a name="august-16-2019br"></a><span data-ttu-id="9c296-939">**2019 年 8 月 16 日**</span><span class="sxs-lookup"><span data-stu-id="9c296-939">**August 16, 2019**</span></span><br/>
<span data-ttu-id="9c296-940">版本 1909 (組建 12013.20000)</span><span class="sxs-lookup"><span data-stu-id="9c296-940">Version 1909 (Build 12013.20000)</span></span><br/>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="9c296-941">PowerPoint 功能更新：</span><span class="sxs-lookup"><span data-stu-id="9c296-941">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="9c296-942">**列印講義上的投影片編號：** 投影片編號會自動包含在講義上。</span><span class="sxs-lookup"><span data-stu-id="9c296-942">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="9c296-943">由您決定將其保留或關閉。</span><span class="sxs-lookup"><span data-stu-id="9c296-943">Leave them on, turn them off, it's all up to you.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="9c296-944">非安全性更新：</span><span class="sxs-lookup"><span data-stu-id="9c296-944">Non-security updates:</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-945">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-945">Excel</span></span>

- <div><span data-ttu-id="9c296-946"><span>我們已修正可能會導致 AutoSave 自動開啟的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-946"><span>We fixed an issue which could cause AutoSave to become enabled</span></span></span></div>


- <div><span data-ttu-id="9c296-947">我們已修正可能會導致不正確計算儲存格高度的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-947">We fixed an issue which could result in cell heights being measured inaccurately</span></span></div>


### <a name="office-suite"></a><span data-ttu-id="9c296-948">Office 套件</span><span class="sxs-lookup"><span data-stu-id="9c296-948">Office Suite</span></span>

- <div><span data-ttu-id="9c296-949"><span>我們已修正了一個問題，將能大幅改善註解功能的效能</span></span><span class="sxs-lookup"><span data-stu-id="9c296-949"><span>We fixed an issue which significantly improves the performance of the Comments feature</span></span></span></div>


- <div><span data-ttu-id="9c296-950"><span>我們已修正搜尋時使用方向鍵可能會造成當機的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-950"><span>We fixed an issue which could cause a crash when using arrow keys while in search</span></span></span></div>


- <div><span data-ttu-id="9c296-951"><span>我們已修正如果將 @ 符號放在特定字元後，可能會無法使用 @ 提及的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-951"><span>We fixed an issue which could prevent an @ mention if the @ symbol was placed after certain characters</span></span></span></div>


- <div><span data-ttu-id="9c296-952"><span>我們已修正在刪除 @ 提及時，可能會導致當機的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-952"><span>We fixed an issue which could sometimes cause a crash when deleting @ mentions</span></span></span></div>


- <div><span data-ttu-id="9c296-953"><span>我們已修正無法在註解卡正確顯示 Emoji 的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-953"><span>We fixed an issue which prevented emojis from displaying correctly in comment cards</span></span></span></div>


- <div><span data-ttu-id="9c296-954"><span>我們已修正使用中​的​剪貼簿​​有時可能會導致當機的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-954"><span>We fixed an issue with Active Clipboard which could sometimes result in a crash</span></span></span></div>


- <div><span data-ttu-id="9c296-955"><span>我們已修正可能會導致快速存取工具列按鈕停止運作的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-955"><span>We fixed an issue which could cause the Quick Access Toolbar buttons to stop working</span></span></span></div>


- <div><span data-ttu-id="9c296-956"><span>我們已修正無法讓文件格式設定預覽切換到背景的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-956"><span>We fixed an issue which could prevent the Document Formatting Preview from switching to the background</span></span></span></div>

### <a name="onenote"></a><span data-ttu-id="9c296-957">OneNote</span><span class="sxs-lookup"><span data-stu-id="9c296-957">OneNote</span></span>

- <span data-ttu-id="9c296-958">我們已修正當 Office 佈景主題設為黑色，區段下拉式清單中的區段名稱顯示為空白的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-958">We fixed an issue where the names of sections appear blank in the section dropdown list when Office Theme is set to Black.</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-959">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-959">Outlook</span></span>

- <div><span data-ttu-id="9c296-960"><span>我們已修正在傳送​​事件時可能會導致 Outlook 重複獲取和失去焦點的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-960"><span>We fixed an issue with Send Events which could cause Outlook to repeatedly gain and lose focus</span></span></span></div>


- <div><span data-ttu-id="9c296-961"><span>我們已修正無法從工作資料夾的捷徑張貼回覆的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-961"><span>We fixed an issue which prevented the Post Reply to Folder shortcut from working</span></span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="9c296-962">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-962">PowerPoint</span></span>

- <div><span data-ttu-id="9c296-963"><span>我們已修正受保護的檢視有時候可能會在合作時造成問題的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-963"><span>We fixed an issue with Protected View which could sometimes cause problems when collaborating</span></span></span></div>


- <div><span data-ttu-id="9c296-964"><span>我們已修正可能無法正確顯示註解窗格中工作的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-964"><span>We fixed an issue which could prevent tasks in comment panes from displaying properly</span></span></span></div>


- <div><span data-ttu-id="9c296-965"><span>我們已修正插入新投影片時可能會造成當機的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-965"><span>We fixed an issue which could cause a crash when inserting new slides</span></span></span></div>


### <a name="user-lifecycle"></a><span data-ttu-id="9c296-966">使用者生命週期</span><span class="sxs-lookup"><span data-stu-id="9c296-966">User Lifecycle</span></span>

- <div><span data-ttu-id="9c296-967"><span>我們已修正有時候可能會導致訂閱功能消失的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-967"><span>We fixed an issue which could sometimes result in subscription features disappearing</span></span></span></div>


### <a name="word"></a><span data-ttu-id="9c296-968">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-968">Word</span></span>

- <div><span data-ttu-id="9c296-969"><span>我們已修正如果超連結包含特定字元，則超連結可能會中斷的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-969"><span>We fixed an issue where hyperlinks could be broken if the hyperlink contained certain characters</span></span></span></div>


- <div><span data-ttu-id="9c296-970"><span>我們已修正在檢視影像註解時，影像可能會調整至不正確大小的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-970"><span>We fixed an issue where images could be improperly sized when viewing a comment for that image</span></span></span></div>


- <div><span data-ttu-id="9c296-971"><span>我們已修正項目符號清單下拉式功能表有時可能會導致當機的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-971"><span>We fixed an issue with the Bullet List drop down menu which could sometimes result in a crash</span></span></span></div>





## <a name="august-09-2019br"></a><span data-ttu-id="9c296-972">**2019 年 8 月 9 日**</span><span class="sxs-lookup"><span data-stu-id="9c296-972">**August 09, 2019**</span></span><br/>
<span data-ttu-id="9c296-973">版本 1909 (組建 12001.20000)</span><span class="sxs-lookup"><span data-stu-id="9c296-973">Version 1909 (Build 12001.20000)</span></span><br/>

### <a name="excel-feature-updates"></a><span data-ttu-id="9c296-974">Excel 功能更新：</span><span class="sxs-lookup"><span data-stu-id="9c296-974">Excel Feature updates:</span></span>

- <span data-ttu-id="9c296-975">**共同作業變得更容易：** 共同撰寫的增強功能表示，使用條件式格式設定、儲存格樣式等等時，您的變更會與共同作業者的變更順暢地合併。</span><span class="sxs-lookup"><span data-stu-id="9c296-975">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>


- <span data-ttu-id="9c296-976">**搜尋並享受：** 我們對插入圖示新增了搜尋，讓您易於找到您要的圖示。</span><span class="sxs-lookup"><span data-stu-id="9c296-976">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="9c296-977">而當您選取時，[插入] 按鈕會告知您已經選取的數量。</span><span class="sxs-lookup"><span data-stu-id="9c296-977">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="office-suite-feature-updates"></a><span data-ttu-id="9c296-978">Office 套件功能更新：</span><span class="sxs-lookup"><span data-stu-id="9c296-978">Office Suite Feature updates:</span></span>

- <span data-ttu-id="9c296-979">**新的 Office 應用程式圖示：** 重新設計的應用程式圖示，可反映簡單、功能強大且智慧型的 Office 體驗</span><span class="sxs-lookup"><span data-stu-id="9c296-979">**New Office app icons:** Redesigned app icons to reflect the simple, powerful, and intelligent experiences of Office</span></span>


### <a name="outlook-feature-updates"></a><span data-ttu-id="9c296-980">Outlook 功能更新：</span><span class="sxs-lookup"><span data-stu-id="9c296-980">Outlook Feature updates:</span></span>

- <span data-ttu-id="9c296-981">**抵禦攻擊的進階防護：** 使用 Office 365 進階威脅防護，您會受到保護，不受電子郵件主旨、附加的郵件、簽署的郵件、網路路徑內超連結的攻擊。</span><span class="sxs-lookup"><span data-stu-id="9c296-981">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>


- <span data-ttu-id="9c296-982">**搜尋並享受：** 我們對插入圖示新增了搜尋，讓您易於找到您要的圖示。</span><span class="sxs-lookup"><span data-stu-id="9c296-982">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="9c296-983">而當您選取時，[插入] 按鈕會告知您已經選取的數量。</span><span class="sxs-lookup"><span data-stu-id="9c296-983">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="9c296-984">PowerPoint 功能更新：</span><span class="sxs-lookup"><span data-stu-id="9c296-984">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="9c296-985">**搜尋並享受：** 我們對插入圖示新增了搜尋，讓您易於找到您要的圖示。</span><span class="sxs-lookup"><span data-stu-id="9c296-985">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="9c296-986">而當您選取時，[插入] 按鈕會告知您已經選取的數量。</span><span class="sxs-lookup"><span data-stu-id="9c296-986">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="word-feature-updates"></a><span data-ttu-id="9c296-987">Word 功能更新：</span><span class="sxs-lookup"><span data-stu-id="9c296-987">Word Feature updates:</span></span>

- <span data-ttu-id="9c296-988">**其他人更快速看到您的變更：** 共同撰寫增強功能表示，共同作業者可較以往更快速看到您的變更。</span><span class="sxs-lookup"><span data-stu-id="9c296-988">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>


- <span data-ttu-id="9c296-989">**搜尋並享受：** 我們對插入圖示新增了搜尋，讓您易於找到您要的圖示。</span><span class="sxs-lookup"><span data-stu-id="9c296-989">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="9c296-990">而當您選取時，[插入] 按鈕會告知您已經選取的數量。</span><span class="sxs-lookup"><span data-stu-id="9c296-990">And when you're selecting, the Insert button tells you how many you've picked.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="9c296-991">非安全性更新：</span><span class="sxs-lookup"><span data-stu-id="9c296-991">Non-security updates:</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-992">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-992">Outlook</span></span>

- <div><span data-ttu-id="9c296-993"><span>我們已修正會導致會議收件者在取消會議後收到兩次通知的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-993"><span>We fixed an issue which caused meeting recipients to receive two notifications after a meeting was cancelled</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="9c296-994">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-994">PowerPoint</span></span>

- <div><span data-ttu-id="9c296-995"><span>我們已修正當使用者對圖形與圖示選取 [無外框] 或 [無填滿] 時會導致損毀的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-995"><span>We fixed an issue which could cause a crash when the user selected No Outline or No Fill for Shapes and Icons</span></span></span></div>





## <a name="august-02-2019br"></a><span data-ttu-id="9c296-996">**2019 年 8 月 2 日**</span><span class="sxs-lookup"><span data-stu-id="9c296-996">**August 02, 2019**</span></span><br/>
<span data-ttu-id="9c296-997">版本 1908 (組建 11929.20002)</span><span class="sxs-lookup"><span data-stu-id="9c296-997">Version 1908 (Build 11929.20002)</span></span><br/>

### <a name="excel-feature-updates"></a><span data-ttu-id="9c296-998">Excel 功能更新：</span><span class="sxs-lookup"><span data-stu-id="9c296-998">Excel Feature updates:</span></span>

- <span data-ttu-id="9c296-999">**轉換檔案，以改善協助工具功能：** 將您的檔案升級為現代格式，讓所有人更容易存取。</span><span class="sxs-lookup"><span data-stu-id="9c296-999">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="9c296-1000">**將敏感度標籤套用至您的文件**：將敏感度標籤套用至您的檔案和電子郵件，使其符合貴組織的資訊保護原則。</span><span class="sxs-lookup"><span data-stu-id="9c296-1000">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="outlook-feature-updates"></a><span data-ttu-id="9c296-1001">Outlook 功能更新：</span><span class="sxs-lookup"><span data-stu-id="9c296-1001">Outlook Feature updates:</span></span>

- <span data-ttu-id="9c296-1002">**將敏感度標籤套用至您的文件**：將敏感度標籤套用至您的檔案和電子郵件，使其符合貴組織的資訊保護原則。</span><span class="sxs-lookup"><span data-stu-id="9c296-1002">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="9c296-1003">PowerPoint 功能更新：</span><span class="sxs-lookup"><span data-stu-id="9c296-1003">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="9c296-1004">**轉換檔案，以改善協助工具功能：** 將您的檔案升級為現代格式，讓所有人更容易存取。</span><span class="sxs-lookup"><span data-stu-id="9c296-1004">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="9c296-1005">**將敏感度標籤套用至您的文件**：將敏感度標籤套用至您的檔案和電子郵件，使其符合貴組織的資訊保護原則。</span><span class="sxs-lookup"><span data-stu-id="9c296-1005">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="word-feature-updates"></a><span data-ttu-id="9c296-1006">Word 功能更新：</span><span class="sxs-lookup"><span data-stu-id="9c296-1006">Word Feature updates:</span></span>

- <span data-ttu-id="9c296-1007">**轉換檔案，以改善協助工具功能：** 將您的檔案升級為現代格式，讓所有人更容易存取。</span><span class="sxs-lookup"><span data-stu-id="9c296-1007">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="9c296-1008">**用其他方式表達：** 當您想要以不同方式表達時，「重寫」功能可以幫助您。</span><span class="sxs-lookup"><span data-stu-id="9c296-1008">**Say it another way:** When you want to say it differently, Rewrite is there to help.</span></span> <span data-ttu-id="9c296-1009">重寫提供其他不同方式來表達您的詞彙。</span><span class="sxs-lookup"><span data-stu-id="9c296-1009">Rewrite offers alternatives for finessing your phrases.</span></span>


- <span data-ttu-id="9c296-1010">**將敏感度標籤套用至您的文件**：將敏感度標籤套用至您的檔案和電子郵件，使其符合貴組織的資訊保護原則。</span><span class="sxs-lookup"><span data-stu-id="9c296-1010">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="9c296-1011">非安全性更新：</span><span class="sxs-lookup"><span data-stu-id="9c296-1011">Non-security updates:</span></span>

### <a name="access"></a><span data-ttu-id="9c296-1012">Access</span><span class="sxs-lookup"><span data-stu-id="9c296-1012">Access</span></span>
- <span data-ttu-id="9c296-1013">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1013">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-1014">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-1014">Excel</span></span>

- <div><span data-ttu-id="9c296-1015"><span>我們已修正了列印至 PDF 時，&quot;重複所有標籤&quot;看起來像已套用的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-1015"><span>We fixed an issue which made it appear as though &quot;repeat all labels&quot; was applied when printing to a PDF</span></span></span></div>

### <a name="office-suite"></a><span data-ttu-id="9c296-1016">Office 套件</span><span class="sxs-lookup"><span data-stu-id="9c296-1016">Office Suite</span></span>

- <div><span data-ttu-id="9c296-1017"><span>我們已修正了使用者可能無法從桌面開啟文件的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-1017"><span>We fixed an issue which could have prevented users from opening a document from the desktop</span></span></span></div>

- <div><span data-ttu-id="9c296-1018"><span>我們已修正了&quot;另一個安裝正在進行中&quot;的不正確錯誤訊息，可能導致無法升級的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-1018"><span>We fixed an issue where an upgrade could be prevented by a incorrect error message of &quot;Another install in progress&quot;</span></span></span></div>

- <div><span data-ttu-id="9c296-1019"><span>我們已修正了安全性更新安裝後，使用者可能會看到錯誤訊息的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-1019"><span>We fixed an issue where a user could see error messages when security updates are installed</span></span></span></div>

- <div><span data-ttu-id="9c296-1020"><span>我們已修正了可能會造成游標消失的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-1020"><span>We fixed an issue which could cause the cursor to disappear</span></span></span></div>

- <div><span data-ttu-id="9c296-1021"><span>我們已修正了使用者可能預設前往 [繪圖] 索引標籤而不是 [常用] 索引標籤的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-1021"><span>We fixed an issue where a user could be defaulted to the draw tab instead of the home tab</span></span></span></div>

- <div><span data-ttu-id="9c296-1022"><span>我們已修正了大型樹狀檢視可能會導致當機的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-1022"><span>We fixed an issue where large tree views could result in a crash</span></span></span></div>

### <a name="outlook"></a><span data-ttu-id="9c296-1023">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-1023">Outlook</span></span>

- <div></div><span data-ttu-id="9c296-1024"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">我們已修正了可能導致系統重複提示輸入密碼的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-1024"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">We fixed an issue that can cause repeated password prompts</span></span></span>

- <div><span data-ttu-id="9c296-1025"><span>我們已修正了可能無法正確查詢電子郵件地址的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-1025"><span>We fixed an issue which could prevent an email address from being queried correctly</span></span></span></div>

- <div><span data-ttu-id="9c296-1026"><span>我們已修正了可能導致使用者無法開啟由舊版 Outlook 建立之行事曆項目的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-1026"><span>We fixed an issue which could prevent users from opening calendar items created by legacy versions of Outlook</span></span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="9c296-1027">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-1027">PowerPoint</span></span>

- <div><span data-ttu-id="9c296-1028"><span>我們已修正了部分動畫無法開始的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-1028"><span>We fixed an issue which could prevent some animations from starting</span></span></span></div>

### <a name="project"></a><span data-ttu-id="9c296-1029">Project</span><span class="sxs-lookup"><span data-stu-id="9c296-1029">Project</span></span>
- <span data-ttu-id="9c296-1030">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1030">Various performance and stability fixes</span></span>

### <a name="word"></a><span data-ttu-id="9c296-1031">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-1031">Word</span></span>

- <div><span data-ttu-id="9c296-1032"><span>我們已修正了註解的回覆以錯誤順序顯示的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-1032"><span>We fixed an issue where replies to comments could appear out of order</span></span></span></div>

- <div><span data-ttu-id="9c296-1033"><span>我們已修正了在某些情況下，會顯示提示而非顯示註解的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-1033"><span>We fixed an issue where in some situations, hints would be displayed instead of comments</span></span></span></div>

- <div><span data-ttu-id="9c296-1034"><span>我們已修正了當使用者嘗試新增註解時，可能會顯示 [修訂窗格] 的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-1034"><span>We fixed an issue where the Revisions Pane could display when the user tried to add a new comment</span></span></span></div>

- <div><span data-ttu-id="9c296-1035"><span>我們已修正了可能無法顯示 [復原] 下拉式清單的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-1035"><span>We fixed an issue which could prevent the undo dropdown list from appearing</span></span></span></div>

- <div><span data-ttu-id="9c296-1036"><span>我們已修正了有時無法新增註解的問題</span></span><span class="sxs-lookup"><span data-stu-id="9c296-1036"><span>We fixed an issue which could prevent comments from being added</span></span></span></div>


## <a name="july-26-2019"></a><span data-ttu-id="9c296-1037">2019 年 7 月 26 日</span><span class="sxs-lookup"><span data-stu-id="9c296-1037">July 26, 2019</span></span>
<span data-ttu-id="9c296-1038">版本 1908 (組建 11916.20000)</span><span class="sxs-lookup"><span data-stu-id="9c296-1038">Version 1908 (build 11916.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9c296-1039">新功能：</span><span class="sxs-lookup"><span data-stu-id="9c296-1039">What's New:</span></span>

### <a name="word-excel-powerpoint"></a><span data-ttu-id="9c296-1040">Word、Excel、PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-1040">Word, Excel, PowerPoint</span></span>

#### <a name="create-more-accessible-pdfs"></a><span data-ttu-id="9c296-1041">建立更易於存取的 PDF</span><span class="sxs-lookup"><span data-stu-id="9c296-1041">Create more accessible PDFs</span></span>

<span data-ttu-id="9c296-1042">建立 PDF 檔案，然後協助工具檢查程式會指出在儲存之前應該修正的協助工具問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-1042">Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9c296-1043">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="9c296-1043">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="9c296-1044">全部</span><span class="sxs-lookup"><span data-stu-id="9c296-1044">All</span></span>

- <span data-ttu-id="9c296-1045">我們修正了 Office 更新後 Office 文件類型關聯和圖示有時會中斷的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1045">We fixed an issue where file type association and icons for Office could sometimes break after an Office Update</span></span>

### <a name="word"></a><span data-ttu-id="9c296-1046">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-1046">Word</span></span> 
- <span data-ttu-id="9c296-1047">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1047">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-1048">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-1048">Excel</span></span>
- <span data-ttu-id="9c296-1049">我們修正了移動圖表有時會導致當機的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1049">We fixed an issue where moving a chart could sometimes result in a crash</span></span>
- <span data-ttu-id="9c296-1050">我們修正了在更改圖表類型後從 Chart 物件獲取 Workbook 物件有時會導致錯誤的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1050">We fixed an issue where to get Workbook object from Chart object after changing chart types could sometimes result in an error</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-1051">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-1051">PowerPoint</span></span>
- <span data-ttu-id="9c296-1052">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1052">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-1053">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-1053">Outlook</span></span>
- <span data-ttu-id="9c296-1054">我們修正了在簡化版的功能區中，停用的控制項有時不會呈現灰色的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1054">We fixed an issue where in simplified ribbon, a disabled control could sometimes not be greyed out in the ribbon</span></span>

### <a name="access"></a><span data-ttu-id="9c296-1055">Access</span><span class="sxs-lookup"><span data-stu-id="9c296-1055">Access</span></span>
- <span data-ttu-id="9c296-1056">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1056">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9c296-1057">Project</span><span class="sxs-lookup"><span data-stu-id="9c296-1057">Project</span></span>
- <span data-ttu-id="9c296-1058">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1058">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-19-2019"></a><span data-ttu-id="9c296-1059">2019 年 7 月 19 日</span><span class="sxs-lookup"><span data-stu-id="9c296-1059">July 19, 2019</span></span>
<span data-ttu-id="9c296-1060">版本 1908 (組建 11911.20000)</span><span class="sxs-lookup"><span data-stu-id="9c296-1060">Version 1908 (build 11911.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9c296-1061">新功能：</span><span class="sxs-lookup"><span data-stu-id="9c296-1061">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="9c296-1062">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-1062">Word</span></span>

#### <a name="learn-what-acronyms-mean-when-you-read-in-word-online"></a><span data-ttu-id="9c296-1063">了解在 Word Online 中閱讀時，縮略字代表的意義</span><span class="sxs-lookup"><span data-stu-id="9c296-1063">Learn what Acronyms mean when you read in Word Online</span></span>

<span data-ttu-id="9c296-1064">當您遇到縮略字時，我們會嘗試使用組織的資料來定義縮略字。</span><span class="sxs-lookup"><span data-stu-id="9c296-1064">When you encounter an Acronym, we'll try to define it using data from within your organization.</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="9c296-1065">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="9c296-1065">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="9c296-1066">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-1066">Word</span></span> 
- <span data-ttu-id="9c296-1067">我們已修正 BookMarkEnd 標記遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-1067">We fixed an issue which BookMarkEnd tag was missing.</span></span>
- <span data-ttu-id="9c296-1068">我們已修正字型選項會在使用者輸入特殊字元時變更的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-1068">We fixed an issue where the font selection could change while the user was typing special characters</span></span>
- <span data-ttu-id="9c296-1069">我們已修正有時候可能會造成新註解卡片有空白回覆的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-1069">We fixed an issue which could sometimes cause blank replies to a new comment card</span></span>
- <span data-ttu-id="9c296-1070">我們已修正共用電子郵件時可能會造成格式遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-1070">We fixed an issue which could cause formatting to be lost when sharing an email</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-1071">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-1071">Excel</span></span>
- <span data-ttu-id="9c296-1072">我們已修正大範圍的陣列有時可能會造成當機的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-1072">We fixed an issue where an array with a large range could sometimes cause a crash</span></span>
- <span data-ttu-id="9c296-1073">我們已大幅改善從篩選範圍複製資料的效能。</span><span class="sxs-lookup"><span data-stu-id="9c296-1073">We significantly improved the performance of copying data from filtered ranges</span></span>
- <span data-ttu-id="9c296-1074">我們已修正如果檔案名稱包含特殊字元便無法開啟某些檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-1074">We fixed an issue which prevented some files from opening if the filenames contained special characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-1075">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-1075">PowerPoint</span></span>
- <span data-ttu-id="9c296-1076">我們已修正 PowerPoint 中預設未選取新建區段的區段名稱問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-1076">We fixed an issue where section name was not selected by default for newly created section in PowerPoint.</span></span>
- <span data-ttu-id="9c296-1077">我們已修正使用 4:3 顯示器時 UI 變得難以使用的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-1077">We fixed an issue which could cause the UI to become difficult to use when using a 4:3 display</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-1078">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-1078">Outlook</span></span>
- <span data-ttu-id="9c296-1079">我們已修正無法列出可用會議室的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-1079">We fixed an issue which could prevent available rooms from being listed</span></span>
- <span data-ttu-id="9c296-1080">我們已修正部分 POP3 使用者無法使用 HTML 格式的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-1080">We fixed an issue which prevented HTML formatting for some POP3 users</span></span>

### <a name="access"></a><span data-ttu-id="9c296-1081">Access</span><span class="sxs-lookup"><span data-stu-id="9c296-1081">Access</span></span>
- <span data-ttu-id="9c296-1082">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1082">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9c296-1083">Project</span><span class="sxs-lookup"><span data-stu-id="9c296-1083">Project</span></span>
- <span data-ttu-id="9c296-1084">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1084">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-12-2019"></a><span data-ttu-id="9c296-1085">2019 年 7 月 12 日</span><span class="sxs-lookup"><span data-stu-id="9c296-1085">July 12, 2019</span></span>
<span data-ttu-id="9c296-1086">版本 1907 (組建 11901.20038)</span><span class="sxs-lookup"><span data-stu-id="9c296-1086">Version 1907 (build 11901.20038)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9c296-1087">新功能：</span><span class="sxs-lookup"><span data-stu-id="9c296-1087">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-1088">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-1088">PowerPoint</span></span>
 
#### <a name="use-ink-replay-in-your-presentations"></a><span data-ttu-id="9c296-1089">在簡報中使用筆跡重播</span><span class="sxs-lookup"><span data-stu-id="9c296-1089">Use ink replay in your presentations</span></span>
 
<span data-ttu-id="9c296-1090">套用 PowerPoint 的筆跡重播動畫，使簡報的表達和溝通更加生動。</span><span class="sxs-lookup"><span data-stu-id="9c296-1090">Apply a replay animation for ink in PowerPoint to express and communicate more in presentations.</span></span> 

## <a name="notable-fixes"></a><span data-ttu-id="9c296-1091">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="9c296-1091">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="9c296-1092">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-1092">Word</span></span> 
- <span data-ttu-id="9c296-1093">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1093">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-1094">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-1094">Excel</span></span>
- <span data-ttu-id="9c296-1095">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1095">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-1096">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-1096">PowerPoint</span></span>
- <span data-ttu-id="9c296-1097">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1097">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-1098">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-1098">Outlook</span></span>
- <span data-ttu-id="9c296-1099">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1099">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="9c296-1100">Access</span><span class="sxs-lookup"><span data-stu-id="9c296-1100">Access</span></span>
- <span data-ttu-id="9c296-1101">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1101">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9c296-1102">Project</span><span class="sxs-lookup"><span data-stu-id="9c296-1102">Project</span></span>
- <span data-ttu-id="9c296-1103">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1103">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-5-2019"></a><span data-ttu-id="9c296-1104">2019 年 7 月 5 日</span><span class="sxs-lookup"><span data-stu-id="9c296-1104">July 5, 2019</span></span>
<span data-ttu-id="9c296-1105">版本 1907 (組建 11901.20018)</span><span class="sxs-lookup"><span data-stu-id="9c296-1105">Version 1907 (build 11901.20018)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9c296-1106">新功能：</span><span class="sxs-lookup"><span data-stu-id="9c296-1106">What's New:</span></span>

### <a name="word-excel-powerpoint"></a><span data-ttu-id="9c296-1107">Word、Excel、PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-1107">Word, Excel, PowerPoint</span></span>

#### <a name="sketchy-shapes"></a><span data-ttu-id="9c296-1108">素描形狀！</span><span class="sxs-lookup"><span data-stu-id="9c296-1108">Sketchy Shapes!</span></span>

<span data-ttu-id="9c296-1109">仍在編寫簡報的草稿嗎？</span><span class="sxs-lookup"><span data-stu-id="9c296-1109">In the middle of drafting a presentation?</span></span> <span data-ttu-id="9c296-1110">套用素描樣式來顯示您仍在處理文件。</span><span class="sxs-lookup"><span data-stu-id="9c296-1110">Apply the sketchy style to show that you're still working on it.</span></span> <span data-ttu-id="9c296-1111">此功能可在不將物件轉換成自由格式、手繪形狀的情況下，為您的物件賦與個人風格。</span><span class="sxs-lookup"><span data-stu-id="9c296-1111">It gives a personal touch to your objects without turning it into a free form, hand-drawn shapes.</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-1112">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-1112">Excel</span></span>

- <span data-ttu-id="9c296-1113">**更快速共用檔案**：不需開啟檔案，即可從最近使用清單直接共用您的檔案。</span><span class="sxs-lookup"><span data-stu-id="9c296-1113">**Faster file sharing**: Share your documents right from the recently used list without having to open the file.</span></span>
### <a name="powerpoint"></a><span data-ttu-id="9c296-1114">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-1114">PowerPoint</span></span>

- <span data-ttu-id="9c296-1115">**[在講義上列印投影片編號] 設定已移至 [列印] 功能表，以易於存取：** 選取講義版面配置時，可在 [列印] > [整頁模式] 下拉式清單中找到它。</span><span class="sxs-lookup"><span data-stu-id="9c296-1115">**The setting to Print Slide Numbers in Handouts has been moved to the Print Menu for easier access:**  Find it in the Print > Print Layout dropdown when a Handout layout is selected.</span></span> <span data-ttu-id="9c296-1116">這也會使得每個簡報的設定易於切換。</span><span class="sxs-lookup"><span data-stu-id="9c296-1116">This also allows the setting to be easily toggled per presentation.</span></span> [<span data-ttu-id="9c296-1117">深入了解</span><span class="sxs-lookup"><span data-stu-id="9c296-1117">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="9c296-1118">**更快速共用檔案：** 不需開啟檔案，即可從最近使用清單直接共用您的檔案。</span><span class="sxs-lookup"><span data-stu-id="9c296-1118">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

### <a name="word"></a><span data-ttu-id="9c296-1119">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-1119">Word</span></span>

- <span data-ttu-id="9c296-1120">**更快速共用檔案：** 不需開啟檔案，即可從最近使用清單直接共用您的檔案。</span><span class="sxs-lookup"><span data-stu-id="9c296-1120">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9c296-1121">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="9c296-1121">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="9c296-1122">全部</span><span class="sxs-lookup"><span data-stu-id="9c296-1122">All</span></span>
- <span data-ttu-id="9c296-1123">我們已大幅提高功能區 KeyTip 的效能</span><span class="sxs-lookup"><span data-stu-id="9c296-1123">We significantly improved the performance of Ribbon KeyTips</span></span>
- <span data-ttu-id="9c296-1124">我們已修正無法正常顯示 [查看即將推出的新功能] 方塊的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1124">We fixed an issue which prevented the "See what's coming soon" dialog from being displayed properly</span></span>
- <span data-ttu-id="9c296-1125">我們已修正可能會導致共同撰寫圖庫飛出視窗中的相片排列錯誤的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1125">We fixed an issue which could cause Photos to be misaligned in the Co-auth Gallery flyout</span></span>

### <a name="word"></a><span data-ttu-id="9c296-1126">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-1126">Word</span></span> 
- <span data-ttu-id="9c296-1127">我們已修正有時無法加入新註解的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1127">We fixed an issue which could sometimes prevent new comments from being added</span></span>
- <span data-ttu-id="9c296-1128">我們已修正表格有時可能會造成當機的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1128">We fixed an issue where tables could sometimes cause a crash</span></span>
- <span data-ttu-id="9c296-1129">我們已修正無效的資料有時可能會新增至合併列印結尾的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1129">We fixed an issue where invalid data could sometimes be added to the end of a mail merge</span></span>
- <span data-ttu-id="9c296-1130">我們已修正可能會導致不正確呈現部分 LaTeX 方程式的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1130">We fixed an issue which could cause some LaTeX equations to render incorrectly</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-1131">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-1131">Excel</span></span>
- <span data-ttu-id="9c296-1132">我們已修正變更圖表類型有時可能會導致執行階段例外狀況的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1132">We fixed an issue where changing chart types could sometimes result in a runtime exception</span></span>
- <span data-ttu-id="9c296-1133">我們已修正開啟多個視窗時會顯示不正確功能區的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1133">We fixed an issue where the incorrect ribbon could be displayed when multiple windows were open</span></span>
- <span data-ttu-id="9c296-1134">我們已修正巨集開啟活頁簿的第二個執行個體時可能會造成錯誤的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1134">We fixed an issue which could cause an error when a macro opened a second instance of a workbook</span></span>
- <span data-ttu-id="9c296-1135">我們已修正開啟或建立活頁簿，或切換使用不同的活頁簿時可能會造成當機的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1135">We fixed an issue which could cause a crash when opening or creating a workbook, or switching between workbooks</span></span>
- <span data-ttu-id="9c296-1136">我們已修正使用者無法在 Teams 中開啟透過 Word 建立之 PDF 的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1136">We fixed an issue preventing users from opening a PDF created from Word in Teams</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-1137">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-1137">PowerPoint</span></span>
- <span data-ttu-id="9c296-1138">我們已修正匯出成 PDF 時會降低圖表品質的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1138">We fixed an issue which would degrade the quality of a chart when exported to a pdf</span></span>
- <span data-ttu-id="9c296-1139">我們已修正工具提示無法顯示到達中心之距離的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1139">We fixed an issue which prevented a tooltip indicating the distance to center from displaying</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-1140">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-1140">Outlook</span></span>
- <span data-ttu-id="9c296-1141">我們已修正有時可能會導致 [磁碟已滿] 錯誤訊息無法顯示的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1141">We fixed an issue which could sometimes prevent a Disk Full error to be displayed</span></span>
- <span data-ttu-id="9c296-1142">我們已修正更新會議邀請時可能會導致附件重複的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1142">We fixed an issue which could cause attachments to become duplicated when updating a meeting request</span></span>

### <a name="access"></a><span data-ttu-id="9c296-1143">Access</span><span class="sxs-lookup"><span data-stu-id="9c296-1143">Access</span></span>
- <span data-ttu-id="9c296-1144">我們已修正某些查詢無法傳回大整數值的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1144">We fixed an issue which prevented some queries from returning large integer values</span></span>
- <span data-ttu-id="9c296-1145">我們已修正可能會引起 SQL 文字方塊無法編輯的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1145">We fixed an issue which could make the sql textbox uneditable</span></span>
- <span data-ttu-id="9c296-1146">我們已修正工具提示可能難以在某些高 DPI 顯示器上查看的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1146">We fixed an issue where tooltips could be difficult to see on some High DPI displays</span></span>

### <a name="project"></a><span data-ttu-id="9c296-1147">Project</span><span class="sxs-lookup"><span data-stu-id="9c296-1147">Project</span></span>
- <span data-ttu-id="9c296-1148">我們已修正在新工作中可能會導致旗標值無法編輯的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1148">We fixed an issue which could cause flag values to become uneditable in new tasks</span></span>
- <span data-ttu-id="9c296-1149">我們已修正可能導致狀態更新在 [工作分派] 和 [任務] 上不正確地設定 [實際開始日期] 的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1149">We fixed an issue which could cause a status update to improperly set Actual Start Date on Assignments and Tasks</span></span>
- <span data-ttu-id="9c296-1150">我們已修正可能會導致部分資源錯誤顯示為過度分派的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1150">We fixed an issue which could cause some resources to incorreclty appear overallocated</span></span>
- <span data-ttu-id="9c296-1151">我們已修正新增延隔時間、小數點分隔符號是逗號，以及連線至伺服器時，工作相依性新增方法可能會出錯的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1151">We fixed an issue where the TaskDependencies Add method could fail when Lag is added, the decimal separator is a comma, and when connected to a server</span></span>
- <span data-ttu-id="9c296-1152">我們已修正透過 CSOM 更新本機自訂欄位的查閱表格值可能會損毀 PCS 的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1152">We fixed an issue where updating local custom field lookup table values via CSOM could crash PCS</span></span>
- <span data-ttu-id="9c296-1153">我們已修正總工時值示內如果含有小數點時將不正確顯示的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1153">We fixed an issue where the total work values may appear incorrect if they contain a decimal</span></span>

</BR></BR>

## <a name="june-28-2019"></a><span data-ttu-id="9c296-1154">2019 年 6 月 28 日</span><span class="sxs-lookup"><span data-stu-id="9c296-1154">June 28, 2019</span></span>
<span data-ttu-id="9c296-1155">版本 1907 (組建 11819.20002)</span><span class="sxs-lookup"><span data-stu-id="9c296-1155">Version 1907 (build 11819.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9c296-1156">新功能：</span><span class="sxs-lookup"><span data-stu-id="9c296-1156">What's New:</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-1157">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-1157">Excel</span></span>

- <span data-ttu-id="9c296-1158">**使用 Power Query 的增強功能快速撰寫程式碼：** 使用自動完成和語法色彩快速完成程式碼。</span><span class="sxs-lookup"><span data-stu-id="9c296-1158">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="9c296-1159">同時輕鬆探索函數、資料行和參數</span><span class="sxs-lookup"><span data-stu-id="9c296-1159">Easily discover functions, columns, and parameters, too</span></span>

- <span data-ttu-id="9c296-1160">**聯結類似欄位上的表格：** 在比較合併表格的欄位時，取得及轉換 (Power Query) 現在具有近似文字比對邏輯 (也稱為模糊比對)。</span><span class="sxs-lookup"><span data-stu-id="9c296-1160">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span>

### <a name="word"></a><span data-ttu-id="9c296-1161">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-1161">Word</span></span>

- <span data-ttu-id="9c296-1162">**共同撰寫的增強功能**：增強共同撰寫時的可靠性。</span><span class="sxs-lookup"><span data-stu-id="9c296-1162">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>
 
### <a name="word-excel-powerpoint-and-visio"></a><span data-ttu-id="9c296-1163">Word、Excel、PowerPoint 和 Visio</span><span class="sxs-lookup"><span data-stu-id="9c296-1163">Word, Excel, PowerPoint, and Visio</span></span>

#### <a name="recommended-documents"></a><span data-ttu-id="9c296-1164">建譯的文件</span><span class="sxs-lookup"><span data-stu-id="9c296-1164">Recommended Documents</span></span>

<span data-ttu-id="9c296-1165">透過建議您的相關活動尋找文件。</span><span class="sxs-lookup"><span data-stu-id="9c296-1165">Find documents with relevant activity recommended to you.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9c296-1166">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="9c296-1166">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="9c296-1167">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-1167">Word</span></span> 
- <span data-ttu-id="9c296-1168">我們已修正可能會導致有些 .DOC 檔案無法開啟的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1168">We fixed an issue which could prevent some .DOC files from opening</span></span>
- <span data-ttu-id="9c296-1169">我們已修正可能會導致註解無法正確載入的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1169">We fixed an issue which could have prevented comments from loading properly</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-1170">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-1170">Excel</span></span>
- <span data-ttu-id="9c296-1171">我們已改善 Power Query 的效能</span><span class="sxs-lookup"><span data-stu-id="9c296-1171">We improved the performance of Power Queries</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-1172">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-1172">PowerPoint</span></span>
- <span data-ttu-id="9c296-1173">我們已修正在 Surface 裝置上使用手寫筆可能會導致螢幕閃爍的相關問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1173">We fixed an issue related to using a pen on a Surface device which could cause the screen to flicker</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-1174">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-1174">Outlook</span></span>
- <span data-ttu-id="9c296-1175">我們已修正將約會轉換成會議時可能會變更約會的空閒/忙碌狀態問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1175">We fixed an issue which could change the free/busy status of an appointment when converted to a meeting</span></span>
- <span data-ttu-id="9c296-1176">我們已修正電子郵件有臨時範本的保護時會顯示錯誤範本和描述的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1176">We fixed an issue where the wrong template and description would be displayed when an e-mail was protected with an ad-hoc template</span></span>

### <a name="access"></a><span data-ttu-id="9c296-1177">Access</span><span class="sxs-lookup"><span data-stu-id="9c296-1177">Access</span></span>
- <span data-ttu-id="9c296-1178">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1178">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9c296-1179">Project</span><span class="sxs-lookup"><span data-stu-id="9c296-1179">Project</span></span>
- <span data-ttu-id="9c296-1180">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1180">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-21-2019"></a><span data-ttu-id="9c296-1181">2019 年 6 月 21 日</span><span class="sxs-lookup"><span data-stu-id="9c296-1181">June 21, 2019</span></span>
<span data-ttu-id="9c296-1182">版本 1907 (組建 11815.20002)</span><span class="sxs-lookup"><span data-stu-id="9c296-1182">Version 1907 (build 11815.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9c296-1183">新功能：</span><span class="sxs-lookup"><span data-stu-id="9c296-1183">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-1184">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-1184">Outlook</span></span>

#### <a name="dark-mode-for-black-theme-in-outlook-desktop"></a><span data-ttu-id="9c296-1185">Outlook 電腦版中用於黑色佈景主題的深色模式</span><span class="sxs-lookup"><span data-stu-id="9c296-1185">Dark Mode for Black Theme in Outlook Desktop</span></span>

<span data-ttu-id="9c296-1186">使用深色模式時，黑色佈景主題中的使用者現在也會在讀取電子郵件時看到讀取窗格具有深色背景，並在撰寫電子郵件時擁有深色背景的撰寫體驗。</span><span class="sxs-lookup"><span data-stu-id="9c296-1186">With dark mode, users in black theme will now also see the reading pane with a dark background when reading emails, and the compose experience with a dark background when writing emails.</span></span> <span data-ttu-id="9c296-1187">如果使用者想要預覽郵件在淺色背景下的外觀，在讀取窗格或功能區中有太陽/月亮切換。</span><span class="sxs-lookup"><span data-stu-id="9c296-1187">There is a sun/moon toggle on the reading pane and in the ribbon in case users want to preview what the message looks like with a light background instead.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="9c296-1188">開始使用：</span><span class="sxs-lookup"><span data-stu-id="9c296-1188">Getting Started:</span></span>

1. <span data-ttu-id="9c296-1189">開啟黑色佈景主題，深色模式預設就會處於開啟狀態。</span><span class="sxs-lookup"><span data-stu-id="9c296-1189">Turn on black theme and dark mode will be on by default.</span></span>
2. <span data-ttu-id="9c296-1190">使用月亮/太陽切換 (在讀取窗格和功能區中) 可為不在深色模式的使用者預覽郵件的外觀</span><span class="sxs-lookup"><span data-stu-id="9c296-1190">Use the moon/sun toggle (in the reading pane and in the ribbon) to preview what the message looks like for users not in dark mode</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="9c296-1191">可嘗試使用的案例</span><span class="sxs-lookup"><span data-stu-id="9c296-1191">Scenarios to Try</span></span>

1. <span data-ttu-id="9c296-1192">在深色模式中讀取電子郵件。</span><span class="sxs-lookup"><span data-stu-id="9c296-1192">Read emails in dark mode.</span></span> <span data-ttu-id="9c296-1193">如果您無法讀取某些項目，請使用讀取窗格中的太陽切換來切換為淺色背景。</span><span class="sxs-lookup"><span data-stu-id="9c296-1193">If you are unable to read something, use the sun toggle in the Reading Pane to switch to a light background.</span></span> 
2. <span data-ttu-id="9c296-1194">在深色模式中撰寫電子郵件。</span><span class="sxs-lookup"><span data-stu-id="9c296-1194">Compose emails in dark mode.</span></span> <span data-ttu-id="9c296-1195">使用功能區中的太陽切換，預覽您的郵件使用淺色背景時的外觀。</span><span class="sxs-lookup"><span data-stu-id="9c296-1195">Preview what your message will look like with a light background by using the sun toggle in the ribbon.</span></span> 

<span data-ttu-id="9c296-1196">如果您遇到未正確顯示的任何電子郵件，請將其 (當作附件) 傳送到 OutlookDarkModeFail@service.microsoft.com</span><span class="sxs-lookup"><span data-stu-id="9c296-1196">If you encounter any emails that don't render properly, please send them (as an attachment) to OutlookDarkModeFail@service.microsoft.com</span></span>

#### <a name="get-location-suggestions"></a><span data-ttu-id="9c296-1197">取得位置建議</span><span class="sxs-lookup"><span data-stu-id="9c296-1197">Get location suggestions</span></span>

<span data-ttu-id="9c296-1198">開始輸入，Outlook 就會尋找符合的位置。</span><span class="sxs-lookup"><span data-stu-id="9c296-1198">Start typing and Outlook will look for matching locations.</span></span>

<span data-ttu-id="9c296-1199">建立約會和會議時，這適用於 [位置] 欄位。</span><span class="sxs-lookup"><span data-stu-id="9c296-1199">This applies to the Location field when creating Appointments and Meetings.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="9c296-1200">開始使用：</span><span class="sxs-lookup"><span data-stu-id="9c296-1200">Getting Started:</span></span>

- <span data-ttu-id="9c296-1201">在 Outlook 中的 O365 或 Outlook.com 行事曆上，建立約會或會議。</span><span class="sxs-lookup"><span data-stu-id="9c296-1201">Create an Appointment or Meeting on an O365 or Outlook.com calendar in Outlook.</span></span> 
- <span data-ttu-id="9c296-1202">按一下 [位置] 欄位，然後開始輸入…</span><span class="sxs-lookup"><span data-stu-id="9c296-1202">Click into the Location field and start typing…</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="9c296-1203">可嘗試使用的案例</span><span class="sxs-lookup"><span data-stu-id="9c296-1203">Scenarios to Try</span></span>

<span data-ttu-id="9c296-1204">當您將會議室加入至會議時，按一下 [位置] 欄位，而不是使用會議室尋找工具增益集或通訊錄。</span><span class="sxs-lookup"><span data-stu-id="9c296-1204">When adding a conference room to a meeting, click into Location field, rather than using Room Finder add-in or Address Book.</span></span>
<span data-ttu-id="9c296-1205">若是在公共場所 (如餐廳、咖啡廳，甚至是牙醫診所) 的實體位置進行會議，請嘗試使用新的選擇器找到確切的位置。</span><span class="sxs-lookup"><span data-stu-id="9c296-1205">For appointments at a physical place with a public location - like a restaurant, coffee shop, or even your dentist's office - try finding the exact location using the new picker.</span></span> <span data-ttu-id="9c296-1206">如此一來，您將可以在該離開時，收到 Outlook Mobile 的通知。</span><span class="sxs-lookup"><span data-stu-id="9c296-1206">This way, you'll be able to get notified on Outlook Mobile when it's time to leave.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9c296-1207">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="9c296-1207">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="9c296-1208">全部</span><span class="sxs-lookup"><span data-stu-id="9c296-1208">All</span></span>
- <span data-ttu-id="9c296-1209">我們已修正在離線時會導致搜尋方塊啟用的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1209">We fixed an issue which would keep the Search Box enabled while offline</span></span>

### <a name="word"></a><span data-ttu-id="9c296-1210">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-1210">Word</span></span> 
- <span data-ttu-id="9c296-1211">我們已修正有時候可能難以查看鍵盤焦點的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1211">We fixed an issue where keyboard focus could sometimes be difficult to see</span></span>
- <span data-ttu-id="9c296-1212">我們已修正貼到新文件的文字，有時候文字對齊可能會不正確的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1212">We fixed an issue where text pasted into a new document could sometimes have the wrong text alignment</span></span>
- <span data-ttu-id="9c296-1213">我們已修正將使用者的電腦暫停之後，可能防止部分使用者儲存變更的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1213">We fixed an issue which could prevent some users from saving changes after suspending their computer</span></span>
- <span data-ttu-id="9c296-1214">我們已修正在某些情況下會列印整份文件，而非所選範圍的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1214">We fixed an issue where in certain cases an entire document would be printed instead of the selected range</span></span>
- <span data-ttu-id="9c296-1215">我們已修正可能會讓註解在較小型的顯示器上難以閱讀的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1215">We fixed an issue which could make comments difficult to read on smaller displays</span></span>
- <span data-ttu-id="9c296-1216">我們已修正擷取到裝置時可能會造成當機的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1216">We fixed an issue which could cause a crash when capturing to a device</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-1217">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-1217">Excel</span></span>
- <span data-ttu-id="9c296-1218">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1218">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-1219">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-1219">PowerPoint</span></span>
- <span data-ttu-id="9c296-1220">我們已修正有時候可能難以查看鍵盤焦點的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1220">We fixed an issue where keyboard focus could sometimes be difficult to see</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-1221">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-1221">Outlook</span></span>
- <span data-ttu-id="9c296-1222">我們已修正不正確地將未啟用的增益集顯示為已啟用的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-1222">We fixed an issue which could incorrectly display an add-in as being enabled when it was not.</span></span>
- <span data-ttu-id="9c296-1223">我們已修正會在有大量原則時，使得客戶無法檢視所有保留原則的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1223">We fixed an issue which would prevent a customer from viewing all retention policies if there were a large number of them</span></span>

### <a name="access"></a><span data-ttu-id="9c296-1224">Access</span><span class="sxs-lookup"><span data-stu-id="9c296-1224">Access</span></span>
- <span data-ttu-id="9c296-1225">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1225">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9c296-1226">Project</span><span class="sxs-lookup"><span data-stu-id="9c296-1226">Project</span></span>
- <span data-ttu-id="9c296-1227">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1227">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-14-2019"></a><span data-ttu-id="9c296-1228">2019 年 6 月 14 日</span><span class="sxs-lookup"><span data-stu-id="9c296-1228">June 14, 2019</span></span>
<span data-ttu-id="9c296-1229">版本 1907 (組建 11807.20000)</span><span class="sxs-lookup"><span data-stu-id="9c296-1229">Version 1907 (build 11807.20000)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9c296-1230">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="9c296-1230">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="9c296-1231">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-1231">Word</span></span> 
- <span data-ttu-id="9c296-1232">我們已修正了儲存到 OneDrive 時，使用者可能無法登入的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1232">We fixed an issue which could prevent a user from signing in when saving to OneDrive</span></span>
- <span data-ttu-id="9c296-1233">我們已修正了使用者可能無法變更限制存取模式中之 SharePoint 內容的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1233">We fixed an issue where a user could be prevented from changing SharePoint properties while in restricted access mode</span></span>
- <span data-ttu-id="9c296-1234">我們已修正了調整邊界時，可能會變更頁首及頁尾內容的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1234">We fixed an issue where header and footer content could change when adjusting margins</span></span>
- <span data-ttu-id="9c296-1235">我們已修正了切換成網頁檢視時，格式設定可能會中斷的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1235">We fixed an issue where formatting could break when switching to web view</span></span>
- <span data-ttu-id="9c296-1236">我們已修正了從 SharePoint 開啟時，使用者無法使用自訂欄位的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1236">We fixed an issue which could prevent a user from using custom fields when opened from SharePoint</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-1237">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-1237">Excel</span></span>
- <span data-ttu-id="9c296-1238">我們已修正了刪除篩選集之資料列時的效能問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1238">We fixed a performance issue when deleting rows of a filtered set</span></span>
- <span data-ttu-id="9c296-1239">我們已修正了有時可能會造成滑鼠在受保護檢視模式中閃爍的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1239">We fixed an issue which could sometimes cause the mouse to flicker in protected view</span></span>
- <span data-ttu-id="9c296-1240">我們修正了刪除系列時，可能會導致當機的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1240">We fixed an issue which could have caused a crash when deleting a series</span></span>
- <span data-ttu-id="9c296-1241">我們已修正了某些使用者即使在沒有提供的情況下，仍舊有新增版本歷程記錄之選項的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1241">We fixed an issue where some users would have the option to add version history when that was not available</span></span>
- <span data-ttu-id="9c296-1242">我們已修正了使用試算表比較工具時，可能導致例外狀況的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1242">We fixed an issue which could have caused an exception when using the Spreadsheet Compare tool</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-1243">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-1243">PowerPoint</span></span>
- <span data-ttu-id="9c296-1244">我們已修正了按一下連結到 SharePoint 時，可能會發生當機的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1244">We fixed an issue where a crash could occur when clicking a link to SharePoint</span></span>
- <span data-ttu-id="9c296-1245">我們已修正了使用 Surface 手寫筆輸入時，可能將使用者切換到下一個頁面的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1245">We fixed an issue which could switch the user to the next page while typing using a Surface Pen</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-1246">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-1246">Outlook</span></span>
- <span data-ttu-id="9c296-1247">我們已修正了在某些情況下 [收件者] 欄位大於正常的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1247">We fixed an issue where in some cases the To field was larger than normal</span></span>

### <a name="access"></a><span data-ttu-id="9c296-1248">Access</span><span class="sxs-lookup"><span data-stu-id="9c296-1248">Access</span></span>
- <span data-ttu-id="9c296-1249">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1249">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9c296-1250">Project</span><span class="sxs-lookup"><span data-stu-id="9c296-1250">Project</span></span>
- <span data-ttu-id="9c296-1251">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1251">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-7-2019"></a><span data-ttu-id="9c296-1252">2019 年 6 月 7 日</span><span class="sxs-lookup"><span data-stu-id="9c296-1252">June 7, 2019</span></span>
<span data-ttu-id="9c296-1253">版本 1907 (組建 11727.20064)</span><span class="sxs-lookup"><span data-stu-id="9c296-1253">Version 1907 (build 11727.20064)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9c296-1254">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="9c296-1254">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="9c296-1255">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-1255">Word</span></span> 
- <span data-ttu-id="9c296-1256">我們已修正當 Word 中的自動校正設定為使句中的第一個字母均為大寫時，偶爾會當機的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1256">We fixed an issue where Word could sometimes crash when autocorrect was set to capitalize the first letter of a sentence</span></span>
- <span data-ttu-id="9c296-1257">我們已改善在 SharePoint 上編輯文件時的效能。</span><span class="sxs-lookup"><span data-stu-id="9c296-1257">We improved performance when editing a document on SharePoint</span></span>
- <span data-ttu-id="9c296-1258">我們已修正在 Adobe Illustrator 中所建立之向量影像無法正確顯示的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1258">We fixed an issue where vector-based images created in Adobe Illustrator would not display correctly</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-1259">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-1259">Excel</span></span>
- <span data-ttu-id="9c296-1260">我們已修正錄製巨集時，排序欄位有時未正確設定的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1260">We fixed an issue where sorting fields were sometimes not set correctly when recording a macro</span></span>
- <span data-ttu-id="9c296-1261">我們已修正重新計算陣列公式期間導致停止回應或當機的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1261">We fixed an issue that causes hang or crash during recalculation of an array formula</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-1262">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-1262">PowerPoint</span></span>
- <span data-ttu-id="9c296-1263">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1263">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-1264">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-1264">Outlook</span></span>
- <span data-ttu-id="9c296-1265">我們已修正內嵌附件有時未正確縮放的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1265">We fixed an issue where inline attachments would sometimes be incorrectly scaled</span></span>

### <a name="access"></a><span data-ttu-id="9c296-1266">Access</span><span class="sxs-lookup"><span data-stu-id="9c296-1266">Access</span></span>
- <span data-ttu-id="9c296-1267">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1267">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9c296-1268">Project</span><span class="sxs-lookup"><span data-stu-id="9c296-1268">Project</span></span>
- <span data-ttu-id="9c296-1269">我們已修正固定工期的時程表有時會變更工作分派完成日期的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1269">We fixed an issue where timesheets on a fixed duration could sometimes change the assignment finish date</span></span>
- <span data-ttu-id="9c296-1270">我們已修正從舊版本中開啟專案時顯示的完成百分比值可能有誤的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1270">We fixed an issue where Percentage Complete values could be wrong when opening a project from an earlier version</span></span>

</BR></BR>

## <a name="may-31-2019"></a><span data-ttu-id="9c296-1271">2019 年 5 月 31 日</span><span class="sxs-lookup"><span data-stu-id="9c296-1271">May 31, 2019</span></span>
<span data-ttu-id="9c296-1272">版本 1906 (組建 11722.20008)</span><span class="sxs-lookup"><span data-stu-id="9c296-1272">Version 1906 (build 11722.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9c296-1273">新功能：</span><span class="sxs-lookup"><span data-stu-id="9c296-1273">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-1274">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-1274">Outlook</span></span>

#### <a name="dialog-for-contacting-support-now-is-dockable-and-appears-on-the-right"></a><span data-ttu-id="9c296-1275">[連絡支援人員] 對話方塊現在可停駐，且會顯示在右側</span><span class="sxs-lookup"><span data-stu-id="9c296-1275">Dialog for Contacting Support now is dockable and appears on the right</span></span>

<span data-ttu-id="9c296-1276">用於 [連絡支援人員] 的對話方塊現在會顯示在右側窗格中，並且會以停駐視窗形式開始。</span><span class="sxs-lookup"><span data-stu-id="9c296-1276">The dialog used for Contacting support will now appear in a pane on the right and will start off as a docked window.</span></span>

#### <a name="ink-in-your-email"></a><span data-ttu-id="9c296-1277">在您的電子郵件中使用筆跡！</span><span class="sxs-lookup"><span data-stu-id="9c296-1277">Ink in Your Email!</span></span>

<span data-ttu-id="9c296-1278">您現在可以在您的 Outlook 電子郵件中繪製圖片並加上註釋。</span><span class="sxs-lookup"><span data-stu-id="9c296-1278">You can now draw and annotate pictures in your Outlook emails.</span></span>

### <a name="word"></a><span data-ttu-id="9c296-1279">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-1279">Word</span></span>

#### <a name="open-document-links-in-word"></a><span data-ttu-id="9c296-1280">在 Word 中開啟文件連結</span><span class="sxs-lookup"><span data-stu-id="9c296-1280">Open document links in Word</span></span>

<span data-ttu-id="9c296-1281">當您在 Office 中按一下文件連結時，您可以更新您的喜好設定，以預設在 Word App 中開啟該連結。</span><span class="sxs-lookup"><span data-stu-id="9c296-1281">When you click a document link in Office, you can update your preference to open in the Word app by default.</span></span>  <span data-ttu-id="9c296-1282">若要更新您的喜好設定，請移至 [檔案] -> [選項] -> [進階] -> [連結處理]。</span><span class="sxs-lookup"><span data-stu-id="9c296-1282">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="9c296-1283">深入了解：https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="9c296-1283">Learn more: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="9c296-1284">開始使用：</span><span class="sxs-lookup"><span data-stu-id="9c296-1284">Getting Started:</span></span>

<span data-ttu-id="9c296-1285">此功能將預設為關閉。</span><span class="sxs-lookup"><span data-stu-id="9c296-1285">Feature will default to off.</span></span> <span data-ttu-id="9c296-1286">使用者可以透過 [選項] -> [進階] -> [連結處理] 設定來開啟它，也可以在 Win32 WXP 應用程式帶他們進行選擇加入體驗時選擇加入。</span><span class="sxs-lookup"><span data-stu-id="9c296-1286">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="9c296-1287">當使用者按一下透過 Outlook/Word/PowerPoint/Excel 儲存在 OneDrive/商務用 OneDrive/SharePoint 上的 Word/PowerPoint/Excel 檔案時，這些連結依預設會在適當的 Office 應用程式中 (而非瀏覽器中) 開啟。</span><span class="sxs-lookup"><span data-stu-id="9c296-1287">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="9c296-1288">若要變更此預設值，使用者可以更新 Outlook/Word/Excel/PowerPoint 中的下列設定：</span><span class="sxs-lookup"><span data-stu-id="9c296-1288">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="9c296-1289">[檔案] -> [選項] -> [進階] -> [連結處理]</span><span class="sxs-lookup"><span data-stu-id="9c296-1289">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="9c296-1290">此設定會在 Outlook/Word/PowerPoint/Excel 之間共用，而且可以在任一應用程式中設定。</span><span class="sxs-lookup"><span data-stu-id="9c296-1290">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="9c296-1291">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="9c296-1291">Scenarios to Try:</span></span>

<span data-ttu-id="9c296-1292">若要觸發選擇加入體驗 - 從 Outlook/Word/PowerPoint/Excel 開啟儲存在 OneDrive/SharePoint 中 Word 文件的連結 - 按一下 [在來自 Office Online 的用戶端中開啟] - 在 30 天內執行此動作兩次。</span><span class="sxs-lookup"><span data-stu-id="9c296-1292">To trigger the opt-in experience - Open a link tot a Word document stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="9c296-1293">在您選擇加入之後，依預設會在 Win32 應用程式中啟動連結。</span><span class="sxs-lookup"><span data-stu-id="9c296-1293">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-1294">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-1294">PowerPoint</span></span>

#### <a name="open-presentation-links-in-powerpoint"></a><span data-ttu-id="9c296-1295">在 PowerPoint 中開啟簡報連結</span><span class="sxs-lookup"><span data-stu-id="9c296-1295">Open presentation links in PowerPoint</span></span>

<span data-ttu-id="9c296-1296">當您在 Office 中按一下連結連結時，您可以更新您的喜好設定，以預設在 PowerPoint App 中開啟該連結。</span><span class="sxs-lookup"><span data-stu-id="9c296-1296">When you click a presentation link in Office, you can update your preference to open in the PowerPoint app by default.</span></span> <span data-ttu-id="9c296-1297">若要更新您的喜好設定，請移至 [檔案] -> [選項] -> [進階] -> [連結處理]。</span><span class="sxs-lookup"><span data-stu-id="9c296-1297">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="9c296-1298">深入了解：https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="9c296-1298">Learn more: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="9c296-1299">開始使用：</span><span class="sxs-lookup"><span data-stu-id="9c296-1299">Getting Started:</span></span>

<span data-ttu-id="9c296-1300">此功能將預設為關閉。</span><span class="sxs-lookup"><span data-stu-id="9c296-1300">Feature will default to off.</span></span> <span data-ttu-id="9c296-1301">使用者可以透過 [選項] -> [進階] -> [連結處理] 設定來開啟它，也可以在 Win32 WXP 應用程式帶他們進行選擇加入體驗時選擇加入。</span><span class="sxs-lookup"><span data-stu-id="9c296-1301">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="9c296-1302">當使用者按一下透過 Outlook/Word/PowerPoint/Excel 儲存在 OneDrive/商務用 OneDrive/SharePoint 上的 Word/PowerPoint/Excel 檔案時，這些連結依預設會在適當的 Office 應用程式中 (而非瀏覽器中) 開啟。</span><span class="sxs-lookup"><span data-stu-id="9c296-1302">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="9c296-1303">若要變更此預設值，使用者可以更新 Outlook/Word/Excel/PowerPoint 中的下列設定：</span><span class="sxs-lookup"><span data-stu-id="9c296-1303">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="9c296-1304">[檔案] -> [選項] -> [進階] -> [連結處理]</span><span class="sxs-lookup"><span data-stu-id="9c296-1304">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="9c296-1305">此設定會在 Outlook/Word/PowerPoint/Excel 之間共用，而且可以在任一應用程式中設定。</span><span class="sxs-lookup"><span data-stu-id="9c296-1305">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="9c296-1306">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="9c296-1306">Scenarios to Try:</span></span>

<span data-ttu-id="9c296-1307">若要觸發選擇加入體驗 - 從 Outlook/Word/PowerPoint/Excel 開啟儲存在 OneDrive/SharePoint 中 PowerPoint 簡報的連結 - 按一下 [在來自 Office Online 的用戶端中開啟] - 在 30 天內執行此動作兩次。</span><span class="sxs-lookup"><span data-stu-id="9c296-1307">To trigger the opt-in experience - Open a link to a PowerPoint presentation stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="9c296-1308">在您選擇加入之後，依預設會在 Win32 應用程式中啟動連結。</span><span class="sxs-lookup"><span data-stu-id="9c296-1308">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-1309">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-1309">Excel</span></span>

#### <a name="open-workbook-links-in-excel"></a><span data-ttu-id="9c296-1310">在 Excel 中開啟活頁簿連結</span><span class="sxs-lookup"><span data-stu-id="9c296-1310">Open workbook links in Excel</span></span>

<span data-ttu-id="9c296-1311">當您在 Office 中按一下活頁簿連結時，您可以更新您的喜好設定，以預設在 Excel App 中開啟該連結。</span><span class="sxs-lookup"><span data-stu-id="9c296-1311">When you click a workbook link in Office, you can update your preference to open in the Excel app by default.</span></span> <span data-ttu-id="9c296-1312">若要更新您的喜好設定，請移至 [檔案] -> [選項] -> [進階] -> [連結處理]。</span><span class="sxs-lookup"><span data-stu-id="9c296-1312">To update your preference, go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="9c296-1313">深入了解：https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="9c296-1313">Learn More: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="9c296-1314">開始使用：</span><span class="sxs-lookup"><span data-stu-id="9c296-1314">Getting Started:</span></span>

<span data-ttu-id="9c296-1315">此功能將預設為關閉。</span><span class="sxs-lookup"><span data-stu-id="9c296-1315">Feature will default to off.</span></span> <span data-ttu-id="9c296-1316">使用者可以透過 [選項] -> [進階] -> [連結處理] 設定來開啟它，也可以在 Win32 WXP 應用程式帶他們進行選擇加入體驗時選擇加入。</span><span class="sxs-lookup"><span data-stu-id="9c296-1316">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="9c296-1317">當使用者按一下透過 Outlook/Word/PowerPoint/Excel 儲存在 OneDrive/商務用 OneDrive/SharePoint 上的 Word/PowerPoint/Excel 檔案時，這些連結依預設會在適當的 Office 應用程式中 (而非瀏覽器中) 開啟。</span><span class="sxs-lookup"><span data-stu-id="9c296-1317">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="9c296-1318">若要變更此預設值，使用者可以更新 Outlook/Word/Excel/PowerPoint 中的下列設定：</span><span class="sxs-lookup"><span data-stu-id="9c296-1318">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="9c296-1319">[檔案] -> [選項] -> [進階] -> [連結處理]</span><span class="sxs-lookup"><span data-stu-id="9c296-1319">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="9c296-1320">此設定會在 Outlook/Word/PowerPoint/Excel 之間共用，而且可以在任一應用程式中設定。</span><span class="sxs-lookup"><span data-stu-id="9c296-1320">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="9c296-1321">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="9c296-1321">Scenarios to Try:</span></span>

<span data-ttu-id="9c296-1322">若要觸發選擇加入體驗 - 從 Outlook/Word/PowerPoint/Excel 開啟儲存在 OneDrive/SharePoint 中 Excel 活頁簿的連結 - 按一下 [在來自 Office Online 的用戶端中開啟] - 在 30 天內執行此動作兩次。</span><span class="sxs-lookup"><span data-stu-id="9c296-1322">To trigger the opt-in experience - Open a link to an Excel workbook stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="9c296-1323">在您選擇加入之後，依預設會在 Win32 應用程式中啟動連結。</span><span class="sxs-lookup"><span data-stu-id="9c296-1323">After you opt-in, links will launch in the Win32 apps by default.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9c296-1324">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="9c296-1324">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="9c296-1325">全部</span><span class="sxs-lookup"><span data-stu-id="9c296-1325">All</span></span>
- <span data-ttu-id="9c296-1326">我們已修正即使在已停用自動儲存的情況下，檔案有時會自動儲存的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1326">We fixed an issue where files could sometimes be auto-saved even when auto-save was disabled</span></span>

### <a name="word"></a><span data-ttu-id="9c296-1327">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-1327">Word</span></span> 
- <span data-ttu-id="9c296-1328">我們已修正可能會導致部分使用者無法儲存至 SharePoint 的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1328">We fixed an issue which may have prevented some users from saving to SharePoint</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-1329">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-1329">Excel</span></span>
- <span data-ttu-id="9c296-1330">我們已修正可能對非作用中篩選器顯示不正確圖示的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-1330">We fixed an issue where an incorrect icon could be displayed for inactive filters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-1331">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-1331">PowerPoint</span></span>
- <span data-ttu-id="9c296-1332">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1332">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-1333">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-1333">Outlook</span></span>
- <span data-ttu-id="9c296-1334">我們已修正有些使用者在群組排程檢視中會不正確地顯示為離線的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1334">We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span>
- <span data-ttu-id="9c296-1335">我們已修正可能會防止 SafeLink 剖析包含尾端空格 URL 的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1335">We fixed an issue which prevented SafeLink from parsing a URL with a trailing space</span></span>
- <span data-ttu-id="9c296-1336">我們已修正會議室在非工作時間外顯示為可用的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1336">We fixed an issue where rooms were displayed as available outside of non-working hours</span></span>

### <a name="access"></a><span data-ttu-id="9c296-1337">Access</span><span class="sxs-lookup"><span data-stu-id="9c296-1337">Access</span></span>
- <span data-ttu-id="9c296-1338">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1338">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9c296-1339">Project</span><span class="sxs-lookup"><span data-stu-id="9c296-1339">Project</span></span>
- <span data-ttu-id="9c296-1340">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1340">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-24-2019"></a><span data-ttu-id="9c296-1341">2019 年 5 月 24 日</span><span class="sxs-lookup"><span data-stu-id="9c296-1341">May 24, 2019</span></span>
<span data-ttu-id="9c296-1342">版本 1906 (組建 11715.20002)</span><span class="sxs-lookup"><span data-stu-id="9c296-1342">Version 1906 (build 11715.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9c296-1343">新功能：</span><span class="sxs-lookup"><span data-stu-id="9c296-1343">What's New:</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="9c296-1344">使用者體驗更新</span><span class="sxs-lookup"><span data-stu-id="9c296-1344">User Experience Updates</span></span>

<span data-ttu-id="9c296-1345">[即將推出] 中的更新現已發佈，其中包括簡化功能區、資料夾窗格的新版視覺效果、郵件清單，以及讀取窗格。</span><span class="sxs-lookup"><span data-stu-id="9c296-1345">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9c296-1346">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="9c296-1346">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="9c296-1347">全部</span><span class="sxs-lookup"><span data-stu-id="9c296-1347">All</span></span>

- <span data-ttu-id="9c296-1348">我們已修正 [聊天] 窗格無法顯示的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1348">We fixed an issue where the Chat Pane would not display</span></span>

### <a name="word"></a><span data-ttu-id="9c296-1349">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-1349">Word</span></span> 
- <span data-ttu-id="9c296-1350">我們已修正在某些情況下 Word 無法為文法錯誤正確醒目提示文字的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1350">We fixed an issue where in some cases Word could incorrectly highlight text for grammatical errors</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-1351">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-1351">Excel</span></span>
- <span data-ttu-id="9c296-1352">我們已修正 [圖表項目] 使用不正確圖示的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1352">We fixed an issue where an incorrect icon was used in for Chart Elements</span></span>
- <span data-ttu-id="9c296-1353">我們已修正開啟同樣的活頁簿時，可能會啟動 VBA 指令碼中不正確活頁簿的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1353">We fixed an issue where the incorrect workbook could be activated in a VBA script when the same book was already open</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-1354">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-1354">PowerPoint</span></span>
- <span data-ttu-id="9c296-1355">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1355">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-1356">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-1356">Outlook</span></span>
- <span data-ttu-id="9c296-1357">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1357">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="9c296-1358">Access</span><span class="sxs-lookup"><span data-stu-id="9c296-1358">Access</span></span>
- <span data-ttu-id="9c296-1359">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1359">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9c296-1360">Project</span><span class="sxs-lookup"><span data-stu-id="9c296-1360">Project</span></span>
- <span data-ttu-id="9c296-1361">我們已修正 Project 在切換工作列後可能會當機的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1361">We fixed an issue where Project could crash after switching to the taskbar</span></span>

</BR></BR>

## <a name="may-17-2019"></a><span data-ttu-id="9c296-1362">2019 年 5 月 17 日</span><span class="sxs-lookup"><span data-stu-id="9c296-1362">May 17, 2019</span></span>
<span data-ttu-id="9c296-1363">版本 1906 (組建 11708.20006)</span><span class="sxs-lookup"><span data-stu-id="9c296-1363">Version 1906 (build 11708.20006)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9c296-1364">新功能：</span><span class="sxs-lookup"><span data-stu-id="9c296-1364">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-1365">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-1365">Outlook</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="9c296-1366">使用者體驗更新</span><span class="sxs-lookup"><span data-stu-id="9c296-1366">User Experience Updates</span></span>

<span data-ttu-id="9c296-1367">[即將推出] 中的更新現已發佈，其中包括簡化功能區、資料夾窗格的新版視覺效果、郵件清單，以及讀取窗格。</span><span class="sxs-lookup"><span data-stu-id="9c296-1367">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="9c296-1368">開始使用：</span><span class="sxs-lookup"><span data-stu-id="9c296-1368">Getting Started:</span></span>

<span data-ttu-id="9c296-1369">這些變更會成為新的預設 UI。自 12 月中旬起，即可透過 [即將推出] 開關切換使用這套 UI，協助您徹底發揮生產力</span><span class="sxs-lookup"><span data-stu-id="9c296-1369">These change will be part of the new default UI; it has been available behind the Coming Soon switch since mid Dec for 100% prod</span></span>

#### <a name="customizable-simplified-ribbon"></a><span data-ttu-id="9c296-1370">自訂簡化功能區</span><span class="sxs-lookup"><span data-stu-id="9c296-1370">Customizable Simplified Ribbon</span></span>

<span data-ttu-id="9c296-1371">提供輕鬆自訂功能，方便在傳統與 [簡化] 檢視之間切換，以及釘選/取消釘選命令。</span><span class="sxs-lookup"><span data-stu-id="9c296-1371">Easily customizable to switch between classic and Simplified views and pin/unpin commands.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="9c296-1372">開始使用：</span><span class="sxs-lookup"><span data-stu-id="9c296-1372">Getting Started:</span></span>

<span data-ttu-id="9c296-1373">使用者可以使用簡化功能區，方法是開啟 [即將推出] (在一開始)，然後按一下功能區中的＞形箭號，即可在傳統的多行功能區與新式的簡化單行功能區之間切換。</span><span class="sxs-lookup"><span data-stu-id="9c296-1373">Users can get to the simplified ribbon by turning on Coming Soon (initially) and clicking the chevron in the ribbon to toggle between the classic multi-line ribbon and the new simplified single-line ribbon.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="9c296-1374">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="9c296-1374">Scenarios to Try:</span></span>

<span data-ttu-id="9c296-1375">從傳統功能區切換到簡化功能區</span><span class="sxs-lookup"><span data-stu-id="9c296-1375">Switch from Classic ribbon to Simplified ribbon</span></span>

#### <a name="pick-your-favorite-action"></a><span data-ttu-id="9c296-1376">挑選您的最愛動作</span><span class="sxs-lookup"><span data-stu-id="9c296-1376">Pick your favorite action</span></span>

<span data-ttu-id="9c296-1377">不使用 [標幟] 和 [刪除] 嗎？</span><span class="sxs-lookup"><span data-stu-id="9c296-1377">Don't use Flag and Delete?</span></span> <span data-ttu-id="9c296-1378">那麼 [封存] 或 [標示為已讀取] 呢？</span><span class="sxs-lookup"><span data-stu-id="9c296-1378">How about Archive or Mark as Read?</span></span> <span data-ttu-id="9c296-1379">自訂快速動作功能表，加上您最常使用的命令。</span><span class="sxs-lookup"><span data-stu-id="9c296-1379">Customize the quick action menu with the commands you use most.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="9c296-1380">開始使用：</span><span class="sxs-lookup"><span data-stu-id="9c296-1380">Getting Started:</span></span>

<span data-ttu-id="9c296-1381">若要選取 [快速動作]，請以滑鼠右鍵按一下郵件清單中的 [電子郵件]，以顯示內容功能表。</span><span class="sxs-lookup"><span data-stu-id="9c296-1381">To select your Quick Actions, right click on an email in the message list to bring up the Context Menu.</span></span> <span data-ttu-id="9c296-1382">然後按一下 [設定快速動作...]</span><span class="sxs-lookup"><span data-stu-id="9c296-1382">Then click "Set Quick Actions..."</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="9c296-1383">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="9c296-1383">Scenarios to Try:</span></span>

<span data-ttu-id="9c296-1384">將 [標幟] 和 [刪除] 的預設值變更為 [封存]、[移動]、[標示為已讀取] 或 [無]，以便清除郵件清單</span><span class="sxs-lookup"><span data-stu-id="9c296-1384">Change the defaults from flag and delete to either archive, move,  mark as read, or none for a cleaner message list</span></span>

#### <a name="relaxed-or-tighter-layout-you-choose"></a><span data-ttu-id="9c296-1385">寬鬆或緊密的版面配置？</span><span class="sxs-lookup"><span data-stu-id="9c296-1385">Relaxed or tighter layout?</span></span> <span data-ttu-id="9c296-1386">由您選擇</span><span class="sxs-lookup"><span data-stu-id="9c296-1386">You choose</span></span>

<span data-ttu-id="9c296-1387">若您想讓郵件之間能有更多空間，可以採用「緊密間距」；或者，您也可以採用緊密的版面配置，以便查看更多郵件。</span><span class="sxs-lookup"><span data-stu-id="9c296-1387">Use Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="9c296-1388">開始使用：</span><span class="sxs-lookup"><span data-stu-id="9c296-1388">Getting Started:</span></span>

<span data-ttu-id="9c296-1389">前往 [檢視] 索引標籤，勾選 [更緊密的間距] 核取方塊。若是使用傳統功能區，該核取方塊位於「郵件」群組內；若是使用簡化功能區，則是位於「目前檢視」設定當中</span><span class="sxs-lookup"><span data-stu-id="9c296-1389">View tab, use tighter spacing checkbox - in Messages group for classic ribbon, Current View settings for simplified ribbon</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="9c296-1390">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="9c296-1390">Scenarios to Try:</span></span>

<span data-ttu-id="9c296-1391">使用 Outlook 在未啟用設定的情況下分類及撰寫電子郵件。</span><span class="sxs-lookup"><span data-stu-id="9c296-1391">Use Outlook to triage and write email with and without the setting enabled.</span></span> <span data-ttu-id="9c296-1392">如果開啟 [使用更緊密的間距]，即可讓每個頁面能夠容納得下更多郵件，並讓撰寫表單的控制項更為簡潔。</span><span class="sxs-lookup"><span data-stu-id="9c296-1392">With Use tighter spacing on, more messages fit per page, and controls on the compose forms are more streamlined.</span></span>

#### <a name="dedupe-mru-entries-when-using-the-onedrive-sync-client"></a><span data-ttu-id="9c296-1393">使用 OneDrive 同步處理用戶端時的刪除重複資料 MRU 項目</span><span class="sxs-lookup"><span data-stu-id="9c296-1393">Dedupe MRU entries when using the Onedrive sync client</span></span>

<span data-ttu-id="9c296-1394">透過刪除重複資料 MRU 項目，改善 OneDrive 同步處理用戶端與雲端附件的整合度並加快附加速度，讓其速度足以媲美同步處理資料的複製行為</span><span class="sxs-lookup"><span data-stu-id="9c296-1394">Enable better integration with onedrive sync client with cloud attachments by deduping the mru entries and to enable faster attach as copy behavior for synchronized data</span></span>

##### <a name="getting-started"></a><span data-ttu-id="9c296-1395">開始使用：</span><span class="sxs-lookup"><span data-stu-id="9c296-1395">Getting Started:</span></span>

<span data-ttu-id="9c296-1396">若您使用的是 OneDrive 同步處理用戶端，將再也看不到「附加檔案 MRU」的檔案重複項目。</span><span class="sxs-lookup"><span data-stu-id="9c296-1396">If you use the OneDrive sync client, you will no longer see file duplicates in the Attach File MRU.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="9c296-1397">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="9c296-1397">Scenarios to Try:</span></span>

<span data-ttu-id="9c296-1398">啟用 OneDrive 同步處理用戶端，並使用 Outlook 電腦版的 [附加檔案] 功能表</span><span class="sxs-lookup"><span data-stu-id="9c296-1398">Enable the OneDrive sync client and use the Attach File menu in Outlook Desktop</span></span>

#### <a name="improved-shared-folder-synchronization-for-mailboxes-with-many-folders"></a><span data-ttu-id="9c296-1399">已改善擁有多個資料夾的信箱共用資料夾同步處理</span><span class="sxs-lookup"><span data-stu-id="9c296-1399">Improved shared folder synchronization for mailboxes with many folders</span></span>

<span data-ttu-id="9c296-1400">Outlook 多年來在同步共用信箱時，其資料夾的數量限制最多為 500 個。</span><span class="sxs-lookup"><span data-stu-id="9c296-1400">For years Outlook has been limited to a maximum of 500 folders when synchronizing shared mailboxes.</span></span> <span data-ttu-id="9c296-1401">透過這項變更已讓 Outlook 獲得改善，您在同步時將不會再遇到這 500 個資料夾的數量限制。</span><span class="sxs-lookup"><span data-stu-id="9c296-1401">With this change Outlook has been improved to sync in a way that will no longer encounter this 500 folder limit.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="9c296-1402">開始使用：</span><span class="sxs-lookup"><span data-stu-id="9c296-1402">Getting Started:</span></span>

<span data-ttu-id="9c296-1403">在信箱中新增 1000 個資料夾、讓其他人存取信箱、新增「其他人」的 Outlook 設定檔，然後確認同步處理是否可正常運作。</span><span class="sxs-lookup"><span data-stu-id="9c296-1403">Create 1000 folders in a mailbox, give someone else access to the mailbox, create an Outlook profile for the "someone else" and verify that sync works.</span></span>

### <a name="word"></a><span data-ttu-id="9c296-1404">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-1404">Word</span></span>

#### <a name="erase-just-a-little-bit"></a><span data-ttu-id="9c296-1405">小面積清除</span><span class="sxs-lookup"><span data-stu-id="9c296-1405">Erase just a little bit</span></span>

##### <a name="getting-started"></a><span data-ttu-id="9c296-1406">開始使用：</span><span class="sxs-lookup"><span data-stu-id="9c296-1406">Getting Started:</span></span>

<span data-ttu-id="9c296-1407">前往 [繪圖] 索引標籤。選取 [橡皮擦] 下拉式清單。</span><span class="sxs-lookup"><span data-stu-id="9c296-1407">Go to the Draw Tab. Select the Eraser dropdown.</span></span> <span data-ttu-id="9c296-1408">選擇 [小型橡皮擦] 或 [中型橡皮擦]。</span><span class="sxs-lookup"><span data-stu-id="9c296-1408">Choose Small Eraser or Medium Eraser.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="9c296-1409">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="9c296-1409">Scenarios to Try:</span></span>

<span data-ttu-id="9c296-1410">前往 [繪圖] 索引標籤。選取畫筆。</span><span class="sxs-lookup"><span data-stu-id="9c296-1410">Go to the Draw Tab. Select a pen.</span></span> <span data-ttu-id="9c296-1411">畫出一道筆跡線條。</span><span class="sxs-lookup"><span data-stu-id="9c296-1411">Draw an ink stroke.</span></span> <span data-ttu-id="9c296-1412">選取 [橡皮擦] 下拉式清單。</span><span class="sxs-lookup"><span data-stu-id="9c296-1412">Select the Eraser dropdown.</span></span> <span data-ttu-id="9c296-1413">選擇 [小型橡皮擦] 或 [中型橡皮擦]。</span><span class="sxs-lookup"><span data-stu-id="9c296-1413">Choose Small Eraser or Medium Eraser.</span></span> <span data-ttu-id="9c296-1414">清除一小塊的筆跡線條。</span><span class="sxs-lookup"><span data-stu-id="9c296-1414">Erase just bits of the ink stroke.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9c296-1415">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="9c296-1415">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="9c296-1416">全部</span><span class="sxs-lookup"><span data-stu-id="9c296-1416">All</span></span> 
- <span data-ttu-id="9c296-1417">我們已修正可能會導致部分使用者無法儲存成 PDF 的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1417">We fixed an issue which could prevent some users from saving as PDF</span></span>
- <span data-ttu-id="9c296-1418">我們已修正可能會影響使用者在 32 位元系統上儲存大型檔案的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1418">We fixed an issue which could impact users saving large files on a 32-bit system</span></span>

### <a name="word"></a><span data-ttu-id="9c296-1419">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-1419">Word</span></span> 
- <span data-ttu-id="9c296-1420">我們已大幅改善 [聽寫] 功能的反應能力</span><span class="sxs-lookup"><span data-stu-id="9c296-1420">We significantly improved the responsiveness of the dictation feature</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-1421">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-1421">Excel</span></span>
- <span data-ttu-id="9c296-1422">我們已修正按兩下事件在觸控式螢幕裝置上可能會失靈的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1422">We fixed an issue where double-click events could fail on touch screen devices</span></span>
- <span data-ttu-id="9c296-1423">我們已修正可能會導致部分使用者無法編輯 VBA 巨集的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1423">We fixed an issue which could prevent some users from being able to edit VBA macros</span></span>
- <span data-ttu-id="9c296-1424">我們已修正使用交叉分析篩選器時可能會影響效能的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1424">We fixed an issue which could impact performance when using slicers</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-1425">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-1425">PowerPoint</span></span>
- <span data-ttu-id="9c296-1426">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1426">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-1427">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-1427">Outlook</span></span>
- <span data-ttu-id="9c296-1428">我們已修正從所選範本中會出現錯誤範本的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1428">We fixed an issue where the wrong template could be displayed from what was selected</span></span>

### <a name="access"></a><span data-ttu-id="9c296-1429">Access</span><span class="sxs-lookup"><span data-stu-id="9c296-1429">Access</span></span>
- <span data-ttu-id="9c296-1430">我們已修正在使用縮放建立器顯示完整 RTF 格式時，可能難以閱讀的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1430">We fixed an issue where using the zoom builder to display long rich text, could be hard to read</span></span>

### <a name="project"></a><span data-ttu-id="9c296-1431">Project</span><span class="sxs-lookup"><span data-stu-id="9c296-1431">Project</span></span>
- <span data-ttu-id="9c296-1432">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1432">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-10-2019"></a><span data-ttu-id="9c296-1433">2019 年 5 月 10 日</span><span class="sxs-lookup"><span data-stu-id="9c296-1433">May 10, 2019</span></span>
<span data-ttu-id="9c296-1434">版本 1906 (組建 11702.20000)</span><span class="sxs-lookup"><span data-stu-id="9c296-1434">Version 1906 (build 11702.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9c296-1435">新功能：</span><span class="sxs-lookup"><span data-stu-id="9c296-1435">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-1436">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-1436">Outlook</span></span>

<span data-ttu-id="9c296-1437">**在螢幕上容納更多郵件：** 選取 [檢視] > [使用更緊密的間距] 來調整郵件之間的間距。</span><span class="sxs-lookup"><span data-stu-id="9c296-1437">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9c296-1438">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="9c296-1438">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="9c296-1439">全部</span><span class="sxs-lookup"><span data-stu-id="9c296-1439">All</span></span>
- <span data-ttu-id="9c296-1440">我們已修正 [另存新檔] 對話方塊顯示不正確路徑的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1440">We fixed an issue where the Save As dialog could display the incorrect path</span></span>

### <a name="word"></a><span data-ttu-id="9c296-1441">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-1441">Word</span></span> 
- <span data-ttu-id="9c296-1442">我們已修正有些「告訴我」選項無法插入的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1442">We fixed an issue where some selections from Tell Me would not get inserted</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-1443">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-1443">Excel</span></span>
- <span data-ttu-id="9c296-1444">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1444">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-1445">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-1445">PowerPoint</span></span>
- <span data-ttu-id="9c296-1446">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1446">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-1447">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-1447">Outlook</span></span>
- <span data-ttu-id="9c296-1448">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1448">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="9c296-1449">Access</span><span class="sxs-lookup"><span data-stu-id="9c296-1449">Access</span></span>
- <span data-ttu-id="9c296-1450">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1450">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9c296-1451">Project</span><span class="sxs-lookup"><span data-stu-id="9c296-1451">Project</span></span>
- <span data-ttu-id="9c296-1452">我們已修正任務識別碼需要醒目提示才能看見的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1452">We fixed an issue where Task ID's could require highlighting to see</span></span>

</BR></BR>

## <a name="may-3-2019"></a><span data-ttu-id="9c296-1453">2019 年 5 月 3 日</span><span class="sxs-lookup"><span data-stu-id="9c296-1453">May 3, 2019</span></span>
<span data-ttu-id="9c296-1454">版本 1906 (組建 11629.20008)</span><span class="sxs-lookup"><span data-stu-id="9c296-1454">Version 1906 (build 11629.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9c296-1455">新功能：</span><span class="sxs-lookup"><span data-stu-id="9c296-1455">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-1456">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-1456">Outlook</span></span>

<span data-ttu-id="9c296-1457">**集中所有加密選項：** 只要前往 [選項] > [加密]，即可選擇要用來保護電子郵件訊息的方法。</span><span class="sxs-lookup"><span data-stu-id="9c296-1457">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9c296-1458">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="9c296-1458">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="9c296-1459">全部</span><span class="sxs-lookup"><span data-stu-id="9c296-1459">All</span></span>
- <span data-ttu-id="9c296-1460">我們已修正有些使用者使用商務用 OneDrive 同步處理時遇到的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1460">We fixed an issue where some users would experience problems syncing with OneDrive for Business</span></span>

### <a name="word"></a><span data-ttu-id="9c296-1461">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-1461">Word</span></span> 
- <span data-ttu-id="9c296-1462">我們已修正在某些情況下，Word 會花很長時間啟動的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1462">We fixed an issue where in some cases Word would take a long time to start</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-1463">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-1463">Excel</span></span>
- <span data-ttu-id="9c296-1464">我們已修正升級至較新版 Excel 後活頁簿的外部連結有時會被移除的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1464">We fixed an issue where external links were sometimes removed from workbooks after upgrading to a newer version of Excel</span></span>
- <span data-ttu-id="9c296-1465">我們已修正有些使用者可能會遇到無法在新活頁簿中選取儲存格的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1465">We fixed an issue where some users could experience difficulty selecting cells in a new workbook</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-1466">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-1466">PowerPoint</span></span>
- <span data-ttu-id="9c296-1467">我們已修正將繪圖轉換成文字時字型大小不一致的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1467">We fixed an issue where font sizes were not consistant when converting drawings to text</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-1468">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-1468">Outlook</span></span>
- <span data-ttu-id="9c296-1469">我們已修正從 .VCF 檔案儲存連絡人可能會導致空白欄位的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1469">We fixed an issue where saving a contact from a .VCF file could result in empty fields</span></span>
- <span data-ttu-id="9c296-1470">我們已修正即使郵件已寄出卻仍卡在寄件匣資料夾的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1470">We fixed an issue where a message could get stuck in the outbox folder even though it had been sent</span></span>
- <span data-ttu-id="9c296-1471">我們已修正檢視 DRM 訊息時 Outlook 可能會當機的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1471">We fixed an issue where Outlook could crash when viewing a DRM message</span></span>

### <a name="access"></a><span data-ttu-id="9c296-1472">Access</span><span class="sxs-lookup"><span data-stu-id="9c296-1472">Access</span></span>
- <span data-ttu-id="9c296-1473">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1473">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9c296-1474">Project</span><span class="sxs-lookup"><span data-stu-id="9c296-1474">Project</span></span>
- <span data-ttu-id="9c296-1475">我們已修正編輯器會從中文切換為英文的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1475">We fixed an issue where the editor would switch from Chinese to English</span></span>
- <span data-ttu-id="9c296-1476">我們已修正主專案的已發佈複本中出現未發佈工作的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1476">We fixed an issue where unpublished tasks could appear in the published copy of a master project</span></span>

</BR></BR>

## <a name="april-26-2019"></a><span data-ttu-id="9c296-1477">2019 年 4 月 26 日</span><span class="sxs-lookup"><span data-stu-id="9c296-1477">April 26, 2019</span></span>
<span data-ttu-id="9c296-1478">版本 1905 (組建 11617.20002)</span><span class="sxs-lookup"><span data-stu-id="9c296-1478">Version 1905 (build 11617.20002)</span></span>

## <a name="new-features"></a><span data-ttu-id="9c296-1479">新功能</span><span class="sxs-lookup"><span data-stu-id="9c296-1479">New Features</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-1480">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-1480">Outlook</span></span>

<span data-ttu-id="9c296-1481">**共用行事曆更新的速度更快：** 針對 Office 365 中的共用行事曆，Outlook 可以使用 REST API 更新這些行事曆。</span><span class="sxs-lookup"><span data-stu-id="9c296-1481">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="9c296-1482">開啟預覽以更快且更可靠地更新共用行事曆。</span><span class="sxs-lookup"><span data-stu-id="9c296-1482">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-1483">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-1483">Excel</span></span>

#### <a name="coauthoring-improvements"></a><span data-ttu-id="9c296-1484">共同撰寫的增強功能</span><span class="sxs-lookup"><span data-stu-id="9c296-1484">Coauthoring improvements</span></span>

<span data-ttu-id="9c296-1485">改善共同撰寫的體驗，盡可能讓其他人即時收到修改過的內容。</span><span class="sxs-lookup"><span data-stu-id="9c296-1485">Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

### <a name="visio"></a><span data-ttu-id="9c296-1486">Visio</span><span class="sxs-lookup"><span data-stu-id="9c296-1486">Visio</span></span>

- <span data-ttu-id="9c296-1487">**從 Power BI 匯出 Visio 視覺效果：** 當匯出 Power BI 報表為 PDF 或 PowerPoint 等更多檔案時，Power BI Visio 視覺效果會正常顯示。</span><span class="sxs-lookup"><span data-stu-id="9c296-1487">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9c296-1488">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="9c296-1488">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="9c296-1489">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-1489">Word</span></span> 
- <span data-ttu-id="9c296-1490">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1490">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-1491">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-1491">Excel</span></span>
- <span data-ttu-id="9c296-1492">我們已修正 Solver 巨集無法執行的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1492">We fixed an issue where Solver macros would fail to run</span></span>
- <span data-ttu-id="9c296-1493">我們已修正阻止 Excel 檔案匯入到 SharePoint 的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1493">We fixed an issue which could prevent Excel files from being imported into SharePoint</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-1494">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-1494">PowerPoint</span></span>
- <span data-ttu-id="9c296-1495">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1495">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-1496">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-1496">Outlook</span></span>
- <span data-ttu-id="9c296-1497">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1497">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="9c296-1498">Access</span><span class="sxs-lookup"><span data-stu-id="9c296-1498">Access</span></span>
- <span data-ttu-id="9c296-1499">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1499">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9c296-1500">Project</span><span class="sxs-lookup"><span data-stu-id="9c296-1500">Project</span></span>
- <span data-ttu-id="9c296-1501">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1501">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-19-2019"></a><span data-ttu-id="9c296-1502">2019 年 4 月 19 日</span><span class="sxs-lookup"><span data-stu-id="9c296-1502">April 19, 2019</span></span>
<span data-ttu-id="9c296-1503">版本 1905 (組建 11609.20002)</span><span class="sxs-lookup"><span data-stu-id="9c296-1503">Version 1905 (build 11609.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9c296-1504">新功能：</span><span class="sxs-lookup"><span data-stu-id="9c296-1504">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-1505">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-1505">Outlook</span></span>

<span data-ttu-id="9c296-1506">**搜尋人員時取得電子郵件建議：** 當您在 [搜尋] 方塊中輸入人員的名稱時，最相關的電子郵件訊息會包括在您的搜尋建議中。</span><span class="sxs-lookup"><span data-stu-id="9c296-1506">**Get email suggestions when you search for a person:** When you type a person's name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-1507">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-1507">Excel</span></span>

#### <a name="improved-filled-maps-experience-using-data-types"></a><span data-ttu-id="9c296-1508">使用資料類型改善區域分布圖體驗</span><span class="sxs-lookup"><span data-stu-id="9c296-1508">Improved Filled Maps experience using Data Types</span></span>

<span data-ttu-id="9c296-1509">此功能是針對使用 Excel 的地理資料類型繪製區域分布圖圖表使用者的增強功能。</span><span class="sxs-lookup"><span data-stu-id="9c296-1509">This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="9c296-1510">對使用者的優點是功能之間有更豐富的整合，以及使用者要對應的區域會有更好的精確度。</span><span class="sxs-lookup"><span data-stu-id="9c296-1510">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="9c296-1511">其他優點包括功能能夠對應城市多邊形。</span><span class="sxs-lookup"><span data-stu-id="9c296-1511">Additional benefits include - ability to map city polygons.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="9c296-1512">開始使用：</span><span class="sxs-lookup"><span data-stu-id="9c296-1512">Getting Started:</span></span>

- <span data-ttu-id="9c296-1513">此功能是 Excel 內現有功能的增強功能。</span><span class="sxs-lookup"><span data-stu-id="9c296-1513">This feature is an improvement to the existing features within Excel.</span></span> <span data-ttu-id="9c296-1514">若要使用增強功能，請將位置轉換為豐富的實體，並使用區域分布圖繪製。</span><span class="sxs-lookup"><span data-stu-id="9c296-1514">To use the improvement - convert locations into Rich Entities and plot with Filled Maps.</span></span> 

##### <a name="scenarios-to-try"></a><span data-ttu-id="9c296-1515">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="9c296-1515">Scenarios to Try:</span></span>

- <span data-ttu-id="9c296-1516">使用者可以嘗試對應城市、省/市、縣/市、國家/地區和郵遞區號。</span><span class="sxs-lookup"><span data-stu-id="9c296-1516">Users can try mapping cities, states, counties, countries and zip codes.</span></span> 


## <a name="notable-fixes"></a><span data-ttu-id="9c296-1517">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="9c296-1517">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="9c296-1518">所有應用程式</span><span class="sxs-lookup"><span data-stu-id="9c296-1518">All Applications</span></span>
- <span data-ttu-id="9c296-1519">我們已修正每當應用程式啟動時會顯示 [初次執行] 對話方塊的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1519">We fixed an issue where the First Run dialog would display whenever an application was launched</span></span>
- <span data-ttu-id="9c296-1520">我們已修正 [另存新檔] 對話方塊中 SharePoint 連結可能遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-1520">We fixed an issue where a SharePoint link in the "save as" dialog could be missing.</span></span>
- <span data-ttu-id="9c296-1521">我們已修正使用者錯誤地看到 [立即修復] 對話方塊的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1521">We fixed an issue where users would incorrectly see a "Repair Now" dialog</span></span>

### <a name="word"></a><span data-ttu-id="9c296-1522">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-1522">Word</span></span> 
- <span data-ttu-id="9c296-1523">我們已修正某些使用者在要求字型時，可能會收到記憶體或磁碟空間不足錯誤的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1523">We fixed an issue where some users could receive an error for insufficient memory or disk space when requesting a font</span></span>
- <span data-ttu-id="9c296-1524">我們已修正視窗從 [註解] 窗格切換時，焦點可能會遺失的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1524">We fixed an issue where a window could lose focus when switching from the comments pane</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-1525">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-1525">Excel</span></span>
- <span data-ttu-id="9c296-1526">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1526">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-1527">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-1527">PowerPoint</span></span>
- <span data-ttu-id="9c296-1528">我們已修正會妨礙調整商標圖形大小的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1528">We fixed an issue preventing the resizing of branded shapes</span></span>
- <span data-ttu-id="9c296-1529">我們已修正在受保護的檢視模式中開啟檔案時，PowerPoint 會當機的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1529">We fixed an issue where PowerPoint could crash when opening a file in protected view mode</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-1530">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-1530">Outlook</span></span>
- <span data-ttu-id="9c296-1531">我們已修正會防礙一些使用者選取中文文字的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1531">We fixed an issue which prevented some users from selecting Chinese words</span></span>
- <span data-ttu-id="9c296-1532">我們已修正未正確計算到期日的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1532">We fixed an issue where expiry dates were not calculated correctly</span></span>

### <a name="access"></a><span data-ttu-id="9c296-1533">Access</span><span class="sxs-lookup"><span data-stu-id="9c296-1533">Access</span></span>
- <span data-ttu-id="9c296-1534">我們已修正會防礙一些使用者使用巨集建立器的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1534">We fixed an issue which prevented some users from using the Macro Builder</span></span>
- <span data-ttu-id="9c296-1535">我們已修正列印報表只會列印第一頁的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1535">We fixed an issue where printing a report would only print the first page</span></span>
- <span data-ttu-id="9c296-1536">我們已修正將游標移到超連結上時，應用程式會當機的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1536">We fixed an issue where the application could crash when hovering over a hyperlink</span></span>
- <span data-ttu-id="9c296-1537">我們已修正使用關聯性檢視檢視時，造成某些項目在螢幕上消失的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1537">We fixed an issue which caused some items to appear off screen when using relationships view</span></span>

### <a name="project"></a><span data-ttu-id="9c296-1538">Project</span><span class="sxs-lookup"><span data-stu-id="9c296-1538">Project</span></span>
- <span data-ttu-id="9c296-1539">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1539">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-12-2019"></a><span data-ttu-id="9c296-1540">2019 年 4 月 12 日</span><span class="sxs-lookup"><span data-stu-id="9c296-1540">April 12, 2019</span></span>
<span data-ttu-id="9c296-1541">版本 1905 (組建 11601.20042)</span><span class="sxs-lookup"><span data-stu-id="9c296-1541">Version 1905 (build 11601.20042)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9c296-1542">新功能：</span><span class="sxs-lookup"><span data-stu-id="9c296-1542">What's New:</span></span>

### <a name="access"></a><span data-ttu-id="9c296-1543">Access</span><span class="sxs-lookup"><span data-stu-id="9c296-1543">Access</span></span>

#### <a name="get-smart-with-microsoft-graph"></a><span data-ttu-id="9c296-1544">充分發揮 Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="9c296-1544">Get smart with Microsoft Graph</span></span>

<span data-ttu-id="9c296-1545">使用智慧型技術匯入或連結到智慧型資料，並重新打造您的桌面資料庫。</span><span class="sxs-lookup"><span data-stu-id="9c296-1545">Import or link to intelligent data and reinvent your desktop database with Intelligent Technology.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9c296-1546">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="9c296-1546">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="9c296-1547">所有應用程式</span><span class="sxs-lookup"><span data-stu-id="9c296-1547">All Applications</span></span>
 - <span data-ttu-id="9c296-1548">我們已修正會防止使用者將檔案儲存到雲端位置的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1548">We fixed an issue which prevented some users from saving files to cloud locations</span></span>
 - <span data-ttu-id="9c296-1549">我們已修正可能從功能區開啟錯誤窗格的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1549">We fixed an issue where the wrong pane could open from the ribbon</span></span>

### <a name="word"></a><span data-ttu-id="9c296-1550">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-1550">Word</span></span> 
- <span data-ttu-id="9c296-1551">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1551">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-1552">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-1552">Excel</span></span>
- <span data-ttu-id="9c296-1553">我們已修正當活頁簿不包含連結資料類型時，使用者會看到連結資料類型之錯誤訊息的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1553">We fixed an issue where users would see an error message for linked data types when the workbook did not contain linked data types</span></span>
- <span data-ttu-id="9c296-1554">我們已修正在本機與線上檢視 Word 文件時，文件中的 URL 連結可能變更的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1554">We fixed an issue where URL links within a Word document could change when viewed locally vs. online</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-1555">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-1555">PowerPoint</span></span>
- <span data-ttu-id="9c296-1556">我們已修正應用程式可能會在從 [動畫] 索引標籤復原變更之後當機的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1556">We fixed an issue where the application could crash after undoing changes from the animations tab</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-1557">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-1557">Outlook</span></span>
- <span data-ttu-id="9c296-1558">我們已修正會防止一些使用者修改公用資料夾中連絡人 [備註] 欄位的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1558">We fixed an issue which prevented some users from modifying the Notes field for contacts in a Public Folder</span></span>
- <span data-ttu-id="9c296-1559">我們已修正到期日與刪除日期之間可能發生衝突的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1559">We fixed an issue where a conflict could occur between expiration dates and deletion dates</span></span>

### <a name="access"></a><span data-ttu-id="9c296-1560">Access</span><span class="sxs-lookup"><span data-stu-id="9c296-1560">Access</span></span>
- <span data-ttu-id="9c296-1561">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1561">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9c296-1562">Project</span><span class="sxs-lookup"><span data-stu-id="9c296-1562">Project</span></span>
- <span data-ttu-id="9c296-1563">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1563">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-5-2019"></a><span data-ttu-id="9c296-1564">2019 年 4 月 5 日</span><span class="sxs-lookup"><span data-stu-id="9c296-1564">April 5, 2019</span></span>
<span data-ttu-id="9c296-1565">版本 1904 (組建 11527.20014)</span><span class="sxs-lookup"><span data-stu-id="9c296-1565">Version 1904 (build 11527.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9c296-1566">新功能：</span><span class="sxs-lookup"><span data-stu-id="9c296-1566">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-1567">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-1567">Outlook</span></span>

#### <a name="outlook-for-windows--set-and-share-your-focused-inbox-settings"></a><span data-ttu-id="9c296-1568">Windows 版 Outlook：設定並共用您的 [焦點收件匣] 設定</span><span class="sxs-lookup"><span data-stu-id="9c296-1568">Outlook for Windows:  set and share your Focused Inbox settings</span></span>

<span data-ttu-id="9c296-1569">[焦點收件匣] 喜好設定會儲存在雲端內，因此當您在任何電腦上使用 Windows 版 Outlook 和 Outlook 網頁版時，都可以取得相同的一致體驗。</span><span class="sxs-lookup"><span data-stu-id="9c296-1569">Your Focused Inbox preferences are stored in the cloud so you can enjoy the same consistent experience when using Outlook for Windows and Outlook on the web on any computer.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="9c296-1570">開始使用：</span><span class="sxs-lookup"><span data-stu-id="9c296-1570">Getting Started:</span></span>

<span data-ttu-id="9c296-1571">在 [檔案] > [選項] > [一般] 索引標籤下，還有一個名為 [將我的 Outlook 設定儲存在雲端中] 的新喜好設定。</span><span class="sxs-lookup"><span data-stu-id="9c296-1571">Under File > Options > General tab, there is a new preference for 'Store my Outlook settings in the cloud'.</span></span> <span data-ttu-id="9c296-1572">使用者需要核取方塊，才能讓他們的 [焦點收件匣] 設定漫遊到其他電腦的 Outlook 安裝和 OWA。</span><span class="sxs-lookup"><span data-stu-id="9c296-1572">Users will need to check the box to enable their Focused Inbox setting to roam to other Desktop Outlook installations and OWA.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="9c296-1573">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="9c296-1573">Scenarios to Try:</span></span>

<span data-ttu-id="9c296-1574">在已開啟雲端設定喜好設定的電腦上變更 [焦點收件匣]。</span><span class="sxs-lookup"><span data-stu-id="9c296-1574">Change Focused Inbox on the machine that has cloud settings preference turned on.</span></span> <span data-ttu-id="9c296-1575">瀏覽至 OWA，然後查看那裡也同樣套用了喜好設定。</span><span class="sxs-lookup"><span data-stu-id="9c296-1575">Navigate to OWA and see the preference applied there as well.</span></span> <span data-ttu-id="9c296-1576">在 OWA 變更 [焦點收件匣]，然後啟動電腦版 Outlook 查看已反映喜好設定。</span><span class="sxs-lookup"><span data-stu-id="9c296-1576">Change Focused Inbox in OWA and start Desktop Outlook to see the preference reflected.</span></span>

### <a name="word"></a><span data-ttu-id="9c296-1577">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-1577">Word</span></span>

#### <a name="learning-tools-mode-has-additional-support-for-more-page-colors"></a><span data-ttu-id="9c296-1578">[學習工具] 模式額外支援更多頁面色彩</span><span class="sxs-lookup"><span data-stu-id="9c296-1578">Learning Tools mode has additional support for more page colors</span></span>

<span data-ttu-id="9c296-1579">Word 中的 [學習工具] 新增更多頁面佈景主題色彩的支援，讓您能夠變更頁面的背景色彩。</span><span class="sxs-lookup"><span data-stu-id="9c296-1579">Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span>  <span data-ttu-id="9c296-1580">許多人在背景全白或全黑時閱讀會有困難，因此我們在 PC 版和 Mac 版 Word 中擴大了色彩選項。</span><span class="sxs-lookup"><span data-stu-id="9c296-1580">Many people have challenges reading with an all-white or all-black background, so we've expanded the choice of colors in Word on PC and Mac.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="9c296-1581">快速入門：</span><span class="sxs-lookup"><span data-stu-id="9c296-1581">Getting Started:</span></span>

<span data-ttu-id="9c296-1582">若要試用，請移至 [檢視] 索引標籤，選擇 [學習工具]，然後選擇 [頁面色彩]。</span><span class="sxs-lookup"><span data-stu-id="9c296-1582">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="9c296-1583">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="9c296-1583">Scenarios to Try:</span></span>

<span data-ttu-id="9c296-1584">若要試用，請移至 [檢視] 索引標籤，選擇 [學習工具]，然後選擇 [頁面色彩]。</span><span class="sxs-lookup"><span data-stu-id="9c296-1584">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-1585">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-1585">Excel</span></span>

#### <a name="elevate-creativity-with-animated-3d-models"></a><span data-ttu-id="9c296-1586">以具備動畫效果的 3D 模型提高創意</span><span class="sxs-lookup"><span data-stu-id="9c296-1586">Elevate Creativity with Animated 3D Models</span></span>

<span data-ttu-id="9c296-1587">Office 現在支援動畫模型，這類模型能在編輯器中播放，讓您的試算表更生動！</span><span class="sxs-lookup"><span data-stu-id="9c296-1587">Office now supports animated models, which will playback in the editor so you can bring your sheets to life!</span></span>

#### <a name="getting-started"></a><span data-ttu-id="9c296-1588">開始使用：</span><span class="sxs-lookup"><span data-stu-id="9c296-1588">Getting Started:</span></span>

1. <span data-ttu-id="9c296-1589">開啟 Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-1589">Open Excel</span></span>
2. <span data-ttu-id="9c296-1590">插入具備動畫效果的 3D 模型 (很快會進到 Remix，但現在請在此位置存取動畫模型：\\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span><span class="sxs-lookup"><span data-stu-id="9c296-1590">Insert an animated 3D Model (coming to Remix soon, but for now, access animated models here: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span></span>
3. <span data-ttu-id="9c296-1591">動畫模型會在編輯器中播放！</span><span class="sxs-lookup"><span data-stu-id="9c296-1591">The animated model will play in the editor!</span></span> <span data-ttu-id="9c296-1592">[檢查投影片放映] 模式 - 動畫模型也會在那裡播放！</span><span class="sxs-lookup"><span data-stu-id="9c296-1592">Check Slideshow mode - it will play there too!</span></span>
4. <span data-ttu-id="9c296-1593">在 3D 格式功能區中，探索模型中更多的動畫場景</span><span class="sxs-lookup"><span data-stu-id="9c296-1593">In the 3D Format Ribbon, explore more animation scenes in the model</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="9c296-1594">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="9c296-1594">Scenarios to Try:</span></span>

1. <span data-ttu-id="9c296-1595">插入動畫模型，然後看它在編輯器中播放</span><span class="sxs-lookup"><span data-stu-id="9c296-1595">Insert an animated model and watch it play in the editor</span></span>
2. <span data-ttu-id="9c296-1596">透過 3D 格式功能區中的 [場景庫]，探索動畫模型中可用的動畫場景</span><span class="sxs-lookup"><span data-stu-id="9c296-1596">Explore the animation scenes available in the animated model via the Scenes Gallery, available in the 3D Format Ribbon</span></span>
3. <span data-ttu-id="9c296-1597">透過功能區、浮動工具列或空格鍵輕鬆地播放/暫停動畫</span><span class="sxs-lookup"><span data-stu-id="9c296-1597">Easily play/pause the animation via the ribbon, floatie or space bar</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9c296-1598">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="9c296-1598">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="9c296-1599">所有應用程式</span><span class="sxs-lookup"><span data-stu-id="9c296-1599">All Applications</span></span>
- <span data-ttu-id="9c296-1600">我們已修正 Excel 的內容功能表中會出現錯誤應用程式圖示的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1600">We fixed an issue where the incorrect app icon could appear for Excel in contextual menus</span></span>
- <span data-ttu-id="9c296-1601">我們已修正在安裝更新之後 [檔案功能表] 按鈕會消失的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1601">We fixed an issue where the File Menu button could disappear after installing an update</span></span>
- <span data-ttu-id="9c296-1602">我們已修正會變更您的使用者授權的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1602">We fixed an issue which could change your user license</span></span>

### <a name="word"></a><span data-ttu-id="9c296-1603">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-1603">Word</span></span> 
- <span data-ttu-id="9c296-1604">我們已修正文字在特定縮放比例中無法正常顯示的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1604">We fixed an issue where text would not render correctly at certain zoom levels</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-1605">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-1605">Excel</span></span>
- <span data-ttu-id="9c296-1606">我們已修正使用者在進行編輯之後未收到儲存活頁簿提示的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1606">We fixed an issue where users would not be prompted to save a workbook after making edits</span></span>
- <span data-ttu-id="9c296-1607">我們已修正當使用者共用活頁簿時未觸發 BeforeSave 事件的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-1607">We fixed an issue where a BeforeSave event would not be triggered if the user shared the workbook.</span></span>
- <span data-ttu-id="9c296-1608">我們已修正將欄的大小重新調整為小於 6 像素會擲回不正確錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-1608">We fixed an issue where resizing a column to fewer than 6 pixels could throw an incorrect error message.</span></span>
- <span data-ttu-id="9c296-1609">我們已修正 Excel 忽略 Application.Visible 旗標的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1609">We fixed an issue where Excel would ignore the Application.Visible flag</span></span>
- <span data-ttu-id="9c296-1610">我們已修正追蹤箭號保留在非作用中凍結窗格的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1610">We fixed an issue where trace arrows would remain on non-active frozen panes</span></span>
- <span data-ttu-id="9c296-1611">我們已修正在開啟活頁簿時日期和貨幣儲存格格式會變更的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1611">We fixed an issue where cell formatting of dates an currency could change when opening a workbook</span></span>
- <span data-ttu-id="9c296-1612">我們已修正工具提示會意外移動的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1612">We fixed an issue where tooltips would move unexpectedly</span></span>
- <span data-ttu-id="9c296-1613">我們已修正 Power Query 編輯器的當地語系化問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1613">We fixed localization issues for the Power Query editor</span></span>
- <span data-ttu-id="9c296-1614">我們已修正在透過電子郵件傳送時活頁簿附件會遭到移除的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1614">We fixed an issue where a workbook would be removed as an attachment when sending via e-mail</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-1615">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-1615">PowerPoint</span></span>
- <span data-ttu-id="9c296-1616">我們已修正複製圖形會比預期還要久的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1616">We fixed an issue where copying shapes would take longer than expected</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-1617">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-1617">Outlook</span></span>
- <span data-ttu-id="9c296-1618">我們已修正在使用繪圖工具時 Outlook 可能會當機的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1618">We fixed an issue where Outlook could crash while using the drawing tool</span></span>
- <span data-ttu-id="9c296-1619">我們已修正當撰寫 html 電子郵件時的當地語系化問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1619">We fixed a localization issue when composing html e-mails</span></span>
- <span data-ttu-id="9c296-1620">我們已修正使用者在選取下面窗格時會遇到困難的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1620">We fixed an issue where the user would have difficulty in selecting the lower pane</span></span>

### <a name="access"></a><span data-ttu-id="9c296-1621">Access</span><span class="sxs-lookup"><span data-stu-id="9c296-1621">Access</span></span>
- <span data-ttu-id="9c296-1622">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1622">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9c296-1623">Project</span><span class="sxs-lookup"><span data-stu-id="9c296-1623">Project</span></span>
- <span data-ttu-id="9c296-1624">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1624">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-22-2019"></a><span data-ttu-id="9c296-1625">2019 年 3 月 22 日</span><span class="sxs-lookup"><span data-stu-id="9c296-1625">March 22, 2019</span></span>
<span data-ttu-id="9c296-1626">版本 1904 (組建 11514.20004)</span><span class="sxs-lookup"><span data-stu-id="9c296-1626">Version 1904 (build 11514.20004)</span></span>

## <a name="new-features"></a><span data-ttu-id="9c296-1627">新功能</span><span class="sxs-lookup"><span data-stu-id="9c296-1627">New Features</span></span>

- <span data-ttu-id="9c296-1628">**隱私權控制：** 用於診斷資料和連線體驗的新增、更新及改良的控制項。</span><span class="sxs-lookup"><span data-stu-id="9c296-1628">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> <span data-ttu-id="9c296-1629">深入了解 <https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json></span><span class="sxs-lookup"><span data-stu-id="9c296-1629">Learn more <https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json></span></span>

- <span data-ttu-id="9c296-1630">**Office 圖示有新的外觀：** Office 圖示經過重新設計，以反映簡單、功能強大且智慧型的 Office 體驗。</span><span class="sxs-lookup"><span data-stu-id="9c296-1630">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9c296-1631">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="9c296-1631">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="9c296-1632">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-1632">Word</span></span> 
- <span data-ttu-id="9c296-1633">我們已修正 UI 經常會顯示「正在檢查變更」的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1633">We fixed an issue where the UI would constantly display "Checking for Changes"</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-1634">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-1634">Excel</span></span>
- <span data-ttu-id="9c296-1635">我們已修正應用程式可能在移動工作表之後當機的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1635">We fixed an issue where the application could crash after moving a worksheet</span></span>
- <span data-ttu-id="9c296-1636">我們已修正應用程式可能在儲存為 PDF 之後當機的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1636">We fixed an issue where the application could crash after saving as a PDF</span></span>
- <span data-ttu-id="9c296-1637">我們已修正儲存對話方塊不會接受某些韓文字元的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1637">We fixed an issue where the save dialog would not accept some Korean characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-1638">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-1638">PowerPoint</span></span>
- <span data-ttu-id="9c296-1639">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1639">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-1640">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-1640">Outlook</span></span>
- <span data-ttu-id="9c296-1641">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1641">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="9c296-1642">Access</span><span class="sxs-lookup"><span data-stu-id="9c296-1642">Access</span></span>
- <span data-ttu-id="9c296-1643">我們已修正 Access 中對 Access 建立額外捷徑的錯誤訊息</span><span class="sxs-lookup"><span data-stu-id="9c296-1643">We fixed the error message in Access where an extra shortcut to Access was created</span></span>
- <span data-ttu-id="9c296-1644">我們已修正來自連結 SharePoint 的資料無法正確顯示的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1644">We fixed an issue where data from a linked SharePoint would display incorrectly</span></span>

### <a name="project"></a><span data-ttu-id="9c296-1645">Project</span><span class="sxs-lookup"><span data-stu-id="9c296-1645">Project</span></span>
- <span data-ttu-id="9c296-1646">我們已修正語言設定會從中文切換為英文的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1646">We fixed an issue where the language settings would switch from Chinese to English</span></span>
- <span data-ttu-id="9c296-1647">我們已修正應用程式可能在同步處理到 SharePoint 時當機的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1647">We fixed an issue where the application could crash when synching to SharePoint</span></span>

</BR></BR>

## <a name="march-15-2019"></a><span data-ttu-id="9c296-1648">2019 年 3 月 15 日</span><span class="sxs-lookup"><span data-stu-id="9c296-1648">March 15, 2019</span></span>
<span data-ttu-id="9c296-1649">版本 1904 (組建 11504.20000)</span><span class="sxs-lookup"><span data-stu-id="9c296-1649">Version 1904 (build 11504.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9c296-1650">新功能：</span><span class="sxs-lookup"><span data-stu-id="9c296-1650">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="9c296-1651">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-1651">Word</span></span>

#### <a name="focus-mode"></a><span data-ttu-id="9c296-1652">焦點模式</span><span class="sxs-lookup"><span data-stu-id="9c296-1652">Focus Mode</span></span>

<span data-ttu-id="9c296-1653">切換到 [檢視] 功能表中的 [焦點] 以移除令人分心的事物，讓您更能專注於工作。</span><span class="sxs-lookup"><span data-stu-id="9c296-1653">Switch to Focus on the View menu to remove distractions and concentrate on your work.</span></span> <span data-ttu-id="9c296-1654">僅供 Office 365 訂閱者使用。</span><span class="sxs-lookup"><span data-stu-id="9c296-1654">For Office 365 subscribers only.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="9c296-1655">開始使用：</span><span class="sxs-lookup"><span data-stu-id="9c296-1655">Getting Started:</span></span>

<span data-ttu-id="9c296-1656">[檢視] 索引標籤 功能區狀態列中的 [焦點] 按鈕 [焦點] 按鈕</span><span class="sxs-lookup"><span data-stu-id="9c296-1656">View tab "Focus" Button in the Ribbon Status Bar "Focus" Button</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="9c296-1657">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="9c296-1657">Scenarios to Try:</span></span>

<span data-ttu-id="9c296-1658">進入焦點模式，享受專注的體驗</span><span class="sxs-lookup"><span data-stu-id="9c296-1658">Enter Focus Mode and experience the Focused Experience</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9c296-1659">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="9c296-1659">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="9c296-1660">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-1660">Word</span></span> 
- <span data-ttu-id="9c296-1661">我們已修正以 PDF 格式儲存文件時，文件中影像的 DPI 會不正確的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1661">We fixed an issue where images in a document saved as a PDF would have the incorrect DPI</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-1662">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-1662">Excel</span></span>
- <span data-ttu-id="9c296-1663">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1663">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-1664">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-1664">PowerPoint</span></span>
- <span data-ttu-id="9c296-1665">我們已修正註解窗格無法正確開啟或關閉的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1665">We fixed an issue where the comments pane would not open or close properly</span></span>
- <span data-ttu-id="9c296-1666">我們已修正應用程式會在刪除影片時當機的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1666">We fixed an issue where the application could crash when deleting a video</span></span>
- <span data-ttu-id="9c296-1667">我們已修正於某些情況下應用程式會無法啟動的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1667">We fixed an issue where in some instances the application would fail to launch</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-1668">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-1668">Outlook</span></span>
- <span data-ttu-id="9c296-1669">我們已修正以日文檢視時讀信回條不正確的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1669">We fixed an issue where read receipts were incorrect when viewed in Japanese</span></span>

### <a name="access"></a><span data-ttu-id="9c296-1670">Access</span><span class="sxs-lookup"><span data-stu-id="9c296-1670">Access</span></span>
- <span data-ttu-id="9c296-1671">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1671">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9c296-1672">Project</span><span class="sxs-lookup"><span data-stu-id="9c296-1672">Project</span></span>
- <span data-ttu-id="9c296-1673">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1673">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-8-2019"></a><span data-ttu-id="9c296-1674">2019 年 3 月 8 日</span><span class="sxs-lookup"><span data-stu-id="9c296-1674">March 8, 2019</span></span> 
<span data-ttu-id="9c296-1675">版本 1903 (組建 11425.20036)</span><span class="sxs-lookup"><span data-stu-id="9c296-1675">Version 1903 (build 11425.20036)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9c296-1676">新功能：</span><span class="sxs-lookup"><span data-stu-id="9c296-1676">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="9c296-1677">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-1677">Word</span></span>

### <a name="find-what-youre-looking-for-with-microsoft-search"></a><span data-ttu-id="9c296-1678">使用 Microsoft Search 尋找您要的內容</span><span class="sxs-lookup"><span data-stu-id="9c296-1678">Find What You're Looking For with Microsoft Search</span></span>

<span data-ttu-id="9c296-1679">您可以使用 Microsoft Search 找到所有檔案、動作、人員，協助您完成工作所需。</span><span class="sxs-lookup"><span data-stu-id="9c296-1679">With Microsoft Search, you can find all the files, actions, people, and help you need to get work done.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="9c296-1680">開始使用：</span><span class="sxs-lookup"><span data-stu-id="9c296-1680">Getting Started:</span></span>

- <span data-ttu-id="9c296-1681">這個功能在標題中的 UI 上方強調顯示。</span><span class="sxs-lookup"><span data-stu-id="9c296-1681">The feature is prominently displayed on top of the UI in the header.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="9c296-1682">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="9c296-1682">Scenarios to Try:</span></span>

- <span data-ttu-id="9c296-1683">搜尋某間大學、最近使用過的文件或搜尋最常用的功能區命令</span><span class="sxs-lookup"><span data-stu-id="9c296-1683">Search for a college, a recent document or search for the ribbon commands you use most often</span></span>
- <span data-ttu-id="9c296-1684">尋找某個主題或主旨並取得更多相關資訊</span><span class="sxs-lookup"><span data-stu-id="9c296-1684">Look up a topic or subject to get more information on it</span></span>
- 
#### <a name="coauthoring"></a><span data-ttu-id="9c296-1685">共同撰寫</span><span class="sxs-lookup"><span data-stu-id="9c296-1685">CoAuthoring</span></span>

<span data-ttu-id="9c296-1686">厭倦於被包含巨集的文件阻礙了嗎？</span><span class="sxs-lookup"><span data-stu-id="9c296-1686">Tired of being locked out of your document with macros?</span></span> <span data-ttu-id="9c296-1687">現在商務用 OneDrive 的 docm 檔案允許同時由多個作者編輯。</span><span class="sxs-lookup"><span data-stu-id="9c296-1687">Now your docm files on OneDrive for Business allow simultaneous editing by multiple authors.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="9c296-1688">開始使用：</span><span class="sxs-lookup"><span data-stu-id="9c296-1688">Getting Started:</span></span>

<span data-ttu-id="9c296-1689">使用者在 UI 中不需要按下任何按鈕，就能存取這項功能。</span><span class="sxs-lookup"><span data-stu-id="9c296-1689">The user doesn't need to press any buttons in the UI to access this feature.</span></span> <span data-ttu-id="9c296-1690">商務用 OneDrive 的 docm 檔案預設已啟用此功能。</span><span class="sxs-lookup"><span data-stu-id="9c296-1690">It is enabled by default on OneDrive for Business docm files.</span></span>
<span data-ttu-id="9c296-1691">因此，使用者應該將 docm 檔案儲存至商務用 OneDrive 試用看看。</span><span class="sxs-lookup"><span data-stu-id="9c296-1691">So, the user should save a docm file to OneDrive for Business to try it out.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="9c296-1692">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="9c296-1692">Scenarios to Try:</span></span>

<span data-ttu-id="9c296-1693">在商務用 OneDrive 建立 docm 檔案、與同事共用並且共同作業！</span><span class="sxs-lookup"><span data-stu-id="9c296-1693">Create a docm file on OneDrive for Business, share it with your colleagues, and collaborate!</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9c296-1694">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="9c296-1694">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="9c296-1695">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-1695">Word</span></span> 
- <span data-ttu-id="9c296-1696">我們已修正在 [選項] 中按下 ESC 鍵時發生的當機問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1696">We fixed a crashing issue that occurred when pressing 'ESC' while in Options</span></span>
- <span data-ttu-id="9c296-1697">我們已修正回覆註解時發生的當機問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1697">We fixed a crashing issue that occurred when replying to comments</span></span>
- <span data-ttu-id="9c296-1698">我們已修正從 Word 到 PowerPoint Online 的複製與貼上問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1698">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-1699">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-1699">Excel</span></span>
- <span data-ttu-id="9c296-1700">我們已修正當受保護的文件和可編輯的文件在開啟時複製 Excel 儲存格導致高 CPU 使用率的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1700">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-1701">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-1701">PowerPoint</span></span>
- <span data-ttu-id="9c296-1702">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1702">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-1703">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-1703">Outlook</span></span>
- <span data-ttu-id="9c296-1704">我們已修正 Outlook 搜尋未依所選時間順序排序的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1704">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="9c296-1705">我們已修正 [開啟此工作] 工作流程功能區按鈕無法回應特定電子郵件的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1705">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="9c296-1706">我們已修正使用者在 [會議室尋找工具] 中選取可用的會議室後，Outlook 無法清除內部部署會議室的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1706">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="9c296-1707">Access</span><span class="sxs-lookup"><span data-stu-id="9c296-1707">Access</span></span>
- <span data-ttu-id="9c296-1708">我們已修正已儲存的匯入/匯出對話方塊在深色佈景主題中有白色文字在白色背景的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1708">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="9c296-1709">我們已修正使用者在表格設計中無法針對 [文字方塊] 的 [是/否] 欄位設定 DisplayControl 屬性的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1709">We fixed an issue where users could not set the DisplayControl property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="9c296-1710">Project</span><span class="sxs-lookup"><span data-stu-id="9c296-1710">Project</span></span>
- <span data-ttu-id="9c296-1711">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1711">Various performance and stability fixes</span></span>


## <a name="march-1-2019"></a><span data-ttu-id="9c296-1712">2019 年 3 月 1 日</span><span class="sxs-lookup"><span data-stu-id="9c296-1712">March 1, 2019</span></span> 
<span data-ttu-id="9c296-1713">版本 1903 (組建 11414.20014)</span><span class="sxs-lookup"><span data-stu-id="9c296-1713">Version 1903 (build 11414.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9c296-1714">新功能</span><span class="sxs-lookup"><span data-stu-id="9c296-1714">What's New</span></span>

### <a name="word"></a><span data-ttu-id="9c296-1715">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-1715">Word</span></span>

#### <a name="colors-for-track-changes-comments-and-real-time-collaboration-in-sync"></a><span data-ttu-id="9c296-1716">追蹤修訂、註解和即時共同作業的色彩會同步</span><span class="sxs-lookup"><span data-stu-id="9c296-1716">Colors for Track Changes, Comments and Real-Time Collaboration in Sync</span></span>

<span data-ttu-id="9c296-1717">我們產品中的修正現在可確保註解、追蹤修訂及共同作業者的游標會以相同色彩顯示。</span><span class="sxs-lookup"><span data-stu-id="9c296-1717">Fixes in our product now ensure that the comments, track changes and the cursor for a collaborator show up in the same color.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="9c296-1718">開始使用：</span><span class="sxs-lookup"><span data-stu-id="9c296-1718">Getting Started:</span></span>

<span data-ttu-id="9c296-1719">開啟其他人已開啟的 SharePoint 或 OneDrive 文件。</span><span class="sxs-lookup"><span data-stu-id="9c296-1719">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="9c296-1720">確認使用者的追蹤修訂和註解色彩符合該使用者游標的色彩。</span><span class="sxs-lookup"><span data-stu-id="9c296-1720">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="9c296-1721">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="9c296-1721">Scenarios to Try:</span></span>

<span data-ttu-id="9c296-1722">開啟其他人已開啟的 SharePoint 或 OneDrive 文件。</span><span class="sxs-lookup"><span data-stu-id="9c296-1722">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="9c296-1723">確認使用者的追蹤修訂和註解色彩符合該使用者游標的色彩。</span><span class="sxs-lookup"><span data-stu-id="9c296-1723">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9c296-1724">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="9c296-1724">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="9c296-1725">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-1725">Word</span></span> 
- <span data-ttu-id="9c296-1726">我們已修正在 [選項] 中按下 ESC 鍵時發生的當機問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1726">We fixed a crashing issue that occurred when pressing 'ESC' while in Options</span></span>
- <span data-ttu-id="9c296-1727">我們已修正從 Word 到 PowerPoint Online 的複製與貼上問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1727">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-1728">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-1728">Excel</span></span>
- <span data-ttu-id="9c296-1729">我們已修正當受保護的文件和可編輯的文件在開啟時複製 Excel 儲存格導致高 CPU 使用率的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1729">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-1730">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-1730">PowerPoint</span></span>
- <span data-ttu-id="9c296-1731">我們已修正在 PowerPoint 中使用 @提及的投影片圖像大小問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1731">We fixed an issue with slide image size when using @Mentions in PowerPoint</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-1732">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-1732">Outlook</span></span>
- <span data-ttu-id="9c296-1733">我們已修正 Outlook 搜尋未依所選時間順序排序的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1733">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="9c296-1734">我們已修正 [開啟此工作] 工作流程功能區按鈕無法回應特定電子郵件的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1734">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="9c296-1735">我們已修正使用者在 [會議室尋找工具] 中選取可用的會議室後，Outlook 無法清除內部部署會議室的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1735">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="9c296-1736">Access</span><span class="sxs-lookup"><span data-stu-id="9c296-1736">Access</span></span>
- <span data-ttu-id="9c296-1737">我們已更新確認使用資料來源重新連結資料表時顯示的提示文字</span><span class="sxs-lookup"><span data-stu-id="9c296-1737">We updated the prompt text that showed when confirming the relinking tables with a datasource</span></span>
- <span data-ttu-id="9c296-1738">我們已修正已儲存的匯入/匯出對話方塊在深色佈景主題中有白色文字在白色背景的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1738">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="9c296-1739">我們已修正使用者在表格設計中無法針對 [文字方塊] 的 [是/否] 欄位設定 [顯示控制項] 屬性的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1739">We fixed an issue where users could not set the Display Control property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="9c296-1740">Project</span><span class="sxs-lookup"><span data-stu-id="9c296-1740">Project</span></span>
- <span data-ttu-id="9c296-1741">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1741">Various performance and stability fixes</span></span>

</BR></BR>



## <a name="february-15-2019"></a><span data-ttu-id="9c296-1742">2019 年 2 月 15 日</span><span class="sxs-lookup"><span data-stu-id="9c296-1742">February 15, 2019</span></span> 
<span data-ttu-id="9c296-1743">版本 1903 (組建 11310.20016)</span><span class="sxs-lookup"><span data-stu-id="9c296-1743">Version 1903 (build 11310.20016)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9c296-1744">新功能：</span><span class="sxs-lookup"><span data-stu-id="9c296-1744">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-1745">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-1745">PowerPoint</span></span>


### <a name="morph-transition-enhancements---morph-by-name"></a><span data-ttu-id="9c296-1746">轉化轉場增強效果 - 依名稱轉化</span><span class="sxs-lookup"><span data-stu-id="9c296-1746">Morph Transition Enhancements - Morph by Name</span></span>

<span data-ttu-id="9c296-1747">選取要轉化的圖形</span><span class="sxs-lookup"><span data-stu-id="9c296-1747">Specify the shapes you want to morph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="9c296-1748">開始使用：</span><span class="sxs-lookup"><span data-stu-id="9c296-1748">Getting Started:</span></span>

- <span data-ttu-id="9c296-1749">若要使轉化將兩個物件視為同一個物件，使用者可以使用 [選取窗格] 重新命名圖形。</span><span class="sxs-lookup"><span data-stu-id="9c296-1749">To get Morph to treat two objects as the same object, the user can rename the shapes using the Selection Pane.</span></span>
- <span data-ttu-id="9c296-1750">名稱前面必須加上「!!」</span><span class="sxs-lookup"><span data-stu-id="9c296-1750">The name must be prefaced with "!!"</span></span> <span data-ttu-id="9c296-1751">(兩個半形驚嘆號)，轉化才能用來覆寫預設比對行為，例如「!!名稱」</span><span class="sxs-lookup"><span data-stu-id="9c296-1751">(two exclamation points) for Morph to use it to override our default matching behavior, e.g. "!!Name"</span></span>
- <span data-ttu-id="9c296-1752">使用者可以繼續將圖形重新命名為不是以「!!」為開頭的任何名稱</span><span class="sxs-lookup"><span data-stu-id="9c296-1752">Users can continue to rename shapes with any name that doesn't start with "!!"</span></span> <span data-ttu-id="9c296-1753">不必擔心會變更轉化的運作方式</span><span class="sxs-lookup"><span data-stu-id="9c296-1753">without worrying that it will change the way Morph works</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="9c296-1754">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="9c296-1754">Scenarios to Try:</span></span>

- <span data-ttu-id="9c296-1755">在投影片中插入圖形，讓我們假設是矩形</span><span class="sxs-lookup"><span data-stu-id="9c296-1755">Insert a Shape in a slide, let's say Rectangle</span></span>
- <span data-ttu-id="9c296-1756">建立新投影片</span><span class="sxs-lookup"><span data-stu-id="9c296-1756">Create a new slide</span></span>
- <span data-ttu-id="9c296-1757">在第 2 張投影片中插入不同的圖形，讓我們假設是三角形</span><span class="sxs-lookup"><span data-stu-id="9c296-1757">Insert a different shape in the 2nd slide, let's say Triangle</span></span>
- <span data-ttu-id="9c296-1758">開啟 [選取窗格]，將投影片 1 中的矩形重新命名為「!!圖形」，將投影片 2 中的三角形重新命名為「!!圖形」</span><span class="sxs-lookup"><span data-stu-id="9c296-1758">Open SelectionPane, rename the Rectangle in slide 1 to "!!shape", and rename the Triangle in slide 2 to "!!shape"</span></span>
- <span data-ttu-id="9c296-1759">將 [轉化] 套用至第 2 張投影片</span><span class="sxs-lookup"><span data-stu-id="9c296-1759">Apply Morph on the 2nd slide</span></span>

</BR>

### <a name="morph-transition-enhancements---smartart"></a><span data-ttu-id="9c296-1760">轉化轉場增強效果 - SmartArt</span><span class="sxs-lookup"><span data-stu-id="9c296-1760">Morph Transition Enhancements - SmartArt</span></span>

<span data-ttu-id="9c296-1761">轉場更順暢的 SmartArt 轉化</span><span class="sxs-lookup"><span data-stu-id="9c296-1761">SmartArt morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="9c296-1762">開始使用：</span><span class="sxs-lookup"><span data-stu-id="9c296-1762">Getting Started:</span></span>

<span data-ttu-id="9c296-1763">您使用 SmartArt 的方式與轉化相同</span><span class="sxs-lookup"><span data-stu-id="9c296-1763">Use Morph the same way you would with SmartArt</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="9c296-1764">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="9c296-1764">Scenarios to Try:</span></span>

- <span data-ttu-id="9c296-1765">在投影片中插入 SmartArt</span><span class="sxs-lookup"><span data-stu-id="9c296-1765">Insert a SmartArt in a slide</span></span>
- <span data-ttu-id="9c296-1766">複製投影片</span><span class="sxs-lookup"><span data-stu-id="9c296-1766">Duplicate the Slide</span></span>
- <span data-ttu-id="9c296-1767">在複製的投影片上調整大小/變更/移動 SmartArt</span><span class="sxs-lookup"><span data-stu-id="9c296-1767">Resize/Change/Move the SmartArt on the duplicated slide</span></span>
- <span data-ttu-id="9c296-1768">在複製的投影片上套用 [轉化]</span><span class="sxs-lookup"><span data-stu-id="9c296-1768">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="morph-transition-enhancements---tables"></a><span data-ttu-id="9c296-1769">轉化轉場增強效果 - 表格​​</span><span class="sxs-lookup"><span data-stu-id="9c296-1769">Morph Transition Enhancements - Tables</span></span>

<span data-ttu-id="9c296-1770">轉場更順暢的表格轉化</span><span class="sxs-lookup"><span data-stu-id="9c296-1770">Tables morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="9c296-1771">開始使用：</span><span class="sxs-lookup"><span data-stu-id="9c296-1771">Getting Started:</span></span>
<span data-ttu-id="9c296-1772">您使用表格的方式與轉化相同</span><span class="sxs-lookup"><span data-stu-id="9c296-1772">Use Morph the same way you would with tables</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="9c296-1773">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="9c296-1773">Scenarios to Try:</span></span>

- <span data-ttu-id="9c296-1774">在投影片中插入表格</span><span class="sxs-lookup"><span data-stu-id="9c296-1774">Insert a Table in a slide</span></span>
- <span data-ttu-id="9c296-1775">複製投影片</span><span class="sxs-lookup"><span data-stu-id="9c296-1775">Duplicate the slide</span></span>
- <span data-ttu-id="9c296-1776">在複製的投影片上調整大小/變更/移動表格</span><span class="sxs-lookup"><span data-stu-id="9c296-1776">Resize/Change/Move the Table on the duplicated slide</span></span>
- <span data-ttu-id="9c296-1777">在複製的投影片上套用 [轉化]</span><span class="sxs-lookup"><span data-stu-id="9c296-1777">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a><span data-ttu-id="9c296-1778">Word、Excel、PowerPoint、OneNote、Access、Project、Publisher 和 Visio</span><span class="sxs-lookup"><span data-stu-id="9c296-1778">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span></span>

### <a name="seamlessly-switch-between-accounts"></a><span data-ttu-id="9c296-1779">在不同帳戶之間順暢切換</span><span class="sxs-lookup"><span data-stu-id="9c296-1779">Seamlessly Switch Between Accounts</span></span>

<span data-ttu-id="9c296-1780">全新的帳戶管理員會在同一個地方顯示您所有的工作和個人帳戶，讓您能控制在其間切換。</span><span class="sxs-lookup"><span data-stu-id="9c296-1780">The new account manager shows all of your work and personal accounts in one place, and puts you in control of switching between them.</span></span> <span data-ttu-id="9c296-1781">這項更新的經驗能清楚知道您的登入方法，因此您現在不需要先登出或處理複雜的對話方塊就可以切換工作和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="9c296-1781">This updated experience makes it clear how you're logged in, and now you can toggle between work and personal accounts without having to sign out first or deal with complex dialogs.</span></span>


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a><span data-ttu-id="9c296-1783">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="9c296-1783">Scenarios to Try:</span></span>
- <span data-ttu-id="9c296-1784">在不同的帳戶之間切換</span><span class="sxs-lookup"><span data-stu-id="9c296-1784">Switch between accounts</span></span>
- <span data-ttu-id="9c296-1785">新增帳戶 [附註：您可能想要先移至 [檔案] | [帳戶] | [已連線服務]，移除任何已連線至工作帳戶的個人服務或是反向服務]</span><span class="sxs-lookup"><span data-stu-id="9c296-1785">Add a new account [Note: you may want to first go to File | Account | Connected Services and remove any personal services connected to work accounts or vice versa]</span></span>
- <span data-ttu-id="9c296-1786">登出帳戶</span><span class="sxs-lookup"><span data-stu-id="9c296-1786">Sign out from an account</span></span>
</BR>

## <a name="notable-fixes"></a><span data-ttu-id="9c296-1787">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="9c296-1787">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="9c296-1788">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-1788">Word</span></span> 
- <span data-ttu-id="9c296-1789">我們已修正表格和影像的內容預覽問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1789">We fixed an issue with context preview for tables & images</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-1790">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-1790">Excel</span></span>
- <span data-ttu-id="9c296-1791">我們已修正在黑色佈景主題中，自動篩選的搜尋欄位中文字是白色的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1791">We fixed an issue where text in autofilter Search field is white in Black theme</span></span>
- <span data-ttu-id="9c296-1792">我們已修正新 Office 增益集的同意 UI 問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1792">We fixed a consent UI issue with New Office Add-in</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-1793">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-1793">PowerPoint</span></span>
- <span data-ttu-id="9c296-1794">我們已修正在膝上型電腦或平板電腦上進行投影片簡報時自動延伸顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="9c296-1794">We fixed an issue with automatically extending display when presenting SlideShows on laptops or tablets.</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-1795">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-1795">Outlook</span></span>
- <span data-ttu-id="9c296-1796">我們已修正 [傳送至 OneNote] 按鈕的顯示問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1796">We fixed an issue with the Send to OneNote button display</span></span>

### <a name="access"></a><span data-ttu-id="9c296-1797">Access</span><span class="sxs-lookup"><span data-stu-id="9c296-1797">Access</span></span>
- <span data-ttu-id="9c296-1798">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1798">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9c296-1799">Project</span><span class="sxs-lookup"><span data-stu-id="9c296-1799">Project</span></span>
- <span data-ttu-id="9c296-1800">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1800">Various performance and stability fixes</span></span>


</BR></BR>
## <a name="february-11-2019"></a><span data-ttu-id="9c296-1801">2019 年 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="9c296-1801">February 11, 2019</span></span>
<span data-ttu-id="9c296-1802">版本 1903 (組建 11330.20014)</span><span class="sxs-lookup"><span data-stu-id="9c296-1802">Version 1903 (build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="9c296-1803">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="9c296-1803">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="9c296-1804">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-1804">Word</span></span> 
- <span data-ttu-id="9c296-1805">我們已修正某些自訂樣式無法套用至線上 Word 的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1805">We fixed an issue where some customized styles could not be applied to word online</span></span>
- <span data-ttu-id="9c296-1806">我們已修正 Word 中豐富物件的內容預覽問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1806">We fixed Context Preview issues with rich objects in Word</span></span>
- <span data-ttu-id="9c296-1807">我們已修正貼上清單會導致 Word 當機的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1807">We fixed an issue where pasting lists  would result in Word crashing</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-1808">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-1808">Excel</span></span>
- <span data-ttu-id="9c296-1809">我們已修正無貨幣符號時，數字格式後的附加空白不再顯示的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1809">We fixed an issue where appended spaces after number formats are no longer showing when there is no currency symbol</span></span>
- <span data-ttu-id="9c296-1810">我們已修正自動偵測股票的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1810">We fixed an issue with auto detect for stocks</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-1811">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-1811">PowerPoint</span></span>
- <span data-ttu-id="9c296-1812">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1812">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-1813">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-1813">Outlook</span></span>
- <span data-ttu-id="9c296-1814">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1814">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="9c296-1815">Access</span><span class="sxs-lookup"><span data-stu-id="9c296-1815">Access</span></span>
- <span data-ttu-id="9c296-1816">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1816">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9c296-1817">Project</span><span class="sxs-lookup"><span data-stu-id="9c296-1817">Project</span></span>
- <span data-ttu-id="9c296-1818">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1818">Various performance and stability fixes</span></span>

</BR></BR>


## <a name="february-1-2019"></a><span data-ttu-id="9c296-1819">2019 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="9c296-1819">February 1, 2019</span></span> 
<span data-ttu-id="9c296-1820">版本 1902 (組建 11326.20000)</span><span class="sxs-lookup"><span data-stu-id="9c296-1820">Version 1902 (build 11326.20000)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="9c296-1821">值得注意的修正</span><span class="sxs-lookup"><span data-stu-id="9c296-1821">Notable Fixes</span></span>

### <a name="word"></a><span data-ttu-id="9c296-1822">Word</span><span class="sxs-lookup"><span data-stu-id="9c296-1822">Word</span></span> 
- <span data-ttu-id="9c296-1823">我們已修正內嵌 Excel 表格中調整儲存格大小的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1823">We fixed an issue with resizing cells in an embedded Excel table</span></span>
- <span data-ttu-id="9c296-1824">我們已修正繪圖畫布中複製/貼上圖形的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1824">We fixed an issue with copy/paste of shapes in a Drawing Canvas</span></span>

### <a name="excel"></a><span data-ttu-id="9c296-1825">Excel</span><span class="sxs-lookup"><span data-stu-id="9c296-1825">Excel</span></span>
- <span data-ttu-id="9c296-1826">我們已修正從 Excel Web App 開啟檔案的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1826">We fixed an issue with opening files from the Excel Web app</span></span>
- <span data-ttu-id="9c296-1827">我們已修正因為檔名大小造成 CSV 檔案儲存為 XLSX 失敗的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1827">We fixed an issue where saving a CSV file as .XLSX was failing due to file name size</span></span>
- <span data-ttu-id="9c296-1828">我們已修正快顯功能表顯示快顯功能表選項的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1828">We fixed the context menu to display the context menu options</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c296-1829">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c296-1829">PowerPoint</span></span>
- <span data-ttu-id="9c296-1830">我們已修正使用者無法使用鍵盤快速鍵 ctrl+alt+7/ctrl+alt+8 輸入方括號的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1830">We fixed an issued where users were unable to use the keyboard shortcut ctrl+alt+7/ctrl+alt+8 to enter square brackets</span></span>
- <span data-ttu-id="9c296-1831">我們已修正將本機影片插入至 PPT 會減少 'C' 磁碟機磁碟空間的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1831">We fixed an issue where inserting a local video into the PPT would reduce the 'C' drive disk space</span></span>
- <span data-ttu-id="9c296-1832">我們已修正 [發佈至 Microsoft Stream] 按鈕無法向某些使用者顯示的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1832">We fixed the Publish to Microsoft Stream button which was not displaying to some users</span></span>

### <a name="outlook"></a><span data-ttu-id="9c296-1833">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c296-1833">Outlook</span></span>
- <span data-ttu-id="9c296-1834">我們已修正行事曆中工作檢視無法正確顯示工作主旨的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1834">We fixed an issue where the task view in calendar was  not correctly showing the task subject</span></span>

### <a name="access"></a><span data-ttu-id="9c296-1835">Access</span><span class="sxs-lookup"><span data-stu-id="9c296-1835">Access</span></span>
- <span data-ttu-id="9c296-1836">我們已修正圖表的縮放比例的問題</span><span class="sxs-lookup"><span data-stu-id="9c296-1836">We fixed a scaling issue with charts</span></span>

### <a name="project"></a><span data-ttu-id="9c296-1837">Project</span><span class="sxs-lookup"><span data-stu-id="9c296-1837">Project</span></span>
- <span data-ttu-id="9c296-1838">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="9c296-1838">Various performance and stability fixes</span></span>
