---
title: 2020 年半年通道版本的版本資訊
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為 IT 專業人員提供 2020 年 Office 365 專業增強版半年通道版本的版本資訊
ms.openlocfilehash: 974a5db6f3bfba2bb20cd75f4e35a2777ea94ca8
ms.sourcegitcommit: 3598ca5e26109a1f99349ce3a4e70cb1d6f13e05
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 02/14/2020
ms.locfileid: "41978581"
---
# <a name="release-notes-for-semi-annual-channel-releases-in-2020"></a><span data-ttu-id="b09a7-103">2020 年半年通道版本的版本資訊</span><span class="sxs-lookup"><span data-stu-id="b09a7-103">Release notes for Semi-Annual Channel releases in 2020</span></span>

<span data-ttu-id="b09a7-104">這些版本資訊可提供 2020 年 Office 365 專業增強版、Visio Pro for Office 365、Project Online 電腦版用戶端以及 Office 365 商務版的半年通道更新所含新功能和非安全性更新的相關資訊。</span><span class="sxs-lookup"><span data-stu-id="b09a7-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Channel updates to Office 365 ProPlus in 2020, Visio Pro for Office 365, Project Online Desktop Client and Office 365 Business.</span></span>

> [!NOTE]
>
>- <span data-ttu-id="b09a7-105">我們通常會在一段時間內推出功能 (有時甚至推出修正程式) 至半年通道。</span><span class="sxs-lookup"><span data-stu-id="b09a7-105">We often roll out features (and sometimes even fixes) to Semi-Annual Channel over a period of time.</span></span> <span data-ttu-id="b09a7-106">如果您現在沒有看到如下所述的項目，您可以預期它近期會推出。</span><span class="sxs-lookup"><span data-stu-id="b09a7-106">If you don’t see something described below right away, you can expect it soon.</span></span> [<span data-ttu-id="b09a7-107">深入了解</span><span class="sxs-lookup"><span data-stu-id="b09a7-107">Learn more</span></span>](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516)
>- <span data-ttu-id="b09a7-108">當使用者在半年通道上，從 Office 入口網站下載並安裝 Office 365 到 Windows 10 上時，OneNote 2016 依預設不會包括在其中。</span><span class="sxs-lookup"><span data-stu-id="b09a7-108">OneNote 2016 will not be included by default when a user on the Semi-Annual Channel downloads and installs Office 365 on Windows 10 from the Office Portal.</span></span>


## <a name="version-1908-february-11"></a><span data-ttu-id="b09a7-109">版本 1908：2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="b09a7-109">Version 1908: February 11</span></span>
<span data-ttu-id="b09a7-110">*版本 1908 (組建 11929.20606)*</span><span class="sxs-lookup"><span data-stu-id="b09a7-110">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="b09a7-111">安全性更新列於[此處](https://docs.microsoft.com/zh-TW/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b09a7-111">Security updates listed [here](https://docs.microsoft.com/zh-TW/officeupdates/office365-proplus-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="b09a7-113">解決的問題</span><span class="sxs-lookup"><span data-stu-id="b09a7-113">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b09a7-114">Excel</span><span class="sxs-lookup"><span data-stu-id="b09a7-114">Excel</span></span>

- <span data-ttu-id="b09a7-115">此更新已修正使用 VBA 將影像新增到圖表的頁首/頁尾時發生錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-115">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="b09a7-116">已修正在預覽列印或列印時群組方塊控制項的框線無法顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-116">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="b09a7-117">使用者在使用某些非英文字元集的情況下，儲存變更時可能會遇到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-117">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="b09a7-118">已修正圖表標題中影像檔案大小在儲存包含圖表的活頁簿時增加的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-118">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="b09a7-119">已修正以下問題：將選取範圍與交互參照的活頁簿保持同步時，導致交互參照的活頁簿中的 DBCS 字元損毀。</span><span class="sxs-lookup"><span data-stu-id="b09a7-119">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="b09a7-120">已解決使用自動調整來調整列高時，核取方塊可能收縮的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-120">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="b09a7-121">Outlook</span><span class="sxs-lookup"><span data-stu-id="b09a7-121">Outlook</span></span>

- <span data-ttu-id="b09a7-122">已解決導致使用者在指定無效寄件者地址時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-122">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="b09a7-123">已解決導致使用者處理衝突郵件時同步失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-123">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="b09a7-124">已解決導致使用者在啟動 Outlook 時，「正在載入設定檔」畫面時停滯的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-124">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="b09a7-125">已解決導致使用者在變更檢視時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-125">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="b09a7-126">已解決在 Citrix 環境中檢視 30 個以上的行事曆時，導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-126">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="b09a7-127">[此處](https://support.microsoft.com/zh-TW/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)是記錄舊版問題的個別 KB。</span><span class="sxs-lookup"><span data-stu-id="b09a7-127">[Here](https://support.microsoft.com/zh-TW/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="b09a7-128">已解決以下問題：使用者將共用行事曆資料夾同步到 OST 時發生問題，這導致嘗試與這些資料夾互動時發生權限錯誤。</span><span class="sxs-lookup"><span data-stu-id="b09a7-128">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="b09a7-129">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b09a7-129">PowerPoint</span></span>

- <span data-ttu-id="b09a7-130">已改善複製貼上的案例，即將 PowerPoint 投影片中的圖形複製並貼到其他投影片可能會因為異常而失敗。</span><span class="sxs-lookup"><span data-stu-id="b09a7-130">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="b09a7-131">已修正導致共同作業使用者之間效能較低的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-131">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="b09a7-132">已修正以下問題：當檔案以漸進式開啟時，若其中一個投影片包含多個內嵌媒體串流可能會發生問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-132">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="b09a7-133">已修正以下問題：首次啟動 PowerPoint 時，不受信任的增益集可能不會顯示安全性警告訊息列。</span><span class="sxs-lookup"><span data-stu-id="b09a7-133">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="b09a7-134">Project</span><span class="sxs-lookup"><span data-stu-id="b09a7-134">Project</span></span>

- <span data-ttu-id="b09a7-135">已修正以下問題：由於基準行事曆變更時未更新資源行事曆，而導致時程表和專案計劃之間的實際工作可能不同。</span><span class="sxs-lookup"><span data-stu-id="b09a7-135">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="b09a7-136">Word</span><span class="sxs-lookup"><span data-stu-id="b09a7-136">Word</span></span>

- <span data-ttu-id="b09a7-137">已從遭取代的 API 移除，以修正 Word 的當機問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-137">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="b09a7-138">Office 套件</span><span class="sxs-lookup"><span data-stu-id="b09a7-138">Office Suite</span></span>

- <span data-ttu-id="b09a7-139">此變更解決開啟損毀的檔案時正確呈現影像的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-139">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-february-11"></a><span data-ttu-id="b09a7-141">版本 1902：2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="b09a7-141">Version 1902: February 11</span></span>
<span data-ttu-id="b09a7-142">*版本 1902 (組建 11328.20526)*</span><span class="sxs-lookup"><span data-stu-id="b09a7-142">*Version 1902 (Build 11328.20526)*</span></span>

<span data-ttu-id="b09a7-143">安全性更新列於[此處](https://docs.microsoft.com/zh-TW/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b09a7-143">Security updates listed [here](https://docs.microsoft.com/zh-TW/officeupdates/office365-proplus-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="b09a7-145">解決的問題</span><span class="sxs-lookup"><span data-stu-id="b09a7-145">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b09a7-146">Outlook</span><span class="sxs-lookup"><span data-stu-id="b09a7-146">Outlook</span></span>

- <span data-ttu-id="b09a7-147">解決導致使用者在傳送加密電子郵件時遇到「不支援加密演算法」錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-147">Addresses an issue that caused users to encounter encryption algorithm is not supported errors when sending an encrypted email.</span></span>


### <a name="word"></a><span data-ttu-id="b09a7-148">Word</span><span class="sxs-lookup"><span data-stu-id="b09a7-148">Word</span></span>

- <span data-ttu-id="b09a7-149">已從遭取代的 API 移除，以修正 Word 的當機問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-149">Fixed a crash in Word by moving away from a deprecated API.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

## <a name="version-1808-february-11"></a><span data-ttu-id="b09a7-152">版本 1808：2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="b09a7-152">Version 1808: February 11</span></span>
<span data-ttu-id="b09a7-153">*版本 1808 (組建 10730.20438)*</span><span class="sxs-lookup"><span data-stu-id="b09a7-153">*Version 1808 (Build 10730.20438)*</span></span>

<span data-ttu-id="b09a7-154">安全性更新列於[此處](https://docs.microsoft.com/zh-TW/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b09a7-154">Security updates listed [here](https://docs.microsoft.com/zh-TW/officeupdates/office365-proplus-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-january-14"></a><span data-ttu-id="b09a7-156">版本 1908：1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="b09a7-156">Version 1908: January 14</span></span>
<span data-ttu-id="b09a7-157">*版本 1908 (組建 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="b09a7-157">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="b09a7-158">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b09a7-158">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="b09a7-160">功能更新</span><span class="sxs-lookup"><span data-stu-id="b09a7-160">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="b09a7-161">Access</span><span class="sxs-lookup"><span data-stu-id="b09a7-161">Access</span></span>

- <span data-ttu-id="b09a7-162">**將索引標籤保留在資料庫物件上：** 能清楚看到使用中的索引標籤、輕鬆拖曳索引標籤來重新排列，只要按一下就能關閉資料庫物件。</span><span class="sxs-lookup"><span data-stu-id="b09a7-162">**Keep tabs on your database objects:** Clearly see the active tab, easily drag tabs to rearrange them, and close database objects with just one click.</span></span>

- <span data-ttu-id="b09a7-163">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="b09a7-163">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="b09a7-164">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="b09a7-164">Switching between them has never been easier.</span></span> [<span data-ttu-id="b09a7-165">深入了解</span><span class="sxs-lookup"><span data-stu-id="b09a7-165">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="b09a7-166">**使用更大的空間來縮放：** 加大 [縮放] 方塊、變更字型、記憶縮放。</span><span class="sxs-lookup"><span data-stu-id="b09a7-166">**Zoom with more room:** Make the Zoom box bigger, change the font, and Zoom remembers it all.</span></span> [<span data-ttu-id="b09a7-167">深入了解</span><span class="sxs-lookup"><span data-stu-id="b09a7-167">Learn more</span></span>](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

### <a name="excel"></a><span data-ttu-id="b09a7-168">Excel</span><span class="sxs-lookup"><span data-stu-id="b09a7-168">Excel</span></span>

- <span data-ttu-id="b09a7-169">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="b09a7-169">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="b09a7-170">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="b09a7-170">Switching between them has never been easier.</span></span> [<span data-ttu-id="b09a7-171">深入了解</span><span class="sxs-lookup"><span data-stu-id="b09a7-171">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="b09a7-172">**增加您內容的覆蓋面：** 想要讓您的簡報更易於使用嗎？</span><span class="sxs-lookup"><span data-stu-id="b09a7-172">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="b09a7-173">讓協助工具檢查程式來幫助您，您不需要自行處理。</span><span class="sxs-lookup"><span data-stu-id="b09a7-173">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="b09a7-174">按一下 [校閱] > [檢查協助工具] 試試看這個功能 – 我們會在狀態列上告訴您需要留意的部分。</span><span class="sxs-lookup"><span data-stu-id="b09a7-174">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="b09a7-175">**快速找到該檔案：** 想要尋找最近使用過的檔案嗎？</span><span class="sxs-lookup"><span data-stu-id="b09a7-175">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="b09a7-176">只要在 [檔案] > [常用] 頁面的 [搜尋] 方塊中輸入，就能找到所需的檔案。</span><span class="sxs-lookup"><span data-stu-id="b09a7-176">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="b09a7-177">**觀看工作表生動地呈現：** 插入動畫 3D 圖形，來查看心跳、行星軌道，以及暴龍在工作表內橫衝直撞。</span><span class="sxs-lookup"><span data-stu-id="b09a7-177">**Watch your worksheet come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage through the workbook.</span></span> [<span data-ttu-id="b09a7-178">深入了解</span><span class="sxs-lookup"><span data-stu-id="b09a7-178">Learn more</span></span>](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- <span data-ttu-id="b09a7-p109">**更深入地探索您的資料：** 新的 [構想] 按鈕可尋找資料的模式，並使用模式建立更有智慧且個人化的建議。[深入了解](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span><span class="sxs-lookup"><span data-stu-id="b09a7-p109">**Discover more about your data:** The new Ideas button looks for patterns in your data, and uses them to create intelligent, personalized suggestions. [Learn more](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span></span>

- <span data-ttu-id="b09a7-181">**共同作業變得更容易：** 共同撰寫的增強功能代表的是使用條件式格式設定、儲存格樣式等等時，您的變更會與共同作業者的變更順暢地合併。</span><span class="sxs-lookup"><span data-stu-id="b09a7-181">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>

- <span data-ttu-id="b09a7-182">**聯結類似欄位上的表格：** 在比較合併表格的欄位時，取得及轉換 (Power Query) 現在具有近似文字比對邏輯 (也稱為模糊比對)。</span><span class="sxs-lookup"><span data-stu-id="b09a7-182">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span> [<span data-ttu-id="b09a7-183">深入了解</span><span class="sxs-lookup"><span data-stu-id="b09a7-183">Learn more</span></span>](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- <span data-ttu-id="b09a7-184">**使用 Power Query 的增強功能快速撰寫程式碼：** 使用自動完成和語法色彩快速完成程式碼。</span><span class="sxs-lookup"><span data-stu-id="b09a7-184">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="b09a7-185">同時輕鬆探索函數、資料行和參數。</span><span class="sxs-lookup"><span data-stu-id="b09a7-185">Easily discover functions, columns, and parameters, too.</span></span>

### <a name="outlook"></a><span data-ttu-id="b09a7-186">Outlook</span><span class="sxs-lookup"><span data-stu-id="b09a7-186">Outlook</span></span>

- <span data-ttu-id="b09a7-187">**我們已為您更新 Outlook 使用者體驗：** 先前利用「即將推出」提供預覽的簡化體驗，專門設計來幫助您專注於最重要的事物上。</span><span class="sxs-lookup"><span data-stu-id="b09a7-187">**We’ve updated the Outlook user experience for you:** A simplified experience, previously available for preview with Coming Soon, designed to help you focus on what matters most.</span></span> [<span data-ttu-id="b09a7-188">深入了解</span><span class="sxs-lookup"><span data-stu-id="b09a7-188">Learn more</span></span>](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- <span data-ttu-id="b09a7-189">**簡化且也能自訂的功能區：** 輕鬆使用簡化、以單一列方式陳列的常用按鈕。</span><span class="sxs-lookup"><span data-stu-id="b09a7-189">**A simplified ribbon that's customizable, too:** Enjoy a streamlined, single row of the most frequently used buttons.</span></span> <span data-ttu-id="b09a7-190">輕鬆在傳統與 [簡化] 檢視之間切換，以及釘選/取消釘選命令。</span><span class="sxs-lookup"><span data-stu-id="b09a7-190">Easily switch between classic and Simplified views, and pin/unpin commands.</span></span> [<span data-ttu-id="b09a7-191">深入了解</span><span class="sxs-lookup"><span data-stu-id="b09a7-191">Learn more</span></span>](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- <span data-ttu-id="b09a7-192">**在移動郵件時繼續作業：** Outlook 現在會在背景中移動郵件，因此，在資料夾之間移動大量郵件時您可以繼續作業。</span><span class="sxs-lookup"><span data-stu-id="b09a7-192">**Keep working while moving messages:** Outlook now moves messages in the background, so you can keep working while moving lots of messages between folders.</span></span>

- <span data-ttu-id="b09a7-193">**在連續會議之間置入時間：** 將會議預設為提早 5-10 分鐘結束，讓出席者有時間休息，或在前往下一個地點。</span><span class="sxs-lookup"><span data-stu-id="b09a7-193">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to end 5-10 minutes early by default.</span></span>

- <span data-ttu-id="b09a7-194">**挑選您的最愛動作：** 不使用 [標幟] 和 [刪除] 嗎？</span><span class="sxs-lookup"><span data-stu-id="b09a7-194">**Pick your favorite action:** Don't use Flag and Delete?</span></span> <span data-ttu-id="b09a7-195">那麼 [封存] 或 [標示為已讀取] 呢？</span><span class="sxs-lookup"><span data-stu-id="b09a7-195">How about Archive or Mark as Read?</span></span> <span data-ttu-id="b09a7-196">自訂快速動作功能表，加上您最常使用的命令。</span><span class="sxs-lookup"><span data-stu-id="b09a7-196">Customize the quick action menu with the commands you use most.</span></span>

- <span data-ttu-id="b09a7-p115">**他們會看到您的 meme：** 如果使用文字或靜態影像還不足以清楚表達您的想法，您可以使用動畫 GIF。[深入了解](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span><span class="sxs-lookup"><span data-stu-id="b09a7-p115">**They'll see what you meme:** When text or static images just won't do, use an animated GIF to make your point. [Learn more](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span></span>

- <span data-ttu-id="b09a7-199">**想要寬鬆或緊密的版面配置？您可自由選擇：** 若您想讓項目之間能有更多空間，可以採用「緊密間距」；或者，您也可以採用緊密的版面配置，以便查看更多項目。</span><span class="sxs-lookup"><span data-stu-id="b09a7-199">**Relaxed or tighter layout? You choose:** Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

- <span data-ttu-id="b09a7-200">**更快速新增帳戶的方式：** 由於帳戶設定已改善，您現在可以更輕鬆地將使用雙因素驗證的 Outlook.com 和 Gmail 帳戶新增到 Outlook。</span><span class="sxs-lookup"><span data-stu-id="b09a7-200">**A quicker way to add accounts:** Thanks to account setup improvements, it's easier than ever to add Outlook.com and Gmail accounts that use 2-factor authentication to Outlook.</span></span> [<span data-ttu-id="b09a7-201">深入了解</span><span class="sxs-lookup"><span data-stu-id="b09a7-201">Learn more</span></span>](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- <span data-ttu-id="b09a7-202">**不再受限於同步處理限制：** Outlook 的增強功能指出資料夾限制已不存在，因此您可以開始將您的共用信箱同步處理。</span><span class="sxs-lookup"><span data-stu-id="b09a7-202">**Say goodbye to sync limits:** Outlook improvements mean the folder limit is gone so go ahead and synchronize your shared mailboxes.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b09a7-203">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b09a7-203">PowerPoint</span></span>

- <span data-ttu-id="b09a7-204">**較佳變形效果：** 命名您的圖形以便加強掌控其轉化方式。</span><span class="sxs-lookup"><span data-stu-id="b09a7-204">**Better shapeshifting:** Name your shapes for more control over how they morph.</span></span> [<span data-ttu-id="b09a7-205">深入了解</span><span class="sxs-lookup"><span data-stu-id="b09a7-205">Learn more</span></span>](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- <span data-ttu-id="b09a7-206">**快速找到該檔案：** 想要尋找最近使用過的檔案嗎？</span><span class="sxs-lookup"><span data-stu-id="b09a7-206">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="b09a7-207">只要在 [檔案] > [常用] 頁面的 [搜尋] 方塊中輸入，就能找到所需的檔案。</span><span class="sxs-lookup"><span data-stu-id="b09a7-207">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="b09a7-208">**增加您內容的覆蓋面：** 想要讓您的簡報更易於使用嗎？</span><span class="sxs-lookup"><span data-stu-id="b09a7-208">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="b09a7-209">讓協助工具檢查程式來幫助您，您不需要自行處理。</span><span class="sxs-lookup"><span data-stu-id="b09a7-209">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="b09a7-210">按一下 [校閱] > [檢查協助工具] 試試看這個功能 – 我們會在狀態列上告訴您需要留意的部分。</span><span class="sxs-lookup"><span data-stu-id="b09a7-210">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="b09a7-211">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="b09a7-211">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="b09a7-212">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="b09a7-212">Switching between them has never been easier.</span></span> [<span data-ttu-id="b09a7-213">深入了解</span><span class="sxs-lookup"><span data-stu-id="b09a7-213">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="b09a7-214">**線上影片有新的首頁：** 將影片儲存至 Microsoft Stream，讓組織中的任何人都看得到。</span><span class="sxs-lookup"><span data-stu-id="b09a7-214">**Online videos have a new home:** Save a video to Microsoft Stream so anyone in your organization can see it.</span></span> <span data-ttu-id="b09a7-215">插入影片連結，享受檔案大小只有原來一小部分的多媒體簡報。</span><span class="sxs-lookup"><span data-stu-id="b09a7-215">Insert the video link and enjoy a multimedia presentation at a fraction of the file size.</span></span> [<span data-ttu-id="b09a7-216">深入了解</span><span class="sxs-lookup"><span data-stu-id="b09a7-216">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="b09a7-217">**隨時儲存變更：** 將檔案上傳至 OneDrive，確保所有的更新都會自動儲存。</span><span class="sxs-lookup"><span data-stu-id="b09a7-217">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="b09a7-p122">**透過測驗或問卷詢問聽眾：** 在投影片上進行測驗或問卷。Office 會收集並儲存存儲您的回應。[深入了解](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span><span class="sxs-lookup"><span data-stu-id="b09a7-p122">**Ask your audience with a quiz or survey:** Put a quiz or survey on a slide. Office collects and stores the responses for you. [Learn more](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span></span>

- <span data-ttu-id="b09a7-p123">**輕鬆插入內嵌影片：** 想要在您的投影片中放入 Vimeo 或 YouTube 影片嗎？只要有影片頁面連結即可。[深入了解](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span><span class="sxs-lookup"><span data-stu-id="b09a7-p123">**Inserting an online video is easier than ever:** Want to put a video from Vimeo or YouTube on your slide? The video page link is all you need. [Learn more](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span></span>

### <a name="project"></a><span data-ttu-id="b09a7-224">Project</span><span class="sxs-lookup"><span data-stu-id="b09a7-224">Project</span></span>

- <span data-ttu-id="b09a7-225">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="b09a7-225">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="b09a7-226">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="b09a7-226">Switching between them has never been easier.</span></span> [<span data-ttu-id="b09a7-227">深入了解</span><span class="sxs-lookup"><span data-stu-id="b09a7-227">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a><span data-ttu-id="b09a7-228">Visio</span><span class="sxs-lookup"><span data-stu-id="b09a7-228">Visio</span></span>

- <span data-ttu-id="b09a7-229">**將進度圖表匯出到 Word：** 在 Word 文件中自動新增圖表內容，如圖案和中繼資料。</span><span class="sxs-lookup"><span data-stu-id="b09a7-229">**Export process diagrams to Word:** Automatically add diagram content, such as shapes and metadata, to a Word document.</span></span> <span data-ttu-id="b09a7-230">然後，自訂文件來建立程序指導方針和操作手冊。</span><span class="sxs-lookup"><span data-stu-id="b09a7-230">Then customize the document to create process guidelines and operation manuals.</span></span> [<span data-ttu-id="b09a7-231">深入了解</span><span class="sxs-lookup"><span data-stu-id="b09a7-231">Learn more</span></span>](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- <span data-ttu-id="b09a7-232">**資料流程圖上的 Double-Take：** 資料視覺化工具流程圖美觀的新版面配置，既清新、簡潔且更易於了解。</span><span class="sxs-lookup"><span data-stu-id="b09a7-232">**Double-take on data flowcharts:** Gorgeous new layouts for Data Visualizer flowcharts are clean, crisp, and easy to understand.</span></span> <span data-ttu-id="b09a7-233">按一下 [設計] 索引標籤來取得選項。</span><span class="sxs-lookup"><span data-stu-id="b09a7-233">Click the Design tab for options.</span></span>

- <span data-ttu-id="b09a7-234">**內建的 Azure 樣板：** 使用數十種 Azure 樣板來設計雲端應用程式或規劃架構。</span><span class="sxs-lookup"><span data-stu-id="b09a7-234">**Azure stencils built right in:** Design a cloud app or plan an architecture using dozens of Azure stencils.</span></span> [<span data-ttu-id="b09a7-235">深入了解</span><span class="sxs-lookup"><span data-stu-id="b09a7-235">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- <span data-ttu-id="b09a7-p128">**告別錯誤的 Excel 連結：** 找不到與 Data Visualizer 圖表連結的 Excel 活頁簿嗎？重新連結，就可繼續使用了。[深入了解](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span><span class="sxs-lookup"><span data-stu-id="b09a7-p128">**Say goodbye to broken Excel links:** Can't find the Excel workbook linked to your Data Visualizer diagram? Relink it, and you're back in business. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span></span>

- <span data-ttu-id="b09a7-239">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="b09a7-239">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="b09a7-240">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="b09a7-240">Switching between them has never been easier.</span></span> [<span data-ttu-id="b09a7-241">深入了解</span><span class="sxs-lookup"><span data-stu-id="b09a7-241">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="b09a7-242">**從 Power BI 匯出 Visio 視覺效果：** 當匯出 Power BI 報表為 PDF 或 PowerPoint 等檔案時，Power BI Visio 視覺效果會正常顯示。</span><span class="sxs-lookup"><span data-stu-id="b09a7-242">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span> [<span data-ttu-id="b09a7-243">深入了解</span><span class="sxs-lookup"><span data-stu-id="b09a7-243">Learn more</span></span>](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a><span data-ttu-id="b09a7-244">Word</span><span class="sxs-lookup"><span data-stu-id="b09a7-244">Word</span></span>

- <span data-ttu-id="b09a7-245">**[學習工具] 模式額外支援更多頁面色彩：** Word 中的 [學習工具] 新增更多頁面佈景主題色彩的支援，讓您能夠變更頁面的背景色彩。</span><span class="sxs-lookup"><span data-stu-id="b09a7-245">**Learning Tools mode has additional support for more page colors:** Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span> <span data-ttu-id="b09a7-246">許多人在背景全白或全黑時閱讀會有困難，因此我們在 PC 和 Mac 的 Word 中增加了色彩選項。</span><span class="sxs-lookup"><span data-stu-id="b09a7-246">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

- <span data-ttu-id="b09a7-p132">**編輯當然是使用筆跡編輯：** 使用畫筆透過單一筆劃來分割或加入文字、新增新的一行，或插入文字。[深入了解](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span><span class="sxs-lookup"><span data-stu-id="b09a7-p132">**Editing comes naturally with Ink Editor:** With a single stroke, split or join words, add a new line, or insert words using your pen. [Learn more](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span></span>

- <span data-ttu-id="b09a7-p133">**為靜態文件注入動人的生命力：** 將文件轉變為在任何裝置上，均具有完美外觀的可互動、易分享的網頁。[深入了解](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span><span class="sxs-lookup"><span data-stu-id="b09a7-p133">**Take your doc from static to stunning:** Transform your document into an interactive, easy-to-share web page that looks great on any device. [Learn more](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span></span>

- <span data-ttu-id="b09a7-251">**增加您內容的覆蓋面：** 想要讓您的文件更易於使用嗎？</span><span class="sxs-lookup"><span data-stu-id="b09a7-251">**Increase the reach of your content:** Need to make your documents accessible?</span></span> <span data-ttu-id="b09a7-252">讓協助工具檢查程式來幫助您，您不需要自行處理。</span><span class="sxs-lookup"><span data-stu-id="b09a7-252">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="b09a7-253">按一下 [校閱] > [檢查協助工具] 試試看這個功能 – 我們會在狀態列上告訴您需要留意的部分。</span><span class="sxs-lookup"><span data-stu-id="b09a7-253">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="b09a7-254">**快速找到該檔案：** 想要尋找最近使用過的檔案嗎？</span><span class="sxs-lookup"><span data-stu-id="b09a7-254">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="b09a7-255">只要在 [檔案] > [常用] 頁面的 [搜尋] 方塊中輸入，就能找到所需的檔案。</span><span class="sxs-lookup"><span data-stu-id="b09a7-255">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="b09a7-256">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="b09a7-256">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="b09a7-257">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="b09a7-257">Switching between them has never been easier.</span></span> [<span data-ttu-id="b09a7-258">深入了解</span><span class="sxs-lookup"><span data-stu-id="b09a7-258">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="b09a7-259">**跟分心說再見：** Mac 中最受歡迎的功能來到 Windows。</span><span class="sxs-lookup"><span data-stu-id="b09a7-259">**Say goodbye to distractions:** A favorite Mac feature comes to Windows.</span></span> <span data-ttu-id="b09a7-260">切換到 [檢視] 功能表中的 [焦點] 以移除令人分心的事物，讓您更能專注於工作。</span><span class="sxs-lookup"><span data-stu-id="b09a7-260">Switch to Focus on the View menu to remove distractions and concentrate on your work.</span></span> [<span data-ttu-id="b09a7-261">深入了解</span><span class="sxs-lookup"><span data-stu-id="b09a7-261">Learn more</span></span>](https://support.office.com/article/51af2fb2-194f-424b-ab7e-b65de9ec9292)

- <span data-ttu-id="b09a7-p138">**運用行聚焦，提高理解力：** 毫不費力地逐行瀏覽文件。調整焦點，在檢視畫面中一次放入一行、三行或五行。[深入了解](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="b09a7-p138">**Improve comprehension with Line Focus:** Move through a document line by line without distractions. Adjust the focus to put one, three, or five lines in view at a time. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>

- <span data-ttu-id="b09a7-265">**隨時儲存變更：** 將檔案上傳至 OneDrive，確保所有的更新都會自動儲存。</span><span class="sxs-lookup"><span data-stu-id="b09a7-265">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="b09a7-266">**使用 \@Mentions 提及功能取得他人注意：** 在註解中使用 @mentions 提及功能，讓同事知道您需要他們提供建議。</span><span class="sxs-lookup"><span data-stu-id="b09a7-266">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="b09a7-267">深入了解</span><span class="sxs-lookup"><span data-stu-id="b09a7-267">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

### <a name="office-suite"></a><span data-ttu-id="b09a7-268">Office 套件</span><span class="sxs-lookup"><span data-stu-id="b09a7-268">Office Suite</span></span>

- <span data-ttu-id="b09a7-269">**快速找到該檔案：** 想要尋找最近使用過的檔案嗎？</span><span class="sxs-lookup"><span data-stu-id="b09a7-269">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="b09a7-270">只要在 [檔案] > [開啟] 索引標籤的 [搜尋] 方塊中輸入，就能找到所需的檔案。</span><span class="sxs-lookup"><span data-stu-id="b09a7-270">Just type in the Search box on the File > Open tab to find the file you're looking for.</span></span>

- <span data-ttu-id="b09a7-271">**隨時儲存變更：** 將檔案上傳至 OneDrive，確保所有的更新都會自動儲存。</span><span class="sxs-lookup"><span data-stu-id="b09a7-271">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="b09a7-272">**隱私權控制：** 用於診斷資料和連線體驗的新增、更新及改良的控制項。</span><span class="sxs-lookup"><span data-stu-id="b09a7-272">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> [<span data-ttu-id="b09a7-273">深入了解</span><span class="sxs-lookup"><span data-stu-id="b09a7-273">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

- <span data-ttu-id="b09a7-274">**Office 圖示有新的外觀：** Office 圖示經過重新設計，以反映簡單、功能強大且智慧型的 Office 體驗。</span><span class="sxs-lookup"><span data-stu-id="b09a7-274">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

- <span data-ttu-id="b09a7-275">**安裝 Microsoft Teams：** 在 Office 365 專業增強版的現有安裝中，預設會安裝 Microsoft Teams。</span><span class="sxs-lookup"><span data-stu-id="b09a7-275">**Installation of Microsoft Teams:** Microsoft Teams is installed by default for existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="b09a7-276">深入了解</span><span class="sxs-lookup"><span data-stu-id="b09a7-276">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/teams-install)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="b09a7-279">解決的問題</span><span class="sxs-lookup"><span data-stu-id="b09a7-279">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="b09a7-280">Access</span><span class="sxs-lookup"><span data-stu-id="b09a7-280">Access</span></span>

- <span data-ttu-id="b09a7-281">此更新修正彙總 (例如 Sum) 可能會將結果截斷成整數值的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-281">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="b09a7-282">此更新修正包含參照遠端桌面 (例如 SQL Server 桌面) 的聯集查詢可能造成 Access 關閉並重新啟動的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-282">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="b09a7-283">此更新可修正 Microsoft Access 中的「更新查詢」執行時或在 SQL 中使用 UPDATE 陳述式時，可能導致發生錯誤「查詢已損壞」&quot;&quot;的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-283">This update fixes an issue in Microsoft Access that may cause the error &quot;Query is Corrupt&quot; when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="b09a7-284">Excel</span><span class="sxs-lookup"><span data-stu-id="b09a7-284">Excel</span></span>

- <span data-ttu-id="b09a7-285">文件標題的荷蘭文按鍵提示已變更為 Alt-G。</span><span class="sxs-lookup"><span data-stu-id="b09a7-285">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="b09a7-286">修正在 Excel 中指派給圖形或表單控制項的巨集可能顯示不正確的錯誤訊息，或者可能會處理不正確目標範圍的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-286">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="b09a7-287">解決「尋找及取代」在找到第一個項目後，對話方塊中的焦點位置變更的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-287">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="b09a7-288">此更新修正在與其他使用者共同撰寫的工作階段中變更樞紐分析表排序的方式，然後重新整理可能觸發當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-288">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="b09a7-289">我們已修正當 OLAP 樞紐分析表的篩選條件設定為已從 cube 移除的值時會發生的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-289">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="b09a7-290">修正以校正使用圖表範本插入圖表時，預覽中使用的色彩。</span><span class="sxs-lookup"><span data-stu-id="b09a7-290">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="b09a7-291">我們已修正當變更系列集合時，可能會導致散佈折線圖無法正確呈現的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-291">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span>

- <span data-ttu-id="b09a7-292">已解決當插入或刪除儲存格時，瀑布圖和漏斗圖無法與表格同步處理的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-292">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="b09a7-293">修正 Excel 中合併衝突的問題，此問題會造成提示使用者重新開啟活頁簿以取得變更。</span><span class="sxs-lookup"><span data-stu-id="b09a7-293">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="b09a7-294">解決了開啟內嵌活頁簿時，功能區自訂無法載入的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-294">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="b09a7-295">已解決造成執行階段錯誤啟動最小化視窗的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-295">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="b09a7-296">解決了開啟內嵌活頁簿時，功能區自訂無法載入的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-296">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="b09a7-297">已解決導致表格旁的剪下並貼上作業在與其他人共同撰寫時失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-297">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="b09a7-298">解決使用執行中巨集變更自訂屬性時，會導致共同撰寫中斷的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-298">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="b09a7-299">發生您無法從增益集開啟的 WPF (Windows Presentation Foundation) 表單的下拉式方塊選取項目的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-299">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="b09a7-300">解決在未開啟活頁簿時，搜尋最近使用的檔案會造成當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-300">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="b09a7-301">非同步使用者定義函數造成的效能問題，導致它們同步執行。</span><span class="sxs-lookup"><span data-stu-id="b09a7-301">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="b09a7-302">已大幅改善刪除有合併儲存格之欄的效能。</span><span class="sxs-lookup"><span data-stu-id="b09a7-302">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="b09a7-303">解決捲動後選取儲存格時，可能導致選取錯誤儲存格的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-303">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="b09a7-304">已解決 Lookup 函數可能會傳回錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-304">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="b09a7-305">解決在目前的 Office 版本中開啟在舊版 Office 中建立的活頁簿時，可能導致 Excel 懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-305">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="b09a7-306">當檔案具備大量設定格式化的條件時，按一下 [字型色彩] 按鈕時出現的效能緩慢問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-306">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="b09a7-307">我們已修正預覽列印中的列印範圍不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-307">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="b09a7-308">從不受信任的網路共用編輯受保護的檔案時，Excel 可能會發生問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-308">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="b09a7-309">我們已大幅提升依色彩篩選的效能。</span><span class="sxs-lookup"><span data-stu-id="b09a7-309">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="b09a7-310">已解決會導致將超連結貼到一些受保護工作表中的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-310">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="b09a7-311">當在增益集管理員中瀏覽時，顯示 16 個以上的增益集。</span><span class="sxs-lookup"><span data-stu-id="b09a7-311">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="b09a7-312">這項變更透過利用軟體轉譯避免特定 Intel 圖形驅動程式發生問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-312">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="b09a7-313">來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。</span><span class="sxs-lookup"><span data-stu-id="b09a7-313">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="b09a7-314">此更新修正 Office 文件無法上傳到商務用 OneDrive 的錯誤 (訊息「上傳失敗」)。</span><span class="sxs-lookup"><span data-stu-id="b09a7-314">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="b09a7-315">已修正在 Excel 構想功能中，在 Win32 用戶端中按一下 [構想] 按鈕來載入增益集時會發生錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-315">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span>

### <a name="outlook"></a><span data-ttu-id="b09a7-316">Outlook</span><span class="sxs-lookup"><span data-stu-id="b09a7-316">Outlook</span></span>

- <span data-ttu-id="b09a7-317">來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。</span><span class="sxs-lookup"><span data-stu-id="b09a7-317">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="b09a7-318">修正使用者將信箱從基本驗證升級為新式驗證後，造成將錯誤的帳戶與其 Outlook 設定檔相關聯的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-318">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="b09a7-319">已解決造成網頁增益集在不該存取數位版權管理郵件時進行存取的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-319">Addressed an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="b09a7-320">已解決導致部分安全連結無法顯示簡單動態顯示 URL 的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-320">Addressed an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="b09a7-321">更新 Outlook 中的附件封鎖邏輯，以同時封鎖 python 附件。</span><span class="sxs-lookup"><span data-stu-id="b09a7-321">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="b09a7-322">已解決導致部分 POP3 使用者查看所有純文字格式電子郵件 (無論設定) 的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-322">Addressed an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="b09a7-323">此修正將會還原 HTML 格式郵件的檢視。</span><span class="sxs-lookup"><span data-stu-id="b09a7-323">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="b09a7-324">已解決當使用者將項目從其主要行事曆複製到群組行事曆時，造成使用者遇到權限錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-324">Addressed an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="b09a7-325">已解決導致使用者無法透過螢幕助讀程式存取位置建議的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-325">Addressed an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="b09a7-326">已解決當使用者透過鍵盤快速鍵與信箱資料夾互動時造成明顯延遲的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-326">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="b09a7-327">已解決導致非常長時間的 Outlook 工作階段記憶體流失的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-327">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="b09a7-328">已解決導致使用者在開啟 [規則] 對話方塊時看到「在這部電腦中建立的規則和 Microsoft Exchange 上的規則衝突」提示的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-328">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="b09a7-329">已解決導致使用者在與特定安全連結互動時在 Outlook 中發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-329">Addressed an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="b09a7-330">已解決導致經理對於代理人是否已經回覆特定會議邀請含混不清的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-330">Addressed an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="b09a7-331">已解決導致使用者在處理某些自動探索回應時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-331">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="b09a7-332">已解決導致使用者在嘗試從 [帳戶建立] 內容連絡支援服務時，看到具有 [確定] 按鈕的空白訊息方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-332">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="b09a7-333">此變更可讓系統管理員啟用一個原則，以在自動探索驗證提示中較 UPN 優先使用所提供的帳戶電子郵件。</span><span class="sxs-lookup"><span data-stu-id="b09a7-333">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="b09a7-334">依預設，自動探索會優先於帳戶 UPN (如果有的話)。</span><span class="sxs-lookup"><span data-stu-id="b09a7-334">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="b09a7-335">解決會導致使用者看到針對新式群組的搜尋失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-335">Addressed an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="b09a7-336">已解決導致 Outlook 使用者在特定案例中停滯在「需要密碼」狀態的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-336">Addressed an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="b09a7-337">已解決以下問題：使用者看到某會議室可用時間之外的會議室建議。</span><span class="sxs-lookup"><span data-stu-id="b09a7-337">Addressed an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="b09a7-338">已解決導致使用者在傳送加密電子郵件時遇到「不支援的加密演算法」錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-338">Addressed an issue that caused users to encounter "encryption algorithm is not supported" errors when sending an encrypted email.</span></span>

- <span data-ttu-id="b09a7-339">已解決非英文使用者的郵件中，主旨列會相當小的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-339">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="b09a7-340">已解決導致某些使用者在新增次要 Exchange 帳戶時看到已建立重複特殊資料夾的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-340">Addressed an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="b09a7-341">已解決導致使用者嘗試從「未接的交談」建立規則時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-341">Addressed an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="b09a7-342">已修正 SMIME 演算法選取的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-342">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="b09a7-343">已解決使用其他寄件者時導致無法顯示原則提示的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-343">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="b09a7-344">已解決導致使用者在 Outlook 處理序中看到記憶體洩漏的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-344">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="b09a7-345">已解決導致使用者在更新目前狀態資訊時遇到間歇性當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-345">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="b09a7-346">已解決導致目前的資料夾搜尋間歇性失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-346">Addressed an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="b09a7-347">已解決嘗試擷取使用者的 Outlook 雲端設定時，導致一些使用者遇到驗證錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-347">Addressed an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="b09a7-348">已解決導致在搜尋意見反應體驗中懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-348">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="b09a7-349">已解決導致使用者在處理某些自動探索回應時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-349">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="b09a7-350">已解決導致使用者在更新目前狀態資訊時遇到間歇性當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-350">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b09a7-351">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b09a7-351">PowerPoint</span></span>

- <span data-ttu-id="b09a7-352">修正某些增益集會在圖表的圖形周圍擲出未預期錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-352">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="b09a7-353">來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。</span><span class="sxs-lookup"><span data-stu-id="b09a7-353">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="b09a7-354">此變更還原 PowerPoint 影片控制項的協助工具名稱的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-354">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="b09a7-355">我們已修正部分動畫無法開始的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-355">We fixed an issue which could prevent some animations from starting.</span></span>

- <span data-ttu-id="b09a7-356">我們已修正將投影片從一個簡報複製到另一個簡報時可能會造成母片重複的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-356">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>

- <span data-ttu-id="b09a7-357">如果在不支援的版本中開啟含有新的新式註解的檔案，將會顯示黃色警告</span><span class="sxs-lookup"><span data-stu-id="b09a7-357">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

- <span data-ttu-id="b09a7-358">可靠性修正：已修正第三方增益集可能會造成 PowerPoint 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-358">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="b09a7-359">已修正 PowerPoint 中半形片假名字元在垂直文字方塊中無法正確旋轉的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-359">Fixed an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="b09a7-360">Project</span><span class="sxs-lookup"><span data-stu-id="b09a7-360">Project</span></span>

- <span data-ttu-id="b09a7-361">修正讓 Windows 7 上的使用者能夠從 Project Web App 和 SharePoint 網站開啟專案的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-361">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="b09a7-362">發現在開啟唯讀專案時，使用者可能會收到數個訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-362">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="b09a7-363">「全部撫平」命令無法正確解決資源過度分派的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-363">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="b09a7-364">當您有作業中有零個工作的指派時，可能無法將作業標示為完成且永遠會顯示為 99%。</span><span class="sxs-lookup"><span data-stu-id="b09a7-364">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

### <a name="visio"></a><span data-ttu-id="b09a7-365">Visio</span><span class="sxs-lookup"><span data-stu-id="b09a7-365">Visio</span></span>

- <span data-ttu-id="b09a7-366">無法從 Visio 將多個圖形匯出為 SVG。</span><span class="sxs-lookup"><span data-stu-id="b09a7-366">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="b09a7-367">Word</span><span class="sxs-lookup"><span data-stu-id="b09a7-367">Word</span></span>

- <span data-ttu-id="b09a7-368">此變更能讓使用 Word 開啟文件的效能提升。</span><span class="sxs-lookup"><span data-stu-id="b09a7-368">This change will lead to performance improvements in opening documents using Word.</span></span>

- <span data-ttu-id="b09a7-369">來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。</span><span class="sxs-lookup"><span data-stu-id="b09a7-369">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="b09a7-370">我們已修正當列印到 Deskjet 印表機時，可能會導致縮放比例問題的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-370">We fixed an issue which could have caused scaling issues when printing to Deskjet printers.</span></span>

- <span data-ttu-id="b09a7-371">我們已修正追蹤修訂有時候會進入無限迴圈的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-371">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="b09a7-372">已修正應用程式可能在關機時懸置的各種問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-372">Fixed various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="b09a7-373">同時修正特定相關增益集當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-373">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="b09a7-374">Office 套件</span><span class="sxs-lookup"><span data-stu-id="b09a7-374">Office Suite</span></span>

- <span data-ttu-id="b09a7-375">已修正不正確地將平假名和漢字中的日本新年號 "Reiwa" (令和) 識別為拼字錯誤或不合文法的運算式的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-375">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="b09a7-376">已修正嘗試共用儲存在 SharePoint 2016 上的檔案時，導致使用者遇到「很抱歉，發生問題，無法共用」訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-376">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="b09a7-377">已修正在 PowerPoint 共同撰寫和離線編輯的工作階段中可能會導致資料遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-377">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="b09a7-378">修正使用者在開啟檔案時可能會遇到的當機問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-378">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="b09a7-379">避免 PowerPoint 使用者嘗試進行「線上展示」時遇到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-379">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

- <span data-ttu-id="b09a7-380">在某些情況下，同步處理引擎備份的 SharePoint 檔案可能會顯示「已儲存」但實際上未儲存任何變更，導致資料遺失。</span><span class="sxs-lookup"><span data-stu-id="b09a7-380">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="b09a7-381">解決使用者可能無法儲存 Word、Excel 和 PowerPoint 文件的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-381">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="b09a7-382">此問題會影響建立新檔案並在按一下 [儲存] 圖示或按 Ctrl + S 之後帶出 [另存成模型對話方塊] 選項的使用者。</span><span class="sxs-lookup"><span data-stu-id="b09a7-382">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="b09a7-383">已修正 Win7 的效能問題，其中，於所有應用程式中從功能區插入圖案庫時，大約需要 4 秒鐘的時間才會顯示。</span><span class="sxs-lookup"><span data-stu-id="b09a7-383">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="b09a7-384">已修正 Backstage 的 [資訊位置] 平板未顯示協助工具資訊的錯誤。</span><span class="sxs-lookup"><span data-stu-id="b09a7-384">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="b09a7-385">改善有關登錄完整性的 Office 更新程序的可靠性。</span><span class="sxs-lookup"><span data-stu-id="b09a7-385">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="b09a7-386">解決 Office 更新可能會非預期地從 Office CDN 而不是預期使用的來源 (例如本機或網路共用或 Configuration Manager 提供的位置) 下載檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-386">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="b09a7-387">修正了 Office 更新訊息不以預期語言顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-387">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="b09a7-388">自此以後，Office 更新訊息會正確符合 Windows 顯示語言。</span><span class="sxs-lookup"><span data-stu-id="b09a7-388">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="b09a7-389">已解決在某些情況下，如果使用者不是系統管理員且系統帳戶沒有網路連線，將無法套用更新的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-389">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="b09a7-390">某些情況下，Office 快速鍵可能會在更新後消失。</span><span class="sxs-lookup"><span data-stu-id="b09a7-390">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="b09a7-391">此更新可改善發佈 Office 快速鍵時的可靠性。</span><span class="sxs-lookup"><span data-stu-id="b09a7-391">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="b09a7-392">已更正可能會在計量網路上意外封鎖更新的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-392">Corrected an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="b09a7-393">修正相對期限只有在第一次設定時才會有效的 ODT 和 GPO 更新期限設定中的錯誤 (bug)。此修正可啟用後續更新的相關期限。</span><span class="sxs-lookup"><span data-stu-id="b09a7-393">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="b09a7-394">已改善透過恢復之前可能已中斷的下載，下載 Office 更新時的可靠性。</span><span class="sxs-lookup"><span data-stu-id="b09a7-394">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="b09a7-395">已解決第三方外掛程式中與文字方塊/圖案自動調整屬性相關的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-395">Addressed issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="b09a7-396">我們已修正大型樹狀檢視可能會導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-396">We fixed an issue where large tree views could result in a crash.</span></span>

- <span data-ttu-id="b09a7-397">為了保護 Office 客戶的安全性，我們現在專門使用 SHA-2 演算法來簽署 Microsoft Office 更新。</span><span class="sxs-lookup"><span data-stu-id="b09a7-397">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-january-14"></a><span data-ttu-id="b09a7-399">版本 1902：1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="b09a7-399">Version 1902: January 14</span></span>
<span data-ttu-id="b09a7-400">*版本 1902 (組建 11328.20512)*</span><span class="sxs-lookup"><span data-stu-id="b09a7-400">*Version 1902 (Build 11328.20512)*</span></span>

<span data-ttu-id="b09a7-401">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b09a7-401">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="b09a7-403">解決的問題</span><span class="sxs-lookup"><span data-stu-id="b09a7-403">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b09a7-404">Excel</span><span class="sxs-lookup"><span data-stu-id="b09a7-404">Excel</span></span>

- <span data-ttu-id="b09a7-405">解決了開啟內嵌活頁簿時，功能區自訂無法載入的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-405">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="b09a7-406">Outlook</span><span class="sxs-lookup"><span data-stu-id="b09a7-406">Outlook</span></span>

- <span data-ttu-id="b09a7-407">解決導致使用者在傳送加密電子郵件時遇到「不支援的加密演算法」錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="b09a7-407">Addresses an issue that caused users to encounter "encryption algorithm is not supporte" errors when sending an encrypted email.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b09a7-408">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b09a7-408">PowerPoint</span></span>

- <span data-ttu-id="b09a7-409">如果在不支援的版本中開啟含有新的新式註解的檔案，將會顯示黃色警告。</span><span class="sxs-lookup"><span data-stu-id="b09a7-409">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

### <a name="word"></a><span data-ttu-id="b09a7-410">Word</span><span class="sxs-lookup"><span data-stu-id="b09a7-410">Word</span></span>

- <span data-ttu-id="b09a7-411">此變更能讓使用 Word 開啟文件的效能提升。</span><span class="sxs-lookup"><span data-stu-id="b09a7-411">This change will lead to performance improvements in opening documents using Word.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1808-january-14"></a><span data-ttu-id="b09a7-413">版本 1808：1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="b09a7-413">Version 1808: January 14</span></span>
<span data-ttu-id="b09a7-414">*版本 1808 (組建 10730.20432)*</span><span class="sxs-lookup"><span data-stu-id="b09a7-414">*Version 1808 (Build 10730.20432)*</span></span>

<span data-ttu-id="b09a7-415">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b09a7-415">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

> [!NOTE]
> <span data-ttu-id="b09a7-417">如果您需要關於使用 Office 的問題協助，建議您將問題張貼在 [Microsoft Answers 論壇](https://answers.microsoft.com/)或[技術社群](https://techcommunity.microsoft.com/)，或連絡[支援](https://support.microsoft.com/contactus)。</span><span class="sxs-lookup"><span data-stu-id="b09a7-417">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>