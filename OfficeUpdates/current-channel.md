---
title: 2020 年目前通道版本的版本資訊
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為 IT 專業人員提供 2020 年 Microsoft 365 Apps 每月通道版本的版本資訊
ms.openlocfilehash: 82e056874fbe4e95247e6b5ccb09accdfcc98816
ms.sourcegitcommit: 8b12ed0c94df66ae0220e8c6e2e4c957d4c64e75
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 11/02/2020
ms.locfileid: "48830324"
---
# <a name="release-notes-for-current-channel-releases-in-2020"></a><span data-ttu-id="2e9d4-103">2020 年目前通道版本的版本資訊</span><span class="sxs-lookup"><span data-stu-id="2e9d4-103">Release notes for Current Channel releases in 2020</span></span>

<span data-ttu-id="2e9d4-104">這些版本資訊提供新功能和非安全性更新的相關資訊，這些功能和非安全性更新包含在 2020 年 Microsoft 365 Apps 企業版、Microsoft 365 Apps 商務版，以及 Project 和 Visio 版的傳統型應用程式訂閱版本的目前通道更新。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-104">These release notes provide information about new features and non-security updates that are included in Current Channel updates in 2020 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="2e9d4-p101">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels. To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="2e9d4-p101">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels. To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

 > [!NOTE]
>
>- <span data-ttu-id="2e9d4-107">我們通常會在一段時間對「目前」通道推出功能 (有時甚至推出修正程式)。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-107">We often roll out features (and sometimes even fixes) to Current over a period of time.</span></span>  <span data-ttu-id="2e9d4-108">如果您現在沒有看到如下所述的項目，您可以預期它近期會推出。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-108">If you don’t see something described below right away, you can expect it soon.</span></span> [<span data-ttu-id="2e9d4-109">深入了解</span><span class="sxs-lookup"><span data-stu-id="2e9d4-109">Learn more</span></span>](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516)
>- <span data-ttu-id="2e9d4-110">Microsoft Teams 功能可能會與最新的目前通道中發行的功能不同，因為後者的發行頻率較高。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-110">Microsoft Teams features may differ from the latest Current Channel released as they have a more frequent release cadence.</span></span>




[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)



[//]: # (請勿移除 BUGDETAILS 內容尾)

## <a name="version-2010-october-27"></a><span data-ttu-id="2e9d4-113">版本 2010：10 月 27 日</span><span class="sxs-lookup"><span data-stu-id="2e9d4-113">Version 2010: October 27</span></span>
<span data-ttu-id="2e9d4-114">*版本 2010 (組建 13328.20292)*</span><span class="sxs-lookup"><span data-stu-id="2e9d4-114">*Version 2010 (Build 13328.20292)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="2e9d4-116">功能更新</span><span class="sxs-lookup"><span data-stu-id="2e9d4-116">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="2e9d4-117">Access</span><span class="sxs-lookup"><span data-stu-id="2e9d4-117">Access</span></span>

- <span data-ttu-id="2e9d4-118">**隨時跟上改變！[日期/時間] 延伸資料類型具有更好的精確度。：** 引進新的和改良的資料類型。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-118">**Keep up with the times! The Date/Time Extended data type has better precision.:** Introducing a new and improved data type.</span></span> <span data-ttu-id="2e9d4-119">為加強與 SQL 的語法相容性，並提高包含日期和時間之記錄的詳細資料和層級，我們正在將 DateTime2 資料類型實施到 Access 中。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-119">To enhance syntax compatibility with SQL, and to increase accuracy and level of detail in records that include dates and times, we’re implementing the DateTime2 data type into Access.</span></span> <span data-ttu-id="2e9d4-120">這個額外的日期與時間資料類型，將會包含更大的日期範圍（0001-01-01 到9999-12-31），具有更高的指定時間精準度(以納秒取代秒為單位)，讓您可以提供和執行計算。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-120">This additional date & time data type will include a larger date range (0001-01-01 through 9999-12-31), with higher-specified time precision (nanoseconds, rather than seconds) that you will be able to provide and perform calculations on.</span></span> <span data-ttu-id="2e9d4-121">若要啟用，請選取 [新增欄位] > [日期與時間延長]。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-121">To enable, select New field > Date & Time Extended.</span></span> [<span data-ttu-id="2e9d4-122">深入了解</span><span class="sxs-lookup"><span data-stu-id="2e9d4-122">Learn more</span></span>](https://support.office.com/article/708c32da-a052-4cc2-9850-9851042e0024)

### <a name="excel"></a><span data-ttu-id="2e9d4-123">Excel</span><span class="sxs-lookup"><span data-stu-id="2e9d4-123">Excel</span></span>

- <span data-ttu-id="2e9d4-124">**使用 Power Query 建立資料類型：** 使用 Power Query 從任何資料來源建立豐富的資料類型。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-124">**Create Data Types with Power Query:** Create rich data types with Power Query from any data source.</span></span> [<span data-ttu-id="2e9d4-125">深入了解</span><span class="sxs-lookup"><span data-stu-id="2e9d4-125">Learn more</span></span>](https://support.office.com/article/a465a3b7-3d37-4eb1-a59c-bd3163315308)<br /><span data-ttu-id="2e9d4-126">在[部落格文章](https://techcommunity.microsoft.com/t5/excel-blog/announcing-power-query-data-types/ba-p/1782903)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="2e9d4-126">See details in [blog post](https://techcommunity.microsoft.com/t5/excel-blog/announcing-power-query-data-types/ba-p/1782903)</span></span>

- <span data-ttu-id="2e9d4-127">**將您的 iPhone 相片直接插入 Office：** 來自您手機的 HEIC 圖片現在可無縫地插入 Office。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-127">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="2e9d4-128">不需要轉換。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-128">No conversion required.</span></span><br /><span data-ttu-id="2e9d4-129">在[部落格文章](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="2e9d4-129">See details in [blog post](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="2e9d4-130">**使用動作手寫筆快速編輯：** 您可以使用動作手寫筆直接在儲存格中書寫，以會自動轉換成 Excel 資料的筆跡記下資料。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-130">**Make quick edits using the action pen:** With the action pen, you can write by hand directly in the cells, jot down data with ink that gets automatically converted to Excel data.</span></span>

### <a name="outlook"></a><span data-ttu-id="2e9d4-131">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e9d4-131">Outlook</span></span>

- <span data-ttu-id="2e9d4-132">**將您的 iPhone 相片直接插入 Office：** 來自您手機的 HEIC 圖片現在可無縫地插入 Office。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-132">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="2e9d4-133">不需要轉換。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-133">No conversion required.</span></span><br /><span data-ttu-id="2e9d4-134">在[部落格文章](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="2e9d4-134">See details in [blog post](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="2e9d4-135">**文法檢查是您的後盾** ：Outlook 會在您輸入時標記文法錯誤，這麼一來，您只需按一下就可以套用建議。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-135">**Grammar checking's got your back:** Outlook marks grammar errors as you type, so you can apply suggestions with a single click.</span></span> [<span data-ttu-id="2e9d4-136">深入了解</span><span class="sxs-lookup"><span data-stu-id="2e9d4-136">Learn more</span></span>](https://support.office.com/article/ddbadc42-4637-451d-b3f4-ecf295036fa9)<br /><span data-ttu-id="2e9d4-137">在[部落格文章](https://insider.office.com/en-us/blog/grammar-and-style-suggestions-available-in-outlook)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="2e9d4-137">See details in [blog post](https://insider.office.com/en-us/blog/grammar-and-style-suggestions-available-in-outlook)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2e9d4-138">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2e9d4-138">PowerPoint</span></span>

- <span data-ttu-id="2e9d4-139">**將您的 iPhone 相片直接插入 Office：** 來自您手機的 HEIC 圖片現在可無縫地插入 Office。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-139">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="2e9d4-140">不需要轉換。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-140">No conversion required.</span></span><br /><span data-ttu-id="2e9d4-141">在[部落格文章](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="2e9d4-141">See details in [blog post](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="teams"></a><span data-ttu-id="2e9d4-142">Teams</span><span class="sxs-lookup"><span data-stu-id="2e9d4-142">Teams</span></span>

- <span data-ttu-id="2e9d4-143">**Microsoft Teams 中的範本：** 使用 Teams 中的範本，使用者可在建立新的小組時從各種可自訂的範本中選擇，協助他們快速開始使用。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-143">**Templates in Microsoft Teams:** With Templates in Teams, users can choose from a variety of customizable templates when creating a new team, helping them get started quickly.</span></span> <span data-ttu-id="2e9d4-144">IT 專業人員也可以為其組織建立新的自訂範本，讓他們能標準化小組結構、讓相關應用程式浮現，以及擴大最佳做法。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-144">IT professionals can also create new custom templates for their organization, allowing them to standardize team structures, surface relevant apps, and scale best practices.</span></span>

- <span data-ttu-id="2e9d4-145">**釘選文章：** 此功能可讓使用者將頻道中的任何訊息「釘選」到頻道資訊窗格，使得頻道中所有成員能夠看見。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-145">**Pinned Posts:** This feature allows users to "pin" any message in a channel to the channel info pane for all members of the channel to see.</span></span> <span data-ttu-id="2e9d4-146">擁有頻道存取權的任何成員都能查看釘選的訊息。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-146">Any members who have access to the channel will be able to see pinned messages.</span></span> <span data-ttu-id="2e9d4-147">頻道的任何成員都能釘選任何訊息 (除非透過頻道仲裁設定關閉)。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-147">Any member of a channel will be able to pin any message (unless turned off via channel moderation settings).</span></span>

- <span data-ttu-id="2e9d4-148">**提交至應用程式目錄：** 您會在此畫面左下角看到 [提交至應用程式目錄] 連結。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-148">**Submit to app catalog:** You’ll see a Submit to app catalog link on the lower left of this screen.</span></span> <span data-ttu-id="2e9d4-149">除了 App Studio 和 Visual Studio，它是您可以提交應用程式進行核准的另一個位置。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-149">In addition to App Studio and Visual Studio, it’s another place where you can submit apps for approval.</span></span>

- <span data-ttu-id="2e9d4-150">**在彈出的會議體驗中，使用 Freehand by Invision 做為白板：** 您現在可以在彈出的會議體驗中，於您參與的任何會議中將 Freehand by Invision 應用程式用作白板。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-150">**Use Freehand by Invision to whiteboard in the popped out meeting experience:** You can now use the Freehand by Invision app to whiteboard in any meeting you take in the popped out meeting experience.</span></span> <span data-ttu-id="2e9d4-151">從共用內容匣選取 Freehand 應用程式並安裝它，然後啟動與您的同事的白板工作階段，順暢地開始激發靈感！</span><span class="sxs-lookup"><span data-stu-id="2e9d4-151">Seamlessly start brainstorming by selecting the Freehand app from the share content tray and, installing it, and starting the whiteboarding session with your colleagues!</span></span>

### <a name="word"></a><span data-ttu-id="2e9d4-152">Word</span><span class="sxs-lookup"><span data-stu-id="2e9d4-152">Word</span></span>

- <span data-ttu-id="2e9d4-153">**將您的 iPhone 相片直接插入 Office：** 來自您手機的 HEIC 圖片現在可無縫地插入 Office。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-153">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="2e9d4-154">不需要轉換。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-154">No conversion required.</span></span><br /><span data-ttu-id="2e9d4-155">在[部落格文章](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="2e9d4-155">See details in [blog post](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e9d4-158">解決的問題</span><span class="sxs-lookup"><span data-stu-id="2e9d4-158">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2e9d4-159">Access</span><span class="sxs-lookup"><span data-stu-id="2e9d4-159">Access</span></span>

- <span data-ttu-id="2e9d4-160">我們已修正從非 Office 應用程式使用 DAO 時，會導致應用程式意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-160">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


### <a name="outlook"></a><span data-ttu-id="2e9d4-161">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e9d4-161">Outlook</span></span>

- <span data-ttu-id="2e9d4-162">我們已修正在回覆或轉寄時，會導致中文郵件標題無法閱讀的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-162">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


- <span data-ttu-id="2e9d4-163">我們已修正在儲存為 OFT 檔案時，會導致中文字元變更為問號的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-163">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


- <span data-ttu-id="2e9d4-164">我們已修正會導致 Outlook 為已啟用雲端設定的使用者建立第二個空白簽名的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-164">We fixed an issue that caused Outlook to create a second empty signature for people who had cloud settings enabled.</span></span>


- <span data-ttu-id="2e9d4-165">我們已修正會導致預設不會為使用者開啟雲端設定的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-165">We fixed a n issue that caused Cloud Settings not to be turned on for users by default.</span></span>


- <span data-ttu-id="2e9d4-166">我們已修正會導致對使用者簽章的變更無法儲存的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-166">We fixed an issue that caused changes to a user's signature to fail to save.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2e9d4-167">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2e9d4-167">PowerPoint</span></span>

- <span data-ttu-id="2e9d4-168">這是此問題的修正：當有增益集在接聽 PresentationBeforeClose 事件並隨著事件處理常式檢查 Presentation.Saved 內容時若關閉文件，儲存提示會以迴圈顯示。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-168">This is a fix for an issue where the save prompt shows in a loop when closing the document when there is an add-in that listens to PresentationBeforeClose event and checks Presentation.Saved property as a part of the event handler.</span></span>


### <a name="project"></a><span data-ttu-id="2e9d4-169">Project</span><span class="sxs-lookup"><span data-stu-id="2e9d4-169">Project</span></span>

- <span data-ttu-id="2e9d4-170">修正當您將專案從 PWA 儲存到本機 mpp 檔案時，ProjectBeforeTaskChangeEvent 會對實際上未由使用者變更的資料觸發的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-170">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="2e9d4-171">修正 Project 在開啟以特定方式指定資源分佈的檔案時可能會意外終止的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-171">Fixed an issue where Project may terminate unexpectedly when opening files where resource contours were specified in a certain manner.</span></span>


- <span data-ttu-id="2e9d4-172">修正當您將專案從 PWA 儲存到本機 mpp 檔案時，ProjectBeforeTaskChangeEvent 會對實際上未由使用者變更的資料觸發的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-172">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="2e9d4-173">修正如果工作表單類型檢視內的延隔時間變更，ProjectBeforeTaskChange 事件中的 NewVal 不會有正確值的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-173">Fixed an issue where the NewVal in the ProjectBeforeTaskChange event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2e9d4-174">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2e9d4-174">Office Suite</span></span>

- <span data-ttu-id="2e9d4-175">當使用者從 Office 噴墨印表機上列印任何文件/檔案且列印機墨水不足時，即使噴墨印表機沒有碳粉，也會顯示「碳粉不足」或「無碳粉」消息。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-175">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="2e9d4-176">將訊息變更為顯示「碳粉/墨水不足」和「沒有碳粉/墨水」。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-176">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2009-october-21"></a><span data-ttu-id="2e9d4-178">版本 2009：10 月 21 日</span><span class="sxs-lookup"><span data-stu-id="2e9d4-178">Version 2009: October 21</span></span>
<span data-ttu-id="2e9d4-179">*版本 2009 (組建 13231.20418)*</span><span class="sxs-lookup"><span data-stu-id="2e9d4-179">*Version 2009 (Build 13231.20418)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e9d4-181">解決的問題</span><span class="sxs-lookup"><span data-stu-id="2e9d4-181">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2e9d4-182">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e9d4-182">Outlook</span></span>

- <span data-ttu-id="2e9d4-183">我們已修正導致使用者無法將 [編輯器] 權限授與代理人的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-183">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="2e9d4-184">我們已修正導致使用者在選取搜尋結果時遇到意外終止的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-184">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="2e9d4-185">我們已修正當回覆或轉寄郵件時，會導致中文郵件標題無法閱讀的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-185">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2e9d4-186">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2e9d4-186">PowerPoint</span></span>

- <span data-ttu-id="2e9d4-187">我們已修正 [表單] 內容增益集在插入之後不會呈現，除非使用者按一下另一張投影片讓它顯示才會呈現的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-187">We have fixed an issue where Forms content add-in doesn't render after insertion until user click to another slide to make it show.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2009-october-13"></a><span data-ttu-id="2e9d4-189">版本 2009：10 月 13 日</span><span class="sxs-lookup"><span data-stu-id="2e9d4-189">Version 2009: October 13</span></span>
<span data-ttu-id="2e9d4-190">*版本 2009 (組建 13231.20390)*</span><span class="sxs-lookup"><span data-stu-id="2e9d4-190">*Version 2009 (Build 13231.20390)*</span></span>

<span data-ttu-id="2e9d4-191">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2e9d4-191">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e9d4-193">解決的問題</span><span class="sxs-lookup"><span data-stu-id="2e9d4-193">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="2e9d4-194">Project</span><span class="sxs-lookup"><span data-stu-id="2e9d4-194">Project</span></span>

- <span data-ttu-id="2e9d4-195">修正 Project 在開啟以特定方式指定資源分佈的檔案時可能會遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-195">Fixed an issue where Project may crash on opening files where resource contours were specified in a certain manner.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2009-october-08"></a><span data-ttu-id="2e9d4-197">版本 2009：10 月 8 日</span><span class="sxs-lookup"><span data-stu-id="2e9d4-197">Version 2009: October 08</span></span>
<span data-ttu-id="2e9d4-198">*版本 2009 (組建 13231.20368)*</span><span class="sxs-lookup"><span data-stu-id="2e9d4-198">*Version 2009 (Build 13231.20368)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e9d4-200">解決的問題</span><span class="sxs-lookup"><span data-stu-id="2e9d4-200">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2e9d4-201">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e9d4-201">Outlook</span></span>

- <span data-ttu-id="2e9d4-202">解决了搜尋未緩存共用行事曆時導致搜尋不傳回結果的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-202">Addresses an issue that caused Search to return no results when searching uncached shared calendars.</span></span>


- <span data-ttu-id="2e9d4-203">解決了導致某些使用者觀察到在離線狀態下意外啟動 Outlook 的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-203">Addresses an issue that caused some users to observe Outlook unexpectedly starting in an offline state.</span></span>


- <span data-ttu-id="2e9d4-204">解決了導致代理人在開啟另一個信箱中的共用資料夾時出現錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-204">Addresses an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2e9d4-205">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2e9d4-205">PowerPoint</span></span>

- <span data-ttu-id="2e9d4-206">解决在受保護的檢視中開啟 PowerPoint 檔案時停用 IRM 保護的問題的安全性問題修正。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-206">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2e9d4-207">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2e9d4-207">Office Suite</span></span>

- <span data-ttu-id="2e9d4-208">當使用者從 Office 噴墨印表機上列印任何文件/檔案且列印機墨水不足時，即使噴墨印表機沒有碳粉，也會顯示「碳粉不足」或「無碳粉」消息。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-208">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="2e9d4-209">將訊息變更為顯示「碳粉/墨水不足」和「沒有碳粉/墨水」。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-209">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2009-september-28"></a><span data-ttu-id="2e9d4-211">版本 200９：9 月 28 日</span><span class="sxs-lookup"><span data-stu-id="2e9d4-211">Version 2009: September 28</span></span>
<span data-ttu-id="2e9d4-212">*版本 2009 (組建 13231.20262)*</span><span class="sxs-lookup"><span data-stu-id="2e9d4-212">*Version 2009 (Build 13231.20262)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="2e9d4-214">功能更新</span><span class="sxs-lookup"><span data-stu-id="2e9d4-214">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2e9d4-215">Excel</span><span class="sxs-lookup"><span data-stu-id="2e9d4-215">Excel</span></span>

- <span data-ttu-id="2e9d4-216">**將圖形另存為圖片：** 只要按幾下，即可將圖形、圖示或其他物件另存成圖片，便於您於任何其他地方使用。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-216">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="2e9d4-217">深入了解</span><span class="sxs-lookup"><span data-stu-id="2e9d4-217">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="2e9d4-218">**使用資料類型從 Power BI 取得組織資料：** 現在，來自 Power BI 的 Excel 資料類型將推出給使用 Office 365 E5/A5 或 Microsoft 365 E5/A5 之組織的測試人員使用。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-218">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 E5/A5 or Microsoft 365 E5/A5.</span></span> <span data-ttu-id="2e9d4-219">取得您所需的資訊，輕鬆地重新整理，對許多日常工作流程而言至關重要。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-219">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="2e9d4-220">我們允許您透過 Excel 中的資料類型從 Power BI 存取公司或組織資訊，從而擴充您在試算表中引入連結資訊的能力。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-220">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="2e9d4-221">深入了解</span><span class="sxs-lookup"><span data-stu-id="2e9d4-221">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="2e9d4-222">在[部落格文章](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="2e9d4-222">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

- <span data-ttu-id="2e9d4-223">**建立變數以在公式中使用：** 使用 LET 函數改善效能、可讀性及可組合性。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-223">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="2e9d4-224">此函數可讓您在新的或現有的公式中建立命名變數。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-224">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="2e9d4-225">深入了解</span><span class="sxs-lookup"><span data-stu-id="2e9d4-225">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="2e9d4-226">在[部落格文章](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="2e9d4-226">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="2e9d4-227">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e9d4-227">Outlook</span></span>

- <span data-ttu-id="2e9d4-228">**自動開展線上目錄搜尋ive Search:** Enabling auto-expanding Online Archive Search</span><span class="sxs-lookup"><span data-stu-id="2e9d4-228">**Auto-Expanding Online Archive Search:** Enabling auto-expanding Online Archive Search</span></span>

- <span data-ttu-id="2e9d4-229">**Outlook 的新設定檔卡：** Outlook 的新設定檔卡，包括更完善的組織方式，並符合 Outlook Web 卡的樣式。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-229">**New profile card for Outlook:** New profile card for Outlook including a better Organization view and matches the card style of Outlook Web.</span></span>

### <a name="teams"></a><span data-ttu-id="2e9d4-230">Teams</span><span class="sxs-lookup"><span data-stu-id="2e9d4-230">Teams</span></span>

- <span data-ttu-id="2e9d4-231">**在 Microsoft Teams 中共用檔案：** [深入了解](https://docs.microsoft.com/MicrosoftTeams/sharing-files-in-teams)</span><span class="sxs-lookup"><span data-stu-id="2e9d4-231">**Sharing files in Microsoft Teams:** [Learn more](https://docs.microsoft.com/MicrosoftTeams/sharing-files-in-teams)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e9d4-234">解決的問題</span><span class="sxs-lookup"><span data-stu-id="2e9d4-234">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2e9d4-235">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e9d4-235">Outlook</span></span>

- <span data-ttu-id="2e9d4-236">已解決當主旨行空白時，會導致傳送的自動產生電子郵件含有空白內文的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-236">Addresses an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2e9d4-237">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2e9d4-237">PowerPoint</span></span>

- <span data-ttu-id="2e9d4-238">修正了在包含大量特定資料物件類型 (E2o) 的檔案上導致共同撰寫變慢的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-238">Fixed an issue causing slow coauthoring on files containing large numbers of a certain data object type (E2o).</span></span>


### <a name="project"></a><span data-ttu-id="2e9d4-239">Project</span><span class="sxs-lookup"><span data-stu-id="2e9d4-239">Project</span></span>

- <span data-ttu-id="2e9d4-240">已修正若您的事件程式碼執行中，並嘗試透過工作 [表單檢視] 進行變更，按一下 [確定] 按鈕可能不會提交變更的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-240">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


### <a name="word"></a><span data-ttu-id="2e9d4-241">Word</span><span class="sxs-lookup"><span data-stu-id="2e9d4-241">Word</span></span>

- <span data-ttu-id="2e9d4-242">我們修正了 [樣式圖庫] 對話方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-242">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2e9d4-243">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2e9d4-243">Office Suite</span></span>

- <span data-ttu-id="2e9d4-244">此變更解決 [匯出至動畫 GIF] 功能的問題，其中按一下 [匯出] 按鈕沒有匯出。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-244">This change addresses an issue with Export to Animated GIF feature where clicking on Export button was not exporting.</span></span>


- <span data-ttu-id="2e9d4-245">此變更解決 [壓縮圖片] 對話方塊無法保留特定使用者設定的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-245">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-september-22"></a><span data-ttu-id="2e9d4-247">版本 2008: 9月 22日</span><span class="sxs-lookup"><span data-stu-id="2e9d4-247">Version 2008: September 22</span></span>
<span data-ttu-id="2e9d4-248">*版本 2008 (組建 13127.20508)*</span><span class="sxs-lookup"><span data-stu-id="2e9d4-248">*Version 2008 (Build 13127.20508)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e9d4-250">解決的問題</span><span class="sxs-lookup"><span data-stu-id="2e9d4-250">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2e9d4-251">Excel</span><span class="sxs-lookup"><span data-stu-id="2e9d4-251">Excel</span></span>

- <span data-ttu-id="2e9d4-252">修正了當凍結工作表頂端列之後，Excel 可能會在使用 [快速分析] 時當機的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-252">Fixed an issue where Excel could crash when using the Quick Analysis after freezing the top row of the sheet.</span></span>


- <span data-ttu-id="2e9d4-253">修正了當活頁簿包含使用 IFNA () 的公式時，可能會造成錯誤活頁簿的警告之問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-253">Fixed an issue that could cause a warning about a corrupt workbook if it contained formulas using IFNA().</span></span>


### <a name="outlook"></a><span data-ttu-id="2e9d4-254">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e9d4-254">Outlook</span></span>

- <span data-ttu-id="2e9d4-255">解決由於按一下角落中的 [X] 而導致使用者無法關閉共用行事曆的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-255">Addresses an issue that caused users to be unable to close shared calendars by clicking on the "X" in the corner.</span></span>


- <span data-ttu-id="2e9d4-256">解決附件上傳的效能問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-256">Addresses a performance issue with attachment upload.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2e9d4-257">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2e9d4-257">PowerPoint</span></span>

- <span data-ttu-id="2e9d4-258">我們修正了在 PowerPoint 應用程式中導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-258">We have fixed an issue which was causing the crash in PowerPoint app.</span></span>


### <a name="visio"></a><span data-ttu-id="2e9d4-259">Visio</span><span class="sxs-lookup"><span data-stu-id="2e9d4-259">Visio</span></span>

- <span data-ttu-id="2e9d4-260">客戶回報文字對齊會在即時預覽時發生當機。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-260">Live preview crashes on text alignment reported by customers.</span></span> <span data-ttu-id="2e9d4-261">7 月分支所發生最多的當機情況。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-261">Top hitting crash of July fork.</span></span>


### <a name="word"></a><span data-ttu-id="2e9d4-262">Word</span><span class="sxs-lookup"><span data-stu-id="2e9d4-262">Word</span></span>

- <span data-ttu-id="2e9d4-263">我們修正了 [樣式圖庫] 對話方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-263">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2e9d4-264">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2e9d4-264">Office Suite</span></span>

- <span data-ttu-id="2e9d4-265">修正使用 GIF/動畫 model3D 時導致高 CPU 使用狀況空閒</span><span class="sxs-lookup"><span data-stu-id="2e9d4-265">Fixes high CPU usage on idle with GIF/animated model3D</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-september-09"></a><span data-ttu-id="2e9d4-267">版本 2008：9月 9 日</span><span class="sxs-lookup"><span data-stu-id="2e9d4-267">Version 2008: September 09</span></span>
<span data-ttu-id="2e9d4-268">*版本 2008 (組建 13127.20408)*</span><span class="sxs-lookup"><span data-stu-id="2e9d4-268">*Version 2008 (Build 13127.20408)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e9d4-270">解決的問題</span><span class="sxs-lookup"><span data-stu-id="2e9d4-270">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2e9d4-271">Access</span><span class="sxs-lookup"><span data-stu-id="2e9d4-271">Access</span></span>

- <span data-ttu-id="2e9d4-272">此變更修正了當啟動縮放框 (Shift + F2) 來編輯文字時，可能會導致 Access 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-272">This change fixes an issue that could cause Access to crash when launching the Zoom box (Shift + F2) to edit text.</span></span>


### <a name="excel"></a><span data-ttu-id="2e9d4-273">Excel</span><span class="sxs-lookup"><span data-stu-id="2e9d4-273">Excel</span></span>

- <span data-ttu-id="2e9d4-274">已修正使用 [複製格式] 時，某些情況下，Excel 可能會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-274">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>


### <a name="word"></a><span data-ttu-id="2e9d4-275">Word</span><span class="sxs-lookup"><span data-stu-id="2e9d4-275">Word</span></span>

- <span data-ttu-id="2e9d4-276">我們已修正在調整圖案大小時，使用者可能會遺失內容的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-276">We fixed an issue where the user might lose content when resize a shape.</span></span>


- <span data-ttu-id="2e9d4-277">我們已修正基本樣式未更新為「內文樣式」的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-277">We fixed an issue which the base styles are not updated with Normal style.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2e9d4-278">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2e9d4-278">Office Suite</span></span>

- <span data-ttu-id="2e9d4-279">此變更解決 [壓縮圖片] 對話方塊無法保留特定使用者設定的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-279">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-august-31"></a><span data-ttu-id="2e9d4-281">版本2008：8月31日</span><span class="sxs-lookup"><span data-stu-id="2e9d4-281">Version 2008: August 31</span></span>
<span data-ttu-id="2e9d4-282">*版本2008（組建13127.20296）*</span><span class="sxs-lookup"><span data-stu-id="2e9d4-282">*Version 2008 (Build 13127.20296)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="2e9d4-284">功能更新</span><span class="sxs-lookup"><span data-stu-id="2e9d4-284">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2e9d4-285">Excel</span><span class="sxs-lookup"><span data-stu-id="2e9d4-285">Excel</span></span>

- <span data-ttu-id="2e9d4-286">**儲存至釘選資料夾：** 釘選資料夾可讓您更輕鬆地儲存 Office 檔案。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-286">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="2e9d4-287">我們收到了意見反應，使用者想更進一步控制儲存新檔案時可用的資料夾。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-287">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="2e9d4-288">我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-288">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="2e9d4-289">這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-289">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="2e9d4-290">深入了解</span><span class="sxs-lookup"><span data-stu-id="2e9d4-290">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="2e9d4-291">在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="2e9d4-291">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="outlook"></a><span data-ttu-id="2e9d4-292">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e9d4-292">Outlook</span></span>

- <span data-ttu-id="2e9d4-293">**電子郵件中的改良連結：** 當您包含檔案的連結時，檔案名會取代 URL。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-293">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="2e9d4-294">您可以變更權限，讓所有收件者都能存取。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-294">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="2e9d4-295">深入了解</span><span class="sxs-lookup"><span data-stu-id="2e9d4-295">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)<br /><span data-ttu-id="2e9d4-296">在[部落格文章](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="2e9d4-296">See details in [blog post](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span></span>



### <a name="powerpoint"></a><span data-ttu-id="2e9d4-297">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2e9d4-297">PowerPoint</span></span>

- <span data-ttu-id="2e9d4-298">**儲存至釘選資料夾：** 釘選資料夾可讓您更輕鬆地儲存 Office 檔案。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-298">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="2e9d4-299">我們收到了意見反應，使用者想更進一步控制儲存新檔案時可用的資料夾。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-299">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="2e9d4-300">我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-300">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="2e9d4-301">這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-301">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="2e9d4-302">深入了解</span><span class="sxs-lookup"><span data-stu-id="2e9d4-302">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="2e9d4-303">在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="2e9d4-303">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="teams"></a><span data-ttu-id="2e9d4-304">Teams</span><span class="sxs-lookup"><span data-stu-id="2e9d4-304">Teams</span></span>

- <span data-ttu-id="2e9d4-305">**合併通話：** 合併通話可讓使用者將使用中的 unheld 1-1 撥入另一個1-1 通話或另一個群組通話。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-305">**Call Merge:** Call Merge gives end users the capability to merge their active unheld 1-1 call into another 1-1 call or another group call.</span></span> <span data-ttu-id="2e9d4-306">這適用於Teams VOIP 通話和 PSTN 通話。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-306">This applies to Teams VOIP calls and PSTN calls.</span></span>

- <span data-ttu-id="2e9d4-307">**系統管理員可以針對其第一線工作者設定按班表顯示（上班、下班）：** 系統管理員可以設定其第一線工作者使用以班表為基礎的狀態顯示：上班、忙碌中（到班時可以切換）和下班。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-307">**Admins can configure shift-based presence (On shift, Off shift) for their Firstline workers:** Admins can configure their firstline workers to have shift-based presence states: On shift, Busy (can be toggled when on shift), and Off shift.</span></span>

- <span data-ttu-id="2e9d4-308">**在Teams中使用 Cortana 語音技能：** Teams行動裝置的應用程式的Cortana 語音功能, 可協助使用者僅使用口頭自然語言即可執行會議、通訊與共同協作任務。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-308">**Cortana voice skills in Teams:** Cortana voice skills in Teams mobile app help users perform meeting, communication and collaboration tasks simply using spoken natural language.</span></span> <span data-ttu-id="2e9d4-309">使用者可以在Teams應用程式中點擊麥克風按鈕與Cortana交談, 而且當他們困在家務中或遛狗或一般外出需與某人聯繫時, 可以發出諸如“打電話給Megan”或“對我的下一個會議發送訊息”之類的請求.</span><span class="sxs-lookup"><span data-stu-id="2e9d4-309">Users can speak to Cortana by clicking on the microphone button in Teams app and make requests like “Call Megan” or “Send a message to my next meeting” if they need to connect with someone while juggling household chores or walking the dog or generally on the go.</span></span> <span data-ttu-id="2e9d4-310">使用者只要說「加入我的下一個會議」即可加入會議，或者詢問「我今天早上有什麼事」來檢查行事曆。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-310">Users can join meetings simply by saying “Join my next meeting” or check their calendar by asking “what do I have this morning”.</span></span> <span data-ttu-id="2e9d4-311">在會議或通話中，他們可以從會議主持者的 [溢出] 功能表中調用 Cortana，並執行典型的會議中任務，例如按照姓名或電話號碼（「將 Megan 新增至通話」）、投影片瀏覽（「顯示季度檢閱投影片瀏覽」）或檢視投影片（「移至投影片備忘稿」）。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-311">Once in a meeting or a call, they can invoke Cortana from the overflow menu in the meeting stage and perform typical in-meeting tasks like adding people by name or number (“Add Megan to the call”), deck presentation (“present the quarterly review deck”) or navigating slides (“Go to the appendix slide”).</span></span> <span data-ttu-id="2e9d4-312">該功能還支持其他功能, 如尋找及共享檔案、搜尋，並通常在Teams應用中導航（與約翰聊天，移至我的未讀取活動，請移至我的表述等等）。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-312">Other things that the feature supports are finding and sharing files, search, and generally navigating within the Teams app (“Open my chat with John, Go to my unread activity, Go to my mentions etc.).</span></span> <span data-ttu-id="2e9d4-313">Teams 的Cortana 對Cortana 企業服務來說說符合對 Cortana 企業服務相同的的企業級隱私、安全性和合規性承諾，並反映在 [線上服務條款（OST）](https://www.microsoft.com/licensing/product-licensing/products)中。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-313">Cortana in Teams meets the same enterprise-level privacy, security, and compliance promises for Cortana enterprise services, as reflected in the [Online Services Terms (OST)](https://www.microsoft.com/licensing/product-licensing/products).</span></span>

- <span data-ttu-id="2e9d4-314">**增加群組交談：** Teams新增了群組聊天中可有250個參與者的功能.</span><span class="sxs-lookup"><span data-stu-id="2e9d4-314">**Group chat increase:** Teams added the ability to now have 250 participants in a group chat.</span></span>

- <span data-ttu-id="2e9d4-315">**按 Shift 加上標籤:** 使用這項功能，系統會自動在小組中的 [Shifts app](https://support.microsoft.com/office/get-started-in-shifts-5f3e30d8-1821-4904-be26-c3cd25a497d6#bkmk_openshiftsappdesktop) 應用程式中, 為人員指派符合其行程和班表的標籤。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-315">**Tagging by Shift:** With this feature, people are automatically assigned tags that match their schedule and shift group name in the [Shifts app](https://support.microsoft.com/office/get-started-in-shifts-5f3e30d8-1821-4904-be26-c3cd25a497d6#bkmk_openshiftsappdesktop) in Teams.</span></span>

### <a name="word"></a><span data-ttu-id="2e9d4-316">Word</span><span class="sxs-lookup"><span data-stu-id="2e9d4-316">Word</span></span>

- <span data-ttu-id="2e9d4-317">**儲存至釘選資料夾：** 釘選資料夾可讓您更輕鬆地儲存 Office 檔案。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-317">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="2e9d4-318">我們收到了意見反應，使用者想更進一步控制儲存新檔案時可用的資料夾。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-318">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="2e9d4-319">我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-319">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="2e9d4-320">這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-320">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="2e9d4-321">深入了解</span><span class="sxs-lookup"><span data-stu-id="2e9d4-321">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="2e9d4-322">在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="2e9d4-322">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="office-suite"></a><span data-ttu-id="2e9d4-323">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2e9d4-323">Office Suite</span></span>

- <span data-ttu-id="2e9d4-324">**索引標籤式窗格：** 現在您可以使用應用程式右側的索引標籤 UI，在多個窗格之間切換。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-324">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="2e9d4-325">只有當您開啟 2 個以上的窗格時，該 UI 才會顯示。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-325">The UI will only be visible when you have 2+ panes open.</span></span><br /><span data-ttu-id="2e9d4-326">在[部落格文章](https://blog-insider.office.com/2020/02/20/improved-pane-management/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="2e9d4-326">See details in [blog post](https://blog-insider.office.com/2020/02/20/improved-pane-management/)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e9d4-329">解決的問題</span><span class="sxs-lookup"><span data-stu-id="2e9d4-329">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2e9d4-330">Access</span><span class="sxs-lookup"><span data-stu-id="2e9d4-330">Access</span></span>

- <span data-ttu-id="2e9d4-331">已解决此問題 - 您現在可以使用 Office 的隨選即用應用程式外的 ODBC 驅動程式。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-331">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>


### <a name="outlook"></a><span data-ttu-id="2e9d4-332">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e9d4-332">Outlook</span></span>

- <span data-ttu-id="2e9d4-333">修正導致使用者嘗試從次要帳戶建立會議邀請的問題，讓帳戶新增至他們的個人檔案，而不會看到空白的表格: 是欄位而不是其電子郵件地址。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-333">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>

- <span data-ttu-id="2e9d4-334">修正了新增共用信箱之後，導致使用者無法連線至公用資料夾的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-334">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>

- <span data-ttu-id="2e9d4-335">解決了當代理人在某些情況下遭到拒絕而導致會議無法從經理的行事曆中移除的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-335">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>

- <span data-ttu-id="2e9d4-336">解决了導致使用 Shared Calendar Improvements 的某些使用者無法查看剛新增的共用行事曆的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-336">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="2e9d4-337">修正了當與雲端附件互動時，導致使用者偶爾當機的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-337">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>

- <span data-ttu-id="2e9d4-338">解決了導致某些字元集的使用者在將 [智慧型連結] 新增至 SharePoint 檔案時，發現檔案名不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-338">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>

- <span data-ttu-id="2e9d4-339">解決會導致使用者在回覆或撰寫新電子郵件時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-339">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>

- <span data-ttu-id="2e9d4-340">解決了當您從 POP 帳戶刪除4或多個電子郵件時，已選取 [僅下載標題] 選項時，導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-340">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>

- <span data-ttu-id="2e9d4-341">解決導致 [排程助理員] 頁面無法顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-341">Addressed an issue that caused some users to see the Scheduling Assistant page fail to display.</span></span>

- <span data-ttu-id="2e9d4-342">修正了編輯收件者時，導致使用者偶爾當機的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-342">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="2e9d4-343">修正導致使用者在使用壓縮模式時發生異常的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-343">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>

- <span data-ttu-id="2e9d4-344">解決的問題導致在搜尋控制項中無法顯示滑鼠右鍵功能表。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-344">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>

- <span data-ttu-id="2e9d4-345">解決會導致使用者在回覆或撰寫新電子郵件時收到下列錯誤的問題：「這個網頁中的某些檔案不存在預期的位置，</span><span class="sxs-lookup"><span data-stu-id="2e9d4-345">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="2e9d4-346">請問您一定要下載嗎?</span><span class="sxs-lookup"><span data-stu-id="2e9d4-346">Do you want to download them anyway?</span></span> <span data-ttu-id="2e9d4-347">如果您確定網頁來自信任的來源，請按 [是]」</span><span class="sxs-lookup"><span data-stu-id="2e9d4-347">If you’re sure the Web page is from a trusted source, click Yes"</span></span>


### <a name="project"></a><span data-ttu-id="2e9d4-348">Project</span><span class="sxs-lookup"><span data-stu-id="2e9d4-348">Project</span></span>

- <span data-ttu-id="2e9d4-349">已修正「連結至 SharePoint 工作清單的專案的完成日期沒有更新」的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-349">Fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>

- <span data-ttu-id="2e9d4-350">修正如果資源中定義了多個成本費率表，其餘成本並不一定都能正確地計算的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-350">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>

### <a name="skype"></a><span data-ttu-id="2e9d4-351">Skype</span><span class="sxs-lookup"><span data-stu-id="2e9d4-351">Skype</span></span>

- <span data-ttu-id="2e9d4-352">將跳舞表情符號膚色變更為中性色彩.</span><span class="sxs-lookup"><span data-stu-id="2e9d4-352">Changed dancing emoticon skin tone to neutral color.</span></span>

### <a name="word"></a><span data-ttu-id="2e9d4-353">Word</span><span class="sxs-lookup"><span data-stu-id="2e9d4-353">Word</span></span>

- <span data-ttu-id="2e9d4-354">此更改解決了一個問題，即在上一個協同合作的作業後，Microsoft Office 應用程式可能卡在未通知的儲存失敗狀態的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-354">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>

- <span data-ttu-id="2e9d4-355">我們已修正整體的 AutoOpen 在 AutoExec 之前執行的問題</span><span class="sxs-lookup"><span data-stu-id="2e9d4-355">We fixed an issue where macro AutoOpen runs before AutoExec</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-august-25"></a><span data-ttu-id="2e9d4-357">版本 2007：8 月 25 日</span><span class="sxs-lookup"><span data-stu-id="2e9d4-357">Version 2007: August 25</span></span>
<span data-ttu-id="2e9d4-358">*版本 2007 (組建 13029.20460)*</span><span class="sxs-lookup"><span data-stu-id="2e9d4-358">*Version 2007 (Build 13029.20460)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e9d4-360">解決的問題</span><span class="sxs-lookup"><span data-stu-id="2e9d4-360">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2e9d4-361">Excel</span><span class="sxs-lookup"><span data-stu-id="2e9d4-361">Excel</span></span>

- <span data-ttu-id="2e9d4-362">嘗試使用 LET() 函數儲存含有公式的檔案時發生錯誤。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-362">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>


### <a name="outlook"></a><span data-ttu-id="2e9d4-363">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e9d4-363">Outlook</span></span>

- <span data-ttu-id="2e9d4-364">解決了導致某些字元集的使用者在將 [智慧型連結] 新增至 SharePoint 檔案時，發現檔案名不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-364">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>


- <span data-ttu-id="2e9d4-365">解決會導致 Outlook 使用者在精簡檢視中看到瀏覽問題的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-365">Addressed an issue that caused outlook users to see issues with navigation in compact views.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2e9d4-366">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2e9d4-366">PowerPoint</span></span>

- <span data-ttu-id="2e9d4-367">我們已修正 PowerPoint 應用程式的當機問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-367">We have fixed a crash issue with PowerPoint app.</span></span>


### <a name="word"></a><span data-ttu-id="2e9d4-368">Word</span><span class="sxs-lookup"><span data-stu-id="2e9d4-368">Word</span></span>

- <span data-ttu-id="2e9d4-369">解決會導致使用者在回覆或撰寫新郵件時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-369">Addresses an issue that caused users to experience a crash when replying to or composing new mail.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2e9d4-370">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2e9d4-370">Office Suite</span></span>

- <span data-ttu-id="2e9d4-371">針對舊版非網頁服務的 [共用] 窗格，在開啟 [共用] 窗格下關閉文件時，可能會導致當機。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-371">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash.</span></span> <span data-ttu-id="2e9d4-372">這個問題現在已經修正。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-372">This is now fixed.</span></span>


- <span data-ttu-id="2e9d4-373">我們已修正使用者在特定情況下 (特別是進入或退出簡報者檢視畫面或使用多個監視器) 看到 UI 元素或內容未顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-373">We fixed an issue where users were seeing the UI elements or content not being displayed under certain conditions, in particular with coming in and out of Presenter View or using multiple monitors.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-august-11"></a><span data-ttu-id="2e9d4-375">版本 2007: 8月11日</span><span class="sxs-lookup"><span data-stu-id="2e9d4-375">Version 2007: August 11</span></span>
<span data-ttu-id="2e9d4-376">*版本 2007 (組建 13029.20344)*</span><span class="sxs-lookup"><span data-stu-id="2e9d4-376">*Version 2007 (Build 13029.20344)*</span></span>

<span data-ttu-id="2e9d4-377">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2e9d4-377">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e9d4-379">解決的問題</span><span class="sxs-lookup"><span data-stu-id="2e9d4-379">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2e9d4-380">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e9d4-380">Outlook</span></span>

- <span data-ttu-id="2e9d4-381">解決會導致 Outlook 無法擷取搜尋建議的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-381">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>


- <span data-ttu-id="2e9d4-382">解決會導致使用者在擷取角色資訊時有時候會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-382">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>


### <a name="project"></a><span data-ttu-id="2e9d4-383">Project</span><span class="sxs-lookup"><span data-stu-id="2e9d4-383">Project</span></span>

- <span data-ttu-id="2e9d4-384">修正無法開啟已進入錯誤狀態的專案的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-384">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-july-30"></a><span data-ttu-id="2e9d4-386">版本 2007：7 月 30 日</span><span class="sxs-lookup"><span data-stu-id="2e9d4-386">Version 2007: July 30</span></span>
<span data-ttu-id="2e9d4-387">*版本 2007 (組建 13029.20308)*</span><span class="sxs-lookup"><span data-stu-id="2e9d4-387">*Version 2007 (Build 13029.20308)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="2e9d4-389">功能更新</span><span class="sxs-lookup"><span data-stu-id="2e9d4-389">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2e9d4-390">Excel</span><span class="sxs-lookup"><span data-stu-id="2e9d4-390">Excel</span></span>

- <span data-ttu-id="2e9d4-391">**建立 PDF 連線：** 連線至、匯入、重新整理 PDF 中的資料。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-391">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="2e9d4-392">深入了解</span><span class="sxs-lookup"><span data-stu-id="2e9d4-392">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="2e9d4-393">**篩選和排序而不干擾其他人：** 您現在可以排序和篩選您的 Excel 檔案，同時與其他人使用工作表檢視進行共同作業。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-393">**Filter and sort without disrupting others:** You can now sort and filter your Excel file while collaborating with others with Sheet View.</span></span> <span data-ttu-id="2e9d4-394">此新功能可防止您在共同撰寫文件時，受到其他使用者的排序和篩選的影響。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-394">This new feature prevents you from being impacted by other user’s sorts and filters while coauthoring the document.</span></span> [<span data-ttu-id="2e9d4-395">深入了解</span><span class="sxs-lookup"><span data-stu-id="2e9d4-395">Learn more</span></span>](https://support.office.com/article/0eea3dc5-d7d1-44c5-a953-25ebfbd6c1a6)

- <span data-ttu-id="2e9d4-396">**自動套用或建議敏感度標籤：** Office 可以根據偵測到的敏感性內容來建議或自動套用敏感度標籤。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-396">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

- <span data-ttu-id="2e9d4-397">**在 Excel 中建立來自 Power BI 資料的樞紐分析表：** 您可以在 Excel 中建立樞紐分析表，只要按幾下滑鼠，就能連線到儲存在 Power BI 的樞紐分析表。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-397">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="2e9d4-398"> 如此一來，您就能獲得樞紐分析表和 Power BI 的最佳效果。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-398">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="2e9d4-399">使用安全 Power BI 資料集的樞紐分析表以計算、摘要及分析資料。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-399">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="2e9d4-400">深入了解</span><span class="sxs-lookup"><span data-stu-id="2e9d4-400">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)<br /><span data-ttu-id="2e9d4-401">在[部落格文章](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="2e9d4-401">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="2e9d4-402">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e9d4-402">Outlook</span></span>

- <span data-ttu-id="2e9d4-403">**在 Outlook 中使用 [快速投票] 建立投票：** 輕鬆建立投票，收集投票，並查看電子郵件中的結果 [深入瞭解](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="2e9d4-403">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="2e9d4-404">**將圖片作為電子郵件的一部分傳送時，讓圖片保持高畫質：** 一個新 Outlook 設定，可讓您在隨著電子郵件內容傳送圖片時限制圖片壓縮</span><span class="sxs-lookup"><span data-stu-id="2e9d4-404">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>

- <span data-ttu-id="2e9d4-405">**快速重新開啟上一個工作階段的項目：** 我們新增了一個選項，可快速重新開啟上一個 Outlook 工作階段的項目。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-405">**Quickly reopen items from previous session:** We added an option to quickly reopen items from a previous Outlook session.</span></span> <span data-ttu-id="2e9d4-406">不管 Outlook 當機或您將其關閉，您現在可以在重新開啟應用程式時快速重新啟動項目。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-406">Whether Outlook crashes or you close it, you’ll now be able to quickly relaunch items when you reopen the app.</span></span> <span data-ttu-id="2e9d4-407">這項功能預設為啟用。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-407">This feature is on by default.</span></span> <span data-ttu-id="2e9d4-408">若要將它關閉，請移至 [選項] > [一般] > [啟動選項]。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-408">To turn it off, go to Options > General > Start up Options.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2e9d4-409">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2e9d4-409">PowerPoint</span></span>

- <span data-ttu-id="2e9d4-410">**[自動套用] 或 [建議敏感度] 標籤：** Office 可以根據偵測到的敏感性內容來推薦或自動套用靈敏度標籤。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-410">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="teams"></a><span data-ttu-id="2e9d4-411">Teams</span><span class="sxs-lookup"><span data-stu-id="2e9d4-411">Teams</span></span>

- <span data-ttu-id="2e9d4-412">**新增簡化的通知設定：** 使用者現在可以使用增強的功能，以更簡單的方式管理其通知設定。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-412">**New simplified notification settings:** Users can now manage their notifications settings in a more simplified manner with enhanced functionalities.</span></span>

- <span data-ttu-id="2e9d4-413">**Teams 現在支援 Windows 原生通知：** 使用者現在可以選取其偏好的通知傳送方式，即透過 Teams 內建橫幅或 Windows 原生橫幅。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-413">**Windows Native Notification are now Supported on Teams:** Users can now select their preferred means of notification delivery, either through teams built in banners or the windows native banners.</span></span>

- <span data-ttu-id="2e9d4-414">**頻道資訊窗格：** 選取頻道標頭中的 [頻道資訊] 圖示時，將開啟一個窗格，其中會顯示頻道資訊的摘要，包括頻道描述、最近的參與者和成員清單，以及系統訊息的新首頁。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-414">**Channel Info Pane:** When selecting on the "Channel info" icon in the channel header, a pane will open where you will see a summary of channel information including the channel description, a list of recent contributors and members, as well as the new home for system messages.</span></span>

- <span data-ttu-id="2e9d4-415">**關閉聊天通知的預覽：** 使用者可以變更設定，並管理其聊天通知快顯的預覽。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-415">**Turn off previews for your chat notifications:** Users can change settings and manage previews for their chat notification toasts.</span></span>

- <span data-ttu-id="2e9d4-416">**建議的回覆：** 我們新增了讓 Teams 使用者對其交談具備建議的回覆功能。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-416">**Suggested replies:** We added the ability for Teams users to have a suggested reply to their conversations.</span></span> <span data-ttu-id="2e9d4-417">這些建議會顯示在聊天訊息的底部 (如果已啟用)。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-417">These suggestions will appear at the bottom of a chat message if they are enabled.</span></span> <span data-ttu-id="2e9d4-418">它們能讓您快速輕鬆地回覆訊息！</span><span class="sxs-lookup"><span data-stu-id="2e9d4-418">They make replying to messages quick and easy!</span></span>

### <a name="word"></a><span data-ttu-id="2e9d4-419">Word</span><span class="sxs-lookup"><span data-stu-id="2e9d4-419">Word</span></span>

- <span data-ttu-id="2e9d4-420">**[自動套用] 或 [建議敏感度] 標籤：** Office 可以根據偵測到的敏感性內容來推薦或自動套用靈敏度標籤。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-420">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

- <span data-ttu-id="2e9d4-421">**以向量保留文字：** 現在當您在 Excel、Word 和 PowerPoint 中轉換地圖、圖表和其他 SVG 向量等物件時，您可以保留物件中的文字。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-421">**Retain text in vectors:** Now you can retain the text in maps, charts, and other SVG vectors when converting these objects in Excel, Word, and PowerPoint.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e9d4-424">解決的問題</span><span class="sxs-lookup"><span data-stu-id="2e9d4-424">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2e9d4-425">Access</span><span class="sxs-lookup"><span data-stu-id="2e9d4-425">Access</span></span>

- <span data-ttu-id="2e9d4-426">此修正會解決嘗試執行之前會產生「查詢太複雜」錯誤訊息的特定查詢的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-426">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex".</span></span>

### <a name="excel"></a><span data-ttu-id="2e9d4-427">Excel</span><span class="sxs-lookup"><span data-stu-id="2e9d4-427">Excel</span></span>

- <span data-ttu-id="2e9d4-428">修正在分頁預覽中載入含有多個工作表的活頁簿時，可能會發生錯誤或當機的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-428">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>


### <a name="outlook"></a><span data-ttu-id="2e9d4-429">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e9d4-429">Outlook</span></span>

- <span data-ttu-id="2e9d4-430">解決會導致 CLP 使用者在回覆時的寄件者地址，從受保護的內容切換到未受保護的內容時會發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-430">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>


- <span data-ttu-id="2e9d4-431">解決會導致若「未」核取 [下載共用資料夾]，共用行事曆會議的 [回應選項] 中會遺失 [允許轉寄] 選項的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-431">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>


- <span data-ttu-id="2e9d4-432">解決在編輯經理行事曆上的現有行事曆約會時，導致代理人收到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-432">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>


- <span data-ttu-id="2e9d4-433">解決了當選取安全性對話方塊上的 [儲存] 選項時，導致使用者無法將 OneDrive 外部的 OneDrive 附件儲存至他們的本機電腦的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-433">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="2e9d4-434">解決導致 [排程助理員] 頁面無法顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-434">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>

- <span data-ttu-id="2e9d4-435">解決事件通知警示中導致格式設定問題的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-435">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>

### <a name="project"></a><span data-ttu-id="2e9d4-436">Project</span><span class="sxs-lookup"><span data-stu-id="2e9d4-436">Project</span></span>

- <span data-ttu-id="2e9d4-437">已修正 [指派資源] 對話方塊中選取的工作與工作面板檢視中所選工作不同的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-437">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>

- <span data-ttu-id="2e9d4-438">修正當您貼上的工作具有多個依存性時，無法正確複製所有依存性的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-438">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>

- <span data-ttu-id="2e9d4-439">修正無法將 PDF/XPS 從 Project 儲存至 SharePoint 文件庫的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-439">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2e9d4-440">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2e9d4-440">Office Suite</span></span>

- <span data-ttu-id="2e9d4-441">修正即使完整產品的轉換已完成，也會導致執行階段訊息顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-441">Fixed an issue that caused a runtime message to show even though the transition to the full product is complete.</span></span> <span data-ttu-id="2e9d4-442">此問題的修正程式是確保服務正確計算新增的產品。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-442">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="2e9d4-443">我們已篩選出新增的產品 (確保它們同時存在於新的設定中)，並將它們新增到現有產品發行識別碼的結尾。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-443">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-july-28"></a><span data-ttu-id="2e9d4-445">版本 2006：7 月 28 日</span><span class="sxs-lookup"><span data-stu-id="2e9d4-445">Version 2006: July 28</span></span>
<span data-ttu-id="2e9d4-446">*版本 2006 (組建 13001.20498)*</span><span class="sxs-lookup"><span data-stu-id="2e9d4-446">*Version 2006 (Build 13001.20498)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e9d4-448">解決的問題</span><span class="sxs-lookup"><span data-stu-id="2e9d4-448">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2e9d4-449">Excel</span><span class="sxs-lookup"><span data-stu-id="2e9d4-449">Excel</span></span>

- <span data-ttu-id="2e9d4-450">修正在分頁預覽中載入含有多個工作表的活頁簿時，可能會發生錯誤或當機的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-450">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>


### <a name="outlook"></a><span data-ttu-id="2e9d4-451">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e9d4-451">Outlook</span></span>

- <span data-ttu-id="2e9d4-452">我們已修正複製和貼上 SVG 影像的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-452">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="word"></a><span data-ttu-id="2e9d4-453">Word</span><span class="sxs-lookup"><span data-stu-id="2e9d4-453">Word</span></span>

- <span data-ttu-id="2e9d4-454">我們已修正複製和貼上 SVG 影像的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-454">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2e9d4-455">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2e9d4-455">Office Suite</span></span>

- <span data-ttu-id="2e9d4-456">關閉 Office 檔案時，計時問題可能會導致當機。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-456">A timing issue could cause a crash when closing office files.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-july-14"></a><span data-ttu-id="2e9d4-458">版本 2006：7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="2e9d4-458">Version 2006: July 14</span></span>
<span data-ttu-id="2e9d4-459">*版本 2006 (組建 13001.20384)*</span><span class="sxs-lookup"><span data-stu-id="2e9d4-459">*Version 2006 (Build 13001.20384)*</span></span>

<span data-ttu-id="2e9d4-460">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2e9d4-460">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e9d4-462">解決的問題</span><span class="sxs-lookup"><span data-stu-id="2e9d4-462">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2e9d4-463">Access</span><span class="sxs-lookup"><span data-stu-id="2e9d4-463">Access</span></span>

- <span data-ttu-id="2e9d4-464">解決插入含有身分識別 (例如，自動編號) 欄位的連結 SQL 資料表的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-464">Resolved an issue with inserting linked SQL tables that include an identity (e.g. autonumber) field.</span></span>

### <a name="excel"></a><span data-ttu-id="2e9d4-465">Excel</span><span class="sxs-lookup"><span data-stu-id="2e9d4-465">Excel</span></span>

- <span data-ttu-id="2e9d4-466">自動文件分類可能已對處於唯讀模式的活頁簿發生。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-466">Automatic document classification may have occurred for workbooks that were in read-only mode.</span></span>

- <span data-ttu-id="2e9d4-467">修正若您已從帳戶登出，嘗試建立資料連線時，可能會發生的當機問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-467">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

### <a name="onenote"></a><span data-ttu-id="2e9d4-468">OneNote</span><span class="sxs-lookup"><span data-stu-id="2e9d4-468">OneNote</span></span>

- <span data-ttu-id="2e9d4-469">改善共同撰寫狀態的偵測，以降低資源利用率。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-469">Improve detection of co-authoring status to reduce resource utilization.</span></span>

### <a name="outlook"></a><span data-ttu-id="2e9d4-470">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e9d4-470">Outlook</span></span>

- <span data-ttu-id="2e9d4-471">解決了當選取安全性對話方塊上的 [儲存] 選項時，導致使用者無法將 OneDrive 外部的 OneDrive 附件儲存至他們的本機電腦的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-471">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2e9d4-472">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2e9d4-472">Office Suite</span></span>

- <span data-ttu-id="2e9d4-473">我們會將新的 AppV51 向後移，以修正先前 AppV51 中的回歸。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-473">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="2e9d4-474">解決在登錄 TabProcGrowth 值為 REG_SZ 類型的情況下啟用增益集時，Windows 中的 Office 主機會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-474">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-june-30"></a><span data-ttu-id="2e9d4-476">版本 2006：6 月 30 日</span><span class="sxs-lookup"><span data-stu-id="2e9d4-476">Version 2006: June 30</span></span>
<span data-ttu-id="2e9d4-477">*版本2006（組建13001.20266）*</span><span class="sxs-lookup"><span data-stu-id="2e9d4-477">*Version 2006 (Build 13001.20266)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="2e9d4-479">功能更新</span><span class="sxs-lookup"><span data-stu-id="2e9d4-479">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2e9d4-480">Excel</span><span class="sxs-lookup"><span data-stu-id="2e9d4-480">Excel</span></span>

- <span data-ttu-id="2e9d4-481">**較長的檔案名稱：** Windows 桌面版專用 Excel 現在支援使用最多 400 個字元名稱和路徑的 OneDrive/SharePoint 檔案。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-481">**Longer file names:** Excel for Windows desktop now supports OneDrive/SharePoint files with names and paths of up to 400 characters.</span></span>

- <span data-ttu-id="2e9d4-482">**RealTimeData (RTD) 的改進：** 在 Office 365 版本 2002 的每月通道或更新版本中，Excel RealTimeData (RTD) 函數速度比在 Excel 2010 試算表中計算資料還快。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-482">**Realtimedata (RTD) improvements:** In Office 365 version 2002 monthly channel and later, Excel's RealTimeData (RTD) function is much faster than Excel 2010 calculating data in the spreadsheet.</span></span> <span data-ttu-id="2e9d4-483">我們在其基礎記憶體和資料結構中移除了瓶頸，並使其成為安全執行緒，讓它可在多執行緒重新計算 (MTR) 的所有可用執行緒上計算。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-483">We removed bottlenecks in its underlying memory and data structures as well as made it thread-safe to allow  it to be calculated on all available threads of Multithreaded recalculation (MTR).</span></span>

### <a name="outlook"></a><span data-ttu-id="2e9d4-484">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e9d4-484">Outlook</span></span>

- <span data-ttu-id="2e9d4-485">**在 Outlook 中撰寫郵件時有新的選項可停用 @ 提及建議：** 您是否覺得 @ 提及的選擇器很煩人，一點都不好用？</span><span class="sxs-lookup"><span data-stu-id="2e9d4-485">**New option to disable @ mention suggestions when composing mail in Outlook:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="2e9d4-486">現在您可以視需要將其關閉了。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-486">Now you can turn it off if you prefer.</span></span><br /><span data-ttu-id="2e9d4-487">在[部落格文章](https://blog-insider.office.com/2020/03/26/feedback-in-action-disable-mentions/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="2e9d4-487">See details in [blog post](https://blog-insider.office.com/2020/03/26/feedback-in-action-disable-mentions/)</span></span>

- <span data-ttu-id="2e9d4-488">**IT 系統管理員的事件通知：** Microsoft 365 租用戶全域系統管理員和 Office 應用程式系統會在 Windows 版 Outlook 的新右側面板中收到影響其使用者的 Outlook 和 O365 Exchange 事件通知。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-488">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="2e9d4-489">深入了解</span><span class="sxs-lookup"><span data-stu-id="2e9d4-489">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

- <span data-ttu-id="2e9d4-490">**新增至 Outlook 快顯通知的其他按鈕：** [快速動作] 按鈕現在會於在 Windows 10 上執行 Outlook 時顯示在 Outlook 快顯通知中</span><span class="sxs-lookup"><span data-stu-id="2e9d4-490">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2e9d4-491">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2e9d4-491">PowerPoint</span></span>

- <span data-ttu-id="2e9d4-492">**改善的 PowerPoint 中的 Steam 影片效能：** 我們改善了 Microsoft Stream 影片的播放效能，將影片載入時間減至最少，以建立出流暢的觀賞體驗。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-492">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="2e9d4-493">您可以在 Microsoft Stream 上使用公司影片來建立更完善的簡報。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-493">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

### <a name="teams"></a><span data-ttu-id="2e9d4-494">Teams</span><span class="sxs-lookup"><span data-stu-id="2e9d4-494">Teams</span></span>

- <span data-ttu-id="2e9d4-495">**針對外部使用者遮罩 PSTN 參與者電話號碼：** 針對為其 Teams 會議啟用音訊會議的客戶，我們會對從組織外部加入的使用者，將 PSTN 參與者的電話號碼遮罩起來。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-495">**PSTN participant phone numbers are masked from external users:** For customers with Audio Conferencing enabled for their Teams meetings, we will mask the PSTN participant's phone number to users who have joined from outside of your organization.</span></span>

- <span data-ttu-id="2e9d4-496">**管理您的頻道通知設定的簡化方式：** 透過團隊和頻道清單或從頻道標頭，使用者只要按一下即可將所有活動開啟或關閉就能快速管理其通知設定，或深入了解自訂以快速設定其偏好的通知排列組合。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-496">**Simplified way to manage your channel notification settings:** Through the teams and channels list or from the channel header, the users can quickly manage their notification settings by turning all activity on or off with a single click or diving deep into custom to set their preferred permutations.</span></span>

- <span data-ttu-id="2e9d4-497">**Walkie Talkie：** 使用按著即可發言即時語音通訊。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-497">**Walkie Talkie:** Instant voice communication using push-to-talk.</span></span>

### <a name="word"></a><span data-ttu-id="2e9d4-498">Word</span><span class="sxs-lookup"><span data-stu-id="2e9d4-498">Word</span></span>

- <span data-ttu-id="2e9d4-499">**螢幕閱讀器的動作確認：** 確認動作是重要的協助工具要求。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-499">**Confirmation of action in screen readers:** Confirmation of action is an important accessibility requirement.</span></span> <span data-ttu-id="2e9d4-500">隨著 Windows 引入新的通知 API 之後，我們現在就能通知螢幕助讀程式使用者的動作成功。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-500">With the introduction of a new Notification API from Windows, we are now able to alert screen reader users about the success of their actions.</span></span> <span data-ttu-id="2e9d4-501">[剪下]、[複製]、[貼上]、[粗體]、[畫底線]、[復原]、[重做]、[自動校正] 和 [自動大小寫] 等功能都已公布給 Win32 Word 的朗讀程式使用者。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-501">Cut, copy, paste, bold, italic, underline, undo, redo, auto corrections, and auto-capitalizations are now all announced to Narrator users in Win32 Word.</span></span> <span data-ttu-id="2e9d4-502">若要啟用此功能，請按 windows + ctrl + enter 以開啟朗讀程式。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-502">To enable this feature, turn on Narrator by pressing windows + ctrl + enter.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e9d4-505">解決的問題</span><span class="sxs-lookup"><span data-stu-id="2e9d4-505">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2e9d4-506">Access</span><span class="sxs-lookup"><span data-stu-id="2e9d4-506">Access</span></span>

- <span data-ttu-id="2e9d4-507">我們已修正執行查詢的時間大約比預期完成時間兩倍久的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-507">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>


### <a name="excel"></a><span data-ttu-id="2e9d4-508">Excel</span><span class="sxs-lookup"><span data-stu-id="2e9d4-508">Excel</span></span>

- <span data-ttu-id="2e9d4-509">已修正當儲存至 SharePoint/OneDrive 時，會導致自訂功能區索引標籤 CustomUI XML 的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-509">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>


### <a name="outlook"></a><span data-ttu-id="2e9d4-510">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e9d4-510">Outlook</span></span>

- <span data-ttu-id="2e9d4-511">解決會導致使用者看到他們透過拖放附件，以複製到其檔案系統所建立附件的建立日期設為 4501 年 1 月 1 日的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-511">Addressed an issue that caused users to see the creation date of attachments that they copied to their file system via drag and drop getting set to January 1, 4501.</span></span>

- <span data-ttu-id="2e9d4-512">解決會導致共用行事曆改善功能的使用者看到行事曆失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-512">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>


- <span data-ttu-id="2e9d4-513">解決會導致使用者看到 Outlook 持續提示他們執行收件匣修復工具的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-513">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>


- <span data-ttu-id="2e9d4-514">解決啟用雲端設定時，會造成 Ctrl + 按一下停止運作的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-514">Addressed an issue that caused Ctrl+click to stop working when cloud settings were enabled.</span></span>


- <span data-ttu-id="2e9d4-515">解決會導致在「建議功能」中尋找功能不會傳回結果，因而讓使用者無法選擇提交新功能想法的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-515">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>


### <a name="project"></a><span data-ttu-id="2e9d4-516">Project</span><span class="sxs-lookup"><span data-stu-id="2e9d4-516">Project</span></span>

- <span data-ttu-id="2e9d4-517">修正 URL 以 .com 結尾時，無法從 Project Web App 在 Project 傳統型用戶端開啟專案的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-517">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>


- <span data-ttu-id="2e9d4-518">已修正當專案摘要工作-或是專案[開始/工作]欄位有變更時，ProjectBeforeTaskChange 事件不會觸發的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-518">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>


- <span data-ttu-id="2e9d4-519">已修正當標示為100% 完成之工作錯誤地變更為完成度低於100% 的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-519">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>


### <a name="word"></a><span data-ttu-id="2e9d4-520">Word</span><span class="sxs-lookup"><span data-stu-id="2e9d4-520">Word</span></span>

- <span data-ttu-id="2e9d4-521">解決 URL 包含查詢元件時，從自訂文件傳遞 (aspx) 開啟 Word 文件的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-521">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-june-24"></a><span data-ttu-id="2e9d4-523">版本 2005：6 月 24 日</span><span class="sxs-lookup"><span data-stu-id="2e9d4-523">Version 2005: June 24</span></span>
<span data-ttu-id="2e9d4-524">*版本 2005 (組建 12827.20470)*</span><span class="sxs-lookup"><span data-stu-id="2e9d4-524">*Version 2005 (Build 12827.20470)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e9d4-526">解決的問題</span><span class="sxs-lookup"><span data-stu-id="2e9d4-526">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2e9d4-527">Access</span><span class="sxs-lookup"><span data-stu-id="2e9d4-527">Access</span></span>

- <span data-ttu-id="2e9d4-528">現已修正此錯誤；您應該可以呼叫日期/時間延伸資料類型至您的程式碼，而不會在您的應用程式中遇到任何當機。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-528">This bug has now been fixed; you should be able to call the Date/Time Extended data type into your code without experiencing any crash in your app.</span></span> <span data-ttu-id="2e9d4-529">請讓團隊知道您是否遇到其他問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-529">Please let the team know if you encounter further issues.</span></span>


- <span data-ttu-id="2e9d4-530">現已修正此問題；您現在可以還原為最新的 Access 版本，並使用 DAO/VBA 來管理及編輯十進位資料類型。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-530">This issue has now been fixed; you can now revert back to your most updated Access version, and use DAO/VBA to manage and edit a decimal data type.</span></span> <span data-ttu-id="2e9d4-531">如果您在使用我們的資料類型時遇到任何進一步問題，請讓 Access 團隊知道。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-531">Please let the Access team know if you encounter any further issues with using our data type.</span></span>


### <a name="excel"></a><span data-ttu-id="2e9d4-532">Excel</span><span class="sxs-lookup"><span data-stu-id="2e9d4-532">Excel</span></span>

- <span data-ttu-id="2e9d4-533">已修正當儲存至 SharePoint/OneDrive 時，會導致自訂功能區索引標籤 CustomUI XML 的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-533">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>





### <a name="outlook"></a><span data-ttu-id="2e9d4-534">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e9d4-534">Outlook</span></span>

- <span data-ttu-id="2e9d4-535">解決了 Outlook 無法啟用 [資料遺失保護原則] 提示使用 M365 商務版進階方案並為此服務付款的的使用者之問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-535">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>


- <span data-ttu-id="2e9d4-536">解決會導致使用者看到他們透過拖放附件，以複製到其檔案系統所建立附件的建立日期設為 4501 年 1 月 1 日的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-536">Addressed an issue that caused users to see the creation date of attachments that they copied to their file system via drag and drop getting set to January 1, 4501.</span></span>


- <span data-ttu-id="2e9d4-537">解決會導致使用者在 Outlook 中更新其規則時，看到&quot;此電腦上的規則與 Microsoft Exchange 上的規則不相符&quot;訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-537">Addressed an issue that caused users to see the &quot;The rules on this computer do not match the rules on Microsoft Exchange&quot; message when updating their rules in Outlook.</span></span>


- <span data-ttu-id="2e9d4-538">解決會導致共用行事曆改善功能的使用者看到行事曆失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-538">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>


- <span data-ttu-id="2e9d4-539">解決會導致使用者在某些情況下遇到間歇性懸置和當機的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-539">Addressed an issue that caused users to experience intermittent hangs and crashes in some scenarios.</span></span>


- <span data-ttu-id="2e9d4-540">解決會導致使用者看到 Outlook 持續提示他們執行收件匣修復工具的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-540">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>


- <span data-ttu-id="2e9d4-541">解決會導致在「建議功能」中尋找功能不會傳回結果，因而讓使用者無法選擇提交新功能想法的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-541">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2e9d4-542">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2e9d4-542">PowerPoint</span></span>

- <span data-ttu-id="2e9d4-543">我們已修正建議窗格的當機問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-543">We have fixed a crash issue with suggestion pane.</span></span>


### <a name="project"></a><span data-ttu-id="2e9d4-544">Project</span><span class="sxs-lookup"><span data-stu-id="2e9d4-544">Project</span></span>

- <span data-ttu-id="2e9d4-545">修正當標示為 100% 完成之工作錯誤地變更為低於 100% 完成的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-545">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

### <a name="word"></a><span data-ttu-id="2e9d4-546">Word</span><span class="sxs-lookup"><span data-stu-id="2e9d4-546">Word</span></span>

- <span data-ttu-id="2e9d4-547">解決會導致從應用程式拖曳部分內容時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-547">Resolved an issue that may have caused a crash when dragging some content from the app.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2e9d4-548">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2e9d4-548">Office Suite</span></span>

- <span data-ttu-id="2e9d4-549">此變更會解決載入和播放動畫內容 (例如 Gif 或3D 模型) 時可能會發生的懸置。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-549">This change addresses potential hangs when loading and playing animated content such as GIFs or 3D models.</span></span>




[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-june-09"></a><span data-ttu-id="2e9d4-551">版本 2005：6 月 9 日</span><span class="sxs-lookup"><span data-stu-id="2e9d4-551">Version 2005: June 09</span></span>
<span data-ttu-id="2e9d4-552">*版本 2005 (組建 12827.20336)*</span><span class="sxs-lookup"><span data-stu-id="2e9d4-552">*Version 2005 (Build 12827.20336)*</span></span>

<span data-ttu-id="2e9d4-553">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2e9d4-553">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="feature-updates"></a><span data-ttu-id="2e9d4-554">功能更新</span><span class="sxs-lookup"><span data-stu-id="2e9d4-554">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2e9d4-555">Excel</span><span class="sxs-lookup"><span data-stu-id="2e9d4-555">Excel</span></span>

- <span data-ttu-id="2e9d4-556">**[筆跡工具箱] 中的 [套索工具] 和 [橡皮擦]:** 使用繪圖工具時，[筆跡工具箱] 現在提供 [套索工具] 和 [橡皮擦] 功能。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-556">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2e9d4-557">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2e9d4-557">PowerPoint</span></span>

- <span data-ttu-id="2e9d4-558">**[筆跡工具箱] 中的 [套索工具] 和 [橡皮擦]:** 使用繪圖工具時，[筆跡工具箱] 現在提供 [套索工具] 和 [橡皮擦] 功能。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-558">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span>

### <a name="word"></a><span data-ttu-id="2e9d4-559">Word</span><span class="sxs-lookup"><span data-stu-id="2e9d4-559">Word</span></span>

- <span data-ttu-id="2e9d4-560">**[筆跡工具箱] 中的 [套索工具] 和 [橡皮擦]:** 使用繪圖工具時，[筆跡工具箱] 現在提供 [套索工具] 和 [橡皮擦] 功能。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-560">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span>




[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e9d4-563">解決的問題</span><span class="sxs-lookup"><span data-stu-id="2e9d4-563">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2e9d4-564">Excel</span><span class="sxs-lookup"><span data-stu-id="2e9d4-564">Excel</span></span>

- <span data-ttu-id="2e9d4-565">解決嘗試將樞紐分析表插入圖表時 Excel 可能會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-565">Addresses an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2e9d4-566">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2e9d4-566">PowerPoint</span></span>

- <span data-ttu-id="2e9d4-567">這可修正使用者在同一檔案中同時有新版和舊版批註，因此觸發批註的升級而當機的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-567">This fixes a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>

### <a name="project"></a><span data-ttu-id="2e9d4-568">Project</span><span class="sxs-lookup"><span data-stu-id="2e9d4-568">Project</span></span>

- <span data-ttu-id="2e9d4-569">已修正當專案摘要工作-或是專案[開始/工作]欄位有變更時，ProjectBeforeTaskChange 事件不會觸發的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-569">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2e9d4-570">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2e9d4-570">Office Suite</span></span>

- <span data-ttu-id="2e9d4-571">我們透過設定Bing附加預設安裝驗證設定為true默認，並將MSI返回成功視為安裝成功，而解決了 ValidateInstall 失敗率問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-571">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-june-02"></a><span data-ttu-id="2e9d4-573">版本 2005：6 月 2 日</span><span class="sxs-lookup"><span data-stu-id="2e9d4-573">Version 2005: June 02</span></span>
<span data-ttu-id="2e9d4-574">*版本2005（組建12827.20268）*</span><span class="sxs-lookup"><span data-stu-id="2e9d4-574">*Version 2005 (Build 12827.20268)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="2e9d4-576">功能更新</span><span class="sxs-lookup"><span data-stu-id="2e9d4-576">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2e9d4-577">Excel</span><span class="sxs-lookup"><span data-stu-id="2e9d4-577">Excel</span></span>

- <span data-ttu-id="2e9d4-578">**自動使用新的資料類型** ：當您輸入的資料值類似股票或地理位置時，Excel 會將該值轉換為正確的連結資料類型 - 股票或地理位置。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-578">**Automatically use new data types:** When you type a data value that resembles a stock or a geographic location, Excel offers to convert it to the right connected data type - Stocks or Geography.</span></span> [<span data-ttu-id="2e9d4-579">深入了解</span><span class="sxs-lookup"><span data-stu-id="2e9d4-579">Learn more</span></span>](https://support.office.com/article/61a33056-9935-484f-8ac8-f1a89e210877)

- <span data-ttu-id="2e9d4-580">**使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦</span><span class="sxs-lookup"><span data-stu-id="2e9d4-580">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier</span></span>

### <a name="outlook"></a><span data-ttu-id="2e9d4-581">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e9d4-581">Outlook</span></span>

- <span data-ttu-id="2e9d4-582">**協助保護群組中的資料：** 建立群組時所選擇的「敏感度」標籤會套用到群組電子郵件、文件及小組網站</span><span class="sxs-lookup"><span data-stu-id="2e9d4-582">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites</span></span>

- <span data-ttu-id="2e9d4-583">**更好的結果—瞬間：** 我們更新了搜尋體驗，讓這個版本比以往更聰明、更快速，且更可靠。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-583">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="2e9d4-584">深入了解</span><span class="sxs-lookup"><span data-stu-id="2e9d4-584">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="2e9d4-585">**使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦</span><span class="sxs-lookup"><span data-stu-id="2e9d4-585">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier</span></span>

- <span data-ttu-id="2e9d4-586">**行事曆煥然一新：** 查看視覺更新，讓您的行事曆更容易流覽。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-586">**Calendar gets a makeover:** See visual updates that make your calendar easier to scan.</span></span> [<span data-ttu-id="2e9d4-587">深入了解</span><span class="sxs-lookup"><span data-stu-id="2e9d4-587">Learn more</span></span>](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br /><span data-ttu-id="2e9d4-588">在[部落格文章](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="2e9d4-588">See details in [blog post](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2e9d4-589">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2e9d4-589">PowerPoint</span></span>

- <span data-ttu-id="2e9d4-590">**使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦 [深入了解](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)</span><span class="sxs-lookup"><span data-stu-id="2e9d4-590">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier [Learn more](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)</span></span>

- <span data-ttu-id="2e9d4-591">**在簡報時同步處理變更：** 即使簡報處於投影片放映模式，仍可即時同步處理所做的變更。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-591">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span> [<span data-ttu-id="2e9d4-592">深入了解</span><span class="sxs-lookup"><span data-stu-id="2e9d4-592">Learn more</span></span>](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br /><span data-ttu-id="2e9d4-593">在[部落格文章](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="2e9d4-593">See details in [blog post](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span></span>

- <span data-ttu-id="2e9d4-594">**不需要簡報導覽裝置：有耳塞式耳機就夠了：** 使用您的 Surface Earbuds 控制 PowerPoint 簡報。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-594">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="2e9d4-595">運作方式：配對之後，您必須在 PowerPoint 中啟用功能。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-595">How it works:  Once paired, you'll need to enable the feature in PowerPoint.</span></span> <span data-ttu-id="2e9d4-596">按 F5 或選取 [投影片放映] > [從開頭] 開始簡報。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-596">Start a presentation by pressing F5 or selecting Slide Show > From Beginning.</span></span>  <span data-ttu-id="2e9d4-597">在投影片放映中，以滑鼠右鍵按一下投影片，然後在 [Surface Earbuds 設定] 底下，選擇 [使用手勢來控制簡報]。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-597">In Slide Show, right click on the slide and under Surface Earbuds Settings choose Use Gestures to Control Presentation.</span></span>  <span data-ttu-id="2e9d4-598">將記住此設定以用於所有未來的簡報。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-598">This setting will be remembered for all future presentations.</span></span> <span data-ttu-id="2e9d4-599">現在，您可以在左耳機上向前後撥動，以在 [投影片放映] 模式中瀏覽簡報。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-599">You can now can swipe forward and backward on the left earbud to navigate your presentations in Slide Show mode.</span></span>  <span data-ttu-id="2e9d4-600">點兩下以播放或暫停內嵌的影片。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-600">Double tap to play or pause embedded videos.</span></span>  <span data-ttu-id="2e9d4-601">重要：您必須在 Windows 10 的 Surface 音訊應用程式中配對 Surface Earbuds，才能使用手勢來控制簡報。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-601">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="2e9d4-602">在此取得 Windows 10 上 Surface 音訊應用程式入門的指示。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-602">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="2e9d4-603">深入了解</span><span class="sxs-lookup"><span data-stu-id="2e9d4-603">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

### <a name="teams"></a><span data-ttu-id="2e9d4-604">Teams</span><span class="sxs-lookup"><span data-stu-id="2e9d4-604">Teams</span></span>

- <span data-ttu-id="2e9d4-605">**對 Teams 會議中視訊版面配置所做的變更：** 在 Teams 會議期間可同時檢視的參與者人數，很快地將從 4 個增加到 9 個。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-605">**Changes to video layout in Teams meetings:** Soon, the number of participants that can be viewed simultaneously during a Teams meeting will increase from 4 to 9.</span></span>

- <span data-ttu-id="2e9d4-606">**在即時活動中包含系統音訊：** 即時活動中的簡報者和製作人，現在可以在即時活動期間共用桌面或視窗螢幕時包含系統音訊。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-606">**Include system audio in live events:** Presenters and producers in live events can now include system audio when sharing a desktop or window screen during the live event.</span></span> <span data-ttu-id="2e9d4-607">這可讓您的使用者聽到您正在共用內容的任何音訊部分。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-607">This will allow your users to hear any audio part of the content you are sharing.</span></span>

- <span data-ttu-id="2e9d4-608">**讓召集人可以變更撥入參與者的大廳設定：** 此設定會控制透過電話撥入的人員是否直接加入會議，或是在大廳中等候，而不論 [自動准許人員] 的設定為何。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-608">**Enable organizers to change lobby settings for dial-in participants:** This setting controls whether people who dial in by phone join the meeting directly or wait in the lobby regardless of the Automatically admit people setting.</span></span>

- <span data-ttu-id="2e9d4-609">**在會議中舉手：** 使用者現在可以在會議中虛擬舉手！</span><span class="sxs-lookup"><span data-stu-id="2e9d4-609">**Raise Your Hand in Meetings:** Users can now raise a virtual hand in a meeting!</span></span> <span data-ttu-id="2e9d4-610">其他參與者會在會議舞台中您的名稱旁和名冊中您的名字旁看到您的舉手。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-610">Other participants will see your raised hand next to your name in the meeting stage and next to your name in the roster.</span></span>

- <span data-ttu-id="2e9d4-611">**自訂會議視訊背景：** 使用視訊會議時，您現在可以選擇要使用的不同靜態背景影像。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-611">**Customize meeting video backgrounds:** When you are meeting with video, you now have the choice of different static background images to use.</span></span> <span data-ttu-id="2e9d4-612">這可讓您顯示此影像，而不是您所在位置的實際背景。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-612">This will let you show this image and not the actual background of where you are sitting.</span></span>

- <span data-ttu-id="2e9d4-613">**新增更多人員至聊天：** 我們現在可以將最多 350 個人新增至單一聊天對話。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-613">**Add more people to chat:** We made it possible to now add up to 350 people to a single chat thread.</span></span>

- <span data-ttu-id="2e9d4-614">**您的活動摘要上設定齒輪：** 使用者現在可以從摘要左側滑軌透過設定齒輪的方式，直接存取活動摘要和通知設定。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-614">**Settings Gear on your Activity Feed:** Users can now directly access activity feed and notification setting from the feed left rail by the means of a settings gear.</span></span>

- <span data-ttu-id="2e9d4-615">**從 Teams 進行中的會議內輕鬆存取會議選項：** 我們讓會議召集人在 Teams 會議一開始，便能更快速且輕鬆地變更簡報者和大廳設定，方法是在參與者窗格中直接提供易於存取的連結。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-615">**Easily access meeting options from within a Teams meeting in progress:** We are making it easier for meeting organizers to quickly and easily change their presenter and lobby settings once a Teams meeting starts by providing an easy to access link directly in the participants pane.</span></span> <span data-ttu-id="2e9d4-616">此新功能將會同時對已排定和「立即開會」會議呈現。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-616">This new functionality will be present for both scheduled and “Meet Now” meetings.</span></span>

- <span data-ttu-id="2e9d4-617">**團隊與頻道分析** ：除了團隊分析以外，您現在也可以檢視頻道層級指標和深入資訊。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-617">**Team and channel analytics:** In addition to team analytics, now you can also view channel level metrics and insights.</span></span> <span data-ttu-id="2e9d4-618">我們也將時間週期增加到 90 天，使得您可以分析資料的時間較長。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-618">We've also enhanced the time period to 90 days so you can analyze data for longer periods.</span></span> <span data-ttu-id="2e9d4-619">除此以外，此版本還包含有關小組或頻道的文章、回覆和會議計數的新計量和圖表。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-619">Apart from that, this release also includes new metrics and charts around count of posts, replies and meetings for a team or channel.</span></span>

- <span data-ttu-id="2e9d4-620">**進入/結束宣告：** 我們新增了此功能，讓會議召集人能夠開啟或關閉會議的進入和結束宣告。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-620">**Entry/exit announcements:** We added this feature that lets meeting organizers have the ability to turn on or off entry and exit announcements for a meeting.</span></span>

### <a name="word"></a><span data-ttu-id="2e9d4-621">Word</span><span class="sxs-lookup"><span data-stu-id="2e9d4-621">Word</span></span>

- <span data-ttu-id="2e9d4-622">**解碼縮寫，而不需離開 Word：** 當您遇到縮寫時，Word 會試著根據其他人的使用方式來給予定義。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-622">**Decode acronyms without leaving Word:** When you encounter an acronym, Word will try to define it based on how others use it.</span></span>

- <span data-ttu-id="2e9d4-623">**使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦</span><span class="sxs-lookup"><span data-stu-id="2e9d4-623">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e9d4-626">解決的問題</span><span class="sxs-lookup"><span data-stu-id="2e9d4-626">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="2e9d4-627">Excel</span><span class="sxs-lookup"><span data-stu-id="2e9d4-627">Excel</span></span>

- <span data-ttu-id="2e9d4-628">已修正當 Excel 視窗透過 Teams 共用時，使用 Ctrl + Shift + 方向鍵滑動後，Excel 可能會無法回應的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-628">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="2e9d4-629">在某些情況下，按一下同一個活頁簿中某個位置的超連結會導致活頁簿被隱藏。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-629">In some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>

### <a name="outlook"></a><span data-ttu-id="2e9d4-630">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e9d4-630">Outlook</span></span>

- <span data-ttu-id="2e9d4-631">已解決有回應/轉寄標註的clp審查活動的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-631">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>

- <span data-ttu-id="2e9d4-632">解決會導致 Windows 10 伺服器版本的使用者看到警告「防毒軟體狀態: 無效」的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-632">Addressed an issue that caused users of Windows 10 server versions to see the warning "Antivirus status: Invalid".</span></span> <span data-ttu-id="2e9d4-633">此版本的 Windows 支援防毒軟體偵測，但即使已正確安裝防毒軟體，也找不到防毒軟體。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-633">This version of Windows supports antivirus detection, but no antivirus was found despite having anti virus correctly installed.</span></span>

- <span data-ttu-id="2e9d4-634">解決從系統管理員通知提交意見反應時，會導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-634">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>

### <a name="skype"></a><span data-ttu-id="2e9d4-635">Skype</span><span class="sxs-lookup"><span data-stu-id="2e9d4-635">Skype</span></span>

- <span data-ttu-id="2e9d4-636">當使用者收到將他們移至 Teams Only 的原則時，他們仍然可以使用商務版 Skype Outlook 增益集來排程會議。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-636">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span> <span data-ttu-id="2e9d4-637">在此更新之後，當客戶端讀取指示用戶為 Teams Only 的策略並進入僅限會議加入模式後，您將不再能用商務版 Skype 安排會議。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-637">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span> <span data-ttu-id="2e9d4-638">此外，如果商務版 Skype Outlook 增益集發現商務版 Skype 用戶端處於 [僅限會議加入] 模式，就無法自行啟動。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-638">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2e9d4-639">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2e9d4-639">Office Suite</span></span>

- <span data-ttu-id="2e9d4-640">此更新修正了 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-640">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="2e9d4-641">此更新解決了 Microsoft Office 中的一個問題：可能無法在執行時期正確找到 Visual Basic for Applications 專案，這些專案的參照預期透搜尋 PATH 環境變數指定的位置來找到，進而導致VBA 執行時期錯誤。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-641">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="2e9d4-642">當您啟用增益集，而登錄金鑰 HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth 被設為零時，辦公主機視窗會當機。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-642">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="2e9d4-643">這變更將修正此問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-643">This change would fix this issue.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-may-21"></a><span data-ttu-id="2e9d4-645">版本 2004：5 月 21 日</span><span class="sxs-lookup"><span data-stu-id="2e9d4-645">Version 2004: May 21</span></span>
<span data-ttu-id="2e9d4-646">*版本 2004 (組建 12730.20352)*</span><span class="sxs-lookup"><span data-stu-id="2e9d4-646">*Version 2004 (Build 12730.20352)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e9d4-648">解決的問題</span><span class="sxs-lookup"><span data-stu-id="2e9d4-648">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2e9d4-649">Excel</span><span class="sxs-lookup"><span data-stu-id="2e9d4-649">Excel</span></span>

- <span data-ttu-id="2e9d4-650">已修正當檔案路徑太長時，在檔案重新開啟之後外部連結會停止運作的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-650">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>


### <a name="outlook"></a><span data-ttu-id="2e9d4-651">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e9d4-651">Outlook</span></span>

- <span data-ttu-id="2e9d4-652">已解決在從系統管理人通知中提交意見反應時，使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-652">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2e9d4-653">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2e9d4-653">Office Suite</span></span>

- <span data-ttu-id="2e9d4-654">修正隨選即用會導致偶爾無法更新至最新組建的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-654">Fixed a Click-to-Run issue which was resulting in occasional update failures to the latest builds.</span></span>

- <span data-ttu-id="2e9d4-655">解決 Microsoft Office 中的 Visual Basic for Applications 專案，其具有的參照預期應透過搜尋 PATH 環境變數指定的位置來找到，但在執行時期中可能無法正確找到，導致 VBA 執行時期錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-655">Fixed an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-may-12"></a><span data-ttu-id="2e9d4-657">版本 2004：5 月 12 日</span><span class="sxs-lookup"><span data-stu-id="2e9d4-657">Version 2004: May 12</span></span>
<span data-ttu-id="2e9d4-658">*版本 2004 (組建 12730.20270)*</span><span class="sxs-lookup"><span data-stu-id="2e9d4-658">*Version 2004 (Build 12730.20270)*</span></span>

<span data-ttu-id="2e9d4-659">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2e9d4-659">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e9d4-661">解決的問題</span><span class="sxs-lookup"><span data-stu-id="2e9d4-661">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2e9d4-662">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e9d4-662">Outlook</span></span>

- <span data-ttu-id="2e9d4-663">解決在顯示快顯通知時，使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-663">Addresses an issue that caused users to experience a crash when displaying toast notifications.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-may-04"></a><span data-ttu-id="2e9d4-665">版本 2004：5 月 4 日</span><span class="sxs-lookup"><span data-stu-id="2e9d4-665">Version 2004: May 04</span></span>
<span data-ttu-id="2e9d4-666">*版本 2004 (組建 12730.20250)*</span><span class="sxs-lookup"><span data-stu-id="2e9d4-666">*Version 2004 (Build 12730.20250)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e9d4-668">解決的問題</span><span class="sxs-lookup"><span data-stu-id="2e9d4-668">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="2e9d4-669">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2e9d4-669">Office Suite</span></span>

- <span data-ttu-id="2e9d4-670">此更新修正了 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-670">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-april-29"></a><span data-ttu-id="2e9d4-672">版本 2004：4 月 29 日</span><span class="sxs-lookup"><span data-stu-id="2e9d4-672">Version 2004: April 29</span></span>
<span data-ttu-id="2e9d4-673">*版本 2004 (組建 12730.20236)*</span><span class="sxs-lookup"><span data-stu-id="2e9d4-673">*Version 2004 (Build 12730.20236)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="2e9d4-675">功能更新</span><span class="sxs-lookup"><span data-stu-id="2e9d4-675">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="2e9d4-676">Access</span><span class="sxs-lookup"><span data-stu-id="2e9d4-676">Access</span></span>

- <span data-ttu-id="2e9d4-677">**在查詢設計工具、SQL 檢視和關聯視窗中工作時更具生產力：** 在資料表上按一下滑鼠右鍵即可開啟、設計、調整大小及隱藏它。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-677">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="2e9d4-678">在 SQL 檢視中搜尋及取代文字。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-678">Search and replace text in SQL View.</span></span> <span data-ttu-id="2e9d4-679">在 [關聯圖] 視窗中選取多個資料表。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-679">Select multiple tables in the Relationships window.</span></span>

- <span data-ttu-id="2e9d4-680">**按幾下就能新增資料表：** 使用 [新增資料表] 工作窗格，當您工作時，該窗格會保持開啟狀態，以便將資料表新增至關聯和查詢。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-680">**Add tables with fewer clicks:** Use the Add Tables task pane, which stays open while you work, to add tables to relationships and queries.</span></span> [<span data-ttu-id="2e9d4-681">深入了解</span><span class="sxs-lookup"><span data-stu-id="2e9d4-681">Learn more</span></span>](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)


### <a name="excel"></a><span data-ttu-id="2e9d4-682">Excel</span><span class="sxs-lookup"><span data-stu-id="2e9d4-682">Excel</span></span>

- <span data-ttu-id="2e9d4-683">**Facebook 連接器支援即將結束：** 於 2020 年 4 月起，Excel 就不再支援使用 Facebook 連接器的外部資料連線。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-683">**Facebook connector support is ending:** Starting in April 2020, Excel will no longer support external data connections that use the Facebook connector.</span></span>

- <span data-ttu-id="2e9d4-684">**有問題嗎？詢問 Excel** ：現在，Excel 構想可讓您提出有關資料的問題，而不需花時間編寫公式 (僅提供英文版)。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-684">**Have a question? Ask Excel:** Now Excel Ideas allows you to ask questions about your data - no need to spend time writing formulas (available in English only).</span></span> [<span data-ttu-id="2e9d4-685">深入了解</span><span class="sxs-lookup"><span data-stu-id="2e9d4-685">Learn more</span></span>](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- <span data-ttu-id="2e9d4-686">**讓活頁簿更生動的新影像：** 您可以在活頁簿中使用的數千個免版稅圖庫影像、圖示和貼紙。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-686">**New images to bring your workbooks to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your workbooks.</span></span> <span data-ttu-id="2e9d4-687">移至 [插入] > [圖片] > [圖庫影像] 以開始使用。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-687">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="2e9d4-688">深入了解</span><span class="sxs-lookup"><span data-stu-id="2e9d4-688">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

### <a name="outlook"></a><span data-ttu-id="2e9d4-689">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e9d4-689">Outlook</span></span>

- <span data-ttu-id="2e9d4-690">**加入會議而不需離開您的收件匣：** 不需切換至您的行事曆即可加入線上會議。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-690">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="2e9d4-691">將行事曆釘選到 [待辦事項] 窗格之後，只要按一下就能加入任何會議。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-691">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="2e9d4-692">**讓郵件更生動的新影像：** 您可以在電子郵件中使用的數千個免版稅圖庫影像、圖示和貼紙。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-692">**New images to bring your messages to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your email messages.</span></span> <span data-ttu-id="2e9d4-693">移至 [插入] > [圖片] > [圖庫影像] 以開始使用。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-693">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="2e9d4-694">深入了解</span><span class="sxs-lookup"><span data-stu-id="2e9d4-694">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

- <span data-ttu-id="2e9d4-695">**週期性會議的位置建議支援：** 搜尋會議室，並排定週期性會議。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-695">**Location suggestion support for recurring meeting:** Search for conference rooms with scheduling recurring meetings.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2e9d4-696">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2e9d4-696">PowerPoint</span></span>

- <span data-ttu-id="2e9d4-697">**在投影片放映期間更新投影片：** 在簡報期間，更新由其他作者變更的投影片。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-697">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>

- <span data-ttu-id="2e9d4-698">**讓投影片更生動的新影像：** 您可以在投影片中使用的數千個免版稅圖庫影像、圖示和貼紙。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-698">**New images to bring your slides to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your presentations.</span></span> <span data-ttu-id="2e9d4-699">移至 [插入] > [圖片] > [圖庫影像] 以開始使用。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-699">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="2e9d4-700">深入了解</span><span class="sxs-lookup"><span data-stu-id="2e9d4-700">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

### <a name="teams"></a><span data-ttu-id="2e9d4-701">Teams</span><span class="sxs-lookup"><span data-stu-id="2e9d4-701">Teams</span></span>

- <span data-ttu-id="2e9d4-702">**增強 Teams 行事曆功能：** 以滑鼠右鍵按一下行事曆中的項目，以展開 RSVP 選項，開始與會議參與者交談，或在會議開始時快速加入會議。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-702">**Improvements to the Teams calendar:** Right-click an item in your calendar to pull up RSVP options, start a chat with meeting participants, or quickly join a meeting when it starts.</span></span> <span data-ttu-id="2e9d4-703">我們也改善了活動排程表單。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-703">We've also made improvements to the event scheduling form.</span></span>

- <span data-ttu-id="2e9d4-704">**抓到你了！：** 建立標籤並將人員指派至標籤，您就可以 @mention 群組、角色、部門等。小組擁有者可以自行嘗試。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-704">**Tag, you're it!:** Create tags and assign people to them so you can @mention a group, role, department, etc. Team owners, try it out for yourselves.</span></span> <span data-ttu-id="2e9d4-705">移至某個小組，選取 [其他選項]、[管理標籤]。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-705">Go to a team, select More options, Manage tags.</span></span>

### <a name="word"></a><span data-ttu-id="2e9d4-706">Word</span><span class="sxs-lookup"><span data-stu-id="2e9d4-706">Word</span></span>

- <span data-ttu-id="2e9d4-707">**讓您的工具方便使用：** 在您的繪圖工具箱中，尋找智慧筆，以便在文字中加入筆跡筆勢。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-707">**Keep your tools handy:** In your drawing toolbox, find the intelligent pen that allows you to add ink gestures to text.</span></span> [<span data-ttu-id="2e9d4-708">深入了解</span><span class="sxs-lookup"><span data-stu-id="2e9d4-708">Learn more</span></span>](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

- <span data-ttu-id="2e9d4-709">**讓文件更生動的新影像：** 您可以在文件中使用的數千個免版稅圖庫影像、圖示和貼紙。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-709">**New images to bring your documents to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your documents.</span></span> <span data-ttu-id="2e9d4-710">移至 [插入] > [圖片] > [圖庫影像] 以開始使用。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-710">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="2e9d4-711">深入了解</span><span class="sxs-lookup"><span data-stu-id="2e9d4-711">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e9d4-714">解決的問題</span><span class="sxs-lookup"><span data-stu-id="2e9d4-714">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2e9d4-715">Excel</span><span class="sxs-lookup"><span data-stu-id="2e9d4-715">Excel</span></span>

- <span data-ttu-id="2e9d4-716">在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-716">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="2e9d4-717">已修正在複製含有樞紐分析表的工作表後，會於某些情況下導致 Excel 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-717">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="2e9d4-718">在某些情況下，Application.Evaluate (VBA) 無法在使用者定義的函數中運作。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-718">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="2e9d4-719">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e9d4-719">Outlook</span></span>

- <span data-ttu-id="2e9d4-720">已解決導致資料夾窗格寬度意外變更的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-720">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>


- <span data-ttu-id="2e9d4-721">已解決導致 Outlook 在某些 Windows 組建上當機的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-721">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>


- <span data-ttu-id="2e9d4-722">已解決在 Windows 更新後，開啟儲存在本機的 msg 或 .oft 檔案會導致 Outlook 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-722">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>


- <span data-ttu-id="2e9d4-723">已解決導致 Outlook 在某些 Windows 組建上當機的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-723">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>


- <span data-ttu-id="2e9d4-724">已解決導致使用者在退出 Outlook 時遇到掛斷的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-724">Addressed an issue that caused users to experience a hang while exiting Outlook.</span></span>


### <a name="project"></a><span data-ttu-id="2e9d4-725">Project</span><span class="sxs-lookup"><span data-stu-id="2e9d4-725">Project</span></span>

- <span data-ttu-id="2e9d4-726">在表單檢視中編輯前置/後續任務資料時，會觸發額外的 ProjectBeforeTaskChange 事件。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-726">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>


- <span data-ttu-id="2e9d4-727">已修正如果您使用的是連線至 Project Web App 的 Project，且小數分隔符號是逗號，當您嘗試將延遲新增至相依性時，TaskDependencies Add 方法會失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-727">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2e9d4-728">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2e9d4-728">Office Suite</span></span>

- <span data-ttu-id="2e9d4-729">已解決同時防止限制存取和保護設有密碼之檔案的錯誤。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-729">Resolved an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-april-15"></a><span data-ttu-id="2e9d4-731">版本 2003：4 月 15 日</span><span class="sxs-lookup"><span data-stu-id="2e9d4-731">Version 2003: April 15</span></span>
<span data-ttu-id="2e9d4-732">*版本 2003 (組建 12624.20466)*</span><span class="sxs-lookup"><span data-stu-id="2e9d4-732">*Version 2003 (Build 12624.20466)*</span></span>
* <span data-ttu-id="2e9d4-733">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-733">Various bugs and performance fixes.</span></span>

## <a name="version-2003-april-14"></a><span data-ttu-id="2e9d4-734">版本 2003：4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="2e9d4-734">Version 2003: April 14</span></span>
<span data-ttu-id="2e9d4-735">*版本 2003 (組建 12624.20442)*</span><span class="sxs-lookup"><span data-stu-id="2e9d4-735">*Version 2003 (Build 12624.20442)*</span></span>

<span data-ttu-id="2e9d4-736">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2e9d4-736">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e9d4-738">解決的問題</span><span class="sxs-lookup"><span data-stu-id="2e9d4-738">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2e9d4-739">Excel</span><span class="sxs-lookup"><span data-stu-id="2e9d4-739">Excel</span></span>

- <span data-ttu-id="2e9d4-740">在某些情況下，Application.Evaluate (VBA) 無法在使用者定義的函數中運作。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-740">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="2e9d4-741">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e9d4-741">Outlook</span></span>

- <span data-ttu-id="2e9d4-742">解決使用滑鼠上的「X」按鈕時，導致使用者偶爾發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-742">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

### <a name="project"></a><span data-ttu-id="2e9d4-743">Project</span><span class="sxs-lookup"><span data-stu-id="2e9d4-743">Project</span></span>

- <span data-ttu-id="2e9d4-744">在表單檢視中編輯前置/後續任務資料時，會觸發額外的 ProjectBeforeTaskChange 事件。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-744">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

### <a name="word"></a><span data-ttu-id="2e9d4-745">Word</span><span class="sxs-lookup"><span data-stu-id="2e9d4-745">Word</span></span>

- <span data-ttu-id="2e9d4-746">解決使用滑鼠上的「X」按鈕時，導致使用者偶爾發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-746">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-march-31"></a><span data-ttu-id="2e9d4-748">版本 2003：3 月 31 日</span><span class="sxs-lookup"><span data-stu-id="2e9d4-748">Version 2003: March 31</span></span>
<span data-ttu-id="2e9d4-749">*版本 2003 (組建 12624.20382)*</span><span class="sxs-lookup"><span data-stu-id="2e9d4-749">*Version 2003 (Build 12624.20382)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e9d4-751">解決的問題</span><span class="sxs-lookup"><span data-stu-id="2e9d4-751">Resolved issues</span></span>
### <a name="onenote"></a><span data-ttu-id="2e9d4-752">OneNote</span><span class="sxs-lookup"><span data-stu-id="2e9d4-752">OneNote</span></span>

- <span data-ttu-id="2e9d4-753">透過在資訊列中通知使用者有關 Microsoft OneNote 中的暫時調整之資訊，可協助改善在高全球使用狀況時的同步處理與服務可用性。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-753">Inform users through the InfoBar about temporary adjustments in Microsoft OneNote that will help improve sync and service availability during high worldwide usage.</span></span>

### <a name="project"></a><span data-ttu-id="2e9d4-754">Project</span><span class="sxs-lookup"><span data-stu-id="2e9d4-754">Project</span></span>

- <span data-ttu-id="2e9d4-755">修正了當開啟保護實際工作的設定時，使用者無法輸入分時期基準工時的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-755">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-march-25"></a><span data-ttu-id="2e9d4-757">版本 2003：3 月 25 日</span><span class="sxs-lookup"><span data-stu-id="2e9d4-757">Version 2003: March 25</span></span>
<span data-ttu-id="2e9d4-758">*版本 2003 (組建 12624.20320)*</span><span class="sxs-lookup"><span data-stu-id="2e9d4-758">*Version 2003 (Build 12624.20320)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="2e9d4-760">功能更新</span><span class="sxs-lookup"><span data-stu-id="2e9d4-760">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2e9d4-761">Excel</span><span class="sxs-lookup"><span data-stu-id="2e9d4-761">Excel</span></span>

- <span data-ttu-id="2e9d4-762">**您最愛的 Excel 函數計算速度提升了：** SUMIFS、AVERAGEIFS、COUNTIFS、MAXIFS 和 MINIFS 函數現在比以往更快了。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-762">**Your favorite Excel functions just got faster:** The SUMIFS, AVERAGEIFS, COUNTIFS, MAXIFS, and MINIFS functions are much faster than ever before.</span></span> <span data-ttu-id="2e9d4-763">更快速地前往底線。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-763">Get to the bottom line more quickly.</span></span> <span data-ttu-id="2e9d4-764">立即試用。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-764">Try one now.</span></span>

### <a name="outlook"></a><span data-ttu-id="2e9d4-765">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e9d4-765">Outlook</span></span>

- <span data-ttu-id="2e9d4-766">**將電子郵件拖曳到您擁有的群組：** 從您的 [收件匣] 拖曳郵件和交談以將它們移動和複製。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-766">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="2e9d4-767">您拖曳的郵件將會與所有群組成員共用。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-767">Messages you drag will be shared with all group members.</span></span>

- <span data-ttu-id="2e9d4-768">**受限 WiFi 網路的新體驗：** 是否曾經加入需要登入網頁的 WiFi 網路呢？</span><span class="sxs-lookup"><span data-stu-id="2e9d4-768">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="2e9d4-769">Outlook 現在會偵測這項要求並協助您取得連結。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-769">Outlook now detects this and helps you get connected.</span></span>

###<a name="powerpoint"></a><span data-ttu-id="2e9d4-770">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2e9d4-770">PowerPoint</span></span>

- <span data-ttu-id="2e9d4-771">**註解：** PowerPoint 中新增的註解體驗可讓您快速輕鬆地探索文件並新增註解。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-771">**Comments:** The new commenting experience in PowerPoint allows you to quickly and easily discover and add comments to your documents.</span></span> <span data-ttu-id="2e9d4-772">使用註解錨定、解決、工作、已改進的提及通知等新功能，現代化您的共同作業工作流程。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-772">Modernize your collaboration workflows with new features like comment anchoring, resolve, tasks, improved mention notifications, and much more.</span></span>

### <a name="word"></a><span data-ttu-id="2e9d4-773">Word</span><span class="sxs-lookup"><span data-stu-id="2e9d4-773">Word</span></span>

- <span data-ttu-id="2e9d4-774">**其他人更快速看到您的變更：** 共同撰寫增強功能表示，共同作業者可較以往更快速看到您的變更。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-774">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2e9d4-775">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2e9d4-775">Office Suite</span></span>

- <span data-ttu-id="2e9d4-776">**敏感度標籤** ：您現在可以套用組織設定、用來提示您輸入自訂權限的敏感度標籤。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-776">**Sensitivity labels:** You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e9d4-779">解決的問題</span><span class="sxs-lookup"><span data-stu-id="2e9d4-779">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2e9d4-780">Excel</span><span class="sxs-lookup"><span data-stu-id="2e9d4-780">Excel</span></span>

- <span data-ttu-id="2e9d4-781">重複開啟內嵌在 Word 或 PowerPoint 中的活頁簿時，在某些情況下，Excel 會當機。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-781">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="2e9d4-782">解決當來源活頁簿關閉時，外部連結無法在填入時更新的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-782">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

- <span data-ttu-id="2e9d4-783">解決從範本建立圖表時的效能問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-783">Addressed a performance issue when creating charts from templates.</span></span>

### <a name="onenote"></a><span data-ttu-id="2e9d4-784">OneNote</span><span class="sxs-lookup"><span data-stu-id="2e9d4-784">OneNote</span></span>

- <span data-ttu-id="2e9d4-785">透過暫時減少新嵌入附件的最大允許尺寸至 50MB，來改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-785">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB.</span></span> <span data-ttu-id="2e9d4-786">對於超過此限制的檔案，使用者可以選擇將檔案上傳到 OneDrive，並將連結插入 OneNote。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-786">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="2e9d4-787">透過暫時調整 OneNote 2016 中的同步處理頻率，來改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-787">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

### <a name="outlook"></a><span data-ttu-id="2e9d4-788">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e9d4-788">Outlook</span></span>

- <span data-ttu-id="2e9d4-789">已解決導致使用者在工作管理員中看到 Outlook 處理序延遲的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-789">Addressed an issue that caused users to see the Outlook process lingering in task manager after exiting.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2e9d4-790">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2e9d4-790">PowerPoint</span></span>

- <span data-ttu-id="2e9d4-791">已改善複製貼上的案例：將 PowerPoint 投影片中的圖形複製並貼到迴圈中的其他投影片，可能會出現例外狀況而失敗。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-791">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


### <a name="project"></a><span data-ttu-id="2e9d4-792">Project</span><span class="sxs-lookup"><span data-stu-id="2e9d4-792">Project</span></span>

- <span data-ttu-id="2e9d4-793">修正透過 [已停用] 按鈕停用/啟動工作時，ProjectBeforeTaskChange 事件無法偵測的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-793">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="2e9d4-794">修正儲存使用舊版 Project 建立的專案時，Project 可能當機的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-794">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="2e9d4-795">修正在將任務標示為完成之後，不正確地將任務完成百分比變更為低於 100% 的值的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-795">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="2e9d4-796">修正無法正確計算摘要任務日期的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-796">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-march-10"></a><span data-ttu-id="2e9d4-798">版本 2002：3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="2e9d4-798">Version 2002: March 10</span></span>
<span data-ttu-id="2e9d4-799">*版本 2002 (組建 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="2e9d4-799">*Version 2002 (Build 12527.20278)*</span></span>

<span data-ttu-id="2e9d4-800">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2e9d4-800">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="2e9d4-802">功能更新</span><span class="sxs-lookup"><span data-stu-id="2e9d4-802">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="2e9d4-803">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2e9d4-803">PowerPoint</span></span>

- <span data-ttu-id="2e9d4-804">**投影片連結:** 要求同事參與製作您的投影片組，讓他們直接在您需要協助的投影片上開始進行。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-804">**Link to a slide:** Ask a colleague to contribute to your slide deck, and start them directly on the slide you need help with.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e9d4-807">解決的問題</span><span class="sxs-lookup"><span data-stu-id="2e9d4-807">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="2e9d4-808">Project</span><span class="sxs-lookup"><span data-stu-id="2e9d4-808">Project</span></span>

- <span data-ttu-id="2e9d4-809">修正不先執行 OpenUndoTransaction 方法就不能觸發 OnUndoOrRedo 事件的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-809">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-march-01"></a><span data-ttu-id="2e9d4-811">版本 2002：3 月 1 日</span><span class="sxs-lookup"><span data-stu-id="2e9d4-811">Version 2002: March 01</span></span>
<span data-ttu-id="2e9d4-812">*版本 2002 (組建 12527.20242)*</span><span class="sxs-lookup"><span data-stu-id="2e9d4-812">*Version 2002 (Build 12527.20242)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e9d4-814">解決的問題</span><span class="sxs-lookup"><span data-stu-id="2e9d4-814">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2e9d4-815">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e9d4-815">Outlook</span></span>

- <span data-ttu-id="2e9d4-816">解決導致協力廠商應用程式無法傳送電子郵件的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-816">Addresses an issue that caused third party applications to be unable to send email.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-february-25"></a><span data-ttu-id="2e9d4-818">版本 2002：2 月 25 日</span><span class="sxs-lookup"><span data-stu-id="2e9d4-818">Version 2002: February 25</span></span>
<span data-ttu-id="2e9d4-819">*版本 2002 (組建 12527.20194)*</span><span class="sxs-lookup"><span data-stu-id="2e9d4-819">*Version 2002 (Build 12527.20194)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="2e9d4-821">功能更新</span><span class="sxs-lookup"><span data-stu-id="2e9d4-821">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2e9d4-822">Excel</span><span class="sxs-lookup"><span data-stu-id="2e9d4-822">Excel</span></span>

- <span data-ttu-id="2e9d4-823">**活頁簿統計資料：** 我們會計算儲存格、公式、圖表、表格，這樣您就不需要計算。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-823">**Workbook Statistics:** Cells, formulas, charts, tables... We count them so you don't have to.</span></span>

- <span data-ttu-id="2e9d4-824">**查詢編輯器中的資料分析：** 取得欄位資料的總覽分析、識別錯誤和空白值，查看分佈長條圖等。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-824">**Data Profiling in Query Editor:** Get at-a-glance analysis of the data in your columns, identify error and empty values, see distribution histograms and more.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e9d4-827">解決的問題</span><span class="sxs-lookup"><span data-stu-id="2e9d4-827">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2e9d4-828">Excel</span><span class="sxs-lookup"><span data-stu-id="2e9d4-828">Excel</span></span>

- <span data-ttu-id="2e9d4-829">修正 CUBEVALUE 函數有時會傳回不正確結果的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-829">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

### <a name="outlook"></a><span data-ttu-id="2e9d4-830">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e9d4-830">Outlook</span></span>

- <span data-ttu-id="2e9d4-831">解決導致會議的位置欄位中的逗號變成分號的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-831">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="2e9d4-832">解決在多個視窗中檢視相同項目時可能會導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-832">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="2e9d4-833">已解決導致在某些情況下無法使用相關選項來停用標幟項目醒目提示的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-833">Addresses an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="2e9d4-834">解決即使將同步處理滑桿設定為較小的設定，也會導致 Outlook 非預期地同步處理所有郵件的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-834">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>


- <span data-ttu-id="2e9d4-835">解決會導致使用黑色佈景主題的使用者，看到 [寄件者] 下拉式功能表在白色背景上顯示白色文字的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-835">Addresses an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>


- <span data-ttu-id="2e9d4-836">此變更會還原在郵件標頭中檢視多行主旨的功能。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-836">This change restores the ability to view multi-line subjects in the message header.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2001-february-19"></a><span data-ttu-id="2e9d4-838">版本 2001：2 月 19 日</span><span class="sxs-lookup"><span data-stu-id="2e9d4-838">Version 2001: February 19</span></span>
<span data-ttu-id="2e9d4-839">*版本 2001 (組建 12430.20288)*</span><span class="sxs-lookup"><span data-stu-id="2e9d4-839">*Version 2001 (Build 12430.20288)*</span></span>
* <span data-ttu-id="2e9d4-840">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-840">Various bugs and performance fixes.</span></span>

## <a name="version-2001-february-11"></a><span data-ttu-id="2e9d4-841">版本 2001：2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="2e9d4-841">Version 2001: February 11</span></span>
<span data-ttu-id="2e9d4-842">*版本 2001 (組建 12430.20264)*</span><span class="sxs-lookup"><span data-stu-id="2e9d4-842">*Version 2001 (Build 12430.20264)*</span></span>

<span data-ttu-id="2e9d4-843">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2e9d4-843">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e9d4-845">解決的問題</span><span class="sxs-lookup"><span data-stu-id="2e9d4-845">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2e9d4-846">Access</span><span class="sxs-lookup"><span data-stu-id="2e9d4-846">Access</span></span>

- <span data-ttu-id="2e9d4-847">Access 範本應不再導致資料庫中的附件欄出現故障。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-847">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="2e9d4-848">個體化範本後，您現在應該可以將附件欄新增至資料庫。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-848">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

### <a name="excel"></a><span data-ttu-id="2e9d4-849">Excel</span><span class="sxs-lookup"><span data-stu-id="2e9d4-849">Excel</span></span>

- <span data-ttu-id="2e9d4-850">已修正未顯示操作功能表中的註解命令的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-850">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="2e9d4-851">已修正以下問題：將文字轉換成具有溢出陣列之儲存格的欄時，某些使用者發生當機。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-851">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>


### <a name="outlook"></a><span data-ttu-id="2e9d4-852">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e9d4-852">Outlook</span></span>

- <span data-ttu-id="2e9d4-853">解決導致使用者在指定無效寄件者地址時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-853">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>


- <span data-ttu-id="2e9d4-854">解決導致使用者在取消帳戶設定時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-854">Addresses an issue that caused users to experience a crash when canceling account setup.</span></span>


### <a name="project"></a><span data-ttu-id="2e9d4-855">Project</span><span class="sxs-lookup"><span data-stu-id="2e9d4-855">Project</span></span>

- <span data-ttu-id="2e9d4-856">已修正以下問題：固定工期類型的 100% 工作可能會誤將其完成百分比計算為小於 100% 完成。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-856">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2e9d4-857">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2e9d4-857">Office Suite</span></span>

- <span data-ttu-id="2e9d4-858">此變更解決使用 Intel Integrated GPU 的圖形配接卡報告問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-858">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2001-january-30"></a><span data-ttu-id="2e9d4-860">版本 2001：1 月 30 日</span><span class="sxs-lookup"><span data-stu-id="2e9d4-860">Version 2001: January 30</span></span>
<span data-ttu-id="2e9d4-861">*版本 2001 (組建 12430.20184)*</span><span class="sxs-lookup"><span data-stu-id="2e9d4-861">*Version 2001 (Build 12430.20184)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="2e9d4-863">功能更新</span><span class="sxs-lookup"><span data-stu-id="2e9d4-863">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2e9d4-864">Excel</span><span class="sxs-lookup"><span data-stu-id="2e9d4-864">Excel</span></span>

- <span data-ttu-id="2e9d4-865">**即時讀取與回覆：** 直接從電子郵件回覆註解和提及，而不需開啟活頁簿。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-865">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="2e9d4-866">**向左看，向右看... XLOOKUP 在這裡！：** 一列接著一列，在含有 XLOOKUP 的表格或範圍中尋找您需要的項目。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-866">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span> [<span data-ttu-id="2e9d4-867">深入了解</span><span class="sxs-lookup"><span data-stu-id="2e9d4-867">Learn more</span></span>](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)

### <a name="outlook"></a><span data-ttu-id="2e9d4-868">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e9d4-868">Outlook</span></span>

- <span data-ttu-id="2e9d4-869">**進階群組電子郵件設定：** 此功能可協助使用者自訂要在收件匣中接收/追蹤哪些電子郵件或活動。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-869">**Advanced group email settings:** This feature helps groups users to customize which emails or events to receive/follow in their inbox.</span></span>

- <span data-ttu-id="2e9d4-870">**群組命名原則：** 群組命名原則可讓 IT 系統管理員將組織中使用者所建立群組的名稱標準化及管理。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-870">**Groups Naming policy:** A group naming policy enables the IT admin to standardize and manage the names of groups created by users in the organization.</span></span> <span data-ttu-id="2e9d4-871">系統管理員可以要求在建立群組時，將特定首碼和尾碼新增至群組的名稱，而且可以封鎖使用特定字詞。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-871">The admin can require a specific prefix and suffix be added to the name for a group when it's created, and can block specific words from being used.</span></span> <span data-ttu-id="2e9d4-872">這有助於將群組名稱中使用不當字詞的情況最小化，以及 IT 管理其目錄中群組的表示方式。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-872">This helps minimize the use of inappropriate words in group names as well as IT manage the representation of groups in their directory.</span></span> <span data-ttu-id="2e9d4-873">命名原則也可協助部署小組網站的組織根據部門來分類。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-873">Naming Policy also helps organizations that deploy team sites to categorize them based on department.</span></span>

### <a name="word"></a><span data-ttu-id="2e9d4-874">Word</span><span class="sxs-lookup"><span data-stu-id="2e9d4-874">Word</span></span>

- <span data-ttu-id="2e9d4-875">**更安全的影片體驗：** 安全性增強功能可讓您擁有更安全的線上影片體驗。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-875">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="2e9d4-876">深入了解</span><span class="sxs-lookup"><span data-stu-id="2e9d4-876">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- <span data-ttu-id="2e9d4-877">**對筆跡使用套索：** [繪圖] 索引標籤上的 [套索] 工具，可協助您選取使用筆跡繪製的物件。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-877">**Lasso your ink:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="2e9d4-878">選取個別筆劃或整個字。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-878">Select individual strokes, or whole words.</span></span> [<span data-ttu-id="2e9d4-879">深入了解</span><span class="sxs-lookup"><span data-stu-id="2e9d4-879">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)






[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e9d4-882">解決的問題</span><span class="sxs-lookup"><span data-stu-id="2e9d4-882">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2e9d4-883">Access</span><span class="sxs-lookup"><span data-stu-id="2e9d4-883">Access</span></span>

- <span data-ttu-id="2e9d4-884">此更新會修正使用 ADODB 的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-884">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="2e9d4-885">VB 程式碼中的記錄器物件可能會不正確地報告錯誤。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-885">Recorder object in VB code may incorrectly report an error.</span></span>


- <span data-ttu-id="2e9d4-886">此更新修正可能會導致 Microsoft Access 無法識別連結的 SQL Server 資料表中的識別資料行的問題，這可能會導致不正確地將資料列報告為已刪除。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-886">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>


### <a name="excel"></a><span data-ttu-id="2e9d4-887">Excel</span><span class="sxs-lookup"><span data-stu-id="2e9d4-887">Excel</span></span>

- <span data-ttu-id="2e9d4-888">解決重新命名簽名時，使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-888">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>


### <a name="outlook"></a><span data-ttu-id="2e9d4-889">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e9d4-889">Outlook</span></span>

- <span data-ttu-id="2e9d4-890">解決重新命名簽名時，使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-890">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1912-january-22"></a><span data-ttu-id="2e9d4-892">版本 1912：1 月 22 日</span><span class="sxs-lookup"><span data-stu-id="2e9d4-892">Version 1912: January 22</span></span>
<span data-ttu-id="2e9d4-893">*版本 1912 (組建 12325.20344)*</span><span class="sxs-lookup"><span data-stu-id="2e9d4-893">*Version 1912 (Build 12325.20344)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e9d4-895">解決的問題</span><span class="sxs-lookup"><span data-stu-id="2e9d4-895">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2e9d4-896">Access</span><span class="sxs-lookup"><span data-stu-id="2e9d4-896">Access</span></span>

- <span data-ttu-id="2e9d4-897">此更新修正可能會導致 Microsoft Access 無法識別連結的 SQL Server 資料表中的識別資料行的問題，這可能會導致不正確地將資料列報告為已刪除。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-897">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1912-january-14"></a><span data-ttu-id="2e9d4-899">版本 1912：1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="2e9d4-899">Version 1912: January 14</span></span>
<span data-ttu-id="2e9d4-900">*版本 1912 (組建 12325.20298)*</span><span class="sxs-lookup"><span data-stu-id="2e9d4-900">*Version 1912 (Build 12325.20298)*</span></span>

<span data-ttu-id="2e9d4-901">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2e9d4-901">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1912-january-08"></a><span data-ttu-id="2e9d4-902">版本 1912：1 月 8 日</span><span class="sxs-lookup"><span data-stu-id="2e9d4-902">Version 1912: January 08</span></span>
<span data-ttu-id="2e9d4-903">*版本 1912 (組建 12325.20288)*</span><span class="sxs-lookup"><span data-stu-id="2e9d4-903">*Version 1912 (Build 12325.20288)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="2e9d4-905">功能更新</span><span class="sxs-lookup"><span data-stu-id="2e9d4-905">Feature updates</span></span>

### <a name="outlook"></a><span data-ttu-id="2e9d4-906">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e9d4-906">Outlook</span></span>

- <span data-ttu-id="2e9d4-907">**傳送可存取的郵件給最需要它的人員：** Outlook 會顯示郵件提示，協助確保將您的內容傳送給偏好可存取內容的使用者時可供其存取</span><span class="sxs-lookup"><span data-stu-id="2e9d4-907">**Send accessible mail to those who need it most:** Outlook will display a mail tip to help you ensure that your content is accessible when sending to a user who prefers accessible content</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2e9d4-908">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2e9d4-908">PowerPoint</span></span>

- <span data-ttu-id="2e9d4-909">**最佳化您的簡報：** 協助工具檢查程式可協助您以螢幕閱讀器為中心，在投影片上排列物件。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-909">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

- <span data-ttu-id="2e9d4-910">**jiffy 中的 Gif：** 一個投影片、一個圖文框。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-910">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="2e9d4-911">在 PowerPoint 中輕鬆建立迴圈 Gif。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-911">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="2e9d4-912">深入了解</span><span class="sxs-lookup"><span data-stu-id="2e9d4-912">Learn more</span></span>](https://support.office.com/en-us/article/a598753e-92de-4f1b-8393-714db4d334b4)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e9d4-915">解決的問題</span><span class="sxs-lookup"><span data-stu-id="2e9d4-915">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2e9d4-916">Excel</span><span class="sxs-lookup"><span data-stu-id="2e9d4-916">Excel</span></span>

- <span data-ttu-id="2e9d4-917">這項變更透過利用軟體轉譯避免特定 Intel 圖形驅動程式發生問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-917">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

### <a name="outlook"></a><span data-ttu-id="2e9d4-918">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e9d4-918">Outlook</span></span>

- <span data-ttu-id="2e9d4-919">解決了導致會議位置在清除之後，又會不預期地重新加回會議的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-919">Addressed an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="2e9d4-920">解決當使用者透過鍵盤快速鍵與信箱資料夾互動時會造成明顯延遲的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-920">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="2e9d4-921">解決在某些情況下，導致使用者看到電子郵件傳送到與顯示的 SMTP 位址不相符之地址的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-921">Addressed an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="2e9d4-922">解決在擷取雲端設定時，導致使用者在 Outlook 中遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-922">Addressed an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

### <a name="word"></a><span data-ttu-id="2e9d4-923">Word</span><span class="sxs-lookup"><span data-stu-id="2e9d4-923">Word</span></span>

- <span data-ttu-id="2e9d4-924">建置組塊組合管理可能會顯示無效的通知：「您已經修改樣式、建置組塊」。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-924">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

### <a name="office-suite"></a><span data-ttu-id="2e9d4-925">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2e9d4-925">Office Suite</span></span>

- <span data-ttu-id="2e9d4-926">解決 Office 更新可能會非預期地從 Office CDN 而不是預期使用的來源 (例如本機或網路共用或 Configuration Manager 提供的位置) 下載檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-926">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

> [!NOTE]
> <span data-ttu-id="2e9d4-928">如果您需要關於使用 Office 的問題協助，建議您將問題張貼在 [Microsoft Answers 論壇](https://answers.microsoft.com/)或[技術社群](https://techcommunity.microsoft.com/)，或連絡[支援](https://support.microsoft.com/contactus)。</span><span class="sxs-lookup"><span data-stu-id="2e9d4-928">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>

[//]: # (DO NOT MODIFY ADMIN CENTER METADATA CONTENT START)
[//]: # (|Win32|CC|Production| |16.0.13328.20292|version-2010-october-27|)
[//]: # (|Win32|CC|Production| |16.0.13231.20418|version-2009-october-21|)
[//]: # (|Win32|CC|Production| |16.0.13231.20390|version-2009-october-13|)
[//]: # (|Win32|CC|Production| |16.0.13231.20368|version-2009-october-08|)
[//]: # (|Win32|CC|Production| |16.0.13231.20262|version-2009-september-28|)
[//]: # (|Win32|CC|Production| |16.0.13127.20508|version-2008-september-22|)
[//]: # (|Win32|CC|Production| |16.0.13127.20408|version-2008-september-09|)
[//]: # (|Win32|CC|Production| |16.0.13127.20296|version-2008-august-31|)
[//]: # (|Win32|CC|Production| |16.0.13029.20460|version-2007-august-25|)
[//]: # (|Win32 |CC|生產||16.0.13029.20344|版本-2007-11|)
[//]: # (DO NOT MODIFY ADMIN CENTER METADATA CONTENT END)
