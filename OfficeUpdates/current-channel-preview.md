---
title: 版本資訊目前通道 (預覽)
ms.author: anankani
author: v-lislo
manager: anankani
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為「測試人員 - 慢」對象提供新功能、修正或已知問題的最新清單
ms.openlocfilehash: 33fad2b4d91d05abedee0de26c8a0bc101e9c4bd
ms.sourcegitcommit: d4973d351666da9b360f4f83cd588e327ccbab1a
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 12/22/2020
ms.locfileid: "49725772"
---
# <a name="release-notes-for-office-current-channel-preview"></a><span data-ttu-id="8dfbc-103">Office 版本資訊目前通道 (預覽)</span><span class="sxs-lookup"><span data-stu-id="8dfbc-103">Release Notes for Office Current Channel (Preview)</span></span>

<span data-ttu-id="8dfbc-104">本文包含 Windows 電腦版之 Word、Excel、PowerPoint、Outlook、Access、Project 與 Teams 目前通道 (預覽) 組建的版本資訊。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-104">This article contains release notes for Current Channel (Preview) builds of Word, Excel, PowerPoint, Outlook, Access, Project, and Teams for Windows desktop.</span></span> <span data-ttu-id="8dfbc-105">我們每週都強調有趣的新功能、重要修正，以及我們想讓您知道的重大問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="8dfbc-106">請注意，我們通常會在一段時間內推出功能 (有時甚至推出修正程式) 至目前通道 (預覽)。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-106">Note that we often roll out features (and sometimes even fixes) to Current Channel (Preview) over a period of time.</span></span> <span data-ttu-id="8dfbc-107">這樣可讓我們確保功能都運作順利，然後才推出給更廣泛的對象。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="8dfbc-108">所以，如果你沒有看到下面描述的項目，不要擔心你最終會得到它。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="8dfbc-109">我們會變更 Microsoft 365 應用程式的更新通道，包括新增新的更新通道 (每月企業通道)，並變更現有的更新通道名稱。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-109">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="8dfbc-110">如需深入了解，[請閱讀本文](https://go.microsoft.com/fwlink/p/?linkid=2127441)。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-110">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
> - <span data-ttu-id="8dfbc-111">版本資訊發佈日期可能與實際組建發行日期不相符。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-111">The release notes publication date may not match the actual build release date.</span></span>
> - <span data-ttu-id="8dfbc-112">Microsoft Teams 功能可能會與最新的目前通道預覽中發行的功能不同，因為它們的發行頻率較高。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-112">Microsoft Teams features may differ from the latest Current Channel Preview released as they have a more frequent release cadence.</span></span>

[//]: # (請勿移除)

## <a name="version-2012-december-21"></a><span data-ttu-id="8dfbc-114">版本 2012：12 月 21 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-114">Version 2012: December 21</span></span>
<span data-ttu-id="8dfbc-115">*版本 2012 (組建 13530.20218)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-115">*Version 2012 (Build 13530.20218)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="8dfbc-117">功能更新</span><span class="sxs-lookup"><span data-stu-id="8dfbc-117">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="8dfbc-118">Excel</span><span class="sxs-lookup"><span data-stu-id="8dfbc-118">Excel</span></span>

- <span data-ttu-id="8dfbc-119">**將敏感度標籤的相關稽核資料傳送給 M365 系統管理員：** 當使用者套用、變更或移除其檔案和電子郵件上的靈敏度標籤時，Office 會將稽核資料發送到 M365 稽核後端，供系統管理員查看。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-119">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="8dfbc-120">此項幕後功能 (無 UI) 為系統管理員權益。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-120">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="outlook"></a><span data-ttu-id="8dfbc-121">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-121">Outlook</span></span>

- <span data-ttu-id="8dfbc-122">**在連續會議之間置入時間：** 將會議預設為延後 5-10 分鐘開始，讓出席者有時間休息，或前往下一個地點。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-122">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to start 5-10 min late by default.</span></span> [<span data-ttu-id="8dfbc-123">深入了解</span><span class="sxs-lookup"><span data-stu-id="8dfbc-123">Learn more</span></span>](https://support.office.com/article/be84396a-0903-4e25-b31c-1c99ce0dacf2)

- <span data-ttu-id="8dfbc-124">**將敏感度標籤的相關稽核資料傳送給 M365 系統管理員：** 當使用者套用、變更或移除其檔案和電子郵件上的靈敏度標籤時，Office 會將稽核資料發送到 M365 稽核後端，供系統管理員查看。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-124">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="8dfbc-125">此項幕後功能 (無 UI) 為系統管理員權益。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-125">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8dfbc-126">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8dfbc-126">PowerPoint</span></span>

- <span data-ttu-id="8dfbc-127">**將敏感度標籤的相關稽核資料傳送給 M365 系統管理員：** 當使用者套用、變更或移除其檔案和電子郵件上的靈敏度標籤時，Office 會將稽核資料發送到 M365 稽核後端，供系統管理員查看。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-127">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="8dfbc-128">此項幕後功能 (無 UI) 為系統管理員權益。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-128">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="word"></a><span data-ttu-id="8dfbc-129">Word</span><span class="sxs-lookup"><span data-stu-id="8dfbc-129">Word</span></span>

- <span data-ttu-id="8dfbc-130">**將敏感度標籤的相關稽核資料傳送給 M365 系統管理員：** 當使用者套用、變更或移除其檔案和電子郵件上的靈敏度標籤時，Office 會將稽核資料發送到 M365 稽核後端，供系統管理員查看。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-130">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="8dfbc-131">此項幕後功能 (無 UI) 為系統管理員權益。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-131">This is a silent functionality (no UI) for administrator benefit.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-134">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-134">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="8dfbc-135">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8dfbc-135">PowerPoint</span></span>

- <span data-ttu-id="8dfbc-136">我們修正了一個問題，即在 QAT 中新增的字型大小命令在更新時，會自動完成到最接近的已定義字型大小。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-136">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2012-december-14"></a><span data-ttu-id="8dfbc-138">版本2012：12 月 14 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-138">Version 2012: December 14</span></span>
<span data-ttu-id="8dfbc-139">*版本 2012 (組建 13530.20144)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-139">*Version 2012 (Build 13530.20144)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="8dfbc-141">功能更新</span><span class="sxs-lookup"><span data-stu-id="8dfbc-141">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="8dfbc-142">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-142">Outlook</span></span>

- <span data-ttu-id="8dfbc-143">**雲端中的 Outlook 設定：** 選擇您的 Windows 版 Outlook 設定，例如自動回復、焦點收件匣和隱私權，並在任何電腦上使用這些功能。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-143">**Your Outlook settings in the cloud:** Choose your Outlook for Windows settings like Automatic Replies, Focused Inbox, and Privacy, and get to them on any PC.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-146">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-146">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="8dfbc-147">Office 套件</span><span class="sxs-lookup"><span data-stu-id="8dfbc-147">Office Suite</span></span>

- <span data-ttu-id="8dfbc-148">優化的二進位大小。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-148">Optimized binary size.</span></span>


- <span data-ttu-id="8dfbc-149">Anaheim WebView 目前尚不支援 Windows 資訊保護(WIP)。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-149">Anaheim WebView does not support Windows Information Protection (WIP) yet.</span></span> <span data-ttu-id="8dfbc-150">有了此修正程式，Office addin 平臺便會回到處於 WIP 啟用環境中的低層級 WebView。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-150">With this fix Office addin platform falls back to down level WebView in WIP enabled environment.</span></span> <span data-ttu-id="8dfbc-151">根據客戶的電腦環境，這可以是 Edge Spartan WebView 或 Trident WebView。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-151">That can be either Edge Spartan WebView or Trident WebView depending on customer's machine environment.</span></span> <span data-ttu-id="8dfbc-152">兩個低層級 WebViews 皆支援 WIP。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-152">Both down level WebViews support WIP.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2012-december-07"></a><span data-ttu-id="8dfbc-154">版本2012：12 月 7 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-154">Version 2012: December 07</span></span>
<span data-ttu-id="8dfbc-155">*版本 2012 (組建 13530.20064)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-155">*Version 2012 (Build 13530.20064)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="8dfbc-157">功能更新</span><span class="sxs-lookup"><span data-stu-id="8dfbc-157">Feature updates</span></span>

### <a name="teams"></a><span data-ttu-id="8dfbc-158">Teams</span><span class="sxs-lookup"><span data-stu-id="8dfbc-158">Teams</span></span>

- <span data-ttu-id="8dfbc-159">**Teams 現在支援 Windows 原生通知：** 使用者現在可以選取其偏好的通知傳送方式，即透過 Teams 內建橫幅或 Windows 原生橫幅。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-159">**Windows Native Notification are now Supported on Teams:** Users can now select their preferred means of notification delivery, either through Teams built-in banners or the Windows native banners.</span></span>


- <span data-ttu-id="8dfbc-160">**Citrix 與 VMWare VDI 的 Teams 會議 2X2 圖庫檢視：** Teams 用戶端在 VDI 最佳化模式中時，Teams 的 VDI 2x2 圖庫檢視功能會啟用，可讓您在 2x2 圖庫中檢視 Citrix、VMWare 之 VDI 用戶端的最多四個出席者影片。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-160">**Teams Meetings 2x2 Gallery View in Citrix and VMWare VDI:** Teams on VDI 2x2 Gallery View feature will enable to view up to four attendees videos in 2x2 Gallery View on VDI clients from Citrix, VMWare when Teams client in VDI optimized mode.</span></span>


- <span data-ttu-id="8dfbc-161">**會議反應：**  會議反應是在會議中互動的新方式。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-161">**Meeting Reactions:**  Meeting reactions are a new way to interact in meetings.</span></span> <span data-ttu-id="8dfbc-162">參與者可以傳送以時間列表顯示的反應，其出現的地點為正在共用的內容上，以及有在會議階段上顯示之傳送反應的個人上。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-162">Participants can send reactions which are shown as a stream on content that is being shared, and on the individual who sent the reaction if they're displayed on the meeting stage.</span></span> 


- <span data-ttu-id="8dfbc-163">**Web 會議的共聚模式和大型圖庫** 大型圖庫可讓您一次看到最多 49 個其他人員的影片。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-163">**Together Mode and Large Gallery for Web Meetings** Large Gallery enables you to see the videos of up to 49 other people at once.</span></span> <span data-ttu-id="8dfbc-164">當至少 10 人開啟相機時，即可使用此選項。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-164">This option is available when at least ten people have their cameras turned on.</span></span> <span data-ttu-id="8dfbc-165">共聚模式可讓您感覺與會議中每個人處於相同的共用空間。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-165">Together mode lets you feel like you're in the same shared space with everyone in the meeting.</span></span> <span data-ttu-id="8dfbc-166">當會議中至少有五個人時，即可使用共聚模式。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-166">Together mode is available when there are at least five people in the meeting.</span></span> 


- <span data-ttu-id="8dfbc-167">**通話合併** 通話合併可讓使用者將其撥打的新通話，或新來電合併到其 1 對 1 或群組通話中。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-167">**Call Merge** Call Merge allows users to merge a new call they place, or a new incoming call, into their 1-1 or group call.</span></span> <span data-ttu-id="8dfbc-168">這適用於Teams VOIP 通話和 PSTN 通話。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-168">This applies to Teams VOIP calls and PSTN calls.</span></span> 


### <a name="visio"></a><span data-ttu-id="8dfbc-169">Visio</span><span class="sxs-lookup"><span data-stu-id="8dfbc-169">Visio</span></span>

- <span data-ttu-id="8dfbc-170">**新 Azure 樣板和圖案：** 我們新增了更多的樣板來協助您建立最新的 Azure 圖表。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-170">**New Azure stencils and shapes:** We've added many more stencils to help you create up-to-date Azure diagrams.</span></span> [<span data-ttu-id="8dfbc-171">深入了解</span><span class="sxs-lookup"><span data-stu-id="8dfbc-171">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-174">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-174">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="8dfbc-175">Excel</span><span class="sxs-lookup"><span data-stu-id="8dfbc-175">Excel</span></span>

- <span data-ttu-id="8dfbc-176">我們已修正部分功能區元素未以簡體中文進行當地語系化的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-176">We fixed an issue where some Ribbon elements were not localized in Simplified Chinese.</span></span>


- <span data-ttu-id="8dfbc-177">我們已修正更新時 Excel 意外終止的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-177">We fixed an issue where Excel terminated unexpectedly when updating.</span></span>


- <span data-ttu-id="8dfbc-178">我們已修正從 OneDrive 本機同步處理資料夾插入檔案時，[插入物件] 命令沒有顯示正確圖示的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-178">We fixed an issue where the Insert Object command does not show the correct icon when inserting a file from OneDrive local sync folder.</span></span>


- <span data-ttu-id="8dfbc-179">修正了在覆寫模式下編輯時，使用需要使用 IME 的語言進行編輯時表現不佳的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-179">Fixed an issue where editing in languages that require use of IME would behave poorly when editing in overwrite mode.</span></span>


- <span data-ttu-id="8dfbc-180">已修正此問題：一些使用者在共同撰寫時會錯誤地看到通知他們檔案新版本的訊息列。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-180">Fixed an issue where some users would incorrectly see a message bar informing them of a new version of a file when coauthoring.</span></span>


- <span data-ttu-id="8dfbc-181">修正了在公式檢視中複製和貼上資料時 Excel 意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-181">Fixed an issue where Excel would close unexpectedly when copying and pasting data in formula view.</span></span>


- <span data-ttu-id="8dfbc-182">修正了在自動儲存被停用時通知中説明文章的斷開連結。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-182">Fixed a broken hyperlink to a help article in an alert in case Autosave becomes disabled.</span></span>


- <span data-ttu-id="8dfbc-183">我們修正了以下問題：當 Excel 以某些語言執行時輸入資料可能導致 Excel 停止運作。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-183">We fixed an issue where when entering data while Excel is running in certain languages could cause Excel to stop working.</span></span>


- <span data-ttu-id="8dfbc-184">此變更解决了在方程式中正確顯示字型的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-184">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="8dfbc-185">這修正了Power Pivot 無法正確導入定位字元分隔的文字檔的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-185">This fixes an issue where Power Pivot wasn't able to correctly import a tab-delimited text file.</span></span>


### <a name="outlook"></a><span data-ttu-id="8dfbc-186">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-186">Outlook</span></span>

- <span data-ttu-id="8dfbc-187">我們已修正會導致「收件者:」欄位在工作狀態報告中空白的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-187">We fixed an issue that caused the To: field to be blank in task status reports.</span></span>


- <span data-ttu-id="8dfbc-188">我們已修正導致 MailItem.BeforeAttachmentAdd 事件中斷的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-188">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="8dfbc-189">我們修正了導致使用者在從 Outlook 以外的應用程式傳送 Outlook 郵件時遇到一些問題的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-189">We fixed an issue that was causing users to experience some issues when sending Outlook mail from applications other than Outlook.</span></span>


- <span data-ttu-id="8dfbc-190">我們修正了導致 SmartLinks 在儲存至草稿時丟失其格式的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-190">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


- <span data-ttu-id="8dfbc-191">我們已修正將附件新增到從 zip 檔案開啟的郵件時會失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-191">We fixed and issue where adding an attachment to a message opened from a zip file would fail.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="8dfbc-192">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8dfbc-192">PowerPoint</span></span>

- <span data-ttu-id="8dfbc-193">已修正從 Word 到 PowerPoint 複製/貼上方程式時發生的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-193">Fixed an issue with copy/paste of an equation from Word to Powerpoint</span></span>


- <span data-ttu-id="8dfbc-194">此變更解決筆跡分析期間發生的超時問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-194">This change addresses an issue related to timeouts experienced during ink analysis.</span></span>


- <span data-ttu-id="8dfbc-195">此變更解決建立動畫 GIF 使用者介面中的語法錯誤。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-195">This change addresses a grammatical error in the Create an Animated GIF user interface.</span></span>


- <span data-ttu-id="8dfbc-196">此變更解决對某些幾何圖形套用 [合併圖案] 作業時路徑填充的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-196">This change addresses an issue with path fills when applying Merge Shapes operations with certain geometries.</span></span>


- <span data-ttu-id="8dfbc-197">此變更解决了在方程式中正確顯示字型的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-197">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="8dfbc-198">此變更解決了處理載入影片期間可能發生錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-198">This change addresses an issue with handling errors that may occur during video loading.</span></span>


- <span data-ttu-id="8dfbc-199">我們已修正 Slide.Shapes.AddMediaObject2 會對舊版影片格式 (MPG-1、Mpeg-2) 發生當機的 VBA 問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-199">We fixed a VBA issue where Slide.Shapes.AddMediaObject2 crashing with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="8dfbc-200">我們修正了一個問題，即未知的共同作者的狀態指示器在有關於共同作者的更多資訊可用時沒有完全重新整理。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-200">We fixed an issue where an unknown coauthor's presence indicator does not get completely refreshed when more information about the coauthor is available.</span></span>


- <span data-ttu-id="8dfbc-201">修正了當投影片檢視的大小在尺規開啟時被解除引用的 null 指標。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-201">Fixed a null pointer being dereferenced when slide view is resized with ruler turned on.</span></span>


- <span data-ttu-id="8dfbc-202">已修正無法正確開啟部分損壞的 PowerPoint 檔案 (即使在文件修復之後) 的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-202">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="project"></a><span data-ttu-id="8dfbc-203">Project</span><span class="sxs-lookup"><span data-stu-id="8dfbc-203">Project</span></span>

- <span data-ttu-id="8dfbc-204">我們已修正預期使用者開啟的專案應已儲存更新的資訊，但發現遺漏更新的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-204">We fixed an issue where users open projects which have supposedly been saved with updated information, but find the updates are is missing.</span></span>


- <span data-ttu-id="8dfbc-205">我們已修正若交付項目相關聯的 SharePoint 網站已不再存在時，無法刪除交付項目的相依性的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-205">We fixed an issue where you couldn't delete dependencies on the deliverables if the SharePoint site the deliverable was associated with no longer existed.</span></span>


- <span data-ttu-id="8dfbc-206">已修正開啟具有大量資源的專案時所花費的時間很長的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-206">Fixed an issue where opening a project with a lot of resources was taking a long time.</span></span>


- <span data-ttu-id="8dfbc-207">已修正使用者可能會看到多個未指派工作分派與任務相關聯的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-207">Fixed an issue where users may see multiple unassigned assignments associated with a task.</span></span>


- <span data-ttu-id="8dfbc-208">已修正在大型專案中，輸入任務名稱的速度可能非常緩慢的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-208">Fixed an issue where in large projects it can be very slow to enter a task name.</span></span>


- <span data-ttu-id="8dfbc-209">已修正如果特定專案在負載的特定部分發生問題，可能會開啟特定專案的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-209">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>


### <a name="word"></a><span data-ttu-id="8dfbc-210">Word</span><span class="sxs-lookup"><span data-stu-id="8dfbc-210">Word</span></span>

- <span data-ttu-id="8dfbc-211">貼上為純文字通常優於貼上為 RTF 文字。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-211">Paste as plain text is often preferred to pasting as rich text.</span></span> <span data-ttu-id="8dfbc-212">此快顯功能表修正功能可讓使用者貼上純文字格式。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-212">This context menu fix allows the user to paste as plain text.</span></span> <span data-ttu-id="8dfbc-213">否則，使用者必須複製至純文字編輯器 (如 [記事本])，然後從 [記事本] 複製到所要的目標應用程式</span><span class="sxs-lookup"><span data-stu-id="8dfbc-213">Else the user would have to copy into a plain-text editor like Notepad and then copy from Notepad into the desired target app</span></span>


- <span data-ttu-id="8dfbc-214">已修正從 Word 到 PowerPoint 複製/貼上方程式時發生的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-214">Fixed an issue with copy/paste of an equation from Word to Powerpoint</span></span>


- <span data-ttu-id="8dfbc-215">此變更解決編輯檔時游標的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-215">This change addresses an issue with the cursor when editing a document.</span></span>


- <span data-ttu-id="8dfbc-216">我們已修正在縮放圖片時，圖片變得模糊的相關問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-216">We fixed an issue related to pictures becoming blurry while zooming.</span></span>


- <span data-ttu-id="8dfbc-217">我們已修正長超連結被截斷的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-217">We fixed an issue where long hyperlinks were getting truncated.</span></span>


### <a name="office-suite"></a><span data-ttu-id="8dfbc-218">Office 套件</span><span class="sxs-lookup"><span data-stu-id="8dfbc-218">Office Suite</span></span>

- <span data-ttu-id="8dfbc-219">Office 套件已修復此問題：在某些較舊的版本上安裝較新版的 Office 時，可能會造成功能受損 (例如由於遺失登錄專案而無法使用 Power Query)。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-219">Office Suite Fixed an issue where installing a newer version of Office over certain older versions can result in impaired functionality (such as being unable to use Power Query) due to missing registry entries.</span></span>



[//]: # (請勿移除 BUGDETAILS 內容尾)

## <a name="version-2011-december-01"></a><span data-ttu-id="8dfbc-221">版本2011：12 月1 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-221">Version 2011: December 01</span></span>
<span data-ttu-id="8dfbc-222">*版本 2011 (組建 13426.20306)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-222">*Version 2011 (Build 13426.20306)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="8dfbc-224">功能更新</span><span class="sxs-lookup"><span data-stu-id="8dfbc-224">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="8dfbc-225">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-225">Outlook</span></span>

- <span data-ttu-id="8dfbc-226">**每個線上會議：** 使用新設定將所有會議預設設定為線上，讓您輕鬆安排線上會議。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-226">**Every meeting online:** Make it easier to schedule online meetings with a new setting to make all your meetings online by default.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-229">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-229">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="8dfbc-230">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-230">Outlook</span></span>

- <span data-ttu-id="8dfbc-231">我們修正了導致某些會議的原始出席者在另一個出席者轉寄會議時收到取消通知的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-231">We fixed an issue that caused the original attendees of some meetings to receive a cancellation when another attendee forwards the meeting.</span></span>


- <span data-ttu-id="8dfbc-232">我們修正了導致某些使用者未設定一或多個簽章時，在 [簽名] 下拉式清單中看不到任何簽名的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-232">We fixed an issue that caused some users to see no signatures in the signatures drop down despite having one or more signatures configured.</span></span>


### <a name="project"></a><span data-ttu-id="8dfbc-233">Project</span><span class="sxs-lookup"><span data-stu-id="8dfbc-233">Project</span></span>

- <span data-ttu-id="8dfbc-234">已修正如果特定專案在負載的特定部分發生問題，可能會開啟特定專案的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-234">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>



[//]: # (請勿移除 BUGDETAILS 內容尾)

## <a name="version-2011-november-24"></a><span data-ttu-id="8dfbc-236">版本 2011：11 月 24 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-236">Version 2011: November 24</span></span>
<span data-ttu-id="8dfbc-237">*版本 2011 (組建 13426.20294)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-237">*Version 2011 (Build 13426.20294)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-239">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-239">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="8dfbc-240">Office 套件</span><span class="sxs-lookup"><span data-stu-id="8dfbc-240">Office Suite</span></span>

- <span data-ttu-id="8dfbc-241">已修正從 Word 到 PowerPoint 複製/貼上方程式時發生的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-241">Fixed an issue with copy/paste of an equation from Word to Powerpoint</span></span>



[//]: # (請勿移除 BUGDETAILS 內容尾)

## <a name="version-2011-november-21"></a><span data-ttu-id="8dfbc-243">版本 2011：11 月 21 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-243">Version 2011: November 21</span></span>
<span data-ttu-id="8dfbc-244">*版本 2011 (組建 13426.20274)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-244">*Version 2011 (Build 13426.20274)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="8dfbc-246">功能更新</span><span class="sxs-lookup"><span data-stu-id="8dfbc-246">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="8dfbc-247">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8dfbc-247">PowerPoint</span></span>

- <span data-ttu-id="8dfbc-248">**影片庫：** 在應用程式內使用精選的免版稅影片素材庫來提升您的文件</span><span class="sxs-lookup"><span data-stu-id="8dfbc-248">**Video Library:** Elevate your documents with a library of curated, royalty-free video footage available in-app</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-251">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-251">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="8dfbc-252">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-252">Outlook</span></span>

- <span data-ttu-id="8dfbc-253">已修正導致 MailItem.BeforeAttachmentAdd 事件中斷的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-253">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="8dfbc-254">我們新增了一個 RegKey，可讓客戶停用 IDataObject 操作 (例如，拖曳拖放、剪貼簿) 中附件的 FileTime 包含內容。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-254">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span> <span data-ttu-id="8dfbc-255">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-255">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span></span> <span data-ttu-id="8dfbc-256">REG_DWORD IncludeFileTimesInDataObject。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-256">REG_DWORD IncludeFileTimesInDataObject.</span></span> <span data-ttu-id="8dfbc-257">0 = 不包含 filetimes。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-257">0 = filetimes are excluded.</span></span> <span data-ttu-id="8dfbc-258">1 = (預設) 包含 filetimes</span><span class="sxs-lookup"><span data-stu-id="8dfbc-258">1 = (default) filetimes are included</span></span>


- <span data-ttu-id="8dfbc-259">我們修正了當回復含有「Azure 資訊保護」保護標籤的郵件時，會導致內嵌影像消失的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-259">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>



[//]: # (請勿移除 BUGDETAILS 內容尾)

## <a name="version-2011-november-18"></a><span data-ttu-id="8dfbc-261">版本 2011：11 月 18 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-261">Version 2011: November 18</span></span>
<span data-ttu-id="8dfbc-262">*版本 2011 (組建 13426.20250)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-262">*Version 2011 (Build 13426.20250)*</span></span>
* <span data-ttu-id="8dfbc-263">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-263">Various bugs and performance fixes.</span></span>

## <a name="version-2011-november-16"></a><span data-ttu-id="8dfbc-264">版本 2011：10 月 16 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-264">Version 2011: November 16</span></span>
<span data-ttu-id="8dfbc-265">*版本 2011 (組建 13426.20234)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-265">*Version 2011 (Build 13426.20234)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="8dfbc-267">功能更新</span><span class="sxs-lookup"><span data-stu-id="8dfbc-267">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="8dfbc-268">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-268">Outlook</span></span>

- <span data-ttu-id="8dfbc-269">**所有裝置都有相同的簽章：** 在雲端中儲存簽章。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-269">**Same signature, all devices:** Your signature is stored in the cloud.</span></span> <span data-ttu-id="8dfbc-270">只要建立一次，就能在所有使用 Outlook 的位置使用。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-270">Create it once and use it everywhere you use Outlook.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-273">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-273">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="8dfbc-274">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-274">Outlook</span></span>

- <span data-ttu-id="8dfbc-275">我們修正了傳送任務中的狀態報表時，導致 [收件者] 欄位為空白的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-275">We fixed an issue that caused the To field to be blank when sending a status report on a task.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="8dfbc-276">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8dfbc-276">PowerPoint</span></span>

- <span data-ttu-id="8dfbc-277">我們修正了 Slide.Shapes.AddMediaObject2 會對舊版影片格式 (MPG-1、Mpeg-2) 發生當機的 VBA 問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-277">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 crashing with legacy video formats (MPG-1,Mpeg-2).</span></span>



[//]: # (請勿移除 BUGDETAILS 內容尾)

## <a name="version-2011-november-09"></a><span data-ttu-id="8dfbc-279">版本 2011：11 月 9 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-279">Version 2011: November 09</span></span>
<span data-ttu-id="8dfbc-280">*版本 2011 (組建 13426.20184)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-280">*Version 2011 (Build 13426.20184)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="8dfbc-282">功能更新</span><span class="sxs-lookup"><span data-stu-id="8dfbc-282">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="8dfbc-283">Excel</span><span class="sxs-lookup"><span data-stu-id="8dfbc-283">Excel</span></span>

- <span data-ttu-id="8dfbc-284">**從查詢建立 Power Platform 資料流程：** 您現在可以將查詢匯出至 Power Query 範本，以建立新的 Power Platform 資料流程</span><span class="sxs-lookup"><span data-stu-id="8dfbc-284">**Create Power Platform dataflows from queries:** You can now export your queries into Power Query templates that can be used to create new Power Platform dataflows</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-287">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-287">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="8dfbc-288">存取</span><span class="sxs-lookup"><span data-stu-id="8dfbc-288">Access</span></span>

- <span data-ttu-id="8dfbc-289">修正某些使用者在嘗試從其同步處理的 OneDrive 資料夾匯出査詢時看到「系統資源滿載」錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-289">We fixed an issue where some users were seeing the "system resource exceeded" error when they tried to export a query from their synced OneDrive folder.</span></span>


- <span data-ttu-id="8dfbc-290">我們已修正表單視窗之間發生「自動」切換而切換到另一個表單的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-290">We fixed an issue where 'auto'-switching between form windows was switching to another form.</span></span>


- <span data-ttu-id="8dfbc-291">我們已修正從非 Office 應用程式使用 DAO 時，會導致應用程式意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-291">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


### <a name="excel"></a><span data-ttu-id="8dfbc-292">Excel</span><span class="sxs-lookup"><span data-stu-id="8dfbc-292">Excel</span></span>

- <span data-ttu-id="8dfbc-293">我們已修正啟用 SaveAs 作業與 COM 增益集之後，檔案名稱未變更的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-293">We fixed an issue where Filename was not changing after a SaveAs operation with COM add-ins enabled.</span></span>


- <span data-ttu-id="8dfbc-294">修正 Power Pivot 使用 Oracle 資料庫連線時的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-294">Fixed an issue with Power Pivot when using a connection to an Oracle database.</span></span>


- <span data-ttu-id="8dfbc-295">我們已修正當 Excel 資料模型中有錯誤的度量定義時，自動儲存會失敗且顯示錯誤/令人誤解的錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-295">We fixed an issue when Auto-Save fails with incorrect/misleading error message when there's a bad measure definition in the Excel data model.</span></span>


- <span data-ttu-id="8dfbc-296">我們已修正觸發 MTR 計算和群組原則物件更新 (例如，透過遠端群組原則重新整理) 的處理序時，Excel 異常終止的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-296">We fixed an issue where Excel terminated unexpectedly when the process of MTR calc and Group Policy Object update (e.g. via Remote Group Policy Refresh) was triggered.</span></span>


- <span data-ttu-id="8dfbc-297">我們已修正使用者無法直接從 SharePoint 開啟 atomsvc (UTF8+BOM) 檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-297">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="8dfbc-298">我們修正了放大和縮小簡報區域會造成縮放選取選框和滑鼠指標之間的間隙的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-298">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


- <span data-ttu-id="8dfbc-299">我們已修正將 Excel 活頁簿插入 Word 文件時，Word 似乎停止回應的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-299">We fixed an issue where Word appears to hang when inserting an Excel workbook into a Word document.</span></span>


### <a name="outlook"></a><span data-ttu-id="8dfbc-300">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-300">Outlook</span></span>

- <span data-ttu-id="8dfbc-301">解決在新增或儲存附件時，會導致 Outlook 偶爾停止運作的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-301">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


- <span data-ttu-id="8dfbc-302">我們已修正快速列印影像附件導致錯誤的問題，錯誤為：「Windows 找不到此圖片。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-302">We fixed an issue where quick print for image attachments resulted in error, "Windows can't find this picture.</span></span> <span data-ttu-id="8dfbc-303">請檢查位置，然後再試一次」。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-303">Check the location, and then try again".</span></span>


- <span data-ttu-id="8dfbc-304">我們已修正導致某些使用者看到 Outlook 在離線狀態下啟動，直到他們手動選擇線上工作的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-304">We fixed an issue that caused some users to see Outlook start in an Offline state until they manually chose to work online.</span></span>


- <span data-ttu-id="8dfbc-305">我們已修正將從會議位置複製的 URL 貼上到其他位置 (例如瀏覽器) 時，URL 的結尾會包含分號的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-305">We fixed an issue when pasting a URL copied from meeting location to somewhere else (such as a browser), the URL contains a semicolon at the end.</span></span>


- <span data-ttu-id="8dfbc-306">我們已修正使用者無法在 [基本驗證] 中刪除 Microsoft 365 群組行事曆約會的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-306">We fixed an issue where users were unable to delete appointments in Calendar of Microsoft 365 Groups in Basic Auth.</span></span>


- <span data-ttu-id="8dfbc-307">我們已修正載入暱稱快取時啟動 Outlook 失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-307">We fixed an issue where starting Outlook failed while loading nickname cache.</span></span>


- <span data-ttu-id="8dfbc-308">我們已修正信箱擁有者無法管理自己行事曆的共用權限的問題，因為該選項呈現灰色停用狀態。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-308">We fixed an issue where a mailbox owner wasn't able to manage Shared permission for their own Calendar as the option was greyed out.</span></span>


- <span data-ttu-id="8dfbc-309">我們已修正 Outlook 無法使用受限制的權限建立郵件的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-309">We fixed an issue where Outlook was not able to create a message with restricted permission.</span></span>


- <span data-ttu-id="8dfbc-310">我們已修正將電子郵件範本儲存為 .OFT 時，會將中文字元變更為問號的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-310">We fixed an issue where saving email templates as .OFT changed Chinese characters to question marks.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="8dfbc-311">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8dfbc-311">PowerPoint</span></span>

- <span data-ttu-id="8dfbc-312">我們已修正放大和縮小簡報會造成縮放選取跑馬燈和滑鼠指標之間間隙的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-312">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


- <span data-ttu-id="8dfbc-313">我們已修正 [圖片] 旁的內容預留位置圖示沒有工具提示的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-313">We fixed an issue where in content placeholder icon next to Pictures didn't have a tooltip.</span></span>


- <span data-ttu-id="8dfbc-314">我們已修正 pptsx 檔案所顯示的投影片放映之受保護檢視，允許受 IRM 保護的文件螢幕擷取的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-314">We have fixed an issue where Protected view of slide show, shown by pptsx file, allows screen capture of IRM protected document.</span></span>


- <span data-ttu-id="8dfbc-315">我們已修正關閉設計窗格時，投影片的格線移位的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-315">We fixed an issue where grid lines were getting shifted from slides when closing design pane.</span></span>


- <span data-ttu-id="8dfbc-316">我們已修正將投影片放映複製到次要監視器時，投影片可能會隱藏在其他視窗後面的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-316">We fixed an issue when duplicating slideshow to secondary monitor, the slideshow may hide behind other window.</span></span>


- <span data-ttu-id="8dfbc-317">我們已修正投影片在選取項目窗格開啟的情況下停止螢幕錄製後，投影片中的捲軸會自行開始調整的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-317">We fixed an issue where the scroll bar in the slide starts adjusting itself after stopping screen recording with selection pane opened.</span></span>


### <a name="project"></a><span data-ttu-id="8dfbc-318">Project</span><span class="sxs-lookup"><span data-stu-id="8dfbc-318">Project</span></span>

- <span data-ttu-id="8dfbc-319">已修正如果 [工作表單] 類型檢視中的延遲變更，ProjectBeforeTaskChagne 事件中的 NewVal 值不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-319">Fixed an issue where the NewVal in the ProjectBeforeTaskChagne event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


- <span data-ttu-id="8dfbc-320">我們已修正在開啟以特定方式指定資源分佈的檔案時，Project 可能會意外終止的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-320">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>


- <span data-ttu-id="8dfbc-321">已修正當您將專案從 PWA 儲存到本機 mpp 檔案時，會針對實際上使用者未變更的資料觸發 ProjectBeforeTaskChangeEvent 的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-321">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="8dfbc-322">已修正資源預訂依名稱 (而不是 GUID) 搜尋資源時，如果有多個名稱相同的資源，會導致問題的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-322">Fixed an issue where resource engagements searched for a resource by name instead of GUID which would cause issues if there were multiple resources with the same name.</span></span>


- <span data-ttu-id="8dfbc-323">已修正如果您在專案網站中有工作清單並將工作清單分組，您將無法快速編輯工作清單的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-323">Fixed an issue where if you have a task list in a project site and group the task list, you will not be able to quick edit the task list.</span></span>


- <span data-ttu-id="8dfbc-324">已修正如果您透過 CSOM 更新企業資源，可能會遺失資源最大單位。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-324">Fixed an issue where if you update an enterprise resource via CSOM, resource max units may be lost.</span></span>


### <a name="word"></a><span data-ttu-id="8dfbc-325">Word</span><span class="sxs-lookup"><span data-stu-id="8dfbc-325">Word</span></span>

- <span data-ttu-id="8dfbc-326">我們修正了放大和縮小簡報區域會造成縮放選取選框和滑鼠指標之間的間隙的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-326">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


- <span data-ttu-id="8dfbc-327">我們已修正按一下註解提示時，註解提示不會放大以在檢視中顯示註解卡片的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-327">We fixed an issue where clicking comment hint didn't zoom out to show comment card in view.</span></span>


- <span data-ttu-id="8dfbc-328">我們已修正欄位之間的線條可能已移位的版面配置問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-328">We fixed a layout issue which the line between columns might have shifted.</span></span>


- <span data-ttu-id="8dfbc-329">我們已修正有時開啟 Word 文件可能會顯示錯誤對話方塊的追蹤修訂問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-329">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>


- <span data-ttu-id="8dfbc-330">我們已修正將 Excel 活頁簿插入 Word 文件時，Word 似乎停止回應的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-330">We fixed an issue where Word appears to hang when inserting an Excel workbook into a Word document.</span></span>


- <span data-ttu-id="8dfbc-331">我們已修正套用具有浮水印的敏感度標籤時的列印問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-331">We fixed a print issue when sensitivity label with watermarks are applied.</span></span>


### <a name="office-suite"></a><span data-ttu-id="8dfbc-332">Office 套件</span><span class="sxs-lookup"><span data-stu-id="8dfbc-332">Office Suite</span></span>

- <span data-ttu-id="8dfbc-333">我們修正了 Office 部署工具中的一個問題，該問題是，在 Microsoft Office 2007 [Microsoft 應用程式錯誤回報工具] 產品存在的情況下使用 RemoveMSI 功能時設定失敗。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-333">We fixed an issue in the Office Deployment Tool where configuration was failing when using the RemoveMSI feature with the Office 2007 "Microsoft Application Error Reporting" product present.</span></span>


- <span data-ttu-id="8dfbc-334">我們已修正 SSO API 互動式登入傳回錯誤碼的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-334">We fixed an issue where SSO API interactive Sign-In was returning an error code.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2010-november-06"></a><span data-ttu-id="8dfbc-336">版本 2010：11 月 6 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-336">Version 2010: November 06</span></span>
<span data-ttu-id="8dfbc-337">*版本 2010 (組建 13328.20356)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-337">*Version 2010 (Build 13328.20356)*</span></span>
* <span data-ttu-id="8dfbc-338">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-338">Various bugs and performance fixes.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)



[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2010-november-04"></a><span data-ttu-id="8dfbc-341">版本 2010：11 月 04 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-341">Version 2010: November 04</span></span>
<span data-ttu-id="8dfbc-342">*版本 2010 (組建 13328.20340)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-342">*Version 2010 (Build 13328.20340)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="8dfbc-344">功能更新</span><span class="sxs-lookup"><span data-stu-id="8dfbc-344">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="8dfbc-345">Excel</span><span class="sxs-lookup"><span data-stu-id="8dfbc-345">Excel</span></span>

- <span data-ttu-id="8dfbc-346">**SVG 剪貼簿支援：** 您現在可以將 SVG 內容從 Office 貼上協力廠商應用程式。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-346">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="8dfbc-347">深入了解</span><span class="sxs-lookup"><span data-stu-id="8dfbc-347">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="outlook"></a><span data-ttu-id="8dfbc-348">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-348">Outlook</span></span>

- <span data-ttu-id="8dfbc-349">**SVG 剪貼簿支援：** 您現在可以將 SVG 內容從 Office 貼上協力廠商應用程式。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-349">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="8dfbc-350">深入了解</span><span class="sxs-lookup"><span data-stu-id="8dfbc-350">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="powerpoint"></a><span data-ttu-id="8dfbc-351">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8dfbc-351">PowerPoint</span></span>

- <span data-ttu-id="8dfbc-352">**SVG 剪貼簿支援：** 您現在可以將 SVG 內容從 Office 貼上協力廠商應用程式。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-352">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="8dfbc-353">深入了解</span><span class="sxs-lookup"><span data-stu-id="8dfbc-353">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)<br /><span data-ttu-id="8dfbc-354">在[部落格文章](https://insider.office.com/zh-TW/blog/svg-content-office-third-party-apps)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8dfbc-354">See details in [blog post](https://insider.office.com/zh-TW/blog/svg-content-office-third-party-apps)</span></span>

- <span data-ttu-id="8dfbc-355">**使用透明背景建立 GIF：** 當匯出成動畫 GIF 時，您可以使用新選項讓背景變透明。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-355">**Create GIFs with Transparent Backgrounds:** When exporting to an Animated GIF, a new option will allow you to make the background transparent.</span></span><br /><span data-ttu-id="8dfbc-356">在[部落格文章](https://insider.office.com/zh-TW/blog/export-animated-gifs-transparent-backgrounds)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8dfbc-356">See details in [blog post](https://insider.office.com/zh-TW/blog/export-animated-gifs-transparent-backgrounds)</span></span>

- <span data-ttu-id="8dfbc-357">**匯出一定範圍內的動畫 GIF** 在匯出成動畫 GIF 時，選取投影片的範圍</span><span class="sxs-lookup"><span data-stu-id="8dfbc-357">**Export animated GIF in a range:** Select a range of slides when exporting to animated GIF</span></span>

### <a name="word"></a><span data-ttu-id="8dfbc-358">Word</span><span class="sxs-lookup"><span data-stu-id="8dfbc-358">Word</span></span>

- <span data-ttu-id="8dfbc-359">**SVG 剪貼簿支援：** 您現在可以將 SVG 內容從 Office 貼上協力廠商應用程式。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-359">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="8dfbc-360">深入了解</span><span class="sxs-lookup"><span data-stu-id="8dfbc-360">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-363">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-363">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="8dfbc-364">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-364">Outlook</span></span>

- <span data-ttu-id="8dfbc-365">我們已修正導致使用者無法將 [編輯器] 權限授與代理人的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-365">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


### <a name="office-suite"></a><span data-ttu-id="8dfbc-366">Office 套件</span><span class="sxs-lookup"><span data-stu-id="8dfbc-366">Office Suite</span></span>

- <span data-ttu-id="8dfbc-367">我們已修正在嘗試儲存已從 syncbacked 檔案轉換為僅限伺服器的檔案時，導致失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-367">We fixed an issue that was causing a failure when trying to save files that have transitioned from syncbacked to server-only.</span></span>



[//]: # (請勿移除 BUGDETAILS 內容尾)

## <a name="version-2010-october-27"></a><span data-ttu-id="8dfbc-369">版本 2010：10 月 27 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-369">Version 2010: October 27</span></span>
<span data-ttu-id="8dfbc-370">*版本 2010 (組建 13328.20292)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-370">*Version 2010 (Build 13328.20292)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-374">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-374">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="8dfbc-375">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-375">Outlook</span></span>

- <span data-ttu-id="8dfbc-376">我們已修正會導致預設不會為使用者開啟雲端設定的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-376">We fixed a n issue that caused Cloud Settings not to be turned on for users by default.</span></span>


- <span data-ttu-id="8dfbc-377">我們已修正會導致對使用者簽章的變更無法儲存的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-377">We fixed an issue that caused changes to a user's signature to fail to save.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2010-october-24"></a><span data-ttu-id="8dfbc-379">版本 2010：10 月 24 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-379">Version 2010: October 24</span></span>
<span data-ttu-id="8dfbc-380">*版本 2010 (組建 13328.20278)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-380">*Version 2010 (Build 13328.20278)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)



[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-384">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-384">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="8dfbc-385">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-385">Outlook</span></span>

- <span data-ttu-id="8dfbc-386">我們已修正在回覆或轉寄時，會導致中文郵件標題無法閱讀的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-386">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


- <span data-ttu-id="8dfbc-387">我們已修正在儲存為 OFT 檔案時，會導致中文字元變更為問號的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-387">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


### <a name="project"></a><span data-ttu-id="8dfbc-388">Project</span><span class="sxs-lookup"><span data-stu-id="8dfbc-388">Project</span></span>

- <span data-ttu-id="8dfbc-389">修正當您將專案從 PWA 儲存到本機 mpp 檔案時，ProjectBeforeTaskChangeEvent 會對實際上未由使用者變更的資料觸發的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-389">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="8dfbc-390">修正如果工作表單類型檢視內的延隔時間變更，ProjectBeforeTaskChange 事件中的 NewVal 不會有正確值的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-390">Fixed an issue where the NewVal in the ProjectBeforeTaskChange event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2010-october-19"></a><span data-ttu-id="8dfbc-392">版本 2010：10 月 19 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-392">Version 2010: October 19</span></span>
<span data-ttu-id="8dfbc-393">*版本 2010 (組建 13328.20210)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-393">*Version 2010 (Build 13328.20210)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="8dfbc-395">功能更新</span><span class="sxs-lookup"><span data-stu-id="8dfbc-395">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="8dfbc-396">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-396">Outlook</span></span>

- <span data-ttu-id="8dfbc-397">**撰寫郵件時節省時間：** Outlook 會顯示書寫建議，協助您快速撰寫郵件。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-397">**Save time while composing messages:** Outlook shows you writing suggestions that help you compose messages quickly.</span></span> <span data-ttu-id="8dfbc-398">若要接受建議，只需使用 Tab 鍵。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-398">To accept the suggestion, just use the Tab key.</span></span><br /><span data-ttu-id="8dfbc-399">在[部落格文章](https://insider.office.com/zh-TW/blog/text-predictions-in-word-outlook)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8dfbc-399">See details in [blog post](https://insider.office.com/zh-TW/blog/text-predictions-in-word-outlook)</span></span>

- <span data-ttu-id="8dfbc-400">**使用內建翻譯工具打破語言障礙：** 不再需要翻譯的增益集！</span><span class="sxs-lookup"><span data-stu-id="8dfbc-400">**Break the language barrier with a built-in translator:** Add-ins for translation aren't required anymore!</span></span> <span data-ttu-id="8dfbc-401">在電子郵件中，按一下滑鼠右鍵以翻譯特定的文字、片語或整個郵件。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-401">In a message, right-click to translate specific words, phrases, or the whole message.</span></span> [<span data-ttu-id="8dfbc-402">深入了解</span><span class="sxs-lookup"><span data-stu-id="8dfbc-402">Learn more</span></span>](https://support.office.com/article/287380e4-a56c-48a1-9977-f2dca89ce93f)

- <span data-ttu-id="8dfbc-403">**工作的使用者體驗更新：** 工作項目的視覺效果更新</span><span class="sxs-lookup"><span data-stu-id="8dfbc-403">**User Experience Updates for Tasks:** A visual refresh of task items</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8dfbc-404">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8dfbc-404">PowerPoint</span></span>

- <span data-ttu-id="8dfbc-405">**使用簡報者教練排練您的簡報：** 獲得可協助吸引對象的項目，例如節奏、過度使用的文字、肢體語言等等的指導。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-405">**Practice your presentation with Presenter Coach:** Get coaching on the things that help keep an audience engaged — like pacing, overused words, body language, and more.</span></span> [<span data-ttu-id="8dfbc-406">深入了解</span><span class="sxs-lookup"><span data-stu-id="8dfbc-406">Learn more</span></span>](https://support.office.com/article/cd7fc941-5c3b-498c-a225-83ef3f64f07b)

### <a name="word"></a><span data-ttu-id="8dfbc-407">Word</span><span class="sxs-lookup"><span data-stu-id="8dfbc-407">Word</span></span>

- <span data-ttu-id="8dfbc-408">**電腦版 Word 中的 Microsoft 編輯器窗格已更新：** 我們已將電腦版 Word 用戶端中編輯器窗格目前的體驗升級。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-408">**Microsoft Editor pane gets an update in Word for desktop:** We have upgraded the current experience with the Editor pane in Word for desktop clients.</span></span>

- <span data-ttu-id="8dfbc-409">**單鍵書寫建議：** 只要按一下，就能套用書寫建議。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-409">**One-click writing suggestions:** Apply writing suggestions with a single click.</span></span> <span data-ttu-id="8dfbc-410">更新的 [編輯器] 窗格讓您輕鬆在建議之間瀏覽。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-410">The updated Editor pane makes it easy to navigate between suggestions.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-413">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-413">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="8dfbc-414">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8dfbc-414">PowerPoint</span></span>

- <span data-ttu-id="8dfbc-415">這是此問題的修正：當有增益集在接聽 PresentationBeforeClose 事件並隨著事件處理常式檢查 Presentation.Saved 內容時若關閉文件，儲存提示會以迴圈顯示。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-415">This is a fix for an issue where the save prompt shows in a loop when closing the document when there is an add-in that listens to PresentationBeforeClose event and checks Presentation.Saved property as a part of the event handler.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2010-october-11"></a><span data-ttu-id="8dfbc-417">版本 2010: 10 月 11 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-417">Version 2010: October 11</span></span>
<span data-ttu-id="8dfbc-418">*版本 2010 (組建 13328.20154)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-418">*Version 2010 (Build 13328.20154)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="8dfbc-420">功能更新</span><span class="sxs-lookup"><span data-stu-id="8dfbc-420">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="8dfbc-421">Excel</span><span class="sxs-lookup"><span data-stu-id="8dfbc-421">Excel</span></span>

- <span data-ttu-id="8dfbc-422">**協助保護您的資料免受惡意檔案的侵害：**[應用程式防護] 可讓您在獨立的容器中讀取、列印和儲存 Office 檔案，協助保護您免受惡意程式碼的侵害。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-422">**Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container.</span></span> [<span data-ttu-id="8dfbc-423">深入了解</span><span class="sxs-lookup"><span data-stu-id="8dfbc-423">Learn more</span></span>](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)

### <a name="powerpoint"></a><span data-ttu-id="8dfbc-424">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8dfbc-424">PowerPoint</span></span>

- <span data-ttu-id="8dfbc-425">**協助保護您的資料免受惡意檔案的侵害：**[應用程式防護] 可讓您在獨立的容器中讀取、列印和儲存 Office 檔案，協助保護您免受惡意程式碼的侵害。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-425">**Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container.</span></span> [<span data-ttu-id="8dfbc-426">深入了解</span><span class="sxs-lookup"><span data-stu-id="8dfbc-426">Learn more</span></span>](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)

### <a name="word"></a><span data-ttu-id="8dfbc-427">Word</span><span class="sxs-lookup"><span data-stu-id="8dfbc-427">Word</span></span>

- <span data-ttu-id="8dfbc-428">**協助保護您的資料免受惡意檔案的侵害：**[應用程式防護] 可讓您在獨立的容器中讀取、列印和儲存 Office 檔案，協助保護您免受惡意程式碼的侵害。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-428">**Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container.</span></span> [<span data-ttu-id="8dfbc-429">深入了解</span><span class="sxs-lookup"><span data-stu-id="8dfbc-429">Learn more</span></span>](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-432">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-432">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="8dfbc-433">Access</span><span class="sxs-lookup"><span data-stu-id="8dfbc-433">Access</span></span>

- <span data-ttu-id="8dfbc-434">我們已修正載入儲存的查詢/關聯視窗在捲動時，捲軸位置未正確設定的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-434">We fixed an issue where scrollbar position was not set correctly when loading query/relationship window saved while scrolled.</span></span>


- <span data-ttu-id="8dfbc-435">我們已修正 [新增表格] 工作窗格未正確顯示包含 '&' 名稱的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-435">We fixed an issue where Add Table Task Pane was not displaying names containing '&' correctly.</span></span>


### <a name="excel"></a><span data-ttu-id="8dfbc-436">Excel</span><span class="sxs-lookup"><span data-stu-id="8dfbc-436">Excel</span></span>

- <span data-ttu-id="8dfbc-437">我們已修正多層次類別的手動間隔在圖表中無法運作的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-437">We fixed an issue where multi-level category manual interval was not working in charts.</span></span>


- <span data-ttu-id="8dfbc-438">修正在使用 2D 地圖圖表時，無法使用 VBA 設定系列中最大值、中間值和最小值顏色的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-438">Fixed an issue with 2D Map Charts where using VBA to set the colors for the max, mid, and min values for a series was not working.</span></span>


- <span data-ttu-id="8dfbc-439">修正可能會導致「嘗試計算一個或多個公式時，Excel 資源不足」的錯誤問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-439">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="8dfbc-440">修正當 Office 語言設定為西班牙文時，其中資料驗證清單可能無法顯示清單中所有項目的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-440">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="8dfbc-441">修正在啟用「分頁預覽」時，在含有大量資料的工作表之間切換時，可能會發生明顯延遲的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-441">Fixed an issue where there could be a noticeable delay when switching between worksheets with large amounts of data when 'Page Break Preview' was enabled.</span></span>


- <span data-ttu-id="8dfbc-442">我們已修正當新增至用於資料驗證的表格時，並未更新活頁簿中所有工作表選項的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-442">We fixed an issue where adding to a table used for Data Validation did not update options for all sheets in the workbook.</span></span>


- <span data-ttu-id="8dfbc-443">我們已修正在重新整理 OLAP 樞紐分析表時，可能會導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-443">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="8dfbc-444">已修正在使用資料編輯列輸入公式時，某些情況下 ChartSheet 出現當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-444">Fixed an issue where ChartSheet crashed in some cases when a formula is entered through formula bar.</span></span>


- <span data-ttu-id="8dfbc-445">我們修正了 Excel 公式列與設備失去連線後無法完全呈現的問題，例如遠端會話的連線/斷線或監視器變更。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-445">We fixed an issue where the Excel formula bar would not render completely after connection to a device was lost, such as a remote session connect/disconnect or a monitor change.</span></span>


### <a name="onenote"></a><span data-ttu-id="8dfbc-446">OneNote</span><span class="sxs-lookup"><span data-stu-id="8dfbc-446">OneNote</span></span>

- <span data-ttu-id="8dfbc-447">我們修正了使用者無法從 [外部空間檔案] > [資訊] 的文字方塊中選取及複製筆記本 URL 的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-447">We fixed an issue where a user was unable to select and copy notebook URL from textbox in OutSpace File > Info.</span></span>


- <span data-ttu-id="8dfbc-448">我們已修正當您將游標移至筆記本色彩選擇器的綠色上方時，快顯會顯示「紅粉色」的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-448">We fixed an issue when you hover over green color in notebook color selector, the pop up reads "red chalk".</span></span>


- <span data-ttu-id="8dfbc-449">我們已修正 OneNote 在自訂主題的畫布中不會採用高對比色彩的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-449">We fixed an issue where OneNote didn't honor High Contrast colors in the canvas for custom themes.</span></span>


### <a name="outlook"></a><span data-ttu-id="8dfbc-450">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-450">Outlook</span></span>

- <span data-ttu-id="8dfbc-451">已解決當主旨為空白時，會導致傳送的自動產生電子郵件含有空白內文的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-451">Addresses an issue that caused automatically generated emails to be sent with a blank body when the subject is blank.</span></span>


- <span data-ttu-id="8dfbc-452">我們修正了資料夾中快取錯誤資料夾 guid 的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-452">We fixed an issue where the wrong folder guid is cached for folders.</span></span>


- <span data-ttu-id="8dfbc-453">當使用者將電子郵件地址複製貼上到顯示名稱的 [收件者] 欄位時，電子郵件地址不一定可被正確分析，並導致出現了一個顯示電子郵件地址無效的警告。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-453">When a user copy-and-pastes an email address into the recipient field with the display name, the email address wasn't always parsed correctly and caused a warning about an invalid email address to appear.</span></span>  <span data-ttu-id="8dfbc-454">已修正此問題，可正確分析名稱和電子郵件地址，因此不會再顯示警告。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-454">It's been fixed so the name and email address are parsed correctly so the warning is no longer shown.</span></span>


- <span data-ttu-id="8dfbc-455">我們修正了線上共用資料夾未傳回母資料夾名稱的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-455">We fixed an issue where online shared folders did not return parent folder name.</span></span> <span data-ttu-id="8dfbc-456">它並非失敗，而是傳回了不正確地移至主要帳戶的空白路徑。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-456">Intsead of failing, it returned an empty path which incorrectly went to the primary account.</span></span>


- <span data-ttu-id="8dfbc-457">我們修正了傳統附件無法使用 [另存為] 選項的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-457">We fixed an issue where the Save As option was not available for classic attachments.</span></span>


- <span data-ttu-id="8dfbc-458">我們修正了讓使用者能在覆寫原則時自訂調整文字的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-458">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


- <span data-ttu-id="8dfbc-459">我們已修正從唯讀預覽窗格中重新開啟 [草稿] 之後會開啟 [追蹤修訂] 的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-459">We fixed an issue where track changes turned on after reopening draft from read-only preview pane.</span></span>


- <span data-ttu-id="8dfbc-460">我們已修正關閉 [焦點收件匣] 並執行排序之後，電子郵件遭隱藏的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-460">We fixed an issue with emails being hidden after turning Focused Inbox off and doing a sort.</span></span>


- <span data-ttu-id="8dfbc-461">我們已修正導致 Outlook 為啟用雲端設定的使用者建立第二個空白簽名的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-461">We fixed an issue that caused Outlook to create a second empty signature for people who had cloud settings enabled.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="8dfbc-462">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8dfbc-462">PowerPoint</span></span>

- <span data-ttu-id="8dfbc-463">我們修正了 PowerPoint 在匯出為 PDF 時，無法匯出矩形專案符號的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-463">We fixed an issue where PowerPoint was not exporting rectangle bullet points while exporting to PDF.</span></span>


- <span data-ttu-id="8dfbc-464">我們已修正 GIF 在編輯器和投影片放映中的動畫只會執行一次的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-464">We fixed an issue where GIF's would animate only once in the editor and slide shows.</span></span>


- <span data-ttu-id="8dfbc-465">我們已修正當使用者將來源路徑變更為本機 OneDrive 資料夾時，連結的 Excel 圖表不正確變更為 Excel 工作表的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-465">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


- <span data-ttu-id="8dfbc-466">我們修正了若您在最後一張投影片上，且您在按 [結束工作模式] 之後和顯示摘要之前，滑向下一張投影片，則會在 [摘要] 頁面上看到 [結束工作模式] 對話方塊。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-466">We fixed an issue that If you are on the last slide and if you swipe to the next slide after pressing 'End Session' and before the summary shows up, the End-Session dialog is visible on the summary page as well.</span></span>


### <a name="project"></a><span data-ttu-id="8dfbc-467">Project</span><span class="sxs-lookup"><span data-stu-id="8dfbc-467">Project</span></span>

- <span data-ttu-id="8dfbc-468">修正了如果您嘗試多次新增同一專案，且將 AttachToSources 設定為 false 時，ConsolidateProjects VBA 方法可能會發生出錯的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-468">Fixed an issue where the ConsolidateProjects VBA method may file if you try to add the same project multiple times and have AttachToSources set to false.</span></span>


- <span data-ttu-id="8dfbc-469">已修正若您的事件程式碼執行中，並嘗試透過工作 [表單檢視] 進行變更，按一下 [確定] 按鈕可能不會提交變更的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-469">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


- <span data-ttu-id="8dfbc-470">修正了如果您嘗試多次新增同一專案，且將 AttachToSources 設定為 false 時，ConsolidateProjects VBA 方法可能會發生出錯的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-470">Fixed an issue where the ConsolidateProjects VBA method may file if you try to add the same project multiple times and have AttachToSources set to false.</span></span>


- <span data-ttu-id="8dfbc-471">修正了如果您的自訂欄位包含公式，且正在使用實獲值分析，您可能會發現效能延遲切換檢視並開啟專案/工作詳細資料的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-471">Fixed an issue where if you have custom fields with formulas and are using earned value, you may notice performance delays switching views and opening project/task details.</span></span>


- <span data-ttu-id="8dfbc-472">修正了如果您將群組套用到 [資源使用狀況] 或 [工作表] 視圖，然後插入欄位，Project 可能會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-472">Fixed an issue where Project may crash if you apply a group by to the Resource Usage or Sheet view and then insert a column.</span></span>


### <a name="word"></a><span data-ttu-id="8dfbc-473">Word</span><span class="sxs-lookup"><span data-stu-id="8dfbc-473">Word</span></span>

- <span data-ttu-id="8dfbc-474">我們己修正已啟用工作流程檔案的連結無法如預期開啟的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-474">We fixed an issue where links to workflow enabled files were not opening as expected.</span></span>


- <span data-ttu-id="8dfbc-475">修正當使用者在點擊追蹤的變更（插入/刪除）時，會彈出註解的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-475">Fixed an issue where a user tapping on a tracked change (insertion/deletion) would bring up a comment pop-out.</span></span>


- <span data-ttu-id="8dfbc-476">我們已修正 Word 中刪除註解圖說文字的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-476">We fixed an issue with deleting comment callouts in Word.</span></span>


- <span data-ttu-id="8dfbc-477">我們已修正 Outlook 有關將郵件設定為 [不要轉寄] 的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-477">We fixed an issue with Outlook with message set to Do not forward.</span></span>


- <span data-ttu-id="8dfbc-478">我們已修正有關儲存含有引文和方程式的 Word 文件問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-478">We fixed an issue with saving Word document that contains citation and equation.</span></span>


- <span data-ttu-id="8dfbc-479">我們修正了 [樣式圖庫] 對話方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-479">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="8dfbc-480">Office 套件</span><span class="sxs-lookup"><span data-stu-id="8dfbc-480">Office Suite</span></span>

- <span data-ttu-id="8dfbc-481">當使用者從 Office 噴墨印表機上列印任何文件/檔案且列印機墨水不足時，即使噴墨印表機沒有碳粉，也會顯示「碳粉不足」或「無碳粉」消息。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-481">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="8dfbc-482">將訊息變更為顯示「碳粉/墨水不足」和「沒有碳粉/墨水」。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-482">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2009-october-07"></a><span data-ttu-id="8dfbc-484">版本 2009：10 月 7 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-484">Version 2009: October 07</span></span>
<span data-ttu-id="8dfbc-485">*版本 2009 (組建 13231.20360)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-485">*Version 2009 (Build 13231.20360)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="8dfbc-487">功能更新</span><span class="sxs-lookup"><span data-stu-id="8dfbc-487">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="8dfbc-488">Excel</span><span class="sxs-lookup"><span data-stu-id="8dfbc-488">Excel</span></span>

- <span data-ttu-id="8dfbc-489">**使用 Power Query 建立資料類型：** 使用任何資料來源中的 Power Query 建立豐富的資料類型</span><span class="sxs-lookup"><span data-stu-id="8dfbc-489">**Create Data Types with Power Query:** Create rich data types with Power Query from any data source</span></span>

### <a name="outlook"></a><span data-ttu-id="8dfbc-490">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-490">Outlook</span></span>

- <span data-ttu-id="8dfbc-491">**語文法檢查鼎力相助**：Outlook 會在你鍵入時標記文法錯誤，因此你只需按一下就可以套用建議。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-491">**Grammar checking's got your back:** Outlook marks grammar errors as you type, so you can apply suggestions with a single click.</span></span> <br /><span data-ttu-id="8dfbc-492">在[部落格文章](https://insider.office.com/zh-TW/blog/grammar-and-style-suggestions-available-in-outlook)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8dfbc-492">See details in [blog post](https://insider.office.com/zh-TW/blog/grammar-and-style-suggestions-available-in-outlook)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-495">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-495">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="8dfbc-496">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-496">Outlook</span></span>

- <span data-ttu-id="8dfbc-497">解决了搜尋未緩存共用行事曆時導致搜尋不傳回結果的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-497">Addresses an issue that caused Search to return no results when searching uncached shared calendars.</span></span>


- <span data-ttu-id="8dfbc-498">解決了導致某些使用者觀察到在離線狀態下意外啟動 Outlook 的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-498">Addresses an issue that caused some users to observe Outlook unexpectedly starting in an offline state.</span></span>


- <span data-ttu-id="8dfbc-499">解決了導致代理人在開啟另一個信箱中的共用資料夾時出現錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-499">Addresses an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="8dfbc-500">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8dfbc-500">PowerPoint</span></span>

- <span data-ttu-id="8dfbc-501">解决在受保護的檢視中開啟 PowerPoint 檔案時停用 IRM 保護的問題的安全性問題修正。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-501">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


### <a name="office-suite"></a><span data-ttu-id="8dfbc-502">Office 套件</span><span class="sxs-lookup"><span data-stu-id="8dfbc-502">Office Suite</span></span>

- <span data-ttu-id="8dfbc-503">當使用者從 Office 噴墨印表機上列印任何文件/檔案且列印機墨水不足時，即使噴墨印表機沒有碳粉，也會顯示「碳粉不足」或「無碳粉」消息。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-503">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="8dfbc-504">將訊息變更為顯示「碳粉/墨水不足」和「沒有碳粉/墨水」。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-504">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2009-september-26"></a><span data-ttu-id="8dfbc-506">版本 2009：9 月 26 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-506">Version 2009: September 26</span></span>
<span data-ttu-id="8dfbc-507">*版本 2009 (組建 13231.20262)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-507">*Version 2009 (Build 13231.20262)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-509">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-509">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="8dfbc-510">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-510">Outlook</span></span>

- <span data-ttu-id="8dfbc-511">已解決當主旨行空白時，會導致傳送的自動產生電子郵件含有空白內文的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-511">Addresses an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


### <a name="project"></a><span data-ttu-id="8dfbc-512">Project</span><span class="sxs-lookup"><span data-stu-id="8dfbc-512">Project</span></span>

- <span data-ttu-id="8dfbc-513">已修正若您的事件程式碼執行中，並嘗試透過工作 [表單檢視] 進行變更，按一下 [確定] 按鈕可能不會提交變更的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-513">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2009-september-21"></a><span data-ttu-id="8dfbc-515">版本 2009：9 月 21 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-515">Version 2009: September 21</span></span>
<span data-ttu-id="8dfbc-516">*版本 2009 (組建 13231.20200)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-516">*Version 2009 (Build 13231.20200)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="8dfbc-518">功能更新</span><span class="sxs-lookup"><span data-stu-id="8dfbc-518">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="8dfbc-519">Access</span><span class="sxs-lookup"><span data-stu-id="8dfbc-519">Access</span></span>

- <span data-ttu-id="8dfbc-520">**自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-520">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="8dfbc-521">移至 [檔案] > [選項]，然後選取 [Office 佈景主題] 旁邊的 [使用系統設定]。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-521">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="8dfbc-522">深入了解</span><span class="sxs-lookup"><span data-stu-id="8dfbc-522">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="excel"></a><span data-ttu-id="8dfbc-523">Excel</span><span class="sxs-lookup"><span data-stu-id="8dfbc-523">Excel</span></span>

- <span data-ttu-id="8dfbc-524">**將您的 iPhone 相片直接插入 Office：** 來自您手機的 HEIC 圖片現在可無縫地插入 Office。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-524">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="8dfbc-525">不需要轉換。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-525">No conversion required.</span></span><br /><span data-ttu-id="8dfbc-526">在[部落格文章](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8dfbc-526">See details in [blog post](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="8dfbc-527">**自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-527">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="8dfbc-528">移至 [檔案] > [選項]，然後選取 [Office 佈景主題] 旁邊的 [使用系統設定]。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-528">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="8dfbc-529">深入了解</span><span class="sxs-lookup"><span data-stu-id="8dfbc-529">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="onenote"></a><span data-ttu-id="8dfbc-530">OneNote</span><span class="sxs-lookup"><span data-stu-id="8dfbc-530">OneNote</span></span>

- <span data-ttu-id="8dfbc-531">**自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-531">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="8dfbc-532">移至 [檔案] > [選項]，然後選取 [Office 佈景主題] 旁邊的 [使用系統設定]。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-532">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="8dfbc-533">深入了解</span><span class="sxs-lookup"><span data-stu-id="8dfbc-533">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="outlook"></a><span data-ttu-id="8dfbc-534">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-534">Outlook</span></span>

- <span data-ttu-id="8dfbc-535">**依訊息擁有者刪除交談：** 此功能可讓您依訊息擁有者刪除交談。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-535">**Delete conversation by message owner:** This feature allows you to delete a conversation by message owner.</span></span>

- <span data-ttu-id="8dfbc-536">**將您的 iPhone 相片直接插入 Office：** 來自您手機的 HEIC 圖片現在可無縫地插入 Office。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-536">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="8dfbc-537">不需要轉換。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-537">No conversion required.</span></span><br /><span data-ttu-id="8dfbc-538">在[部落格文章](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8dfbc-538">See details in [blog post](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="8dfbc-539">**自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-539">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="8dfbc-540">移至 [檔案] > [選項]，然後選取 [Office 佈景主題] 旁邊的 [使用系統設定]。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-540">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="8dfbc-541">深入了解</span><span class="sxs-lookup"><span data-stu-id="8dfbc-541">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="powerpoint"></a><span data-ttu-id="8dfbc-542">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8dfbc-542">PowerPoint</span></span>

- <span data-ttu-id="8dfbc-543">**將您的 iPhone 相片直接插入 Office：** 來自您手機的 HEIC 圖片現在可無縫地插入 Office。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-543">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="8dfbc-544">不需要轉換。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-544">No conversion required.</span></span><br /><span data-ttu-id="8dfbc-545">在[部落格文章](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8dfbc-545">See details in [blog post](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="8dfbc-546">**自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-546">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="8dfbc-547">移至 [檔案] > [選項]，然後選取 [Office 佈景主題] 旁邊的 [使用系統設定]。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-547">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="8dfbc-548">深入了解</span><span class="sxs-lookup"><span data-stu-id="8dfbc-548">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="project"></a><span data-ttu-id="8dfbc-549">Project</span><span class="sxs-lookup"><span data-stu-id="8dfbc-549">Project</span></span>

- <span data-ttu-id="8dfbc-550">**自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-550">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="8dfbc-551">移至 [檔案] > [選項]，然後選取 [Office 佈景主題] 旁邊的 [使用系統設定]。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-551">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="8dfbc-552">深入了解</span><span class="sxs-lookup"><span data-stu-id="8dfbc-552">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="publisher"></a><span data-ttu-id="8dfbc-553">Publisher</span><span class="sxs-lookup"><span data-stu-id="8dfbc-553">Publisher</span></span>

- <span data-ttu-id="8dfbc-554">**自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-554">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="8dfbc-555">移至 [檔案] > [選項]，然後選取 [Office 佈景主題] 旁邊的 [使用系統設定]。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-555">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="8dfbc-556">深入了解</span><span class="sxs-lookup"><span data-stu-id="8dfbc-556">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="visio"></a><span data-ttu-id="8dfbc-557">Visio</span><span class="sxs-lookup"><span data-stu-id="8dfbc-557">Visio</span></span>

- <span data-ttu-id="8dfbc-558">**自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-558">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="8dfbc-559">移至 [檔案] > [選項]，然後選取 [Office 佈景主題] 旁邊的 [使用系統設定]。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-559">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="8dfbc-560">深入了解</span><span class="sxs-lookup"><span data-stu-id="8dfbc-560">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="word"></a><span data-ttu-id="8dfbc-561">Word</span><span class="sxs-lookup"><span data-stu-id="8dfbc-561">Word</span></span>

- <span data-ttu-id="8dfbc-562">**將您的 iPhone 相片直接插入 Office：** 來自您手機的 HEIC 圖片現在可無縫地插入 Office。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-562">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="8dfbc-563">不需要轉換。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-563">No conversion required.</span></span><br /><span data-ttu-id="8dfbc-564">在[部落格文章](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8dfbc-564">See details in [blog post](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="8dfbc-565">**自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-565">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="8dfbc-566">移至 [檔案] > [選項]，然後選取 [Office 佈景主題] 旁邊的 [使用系統設定]。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-566">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="8dfbc-567">深入了解</span><span class="sxs-lookup"><span data-stu-id="8dfbc-567">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-570">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-570">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="8dfbc-571">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8dfbc-571">PowerPoint</span></span>

- <span data-ttu-id="8dfbc-572">修正了在包含大量特定資料物件類型 (E2o) 的檔案上導致共同撰寫變慢的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-572">Fixed an issue causing slow coauthoring on files containing large numbers of a certain data object type (E2o).</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2009-september-14"></a><span data-ttu-id="8dfbc-574">版本 2009：9 月 14 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-574">Version 2009: September 14</span></span>
<span data-ttu-id="8dfbc-575">*版本 2009 (組建 13231.20152)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-575">*Version 2009 (Build 13231.20152)*</span></span>
* <span data-ttu-id="8dfbc-576">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-576">Various bugs and performance fixes.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2009-september-10"></a><span data-ttu-id="8dfbc-579">版本 2009：9 月 10 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-579">Version 2009: September 10</span></span>
<span data-ttu-id="8dfbc-580">*版本 2009 (組建 13231.20126)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-580">*Version 2009 (Build 13231.20126)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-582">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-582">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="8dfbc-583">Access</span><span class="sxs-lookup"><span data-stu-id="8dfbc-583">Access</span></span>

- <span data-ttu-id="8dfbc-584">此問題現在已解決，您不應該會再遇到當機。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-584">This issue has now been resolved and you should no longer experience a crash.</span></span>


- <span data-ttu-id="8dfbc-585">我們已修正 ODBC 資料庫的連線對協力廠商應用程式沒有作用的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-585">We fixed an issue where connections to an ODBC database were not working with third party applications.</span></span>


### <a name="excel"></a><span data-ttu-id="8dfbc-586">Excel</span><span class="sxs-lookup"><span data-stu-id="8dfbc-586">Excel</span></span>

- <span data-ttu-id="8dfbc-587">我們修正了一個問題, 即如果您開啟包含LET 函數的檔案，它會顯示警示：”我們在您的檔案.xlsx 中發現內容有問題”。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-587">We fixed an issue where if you opened a file containing the LET function, it would display the alert:  "We found a problem with content in "your file.xlsx".</span></span> <span data-ttu-id="8dfbc-588">您想要我們儘量嘗試復原嗎？</span><span class="sxs-lookup"><span data-stu-id="8dfbc-588">Do you want us to try to recover as much as we can?</span></span> <span data-ttu-id="8dfbc-589">如果您信任這個活頁簿的來源，請按一下 [是]。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-589">If you trust the source of this workbook, click Yes".</span></span>


- <span data-ttu-id="8dfbc-590">我們修復了如果用戶鍵入包含括號的公式名稱並通過F1調用了協助，則該特定於公式的說明主題將不會顯示。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-590">We fixed an issue where if a user typed a formula name including the parenthesis and invoked help via F1, the help topic specific to that formula would not be displayed.</span></span>


- <span data-ttu-id="8dfbc-591">我們已修正使用巨集來設定某個範圍的 FormulaR1C1 屬性時，如果圖表工作表為作用中工作表，則儲存格參考會不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-591">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>


- <span data-ttu-id="8dfbc-592">我們修正了使用者無法修改樞紐分析表篩選的問題，因為它已設定為Analysis Services數據庫中不再存在的值。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-592">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


- <span data-ttu-id="8dfbc-593">修正與 XLAM 增益集參照和具名範圍相關的損毀。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-593">Fixed a crash related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="8dfbc-594">我們修正了一個問題: 如果使用者將自訂樣式套用至動態陣列, 他們則會收到錯誤提示：「您無法變更陣列的一部分」。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-594">We fixed an issue where if a user applied a custom style to a dynamic array, they would get the error: "You can't change part of an array".</span></span> <span data-ttu-id="8dfbc-595">這是舊版限制，已移除。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-595">This was a legacy restriction that has been removed.</span></span>


- <span data-ttu-id="8dfbc-596">修正在還原檔案的舊版本後，指派給按鈕的巨集會中斷的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-596">Fixed an issue where macros assigned to buttons were broken after restoring an older version of the file.</span></span>


- <span data-ttu-id="8dfbc-597">我們已修正筆跡會導致 Excel 無法回應的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-597">We fixed an issue where inking could cause Excel to become unresponsive.</span></span>


### <a name="outlook"></a><span data-ttu-id="8dfbc-598">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-598">Outlook</span></span>

- <span data-ttu-id="8dfbc-599">我們修正了一個問題, 讓您可透過群組政策來啟用/停用預設的登入選項。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-599">We fixed an issue which provides more flexibility in enabling / disabling the default logging options via Group Policy.</span></span>


- <span data-ttu-id="8dfbc-600">我們修正了電子郵件草稿在助理和經理權限移動時, 寄件者的舊網域名稱仍被保留和顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-600">We fixed an issue where the Legacy Domain Name for an email sender was preserved and displayed after a draft of the email was moved between mailboxes with assistant permissions and manager permissions.</span></span>


- <span data-ttu-id="8dfbc-601">修正會導致某些使用者看到 Outlook 在離線狀態中啟動，直到他們手動選擇線上工作為止的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-601">Fixes an issue that caused some users to see Outlook to start in an Offline state until they manually chose to work online.</span></span>


- <span data-ttu-id="8dfbc-602">我們已修正在啟用單行功能區（SLR）後，執行 VBA 程式碼 ActiveInspector （"ShowSchedulingPage"）會導致執行階段錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-602">We fixed an issue where running the VBA code ActiveInspector.CommandBars.ExecuteMso("ShowSchedulingPage") after enabling the Single Line Ribbon (SLR) would result in a runtime error.</span></span>


- <span data-ttu-id="8dfbc-603">我們修正了一個問題, 即Automatic Replies自動回復對話方塊上的確定和取消按鈕以高解析度（例如 1750 x 1920）及較大文字（例如175%）顯示的系統上的錯誤。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-603">We fixed an issue where the 'OK' and 'Cancel' buttons on the Automatic Replies dialog would not be visible on a system with a high resolution (such as 1750 x 1920) combined with a large text size (such as 175%).</span></span>


- <span data-ttu-id="8dfbc-604">我們修正一個情況, 即將會議請求從空的聯繫人群組發送到另一個聯繫人組會導致當機。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-604">We fixed a condition where sending a meeting request from an empty contact group to another contact group would result in a crash.</span></span>


- <span data-ttu-id="8dfbc-605">解決會導致使用者在開啟某些很大型電子郵件時會發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-605">Fixes an issue that caused users to experience a crash when opening certain very large emails.</span></span>


- <span data-ttu-id="8dfbc-606">我們修正了一個問題, 它使的群組政策要求始終啟用增益集, 則 監視增益集的功能則無法使用，以防止使用者禁用增益集,。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-606">We fixed an issue where if Group Policy requires an Add-in to be always enabled, then monitoring add-in's becomes unavailable in order to prevent users from disabling the Add-in.</span></span>


- <span data-ttu-id="8dfbc-607">解決一個問題，該問題導致使用者在選擇多個訊息時，能夠傳送 OneNote 所套用的「不可轉寄」原則的電子郵件內容。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-607">Addresses an issue that caused users to be able to send email content that had a "Do Not Forward" policy applied to OneNote when selecting more than one message.</span></span>


- <span data-ttu-id="8dfbc-608">我們已修正一個問題，使用者現在可以停用 Outlook 的 IRM (資訊版權管理)，而不需要為其餘 Office 應用程式停用它。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-608">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>


- <span data-ttu-id="8dfbc-609">我們修正了 Active Directory 中的 "otherTelephone" 和 "otherHomePhone" 使用者帳戶屬性未對應到對應的 Outlook LDAP 屬性的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-609">We fixed an issue where the user account attributes in Active Directory for "otherTelephone" and "otherHomePhone" were not mapped to the corresponding Outlook LDAP attributes.</span></span>


- <span data-ttu-id="8dfbc-610">此變更解決了在用戶將索引標籤從會議頁面切換到排程小幫手頁面後，會議頁面將繼續顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-610">This change fixes an issue where the Meeting page would continue to be displayed after the user switched tabs from the Meeting page to the Scheduling Assistant page.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="8dfbc-611">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8dfbc-611">PowerPoint</span></span>

- <span data-ttu-id="8dfbc-612">我們修正了使用者在特定情況下看到功能區/標題列未顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-612">We fixed an issue where users were seeing the ribbon/title bar not being displayed under certain conditions.</span></span>


- <span data-ttu-id="8dfbc-613">我們已修正啟動 PowerPoint 之後，插入投影片並開啟和關閉批註窗格的問題，縮圖窗格中的投影片會顯示為重疊。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-613">We fixed an issue where after booting PowerPoint, inserting a slide and opening and closing the comments pane, the slides in the thumbnail pane displayed as being overlapped.</span></span>


- <span data-ttu-id="8dfbc-614">我們已修正插入影片的功能已停用的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-614">We fixed an issue where the functionality to insert a video was disabled.</span></span>


- <span data-ttu-id="8dfbc-615">我們已修正影片在投影片放映中無法自動播放的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-615">We fixed an issue where videos were not playing automatically in slideshows.</span></span>


### <a name="project"></a><span data-ttu-id="8dfbc-616">Project</span><span class="sxs-lookup"><span data-stu-id="8dfbc-616">Project</span></span>

- <span data-ttu-id="8dfbc-617">我們修正了如果資源有多個成本費率表的問題，則剩餘成本可能無法被正確計算.</span><span class="sxs-lookup"><span data-stu-id="8dfbc-617">We fixed an issue where if a resource has multiple cost rate tables, the remaining cost may not be calculated correctly.</span></span>


- <span data-ttu-id="8dfbc-618">我們已修正連結至 SharePoint 工作清單的專案的專案完成日期不會更新的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-618">We fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>


### <a name="visio"></a><span data-ttu-id="8dfbc-619">Visio</span><span class="sxs-lookup"><span data-stu-id="8dfbc-619">Visio</span></span>

- <span data-ttu-id="8dfbc-620">客戶回報文字對齊會在即時預覽時發生當機。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-620">Live preview crashes on text alignment reported by customers.</span></span> <span data-ttu-id="8dfbc-621">7 月分支所發生最多的當機情況。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-621">Top hitting crash of July fork.</span></span>


### <a name="word"></a><span data-ttu-id="8dfbc-622">Word</span><span class="sxs-lookup"><span data-stu-id="8dfbc-622">Word</span></span>

- <span data-ttu-id="8dfbc-623">我們修正了一個問題, 即使用者點擊註解，註解卡將在註解文周圍顯示邊框。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-623">We fixed an issue where the Comment card would display a border around the comment text if the user clicked on the comment.</span></span>


- <span data-ttu-id="8dfbc-624">我們已修正項目符號圖片無法正確顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-624">We fixed an issue where the bullet picture icon didn't display correctly.</span></span>


- <span data-ttu-id="8dfbc-625">我們已修正使用者在選取註解時無法退出頁首/頁尾的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-625">We fixed an issue where the user could not exit the Header/Footer when selecting a comment.</span></span>


- <span data-ttu-id="8dfbc-626">我們已修正刪除註解之後 Word 可能會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-626">We fixed an issue where Word could crash after comments were deleted.</span></span>


- <span data-ttu-id="8dfbc-627">我們修復了一個問題，即如果使用者建立的評論草稿, 錨定在已包含提交的評論行上，則在SideTrack與提交評論相關的草案則以錯誤的順序排列。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-627">We fixed an issue where if a user created a comment draft anchored to a line already containing committed comments, then the draft was arranged in the wrong order relative to the committed comment in the SideTrack.</span></span>


- <span data-ttu-id="8dfbc-628">我們修正了一個問題, 即如將文件縮放到160％或更高, 且註解窗格不可見，焦點將不會移至註解窗格。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-628">We fixed an issue where the focus would not go to the comment pane if the document was zoomed to 160% or more and the comment pane was not visible.</span></span>


- <span data-ttu-id="8dfbc-629">我們已修正一個問題，該問題造成使用者無法看到超出邊界的註解，因為在邊界中無法下拉。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-629">We fixed an issue that prevented users from seeing comment threads that exceeded the sidetrack boundary because scrolling through the sidetrack was not working.</span></span>


- <span data-ttu-id="8dfbc-630">我們修正了在邊界窗格中，搜尋已解決的註解無法正常運作的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-630">We fixed an issue where searching for resolved comments in the sidetrack pane was not working.</span></span>


- <span data-ttu-id="8dfbc-631">我們修復了一個問題，即在多個打開的文件之間切換後，一個文件的註解會顯示在其他打開的文檔上。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-631">We fixed an issue where the comments on one document would be displayed on other open documents after switching between the multiple open documents.</span></span>


- <span data-ttu-id="8dfbc-632">我們已修正將文件儲存成 HTML 格式時，長連結無法換行的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-632">We fixed an issue where long links were not being wrapped when saving document to HTML format.</span></span>


- <span data-ttu-id="8dfbc-633">我們已修正在某些情況下，項目符號無法在電子郵件中正確顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-633">We fixed an issue where in some cases, bullets are not displaying correctly in email.</span></span>


- <span data-ttu-id="8dfbc-634">我們已修正 AutoOpen 會在 AutoExec 之前執行的巨集問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-634">We fixed an issue with macros in which AutoOpen runs before AutoExec.</span></span>


### <a name="office-suite"></a><span data-ttu-id="8dfbc-635">Office 套件</span><span class="sxs-lookup"><span data-stu-id="8dfbc-635">Office Suite</span></span>

- <span data-ttu-id="8dfbc-636">我們修正了 Office 部署工具中的一個問題，該問題是，在 Microsoft Office 2007 [Microsoft 應用程式錯誤回報工具] 產品存在的情況下使用 RemoveMSI 功能時設定失敗。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-636">We fixed an issue in the Office Deployment Tool where configuration was failing when using the RemoveMSI feature with the Office 2007 "Microsoft Application Error Reporting" product present.</span></span>


- <span data-ttu-id="8dfbc-637">我們在 [壓縮圖片] 對話方塊中，修正了某些使用者選取的 DPI 設定無法保留的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-637">We fixed an issue in the Compress Picture dialog where some user-selected DPI settings are not retained.</span></span>


- <span data-ttu-id="8dfbc-638">此變更解決 [壓縮圖片] 對話方塊無法保留特定使用者設定的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-638">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-september-04"></a><span data-ttu-id="8dfbc-640">版本2008：9月 4日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-640">Version 2008: September 04</span></span>
<span data-ttu-id="8dfbc-641">*版本2008（組建13127.20378）*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-641">*Version 2008 (Build 13127.20378)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-643">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-643">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="8dfbc-644">Office 套件</span><span class="sxs-lookup"><span data-stu-id="8dfbc-644">Office Suite</span></span>

- <span data-ttu-id="8dfbc-645">此變更解決 [壓縮圖片] 對話方塊無法保留特定使用者設定的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-645">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-september-02"></a><span data-ttu-id="8dfbc-647">版本 2008：9 月 2 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-647">Version 2008: September 02</span></span>
<span data-ttu-id="8dfbc-648">*版本2008（組建13127.20360）*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-648">*Version 2008 (Build 13127.20360)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="8dfbc-650">功能更新</span><span class="sxs-lookup"><span data-stu-id="8dfbc-650">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="8dfbc-651">Excel</span><span class="sxs-lookup"><span data-stu-id="8dfbc-651">Excel</span></span>

- <span data-ttu-id="8dfbc-652">**將圖形另存為圖片：** 只要按幾下，即可將圖形、圖示或其他物件另存成圖片，便於您於任何其他地方使用。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-652">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="8dfbc-653">深入了解</span><span class="sxs-lookup"><span data-stu-id="8dfbc-653">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="8dfbc-654">**使用 Excel 手寫筆進行快速編輯：**[手寫筆工具] 可協助您手寫並快速編輯資料</span><span class="sxs-lookup"><span data-stu-id="8dfbc-654">**Make quick edits using the Excel pen:** Pen Tool to help you handwrite and make quick edits to your data</span></span>



[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-657">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-657">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="8dfbc-658">Excel</span><span class="sxs-lookup"><span data-stu-id="8dfbc-658">Excel</span></span>

- <span data-ttu-id="8dfbc-659">已修正使用 [複製格式] 時，某些情況下，Excel 可能會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-659">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>


### <a name="word"></a><span data-ttu-id="8dfbc-660">Word</span><span class="sxs-lookup"><span data-stu-id="8dfbc-660">Word</span></span>

- <span data-ttu-id="8dfbc-661">我們已修正基本樣式並未以 [內文樣式] 更新的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-661">We fixed an issue which the base styles are not updated with Normal style.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-august-27"></a><span data-ttu-id="8dfbc-663">版本2008：8月27日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-663">Version 2008: August 27</span></span>
<span data-ttu-id="8dfbc-664">*版本2008（組建13127.20296）*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-664">*Version 2008 (Build 13127.20296)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-668">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-668">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="8dfbc-669">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-669">Outlook</span></span>

- <span data-ttu-id="8dfbc-670">修正導致使用者嘗試從次要帳戶建立會議邀請的問題，讓帳戶新增至他們的個人檔案，而不會看到空白的表格: 是欄位而不是其電子郵件地址。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-670">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>

- <span data-ttu-id="8dfbc-671">修正了新增共用信箱之後，導致使用者無法連線至公用資料夾的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-671">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>

- <span data-ttu-id="8dfbc-672">修正了當與雲端附件互動時，導致使用者偶爾當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-672">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>

- <span data-ttu-id="8dfbc-673">修正了編輯收件者時，導致使用者偶爾當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-673">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="8dfbc-674">修正導致使用者在使用壓縮模式時發生異常的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-674">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>

### <a name="word"></a><span data-ttu-id="8dfbc-675">Word</span><span class="sxs-lookup"><span data-stu-id="8dfbc-675">Word</span></span>

- <span data-ttu-id="8dfbc-676">此更改解決了一個問題，即在上一個協同合作的作業後，Microsoft Office 應用程式可能卡在未通知的儲存失敗狀態的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-676">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>

- <span data-ttu-id="8dfbc-677">我們已修正整體的 AutoOpen 在 AutoExec 之前執行的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-677">We fixed an issue where macro AutoOpen runs before AutoExec</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-august-25"></a><span data-ttu-id="8dfbc-679">版本 2008：8 月 25 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-679">Version 2008: August 25</span></span>
<span data-ttu-id="8dfbc-680">*版本 2008 (組建 13127.20268)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-680">*Version 2008 (Build 13127.20268)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="8dfbc-682">功能更新</span><span class="sxs-lookup"><span data-stu-id="8dfbc-682">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="8dfbc-683">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-683">Outlook</span></span>

- <span data-ttu-id="8dfbc-684">**依人員搜尋時，收到電子郵件的建議：** 當您在 Outlook 中輸入搜尋字詞時，您會在建議中看到出現最相關的電子郵件。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-684">**Receive email suggestions when searching by person.:** As you type your search terms in Outlook you'll receive the most relevant emails surfaced in the suggestions.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-687">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-687">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="8dfbc-688">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-688">Outlook</span></span>

- <span data-ttu-id="8dfbc-689">解決會導致使用者在回覆或撰寫新電子郵件時收到下列錯誤的問題：「這個網頁中的某些檔案不存在預期的位置，</span><span class="sxs-lookup"><span data-stu-id="8dfbc-689">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="8dfbc-690">請問您一定要下載嗎?</span><span class="sxs-lookup"><span data-stu-id="8dfbc-690">Do you want to download them anyway?</span></span> <span data-ttu-id="8dfbc-691">如果您確定網頁來自信任的來源，請按 [是]」</span><span class="sxs-lookup"><span data-stu-id="8dfbc-691">If you’re sure the Web page is from a trusted source, click Yes"</span></span>


### <a name="project"></a><span data-ttu-id="8dfbc-692">Project</span><span class="sxs-lookup"><span data-stu-id="8dfbc-692">Project</span></span>

- <span data-ttu-id="8dfbc-693">修正如果資源中定義了多個成本費率表，其餘成本並不一定都能正確地計算的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-693">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>


### <a name="word"></a><span data-ttu-id="8dfbc-694">Word</span><span class="sxs-lookup"><span data-stu-id="8dfbc-694">Word</span></span>

- <span data-ttu-id="8dfbc-695">解決會導致使用者在回覆或撰寫新電子郵件時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-695">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-august-17"></a><span data-ttu-id="8dfbc-697">版本2008：8月17日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-697">Version 2008: August 17</span></span>
<span data-ttu-id="8dfbc-698">*版本2008（組建13127.20208）*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-698">*Version 2008 (Build 13127.20208)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-700">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-700">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="8dfbc-701">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-701">Outlook</span></span>

- <span data-ttu-id="8dfbc-702">解決了當代理人在某些情況下遭到拒絕而導致會議無法從經理的行事曆中移除的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-702">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>


- <span data-ttu-id="8dfbc-703">解決了導致某些字元集的使用者在將 [智慧型連結] 新增至 SharePoint 檔案時，發現檔案名不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-703">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>


- <span data-ttu-id="8dfbc-704">解決了當您從 POP 帳戶刪除4或多個電子郵件時，已選取 [僅下載標題] 選項時，導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-704">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>


- <span data-ttu-id="8dfbc-705">解決的問題導致在搜尋控制項中無法顯示滑鼠右鍵功能表。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-705">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>



[//]: # (請勿移除 BUGDETAILS 內容尾)

## <a name="version-2008-august-11"></a><span data-ttu-id="8dfbc-707">版本 2008: 8月11日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-707">Version 2008: August 11</span></span>
<span data-ttu-id="8dfbc-708">*版本2008（組建13127.20164）*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-708">*Version 2008 (Build 13127.20164)*</span></span>

<span data-ttu-id="8dfbc-709">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="8dfbc-709">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-711">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-711">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="8dfbc-712">Access</span><span class="sxs-lookup"><span data-stu-id="8dfbc-712">Access</span></span>

- <span data-ttu-id="8dfbc-713">此修正會解決嘗試執行之前會產生「查詢太複雜」錯誤訊息的特定查詢的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-713">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>

- <span data-ttu-id="8dfbc-714">如果您已安装 Office 365，您就不需要再安装 [ACE 可再發行引擎]，就能在 Office 生態友善系統外公開 ACE。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-714">If you have Office 365 installed, you no longer need to install our ACE Redistributable Engine to expose ACE outside of the Office ecosystem.</span></span> <span data-ttu-id="8dfbc-715">因此，如果您使用的是 Office 365，您將不需要 [ACE 可再發行引擎]，也因此不會再遭遇此問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-715">Therefore, for those with Office 365, you will no longer need the ACE Redist Engine, and consequently you should not experience this issue.</span></span>

- <span data-ttu-id="8dfbc-716">已解决此問題 - 您現在可以使用 Office 的隨選即用應用程式外的 ODBC 驅動程式。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-716">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>

### <a name="excel"></a><span data-ttu-id="8dfbc-717">Excel</span><span class="sxs-lookup"><span data-stu-id="8dfbc-717">Excel</span></span>

- <span data-ttu-id="8dfbc-718">我們已修正若圖表數列順序已變更，與該數列對齊的對應核取方塊未隨著該數列重新排序的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-718">We fixed an issue where if the order of a chart series was changed, the corresponding checkbox aligned with the series was not reordered along with the series.</span></span>

- <span data-ttu-id="8dfbc-719">嘗試使用 LET () 函數儲存含有公式的檔案時，可能會發生錯誤。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-719">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>

- <span data-ttu-id="8dfbc-720">我們修正了當透過 VBA 啟用活頁簿的 [ForceFullCalculation] 時，圖表不一會更新的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-720">We fixed an issue where charts were not always updated as expected when "ForceFullCalculation" was enabled via VBA for the workbook.</span></span>

- <span data-ttu-id="8dfbc-721">我們已修正具有放射狀漸層填滿的影像複本與原始不符的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-721">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

### <a name="onenote"></a><span data-ttu-id="8dfbc-722">OneNote</span><span class="sxs-lookup"><span data-stu-id="8dfbc-722">OneNote</span></span>

- <span data-ttu-id="8dfbc-723">我們修正了當應用程式視窗調整為小尺寸時，[搜尋] 編輯方塊中的預留位置文字發生溢出的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-723">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>

### <a name="outlook"></a><span data-ttu-id="8dfbc-724">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-724">Outlook</span></span>

- <span data-ttu-id="8dfbc-725">我們修正了從相同的電子郵件網域在 Outlook 中建立多個設定檔會產生的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-725">We fixed an issue around creating multiple profiles in Outlookfrom the same email domain.</span></span>

- <span data-ttu-id="8dfbc-726">解决了導致使用 [共用行事曆改善] 的某些使用者無法查看剛新增的共用行事曆的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-726">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="8dfbc-727">解決了導致在 S/MIME 加密郵件的頁首中無法顯示鎖定圖示的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-727">Addressed an issue that caused the lock icon to fail to display in the header of S/MIME encrypted messages.</span></span>

- <span data-ttu-id="8dfbc-728">我們已修正，如果未核取 [下載共用資料夾]，共用行事曆會議 [回覆選項] 中缺少 [允許轉寄] 選項的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-728">We fixed an issue where the "Allow Forwarding" option was missing from the shared calendar meeting "Response Options" if Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="8dfbc-729">解決了當選取安全性對話方塊上的 [儲存] 選項時，導致使用者無法將 OneDrive 外部的 OneDrive 附件儲存至他們的本機電腦的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-729">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="8dfbc-730">我們已修正，即使使用者具有適當的列印權限也會在停用狀態下顯示列印按鈕的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-730">We fixed an issue that would display the print button in a disabled state even though the user had the appropriate print permissions.</span></span>

- <span data-ttu-id="8dfbc-731">解決了當以未加密郵件進行傳送時，會導致附件從 S/MIME 郵件中剝離出來的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-731">Addressed an issue that caused attachments to get stripped from S/MIME messages when sending as unencrypted.</span></span>

- <span data-ttu-id="8dfbc-732">解決了當純文字 S/MIME 郵件在傳送時發生亂碼的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-732">Addressed an issue that caused plain text S/MIME messages to become garbled when sending.</span></span>

- <span data-ttu-id="8dfbc-733">解決了當傳送未加密的 S/MIME 電子郵件時，會導致附件損毀的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-733">Addressed an issue that caused attachments to become corrupted when sending an S/MIME email unencrypted.</span></span>

- <span data-ttu-id="8dfbc-734">解決了當寄件者授與 [另存為] 許可權時，會導致收件者無法儲存許可權保護郵件的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-734">Addressed an issue that cause recipients to be unable to save rights protected messages even when the save as permission was granted by the sender.</span></span>

- <span data-ttu-id="8dfbc-735">這解決了當使用者從檢查程式視窗回覆受到數位版權管理的郵件，卻沒有所回覆郵件的擁有者權限時，會導致使用者會無法新增簽名的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-735">This fix addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user did not have Owner permissions on the message being replied to.</span></span>

- <span data-ttu-id="8dfbc-736">此修正會解決導致 Outlook 無法在 markdown 內容中正確顯示換行符號的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-736">This fix addresses an issue that was causing Outlook to fail to display line breaks properly in markdown content.</span></span>

- <span data-ttu-id="8dfbc-737">解決了某些 [進階搜尋] 選項標籤在某些語言中會被截斷的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-737">Addressed an issue that caused the labels for some Advanced Search options to be truncated in some languages.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8dfbc-738">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8dfbc-738">PowerPoint</span></span>

- <span data-ttu-id="8dfbc-739">我們已修正具有放射狀漸層填滿的影像複本與原始不符的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-739">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

- <span data-ttu-id="8dfbc-740">我們已修正 PowerPoint 中的 [表單] 按鈕在不允許存取 Office Store 時不會允許建立表單的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-740">We fixed an issue where the Forms button in PowerPoint did not allow the creation of Forms when access to Office Store was not permitted.</span></span>

### <a name="project"></a><span data-ttu-id="8dfbc-741">Project</span><span class="sxs-lookup"><span data-stu-id="8dfbc-741">Project</span></span>

- <span data-ttu-id="8dfbc-742">我們修正了 [工作委員會] 畫面中列出的工作未與 [指派資源] 對話方塊中的任務同步處理的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-742">We fixed an issue where tasks listed in the Task Board view were not in sync with those in the Assign Resources dialog.</span></span>

- <span data-ttu-id="8dfbc-743">我們修正了如果您嘗試從 Project 將 PDF/XPS 儲存至 SharePoint 文件庫，沒有發生任何動作的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-743">We fixed an issue where if you tried to save a PDF/XPS from Project to a SharePoint document library, nothing would happen.</span></span>

- <span data-ttu-id="8dfbc-744">我們修正了當您複製並貼上具有多個相關性的工作，並非所有相關性都能正確複製的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-744">We fixed an issue where if you copied & pasted a task that had multiple dependencies, not all dependencies were copied correctly.</span></span>

- <span data-ttu-id="8dfbc-745">已修正針對 SharePoint 工作清單，第二個索引標籤上的功能區按鈕可能會停用的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-745">Fixed an issue where for a SharePoint tasks list, the ribbon buttons on the second tab may be disabled.</span></span>

### <a name="skype"></a><span data-ttu-id="8dfbc-746">Skype</span><span class="sxs-lookup"><span data-stu-id="8dfbc-746">Skype</span></span>

- <span data-ttu-id="8dfbc-747">將跳舞表情符號膚色變更為中性色彩</span><span class="sxs-lookup"><span data-stu-id="8dfbc-747">Changed dancing emoticon skin tone to neutral color</span></span>

### <a name="visio"></a><span data-ttu-id="8dfbc-748">Visio</span><span class="sxs-lookup"><span data-stu-id="8dfbc-748">Visio</span></span>

- <span data-ttu-id="8dfbc-749">在此修正程序完成之后，如果使用者在任何機制（在此情况下是透過增益集）停止執行刪除命令，內存便不會泄漏，而且也不會影響整台電腦。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-749">After this fix, if the user halted the execution of delete command by any mechanism in between (in this case it was through add-in) the memory won't leak and the whole machine won't be impacted.</span></span>

### <a name="word"></a><span data-ttu-id="8dfbc-750">Word</span><span class="sxs-lookup"><span data-stu-id="8dfbc-750">Word</span></span>

- <span data-ttu-id="8dfbc-751">我們已修正將某些文字及影像貼到 [註解] 方塊之後，Word 停止回應的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-751">We fixed an issue where Word would stop responding after pasting some text and an image in to a comments box.</span></span>

- <span data-ttu-id="8dfbc-752">我們已修正具有放射狀漸層填滿的影像複本與原始不符的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-752">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

- <span data-ttu-id="8dfbc-753">我們修正了當應用程式視窗調整為小尺寸時，[搜尋] 編輯方塊中的預留位置文字發生溢出的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-753">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>

- <span data-ttu-id="8dfbc-754">我們已修正如果新增註解來追蹤變更，將會意外開啟 [修訂] 窗格的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-754">We fixed an issue where if a comment was added to track a change, the revisions pane would unexpectedly open.</span></span>

- <span data-ttu-id="8dfbc-755">我們修正了當焦點位於註解文字方塊中時，[編輯器] 命令會被停用的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-755">We fixed an issue where the Editor command was disabled when the focus was in a comment text box.</span></span>

- <span data-ttu-id="8dfbc-756">我們修正了當焦點位於註解文字方塊中時，[顯示標記] 命令會被停用的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-756">We fixed an issue where the Show Markup command was disabled when the focus was in a comment text box.</span></span>

- <span data-ttu-id="8dfbc-757">我們已修正刪除最後一個註解後，[新增批註] 按鈕停用的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-757">We fixed an issue where the 'New comment' button would be disabled after deleting the last comment.</span></span>

- <span data-ttu-id="8dfbc-758">我們已修正 [追蹤修訂] 中的 [特定人員] 選項已停用的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-758">We fixed an issue where the 'Specific People' option for Track Changes was disabled.</span></span>

- <span data-ttu-id="8dfbc-759">我們已修正文件連結未透過 [插入] > [連結] 下拉式功能表插入 [註解] 方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-759">We fixed an issue where links to documents were not being inserted to the comments box via the Insert -> Link dropdown.</span></span>

- <span data-ttu-id="8dfbc-760">我們已修正了開啟 HTML 檔案時偶爾停止回應的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-760">We fixed an occasional hang while opening HTML files.</span></span>

- <span data-ttu-id="8dfbc-761">我們修正了自訂 XML 中的註解狀態在開啟文件時可能會遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-761">We fixed an issue in custom XML where the state of comments may be lost when opening the document.</span></span>

- <span data-ttu-id="8dfbc-762">我們已修正 VBA 超連結集合中的超連結計數，在新增包含超連結的影像之後，未正確反覆運算的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-762">We fixed an issue where the hyperlink count in the VBA hyperlinks collection was not iterating correctly after adding an image containing a hyperlink.</span></span>

- <span data-ttu-id="8dfbc-763">針對舊版非網頁服務的 [共用] 窗格，在開啟 [共用] 窗格下關閉文件時，可能會導致當機。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-763">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash.</span></span> <span data-ttu-id="8dfbc-764">這個問題現在已經修正。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-764">This is now fixed.</span></span>

- <span data-ttu-id="8dfbc-765">我們修正了使用者從工作列開啟新應用程式視窗，並建立新的空白檔時，會造成額外檔案建立的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-765">We fixed an issue where after the user opened a new app window from the taskbar and created a new blank document, additional files were created.</span></span>

- <span data-ttu-id="8dfbc-766">我們修正了當使用者在編輯文件，但是許可權遺失時，我們並未通知使用者必須重新驗證的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-766">We fixed an issue where if a user was editing a document but had lost permissions, we were not notifying the user that they had to re-authenticate.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-august-05"></a><span data-ttu-id="8dfbc-768">版本 2007：8 月 5 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-768">Version 2007: August 05</span></span>
<span data-ttu-id="8dfbc-769">*版本 2007 (組建 13029.20344)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-769">*Version 2007 (Build 13029.20344)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)



[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-773">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-773">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="8dfbc-774">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-774">Outlook</span></span>

- <span data-ttu-id="8dfbc-775">解決會導致 Outlook 無法擷取搜尋建議的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-775">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>


- <span data-ttu-id="8dfbc-776">解決會導致使用者在擷取角色資訊時有時候會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-776">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>


### <a name="project"></a><span data-ttu-id="8dfbc-777">Project</span><span class="sxs-lookup"><span data-stu-id="8dfbc-777">Project</span></span>

- <span data-ttu-id="8dfbc-778">修正無法開啟已進入錯誤狀態的專案的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-778">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-july-29"></a><span data-ttu-id="8dfbc-780">版本 2007：7 月 29 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-780">Version 2007: July 29</span></span>
<span data-ttu-id="8dfbc-781">*版本 2007 (組建 13029.20308)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-781">*Version 2007 (Build 13029.20308)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="8dfbc-783">功能更新</span><span class="sxs-lookup"><span data-stu-id="8dfbc-783">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="8dfbc-784">Excel</span><span class="sxs-lookup"><span data-stu-id="8dfbc-784">Excel</span></span>

- <span data-ttu-id="8dfbc-785">**使用資料類型從 Power BI 取得組織資料：** 現在，來自 Power BI 的 Excel 資料類型將推出給使用 Office 365 E5/A5 或 Microsoft 365 E5/A5 之組織的測試人員使用。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-785">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 E5/A5 or Microsoft 365 E5/A5.</span></span> <span data-ttu-id="8dfbc-786">取得您所需的資訊，輕鬆地重新整理，對許多日常工作流程而言至關重要。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-786">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="8dfbc-787">我們允許您透過 Excel 中的資料類型從 Power BI 存取公司或組織資訊，從而擴充您在試算表中引入連結資訊的能力。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-787">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="8dfbc-788">深入了解</span><span class="sxs-lookup"><span data-stu-id="8dfbc-788">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="8dfbc-789">在[部落格文章](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8dfbc-789">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="8dfbc-790">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-790">Outlook</span></span>

- <span data-ttu-id="8dfbc-791">**挑選搜尋的位置：** 新的搜尋範圍下拉式清單，可讓您更輕鬆地修改搜尋，並在目前資料夾和目前信箱之間切換。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-791">**Pick where to search:** The new search scope drop down allows you to more easily modify your search and switch between Current Folder and Current Mailbox.</span></span> <span data-ttu-id="8dfbc-792">感謝每個在 [即將推出] 為 [頂極體驗] 的 新 [搜尋] 提供意見反應的人。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-792">Thank you to everyone in Coming Soon who provided feedback on the new Search at Top experience.</span></span> <span data-ttu-id="8dfbc-793">因為有這份意見反應，才有這項設計與更新！</span><span class="sxs-lookup"><span data-stu-id="8dfbc-793">This design and update came out of that feedback!</span></span>

### <a name="word"></a><span data-ttu-id="8dfbc-794">Word</span><span class="sxs-lookup"><span data-stu-id="8dfbc-794">Word</span></span>

- <span data-ttu-id="8dfbc-795">**以新式註解更輕鬆地進行共同作業：** 新增註解到物件、@提及 同事，並解決註解執行緒，以獲得更佳的共同作業體驗。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-795">**Better collaboration with modern comments:** Add comments to objects, @mention colleagues, and resolve comment threads for a better collaboration experience.</span></span> [<span data-ttu-id="8dfbc-796">深入了解</span><span class="sxs-lookup"><span data-stu-id="8dfbc-796">Learn more</span></span>](https://support.office.com/article/8d3f868a-867e-4df2-8c68-bf96671641e2)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-799">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-799">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="8dfbc-800">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-800">Outlook</span></span>

- <span data-ttu-id="8dfbc-801">解決了導致 CLP 使用者在從受保護的內容切換到未受保護之回復的 [寄件者] 位址時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-801">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>


- <span data-ttu-id="8dfbc-802">解決了導致 [排程小幫手] 頁面無法顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-802">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>


- <span data-ttu-id="8dfbc-803">解決了事件通知提醒中導致格式設定問題的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-803">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-july-27"></a><span data-ttu-id="8dfbc-805">版本 2007：7 月 27 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-805">Version 2007: July 27</span></span>
<span data-ttu-id="8dfbc-806">*Version 2007 (組建 13029.20292)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-806">*Version 2007 (Build 13029.20292)*</span></span>
* <span data-ttu-id="8dfbc-807">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-807">Various bugs and performance fixes.</span></span>

## <a name="version-2007-july-20"></a><span data-ttu-id="8dfbc-808">版本 2007：7 月 20 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-808">Version 2007: July 20</span></span>
<span data-ttu-id="8dfbc-809">*版本2007 (組建 13029.20236)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-809">*Version 2007 (Build 13029.20236)*</span></span>
* <span data-ttu-id="8dfbc-810">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-810">Various bugs and performance fixes.</span></span>

## <a name="version-2007-july-15"></a><span data-ttu-id="8dfbc-811">版本 2007：7 月 15 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-811">Version 2007: July 15</span></span>
<span data-ttu-id="8dfbc-812">*版本 2007 (組建 13029.20200)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-812">*Version 2007 (Build 13029.20200)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="8dfbc-814">功能更新</span><span class="sxs-lookup"><span data-stu-id="8dfbc-814">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="8dfbc-815">Excel</span><span class="sxs-lookup"><span data-stu-id="8dfbc-815">Excel</span></span>

- <span data-ttu-id="8dfbc-816">**在 Excel 中製作精美的 Visio 圖表：** 將資料放在工作表上，以建立流程圖或組織圖。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-816">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="8dfbc-817">深入了解</span><span class="sxs-lookup"><span data-stu-id="8dfbc-817">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-820">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-820">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="8dfbc-821">Access</span><span class="sxs-lookup"><span data-stu-id="8dfbc-821">Access</span></span>

- <span data-ttu-id="8dfbc-822">我們已修正在重新整理連結的 SQL 資料表時，連結資料表管理員會提示您輸入主要索引鍵的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-822">We fixed an issue where the linked table manager would prompt a primary key if a linked SQL table was refreshed.</span></span>

- <span data-ttu-id="8dfbc-823">我們已修正 [查詢編輯器] 中的查詢捲出畫面的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-823">We fixed an issue where queries in the Query Editor scrolled out of view.</span></span>

- <span data-ttu-id="8dfbc-824">我們已修正執行查詢的時間大約比預期完成時間兩倍久的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-824">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

- <span data-ttu-id="8dfbc-825">我們已修正導致 Microsoft Access 無法識別連結的 SQL Server 資料表中的識別資料行的問題，這可能會導致不正確地將資料列報告為已刪除。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-825">We fixed an issue that caused Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which could cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="8dfbc-826">Excel</span><span class="sxs-lookup"><span data-stu-id="8dfbc-826">Excel</span></span>

- <span data-ttu-id="8dfbc-827">我們已修正非 HTTP 或 HTTPS 型 URL 未顯示在 [最近用過的] 清單中的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-827">We fixed an issue where URLs that were not http or https based were not being displayed in the Most Recently Used list.</span></span>

- <span data-ttu-id="8dfbc-828">已修正在載入含有多張分頁預覽的活頁簿時，可能會發生錯誤或當機問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-828">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>

- <span data-ttu-id="8dfbc-829">我們修正以下問題：在特定版本 Excel 中建立的資料模型表格無法在 [表格預覽] 中看到，即使與該表相關聯的查詢尚未編輯。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-829">We fixed an issue where data model tables created in certain versions of Excel could not be seen in 'Table Preview' even though the query associated with the table had not been edited.</span></span>

- <span data-ttu-id="8dfbc-830">在 [定義名稱\套用名稱] 對話方塊中停用 [忽略相對/絕對] 參照會導致公式無法使用。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-830">Ignore Relative/Absolute' references in the Define Name \ Apply Names dialog would cause formulas to not work.</span></span>

- <span data-ttu-id="8dfbc-831">我們已修正將活頁簿儲存至 SharePoint/OneDrive 時，會導致自訂功能區索引標籤 CustomUI XML 遭移除的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-831">We fixed an issue where CustomUI XML for a custom ribbon tab was removed when saving a workbook to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="8dfbc-832">我們已修正當建議以唯讀方式使用檔案時，活頁簿處於唯讀狀態的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-832">We fixed an issue where workbooks were read-only when the file only had read-only recommended.</span></span>

- <span data-ttu-id="8dfbc-833">已修正在載入含有多張分頁預覽的活頁簿時，可能會發生錯誤或當機問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-833">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>

- <span data-ttu-id="8dfbc-834">我們已修正雷達圖的主要格線無法正確設定格式的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-834">We fixed an issue where the major gridlines of radar charts could not be formatted correctly.</span></span>


- <span data-ttu-id="8dfbc-835">我們已修正清除 [進階資料篩選] 可能會遺失表格格式設定的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-835">We fixed an issue where clearing an advanced data filter could lose table formatting.</span></span>


- <span data-ttu-id="8dfbc-836">我們已修正嵌入式 PDF 文件的完整路徑顯示在文件標題，而不只是檔案名稱的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-836">We fixed an issue where the full path of an embedded PDF document would show in the document caption rather than just the filename.</span></span>


- <span data-ttu-id="8dfbc-837">我們已修正停用 Wolfram 雲端連接器之後，儲存並重新開啟 Excel 活頁簿可能會導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-837">We fixed an issue where after disabling the Wolfram cloud connector and then saving and re-opening an Excel workbook, could result in a crash.</span></span>


- <span data-ttu-id="8dfbc-838">我們已修正啟動 Excel 時啟用 [規劃求解] 增益集將導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-838">We fixed an issue where booting Excel with the Solver add-in enabled would result in a crash.</span></span>


### <a name="outlook"></a><span data-ttu-id="8dfbc-839">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-839">Outlook</span></span>

- <span data-ttu-id="8dfbc-840">我們已修正如果在 [收件者] 行上有超過 130 個收件者，Outlook 會當機的問題，且我們也改善了呈現文字的效能。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-840">We fixed an issue where Outlook would hang if there were over 130 recipients on the 'To' line and we also improved the performance of rendering the text.</span></span>


- <span data-ttu-id="8dfbc-841">我們已修正以下問題：當使用多個不同解析度的監視器時，輸入法編輯器 (IEM) 視窗會覆蓋透過 IME 輸入的文字。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-841">We fixed an issue where the Input Method Editor (IME) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>


- <span data-ttu-id="8dfbc-842">我們已修正「待辦事項列」中跨越兩天以上的活動，在後續的所有日期中顯示相同結束時間的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-842">We fixed an issue in the 'To Do Bar' where events that spanned more than two days, displayed the same end time for all subsequent days.</span></span>


- <span data-ttu-id="8dfbc-843">解決會導致使用者看到他們透過拖放附件，以複製到其檔案系統所建立附件的建立日期設為 4501 年 1 月 1 日的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-843">Addresses an issue that caused users to see the creation date of attachments that they copied to their file system via drag and drop getting set to January 1, 4501.</span></span>


- <span data-ttu-id="8dfbc-844">我們已修正使用者無法使用通訊群組清單中的「傳送為」或「代理傳送者」的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-844">We fixed an issue where users were unable to 'Send As' or 'Send on behalf' of a distribution list.</span></span>


- <span data-ttu-id="8dfbc-845">解決在編輯經理行事曆上的現有行事曆約會時，導致代理人收到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-845">Addresses an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>


- <span data-ttu-id="8dfbc-846">我們已修正導致使用者在關閉先前儲存的約會時看到下列錯誤的問題：「項目無法儲存，因為已被其他使用者或已在其他視窗中變更過。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-846">We fixed an issue that caused users to see the following error when closing an appointment that was previously saved "The item cannot be saved because it was changed by another user or in another window.</span></span> <span data-ttu-id="8dfbc-847">您要在預設資料夾為這個項目建立複本?」</span><span class="sxs-lookup"><span data-stu-id="8dfbc-847">Do you want to make a copy in the default folder for the item?"</span></span>


- <span data-ttu-id="8dfbc-848">解決會導致若「未」核取 [下載共用資料夾]，共用行事曆會議的 [回應選項] 中會遺失 [允許轉寄] 選項的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-848">Addresses an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>


- <span data-ttu-id="8dfbc-849">解決選取安全性對話方塊上的 [儲存] 選項時，會導致使用者無法將來自其租用戶外部的 OneDrive 附件儲存至其本機電腦的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-849">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>


- <span data-ttu-id="8dfbc-850">我們已修正導致 Outlook 使用者在使用共用行事曆後，在幾分鐘內訊息清單停止更新的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-850">We fixed an issue that caused users of Outlook to see their message list stop updating for several minutes after using shared calendars.</span></span>


- <span data-ttu-id="8dfbc-851">我們已修正行事曆提醒無法針對一週內即將到來的會議顯示確切時間的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-851">We fixed an issue that prevented calendar reminders from showing exact times for meetings coming up in less than a week.</span></span> 


- <span data-ttu-id="8dfbc-852">我們已修正在郵件中插入影像內嵌，然後將郵件儲存為草稿將會重新調整影像大小的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-852">We fixed an issue where inserting an image inline in a message, then saving the message as a draft would result in a resizing of the image.</span></span>


- <span data-ttu-id="8dfbc-853">我們已修正在編輯主旨之後，導致 NDR 郵件的本文從 Unicode 變更為 ASCII 的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-853">We fixed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>


- <span data-ttu-id="8dfbc-854">我們已修正迷你行事曆中的日期無法針對日本使用者顯示粗體的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-854">We fixed an issue where dates in the mini calendar failed to display in bold for users in Japan.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="8dfbc-855">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8dfbc-855">PowerPoint</span></span>

- <span data-ttu-id="8dfbc-856">我們已修正在即時共同撰寫工作階段期間，使用者的目前狀態色彩指示器無法在共同撰寫文件庫中重新整理的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-856">We fixed an issue where a user's presence color indicator was not getting refreshed in the co-authoring gallery during a live co-authoring session.</span></span>


- <span data-ttu-id="8dfbc-857">我們已修正將 HTML 貼到投影片上的文字區域時，會改為貼上投影片最上方所建立的文字方塊中的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-857">We fixed an issue where pasting HTML to a text area on a slide would instead get pasted into a text box created at the top of the slide.</span></span>


- <span data-ttu-id="8dfbc-858">我們已修正在 [簡報者檢視畫面] 中選取所有投影片、使用 Alt+Tab 退出 [簡報者檢視畫面] 並返回投影片放映，然後按一下 [結束放映] 時，將導致未處理例外狀況的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-858">We fixed an issue where selecting all slides in Presenter View, then exiting Presenter View using Alt+Tab and returning to the slide show and clicking 'End Show' would result in an unhandled exception.</span></span>


### <a name="project"></a><span data-ttu-id="8dfbc-859">Project</span><span class="sxs-lookup"><span data-stu-id="8dfbc-859">Project</span></span>

- <span data-ttu-id="8dfbc-860">已修正無法將從 Project 將 PDF/XPS 儲存至 SharePoint 文件庫的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-860">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>


- <span data-ttu-id="8dfbc-861">修正 URL 以 .com 結尾時，無法從 Project Web App 在 Project 傳統型用戶端開啟專案的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-861">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>


- <span data-ttu-id="8dfbc-862">我們已修正 Project 在開啟特定 XML 檔案時可能當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-862">We fixed an issue where Project may crash when opening certain XML files.</span></span>


- <span data-ttu-id="8dfbc-863">我們已修正 URL 以 '.com' 結尾時，無法從 Project Web App 在 Project 傳統型用戶端開啟專案的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-863">We fixed an issue where projects couldn't be opened in the Project desktop client from the Project Web App if the URL ended in '.com'.</span></span>


- <span data-ttu-id="8dfbc-864">已修正問題：如果您貼上具有多個相關性的工作，並不會正確複製所有相關性。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-864">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>


- <span data-ttu-id="8dfbc-865">已修正 [指派資源] 對話方塊中選取的工作與工作面板檢視中所選工作不同的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-865">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>


- <span data-ttu-id="8dfbc-866">我們已修正當專案摘要工作，或專案 [開始/工作] 欄位變更時，ProjectBeforeTaskChange 事件無法觸發的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-866">We fixed an issue where the ProjectBeforeTaskChange event didn't fire when there was a change to the project summary task, either the project start/task field.</span></span>


- <span data-ttu-id="8dfbc-867">我們已修正以下問題：如果固定工期的任務已 100% 完成，但未指定 [實際完成日期]，則任務的完成 % 將顯示為低於 100%。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-867">We fixed an issue where if Fixed Duration tasks are at 100% complete but the Actual Finish is not specified, the Task % Complete would display as less than 100%.</span></span>

- <span data-ttu-id="8dfbc-868">我們已修正以下問題：比較基準重設或更新可能會變更時間分段預算成本/工時資源，且比較基準反映不正確的預算值。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-868">We fixed an issue where a baseline reset or update could change time-phased budget cost/work resources and the baseline could reflect incorrect budget values.</span></span>


- <span data-ttu-id="8dfbc-869">我們已修正政府社群雲端中的 Project Planner 連結已停用的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-869">We fixed an issue where Project Planner links in Government Community Cloud environments had been disabled.</span></span>


- <span data-ttu-id="8dfbc-870">我們已修正如果文件庫處於新式模式，您無法從 SharePoint 文件庫開啟 Project 檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-870">We fixed an issue where you couldn't open a Project file from a SharePoint document library if the library was in modern mode.</span></span>


### <a name="word"></a><span data-ttu-id="8dfbc-871">Word</span><span class="sxs-lookup"><span data-stu-id="8dfbc-871">Word</span></span>

- <span data-ttu-id="8dfbc-872">我們已修正使用 Office 功能區中的 [清除格式設定] 按鈕清除 [註解] 窗格中的格式設定時，無法運作的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-872">We fixed an issue where the ability to clear formatting within the Comments pane via the Clear Formatting button in the Office Ribbon was not working.</span></span>


- <span data-ttu-id="8dfbc-873">我們已修正將插入可縮放向量圖形 (SVG) 中的文字插入到 Word、Excel 或 PowerPoint 檔案、儲存並關閉檔案，然後重新開啟檔案後，難以辨識的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-873">We fixed an issue where text inserted in a Scalable Vector Graphic (SVG) was illegible after inserting it in a Word, Excel, or PowerPoint file, saving and closing the file, and then re-opening the file.</span></span>


- <span data-ttu-id="8dfbc-874">我們已修正當尺規未顯示時變更表格大小，導致在背景中執行其他應用程式開始閃爍的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-874">We fixed an issue where changing the size of a table when the ruler is not displayed caused other applications running in the background to start flashing.</span></span>


- <span data-ttu-id="8dfbc-875">我們已修正在共同撰寫模式中，註解回覆有時候不會顯示在 [註解] 窗格中，而是顯示在 [修訂] 窗格中的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-875">We fixed an issue where in co-authoring mode, comment replies would sometimes not show up in the comments pane but would be visible in the revisions pane.</span></span>


- <span data-ttu-id="8dfbc-876">我們已修正在共同撰寫模式期間，當發生合併衝突且使用者已選取放棄變更時，我們不再顯示儲存或捨棄變更選項的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-876">We fixed an issue during co-authoring mode when there is a merge conflict and the user has already chosen to discard changes, we no longer display the option to save or discard changes.</span></span>


- <span data-ttu-id="8dfbc-877">我們已修正 HTML 超連結色彩無法正確呈現的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-877">We fixed an issue where the HTML hyperlink color was not being rendered correctly.</span></span>


- <span data-ttu-id="8dfbc-878">我們已修正以下問題：如果 Word 經常開啟的文件清單多於 50 個，然後儲存並開啟文件後，即使該文件沒有進行任何修訂，也會顯示歷程記錄。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-878">We fixed an issue where if Word had a list of more than 50 frequently opened documents, then after saving and opening a document, a revision history would be displayed even though no revisions were made to that document.</span></span>


- <span data-ttu-id="8dfbc-879">我們已修正共同撰寫期間的自動儲存問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-879">We fixed in issue with autosave during coauthoring.</span></span>


- <span data-ttu-id="8dfbc-880">我們已修正一個問題，當嘗試使用新名稱儲存包含巨集的檔案時，無論使用者輸入什麼名稱，都會導致該檔案以 .docx 副檔名和檔案名稱 'WRO0004.docx' 儲存，進而導致文件無法使用。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-880">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with a .docx extension and the filename 'WRO0004.docx', regardless of what the user entered, rendering the document unusable.</span></span>


### <a name="office-suite"></a><span data-ttu-id="8dfbc-881">Office 套件</span><span class="sxs-lookup"><span data-stu-id="8dfbc-881">Office Suite</span></span>

- <span data-ttu-id="8dfbc-882">關閉 Office 檔案時，計時問題可能會導致當機</span><span class="sxs-lookup"><span data-stu-id="8dfbc-882">A timing issue could cause a crash when closing office files</span></span>

- <span data-ttu-id="8dfbc-883">此問題的修正程式是確保服務正確計算新增的產品。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-883">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="8dfbc-884">我們已篩選出新增的產品 (確保它們同時存在於新的設定中)，並將它們新增到現有產品發行識別碼的結尾。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-884">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-july-09"></a><span data-ttu-id="8dfbc-886">版本 2006：7 月 09 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-886">Version 2006: July 09</span></span>
<span data-ttu-id="8dfbc-887">*版本2006（組建13001.20384）*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-887">*Version 2006 (Build 13001.20384)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="8dfbc-889">功能更新</span><span class="sxs-lookup"><span data-stu-id="8dfbc-889">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="8dfbc-890">Excel</span><span class="sxs-lookup"><span data-stu-id="8dfbc-890">Excel</span></span>

- <span data-ttu-id="8dfbc-891">**建立 PDF 連線：** 連線至、匯入、重新整理 PDF 中的資料。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-891">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="8dfbc-892">深入了解</span><span class="sxs-lookup"><span data-stu-id="8dfbc-892">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="8dfbc-893">**建立變數以在公式中使用：** 使用 LET 函數改善效能、可讀性及可組合性。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-893">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="8dfbc-894">此函數可讓您在新的或現有的公式中建立命名變數。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-894">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="8dfbc-895">深入了解</span><span class="sxs-lookup"><span data-stu-id="8dfbc-895">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="8dfbc-896">在[部落格文章](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8dfbc-896">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

- <span data-ttu-id="8dfbc-897">**Excel 中的鍵盤快速鍵：** Excel 升級的鍵盤快速鍵</span><span class="sxs-lookup"><span data-stu-id="8dfbc-897">**Keyboard shortcuts in Excel:** Updated keyboard shortcuts for Excel</span></span>

### <a name="outlook"></a><span data-ttu-id="8dfbc-898">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-898">Outlook</span></span>

- <span data-ttu-id="8dfbc-899">**在 Outlook 中使用 [快速投票] 建立投票：** 輕鬆建立投票，收集投票，並查看電子郵件中的結果 [深入瞭解](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="8dfbc-899">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="8dfbc-900">**將圖片作為電子郵件的一部分傳送時，讓圖片保持高畫質：** 一個新 Outlook 設定，可讓您在隨著電子郵件內容傳送圖片時限制圖片壓縮</span><span class="sxs-lookup"><span data-stu-id="8dfbc-900">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-903">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-903">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="8dfbc-904">Access</span><span class="sxs-lookup"><span data-stu-id="8dfbc-904">Access</span></span>

- <span data-ttu-id="8dfbc-905">此問題已解決，您應該能成功地將包含身分識別(例如 [自動編號]) 欄位的連結的 SQL 資料表插入到 Access 中。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-905">This issue is resolved, and you should expect to be able to successfully insert linked SQL tables that include an identity (e.g. autonumber) field into Access.</span></span>

### <a name="excel"></a><span data-ttu-id="8dfbc-906">Excel</span><span class="sxs-lookup"><span data-stu-id="8dfbc-906">Excel</span></span>

- <span data-ttu-id="8dfbc-907">已修正當您從帳戶登出時，嘗試建立資料連線時，可能會發生的當機問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-907">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

### <a name="outlook"></a><span data-ttu-id="8dfbc-908">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-908">Outlook</span></span>

- <span data-ttu-id="8dfbc-909">解決了當選取安全性對話方塊上的 [儲存] 選項時，導致使用者無法將 OneDrive 外部的 OneDrive 附件儲存至他們的本機電腦的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-909">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="office-suite"></a><span data-ttu-id="8dfbc-910">Office 套件</span><span class="sxs-lookup"><span data-stu-id="8dfbc-910">Office Suite</span></span>

- <span data-ttu-id="8dfbc-911">我們會將新的 AppV51 向後移，以修正先前 AppV51 中的回歸。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-911">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="8dfbc-912">當您啟用增益集，而登錄 TabProcGrowth 值為 REG_SZ 類型且其值為 "0"時，辦公主機視窗會當機。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-912">he office host was crashing in windows, when an add-in is being activated while the registry TabProcGrowth value is REG_SZ type and with value "0".</span></span>  <span data-ttu-id="8dfbc-913">這個登錄 TabProcGrowth 值可以在下列4個路徑中的任何一個中： HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main HKEY_CURRENT_USER \Software\Policies\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINE \Software\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINER \Software\Policies\Microsoft\Internet Explorer\Main 此變更將修正此問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-913">That registry TabProcGrowth value can be under any one of 4 paths: HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main HKEY_CURRENT_USER\Software\Policies\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINE\Software\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINER\Software\Policies\Microsoft\Internet Explorer\Main This change would fix this issue.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-june-25"></a><span data-ttu-id="8dfbc-915">版本 2006：6 月 25 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-915">Version 2006: June 25</span></span>
<span data-ttu-id="8dfbc-916">*版本2006（組建13001.20266）*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-916">*Version 2006 (Build 13001.20266)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="8dfbc-918">功能更新</span><span class="sxs-lookup"><span data-stu-id="8dfbc-918">Feature updates</span></span>
### <a name="visio"></a><span data-ttu-id="8dfbc-919">Visio</span><span class="sxs-lookup"><span data-stu-id="8dfbc-919">Visio</span></span>

- <span data-ttu-id="8dfbc-920">**在 Excel 中製作精美的 Visio 圖表：** 根據工作表上的資料，建立流程圖或組織圖。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-920">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart based on data in a worksheet.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-923">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-923">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="8dfbc-924">Access</span><span class="sxs-lookup"><span data-stu-id="8dfbc-924">Access</span></span>

- <span data-ttu-id="8dfbc-925">這個問題已解決。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-925">This problem is now resolved.</span></span> <span data-ttu-id="8dfbc-926">如果您在此流程中遇到更多問題，請告知小組。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-926">Please let the team know if you experience more issues with this process.</span></span>


### <a name="outlook"></a><span data-ttu-id="8dfbc-927">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-927">Outlook</span></span>

- <span data-ttu-id="8dfbc-928"><span style="display:inline !important;">解決一個問題，該問題導致使用者看到<span>&nbsp;</span></span><span style="box-sizing:border-box;font-family:Calibri, sans-serif;font-size:14.6667px;display:inline !important;">附件的建立日期&nbsp; 他們透過托放方式將該附件複製到其檔案系統&nbsp; 該建立日期設於 4501年1月1日。</span></span><span class="sxs-lookup"><span data-stu-id="8dfbc-928"><span style="display:inline !important;">Addresses an issue that caused users to see<span>&nbsp;</span></span><span style="box-sizing:border-box;font-family:Calibri, sans-serif;font-size:14.6667px;display:inline !important;">the creation date of&nbsp; attachments that they copied to their file system via drag and drop getting&nbsp; set to January 1, 4501.</span></span></span><br>


- <span data-ttu-id="8dfbc-929"><span style="font-family:&quot;Segoe UI&quot;, system-ui, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, sans-serif;display:inline !important;">解決導致 [共用行事曆] 改善的使用者查看行事曆失敗的問題。</span></span><span class="sxs-lookup"><span data-stu-id="8dfbc-929"><span style="font-family:&quot;Segoe UI&quot;, system-ui, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, sans-serif;display:inline !important;">Addresses an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span></span><br>


- <span data-ttu-id="8dfbc-930"><span style="display:inline !important;">解決導致使用者看到 Outlook 持續提示他們執行收件匣修復工具的問題。</span></span><span class="sxs-lookup"><span data-stu-id="8dfbc-930"><span style="display:inline !important;">Addresses an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span></span><br>


- <span data-ttu-id="8dfbc-931"><span style="display:inline !important;">解決導致在[建議功能]中尋找功能沒有結果並未留給使用者選項以提交新功能點子的問題。</span></span><span class="sxs-lookup"><span data-stu-id="8dfbc-931"><span style="display:inline !important;">Addresses an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span></span><br>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-june-18"></a><span data-ttu-id="8dfbc-933">版本 2006：6 月 18 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-933">Version 2006: June 18</span></span>
<span data-ttu-id="8dfbc-934">*版本2006（組建13001.20198）*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-934">*Version 2006 (Build 13001.20198)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="8dfbc-936">功能更新</span><span class="sxs-lookup"><span data-stu-id="8dfbc-936">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="8dfbc-937">Excel</span><span class="sxs-lookup"><span data-stu-id="8dfbc-937">Excel</span></span>



- <span data-ttu-id="8dfbc-938">**儲存至 [釘選資料夾]：** 釘選您的資料夾可讓您更輕鬆地儲存 Office 檔案，我們收到意見反應，使用者希望能在新檔案儲存時可以在可用的資料夾上有更多控制權。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-938">**Save to Pinned Folders:** Pin your folders makes saving Office files easier We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="8dfbc-939">我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-939">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="8dfbc-940">這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-940">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> <br /><span data-ttu-id="8dfbc-941">在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8dfbc-941">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8dfbc-942">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8dfbc-942">PowerPoint</span></span>

- <span data-ttu-id="8dfbc-943">**儲存至 [釘選資料夾]：** 釘選您的資料夾可讓您更輕鬆地儲存 Office 檔案，我們收到意見反應，使用者希望能在新檔案儲存時可以在可用的資料夾上有更多控制權。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-943">**Save to Pinned Folders:** Pin your folders makes saving Office files easier We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="8dfbc-944">我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-944">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="8dfbc-945">這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-945">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="8dfbc-946">在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8dfbc-946">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="word"></a><span data-ttu-id="8dfbc-947">Word</span><span class="sxs-lookup"><span data-stu-id="8dfbc-947">Word</span></span>

- <span data-ttu-id="8dfbc-948">**儲存至 [釘選資料夾]：** 釘選您的資料夾可讓您更輕鬆地儲存 Office 檔案。我們收到意見反應，使用者希望能在新檔案儲存時可以在可用的資料夾上有更多控制權。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-948">**Save to Pinned Folders:** Pin your folders makes saving Office files easierWe received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="8dfbc-949">我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-949">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="8dfbc-950">這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-950">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> <br /><span data-ttu-id="8dfbc-951">在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8dfbc-951">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-954">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-954">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="8dfbc-955">Excel</span><span class="sxs-lookup"><span data-stu-id="8dfbc-955">Excel</span></span>

- <span data-ttu-id="8dfbc-956">已修正當儲存至 SharePoint/OneDrive 時，會導致自訂功能區索引標籤 CustomUI XML 的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-956">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

### <a name="outlook"></a><span data-ttu-id="8dfbc-957">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-957">Outlook</span></span>

- <span data-ttu-id="8dfbc-958">解決了啟用雲端設定時，按下 Ctrl + 按一下會造成運作停止的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-958">Addressed an issue that caused Ctrl+click to stop working when cloud settings were enabled.</span></span>

### <a name="project"></a><span data-ttu-id="8dfbc-959">專案</span><span class="sxs-lookup"><span data-stu-id="8dfbc-959">Project</span></span>

- <span data-ttu-id="8dfbc-960">已修正當標示為100% 完成之工作錯誤地變更為完成度低於100% 的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-960">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-june-11"></a><span data-ttu-id="8dfbc-962">版本 2006：6 月 11 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-962">Version 2006: June 11</span></span>
<span data-ttu-id="8dfbc-963">*版本2006（組建13001.20144）*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-963">*Version 2006 (Build 13001.20144)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="8dfbc-965">功能更新</span><span class="sxs-lookup"><span data-stu-id="8dfbc-965">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="8dfbc-966">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8dfbc-966">PowerPoint</span></span>

- <span data-ttu-id="8dfbc-967">**改善的 PowerPoint 中的 Steam 影片效能：** 我們改善了 Microsoft Stream 影片的播放效能，將影片載入時間減至最少，以建立出流暢的觀賞體驗。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-967">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="8dfbc-968">您可以使用 Microsoft Stream 上您的公司影片來建立更完善的簡報。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-968">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

### <a name="word"></a><span data-ttu-id="8dfbc-969">Word</span><span class="sxs-lookup"><span data-stu-id="8dfbc-969">Word</span></span>

- <span data-ttu-id="8dfbc-970">**以向量保留文字：** 現在當您在 Excel、Word 和 PowerPoint 中轉換地圖、圖表和其他 SVG 向量等物件時，您可以保留物件中的文字。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-970">**Retain text in vectors:** Now you can retain the text in maps, charts, and other SVG vectors when converting these objects in Excel, Word, and PowerPoint.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-973">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-973">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="8dfbc-974">Excel</span><span class="sxs-lookup"><span data-stu-id="8dfbc-974">Excel</span></span>

- <span data-ttu-id="8dfbc-975">我們修正了在使用 OneDrive 時，Excel 偶爾會關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-975">We fixed an issue where Excel would occasionally shut down when engaging OneDrive.</span></span>

- <span data-ttu-id="8dfbc-976">我們修正了圖表座標軸自訂值無法正確套用的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-976">We fixed an issue where custom values on the chart axis would not get applied correctly.</span></span>

- <span data-ttu-id="8dfbc-977">我們修正了包含多個含有定義名稱的公式會導致儲存檔案時間加長的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-977">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

- <span data-ttu-id="8dfbc-978">我們修正了導致印表機名稱在可用印表機清單中重複的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-978">We fixed an issue that caused printer names to be duplicated in the list of available printers.</span></span>

- <span data-ttu-id="8dfbc-979">我們修正了在使用者刪除合併的欄時，造成執行時間增加的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-979">We fixed an issue that resulted in improved performance time for users when they deleted merged columns.</span></span>

- <span data-ttu-id="8dfbc-980">我們修正了因為增益集是以字母順序裝載，而不是以使用者指定的順序載入，而造成出現「因為此活頁簿目前有他人進行參考，而無法關閉」的錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-980">We fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="8dfbc-981">我們修正了管理 Excel 與部分協力廠商輔助技術應用程式之間的字型時發生記憶體損毀的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-981">We fixed an issue where memory was being corrupted when managing fonts between Excel and some third party assistive technology applications.</span></span>

- <span data-ttu-id="8dfbc-982">我們修正了在相同活頁簿中按一下加上書簽的超連結會導致活頁簿隱藏的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-982">We fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="8dfbc-983">我們已修正某些複製和貼上的圖表連結使用的是映射磁碟機位址，而不是通用位址的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-983">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="8dfbc-984">我們修正了當 Excel 視窗透過 Teams 共用時，使用 Ctrl + Shift + 方向鍵滑動後，Excel 可能會無法回應的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-984">We fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window was shared through Teams.</span></span>

- <span data-ttu-id="8dfbc-985">我們修正了當增益集在工作表中詢問含有 noSelect 鎖定的圖形的主項目目時，Excel 會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-985">We fixed an issue where Excel would crash when Add-ins ask for Host Items on worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="8dfbc-986">解決了嘗試將樞紐分析表插入圖表時 Excel 可能會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-986">Addressed an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

### <a name="outlook"></a><span data-ttu-id="8dfbc-987">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-987">Outlook</span></span>

- <span data-ttu-id="8dfbc-988">我們已修正以下問題：當使用多個不同解析度的監視器時，輸入法編輯器 (IEM) 視窗會覆蓋透過 IME 輸入的文字。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-988">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="8dfbc-989">我們已修正在撰寫新電子郵件訊息時，檢視範本會導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-989">We fixed an issue where viewing a template when composing a new email message would result in a crash.</span></span>

- <span data-ttu-id="8dfbc-990">我們已修正在 Outlook 版本 1911之後，使用者無法使用 Exchange 2010 公用資料夾的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-990">We fixed an issue where users were unable to Exchange 2010 public folders after Outlook version 1911.</span></span>

- <span data-ttu-id="8dfbc-991">我們修正了 Office 功能區中群組行事曆分類按鈕已停用的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-991">We fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>

- <span data-ttu-id="8dfbc-992">解決了 Outlook 無法啟用 [資料遺失保護原則] 提示使用 M365 商務版進階方案並為此服務付款的的使用者之問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-992">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="8dfbc-993">已解決導致 Outlook 在某些 Windows 組建上當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-993">Addressed an issue that caused Outlook to crash on some Windows builds.</span></span>

- <span data-ttu-id="8dfbc-994">我們修正了使用者無法與來賓使用者共用行事曆的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-994">We fixed an issue where users were unable to share a calendar with a guest user.</span></span>

- <span data-ttu-id="8dfbc-995">我們修正了使用者看到將午夜臨界值視為全天事件的行事曆專案的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-995">We fixed an issue where users saw calendar items that spanned the midnight threshold as All day events.</span></span>

- <span data-ttu-id="8dfbc-996">我們修正了導致使用者在高 DPI 監視器上遺失 [線上封存] 摘要的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-996">We fixed an issue that resulted in the Online Archive dropdown in folder properties to be missing for users on high DPI monitors.</span></span>

- <span data-ttu-id="8dfbc-997">我們修正了當使用者在資料夾之間移動專案時，BeforeItemMove 事件未正確觸發的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-997">We fixed an issue where the Folder.BeforeItemMove event didn't fire correctly when a user moved items between folders.</span></span>

- <span data-ttu-id="8dfbc-998">我們修正了當兩個增益集將按鈕新增到功能區中相同群組時，Outlook 發生當端的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-998">We fixed an issue where Outlook crashed when two add-ins added a button to the same group in the ribbon.</span></span>

- <span data-ttu-id="8dfbc-999">我們修正了當處理純文字電子郵件中的超連結時，會導致使用者遇到 Outlook 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-999">We fixed an issue that caused users to experience a crash in Outlook when working with hyperlinks in Plain Text emails.</span></span>

- <span data-ttu-id="8dfbc-1000">我們已修正導致 Outlook 無法剖析使用 RFC2231 編碼的長檔名的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1000">We fixed an issue that caused Outlook to be unable to parse long file names encoded with RFC2231.</span></span>

- <span data-ttu-id="8dfbc-1001">我們修正了導致 Outlook 使用者在使用螢幕閱讀器時遇到間歇性的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1001">We fixed an issue that was causing Outlook users to experience intermittent hangs when using screen readers.</span></span>

- <span data-ttu-id="8dfbc-1002">我們已修正具有衝突連絡人的使用者在 Outlook 中遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1002">We fixed an issue that would cause users with conflicting contacts to experience crashes in Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8dfbc-1003">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1003">PowerPoint</span></span>

- <span data-ttu-id="8dfbc-1004">我們已修正使用表單型驗證開啟伺服器設定的檔案時發生的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1004">We fixed an issue with opening server-configured files with forms-based authentication.</span></span>

- <span data-ttu-id="8dfbc-1005">我們修正了內嵌圖表/活頁簿的 PowerPoint 檔案可能會導致儲存檔案失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1005">We fixed an issue where PowerPoint files with embedded charts / workbooks could result in failures when saving the file.</span></span>

- <span data-ttu-id="8dfbc-1006">我們修正了放大和縮小簡報區域會造成縮放選取選框和滑鼠指標之間的間隙的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1006">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

- <span data-ttu-id="8dfbc-1007">我們修正了使用滑鼠滾輪縮放後，投影片並未居中的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1007">We fixed an issue where slides were not centered after zooming using the mouse wheel.</span></span>

- <span data-ttu-id="8dfbc-1008">我們已修正使用英文 (瑞士) (QWERTZ) 鍵盤時鍵盤快速鍵和拼字檢查無法正常運作的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1008">We fixed an issue where keyboard shortcuts and spell check wouldn’t function as expected when using an English Switzerland (QWERTZ) keyboard.</span></span>

- <span data-ttu-id="8dfbc-1009">我們修正了使用者已關閉的批註窗格會自動開啟的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1009">We fixed an issue where a Comment pane that had been closed by the user would re-open automatically.</span></span>

- <span data-ttu-id="8dfbc-1010">我們已修正某張投影片的投影片編輯工具會在下一張投影片上重疊的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1010">We fixed an issue where the slide editor from one slide would overlap on to the next slide.</span></span>

### <a name="project"></a><span data-ttu-id="8dfbc-1011">Project</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1011">Project</span></span>

- <span data-ttu-id="8dfbc-1012">已修正當專案摘要工作-或是專案[開始/工作]欄位有變更時，ProjectBeforeTaskChange 事件不會觸發的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1012">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

- <span data-ttu-id="8dfbc-1013">已修正當標示為100% 完成之工作錯誤地變更為完成度低於100% 的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1013">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

- <span data-ttu-id="8dfbc-1014">我們修正了在按一下 [選項] 之後 Project 會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1014">We fixed an issue where Project would crash after clicking on Options.</span></span>

- <span data-ttu-id="8dfbc-1015">我們修正了在刪除母計畫之後，無法刪除或重新指派孤立工作的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1015">We fixed an issue that prevented orphaned tasks from being deleted or re-assigned after their parent plan was deleted.</span></span>

### <a name="visio"></a><span data-ttu-id="8dfbc-1016">Visio</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1016">Visio</span></span>

- <span data-ttu-id="8dfbc-1017">有已修復的依賴代碼迴歸分析。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1017">There was regression in dependent code which has been fixed.</span></span> <span data-ttu-id="8dfbc-1018">現在，影像會在執行于 SharePoint Onprem 上的 Visio 服務中呈現。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1018">Now, the images are getting rendered in Visio services running on SharePoint Onprem.</span></span>

### <a name="word"></a><span data-ttu-id="8dfbc-1019">Word</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1019">Word</span></span>

- <span data-ttu-id="8dfbc-1020">我們修正了批註窗格中的時間戳記不是根據系統區域設定時間所建立的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1020">We fixed an issue where timestamps in Comment panes were not based on the system locale time.</span></span>

- <span data-ttu-id="8dfbc-1021">已解決在 URL 包含查詢元件時，從自訂檔傳遞（aspx）開啟 Word 檔的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1021">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>

- <span data-ttu-id="8dfbc-1022">我們修正了在批註窗格中複製及貼上文字不會顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1022">We fixed an issue where copy and pasting text to a comment pane would not be displayed.</span></span>

- <span data-ttu-id="8dfbc-1023">我們修正了批註中的超連結無法正常運作的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1023">We fixed an issue where hyperlinks in comments weren’t working.</span></span>

- <span data-ttu-id="8dfbc-1024">我們修正了放大和縮小簡報區域會造成縮放選取選框和滑鼠指標之間的間隙的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1024">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

- <span data-ttu-id="8dfbc-1025">我們修正了網頁應用程式與傳統型應用程式之間的批註未同步處理的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1025">We fixed an issue where comments between the web app and the desktop application were not in sync.</span></span>

- <span data-ttu-id="8dfbc-1026">我們修正了批註提示泡泡在100% 縮放比例中顯示模糊的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1026">We fixed an issue where comment hint bubbles appeared blurry at 100% zoom.</span></span>

- <span data-ttu-id="8dfbc-1027">我們已修正在空白文件中新增註解卻未執行任何動作的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1027">We fixed an issue where adding a new comment on a blank document wouldn't do anything.</span></span>

- <span data-ttu-id="8dfbc-1028">我們修正了無法將 HTML 貼入行事曆的 WordMail 的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1028">We fixed an issue where pasting HTML into WordMail for Calendar wasn’t working.</span></span>

- <span data-ttu-id="8dfbc-1029">我們修正了在共同撰寫的會話中回復批註有時會導致 Word 停滯的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1029">We fixed an issue where replying to a comment in a co-authored session could sometimes cause Word to freeze.</span></span>

- <span data-ttu-id="8dfbc-1030">我們修正了在含有一百個以上專案的檔中插入或更新索引會導致應用程式當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1030">We fixed an issue where inserting or updating an Index in a document containing more than a hundred entries would result in the application crashing.</span></span>

- <span data-ttu-id="8dfbc-1031">我們修正了啟用原則 Word 2007 及更新版本的二進位檔案和範本會導致部分共同撰寫案例失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1031">We fixed an issue where enabling policy Word 2007 and later Binary Documents and Templates would cause some co-authoring cases to fail.</span></span>

- <span data-ttu-id="8dfbc-1032">我們修正了具有自訂 xml 值的檔案在開啟時速度極度緩慢的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1032">We fixed an issue where files with custom xml values opened extremely slowly.</span></span>

- <span data-ttu-id="8dfbc-1033">我們修正了使用長路徑名稱（大於32K）的檔案無法開啟，且未顯示適當的錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1033">We fixed an issue where files with long path names (greater than 32K) would not open and an appropriate error message was not being displayed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="8dfbc-1034">Office 套件</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1034">Office Suite</span></span>

- <span data-ttu-id="8dfbc-1035">我們已經研究並解決了在作業系統關閉後，透過 InTune 進行的 Office 365 專業增強版部署會暫停的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1035">We have investigated and resolved the issue where an Office 365 ProPlus deployment via InTune is paused after an OS shutdown.</span></span>

- <span data-ttu-id="8dfbc-1036">我們修正了 Microsoft Office 的 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1036">We fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="8dfbc-1037">此更新解決了 Microsoft Office 中的一個問題：可能無法在執行時期正確找到 Visual Basic for Applications 專案，這些專案的參照預期透搜尋 PATH 環境變數指定的位置來找到，進而導致VBA 執行時期錯誤。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1037">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-june-08"></a><span data-ttu-id="8dfbc-1039">版本 2005：6 月 08 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1039">Version 2005: June 08</span></span>
<span data-ttu-id="8dfbc-1040">*版本2005（組建12827.20336）*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1040">*Version 2005 (Build 12827.20336)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-1042">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1042">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="8dfbc-1043">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1043">PowerPoint</span></span>

- <span data-ttu-id="8dfbc-1044">我們修正了取代字型對話方塊中，取代字型下拉清單只會顯示系統中安裝的字型，而不是所安裝的字型的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1044">We have fixed an issue with replace fonts dialog where replace font dropdown only shows fonts within the presentation instead of fonts installed on the system.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-june-04"></a><span data-ttu-id="8dfbc-1046">版本 2005：6 月 04 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1046">Version 2005: June 04</span></span>
<span data-ttu-id="8dfbc-1047">*版本2005（組建12827.20320）*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1047">*Version 2005 (Build 12827.20320)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="8dfbc-1049">功能更新</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1049">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="8dfbc-1050">Access</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1050">Access</span></span>

- <span data-ttu-id="8dfbc-1051">**隨時跟上改變！[日期/時間] 延伸資料類型具有更好的精確度。：** 引進新的和改良的資料類型。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1051">**Keep up with the times! The Date/Time Extended data type has better precision.:** Introducing a new and improved data type.</span></span>  <span data-ttu-id="8dfbc-1052">為加強與 SQL 的語法相容性，並提高包含日期和時間之記錄的詳細資料和層級，我們正在將 DateTime2 資料類型實施到 Access 中。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1052">To enhance syntax compatibility with SQL, and to increase accuracy and level of detail in records that include dates and times, we’re implementing the DateTime2 data type into Access.</span></span> <span data-ttu-id="8dfbc-1053">這個額外的日期與時間資料類型，將會包含更大的日期範圍（0001-01-01 到9999-12-31），具有更高的指定時間精準度(以納秒取代秒為單位)，讓您可以提供和執行計算。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1053">This additional date & time data type will include a larger date range (0001-01-01 through 9999-12-31), with higher-specified time precision (nanoseconds, rather than seconds) that you will be able to provide and perform calculations on.</span></span> <span data-ttu-id="8dfbc-1054">若要啟用，請選取 [新增欄位] > [日期與時間延長]。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1054">To enable, select New field > Date & Time Extended.</span></span> [<span data-ttu-id="8dfbc-1055">深入了解</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1055">Learn more</span></span>](https://support.office.com/article/708c32da-a052-4cc2-9850-9851042e0024)

### <a name="excel"></a><span data-ttu-id="8dfbc-1056">Excel</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1056">Excel</span></span>

- <span data-ttu-id="8dfbc-1057">**在 Excel 中建立來自 Power BI 資料的樞紐分析表：** 您可以在 Excel 中建立樞紐分析表，只要按幾下滑鼠，就能連線到儲存在 Power BI 的樞紐分析表。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1057">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="8dfbc-1058"> 如此一來，您就能獲得樞紐分析表和 Power BI 的最佳效果。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1058">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="8dfbc-1059">使用安全 Power BI 資料集的樞紐分析表以計算、摘要及分析資料。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1059">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span>

### <a name="outlook"></a><span data-ttu-id="8dfbc-1060">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1060">Outlook</span></span>

- <span data-ttu-id="8dfbc-1061">**可讓您從上一個 Outlook 會話中快速重新開啟專案的選項：** 我們新增了一個可快速重新開啟先前 Outlook 會話專案的選項。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1061">**Option to quickly reopen items from previous Outlook session:** We added an option to quickly reopen items from a previous Outlook session.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-1064">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1064">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="8dfbc-1065">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1065">PowerPoint</span></span>

- <span data-ttu-id="8dfbc-1066">這可修正使用者在同一檔案中同時有新版和舊版批註，因此觸發批註的升級而當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1066">This fixes a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>


### <a name="office-suite"></a><span data-ttu-id="8dfbc-1067">Office 套件</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1067">Office Suite</span></span>

- <span data-ttu-id="8dfbc-1068">我們透過設定Bing附加預設安裝驗證設定為true默認，並將MSI返回成功視為安裝成功，而解決了 ValidateInstall 失敗率問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1068">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-may-29"></a><span data-ttu-id="8dfbc-1070">版本 2005：5 月 29 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1070">Version 2005: May 29</span></span>
<span data-ttu-id="8dfbc-1071">*版本2005（組建12827.20268）*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1071">*Version 2005 (Build 12827.20268)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="8dfbc-1073">功能更新</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1073">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="8dfbc-1074">Excel</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1074">Excel</span></span>

- <span data-ttu-id="8dfbc-1075">**工作表視圖：** 排序/篩選，同時與其他人在 Excel 電腦版共同作業。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1075">**Sheet View:** Sort/filter while collaborating with others in Excel desktop.</span></span>

### <a name="outlook"></a><span data-ttu-id="8dfbc-1076">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1076">Outlook</span></span>

- <span data-ttu-id="8dfbc-1077">**新增至 Outlook 快顯通知的其他按鈕：** [快速動作] 按鈕，現在會於在 Windows 10 上執行 Outlook 時顯示在 Outlook 快顯通知中。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1077">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-1080">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1080">Resolved issues</span></span>



### <a name="outlook"></a><span data-ttu-id="8dfbc-1081">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1081">Outlook</span></span>

- <span data-ttu-id="8dfbc-1082">解決了導致 Windows 10 伺服器版本的使用者看到警告防毒軟體狀態：無效的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1082">Addressed an issue that caused users of Windows 10 server versions to see the warning  Antivirus status: Invalid.</span></span> <span data-ttu-id="8dfbc-1083">這個版本的 Windows 支援防毒軟體檢測，但即使已正確安裝防毒軟體，也無法找到防毒軟體。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1083">This version of Windows supports antivirus detection, but no antivirus was found despite having anti virus correctly installed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="8dfbc-1084">Office 套件</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1084">Office Suite</span></span>

- <span data-ttu-id="8dfbc-1085">當您啟用增益集，而登錄金鑰 HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth 被設為零時，辦公主機視窗會當機。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1085">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="8dfbc-1086">這變更將修正此問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1086">This change would fix this issue.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-may-21"></a><span data-ttu-id="8dfbc-1088">版本 2005：5 月 21 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1088">Version 2005: May 21</span></span>
<span data-ttu-id="8dfbc-1089">*版本2005（組建12827.20210）*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1089">*Version 2005 (Build 12827.20210)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)




[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-1093">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1093">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="8dfbc-1094">Excel</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1094">Excel</span></span>

- <span data-ttu-id="8dfbc-1095">已修正當 Excel 視窗透過 Teams 共用時，使用 Ctrl + Shift + 方向鍵滑動後，Excel 可能會無法回應的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1095">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>


- <span data-ttu-id="8dfbc-1096">在某些情況下，按一下同一個活頁簿中某個位置的超連結會導致活頁簿被隱藏。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1096">In some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>


### <a name="outlook"></a><span data-ttu-id="8dfbc-1097">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1097">Outlook</span></span>

- <span data-ttu-id="8dfbc-1098">已解決有回應/轉寄標註的clp審查活動的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1098">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>


- <span data-ttu-id="8dfbc-1099">已解決在從系統管理人通知中提交意見反應時，使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1099">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-may-14"></a><span data-ttu-id="8dfbc-1101">版本 2005：5 月 14 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1101">Version 2005: May 14</span></span>
<span data-ttu-id="8dfbc-1102">*版本2005（組建12827.20160）*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1102">*Version 2005 (Build 12827.20160)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="8dfbc-1104">功能更新</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1104">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="8dfbc-1105">Excel</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1105">Excel</span></span>

- <span data-ttu-id="8dfbc-1106">**[自動套用] 或 [建議敏感度] 標籤：** Office 可以根據偵測到的敏感性內容來推薦或自動套用靈敏度標籤。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1106">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8dfbc-1107">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1107">PowerPoint</span></span>

- <span data-ttu-id="8dfbc-1108">**不需要簡報導覽裝置：有耳塞式耳機就夠了：** 使用您的 Surface Earbuds 控制 PowerPoint 簡報。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1108">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="8dfbc-1109">重要：您必須在 Windows 10 的 Surface 音訊應用程式中配對 Surface Earbuds，才能使用手勢來控制簡報。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1109">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="8dfbc-1110">在此取得 Windows 10 上 Surface 音訊應用程式入門的指示。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1110">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="8dfbc-1111">深入了解</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1111">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

- <span data-ttu-id="8dfbc-1112">**[自動套用] 或 [建議敏感度] 標籤：** Office 可以根據偵測到的敏感性內容來推薦或自動套用靈敏度標籤。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1112">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="word"></a><span data-ttu-id="8dfbc-1113">Word</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1113">Word</span></span>

- <span data-ttu-id="8dfbc-1114">**[自動套用] 或 [建議敏感度] 標籤：** Office 可以根據偵測到的敏感性內容來推薦或自動套用靈敏度標籤。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1114">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-1117">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1117">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="8dfbc-1118">Excel</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1118">Excel</span></span>

- <span data-ttu-id="8dfbc-1119">已增加搭配圖表使用的 [自訂誤差線] 對話方塊上儲存格參照 [編輯] 控制項的大小。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1119">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>

- <span data-ttu-id="8dfbc-1120">修正圖表資料表無法正確呈現日期座標軸中的值的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1120">Fixed an issue where chart data table could render values in a date axis incorrectly.</span></span>

- <span data-ttu-id="8dfbc-1121">修正使用 [頁面配置] 或 [分頁預覽] 之後無法停用分頁符號的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1121">Fixed an issue where page breaks could not be disabled after going into Page Layout or Page Break Preview.</span></span>

- <span data-ttu-id="8dfbc-1122">修正隱藏和取消隱藏具有系列資料的欄之後，圖表線條樣式可能會遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1122">Fixed an issue where chart line styles could be lost after hiding and unhiding columns with series data.</span></span>

- <span data-ttu-id="8dfbc-1123">已修正在已篩選清單中插入欄的時間會比預期更長的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1123">Fixed an issue where inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="8dfbc-1124">已修正列印時表單控制項的核取方塊縮放的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1124">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="8dfbc-1125">已修正當檔案路徑太長時，在檔案重新開啟之後外部連結會停止運作的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1125">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="8dfbc-1126">在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1126">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="8dfbc-1127">在某些情況下，Application.Evaluate (VBA) 無法在使用者定義的函數中運作。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1127">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="8dfbc-1128">在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1128">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="8dfbc-1129">此變更會修正設定格式化的條件 (CF) 資訊無法正確儲存到 XLSB 檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1129">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

- <span data-ttu-id="8dfbc-1130">這項變更修正了即使 LINEST 函式傳回正確的值，圖表趨勢線的 R 平方值 (在強制 y 截距的情況下) 仍然不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1130">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>

- <span data-ttu-id="8dfbc-1131">此變更修正了自訂圖表趨勢線格式不一定會儲存的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1131">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

- <span data-ttu-id="8dfbc-1132">當您使用舊版的「共用活頁簿」模式，嘗試為活頁簿的新工作表列出變更時，就會發生當機。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1132">A crash could occur when trying to list changes on a new sheet for a workbook using legacy"Shared Workbook" mode.</span></span>

- <span data-ttu-id="8dfbc-1133">修正啟用 [負值以補色顯示] 選項後，可能無法儲存樞紐分析表中的自訂格式設定的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1133">Fixed the issue where custom formatting in Pivot charts may not be saved when the "Invert if negative" option was enabled.</span></span>

- <span data-ttu-id="8dfbc-1134">修正如果選取 [負值以補色顯示] 選項，可能無法儲存樞紐分析表中單一資料點的自訂格式設定的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1134">Fixed an issue where custom formatting for a single data point in a Pivot chart was not saved if the "Invert if negative" option was selected.</span></span>

- <span data-ttu-id="8dfbc-1135">這項變更修正在 CSV 檔案中上傳 '@' 字元時，會導致將 '@' 字元之後的字串轉換成公式的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1135">This change fixes an issue where the '@' character uploaded in a CSV file, would result in the string after the '@' character to be converted to a formula.</span></span>

- <span data-ttu-id="8dfbc-1136">修正無法正確捨入 SEQUENCE 函數中十進位值的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1136">Fixed an issue where decimal values in the SEQUENCE function were not rounded correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="8dfbc-1137">OneNote</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1137">OneNote</span></span>

- <span data-ttu-id="8dfbc-1138">修正將分行符號儲存為垂直 Tab 的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1138">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="8dfbc-1139">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1139">Outlook</span></span>

- <span data-ttu-id="8dfbc-1140">解決會導致使用者無法將個人連絡人群組新增為會議出席者的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1140">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>

- <span data-ttu-id="8dfbc-1141">已修正 Office 功能區中群組行事曆分類按鈕已停用的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1141">Fixed an issue where the categorize button for group calendars in the Office Ribbon was disabled.</span></span>

- <span data-ttu-id="8dfbc-1142">已解決在 Windows 更新後，開啟儲存在本機的 msg 或 .oft 檔案會導致 Outlook 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1142">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="8dfbc-1143">已修正企業客戶沒有執行或無法使用群組資料夾的問題，該問題會導致 Outlook 顯示「沒有回應」的訊息。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1143">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

- <span data-ttu-id="8dfbc-1144">已解決導致使用者在 Outlook 桌面用戶端中按一下非常長的安全連結時，由於截斷而無法載入的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1144">Addressed an issue that caused very long safelinks that users clicked on in the Outlook Desktop client to fail to load due to truncation.</span></span>

- <span data-ttu-id="8dfbc-1145">修正當與伺服器同步處理時，名稱中包含 DBCS (雙位元組字元集) 字元的 Outlook 資料夾會間斷消失的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1145">Fixed an issue where Outlook folders with names containing DBCS (Double Byte Character Set) characters would intermittently disappear when synchronizing with the server.</span></span> <span data-ttu-id="8dfbc-1146">為此，必須為 Outlook 設定 IMAP 帳戶，並在地區設定設定為日文的系統上執行。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1146">For this to happen, Outlook had to be configured with an IMAP account and running on a system with the locale set to Japanese.</span></span>

- <span data-ttu-id="8dfbc-1147">已解決會導致為使用者主要信箱以外的信箱所建立的刪除規則變得無效的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1147">Addressed an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>

- <span data-ttu-id="8dfbc-1148">已解決在轉寄加密郵件時導致捨棄附件的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1148">Addressed an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

- <span data-ttu-id="8dfbc-1149">已解決會導致還有 2 個月時間的會議，無法在排程小幫手中顯示會議主題的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1149">Addressed an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>

- <span data-ttu-id="8dfbc-1150">已解決會導致使用者在轉寄大型 HTML 郵件時，看到郵件內文截斷的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1150">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="8dfbc-1151">新增透過群組原則強制執行 S/MIME 預設登入設定的功能。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1151">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8dfbc-1152">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1152">PowerPoint</span></span>

- <span data-ttu-id="8dfbc-1153">已修正問題：如果使用者建立了註解，但未張貼就關閉 [註解] 窗格，然後開啟新視窗、瀏覽多張投影片並關閉視窗，最後再開啟原始簡報中的 [註解] 窗格，將導致無法使用草稿註解。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1153">Fixed an issue where if a user created a comment without posting it and closed the Comments pane, then opened a new window, navigated through multiple slides and, closed the window, and finally re-opened the Comments pane in the original presentation, the draft comments would not be available.</span></span>

- <span data-ttu-id="8dfbc-1154">修正了將滑鼠游標移到星號 (\*) 符號，但不會顯示上一次更新文件的日期和使用者姓名。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1154">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="project"></a><span data-ttu-id="8dfbc-1155">Project</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1155">Project</span></span>

- <span data-ttu-id="8dfbc-1156">在表單檢視中編輯前置/後續任務資料時，會觸發額外的 ProjectBeforeTaskChange 事件。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1156">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="8dfbc-1157">修正變更連結至 SharePoint 工作清單之專案的面板狀態欄位時，Project 可能當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1157">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>

- <span data-ttu-id="8dfbc-1158">修正儲存使用舊版 Project 建立的專案時，Project 可能當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1158">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="8dfbc-1159">已修正如果 Project 連線至 Project Web App，且小數分隔符號是逗號，當新增延遲時，TaskDependencies Add 方法會失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1159">Fixed an issue where if Project is connected to Project Web App and the decimal separator is a comma, TaskDependencies Add method fails when Lag is added.</span></span>


### <a name="word"></a><span data-ttu-id="8dfbc-1160">Word</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1160">Word</span></span>

- <span data-ttu-id="8dfbc-1161">修正在 [共同作業] 模式時，在文件中插入註解並不總是成功的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1161">Fixed an issue where inserting comments on a document in collaboration mode would not always work.</span></span>

- <span data-ttu-id="8dfbc-1162">此變更修正在按一下 @ 提及時，[人員卡片] 會閃動的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1162">This change fixes an issue where the People card would flash if the @ mention was clicked.</span></span>

- <span data-ttu-id="8dfbc-1163">啟用「顯示書簽」選項卻不會顯示書簽。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1163">Enabling the option "Show bookmarks" would not display bookmarks.</span></span> <span data-ttu-id="8dfbc-1164">已修正這個問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1164">This has been fixed.</span></span>

- <span data-ttu-id="8dfbc-1165">修正問題：關閉具有草稿註解的文件時，會在不儲存草稿註解的情況下，提示使用者是否要關閉文件。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1165">Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments.</span></span> <span data-ttu-id="8dfbc-1166">取消提示會關閉文件，而不是保持文件開啟。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1166">Cancelling the prompt would close the document rather than leaving it open.</span></span>

- <span data-ttu-id="8dfbc-1167">我們修正了複製及貼上標題的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1167">We fixed an issue in copying and pasting headings.</span></span>

- <span data-ttu-id="8dfbc-1168">已修正翻譯已張貼註解將導致「插入已翻譯的文字失敗」錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1168">Fixed an issue where translating a posted comment would result in the error 'Inserting translated text failed'.</span></span>

- <span data-ttu-id="8dfbc-1169">此變更修正了下列問題：如果已啟用 [顯示功能變數代碼，而非其值] 選項，則含有超連結的文字可能不會顯示。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1169">This change fixes an issue where text with hyperlinks may not display if the option: "Show field codes instead of their values" was enabled.</span></span>

- <span data-ttu-id="8dfbc-1170">在 Web 檢視/沉浸式閱讀器中，如果已在檢視中，按一下提示會捲動到最上方。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1170">In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view.</span></span> <span data-ttu-id="8dfbc-1171">已修正這個問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1171">This has been fixed.</span></span>

- <span data-ttu-id="8dfbc-1172">我們已修正一個問題，當嘗試使用新名稱儲存包含巨集的檔案時，無論使用者輸入什麼名稱，都會導致該檔案以.docx 副檔名和檔案名稱 WRO0004.docx 儲存，進而導致文件無法使用。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1172">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with .docx extension and the filename WRO0004.docx, regardless of what the user entered, rendering the document unusable.</span></span>

### <a name="office-suite"></a><span data-ttu-id="8dfbc-1173">Office 套件</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1173">Office Suite</span></span>

- <span data-ttu-id="8dfbc-1174">當使用者收到將他們移至 Teams Only 的原則時，他們仍然可以使用商務版 Skype Outlook 增益集來排程會議。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1174">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span>  <span data-ttu-id="8dfbc-1175">在此更新之後，當客戶端讀取指示用戶為 Teams Only 的策略並進入僅限會議加入模式後，您將不再能用商務版 Skype 安排會議。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1175">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span>  <span data-ttu-id="8dfbc-1176">此外，如果商務版 Skype Outlook 增益集發現商務版 Skype 用戶端處於 [僅限會議加入] 模式，就無法自行啟動。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1176">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="8dfbc-1177">此更新解決了 Microsoft Office 中的一個問題：可能無法在執行時期正確找到 Visual Basic for Applications 專案，這些專案的參照預期透搜尋 PATH 環境變數指定的位置來找到，進而導致VBA 執行時期錯誤。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1177">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="8dfbc-1178">此更新修正了 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1178">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-may-11"></a><span data-ttu-id="8dfbc-1180">版本 2004：5 月 11 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1180">Version 2004: May 11</span></span>
<span data-ttu-id="8dfbc-1181">*版本 2004 (組建 12730.20270)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1181">*Version 2004 (Build 12730.20270)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="8dfbc-1183">功能更新</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1183">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="8dfbc-1184">Excel</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1184">Excel</span></span>

- <span data-ttu-id="8dfbc-1185">**使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1185">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="outlook"></a><span data-ttu-id="8dfbc-1186">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1186">Outlook</span></span>

- <span data-ttu-id="8dfbc-1187">**電子郵件中的改良連結：** 當您包含檔案的連結時，檔案名會取代 URL。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1187">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="8dfbc-1188">您可以變更權限，讓所有收件者都能存取。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1188">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="8dfbc-1189">深入了解</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1189">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)<br /><span data-ttu-id="8dfbc-1190">在[部落格文章](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1190">See details in [blog post](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span></span>

- <span data-ttu-id="8dfbc-1191">**使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1191">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8dfbc-1192">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1192">PowerPoint</span></span>

- <span data-ttu-id="8dfbc-1193">**使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1193">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>  [<span data-ttu-id="8dfbc-1194">深入了解</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1194">Learn more</span></span>](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a><span data-ttu-id="8dfbc-1195">Word</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1195">Word</span></span>

- <span data-ttu-id="8dfbc-1196">**使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1196">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-1199">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1199">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="8dfbc-1200">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1200">Outlook</span></span>

- <span data-ttu-id="8dfbc-1201">解決在顯示快顯通知時，使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1201">Addressed an issue that caused users to experience a crash when displaying toast notifications.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-may-04"></a><span data-ttu-id="8dfbc-1203">版本 2004：5 月 4 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1203">Version 2004: May 04</span></span>
<span data-ttu-id="8dfbc-1204">*版本 2004 (組建 12730.20250)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1204">*Version 2004 (Build 12730.20250)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="8dfbc-1206">功能更新</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1206">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="8dfbc-1207">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1207">Outlook</span></span>

- <span data-ttu-id="8dfbc-1208">**更好的結果—瞬間：** 我們更新了搜尋體驗，讓這個版本比以往更聰明、更快速，且更可靠。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1208">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="8dfbc-1209">深入了解</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1209">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="8dfbc-1210">**IT 系統管理員的事件通知：** Microsoft 365 租用戶全域系統管理員和 Office 應用程式系統會在 Windows 版 Outlook 的新右側面板中收到影響其使用者的 Outlook 和 O365 Exchange 事件通知。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1210">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="8dfbc-1211">深入了解</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1211">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-1214">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1214">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="8dfbc-1215">Office 套件</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1215">Office Suite</span></span>

- <span data-ttu-id="8dfbc-1216">此更新修正了 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1216">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-april-29"></a><span data-ttu-id="8dfbc-1218">版本 2004：4 月 29 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1218">Version 2004: April 29</span></span>
<span data-ttu-id="8dfbc-1219">*版本 2004 (組建 12730.20236)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1219">*Version 2004 (Build 12730.20236)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="8dfbc-1221">功能更新</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1221">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="8dfbc-1222">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1222">Outlook</span></span>

- <span data-ttu-id="8dfbc-1223">**協助保護群組中的資料：** 建立群組時所選擇的「敏感度」標籤會套用到群組電子郵件、文件及小組網站。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1223">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-1226">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1226">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="8dfbc-1227">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1227">Outlook</span></span>

- <span data-ttu-id="8dfbc-1228">解決導致 Outlook 在某些 Windows 組建上當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1228">Addresses an issue that caused Outlook to crash on some builds of Windows.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-april-25"></a><span data-ttu-id="8dfbc-1230">版本 2004：4 月 25 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1230">Version 2004: April 25</span></span>
<span data-ttu-id="8dfbc-1231">*版本 2004 (組建 12730.20206)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1231">*Version 2004 (Build 12730.20206)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-1233">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1233">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="8dfbc-1234">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1234">Outlook</span></span>

- <span data-ttu-id="8dfbc-1235">已解決在 Windows 更新後，開啟儲存在本機的 msg 或 .oft 檔案會導致 Outlook 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1235">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

### <a name="project"></a><span data-ttu-id="8dfbc-1236">Project</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1236">Project</span></span>

- <span data-ttu-id="8dfbc-1237">已修正如果您使用的是連線至 Project Web App 的 Project，且小數分隔符號是逗號，當您嘗試將延遲新增至相依性時，TaskDependencies Add 方法會失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1237">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>


### <a name="office-suite"></a><span data-ttu-id="8dfbc-1238">Office 套件</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1238">Office Suite</span></span>

- <span data-ttu-id="8dfbc-1239">此修正可解決同時防止限制存取和保護設有密碼之檔案的錯誤。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1239">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-april-21"></a><span data-ttu-id="8dfbc-1241">版本 2004：4 月 21 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1241">Version 2004: April 21</span></span>
<span data-ttu-id="8dfbc-1242">版本 2004 (組建 12730.20182)</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1242">*Version 2004 (Build 12730.20182)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-1244">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1244">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="8dfbc-1245">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1245">Outlook</span></span>

- <span data-ttu-id="8dfbc-1246">解決導致資料夾窗格寬度意外變更的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1246">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="8dfbc-1247">解決導致使用者在退出 Outlook 時遇到掛斷的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1247">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-april-15"></a><span data-ttu-id="8dfbc-1249">版本 2004：4 月 15 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1249">Version 2004: April 15</span></span>
<span data-ttu-id="8dfbc-1250">*版本 2004 (組建 12730.20150)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1250">*Version 2004 (Build 12730.20150)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="8dfbc-1252">功能更新</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1252">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="8dfbc-1253">Excel</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1253">Excel</span></span>

- <span data-ttu-id="8dfbc-1254">**Facebook 連接器支援即將結束：** 於 2020 年 4 月起，Excel 就不再支援使用 Facebook 連接器的外部資料連線。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1254">**Facebook connector support is ending:** Starting in April 2020, Excel will no longer support external data connections that use the Facebook connector.</span></span>

### <a name="outlook"></a><span data-ttu-id="8dfbc-1255">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1255">Outlook</span></span>

- <span data-ttu-id="8dfbc-1256">**在 Outlook 中撰寫郵件時有新的選項可停用 @ 提及建議：** 您是否覺得 @ 提及的選擇器很煩人，一點都不好用？</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1256">**New option to disable @ mention suggestions when composing mail in Outlook:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="8dfbc-1257">現在您可以視需要將其關閉了。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1257">Now you can turn it off if you prefer.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8dfbc-1258">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1258">PowerPoint</span></span>

- <span data-ttu-id="8dfbc-1259">**在簡報時同步處理變更：** 即使簡報處於投影片放映模式，仍可即時同步處理所做的變更。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1259">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="8dfbc-1260">Word</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1260">Word</span></span>

- <span data-ttu-id="8dfbc-1261">**標註私人複本：** 製作共用文件的私人複本，以建立只有您本人能夠看到的手寫筆記。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1261">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="8dfbc-1262">若要開始使用，請移至 [檢視] > [建立私人複本]。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1262">Go to View > Create a Private Copy to get started.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-1265">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1265">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="8dfbc-1266">Access</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1266">Access</span></span>

- <span data-ttu-id="8dfbc-1267">已修正工作窗格中表格的重新調整及重新整理問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1267">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

- <span data-ttu-id="8dfbc-1268">修正國際版 Access 在使用者介面中顯示英文字串的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1268">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="8dfbc-1269">Excel</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1269">Excel</span></span>

- <span data-ttu-id="8dfbc-1270">已修正在工作表上選取儲存格範圍會導致只選取單一儲存格的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1270">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="8dfbc-1271">在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1271">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="8dfbc-1272">已修正在複製含有樞紐分析表的工作表後，會於某些情況下導致 Excel 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1272">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="8dfbc-1273">在某些情況下，Application.Evaluate (VBA) 無法在使用者定義的函式中運作。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1273">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="8dfbc-1274">修正使用者在以程式設計方式編輯大量儲存格範圍時可能遇到的效能問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1274">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>

- <span data-ttu-id="8dfbc-1275">修正以日文環境開啟 CSV 檔案時發生的效能問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1275">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

- <span data-ttu-id="8dfbc-1276">已修正插入使用者定義的圖表範本來作為預設值會導致其儲存為直條圖的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1276">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="8dfbc-1277">已修正當基礎資料儲存格沒有標題時，圖表上的資料標籤會以空白顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1277">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="8dfbc-1278">已修正在為含有 X 軸範圍的圖表縮減大小時，可能會導致 Excel 停止回應的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1278">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="8dfbc-1279">已修正已啟用 R1C1 儲存格參照且正在共同撰寫/共用的 Excel 工作表，在將游標移到 [使用者目前狀態] 圖示上方時不會以 R1C1 模式顯示作用中儲存格的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1279">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

- <span data-ttu-id="8dfbc-1280">此變更解決了處理格式錯誤或無效通訊協定資訊影像時所導致的延遲問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1280">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="8dfbc-1281">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1281">Outlook</span></span>

- <span data-ttu-id="8dfbc-1282">此變更解決了處理格式錯誤或無效通訊協定資訊影像時所導致的延遲問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1282">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="8dfbc-1283">此變更修正了電子郵件草稿最新變更未更新的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1283">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="8dfbc-1284">已修正在檔案上按一下滑鼠右鍵並使用「傳送到」功能無法運作的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1284">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="8dfbc-1285">已解決會導致代理人在不同機器上所看到的共用信箱有不同資料夾階層的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1285">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="8dfbc-1286">已解決會導致類別有時候會從電子郵件訊息中消失的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1286">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="8dfbc-1287">已解決在變更機器上的時區時，會導致某些提醒無法觸發的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1287">Addressed an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

- <span data-ttu-id="8dfbc-1288">已解決在嘗試檢視組織表單的屬性時，會導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1288">Addressed an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="8dfbc-1289">已修正如果使用者有自訂的 [通訊錄] 搜尋路徑，則 Outlook 的名稱解析範圍會限制為自訂路徑，而不是包括全域通訊清單 (GAL) 的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1289">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="8dfbc-1290">解決了會讓 [附件工具] 中的 [儲存至雲端] 按鈕不見的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1290">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="8dfbc-1291">解決了以下問題：當使用者從檢查程式視窗回覆受到數位版權管理的郵件，卻沒有所回覆郵件的擁有者權限時，使用者會無法新增簽名。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1291">Addressed an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>

- <span data-ttu-id="8dfbc-1292">解決了以下問題：使用者無法從網頁位置將其他附件新增到先前建立的會議。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1292">Addressed an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

- <span data-ttu-id="8dfbc-1293">解決將附件新增至郵件或從郵件拖放 (與透過功能表相對) 來儲存附件時，導致檔案的「上次修改」日期更新的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1293">Addressed an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

- <span data-ttu-id="8dfbc-1294">解決會導致在展開的尋找窗格中按一下 Enter 時無法開始搜尋，而是會要求使用者按一下 [搜尋] 按鈕的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1294">Addressed an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>

- <span data-ttu-id="8dfbc-1295">已修正在一組傳回的搜尋結果中，依類別結果排序不會顯示類別色彩的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1295">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

- <span data-ttu-id="8dfbc-1296">修正將 [如果有，顯示使用者的照片] 選項停用時，搜尋不會顯示有關使用者的任何資訊的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1296">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="8dfbc-1297">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1297">PowerPoint</span></span>

- <span data-ttu-id="8dfbc-1298">此變更修正了會導致包含 emojis 的 PowerPoint 檔案在儲存時發生失敗的錯誤。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1298">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

- <span data-ttu-id="8dfbc-1299">此變更修正了在 PowerPoint 或 Word 中呈現內嵌為 OLE 物件的舊版 Excel 圖表時可能不會永遠顯示圖表標題的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1299">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="8dfbc-1300">我們已修正將文字從 Excel 複製到 PowerPoint 時可能會導致其格式設定發生變更的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1300">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="8dfbc-1301">此變更修正了使用 [全字拼寫須相符] 來尋找特殊字元時，不一定能正常運作的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1301">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="8dfbc-1302">Project</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1302">Project</span></span>

- <span data-ttu-id="8dfbc-1303">修正無法正確計算摘要工作日期的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1303">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="8dfbc-1304">修正不先執行 OpenUndoTransaction 方法就不能觸發 OnUndoOrRedo 事件的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1304">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="8dfbc-1305">已修正當使用者按一下 [排程群組] 內 [工作] 功能區中的 [停用] 按鈕時，不會觸發 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) 事件的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1305">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the “Inactivate” button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="8dfbc-1306">如果您在 [表單類型] 檢視中設定前置任務或後置任務詳細資訊，則 ProjectBeforeTaskChange Visual Basic Applications (VBA) 事件不會一律擷取變更。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1306">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="8dfbc-1307">例如，如果刪除了某個相依性，並在表單上按一下 [確定]，則不會觸發該事件。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1307">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="8dfbc-1308">已修正此問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1308">This behavior has been fixed.</span></span>

- <span data-ttu-id="8dfbc-1309">已修正在進行變更 (例如日期變更) 之後，實際工作成本 (ACWP) 的最新值不會顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1309">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="8dfbc-1310">已修正使用「最近使用」(MRU) 功能表開啟專案時，會使用 [讀取/寫入] 存取權開啟專案的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1310">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="8dfbc-1311">這項變更修正了如果您建立包含開始日期和時間 (但無工期) 的手動工作，則時間表上的時間顯示不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1311">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="8dfbc-1312">已修正使用回曆列印時間表時，會導致列印檢視中略過或重複一個月的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1312">Fixed an issue where printing a timeline using a Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="8dfbc-1313">這項變更解決了在團隊規劃中使用 GDI 物件時，可能導致 GDI 物件分配過多並產生記憶體不足的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1313">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

- <span data-ttu-id="8dfbc-1314">修正了以下問題：如果執行 'CustomFieldValueListGetItem' 且自訂欄位的查閱資料表不存在，系統會建立一個不應建立的空白查閱資料表。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1314">Fixed an issue where if CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

- <span data-ttu-id="8dfbc-1315">在表單檢視中編輯前置/後續任務資料時，會觸發額外的 ProjectBeforeTaskChange 事件</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1315">WhenPredecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired</span></span>

- <span data-ttu-id="8dfbc-1316">修正了當開啟保護實際工作的設定時，使用者無法輸入分時期基準工時的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1316">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="8dfbc-1317">Word</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1317">Word</span></span>

- <span data-ttu-id="8dfbc-1318">此變更修正了將游標懸停在提示上並不會醒目提示其卡片的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1318">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="8dfbc-1319">此變更修正了以下問題：從 [檢視] 功能表選取多個頁面時，其中的 [註解] 窗格會顯示為空白。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1319">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

- <span data-ttu-id="8dfbc-1320">已修正張貼留言功能停用的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1320">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="8dfbc-1321">此變更修正了使用套索選取工具時，群組圖形中的文字會暫時消失的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1321">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="8dfbc-1322">此變更解決了處理格式錯誤或無效通訊協定資訊影像時所導致的延遲問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1322">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="8dfbc-1323">此變更修正了在 PowerPoint 或 Word 中呈現內嵌為 OLE 物件的舊版 Excel 圖表時可能不會永遠顯示圖表標題的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1323">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="8dfbc-1324">這項變更解決了帳戶管理員不會分派訊息而導致協力廠商應用程式懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1324">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="8dfbc-1325">此變更修正了在雙頁檢視中建立註解時，註解錨點不一定會顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1325">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="8dfbc-1326">修正輸入或編輯備註然後使用 Ctrl+A 時，會導致選取畫布中的文字，而不只是選取備註卡片內文字的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1326">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>

- <span data-ttu-id="8dfbc-1327">已修正如果段落的樣式是連結至清單的樣式上階，則該清單的編號可能會遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1327">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

- <span data-ttu-id="8dfbc-1328">這項變更修正了目錄會使用文件中未包含的標題樣式進行更新的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1328">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="8dfbc-1329">我們已修正文件中的文字對齊，在使用 [快速列印] 進行列印之後嘗試進行編輯時變得混亂的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1329">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="8dfbc-1330">我們已修正將兩份文件合併成一份文件時的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1330">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="8dfbc-1331">已修正在寄送文件時，儲存在 Word 文件中的數位簽章會被刪除的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1331">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

- <span data-ttu-id="8dfbc-1332">修正標示的修訂若與方程式有關，在儲存檔案時可能會導致失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1332">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-april-14"></a><span data-ttu-id="8dfbc-1334">版本 2003：4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1334">Version 2003: April 14</span></span>
<span data-ttu-id="8dfbc-1335">*版本 2003 (組建 12624.20466)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1335">*Version 2003 (Build 12624.20466)*</span></span>

<span data-ttu-id="8dfbc-1336">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1336">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

- <span data-ttu-id="8dfbc-1338">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1338">Various bugs and performance fixes.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2003-april-09"></a><span data-ttu-id="8dfbc-1340">版本 2003：4 月 9 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1340">Version 2003: April 09</span></span>
<span data-ttu-id="8dfbc-1341">*版本 2003 (組建 12624.20442)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1341">*Version 2003 (Build 12624.20442)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="8dfbc-1343">功能更新</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1343">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="8dfbc-1344">Excel</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1344">Excel</span></span>

- <span data-ttu-id="8dfbc-1345">**M365 進階版內容選擇器：** 讓您的文件栩栩如生！</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1345">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="8dfbc-1346">探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1346">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="8dfbc-1347">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1347">Outlook</span></span>

- <span data-ttu-id="8dfbc-1348">**M365 進階版內容選擇器：** 讓您的文件栩栩如生！</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1348">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="8dfbc-1349">探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1349">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8dfbc-1350">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1350">PowerPoint</span></span>

- <span data-ttu-id="8dfbc-1351">**M365 進階版內容選擇器：** 讓您的文件栩栩如生！</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1351">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="8dfbc-1352">探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1352">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="word"></a><span data-ttu-id="8dfbc-1353">Word</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1353">Word</span></span>

- <span data-ttu-id="8dfbc-1354">**M365 進階版內容選擇器：** 讓您的文件栩栩如生！</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1354">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="8dfbc-1355">探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1355">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)




[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-april-03"></a><span data-ttu-id="8dfbc-1359">版本 2003：4 月 3 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1359">Version 2003: April 03</span></span>
<span data-ttu-id="8dfbc-1360">*版本 2003 (組建 12624.20410)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1360">*Version 2003 (Build 12624.20410)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-1362">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1362">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="8dfbc-1363">Excel</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1363">Excel</span></span>

- <span data-ttu-id="8dfbc-1364">使用 VBA 應用程式的 Application.Evaluate 在某些情況下，對使用者定義的函數無法運作。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1364">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="8dfbc-1365">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1365">Outlook</span></span>

- <span data-ttu-id="8dfbc-1366">解決使用滑鼠上的「X」按鈕時，導致使用者偶爾發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1366">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

### <a name="project"></a><span data-ttu-id="8dfbc-1367">Project</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1367">Project</span></span>

- <span data-ttu-id="8dfbc-1368">在表單檢視中編輯前置/後續任務資料時，會觸發額外的 ProjectBeforeTaskChangeevent。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1368">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChangeevent is fired.</span></span>

### <a name="word"></a><span data-ttu-id="8dfbc-1369">Word</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1369">Word</span></span>

- <span data-ttu-id="8dfbc-1370">解決使用滑鼠上的「X」按鈕時，導致使用者偶爾發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1370">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-march-31"></a><span data-ttu-id="8dfbc-1372">版本 2003：3 月 31 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1372">Version 2003: March 31</span></span>
<span data-ttu-id="8dfbc-1373">*版本 2003 (組建 12624.20382)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1373">*Version 2003 (Build 12624.20382)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="8dfbc-1375">功能更新</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1375">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="8dfbc-1376">Access</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1376">Access</span></span>

- <span data-ttu-id="8dfbc-1377">**「新增資料表」工作窗格：** Access 的全新「新增資料表」工作窗格終於推出！</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1377">**"Add Tables" Task Pane:** Access's new "Add Tables" Task Pane is finally here!</span></span> <span data-ttu-id="8dfbc-1378">這項功能可讓您輕鬆選取/多重選取要在查詢視窗中新增/移除的資料表，而不需要瀏覽至查詢和關聯視圖的「顯示資料表」對話方塊。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1378">This feature allows you to easily select/multi-select which tables they'd like to add/remove into a query window, without navigating to the "Show Tables" dialog for queries and for relationship view.</span></span> <span data-ttu-id="8dfbc-1379">這也包含新的「連結」索引標籤，可顯示連結的資料表、可篩選目前清單的搜尋方塊、「拖放」行為及更多功能！</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1379">This also includes a new "links" tab to display linked tables, a search box to filter the current list, "drag and drop" behavior, and more!</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-1382">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1382">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="8dfbc-1383">Project</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1383">Project</span></span>

- <span data-ttu-id="8dfbc-1384"><span style="display:inline !important;">修正了當開啟保護實際工作的設定時，使用者無法輸入分時期基準工時的問題。</span></span><span class="sxs-lookup"><span data-stu-id="8dfbc-1384"><span style="display:inline !important;">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span></span><br>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-march-25"></a><span data-ttu-id="8dfbc-1386">版本 2003：3 月 25 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1386">Version 2003: March 25</span></span>
<span data-ttu-id="8dfbc-1387">*版本 2003 (組建 12624.20320)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1387">*Version 2003 (Build 12624.20320)*</span></span>

- <span data-ttu-id="8dfbc-1388">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1388">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-23"></a><span data-ttu-id="8dfbc-1389">版本 2003：3 月 23 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1389">Version 2003: March 23</span></span>
<span data-ttu-id="8dfbc-1390">*版本 2003 (組建 12624.20296)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1390">*Version 2003 (Build 12624.20296)*</span></span>

- <span data-ttu-id="8dfbc-1391">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1391">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-21"></a><span data-ttu-id="8dfbc-1392">版本 2003：3 月 21 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1392">Version 2003: March 21</span></span>
<span data-ttu-id="8dfbc-1393">*版本 2003 (組建 12624.20276)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1393">*Version 2003 (Build 12624.20276)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="8dfbc-1395">功能更新</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1395">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="8dfbc-1396">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1396">Outlook</span></span>

- <span data-ttu-id="8dfbc-1397">**加入會議而不需離開您的收件匣：** 不需切換至您的行事曆即可加入線上會議。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1397">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="8dfbc-1398">將行事曆釘選到 [待辦事項] 窗格之後，只要按一下就能加入任何會議。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1398">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="8dfbc-1399">**行事曆新版視覺效果：** 去年，我們提供了全新的郵件體驗，而今年將為您帶來嶄新的行事曆！</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1399">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar’s turn to get a facelift!</span></span> <span data-ttu-id="8dfbc-1400">這些更新是全新但令人熟悉的，身為經驗豐富的 Outlook 使用者的您，可以立即上手並更具生產力。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1400">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8dfbc-1401">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1401">PowerPoint</span></span>

- <span data-ttu-id="8dfbc-1402">**在投影片放映期間更新投影片：** 在簡報期間，更新由其他作者變更的投影片。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1402">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2003-march-16"></a><span data-ttu-id="8dfbc-1404">版本 2003：3 月 16 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1404">Version 2003: March 16</span></span>
<span data-ttu-id="8dfbc-1405">*版本 2003 (組建 12624.20224)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1405">*Version 2003 (Build 12624.20224)*</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="8dfbc-1407">功能更新</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1407">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="8dfbc-1408">Excel</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1408">Excel</span></span>

- <span data-ttu-id="8dfbc-1409">**挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1409">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="outlook"></a><span data-ttu-id="8dfbc-1410">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1410">Outlook</span></span>

- <span data-ttu-id="8dfbc-1411">**挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1411">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8dfbc-1412">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1412">PowerPoint</span></span>

- <span data-ttu-id="8dfbc-1413">**挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1413">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="word"></a><span data-ttu-id="8dfbc-1414">Word</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1414">Word</span></span>

- <span data-ttu-id="8dfbc-1415">**挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1415">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="office-suite"></a><span data-ttu-id="8dfbc-1416">Office 套件</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1416">Office Suite</span></span>

- <span data-ttu-id="8dfbc-1417">**索引標籤式窗格：** 現在您可以使用應用程式右側的索引標籤 UI，在多個窗格之間切換。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1417">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="8dfbc-1418">只有當您開啟 2 個以上的窗格時，該 UI 才會顯示。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1418">The UI will only be visible when you have 2+ panes open.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-1421">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1421">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="8dfbc-1422">Excel</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1422">Excel</span></span>

- <span data-ttu-id="8dfbc-1423">已解決當來源活頁簿關閉時，外部連結無法在填滿時更新的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1423">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

### <a name="outlook"></a><span data-ttu-id="8dfbc-1424">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1424">Outlook</span></span>

- <span data-ttu-id="8dfbc-1425">已解決導致使用者在工作管理員中看到 Outlook 處理序延遲的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1425">Addressed an issue that caused users to see the Outlook process lingering in task manager after exiting.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-march-10"></a><span data-ttu-id="8dfbc-1427">版本 2003：3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1427">Version 2003: March 10</span></span>
<span data-ttu-id="8dfbc-1428">*版本 2003 (組建 12624.20176)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1428">*Version 2003 (Build 12624.20176)*</span></span>

<span data-ttu-id="8dfbc-1429">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1429">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)
### <a name="feature-updates"></a><span data-ttu-id="8dfbc-1431">功能更新</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1431">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="8dfbc-1432">Excel</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1432">Excel</span></span>
- <span data-ttu-id="8dfbc-1433">**敏感度標籤**：您現在可以套用組織設定、用來提示您輸入自訂權限的敏感度標籤。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1433">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="8dfbc-1434">深入了解</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1434">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions&preserve-view=true)

### <a name="powerpoint"></a><span data-ttu-id="8dfbc-1435">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1435">PowerPoint</span></span>
- <span data-ttu-id="8dfbc-1436">**敏感度標籤**：您現在可以套用組織設定、用來提示您輸入自訂權限的敏感度標籤。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1436">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="8dfbc-1437">深入了解</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1437">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions&preserve-view=true)

### <a name="word"></a><span data-ttu-id="8dfbc-1438">Word</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1438">Word</span></span>
- <span data-ttu-id="8dfbc-1439">**敏感度標籤**：您現在可以套用組織設定、用來提示您輸入自訂權限的敏感度標籤。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1439">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="8dfbc-1440">深入了解</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1440">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions&preserve-view=true)
</br>

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-1441">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1441">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="8dfbc-1442">Excel</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1442">Excel</span></span>

- <span data-ttu-id="8dfbc-1443">修正 [檔案]\[選項] 對話方塊上的 [確定] 按鈕顯示為灰色停用狀態，但功能並未受影響的外觀問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1443">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="8dfbc-1444">修正使用者在重新命名樞紐分析表度量值時可能遇到的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1444">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>

- <span data-ttu-id="8dfbc-1445">修正交叉分析篩選器中的文字在預覽列印中無法正確縮放的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1445">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

- <span data-ttu-id="8dfbc-1446">已修正使用者在使用 VBA 巨集清除範圍內容時可能遇到的效能問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1446">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="8dfbc-1447">已修正當使用者執行與功能區互動的巨集時，導致 UI 快閃的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1447">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>

- <span data-ttu-id="8dfbc-1448">已修正當檔案中的第一個字為 TABLE 時，CSV 檔案載入錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1448">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>

- <span data-ttu-id="8dfbc-1449">已修正當您在兩個具有不同縮放比例的活頁簿之間切換時，使用者可能遇到的當機問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1449">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

- <span data-ttu-id="8dfbc-1450">修正 CUBEVALUE 函數有時會傳回不正確結果的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1450">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="8dfbc-1451">此變更可解決物件模型中的執行階段錯誤，以及當增益集要求的文件/工作表上的主機項目包含具有 noSelect 鎖定的圖形時，應用程式 (Excel、Word) 的潛在當機。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1451">This change addresses a run-time error in the object model and potential crash of the App (Excel, Word) when Add-ins ask for Host Items on documents/worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="8dfbc-1452">解決導致 Outlook 使用者在同步處理設定時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1452">Addresses an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>



### <a name="outlook"></a><span data-ttu-id="8dfbc-1453">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1453">Outlook</span></span>

- <span data-ttu-id="8dfbc-1454">修正使用 Outlook Web Access 建立規則時不會保存到 Exchange 伺服器，並導致衝突的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1454">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>

- <span data-ttu-id="8dfbc-1455">解決導致 Outlook 使用者在同步處理設定時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1455">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

- <span data-ttu-id="8dfbc-1456">修正 Outlook 在深色模式中不會在 [寄件者:] 欄位中顯示下拉式清單的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1456">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>

- <span data-ttu-id="8dfbc-1457">解決即使已關閉記錄，在某些情況下仍導致 Outlook 異常產生記錄輸出的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1457">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

- <span data-ttu-id="8dfbc-1458">已解決當持續整夜執行 Outlook 時，導致使用者無法開啟公用資料夾訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1458">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>

- <span data-ttu-id="8dfbc-1459">已修正在新增 Gmail 帳戶的驗證工作流程中，[權限] 頁面上的 [允許] 和 [拒絕] 按鈕停用的爭用情況。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1459">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>

- <span data-ttu-id="8dfbc-1460">解決導致使用者無法存取 [空閒/忙碌選項] 行事曆權限對話方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1460">Addressed an issue that caused users to lose access to the &quot;Free Busy Options&quot; calendar permissions dialog.</span></span>

- <span data-ttu-id="8dfbc-1461">修正開啟某些傳送自不同時區的週期性會議執行個體時，可能導致出現警示：「很抱歉，開啟此項目時發生問題」的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1461">Fixed an issue that may result in the alert: &quot;Sorry we're having trouble opening this item&quot; when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="8dfbc-1462">已解決從該郵件拖放附件後造成使用者無法重新開啟 .msg 檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1462">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="8dfbc-1463">修正從 Outlook 上傳檔案附件到 OneDrive 後，造成包含括號之附件名稱的檔案名稱被變更。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1463">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

- <span data-ttu-id="8dfbc-1464">解決在其他應用程式中開啟某個檔案時，導致使用者無法透過檔案總管將該檔案附加至郵件訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1464">Addressed an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

- <span data-ttu-id="8dfbc-1465">解決導致 Outlook 使用者在同步處理設定時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1465">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8dfbc-1466">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1466">PowerPoint</span></span>

- <span data-ttu-id="8dfbc-1467">修正將滑鼠移至縮圖上時，建議的縮圖閃動的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1467">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="8dfbc-1468">在某些情況下，這可能會導致 PowerPoint 當機。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1468">In some cases this could cause PowerPoint to crash.</span></span>

- <span data-ttu-id="8dfbc-1469">修正 [檔案]\[選項] 對話方塊上的 [確定] 按鈕顯示為灰色停用狀態，但功能並未受影響的外觀問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1469">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="8dfbc-1470">修正儲存包含 Excel 圖表的 PowerPoint 或 Word 文件會導致失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1470">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>



### <a name="project"></a><span data-ttu-id="8dfbc-1471">Project</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1471">Project</span></span>

- <span data-ttu-id="8dfbc-1472">修正在將任務標示為完成之後，不正確地將任務完成百分比變更為低於 100% 的值的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1472">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="8dfbc-1473">修正不先執行 OpenUndoTransaction 方法就不能觸發 OnUndoOrRedo 事件的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1473">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="8dfbc-1474">修正無法正確計算摘要工作日期的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1474">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

### <a name="visio"></a><span data-ttu-id="8dfbc-1475">Visio</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1475">Visio</span></span>

- <span data-ttu-id="8dfbc-1476">[圖形資訊] 窗格的 [圖案資料] 區段下顯示的詳細資料，與在 Visio 桌面版中開啟該檔案時所顯示的不一致。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1476">Shape info pane was showing inconsistent details under Shape Data section, with respect to the file when opened in Visio Desktop.</span></span> <span data-ttu-id="8dfbc-1477">已修正此問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1477">It has now been fixed.</span></span>

- <span data-ttu-id="8dfbc-1478">在 2016 之前版本中匯入的點陣圖，由於某些安全性檢查而未呈現。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1478">Bitmaps imported in versions before 2016 were not being rendered due to some security checks.</span></span> <span data-ttu-id="8dfbc-1479">我們已在 Visio 訂閱中修正此問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1479">We have fixed this issue in Visio Subscription.</span></span>

### <a name="word"></a><span data-ttu-id="8dfbc-1480">Word</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1480">Word</span></span>

- <span data-ttu-id="8dfbc-1481">已修正當滑鼠指標暫留在註解卡片上方時，未醒目提示註解卡片的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1481">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>

- <span data-ttu-id="8dfbc-1482">修正按 Tab 鍵導覽註解卡片時，註解編輯方塊上的焦點無法顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1482">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="8dfbc-1483">修正 [檔案]\[選項] 對話方塊上的 [確定] 按鈕顯示為灰色停用狀態，但功能並未受影響的外觀問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1483">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="8dfbc-1484">在使用中的文件共同撰寫工作階段中，直接在註解卡片中新增影像可能會導致新增標籤。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1484">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="8dfbc-1485">我們已修正此問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1485">This issue has been fixed.</span></span>

- <span data-ttu-id="8dfbc-1486">在方程式中插入控制項 (例如文字內容控制項)，然後儲存再開啟檔案，便會導致內容無法讀取的錯誤。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1486">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="8dfbc-1487">修正將先前使用密碼保護的檔案儲存到雲端儲存空間無法運作的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1487">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

- <span data-ttu-id="8dfbc-1488">修正受保護無法編輯之文件的比較功能問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1488">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>




### <a name="office-suite"></a><span data-ttu-id="8dfbc-1489">Office 套件</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1489">Office Suite</span></span>

- <span data-ttu-id="8dfbc-1490">當您將 Multichoice/Lookup/Managed-metadata 屬性與 Word/Excel/PowerPoint 文件一起使用並儲存至 SharePoint 文件庫時，這些屬性之前限制為 255 個字元。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1490">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="8dfbc-1491">當這些屬性超過 255 個字元時，這類文件就無法儲存。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1491">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="8dfbc-1492">在此變更中，此限制已增加到 2048 個字元。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1492">With this change, this limit has been increased to 2048 characters.</span></span>

- <span data-ttu-id="8dfbc-1493">修正 Word/Excel/PowerPoint 中的使用者主體名稱 (UPN) 不再區分大小寫，導致在 SharePoint 上使用檔案時較少發生失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1493">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="8dfbc-1494">修正在 Word/Excel/PowerPoint 中開啟來自相同 SharePoint 文件庫的多個文件時，僅掃描開啟的第一個文件是否符合原則的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1494">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-march-05"></a><span data-ttu-id="8dfbc-1496">版本 2002：3 月 5 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1496">Version 2002: March 05</span></span>
<span data-ttu-id="8dfbc-1497">*版本 2002 (組建 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1497">*Version 2002 (Build 12527.20278)*</span></span>

- <span data-ttu-id="8dfbc-1498">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1498">Various bugs and performance fixes.</span></span>


## <a name="version-2002-march-04"></a><span data-ttu-id="8dfbc-1499">版本 2002：3 月 4 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1499">Version 2002: March 04</span></span>
<span data-ttu-id="8dfbc-1500">*版本 2002 (組建 12527.20264)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1500">*Version 2002 (Build 12527.20264)*</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-1502">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1502">Resolved issues</span></span>

### <a name="project"></a><span data-ttu-id="8dfbc-1503">Project</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1503">Project</span></span>
- <span data-ttu-id="8dfbc-1504">修正無法正確計算摘要工作日期的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1504">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>


### <a name="office-suite"></a><span data-ttu-id="8dfbc-1505">Office 套件</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1505">Office Suite</span></span>
- <span data-ttu-id="8dfbc-1506">修正在 Word/Excel/PowerPoint 中開啟來自相同 SharePoint 文件庫的多個文件時，僅掃描開啟的第一個文件是否符合原則的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1506">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-march-01"></a><span data-ttu-id="8dfbc-1508">版本 2002：3 月 1 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1508">Version 2002: March 01</span></span>
<span data-ttu-id="8dfbc-1509">*版本 2002 (組建 12527.20242)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1509">*Version 2002 (Build 12527.20242)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-1510">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1510">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="8dfbc-1511">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1511">Outlook</span></span>

- <span data-ttu-id="8dfbc-1512">解決導致協力廠商應用程式無法傳送電子郵件的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1512">Addresses an issue that caused third party applications to be unable to send email.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-february-24"></a><span data-ttu-id="8dfbc-1514">版本 2002：2 月 24 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1514">Version 2002: February 24</span></span>
<span data-ttu-id="8dfbc-1515">*版本 2002 (組建 12527.20194)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1515">*Version 2002 (Build 12527.20194)*</span></span>

- <span data-ttu-id="8dfbc-1516">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1516">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-22"></a><span data-ttu-id="8dfbc-1517">版本 2002：2 月 22 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1517">Version 2002: February 22</span></span>
<span data-ttu-id="8dfbc-1518">*版本 2002 (組建 12527.20186)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1518">*Version 2002 (Build 12527.20186)*</span></span>

- <span data-ttu-id="8dfbc-1519">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1519">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-21"></a><span data-ttu-id="8dfbc-1520">版本 2002：2 月 21 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1520">Version 2002: February 21</span></span>
<span data-ttu-id="8dfbc-1521">*版本 2002 (組建 12527.20174)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1521">*Version 2002 (Build 12527.20174)*</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="8dfbc-1523">功能更新</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1523">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="8dfbc-1524">Access</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1524">Access</span></span>

- <span data-ttu-id="8dfbc-1525">**在查詢設計工具、SQL 檢視和關聯視窗中工作時更具生產力：** 在資料表上按一下滑鼠右鍵即可開啟、設計、調整大小及隱藏它。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1525">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="8dfbc-1526">在 SQL 檢視中搜尋及取代文字。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1526">Search and replace text in SQL View.</span></span> <span data-ttu-id="8dfbc-1527">在 [關聯圖] 視窗中選取多個資料表。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1527">Select multiple tables in the Relationships window.</span></span>

### <a name="outlook"></a><span data-ttu-id="8dfbc-1528">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1528">Outlook</span></span>

- <span data-ttu-id="8dfbc-1529">**受限 WiFi 網路的新體驗：** 是否曾經加入需要登入網頁的 WiFi 網路呢？</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1529">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="8dfbc-1530">Outlook 現在會偵測這項要求並協助您取得連結。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1530">Outlook now detects this and helps you get connected.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-1533">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1533">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="8dfbc-1534">Excel</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1534">Excel</span></span>

- <div style="box-sizing:border-box;"><span data-ttu-id="8dfbc-1535">修正 CUBEVALUE 函數有時會傳回不正確結果的問題。&nbsp;<span style="display:inline !important;"></span></span><span class="sxs-lookup"><span data-stu-id="8dfbc-1535">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.&nbsp;<span style="display:inline !important;"></span></span></span><br>


### <a name="outlook"></a><span data-ttu-id="8dfbc-1536">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1536">Outlook</span></span>

- <span data-ttu-id="8dfbc-1537">解決導致會議的位置欄位中的逗號變成分號的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1537">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>


- <span data-ttu-id="8dfbc-1538">解決在多個視窗中檢視相同項目時可能會導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1538">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>


- <span data-ttu-id="8dfbc-1539">解決即使將同步處理滑桿設定為較小的設定，也會導致 Outlook 非預期地同步處理所有郵件的問題。&nbsp;</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1539">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.&nbsp;</span></span>


- <span data-ttu-id="8dfbc-1540">解決會導致使用黑色佈景主題的使用者看到 [從]&quot;&quot; 下拉式功能表在白色背景上顯示白色文字的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1540">Addresses an issue that caused users with Black Theme to see the &quot;From&quot; dropdown show white text on a white background.</span></span>


- <span data-ttu-id="8dfbc-1541"><span style="display:inline !important;">此變更會還原在郵件標頭中檢視多行主旨的功能。</span></span><span class="sxs-lookup"><span data-stu-id="8dfbc-1541"><span style="display:inline !important;">This change restores the ability to view multi-line subjects in the message header.</span></span></span><br>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-february-18"></a><span data-ttu-id="8dfbc-1543">版本 2002：2 月 18 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1543">Version 2002: February 18</span></span>
<span data-ttu-id="8dfbc-1544">*版本 2002 (組建 12527.20138)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1544">*Version 2002 (Build 12527.20138)*</span></span>

## <a name="version-2002-february-11"></a><span data-ttu-id="8dfbc-1545">版本 2002：2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1545">Version 2002: February 11</span></span>
<span data-ttu-id="8dfbc-1546">*版本 2002 (組建 12527.20092)*</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1546">*Version 2002 (Build 12527.20092)*</span></span>

<span data-ttu-id="8dfbc-1547">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1547">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="8dfbc-1549">功能更新</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1549">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="8dfbc-1550">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1550">Outlook</span></span>

- <span data-ttu-id="8dfbc-1551">**將電子郵件拖曳到您擁有的群組：** 從您的 [收件匣] 拖曳郵件和交談以將它們移動和複製。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1551">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="8dfbc-1552">您拖曳的郵件將會與所有群組成員共用。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1552">Messages you drag will be shared with all group members.</span></span>

### <a name="word"></a><span data-ttu-id="8dfbc-1553">Word</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1553">Word</span></span>

- <span data-ttu-id="8dfbc-1554">**其他人更快速看到您的變更：** 共同撰寫增強功能表示，共同作業者可較以往更快速看到您的變更。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1554">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

### <a name="office-suite"></a><span data-ttu-id="8dfbc-1555">Office 套件</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1555">Office Suite</span></span>

- <span data-ttu-id="8dfbc-1556">**更清楚的狀態列圖示：** 狀態列圖示現在更容易查看。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1556">**Clearer status bar icons:** Status bar icons are now easier to see.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8dfbc-1559">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1559">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="8dfbc-1560">Access</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1560">Access</span></span>

- <span data-ttu-id="8dfbc-1561">Access 範本應不再導致資料庫中的附件欄出現故障。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1561">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="8dfbc-1562">個體化範本後，您現在應該可以將附件欄新增至資料庫。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1562">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="8dfbc-1563">此更新會修正使用 ADODB 的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1563">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="8dfbc-1564">VB 程式碼中的記錄器物件可能會不正確地報告錯誤。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1564">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="8dfbc-1565">此更新修正可能會導致 Microsoft Access 無法識別連結的 SQL Server 資料表中的識別資料行的問題，這可能會導致不正確地將資料列報告為已刪除。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1565">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>


### <a name="excel"></a><span data-ttu-id="8dfbc-1566">Excel</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1566">Excel</span></span>

- <span data-ttu-id="8dfbc-1567">已修正未顯示操作功能表中的註解命令的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1567">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>


- <span data-ttu-id="8dfbc-1568">已修正以下問題：將文字轉換成具有溢出陣列之儲存格的欄時，某些使用者發生當機。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1568">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>


- <span data-ttu-id="8dfbc-1569">修正使用「資料剖析」搭配動態陣列時，Excel 會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1569">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="8dfbc-1570">Outlook</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1570">Outlook</span></span>

- <span data-ttu-id="8dfbc-1571">修正以月檢視在行事曆中捲動時，無法顯示之前的行事曆活動的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1571">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="8dfbc-1572">儲存在左側瀏覽窗格 [我的最愛] 的資料夾可能會間歇性消失。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1572">Folders saved in 'Favorites' in the left navigation pane may intermittently disappear.</span></span>


- <span data-ttu-id="8dfbc-1573">已解決導致使用者在指定無效寄件者地址時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1573">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>


- <span data-ttu-id="8dfbc-1574">已解決導致在某些情況下無法使用相關選項來停用標幟項目醒目提示的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1574">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="8dfbc-1575">已解決導致使用者在取消帳戶設定時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1575">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>


- <span data-ttu-id="8dfbc-1576">修正根據保留原則到期的電子郵件會顯示兩個標籤的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1576">Fixed an issue where emails expiring based on a retention policy would display two labels.</span></span> <span data-ttu-id="8dfbc-1577">其中一個顯示郵件將在一天內過期，另一個則顯示將在兩天內到期。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1577">One showing that the mail will expire in one day and another displaying that it will expire in two days.</span></span>


- <span data-ttu-id="8dfbc-1578">已解決在 Citrix 環境中檢視 30 個以上的行事曆時，導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1578">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="8dfbc-1579">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1579">PowerPoint</span></span>

- <span data-ttu-id="8dfbc-1580">已修正使用 PowerPoint 筆跡動畫時，無法完整轉譯或跳過的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1580">Fixed an issue where Ink may not render completely or get skipped when used in a PowerPoint ink animations.</span></span>

- <span data-ttu-id="8dfbc-1581">已修正關閉檔案之後，如果有任何事件處理常式正在執行，PowerPoint 就不會立即將它從 [簡報] 集合中移除的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1581">Fixed an issue where After closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="8dfbc-1582">因此，物件模型報告的開啟中簡報數目會不正確，且會防止關閉 PowerPoint。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1582">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>


- <span data-ttu-id="8dfbc-1583">修正具有深色螢光筆色彩的白色文字，在灰階中會以黑色列印的螢光筆問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1583">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>


### <a name="project"></a><span data-ttu-id="8dfbc-1584">Project</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1584">Project</span></span>

- <span data-ttu-id="8dfbc-1585">已修正以下問題：固定工期類型的 100% 工作可能會誤將其完成百分比計算為小於 100% 完成。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1585">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>


### <a name="word"></a><span data-ttu-id="8dfbc-1586">Word</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1586">Word</span></span>

- <span data-ttu-id="8dfbc-1587">更新和瀏覽目錄時，有時可能會在文件上顯示灰色區域的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1587">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>


- <span data-ttu-id="8dfbc-1588">修正在已撰寫註解但未張貼，且使用者嘗試儲存檔案的情況下，使用 [瀏覽] 來儲存檔案沒有作用的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1588">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>


- <span data-ttu-id="8dfbc-1589">已修正在註解卡片之間來回切換時，有時會顯示一開始選取的註解，並將某選取範圍醒目提示的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1589">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>


- <span data-ttu-id="8dfbc-1590">已修正在編輯備註之後將文字設為斜體然後再張貼，斜體格式設定遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1590">Fixed an issue where italics formatting is lost after editing a comment, italicizing the text and then posting it.</span></span>


- <span data-ttu-id="8dfbc-1591">已修正在具有「反轉」頁面色彩的閱讀模式中，備註提示未顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1591">Fixed an issue where comment hint was not visible in read mode with Inverse page color.</span></span>


- <span data-ttu-id="8dfbc-1592">已修正共同撰寫文件時，可能不會保留根註解的草稿版本的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1592">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>


- <span data-ttu-id="8dfbc-1593">將 SlideTrack 啟用且 [註解] 窗格關閉時，Ctrl+Alt+M 可能無法開啟 [註解] 窗格的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1593">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>


- <span data-ttu-id="8dfbc-1594">修正在表格中新增 @提及時可能發生錯誤訊息：「文件中的表格已經毀損」的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1594">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>


- <span data-ttu-id="8dfbc-1595">修正備註內容功能表中的備註命令 (編輯備註、回覆備註、刪除備註、解決備註) 未顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1595">Fixed an issue where comment commands (Edit comment, Reply to comment, Delete comment, Resolve comment) in the comments context menu were not being displayed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="8dfbc-1596">Office 套件</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1596">Office Suite</span></span>

- <span data-ttu-id="8dfbc-1597">解決可能導致挪威耐諾斯克 (nn-no) 校訂工具套件安裝不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1597">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>


- <span data-ttu-id="8dfbc-1598">此變更解決使用 Intel Integrated GPU 的圖形配接卡報告問題。</span><span class="sxs-lookup"><span data-stu-id="8dfbc-1598">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

