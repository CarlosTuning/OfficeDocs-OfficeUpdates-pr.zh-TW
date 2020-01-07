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
ms.openlocfilehash: b136c43128f6f995057f35c7b47c9e517c457097
ms.sourcegitcommit: 78fb0c27e6b75aefcfcbd1b0ac7d17c1b53f86e0
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 01/07/2020
ms.locfileid: "40951091"
---
# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="99c53-103">Office 測試人員的版本資訊</span><span class="sxs-lookup"><span data-stu-id="99c53-103">Release Notes for Office Insiders</span></span>

<span data-ttu-id="99c53-104">本文包含 Windows 電腦版 Word、Excel、PowerPoint、Outlook、Access 和 Project 測試人員組建的版本資訊。</span><span class="sxs-lookup"><span data-stu-id="99c53-104">This article contains release notes for Insider builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="99c53-105">我們每週都強調有趣的新功能、重要修正，以及我們想讓您知道的重大問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="99c53-106">請注意，我們在一段時間內會經常推出新功能 (某些時候還有修正) 給測試人員。</span><span class="sxs-lookup"><span data-stu-id="99c53-106">Note that we often roll out features (and sometimes even fixes) to Insiders over a period of time.</span></span> <span data-ttu-id="99c53-107">這樣可讓我們確保功能都運作順利，然後才推出給更廣泛的對象。</span><span class="sxs-lookup"><span data-stu-id="99c53-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="99c53-108">所以，如果你沒有看到下面描述的項目，不要擔心你最終會得到它。</span><span class="sxs-lookup"><span data-stu-id="99c53-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!NOTE]
> - <span data-ttu-id="99c53-109">版本資訊會每週發佈，可能是多個組建的編譯。</span><span class="sxs-lookup"><span data-stu-id="99c53-109">Release notes are posted weekly and may be a compilation of multiple builds.</span></span>
> - <span data-ttu-id="99c53-110">版本資訊發佈日期可能與實際組建發行日期不相符。</span><span class="sxs-lookup"><span data-stu-id="99c53-110">The release notes publication date may not match the actual build release date.</span></span>
> - <span data-ttu-id="99c53-111">現有 Office 365 專業增強版安裝上的 Microsoft Teams - 從 6 月底開始，Microsoft Teams 將在更新這些安裝時，新增至 Office 365 專業增強版的 (和 Office 365 商務版) 的現有安裝中。</span><span class="sxs-lookup"><span data-stu-id="99c53-111">Microsoft Teams on existing installations of Office 365 ProPlus - Beginning in late June, Microsoft Teams will be included in existing installations of Office 365 ProPlus (and Office 365 Business) upon updates of these installations.</span></span> <span data-ttu-id="99c53-112">新增 Teams 的日期取決於您使用的更新通道。</span><span class="sxs-lookup"><span data-stu-id="99c53-112">The date when Teams will be added depends on which update channel you're using.</span></span> <span data-ttu-id="99c53-113">如需詳細資訊，請參閱[隨著 Office 365 專業增強版部署 Microsoft Teams](https://docs.microsoft.com/deployoffice/teams-install)。</span><span class="sxs-lookup"><span data-stu-id="99c53-113">Please refer to [Deploy Microsoft Teams with Office 365 ProPlus](https://docs.microsoft.com/deployoffice/teams-install) for additional information.</span></span>

[//]: # (DO NOT REMOVE)

## <a name="version-2001-january-03"></a><span data-ttu-id="99c53-115">版本 2001：1 月 3 日</span><span class="sxs-lookup"><span data-stu-id="99c53-115">Version 2001: January 03</span></span>
<span data-ttu-id="99c53-116">*版本 2001 (組建 12425.20000)*</span><span class="sxs-lookup"><span data-stu-id="99c53-116">*Version 2001 (Build 12425.20000)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="99c53-118">解決的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-118">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="99c53-119">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-119">Excel</span></span>
- <span data-ttu-id="99c53-120">有些框線在 A4 大小的紙張上可能無法如預期列印。</span><span class="sxs-lookup"><span data-stu-id="99c53-120">Some border lines may not print as expected on A4 size paper.</span></span>
- <span data-ttu-id="99c53-121">使用 VBA 將影像新增到工作表圖表物件的頁首/頁尾可能會導致錯誤。</span><span class="sxs-lookup"><span data-stu-id="99c53-121">Adding an image to the header/footer of a chart object on a sheet using VBA may result in an error.</span></span>
- <span data-ttu-id="99c53-122">設定圖表座標軸格式時，標籤之間的間隔限制為 255。</span><span class="sxs-lookup"><span data-stu-id="99c53-122">When formatting a chart axis, the interval between labels was limited to 255.</span></span>
- <span data-ttu-id="99c53-123">已修正嘗試重新整理 XML 查詢 (資料來源 URL 遭截斷) 時發生錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-123">Fixed an issue where an error would occur trying to refresh an XML query in which the URL to the datasource was being truncated.</span></span>
- <span data-ttu-id="99c53-124">活頁簿統計資料會報告所有開啟的活頁簿 (包括個人巨集活頁簿) 中的巨集計數。</span><span class="sxs-lookup"><span data-stu-id="99c53-124">Workbook Statistics would report a macro count from all open workbooks, including the personal macro workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="99c53-125">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-125">Outlook</span></span>
- <span data-ttu-id="99c53-126">切換資料夾可能會導致郵件清單/郵件預覽中「快閃」短暫的空白。</span><span class="sxs-lookup"><span data-stu-id="99c53-126">Switching folders may result in a brief white 'flash' in the mail list / mail preview.</span></span> <span data-ttu-id="99c53-127">此行為在深色模式中更明顯。</span><span class="sxs-lookup"><span data-stu-id="99c53-127">This behavior was more pronounced in dark mode.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="99c53-128">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-128">PowerPoint</span></span>
- <span data-ttu-id="99c53-129">已修正呼叫 Shape.Paste 方法會導致貼上的圖形置於焦點下的物件模型問題。&nbsp;</span><span class="sxs-lookup"><span data-stu-id="99c53-129">Fixed an Object Model issue where calling Shape.Paste method would result in the pasted shape receiving focus.&nbsp;</span></span>
- <span data-ttu-id="99c53-130">已改善複製貼上案例：&nbsp;以程式設計方式從 PowerPoint 投影片複製圖形，並將其貼到循環播放中的另一張投影片會失敗並發生異常錯誤。&nbsp;</span><span class="sxs-lookup"><span data-stu-id="99c53-130">Improved a copy-paste scenario:&nbsp;Progamatically copying a shape from a PowerPoint slide and pasting it to another slide in a loop could fail with an exception error.&nbsp;</span></span>
- <span data-ttu-id="99c53-131">折疊及展開節標頭後，投影片節標頭的動畫無法正確呈現。</span><span class="sxs-lookup"><span data-stu-id="99c53-131">Animation in the section headers of slides would not render properly after collapsing and expanding section headers.</span></span>

### <a name="project"></a><span data-ttu-id="99c53-132">Project</span><span class="sxs-lookup"><span data-stu-id="99c53-132">Project</span></span>
- <span data-ttu-id="99c53-133">已修正文字換行在任務和資源使用狀況檢視中無法正常運作的問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-133">Fixed an issue where text wrapping wasn't working in the task and resource usage views.</span></span>
- <span data-ttu-id="99c53-134">已修正如果某資源有多個成本比率，則工作分派的成本值可能不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-134">Fixed an issue where if a resource has more than one cost rate, cost value on assignments may not be correct.</span></span>

### <a name="word"></a><span data-ttu-id="99c53-135">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-135">Word</span></span>
- <span data-ttu-id="99c53-136">在方程式中插入控制項 (例如文字內容控制項)，然後儲存再開啟檔案，便會導致內容無法讀取的錯誤。</span><span class="sxs-lookup"><span data-stu-id="99c53-136">Inserting a control (such as a Text Content Control) in an equation, then saving and opening the file would result in an un-readable content error.</span></span>
- <span data-ttu-id="99c53-137">共同撰寫時，Word 電腦版可能不會顯示使用 Word Online 新增註解的功能。</span><span class="sxs-lookup"><span data-stu-id="99c53-137">When co-authoring, adding a comment using Word online may not appear in Word desktop.</span></span>

### <a name="office-suite"></a><span data-ttu-id="99c53-138">Office 套件</span><span class="sxs-lookup"><span data-stu-id="99c53-138">Office Suite</span></span>
- <span data-ttu-id="99c53-139">嘗試在只有一個授權的情況下變更授權時，不再顯示有效授權的錯誤到期日。</span><span class="sxs-lookup"><span data-stu-id="99c53-139">Removed showing an erroneous expiry date of the valid license when trying to change license with only one license.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2001-december-13"></a><span data-ttu-id="99c53-141">版本 2001：12 月 13 日</span><span class="sxs-lookup"><span data-stu-id="99c53-141">Version 2001: December 13</span></span>
<span data-ttu-id="99c53-142">*版本 2001 (組建 12410.20000)*</span><span class="sxs-lookup"><span data-stu-id="99c53-142">*Version 2001 (Build 12410.20000)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="99c53-144">功能更新</span><span class="sxs-lookup"><span data-stu-id="99c53-144">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="99c53-145">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-145">Outlook</span></span>

- <span data-ttu-id="99c53-146">**將電子郵件拖曳到您擁有的群組：** 從您的 [收件匣] 拖曳郵件和交談以將它們移動和複製。</span><span class="sxs-lookup"><span data-stu-id="99c53-146">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="99c53-147">您拖曳的郵件將會與所有群組成員共用。</span><span class="sxs-lookup"><span data-stu-id="99c53-147">Messages you drag will be shared with all group members.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="99c53-150">解決的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-150">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="99c53-151">Access</span><span class="sxs-lookup"><span data-stu-id="99c53-151">Access</span></span>
- <span data-ttu-id="99c53-152">執行可參考連結之 ODBC 資料表且包含 Order By 子句的聯集查詢，會導致 64 位元 Access 當機。</span><span class="sxs-lookup"><span data-stu-id="99c53-152">Executing a union query that references linked ODBC table(s) and contains an Order By clause crashes 64 bit Access.</span></span>
- <span data-ttu-id="99c53-153">Access (O365) 中由聯集查詢的資料匯合可能會導致小數資料的截斷。</span><span class="sxs-lookup"><span data-stu-id="99c53-153">Summing of data from union queries in Access (O365) may result in truncation of decimal data.</span></span>
- <span data-ttu-id="99c53-154">ACE 的 COM 介面並未公開於 Office 應用程式的外部使用。</span><span class="sxs-lookup"><span data-stu-id="99c53-154">COM Interfaces for ACE are not exposed for use outside of Office applications.</span></span>

### <a name="excel"></a><span data-ttu-id="99c53-155">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-155">Excel</span></span>
- <span data-ttu-id="99c53-156">無法執行插入3D 模型 (動態或靜態)，且嘗試 [另存成圖片]。</span><span class="sxs-lookup"><span data-stu-id="99c53-156">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>
- <span data-ttu-id="99c53-157">從 Backstage 啟動意見反應的 Shortkey (Alt+Ctrl + 7/8) 與 AZERTY 鍵盤 (Alt-Gr + 7/8) 有衝突。</span><span class="sxs-lookup"><span data-stu-id="99c53-157">The shortkey (Alt+Ctrl + 7/8)  to launch feedback from backstage is in conflict with AZERTY keyboards (Alt-Gr + 7/8).</span></span> <span data-ttu-id="99c53-158">影響：使用者可能無法使用下列字元，例如：'\'。</span><span class="sxs-lookup"><span data-stu-id="99c53-158">Impact: users may not be able to use some characters such as: '\'.</span></span>

### <a name="outlook"></a><span data-ttu-id="99c53-159">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-159">Outlook</span></span>
- <span data-ttu-id="99c53-160">解決導致電子郵件傳送到收件者錯誤地址的問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-160">Addresses an issue that caused email to be sent to the wrong address for the recipient.</span></span>
- <span data-ttu-id="99c53-161">解決了導致 Outlook 不正確地允許使用者具有信箱的 &quot;[讀取]&quot; 存取權，而變更郵件之讀取/未讀取狀態的問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-161">Addresses an issue that caused Outlook to incorrectly allow users with &quot;read&quot; access to a mailbox to change the read/unread state of a message.</span></span>
- <span data-ttu-id="99c53-162">網站上安全性憑證的撤銷無法由 [產品支援] 重新製造。</span><span class="sxs-lookup"><span data-stu-id="99c53-162">The revocation of the security certificate on the web site is not re-producible by Product Support.</span></span> <span data-ttu-id="99c53-163">需要新增 [記錄] 以協助根本解決問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-163">Logging needs to be added to help root cause the issue.</span></span>
- <span data-ttu-id="99c53-164">解決導致使用者看到同步處理失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-164">Addresses an issue that caused users to see synchronization failures.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="99c53-165">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-165">PowerPoint</span></span>
- <span data-ttu-id="99c53-166">無法執行插入3D 模型 (動態或靜態)，且嘗試 [另存成圖片]。</span><span class="sxs-lookup"><span data-stu-id="99c53-166">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>

### <a name="project"></a><span data-ttu-id="99c53-167">Project</span><span class="sxs-lookup"><span data-stu-id="99c53-167">Project</span></span>
- <span data-ttu-id="99c53-168">[工作] 不會在 [手動排程的子工作] 彙總中計算。</span><span class="sxs-lookup"><span data-stu-id="99c53-168">Task work is not calculated in Summary roll-up for manually scheduled child tasks.</span></span>
- <span data-ttu-id="99c53-169">嘗試儲存伺服器架構專案時，從 [功能區] 按鈕叫用的 Project VBA 程式碼可能無法使用。</span><span class="sxs-lookup"><span data-stu-id="99c53-169">Project VBA Code invoked from a Ribbon button may not work when trying to save server-based Projects.</span></span>
- <span data-ttu-id="99c53-170">除非 Project 已在執行，從 SharePoint 文件庫中開啟專案檔案會顯示錯誤，且檔案無法開啟。</span><span class="sxs-lookup"><span data-stu-id="99c53-170">Unless Project is already running, opening Project files from a SharePoint document library displays an error and the file will not open.</span></span>

### <a name="word"></a><span data-ttu-id="99c53-171">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-171">Word</span></span>
- <span data-ttu-id="99c53-172">儲存現有檔案可能會無法執行。</span><span class="sxs-lookup"><span data-stu-id="99c53-172">Saving existing files may not work.</span></span>
- <span data-ttu-id="99c53-173">在 [拼字及文法檢查編輯器] 視窗中使用方向鍵可能會導致間歇性閃爍。</span><span class="sxs-lookup"><span data-stu-id="99c53-173">Using arrow keys in the Spelling and Grammar editor window may result in intermittent flickering.</span></span>
- <span data-ttu-id="99c53-174">解決待處理時，相關註解可能不會轉換成指向註解。</span><span class="sxs-lookup"><span data-stu-id="99c53-174">When resolving a follow-up, associated comments may not convert to point comments.</span></span>
- <span data-ttu-id="99c53-175">無法執行插入3D 模型 (動態或靜態)，且嘗試 [另存成圖片]。</span><span class="sxs-lookup"><span data-stu-id="99c53-175">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>

### <a name="office-suite"></a><span data-ttu-id="99c53-176">Office 套件</span><span class="sxs-lookup"><span data-stu-id="99c53-176">Office Suite</span></span>
- <span data-ttu-id="99c53-177">修正了 Office 更新訊息不以預期語言顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-177">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="99c53-178">自此以後，Office 更新訊息會正確符合 Windows 顯示語言。</span><span class="sxs-lookup"><span data-stu-id="99c53-178">Going forward, Office update messages will correctly match the Windows display language.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1912-december-06"></a><span data-ttu-id="99c53-180">版本 1912：12 月 06 日</span><span class="sxs-lookup"><span data-stu-id="99c53-180">Version 1912: December 06</span></span>
<span data-ttu-id="99c53-181">*版本 1912 (組建 12325.20012)*</span><span class="sxs-lookup"><span data-stu-id="99c53-181">*Version 1912 (Build 12325.20012)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="99c53-183">功能更新</span><span class="sxs-lookup"><span data-stu-id="99c53-183">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="99c53-184">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-184">Outlook</span></span>

- <span data-ttu-id="99c53-185">**進階群組電子郵件設定：** 此功能可協助使用者自訂要在收件匣中接收/追蹤哪些電子郵件或活動。</span><span class="sxs-lookup"><span data-stu-id="99c53-185">**Advanced group email settings:** This feature helps groups users to customize which emails or events to receive/follow in their inbox.</span></span>

- <span data-ttu-id="99c53-186">**群組命名原則：** 群組命名原則可讓 IT 系統管理員將組織中使用者所建立群組的名稱標準化及管理。</span><span class="sxs-lookup"><span data-stu-id="99c53-186">**Groups Naming policy:** A group naming policy enables the IT admin to standardize and manage the names of groups created by users in the organization.</span></span> <span data-ttu-id="99c53-187">系統管理員可以要求在建立群組時，將特定首碼和尾碼新增至群組的名稱，而且可以封鎖使用特定字詞。</span><span class="sxs-lookup"><span data-stu-id="99c53-187">The admin can require a specific prefix and suffix be added to the name for a group when it's created, and can block specific words from being used.</span></span> <span data-ttu-id="99c53-188">這有助於將群組名稱中使用不當字詞的情況最小化，以及 IT 管理其目錄中群組的表示方式。</span><span class="sxs-lookup"><span data-stu-id="99c53-188">This helps minimize the use of inappropriate words in group names as well as IT manage the representation of groups in their directory.</span></span> <span data-ttu-id="99c53-189">命名原則也可協助部署小組網站的組織根據部門來分類。</span><span class="sxs-lookup"><span data-stu-id="99c53-189">Naming Policy also helps organizations that deploy team sites to categorize them based on department.</span></span>

### <a name="office-suite"></a><span data-ttu-id="99c53-190">Office 套件</span><span class="sxs-lookup"><span data-stu-id="99c53-190">Office Suite</span></span>

- <span data-ttu-id="99c53-191">**索引標籤式窗格：** 現在您可以使用應用程式右側的索引標籤 UI，在多個窗格之間切換。</span><span class="sxs-lookup"><span data-stu-id="99c53-191">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="99c53-192">只有當您開啟 2 個以上的窗格時，該 UI 才會顯示。</span><span class="sxs-lookup"><span data-stu-id="99c53-192">The UI will only be visible when you have 2+ panes open.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="99c53-195">解決的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-195">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="99c53-196">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-196">Excel</span></span>
- <span data-ttu-id="99c53-197">使用者在使用某些非英文字元集的情況下，儲存變更時可能會遇到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-197">Users may encounter an error when saving changes while using some non-English character sets.</span></span>
- <span data-ttu-id="99c53-198">使用者在存取隱藏的命名範圍時可能會發生錯誤。</span><span class="sxs-lookup"><span data-stu-id="99c53-198">Users may encounter an error when accessing a hidden named range.</span></span>
- <span data-ttu-id="99c53-199">停用使用 4K 解析度的硬體圖形加速的情況下，可能會在捲動時發生延遲儲存格呈現的問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-199">Disabling hardware graphics acceleration with 4K resolution may result in delayed rendering of cells when scrolling around.</span></span>
- <span data-ttu-id="99c53-200">清除與儲存格界限重疊的長型公式，可能仍舊會跨儲存格界限顯示出來。</span><span class="sxs-lookup"><span data-stu-id="99c53-200">Clearing a long formula that overlaps a cell boundary may still display across the cell boundary.</span></span>
- <span data-ttu-id="99c53-201">解決了開啟內嵌活頁簿時，功能區自訂無法載入的問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-201">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>
- <span data-ttu-id="99c53-202">邊界下拉式功能表可能無法正確呈現。</span><span class="sxs-lookup"><span data-stu-id="99c53-202">Margin dropdown menu may not render correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="99c53-203">OneNote</span><span class="sxs-lookup"><span data-stu-id="99c53-203">OneNote</span></span>
- <span data-ttu-id="99c53-204">OneNote 可能無法透過「會議記事」Outlook 增益集開啟。</span><span class="sxs-lookup"><span data-stu-id="99c53-204">OneNote may not open via the 'Meeting Notes' Outlook add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="99c53-205">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-205">Outlook</span></span>
- <span data-ttu-id="99c53-206">保留原則標籤可能會將保留時間顯示於括弧中。</span><span class="sxs-lookup"><span data-stu-id="99c53-206">Retention policy labels may display the retention time period in parenthesis.</span></span>
- <span data-ttu-id="99c53-207">空格可能會顯示於日文語言套件的連絡人卡片中。</span><span class="sxs-lookup"><span data-stu-id="99c53-207">Blank spaces may appear in Contact cards with Japanese language pack.</span></span>
- <span data-ttu-id="99c53-208">內嵌插入至 Outlook 電子郵件訊息中的影像有時候會改變大小。</span><span class="sxs-lookup"><span data-stu-id="99c53-208">Images inserted inline to Outlook e-mail messages can sometimes get resized.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="99c53-209">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-209">PowerPoint</span></span>
- <span data-ttu-id="99c53-210">如果使用者雲端檔案的投影片上有兩個 (或多個) 不同的影片，影片影像可正確呈現，但是當使用者按一下每一個檔案來播放時，影片內容會是相同的。</span><span class="sxs-lookup"><span data-stu-id="99c53-210">If a user has two (or more) different videos on a slide in a cloud file, the video images are rendered correctly, but when the user clicks on each one to play, the video content is the same.</span></span>
- <span data-ttu-id="99c53-211">在某些情況下，使用觸控裝置進行捲動將無法運作。</span><span class="sxs-lookup"><span data-stu-id="99c53-211">In some cases, scrolling with touch devices will not work.</span></span>
- <span data-ttu-id="99c53-212">邊界下拉式功能表可能無法正確呈現。</span><span class="sxs-lookup"><span data-stu-id="99c53-212">Margin dropdown menu may not render correctly.</span></span>
- <span data-ttu-id="99c53-213">Office 應用程式之間的安全性連結可能無法啟動連結的應用程式。</span><span class="sxs-lookup"><span data-stu-id="99c53-213">Safelinks from one Office application to another may not launch the linked application.</span></span>

### <a name="project"></a><span data-ttu-id="99c53-214">Project</span><span class="sxs-lookup"><span data-stu-id="99c53-214">Project</span></span>
- <span data-ttu-id="99c53-215">當您使用 [比較專案] 功能時，Project 可能會當機。</span><span class="sxs-lookup"><span data-stu-id="99c53-215">Project may crash when you use the Compare Projects feature.</span></span>
- <span data-ttu-id="99c53-216">如果您在 [深色] 模式中，當您移至含有過度分配資源之工作上的工作檢查面板時，將無法讀取資料表。</span><span class="sxs-lookup"><span data-stu-id="99c53-216">If you are in Dark mode, when you go to the task inspector panel on a task with an over allocated resource, you are unable to read the table.</span></span>
- <span data-ttu-id="99c53-217">將沒有作業的任務進行進位設定為 1 天。</span><span class="sxs-lookup"><span data-stu-id="99c53-217">Setting effort on tasks that have no assignments are rounded to 1 day.</span></span>

### <a name="word"></a><span data-ttu-id="99c53-218">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-218">Word</span></span>
- <span data-ttu-id="99c53-219">在特定條件下，完成合併列印之後儲存的檔案可能無法使用。</span><span class="sxs-lookup"><span data-stu-id="99c53-219">Saving a file after doing a mail merge may not work under certain conditions.</span></span>
- <span data-ttu-id="99c53-220">建置組塊召集人可能會顯示不正確通知：&quot;您已修改過樣式、建置組塊&quot;。</span><span class="sxs-lookup"><span data-stu-id="99c53-220">Building blocks organizer may display an invalid alert: &quot;You have modified styles, building blocks&quot;.</span></span>
- <span data-ttu-id="99c53-221">使用複製/貼上時，有時會重新載入註解窗格。</span><span class="sxs-lookup"><span data-stu-id="99c53-221">Comment pane sometimes gets reloaded when using copy/paste.</span></span>
- <span data-ttu-id="99c53-222">註解有時不會以正確的順序貼上。</span><span class="sxs-lookup"><span data-stu-id="99c53-222">Comments are sometimes not pasted in the correct order.</span></span>
- <span data-ttu-id="99c53-223">將含有自訂樣式的多層級清單範本套用至現有的文件時，可能在特定條件下不會保留該樣式。</span><span class="sxs-lookup"><span data-stu-id="99c53-223">Applying a template consisting of a multi-level list with custom styles to existing documents may not preserve the style under certain conditions.</span></span>
- <span data-ttu-id="99c53-224">調整分割螢幕邊界的大小可能會造成其他的分割螢幕。</span><span class="sxs-lookup"><span data-stu-id="99c53-224">Resizing a split screen border may introduce an additional split screen.</span></span>
- <span data-ttu-id="99c53-225">邊界下拉式功能表可能無法正確呈現。</span><span class="sxs-lookup"><span data-stu-id="99c53-225">Margin dropdown menu may not render correctly.</span></span>
- <span data-ttu-id="99c53-226">@提及註解卡中的使用者可能會顯示 JSON。</span><span class="sxs-lookup"><span data-stu-id="99c53-226">At-mentioning a user in a comment card may show JSON.</span></span>
- <span data-ttu-id="99c53-227">Office 應用程式之間的安全性連結可能無法啟動連結的應用程式。</span><span class="sxs-lookup"><span data-stu-id="99c53-227">Safelinks from one Office application to another may not launch the linked application.</span></span>

### <a name="office-suite"></a><span data-ttu-id="99c53-228">Office 套件</span><span class="sxs-lookup"><span data-stu-id="99c53-228">Office Suite</span></span>
- <span data-ttu-id="99c53-229">針對日文產品，帳戶使用者的姓名可能會以錯誤的順序出現。</span><span class="sxs-lookup"><span data-stu-id="99c53-229">For Japanese based products, account user first name, last name may appear in incorrect order.</span></span>
- <span data-ttu-id="99c53-230">將滑鼠指標暫留於註解上方時，可能會在註解周圍顯示文字方塊外框的問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-230">Hovering a mouse pointer over comments may display a textbox outline around the comment.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1912-november-15"></a><span data-ttu-id="99c53-232">版本 1912：11 月 15 日</span><span class="sxs-lookup"><span data-stu-id="99c53-232">Version 1912: November 15</span></span>
<span data-ttu-id="99c53-233">*版本1912 (組建 12307.20000)*</span><span class="sxs-lookup"><span data-stu-id="99c53-233">*Version 1912 (Build 12307.20000)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="99c53-235">功能更新</span><span class="sxs-lookup"><span data-stu-id="99c53-235">Feature updates</span></span>
### <a name="insights-services"></a><span data-ttu-id="99c53-236">深入解析服務</span><span class="sxs-lookup"><span data-stu-id="99c53-236">Insights Services</span></span>
- <span data-ttu-id="99c53-237">**Excel 構想中的自然語言查詢：** Excel 構想的新功能，詢問關於您資料的自然語言問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-237">**Natural Language Queries in Ideas in Excel:** Excel Ideas's new capability to ask a natural language question about your data.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="99c53-240">解決的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-240">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="99c53-241">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-241">Excel</span></span>
- <span data-ttu-id="99c53-242">某些當地語系化版本的 [文字到欄] 功能可能會失敗。</span><span class="sxs-lookup"><span data-stu-id="99c53-242">Text to Column functionality may fail for some localizations.</span></span>
- <span data-ttu-id="99c53-243">編輯儲存格中的動態陣列公式可能會導致文字在儲存格邊界以外對齊。</span><span class="sxs-lookup"><span data-stu-id="99c53-243">Editing dynamic array formulas within a cell may result in text being aligned outside of the boundary of the cell.</span></span>

### <a name="outlook"></a><span data-ttu-id="99c53-244">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-244">Outlook</span></span>
- <span data-ttu-id="99c53-245">新增透過群組原則強制執行 S/MIME 設定的功能。</span><span class="sxs-lookup"><span data-stu-id="99c53-245">Added the ability to enforce S/MIME configuration via group policy.</span></span>
- <span data-ttu-id="99c53-246">內嵌影像可能會比預期小。</span><span class="sxs-lookup"><span data-stu-id="99c53-246">Embedded images may appear smaller than expected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="99c53-247">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-247">PowerPoint</span></span>
- <span data-ttu-id="99c53-248">當您將焦點移出文字後，游標可能會消失。</span><span class="sxs-lookup"><span data-stu-id="99c53-248">Cursor may disappear after moving focus from text.</span></span>

### <a name="project"></a><span data-ttu-id="99c53-249">Project</span><span class="sxs-lookup"><span data-stu-id="99c53-249">Project</span></span>
- <span data-ttu-id="99c53-250">使用者可能會遇到授權錯誤。</span><span class="sxs-lookup"><span data-stu-id="99c53-250">Users may experience an error regarding licensing.</span></span>
- <span data-ttu-id="99c53-251">日期選擇器中的 [今日] 按鈕有時候可能會設定不正確的日期。</span><span class="sxs-lookup"><span data-stu-id="99c53-251">The Today button in the date picker may sometimes set the incorrect date.</span></span>

### <a name="word"></a><span data-ttu-id="99c53-252">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-252">Word</span></span>
- <span data-ttu-id="99c53-253">以滑鼠右鍵按一下有時不會選取整個字詞。</span><span class="sxs-lookup"><span data-stu-id="99c53-253">Right-clicking can sometimes not result in selecting the whole word.</span></span>
- <span data-ttu-id="99c53-254">轉換成建議格式之後，游標在物件內可能仍處於使用中狀態。</span><span class="sxs-lookup"><span data-stu-id="99c53-254">The cursor may remain active within an object after converting to a suggested format.</span></span>
- <span data-ttu-id="99c53-255">訊息中的影像在某些情況下可能會不正確的縮放。</span><span class="sxs-lookup"><span data-stu-id="99c53-255">Images in messages may be incorrectly scaled in some scenarios.</span></span>
- <span data-ttu-id="99c53-256">某些主題可能會導致難以判斷所選取的註解。</span><span class="sxs-lookup"><span data-stu-id="99c53-256">Some themes may make it difficult to determine which comment is selected.</span></span>
- <span data-ttu-id="99c53-257">選取註解提示之後，在窗格切換器中隱藏時，現在會顯示新式註解窗格。</span><span class="sxs-lookup"><span data-stu-id="99c53-257">Selecting a comment hint should now show the modern comments pane when hidden in pane switcher.</span></span>

### <a name="office-suite"></a><span data-ttu-id="99c53-258">Office 套件</span><span class="sxs-lookup"><span data-stu-id="99c53-258">Office Suite</span></span>
- <span data-ttu-id="99c53-259">回覆註解可能會導致文字方塊垂直延伸到窗格的邊緣以外。</span><span class="sxs-lookup"><span data-stu-id="99c53-259">Replying to a comment may cause the textbox to expand vertically beyond the edge of the pane.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1912-november-08"></a><span data-ttu-id="99c53-261">版本 1912：11 月 8 日</span><span class="sxs-lookup"><span data-stu-id="99c53-261">Version 1912: November 08</span></span>
<span data-ttu-id="99c53-262">*版本 1912 (組建 12231.20000)*</span><span class="sxs-lookup"><span data-stu-id="99c53-262">*Version 1912 (Build 12231.20000)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="99c53-264">功能更新</span><span class="sxs-lookup"><span data-stu-id="99c53-264">Feature updates</span></span>
### <a name="user-lifecycle"></a><span data-ttu-id="99c53-265">使用者生命週期</span><span class="sxs-lookup"><span data-stu-id="99c53-265">User Lifecycle</span></span>
- <span data-ttu-id="99c53-266">**AFO 啟用的經驗改進：** 對客戶啟用新電腦隨附的 Office 時，所會看到的畫面進行更新。</span><span class="sxs-lookup"><span data-stu-id="99c53-266">**Experience improvements for AFO activation:** Updates to the screens customers see when activating Office that comes bundled with their new PC.</span></span>

### <a name="word"></a><span data-ttu-id="99c53-267">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-267">Word</span></span>
- <span data-ttu-id="99c53-268">**Word 中的全新和改良的線上影片體驗：** 全新和更安全的線上影片體驗，可協助您在 Word 中插入新的影片並播放現有影片。</span><span class="sxs-lookup"><span data-stu-id="99c53-268">**New and improved online video experience in Word:** New and more secure online video experience to help you insert new videos and play existing videos in Word.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="99c53-271">解決的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-271">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="99c53-272">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-272">Outlook</span></span>
- <span data-ttu-id="99c53-273">與跨資料夾內容有關的間歇性損毀。</span><span class="sxs-lookup"><span data-stu-id="99c53-273">Intermittent crash involving cross folder content.</span></span>

### <a name="office-suite"></a><span data-ttu-id="99c53-274">Office 套件</span><span class="sxs-lookup"><span data-stu-id="99c53-274">Office Suite</span></span>
- <span data-ttu-id="99c53-275">將圖表從 Excel 貼上至 PowerPoint 可能會造成圖表的大小縮小。</span><span class="sxs-lookup"><span data-stu-id="99c53-275">Pasting a chart from Excel to PowerPoint can reduce the size of the chart.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1911-november-01"></a><span data-ttu-id="99c53-277">版本 1911：11 月 1 日</span><span class="sxs-lookup"><span data-stu-id="99c53-277">Version 1911: November 01</span></span>
<span data-ttu-id="99c53-278">*版本 1911 (組建 12228.20020)*</span><span class="sxs-lookup"><span data-stu-id="99c53-278">*Version 1911 (Build 12228.20020)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="99c53-280">功能更新</span><span class="sxs-lookup"><span data-stu-id="99c53-280">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="99c53-281">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-281">Excel</span></span>
- <span data-ttu-id="99c53-282">**將內容與 SVG 物件一起顯示！：** 在 Office 中轉換地圖、圖表和其他 SVG 向量等物件時，現在您可以保留物件中的文字。</span><span class="sxs-lookup"><span data-stu-id="99c53-282">**Bring the context along with your SVG objects!:** Now you can retain the text in maps, chart and other SVG vectors when converting these objects in Office.</span></span>

- <span data-ttu-id="99c53-283">**拿起 Surface 手寫筆時查看手寫筆選項：** 當您在 Word、Excel 或 PowerPoint 中先拿起 Surface 手寫筆時，[繪圖] 索引標籤將會啟動，讓您輕鬆地選取畫筆色彩。</span><span class="sxs-lookup"><span data-stu-id="99c53-283">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="99c53-284">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-284">PowerPoint</span></span>
- <span data-ttu-id="99c53-285">**將內容與 SVG 物件一起顯示！：** 在 Office 中轉換地圖、圖表和其他 SVG 向量等物件時，現在您可以保留物件中的文字。</span><span class="sxs-lookup"><span data-stu-id="99c53-285">**Bring the context along with your SVG objects!:** Now you can retain the text in maps, chart and other SVG vectors when converting these objects in Office.</span></span>

- <span data-ttu-id="99c53-286">**拿起 Surface 手寫筆時查看手寫筆選項：** 當您在 Word、Excel 或 PowerPoint 中先拿起 Surface 手寫筆時，[繪圖] 索引標籤將會啟動，讓您輕鬆地選取畫筆色彩。</span><span class="sxs-lookup"><span data-stu-id="99c53-286">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

### <a name="visio"></a><span data-ttu-id="99c53-287">Visio</span><span class="sxs-lookup"><span data-stu-id="99c53-287">Visio</span></span>
- <span data-ttu-id="99c53-288">**在 Excel 中製作精美的 Visio 圖表：** 在 Excel 中快速且輕鬆地將資料呈現為精美的 Visio 圖表。</span><span class="sxs-lookup"><span data-stu-id="99c53-288">**Make polished Visio diagrams in Excel:** Quickly and easily visualize your data into polished Visio diagrams within Excel.</span></span> <span data-ttu-id="99c53-289">[深入了解](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)。</span><span class="sxs-lookup"><span data-stu-id="99c53-289">[Learn more](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c).</span></span>

### <a name="word"></a><span data-ttu-id="99c53-290">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-290">Word</span></span>
- <span data-ttu-id="99c53-291">**拿起 Surface 手寫筆時查看手寫筆選項：** 當您在 Word、Excel 或 PowerPoint 中先拿起 Surface 手寫筆時，[繪圖] 索引標籤將會啟動，讓您輕鬆地選取畫筆色彩。</span><span class="sxs-lookup"><span data-stu-id="99c53-291">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

- <span data-ttu-id="99c53-292">**改善共同撰寫：** 改善共同撰寫的體驗，盡可能讓其他人即時收到修改過的內容。</span><span class="sxs-lookup"><span data-stu-id="99c53-292">**Coauthoring improvements:** Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

- <span data-ttu-id="99c53-293">**其他人更快速看到您的變更：** 共同撰寫增強功能表示，共同作業者可較以往更快速看到您的變更。</span><span class="sxs-lookup"><span data-stu-id="99c53-293">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="99c53-296">解決的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-296">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="99c53-297">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-297">Excel</span></span>
- <span data-ttu-id="99c53-298">解決從不受信任的網路共用編輯受保護的檔案時，Excel 可能會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-298">Resolved an issue where Excel may crash when editing a protected file from an untrusted network share.</span></span>
- <span data-ttu-id="99c53-299">解決在刪除含有的走勢圖參考另一個資料表中資料的資料表時，會導致重新開啟檔案時，將檔案識別為已損毀的問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-299">Resolved an issue where deleting sheets containing sparklines referencing data on another sheet could cause the file to be identified as corrupted when re-opened.</span></span>
- <span data-ttu-id="99c53-300">解決當您將報表篩選隨著其餘的樞紐分析表一起轉換，以用於 SQL 表格式伺服器的查詢時，可能會遇到結果不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-300">Resolved an Issue where you may get incorrect results when converting report filters along with the rest of the PivotTable for queries to SQL tabular servers.</span></span>
- <span data-ttu-id="99c53-301">同時使用朗讀程式和放大鏡，可能會導致當機。</span><span class="sxs-lookup"><span data-stu-id="99c53-301">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="99c53-302">同時使用朗讀程式和放大鏡，可能會導致當機。</span><span class="sxs-lookup"><span data-stu-id="99c53-302">Using Narrator and Magnifier at the same time may result in a crash.</span></span>

### <a name="outlook"></a><span data-ttu-id="99c53-303">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-303">Outlook</span></span>
- <span data-ttu-id="99c53-304">轉寄的電子郵件可能會遺失內嵌的影像。</span><span class="sxs-lookup"><span data-stu-id="99c53-304">A forwarded e-mail may be missing embedded images.</span></span>
- <span data-ttu-id="99c53-305">會議室尋找工具可能會對可用的會議室顯示 &quot;[無]&quot;。</span><span class="sxs-lookup"><span data-stu-id="99c53-305">Room Finder tool may be displaying &quot;None&quot; for available rooms.</span></span>
- <span data-ttu-id="99c53-306">使用者可能無法建立具有嚴格租用戶限制的 Outlook 設定檔。</span><span class="sxs-lookup"><span data-stu-id="99c53-306">Users may not be able to create Outlook profiles with strict tenant restriction.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="99c53-307">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-307">PowerPoint</span></span>
- <span data-ttu-id="99c53-308">同時使用朗讀程式和放大鏡，可能會導致當機。</span><span class="sxs-lookup"><span data-stu-id="99c53-308">Using Narrator and Magnifier at the same time may result in a crash.</span></span>

### <a name="project"></a><span data-ttu-id="99c53-309">Project</span><span class="sxs-lookup"><span data-stu-id="99c53-309">Project</span></span>
- <span data-ttu-id="99c53-310">使用者無法將工作標示為已完成，並將它設為 99%。</span><span class="sxs-lookup"><span data-stu-id="99c53-310">User is unable to mark a task as complete, and it gets set to 99%.</span></span>
- <span data-ttu-id="99c53-311">資源撫平無法解決資源過度分派問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-311">Overallocations are not resolved by leveling.</span></span>

### <a name="word"></a><span data-ttu-id="99c53-312">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-312">Word</span></span>
- <span data-ttu-id="99c53-313">同時使用朗讀程式和放大鏡，可能會導致當機。</span><span class="sxs-lookup"><span data-stu-id="99c53-313">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="99c53-314">開啟舊版文件，然後移至 [資訊] 索引標籤會導致當機。</span><span class="sxs-lookup"><span data-stu-id="99c53-314">Opening legacy documents and then going to the Info tab can cause a crash.</span></span>
- <span data-ttu-id="99c53-315">內容功能表中未顯示校訂建議。</span><span class="sxs-lookup"><span data-stu-id="99c53-315">Proofing suggestins are not displaying in contextual menus.</span></span>
- <span data-ttu-id="99c53-316">對註解套用不正確的內容原則。</span><span class="sxs-lookup"><span data-stu-id="99c53-316">Content policies are being incorrectly applied to comments.</span></span>
- <span data-ttu-id="99c53-317">以深色文字編寫的舊版註解在深色模式中不會顯示。</span><span class="sxs-lookup"><span data-stu-id="99c53-317">Legacy comments written with dark text is not visible in Dark Mode.</span></span>
- <span data-ttu-id="99c53-318">使用韓文/英文自動校正時，可能出現不正確的字元。</span><span class="sxs-lookup"><span data-stu-id="99c53-318">Incorrect characters may appear when using Korean/English autocorrect.</span></span>
- <span data-ttu-id="99c53-319">在應優先套用較高的原則標籤前，可能已套用了較低的原則標籤。</span><span class="sxs-lookup"><span data-stu-id="99c53-319">Lower policy labels may be applied when a higher policy label should have taken priority.</span></span>
- <span data-ttu-id="99c53-320">來自 Outlook 郵件中的 cid: 影像連結&nbsp;現在能在要求時成功中斷。</span><span class="sxs-lookup"><span data-stu-id="99c53-320">The links of cid: images from Outlook messages&nbsp;can now be successfully broken when requested.</span></span>
- <span data-ttu-id="99c53-321">同時使用朗讀程式和放大鏡，可能會導致當機。</span><span class="sxs-lookup"><span data-stu-id="99c53-321">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="99c53-322">從瀏覽窗格搜尋可能會失敗。</span><span class="sxs-lookup"><span data-stu-id="99c53-322">Searching from the Navigation pane may fail.</span></span>

### <a name="office-suite"></a><span data-ttu-id="99c53-323">Office 套件</span><span class="sxs-lookup"><span data-stu-id="99c53-323">Office Suite</span></span>
- <span data-ttu-id="99c53-324">某些繪圖可能不會在預覽或投影片放映中顯示。</span><span class="sxs-lookup"><span data-stu-id="99c53-324">Some drawings may not display in preview or slide shows.</span></span>
- <span data-ttu-id="99c53-325">在垂直文字方塊中，部分片假名字元可能無法正確顯示。</span><span class="sxs-lookup"><span data-stu-id="99c53-325">Some katakana characters may display incorrectly in a vertical text box.</span></span>
- <span data-ttu-id="99c53-326">嘗試將檔案儲存到已中斷連線的網路共用時可能會導致當機。</span><span class="sxs-lookup"><span data-stu-id="99c53-326">Attempting to save a file to a disconnected network share may result in a crash.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1911-october-25"></a><span data-ttu-id="99c53-328">版本 1911：10 月 25 日</span><span class="sxs-lookup"><span data-stu-id="99c53-328">Version 1911: October 25</span></span>
<span data-ttu-id="99c53-329">*版本 1911 (組建 12215.20006)*</span><span class="sxs-lookup"><span data-stu-id="99c53-329">*Version 1911 (Build 12215.20006)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="99c53-331">功能更新</span><span class="sxs-lookup"><span data-stu-id="99c53-331">Feature updates</span></span>
### <a name="visio"></a><span data-ttu-id="99c53-332">Visio</span><span class="sxs-lookup"><span data-stu-id="99c53-332">Visio</span></span>

- <span data-ttu-id="99c53-333">**在 Excel 中製作精美的 Visio 圖表：** 在 Excel 中快速且輕鬆地將資料呈現為精美的 Visio 圖表。</span><span class="sxs-lookup"><span data-stu-id="99c53-333">**Make polished Visio diagrams in Excel:** Quickly and easily visualize your data into polished Visio diagrams within Excel.</span></span> [<span data-ttu-id="99c53-334">深入了解</span><span class="sxs-lookup"><span data-stu-id="99c53-334">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="99c53-335">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-335">Word</span></span>

- <span data-ttu-id="99c53-336">**改善共同撰寫：** 改善共同撰寫的體驗，盡可能讓其他人即時收到修改過的內容。</span><span class="sxs-lookup"><span data-stu-id="99c53-336">**Coauthoring improvements:** Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

- <span data-ttu-id="99c53-337">**其他人更快速看到您的變更：** 共同撰寫增強功能表示，共同作業者可較以往更快速看到您的變更。</span><span class="sxs-lookup"><span data-stu-id="99c53-337">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="99c53-340">解決的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-340">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="99c53-341">Access</span><span class="sxs-lookup"><span data-stu-id="99c53-341">Access</span></span>

- <div><span data-ttu-id="99c53-342"><span>記錄計數可能不正確</span></span><span class="sxs-lookup"><span data-stu-id="99c53-342"><span>The record count could be incorrect</span></span></span></div>


### <a name="excel"></a><span data-ttu-id="99c53-343">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-343">Excel</span></span>

- <div><span data-ttu-id="99c53-344"><span>我們已大幅改善刪除合併儲存格的資料行的效能</span></span><span class="sxs-lookup"><span data-stu-id="99c53-344"><span>We significantly improved the performance of deleting columns with merged cells</span></span></span></div>


- <div><span data-ttu-id="99c53-345"><span>可能已防止使用者以 Office 365 Excel 活頁簿格式儲存</span></span><span class="sxs-lookup"><span data-stu-id="99c53-345"><span>Users could be prevented from saving in Office 365 Excel Workbook format</span></span></span></div>


- <div><span data-ttu-id="99c53-346"><span>核取方塊無法正確呈現</span></span><span class="sxs-lookup"><span data-stu-id="99c53-346"><span>Checkboxes could not render correctly</span></span></span></div>


- <div><span data-ttu-id="99c53-347"><span>無法儲存對圖表大小的變更</span></span><span class="sxs-lookup"><span data-stu-id="99c53-347"><span>Changes to a chart size could not be saved</span></span></span></div>


- <div><span data-ttu-id="99c53-348"><span>某些 VBA 函數會針對新的圖表類型傳回錯誤</span></span><span class="sxs-lookup"><span data-stu-id="99c53-348"><span>Some VBA functions would return an error on new chart types</span></span></span></div>


- <div><span data-ttu-id="99c53-349"><span>[選取資料來源] 對話方塊上的部分欄位並未區分大小寫</span></span><span class="sxs-lookup"><span data-stu-id="99c53-349"><span>Select Data Source dialogs were not case sensitive for some fields</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="99c53-350">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-350">PowerPoint</span></span>

- <div><span data-ttu-id="99c53-351"><span>無法儲存對圖表大小的變更</span></span><span class="sxs-lookup"><span data-stu-id="99c53-351"><span>Changes to a chart size could not be saved</span></span></span></div>


### <a name="publisher"></a><span data-ttu-id="99c53-352">Publisher</span><span class="sxs-lookup"><span data-stu-id="99c53-352">Publisher</span></span>

- <div><span data-ttu-id="99c53-353"><span>圖形可能會顯示在圖形框線以外</span></span><span class="sxs-lookup"><span data-stu-id="99c53-353"><span>Shapes could appear outside of the graphics border</span></span></span></div>


### <a name="word"></a><span data-ttu-id="99c53-354">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-354">Word</span></span>

- <div><span data-ttu-id="99c53-355"><span>圖形可能會顯示在圖形框線以外</span></span><span class="sxs-lookup"><span data-stu-id="99c53-355"><span>Shapes could appear outside of the graphics border</span></span></span></div>


- <div><span data-ttu-id="99c53-356"><span>醒目提示文字可能很困難</span></span><span class="sxs-lookup"><span data-stu-id="99c53-356"><span>Highlighting text could be challenging</span></span></span></div>


- <div><span data-ttu-id="99c53-357"><span>可能已防止使用者在編輯器中瀏覽個別項目</span></span><span class="sxs-lookup"><span data-stu-id="99c53-357"><span>A user could be prevented from navigating to an individual item in the editor</span></span></span></div>


- <div><span data-ttu-id="99c53-358"><span>可能不會將文法或拼寫錯誤醒目提示</span></span><span class="sxs-lookup"><span data-stu-id="99c53-358"><span>Grammar or spelling errors might not be highlighted</span></span></span></div>


- <div><span data-ttu-id="99c53-359"><span>無法儲存對圖表大小的變更</span></span><span class="sxs-lookup"><span data-stu-id="99c53-359"><span>Changes to a chart size could not be saved</span></span></span></div>


- <div><span data-ttu-id="99c53-360"><span>將格式設定套用到 @ 提及之後，可能會防止開啟連絡人卡片</span></span><span class="sxs-lookup"><span data-stu-id="99c53-360"><span>A contact card could be prevented from opening after apply formatting to an @ mention</span></span></span></div>


- <div><span data-ttu-id="99c53-361"><span>已解決使用者無法儲存 Word、Excel 和 PowerPoint 文件的問題。&nbsp;此問題會影響建立新檔案並在按一下 [儲存] 圖示或按 Ctrl + S 之後帶出 [另存成模型對話方塊]&quot;&quot; 選項的使用者。</span></span><span class="sxs-lookup"><span data-stu-id="99c53-361"><span>Resolvedan issue where users may be unable to save Word, Excel, and PowerPoint documents.&nbsp; This issue affects users that create a new file and bring up the &quot;Save as Model Dialog&quot; option after clicking on the Save icon or pressing Ctrl + S.</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="99c53-362">Office 套件</span><span class="sxs-lookup"><span data-stu-id="99c53-362">Office Suite</span></span>

- <div><span data-ttu-id="99c53-363"><span>在 Windows 7 上使用圖形時的效能問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-363"><span>Performance issue when using Shapes on Windows 7</span></span></span></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1911-october-18"></a><span data-ttu-id="99c53-365">版本 1911：10 月 18 日</span><span class="sxs-lookup"><span data-stu-id="99c53-365">Version 1911: October 18</span></span>
<span data-ttu-id="99c53-366">*版本 1911 (組建 12209.20010)*</span><span class="sxs-lookup"><span data-stu-id="99c53-366">*Version 1911 (Build 12209.20010)*</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="99c53-368">功能更新</span><span class="sxs-lookup"><span data-stu-id="99c53-368">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="99c53-369">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-369">Outlook</span></span>

- <span data-ttu-id="99c53-370">**傳送可存取的郵件給最需要它的人員：** Outlook 會顯示郵件提示，協助確保將您的內容傳送給偏好可存取內容的使用者時可供其存取</span><span class="sxs-lookup"><span data-stu-id="99c53-370">**Send accessible mail to those who need it most:** Outlook will display a mail tip to help you ensure that your content is accessible when sending to a user who prefers accessible content</span></span>

### <a name="powerpoint"></a><span data-ttu-id="99c53-371">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-371">PowerPoint</span></span>

- <span data-ttu-id="99c53-372">**最佳化您的簡報：** 協助工具檢查程式可協助您以螢幕閱讀器為中心，在投影片上排列物件。</span><span class="sxs-lookup"><span data-stu-id="99c53-372">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

### <a name="office-suite"></a><span data-ttu-id="99c53-373">Office 套件</span><span class="sxs-lookup"><span data-stu-id="99c53-373">Office Suite</span></span>

- <span data-ttu-id="99c53-374">**上傳中心將由需要注意的檔案體驗取代：**「上傳中心」將由會顯示在 Office 應用程式的 [檔案] > [開啟] 下的「需要注意的檔案」體驗取代。</span><span class="sxs-lookup"><span data-stu-id="99c53-374">**The Upload Center is being replaced by the Files Needing Attention experience:** The Upload Center is being replaced by the Files Needing Attention experience that will show up inside the Office applications under File > Open.</span></span> <span data-ttu-id="99c53-375">相較於上傳中心，此新體驗更為現代化、整合且更不具侵入性。</span><span class="sxs-lookup"><span data-stu-id="99c53-375">This new experience is more modern, integrated, and less intrusive compared to the Upload Center.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a><span data-ttu-id="99c53-378">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="99c53-378">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="99c53-379">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-379">Excel</span></span>

- <div><span data-ttu-id="99c53-380"><span>解決使用自動調整來調整列高時，核取方塊控制項可能收縮的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-380"><span>Resolved an issue where check box controls could shrink when using autofit to adjust row height</span></span></span></div>


- <div><span data-ttu-id="99c53-381"><span>解決捲動後選取儲存格時，可能導致選取錯誤的儲存格的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-381"><span>Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="99c53-382">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-382">Outlook</span></span>

- <div><span data-ttu-id="99c53-383"><span>發現簽署具有數位簽署附件的電子郵件時，可能導致數位簽章遭到破壞的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-383"><span>Identified an issue which could cause digital signatures to become broken when signing an e-mail with a digitally signed attachment</span></span></span></div>


- <div><span data-ttu-id="99c53-384"><span>發現在將長檔名拖放至郵件內文時，長檔名遭到截斷的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-384"><span>Identified an issue where long filenames were truncated after draging and droping to the message body</span></span></span></div>


- <div><span data-ttu-id="99c53-385">發現當功能區設定為自動隱藏時，搜尋方塊可能消失的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-385">Identified an issue where the search box could disappear when the ribbon is set to hide automatically</span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="99c53-386">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-386">PowerPoint</span></span>

- <div><span data-ttu-id="99c53-387"><span>發現投影片預覽的長寬比未正確鎖定/解除鎖定的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-387"><span>Identified an issuewhere aspect ratio for the slide preview was not being properly locked/unlocked</span></span></span></div>

### <a name="project"></a><span data-ttu-id="99c53-388">Project</span><span class="sxs-lookup"><span data-stu-id="99c53-388">Project</span></span>

- <div><span data-ttu-id="99c53-389">發現在執行更新工作時，若輸入記事，可能不會保留記事的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-389">Identified an issue where notes might not persist if entered while doing update tasks</span></span><br></div>


- <div><span data-ttu-id="99c53-390">發現檔案可能遭某個使用者鎖定，但不會在錯誤訊息中顯示任何使用者名稱的問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-390">Identified an issue where a file could be locked by a user, but no username would be displayed in the error message</span></span></div>


- <div><span data-ttu-id="99c53-391"><span>發現在開啟唯讀專案時，使用者可能會收到數個訊息的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-391"><span>Identified an issue where users could get several messages when opening a read-only project</span></span></span></div>


### <a name="word"></a><span data-ttu-id="99c53-392">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-392">Word</span></span>

- <div><span data-ttu-id="99c53-393"><span>發現使用螢幕閱讀器檢視註解時的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-393"><span>Identified an issue when viewing comments while using a screen reader</span></span></span></div>


- <div><span data-ttu-id="99c53-394"><span>發現將某些評論錯誤地識別為拼寫或文法評論的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-394"><span>Identified an issue where some critiques were misidentified as being spelling or grammar critiques</span></span></span></div>


- <div><span data-ttu-id="99c53-395"><span>發現新留言對話方塊有時候未取得焦點的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-395"><span>Identified an issue where a new comment dialog could sometimes not obtain focus</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="99c53-396">Office 套件</span><span class="sxs-lookup"><span data-stu-id="99c53-396">Office Suite</span></span>

- <div><span data-ttu-id="99c53-397"><span>我們已修正了&quot;另一個安裝正在進行中&quot;的不正確錯誤訊息，可能導致無法升級的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-397"><span>We fixed an issue where an upgrade could be prevented by a incorrect error message of &quot;Another install in progress&quot;</span></span></span></div>

- <div><span data-ttu-id="99c53-398"><span>發現可能會影響從本機資源同步至雲端資源的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-398"><span>Identified an issue which could affect syncing from a local resource to a cloud resource</span></span></span></div>

- <div><span data-ttu-id="99c53-399"><span>發現歡迎訊息含有無效連結的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-399"><span>Identified an issue where a welcome message contained an invalid link</span></span></span></div>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1910-october-11"></a><span data-ttu-id="99c53-401">版本 1910：10 月 11 日</span><span class="sxs-lookup"><span data-stu-id="99c53-401">Version 1910: October 11</span></span>
<span data-ttu-id="99c53-402">*版本 1910 (組建 12130.20112)*</span><span class="sxs-lookup"><span data-stu-id="99c53-402">*Version 1910 (Build 12130.20112)*</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)
[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)
[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a><span data-ttu-id="99c53-406">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="99c53-406">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="99c53-407">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-407">Excel</span></span>

- <div><span data-ttu-id="99c53-408">解決從 OneDrive 以物件形式插入檔案的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-408">Resolved an issue in inserting files as object from OneDrive</span></span></div>


- <div><span data-ttu-id="99c53-409">解決無法將超連結格式正確套用至部分內容的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-409">Resolved an issue where the hyperlink format could not be properly applied to some content</span></span></div>


- <div><span data-ttu-id="99c53-410">解決含有結構化絕對參考的公式可能無法正確調整的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-410">Resolved an issue where formulas containing structured absolute references may be adjusted incorrectly</span></span></div>


- <div><span data-ttu-id="99c53-411">解決在目前的 Office 版本中開啟在舊版 Office 中建立的活頁簿時，可能導致 Excel 懸置的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-411">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office</span></span></div>


- <div><span data-ttu-id="99c53-412">解決從 Excel 複製的內容，在貼上到其他 Office 應用程式時，可能無法正確顯示的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-412">Resolved an issue where content copied from Excel could appear incorrect when pasted into other Office applications</span></span></div>


- <div><span data-ttu-id="99c53-413">修正以校正使用圖表範本插入圖表時，預覽中使用的色彩</span><span class="sxs-lookup"><span data-stu-id="99c53-413">Fix to correct colors used in previews when inserting charts using chart templates</span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="99c53-414">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-414">PowerPoint</span></span>

- <div><span data-ttu-id="99c53-415">已發現 ARC 裝置在 AirSpace WinComp 下執行時，可能會遺失連線的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-415">Identified an issue where ARC Devices could lose connection when running under AirSpace WinComp</span></span></div>


### <a name="word"></a><span data-ttu-id="99c53-416">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-416">Word</span></span>

- <div><span data-ttu-id="99c53-417">解決從 OneDrive 以物件形式插入檔案的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-417">Resolved an issue in inserting files as object from OneDrive</span></span></div>


- <div><span data-ttu-id="99c53-418">改善復原步驟，以<span>修正會導致從電子郵件執行緒中刪除圖形內容的問題。&nbsp;</span></span><span class="sxs-lookup"><span data-stu-id="99c53-418">Improved our recovery steps to f<span>ix an issue that caused graphical content to get deleted from email threads.&nbsp;</span></span></span></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1910-october-04"></a><span data-ttu-id="99c53-420">版本 1910：10 月 4 日</span><span class="sxs-lookup"><span data-stu-id="99c53-420">Version 1910: October 04</span></span>
<span data-ttu-id="99c53-421">*版本 1910 (組建 12126.20000)*</span><span class="sxs-lookup"><span data-stu-id="99c53-421">*Version 1910 (Build 12126.20000)*</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="99c53-423">功能更新</span><span class="sxs-lookup"><span data-stu-id="99c53-423">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="99c53-424">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-424">Excel</span></span>

- <span data-ttu-id="99c53-425">**資料視覺化工具增益集：** 從 Excel 快速建立 Visio 流程圖。</span><span class="sxs-lookup"><span data-stu-id="99c53-425">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="99c53-426">深入了解</span><span class="sxs-lookup"><span data-stu-id="99c53-426">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a><span data-ttu-id="99c53-429">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="99c53-429">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="99c53-430">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-430">Excel</span></span>

- <div><span data-ttu-id="99c53-431"><span>我們已修正 [預覽列印] 中的列印範圍不正確的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-431"><span>We fixed an issue where the print area in print preview was not correct</span></span></span></div>


- <div><span data-ttu-id="99c53-432"><span>我們已修正可能會讓樞紐分析表在共同撰寫工作階段期間無法重新整理的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-432"><span>We fixed an issue which could have prevented pivot tables from being refreshed during a co-authoring session</span></span></span></div>


### <a name="access"></a><span data-ttu-id="99c53-433">Access</span><span class="sxs-lookup"><span data-stu-id="99c53-433">Access</span></span>

- <div><span data-ttu-id="99c53-434">我們已修正當使用共用資料庫時，使用者可能收到&quot;不一致的狀態&quot;錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-434">We fixed an issue where users could receive an &quot;inconsistent state&quot; error when using a shared database.</span></span></div>


### <a name="outlook"></a><span data-ttu-id="99c53-435">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-435">Outlook</span></span>

- <div><span data-ttu-id="99c53-436"><span>我們已修正導致郵件資料夾重複的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-436"><span>We fixed an issue which could have caused duplication of mail folders</span></span></span></div>


- <div><span data-ttu-id="99c53-437"><span>我們已修正當嘗試傳送 s/MIME 加密電子郵件時，可能會導致錯誤訊息的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-437"><span>We fixed an issue which could have caused an incorrect error message when attempting to send s/MIME encrypted e-mail</span></span></span></div>


- <div><span data-ttu-id="99c53-438"><span>我們已修正當使用者收到來自 Skype 的「未接的交談」訊息時，有時可能會導致當機的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-438"><span>We fixed an issue which could sometimes result in a crash when a user receives a 'Missed Conversation' message from Skype</span></span></span></div>


- <div><span data-ttu-id="99c53-439"><span>我們已修正可能會造成記憶體洩漏的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-439"><span>We fixed an issue which could have resulted in a memory leak</span></span></span></div>


- <div><span data-ttu-id="99c53-440"><span>我們已修正當儲存為草稿時，可能會導致寄件者名稱變更的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-440"><span>We fixed an issue which could have caused the senders name to change when saved as a draft</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="99c53-441">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-441">PowerPoint</span></span>

- <div><span></span></div><span data-ttu-id="99c53-442">我們已修正以下問題：在您將文字貼到投影片母片和投影片版面配置上的頁首/頁尾/投影片編號預留位置之後，造成 TextRanges 損壞</span><span class="sxs-lookup"><span data-stu-id="99c53-442">We fixed an issue which could cause TextRanges to become broken after pasting text into the header/footer/slide number placeholders on slide master and slide layout</span></span>


- <div><span></span></div><span data-ttu-id="99c53-443">我們已修正在使用超連結貼上文字時，無法建立超連結的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-443">We fixed an issue which prevented hyperlink from being created when pasting text with hyperlink</span></span>


- <div><span data-ttu-id="99c53-444">我們已修正造成統計資料無法正常運作的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-444">We fixed an issue which would prevent statistics from working correctly</span></span></div>


### <a name="word"></a><span data-ttu-id="99c53-445">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-445">Word</span></span>

- <div><span data-ttu-id="99c53-446"><span>我們已修正未確認字型色彩的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-446"><span>We fixed an issue where font colors were not being committed</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="99c53-447">Office 套件</span><span class="sxs-lookup"><span data-stu-id="99c53-447">Office Suite</span></span>

- <div><span data-ttu-id="99c53-448">我們已修正在停用功能後，可能會提供版本歷程記錄的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-448">We fixed an issue which could offer version history when that feature was disabled</span></span></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1910-september-27"></a><span data-ttu-id="99c53-450">版本 1910：9 月 27 日</span><span class="sxs-lookup"><span data-stu-id="99c53-450">Version 1910: September 27</span></span>
<span data-ttu-id="99c53-451">*版本：1910 (組建 12119.20000)*</span><span class="sxs-lookup"><span data-stu-id="99c53-451">*Version 1910 (Build 12119.20000)*</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)
[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)
[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a><span data-ttu-id="99c53-455">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="99c53-455">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="99c53-456">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-456">Excel</span></span>

- <div><span data-ttu-id="99c53-457"><span>我們已修正當變更系列集合時，可能會導致散佈折線圖無法正確呈現的問題。</span></span><span class="sxs-lookup"><span data-stu-id="99c53-457"><span>We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="99c53-458">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-458">Outlook</span></span>

- <div><span data-ttu-id="99c53-459"><span>我們已修正了當與共享行事曆資料夾互動時，可能會報告權限錯誤的問題。</span></span><span class="sxs-lookup"><span data-stu-id="99c53-459"><span>We fixed an issue which could have reported permission errors when interacting with shared calendar folders</span></span></span></div>


- <div><span data-ttu-id="99c53-460"><span>我們已修正了使用者可能會無法新增附件至行事曆的問題。</span></span><span class="sxs-lookup"><span data-stu-id="99c53-460"><span>We fixed an issue which could have prevented users from adding attachments to calendars</span></span></span></div>


- <div><span data-ttu-id="99c53-461"><span>我們已修正了當回覆數位簽章的郵件時，導致顯示錯誤訊息的問題。</span></span><span class="sxs-lookup"><span data-stu-id="99c53-461"><span>We fixed an issue which caused error messages to display when replying to a digitally signed message</span></span></span></div>


### <a name="word"></a><span data-ttu-id="99c53-462">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-462">Word</span></span>

- <div><span data-ttu-id="99c53-463"><span>我們已修正列印到 Deskjet 印表機時，可能會導致縮放問題的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-463"><span>We fixed an issue which could have caused scaling issues when printing to Deskjet printers</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="99c53-464">Office 套件</span><span class="sxs-lookup"><span data-stu-id="99c53-464">Office Suite</span></span>

- <div><span data-ttu-id="99c53-465"><span>我們已修正中等粗體文字樣式不正確的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-465"><span>We fixed an issue where medium bold text could be incorrectly styled</span></span></span></div>


- <div><span data-ttu-id="99c53-466"><span>我們已修正當關閉具有擱置上傳的檔案時，使用者收到不正確錯誤訊息的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-466"><span>We fixed an issue where a user could be given an incorrect error message when closing a file with a pending upload</span></span></span></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1910-september-20"></a><span data-ttu-id="99c53-468">版本 1910：9 月 20 日</span><span class="sxs-lookup"><span data-stu-id="99c53-468">Version 1910: September 20</span></span>
<span data-ttu-id="99c53-469">*版本：1910 (組建 12112.20000)*</span><span class="sxs-lookup"><span data-stu-id="99c53-469">*Version 1910 (Build 12112.20000)*</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a><span data-ttu-id="99c53-473">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="99c53-473">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="99c53-474">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-474">Excel</span></span>

- <div><span data-ttu-id="99c53-475"><span>我們已修正 Excel 有時候會在啟動時發生懸置的問題。</span></span><span class="sxs-lookup"><span data-stu-id="99c53-475"><span>We fixed an issue where Excel could sometimes hang at launch</span></span></span></div>

### <a name="outlook"></a><span data-ttu-id="99c53-476">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-476">Outlook</span></span>

- <div><span data-ttu-id="99c53-477"><span>我們大幅改善了當有大量會議室可供選擇時，會議室選取的效能。</span></span><span class="sxs-lookup"><span data-stu-id="99c53-477"><span>We significantly improved the performance of room selection when there are a large number of rooms available</span></span></span></div>


- <div><span data-ttu-id="99c53-478"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">我們已修正在 Office 365.中移轉至新式驗證時，擁有 Outlook 多個信箱的客戶無法進行信箱同步處理的問題。</span></span><span class="sxs-lookup"><span data-stu-id="99c53-478"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">We fixed an issue that can prevent mailbox sync for customers with multiple mailboxes in Outlook when migrating to modern authentication in Office 365.</span></span></span><br></div>


- <div><span data-ttu-id="99c53-479"><span>我們已修正簽章標籤中某些字元不會顯示在下拉式功能表中的問題。</span></span><span class="sxs-lookup"><span data-stu-id="99c53-479"><span>We fixed an issue where some characters in signature labels would not display in the dropdown menu</span></span></span></div>


### <a name="project"></a><span data-ttu-id="99c53-480">Project</span><span class="sxs-lookup"><span data-stu-id="99c53-480">Project</span></span>

- <div><span data-ttu-id="99c53-481"><span>我們修正了使用本機資源取代企業資源時，可能會導致當機的問題。</span></span><span class="sxs-lookup"><span data-stu-id="99c53-481"><span>We fixed an issue which could cause a crash when replacing an enterprise resource with a local resource</span></span></span></div>


### <a name="word"></a><span data-ttu-id="99c53-482">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-482">Word</span></span>

- <div><span data-ttu-id="99c53-483"><span>我們已修正 [草稿模式] 中可能會導致同步捲動無法正常運作的問題。</span></span><span class="sxs-lookup"><span data-stu-id="99c53-483"><span>We fixed an issue which could prevent synchronous scrolling from working properly in draft view</span></span></span></div>


- <div><span data-ttu-id="99c53-484">我們已修正第一次儲存文件後可能導致 [工具提示] 無法正確顯示的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-484">We fixed an issue which could prevent Tool Tips from displaying properly after saving a document for the first time</span></span></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1910-september-13"></a><span data-ttu-id="99c53-486">版本 1910：9 月 13 日</span><span class="sxs-lookup"><span data-stu-id="99c53-486">Version 1910: September 13</span></span>
<span data-ttu-id="99c53-487">*版本 1910 (組建 12105.20000)*</span><span class="sxs-lookup"><span data-stu-id="99c53-487">*Version 1910 (Build 12105.20000)*</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a><span data-ttu-id="99c53-489">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="99c53-489">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="99c53-490">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-490">Excel</span></span>

- <div><span data-ttu-id="99c53-491"><span>我們已修正使用者在部分受保護的工作表中無法貼上超連結的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-491"><span>We fixed an issue which could prevent a user from pasting hyperlinks in some protected sheets</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="99c53-492">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-492">Outlook</span></span>

- <div><span data-ttu-id="99c53-493"><span>我們已修正 UI 可能停滯在精簡檢視中的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-493"><span>We fixed an issue where the UI could get stuck in a compact view</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="99c53-494">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-494">PowerPoint</span></span>

- <div><span data-ttu-id="99c53-495"><span>我們已修正使用者可能會在列印為 PDF 時發生錯誤的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-495"><span>We fixed an issue where a user could experience an error upon printing to PDF</span></span></span></div>


### <a name="project"></a><span data-ttu-id="99c53-496">Project</span><span class="sxs-lookup"><span data-stu-id="99c53-496">Project</span></span>

- <div><span data-ttu-id="99c53-497"><span>我們已修正在摘要任務上<span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">變更工時值時，如果已啟用受保護的工作則可能會造成當機的問題</span></span></span><span class="sxs-lookup"><span data-stu-id="99c53-497"><span>We fixed an issue where <span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">changes to a work value on a summary task could cause a crash if protected work is enabled</span></span></span></span></div>


- <span data-ttu-id="99c53-498"><font size=2 style="background-color:rgb(255, 255, 255);">我們已修正可能會禁止將事件同步處理到企業行事曆功能的問題</font></span><span class="sxs-lookup"><span data-stu-id="99c53-498"><font size=2 style="background-color:rgb(255, 255, 255);">We fixed an issue which could inhibit the ability to sync events with enterprise calendars</font></span></span>


### <a name="office-suite"></a><span data-ttu-id="99c53-499">Office 套件</span><span class="sxs-lookup"><span data-stu-id="99c53-499">Office Suite</span></span>

- <div><span data-ttu-id="99c53-500"><span>我們已修正可能會導致重複警告以捨棄本機檔案版本的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-500"><span>We fixed an issue which could cause a repeated warning to discard local versions of a file</span></span></span></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1910-september-06"></a><span data-ttu-id="99c53-502">版本 1910：9 月 6 日</span><span class="sxs-lookup"><span data-stu-id="99c53-502">Version 1910: September 06</span></span>
<span data-ttu-id="99c53-503">*版本 1910 (組建 12030.20004)*</span><span class="sxs-lookup"><span data-stu-id="99c53-503">*Version 1910 (Build 12030.20004)*</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="99c53-505">功能更新</span><span class="sxs-lookup"><span data-stu-id="99c53-505">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="99c53-506">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-506">Excel</span></span>

- <span data-ttu-id="99c53-507">**準備、設定、繪圖：** 抓取 Surface 手寫筆之後, 您就可以開始繪製。</span><span class="sxs-lookup"><span data-stu-id="99c53-507">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="99c53-508">深入了解</span><span class="sxs-lookup"><span data-stu-id="99c53-508">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="powerpoint"></a><span data-ttu-id="99c53-509">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-509">PowerPoint</span></span>

- <span data-ttu-id="99c53-510">**準備、設定、繪圖：** 抓取 Surface 手寫筆之後, 您就可以開始繪製。</span><span class="sxs-lookup"><span data-stu-id="99c53-510">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="99c53-511">深入了解</span><span class="sxs-lookup"><span data-stu-id="99c53-511">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="word"></a><span data-ttu-id="99c53-512">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-512">Word</span></span>

- <span data-ttu-id="99c53-513">**準備、設定、繪圖：** 抓取 Surface 手寫筆之後, 您就可以開始繪製。</span><span class="sxs-lookup"><span data-stu-id="99c53-513">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="99c53-514">深入了解</span><span class="sxs-lookup"><span data-stu-id="99c53-514">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a><span data-ttu-id="99c53-517">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="99c53-517">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="99c53-518">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-518">Excel</span></span>

- <div><span data-ttu-id="99c53-519"><span>我們已修正可能會導致功能區中的字型名稱與正在使用的字型不同的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-519"><span>We fixed an issue which could cause the font name in the ribbon to be different from the font being used</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="99c53-520">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-520">Outlook</span></span>

- <div><span data-ttu-id="99c53-521"><span>我們已修正當 Internet Explorer 中的受限制網站停用受保護模式時，可能會導致 Outlook 不適當的資源消耗的問題。</span></span><span class="sxs-lookup"><span data-stu-id="99c53-521"><span>We fixed an issue that could result in inappropriate resource consumption by Outlook when Protected Mode is disabled for Restricted Sites in Internet Explorer</span></span></span></div>


- <div><span data-ttu-id="99c53-522"><span>我們已修正當貼上 ANSI 原始碼的文字時, 有時可能會導致顯示 Unicode 字元的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-522"><span>We fixed an issue which could sometimes cause Unicode characters to appear when pasting text from an ANSI source</span></span></span></div>


- <div><span data-ttu-id="99c53-523"><span>我們已修正有些使用者在群組排程檢視中會不正確地顯示為離線的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-523"><span>We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span></span></div>


### <a name="word"></a><span data-ttu-id="99c53-524">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-524">Word</span></span>

- <div><span data-ttu-id="99c53-525"><span>我們已修正表格格式設定可能遺失的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-525"><span>We fixed an issue where table formatting could be lost</span></span></span></div>


- <div><span data-ttu-id="99c53-526"><span>我們已修正導致 Ctrl+V 鍵盤快速鍵中斷的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-526"><span>We fixed an issue which could break the ctrl+v keyboard shortcut</span></span></span></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1909-august-30"></a><span data-ttu-id="99c53-528">版本 1909：8 月 30 日</span><span class="sxs-lookup"><span data-stu-id="99c53-528">Version 1909: August 30</span></span>
<span data-ttu-id="99c53-529">*版本 1909 (組建 12026.20000)*</span><span class="sxs-lookup"><span data-stu-id="99c53-529">*Version 1909 (Build 12026.20000)*</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="99c53-531">功能更新</span><span class="sxs-lookup"><span data-stu-id="99c53-531">Feature updates</span></span>

### <a name="access"></a><span data-ttu-id="99c53-532">Access</span><span class="sxs-lookup"><span data-stu-id="99c53-532">Access</span></span>

- <span data-ttu-id="99c53-533">**快速尋找連結資料表：** 新的搜尋方塊可讓您輕鬆尋找連結資料表。</span><span class="sxs-lookup"><span data-stu-id="99c53-533">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="99c53-534">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-534">PowerPoint</span></span>

- <span data-ttu-id="99c53-535">**將圖例另存成 SVG：** 將圖表、圖形或其他圖例另存成可縮放向量圖形，其可調整大小，且不損失影像品質。</span><span class="sxs-lookup"><span data-stu-id="99c53-535">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="99c53-536">深入了解</span><span class="sxs-lookup"><span data-stu-id="99c53-536">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a><span data-ttu-id="99c53-539">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="99c53-539">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="99c53-540">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-540">Excel</span></span>

- <div><span data-ttu-id="99c53-541"><span>我們已修正&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">敏感度</span>的 keytip &nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">與其他 keytip 相衝突的問題。</span></span></span><span class="sxs-lookup"><span data-stu-id="99c53-541"><span>We fixed an issue where the keytip for&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">Sensitivity </span>was&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">conflicting with another keytip.</span></span></span></span></div>

- <div><span data-ttu-id="99c53-542"><span>我們已修正在嘗試儲存的同時使用共用活頁簿時所發生的問題。</span></span><span class="sxs-lookup"><span data-stu-id="99c53-542"><span>We fixed an issue that occurred while working on a shared workbook when trying to save.</span></span></span></div>

- <div><span data-ttu-id="99c53-543"><span>我們已修正 Excel 只列出位於「\Excel\Add-in Manager」登錄值中前 16 個增益集的問題。<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></span><span class="sxs-lookup"><span data-stu-id="99c53-543"><span>We fixed an issue where Excel only lists the first 16 addins located in the '\Excel\Add-in Manager' registry values.<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></span></span></div>


- <div><span data-ttu-id="99c53-544"><span>我們已修正 Frequency 函數會傳回不正確結果的問題。</span></span><span class="sxs-lookup"><span data-stu-id="99c53-544"><span>We fixed an issue where the function Frequency() returns incorrect results.</span></span></span></div>


- <div><span data-ttu-id="99c53-545"><span>我們已大幅提升透過色彩篩選的效能。</span></span><span class="sxs-lookup"><span data-stu-id="99c53-545"><span>We have significantly improved the performance of filtering by color.</span></span></span></div>


- <div><span data-ttu-id="99c53-546"><span>我們已修正 Surface 使用者移動滑鼠可能解譯為按一下滑鼠事件的問題。</span></span><span class="sxs-lookup"><span data-stu-id="99c53-546"><span>We fixed an issue for Surface users where moving the mouse could be interpreted as a mouse click event.</span></span></span></div>


- <div><span data-ttu-id="99c53-547"><span>我們已修正在 [尋找/取代] 對話方塊中鍵盤無法瀏覽的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-547"><span>We fixed an issue which prevented keyboard navigation in the Find/Replace dialog</span></span></span></div>


- <div><span data-ttu-id="99c53-548"><span>我們已修正某些字型名稱無法正確顯示的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-548"><span>We fixed an issue where the name of some fonts were not displayed correctly</span></span></span></div>


- <div><span data-ttu-id="99c53-549"><span>我們已修正 CSV 無法顯示為支援的檔案類型的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-549"><span>We fixed an issue which prevented CSV from appearing as a supported file type</span></span></span></div>


### <a name="access"></a><span data-ttu-id="99c53-550">Access</span><span class="sxs-lookup"><span data-stu-id="99c53-550">Access</span></span>

- <div><span data-ttu-id="99c53-551">我們已修正當使用共用資料庫時，使用者可能收到&quot;不一致的狀態&quot;錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-551">We fixed an issue where users could receive an &quot;inconsistent state&quot; error when using a shared database.</span></span></div>


- <div><span data-ttu-id="99c53-552"><span>我們已修正可能導致日期選擇器在不該出現時出現的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-552"><span>We fixed an issue which could cause the date picker to appear when it shouldn't</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="99c53-553">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-553">Outlook</span></span>

- <div><span data-ttu-id="99c53-554"><span>我們已修正部分 POP3 使用者無法顯示 HTML 內容的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-554"><span>We fixed an issue which prevented HTML content from appearing for some POP3 users</span></span></span></div>


- <div><span data-ttu-id="99c53-555"><span>我們已修正在無法使用的環境中工作時，從連絡人卡片的溢位功能表移除非功能性「Planner」連結的問題。</span></span><span class="sxs-lookup"><span data-stu-id="99c53-555"><span>We fixed an issue to remove non-functional 'Planner' link from the overflow menu in the contact card when working in environments where it is not available.</span></span></span></div>

### <a name="onenote"></a><span data-ttu-id="99c53-556">OneNote</span><span class="sxs-lookup"><span data-stu-id="99c53-556">OneNote</span></span>

- <div><span data-ttu-id="99c53-557"><span>我們已修正 &nbsp;OneNote 背景同步處理有時候會竊取焦點的問題。</span></span><span class="sxs-lookup"><span data-stu-id="99c53-557"><span>We fixed an issue where&nbsp;OneNote background sync was sometimes stealing focus.</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="99c53-558">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-558">PowerPoint</span></span>

- <div><span data-ttu-id="99c53-559"><span>我們已修正會影響 3D 盤旋的旋轉方向的問題。</span></span><span class="sxs-lookup"><span data-stu-id="99c53-559"><span>We fixed an issue which would affect the rotation orientation of a 3D Turntable.</span></span></span></div>

- <div><span data-ttu-id="99c53-560"><span>我們已修正如果超連結包含特殊字元便無法運作的問題。</span></span><span class="sxs-lookup"><span data-stu-id="99c53-560"><span>We fixed an issue which prevented some hyperlinks from working if they contained special characters.</span></span></span></div>

- <div><span data-ttu-id="99c53-561"><span>我們已修正會造成的同時開啟多個註解窗格的問題。</span></span><span class="sxs-lookup"><span data-stu-id="99c53-561"><span>We fixed an issue which caused multiple comment panes to open at the same time.</span></span></span></div>

### <a name="project"></a><span data-ttu-id="99c53-562">Project</span><span class="sxs-lookup"><span data-stu-id="99c53-562">Project</span></span>

- <div><span data-ttu-id="99c53-563"><span>我們已修正在列印團隊規劃檢視之後可能會導致當機的問題。</span></span><span class="sxs-lookup"><span data-stu-id="99c53-563"><span>We fixed an issue which could sometimes cause a crash after printing a Team Planner view.</span></span></span></div>

### <a name="word"></a><span data-ttu-id="99c53-564">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-564">Word</span></span>

- <div><span data-ttu-id="99c53-565">我們已<span>修正直排文字方塊中多位元組字元在閱讀檢視中顯示重疊的問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-565">We f<span>ixed an issue where multi-byte characters in vertical text box are shown overlapped in reading view.</span></span><br></span></div>

- <div><span data-ttu-id="99c53-566"><span>我們&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">已修正當使用者在增益集中採取動作時，找不到日文明信片和賀卡相關增益集資源的問題。</span></span></span><span class="sxs-lookup"><span data-stu-id="99c53-566"><span>We&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">fixed an issue where Japanese post card and greeting card related addin resources are not found when the user takes action in the addin wizard.</span></span></span></span></div>

- <div><span data-ttu-id="99c53-567"><span>我們已修正在受保護的檢視中的標題列使用者介面會造成問題的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-567"><span>We fixed an issue which could cause issues with the Title Bar User Interface when in Protected View</span></span></span></div>

### <a name="office-suite"></a><span data-ttu-id="99c53-568">Office 套件</span><span class="sxs-lookup"><span data-stu-id="99c53-568">Office Suite</span></span>

- <div><span data-ttu-id="99c53-569"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"> 我們已修正當您在含有一般圖形和連接器圖形的選擇上變更圖形時的損毀檔案問題。</span></span></span><span class="sxs-lookup"><span data-stu-id="99c53-569"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"> We fixed a corrupt file issue when you Change Shape on a selection that contains both a normal shape and a connector shape.</span></span></span></span></div>

- <div><span data-ttu-id="99c53-570"><span>我們已修正<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">從多個外部顯示器使用固定/解除固定時會造成問題的問題。</span></span></span><span class="sxs-lookup"><span data-stu-id="99c53-570"><span>We fixed an issue that <span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">caused a problem in applications when using dock/undock from multiple external displays. </span></span></span></span></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="august-23-2019br"></a><span data-ttu-id="99c53-572">**2019 年 8 月 23 日**</span><span class="sxs-lookup"><span data-stu-id="99c53-572">**August 23, 2019**</span></span><br/>
<span data-ttu-id="99c53-573">版本 1909 (組建 12015.20004)</span><span class="sxs-lookup"><span data-stu-id="99c53-573">Version 1909 (Build 12015.20004)</span></span><br/>



## <a name="non-security-updates"></a><span data-ttu-id="99c53-574">非安全性更新：</span><span class="sxs-lookup"><span data-stu-id="99c53-574">Non-security updates:</span></span>

### <a name="excel"></a><span data-ttu-id="99c53-575">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-575">Excel</span></span>

- <div><span data-ttu-id="99c53-576"><span>我們已大幅改善刪除合併儲存格的資料行的效能</span></span><span class="sxs-lookup"><span data-stu-id="99c53-576"><span>We significantly improved the performance of deleting columns with merged cells</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="99c53-577">Office 套件</span><span class="sxs-lookup"><span data-stu-id="99c53-577">Office Suite</span></span>

- <div><span data-ttu-id="99c53-578"><span>我們已修正在瀏覽器中檢視時，部分的 Unicode 字元可能會無法顯示的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-578"><span>We fixed an issue which could prevent some Unicode characters from being displayed when viewed in a browser</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="99c53-579">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-579">Outlook</span></span>

- <div><span data-ttu-id="99c53-580"><span>我們已修正可能會無法儲存檔案到 WebDAV 的位置的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-580"><span>We fixed an issue which could have prevented files from being saved to a WebDAV location</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="99c53-581">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-581">PowerPoint</span></span>

- <div><span data-ttu-id="99c53-582"><span>我們已修正當使用者點擊一個註解，但可能是另一個註解被選取的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-582"><span>We fixed an issue where a user would click on one comment, but another comment would be selected</span></span></span></div>





## <a name="august-16-2019br"></a><span data-ttu-id="99c53-583">**2019 年 8 月 16 日**</span><span class="sxs-lookup"><span data-stu-id="99c53-583">**August 16, 2019**</span></span><br/>
<span data-ttu-id="99c53-584">版本 1909 (組建 12013.20000)</span><span class="sxs-lookup"><span data-stu-id="99c53-584">Version 1909 (Build 12013.20000)</span></span><br/>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="99c53-585">PowerPoint 功能更新：</span><span class="sxs-lookup"><span data-stu-id="99c53-585">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="99c53-586">**列印講義上的投影片編號：** 投影片編號會自動包含在講義上。</span><span class="sxs-lookup"><span data-stu-id="99c53-586">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="99c53-587">由您決定將其保留或關閉。</span><span class="sxs-lookup"><span data-stu-id="99c53-587">Leave them on, turn them off, it's all up to you.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="99c53-588">非安全性更新：</span><span class="sxs-lookup"><span data-stu-id="99c53-588">Non-security updates:</span></span>

### <a name="excel"></a><span data-ttu-id="99c53-589">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-589">Excel</span></span>

- <div><span data-ttu-id="99c53-590"><span>我們已修正可能會導致 AutoSave 自動開啟的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-590"><span>We fixed an issue which could cause AutoSave to become enabled</span></span></span></div>


- <div><span data-ttu-id="99c53-591">我們已修正可能會導致不正確計算儲存格高度的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-591">We fixed an issue which could result in cell heights being measured inaccurately</span></span></div>


### <a name="office-suite"></a><span data-ttu-id="99c53-592">Office 套件</span><span class="sxs-lookup"><span data-stu-id="99c53-592">Office Suite</span></span>

- <div><span data-ttu-id="99c53-593"><span>我們已修正了一個問題，將能大幅改善註解功能的效能</span></span><span class="sxs-lookup"><span data-stu-id="99c53-593"><span>We fixed an issue which significantly improves the performance of the Comments feature</span></span></span></div>


- <div><span data-ttu-id="99c53-594"><span>我們已修正搜尋時使用方向鍵可能會造成當機的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-594"><span>We fixed an issue which could cause a crash when using arrow keys while in search</span></span></span></div>


- <div><span data-ttu-id="99c53-595"><span>我們已修正如果將 @ 符號放在特定字元後，可能會無法使用 @ 提及的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-595"><span>We fixed an issue which could prevent an @ mention if the @ symbol was placed after certain characters</span></span></span></div>


- <div><span data-ttu-id="99c53-596"><span>我們已修正在刪除 @ 提及時，可能會導致當機的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-596"><span>We fixed an issue which could sometimes cause a crash when deleting @ mentions</span></span></span></div>


- <div><span data-ttu-id="99c53-597"><span>我們已修正無法在註解卡正確顯示 Emoji 的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-597"><span>We fixed an issue which prevented emojis from displaying correctly in comment cards</span></span></span></div>


- <div><span data-ttu-id="99c53-598"><span>我們已修正使用中​的​剪貼簿​​有時可能會導致當機的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-598"><span>We fixed an issue with Active Clipboard which could sometimes result in a crash</span></span></span></div>


- <div><span data-ttu-id="99c53-599"><span>我們已修正可能會導致快速存取工具列按鈕停止運作的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-599"><span>We fixed an issue which could cause the Quick Access Toolbar buttons to stop working</span></span></span></div>


- <div><span data-ttu-id="99c53-600"><span>我們已修正無法讓文件格式設定預覽切換到背景的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-600"><span>We fixed an issue which could prevent the Document Formatting Preview from switching to the background</span></span></span></div>

### <a name="onenote"></a><span data-ttu-id="99c53-601">OneNote</span><span class="sxs-lookup"><span data-stu-id="99c53-601">OneNote</span></span>

- <span data-ttu-id="99c53-602">我們已修正當 Office 佈景主題設為黑色，區段下拉式清單中的區段名稱顯示為空白的問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-602">We fixed an issue where the names of sections appear blank in the section dropdown list when Office Theme is set to Black.</span></span>

### <a name="outlook"></a><span data-ttu-id="99c53-603">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-603">Outlook</span></span>

- <div><span data-ttu-id="99c53-604"><span>我們已修正在傳送​​事件時可能會導致 Outlook 重複獲取和失去焦點的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-604"><span>We fixed an issue with Send Events which could cause Outlook to repeatedly gain and lose focus</span></span></span></div>


- <div><span data-ttu-id="99c53-605"><span>我們已修正無法從工作資料夾的捷徑張貼回覆的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-605"><span>We fixed an issue which prevented the Post Reply to Folder shortcut from working</span></span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="99c53-606">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-606">PowerPoint</span></span>

- <div><span data-ttu-id="99c53-607"><span>我們已修正受保護的檢視有時候可能會在合作時造成問題的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-607"><span>We fixed an issue with Protected View which could sometimes cause problems when collaborating</span></span></span></div>


- <div><span data-ttu-id="99c53-608"><span>我們已修正可能無法正確顯示註解窗格中工作的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-608"><span>We fixed an issue which could prevent tasks in comment panes from displaying properly</span></span></span></div>


- <div><span data-ttu-id="99c53-609"><span>我們已修正插入新投影片時可能會造成當機的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-609"><span>We fixed an issue which could cause a crash when inserting new slides</span></span></span></div>


### <a name="user-lifecycle"></a><span data-ttu-id="99c53-610">使用者生命週期</span><span class="sxs-lookup"><span data-stu-id="99c53-610">User Lifecycle</span></span>

- <div><span data-ttu-id="99c53-611"><span>我們已修正有時候可能會導致訂閱功能消失的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-611"><span>We fixed an issue which could sometimes result in subscription features disappearing</span></span></span></div>


### <a name="word"></a><span data-ttu-id="99c53-612">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-612">Word</span></span>

- <div><span data-ttu-id="99c53-613"><span>我們已修正如果超連結包含特定字元，則超連結可能會中斷的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-613"><span>We fixed an issue where hyperlinks could be broken if the hyperlink contained certain characters</span></span></span></div>


- <div><span data-ttu-id="99c53-614"><span>我們已修正在檢視影像註解時，影像可能會調整至不正確大小的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-614"><span>We fixed an issue where images could be improperly sized when viewing a comment for that image</span></span></span></div>


- <div><span data-ttu-id="99c53-615"><span>我們已修正項目符號清單下拉式功能表有時可能會導致當機的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-615"><span>We fixed an issue with the Bullet List drop down menu which could sometimes result in a crash</span></span></span></div>





## <a name="august-09-2019br"></a><span data-ttu-id="99c53-616">**2019 年 8 月 9 日**</span><span class="sxs-lookup"><span data-stu-id="99c53-616">**August 09, 2019**</span></span><br/>
<span data-ttu-id="99c53-617">版本 1909 (組建 12001.20000)</span><span class="sxs-lookup"><span data-stu-id="99c53-617">Version 1909 (Build 12001.20000)</span></span><br/>

### <a name="excel-feature-updates"></a><span data-ttu-id="99c53-618">Excel 功能更新：</span><span class="sxs-lookup"><span data-stu-id="99c53-618">Excel Feature updates:</span></span>

- <span data-ttu-id="99c53-619">**共同作業變得更容易：** 共同撰寫的增強功能表示，使用條件式格式設定、儲存格樣式等等時，您的變更會與共同作業者的變更順暢地合併。</span><span class="sxs-lookup"><span data-stu-id="99c53-619">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>


- <span data-ttu-id="99c53-620">**搜尋並享受：** 我們對插入圖示新增了搜尋，讓您易於找到您要的圖示。</span><span class="sxs-lookup"><span data-stu-id="99c53-620">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="99c53-621">而當您選取時，[插入] 按鈕會告知您已經選取的數量。</span><span class="sxs-lookup"><span data-stu-id="99c53-621">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="office-suite-feature-updates"></a><span data-ttu-id="99c53-622">Office 套件功能更新：</span><span class="sxs-lookup"><span data-stu-id="99c53-622">Office Suite Feature updates:</span></span>

- <span data-ttu-id="99c53-623">**新的 Office 應用程式圖示：** 重新設計的應用程式圖示，可反映簡單、功能強大且智慧型的 Office 體驗</span><span class="sxs-lookup"><span data-stu-id="99c53-623">**New Office app icons:** Redesigned app icons to reflect the simple, powerful, and intelligent experiences of Office</span></span>


### <a name="outlook-feature-updates"></a><span data-ttu-id="99c53-624">Outlook 功能更新：</span><span class="sxs-lookup"><span data-stu-id="99c53-624">Outlook Feature updates:</span></span>

- <span data-ttu-id="99c53-625">**抵禦攻擊的進階防護：** 使用 Office 365 進階威脅防護，您會受到保護，不受電子郵件主旨、附加的郵件、簽署的郵件、網路路徑內超連結的攻擊。</span><span class="sxs-lookup"><span data-stu-id="99c53-625">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>


- <span data-ttu-id="99c53-626">**搜尋並享受：** 我們對插入圖示新增了搜尋，讓您易於找到您要的圖示。</span><span class="sxs-lookup"><span data-stu-id="99c53-626">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="99c53-627">而當您選取時，[插入] 按鈕會告知您已經選取的數量。</span><span class="sxs-lookup"><span data-stu-id="99c53-627">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="99c53-628">PowerPoint 功能更新：</span><span class="sxs-lookup"><span data-stu-id="99c53-628">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="99c53-629">**搜尋並享受：** 我們對插入圖示新增了搜尋，讓您易於找到您要的圖示。</span><span class="sxs-lookup"><span data-stu-id="99c53-629">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="99c53-630">而當您選取時，[插入] 按鈕會告知您已經選取的數量。</span><span class="sxs-lookup"><span data-stu-id="99c53-630">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="word-feature-updates"></a><span data-ttu-id="99c53-631">Word 功能更新：</span><span class="sxs-lookup"><span data-stu-id="99c53-631">Word Feature updates:</span></span>

- <span data-ttu-id="99c53-632">**其他人更快速看到您的變更：** 共同撰寫增強功能表示，共同作業者可較以往更快速看到您的變更。</span><span class="sxs-lookup"><span data-stu-id="99c53-632">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>


- <span data-ttu-id="99c53-633">**搜尋並享受：** 我們對插入圖示新增了搜尋，讓您易於找到您要的圖示。</span><span class="sxs-lookup"><span data-stu-id="99c53-633">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="99c53-634">而當您選取時，[插入] 按鈕會告知您已經選取的數量。</span><span class="sxs-lookup"><span data-stu-id="99c53-634">And when you're selecting, the Insert button tells you how many you've picked.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="99c53-635">非安全性更新：</span><span class="sxs-lookup"><span data-stu-id="99c53-635">Non-security updates:</span></span>

### <a name="outlook"></a><span data-ttu-id="99c53-636">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-636">Outlook</span></span>

- <div><span data-ttu-id="99c53-637"><span>我們已修正會導致會議收件者在取消會議後收到兩次通知的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-637"><span>We fixed an issue which caused meeting recipients to receive two notifications after a meeting was cancelled</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="99c53-638">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-638">PowerPoint</span></span>

- <div><span data-ttu-id="99c53-639"><span>我們已修正當使用者對圖形與圖示選取 [無外框] 或 [無填滿] 時會導致損毀的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-639"><span>We fixed an issue which could cause a crash when the user selected No Outline or No Fill for Shapes and Icons</span></span></span></div>





## <a name="august-02-2019br"></a><span data-ttu-id="99c53-640">**2019 年 8 月 2 日**</span><span class="sxs-lookup"><span data-stu-id="99c53-640">**August 02, 2019**</span></span><br/>
<span data-ttu-id="99c53-641">版本 1908 (組建 11929.20002)</span><span class="sxs-lookup"><span data-stu-id="99c53-641">Version 1908 (Build 11929.20002)</span></span><br/>

### <a name="excel-feature-updates"></a><span data-ttu-id="99c53-642">Excel 功能更新：</span><span class="sxs-lookup"><span data-stu-id="99c53-642">Excel Feature updates:</span></span>

- <span data-ttu-id="99c53-643">**轉換檔案，以改善協助工具功能：** 將您的檔案升級為現代格式，讓所有人更容易存取。</span><span class="sxs-lookup"><span data-stu-id="99c53-643">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="99c53-644">**將敏感度標籤套用至您的文件**：將敏感度標籤套用至您的檔案和電子郵件，使其符合貴組織的資訊保護原則。</span><span class="sxs-lookup"><span data-stu-id="99c53-644">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="outlook-feature-updates"></a><span data-ttu-id="99c53-645">Outlook 功能更新：</span><span class="sxs-lookup"><span data-stu-id="99c53-645">Outlook Feature updates:</span></span>

- <span data-ttu-id="99c53-646">**將敏感度標籤套用至您的文件**：將敏感度標籤套用至您的檔案和電子郵件，使其符合貴組織的資訊保護原則。</span><span class="sxs-lookup"><span data-stu-id="99c53-646">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="99c53-647">PowerPoint 功能更新：</span><span class="sxs-lookup"><span data-stu-id="99c53-647">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="99c53-648">**轉換檔案，以改善協助工具功能：** 將您的檔案升級為現代格式，讓所有人更容易存取。</span><span class="sxs-lookup"><span data-stu-id="99c53-648">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="99c53-649">**將敏感度標籤套用至您的文件**：將敏感度標籤套用至您的檔案和電子郵件，使其符合貴組織的資訊保護原則。</span><span class="sxs-lookup"><span data-stu-id="99c53-649">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="word-feature-updates"></a><span data-ttu-id="99c53-650">Word 功能更新：</span><span class="sxs-lookup"><span data-stu-id="99c53-650">Word Feature updates:</span></span>

- <span data-ttu-id="99c53-651">**轉換檔案，以改善協助工具功能：** 將您的檔案升級為現代格式，讓所有人更容易存取。</span><span class="sxs-lookup"><span data-stu-id="99c53-651">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="99c53-652">**用其他方式表達：** 當您想要以不同方式表達時，「重寫」功能可以幫助您。</span><span class="sxs-lookup"><span data-stu-id="99c53-652">**Say it another way:** When you want to say it differently, Rewrite is there to help.</span></span> <span data-ttu-id="99c53-653">重寫提供其他不同方式來表達您的詞彙。</span><span class="sxs-lookup"><span data-stu-id="99c53-653">Rewrite offers alternatives for finessing your phrases.</span></span>


- <span data-ttu-id="99c53-654">**將敏感度標籤套用至您的文件**：將敏感度標籤套用至您的檔案和電子郵件，使其符合貴組織的資訊保護原則。</span><span class="sxs-lookup"><span data-stu-id="99c53-654">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="99c53-655">非安全性更新：</span><span class="sxs-lookup"><span data-stu-id="99c53-655">Non-security updates:</span></span>

### <a name="access"></a><span data-ttu-id="99c53-656">Access</span><span class="sxs-lookup"><span data-stu-id="99c53-656">Access</span></span>
- <span data-ttu-id="99c53-657">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-657">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="99c53-658">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-658">Excel</span></span>

- <div><span data-ttu-id="99c53-659"><span>我們已修正了列印至 PDF 時，&quot;重複所有標籤&quot;看起來像已套用的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-659"><span>We fixed an issue which made it appear as though &quot;repeat all labels&quot; was applied when printing to a PDF</span></span></span></div>

### <a name="office-suite"></a><span data-ttu-id="99c53-660">Office 套件</span><span class="sxs-lookup"><span data-stu-id="99c53-660">Office Suite</span></span>

- <div><span data-ttu-id="99c53-661"><span>我們已修正了使用者可能無法從桌面開啟文件的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-661"><span>We fixed an issue which could have prevented users from opening a document from the desktop</span></span></span></div>

- <div><span data-ttu-id="99c53-662"><span>我們已修正了&quot;另一個安裝正在進行中&quot;的不正確錯誤訊息，可能導致無法升級的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-662"><span>We fixed an issue where an upgrade could be prevented by a incorrect error message of &quot;Another install in progress&quot;</span></span></span></div>

- <div><span data-ttu-id="99c53-663"><span>我們已修正了安全性更新安裝後，使用者可能會看到錯誤訊息的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-663"><span>We fixed an issue where a user could see error messages when security updates are installed</span></span></span></div>

- <div><span data-ttu-id="99c53-664"><span>我們已修正了可能會造成游標消失的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-664"><span>We fixed an issue which could cause the cursor to disappear</span></span></span></div>

- <div><span data-ttu-id="99c53-665"><span>我們已修正了使用者可能預設前往 [繪圖] 索引標籤而不是 [常用] 索引標籤的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-665"><span>We fixed an issue where a user could be defaulted to the draw tab instead of the home tab</span></span></span></div>

- <div><span data-ttu-id="99c53-666"><span>我們已修正了大型樹狀檢視可能會導致當機的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-666"><span>We fixed an issue where large tree views could result in a crash</span></span></span></div>

### <a name="outlook"></a><span data-ttu-id="99c53-667">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-667">Outlook</span></span>

- <div></div><span data-ttu-id="99c53-668"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">我們已修正了可能導致系統重複提示輸入密碼的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-668"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">We fixed an issue that can cause repeated password prompts</span></span></span>

- <div><span data-ttu-id="99c53-669"><span>我們已修正了可能無法正確查詢電子郵件地址的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-669"><span>We fixed an issue which could prevent an email address from being queried correctly</span></span></span></div>

- <div><span data-ttu-id="99c53-670"><span>我們已修正了可能導致使用者無法開啟由舊版 Outlook 建立之行事曆項目的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-670"><span>We fixed an issue which could prevent users from opening calendar items created by legacy versions of Outlook</span></span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="99c53-671">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-671">PowerPoint</span></span>

- <div><span data-ttu-id="99c53-672"><span>我們已修正了部分動畫無法開始的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-672"><span>We fixed an issue which could prevent some animations from starting</span></span></span></div>

### <a name="project"></a><span data-ttu-id="99c53-673">Project</span><span class="sxs-lookup"><span data-stu-id="99c53-673">Project</span></span>
- <span data-ttu-id="99c53-674">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-674">Various performance and stability fixes</span></span>

### <a name="word"></a><span data-ttu-id="99c53-675">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-675">Word</span></span>

- <div><span data-ttu-id="99c53-676"><span>我們已修正了註解的回覆以錯誤順序顯示的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-676"><span>We fixed an issue where replies to comments could appear out of order</span></span></span></div>

- <div><span data-ttu-id="99c53-677"><span>我們已修正了在某些情況下，會顯示提示而非顯示註解的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-677"><span>We fixed an issue where in some situations, hints would be displayed instead of comments</span></span></span></div>

- <div><span data-ttu-id="99c53-678"><span>我們已修正了當使用者嘗試新增註解時，可能會顯示 [修訂窗格] 的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-678"><span>We fixed an issue where the Revisions Pane could display when the user tried to add a new comment</span></span></span></div>

- <div><span data-ttu-id="99c53-679"><span>我們已修正了可能無法顯示 [復原] 下拉式清單的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-679"><span>We fixed an issue which could prevent the undo dropdown list from appearing</span></span></span></div>

- <div><span data-ttu-id="99c53-680"><span>我們已修正了有時無法新增註解的問題</span></span><span class="sxs-lookup"><span data-stu-id="99c53-680"><span>We fixed an issue which could prevent comments from being added</span></span></span></div>


## <a name="july-26-2019"></a><span data-ttu-id="99c53-681">2019 年 7 月 26 日</span><span class="sxs-lookup"><span data-stu-id="99c53-681">July 26, 2019</span></span>
<span data-ttu-id="99c53-682">版本 1908 (組建 11916.20000)</span><span class="sxs-lookup"><span data-stu-id="99c53-682">Version 1908 (build 11916.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="99c53-683">新功能：</span><span class="sxs-lookup"><span data-stu-id="99c53-683">What's New:</span></span>

### <a name="word-excel-powerpoint"></a><span data-ttu-id="99c53-684">Word、Excel、PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-684">Word, Excel, PowerPoint</span></span>

#### <a name="create-more-accessible-pdfs"></a><span data-ttu-id="99c53-685">建立更易於存取的 PDF</span><span class="sxs-lookup"><span data-stu-id="99c53-685">Create more accessible PDFs</span></span>

<span data-ttu-id="99c53-686">建立 PDF 檔案，然後協助工具檢查程式會指出在儲存之前應該修正的協助工具問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-686">Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="99c53-687">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="99c53-687">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="99c53-688">全部</span><span class="sxs-lookup"><span data-stu-id="99c53-688">All</span></span>

- <span data-ttu-id="99c53-689">我們修正了 Office 更新後 Office 文件類型關聯和圖示有時會中斷的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-689">We fixed an issue where file type association and icons for Office could sometimes break after an Office Update</span></span>

### <a name="word"></a><span data-ttu-id="99c53-690">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-690">Word</span></span> 
- <span data-ttu-id="99c53-691">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-691">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="99c53-692">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-692">Excel</span></span>
- <span data-ttu-id="99c53-693">我們修正了移動圖表有時會導致當機的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-693">We fixed an issue where moving a chart could sometimes result in a crash</span></span>
- <span data-ttu-id="99c53-694">我們修正了在更改圖表類型後從 Chart 物件獲取 Workbook 物件有時會導致錯誤的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-694">We fixed an issue where to get Workbook object from Chart object after changing chart types could sometimes result in an error</span></span>

### <a name="powerpoint"></a><span data-ttu-id="99c53-695">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-695">PowerPoint</span></span>
- <span data-ttu-id="99c53-696">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-696">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="99c53-697">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-697">Outlook</span></span>
- <span data-ttu-id="99c53-698">我們修正了在簡化版的功能區中，停用的控制項有時不會呈現灰色的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-698">We fixed an issue where in simplified ribbon, a disabled control could sometimes not be greyed out in the ribbon</span></span>

### <a name="access"></a><span data-ttu-id="99c53-699">Access</span><span class="sxs-lookup"><span data-stu-id="99c53-699">Access</span></span>
- <span data-ttu-id="99c53-700">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-700">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="99c53-701">Project</span><span class="sxs-lookup"><span data-stu-id="99c53-701">Project</span></span>
- <span data-ttu-id="99c53-702">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-702">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-19-2019"></a><span data-ttu-id="99c53-703">2019 年 7 月 19 日</span><span class="sxs-lookup"><span data-stu-id="99c53-703">July 19, 2019</span></span>
<span data-ttu-id="99c53-704">版本 1908 (組建 11911.20000)</span><span class="sxs-lookup"><span data-stu-id="99c53-704">Version 1908 (build 11911.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="99c53-705">新功能：</span><span class="sxs-lookup"><span data-stu-id="99c53-705">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="99c53-706">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-706">Word</span></span>

#### <a name="learn-what-acronyms-mean-when-you-read-in-word-online"></a><span data-ttu-id="99c53-707">了解在 Word Online 中閱讀時，縮略字代表的意義</span><span class="sxs-lookup"><span data-stu-id="99c53-707">Learn what Acronyms mean when you read in Word Online</span></span>

<span data-ttu-id="99c53-708">當您遇到縮略字時，我們會嘗試使用組織的資料來定義縮略字。</span><span class="sxs-lookup"><span data-stu-id="99c53-708">When you encounter an Acronym, we'll try to define it using data from within your organization.</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="99c53-709">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="99c53-709">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="99c53-710">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-710">Word</span></span> 
- <span data-ttu-id="99c53-711">我們已修正 BookMarkEnd 標記遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-711">We fixed an issue which BookMarkEnd tag was missing.</span></span>
- <span data-ttu-id="99c53-712">我們已修正字型選項會在使用者輸入特殊字元時變更的問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-712">We fixed an issue where the font selection could change while the user was typing special characters</span></span>
- <span data-ttu-id="99c53-713">我們已修正有時候可能會造成新註解卡片有空白回覆的問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-713">We fixed an issue which could sometimes cause blank replies to a new comment card</span></span>
- <span data-ttu-id="99c53-714">我們已修正共用電子郵件時可能會造成格式遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-714">We fixed an issue which could cause formatting to be lost when sharing an email</span></span>

### <a name="excel"></a><span data-ttu-id="99c53-715">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-715">Excel</span></span>
- <span data-ttu-id="99c53-716">我們已修正大範圍的陣列有時可能會造成當機的問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-716">We fixed an issue where an array with a large range could sometimes cause a crash</span></span>
- <span data-ttu-id="99c53-717">我們已大幅改善從篩選範圍複製資料的效能。</span><span class="sxs-lookup"><span data-stu-id="99c53-717">We significantly improved the performance of copying data from filtered ranges</span></span>
- <span data-ttu-id="99c53-718">我們已修正如果檔案名稱包含特殊字元便無法開啟某些檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-718">We fixed an issue which prevented some files from opening if the filenames contained special characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="99c53-719">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-719">PowerPoint</span></span>
- <span data-ttu-id="99c53-720">我們已修正 PowerPoint 中預設未選取新建區段的區段名稱問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-720">We fixed an issue where section name was not selected by default for newly created section in PowerPoint.</span></span>
- <span data-ttu-id="99c53-721">我們已修正使用 4:3 顯示器時 UI 變得難以使用的問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-721">We fixed an issue which could cause the UI to become difficult to use when using a 4:3 display</span></span>

### <a name="outlook"></a><span data-ttu-id="99c53-722">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-722">Outlook</span></span>
- <span data-ttu-id="99c53-723">我們已修正無法列出可用會議室的問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-723">We fixed an issue which could prevent available rooms from being listed</span></span>
- <span data-ttu-id="99c53-724">我們已修正部分 POP3 使用者無法使用 HTML 格式的問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-724">We fixed an issue which prevented HTML formatting for some POP3 users</span></span>

### <a name="access"></a><span data-ttu-id="99c53-725">Access</span><span class="sxs-lookup"><span data-stu-id="99c53-725">Access</span></span>
- <span data-ttu-id="99c53-726">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-726">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="99c53-727">Project</span><span class="sxs-lookup"><span data-stu-id="99c53-727">Project</span></span>
- <span data-ttu-id="99c53-728">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-728">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-12-2019"></a><span data-ttu-id="99c53-729">2019 年 7 月 12 日</span><span class="sxs-lookup"><span data-stu-id="99c53-729">July 12, 2019</span></span>
<span data-ttu-id="99c53-730">版本 1907 (組建 11901.20038)</span><span class="sxs-lookup"><span data-stu-id="99c53-730">Version 1907 (build 11901.20038)</span></span>

## <a name="whats-new"></a><span data-ttu-id="99c53-731">新功能：</span><span class="sxs-lookup"><span data-stu-id="99c53-731">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="99c53-732">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-732">PowerPoint</span></span>
 
#### <a name="use-ink-replay-in-your-presentations"></a><span data-ttu-id="99c53-733">在簡報中使用筆跡重播</span><span class="sxs-lookup"><span data-stu-id="99c53-733">Use ink replay in your presentations</span></span>
 
<span data-ttu-id="99c53-734">套用 PowerPoint 的筆跡重播動畫，使簡報的表達和溝通更加生動。</span><span class="sxs-lookup"><span data-stu-id="99c53-734">Apply a replay animation for ink in PowerPoint to express and communicate more in presentations.</span></span> 

## <a name="notable-fixes"></a><span data-ttu-id="99c53-735">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="99c53-735">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="99c53-736">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-736">Word</span></span> 
- <span data-ttu-id="99c53-737">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-737">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="99c53-738">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-738">Excel</span></span>
- <span data-ttu-id="99c53-739">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-739">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="99c53-740">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-740">PowerPoint</span></span>
- <span data-ttu-id="99c53-741">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-741">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="99c53-742">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-742">Outlook</span></span>
- <span data-ttu-id="99c53-743">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-743">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="99c53-744">Access</span><span class="sxs-lookup"><span data-stu-id="99c53-744">Access</span></span>
- <span data-ttu-id="99c53-745">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-745">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="99c53-746">Project</span><span class="sxs-lookup"><span data-stu-id="99c53-746">Project</span></span>
- <span data-ttu-id="99c53-747">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-747">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-5-2019"></a><span data-ttu-id="99c53-748">2019 年 7 月 5 日</span><span class="sxs-lookup"><span data-stu-id="99c53-748">July 5, 2019</span></span>
<span data-ttu-id="99c53-749">版本 1907 (組建 11901.20018)</span><span class="sxs-lookup"><span data-stu-id="99c53-749">Version 1907 (build 11901.20018)</span></span>

## <a name="whats-new"></a><span data-ttu-id="99c53-750">新功能：</span><span class="sxs-lookup"><span data-stu-id="99c53-750">What's New:</span></span>

### <a name="word-excel-powerpoint"></a><span data-ttu-id="99c53-751">Word、Excel、PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-751">Word, Excel, PowerPoint</span></span>

#### <a name="sketchy-shapes"></a><span data-ttu-id="99c53-752">素描形狀！</span><span class="sxs-lookup"><span data-stu-id="99c53-752">Sketchy Shapes!</span></span>

<span data-ttu-id="99c53-753">仍在編寫簡報的草稿嗎？</span><span class="sxs-lookup"><span data-stu-id="99c53-753">In the middle of drafting a presentation?</span></span> <span data-ttu-id="99c53-754">套用素描樣式來顯示您仍在處理文件。</span><span class="sxs-lookup"><span data-stu-id="99c53-754">Apply the sketchy style to show that you're still working on it.</span></span> <span data-ttu-id="99c53-755">此功能可在不將物件轉換成自由格式、手繪形狀的情況下，為您的物件賦與個人風格。</span><span class="sxs-lookup"><span data-stu-id="99c53-755">It gives a personal touch to your objects without turning it into a free form, hand-drawn shapes.</span></span>

### <a name="excel"></a><span data-ttu-id="99c53-756">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-756">Excel</span></span>

- <span data-ttu-id="99c53-757">**更快速共用檔案**：不需開啟檔案，即可從最近使用清單直接共用您的檔案。</span><span class="sxs-lookup"><span data-stu-id="99c53-757">**Faster file sharing**: Share your documents right from the recently used list without having to open the file.</span></span>
### <a name="powerpoint"></a><span data-ttu-id="99c53-758">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-758">PowerPoint</span></span>

- <span data-ttu-id="99c53-759">**[在講義上列印投影片編號] 設定已移至 [列印] 功能表，以易於存取：** 選取講義版面配置時，可在 [列印] > [整頁模式] 下拉式清單中找到它。</span><span class="sxs-lookup"><span data-stu-id="99c53-759">**The setting to Print Slide Numbers in Handouts has been moved to the Print Menu for easier access:**  Find it in the Print > Print Layout dropdown when a Handout layout is selected.</span></span> <span data-ttu-id="99c53-760">這也會使得每個簡報的設定易於切換。</span><span class="sxs-lookup"><span data-stu-id="99c53-760">This also allows the setting to be easily toggled per presentation.</span></span> [<span data-ttu-id="99c53-761">深入了解</span><span class="sxs-lookup"><span data-stu-id="99c53-761">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="99c53-762">**更快速共用檔案：** 不需開啟檔案，即可從最近使用清單直接共用您的檔案。</span><span class="sxs-lookup"><span data-stu-id="99c53-762">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

### <a name="word"></a><span data-ttu-id="99c53-763">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-763">Word</span></span>

- <span data-ttu-id="99c53-764">**更快速共用檔案：** 不需開啟檔案，即可從最近使用清單直接共用您的檔案。</span><span class="sxs-lookup"><span data-stu-id="99c53-764">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="99c53-765">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="99c53-765">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="99c53-766">全部</span><span class="sxs-lookup"><span data-stu-id="99c53-766">All</span></span>
- <span data-ttu-id="99c53-767">我們已大幅提高功能區 KeyTip 的效能</span><span class="sxs-lookup"><span data-stu-id="99c53-767">We significantly improved the performance of Ribbon KeyTips</span></span>
- <span data-ttu-id="99c53-768">我們已修正無法正常顯示 [查看即將推出的新功能] 方塊的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-768">We fixed an issue which prevented the "See what's coming soon" dialog from being displayed properly</span></span>
- <span data-ttu-id="99c53-769">我們已修正可能會導致共同撰寫圖庫飛出視窗中的相片排列錯誤的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-769">We fixed an issue which could cause Photos to be misaligned in the Co-auth Gallery flyout</span></span>

### <a name="word"></a><span data-ttu-id="99c53-770">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-770">Word</span></span> 
- <span data-ttu-id="99c53-771">我們已修正有時無法加入新註解的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-771">We fixed an issue which could sometimes prevent new comments from being added</span></span>
- <span data-ttu-id="99c53-772">我們已修正表格有時可能會造成當機的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-772">We fixed an issue where tables could sometimes cause a crash</span></span>
- <span data-ttu-id="99c53-773">我們已修正無效的資料有時可能會新增至合併列印結尾的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-773">We fixed an issue where invalid data could sometimes be added to the end of a mail merge</span></span>
- <span data-ttu-id="99c53-774">我們已修正可能會導致不正確呈現部分 LaTeX 方程式的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-774">We fixed an issue which could cause some LaTeX equations to render incorrectly</span></span>

### <a name="excel"></a><span data-ttu-id="99c53-775">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-775">Excel</span></span>
- <span data-ttu-id="99c53-776">我們已修正變更圖表類型有時可能會導致執行階段例外狀況的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-776">We fixed an issue where changing chart types could sometimes result in a runtime exception</span></span>
- <span data-ttu-id="99c53-777">我們已修正開啟多個視窗時會顯示不正確功能區的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-777">We fixed an issue where the incorrect ribbon could be displayed when multiple windows were open</span></span>
- <span data-ttu-id="99c53-778">我們已修正巨集開啟活頁簿的第二個執行個體時可能會造成錯誤的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-778">We fixed an issue which could cause an error when a macro opened a second instance of a workbook</span></span>
- <span data-ttu-id="99c53-779">我們已修正開啟或建立活頁簿，或切換使用不同的活頁簿時可能會造成當機的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-779">We fixed an issue which could cause a crash when opening or creating a workbook, or switching between workbooks</span></span>
- <span data-ttu-id="99c53-780">我們已修正使用者無法在 Teams 中開啟透過 Word 建立之 PDF 的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-780">We fixed an issue preventing users from opening a PDF created from Word in Teams</span></span>

### <a name="powerpoint"></a><span data-ttu-id="99c53-781">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-781">PowerPoint</span></span>
- <span data-ttu-id="99c53-782">我們已修正匯出成 PDF 時會降低圖表品質的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-782">We fixed an issue which would degrade the quality of a chart when exported to a pdf</span></span>
- <span data-ttu-id="99c53-783">我們已修正工具提示無法顯示到達中心之距離的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-783">We fixed an issue which prevented a tooltip indicating the distance to center from displaying</span></span>

### <a name="outlook"></a><span data-ttu-id="99c53-784">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-784">Outlook</span></span>
- <span data-ttu-id="99c53-785">我們已修正有時可能會導致 [磁碟已滿] 錯誤訊息無法顯示的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-785">We fixed an issue which could sometimes prevent a Disk Full error to be displayed</span></span>
- <span data-ttu-id="99c53-786">我們已修正更新會議邀請時可能會導致附件重複的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-786">We fixed an issue which could cause attachments to become duplicated when updating a meeting request</span></span>

### <a name="access"></a><span data-ttu-id="99c53-787">Access</span><span class="sxs-lookup"><span data-stu-id="99c53-787">Access</span></span>
- <span data-ttu-id="99c53-788">我們已修正某些查詢無法傳回大整數值的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-788">We fixed an issue which prevented some queries from returning large integer values</span></span>
- <span data-ttu-id="99c53-789">我們已修正可能會引起 SQL 文字方塊無法編輯的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-789">We fixed an issue which could make the sql textbox uneditable</span></span>
- <span data-ttu-id="99c53-790">我們已修正工具提示可能難以在某些高 DPI 顯示器上查看的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-790">We fixed an issue where tooltips could be difficult to see on some High DPI displays</span></span>

### <a name="project"></a><span data-ttu-id="99c53-791">Project</span><span class="sxs-lookup"><span data-stu-id="99c53-791">Project</span></span>
- <span data-ttu-id="99c53-792">我們已修正在新工作中可能會導致旗標值無法編輯的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-792">We fixed an issue which could cause flag values to become uneditable in new tasks</span></span>
- <span data-ttu-id="99c53-793">我們已修正可能導致狀態更新在 [工作分派] 和 [任務] 上不正確地設定 [實際開始日期] 的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-793">We fixed an issue which could cause a status update to improperly set Actual Start Date on Assignments and Tasks</span></span>
- <span data-ttu-id="99c53-794">我們已修正可能會導致部分資源錯誤顯示為過度分派的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-794">We fixed an issue which could cause some resources to incorreclty appear overallocated</span></span>
- <span data-ttu-id="99c53-795">我們已修正新增延隔時間、小數點分隔符號是逗號，以及連線至伺服器時，工作相依性新增方法可能會出錯的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-795">We fixed an issue where the TaskDependencies Add method could fail when Lag is added, the decimal separator is a comma, and when connected to a server</span></span>
- <span data-ttu-id="99c53-796">我們已修正透過 CSOM 更新本機自訂欄位的查閱表格值可能會損毀 PCS 的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-796">We fixed an issue where updating local custom field lookup table values via CSOM could crash PCS</span></span>
- <span data-ttu-id="99c53-797">我們已修正總工時值示內如果含有小數點時將不正確顯示的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-797">We fixed an issue where the total work values may appear incorrect if they contain a decimal</span></span>

</BR></BR>

## <a name="june-28-2019"></a><span data-ttu-id="99c53-798">2019 年 6 月 28 日</span><span class="sxs-lookup"><span data-stu-id="99c53-798">June 28, 2019</span></span>
<span data-ttu-id="99c53-799">版本 1907 (組建 11819.20002)</span><span class="sxs-lookup"><span data-stu-id="99c53-799">Version 1907 (build 11819.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="99c53-800">新功能：</span><span class="sxs-lookup"><span data-stu-id="99c53-800">What's New:</span></span>

### <a name="excel"></a><span data-ttu-id="99c53-801">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-801">Excel</span></span>

- <span data-ttu-id="99c53-802">**使用 Power Query 的增強功能快速撰寫程式碼：** 使用自動完成和語法色彩快速完成程式碼。</span><span class="sxs-lookup"><span data-stu-id="99c53-802">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="99c53-803">同時輕鬆探索函數、資料行和參數</span><span class="sxs-lookup"><span data-stu-id="99c53-803">Easily discover functions, columns, and parameters, too</span></span>

- <span data-ttu-id="99c53-804">**聯結類似欄位上的表格：** 在比較合併表格的欄位時，取得及轉換 (Power Query) 現在具有近似文字比對邏輯 (也稱為模糊比對)。</span><span class="sxs-lookup"><span data-stu-id="99c53-804">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span>

### <a name="word"></a><span data-ttu-id="99c53-805">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-805">Word</span></span>

- <span data-ttu-id="99c53-806">**共同撰寫的增強功能**：增強共同撰寫時的可靠性。</span><span class="sxs-lookup"><span data-stu-id="99c53-806">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>
 
### <a name="word-excel-powerpoint-and-visio"></a><span data-ttu-id="99c53-807">Word、Excel、PowerPoint 和 Visio</span><span class="sxs-lookup"><span data-stu-id="99c53-807">Word, Excel, PowerPoint, and Visio</span></span>

#### <a name="recommended-documents"></a><span data-ttu-id="99c53-808">建譯的文件</span><span class="sxs-lookup"><span data-stu-id="99c53-808">Recommended Documents</span></span>

<span data-ttu-id="99c53-809">透過建議您的相關活動尋找文件。</span><span class="sxs-lookup"><span data-stu-id="99c53-809">Find documents with relevant activity recommended to you.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="99c53-810">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="99c53-810">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="99c53-811">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-811">Word</span></span> 
- <span data-ttu-id="99c53-812">我們已修正可能會導致有些 .DOC 檔案無法開啟的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-812">We fixed an issue which could prevent some .DOC files from opening</span></span>
- <span data-ttu-id="99c53-813">我們已修正可能會導致註解無法正確載入的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-813">We fixed an issue which could have prevented comments from loading properly</span></span>

### <a name="excel"></a><span data-ttu-id="99c53-814">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-814">Excel</span></span>
- <span data-ttu-id="99c53-815">我們已改善 Power Query 的效能</span><span class="sxs-lookup"><span data-stu-id="99c53-815">We improved the performance of Power Queries</span></span>

### <a name="powerpoint"></a><span data-ttu-id="99c53-816">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-816">PowerPoint</span></span>
- <span data-ttu-id="99c53-817">我們已修正在 Surface 裝置上使用手寫筆可能會導致螢幕閃爍的相關問題</span><span class="sxs-lookup"><span data-stu-id="99c53-817">We fixed an issue related to using a pen on a Surface device which could cause the screen to flicker</span></span>

### <a name="outlook"></a><span data-ttu-id="99c53-818">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-818">Outlook</span></span>
- <span data-ttu-id="99c53-819">我們已修正將約會轉換成會議時可能會變更約會的空閒/忙碌狀態問題</span><span class="sxs-lookup"><span data-stu-id="99c53-819">We fixed an issue which could change the free/busy status of an appointment when converted to a meeting</span></span>
- <span data-ttu-id="99c53-820">我們已修正電子郵件有臨時範本的保護時會顯示錯誤範本和描述的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-820">We fixed an issue where the wrong template and description would be displayed when an e-mail was protected with an ad-hoc template</span></span>

### <a name="access"></a><span data-ttu-id="99c53-821">Access</span><span class="sxs-lookup"><span data-stu-id="99c53-821">Access</span></span>
- <span data-ttu-id="99c53-822">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-822">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="99c53-823">Project</span><span class="sxs-lookup"><span data-stu-id="99c53-823">Project</span></span>
- <span data-ttu-id="99c53-824">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-824">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-21-2019"></a><span data-ttu-id="99c53-825">2019 年 6 月 21 日</span><span class="sxs-lookup"><span data-stu-id="99c53-825">June 21, 2019</span></span>
<span data-ttu-id="99c53-826">版本 1907 (組建 11815.20002)</span><span class="sxs-lookup"><span data-stu-id="99c53-826">Version 1907 (build 11815.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="99c53-827">新功能：</span><span class="sxs-lookup"><span data-stu-id="99c53-827">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="99c53-828">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-828">Outlook</span></span>

#### <a name="dark-mode-for-black-theme-in-outlook-desktop"></a><span data-ttu-id="99c53-829">Outlook 電腦版中用於黑色佈景主題的深色模式</span><span class="sxs-lookup"><span data-stu-id="99c53-829">Dark Mode for Black Theme in Outlook Desktop</span></span>

<span data-ttu-id="99c53-830">使用深色模式時，黑色佈景主題中的使用者現在也會在讀取電子郵件時看到讀取窗格具有深色背景，並在撰寫電子郵件時擁有深色背景的撰寫體驗。</span><span class="sxs-lookup"><span data-stu-id="99c53-830">With dark mode, users in black theme will now also see the reading pane with a dark background when reading emails, and the compose experience with a dark background when writing emails.</span></span> <span data-ttu-id="99c53-831">如果使用者想要預覽郵件在淺色背景下的外觀，在讀取窗格或功能區中有太陽/月亮切換。</span><span class="sxs-lookup"><span data-stu-id="99c53-831">There is a sun/moon toggle on the reading pane and in the ribbon in case users want to preview what the message looks like with a light background instead.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="99c53-832">開始使用：</span><span class="sxs-lookup"><span data-stu-id="99c53-832">Getting Started:</span></span>

1. <span data-ttu-id="99c53-833">開啟黑色佈景主題，深色模式預設就會處於開啟狀態。</span><span class="sxs-lookup"><span data-stu-id="99c53-833">Turn on black theme and dark mode will be on by default.</span></span>
2. <span data-ttu-id="99c53-834">使用月亮/太陽切換 (在讀取窗格和功能區中) 可為不在深色模式的使用者預覽郵件的外觀</span><span class="sxs-lookup"><span data-stu-id="99c53-834">Use the moon/sun toggle (in the reading pane and in the ribbon) to preview what the message looks like for users not in dark mode</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="99c53-835">可嘗試使用的案例</span><span class="sxs-lookup"><span data-stu-id="99c53-835">Scenarios to Try</span></span>

1. <span data-ttu-id="99c53-836">在深色模式中讀取電子郵件。</span><span class="sxs-lookup"><span data-stu-id="99c53-836">Read emails in dark mode.</span></span> <span data-ttu-id="99c53-837">如果您無法讀取某些項目，請使用讀取窗格中的太陽切換來切換為淺色背景。</span><span class="sxs-lookup"><span data-stu-id="99c53-837">If you are unable to read something, use the sun toggle in the Reading Pane to switch to a light background.</span></span> 
2. <span data-ttu-id="99c53-838">在深色模式中撰寫電子郵件。</span><span class="sxs-lookup"><span data-stu-id="99c53-838">Compose emails in dark mode.</span></span> <span data-ttu-id="99c53-839">使用功能區中的太陽切換，預覽您的郵件使用淺色背景時的外觀。</span><span class="sxs-lookup"><span data-stu-id="99c53-839">Preview what your message will look like with a light background by using the sun toggle in the ribbon.</span></span> 

<span data-ttu-id="99c53-840">如果您遇到未正確顯示的任何電子郵件，請將其 (當作附件) 傳送到 OutlookDarkModeFail@service.microsoft.com</span><span class="sxs-lookup"><span data-stu-id="99c53-840">If you encounter any emails that don't render properly, please send them (as an attachment) to OutlookDarkModeFail@service.microsoft.com</span></span>

#### <a name="get-location-suggestions"></a><span data-ttu-id="99c53-841">取得位置建議</span><span class="sxs-lookup"><span data-stu-id="99c53-841">Get location suggestions</span></span>

<span data-ttu-id="99c53-842">開始輸入，Outlook 就會尋找符合的位置。</span><span class="sxs-lookup"><span data-stu-id="99c53-842">Start typing and Outlook will look for matching locations.</span></span>

<span data-ttu-id="99c53-843">建立約會和會議時，這適用於 [位置] 欄位。</span><span class="sxs-lookup"><span data-stu-id="99c53-843">This applies to the Location field when creating Appointments and Meetings.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="99c53-844">開始使用：</span><span class="sxs-lookup"><span data-stu-id="99c53-844">Getting Started:</span></span>

- <span data-ttu-id="99c53-845">在 Outlook 中的 O365 或 Outlook.com 行事曆上，建立約會或會議。</span><span class="sxs-lookup"><span data-stu-id="99c53-845">Create an Appointment or Meeting on an O365 or Outlook.com calendar in Outlook.</span></span> 
- <span data-ttu-id="99c53-846">按一下 [位置] 欄位，然後開始輸入…</span><span class="sxs-lookup"><span data-stu-id="99c53-846">Click into the Location field and start typing…</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="99c53-847">可嘗試使用的案例</span><span class="sxs-lookup"><span data-stu-id="99c53-847">Scenarios to Try</span></span>

<span data-ttu-id="99c53-848">當您將會議室加入至會議時，按一下 [位置] 欄位，而不是使用會議室尋找工具增益集或通訊錄。</span><span class="sxs-lookup"><span data-stu-id="99c53-848">When adding a conference room to a meeting, click into Location field, rather than using Room Finder add-in or Address Book.</span></span>
<span data-ttu-id="99c53-849">若是在公共場所 (如餐廳、咖啡廳，甚至是牙醫診所) 的實體位置進行會議，請嘗試使用新的選擇器找到確切的位置。</span><span class="sxs-lookup"><span data-stu-id="99c53-849">For appointments at a physical place with a public location - like a restaurant, coffee shop, or even your dentist's office - try finding the exact location using the new picker.</span></span> <span data-ttu-id="99c53-850">如此一來，您將可以在該離開時，收到 Outlook Mobile 的通知。</span><span class="sxs-lookup"><span data-stu-id="99c53-850">This way, you'll be able to get notified on Outlook Mobile when it's time to leave.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="99c53-851">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="99c53-851">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="99c53-852">全部</span><span class="sxs-lookup"><span data-stu-id="99c53-852">All</span></span>
- <span data-ttu-id="99c53-853">我們已修正在離線時會導致搜尋方塊啟用的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-853">We fixed an issue which would keep the Search Box enabled while offline</span></span>

### <a name="word"></a><span data-ttu-id="99c53-854">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-854">Word</span></span> 
- <span data-ttu-id="99c53-855">我們已修正有時候可能難以查看鍵盤焦點的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-855">We fixed an issue where keyboard focus could sometimes be difficult to see</span></span>
- <span data-ttu-id="99c53-856">我們已修正貼到新文件的文字，有時候文字對齊可能會不正確的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-856">We fixed an issue where text pasted into a new document could sometimes have the wrong text alignment</span></span>
- <span data-ttu-id="99c53-857">我們已修正將使用者的電腦暫停之後，可能防止部分使用者儲存變更的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-857">We fixed an issue which could prevent some users from saving changes after suspending their computer</span></span>
- <span data-ttu-id="99c53-858">我們已修正在某些情況下會列印整份文件，而非所選範圍的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-858">We fixed an issue where in certain cases an entire document would be printed instead of the selected range</span></span>
- <span data-ttu-id="99c53-859">我們已修正可能會讓註解在較小型的顯示器上難以閱讀的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-859">We fixed an issue which could make comments difficult to read on smaller displays</span></span>
- <span data-ttu-id="99c53-860">我們已修正擷取到裝置時可能會造成當機的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-860">We fixed an issue which could cause a crash when capturing to a device</span></span>

### <a name="excel"></a><span data-ttu-id="99c53-861">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-861">Excel</span></span>
- <span data-ttu-id="99c53-862">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-862">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="99c53-863">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-863">PowerPoint</span></span>
- <span data-ttu-id="99c53-864">我們已修正有時候可能難以查看鍵盤焦點的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-864">We fixed an issue where keyboard focus could sometimes be difficult to see</span></span>

### <a name="outlook"></a><span data-ttu-id="99c53-865">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-865">Outlook</span></span>
- <span data-ttu-id="99c53-866">我們已修正不正確地將未啟用的增益集顯示為已啟用的問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-866">We fixed an issue which could incorrectly display an add-in as being enabled when it was not.</span></span>
- <span data-ttu-id="99c53-867">我們已修正會在有大量原則時，使得客戶無法檢視所有保留原則的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-867">We fixed an issue which would prevent a customer from viewing all retention policies if there were a large number of them</span></span>

### <a name="access"></a><span data-ttu-id="99c53-868">Access</span><span class="sxs-lookup"><span data-stu-id="99c53-868">Access</span></span>
- <span data-ttu-id="99c53-869">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-869">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="99c53-870">Project</span><span class="sxs-lookup"><span data-stu-id="99c53-870">Project</span></span>
- <span data-ttu-id="99c53-871">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-871">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-14-2019"></a><span data-ttu-id="99c53-872">2019 年 6 月 14 日</span><span class="sxs-lookup"><span data-stu-id="99c53-872">June 14, 2019</span></span>
<span data-ttu-id="99c53-873">版本 1907 (組建 11807.20000)</span><span class="sxs-lookup"><span data-stu-id="99c53-873">Version 1907 (build 11807.20000)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="99c53-874">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="99c53-874">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="99c53-875">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-875">Word</span></span> 
- <span data-ttu-id="99c53-876">我們已修正了儲存到 OneDrive 時，使用者可能無法登入的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-876">We fixed an issue which could prevent a user from signing in when saving to OneDrive</span></span>
- <span data-ttu-id="99c53-877">我們已修正了使用者可能無法變更限制存取模式中之 SharePoint 內容的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-877">We fixed an issue where a user could be prevented from changing SharePoint properties while in restricted access mode</span></span>
- <span data-ttu-id="99c53-878">我們已修正了調整邊界時，可能會變更頁首及頁尾內容的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-878">We fixed an issue where header and footer content could change when adjusting margins</span></span>
- <span data-ttu-id="99c53-879">我們已修正了切換成網頁檢視時，格式設定可能會中斷的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-879">We fixed an issue where formatting could break when switching to web view</span></span>
- <span data-ttu-id="99c53-880">我們已修正了從 SharePoint 開啟時，使用者無法使用自訂欄位的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-880">We fixed an issue which could prevent a user from using custom fields when opened from SharePoint</span></span>

### <a name="excel"></a><span data-ttu-id="99c53-881">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-881">Excel</span></span>
- <span data-ttu-id="99c53-882">我們已修正了刪除篩選集之資料列時的效能問題</span><span class="sxs-lookup"><span data-stu-id="99c53-882">We fixed a performance issue when deleting rows of a filtered set</span></span>
- <span data-ttu-id="99c53-883">我們已修正了有時可能會造成滑鼠在受保護檢視模式中閃爍的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-883">We fixed an issue which could sometimes cause the mouse to flicker in protected view</span></span>
- <span data-ttu-id="99c53-884">我們修正了刪除系列時，可能會導致當機的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-884">We fixed an issue which could have caused a crash when deleting a series</span></span>
- <span data-ttu-id="99c53-885">我們已修正了某些使用者即使在沒有提供的情況下，仍舊有新增版本歷程記錄之選項的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-885">We fixed an issue where some users would have the option to add version history when that was not available</span></span>
- <span data-ttu-id="99c53-886">我們已修正了使用試算表比較工具時，可能導致例外狀況的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-886">We fixed an issue which could have caused an exception when using the Spreadsheet Compare tool</span></span>

### <a name="powerpoint"></a><span data-ttu-id="99c53-887">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-887">PowerPoint</span></span>
- <span data-ttu-id="99c53-888">我們已修正了按一下連結到 SharePoint 時，可能會發生當機的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-888">We fixed an issue where a crash could occur when clicking a link to SharePoint</span></span>
- <span data-ttu-id="99c53-889">我們已修正了使用 Surface 手寫筆輸入時，可能將使用者切換到下一個頁面的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-889">We fixed an issue which could switch the user to the next page while typing using a Surface Pen</span></span>

### <a name="outlook"></a><span data-ttu-id="99c53-890">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-890">Outlook</span></span>
- <span data-ttu-id="99c53-891">我們已修正了在某些情況下 [收件者] 欄位大於正常的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-891">We fixed an issue where in some cases the To field was larger than normal</span></span>

### <a name="access"></a><span data-ttu-id="99c53-892">Access</span><span class="sxs-lookup"><span data-stu-id="99c53-892">Access</span></span>
- <span data-ttu-id="99c53-893">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-893">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="99c53-894">Project</span><span class="sxs-lookup"><span data-stu-id="99c53-894">Project</span></span>
- <span data-ttu-id="99c53-895">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-895">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-7-2019"></a><span data-ttu-id="99c53-896">2019 年 6 月 7 日</span><span class="sxs-lookup"><span data-stu-id="99c53-896">June 7, 2019</span></span>
<span data-ttu-id="99c53-897">版本 1907 (組建 11727.20064)</span><span class="sxs-lookup"><span data-stu-id="99c53-897">Version 1907 (build 11727.20064)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="99c53-898">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="99c53-898">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="99c53-899">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-899">Word</span></span> 
- <span data-ttu-id="99c53-900">我們已修正當 Word 中的自動校正設定為使句中的第一個字母均為大寫時，偶爾會當機的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-900">We fixed an issue where Word could sometimes crash when autocorrect was set to capitalize the first letter of a sentence</span></span>
- <span data-ttu-id="99c53-901">我們已改善在 SharePoint 上編輯文件時的效能。</span><span class="sxs-lookup"><span data-stu-id="99c53-901">We improved performance when editing a document on SharePoint</span></span>
- <span data-ttu-id="99c53-902">我們已修正在 Adobe Illustrator 中所建立之向量影像無法正確顯示的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-902">We fixed an issue where vector-based images created in Adobe Illustrator would not display correctly</span></span>

### <a name="excel"></a><span data-ttu-id="99c53-903">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-903">Excel</span></span>
- <span data-ttu-id="99c53-904">我們已修正錄製巨集時，排序欄位有時未正確設定的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-904">We fixed an issue where sorting fields were sometimes not set correctly when recording a macro</span></span>
- <span data-ttu-id="99c53-905">我們已修正重新計算陣列公式期間導致停止回應或當機的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-905">We fixed an issue that causes hang or crash during recalculation of an array formula</span></span>

### <a name="powerpoint"></a><span data-ttu-id="99c53-906">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-906">PowerPoint</span></span>
- <span data-ttu-id="99c53-907">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-907">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="99c53-908">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-908">Outlook</span></span>
- <span data-ttu-id="99c53-909">我們已修正內嵌附件有時未正確縮放的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-909">We fixed an issue where inline attachments would sometimes be incorrectly scaled</span></span>

### <a name="access"></a><span data-ttu-id="99c53-910">Access</span><span class="sxs-lookup"><span data-stu-id="99c53-910">Access</span></span>
- <span data-ttu-id="99c53-911">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-911">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="99c53-912">Project</span><span class="sxs-lookup"><span data-stu-id="99c53-912">Project</span></span>
- <span data-ttu-id="99c53-913">我們已修正固定工期的時程表有時會變更工作分派完成日期的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-913">We fixed an issue where timesheets on a fixed duration could sometimes change the assignment finish date</span></span>
- <span data-ttu-id="99c53-914">我們已修正從舊版本中開啟專案時顯示的完成百分比值可能有誤的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-914">We fixed an issue where Percentage Complete values could be wrong when opening a project from an earlier version</span></span>

</BR></BR>

## <a name="may-31-2019"></a><span data-ttu-id="99c53-915">2019 年 5 月 31 日</span><span class="sxs-lookup"><span data-stu-id="99c53-915">May 31, 2019</span></span>
<span data-ttu-id="99c53-916">版本 1906 (組建 11722.20008)</span><span class="sxs-lookup"><span data-stu-id="99c53-916">Version 1906 (build 11722.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="99c53-917">新功能：</span><span class="sxs-lookup"><span data-stu-id="99c53-917">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="99c53-918">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-918">Outlook</span></span>

#### <a name="dialog-for-contacting-support-now-is-dockable-and-appears-on-the-right"></a><span data-ttu-id="99c53-919">[連絡支援人員] 對話方塊現在可停駐，且會顯示在右側</span><span class="sxs-lookup"><span data-stu-id="99c53-919">Dialog for Contacting Support now is dockable and appears on the right</span></span>

<span data-ttu-id="99c53-920">用於 [連絡支援人員] 的對話方塊現在會顯示在右側窗格中，並且會以停駐視窗形式開始。</span><span class="sxs-lookup"><span data-stu-id="99c53-920">The dialog used for Contacting support will now appear in a pane on the right and will start off as a docked window.</span></span>

#### <a name="ink-in-your-email"></a><span data-ttu-id="99c53-921">在您的電子郵件中使用筆跡！</span><span class="sxs-lookup"><span data-stu-id="99c53-921">Ink in Your Email!</span></span>

<span data-ttu-id="99c53-922">您現在可以在您的 Outlook 電子郵件中繪製圖片並加上註釋。</span><span class="sxs-lookup"><span data-stu-id="99c53-922">You can now draw and annotate pictures in your Outlook emails.</span></span>

### <a name="word"></a><span data-ttu-id="99c53-923">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-923">Word</span></span>

#### <a name="open-document-links-in-word"></a><span data-ttu-id="99c53-924">在 Word 中開啟文件連結</span><span class="sxs-lookup"><span data-stu-id="99c53-924">Open document links in Word</span></span>

<span data-ttu-id="99c53-925">當您在 Office 中按一下文件連結時，您可以更新您的喜好設定，以預設在 Word App 中開啟該連結。</span><span class="sxs-lookup"><span data-stu-id="99c53-925">When you click a document link in Office, you can update your preference to open in the Word app by default.</span></span>  <span data-ttu-id="99c53-926">若要更新您的喜好設定，請移至 [檔案] -> [選項] -> [進階] -> [連結處理]。</span><span class="sxs-lookup"><span data-stu-id="99c53-926">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="99c53-927">深入了解：https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="99c53-927">Learn more: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="99c53-928">開始使用：</span><span class="sxs-lookup"><span data-stu-id="99c53-928">Getting Started:</span></span>

<span data-ttu-id="99c53-929">此功能將預設為關閉。</span><span class="sxs-lookup"><span data-stu-id="99c53-929">Feature will default to off.</span></span> <span data-ttu-id="99c53-930">使用者可以透過 [選項] -> [進階] -> [連結處理] 設定來開啟它，也可以在 Win32 WXP 應用程式帶他們進行選擇加入體驗時選擇加入。</span><span class="sxs-lookup"><span data-stu-id="99c53-930">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="99c53-931">當使用者按一下透過 Outlook/Word/PowerPoint/Excel 儲存在 OneDrive/商務用 OneDrive/SharePoint 上的 Word/PowerPoint/Excel 檔案時，這些連結依預設會在適當的 Office 應用程式中 (而非瀏覽器中) 開啟。</span><span class="sxs-lookup"><span data-stu-id="99c53-931">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="99c53-932">若要變更此預設值，使用者可以更新 Outlook/Word/Excel/PowerPoint 中的下列設定：</span><span class="sxs-lookup"><span data-stu-id="99c53-932">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="99c53-933">[檔案] -> [選項] -> [進階] -> [連結處理]</span><span class="sxs-lookup"><span data-stu-id="99c53-933">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="99c53-934">此設定會在 Outlook/Word/PowerPoint/Excel 之間共用，而且可以在任一應用程式中設定。</span><span class="sxs-lookup"><span data-stu-id="99c53-934">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="99c53-935">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="99c53-935">Scenarios to Try:</span></span>

<span data-ttu-id="99c53-936">若要觸發選擇加入體驗 - 從 Outlook/Word/PowerPoint/Excel 開啟儲存在 OneDrive/SharePoint 中 Word 文件的連結 - 按一下 [在來自 Office Online 的用戶端中開啟] - 在 30 天內執行此動作兩次。</span><span class="sxs-lookup"><span data-stu-id="99c53-936">To trigger the opt-in experience - Open a link tot a Word document stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="99c53-937">在您選擇加入之後，依預設會在 Win32 應用程式中啟動連結。</span><span class="sxs-lookup"><span data-stu-id="99c53-937">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="99c53-938">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-938">PowerPoint</span></span>

#### <a name="open-presentation-links-in-powerpoint"></a><span data-ttu-id="99c53-939">在 PowerPoint 中開啟簡報連結</span><span class="sxs-lookup"><span data-stu-id="99c53-939">Open presentation links in PowerPoint</span></span>

<span data-ttu-id="99c53-940">當您在 Office 中按一下連結連結時，您可以更新您的喜好設定，以預設在 PowerPoint App 中開啟該連結。</span><span class="sxs-lookup"><span data-stu-id="99c53-940">When you click a presentation link in Office, you can update your preference to open in the PowerPoint app by default.</span></span> <span data-ttu-id="99c53-941">若要更新您的喜好設定，請移至 [檔案] -> [選項] -> [進階] -> [連結處理]。</span><span class="sxs-lookup"><span data-stu-id="99c53-941">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="99c53-942">深入了解：https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="99c53-942">Learn more: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="99c53-943">開始使用：</span><span class="sxs-lookup"><span data-stu-id="99c53-943">Getting Started:</span></span>

<span data-ttu-id="99c53-944">此功能將預設為關閉。</span><span class="sxs-lookup"><span data-stu-id="99c53-944">Feature will default to off.</span></span> <span data-ttu-id="99c53-945">使用者可以透過 [選項] -> [進階] -> [連結處理] 設定來開啟它，也可以在 Win32 WXP 應用程式帶他們進行選擇加入體驗時選擇加入。</span><span class="sxs-lookup"><span data-stu-id="99c53-945">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="99c53-946">當使用者按一下透過 Outlook/Word/PowerPoint/Excel 儲存在 OneDrive/商務用 OneDrive/SharePoint 上的 Word/PowerPoint/Excel 檔案時，這些連結依預設會在適當的 Office 應用程式中 (而非瀏覽器中) 開啟。</span><span class="sxs-lookup"><span data-stu-id="99c53-946">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="99c53-947">若要變更此預設值，使用者可以更新 Outlook/Word/Excel/PowerPoint 中的下列設定：</span><span class="sxs-lookup"><span data-stu-id="99c53-947">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="99c53-948">[檔案] -> [選項] -> [進階] -> [連結處理]</span><span class="sxs-lookup"><span data-stu-id="99c53-948">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="99c53-949">此設定會在 Outlook/Word/PowerPoint/Excel 之間共用，而且可以在任一應用程式中設定。</span><span class="sxs-lookup"><span data-stu-id="99c53-949">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="99c53-950">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="99c53-950">Scenarios to Try:</span></span>

<span data-ttu-id="99c53-951">若要觸發選擇加入體驗 - 從 Outlook/Word/PowerPoint/Excel 開啟儲存在 OneDrive/SharePoint 中 PowerPoint 簡報的連結 - 按一下 [在來自 Office Online 的用戶端中開啟] - 在 30 天內執行此動作兩次。</span><span class="sxs-lookup"><span data-stu-id="99c53-951">To trigger the opt-in experience - Open a link to a PowerPoint presentation stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="99c53-952">在您選擇加入之後，依預設會在 Win32 應用程式中啟動連結。</span><span class="sxs-lookup"><span data-stu-id="99c53-952">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="excel"></a><span data-ttu-id="99c53-953">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-953">Excel</span></span>

#### <a name="open-workbook-links-in-excel"></a><span data-ttu-id="99c53-954">在 Excel 中開啟活頁簿連結</span><span class="sxs-lookup"><span data-stu-id="99c53-954">Open workbook links in Excel</span></span>

<span data-ttu-id="99c53-955">當您在 Office 中按一下活頁簿連結時，您可以更新您的喜好設定，以預設在 Excel App 中開啟該連結。</span><span class="sxs-lookup"><span data-stu-id="99c53-955">When you click a workbook link in Office, you can update your preference to open in the Excel app by default.</span></span> <span data-ttu-id="99c53-956">若要更新您的喜好設定，請移至 [檔案] -> [選項] -> [進階] -> [連結處理]。</span><span class="sxs-lookup"><span data-stu-id="99c53-956">To update your preference, go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="99c53-957">深入了解：https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="99c53-957">Learn More: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="99c53-958">開始使用：</span><span class="sxs-lookup"><span data-stu-id="99c53-958">Getting Started:</span></span>

<span data-ttu-id="99c53-959">此功能將預設為關閉。</span><span class="sxs-lookup"><span data-stu-id="99c53-959">Feature will default to off.</span></span> <span data-ttu-id="99c53-960">使用者可以透過 [選項] -> [進階] -> [連結處理] 設定來開啟它，也可以在 Win32 WXP 應用程式帶他們進行選擇加入體驗時選擇加入。</span><span class="sxs-lookup"><span data-stu-id="99c53-960">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="99c53-961">當使用者按一下透過 Outlook/Word/PowerPoint/Excel 儲存在 OneDrive/商務用 OneDrive/SharePoint 上的 Word/PowerPoint/Excel 檔案時，這些連結依預設會在適當的 Office 應用程式中 (而非瀏覽器中) 開啟。</span><span class="sxs-lookup"><span data-stu-id="99c53-961">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="99c53-962">若要變更此預設值，使用者可以更新 Outlook/Word/Excel/PowerPoint 中的下列設定：</span><span class="sxs-lookup"><span data-stu-id="99c53-962">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="99c53-963">[檔案] -> [選項] -> [進階] -> [連結處理]</span><span class="sxs-lookup"><span data-stu-id="99c53-963">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="99c53-964">此設定會在 Outlook/Word/PowerPoint/Excel 之間共用，而且可以在任一應用程式中設定。</span><span class="sxs-lookup"><span data-stu-id="99c53-964">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="99c53-965">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="99c53-965">Scenarios to Try:</span></span>

<span data-ttu-id="99c53-966">若要觸發選擇加入體驗 - 從 Outlook/Word/PowerPoint/Excel 開啟儲存在 OneDrive/SharePoint 中 Excel 活頁簿的連結 - 按一下 [在來自 Office Online 的用戶端中開啟] - 在 30 天內執行此動作兩次。</span><span class="sxs-lookup"><span data-stu-id="99c53-966">To trigger the opt-in experience - Open a link to an Excel workbook stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="99c53-967">在您選擇加入之後，依預設會在 Win32 應用程式中啟動連結。</span><span class="sxs-lookup"><span data-stu-id="99c53-967">After you opt-in, links will launch in the Win32 apps by default.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="99c53-968">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="99c53-968">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="99c53-969">全部</span><span class="sxs-lookup"><span data-stu-id="99c53-969">All</span></span>
- <span data-ttu-id="99c53-970">我們已修正即使在已停用自動儲存的情況下，檔案有時會自動儲存的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-970">We fixed an issue where files could sometimes be auto-saved even when auto-save was disabled</span></span>

### <a name="word"></a><span data-ttu-id="99c53-971">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-971">Word</span></span> 
- <span data-ttu-id="99c53-972">我們已修正可能會導致部分使用者無法儲存至 SharePoint 的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-972">We fixed an issue which may have prevented some users from saving to SharePoint</span></span>

### <a name="excel"></a><span data-ttu-id="99c53-973">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-973">Excel</span></span>
- <span data-ttu-id="99c53-974">我們已修正可能對非作用中篩選器顯示不正確圖示的問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-974">We fixed an issue where an incorrect icon could be displayed for inactive filters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="99c53-975">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-975">PowerPoint</span></span>
- <span data-ttu-id="99c53-976">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-976">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="99c53-977">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-977">Outlook</span></span>
- <span data-ttu-id="99c53-978">我們已修正有些使用者在群組排程檢視中會不正確地顯示為離線的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-978">We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span>
- <span data-ttu-id="99c53-979">我們已修正可能會防止 SafeLink 剖析包含尾端空格 URL 的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-979">We fixed an issue which prevented SafeLink from parsing a URL with a trailing space</span></span>
- <span data-ttu-id="99c53-980">我們已修正會議室在非工作時間外顯示為可用的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-980">We fixed an issue where rooms were displayed as available outside of non-working hours</span></span>

### <a name="access"></a><span data-ttu-id="99c53-981">Access</span><span class="sxs-lookup"><span data-stu-id="99c53-981">Access</span></span>
- <span data-ttu-id="99c53-982">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-982">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="99c53-983">Project</span><span class="sxs-lookup"><span data-stu-id="99c53-983">Project</span></span>
- <span data-ttu-id="99c53-984">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-984">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-24-2019"></a><span data-ttu-id="99c53-985">2019 年 5 月 24 日</span><span class="sxs-lookup"><span data-stu-id="99c53-985">May 24, 2019</span></span>
<span data-ttu-id="99c53-986">版本 1906 (組建 11715.20002)</span><span class="sxs-lookup"><span data-stu-id="99c53-986">Version 1906 (build 11715.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="99c53-987">新功能：</span><span class="sxs-lookup"><span data-stu-id="99c53-987">What's New:</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="99c53-988">使用者體驗更新</span><span class="sxs-lookup"><span data-stu-id="99c53-988">User Experience Updates</span></span>

<span data-ttu-id="99c53-989">[即將推出] 中的更新現已發佈，其中包括簡化功能區、資料夾窗格的新版視覺效果、郵件清單，以及讀取窗格。</span><span class="sxs-lookup"><span data-stu-id="99c53-989">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="99c53-990">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="99c53-990">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="99c53-991">全部</span><span class="sxs-lookup"><span data-stu-id="99c53-991">All</span></span>

- <span data-ttu-id="99c53-992">我們已修正 [聊天] 窗格無法顯示的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-992">We fixed an issue where the Chat Pane would not display</span></span>

### <a name="word"></a><span data-ttu-id="99c53-993">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-993">Word</span></span> 
- <span data-ttu-id="99c53-994">我們已修正在某些情況下 Word 無法為文法錯誤正確醒目提示文字的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-994">We fixed an issue where in some cases Word could incorrectly highlight text for grammatical errors</span></span>

### <a name="excel"></a><span data-ttu-id="99c53-995">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-995">Excel</span></span>
- <span data-ttu-id="99c53-996">我們已修正 [圖表項目] 使用不正確圖示的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-996">We fixed an issue where an incorrect icon was used in for Chart Elements</span></span>
- <span data-ttu-id="99c53-997">我們已修正開啟同樣的活頁簿時，可能會啟動 VBA 指令碼中不正確活頁簿的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-997">We fixed an issue where the incorrect workbook could be activated in a VBA script when the same book was already open</span></span>

### <a name="powerpoint"></a><span data-ttu-id="99c53-998">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-998">PowerPoint</span></span>
- <span data-ttu-id="99c53-999">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-999">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="99c53-1000">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-1000">Outlook</span></span>
- <span data-ttu-id="99c53-1001">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-1001">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="99c53-1002">Access</span><span class="sxs-lookup"><span data-stu-id="99c53-1002">Access</span></span>
- <span data-ttu-id="99c53-1003">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-1003">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="99c53-1004">Project</span><span class="sxs-lookup"><span data-stu-id="99c53-1004">Project</span></span>
- <span data-ttu-id="99c53-1005">我們已修正 Project 在切換工作列後可能會當機的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1005">We fixed an issue where Project could crash after switching to the taskbar</span></span>

</BR></BR>

## <a name="may-17-2019"></a><span data-ttu-id="99c53-1006">2019 年 5 月 17 日</span><span class="sxs-lookup"><span data-stu-id="99c53-1006">May 17, 2019</span></span>
<span data-ttu-id="99c53-1007">版本 1906 (組建 11708.20006)</span><span class="sxs-lookup"><span data-stu-id="99c53-1007">Version 1906 (build 11708.20006)</span></span>

## <a name="whats-new"></a><span data-ttu-id="99c53-1008">新功能：</span><span class="sxs-lookup"><span data-stu-id="99c53-1008">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="99c53-1009">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-1009">Outlook</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="99c53-1010">使用者體驗更新</span><span class="sxs-lookup"><span data-stu-id="99c53-1010">User Experience Updates</span></span>

<span data-ttu-id="99c53-1011">[即將推出] 中的更新現已發佈，其中包括簡化功能區、資料夾窗格的新版視覺效果、郵件清單，以及讀取窗格。</span><span class="sxs-lookup"><span data-stu-id="99c53-1011">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="99c53-1012">開始使用：</span><span class="sxs-lookup"><span data-stu-id="99c53-1012">Getting Started:</span></span>

<span data-ttu-id="99c53-1013">這些變更會成為新的預設 UI。自 12 月中旬起，即可透過 [即將推出] 開關切換使用這套 UI，協助您徹底發揮生產力</span><span class="sxs-lookup"><span data-stu-id="99c53-1013">These change will be part of the new default UI; it has been available behind the Coming Soon switch since mid Dec for 100% prod</span></span>

#### <a name="customizable-simplified-ribbon"></a><span data-ttu-id="99c53-1014">自訂簡化功能區</span><span class="sxs-lookup"><span data-stu-id="99c53-1014">Customizable Simplified Ribbon</span></span>

<span data-ttu-id="99c53-1015">提供輕鬆自訂功能，方便在傳統與 [簡化] 檢視之間切換，以及釘選/取消釘選命令。</span><span class="sxs-lookup"><span data-stu-id="99c53-1015">Easily customizable to switch between classic and Simplified views and pin/unpin commands.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="99c53-1016">開始使用：</span><span class="sxs-lookup"><span data-stu-id="99c53-1016">Getting Started:</span></span>

<span data-ttu-id="99c53-1017">使用者可以使用簡化功能區，方法是開啟 [即將推出] (在一開始)，然後按一下功能區中的＞形箭號，即可在傳統的多行功能區與新式的簡化單行功能區之間切換。</span><span class="sxs-lookup"><span data-stu-id="99c53-1017">Users can get to the simplified ribbon by turning on Coming Soon (initially) and clicking the chevron in the ribbon to toggle between the classic multi-line ribbon and the new simplified single-line ribbon.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="99c53-1018">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="99c53-1018">Scenarios to Try:</span></span>

<span data-ttu-id="99c53-1019">從傳統功能區切換到簡化功能區</span><span class="sxs-lookup"><span data-stu-id="99c53-1019">Switch from Classic ribbon to Simplified ribbon</span></span>

#### <a name="pick-your-favorite-action"></a><span data-ttu-id="99c53-1020">挑選您的最愛動作</span><span class="sxs-lookup"><span data-stu-id="99c53-1020">Pick your favorite action</span></span>

<span data-ttu-id="99c53-1021">不使用 [標幟] 和 [刪除] 嗎？</span><span class="sxs-lookup"><span data-stu-id="99c53-1021">Don't use Flag and Delete?</span></span> <span data-ttu-id="99c53-1022">那麼 [封存] 或 [標示為已讀取] 呢？</span><span class="sxs-lookup"><span data-stu-id="99c53-1022">How about Archive or Mark as Read?</span></span> <span data-ttu-id="99c53-1023">自訂快速動作功能表，加上您最常使用的命令。</span><span class="sxs-lookup"><span data-stu-id="99c53-1023">Customize the quick action menu with the commands you use most.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="99c53-1024">開始使用：</span><span class="sxs-lookup"><span data-stu-id="99c53-1024">Getting Started:</span></span>

<span data-ttu-id="99c53-1025">若要選取 [快速動作]，請以滑鼠右鍵按一下郵件清單中的 [電子郵件]，以顯示內容功能表。</span><span class="sxs-lookup"><span data-stu-id="99c53-1025">To select your Quick Actions, right click on an email in the message list to bring up the Context Menu.</span></span> <span data-ttu-id="99c53-1026">然後按一下 [設定快速動作...]</span><span class="sxs-lookup"><span data-stu-id="99c53-1026">Then click "Set Quick Actions..."</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="99c53-1027">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="99c53-1027">Scenarios to Try:</span></span>

<span data-ttu-id="99c53-1028">將 [標幟] 和 [刪除] 的預設值變更為 [封存]、[移動]、[標示為已讀取] 或 [無]，以便清除郵件清單</span><span class="sxs-lookup"><span data-stu-id="99c53-1028">Change the defaults from flag and delete to either archive, move,  mark as read, or none for a cleaner message list</span></span>

#### <a name="relaxed-or-tighter-layout-you-choose"></a><span data-ttu-id="99c53-1029">寬鬆或緊密的版面配置？</span><span class="sxs-lookup"><span data-stu-id="99c53-1029">Relaxed or tighter layout?</span></span> <span data-ttu-id="99c53-1030">由您選擇</span><span class="sxs-lookup"><span data-stu-id="99c53-1030">You choose</span></span>

<span data-ttu-id="99c53-1031">若您想讓郵件之間能有更多空間，可以採用「緊密間距」；或者，您也可以採用緊密的版面配置，以便查看更多郵件。</span><span class="sxs-lookup"><span data-stu-id="99c53-1031">Use Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="99c53-1032">開始使用：</span><span class="sxs-lookup"><span data-stu-id="99c53-1032">Getting Started:</span></span>

<span data-ttu-id="99c53-1033">前往 [檢視] 索引標籤，勾選 [更緊密的間距] 核取方塊。若是使用傳統功能區，該核取方塊位於「郵件」群組內；若是使用簡化功能區，則是位於「目前檢視」設定當中</span><span class="sxs-lookup"><span data-stu-id="99c53-1033">View tab, use tighter spacing checkbox - in Messages group for classic ribbon, Current View settings for simplified ribbon</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="99c53-1034">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="99c53-1034">Scenarios to Try:</span></span>

<span data-ttu-id="99c53-1035">使用 Outlook 在未啟用設定的情況下分類及撰寫電子郵件。</span><span class="sxs-lookup"><span data-stu-id="99c53-1035">Use Outlook to triage and write email with and without the setting enabled.</span></span> <span data-ttu-id="99c53-1036">如果開啟 [使用更緊密的間距]，即可讓每個頁面能夠容納得下更多郵件，並讓撰寫表單的控制項更為簡潔。</span><span class="sxs-lookup"><span data-stu-id="99c53-1036">With Use tighter spacing on, more messages fit per page, and controls on the compose forms are more streamlined.</span></span>

#### <a name="dedupe-mru-entries-when-using-the-onedrive-sync-client"></a><span data-ttu-id="99c53-1037">使用 OneDrive 同步處理用戶端時的刪除重複資料 MRU 項目</span><span class="sxs-lookup"><span data-stu-id="99c53-1037">Dedupe MRU entries when using the Onedrive sync client</span></span>

<span data-ttu-id="99c53-1038">透過刪除重複資料 MRU 項目，改善 OneDrive 同步處理用戶端與雲端附件的整合度並加快附加速度，讓其速度足以媲美同步處理資料的複製行為</span><span class="sxs-lookup"><span data-stu-id="99c53-1038">Enable better integration with onedrive sync client with cloud attachments by deduping the mru entries and to enable faster attach as copy behavior for synchronized data</span></span>

##### <a name="getting-started"></a><span data-ttu-id="99c53-1039">開始使用：</span><span class="sxs-lookup"><span data-stu-id="99c53-1039">Getting Started:</span></span>

<span data-ttu-id="99c53-1040">若您使用的是 OneDrive 同步處理用戶端，將再也看不到「附加檔案 MRU」的檔案重複項目。</span><span class="sxs-lookup"><span data-stu-id="99c53-1040">If you use the OneDrive sync client, you will no longer see file duplicates in the Attach File MRU.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="99c53-1041">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="99c53-1041">Scenarios to Try:</span></span>

<span data-ttu-id="99c53-1042">啟用 OneDrive 同步處理用戶端，並使用 Outlook 電腦版的 [附加檔案] 功能表</span><span class="sxs-lookup"><span data-stu-id="99c53-1042">Enable the OneDrive sync client and use the Attach File menu in Outlook Desktop</span></span>

#### <a name="improved-shared-folder-synchronization-for-mailboxes-with-many-folders"></a><span data-ttu-id="99c53-1043">已改善擁有多個資料夾的信箱共用資料夾同步處理</span><span class="sxs-lookup"><span data-stu-id="99c53-1043">Improved shared folder synchronization for mailboxes with many folders</span></span>

<span data-ttu-id="99c53-1044">Outlook 多年來在同步共用信箱時，其資料夾的數量限制最多為 500 個。</span><span class="sxs-lookup"><span data-stu-id="99c53-1044">For years Outlook has been limited to a maximum of 500 folders when synchronizing shared mailboxes.</span></span> <span data-ttu-id="99c53-1045">透過這項變更已讓 Outlook 獲得改善，您在同步時將不會再遇到這 500 個資料夾的數量限制。</span><span class="sxs-lookup"><span data-stu-id="99c53-1045">With this change Outlook has been improved to sync in a way that will no longer encounter this 500 folder limit.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="99c53-1046">開始使用：</span><span class="sxs-lookup"><span data-stu-id="99c53-1046">Getting Started:</span></span>

<span data-ttu-id="99c53-1047">在信箱中新增 1000 個資料夾、讓其他人存取信箱、新增「其他人」的 Outlook 設定檔，然後確認同步處理是否可正常運作。</span><span class="sxs-lookup"><span data-stu-id="99c53-1047">Create 1000 folders in a mailbox, give someone else access to the mailbox, create an Outlook profile for the "someone else" and verify that sync works.</span></span>

### <a name="word"></a><span data-ttu-id="99c53-1048">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-1048">Word</span></span>

#### <a name="erase-just-a-little-bit"></a><span data-ttu-id="99c53-1049">小面積清除</span><span class="sxs-lookup"><span data-stu-id="99c53-1049">Erase just a little bit</span></span>

##### <a name="getting-started"></a><span data-ttu-id="99c53-1050">開始使用：</span><span class="sxs-lookup"><span data-stu-id="99c53-1050">Getting Started:</span></span>

<span data-ttu-id="99c53-1051">前往 [繪圖] 索引標籤。選取 [橡皮擦] 下拉式清單。</span><span class="sxs-lookup"><span data-stu-id="99c53-1051">Go to the Draw Tab. Select the Eraser dropdown.</span></span> <span data-ttu-id="99c53-1052">選擇 [小型橡皮擦] 或 [中型橡皮擦]。</span><span class="sxs-lookup"><span data-stu-id="99c53-1052">Choose Small Eraser or Medium Eraser.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="99c53-1053">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="99c53-1053">Scenarios to Try:</span></span>

<span data-ttu-id="99c53-1054">前往 [繪圖] 索引標籤。選取畫筆。</span><span class="sxs-lookup"><span data-stu-id="99c53-1054">Go to the Draw Tab. Select a pen.</span></span> <span data-ttu-id="99c53-1055">畫出一道筆跡線條。</span><span class="sxs-lookup"><span data-stu-id="99c53-1055">Draw an ink stroke.</span></span> <span data-ttu-id="99c53-1056">選取 [橡皮擦] 下拉式清單。</span><span class="sxs-lookup"><span data-stu-id="99c53-1056">Select the Eraser dropdown.</span></span> <span data-ttu-id="99c53-1057">選擇 [小型橡皮擦] 或 [中型橡皮擦]。</span><span class="sxs-lookup"><span data-stu-id="99c53-1057">Choose Small Eraser or Medium Eraser.</span></span> <span data-ttu-id="99c53-1058">清除一小塊的筆跡線條。</span><span class="sxs-lookup"><span data-stu-id="99c53-1058">Erase just bits of the ink stroke.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="99c53-1059">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="99c53-1059">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="99c53-1060">全部</span><span class="sxs-lookup"><span data-stu-id="99c53-1060">All</span></span> 
- <span data-ttu-id="99c53-1061">我們已修正可能會導致部分使用者無法儲存成 PDF 的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1061">We fixed an issue which could prevent some users from saving as PDF</span></span>
- <span data-ttu-id="99c53-1062">我們已修正可能會影響使用者在 32 位元系統上儲存大型檔案的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1062">We fixed an issue which could impact users saving large files on a 32-bit system</span></span>

### <a name="word"></a><span data-ttu-id="99c53-1063">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-1063">Word</span></span> 
- <span data-ttu-id="99c53-1064">我們已大幅改善 [聽寫] 功能的反應能力</span><span class="sxs-lookup"><span data-stu-id="99c53-1064">We significantly improved the responsiveness of the dictation feature</span></span>

### <a name="excel"></a><span data-ttu-id="99c53-1065">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-1065">Excel</span></span>
- <span data-ttu-id="99c53-1066">我們已修正按兩下事件在觸控式螢幕裝置上可能會失靈的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1066">We fixed an issue where double-click events could fail on touch screen devices</span></span>
- <span data-ttu-id="99c53-1067">我們已修正可能會導致部分使用者無法編輯 VBA 巨集的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1067">We fixed an issue which could prevent some users from being able to edit VBA macros</span></span>
- <span data-ttu-id="99c53-1068">我們已修正使用交叉分析篩選器時可能會影響效能的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1068">We fixed an issue which could impact performance when using slicers</span></span>

### <a name="powerpoint"></a><span data-ttu-id="99c53-1069">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-1069">PowerPoint</span></span>
- <span data-ttu-id="99c53-1070">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-1070">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="99c53-1071">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-1071">Outlook</span></span>
- <span data-ttu-id="99c53-1072">我們已修正從所選範本中會出現錯誤範本的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1072">We fixed an issue where the wrong template could be displayed from what was selected</span></span>

### <a name="access"></a><span data-ttu-id="99c53-1073">Access</span><span class="sxs-lookup"><span data-stu-id="99c53-1073">Access</span></span>
- <span data-ttu-id="99c53-1074">我們已修正在使用縮放建立器顯示完整 RTF 格式時，可能難以閱讀的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1074">We fixed an issue where using the zoom builder to display long rich text, could be hard to read</span></span>

### <a name="project"></a><span data-ttu-id="99c53-1075">Project</span><span class="sxs-lookup"><span data-stu-id="99c53-1075">Project</span></span>
- <span data-ttu-id="99c53-1076">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-1076">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-10-2019"></a><span data-ttu-id="99c53-1077">2019 年 5 月 10 日</span><span class="sxs-lookup"><span data-stu-id="99c53-1077">May 10, 2019</span></span>
<span data-ttu-id="99c53-1078">版本 1906 (組建 11702.20000)</span><span class="sxs-lookup"><span data-stu-id="99c53-1078">Version 1906 (build 11702.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="99c53-1079">新功能：</span><span class="sxs-lookup"><span data-stu-id="99c53-1079">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="99c53-1080">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-1080">Outlook</span></span>

<span data-ttu-id="99c53-1081">**在螢幕上容納更多郵件：** 選取 [檢視] > [使用更緊密的間距] 來調整郵件之間的間距。</span><span class="sxs-lookup"><span data-stu-id="99c53-1081">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="99c53-1082">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="99c53-1082">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="99c53-1083">全部</span><span class="sxs-lookup"><span data-stu-id="99c53-1083">All</span></span>
- <span data-ttu-id="99c53-1084">我們已修正 [另存新檔] 對話方塊顯示不正確路徑的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1084">We fixed an issue where the Save As dialog could display the incorrect path</span></span>

### <a name="word"></a><span data-ttu-id="99c53-1085">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-1085">Word</span></span> 
- <span data-ttu-id="99c53-1086">我們已修正有些「告訴我」選項無法插入的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1086">We fixed an issue where some selections from Tell Me would not get inserted</span></span>

### <a name="excel"></a><span data-ttu-id="99c53-1087">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-1087">Excel</span></span>
- <span data-ttu-id="99c53-1088">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-1088">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="99c53-1089">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-1089">PowerPoint</span></span>
- <span data-ttu-id="99c53-1090">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-1090">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="99c53-1091">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-1091">Outlook</span></span>
- <span data-ttu-id="99c53-1092">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-1092">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="99c53-1093">Access</span><span class="sxs-lookup"><span data-stu-id="99c53-1093">Access</span></span>
- <span data-ttu-id="99c53-1094">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-1094">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="99c53-1095">Project</span><span class="sxs-lookup"><span data-stu-id="99c53-1095">Project</span></span>
- <span data-ttu-id="99c53-1096">我們已修正任務識別碼需要醒目提示才能看見的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1096">We fixed an issue where Task ID's could require highlighting to see</span></span>

</BR></BR>

## <a name="may-3-2019"></a><span data-ttu-id="99c53-1097">2019 年 5 月 3 日</span><span class="sxs-lookup"><span data-stu-id="99c53-1097">May 3, 2019</span></span>
<span data-ttu-id="99c53-1098">版本 1906 (組建 11629.20008)</span><span class="sxs-lookup"><span data-stu-id="99c53-1098">Version 1906 (build 11629.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="99c53-1099">新功能：</span><span class="sxs-lookup"><span data-stu-id="99c53-1099">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="99c53-1100">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-1100">Outlook</span></span>

<span data-ttu-id="99c53-1101">**集中所有加密選項：** 只要前往 [選項] > [加密]，即可選擇要用來保護電子郵件訊息的方法。</span><span class="sxs-lookup"><span data-stu-id="99c53-1101">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="99c53-1102">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="99c53-1102">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="99c53-1103">全部</span><span class="sxs-lookup"><span data-stu-id="99c53-1103">All</span></span>
- <span data-ttu-id="99c53-1104">我們已修正有些使用者使用商務用 OneDrive 同步處理時遇到的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1104">We fixed an issue where some users would experience problems syncing with OneDrive for Business</span></span>

### <a name="word"></a><span data-ttu-id="99c53-1105">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-1105">Word</span></span> 
- <span data-ttu-id="99c53-1106">我們已修正在某些情況下，Word 會花很長時間啟動的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1106">We fixed an issue where in some cases Word would take a long time to start</span></span>

### <a name="excel"></a><span data-ttu-id="99c53-1107">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-1107">Excel</span></span>
- <span data-ttu-id="99c53-1108">我們已修正升級至較新版 Excel 後活頁簿的外部連結有時會被移除的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1108">We fixed an issue where external links were sometimes removed from workbooks after upgrading to a newer version of Excel</span></span>
- <span data-ttu-id="99c53-1109">我們已修正有些使用者可能會遇到無法在新活頁簿中選取儲存格的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1109">We fixed an issue where some users could experience difficulty selecting cells in a new workbook</span></span>

### <a name="powerpoint"></a><span data-ttu-id="99c53-1110">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-1110">PowerPoint</span></span>
- <span data-ttu-id="99c53-1111">我們已修正將繪圖轉換成文字時字型大小不一致的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1111">We fixed an issue where font sizes were not consistant when converting drawings to text</span></span>

### <a name="outlook"></a><span data-ttu-id="99c53-1112">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-1112">Outlook</span></span>
- <span data-ttu-id="99c53-1113">我們已修正從 .VCF 檔案儲存連絡人可能會導致空白欄位的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1113">We fixed an issue where saving a contact from a .VCF file could result in empty fields</span></span>
- <span data-ttu-id="99c53-1114">我們已修正即使郵件已寄出卻仍卡在寄件匣資料夾的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1114">We fixed an issue where a message could get stuck in the outbox folder even though it had been sent</span></span>
- <span data-ttu-id="99c53-1115">我們已修正檢視 DRM 訊息時 Outlook 可能會當機的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1115">We fixed an issue where Outlook could crash when viewing a DRM message</span></span>

### <a name="access"></a><span data-ttu-id="99c53-1116">Access</span><span class="sxs-lookup"><span data-stu-id="99c53-1116">Access</span></span>
- <span data-ttu-id="99c53-1117">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-1117">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="99c53-1118">Project</span><span class="sxs-lookup"><span data-stu-id="99c53-1118">Project</span></span>
- <span data-ttu-id="99c53-1119">我們已修正編輯器會從中文切換為英文的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1119">We fixed an issue where the editor would switch from Chinese to English</span></span>
- <span data-ttu-id="99c53-1120">我們已修正主專案的已發佈複本中出現未發佈工作的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1120">We fixed an issue where unpublished tasks could appear in the published copy of a master project</span></span>

</BR></BR>

## <a name="april-26-2019"></a><span data-ttu-id="99c53-1121">2019 年 4 月 26 日</span><span class="sxs-lookup"><span data-stu-id="99c53-1121">April 26, 2019</span></span>
<span data-ttu-id="99c53-1122">版本 1905 (組建 11617.20002)</span><span class="sxs-lookup"><span data-stu-id="99c53-1122">Version 1905 (build 11617.20002)</span></span>

## <a name="new-features"></a><span data-ttu-id="99c53-1123">新功能</span><span class="sxs-lookup"><span data-stu-id="99c53-1123">New Features</span></span>

### <a name="outlook"></a><span data-ttu-id="99c53-1124">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-1124">Outlook</span></span>

<span data-ttu-id="99c53-1125">**共用行事曆更新的速度更快：** 針對 Office 365 中的共用行事曆，Outlook 可以使用 REST API 更新這些行事曆。</span><span class="sxs-lookup"><span data-stu-id="99c53-1125">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="99c53-1126">開啟預覽以更快且更可靠地更新共用行事曆。</span><span class="sxs-lookup"><span data-stu-id="99c53-1126">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

### <a name="excel"></a><span data-ttu-id="99c53-1127">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-1127">Excel</span></span>

#### <a name="coauthoring-improvements"></a><span data-ttu-id="99c53-1128">共同撰寫的增強功能</span><span class="sxs-lookup"><span data-stu-id="99c53-1128">Coauthoring improvements</span></span>

<span data-ttu-id="99c53-1129">改善共同撰寫的體驗，盡可能讓其他人即時收到修改過的內容。</span><span class="sxs-lookup"><span data-stu-id="99c53-1129">Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

### <a name="visio"></a><span data-ttu-id="99c53-1130">Visio</span><span class="sxs-lookup"><span data-stu-id="99c53-1130">Visio</span></span>

- <span data-ttu-id="99c53-1131">**從 Power BI 匯出 Visio 視覺效果：** 當匯出 Power BI 報表為 PDF 或 PowerPoint 等更多檔案時，Power BI Visio 視覺效果會正常顯示。</span><span class="sxs-lookup"><span data-stu-id="99c53-1131">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="99c53-1132">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="99c53-1132">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="99c53-1133">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-1133">Word</span></span> 
- <span data-ttu-id="99c53-1134">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-1134">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="99c53-1135">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-1135">Excel</span></span>
- <span data-ttu-id="99c53-1136">我們已修正 Solver 巨集無法執行的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1136">We fixed an issue where Solver macros would fail to run</span></span>
- <span data-ttu-id="99c53-1137">我們已修正阻止 Excel 檔案匯入到 SharePoint 的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1137">We fixed an issue which could prevent Excel files from being imported into SharePoint</span></span>

### <a name="powerpoint"></a><span data-ttu-id="99c53-1138">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-1138">PowerPoint</span></span>
- <span data-ttu-id="99c53-1139">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-1139">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="99c53-1140">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-1140">Outlook</span></span>
- <span data-ttu-id="99c53-1141">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-1141">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="99c53-1142">Access</span><span class="sxs-lookup"><span data-stu-id="99c53-1142">Access</span></span>
- <span data-ttu-id="99c53-1143">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-1143">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="99c53-1144">Project</span><span class="sxs-lookup"><span data-stu-id="99c53-1144">Project</span></span>
- <span data-ttu-id="99c53-1145">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-1145">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-19-2019"></a><span data-ttu-id="99c53-1146">2019 年 4 月 19 日</span><span class="sxs-lookup"><span data-stu-id="99c53-1146">April 19, 2019</span></span>
<span data-ttu-id="99c53-1147">版本 1905 (組建 11609.20002)</span><span class="sxs-lookup"><span data-stu-id="99c53-1147">Version 1905 (build 11609.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="99c53-1148">新功能：</span><span class="sxs-lookup"><span data-stu-id="99c53-1148">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="99c53-1149">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-1149">Outlook</span></span>

<span data-ttu-id="99c53-1150">**搜尋人員時取得電子郵件建議：** 當您在 [搜尋] 方塊中輸入人員的名稱時，最相關的電子郵件訊息會包括在您的搜尋建議中。</span><span class="sxs-lookup"><span data-stu-id="99c53-1150">**Get email suggestions when you search for a person:** When you type a person’s name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span>

### <a name="excel"></a><span data-ttu-id="99c53-1151">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-1151">Excel</span></span>

#### <a name="improved-filled-maps-experience-using-data-types"></a><span data-ttu-id="99c53-1152">使用資料類型改善區域分布圖體驗</span><span class="sxs-lookup"><span data-stu-id="99c53-1152">Improved Filled Maps experience using Data Types</span></span>

<span data-ttu-id="99c53-1153">此功能是針對使用 Excel 的地理資料類型繪製區域分布圖圖表使用者的增強功能。</span><span class="sxs-lookup"><span data-stu-id="99c53-1153">This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="99c53-1154">對使用者的優點是功能之間有更豐富的整合，以及使用者要對應的區域會有更好的精確度。</span><span class="sxs-lookup"><span data-stu-id="99c53-1154">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="99c53-1155">其他優點包括功能能夠對應城市多邊形。</span><span class="sxs-lookup"><span data-stu-id="99c53-1155">Additional benefits include - ability to map city polygons.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="99c53-1156">開始使用：</span><span class="sxs-lookup"><span data-stu-id="99c53-1156">Getting Started:</span></span>

- <span data-ttu-id="99c53-1157">此功能是 Excel 內現有功能的增強功能。</span><span class="sxs-lookup"><span data-stu-id="99c53-1157">This feature is an improvement to the existing features within Excel.</span></span> <span data-ttu-id="99c53-1158">若要使用增強功能，請將位置轉換為豐富的實體，並使用區域分布圖繪製。</span><span class="sxs-lookup"><span data-stu-id="99c53-1158">To use the improvement - convert locations into Rich Entities and plot with Filled Maps.</span></span> 

##### <a name="scenarios-to-try"></a><span data-ttu-id="99c53-1159">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="99c53-1159">Scenarios to Try:</span></span>

- <span data-ttu-id="99c53-1160">使用者可以嘗試對應城市、省/市、縣/市、國家/地區和郵遞區號。</span><span class="sxs-lookup"><span data-stu-id="99c53-1160">Users can try mapping cities, states, counties, countries and zip codes.</span></span> 


## <a name="notable-fixes"></a><span data-ttu-id="99c53-1161">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="99c53-1161">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="99c53-1162">所有應用程式</span><span class="sxs-lookup"><span data-stu-id="99c53-1162">All Applications</span></span>
- <span data-ttu-id="99c53-1163">我們已修正每當應用程式啟動時會顯示 [初次執行] 對話方塊的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1163">We fixed an issue where the First Run dialog would display whenever an application was launched</span></span>
- <span data-ttu-id="99c53-1164">我們已修正 [另存新檔] 對話方塊中 SharePoint 連結可能遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-1164">We fixed an issue where a SharePoint link in the "save as" dialog could be missing.</span></span>
- <span data-ttu-id="99c53-1165">我們已修正使用者錯誤地看到 [立即修復] 對話方塊的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1165">We fixed an issue where users would incorrectly see a "Repair Now" dialog</span></span>

### <a name="word"></a><span data-ttu-id="99c53-1166">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-1166">Word</span></span> 
- <span data-ttu-id="99c53-1167">我們已修正某些使用者在要求字型時，可能會收到記憶體或磁碟空間不足錯誤的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1167">We fixed an issue where some users could receive an error for insufficient memory or disk space when requesting a font</span></span>
- <span data-ttu-id="99c53-1168">我們已修正視窗從 [註解] 窗格切換時，焦點可能會遺失的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1168">We fixed an issue where a window could lose focus when switching from the comments pane</span></span>

### <a name="excel"></a><span data-ttu-id="99c53-1169">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-1169">Excel</span></span>
- <span data-ttu-id="99c53-1170">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-1170">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="99c53-1171">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-1171">PowerPoint</span></span>
- <span data-ttu-id="99c53-1172">我們已修正會妨礙調整商標圖形大小的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1172">We fixed an issue preventing the resizing of branded shapes</span></span>
- <span data-ttu-id="99c53-1173">我們已修正在受保護的檢視模式中開啟檔案時，PowerPoint 會當機的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1173">We fixed an issue where PowerPoint could crash when opening a file in protected view mode</span></span>

### <a name="outlook"></a><span data-ttu-id="99c53-1174">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-1174">Outlook</span></span>
- <span data-ttu-id="99c53-1175">我們已修正會防礙一些使用者選取中文文字的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1175">We fixed an issue which prevented some users from selecting Chinese words</span></span>
- <span data-ttu-id="99c53-1176">我們已修正未正確計算到期日的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1176">We fixed an issue where expiry dates were not calculated correctly</span></span>

### <a name="access"></a><span data-ttu-id="99c53-1177">Access</span><span class="sxs-lookup"><span data-stu-id="99c53-1177">Access</span></span>
- <span data-ttu-id="99c53-1178">我們已修正會防礙一些使用者使用巨集建立器的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1178">We fixed an issue which prevented some users from using the Macro Builder</span></span>
- <span data-ttu-id="99c53-1179">我們已修正列印報表只會列印第一頁的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1179">We fixed an issue where printing a report would only print the first page</span></span>
- <span data-ttu-id="99c53-1180">我們已修正將游標移到超連結上時，應用程式會當機的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1180">We fixed an issue where the application could crash when hovering over a hyperlink</span></span>
- <span data-ttu-id="99c53-1181">我們已修正使用關聯性檢視檢視時，造成某些項目在螢幕上消失的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1181">We fixed an issue which caused some items to appear off screen when using relationships view</span></span>

### <a name="project"></a><span data-ttu-id="99c53-1182">Project</span><span class="sxs-lookup"><span data-stu-id="99c53-1182">Project</span></span>
- <span data-ttu-id="99c53-1183">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-1183">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-12-2019"></a><span data-ttu-id="99c53-1184">2019 年 4 月 12 日</span><span class="sxs-lookup"><span data-stu-id="99c53-1184">April 12, 2019</span></span>
<span data-ttu-id="99c53-1185">版本 1905 (組建 11601.20042)</span><span class="sxs-lookup"><span data-stu-id="99c53-1185">Version 1905 (build 11601.20042)</span></span>

## <a name="whats-new"></a><span data-ttu-id="99c53-1186">新功能：</span><span class="sxs-lookup"><span data-stu-id="99c53-1186">What's New:</span></span>

### <a name="access"></a><span data-ttu-id="99c53-1187">Access</span><span class="sxs-lookup"><span data-stu-id="99c53-1187">Access</span></span>

#### <a name="get-smart-with-microsoft-graph"></a><span data-ttu-id="99c53-1188">充分發揮 Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="99c53-1188">Get smart with Microsoft Graph</span></span>

<span data-ttu-id="99c53-1189">使用智慧型技術匯入或連結到智慧型資料，並重新打造您的桌面資料庫。</span><span class="sxs-lookup"><span data-stu-id="99c53-1189">Import or link to intelligent data and reinvent your desktop database with Intelligent Technology.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="99c53-1190">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="99c53-1190">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="99c53-1191">所有應用程式</span><span class="sxs-lookup"><span data-stu-id="99c53-1191">All Applications</span></span>
 - <span data-ttu-id="99c53-1192">我們已修正會防止使用者將檔案儲存到雲端位置的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1192">We fixed an issue which prevented some users from saving files to cloud locations</span></span>
 - <span data-ttu-id="99c53-1193">我們已修正可能從功能區開啟錯誤窗格的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1193">We fixed an issue where the wrong pane could open from the ribbon</span></span>

### <a name="word"></a><span data-ttu-id="99c53-1194">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-1194">Word</span></span> 
- <span data-ttu-id="99c53-1195">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-1195">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="99c53-1196">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-1196">Excel</span></span>
- <span data-ttu-id="99c53-1197">我們已修正當活頁簿不包含連結資料類型時，使用者會看到連結資料類型之錯誤訊息的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1197">We fixed an issue where users would see an error message for linked data types when the workbook did not contain linked data types</span></span>
- <span data-ttu-id="99c53-1198">我們已修正在本機與線上檢視 Word 文件時，文件中的 URL 連結可能變更的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1198">We fixed an issue where URL links within a Word document could change when viewed locally vs. online</span></span>

### <a name="powerpoint"></a><span data-ttu-id="99c53-1199">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-1199">PowerPoint</span></span>
- <span data-ttu-id="99c53-1200">我們已修正應用程式可能會在從 [動畫] 索引標籤復原變更之後當機的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1200">We fixed an issue where the application could crash after undoing changes from the animations tab</span></span>

### <a name="outlook"></a><span data-ttu-id="99c53-1201">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-1201">Outlook</span></span>
- <span data-ttu-id="99c53-1202">我們已修正會防止一些使用者修改公用資料夾中連絡人 [備註] 欄位的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1202">We fixed an issue which prevented some users from modifying the Notes field for contacts in a Public Folder</span></span>
- <span data-ttu-id="99c53-1203">我們已修正到期日與刪除日期之間可能發生衝突的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1203">We fixed an issue where a conflict could occur between expiration dates and deletion dates</span></span>

### <a name="access"></a><span data-ttu-id="99c53-1204">Access</span><span class="sxs-lookup"><span data-stu-id="99c53-1204">Access</span></span>
- <span data-ttu-id="99c53-1205">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-1205">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="99c53-1206">Project</span><span class="sxs-lookup"><span data-stu-id="99c53-1206">Project</span></span>
- <span data-ttu-id="99c53-1207">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-1207">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-5-2019"></a><span data-ttu-id="99c53-1208">2019 年 4 月 5 日</span><span class="sxs-lookup"><span data-stu-id="99c53-1208">April 5, 2019</span></span>
<span data-ttu-id="99c53-1209">版本 1904 (組建 11527.20014)</span><span class="sxs-lookup"><span data-stu-id="99c53-1209">Version 1904 (build 11527.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="99c53-1210">新功能：</span><span class="sxs-lookup"><span data-stu-id="99c53-1210">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="99c53-1211">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-1211">Outlook</span></span>

#### <a name="outlook-for-windows--set-and-share-your-focused-inbox-settings"></a><span data-ttu-id="99c53-1212">Windows 版 Outlook：設定並共用您的 [焦點收件匣] 設定</span><span class="sxs-lookup"><span data-stu-id="99c53-1212">Outlook for Windows:  set and share your Focused Inbox settings</span></span>

<span data-ttu-id="99c53-1213">[焦點收件匣] 喜好設定會儲存在雲端內，因此當您在任何電腦上使用 Windows 版 Outlook 和 Outlook 網頁版時，都可以取得相同的一致體驗。</span><span class="sxs-lookup"><span data-stu-id="99c53-1213">Your Focused Inbox preferences are stored in the cloud so you can enjoy the same consistent experience when using Outlook for Windows and Outlook on the web on any computer.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="99c53-1214">開始使用：</span><span class="sxs-lookup"><span data-stu-id="99c53-1214">Getting Started:</span></span>

<span data-ttu-id="99c53-1215">在 [檔案] > [選項] > [一般] 索引標籤下，還有一個名為 [將我的 Outlook 設定儲存在雲端中] 的新喜好設定。</span><span class="sxs-lookup"><span data-stu-id="99c53-1215">Under File > Options > General tab, there is a new preference for 'Store my Outlook settings in the cloud'.</span></span> <span data-ttu-id="99c53-1216">使用者需要核取方塊，才能讓他們的 [焦點收件匣] 設定漫遊到其他電腦的 Outlook 安裝和 OWA。</span><span class="sxs-lookup"><span data-stu-id="99c53-1216">Users will need to check the box to enable their Focused Inbox setting to roam to other Desktop Outlook installations and OWA.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="99c53-1217">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="99c53-1217">Scenarios to Try:</span></span>

<span data-ttu-id="99c53-1218">在已開啟雲端設定喜好設定的電腦上變更 [焦點收件匣]。</span><span class="sxs-lookup"><span data-stu-id="99c53-1218">Change Focused Inbox on the machine that has cloud settings preference turned on.</span></span> <span data-ttu-id="99c53-1219">瀏覽至 OWA，然後查看那裡也同樣套用了喜好設定。</span><span class="sxs-lookup"><span data-stu-id="99c53-1219">Navigate to OWA and see the preference applied there as well.</span></span> <span data-ttu-id="99c53-1220">在 OWA 變更 [焦點收件匣]，然後啟動電腦版 Outlook 查看已反映喜好設定。</span><span class="sxs-lookup"><span data-stu-id="99c53-1220">Change Focused Inbox in OWA and start Desktop Outlook to see the preference reflected.</span></span>

### <a name="word"></a><span data-ttu-id="99c53-1221">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-1221">Word</span></span>

#### <a name="learning-tools-mode-has-additional-support-for-more-page-colors"></a><span data-ttu-id="99c53-1222">[學習工具] 模式額外支援更多頁面色彩</span><span class="sxs-lookup"><span data-stu-id="99c53-1222">Learning Tools mode has additional support for more page colors</span></span>

<span data-ttu-id="99c53-1223">Word 中的 [學習工具] 新增更多頁面佈景主題色彩的支援，讓您能夠變更頁面的背景色彩。</span><span class="sxs-lookup"><span data-stu-id="99c53-1223">Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span>  <span data-ttu-id="99c53-1224">許多人在背景全白或全黑時閱讀會有困難，因此我們在 PC 和 Mac 的 Word 中增加了色彩選項。</span><span class="sxs-lookup"><span data-stu-id="99c53-1224">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="99c53-1225">開始使用：</span><span class="sxs-lookup"><span data-stu-id="99c53-1225">Getting Started:</span></span>

<span data-ttu-id="99c53-1226">若要試用，請移至 [檢視] 索引標籤，選擇 [學習工具]，然後選擇 [頁面色彩]。</span><span class="sxs-lookup"><span data-stu-id="99c53-1226">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="99c53-1227">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="99c53-1227">Scenarios to Try:</span></span>

<span data-ttu-id="99c53-1228">若要試用，請移至 [檢視] 索引標籤，選擇 [學習工具]，然後選擇 [頁面色彩]。</span><span class="sxs-lookup"><span data-stu-id="99c53-1228">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

### <a name="excel"></a><span data-ttu-id="99c53-1229">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-1229">Excel</span></span>

#### <a name="elevate-creativity-with-animated-3d-models"></a><span data-ttu-id="99c53-1230">以具備動畫效果的 3D 模型提高創意</span><span class="sxs-lookup"><span data-stu-id="99c53-1230">Elevate Creativity with Animated 3D Models</span></span>

<span data-ttu-id="99c53-1231">Office 現在支援動畫模型，這類模型能在編輯器中播放，讓您的試算表更生動！</span><span class="sxs-lookup"><span data-stu-id="99c53-1231">Office now supports animated models, which will playback in the editor so you can bring your sheets to life!</span></span>

#### <a name="getting-started"></a><span data-ttu-id="99c53-1232">開始使用：</span><span class="sxs-lookup"><span data-stu-id="99c53-1232">Getting Started:</span></span>

1. <span data-ttu-id="99c53-1233">開啟 Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-1233">Open Excel</span></span>
2. <span data-ttu-id="99c53-1234">插入具備動畫效果的 3D 模型 (很快會進到 Remix，但現在請在此位置存取動畫模型：\\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span><span class="sxs-lookup"><span data-stu-id="99c53-1234">Insert an animated 3D Model (coming to Remix soon, but for now, access animated models here: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span></span>
3. <span data-ttu-id="99c53-1235">動畫模型會在編輯器中播放！</span><span class="sxs-lookup"><span data-stu-id="99c53-1235">The animated model will play in the editor!</span></span> <span data-ttu-id="99c53-1236">[檢查投影片放映] 模式 - 動畫模型也會在那裡播放！</span><span class="sxs-lookup"><span data-stu-id="99c53-1236">Check Slideshow mode - it will play there too!</span></span>
4. <span data-ttu-id="99c53-1237">在 3D 格式功能區中，探索模型中更多的動畫場景</span><span class="sxs-lookup"><span data-stu-id="99c53-1237">In the 3D Format Ribbon, explore more animation scenes in the model</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="99c53-1238">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="99c53-1238">Scenarios to Try:</span></span>

1. <span data-ttu-id="99c53-1239">插入動畫模型，然後看它在編輯器中播放</span><span class="sxs-lookup"><span data-stu-id="99c53-1239">Insert an animated model and watch it play in the editor</span></span>
2. <span data-ttu-id="99c53-1240">透過 3D 格式功能區中的 [場景庫]，探索動畫模型中可用的動畫場景</span><span class="sxs-lookup"><span data-stu-id="99c53-1240">Explore the animation scenes available in the animated model via the Scenes Gallery, available in the 3D Format Ribbon</span></span>
3. <span data-ttu-id="99c53-1241">透過功能區、浮動工具列或空格鍵輕鬆地播放/暫停動畫</span><span class="sxs-lookup"><span data-stu-id="99c53-1241">Easily play/pause the animation via the ribbon, floatie or space bar</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="99c53-1242">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="99c53-1242">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="99c53-1243">所有應用程式</span><span class="sxs-lookup"><span data-stu-id="99c53-1243">All Applications</span></span>
- <span data-ttu-id="99c53-1244">我們已修正 Excel 的內容功能表中會出現錯誤應用程式圖示的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1244">We fixed an issue where the incorrect app icon could appear for Excel in contextual menus</span></span>
- <span data-ttu-id="99c53-1245">我們已修正在安裝更新之後 [檔案功能表] 按鈕會消失的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1245">We fixed an issue where the File Menu button could disappear after installing an update</span></span>
- <span data-ttu-id="99c53-1246">我們已修正會變更您的使用者授權的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1246">We fixed an issue which could change your user license</span></span>

### <a name="word"></a><span data-ttu-id="99c53-1247">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-1247">Word</span></span> 
- <span data-ttu-id="99c53-1248">我們已修正文字在特定縮放比例中無法正常顯示的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1248">We fixed an issue where text would not render correctly at certain zoom levels</span></span>

### <a name="excel"></a><span data-ttu-id="99c53-1249">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-1249">Excel</span></span>
- <span data-ttu-id="99c53-1250">我們已修正使用者在進行編輯之後未收到儲存活頁簿提示的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1250">We fixed an issue where users would not be prompted to save a workbook after making edits</span></span>
- <span data-ttu-id="99c53-1251">我們已修正當使用者共用活頁簿時未觸發 BeforeSave 事件的問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-1251">We fixed an issue where a BeforeSave event would not be triggered if the user shared the workbook.</span></span>
- <span data-ttu-id="99c53-1252">我們已修正將欄的大小重新調整為小於 6 像素會擲回不正確錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-1252">We fixed an issue where resizing a column to fewer than 6 pixels could throw an incorrect error message.</span></span>
- <span data-ttu-id="99c53-1253">我們已修正 Excel 忽略 Application.Visible 旗標的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1253">We fixed an issue where Excel would ignore the Application.Visible flag</span></span>
- <span data-ttu-id="99c53-1254">我們已修正追蹤箭號保留在非作用中凍結窗格的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1254">We fixed an issue where trace arrows would remain on non-active frozen panes</span></span>
- <span data-ttu-id="99c53-1255">我們已修正在開啟活頁簿時日期和貨幣儲存格格式會變更的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1255">We fixed an issue where cell formatting of dates an currency could change when opening a workbook</span></span>
- <span data-ttu-id="99c53-1256">我們已修正工具提示會意外移動的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1256">We fixed an issue where tooltips would move unexpectedly</span></span>
- <span data-ttu-id="99c53-1257">我們已修正 Power Query 編輯器的當地語系化問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1257">We fixed localization issues for the Power Query editor</span></span>
- <span data-ttu-id="99c53-1258">我們已修正在透過電子郵件傳送時活頁簿附件會遭到移除的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1258">We fixed an issue where a workbook would be removed as an attachment when sending via e-mail</span></span>

### <a name="powerpoint"></a><span data-ttu-id="99c53-1259">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-1259">PowerPoint</span></span>
- <span data-ttu-id="99c53-1260">我們已修正複製圖形會比預期還要久的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1260">We fixed an issue where copying shapes would take longer than expected</span></span>

### <a name="outlook"></a><span data-ttu-id="99c53-1261">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-1261">Outlook</span></span>
- <span data-ttu-id="99c53-1262">我們已修正在使用繪圖工具時 Outlook 可能會當機的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1262">We fixed an issue where Outlook could crash while using the drawing tool</span></span>
- <span data-ttu-id="99c53-1263">我們已修正當撰寫 html 電子郵件時的當地語系化問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1263">We fixed a localization issue when composing html e-mails</span></span>
- <span data-ttu-id="99c53-1264">我們已修正使用者在選取下面窗格時會遇到困難的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1264">We fixed an issue where the user would have difficulty in selecting the lower pane</span></span>

### <a name="access"></a><span data-ttu-id="99c53-1265">Access</span><span class="sxs-lookup"><span data-stu-id="99c53-1265">Access</span></span>
- <span data-ttu-id="99c53-1266">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-1266">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="99c53-1267">Project</span><span class="sxs-lookup"><span data-stu-id="99c53-1267">Project</span></span>
- <span data-ttu-id="99c53-1268">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-1268">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-22-2019"></a><span data-ttu-id="99c53-1269">2019 年 3 月 22 日</span><span class="sxs-lookup"><span data-stu-id="99c53-1269">March 22, 2019</span></span>
<span data-ttu-id="99c53-1270">版本 1904 (組建 11514.20004)</span><span class="sxs-lookup"><span data-stu-id="99c53-1270">Version 1904 (build 11514.20004)</span></span>

## <a name="new-features"></a><span data-ttu-id="99c53-1271">新功能</span><span class="sxs-lookup"><span data-stu-id="99c53-1271">New Features</span></span>

- <span data-ttu-id="99c53-1272">**隱私權控制：** 用於診斷資料和連線體驗的新增、更新及改良的控制項。</span><span class="sxs-lookup"><span data-stu-id="99c53-1272">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> <span data-ttu-id="99c53-1273">深入了解 <https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json></span><span class="sxs-lookup"><span data-stu-id="99c53-1273">Learn more <https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json></span></span>

- <span data-ttu-id="99c53-1274">**Office 圖示有新的外觀：** Office 圖示經過重新設計，以反映簡單、功能強大且智慧型的 Office 體驗。</span><span class="sxs-lookup"><span data-stu-id="99c53-1274">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="99c53-1275">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="99c53-1275">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="99c53-1276">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-1276">Word</span></span> 
- <span data-ttu-id="99c53-1277">我們已修正 UI 經常會顯示「正在檢查變更」的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1277">We fixed an issue where the UI would constantly display "Checking for Changes"</span></span>

### <a name="excel"></a><span data-ttu-id="99c53-1278">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-1278">Excel</span></span>
- <span data-ttu-id="99c53-1279">我們已修正應用程式可能在移動工作表之後當機的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1279">We fixed an issue where the application could crash after moving a worksheet</span></span>
- <span data-ttu-id="99c53-1280">我們已修正應用程式可能在儲存為 PDF 之後當機的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1280">We fixed an issue where the application could crash after saving as a PDF</span></span>
- <span data-ttu-id="99c53-1281">我們已修正儲存對話方塊不會接受某些韓文字元的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1281">We fixed an issue where the save dialog would not accept some Korean characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="99c53-1282">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-1282">PowerPoint</span></span>
- <span data-ttu-id="99c53-1283">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-1283">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="99c53-1284">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-1284">Outlook</span></span>
- <span data-ttu-id="99c53-1285">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-1285">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="99c53-1286">Access</span><span class="sxs-lookup"><span data-stu-id="99c53-1286">Access</span></span>
- <span data-ttu-id="99c53-1287">我們已修正 Access 中對 Access 建立額外捷徑的錯誤訊息</span><span class="sxs-lookup"><span data-stu-id="99c53-1287">We fixed the error message in Access where an extra shortcut to Access was created</span></span>
- <span data-ttu-id="99c53-1288">我們已修正來自連結 SharePoint 的資料無法正確顯示的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1288">We fixed an issue where data from a linked SharePoint would display incorrectly</span></span>

### <a name="project"></a><span data-ttu-id="99c53-1289">Project</span><span class="sxs-lookup"><span data-stu-id="99c53-1289">Project</span></span>
- <span data-ttu-id="99c53-1290">我們已修正語言設定會從中文切換為英文的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1290">We fixed an issue where the language settings would switch from Chinese to English</span></span>
- <span data-ttu-id="99c53-1291">我們已修正應用程式可能在同步處理到 SharePoint 時當機的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1291">We fixed an issue where the application could crash when synching to SharePoint</span></span>

</BR></BR>

## <a name="march-15-2019"></a><span data-ttu-id="99c53-1292">2019 年 3 月 15 日</span><span class="sxs-lookup"><span data-stu-id="99c53-1292">March 15, 2019</span></span>
<span data-ttu-id="99c53-1293">版本 1904 (組建 11504.20000)</span><span class="sxs-lookup"><span data-stu-id="99c53-1293">Version 1904 (build 11504.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="99c53-1294">新功能：</span><span class="sxs-lookup"><span data-stu-id="99c53-1294">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="99c53-1295">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-1295">Word</span></span>

#### <a name="focus-mode"></a><span data-ttu-id="99c53-1296">焦點模式</span><span class="sxs-lookup"><span data-stu-id="99c53-1296">Focus Mode</span></span>

<span data-ttu-id="99c53-1297">切換到 [檢視] 功能表中的 [焦點] 以移除令人分心的事物，讓您更能專注於工作。</span><span class="sxs-lookup"><span data-stu-id="99c53-1297">Switch to Focus on the View menu to remove distractions and concentrate on your work.</span></span> <span data-ttu-id="99c53-1298">僅供 Office 365 訂閱者使用。</span><span class="sxs-lookup"><span data-stu-id="99c53-1298">For Office 365 subscribers only.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="99c53-1299">開始使用：</span><span class="sxs-lookup"><span data-stu-id="99c53-1299">Getting Started:</span></span>

<span data-ttu-id="99c53-1300">[檢視] 索引標籤 功能區狀態列中的 [焦點] 按鈕 [焦點] 按鈕</span><span class="sxs-lookup"><span data-stu-id="99c53-1300">View tab "Focus" Button in the Ribbon Status Bar "Focus" Button</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="99c53-1301">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="99c53-1301">Scenarios to Try:</span></span>

<span data-ttu-id="99c53-1302">進入焦點模式，享受專注的體驗</span><span class="sxs-lookup"><span data-stu-id="99c53-1302">Enter Focus Mode and experience the Focused Experience</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="99c53-1303">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="99c53-1303">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="99c53-1304">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-1304">Word</span></span> 
- <span data-ttu-id="99c53-1305">我們已修正以 PDF 格式儲存文件時，文件中影像的 DPI 會不正確的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1305">We fixed an issue where images in a document saved as a PDF would have the incorrect DPI</span></span>

### <a name="excel"></a><span data-ttu-id="99c53-1306">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-1306">Excel</span></span>
- <span data-ttu-id="99c53-1307">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-1307">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="99c53-1308">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-1308">PowerPoint</span></span>
- <span data-ttu-id="99c53-1309">我們已修正註解窗格無法正確開啟或關閉的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1309">We fixed an issue where the comments pane would not open or close properly</span></span>
- <span data-ttu-id="99c53-1310">我們已修正應用程式會在刪除影片時當機的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1310">We fixed an issue where the application could crash when deleting a video</span></span>
- <span data-ttu-id="99c53-1311">我們已修正於某些情況下應用程式會無法啟動的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1311">We fixed an issue where in some instances the application would fail to launch</span></span>

### <a name="outlook"></a><span data-ttu-id="99c53-1312">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-1312">Outlook</span></span>
- <span data-ttu-id="99c53-1313">我們已修正以日文檢視時讀信回條不正確的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1313">We fixed an issue where read receipts were incorrect when viewed in Japanese</span></span>

### <a name="access"></a><span data-ttu-id="99c53-1314">Access</span><span class="sxs-lookup"><span data-stu-id="99c53-1314">Access</span></span>
- <span data-ttu-id="99c53-1315">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-1315">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="99c53-1316">Project</span><span class="sxs-lookup"><span data-stu-id="99c53-1316">Project</span></span>
- <span data-ttu-id="99c53-1317">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-1317">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-8-2019"></a><span data-ttu-id="99c53-1318">2019 年 3 月 8 日</span><span class="sxs-lookup"><span data-stu-id="99c53-1318">March 8, 2019</span></span> 
<span data-ttu-id="99c53-1319">版本 1903 (組建 11425.20036)</span><span class="sxs-lookup"><span data-stu-id="99c53-1319">Version 1903 (build 11425.20036)</span></span>

## <a name="whats-new"></a><span data-ttu-id="99c53-1320">新功能：</span><span class="sxs-lookup"><span data-stu-id="99c53-1320">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="99c53-1321">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-1321">Word</span></span>

### <a name="find-what-youre-looking-for-with-microsoft-search"></a><span data-ttu-id="99c53-1322">使用 Microsoft Search 尋找您要的內容</span><span class="sxs-lookup"><span data-stu-id="99c53-1322">Find What You're Looking For with Microsoft Search</span></span>

<span data-ttu-id="99c53-1323">您可以使用 Microsoft Search 找到所有檔案、動作、人員，協助您完成工作所需。</span><span class="sxs-lookup"><span data-stu-id="99c53-1323">With Microsoft Search, you can find all the files, actions, people, and help you need to get work done.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="99c53-1324">開始使用：</span><span class="sxs-lookup"><span data-stu-id="99c53-1324">Getting Started:</span></span>

- <span data-ttu-id="99c53-1325">這個功能在標題中的 UI 上方強調顯示。</span><span class="sxs-lookup"><span data-stu-id="99c53-1325">The feature is prominently displayed on top of the UI in the header.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="99c53-1326">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="99c53-1326">Scenarios to Try:</span></span>

- <span data-ttu-id="99c53-1327">搜尋某間大學、最近使用過的文件或搜尋最常用的功能區命令</span><span class="sxs-lookup"><span data-stu-id="99c53-1327">Search for a college, a recent document or search for the ribbon commands you use most often</span></span>
- <span data-ttu-id="99c53-1328">尋找某個主題或主旨並取得更多相關資訊</span><span class="sxs-lookup"><span data-stu-id="99c53-1328">Look up a topic or subject to get more information on it</span></span>
- 
#### <a name="coauthoring"></a><span data-ttu-id="99c53-1329">共同撰寫</span><span class="sxs-lookup"><span data-stu-id="99c53-1329">CoAuthoring</span></span>

<span data-ttu-id="99c53-1330">厭倦於被包含巨集的文件阻礙了嗎？</span><span class="sxs-lookup"><span data-stu-id="99c53-1330">Tired of being locked out of your document with macros?</span></span> <span data-ttu-id="99c53-1331">現在商務用 OneDrive 的 docm 檔案允許同時由多個作者編輯。</span><span class="sxs-lookup"><span data-stu-id="99c53-1331">Now your docm files on OneDrive for Business allow simultaneous editing by multiple authors.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="99c53-1332">開始使用：</span><span class="sxs-lookup"><span data-stu-id="99c53-1332">Getting Started:</span></span>

<span data-ttu-id="99c53-1333">使用者在 UI 中不需要按下任何按鈕，就能存取這項功能。</span><span class="sxs-lookup"><span data-stu-id="99c53-1333">The user doesn't need to press any buttons in the UI to access this feature.</span></span> <span data-ttu-id="99c53-1334">商務用 OneDrive 的 docm 檔案預設已啟用此功能。</span><span class="sxs-lookup"><span data-stu-id="99c53-1334">It is enabled by default on OneDrive for Business docm files.</span></span>
<span data-ttu-id="99c53-1335">因此，使用者應該將 docm 檔案儲存至商務用 OneDrive 試用看看。</span><span class="sxs-lookup"><span data-stu-id="99c53-1335">So, the user should save a docm file to OneDrive for Business to try it out.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="99c53-1336">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="99c53-1336">Scenarios to Try:</span></span>

<span data-ttu-id="99c53-1337">在商務用 OneDrive 建立 docm 檔案、與同事共用並且共同作業！</span><span class="sxs-lookup"><span data-stu-id="99c53-1337">Create a docm file on OneDrive for Business, share it with your colleagues, and collaborate!</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="99c53-1338">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="99c53-1338">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="99c53-1339">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-1339">Word</span></span> 
- <span data-ttu-id="99c53-1340">我們已修正在 [選項] 中按下 ESC 鍵時發生的當機問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1340">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="99c53-1341">我們已修正回覆註解時發生的當機問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1341">We fixed a crashing issue that occurred when replying to comments</span></span>
- <span data-ttu-id="99c53-1342">我們已修正從 Word 到 PowerPoint Online 的複製與貼上問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1342">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="99c53-1343">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-1343">Excel</span></span>
- <span data-ttu-id="99c53-1344">我們已修正當受保護的文件和可編輯的文件在開啟時複製 Excel 儲存格導致高 CPU 使用率的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1344">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="99c53-1345">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-1345">PowerPoint</span></span>
- <span data-ttu-id="99c53-1346">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-1346">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="99c53-1347">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-1347">Outlook</span></span>
- <span data-ttu-id="99c53-1348">我們已修正 Outlook 搜尋未依所選時間順序排序的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1348">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="99c53-1349">我們已修正 [開啟此工作] 工作流程功能區按鈕無法回應特定電子郵件的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1349">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="99c53-1350">我們已修正使用者在 [會議室尋找工具] 中選取可用的會議室後，Outlook 無法清除內部部署會議室的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1350">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="99c53-1351">Access</span><span class="sxs-lookup"><span data-stu-id="99c53-1351">Access</span></span>
- <span data-ttu-id="99c53-1352">我們已修正已儲存的匯入/匯出對話方塊在深色佈景主題中有白色文字在白色背景的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1352">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="99c53-1353">我們已修正使用者在表格設計中無法針對 [文字方塊] 的 [是/否] 欄位設定 DisplayControl 屬性的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1353">We fixed an issue where users could not set the DisplayControl property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="99c53-1354">Project</span><span class="sxs-lookup"><span data-stu-id="99c53-1354">Project</span></span>
- <span data-ttu-id="99c53-1355">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-1355">Various performance and stability fixes</span></span>


## <a name="march-1-2019"></a><span data-ttu-id="99c53-1356">2019 年 3 月 1 日</span><span class="sxs-lookup"><span data-stu-id="99c53-1356">March 1, 2019</span></span> 
<span data-ttu-id="99c53-1357">版本 1903 (組建 11414.20014)</span><span class="sxs-lookup"><span data-stu-id="99c53-1357">Version 1903 (build 11414.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="99c53-1358">新功能</span><span class="sxs-lookup"><span data-stu-id="99c53-1358">What's New</span></span>

### <a name="word"></a><span data-ttu-id="99c53-1359">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-1359">Word</span></span>

#### <a name="colors-for-track-changes-comments-and-real-time-collaboration-in-sync"></a><span data-ttu-id="99c53-1360">追蹤修訂、註解和即時共同作業的色彩會同步</span><span class="sxs-lookup"><span data-stu-id="99c53-1360">Colors for Track Changes, Comments and Real-Time Collaboration in Sync</span></span>

<span data-ttu-id="99c53-1361">我們產品中的修正現在可確保註解、追蹤修訂及共同作業者的游標會以相同色彩顯示。</span><span class="sxs-lookup"><span data-stu-id="99c53-1361">Fixes in our product now ensure that the comments, track changes and the cursor for a collaborator show up in the same color.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="99c53-1362">開始使用：</span><span class="sxs-lookup"><span data-stu-id="99c53-1362">Getting Started:</span></span>

<span data-ttu-id="99c53-1363">開啟其他人已開啟的 SharePoint 或 OneDrive 文件。</span><span class="sxs-lookup"><span data-stu-id="99c53-1363">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="99c53-1364">確認使用者的追蹤修訂和註解色彩符合該使用者游標的色彩。</span><span class="sxs-lookup"><span data-stu-id="99c53-1364">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="99c53-1365">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="99c53-1365">Scenarios to Try:</span></span>

<span data-ttu-id="99c53-1366">開啟其他人已開啟的 SharePoint 或 OneDrive 文件。</span><span class="sxs-lookup"><span data-stu-id="99c53-1366">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="99c53-1367">確認使用者的追蹤修訂和註解色彩符合該使用者游標的色彩。</span><span class="sxs-lookup"><span data-stu-id="99c53-1367">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="99c53-1368">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="99c53-1368">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="99c53-1369">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-1369">Word</span></span> 
- <span data-ttu-id="99c53-1370">我們已修正在 [選項] 中按下 ESC 鍵時發生的當機問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1370">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="99c53-1371">我們已修正從 Word 到 PowerPoint Online 的複製與貼上問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1371">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="99c53-1372">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-1372">Excel</span></span>
- <span data-ttu-id="99c53-1373">我們已修正當受保護的文件和可編輯的文件在開啟時複製 Excel 儲存格導致高 CPU 使用率的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1373">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="99c53-1374">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-1374">PowerPoint</span></span>
- <span data-ttu-id="99c53-1375">我們已修正在 PowerPoint 中使用 @提及的投影片圖像大小問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1375">We fixed an issue with slide image size when using @Mentions in PowerPoint</span></span>

### <a name="outlook"></a><span data-ttu-id="99c53-1376">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-1376">Outlook</span></span>
- <span data-ttu-id="99c53-1377">我們已修正 Outlook 搜尋未依所選時間順序排序的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1377">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="99c53-1378">我們已修正 [開啟此工作] 工作流程功能區按鈕無法回應特定電子郵件的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1378">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="99c53-1379">我們已修正使用者在 [會議室尋找工具] 中選取可用的會議室後，Outlook 無法清除內部部署會議室的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1379">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="99c53-1380">Access</span><span class="sxs-lookup"><span data-stu-id="99c53-1380">Access</span></span>
- <span data-ttu-id="99c53-1381">我們已更新確認使用資料來源重新連結資料表時顯示的提示文字</span><span class="sxs-lookup"><span data-stu-id="99c53-1381">We updated the prompt text that showed when confirming the relinking tables with a datasource</span></span>
- <span data-ttu-id="99c53-1382">我們已修正已儲存的匯入/匯出對話方塊在深色佈景主題中有白色文字在白色背景的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1382">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="99c53-1383">我們已修正使用者在表格設計中無法針對 [文字方塊] 的 [是/否] 欄位設定 [顯示控制項] 屬性的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1383">We fixed an issue where users could not set the Display Control property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="99c53-1384">Project</span><span class="sxs-lookup"><span data-stu-id="99c53-1384">Project</span></span>
- <span data-ttu-id="99c53-1385">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-1385">Various performance and stability fixes</span></span>

</BR></BR>



## <a name="february-15-2019"></a><span data-ttu-id="99c53-1386">2019 年 2 月 15 日</span><span class="sxs-lookup"><span data-stu-id="99c53-1386">February 15, 2019</span></span> 
<span data-ttu-id="99c53-1387">版本 1903 (組建 11310.20016)</span><span class="sxs-lookup"><span data-stu-id="99c53-1387">Version 1903 (build 11310.20016)</span></span>

## <a name="whats-new"></a><span data-ttu-id="99c53-1388">新功能：</span><span class="sxs-lookup"><span data-stu-id="99c53-1388">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="99c53-1389">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-1389">PowerPoint</span></span>


### <a name="morph-transition-enhancements---morph-by-name"></a><span data-ttu-id="99c53-1390">轉化轉場增強效果 - 依名稱轉化</span><span class="sxs-lookup"><span data-stu-id="99c53-1390">Morph Transition Enhancements - Morph by Name</span></span>

<span data-ttu-id="99c53-1391">選取要轉化的圖形</span><span class="sxs-lookup"><span data-stu-id="99c53-1391">Specify the shapes you want to morph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="99c53-1392">開始使用：</span><span class="sxs-lookup"><span data-stu-id="99c53-1392">Getting Started:</span></span>

- <span data-ttu-id="99c53-1393">若要使轉化將兩個物件視為同一個物件，使用者可以使用 [選取窗格] 重新命名圖形。</span><span class="sxs-lookup"><span data-stu-id="99c53-1393">To get Morph to treat two objects as the same object, the user can rename the shapes using the Selection Pane.</span></span>
- <span data-ttu-id="99c53-1394">名稱前面必須加上「!!」</span><span class="sxs-lookup"><span data-stu-id="99c53-1394">The name must be prefaced with “!!”</span></span> <span data-ttu-id="99c53-1395">(兩個半形驚嘆號)，例如「!!名稱」，轉化才能用來覆寫預設比對行為</span><span class="sxs-lookup"><span data-stu-id="99c53-1395">(two exclamation points) for Morph to use it to override our default matching behavior, e.g. “!!Name”</span></span>
- <span data-ttu-id="99c53-1396">使用者可以繼續將圖形重新命名為不是以「!!」為開頭的任何名稱</span><span class="sxs-lookup"><span data-stu-id="99c53-1396">Users can continue to rename shapes with any name that doesn’t start with “!!”</span></span> <span data-ttu-id="99c53-1397">不必擔心會變更轉化的運作方式</span><span class="sxs-lookup"><span data-stu-id="99c53-1397">without worrying that it will change the way Morph works</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="99c53-1398">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="99c53-1398">Scenarios to Try:</span></span>

- <span data-ttu-id="99c53-1399">在投影片中插入圖形，讓我們假設是矩形</span><span class="sxs-lookup"><span data-stu-id="99c53-1399">Insert a Shape in a slide, let's say Rectangle</span></span>
- <span data-ttu-id="99c53-1400">建立新投影片</span><span class="sxs-lookup"><span data-stu-id="99c53-1400">Create a new slide</span></span>
- <span data-ttu-id="99c53-1401">在第 2 張投影片中插入不同的圖形，讓我們假設是三角形</span><span class="sxs-lookup"><span data-stu-id="99c53-1401">Insert a different shape in the 2nd slide, let's say Triangle</span></span>
- <span data-ttu-id="99c53-1402">開啟 [選取窗格]，將投影片 1 中的矩形重新命名為「!!圖形」，將投影片 2 中的三角形重新命名為「!!圖形」</span><span class="sxs-lookup"><span data-stu-id="99c53-1402">Open SelectionPane, rename the Rectangle in slide 1 to "!!shape", and rename the Triangle in slide 2 to "!!shape"</span></span>
- <span data-ttu-id="99c53-1403">將 [轉化] 套用至第 2 張投影片</span><span class="sxs-lookup"><span data-stu-id="99c53-1403">Apply Morph on the 2nd slide</span></span>

</BR>

### <a name="morph-transition-enhancements---smartart"></a><span data-ttu-id="99c53-1404">轉化轉場增強效果 - SmartArt</span><span class="sxs-lookup"><span data-stu-id="99c53-1404">Morph Transition Enhancements - SmartArt</span></span>

<span data-ttu-id="99c53-1405">轉場更順暢的 SmartArt 轉化</span><span class="sxs-lookup"><span data-stu-id="99c53-1405">SmartArt morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="99c53-1406">開始使用：</span><span class="sxs-lookup"><span data-stu-id="99c53-1406">Getting Started:</span></span>

<span data-ttu-id="99c53-1407">您使用 SmartArt 的方式與轉化相同</span><span class="sxs-lookup"><span data-stu-id="99c53-1407">Use Morph the same way you would with SmartArt</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="99c53-1408">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="99c53-1408">Scenarios to Try:</span></span>

- <span data-ttu-id="99c53-1409">在投影片中插入 SmartArt</span><span class="sxs-lookup"><span data-stu-id="99c53-1409">Insert a SmartArt in a slide</span></span>
- <span data-ttu-id="99c53-1410">複製投影片</span><span class="sxs-lookup"><span data-stu-id="99c53-1410">Duplicate the Slide</span></span>
- <span data-ttu-id="99c53-1411">在複製的投影片上調整大小/變更/移動 SmartArt</span><span class="sxs-lookup"><span data-stu-id="99c53-1411">Resize/Change/Move the SmartArt on the duplicated slide</span></span>
- <span data-ttu-id="99c53-1412">在複製的投影片上套用 [轉化]</span><span class="sxs-lookup"><span data-stu-id="99c53-1412">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="morph-transition-enhancements---tables"></a><span data-ttu-id="99c53-1413">轉化轉場增強效果 - 表格​​</span><span class="sxs-lookup"><span data-stu-id="99c53-1413">Morph Transition Enhancements - Tables</span></span>

<span data-ttu-id="99c53-1414">轉場更順暢的表格轉化</span><span class="sxs-lookup"><span data-stu-id="99c53-1414">Tables morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="99c53-1415">開始使用：</span><span class="sxs-lookup"><span data-stu-id="99c53-1415">Getting Started:</span></span>
<span data-ttu-id="99c53-1416">您使用表格的方式與轉化相同</span><span class="sxs-lookup"><span data-stu-id="99c53-1416">Use Morph the same way you would with tables</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="99c53-1417">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="99c53-1417">Scenarios to Try:</span></span>

- <span data-ttu-id="99c53-1418">在投影片中插入表格</span><span class="sxs-lookup"><span data-stu-id="99c53-1418">Insert a Table in a slide</span></span>
- <span data-ttu-id="99c53-1419">複製投影片</span><span class="sxs-lookup"><span data-stu-id="99c53-1419">Duplicate the slide</span></span>
- <span data-ttu-id="99c53-1420">在複製的投影片上調整大小/變更/移動表格</span><span class="sxs-lookup"><span data-stu-id="99c53-1420">Resize/Change/Move the Table on the duplicated slide</span></span>
- <span data-ttu-id="99c53-1421">在複製的投影片上套用 [轉化]</span><span class="sxs-lookup"><span data-stu-id="99c53-1421">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a><span data-ttu-id="99c53-1422">Word、Excel、PowerPoint、OneNote、Access、Project、Publisher 和 Visio</span><span class="sxs-lookup"><span data-stu-id="99c53-1422">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span></span>

### <a name="seamlessly-switch-between-accounts"></a><span data-ttu-id="99c53-1423">在不同帳戶之間順暢切換</span><span class="sxs-lookup"><span data-stu-id="99c53-1423">Seamlessly Switch Between Accounts</span></span>

<span data-ttu-id="99c53-1424">全新的帳戶管理員會在同一個地方顯示您所有的工作和個人帳戶，讓您能控制在其間切換。</span><span class="sxs-lookup"><span data-stu-id="99c53-1424">The new account manager shows all of your work and personal accounts in one place, and puts you in control of switching between them.</span></span> <span data-ttu-id="99c53-1425">這項更新的經驗能清楚知道您的登入方法，因此您現在不需要先登出或處理複雜的對話方塊就可以切換工作和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="99c53-1425">This updated experience makes it clear how you're logged in, and now you can toggle between work and personal accounts without having to sign out first or deal with complex dialogs.</span></span>


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a><span data-ttu-id="99c53-1427">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="99c53-1427">Scenarios to Try:</span></span>
- <span data-ttu-id="99c53-1428">在不同的帳戶之間切換</span><span class="sxs-lookup"><span data-stu-id="99c53-1428">Switch between accounts</span></span>
- <span data-ttu-id="99c53-1429">新增帳戶 [附註：您可能想要先移至 [檔案] | [帳戶] | [已連線服務]，移除任何已連線至工作帳戶的個人服務或是反向服務]</span><span class="sxs-lookup"><span data-stu-id="99c53-1429">Add a new account [Note: you may want to first go to File | Account | Connected Services and remove any personal services connected to work accounts or vice versa]</span></span>
- <span data-ttu-id="99c53-1430">登出帳戶</span><span class="sxs-lookup"><span data-stu-id="99c53-1430">Sign out from an account</span></span>
</BR>

## <a name="notable-fixes"></a><span data-ttu-id="99c53-1431">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="99c53-1431">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="99c53-1432">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-1432">Word</span></span> 
- <span data-ttu-id="99c53-1433">我們已修正表格和影像的內容預覽問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1433">We fixed an issue with context preview for tables & images</span></span>

### <a name="excel"></a><span data-ttu-id="99c53-1434">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-1434">Excel</span></span>
- <span data-ttu-id="99c53-1435">我們已修正在黑色佈景主題中，自動篩選的搜尋欄位中文字是白色的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1435">We fixed an issue where text in autofilter Search field is white in Black theme</span></span>
- <span data-ttu-id="99c53-1436">我們已修正新 Office 增益集的同意 UI 問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1436">We fixed a consent UI issue with New Office Add-in</span></span>

### <a name="powerpoint"></a><span data-ttu-id="99c53-1437">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-1437">PowerPoint</span></span>
- <span data-ttu-id="99c53-1438">我們已修正在膝上型電腦或平板電腦上進行投影片簡報時自動延伸顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="99c53-1438">We fixed an issue with automatically extending display when presenting SlideShows on laptops or tablets.</span></span>

### <a name="outlook"></a><span data-ttu-id="99c53-1439">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-1439">Outlook</span></span>
- <span data-ttu-id="99c53-1440">我們已修正 [傳送至 OneNote] 按鈕的顯示問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1440">We fixed an issue with the Send to OneNote button display</span></span>

### <a name="access"></a><span data-ttu-id="99c53-1441">Access</span><span class="sxs-lookup"><span data-stu-id="99c53-1441">Access</span></span>
- <span data-ttu-id="99c53-1442">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-1442">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="99c53-1443">Project</span><span class="sxs-lookup"><span data-stu-id="99c53-1443">Project</span></span>
- <span data-ttu-id="99c53-1444">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-1444">Various performance and stability fixes</span></span>


</BR></BR>
## <a name="february-11-2019"></a><span data-ttu-id="99c53-1445">2019 年 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="99c53-1445">February 11, 2019</span></span>
<span data-ttu-id="99c53-1446">版本 1903 (組建 11330.20014)</span><span class="sxs-lookup"><span data-stu-id="99c53-1446">Version 1903 (build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="99c53-1447">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="99c53-1447">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="99c53-1448">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-1448">Word</span></span> 
- <span data-ttu-id="99c53-1449">我們已修正某些自訂樣式無法套用至線上 Word 的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1449">We fixed an issue where some customized styles could not be applied to word online</span></span>
- <span data-ttu-id="99c53-1450">我們已修正 Word 中豐富物件的內容預覽問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1450">We fixed Context Preview issues with rich objects in Word</span></span>
- <span data-ttu-id="99c53-1451">我們已修正貼上清單會導致 Word 當機的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1451">We fixed an issue where pasting lists  would result in Word crashing</span></span>

### <a name="excel"></a><span data-ttu-id="99c53-1452">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-1452">Excel</span></span>
- <span data-ttu-id="99c53-1453">我們已修正無貨幣符號時，數字格式後的附加空白不再顯示的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1453">We fixed an issue where appended spaces after number formats are no longer showing when there is no currency symbol</span></span>
- <span data-ttu-id="99c53-1454">我們已修正自動偵測股票的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1454">We fixed an issue with auto detect for stocks</span></span>

### <a name="powerpoint"></a><span data-ttu-id="99c53-1455">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-1455">PowerPoint</span></span>
- <span data-ttu-id="99c53-1456">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-1456">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="99c53-1457">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-1457">Outlook</span></span>
- <span data-ttu-id="99c53-1458">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-1458">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="99c53-1459">Access</span><span class="sxs-lookup"><span data-stu-id="99c53-1459">Access</span></span>
- <span data-ttu-id="99c53-1460">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-1460">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="99c53-1461">Project</span><span class="sxs-lookup"><span data-stu-id="99c53-1461">Project</span></span>
- <span data-ttu-id="99c53-1462">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-1462">Various performance and stability fixes</span></span>

</BR></BR>


## <a name="february-1-2019"></a><span data-ttu-id="99c53-1463">2019 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="99c53-1463">February 1, 2019</span></span> 
<span data-ttu-id="99c53-1464">版本 1902 (組建 11326.20000)</span><span class="sxs-lookup"><span data-stu-id="99c53-1464">Version 1902 (build 11326.20000)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="99c53-1465">值得注意的修正</span><span class="sxs-lookup"><span data-stu-id="99c53-1465">Notable Fixes</span></span>

### <a name="word"></a><span data-ttu-id="99c53-1466">Word</span><span class="sxs-lookup"><span data-stu-id="99c53-1466">Word</span></span> 
- <span data-ttu-id="99c53-1467">我們已修正內嵌 Excel 表格中調整儲存格大小的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1467">We fixed an issue with resizing cells in an embedded Excel table</span></span>
- <span data-ttu-id="99c53-1468">我們已修正繪圖畫布中複製/貼上圖形的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1468">We fixed an issue with copy/paste of shapes in a Drawing Canvas</span></span>

### <a name="excel"></a><span data-ttu-id="99c53-1469">Excel</span><span class="sxs-lookup"><span data-stu-id="99c53-1469">Excel</span></span>
- <span data-ttu-id="99c53-1470">我們已修正從 Excel Web App 開啟檔案的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1470">We fixed an issue with opening files from the Excel Web app</span></span>
- <span data-ttu-id="99c53-1471">我們已修正因為檔名大小造成 CSV 檔案儲存為 XLSX 失敗的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1471">We fixed an issue where saving a CSV file as .XLSX was failing due to file name size</span></span>
- <span data-ttu-id="99c53-1472">我們已修正快顯功能表顯示快顯功能表選項的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1472">We fixed the context menu to display the context menu options</span></span>

### <a name="powerpoint"></a><span data-ttu-id="99c53-1473">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="99c53-1473">PowerPoint</span></span>
- <span data-ttu-id="99c53-1474">我們已修正使用者無法使用鍵盤快速鍵 ctrl+alt+7/ctrl+alt+8 輸入方括號的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1474">We fixed an issued where users were unable to use the keyboard shortcut ctrl+alt+7/ctrl+alt+8 to enter square brackets</span></span>
- <span data-ttu-id="99c53-1475">我們已修正將本機影片插入至 PPT 會減少 C 磁碟機磁碟空間的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1475">We fixed an issue where inserting a local video into the PPT would reduce the ‘C’ drive disk space</span></span>
- <span data-ttu-id="99c53-1476">我們已修正 [發佈至 Microsoft Stream] 按鈕無法向某些使用者顯示的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1476">We fixed the Publish to Microsoft Stream button which was not displaying to some users</span></span>

### <a name="outlook"></a><span data-ttu-id="99c53-1477">Outlook</span><span class="sxs-lookup"><span data-stu-id="99c53-1477">Outlook</span></span>
- <span data-ttu-id="99c53-1478">我們已修正行事曆中工作檢視無法正確顯示工作主旨的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1478">We fixed an issue where the task view in calendar was  not correctly showing the task subject</span></span>

### <a name="access"></a><span data-ttu-id="99c53-1479">Access</span><span class="sxs-lookup"><span data-stu-id="99c53-1479">Access</span></span>
- <span data-ttu-id="99c53-1480">我們已修正圖表的縮放比例的問題</span><span class="sxs-lookup"><span data-stu-id="99c53-1480">We fixed a scaling issue with charts</span></span>

### <a name="project"></a><span data-ttu-id="99c53-1481">Project</span><span class="sxs-lookup"><span data-stu-id="99c53-1481">Project</span></span>
- <span data-ttu-id="99c53-1482">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="99c53-1482">Various performance and stability fixes</span></span>
