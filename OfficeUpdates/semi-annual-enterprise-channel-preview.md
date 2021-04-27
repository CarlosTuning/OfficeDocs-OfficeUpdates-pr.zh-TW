---
title: 2021 年半年企業通道 (預覽) 版本的版本資訊
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為 IT 專業人員提供 2021 年 Microsoft 365 Apps 半年通道 (已設定目標) 版本的版本資訊
ms.openlocfilehash: 3a0307e973092e845ee17c17d22a8b160f9e9ef4
ms.sourcegitcommit: 5f72a0e94cda2cb64636380605806c29bbcdc53f
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/26/2021
ms.locfileid: "52026278"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-preview"></a><span data-ttu-id="921b7-103">半年企業通道 (預覽版) 的版本資訊</span><span class="sxs-lookup"><span data-stu-id="921b7-103">Release notes for Semi-Annual Enterprise Channel (Preview)</span></span>

<span data-ttu-id="921b7-104">這些版本資訊提供新功能和非安全性更新的相關資訊，這些功能和非安全性更新包含在 Microsoft 365 Apps 企業版、Microsoft 365 Apps 商務版，以及 Project 和 Visio 版的傳統型應用程式訂閱版本的半年企業通道 (預覽) 更新。</span><span class="sxs-lookup"><span data-stu-id="921b7-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel (Preview) updates for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="921b7-105">我們會變更 Microsoft 365 應用程式的更新通道，包括新增新的更新通道 (每月企業通道)，並變更現有的更新通道名稱。</span><span class="sxs-lookup"><span data-stu-id="921b7-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="921b7-106">如需深入了解，[請閱讀本文](/DeployOffice/update-channels-changes)。</span><span class="sxs-lookup"><span data-stu-id="921b7-106">To learn more, [read this article](/DeployOffice/update-channels-changes).</span></span>


## <a name="version-2102-april-13"></a><span data-ttu-id="921b7-107">版本 2102：4 月 13 日</span><span class="sxs-lookup"><span data-stu-id="921b7-107">Version 2102: April 13</span></span>
<span data-ttu-id="921b7-108">*版本 2102 (組建 13801.20506)*</span><span class="sxs-lookup"><span data-stu-id="921b7-108">*Version 2102 (Build 13801.20506)*</span></span>

<span data-ttu-id="921b7-109">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="921b7-109">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="921b7-111">解決的問題</span><span class="sxs-lookup"><span data-stu-id="921b7-111">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="921b7-112">Access</span><span class="sxs-lookup"><span data-stu-id="921b7-112">Access</span></span>

- <span data-ttu-id="921b7-113">修正在某些情況下，執行 SQL Server 傳遞查詢時，可能會導致錯誤訊息指出「無效的 Cursor 狀態」的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-113">Fixed an issue where in some cases running a SQL Server pass through query could result in an error message indicating that there was an "invalid cursor state".</span></span>


### <a name="excel"></a><span data-ttu-id="921b7-114">Excel</span><span class="sxs-lookup"><span data-stu-id="921b7-114">Excel</span></span>

- <span data-ttu-id="921b7-115">修正 Office 功能區中已停用的命令，在深灰色 Office 佈景主題中只會使圖示而非文字呈現灰色的錯誤。</span><span class="sxs-lookup"><span data-stu-id="921b7-115">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


- <span data-ttu-id="921b7-116">我們已修正將資料列新增至另一個工作表上的表格後，可能會非預期地對儲存格套用資料驗證的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-116">We fixed an issue in which data validation could be applied to cells unexpectedly after adding rows to a table on another sheet.</span></span>


- <span data-ttu-id="921b7-117">我們已修正 DialogSheets show 函數在 32 位元版本的 Excel 上無法運作的問題</span><span class="sxs-lookup"><span data-stu-id="921b7-117">We fixed an issue where the DialogSheets show function was not working on 32 bit versions of Excel</span></span>


### <a name="outlook"></a><span data-ttu-id="921b7-118">Outlook</span><span class="sxs-lookup"><span data-stu-id="921b7-118">Outlook</span></span>

- <span data-ttu-id="921b7-119">我們已修正會導致 Outlook 在閒置時當機的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-119">We fixed an issue that caused Outlook to crash when idle.</span></span>


- <span data-ttu-id="921b7-120">我們已修正會導致雲端設定功能的使用者在新裝置上設定 Outlook 之後，會看到自訂設定遭到預設設定覆寫的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-120">We fixed an issue that caused users of the Cloud Settings feature to see customized settings overridden by default setting after configuring Outlook on a new device.</span></span>


- <span data-ttu-id="921b7-121">我們已修正會導致使用者看到較預期更多的簽章的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-121">We fixed an issue that caused users to see more signatures than expected.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="921b7-122">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="921b7-122">PowerPoint</span></span>

- <span data-ttu-id="921b7-123">修正 Office 功能區中已停用的命令，在深灰色 Office 佈景主題中只會使圖示而非文字呈現灰色的錯誤。</span><span class="sxs-lookup"><span data-stu-id="921b7-123">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


### <a name="word"></a><span data-ttu-id="921b7-124">Word</span><span class="sxs-lookup"><span data-stu-id="921b7-124">Word</span></span>

- <span data-ttu-id="921b7-125">修正 Office 功能區中已停用的命令，在深灰色 Office 佈景主題中只會使圖示而非文字呈現灰色的錯誤。</span><span class="sxs-lookup"><span data-stu-id="921b7-125">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


- <span data-ttu-id="921b7-126">我們已修正有關複製和貼上的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-126">We fixed an issue relating to copy and paste.</span></span>


- <span data-ttu-id="921b7-127">我們已修正在隱藏段落結尾輸入可能會導致應用程式懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-127">We fixed an issue with typing at the end of a hidden paragraph may result in application hang.</span></span>


### <a name="office-suite"></a><span data-ttu-id="921b7-128">Office 套件</span><span class="sxs-lookup"><span data-stu-id="921b7-128">Office Suite</span></span>

- <span data-ttu-id="921b7-129">修正使用者在開啟先前開啟的檔案具有未儲存的編輯但現在檔案已遭到刪除時，無法儲存檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-129">Fixed an issue where users are unable to save file when open a previously opened file with edits not saved but now the file has been deleted.</span></span> <span data-ttu-id="921b7-130">修正之後，使用者將會收到一則友善的訊息，通知他們已刪除該檔案，因此使用者可以選擇捨棄變更，或將檔案另存為新檔。</span><span class="sxs-lookup"><span data-stu-id="921b7-130">After the fix, users will get a friendly message to inform them that the file is deleted, thus user can choose to discard changes, or SaveAs the file.</span></span>


- <span data-ttu-id="921b7-131">修正離線開啟 SyncBacked 檔案，然後於儲存檔案之前，在應用程式中重新命名檔案時重新命名失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-131">Fixed rename failure issue when open a SyncBacked file offline then rename the file in app before saving file.</span></span>


- <span data-ttu-id="921b7-132">修正針對 GCC 使用者停用聽寫的問題</span><span class="sxs-lookup"><span data-stu-id="921b7-132">Fixed an issue where Dictation was disabled for GCC users</span></span>


- <span data-ttu-id="921b7-133">修正有時可能會導致 Outlook 中的文字變得透明，因而無法辨認的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-133">Fixed an issue that could sometimes lead to text in Outlook becoming transparent and thereby not legible.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2102-march-09"></a><span data-ttu-id="921b7-135">版本 2102：3 月 9 日</span><span class="sxs-lookup"><span data-stu-id="921b7-135">Version 2102: March 09</span></span>
<span data-ttu-id="921b7-136">*版本 2102 (組建 13801.20294)*</span><span class="sxs-lookup"><span data-stu-id="921b7-136">*Version 2102 (Build 13801.20294)*</span></span>

<span data-ttu-id="921b7-137">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="921b7-137">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="921b7-139">功能更新</span><span class="sxs-lookup"><span data-stu-id="921b7-139">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="921b7-140">Excel</span><span class="sxs-lookup"><span data-stu-id="921b7-140">Excel</span></span>

- <span data-ttu-id="921b7-141">**[筆跡工具箱] 中的 [套索工具] 和 [橡皮擦]:** 使用繪圖工具時，[筆跡工具箱] 現在提供 [套索工具] 和 [橡皮擦] 功能。</span><span class="sxs-lookup"><span data-stu-id="921b7-141">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span><br /><span data-ttu-id="921b7-142">在[部落格文章](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="921b7-142">See details in [blog post](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span></span>

- <span data-ttu-id="921b7-143">**建立 PDF 連線：** 連線至、匯入、重新整理 PDF 中的資料。</span><span class="sxs-lookup"><span data-stu-id="921b7-143">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="921b7-144">深入了解</span><span class="sxs-lookup"><span data-stu-id="921b7-144">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="921b7-145">**建立變數以在公式中使用：** 使用 LET 函數改善效能、可讀性及可組合性。</span><span class="sxs-lookup"><span data-stu-id="921b7-145">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="921b7-146">此函數可讓您在新的或現有的公式中建立命名變數。</span><span class="sxs-lookup"><span data-stu-id="921b7-146">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="921b7-147">深入了解</span><span class="sxs-lookup"><span data-stu-id="921b7-147">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="921b7-148">在[部落格文章](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="921b7-148">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

- <span data-ttu-id="921b7-149">**儲存至釘選資料夾：** 釘選資料夾可讓您更輕鬆地儲存 Office 檔案。</span><span class="sxs-lookup"><span data-stu-id="921b7-149">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="921b7-150">我們收到了意見反應，使用者想更進一步控制儲存新檔案時可用的資料夾。</span><span class="sxs-lookup"><span data-stu-id="921b7-150">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="921b7-151">我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。</span><span class="sxs-lookup"><span data-stu-id="921b7-151">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="921b7-152">這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。</span><span class="sxs-lookup"><span data-stu-id="921b7-152">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="921b7-153">深入了解</span><span class="sxs-lookup"><span data-stu-id="921b7-153">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="921b7-154">在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="921b7-154">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="921b7-155">**使用資料類型從 Power BI 取得組織資料：** 現在，來自 Power BI 的 Excel 資料類型將推出給使用 Office 365 / Microsoft 365 和 Power BI Pro 服務方案的組織測試人員使用。</span><span class="sxs-lookup"><span data-stu-id="921b7-155">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 / Microsoft 365 and the Power BI Pro service plan.</span></span> <span data-ttu-id="921b7-156">取得您所需的資訊，輕鬆地重新整理，對許多日常工作流程而言至關重要。</span><span class="sxs-lookup"><span data-stu-id="921b7-156">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="921b7-157">我們允許您透過 Excel 中的資料類型從 Power BI 存取公司或組織資訊，從而擴充您在試算表中引入連結資訊的能力。</span><span class="sxs-lookup"><span data-stu-id="921b7-157">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="921b7-158">深入了解</span><span class="sxs-lookup"><span data-stu-id="921b7-158">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="921b7-159">在[部落格文章](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="921b7-159">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

- <span data-ttu-id="921b7-160">**將您的 iPhone 相片直接插入 Office：** 來自您手機的 HEIC 圖片現在可無縫地插入 Office。</span><span class="sxs-lookup"><span data-stu-id="921b7-160">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="921b7-161">不需要轉換。</span><span class="sxs-lookup"><span data-stu-id="921b7-161">No conversion required.</span></span><br /><span data-ttu-id="921b7-162">在[部落格文章](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="921b7-162">See details in [blog post](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="921b7-163">**在 Excel 中製作精美的 Visio 圖表：** 在工作表中從資料建立資料驅動的圖表，如流程圖或組織結構圖。</span><span class="sxs-lookup"><span data-stu-id="921b7-163">**Make polished Visio diagrams in Excel:** Create data-driven diagrams like flowcharts or organizational charts from data in a worksheet.</span></span> [<span data-ttu-id="921b7-164">深入了解</span><span class="sxs-lookup"><span data-stu-id="921b7-164">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="outlook"></a><span data-ttu-id="921b7-165">Outlook</span><span class="sxs-lookup"><span data-stu-id="921b7-165">Outlook</span></span>

- <span data-ttu-id="921b7-166">**協助保護群組中的資料：** 建立群組時所選擇的「敏感度」標籤會套用到群組電子郵件、文件及小組網站。</span><span class="sxs-lookup"><span data-stu-id="921b7-166">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites.</span></span>

- <span data-ttu-id="921b7-167">**IT 系統管理員的事件通知：** Microsoft 365 租用戶全域系統管理員和 Office 應用程式系統會在 Windows 版 Outlook 的新右側面板中收到影響其使用者的 Outlook 和 O365 Exchange 事件通知。</span><span class="sxs-lookup"><span data-stu-id="921b7-167">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="921b7-168">深入了解</span><span class="sxs-lookup"><span data-stu-id="921b7-168">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

- <span data-ttu-id="921b7-169">**在 Outlook 中使用快速投票建立投票：** 輕鬆建立投票、收集投票，並在電子郵件中檢視結果 [深入了解](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="921b7-169">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="921b7-170">**將您的 iPhone 相片直接插入 Office：** 來自您手機的 HEIC 圖片現在可無縫地插入 Office。</span><span class="sxs-lookup"><span data-stu-id="921b7-170">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="921b7-171">不需要轉換。</span><span class="sxs-lookup"><span data-stu-id="921b7-171">No conversion required.</span></span><br /><span data-ttu-id="921b7-172">在[部落格文章](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="921b7-172">See details in [blog post](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="921b7-173">**新的會議室尋找工具：** 依不同功能搜尋會議室。</span><span class="sxs-lookup"><span data-stu-id="921b7-173">**New room finder:** Search for conference rooms by different capabilities.</span></span>

- <span data-ttu-id="921b7-174">**以您說話的方式搜尋：** 使用日常語言如「上週獸醫的預約」來篩選和縮小搜尋範圍。</span><span class="sxs-lookup"><span data-stu-id="921b7-174">**Search for it the way you'd say it:** Use everyday language like "vet appointment last week" to filter and narrow your search.</span></span>

- <span data-ttu-id="921b7-175">**快速重新開啟上一個 Outlook 工作階段的項目：** 我們新增了一個選項，可快速重新開啟上一個 Outlook 工作階段的項目。</span><span class="sxs-lookup"><span data-stu-id="921b7-175">**Option to quickly reopen items from previous Outlook session:** We added an option to quickly reopen items from a previous Outlook session.</span></span><br /><span data-ttu-id="921b7-176">在[部落格文章](https://insider.office.com/zh-TW/blog/automatically-restore-windows-in-outlook)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="921b7-176">See details in [blog post](https://insider.office.com/zh-TW/blog/automatically-restore-windows-in-outlook)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="921b7-177">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="921b7-177">PowerPoint</span></span>

- <span data-ttu-id="921b7-178">**[筆跡工具箱] 中的 [套索工具] 和 [橡皮擦]:** 使用繪圖工具時，[筆跡工具箱] 現在提供 [套索工具] 和 [橡皮擦] 功能。</span><span class="sxs-lookup"><span data-stu-id="921b7-178">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span><br /><span data-ttu-id="921b7-179">在[部落格文章](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="921b7-179">See details in [blog post](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span></span>

- <span data-ttu-id="921b7-180">**儲存至釘選資料夾：** 釘選資料夾可讓您更輕鬆地儲存 Office 檔案。</span><span class="sxs-lookup"><span data-stu-id="921b7-180">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="921b7-181">我們收到了意見反應，使用者想更進一步控制儲存新檔案時可用的資料夾。</span><span class="sxs-lookup"><span data-stu-id="921b7-181">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="921b7-182">我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。</span><span class="sxs-lookup"><span data-stu-id="921b7-182">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="921b7-183">這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。</span><span class="sxs-lookup"><span data-stu-id="921b7-183">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="921b7-184">深入了解</span><span class="sxs-lookup"><span data-stu-id="921b7-184">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="921b7-185">在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="921b7-185">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="921b7-186">**將您的 iPhone 相片直接插入 Office：** 來自您手機的 HEIC 圖片現在可無縫地插入 Office。</span><span class="sxs-lookup"><span data-stu-id="921b7-186">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="921b7-187">不需要轉換。</span><span class="sxs-lookup"><span data-stu-id="921b7-187">No conversion required.</span></span><br /><span data-ttu-id="921b7-188">在[部落格文章](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="921b7-188">See details in [blog post](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="visio"></a><span data-ttu-id="921b7-189">Visio</span><span class="sxs-lookup"><span data-stu-id="921b7-189">Visio</span></span>

- <span data-ttu-id="921b7-190">**新 Azure 樣板和圖案：** 我們新增了更多的樣板來協助您建立最新的 Azure 圖表。</span><span class="sxs-lookup"><span data-stu-id="921b7-190">**New Azure stencils and shapes:** We've added many more stencils to help you create up-to-date Azure diagrams.</span></span> [<span data-ttu-id="921b7-191">深入了解</span><span class="sxs-lookup"><span data-stu-id="921b7-191">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

### <a name="word"></a><span data-ttu-id="921b7-192">Word</span><span class="sxs-lookup"><span data-stu-id="921b7-192">Word</span></span>

- <span data-ttu-id="921b7-193">**[筆跡工具箱] 中的 [套索工具] 和 [橡皮擦]:** 使用繪圖工具時，[筆跡工具箱] 現在提供 [套索工具] 和 [橡皮擦] 功能。</span><span class="sxs-lookup"><span data-stu-id="921b7-193">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span><br /><span data-ttu-id="921b7-194">在[部落格文章](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="921b7-194">See details in [blog post](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span></span>

- <span data-ttu-id="921b7-195">**儲存至釘選資料夾：** 釘選資料夾可讓您更輕鬆地儲存 Office 檔案。</span><span class="sxs-lookup"><span data-stu-id="921b7-195">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="921b7-196">我們收到了意見反應，使用者想更進一步控制儲存新檔案時可用的資料夾。</span><span class="sxs-lookup"><span data-stu-id="921b7-196">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="921b7-197">我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。</span><span class="sxs-lookup"><span data-stu-id="921b7-197">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="921b7-198">這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。</span><span class="sxs-lookup"><span data-stu-id="921b7-198">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="921b7-199">深入了解</span><span class="sxs-lookup"><span data-stu-id="921b7-199">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="921b7-200">在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="921b7-200">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="921b7-201">**將您的 iPhone 相片直接插入 Office：** 來自您手機的 HEIC 圖片現在可無縫地插入 Office。</span><span class="sxs-lookup"><span data-stu-id="921b7-201">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="921b7-202">不需要轉換。</span><span class="sxs-lookup"><span data-stu-id="921b7-202">No conversion required.</span></span><br /><span data-ttu-id="921b7-203">在[部落格文章](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="921b7-203">See details in [blog post](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="office-suite"></a><span data-ttu-id="921b7-204">Office 套件</span><span class="sxs-lookup"><span data-stu-id="921b7-204">Office Suite</span></span>

- <span data-ttu-id="921b7-205">**索引標籤式窗格：** 現在您可以使用應用程式右側的索引標籤 UI，在多個窗格之間切換。</span><span class="sxs-lookup"><span data-stu-id="921b7-205">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="921b7-206">只有當您開啟 2 個以上的窗格時，該 UI 才會顯示。</span><span class="sxs-lookup"><span data-stu-id="921b7-206">The UI will only be visible when you have 2+ panes open.</span></span><br /><span data-ttu-id="921b7-207">在[部落格文章](https://blog-insider.office.com/2020/02/20/improved-pane-management/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="921b7-207">See details in [blog post](https://blog-insider.office.com/2020/02/20/improved-pane-management/)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="921b7-210">解決的問題</span><span class="sxs-lookup"><span data-stu-id="921b7-210">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="921b7-211">存取</span><span class="sxs-lookup"><span data-stu-id="921b7-211">Access</span></span>

- <span data-ttu-id="921b7-212">我們已修正從非 Office 應用程式使用 DAO 時，會導致應用程式意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-212">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


- <span data-ttu-id="921b7-213">我們已修正使用者收到「資料指標狀態無效」錯誤對話方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-213">We fixed an issue where users were getting an error dialog " Invalid cursor state".</span></span>


### <a name="excel"></a><span data-ttu-id="921b7-214">Excel</span><span class="sxs-lookup"><span data-stu-id="921b7-214">Excel</span></span>

- <span data-ttu-id="921b7-215">我們已修正會破壞一些舊版 Excel 4.0 和 Excel 5.0 巨集以及對 dialogsheets.show 的一些 VBA 呼叫的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-215">We fixed an issue that broke some legacy Excel 4.0 and Excel 5.0 macros as well as some VBA calls to dialogsheets.show.</span></span>


- <span data-ttu-id="921b7-216">修正使用樞紐分析表的 [值的顯示方式] 功能表時，Excel 可能會意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-216">Fixed an issue where Excel might close unexpectedly when using the "Show Values As" menu for a PivotTable.</span></span>


- <span data-ttu-id="921b7-217">我們已修正會導致使用者無法將 Excel 活頁簿匯出至 PDF 的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-217">We fixed an issue that prevented users from exporting an Excel workbook to PDF.</span></span>


- <span data-ttu-id="921b7-218">我們已修正使用 [貼上連結圖片] 選項時，會導致影像小於預期的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-218">We fixed an issue which caused images to be smaller than expected when using the Paste Linked Picture option.</span></span>


- <span data-ttu-id="921b7-219">我們已修正在儲存為 .xls 或 .xlt 格式時，會導致某些樞紐分析表格式損壞活頁簿的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-219">We fixed an issue that caused some PivotTable formatting to corrupt the workbook when saving to the .xls or .xlt format.</span></span>


- <span data-ttu-id="921b7-220">修正在開啟含有 Excel 4.0 巨集的 Excel 增益集檔案時，Excel 可能會將巨集停用而不提示的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-220">Fixed an issue where Excel may leave macros disabled without prompting when opening an Excel Add-in file containing Excel 4.0 Macros.</span></span>


- <span data-ttu-id="921b7-221">修正以下問題：Excel 錯誤地顯示檔案新版本可用的訊息列，並強制使用者將變更儲存到活頁簿的副本中或捨棄變更。</span><span class="sxs-lookup"><span data-stu-id="921b7-221">Fixed an issue where Excel would incorrectly show a message bar that a new version of the file is available and force the user to save their changes in a copy of the workbook or discard their changes.</span></span>


- <span data-ttu-id="921b7-222">修正當某些使用者在共同撰寫時會不正確地在訊息列中看到通知他們檔案有新版本的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-222">Fixed an issue where some users would incorrectly see a message bar informing them of a new version of a file when coauthoring.</span></span>


- <span data-ttu-id="921b7-223">修正當使用特定 Windows 安全性漏洞防護設定(SimExec、CallerCheck) 時，Excel 無法正常啟動或關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-223">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use.</span></span>


- <span data-ttu-id="921b7-224">我們已修正選取圖表的資料數列之後，Excel 會停止回應的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-224">We fixed an issue where Excel would stop responding after selecting a data series in a chart.</span></span>


- <span data-ttu-id="921b7-225">此變更解決了在方程式中正確顯示字型的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-225">This change addresses an issue with properly displaying fonts within equations.</span></span>


### <a name="outlook"></a><span data-ttu-id="921b7-226">Outlook</span><span class="sxs-lookup"><span data-stu-id="921b7-226">Outlook</span></span>

- <span data-ttu-id="921b7-227">我們已修正會導致使用者無法將 [編輯器] 權限授與代理人的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-227">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="921b7-228">我們已修正會導致某些使用者在特定搜尋案例中遇到 Outlook 異常關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-228">We fixed an issue that caused some users to experience Outlook to close unexpectedly in certain search scenarios.</span></span>


- <span data-ttu-id="921b7-229">我們已修正會導致在其設定檔中具有大型階層的共用或委派信箱的使用者遇到停止回應的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-229">We fixed an issue that caused users that have Shared or Delegated Mailboxes with large hierarchies in their profile to encounter hangs.</span></span>


- <span data-ttu-id="921b7-230">已解決當主旨行空白時，會導致傳送的自動產生電子郵件含有空白內文的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-230">Addressed an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


- <span data-ttu-id="921b7-231">解決了導致某些使用者觀察到在離線狀態下意外啟動 Outlook 的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-231">Addressed an issue that caused some users to observe Outlook unexpectedly starting in an offline state.</span></span>


- <span data-ttu-id="921b7-232">已解決在開啟另一個信箱中的共用資料夾時，會導致代理人看到間歇性失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-232">Addressed an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


- <span data-ttu-id="921b7-233">我們已修正會導致使用者在選取搜尋結果時遇到非預期終止的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-233">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="921b7-234">我們已修正會導致某些客戶在載入行事曆時遇到懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-234">We fixed an issue that caused some customers to encounter a hang while loading their calendars.</span></span>


- <span data-ttu-id="921b7-235">我們已修正會導致某些會議的原始出席者在另一個出席者轉寄會議時收到取消通知的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-235">We fixed an issue that caused the original attendees of some meetings to receive a cancellation when another attendee forwards the meeting.</span></span>


- <span data-ttu-id="921b7-236">我們已修正會導致使用者在建立新群組後看到重複的行事曆群組的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-236">We fixed and issue that caused users to see duplicate calendar groups appearing after creating a new group.</span></span>


- <span data-ttu-id="921b7-237">我們已修正會導致共用行事曆改良功能的使用者無法將行事曆的色彩設定為黃色或褐色的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-237">We fixed an issue that caused users of the Shared Calendar improvements to be unable to set a calendar's color to yellow or brown.</span></span>


- <span data-ttu-id="921b7-238">我們已修正會導致使用者在 Outlook 重新啟動之前，在功能窗格中看不到新增的行事曆顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-238">We fixed a problem that caused users to see newly added calendars fail to appear in the navigation pane until after Outlook had been restarted.</span></span>


- <span data-ttu-id="921b7-239">已解決在搜尋未快取的共用行事曆時，會導致搜尋未傳回結果的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-239">Addressed an issue that caused Search to return no results when searching uncached shared calendars.</span></span>


- <span data-ttu-id="921b7-240">我們已修正會導致某些使用者在關閉訊息視窗時遇到應用程式關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-240">We fixed an issue that  caused some users to experience the app to shut down when closing message windows.</span></span>


- <span data-ttu-id="921b7-241">修正在傳送工作的狀態報告時，造成 [收件者] 欄位為空白的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-241">We fixed an issue that caused the To field to be blank when sending a status report on a task.</span></span>


- <span data-ttu-id="921b7-242">我們已修正會導致 MailItem.BeforeAttachmentAdd 事件中斷的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-242">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="921b7-243">我們已修正會導致某些使用者在特定搜尋案例中遇到 Outlook 未預期關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-243">We fixed an issue that caused some users to experience Outlook closing unexpectedly in certain search scenarios.</span></span>


- <span data-ttu-id="921b7-244">我們已修正使用者在 Outlook 中進行搜尋時，有時候會導致應用程式未預期關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-244">We fixed an issue that caused the app to sometimes close unexpectedly when users were searching in Outlook.</span></span>


- <span data-ttu-id="921b7-245">我們已修正會導致雲端設定使用者在更新設定時遇到懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-245">We fixed an issue that caused Cloud Settings users to experience a hang when updating settings.</span></span>


- <span data-ttu-id="921b7-246">我們已修正在提示使用者儲存已編輯的簽章後，會導致該動作無法執行的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-246">We fixed an issue that caused an edited signature to fail to save after prompting the user to do so.</span></span>


- <span data-ttu-id="921b7-247">我們已修正會導致某些使用者未設定一或多個簽章時，在 [簽名] 下拉式清單中看不到任何簽名的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-247">We fixed an issue that caused some users to see no signatures in the signatures drop down despite having one or more signatures configured.</span></span>


- <span data-ttu-id="921b7-248">我們已修正會導致預設不會為使用者開啟雲端設定的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-248">We fixed an issue that caused Cloud Settings not to be turned on for users by default.</span></span>


- <span data-ttu-id="921b7-249">我們已修正會導致對使用者簽章的變更無法儲存的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-249">We fixed an issue that caused changes to a user's signature to fail to save.</span></span>


- <span data-ttu-id="921b7-250">我們已修正會導致 Outlook 為已啟用雲端設定的使用者建立第二個空白簽名的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-250">We fixed an issue that caused Outlook to create a second empty signature for people who had cloud settings enabled.</span></span>


- <span data-ttu-id="921b7-251">我們已修正會導致在 OWA 中顯示正確的預設簽章時發生問題的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-251">We fixed an issue that caused issues with displaying the correct default signature in OWA.</span></span>


- <span data-ttu-id="921b7-252">我們已修正會導致使用者看到包含 Unicode 內容的簽章損毀的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-252">We fixed an issue that caused users to see signatures containing unicode content to get damaged.</span></span>


- <span data-ttu-id="921b7-253">我們已修正會導致內嵌翻譯的使用者無法提交意見反應的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-253">We fixed an issue that caused users of inline translation to be unable to submit feedback.</span></span>


- <span data-ttu-id="921b7-254">我們已修正當回覆或轉寄郵件時，會導致中文郵件標題無法閱讀的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-254">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


- <span data-ttu-id="921b7-255">我們已修正在儲存為 OFT 檔案時，會導致中文字元變更為問號的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-255">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


- <span data-ttu-id="921b7-256">我們新增了一個 RegKey，可讓客戶停用 IDataObject 操作 (例如，拖曳拖放、剪貼簿) 中附件的 FileTime 包含。</span><span class="sxs-lookup"><span data-stu-id="921b7-256">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="921b7-257">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments。</span><span class="sxs-lookup"><span data-stu-id="921b7-257">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span></span>  <span data-ttu-id="921b7-258">REG_DWORD IncludeFileTimesInDataObject。</span><span class="sxs-lookup"><span data-stu-id="921b7-258">REG_DWORD IncludeFileTimesInDataObject.</span></span>  <span data-ttu-id="921b7-259">0 = 不包含 filetimes。</span><span class="sxs-lookup"><span data-stu-id="921b7-259">0 = filetimes are excluded.</span></span>  <span data-ttu-id="921b7-260">1 = (預設) 包含 filetimes。</span><span class="sxs-lookup"><span data-stu-id="921b7-260">1 = (default) filetimes are included.</span></span>


- <span data-ttu-id="921b7-261">修正當回覆含有「Azure 資訊保護」保護標籤的郵件時，導致內嵌影像消失的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-261">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


- <span data-ttu-id="921b7-262">我們已修正會導致加密圖示無法對使用僅加密選項傳送的電子郵件顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-262">We fixed an issue that caused the encryption icon to fail to display on emails sent using the encryption only option.</span></span>


- <span data-ttu-id="921b7-263">我們已修正會導致郵件在使用者取消選取該選項之後，以數位簽章方式傳送的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-263">We fixed an issue that caused mails to be sent as digitally signed after the user unchecked that option.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="921b7-264">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="921b7-264">PowerPoint</span></span>

- <span data-ttu-id="921b7-265">修正如果文件儲存失敗，可能會導致應用程式非預期關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-265">Fixed an issue that could cause the application to close unexpectedly if a document save failed.</span></span>


- <span data-ttu-id="921b7-266">修正將方程式從 Word 複製/貼上到 PowerPoint 時的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-266">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


- <span data-ttu-id="921b7-267">此變更解決對某些幾何圖形套用 [合併圖案] 作業時路徑填充的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-267">This change addresses an issue with path fills when applying Merge Shapes operations with certain geometries.</span></span>


- <span data-ttu-id="921b7-268">此變更解決了在方程式中正確顯示字型的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-268">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="921b7-269">此變更解決了處理載入影片期間可能發生錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-269">This change addresses an issue with handling errors that may occur during video loading.</span></span>


- <span data-ttu-id="921b7-270">我們已修正 Slide.Shapes.AddMediaObject2 會對舊版影片格式 (MPG-1、Mpeg-2) 發生非預期關閉的 VBA 問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-270">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 would unexpectedly close with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="921b7-271">我們已修正在 QAT 中新增的字型大小命令在更新時自動完成到最接近的已定義字型大小的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-271">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="921b7-272">我們已修正在複製含有新錄製音訊的投影片後，儲存檔案時發生錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-272">We fixed an issue where there is an error when saving the file after duplicating a slide that contains a newly recorded audio.</span></span>


- <span data-ttu-id="921b7-273">我們已修正 Forms 內容增益集在插入之後不會呈現，除非使用者按一下另一張投影片讓它顯示才會呈現的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-273">We fixed an issue where Forms content add-in doesn't render after insertion until user clicks to another slide to make it show.</span></span>


- <span data-ttu-id="921b7-274">我們已修正在受保護的檢視中開啟 PowerPoint 檔案時，會停用 IRM 保護的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-274">We fixed an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


- <span data-ttu-id="921b7-275">修正會導致共同撰寫在包含大量特定資料物件類型 (E2o) 的檔案上變慢的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-275">Fixed an issue causing slow coauthoring on files containing large numbers of a certain data object type (E2o).</span></span>


- <span data-ttu-id="921b7-276">修正以解決在合併錯誤期間使用 IRM/受保護文件的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-276">Fix to address a an issue when using IRM/protected documents during a merge error.</span></span>


- <span data-ttu-id="921b7-277">這是此問題的修正：當有增益集在接聽 PresentationBeforeClose 事件並隨著事件處理常式檢查 Presentation.Saved 內容時若關閉文件，儲存提示會以迴圈顯示。</span><span class="sxs-lookup"><span data-stu-id="921b7-277">This is a fix for an issue where the save prompt shows in a loop when closing the document when there is an add-in that listens to PresentationBeforeClose event and checks Presentation.Saved property as a part of the event handler.</span></span>


- <span data-ttu-id="921b7-278">已修正無法正確開啟部分損壞的 PowerPoint 檔案 (即使在文件修復之後) 的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-278">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


- <span data-ttu-id="921b7-279">解決在某些情況下，選取設計構想會移除簡報的資料分類標籤的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-279">Addresses an issue where selecting a Design Idea removes the presentation's Data Classification Label, in certain cases.</span></span>


### <a name="project"></a><span data-ttu-id="921b7-280">Project</span><span class="sxs-lookup"><span data-stu-id="921b7-280">Project</span></span>

- <span data-ttu-id="921b7-281">修正當您將專案從 PWA 儲存到本機 mpp 檔案時，ProjectBeforeTaskChangeEvent 會對實際上未由使用者變更的資料觸發的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-281">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="921b7-282">修正如果工作表單類型檢視內的延隔時間變更，ProjectBeforeTaskChange 事件中的 NewVal 不會有正確值的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-282">Fixed an issue where the NewVal in the ProjectBeforeTaskChange event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


- <span data-ttu-id="921b7-283">修正若您的事件程式碼執行中，並嘗試透過工作 [表單檢視] 進行變更，按一下 [確定] 按鈕可能不會提交變更的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-283">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


- <span data-ttu-id="921b7-284">修正 Project 在開啟以特定方式指定資源分佈的檔案時可能會意外終止的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-284">Fixed an issue where Project may terminate unexpectedly when opening files where resource contours were specified in a certain manner.</span></span>


- <span data-ttu-id="921b7-285">已修正如果特定專案在負載的特定部分發生問題，可能會開啟特定專案的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-285">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>


- <span data-ttu-id="921b7-286">修正在 [團隊規劃] 檢視中工作沒有顯示邊框的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-286">Fixed an issue where borders weren't showing up for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="921b7-287">修正了在 [團隊規劃] 檢視中拖放工作不起作用的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-287">Fixed an issue where you drag and drop wasn't working for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="921b7-288">修正將成本資源指派給里程碑工作時，比較基準成本沒有正確彙總的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-288">Fixed an issue where when a cost resource was assigned to a milestone task, baseline cost didn't rollup correctly.</span></span>


### <a name="visio"></a><span data-ttu-id="921b7-289">Visio</span><span class="sxs-lookup"><span data-stu-id="921b7-289">Visio</span></span>

- <span data-ttu-id="921b7-290">修正使用者將可在自訂 Visio 樣板和內建範本中使用適用於 Office 365 的 Visio 連接器建立直線的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-290">We fixed an issue where users will be able to create straight lines using connectors in Visio for Office 365 for both custom Visio stencils and in-built templates.</span></span>


### <a name="word"></a><span data-ttu-id="921b7-291">Word</span><span class="sxs-lookup"><span data-stu-id="921b7-291">Word</span></span>

- <span data-ttu-id="921b7-292">修正如果文件儲存失敗，可能會導致應用程式非預期關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-292">Fixed an issue that could cause the application to close unexpectedly if a document save failed.</span></span>


- <span data-ttu-id="921b7-293">修正將方程式從 Word 複製/貼上到 PowerPoint 時的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-293">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


- <span data-ttu-id="921b7-294">此變更可解決編輯文件時游標的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-294">This change addresses an issue with the cursor when editing a document.</span></span>


- <span data-ttu-id="921b7-295">修正對具有 3D 效果的圖示和 SVG 圖形套用色彩的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-295">Fixes an issue with colors applied to icons and SVG graphics with 3D effects.</span></span>


- <span data-ttu-id="921b7-296">我們已修正可能會略過段落的朗讀程式問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-296">We fixed an issue with Narrator which may skips over a paragraph.</span></span>


- <span data-ttu-id="921b7-297">我們已修正 RTF 內容控制項的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-297">We fixed an issue with Rich text content controls.</span></span>


- <span data-ttu-id="921b7-298">我們已修正 [樣式庫] 對話方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-298">We fixed an issue with Style Gallery dialog.</span></span>


- <span data-ttu-id="921b7-299">我們已修正解決共同撰寫時衝突的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-299">We fixed an issue in resolving conflicts while in coauthoring.</span></span>


- <span data-ttu-id="921b7-300">我們已修正文件樣式會以範本中的其他樣式取代的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-300">We fixed an issue which document styles are replaced with other styles from the template.</span></span>


- <span data-ttu-id="921b7-301">修正會影響 Word 的最佳化閘道所暴露的宣告錯誤。</span><span class="sxs-lookup"><span data-stu-id="921b7-301">Fix an assert bug exposed by optimized gates affecting Word.</span></span>


### <a name="office-suite"></a><span data-ttu-id="921b7-302">Office 套件</span><span class="sxs-lookup"><span data-stu-id="921b7-302">Office Suite</span></span>

- <span data-ttu-id="921b7-303">我們已修正在嘗試儲存已從 syncbacked 檔案轉換為僅限伺服器的檔案時，導致失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-303">We fixed an issue that was causing a failure when trying to save files that have transitioned from syncbacked to server-only.</span></span>


- <span data-ttu-id="921b7-304">修正在某些情況下，嘗試執行另存新檔會失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-304">Fixed an issue where trying to do a SaveAs would fail in certain scenarios.</span></span>


- <span data-ttu-id="921b7-305">我們已修正 SaveRequestManagerCam 會導致應用程式關閉，而非傳回錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-305">We fixed an issue where SaveRequestManagerCam was causing the application to close instead of returning an error.</span></span>


- <span data-ttu-id="921b7-306">修正檔案關閉順序，使得所有相互依賴的元件都能正常關閉。</span><span class="sxs-lookup"><span data-stu-id="921b7-306">Fixed the file closing sequence so that all the interdependent components are closed gracefully.</span></span>


- <span data-ttu-id="921b7-307">修正當來自快取的 URL 與來自 OneDrive 的 URL 不相符時，檔案將被開啟為 NOT SyncBacked 的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-307">Fixed an issue of file would be opened as NOT SyncBacked when url from cache and url from OneDrive does NOT match.</span></span>


- <span data-ttu-id="921b7-308">修正在商務用 Skype 訊息中複製/貼上時，會導致出現對話方塊顯示「貼上您的內容時發生問題」的錯誤。</span><span class="sxs-lookup"><span data-stu-id="921b7-308">Fixing a bug where copy/paste in Skype for Business messages resulted in a dialog displaying "Something went wrong when pasting your content".</span></span>


- <span data-ttu-id="921b7-309">修正將註解中的文字複製/貼上到 Excel 時會發生錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-309">Fixed an issue where an error would occur when copy/paste text from a comment into Excel</span></span>


- <span data-ttu-id="921b7-310">修正在包含數學方程式的文字內使用朗讀程式時可能發生的損毀。</span><span class="sxs-lookup"><span data-stu-id="921b7-310">Fix a crash that could happen when using narrator within text that contains math equations.</span></span>


- <span data-ttu-id="921b7-311">當使用者從 Office 噴墨印表機上列印任何文件/檔案且列印機墨水不足時，即使噴墨印表機沒有碳粉，也會顯示「碳粉不足」或「無碳粉」消息。</span><span class="sxs-lookup"><span data-stu-id="921b7-311">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="921b7-312">將訊息變更為顯示「碳粉/墨水不足」和「沒有碳粉/墨水」。</span><span class="sxs-lookup"><span data-stu-id="921b7-312">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


- <span data-ttu-id="921b7-313">已修復在某些較舊的版本上安裝較新版的 Office 時，可能會造成功能受損 (例如由於遺失登錄專案而無法使用 Power Query) 的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-313">Fixed an issue where installing a newer version of Office over certain older versions can result in impaired functionality (such as being unable to use Power Query) due to missing registry entries.</span></span>


- <span data-ttu-id="921b7-314">修正 Microsoft 365 端點資料外洩防護無法分類磁碟上 Office 文件的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-314">Fixed an issue where Microsoft 365 Endpoint data loss prevention was unable to classify Office documents on disk.</span></span>


- <span data-ttu-id="921b7-315">我們已修正 [壓縮圖片] 對話方塊未保留某些使用者設定的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-315">We fixed an issue with the Compress Picture dialog not retaining certain user settings.</span></span>


- <span data-ttu-id="921b7-316">修正與媒體控制器事件通知相關的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-316">Fixes an issue related to media controller event notifications.</span></span>


- <span data-ttu-id="921b7-317">修正與媒體播放程式引擎時間相關的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-317">Fixes an issue related to media player engine timing.</span></span>


- <span data-ttu-id="921b7-318">優化的二進位大小。</span><span class="sxs-lookup"><span data-stu-id="921b7-318">Optimized binary size.</span></span>


- <span data-ttu-id="921b7-319">Anaheim WebView 目前尚不支援 Windows 資訊保護(WIP)。</span><span class="sxs-lookup"><span data-stu-id="921b7-319">Anaheim WebView does not support Windows Information Protection (WIP) yet.</span></span> <span data-ttu-id="921b7-320">有了此修正程式，Office addin 平臺便會回到處於 WIP 啟用環境中的低層級 WebView。</span><span class="sxs-lookup"><span data-stu-id="921b7-320">With this fix Office addin platform falls back to down level WebView in WIP enabled environment.</span></span> <span data-ttu-id="921b7-321">根據客戶的電腦環境，這可以是 Edge Spartan WebView 或 Trident WebView。</span><span class="sxs-lookup"><span data-stu-id="921b7-321">That can be either Edge Spartan WebView or Trident WebView depending on customer's machine environment.</span></span> <span data-ttu-id="921b7-322">兩個低層級 WebViews 皆支援 WIP。</span><span class="sxs-lookup"><span data-stu-id="921b7-322">Both down level WebViews support WIP.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-february-09"></a><span data-ttu-id="921b7-324">版本 2008：2 月 9 日</span><span class="sxs-lookup"><span data-stu-id="921b7-324">Version 2008: February 09</span></span>
<span data-ttu-id="921b7-325">*版本 2008 (組建 13127.21216)*</span><span class="sxs-lookup"><span data-stu-id="921b7-325">*Version 2008 (Build 13127.21216)*</span></span>

<span data-ttu-id="921b7-326">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="921b7-326">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="921b7-328">解決的問題</span><span class="sxs-lookup"><span data-stu-id="921b7-328">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="921b7-329">Excel</span><span class="sxs-lookup"><span data-stu-id="921b7-329">Excel</span></span>

- <span data-ttu-id="921b7-330">修正了當開啟具有無效檔案内容 (建立時間、修改時間等) 的 UNC 檔案時，Excel 會意外關閉的問題</span><span class="sxs-lookup"><span data-stu-id="921b7-330">Fixed an issue where Excel would close unexpectedly when opening UNC files that have invalid file attributes (creation time, modified time, etc.)</span></span>


- <span data-ttu-id="921b7-331">我們已修正將圖表從 Excel 複製並貼到 Word 或 PowerPoint 時，小數位和千分位分隔符號設定不會執行的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-331">We fixed an issue where decimal and thousands separators settings would not carry over when copying a chart from Excel and pasting into Word or PowerPoint.</span></span>


- <span data-ttu-id="921b7-332">我們已修正執行涉及樞紐分析表範圍格式設定的巨集，在每次執行巨集時效能都會變差的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-332">We fixed an issue where the performance of running a macro involving PivotTable range formatting would get worse each time the macro is run.</span></span>


- <span data-ttu-id="921b7-333">我們已修正將工作表複製或移動到另一個活頁簿時，設定格式化的條件規則的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-333">We fixed an issue where conditional formatting rules were dropped when copying or moving sheets to another workbook.</span></span>


- <span data-ttu-id="921b7-334">我們已修正當應用程式啟動時停用開始頁面，使用者無法將敏感度標籤套用至 Excel 檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-334">We fixed an issue where users were unable to apply sensitivity labels to Excel files when the start screen on app boot was disabled.</span></span>


- <span data-ttu-id="921b7-335">我們已修正從 OneDrive 同步處理資料夾開啟雲端檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-335">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="outlook"></a><span data-ttu-id="921b7-336">Outlook</span><span class="sxs-lookup"><span data-stu-id="921b7-336">Outlook</span></span>

- <span data-ttu-id="921b7-337">解決在新增或儲存附件時，會導致 Outlook 停止運作的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-337">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="921b7-338">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="921b7-338">PowerPoint</span></span>

- <span data-ttu-id="921b7-339">我們已修正一個問題，即在 QAT 中新增的字型大小命令在更新時，會自動完成到最接近的已定義字型大小。</span><span class="sxs-lookup"><span data-stu-id="921b7-339">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="921b7-340">修正使用保留來源格式設定選項複製及貼上投影片時，有時會將此設定意外地複製到新的投影片母片的問題</span><span class="sxs-lookup"><span data-stu-id="921b7-340">Fixed an issue where copy and paste of a slide with 'keep source formatting' option would sometimes copy over a new slide master unexpectedly</span></span>


### <a name="word"></a><span data-ttu-id="921b7-341">Word</span><span class="sxs-lookup"><span data-stu-id="921b7-341">Word</span></span>

- <span data-ttu-id="921b7-342">我們已修正有時開啟 Word 文件可能會顯示錯誤對話方塊的追蹤修訂問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-342">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>


- <span data-ttu-id="921b7-343">我們已修正從 OneDrive 同步處理資料夾開啟雲端檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-343">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="office-suite"></a><span data-ttu-id="921b7-344">Office 套件</span><span class="sxs-lookup"><span data-stu-id="921b7-344">Office Suite</span></span>

- <span data-ttu-id="921b7-345">修正無法在 Office 中成功開啟檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-345">Fixed an issue that prevented successful open of a file in Office.</span></span>


- <span data-ttu-id="921b7-346">修正使用複製格式將包含草繪外框的文件套用至連接器可能會損毀的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-346">Fixed an issue where documents containing Sketched outlines applied to connectors via Format Painter could become corrupted.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-january-12"></a><span data-ttu-id="921b7-348">版本 2008：1 月 12 日</span><span class="sxs-lookup"><span data-stu-id="921b7-348">Version 2008: January 12</span></span>
<span data-ttu-id="921b7-349">*版本 2008 (組建 13127.21064)*</span><span class="sxs-lookup"><span data-stu-id="921b7-349">*Version 2008 (Build 13127.21064)*</span></span>

<span data-ttu-id="921b7-350">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="921b7-350">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="921b7-352">解決的問題</span><span class="sxs-lookup"><span data-stu-id="921b7-352">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="921b7-353">Excel</span><span class="sxs-lookup"><span data-stu-id="921b7-353">Excel</span></span>

- <span data-ttu-id="921b7-354">修正唯讀書籍在開啟時無法再重新整理樞紐分析表資料的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-354">Fixed an issue where read-only books would no longer refresh pivot table data when opened.</span></span>


- <span data-ttu-id="921b7-355">這項變更提供下列問題的修正程式：從 OneDrive 本機同步處理資料夾插入檔案時，Excel 的 [插入物件] 不會顯示正確的圖示。</span><span class="sxs-lookup"><span data-stu-id="921b7-355">This change provides a fix for the following issue: Excel "Insert Object" does not show correct icon when inserts a file from OneDrive local sync folder.</span></span>


- <span data-ttu-id="921b7-356">修正客戶在共同撰寫時會錯誤地得到有關文件新版本通知的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-356">Fixed an issue where customers would incorrectly get notified about a new version of the file when coauthoring.</span></span>


- <span data-ttu-id="921b7-357">修正即使用 IME 和覆寫模式將錯誤地推進額外的字元的編輯問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-357">Fixed an editing issue where using IME with Overwrite mode would incorrectly advance extra characters.</span></span>


- <span data-ttu-id="921b7-358">修復了將即時資料與多執行緒 recalc 功能結合使用時出現的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-358">Fixed an issue when using real time data in conjunction with multithreaded recalc functionality.</span></span>


- <span data-ttu-id="921b7-359">修正當使用特定 Windows 安全性漏洞防護設定(SimExec、CallerCheck) 時，Excel 無法正常啟動或關閉的問題</span><span class="sxs-lookup"><span data-stu-id="921b7-359">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use</span></span>


### <a name="outlook"></a><span data-ttu-id="921b7-360">Outlook</span><span class="sxs-lookup"><span data-stu-id="921b7-360">Outlook</span></span>

- <span data-ttu-id="921b7-361">我們已修正導致 SmartLinks 在儲存至草稿時格式遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-361">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


- <span data-ttu-id="921b7-362">我們已修正讓使用者能在覆寫原則時自訂調整文字的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-362">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


- <span data-ttu-id="921b7-363">我們已修正會導致中文字元在儲存為 OFT 檔案時變更為問號的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-363">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="921b7-364">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="921b7-364">PowerPoint</span></span>

- <span data-ttu-id="921b7-365">我們已修正 Slide.Shapes.AddMediaObject2 會對舊版影片格式 (MPG-1、Mpeg-2) 發生意外關閉的 VBA 問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-365">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 would unexpectedly close with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="921b7-366">已修正無法正確開啟部分損壞的 PowerPoint 檔案 (即使在文件修復之後) 的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-366">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="project"></a><span data-ttu-id="921b7-367">Project</span><span class="sxs-lookup"><span data-stu-id="921b7-367">Project</span></span>

- <span data-ttu-id="921b7-368">我們已修正在開啟以特定方式指定資源分佈的檔案時，Project 可能會意外終止的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-368">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>


### <a name="skype"></a><span data-ttu-id="921b7-369">Skype</span><span class="sxs-lookup"><span data-stu-id="921b7-369">Skype</span></span>

- <span data-ttu-id="921b7-370">修正使用者的 TLS-DSK 憑證不會在預期時間續訂，而只在有效期剩餘不到 12 小時才續訂的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-370">Fixes an issue where a user's TLS-DSK certificate would not renew at the expected time, instead only renewing when less than 12 hours remain on its validity.</span></span>


- <span data-ttu-id="921b7-371">修正當 Office 尚未獲得授權時，商務用 Skype UI 在登入後顯示為空白的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-371">Fixes an issue where the Skype for Business UI shows as blank after signing in when Office is not yet licensed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="921b7-372">Office 套件</span><span class="sxs-lookup"><span data-stu-id="921b7-372">Office Suite</span></span>

- <span data-ttu-id="921b7-373">此變更解決了與開啟包含舊圖表之檔案相關的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-373">This change addresses an issue related to opening files containing legacy diagrams.</span></span>


- <span data-ttu-id="921b7-374">此變更解決了 SVG 回復 Proxy 導致存取衝突的問題。</span><span class="sxs-lookup"><span data-stu-id="921b7-374">This change addresses an issue with SVG fallback proxy resulting in access violations.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

> [!NOTE]
> <span data-ttu-id="921b7-377">如果您需要關於使用 Office 的問題協助，建議您將問題張貼在 [Microsoft Answers 論壇](https://answers.microsoft.com/)或[技術社群](https://techcommunity.microsoft.com/)，或連絡[支援](https://support.microsoft.com/contactus)。</span><span class="sxs-lookup"><span data-stu-id="921b7-377">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (DO NOT MODIFY ADMIN CENTER METADATA CONTENT START)
[//]: # (|Win32|FRDC|Insiders| |16.0.13801.20506|version-2102-april-13|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13801.20294|version-2102-march-09|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.21216|version-2008-february-09|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.21064|version-2008-january-12|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20910|version-2008-december-08|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20760|version-2008-november-10|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20638|version-2008-october-13|)
[//]: # (|Win32|FRDC|測試人員| |16.0.13127.20408|version-2008-september-08|)
[//]: # (|Win32|FRDC|測試人員| |16.0.12527.20988|version-2002-august-11|)
[//]: # (|Win32|FRDC|測試人員| |16.0.12527.20880|version-2002-july-14|)
[//]: # (DO NOT MODIFY ADMIN CENTER METADATA CONTENT END)
