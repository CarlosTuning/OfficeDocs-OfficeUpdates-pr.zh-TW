---
title: Office 測試人員的版本資訊
ms.author: andrewmo
author: v-almuzz
manager: andrewmo
ms.date: 6/21/2019
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為「測試人員 - 快」對象提供關鍵新功能、修正或已知問題的最新清單
ms.openlocfilehash: d59dfd6abece5cefb49d2da86bf28ac24d1cebc7
ms.sourcegitcommit: 61132166c48f967340a1579185728b5c3acd7bd8
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 06/21/2019
ms.locfileid: "35130642"
---
# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="e2734-103">Office 測試人員的版本資訊</span><span class="sxs-lookup"><span data-stu-id="e2734-103">Release Notes for Office Insiders</span></span>

<span data-ttu-id="e2734-104">本文包含 Windows 電腦版 Word、Excel、PowerPoint、Outlook、Access 和 Project 測試人員組建的版本資訊。</span><span class="sxs-lookup"><span data-stu-id="e2734-104">This article contains release notes for Insider builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="e2734-105">我們每週都強調有趣的新功能、重要修正，以及我們想讓您知道的重大問題。</span><span class="sxs-lookup"><span data-stu-id="e2734-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="e2734-106">請注意，我們在一段時間內會經常推出新功能 (某些時候還有修正) 給測試人員。</span><span class="sxs-lookup"><span data-stu-id="e2734-106">Note that we often roll out features (and sometimes even fixes) to Insiders over a period of time.</span></span> <span data-ttu-id="e2734-107">這樣可讓我們確保功能都運作順利，然後才推出給更廣泛的對象。</span><span class="sxs-lookup"><span data-stu-id="e2734-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="e2734-108">所以，如果你沒有看到下面描述的項目，不要擔心你最終會得到它。</span><span class="sxs-lookup"><span data-stu-id="e2734-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!NOTE]
> - <span data-ttu-id="e2734-109">版本資訊會每週發佈，可能是多個組建的編譯</span><span class="sxs-lookup"><span data-stu-id="e2734-109">Release notes are posted weekly and may be a compilation of multiple builds</span></span>
> - <span data-ttu-id="e2734-110">版本資訊發佈日期可能與實際組建發行日期不相符</span><span class="sxs-lookup"><span data-stu-id="e2734-110">The release notes publication date may not match the actual build release date</span></span>

 > [!NOTE]
> - <span data-ttu-id="e2734-111">現有 Office 365 專業增強版安裝上的 Microsoft Teams - 從 6 月底開始，Microsoft Teams 將在更新這些安裝時，新增至 Office 365 專業增強版的 (和 Office 365 商務版) 的現有安裝中。</span><span class="sxs-lookup"><span data-stu-id="e2734-111">Microsoft Teams on existing installations of Office 365 ProPlus - Beginning in late June, Microsoft Teams will be included in existing installations of Office 365 ProPlus (and Office 365 Business) upon updates of these installations.</span></span> <span data-ttu-id="e2734-112">新增 Teams 的日期取決於您使用的更新通道。</span><span class="sxs-lookup"><span data-stu-id="e2734-112">The date when Teams will be added depends on which update channel you're using.</span></span> <span data-ttu-id="e2734-113">如需其他資訊，請參閱[隨著 Office 365 專業增強版部署 Microsoft Teams](https://docs.microsoft.com/zh-TW/deployoffice/teams-install)。</span><span class="sxs-lookup"><span data-stu-id="e2734-113">Please refer to [Deploy Microsoft Teams with Office 365 ProPlus](https://docs.microsoft.com/en-us/deployoffice/teams-install) for additional information.</span></span>

## <a name="june-21-2019"></a><span data-ttu-id="e2734-114">2019 年 6 月 21 日</span><span class="sxs-lookup"><span data-stu-id="e2734-114">June 21, 2019</span></span>
<span data-ttu-id="e2734-115">版本 1907 (組建 11815.20002)</span><span class="sxs-lookup"><span data-stu-id="e2734-115">Version 1907 (build 11815.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="e2734-116">新功能：</span><span class="sxs-lookup"><span data-stu-id="e2734-116">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="e2734-117">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2734-117">Outlook</span></span>

#### <a name="dark-mode-for-black-theme-in-outlook-desktop"></a><span data-ttu-id="e2734-118">Outlook 電腦版中用於黑色佈景主題的深色模式</span><span class="sxs-lookup"><span data-stu-id="e2734-118">Dark Mode for Black Theme in Outlook Desktop</span></span>

<span data-ttu-id="e2734-119">使用深色模式時，黑色佈景主題中的使用者現在也會在讀取電子郵件時看到讀取窗格具有深色背景，並在撰寫電子郵件時擁有深色背景的撰寫體驗。</span><span class="sxs-lookup"><span data-stu-id="e2734-119">With dark mode, users in black theme will now also see the reading pane with a dark background when reading emails, and the compose experience with a dark background when writing emails.</span></span> <span data-ttu-id="e2734-120">如果使用者想要預覽郵件在淺色背景下的外觀，在讀取窗格或功能區中有太陽/月亮切換。</span><span class="sxs-lookup"><span data-stu-id="e2734-120">There is a sun/moon toggle on the reading pane and in the ribbon in case users want to preview what the message looks like with a light background instead.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="e2734-121">開始使用：</span><span class="sxs-lookup"><span data-stu-id="e2734-121">Getting Started:</span></span>

1. <span data-ttu-id="e2734-122">開啟黑色佈景主題，深色模式預設就會處於開啟狀態。</span><span class="sxs-lookup"><span data-stu-id="e2734-122">Turn on black theme and dark mode will be on by default.</span></span>
2. <span data-ttu-id="e2734-123">使用月亮/太陽切換 (在讀取窗格和功能區中) 可為不在深色模式的使用者預覽郵件的外觀</span><span class="sxs-lookup"><span data-stu-id="e2734-123">Use the moon/sun toggle (in the reading pane and in the ribbon) to preview what the message looks like for users not in dark mode</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="e2734-124">可嘗試使用的案例</span><span class="sxs-lookup"><span data-stu-id="e2734-124">Scenarios to Try:</span></span>

1. <span data-ttu-id="e2734-125">在深色模式中讀取電子郵件。</span><span class="sxs-lookup"><span data-stu-id="e2734-125">Read emails in dark mode.</span></span> <span data-ttu-id="e2734-126">如果您無法讀取某些項目，請使用讀取窗格中的太陽切換來切換為淺色背景。</span><span class="sxs-lookup"><span data-stu-id="e2734-126">If you are unable to read something, use the sun toggle in the Reading Pane to switch to a light background.</span></span> 
2. <span data-ttu-id="e2734-127">在深色模式中撰寫電子郵件。</span><span class="sxs-lookup"><span data-stu-id="e2734-127">Compose emails in dark mode.</span></span> <span data-ttu-id="e2734-128">使用功能區中的太陽切換，預覽您的郵件使用淺色背景時的外觀。</span><span class="sxs-lookup"><span data-stu-id="e2734-128">Preview what your message will look like with a light background by using the sun toggle in the ribbon.</span></span> 

<span data-ttu-id="e2734-129">如果您遇到未正確顯示的任何電子郵件，請將其 (當作附件) 傳送到 OutlookDarkModeFail，</span><span class="sxs-lookup"><span data-stu-id="e2734-129">If you encounter any emails that don't render properly, please send them (as an attachment) to the OutlookDarkModeFail,</span></span>

#### <a name="get-location-suggestions"></a><span data-ttu-id="e2734-130">取得位置建議</span><span class="sxs-lookup"><span data-stu-id="e2734-130">Get location suggestions</span></span>

<span data-ttu-id="e2734-131">開始輸入，Outlook 就會尋找符合的位置。</span><span class="sxs-lookup"><span data-stu-id="e2734-131">Start typing and Outlook will look for matching locations.</span></span>

<span data-ttu-id="e2734-132">建立約會和會議時，這適用於 [位置] 欄位。</span><span class="sxs-lookup"><span data-stu-id="e2734-132">This applies to the Location field when creating Appointments and Meetings.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="e2734-133">開始使用：</span><span class="sxs-lookup"><span data-stu-id="e2734-133">Getting Started:</span></span>

- <span data-ttu-id="e2734-134">在 Outlook 中的 O365 或 Outlook.com 行事曆上，建立約會或會議。</span><span class="sxs-lookup"><span data-stu-id="e2734-134">Create an Appointment or Meeting on an O365 or Outlook.com calendar in Outlook.</span></span> 
- <span data-ttu-id="e2734-135">按一下 [位置] 欄位，然後開始輸入…</span><span class="sxs-lookup"><span data-stu-id="e2734-135">Click into the Location field and start typing…</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="e2734-136">可嘗試使用的案例</span><span class="sxs-lookup"><span data-stu-id="e2734-136">Scenarios to Try:</span></span>

<span data-ttu-id="e2734-137">當您將會議室加入至會議時，按一下 [位置] 欄位，而不是使用會議室尋找工具增益集或通訊錄。</span><span class="sxs-lookup"><span data-stu-id="e2734-137">When adding a conference room to a meeting, click into Location field, rather than using Room Finder add-in or Address Book.</span></span>
<span data-ttu-id="e2734-138">若是在公共場所 (如餐廳、咖啡廳，甚至是牙醫診所) 的實體位置進行會議，請嘗試使用新的選擇器找到確切的位置。</span><span class="sxs-lookup"><span data-stu-id="e2734-138">For appointments at a physical place with a public location - like a restaurant, coffee shop, or even your dentist's office - try finding the exact location using the new picker.</span></span> <span data-ttu-id="e2734-139">如此一來，您將可以在該離開時，收到 Outlook Mobile 的通知。</span><span class="sxs-lookup"><span data-stu-id="e2734-139">This way, you'll be able to get notified on Outlook Mobile when it's time to leave.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="e2734-140">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="e2734-140">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="e2734-141">全部</span><span class="sxs-lookup"><span data-stu-id="e2734-141">All</span></span>
- <span data-ttu-id="e2734-142">我們已修正在離線時會導致搜尋方塊啟用的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-142">We fixed an issue which would keep the Search Box enabled while offline</span></span>

### <a name="word"></a><span data-ttu-id="e2734-143">Word</span><span class="sxs-lookup"><span data-stu-id="e2734-143">Word</span></span> 
- <span data-ttu-id="e2734-144">我們已修正有時候可能難以查看鍵盤焦點的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-144">We fixed an issue where keyboard focus could sometimes be difficult to see</span></span>
- <span data-ttu-id="e2734-145">我們已修正貼到新文件的文字，有時候文字對齊可能會不正確的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-145">We fixed an issue where text pasted into a new document could sometimes have the wrong text alignment</span></span>
- <span data-ttu-id="e2734-146">我們已修正將使用者的電腦暫停之後，可能防止部分使用者儲存變更的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-146">We fixed an issue which could prevent some users from saving changes after suspending their computer</span></span>
- <span data-ttu-id="e2734-147">我們已修正在某些情況下會列印整份文件，而非所選範圍的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-147">We fixed an issue where in certain cases an entire document would be printed instead of the selected range</span></span>
- <span data-ttu-id="e2734-148">我們已修正可能會讓註解在較小型的顯示器上難以閱讀的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-148">We fixed an issue which could make comments difficult to read on smaller displays</span></span>
- <span data-ttu-id="e2734-149">我們已修正擷取到裝置時可能會造成當機的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-149">We fixed an issue which could cause a crash when capturing to a device</span></span>

### <a name="excel"></a><span data-ttu-id="e2734-150">Excel</span><span class="sxs-lookup"><span data-stu-id="e2734-150">Excel</span></span>
- <span data-ttu-id="e2734-151">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-151">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="e2734-152">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e2734-152">PowerPoint</span></span>
- <span data-ttu-id="e2734-153">我們已修正有時候可能難以查看鍵盤焦點的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-153">We fixed an issue where keyboard focus could sometimes be difficult to see</span></span>

### <a name="outlook"></a><span data-ttu-id="e2734-154">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2734-154">Outlook</span></span>
- <span data-ttu-id="e2734-155">我們已修正不正確地將未啟用的增益集顯示為已啟用的問題。</span><span class="sxs-lookup"><span data-stu-id="e2734-155">We fixed an issue which could incorrectly display an add-in as being enabled when it was not.</span></span>
- <span data-ttu-id="e2734-156">我們已修正會在有大量原則時，使得客戶無法檢視所有保留原則的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-156">We fixed an issue which would prevent a customer from viewing all retention policies if there were a large number of them</span></span>

### <a name="access"></a><span data-ttu-id="e2734-157">Access</span><span class="sxs-lookup"><span data-stu-id="e2734-157">Access</span></span>
- <span data-ttu-id="e2734-158">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-158">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="e2734-159">Project</span><span class="sxs-lookup"><span data-stu-id="e2734-159">Project</span></span>
- <span data-ttu-id="e2734-160">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-160">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-14-2019"></a><span data-ttu-id="e2734-161">2019 年 6 月 14 日</span><span class="sxs-lookup"><span data-stu-id="e2734-161">June 14, 2019</span></span>
<span data-ttu-id="e2734-162">版本 1907 (組建 11807.20000)</span><span class="sxs-lookup"><span data-stu-id="e2734-162">Version 1907 (build 11807.20000)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="e2734-163">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="e2734-163">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="e2734-164">Word</span><span class="sxs-lookup"><span data-stu-id="e2734-164">Word</span></span> 
- <span data-ttu-id="e2734-165">我們已修正了儲存到 OneDrive 時，使用者可能無法登入的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-165">We fixed an issue which could prevent a user from signing in when saving to OneDrive</span></span>
- <span data-ttu-id="e2734-166">我們已修正了使用者可能無法變更限制存取模式中之 SharePoint 內容的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-166">We fixed an issue where a user could be prevented from changing SharePoint properties while in restricted access mode</span></span>
- <span data-ttu-id="e2734-167">我們已修正了調整邊界時，可能會變更頁首及頁尾內容的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-167">We fixed an issue where header and footer content could change when adjusting margins</span></span>
- <span data-ttu-id="e2734-168">我們已修正了切換成網頁檢視時，格式設定可能會中斷的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-168">We fixed an issue where formatting could break when switching to web view</span></span>
- <span data-ttu-id="e2734-169">我們已修正了從 SharePoint 開啟時，使用者無法使用自訂欄位的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-169">We fixed an issue which could prevent a user from using custom fields when opened from SharePoint</span></span>

### <a name="excel"></a><span data-ttu-id="e2734-170">Excel</span><span class="sxs-lookup"><span data-stu-id="e2734-170">Excel</span></span>
- <span data-ttu-id="e2734-171">我們已修正了刪除篩選集之資料列時的效能問題</span><span class="sxs-lookup"><span data-stu-id="e2734-171">We fixed a performance issue when deleting rows of a filtered set</span></span>
- <span data-ttu-id="e2734-172">我們已修正了有時可能會造成滑鼠在受保護檢視模式中閃爍的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-172">We fixed an issue which could sometimes cause the mouse to flicker in protected view</span></span>
- <span data-ttu-id="e2734-173">我們修正了刪除系列時，可能會導致當機的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-173">We fixed an issue which could have caused a crash when deleting a series</span></span>
- <span data-ttu-id="e2734-174">我們已修正了某些使用者即使在沒有提供的情況下，仍舊有新增版本歷程記錄之選項的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-174">We fixed an issue where some users would have the option to add version history when that was not available</span></span>
- <span data-ttu-id="e2734-175">我們已修正了使用試算表比較工具時，可能導致例外狀況的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-175">We fixed an issue which could have caused an exception when using the Spreadsheet Compare tool</span></span>

### <a name="powerpoint"></a><span data-ttu-id="e2734-176">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e2734-176">PowerPoint</span></span>
- <span data-ttu-id="e2734-177">我們已修正了按一下連結到 SharePoint 時，可能會發生當機的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-177">We fixed an issue where a crash could occur when clicking a link to SharePoint</span></span>
- <span data-ttu-id="e2734-178">我們已修正了使用 Surface 手寫筆輸入時，可能將使用者切換到下一個頁面的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-178">We fixed an issue which could switch the user to the next page while typing using a Surface Pen</span></span>

### <a name="outlook"></a><span data-ttu-id="e2734-179">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2734-179">Outlook</span></span>
- <span data-ttu-id="e2734-180">我們已修正了在某些情況下 [收件者] 欄位大於正常的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-180">We fixed an issue where in some cases the To field was larger than normal</span></span>

### <a name="access"></a><span data-ttu-id="e2734-181">Access</span><span class="sxs-lookup"><span data-stu-id="e2734-181">Access</span></span>
- <span data-ttu-id="e2734-182">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-182">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="e2734-183">Project</span><span class="sxs-lookup"><span data-stu-id="e2734-183">Project</span></span>
- <span data-ttu-id="e2734-184">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-184">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-7-2019"></a><span data-ttu-id="e2734-185">2019 年 6 月 7 日</span><span class="sxs-lookup"><span data-stu-id="e2734-185">June 7, 2019</span></span>
<span data-ttu-id="e2734-186">版本 1907 (組建 11727.20064)</span><span class="sxs-lookup"><span data-stu-id="e2734-186">Version 1907 (build 11727.20064)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="e2734-187">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="e2734-187">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="e2734-188">Word</span><span class="sxs-lookup"><span data-stu-id="e2734-188">Word</span></span> 
- <span data-ttu-id="e2734-189">我們已修正當 Word 中的自動校正設定為使句中的第一個字母均為大寫時，偶爾會當機的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-189">We fixed an issue where Word could sometimes crash when autocorrect was set to capitalize the first letter of a sentence</span></span>
- <span data-ttu-id="e2734-190">我們已改善在 SharePoint 上編輯文件時的效能。</span><span class="sxs-lookup"><span data-stu-id="e2734-190">We improved performance when editing a document on SharePoint</span></span>
- <span data-ttu-id="e2734-191">我們已修正在 Adobe Illustrator 中所建立之向量影像無法正確顯示的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-191">We fixed an issue where vector-based images created in Adobe Illustrator would not display correctly</span></span>

### <a name="excel"></a><span data-ttu-id="e2734-192">Excel</span><span class="sxs-lookup"><span data-stu-id="e2734-192">Excel</span></span>
- <span data-ttu-id="e2734-193">我們已修正錄製巨集時，排序欄位有時未正確設定的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-193">We fixed an issue where sorting fields were sometimes not set correctly when recording a macro</span></span>
- <span data-ttu-id="e2734-194">我們已修正重新計算陣列公式期間導致停止回應或當機的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-194">We fixed an issue that causes hang or crash during recalculation of an array formula</span></span>

### <a name="powerpoint"></a><span data-ttu-id="e2734-195">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e2734-195">PowerPoint</span></span>
- <span data-ttu-id="e2734-196">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-196">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="e2734-197">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2734-197">Outlook</span></span>
- <span data-ttu-id="e2734-198">我們已修正內嵌附件有時未正確縮放的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-198">We fixed an issue where inline attachments would sometimes be incorrectly scaled</span></span>

### <a name="access"></a><span data-ttu-id="e2734-199">Access</span><span class="sxs-lookup"><span data-stu-id="e2734-199">Access</span></span>
- <span data-ttu-id="e2734-200">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-200">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="e2734-201">Project</span><span class="sxs-lookup"><span data-stu-id="e2734-201">Project</span></span>
- <span data-ttu-id="e2734-202">我們已修正固定工期的時程表有時會變更工作分派完成日期的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-202">We fixed an issue where timesheets on a fixed duration could sometimes change the assignment finish date</span></span>
- <span data-ttu-id="e2734-203">我們已修正從舊版本中開啟專案時顯示的完成百分比值可能有誤的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-203">We fixed an issue where Percentage Complete values could be wrong when opening a project from an earlier version</span></span>

</BR></BR>

## <a name="may-31-2019"></a><span data-ttu-id="e2734-204">2019 年 5 月 31 日</span><span class="sxs-lookup"><span data-stu-id="e2734-204">May 31, 2019</span></span>
<span data-ttu-id="e2734-205">版本 1906 (組建 11722.20008)</span><span class="sxs-lookup"><span data-stu-id="e2734-205">Version 1906 (build 11629.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="e2734-206">新功能：</span><span class="sxs-lookup"><span data-stu-id="e2734-206">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="e2734-207">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2734-207">Outlook</span></span>

#### <a name="dialog-for-contacting-support-now-is-dockable-and-appears-on-the-right"></a><span data-ttu-id="e2734-208">[連絡支援人員] 對話方塊現在可停駐，且會顯示在右側</span><span class="sxs-lookup"><span data-stu-id="e2734-208">Dialog for Contacting Support now is dockable and appears on the right</span></span>

<span data-ttu-id="e2734-209">用於 [連絡支援人員] 的對話方塊現在會顯示在右側窗格中，並且會以停駐視窗形式開始。</span><span class="sxs-lookup"><span data-stu-id="e2734-209">The dialog used for Contacting support will now appear in a pane on the right and will start off as a docked window.</span></span>

#### <a name="ink-in-your-email"></a><span data-ttu-id="e2734-210">在您的電子郵件中使用筆跡！</span><span class="sxs-lookup"><span data-stu-id="e2734-210">Ink in Your Email!</span></span>

<span data-ttu-id="e2734-211">您現在可以在您的 Outlook 電子郵件中繪製圖片並加上註釋。</span><span class="sxs-lookup"><span data-stu-id="e2734-211">You can now draw and annotate pictures in your Outlook emails.</span></span>

### <a name="word"></a><span data-ttu-id="e2734-212">Word</span><span class="sxs-lookup"><span data-stu-id="e2734-212">Word</span></span>

#### <a name="open-document-links-in-word"></a><span data-ttu-id="e2734-213">在 Word 中開啟文件連結</span><span class="sxs-lookup"><span data-stu-id="e2734-213">Open document links in Word</span></span>

<span data-ttu-id="e2734-214">當您在 Office 中按一下文件連結時，您可以更新您的喜好設定，以預設在 Word App 中開啟該連結。</span><span class="sxs-lookup"><span data-stu-id="e2734-214">When you click a document link in Office, you can update your preference to open in the Word app by default.</span></span>  <span data-ttu-id="e2734-215">若要更新您的喜好設定，請移至 [檔案] -> [選項] -> [進階] -> [連結處理]。</span><span class="sxs-lookup"><span data-stu-id="e2734-215">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="e2734-216">深入了解：https://support.office.com/zh-TW/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="e2734-216">https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="e2734-217">開始使用：</span><span class="sxs-lookup"><span data-stu-id="e2734-217">Getting Started:</span></span>

<span data-ttu-id="e2734-218">此功能將預設為關閉。</span><span class="sxs-lookup"><span data-stu-id="e2734-218">Feature will default to off.</span></span> <span data-ttu-id="e2734-219">使用者可以透過 [選項] -> [進階] -> [連結處理] 設定來開啟它，也可以在 Win32 WXP 應用程式帶他們進行選擇加入體驗時選擇加入。</span><span class="sxs-lookup"><span data-stu-id="e2734-219">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="e2734-220">當使用者按一下透過 Outlook/Word/PowerPoint/Excel 儲存在 OneDrive/商務用 OneDrive/SharePoint 上的 Word/PowerPoint/Excel 檔案時，這些連結依預設會在適當的 Office 應用程式中 (而非瀏覽器中) 開啟。</span><span class="sxs-lookup"><span data-stu-id="e2734-220">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="e2734-221">若要變更此預設值，使用者可以更新 Outlook/Word/Excel/PowerPoint 中的下列設定：</span><span class="sxs-lookup"><span data-stu-id="e2734-221">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="e2734-222">[檔案] -> [選項] -> [進階] -> [連結處理]</span><span class="sxs-lookup"><span data-stu-id="e2734-222">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="e2734-223">此設定會在 Outlook/Word/PowerPoint/Excel 之間共用，而且可以在任一應用程式中設定。</span><span class="sxs-lookup"><span data-stu-id="e2734-223">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="e2734-224">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="e2734-224">Scenarios to Try:</span></span>

<span data-ttu-id="e2734-225">若要觸發選擇加入體驗 - 從 Outlook/Word/PowerPoint/Excel 開啟儲存在 OneDrive/SharePoint 中 Word 文件的連結 - 按一下 [在來自 Office Online 的用戶端中開啟] - 在 30 天內執行此動作兩次。</span><span class="sxs-lookup"><span data-stu-id="e2734-225">To trigger the opt-in experience - Open a link tot a Word document stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="e2734-226">在您選擇加入之後，依預設會在 Win32 應用程式中啟動連結。</span><span class="sxs-lookup"><span data-stu-id="e2734-226">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="e2734-227">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e2734-227">PowerPoint</span></span>

#### <a name="open-presentation-links-in-powerpoint"></a><span data-ttu-id="e2734-228">在 PowerPoint 中開啟簡報連結</span><span class="sxs-lookup"><span data-stu-id="e2734-228">Open presentation links in PowerPoint</span></span>

<span data-ttu-id="e2734-229">當您在 Office 中按一下連結連結時，您可以更新您的喜好設定，以預設在 PowerPoint App 中開啟該連結。</span><span class="sxs-lookup"><span data-stu-id="e2734-229">When you click a presentation link in Office, you can update your preference to open in the PowerPoint app by default.</span></span> <span data-ttu-id="e2734-230">若要更新您的喜好設定，請移至 [檔案] -> [選項] -> [進階] -> [連結處理]。</span><span class="sxs-lookup"><span data-stu-id="e2734-230">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="e2734-231">深入了解：https://support.office.com/zh-TW/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="e2734-231">https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="e2734-232">開始使用：</span><span class="sxs-lookup"><span data-stu-id="e2734-232">Getting Started:</span></span>

<span data-ttu-id="e2734-233">此功能將預設為關閉。</span><span class="sxs-lookup"><span data-stu-id="e2734-233">Feature will default to off.</span></span> <span data-ttu-id="e2734-234">使用者可以透過 [選項] -> [進階] -> [連結處理] 設定來開啟它，也可以在 Win32 WXP 應用程式帶他們進行選擇加入體驗時選擇加入。</span><span class="sxs-lookup"><span data-stu-id="e2734-234">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="e2734-235">當使用者按一下透過 Outlook/Word/PowerPoint/Excel 儲存在 OneDrive/商務用 OneDrive/SharePoint 上的 Word/PowerPoint/Excel 檔案時，這些連結依預設會在適當的 Office 應用程式中 (而非瀏覽器中) 開啟。</span><span class="sxs-lookup"><span data-stu-id="e2734-235">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="e2734-236">若要變更此預設值，使用者可以更新 Outlook/Word/Excel/PowerPoint 中的下列設定：</span><span class="sxs-lookup"><span data-stu-id="e2734-236">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="e2734-237">[檔案] -> [選項] -> [進階] -> [連結處理]</span><span class="sxs-lookup"><span data-stu-id="e2734-237">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="e2734-238">此設定會在 Outlook/Word/PowerPoint/Excel 之間共用，而且可以在任一應用程式中設定。</span><span class="sxs-lookup"><span data-stu-id="e2734-238">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="e2734-239">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="e2734-239">Scenarios to Try:</span></span>

<span data-ttu-id="e2734-240">若要觸發選擇加入體驗 - 從 Outlook/Word/PowerPoint/Excel 開啟儲存在 OneDrive/SharePoint 中 PowerPoint 簡報的連結 - 按一下 [在來自 Office Online 的用戶端中開啟] - 在 30 天內執行此動作兩次。</span><span class="sxs-lookup"><span data-stu-id="e2734-240">To trigger the opt-in experience - Open a link to a PowerPoint presentation stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="e2734-241">在您選擇加入之後，依預設會在 Win32 應用程式中啟動連結。</span><span class="sxs-lookup"><span data-stu-id="e2734-241">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="excel"></a><span data-ttu-id="e2734-242">Excel</span><span class="sxs-lookup"><span data-stu-id="e2734-242">Excel</span></span>

#### <a name="open-workbook-links-in-excel"></a><span data-ttu-id="e2734-243">在 Excel 中開啟活頁簿連結</span><span class="sxs-lookup"><span data-stu-id="e2734-243">Open workbook links in Excel</span></span>

<span data-ttu-id="e2734-244">當您在 Office 中按一下活頁簿連結時，您可以更新您的喜好設定，以預設在 Excel App 中開啟該連結。</span><span class="sxs-lookup"><span data-stu-id="e2734-244">When you click a workbook link in Office, you can update your preference to open in the Excel app by default.</span></span> <span data-ttu-id="e2734-245">若要更新您的喜好設定，請移至 [檔案] -> [選項] -> [進階] -> [連結處理]。</span><span class="sxs-lookup"><span data-stu-id="e2734-245">To update your preference, go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="e2734-246">深入了解：https://support.office.com/zh-TW/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="e2734-246">https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="e2734-247">開始使用：</span><span class="sxs-lookup"><span data-stu-id="e2734-247">Getting Started:</span></span>

<span data-ttu-id="e2734-248">此功能將預設為關閉。</span><span class="sxs-lookup"><span data-stu-id="e2734-248">Feature will default to off.</span></span> <span data-ttu-id="e2734-249">使用者可以透過 [選項] -> [進階] -> [連結處理] 設定來開啟它，也可以在 Win32 WXP 應用程式帶他們進行選擇加入體驗時選擇加入。</span><span class="sxs-lookup"><span data-stu-id="e2734-249">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="e2734-250">當使用者按一下透過 Outlook/Word/PowerPoint/Excel 儲存在 OneDrive/商務用 OneDrive/SharePoint 上的 Word/PowerPoint/Excel 檔案時，這些連結依預設會在適當的 Office 應用程式中 (而非瀏覽器中) 開啟。</span><span class="sxs-lookup"><span data-stu-id="e2734-250">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="e2734-251">若要變更此預設值，使用者可以更新 Outlook/Word/Excel/PowerPoint 中的下列設定：</span><span class="sxs-lookup"><span data-stu-id="e2734-251">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="e2734-252">[檔案] -> [選項] -> [進階] -> [連結處理]</span><span class="sxs-lookup"><span data-stu-id="e2734-252">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="e2734-253">此設定會在 Outlook/Word/PowerPoint/Excel 之間共用，而且可以在任一應用程式中設定。</span><span class="sxs-lookup"><span data-stu-id="e2734-253">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="e2734-254">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="e2734-254">Scenarios to Try:</span></span>

<span data-ttu-id="e2734-255">若要觸發選擇加入體驗 - 從 Outlook/Word/PowerPoint/Excel 開啟儲存在 OneDrive/SharePoint 中 Excel 活頁簿的連結 - 按一下 [在來自 Office Online 的用戶端中開啟] - 在 30 天內執行此動作兩次。</span><span class="sxs-lookup"><span data-stu-id="e2734-255">To trigger the opt-in experience - Open a link to an Excel workbook stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="e2734-256">在您選擇加入之後，依預設會在 Win32 應用程式中啟動連結。</span><span class="sxs-lookup"><span data-stu-id="e2734-256">After you opt-in, links will launch in the Win32 apps by default.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="e2734-257">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="e2734-257">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="e2734-258">全部</span><span class="sxs-lookup"><span data-stu-id="e2734-258">All</span></span>
- <span data-ttu-id="e2734-259">我們已修正即使在已停用自動儲存的情況下，檔案有時會自動儲存的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-259">We fixed an issue where files could sometimes be auto-saved even when auto-save was disabled</span></span>

### <a name="word"></a><span data-ttu-id="e2734-260">Word</span><span class="sxs-lookup"><span data-stu-id="e2734-260">Word</span></span> 
- <span data-ttu-id="e2734-261">我們已修正可能會導致部分使用者無法儲存至 SharePoint 的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-261">We fixed an issue which prevented some users from saving files to cloud locations</span></span>

### <a name="excel"></a><span data-ttu-id="e2734-262">Excel</span><span class="sxs-lookup"><span data-stu-id="e2734-262">Excel</span></span>
- <span data-ttu-id="e2734-263">我們已修正可能對非作用中篩選器顯示不正確圖示的問題。</span><span class="sxs-lookup"><span data-stu-id="e2734-263">We fixed an issue where an incorrect icon could be displayed for inactive filters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="e2734-264">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e2734-264">PowerPoint</span></span>
- <span data-ttu-id="e2734-265">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-265">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="e2734-266">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2734-266">Outlook</span></span>
- <span data-ttu-id="e2734-267">我們已修正有些使用者在群組排程檢視中會不正確地顯示為離線的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-267">We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span>
- <span data-ttu-id="e2734-268">我們已修正可能會防止 SafeLink 剖析包含尾端空格 URL 的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-268">We fixed an issue which prevented SafeLink from parsing a URL with a trailing space</span></span>
- <span data-ttu-id="e2734-269">我們已修正會議室在非工作時間外顯示為可用的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-269">We fixed an issue where rooms were displayed as available outside of non-working hours</span></span>

### <a name="access"></a><span data-ttu-id="e2734-270">Access</span><span class="sxs-lookup"><span data-stu-id="e2734-270">Access</span></span>
- <span data-ttu-id="e2734-271">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-271">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="e2734-272">Project</span><span class="sxs-lookup"><span data-stu-id="e2734-272">Project</span></span>
- <span data-ttu-id="e2734-273">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-273">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-24-2019"></a><span data-ttu-id="e2734-274">2019 年 5 月 24 日</span><span class="sxs-lookup"><span data-stu-id="e2734-274">May 24, 2019</span></span>
<span data-ttu-id="e2734-275">版本 1906 (組建 11715.20002)</span><span class="sxs-lookup"><span data-stu-id="e2734-275">Version 1906 (build 11715.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="e2734-276">新功能：</span><span class="sxs-lookup"><span data-stu-id="e2734-276">What's New:</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="e2734-277">使用者體驗更新</span><span class="sxs-lookup"><span data-stu-id="e2734-277">User Experience Updates</span></span>

<span data-ttu-id="e2734-278">[即將推出] 中的更新現已發佈，其中包括簡化功能區、資料夾窗格的新版視覺效果、郵件清單，以及讀取窗格。</span><span class="sxs-lookup"><span data-stu-id="e2734-278">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="e2734-279">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="e2734-279">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="e2734-280">全部</span><span class="sxs-lookup"><span data-stu-id="e2734-280">All</span></span>

- <span data-ttu-id="e2734-281">我們已修正 [聊天] 窗格無法顯示的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-281">We fixed an issue where the Chat Pane would not display</span></span>

### <a name="word"></a><span data-ttu-id="e2734-282">Word</span><span class="sxs-lookup"><span data-stu-id="e2734-282">Word</span></span> 
- <span data-ttu-id="e2734-283">我們已修正在某些情況下 Word 無法為文法錯誤正確醒目提示文字的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-283">We fixed an issue where in some cases Word could incorrectly highlight text for grammatical errors</span></span>

### <a name="excel"></a><span data-ttu-id="e2734-284">Excel</span><span class="sxs-lookup"><span data-stu-id="e2734-284">Excel</span></span>
- <span data-ttu-id="e2734-285">我們已修正 [圖表項目] 使用不正確圖示的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-285">We fixed an issue where an incorrect icon was used in for Chart Elements</span></span>
- <span data-ttu-id="e2734-286">我們已修正開啟同樣的活頁簿時，可能會啟動 VBA 指令碼中不正確活頁簿的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-286">We fixed an issue where the incorrect workbook could be activated in a VBA script when the same book was already open</span></span>

### <a name="powerpoint"></a><span data-ttu-id="e2734-287">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e2734-287">PowerPoint</span></span>
- <span data-ttu-id="e2734-288">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-288">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="e2734-289">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2734-289">Outlook</span></span>
- <span data-ttu-id="e2734-290">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-290">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="e2734-291">Access</span><span class="sxs-lookup"><span data-stu-id="e2734-291">Access</span></span>
- <span data-ttu-id="e2734-292">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-292">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="e2734-293">Project</span><span class="sxs-lookup"><span data-stu-id="e2734-293">Project</span></span>
- <span data-ttu-id="e2734-294">我們已修正 Project 在切換工作列後可能會當機的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-294">We fixed an issue where Project could crash after switching to the taskbar</span></span>

</BR></BR>

## <a name="may-17-2019"></a><span data-ttu-id="e2734-295">2019 年 5 月 17 日</span><span class="sxs-lookup"><span data-stu-id="e2734-295">May 17, 2019</span></span>
<span data-ttu-id="e2734-296">版本 1906 (組建 11708.20006)</span><span class="sxs-lookup"><span data-stu-id="e2734-296">Version 1906 (build 11708.20006)</span></span>

## <a name="whats-new"></a><span data-ttu-id="e2734-297">新功能：</span><span class="sxs-lookup"><span data-stu-id="e2734-297">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="e2734-298">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2734-298">Outlook</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="e2734-299">使用者體驗更新</span><span class="sxs-lookup"><span data-stu-id="e2734-299">User Experience Updates</span></span>

<span data-ttu-id="e2734-300">[即將推出] 中的更新現已發佈，其中包括簡化功能區、資料夾窗格的新版視覺效果、郵件清單，以及讀取窗格。</span><span class="sxs-lookup"><span data-stu-id="e2734-300">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="e2734-301">開始使用：</span><span class="sxs-lookup"><span data-stu-id="e2734-301">Getting Started:</span></span>

<span data-ttu-id="e2734-302">這些變更會成為新的預設 UI。自 12 月中旬起，即可透過 [即將推出] 開關切換使用這套 UI，協助您徹底發揮生產力</span><span class="sxs-lookup"><span data-stu-id="e2734-302">These change will be part of the new default UI; it has been available behind the Coming Soon switch since mid Dec for 100% prod</span></span>

#### <a name="customizable-simplified-ribbon"></a><span data-ttu-id="e2734-303">自訂簡化功能區</span><span class="sxs-lookup"><span data-stu-id="e2734-303">Customizable Simplified Ribbon</span></span>

<span data-ttu-id="e2734-304">提供輕鬆自訂功能，方便在傳統與 [簡化] 檢視之間切換，以及釘選/取消釘選命令。</span><span class="sxs-lookup"><span data-stu-id="e2734-304">Easily customizable to switch between classic and Simplified views and pin/unpin commands.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="e2734-305">開始使用：</span><span class="sxs-lookup"><span data-stu-id="e2734-305">Getting Started:</span></span>

<span data-ttu-id="e2734-306">使用者可以使用簡化功能區，方法是開啟 [即將推出] (在一開始)，然後按一下功能區中的＞形箭號，即可在傳統的多行功能區與新式的簡化單行功能區之間切換。</span><span class="sxs-lookup"><span data-stu-id="e2734-306">Users can get to the simplified ribbon by turning on Coming Soon (initially) and clicking the chevron in the ribbon to toggle between the classic multi-line ribbon and the new simplified single-line ribbon.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="e2734-307">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="e2734-307">Scenarios to Try:</span></span>

<span data-ttu-id="e2734-308">從傳統功能區切換到簡化功能區</span><span class="sxs-lookup"><span data-stu-id="e2734-308">Switch from Classic ribbon to Simplified ribbon</span></span>

#### <a name="pick-your-favorite-action"></a><span data-ttu-id="e2734-309">挑選您的最愛動作</span><span class="sxs-lookup"><span data-stu-id="e2734-309">Pick your favorite action</span></span>

<span data-ttu-id="e2734-310">不使用 [標幟] 和 [刪除] 嗎？</span><span class="sxs-lookup"><span data-stu-id="e2734-310">Don't use Flag and Delete?</span></span> <span data-ttu-id="e2734-311">那麼 [封存] 或 [標示為已讀取] 呢？</span><span class="sxs-lookup"><span data-stu-id="e2734-311">How about Archive or Mark as Read?</span></span> <span data-ttu-id="e2734-312">自訂快速動作功能表，加上您最常使用的命令。</span><span class="sxs-lookup"><span data-stu-id="e2734-312">Customize the quick action menu with the commands you use most.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="e2734-313">開始使用：</span><span class="sxs-lookup"><span data-stu-id="e2734-313">Getting Started:</span></span>

<span data-ttu-id="e2734-314">若要選取 [快速動作]，請以滑鼠右鍵按一下郵件清單中的 [電子郵件]，以顯示內容功能表。</span><span class="sxs-lookup"><span data-stu-id="e2734-314">To select your Quick Actions, right click on an email in the message list to bring up the Context Menu.</span></span> <span data-ttu-id="e2734-315">然後按一下 [設定快速動作...]</span><span class="sxs-lookup"><span data-stu-id="e2734-315">Then click "Set Quick Actions..."</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="e2734-316">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="e2734-316">Scenarios to Try:</span></span>

<span data-ttu-id="e2734-317">將 [標幟] 和 [刪除] 的預設值變更為 [封存]、[移動]、[標示為已讀取] 或 [無]，以便清除郵件清單</span><span class="sxs-lookup"><span data-stu-id="e2734-317">Change the defaults from flag and delete to either archive, move,  mark as read, or none for a cleaner message list</span></span>

#### <a name="relaxed-or-tighter-layout-you-choose"></a><span data-ttu-id="e2734-318">寬鬆或緊密的版面配置？</span><span class="sxs-lookup"><span data-stu-id="e2734-318">Relaxed or tighter layout?</span></span> <span data-ttu-id="e2734-319">由您選擇</span><span class="sxs-lookup"><span data-stu-id="e2734-319">You choose</span></span>

<span data-ttu-id="e2734-320">若您想讓郵件之間能有更多空間，可以採用「緊密間距」；或者，您也可以採用緊密的版面配置，以便查看更多郵件。</span><span class="sxs-lookup"><span data-stu-id="e2734-320">Use Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="e2734-321">開始使用：</span><span class="sxs-lookup"><span data-stu-id="e2734-321">Getting Started:</span></span>

<span data-ttu-id="e2734-322">前往 [檢視] 索引標籤，勾選 [更緊密的間距] 核取方塊。若是使用傳統功能區，該核取方塊位於「郵件」群組內；若是使用簡化功能區，則是位於「目前檢視」設定當中</span><span class="sxs-lookup"><span data-stu-id="e2734-322">View tab, use tighter spacing checkbox - in Messages group for classic ribbon, Current View settings for simplified ribbon</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="e2734-323">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="e2734-323">Scenarios to Try:</span></span>

<span data-ttu-id="e2734-324">使用 Outlook 在未啟用設定的情況下分類及撰寫電子郵件。</span><span class="sxs-lookup"><span data-stu-id="e2734-324">Use Outlook to triage and write email with and without the setting enabled.</span></span> <span data-ttu-id="e2734-325">如果開啟 [使用更緊密的間距]，即可讓每個頁面能夠容納得下更多郵件，並讓撰寫表單的控制項更為簡潔。</span><span class="sxs-lookup"><span data-stu-id="e2734-325">With Use tighter spacing on, more messages fit per page, and controls on the compose forms are more streamlined.</span></span>

#### <a name="dedupe-mru-entries-when-using-the-onedrive-sync-client"></a><span data-ttu-id="e2734-326">使用 OneDrive 同步處理用戶端時的刪除重複資料 MRU 項目</span><span class="sxs-lookup"><span data-stu-id="e2734-326">Dedupe MRU entries when using the Onedrive sync client</span></span>

<span data-ttu-id="e2734-327">透過刪除重複資料 MRU 項目，改善 OneDrive 同步處理用戶端與雲端附件的整合度並加快附加速度，讓其速度足以媲美同步處理資料的複製行為</span><span class="sxs-lookup"><span data-stu-id="e2734-327">Enable better integration with onedrive sync client with cloud attachments by deduping the mru entries and to enable faster attach as copy behavior for synchronized data</span></span>

##### <a name="getting-started"></a><span data-ttu-id="e2734-328">開始使用：</span><span class="sxs-lookup"><span data-stu-id="e2734-328">Getting Started:</span></span>

<span data-ttu-id="e2734-329">若您使用的是 OneDrive 同步處理用戶端，將再也看不到「附加檔案 MRU」的檔案重複項目。</span><span class="sxs-lookup"><span data-stu-id="e2734-329">If you use the OneDrive sync client, you will no longer see file duplicates in the Attach File MRU.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="e2734-330">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="e2734-330">Scenarios to Try:</span></span>

<span data-ttu-id="e2734-331">啟用 OneDrive 同步處理用戶端，並使用 Outlook 電腦版的 [附加檔案] 功能表</span><span class="sxs-lookup"><span data-stu-id="e2734-331">Enable the OneDrive sync client and use the Attach File menu in Outlook Desktop</span></span>

#### <a name="improved-shared-folder-synchronization-for-mailboxes-with-many-folders"></a><span data-ttu-id="e2734-332">已改善擁有多個資料夾的信箱共用資料夾同步處理</span><span class="sxs-lookup"><span data-stu-id="e2734-332">Improved shared folder synchronization for mailboxes with many folders</span></span>

<span data-ttu-id="e2734-333">Outlook 多年來在同步共用信箱時，其資料夾的數量限制最多為 500 個。</span><span class="sxs-lookup"><span data-stu-id="e2734-333">For years Outlook has been limited to a maximum of 500 folders when synchronizing shared mailboxes.</span></span> <span data-ttu-id="e2734-334">透過這項變更已讓 Outlook 獲得改善，您在同步時將不會再遇到這 500 個資料夾的數量限制。</span><span class="sxs-lookup"><span data-stu-id="e2734-334">With this change Outlook has been improved to sync in a way that will no longer encounter this 500 folder limit.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="e2734-335">開始使用：</span><span class="sxs-lookup"><span data-stu-id="e2734-335">Getting Started:</span></span>

<span data-ttu-id="e2734-336">在信箱中新增 1000 個資料夾、讓其他人存取信箱、新增「其他人」的 Outlook 設定檔，然後確認同步處理是否可正常運作。</span><span class="sxs-lookup"><span data-stu-id="e2734-336">Create 1000 folders in a mailbox, give someone else access to the mailbox, create an Outlook profile for the "someone else" and verify that sync works.</span></span>

### <a name="word"></a><span data-ttu-id="e2734-337">Word</span><span class="sxs-lookup"><span data-stu-id="e2734-337">Word</span></span>

#### <a name="erase-just-a-little-bit"></a><span data-ttu-id="e2734-338">小面積清除</span><span class="sxs-lookup"><span data-stu-id="e2734-338">Erase just a little bit</span></span>

##### <a name="getting-started"></a><span data-ttu-id="e2734-339">開始使用：</span><span class="sxs-lookup"><span data-stu-id="e2734-339">Getting Started:</span></span>

<span data-ttu-id="e2734-340">前往 [繪圖] 索引標籤。選取 [橡皮擦] 下拉式清單。</span><span class="sxs-lookup"><span data-stu-id="e2734-340">Go to the Draw Tab. Select the Eraser dropdown.</span></span> <span data-ttu-id="e2734-341">選擇 [小型橡皮擦] 或 [中型橡皮擦]。</span><span class="sxs-lookup"><span data-stu-id="e2734-341">Choose Small Eraser or Medium Eraser.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="e2734-342">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="e2734-342">Scenarios to Try:</span></span>

<span data-ttu-id="e2734-343">前往 [繪圖] 索引標籤。選取畫筆。</span><span class="sxs-lookup"><span data-stu-id="e2734-343">Go to the Draw Tab. Select a pen.</span></span> <span data-ttu-id="e2734-344">畫出一道筆跡線條。</span><span class="sxs-lookup"><span data-stu-id="e2734-344">Draw an ink stroke.</span></span> <span data-ttu-id="e2734-345">選取 [橡皮擦] 下拉式清單。</span><span class="sxs-lookup"><span data-stu-id="e2734-345">Select the Eraser dropdown.</span></span> <span data-ttu-id="e2734-346">選擇 [小型橡皮擦] 或 [中型橡皮擦]。</span><span class="sxs-lookup"><span data-stu-id="e2734-346">Choose Small Eraser or Medium Eraser.</span></span> <span data-ttu-id="e2734-347">清除一小塊的筆跡線條。</span><span class="sxs-lookup"><span data-stu-id="e2734-347">Erase just bits of the ink stroke.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="e2734-348">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="e2734-348">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="e2734-349">全部</span><span class="sxs-lookup"><span data-stu-id="e2734-349">All</span></span> 
- <span data-ttu-id="e2734-350">我們已修正可能會導致部分使用者無法儲存成 PDF 的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-350">We fixed an issue which could prevent some users from saving as PDF</span></span>
- <span data-ttu-id="e2734-351">我們已修正可能會影響使用者在 32 位元系統上儲存大型檔案的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-351">We fixed an issue which could impact users saving large files on a 32-bit system</span></span>

### <a name="word"></a><span data-ttu-id="e2734-352">Word</span><span class="sxs-lookup"><span data-stu-id="e2734-352">Word</span></span> 
- <span data-ttu-id="e2734-353">我們已大幅改善 [聽寫] 功能的反應能力</span><span class="sxs-lookup"><span data-stu-id="e2734-353">We significantly improved the responsiveness of the dictation feature</span></span>

### <a name="excel"></a><span data-ttu-id="e2734-354">Excel</span><span class="sxs-lookup"><span data-stu-id="e2734-354">Excel</span></span>
- <span data-ttu-id="e2734-355">我們已修正按兩下事件在觸控式螢幕裝置上可能會失靈的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-355">We fixed an issue where double-click events could fail on touch screen devices</span></span>
- <span data-ttu-id="e2734-356">我們已修正可能會導致部分使用者無法編輯 VBA 巨集的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-356">We fixed an issue which could prevent some users from being able to edit VBA macros</span></span>
- <span data-ttu-id="e2734-357">我們已修正使用交叉分析篩選器時可能會影響效能的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-357">We fixed an issue which could impact performance when using slicers</span></span>

### <a name="powerpoint"></a><span data-ttu-id="e2734-358">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e2734-358">PowerPoint</span></span>
- <span data-ttu-id="e2734-359">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-359">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="e2734-360">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2734-360">Outlook</span></span>
- <span data-ttu-id="e2734-361">我們已修正從所選範本中會出現錯誤範本的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-361">We fixed an issue where the wrong template could be displayed from what was selected</span></span>

### <a name="access"></a><span data-ttu-id="e2734-362">Access</span><span class="sxs-lookup"><span data-stu-id="e2734-362">Access</span></span>
- <span data-ttu-id="e2734-363">我們已修正在使用縮放建立器顯示完整 RTF 格式時，可能難以閱讀的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-363">We fixed an issue where using the zoom builder to display long rich text, could be hard to read</span></span>

### <a name="project"></a><span data-ttu-id="e2734-364">Project</span><span class="sxs-lookup"><span data-stu-id="e2734-364">Project</span></span>
- <span data-ttu-id="e2734-365">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-365">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-10-2019"></a><span data-ttu-id="e2734-366">2019 年 5 月 10 日</span><span class="sxs-lookup"><span data-stu-id="e2734-366">May 10, 2019</span></span>
<span data-ttu-id="e2734-367">版本 1906 (組建 11702.20000)</span><span class="sxs-lookup"><span data-stu-id="e2734-367">Version 1906 (build 11702.20000)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="e2734-368">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="e2734-368">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="e2734-369">全部</span><span class="sxs-lookup"><span data-stu-id="e2734-369">All</span></span>
- <span data-ttu-id="e2734-370">我們已修正 [另存新檔] 對話方塊顯示不正確路徑的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-370">We fixed an issue where the Save As dialog could display the incorrect path</span></span>

### <a name="word"></a><span data-ttu-id="e2734-371">Word</span><span class="sxs-lookup"><span data-stu-id="e2734-371">Word</span></span> 
- <span data-ttu-id="e2734-372">我們已修正有些「告訴我」選項無法插入的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-372">We fixed an issue where some selections from Tell Me would not get inserted</span></span>

### <a name="excel"></a><span data-ttu-id="e2734-373">Excel</span><span class="sxs-lookup"><span data-stu-id="e2734-373">Excel</span></span>
- <span data-ttu-id="e2734-374">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-374">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="e2734-375">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e2734-375">PowerPoint</span></span>
- <span data-ttu-id="e2734-376">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-376">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="e2734-377">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2734-377">Outlook</span></span>
- <span data-ttu-id="e2734-378">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-378">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="e2734-379">Access</span><span class="sxs-lookup"><span data-stu-id="e2734-379">Access</span></span>
- <span data-ttu-id="e2734-380">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-380">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="e2734-381">Project</span><span class="sxs-lookup"><span data-stu-id="e2734-381">Project</span></span>
- <span data-ttu-id="e2734-382">我們已修正任務識別碼需要醒目提示才能看見的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-382">We fixed an issue where Task ID's could require highlighting to see</span></span>

</BR></BR>

## <a name="may-3-2019"></a><span data-ttu-id="e2734-383">2019 年 5 月 3 日</span><span class="sxs-lookup"><span data-stu-id="e2734-383">May 3, 2019</span></span>
<span data-ttu-id="e2734-384">版本 1906 (組建 11629.20008)</span><span class="sxs-lookup"><span data-stu-id="e2734-384">Version 1906 (build 11629.20008)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="e2734-385">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="e2734-385">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="e2734-386">全部</span><span class="sxs-lookup"><span data-stu-id="e2734-386">All</span></span>
- <span data-ttu-id="e2734-387">我們已修正有些使用者使用商務用 OneDrive 同步處理時遇到的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-387">We fixed an issue where some users would experience problems syncing with OneDrive for Business</span></span>

### <a name="word"></a><span data-ttu-id="e2734-388">Word</span><span class="sxs-lookup"><span data-stu-id="e2734-388">Word</span></span> 
- <span data-ttu-id="e2734-389">我們已修正在某些情況下，Word 會花很長時間啟動的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-389">We fixed an issue where in some cases Word would take a long time to start</span></span>

### <a name="excel"></a><span data-ttu-id="e2734-390">Excel</span><span class="sxs-lookup"><span data-stu-id="e2734-390">Excel</span></span>
- <span data-ttu-id="e2734-391">我們已修正升級至較新版 Excel 後活頁簿的外部連結有時會被移除的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-391">We fixed an issue where external links were sometimes removed from workbooks after upgrading to a newer version of Excel</span></span>
- <span data-ttu-id="e2734-392">我們已修正有些使用者可能會遇到無法在新活頁簿中選取儲存格的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-392">We fixed an issue where some users could experience difficulty selecting cells in a new workbook</span></span>

### <a name="powerpoint"></a><span data-ttu-id="e2734-393">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e2734-393">PowerPoint</span></span>
- <span data-ttu-id="e2734-394">我們已修正將繪圖轉換成文字時字型大小不一致的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-394">We fixed an issue where font sizes were not consistant when converting drawings to text</span></span>

### <a name="outlook"></a><span data-ttu-id="e2734-395">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2734-395">Outlook</span></span>
- <span data-ttu-id="e2734-396">我們已修正從 .VCF 檔案儲存連絡人可能會導致空白欄位的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-396">We fixed an issue where saving a contact from a .VCF file could result in empty fields</span></span>
- <span data-ttu-id="e2734-397">我們已修正即使郵件已寄出卻仍卡在寄件匣資料夾的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-397">We fixed an issue where a message could get stuck in the outbox folder even though it had been sent</span></span>
- <span data-ttu-id="e2734-398">我們已修正檢視 DRM 訊息時 Outlook 可能會當機的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-398">We fixed an issue where Outlook could crash when viewing a DRM message</span></span>

### <a name="access"></a><span data-ttu-id="e2734-399">Access</span><span class="sxs-lookup"><span data-stu-id="e2734-399">Access</span></span>
- <span data-ttu-id="e2734-400">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-400">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="e2734-401">Project</span><span class="sxs-lookup"><span data-stu-id="e2734-401">Project</span></span>
- <span data-ttu-id="e2734-402">我們已修正編輯器會從中文切換為英文的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-402">We fixed an issue where the editor would switch from Chinese to English</span></span>
- <span data-ttu-id="e2734-403">我們已修正主專案的已發佈複本中出現未發佈工作的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-403">We fixed an issue where unpublished tasks could appear in the published copy of a master project</span></span>

</BR></BR>

## <a name="april-26-2019"></a><span data-ttu-id="e2734-404">2019 年 4 月 26 日</span><span class="sxs-lookup"><span data-stu-id="e2734-404">April 26, 2019</span></span>
<span data-ttu-id="e2734-405">版本 1905 (組建 11617.20002)</span><span class="sxs-lookup"><span data-stu-id="e2734-405">Version 1905 (build 11617.20002)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="e2734-406">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="e2734-406">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="e2734-407">Word</span><span class="sxs-lookup"><span data-stu-id="e2734-407">Word</span></span> 
- <span data-ttu-id="e2734-408">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-408">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="e2734-409">Excel</span><span class="sxs-lookup"><span data-stu-id="e2734-409">Excel</span></span>
- <span data-ttu-id="e2734-410">我們已修正 Solver 巨集無法執行的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-410">We fixed an issue where Solver macros would fail to run</span></span>
- <span data-ttu-id="e2734-411">我們已修正阻止 Excel 檔案匯入到 SharePoint 的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-411">We fixed an issue which could prevent Excel files from being imported into SharePoint</span></span>

### <a name="powerpoint"></a><span data-ttu-id="e2734-412">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e2734-412">PowerPoint</span></span>
- <span data-ttu-id="e2734-413">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-413">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="e2734-414">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2734-414">Outlook</span></span>
- <span data-ttu-id="e2734-415">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-415">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="e2734-416">Access</span><span class="sxs-lookup"><span data-stu-id="e2734-416">Access</span></span>
- <span data-ttu-id="e2734-417">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-417">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="e2734-418">Project</span><span class="sxs-lookup"><span data-stu-id="e2734-418">Project</span></span>
- <span data-ttu-id="e2734-419">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-419">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-19-2019"></a><span data-ttu-id="e2734-420">2019 年 4 月 19 日</span><span class="sxs-lookup"><span data-stu-id="e2734-420">April 19, 2019</span></span>
<span data-ttu-id="e2734-421">版本 1905 (組建 11609.20002)</span><span class="sxs-lookup"><span data-stu-id="e2734-421">Version 1905 (build 11609.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="e2734-422">新功能：</span><span class="sxs-lookup"><span data-stu-id="e2734-422">What's New:</span></span>

### <a name="excel"></a><span data-ttu-id="e2734-423">Excel</span><span class="sxs-lookup"><span data-stu-id="e2734-423">Excel</span></span>

#### <a name="improved-filled-maps-experience-using-data-types"></a><span data-ttu-id="e2734-424">使用資料類型改善區域分布圖體驗</span><span class="sxs-lookup"><span data-stu-id="e2734-424">Improved Filled Maps experience using Data Types</span></span>

<span data-ttu-id="e2734-425">此功能是針對使用 Excel 的地理資料類型繪製區域分布圖圖表使用者的增強功能。</span><span class="sxs-lookup"><span data-stu-id="e2734-425">This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="e2734-426">對使用者的優點是功能之間有更豐富的整合，以及使用者要對應的區域會有更好的精確度。</span><span class="sxs-lookup"><span data-stu-id="e2734-426">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="e2734-427">其他優點包括功能能夠對應城市多邊形。</span><span class="sxs-lookup"><span data-stu-id="e2734-427">Additional benefits include - ability to map city polygons.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="e2734-428">開始使用：</span><span class="sxs-lookup"><span data-stu-id="e2734-428">Getting Started:</span></span>

- <span data-ttu-id="e2734-429">此功能是 Excel 內現有功能的增強功能。</span><span class="sxs-lookup"><span data-stu-id="e2734-429">This feature is an improvement to the existing features within Excel.</span></span> <span data-ttu-id="e2734-430">若要使用增強功能，請將位置轉換為豐富的實體，並使用區域分布圖繪製。</span><span class="sxs-lookup"><span data-stu-id="e2734-430">To use the improvement - convert locations into Rich Entities and plot with Filled Maps.</span></span> 

##### <a name="scenarios-to-try"></a><span data-ttu-id="e2734-431">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="e2734-431">Scenarios to Try:</span></span>

- <span data-ttu-id="e2734-432">使用者可以嘗試對應城市、省/市、縣/市、國家/地區和郵遞區號。</span><span class="sxs-lookup"><span data-stu-id="e2734-432">Users can try mapping cities, states, counties, countries and zip codes.</span></span> 


## <a name="notable-fixes"></a><span data-ttu-id="e2734-433">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="e2734-433">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="e2734-434">所有應用程式</span><span class="sxs-lookup"><span data-stu-id="e2734-434">All Applications</span></span>
- <span data-ttu-id="e2734-435">我們已修正每當應用程式啟動時會顯示 [初次執行] 對話方塊的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-435">We fixed an issue where the First Run dialog would display whenever an application was launched</span></span>
- <span data-ttu-id="e2734-436">我們已修正 [另存新檔] 對話方塊中 SharePoint 連結可能遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="e2734-436">We fixed an issue where a SharePoint link in the "save as" dialog could be missing.</span></span>
- <span data-ttu-id="e2734-437">我們已修正使用者錯誤地看到 [立即修復] 對話方塊的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-437">We fixed an issue where users would incorrectly see a "Repair Now" dialog</span></span>

### <a name="word"></a><span data-ttu-id="e2734-438">Word</span><span class="sxs-lookup"><span data-stu-id="e2734-438">Word</span></span> 
- <span data-ttu-id="e2734-439">我們已修正某些使用者在要求字型時，可能會收到記憶體或磁碟空間不足錯誤的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-439">We fixed an issue where some users could receive an error for insufficient memory or disk space when requesting a font</span></span>
- <span data-ttu-id="e2734-440">我們已修正視窗從 [註解] 窗格切換時，焦點可能會遺失的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-440">We fixed an issue where a window could lose focus when switching from the comments pane</span></span>

### <a name="excel"></a><span data-ttu-id="e2734-441">Excel</span><span class="sxs-lookup"><span data-stu-id="e2734-441">Excel</span></span>
- <span data-ttu-id="e2734-442">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-442">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="e2734-443">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e2734-443">PowerPoint</span></span>
- <span data-ttu-id="e2734-444">我們已修正會妨礙調整商標圖形大小的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-444">We fixed an issue preventing the resizing of branded shapes</span></span>
- <span data-ttu-id="e2734-445">我們已修正在受保護的檢視模式中開啟檔案時，PowerPoint 會當機的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-445">We fixed an issue where PowerPoint could crash when opening a file in protected view mode</span></span>

### <a name="outlook"></a><span data-ttu-id="e2734-446">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2734-446">Outlook</span></span>
- <span data-ttu-id="e2734-447">我們已修正會防礙一些使用者選取中文文字的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-447">We fixed an issue which prevented some users from selecting Chinese words</span></span>
- <span data-ttu-id="e2734-448">我們已修正未正確計算到期日的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-448">We fixed an issue where expiry dates were not calculated correctly</span></span>

### <a name="access"></a><span data-ttu-id="e2734-449">Access</span><span class="sxs-lookup"><span data-stu-id="e2734-449">Access</span></span>
- <span data-ttu-id="e2734-450">我們已修正會防礙一些使用者使用巨集建立器的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-450">We fixed an issue which prevented some users from using the Macro Builder</span></span>
- <span data-ttu-id="e2734-451">我們已修正列印報表只會列印第一頁的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-451">We fixed an issue where printing a report would only print the first page</span></span>
- <span data-ttu-id="e2734-452">我們已修正將游標移到超連結上時，應用程式會當機的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-452">We fixed an issue where the application could crash when hovering over a hyperlink</span></span>
- <span data-ttu-id="e2734-453">我們已修正使用關聯性檢視檢視時，造成某些項目在螢幕上消失的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-453">We fixed an issue which caused some items to appear off screen when using relationships view</span></span>

### <a name="project"></a><span data-ttu-id="e2734-454">Project</span><span class="sxs-lookup"><span data-stu-id="e2734-454">Project</span></span>
- <span data-ttu-id="e2734-455">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-455">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-12-2019"></a><span data-ttu-id="e2734-456">2019 年 4 月 12 日</span><span class="sxs-lookup"><span data-stu-id="e2734-456">April 12, 2019</span></span>
<span data-ttu-id="e2734-457">版本 1905 (組建 11601.20042)</span><span class="sxs-lookup"><span data-stu-id="e2734-457">Version 1905 (build 11601.20042)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="e2734-458">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="e2734-458">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="e2734-459">所有應用程式</span><span class="sxs-lookup"><span data-stu-id="e2734-459">All Applications</span></span>
 - <span data-ttu-id="e2734-460">我們已修正會防止使用者將檔案儲存到雲端位置的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-460">We fixed an issue which prevented some users from saving files to cloud locations</span></span>
 - <span data-ttu-id="e2734-461">我們已修正可能從功能區開啟錯誤窗格的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-461">We fixed an issue where the wrong pane could open from the ribbon</span></span>

### <a name="word"></a><span data-ttu-id="e2734-462">Word</span><span class="sxs-lookup"><span data-stu-id="e2734-462">Word</span></span> 
- <span data-ttu-id="e2734-463">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-463">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="e2734-464">Excel</span><span class="sxs-lookup"><span data-stu-id="e2734-464">Excel</span></span>
- <span data-ttu-id="e2734-465">我們已修正當活頁簿不包含連結資料類型時，使用者會看到連結資料類型之錯誤訊息的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-465">We fixed an issue where users would see an error message for linked data types when the workbook did not contain linked data types</span></span>
- <span data-ttu-id="e2734-466">我們已修正在本機與線上檢視 Word 文件時，文件中的 URL 連結可能變更的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-466">We fixed an issue where URL links within a Word document could change when viewed locally vs. online</span></span>

### <a name="powerpoint"></a><span data-ttu-id="e2734-467">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e2734-467">PowerPoint</span></span>
- <span data-ttu-id="e2734-468">我們已修正應用程式可能會在從 [動畫] 索引標籤復原變更之後當機的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-468">We fixed an issue where the application could crash after undoing changes from the animations tab</span></span>

### <a name="outlook"></a><span data-ttu-id="e2734-469">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2734-469">Outlook</span></span>
- <span data-ttu-id="e2734-470">我們已修正會防止一些使用者修改公用資料夾中連絡人 [備註] 欄位的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-470">We fixed an issue which prevented some users from modifying the Notes field for contacts in a Public Folder</span></span>
- <span data-ttu-id="e2734-471">我們已修正到期日與刪除日期之間可能發生衝突的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-471">We fixed an issue where a conflict could occur between expiration dates and deletion dates</span></span>

### <a name="access"></a><span data-ttu-id="e2734-472">Access</span><span class="sxs-lookup"><span data-stu-id="e2734-472">Access</span></span>
- <span data-ttu-id="e2734-473">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-473">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="e2734-474">Project</span><span class="sxs-lookup"><span data-stu-id="e2734-474">Project</span></span>
- <span data-ttu-id="e2734-475">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-475">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-5-2019"></a><span data-ttu-id="e2734-476">2019 年 4 月 5 日</span><span class="sxs-lookup"><span data-stu-id="e2734-476">April 5, 2019</span></span>
<span data-ttu-id="e2734-477">版本 1904 (組建 11527.20014)</span><span class="sxs-lookup"><span data-stu-id="e2734-477">Version 1904 (build 11527.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="e2734-478">新功能：</span><span class="sxs-lookup"><span data-stu-id="e2734-478">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="e2734-479">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2734-479">Outlook</span></span>

#### <a name="outlook-for-windows--set-and-share-your-focused-inbox-settings"></a><span data-ttu-id="e2734-480">Windows 版 Outlook：設定並共用您的 [焦點收件匣] 設定</span><span class="sxs-lookup"><span data-stu-id="e2734-480">Outlook for Windows:  set and share your Focused Inbox settings</span></span>

<span data-ttu-id="e2734-481">[焦點收件匣] 喜好設定會儲存在雲端內，因此當您在任何電腦上使用 Windows 版 Outlook 和 Outlook 網頁版時，都可以取得相同的一致體驗。</span><span class="sxs-lookup"><span data-stu-id="e2734-481">Your Focused Inbox preferences are stored in the cloud so you can enjoy the same consistent experience when using Outlook for Windows and Outlook on the web on any computer.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="e2734-482">開始使用：</span><span class="sxs-lookup"><span data-stu-id="e2734-482">Getting Started:</span></span>

<span data-ttu-id="e2734-483">在 [檔案] > [選項] > [一般] 索引標籤下，還有一個名為 [將我的 Outlook 設定儲存在雲端中] 的新喜好設定。</span><span class="sxs-lookup"><span data-stu-id="e2734-483">Under File > Options > General tab, there is a new preference for 'Store my Outlook settings in the cloud'.</span></span> <span data-ttu-id="e2734-484">使用者需要核取方塊，才能讓他們的 [焦點收件匣] 設定漫遊到其他電腦的 Outlook 安裝和 OWA。</span><span class="sxs-lookup"><span data-stu-id="e2734-484">Users will need to check the box to enable their Focused Inbox setting to roam to other Desktop Outlook installations and OWA.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="e2734-485">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="e2734-485">Scenarios to Try:</span></span>

<span data-ttu-id="e2734-486">在已開啟雲端設定喜好設定的電腦上變更 [焦點收件匣]。</span><span class="sxs-lookup"><span data-stu-id="e2734-486">Change Focused Inbox on the machine that has cloud settings preference turned on.</span></span> <span data-ttu-id="e2734-487">瀏覽至 OWA，然後查看那裡也同樣套用了喜好設定。</span><span class="sxs-lookup"><span data-stu-id="e2734-487">Navigate to OWA and see the preference applied there as well.</span></span> <span data-ttu-id="e2734-488">在 OWA 變更 [焦點收件匣]，然後啟動電腦版 Outlook 查看已反映喜好設定。</span><span class="sxs-lookup"><span data-stu-id="e2734-488">Change Focused Inbox in OWA and start Desktop Outlook to see the preference reflected.</span></span>

### <a name="word"></a><span data-ttu-id="e2734-489">Word</span><span class="sxs-lookup"><span data-stu-id="e2734-489">Word</span></span>

#### <a name="learning-tools-mode-has-additional-support-for-more-page-colors"></a><span data-ttu-id="e2734-490">[學習工具] 模式額外支援更多頁面色彩</span><span class="sxs-lookup"><span data-stu-id="e2734-490">Learning Tools mode has additional support for more page colors</span></span>

<span data-ttu-id="e2734-491">Word 中的 [學習工具] 新增更多頁面佈景主題色彩的支援，讓您能夠變更頁面的背景色彩。</span><span class="sxs-lookup"><span data-stu-id="e2734-491">Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span>  <span data-ttu-id="e2734-492">許多人在背景全白或全黑時閱讀會有困難，因此我們在 PC 和 Mac 的 Word 中增加了色彩選項。</span><span class="sxs-lookup"><span data-stu-id="e2734-492">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="e2734-493">開始使用：</span><span class="sxs-lookup"><span data-stu-id="e2734-493">Getting Started:</span></span>

<span data-ttu-id="e2734-494">若要試用，請移至 [檢視] 索引標籤，選擇 [學習工具]，然後選擇 [頁面色彩]。</span><span class="sxs-lookup"><span data-stu-id="e2734-494">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="e2734-495">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="e2734-495">Scenarios to Try:</span></span>

<span data-ttu-id="e2734-496">若要試用，請移至 [檢視] 索引標籤，選擇 [學習工具]，然後選擇 [頁面色彩]。</span><span class="sxs-lookup"><span data-stu-id="e2734-496">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

### <a name="excel"></a><span data-ttu-id="e2734-497">Excel</span><span class="sxs-lookup"><span data-stu-id="e2734-497">Excel</span></span>

#### <a name="elevate-creativity-with-animated-3d-models"></a><span data-ttu-id="e2734-498">以具備動畫效果的 3D 模型提高創意</span><span class="sxs-lookup"><span data-stu-id="e2734-498">Elevate Creativity with Animated 3D Models</span></span>

<span data-ttu-id="e2734-499">Office 現在支援動畫模型，這類模型能在編輯器中播放，讓您的試算表更生動！</span><span class="sxs-lookup"><span data-stu-id="e2734-499">Office now supports animated models, which will playback in the editor so you can bring your sheets to life!</span></span>

#### <a name="getting-started"></a><span data-ttu-id="e2734-500">開始使用：</span><span class="sxs-lookup"><span data-stu-id="e2734-500">Getting Started:</span></span>

1. <span data-ttu-id="e2734-501">開啟 Excel</span><span class="sxs-lookup"><span data-stu-id="e2734-501">Open Excel 2007.</span></span>
2. <span data-ttu-id="e2734-502">插入具備動畫效果的 3D 模型 (很快會進到 Remix，但現在請在此位置存取動畫模型：\\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span><span class="sxs-lookup"><span data-stu-id="e2734-502">Insert an animated 3D Model (coming to Remix soon, but for now, access animated models here: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span></span>
3. <span data-ttu-id="e2734-503">動畫模型會在編輯器中播放！</span><span class="sxs-lookup"><span data-stu-id="e2734-503">The animated model will play in the editor!</span></span> <span data-ttu-id="e2734-504">[檢查投影片放映] 模式 - 動畫模型也會在那裡播放！</span><span class="sxs-lookup"><span data-stu-id="e2734-504">Check Slideshow mode - it will play there too!</span></span>
4. <span data-ttu-id="e2734-505">在 3D 格式功能區中，探索模型中更多的動畫場景</span><span class="sxs-lookup"><span data-stu-id="e2734-505">In the 3D Format Ribbon, explore more animation scenes in the model</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="e2734-506">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="e2734-506">Scenarios to Try:</span></span>

1. <span data-ttu-id="e2734-507">插入動畫模型，然後看它在編輯器中播放</span><span class="sxs-lookup"><span data-stu-id="e2734-507">Insert an animated model and watch it play in the editor</span></span>
2. <span data-ttu-id="e2734-508">透過 3D 格式功能區中的 [場景庫]，探索動畫模型中可用的動畫場景</span><span class="sxs-lookup"><span data-stu-id="e2734-508">Explore the animation scenes available in the animated model via the Scenes Gallery, available in the 3D Format Ribbon</span></span>
3. <span data-ttu-id="e2734-509">透過功能區、浮動工具列或空格鍵輕鬆地播放/暫停動畫</span><span class="sxs-lookup"><span data-stu-id="e2734-509">Easily play/pause the animation via the ribbon, floatie or space bar</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="e2734-510">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="e2734-510">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="e2734-511">所有應用程式</span><span class="sxs-lookup"><span data-stu-id="e2734-511">All Applications</span></span>
- <span data-ttu-id="e2734-512">我們已修正 Excel 的內容功能表中會出現錯誤應用程式圖示的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-512">We fixed an issue where the incorrect app icon could appear for Excel in contextual menus</span></span>
- <span data-ttu-id="e2734-513">我們已修正在安裝更新之後 [檔案功能表] 按鈕會消失的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-513">We fixed an issue where the File Menu button could disappear after installing an update</span></span>
- <span data-ttu-id="e2734-514">我們已修正會變更您的使用者授權的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-514">We fixed an issue which could change your user license</span></span>

### <a name="word"></a><span data-ttu-id="e2734-515">Word</span><span class="sxs-lookup"><span data-stu-id="e2734-515">Word</span></span> 
- <span data-ttu-id="e2734-516">我們已修正文字在特定縮放比例中無法正常顯示的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-516">We fixed an issue where text would not render correctly at certain zoom levels</span></span>

### <a name="excel"></a><span data-ttu-id="e2734-517">Excel</span><span class="sxs-lookup"><span data-stu-id="e2734-517">Excel</span></span>
- <span data-ttu-id="e2734-518">我們已修正使用者在進行編輯之後未收到儲存活頁簿提示的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-518">We fixed an issue where users would not be prompted to save a workbook after making edits</span></span>
- <span data-ttu-id="e2734-519">我們已修正當使用者共用活頁簿時未觸發 BeforeSave 事件的問題。</span><span class="sxs-lookup"><span data-stu-id="e2734-519">We fixed an issue where a BeforeSave event would not be triggered if the user shared the workbook.</span></span>
- <span data-ttu-id="e2734-520">我們已修正將欄的大小重新調整為小於 6 像素會擲回不正確錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="e2734-520">We fixed an issue where resizing a column to fewer than 6 pixels could throw an incorrect error message.</span></span>
- <span data-ttu-id="e2734-521">我們已修正 Excel 忽略 Application.Visible 旗標的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-521">We fixed an issue where Excel would ignore the Application.Visible flag</span></span>
- <span data-ttu-id="e2734-522">我們已修正追蹤箭號保留在非作用中凍結窗格的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-522">We fixed an issue where trace arrows would remain on non-active frozen panes</span></span>
- <span data-ttu-id="e2734-523">我們已修正在開啟活頁簿時日期和貨幣儲存格格式會變更的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-523">We fixed an issue where cell formatting of dates an currency could change when opening a workbook</span></span>
- <span data-ttu-id="e2734-524">我們已修正工具提示會意外移動的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-524">We fixed an issue where tooltips would move unexpectedly</span></span>
- <span data-ttu-id="e2734-525">我們已修正 Power Query 編輯器的當地語系化問題</span><span class="sxs-lookup"><span data-stu-id="e2734-525">We fixed localization issues for the Power Query editor</span></span>
- <span data-ttu-id="e2734-526">我們已修正在透過電子郵件傳送時活頁簿附件會遭到移除的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-526">We fixed an issue where a workbook would be removed as an attachment when sending via e-mail</span></span>

### <a name="powerpoint"></a><span data-ttu-id="e2734-527">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e2734-527">PowerPoint</span></span>
- <span data-ttu-id="e2734-528">我們已修正複製圖形會比預期還要久的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-528">We fixed an issue where copying shapes would take longer than expected</span></span>

### <a name="outlook"></a><span data-ttu-id="e2734-529">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2734-529">Outlook</span></span>
- <span data-ttu-id="e2734-530">我們已修正在使用繪圖工具時 Outlook 可能會當機的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-530">We fixed an issue where Outlook could crash while using the drawing tool</span></span>
- <span data-ttu-id="e2734-531">我們已修正當撰寫 html 電子郵件時的當地語系化問題</span><span class="sxs-lookup"><span data-stu-id="e2734-531">We fixed a localization issue when composing html e-mails</span></span>
- <span data-ttu-id="e2734-532">我們已修正使用者在選取下面窗格時會遇到困難的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-532">We fixed an issue where the user would have difficulty in selecting the lower pane</span></span>

### <a name="access"></a><span data-ttu-id="e2734-533">Access</span><span class="sxs-lookup"><span data-stu-id="e2734-533">Access</span></span>
- <span data-ttu-id="e2734-534">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-534">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="e2734-535">Project</span><span class="sxs-lookup"><span data-stu-id="e2734-535">Project</span></span>
- <span data-ttu-id="e2734-536">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-536">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-22-2019"></a><span data-ttu-id="e2734-537">2019 年 3 月 22 日</span><span class="sxs-lookup"><span data-stu-id="e2734-537">March 22, 2019</span></span>
<span data-ttu-id="e2734-538">版本 1904 (組建 11514.20004)</span><span class="sxs-lookup"><span data-stu-id="e2734-538">Version 1904 (build 11514.20004)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="e2734-539">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="e2734-539">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="e2734-540">Word</span><span class="sxs-lookup"><span data-stu-id="e2734-540">Word</span></span> 
- <span data-ttu-id="e2734-541">我們已修正 UI 經常會顯示「正在檢查變更」的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-541">We fixed an issue where the UI would constantly display "Checking for Changes"</span></span>

### <a name="excel"></a><span data-ttu-id="e2734-542">Excel</span><span class="sxs-lookup"><span data-stu-id="e2734-542">Excel</span></span>
- <span data-ttu-id="e2734-543">我們已修正應用程式可能在移動工作表之後當機的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-543">We fixed an issue where the application could crash after moving a worksheet</span></span>
- <span data-ttu-id="e2734-544">我們已修正應用程式可能在儲存為 PDF 之後當機的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-544">We fixed an issue where the application could crash after saving as a PDF</span></span>
- <span data-ttu-id="e2734-545">我們已修正儲存對話方塊不會接受某些韓文字元的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-545">We fixed an issue where the save dialog would not accept some Korean characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="e2734-546">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e2734-546">PowerPoint</span></span>
- <span data-ttu-id="e2734-547">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-547">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="e2734-548">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2734-548">Outlook</span></span>
- <span data-ttu-id="e2734-549">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-549">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="e2734-550">Access</span><span class="sxs-lookup"><span data-stu-id="e2734-550">Access</span></span>
- <span data-ttu-id="e2734-551">我們已修正 Access 中對 Access 建立額外捷徑的錯誤訊息</span><span class="sxs-lookup"><span data-stu-id="e2734-551">We fixed the error message in Access where an extra shortcut to Access was created</span></span>
- <span data-ttu-id="e2734-552">我們已修正來自連結 SharePoint 的資料無法正確顯示的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-552">We fixed an issue where data from a linked SharePoint would display incorrectly</span></span>

### <a name="project"></a><span data-ttu-id="e2734-553">Project</span><span class="sxs-lookup"><span data-stu-id="e2734-553">Project</span></span>
- <span data-ttu-id="e2734-554">我們已修正語言設定會從中文切換為英文的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-554">We fixed an issue where the language settings would switch from Chinese to English</span></span>
- <span data-ttu-id="e2734-555">我們已修正應用程式可能在同步處理到 SharePoint 時當機的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-555">We fixed an issue where the application could crash when synching to SharePoint</span></span>

</BR></BR>

## <a name="march-15-2019"></a><span data-ttu-id="e2734-556">2019 年 3 月 15 日</span><span class="sxs-lookup"><span data-stu-id="e2734-556">March 15, 2019</span></span>
<span data-ttu-id="e2734-557">版本 1904 (組建 11504.20000)</span><span class="sxs-lookup"><span data-stu-id="e2734-557">Version 1904 (build 11504.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="e2734-558">新功能：</span><span class="sxs-lookup"><span data-stu-id="e2734-558">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="e2734-559">Word</span><span class="sxs-lookup"><span data-stu-id="e2734-559">Word</span></span>

#### <a name="focus-mode"></a><span data-ttu-id="e2734-560">焦點模式</span><span class="sxs-lookup"><span data-stu-id="e2734-560">Focus mode</span></span>

<span data-ttu-id="e2734-561">切換到 [檢視] 功能表中的 [焦點] 以移除令人分心的事物，讓您更能專注於工作。</span><span class="sxs-lookup"><span data-stu-id="e2734-561">Switch to Focus on the View menu to remove distractions and concentrate on your work.</span></span> <span data-ttu-id="e2734-562">僅供 Office 365 訂閱者使用。</span><span class="sxs-lookup"><span data-stu-id="e2734-562">For Office 365 subscribers only.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="e2734-563">開始使用：</span><span class="sxs-lookup"><span data-stu-id="e2734-563">Getting Started:</span></span>

<span data-ttu-id="e2734-564">[檢視] 索引標籤 功能區狀態列中的 [焦點] 按鈕 [焦點] 按鈕</span><span class="sxs-lookup"><span data-stu-id="e2734-564">View tab "Focus" Button in the Ribbon Status Bar "Focus" Button</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="e2734-565">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="e2734-565">Scenarios to Try:</span></span>

<span data-ttu-id="e2734-566">進入焦點模式，享受專注的體驗</span><span class="sxs-lookup"><span data-stu-id="e2734-566">Enter Focus Mode and experience the Focused Experience</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="e2734-567">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="e2734-567">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="e2734-568">Word</span><span class="sxs-lookup"><span data-stu-id="e2734-568">Word</span></span> 
- <span data-ttu-id="e2734-569">我們已修正以 PDF 格式儲存文件時，文件中影像的 DPI 會不正確的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-569">We fixed an issue where images in a document saved as a PDF would have the incorrect DPI</span></span>

### <a name="excel"></a><span data-ttu-id="e2734-570">Excel</span><span class="sxs-lookup"><span data-stu-id="e2734-570">Excel</span></span>
- <span data-ttu-id="e2734-571">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-571">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="e2734-572">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e2734-572">PowerPoint</span></span>
- <span data-ttu-id="e2734-573">我們已修正註解窗格無法正確開啟或關閉的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-573">We fixed an issue where the comments pane would not open or close properly</span></span>
- <span data-ttu-id="e2734-574">我們已修正應用程式會在刪除影片時當機的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-574">We fixed an issue where the application could crash when deleting a video</span></span>
- <span data-ttu-id="e2734-575">我們已修正於某些情況下應用程式會無法啟動的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-575">We fixed an issue where in some instances the application would fail to launch</span></span>

### <a name="outlook"></a><span data-ttu-id="e2734-576">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2734-576">Outlook</span></span>
- <span data-ttu-id="e2734-577">我們已修正以日文檢視時讀信回條不正確的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-577">We fixed an issue where read receipts were incorrect when viewed in Japanese</span></span>

### <a name="access"></a><span data-ttu-id="e2734-578">Access</span><span class="sxs-lookup"><span data-stu-id="e2734-578">Access</span></span>
- <span data-ttu-id="e2734-579">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-579">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="e2734-580">Project</span><span class="sxs-lookup"><span data-stu-id="e2734-580">Project</span></span>
- <span data-ttu-id="e2734-581">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-581">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-8-2019"></a><span data-ttu-id="e2734-582">2019 年 3 月 8 日</span><span class="sxs-lookup"><span data-stu-id="e2734-582">March 8, 2019</span></span> 
<span data-ttu-id="e2734-583">版本 1903 (組建 11425.20036)</span><span class="sxs-lookup"><span data-stu-id="e2734-583">Version 1903 (build 11425.20036)</span></span>

## <a name="whats-new"></a><span data-ttu-id="e2734-584">新功能：</span><span class="sxs-lookup"><span data-stu-id="e2734-584">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="e2734-585">Word</span><span class="sxs-lookup"><span data-stu-id="e2734-585">Word</span></span>

### <a name="find-what-youre-looking-for-with-microsoft-search"></a><span data-ttu-id="e2734-586">使用 Microsoft Search 尋找您要的內容</span><span class="sxs-lookup"><span data-stu-id="e2734-586">Find What You're Looking For with Microsoft Search</span></span>

<span data-ttu-id="e2734-587">您可以使用 Microsoft Search 找到所有檔案、動作、人員，協助您完成工作所需。</span><span class="sxs-lookup"><span data-stu-id="e2734-587">With Microsoft Search, you can find all the files, actions, people, and help you need to get work done.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="e2734-588">開始使用：</span><span class="sxs-lookup"><span data-stu-id="e2734-588">Getting Started:</span></span>

- <span data-ttu-id="e2734-589">這個功能在標題中的 UI 上方強調顯示。</span><span class="sxs-lookup"><span data-stu-id="e2734-589">The feature is prominently displayed on top of the UI in the header.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="e2734-590">可嘗試使用的範例：</span><span class="sxs-lookup"><span data-stu-id="e2734-590">Scenarios to Try:</span></span>

- <span data-ttu-id="e2734-591">搜尋某間大學、最近使用過的文件或搜尋最常用的功能區命令</span><span class="sxs-lookup"><span data-stu-id="e2734-591">Search for a college, a recent document or search for the ribbon commands you use most often</span></span>
- <span data-ttu-id="e2734-592">尋找某個主題或主旨並取得更多相關資訊</span><span class="sxs-lookup"><span data-stu-id="e2734-592">Look up a topic or subject to get more information on it</span></span>
- 
#### <a name="coauthoring"></a><span data-ttu-id="e2734-593">共同撰寫</span><span class="sxs-lookup"><span data-stu-id="e2734-593">CoAuthoring</span></span>

<span data-ttu-id="e2734-594">厭倦於被包含巨集的文件阻礙了嗎？</span><span class="sxs-lookup"><span data-stu-id="e2734-594">Tired of being locked out of your document with macros?</span></span> <span data-ttu-id="e2734-595">現在商務用 OneDrive 的 docm 檔案允許同時由多個作者編輯。</span><span class="sxs-lookup"><span data-stu-id="e2734-595">Now your docm files on OneDrive for Business allow simultaneous editing by multiple authors.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="e2734-596">開始使用：</span><span class="sxs-lookup"><span data-stu-id="e2734-596">Getting Started:</span></span>

<span data-ttu-id="e2734-597">使用者在 UI 中不需要按下任何按鈕，就能存取這項功能。</span><span class="sxs-lookup"><span data-stu-id="e2734-597">The user doesn't need to press any buttons in the UI to access this feature.</span></span> <span data-ttu-id="e2734-598">商務用 OneDrive 的 docm 檔案預設已啟用此功能。</span><span class="sxs-lookup"><span data-stu-id="e2734-598">It is enabled by default on OneDrive for Business docm files.</span></span>
<span data-ttu-id="e2734-599">因此，使用者應該將 docm 檔案儲存至商務用 OneDrive 試用看看。</span><span class="sxs-lookup"><span data-stu-id="e2734-599">So, the user should save a docm file to OneDrive for Business to try it out.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="e2734-600">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="e2734-600">Scenarios to Try:</span></span>

<span data-ttu-id="e2734-601">在商務用 OneDrive 建立 docm 檔案、與同事共用並且共同作業！</span><span class="sxs-lookup"><span data-stu-id="e2734-601">Create a docm file on OneDrive for Business, share it with your colleagues, and collaborate!</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="e2734-602">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="e2734-602">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="e2734-603">Word</span><span class="sxs-lookup"><span data-stu-id="e2734-603">Word</span></span> 
- <span data-ttu-id="e2734-604">我們已修正在 [選項] 中按下 ESC 鍵時發生的當機問題</span><span class="sxs-lookup"><span data-stu-id="e2734-604">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="e2734-605">我們已修正回覆註解時發生的當機問題</span><span class="sxs-lookup"><span data-stu-id="e2734-605">We fixed a crashing issue that occurred when replying to comments</span></span>
- <span data-ttu-id="e2734-606">我們已修正從 Word 到 PowerPoint Online 的複製與貼上問題</span><span class="sxs-lookup"><span data-stu-id="e2734-606">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="e2734-607">Excel</span><span class="sxs-lookup"><span data-stu-id="e2734-607">Excel</span></span>
- <span data-ttu-id="e2734-608">我們已修正當受保護的文件和可編輯的文件在開啟時複製 Excel 儲存格導致高 CPU 使用率的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-608">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="e2734-609">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e2734-609">PowerPoint</span></span>
- <span data-ttu-id="e2734-610">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-610">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="e2734-611">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2734-611">Outlook</span></span>
- <span data-ttu-id="e2734-612">我們已修正 Outlook 搜尋未依所選時間順序排序的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-612">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="e2734-613">我們已修正 [開啟此工作] 工作流程功能區按鈕無法回應特定電子郵件的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-613">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="e2734-614">我們已修正使用者在 [會議室尋找工具] 中選取可用的會議室後，Outlook 無法清除內部部署會議室的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-614">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="e2734-615">Access</span><span class="sxs-lookup"><span data-stu-id="e2734-615">Access</span></span>
- <span data-ttu-id="e2734-616">我們已修正已儲存的匯入/匯出對話方塊在深色佈景主題中有白色文字在白色背景的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-616">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="e2734-617">我們已修正使用者在表格設計中無法針對 [文字方塊] 的 [是/否] 欄位設定 DisplayControl 屬性的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-617">We fixed an issue where users could not set the DisplayControl property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="e2734-618">Project</span><span class="sxs-lookup"><span data-stu-id="e2734-618">Project</span></span>
- <span data-ttu-id="e2734-619">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-619">Various performance and stability fixes</span></span>


## <a name="march-1-2019"></a><span data-ttu-id="e2734-620">2019 年 3 月 1 日</span><span class="sxs-lookup"><span data-stu-id="e2734-620">March 1, 2019</span></span> 
<span data-ttu-id="e2734-621">版本 1903 (組建 11414.20014)</span><span class="sxs-lookup"><span data-stu-id="e2734-621">Version 1903 (build 11414.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="e2734-622">新功能</span><span class="sxs-lookup"><span data-stu-id="e2734-622">What's New</span></span>

### <a name="word"></a><span data-ttu-id="e2734-623">Word</span><span class="sxs-lookup"><span data-stu-id="e2734-623">Word</span></span>

#### <a name="colors-for-track-changes-comments-and-real-time-collaboration-in-sync"></a><span data-ttu-id="e2734-624">追蹤修訂、註解和即時共同作業的色彩會同步</span><span class="sxs-lookup"><span data-stu-id="e2734-624">Colors for Track Changes, Comments and Real-Time Collaboration in Sync</span></span>

<span data-ttu-id="e2734-625">我們產品中的修正現在可確保註解、追蹤修訂及共同作業者的游標會以相同色彩顯示。</span><span class="sxs-lookup"><span data-stu-id="e2734-625">Colors for Track Changes, Comments and Real-Time Collaboration in Sync: Fixes in our product now ensure that the comments, track changes and the cursor for a collaborator show up in the same color.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="e2734-626">開始使用：</span><span class="sxs-lookup"><span data-stu-id="e2734-626">Getting Started:</span></span>

<span data-ttu-id="e2734-627">開啟其他人已開啟的 SharePoint 或 OneDrive 文件。</span><span class="sxs-lookup"><span data-stu-id="e2734-627">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="e2734-628">確認使用者的追蹤修訂和註解色彩符合該使用者游標的色彩。</span><span class="sxs-lookup"><span data-stu-id="e2734-628">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="e2734-629">可嘗試使用的案例：</span><span class="sxs-lookup"><span data-stu-id="e2734-629">Scenarios to Try:</span></span>

<span data-ttu-id="e2734-630">開啟其他人已開啟的 SharePoint 或 OneDrive 文件。</span><span class="sxs-lookup"><span data-stu-id="e2734-630">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="e2734-631">確認使用者的追蹤修訂和註解色彩符合該使用者游標的色彩。</span><span class="sxs-lookup"><span data-stu-id="e2734-631">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="e2734-632">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="e2734-632">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="e2734-633">Word</span><span class="sxs-lookup"><span data-stu-id="e2734-633">Word</span></span> 
- <span data-ttu-id="e2734-634">我們已修正在 [選項] 中按下 ESC 鍵時發生的當機問題</span><span class="sxs-lookup"><span data-stu-id="e2734-634">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="e2734-635">我們已修正從 Word 到 PowerPoint Online 的複製與貼上問題</span><span class="sxs-lookup"><span data-stu-id="e2734-635">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="e2734-636">Excel</span><span class="sxs-lookup"><span data-stu-id="e2734-636">Excel</span></span>
- <span data-ttu-id="e2734-637">我們已修正當受保護的文件和可編輯的文件在開啟時複製 Excel 儲存格導致高 CPU 使用率的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-637">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="e2734-638">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e2734-638">PowerPoint</span></span>
- <span data-ttu-id="e2734-639">我們已修正在 PowerPoint 中使用 @提及的投影片圖像大小問題</span><span class="sxs-lookup"><span data-stu-id="e2734-639">We fixed an issue with slide image size when using @Mentions in PowerPoint</span></span>

### <a name="outlook"></a><span data-ttu-id="e2734-640">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2734-640">Outlook</span></span>
- <span data-ttu-id="e2734-641">我們已修正 Outlook 搜尋未依所選時間順序排序的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-641">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="e2734-642">我們已修正 [開啟此工作] 工作流程功能區按鈕無法回應特定電子郵件的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-642">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="e2734-643">我們已修正使用者在 [會議室尋找工具] 中選取可用的會議室後，Outlook 無法清除內部部署會議室的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-643">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="e2734-644">Access</span><span class="sxs-lookup"><span data-stu-id="e2734-644">Access</span></span>
- <span data-ttu-id="e2734-645">我們已更新確認使用資料來源重新連結資料表時顯示的提示文字</span><span class="sxs-lookup"><span data-stu-id="e2734-645">We updated the prompt text that showed when confirming the relinking tables with a datasource</span></span>
- <span data-ttu-id="e2734-646">我們已修正已儲存的匯入/匯出對話方塊在深色佈景主題中有白色文字在白色背景的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-646">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="e2734-647">我們已修正使用者在表格設計中無法針對 [文字方塊] 的 [是/否] 欄位設定 [顯示控制項] 屬性的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-647">We fixed an issue where users could not set the Display Control property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="e2734-648">Project</span><span class="sxs-lookup"><span data-stu-id="e2734-648">Project</span></span>
- <span data-ttu-id="e2734-649">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-649">Various performance and stability fixes</span></span>

</BR></BR>



## <a name="february-15-2019"></a><span data-ttu-id="e2734-650">2019 年 2 月 15 日</span><span class="sxs-lookup"><span data-stu-id="e2734-650">February 15, 2019</span></span> 
<span data-ttu-id="e2734-651">版本 1903 (組建 11310.20016)</span><span class="sxs-lookup"><span data-stu-id="e2734-651">Version 1903 (build 11310.20016)</span></span>

## <a name="whats-new"></a><span data-ttu-id="e2734-652">新功能：</span><span class="sxs-lookup"><span data-stu-id="e2734-652">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="e2734-653">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e2734-653">PowerPoint</span></span>


### <a name="morph-transition-enhancements---morph-by-name"></a><span data-ttu-id="e2734-654">轉化轉場增強效果 - 依名稱轉化</span><span class="sxs-lookup"><span data-stu-id="e2734-654">Morph Transition Enhancements - Morph by Name</span></span>

<span data-ttu-id="e2734-655">選取要轉化的圖形</span><span class="sxs-lookup"><span data-stu-id="e2734-655">Specify the shapes you want to morph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="e2734-656">開始使用：</span><span class="sxs-lookup"><span data-stu-id="e2734-656">Getting Started:</span></span>

- <span data-ttu-id="e2734-657">若要使轉化將兩個物件視為同一個物件，使用者可以使用 [選取窗格] 重新命名圖形。</span><span class="sxs-lookup"><span data-stu-id="e2734-657">To get Morph to treat two objects as the same object, the user can rename the shapes using the Selection Pane.</span></span>
- <span data-ttu-id="e2734-658">名稱前面必須加上「!!」</span><span class="sxs-lookup"><span data-stu-id="e2734-658">The name must be prefaced with “!!”</span></span> <span data-ttu-id="e2734-659">(兩個半形驚嘆號)，例如「!!名稱」，轉化才能用來覆寫預設比對行為</span><span class="sxs-lookup"><span data-stu-id="e2734-659">(two exclamation points) for Morph to use it to override our default matching behavior, e.g. “!!Name”</span></span>
- <span data-ttu-id="e2734-660">使用者可以繼續將圖形重新命名為不是以「!!」為開頭的任何名稱</span><span class="sxs-lookup"><span data-stu-id="e2734-660">Users can continue to rename shapes with any name that doesn’t start with “!!”</span></span> <span data-ttu-id="e2734-661">不必擔心會變更轉化的運作方式</span><span class="sxs-lookup"><span data-stu-id="e2734-661">without worrying that it will change the way Morph works</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="e2734-662">可嘗試使用的範例：</span><span class="sxs-lookup"><span data-stu-id="e2734-662">Scenarios to Try:</span></span>

- <span data-ttu-id="e2734-663">在投影片中插入圖形，讓我們假設是矩形</span><span class="sxs-lookup"><span data-stu-id="e2734-663">Insert a Shape in a slide, let's say Rectangle</span></span>
- <span data-ttu-id="e2734-664">建立新投影片</span><span class="sxs-lookup"><span data-stu-id="e2734-664">Create a new slide</span></span>
- <span data-ttu-id="e2734-665">在第 2 張投影片中插入不同的圖形，讓我們假設是三角形</span><span class="sxs-lookup"><span data-stu-id="e2734-665">Insert a different shape in the 2nd slide, let's say Triangle</span></span>
- <span data-ttu-id="e2734-666">開啟 [選取窗格]，將投影片 1 中的矩形重新命名為「!!圖形」，將投影片 2 中的三角形重新命名為「!!圖形」</span><span class="sxs-lookup"><span data-stu-id="e2734-666">Open SelectionPane, rename the Rectangle in slide 1 to "!!shape", and rename the Triangle in slide 2 to "!!shape"</span></span>
- <span data-ttu-id="e2734-667">將 [轉化] 套用至第 2 張投影片</span><span class="sxs-lookup"><span data-stu-id="e2734-667">Apply Morph on the 2nd slide</span></span>

</BR>

### <a name="morph-transition-enhancements---smartart"></a><span data-ttu-id="e2734-668">轉化轉場增強效果 - SmartArt</span><span class="sxs-lookup"><span data-stu-id="e2734-668">Morph Transition Enhancements - SmartArt</span></span>

<span data-ttu-id="e2734-669">轉場更順暢的 SmartArt 轉化</span><span class="sxs-lookup"><span data-stu-id="e2734-669">SmartArt morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="e2734-670">開始使用：</span><span class="sxs-lookup"><span data-stu-id="e2734-670">Getting Started:</span></span>

<span data-ttu-id="e2734-671">您使用 SmartArt 的方式與轉化相同</span><span class="sxs-lookup"><span data-stu-id="e2734-671">Use Morph the same way you would with SmartArt</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="e2734-672">可嘗試使用的範例：</span><span class="sxs-lookup"><span data-stu-id="e2734-672">Scenarios to Try:</span></span>

- <span data-ttu-id="e2734-673">在投影片中插入 SmartArt</span><span class="sxs-lookup"><span data-stu-id="e2734-673">Insert a SmartArt in a slide</span></span>
- <span data-ttu-id="e2734-674">複製投影片</span><span class="sxs-lookup"><span data-stu-id="e2734-674">Duplicate the Slide</span></span>
- <span data-ttu-id="e2734-675">在複製的投影片上調整大小/變更/移動 SmartArt</span><span class="sxs-lookup"><span data-stu-id="e2734-675">Resize/Change/Move the SmartArt on the duplicated slide</span></span>
- <span data-ttu-id="e2734-676">在複製的投影片上套用 [轉化]</span><span class="sxs-lookup"><span data-stu-id="e2734-676">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="morph-transition-enhancements---tables"></a><span data-ttu-id="e2734-677">轉化轉場增強效果 - 表格​​</span><span class="sxs-lookup"><span data-stu-id="e2734-677">Morph Transition Enhancements - Tables</span></span>

<span data-ttu-id="e2734-678">轉場更順暢的表格轉化</span><span class="sxs-lookup"><span data-stu-id="e2734-678">Tables morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="e2734-679">開始使用：</span><span class="sxs-lookup"><span data-stu-id="e2734-679">Getting Started:</span></span>
<span data-ttu-id="e2734-680">您使用表格的方式與轉化相同</span><span class="sxs-lookup"><span data-stu-id="e2734-680">Use Morph the same way you would with tables</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="e2734-681">可嘗試使用的範例：</span><span class="sxs-lookup"><span data-stu-id="e2734-681">Scenarios to Try:</span></span>

- <span data-ttu-id="e2734-682">在投影片中插入表格</span><span class="sxs-lookup"><span data-stu-id="e2734-682">Insert a Table in a slide</span></span>
- <span data-ttu-id="e2734-683">複製投影片</span><span class="sxs-lookup"><span data-stu-id="e2734-683">Duplicate the slide</span></span>
- <span data-ttu-id="e2734-684">在複製的投影片上調整大小/變更/移動表格</span><span class="sxs-lookup"><span data-stu-id="e2734-684">Resize/Change/Move the Table on the duplicated slide</span></span>
- <span data-ttu-id="e2734-685">在複製的投影片上套用 [轉化]</span><span class="sxs-lookup"><span data-stu-id="e2734-685">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a><span data-ttu-id="e2734-686">Word、Excel、PowerPoint、OneNote、Access、Project、Publisher 和 Visio</span><span class="sxs-lookup"><span data-stu-id="e2734-686">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span></span>

### <a name="seamlessly-switch-between-accounts"></a><span data-ttu-id="e2734-687">在不同帳戶之間順暢切換</span><span class="sxs-lookup"><span data-stu-id="e2734-687">Seamlessly Switch Between Accounts</span></span>

<span data-ttu-id="e2734-688">全新的帳戶管理員會在同一個地方顯示您所有的工作和個人帳戶，讓您能控制在其間切換。</span><span class="sxs-lookup"><span data-stu-id="e2734-688">The new account manager shows all of your work and personal accounts in one place, and puts you in control of switching between them.</span></span> <span data-ttu-id="e2734-689">這項更新的經驗能清楚知道您的登入方法，因此您現在不需要先登出或處理複雜的對話方塊就可以切換工作和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="e2734-689">This updated experience makes it clear how you're logged in, and now you can toggle between work and personal accounts without having to sign out first or deal with complex dialogs.</span></span>


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a><span data-ttu-id="e2734-691">可嘗試使用的範例：</span><span class="sxs-lookup"><span data-stu-id="e2734-691">Scenarios to Try:</span></span>
- <span data-ttu-id="e2734-692">在不同的帳戶之間切換</span><span class="sxs-lookup"><span data-stu-id="e2734-692">Switch between accounts</span></span>
- <span data-ttu-id="e2734-693">新增帳戶 [附註：您可能想要先移至 [檔案] | [帳戶] | [已連線服務]，移除任何已連線至工作帳戶的個人服務或是反向服務]</span><span class="sxs-lookup"><span data-stu-id="e2734-693">Add a new account [Note: you may want to first go to File | Account | Connected Services and remove any personal services connected to work accounts or vice versa]</span></span>
- <span data-ttu-id="e2734-694">登出帳戶</span><span class="sxs-lookup"><span data-stu-id="e2734-694">Sign out from an account</span></span>
</BR>

## <a name="notable-fixes"></a><span data-ttu-id="e2734-695">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="e2734-695">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="e2734-696">Word</span><span class="sxs-lookup"><span data-stu-id="e2734-696">Word</span></span> 
- <span data-ttu-id="e2734-697">我們已修正表格和影像的內容預覽問題</span><span class="sxs-lookup"><span data-stu-id="e2734-697">We fixed an issue with context preview for tables & images</span></span>

### <a name="excel"></a><span data-ttu-id="e2734-698">Excel</span><span class="sxs-lookup"><span data-stu-id="e2734-698">Excel</span></span>
- <span data-ttu-id="e2734-699">我們已修正在黑色佈景主題中，自動篩選的搜尋欄位中文字是白色的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-699">We fixed an issue where text in autofilter Search field is white in Black theme</span></span>
- <span data-ttu-id="e2734-700">我們已修正新 Office 增益集的同意 UI 問題</span><span class="sxs-lookup"><span data-stu-id="e2734-700">We fixed a consent UI issue with New Office Add-in</span></span>

### <a name="powerpoint"></a><span data-ttu-id="e2734-701">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e2734-701">PowerPoint</span></span>
- <span data-ttu-id="e2734-702">我們已修正在膝上型電腦或平板電腦上進行投影片簡報時自動延伸顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="e2734-702">We fixed an issue with automatically extending display when presenting SlideShows on laptops or tablets.</span></span>

### <a name="outlook"></a><span data-ttu-id="e2734-703">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2734-703">Outlook</span></span>
- <span data-ttu-id="e2734-704">我們已修正 [傳送至 OneNote] 按鈕的顯示問題</span><span class="sxs-lookup"><span data-stu-id="e2734-704">We fixed an issue with the Send to OneNote button display</span></span>

### <a name="access"></a><span data-ttu-id="e2734-705">Access</span><span class="sxs-lookup"><span data-stu-id="e2734-705">Access</span></span>
- <span data-ttu-id="e2734-706">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-706">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="e2734-707">Project</span><span class="sxs-lookup"><span data-stu-id="e2734-707">Project</span></span>
- <span data-ttu-id="e2734-708">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-708">Various performance and stability fixes</span></span>


</BR></BR>
## <a name="february-11-2019"></a><span data-ttu-id="e2734-709">2019 年 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="e2734-709">February 11, 2019</span></span>
<span data-ttu-id="e2734-710">版本 1903 (組建 11330.20014)</span><span class="sxs-lookup"><span data-stu-id="e2734-710">Version 1903 (build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="e2734-711">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="e2734-711">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="e2734-712">Word</span><span class="sxs-lookup"><span data-stu-id="e2734-712">Word</span></span> 
- <span data-ttu-id="e2734-713">我們已修正某些自訂樣式無法套用至線上 Word 的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-713">We fixed an issue where some customized styles could not be applied to word online</span></span>
- <span data-ttu-id="e2734-714">我們已修正 Word 中豐富物件的內容預覽問題</span><span class="sxs-lookup"><span data-stu-id="e2734-714">We fixed Context Preview issues with rich objects in Word</span></span>
- <span data-ttu-id="e2734-715">我們已修正貼上清單會導致 Word 當機的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-715">We fixed an issue where pasting lists  would result in Word crashing</span></span>

### <a name="excel"></a><span data-ttu-id="e2734-716">Excel</span><span class="sxs-lookup"><span data-stu-id="e2734-716">Excel</span></span>
- <span data-ttu-id="e2734-717">我們已修正無貨幣符號時，數字格式後的附加空白不再顯示的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-717">We fixed an issue where appended spaces after number formats are no longer showing when there is no currency symbol</span></span>
- <span data-ttu-id="e2734-718">我們已修正自動偵測股票的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-718">We fixed an issue with auto detect for stocks</span></span>

### <a name="powerpoint"></a><span data-ttu-id="e2734-719">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e2734-719">PowerPoint</span></span>
- <span data-ttu-id="e2734-720">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-720">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="e2734-721">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2734-721">Outlook</span></span>
- <span data-ttu-id="e2734-722">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-722">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="e2734-723">Access</span><span class="sxs-lookup"><span data-stu-id="e2734-723">Access</span></span>
- <span data-ttu-id="e2734-724">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-724">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="e2734-725">Project</span><span class="sxs-lookup"><span data-stu-id="e2734-725">Project</span></span>
- <span data-ttu-id="e2734-726">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-726">Various performance and stability fixes</span></span>

</BR></BR>


## <a name="february-1-2019"></a><span data-ttu-id="e2734-727">2019 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="e2734-727">February 1, 2019</span></span> 
<span data-ttu-id="e2734-728">版本 1902 (組建 11326.20000)</span><span class="sxs-lookup"><span data-stu-id="e2734-728">Version 1902 (build 11326.20000)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="e2734-729">值得注意的修正</span><span class="sxs-lookup"><span data-stu-id="e2734-729">Notable Fixes</span></span>

### <a name="word"></a><span data-ttu-id="e2734-730">Word</span><span class="sxs-lookup"><span data-stu-id="e2734-730">Word</span></span> 
- <span data-ttu-id="e2734-731">我們已修正內嵌 Excel 表格中調整儲存格大小的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-731">We fixed an issue with resizing cells in an embedded Excel table</span></span>
- <span data-ttu-id="e2734-732">我們已修正繪圖畫布中複製/貼上圖形的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-732">We fixed an issue with copy/paste of shapes in a Drawing Canvas</span></span>

### <a name="excel"></a><span data-ttu-id="e2734-733">Excel</span><span class="sxs-lookup"><span data-stu-id="e2734-733">Excel</span></span>
- <span data-ttu-id="e2734-734">我們已修正從 Excel Web App 開啟檔案的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-734">We fixed an issue with opening files from the Excel Web app</span></span>
- <span data-ttu-id="e2734-735">我們已修正因為檔名大小造成 CSV 檔案儲存為 XLSX 失敗的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-735">We fixed an issue where saving a CSV file as .XLSX was failing due to file name size</span></span>
- <span data-ttu-id="e2734-736">我們已修正快顯功能表顯示快顯功能表選項的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-736">We fixed the context menu to display the context menu options</span></span>

### <a name="powerpoint"></a><span data-ttu-id="e2734-737">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e2734-737">PowerPoint</span></span>
- <span data-ttu-id="e2734-738">我們已修正使用者無法使用鍵盤快速鍵 ctrl+alt+7/ctrl+alt+8 輸入方括號的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-738">We fixed an issued where users were unable to use the keyboard shortcut ctrl+alt+7/ctrl+alt+8 to enter square brackets</span></span>
- <span data-ttu-id="e2734-739">我們已修正將本機影片插入至 PPT 會減少 C 磁碟機磁碟空間的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-739">We fixed an issue where inserting a local video into the PPT would reduce the ‘C’ drive disk space</span></span>
- <span data-ttu-id="e2734-740">我們已修正 [發佈至 Microsoft Stream] 按鈕無法向某些使用者顯示的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-740">We fixed the Publish to Microsoft Stream button which was not displaying to some users</span></span>

### <a name="outlook"></a><span data-ttu-id="e2734-741">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2734-741">Outlook</span></span>
- <span data-ttu-id="e2734-742">我們已修正行事曆中工作檢視無法正確顯示工作主旨的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-742">We fixed an issue where the task view in calendar was  not correctly showing the task subject</span></span>

### <a name="access"></a><span data-ttu-id="e2734-743">Access</span><span class="sxs-lookup"><span data-stu-id="e2734-743">Access</span></span>
- <span data-ttu-id="e2734-744">我們已修正圖表的縮放比例的問題</span><span class="sxs-lookup"><span data-stu-id="e2734-744">We fixed a scaling issue with charts</span></span>

### <a name="project"></a><span data-ttu-id="e2734-745">Project</span><span class="sxs-lookup"><span data-stu-id="e2734-745">Project</span></span>
- <span data-ttu-id="e2734-746">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="e2734-746">Various performance and stability fixes</span></span>
