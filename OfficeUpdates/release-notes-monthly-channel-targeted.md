---
title: 每月通道版本資訊 (已設定目標)
ms.author: anankani
author: v-lislo
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為「測試人員 - 慢」對象提供關鍵新功能、修正或已知問題的最新清單
ms.openlocfilehash: 41dba1efa79735aafd74b318fd49c7c3211736e3
ms.sourcegitcommit: e9b127c7dfd80f3beb3c9aa9dadfb9e7f442c58c
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 06/04/2020
ms.locfileid: "44563673"
---
# <a name="release-notes-for-office-monthly-channel-targeted"></a><span data-ttu-id="f95b3-103">Office 每月通道的版本資訊 (已設定目標)</span><span class="sxs-lookup"><span data-stu-id="f95b3-103">Release Notes for Office Monthly Channel (Targeted)</span></span>

<span data-ttu-id="f95b3-104">本文包含 Windows 電腦版 Word、Excel、PowerPoint、Outlook、Access 和 Project 每月通道 (已設定目標) 組建的版本資訊。</span><span class="sxs-lookup"><span data-stu-id="f95b3-104">This article contains release notes for Monthly Channel (Targeted) builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="f95b3-105">我們每週都強調有趣的新功能、重要修正，以及我們想讓您知道的重大問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="f95b3-106">請注意，我們通常會在一段時間內推出功能 (有時甚至推出修正程式) 至每月通道 (已設定目標)。</span><span class="sxs-lookup"><span data-stu-id="f95b3-106">Note that we often roll out features (and sometimes even fixes) to Monthly Channel (Targeted) over a period of time.</span></span> <span data-ttu-id="f95b3-107">這樣可讓我們確保功能都運作順利，然後才推出給更廣泛的對象。</span><span class="sxs-lookup"><span data-stu-id="f95b3-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="f95b3-108">所以，如果你沒有看到下面描述的項目，不要擔心你最終會得到它。</span><span class="sxs-lookup"><span data-stu-id="f95b3-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="f95b3-109">我們會變更 Microsoft 365 應用程式的更新通道，包括新增新的更新通道 (每月企業通道)，並變更現有的更新通道名稱。</span><span class="sxs-lookup"><span data-stu-id="f95b3-109">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="f95b3-110">如需深入了解，[請閱讀本文](https://go.microsoft.com/fwlink/p/?linkid=2127441)。</span><span class="sxs-lookup"><span data-stu-id="f95b3-110">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
> - <span data-ttu-id="f95b3-111">版本資訊發佈日期可能與實際組建發行日期不相符。</span><span class="sxs-lookup"><span data-stu-id="f95b3-111">The release notes publication date may not match the actual build release date.</span></span>


[//]: # (DO NOT REMOVE)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2005-june-04"></a><span data-ttu-id="f95b3-115">版本2005：04年6月</span><span class="sxs-lookup"><span data-stu-id="f95b3-115">Version 2005: June 04</span></span>
<span data-ttu-id="f95b3-116">*版本2005（組建12827.20320）*</span><span class="sxs-lookup"><span data-stu-id="f95b3-116">*Version 2005 (Build 12827.20320)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="f95b3-118">功能更新</span><span class="sxs-lookup"><span data-stu-id="f95b3-118">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="f95b3-119">Access</span><span class="sxs-lookup"><span data-stu-id="f95b3-119">Access</span></span>

- <span data-ttu-id="f95b3-120">**請繼續進行時間！日期/時間擴充資料類型具有較佳的精確度。：** 引進新的和改進的資料類型。</span><span class="sxs-lookup"><span data-stu-id="f95b3-120">**Keep up with the times! The Date/Time Extended data type has better precision.:** Introducing a new and improved data type.</span></span>  <span data-ttu-id="f95b3-121">若要增強與 SQL 的語法相容性，以及在包含日期和時間的記錄中提高精確度和詳細資料的詳細資料，我們會在 Access 中執行 DateTime2 資料類型。</span><span class="sxs-lookup"><span data-stu-id="f95b3-121">To enhance syntax compatibility with SQL, and to increase accuracy and level of detail in records that include dates and times, we’re implementing the DateTime2 data type into Access.</span></span> <span data-ttu-id="f95b3-122">這個額外的日期 & time 資料類型會包含較大的日期範圍（0001-01-01 到9999-12-31），具有較高指定的時間精度（毫微秒，而不是秒），您可以在此提供並執行計算。</span><span class="sxs-lookup"><span data-stu-id="f95b3-122">This additional date & time data type will include a larger date range (0001-01-01 through 9999-12-31), with higher-specified time precision (nanoseconds, rather than seconds) that you will be able to provide and perform calculations on.</span></span> <span data-ttu-id="f95b3-123">若要啟用，請選取 [新增欄位 > 日期 & 時間擴充。</span><span class="sxs-lookup"><span data-stu-id="f95b3-123">To enable, select New field > Date & Time Extended.</span></span> [<span data-ttu-id="f95b3-124">深入了解</span><span class="sxs-lookup"><span data-stu-id="f95b3-124">Learn more</span></span>](https://support.office.com/article/708c32da-a052-4cc2-9850-9851042e0024)

### <a name="excel"></a><span data-ttu-id="f95b3-125">Excel</span><span class="sxs-lookup"><span data-stu-id="f95b3-125">Excel</span></span>

- <span data-ttu-id="f95b3-126">**在 Excel 內從 POWER BI 建立資料集的 PivotTables：** 您可以在 Excel 中建立連接至儲存于 Power BI 之資料集的 PivotTables，只需按幾下滑鼠即可。</span><span class="sxs-lookup"><span data-stu-id="f95b3-126">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span><span data-ttu-id="f95b3-127">這樣做可讓您最適合 PivotTables 和 Power BI。</span><span class="sxs-lookup"><span data-stu-id="f95b3-127"> Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="f95b3-128">使用您的安全 Power BI 資料集的 PivotTables，計算、匯總及分析您的資料。</span><span class="sxs-lookup"><span data-stu-id="f95b3-128">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span>

### <a name="outlook"></a><span data-ttu-id="f95b3-129">Outlook</span><span class="sxs-lookup"><span data-stu-id="f95b3-129">Outlook</span></span>

- <span data-ttu-id="f95b3-130">**可立即重新開啟先前 Outlook 會話之專案的選項：** 我們新增了一個選項，可快速重新開啟先前 Outlook 會話中的專案。</span><span class="sxs-lookup"><span data-stu-id="f95b3-130">**Option to quickly reopen items from previous Outlook session:** We added an option to quickly reopen items from a previous Outlook session.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f95b3-133">解決的問題</span><span class="sxs-lookup"><span data-stu-id="f95b3-133">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="f95b3-134">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f95b3-134">PowerPoint</span></span>

- <span data-ttu-id="f95b3-135">這會修正使用者在檔案中同時有新式和舊版批註時的損毀，因此會觸發對批註的升級。</span><span class="sxs-lookup"><span data-stu-id="f95b3-135">This fixes a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>


### <a name="office-suite"></a><span data-ttu-id="f95b3-136">Office 套件</span><span class="sxs-lookup"><span data-stu-id="f95b3-136">Office Suite</span></span>

- <span data-ttu-id="f95b3-137">我們已解決 ValidateInstall 失敗率問題，方法是將 Bing 載入項預設安裝驗證設定為 true，並考慮 MSI 傳回成功為安裝成功。</span><span class="sxs-lookup"><span data-stu-id="f95b3-137">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-may-29"></a><span data-ttu-id="f95b3-139">版本2005：5月29日</span><span class="sxs-lookup"><span data-stu-id="f95b3-139">Version 2005: May 29</span></span>
<span data-ttu-id="f95b3-140">*版本2005（組建12827.20268）*</span><span class="sxs-lookup"><span data-stu-id="f95b3-140">*Version 2005 (Build 12827.20268)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="f95b3-142">功能更新</span><span class="sxs-lookup"><span data-stu-id="f95b3-142">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="f95b3-143">Excel</span><span class="sxs-lookup"><span data-stu-id="f95b3-143">Excel</span></span>

- <span data-ttu-id="f95b3-144">**工作表視圖：** 在 Excel desktop 中與其他人共同作業時排序/篩選。</span><span class="sxs-lookup"><span data-stu-id="f95b3-144">**Sheet View:** Sort/filter while collaborating with others in Excel desktop.</span></span>

### <a name="outlook"></a><span data-ttu-id="f95b3-145">Outlook</span><span class="sxs-lookup"><span data-stu-id="f95b3-145">Outlook</span></span>

- <span data-ttu-id="f95b3-146">**新增至 Outlook toast 通知的其他按鈕：** 快速動作按鈕現在會出現在 Windows 10 上執行 Outlook 的 Outlook toast 通知中。</span><span class="sxs-lookup"><span data-stu-id="f95b3-146">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f95b3-149">解決的問題</span><span class="sxs-lookup"><span data-stu-id="f95b3-149">Resolved issues</span></span>



### <a name="outlook"></a><span data-ttu-id="f95b3-150">Outlook</span><span class="sxs-lookup"><span data-stu-id="f95b3-150">Outlook</span></span>

- <span data-ttu-id="f95b3-151">解決的問題導致 Windows 10 伺服器版本的使用者看到警告防毒程式狀態：無效。</span><span class="sxs-lookup"><span data-stu-id="f95b3-151">Addressed an issue that caused users of Windows 10 server versions to see the warning  Antivirus status: Invalid.</span></span> <span data-ttu-id="f95b3-152">此版本的 Windows 支援防病毒偵測，但即使已正確安裝防毒軟體，仍未找到防毒軟體。</span><span class="sxs-lookup"><span data-stu-id="f95b3-152">This version of Windows supports antivirus detection, but no antivirus was found despite having anti virus correctly installed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="f95b3-153">Office 套件</span><span class="sxs-lookup"><span data-stu-id="f95b3-153">Office Suite</span></span>

- <span data-ttu-id="f95b3-154">Office 主應用程式在 windows 中已崩潰，當登錄機碼 HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth 設定為0時，便會啟用增益集。</span><span class="sxs-lookup"><span data-stu-id="f95b3-154">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="f95b3-155">這種變更可修正此問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-155">This change would fix this issue.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-may-21"></a><span data-ttu-id="f95b3-157">版本2005：5月21日</span><span class="sxs-lookup"><span data-stu-id="f95b3-157">Version 2005: May 21</span></span>
<span data-ttu-id="f95b3-158">*版本2005（組建12827.20210）*</span><span class="sxs-lookup"><span data-stu-id="f95b3-158">*Version 2005 (Build 12827.20210)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="f95b3-160">功能更新</span><span class="sxs-lookup"><span data-stu-id="f95b3-160">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="f95b3-161">Excel</span><span class="sxs-lookup"><span data-stu-id="f95b3-161">Excel</span></span>

- <span data-ttu-id="f95b3-162">**使用 Excel 資料類型從 POWER BI 取得組織資料：** 您可以使用 Excel 資料類型插入組織中的資料。</span><span class="sxs-lookup"><span data-stu-id="f95b3-162">**Get Organization Data from Power BI using Excel Data Types:** You can insert data from your Organization using Excel Data Types.</span></span> <span data-ttu-id="f95b3-163">轉換活頁簿中的儲存格並取得其他資訊，並隨時重新整理資料！</span><span class="sxs-lookup"><span data-stu-id="f95b3-163">Convert a cell in your workbook and get additional information, and refresh the data anytime you need!</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f95b3-166">解決的問題</span><span class="sxs-lookup"><span data-stu-id="f95b3-166">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="f95b3-167">Excel</span><span class="sxs-lookup"><span data-stu-id="f95b3-167">Excel</span></span>

- <span data-ttu-id="f95b3-168">已修正此問題：使用 Ctrl + Shift + 箭號鍵，在 Excel 視窗透過團隊共用時，Excel 可能會停止回應。</span><span class="sxs-lookup"><span data-stu-id="f95b3-168">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>


- <span data-ttu-id="f95b3-169">在某些情況下，按一下相同活頁簿中某個位置的超連結，就會隱藏該活頁簿。</span><span class="sxs-lookup"><span data-stu-id="f95b3-169">In some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>


### <a name="outlook"></a><span data-ttu-id="f95b3-170">Outlook</span><span class="sxs-lookup"><span data-stu-id="f95b3-170">Outlook</span></span>

- <span data-ttu-id="f95b3-171">解決 [回復/轉寄] 標籤的 clp 審核事件問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-171">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>


- <span data-ttu-id="f95b3-172">解決了使用者從系統管理員通知提交意見反應時遇到損毀的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-172">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-may-14"></a><span data-ttu-id="f95b3-174">版本2005：5月14日</span><span class="sxs-lookup"><span data-stu-id="f95b3-174">Version 2005: May 14</span></span>
<span data-ttu-id="f95b3-175">*版本2005（組建12827.20160）*</span><span class="sxs-lookup"><span data-stu-id="f95b3-175">*Version 2005 (Build 12827.20160)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="f95b3-177">功能更新</span><span class="sxs-lookup"><span data-stu-id="f95b3-177">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="f95b3-178">Excel</span><span class="sxs-lookup"><span data-stu-id="f95b3-178">Excel</span></span>

- <span data-ttu-id="f95b3-179">**自動套用或建議敏感度標籤：** Office 可以建議或根據偵測到的敏感內容自動套用敏感度標籤。</span><span class="sxs-lookup"><span data-stu-id="f95b3-179">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f95b3-180">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f95b3-180">PowerPoint</span></span>

- <span data-ttu-id="f95b3-181">**不需要簡報導覽裝置：您的 earbuds 包括：** 使用表面 Earbuds 來控制您的 PowerPoint 簡報。</span><span class="sxs-lookup"><span data-stu-id="f95b3-181">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="f95b3-182">重要：您必須在適用于 Windows 10 的「表面音訊」應用程式中搭配您的 Surface Earbuds，以便使用筆勢控制簡報。</span><span class="sxs-lookup"><span data-stu-id="f95b3-182">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="f95b3-183">在 Windows 10 上開始使用表面音訊應用程式的指示可于這裡取得。</span><span class="sxs-lookup"><span data-stu-id="f95b3-183">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="f95b3-184">深入了解</span><span class="sxs-lookup"><span data-stu-id="f95b3-184">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

- <span data-ttu-id="f95b3-185">**自動套用或建議敏感度標籤：** Office 可以建議或根據偵測到的敏感內容自動套用敏感度標籤。</span><span class="sxs-lookup"><span data-stu-id="f95b3-185">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="word"></a><span data-ttu-id="f95b3-186">Word</span><span class="sxs-lookup"><span data-stu-id="f95b3-186">Word</span></span>

- <span data-ttu-id="f95b3-187">**自動套用或建議敏感度標籤：** Office 可以建議或根據偵測到的敏感內容自動套用敏感度標籤。</span><span class="sxs-lookup"><span data-stu-id="f95b3-187">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f95b3-190">解決的問題</span><span class="sxs-lookup"><span data-stu-id="f95b3-190">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="f95b3-191">Excel</span><span class="sxs-lookup"><span data-stu-id="f95b3-191">Excel</span></span>

- <span data-ttu-id="f95b3-192">已增加搭配圖表使用的 [自訂誤差線] 對話方塊上儲存格參照 [編輯] 控制項的大小。</span><span class="sxs-lookup"><span data-stu-id="f95b3-192">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>

- <span data-ttu-id="f95b3-193">修正圖表資料表無法正確呈現日期座標軸中的值的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-193">Fixed an issue where chart data table could render values in a date axis incorrectly.</span></span>

- <span data-ttu-id="f95b3-194">修正使用 [頁面配置] 或 [分頁預覽] 之後無法停用分頁符號的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-194">Fixed an issue where page breaks could not be disabled after going into Page Layout or Page Break Preview.</span></span>

- <span data-ttu-id="f95b3-195">修正隱藏和取消隱藏具有系列資料的欄之後，圖表線條樣式可能會遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-195">Fixed an issue where chart line styles could be lost after hiding and unhiding columns with series data.</span></span>

- <span data-ttu-id="f95b3-196">已修正此問題：在篩選的清單中插入欄所需的時間會超出預期。</span><span class="sxs-lookup"><span data-stu-id="f95b3-196">Fixed an issue where inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="f95b3-197">修正列印時表單控制項的核取方塊縮放問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-197">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="f95b3-198">已修正此問題：如果檔路徑過長，外部連結會在重新開啟檔案後停止運作。</span><span class="sxs-lookup"><span data-stu-id="f95b3-198">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="f95b3-199">在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。</span><span class="sxs-lookup"><span data-stu-id="f95b3-199">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="f95b3-200">在某些情況下，Application.Evaluate (VBA) 無法在使用者定義的函式中運作。</span><span class="sxs-lookup"><span data-stu-id="f95b3-200">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="f95b3-201">在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。</span><span class="sxs-lookup"><span data-stu-id="f95b3-201">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="f95b3-202">此變更會修正設定格式化的條件 (CF) 資訊無法正確儲存到 XLSB 檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-202">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

- <span data-ttu-id="f95b3-203">這項變更修正了即使 LINEST 函式傳回正確的值，圖表趨勢線的 R 平方值 (在強制 y 截距的情況下) 仍然不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-203">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>

- <span data-ttu-id="f95b3-204">此變更修正了自訂圖表趨勢線格式不一定會儲存的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-204">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

- <span data-ttu-id="f95b3-205">當您使用舊版的「共用活頁簿」模式嘗試為活頁簿的新工作表上列出變更時，就會發生損毀。</span><span class="sxs-lookup"><span data-stu-id="f95b3-205">A crash could occur when trying to list changes on a new sheet for a workbook using legacy"Shared Workbook" mode.</span></span>

- <span data-ttu-id="f95b3-206">修正啟用 [負值以補色顯示] 選項後，可能無法儲存樞紐分析表中的自訂格式設定的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-206">Fixed the issue where custom formatting in Pivot charts may not be saved when the "Invert if negative" option was enabled.</span></span>

- <span data-ttu-id="f95b3-207">修正如果選取 [負值以補色顯示] 選項，可能無法儲存樞紐分析表中單一資料點的自訂格式設定的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-207">Fixed an issue where custom formatting for a single data point in a Pivot chart was not saved if the "Invert if negative" option was selected.</span></span>

- <span data-ttu-id="f95b3-208">這項變更修正在 CSV 檔案中上傳 '@' 字元時，會導致將 '@' 字元之後的字串轉換成公式的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-208">This change fixes an issue where the '@' character uploaded in a CSV file, would result in the string after the '@' character to be converted to a formula.</span></span>

- <span data-ttu-id="f95b3-209">修正無法正確捨入 SEQUENCE 函數中十進位值的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-209">Fixed an issue where decimal values in the SEQUENCE function were not rounded correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="f95b3-210">OneNote</span><span class="sxs-lookup"><span data-stu-id="f95b3-210">OneNote</span></span>

- <span data-ttu-id="f95b3-211">修正將分行符號儲存為垂直 Tab 的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-211">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="f95b3-212">Outlook</span><span class="sxs-lookup"><span data-stu-id="f95b3-212">Outlook</span></span>

- <span data-ttu-id="f95b3-213">解決會導致使用者無法將個人連絡人群組新增為會議出席者的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-213">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>

- <span data-ttu-id="f95b3-214">已修正此問題：已停用 Office 功能區中群組行事曆的 [分類] 按鈕。</span><span class="sxs-lookup"><span data-stu-id="f95b3-214">Fixed an issue where the categorize button for group calendars in the Office Ribbon was disabled.</span></span>

- <span data-ttu-id="f95b3-215">已解決在 Windows 更新後，開啟儲存在本機的 msg 或 .oft 檔案會導致 Outlook 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-215">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="f95b3-216">修正了企業客戶沒有執行或無法使用群組資料夾的問題，該問題會導致 Outlook 顯示「沒有回應」的訊息。</span><span class="sxs-lookup"><span data-stu-id="f95b3-216">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

- <span data-ttu-id="f95b3-217">解決的問題導致很長的 safelinks，使用者在 Outlook 桌面用戶端中按下時無法載入，因為截斷。</span><span class="sxs-lookup"><span data-stu-id="f95b3-217">Addressed an issue that caused very long safelinks that users clicked on in the Outlook Desktop client to fail to load due to truncation.</span></span>

- <span data-ttu-id="f95b3-218">修正當與伺服器同步處理時，名稱中包含 DBCS (雙位元組字元集) 字元的 Outlook 資料夾會間斷消失的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-218">Fixed an issue where Outlook folders with names containing DBCS (Double Byte Character Set) characters would intermittently disappear when synchronizing with the server.</span></span> <span data-ttu-id="f95b3-219">為此，必須為 Outlook 設定 IMAP 帳戶，並在地區設定設定為日文的系統上執行。</span><span class="sxs-lookup"><span data-stu-id="f95b3-219">For this to happen, Outlook had to be configured with an IMAP account and running on a system with the locale set to Japanese.</span></span>

- <span data-ttu-id="f95b3-220">解決此問題導致針對使用者主要信箱以外的信箱所建立的刪除規則失效。</span><span class="sxs-lookup"><span data-stu-id="f95b3-220">Addressed an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>

- <span data-ttu-id="f95b3-221">解決當轉寄加密的郵件時，導致附件被刪除的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-221">Addressed an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

- <span data-ttu-id="f95b3-222">解決了導致會議超過2個月以上的問題，使其無法在排程助理中顯示會議主旨。</span><span class="sxs-lookup"><span data-stu-id="f95b3-222">Addressed an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>

- <span data-ttu-id="f95b3-223">解決會導致使用者在轉寄大型 HTML 郵件時，看到郵件內文截斷的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-223">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="f95b3-224">新增透過群組原則強制執行 S/MIME預設登入設定的功能。</span><span class="sxs-lookup"><span data-stu-id="f95b3-224">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f95b3-225">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f95b3-225">PowerPoint</span></span>

- <span data-ttu-id="f95b3-226">已修正問題：如果使用者建立了註解，但未張貼就關閉 [註解] 窗格，然後開啟新視窗、瀏覽多張投影片並關閉視窗，最後再開啟原始簡報中的 [註解] 窗格，將導致無法使用草稿註解。</span><span class="sxs-lookup"><span data-stu-id="f95b3-226">Fixed an issue where if a user created a comment without posting it and closed the Comments pane, then opened a new window, navigated through multiple slides and, closed the window, and finally re-opened the Comments pane in the original presentation, the draft comments would not be available.</span></span>

- <span data-ttu-id="f95b3-227">修正了將滑鼠游標移到星號 (\*) 符號，但不會顯示上一次更新文件的日期和使用者姓名。</span><span class="sxs-lookup"><span data-stu-id="f95b3-227">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="project"></a><span data-ttu-id="f95b3-228">Project</span><span class="sxs-lookup"><span data-stu-id="f95b3-228">Project</span></span>

- <span data-ttu-id="f95b3-229">在表單檢視中編輯前置/後續任務資料時，會觸發額外的 ProjectBeforeTaskChange 事件。</span><span class="sxs-lookup"><span data-stu-id="f95b3-229">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="f95b3-230">修正變更連結至 SharePoint 工作清單之專案的面板狀態欄位時，Project 可能當機的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-230">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>

- <span data-ttu-id="f95b3-231">修正儲存使用舊版 Project 建立的專案時，Project 可能當機的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-231">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="f95b3-232">已修正此問題：如果 Project 已連接至 Project Web App，而且小數點分隔符號是逗號，則新增 Lag 時 TaskDependencies Add 方法會失敗。</span><span class="sxs-lookup"><span data-stu-id="f95b3-232">Fixed an issue where if Project is connected to Project Web App and the decimal separator is a comma, TaskDependencies Add method fails when Lag is added.</span></span>


### <a name="word"></a><span data-ttu-id="f95b3-233">Word</span><span class="sxs-lookup"><span data-stu-id="f95b3-233">Word</span></span>

- <span data-ttu-id="f95b3-234">修正在 [共同作業] 模式時，在文件中插入註解並不總是成功的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-234">Fixed an issue where inserting comments on a document in collaboration mode would not always work.</span></span>

- <span data-ttu-id="f95b3-235">此變更修正在按一下 @ 提及時，[人員卡片] 會閃動的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-235">This change fixes an issue where the People card would flash if the @ mention was clicked.</span></span>

- <span data-ttu-id="f95b3-236">啟用「顯示書簽」選項卻不會顯示書簽。</span><span class="sxs-lookup"><span data-stu-id="f95b3-236">Enabling the option "Show bookmarks" would not display bookmarks.</span></span> <span data-ttu-id="f95b3-237">已修正這個問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-237">This has been fixed.</span></span>

- <span data-ttu-id="f95b3-238">修正問題：關閉具有草稿註解的文件時，會在不儲存草稿註解的情況下，提示使用者是否要關閉文件。</span><span class="sxs-lookup"><span data-stu-id="f95b3-238">Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments.</span></span> <span data-ttu-id="f95b3-239">取消提示會關閉文件，而不是保持文件開啟。</span><span class="sxs-lookup"><span data-stu-id="f95b3-239">Cancelling the prompt would close the document rather than leaving it open.</span></span>

- <span data-ttu-id="f95b3-240">我們已修正複製及貼上標題的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-240">We fixed an issue in copying and pasting headings.</span></span>

- <span data-ttu-id="f95b3-241">已修正此問題：翻譯已張貼的批註會導致「插入已轉譯的文字失敗」錯誤。</span><span class="sxs-lookup"><span data-stu-id="f95b3-241">Fixed an issue where translating a posted comment would result in the error 'Inserting translated text failed'.</span></span>

- <span data-ttu-id="f95b3-242">此變更可修正此問題：如果啟用此選項，則不會顯示超連結的文字：「顯示欄位代碼而非其值」。</span><span class="sxs-lookup"><span data-stu-id="f95b3-242">This change fixes an issue where text with hyperlinks may not display if the option: "Show field codes instead of their values" was enabled.</span></span>

- <span data-ttu-id="f95b3-243">在 Web 檢視/沉浸式閱讀器中，如果已在檢視中，按一下提示會捲動到最上方。</span><span class="sxs-lookup"><span data-stu-id="f95b3-243">In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view.</span></span> <span data-ttu-id="f95b3-244">已修正這個問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-244">This has been fixed.</span></span>

- <span data-ttu-id="f95b3-245">我們已修正一個問題，當嘗試使用新名稱儲存包含巨集的檔案時，無論使用者輸入什麼名稱，都會導致該檔案以.docx 副檔名和檔案名稱 WRO0004.docx 儲存，進而導致文件無法使用。</span><span class="sxs-lookup"><span data-stu-id="f95b3-245">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with .docx extension and the filename WRO0004.docx, regardless of what the user entered, rendering the document unusable.</span></span>

### <a name="office-suite"></a><span data-ttu-id="f95b3-246">Office 套件</span><span class="sxs-lookup"><span data-stu-id="f95b3-246">Office Suite</span></span>

- <span data-ttu-id="f95b3-247">當使用者獲得只將其移至小組的原則時，他們仍然可以使用商務用 Skype Outlook 增益集來排程會議。</span><span class="sxs-lookup"><span data-stu-id="f95b3-247">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span>  <span data-ttu-id="f95b3-248">在此更新之後，用戶端將無法再排程商務用 Skype 會議。用戶端讀取指出使用者只有小組的原則，並進入僅限會議加入模式。</span><span class="sxs-lookup"><span data-stu-id="f95b3-248">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span>  <span data-ttu-id="f95b3-249">此外，商務用 Skype Outlook 增益集會在啟動時不會自行啟用（如果它看到商務用 Skype 用戶端為會議僅限加入模式）。</span><span class="sxs-lookup"><span data-stu-id="f95b3-249">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="f95b3-250">此更新解決了 Microsoft Office 中的一個問題：可能無法在執行時期正確找到 Visual Basic for Applications 專案，這些專案的參照預期透搜尋 PATH 環境變數指定的位置來找到，進而導致VBA 執行時期錯誤。</span><span class="sxs-lookup"><span data-stu-id="f95b3-250">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="f95b3-251">此更新修正了 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。</span><span class="sxs-lookup"><span data-stu-id="f95b3-251">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-may-11"></a><span data-ttu-id="f95b3-253">版本 2004：5 月 11 日</span><span class="sxs-lookup"><span data-stu-id="f95b3-253">Version 2004: May 11</span></span>
<span data-ttu-id="f95b3-254">*版本 2004 (組建 12730.20270)*</span><span class="sxs-lookup"><span data-stu-id="f95b3-254">*Version 2004 (Build 12730.20270)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="f95b3-256">功能更新</span><span class="sxs-lookup"><span data-stu-id="f95b3-256">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="f95b3-257">Excel</span><span class="sxs-lookup"><span data-stu-id="f95b3-257">Excel</span></span>

- <span data-ttu-id="f95b3-258">**使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦。</span><span class="sxs-lookup"><span data-stu-id="f95b3-258">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="outlook"></a><span data-ttu-id="f95b3-259">Outlook</span><span class="sxs-lookup"><span data-stu-id="f95b3-259">Outlook</span></span>

- <span data-ttu-id="f95b3-260">**電子郵件中的改良連結：** 當您包含檔案的連結時，檔案名會取代 URL。</span><span class="sxs-lookup"><span data-stu-id="f95b3-260">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="f95b3-261">您可以變更權限，讓所有收件者都能存取。</span><span class="sxs-lookup"><span data-stu-id="f95b3-261">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="f95b3-262">深入了解</span><span class="sxs-lookup"><span data-stu-id="f95b3-262">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)<br /><span data-ttu-id="f95b3-263">在[部落格文章](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="f95b3-263">See details in [blog post](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span></span>

- <span data-ttu-id="f95b3-264">**使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦。</span><span class="sxs-lookup"><span data-stu-id="f95b3-264">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f95b3-265">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f95b3-265">PowerPoint</span></span>

- <span data-ttu-id="f95b3-266">**使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦。</span><span class="sxs-lookup"><span data-stu-id="f95b3-266">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>  [<span data-ttu-id="f95b3-267">深入了解</span><span class="sxs-lookup"><span data-stu-id="f95b3-267">Learn more</span></span>](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a><span data-ttu-id="f95b3-268">Word</span><span class="sxs-lookup"><span data-stu-id="f95b3-268">Word</span></span>

- <span data-ttu-id="f95b3-269">**使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦。</span><span class="sxs-lookup"><span data-stu-id="f95b3-269">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f95b3-272">解決的問題</span><span class="sxs-lookup"><span data-stu-id="f95b3-272">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="f95b3-273">Outlook</span><span class="sxs-lookup"><span data-stu-id="f95b3-273">Outlook</span></span>

- <span data-ttu-id="f95b3-274">解決在顯示快顯通知時，使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-274">Addressed an issue that caused users to experience a crash when displaying toast notifications.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-may-04"></a><span data-ttu-id="f95b3-276">版本 2004：5 月 4 日</span><span class="sxs-lookup"><span data-stu-id="f95b3-276">Version 2004: May 04</span></span>
<span data-ttu-id="f95b3-277">*版本 2004 (組建 12730.20250)*</span><span class="sxs-lookup"><span data-stu-id="f95b3-277">*Version 2004 (Build 12730.20250)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="f95b3-279">功能更新</span><span class="sxs-lookup"><span data-stu-id="f95b3-279">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="f95b3-280">Outlook</span><span class="sxs-lookup"><span data-stu-id="f95b3-280">Outlook</span></span>

- <span data-ttu-id="f95b3-281">**更好的結果—瞬間：** 我們更新了搜尋體驗，讓這個版本比以往更聰明、更快速，且更可靠。</span><span class="sxs-lookup"><span data-stu-id="f95b3-281">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="f95b3-282">深入了解</span><span class="sxs-lookup"><span data-stu-id="f95b3-282">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="f95b3-283">**IT 系統管理員的事件通知：** Microsoft 365 租用戶全域系統管理員和 Office 應用程式系統會在 Windows 版 Outlook 的新右側面板中收到影響其使用者的 Outlook 和 O365 Exchange 事件通知。</span><span class="sxs-lookup"><span data-stu-id="f95b3-283">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f95b3-286">解決的問題</span><span class="sxs-lookup"><span data-stu-id="f95b3-286">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="f95b3-287">Office 套件</span><span class="sxs-lookup"><span data-stu-id="f95b3-287">Office Suite</span></span>

- <span data-ttu-id="f95b3-288">此更新修正了 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。</span><span class="sxs-lookup"><span data-stu-id="f95b3-288">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-april-29"></a><span data-ttu-id="f95b3-290">版本 2004：4 月 29 日</span><span class="sxs-lookup"><span data-stu-id="f95b3-290">Version 2004: April 29</span></span>
<span data-ttu-id="f95b3-291">*版本 2004 (組建 12730.20236)*</span><span class="sxs-lookup"><span data-stu-id="f95b3-291">*Version 2004 (Build 12730.20236)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="f95b3-293">功能更新</span><span class="sxs-lookup"><span data-stu-id="f95b3-293">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="f95b3-294">Outlook</span><span class="sxs-lookup"><span data-stu-id="f95b3-294">Outlook</span></span>

- <span data-ttu-id="f95b3-295">**協助保護群組中的資料：** 建立群組時所選擇的「敏感度」標籤會套用到群組電子郵件、文件及小組網站。</span><span class="sxs-lookup"><span data-stu-id="f95b3-295">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f95b3-298">解決的問題</span><span class="sxs-lookup"><span data-stu-id="f95b3-298">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="f95b3-299">Outlook</span><span class="sxs-lookup"><span data-stu-id="f95b3-299">Outlook</span></span>

- <span data-ttu-id="f95b3-300">解決導致 Outlook 在某些 Windows 組建上當機的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-300">Addresses an issue that caused Outlook to crash on some builds of Windows.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-april-25"></a><span data-ttu-id="f95b3-302">版本 2004：4 月 25 日</span><span class="sxs-lookup"><span data-stu-id="f95b3-302">Version 2004: April 25</span></span>
<span data-ttu-id="f95b3-303">*版本 2004 (組建 12730.20206)*</span><span class="sxs-lookup"><span data-stu-id="f95b3-303">*Version 2004 (Build 12730.20206)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f95b3-305">解決的問題</span><span class="sxs-lookup"><span data-stu-id="f95b3-305">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="f95b3-306">Outlook</span><span class="sxs-lookup"><span data-stu-id="f95b3-306">Outlook</span></span>

- <span data-ttu-id="f95b3-307">已解決在 Windows 更新後，開啟儲存在本機的 msg 或 .oft 檔案會導致 Outlook 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-307">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

### <a name="project"></a><span data-ttu-id="f95b3-308">Project</span><span class="sxs-lookup"><span data-stu-id="f95b3-308">Project</span></span>

- <span data-ttu-id="f95b3-309">已修正如果您使用的是連線至 Project Web App 的 Project，且小數分隔符號是逗號，當您嘗試將延遲新增至相依性時，TaskDependencies Add 方法會失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-309">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>


### <a name="office-suite"></a><span data-ttu-id="f95b3-310">Office 套件</span><span class="sxs-lookup"><span data-stu-id="f95b3-310">Office Suite</span></span>

- <span data-ttu-id="f95b3-311">此修正可解決同時防止限制存取和保護設有密碼之檔案的錯誤。</span><span class="sxs-lookup"><span data-stu-id="f95b3-311">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-april-21"></a><span data-ttu-id="f95b3-313">版本 2004：4 月 21 日</span><span class="sxs-lookup"><span data-stu-id="f95b3-313">Version 2004: April 21</span></span>
<span data-ttu-id="f95b3-314">版本 2004 (組建 12730.20182)\*\*</span><span class="sxs-lookup"><span data-stu-id="f95b3-314">*Version 2004 (Build 12730.20182)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f95b3-316">解決的問題</span><span class="sxs-lookup"><span data-stu-id="f95b3-316">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="f95b3-317">Outlook</span><span class="sxs-lookup"><span data-stu-id="f95b3-317">Outlook</span></span>

- <span data-ttu-id="f95b3-318">解決導致資料夾窗格寬度意外變更的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-318">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="f95b3-319">解決導致使用者在退出 Outlook 時遇到掛斷的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-319">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-april-15"></a><span data-ttu-id="f95b3-321">版本 2004：4 月 15 日</span><span class="sxs-lookup"><span data-stu-id="f95b3-321">Version 2004: April 15</span></span>
<span data-ttu-id="f95b3-322">*版本 2004 (組建 12730.20150)*</span><span class="sxs-lookup"><span data-stu-id="f95b3-322">*Version 2004 (Build 12730.20150)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="f95b3-324">功能更新</span><span class="sxs-lookup"><span data-stu-id="f95b3-324">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="f95b3-325">Excel</span><span class="sxs-lookup"><span data-stu-id="f95b3-325">Excel</span></span>

- <span data-ttu-id="f95b3-326">**Facebook 連接器支援即將結束：** 於 2020 年 4 月起，Excel 就不再支援使用 Facebook 連接器的外部資料連線。</span><span class="sxs-lookup"><span data-stu-id="f95b3-326">**Facebook connector support is ending:** Starting in April 2020, Excel will no longer support external data connections that use the Facebook connector.</span></span>

### <a name="outlook"></a><span data-ttu-id="f95b3-327">Outlook</span><span class="sxs-lookup"><span data-stu-id="f95b3-327">Outlook</span></span>

- <span data-ttu-id="f95b3-328">**在 Outlook 中撰寫郵件時有新的選項可停用 @ 提及建議：** 您是否覺得 @ 提及的選擇器很煩人，一點都不好用？</span><span class="sxs-lookup"><span data-stu-id="f95b3-328">**New option to disable @ mention suggestions when composing mail in Outlook:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="f95b3-329">現在您可以視需要將其關閉了。</span><span class="sxs-lookup"><span data-stu-id="f95b3-329">Now you can turn it off if you prefer.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f95b3-330">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f95b3-330">PowerPoint</span></span>

- <span data-ttu-id="f95b3-331">**在簡報時同步處理變更：** 即使簡報處於投影片放映模式，仍可即時同步處理所做的變更。</span><span class="sxs-lookup"><span data-stu-id="f95b3-331">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="f95b3-332">Word</span><span class="sxs-lookup"><span data-stu-id="f95b3-332">Word</span></span>

- <span data-ttu-id="f95b3-333">**標註私人複本：** 製作共用文件的私人複本，以建立只有您本人能夠看到的手寫筆記。</span><span class="sxs-lookup"><span data-stu-id="f95b3-333">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="f95b3-334">若要開始使用，請移至 [檢視] > [建立私人複本]。</span><span class="sxs-lookup"><span data-stu-id="f95b3-334">Go to View > Create a Private Copy to get started.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f95b3-337">解決的問題</span><span class="sxs-lookup"><span data-stu-id="f95b3-337">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="f95b3-338">Access</span><span class="sxs-lookup"><span data-stu-id="f95b3-338">Access</span></span>

- <span data-ttu-id="f95b3-339">已修正工作窗格中表格的重新調整及重新整理問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-339">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

- <span data-ttu-id="f95b3-340">修正國際版 Access 在使用者介面中顯示英文字串的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-340">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="f95b3-341">Excel</span><span class="sxs-lookup"><span data-stu-id="f95b3-341">Excel</span></span>

- <span data-ttu-id="f95b3-342">已修正在工作表上選取儲存格範圍會導致只選取單一儲存格的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-342">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="f95b3-343">在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。</span><span class="sxs-lookup"><span data-stu-id="f95b3-343">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="f95b3-344">已修正在複製含有樞紐分析表的工作表後，會於某些情況下導致 Excel 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-344">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="f95b3-345">在某些情況下，Application.Evaluate (VBA) 無法在使用者定義的函式中運作。</span><span class="sxs-lookup"><span data-stu-id="f95b3-345">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="f95b3-346">修正使用者在以程式設計方式編輯大量儲存格範圍時可能遇到的效能問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-346">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>

- <span data-ttu-id="f95b3-347">修正以日文環境開啟 CSV 檔案時發生的效能問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-347">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

- <span data-ttu-id="f95b3-348">已修正插入使用者定義的圖表範本來作為預設值會導致其儲存為直條圖的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-348">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="f95b3-349">已修正當基礎資料儲存格沒有標題時，圖表上的資料標籤會以空白顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-349">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="f95b3-350">已修正在為含有 X 軸範圍的圖表縮減大小時，可能會導致 Excel 停止回應的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-350">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="f95b3-351">已修正已啟用 R1C1 儲存格參照且正在共同撰寫/共用的 Excel 工作表，在將游標移到 [使用者目前狀態] 圖示上方時不會以 R1C1 模式顯示作用中儲存格的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-351">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

- <span data-ttu-id="f95b3-352">此變更解決了處理格式錯誤或無效通訊協定資訊影像時所導致的延遲問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-352">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="f95b3-353">Outlook</span><span class="sxs-lookup"><span data-stu-id="f95b3-353">Outlook</span></span>

- <span data-ttu-id="f95b3-354">此變更解決了處理格式錯誤或無效通訊協定資訊影像時所導致的延遲問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-354">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="f95b3-355">此變更修正了電子郵件草稿最新變更未更新的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-355">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="f95b3-356">已修正在檔案上按一下滑鼠右鍵並使用「傳送到」功能無法運作的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-356">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="f95b3-357">已解決會導致代理人在不同機器上所看到的共用信箱有不同資料夾階層的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-357">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="f95b3-358">已解決會導致類別有時候會從電子郵件訊息中消失的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-358">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="f95b3-359">已解決在變更機器上的時區時，會導致某些提醒無法觸發的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-359">Addressed an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

- <span data-ttu-id="f95b3-360">已解決在嘗試檢視組織表單的屬性時，會導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-360">Addressed an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="f95b3-361">已修正如果使用者有自訂的 [通訊錄] 搜尋路徑，則 Outlook 的名稱解析範圍會限制為自訂路徑，而不是包括全域通訊清單 (GAL) 的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-361">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="f95b3-362">解決了會讓 [附件工具] 中的 [儲存至雲端] 按鈕不見的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-362">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="f95b3-363">解決了以下問題：當使用者從檢查程式視窗回覆受到數位版權管理的郵件，卻沒有所回覆郵件的擁有者權限時，使用者會無法新增簽名。</span><span class="sxs-lookup"><span data-stu-id="f95b3-363">Addressed an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>

- <span data-ttu-id="f95b3-364">解決了以下問題：使用者無法從網頁位置將其他附件新增到先前建立的會議。</span><span class="sxs-lookup"><span data-stu-id="f95b3-364">Addressed an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

- <span data-ttu-id="f95b3-365">解決將附件新增至郵件或從郵件拖放 (與透過功能表相對) 來儲存附件時，導致檔案的「上次修改」日期更新的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-365">Addressed an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

- <span data-ttu-id="f95b3-366">解決會導致在展開的尋找窗格中按一下 Enter 時無法開始搜尋，而是會要求使用者按一下 [搜尋] 按鈕的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-366">Addressed an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>

- <span data-ttu-id="f95b3-367">已修正在一組傳回的搜尋結果中，依類別結果排序不會顯示類別色彩的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-367">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

- <span data-ttu-id="f95b3-368">修正將 [如果有，顯示使用者的照片] 選項停用時，搜尋不會顯示有關使用者的任何資訊的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-368">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="f95b3-369">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f95b3-369">PowerPoint</span></span>

- <span data-ttu-id="f95b3-370">此變更修正了會導致包含 emojis 的 PowerPoint 檔案在儲存時發生失敗的錯誤。</span><span class="sxs-lookup"><span data-stu-id="f95b3-370">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

- <span data-ttu-id="f95b3-371">此變更修正了在 PowerPoint 或 Word 中呈現內嵌為 OLE 物件的舊版 Excel 圖表時可能不會永遠顯示圖表標題的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-371">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="f95b3-372">我們已修正將文字從 Excel 複製到 PowerPoint 時可能會導致其格式設定發生變更的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-372">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="f95b3-373">此變更修正了使用 [全字拼寫須相符] 來尋找特殊字元時，不一定能正常運作的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-373">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="f95b3-374">Project</span><span class="sxs-lookup"><span data-stu-id="f95b3-374">Project</span></span>

- <span data-ttu-id="f95b3-375">修正無法正確計算摘要工作日期的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-375">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="f95b3-376">修正不先執行 OpenUndoTransaction 方法就不能觸發 OnUndoOrRedo 事件的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-376">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="f95b3-377">已修正當使用者按一下 [排程群組] 內 [工作] 功能區中的 [停用] 按鈕時，不會觸發 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) 事件的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-377">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the “Inactivate” button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="f95b3-378">如果您在 [表單類型] 檢視中設定前置任務或後置任務詳細資訊，則 ProjectBeforeTaskChange Visual Basic Applications (VBA) 事件不會一律擷取變更。</span><span class="sxs-lookup"><span data-stu-id="f95b3-378">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="f95b3-379">例如，如果刪除了某個相依性，並在表單上按一下 [確定]，則不會觸發該事件。</span><span class="sxs-lookup"><span data-stu-id="f95b3-379">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="f95b3-380">已修正此問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-380">This behavior has been fixed.</span></span>

- <span data-ttu-id="f95b3-381">已修正在進行變更 (例如日期變更) 之後，實際工作成本 (ACWP) 的最新值不會顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-381">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="f95b3-382">已修正使用「最近使用」(MRU) 功能表開啟專案時，會使用 [讀取/寫入] 存取權開啟專案的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-382">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="f95b3-383">這項變更修正了如果您建立包含開始日期和時間 (但無工期) 的手動工作，則時間表上的時間顯示不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-383">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="f95b3-384">已修正使用回曆列印時間表時，會導致列印檢視中略過或重複一個月的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-384">Fixed an issue where printing a timeline using a Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="f95b3-385">這項變更解決了在團隊規劃中使用 GDI 物件時，可能導致 GDI 物件分配過多並產生記憶體不足的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-385">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

- <span data-ttu-id="f95b3-386">修正了以下問題：如果執行 'CustomFieldValueListGetItem' 且自訂欄位的查閱資料表不存在，系統會建立一個不應建立的空白查閱資料表。</span><span class="sxs-lookup"><span data-stu-id="f95b3-386">Fixed an issue where if CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

- <span data-ttu-id="f95b3-387">在表單檢視中編輯前置/後續任務資料時，會觸發額外的 ProjectBeforeTaskChange 事件</span><span class="sxs-lookup"><span data-stu-id="f95b3-387">WhenPredecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired</span></span>

- <span data-ttu-id="f95b3-388">修正了當開啟保護實際工作的設定時，使用者無法輸入分時期基準工時的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-388">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="f95b3-389">Word</span><span class="sxs-lookup"><span data-stu-id="f95b3-389">Word</span></span>

- <span data-ttu-id="f95b3-390">此變更修正了將游標懸停在提示上並不會醒目提示其卡片的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-390">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="f95b3-391">此變更修正了以下問題：從 [檢視] 功能表選取多個頁面時，其中的 [註解] 窗格會顯示為空白。</span><span class="sxs-lookup"><span data-stu-id="f95b3-391">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

- <span data-ttu-id="f95b3-392">已修正張貼留言功能停用的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-392">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="f95b3-393">此變更修正了使用套索選取工具時，群組圖形中的文字會暫時消失的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-393">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="f95b3-394">此變更解決了處理格式錯誤或無效通訊協定資訊影像時所導致的延遲問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-394">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="f95b3-395">此變更修正了在 PowerPoint 或 Word 中呈現內嵌為 OLE 物件的舊版 Excel 圖表時可能不會永遠顯示圖表標題的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-395">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="f95b3-396">這項變更解決了帳戶管理員不會分派訊息而導致協力廠商應用程式懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-396">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="f95b3-397">此變更修正了在雙頁檢視中建立註解時，註解錨點不一定會顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-397">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="f95b3-398">修正輸入或編輯備註然後使用 Ctrl+A 時，會導致選取畫布中的文字，而不只是選取備註卡片內文字的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-398">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>

- <span data-ttu-id="f95b3-399">已修正如果段落的樣式是連結至清單的樣式上階，則該清單的編號可能會遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-399">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

- <span data-ttu-id="f95b3-400">這項變更修正了目錄會使用文件中未包含的標題樣式進行更新的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-400">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="f95b3-401">我們已修正文件中的文字對齊，在使用 [快速列印] 進行列印之後嘗試進行編輯時變得混亂的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-401">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="f95b3-402">我們已修正將兩份文件合併成一份文件時的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-402">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="f95b3-403">已修正在寄送文件時，儲存在 Word 文件中的數位簽章會被刪除的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-403">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

- <span data-ttu-id="f95b3-404">修正標示的修訂若與方程式有關，在儲存檔案時可能會導致失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-404">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-april-14"></a><span data-ttu-id="f95b3-406">版本 2003：4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="f95b3-406">Version 2003: April 14</span></span>
<span data-ttu-id="f95b3-407">*版本 2003 (組建 12624.20466)*</span><span class="sxs-lookup"><span data-stu-id="f95b3-407">*Version 2003 (Build 12624.20466)*</span></span>

<span data-ttu-id="f95b3-408">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="f95b3-408">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

- <span data-ttu-id="f95b3-410">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="f95b3-410">Various bugs and performance fixes.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2003-april-09"></a><span data-ttu-id="f95b3-412">版本 2003：4 月 9 日</span><span class="sxs-lookup"><span data-stu-id="f95b3-412">Version 2003: April 09</span></span>
<span data-ttu-id="f95b3-413">*版本 2003 (組建 12624.20442)*</span><span class="sxs-lookup"><span data-stu-id="f95b3-413">*Version 2003 (Build 12624.20442)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="f95b3-415">功能更新</span><span class="sxs-lookup"><span data-stu-id="f95b3-415">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="f95b3-416">Excel</span><span class="sxs-lookup"><span data-stu-id="f95b3-416">Excel</span></span>

- <span data-ttu-id="f95b3-417">**M365 進階版內容選擇器：** 讓您的文件栩栩如生！</span><span class="sxs-lookup"><span data-stu-id="f95b3-417">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="f95b3-418">探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="f95b3-418">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="f95b3-419">Outlook</span><span class="sxs-lookup"><span data-stu-id="f95b3-419">Outlook</span></span>

- <span data-ttu-id="f95b3-420">**M365 進階版內容選擇器：** 讓您的文件栩栩如生！</span><span class="sxs-lookup"><span data-stu-id="f95b3-420">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="f95b3-421">探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="f95b3-421">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f95b3-422">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f95b3-422">PowerPoint</span></span>

- <span data-ttu-id="f95b3-423">**M365 進階版內容選擇器：** 讓您的文件栩栩如生！</span><span class="sxs-lookup"><span data-stu-id="f95b3-423">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="f95b3-424">探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="f95b3-424">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="word"></a><span data-ttu-id="f95b3-425">Word</span><span class="sxs-lookup"><span data-stu-id="f95b3-425">Word</span></span>

- <span data-ttu-id="f95b3-426">**M365 進階版內容選擇器：** 讓您的文件栩栩如生！</span><span class="sxs-lookup"><span data-stu-id="f95b3-426">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="f95b3-427">探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="f95b3-427">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)




[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-april-03"></a><span data-ttu-id="f95b3-431">版本 2003：4 月 3 日</span><span class="sxs-lookup"><span data-stu-id="f95b3-431">Version 2003: April 03</span></span>
<span data-ttu-id="f95b3-432">*版本 2003 (組建 12624.20410)*</span><span class="sxs-lookup"><span data-stu-id="f95b3-432">*Version 2003 (Build 12624.20410)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f95b3-434">已解決的問題</span><span class="sxs-lookup"><span data-stu-id="f95b3-434">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="f95b3-435">Excel</span><span class="sxs-lookup"><span data-stu-id="f95b3-435">Excel</span></span>

- <span data-ttu-id="f95b3-436">使用 VBA 應用程式的 Application.Evaluate 在某些情況下，對使用者定義的函數無法運作。</span><span class="sxs-lookup"><span data-stu-id="f95b3-436">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="f95b3-437">Outlook</span><span class="sxs-lookup"><span data-stu-id="f95b3-437">Outlook</span></span>

- <span data-ttu-id="f95b3-438">解決使用滑鼠上的「X」按鈕時，導致使用者偶爾發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-438">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

### <a name="project"></a><span data-ttu-id="f95b3-439">Project</span><span class="sxs-lookup"><span data-stu-id="f95b3-439">Project</span></span>

- <span data-ttu-id="f95b3-440">在表單檢視中編輯前置/後續任務資料時，會觸發額外的 ProjectBeforeTaskChangeevent。</span><span class="sxs-lookup"><span data-stu-id="f95b3-440">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChangeevent is fired.</span></span>

### <a name="word"></a><span data-ttu-id="f95b3-441">Word</span><span class="sxs-lookup"><span data-stu-id="f95b3-441">Word</span></span>

- <span data-ttu-id="f95b3-442">解決使用滑鼠上的「X」按鈕時，導致使用者偶爾發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-442">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-march-31"></a><span data-ttu-id="f95b3-444">版本 2003：3 月 31 日</span><span class="sxs-lookup"><span data-stu-id="f95b3-444">Version 2003: March 31</span></span>
<span data-ttu-id="f95b3-445">*版本 2003 (組建 12624.20382)*</span><span class="sxs-lookup"><span data-stu-id="f95b3-445">*Version 2003 (Build 12624.20382)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="f95b3-447">功能更新</span><span class="sxs-lookup"><span data-stu-id="f95b3-447">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="f95b3-448">Access</span><span class="sxs-lookup"><span data-stu-id="f95b3-448">Access</span></span>

- <span data-ttu-id="f95b3-449">**「新增資料表」工作窗格：** Access 的全新「新增資料表」工作窗格終於推出！</span><span class="sxs-lookup"><span data-stu-id="f95b3-449">**"Add Tables" Task Pane:** Access's new "Add Tables" Task Pane is finally here!</span></span> <span data-ttu-id="f95b3-450">這項功能可讓您輕鬆選取/多重選取要在查詢視窗中新增/移除的資料表，而不需要瀏覽至查詢和關聯視圖的「顯示資料表」對話方塊。</span><span class="sxs-lookup"><span data-stu-id="f95b3-450">This feature allows you to easily select/multi-select which tables they'd like to add/remove into a query window, without navigating to the "Show Tables" dialog for queries and for relationship view.</span></span> <span data-ttu-id="f95b3-451">這也包含新的「連結」索引標籤，可顯示連結的資料表、可篩選目前清單的搜尋方塊、「拖放」行為及更多功能！</span><span class="sxs-lookup"><span data-stu-id="f95b3-451">This also includes a new "links" tab to display linked tables, a search box to filter the current list, "drag and drop" behavior, and more!</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f95b3-454">已解決的問題</span><span class="sxs-lookup"><span data-stu-id="f95b3-454">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="f95b3-455">Project</span><span class="sxs-lookup"><span data-stu-id="f95b3-455">Project</span></span>

- <div><span data-ttu-id="f95b3-456"><span style="display:inline !important;">修正了當開啟保護實際工作的設定時，使用者無法輸入分時期基準工時的問題。</span></span><span class="sxs-lookup"><span data-stu-id="f95b3-456"><span style="display:inline !important;">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span></span><br></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-march-25"></a><span data-ttu-id="f95b3-458">版本 2003：3 月 25 日</span><span class="sxs-lookup"><span data-stu-id="f95b3-458">Version 2003: March 25</span></span>
<span data-ttu-id="f95b3-459">*版本 2003 (組建 12624.20320)*</span><span class="sxs-lookup"><span data-stu-id="f95b3-459">*Version 2003 (Build 12624.20320)*</span></span>

- <span data-ttu-id="f95b3-460">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="f95b3-460">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-23"></a><span data-ttu-id="f95b3-461">版本 2003：3 月 23 日</span><span class="sxs-lookup"><span data-stu-id="f95b3-461">Version 2003: March 23</span></span>
<span data-ttu-id="f95b3-462">*版本 2003 (組建 12624.20296)*</span><span class="sxs-lookup"><span data-stu-id="f95b3-462">*Version 2003 (Build 12624.20296)*</span></span>

- <span data-ttu-id="f95b3-463">不同的錯誤 (bug) 和效能修正。</span><span class="sxs-lookup"><span data-stu-id="f95b3-463">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-21"></a><span data-ttu-id="f95b3-464">版本 2003：3 月 21 日</span><span class="sxs-lookup"><span data-stu-id="f95b3-464">Version 2003: March 21</span></span>
<span data-ttu-id="f95b3-465">*版本 2003 (組建 12624.20276)*</span><span class="sxs-lookup"><span data-stu-id="f95b3-465">*Version 2003 (Build 12624.20276)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="f95b3-467">功能更新</span><span class="sxs-lookup"><span data-stu-id="f95b3-467">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="f95b3-468">Outlook</span><span class="sxs-lookup"><span data-stu-id="f95b3-468">Outlook</span></span>

- <span data-ttu-id="f95b3-469">**加入會議而不需離開您的收件匣：** 不需切換至您的行事曆即可加入線上會議。</span><span class="sxs-lookup"><span data-stu-id="f95b3-469">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="f95b3-470">將行事曆釘選到 [待辦事項] 窗格之後，只要按一下就能加入任何會議。</span><span class="sxs-lookup"><span data-stu-id="f95b3-470">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="f95b3-471">**行事曆新版視覺效果：** 去年，我們提供了全新的郵件體驗，而今年將為您帶來嶄新的行事曆！</span><span class="sxs-lookup"><span data-stu-id="f95b3-471">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar’s turn to get a facelift!</span></span> <span data-ttu-id="f95b3-472">這些更新是全新但令人熟悉的，身為經驗豐富的 Outlook 使用者的您，可以立即上手並更具生產力。</span><span class="sxs-lookup"><span data-stu-id="f95b3-472">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f95b3-473">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f95b3-473">PowerPoint</span></span>

- <span data-ttu-id="f95b3-474">**在投影片放映期間更新投影片：** 在簡報期間，更新由其他作者變更的投影片。</span><span class="sxs-lookup"><span data-stu-id="f95b3-474">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2003-march-16"></a><span data-ttu-id="f95b3-476">版本 2003：3 月 16 日</span><span class="sxs-lookup"><span data-stu-id="f95b3-476">Version 2003: March 16</span></span>
<span data-ttu-id="f95b3-477">*版本 2003 (組建 12624.20224)*</span><span class="sxs-lookup"><span data-stu-id="f95b3-477">*Version 2003 (Build 12624.20224)*</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="f95b3-479">功能更新</span><span class="sxs-lookup"><span data-stu-id="f95b3-479">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="f95b3-480">Excel</span><span class="sxs-lookup"><span data-stu-id="f95b3-480">Excel</span></span>

- <span data-ttu-id="f95b3-481">**挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。</span><span class="sxs-lookup"><span data-stu-id="f95b3-481">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="outlook"></a><span data-ttu-id="f95b3-482">Outlook</span><span class="sxs-lookup"><span data-stu-id="f95b3-482">Outlook</span></span>

- <span data-ttu-id="f95b3-483">**挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。</span><span class="sxs-lookup"><span data-stu-id="f95b3-483">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f95b3-484">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f95b3-484">PowerPoint</span></span>

- <span data-ttu-id="f95b3-485">**挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。</span><span class="sxs-lookup"><span data-stu-id="f95b3-485">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="word"></a><span data-ttu-id="f95b3-486">Word</span><span class="sxs-lookup"><span data-stu-id="f95b3-486">Word</span></span>

- <span data-ttu-id="f95b3-487">**挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。</span><span class="sxs-lookup"><span data-stu-id="f95b3-487">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="office-suite"></a><span data-ttu-id="f95b3-488">Office 套件</span><span class="sxs-lookup"><span data-stu-id="f95b3-488">Office Suite</span></span>

- <span data-ttu-id="f95b3-489">**索引標籤式窗格：** 現在您可以使用應用程式右側的索引標籤 UI，在多個窗格之間切換。</span><span class="sxs-lookup"><span data-stu-id="f95b3-489">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="f95b3-490">只有當您開啟 2 個以上的窗格時，該 UI 才會顯示。</span><span class="sxs-lookup"><span data-stu-id="f95b3-490">The UI will only be visible when you have 2+ panes open.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f95b3-493">解決的問題</span><span class="sxs-lookup"><span data-stu-id="f95b3-493">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="f95b3-494">Excel</span><span class="sxs-lookup"><span data-stu-id="f95b3-494">Excel</span></span>

- <span data-ttu-id="f95b3-495">已解決當來源活頁簿關閉時，外部連結無法在填滿時更新的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-495">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

### <a name="outlook"></a><span data-ttu-id="f95b3-496">Outlook</span><span class="sxs-lookup"><span data-stu-id="f95b3-496">Outlook</span></span>

- <span data-ttu-id="f95b3-497">已解決導致使用者在工作管理員中看到 Outlook 處理序延遲的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-497">Addressed an issue that caused users to see the Outlook process lingering in task manager after exiting.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-march-10"></a><span data-ttu-id="f95b3-499">版本 2003：3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="f95b3-499">Version 2003: March 10</span></span>
<span data-ttu-id="f95b3-500">*版本 2003 (組建 12624.20176)*</span><span class="sxs-lookup"><span data-stu-id="f95b3-500">*Version 2003 (Build 12624.20176)*</span></span>

<span data-ttu-id="f95b3-501">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="f95b3-501">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)
### <a name="feature-updates"></a><span data-ttu-id="f95b3-503">功能更新</span><span class="sxs-lookup"><span data-stu-id="f95b3-503">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="f95b3-504">Excel</span><span class="sxs-lookup"><span data-stu-id="f95b3-504">Excel</span></span>
- <span data-ttu-id="f95b3-505">**敏感度標籤**：您現在可以套用組織設定、用來提示您輸入自訂權限的敏感度標籤。</span><span class="sxs-lookup"><span data-stu-id="f95b3-505">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="f95b3-506">深入了解</span><span class="sxs-lookup"><span data-stu-id="f95b3-506">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a><span data-ttu-id="f95b3-507">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f95b3-507">PowerPoint</span></span>
- <span data-ttu-id="f95b3-508">**敏感度標籤**：您現在可以套用組織設定、用來提示您輸入自訂權限的敏感度標籤。</span><span class="sxs-lookup"><span data-stu-id="f95b3-508">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="f95b3-509">深入了解</span><span class="sxs-lookup"><span data-stu-id="f95b3-509">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a><span data-ttu-id="f95b3-510">Word</span><span class="sxs-lookup"><span data-stu-id="f95b3-510">Word</span></span>
- <span data-ttu-id="f95b3-511">**敏感度標籤**：您現在可以套用組織設定、用來提示您輸入自訂權限的敏感度標籤。</span><span class="sxs-lookup"><span data-stu-id="f95b3-511">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="f95b3-512">深入了解</span><span class="sxs-lookup"><span data-stu-id="f95b3-512">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)
</br>

### <a name="resolved-issues"></a><span data-ttu-id="f95b3-513">解決的問題</span><span class="sxs-lookup"><span data-stu-id="f95b3-513">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="f95b3-514">Excel</span><span class="sxs-lookup"><span data-stu-id="f95b3-514">Excel</span></span>

- <span data-ttu-id="f95b3-515">修正 [檔案]\[選項] 對話方塊上的 [確定] 按鈕顯示為灰色停用狀態，但功能並未受影響的外觀問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-515">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="f95b3-516">修正使用者在重新命名樞紐分析表度量值時可能遇到的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-516">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>

- <span data-ttu-id="f95b3-517">修正交叉分析篩選器中的文字在預覽列印中無法正確縮放的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-517">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

- <span data-ttu-id="f95b3-518">已修正使用者在使用 VBA 巨集清除範圍內容時可能遇到的效能問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-518">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="f95b3-519">已修正當使用者執行與功能區互動的巨集時，導致 UI 快閃的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-519">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>

- <span data-ttu-id="f95b3-520">已修正當檔案中的第一個字為 TABLE 時，CSV 檔案載入錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-520">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>

- <span data-ttu-id="f95b3-521">已修正當您在兩個具有不同縮放比例的活頁簿之間切換時，使用者可能遇到的當機問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-521">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

- <span data-ttu-id="f95b3-522">修正 CUBEVALUE 函數有時會傳回不正確結果的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-522">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="f95b3-523">此變更可解決物件模型中的執行階段錯誤，以及當增益集要求的文件/工作表上的主機項目包含具有 noSelect 鎖定的圖形時，應用程式 (Excel、Word) 的潛在當機。</span><span class="sxs-lookup"><span data-stu-id="f95b3-523">This change addresses a run-time error in the object model and potential crash of the App (Excel, Word) when Add-ins ask for Host Items on documents/worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="f95b3-524">解決導致 Outlook 使用者在同步處理設定時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-524">Addresses an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>



### <a name="outlook"></a><span data-ttu-id="f95b3-525">Outlook</span><span class="sxs-lookup"><span data-stu-id="f95b3-525">Outlook</span></span>

- <span data-ttu-id="f95b3-526">修正使用 Outlook Web Access 建立規則時不會保存到 Exchange 伺服器，並導致衝突的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-526">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>

- <span data-ttu-id="f95b3-527">解決導致 Outlook 使用者在同步處理設定時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-527">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

- <span data-ttu-id="f95b3-528">修正 Outlook 在深色模式中不會在 [寄件者:] 欄位中顯示下拉式清單的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-528">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>

- <span data-ttu-id="f95b3-529">解決即使已關閉記錄，在某些情況下仍導致 Outlook 異常產生記錄輸出的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-529">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

- <span data-ttu-id="f95b3-530">已解決當持續整夜執行 Outlook 時，導致使用者無法開啟公用資料夾訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-530">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>

- <span data-ttu-id="f95b3-531">已修正在新增 Gmail 帳戶的驗證工作流程中，[權限] 頁面上的 [允許] 和 [拒絕] 按鈕停用的爭用情況。</span><span class="sxs-lookup"><span data-stu-id="f95b3-531">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>

- <span data-ttu-id="f95b3-532">解決導致使用者無法存取 [空閒/忙碌選項] 行事曆權限對話方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-532">Addressed an issue that caused users to lose access to the &quot;Free Busy Options&quot; calendar permissions dialog.</span></span>

- <span data-ttu-id="f95b3-533">修正開啟某些傳送自不同時區的週期性會議執行個體時，可能導致出現警示：「很抱歉，開啟此項目時發生問題」的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-533">Fixed an issue that may result in the alert: &quot;Sorry we're having trouble opening this item&quot; when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="f95b3-534">已解決從該郵件拖放附件後造成使用者無法重新開啟 .msg 檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-534">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="f95b3-535">修正從 Outlook 上傳檔案附件到 OneDrive 後，造成包含括號之附件名稱的檔案名稱被變更。</span><span class="sxs-lookup"><span data-stu-id="f95b3-535">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

- <span data-ttu-id="f95b3-536">解決在其他應用程式中開啟某個檔案時，導致使用者無法透過檔案總管將該檔案附加至郵件訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-536">Addressed an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

- <span data-ttu-id="f95b3-537">解決導致 Outlook 使用者在同步處理設定時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-537">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f95b3-538">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f95b3-538">PowerPoint</span></span>

- <span data-ttu-id="f95b3-539">修正將滑鼠移至縮圖上時，建議的縮圖閃動的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-539">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="f95b3-540">在某些情況下，這可能會導致 PowerPoint 當機。</span><span class="sxs-lookup"><span data-stu-id="f95b3-540">In some cases this could cause PowerPoint to crash.</span></span>

- <span data-ttu-id="f95b3-541">修正 [檔案]\[選項] 對話方塊上的 [確定] 按鈕顯示為灰色停用狀態，但功能並未受影響的外觀問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-541">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="f95b3-542">修正儲存包含 Excel 圖表的 PowerPoint 或 Word 文件會導致失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-542">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>



### <a name="project"></a><span data-ttu-id="f95b3-543">Project</span><span class="sxs-lookup"><span data-stu-id="f95b3-543">Project</span></span>

- <span data-ttu-id="f95b3-544">修正在將任務標示為完成之後，不正確地將任務完成百分比變更為低於 100% 的值的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-544">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="f95b3-545">修正不先執行 OpenUndoTransaction 方法就不能觸發 OnUndoOrRedo 事件的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-545">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="f95b3-546">修正無法正確計算摘要工作日期的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-546">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

### <a name="visio"></a><span data-ttu-id="f95b3-547">Visio</span><span class="sxs-lookup"><span data-stu-id="f95b3-547">Visio</span></span>

- <span data-ttu-id="f95b3-548">[圖形資訊] 窗格的 [圖案資料] 區段下顯示的詳細資料，與在 Visio 桌面版中開啟該檔案時所顯示的不一致。</span><span class="sxs-lookup"><span data-stu-id="f95b3-548">Shape info pane was showing inconsistent details under Shape Data section, with respect to the file when opened in Visio Desktop.</span></span> <span data-ttu-id="f95b3-549">已修正此問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-549">It has now been fixed.</span></span>

- <span data-ttu-id="f95b3-550">在 2016 之前版本中匯入的點陣圖，由於某些安全性檢查而未呈現。</span><span class="sxs-lookup"><span data-stu-id="f95b3-550">Bitmaps imported in versions before 2016 were not being rendered due to some security checks.</span></span> <span data-ttu-id="f95b3-551">我們已在 Visio 訂閱中修正此問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-551">We have fixed this issue in Visio Subscription.</span></span>

### <a name="word"></a><span data-ttu-id="f95b3-552">Word</span><span class="sxs-lookup"><span data-stu-id="f95b3-552">Word</span></span>

- <span data-ttu-id="f95b3-553">已修正當滑鼠指標暫留在註解卡片上方時，未醒目提示註解卡片的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-553">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>

- <span data-ttu-id="f95b3-554">修正按 Tab 鍵導覽註解卡片時，註解編輯方塊上的焦點無法顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-554">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="f95b3-555">修正 [檔案]\[選項] 對話方塊上的 [確定] 按鈕顯示為灰色停用狀態，但功能並未受影響的外觀問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-555">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="f95b3-556">在使用中的文件共同撰寫工作階段中，直接在註解卡片中新增影像可能會導致新增標籤。</span><span class="sxs-lookup"><span data-stu-id="f95b3-556">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="f95b3-557">我們已修正此問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-557">This issue has been fixed.</span></span>

- <span data-ttu-id="f95b3-558">在方程式中插入控制項 (例如文字內容控制項)，然後儲存再開啟檔案，便會導致內容無法讀取的錯誤。</span><span class="sxs-lookup"><span data-stu-id="f95b3-558">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="f95b3-559">修正將先前使用密碼保護的檔案儲存到雲端儲存空間無法運作的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-559">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

- <span data-ttu-id="f95b3-560">修正受保護無法編輯之文件的比較功能問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-560">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>




### <a name="office-suite"></a><span data-ttu-id="f95b3-561">Office 套件</span><span class="sxs-lookup"><span data-stu-id="f95b3-561">Office Suite</span></span>

- <span data-ttu-id="f95b3-562">當您將 Multichoice/Lookup/Managed-metadata 屬性與 Word/Excel/PowerPoint 文件一起使用並儲存至 SharePoint 文件庫時，這些屬性之前限制為 255 個字元。</span><span class="sxs-lookup"><span data-stu-id="f95b3-562">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="f95b3-563">當這些屬性超過 255 個字元時，這類文件就無法儲存。</span><span class="sxs-lookup"><span data-stu-id="f95b3-563">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="f95b3-564">在此變更中，此限制已增加到 2048 個字元。</span><span class="sxs-lookup"><span data-stu-id="f95b3-564">With this change, this limit has been increased to 2048 characters.</span></span>

- <span data-ttu-id="f95b3-565">修正 Word/Excel/PowerPoint 中的使用者主體名稱 (UPN) 不再區分大小寫，導致在 SharePoint 上使用檔案時較少發生失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-565">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="f95b3-566">修正在 Word/Excel/PowerPoint 中開啟來自相同 SharePoint 文件庫的多個文件時，僅掃描開啟的第一個文件是否符合原則的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-566">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-march-05"></a><span data-ttu-id="f95b3-568">版本 2002：3 月 5 日</span><span class="sxs-lookup"><span data-stu-id="f95b3-568">Version 2002: March 05</span></span>
<span data-ttu-id="f95b3-569">*版本 2002 (組建 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="f95b3-569">*Version 2002 (Build 12527.20278)*</span></span>

- <span data-ttu-id="f95b3-570">不同的錯誤 (bug) 和效能修正。</span><span class="sxs-lookup"><span data-stu-id="f95b3-570">Various bugs and performance fixes.</span></span>


## <a name="version-2002-march-04"></a><span data-ttu-id="f95b3-571">版本 2002：3 月 4 日</span><span class="sxs-lookup"><span data-stu-id="f95b3-571">Version 2002: March 04</span></span>
<span data-ttu-id="f95b3-572">*版本 2002 (組建 12527.20264)*</span><span class="sxs-lookup"><span data-stu-id="f95b3-572">*Version 2002 (Build 12527.20264)*</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f95b3-574">已解決的問題</span><span class="sxs-lookup"><span data-stu-id="f95b3-574">Resolved issues</span></span>

### <a name="project"></a><span data-ttu-id="f95b3-575">Project</span><span class="sxs-lookup"><span data-stu-id="f95b3-575">Project</span></span>
- <div><span data-ttu-id="f95b3-576">修正無法正確計算摘要工作日期的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-576">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span></div>


### <a name="office-suite"></a><span data-ttu-id="f95b3-577">Office 套件</span><span class="sxs-lookup"><span data-stu-id="f95b3-577">Office Suite</span></span>
- <div><span data-ttu-id="f95b3-578">修正在 Word/Excel/PowerPoint 中開啟來自相同 SharePoint 文件庫的多個文件時，僅掃描開啟的第一個文件是否符合原則的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-578">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-march-01"></a><span data-ttu-id="f95b3-580">版本 2002：3 月 1 日</span><span class="sxs-lookup"><span data-stu-id="f95b3-580">Version 2002: March 01</span></span>
<span data-ttu-id="f95b3-581">*版本 2002 (組建 12527.20242)*</span><span class="sxs-lookup"><span data-stu-id="f95b3-581">*Version 2002 (Build 12527.20242)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="f95b3-582">解決的問題</span><span class="sxs-lookup"><span data-stu-id="f95b3-582">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="f95b3-583">Outlook</span><span class="sxs-lookup"><span data-stu-id="f95b3-583">Outlook</span></span>

- <div><span data-ttu-id="f95b3-584">解決導致協力廠商應用程式無法傳送電子郵件的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-584">Addresses an issue that caused third party applications to be unable to send email.</span></span></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-february-24"></a><span data-ttu-id="f95b3-586">版本 2002：2 月 24 日</span><span class="sxs-lookup"><span data-stu-id="f95b3-586">Version 2002: February 24</span></span>
<span data-ttu-id="f95b3-587">*版本 2002 (組建 12527.20194)*</span><span class="sxs-lookup"><span data-stu-id="f95b3-587">*Version 2002 (Build 12527.20194)*</span></span>

- <span data-ttu-id="f95b3-588">不同的錯誤 (bug) 和效能修正。</span><span class="sxs-lookup"><span data-stu-id="f95b3-588">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-22"></a><span data-ttu-id="f95b3-589">版本 2002：2 月 22 日</span><span class="sxs-lookup"><span data-stu-id="f95b3-589">Version 2002: February 22</span></span>
<span data-ttu-id="f95b3-590">*版本 2002 (組建 12527.20186)*</span><span class="sxs-lookup"><span data-stu-id="f95b3-590">*Version 2002 (Build 12527.20186)*</span></span>

- <span data-ttu-id="f95b3-591">各種錯誤和效能修正。</span><span class="sxs-lookup"><span data-stu-id="f95b3-591">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-21"></a><span data-ttu-id="f95b3-592">版本 2002：2 月 21 日</span><span class="sxs-lookup"><span data-stu-id="f95b3-592">Version 2002: February 21</span></span>
<span data-ttu-id="f95b3-593">*版本 2002 (組建 12527.20174)*</span><span class="sxs-lookup"><span data-stu-id="f95b3-593">*Version 2002 (Build 12527.20174)*</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="f95b3-595">功能更新</span><span class="sxs-lookup"><span data-stu-id="f95b3-595">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="f95b3-596">Access</span><span class="sxs-lookup"><span data-stu-id="f95b3-596">Access</span></span>

- <span data-ttu-id="f95b3-597">**在查詢設計工具、SQL 檢視和關聯視窗中工作時更具生產力：** 在資料表上按一下滑鼠右鍵即可開啟、設計、調整大小及隱藏它。</span><span class="sxs-lookup"><span data-stu-id="f95b3-597">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="f95b3-598">在 SQL 檢視中搜尋及取代文字。</span><span class="sxs-lookup"><span data-stu-id="f95b3-598">Search and replace text in SQL View.</span></span> <span data-ttu-id="f95b3-599">在 [關聯圖] 視窗中選取多個資料表。</span><span class="sxs-lookup"><span data-stu-id="f95b3-599">Select multiple tables in the Relationships window.</span></span>

### <a name="outlook"></a><span data-ttu-id="f95b3-600">Outlook</span><span class="sxs-lookup"><span data-stu-id="f95b3-600">Outlook</span></span>

- <span data-ttu-id="f95b3-601">**受限 WiFi 網路的新體驗：** 是否曾經加入需要登入網頁的 WiFi 網路呢？</span><span class="sxs-lookup"><span data-stu-id="f95b3-601">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="f95b3-602">Outlook 現在會偵測這項要求並協助您取得連結。</span><span class="sxs-lookup"><span data-stu-id="f95b3-602">Outlook now detects this and helps you get connected.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f95b3-605">已解決的問題</span><span class="sxs-lookup"><span data-stu-id="f95b3-605">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="f95b3-606">Excel</span><span class="sxs-lookup"><span data-stu-id="f95b3-606">Excel</span></span>

- <div style="box-sizing:border-box;"><span data-ttu-id="f95b3-607">修正 CUBEVALUE 函數有時會傳回不正確結果的問題。&nbsp;</span><span class="sxs-lookup"><span data-stu-id="f95b3-607">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.&nbsp;</span></span></div><div><span style="display:inline !important;"></span><br></div>


### <a name="outlook"></a><span data-ttu-id="f95b3-608">Outlook</span><span class="sxs-lookup"><span data-stu-id="f95b3-608">Outlook</span></span>

- <div><span data-ttu-id="f95b3-609">解決導致會議的位置欄位中的逗號變成分號的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-609">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span></div>


- <div><span data-ttu-id="f95b3-610">解決在多個視窗中檢視相同項目時可能會導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-610">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span></div>


- <div><span data-ttu-id="f95b3-611">解決即使將同步處理滑桿設定為較小的設定，也會導致 Outlook 非預期地同步處理所有郵件的問題。&nbsp;</span><span class="sxs-lookup"><span data-stu-id="f95b3-611">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.&nbsp;</span></span></div>


- <div><span data-ttu-id="f95b3-612">解決會導致使用黑色佈景主題的使用者看到 [從]&quot;&quot; 下拉式功能表在白色背景上顯示白色文字的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-612">Addresses an issue that caused users with Black Theme to see the &quot;From&quot; dropdown show white text on a white background.</span></span></div>


- <div><span data-ttu-id="f95b3-613"><span style="display:inline !important;">此變更會還原在郵件標頭中檢視多行主旨的功能。</span></span><span class="sxs-lookup"><span data-stu-id="f95b3-613"><span style="display:inline !important;">This change restores the ability to view multi-line subjects in the message header.</span></span></span><br></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-february-18"></a><span data-ttu-id="f95b3-615">版本 2002：2 月 18 日</span><span class="sxs-lookup"><span data-stu-id="f95b3-615">Version 2002: February 18</span></span>
<span data-ttu-id="f95b3-616">*版本 2002 (組建 12527.20138)*</span><span class="sxs-lookup"><span data-stu-id="f95b3-616">*Version 2002 (Build 12527.20138)*</span></span>

## <a name="version-2002-february-11"></a><span data-ttu-id="f95b3-617">版本 2002：2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="f95b3-617">Version 2002: February 11</span></span>
<span data-ttu-id="f95b3-618">*版本 2002 (組建 12527.20092)*</span><span class="sxs-lookup"><span data-stu-id="f95b3-618">*Version 2002 (Build 12527.20092)*</span></span>

<span data-ttu-id="f95b3-619">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="f95b3-619">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="f95b3-621">功能更新</span><span class="sxs-lookup"><span data-stu-id="f95b3-621">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="f95b3-622">Outlook</span><span class="sxs-lookup"><span data-stu-id="f95b3-622">Outlook</span></span>

- <span data-ttu-id="f95b3-623">**將電子郵件拖曳到您擁有的群組：** 從您的 [收件匣] 拖曳郵件和交談以將它們移動和複製。</span><span class="sxs-lookup"><span data-stu-id="f95b3-623">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="f95b3-624">您拖曳的郵件將會與所有群組成員共用。</span><span class="sxs-lookup"><span data-stu-id="f95b3-624">Messages you drag will be shared with all group members.</span></span>

### <a name="word"></a><span data-ttu-id="f95b3-625">Word</span><span class="sxs-lookup"><span data-stu-id="f95b3-625">Word</span></span>

- <span data-ttu-id="f95b3-626">**其他人更快速看到您的變更：** 共同撰寫增強功能表示，共同作業者可較以往更快速看到您的變更。</span><span class="sxs-lookup"><span data-stu-id="f95b3-626">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

### <a name="office-suite"></a><span data-ttu-id="f95b3-627">Office 套件</span><span class="sxs-lookup"><span data-stu-id="f95b3-627">Office Suite</span></span>

- <span data-ttu-id="f95b3-628">**更清楚的狀態列圖示：** 狀態列圖示現在更容易查看。</span><span class="sxs-lookup"><span data-stu-id="f95b3-628">**Clearer status bar icons:** Status bar icons are now easier to see.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f95b3-631">解決的問題</span><span class="sxs-lookup"><span data-stu-id="f95b3-631">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="f95b3-632">Access</span><span class="sxs-lookup"><span data-stu-id="f95b3-632">Access</span></span>

- <span data-ttu-id="f95b3-633">Access 範本應不再導致資料庫中的附件欄出現故障。</span><span class="sxs-lookup"><span data-stu-id="f95b3-633">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="f95b3-634">個體化範本後，您現在應該可以將附件欄新增至資料庫。</span><span class="sxs-lookup"><span data-stu-id="f95b3-634">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="f95b3-635">此更新會修正使用 ADODB 的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-635">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="f95b3-636">VB 程式碼中的記錄器物件可能會不正確地報告錯誤。</span><span class="sxs-lookup"><span data-stu-id="f95b3-636">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="f95b3-637">此更新修正可能會導致 Microsoft Access 無法識別連結的 SQL Server 資料表中的識別資料行的問題，這可能會導致不正確地將資料列報告為已刪除。</span><span class="sxs-lookup"><span data-stu-id="f95b3-637">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>


### <a name="excel"></a><span data-ttu-id="f95b3-638">Excel</span><span class="sxs-lookup"><span data-stu-id="f95b3-638">Excel</span></span>

- <span data-ttu-id="f95b3-639">已修正未顯示操作功能表中的註解命令的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-639">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>


- <span data-ttu-id="f95b3-640">已修正以下問題：將文字轉換成具有溢出陣列之儲存格的欄時，某些使用者發生當機。</span><span class="sxs-lookup"><span data-stu-id="f95b3-640">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>


- <span data-ttu-id="f95b3-641">修正使用「資料剖析」搭配動態陣列時，Excel 會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-641">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="f95b3-642">Outlook</span><span class="sxs-lookup"><span data-stu-id="f95b3-642">Outlook</span></span>

- <span data-ttu-id="f95b3-643">修正以月檢視在行事曆中捲動時，無法顯示之前的行事曆活動的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-643">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="f95b3-644">儲存在左側瀏覽窗格 [我的最愛] 的資料夾可能會間歇性消失。</span><span class="sxs-lookup"><span data-stu-id="f95b3-644">Folders saved in 'Favorites' in the left navigation pane may intermittently disappear.</span></span>


- <span data-ttu-id="f95b3-645">已解決導致使用者在指定無效寄件者地址時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-645">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>


- <span data-ttu-id="f95b3-646">已解決導致在某些情況下無法使用相關選項來停用標幟項目醒目提示的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-646">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="f95b3-647">已解決導致使用者在取消帳戶設定時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-647">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>


- <span data-ttu-id="f95b3-648">修正根據保留原則到期的電子郵件會顯示兩個標籤的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-648">Fixed an issue where emails expiring based on a retention policy would display two labels.</span></span> <span data-ttu-id="f95b3-649">其中一個顯示郵件將在一天內過期，另一個則顯示將在兩天內到期。</span><span class="sxs-lookup"><span data-stu-id="f95b3-649">One showing that the mail will expire in one day and another displaying that it will expire in two days.</span></span>


- <span data-ttu-id="f95b3-650">已解決在 Citrix 環境中檢視 30 個以上的行事曆時，導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-650">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="f95b3-651">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f95b3-651">PowerPoint</span></span>

- <span data-ttu-id="f95b3-652">已修正使用 PowerPoint 筆跡動畫時，無法完整轉譯或跳過的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-652">Fixed an issue where Ink may not render completely or get skipped when used in a PowerPoint ink animations.</span></span>

- <span data-ttu-id="f95b3-653">已修正關閉檔案之後，如果有任何事件處理常式正在執行，PowerPoint 就不會立即將它從 [簡報] 集合中移除的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-653">Fixed an issue where After closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="f95b3-654">因此，物件模型報告的開啟中簡報數目會不正確，且會防止關閉 PowerPoint。</span><span class="sxs-lookup"><span data-stu-id="f95b3-654">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>


- <span data-ttu-id="f95b3-655">修正具有深色螢光筆色彩的白色文字，在灰階中會以黑色列印的螢光筆問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-655">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>


### <a name="project"></a><span data-ttu-id="f95b3-656">Project</span><span class="sxs-lookup"><span data-stu-id="f95b3-656">Project</span></span>

- <span data-ttu-id="f95b3-657">已修正以下問題：固定工期類型的 100% 工作可能會誤將其完成百分比計算為小於 100% 完成。</span><span class="sxs-lookup"><span data-stu-id="f95b3-657">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>


### <a name="word"></a><span data-ttu-id="f95b3-658">Word</span><span class="sxs-lookup"><span data-stu-id="f95b3-658">Word</span></span>

- <span data-ttu-id="f95b3-659">更新和瀏覽目錄時，有時可能會在文件上顯示灰色區域的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-659">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>


- <span data-ttu-id="f95b3-660">修正在已撰寫註解但未張貼，且使用者嘗試儲存檔案的情況下，使用 [瀏覽] 來儲存檔案沒有作用的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-660">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>


- <span data-ttu-id="f95b3-661">已修正在註解卡片之間來回切換時，有時會顯示一開始選取的註解，並將某選取範圍醒目提示的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-661">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>


- <span data-ttu-id="f95b3-662">已修正在編輯備註之後將文字設為斜體然後再張貼，斜體格式設定遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-662">Fixed an issue where italics formatting is lost after editing a comment, italicizing the text and then posting it.</span></span>


- <span data-ttu-id="f95b3-663">已修正在具有「反轉」頁面色彩的閱讀模式中，備註提示未顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-663">Fixed an issue where comment hint was not visible in read mode with Inverse page color.</span></span>


- <span data-ttu-id="f95b3-664">已修正共同撰寫文件時，可能不會保留根註解的草稿版本的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-664">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>


- <span data-ttu-id="f95b3-665">將 SlideTrack 啟用且 [註解] 窗格關閉時，Ctrl+Alt+M 可能無法開啟 [註解] 窗格的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-665">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>


- <span data-ttu-id="f95b3-666">修正在表格中新增 @提及時可能發生錯誤訊息：「文件中的表格已經毀損」的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-666">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>


- <span data-ttu-id="f95b3-667">修正備註內容功能表中的備註命令 (編輯備註、回覆備註、刪除備註、解決備註) 未顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-667">Fixed an issue where comment commands (Edit comment, Reply to comment, Delete comment, Resolve comment) in the comments context menu were not being displayed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="f95b3-668">Office 套件</span><span class="sxs-lookup"><span data-stu-id="f95b3-668">Office Suite</span></span>

- <span data-ttu-id="f95b3-669">解決可能導致挪威耐諾斯克 (nn-no) 校訂工具套件安裝不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-669">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>


- <span data-ttu-id="f95b3-670">此變更解決使用 Intel Integrated GPU 的圖形配接卡報告問題。</span><span class="sxs-lookup"><span data-stu-id="f95b3-670">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

