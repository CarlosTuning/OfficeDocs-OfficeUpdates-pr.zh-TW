---
title: 2020年的半年期企業通道（預覽版）發行記錄
ms.author: anankani
author: andymosten
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為 IT 專業人員提供 2020 年 Microsoft 365 Apps 半年通道 (已設定目標) 版本的版本資訊
ms.openlocfilehash: d6c48db35445d15503c246506bc7d03da3ca0548
ms.sourcegitcommit: 4a2190fd43c552c92d8194ec4520673d75af22f1
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/13/2021
ms.locfileid: "51748961"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-preview"></a><span data-ttu-id="8efa7-103">半年企業通道 (預覽版) 的版本資訊</span><span class="sxs-lookup"><span data-stu-id="8efa7-103">Release notes for Semi-Annual Enterprise Channel (Preview)</span></span>

<span data-ttu-id="8efa7-104">這些版本資訊提供新功能和非安全性更新的相關資訊，這些功能和非安全性更新包含在 Microsoft 365 Apps 企業版、Microsoft 365 Apps 商務版，以及 Project 和 Visio 版的傳統型應用程式訂閱版本的半年企業通道 (預覽) 更新。</span><span class="sxs-lookup"><span data-stu-id="8efa7-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel (Preview) updates for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="8efa7-105">我們會變更 Microsoft 365 應用程式的更新通道，包括新增新的更新通道 (每月企業通道)，並變更現有的更新通道名稱。</span><span class="sxs-lookup"><span data-stu-id="8efa7-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="8efa7-106">如需深入了解，[請閱讀本文](/DeployOffice/update-channels-changes)。</span><span class="sxs-lookup"><span data-stu-id="8efa7-106">To learn more, [read this article](/DeployOffice/update-channels-changes).</span></span>


## <a name="version-2102-april-13"></a><span data-ttu-id="8efa7-107">版本 2102：4 月 13 日</span><span class="sxs-lookup"><span data-stu-id="8efa7-107">Version 2102: April 13</span></span>
<span data-ttu-id="8efa7-108">*版本 2102 (組建 13801.20506)*</span><span class="sxs-lookup"><span data-stu-id="8efa7-108">*Version 2102 (Build 13801.20506)*</span></span>

<span data-ttu-id="8efa7-109">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="8efa7-109">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8efa7-111">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8efa7-111">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="8efa7-112">Access</span><span class="sxs-lookup"><span data-stu-id="8efa7-112">Access</span></span>

- <span data-ttu-id="8efa7-113">修正在某些情況下，執行 SQL Server 傳遞查詢時，可能會導致錯誤訊息指出「無效的 Cursor 狀態」的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-113">Fixed an issue where in some cases running a SQL Server pass through query could result in an error message indicating that there was an "invalid cursor state".</span></span>


### <a name="excel"></a><span data-ttu-id="8efa7-114">Excel</span><span class="sxs-lookup"><span data-stu-id="8efa7-114">Excel</span></span>

- <span data-ttu-id="8efa7-115">修正 Office 功能區中已停用的命令，在深灰色 Office 佈景主題中只會使圖示而非文字呈現灰色的錯誤。</span><span class="sxs-lookup"><span data-stu-id="8efa7-115">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


- <span data-ttu-id="8efa7-116">我們已修正將資料列新增至另一個工作表上的表格後，可能會非預期地對儲存格套用資料驗證的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-116">We fixed an issue in which data validation could be applied to cells unexpectedly after adding rows to a table on another sheet.</span></span>


- <span data-ttu-id="8efa7-117">我們已修正 DialogSheets show 函數在 32 位元版本的 Excel 上無法運作的問題</span><span class="sxs-lookup"><span data-stu-id="8efa7-117">We fixed an issue where the DialogSheets show function was not working on 32 bit versions of Excel</span></span>


### <a name="outlook"></a><span data-ttu-id="8efa7-118">Outlook</span><span class="sxs-lookup"><span data-stu-id="8efa7-118">Outlook</span></span>

- <span data-ttu-id="8efa7-119">我們已修正會導致 Outlook 在閒置時當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-119">We fixed an issue that caused Outlook to crash when idle.</span></span>


- <span data-ttu-id="8efa7-120">我們已修正會導致雲端設定功能的使用者在新裝置上設定 Outlook 之後，會看到自訂設定遭到預設設定覆寫的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-120">We fixed an issue that caused users of the Cloud Settings feature to see customized settings overridden by default setting after configuring Outlook on a new device.</span></span>


- <span data-ttu-id="8efa7-121">我們已修正會導致使用者看到較預期更多的簽章的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-121">We fixed an issue that caused users to see more signatures than expected.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="8efa7-122">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8efa7-122">PowerPoint</span></span>

- <span data-ttu-id="8efa7-123">修正 Office 功能區中已停用的命令，在深灰色 Office 佈景主題中只會使圖示而非文字呈現灰色的錯誤。</span><span class="sxs-lookup"><span data-stu-id="8efa7-123">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


### <a name="word"></a><span data-ttu-id="8efa7-124">Word</span><span class="sxs-lookup"><span data-stu-id="8efa7-124">Word</span></span>

- <span data-ttu-id="8efa7-125">修正 Office 功能區中已停用的命令，在深灰色 Office 佈景主題中只會使圖示而非文字呈現灰色的錯誤。</span><span class="sxs-lookup"><span data-stu-id="8efa7-125">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


- <span data-ttu-id="8efa7-126">我們已修正有關複製和貼上的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-126">We fixed an issue relating to copy and paste.</span></span>


- <span data-ttu-id="8efa7-127">我們已修正在隱藏段落結尾輸入可能會導致應用程式懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-127">We fixed an issue with typing at the end of a hidden paragraph may result in application hang.</span></span>


### <a name="office-suite"></a><span data-ttu-id="8efa7-128">Office 套件</span><span class="sxs-lookup"><span data-stu-id="8efa7-128">Office Suite</span></span>

- <span data-ttu-id="8efa7-129">修正使用者在開啟先前開啟的檔案具有未儲存的編輯但現在檔案已遭到刪除時，無法儲存檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-129">Fixed an issue where users are unable to save file when open a previously opened file with edits not saved but now the file has been deleted.</span></span> <span data-ttu-id="8efa7-130">修正之後，使用者將會收到一則友善的訊息，通知他們已刪除該檔案，因此使用者可以選擇捨棄變更，或將檔案另存為新檔。</span><span class="sxs-lookup"><span data-stu-id="8efa7-130">After the fix, users will get a friendly message to inform them that the file is deleted, thus user can choose to discard changes, or SaveAs the file.</span></span>


- <span data-ttu-id="8efa7-131">修正離線開啟 SyncBacked 檔案，然後於儲存檔案之前，在應用程式中重新命名檔案時重新命名失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-131">Fixed rename failure issue when open a SyncBacked file offline then rename the file in app before saving file.</span></span>


- <span data-ttu-id="8efa7-132">修正針對 GCC 使用者停用聽寫的問題</span><span class="sxs-lookup"><span data-stu-id="8efa7-132">Fixed an issue where Dictation was disabled for GCC users</span></span>


- <span data-ttu-id="8efa7-133">修正有時可能會導致 Outlook 中的文字變得透明，因而無法辨認的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-133">Fixed an issue that could sometimes lead to text in Outlook becoming transparent and thereby not legible.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2102-march-09"></a><span data-ttu-id="8efa7-135">版本 2102：3 月 9 日</span><span class="sxs-lookup"><span data-stu-id="8efa7-135">Version 2102: March 09</span></span>
<span data-ttu-id="8efa7-136">*版本 2102 (組建 13801.20294)*</span><span class="sxs-lookup"><span data-stu-id="8efa7-136">*Version 2102 (Build 13801.20294)*</span></span>

<span data-ttu-id="8efa7-137">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="8efa7-137">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="8efa7-139">功能更新</span><span class="sxs-lookup"><span data-stu-id="8efa7-139">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="8efa7-140">Excel</span><span class="sxs-lookup"><span data-stu-id="8efa7-140">Excel</span></span>

- <span data-ttu-id="8efa7-141">**[筆跡工具箱] 中的 [套索工具] 和 [橡皮擦]:** 使用繪圖工具時，[筆跡工具箱] 現在提供 [套索工具] 和 [橡皮擦] 功能。</span><span class="sxs-lookup"><span data-stu-id="8efa7-141">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span><br /><span data-ttu-id="8efa7-142">在[部落格文章](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8efa7-142">See details in [blog post](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span></span>

- <span data-ttu-id="8efa7-143">**建立 PDF 連線：** 連線至、匯入、重新整理 PDF 中的資料。</span><span class="sxs-lookup"><span data-stu-id="8efa7-143">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="8efa7-144">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-144">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="8efa7-145">**建立變數以在公式中使用：** 使用 LET 函數改善效能、可讀性及可組合性。</span><span class="sxs-lookup"><span data-stu-id="8efa7-145">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="8efa7-146">此函數可讓您在新的或現有的公式中建立命名變數。</span><span class="sxs-lookup"><span data-stu-id="8efa7-146">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="8efa7-147">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-147">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="8efa7-148">在[部落格文章](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8efa7-148">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

- <span data-ttu-id="8efa7-149">**儲存至釘選資料夾：** 釘選資料夾可讓您更輕鬆地儲存 Office 檔案。</span><span class="sxs-lookup"><span data-stu-id="8efa7-149">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="8efa7-150">我們收到了意見反應，使用者想更進一步控制儲存新檔案時可用的資料夾。</span><span class="sxs-lookup"><span data-stu-id="8efa7-150">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="8efa7-151">我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。</span><span class="sxs-lookup"><span data-stu-id="8efa7-151">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="8efa7-152">這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。</span><span class="sxs-lookup"><span data-stu-id="8efa7-152">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="8efa7-153">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-153">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="8efa7-154">在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8efa7-154">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="8efa7-155">**使用資料類型從 Power BI 取得組織資料：** 現在，來自 Power BI 的 Excel 資料類型將推出給使用 Office 365 / Microsoft 365 和 Power BI Pro 服務方案的組織測試人員使用。</span><span class="sxs-lookup"><span data-stu-id="8efa7-155">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 / Microsoft 365 and the Power BI Pro service plan.</span></span> <span data-ttu-id="8efa7-156">取得您所需的資訊，輕鬆地重新整理，對許多日常工作流程而言至關重要。</span><span class="sxs-lookup"><span data-stu-id="8efa7-156">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="8efa7-157">我們允許您透過 Excel 中的資料類型從 Power BI 存取公司或組織資訊，從而擴充您在試算表中引入連結資訊的能力。</span><span class="sxs-lookup"><span data-stu-id="8efa7-157">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="8efa7-158">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-158">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="8efa7-159">在[部落格文章](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8efa7-159">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

- <span data-ttu-id="8efa7-160">**將您的 iPhone 相片直接插入 Office：** 來自您手機的 HEIC 圖片現在可無縫地插入 Office。</span><span class="sxs-lookup"><span data-stu-id="8efa7-160">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="8efa7-161">不需要轉換。</span><span class="sxs-lookup"><span data-stu-id="8efa7-161">No conversion required.</span></span><br /><span data-ttu-id="8efa7-162">在[部落格文章](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8efa7-162">See details in [blog post](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="8efa7-163">**在 Excel 中製作精美的 Visio 圖表：** 在工作表中從資料建立資料驅動的圖表，如流程圖或組織結構圖。</span><span class="sxs-lookup"><span data-stu-id="8efa7-163">**Make polished Visio diagrams in Excel:** Create data-driven diagrams like flowcharts or organizational charts from data in a worksheet.</span></span> [<span data-ttu-id="8efa7-164">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-164">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="outlook"></a><span data-ttu-id="8efa7-165">Outlook</span><span class="sxs-lookup"><span data-stu-id="8efa7-165">Outlook</span></span>

- <span data-ttu-id="8efa7-166">**協助保護群組中的資料：** 建立群組時所選擇的「敏感度」標籤會套用到群組電子郵件、文件及小組網站。</span><span class="sxs-lookup"><span data-stu-id="8efa7-166">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites.</span></span>

- <span data-ttu-id="8efa7-167">**IT 系統管理員的事件通知：** Microsoft 365 租用戶全域系統管理員和 Office 應用程式系統會在 Windows 版 Outlook 的新右側面板中收到影響其使用者的 Outlook 和 O365 Exchange 事件通知。</span><span class="sxs-lookup"><span data-stu-id="8efa7-167">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="8efa7-168">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-168">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

- <span data-ttu-id="8efa7-169">**在 Outlook 中使用快速投票建立投票：** 輕鬆建立投票、收集投票，並在電子郵件中檢視結果 [深入了解](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="8efa7-169">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="8efa7-170">**將您的 iPhone 相片直接插入 Office：** 來自您手機的 HEIC 圖片現在可無縫地插入 Office。</span><span class="sxs-lookup"><span data-stu-id="8efa7-170">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="8efa7-171">不需要轉換。</span><span class="sxs-lookup"><span data-stu-id="8efa7-171">No conversion required.</span></span><br /><span data-ttu-id="8efa7-172">在[部落格文章](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8efa7-172">See details in [blog post](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="8efa7-173">**新的會議室尋找工具：** 依不同功能搜尋會議室。</span><span class="sxs-lookup"><span data-stu-id="8efa7-173">**New room finder:** Search for conference rooms by different capabilities.</span></span>

- <span data-ttu-id="8efa7-174">**以您說話的方式搜尋：** 使用日常語言如「上週獸醫的預約」來篩選和縮小搜尋範圍。</span><span class="sxs-lookup"><span data-stu-id="8efa7-174">**Search for it the way you'd say it:** Use everyday language like "vet appointment last week" to filter and narrow your search.</span></span>

- <span data-ttu-id="8efa7-175">**快速重新開啟上一個 Outlook 工作階段的項目：** 我們新增了一個選項，可快速重新開啟上一個 Outlook 工作階段的項目。</span><span class="sxs-lookup"><span data-stu-id="8efa7-175">**Option to quickly reopen items from previous Outlook session:** We added an option to quickly reopen items from a previous Outlook session.</span></span><br /><span data-ttu-id="8efa7-176">在[部落格文章](https://insider.office.com/zh-TW/blog/automatically-restore-windows-in-outlook)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8efa7-176">See details in [blog post](https://insider.office.com/zh-TW/blog/automatically-restore-windows-in-outlook)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8efa7-177">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8efa7-177">PowerPoint</span></span>

- <span data-ttu-id="8efa7-178">**[筆跡工具箱] 中的 [套索工具] 和 [橡皮擦]:** 使用繪圖工具時，[筆跡工具箱] 現在提供 [套索工具] 和 [橡皮擦] 功能。</span><span class="sxs-lookup"><span data-stu-id="8efa7-178">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span><br /><span data-ttu-id="8efa7-179">在[部落格文章](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8efa7-179">See details in [blog post](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span></span>

- <span data-ttu-id="8efa7-180">**儲存至釘選資料夾：** 釘選資料夾可讓您更輕鬆地儲存 Office 檔案。</span><span class="sxs-lookup"><span data-stu-id="8efa7-180">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="8efa7-181">我們收到了意見反應，使用者想更進一步控制儲存新檔案時可用的資料夾。</span><span class="sxs-lookup"><span data-stu-id="8efa7-181">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="8efa7-182">我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。</span><span class="sxs-lookup"><span data-stu-id="8efa7-182">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="8efa7-183">這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。</span><span class="sxs-lookup"><span data-stu-id="8efa7-183">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="8efa7-184">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-184">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="8efa7-185">在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8efa7-185">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="8efa7-186">**將您的 iPhone 相片直接插入 Office：** 來自您手機的 HEIC 圖片現在可無縫地插入 Office。</span><span class="sxs-lookup"><span data-stu-id="8efa7-186">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="8efa7-187">不需要轉換。</span><span class="sxs-lookup"><span data-stu-id="8efa7-187">No conversion required.</span></span><br /><span data-ttu-id="8efa7-188">在[部落格文章](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8efa7-188">See details in [blog post](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="visio"></a><span data-ttu-id="8efa7-189">Visio</span><span class="sxs-lookup"><span data-stu-id="8efa7-189">Visio</span></span>

- <span data-ttu-id="8efa7-190">**新 Azure 樣板和圖案：** 我們新增了更多的樣板來協助您建立最新的 Azure 圖表。</span><span class="sxs-lookup"><span data-stu-id="8efa7-190">**New Azure stencils and shapes:** We've added many more stencils to help you create up-to-date Azure diagrams.</span></span> [<span data-ttu-id="8efa7-191">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-191">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

### <a name="word"></a><span data-ttu-id="8efa7-192">Word</span><span class="sxs-lookup"><span data-stu-id="8efa7-192">Word</span></span>

- <span data-ttu-id="8efa7-193">**[筆跡工具箱] 中的 [套索工具] 和 [橡皮擦]:** 使用繪圖工具時，[筆跡工具箱] 現在提供 [套索工具] 和 [橡皮擦] 功能。</span><span class="sxs-lookup"><span data-stu-id="8efa7-193">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span><br /><span data-ttu-id="8efa7-194">在[部落格文章](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8efa7-194">See details in [blog post](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span></span>

- <span data-ttu-id="8efa7-195">**儲存至釘選資料夾：** 釘選資料夾可讓您更輕鬆地儲存 Office 檔案。</span><span class="sxs-lookup"><span data-stu-id="8efa7-195">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="8efa7-196">我們收到了意見反應，使用者想更進一步控制儲存新檔案時可用的資料夾。</span><span class="sxs-lookup"><span data-stu-id="8efa7-196">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="8efa7-197">我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。</span><span class="sxs-lookup"><span data-stu-id="8efa7-197">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="8efa7-198">這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。</span><span class="sxs-lookup"><span data-stu-id="8efa7-198">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="8efa7-199">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-199">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="8efa7-200">在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8efa7-200">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="8efa7-201">**將您的 iPhone 相片直接插入 Office：** 來自您手機的 HEIC 圖片現在可無縫地插入 Office。</span><span class="sxs-lookup"><span data-stu-id="8efa7-201">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="8efa7-202">不需要轉換。</span><span class="sxs-lookup"><span data-stu-id="8efa7-202">No conversion required.</span></span><br /><span data-ttu-id="8efa7-203">在[部落格文章](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8efa7-203">See details in [blog post](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="office-suite"></a><span data-ttu-id="8efa7-204">Office 套件</span><span class="sxs-lookup"><span data-stu-id="8efa7-204">Office Suite</span></span>

- <span data-ttu-id="8efa7-205">**索引標籤式窗格：** 現在您可以使用應用程式右側的索引標籤 UI，在多個窗格之間切換。</span><span class="sxs-lookup"><span data-stu-id="8efa7-205">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="8efa7-206">只有當您開啟 2 個以上的窗格時，該 UI 才會顯示。</span><span class="sxs-lookup"><span data-stu-id="8efa7-206">The UI will only be visible when you have 2+ panes open.</span></span><br /><span data-ttu-id="8efa7-207">在[部落格文章](https://blog-insider.office.com/2020/02/20/improved-pane-management/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8efa7-207">See details in [blog post](https://blog-insider.office.com/2020/02/20/improved-pane-management/)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8efa7-210">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8efa7-210">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="8efa7-211">存取</span><span class="sxs-lookup"><span data-stu-id="8efa7-211">Access</span></span>

- <span data-ttu-id="8efa7-212">我們已修正從非 Office 應用程式使用 DAO 時，會導致應用程式意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-212">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


- <span data-ttu-id="8efa7-213">我們已修正使用者收到「資料指標狀態無效」錯誤對話方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-213">We fixed an issue where users were getting an error dialog " Invalid cursor state".</span></span>


### <a name="excel"></a><span data-ttu-id="8efa7-214">Excel</span><span class="sxs-lookup"><span data-stu-id="8efa7-214">Excel</span></span>

- <span data-ttu-id="8efa7-215">我們已修正會破壞一些舊版 Excel 4.0 和 Excel 5.0 巨集以及對 dialogsheets.show 的一些 VBA 呼叫的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-215">We fixed an issue that broke some legacy Excel 4.0 and Excel 5.0 macros as well as some VBA calls to dialogsheets.show.</span></span>


- <span data-ttu-id="8efa7-216">修正使用樞紐分析表的 [值的顯示方式] 功能表時，Excel 可能會意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-216">Fixed an issue where Excel might close unexpectedly when using the "Show Values As" menu for a PivotTable.</span></span>


- <span data-ttu-id="8efa7-217">我們已修正會導致使用者無法將 Excel 活頁簿匯出至 PDF 的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-217">We fixed an issue that prevented users from exporting an Excel workbook to PDF.</span></span>


- <span data-ttu-id="8efa7-218">我們已修正使用 [貼上連結圖片] 選項時，會導致影像小於預期的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-218">We fixed an issue which caused images to be smaller than expected when using the Paste Linked Picture option.</span></span>


- <span data-ttu-id="8efa7-219">我們已修正在儲存為 .xls 或 .xlt 格式時，會導致某些樞紐分析表格式損壞活頁簿的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-219">We fixed an issue that caused some PivotTable formatting to corrupt the workbook when saving to the .xls or .xlt format.</span></span>


- <span data-ttu-id="8efa7-220">修正在開啟含有 Excel 4.0 巨集的 Excel 增益集檔案時，Excel 可能會將巨集停用而不提示的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-220">Fixed an issue where Excel may leave macros disabled without prompting when opening an Excel Add-in file containing Excel 4.0 Macros.</span></span>


- <span data-ttu-id="8efa7-221">修正以下問題：Excel 錯誤地顯示檔案新版本可用的訊息列，並強制使用者將變更儲存到活頁簿的副本中或捨棄變更。</span><span class="sxs-lookup"><span data-stu-id="8efa7-221">Fixed an issue where Excel would incorrectly show a message bar that a new version of the file is available and force the user to save their changes in a copy of the workbook or discard their changes.</span></span>


- <span data-ttu-id="8efa7-222">修正當某些使用者在共同撰寫時會不正確地在訊息列中看到通知他們檔案有新版本的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-222">Fixed an issue where some users would incorrectly see a message bar informing them of a new version of a file when coauthoring.</span></span>


- <span data-ttu-id="8efa7-223">修正當使用特定 Windows 安全性漏洞防護設定(SimExec、CallerCheck) 時，Excel 無法正常啟動或關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-223">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use.</span></span>


- <span data-ttu-id="8efa7-224">我們已修正選取圖表的資料數列之後，Excel 會停止回應的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-224">We fixed an issue where Excel would stop responding after selecting a data series in a chart.</span></span>


- <span data-ttu-id="8efa7-225">此變更解決了在方程式中正確顯示字型的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-225">This change addresses an issue with properly displaying fonts within equations.</span></span>


### <a name="outlook"></a><span data-ttu-id="8efa7-226">Outlook</span><span class="sxs-lookup"><span data-stu-id="8efa7-226">Outlook</span></span>

- <span data-ttu-id="8efa7-227">我們已修正會導致使用者無法將 [編輯器] 權限授與代理人的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-227">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="8efa7-228">我們已修正會導致某些使用者在特定搜尋案例中遇到 Outlook 異常關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-228">We fixed an issue that caused some users to experience Outlook to close unexpectedly in certain search scenarios.</span></span>


- <span data-ttu-id="8efa7-229">我們已修正會導致在其設定檔中具有大型階層的共用或委派信箱的使用者遇到停止回應的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-229">We fixed an issue that caused users that have Shared or Delegated Mailboxes with large hierarchies in their profile to encounter hangs.</span></span>


- <span data-ttu-id="8efa7-230">已解決當主旨行空白時，會導致傳送的自動產生電子郵件含有空白內文的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-230">Addressed an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


- <span data-ttu-id="8efa7-231">解決了導致某些使用者觀察到在離線狀態下意外啟動 Outlook 的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-231">Addressed an issue that caused some users to observe Outlook unexpectedly starting in an offline state.</span></span>


- <span data-ttu-id="8efa7-232">已解決在開啟另一個信箱中的共用資料夾時，會導致代理人看到間歇性失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-232">Addressed an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


- <span data-ttu-id="8efa7-233">我們已修正會導致使用者在選取搜尋結果時遇到非預期終止的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-233">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="8efa7-234">我們已修正會導致某些客戶在載入行事曆時遇到懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-234">We fixed an issue that caused some customers to encounter a hang while loading their calendars.</span></span>


- <span data-ttu-id="8efa7-235">我們已修正會導致某些會議的原始出席者在另一個出席者轉寄會議時收到取消通知的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-235">We fixed an issue that caused the original attendees of some meetings to receive a cancellation when another attendee forwards the meeting.</span></span>


- <span data-ttu-id="8efa7-236">我們已修正會導致使用者在建立新群組後看到重複的行事曆群組的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-236">We fixed and issue that caused users to see duplicate calendar groups appearing after creating a new group.</span></span>


- <span data-ttu-id="8efa7-237">我們已修正會導致共用行事曆改良功能的使用者無法將行事曆的色彩設定為黃色或褐色的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-237">We fixed an issue that caused users of the Shared Calendar improvements to be unable to set a calendar's color to yellow or brown.</span></span>


- <span data-ttu-id="8efa7-238">我們已修正會導致使用者在 Outlook 重新啟動之前，在功能窗格中看不到新增的行事曆顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-238">We fixed a problem that caused users to see newly added calendars fail to appear in the navigation pane until after Outlook had been restarted.</span></span>


- <span data-ttu-id="8efa7-239">已解決在搜尋未快取的共用行事曆時，會導致搜尋未傳回結果的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-239">Addressed an issue that caused Search to return no results when searching uncached shared calendars.</span></span>


- <span data-ttu-id="8efa7-240">我們已修正會導致某些使用者在關閉訊息視窗時遇到應用程式關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-240">We fixed an issue that  caused some users to experience the app to shut down when closing message windows.</span></span>


- <span data-ttu-id="8efa7-241">修正在傳送工作的狀態報告時，造成 [收件者] 欄位為空白的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-241">We fixed an issue that caused the To field to be blank when sending a status report on a task.</span></span>


- <span data-ttu-id="8efa7-242">我們已修正會導致 MailItem.BeforeAttachmentAdd 事件中斷的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-242">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="8efa7-243">我們已修正會導致某些使用者在特定搜尋案例中遇到 Outlook 未預期關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-243">We fixed an issue that caused some users to experience Outlook closing unexpectedly in certain search scenarios.</span></span>


- <span data-ttu-id="8efa7-244">我們已修正使用者在 Outlook 中進行搜尋時，有時候會導致應用程式未預期關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-244">We fixed an issue that caused the app to sometimes close unexpectedly when users were searching in Outlook.</span></span>


- <span data-ttu-id="8efa7-245">我們已修正會導致雲端設定使用者在更新設定時遇到懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-245">We fixed an issue that caused Cloud Settings users to experience a hang when updating settings.</span></span>


- <span data-ttu-id="8efa7-246">我們已修正在提示使用者儲存已編輯的簽章後，會導致該動作無法執行的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-246">We fixed an issue that caused an edited signature to fail to save after prompting the user to do so.</span></span>


- <span data-ttu-id="8efa7-247">我們已修正會導致某些使用者未設定一或多個簽章時，在 [簽名] 下拉式清單中看不到任何簽名的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-247">We fixed an issue that caused some users to see no signatures in the signatures drop down despite having one or more signatures configured.</span></span>


- <span data-ttu-id="8efa7-248">我們已修正會導致預設不會為使用者開啟雲端設定的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-248">We fixed an issue that caused Cloud Settings not to be turned on for users by default.</span></span>


- <span data-ttu-id="8efa7-249">我們已修正會導致對使用者簽章的變更無法儲存的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-249">We fixed an issue that caused changes to a user's signature to fail to save.</span></span>


- <span data-ttu-id="8efa7-250">我們已修正會導致 Outlook 為已啟用雲端設定的使用者建立第二個空白簽名的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-250">We fixed an issue that caused Outlook to create a second empty signature for people who had cloud settings enabled.</span></span>


- <span data-ttu-id="8efa7-251">我們已修正會導致在 OWA 中顯示正確的預設簽章時發生問題的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-251">We fixed an issue that caused issues with displaying the correct default signature in OWA.</span></span>


- <span data-ttu-id="8efa7-252">我們已修正會導致使用者看到包含 Unicode 內容的簽章損毀的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-252">We fixed an issue that caused users to see signatures containing unicode content to get damaged.</span></span>


- <span data-ttu-id="8efa7-253">我們已修正會導致內嵌翻譯的使用者無法提交意見反應的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-253">We fixed an issue that caused users of inline translation to be unable to submit feedback.</span></span>


- <span data-ttu-id="8efa7-254">我們已修正當回覆或轉寄郵件時，會導致中文郵件標題無法閱讀的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-254">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


- <span data-ttu-id="8efa7-255">我們已修正在儲存為 OFT 檔案時，會導致中文字元變更為問號的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-255">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


- <span data-ttu-id="8efa7-256">我們新增了一個 RegKey，可讓客戶停用 IDataObject 操作 (例如，拖曳拖放、剪貼簿) 中附件的 FileTime 包含。</span><span class="sxs-lookup"><span data-stu-id="8efa7-256">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="8efa7-257">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments。</span><span class="sxs-lookup"><span data-stu-id="8efa7-257">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span></span>  <span data-ttu-id="8efa7-258">REG_DWORD IncludeFileTimesInDataObject。</span><span class="sxs-lookup"><span data-stu-id="8efa7-258">REG_DWORD IncludeFileTimesInDataObject.</span></span>  <span data-ttu-id="8efa7-259">0 = 不包含 filetimes。</span><span class="sxs-lookup"><span data-stu-id="8efa7-259">0 = filetimes are excluded.</span></span>  <span data-ttu-id="8efa7-260">1 = (預設) 包含 filetimes。</span><span class="sxs-lookup"><span data-stu-id="8efa7-260">1 = (default) filetimes are included.</span></span>


- <span data-ttu-id="8efa7-261">修正當回覆含有「Azure 資訊保護」保護標籤的郵件時，導致內嵌影像消失的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-261">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


- <span data-ttu-id="8efa7-262">我們已修正會導致加密圖示無法對使用僅加密選項傳送的電子郵件顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-262">We fixed an issue that caused the encryption icon to fail to display on emails sent using the encryption only option.</span></span>


- <span data-ttu-id="8efa7-263">我們已修正會導致郵件在使用者取消選取該選項之後，以數位簽章方式傳送的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-263">We fixed an issue that caused mails to be sent as digitally signed after the user unchecked that option.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="8efa7-264">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8efa7-264">PowerPoint</span></span>

- <span data-ttu-id="8efa7-265">修正如果文件儲存失敗，可能會導致應用程式非預期關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-265">Fixed an issue that could cause the application to close unexpectedly if a document save failed.</span></span>


- <span data-ttu-id="8efa7-266">修正將方程式從 Word 複製/貼上到 PowerPoint 時的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-266">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


- <span data-ttu-id="8efa7-267">此變更解決對某些幾何圖形套用 [合併圖案] 作業時路徑填充的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-267">This change addresses an issue with path fills when applying Merge Shapes operations with certain geometries.</span></span>


- <span data-ttu-id="8efa7-268">此變更解決了在方程式中正確顯示字型的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-268">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="8efa7-269">此變更解決了處理載入影片期間可能發生錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-269">This change addresses an issue with handling errors that may occur during video loading.</span></span>


- <span data-ttu-id="8efa7-270">我們已修正 Slide.Shapes.AddMediaObject2 會對舊版影片格式 (MPG-1、Mpeg-2) 發生非預期關閉的 VBA 問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-270">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 would unexpectedly close with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="8efa7-271">我們已修正在 QAT 中新增的字型大小命令在更新時自動完成到最接近的已定義字型大小的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-271">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="8efa7-272">我們已修正在複製含有新錄製音訊的投影片後，儲存檔案時發生錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-272">We fixed an issue where there is an error when saving the file after duplicating a slide that contains a newly recorded audio.</span></span>


- <span data-ttu-id="8efa7-273">我們已修正 Forms 內容增益集在插入之後不會呈現，除非使用者按一下另一張投影片讓它顯示才會呈現的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-273">We fixed an issue where Forms content add-in doesn't render after insertion until user clicks to another slide to make it show.</span></span>


- <span data-ttu-id="8efa7-274">我們已修正在受保護的檢視中開啟 PowerPoint 檔案時，會停用 IRM 保護的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-274">We fixed an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


- <span data-ttu-id="8efa7-275">修正會導致共同撰寫在包含大量特定資料物件類型 (E2o) 的檔案上變慢的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-275">Fixed an issue causing slow coauthoring on files containing large numbers of a certain data object type (E2o).</span></span>


- <span data-ttu-id="8efa7-276">修正以解決在合併錯誤期間使用 IRM/受保護文件的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-276">Fix to address a an issue when using IRM/protected documents during a merge error.</span></span>


- <span data-ttu-id="8efa7-277">這是此問題的修正：當有增益集在接聽 PresentationBeforeClose 事件並隨著事件處理常式檢查 Presentation.Saved 內容時若關閉文件，儲存提示會以迴圈顯示。</span><span class="sxs-lookup"><span data-stu-id="8efa7-277">This is a fix for an issue where the save prompt shows in a loop when closing the document when there is an add-in that listens to PresentationBeforeClose event and checks Presentation.Saved property as a part of the event handler.</span></span>


- <span data-ttu-id="8efa7-278">修正無法正確開啟部分損壞的 PowerPoint 檔案 (即使在文件修復之後) 的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-278">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


- <span data-ttu-id="8efa7-279">解決在某些情況下，選取設計構想會移除簡報的資料分類標籤的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-279">Addresses an issue where selecting a Design Idea removes the presentation's Data Classification Label, in certain cases.</span></span>


### <a name="project"></a><span data-ttu-id="8efa7-280">Project</span><span class="sxs-lookup"><span data-stu-id="8efa7-280">Project</span></span>

- <span data-ttu-id="8efa7-281">修正當您將專案從 PWA 儲存到本機 mpp 檔案時，ProjectBeforeTaskChangeEvent 會對實際上未由使用者變更的資料觸發的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-281">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="8efa7-282">修正如果工作表單類型檢視內的延隔時間變更，ProjectBeforeTaskChange 事件中的 NewVal 不會有正確值的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-282">Fixed an issue where the NewVal in the ProjectBeforeTaskChange event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


- <span data-ttu-id="8efa7-283">修正若您的事件程式碼執行中，並嘗試透過工作 [表單檢視] 進行變更，按一下 [確定] 按鈕可能不會提交變更的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-283">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


- <span data-ttu-id="8efa7-284">修正 Project 在開啟以特定方式指定資源分佈的檔案時可能會意外終止的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-284">Fixed an issue where Project may terminate unexpectedly when opening files where resource contours were specified in a certain manner.</span></span>


- <span data-ttu-id="8efa7-285">修正如果特定專案在負載的特定部分發生問題，可能會開啟特定專案的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-285">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>


- <span data-ttu-id="8efa7-286">修正在 [團隊規劃] 檢視中工作沒有顯示邊框的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-286">Fixed an issue where borders weren't showing up for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="8efa7-287">修正了在 [團隊規劃] 檢視中拖放工作不起作用的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-287">Fixed an issue where you drag and drop wasn't working for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="8efa7-288">修正將成本資源指派給里程碑工作時，比較基準成本沒有正確彙總的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-288">Fixed an issue where when a cost resource was assigned to a milestone task, baseline cost didn't rollup correctly.</span></span>


### <a name="visio"></a><span data-ttu-id="8efa7-289">Visio</span><span class="sxs-lookup"><span data-stu-id="8efa7-289">Visio</span></span>

- <span data-ttu-id="8efa7-290">修正使用者將可在自訂 Visio 樣板和內建範本中使用適用於 Office 365 的 Visio 連接器建立直線的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-290">We fixed an issue where users will be able to create straight lines using connectors in Visio for Office 365 for both custom Visio stencils and in-built templates.</span></span>


### <a name="word"></a><span data-ttu-id="8efa7-291">Word</span><span class="sxs-lookup"><span data-stu-id="8efa7-291">Word</span></span>

- <span data-ttu-id="8efa7-292">修正如果文件儲存失敗，可能會導致應用程式非預期關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-292">Fixed an issue that could cause the application to close unexpectedly if a document save failed.</span></span>


- <span data-ttu-id="8efa7-293">修正將方程式從 Word 複製/貼上到 PowerPoint 時的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-293">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


- <span data-ttu-id="8efa7-294">此變更可解決編輯文件時游標的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-294">This change addresses an issue with the cursor when editing a document.</span></span>


- <span data-ttu-id="8efa7-295">修正對具有 3D 效果的圖示和 SVG 圖形套用色彩的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-295">Fixes an issue with colors applied to icons and SVG graphics with 3D effects.</span></span>


- <span data-ttu-id="8efa7-296">我們已修正可能會略過段落的朗讀程式問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-296">We fixed an issue with Narrator which may skips over a paragraph.</span></span>


- <span data-ttu-id="8efa7-297">我們已修正 RTF 內容控制項的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-297">We fixed an issue with Rich text content controls.</span></span>


- <span data-ttu-id="8efa7-298">我們已修正 [樣式庫] 對話方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-298">We fixed an issue with Style Gallery dialog.</span></span>


- <span data-ttu-id="8efa7-299">我們已修正解決共同撰寫時衝突的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-299">We fixed an issue in resolving conflicts while in coauthoring.</span></span>


- <span data-ttu-id="8efa7-300">我們已修正文件樣式會以範本中的其他樣式取代的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-300">We fixed an issue which document styles are replaced with other styles from the template.</span></span>


- <span data-ttu-id="8efa7-301">修正會影響 Word 的最佳化閘道所暴露的宣告錯誤。</span><span class="sxs-lookup"><span data-stu-id="8efa7-301">Fix an assert bug exposed by optimized gates affecting Word.</span></span>


### <a name="office-suite"></a><span data-ttu-id="8efa7-302">Office 套件</span><span class="sxs-lookup"><span data-stu-id="8efa7-302">Office Suite</span></span>

- <span data-ttu-id="8efa7-303">我們已修正在嘗試儲存已從 syncbacked 檔案轉換為僅限伺服器的檔案時，導致失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-303">We fixed an issue that was causing a failure when trying to save files that have transitioned from syncbacked to server-only.</span></span>


- <span data-ttu-id="8efa7-304">修正在某些情況下，嘗試執行另存新檔會失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-304">Fixed an issue where trying to do a SaveAs would fail in certain scenarios.</span></span>


- <span data-ttu-id="8efa7-305">我們已修正 SaveRequestManagerCam 會導致應用程式關閉，而非傳回錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-305">We fixed an issue where SaveRequestManagerCam was causing the application to close instead of returning an error.</span></span>


- <span data-ttu-id="8efa7-306">修正檔案關閉順序，使得所有相互依賴的元件都能正常關閉。</span><span class="sxs-lookup"><span data-stu-id="8efa7-306">Fixed the file closing sequence so that all the interdependent components are closed gracefully.</span></span>


- <span data-ttu-id="8efa7-307">修正當來自快取的 URL 與來自 OneDrive 的 URL 不相符時，檔案將被開啟為 NOT SyncBacked 的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-307">Fixed an issue of file would be opened as NOT SyncBacked when url from cache and url from OneDrive does NOT match.</span></span>


- <span data-ttu-id="8efa7-308">修正在商務用 Skype 訊息中複製/貼上時，會導致出現對話方塊顯示「貼上您的內容時發生問題」的錯誤。</span><span class="sxs-lookup"><span data-stu-id="8efa7-308">Fixing a bug where copy/paste in Skype for Business messages resulted in a dialog displaying "Something went wrong when pasting your content".</span></span>


- <span data-ttu-id="8efa7-309">修正將註解中的文字複製/貼上到 Excel 時會發生錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-309">Fixed an issue where an error would occur when copy/paste text from a comment into Excel</span></span>


- <span data-ttu-id="8efa7-310">修正在包含數學方程式的文字內使用朗讀程式時可能發生的損毀。</span><span class="sxs-lookup"><span data-stu-id="8efa7-310">Fix a crash that could happen when using narrator within text that contains math equations.</span></span>


- <span data-ttu-id="8efa7-311">當使用者從 Office 噴墨印表機上列印任何文件/檔案且列印機墨水不足時，即使噴墨印表機沒有碳粉，也會顯示「碳粉不足」或「無碳粉」消息。</span><span class="sxs-lookup"><span data-stu-id="8efa7-311">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="8efa7-312">將訊息變更為顯示「碳粉/墨水不足」和「沒有碳粉/墨水」。</span><span class="sxs-lookup"><span data-stu-id="8efa7-312">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


- <span data-ttu-id="8efa7-313">已修復在某些較舊的版本上安裝較新版的 Office 時，可能會造成功能受損 (例如由於遺失登錄專案而無法使用 Power Query) 的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-313">Fixed an issue where installing a newer version of Office over certain older versions can result in impaired functionality (such as being unable to use Power Query) due to missing registry entries.</span></span>


- <span data-ttu-id="8efa7-314">修正 Microsoft 365 端點資料外洩防護無法分類磁碟上 Office 文件的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-314">Fixed an issue where Microsoft 365 Endpoint data loss prevention was unable to classify Office documents on disk.</span></span>


- <span data-ttu-id="8efa7-315">我們已修正 [壓縮圖片] 對話方塊未保留某些使用者設定的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-315">We fixed an issue with the Compress Picture dialog not retaining certain user settings.</span></span>


- <span data-ttu-id="8efa7-316">修正與媒體控制器事件通知相關的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-316">Fixes an issue related to media controller event notifications.</span></span>


- <span data-ttu-id="8efa7-317">修正與媒體播放程式引擎時間相關的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-317">Fixes an issue related to media player engine timing.</span></span>


- <span data-ttu-id="8efa7-318">優化的二進位大小。</span><span class="sxs-lookup"><span data-stu-id="8efa7-318">Optimized binary size.</span></span>


- <span data-ttu-id="8efa7-319">Anaheim WebView 目前尚不支援 Windows 資訊保護(WIP)。</span><span class="sxs-lookup"><span data-stu-id="8efa7-319">Anaheim WebView does not support Windows Information Protection (WIP) yet.</span></span> <span data-ttu-id="8efa7-320">有了此修正程式，Office addin 平臺便會回到處於 WIP 啟用環境中的低層級 WebView。</span><span class="sxs-lookup"><span data-stu-id="8efa7-320">With this fix Office addin platform falls back to down level WebView in WIP enabled environment.</span></span> <span data-ttu-id="8efa7-321">根據客戶的電腦環境，這可以是 Edge Spartan WebView 或 Trident WebView。</span><span class="sxs-lookup"><span data-stu-id="8efa7-321">That can be either Edge Spartan WebView or Trident WebView depending on customer's machine environment.</span></span> <span data-ttu-id="8efa7-322">兩個低層級 WebViews 皆支援 WIP。</span><span class="sxs-lookup"><span data-stu-id="8efa7-322">Both down level WebViews support WIP.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-february-09"></a><span data-ttu-id="8efa7-324">版本 2008：2 月 9 日</span><span class="sxs-lookup"><span data-stu-id="8efa7-324">Version 2008: February 09</span></span>
<span data-ttu-id="8efa7-325">*版本 2008 (組建 13127.21216)*</span><span class="sxs-lookup"><span data-stu-id="8efa7-325">*Version 2008 (Build 13127.21216)*</span></span>

<span data-ttu-id="8efa7-326">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="8efa7-326">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8efa7-328">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8efa7-328">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="8efa7-329">Excel</span><span class="sxs-lookup"><span data-stu-id="8efa7-329">Excel</span></span>

- <span data-ttu-id="8efa7-330">修正了當開啟具有無效檔案内容 (建立時間、修改時間等) 的 UNC 檔案時，Excel 會意外關閉的問題</span><span class="sxs-lookup"><span data-stu-id="8efa7-330">Fixed an issue where Excel would close unexpectedly when opening UNC files that have invalid file attributes (creation time, modified time, etc.)</span></span>


- <span data-ttu-id="8efa7-331">我們已修正將圖表從 Excel 複製並貼到 Word 或 PowerPoint 時，小數位和千分位分隔符號設定不會執行的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-331">We fixed an issue where decimal and thousands separators settings would not carry over when copying a chart from Excel and pasting into Word or PowerPoint.</span></span>


- <span data-ttu-id="8efa7-332">我們已修正執行涉及樞紐分析表範圍格式設定的巨集，在每次執行巨集時效能都會變差的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-332">We fixed an issue where the performance of running a macro involving PivotTable range formatting would get worse each time the macro is run.</span></span>


- <span data-ttu-id="8efa7-333">我們已修正將工作表複製或移動到另一個活頁簿時，設定格式化的條件規則的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-333">We fixed an issue where conditional formatting rules were dropped when copying or moving sheets to another workbook.</span></span>


- <span data-ttu-id="8efa7-334">我們已修正當應用程式啟動時停用開始頁面，使用者無法將敏感度標籤套用至 Excel 檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-334">We fixed an issue where users were unable to apply sensitivity labels to Excel files when the start screen on app boot was disabled.</span></span>


- <span data-ttu-id="8efa7-335">我們已修正從 OneDrive 同步處理資料夾開啟雲端檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-335">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="outlook"></a><span data-ttu-id="8efa7-336">Outlook</span><span class="sxs-lookup"><span data-stu-id="8efa7-336">Outlook</span></span>

- <span data-ttu-id="8efa7-337">解決在新增或儲存附件時，會導致 Outlook 停止運作的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-337">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="8efa7-338">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8efa7-338">PowerPoint</span></span>

- <span data-ttu-id="8efa7-339">我們已修正一個問題，即在 QAT 中新增的字型大小命令在更新時，會自動完成到最接近的已定義字型大小。</span><span class="sxs-lookup"><span data-stu-id="8efa7-339">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="8efa7-340">修正使用保留來源格式設定選項複製及貼上投影片時，有時會將此設定意外地複製到新的投影片母片的問題</span><span class="sxs-lookup"><span data-stu-id="8efa7-340">Fixed an issue where copy and paste of a slide with 'keep source formatting' option would sometimes copy over a new slide master unexpectedly</span></span>


### <a name="word"></a><span data-ttu-id="8efa7-341">Word</span><span class="sxs-lookup"><span data-stu-id="8efa7-341">Word</span></span>

- <span data-ttu-id="8efa7-342">我們已修正有時開啟 Word 文件可能會顯示錯誤對話方塊的追蹤修訂問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-342">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>


- <span data-ttu-id="8efa7-343">我們已修正從 OneDrive 同步處理資料夾開啟雲端檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-343">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="office-suite"></a><span data-ttu-id="8efa7-344">Office 套件</span><span class="sxs-lookup"><span data-stu-id="8efa7-344">Office Suite</span></span>

- <span data-ttu-id="8efa7-345">修正無法在 Office 中成功開啟檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-345">Fixed an issue that prevented successful open of a file in Office.</span></span>


- <span data-ttu-id="8efa7-346">修正使用複製格式將包含草繪外框的文件套用至連接器可能會損毀的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-346">Fixed an issue where documents containing Sketched outlines applied to connectors via Format Painter could become corrupted.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-january-12"></a><span data-ttu-id="8efa7-348">版本 2008：1 月 12 日</span><span class="sxs-lookup"><span data-stu-id="8efa7-348">Version 2008: January 12</span></span>
<span data-ttu-id="8efa7-349">*版本 2008 (組建 13127.21064)*</span><span class="sxs-lookup"><span data-stu-id="8efa7-349">*Version 2008 (Build 13127.21064)*</span></span>

<span data-ttu-id="8efa7-350">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="8efa7-350">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8efa7-352">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8efa7-352">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="8efa7-353">Excel</span><span class="sxs-lookup"><span data-stu-id="8efa7-353">Excel</span></span>

- <span data-ttu-id="8efa7-354">修正唯讀書籍在開啟時無法再重新整理樞紐分析表資料的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-354">Fixed an issue where read-only books would no longer refresh pivot table data when opened.</span></span>


- <span data-ttu-id="8efa7-355">這項變更提供下列問題的修正程式：從 OneDrive 本機同步處理資料夾插入檔案時，Excel 的 [插入物件] 不會顯示正確的圖示。</span><span class="sxs-lookup"><span data-stu-id="8efa7-355">This change provides a fix for the following issue: Excel "Insert Object" does not show correct icon when inserts a file from OneDrive local sync folder.</span></span>


- <span data-ttu-id="8efa7-356">修正客戶在共同撰寫時會錯誤地得到有關文件新版本通知的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-356">Fixed an issue where customers would incorrectly get notified about a new version of the file when coauthoring.</span></span>


- <span data-ttu-id="8efa7-357">修正即使用 IME 和覆寫模式將錯誤地推進額外的字元的編輯問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-357">Fixed an editing issue where using IME with Overwrite mode would incorrectly advance extra characters.</span></span>


- <span data-ttu-id="8efa7-358">修復了將即時資料與多執行緒 recalc 功能結合使用時出現的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-358">Fixed an issue when using real time data in conjunction with multithreaded recalc functionality.</span></span>


- <span data-ttu-id="8efa7-359">修正當使用特定 Windows 安全性漏洞防護設定(SimExec、CallerCheck) 時，Excel 無法正常啟動或關閉的問題</span><span class="sxs-lookup"><span data-stu-id="8efa7-359">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use</span></span>


### <a name="outlook"></a><span data-ttu-id="8efa7-360">Outlook</span><span class="sxs-lookup"><span data-stu-id="8efa7-360">Outlook</span></span>

- <span data-ttu-id="8efa7-361">我們已修正會導致 SmartLinks 在儲存至草稿時格式遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-361">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


- <span data-ttu-id="8efa7-362">我們已修正讓使用者能在覆寫原則時自訂調整文字的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-362">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


- <span data-ttu-id="8efa7-363">我們已修正會導致中文字元在儲存為 OFT 檔案時變更為問號的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-363">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="8efa7-364">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8efa7-364">PowerPoint</span></span>

- <span data-ttu-id="8efa7-365">我們已修正 Slide.Shapes.AddMediaObject2 會對舊版影片格式 (MPG-1、Mpeg-2) 發生意外關閉的 VBA 問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-365">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 would unexpectedly close with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="8efa7-366">修正無法正確開啟部分損壞的 PowerPoint 檔案 (即使在文件修復之後) 的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-366">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="project"></a><span data-ttu-id="8efa7-367">Project</span><span class="sxs-lookup"><span data-stu-id="8efa7-367">Project</span></span>

- <span data-ttu-id="8efa7-368">我們已修正在開啟以特定方式指定資源分佈的檔案時，Project 可能會意外終止的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-368">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>


### <a name="skype"></a><span data-ttu-id="8efa7-369">Skype</span><span class="sxs-lookup"><span data-stu-id="8efa7-369">Skype</span></span>

- <span data-ttu-id="8efa7-370">修正使用者的 TLS-DSK 憑證不會在預期時間續訂，而只在有效期剩餘不到 12 小時才續訂的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-370">Fixes an issue where a user's TLS-DSK certificate would not renew at the expected time, instead only renewing when less than 12 hours remain on its validity.</span></span>


- <span data-ttu-id="8efa7-371">修正當 Office 尚未獲得授權時，商務用 Skype UI 在登入後顯示為空白的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-371">Fixes an issue where the Skype for Business UI shows as blank after signing in when Office is not yet licensed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="8efa7-372">Office 套件</span><span class="sxs-lookup"><span data-stu-id="8efa7-372">Office Suite</span></span>

- <span data-ttu-id="8efa7-373">此變更解決了與開啟包含舊圖表之檔案相關的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-373">This change addresses an issue related to opening files containing legacy diagrams.</span></span>


- <span data-ttu-id="8efa7-374">此變更解決了 SVG 回復 Proxy 導致存取衝突的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-374">This change addresses an issue with SVG fallback proxy resulting in access violations.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-december-08"></a><span data-ttu-id="8efa7-376">版本2008：12 月 8 日</span><span class="sxs-lookup"><span data-stu-id="8efa7-376">Version 2008: December 08</span></span>
<span data-ttu-id="8efa7-377">*版本 2008 (組建 13127.20910)*</span><span class="sxs-lookup"><span data-stu-id="8efa7-377">*Version 2008 (Build 13127.20910)*</span></span>

<span data-ttu-id="8efa7-378">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="8efa7-378">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8efa7-380">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8efa7-380">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="8efa7-381">Access</span><span class="sxs-lookup"><span data-stu-id="8efa7-381">Access</span></span>

- <span data-ttu-id="8efa7-382">我們已修正嘗試使用 ODBC DSN 建立器時的錯誤問題</span><span class="sxs-lookup"><span data-stu-id="8efa7-382">We fixed an error issue when trying to use ODBC DSN builder</span></span>


### <a name="excel"></a><span data-ttu-id="8efa7-383">Excel</span><span class="sxs-lookup"><span data-stu-id="8efa7-383">Excel</span></span>

- <span data-ttu-id="8efa7-384">修正從 Project 計劃匯出時無法編輯樞紐分析表和無法儲存活頁簿的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-384">Fixed an issue where pivot tables could not be edited and workbooks could not be saved if they were exported from Project plan.</span></span>


- <span data-ttu-id="8efa7-385">我們已修正在某些情况下，以唯讀模式開啟文件時會出現多個訊息列。</span><span class="sxs-lookup"><span data-stu-id="8efa7-385">We fixed an issue where in some cases, multiple message bars were appearing when a file was opened in read-only mode.</span></span>


- <span data-ttu-id="8efa7-386">我們已修正當有許多重複的欄標題值時，大綱子總計可能停止運作的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-386">We fixed an issue where outline sub-totals could stop working when there were many duplicate column header values.</span></span>


- <span data-ttu-id="8efa7-387">我們已修正在多執行緒重新計算期間進行群組原則物件更新 (例如，透過遠端群組原則重新整理) 時，Excel 將停止運作的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-387">We fixed an issue where Excel would stop working when there is a Group Policy Object update (e.g. via Remote Group Policy Refresh) during multithreaded recalc.</span></span>


- <span data-ttu-id="8efa7-388">我們已修正當使用者對超過 255 列使用小計函數時 Excel 將停止運作的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-388">We fixed an issue where Excel would stop working when users use the subtotal function on more than 255 columns.</span></span>


- <span data-ttu-id="8efa7-389">當內容從 Excel 複製並使用 [内嵌] 選項貼上到 PowerPoint 中時，改進了 PowerPoint 中的文字字元間距調整。</span><span class="sxs-lookup"><span data-stu-id="8efa7-389">Improved text kerning in PowerPoint when when content is copied from Excel and pasted into PowerPoint with the Embed option.</span></span>


- <span data-ttu-id="8efa7-390">修正在 PowerPivot 中封鎖從 [資料表預覽] 和 [査詢編輯器] 切換的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-390">Fixed an issue that would prevent switching from Table Preview and the Query Editor in PowerPivot.</span></span>


- <span data-ttu-id="8efa7-391">我們已修正使用者無法直接從 SharePoint 開啟 atomsvc (UTF8+BOM) 檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-391">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="8efa7-392">我們已修正Power Pivot 現在將成功識別定位字元分隔符號的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-392">We fixed an issue where Power Pivot will now successfully recognize tab delimiter.</span></span>


### <a name="outlook"></a><span data-ttu-id="8efa7-393">Outlook</span><span class="sxs-lookup"><span data-stu-id="8efa7-393">Outlook</span></span>

- <span data-ttu-id="8efa7-394">我們已修正在傳送任務狀態報告時導致 [收件人：] 欄位為空的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-394">We fixed an issue that caused the To: field to be empty when sending a status report on a Task.</span></span>


- <span data-ttu-id="8efa7-395">我們已修正會導致 MailItem.BeforeAttachmentAdd 事件中斷的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-395">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="8efa7-396">我們已修正一些問題，導致某些使用者在從 Outlook 以外的應用程式傳送 Outlook 郵件時，遇到應用程式意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-396">We fixed an issue that was causing some users to experience the application to close unexpectedly when sending Outlook mail from applications other than Outlook.</span></span>


- <span data-ttu-id="8efa7-397">我們已修正會導致使用者在線上模式下在資料夾之間移動多個郵件項時效能下降的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-397">We fixed an issue that caused users to experience degraded performance when moving multiple mail items between folders in online mode.</span></span>


- <span data-ttu-id="8efa7-398">我們新增了一個 RegKey，可讓客戶停用 IDataObject 操作 (例如，拖曳拖放、剪貼簿) 中附件的 FileTime 包含。</span><span class="sxs-lookup"><span data-stu-id="8efa7-398">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="8efa7-399">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject  0 = filetimes 被排除  1 = (預設) 事件時間包含在内</span><span class="sxs-lookup"><span data-stu-id="8efa7-399">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject  0 = filetimes are excluded  1 = (default) filetimes are included</span></span>


- <span data-ttu-id="8efa7-400">我們已修正當回復含有「Azure 資訊保護」保護標籤的郵件時，會導致內嵌影像消失的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-400">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


- <span data-ttu-id="8efa7-401">我們已修正會導致在傳送受 Azure 保護的語音信箱時用戶名顯示為電話號碼，從而導致傳統型 Outlook 使用者無法開啟來自外部使用者的語音信箱。</span><span class="sxs-lookup"><span data-stu-id="8efa7-401">We fixed an issue that caused the user name to be displayed as a phone number when sending an Azure Protected Voicemail, causing Outlook Desktop users to be unable to open voicemails from external users.</span></span>


- <span data-ttu-id="8efa7-402">我們已修正一個問題，即設定 OME 設定時在郵件項目上新增無關的附件，這會迫使 Outlook 加密郵件，即使在服務端設定了DecryptAttachmentsFontryptOnly 選項。</span><span class="sxs-lookup"><span data-stu-id="8efa7-402">We fixed an issue where setting up OME Configuration was adding an extraneous attachments on the mail item which was forcing Outlook to Encrypt the message even though the DecryptAttachmentsForEncryptOnly option was setup on the service side.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="8efa7-403">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8efa7-403">PowerPoint</span></span>

- <span data-ttu-id="8efa7-404">我們已修正當使用者將來源路徑變更為本機 OneDrive 資料夾時，連結的 Excel 圖表不正確變更為 Excel 工作表的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-404">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


- <span data-ttu-id="8efa7-405">我們已修正會導致「歡迎回來」的問題！</span><span class="sxs-lookup"><span data-stu-id="8efa7-405">We fixed an issue due to which the feature ‘Welcome back!</span></span> <span data-ttu-id="8efa7-406">「從先前離開的地方開始」在 PowerPoint 裏不起作用。</span><span class="sxs-lookup"><span data-stu-id="8efa7-406">Pick up where you left off in the office' was not working in the PowerPoint .</span></span>


### <a name="visio"></a><span data-ttu-id="8efa7-407">Visio</span><span class="sxs-lookup"><span data-stu-id="8efa7-407">Visio</span></span>

- <span data-ttu-id="8efa7-408">修正使用者將可在自訂 Visio 樣板和內建範本中使用適用於 Office 365 的 Visio 連接器建立直線的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-408">We fixed an issue where users will be able to create straight lines using connectors in Visio for Office 365 for both custom Visio stencils and in-built templates.</span></span>


### <a name="word"></a><span data-ttu-id="8efa7-409">Word</span><span class="sxs-lookup"><span data-stu-id="8efa7-409">Word</span></span>

- <span data-ttu-id="8efa7-410">我們已修正將文件儲存成 HTML 格式時，長連結無法換行的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-410">We fixed an issue where long links were not being wrapped when saving document to HTML format.</span></span>


- <span data-ttu-id="8efa7-411">我們已修正問題：如果您回復的父級註解在副檔名清單中有未知的副檔名，那麼回復將得到相同的副檔名。</span><span class="sxs-lookup"><span data-stu-id="8efa7-411">We fixed an issue where if you reply to a parent comment that has unknown extensions in an extension list, the reply will get those same extensions.</span></span>


- <span data-ttu-id="8efa7-412">我們已修正 Outlook 有關將郵件設定為 [不要轉寄] 的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-412">We fixed an issue with Outlook with message set to Do not forward.</span></span>


### <a name="office-suite"></a><span data-ttu-id="8efa7-413">Office 套件</span><span class="sxs-lookup"><span data-stu-id="8efa7-413">Office Suite</span></span>

- <span data-ttu-id="8efa7-414">解決已停用 ADAL 時，使用者無法匯入 SPO 清單的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-414">Addresses an issue that prevented users from importing SPO Lists when ADAL was disabled.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-november-10"></a><span data-ttu-id="8efa7-416">版本 2008：11 月 10 日</span><span class="sxs-lookup"><span data-stu-id="8efa7-416">Version 2008: November 10</span></span>
<span data-ttu-id="8efa7-417">*版本 2008 (組建 13127.20760)*</span><span class="sxs-lookup"><span data-stu-id="8efa7-417">*Version 2008 (Build 13127.20760)*</span></span>

<span data-ttu-id="8efa7-418">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="8efa7-418">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8efa7-420">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8efa7-420">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="8efa7-421">Excel</span><span class="sxs-lookup"><span data-stu-id="8efa7-421">Excel</span></span>

- <span data-ttu-id="8efa7-422">我們已修正載入活頁簿之後特定功能可能會發生錯誤結果的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-422">We fixed an issue where certain functions would have an incorrect result after loading a workbook.</span></span>


- <span data-ttu-id="8efa7-423">我們已修正應用程式意外終止 (與 XLAM 增益集參照和命名範圍相關的問題) 的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-423">We fixed an issue where the application would terminate unexpectedly which was related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="8efa7-424">我們已修正使用巨集來設定某個範圍的 FormulaR1C1 屬性時，如果圖表工作表為作用中工作表，則儲存格參考會不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-424">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>


- <span data-ttu-id="8efa7-425">修正可能會導致「嘗試計算一個或多個公式時，Excel 資源不足」錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-425">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="8efa7-426">修正當 Office 語言設定為西班牙文時，其中資料驗證清單可能無法顯示清單中所有項目的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-426">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="8efa7-427">我們已修正在重新整理 OLAP 樞紐分析表時，可能會導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-427">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>

### <a name="outlook"></a><span data-ttu-id="8efa7-428">Outlook</span><span class="sxs-lookup"><span data-stu-id="8efa7-428">Outlook</span></span>

- <span data-ttu-id="8efa7-429">我們已修正一個問題，使用者現在可以停用 Outlook 的 IRM (資訊版權管理)，而不需要為其餘 Office 應用程式停用它。</span><span class="sxs-lookup"><span data-stu-id="8efa7-429">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>


- <span data-ttu-id="8efa7-430">我們已修正會導致使用者無法將 [編輯器] 權限授與代理人的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-430">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="8efa7-431">我們已修正會導致使用者在選取搜尋結果時遇到意外終止的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-431">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="8efa7-432">我們已修正會導致群組行事曆中的搜尋無法傳回任何結果的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-432">We fixed an issue that caused searches in Group calendars fail to return any results.</span></span>


- <span data-ttu-id="8efa7-433">已解決導致代理人在開啟另一個信箱中的共用資料夾時出現錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-433">Addressed an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


- <span data-ttu-id="8efa7-434">已解決當主旨行空白時，會導致傳送的自動產生電子郵件含有空白內文的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-434">Addressed an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


- <span data-ttu-id="8efa7-435">我們已修正在回覆或轉寄時，導致中文郵件標題出現亂碼的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-435">We fixed an issue that caused the headers of Chinese messages to get garbled when replying or forwarding.</span></span>

- <span data-ttu-id="8efa7-436">我們已修正選用連線體驗導致網頁增益集無法載入的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-436">We fixed an issue where optional connected experiences blocked web add-ins from loading.</span></span>  <br /><span data-ttu-id="8efa7-437">在[部落格文章](https://developer.microsoft.com/zh-TW/office/blogs/outlook-add-ins-and-optional-connected-experiences/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8efa7-437">See details in [blog post](https://developer.microsoft.com/zh-TW/office/blogs/outlook-add-ins-and-optional-connected-experiences/)</span></span>


### <a name="powerpoint"></a><span data-ttu-id="8efa7-438">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8efa7-438">PowerPoint</span></span>

- <span data-ttu-id="8efa7-439">我們已修正 Forms 內容增益集在插入之後不會呈現，除非使用者按一下另一張投影片讓它顯示才會呈現的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-439">We have fixed an issue where Forms content add-in doesn't render after insertion until user click to another slide to make it show.</span></span>


### <a name="office-suite"></a><span data-ttu-id="8efa7-440">Office 套件</span><span class="sxs-lookup"><span data-stu-id="8efa7-440">Office Suite</span></span>

- <span data-ttu-id="8efa7-441">已解決針對使用 System Center Configuration Manager 或其他管理工具來使用 Microsoft 365 Endpoint 資料外洩防護進行 Office Update 的商業客戶的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-441">Addressed an issue for commercial customers who leverage System Center Configuration Manager or other management tool for the Office Update using Microsoft 365 Endpoint data loss prevention.</span></span>

- <span data-ttu-id="8efa7-442">修正 Office 增益集的傳訊 API 無法正常運作的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-442">Fix an issue that the Messaging API for Office Add-ins is not working.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-october-13"></a><span data-ttu-id="8efa7-444">版本 2008：10 月 13 日</span><span class="sxs-lookup"><span data-stu-id="8efa7-444">Version 2008: October 13</span></span>
<span data-ttu-id="8efa7-445">*版本 2008 (組建 13127.20638)*</span><span class="sxs-lookup"><span data-stu-id="8efa7-445">*Version 2008 (Build 13127.20638)*</span></span>

<span data-ttu-id="8efa7-446">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="8efa7-446">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8efa7-448">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8efa7-448">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="8efa7-449">Excel</span><span class="sxs-lookup"><span data-stu-id="8efa7-449">Excel</span></span>

- <span data-ttu-id="8efa7-450">修正 PivotDateFilter API 中的錯誤，其中的 'Before' 和 'After' 篩選條件是相反的。</span><span class="sxs-lookup"><span data-stu-id="8efa7-450">Fixed a bug with PivotDateFilter APIs in which 'Before' and 'After' filter conditions were reversed.</span></span>


- <span data-ttu-id="8efa7-451">我們已修正使用者無法修改樞紐分析表篩選的問題，因為它已設定為Analysis Services數據庫中不再存在的值。</span><span class="sxs-lookup"><span data-stu-id="8efa7-451">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


- <span data-ttu-id="8efa7-452">修正當凍結工作表頂端列之後，Excel 可能會在使用 [快速分析] 時當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-452">Fixed an issue where Excel could crash when using the Quick Analysis after freezing the top row of the sheet.</span></span>


- <span data-ttu-id="8efa7-453">修正當活頁簿包含使用 IFNA () 的公式時，可能會造成錯誤活頁簿的警告之問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-453">Fixed an issue that could cause a warning about a corrupt workbook if it contained formulas using IFNA().</span></span>


### <a name="outlook"></a><span data-ttu-id="8efa7-454">Outlook</span><span class="sxs-lookup"><span data-stu-id="8efa7-454">Outlook</span></span>

- <span data-ttu-id="8efa7-455">解決由於按一下角落中的 [X] 而導致使用者無法關閉共用行事曆的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-455">Addresses an issue that caused users to be unable to close shared calendars by clicking on the "X" in the corner.</span></span>


- <span data-ttu-id="8efa7-456">解決會導致 [開啟共用行事曆改良] 設定有時候無法套用至現有共用行事曆的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-456">Addresses an issue that caused the "Turn on shared calendar improvements" setting to sometimes fail to apply to existing shared calendars.</span></span>


- <span data-ttu-id="8efa7-457">解決使用者嘗試開啟雲端附件時，會導致使用者在 safelinks 頁面上看到錯誤，而非所嘗試開啟文件的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-457">Addresses an issue that caused users to see an error on the safelinks page instead of the document they were trying to open when opening a cloud attachment.</span></span>


- <span data-ttu-id="8efa7-458">解決附件上傳的效能問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-458">Addresses a performance issue with attachment upload.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="8efa7-459">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8efa7-459">PowerPoint</span></span>

- <span data-ttu-id="8efa7-460">此變更可解決「匯出為動畫 GIF」功能的問題，其中按一下 [匯出] 按鈕不會匯出。</span><span class="sxs-lookup"><span data-stu-id="8efa7-460">This change addresses an issue with Export to Animated GIF feature where clicking on Export button was not exporting.</span></span>


- <span data-ttu-id="8efa7-461">安全性修正程式可解決在 [受保護的檢視] 中開啟 PowerPoint 檔案時會停用 IRM 保護的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-461">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>

- <span data-ttu-id="8efa7-462">我們已修正在 PowerPoint 應用程式中 [動作設定] 對話方塊導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-462">We have fixed an issue in Action Settings dialog which was causing a crash in PowerPoint app.</span></span>

### <a name="visio"></a><span data-ttu-id="8efa7-463">Visio</span><span class="sxs-lookup"><span data-stu-id="8efa7-463">Visio</span></span>

- <span data-ttu-id="8efa7-464">我們已修正會導致即時預覽在文字對齊時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-464">We fixed an issue that caused the Live preview to crash on text alignment.</span></span>


### <a name="word"></a><span data-ttu-id="8efa7-465">Word</span><span class="sxs-lookup"><span data-stu-id="8efa7-465">Word</span></span>

- <span data-ttu-id="8efa7-466">解決會導致使用者在開啟某些非常大型電子郵件時會遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-466">Fixes an issue that caused users to experience a crash when opening certain very large emails.</span></span>


- <span data-ttu-id="8efa7-467">我們已修正使用者開啟文件時可能會遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-467">We fixed an issue which user might experience crash when opening a document.</span></span>


- <span data-ttu-id="8efa7-468">解決 Word 啟動時會導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-468">Resolved an issue that may have caused a crash when booting Word.</span></span>


- <span data-ttu-id="8efa7-469">我們已修正 [樣式圖庫] 對話方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-469">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="8efa7-470">Office 套件</span><span class="sxs-lookup"><span data-stu-id="8efa7-470">Office Suite</span></span>

- <span data-ttu-id="8efa7-471">當使用者從 Office 噴墨印表機上列印任何文件/檔案且列印機墨水不足時，即使噴墨印表機沒有碳粉，也會顯示「碳粉不足」或「無碳粉」消息。</span><span class="sxs-lookup"><span data-stu-id="8efa7-471">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="8efa7-472">將訊息變更為顯示「碳粉/墨水不足」和「沒有碳粉/墨水」。</span><span class="sxs-lookup"><span data-stu-id="8efa7-472">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


- <span data-ttu-id="8efa7-473">修正使用 GIF/動畫 model3D 閒置時的高 CPU 使用量</span><span class="sxs-lookup"><span data-stu-id="8efa7-473">Fixes high CPU usage on idle with GIF/animated model3D</span></span>


- <span data-ttu-id="8efa7-474">此變更可解決啟動 Office 應用程式時由於無法載入 d2d1.dll 而產生的當機。</span><span class="sxs-lookup"><span data-stu-id="8efa7-474">This change addresses a crash when launching Office apps due to failing to load d2d1.dll.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-september-08"></a><span data-ttu-id="8efa7-476">版本2008：9月 8 日</span><span class="sxs-lookup"><span data-stu-id="8efa7-476">Version 2008: September 08</span></span>
<span data-ttu-id="8efa7-477">*版本 2008 (組建 13127.20408)*</span><span class="sxs-lookup"><span data-stu-id="8efa7-477">*Version 2008 (Build 13127.20408)*</span></span>

<span data-ttu-id="8efa7-478">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="8efa7-478">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="8efa7-480">功能更新</span><span class="sxs-lookup"><span data-stu-id="8efa7-480">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="8efa7-481">Access</span><span class="sxs-lookup"><span data-stu-id="8efa7-481">Access</span></span>

- <span data-ttu-id="8efa7-482">**在查詢設計工具、SQL 檢視和關聯視窗中工作時更具生產力：** 在資料表上按一下滑鼠右鍵即可開啟、設計、調整大小及隱藏它。</span><span class="sxs-lookup"><span data-stu-id="8efa7-482">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="8efa7-483">在 SQL 檢視中搜尋及取代文字。</span><span class="sxs-lookup"><span data-stu-id="8efa7-483">Search and replace text in SQL View.</span></span> <span data-ttu-id="8efa7-484">在 [關聯圖] 視窗中選取多個資料表。</span><span class="sxs-lookup"><span data-stu-id="8efa7-484">Select multiple tables in the Relationships window.</span></span>

- <span data-ttu-id="8efa7-485">**按幾下就能新增資料表：** 使用 [新增資料表] 工作窗格，當您工作時，該窗格會保持開啟狀態，以便將資料表新增至關聯和查詢。</span><span class="sxs-lookup"><span data-stu-id="8efa7-485">**Add tables with fewer clicks:** Use the Add Tables task pane, which stays open while you work, to add tables to relationships and queries.</span></span> [<span data-ttu-id="8efa7-486">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-486">Learn more</span></span>](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)

### <a name="excel"></a><span data-ttu-id="8efa7-487">Excel</span><span class="sxs-lookup"><span data-stu-id="8efa7-487">Excel</span></span>

- <span data-ttu-id="8efa7-488">**改善地圖圖表：** 我們讓地圖圖表變得更好，方法是將地圖圖表與可顯示有關對應位置豐富資訊的 Excel 地理資料類型整合。</span><span class="sxs-lookup"><span data-stu-id="8efa7-488">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="8efa7-489">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-489">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="8efa7-490">**挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。</span><span class="sxs-lookup"><span data-stu-id="8efa7-490">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="8efa7-491">在[部落格文章](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8efa7-491">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="8efa7-492">**在 Excel 中建立來自 Power BI 資料的樞紐分析表：** 您可以在 Excel 中建立樞紐分析表，只要按幾下滑鼠，就能連線到儲存在 Power BI 的樞紐分析表。</span><span class="sxs-lookup"><span data-stu-id="8efa7-492">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="8efa7-493"> 如此一來，您就能獲得樞紐分析表和 Power BI 的最佳效果。</span><span class="sxs-lookup"><span data-stu-id="8efa7-493">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="8efa7-494">使用安全 Power BI 資料集的樞紐分析表以計算、摘要及分析資料。</span><span class="sxs-lookup"><span data-stu-id="8efa7-494">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="8efa7-495">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-495">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)<br /><span data-ttu-id="8efa7-496">在[部落格文章](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8efa7-496">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

- <span data-ttu-id="8efa7-497">**您最愛的 Excel 函數計算速度提升了：** SUMIFS、AVERAGEIFS、COUNTIFS、MAXIFS 和 MINIFS 函數現在比以往更快了。</span><span class="sxs-lookup"><span data-stu-id="8efa7-497">**Your favorite Excel functions just got faster:** The SUMIFS, AVERAGEIFS, COUNTIFS, MAXIFS, and MINIFS functions are much faster than ever before.</span></span> <span data-ttu-id="8efa7-498">更快速地前往底線。</span><span class="sxs-lookup"><span data-stu-id="8efa7-498">Get to the bottom line more quickly.</span></span> <span data-ttu-id="8efa7-499">立即試用。</span><span class="sxs-lookup"><span data-stu-id="8efa7-499">Try one now.</span></span>

- <span data-ttu-id="8efa7-500">**RealTimeData (RTD) 的改進** 在 Office 365 版本 2002 的每月通道或更新版本中，Excel RealTimeData (RTD) 函數速度快于 Excel 2010 計算試算表中的資料。</span><span class="sxs-lookup"><span data-stu-id="8efa7-500">**Realtimedata (RTD) improvements:** In Office 365 version 2002 monthly channel and later, Excel's RealTimeData (RTD) function is much faster than Excel 2010 calculating data in the spreadsheet.</span></span> <span data-ttu-id="8efa7-501">我們在其基礎記憶體和資料結構中移除了瓶頸，並使其成為安全執行緒，讓它可在多執行緒重新計算 (MTR) 的所有可用執行緒上計算。</span><span class="sxs-lookup"><span data-stu-id="8efa7-501">We removed bottlenecks in its underlying memory and data structures as well as made it thread-safe to allow  it to be calculated on all available threads of Multithreaded recalculation (MTR).</span></span>

### <a name="outlook"></a><span data-ttu-id="8efa7-502">Outlook</span><span class="sxs-lookup"><span data-stu-id="8efa7-502">Outlook</span></span>

- <span data-ttu-id="8efa7-503">**共用行事曆更新的速度更快：** 針對 Office 365 中的共用行事曆，Outlook 可以使用 REST API 更新這些行事曆。</span><span class="sxs-lookup"><span data-stu-id="8efa7-503">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="8efa7-504">開啟預覽以更快且更可靠地更新共用行事曆。</span><span class="sxs-lookup"><span data-stu-id="8efa7-504">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

- <span data-ttu-id="8efa7-505">**更好的結果—瞬間：** 我們更新了搜尋體驗，讓這個版本比以往更聰明、更快速，且更可靠。</span><span class="sxs-lookup"><span data-stu-id="8efa7-505">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="8efa7-506">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-506">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="8efa7-507">**挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。</span><span class="sxs-lookup"><span data-stu-id="8efa7-507">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="8efa7-508">在[部落格文章](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8efa7-508">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="8efa7-509">**將電子郵件拖曳到您擁有的群組：** 從您的 [收件匣] 拖曳郵件和交談以將它們移動和複製。</span><span class="sxs-lookup"><span data-stu-id="8efa7-509">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="8efa7-510">您拖曳的郵件將會與所有群組成員共用。</span><span class="sxs-lookup"><span data-stu-id="8efa7-510">Messages you drag will be shared with all group members.</span></span><br /><span data-ttu-id="8efa7-511">在[部落格文章](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8efa7-511">See details in [blog post](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span></span>

- <span data-ttu-id="8efa7-512">**行事曆煥然一新：** 查看視覺更新，讓您的行事曆更容易流覽。</span><span class="sxs-lookup"><span data-stu-id="8efa7-512">**Calendar gets a makeover:** See visual updates that make your calendar easier to scan.</span></span> [<span data-ttu-id="8efa7-513">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-513">Learn more</span></span>](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br /><span data-ttu-id="8efa7-514">在[部落格文章](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8efa7-514">See details in [blog post](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span></span>

- <span data-ttu-id="8efa7-515">**加入會議而不需離開您的收件匣：** 不需切換至您的行事曆即可加入線上會議。</span><span class="sxs-lookup"><span data-stu-id="8efa7-515">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="8efa7-516">將行事曆釘選到 [待辦事項] 窗格之後，只要按一下就能加入任何會議。</span><span class="sxs-lookup"><span data-stu-id="8efa7-516">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span> [<span data-ttu-id="8efa7-517">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-517">Learn more</span></span>](https://support.office.com/article/d8baa9d5-0645-41b8-9f36-b498a6c36064 )

- <span data-ttu-id="8efa7-518">**受限 WiFi 網路的新體驗：** 是否曾經加入需要登入網頁的 WiFi 網路呢？</span><span class="sxs-lookup"><span data-stu-id="8efa7-518">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="8efa7-519">Outlook 現在會偵測這項要求並協助您取得連結。</span><span class="sxs-lookup"><span data-stu-id="8efa7-519">Outlook now detects this and helps you get connected.</span></span><br /><span data-ttu-id="8efa7-520">在[部落格文章](https://insider.office.com/zh-TW/blog/outlook-on-public-wi-fi-networks-just-got-easier)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8efa7-520">See details in [blog post](https://insider.office.com/zh-TW/blog/outlook-on-public-wi-fi-networks-just-got-easier)</span></span>

- <span data-ttu-id="8efa7-521">**搜尋人員時取得電子郵件建議：** 當您在 [搜尋] 方塊中輸入人員的名稱時，最相關的電子郵件訊息會包括在您的搜尋建議中。</span><span class="sxs-lookup"><span data-stu-id="8efa7-521">**Get email suggestions when you search for a person:** When you type a person’s name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span> [<span data-ttu-id="8efa7-522">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-522">Learn more</span></span>](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

### <a name="powerpoint"></a><span data-ttu-id="8efa7-523">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8efa7-523">PowerPoint</span></span>

- <span data-ttu-id="8efa7-524">**使用 \@提及取得他人注意：** 在註解中使用 @提及功能，讓同事知道您需要他們提供建議。</span><span class="sxs-lookup"><span data-stu-id="8efa7-524">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="8efa7-525">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-525">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="8efa7-526">**改善地圖圖表：** 我們讓地圖圖表變得更好，方法是將地圖圖表與可顯示有關對應位置豐富資訊的 Excel 地理資料類型整合。</span><span class="sxs-lookup"><span data-stu-id="8efa7-526">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="8efa7-527">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-527">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="8efa7-528">**jiffy 中的 Gif：** 一個投影片、一個圖文框。</span><span class="sxs-lookup"><span data-stu-id="8efa7-528">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="8efa7-529">在 PowerPoint 中輕鬆建立迴圈 Gif。</span><span class="sxs-lookup"><span data-stu-id="8efa7-529">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="8efa7-530">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-530">Learn more</span></span>](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)<br /><span data-ttu-id="8efa7-531">在[部落格文章](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8efa7-531">See details in [blog post](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span></span>

- <span data-ttu-id="8efa7-532">**更好的圖表：** 使用更完善的連接線和更平滑的筆跡轉換程式，您可以自信地用筆跡繪製您的想法。</span><span class="sxs-lookup"><span data-stu-id="8efa7-532">**Better diagrams:** With better connectors and a smoother ink conversion process you can ink your ideas more confidently.</span></span> [<span data-ttu-id="8efa7-533">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-533">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="8efa7-534">**挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。</span><span class="sxs-lookup"><span data-stu-id="8efa7-534">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="8efa7-535">在[部落格文章](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8efa7-535">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="8efa7-536">**註解：** PowerPoint 中新增的註解體驗可讓您快速輕鬆地探索文件並新增註解。</span><span class="sxs-lookup"><span data-stu-id="8efa7-536">**Comments:** The new commenting experience in PowerPoint allows you to quickly and easily discover and add comments to your documents.</span></span> <span data-ttu-id="8efa7-537">使用註解錨定、解析、任務、已改進的提及通知等新功能使您的共同作業工作流程現代化。</span><span class="sxs-lookup"><span data-stu-id="8efa7-537">Modernize your collaboration workflows with new features like comment anchoring, resolve, tasks, improved mention notifications, and much more.</span></span> [<span data-ttu-id="8efa7-538">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-538">Learn more</span></span>](https://support.office.com/article/c0aa37bb-82cb-414c-872d-178946ff60ec)

- <span data-ttu-id="8efa7-539">**在簡報時同步處理變更：** 即使簡報處於投影片放映模式，仍可即時同步處理所做的變更。</span><span class="sxs-lookup"><span data-stu-id="8efa7-539">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span> [<span data-ttu-id="8efa7-540">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-540">Learn more</span></span>](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br /><span data-ttu-id="8efa7-541">在[部落格文章](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8efa7-541">See details in [blog post](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span></span>

- <span data-ttu-id="8efa7-542">**投影片連結:** 要求同事參與製作您的投影片組，讓他們直接在您需要協助的投影片上開始進行。</span><span class="sxs-lookup"><span data-stu-id="8efa7-542">**Link to a slide:** Ask a colleague to contribute to your slide deck, and start them directly on the slide you need help with.</span></span> [<span data-ttu-id="8efa7-543">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-543">Learn more</span></span>](https://support.office.com/article/4f5f3d5e-1674-4742-8cf1-9623050c19ef)<br /><span data-ttu-id="8efa7-544">在[部落格文章](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8efa7-544">See details in [blog post](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)</span></span>

- <span data-ttu-id="8efa7-545">**改善的 PowerPoint 中的 Steam 影片效能：** 我們改善了 Microsoft Stream 影片的播放效能，將影片載入時間減至最少，以建立出流暢的觀賞體驗。</span><span class="sxs-lookup"><span data-stu-id="8efa7-545">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="8efa7-546">您可以使用 Microsoft Stream 上您的公司影片來建立更完善的簡報。</span><span class="sxs-lookup"><span data-stu-id="8efa7-546">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>


### <a name="word"></a><span data-ttu-id="8efa7-547">Word</span><span class="sxs-lookup"><span data-stu-id="8efa7-547">Word</span></span>

- <span data-ttu-id="8efa7-548">**改善地圖圖表：** 我們讓地圖圖表變得更好，方法是將地圖圖表與可顯示有關對應位置豐富資訊的 Excel 地理資料類型整合。</span><span class="sxs-lookup"><span data-stu-id="8efa7-548">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="8efa7-549">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-549">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="8efa7-550">**對筆跡使用套索：**[繪圖] 索引標籤上的 [套索] 工具，可協助您選取使用筆跡繪製的物件。</span><span class="sxs-lookup"><span data-stu-id="8efa7-550">**Lasso your ink:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="8efa7-551">選取個別筆劃或整個字。</span><span class="sxs-lookup"><span data-stu-id="8efa7-551">Select individual strokes, or whole words.</span></span> [<span data-ttu-id="8efa7-552">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-552">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="8efa7-553">**挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。</span><span class="sxs-lookup"><span data-stu-id="8efa7-553">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="8efa7-554">在[部落格文章](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8efa7-554">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="8efa7-555">**螢幕閱讀器的動作確認：** 確認動作是重要的協助工具要求。</span><span class="sxs-lookup"><span data-stu-id="8efa7-555">**Confirmation of action in screen readers:** Confirmation of action is an important accessibility requirement.</span></span> <span data-ttu-id="8efa7-556">隨著 Windows 引入新的通知 API 之後，我們現在就能通知螢幕助讀程式使用者的動作成功。</span><span class="sxs-lookup"><span data-stu-id="8efa7-556">With the introduction of a new Notification API from Windows, we are now able to alert screen reader users about the success of their actions.</span></span> <span data-ttu-id="8efa7-557">[剪下]、[複製]、[貼上]、[粗體]、[畫底線]、[復原]、[重做]、[自動校正] 和 [自動大小寫] 等功能都已公布給 Win32 Word 的朗讀程式使用者。</span><span class="sxs-lookup"><span data-stu-id="8efa7-557">Cut, copy, paste, bold, italic, underline, undo, redo, auto corrections, and auto-capitalizations are now all announced to Narrator users in Win32 Word.</span></span> <span data-ttu-id="8efa7-558">若要啟用此功能，請按 windows + ctrl + enter 以開啟朗讀程式。</span><span class="sxs-lookup"><span data-stu-id="8efa7-558">To enable this feature, turn on Narrator by pressing windows + ctrl + enter.</span></span><br /><span data-ttu-id="8efa7-559">在[部落格文章](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="8efa7-559">See details in [blog post](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)</span></span>

### <a name="office-suite"></a><span data-ttu-id="8efa7-560">Office 套件</span><span class="sxs-lookup"><span data-stu-id="8efa7-560">Office Suite</span></span>

- <span data-ttu-id="8efa7-561">**敏感度標籤**：您現在可以套用組織設定、用來提示您輸入自訂權限的敏感度標籤。</span><span class="sxs-lookup"><span data-stu-id="8efa7-561">**Sensitivity labels:** You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8efa7-564">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8efa7-564">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="8efa7-565">Access</span><span class="sxs-lookup"><span data-stu-id="8efa7-565">Access</span></span>

- <span data-ttu-id="8efa7-566">解決插入含有身分識別 (例如，自動編號) 欄位的連結 SQL 資料表的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-566">Resolved an issue with inserting linked SQL tables that include an identity (e.g. autonumber) field.</span></span>

- <span data-ttu-id="8efa7-567">我們已修正執行查詢的時間大約比預期完成時間兩倍久的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-567">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

- <span data-ttu-id="8efa7-568">修正問題；您應該可以呼叫日期/時間延伸資料類型至您的程式碼，而不會在您的應用程式中遇到任何當機。</span><span class="sxs-lookup"><span data-stu-id="8efa7-568">Fixed an issue to be able to call the Date/Time Extended data type into your code without experiencing any crash in your app.</span></span>

- <span data-ttu-id="8efa7-569">修正問題；您現在可以還原為最新的 Access 版本，並使用 DAO/VBA 來管理及編輯十進位資料類型。</span><span class="sxs-lookup"><span data-stu-id="8efa7-569">Fixed an issue so you can now revert back to your most updated Access version, and use DAO/VBA to manage and edit a decimal data type.</span></span>

- <span data-ttu-id="8efa7-570">此修正會解決嘗試執行之前會產生「查詢太複雜」錯誤訊息的特定查詢的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-570">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>

- <span data-ttu-id="8efa7-571">存取已經修正了目前的問題，但將調查我們的其他介面，以確保這個問題不會持續存在。</span><span class="sxs-lookup"><span data-stu-id="8efa7-571">Access has fixed this current issue, but will be investigating our additional interfaces to ensure that this problem does not persist.</span></span> <span data-ttu-id="8efa7-572">小組會通知您未來的更新；我們感謝您的耐心等待。</span><span class="sxs-lookup"><span data-stu-id="8efa7-572">The team will inform you with future updates; we appreciate your patience.</span></span>

- <span data-ttu-id="8efa7-573">已解决此問題 - 您現在可以使用 Office 的隨選即用應用程式外的 ODBC 驅動程式。</span><span class="sxs-lookup"><span data-stu-id="8efa7-573">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>

### <a name="excel"></a><span data-ttu-id="8efa7-574">Excel</span><span class="sxs-lookup"><span data-stu-id="8efa7-574">Excel</span></span>

- <span data-ttu-id="8efa7-575">自動文件分類可能已對處於唯讀模式的活頁簿發生。</span><span class="sxs-lookup"><span data-stu-id="8efa7-575">Automatic document classification may have occurred for workbooks that were in read-only mode.</span></span>

- <span data-ttu-id="8efa7-576">修正若您已從帳戶登出，嘗試建立資料連線時，可能會發生的當機問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-576">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

- <span data-ttu-id="8efa7-577">解決了嘗試將樞紐分析表插入圖表時 Excel 可能會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-577">Addressed an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

- <span data-ttu-id="8efa7-578">嘗試使用 LET() 函數儲存含有公式的檔案時發生錯誤。</span><span class="sxs-lookup"><span data-stu-id="8efa7-578">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>

- <span data-ttu-id="8efa7-579">修正使用 [複製格式] 時，某些情況下，Excel 可能會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-579">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>

- <span data-ttu-id="8efa7-580">修正當儲存至 SharePoint/OneDrive 時，會導致自訂功能區索引標籤 CustomUI XML 的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-580">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="8efa7-581">修正當 Excel 視窗透過 Teams 共用時，使用 Ctrl + Shift + 方向鍵滑動後，Excel 可能會無法回應的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-581">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="8efa7-582">修正在某些情況下，按一下同一個活頁簿中某個位置的超連結會導致活頁簿被隱藏的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-582">Fixed an issue where in some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>

- <span data-ttu-id="8efa7-583">修正當檔案路徑太長時，在檔案重新開啟之後外部連結會停止運作的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-583">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="8efa7-584">在某些情況下，Application.Evaluate (VBA) 無法在使用者定義的函數中運作。</span><span class="sxs-lookup"><span data-stu-id="8efa7-584">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="8efa7-585">在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。</span><span class="sxs-lookup"><span data-stu-id="8efa7-585">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="8efa7-586">修正在複製含有樞紐分析表的工作表後，會於某些情況下導致 Excel 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-586">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="8efa7-587">這解決了舊版 Office 中 SQL 資料提供者建立的連結設定內部表格内容與 Office 365 不同的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-587">This addresses an issue where connections created by the SQL data provider in older versions of Office would set internal table properties differently from Office 365.</span></span> <span data-ttu-id="8efa7-588">這導致在舊版 Office 中使用 Office 365 開啟文件時，這些檔案的 [表格預覽/查詢編輯器] 下拉清單被停用。</span><span class="sxs-lookup"><span data-stu-id="8efa7-588">This caused the Table Preview / Query Editor dropdown to be disabled for files with connections created in older versions of Office when they were opened using Office 365.</span></span>

- <span data-ttu-id="8efa7-589">解決當來源活頁簿關閉時，外部連結無法在填入時更新的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-589">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

- <span data-ttu-id="8efa7-590">修正筆跡會導致 Excel 無法回應的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-590">Resolved an issue where inking could cause Excel to become unresponsive.</span></span>

### <a name="onenote"></a><span data-ttu-id="8efa7-591">OneNote</span><span class="sxs-lookup"><span data-stu-id="8efa7-591">OneNote</span></span>

- <span data-ttu-id="8efa7-592">透過在資訊列中通知使用者有關 Microsoft OneNote 中的暫時調整之資訊，將協助改善在全球高使用量期間的同步處理與服務可用性。</span><span class="sxs-lookup"><span data-stu-id="8efa7-592">Inform users through the InfoBar about temporary adjustments in Microsoft OneNote that will help improve sync and service availability during high worldwide usage.</span></span>

- <span data-ttu-id="8efa7-593">透過暫時調整 OneNote 2016 中的同步處理頻率，來改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="8efa7-593">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="8efa7-594">改善了共同撰寫狀態的偵測，以降低資源利用率。</span><span class="sxs-lookup"><span data-stu-id="8efa7-594">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="8efa7-595">透過暫時將 OneNote 2016 中新嵌入附件的最大允許大小減少為 50MB，來改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="8efa7-595">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="8efa7-596">對於超過此限制的檔案，使用者可以選擇將檔案上傳到 OneDrive，並將連結插入 OneNote。</span><span class="sxs-lookup"><span data-stu-id="8efa7-596">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="8efa7-597">透過暫時停用 OneNote 2016 中的應用程式內視訊錄製，來改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="8efa7-597">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="8efa7-598">本機筆記本不受這個值的影響。</span><span class="sxs-lookup"><span data-stu-id="8efa7-598">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="8efa7-599">透過暫時變更建立頁面版本歷程記錄的頻率，可改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="8efa7-599">Improved sync and service stability by temporarily altering how frequently page version histories are created.</span></span>

- <span data-ttu-id="8efa7-600">透過暫時停用將頁面移動至資源回收桶，來改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="8efa7-600">Improved sync and service stability by temporarily disabling moving pages into the recycle bin.</span></span> <span data-ttu-id="8efa7-601">若使用者想要刪除頁面，則會改為顯示詢問是否要永久刪除頁面的對話方塊。</span><span class="sxs-lookup"><span data-stu-id="8efa7-601">Users who want to delete a page will instead be shown a dialog asking if they'd want to permanently delete the page.</span></span>

### <a name="outlook"></a><span data-ttu-id="8efa7-602">Outlook</span><span class="sxs-lookup"><span data-stu-id="8efa7-602">Outlook</span></span>

- <span data-ttu-id="8efa7-603">修正會導致使用者嘗試從次要帳戶建立會議邀請的問題，讓帳戶新增至他們的個人檔案，而不會看到空白的表格: 是欄位而不是其電子郵件地址。</span><span class="sxs-lookup"><span data-stu-id="8efa7-603">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>

- <span data-ttu-id="8efa7-604">修正新增共用信箱之後，導致使用者無法連線至公用資料夾的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-604">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>

- <span data-ttu-id="8efa7-605">解決了當代理人在某些情況下遭到拒絕而導致會議無法從經理的行事曆中移除的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-605">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>

- <span data-ttu-id="8efa7-606">解決了導致使用 Shared Calendar Improvements 的某些使用者無法查看剛新增的共用行事曆的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-606">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="8efa7-607">修正了當與雲端附件互動時，導致使用者偶爾當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-607">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>

- <span data-ttu-id="8efa7-608">解決會導致 CLP 使用者在回覆時的寄件者地址，從受保護的內容切換到未受保護的內容時會發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-608">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>

- <span data-ttu-id="8efa7-609">解決了 Outlook 無法啟用 [資料遺失保護原則] 提示使用 M365 商務版進階方案並為此服務付款的的使用者之問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-609">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="8efa7-610">已解決有回應/轉寄標註的clp審查活動的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-610">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>

- <span data-ttu-id="8efa7-611">已解決導致資料夾窗格寬度意外變更的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-611">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="8efa7-612">解決會導致使用者看到他們透過拖放附件，以複製到其檔案系統所建立附件的建立日期設為 4501 年 1 月 1 日的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-612">Addressed an issue that caused users to see the creation date of  attachments that they copied to their file system via drag and drop getting  set to January 1, 4501.</span></span>

- <span data-ttu-id="8efa7-613">解決了導致某些字元集的使用者在將 [智慧型連結] 新增至 SharePoint 檔案時，發現檔案名不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-613">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>

- <span data-ttu-id="8efa7-614">解決會導致使用者在 Outlook 中更新其規則時，看到 [此電腦上的規則與 Microsoft Exchange 上的規則不相符] 訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-614">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="8efa7-615">解決會導致 Outlook 無法擷取搜尋建議的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-615">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>

- <span data-ttu-id="8efa7-616">解決會導致共用行事曆改善功能的使用者看到行事曆失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-616">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>

- <span data-ttu-id="8efa7-617">解決會導致使用者在某些情況下遇到間歇性懸置和當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-617">Addressed an issue that caused users to experience intermittent hangs and crashes in some scenarios.</span></span>

- <span data-ttu-id="8efa7-618">解決了當您從 POP 帳戶刪除4或多個電子郵件時，已選取 [僅下載標題] 選項時，導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-618">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>

- <span data-ttu-id="8efa7-619">解決會導致若「未」核取 [下載共用資料夾]，共用行事曆會議的 [回應選項] 中會遺失 [允許轉寄] 選項的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-619">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="8efa7-620">解決在編輯經理行事曆上的現有行事曆約會時，導致代理人收到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-620">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="8efa7-621">解決使用者在第三方 MAPI 應用程式中遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-621">Addressed an issue that caused users to experience crashes in third party MAPI applications.</span></span>

- <span data-ttu-id="8efa7-622">已解決在 Windows 更新後，開啟儲存在本機的 msg 或 .oft 檔案會導致 Outlook 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-622">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="8efa7-623">已解決導致 Outlook 在某些 Windows 組建上當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-623">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>

- <span data-ttu-id="8efa7-624">解決會導致 Windows 10 伺服器版本的使用者看到警告「防毒軟體狀態: 無效」的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-624">Addressed an issue that caused users of Windows 10 server versions to see the warning "Antivirus status: Invalid.</span></span> <span data-ttu-id="8efa7-625">這個版本的 Windows 支援防毒偵測，但找不到任何防毒軟體。]，即使已正確安裝防毒軟體。</span><span class="sxs-lookup"><span data-stu-id="8efa7-625">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus correctly installed.</span></span>

- <span data-ttu-id="8efa7-626">已解決在 Windows 更新後，開啟儲存在本機的 msg 或 .oft 檔案會導致 Outlook 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-626">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="8efa7-627">已解決導致 Outlook 在某些 Windows 組建上當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-627">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>

- <span data-ttu-id="8efa7-628">解決會導致使用者看到 Outlook 持續提示他們執行收件匣修復工具的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-628">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>

- <span data-ttu-id="8efa7-629">解決使用滑鼠上的「X」按鈕時，導致使用者偶爾發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-629">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

- <span data-ttu-id="8efa7-630">解決了當選取安全性對話方塊上的 [儲存] 選項時，導致使用者無法將 OneDrive 外部的 OneDrive 附件儲存至他們的本機電腦的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-630">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="8efa7-631">解決導致 [排程助理員] 頁面無法顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-631">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>

- <span data-ttu-id="8efa7-632">解決導致 [排程助理員] 頁面無法顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-632">Addressed an issue that caused some users to see the Scheduling Assistant page fail to display.</span></span>

- <span data-ttu-id="8efa7-633">解決會導致使用者在擷取角色資訊時有時候會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-633">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>

- <span data-ttu-id="8efa7-634">修正了編輯收件者時，導致使用者偶爾當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-634">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="8efa7-635">修正會導致使用者在使用壓縮模式時發生異常的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-635">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>

- <span data-ttu-id="8efa7-636">解決會導致 Outlook 使用者在精簡檢視中看到瀏覽問題的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-636">Addressed an issue that caused outlook users to see issues with navigation in compact views.</span></span>

- <span data-ttu-id="8efa7-637">解決的問題導致在搜尋控制項中無法顯示滑鼠右鍵功能表。</span><span class="sxs-lookup"><span data-stu-id="8efa7-637">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>

- <span data-ttu-id="8efa7-638">解決會導致使用者在回覆或撰寫新電子郵件時收到下列錯誤的問題：「這個網頁中的某些檔案不存在預期的位置，</span><span class="sxs-lookup"><span data-stu-id="8efa7-638">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="8efa7-639">請問您一定要下載嗎?</span><span class="sxs-lookup"><span data-stu-id="8efa7-639">Do you want to download them anyway?</span></span> <span data-ttu-id="8efa7-640">如果您確定網頁來自信任的來源，請按 [是]」</span><span class="sxs-lookup"><span data-stu-id="8efa7-640">If you’re sure the Web page is from a trusted source, click Yes"</span></span>

- <span data-ttu-id="8efa7-641">解決導致使用者在退出 Outlook 時遇到掛斷的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-641">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>

- <span data-ttu-id="8efa7-642">解決會導致在「建議功能」中尋找功能不會傳回結果，因而讓使用者無法選擇提交新功能想法的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-642">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>

- <span data-ttu-id="8efa7-643">解決事件通知警示中導致格式設定問題的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-643">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>

- <span data-ttu-id="8efa7-644">已解決在從系統管理人通知中提交意見反應時，使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-644">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>

- <span data-ttu-id="8efa7-645">我們已修正複製和貼上 SVG 影像的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-645">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="8efa7-646">修正編輯收件者時，導致使用者偶爾當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-646">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="8efa7-647">我們已修正複製和貼上 SVG 影像的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-647">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="8efa7-648">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8efa7-648">PowerPoint</span></span>

- <span data-ttu-id="8efa7-649">修正使用者在同一檔案中同時有新版和舊版批註，因此觸發批註的升級而當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-649">Fixed a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>

- <span data-ttu-id="8efa7-650">我們已修正 PowerPoint 應用程式的當機問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-650">We have fixed a crash issue with PowerPoint app.</span></span>

- <span data-ttu-id="8efa7-651">我們已修正建議窗格的當機問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-651">We have fixed a crash issue with suggestion pane.</span></span>

### <a name="project"></a><span data-ttu-id="8efa7-652">Project</span><span class="sxs-lookup"><span data-stu-id="8efa7-652">Project</span></span>

- <span data-ttu-id="8efa7-653">修正在表單檢視中編輯前置/後續任務資料時，會觸發額外的 ProjectBeforeTaskChange 事件的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-653">Fixed an issue when Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="8efa7-654">修正儲存使用舊版 Project 建立的專案時，Project 可能當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-654">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="8efa7-655">修正了當開啟保護實際工作的設定時，使用者無法輸入分時期基準工時的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-655">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

- <span data-ttu-id="8efa7-656">修正在將任務標示為完成之後，不正確地將任務完成百分比變更為低於 100% 的值的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-656">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="8efa7-657">修正不先執行 OpenUndoTransaction 方法就不能觸發 OnUndoOrRedo 事件的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-657">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="8efa7-658">修正無法正確計算摘要工作日期的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-658">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="8efa7-659">修正透過 [已停用] 按鈕停用/啟動工作時，ProjectBeforeTaskChange 事件無法偵測的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-659">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="8efa7-660">修正如果您使用的是連線至 Project Web App 的 Project，且小數分隔符號是逗號，當您嘗試將延遲新增至相依性時，TaskDependencies Add 方法會失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-660">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>

- <span data-ttu-id="8efa7-661">修正 URL 以 .com 結尾時，無法從 Project Web App 在 Project 傳統型用戶端開啟專案的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-661">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>

- <span data-ttu-id="8efa7-662">修正當您貼上的工作具有多個依存性時，無法正確複製所有依存性的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-662">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>

- <span data-ttu-id="8efa7-663">修正無法將 PDF/XPS 從 Project 儲存至 SharePoint 文件庫的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-663">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>

- <span data-ttu-id="8efa7-664">修正當標示為 100% 完成之工作錯誤地變更為低於 100% 完成的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-664">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

- <span data-ttu-id="8efa7-665">修正當專案摘要工作-或是專案[開始/工作]欄位有變更時，ProjectBeforeTaskChange 事件不會觸發的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-665">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

- <span data-ttu-id="8efa7-666">修正如果資源中定義了多個成本費率表，其餘成本並不一定都能正確地計算的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-666">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>

- <span data-ttu-id="8efa7-667">修正「連結至 SharePoint 工作清單的專案的完成日期沒有更新」的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-667">Fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>

- <span data-ttu-id="8efa7-668">修正 [指派資源] 對話方塊中選取的工作與工作面板檢視中所選工作不同的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-668">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>

- <span data-ttu-id="8efa7-669">修正無法開啟已進入錯誤狀態的專案的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-669">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>

### <a name="skype"></a><span data-ttu-id="8efa7-670">Skype</span><span class="sxs-lookup"><span data-stu-id="8efa7-670">Skype</span></span>

- <span data-ttu-id="8efa7-671">當使用者收到將他們移至 Teams Only 的原則時，他們仍然可以使用商務版 Skype Outlook 增益集來排程會議。</span><span class="sxs-lookup"><span data-stu-id="8efa7-671">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span> <span data-ttu-id="8efa7-672">在此更新之後，當客戶端讀取指示用戶為 Teams Only 的策略並進入僅限會議加入模式後，您將不再能用商務版 Skype 安排會議。</span><span class="sxs-lookup"><span data-stu-id="8efa7-672">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span> <span data-ttu-id="8efa7-673">此外，如果商務版 Skype Outlook 增益集發現商務版 Skype 用戶端處於 [僅限會議加入] 模式，就無法自行啟動。</span><span class="sxs-lookup"><span data-stu-id="8efa7-673">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="8efa7-674">將跳舞表情符號膚色變更為中性色彩.</span><span class="sxs-lookup"><span data-stu-id="8efa7-674">Changed dancing emoticon skin tone to neutral color.</span></span>

### <a name="word"></a><span data-ttu-id="8efa7-675">Word</span><span class="sxs-lookup"><span data-stu-id="8efa7-675">Word</span></span>

- <span data-ttu-id="8efa7-676">解決 URL 包含查詢元件時，從自訂文件傳遞 (aspx) 開啟 Word 文件的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-676">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>

- <span data-ttu-id="8efa7-677">此更改解決了一個問題，即在上一個協同合作的作業後，Microsoft Office 應用程式可能卡在未通知的儲存失敗狀態的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-677">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>

- <span data-ttu-id="8efa7-678">解決會導致使用者在回覆或撰寫新電子郵件時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-678">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>

- <span data-ttu-id="8efa7-679">解決使用滑鼠上的「X」按鈕時，導致使用者偶爾發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-679">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

- <span data-ttu-id="8efa7-680">我們已修正複製和貼上 SVG 影像的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-680">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="8efa7-681">我們已修正當調整圖案大小時，使用者可能會遺失內容的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-681">We fixed an issue where the user might lose content when resize a shape.</span></span>

- <span data-ttu-id="8efa7-682">我們已修正基本樣式並未以 [內文樣式] 更新的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-682">We fixed an issue which the base styles are not updated with Normal style.</span></span>

- <span data-ttu-id="8efa7-683">我們已修正巨集 AutoOpen 在 AutoExec 之前執行的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-683">We fixed an issue where macro AutoOpen runs before AutoExec.</span></span>

- <span data-ttu-id="8efa7-684">我們已修正複製和貼上 SVG 影像的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-684">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="8efa7-685">解決會導致從應用程式拖曳部分內容時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-685">Resolved an issue that may have caused a crash when dragging some content from the app.</span></span>


### <a name="office-suite"></a><span data-ttu-id="8efa7-686">Office 套件</span><span class="sxs-lookup"><span data-stu-id="8efa7-686">Office Suite</span></span>

- <span data-ttu-id="8efa7-687">針對舊版非網頁服務的 [共用] 窗格，在開啟 [共用] 窗格下關閉文件時，可能會導致當機。</span><span class="sxs-lookup"><span data-stu-id="8efa7-687">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash.</span></span> <span data-ttu-id="8efa7-688">這個問題現在已經修正。</span><span class="sxs-lookup"><span data-stu-id="8efa7-688">This is now fixed.</span></span>

- <span data-ttu-id="8efa7-689">修正關閉 Office 檔案時，計時問題可能會導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-689">Fixed a timing issue could cause a crash when closing office files</span></span>

- <span data-ttu-id="8efa7-690">我們透過設定Bing附加預設安裝驗證設定為true默認，並將MSI返回成功視為安裝成功，而解決了 ValidateInstall 失敗率問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-690">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>

- <span data-ttu-id="8efa7-691">我們會將新的 AppV51 向後移，以修正先前 AppV51 中的回歸。</span><span class="sxs-lookup"><span data-stu-id="8efa7-691">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="8efa7-692">修正當嘗試硬連結符號連結時，導致更新失敗的 [點擊運作] 問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-692">Fixed a Click-to-Run issue which was resulting in update failure when trying to hard link symbolic links.</span></span>

- <span data-ttu-id="8efa7-693">修正即使完整產品的轉換已完成，也會導致執行階段訊息顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-693">Fixed an issue that caused a runtime message to show even though the transition to the full product is complete.</span></span> <span data-ttu-id="8efa7-694">此問題的修正程式是確保服務正確計算新增的產品。</span><span class="sxs-lookup"><span data-stu-id="8efa7-694">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="8efa7-695">我們已篩選出新增的產品 (確保它們同時存在於新的設定中)，並將它們新增到現有產品發行識別碼的結尾。</span><span class="sxs-lookup"><span data-stu-id="8efa7-695">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>

- <span data-ttu-id="8efa7-696">我們已修正使用者在特定情況下 (特別是進入或退出簡報者檢視畫面或使用多個監視器) 看到 UI 元素或內容未顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-696">We fixed an issue where users were seeing the UI elements or content not being displayed under certain conditions, in particular with coming in and out of Presenter View or using multiple monitors.</span></span>

- <span data-ttu-id="8efa7-697">此變更會解決載入和播放動畫內容 (例如 Gif 或3D 模型) 時可能會發生的懸置。</span><span class="sxs-lookup"><span data-stu-id="8efa7-697">This change addresses potential hangs when loading and playing animated content such as GIFs or 3D models.</span></span>

- <span data-ttu-id="8efa7-698">此變更解決 [壓縮圖片] 對話方塊無法保留特定使用者設定的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-698">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>

- <span data-ttu-id="8efa7-699">此更新解決了 Microsoft Office 中的一個問題：可能無法在執行時期正確找到 Visual Basic for Applications 專案，這些專案的參照預期透搜尋 PATH 環境變數指定的位置來找到，進而導致VBA 執行時期錯誤。</span><span class="sxs-lookup"><span data-stu-id="8efa7-699">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="8efa7-700">此更新修正了 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。</span><span class="sxs-lookup"><span data-stu-id="8efa7-700">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="8efa7-701">此修正可解決同時防止限制存取和保護設有密碼之檔案的錯誤。</span><span class="sxs-lookup"><span data-stu-id="8efa7-701">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>

- <span data-ttu-id="8efa7-702">解決在登錄 TabProcGrowth 值為 REG_SZ 類型的情況下啟用增益集時，Windows 中的 Office 主機會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-702">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>

- <span data-ttu-id="8efa7-703">當您啟用增益集，而登錄金鑰 HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth 被設為零時，辦公主機視窗會當機。</span><span class="sxs-lookup"><span data-stu-id="8efa7-703">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="8efa7-704">這變更將修正此問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-704">This change would fix this issue.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-august-11"></a><span data-ttu-id="8efa7-706">版本 2002: 8月11日</span><span class="sxs-lookup"><span data-stu-id="8efa7-706">Version 2002: August 11</span></span>
<span data-ttu-id="8efa7-707">*版本2002（组建12527.20988）*</span><span class="sxs-lookup"><span data-stu-id="8efa7-707">*Version 2002 (Build 12527.20988)*</span></span>

<span data-ttu-id="8efa7-708">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="8efa7-708">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8efa7-710">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8efa7-710">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="8efa7-711">Excel</span><span class="sxs-lookup"><span data-stu-id="8efa7-711">Excel</span></span>

- <span data-ttu-id="8efa7-712">修正無法將以 [唯讀建議] 方式開啟的檔案切換至編輯功能的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-712">Fixed an issue which prevented the ability to switch to editing for files that opened as "read-only recommended".</span></span>

### <a name="onenote"></a><span data-ttu-id="8efa7-713">OneNote</span><span class="sxs-lookup"><span data-stu-id="8efa7-713">OneNote</span></span>

- <span data-ttu-id="8efa7-714">移除了多餘的身分識別通話，以降低資源使用率</span><span class="sxs-lookup"><span data-stu-id="8efa7-714">Removed redundant identity calls to reduce resource utilization</span></span>

- <span data-ttu-id="8efa7-715">改善了共同撰寫狀態的偵測，以降低資源利用率。</span><span class="sxs-lookup"><span data-stu-id="8efa7-715">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="8efa7-716">改善了偵測錯誤的功能和同步處理經驗的品質。</span><span class="sxs-lookup"><span data-stu-id="8efa7-716">Improved capability for detecting errors and the quality of the sync experience.</span></span>

### <a name="outlook"></a><span data-ttu-id="8efa7-717">Outlook</span><span class="sxs-lookup"><span data-stu-id="8efa7-717">Outlook</span></span>

- <span data-ttu-id="8efa7-718">解決了在啟動某些租使用者的 Outlook 時，會導致嚴重效能問題的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-718">Addressed an issue that caused a significant performance issue when starting Outlook for some tenants.</span></span>

### <a name="skype"></a><span data-ttu-id="8efa7-719">Skype</span><span class="sxs-lookup"><span data-stu-id="8efa7-719">Skype</span></span>

- <span data-ttu-id="8efa7-720">修正在執行數天後，會無法啟動 32位元 Skype 商務版客戶螢幕共享的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-720">Fixed an issue where starting a screen share can fail on a 32-bit Skype for Business client after it has been running for several days.</span></span>

### <a name="office-suite"></a><span data-ttu-id="8efa7-721">Office 套件</span><span class="sxs-lookup"><span data-stu-id="8efa7-721">Office Suite</span></span>

- <span data-ttu-id="8efa7-722">修正如果 [自動儲存] 已透過組織政策關閉的話，某些文件可能不會在開啟時顯示最新的伺服器內容，除非使用者點擊 [可用的更新] 才會顯現。</span><span class="sxs-lookup"><span data-stu-id="8efa7-722">Fixed an issue where if AutoSave is turned off through group policy, some documents might not show the latest server contents on open until the user clicks on 'Updates available'.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-july-14"></a><span data-ttu-id="8efa7-724">版本 2002：7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="8efa7-724">Version 2002: July 14</span></span>
<span data-ttu-id="8efa7-725">*版本 2002 (組建 12527.20880)*</span><span class="sxs-lookup"><span data-stu-id="8efa7-725">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="8efa7-726">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="8efa7-726">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8efa7-728">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8efa7-728">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="8efa7-729">Excel</span><span class="sxs-lookup"><span data-stu-id="8efa7-729">Excel</span></span>

- <span data-ttu-id="8efa7-730">加速載入本機 OneDrive 資料夾中的檔案。</span><span class="sxs-lookup"><span data-stu-id="8efa7-730">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="8efa7-731">修正當儲存至 SharePoint/OneDrive 時，會導致自訂功能區索引標籤 CustomUI XML 的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-731">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="8efa7-732">修正因為增益集是以字母順序載入，而不是以使用者指定的順序載入，而顯示 [這個活頁簿目前正由其他活頁簿所參考中，不可關閉] 錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-732">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="8efa7-733">修正按一下已開啟活頁簿中某個位置的超連結時，活頁簿可能會隱藏的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-733">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="8efa7-734">我們已修正某些複製和貼上的圖表連結使用的是映射磁碟機位址，而不是通用位址的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-734">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="8efa7-735">改善刪除具有合併儲存格的欄時的效能。</span><span class="sxs-lookup"><span data-stu-id="8efa7-735">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="8efa7-736">修正 [列印] 對話方塊的印表機清單中，印表機名稱可能會重複的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-736">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="8efa7-737">我們已修正包含多個含有定義名稱的公式會導致儲存檔案時間加長的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-737">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>


### <a name="outlook"></a><span data-ttu-id="8efa7-738">Outlook</span><span class="sxs-lookup"><span data-stu-id="8efa7-738">Outlook</span></span>

- <span data-ttu-id="8efa7-739">我們已修正以下問題：當使用多個不同解析度的監視器時，輸入法編輯器 (IEM) 視窗會覆蓋透過 IME 輸入的文字。</span><span class="sxs-lookup"><span data-stu-id="8efa7-739">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="8efa7-740">解決會導致週期性約會或會議在接近時區定義變更時於錯誤的時間顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-740">Addressed an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="8efa7-741">解決會導致使用者在 Outlook 中更新其規則時，看到 [此電腦上的規則與 Microsoft Exchange 上的規則不相符] 訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-741">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="8efa7-742">解決會導致若「未」核取 [下載共用資料夾]，共用行事曆會議的 [回應選項] 中會遺失 [允許轉寄] 選項的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-742">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="8efa7-743">已解決會導致類別有時候會從電子郵件訊息中消失的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-743">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="8efa7-744">已解決會導致代理人在不同機器上所看到的共用信箱有不同資料夾階層的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-744">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="8efa7-745">解決在編輯經理行事曆上的現有行事曆約會時，導致代理人收到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-745">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="8efa7-746">解決在編輯主旨之後，會導致 NDR 訊息的本文從 Unicode 變更為 ASCII 的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-746">Addressed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="8efa7-747">解決當兩個增益集將一個按鈕新增到相同功能區群組時，會導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-747">Addressed an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="8efa7-748">解決了導致使用者無法將電子郵件傳送到個人通訊群組清單的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-748">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="8efa7-749">解決當租用戶預設權限設定為「任何人」時，會導致無法將連結新增至具有正確租用戶預設權限的電子郵件的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-749">Addressed an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as"anyone".</span></span>

- <span data-ttu-id="8efa7-750">解決了當選取安全性對話方塊上的 [儲存] 選項時，導致使用者無法將 OneDrive 外部的 OneDrive 附件儲存至他們的本機電腦的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-750">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="word"></a><span data-ttu-id="8efa7-751">Word</span><span class="sxs-lookup"><span data-stu-id="8efa7-751">Word</span></span>

- <span data-ttu-id="8efa7-752">我們已修正啟用原則 FileBlick\Word2007Files 時共同編輯中的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-752">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="8efa7-753">我們已修正新增已重新命名之查閱欄位時，Word QuickPart 無法使用的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-753">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="8efa7-754">Office 套件</span><span class="sxs-lookup"><span data-stu-id="8efa7-754">Office Suite</span></span>

- <span data-ttu-id="8efa7-755">修正當共同撰寫大型 PowerPoint 檔案時，使用者可能會遇到過度網路和 CPU 使用量的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-755">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="8efa7-756">我們會將新的 AppV51 向後移，以修正先前 AppV51 中的回歸。</span><span class="sxs-lookup"><span data-stu-id="8efa7-756">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="8efa7-757">解決在登錄 TabProcGrowth 值為 REG_SZ 類型的情況下啟用增益集時，Windows 中的 Office 主機會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-757">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-june-09"></a><span data-ttu-id="8efa7-759">版本 2002: 6 月 09日</span><span class="sxs-lookup"><span data-stu-id="8efa7-759">Version 2002: June 09</span></span>
<span data-ttu-id="8efa7-760">*版本2002（組建12527.20720）*</span><span class="sxs-lookup"><span data-stu-id="8efa7-760">*Version 2002 (Build 12527.20720)*</span></span>

<span data-ttu-id="8efa7-761">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="8efa7-761">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8efa7-763">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8efa7-763">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="8efa7-764">Excel</span><span class="sxs-lookup"><span data-stu-id="8efa7-764">Excel</span></span>

- <span data-ttu-id="8efa7-765">修正當檔案路徑太長時，在檔案重新開啟之後外部連結會停止運作的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-765">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="8efa7-766">修正當 Excel 視窗透過 Teams 共用時，使用 Ctrl + Shift + 方向鍵滑動後，Excel 可能會無法回應的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-766">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="8efa7-767">修正列印時表單控制項的核取方塊縮放的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-767">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="8efa7-768">當您使用舊版的「共用活頁簿」模式，嘗試為活頁簿的新工作表列出變更時，就會發生當機。</span><span class="sxs-lookup"><span data-stu-id="8efa7-768">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="8efa7-769">在已篩選清單中插入欄的時間會比預期更長。</span><span class="sxs-lookup"><span data-stu-id="8efa7-769">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="8efa7-770">修正開始公式的 @ 符號會被視為隱式交集運算子的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-770">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

### <a name="outlook"></a><span data-ttu-id="8efa7-771">Outlook</span><span class="sxs-lookup"><span data-stu-id="8efa7-771">Outlook</span></span>

- <span data-ttu-id="8efa7-772">可透過原 Teams 客戶直接啟用加入 Teams 會議。</span><span class="sxs-lookup"><span data-stu-id="8efa7-772">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="8efa7-773">解決了 Outlook 無法啟用 [資料遺失保護原則] 提示使用 M365 商務版進階方案並為此服務付款的的使用者之問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-773">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="8efa7-774">解決了導致瀏覽器模擬設置錯誤的用戶無法完成 Gmail 身分驗證提示的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-774">Addressed an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="8efa7-775">解決了導致伺服器作業系統上的 Outlook 使用者看到「防病毒處理狀態：無效」的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-775">Addressed an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="8efa7-776">這個版本的 Windows 支援防毒軟體檢測，但即使已適當設定防毒軟體，也無法找到防毒軟體。</span><span class="sxs-lookup"><span data-stu-id="8efa7-776">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

### <a name="word"></a><span data-ttu-id="8efa7-777">Word</span><span class="sxs-lookup"><span data-stu-id="8efa7-777">Word</span></span>

- <span data-ttu-id="8efa7-778">我們已修正文件中的文字對齊，在使用 [快速列印] 進行列印之後嘗試進行編輯時變得混亂的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-778">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

### <a name="office-suite"></a><span data-ttu-id="8efa7-779">Office 套件</span><span class="sxs-lookup"><span data-stu-id="8efa7-779">Office Suite</span></span>

- <span data-ttu-id="8efa7-780">我們將後台中的頻道名稱更新為2020年1月 Fork 的新通道名稱，解決了此問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-780">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="8efa7-781">我們已修正此問題，如果裝置受政策管理，將不會調用 DMS 聽眾 API。</span><span class="sxs-lookup"><span data-stu-id="8efa7-781">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="8efa7-782">已解決在單一交易中新增和移除應用程式時，未完成移除的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-782">Resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="8efa7-783">當您啟用增益集，而登錄金鑰 HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth 被設為零時，辦公主機視窗會當機。</span><span class="sxs-lookup"><span data-stu-id="8efa7-783">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="8efa7-784">這變更將修正此問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-784">This change would fix this issue.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-may-12"></a><span data-ttu-id="8efa7-786">版本 2002：5 月 12 日</span><span class="sxs-lookup"><span data-stu-id="8efa7-786">Version 2002: May 12</span></span>
<span data-ttu-id="8efa7-787">*版本 2002 (組建 12527.20612)*</span><span class="sxs-lookup"><span data-stu-id="8efa7-787">*Version 2002 (Build 12527.20612)*</span></span>

<span data-ttu-id="8efa7-788">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="8efa7-788">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8efa7-790">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8efa7-790">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="8efa7-791">Excel</span><span class="sxs-lookup"><span data-stu-id="8efa7-791">Excel</span></span>

- <span data-ttu-id="8efa7-792">開啟含有許多其他活頁簿 (尤其是含有隱藏視窗) 參照的活頁簿時，速度比預期慢。</span><span class="sxs-lookup"><span data-stu-id="8efa7-792">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="8efa7-793">在某些情況下，開啟 CSV 檔案所花費的時間超過預期。</span><span class="sxs-lookup"><span data-stu-id="8efa7-793">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="8efa7-794">在某些情況下，當您切換不同縮放比例的活頁簿時，Excel 可能會當機。</span><span class="sxs-lookup"><span data-stu-id="8efa7-794">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="8efa7-795">修正 VBA 將值寫入範圍時，速度比預期慢的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-795">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="8efa7-796">從有色彩篩選的欄複製的資料有時候無法正確貼上。</span><span class="sxs-lookup"><span data-stu-id="8efa7-796">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="8efa7-797">修正在複製含有樞紐分析表的工作表後，會於某些情況下導致 Excel 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-797">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="8efa7-798">在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。</span><span class="sxs-lookup"><span data-stu-id="8efa7-798">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="8efa7-799">已解決在儲存並重新開啟檔案時，圖表軸上的 "Value Crosses At" 屬性發生意外變更的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-799">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="8efa7-800">使用 Range.Value 和 Range.Value2 (VBA) 會導致公式以動態陣列的形式輸入。</span><span class="sxs-lookup"><span data-stu-id="8efa7-800">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

### <a name="onenote"></a><span data-ttu-id="8efa7-801">OneNote</span><span class="sxs-lookup"><span data-stu-id="8efa7-801">OneNote</span></span>

- <span data-ttu-id="8efa7-802">對通知進行本地化，讓使用者可以了解更多 OneNote 使用者體驗中正在採取的臨時措施的資訊，以改善同步處理和服務穩定性。</span><span class="sxs-lookup"><span data-stu-id="8efa7-802">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="8efa7-803">顯示通知，讓使用者可以了解更多 OneNote 使用者體驗中正在採取的臨時措施的資訊，以改善同步處理和服務穩定性。</span><span class="sxs-lookup"><span data-stu-id="8efa7-803">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="8efa7-804">在 OneNote 2016 中暫時降低版本歷程記錄頁面的數目和同步處理頻率，以改善同步處理與服務穩定性。</span><span class="sxs-lookup"><span data-stu-id="8efa7-804">Improved sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="8efa7-805">透過暫時停用 OneNote 2016 中的資源回收筒，來改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="8efa7-805">Improved sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="8efa7-806">當使用者嘗試刪除通常會傳送到 [資源回收筒] 的資料時，系統會詢問使用者是否希望保留或永久刪除資料。</span><span class="sxs-lookup"><span data-stu-id="8efa7-806">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="8efa7-807">透過暫時調整 OneNote 2016 中的同步處理頻率，來改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="8efa7-807">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="8efa7-808">暫時延遲下載線上筆記本中內嵌的檔案和影像，直到使用者瀏覽至 OneNote 2016 中的頁面，以改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="8efa7-808">Improved sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="8efa7-809">透過暫時停用 OneNote 2016 中的應用程式內視訊錄製，來改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="8efa7-809">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="8efa7-810">本機筆記本不受這個值的影響。</span><span class="sxs-lookup"><span data-stu-id="8efa7-810">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="8efa7-811">透過暫時將 OneNote 2016 中新嵌入附件的最大允許大小減少為 50MB，來改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="8efa7-811">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="8efa7-812">對於超過此限制的檔案，使用者可以選擇將檔案上傳到 OneDrive，並將連結插入 OneNote。</span><span class="sxs-lookup"><span data-stu-id="8efa7-812">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

### <a name="outlook"></a><span data-ttu-id="8efa7-813">Outlook</span><span class="sxs-lookup"><span data-stu-id="8efa7-813">Outlook</span></span>

- <span data-ttu-id="8efa7-814">已解決導致資料夾窗格寬度意外變更的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-814">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="8efa7-815">解決以下問題：Windows 更新之後，使用者開啟 .msg 和 .oft 檔案時遇到當機。</span><span class="sxs-lookup"><span data-stu-id="8efa7-815">Addressed an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="8efa7-816">解決會導致使用者在轉寄大型 HTML 郵件時，看到郵件內文截斷的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-816">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="8efa7-817">此更新修正在查看或撰寫郵件時，Microsoft Outlook 未顯示目前的敏感度標籤的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-817">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="8efa7-818">解決了導致使用者無法將電子郵件傳送到個人通訊群組清單的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-818">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8efa7-819">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8efa7-819">PowerPoint</span></span>

- <span data-ttu-id="8efa7-820">修正以下問題：當開啟的檔案複本具有增強式註解時，為使用者轉送正確的訊息。</span><span class="sxs-lookup"><span data-stu-id="8efa7-820">Fixed an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="word"></a><span data-ttu-id="8efa7-821">Word</span><span class="sxs-lookup"><span data-stu-id="8efa7-821">Word</span></span>

- <span data-ttu-id="8efa7-822">解決了 Access 和 Publisher 因所安裝的語言而無法正常啟動的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-822">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>

- <span data-ttu-id="8efa7-823">修正受保護無法編輯之文件的比較功能問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-823">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="8efa7-824">我們已修正將兩份文件合併成一份文件時的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-824">We fixed an issue when merging 2 documents into one document.</span></span>

### <a name="office-suite"></a><span data-ttu-id="8efa7-825">Office 套件</span><span class="sxs-lookup"><span data-stu-id="8efa7-825">Office Suite</span></span>

- <span data-ttu-id="8efa7-826">此修正解決了當檔案已在用戶端中進行快取時，Project 應用程式不應封鎖網路。</span><span class="sxs-lookup"><span data-stu-id="8efa7-826">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>

- <span data-ttu-id="8efa7-827">我們已解決內部作業在失敗時擲出例外狀況，而不是記錄和繼續進行的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-827">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="8efa7-828">受影響的使用者將不會再無法收到更新。</span><span class="sxs-lookup"><span data-stu-id="8efa7-828">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="8efa7-829">這項變更可確保草繪大綱可在功能區中正常運作。</span><span class="sxs-lookup"><span data-stu-id="8efa7-829">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="8efa7-830">修正使用一些特定 proxy 設定時，從內部部署位置開啟檔案時發生的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-830">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="8efa7-831">此更新修正了 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。</span><span class="sxs-lookup"><span data-stu-id="8efa7-831">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="8efa7-832">此更新解決了 Microsoft Office 中的一個問題：可能無法在執行時期正確找到 Visual Basic for Applications 專案，這些專案的參照預期透搜尋 PATH 環境變數指定的位置來找到，進而導致VBA 執行時期錯誤。</span><span class="sxs-lookup"><span data-stu-id="8efa7-832">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="8efa7-833">此更新解決了 Microsoft Word 中的一個問題：如果標籤原則套用了頁首或頁尾或浮水印，那麼在套用敏感度標籤時，插入長度超過 255 個字元的文字後續將無法透過變更或刪除標籤來識別和刪除。</span><span class="sxs-lookup"><span data-stu-id="8efa7-833">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

- <span data-ttu-id="8efa7-834">修正問題，可在 Office 遞交工作階段期間消除當機，並改善使用者體驗中的可靠性。</span><span class="sxs-lookup"><span data-stu-id="8efa7-834">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>  

- <span data-ttu-id="8efa7-835">這個錯誤會更新增強的設定服務 (ECS) url 端點。</span><span class="sxs-lookup"><span data-stu-id="8efa7-835">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="8efa7-836">呼叫這個較新的端點，可從 ECS 進行提取獲得更高的成功率。</span><span class="sxs-lookup"><span data-stu-id="8efa7-836">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-april-14"></a><span data-ttu-id="8efa7-838">版本 2002：4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="8efa7-838">Version 2002: April 14</span></span>
<span data-ttu-id="8efa7-839">*版本 2002 (組建 12527.20442)*</span><span class="sxs-lookup"><span data-stu-id="8efa7-839">*Version 2002 (Build 12527.20442)*</span></span>

<span data-ttu-id="8efa7-840">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="8efa7-840">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


### <a name="feature-updates"></a><span data-ttu-id="8efa7-841">功能更新</span><span class="sxs-lookup"><span data-stu-id="8efa7-841">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="8efa7-842">Excel</span><span class="sxs-lookup"><span data-stu-id="8efa7-842">Excel</span></span>

- <span data-ttu-id="8efa7-843">**輸入會傳回多個值的公式**：現在您可以快速輸入公式來傳回多個值，並且值會自動溢出至相鄰的儲存格。</span><span class="sxs-lookup"><span data-stu-id="8efa7-843">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="8efa7-844">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-844">Learn more</span></span>](https://support.microsoft.com/en-us/office/new-array-functions-003df6c7-1dcb-4388-8e2e-0fe77a0887bc?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="8efa7-845">**六個功能強大的函數：** 我們新增了六個新的函數，讓您的試算表功能更強大：FILTER、SORT、SORTBY、UNIQUE、SEQUENCE 和 RANDARRAY。</span><span class="sxs-lookup"><span data-stu-id="8efa7-845">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span>  [<span data-ttu-id="8efa7-846">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-846">Learn more</span></span>](https://support.microsoft.com/en-us/office/easier-array-formulas-5c2c9cbb-def8-409a-b380-2fbf91b20aa3?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="8efa7-847">**向左看，向右看... XLOOKUP 在這裡！：** 一列接著一列，在含有 XLOOKUP 的表格或範圍中尋找您需要的項目。</span><span class="sxs-lookup"><span data-stu-id="8efa7-847">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span>  <span data-ttu-id="8efa7-848">
  [深入了解](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)</span><span class="sxs-lookup"><span data-stu-id="8efa7-848">[Learn more](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8efa7-850">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8efa7-850">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="8efa7-851">Excel</span><span class="sxs-lookup"><span data-stu-id="8efa7-851">Excel</span></span>

- <span data-ttu-id="8efa7-852">重複開啟內嵌在 Word 或 PowerPoint 中的活頁簿時，在某些情況下，Excel 會當機。</span><span class="sxs-lookup"><span data-stu-id="8efa7-852">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="8efa7-853">儲存為 CSV 檔案時，在某些情況下，Excel 會將所有欄合併成單一欄。</span><span class="sxs-lookup"><span data-stu-id="8efa7-853">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="8efa7-854">在受保護工作表中的範圍使用 Range.ClearContents 可能會比預期花的時間更長。</span><span class="sxs-lookup"><span data-stu-id="8efa7-854">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="8efa7-855">修正在 [預覽列印] 中顯示表單控制項時的文字縮放比例問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-855">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="8efa7-856">與功能區互動的 VBA 宏可能會意外以 ScreenUpdating 設定為 True 執行。</span><span class="sxs-lookup"><span data-stu-id="8efa7-856">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="8efa7-857">解決了當來源活頁簿關閉時，外部連結無法在填滿時 (向下填滿、跨表填滿等) 更新的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-857">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is closed.</span></span>

- <span data-ttu-id="8efa7-858">在某些情況下，使用 VBA 的 Application.Evaluate 對使用者定義的函數無法運作。</span><span class="sxs-lookup"><span data-stu-id="8efa7-858">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="8efa7-859">解決從範本建立圖表時的效能問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-859">Addressed a performance issue when creating charts from templates.</span></span>


### <a name="outlook"></a><span data-ttu-id="8efa7-860">Outlook</span><span class="sxs-lookup"><span data-stu-id="8efa7-860">Outlook</span></span>

- <span data-ttu-id="8efa7-861">解決了在某些情況下，[群組] 標題會意外展開的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-861">Addressed an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="8efa7-862">解決了導致使用者在選取特定搜尋結果時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-862">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="8efa7-863">解決了使用滑鼠上的 X 按鈕時，導致使用者偶爾發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-863">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="8efa7-864">解決了會讓 [附件工具] 中的 [儲存至雲端] 按鈕不見的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-864">Addressed an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8efa7-865">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8efa7-865">PowerPoint</span></span>

- <span data-ttu-id="8efa7-866">已改善複製貼上的案例：將 PowerPoint 投影片中的圖形複製並貼到迴圈中的其他投影片，可能會出現例外狀況而失敗。</span><span class="sxs-lookup"><span data-stu-id="8efa7-866">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


### <a name="project"></a><span data-ttu-id="8efa7-867">Project</span><span class="sxs-lookup"><span data-stu-id="8efa7-867">Project</span></span>

- <span data-ttu-id="8efa7-868">修正儲存使用舊版 [專案] 建立的專案時，[專案] 可能當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-868">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="8efa7-869">修正透過 [已停用] 按鈕停用/啟動工作時，ProjectBeforeTaskChange 事件無法偵測的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-869">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

### <a name="word"></a><span data-ttu-id="8efa7-870">Word</span><span class="sxs-lookup"><span data-stu-id="8efa7-870">Word</span></span>

- <span data-ttu-id="8efa7-871">解決了使用滑鼠上的 X 按鈕時，導致使用者偶爾發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-871">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="8efa7-872">我們已修正表格中最適文字大小的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-872">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="8efa7-873">我們已修正插入水平線無法更短並置中的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-873">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-march-10"></a><span data-ttu-id="8efa7-875">版本 2002：3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="8efa7-875">Version 2002: March 10</span></span>
<span data-ttu-id="8efa7-876">*版本 2002 (組建 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="8efa7-876">*Version 2002 (Build 12527.20278)*</span></span>

<span data-ttu-id="8efa7-877">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="8efa7-877">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="8efa7-879">功能更新</span><span class="sxs-lookup"><span data-stu-id="8efa7-879">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="8efa7-880">Access</span><span class="sxs-lookup"><span data-stu-id="8efa7-880">Access</span></span>

- <span data-ttu-id="8efa7-881">**快速尋找連結資料表：** 新的搜尋方塊可讓您輕鬆尋找連結資料表。</span><span class="sxs-lookup"><span data-stu-id="8efa7-881">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="8efa7-882">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-882">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="8efa7-883">Excel</span><span class="sxs-lookup"><span data-stu-id="8efa7-883">Excel</span></span>

- <span data-ttu-id="8efa7-884">**使用 \@提及取得他人注意：** 在註解中使用 @提及功能，讓同事知道您需要他們提供建議。</span><span class="sxs-lookup"><span data-stu-id="8efa7-884">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="8efa7-885">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-885">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="8efa7-886">**找到您要尋找的項目：** 搜尋命令、人員、檔案、相片、網頁文章等。</span><span class="sxs-lookup"><span data-stu-id="8efa7-886">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="8efa7-887">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-887">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- <span data-ttu-id="8efa7-888">**勾勒草圖：** 為活頁簿中的 Office 圖形提供隨意的手繪外觀。</span><span class="sxs-lookup"><span data-stu-id="8efa7-888">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="8efa7-889">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-889">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="8efa7-890">**更快速共用檔案：** 不需開啟檔案，即可從最近使用清單直接共用您的檔案。</span><span class="sxs-lookup"><span data-stu-id="8efa7-890">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="8efa7-891">**不必再來回往返瀏覽器：** 您決定開啟 Office 文件連結的方式：在瀏覽器或應用程式中開啟。</span><span class="sxs-lookup"><span data-stu-id="8efa7-891">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="8efa7-892">**專注在待辦事項上：** 選取 [解決] 來摺疊註解，使得開啟中的項目能夠突顯。</span><span class="sxs-lookup"><span data-stu-id="8efa7-892">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="8efa7-893">**建立更易於存取的 PDF：** 建立 PDF 檔案，在儲存之前，協助工具檢查程式會指出應該修正的協助工具問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-893">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="8efa7-894">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-894">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="8efa7-895">**轉換檔案，以提升存取性：** 將您的檔案升級為現代格式，讓所有人更容易存取。</span><span class="sxs-lookup"><span data-stu-id="8efa7-895">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="8efa7-896">**資料視覺化工具增益集：** 從 Excel 快速建立 Visio 流程圖。</span><span class="sxs-lookup"><span data-stu-id="8efa7-896">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="8efa7-897">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-897">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="8efa7-898">**即時讀取與回覆：** 直接從電子郵件回覆註解和提及，而不需開啟活頁簿。</span><span class="sxs-lookup"><span data-stu-id="8efa7-898">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="8efa7-899">**在活頁簿上取得統計資料：** 活頁簿統計資料提供活頁簿內容的概觀，協助您更輕鬆地探索其內容。</span><span class="sxs-lookup"><span data-stu-id="8efa7-899">**Get stats on your workbook:** Workbook Statistics provides an overview of the content of a workbook, to help you more easily discover its contents.</span></span>

- <span data-ttu-id="8efa7-900">**符合您情境的更多圖示：** 我們新增了超過 300 個新圖示。</span><span class="sxs-lookup"><span data-stu-id="8efa7-900">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="8efa7-901">其位置：[插入] > [圖示]。</span><span class="sxs-lookup"><span data-stu-id="8efa7-901">Find them at Insert > Icons.</span></span> [<span data-ttu-id="8efa7-902">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-902">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="outlook"></a><span data-ttu-id="8efa7-903">Outlook</span><span class="sxs-lookup"><span data-stu-id="8efa7-903">Outlook</span></span>

- <span data-ttu-id="8efa7-904">**將您的 LinkedIn 人際網路連接至 Outlook：** 安全地將您的 LinkedIn 帳戶與 Microsoft 帳戶連結，以直接在人員卡片中查看 LinkedIn 個人資料中的資訊。</span><span class="sxs-lookup"><span data-stu-id="8efa7-904">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="8efa7-905">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-905">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="8efa7-p176">**集中所有加密選項：** 只要前往 [選項] > [加密]，即可選擇要用來保護電子郵件訊息的方法。[深入了解](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="8efa7-p176">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="8efa7-908">**Outlook 中的 [插入連結] 功能表會插入含有租用戶系統管理員所定義的權限的連結：** Outlook 中使用 [插入連結] 所插入的連結，只有具有連結權限的使用者可使用。</span><span class="sxs-lookup"><span data-stu-id="8efa7-908">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="8efa7-909">這常會造成使用者來回傳送電子郵件，要求對方授與文件的存取權。</span><span class="sxs-lookup"><span data-stu-id="8efa7-909">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="8efa7-910">我們已更新這項體驗，現在插入的連結將具有由租用戶系統管理員設定的預設權限。針對 MSIT，這是「組織可以編輯」，使得以此方式收到共用連結的所有內部使用者將可以存取它。</span><span class="sxs-lookup"><span data-stu-id="8efa7-910">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="8efa7-911">**具有拼字問題或錯字的搜尋：** 即使您的拼寫不相符，Outlook 也會找到您要尋找的內容。</span><span class="sxs-lookup"><span data-stu-id="8efa7-911">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="8efa7-912">**網路釣魚郵件很容易找到：** 垃圾郵件和網路釣魚訊息的外觀不同，因此您可以從收件匣輕鬆找出並加以清除。</span><span class="sxs-lookup"><span data-stu-id="8efa7-912">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="8efa7-913">**抵禦攻擊的進階防護：** 使用 Office 365 進階威脅防護，您會受到保護，不受電子郵件主旨、附加的郵件、簽署的郵件、網路路徑內超連結的攻擊。</span><span class="sxs-lookup"><span data-stu-id="8efa7-913">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="8efa7-914">**讓我繪製：** 使用筆跡在圖片上徒手畫或新增繪圖畫布來傳達您的想法。</span><span class="sxs-lookup"><span data-stu-id="8efa7-914">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="8efa7-915">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-915">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="8efa7-916">**在搜尋結果中查看相關郵件：** Outlook 會分析搜尋字詞，然後在搜尋結果的最上方顯示最相關的電子郵件。</span><span class="sxs-lookup"><span data-stu-id="8efa7-916">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="8efa7-917">您也可以在 [最佳結果] 區段中查看依日期排列順序的所有結果。</span><span class="sxs-lookup"><span data-stu-id="8efa7-917">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="8efa7-918">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-918">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

- <span data-ttu-id="8efa7-919">**取得位置建議：** 排程約會和會議時，請在 [位置] 中開始輸入，Outlook 會建議會議室、地址，以及其他最近使用的位置。</span><span class="sxs-lookup"><span data-stu-id="8efa7-919">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="8efa7-920">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-920">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)

- <span data-ttu-id="8efa7-921">**在螢幕上容納更多郵件：** 選取 [檢視] > [使用更緊密的間距] 來調整郵件之間的間距。</span><span class="sxs-lookup"><span data-stu-id="8efa7-921">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="8efa7-922">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-922">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="8efa7-923">**在不同燈光下查看郵件：** 使用太陽/月亮按鈕以在讀取窗格中於淺色和深色背景之間切換。</span><span class="sxs-lookup"><span data-stu-id="8efa7-923">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="8efa7-924">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-924">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="8efa7-925">**符合您情境的更多圖示：** 我們新增了超過 300 個新圖示。</span><span class="sxs-lookup"><span data-stu-id="8efa7-925">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="8efa7-926">其位置：[插入] > [圖示]。</span><span class="sxs-lookup"><span data-stu-id="8efa7-926">Find them at Insert > Icons.</span></span> [<span data-ttu-id="8efa7-927">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-927">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="powerpoint"></a><span data-ttu-id="8efa7-928">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8efa7-928">PowerPoint</span></span>

- <span data-ttu-id="8efa7-929">**在 PowerPoint 中快速即時共同作業：** 在 PowerPoint 中快速即時共同作業</span><span class="sxs-lookup"><span data-stu-id="8efa7-929">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="8efa7-930">**新的校對工具：** 不著重您的文字。</span><span class="sxs-lookup"><span data-stu-id="8efa7-930">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="8efa7-931">PowerPoint 現在提供文法及書寫建議。</span><span class="sxs-lookup"><span data-stu-id="8efa7-931">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="8efa7-932">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-932">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="8efa7-933">**即時的輔助字幕和翻譯字幕：** 簡報者的文字會自動顯示為畫面上的標題，或翻譯為所選語言的字幕。</span><span class="sxs-lookup"><span data-stu-id="8efa7-933">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="8efa7-934">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-934">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="8efa7-p186">**您來計算，格式設定交給我們** 我們能將難懂的手寫數學運算式變更為標準字元。只要選擇 [筆跡轉換數學]，然後選取您的手寫筆記，即可開始使用。[深入了解](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="8efa7-p186">**You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

- <span data-ttu-id="8efa7-938">**尋找您要尋找的項目：** 使用搜尋方塊來尋找文字、命令、說明等。</span><span class="sxs-lookup"><span data-stu-id="8efa7-938">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="8efa7-939">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-939">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="8efa7-940">**尋找並修正遺失的投影片標題：** 投影片標題可為您的企劃加分，並讓所有功能的使用者都能存取投影片。</span><span class="sxs-lookup"><span data-stu-id="8efa7-940">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="8efa7-941">協助工具檢查程式會顯示缺少標題的地方，這樣您就可以快速新增標題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-941">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="8efa7-942">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-942">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="8efa7-943">**勾勒草圖：** 為簡報中的 Office 圖形提供隨意的手繪外觀。</span><span class="sxs-lookup"><span data-stu-id="8efa7-943">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="8efa7-944">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-944">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="8efa7-945">**更快速共用檔案：** 不需開啟檔案，即可從最近使用清單直接共用您的檔案。</span><span class="sxs-lookup"><span data-stu-id="8efa7-945">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="8efa7-946">**不必再來回往返瀏覽器：** 您決定開啟 Office 文件連結的方式：在瀏覽器或應用程式中開啟。</span><span class="sxs-lookup"><span data-stu-id="8efa7-946">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="8efa7-947">**將圖例另存成 SVG：** 將圖表、圖形或其他圖例另存成可縮放向量圖形，其可調整大小，且不損失影像品質。</span><span class="sxs-lookup"><span data-stu-id="8efa7-947">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="8efa7-948">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-948">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="8efa7-949">**列印講義上的投影片編號：** 投影片編號會自動包含在講義上。</span><span class="sxs-lookup"><span data-stu-id="8efa7-949">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="8efa7-950">由您決定將其保留或關閉。</span><span class="sxs-lookup"><span data-stu-id="8efa7-950">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="8efa7-951">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-951">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="8efa7-952">**筆跡立即重播：** 當您在投影片上進行手寫時，套用重播動畫可在投影片放映期間重播真實手繪的筆跡。</span><span class="sxs-lookup"><span data-stu-id="8efa7-952">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="8efa7-953">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-953">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- <span data-ttu-id="8efa7-954">**建立更易於存取的 PDF：** 建立 PDF 檔案，在儲存之前，協助工具檢查程式會指出應該修正的協助工具問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-954">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

- <span data-ttu-id="8efa7-955">**全方位最佳化您的簡報：** 協助工具檢查程式可協助您以螢幕閱讀器為中心，在投影片上排列物件。</span><span class="sxs-lookup"><span data-stu-id="8efa7-955">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

- <span data-ttu-id="8efa7-956">**轉換檔案以增強協助工具功能：** 將您的檔案升級為現代格式，讓所有人更容易存取。</span><span class="sxs-lookup"><span data-stu-id="8efa7-956">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="8efa7-957">**更安全的影片體驗：** 安全性增強功能可讓您擁有更安全的線上影片體驗。</span><span class="sxs-lookup"><span data-stu-id="8efa7-957">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="8efa7-958">**當您可以重複使用時為什麼要重新打造？** 重複使用您所建立的投影片或其他人與您共用的投影片來以節省時間。</span><span class="sxs-lookup"><span data-stu-id="8efa7-958">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="8efa7-959">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-959">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

- <span data-ttu-id="8efa7-960">**在 Office 365 的 PowerPoint 中將手寫筆跡變更為圖形、文字或數學：** 從任意格式的筆跡變成 Office 圖形、文字，或以幾個筆劃變成數學運算式。</span><span class="sxs-lookup"><span data-stu-id="8efa7-960">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="8efa7-961">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-961">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="8efa7-962">**運用筆跡製作精彩的投影片：** 將筆跡轉換成標準圖形和文字，然後從 PowerPoint 設計工具吸取智慧的投影片設計概念。</span><span class="sxs-lookup"><span data-stu-id="8efa7-962">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="8efa7-963">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-963">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- <span data-ttu-id="8efa7-964">**符合您情境的更多圖示：** 我們新增了超過 300 個新圖示。</span><span class="sxs-lookup"><span data-stu-id="8efa7-964">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="8efa7-965">其位置：[插入] > [圖示]。</span><span class="sxs-lookup"><span data-stu-id="8efa7-965">Find them at Insert > Icons.</span></span> [<span data-ttu-id="8efa7-966">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-966">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="visio"></a><span data-ttu-id="8efa7-967">Visio</span><span class="sxs-lookup"><span data-stu-id="8efa7-967">Visio</span></span>

- <span data-ttu-id="8efa7-968">**回到犯罪場景：** 在犯罪場景調查範本中使用新的證據、室內、室外樣板，重建犯罪場景的細節。</span><span class="sxs-lookup"><span data-stu-id="8efa7-968">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

- <span data-ttu-id="8efa7-969">**在 Excel 中製作精美的 Visio 圖表：** 將資料放在工作表上，以建立流程圖或組織圖。</span><span class="sxs-lookup"><span data-stu-id="8efa7-969">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="8efa7-970">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-970">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="8efa7-971">Word</span><span class="sxs-lookup"><span data-stu-id="8efa7-971">Word</span></span>

- <span data-ttu-id="8efa7-972">**簡歷編輯器加入 LinkedIn 簡歷小幫手：** 簡歷編輯器提供特別為簡歷量身打造的文法和樣式檢查選項，讓您的寫作更準確且更專業。</span><span class="sxs-lookup"><span data-stu-id="8efa7-972">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="8efa7-973">**修正合併 3D 物件所造成的文件損毀問題：** 修正合併 3D 物件所造成的文件損毀問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-973">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="8efa7-974">**尋找您要尋找的項目：** 使用搜尋方塊來尋找文字、命令、說明等。</span><span class="sxs-lookup"><span data-stu-id="8efa7-974">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="8efa7-975">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-975">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="8efa7-976">**在生動色彩中進行共同作業：** 註解和變更都依參與者加上色彩標示，讓您可以輕鬆查看您的共同作業者。</span><span class="sxs-lookup"><span data-stu-id="8efa7-976">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="8efa7-977">**共同編輯啟用巨集的文件：** 將 docm 檔案儲存在商務用 OneDrive，並與共同作業者即時編輯。</span><span class="sxs-lookup"><span data-stu-id="8efa7-977">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

- <span data-ttu-id="8efa7-978">**共同撰寫的增強功能**：在具有追蹤修訂的文件中共同撰寫來強化 Word 效能。</span><span class="sxs-lookup"><span data-stu-id="8efa7-978">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="8efa7-979">**符合您情境的更多圖示：** 我們新增了超過 300 個新圖示。</span><span class="sxs-lookup"><span data-stu-id="8efa7-979">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="8efa7-980">其位置：[插入] > [圖示]。</span><span class="sxs-lookup"><span data-stu-id="8efa7-980">Find them at Insert > Icons.</span></span> [<span data-ttu-id="8efa7-981">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-981">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="8efa7-982">**其他人更快速看到您的變更：** 共同撰寫增強功能表示，共同作業者可較以往更快速看到您的變更。</span><span class="sxs-lookup"><span data-stu-id="8efa7-982">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="8efa7-983">**勾勒草圖：** 為文件中的 Office 圖形提供隨意的手繪外觀。</span><span class="sxs-lookup"><span data-stu-id="8efa7-983">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="8efa7-984">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-984">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="8efa7-985">**精確橡皮擦：** 從兩個橡皮擦尺寸中選擇，以修正小型筆跡缺陷。</span><span class="sxs-lookup"><span data-stu-id="8efa7-985">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="8efa7-986">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-986">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="8efa7-987">**更快速共用檔案：** 不需開啟檔案，即可從最近使用清單直接共用您的檔案。</span><span class="sxs-lookup"><span data-stu-id="8efa7-987">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="8efa7-988">**不必再來回往返瀏覽器：** 您決定開啟 Office 文件連結的方式：在瀏覽器或應用程式中開啟。</span><span class="sxs-lookup"><span data-stu-id="8efa7-988">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="8efa7-989">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-989">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="8efa7-990">**共同撰寫的增強功能**：增強共同撰寫時的可靠性。</span><span class="sxs-lookup"><span data-stu-id="8efa7-990">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="8efa7-991">**建立更易於存取的 PDF：** 建立 PDF 檔案，在儲存之前，協助工具檢查程式會指出應該修正的協助工具問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-991">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="8efa7-992">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-992">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="8efa7-993">**轉換檔案，以改善協助工具功能：** 將您的檔案升級為現代格式，讓所有人更容易存取。</span><span class="sxs-lookup"><span data-stu-id="8efa7-993">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="8efa7-994">**更安全的影片體驗：** 安全性增強功能可讓您擁有更安全的線上影片體驗。</span><span class="sxs-lookup"><span data-stu-id="8efa7-994">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="8efa7-995">深入了解</span><span class="sxs-lookup"><span data-stu-id="8efa7-995">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)





[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8efa7-998">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8efa7-998">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="8efa7-999">Access</span><span class="sxs-lookup"><span data-stu-id="8efa7-999">Access</span></span>

- <span data-ttu-id="8efa7-1000">此更新可修正 Microsoft Access 中的「更新查詢」執行時或在 SQL 中使用 UPDATE 陳述式時，可能導致錯誤「查詢已損壞」的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1000">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

- <span data-ttu-id="8efa7-1001">此更新修正可能會導致 Microsoft Access 無法識別連結的 SQL Server 資料表中的識別資料行的問題，這可能會導致不正確地將資料列報告為已刪除。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1001">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="8efa7-1002">此更新會修正使用 ADODB 的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1002">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="8efa7-1003">VB 程式碼中的記錄器物件可能會不正確地報告錯誤。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1003">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="8efa7-1004">Access 範本應不再導致資料庫中的附件欄出現故障。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1004">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="8efa7-1005">個體化範本後，您現在應該可以將附件欄新增至資料庫。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1005">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

### <a name="excel"></a><span data-ttu-id="8efa7-1006">Excel</span><span class="sxs-lookup"><span data-stu-id="8efa7-1006">Excel</span></span>

- <span data-ttu-id="8efa7-1007">解決重新命名簽名時，使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1007">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="8efa7-1008">這項變更透過利用軟體轉譯來避免特定 Intel 圖形驅動程式的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1008">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="8efa7-1009">修正對具有溢出陣列之儲存格進行資料剖析的轉換時，導致某些使用者發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1009">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="8efa7-1010">此更新可修正導致資料編輯列以預期不同的字型顯示文字的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1010">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="8efa7-1011">[資料剖析] 功能對某些地區設定可能會失敗。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1011">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="8efa7-1012">使用者在存取隱藏的命名範圍時可能會遇到錯誤。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1012">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="8efa7-1013">使用者在使用某些非英文字元集的情況下，儲存變更時可能會遇到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1013">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="8efa7-1014">解決捲動後選取儲存格時，可能導致選取錯誤儲存格的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1014">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="8efa7-1015">從不受信任的網路共用編輯受保護的檔案時，Excel 可能會發生問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1015">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="8efa7-1016">某些當地語系化版本的 [資料剖析] 功能可能會失敗。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1016">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="8efa7-1017">使用者在存取隱藏的命名範圍時可能會遇到錯誤。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1017">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="8efa7-1018">使用者在使用某些非英文字元集的情況下，儲存變更時可能會遇到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1018">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="8efa7-1019">修正某些使用者使用內嵌和連結化物件 (OLE) 時可能發生的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1019">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="8efa7-1020">我們已修正樞紐分析圖的右鍵功能表，以啟用 [顯示詳細資料] 選項。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1020">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="8efa7-1021">解決在未開啟活頁簿時，搜尋最近使用的檔案會造成當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1021">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="8efa7-1022">修正當活頁簿中有外部連結時，有些使用者可能會遇到多個彈出式視窗的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1022">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="8efa7-1023">修正操作功能表中未顯示註解命令的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1023">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="8efa7-1024">解決開啟內嵌活頁簿時，功能區自訂無法載入的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1024">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="8efa7-1025">修正 CUBEVALUE 函數有時會傳回不正確結果的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1025">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

### <a name="outlook"></a><span data-ttu-id="8efa7-1026">Outlook</span><span class="sxs-lookup"><span data-stu-id="8efa7-1026">Outlook</span></span>

- <span data-ttu-id="8efa7-1027">已解決導致在搜尋意見反應體驗中懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1027">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="8efa7-1028">解決在擷取雲端設定時，導致使用者在 Outlook 中遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1028">Addressed an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="8efa7-1029">解決導致搜尋方塊在高 DPI 模式中未正確對齊的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1029">Addressed an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="8efa7-1030">解決導致使用者在 Outlook 處理序中看到記憶體流失的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1030">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="8efa7-1031">解決在某些情況下，導致使用者看到電子郵件傳送到與顯示的 SMTP 位址不相符之地址的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1031">Addressed an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="8efa7-1032">此變更會還原在郵件標頭中檢視多行主旨的功能。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1032">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="8efa7-1033">我們已修正會防止將檔案儲存到 WebDAV 位置的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1033">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="8efa7-1034">修正 SMIME 演算法選取的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1034">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="8efa7-1035">解決導致協力廠商應用程式無法傳送電子郵件的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1035">Addressed an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="8efa7-1036">已解決導致使用者在嘗試從 [帳戶建立] 內容連絡支援服務時，看到具有 [確定] 按鈕的空白訊息方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1036">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="8efa7-1037">解決導致使用者在建立設定檔時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1037">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="8efa7-1038">解決即使將同步處理滑桿設定為較小的設定，也會導致 Outlook 非預期地同步處理所有郵件的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1038">Addressed an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="8efa7-1039">解決導致使用黑色佈景主題的使用者看到 [寄件者] 下拉式清單在白色背景上顯示白色文字的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1039">Addressed an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>

- <span data-ttu-id="8efa7-1040">已解決導致使用者在取消帳戶設定時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1040">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="8efa7-1041">解決重新命名簽名時，使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1041">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="8efa7-1042">已解決導致在某些情況下無法使用相關選項來停用標幟項目醒目提示的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1042">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="8efa7-1043">已解決導致使用者在開啟 [規則] 對話方塊時看到「在這部電腦中建立的規則和 Microsoft Exchange 上的規則衝突」提示的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1043">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="8efa7-1044">已解決導致使用者在指定無效寄件者地址時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1044">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="8efa7-1045">解決導致非常長時間的 Outlook 工作階段記憶體流失的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1045">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="8efa7-1046">解決在多個視窗中檢視相同項目時可能會導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1046">Addressed an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="8efa7-1047">解決當使用者透過鍵盤快速鍵與信箱資料夾互動時，導致明顯延遲的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1047">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="8efa7-1048">解決導致使用者無法開啟某些週期性行事曆項目執行個體的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1048">Addressed an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="8efa7-1049">解決導致使用 Exchange 2010 伺服器上信箱的使用者在將附件新增至行事曆項目時遇到問題的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1049">Addressed an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="8efa7-1050">解決導致使用者在回覆數位簽章的郵件時發生問題的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1050">Addressed an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="8efa7-1051">解決會導致會議中的 [位置] 欄位意外更新的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1051">Addressed an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="8efa7-1052">解決導致會議的位置欄位中的逗號變成分號的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1052">Addressed an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="8efa7-1053">解決導致會議位置在清除之後，又會不預期地重新加回會議的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1053">Addressed an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="8efa7-1054">解決與在巴西時區中設定的會議和約會相關的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1054">Addressed issues relating to meetings and appointments set in the Brazilia time zone.</span></span>

- <span data-ttu-id="8efa7-1055">解決當您關閉協助工具檢查程式窗格之後按 [S] 鍵時，導致使用者看到郵件意外傳送的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1055">Addressed an issue that caused users to see mails unexpectedly send when pressing the "S" key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="8efa7-1056">這會更新 Outlook 中的附件封鎖邏輯，以同時封鎖 Python 附件。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1056">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="8efa7-1057">解決導致網頁增益集存取數位版權管理郵件的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1057">Addressed an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="8efa7-1058">解決導致使用者在建立設定檔時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1058">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="8efa7-1059">解決重新命名簽名時，使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1059">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8efa7-1060">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8efa7-1060">PowerPoint</span></span>

- <span data-ttu-id="8efa7-1061">我們已修正 Shape.Paste 方法的問題：當使用者使用 Shape.Paste 方法複製並貼上圖形時，它會將選取範圍變更為貼上的圖形。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1061">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="8efa7-1062">解決在舊版 PPT 註解中使用操作功能表時可能發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1062">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

### <a name="project"></a><span data-ttu-id="8efa7-1063">Project</span><span class="sxs-lookup"><span data-stu-id="8efa7-1063">Project</span></span>

- <span data-ttu-id="8efa7-1064">發現在開啟唯讀專案時，使用者可能會收到數個訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1064">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="8efa7-1065">修正固定工期類型的 100% 工作可能會誤將其完成百分比計算為小於 100% 完成的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1065">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

- <span data-ttu-id="8efa7-1066">修正無法正確計算摘要工作日期的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1066">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="8efa7-1067">修正不先執行 OpenUndoTransaction 方法就不能觸發 OnUndoOrRedo 事件的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1067">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="8efa7-1068">Word</span><span class="sxs-lookup"><span data-stu-id="8efa7-1068">Word</span></span>

- <span data-ttu-id="8efa7-1069">我們已修正在某些情況下，儲存現有檔案永遠會導致出現 [另存新檔] 對話方塊且檔案永遠不會儲存的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1069">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="8efa7-1070">建置組塊組合管理可能會顯示無效的通知：「您已經修改樣式、建置組塊」。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1070">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

### <a name="office-suite"></a><span data-ttu-id="8efa7-1071">Office 套件</span><span class="sxs-lookup"><span data-stu-id="8efa7-1071">Office Suite</span></span>

- <span data-ttu-id="8efa7-1072">此變更可解決轉譯某些含有資料標記的散佈圖緩慢的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1072">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="8efa7-1073">此變更可解決所報告使用 Intel 整合式 GPU 圖形配接卡的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1073">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="8efa7-1074">修正相對期限只有在第一次設定時才會有效的 ODT 和 GPO 更新期限設定中的錯誤，此修正可啟用後續更新的相關期限。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1074">Fixed a bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="8efa7-1075">解決 Office 更新可能會非預期地從 Office CDN 而不是預期使用的來源 (例如本機或網路共用或 Configuration Manager 提供的位置) 下載檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1075">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="8efa7-1076">修正在 Word/Excel/PowerPoint 中開啟來自相同 SharePoint 文件庫的多個文件時，僅掃描開啟的第一個文件是否符合原則的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1076">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-february-11"></a><span data-ttu-id="8efa7-1078">版本 1908：2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="8efa7-1078">Version 1908: February 11</span></span>
<span data-ttu-id="8efa7-1079">*版本 1908 (組建 11929.20606)*</span><span class="sxs-lookup"><span data-stu-id="8efa7-1079">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="8efa7-1080">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="8efa7-1080">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8efa7-1082">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8efa7-1082">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="8efa7-1083">Excel</span><span class="sxs-lookup"><span data-stu-id="8efa7-1083">Excel</span></span>

- <span data-ttu-id="8efa7-1084">此更新已修正使用 VBA 將影像新增到圖表的頁首/頁尾時發生錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1084">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="8efa7-1085">修正在預覽列印或列印時群組方塊控制項的框線無法顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1085">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="8efa7-1086">使用者在使用某些非英文字元集的情況下，儲存變更時可能會遇到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1086">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="8efa7-1087">修正圖表標題中影像檔案大小在儲存包含圖表的活頁簿時增加的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1087">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="8efa7-1088">修正以下問題：將選取範圍與交互參照的活頁簿保持同步時，導致交互參照的活頁簿中的 DBCS 字元損毀。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1088">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="8efa7-1089">已解決使用自動調整來調整列高時，核取方塊可能收縮的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1089">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="8efa7-1090">Outlook</span><span class="sxs-lookup"><span data-stu-id="8efa7-1090">Outlook</span></span>

- <span data-ttu-id="8efa7-1091">已解決導致使用者在指定無效寄件者地址時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1091">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="8efa7-1092">已解決導致使用者處理衝突郵件時同步失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1092">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="8efa7-1093">已解決導致使用者在啟動 Outlook 時，「正在載入設定檔」畫面時停滯的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1093">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="8efa7-1094">已解決導致使用者在變更檢視時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1094">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="8efa7-1095">已解決在 Citrix 環境中檢視 30 個以上的行事曆時，導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1095">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="8efa7-1096">[此處](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)是記錄舊版問題的個別 KB。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1096">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="8efa7-1097">已解決以下問題：使用者將共用行事曆資料夾同步到 OST 時發生問題，這導致嘗試與這些資料夾互動時發生權限錯誤。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1097">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="8efa7-1098">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8efa7-1098">PowerPoint</span></span>

- <span data-ttu-id="8efa7-1099">已改善複製貼上的案例，即將 PowerPoint 投影片中的圖形複製並貼到其他投影片可能會因為異常而失敗。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1099">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="8efa7-1100">修正導致共同作業使用者之間效能較低的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1100">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="8efa7-1101">修正以下問題：當檔案以漸進式開啟時，若其中一個投影片包含多個內嵌媒體串流可能會發生問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1101">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="8efa7-1102">修正以下問題：首次啟動 PowerPoint 時，不受信任的增益集可能不會顯示安全性警告訊息列。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1102">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="8efa7-1103">Project</span><span class="sxs-lookup"><span data-stu-id="8efa7-1103">Project</span></span>

- <span data-ttu-id="8efa7-1104">修正以下問題：由於基準行事曆變更時未更新資源行事曆，而導致時程表和專案計劃之間的實際工作可能不同。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1104">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="8efa7-1105">Word</span><span class="sxs-lookup"><span data-stu-id="8efa7-1105">Word</span></span>

- <span data-ttu-id="8efa7-1106">已從遭取代的 API 移除，以修正 Word 的當機問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1106">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="8efa7-1107">Office 套件</span><span class="sxs-lookup"><span data-stu-id="8efa7-1107">Office Suite</span></span>

- <span data-ttu-id="8efa7-1108">此變更解決開啟損毀的檔案時正確呈現影像的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1108">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-january-14"></a><span data-ttu-id="8efa7-1110">版本 1908：1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="8efa7-1110">Version 1908: January 14</span></span>
<span data-ttu-id="8efa7-1111">*版本 1908 (組建 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="8efa7-1111">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="8efa7-1112">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="8efa7-1112">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="8efa7-1114">解決的問題</span><span class="sxs-lookup"><span data-stu-id="8efa7-1114">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="8efa7-1115">Excel</span><span class="sxs-lookup"><span data-stu-id="8efa7-1115">Excel</span></span>

- <span data-ttu-id="8efa7-1116">文件標題的荷蘭文按鍵提示已變更為 Alt-G。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1116">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="8efa7-1117">解決了開啟內嵌活頁簿時，功能區自訂無法載入的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1117">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="8efa7-1118">發生您無法從增益集開啟的 WPF (Windows Presentation Foundation) 表單的下拉式方塊選取項目的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1118">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="8efa7-1119">Outlook</span><span class="sxs-lookup"><span data-stu-id="8efa7-1119">Outlook</span></span>

- <span data-ttu-id="8efa7-1120">解決當使用者透過鍵盤快速鍵與信箱資料夾互動時會造成明顯延遲的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1120">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="8efa7-1121">解決使用其他寄件者時導致無法顯示原則提示的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1121">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="8efa7-1122">解決了導致使用者在更新目前狀態資訊時遇到間歇性當機的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1122">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8efa7-1123">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8efa7-1123">PowerPoint</span></span>

- <span data-ttu-id="8efa7-1124">我們已修正將投影片從一個簡報複製到另一個簡報時可能會造成母片重複的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1124">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>
- <span data-ttu-id="8efa7-1125">如果在不支援的版本中開啟含有新的新式註解的檔案，將會顯示黃色警告</span><span class="sxs-lookup"><span data-stu-id="8efa7-1125">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

### <a name="office-suite"></a><span data-ttu-id="8efa7-1126">Office 套件</span><span class="sxs-lookup"><span data-stu-id="8efa7-1126">Office Suite</span></span>

- <span data-ttu-id="8efa7-1127">修正 Office 更新訊息不以預期語言顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1127">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="8efa7-1128">自此以後，Office 更新訊息會正確符合 Windows 顯示語言。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1128">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="8efa7-1129">解決在某些情況下，如果使用者不是系統管理員且系統帳戶沒有網路連線，將無法套用更新的問題。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1129">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

> [!NOTE]
> <span data-ttu-id="8efa7-1131">如果您需要關於使用 Office 的問題協助，建議您將問題張貼在 [Microsoft Answers 論壇](https://answers.microsoft.com/)或[技術社群](https://techcommunity.microsoft.com/)，或連絡[支援](https://support.microsoft.com/contactus)。</span><span class="sxs-lookup"><span data-stu-id="8efa7-1131">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


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
