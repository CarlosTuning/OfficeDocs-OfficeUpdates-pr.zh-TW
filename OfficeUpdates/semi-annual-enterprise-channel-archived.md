---
title: 半年通道版本的封存版本資訊
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為 IT 專業人員提供 Office 365 專業增強版半年通道版本的版本資訊
ms.openlocfilehash: 983782e92fbcaeebe5bbcfceee691fee57134da3
ms.sourcegitcommit: 5f72a0e94cda2cb64636380605806c29bbcdc53f
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/26/2021
ms.locfileid: "52026338"
---
# <a name="archived-release-notes-for-semi-annual-enterprise-channel"></a><span data-ttu-id="44499-103">半年企業通道的封存版本資訊</span><span class="sxs-lookup"><span data-stu-id="44499-103">Archived Release notes for Semi-Annual Enterprise Channel</span></span>

<span data-ttu-id="44499-104">這些版本資訊可提供 Office 365 專業增強版、Visio Pro for Office 365、Project Online 電腦版用戶端以及 Office 365 商務版的半年企業通道更新所含新功能和非安全性更新的相關資訊。</span><span class="sxs-lookup"><span data-stu-id="44499-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel updates to Office 365 ProPlus, Visio Pro for Office 365, Project Online Desktop Client and Office 365 Business.</span></span>

> [!NOTE]
> - <span data-ttu-id="44499-105">我們通常會在一段時間內推出功能 (有時甚至推出修正程式) 至半年企業通道。</span><span class="sxs-lookup"><span data-stu-id="44499-105">We often roll out features (and sometimes even fixes) to Semi-Annual Enterprise Channel over a period of time.</span></span> <span data-ttu-id="44499-106">如果您現在沒有看到如下所述的項目，您可以預期它近期會推出。</span><span class="sxs-lookup"><span data-stu-id="44499-106">If you don't see something described below right away, you can expect it soon.</span></span> [<span data-ttu-id="44499-107">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-107">Learn more</span></span>](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516)
> - <span data-ttu-id="44499-108">當使用者在半年企業通道上，從 Office 入口網站下載並安裝 Office 365 到 Windows 10 上時，OneNote 2016 依預設不會包括在其中。</span><span class="sxs-lookup"><span data-stu-id="44499-108">OneNote 2016 will not be included by default when a user on the Semi-Annual Enterprise Channel downloads and installs Office 365 on Windows 10 from the Office Portal.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-december-08"></a><span data-ttu-id="44499-110">版本 2002：12 月 8 日</span><span class="sxs-lookup"><span data-stu-id="44499-110">Version 2002: December 08</span></span>
<span data-ttu-id="44499-111">*版本 2002 (組建 12527.21416)*</span><span class="sxs-lookup"><span data-stu-id="44499-111">*Version 2002 (Build 12527.21416)*</span></span>

<span data-ttu-id="44499-112">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-112">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="44499-114">解決的問題</span><span class="sxs-lookup"><span data-stu-id="44499-114">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="44499-115">Excel</span><span class="sxs-lookup"><span data-stu-id="44499-115">Excel</span></span>

- <span data-ttu-id="44499-116">內容從 Excel 複製並使用 [内嵌] 選項貼上到 PowerPoint 中時，改進了 PowerPoint 中的文字字元間距調整。</span><span class="sxs-lookup"><span data-stu-id="44499-116">Improved text kerning in PowerPoint when content is copied from Excel and pasted into PowerPoint with the Embed option.</span></span>


- <span data-ttu-id="44499-117">我們已修復此問題：在重新計算期間，Excel 會停止運作。</span><span class="sxs-lookup"><span data-stu-id="44499-117">We fixed an issue where Excel would stop working during recalc.</span></span>


- <span data-ttu-id="44499-118">我們已修正使用者無法直接從 SharePoint 開啟 atomsvc (UTF8+BOM) 檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-118">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="44499-119">修正在 PowerPivot 中封鎖從 [資料表預覽] 和 [査詢編輯器] 切換的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-119">Fixed an issue that would prevent switching from Table Preview and the Query Editor in PowerPivot.</span></span>


- <span data-ttu-id="44499-120">改進了使用許多最近發佈函數的檔案的效能。</span><span class="sxs-lookup"><span data-stu-id="44499-120">Improved performance for files that are using many of the more recently released functions.</span></span>


### <a name="outlook"></a><span data-ttu-id="44499-121">Outlook</span><span class="sxs-lookup"><span data-stu-id="44499-121">Outlook</span></span>

- <span data-ttu-id="44499-122">我們已修正以下問題：設定 OME 設定時在郵件項目上新增無關的附件，這迫使 Outlook 對郵件進行加密，即使在服務端設定了 DecryptAttachmentsFontryptOnly選項。</span><span class="sxs-lookup"><span data-stu-id="44499-122">We fixed an issue where setting up OME Configuration was adding an extraneous attachments on the mail item which was forcing Outlook to Encrypt the message even though DecryptAttachmentsForEncryptOnly option is setup on the service side.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="44499-123">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="44499-123">PowerPoint</span></span>

- <span data-ttu-id="44499-124">我們已修正當使用者將來源路徑變更為本機 OneDrive 資料夾時，連結的 Excel 圖表不正確變更為 Excel 工作表的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-124">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


### <a name="project"></a><span data-ttu-id="44499-125">Project</span><span class="sxs-lookup"><span data-stu-id="44499-125">Project</span></span>

- <span data-ttu-id="44499-126">我們已修正 URL 以 .com 結尾時，無法從 Project Web App 在 Project 傳統型用戶端開啟專案的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-126">We fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App is the URL ended in .com.</span></span>



[//]: # (請勿移除 BUGDETAILS 內容尾)

## <a name="version-1908-december-08"></a><span data-ttu-id="44499-128">版本 1908：12 月 8 日</span><span class="sxs-lookup"><span data-stu-id="44499-128">Version 1908: December 08</span></span>
<span data-ttu-id="44499-129">*版本 1908 (組建 11929.20984)*</span><span class="sxs-lookup"><span data-stu-id="44499-129">*Version 1908 (Build 11929.20984)*</span></span>

<span data-ttu-id="44499-130">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-130">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

## <a name="version-2002-november-10"></a><span data-ttu-id="44499-131">版本 2002：11 月 10 日</span><span class="sxs-lookup"><span data-stu-id="44499-131">Version 2002: November 10</span></span>
<span data-ttu-id="44499-132">*版本 2002 (組建 12527.21330)*</span><span class="sxs-lookup"><span data-stu-id="44499-132">*Version 2002 (Build 12527.21330)*</span></span>

<span data-ttu-id="44499-133">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-133">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="44499-135">解決的問題</span><span class="sxs-lookup"><span data-stu-id="44499-135">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="44499-136">Excel</span><span class="sxs-lookup"><span data-stu-id="44499-136">Excel</span></span>

- <span data-ttu-id="44499-137">修正當 Office 語言設定為西班牙文時，其中資料驗證清單可能無法顯示清單中所有項目的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-137">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="44499-138">我們已修正在重新整理 OLAP 樞紐分析表時，可能會導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-138">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="44499-139">修正載入活頁簿之後特定函數可能會發生錯誤結果的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-139">Fixed a bug where certain functions would have an incorrect result after loading a workbook.</span></span>


- <span data-ttu-id="44499-140">我們已修正應用程式意外終止 (與 XLAM 增益集參照和命名範圍相關的問題) 的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-140">We fixed an issue where the application would terminate unexpectedly which was related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="44499-141">修正在執行進階篩選巨集時，不正確報告錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-141">Fixed an issue where running the advanced filter macro would incorrectly report errors.</span></span>


### <a name="outlook"></a><span data-ttu-id="44499-142">Outlook</span><span class="sxs-lookup"><span data-stu-id="44499-142">Outlook</span></span>

- <span data-ttu-id="44499-143">我們已修正當已停用選用的連線體驗時，導致內部增益集意外停用的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-143">We fixed an issue that caused internal add-ins to be unexpectedly disabled when optional connected experiences were disabled.</span></span>


- <span data-ttu-id="44499-144">我們已修正會導致使用者無法以「全域通訊清單」中隱藏的「通訊群組」的名義或以代表其傳送的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-144">We fixed an issue that caused users to be unable to send as or on behalf of a Distribution List that was hidden from the Global Address List.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-november-10"></a><span data-ttu-id="44499-146">版本 1908：11 月 10 日</span><span class="sxs-lookup"><span data-stu-id="44499-146">Version 1908: November 10</span></span>
<span data-ttu-id="44499-147">*版本 1908 (組建 11929.20974)*</span><span class="sxs-lookup"><span data-stu-id="44499-147">*Version 1908 (Build 11929.20974)*</span></span>

<span data-ttu-id="44499-148">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-148">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

## <a name="version-2002-october-13"></a><span data-ttu-id="44499-149">版本 2002：10 月 13 日</span><span class="sxs-lookup"><span data-stu-id="44499-149">Version 2002: October 13</span></span>
<span data-ttu-id="44499-150">*版本 2002 (組建 12527.21236)*</span><span class="sxs-lookup"><span data-stu-id="44499-150">*Version 2002 (Build 12527.21236)*</span></span>

<span data-ttu-id="44499-151">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-151">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="44499-153">解決的問題</span><span class="sxs-lookup"><span data-stu-id="44499-153">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="44499-154">存取</span><span class="sxs-lookup"><span data-stu-id="44499-154">Access</span></span>

- <span data-ttu-id="44499-155">只要您滿足 Access 資料庫指導方針和需求，則應該不會再於您的 64 位元版本 Access 中收到「查詢太複雜」或系統資源滿載錯誤。</span><span class="sxs-lookup"><span data-stu-id="44499-155">You should no longer receive a "Query is too complex" or a system resource exceeded error on your 64-bit version of Access, as long as you are meeting Access database guidelines and requirements.</span></span>


- <span data-ttu-id="44499-156">一旦您決定在我們的查詢設計工具之後使用篩選功能，您的資料庫應該就不會再當機。</span><span class="sxs-lookup"><span data-stu-id="44499-156">Once you decide to use our filter feature after our query designer, your database should no longer crash.</span></span> <span data-ttu-id="44499-157">請相應地檢查。</span><span class="sxs-lookup"><span data-stu-id="44499-157">Please check accordingly.</span></span>


### <a name="excel"></a><span data-ttu-id="44499-158">Excel</span><span class="sxs-lookup"><span data-stu-id="44499-158">Excel</span></span>

- <span data-ttu-id="44499-159">我們已修正使用者無法修改樞紐分析表篩選的問題，因為它已設定為Analysis Services數據庫中不再存在的值。</span><span class="sxs-lookup"><span data-stu-id="44499-159">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="44499-160">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="44499-160">PowerPoint</span></span>

- <span data-ttu-id="44499-161">從範本建立的新簡報會繼承設定，使得您無法順利進行共同撰寫。</span><span class="sxs-lookup"><span data-stu-id="44499-161">New presentations created from a template could inherit a setting that prevented  a good co-authoring experience.</span></span> <span data-ttu-id="44499-162">此修正程式可確保在此情況下會清除該設定。</span><span class="sxs-lookup"><span data-stu-id="44499-162">This fix ensures that the setting is cleared in this case.</span></span>


### <a name="word"></a><span data-ttu-id="44499-163">Word</span><span class="sxs-lookup"><span data-stu-id="44499-163">Word</span></span>

- <span data-ttu-id="44499-164">我們已修正在開啟含有分頁符號和欄的文件時，使用者可能會遇到錯誤訊息：「您已超過 Microsoft Word 所支援的頁數上限或此文件已損毀」</span><span class="sxs-lookup"><span data-stu-id="44499-164">We fixed an issue which when opening documents with page breaks and columns, user might encountered an error message, " You have exceeded the maximum number of pages allowed by Microsoft Word supported, or the document may be damaged"</span></span>


### <a name="office-suite"></a><span data-ttu-id="44499-165">Office 套件</span><span class="sxs-lookup"><span data-stu-id="44499-165">Office Suite</span></span>

- <span data-ttu-id="44499-166">當使用者從 Office 噴墨印表機上列印任何文件/檔案且列印機墨水不足時，即使噴墨印表機沒有碳粉，也會顯示「碳粉不足」或「無碳粉」消息。</span><span class="sxs-lookup"><span data-stu-id="44499-166">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="44499-167">將訊息變更為顯示「碳粉/墨水不足」和「沒有碳粉/墨水」。</span><span class="sxs-lookup"><span data-stu-id="44499-167">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-october-13"></a><span data-ttu-id="44499-169">版本 1908：10 月 13 日</span><span class="sxs-lookup"><span data-stu-id="44499-169">Version 1908: October 13</span></span>
<span data-ttu-id="44499-170">*版本 1908 (組建 11929.20966)*</span><span class="sxs-lookup"><span data-stu-id="44499-170">*Version 1908 (Build 11929.20966)*</span></span>

<span data-ttu-id="44499-171">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-171">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="44499-173">解決的問題</span><span class="sxs-lookup"><span data-stu-id="44499-173">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="44499-174">Office 套件</span><span class="sxs-lookup"><span data-stu-id="44499-174">Office Suite</span></span>

- <span data-ttu-id="44499-175">當使用者從 Office 噴墨印表機上列印任何文件/檔案且列印機墨水不足時，即使噴墨印表機沒有碳粉，也會顯示「碳粉不足」或「無碳粉」消息。</span><span class="sxs-lookup"><span data-stu-id="44499-175">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="44499-176">將訊息變更為顯示「碳粉/墨水不足」和「沒有碳粉/墨水」。</span><span class="sxs-lookup"><span data-stu-id="44499-176">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-september-08"></a><span data-ttu-id="44499-178">版本 2002：9 月 8 日</span><span class="sxs-lookup"><span data-stu-id="44499-178">Version 2002: September 08</span></span>
<span data-ttu-id="44499-179">*版本 2002 (組建 12527.21104)*</span><span class="sxs-lookup"><span data-stu-id="44499-179">*Version 2002 (Build 12527.21104)*</span></span>

<span data-ttu-id="44499-180">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-180">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="44499-182">解決的問題</span><span class="sxs-lookup"><span data-stu-id="44499-182">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="44499-183">Excel</span><span class="sxs-lookup"><span data-stu-id="44499-183">Excel</span></span>

- <span data-ttu-id="44499-184">這解決了舊版 Office 中 SQL 資料提供者建立的連結設定內部表格内容與 Office 365 不同的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-184">This addresses an issue where connections created by the SQL data provider in older versions of Office would set internal table properties differently from Office 365.</span></span> <span data-ttu-id="44499-185">這導致在舊版 Office 中使用 Office 365 開啟文件時，這些檔案的 [表格預覽/查詢編輯器] 下拉清單被停用。</span><span class="sxs-lookup"><span data-stu-id="44499-185">This caused the Table Preview / Query Editor dropdown to be disabled for files with connections created in older versions of Office when they were opened using Office 365.</span></span>


- <span data-ttu-id="44499-186">已解決筆跡會導致 Excel 無法回應的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-186">Resolved an issue where inking could cause Excel to become unresponsive.</span></span>


### <a name="outlook"></a><span data-ttu-id="44499-187">Outlook</span><span class="sxs-lookup"><span data-stu-id="44499-187">Outlook</span></span>

- <span data-ttu-id="44499-188">修正新增共用信箱之後，導致使用者無法連線至公用資料夾的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-188">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>


### <a name="office-suite"></a><span data-ttu-id="44499-189">Office 套件</span><span class="sxs-lookup"><span data-stu-id="44499-189">Office Suite</span></span>

- <span data-ttu-id="44499-190">此變更解決 [壓縮圖片] 對話方塊無法保留特定使用者設定的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-190">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-september-08"></a><span data-ttu-id="44499-192">版本 1908：9 月 8 日</span><span class="sxs-lookup"><span data-stu-id="44499-192">Version 1908: September 08</span></span>
<span data-ttu-id="44499-193">*版本 1908 (組建 11929.20946)*</span><span class="sxs-lookup"><span data-stu-id="44499-193">*Version 1908 (Build 11929.20946)*</span></span>

<span data-ttu-id="44499-194">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-194">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

## <a name="version-2002-august-11"></a><span data-ttu-id="44499-195">版本 2002: 8月11日</span><span class="sxs-lookup"><span data-stu-id="44499-195">Version 2002: August 11</span></span>
<span data-ttu-id="44499-196">*版本2002（组建12527.20988）*</span><span class="sxs-lookup"><span data-stu-id="44499-196">*Version 2002 (Build 12527.20988)*</span></span>

<span data-ttu-id="44499-197">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-197">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="44499-199">解決的問題</span><span class="sxs-lookup"><span data-stu-id="44499-199">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="44499-200">Excel</span><span class="sxs-lookup"><span data-stu-id="44499-200">Excel</span></span>

- <span data-ttu-id="44499-201">修正無法將以 [唯讀建議] 方式開啟的檔案切換至編輯功能的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-201">Fixed an issue which prevented the ability to switch to editing for files that opened as "read-only recommended".</span></span>

### <a name="onenote"></a><span data-ttu-id="44499-202">OneNote</span><span class="sxs-lookup"><span data-stu-id="44499-202">OneNote</span></span>

- <span data-ttu-id="44499-203">移除了多餘的身分識別通話，以降低資源使用率</span><span class="sxs-lookup"><span data-stu-id="44499-203">Removed redundant identity calls to reduce resource utilization</span></span>

- <span data-ttu-id="44499-204">改善了共同撰寫狀態的偵測，以降低資源利用率。</span><span class="sxs-lookup"><span data-stu-id="44499-204">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="44499-205">改善了偵測錯誤的功能和同步處理經驗的品質。</span><span class="sxs-lookup"><span data-stu-id="44499-205">Improved capability for detecting errors and the quality of the sync experience.</span></span>

### <a name="outlook"></a><span data-ttu-id="44499-206">Outlook</span><span class="sxs-lookup"><span data-stu-id="44499-206">Outlook</span></span>

- <span data-ttu-id="44499-207">解決了在啟動某些租使用者的 Outlook 時，會導致嚴重效能問題的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-207">Addressed an issue that caused a significant performance issue when starting Outlook for some tenants.</span></span>

### <a name="skype"></a><span data-ttu-id="44499-208">Skype</span><span class="sxs-lookup"><span data-stu-id="44499-208">Skype</span></span>

- <span data-ttu-id="44499-209">修正在執行數天後，會無法啟動 32位元 Skype 商務版客戶螢幕共享的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-209">Fixed an issue where starting a screen share can fail on a 32-bit Skype for Business client after it has been running for several days.</span></span>

### <a name="office-suite"></a><span data-ttu-id="44499-210">Office 套件</span><span class="sxs-lookup"><span data-stu-id="44499-210">Office Suite</span></span>

- <span data-ttu-id="44499-211">修正如果 [自動儲存] 已透過組織政策關閉的話，某些文件可能不會在開啟時顯示最新的伺服器內容，除非使用者點擊 [可用的更新] 才會顯現。</span><span class="sxs-lookup"><span data-stu-id="44499-211">Fixed an issue where if AutoSave is turned off through group policy, some documents might not show the latest server contents on open until the user clicks on 'Updates available'.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-august-11"></a><span data-ttu-id="44499-213">版本 1908: 8月11日</span><span class="sxs-lookup"><span data-stu-id="44499-213">Version 1908: August 11</span></span>
<span data-ttu-id="44499-214">*版本 1908 (組建 11929.20934)*</span><span class="sxs-lookup"><span data-stu-id="44499-214">*Version 1908 (Build 11929.20934)*</span></span>

<span data-ttu-id="44499-215">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-215">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

## <a name="version-1902-august-11"></a><span data-ttu-id="44499-216">版本 1902: 8月11日</span><span class="sxs-lookup"><span data-stu-id="44499-216">Version 1902: August 11</span></span>
<span data-ttu-id="44499-217">*版本 1902 (組建 11328.20644)*</span><span class="sxs-lookup"><span data-stu-id="44499-217">*Version 1902 (Build 11328.20644)*</span></span>

<span data-ttu-id="44499-218">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-218">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-july-14"></a><span data-ttu-id="44499-221">版本 2002：7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="44499-221">Version 2002: July 14</span></span>
<span data-ttu-id="44499-222">*版本 2002 (組建 12527.20880)*</span><span class="sxs-lookup"><span data-stu-id="44499-222">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="44499-223">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-223">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="44499-225">功能更新</span><span class="sxs-lookup"><span data-stu-id="44499-225">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="44499-226">Access</span><span class="sxs-lookup"><span data-stu-id="44499-226">Access</span></span>

- <span data-ttu-id="44499-227">**快速尋找連結資料表：** 新的搜尋方塊可讓您輕鬆尋找連結資料表。</span><span class="sxs-lookup"><span data-stu-id="44499-227">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="44499-228">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-228">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="44499-229">Excel</span><span class="sxs-lookup"><span data-stu-id="44499-229">Excel</span></span>

- <span data-ttu-id="44499-230">**更快速共用檔案：** 不需開啟檔案，即可從最近使用清單直接共用您的檔案。</span><span class="sxs-lookup"><span data-stu-id="44499-230">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="44499-231">**資料視覺化工具增益集：** 從 Excel 快速建立 Visio 流程圖。</span><span class="sxs-lookup"><span data-stu-id="44499-231">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="44499-232">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-232">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="44499-233">**建立更易於存取的 PDF：** 建立 PDF 檔案，在儲存之前，協助工具檢查程式會指出應該修正的協助工具問題。</span><span class="sxs-lookup"><span data-stu-id="44499-233">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="44499-234">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-234">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br /><span data-ttu-id="44499-235">在[部落格文章](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="44499-235">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="44499-236">**符合您情境的更多圖示：** 我們新增了超過 300 個新圖示。</span><span class="sxs-lookup"><span data-stu-id="44499-236">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="44499-237">其位置：[插入] > [圖示]。</span><span class="sxs-lookup"><span data-stu-id="44499-237">Find them at Insert > Icons.</span></span> [<span data-ttu-id="44499-238">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-238">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="44499-239">**轉換檔案，以改善協助工具功能：** 將您的檔案升級為現代格式，讓所有人更容易存取。</span><span class="sxs-lookup"><span data-stu-id="44499-239">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="44499-240">在[部落格文章](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="44499-240">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="44499-241">**專注於剩餘工作：** 選取 [解決] 來摺疊註解，使得開啟中的項目能夠突顯。</span><span class="sxs-lookup"><span data-stu-id="44499-241">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="44499-242">**輸入會傳回多個值的公式**：現在您可以快速輸入公式來傳回多個值，並且值會自動溢出至相鄰的儲存格。</span><span class="sxs-lookup"><span data-stu-id="44499-242">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="44499-243">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-243">Learn more</span></span>](https://support.office.com/article/5c2c9cbb-def8-409a-b380-2fbf91b20aa3)<br /><span data-ttu-id="44499-244">在[部落格文章](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="44499-244">See details in [blog post](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)</span></span>

- <span data-ttu-id="44499-245">**不必再來回往返瀏覽器：** 您決定開啟 Office 文件連結的方式：在瀏覽器或應用程式中開啟。</span><span class="sxs-lookup"><span data-stu-id="44499-245">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="44499-246">**勾勒草圖：** 為活頁簿中的 Office 圖形提供隨意的手繪外觀。</span><span class="sxs-lookup"><span data-stu-id="44499-246">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="44499-247">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-247">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="44499-248">在[部落格文章](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="44499-248">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="44499-249">**找到您要尋找的項目：** 搜尋命令、人員、檔案、相片、網頁文章等。</span><span class="sxs-lookup"><span data-stu-id="44499-249">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="44499-250">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-250">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="44499-251">**六個功能強大的函數：** 我們新增了六個新的函數，讓您的試算表功能更強大：FILTER、SORT、SORTBY、UNIQUE、SEQUENCE 和 RANDARRAY。</span><span class="sxs-lookup"><span data-stu-id="44499-251">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span> [<span data-ttu-id="44499-252">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-252">Learn more</span></span>](https://support.office.com/article/003df6c7-1dcb-4388-8e2e-0fe77a0887bc)

- <span data-ttu-id="44499-253">**向左看，向右看... XLOOKUP 在這裡！：** 一列接著一列，在含有 XLOOKUP 的表格或範圍中尋找您需要的項目。</span><span class="sxs-lookup"><span data-stu-id="44499-253">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span> [<span data-ttu-id="44499-254">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-254">Learn more</span></span>](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)<br /><span data-ttu-id="44499-255">在[部落格文章](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="44499-255">See details in [blog post](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)</span></span>

- <span data-ttu-id="44499-256">**整理您的大型活頁簿：** 儲存格、公式、圖表、表格... 利用「活頁簿統計資料」來取得活頁簿的快照。</span><span class="sxs-lookup"><span data-stu-id="44499-256">**Tame your big workbook:** Cells, formulas, charts, tables... get a snapshot of your workbook with Workbook Statistics.</span></span>

- <span data-ttu-id="44499-257">**即時讀取與回覆：** 直接從電子郵件回覆註解和提及，而不需開啟活頁簿。</span><span class="sxs-lookup"><span data-stu-id="44499-257">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="44499-258">**使用 \@Mentions 提及功能取得他人注意：** 在註解中使用 @mentions 提及功能，讓同事知道您需要他們提供建議。</span><span class="sxs-lookup"><span data-stu-id="44499-258">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="44499-259">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-259">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

### <a name="outlook"></a><span data-ttu-id="44499-260">Outlook</span><span class="sxs-lookup"><span data-stu-id="44499-260">Outlook</span></span>

- <span data-ttu-id="44499-261">**在螢幕上容納更多郵件：** 選取 [檢視] > [使用更緊密的間距] 來調整郵件之間的間距。</span><span class="sxs-lookup"><span data-stu-id="44499-261">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="44499-262">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-262">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="44499-263">**符合您情境的更多圖示：** 我們新增了超過 300 個新圖示。</span><span class="sxs-lookup"><span data-stu-id="44499-263">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="44499-264">其位置：[插入] > [圖示]。</span><span class="sxs-lookup"><span data-stu-id="44499-264">Find them at Insert > Icons.</span></span> [<span data-ttu-id="44499-265">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-265">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="44499-266">**讓我繪製：** 使用筆跡在圖片上徒手畫或新增繪圖畫布來傳達您的想法。</span><span class="sxs-lookup"><span data-stu-id="44499-266">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="44499-267">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-267">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="44499-268">**取得位置建議：** 排程約會和會議時，請在 [位置] 中開始輸入，Outlook 會建議會議室、地址，以及其他最近使用的位置。</span><span class="sxs-lookup"><span data-stu-id="44499-268">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="44499-269">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-269">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)<br /><span data-ttu-id="44499-270">在[部落格文章](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="44499-270">See details in [blog post](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/)</span></span>

- <span data-ttu-id="44499-271">**抵禦攻擊的進階防護：** 使用 Office 365 進階威脅防護，您會受到保護，不受電子郵件主旨、附加的郵件、簽署的郵件、網路路徑內超連結的攻擊。</span><span class="sxs-lookup"><span data-stu-id="44499-271">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="44499-272">**Outlook 中的 [插入連結] 功能表會插入含有租用戶系統管理員所定義的權限的連結：** Outlook 中使用 [插入連結] 所插入的連結，只有具有連結權限的使用者可使用。</span><span class="sxs-lookup"><span data-stu-id="44499-272">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="44499-273">這常會造成使用者來回傳送電子郵件，要求對方授與文件的存取權。</span><span class="sxs-lookup"><span data-stu-id="44499-273">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="44499-274">我們已更新這項體驗，現在插入的連結將具有由租用戶系統管理員設定的預設權限。針對 MSIT，這是「組織可以編輯」，使得以此方式收到共用連結的所有內部使用者將可以存取它。</span><span class="sxs-lookup"><span data-stu-id="44499-274">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="44499-275">**在不同燈光下查看郵件：** 使用太陽/月亮按鈕以在讀取窗格中於淺色和深色背景之間切換。</span><span class="sxs-lookup"><span data-stu-id="44499-275">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="44499-276">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-276">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="44499-277">**網路釣魚郵件很容易找到：** 垃圾郵件和網路釣魚訊息的外觀不同，因此您可以從收件匣輕鬆找出並加以清除。</span><span class="sxs-lookup"><span data-stu-id="44499-277">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="44499-p123">**集中所有加密選項：** 只要前往 [選項] > [加密]，即可選擇要用來保護電子郵件訊息的方法。[深入了解](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="44499-p123">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="44499-280">**具有拼字問題或錯字的搜尋：** 即使您的拼寫不相符，Outlook 也會找到您要尋找的內容。</span><span class="sxs-lookup"><span data-stu-id="44499-280">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="44499-281">**將您的 LinkedIn 人際網路連接至 Outlook：** 安全地將您的 LinkedIn 帳戶與 Microsoft 帳戶連結，以直接在人員卡片中查看 LinkedIn 個人資料中的資訊。</span><span class="sxs-lookup"><span data-stu-id="44499-281">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="44499-282">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-282">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="44499-283">**在搜尋結果中查看相關郵件：** Outlook 會分析搜尋字詞，然後在搜尋結果的最上方顯示最相關的電子郵件。</span><span class="sxs-lookup"><span data-stu-id="44499-283">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="44499-284">您也可以在 [最佳結果] 區段中查看依日期排列順序的所有結果。</span><span class="sxs-lookup"><span data-stu-id="44499-284">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="44499-285">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-285">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

### <a name="powerpoint"></a><span data-ttu-id="44499-286">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="44499-286">PowerPoint</span></span>

- <span data-ttu-id="44499-p126">**您來計算，格式設定交給我們** 我們能將難懂的手寫數學運算式變更為標準字元。只要選擇 [筆跡轉換數學]，然後選取您的手寫筆記，即可開始使用。[深入了解](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="44499-p126">**You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

- <span data-ttu-id="44499-290">**尋找您要尋找的項目：** 使用搜尋方塊來尋找文字、命令、說明等。</span><span class="sxs-lookup"><span data-stu-id="44499-290">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="44499-291">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-291">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="44499-292">**運用筆跡製作精彩的投影片：** 將筆跡轉換成標準圖形和文字，然後從 PowerPoint 設計工具吸取智慧的投影片設計概念。</span><span class="sxs-lookup"><span data-stu-id="44499-292">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="44499-293">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-293">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- <span data-ttu-id="44499-294">**勾勒草圖：** 為簡報中的 Office 圖形提供隨意的手繪外觀。</span><span class="sxs-lookup"><span data-stu-id="44499-294">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="44499-295">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-295">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="44499-296">在[部落格文章](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="44499-296">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="44499-297">**筆跡立即重播：** 當您在投影片上進行手寫時，套用重播動畫可在投影片放映期間重播真實手繪的筆跡。</span><span class="sxs-lookup"><span data-stu-id="44499-297">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="44499-298">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-298">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)<br /><span data-ttu-id="44499-299">在[部落格文章](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="44499-299">See details in [blog post](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/)</span></span>

- <span data-ttu-id="44499-300">**更安全的影片體驗：** 安全性增強功能可讓您擁有更安全的線上影片體驗。</span><span class="sxs-lookup"><span data-stu-id="44499-300">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="44499-301">**將圖例另存成 SVG：** 將圖表、圖形或其他圖例另存成可縮放向量圖形，其可調整大小，且不損失影像品質。</span><span class="sxs-lookup"><span data-stu-id="44499-301">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="44499-302">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-302">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="44499-303">**列印講義上的投影片編號：** 投影片編號會自動包含在講義上。</span><span class="sxs-lookup"><span data-stu-id="44499-303">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="44499-304">由您決定將其保留或關閉。</span><span class="sxs-lookup"><span data-stu-id="44499-304">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="44499-305">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-305">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="44499-306">**尋找並修正遺失的投影片標題：** 投影片標題可為您的企劃加分，並讓所有功能的使用者都能存取投影片。</span><span class="sxs-lookup"><span data-stu-id="44499-306">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="44499-307">協助工具檢查程式會顯示缺少標題的地方，這樣您就可以快速新增標題。</span><span class="sxs-lookup"><span data-stu-id="44499-307">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="44499-308">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-308">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="44499-309">**轉換檔案，以改善協助工具功能：** 將您的檔案升級為現代格式，讓所有人更容易存取。</span><span class="sxs-lookup"><span data-stu-id="44499-309">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="44499-310">在[部落格文章](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="44499-310">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="44499-311">**符合您情境的更多圖示：** 我們新增了超過 300 個新圖示。</span><span class="sxs-lookup"><span data-stu-id="44499-311">**More icons to match your mood:** We've added more than 300 new icons.</span></span> <span data-ttu-id="44499-312">其位置：[插入] > [圖示]。</span><span class="sxs-lookup"><span data-stu-id="44499-312">Find them at Insert > Icons.</span></span> [<span data-ttu-id="44499-313">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-313">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="44499-314">**建立更易於存取的 PDF：** 建立 PDF 檔案，在儲存之前，協助工具檢查程式會指出應該修正的協助工具問題。</span><span class="sxs-lookup"><span data-stu-id="44499-314">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span><br /><span data-ttu-id="44499-315">在[部落格文章](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="44499-315">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="44499-316">**更快速共用檔案：** 不需開啟檔案，即可從最近使用清單直接共用您的檔案。</span><span class="sxs-lookup"><span data-stu-id="44499-316">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="44499-317">**在 PowerPoint 中快速即時共同作業：** 在 PowerPoint 中快速即時共同作業</span><span class="sxs-lookup"><span data-stu-id="44499-317">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="44499-318">**不必再來回往返瀏覽器：** 您決定開啟 Office 文件連結的方式：在瀏覽器或應用程式中開啟。</span><span class="sxs-lookup"><span data-stu-id="44499-318">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="44499-319">**新的校對工具：** 不著重您的文字。</span><span class="sxs-lookup"><span data-stu-id="44499-319">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="44499-320">PowerPoint 現在提供文法及書寫建議。</span><span class="sxs-lookup"><span data-stu-id="44499-320">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="44499-321">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-321">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="44499-322">**即時的輔助字幕和翻譯字幕：** 簡報者的文字會自動顯示為畫面上的標題，或翻譯為所選語言的字幕。</span><span class="sxs-lookup"><span data-stu-id="44499-322">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="44499-323">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-323">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="44499-324">**最佳化您的簡報：** 協助工具檢查程式可協助您以螢幕閱讀器為中心，在投影片上排列物件。</span><span class="sxs-lookup"><span data-stu-id="44499-324">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span><br /><span data-ttu-id="44499-325">在[部落格文章](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="44499-325">See details in [blog post](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/)</span></span>

- <span data-ttu-id="44499-326">**當您可以重複使用時為什麼要重新打造？** 重複使用您所建立的投影片或其他人與您共用的投影片來以節省時間。</span><span class="sxs-lookup"><span data-stu-id="44499-326">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="44499-327">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-327">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

### <a name="visio"></a><span data-ttu-id="44499-328">Visio</span><span class="sxs-lookup"><span data-stu-id="44499-328">Visio</span></span>

- <span data-ttu-id="44499-329">**在 Excel 中製作精美的 Visio 圖表：** 將資料放在工作表上，以建立流程圖或組織圖。</span><span class="sxs-lookup"><span data-stu-id="44499-329">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="44499-330">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-330">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="44499-331">**回到犯罪場景：** 在犯罪場景調查範本中使用新的證據、室內、室外樣板，重建犯罪場景的細節。</span><span class="sxs-lookup"><span data-stu-id="44499-331">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

### <a name="word"></a><span data-ttu-id="44499-332">Word</span><span class="sxs-lookup"><span data-stu-id="44499-332">Word</span></span>

- <span data-ttu-id="44499-333">**更安全的影片體驗：** 安全性增強功能可讓您擁有更安全的線上影片體驗。</span><span class="sxs-lookup"><span data-stu-id="44499-333">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="44499-334">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-334">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- <span data-ttu-id="44499-335">**建立更易於存取的 PDF：** 建立 PDF 檔案，在儲存之前，協助工具檢查程式會指出應該修正的協助工具問題。</span><span class="sxs-lookup"><span data-stu-id="44499-335">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="44499-336">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-336">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br /><span data-ttu-id="44499-337">在[部落格文章](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="44499-337">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="44499-338">**更快速共用檔案：** 不需開啟檔案，即可從最近使用清單直接共用您的檔案。</span><span class="sxs-lookup"><span data-stu-id="44499-338">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="44499-339">**符合您情境的更多圖示：** 我們新增了超過 300 個新圖示。</span><span class="sxs-lookup"><span data-stu-id="44499-339">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="44499-340">其位置：[插入] > [圖示]。</span><span class="sxs-lookup"><span data-stu-id="44499-340">Find them at Insert > Icons.</span></span> [<span data-ttu-id="44499-341">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-341">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)<br /><span data-ttu-id="44499-342">在[部落格文章](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="44499-342">See details in [blog post](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/)</span></span>

- <span data-ttu-id="44499-343">**精確橡皮擦：** 從兩個橡皮擦尺寸中選擇，以修正小型筆跡缺陷。</span><span class="sxs-lookup"><span data-stu-id="44499-343">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="44499-344">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-344">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="44499-345">**轉換檔案，以改善協助工具功能：** 將您的檔案升級為現代格式，讓所有人更容易存取。</span><span class="sxs-lookup"><span data-stu-id="44499-345">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="44499-346">在[部落格文章](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="44499-346">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="44499-347">**勾勒草圖：** 為文件中的 Office 圖形提供隨意的手繪外觀。</span><span class="sxs-lookup"><span data-stu-id="44499-347">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="44499-348">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-348">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="44499-349">在[部落格文章](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="44499-349">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="44499-350">**尋找您要尋找的項目：** 使用搜尋方塊來尋找文字、命令、說明等。</span><span class="sxs-lookup"><span data-stu-id="44499-350">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="44499-351">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-351">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="44499-352">**不必再來回往返瀏覽器：** 您決定開啟 Office 文件連結的方式：在瀏覽器或應用程式中開啟。</span><span class="sxs-lookup"><span data-stu-id="44499-352">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="44499-353">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-353">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="44499-354">**簡歷編輯器加入 LinkedIn 簡歷小幫手：** 簡歷編輯器提供特別為簡歷量身打造的文法和樣式檢查選項，讓您的寫作更準確且更專業。</span><span class="sxs-lookup"><span data-stu-id="44499-354">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="44499-355">**其他人更快速看到您的變更：** 共同撰寫增強功能表示，共同作業者可較以往更快速看到您的變更。</span><span class="sxs-lookup"><span data-stu-id="44499-355">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="44499-356">**修正合併 3D 物件所造成的文件損毀問題：** 修正合併 3D 物件所造成的文件損毀問題。</span><span class="sxs-lookup"><span data-stu-id="44499-356">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="44499-357">**共同撰寫的增強功能**：在具有追蹤修訂的文件中共同撰寫來強化 Word 效能。</span><span class="sxs-lookup"><span data-stu-id="44499-357">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="44499-358">**共同撰寫的增強功能**：增強共同撰寫時的可靠性。</span><span class="sxs-lookup"><span data-stu-id="44499-358">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="44499-359">**在生動色彩中進行共同作業：** 註解和變更都依參與者加上色彩標示，讓您可以輕鬆查看您的共同作業者。</span><span class="sxs-lookup"><span data-stu-id="44499-359">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="44499-360">**共同編輯啟用巨集的文件：** 將 docm 檔案儲存在商務用 OneDrive，並與共同作業者即時編輯。</span><span class="sxs-lookup"><span data-stu-id="44499-360">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

### <a name="office-suite"></a><span data-ttu-id="44499-361">Office 套件</span><span class="sxs-lookup"><span data-stu-id="44499-361">Office Suite</span></span>

- <span data-ttu-id="44499-362">**在 Office 365 的 PowerPoint 中將手寫筆跡變更為圖形、文字或數學：** 從任意格式的筆跡變成 Office 圖形、文字，或以幾個筆劃變成數學運算式。</span><span class="sxs-lookup"><span data-stu-id="44499-362">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="44499-363">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-363">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="44499-366">解決的問題</span><span class="sxs-lookup"><span data-stu-id="44499-366">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="44499-367">Access</span><span class="sxs-lookup"><span data-stu-id="44499-367">Access</span></span>

- <span data-ttu-id="44499-368">此更新會修正使用 ADODB 的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-368">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="44499-369">VB 程式碼中的記錄器物件可能會不正確地報告錯誤。</span><span class="sxs-lookup"><span data-stu-id="44499-369">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="44499-370">Access 範本應不再導致資料庫中的附件欄出現故障。</span><span class="sxs-lookup"><span data-stu-id="44499-370">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="44499-371">個體化範本後，您現在應該可以將附件欄新增至資料庫。</span><span class="sxs-lookup"><span data-stu-id="44499-371">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="44499-372">此更新修正可能會導致 Microsoft Access 無法識別連結的 SQL Server 資料表中的識別資料行的問題，這可能會導致不正確地將資料列報告為已刪除。</span><span class="sxs-lookup"><span data-stu-id="44499-372">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="44499-373">此更新可修正 Microsoft Access 中的「更新查詢」執行時或在 SQL 中使用 UPDATE 陳述式時，可能導致錯誤「查詢已損壞」的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-373">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="44499-374">Excel</span><span class="sxs-lookup"><span data-stu-id="44499-374">Excel</span></span>

- <span data-ttu-id="44499-375">加速載入本機 OneDrive 資料夾中的檔案。</span><span class="sxs-lookup"><span data-stu-id="44499-375">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="44499-376">修正 CUBEVALUE 函數有時會傳回不正確結果的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-376">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="44499-377">解決開啟內嵌活頁簿時，功能區自訂無法載入的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-377">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="44499-378">在 Word 或 PowerPoint 中重新開啟內嵌的活頁簿時，在某些情況下 Excel 會當機。</span><span class="sxs-lookup"><span data-stu-id="44499-378">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="44499-379">修正操作功能表中的註解命令未顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-379">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="44499-380">我們已修正樞紐分析圖的右鍵功能表，以啟用 [顯示詳細資料] 選項。</span><span class="sxs-lookup"><span data-stu-id="44499-380">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="44499-381">解決在未開啟活頁簿時，搜尋最近使用的檔案會造成當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-381">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="44499-382">修正在相同活頁簿中按一下加入書籤的超連結會導致活頁簿隱藏的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-382">Fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="44499-383">儲存為 CSV 檔案時，在某些情況下，Excel 會將所有欄合併成單一欄。</span><span class="sxs-lookup"><span data-stu-id="44499-383">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="44499-384">在受保護工作表中的範圍使用 Range.ClearContents 可能會比預期花的時間更長。</span><span class="sxs-lookup"><span data-stu-id="44499-384">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="44499-385">修正在 [預覽列印] 中顯示表單控制項時的文字縮放比例問題。</span><span class="sxs-lookup"><span data-stu-id="44499-385">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="44499-386">與功能區互動的 VBA 宏可能會意外以 ScreenUpdating 設定為 True 執行。</span><span class="sxs-lookup"><span data-stu-id="44499-386">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="44499-387">修正在複製含有樞紐分析表的工作表後，會於某些情況下導致 Excel 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-387">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="44499-388">在某些情況下，開啟 CSV 檔案所花費的時間超過預期。</span><span class="sxs-lookup"><span data-stu-id="44499-388">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="44499-389">在某些情況下，當您切換不同縮放比例的活頁簿時，Excel 可能會當機。</span><span class="sxs-lookup"><span data-stu-id="44499-389">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="44499-390">修正 VBA 將值寫入範圍時，速度比預期慢的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-390">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="44499-391">從有色彩篩選的欄複製的資料有時候無法正確貼上。</span><span class="sxs-lookup"><span data-stu-id="44499-391">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="44499-392">開啟含有許多其他活頁簿 (尤其是含有隱藏視窗) 參照的活頁簿時，速度比預期慢。</span><span class="sxs-lookup"><span data-stu-id="44499-392">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="44499-393">解決當來源活頁簿關閉時，外部連結在填滿時 (向下填滿、跨表填滿等) 不會更新的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-393">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is& closed.</span></span>

- <span data-ttu-id="44499-394">修正透過 Teams 共用 Excel 視窗時，使用 Ctrl+Shift+方向鍵來捲動之後，可能會使得 Excel 未回應的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-394">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="44499-395">在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。</span><span class="sxs-lookup"><span data-stu-id="44499-395">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="44499-396">解決在儲存並重新開啟檔案時，圖表軸上的「值置於」屬性非預期變更的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-396">Addresses an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="44499-397">修正儲存至 SharePoint/OneDrive 時，會導致將自訂功能區索引標籤的 CustomUI XML 移除的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-397">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="44499-398">改善刪除具有合併儲存格的欄時的效能。</span><span class="sxs-lookup"><span data-stu-id="44499-398">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="44499-399">修正 [列印] 對話方塊的印表機清單中，印表機名稱可能會重複的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-399">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="44499-400">修正當檔案路徑太長時，在重新開啟檔案後，外部連結會停止運作的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-400">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="44499-401">修正列印時表單控制項的核取方塊縮放的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-401">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="44499-402">當您使用舊版的「共用活頁簿」模式，嘗試為活頁簿的新工作表列出變更時，就會發生當機。</span><span class="sxs-lookup"><span data-stu-id="44499-402">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="44499-403">在已篩選清單中插入欄的時間會比預期更長。</span><span class="sxs-lookup"><span data-stu-id="44499-403">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="44499-404">我們已修正某些複製和貼上的圖表連結使用的是對應磁碟機位址，而不是通用位址的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-404">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="44499-405">修正因為增益集是以字母順序載入，而不是以使用者指定的順序載入，而顯示 [這個活頁簿目前正由其他活頁簿所參考中，不可關閉] 錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-405">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="44499-406">修正按一下已開啟活頁簿中某個位置的超連結時，活頁簿可能會隱藏的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-406">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="44499-407">開啟含有許多其他活頁簿 (尤其是含有隱藏視窗) 參照的活頁簿時，速度比預期慢。</span><span class="sxs-lookup"><span data-stu-id="44499-407">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="44499-408">使用 VBA 應用程式的 Application.Evaluate 在某些情況下，對使用者定義的函數無法運作。</span><span class="sxs-lookup"><span data-stu-id="44499-408">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="44499-409">修正某些使用者使用內嵌和連結物件 (OLE) 時可能發生的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-409">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="44499-410">使用者在使用某些非英文字元集的情況下，儲存變更時可能會遇到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-410">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="44499-411">此更新可修正會導致資料編輯列以較預期不同的字型顯示文字的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-411">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="44499-412">使用者在使用某些非英文字元集的情況下，儲存變更時可能會遇到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-412">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="44499-413">解決捲動後選取儲存格時，可能導致選取錯誤儲存格的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-413">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="44499-414">使用者在存取隱藏的命名範圍時可能會遇到錯誤。</span><span class="sxs-lookup"><span data-stu-id="44499-414">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="44499-415">從不受信任的網路共用編輯受保護的檔案時，Excel 可能會發生問題。</span><span class="sxs-lookup"><span data-stu-id="44499-415">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="44499-416">某些當地語系化版本的 [文字到欄] 功能可能會失敗。</span><span class="sxs-lookup"><span data-stu-id="44499-416">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="44499-417">解決從範本建立圖表時的效能問題。</span><span class="sxs-lookup"><span data-stu-id="44499-417">Addresses a performance issue when creating charts from templates.</span></span>

- <span data-ttu-id="44499-418">修正對具有溢出陣列之儲存格進行資料剖析的轉換時，導致某些使用者發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-418">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="44499-419">使用 Range.Value 和 Range.Value2 (VBA) 會導致公式以動態陣列的形式輸入。</span><span class="sxs-lookup"><span data-stu-id="44499-419">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

- <span data-ttu-id="44499-420">修正公式開頭的 @ 符號會被視為隱含交集運算子的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-420">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

- <span data-ttu-id="44499-421">我們已修正包含多個含有定義名稱的公式，會導致儲存檔案時間加長的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-421">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

- <span data-ttu-id="44499-422">此變更利用軟體轉譯，以避免特定 Intel 圖形驅動程式的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-422">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="44499-423">解決重新命名簽名時，會導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-423">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="onenote"></a><span data-ttu-id="44499-424">OneNote</span><span class="sxs-lookup"><span data-stu-id="44499-424">OneNote</span></span>

- <span data-ttu-id="44499-425">透過暫時調整 OneNote 2016 中的同步處理頻率，來改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="44499-425">Improve sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="44499-426">透過暫時延遲下載線上筆記本中內嵌的檔案和影像，直到使用者瀏覽至 OneNote 2016 中的頁面，來改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="44499-426">Improve sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="44499-427">透過暫時停用 OneNote 2016 中的資源回收筒，來改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="44499-427">Improve sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="44499-428">當使用者嘗試刪除通常會傳送到 [資源回收筒] 的資料時，系統會詢問使用者是否希望保留或永久刪除資料。</span><span class="sxs-lookup"><span data-stu-id="44499-428">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="44499-429">透過暫時將 OneNote 2016 中版本歷程記錄頁面的數目和同步處理頻率降低，來改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="44499-429">Improve sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="44499-430">顯示通知，讓使用者可以了解更多 OneNote 使用者體驗中正在採取的臨時措施的資訊，以改善同步處理和服務穩定性。</span><span class="sxs-lookup"><span data-stu-id="44499-430">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="44499-431">透過暫時將 OneNote 2016 中新嵌入附件的最大允許大小減少為 50 MB，來改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="44499-431">Improve sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="44499-432">對於超過此限制的檔案，使用者可以選擇將檔案上傳到 OneDrive，並將連結插入 OneNote。</span><span class="sxs-lookup"><span data-stu-id="44499-432">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="44499-433">透過暫時停用 OneNote 2016 中的應用程式內視訊錄製，來改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="44499-433">Improve sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="44499-434">本機筆記本不受這個測量的影響。</span><span class="sxs-lookup"><span data-stu-id="44499-434">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="44499-435">對通知進行本地化，讓使用者可以了解更多 OneNote 使用者體驗中正在採取的臨時措施的資訊，以改善同步處理和服務穩定性。</span><span class="sxs-lookup"><span data-stu-id="44499-435">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="44499-436">Outlook</span><span class="sxs-lookup"><span data-stu-id="44499-436">Outlook</span></span>

- <span data-ttu-id="44499-437">我們已修正以下問題：當使用多個不同解析度的監視器時，輸入法編輯器 (IEM) 視窗會覆蓋透過 IME 輸入的文字。</span><span class="sxs-lookup"><span data-stu-id="44499-437">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="44499-438">解決會導致使用者在 Outlook 中偶爾看到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-438">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

- <span data-ttu-id="44499-439">此這會更新 Outlook 中的附件封鎖邏輯，以同時封鎖 Python 附件。</span><span class="sxs-lookup"><span data-stu-id="44499-439">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="44499-440">解決會導致網頁增益集存取數位版權管理訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-440">Addresses an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="44499-441">解決會導致週期性約會或會議在接近時區定義變更時於錯誤的時間顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-441">Addresses an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="44499-442">在 2019 年使用巴西時區時，週期性會議和約會以 2020 年的錯誤時段顯示。</span><span class="sxs-lookup"><span data-stu-id="44499-442">When using the Brazilia time zone in the year 2019, recurring meetings and appointments are displayed in the wrong timeslot for the year 2020.</span></span> <span data-ttu-id="44499-443">此變更與設定使用巴西時區的用戶端或設定使用該時區的會議和約會相關。</span><span class="sxs-lookup"><span data-stu-id="44499-443">This change is relevant for clients set in the Brazilia time zone or for meetings and appointments set in that time zone.</span></span><br><br><span data-ttu-id="44499-444">此變更會允許 Outlook 覆寫 Outlook 所使用的特定時區設定。</span><span class="sxs-lookup"><span data-stu-id="44499-444">This change allows Outlook to override certain time zone settings used by Outlook.</span></span> <span data-ttu-id="44499-445">若要叫用時區覆寫，您必須為目前的使用者設定登錄機碼。</span><span class="sxs-lookup"><span data-stu-id="44499-445">In order to invoke a time zone override you must set a registry key for the current user.</span></span> <span data-ttu-id="44499-446">登錄機碼名稱必須符合時區的內部名稱。</span><span class="sxs-lookup"><span data-stu-id="44499-446">The registry key name must match the internal name of the time zone.</span></span> <span data-ttu-id="44499-447">值表示時區規則的年，用來取代生效年。</span><span class="sxs-lookup"><span data-stu-id="44499-447">The value indicates the time zone rule's year to be used in place of the effective year.</span></span> <span data-ttu-id="44499-448">例如，下列登錄機碼覆寫值將使用巴西時區規則做為 2020 年的生效規則。</span><span class="sxs-lookup"><span data-stu-id="44499-448">For example, the following registry key override value will use the Brazilia time zone rule for the year 2020 as the effective rule.</span></span> <span data-ttu-id="44499-449">HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"E.</span><span class="sxs-lookup"><span data-stu-id="44499-449">HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"E.</span></span> <span data-ttu-id="44499-450">South America Standard Time"=dword:000007e4.</span><span class="sxs-lookup"><span data-stu-id="44499-450">South America Standard Time"=dword:000007e4.</span></span>

- <span data-ttu-id="44499-451">解決會導致使用者在會議中看到位置欄位非預期變更的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-451">Addresses an issue that caused users to see the location field in meetings change unexpectedly.</span></span>

- <span data-ttu-id="44499-452">解決會導致會議中的 [位置] 欄位非預期更新的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-452">Addresses an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="44499-453">解決會導致會議位置在清除之後，又會非預期地重新加回會議的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-453">Addresses an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="44499-454">解決會導致會議的位置欄位中的逗號變成分號的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-454">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="44499-455">可透過原生 Teams 用戶端直接加入 Teams 會議。</span><span class="sxs-lookup"><span data-stu-id="44499-455">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="44499-456">解決會導致使用 Exchange 2010 伺服器上信箱的使用者，在將附件新增至行事曆項目時遇到問題的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-456">Addresses an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="44499-457">解決會導致使用者在回覆數位簽章郵件時遇到問題的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-457">Addresses an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="44499-458">解決會導致使用者無法開啟某些週期性行事曆項目執行個體的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-458">Addresses an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="44499-459">解決在某些情況下，[群組] 標題會非預期展開的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-459">Addresses an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="44499-460">解決會導致資料夾窗格寬度非預期地變更的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-460">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="44499-461">解決 Outlook 無法為已支付 M365 Business Plus 方案服務的使用者啟用「資料外洩防護」原則提示的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-461">Addresses an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="44499-462">解決當使用者透過鍵盤快速鍵與信箱資料夾互動時，會導致明顯延遲的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-462">Addresses an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="44499-463">解決在多個視窗中檢視相同項目時可能會導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-463">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="44499-464">解決會導致使用者在 Outlook 中更新其規則時，看到「此電腦上的規則與 Microsoft Exchange 上的規則不相符」訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-464">Addresses an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="44499-465">解決會導致非常長時間的 Outlook 工作階段記憶體流失的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-465">Addresses an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="44499-466">解決會導致使用者在指定無效寄件者地址時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-466">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="44499-467">解決會導致使用者在開啟 [規則] 對話方塊時看到「此電腦上的規則與 Microsoft Exchange 上的規則不相符」提示的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-467">Addresses an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="44499-468">解決會導致在某些情況下，用來停用標幟項目醒目提示的選項無法使用的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-468">Addresses an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="44499-469">解決在關閉協助工具檢查程式窗格之後按 S 鍵時，會導致使用者看到郵件非預期傳送的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-469">Addresses an issue that caused users to see mails unexpectedly send when pressing the "S" key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="44499-470">解決重新命名簽名時，會導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-470">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="44499-471">解決會導致使用者在取消帳戶設定時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-471">Addresses an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="44499-472">解決即使將同步處理滑桿設定為較小的設定，也會導致 Outlook 非預期地同步處理所有郵件的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-472">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="44499-473">解決會導致使用黑色佈景主題的使用者，看到 [寄件者] 下拉式功能表在白色背景上顯示白色文字的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-473">Addresses an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>

- <span data-ttu-id="44499-474">解決會導致使用者在建立設定檔期間遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-474">Addresses an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="44499-475">解決會導致使用者在嘗試從 [帳戶建立] 內容連絡支援服務時，看到具有 [確定] 按鈕的空白訊息方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-475">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="44499-476">解決會導致使用者在嘗試從 [帳戶建立] 內容連絡支援服務時，看到具有 [確定] 按鈕的空白訊息方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-476">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="44499-477">解決會導致協力廠商應用程式無法傳送電子郵件的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-477">Addresses an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="44499-478">解決有時候會導致類別從電子郵件訊息中消失的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-478">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="44499-479">解決會導致伺服器作業系統上的 Outlook 使用者看到「防毒軟體狀態: 無效」的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-479">Addresses an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="44499-480">此版本的 Windows 支援防毒軟體偵測，但即使已適當設定防毒軟體，也找不到防毒軟體。</span><span class="sxs-lookup"><span data-stu-id="44499-480">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

- <span data-ttu-id="44499-481">解決會導致代理人在不同機器上所看到的共用信箱有不同資料夾階層的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-481">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="44499-482">解決在編輯經理行事曆上的現有行事曆約會時，導致代理人收到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-482">Addresses an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="44499-483">解決會導致使用不正確瀏覽器模擬設定的使用者，無法完成 Gmail 身分驗證提示的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-483">Addresses an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="44499-484">解決會導致若「未」核取 [下載共用資料夾]，共用行事曆會議的 [回應選項] 中會遺失 [允許轉寄] 選項的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-484">Addresses an issue that caused the " Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="44499-485">解決會導致在 Windows 更新之後，使用者嘗試開啟 .msg 和 .oft 檔案時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-485">Addresses an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="44499-486">解決會導致使用滑鼠上的 X 按鈕時，使用者偶爾遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-486">Addresses an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="44499-487">解決會導致使用者在選取特定搜尋結果時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-487">Addresses an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="44499-488">解決會讓 [附件工具] 中的 [儲存至雲端] 按鈕不見的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-488">Addresses an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="44499-489">此變更可還原在郵件標頭中檢視多行主旨的功能。</span><span class="sxs-lookup"><span data-stu-id="44499-489">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="44499-490">解決當兩個增益集將一個按鈕新增到相同功能區群組時，會導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-490">Addresses an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="44499-491">解決當租用戶預設權限設定為「任何人」時，會導致無法將連結新增至具有正確租用戶預設權限的電子郵件的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-491">Addresses an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as "anyone".</span></span>

- <span data-ttu-id="44499-492">解決會導致使用者無法將電子郵件傳送到個人通訊群組清單的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-492">Addresses an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="44499-493">解決在轉寄大型 HTML 郵件時，會導致使用者看到郵件內文截斷的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-493">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="44499-494">修正 SMIME 演算法選取的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-494">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="44499-495">我們已修正可能會防止將檔案儲存到 WebDAV 位置的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-495">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="44499-496">解決選取安全性對話方塊上的 [儲存] 選項時，會導致使用者無法將來自其租用戶外部的 OneDrive 附件儲存至其本機電腦的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-496">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="44499-497">解決在編輯主旨之後，會導致 NDR 訊息的本文從 Unicode 變更為 ASCII 的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-497">Addresses an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="44499-498">解決會導致使用者在 Outlook 處理程序中看到記憶體流失的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-498">Addresses an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="44499-499">解決在某些情況下，導致使用者看到電子郵件傳送到與顯示的 SMTP 位址不相符之地址的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-499">Addresses an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="44499-500">解決會導致搜尋方塊在高 DPI 模式中對齊不當的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-500">Addresses an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="44499-501">解決在擷取雲端設定時，會導致使用者在 Outlook 中遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-501">Addresses an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="44499-502">解決會導致在搜尋意見反應體驗中懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-502">Addresses an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="44499-503">解決會導致使用者在 Outlook 中偶爾看到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-503">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

- <span data-ttu-id="44499-504">解決重新命名簽名時，會導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-504">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="44499-505">解決會導致使用者在建立設定檔期間遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-505">Addresses an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="44499-506">解決會導致使用者在 Outlook 中偶爾看到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-506">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="44499-507">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="44499-507">PowerPoint</span></span>

- <span data-ttu-id="44499-508">解決在舊版 PPT 註解中使用操作功能表時，可能會導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-508">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

- <span data-ttu-id="44499-509">改善複製貼上的案例：將 PowerPoint 投影片中的圖形複製並重複貼到其他投影片中，可能會出現例外狀況而失敗。</span><span class="sxs-lookup"><span data-stu-id="44499-509">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>

- <span data-ttu-id="44499-510">修正問題，以在開啟的檔案複本具有改善的註解時，為使用者轉送正確的訊息。</span><span class="sxs-lookup"><span data-stu-id="44499-510">Fixes an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="project"></a><span data-ttu-id="44499-511">Project</span><span class="sxs-lookup"><span data-stu-id="44499-511">Project</span></span>

- <span data-ttu-id="44499-512">修正無法正確計算摘要工作日期的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-512">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="44499-513">修正不先執行 OpenUndoTransaction 方法就不能觸發 OnUndoOrRedo 事件的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-513">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="44499-514">修正透過 [已停用] 按鈕停用/啟動工作時，ProjectBeforeTaskChange 事件無法偵測的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-514">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="44499-515">修正儲存使用舊版 Project 建立的專案時，Project 可能當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-515">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="44499-516">發現在開啟唯讀專案時，使用者可能會收到數個訊息的問題</span><span class="sxs-lookup"><span data-stu-id="44499-516">Identified an issue where users could get several messages when opening a read-only project</span></span>

- <span data-ttu-id="44499-517">修正以下問題：固定工期類型的 100% 工作可能會誤將其完成百分比計算為小於 100% 完成。</span><span class="sxs-lookup"><span data-stu-id="44499-517">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

### <a name="word"></a><span data-ttu-id="44499-518">Word</span><span class="sxs-lookup"><span data-stu-id="44499-518">Word</span></span>

- <span data-ttu-id="44499-519">解決會導致使用滑鼠上的 X 按鈕時，使用者偶爾遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-519">Addresses an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="44499-520">我們已修正文件中的文字對齊，在使用 [快速列印] 進行列印之後嘗試進行編輯時變得混亂的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-520">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="44499-521">我們已修正表格中最適文字大小的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-521">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="44499-522">我們已修正插入水平線無法更短並置中的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-522">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>

- <span data-ttu-id="44499-523">建置組塊組合管理可能會顯示無效的通知：「您已經修改樣式、建置組塊」。</span><span class="sxs-lookup"><span data-stu-id="44499-523">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

- <span data-ttu-id="44499-524">我們已修正啟用原則 FileBlick\Word2007Files 時共同編輯中的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-524">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="44499-525">我們已修正新增已重新命名之查閱欄位時，Word QuickPart 無法使用的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-525">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

- <span data-ttu-id="44499-526">我們已修正將兩份文件合併成一份文件時的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-526">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="44499-527">修正受保護無法編輯之文件的比較功能問題。</span><span class="sxs-lookup"><span data-stu-id="44499-527">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="44499-528">此更新解決了 Microsoft Word 中的一個問題：如果標籤原則套用了頁首或頁尾或浮水印，那麼在套用敏感度標籤時，插入長度超過 255 個字元的文字後續將無法透過變更或刪除標籤來識別和刪除。</span><span class="sxs-lookup"><span data-stu-id="44499-528">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

### <a name="office-suite"></a><span data-ttu-id="44499-529">Office 套件</span><span class="sxs-lookup"><span data-stu-id="44499-529">Office Suite</span></span>

- <span data-ttu-id="44499-530">修正當共同撰寫大型 PowerPoint 檔案時，使用者可能會遇到過度網路和 CPU 使用量的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-530">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="44499-531">此修正可解決已在用戶端中快取檔案時，Project 應用程式不應封鎖網路的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-531">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>


- <span data-ttu-id="44499-532">我們將後台中的頻道名稱更新為2020年1月 Fork 的新通道名稱，解決了此問題。</span><span class="sxs-lookup"><span data-stu-id="44499-532">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="44499-533">我們已修正此問題，如果裝置受政策管理，將不會調用 DMS 聽眾 API。</span><span class="sxs-lookup"><span data-stu-id="44499-533">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="44499-534">我們已解決在單一交易中新增和移除應用程式時，移除不完整的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-534">We have resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="44499-535">修正相對期限只有在第一次設定時才會有效的 ODT 和 GPO 更新期限設定中的錯誤 (bug)。此修正可啟用後續更新的相關期限。</span><span class="sxs-lookup"><span data-stu-id="44499-535">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="44499-536">解決 Office 更新可能會非預期地從 Office CDN 而不是預期使用的來源 (例如本機或網路共用或 Configuration Manager 提供的位置) 下載檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-536">Resolves an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="44499-537">修正相對期限只有在第一次設定時才會有效的 ODT 和 GPO 更新期限設定中的錯誤 (bug)。此修正可啟用後續更新的相關期限。</span><span class="sxs-lookup"><span data-stu-id="44499-537">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="44499-538">我們將新的 AppV51 放置向後移植，以修正先前 AppV51 中的迴歸。</span><span class="sxs-lookup"><span data-stu-id="44499-538">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="44499-539">我們已解決內部作業在失敗時擲出例外狀況，而不是記錄和繼續進行的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-539">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="44499-540">受影響的使用者將不會再無法收到更新。</span><span class="sxs-lookup"><span data-stu-id="44499-540">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="44499-541">我們的團隊已在半年企業預覽的 Office CDN 網域中新增報告遙測的用戶端支援。</span><span class="sxs-lookup"><span data-stu-id="44499-541">Our team has added client support for reporting telemetry on the Office CDN domains in Semi-Annual Enterprise Preview.</span></span>

- <span data-ttu-id="44499-542">此變更可解決利用 Intel Integrated GPU 的圖形配接卡所報告的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-542">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="44499-543">這項變更可確保草繪大綱可在功能區中正常運作。</span><span class="sxs-lookup"><span data-stu-id="44499-543">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="44499-544">修正使用一些特定 proxy 設定時，從內部部署位置開啟檔案時發生的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-544">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="44499-545">此更新修正了 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。</span><span class="sxs-lookup"><span data-stu-id="44499-545">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="44499-546">修正問題，可在 Office 遞交工作階段期間消除當機，並改善使用者體驗中的可靠性。</span><span class="sxs-lookup"><span data-stu-id="44499-546">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>

- <span data-ttu-id="44499-547">這個錯誤會更新增強的設定服務 (ECS) url 端點。</span><span class="sxs-lookup"><span data-stu-id="44499-547">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="44499-548">呼叫這個較新的端點，可從 ECS 進行提取獲得更高的成功率。</span><span class="sxs-lookup"><span data-stu-id="44499-548">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

- <span data-ttu-id="44499-549">此更新可修正在檢視或撰寫郵件時，Microsoft Outlook 未顯示目前的敏感度標籤的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-549">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="44499-550">修正在 Word/Excel/PowerPoint 中開啟來自相同 SharePoint 文件庫的多個文件時，僅掃描開啟的第一個文件是否符合原則的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-550">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

- <span data-ttu-id="44499-551">為了保護 Office 客戶的安全性，我們現在專門使用 SHA-2 演算法來簽署 Microsoft Office 更新。</span><span class="sxs-lookup"><span data-stu-id="44499-551">To protect Office customers’ security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

- <span data-ttu-id="44499-552">當您啟用增益集，而登錄金鑰 HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth 被設為零時，辦公主機視窗會關閉。</span><span class="sxs-lookup"><span data-stu-id="44499-552">The office host was closing in windows, when an add-in is being activated while the registry key  HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="44499-553">此變更將修正此問題。</span><span class="sxs-lookup"><span data-stu-id="44499-553">This change would fix this issue.</span></span>

- <span data-ttu-id="44499-554">解決 Access 和 Publisher 因所安裝的語言而無法正常啟動的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-554">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)





[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-july-14"></a><span data-ttu-id="44499-557">版本 1908：7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="44499-557">Version 1908: July 14</span></span>
<span data-ttu-id="44499-558">*版本 1908 (組建 11929.20904)*</span><span class="sxs-lookup"><span data-stu-id="44499-558">*Version 1908 (Build 11929.20904)*</span></span>

<span data-ttu-id="44499-559">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-559">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="44499-561">解決的問題</span><span class="sxs-lookup"><span data-stu-id="44499-561">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="44499-562">Access</span><span class="sxs-lookup"><span data-stu-id="44499-562">Access</span></span>

- <span data-ttu-id="44499-563">此更新修正彙總 (例如 Sum) 可能會將結果截斷成整數值的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-563">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="44499-564">此更新修正包含參照遠端桌面 (例如 SQL Server 桌面) 的聯集查詢可能造成 Access 關閉並重新啟動的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-564">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="44499-565">此更新可修正 Microsoft Access 中的「更新查詢」執行時或在 SQL 中使用 UPDATE 陳述式時，可能導致錯誤「查詢已損壞」的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-565">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="44499-566">Excel</span><span class="sxs-lookup"><span data-stu-id="44499-566">Excel</span></span>

- <span data-ttu-id="44499-567">文件標題的荷蘭文按鍵提示已變更為 Alt-G。</span><span class="sxs-lookup"><span data-stu-id="44499-567">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="44499-568">修正在 Excel 中指派給圖形或表單控制項的巨集可能顯示不正確的錯誤訊息，或者可能會處理不正確目標範圍的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-568">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="44499-569">解決「尋找及取代」在找到第一個項目後，對話方塊中的焦點位置變更的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-569">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="44499-570">此更新修正在與其他使用者共同撰寫的工作階段中變更樞紐分析表排序的方式，然後重新整理可能觸發當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-570">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="44499-571">我們已修正當 OLAP 樞紐分析表的篩選條件設定為已從 cube 移除的值時會發生的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-571">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="44499-572">此更新已修正使用 VBA 將影像新增到圖表的頁首/頁尾時發生錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-572">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="44499-573">我們已修正當變更系列集合時，可能會導致散佈折線圖無法正確呈現的問題</span><span class="sxs-lookup"><span data-stu-id="44499-573">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection</span></span>

- <span data-ttu-id="44499-574">修正以校正使用圖表範本插入圖表時，預覽中使用的色彩。</span><span class="sxs-lookup"><span data-stu-id="44499-574">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="44499-575">已解決當插入或刪除儲存格時，瀑布圖和漏斗圖無法與表格同步處理的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-575">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="44499-576">修正 Excel 中合併衝突的問題，此問題會造成提示使用者重新開啟活頁簿以取得變更。</span><span class="sxs-lookup"><span data-stu-id="44499-576">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="44499-577">已解決造成執行階段錯誤啟動最小化視窗的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-577">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="44499-578">解決了開啟內嵌活頁簿時，功能區自訂無法載入的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-578">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="44499-579">已解決導致表格旁的剪下並貼上作業在與其他人共同撰寫時失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-579">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="44499-580">解決使用執行中巨集變更自訂屬性時，會導致共同撰寫中斷的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-580">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="44499-581">發生您無法從增益集開啟的 WPF (Windows Presentation Foundation) 表單的下拉式方塊選取項目的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-581">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="44499-582">解決在未開啟活頁簿時，搜尋最近使用的檔案會造成當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-582">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="44499-583">修正在預覽列印或列印時，群組方塊控制項的框線無法顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-583">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="44499-584">修正當活頁簿中有外部連結時，有些使用者可能會遇到多個快顯視窗的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-584">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="44499-585">已修正使用者在使用 VBA 巨集清除範圍內容時可能遇到的效能問題。</span><span class="sxs-lookup"><span data-stu-id="44499-585">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="44499-586">修正 VBA 將值寫入範圍時，速度比預期慢的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-586">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="44499-587">解決在儲存並重新開啟檔案時，圖表軸上的「值置於」屬性非預期變更的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-587">Addresses an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="44499-588">在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。</span><span class="sxs-lookup"><span data-stu-id="44499-588">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="44499-589">修正在刪除包含合併儲存格的資料行時，會導致效能變慢的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-589">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="44499-590">修正在 [預覽列印] 中顯示表單控制項時的文字縮放比例問題。</span><span class="sxs-lookup"><span data-stu-id="44499-590">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="44499-591">將依色彩篩選的資料複製到具有不同寬度的欄時，值無法貼上。</span><span class="sxs-lookup"><span data-stu-id="44499-591">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

- <span data-ttu-id="44499-592">修正當 Excel 視窗透過 Teams 共用時，使用 Ctrl + Shift + 方向鍵滑動後，Excel 可能會無法回應的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-592">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="44499-593">修正列印時表單控制項的核取方塊縮放的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-593">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="44499-594">修正在相同活頁簿中按一下加入書籤的超連結會導致活頁簿隱藏的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-594">Fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="44499-595">當您使用舊版的「共用活頁簿」模式，嘗試為活頁簿的新工作表列出變更時，就會發生當機。</span><span class="sxs-lookup"><span data-stu-id="44499-595">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="44499-596">[資料剖析] 功能對某些地區設定可能會失敗。</span><span class="sxs-lookup"><span data-stu-id="44499-596">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="44499-597">使用者在存取隱藏的命名範圍時可能會遇到錯誤。</span><span class="sxs-lookup"><span data-stu-id="44499-597">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="44499-598">使用者在使用某些非英文字元集的情況下，儲存變更時可能會遇到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-598">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="44499-599">修正圖表標題中影像檔案大小在儲存包含圖表的活頁簿時增加的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-599">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>

- <span data-ttu-id="44499-600">非同步使用者定義函數造成的效能問題，導致它們同步執行。</span><span class="sxs-lookup"><span data-stu-id="44499-600">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="44499-601">已大幅改善刪除有合併儲存格之欄的效能。</span><span class="sxs-lookup"><span data-stu-id="44499-601">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="44499-602">解決捲動後選取儲存格時，可能導致選取錯誤儲存格的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-602">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="44499-603">已解決 Lookup 函數可能會傳回錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-603">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="44499-604">修正以下問題：將選取範圍與交互參照的活頁簿保持同步時，導致交互參照的活頁簿中的 DBCS 字元損毀。</span><span class="sxs-lookup"><span data-stu-id="44499-604">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="44499-605">已解決使用自動調整來調整列高時，核取方塊可能收縮的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-605">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>

- <span data-ttu-id="44499-606">當檔案具備大量設定格式化的條件時，按一下 [字型色彩] 按鈕時出現的效能緩慢問題。</span><span class="sxs-lookup"><span data-stu-id="44499-606">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="44499-607">我們已修正預覽列印中的列印範圍不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-607">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="44499-608">從不受信任的網路共用編輯受保護的檔案時，Excel 可能會發生問題。</span><span class="sxs-lookup"><span data-stu-id="44499-608">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="44499-609">我們已大幅提升依色彩篩選的效能。</span><span class="sxs-lookup"><span data-stu-id="44499-609">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="44499-610">解決在目前的 Office 版本中開啟在舊版 Office 中建立的活頁簿時，可能導致 Excel 懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-610">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="44499-611">在增益集管理員中瀏覽時，可顯示 16 個以上的增益集。</span><span class="sxs-lookup"><span data-stu-id="44499-611">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="44499-612">解決會防止將超連結貼到一些受保護工作表中的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-612">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="44499-613">這項變更透過利用軟體轉譯避免特定 Intel 圖形驅動程式發生問題。</span><span class="sxs-lookup"><span data-stu-id="44499-613">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="44499-614">來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。</span><span class="sxs-lookup"><span data-stu-id="44499-614">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="44499-615">此更新修正 Office 文件無法上傳到商務用 OneDrive 的錯誤 (訊息「上傳失敗」)。</span><span class="sxs-lookup"><span data-stu-id="44499-615">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="44499-616">修正在 Excel 構想功能中，在 Win32 用戶端中按一下 [構想] 按鈕來載入增益集時會發生錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-616">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span> 

### <a name="onenote"></a><span data-ttu-id="44499-617">OneNote</span><span class="sxs-lookup"><span data-stu-id="44499-617">OneNote</span></span>

- <span data-ttu-id="44499-618">對通知進行本地化，讓使用者可以了解更多 OneNote 使用者體驗中正在採取的臨時措施的資訊，以改善同步處理和服務穩定性。</span><span class="sxs-lookup"><span data-stu-id="44499-618">Localizes the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="44499-619">Outlook</span><span class="sxs-lookup"><span data-stu-id="44499-619">Outlook</span></span>

- <span data-ttu-id="44499-620">來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。</span><span class="sxs-lookup"><span data-stu-id="44499-620">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="44499-621">修正使用者將信箱從基本驗證升級為新式驗證後，造成將錯誤的帳戶與其 Outlook 設定檔相關聯的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-621">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="44499-622">解決會導致網頁增益集在不該存取數位版權管理訊息時進行存取的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-622">Addresses an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="44499-623">解決會導致部分安全連結無法顯示簡單動態顯示 URL 的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-623">Addresses an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="44499-624">此這會更新 Outlook 中的附件封鎖邏輯，以同時封鎖 Python 附件。</span><span class="sxs-lookup"><span data-stu-id="44499-624">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="44499-625">解決導致部分 POP3 使用者查看所有純文字格式電子郵件 (無論設定) 的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-625">Addresses an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="44499-626">此修正將會還原 HTML 格式郵件的檢視。</span><span class="sxs-lookup"><span data-stu-id="44499-626">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="44499-627">解決在使用者將項目從其主要行事曆複製到群組行事曆時，會導致使用者遇到權限錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-627">Addresses an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="44499-628">解決會導致使用者無法透過螢幕助讀程式存取位置建議的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-628">Addresses an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="44499-629">解決當使用者透過鍵盤快速鍵與信箱資料夾互動時，會導致明顯延遲的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-629">Addresses an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="44499-630">解決會導致非常長時間的 Outlook 工作階段記憶體流失的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-630">Addresses an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="44499-631">解決會導致使用者在指定無效寄件者地址時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-631">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="44499-632">解決會導致使用者在開啟 [規則] 對話方塊時看到「此電腦上的規則與 Microsoft Exchange 上的規則不相符」提示的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-632">Addresses an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="44499-633">解決會導致使用者在與特定安全連結互動時在 Outlook 中遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-633">Addresses an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="44499-634">解決會導致經理對於代理人是否已經回覆特定會議邀請含混不清的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-634">Addresses an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="44499-635">解決會導致使用者在處理某些自動探索回應時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-635">Addresses an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="44499-636">解決會導致使用者在嘗試從 [帳戶建立] 內容連絡支援服務時，看到具有 [確定] 按鈕的空白訊息方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-636">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="44499-637">此變更可讓系統管理員啟用一個原則，以在自動探索驗證提示中較 UPN 優先使用所提供的帳戶電子郵件。</span><span class="sxs-lookup"><span data-stu-id="44499-637">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="44499-638">依預設，自動探索會優先於帳戶 UPN (如果有的話)。</span><span class="sxs-lookup"><span data-stu-id="44499-638">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="44499-639">解決會導致使用者看到針對新式群組的搜尋失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-639">Addresses an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="44499-640">解決會導致 Outlook 使用者在特定案例中停滯在「需要密碼」狀態的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-640">Addresses an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="44499-641">解決會導致使用者處理衝突郵件時遇到同步失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-641">Addresses an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="44499-642">解決會導致在套用最新的 Windows 更新之後，使用者開啟 .msg 和 .oft 檔案時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-642">Addresses an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="44499-643">解決會導致使用者在啟動 Outlook 時，在「正在載入設定檔」畫面遇到停滯的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-643">Addresses an issue that caused users to experience a hang at the "Loading Profile" screen when Outlook is starting up.</span></span>

- <span data-ttu-id="44499-644">解決會導致使用者在選取特定搜尋結果時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-644">Addresses an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="44499-645">解決會讓 [附件工具] 中的 [儲存至雲端] 按鈕不見的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-645">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="44499-646">根據預設，保留原則標籤會將保留時間顯示於括弧中。</span><span class="sxs-lookup"><span data-stu-id="44499-646">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="44499-647">此修正提供登錄機碼，讓系統管理員能夠指定只應顯示的原則名稱。</span><span class="sxs-lookup"><span data-stu-id="44499-647">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="44499-648">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = 預設值 1 = 我們只會顯示保留原則文字的 PolicyName。</span><span class="sxs-lookup"><span data-stu-id="44499-648">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = Default 1 = we will only show the PolicyName for Retention policy text.</span></span>

- <span data-ttu-id="44499-649">解決會導致使用者在關閉 Outlook 時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-649">Addresses an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="44499-650">解決會導致客戶在某些情況下看到空白會議室清單的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-650">Addresses an issue that caused customers to see an empty room list in some scenarios.</span></span>

- <span data-ttu-id="44499-651">解決會導致使用者在變更檢視時看到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-651">Addresses an issue that caused users to see intermittent crashes when changing views.</span></span>

- <span data-ttu-id="44499-652">已解決以下問題：使用者將共用行事曆資料夾同步到 OST 時發生問題，這導致嘗試與這些資料夾互動時發生權限錯誤。</span><span class="sxs-lookup"><span data-stu-id="44499-652">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>

- <span data-ttu-id="44499-653">解決會導致使用者在 Citrix 環境中檢視 30 個以上的行事曆時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-653">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="44499-654">此處是[記錄舊版問題的個別 KB](https://support.microsoft.com/en-us/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)</span><span class="sxs-lookup"><span data-stu-id="44499-654">Here's the individual [KB where this was documented for previous versions](https://support.microsoft.com/en-us/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)</span></span>

- <span data-ttu-id="44499-655">修正 SMIME 演算法選取的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-655">Corrects an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="44499-656">解決會導致使用其他寄件者時，無法顯示原則提示的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-656">Addresses an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="44499-657">解決會導致使用者看到在該會議室的可用時間以外進行之會議的會議室建議的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-657">Addresses an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="44499-658">解決非英文使用者的郵件中，主旨列會相當小的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-658">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="44499-659">解決會導致使用者嘗試從「未接的交談」訊息建立規則時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-659">Addresses an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="44499-660">解決會導致某些使用者在新增次要 Exchange 帳戶時看到建立了重複的特殊資料夾的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-660">Addresses an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="44499-661">解決在轉寄大型 HTML 郵件時，會導致使用者看到郵件內文截斷的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-661">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="44499-662">解決會導致使用者在 Outlook 處理程序中看到記憶體流失的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-662">Addresses an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="44499-663">解決會導致使用者在更新目前狀態資訊時遇到間歇性當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-663">Addresses an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="44499-664">解決會導致目前的資料夾搜尋間歇性失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-664">Addresses an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="44499-665">解決嘗試擷取使用者的 Outlook 雲端設定時，會導致一些使用者遇到驗證錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-665">Addresses an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="44499-666">解決會導致在搜尋意見反應體驗中懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-666">Addresses an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="44499-667">解決會導致使用者在處理某些自動探索回應時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-667">Addresses an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="44499-668">解決會導致使用者在更新目前狀態資訊時遇到間歇性當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-668">Addresses an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="44499-669">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="44499-669">PowerPoint</span></span>

- <span data-ttu-id="44499-670">來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。</span><span class="sxs-lookup"><span data-stu-id="44499-670">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="44499-671">此變更還原 PowerPoint 影片控制項的協助工具名稱的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-671">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="44499-672">我們已修正部分動畫無法開始的問題</span><span class="sxs-lookup"><span data-stu-id="44499-672">We fixed an issue which could prevent some animations from starting</span></span>

- <span data-ttu-id="44499-673">我們已修正將投影片從一個簡報複製到另一個簡報時可能會造成建立重複母片的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-673">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span><br>

- <span data-ttu-id="44499-674">改善複製貼上的案例：將 PowerPoint 投影片中的圖形複製並重複貼到其他投影片中，可能會出現例外狀況而失敗。</span><span class="sxs-lookup"><span data-stu-id="44499-674">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>

- <span data-ttu-id="44499-675">修正螢光筆的問題：具有深色螢光筆色彩的白色文字，在灰階中會以黑色列印。</span><span class="sxs-lookup"><span data-stu-id="44499-675">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

- <span data-ttu-id="44499-676">如果在不支援的版本中開啟含有新的新式註解的檔案，將會顯示黃色警告。</span><span class="sxs-lookup"><span data-stu-id="44499-676">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

- <span data-ttu-id="44499-677">修正會導致共同作業使用者之間效能較低的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-677">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="44499-678">可靠性修正：修正第三方增益集可能會造成 PowerPoint 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-678">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="44499-679">修正以漸進式開啟檔案時，其包含的投影片若具有多個內嵌媒體串流，可能會發生的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-679">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="44499-680">我們已修正 Shape.Paste 方法的問題：當使用者使用 Shape.Paste 方法複製並貼上圖形時，它會將選取範圍變更為貼上的圖形。</span><span class="sxs-lookup"><span data-stu-id="44499-680">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="44499-681">我們已修正首次啟動 PowerPoint 時，未受信任的增益集可能不會顯示安全性警告訊息列的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-681">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

- <span data-ttu-id="44499-682">修正某些增益集會對圖表的圖形擲出未預期錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-682">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="44499-683">避免 PowerPoint 使用者嘗試進行「線上展示」時遇到錯誤。</span><span class="sxs-lookup"><span data-stu-id="44499-683">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

### <a name="project"></a><span data-ttu-id="44499-684">Project</span><span class="sxs-lookup"><span data-stu-id="44499-684">Project</span></span>

- <span data-ttu-id="44499-685">修正讓 Windows 7 上的使用者能夠從 Project Web App 和 SharePoint 網站開啟專案的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-685">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="44499-686">發現在開啟唯讀專案時，使用者可能會收到數個訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-686">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="44499-687">「全部撫平」命令無法正確解決資源過度分派的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-687">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="44499-688">當您有作業中有零個工作的指派時，可能無法將作業標示為完成且永遠會顯示為 99%。</span><span class="sxs-lookup"><span data-stu-id="44499-688">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

- <span data-ttu-id="44499-689">修正以下問題：由於基準行事曆變更時未更新資源行事曆，而導致時程表和專案計劃之間的實際工作可能不同。</span><span class="sxs-lookup"><span data-stu-id="44499-689">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="skype"></a><span data-ttu-id="44499-690">Skype</span><span class="sxs-lookup"><span data-stu-id="44499-690">Skype</span></span>

- <span data-ttu-id="44499-691">修正有多個交談正在進行時的索引標籤式交談標題名稱。</span><span class="sxs-lookup"><span data-stu-id="44499-691">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="visio"></a><span data-ttu-id="44499-692">Visio</span><span class="sxs-lookup"><span data-stu-id="44499-692">Visio</span></span>

- <span data-ttu-id="44499-693">無法從 Visio 將多個圖形匯出為 SVG。</span><span class="sxs-lookup"><span data-stu-id="44499-693">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="44499-694">Word</span><span class="sxs-lookup"><span data-stu-id="44499-694">Word</span></span>

- <span data-ttu-id="44499-695">來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。</span><span class="sxs-lookup"><span data-stu-id="44499-695">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="44499-696">我們已修正列印到 Deskjet 印表機時，可能會導致縮放問題的問題</span><span class="sxs-lookup"><span data-stu-id="44499-696">We fixed an issue which could have caused scaling issues when printing to Deskjet printers</span></span>

- <span data-ttu-id="44499-697">我們已修正表格中「最適文字大小」的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-697">We fixed an issue in Fit Text in Table.</span></span>

- <span data-ttu-id="44499-698">我們已修正追蹤修訂有時候會進入無限迴圈的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-698">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="44499-699">我們已修正在某些情況下，儲存現有檔案永遠會導致出現 [另存新檔] 對話方塊且檔案永遠不會儲存的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-699">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="44499-700">我們已修正將兩份文件合併成一份文件時的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-700">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="44499-701">修正受保護無法編輯之文件的比較功能問題。</span><span class="sxs-lookup"><span data-stu-id="44499-701">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="44499-702">修正應用程式可能在關機時懸置的各種問題。</span><span class="sxs-lookup"><span data-stu-id="44499-702">Fixes various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="44499-703">同時修正特定相關增益集當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-703">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="44499-704">Office 套件</span><span class="sxs-lookup"><span data-stu-id="44499-704">Office Suite</span></span>

- <span data-ttu-id="44499-705">修正不正確地將平假名和漢字中的日本新年號 "Reiwa" (令和) 識別為拼字錯誤或不合文法的運算式的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-705">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="44499-706">修正嘗試共用儲存在 SharePoint 2016 上的檔案時，導致使用者遇到「很抱歉，發生問題，無法共用」訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-706">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="44499-707">修正在 PowerPoint 共同撰寫和離線編輯的工作階段中可能會導致資料遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-707">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="44499-708">修正使用者在開啟檔案時可能會遇到的當機問題。</span><span class="sxs-lookup"><span data-stu-id="44499-708">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="44499-709">在某些情況下，同步處理引擎備份的 SharePoint 檔案可能會顯示「已儲存」但實際上未儲存任何變更，導致資料遺失。</span><span class="sxs-lookup"><span data-stu-id="44499-709">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="44499-710">解決使用者可能無法儲存 Word、Excel 和 PowerPoint 文件的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-710">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="44499-711">此問題會影響建立新檔案並在按一下 [儲存] 圖示或按 Ctrl + S 之後帶出 [另存成模型對話方塊] 選項的使用者。</span><span class="sxs-lookup"><span data-stu-id="44499-711">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="44499-712">從已過時的 API 中移除 Word，以修正其當機問題。</span><span class="sxs-lookup"><span data-stu-id="44499-712">Fixes a crash in Word by moving away from a deprecated API.</span></span>

- <span data-ttu-id="44499-713">修正 PowerPoint 中半形片假名字元在垂直文字方塊中無法正確旋轉的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-713">Fixing an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

- <span data-ttu-id="44499-714">修正 Win7 的效能問題，其中，於所有應用程式中從功能區插入圖案庫時，大約需要 4 秒鐘的時間才會顯示。</span><span class="sxs-lookup"><span data-stu-id="44499-714">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="44499-715">修正 Backstage 的 [資訊位置] 平板未顯示協助工具資訊的錯誤。</span><span class="sxs-lookup"><span data-stu-id="44499-715">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="44499-716">改善有關登錄完整性的 Office 更新程序的可靠性。</span><span class="sxs-lookup"><span data-stu-id="44499-716">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="44499-717">我們已將 2019 年 1 月和 7 月分支的通道名稱更新為新通道名稱。</span><span class="sxs-lookup"><span data-stu-id="44499-717">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>

- <span data-ttu-id="44499-718">更正可能會在計量網路上非預期封鎖更新的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-718">Corrects an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="44499-719">修正相對期限只有在第一次設定時才會有效的 ODT 和 GPO 更新期限設定中的錯誤 (bug)。此修正可啟用後續更新的相關期限。</span><span class="sxs-lookup"><span data-stu-id="44499-719">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="44499-720">某些情況下，Office 快速鍵可能會在更新後消失。</span><span class="sxs-lookup"><span data-stu-id="44499-720">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="44499-721">此更新可改善發佈 Office 快速鍵時的可靠性。</span><span class="sxs-lookup"><span data-stu-id="44499-721">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="44499-722">解決 Office 更新可能會非預期地從 Office CDN 而不是預期使用的來源 (例如本機或網路共用或 Configuration Manager 提供的位置) 下載檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-722">Resolves an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="44499-723">解決在某些情況下，若使用者不是系統管理員且系統帳戶沒有網路連線時，將無法套用更新的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-723">Resolves an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="44499-724">修正 Office 更新訊息不以預期語言顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-724">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="44499-725">自此以後，Office 更新訊息會正確符合 Windows 顯示語言。</span><span class="sxs-lookup"><span data-stu-id="44499-725">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="44499-726">下載 Office 更新時透過繼續之前可能已中斷的下載，藉此改善可靠性。</span><span class="sxs-lookup"><span data-stu-id="44499-726">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="44499-727">解決第三方外掛程式中與文字方塊/圖案自動調整屬性相關的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-727">Address issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="44499-728">此變更可解決開啟損毀的檔案之後，正確呈現影像的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-728">This change addresses correctly rendering images after opening a corrupted file.</span></span>

- <span data-ttu-id="44499-729">此變更可解決轉譯某些含有標記的散佈圖緩慢的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-729">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="44499-730">我們已修正大型樹狀檢視可能會導致當機的問題</span><span class="sxs-lookup"><span data-stu-id="44499-730">We fixed an issue where large tree views could result in a crash</span></span>

- <span data-ttu-id="44499-731">此更新修正了 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。</span><span class="sxs-lookup"><span data-stu-id="44499-731">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="44499-732">為了保護 Office 客戶的安全性，我們現在專門使用 SHA-2 演算法來簽署 Microsoft Office 更新。</span><span class="sxs-lookup"><span data-stu-id="44499-732">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

- <span data-ttu-id="44499-733">為了保護 Office 客戶的安全性，我們現在專門使用 SHA-2 演算法來簽署 Microsoft Office 更新。</span><span class="sxs-lookup"><span data-stu-id="44499-733">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-july-14"></a><span data-ttu-id="44499-735">版本 1902：7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="44499-735">Version 1902: July 14</span></span>
<span data-ttu-id="44499-736">*版本 1902 (組建 11328.20624)*</span><span class="sxs-lookup"><span data-stu-id="44499-736">*Version 1902 (Build 11328.20624)*</span></span>

<span data-ttu-id="44499-737">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-737">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

## <a name="version-1908-june-09"></a><span data-ttu-id="44499-738">版本 1908: 6 月 09日</span><span class="sxs-lookup"><span data-stu-id="44499-738">Version 1908: June 09</span></span>
<span data-ttu-id="44499-739">*版本1908（組建11929.20838）*</span><span class="sxs-lookup"><span data-stu-id="44499-739">*Version 1908 (Build 11929.20838)*</span></span>

<span data-ttu-id="44499-740">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-740">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="44499-742">解決的問題</span><span class="sxs-lookup"><span data-stu-id="44499-742">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="44499-743">Excel</span><span class="sxs-lookup"><span data-stu-id="44499-743">Excel</span></span>

- <span data-ttu-id="44499-744">修正當 Excel 視窗透過 Teams 共用時，使用 Ctrl + Shift + 方向鍵滑動後，Excel 可能會無法回應的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-744">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="44499-745">修正列印時表單控制項的核取方塊縮放的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-745">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="44499-746">當您使用舊版的「共用活頁簿」模式，嘗試為活頁簿的新工作表列出變更時，就會發生當機。</span><span class="sxs-lookup"><span data-stu-id="44499-746">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="44499-747">Outlook</span><span class="sxs-lookup"><span data-stu-id="44499-747">Outlook</span></span>

- <span data-ttu-id="44499-748">已解決會導致使用者在轉寄大型 HTML 郵件時，看到郵件內文截斷的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-748">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

### <a name="office-suite"></a><span data-ttu-id="44499-749">Office 套件</span><span class="sxs-lookup"><span data-stu-id="44499-749">Office Suite</span></span>

- <span data-ttu-id="44499-750">我們已將 2019 年 1月和7月叉的通道名稱更新為新的通道名稱。</span><span class="sxs-lookup"><span data-stu-id="44499-750">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-june-09"></a><span data-ttu-id="44499-752">版本 1902: 6 月 09日</span><span class="sxs-lookup"><span data-stu-id="44499-752">Version 1902: June 09</span></span>
<span data-ttu-id="44499-753">*版本 1902 (組建 11328.20602)*</span><span class="sxs-lookup"><span data-stu-id="44499-753">*Version 1902 (Build 11328.20602)*</span></span>

<span data-ttu-id="44499-754">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-754">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="44499-756">解決的問題</span><span class="sxs-lookup"><span data-stu-id="44499-756">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="44499-757">Office 套件</span><span class="sxs-lookup"><span data-stu-id="44499-757">Office Suite</span></span>

- <span data-ttu-id="44499-758">我們已將 2019 年 1月和7月叉的通道名稱更新為新的通道名稱。</span><span class="sxs-lookup"><span data-stu-id="44499-758">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>

- <span data-ttu-id="44499-759">我們從中斷 C2R 組建的基線檔案中移除過時的參照。</span><span class="sxs-lookup"><span data-stu-id="44499-759">We removed obsolete references from the baseline files that were breaking the C2R Build.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-may-12"></a><span data-ttu-id="44499-761">版本 1908：5 月 12 日</span><span class="sxs-lookup"><span data-stu-id="44499-761">Version 1908: May 12</span></span>
<span data-ttu-id="44499-762">*版本 1908 (組建 11929.20776)*</span><span class="sxs-lookup"><span data-stu-id="44499-762">*Version 1908 (Build 11929.20776)*</span></span>

<span data-ttu-id="44499-763">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-763">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="44499-765">解決的問題</span><span class="sxs-lookup"><span data-stu-id="44499-765">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="44499-766">Excel</span><span class="sxs-lookup"><span data-stu-id="44499-766">Excel</span></span>

- <span data-ttu-id="44499-767">當您將有色彩篩選的資料複製到不同寬度的欄時，不會貼上值。</span><span class="sxs-lookup"><span data-stu-id="44499-767">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

### <a name="outlook"></a><span data-ttu-id="44499-768">Outlook</span><span class="sxs-lookup"><span data-stu-id="44499-768">Outlook</span></span>

- <span data-ttu-id="44499-769">解決以下問題：使用者在套用最新的 Windows 更新之後，開啟 .msg 和 .oft 檔案發生當機。</span><span class="sxs-lookup"><span data-stu-id="44499-769">Addressed an issue that caused users to experience a crash when opening msg and .oft files after applying a recent Windows update.</span></span>

### <a name="word"></a><span data-ttu-id="44499-770">Word</span><span class="sxs-lookup"><span data-stu-id="44499-770">Word</span></span>

- <span data-ttu-id="44499-771">我們已修正將兩份文件合併成一份文件時的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-771">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="44499-772">修正受保護無法編輯之文件的比較功能問題。</span><span class="sxs-lookup"><span data-stu-id="44499-772">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-may-12"></a><span data-ttu-id="44499-774">版本 1902：5 月 12 日</span><span class="sxs-lookup"><span data-stu-id="44499-774">Version 1902: May 12</span></span>
<span data-ttu-id="44499-775">*版本 1902 (組建 11328.20586)*</span><span class="sxs-lookup"><span data-stu-id="44499-775">*Version 1902 (Build 11328.20586)*</span></span>

<span data-ttu-id="44499-776">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-776">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="44499-778">解決的問題</span><span class="sxs-lookup"><span data-stu-id="44499-778">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="44499-779">Outlook</span><span class="sxs-lookup"><span data-stu-id="44499-779">Outlook</span></span>

- <span data-ttu-id="44499-780">解決以下問題：使用者在套用最新的 Windows 更新之後，開啟 .msg 和 .oft 檔案發生當機。</span><span class="sxs-lookup"><span data-stu-id="44499-780">Addressed an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="44499-781">根據預設，保留原則標籤會將保留時間顯示於括弧中。</span><span class="sxs-lookup"><span data-stu-id="44499-781">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="44499-782">此修正提供登錄機碼，讓系統管理員能夠指定只應顯示的原則名稱。</span><span class="sxs-lookup"><span data-stu-id="44499-782">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="44499-783">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration。</span><span class="sxs-lookup"><span data-stu-id="44499-783">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="44499-784">0 = 預設值。</span><span class="sxs-lookup"><span data-stu-id="44499-784">0 = Default.</span></span>  <span data-ttu-id="44499-785">1 = 我們只會顯示保留原則文字的原則名稱。</span><span class="sxs-lookup"><span data-stu-id="44499-785">1 = we will only show the PolicyName for Retention policy text.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-may-04"></a><span data-ttu-id="44499-787">版本 1908：5 月 4 日</span><span class="sxs-lookup"><span data-stu-id="44499-787">Version 1908: May 04</span></span>
<span data-ttu-id="44499-788">*版本 1908 (組建 11929.20752)*</span><span class="sxs-lookup"><span data-stu-id="44499-788">*Version 1908 (Build 11929.20752)*</span></span>

<span data-ttu-id="44499-789">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-789">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="44499-790">解決的問題</span><span class="sxs-lookup"><span data-stu-id="44499-790">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="44499-791">Outlook</span><span class="sxs-lookup"><span data-stu-id="44499-791">Outlook</span></span>

- <span data-ttu-id="44499-792">已解決導致使用者在選取特定搜尋結果時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-792">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="44499-793">已解決導致 [附件工具] 中的 [儲存至雲端] 按鈕遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-793">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="44499-794">根據預設，保留原則標籤會將保留時間顯示於括弧中。</span><span class="sxs-lookup"><span data-stu-id="44499-794">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="44499-795">此修正提供登錄機碼，讓系統管理員能夠指定只應顯示的原則名稱。</span><span class="sxs-lookup"><span data-stu-id="44499-795">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="44499-796">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration。</span><span class="sxs-lookup"><span data-stu-id="44499-796">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="44499-797">0 = 預設 1 = 我們只會顯示保留原則文字的原則名稱。</span><span class="sxs-lookup"><span data-stu-id="44499-797">0 = Default 1 = we will only show the PolicyName for Retention policy text.</span></span>

### <a name="office-suite"></a><span data-ttu-id="44499-798">Office 套件</span><span class="sxs-lookup"><span data-stu-id="44499-798">Office Suite</span></span>

- <span data-ttu-id="44499-799">修正 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。</span><span class="sxs-lookup"><span data-stu-id="44499-799">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1902-may-04"></a><span data-ttu-id="44499-800">版本 1902：5 月 4 日</span><span class="sxs-lookup"><span data-stu-id="44499-800">Version 1902: May 04</span></span>
<span data-ttu-id="44499-801">*版本 1902 (組建 11328.20572)*</span><span class="sxs-lookup"><span data-stu-id="44499-801">*Version 1902 (Build 11328.20572)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="44499-802">解決的問題</span><span class="sxs-lookup"><span data-stu-id="44499-802">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="44499-803">Office 套件</span><span class="sxs-lookup"><span data-stu-id="44499-803">Office Suite</span></span>

- <span data-ttu-id="44499-804">修正 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。</span><span class="sxs-lookup"><span data-stu-id="44499-804">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1908-april-26"></a><span data-ttu-id="44499-805">版本 1908：4 月 26 日</span><span class="sxs-lookup"><span data-stu-id="44499-805">Version 1908: April 26</span></span>
<span data-ttu-id="44499-806">*版本 1908 (組建 11929.20736)*</span><span class="sxs-lookup"><span data-stu-id="44499-806">*Version 1908 (Build 11929.20736)*</span></span>

<span data-ttu-id="44499-807">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-807">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="44499-808">解決的問題</span><span class="sxs-lookup"><span data-stu-id="44499-808">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="44499-809">Excel</span><span class="sxs-lookup"><span data-stu-id="44499-809">Excel</span></span>

- <span data-ttu-id="44499-810">已修正使用者在使用 VBA 巨集清除範圍內容時可能遇到的效能問題。</span><span class="sxs-lookup"><span data-stu-id="44499-810">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="44499-811">修正 VBA 將值寫入範圍時，速度比預期慢的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-811">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="44499-812">已解決在儲存並重新開啟檔案時，圖表軸上的 "Value Crosses At" 屬性發生意外變更的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-812">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="44499-813">在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。</span><span class="sxs-lookup"><span data-stu-id="44499-813">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>


### <a name="onenote"></a><span data-ttu-id="44499-814">OneNote</span><span class="sxs-lookup"><span data-stu-id="44499-814">OneNote</span></span>

- <span data-ttu-id="44499-815">對通知進行本地化，讓使用者可以了解更多 OneNote 使用者體驗中正在採取的臨時措施的資訊，以改善同步處理和服務穩定性。</span><span class="sxs-lookup"><span data-stu-id="44499-815">Localizes the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>


## <a name="version-1908-april-14"></a><span data-ttu-id="44499-816">版本 1908：4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="44499-816">Version 1908: April 14</span></span>
<span data-ttu-id="44499-817">*版本 1908 (組建 11929.20708)*</span><span class="sxs-lookup"><span data-stu-id="44499-817">*Version 1908 (Build 11929.20708)*</span></span>

<span data-ttu-id="44499-818">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-818">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="44499-820">解決的問題</span><span class="sxs-lookup"><span data-stu-id="44499-820">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="44499-821">Excel</span><span class="sxs-lookup"><span data-stu-id="44499-821">Excel</span></span>

- <span data-ttu-id="44499-822">修正在刪除包含合併儲存格的資料行時，會導致效能變慢的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-822">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="44499-823">修正在 [預覽列印] 中顯示表單控制項時的文字縮放比例問題。</span><span class="sxs-lookup"><span data-stu-id="44499-823">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

### <a name="skype"></a><span data-ttu-id="44499-824">Skype</span><span class="sxs-lookup"><span data-stu-id="44499-824">Skype</span></span>

- <span data-ttu-id="44499-825">修正有多個交談正在進行時的索引標籤式交談標題名稱。</span><span class="sxs-lookup"><span data-stu-id="44499-825">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="outlook"></a><span data-ttu-id="44499-826">Outlook</span><span class="sxs-lookup"><span data-stu-id="44499-826">Outlook</span></span>

- <span data-ttu-id="44499-827">已解決會導致使用者在關閉 Outlook 時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-827">Addressed an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="44499-828">已解決會導致客戶在某些情況下看到空白會議室清單的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-828">Addressed an issue that caused customers to see an empty room list in some scenarios.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="44499-829">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="44499-829">PowerPoint</span></span>

- <span data-ttu-id="44499-830">修正具有深色螢光筆色彩的白色文字，在灰階中會以黑色列印的螢光筆問題。</span><span class="sxs-lookup"><span data-stu-id="44499-830">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="44499-831">Word</span><span class="sxs-lookup"><span data-stu-id="44499-831">Word</span></span>

- <span data-ttu-id="44499-832">修正「文字配合資料表」中的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-832">Fixed an issue in Fit Text in Table.</span></span>


## <a name="version-1902-april-14"></a><span data-ttu-id="44499-833">版本 1902：4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="44499-833">Version 1902: April 14</span></span>
<span data-ttu-id="44499-834">*版本 1902 (組建 11328.20564)*</span><span class="sxs-lookup"><span data-stu-id="44499-834">*Version 1902 (Build 11328.20564)*</span></span>

<span data-ttu-id="44499-835">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-835">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-march-10"></a><span data-ttu-id="44499-837">版本 1908：3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="44499-837">Version 1908: March 10</span></span>
<span data-ttu-id="44499-838">*版本 1908 (組建 11929.20648)*</span><span class="sxs-lookup"><span data-stu-id="44499-838">*Version 1908 (Build 11929.20648)*</span></span>

<span data-ttu-id="44499-839">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-839">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="44499-841">解決的問題</span><span class="sxs-lookup"><span data-stu-id="44499-841">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="44499-842">Excel</span><span class="sxs-lookup"><span data-stu-id="44499-842">Excel</span></span>

- <span data-ttu-id="44499-843">修正當活頁簿中有外部連結時，有些使用者可能會遇到多個彈出式視窗的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-843">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>


- <span data-ttu-id="44499-844">[資料剖析] 功能對某些地區設定可能會失敗。</span><span class="sxs-lookup"><span data-stu-id="44499-844">Text to Column functionality may fail for some locales.</span></span>


- <span data-ttu-id="44499-845">使用者在存取隱藏的命名範圍時可能會發生錯誤。</span><span class="sxs-lookup"><span data-stu-id="44499-845">Users may encounter an error when accessing a hidden named range.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="44499-846">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="44499-846">PowerPoint</span></span>

- <span data-ttu-id="44499-847">我們已修正 Shape.Paste 方法的問題：當使用者使用 Shape.Paste 方法複製並貼上圖形時，它會將選取範圍變更為貼上的圖形。</span><span class="sxs-lookup"><span data-stu-id="44499-847">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>


### <a name="word"></a><span data-ttu-id="44499-848">Word</span><span class="sxs-lookup"><span data-stu-id="44499-848">Word</span></span>

- <span data-ttu-id="44499-849">我們已修正在某些情況下，儲存現有檔案永遠會導致出現 [另存新檔] 對話方塊且檔案永遠不會儲存的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-849">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>


### <a name="office-suite"></a><span data-ttu-id="44499-850">Office 套件</span><span class="sxs-lookup"><span data-stu-id="44499-850">Office Suite</span></span>

- <span data-ttu-id="44499-851">此變更可解決轉譯某些含有資料標記的散佈圖緩慢的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-851">This change addresses slow rendering of some scatter charts with markers.</span></span>

## <a name="version-1902-march-10"></a><span data-ttu-id="44499-852">版本 1902：3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="44499-852">Version 1902: March 10</span></span>
<span data-ttu-id="44499-853">*版本 1902 (組建 11328.20554)*</span><span class="sxs-lookup"><span data-stu-id="44499-853">*Version 1902 (Build 11328.20554)*</span></span>

<span data-ttu-id="44499-854">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-854">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-february-11"></a><span data-ttu-id="44499-856">版本 1908：2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="44499-856">Version 1908: February 11</span></span>
<span data-ttu-id="44499-857">*版本 1908 (組建 11929.20606)*</span><span class="sxs-lookup"><span data-stu-id="44499-857">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="44499-858">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-858">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="44499-860">解決的問題</span><span class="sxs-lookup"><span data-stu-id="44499-860">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="44499-861">Excel</span><span class="sxs-lookup"><span data-stu-id="44499-861">Excel</span></span>

- <span data-ttu-id="44499-862">此更新已修正使用 VBA 將影像新增到圖表的頁首/頁尾時發生錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-862">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="44499-863">修正在預覽列印或列印時群組方塊控制項的框線無法顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-863">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="44499-864">使用者在使用某些非英文字元集的情況下，儲存變更時可能會遇到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-864">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="44499-865">修正圖表標題中影像檔案大小在儲存包含圖表的活頁簿時增加的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-865">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="44499-866">修正以下問題：將選取範圍與交互參照的活頁簿保持同步時，導致交互參照的活頁簿中的 DBCS 字元損毀。</span><span class="sxs-lookup"><span data-stu-id="44499-866">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="44499-867">已解決使用自動調整來調整列高時，核取方塊可能收縮的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-867">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="44499-868">Outlook</span><span class="sxs-lookup"><span data-stu-id="44499-868">Outlook</span></span>

- <span data-ttu-id="44499-869">已解決導致使用者在指定無效寄件者地址時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-869">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="44499-870">已解決導致使用者處理衝突郵件時同步失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-870">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="44499-871">已解決導致使用者在啟動 Outlook 時，「正在載入設定檔」畫面時停滯的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-871">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="44499-872">已解決導致使用者在變更檢視時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-872">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="44499-873">已解決在 Citrix 環境中檢視 30 個以上的行事曆時，導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-873">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="44499-874">[此處](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)是記錄舊版問題的個別 KB。</span><span class="sxs-lookup"><span data-stu-id="44499-874">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="44499-875">已解決以下問題：使用者將共用行事曆資料夾同步到 OST 時發生問題，這導致嘗試與這些資料夾互動時發生權限錯誤。</span><span class="sxs-lookup"><span data-stu-id="44499-875">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="44499-876">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="44499-876">PowerPoint</span></span>

- <span data-ttu-id="44499-877">已改善複製貼上的案例，即將 PowerPoint 投影片中的圖形複製並貼到其他投影片可能會因為異常而失敗。</span><span class="sxs-lookup"><span data-stu-id="44499-877">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="44499-878">修正導致共同作業使用者之間效能較低的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-878">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="44499-879">修正以下問題：當檔案以漸進式開啟時，若其中一個投影片包含多個內嵌媒體串流可能會發生問題。</span><span class="sxs-lookup"><span data-stu-id="44499-879">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="44499-880">修正以下問題：首次啟動 PowerPoint 時，不受信任的增益集可能不會顯示安全性警告訊息列。</span><span class="sxs-lookup"><span data-stu-id="44499-880">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="44499-881">Project</span><span class="sxs-lookup"><span data-stu-id="44499-881">Project</span></span>

- <span data-ttu-id="44499-882">修正以下問題：由於基準行事曆變更時未更新資源行事曆，而導致時程表和專案計劃之間的實際工作可能不同。</span><span class="sxs-lookup"><span data-stu-id="44499-882">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="44499-883">Word</span><span class="sxs-lookup"><span data-stu-id="44499-883">Word</span></span>

- <span data-ttu-id="44499-884">已從遭取代的 API 移除，以修正 Word 的當機問題。</span><span class="sxs-lookup"><span data-stu-id="44499-884">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="44499-885">Office 套件</span><span class="sxs-lookup"><span data-stu-id="44499-885">Office Suite</span></span>

- <span data-ttu-id="44499-886">此變更解決開啟損毀的檔案時正確呈現影像的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-886">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-february-11"></a><span data-ttu-id="44499-888">版本 1902：2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="44499-888">Version 1902: February 11</span></span>
<span data-ttu-id="44499-889">*版本 1902 (組建 11328.20526)*</span><span class="sxs-lookup"><span data-stu-id="44499-889">*Version 1902 (Build 11328.20526)*</span></span>

<span data-ttu-id="44499-890">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-890">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="44499-892">解決的問題</span><span class="sxs-lookup"><span data-stu-id="44499-892">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="44499-893">Outlook</span><span class="sxs-lookup"><span data-stu-id="44499-893">Outlook</span></span>

- <span data-ttu-id="44499-894">解決導致使用者在傳送加密電子郵件時遇到「不支援加密演算法」錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-894">Addresses an issue that caused users to encounter encryption algorithm is not supported errors when sending an encrypted email.</span></span>


### <a name="word"></a><span data-ttu-id="44499-895">Word</span><span class="sxs-lookup"><span data-stu-id="44499-895">Word</span></span>

- <span data-ttu-id="44499-896">已從遭取代的 API 移除，以修正 Word 的當機問題。</span><span class="sxs-lookup"><span data-stu-id="44499-896">Fixed a crash in Word by moving away from a deprecated API.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

## <a name="version-1808-february-11"></a><span data-ttu-id="44499-899">版本 1808：2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="44499-899">Version 1808: February 11</span></span>
<span data-ttu-id="44499-900">*版本 1808 (組建 10730.20438)*</span><span class="sxs-lookup"><span data-stu-id="44499-900">*Version 1808 (Build 10730.20438)*</span></span>

<span data-ttu-id="44499-901">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-901">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-january-14"></a><span data-ttu-id="44499-903">版本 1908：1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="44499-903">Version 1908: January 14</span></span>
<span data-ttu-id="44499-904">*版本 1908 (組建 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="44499-904">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="44499-905">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-905">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="44499-907">功能更新</span><span class="sxs-lookup"><span data-stu-id="44499-907">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="44499-908">Access</span><span class="sxs-lookup"><span data-stu-id="44499-908">Access</span></span>

- <span data-ttu-id="44499-909">**將索引標籤保留在資料庫物件上：** 能清楚看到使用中的索引標籤、輕鬆拖曳索引標籤來重新排列，只要按一下就能關閉資料庫物件。</span><span class="sxs-lookup"><span data-stu-id="44499-909">**Keep tabs on your database objects:** Clearly see the active tab, easily drag tabs to rearrange them, and close database objects with just one click.</span></span>

- <span data-ttu-id="44499-910">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="44499-910">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="44499-911">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="44499-911">Switching between them has never been easier.</span></span> [<span data-ttu-id="44499-912">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-912">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="44499-913">**使用更大的空間來縮放：** 加大 [縮放] 方塊、變更字型、記憶縮放。</span><span class="sxs-lookup"><span data-stu-id="44499-913">**Zoom with more room:** Make the Zoom box bigger, change the font, and Zoom remembers it all.</span></span> [<span data-ttu-id="44499-914">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-914">Learn more</span></span>](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

### <a name="excel"></a><span data-ttu-id="44499-915">Excel</span><span class="sxs-lookup"><span data-stu-id="44499-915">Excel</span></span>

- <span data-ttu-id="44499-916">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="44499-916">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="44499-917">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="44499-917">Switching between them has never been easier.</span></span> [<span data-ttu-id="44499-918">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-918">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="44499-919">**增加您內容的覆蓋面：** 想要讓您的簡報更易於使用嗎？</span><span class="sxs-lookup"><span data-stu-id="44499-919">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="44499-920">讓協助工具檢查程式來幫助您，您不需要自行處理。</span><span class="sxs-lookup"><span data-stu-id="44499-920">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="44499-921">按一下 [校閱] > [檢查協助工具] 試試看這個功能 – 我們會在狀態列上告訴您需要留意的部分。</span><span class="sxs-lookup"><span data-stu-id="44499-921">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="44499-922">**快速找到該檔案：** 想要尋找最近使用過的檔案嗎？</span><span class="sxs-lookup"><span data-stu-id="44499-922">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="44499-923">只要在 [檔案] > [常用] 頁面的 [搜尋] 方塊中輸入，就能找到所需的檔案。</span><span class="sxs-lookup"><span data-stu-id="44499-923">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="44499-924">**觀看工作表生動地呈現：** 插入動畫 3D 圖形，來查看心跳、行星軌道，以及暴龍在工作表內橫衝直撞。</span><span class="sxs-lookup"><span data-stu-id="44499-924">**Watch your worksheet come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage through the workbook.</span></span> [<span data-ttu-id="44499-925">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-925">Learn more</span></span>](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- <span data-ttu-id="44499-p175">**更深入地探索您的資料：** 新的 [構想] 按鈕可尋找資料的模式，並使用模式建立更有智慧且個人化的建議。[深入了解](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span><span class="sxs-lookup"><span data-stu-id="44499-p175">**Discover more about your data:** The new Ideas button looks for patterns in your data, and uses them to create intelligent, personalized suggestions. [Learn more](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span></span>

- <span data-ttu-id="44499-928">**共同作業變得更容易：** 共同撰寫的增強功能代表的是使用條件式格式設定、儲存格樣式等等時，您的變更會與共同作業者的變更順暢地合併。</span><span class="sxs-lookup"><span data-stu-id="44499-928">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>

- <span data-ttu-id="44499-929">**聯結類似欄位上的表格：** 在比較合併表格的欄位時，取得及轉換 (Power Query) 現在具有近似文字比對邏輯 (也稱為模糊比對)。</span><span class="sxs-lookup"><span data-stu-id="44499-929">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span> [<span data-ttu-id="44499-930">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-930">Learn more</span></span>](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- <span data-ttu-id="44499-931">**使用 Power Query 的增強功能快速撰寫程式碼：** 使用自動完成和語法色彩快速完成程式碼。</span><span class="sxs-lookup"><span data-stu-id="44499-931">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="44499-932">同時輕鬆探索函數、資料行和參數。</span><span class="sxs-lookup"><span data-stu-id="44499-932">Easily discover functions, columns, and parameters, too.</span></span>

- <span data-ttu-id="44499-933">**搜尋並享受：** 我們新增了 [搜尋以插入] 圖示，讓您輕鬆找到您要的圖示。</span><span class="sxs-lookup"><span data-stu-id="44499-933">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="44499-934">而當您選取時，[插入] 按鈕會告知您已經選取的數量。</span><span class="sxs-lookup"><span data-stu-id="44499-934">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="44499-935">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-935">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook"></a><span data-ttu-id="44499-936">Outlook</span><span class="sxs-lookup"><span data-stu-id="44499-936">Outlook</span></span>

- <span data-ttu-id="44499-937">**我們已為您更新 Outlook 使用者體驗：** 先前利用「即將推出」提供預覽的簡化體驗，專門設計來幫助您專注於最重要的事物上。</span><span class="sxs-lookup"><span data-stu-id="44499-937">**We’ve updated the Outlook user experience for you:** A simplified experience, previously available for preview with Coming Soon, designed to help you focus on what matters most.</span></span> [<span data-ttu-id="44499-938">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-938">Learn more</span></span>](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- <span data-ttu-id="44499-939">**簡化且也能自訂的功能區：** 輕鬆使用簡化、以單一列方式陳列的常用按鈕。</span><span class="sxs-lookup"><span data-stu-id="44499-939">**A simplified ribbon that's customizable, too:** Enjoy a streamlined, single row of the most frequently used buttons.</span></span> <span data-ttu-id="44499-940">輕鬆在傳統與 [簡化] 檢視之間切換，以及釘選/取消釘選命令。</span><span class="sxs-lookup"><span data-stu-id="44499-940">Easily switch between classic and Simplified views, and pin/unpin commands.</span></span> [<span data-ttu-id="44499-941">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-941">Learn more</span></span>](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- <span data-ttu-id="44499-942">**在移動郵件時繼續作業：** Outlook 現在會在背景中移動郵件，因此，在資料夾之間移動大量郵件時您可以繼續作業。</span><span class="sxs-lookup"><span data-stu-id="44499-942">**Keep working while moving messages:** Outlook now moves messages in the background, so you can keep working while moving lots of messages between folders.</span></span>

- <span data-ttu-id="44499-943">**在連續會議之間置入時間：** 將會議預設為提早 5-10 分鐘結束，讓出席者有時間休息，或在前往下一個地點。</span><span class="sxs-lookup"><span data-stu-id="44499-943">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to end 5-10 minutes early by default.</span></span>

- <span data-ttu-id="44499-944">**挑選您的最愛動作：** 不使用 [標幟] 和 [刪除] 嗎？</span><span class="sxs-lookup"><span data-stu-id="44499-944">**Pick your favorite action:** Don't use Flag and Delete?</span></span> <span data-ttu-id="44499-945">那麼 [封存] 或 [標示為已讀取] 呢？</span><span class="sxs-lookup"><span data-stu-id="44499-945">How about Archive or Mark as Read?</span></span> <span data-ttu-id="44499-946">自訂快速動作功能表，加上您最常使用的命令。</span><span class="sxs-lookup"><span data-stu-id="44499-946">Customize the quick action menu with the commands you use most.</span></span>

- <span data-ttu-id="44499-p182">**他們會看到您的 meme：** 如果使用文字或靜態影像還不足以清楚表達您的想法，您可以使用動畫 GIF。[深入了解](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span><span class="sxs-lookup"><span data-stu-id="44499-p182">**They'll see what you meme:** When text or static images just won't do, use an animated GIF to make your point. [Learn more](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span></span>

- <span data-ttu-id="44499-949">**更快速新增帳戶的方式：** 由於帳戶設定已改善，您現在可以更輕鬆地將使用雙因素驗證的 Outlook.com 和 Gmail 帳戶新增到 Outlook。</span><span class="sxs-lookup"><span data-stu-id="44499-949">**A quicker way to add accounts:** Thanks to account setup improvements, it's easier than ever to add Outlook.com and Gmail accounts that use 2-factor authentication to Outlook.</span></span> [<span data-ttu-id="44499-950">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-950">Learn more</span></span>](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- <span data-ttu-id="44499-951">**不再受限於同步處理限制：** Outlook 的增強功能指出資料夾限制已不存在，因此您可以開始將您的共用信箱同步處理。</span><span class="sxs-lookup"><span data-stu-id="44499-951">**Say goodbye to sync limits:** Outlook improvements mean the folder limit is gone so go ahead and synchronize your shared mailboxes.</span></span>

- <span data-ttu-id="44499-952">**搜尋並享受：** 我們新增了 [搜尋以插入] 圖示，讓您輕鬆找到您要的圖示。</span><span class="sxs-lookup"><span data-stu-id="44499-952">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="44499-953">而當您選取時，[插入] 按鈕會告知您已經選取的數量。</span><span class="sxs-lookup"><span data-stu-id="44499-953">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="44499-954">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-954">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint"></a><span data-ttu-id="44499-955">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="44499-955">PowerPoint</span></span>

- <span data-ttu-id="44499-956">**較佳變形效果：** 命名您的圖形以便加強掌控其轉化方式。</span><span class="sxs-lookup"><span data-stu-id="44499-956">**Better shapeshifting:** Name your shapes for more control over how they morph.</span></span> [<span data-ttu-id="44499-957">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-957">Learn more</span></span>](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- <span data-ttu-id="44499-958">**快速找到該檔案：** 想要尋找最近使用過的檔案嗎？</span><span class="sxs-lookup"><span data-stu-id="44499-958">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="44499-959">只要在 [檔案] > [常用] 頁面的 [搜尋] 方塊中輸入，就能找到所需的檔案。</span><span class="sxs-lookup"><span data-stu-id="44499-959">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="44499-960">**增加您內容的覆蓋面：** 想要讓您的簡報更易於使用嗎？</span><span class="sxs-lookup"><span data-stu-id="44499-960">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="44499-961">讓協助工具檢查程式來幫助您，您不需要自行處理。</span><span class="sxs-lookup"><span data-stu-id="44499-961">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="44499-962">按一下 [校閱] > [檢查協助工具] 試試看這個功能 – 我們會在狀態列上告訴您需要留意的部分。</span><span class="sxs-lookup"><span data-stu-id="44499-962">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="44499-963">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="44499-963">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="44499-964">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="44499-964">Switching between them has never been easier.</span></span> [<span data-ttu-id="44499-965">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-965">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="44499-966">**線上影片有新的首頁：** 將影片儲存至 Microsoft Stream，讓組織中的任何人都看得到。</span><span class="sxs-lookup"><span data-stu-id="44499-966">**Online videos have a new home:** Save a video to Microsoft Stream so anyone in your organization can see it.</span></span> <span data-ttu-id="44499-967">插入影片連結，享受檔案大小只有原來一小部分的多媒體簡報。</span><span class="sxs-lookup"><span data-stu-id="44499-967">Insert the video link and enjoy a multimedia presentation at a fraction of the file size.</span></span> [<span data-ttu-id="44499-968">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-968">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="44499-969">**隨時儲存變更：** 將檔案上傳至 OneDrive，確保所有的更新都會自動儲存。</span><span class="sxs-lookup"><span data-stu-id="44499-969">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="44499-p190">**透過測驗或問卷詢問聽眾：** 在投影片上進行測驗或問卷。Office 會收集並儲存存儲您的回應。[深入了解](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span><span class="sxs-lookup"><span data-stu-id="44499-p190">**Ask your audience with a quiz or survey:** Put a quiz or survey on a slide. Office collects and stores the responses for you. [Learn more](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span></span>

- <span data-ttu-id="44499-p191">**輕鬆插入內嵌影片：** 想要在您的投影片中放入 Vimeo 或 YouTube 影片嗎？只要有影片頁面連結即可。[深入了解](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span><span class="sxs-lookup"><span data-stu-id="44499-p191">**Inserting an online video is easier than ever:** Want to put a video from Vimeo or YouTube on your slide? The video page link is all you need. [Learn more](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span></span>

- <span data-ttu-id="44499-976">**搜尋並享受：** 我們新增了 [搜尋以插入] 圖示，讓您輕鬆找到您要的圖示。</span><span class="sxs-lookup"><span data-stu-id="44499-976">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="44499-977">而當您選取時，[插入] 按鈕會告知您已經選取的數量。</span><span class="sxs-lookup"><span data-stu-id="44499-977">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="44499-978">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-978">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="project"></a><span data-ttu-id="44499-979">Project</span><span class="sxs-lookup"><span data-stu-id="44499-979">Project</span></span>

- <span data-ttu-id="44499-980">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="44499-980">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="44499-981">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="44499-981">Switching between them has never been easier.</span></span> [<span data-ttu-id="44499-982">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-982">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a><span data-ttu-id="44499-983">Visio</span><span class="sxs-lookup"><span data-stu-id="44499-983">Visio</span></span>

- <span data-ttu-id="44499-984">**將進度圖表匯出到 Word：** 在 Word 文件中自動新增圖表內容，如圖案和中繼資料。</span><span class="sxs-lookup"><span data-stu-id="44499-984">**Export process diagrams to Word:** Automatically add diagram content, such as shapes and metadata, to a Word document.</span></span> <span data-ttu-id="44499-985">然後，自訂文件來建立程序指導方針和操作手冊。</span><span class="sxs-lookup"><span data-stu-id="44499-985">Then customize the document to create process guidelines and operation manuals.</span></span> [<span data-ttu-id="44499-986">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-986">Learn more</span></span>](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- <span data-ttu-id="44499-987">**資料流程圖上的 Double-Take：** 資料視覺化工具流程圖美觀的新版面配置，既清新、簡潔且更易於了解。</span><span class="sxs-lookup"><span data-stu-id="44499-987">**Double-take on data flowcharts:** Gorgeous new layouts for Data Visualizer flowcharts are clean, crisp, and easy to understand.</span></span> <span data-ttu-id="44499-988">按一下 [設計] 索引標籤來取得選項。</span><span class="sxs-lookup"><span data-stu-id="44499-988">Click the Design tab for options.</span></span>

- <span data-ttu-id="44499-989">**內建的 Azure 樣板：** 使用數十種 Azure 樣板來設計雲端應用程式或規劃架構。</span><span class="sxs-lookup"><span data-stu-id="44499-989">**Azure stencils built right in:** Design a cloud app or plan an architecture using dozens of Azure stencils.</span></span> [<span data-ttu-id="44499-990">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-990">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- <span data-ttu-id="44499-p197">**告別錯誤的 Excel 連結：** 找不到與 Data Visualizer 圖表連結的 Excel 活頁簿嗎？重新連結，就可繼續使用了。[深入了解](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span><span class="sxs-lookup"><span data-stu-id="44499-p197">**Say goodbye to broken Excel links:** Can't find the Excel workbook linked to your Data Visualizer diagram? Relink it, and you're back in business. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span></span>

- <span data-ttu-id="44499-994">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="44499-994">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="44499-995">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="44499-995">Switching between them has never been easier.</span></span> [<span data-ttu-id="44499-996">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-996">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="44499-997">**從 Power BI 匯出 Visio 視覺效果：** 當匯出 Power BI 報表為 PDF 或 PowerPoint 等檔案時，Power BI Visio 視覺效果會正常顯示。</span><span class="sxs-lookup"><span data-stu-id="44499-997">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span> [<span data-ttu-id="44499-998">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-998">Learn more</span></span>](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a><span data-ttu-id="44499-999">Word</span><span class="sxs-lookup"><span data-stu-id="44499-999">Word</span></span>

- <span data-ttu-id="44499-1000">**[學習工具] 模式額外支援更多頁面色彩：** Word 中的 [學習工具] 新增更多頁面佈景主題色彩的支援，讓您能夠變更頁面的背景色彩。</span><span class="sxs-lookup"><span data-stu-id="44499-1000">**Learning Tools mode has additional support for more page colors:** Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span> <span data-ttu-id="44499-1001">許多人在背景全白或全黑時閱讀會有困難，因此我們在 PC 和 Mac 的 Word 中增加了色彩選項。</span><span class="sxs-lookup"><span data-stu-id="44499-1001">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

- <span data-ttu-id="44499-p201">**編輯當然是使用筆跡編輯：** 使用畫筆透過單一筆劃來分割或加入文字、新增新的一行，或插入文字。[深入了解](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span><span class="sxs-lookup"><span data-stu-id="44499-p201">**Editing comes naturally with Ink Editor:** With a single stroke, split or join words, add a new line, or insert words using your pen. [Learn more](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span></span>

- <span data-ttu-id="44499-p202">**為靜態文件注入動人的生命力：** 將文件轉變為在任何裝置上，均具有完美外觀的可互動、易分享的網頁。[深入了解](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span><span class="sxs-lookup"><span data-stu-id="44499-p202">**Take your doc from static to stunning:** Transform your document into an interactive, easy-to-share web page that looks great on any device. [Learn more](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span></span>

- <span data-ttu-id="44499-1006">**增加您內容的覆蓋面：** 想要讓您的文件更易於使用嗎？</span><span class="sxs-lookup"><span data-stu-id="44499-1006">**Increase the reach of your content:** Need to make your documents accessible?</span></span> <span data-ttu-id="44499-1007">讓協助工具檢查程式來幫助您，您不需要自行處理。</span><span class="sxs-lookup"><span data-stu-id="44499-1007">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="44499-1008">按一下 [校閱] > [檢查協助工具] 試試看這個功能 – 我們會在狀態列上告訴您需要留意的部分。</span><span class="sxs-lookup"><span data-stu-id="44499-1008">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="44499-1009">**快速找到該檔案：** 想要尋找最近使用過的檔案嗎？</span><span class="sxs-lookup"><span data-stu-id="44499-1009">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="44499-1010">只要在 [檔案] > [常用] 頁面的 [搜尋] 方塊中輸入，就能找到所需的檔案。</span><span class="sxs-lookup"><span data-stu-id="44499-1010">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="44499-1011">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="44499-1011">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="44499-1012">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="44499-1012">Switching between them has never been easier.</span></span> [<span data-ttu-id="44499-1013">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-1013">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="44499-p206">**運用行聚焦，提高理解力：** 毫不費力地逐行瀏覽文件。調整焦點，在檢視畫面中一次放入一行、三行或五行。[深入了解](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="44499-p206">**Improve comprehension with Line Focus:** Move through a document line by line without distractions. Adjust the focus to put one, three, or five lines in view at a time. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>

- <span data-ttu-id="44499-1017">**隨時儲存變更：** 將檔案上傳至 OneDrive，確保所有的更新都會自動儲存。</span><span class="sxs-lookup"><span data-stu-id="44499-1017">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="44499-1018">**使用 \@Mentions 提及功能取得他人注意：** 在註解中使用 @mentions 提及功能，讓同事知道您需要他們提供建議。</span><span class="sxs-lookup"><span data-stu-id="44499-1018">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="44499-1019">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-1019">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="44499-1020">**搜尋並享受：** 我們新增了 [搜尋以插入] 圖示，讓您輕鬆找到您要的圖示。</span><span class="sxs-lookup"><span data-stu-id="44499-1020">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="44499-1021">而當您選取時，[插入] 按鈕會告知您已經選取的數量。</span><span class="sxs-lookup"><span data-stu-id="44499-1021">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="44499-1022">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-1022">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="office-suite"></a><span data-ttu-id="44499-1023">Office 套件</span><span class="sxs-lookup"><span data-stu-id="44499-1023">Office Suite</span></span>

- <span data-ttu-id="44499-1024">**快速找到該檔案：** 想要尋找最近使用過的檔案嗎？</span><span class="sxs-lookup"><span data-stu-id="44499-1024">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="44499-1025">只要在 [檔案] > [開啟] 索引標籤的 [搜尋] 方塊中輸入，就能找到所需的檔案。</span><span class="sxs-lookup"><span data-stu-id="44499-1025">Just type in the Search box on the File > Open tab to find the file you're looking for.</span></span>

- <span data-ttu-id="44499-1026">**隨時儲存變更：** 將檔案上傳至 OneDrive，確保所有的更新都會自動儲存。</span><span class="sxs-lookup"><span data-stu-id="44499-1026">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="44499-1027">**隱私權控制：** 用於診斷資料和連線體驗的新增、更新及改良的控制項。</span><span class="sxs-lookup"><span data-stu-id="44499-1027">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> [<span data-ttu-id="44499-1028">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-1028">Learn more</span></span>](/DeployOffice/privacy/overview-privacy-controls?toc=%2fdeployoffice%2ftoc.json)

- <span data-ttu-id="44499-1029">**Office 圖示有新的外觀：** Office 圖示經過重新設計，以反映簡單、功能強大且智慧型的 Office 體驗。</span><span class="sxs-lookup"><span data-stu-id="44499-1029">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

- <span data-ttu-id="44499-1030">**安裝 Microsoft Teams：** 在 Office 365 專業增強版的現有安裝中，預設會安裝 Microsoft Teams。</span><span class="sxs-lookup"><span data-stu-id="44499-1030">**Installation of Microsoft Teams:** Microsoft Teams is installed by default for existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="44499-1031">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-1031">Learn more</span></span>](/DeployOffice/teams-install)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="44499-1034">解決的問題</span><span class="sxs-lookup"><span data-stu-id="44499-1034">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="44499-1035">Access</span><span class="sxs-lookup"><span data-stu-id="44499-1035">Access</span></span>

- <span data-ttu-id="44499-1036">此更新修正彙總 (例如 Sum) 可能會將結果截斷成整數值的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1036">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="44499-1037">此更新修正包含參照遠端桌面 (例如 SQL Server 桌面) 的聯集查詢可能造成 Access 關閉並重新啟動的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1037">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="44499-1038">此更新可修正 Microsoft Access 中的「更新查詢」執行時或在 SQL 中使用 UPDATE 陳述式時，可能導致發生錯誤「查詢已損壞」&quot;&quot;的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1038">This update fixes an issue in Microsoft Access that may cause the error &quot;Query is Corrupt&quot; when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="44499-1039">Excel</span><span class="sxs-lookup"><span data-stu-id="44499-1039">Excel</span></span>

- <span data-ttu-id="44499-1040">文件標題的荷蘭文按鍵提示已變更為 Alt-G。</span><span class="sxs-lookup"><span data-stu-id="44499-1040">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="44499-1041">修正在 Excel 中指派給圖形或表單控制項的巨集可能顯示不正確的錯誤訊息，或者可能會處理不正確目標範圍的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1041">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="44499-1042">解決「尋找及取代」在找到第一個項目後，對話方塊中的焦點位置變更的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1042">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="44499-1043">此更新修正在與其他使用者共同撰寫的工作階段中變更樞紐分析表排序的方式，然後重新整理可能觸發當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1043">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="44499-1044">我們已修正當 OLAP 樞紐分析表的篩選條件設定為已從 cube 移除的值時會發生的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1044">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="44499-1045">修正以校正使用圖表範本插入圖表時，預覽中使用的色彩。</span><span class="sxs-lookup"><span data-stu-id="44499-1045">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="44499-1046">我們已修正當變更系列集合時，可能會導致散佈折線圖無法正確呈現的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1046">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span>

- <span data-ttu-id="44499-1047">已解決當插入或刪除儲存格時，瀑布圖和漏斗圖無法與表格同步處理的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1047">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="44499-1048">修正 Excel 中合併衝突的問題，此問題會造成提示使用者重新開啟活頁簿以取得變更。</span><span class="sxs-lookup"><span data-stu-id="44499-1048">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="44499-1049">解決了開啟內嵌活頁簿時，功能區自訂無法載入的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1049">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="44499-1050">已解決造成執行階段錯誤啟動最小化視窗的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1050">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="44499-1051">解決了開啟內嵌活頁簿時，功能區自訂無法載入的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1051">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="44499-1052">已解決導致表格旁的剪下並貼上作業在與其他人共同撰寫時失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1052">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="44499-1053">解決使用執行中巨集變更自訂屬性時，會導致共同撰寫中斷的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1053">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="44499-1054">發生您無法從增益集開啟的 WPF (Windows Presentation Foundation) 表單的下拉式方塊選取項目的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1054">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="44499-1055">解決在未開啟活頁簿時，搜尋最近使用的檔案會造成當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1055">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="44499-1056">非同步使用者定義函數造成的效能問題，導致它們同步執行。</span><span class="sxs-lookup"><span data-stu-id="44499-1056">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="44499-1057">已大幅改善刪除有合併儲存格之欄的效能。</span><span class="sxs-lookup"><span data-stu-id="44499-1057">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="44499-1058">解決捲動後選取儲存格時，可能導致選取錯誤儲存格的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1058">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="44499-1059">已解決 Lookup 函數可能會傳回錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1059">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="44499-1060">解決在目前的 Office 版本中開啟在舊版 Office 中建立的活頁簿時，可能導致 Excel 懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1060">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="44499-1061">當檔案具備大量設定格式化的條件時，按一下 [字型色彩] 按鈕時出現的效能緩慢問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1061">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="44499-1062">我們已修正預覽列印中的列印範圍不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1062">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="44499-1063">從不受信任的網路共用編輯受保護的檔案時，Excel 可能會發生問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1063">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="44499-1064">我們已大幅提升依色彩篩選的效能。</span><span class="sxs-lookup"><span data-stu-id="44499-1064">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="44499-1065">已解決會導致將超連結貼到一些受保護工作表中的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1065">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="44499-1066">當在增益集管理員中瀏覽時，顯示 16 個以上的增益集。</span><span class="sxs-lookup"><span data-stu-id="44499-1066">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="44499-1067">這項變更透過利用軟體轉譯避免特定 Intel 圖形驅動程式發生問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1067">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="44499-1068">來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。</span><span class="sxs-lookup"><span data-stu-id="44499-1068">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="44499-1069">此更新修正 Office 文件無法上傳到商務用 OneDrive 的錯誤 (訊息「上傳失敗」)。</span><span class="sxs-lookup"><span data-stu-id="44499-1069">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="44499-1070">修正在 Excel 構想功能中，在 Win32 用戶端中按一下 [構想] 按鈕來載入增益集時會發生錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1070">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span>

### <a name="outlook"></a><span data-ttu-id="44499-1071">Outlook</span><span class="sxs-lookup"><span data-stu-id="44499-1071">Outlook</span></span>

- <span data-ttu-id="44499-1072">來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。</span><span class="sxs-lookup"><span data-stu-id="44499-1072">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="44499-1073">修正使用者將信箱從基本驗證升級為新式驗證後，造成將錯誤的帳戶與其 Outlook 設定檔相關聯的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1073">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="44499-1074">已解決造成網頁增益集在不該存取數位版權管理郵件時進行存取的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1074">Addressed an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="44499-1075">已解決導致部分安全連結無法顯示簡單動態顯示 URL 的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1075">Addressed an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="44499-1076">更新 Outlook 中的附件封鎖邏輯，以同時封鎖 python 附件。</span><span class="sxs-lookup"><span data-stu-id="44499-1076">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="44499-1077">已解決導致部分 POP3 使用者查看所有純文字格式電子郵件 (無論設定) 的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1077">Addressed an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="44499-1078">此修正將會還原 HTML 格式郵件的檢視。</span><span class="sxs-lookup"><span data-stu-id="44499-1078">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="44499-1079">已解決當使用者將項目從其主要行事曆複製到群組行事曆時，造成使用者遇到權限錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1079">Addressed an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="44499-1080">已解決導致使用者無法透過螢幕助讀程式存取位置建議的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1080">Addressed an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="44499-1081">已解決當使用者透過鍵盤快速鍵與信箱資料夾互動時造成明顯延遲的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1081">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="44499-1082">已解決導致非常長時間的 Outlook 工作階段記憶體流失的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1082">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="44499-1083">已解決導致使用者在開啟 [規則] 對話方塊時看到「在這部電腦中建立的規則和 Microsoft Exchange 上的規則衝突」提示的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1083">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="44499-1084">已解決導致使用者在與特定安全連結互動時在 Outlook 中發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1084">Addressed an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="44499-1085">已解決導致經理對於代理人是否已經回覆特定會議邀請含混不清的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1085">Addressed an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="44499-1086">已解決導致使用者在處理某些自動探索回應時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1086">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="44499-1087">已解決導致使用者在嘗試從 [帳戶建立] 內容連絡支援服務時，看到具有 [確定] 按鈕的空白訊息方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1087">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="44499-1088">此變更可讓系統管理員啟用一個原則，以在自動探索驗證提示中較 UPN 優先使用所提供的帳戶電子郵件。</span><span class="sxs-lookup"><span data-stu-id="44499-1088">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="44499-1089">依預設，自動探索會優先於帳戶 UPN (如果有的話)。</span><span class="sxs-lookup"><span data-stu-id="44499-1089">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="44499-1090">解決會導致使用者看到針對新式群組的搜尋失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1090">Addressed an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="44499-1091">已解決導致 Outlook 使用者在特定案例中停滯在「需要密碼」狀態的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1091">Addressed an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="44499-1092">已解決以下問題：使用者看到某會議室可用時間之外的會議室建議。</span><span class="sxs-lookup"><span data-stu-id="44499-1092">Addressed an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="44499-1093">已解決導致使用者在傳送加密電子郵件時遇到「不支援的加密演算法」錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1093">Addressed an issue that caused users to encounter "encryption algorithm is not supported" errors when sending an encrypted email.</span></span>

- <span data-ttu-id="44499-1094">已解決非英文使用者的郵件中，主旨列會相當小的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1094">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="44499-1095">已解決導致某些使用者在新增次要 Exchange 帳戶時看到建立了重複特殊資料夾的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1095">Addressed an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="44499-1096">已解決導致使用者嘗試從「未接的交談」建立規則時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1096">Addressed an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="44499-1097">修正 SMIME 演算法選取的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1097">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="44499-1098">已解決使用其他寄件者時導致無法顯示原則提示的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1098">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="44499-1099">已解決導致使用者在 Outlook 處理序中看到記憶體洩漏的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1099">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="44499-1100">已解決導致使用者在更新目前狀態資訊時遇到間歇性當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1100">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="44499-1101">已解決導致目前的資料夾搜尋間歇性失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1101">Addressed an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="44499-1102">已解決嘗試擷取使用者的 Outlook 雲端設定時，導致一些使用者遇到驗證錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1102">Addressed an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="44499-1103">已解決導致在搜尋意見反應體驗中懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1103">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="44499-1104">已解決導致使用者在處理某些自動探索回應時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1104">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="44499-1105">已解決導致使用者在更新目前狀態資訊時遇到間歇性當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1105">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="44499-1106">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="44499-1106">PowerPoint</span></span>

- <span data-ttu-id="44499-1107">修正某些增益集會在圖表的圖形周圍擲出未預期錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1107">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="44499-1108">來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。</span><span class="sxs-lookup"><span data-stu-id="44499-1108">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="44499-1109">此變更還原 PowerPoint 影片控制項的協助工具名稱的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1109">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="44499-1110">我們已修正部分動畫無法開始的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1110">We fixed an issue which could prevent some animations from starting.</span></span>

- <span data-ttu-id="44499-1111">我們已修正將投影片從一個簡報複製到另一個簡報時可能會造成母片重複的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1111">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>

- <span data-ttu-id="44499-1112">如果在不支援的版本中開啟含有新的新式註解的檔案，將會顯示黃色警告</span><span class="sxs-lookup"><span data-stu-id="44499-1112">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

- <span data-ttu-id="44499-1113">可靠性修正：已修正第三方增益集可能會造成 PowerPoint 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1113">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="44499-1114">修正 PowerPoint 中半形片假名字元在垂直文字方塊中無法正確旋轉的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1114">Fixed an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="44499-1115">Project</span><span class="sxs-lookup"><span data-stu-id="44499-1115">Project</span></span>

- <span data-ttu-id="44499-1116">修正讓 Windows 7 上的使用者能夠從 Project Web App 和 SharePoint 網站開啟專案的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1116">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="44499-1117">發現在開啟唯讀專案時，使用者可能會收到數個訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1117">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="44499-1118">「全部撫平」命令無法正確解決資源過度分派的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1118">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="44499-1119">當您有作業中有零個工作的指派時，可能無法將作業標示為完成且永遠會顯示為 99%。</span><span class="sxs-lookup"><span data-stu-id="44499-1119">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

### <a name="visio"></a><span data-ttu-id="44499-1120">Visio</span><span class="sxs-lookup"><span data-stu-id="44499-1120">Visio</span></span>

- <span data-ttu-id="44499-1121">無法從 Visio 將多個圖形匯出為 SVG。</span><span class="sxs-lookup"><span data-stu-id="44499-1121">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="44499-1122">Word</span><span class="sxs-lookup"><span data-stu-id="44499-1122">Word</span></span>

- <span data-ttu-id="44499-1123">此變更能讓使用 Word 開啟文件的效能提升。</span><span class="sxs-lookup"><span data-stu-id="44499-1123">This change will lead to performance improvements in opening documents using Word.</span></span>

- <span data-ttu-id="44499-1124">來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。</span><span class="sxs-lookup"><span data-stu-id="44499-1124">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="44499-1125">我們已修正當列印到 Deskjet 印表機時，可能會導致縮放比例問題的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1125">We fixed an issue which could have caused scaling issues when printing to Deskjet printers.</span></span>

- <span data-ttu-id="44499-1126">我們已修正追蹤修訂有時候會進入無限迴圈的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1126">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="44499-1127">修正應用程式可能在關機時懸置的各種問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1127">Fixed various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="44499-1128">同時修正特定相關增益集當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1128">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="44499-1129">Office 套件</span><span class="sxs-lookup"><span data-stu-id="44499-1129">Office Suite</span></span>

- <span data-ttu-id="44499-1130">修正不正確地將平假名和漢字中的日本新年號 "Reiwa" (令和) 識別為拼字錯誤或不合文法的運算式的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1130">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="44499-1131">修正嘗試共用儲存在 SharePoint 2016 上的檔案時，導致使用者遇到「很抱歉，發生問題，無法共用」訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1131">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="44499-1132">修正在 PowerPoint 共同撰寫和離線編輯的工作階段中可能會導致資料遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1132">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="44499-1133">修正使用者在開啟檔案時可能會遇到的當機問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1133">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="44499-1134">避免 PowerPoint 使用者嘗試進行「線上展示」時遇到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1134">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

- <span data-ttu-id="44499-1135">在某些情況下，同步處理引擎備份的 SharePoint 檔案可能會顯示「已儲存」但實際上未儲存任何變更，導致資料遺失。</span><span class="sxs-lookup"><span data-stu-id="44499-1135">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="44499-1136">解決使用者可能無法儲存 Word、Excel 和 PowerPoint 文件的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1136">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="44499-1137">此問題會影響建立新檔案並在按一下 [儲存] 圖示或按 Ctrl + S 之後帶出 [另存成模型對話方塊] 選項的使用者。</span><span class="sxs-lookup"><span data-stu-id="44499-1137">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="44499-1138">修正 Win7 的效能問題，其中，於所有應用程式中從功能區插入圖案庫時，大約需要 4 秒鐘的時間才會顯示。</span><span class="sxs-lookup"><span data-stu-id="44499-1138">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="44499-1139">修正 Backstage 的 [資訊位置] 平板未顯示協助工具資訊的錯誤。</span><span class="sxs-lookup"><span data-stu-id="44499-1139">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="44499-1140">改善有關登錄完整性的 Office 更新程序的可靠性。</span><span class="sxs-lookup"><span data-stu-id="44499-1140">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="44499-1141">解決 Office 更新可能會非預期地從 Office CDN 而不是預期使用的來源 (例如本機或網路共用或 Configuration Manager 提供的位置) 下載檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1141">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="44499-1142">修正 Office 更新訊息不以預期語言顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1142">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="44499-1143">自此以後，Office 更新訊息會正確符合 Windows 顯示語言。</span><span class="sxs-lookup"><span data-stu-id="44499-1143">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="44499-1144">已解決在某些情況下，如果使用者不是系統管理員且系統帳戶沒有網路連線，將無法套用更新的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1144">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="44499-1145">某些情況下，Office 快速鍵可能會在更新後消失。</span><span class="sxs-lookup"><span data-stu-id="44499-1145">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="44499-1146">此更新可改善發佈 Office 快速鍵時的可靠性。</span><span class="sxs-lookup"><span data-stu-id="44499-1146">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="44499-1147">已更正可能會在計量網路上意外封鎖更新的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1147">Corrected an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="44499-1148">修正相對期限只有在第一次設定時才會有效的 ODT 和 GPO 更新期限設定中的錯誤 (bug)。此修正可啟用後續更新的相關期限。</span><span class="sxs-lookup"><span data-stu-id="44499-1148">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="44499-1149">已改善透過恢復之前可能已中斷的下載，下載 Office 更新時的可靠性。</span><span class="sxs-lookup"><span data-stu-id="44499-1149">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="44499-1150">已解決第三方外掛程式中與文字方塊/圖案自動調整屬性相關的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1150">Addressed issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="44499-1151">我們已修正大型樹狀檢視可能會導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1151">We fixed an issue where large tree views could result in a crash.</span></span>

- <span data-ttu-id="44499-1152">為了保護 Office 客戶的安全性，我們現在專門使用 SHA-2 演算法來簽署 Microsoft Office 更新。</span><span class="sxs-lookup"><span data-stu-id="44499-1152">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-january-14"></a><span data-ttu-id="44499-1154">版本 1902：1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="44499-1154">Version 1902: January 14</span></span>
<span data-ttu-id="44499-1155">*版本 1902 (組建 11328.20512)*</span><span class="sxs-lookup"><span data-stu-id="44499-1155">*Version 1902 (Build 11328.20512)*</span></span>

<span data-ttu-id="44499-1156">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-1156">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="44499-1158">解決的問題</span><span class="sxs-lookup"><span data-stu-id="44499-1158">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="44499-1159">Excel</span><span class="sxs-lookup"><span data-stu-id="44499-1159">Excel</span></span>

- <span data-ttu-id="44499-1160">解決了開啟內嵌活頁簿時，功能區自訂無法載入的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1160">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="44499-1161">Outlook</span><span class="sxs-lookup"><span data-stu-id="44499-1161">Outlook</span></span>

- <span data-ttu-id="44499-1162">解決導致使用者在傳送加密電子郵件時遇到「不支援的加密演算法」錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1162">Addresses an issue that caused users to encounter "encryption algorithm is not supporte" errors when sending an encrypted email.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="44499-1163">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="44499-1163">PowerPoint</span></span>

- <span data-ttu-id="44499-1164">如果在不支援的版本中開啟含有新的新式註解的檔案，將會顯示黃色警告。</span><span class="sxs-lookup"><span data-stu-id="44499-1164">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

### <a name="word"></a><span data-ttu-id="44499-1165">Word</span><span class="sxs-lookup"><span data-stu-id="44499-1165">Word</span></span>

- <span data-ttu-id="44499-1166">此變更能讓使用 Word 開啟文件的效能提升。</span><span class="sxs-lookup"><span data-stu-id="44499-1166">This change will lead to performance improvements in opening documents using Word.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1808-january-14"></a><span data-ttu-id="44499-1168">版本 1808：1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="44499-1168">Version 1808: January 14</span></span>
<span data-ttu-id="44499-1169">*版本 1808 (組建 10730.20432)*</span><span class="sxs-lookup"><span data-stu-id="44499-1169">*Version 1808 (Build 10730.20432)*</span></span>

<span data-ttu-id="44499-1170">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-1170">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-december-10"></a><span data-ttu-id="44499-1172">版本 1902：12 月 10 日</span><span class="sxs-lookup"><span data-stu-id="44499-1172">Version 1902: December 10</span></span>
<span data-ttu-id="44499-1173">*版本 1902 (組建 11328.20492)*</span><span class="sxs-lookup"><span data-stu-id="44499-1173">*Version 1902 (Build 11328.20492)*</span></span>

<span data-ttu-id="44499-1174">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-1174">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="44499-1176">解決的問題</span><span class="sxs-lookup"><span data-stu-id="44499-1176">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="44499-1177">Excel</span><span class="sxs-lookup"><span data-stu-id="44499-1177">Excel</span></span>

- <span data-ttu-id="44499-1178">這項變更透過利用軟體轉譯避免特定 Intel 圖形驅動程式發生問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1178">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

### <a name="outlook"></a><span data-ttu-id="44499-1179">Outlook</span><span class="sxs-lookup"><span data-stu-id="44499-1179">Outlook</span></span>

- <span data-ttu-id="44499-1180">Outlook 中明年的行事曆項目可能會顯示不正確。</span><span class="sxs-lookup"><span data-stu-id="44499-1180">Calendar items for next year may display an incorrect time in Outlook.</span></span> [<span data-ttu-id="44499-1181">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-1181">Learn More</span></span>](/outlook/troubleshoot/calendars/calendar-items-display-incorrect-time)

- <span data-ttu-id="44499-1182">解決會導致客戶嘗試從「未接的交談」&quot;&quot;郵件建立規則時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1182">Addresses an issue that caused customers to encounter a crash when attempting to create a rule from a &quot;missed conversation&quot; message.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="44499-1183">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="44499-1183">PowerPoint</span></span>

- <span data-ttu-id="44499-1184">已修正列印備忘稿 (部分案例有版面配置問題) 相關的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1184">Fixed an issue related to printing in notes page that had layout issues in some cases.</span></span>

## <a name="version-1808-december-10"></a><span data-ttu-id="44499-1185">版本 1808：12 月 10 日</span><span class="sxs-lookup"><span data-stu-id="44499-1185">Version 1808: December 10</span></span>
<span data-ttu-id="44499-1186">*版本 1808 (組建 10730.20426)*</span><span class="sxs-lookup"><span data-stu-id="44499-1186">*Version 1808 (Build 10730.20426)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="44499-1187">解決的問題</span><span class="sxs-lookup"><span data-stu-id="44499-1187">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="44499-1188">Outlook</span><span class="sxs-lookup"><span data-stu-id="44499-1188">Outlook</span></span>

- <span data-ttu-id="44499-1189">Outlook 中明年的行事曆項目可能會顯示不正確。</span><span class="sxs-lookup"><span data-stu-id="44499-1189">Calendar items for next year may display an incorrect time in Outlook.</span></span> [<span data-ttu-id="44499-1190">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-1190">Learn More</span></span>](/outlook/troubleshoot/calendars/calendar-items-display-incorrect-time)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-november-22"></a><span data-ttu-id="44499-1192">版本 1902：11 月 22 日</span><span class="sxs-lookup"><span data-stu-id="44499-1192">Version 1902: November 22</span></span>
<span data-ttu-id="44499-1193">*版本 1902 (組建 11328.20480)*</span><span class="sxs-lookup"><span data-stu-id="44499-1193">*Version 1902 (Build 11328.20480)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="44499-1195">解決的問題</span><span class="sxs-lookup"><span data-stu-id="44499-1195">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="44499-1196">Access</span><span class="sxs-lookup"><span data-stu-id="44499-1196">Access</span></span>

- <span data-ttu-id="44499-1197">已修正執行更新查詢會不正確顯示「查詢損毀」錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1197">Fixed an issue where running an Update query would incorrectly give an error message: "Query is corrupt".</span></span>

### <a name="outlook"></a><span data-ttu-id="44499-1198">Outlook</span><span class="sxs-lookup"><span data-stu-id="44499-1198">Outlook</span></span>

- <span data-ttu-id="44499-1199">解決啟用快顯通知時，導致使用者注意到記憶體流失的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1199">Addressed an issue that caused users to observe memory leaks when toast notifications were enabled.</span></span>

### <a name="office-suite"></a><span data-ttu-id="44499-1200">Office 套件</span><span class="sxs-lookup"><span data-stu-id="44499-1200">Office Suite</span></span>

- <span data-ttu-id="44499-1201">藉由此變更，將不會針對與節流無關的同步處理錯誤加以限制同步處理。</span><span class="sxs-lookup"><span data-stu-id="44499-1201">With this change, syncing will not be throttled for sync errors that are not related to throttling.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1808-november-22"></a><span data-ttu-id="44499-1203">版本 1808：11 月 22 日</span><span class="sxs-lookup"><span data-stu-id="44499-1203">Version 1808: November 22</span></span>
<span data-ttu-id="44499-1204">*版本 1808 (組建 10730.20422)*</span><span class="sxs-lookup"><span data-stu-id="44499-1204">*Version 1808 (Build 10730.20422)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="access"></a><span data-ttu-id="44499-1206">Access</span><span class="sxs-lookup"><span data-stu-id="44499-1206">Access</span></span>

- <span data-ttu-id="44499-1207">已修正執行更新查詢會不正確顯示「查詢損毀」錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1207">Fixed an issue where running an Update query would incorrectly give an error message: "Query is corrupt".</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-november-12"></a><span data-ttu-id="44499-1209">版本 1902：11 月 12 日</span><span class="sxs-lookup"><span data-stu-id="44499-1209">Version 1902: November 12</span></span>
<span data-ttu-id="44499-1210">*版本 1902 (組建 11328.20468)*</span><span class="sxs-lookup"><span data-stu-id="44499-1210">*Version 1902 (Build 11328.20468)*</span></span>

<span data-ttu-id="44499-1211">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-1211">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="44499-1213">解決的問題</span><span class="sxs-lookup"><span data-stu-id="44499-1213">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="44499-1214">Excel</span><span class="sxs-lookup"><span data-stu-id="44499-1214">Excel</span></span>

- <span data-ttu-id="44499-1215">解決在刪除某個範圍之後，可能會導致輸入的值延遲顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1215">Resolved an issue that was causing delays in displaying typed values after deleting a range.</span></span>
- <span data-ttu-id="44499-1216">解決在目前的 Office 版本中開啟在舊版 Office 中建立的活頁簿時，可能導致 Excel 懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1216">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

### <a name="outlook"></a><span data-ttu-id="44499-1217">Outlook</span><span class="sxs-lookup"><span data-stu-id="44499-1217">Outlook</span></span>

- <span data-ttu-id="44499-1218">解決啟用快顯通知時，導致使用者注意到記憶體流失的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1218">Addressed an issue that caused users to observe memory leaks when toast notifications were enabled.</span></span>
- <span data-ttu-id="44499-1219">解決會導致客戶注意到 Outlook 中的記憶體流失的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1219">Addressed an issue that caused customers to notice a memory leak in Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="44499-1220">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="44499-1220">PowerPoint</span></span>

- <span data-ttu-id="44499-1221">可靠性修正：修正第三方增益集可能會造成 PowerPoint 失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1221">Reliability fix: Fixed an issue where third party add-in might cause PowerPoint to fail.</span></span>

### <a name="word"></a><span data-ttu-id="44499-1222">Word</span><span class="sxs-lookup"><span data-stu-id="44499-1222">Word</span></span>

- <span data-ttu-id="44499-1223">我們已修正在嘗試完成部分特殊字元時，字型變更為 MS Mincho 的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1223">We fixed an issue with font changed to MS Mincho when trying to finalize some special characters.</span></span>

### <a name="office-suite"></a><span data-ttu-id="44499-1224">Office 套件</span><span class="sxs-lookup"><span data-stu-id="44499-1224">Office Suite</span></span>

- <span data-ttu-id="44499-1225">修正 Win7 上的效能問題，其中，於所有應用程式中從功能區插入圖案庫時，大約需要 4 秒鐘的時間才會顯示。</span><span class="sxs-lookup"><span data-stu-id="44499-1225">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>
- <span data-ttu-id="44499-1226">修正 [開始功能表] 快速鍵和 Office 副檔名會在更新之後意外消失的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1226">Fixed an issue where Start Menu shortcuts and Office file extensions would unexpectedly disappear following an update.</span></span>
- <span data-ttu-id="44499-1227">為了保護 Office 客戶的安全性，我們現在專門使用 SHA-2 演算法來簽署 Microsoft Office 更新。</span><span class="sxs-lookup"><span data-stu-id="44499-1227">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1808-november-12"></a><span data-ttu-id="44499-1229">版本 1808：11 月 12 日</span><span class="sxs-lookup"><span data-stu-id="44499-1229">Version 1808: November 12</span></span>
<span data-ttu-id="44499-1230">*版本 1808 (組建 10730.20416)*</span><span class="sxs-lookup"><span data-stu-id="44499-1230">*Version 1808 (Build 10730.20416)*</span></span>

<span data-ttu-id="44499-1231">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-1231">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="44499-1233">解決的問題</span><span class="sxs-lookup"><span data-stu-id="44499-1233">Resolved issues</span></span>

### <a name="outlook"></a><span data-ttu-id="44499-1234">Outlook</span><span class="sxs-lookup"><span data-stu-id="44499-1234">Outlook</span></span>

- <span data-ttu-id="44499-1235">解決會導致將 [要離線保留的郵件] 設定為 [全部] 以外的使用者，在將同步處理視窗外部的項目從本機存放區移至 Exchange Online 信箱時，會看到資料遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1235">Addresses an issue that caused users with a "mail to keep offline setting" of anything other than "All" to see data loss when moving items outside of the sync window from a local store to Exchange Online mailbox.</span></span>

### <a name="office-suite"></a><span data-ttu-id="44499-1236">Office 套件</span><span class="sxs-lookup"><span data-stu-id="44499-1236">Office Suite</span></span>

- <span data-ttu-id="44499-1237">為了保護 Office 客戶的安全性，我們現在專門使用 SHA-2 演算法來簽署 Microsoft Office 更新。</span><span class="sxs-lookup"><span data-stu-id="44499-1237">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-october-08"></a><span data-ttu-id="44499-1239">版本 1902：10 月 8 日</span><span class="sxs-lookup"><span data-stu-id="44499-1239">Version 1902: October 08</span></span>
<span data-ttu-id="44499-1240">*版本 1902 (組建 11328.20438)*</span><span class="sxs-lookup"><span data-stu-id="44499-1240">*Version 1902 (Build 11328.20438)*</span></span>

<span data-ttu-id="44499-1241">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-1241">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a><span data-ttu-id="44499-1243">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1243">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="44499-1244">Excel</span><span class="sxs-lookup"><span data-stu-id="44499-1244">Excel</span></span>

- <span data-ttu-id="44499-1245">已解決會導致將超連結貼到一些受保護工作表中的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1245">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

### <a name="project"></a><span data-ttu-id="44499-1246">Project</span><span class="sxs-lookup"><span data-stu-id="44499-1246">Project</span></span>

- <span data-ttu-id="44499-1247">已修正無法在下列情況中建立 XPS 檔案的 PDF 的問題：</span><span class="sxs-lookup"><span data-stu-id="44499-1247">Fixed an issue when the PDF of XPS file is not created in the following scenario:</span></span><ul><li><span data-ttu-id="44499-1248">開啟專案。</span><span class="sxs-lookup"><span data-stu-id="44499-1248">You open a project.</span></span></li><li><span data-ttu-id="44499-1249">按一下 [檔案] 功能表、按一下 [匯出]、然後按一下 [建立 PDF/XPS] <b></b>按鈕。</span><span class="sxs-lookup"><span data-stu-id="44499-1249">You click the File menu, click Export and click the<b> Create PDF/XPS</b> button.</span></span></li><li><span data-ttu-id="44499-1250">在 [瀏覽] 對話方塊中、輸入檔案名稱、然後按一下 [確定]。</span><span class="sxs-lookup"><span data-stu-id="44499-1250">Within the Browse dialog box, you enter a file name and click OK.</span></span></li></ul>

### <a name="word"></a><span data-ttu-id="44499-1251">Word</span><span class="sxs-lookup"><span data-stu-id="44499-1251">Word</span></span>

- <span data-ttu-id="44499-1252">已修正 Windows 目前組建的 JAWS 在使用 Caps + 向右鍵時無法讀出字詞的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1252">Fixed an issue where JAWS on Windows current builds won't announce words when using Caps + Right arrow.</span></span>

### <a name="office-suite"></a><span data-ttu-id="44499-1253">Office 套件</span><span class="sxs-lookup"><span data-stu-id="44499-1253">Office Suite</span></span>

- <span data-ttu-id="44499-1254">使用者現在可以儲存由 OneDrive 同步處理用戶端同步處理的 Office 檔案，但缺少必要的屬性。</span><span class="sxs-lookup"><span data-stu-id="44499-1254">Users will now be able to save Office files synced by the OneDrive sync client with missing required properties.</span></span> <span data-ttu-id="44499-1255">透過移至 [檔案 > 資訊]，可繼續在文件 Backstage 中查看和編輯文件內容。</span><span class="sxs-lookup"><span data-stu-id="44499-1255">The document properties will continue to be available for viewing and editing through the document backstage by going to File>Info.</span></span> <span data-ttu-id="44499-1256">這項變更導致效能提升。</span><span class="sxs-lookup"><span data-stu-id="44499-1256">This change will lead to performance improvements.</span></span>

- <span data-ttu-id="44499-1257">已修正 [修正我的帳戶]&quot;&quot; 通知未在登入成功之後消失的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1257">Fixed an issue where &quot;Fix my account&quot; notification does not disappear after signing-in successfully.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1808-october-08"></a><span data-ttu-id="44499-1259">版本 1808：10 月 8 日</span><span class="sxs-lookup"><span data-stu-id="44499-1259">Version 1808: October 08</span></span>

<span data-ttu-id="44499-1260">*版本 1808 (組建 10730.20386)*</span><span class="sxs-lookup"><span data-stu-id="44499-1260">*Version 1808 (Build 10730.20386)*</span></span>

<span data-ttu-id="44499-1261">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-1261">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

## <a name="version-1902-september-10"></a><span data-ttu-id="44499-1262">版本 1902：9 月 10 日</span><span class="sxs-lookup"><span data-stu-id="44499-1262">Version 1902: September 10</span></span>
<span data-ttu-id="44499-1263">*版本 1902 (組建 11328.20420)*</span><span class="sxs-lookup"><span data-stu-id="44499-1263">*Version 1902 (Build 11328.20420)*</span></span>

<span data-ttu-id="44499-1264">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-1264">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a><span data-ttu-id="44499-1266">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1266">Non-security updates</span></span>
### <a name="access"></a><span data-ttu-id="44499-1267">Access</span><span class="sxs-lookup"><span data-stu-id="44499-1267">Access</span></span>

- <span data-ttu-id="44499-1268">修正會導致 Microsoft Access 中特定查詢執行速度較舊版組建中更慢的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1268">Fixed an issue that caused certain queries in Microsoft Access to run more slowly than in previous builds.</span></span>

### <a name="outlook"></a><span data-ttu-id="44499-1269">Outlook</span><span class="sxs-lookup"><span data-stu-id="44499-1269">Outlook</span></span>

- <span data-ttu-id="44499-1270">修正導致使用者看到「找不到此檔案」錯誤的暫時服務問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1270">Fixed temporary service issue that caused users to see the error "Cannot find this file.</span></span> <span data-ttu-id="44499-1271">使用雲端附件時，請確認路徑和檔案名正確。</span><span class="sxs-lookup"><span data-stu-id="44499-1271">Verify the path and file name are correct" when using cloud attachments.</span></span> [<span data-ttu-id="44499-1272">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-1272">Learn more</span></span>](https://support.office.com/article/outlook-unable-to-attach-onedrive-or-sharepoint-files-to-emails-136951bb-60dc-478a-b916-6ee39e62c37a)

- <span data-ttu-id="44499-1273">修正會導致使用者看到從 Outlook 上傳至 OneDrive 或 SharePoint 檔案其檔案名稱已變更，其中的數個字元由底線取代的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1273">Fixed an issue that caused users to see uploaded files from Outlook to OneDrive or Sharepoint have the file name changed where several characters replaced by underscores.</span></span>

### <a name="word"></a><span data-ttu-id="44499-1274">Word</span><span class="sxs-lookup"><span data-stu-id="44499-1274">Word</span></span>

- <span data-ttu-id="44499-1275">修正在 Word 文件上與其他人共同作業時，使用者會遇到錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1275">Fixed an issue where users would get error messages while collaborating with others on a Word document.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1808-september-10"></a><span data-ttu-id="44499-1277">版本 1808：9 月 10 日</span><span class="sxs-lookup"><span data-stu-id="44499-1277">Version 1808: September 10</span></span>
<span data-ttu-id="44499-1278">*版本 1808 (組建 10730.20380)*</span><span class="sxs-lookup"><span data-stu-id="44499-1278">*Version 1808 (Build 10730.20380)*</span></span>

<span data-ttu-id="44499-1279">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-1279">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a><span data-ttu-id="44499-1281">非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1281">Non-security updates</span></span>
### <a name="access"></a><span data-ttu-id="44499-1282">Access</span><span class="sxs-lookup"><span data-stu-id="44499-1282">Access</span></span>

- <span data-ttu-id="44499-1283">修正會導致 Microsoft Access 中特定查詢執行速度較舊版組建中更慢的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1283">Fixed an issue that caused certain queries in Microsoft Access to run more slowly than in previous builds.</span></span>

## <a name="version-1902-august-13"></a><span data-ttu-id="44499-1284">版本 1902：8 月 13 日</span><span class="sxs-lookup"><span data-stu-id="44499-1284">Version 1902: August 13</span></span>
<span data-ttu-id="44499-1285">*版本 1902 (組建 11328.20392)*</span><span class="sxs-lookup"><span data-stu-id="44499-1285">*Version 1902 (Build 11328.20392)*</span></span>

<span data-ttu-id="44499-1286">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-1286">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="44499-1287">Excel：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1287">Excel: Non-security updates</span></span>
- <span data-ttu-id="44499-1288">修正清除篩選圖示同時對表格中已篩選和未篩選交叉分析篩選器顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1288">Fixed an issue where the clear filter icon was shown for both filtered and unfiltered Slicers in tables.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="44499-1289">Outlook：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1289">Outlook: Non-security updates</span></span>
- <span data-ttu-id="44499-1290">修正使用者將信箱從基本驗證升級為新式驗證後，造成關聯的帳戶錯誤的問題</span><span class="sxs-lookup"><span data-stu-id="44499-1290">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="44499-1291">PowerPoint：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1291">PowerPoint: Non-security updates</span></span>
- <span data-ttu-id="44499-1292">修正與其他使用者就文件共同作業時，應用程式可能會意外終止的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1292">Fixed an issue where the application could unexpectedly terminate while collaborating on a document with other users.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="44499-1293">Word：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1293">Word: Non-security updates</span></span>
- <span data-ttu-id="44499-1294">修正 VBA 更新欄位很緩慢的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1294">Fixed an issue which VBA updating fields were slow.</span></span>
- <span data-ttu-id="44499-1295">修正開啟部分 DOC 檔案時，出現提示說明檔案已損毀的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1295">Fixed in issue when opening some DOC file, it says it is corrupt.</span></span>
- <span data-ttu-id="44499-1296">修正與其他使用者就文件共同作業時，應用程式可能會意外終止的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1296">Fixed an issue where the application could unexpectedly terminate while collaborating on a document with other users.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="44499-1297">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1297">Office Suite: Non-security updates</span></span>
- <span data-ttu-id="44499-1298">修正設定 API 在某些案例下無法在 Office JavaScript 程式庫運作的問題 [深入了解](https://support.microsoft.com/help/4475551/august-6-2019-update-for-office-2016-kb4475551)</span><span class="sxs-lookup"><span data-stu-id="44499-1298">Fixed an issue in which Setting API doesn't work in the Office JavaScript library in certain scenarios [Learn More](https://support.microsoft.com/help/4475551/august-6-2019-update-for-office-2016-kb4475551)</span></span>

## <a name="version-1808-august-13"></a><span data-ttu-id="44499-1299">版本 1808：8 月 13 日</span><span class="sxs-lookup"><span data-stu-id="44499-1299">Version 1808 August 13</span></span>
<span data-ttu-id="44499-1300">*版本 1808 (組建 10730.20370)*</span><span class="sxs-lookup"><span data-stu-id="44499-1300">*Version 1808 (Build 10730.20370)*</span></span>

<span data-ttu-id="44499-1301">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-1301">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="44499-1302">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1302">Office Suite: Non-security updates</span></span>
- <span data-ttu-id="44499-1303">修正設定 API 在某些案例下無法在 Office JavaScript 程式庫運作的問題 [深入了解](https://support.microsoft.com/help/4475551/august-6-2019-update-for-office-2016-kb4475551)</span><span class="sxs-lookup"><span data-stu-id="44499-1303">Fixed an issue in which Setting API doesn't work in the Office JavaScript library in certain scenarios [Learn More](https://support.microsoft.com/help/4475551/august-6-2019-update-for-office-2016-kb4475551)</span></span>


## <a name="version-1803-august-13"></a><span data-ttu-id="44499-1304">版本 1803：8 月 13 日</span><span class="sxs-lookup"><span data-stu-id="44499-1304">Version 1803 August 13</span></span>
<span data-ttu-id="44499-1305">*版本 1803 (組建 9126.2432)*</span><span class="sxs-lookup"><span data-stu-id="44499-1305">*Version 1803 (Build 9126.2432)*</span></span>

<span data-ttu-id="44499-1306">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-1306">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="44499-1307">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1307">Office Suite: Non-security updates</span></span>
- <span data-ttu-id="44499-1308">修正設定 API 在某些案例下無法在 Office JavaScript 程式庫運作的問題 [深入了解](https://support.microsoft.com/help/4475551/august-6-2019-update-for-office-2016-kb4475551)</span><span class="sxs-lookup"><span data-stu-id="44499-1308">Fixed an issue in which Setting API doesn't work in the Office JavaScript library in certain scenarios [Learn More](https://support.microsoft.com/help/4475551/august-6-2019-update-for-office-2016-kb4475551)</span></span>


## <a name="version-1902-july-09"></a><span data-ttu-id="44499-1309">版本 1902：7 月 9 日</span><span class="sxs-lookup"><span data-stu-id="44499-1309">Version 1902: July 09</span></span>
<span data-ttu-id="44499-1310">*版本 1902 (組建 11328.20368)*</span><span class="sxs-lookup"><span data-stu-id="44499-1310">*Version 1902 (Build 11328.20368)*</span></span>
<br/><span data-ttu-id="44499-1311">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-1311">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


### <a name="access-feature-updates"></a><span data-ttu-id="44499-1312">Access：功能更新</span><span class="sxs-lookup"><span data-stu-id="44499-1312">Access: Feature updates</span></span>

- <span data-ttu-id="44499-1313">**重新整理、重新連結或移除連結的資料表** 更新的連結資料表管理員是用於管理所有資料來源與連結資料表的位置。</span><span class="sxs-lookup"><span data-stu-id="44499-1313">**Refresh, relink, or remove linked tables:** The updated Linked Table Manager is the location for managing all data sources and linked tables.</span></span> [<span data-ttu-id="44499-1314">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-1314">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)
- <span data-ttu-id="44499-p223">**繪製成黑色、繪製成灰色：** 依照您的喜好變更 Access 的外觀。有四個佈景主題可供選擇：彩色、深灰色、黑色或白色。[深入了解](https://support.office.com/article/9d76a8b4-bfff-48a9-b8c8-8e133461bc94)</span><span class="sxs-lookup"><span data-stu-id="44499-p223">**Paint it black, paint it gray:** Change the look of Access as often as you like. Four themes to choose from: Colorful, Dark Gray, Black, or White. [Learn more](https://support.office.com/article/9d76a8b4-bfff-48a9-b8c8-8e133461bc94)</span></span>
- <span data-ttu-id="44499-1318">**Office 擁有新的外觀：** Office應用程式現在擁有更簡單、更方便使用的現代化圖示，而功能區也更新了視覺效果，能強調顯示 Office 應用程式中的豐富共同作業功能。</span><span class="sxs-lookup"><span data-stu-id="44499-1318">**Office has a new look:**  Office apps now have modern icons that are simpler and more accessible, and the ribbon has updated visuals that highlight the rich collaboration features available in Office apps.</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="44499-1319">Excel：功能更新</span><span class="sxs-lookup"><span data-stu-id="44499-1319">Excel: Feature updates</span></span>

- <span data-ttu-id="44499-1320">**更快速地開始**：新設計的 [開始頁面] 會將您最近開啟的文件放在最前面並置中。</span><span class="sxs-lookup"><span data-stu-id="44499-1320">**Get a faster start** The newly designed Start Page puts your recently opened documents front and center.</span></span> <span data-ttu-id="44499-1321">按幾下便能取得檔案，並從這裡直接開啟 [帳戶] 設定或 [選項]。</span><span class="sxs-lookup"><span data-stu-id="44499-1321">Get to files in fewer clicks, and open Account settings or Options right from here.</span></span>
- <span data-ttu-id="44499-1322">**使用註解共同作業：** 使用內建的回覆方塊試保持試算表中的交談正確。</span><span class="sxs-lookup"><span data-stu-id="44499-1322">**Collaborate with comments:** Keep the conversation going right in your spreadsheet with the built-in reply box.</span></span> [<span data-ttu-id="44499-1323">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-1323">Learn more</span></span>](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)
- <span data-ttu-id="44499-1324">**功能區圖示有了嶄新的外觀：** 別擔心，功能一切如常。</span><span class="sxs-lookup"><span data-stu-id="44499-1324">**Your ribbon icons have a new look:** Don't worry, everything works the same.</span></span> <span data-ttu-id="44499-1325">此外，它們在各種尺寸的螢幕上看起來很棒。</span><span class="sxs-lookup"><span data-stu-id="44499-1325">Plus, they look great on screens of all sizes.</span></span> [<span data-ttu-id="44499-1326">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-1326">Learn more</span></span>](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- <span data-ttu-id="44499-p227">**能在套用篩選時插入 SVG：** Office 使用者現在可以在套用篩選的同時，插入 SVG。[深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="44499-p227">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>
- <span data-ttu-id="44499-p228">**顯示圖片後面的內容：** 將圖片放在工作表中、挑選您的預設，並觀看透明度變更。就這麼簡單！[深入了解](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span><span class="sxs-lookup"><span data-stu-id="44499-p228">**Reveal what's behind a picture:** Put a picture in a worksheet, pick your preset, and watch the transparency change. That's it! [Learn more](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span></span>
- <span data-ttu-id="44499-1332">**呼叫所有「取得與轉換」粉絲：** 如果您經常使用「取得與轉換」，您會很高興知道我們已改善資料行來源範例功能。</span><span class="sxs-lookup"><span data-stu-id="44499-1332">**Calling all Get & Transform fans:** If you use Get & Transform a lot, you'll be happy to know that the Column From Example feature has been improved.</span></span> <span data-ttu-id="44499-1333">此外，也已改善許多連接器。</span><span class="sxs-lookup"><span data-stu-id="44499-1333">And, many connectors have been improved as well.</span></span> [<span data-ttu-id="44499-1334">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-1334">Learn more</span></span>](https://support.office.com/article/ed01ec34-679d-48e7-ba49-bb14c7908f9e)
- <span data-ttu-id="44499-1335">**改善了對高解析度顯示器的支援**：現在，如果您使用多部監視器或筆記型電腦基座，Office 應用程式在每個顯示器上都會順暢清晰地呈現，即使顯示器使用不同的縮放設定亦然。</span><span class="sxs-lookup"><span data-stu-id="44499-1335">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings.</span></span> [<span data-ttu-id="44499-1336">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-1336">Learn more</span></span>](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- <span data-ttu-id="44499-1337">**快速查閱** 我們已加速 VLOOKUP、HLOOKUP 和 MATCH 的計算速度，讓您能更快得到答案。</span><span class="sxs-lookup"><span data-stu-id="44499-1337">**Speedy Lookup** We've turbo-charged your VLOOKUP, HLOOKUP, and MATCH calculations so you can get answers faster.</span></span> [<span data-ttu-id="44499-1338">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-1338">Learn more</span></span>](https://support.office.com/article/60f18521-2589-4734-89dd-ba4ee1f6c000)

### <a name="outlook-feature-updates"></a><span data-ttu-id="44499-1339">Outlook：功能更新</span><span class="sxs-lookup"><span data-stu-id="44499-1339">Outlook: Feature updates</span></span>

- <span data-ttu-id="44499-p232">**使用「大聲朗讀」聆聽您的電子郵件：** Outlook 可以大聲朗讀您的電子郵件，強調所朗讀的文字。若要開啟 [大聲朗讀]，請移至 [輕鬆存取] 設定。[深入了解](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)</span><span class="sxs-lookup"><span data-stu-id="44499-p232">**Use Read Aloud to listen to your email:** Outlook can read your email aloud, highlighting text as it's read. To turn on Read Aloud, go to the Ease of Access settings. [Learn more](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)</span></span>
- <span data-ttu-id="44499-1343">**免用手輸入：** 您有麥克風嗎？</span><span class="sxs-lookup"><span data-stu-id="44499-1343">**Type hands-free:** Got a microphone?</span></span> <span data-ttu-id="44499-1344">按一下 [聽寫] 並看看 Outlook 如何在您說話的同時輸入您說話的內容。</span><span class="sxs-lookup"><span data-stu-id="44499-1344">Click Dictate and watch Outlook type while you talk.</span></span> [<span data-ttu-id="44499-1345">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-1345">Learn more</span></span>](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- <span data-ttu-id="44499-1346">**功能區圖示有了嶄新的外觀：** 別擔心，功能一切如常。</span><span class="sxs-lookup"><span data-stu-id="44499-1346">**Your ribbon icons have a new look:** Don't worry, everything works the same.</span></span> <span data-ttu-id="44499-1347">此外，它們在各種尺寸的螢幕上看起來很棒。</span><span class="sxs-lookup"><span data-stu-id="44499-1347">Plus, they look great on screens of all sizes.</span></span> [<span data-ttu-id="44499-1348">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-1348">Learn more</span></span>](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- <span data-ttu-id="44499-1349">**在經 SMIME 加密和簽署的電子郵件中，預設封鎖外部內容的下載：** 由於 SMIME 通訊協定中存在漏洞，Outlook 將封鎖在已通過 SMIME 加密或簽署的郵件上下載外部內容。</span><span class="sxs-lookup"><span data-stu-id="44499-1349">**Block download of external content by default in SMIME encrypted and signed emails:** Due to a vulnerability in the SMIME protocol - Outlook will block download of external content on messages that have been encrypted or signed over SMIME.</span></span> <span data-ttu-id="44499-1350">使用者無法透過 Outlook UI 的按下動作下載外部內容，藉此防止安全性漏洞。</span><span class="sxs-lookup"><span data-stu-id="44499-1350">Users will not be able to single-click download external content through Outlook UI to protect from the security vulnerability.</span></span> <span data-ttu-id="44499-1351">[選項] 對話方塊中有一個新選項，可讓使用者回復為舊行為。</span><span class="sxs-lookup"><span data-stu-id="44499-1351">There is a new option in the Options dialog to allow for users to revert to old behavior.</span></span>
- <span data-ttu-id="44499-1352">**關閉會議轉寄功能：** 防止出席者將您的會議轉寄給其他人。</span><span class="sxs-lookup"><span data-stu-id="44499-1352">**Turn off forwarding for a meeting:** Prevent attendees from forwarding your meeting to others.</span></span> <span data-ttu-id="44499-1353">只需移至功能區，按一下 [回應選項] 即可。</span><span class="sxs-lookup"><span data-stu-id="44499-1353">Just go to the ribbon and click Response Options.</span></span> [<span data-ttu-id="44499-1354">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-1354">Learn more</span></span>](https://support.office.com/article/5C9877BC-AB91-4A7C-99FB-B0B68D7EA94F)
- <span data-ttu-id="44499-p237">**排程助理員中的人員建議：** 在您排定會議時查看對要新增之出席者的建議。不再來回切換排程助理員與收件者。[深入了解](https://support.office.com/article/d284c6d9-206e-4926-92b4-5addc0fcbefb)</span><span class="sxs-lookup"><span data-stu-id="44499-p237">**People suggestions in the Scheduling Assistant:** See recommendations for attendees to add when you schedule a meeting. No more switching back and forth between the Scheduling Assistant and the To line. [Learn more](https://support.office.com/article/d284c6d9-206e-4926-92b4-5addc0fcbefb)</span></span>
- <span data-ttu-id="44499-1358">**預留房間更加輕鬆：** 使用多個會議室清單尋找會議室 - 以及切換清單，而不會失去您已選取的會議室。</span><span class="sxs-lookup"><span data-stu-id="44499-1358">**Reserving a room just got easier:** Look for a conference room using more than one room list - and switch lists without losing rooms you've selected.</span></span>
- <span data-ttu-id="44499-p238">**循環範圍的新預設值：** 在 [週期設定] 對話方塊中，循環範圍之前的預設值為 [沒有結束日期]。雖然這有助於建立長時間執行的週期性系列，但在一段時間之後可能會發生損壞。我們正將 [週期設定] 對話方塊的預設值更新為 [結束於]，這樣我們的預設值就會符合行事曆操作的建議最佳做法。</span><span class="sxs-lookup"><span data-stu-id="44499-p238">**New default for range of recurrence:** For the Recurrence dialog, the range of recurrence used to default for "No end date". This facilitated the creation of long-running recurring series, which can become corrupted over time. We are updating the default for the Recurrence dialog to "End by", such that our default value matches recommended best practices for calendaring.</span></span>
- <span data-ttu-id="44499-p239">**從 Outlook 提醒對話方塊加入小組會議：** 當 Outlook 提醒使用者有即將來臨的會議時，如果即將來臨的會議是小組線上會議，則它會顯示 [線上加入] 按鈕。這個動作與從 Outlook [提醒] 對話方塊加入商務用 Skype 會議的體驗類似。</span><span class="sxs-lookup"><span data-stu-id="44499-p239">**Join Teams meetings from the Outlook Reminders dialog:** When Outlook reminds users of an upcoming meeting, it will show a Join Online button if the upcoming meeting is a Teams online meeting. This is similar to the experience of joining a Skype for Business meeting from the Outlook Reminders dialog.</span></span>
- <span data-ttu-id="44499-1364">**停止看到過去事件的提醒：** 您可以設定行事曆，以在事件結束之後自動關閉事件的提醒。</span><span class="sxs-lookup"><span data-stu-id="44499-1364">**Stop seeing reminders for past events:** You can set your calendar to automatically dismiss reminders for events after they've ended.</span></span> [<span data-ttu-id="44499-1365">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-1365">Learn more</span></span>](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)
- <span data-ttu-id="44499-1366">**查看安全連結背後的 URL：** 安全連結可保護您防範在電子郵件中收到但隱藏原始 URL 的惡意 URL。</span><span class="sxs-lookup"><span data-stu-id="44499-1366">**See the URL behind Safe Links:** Safe Links protects you from malicious URLS received in email but they hide the original URL.</span></span> <span data-ttu-id="44499-1367">若要查看原始 URL，請將滑鼠游標移到 URL 上。</span><span class="sxs-lookup"><span data-stu-id="44499-1367">To see the original, hover your mouse over the URL.</span></span> <span data-ttu-id="44499-1368">需要進階威脅防護授權。</span><span class="sxs-lookup"><span data-stu-id="44499-1368">Requires an Advanced Threat Protection license.</span></span> [<span data-ttu-id="44499-1369">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-1369">Learn more</span></span>](https://products.office.com/exchange/advance-threat-protection)
- <span data-ttu-id="44499-1370">**縮放與搖桿：** 選擇要用於所有郵件的預設值，而不用在每次讀取郵件時調整 [縮放]。</span><span class="sxs-lookup"><span data-stu-id="44499-1370">**Zoom and stick:** Instead of adjusting Zoom each time you read a message, choose a default to use for all your messages.</span></span> [<span data-ttu-id="44499-1371">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-1371">Learn more</span></span>](https://support.office.com/article/56c090bc-e148-44a7-bd06-1290edd38983)
- <span data-ttu-id="44499-1372">**郵件加密：僅加密 IRM 原則：**[選項] > [權限] 功能表上的全新僅加密選項，供 Office 365 郵件加密使用者使用。</span><span class="sxs-lookup"><span data-stu-id="44499-1372">**Message Encryption: encrypt-only IRM policy:** New encrypt-only option appears in the Options > Permissions menu for Office 365 Message Encryption users.</span></span> <span data-ttu-id="44499-1373">這個選項可讓您加密郵件，並將郵件傳送給組織內外的任何人。</span><span class="sxs-lookup"><span data-stu-id="44499-1373">This option allows you to encrypt a message and send it to anyone, inside or outside your organization.</span></span>
- <span data-ttu-id="44499-1374">**當您被列於密件副本時，顯示提醒：** 當您不小心回覆所有人，而將自己列於密件副本時，密件副本資訊提示會顯示提醒。</span><span class="sxs-lookup"><span data-stu-id="44499-1374">**Warning when you've been BCC'ed:** The BCC infotip will warn you before you accidentally reply all to a mail that you've been blind carbon copied on.</span></span>
- <span data-ttu-id="44499-1375">**更智慧的 [收件者:] 行：** 當您按一下 [收件者:] 行來撰寫郵件時，我們會建議您可能要選擇的收件者。</span><span class="sxs-lookup"><span data-stu-id="44499-1375">**A smarter To: line:** When you click the To: line to address a message, we suggest recipients you're likely to choose.</span></span> <span data-ttu-id="44499-1376">此外，還可以看到收件者的相片，讓您知道要傳送的對象是正確的。</span><span class="sxs-lookup"><span data-stu-id="44499-1376">Plus, you can see their picture, so you know yo're sending to the right person.</span></span> [<span data-ttu-id="44499-1377">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-1377">Learn more</span></span>](https://support.office.com/article/147208AF-CA8E-4CDF-B71F-77BA81A54069)
- <span data-ttu-id="44499-p245">**能在套用篩選時插入 SVG：** Office 使用者現在可以在套用篩選的同時，插入 SVG。[深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="44499-p245">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>
- <span data-ttu-id="44499-1380">**改善了對高解析度顯示器的支援**：現在，如果您使用多部監視器或筆記型電腦基座，Office 應用程式在每個顯示器上都會順暢清晰地呈現，即使顯示器使用不同的縮放設定亦然。</span><span class="sxs-lookup"><span data-stu-id="44499-1380">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings.</span></span> [<span data-ttu-id="44499-1381">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-1381">Learn more</span></span>](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="44499-1382">PowerPoint：功能更新</span><span class="sxs-lookup"><span data-stu-id="44499-1382">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="44499-1383">**更快速地開始**：新設計的 [開始頁面] 會將您最近開啟的文件放在最前面並置中。</span><span class="sxs-lookup"><span data-stu-id="44499-1383">**Get a faster start** The newly designed Start Page puts your recently opened documents front and center.</span></span> <span data-ttu-id="44499-1384">按幾下便能取得檔案，並從這裡直接開啟 [帳戶] 設定或 [選項]。</span><span class="sxs-lookup"><span data-stu-id="44499-1384">Get to files in fewer clicks, and open Account settings or Options right from here.</span></span>
- <span data-ttu-id="44499-1385">**免用手輸入：** 您有麥克風嗎？</span><span class="sxs-lookup"><span data-stu-id="44499-1385">**Type hands-free:** Got a microphone?</span></span> <span data-ttu-id="44499-1386">按一下 [聽寫] 並看看 PowerPoint 如何在您說話的同時輸入您說話的內容。</span><span class="sxs-lookup"><span data-stu-id="44499-1386">Click Dictate and watch PowerPoint type while you talk.</span></span> [<span data-ttu-id="44499-1387">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-1387">Learn more</span></span>](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- <span data-ttu-id="44499-1388">**功能區圖示有了嶄新的外觀：** 別擔心，功能一切如常。</span><span class="sxs-lookup"><span data-stu-id="44499-1388">**Your ribbon icons have a new look:** Don't worry, everything works the same.</span></span> <span data-ttu-id="44499-1389">此外，它們在各種尺寸的螢幕上看起來很棒。</span><span class="sxs-lookup"><span data-stu-id="44499-1389">Plus, they look great on screens of all sizes.</span></span> [<span data-ttu-id="44499-1390">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-1390">Learn more</span></span>](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- <span data-ttu-id="44499-1391">**改善了對高解析度顯示器的支援**：現在，如果您使用多部監視器或筆記型電腦基座，Office 應用程式在每個顯示器上都會順暢清晰地呈現，即使顯示器使用不同的縮放設定亦然。</span><span class="sxs-lookup"><span data-stu-id="44499-1391">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings.</span></span> [<span data-ttu-id="44499-1392">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-1392">Learn more</span></span>](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- <span data-ttu-id="44499-1393">**色彩生動的超連結：** 超連結不再只是藍色的。</span><span class="sxs-lookup"><span data-stu-id="44499-1393">**Hyperlinks in living color:** Hyperlinks aren't just blue anymore.</span></span> <span data-ttu-id="44499-1394">您可以套用您喜歡的任何字型色彩。</span><span class="sxs-lookup"><span data-stu-id="44499-1394">Apply any font color you like.</span></span> [<span data-ttu-id="44499-1395">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-1395">Learn more</span></span>](https://support.office.com/article/988ed94c-82e9-4e2c-96a1-7ffd2c382ce8)
- <span data-ttu-id="44499-1396">**生動地觀看您的投影片：** 插入動畫 3D 圖形，來查看心跳、行星軌道，以及暴龍在整個畫面橫衝直撞。</span><span class="sxs-lookup"><span data-stu-id="44499-1396">**Watch your slides come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage across the screen.</span></span> [<span data-ttu-id="44499-1397">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-1397">Learn more</span></span>](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)
- <span data-ttu-id="44499-p253">**您素描，我修飾：** 我們可將手繪文字和形狀變為更精緻的圖表。只需選取您的筆跡線條即可開始。[深入了解](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="44499-p253">**You sketch, we polish:** We change hand-drawn text and shapes into refined diagrams. Just select your ink strokes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>
- <span data-ttu-id="44499-p254">**顯示圖片後面的內容：** 將圖片放在工作表中、挑選您的預設，並觀看透明度變更。就這麼簡單！[深入了解](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span><span class="sxs-lookup"><span data-stu-id="44499-p254">**Reveal what's behind a picture:** Put a picture in a worksheet, pick your preset, and watch the transparency change. That's it! [Learn more](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span></span>
- <span data-ttu-id="44499-1404">**發佈到 Microsoft Stream：** 透過使用 Microsoft Stream，在組織內更安全地以影片形式共用簡報。</span><span class="sxs-lookup"><span data-stu-id="44499-1404">**Publish to Microsoft Stream:** Share a presentation as a video more securely within your organization by using Microsoft Stream.</span></span> [<span data-ttu-id="44499-1405">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-1405">Learn more</span></span>](https://support.office.com/article/C140551F-CB37-4818-B5D4-3E30815C3E83)
- <span data-ttu-id="44499-1406">**匯出為 4K 影片：** 您現在可以在將簡報匯出為影片時選取 4K 解析度。</span><span class="sxs-lookup"><span data-stu-id="44499-1406">**Export to 4K video:** When you export a presentation to video, 4K resolution is now an option.</span></span>  [<span data-ttu-id="44499-1407">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-1407">Learn more</span></span>](https://support.office.com/article/c140551f-cb37-4818-b5d4-3e30815c3e83)
- <span data-ttu-id="44499-p257">**能在套用篩選時插入 SVG：** Office 使用者現在可以在套用篩選的同時，插入 SVG。[深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="44499-p257">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>
- <span data-ttu-id="44499-1410">**大型檔案現在會以更快速度開啟：** 現在開啟儲存在 OneDrive 或 SharePoint 上的檔案時，會在背景下載影像、影片及其他大型元素。</span><span class="sxs-lookup"><span data-stu-id="44499-1410">**Large files now open faster:** Images, videos, and other large elements now download in the background when opening files stored on OneDrive or SharePoint.</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="44499-1411">Word：功能更新</span><span class="sxs-lookup"><span data-stu-id="44499-1411">Word: Feature updates</span></span>

- <span data-ttu-id="44499-1412">**更快速地開始**：新設計的 [開始頁面] 會將您最近開啟的文件放在最前面並置中。</span><span class="sxs-lookup"><span data-stu-id="44499-1412">**Get a faster start** The newly designed Start Page puts your recently opened documents front and center.</span></span> <span data-ttu-id="44499-1413">按幾下便能取得檔案，並從這裡直接開啟 [帳戶] 設定或 [選項]。</span><span class="sxs-lookup"><span data-stu-id="44499-1413">Get to files in fewer clicks, and open Account settings or Options right from here.</span></span>
- <span data-ttu-id="44499-1414">**免用手輸入：** 您有麥克風嗎？</span><span class="sxs-lookup"><span data-stu-id="44499-1414">**Type hands-free:** Got a microphone?</span></span> <span data-ttu-id="44499-1415">按一下 [聽寫] 並看看 Word 如何在您說話的同時輸入您說話的內容。</span><span class="sxs-lookup"><span data-stu-id="44499-1415">Click Dictate and watch Word type while you talk.</span></span> [<span data-ttu-id="44499-1416">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-1416">Learn more</span></span>](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- <span data-ttu-id="44499-p260">**生動地觀看您的文件：** 插入動畫 3D 圖形，來查看心跳、行星軌道，以及暴龍在整個頁面橫衝直撞。[深入了解](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)</span><span class="sxs-lookup"><span data-stu-id="44499-p260">**Watch your documents come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage across the page. [Learn more](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)</span></span>
- <span data-ttu-id="44499-1419">**功能區圖示有了嶄新的外觀：** 別擔心，功能一切如常。</span><span class="sxs-lookup"><span data-stu-id="44499-1419">**Your ribbon icons have a new look:** Don't worry, everything works the same.</span></span> <span data-ttu-id="44499-1420">此外，它們在各種尺寸的螢幕上看起來很棒。</span><span class="sxs-lookup"><span data-stu-id="44499-1420">Plus, they look great on screens of all sizes.</span></span> [<span data-ttu-id="44499-1421">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-1421">Learn more</span></span>](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- <span data-ttu-id="44499-p262">**顯示圖片後面的內容：** 將圖片放在工作表中、挑選您的預設，並觀看透明度變更。就這麼簡單！[深入了解](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span><span class="sxs-lookup"><span data-stu-id="44499-p262">**Reveal what's behind a picture:** Put a picture in a worksheet, pick your preset, and watch the transparency change. That's it! [Learn more](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span></span>
- <span data-ttu-id="44499-p263">**能在套用篩選時插入 SVG：** Office 使用者現在可以在套用篩選的同時，插入 SVG。[深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="44499-p263">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>
- <span data-ttu-id="44499-1427">**改善了對高解析度顯示器的支援**：現在，如果您使用多部監視器或筆記型電腦基座，Office 應用程式在每個顯示器上都會順暢清晰地呈現，即使顯示器使用不同的縮放設定亦然。</span><span class="sxs-lookup"><span data-stu-id="44499-1427">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings.</span></span> [<span data-ttu-id="44499-1428">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-1428">Learn more</span></span>](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- <span data-ttu-id="44499-p265">**利用 LinkedIn 的協助撰寫最佳簡歷或履歷表：** 利用簡歷小幫手，查看特定角色的工作經驗、建議的技能以及其他資訊。 [深入了解](https://support.office.com/article/444ff6f0-ef74-4a9c-9091-ffd7a9d1917a)</span><span class="sxs-lookup"><span data-stu-id="44499-p265">**Write your best resume or CV with help from LinkedIn:** With Resume Assistant, see work experiences, suggested skills, and more for a given role. [Learn more](https://support.office.com/article/444ff6f0-ef74-4a9c-9091-ffd7a9d1917a)</span></span>

### <a name="project-feature-updates"></a><span data-ttu-id="44499-1431">Project：功能更新</span><span class="sxs-lookup"><span data-stu-id="44499-1431">Project: Feature updates</span></span>

- <span data-ttu-id="44499-1432">**在任務面板卡片上查看詳細資訊：** 當標題本身無法陳述完整故事時，請自訂您的任務面板卡片，以顯示所有最重要的詳細資料。</span><span class="sxs-lookup"><span data-stu-id="44499-1432">**See more info on Task Board cards:** When the title alone doesn't tell the story, customize your Task Board cards to show all the most important details.</span></span> [<span data-ttu-id="44499-1433">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-1433">Learn more</span></span>](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)
- <span data-ttu-id="44499-1434">**Office 擁有新的外觀：** Office應用程式現在擁有更簡單、更方便使用的現代化圖示，而功能區也更新了視覺效果，能強調顯示 Office 應用程式中的豐富共同作業功能。</span><span class="sxs-lookup"><span data-stu-id="44499-1434">**Office has a new look:**  Office apps now have modern icons that are simpler and more accessible, and the ribbon has updated visuals that highlight the rich collaboration features available in Office apps.</span></span>

### <a name="publisher-feature-updates"></a><span data-ttu-id="44499-1435">Publisher：功能更新</span><span class="sxs-lookup"><span data-stu-id="44499-1435">Publisher: Feature updates</span></span>

- <span data-ttu-id="44499-1436">**Office 擁有新的外觀：** Office應用程式現在擁有更簡單、更方便使用的現代化圖示，而功能區也更新了視覺效果，能強調顯示 Office 應用程式中的豐富共同作業功能。</span><span class="sxs-lookup"><span data-stu-id="44499-1436">**Office has a new look:**  Office apps now have modern icons that are simpler and more accessible, and the ribbon has updated visuals that highlight the rich collaboration features available in Office apps.</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="44499-1437">Visio：功能更新</span><span class="sxs-lookup"><span data-stu-id="44499-1437">Visio: Feature updates</span></span>

- <span data-ttu-id="44499-1438">**在下一個圖表中享受圖示時刻：** 有 26 個全新的圖示樣板供您挑選，其中包含分析、藝術、慶典、臉部、運動和其他圖示。</span><span class="sxs-lookup"><span data-stu-id="44499-1438">**Enjoy an iconic moment in your next diagram:** Pick from 26 new stencils with icons for analytics, arts, celebration, faces, sports, and more.</span></span>
- <span data-ttu-id="44499-1439">**Office 擁有新的外觀：** Office應用程式現在擁有更簡單、更方便使用的現代化圖示，而功能區也更新了視覺效果，能強調顯示 Office 應用程式中的豐富共同作業功能。</span><span class="sxs-lookup"><span data-stu-id="44499-1439">**Office has a new look:**  Office apps now have modern icons that are simpler and more accessible, and the ribbon has updated visuals that highlight the rich collaboration features available in Office apps.</span></span>

### <a name="office-suite-feature-updates"></a><span data-ttu-id="44499-1440">Office 套件：功能更新</span><span class="sxs-lookup"><span data-stu-id="44499-1440">Office Suite: Feature updates</span></span>

- <span data-ttu-id="44499-p267">**Office 第三方應用程式現在已使用 office.js api 擁有插入 SVG 支援的功能：** 亦稱為 Office 增益集的第三方應用程式現在擁有插入 SVG 的功能。使用者現在可以將個人的 SVG 集合連線至 Office。開發人員現在可以使用 Office.js API 來使用這項功能。</span><span class="sxs-lookup"><span data-stu-id="44499-p267">**Office 3rd Party Applications now have insert SVG support using the office.js api:** 3rd party applications also known as add-ins in Office now have the ability to insert SVG's. Users can now connect their personal collection of SVG's to Office. Developers can use this feature by using the Office.js API.</span></span>
- <span data-ttu-id="44499-1444">**安裝 Microsoft Teams：** 在 Office 365 專業增強版的新安裝中，預設會安裝 Microsoft Teams。</span><span class="sxs-lookup"><span data-stu-id="44499-1444">**Installation of Microsoft Teams:**  Microsoft Teams is installed by default for NEW installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="44499-1445">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-1445">Learn more</span></span>](/DeployOffice/teams-install)

### <a name="skype-for-business-feature-updates"></a><span data-ttu-id="44499-1446">商務用 Skype：功能更新</span><span class="sxs-lookup"><span data-stu-id="44499-1446">Skype for Business: Feature updates</span></span>

- <span data-ttu-id="44499-1447">**改善了對高解析度顯示器的支援**：現在，如果您使用多部監視器或筆記型電腦基座，Office 應用程式在每個顯示器上都會順暢清晰地呈現，即使顯示器使用不同的縮放設定亦然。</span><span class="sxs-lookup"><span data-stu-id="44499-1447">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings.</span></span> [<span data-ttu-id="44499-1448">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-1448">Learn more</span></span>](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)


### <a name="excel-non-security-updates"></a><span data-ttu-id="44499-1449">Excel：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1449">Excel: Non-security updates</span></span>

- <span data-ttu-id="44499-1450">已解決將包含 XML 對應的檔案儲存為 PDF 時導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1450">Resolved an issue that caused a crash when saving a file containing an XML map to PDF.</span></span>
- <span data-ttu-id="44499-1451">已解決在載入包含無效工作表名稱之活頁簿時，導致外部連結遭到刪除的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1451">Resolved an issue that caused external links to be removed when workbooks containing invalid sheet names are loaded.</span></span>
- <span data-ttu-id="44499-1452">已修正在 Excel 中使用相機工具可能會造成試算表當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1452">Fixed an issue where using the Camera tool in Excel could cause the spreadsheet to hang.</span></span>
- <span data-ttu-id="44499-1453">已解決當插入或刪除儲存格時，瀑布圖和漏斗圖無法與表格同步處理的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1453">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>
- <span data-ttu-id="44499-1454">已解決在工作表計算期間，使用依賴表格之另一個工作表上的陣列公式重新計算資料表格的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1454">Resolved an issue when a data table is recalculated during Worksheet Calculate with an array formula on another sheet depending on the table.</span></span> 
- <span data-ttu-id="44499-1455">已解決未先簽出檔案，無法從 SharePoint 開啟受密碼保護的活頁簿的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1455">Resolved an issue that prevented password protected workbooks from being opened from SharePoint without checking out file first.</span></span>
- <span data-ttu-id="44499-1456">已進行變更，確保在共用或切換自動儲存時，處理 BeforeSave 事件。</span><span class="sxs-lookup"><span data-stu-id="44499-1456">A change was made to ensure the BeforeSave event is handled when sharing or toggling AutoSave.</span></span> 
- <span data-ttu-id="44499-1457">已修正在帶有圖表工作表的非使用中視窗中使用滑鼠滾輪的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1457">An issue using the mouse scroll wheel on an in-active window with a chart sheet was fixed.</span></span>
- <span data-ttu-id="44499-1458">已解決將試算表匯入 SharePoint 時發生「未預期錯誤」訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1458">A problem that caused an "Unexpected Error" message to appear when importing a spreadsheet in SharePoint has been resolved.</span></span>
- <span data-ttu-id="44499-1459">已解決在開啟包含使用其規則名稱和自訂檢視的條件式格式設定的活頁簿的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1459">A problem that opening a workbook containing conditional formatting that uses a Name for its rule and a custom view is applied has been resolved.</span></span>
- <span data-ttu-id="44499-1460">巨集用於驗證資料的公式若長於 255 個字元可能會產生執行階段錯誤。</span><span class="sxs-lookup"><span data-stu-id="44499-1460">Macros using data validation with formulas longer than 255 characters may have produced run-time errors.</span></span> <span data-ttu-id="44499-1461">此問題現已修正。</span><span class="sxs-lookup"><span data-stu-id="44499-1461">This issue has now been corrected.</span></span>
- <span data-ttu-id="44499-1462">發生問題，導致包含連結至其他活頁簿之樞紐分析表的檔案載入速度緩慢。</span><span class="sxs-lookup"><span data-stu-id="44499-1462">A problem which caused files containing PivotTables linked to other workbooks to load slowly.</span></span> <span data-ttu-id="44499-1463">此問題已解決。</span><span class="sxs-lookup"><span data-stu-id="44499-1463">This issue has been resolved.</span></span>
- <span data-ttu-id="44499-1464">開啟 HTML 檔案時收到「檔案格式與副檔名不符」錯誤的問題已解決。</span><span class="sxs-lookup"><span data-stu-id="44499-1464">An issue with opening HTML files and receiving a "file format and extension do not match" error has been resolved.</span></span>
- <span data-ttu-id="44499-1465">已進行變更，以解決在非使用中視窗滾動滑鼠滾輪的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1465">A change has been made to resolve issues with mouse-wheel scrolling on inactive windows.</span></span>
- <span data-ttu-id="44499-1466">解決了當儲存格中包含的公式結尾為定義的名稱時，按下 Tab 鍵不會移至下一個儲存格的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1466">Resolved an issue where pressing the Tab key would not move to the next cell when in a cell containing a formula ending in a defined name.</span></span>
- <span data-ttu-id="44499-1467">解決了儲存格格式設定導致檔案大小不必要地增加的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1467">Resolved an issue where cell formatting was causing the file size to grow unnecessarily.</span></span>
- <span data-ttu-id="44499-1468">解決了在活頁簿之間剪下並貼上樞紐分析表可能導致貼上資料，但沒有您正與其共同作業的其他人的樞紐分析表的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1468">Resolved an issue where cutting and pasting a PivotTable between workbooks may result in the data being pasted, without a PivotTable for others you are collaborating with.</span></span>


### <a name="outlook-non-security-updates"></a><span data-ttu-id="44499-1469">Outlook：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1469">Outlook: Non-security updates</span></span>

- <span data-ttu-id="44499-1470">已解決在「群組依據」中新增第二個條件後，客戶的工作似乎會消失的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1470">Addressed an issue that caused customers to see their tasks seem to disappear when adding a 2nd condition to "Group by".</span></span>
- <span data-ttu-id="44499-1471">解決了造成客戶無法編輯所移轉項目上某些欄位的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1471">Addresses an issue that caused customers to be unable to edit some fields on items that had been migrated.</span></span>
- <span data-ttu-id="44499-1472">已修正當系統工作列停留在螢幕左側或頂部時，視窗無法顯示在正確位置的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1472">Fixed an issue in which windows would not appear in the correct location when the system task bar was kept at the left or top of the screen.</span></span>
- <span data-ttu-id="44499-1473">解決了在連絡人卡片上載入圖片時導致客戶遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1473">Addresses an issue that caused customers to experience a crash when loading pictures on the contact card.</span></span>
- <span data-ttu-id="44499-1474">解決了導致某些客戶在啟動 Office 應用程式時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1474">Addresses an issue that caused some customers to experience crashes when starting office applications.</span></span>
- <span data-ttu-id="44499-1475">已修正當系統工作列停留在螢幕左側或頂部時，視窗無法顯示在正確位置的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1475">Fixed an issue in which windows would not appear in the correct location when the system task bar was kept at the left or top of the screen.</span></span>
- <span data-ttu-id="44499-1476">解決了造成客戶無法編輯所移轉項目上某些欄位的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1476">Addresses an issue that caused customers to be unable to edit some fields on items that had been migrated.</span></span>


### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="44499-1477">PowerPoint：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1477">PowerPoint: Non-Security updates</span></span>

- <span data-ttu-id="44499-1478">已修正在罕見的情況下，PowerPoint 停止將使用者的變更上傳到雲端的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1478">Fixed an issue that PowerPoint stops uploading user changes to the cloud in rare situations.</span></span>


### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="44499-1479">商務用 Skype：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1479">Skype for Business: Non-security updates</span></span>

- <span data-ttu-id="44499-1480">已修正 Lync (商務用 Skype) 中的問題，在其中，當任何線上會議具有 7 位以上參與者時，會議視窗可能會消失。</span><span class="sxs-lookup"><span data-stu-id="44499-1480">Fixed an issue in Lync (Skype for Business) where for any online meeting with more 7+ participants, the meeting window can disappear.</span></span>
- <span data-ttu-id="44499-1481">使用用來登入其他 Office 應用程式的認證來登入商務用 Skype。</span><span class="sxs-lookup"><span data-stu-id="44499-1481">Sign into Skype for Business with credentials used to sign into another Office application.</span></span>
- <span data-ttu-id="44499-1482">隨著共用電腦啟用安裝時，正確地啟用商務用 Skype 應用程式。</span><span class="sxs-lookup"><span data-stu-id="44499-1482">Properly activate the Skype for Business app when installed with shared computer activation.</span></span>


### <a name="visio-non-security-updates"></a><span data-ttu-id="44499-1483">Visio：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1483">Visio: Non-security updates</span></span>

- <span data-ttu-id="44499-1484">已修正第三方解決方案利用停用動態 DPI 功能來擴充 Visio，造成損毀視窗階層問題的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1484">Fixed an issue which was causing broken window hierarchy issues for 3rd party solutions extending Visio by disabling Dynamic DPI feature.</span></span>


### <a name="word-non-security-updates"></a><span data-ttu-id="44499-1485">Word：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1485">Word: Non-security updates</span></span>

 - <span data-ttu-id="44499-1486">已修正以下問題：共用目前正在共同作業的文件時，會產生具 .asd 副檔名的附件。</span><span class="sxs-lookup"><span data-stu-id="44499-1486">Fixed when sharing a document which is currently being collaborated upon the document produces attachment with .asd extension.</span></span>
 - <span data-ttu-id="44499-1487">已修正註解被歸因於隨機作者的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1487">Fixed an issue with comments get attributed to random authors.</span></span>
 - <span data-ttu-id="44499-1488">已修正在簽出文件時，簽章遭到移除的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1488">Fixed an issue in the remove signature when checking out a document.</span></span>
 - <span data-ttu-id="44499-1489">已修正編輯 SharePoint 新增的相關人員可能會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1489">Fixed an issue where editing a Related Person added by SharePoint could crash.</span></span>
 - <span data-ttu-id="44499-1490">已修正 Word 啟動時出現的「無法載入資源」對話方塊。</span><span class="sxs-lookup"><span data-stu-id="44499-1490">Fixed where the "Failed to load resource" dialog when Word launches.</span></span>
 - <span data-ttu-id="44499-1491">如果檔案以唯讀模式開啟，然後您從 [資訊] 窗格中按一下 [另存新檔]，修正問題以便顯示儲存 UI。</span><span class="sxs-lookup"><span data-stu-id="44499-1491">If a file is opened in read-only mode and you click 'Save As' from the 'Info' pane, fixes issue so that the save UI is displayed.</span></span>


### <a name="office-suite-non-security-updates"></a><span data-ttu-id="44499-1492">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1492">Office Suite: Non-security updates</span></span>

 - <span data-ttu-id="44499-1493">此修正在「復原」動作後，VBA 報告不正確的圖案填滿狀態的錯誤。</span><span class="sxs-lookup"><span data-stu-id="44499-1493">This fixed a bug in VBA reporting incorrect shape fill state after an "undo" action.</span></span>
 - <span data-ttu-id="44499-1494">此修正程式可修正無法將檔案儲存到 Apache WebDAV 資料夾的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1494">This is a fix for an issue where files cannot be saved to Apache WebDAV folders.</span></span>
 - <span data-ttu-id="44499-1495">修正 Office 在客戶開啟某些雲端儲存檔案時會意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1495">Fixes an issue where Office closes abruptly when customers open some cloud-stored files.</span></span>
 - <span data-ttu-id="44499-1496">已修正不正確地將平假名和漢字中的日本新年號 "Reiwa" (令和) 識別為拼字錯誤或不合文法表達的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1496">Fixed an issue of incorrectly identifying the new era name "Reiwa" in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>
 - <span data-ttu-id="44499-1497">已修正似乎為 Windows 10 上的許多使用者清除最近使用的檔案清單的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1497">Fixed an issue where the recent files list appeared to have been cleared for many users on Windows 10.</span></span>
 - <span data-ttu-id="44499-1498">已修正即使已有系統管理員觸發的更新進行中，仍導致使用者看到 Office 更新業務列的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1498">Fixed an issue that caused an end-user to see an Office Update business bar, even though there is an Admin-triggered update in progress.</span></span>
 - <span data-ttu-id="44499-1499">已修正與間歇性的空白登入提示相關的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1499">Fixed an issues related to intermittent blank sign-in prompts.</span></span>
 - <span data-ttu-id="44499-1500">已修正部分 Office 更新未使用傳遞最佳化對等快取的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1500">Fixed an issue where parts of an Office update do not use Delivery Optimization peer caching.</span></span> [<span data-ttu-id="44499-1501">深入了解</span><span class="sxs-lookup"><span data-stu-id="44499-1501">Learn more</span></span>](/windows/deployment/update/waas-delivery-optimization)
- <span data-ttu-id="44499-1502">修正如果使用 Office 部署工具安裝 Office，並發生大小寫不相符時，可能導致移除產品或未啟用的錯誤。</span><span class="sxs-lookup"><span data-stu-id="44499-1502">Fix to a bug that could lead to products being removed or not activated if Office was installed using the Office Deployment Tool and there was a case mis-match.</span></span>
- <span data-ttu-id="44499-1503">已修正導致 Windows 10 (版本 1803 或更高版本) 裝置上出現過多登入提示的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1503">Fixed an issue which was causing excessive sign-in prompts on Windows 10 (version 1803 or later) devices.</span></span>
- <span data-ttu-id="44499-1504">已修正下載連結圖片時，造成懸置的迴歸。</span><span class="sxs-lookup"><span data-stu-id="44499-1504">Fixed regression that causes hangs when downloading linked pictures.</span></span>
- <span data-ttu-id="44499-1505">已修正在 Word、Excel、PowerPoint 貼上大型 EMF 檔案的模糊問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1505">Fixed blurriness of large EMF files pasted in Word, Excel, PowerPoint.</span></span>
- <span data-ttu-id="44499-1506">已修正版本歷程記錄剖析邏輯時，在少數情況下導致文件以唯讀模式開啟的錯誤 (bug)。</span><span class="sxs-lookup"><span data-stu-id="44499-1506">Fixed the bug in version history parsing logic that in few cases caused the documents to be opened in read-only.</span></span>


## <a name="version-1808-july-09"></a><span data-ttu-id="44499-1507">版本 1808：7 月 9 日</span><span class="sxs-lookup"><span data-stu-id="44499-1507">Version 1808: July 09</span></span>
<span data-ttu-id="44499-1508">*版本 1808 (組建 10730.20360)*</span><span class="sxs-lookup"><span data-stu-id="44499-1508">*Version 1808 (Build 10730.20360)*</span></span>
<br/><span data-ttu-id="44499-1509">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-1509">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


### <a name="word-non-security-updates"></a><span data-ttu-id="44499-1510">Word：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1510">Word: Non-Security updates</span></span>

- <span data-ttu-id="44499-1511">已改善啟用快速組件文件摘要資訊時的效能。</span><span class="sxs-lookup"><span data-stu-id="44499-1511">Improved performance when enabling Quick Parts for Document properties.</span></span>
- <span data-ttu-id="44499-1512">已修正在簽出檔案時，簽章遭到移除的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1512">Fixed an issue about remove signature when checking out a file.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="44499-1513">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1513">Office Suite: Non-Security updates</span></span>

- <span data-ttu-id="44499-1514">已修正會影響在虛擬化 Windows 上執行 Office 應用程式的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1514">Fixed an issue affecting Office applications running on virtualized Windows.</span></span>


## <a name="version-1803-july-09"></a><span data-ttu-id="44499-1515">版本 1803：7 月 9 日</span><span class="sxs-lookup"><span data-stu-id="44499-1515">Version 1803: July 09</span></span>
<span data-ttu-id="44499-1516">*版本 1803 (組建 9126.2428)*</span><span class="sxs-lookup"><span data-stu-id="44499-1516">*Version 1803 (Build 9126.2428)*</span></span>
<br/><span data-ttu-id="44499-1517">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-1517">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


## <a name="version-1808-june-11"></a><span data-ttu-id="44499-1518">版本 1808：6 月 11 日</span><span class="sxs-lookup"><span data-stu-id="44499-1518">Version 1808: June 11</span></span>
<span data-ttu-id="44499-1519">*版本 1808 (組建 10730.20348)*</span><span class="sxs-lookup"><span data-stu-id="44499-1519">*Version 1808 (Build 10730.20348)*</span></span>
<br/><span data-ttu-id="44499-1520">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-1520">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="44499-1521">Word：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1521">Word: Non-Security updates</span></span>
 - <span data-ttu-id="44499-1522">已修正在簽出檔案時，簽章遭到移除的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1522">Fixed an issue about remove signature when checking out a file.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="44499-1523">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1523">Office Suite: Non-security updates</span></span>
 - <span data-ttu-id="44499-1524">已修正在虛擬化 Windows 上執行 Office 應用程式可能會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1524">Fixed an issue that could crash Office applications running on virtualized Windows.</span></span>

## <a name="version-1803-june-11"></a><span data-ttu-id="44499-1525">版本 1803：6 月 11 日</span><span class="sxs-lookup"><span data-stu-id="44499-1525">Version 1803: June 11</span></span>
<span data-ttu-id="44499-1526">*版本 1803 (組建 9126.2388)*</span><span class="sxs-lookup"><span data-stu-id="44499-1526">*Version 1803 (Build 9126.2388)*</span></span>
<br/><span data-ttu-id="44499-1527">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-1527">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span> 

## <a name="version-1808-may-14"></a><span data-ttu-id="44499-1528">版本 1808：5 月 14 日</span><span class="sxs-lookup"><span data-stu-id="44499-1528">Version 1808: May 14</span></span>
<span data-ttu-id="44499-1529">*版本 1808 (組建 10730.20344)*</span><span class="sxs-lookup"><span data-stu-id="44499-1529">*Version 1808 (Build 10730.20344)*</span></span>   

### <a name="outlook-non-security-updates"></a><span data-ttu-id="44499-1530">Outlook：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1530">Outlook: Non-security updates</span></span>
 - <span data-ttu-id="44499-1531">解決了造成客戶無法編輯所移轉項目上某些欄位的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1531">Addresses an issue that caused customers to be unable to edit some fields on items that had been migrated.</span></span>

### <a name="visio-non-security-updates"></a><span data-ttu-id="44499-1532">Visio：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1532">Visio: Non-security updates</span></span>
 - <span data-ttu-id="44499-1533">已修正第三方解決方案利用停用動態 DPI 功能來擴充 Visio，造成損毀視窗階層問題的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1533">Fixed an issue which was causing broken window hierarchy issues for 3rd party solutions extending Visio by disabling Dynamic DPI feature.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="44499-1534">Word：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1534">Word: Non-Security updates</span></span>
 - <span data-ttu-id="44499-1535">已修正編輯 SharePoint 新增的相關人員可能會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1535">Fixed an issue where editing a Related Person added by SharePoint could crash.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="44499-1536">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1536">Office Suite: Non-security updates</span></span>
 - <span data-ttu-id="44499-1537">已修正不正確地將平假名和漢字中的日本新年號 "Reiwa" (令和) 識別為拼字錯誤或不合文法表達的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1537">Fixed an issue of incorrectly identifying the new era name "Reiwa" in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>
  
## <a name="version-1803-may-14"></a><span data-ttu-id="44499-1538">版本 1803：5 月 14 日</span><span class="sxs-lookup"><span data-stu-id="44499-1538">Version 1803: May 14</span></span>
<span data-ttu-id="44499-1539">*版本 1803 (組建 9126.2387)*</span><span class="sxs-lookup"><span data-stu-id="44499-1539">*Version 1803 (Build 9126.2387)*</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="44499-1540">Outlook：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1540">Outlook: Non-security updates</span></span>
 - <span data-ttu-id="44499-1541">解決了造成客戶無法編輯所移轉項目上某些欄位的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1541">Addresses an issue that caused customers to be unable to edit some fields on items that had been migrated.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="44499-1542">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1542">Office Suite: Non-security updates</span></span>
 - <span data-ttu-id="44499-1543">已修正不正確地將平假名和漢字中的日本新年號 "Reiwa" (令和) 識別為拼字錯誤或不合文法表達的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1543">Fixed an issue of incorrectly identifying the new era name "Reiwa" in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

## <a name="version-1808-april-9"></a><span data-ttu-id="44499-1544">版本 1808：4 月 9 日</span><span class="sxs-lookup"><span data-stu-id="44499-1544">Version 1808: April 9</span></span>
<span data-ttu-id="44499-1545">*版本 1808 (組建 10730.20334)*</span><span class="sxs-lookup"><span data-stu-id="44499-1545">*Version 1808 (Build 10730.20334)*</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="44499-1546">商務用 Skype：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1546">Skype for Business: Non-security updates</span></span>
- <span data-ttu-id="44499-1547">已修正 Lync (商務用 Skype) 中的問題，在其中，當任何線上會議具有 7 位以上參與者時，會議視窗可能會消失。</span><span class="sxs-lookup"><span data-stu-id="44499-1547">Fixed an issue in Lync (Skype for Business) where for any online meeting with more 7+ participants, the meeting window can disappear.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="44499-1548">Word：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1548">Word: Non-Security updates</span></span>

- <span data-ttu-id="44499-1549">已修正使用者可在 IE 或 Edge 以匿名方式開啟文件的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1549">Fixed an issue where the user can open documents anonymously in IE or Edge.</span></span>
- <span data-ttu-id="44499-1550">已修正問題：將文字強調顯示色彩格式設定套用至任何 Word 文檔頁首/頁腳 PAGE 和/或 NUMPAGES 功能變數後，將欄位呈現為黑色而不是套用的文字強調顯示色彩。</span><span class="sxs-lookup"><span data-stu-id="44499-1550">Fixed an issue where text highlight color formatting applied to any Word document header/footer PAGE and/or NUMPAGES field renders the field as black instead of the applied text highlight color.</span></span>
- <span data-ttu-id="44499-1551">我們為日本新時代新增了 Word 日語明信片精靈增益集的支援。</span><span class="sxs-lookup"><span data-stu-id="44499-1551">We added support to Word Japanese postcard wizard add-in for the Japanese new era.</span></span> 

## <a name="version-1803-april-9"></a><span data-ttu-id="44499-1552">版本 1803：4 月 9 日</span><span class="sxs-lookup"><span data-stu-id="44499-1552">Version 1803: April 9</span></span>
- <span data-ttu-id="44499-1553">安全性更新列於[此處](microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-1553">Security updates listed [here](microsoft365-apps-security-updates.md)</span></span>

## <a name="version-1808-march-12"></a><span data-ttu-id="44499-1554">版本 1808：3 月 12 日</span><span class="sxs-lookup"><span data-stu-id="44499-1554">Version 1808: March 12</span></span>
<span data-ttu-id="44499-1555">*版本 1808 (組建 10730.20304)*</span><span class="sxs-lookup"><span data-stu-id="44499-1555">*Version 1808 (Build 10730.20304)*</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="44499-1556">Word：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1556">Word: Non-Security updates</span></span>

- <span data-ttu-id="44499-1557">修正 VBA 傳回不正確頁碼的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1557">Fixed an issue when VBA returns incorrect page number.</span></span>
- <span data-ttu-id="44499-1558">改善儲存在本機檔案的時間。</span><span class="sxs-lookup"><span data-stu-id="44499-1558">Improve time to save on local Word file.</span></span> 

### <a name="outlook-non-security-updates"></a><span data-ttu-id="44499-1559">Outlook：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1559">Outlook: Non-Security updates</span></span>

- <span data-ttu-id="44499-1560">提供 regkey 以停用 Office 365 [郵件加密] 功能表的 [僅加密] 選項。</span><span class="sxs-lookup"><span data-stu-id="44499-1560">Provided regkey to disable the "Encrypt Only" option in the Office 365 Message Encryption menu.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="44499-1561">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1561">Office Suite: Non-Security updates</span></span>

- <span data-ttu-id="44499-1562">已修正 Office 更新在嘗試下載時有時會卡住的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1562">Fixed an issue where Office update may get stuck for some time trying to download.</span></span>

## <a name="version-1803-march-12"></a><span data-ttu-id="44499-1563">版本 1803：3 月 12 日</span><span class="sxs-lookup"><span data-stu-id="44499-1563">Version 1803: March 12</span></span> 
- <span data-ttu-id="44499-1564">安全性更新列於[此處](microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="44499-1564">Security updates listed [here](microsoft365-apps-security-updates.md)</span></span>

## <a name="version-1808-february-12"></a><span data-ttu-id="44499-1565">版本 1808：2 月 12 日</span><span class="sxs-lookup"><span data-stu-id="44499-1565">Version 1808: February 12</span></span>
<span data-ttu-id="44499-1566">*版本 1808 (組建 10730.20280)*</span><span class="sxs-lookup"><span data-stu-id="44499-1566">*Version 1808 (Build 10730.20280)*</span></span>

### <a name="access-non-security-updates"></a><span data-ttu-id="44499-1567">Access：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1567">Access: Non-Security updates</span></span> 

- <span data-ttu-id="44499-1568">這個更新將新日本時代的支援新增至 Access。</span><span class="sxs-lookup"><span data-stu-id="44499-1568">This update adds support for new Japanese eras to Access.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="44499-1569">Outlook：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1569">Outlook: Non-Security updates</span></span> 

- <span data-ttu-id="44499-p273">解決嘗試管理規則時，因參照不再存在資料夾的規則而導致使用者 1. 看見錯誤訊息以及 2. 看見用戶端規則無法執行的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-p273">Addresses an issue that caused users with rules that refer to a folder that no longer exist to 1. See an error when trying to manage rules and 2. See client-side rules fail to run.</span></span>
- <span data-ttu-id="44499-1573">解決因快取的委派信箱導致使用者在無法預測的時間間隔遇到頻繁的當機問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1573">Addresses an issue that caused users with cached delegate mailboxes to encounter frequent hangs at unpredictable intervals.</span></span>
- <span data-ttu-id="44499-1574">解決因為會議結束時間設定為隔天午夜而導致全天會議在某些檢視中比原訂多橫跨一天的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1574">Addresses an issue that caused All Day Meetings to appear to span one more day than intended in some views due to the end time of the meeting being set to midnight of the following day.</span></span>
- <span data-ttu-id="44499-1575">修正參考日本時代建立新約會或會議時發生的當機問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1575">Fixed a hang when creating new appointments or meetings that reference Japanese eras.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="44499-1576">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1576">Office Suite: Non-security updates</span></span>

- <span data-ttu-id="44499-1577">修正使用 [O365 Office 集中式部署](/office/dev/add-ins/publish/centralized-deployment)部署的增益集發生凍結且無法使用的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1577">Fixed issue where Add-ins, deployed using [O365 Office centralized deployment](/office/dev/add-ins/publish/centralized-deployment), were freezing and unusable.</span></span>


## <a name="version-1803-february-12"></a><span data-ttu-id="44499-1578">版本 1803：2 月 12 日</span><span class="sxs-lookup"><span data-stu-id="44499-1578">Version 1803: February 12</span></span>
<span data-ttu-id="44499-1579">*版本 1803 (組建 9126.2356)*</span><span class="sxs-lookup"><span data-stu-id="44499-1579">*Version 1803 (Build 9126.2356)*</span></span>

<span data-ttu-id="44499-1580">*這是從 2018 年 7 月以來提供的半年通道版本。這個版本會繼續受到支援並會收到安全性更新，直到 2019 年 9 月為止。不過，目前已提供新的半年通道版本 — 版本 1808 (組建 10730.20280) — 其中包含了新功能、安全性更新和非安全性更新。*</span><span class="sxs-lookup"><span data-stu-id="44499-1580">*This is the Semi-Annual Channel release that's been available since July 2018. It will continue to be supported and receive security updates until September 2019. But, a new Semi-Annual Channel release is now available — Version 1808 (Build 10730.20280) — which contains new features, security updates, and non-security updates.*</span></span>

### <a name="access-non-security-updates"></a><span data-ttu-id="44499-1581">Access：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1581">Access: Non-Security updates</span></span> 

- <span data-ttu-id="44499-1582">這個更新將新日本時代的支援新增至 Access。</span><span class="sxs-lookup"><span data-stu-id="44499-1582">This update adds support for new Japanese eras to Access.</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="44499-1583">Excel：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1583">Excel: Non-Security updates</span></span> 

- <span data-ttu-id="44499-1584">這個更新將新日本時代的支援新增至 Excel。</span><span class="sxs-lookup"><span data-stu-id="44499-1584">This update adds support for new Japanese eras to Excel.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="44499-1585">Outlook：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1585">Outlook: Non-Security updates</span></span>

- <span data-ttu-id="44499-1586">修正參考日本時代建立新約會或會議時發生的當機問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1586">Fixed a hang when creating new appointments or meetings that reference Japanese eras.</span></span>

### <a name="project-non-security-updates"></a><span data-ttu-id="44499-1587">Project：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1587">Project: Non-Security updates</span></span>
- <span data-ttu-id="44499-1588">這個更新將新日本時代的支援新增至 Project</span><span class="sxs-lookup"><span data-stu-id="44499-1588">This update adds support for new Japanese eras to Project</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="44499-1589">Word：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1589">Word: Non-Security updates</span></span>

- <span data-ttu-id="44499-1590">這個更新將新日本時代的支援新增至 Word。</span><span class="sxs-lookup"><span data-stu-id="44499-1590">This update adds support for new Japanese eras to Word.</span></span>

### <a name="visio-non-security-updates"></a><span data-ttu-id="44499-1591">Visio：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1591">Visio: Non-Security updates</span></span>

- <span data-ttu-id="44499-1592">這個更新將新日本時代的支援新增至 Visio。</span><span class="sxs-lookup"><span data-stu-id="44499-1592">This update adds support for new Japanese eras to Visio.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="44499-1593">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1593">Office Suite: Non-security updates</span></span>

- <span data-ttu-id="44499-1594">修正使用 [O365 Office 集中式部署](/office/dev/add-ins/publish/centralized-deployment)部署的增益集發生凍結且無法使用的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1594">Fixed issue where Add-ins, deployed using [O365 Office centralized deployment](/office/dev/add-ins/publish/centralized-deployment), were freezing and unusable.</span></span>

## <a name="version-1708-february-12"></a><span data-ttu-id="44499-1595">版本 1708：2 月 12 日</span><span class="sxs-lookup"><span data-stu-id="44499-1595">Version 1708: February 12</span></span>
<span data-ttu-id="44499-1596">*版本 1708 (組建 8431.2372)*</span><span class="sxs-lookup"><span data-stu-id="44499-1596">*Version 1708 (Build 8431.2372)*</span></span>

<span data-ttu-id="44499-1597">*這是自從 2018 年 1 月以來提供的半年通道版本。它會繼續受到支援並接收安全性更新，直到 2019 年 3 月為止。不過，目前已提供新的半年通道版本 — 版本 1808 (組建 10730.20280) — 其中包含了新功能、安全性更新和非安全性更新。*</span><span class="sxs-lookup"><span data-stu-id="44499-1597">*This is the Semi-Annual Channel release that's been available since January 2018. It will continue to be supported and receive security updates until March 2019. But, a new Semi-Annual Channel release is now available — Version 1808 (Build 10730.20280) — which contains new features, security updates, and non-security updates.*</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="44499-1598">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1598">Office Suite: Non-security updates</span></span>

- <span data-ttu-id="44499-1599">修正使用 [O365 Office 集中式部署](/office/dev/add-ins/publish/centralized-deployment)部署的增益集發生凍結且無法使用的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1599">Fixed issue where Add-ins, deployed using [O365 Office centralized deployment](/office/dev/add-ins/publish/centralized-deployment), were freezing and unusable.</span></span>


## <a name="version-1808-january-8"></a><span data-ttu-id="44499-1600">版本 1808：1 月 8 日</span><span class="sxs-lookup"><span data-stu-id="44499-1600">Version 1808: January 8</span></span>
<span data-ttu-id="44499-1601">版本 1808 (組建 10730.20264)</span><span class="sxs-lookup"><span data-stu-id="44499-1601">*Version 1808 (Build 10730.20264)*</span></span>

### <a name="access-feature-updates"></a><span data-ttu-id="44499-1602">Access：功能更新</span><span class="sxs-lookup"><span data-stu-id="44499-1602">Access: Feature Updates</span></span>

 - <span data-ttu-id="44499-p274">**使用新圖表以視覺化方式呈現資料：** 從 11 個圖表中選擇，並將其中一個新增至您的表單和報告，更有效地以視覺化方式呈現資料並進行明智的決策。[深入了解](https://support.office.com/article/1a463106-65d0-4dbb-9d66-4ecb737ea7f7)</span><span class="sxs-lookup"><span data-stu-id="44499-p274">**Visualize data with new charts:** Choose from 11 charts and add one to your forms and reports to better visualize the data and make informed decisions. [Learn more](https://support.office.com/article/1a463106-65d0-4dbb-9d66-4ecb737ea7f7)</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="44499-1605">Excel：功能更新</span><span class="sxs-lookup"><span data-stu-id="44499-1605">Excel: Feature updates</span></span>
 - <span data-ttu-id="44499-p275">**共同作業編輯：** 在您的活頁簿中與他人同時作業。[深入了解](https://support.office.com/article/7152aa8b-b791-414c-a3bb-3024e46fb104)</span><span class="sxs-lookup"><span data-stu-id="44499-p275">**Collaborative editing:** Work with others at the same time in your workbook. [Learn more](https://support.office.com/article/7152aa8b-b791-414c-a3bb-3024e46fb104)</span></span>
 - <span data-ttu-id="44499-p276">**現在已預設啟用雲端檔案的自動儲存：** 這項改變代表使用者再也無須擔心儲存在 OneDrive 或 SharePoint Online 上的文件變更會遺失。變更將會自動儲存在雲端，使用者再也不需要明確按下 Ctrl + S 鍵或 [儲存] 按鈕。但使用者必須了解此行為中的變更，以防意外變更文件。請注意，使用者可以用畫面頂端的 [自動儲存] 切換來關閉自動儲存。建議您通知使用者此即將到來的變更，並提供有關 Office 365 中此項新功能的使用教學。[深入了解自動儲存](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5)並 [深入了解 IT 管理員對自動儲存所應注意的事項](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)</span><span class="sxs-lookup"><span data-stu-id="44499-p276">**AutoSave for cloud files is now enabled by default:** This change means users won't have to worry about losing their changes in documents stored on OneDrive or SharePoint Online. Changes will be saved in the cloud automatically, and users will no longer have to explicitly press Ctrl + S or the Save button. However, they will have to understand this change in behavior so they don't make accidental changes to documents. Note that users can turn off AutoSave using the AutoSave toggle at the top of the screen. We recommend that you notify your users about this upcoming change and educate them about how to best take advantage of this new feature in Office 365. [Learn more about AutoSave](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) and [Learn more about what IT admins should know about AutoSave](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)</span></span>
- <span data-ttu-id="44499-p277">**改善儲存格和資料編輯列編輯：** 您現在可以使用 CTRL + A 來選取儲存格或資料編輯列中的文字。另外也改善了 Emoji 和其他複雜字元的支援。[深入了解](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)</span><span class="sxs-lookup"><span data-stu-id="44499-p277">**Improved cell and formula bar editing:** You can now use CTRL+A to select text in a cell or the formula bar. There's also improved support for emojis and other complex characters. [Learn more](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)</span></span>
- <span data-ttu-id="44499-p278">**改善協助工具檢查程式︰** 協助工具檢查程式已更新，現可支援國際標準並提供讓活頁簿更易於使用的建議。[深入了解](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span><span class="sxs-lookup"><span data-stu-id="44499-p278">**Accessibility Checker improvements:** The Accessibility Checker has updated support for international standards and recommendations to make your workbooks more accessible. [Learn more](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span></span>
- <span data-ttu-id="44499-p279">**避免不想要的編輯：** 設定您的活頁簿開啟為唯讀，以避免意外變更。移至 [檔案 > 資訊 > 保護活頁簿 > 一律以唯讀開啟]</span><span class="sxs-lookup"><span data-stu-id="44499-p279">**Avoid unwanted edits:** Set your workbooks to open as read-only to prevent accidental changes. Go to File > Info > Protect Workbook > Always Open Read-Only</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="44499-1621">Excel：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1621">Excel: Non-Security updates</span></span> 

- <span data-ttu-id="44499-1622">已修正此問題：在共同撰寫工作階段中，當另一位使用者對交叉分析篩選器中的資料套用資料行篩選後，交叉分析篩選器未正確更新。</span><span class="sxs-lookup"><span data-stu-id="44499-1622">Fixed an issue in coauthoring sessions where a slicer is not properly updated after another user applies a column filter to the data in that slicer.</span></span>
- <span data-ttu-id="44499-1623">已修正此問題：在共同撰寫工作階段中，當其中一位使用者清除交叉分析篩選器的說明文字時，會導致共同撰寫工作階段中的另一位使用者遇到 Excel 損毀。</span><span class="sxs-lookup"><span data-stu-id="44499-1623">Fixed an issue in a coauthoring session where one of the users clears the caption for a slicer and this causes another user in the coauthoring session to experience an Excel crash.</span></span>
- <span data-ttu-id="44499-1624">已修正此問題：建立多個繫結至相同資料行的表格交叉分析篩選器時可能發生損毀，並刪除該行資料。</span><span class="sxs-lookup"><span data-stu-id="44499-1624">Fixed possible crash when creating multiple table slicers bound to the same column of data and then deleting that column of data.</span></span>
- <span data-ttu-id="44499-1625">已修正此問題：關閉自動調整欄寬的選項後，Excel 有時在重新整理儲存格中有換行文字的已篩選查詢資料表時會發生損毀。</span><span class="sxs-lookup"><span data-stu-id="44499-1625">Fixed an issue where Excel would sometimes crash while refreshing a filtered query table that contains wrapped text in cells when the option to automatically adjust column widths was off.</span></span>
- <span data-ttu-id="44499-1626">已修正此問題：儲存在 Excel 2007 中的交叉分析篩選器若在較新版的 Excel 中開啟，且交叉分析篩選器中顯示的項目有變更，則可能觸發損毀。</span><span class="sxs-lookup"><span data-stu-id="44499-1626">Fixed an issue where slicers saved in Excel 2007 can trigger a crash when opened in newer versions of Excel if the number of items shown in the slicer changes.</span></span>
- <span data-ttu-id="44499-1627">引入 [取得診斷] 按鈕的支援，可簡化支援要求的調查。</span><span class="sxs-lookup"><span data-stu-id="44499-1627">Introduces support for the Get Diagnostics button to simplify the investigation of support requests.</span></span>
- <span data-ttu-id="44499-1628">修正了在某些組建/版本中未出現 Power Pivot 的錯誤。</span><span class="sxs-lookup"><span data-stu-id="44499-1628">Fixed a bug where Power Pivot did not appear in some builds/versions.</span></span>
- <span data-ttu-id="44499-1629">修正以下的 Excel 問題：當使用者將滑鼠停留在具有多個定義名稱的活頁簿中的格式選項上，Excel 可能無反應，而且即使在格式選項中停用了即時預覽，Excel 也可能在快速分析工具中無反應。</span><span class="sxs-lookup"><span data-stu-id="44499-1629">Fixed the issue in Excel wherein Excel may become unresponsive when the user hovers over formatting options in a workbook with many defined names, and where Excel may become unresponsive in the Quick Analysis tool even when Live Preview was disabled in options.</span></span>
- <span data-ttu-id="44499-p280">我們目前正在調查，當 Excel 應用程式視窗從一個桌面移動到另一個桌面時，效能降低的問題。 同時，如果您發現到這種效能降低的問題，請試試在「檔案選項」對話方塊裡的「一般」索引標籤中將「當使用多個顯示器時」設定為「相容性最佳化」。</span><span class="sxs-lookup"><span data-stu-id="44499-p280">We are currently investigating slow performance when moving the Excel Application Window from one desktop to another. In the meantime, if you do notice this slowness then a work around to consider is to select "Optimize for compatibility" for "When using multiple displays" in the "General" tab in the File Options dialog.</span></span>
- <span data-ttu-id="44499-1632">已修正此問題：從原儲存格變更圖表來源資料時 Excel 可能會損毀。</span><span class="sxs-lookup"><span data-stu-id="44499-1632">Fixed an issue where Excel may crash when changing a chart's source data from its original set of cells.</span></span>
- <span data-ttu-id="44499-1633">已修正此問題：即使已設定 FullCalcOnLoad 屬性，開啟時也可能不會算。</span><span class="sxs-lookup"><span data-stu-id="44499-1633">Fixed an issue where recalculation may not happen on open even if the FullCalcOnLoad property is set.</span></span>  
- <span data-ttu-id="44499-1634">已修正此問題：在日期儲存格格式使用日本紀元日曆時顯示錯誤年份。</span><span class="sxs-lookup"><span data-stu-id="44499-1634">Fixed an issue where the wrong year is shown when Japanese Era calendar is used in date cell format.</span></span>
- <span data-ttu-id="44499-p281">當資料匯入 Excel 資料模型中，負值或零的輸入值會造成錯誤。此修正會將此類的值匯入為零。</span><span class="sxs-lookup"><span data-stu-id="44499-p281">When importing data into the Excel Data Model, incoming values of negative zero would result in an error.  The fix imports such values as zero.</span></span>
- <span data-ttu-id="44499-1637">已修正此問題：Excel 樞紐分析表中的群組 (或取消群組) 作業有時候會觸發當機。</span><span class="sxs-lookup"><span data-stu-id="44499-1637">Fixed an issue where a group (or ungroup) operation in an Excel PivotTable could sometimes trigger a crash.</span></span>
- <span data-ttu-id="44499-1638">已修正此問題：在圖表上動作可能會造成 Excel 當機。</span><span class="sxs-lookup"><span data-stu-id="44499-1638">Fixed an issue where charting actions could cause Excel to crash.</span></span>
- <span data-ttu-id="44499-1639">已修正此問題：部分使用者不小心停用 Power View 增益集。</span><span class="sxs-lookup"><span data-stu-id="44499-1639">Fixed an issue where the Power View add-in is inadvertently disabled for some users.</span></span>
- <span data-ttu-id="44499-1640">已修正此問題：在文件復原期間建立的暫時自動復原檔案永遠不會清除。</span><span class="sxs-lookup"><span data-stu-id="44499-1640">Fixed an issue where temporary auto-recovery files created during document recovery are never cleaned up.</span></span>
- <span data-ttu-id="44499-1641">已修正此問題：在嘗試與受保護 Workbook 中的文字檔建立新連線時，收到「Workbook 受到保護，且無法變更」錯誤訊息。</span><span class="sxs-lookup"><span data-stu-id="44499-1641">Fixed an issue where attempting to make a new connection to a text file in a protected workbook results in getting a "Workbook is protected and cannot be changed" error message.</span></span>
- <span data-ttu-id="44499-1642">已修正此問題：快速列印附加至 Outlook 電子郵件的 Excel 活頁簿可能會列印不出來。</span><span class="sxs-lookup"><span data-stu-id="44499-1642">Fixed an issue where Quick Print of an Excel workbook attached to an Outlook email may not print.</span></span>
- <span data-ttu-id="44499-1643">已修正此問題：按一下超連結可能會造成 Excel 當機。</span><span class="sxs-lookup"><span data-stu-id="44499-1643">Fixed an issue where clicking on a hyperlink may cause Excel to crash.</span></span>
- <span data-ttu-id="44499-1644">已修正此問題：使用 cube 函式會造成 Excel 當機。</span><span class="sxs-lookup"><span data-stu-id="44499-1644">Fixed an issue where using cube functions causes Excel to crash.</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="44499-1645">Outlook：功能更新</span><span class="sxs-lookup"><span data-stu-id="44499-1645">Outlook: Feature updates</span></span>
 - <span data-ttu-id="44499-p282">**改善協助工具檢查程式︰** 協助工具檢查程式已更新對國際標準與建議的支援，以使您的郵件更易於存取。[深入了解](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span><span class="sxs-lookup"><span data-stu-id="44499-p282">**Accessibility Checker improvements:** The Accessibility Checker has updated support for international standards and recommendations to make your messages more accessible. [Learn more](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span></span>
 - <span data-ttu-id="44499-p283">**從設定檔選擇器管理設定檔：** 如果您習慣在 Outlook 啟動時使用設定檔選擇器，現在不用去 [控制台] 也能進行變更。建立及刪除設定檔、變更設定，全都能在 [設定檔選擇器] 一次搞定。</span><span class="sxs-lookup"><span data-stu-id="44499-p283">**Manage Profiles from the Profile Picker:** If you use the Profile Picker when Outlook starts up, you can now make changes without going to the control panel. Create and delete profiles, change settings, all from the Profile Picker.</span></span>
- <span data-ttu-id="44499-1650">**內建的協助工具：** 在圖片上新增替代文字，即可讓每個人存取相關訊息。</span><span class="sxs-lookup"><span data-stu-id="44499-1650">**Accessibility built right in:** Make your messages accessible to everyone by adding descriptive alt text to your images.</span></span>
- <span data-ttu-id="44499-p284">**Outlook 增益集警告：** 有時 Outlook COM 增益集會發生問題，讓其餘 Outlook 功能變慢。這些問題可能是因為以下的事件延遲：在 Outlook 資料夾之間進行切換、新的電子郵件送達、開啟行事曆項目等等。當這類問題發生時，Outlook 會在通知列中顯示警告。</span><span class="sxs-lookup"><span data-stu-id="44499-p284">**Outlook add-in warnings:** Occasionally an Outlook COM add-in can encounter problems that slows down the rest of Outlook. These problems could be due to latency of events such as switching between Outlook folders, arrival of new emails, opening Calendar items, etc. When such issues arise, Outlook will display a warning in the notification bar.</span></span>
- <span data-ttu-id="44499-1653">**知道誰是與會者：** 即使您不是召集人，也可以看到其他人對於會議邀請的回應。</span><span class="sxs-lookup"><span data-stu-id="44499-1653">**Know who you'll be meeting with:** You can see other people's responses to a meeting request, even if you aren't the organizer.</span></span>
- <span data-ttu-id="44499-p285">**絕不錯過任何提醒：** 將提醒設定為在使用中視窗上彈出。若未設定，Outlook 會在工作列中閃爍，以引起您的注意。[深入了解](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)</span><span class="sxs-lookup"><span data-stu-id="44499-p285">**Never miss a reminder:** Set reminders to pop up over windows you're working in. Otherwise, Outlook will blink in the taskbar to get your attention. [Learn more](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)</span></span>
- <span data-ttu-id="44499-p286">**將刪除的郵件標示為已讀取：** 您現在可以將任何已刪除的郵件標示為已讀取。請移至 [檔案] \> [選項] \> [郵件] \> [其他] 來選擇使用。</span><span class="sxs-lookup"><span data-stu-id="44499-p286">**Mark deleted items as read:** You can now set any message that you delete as read. Opt in by going to File \> Options \> Mail \> Other.</span></span>
- <span data-ttu-id="44499-p287">**檢視三個時區：** 需要跨時區排程會議嗎？將多個時區新增至行事曆，方便檢視所有人員的空檔，並挑選出所有人都可行的時間。[深入了解](https://support.office.com/article/5ab3e10e-5a6c-46af-ab48-156fedf70c04)</span><span class="sxs-lookup"><span data-stu-id="44499-p287">**View three time zones:** Need to schedule a meeting across time zones? Add multiple time zones to your calendar to easily see everyone's availability and pick a time that works for all. [Learn more](https://support.office.com/article/5ab3e10e-5a6c-46af-ab48-156fedf70c04)</span></span>
- <span data-ttu-id="44499-p288">**改善建立群組的使用者體驗：** 我們已改善建立群組的使用者體驗，讓它更具現代化。[深入了解](https://support.office.com/article/04d0c9cf-6864-423c-a380-4fa858f27102)</span><span class="sxs-lookup"><span data-stu-id="44499-p288">**Refined user experience for creating a group:** We have refined the user experience for the create group to make it look more modern and clutter-free. [Learn more](https://support.office.com/article/04d0c9cf-6864-423c-a380-4fa858f27102)</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="44499-1664">Outlook：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1664">Outlook: Non-Security updates</span></span>
- <span data-ttu-id="44499-1665">修正導致使用者遇到行事曆同步處理錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1665">Fixed an issue that caused users to experience calendar synchronization errors.</span></span>
- <span data-ttu-id="44499-1666">已修正使用者啟動 [管理規則及通知] 對話方塊時看到錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1666">Fixed an issue that caused users to see an error when launching the "Manage Rules and Alerts" dialog.</span></span>
- <span data-ttu-id="44499-1667">已修正此問題：使用者使用計量付費連線時，無法透過 DirectAccess 連線到他們的信箱。</span><span class="sxs-lookup"><span data-stu-id="44499-1667">Fixed an issue that caused users to be unable to connect to their mailboxes over DirectAccess when using a metered connection.</span></span>
- <span data-ttu-id="44499-1668">已修正此問題：使用者會看到儲存在公用資料夾中的可用文件錯誤地在「受保護的檢視」中開啟。</span><span class="sxs-lookup"><span data-stu-id="44499-1668">Fixed an issue that caused users to see free docs stored in Public Folders erroneously open in "Protected View".</span></span>
- <span data-ttu-id="44499-1669">已修正此問題：使用者轉寄具有內嵌附件的項目時，會看到非預期的附件。</span><span class="sxs-lookup"><span data-stu-id="44499-1669">Fixed an issue that caused users to see unexpected attachments when forwarding items with inline attachments.</span></span>
- <span data-ttu-id="44499-1670">已修正 OFT 檔案在作為附件傳送後，呈現效果不良的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1670">Fixed an issue that caused OFT files to render poorly after being sent as an attachment.</span></span>
- <span data-ttu-id="44499-1671">已修正此問題：部分增益集使用者在將會議新增至共用行事曆時遇到損毀問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1671">Fixed an issue that caused some add in users to experience crashes when adding a meeting to a shared calendar.</span></span>
- <span data-ttu-id="44499-1672">已修正此問題：使用者開啟交談歷程記錄資料夾時遇到當機問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1672">Fixed an issue that caused users to experience hangs when opening the Conversation History folder.</span></span>
- <span data-ttu-id="44499-1673">已修正此問題：如果將系統語言切換為日文，並在載入 Outlook 時嘗試輸入 VBA IDE 時，畫面會凍結。</span><span class="sxs-lookup"><span data-stu-id="44499-1673">Fixed an issue where if you switch the system language to Japanese and attempt to type Japanese characters into the VBA IDE when loaded within Outlook, it freezes.</span></span>
- <span data-ttu-id="44499-1674">已修正此問題：切換到 [寄件匣] 或 [寄件備份] 資料夾造成 Outlook 損毀。</span><span class="sxs-lookup"><span data-stu-id="44499-1674">Fixed an issue where switching to the Outbox or Sent Items folder causes Outlook to crash.</span></span>
- <span data-ttu-id="44499-1675">已修正此問題：會議內文或附件變更時所有出席者收到會議更新，而非傳送會議更新給選擇性的出席者。</span><span class="sxs-lookup"><span data-stu-id="44499-1675">Fixed an issue where all attendees receive meeting updates when the meeting body or attachments change, instead of sending a meeting update to the attendees being optional.</span></span>
- <span data-ttu-id="44499-1676">已修正此問題：因為使用者代理程式字串中的變更，造成使用者無法連線到 EWS 及 REST 端點。</span><span class="sxs-lookup"><span data-stu-id="44499-1676">Fixed an issue that causes users to be unable to connect to EWS and REST endpoints because of a change in the User-Agent string.</span></span>
- <span data-ttu-id="44499-1677">已修正此問題：出席者的會議位置更新是顯示舊的位置而不是新的位置。</span><span class="sxs-lookup"><span data-stu-id="44499-1677">Fixed an issue where a meeting location update to attendees shows the old location instead of the new location.</span></span>
- <span data-ttu-id="44499-1678">已修正此問題：使用者在預覽讀取窗格中的附件時，會看到錯誤。</span><span class="sxs-lookup"><span data-stu-id="44499-1678">Fixed an issue where the user sees an error when previewing an attachment in the reading pane.</span></span>
- <span data-ttu-id="44499-1679">已修正此問題：當使用者在撰寫電子郵件時，解決電子郵件地址的顯示名稱會使 Outlook 當機。</span><span class="sxs-lookup"><span data-stu-id="44499-1679">Fixed an issue where Outlook crashes when resolving display names to email addresses when the user is composing an email.</span></span>
- <span data-ttu-id="44499-1680">已修正此問題：有些使用者未收到其租用戶系統管理員已啟用的支援功能。</span><span class="sxs-lookup"><span data-stu-id="44499-1680">Fixed an issue where some users don't receive support features that have been enabled by their tenant admin.</span></span>

### <a name="onenote-non-security-updates"></a><span data-ttu-id="44499-1681">OneNote：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1681">OneNote: Non-security updates</span></span> 

- <span data-ttu-id="44499-1682">修正了可能發生的穩定性問題，包括同步處理和瀏覽至刪除的部分。</span><span class="sxs-lookup"><span data-stu-id="44499-1682">Fixed a stability issue that can occur involving sync and navigating to a deleted section.</span></span>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="44499-1683">PowerPoint：功能更新</span><span class="sxs-lookup"><span data-stu-id="44499-1683">PowerPoint: Feature updates</span></span> 
- <span data-ttu-id="44499-p289">**現在已預設啟用雲端檔案的自動儲存：** 這項改變代表使用者再也無須擔心儲存在 OneDrive 或 SharePoint Online 上的文件變更會遺失。變更將會自動儲存在雲端，使用者再也不需要明確按下 Ctrl + S 鍵或 [儲存] 按鈕。但使用者必須了解此行為中的變更，以防意外變更簡報。請注意，使用者可以用畫面頂端的 [自動儲存] 切換來關閉自動儲存。建議您通知使用者此即將到來的變更，並提供有關 Office 365 中此項新功能的使用教學。[深入了解自動儲存](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5)以及 [深入了解 IT 管理員對自動儲存所應注意的事項](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)</span><span class="sxs-lookup"><span data-stu-id="44499-p289">**AutoSave for cloud files is now enabled by default:** This change means users won't have to worry about losing their changes in documents stored on OneDrive or SharePoint Online. Changes will be saved in the cloud automatically, and users will no longer have to explicitly press Ctrl + S or the Save button. However, they will have to understand this change in behavior so they don't make accidental changes to presentations. Note that users can turn off AutoSave using the AutoSave toggle at the top of the screen. We recommend that you notify your users about this upcoming change and educate them about how to best take advantage of this new feature in Office 365. [Learn more about AutoSave](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) and [Learn more about what IT admins should know about AutoSave](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)</span></span>
- <span data-ttu-id="44499-p290">**改善儲存格和資料編輯列編輯：** 您現在可以使用 CTRL + A 來選取儲存格或資料編輯列中的文字。另外也改善了 Emoji 和其他複雜字元的支援。[深入了解](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)</span><span class="sxs-lookup"><span data-stu-id="44499-p290">**Improved cell and formula bar editing:** You can now use CTRL+A to select text in a cell or the formula bar. There's also improved support for emojis and other complex characters. [Learn more](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)</span></span>
- <span data-ttu-id="44499-p291">**轉換筆跡：** 擷取草草寫下的筆記和繪圖，並將其轉換為可供閱讀的文字和簡潔的圖形，以建立精美的簡報。 [深入了解](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)</span><span class="sxs-lookup"><span data-stu-id="44499-p291">**Convert your ink:** Take scribbled notes and drawings, and convert them into readable text and crisp shapes to create a polished presentation. [Learn more](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)</span></span>
- <span data-ttu-id="44499-p292">**改善 SVG 支援：** 您可以將已套用篩選的 SVG 插入。[深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="44499-p292">**Improved SVG support:** You can insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>
- <span data-ttu-id="44499-p293">**使用手寫筆為投影片撰寫標題：** 使用手寫筆輸入標題，並觀看 PowerPoint 將它轉換成文字。[深入了解](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="44499-p293">**Title your slides with a pen:** Use your pen to ink in a title, and watch PowerPoint convert it to text. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>
- <span data-ttu-id="44499-p294">**避免不想要的編輯：** 設定您的活頁簿開啟為唯讀，以避免意外變更。移至 [檔案 > 資訊 > 保護活頁簿 > 一律以唯讀開啟]</span><span class="sxs-lookup"><span data-stu-id="44499-p294">**Avoid unwanted edits:** Set your workbooks to open as read-only to prevent accidental changes. Go to File > Info > Protect Workbook > Always Open Read-Only</span></span>
- <span data-ttu-id="44499-p295">**改善協助工具檢查程式︰** 協助工具檢查程式已更新對國際標準與建議的支援，以使您的簡報更易於存取。[深入了解](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span><span class="sxs-lookup"><span data-stu-id="44499-p295">**Accessibility Checker improvements:** The Accessibility Checker has updated support for international standards and recommendations to make your presentations more accessible. [Learn more](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span></span>


### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="44499-1703">PowerPoint：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1703">PowerPoint: Non-Security updates</span></span>
- <span data-ttu-id="44499-1704">修正了使用 ActiveX 內容來儲存文件時，可能造成文件損毀的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1704">Fixed an issue of potential file corruptions when saving files with ActiveX content.</span></span>
- <span data-ttu-id="44499-1705">已修正此問題：表格以粗框線錯誤編譯。</span><span class="sxs-lookup"><span data-stu-id="44499-1705">Fixed an issue where tables are rendered incorrectly with thick borders.</span></span>
- <span data-ttu-id="44499-1706">已修正此問題：當變更 Shape.Visibile 屬性時可能會造成當機。</span><span class="sxs-lookup"><span data-stu-id="44499-1706">Fixed an issue where a potential crash could occur when changing the Shape.Visibile property.</span></span>
- <span data-ttu-id="44499-1707">已修正此問題：共同撰寫文件中的變更無法合併。</span><span class="sxs-lookup"><span data-stu-id="44499-1707">Fixed an issue where changes in co-authored documents fail to merge.</span></span>
- <span data-ttu-id="44499-1708">已修正此問題：包含 ActiveX 控制項的文件會造成共同撰寫失敗。</span><span class="sxs-lookup"><span data-stu-id="44499-1708">Fixed an issue where documents containing ActiveX controls would cause co-authoring to fail.</span></span>
- <span data-ttu-id="44499-1709">已修正此問題：在圖形中使用拼字校正時會造成 PowerPoint 當機。</span><span class="sxs-lookup"><span data-stu-id="44499-1709">Fixed an issue where spelling correction in shapes causes PowerPoint to crash.</span></span>
- <span data-ttu-id="44499-1710">已修正此問題：PowerPoint 在從 SharePoint Online 開啟檔案時損毀。</span><span class="sxs-lookup"><span data-stu-id="44499-1710">Fixed an issue where PowerPoint crashes when opening a file from SharePoint Online.</span></span>
- <span data-ttu-id="44499-1711">已修正此問題：開啟 [自動儲存] 時，[復原] 窗格不正確地顯示。</span><span class="sxs-lookup"><span data-stu-id="44499-1711">Fixed an issue where the Recovery Pane incorrectly appears when AutoSave is on.</span></span>
- <span data-ttu-id="44499-1712">已修正此問題：未顯示登入，使得使用者無法存取檔案。</span><span class="sxs-lookup"><span data-stu-id="44499-1712">Fixed an issue where sign-in isn't shown preventing a user from accessing a file.</span></span>
- <span data-ttu-id="44499-1713">已修正此問題：多個使用者在相同簡報上共同撰寫會導致投影片母片不正確重複。</span><span class="sxs-lookup"><span data-stu-id="44499-1713">Fixed an issue where multiple users co-authoring on the same presentation results in an incorrect duplication of slides masters.</span></span>
- <span data-ttu-id="44499-1714">已修正此問題：將儲存在 OneDrive 中的檔案開啟時，結束受保護的檢視時會導致 PowerPoint 當機。</span><span class="sxs-lookup"><span data-stu-id="44499-1714">Fixed an issue where opening a file saved on OneDrive results in PowerPoint crashing when exiting Protected View.</span></span>

### <a name="project-feature-updates"></a><span data-ttu-id="44499-1715">Project：功能更新</span><span class="sxs-lookup"><span data-stu-id="44499-1715">Project: Feature updates</span></span> 
- <span data-ttu-id="44499-1716">**短期衝刺管理：** 快速新增、 更新或刪除敏捷短期衝刺。</span><span class="sxs-lookup"><span data-stu-id="44499-1716">**Sprint management:** Quickly add, update, or delete agile sprints.</span></span>
- <span data-ttu-id="44499-1717">**工作面板篩選：** 篩選重要資源或摘要任務，以簡化您的工作面板。</span><span class="sxs-lookup"><span data-stu-id="44499-1717">**Task board filtering:** Streamline your task boards by filtering on key resources or summary tasks.</span></span>
- <span data-ttu-id="44499-1718">**從工作面板設定完成百分比：** 針對每個資料行選擇完成百分比，然後透過拖放更新工作完成度。</span><span class="sxs-lookup"><span data-stu-id="44499-1718">**Set percent complete from a task board:** Choose a percent complete for each column, and then update task completion with drag-and-drop.</span></span>
- <span data-ttu-id="44499-1719">**短期衝刺瀏覽：** 從某個短期衝刺檢視切換到另一個檢視，並快速地在短期衝刺之間移動工作。</span><span class="sxs-lookup"><span data-stu-id="44499-1719">**Sprint navigation:** Switch from one sprint view to another, and quickly move tasks between sprints.</span></span>
- <span data-ttu-id="44499-p296">**管理短期衝刺的全新方法：** 採取敏捷方式來使用工作面板。隨著專案的發展，請移至 [管理短期衝刺] 來新增或移除短期衝刺。</span><span class="sxs-lookup"><span data-stu-id="44499-p296">**A new way to manage sprints:** Take an agile approach to working with Task Boards. Go to Manage Sprints to add and remove sprints as your project evolves.</span></span>
- <span data-ttu-id="44499-p297">**使用最近的儲存位置保持組織：** 專案會保存您已儲存其他專案位置的持續清單。當您準備好要儲存專案時，只需選擇其中一個您最近的儲存位置，就能繼續進行您一天的工作。</span><span class="sxs-lookup"><span data-stu-id="44499-p297">**Stay organized with Recent save locations:** Project keeps a running list of where you've saved other projects. When you're ready to save your project, just choose one of your Recent save locations and get on with your day.</span></span>

### <a name="project-non-security-updates"></a><span data-ttu-id="44499-1724">Project：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1724">Project: Non-Security updates</span></span>

- <span data-ttu-id="44499-1725">已修正在專案中支援新委內瑞拉貨幣的相關問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1725">Fixed an issue around supporting a new Venezuelan currency in Project.</span></span>
- <span data-ttu-id="44499-1726">已修正此問題：專案若使用連線到外部監視器的介面 Surface 4，可能會停止回應。</span><span class="sxs-lookup"><span data-stu-id="44499-1726">Fixed an issue where Project may hang when using a Surface 4 that is connected to an external monitor.</span></span>
- <span data-ttu-id="44499-1727">已修正此問題：將專案儲存為 XML 格式時，專案可能會損毀。</span><span class="sxs-lookup"><span data-stu-id="44499-1727">Fixed an issue where Project may crash when saving the project to the XML format.</span></span>
- <span data-ttu-id="44499-1728">已修正此問題：企業資源自訂欄位可能會在編輯資源的行事曆後遭到刪除。</span><span class="sxs-lookup"><span data-stu-id="44499-1728">Fixed an issue where enterprise resource custom fields may be deleted after editing a resource's calendar.</span></span>
- <span data-ttu-id="44499-1729">已修正此問題：使用者搜尋韓文的顯示名稱時會遇到損毀問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1729">Fixed an issue that caused users to experience crashes when searching for Korean display names.</span></span>
- <span data-ttu-id="44499-1730">已修正此問題：當您透過主要專案使用子專案時，系統阻止您儲存子專案。</span><span class="sxs-lookup"><span data-stu-id="44499-1730">Fixed an issue where you are blocked from saving a sub project when working with them through the context of a master project.</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="44499-1731">Word：功能更新</span><span class="sxs-lookup"><span data-stu-id="44499-1731">Word: Feature updates</span></span>
- <span data-ttu-id="44499-p298">**現在已預設啟用雲端檔案的自動儲存：** 這項改變代表使用者再也無須擔心儲存在 OneDrive 或 SharePoint Online 上的文件變更會遺失。變更將會自動儲存在雲端，使用者再也不需要明確按下 Ctrl + S 鍵或 [儲存] 按鈕。但使用者必須了解此行為中的變更，以防意外變更簡報。請注意，使用者可以用畫面頂端的 [自動儲存] 切換來關閉自動儲存。建議您通知使用者此即將到來的變更，並提供有關 Office 365 中此項新功能的使用教學。[深入了解自動儲存](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5)以及 [深入了解 IT 管理員對自動儲存所應注意的事項](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)</span><span class="sxs-lookup"><span data-stu-id="44499-p298">**AutoSave for cloud files is now enabled by default:** This change means users won't have to worry about losing their changes in documents stored on OneDrive or SharePoint Online. Changes will be saved in the cloud automatically, and users will no longer have to explicitly press Ctrl + S or the Save button. However, they will have to understand this change in behavior so they don't make accidental changes to presentations. Note that users can turn off AutoSave using the AutoSave toggle at the top of the screen. We recommend that you notify your users about this upcoming change and educate them about how to best take advantage of this new feature in Office 365. [Learn more about AutoSave](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) and [Learn more about what IT admins should know about AutoSave](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)</span></span>
- <span data-ttu-id="44499-p299">**改善協助工具檢查程式︰** 協助工具檢查程式已更新對國際標準與建議的支援，以使您的文件更易於存取。[深入了解](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span><span class="sxs-lookup"><span data-stu-id="44499-p299">**Accessibility Checker improvements:** The Accessibility Checker has updated support for international standards and recommendations to make your documents more accessible. [Learn more](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span></span>
- <span data-ttu-id="44499-p300">**改善 SVG 支援：** 您可以將已套用篩選的 SVG 插入。[深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="44499-p300">**Improved SVG support:** You can insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="44499-1742">Word：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1742">Word: Non-Security updates</span></span>
- <span data-ttu-id="44499-1743">修正造成顯示記憶體不足訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1743">Fix an issue that causes an insufficient memory message to appear.</span></span>
- <span data-ttu-id="44499-1744">修正了防止部分使用者開啟受 IRM 保護的文件和電子郵件 (由其他組織中的人員與他們共用) 的一些問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1744">Fixed a set of issues that prevented some users from opening IRM-protected documents & emails that were shared with them by people in other organizations.</span></span>
- <span data-ttu-id="44499-1745">修正一些效能問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1745">Fixed some performance issues.</span></span>
- <span data-ttu-id="44499-1746">改善開啟效能。</span><span class="sxs-lookup"><span data-stu-id="44499-1746">Improve open performance.</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="44499-1747">商務用 Skype：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1747">Skype for Business: Non-security updates</span></span>
- <span data-ttu-id="44499-p301">修正與 TLS 1.2 支援相關的問題。(附註：這是 4 月 10 日的資訊曾經提及的同一個修正。但在這裡，它變成 9 月彙總套件的一部分，並且再被提及一次。)</span><span class="sxs-lookup"><span data-stu-id="44499-p301">Fix an issue related to TLS 1.2 support. (Note: This is the same fix that was mentioned in the April 10 notes and is mentioned here again as part of the September rollup.)</span></span>
- <span data-ttu-id="44499-1750">修正此問題：在會議中以選取 [Skype 通話] 的方式新增使用者會產生錯誤。</span><span class="sxs-lookup"><span data-stu-id="44499-1750">Fix an issue where adding users by selecting 'Skype Call' in a meeting causes an error.</span></span>
- <span data-ttu-id="44499-1751">如果已將 Skype 會議室新增為位置，且會議已包含小組會議座標，請移除要求使用者將 Skype 座標新增至會議的提示。</span><span class="sxs-lookup"><span data-stu-id="44499-1751">Remove prompt asking user to add Skype coordinates to a meeting, if a Skype Room is added as the location and the meeting already contains Teams meeting coordinates.</span></span>
- <span data-ttu-id="44499-1752">修正此問題：即使 UseLocationForE911Only 設定為 true，也會填入位置。</span><span class="sxs-lookup"><span data-stu-id="44499-1752">Fix an issue where location is populated even when UseLocationForE911Only is set to true.</span></span>
- <span data-ttu-id="44499-1753">修正此問題：使用名冊中的「使用會議中心呼叫」選項來邀請使用者時，商務用 Skype 會當機。</span><span class="sxs-lookup"><span data-stu-id="44499-1753">Fix an issue where Skype for Business hangs when using the "call using conference center" option to invite users from the roster.</span></span>
- <span data-ttu-id="44499-1754">修正此問題：建立商務用 Skype 會議時，在終端機伺服器上運行的Outlook 會凍結。</span><span class="sxs-lookup"><span data-stu-id="44499-1754">Fix an issue where Outlook running on terminal server freezes while creating a Skype for Business meeting.</span></span>
- <span data-ttu-id="44499-1755">將 EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket 的預設值變更為 TRUE。</span><span class="sxs-lookup"><span data-stu-id="44499-1755">Change the default value of EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket to TRUE.</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="44499-1756">Visio：功能更新</span><span class="sxs-lookup"><span data-stu-id="44499-1756">Visio: Feature updates</span></span>
- <span data-ttu-id="44499-1757">**讓您的圖表和來源能保持同步：** 當您在 Visio 中編輯 [資料視覺化工具] 圖表時，可以選擇用最新的圖表內容來更新連結的 Excel 來源資料。</span><span class="sxs-lookup"><span data-stu-id="44499-1757">**Keep your diagram and source in sync:** When you edit a Data Visualizer diagram in Visio, you have the option to update the linked Excel source data with the latest diagram content.</span></span>
- <span data-ttu-id="44499-1758">**資料視覺化工具稽核範本：** 從 Excel 匯入內容，並建立金融交易、庫存管理等稽核圖表。</span><span class="sxs-lookup"><span data-stu-id="44499-1758">**Data Visualizer audit template:** Import content from Excel and create audit diagrams for financial transactions, inventory management, and more.</span></span>
- <span data-ttu-id="44499-1759">**入門圖表：** 組織圖、腦力激盪和 SDL 範本有新的入門圖表可讓您快速啟動並執行。</span><span class="sxs-lookup"><span data-stu-id="44499-1759">**Starter diagrams:** The Organization Chart, Brainstorming, and SDL templates have new starter diagrams to get you up and running quickly.</span></span>
- <span data-ttu-id="44499-p302">**從 Visio 圖形建立 Word 文件：** 自動將圖表內容 (包括圖形和中繼資料) 新增至 Word 文件。然後自訂文件以建立程序指導方針和操作手冊。[深入了解](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)</span><span class="sxs-lookup"><span data-stu-id="44499-p302">**Build a Word document out of Visio shapes** Automatically add diagram content, including shapes and metadata, to a Word document. Then customize the document to create process guidelines and operation manuals. [Learn more](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)</span></span>

### <a name="office-suite-security-update"></a><span data-ttu-id="44499-1763">Office 套件：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1763">Office Suite: Security update</span></span>

- <span data-ttu-id="44499-p303">
  \*\*基於安全原因已封鎖 Flash、Silverlight、Shockwave 控制在 Office 中啟動：\*\* 基於安全原因，Windows 上新組建的 Microsoft Office for Office 365 會封鎖 Flash、Silverlight、Shockwave 控制的啟動。請看[這裡](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Blocking-Flash-Shockwave-Silverlight-controls-from-activating-in/ba-p/191729)和[這裡](https://support.office.com/article/flash-silverlight-and-shockwave-controls-blocked-in-office-2016-55738f12-a01d-420e-a533-7cef1ff6aeb1)深入了解。</span><span class="sxs-lookup"><span data-stu-id="44499-p303">**Flash, Silverlight and Shockwave controls blocked from activating in Office for security reasons:** For security reasons new builds of Microsoft Office for Office 365 on Windows block activation of Flash, Silverlight, and Shockwave controls. Learn more [here](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Blocking-Flash-Shockwave-Silverlight-controls-from-activating-in/ba-p/191729) and [here](https://support.office.com/article/flash-silverlight-and-shockwave-controls-blocked-in-office-2016-55738f12-a01d-420e-a533-7cef1ff6aeb1).</span></span>
 
### <a name="office-suite-non-security-updates"></a><span data-ttu-id="44499-1766">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1766">Office Suite: Non-Security updates</span></span>
- <span data-ttu-id="44499-1767">已修正導致更新安裝在特定情況下需要很長時間的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1767">Fixed an issue that caused update install to take a long time in certain scenarios.</span></span>
- <span data-ttu-id="44499-1768">修正此問題：開啟應用程式時，使用者可能會看到以安全模式啟動的訊息，然後應用程式無法開啟。</span><span class="sxs-lookup"><span data-stu-id="44499-1768">Fix an issue where, when opening an application, the user might see a message about launching in Safe mode and then the application fails to open.</span></span>
- <span data-ttu-id="44499-1769">修正一些效能問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1769">Fixed some performance issues.</span></span>


## <a name="version-1803-january-8"></a><span data-ttu-id="44499-1770">版本 1803：1 月 8 日</span><span class="sxs-lookup"><span data-stu-id="44499-1770">Version 1803: January 8</span></span>
<span data-ttu-id="44499-1771">版本 1803 (組建 9126.2351)</span><span class="sxs-lookup"><span data-stu-id="44499-1771">*Version 1803 (Build 9126.2351)*</span></span>

<span data-ttu-id="44499-1772">這是從 2018 年 7 月以來提供的半年通道版本。這個版本會繼續受到支援並會收到安全性更新，直到 2019 年 9 月為止。不過，目前已提供新的半年通道版本 — 版本 1808 — 其中包含了新功能、安全性更新和非安全性更新。</span><span class="sxs-lookup"><span data-stu-id="44499-1772">*This is the Semi-Annual Channel release that's been available since July 2018. It will continue to be supported and receive security updates until September 2019. But, a new Semi-Annual Channel release is now available — Version 1808 — which contains new features, security updates, and non-security updates.*</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="44499-1773">PowerPoint：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1773">PowerPoint: Non-Security updates</span></span>
- <span data-ttu-id="44499-1774">修正問題，確保 LinkedIn 選項在 各 Office 應用程式之間的一致性。</span><span class="sxs-lookup"><span data-stu-id="44499-1774">Fixed an issue to ensure feature parity of the LinkedIn option between Office applications.</span></span>

## <a name="version-1803-december-11"></a><span data-ttu-id="44499-1775">版本 1803：12 月 11 日</span><span class="sxs-lookup"><span data-stu-id="44499-1775">Version 1803: December 11</span></span>
<span data-ttu-id="44499-1776">*版本 1803 (組建 9126.2336)*</span><span class="sxs-lookup"><span data-stu-id="44499-1776">*Version 1803 (Build 9126.2336)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="44499-1777">Excel：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1777">Excel: Security updates</span></span> 

-   <span data-ttu-id="44499-1778">[CVE-2018-8597](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8597)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1778">[CVE-2018-8597](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8597): Microsoft Excel Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="44499-1779">[CVE-2018-8598](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8598)：Microsoft Excel 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1779">[CVE-2018-8598](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8598): Microsoft Excel Information Disclosure Vulnerability</span></span> 
-   <span data-ttu-id="44499-1780">[CVE-2018-8627](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8627)：Microsoft Excel 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1780">[CVE-2018-8627](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8627): Microsoft Excel Information Disclosure Vulnerability</span></span> 
-   <span data-ttu-id="44499-1781">[CVE-2018-8636](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8636)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1781">[CVE-2018-8636](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8636): Microsoft Excel Remote Code Execution Vulnerability</span></span> 

### <a name="outlook-security-updates"></a><span data-ttu-id="44499-1782">Outlook：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1782">Outlook: Security updates</span></span> 

-   <span data-ttu-id="44499-1783">[CVE-2018-8587](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8587)：Microsoft Outlook 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1783">[CVE-2018-8587](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8587): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 

### <a name="powerpoint-security-updates"></a><span data-ttu-id="44499-1784">PowerPoint：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1784">PowerPoint: Security updates</span></span> 

-   <span data-ttu-id="44499-1785">[CVE-2018-8628](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8628)：Microsoft PowerPoint 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1785">[CVE-2018-8628](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8628): Microsoft PowerPoint Remote Code Execution Vulnerability</span></span> 


### <a name="outlook-non-security-updates"></a><span data-ttu-id="44499-1786">Outlook：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1786">Outlook: Non-Security updates</span></span>

- <span data-ttu-id="44499-1787">修正 Outlook 更新特定連絡人欄位時意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1787">Fixed an issue that caused Outlook to close unexpectedly when updating certain contact fields.</span></span>
- <span data-ttu-id="44499-1788">解決使用者啟動 [管理規則及通知] 對話方塊時看到錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1788">Addresses an issue that caused users to see an error when launching the "Manage Rules and Alerts" dialog.</span></span>
- <span data-ttu-id="44499-1789">解決 Outlook 使用者執行一些增益集時遇到損毀的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1789">Addresses an issue that caused Outlook users to experience crashes while running some add ins.</span></span>


## <a name="version-1708-december-11"></a><span data-ttu-id="44499-1790">版本 1708：12 月 11 日</span><span class="sxs-lookup"><span data-stu-id="44499-1790">Version 1708: December 11</span></span>
<span data-ttu-id="44499-1791">*版本 1708 (組建 8431.2351)*</span><span class="sxs-lookup"><span data-stu-id="44499-1791">*Version 1708 (Build 8431.2351)*</span></span>

<span data-ttu-id="44499-1792">*這是自從 2018 年 1 月以來提供的半年通道版本。它會繼續受到支援並接收安全性更新，直到 2019 年 3 月為止。不過，目前已提供新的半年通道版本 — 版本 1803 (組建 16.0.9126.2336) — 其中包含了新功能、安全性更新和非安全性更新。*</span><span class="sxs-lookup"><span data-stu-id="44499-1792">*This is the Semi-Annual Channel release that's been available since January 2018. It will continue to be supported and receive security updates until March 2019. But, a new Semi-Annual Channel release is now available — Version 1803 (Build 16.0.9126.2336) — which contains new features, security updates, and non-security updates.*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="44499-1793">Excel：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1793">Excel: Security updates</span></span> 

-   <span data-ttu-id="44499-1794">[CVE-2018-8597](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8597)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1794">[CVE-2018-8597](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8597): Microsoft Excel Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="44499-1795">[CVE-2018-8598](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8598)：Microsoft Excel 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1795">[CVE-2018-8598](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8598): Microsoft Excel Information Disclosure Vulnerability</span></span> 
-   <span data-ttu-id="44499-1796">[CVE-2018-8627](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8627)：Microsoft Excel 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1796">[CVE-2018-8627](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8627): Microsoft Excel Information Disclosure Vulnerability</span></span> 
-   <span data-ttu-id="44499-1797">[CVE-2018-8636](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8636)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1797">[CVE-2018-8636](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8636): Microsoft Excel Remote Code Execution Vulnerability</span></span> 

### <a name="outlook-security-updates"></a><span data-ttu-id="44499-1798">Outlook：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1798">Outlook: Security updates</span></span> 

-   <span data-ttu-id="44499-1799">[CVE-2018-8587](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8587)：Microsoft Outlook 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1799">[CVE-2018-8587](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8587): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 

### <a name="powerpoint-security-updates"></a><span data-ttu-id="44499-1800">PowerPoint：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1800">PowerPoint: Security updates</span></span> 

-   <span data-ttu-id="44499-1801">[CVE-2018-8628](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8628)：Microsoft PowerPoint 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1801">[CVE-2018-8628](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8628): Microsoft PowerPoint Remote Code Execution Vulnerability</span></span> 

### <a name="outlook-non-security-updates"></a><span data-ttu-id="44499-1802">Outlook：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1802">Outlook: Non-Security updates</span></span>

- <span data-ttu-id="44499-1803">修正 Outlook 更新特定連絡人欄位時意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1803">Fixed an issue that caused Outlook to close unexpectedly when updating certain contact fields.</span></span>
- <span data-ttu-id="44499-1804">解決使用者啟動 [管理規則及通知] 對話方塊時看到錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1804">Addresses an issue that caused users to see an error when launching the "Manage Rules and Alerts" dialog.</span></span>
- <span data-ttu-id="44499-1805">解決 Outlook 使用者執行一些增益集時遇到損毀的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1805">Addresses an issue that caused Outlook users to experience crashes while running some add ins.</span></span>


## <a name="version-1803-november-13"></a><span data-ttu-id="44499-1806">版本 1803：11 月 13 日</span><span class="sxs-lookup"><span data-stu-id="44499-1806">Version 1803: November 13</span></span>
<span data-ttu-id="44499-1807">*版本 1803 (組建 9126.2315)*</span><span class="sxs-lookup"><span data-stu-id="44499-1807">*Version 1803 (Build 9126.2315)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="44499-1808">Excel：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1808">Excel: Security updates</span></span>

-   <span data-ttu-id="44499-1809">[CVE-2018-8574](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8574)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1809">[CVE-2018-8574](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8574): Microsoft Excel Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="44499-1810">[CVE-2018-8577](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8577)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1810">[CVE-2018-8577](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8577): Microsoft Excel Remote Code Execution Vulnerability</span></span> 

### <a name="outlook-security-updates"></a><span data-ttu-id="44499-1811">Outlook：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1811">Outlook: Security updates</span></span> 

-   <span data-ttu-id="44499-1812">[CVE-2018-8522](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8522)：Microsoft Outlook 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1812">[CVE-2018-8522](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8522): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="44499-1813">[CVE-2018-8524](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8524)：Microsoft Outlook 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1813">[CVE-2018-8524](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8524): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="44499-1814">[CVE-2018-8558](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8558)：Microsoft Outlook 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1814">[CVE-2018-8558](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8558): Microsoft Outlook Information Disclosure Vulnerability</span></span> 
-   <span data-ttu-id="44499-1815">[CVE-2018-8576](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8576)：Microsoft Outlook 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1815">[CVE-2018-8576](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8576): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="44499-1816">[CVE-2018-8579](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8579)：Microsoft Outlook 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1816">[CVE-2018-8579](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8579): Microsoft Outlook Information Disclosure Vulnerability</span></span> 
-   <span data-ttu-id="44499-1817">[CVE-2018-8582](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8582)：Microsoft Outlook 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1817">[CVE-2018-8582](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8582): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 

### <a name="project-security-updates"></a><span data-ttu-id="44499-1818">Project：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1818">Project: Security updates</span></span> 

-   <span data-ttu-id="44499-1819">[CVE-2018-8575](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8575)：Microsoft Project 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1819">[CVE-2018-8575](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8575): Microsoft Project Remote Code Execution Vulnerability</span></span> 

### <a name="word-security-updates"></a><span data-ttu-id="44499-1820">Word：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1820">Word: Security updates</span></span> 

-   <span data-ttu-id="44499-1821">[CVE-2018-8573](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8573)：Microsoft Word 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1821">[CVE-2018-8573](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8573): Microsoft Word Remote Code Execution Vulnerability</span></span> 

### <a name="skype-for-business-security-updates"></a><span data-ttu-id="44499-1822">商務用 Skype：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1822">Skype for Business: Security updates</span></span> 

-   <span data-ttu-id="44499-1823">[CVE-2018-8546](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8546)：Microsoft 商務用 Skype 阻絕服務弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1823">[CVE-2018-8546](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8546): Microsoft Skype for Business Denial of Service Vulnerability</span></span> 

### <a name="outlook-non-security-updates"></a><span data-ttu-id="44499-1824">Outlook：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1824">Outlook: Non-security updates</span></span> 

- <span data-ttu-id="44499-1825">這項改變可讓使用者將所有的實體檔案儲存到網路共用，包括對應的網路磁碟機。</span><span class="sxs-lookup"><span data-stu-id="44499-1825">This change allows users to Save All for physical files to a network share, including a mapped network drive.</span></span> 

## <a name="version-1708-november-13"></a><span data-ttu-id="44499-1826">版本 1708：11 月 13 日</span><span class="sxs-lookup"><span data-stu-id="44499-1826">Version 1708: November 13</span></span>
<span data-ttu-id="44499-1827">*版本 1708 (組建 8431.2329)*</span><span class="sxs-lookup"><span data-stu-id="44499-1827">*Version 1708 (Build 8431.2329)*</span></span>

<span data-ttu-id="44499-1828">*這是自從 2018 年 1 月以來提供的半年通道版本。它會繼續受到支援並接收安全性更新，直到 2019 年 3 月為止。不過，目前已提供新的半年通道版本 — 版本 1803 (組建 16.0.9126.2315) — 其中包含了新功能、安全性更新和非安全性更新。*</span><span class="sxs-lookup"><span data-stu-id="44499-1828">*This is the Semi-Annual Channel release that's been available since January 2018. It will continue to be supported and receive security updates until March 2019. But, a new Semi-Annual Channel release is now available — Version 1803 (Build 16.0.9126.2315) — which contains new features, security updates, and non-security updates.*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="44499-1829">Excel：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1829">Excel: Security updates</span></span>

-   <span data-ttu-id="44499-1830">[CVE-2018-8574](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8574)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1830">[CVE-2018-8574](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8574): Microsoft Excel Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="44499-1831">[CVE-2018-8577](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8577)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1831">[CVE-2018-8577](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8577): Microsoft Excel Remote Code Execution Vulnerability</span></span> 

### <a name="outlook-security-updates"></a><span data-ttu-id="44499-1832">Outlook：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1832">Outlook: Security updates</span></span> 

-   <span data-ttu-id="44499-1833">[CVE-2018-8522](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8522)：Microsoft Outlook 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1833">[CVE-2018-8522](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8522): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="44499-1834">[CVE-2018-8524](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8524)：Microsoft Outlook 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1834">[CVE-2018-8524](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8524): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="44499-1835">[CVE-2018-8558](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8558)：Microsoft Outlook 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1835">[CVE-2018-8558](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8558): Microsoft Outlook Information Disclosure Vulnerability</span></span> 
-   <span data-ttu-id="44499-1836">[CVE-2018-8576](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8576)：Microsoft Outlook 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1836">[CVE-2018-8576](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8576): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="44499-1837">[CVE-2018-8579](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8579)：Microsoft Outlook 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1837">[CVE-2018-8579](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8579): Microsoft Outlook Information Disclosure Vulnerability</span></span> 
-   <span data-ttu-id="44499-1838">[CVE-2018-8582](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8582)：Microsoft Outlook 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1838">[CVE-2018-8582](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8582): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 

### <a name="project-security-updates"></a><span data-ttu-id="44499-1839">Project：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1839">Project: Security updates</span></span> 

-   <span data-ttu-id="44499-1840">[CVE-2018-8575](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8575)：Microsoft Project 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1840">[CVE-2018-8575](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8575): Microsoft Project Remote Code Execution Vulnerability</span></span> 

### <a name="word-security-updates"></a><span data-ttu-id="44499-1841">Word：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1841">Word: Security updates</span></span> 

-   <span data-ttu-id="44499-1842">[CVE-2018-8573](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8573)：Microsoft Word 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1842">[CVE-2018-8573](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8573): Microsoft Word Remote Code Execution Vulnerability</span></span> 

### <a name="skype-for-business-security-updates"></a><span data-ttu-id="44499-1843">商務用 Skype：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1843">Skype for Business: Security updates</span></span> 

-   <span data-ttu-id="44499-1844">[CVE-2018-8546](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8546)：Microsoft 商務用 Skype 阻絕服務弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1844">[CVE-2018-8546](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8546): Microsoft Skype for Business Denial of Service Vulnerability</span></span> 

### <a name="outlook-non-security-updates"></a><span data-ttu-id="44499-1845">Outlook：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1845">Outlook: Non-security updates</span></span> 

- <span data-ttu-id="44499-1846">這項改變可讓使用者將所有的實體檔案儲存到網路共用，包括對應的網路磁碟機。</span><span class="sxs-lookup"><span data-stu-id="44499-1846">This change allows users to Save All for physical files to a network share, including a mapped network drive.</span></span> 


## <a name="version-1803-october-9"></a><span data-ttu-id="44499-1847">版本 1803：10 月 9 日</span><span class="sxs-lookup"><span data-stu-id="44499-1847">Version 1803: October 9</span></span>
<span data-ttu-id="44499-1848">*版本 1803 (組建 9126.2295)*</span><span class="sxs-lookup"><span data-stu-id="44499-1848">*Version 1803 (Build 9126.2295)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="44499-1849">Excel：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1849">Excel: Security updates</span></span>
-   <span data-ttu-id="44499-1850">[CVE-2018-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8502)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1850">[CVE-2018-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8502): Microsoft Excel Remote Code Execution Vulnerability</span></span> 

### <a name="outlook-security-updates"></a><span data-ttu-id="44499-1851">Outlook：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1851">Outlook: Security updates</span></span> 
-   <span data-ttu-id="44499-1852">[ADV180026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180026)：Microsoft Office 深度防禦更新</span><span class="sxs-lookup"><span data-stu-id="44499-1852">[ADV180026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180026): Microsoft Office Defense in Depth Update</span></span> 

### <a name="powerpoint-security-updates"></a><span data-ttu-id="44499-1853">PowerPoint：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1853">PowerPoint: Security updates</span></span> 
-   <span data-ttu-id="44499-1854">[CVE-2018-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8501)：Microsoft PowerPoint 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1854">[CVE-2018-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8501): Microsoft PowerPoint Remote Code Execution Vulnerability</span></span>

### <a name="word-security-updates"></a><span data-ttu-id="44499-1855">Word：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1855">Word: Security updates</span></span> 
-   <span data-ttu-id="44499-1856">[CVE-2018-8504](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8504)：Microsoft Word 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1856">[CVE-2018-8504](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8504): Microsoft Word Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="44499-1857">[ADV180026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180026)：Microsoft Office 深度防禦更新</span><span class="sxs-lookup"><span data-stu-id="44499-1857">[ADV180026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180026): Microsoft Office Defense in Depth Update</span></span> 

### <a name="office-suite-security-updates"></a><span data-ttu-id="44499-1858">Office 套件：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1858">Office suite: Security updates</span></span> 
-   <span data-ttu-id="44499-1859">[CVE-2018-8432](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8432)：Microsoft Graphics 元件遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1859">[CVE-2018-8432](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8432): Microsoft Graphics Components Remote Code Execution Vulnerability</span></span> 

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="44499-1860">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1860">Office Suite: Non-Security updates</span></span>
-   <span data-ttu-id="44499-1861">修正了儘管已透過協助功能和效能設定關閉動畫後，應用程式仍會顯示動畫的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1861">Fixed issue of apps showing animations despite turning off animations through accessibility and performance settings.</span></span>
-   <span data-ttu-id="44499-1862">修正了使用螢光筆繪圖工具時背景變為空白的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1862">Fixed issue of background turning blank when using highlighter drawing tool.</span></span>

## <a name="version-1708-october-9"></a><span data-ttu-id="44499-1863">版本 1708：10 月 9 日</span><span class="sxs-lookup"><span data-stu-id="44499-1863">Version 1708: October 9</span></span>
<span data-ttu-id="44499-1864">*版本 1708 (組建 8431.2316)*</span><span class="sxs-lookup"><span data-stu-id="44499-1864">*Version 1708 (Build 8431.2316)*</span></span>

<span data-ttu-id="44499-1865">*這是自從 2018 年 1 月以來提供的半年通道版本。它會繼續受到支援並接收安全性更新，直到 2019 年 3 月為止。不過，目前已提供新的半年通道版本 — 版本 1803 (組建 16.0.9126.2282) — 其中包含了新功能、安全性更新和非安全性更新。*</span><span class="sxs-lookup"><span data-stu-id="44499-1865">*This is the Semi-Annual Channel release that's been available since January 2018. It will continue to be supported and receive security updates until March 2019. But, a new Semi-Annual Channel release is now available — Version 1803 (Build 16.0.9126.2282) — which contains new features, security updates, and non-security updates.*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="44499-1866">Excel：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1866">Excel: Security updates</span></span>
-   <span data-ttu-id="44499-1867">[CVE-2018-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8502)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1867">[CVE-2018-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8502): Microsoft Excel Remote Code Execution Vulnerability</span></span> 

### <a name="outlook-security-updates"></a><span data-ttu-id="44499-1868">Outlook：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1868">Outlook: Security updates</span></span> 
-   <span data-ttu-id="44499-1869">[ADV180026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180026)：Microsoft Office 深度防禦更新</span><span class="sxs-lookup"><span data-stu-id="44499-1869">[ADV180026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180026): Microsoft Office Defense in Depth Update</span></span> 

### <a name="powerpoint-security-updates"></a><span data-ttu-id="44499-1870">PowerPoint：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1870">PowerPoint: Security updates</span></span> 
-   <span data-ttu-id="44499-1871">[CVE-2018-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8501)：Microsoft PowerPoint 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1871">[CVE-2018-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8501): Microsoft PowerPoint Remote Code Execution Vulnerability</span></span>

### <a name="word-security-updates"></a><span data-ttu-id="44499-1872">Word：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1872">Word: Security updates</span></span> 
-   <span data-ttu-id="44499-1873">[CVE-2018-8504](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8504)：Microsoft Word 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1873">[CVE-2018-8504](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8504): Microsoft Word Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="44499-1874">[ADV180026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180026)：Microsoft Office 深度防禦更新</span><span class="sxs-lookup"><span data-stu-id="44499-1874">[ADV180026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180026): Microsoft Office Defense in Depth Update</span></span> 

### <a name="office-suite-security-updates"></a><span data-ttu-id="44499-1875">Office 套件：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1875">Office suite: Security updates</span></span> 
-   <span data-ttu-id="44499-1876">[CVE-2018-8432](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8432)：Microsoft Graphics 元件遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1876">[CVE-2018-8432](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8432): Microsoft Graphics Components Remote Code Execution Vulnerability</span></span> 


## <a name="version-1803-september-11"></a><span data-ttu-id="44499-1877">版本 1803：9 月 11 日</span><span class="sxs-lookup"><span data-stu-id="44499-1877">Version 1803: September 11</span></span>
<span data-ttu-id="44499-1878">*版本 1803 (組建 9126.2282)*</span><span class="sxs-lookup"><span data-stu-id="44499-1878">*Version 1803 (Build 9126.2282)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="44499-1879">Excel：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1879">Excel: Security updates</span></span>
-   <span data-ttu-id="44499-1880">[CVE-2018-8331](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8331)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1880">[CVE-2018-8331](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8331): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-1881">[CVE-2018-8429](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8429)：Microsoft Excel 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1881">[CVE-2018-8429](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8429): Microsoft Excel Information Disclosure Vulnerability</span></span>

### <a name="word-security-updates"></a><span data-ttu-id="44499-1882">Word：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1882">Word: Security updates</span></span>
-   <span data-ttu-id="44499-1883">[CVE-2018-8430](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8430)：Windows PDF 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1883">[CVE-2018-8430](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8430): Word PDF Remote Code Execution Vulnerability</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="44499-1884">Office 套件：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1884">Office suite: Security updates</span></span>
-   <span data-ttu-id="44499-1885">[CVE-2018-8332](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8332)：Win32k 圖形遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1885">[CVE-2018-8332](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8332): Win32k Graphics Remote Code Execution Vulnerability</span></span>


## <a name="version-1708-september-11"></a><span data-ttu-id="44499-1886">版本 1708：9 月 11 日</span><span class="sxs-lookup"><span data-stu-id="44499-1886">Version 1708: September 11</span></span>
<span data-ttu-id="44499-1887">*版本 1708 (組建 8431.2309)*</span><span class="sxs-lookup"><span data-stu-id="44499-1887">*Version 1708 (Build 8431.2309)*</span></span>

<span data-ttu-id="44499-1888">*這是自從 2018 年 1 月以來提供的半年通道版本。它會繼續受到支援並接收安全性更新，直到 2019 年 3 月為止。不過，目前已提供新的半年通道版本 — 版本 1803 (組建 16.0.9126.2282) — 其中包含了新功能、安全性更新和非安全性更新。*</span><span class="sxs-lookup"><span data-stu-id="44499-1888">*This is the Semi-Annual Channel release that's been available since January 2018. It will continue to be supported and receive security updates until March 2019. But, a new Semi-Annual Channel release is now available — Version 1803 (Build 16.0.9126.2282) — which contains new features, security updates, and non-security updates.*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="44499-1889">Excel：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1889">Excel: Security updates</span></span>
-   <span data-ttu-id="44499-1890">[CVE-2018-8331](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8331)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1890">[CVE-2018-8331](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8331): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-1891">[CVE-2018-8429](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8429)：Microsoft Excel 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1891">[CVE-2018-8429](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8429): Microsoft Excel Information Disclosure Vulnerability</span></span>

### <a name="word-security-updates"></a><span data-ttu-id="44499-1892">Word：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1892">Word: Security updates</span></span>
-   <span data-ttu-id="44499-1893">[CVE-2018-8430](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8430)：Windows PDF 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1893">[CVE-2018-8430](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8430): Word PDF Remote Code Execution Vulnerability</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="44499-1894">Office 套件：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1894">Office suite: Security updates</span></span>
-   <span data-ttu-id="44499-1895">[CVE-2018-8332](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8332)：Win32k 圖形遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1895">[CVE-2018-8332](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8332): Win32k Graphics Remote Code Execution Vulnerability</span></span>


## <a name="version-1803-august-14"></a><span data-ttu-id="44499-1896">版本 1803：8 月 14 日</span><span class="sxs-lookup"><span data-stu-id="44499-1896">Version 1803: August 14</span></span>
<span data-ttu-id="44499-1897">*版本 1803 (組建 9126.2275)*</span><span class="sxs-lookup"><span data-stu-id="44499-1897">*Version 1803 (Build 9126.2275)*</span></span>

### <a name="access-security-updates"></a><span data-ttu-id="44499-1898">Access：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1898">Access: Security updates</span></span>
-   <span data-ttu-id="44499-1899">[CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312)：Microsoft Access 遠端程式碼執行 Use After Free 弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1899">[CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312): Microsoft Access Remote Code Execution Use After Free Vulnerability</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="44499-1900">Excel：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1900">Excel: Security updates</span></span>
-   <span data-ttu-id="44499-1901">[CVE-2018-8375](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8375)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1901">[CVE-2018-8375](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8375): Microsoft Excel Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="44499-1902">[CVE-2018-8379](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8379)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1902">[CVE-2018-8379](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8379): Microsoft Excel Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="44499-1903">[CVE-2018-8382](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8382)：Microsoft Excel 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1903">[CVE-2018-8382](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8382): Microsoft Excel Information Disclosure Vulnerability</span></span> 

### <a name="outlook-security-updates"></a><span data-ttu-id="44499-1904">Outlook：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1904">Outlook: Security updates</span></span>
-   <span data-ttu-id="44499-1905">[ADV180021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180021)：Microsoft Office 深度防禦更新</span><span class="sxs-lookup"><span data-stu-id="44499-1905">[ADV180021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180021): Microsoft Office Defense in Depth Update</span></span> 

### <a name="office-suite-security-updates"></a><span data-ttu-id="44499-1906">Office 套件：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1906">Office Suite: Security updates</span></span>
-   <span data-ttu-id="44499-1907">[CVE-2018-8378](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8378)：Microsoft Office 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1907">[CVE-2018-8378](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8378): Microsoft Office Information Disclosure Vulnerability</span></span> 


## <a name="version-1708-august-14"></a><span data-ttu-id="44499-1908">版本 1708：8 月 14 日</span><span class="sxs-lookup"><span data-stu-id="44499-1908">Version 1708: August 14</span></span>
<span data-ttu-id="44499-1909">*版本 1708 (組建 8431.2299)*</span><span class="sxs-lookup"><span data-stu-id="44499-1909">*Version 1708 (Build 8431.2299)*</span></span>

<span data-ttu-id="44499-1910">*這是自從 2018 年 1 月以來提供的半年通道版本。它會繼續受到支援並接收安全性更新，直到 2019 年 3 月為止。不過，目前已提供新的半年通道版本 — 版本 1803 (組建 16.0.9126.2275) — 其中包含了新功能、安全性更新和非安全性更新。*</span><span class="sxs-lookup"><span data-stu-id="44499-1910">*This is the Semi-Annual Channel release that's been available since January 2018. It will continue to be supported and receive security updates until March 2019. But, a new Semi-Annual Channel release is now available — Version 1803 (Build 16.0.9126.2275) — which contains new features, security updates, and non-security updates.*</span></span>

### <a name="access-security-updates"></a><span data-ttu-id="44499-1911">Access：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1911">Access: Security updates</span></span>
-   <span data-ttu-id="44499-1912">[CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312)：Microsoft Access 遠端程式碼執行 Use After Free 弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1912">[CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312): Microsoft Access Remote Code Execution Use After Free Vulnerability</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="44499-1913">Excel：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1913">Excel: Security updates</span></span>
-   <span data-ttu-id="44499-1914">[CVE-2018-8375](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8375)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1914">[CVE-2018-8375](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8375): Microsoft Excel Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="44499-1915">[CVE-2018-8379](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8379)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1915">[CVE-2018-8379](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8379): Microsoft Excel Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="44499-1916">[CVE-2018-8382](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8382)：Microsoft Excel 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1916">[CVE-2018-8382](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8382): Microsoft Excel Information Disclosure Vulnerability</span></span> 

### <a name="outlook-security-updates"></a><span data-ttu-id="44499-1917">Outlook：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1917">Outlook: Security updates</span></span>
-   <span data-ttu-id="44499-1918">[ADV180021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180021)：Microsoft Office 深度防禦更新</span><span class="sxs-lookup"><span data-stu-id="44499-1918">[ADV180021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180021): Microsoft Office Defense in Depth Update</span></span> 

### <a name="office-suite-security-updates"></a><span data-ttu-id="44499-1919">Office 套件：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1919">Office Suite: Security updates</span></span>
-   <span data-ttu-id="44499-1920">[CVE-2018-8378](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8378)：Microsoft Office 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1920">[CVE-2018-8378](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8378): Microsoft Office Information Disclosure Vulnerability</span></span> 


## <a name="version-1803-july-10"></a><span data-ttu-id="44499-1921">版本 1803：7 月 10 日</span><span class="sxs-lookup"><span data-stu-id="44499-1921">Version 1803: July 10</span></span>
<span data-ttu-id="44499-1922">*版本 1803 (組建 9126.2259)*</span><span class="sxs-lookup"><span data-stu-id="44499-1922">*Version 1803 (Build 9126.2259)*</span></span>

### <a name="access-security-updates"></a><span data-ttu-id="44499-1923">Access：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1923">Access: Security updates</span></span>
-   <span data-ttu-id="44499-1924">[CVE-2018-0903](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0903)：Microsoft Access 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1924">[CVE-2018-0903](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0903): Microsoft Access Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-1925">[CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312)：Microsoft Access 遠端程式碼執行 Use After Free 弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1925">[CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312): Microsoft Access Remote Code Execution Use After Free Vulnerability</span></span> 

### <a name="access-non-security-updates"></a><span data-ttu-id="44499-1926">Access：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1926">Access: Non-security updates</span></span>
-   <span data-ttu-id="44499-1927">修正此問題：開啟 Access 執行階段應用程式 (.accde 檔案) 會導致「無法辨認此資料庫格式」錯誤訊息，且應用程式不會開啟。</span><span class="sxs-lookup"><span data-stu-id="44499-1927">Fix an issue where opening an Access runtime application (.accde file) results in a "This database is in an unrecognized format" error message and the application won’t open.</span></span>
-   <span data-ttu-id="44499-1928">修正此問題：嘗試在文字方塊或下拉式方塊中選取文字似乎會選取所有文字，而不是表示選取範圍。</span><span class="sxs-lookup"><span data-stu-id="44499-1928">Fix an issue where attempting to select text in a text box or combo box appears to select all the text, rather than the indication selection.</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="44499-1929">Excel：功能更新</span><span class="sxs-lookup"><span data-stu-id="44499-1929">Excel: Feature updates</span></span>
-   <span data-ttu-id="44499-p304">**Microsoft Translator：** 使用 Microsoft Translator 可將單字、片語或句子翻譯成另一種語言。您可以從功能區中的 [校閱] 索引標籤使用此功能。</span><span class="sxs-lookup"><span data-stu-id="44499-p304">**Microsoft Translator:** Translate words, phrases or sentences to another language with Microsoft Translator. You can do this from the Review tab in the ribbon.</span></span>
-   <span data-ttu-id="44499-1932">**將 SVG 圖示轉換成圖形：** 將所有 SVG 圖片和圖示轉換成 Office 圖形，讓您可以變更其色彩、大小或材質。</span><span class="sxs-lookup"><span data-stu-id="44499-1932">**Convert SVG icons to shapes:** Transform all SVG pictures and icons into Office shapes so you can change their color, size, or texture.</span></span>
-   <span data-ttu-id="44499-1933">**取消選取儲存格：** 在工作表中進行選取，並取消選取不小心按到的儲存格而不必重新開始。</span><span class="sxs-lookup"><span data-stu-id="44499-1933">**Deselect cells:** Make selections in your worksheet and deselect cells that you accidentally clicked without having to start over.</span></span>
-   <span data-ttu-id="44499-1934">**快速存取您的網站和群組︰** 您可以使用 [檔案] 功能表，使用儲存在您常用的網站和群組中的文件。</span><span class="sxs-lookup"><span data-stu-id="44499-1934">**Quickly access your sites and groups:** Use the File menu to work with documents stored in your frequently used sites and groups.</span></span>
-   <span data-ttu-id="44499-p305">**數位鉛筆：** 使用新的鉛筆紋理手寫或繪製出您的創意。只需傾斜即可使用支援的數位鉛筆進行陰影處理。</span><span class="sxs-lookup"><span data-stu-id="44499-p305">**Digital Pencil:** Write or sketch out ideas with our new pencil texture. Simply tilt to do shading with supported digital pens.</span></span>
-   <span data-ttu-id="44499-p306">**LinkedIn 功能設定：** 移至 [檔案] \> [選項] \> [一般]，以控制 LinkedIn 功能是否要顯示在您的 Office 應用程式中。[深入了解](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)</span><span class="sxs-lookup"><span data-stu-id="44499-p306">**LinkedIn features setting:** Go to File \> Options \> General to control whether LinkedIn features are shown in your Office applications. [Learn more](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)</span></span>
-   <span data-ttu-id="44499-p307">**3D 模型：** 使用 3D 來增加活頁簿的視覺效果和創意影響。輕鬆插入 3D 模型，然後將其旋轉 360 度。 [深入了解](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)</span><span class="sxs-lookup"><span data-stu-id="44499-p307">**3D models:** Use 3D to increase the visual and creative impact of your workbooks.  Easily insert a 3D model, then you can rotate it through 360 degrees. [Learn more](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)</span></span>
-   <span data-ttu-id="44499-1942">**新的筆跡效果：** 使用金屬畫筆和筆跡效果 (如彩虹、星空、熔岩、海洋、黃金、銀等) 來展現您的想法。</span><span class="sxs-lookup"><span data-stu-id="44499-1942">**New ink effects:** Express your ideas with flair using metallic pens and ink effects like rainbow, galaxy, lava, ocean, gold, silver and more.</span></span>
-   <span data-ttu-id="44499-p308">**共用檔案 UI：** 對於商務用 OneDrive 或 SharePoint 檔案，按一下功能區右上角的 [共用] 按鈕，或移至 [檔案] \> [共用] 可啟動經簡化並改良過的 [共用] 對話方塊。對於新的或儲存在本機的檔案，該 UI 可讓使用者輕鬆地將檔案上傳至 OneDrive 以啟動共同作業。</span><span class="sxs-lookup"><span data-stu-id="44499-p308">**Sharing files UI:** For OneDrive for Business or SharePoint files, clicking the Share button in the upper right-hand corner of the ribbon or going to File \> Share launches a simplified and improved Share dialog. For new or locally-saved files, the UI allows users to easily upload their files to OneDrive to start collaborating.</span></span>
-   <span data-ttu-id="44499-p309">**封鎖危險的副檔名：** 依預設，視為具有高風險以及內嵌為 OLE 封裝物件的副檔名 (例如.exe、.vbs 和 .js)，會遭到封鎖而無法啟動。[深入了解](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span><span class="sxs-lookup"><span data-stu-id="44499-p309">**Block dangerous extensions:** Extensions that are considered to be high risk, and are embedded as OLE package objects, are blocked, by default, from activating. For example, .exe, .vbs, and .js. [Learn more](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span></span>
-   <span data-ttu-id="44499-p310">**有用的聲音可改善協助工具：** 開啟音訊提示可在作業時一面引導您。可在 [檔案] \> [選項] \> [輕鬆存取] 中找到此功能。無需增益集。 [深入了解](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)</span><span class="sxs-lookup"><span data-stu-id="44499-p310">**Helpful sounds improve accessibility:** Turn on audio cues to guide you as you work. Find it in File \> Options \> Ease of Access. No add-in needed. [Learn more](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)</span></span>
-   <span data-ttu-id="44499-1952">**依帳戶的檔案位置：** 開啟或儲存檔案時，位置清單會依照與其相關聯的帳戶整理。</span><span class="sxs-lookup"><span data-stu-id="44499-1952">**File locations by account:** When opening or saving a file, the list of places is organized by the account associated with them.</span></span>
-   <span data-ttu-id="44499-p311">**畫筆自訂：** 針對筆跡選擇畫筆和螢光筆的個人集合。您的自訂集可在您所有的 Windows 電腦上使用。</span><span class="sxs-lookup"><span data-stu-id="44499-p311">**Pen customization:** Choose a personal set of pens and highlighters for inking. Your customized set is available on all your Windows PCs.</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="44499-1955">Excel：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1955">Excel: Security updates</span></span>
-   <span data-ttu-id="44499-1956">[CVE-2017-11877](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11877)：Microsoft Excel 安全性功能略過的弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1956">[CVE-2017-11877](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11877): Microsoft Excel Security Feature Bypass Vulnerability</span></span>
-   <span data-ttu-id="44499-1957">[CVE-2017-11878](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11878)：Microsoft Excel 記憶體損毀弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1957">[CVE-2017-11878](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11878): Microsoft Excel Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="44499-1958">[CVE-2017-11884](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11884)：Microsoft Office 記憶體損毀弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1958">[CVE-2017-11884](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11884): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="44499-1959">[CVE-2018-0796](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0796)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1959">[CVE-2018-0796](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0796): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-1960">[CVE-2018-0841](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0841)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1960">[CVE-2018-0841](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0841): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-1961">[CVE-2018-0907](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0907)：Microsoft Office Excel 安全性功能略過</span><span class="sxs-lookup"><span data-stu-id="44499-1961">[CVE-2018-0907](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0907): Microsoft Office Excel Security Feature Bypass</span></span>
-   <span data-ttu-id="44499-1962">[CVE-2018-1029](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1029)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1962">[CVE-2018-1029](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1029): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-1963">[CVE-2018-8147](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8147)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1963">[CVE-2018-8147](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8147): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-1964">[CVE-2018-8148](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8148)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1964">[CVE-2018-8148](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8148): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-1965">[CVE-2018-8162](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8162)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1965">[CVE-2018-8162](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8162): Microsoft Excel Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="44499-1966">[CVE-2018-8163](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8163)：Microsoft Excel 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1966">[CVE-2018-8163](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8163): Microsoft Excel Information Disclosure Vulnerability</span></span> 
-   <span data-ttu-id="44499-1967">[CVE-2018-8246](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8246)：Microsoft Excel 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1967">[CVE-2018-8246](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8246): Microsoft Excel Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="44499-1968">[CVE-2018-8248](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0907)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-1968">[CVE-2018-8248](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0907): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-1969">[CVE-2018-0907](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0907)：Microsoft Office Excel 安全性功能略過</span><span class="sxs-lookup"><span data-stu-id="44499-1969">[CVE-2018-0907](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0907): Microsoft Office Excel Security Feature Bypass</span></span>
-   <span data-ttu-id="44499-1970">[Advisory 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021)：Microsoft Office 深度防禦更新</span><span class="sxs-lookup"><span data-stu-id="44499-1970">[Advisory 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021): Microsoft Office Defense in Depth Update</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="44499-1971">Excel：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-1971">Excel: Non-security updates</span></span>

-   <span data-ttu-id="44499-1972">修正此問題：在日期儲存格格式使用日本紀元日曆時顯示錯誤年份。</span><span class="sxs-lookup"><span data-stu-id="44499-1972">Fix an issue where the wrong year is shown when Japanese Era calendar is used in date cell format.</span></span>
-   <span data-ttu-id="44499-p312">當資料匯入 Excel 資料模型中，負值或零的輸入值會造成錯誤。此修正會將此類的值匯入為零。</span><span class="sxs-lookup"><span data-stu-id="44499-p312">When importing data into the Excel Data Model, incoming values of negative zero would result in an error.  The fix imports such values as zero.</span></span>
-   <span data-ttu-id="44499-1975">修正 Excel 樞紐分析表中的群組 (或取消群組) 作業有時候會觸發當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-1975">Fix an issue where a group (or ungroup) operation in an Excel PivotTable could sometimes trigger a crash.</span></span>
-   <span data-ttu-id="44499-1976">修正此問題：在圖表上動作可能會造成 Excel 當機。</span><span class="sxs-lookup"><span data-stu-id="44499-1976">Fix an issue where charting actions could cause Excel to crash.</span></span>
-   <span data-ttu-id="44499-1977">修正此問題：部分使用者不小心停用 Power View 增益集。</span><span class="sxs-lookup"><span data-stu-id="44499-1977">Fix an issue where the Power View add-in is inadvertently disabled for some users.</span></span>
-   <span data-ttu-id="44499-1978">修正此問題：在文件復原期間建立的暫時自動復原檔案永遠不會清除。</span><span class="sxs-lookup"><span data-stu-id="44499-1978">Fix an issue where temporary auto-recovery files created during document recovery are never cleaned up.</span></span>
-   <span data-ttu-id="44499-1979">修正此問題：Excel 在從 SharePoint Online 開啟檔案時損毀。</span><span class="sxs-lookup"><span data-stu-id="44499-1979">Fix an issue where Excel crashes when opening a file from SharePoint Online.</span></span>
-   <span data-ttu-id="44499-1980">修正此問題：快速列印附加至 Outlook 電子郵件的 Excel 活頁簿可能會列印不出來。</span><span class="sxs-lookup"><span data-stu-id="44499-1980">Fix an issue where Quick Print of an Excel workbook attached to an Outlook email may not print.</span></span>
-   <span data-ttu-id="44499-1981">修正此問題：按一下超連結可能會造成 Excel 當機。</span><span class="sxs-lookup"><span data-stu-id="44499-1981">Fix an issue where clicking on a hyperlink may cause Excel to crash.</span></span>
-   <span data-ttu-id="44499-1982">修正此問題：使用 cube 函式會造成 Excel 當機。</span><span class="sxs-lookup"><span data-stu-id="44499-1982">Fix an issue where using cube functions causes Excel to crash.</span></span>
-   <span data-ttu-id="44499-1983">修正此問題，列印或預覽列印時，只列印或顯示了工作表中的一部分，內容被截斷為工作表上的交叉分析篩選器。</span><span class="sxs-lookup"><span data-stu-id="44499-1983">Fix a problem where print or print preview only prints or displays a portion of the worksheet, with the content being truncated at a slicer on the worksheet.</span></span>
-   <span data-ttu-id="44499-1984">修正此問題：在嘗試與受保護活頁簿中的文字檔建立新連線時，收到「活頁簿受到保護，且無法變更」錯誤訊息。修正此問題：如果您的編輯語言是日文、中文或韓文，則當您嘗試在 [首頁] 索引標籤上選取新字型時，或當編輯時，Excel 可能會凍結。</span><span class="sxs-lookup"><span data-stu-id="44499-1984">Fix an issue where attempting to make a new connection to a text file in a protected workbook results in getting a "Workbook is protected and cannot be changed" error message.Fix an issue where, if your editing language is Japanese, Chinese, or Korean, Excel may freeze when you try to choose a new font on the Home tab or when you edit.</span></span>
-   <span data-ttu-id="44499-1985">修正此問題：當 Excel 最小化時，開啟活頁簿時捲軸會遺失。</span><span class="sxs-lookup"><span data-stu-id="44499-1985">Fix an issue where the scroll bars are missing when a workbook is opened when Excel is minimized.</span></span>
-   <span data-ttu-id="44499-1986">修正此問題：在 [檔案總管] 中的檔案名稱上按兩下以開啟多個活頁簿時，活頁簿參照會失敗。</span><span class="sxs-lookup"><span data-stu-id="44499-1986">Fix an issue where workbook references fail when opening multiple workbooks by double-clicking on the file names in File Explorer.</span></span>
-   <span data-ttu-id="44499-1987">修正此問題：以程式設計方式建立樞紐分析表，接著以程式設計方式重新整理，會造成 Excel 當機。</span><span class="sxs-lookup"><span data-stu-id="44499-1987">Fix an issue where the programmatic creation of a PivotTable followed by a programmatic refresh causes Excel to crash.</span></span>
-   <span data-ttu-id="44499-1988">修正此問題：以程式設計方式呼叫 Workbook.Open() 可能會造成 Excel 當機。</span><span class="sxs-lookup"><span data-stu-id="44499-1988">Fix an issue where programmatically calling Workbook.Open() may cause Excel to crash.</span></span>
-   <span data-ttu-id="44499-1989">修正此問題：使用者使用巨集開啟 Office 2007 或較舊的活頁簿 (.xls 或 .xla) 時，會看到不正確的「重大失敗」錯誤訊息。</span><span class="sxs-lookup"><span data-stu-id="44499-1989">Fix an issue where the user incorrectly sees a "catastrophic failure" error message when opening an Office 2007 or older workbook (.xls or .xla) with macros.</span></span>
-   <span data-ttu-id="44499-1990">修正此問題：使用者開啟內容功能表時，Excel 可能會當機。</span><span class="sxs-lookup"><span data-stu-id="44499-1990">Fix an issue where Excel might crash when a user opens a context menu.</span></span>
-   <span data-ttu-id="44499-1991">修正此問題：當使用者嘗試在現有的活頁簿中插入物件時，Excel 會在使用者按一下 [瀏覽] 時損毀。</span><span class="sxs-lookup"><span data-stu-id="44499-1991">Fix an issue where, when the user tries to insert an object in an existing workbook, Excel crashes when the user clicks Browse.</span></span>
-   <span data-ttu-id="44499-1992">修正此問題：使用密碼保護一個範圍時，看不到要輸入密碼以解鎖範圍的對話方塊。</span><span class="sxs-lookup"><span data-stu-id="44499-1992">Fix an issue where, when protecting a range with a password, the dialog box to enter the password to unlock the range isn't visible.</span></span>
-   <span data-ttu-id="44499-1993">修正此問題：在檔案名稱包含方括弧時，使用者無法在受保護的檢視中關閉活頁簿。</span><span class="sxs-lookup"><span data-stu-id="44499-1993">Fix an issue where the user can't close a workbook in protected view when the file name contains square brackets.</span></span>
-   <span data-ttu-id="44499-1994">修正此問題：在拖曳或拖曳填滿時，工具提示的放置位置沒有對齊。</span><span class="sxs-lookup"><span data-stu-id="44499-1994">Fix an issue where placement of the tooltip is misaligned when dragging or drag filling.</span></span>
-   <span data-ttu-id="44499-1995">修正此問題：使用 [檔案] \> [另存新檔] 來儲存活頁簿時，包含句點的檔案名稱在檔案儲存對話方塊中會出現空白或截斷。</span><span class="sxs-lookup"><span data-stu-id="44499-1995">Fix an issue where, when saving a workbook by using File \> Save As, a file name that contains periods appears blank or truncated in the file save dialog.</span></span>
-   <span data-ttu-id="44499-p313">修正此問題：正在儲存同步備份檔案時，Office 無法寫入磁碟，但 Office 會不斷上傳檔案到 OneDrive。有了此修正程式之後，使用者現在會看到一則錯誤訊息，且 Office 不會繼續上傳。</span><span class="sxs-lookup"><span data-stu-id="44499-p313">Fix an issue where, when saving a sync-backed file, Office fails to write to disk, but Office keeps uploading the file to OneDrive. With this fix, user will now see an error message and the upload won't proceed.</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="44499-1998">Outlook：功能更新</span><span class="sxs-lookup"><span data-stu-id="44499-1998">Outlook: Feature updates</span></span>
-   <span data-ttu-id="44499-1999">**輕鬆地排序您的電子郵件：** 由於您的意見反應，我們已為不使用 [焦點收件匣] 的使用者，重新加入了郵件清單上方的排序功能和 [未讀取] 篩選器。</span><span class="sxs-lookup"><span data-stu-id="44499-1999">**Sort your email with ease:** Thanks to your feedback, we've brought back sorting above the message list and the Unread filter for people who don't use Focused Inbox.</span></span>
-   <span data-ttu-id="44499-2000">**將 SVG 圖示轉換成圖形：** 將所有 SVG 圖片和圖示轉換成 Office 圖形，讓您可以變更其色彩、大小或材質。</span><span class="sxs-lookup"><span data-stu-id="44499-2000">**Convert SVG icons to shapes:** Transform all SVG pictures and icons into Office shapes so you can change their color, size, or texture.</span></span>
-   <span data-ttu-id="44499-2001">**Office 365 群組的改善︰** 您可以在群組訊息上按兩下，開啟其個別視窗，這讓您更加容易閱讀和回覆群組對話。</span><span class="sxs-lookup"><span data-stu-id="44499-2001">**Improvements to Office 365 groups:** It’s easier than ever to read and reply to group conversations because you can double-click on a group message to open it in its own window.</span></span>
-   <span data-ttu-id="44499-p314">**LinkedIn 功能設定：** 移至 [檔案] \> [選項] \> [一般]，以控制 LinkedIn 功能是否要顯示在您的 Office 應用程式中。[深入了解](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)</span><span class="sxs-lookup"><span data-stu-id="44499-p314">**LinkedIn features setting:** Go to File \> Options \> General to control whether LinkedIn features are shown in your Office applications. [Learn more](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)</span></span>
-   <span data-ttu-id="44499-p315">**3D 模型：** 使用 3D 來增加電子郵件的視覺效果和創意影響。輕鬆插入 3D 模型，然後將其旋轉 360 度。 [深入了解](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)</span><span class="sxs-lookup"><span data-stu-id="44499-p315">**3D models:** Use 3D to increase the visual and creative impact of your email.  Easily insert a 3D model, then you can rotate it through 360 degrees. [Learn more](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)</span></span>
-   <span data-ttu-id="44499-2007">**個人檔案卡片：** 無論您是使用桌面應用程式、Web 應用程式或行動應用程式，都能顯示有關人員和群組的最相關詳細資料。</span><span class="sxs-lookup"><span data-stu-id="44499-2007">**Profile card:** Shows you the most relevant details about people and groups, whether you’re on the desktop, the web, or using a mobile app.</span></span>
-   <span data-ttu-id="44499-2008">**在群組行事曆中新增約會：** 現在，您可以讓群組中的每個人都知道您何時會離開，而不需要以電子郵件傳送會議。</span><span class="sxs-lookup"><span data-stu-id="44499-2008">**Add an appointment to a group calendar:** Now you can let everyone in your group know when you’ll be away without sending a meeting in email.</span></span>
-   <span data-ttu-id="44499-2009">**下載雲端附件：** 當您將 OneDrive 附件儲存或拖放到電腦時，我們會為您下載檔案。</span><span class="sxs-lookup"><span data-stu-id="44499-2009">**Downloading cloud attachments:** When you save or drag and drop OneDrive attachments to your computer, we download the file for you.</span></span>
-   <span data-ttu-id="44499-p316">**有用的聲音可改善協助工具：** 開啟音訊提示可在作業時一面引導您。可在 [檔案] \> [選項] \> [輕鬆存取] 中找到此功能。無需增益集。 [深入了解](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)</span><span class="sxs-lookup"><span data-stu-id="44499-p316">**Helpful sounds improve accessibility:** Turn on audio cues to guide you as you work. Find it in File \> Options \> Ease of Access. No add-in needed. [Learn more](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)</span></span>
-   <span data-ttu-id="44499-p317">**焦點收件匣：** 收件匣分成兩個索引標籤 – 焦點及其他。訊息會依照訊息內容和您最常互動的寄信者進行分類。 [深入了解](https://support.office.com/article/f445ad7f-02f4-4294-a82e-71d8964e3978)</span><span class="sxs-lookup"><span data-stu-id="44499-p317">**Focused Inbox:** The Inbox is separated into two tabs – Focused and Other. Messages are sorted based on the content of the message and who you interact with most often. [Learn more](https://support.office.com/article/f445ad7f-02f4-4294-a82e-71d8964e3978)</span></span>
-   <span data-ttu-id="44499-2017">**快速存取您最常使用的群組︰** 您最有可能互動的群組，會出現在 [群組] 下方清單頂端的 [資料夾] 窗格中。</span><span class="sxs-lookup"><span data-stu-id="44499-2017">**Quickly access the groups you use most:** Groups you're most likely to interact with now appear at the top of the list under Groups in the Folder pane.</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="44499-2018">Outlook：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2018">Outlook: Security updates</span></span>
-   <span data-ttu-id="44499-2019">[CVE-2017-11939](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11939)：Microsoft Office 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2019">[CVE-2017-11939](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11939): Microsoft Office Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="44499-2020">[CVE-2018-0791](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0791)：Microsoft Outlook 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2020">[CVE-2018-0791](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0791): Microsoft Outlook Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2021">[CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793)：Microsoft Outlook 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2021">[CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2022">[CVE-2018-0850](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0850)：Microsoft Outlook 提高權限弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2022">[CVE-2018-0850](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0850): Microsoft Outlook Elevation of Privilege Vulnerability</span></span>
-   <span data-ttu-id="44499-2023">[CVE-2018-0852](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0852)：Microsoft Outlook 記憶體損毀弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2023">[CVE-2018-0852](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0852): Microsoft Outlook Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="44499-2024">[CVE-2018-8150](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8150)：Microsoft Outlook 安全性功能略過的弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2024">[CVE-2018-8150](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8150): Microsoft Outlook Security Feature Bypass Vulnerability</span></span>
-   <span data-ttu-id="44499-2025">[CVE-2018-8244](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8244)：Microsoft Outlook 提高權限弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2025">[CVE-2018-8244](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8244): Microsoft Outlook Elevation of Privilege Vulnerability</span></span>
-   <span data-ttu-id="44499-2026">[CVE-2018-8310](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8310)：Microsoft Office 竄改弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2026">[CVE-2018-8310](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8310): Microsoft Office Tampering Vulnerability</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="44499-2027">Outlook：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2027">Outlook: Non-security updates</span></span>
-   <span data-ttu-id="44499-2028">修正此問題：切換到 [寄件匣] 或 [寄件備份] 資料夾造成 Outlook 損毀。</span><span class="sxs-lookup"><span data-stu-id="44499-2028">Fix an issue where switching to the Outbox or Sent Items folder causes Outlook to crash.</span></span>
-   <span data-ttu-id="44499-2029">修正此問題：會議內文或附件變更時所有出席者收到會議更新，而非傳送會議更新給選擇性的出席者。</span><span class="sxs-lookup"><span data-stu-id="44499-2029">Fix an issue where all attendees receive meeting updates when the meeting body or attachments change, instead of sending a meeting update to the attendees being optional.</span></span>
-   <span data-ttu-id="44499-2030">修正此問題：因為使用者代理程式字串中的變更，造成使用者無法連線到 EWS 及 REST 端點。</span><span class="sxs-lookup"><span data-stu-id="44499-2030">Fix an issue that causes users to be unable to connect to EWS and REST endpoints because of a change in the User-Agent string.</span></span>
-   <span data-ttu-id="44499-2031">修正此問題：出席者的會議位置更新是顯示舊的位置而不是新的位置。</span><span class="sxs-lookup"><span data-stu-id="44499-2031">Fix an issue where a meeting location update to attendees shows the old location instead of the new location.</span></span>
-   <span data-ttu-id="44499-2032">修正此問題：使用者在預覽讀取窗格中的附件時，會看到錯誤。</span><span class="sxs-lookup"><span data-stu-id="44499-2032">Fix an issue where the user sees an error when previewing an attachment in the reading pane.</span></span>
-   <span data-ttu-id="44499-2033">修正此問題：當使用者在撰寫電子郵件時，解決電子郵件地址的顯示名稱會使 Outlook 當機。</span><span class="sxs-lookup"><span data-stu-id="44499-2033">Fix an issue where Outlook crashes when resolving display names to email addresses when the user is composing an email.</span></span>
-   <span data-ttu-id="44499-2034">修正此問題：有些使用者未收到其租用戶系統管理員已啟用的支援功能</span><span class="sxs-lookup"><span data-stu-id="44499-2034">Fix an issue where some users don't receive support features that have been enabled by their tenant admin</span></span>
-   <span data-ttu-id="44499-2035">修正此問題：當搜尋範圍限定為 [所有信箱] 時，搜索會失敗並顯示 [找不到相符項目]。</span><span class="sxs-lookup"><span data-stu-id="44499-2035">Fix an issue where search fails with “No matches found” when search is scoped to All Mailboxes.</span></span>
-   <span data-ttu-id="44499-2036">修正此問題：使用 Accessible Event Watcher (AccEvent.exe) 來監視時，切換資料夾會導致 Outlook 當機。</span><span class="sxs-lookup"><span data-stu-id="44499-2036">Fix an issue where, when monitoring using Accessible Event Watcher (AccEvent.exe), Outlook crashes when switching folders.</span></span>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="44499-2037">PowerPoint：功能更新</span><span class="sxs-lookup"><span data-stu-id="44499-2037">PowerPoint: Feature updates</span></span>
-   <span data-ttu-id="44499-p318">**Microsoft Translator：** 使用 Microsoft Translator 可將單字、片語或句子翻譯成另一種語言。您可以從功能區中的 [校閱] 索引標籤使用此功能。</span><span class="sxs-lookup"><span data-stu-id="44499-p318">**Microsoft Translator:** Translate words, phrases or sentences to another language with Microsoft Translator. You can do this from the Review tab in the ribbon.</span></span>
-   <span data-ttu-id="44499-2040">**3D 動畫：** 透過輕輕搖晃或跳躍及旋轉等動畫，讓 3D 模型栩栩如生。</span><span class="sxs-lookup"><span data-stu-id="44499-2040">**3D animations:** Bring your 3D models to life with animations such as swinging gently or jumping and turning.</span></span>
-   <span data-ttu-id="44499-2041">**將 SVG 圖示轉換成圖形：** 將所有 SVG 圖片和圖示轉換成 Office 圖形，讓您可以變更其色彩、大小或材質。</span><span class="sxs-lookup"><span data-stu-id="44499-2041">**Convert SVG icons to shapes:** Transform all SVG pictures and icons into Office shapes so you can change their color, size, or texture.</span></span>
-   <span data-ttu-id="44499-2042">**修訂追蹤資訊漫遊：** 醒目提示共用投影片 (已經過他人修改) 的已讀取/未讀取狀態，現在會儲存在漫遊服務中 (而不是在使用者的本機電腦上)，讓這項資訊可以跨越多個裝置或平台上進行同步處理。</span><span class="sxs-lookup"><span data-stu-id="44499-2042">**Roaming of revision tracking info:** The read/unread status for highlighting shared slides that have been modified by others is now stored in a roaming service (instead of on the user's local computer) so that this information can be synchronized across multiple devices or platforms.</span></span>
-   <span data-ttu-id="44499-2043">**快速存取您的網站和群組︰** 您可以使用 [檔案] 功能表，使用儲存在您常用的網站和群組中的文件。</span><span class="sxs-lookup"><span data-stu-id="44499-2043">**Quickly access your sites and groups:** Use the File menu to work with documents stored in your frequently used sites and groups.</span></span>
-   <span data-ttu-id="44499-p319">**數位鉛筆：** 使用新的鉛筆紋理手寫或繪製出您的創意。只需傾斜即可使用支援的數位鉛筆進行陰影處理。</span><span class="sxs-lookup"><span data-stu-id="44499-p319">**Digital Pencil:** Write or sketch out ideas with our new pencil texture. Simply tilt to do shading with supported digital pens.</span></span>
-   <span data-ttu-id="44499-p320">**LinkedIn 功能設定：** 移至 [檔案] \> [選項] \> [一般]，以控制 LinkedIn 功能是否要顯示在您的 Office 應用程式中。[深入了解](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)</span><span class="sxs-lookup"><span data-stu-id="44499-p320">**LinkedIn features setting:** Go to File \> Options \> General to control whether LinkedIn features are shown in your Office applications. [Learn more](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)</span></span>
-   <span data-ttu-id="44499-p321">**使用數位筆執行投影片放映：** 使用 Surface 手寫筆或其他有藍牙按鈕的手寫筆，推進您的投影片。必須有 Windows 10 Fall Creators Update。 [深入了解](https://support.office.com/article/e36da834-7d34-4b71-aafd-071727549f7a)</span><span class="sxs-lookup"><span data-stu-id="44499-p321">**Run a slide show with your digital pen:** Use your Surface Pen, or other pen with a Bluetooth button, to advance your slides. Windows 10 Fall Creators Update is required. [Learn more](https://support.office.com/article/e36da834-7d34-4b71-aafd-071727549f7a)</span></span>
-   <span data-ttu-id="44499-p322">**3D 模型：** 使用 3D 來增加簡報的視覺效果和創意影響。透過「轉化」轉場在投影片之間建立電影動畫，讓 3D 模型讓您的簡報更生動。 [深入了解](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)</span><span class="sxs-lookup"><span data-stu-id="44499-p322">**3D models:** Use 3D to increase the visual and creative impact of your presentations. Bring 3D models to life in your presentations with transitions like Morph that create cinematic animations between slides. [Learn more](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)</span></span>
-   <span data-ttu-id="44499-2054">**新的筆跡效果：** 使用金屬畫筆和筆跡效果 (如彩虹、星空、熔岩、海洋、黃金、銀等) 來展現您的想法。</span><span class="sxs-lookup"><span data-stu-id="44499-2054">**New ink effects:** Express your ideas with flair using metallic pens and ink effects like rainbow, galaxy, lava, ocean, gold, silver and more.</span></span>
-   <span data-ttu-id="44499-p323">**共用檔案 UI：** 對於商務用 OneDrive 或 SharePoint 檔案，按一下功能區右上角的 [共用] 按鈕，或移至 [檔案] \> [共用] 可啟動經簡化並改良過的 [共用] 對話方塊。對於新的或儲存在本機的檔案，該 UI 可讓使用者輕鬆地將檔案上傳至 OneDrive 以啟動共同作業。</span><span class="sxs-lookup"><span data-stu-id="44499-p323">**Sharing files UI:** For OneDrive for Business or SharePoint files, clicking the Share button in the upper right-hand corner of the ribbon or going to File \> Share launches a simplified and improved Share dialog. For new or locally-saved files, the UI allows users to easily upload their files to OneDrive to start collaborating.</span></span>
-   <span data-ttu-id="44499-p324">**封鎖危險的副檔名：** 依預設，視為具有高風險以及內嵌為 OLE 封裝物件的副檔名 (例如.exe、.vbs 和 .js)，會遭到封鎖而無法啟動。[深入了解](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span><span class="sxs-lookup"><span data-stu-id="44499-p324">**Block dangerous extensions:** Extensions that are considered to be high risk, and are embedded as OLE package objects, are blocked, by default, from activating. For example, .exe, .vbs, and .js. [Learn more](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span></span>
-   <span data-ttu-id="44499-2060">**修訂醒目提示：** 會醒目提示已由其他使用者修改的投影片。</span><span class="sxs-lookup"><span data-stu-id="44499-2060">**Revision highlighting:** Slides that have been modified by other users are highlighted.</span></span>
-   <span data-ttu-id="44499-2061">**當您離開時：** PowerPoint 會顯示自您上次查閱以來誰編輯了共用的簡報。</span><span class="sxs-lookup"><span data-stu-id="44499-2061">**While you were away:** PowerPoint shows you who edited your shared presentation since your last visit.</span></span>
-   <span data-ttu-id="44499-2062">**設計工具的改進：** 設計工具現在會針對項目符號清單中的時間軸建議設計概念。</span><span class="sxs-lookup"><span data-stu-id="44499-2062">**Designer improvement:** Designer now recommends design ideas for timelines in a bulleted list.</span></span>
-   <span data-ttu-id="44499-p325">**有用的聲音可改善協助工具：** 開啟音訊提示可在作業時一面引導您。可在 [檔案] \> [選項] \> [輕鬆存取] 中找到此功能。無需增益集。 [深入了解](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)</span><span class="sxs-lookup"><span data-stu-id="44499-p325">**Helpful sounds improve accessibility:** Turn on audio cues to guide you as you work. Find it in File \> Options \> Ease of Access. No add-in needed. [Learn more](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)</span></span>
-   <span data-ttu-id="44499-2067">**依帳戶的檔案位置：** 開啟或儲存檔案時，位置清單會依照與其相關聯的帳戶整理。</span><span class="sxs-lookup"><span data-stu-id="44499-2067">**File locations by account:** When opening or saving a file, the list of places is organized by the account associated with them.</span></span>
-   <span data-ttu-id="44499-p326">**畫筆自訂：** 針對筆跡選擇畫筆和螢光筆的個人集合。您的自訂集可在您所有的 Windows 電腦上使用。</span><span class="sxs-lookup"><span data-stu-id="44499-p326">**Pen customization:** Choose a personal set of pens and highlighters for inking. Your customized set is available on all your Windows PCs.</span></span>
-   <span data-ttu-id="44499-2070">**設計工具的改進：** 設計工具現在會針對新增至投影片的圖表建議設計概念。</span><span class="sxs-lookup"><span data-stu-id="44499-2070">**Designer improvement:** Designer now recommends design ideas for charts added to your slides.</span></span>
-   <span data-ttu-id="44499-p327">**快速啟動工具：** 自動建置大綱，協助使用者開始研究他們所選擇的主題。[深入了解](https://support.office.com/article/4784f273-0b2c-456c-9c89-24e5b977c224)</span><span class="sxs-lookup"><span data-stu-id="44499-p327">**QuickStarter:** Automatically builds an outline to help users get started researching a subject of their choosing. [Learn more](https://support.office.com/article/4784f273-0b2c-456c-9c89-24e5b977c224)</span></span>
-   <span data-ttu-id="44499-p328">**數位尺規：** 在有觸控式螢幕的裝置上，請移至「繪圖 \> 尺規」，然後使用您的手寫筆或手指來繪製直線，或對齊一組物件。[深入了解](https://support.office.com/article/6222c9b4-2fdf-48f7-a3fd-1687fbe2bf84)</span><span class="sxs-lookup"><span data-stu-id="44499-p328">**Digital ruler:** On devices that have touch screens, go to Draw \> Ruler, then use your pen or finger to draw straight lines or to align a set of objects. [Learn more](https://support.office.com/article/6222c9b4-2fdf-48f7-a3fd-1687fbe2bf84)</span></span>

### <a name="powerpoint-security-updates"></a><span data-ttu-id="44499-2075">PowerPoint：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2075">PowerPoint: Security updates</span></span>
-   <span data-ttu-id="44499-2076">[CVE-2017-11934](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11934)：Microsoft PowerPoint 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2076">[CVE-2017-11934](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11934): Microsoft PowerPoint Information Disclosure Vulnerability</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="44499-2077">PowerPoint：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2077">PowerPoint: Non-security updates</span></span>
-   <span data-ttu-id="44499-2078">修正此問題：表格以粗框線錯誤編譯。</span><span class="sxs-lookup"><span data-stu-id="44499-2078">Fix an issue where tables are rendered incorrectly with thick borders.</span></span>
-   <span data-ttu-id="44499-2079">修正當變更 Shape.Visibile 屬性時可能會造成當機的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-2079">Fix an issue where a potential crash could occur when changing the Shape.Visibile property.</span></span>
-   <span data-ttu-id="44499-2080">修正共同撰寫文件中的變更無法合併的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-2080">Fix an issue where changes in co-authored documents fail to merge.</span></span>
-   <span data-ttu-id="44499-2081">修正包含 ActiveX 控制項的文件會造成共同撰寫失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-2081">Fix an issue where documents containing ActiveX controls would cause co-authoring to fail.</span></span>
-   <span data-ttu-id="44499-2082">修正此問題：在圖形中使用拼字校正時會造成 PowerPoint 當機。</span><span class="sxs-lookup"><span data-stu-id="44499-2082">Fix an issue where spelling correction in shapes causes PowerPoint to crash.</span></span>
-   <span data-ttu-id="44499-2083">修正此問題：PowerPoint 在從 SharePoint Online 開啟檔案時損毀。</span><span class="sxs-lookup"><span data-stu-id="44499-2083">Fix an issue where PowerPoint crashes when opening a file from SharePoint Online.</span></span>
-   <span data-ttu-id="44499-2084">修正此問題：開啟 [自動儲存] 時，[復原] 窗格不正確地顯示。</span><span class="sxs-lookup"><span data-stu-id="44499-2084">Fix an issue where the Recovery Pane incorrectly appears when AutoSave is on.</span></span>
-   <span data-ttu-id="44499-2085">修正此問題：未顯示登入，使得使用者無法存取檔案。</span><span class="sxs-lookup"><span data-stu-id="44499-2085">Fix an issue where sign-in isn't shown preventing a user from accessing a file.</span></span>
-   <span data-ttu-id="44499-2086">修正此問題：多個使用者在相同簡報上共同撰寫會導致投影片母片不正確重複。</span><span class="sxs-lookup"><span data-stu-id="44499-2086">Fix an issue where multiple users co-authoring on the same presentation results in an incorrect duplication of slides masters.</span></span>
-   <span data-ttu-id="44499-2087">修正此問題：將儲存在 OneDrive 中的檔案開啟時，結束受保護的檢視時會導致 PowerPoint 當機。修正此問題：移除文件屬性和個人資訊會造成儲存至 SharePoint 失敗。</span><span class="sxs-lookup"><span data-stu-id="44499-2087">Fix an issue where opening a file saved on OneDrive results in PowerPoint crashing when exiting Protected View.Fix an issue where removing document properties and personal information causes saving to SharePoint to fail.</span></span>
-   <span data-ttu-id="44499-p329">修正此問題：以 Flash Player 為基礎之 YouTube 內嵌程式碼的參考，導致開啟新視窗來播放影片。舊的內嵌程式碼現已升級為參考以 HTML5 為基礎的 YouTube 影片，以便正確地就地播放。</span><span class="sxs-lookup"><span data-stu-id="44499-p329">Fix an issue where references to Flash Player based YouTube embed codes result in a new window opening to play the video. Old embed codes are now upgraded to reference HTML5 based YouTube videos so that they correctly play in place.</span></span>
-   <span data-ttu-id="44499-p330">修正此問題：正在儲存同步備份檔案時，Office 無法寫入磁碟，但 Office 會不斷上傳檔案到 OneDrive。有了此修正程式之後，使用者現在會看到一則錯誤訊息，且 Office 不會繼續上傳。</span><span class="sxs-lookup"><span data-stu-id="44499-p330">Fix an issue where, when saving a sync-backed file, Office fails to write to disk, but Office keeps uploading the file to OneDrive. With this fix, user will now see an error message and the upload won't proceed.</span></span>

### <a name="project-feature-updates"></a><span data-ttu-id="44499-2092">Project：功能更新</span><span class="sxs-lookup"><span data-stu-id="44499-2092">Project: Feature updates</span></span>
-   <span data-ttu-id="44499-p331">**工作面板檢視：** 在 [工作面板] 檢視中的卡片上排序工作。在面板上的資料行之間重新排序和移動卡片，就像在敏捷式專案中一樣。</span><span class="sxs-lookup"><span data-stu-id="44499-p331">**Task Board view:** Sort tasks on cards in the Task Board view. Reorder and move cards between columns on the board just like in Agile projects.</span></span>
-   <span data-ttu-id="44499-p332">**敏捷式專案：** 使用待辦項目、工作面板、衝刺及其他項目管理您的敏捷式專案。同時支援 Scrum 或 Kanban 方法。[深入了解](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)</span><span class="sxs-lookup"><span data-stu-id="44499-p332">**Agile projects:** Manage your Agile projects using backlogs, task boards, sprints, and more. Both Scrum or Kanban methodologies are supported. [Learn more](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)</span></span>  
-   <span data-ttu-id="44499-p333">**在 Planner 中管理工作：** 將專案工作連結至 Planner，並為其建立計劃。將工作分成子工作、新增小組、指派任務，以及管理工作面板上的工作。</span><span class="sxs-lookup"><span data-stu-id="44499-p333">**Manage a task in Planner:** Link a Project task to Planner and create a plan for it. Break the task into subtasks, add a team, assign tasks, and manage the work on a task board.</span></span>

### <a name="project-non-security-updates"></a><span data-ttu-id="44499-2100">Project：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2100">Project: Non-security updates</span></span>
-   <span data-ttu-id="44499-2101">修正此問題：如果工作以成本資源分割，成本資源未正確更新，且成本遺失。</span><span class="sxs-lookup"><span data-stu-id="44499-2101">Fix an issue where if a task is split with a cost resource, the cost resource isn't correctly updated and the cost is lost.</span></span>
-   <span data-ttu-id="44499-2102">修正時間表檢視的問題：在 [將現有工作新增至時間表] 對話方塊中，只會出現來自第一個摘要工作中的工作。</span><span class="sxs-lookup"><span data-stu-id="44499-2102">Fix an issue where in the Timeline view - Add Existing Tasks to the Timeline dialog, only tasks from the first summary task would show up.</span></span>
-   <span data-ttu-id="44499-2103">修正此問題：從 Project Online 或 Project Server 將主要專案儲存為 XML 時失敗。</span><span class="sxs-lookup"><span data-stu-id="44499-2103">Fix an issue where saving as XML may fail for master projects from Project Online or Project Server.</span></span>
-   <span data-ttu-id="44499-2104">修正時間表檢視的問題：在 [將現有工作新增至時間表] 對話方塊中，只會出現來自第一個摘要工作中的工作。</span><span class="sxs-lookup"><span data-stu-id="44499-2104">Fix an issue where in the Timeline view - Add Existing Tasks to the Timeline dialog, only tasks from the first summary task would show up.</span></span>
-   <span data-ttu-id="44499-2105">修正此問題：在日期資料行上使用 [自動篩選] 下拉式清單造成專案中的所有工作隱藏。</span><span class="sxs-lookup"><span data-stu-id="44499-2105">Fix an issue where using the AutoFilter dropdown on a date column causes all tasks in the project to be hidden.</span></span>
-   <span data-ttu-id="44499-2106">修正此問題：將現有的工作新增至時間表檢視中的時間表時，對話方塊中只會出現來自第一個摘要工作的工作。</span><span class="sxs-lookup"><span data-stu-id="44499-2106">Fix an issue where only tasks from the first summary task show up in the dialog box when adding existing tasks to a timeline when in Timeline view.</span></span>
-   <span data-ttu-id="44499-2107">修正此問題：在工作階段中設定多個基準，會讓 MOD\_DATE 值都設為相同。</span><span class="sxs-lookup"><span data-stu-id="44499-2107">Fix an issue where setting more than one baseline in a session sets the MOD\_DATE value as the same.</span></span>
-   <span data-ttu-id="44499-2108">修正此問題：將實際工時從 [儲存為共用] 工作階段中移除之後，[實際工時] 仍然顯示在報表中。</span><span class="sxs-lookup"><span data-stu-id="44499-2108">Fix an issue where Actual Work is still shown in the reporting tables after being removed in a Save for Sharing session.</span></span>
-   <span data-ttu-id="44499-2109">修正此問題：在德文版中進行排程時，要使用 [週] 日期格式時會傳回錯誤。</span><span class="sxs-lookup"><span data-stu-id="44499-2109">Fix an issue in the German language version where using a Weeks date format returns an error when scheduling.</span></span>
-   <span data-ttu-id="44499-2110">修正此問題：在編輯 [排程網頁組件] 的完成日期時，工作保持為每天 8 小時，而不是隨著時間分配。</span><span class="sxs-lookup"><span data-stu-id="44499-2110">Fix an issue where, when editing finish dates in Schedule Web Part, tasks stay at 8 hours per day instead of being spread over time.</span></span>
-   <span data-ttu-id="44499-2111">修正此問題：在非預期的位置繪製「進度點形狀」。</span><span class="sxs-lookup"><span data-stu-id="44499-2111">Fix an issue where "Progress point shape" is drawn at an unexpected location.</span></span>
-   <span data-ttu-id="44499-2112">修正此問題：VBA 程式碼從專案中遺失。</span><span class="sxs-lookup"><span data-stu-id="44499-2112">Fix an issue where VBA code gets lost from projects.</span></span>
-   <span data-ttu-id="44499-2113">修正此問題：即使有剩餘工時，工作卻顯示為完成。</span><span class="sxs-lookup"><span data-stu-id="44499-2113">Fix an issue where tasks show as complete even when there is remaining work.</span></span>
-   <span data-ttu-id="44499-2114">修正此問題：使用「任務路徑」功能時，專案停止回應。</span><span class="sxs-lookup"><span data-stu-id="44499-2114">Fix an issue where Project hangs when using the Task Path feature.</span></span>
-   <span data-ttu-id="44499-2115">修正此問題：時幅沒有顯示時幅標籤。</span><span class="sxs-lookup"><span data-stu-id="44499-2115">Fix an issue where the timescale doesn't show the timescale labels.</span></span>
-   <span data-ttu-id="44499-2116">修正此問題：視覺效果報表顯示不完整的資訊或完全失敗。</span><span class="sxs-lookup"><span data-stu-id="44499-2116">Fix an issue where visual reports show incomplete information or fail completely.</span></span>
-   <span data-ttu-id="44499-2117">修正此問題：儲存失敗會導致檔案損毀，並造成專案在開啟時當機。</span><span class="sxs-lookup"><span data-stu-id="44499-2117">Fix an issue where a failed save can corrupt a file and cause Project to crash on open.</span></span>
-   <span data-ttu-id="44499-2118">修正此問題：您無法在時間軸和團隊規劃檢視中拖曳工作。</span><span class="sxs-lookup"><span data-stu-id="44499-2118">Fix an issue where you can't drag tasks in the Timeline and Team Planner view.</span></span>
-   <span data-ttu-id="44499-2119">修正此問題：「小組建立器」中沒有顯示資源可用性。</span><span class="sxs-lookup"><span data-stu-id="44499-2119">Fix an issue where resource availability isn't shown in Team Builder.</span></span>
-   <span data-ttu-id="44499-2120">修正此問題：圖形指標並未正確顯示。</span><span class="sxs-lookup"><span data-stu-id="44499-2120">Fix an issue where graphical indicators aren't displaying correctly.</span></span>
-   <span data-ttu-id="44499-2121">修正此問題：專案以每小時或每一天為基礎進行調整時沒有反應。</span><span class="sxs-lookup"><span data-stu-id="44499-2121">Fix an issue where Project hangs while leveling on hour-by-hour or day-by-day basis.</span></span>
-   <span data-ttu-id="44499-2122">修正此問題：搭配使用 SharePoint 文件庫的主/子專案。</span><span class="sxs-lookup"><span data-stu-id="44499-2122">Fix an issue for working with master/sub projects from a SharePoint Document library.</span></span>
-   <span data-ttu-id="44499-2123">修正此問題：當您將工作分派新增到固定工期的排程時，可能會導致沒有名稱的資源。</span><span class="sxs-lookup"><span data-stu-id="44499-2123">Fix an issue where, when you add assignments to a fixed duration task, you may end up with a nameless resource.</span></span>
-   <span data-ttu-id="44499-2124">修正此問題：變更受保護的工作時，會產生不正確的錯誤訊息。</span><span class="sxs-lookup"><span data-stu-id="44499-2124">Fix an issue that produces an incorrect error message of change on protected work.</span></span>
-   <span data-ttu-id="44499-2125">修正此問題：當報表包含數個影像時，Project 可能會損毀。</span><span class="sxs-lookup"><span data-stu-id="44499-2125">Fix an issue where Project might crash when going to reports that contain several images.</span></span>

### <a name="publisher-feature-updates"></a><span data-ttu-id="44499-2126">Publisher：功能更新</span><span class="sxs-lookup"><span data-stu-id="44499-2126">Publisher: Feature updates</span></span>
-   <span data-ttu-id="44499-p334">**封鎖危險的副檔名：** 依預設，視為具有高風險以及內嵌為 OLE 封裝物件的副檔名 (例如.exe、.vbs 和 .js)，會遭到封鎖而無法啟動。[深入了解](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span><span class="sxs-lookup"><span data-stu-id="44499-p334">**Block dangerous extensions:** Extensions that are considered to be high risk, and are embedded as OLE package objects, are blocked, by default, from activating. For example, .exe, .vbs, and .js. [Learn more](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span></span>

### <a name="publisher-non-security-updates"></a><span data-ttu-id="44499-2130">Publisher：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2130">Publisher: Non-security updates</span></span>
-   <span data-ttu-id="44499-2131">修正此問題：執行合併列印精靈時，篩選包含 null (空白) 值的資料來源欄位失敗。</span><span class="sxs-lookup"><span data-stu-id="44499-2131">Fix an issue where filtering on data source fields containing null (empty) values fails when running the Mail Merge wizard.</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="44499-2132">商務用 Skype：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2132">Skype for Business: Non-security updates</span></span>
-   <span data-ttu-id="44499-2133">修正與 TLS 1.2 支援相關的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-2133">Fix an issue related to TLS 1.2 support.</span></span>
-   <span data-ttu-id="44499-2134">修正此問題：在會議中以選取 [Skype 通話] 的方式新增使用者會產生錯誤</span><span class="sxs-lookup"><span data-stu-id="44499-2134">Fix an issue where adding users by selecting 'Skype Call' in a meeting causes an error</span></span>
-   <span data-ttu-id="44499-2135">修正此問題：在會議中以選取 [Skype 通話] 的方式新增使用者會產生錯誤。</span><span class="sxs-lookup"><span data-stu-id="44499-2135">Fix an issue where adding users by selecting 'Skype Call' in a meeting causes an error.</span></span>
-   <span data-ttu-id="44499-2136">如果已將 Skype 會議室新增為位置，且會議已包含小組會議座標，請移除要求使用者將 Skype 座標新增至會議的提示。</span><span class="sxs-lookup"><span data-stu-id="44499-2136">Remove prompt asking user to add Skype coordinates to a meeting, if a Skype Room is added as the location and the meeting already contains Teams meeting coordinates.</span></span>
-   <span data-ttu-id="44499-2137">修正此問題：即使 UseLocationForE911Only 設定為 true，也會填入位置。</span><span class="sxs-lookup"><span data-stu-id="44499-2137">Fix an issue where location is populated even when UseLocationForE911Only is set to true.</span></span>
-   <span data-ttu-id="44499-2138">修正此問題：使用名冊中的「使用會議中心呼叫」選項來邀請使用者時，商務用 Skype 會當機。</span><span class="sxs-lookup"><span data-stu-id="44499-2138">Fix an issue where Skype for Business hangs when using the "call using conference center" option to invite users from the roster.</span></span>
-   <span data-ttu-id="44499-2139">修正此問題：建立商務用 Skype 會議時，在終端機伺服器上運行的Outlook 會凍結。</span><span class="sxs-lookup"><span data-stu-id="44499-2139">Fix an issue where Outlook running on terminal server freezes while creating a Skype for Business meeting.</span></span>
-   <span data-ttu-id="44499-2140">將 EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket 的預設值變更為 TRUE。</span><span class="sxs-lookup"><span data-stu-id="44499-2140">Change the default value of EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket to TRUE.</span></span>
-   <span data-ttu-id="44499-2141">修正此問題：當會議處於全螢幕模式時，[其他選項] 和 [邀請其他人] 按鈕會隱藏。</span><span class="sxs-lookup"><span data-stu-id="44499-2141">Fix an issue where "More Options" and "Invite More People" buttons are hidden when a meeting is in full-screen mode.</span></span>
-   <span data-ttu-id="44499-2142">修正此問題：當您想要加入會議時，P2P 音訊撥號視窗或電話會議視窗會變成透明。</span><span class="sxs-lookup"><span data-stu-id="44499-2142">Fix an issue where the P2P audio call window or conference call window becomes transparent when you attempt to join.</span></span>
-   <span data-ttu-id="44499-2143">修正此問題：即將開始的 Skype 會議未顯示在 [會議] 索引標籤。</span><span class="sxs-lookup"><span data-stu-id="44499-2143">Fix an issue where upcoming Skype meetings do not show up in the meetings tab.</span></span>
-   <span data-ttu-id="44499-2144">修正此問題：當商務用 Skype 配置為無音訊加入會議，新增音訊至會議時不會將音訊新增至現有的會議，反而是向使用者本身啟動新的 P2P 撥號。</span><span class="sxs-lookup"><span data-stu-id="44499-2144">Fix an issue where, when Skype for Business is configured to join meetings without audio, adding audio to a meeting initiates a new P2P call to the user itself rather than adding audio to the existing meeting.</span></span>
-   <span data-ttu-id="44499-2145">修正此問題：當使用者按下 Outlook 會議邀請的 [加入 Skype 會議] 連結時，會收到錯誤訊息 [找不到此 Skype 會議]。</span><span class="sxs-lookup"><span data-stu-id="44499-2145">Fix an issue where user receives the error message "We couldn't find this Skype meeting" when clicking 'Join Skype Meeting' link in a meeting request from Outlook.</span></span>
-   <span data-ttu-id="44499-2146">在快顯通知 UI 中為撥入的 PSTN 通話新增來電轉接按鈕。</span><span class="sxs-lookup"><span data-stu-id="44499-2146">Add call transfer button in the toast UI for incoming PSTN calls.</span></span>
-   <span data-ttu-id="44499-2147">當 ChatDefaultClient 和 CallDefaultClient 設定至 Teams 時，通知使用者來電與交談正在傳送至 Teams。</span><span class="sxs-lookup"><span data-stu-id="44499-2147">Notify users that calls and chat are being sent to Teams when ChatDefaultClient and CallDefaultClient are set to Teams.</span></span>
-   <span data-ttu-id="44499-2148">當使用者不在會議中並停用商務用 Skype 時，使用者狀態會顯示為 [離線]，且會議加入體驗會設為 [原生有限用戶端]。</span><span class="sxs-lookup"><span data-stu-id="44499-2148">Show user's presence as Offline when user is not in a meeting and disabled from Skype for Business and meeting join experience is set to Native Limited Client.</span></span>
-   <span data-ttu-id="44499-2149">商務用 Skype 最小化至通知區域時，停用 [開啟] 和 [結束] 以外的所有選項。</span><span class="sxs-lookup"><span data-stu-id="44499-2149">Disable all options except Open and Exit when Skype for Business is minimized to the notification area.</span></span>
-   <span data-ttu-id="44499-2150">與 Aries 電話配對且啟用 RedirectClient 時，隱藏新來電和對話。</span><span class="sxs-lookup"><span data-stu-id="44499-2150">Suppress new calls and conversations when paired with Aries phones and RedirectClient is enabled.</span></span>
-   <span data-ttu-id="44499-2151">修正此問題：日期格式非美國格式 (mm/dd/yy) 時，在 PChat 中依日期搜尋訊息會失敗。</span><span class="sxs-lookup"><span data-stu-id="44499-2151">Fix an issue where searching messages in PChat by date fails when the date format is other than US format (mm/dd/yy).</span></span>
-   <span data-ttu-id="44499-2152">修正此問題：當 EnableExternalP2PFileTransfer 原則設為 false 時，使用者仍然可以在會議中附加檔案。</span><span class="sxs-lookup"><span data-stu-id="44499-2152">Fix an issue where, when EnableExternalP2PFileTransfer policy is set to false, users are still able to attach files in meetings.</span></span>
-   <span data-ttu-id="44499-p335">修正此問題：在 [交談歷程記錄] 中，顯示了來電者而非受話者。使用 Active Directory 修改受話者的公司電話時會發生這種情況。</span><span class="sxs-lookup"><span data-stu-id="44499-p335">Fix an issue where, in Conversation History, the caller is shown instead of the called person. This happens when the called person's work number is modified using Active Directory.</span></span>
-   <span data-ttu-id="44499-2155">修正此問題：對於撥出 PSTN 通話到行動號碼，交談歷程記錄的通話記錄中遺失受話方資訊。</span><span class="sxs-lookup"><span data-stu-id="44499-2155">Fix an issue where, for outgoing PSTN calls to mobile numbers, recipient information is missing in the call history in conversation history.</span></span>
-   <span data-ttu-id="44499-2156">修正此問題：從 Outlook 中的電子郵件起始 IM 時，電子郵件的主旨列並不包含在 IM 的主旨中。</span><span class="sxs-lookup"><span data-stu-id="44499-2156">Fix an issue where, when initiating an IM from an email in Outlook, the subject line of the email is not included in the subject of the IM.</span></span>
-   <span data-ttu-id="44499-2157">修正此問題：當 [IM 交談] 視窗貼齊到一側時，交談會出現雙重堆疊。</span><span class="sxs-lookup"><span data-stu-id="44499-2157">Fix an issue where, when IM conversation windows are snapped to one side, conversations appear double stacked.</span></span>
-   <span data-ttu-id="44499-2158">修正此問題：在 VDIv2 環境中，VbSS 螢幕畫面分享要求會顯示為 RDP 要求。</span><span class="sxs-lookup"><span data-stu-id="44499-2158">Fix an issue where, in a VDIv2 environment, VbSS screen sharing requests appear as RDP-based requests.</span></span>
-   <span data-ttu-id="44499-2159">修正此問題：來電轉接失敗時，來電者會列在失敗通知中而非列在未接受話方。</span><span class="sxs-lookup"><span data-stu-id="44499-2159">Fix an issue where, in a failed call transfer, the caller is listed in the failure notification, instead of the missed recipient.</span></span>
-   <span data-ttu-id="44499-2160">修正此問題：「開始使用 Teams」按鈕隱藏在用戶端升級重新導向橫幅內。</span><span class="sxs-lookup"><span data-stu-id="44499-2160">Fix an issue where the "Start using Teams" button is hidden within the client upgrade redirect banner.</span></span>
-   <span data-ttu-id="44499-2161">修正即時通訊視窗中的 DPI 縮放比例問題。</span><span class="sxs-lookup"><span data-stu-id="44499-2161">Fix DPI scaling issues in IM windows.</span></span>
-   <span data-ttu-id="44499-2162">修正此問題：商務用 Skype 連絡人卡片中未顯示 LinkedIn 資料。</span><span class="sxs-lookup"><span data-stu-id="44499-2162">Fix an issue where LinkedIn data does not appear in the Skype for Business Contact Card.</span></span>
-   <span data-ttu-id="44499-2163">新增可讓使用者代表群組搜尋停止接受呼叫的功能。</span><span class="sxs-lookup"><span data-stu-id="44499-2163">Add the ability for users to stop receiving calls on behalf of a hunt group.</span></span>
-   <span data-ttu-id="44499-2164">新增功能，正在商務用 Skype 或 Teams 進行通話時，若接收或起動新的通話時，會自動保留通話。</span><span class="sxs-lookup"><span data-stu-id="44499-2164">Add the ability to automatically hold calls when a call is active in Skype for Business or Teams and a new call is received or initiated.</span></span>
-   <span data-ttu-id="44499-2165">修正此問題：使用者使用全螢幕共用之後無法傳送 IM。</span><span class="sxs-lookup"><span data-stu-id="44499-2165">Fix an issue where users are unable to IM after full screen sharing.</span></span>
-   <span data-ttu-id="44499-2166">修正此問題：在大廳中的使用者進入會議室遭到拒絕時，不會收到通知。</span><span class="sxs-lookup"><span data-stu-id="44499-2166">Fix an issue where users in the lobby aren't notified when they're denied from entering the meeting.</span></span>
-   <span data-ttu-id="44499-2167">修正此問題：自動增益控制在通話期間無法控制的增加。</span><span class="sxs-lookup"><span data-stu-id="44499-2167">Fix an issue where automatic gain control increases uncontrollably during calls.</span></span>
-   <span data-ttu-id="44499-2168">修正此問題：將會議室資源信箱加入會議邀請時，使用者無法選取「會議選項」中的簡報者。</span><span class="sxs-lookup"><span data-stu-id="44499-2168">Fix an issue where users are unable to select a presenter in Meeting Options when a conference room resource mailbox is added to a meeting invite.</span></span>
-   <span data-ttu-id="44499-2169">修正此問題：如果 AllowlPVideo 設定為 False，桌面共用按鈕在端對端視訊通話期間無法使用。</span><span class="sxs-lookup"><span data-stu-id="44499-2169">Fix an issue where the desktop sharing button is dimmed during a peer-to-peer video call if AllowlPVideo is set to False.</span></span>
-   <span data-ttu-id="44499-2170">修正此問題：將現有會議 (建立時為「停用 IM」) 的「會議選項」設定變更為「啟用 IM」之後，IM 仍保持停用。</span><span class="sxs-lookup"><span data-stu-id="44499-2170">Fix an issue where IM stays disabled after changing the Meeting Option setting to Enable IM for existing meetings created with Disable IM.</span></span>
-   <span data-ttu-id="44499-2171">修正此問題：當滑鼠停留在聊天視窗的 [插入連結] 按鈕上時，工具提示不會顯示，並且在選取按鈕時沒有協助工具名稱。</span><span class="sxs-lookup"><span data-stu-id="44499-2171">Fix an issue where the tooltip isn't shown when hovering over the "Insert Link" button in the chat window, and there isn't an accessibility name when the button is selected.</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="44499-2172">Visio：功能更新</span><span class="sxs-lookup"><span data-stu-id="44499-2172">Visio: Feature updates</span></span>
-   <span data-ttu-id="44499-p336">**內建資料庫模型圖表：** 使用新的資料庫模型圖表範本，將您的資料庫精確地建模為 Visio 圖表。不需要增益集。</span><span class="sxs-lookup"><span data-stu-id="44499-p336">**Built-in database model diagrams:** Use the new Database Model Diagram template to accurately model your database as a Visio diagram. No add-in required.</span></span>
-   <span data-ttu-id="44499-2175">**更多商用圖表的樣板：** 使用新式圖形，以文氏圖表來比較和對比資料；或繪製循環、矩陣或金字塔圖表來表達您的想法。</span><span class="sxs-lookup"><span data-stu-id="44499-2175">**More stencils for business diagrams:** Using modern shapes, compare and contrast data with a Venn diagram, or draw Cycle, Matrix, or Pyramid diagrams to help tell your story.</span></span>
-   <span data-ttu-id="44499-p337">**建立網站的線框圖：** 快速地建立網站的線框圖，包括介面、瀏覽，以及如何共同作業。 [深入了解](https://support.office.com/article/2d54dc55-f5c4-49a2-85da-d649eb7fc281)</span><span class="sxs-lookup"><span data-stu-id="44499-p337">**Create a wireframe diagram for a website:** Quickly create a wireframe diagram of a website including interface, navigation, and how they work together. [Learn more](https://support.office.com/article/2d54dc55-f5c4-49a2-85da-d649eb7fc281)</span></span>
-   <span data-ttu-id="44499-p338">**建立行動應用程式的框線：** 使用範本來建立行動應用程式的框線。[深入了解](https://support.office.com/article/2d54dc55-f5c4-49a2-85da-d649eb7fc281)</span><span class="sxs-lookup"><span data-stu-id="44499-p338">**Create a wireframe of your mobile application:** Use a template to create a wireframe of your mobile application. [Learn more](https://support.office.com/article/2d54dc55-f5c4-49a2-85da-d649eb7fc281)</span></span>
-   <span data-ttu-id="44499-p339">**將資料圖形套用至 [資料視覺化工具] 圖表：** 藉由自動套用圖形資料作為資料圖形，以節省建立資料視覺化工具圖表的時間。[深入了解](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6?#apply_dg)</span><span class="sxs-lookup"><span data-stu-id="44499-p339">**Apply data graphics to Data Visualizer diagrams:** Save time when you create a Data Visualizer diagram by automatically applying shape data as data graphics. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6?#apply_dg)</span></span>
-   <span data-ttu-id="44499-p340">**繪圖共同作業：** 透過在商務用 OneDrive 或 SharePoint Online 上共用繪圖來與其他人合作。您可以看到誰在使用繪圖、新增註解以及查看檔案活動。 [深入了解](https://support.office.com/article/413c0b5a-0d52-4ace-af85-8b9bf115bbbf)</span><span class="sxs-lookup"><span data-stu-id="44499-p340">**Collaborate on drawings:** Work with others by sharing your drawings on OneDrive for Business or SharePoint Online. You can see who is working on the drawing, add comments, and see file activity. [Learn more](https://support.office.com/article/413c0b5a-0d52-4ace-af85-8b9bf115bbbf)</span></span>
-   <span data-ttu-id="44499-p341">**封鎖危險的副檔名：** 依預設，視為具有高風險以及內嵌為 OLE 封裝物件的副檔名 (例如.exe、.vbs 和 .js)，會遭到封鎖而無法啟動。[深入了解](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span><span class="sxs-lookup"><span data-stu-id="44499-p341">**Block dangerous extensions:** Extensions that are considered to be high risk, and are embedded as OLE package objects, are blocked, by default, from activating. For example, .exe, .vbs, and .js. [Learn more](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="44499-2188">Word：功能更新</span><span class="sxs-lookup"><span data-stu-id="44499-2188">Word: Feature updates</span></span>
-   <span data-ttu-id="44499-2189">**將 SVG 圖示轉換成圖形：** 將所有 SVG 圖片和圖示轉換成 Office 圖形，讓您可以變更其色彩、大小或材質。</span><span class="sxs-lookup"><span data-stu-id="44499-2189">**Convert SVG icons to shapes:** Transform all SVG pictures and icons into Office shapes so you can change their color, size, or texture.</span></span>
-   <span data-ttu-id="44499-p342">**字元數：** 當您輸入時，可在狀態列上顯示字元數。您可以從 [自訂狀態列] 功能表啟用此項目。</span><span class="sxs-lookup"><span data-stu-id="44499-p342">**Character count:** Display the character count on the status bar as you type. You can enable this from the Customize Status Bar menu.</span></span>
-   <span data-ttu-id="44499-2192">**快速存取您的網站和群組︰** 您可以使用 [檔案] 功能表，使用儲存在您常用的網站和群組中的文件。</span><span class="sxs-lookup"><span data-stu-id="44499-2192">**Quickly access your sites and groups:** Use the File menu to work with documents stored in your frequently used sites and groups.</span></span>
-   <span data-ttu-id="44499-p343">**Microsoft Translator：** 在 Word 中使用 Microsoft Translator 將文字、片語或整個文件翻譯成另一種語言。[深入了解](https://support.office.com/article/24a987b3-03a1-4c17-8c1b-54495fca6b17)</span><span class="sxs-lookup"><span data-stu-id="44499-p343">**Microsoft Translator:** Translate words, phrases, or the whole document into another language using Microsoft Translator, right in Word. [Learn more](https://support.office.com/article/24a987b3-03a1-4c17-8c1b-54495fca6b17)</span></span>
-   <span data-ttu-id="44499-p344">**數位鉛筆：** 使用新的鉛筆紋理手寫或繪製出您的創意。只需傾斜即可使用支援的數位鉛筆進行陰影處理。</span><span class="sxs-lookup"><span data-stu-id="44499-p344">**Digital Pencil:** Write or sketch out ideas with our new pencil texture. Simply tilt to do shading with supported digital pens.</span></span>
-   <span data-ttu-id="44499-p345">**LinkedIn 功能設定：** 移至 [檔案] \> [選項] \> [一般]，以控制 LinkedIn 功能是否要顯示在您的 Office 應用程式中。[深入了解](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)</span><span class="sxs-lookup"><span data-stu-id="44499-p345">**LinkedIn features setting:** Go to File \> Options \> General to control whether LinkedIn features are shown in your Office applications. [Learn more](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)</span></span>
-   <span data-ttu-id="44499-p346">**SharePoint 屬性面板：** 在文件中顯示和編輯 SharePoint 文件庫欄值。[檢視] 索引標籤上的功能區按鈕可讓您輕鬆存取面板，且 SharePoint 系統管理員可以使用文件庫設定來自動開啟 [屬性] 面板。</span><span class="sxs-lookup"><span data-stu-id="44499-p346">**SharePoint property panel:** Display and edit SharePoint document library column values from within a document. A ribbon button on the View tab provides easy access to the panel and SharePoint admins can use a document library setting to automatically open the property panel.</span></span>
-   <span data-ttu-id="44499-p347">**3D 模型：** 使用 3D 來增加文件的視覺效果和創意影響。輕鬆插入 3D 模型，然後將其旋轉 360 度。 [深入了解](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)</span><span class="sxs-lookup"><span data-stu-id="44499-p347">**3D models:** Use 3D to increase the visual and creative impact of your documents.  Easily insert a 3D model, then you can rotate it through 360 degrees. [Learn more](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)</span></span>
-   <span data-ttu-id="44499-2204">**新的筆跡效果：** 使用金屬畫筆和筆跡效果 (如彩虹、星空、熔岩、海洋、黃金、銀等) 來展現您的想法。</span><span class="sxs-lookup"><span data-stu-id="44499-2204">**New ink effects:** Express your ideas with flair using metallic pens and ink effects like rainbow, galaxy, lava, ocean, gold, silver and more.</span></span>
-   <span data-ttu-id="44499-p348">**共用檔案 UI：** 對於商務用 OneDrive 或 SharePoint 檔案，按一下功能區右上角的 [共用] 按鈕，或移至 [檔案] \> [共用] 可啟動經簡化並改良過的 [共用] 對話方塊。對於新的或儲存在本機的檔案，該 UI 可讓使用者輕鬆地將檔案上傳至 OneDrive 以啟動共同作業。</span><span class="sxs-lookup"><span data-stu-id="44499-p348">**Sharing files UI:** For OneDrive for Business or SharePoint files, clicking the Share button in the upper right-hand corner of the ribbon or going to File \> Share launches a simplified and improved Share dialog. For new or locally-saved files, the UI allows users to easily upload their files to OneDrive to start collaborating.</span></span>
-   <span data-ttu-id="44499-p349">**封鎖危險的副檔名：** 依預設，視為具有高風險以及內嵌為 OLE 封裝物件的副檔名 (例如.exe、.vbs 和 .js)，會遭到封鎖而無法啟動。[深入了解](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span><span class="sxs-lookup"><span data-stu-id="44499-p349">**Block dangerous extensions:** Extensions that are considered to be high risk, and are embedded as OLE package objects, are blocked, by default, from activating. For example, .exe, .vbs, and .js. [Learn more](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span></span>
-   <span data-ttu-id="44499-p350">**使用學習工具進行編輯：** 在 Word 的 Web 版面配置中現已提供學習工具。在您編輯時可調整文字間距和顯示音節。在任何檢視中，都可看見每個字會隨著大聲朗讀文件而以反白顯示。 [深入了解](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="44499-p350">**Edit using Learning Tools:** Learning Tools is now available in Word's Web Layout. Adjust your text spacing and show syllables while you edit. In any view, see each word highlighted as the document is read aloud. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>
-   <span data-ttu-id="44499-2214">**LaTeX 語法：** 使用 LaTeX 語法建立並編輯數學方程式。</span><span class="sxs-lookup"><span data-stu-id="44499-2214">**LaTeX syntax:** Create and edit math equations using LaTeX syntax.</span></span>
-   <span data-ttu-id="44499-p351">**有用的聲音可改善協助工具：** 開啟音訊提示可在作業時一面引導您。可在 [檔案] \> [選項] \> [輕鬆存取] 中找到此功能。無需增益集。 [深入了解](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)</span><span class="sxs-lookup"><span data-stu-id="44499-p351">**Helpful sounds improve accessibility:** Turn on audio cues to guide you as you work. Find it in File \> Options \> Ease of Access. No add-in needed. [Learn more](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)</span></span>
-   <span data-ttu-id="44499-2219">**依帳戶的檔案位置：** 開啟或儲存檔案時，位置清單會依照與其相關聯的帳戶整理。</span><span class="sxs-lookup"><span data-stu-id="44499-2219">**File locations by account:** When opening or saving a file, the list of places is organized by the account associated with them.</span></span>
-   <span data-ttu-id="44499-p352">**畫筆自訂：** 針對筆跡選擇畫筆和螢光筆的個人集合。您的自訂集可在您所有的 Windows 電腦上使用。</span><span class="sxs-lookup"><span data-stu-id="44499-p352">**Pen customization:** Choose a personal set of pens and highlighters for inking. Your customized set is available on all your Windows PCs.</span></span>
-   <span data-ttu-id="44499-p353">**以 [編輯器] 窗格增強了撰寫協助：** 使用 [編輯器] 窗格可得到進階拼字檢查、文法和書寫樣式的建議。它內建無障礙功能，並已改善對輔助技術的支援。</span><span class="sxs-lookup"><span data-stu-id="44499-p353">**Enhanced writing assistance with Editor pane:** Use the Editor pane for advanced spelling, grammar and writing style recommendations. It’s built to be accessible with improved support for assistive technologies.</span></span>

### <a name="word-security-updates"></a><span data-ttu-id="44499-2224">Word：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2224">Word: Security updates</span></span>
-   <span data-ttu-id="44499-2225">[CVE-2018-0792](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0792)：Microsoft Word 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2225">[CVE-2018-0792](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0792): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2226">[CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793)：Microsoft Outlook 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2226">[CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2227">[CVE-2018-0794](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0794)：Microsoft Word 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2227">[CVE-2018-0794](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0794): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2228">[CVE-2018-0798](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0798)：Microsoft Office 記憶體損毀弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2228">[CVE-2018-0798](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0798): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="44499-2229">[CVE-2018-0801](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0801)：Microsoft Office 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2229">[CVE-2018-0801](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0801): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2230">[CVE-2018-0802](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0802)：Microsoft Office 記憶體損毀弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2230">[CVE-2018-0802](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0802): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="44499-2231">[CVE-2018-0804](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0804)：Microsoft Word 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2231">[CVE-2018-0804](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0804): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2232">[CVE-2018-0805](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0805)：Microsoft Word 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2232">[CVE-2018-0805](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0805): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2233">[CVE-2018-0806](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0806)：Microsoft Word 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2233">[CVE-2018-0806](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0806): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2234">[CVE-2018-0807](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0807)：Microsoft Word 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2234">[CVE-2018-0807](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0807): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2235">[CVE-2018-0812](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0812)：Microsoft Word 記憶體損毀弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2235">[CVE-2018-0812](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0812): Microsoft Word Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="44499-2236">[CVE-2018-0919](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0919)：Microsoft Office 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2236">[CVE-2018-0919](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0919): Microsoft Office Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="44499-2237">[Advisory 170020](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170020)：Microsoft Office 深度防禦更新</span><span class="sxs-lookup"><span data-stu-id="44499-2237">[Advisory 170020](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170020): Microsoft Office Defense in Depth Update</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="44499-2238">Word：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2238">Word: Non-security updates</span></span>
-   <span data-ttu-id="44499-2239">修正此問題：Word 在從 SharePoint Online 開啟檔案時損毀。</span><span class="sxs-lookup"><span data-stu-id="44499-2239">Fix an issue where Word crashes when opening a file from SharePoint Online.</span></span>
-   <span data-ttu-id="44499-2240">修正此問題：小寫羅馬數字頁碼不正確地變更為大寫。</span><span class="sxs-lookup"><span data-stu-id="44499-2240">Fix an issue where lower-case Roman number page numbers are incorrectly changed to upper case.</span></span>
-   <span data-ttu-id="44499-2241">修正造成顯示記憶體不足訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-2241">Fix an issue that causes an insufficient memory message to appear.</span></span>
-   <span data-ttu-id="44499-2242">修正此問題：Word 在執行 Windows 7 的電腦上無法開啟，且該電腦上未安裝 客戶體驗和診斷遙測的更新。</span><span class="sxs-lookup"><span data-stu-id="44499-2242">Fix an issue where Word won’t open on a computer running Windows 7 that doesn't have the update for customer experience and diagnostic telemetry installed.</span></span>
-   <span data-ttu-id="44499-2243">修正此問題：清單中的項目符號無法列印。</span><span class="sxs-lookup"><span data-stu-id="44499-2243">Fix an issue where bullets in lists don’t print.</span></span>
-   <span data-ttu-id="44499-2244">修正此問題：當使用者嘗試對商務用 OneDrive 上的現有文件執行 [另存新檔] 時，Word 會當機，並取消儲存作業或嘗試合併現有變更。</span><span class="sxs-lookup"><span data-stu-id="44499-2244">Fix an issue where Word crashes when a user tries to do a Save As to an existing document on OneDrive for Business and then cancels the save or tries to merge existing changes.</span></span>
-   <span data-ttu-id="44499-2245">修正此問題：執行合併列印精靈時，篩選包含 null (空白) 值的資料來源欄位失敗。</span><span class="sxs-lookup"><span data-stu-id="44499-2245">Fix an issue where filtering on data source fields containing null (empty) values fails when running the Mail Merge wizard.</span></span>
-   <span data-ttu-id="44499-p354">修正此問題：正在儲存同步備份檔案時，Office 無法寫入磁碟，但 Office 會不斷上傳檔案到 OneDrive。有了此修正程式之後，使用者現在會看到一則錯誤訊息，且 Office 不會繼續上傳。</span><span class="sxs-lookup"><span data-stu-id="44499-p354">Fix an issue where, when saving a sync-backed file, Office fails to write to disk, but Office keeps uploading the file to OneDrive. With this fix, user will now see an error message and the upload won't proceed.</span></span>
-   <span data-ttu-id="44499-2248">修正此問題：要移除文件中的 IRM 保護時並沒有移除保護。</span><span class="sxs-lookup"><span data-stu-id="44499-2248">Fix an issue where removing IRM protection on a document doesn’t remove the protection.</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="44499-2249">Office 套件：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2249">Office suite: Security updates</span></span>
-   <span data-ttu-id="44499-2250">[CVE-2017-11882](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11882)：Microsoft Office 記憶體損毀弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2250">[CVE-2017-11882](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11882): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="44499-2251">[CVE-2018-0795](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0795)：Microsoft Office 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2251">[CVE-2018-0795](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0795): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2252">[CVE-2018-0851](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0851)：Microsoft Office 記憶體損毀弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2252">[CVE-2018-0851](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0851): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="44499-2253">[CVE-2018-0853](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0853)：Microsoft Office 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2253">[CVE-2018-0853](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0853): Microsoft Office Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="44499-2254">[CVE-2018-0950](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0950)：Microsoft Office 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2254">[CVE-2018-0950](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0950): Microsoft Office Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="44499-2255">[CVE-2018-1026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1026)：Microsoft Office 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2255">[CVE-2018-1026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1026): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2256">[CVE-2018-1030](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1030)：Microsoft Office 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2256">[CVE-2018-1030](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1030): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2257">[CVE-2018-8157](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8157)：Microsoft Office 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2257">[CVE-2018-8157](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8157): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2258">[CVE-2018-8158](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8158)：Microsoft Office 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2258">[CVE-2018-8158](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8158): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2259">[CVE-2018-8281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8281)：Microsoft Office 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2259">[CVE-2018-8281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8281): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2260">[Advisory 180003](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180003)：Microsoft Office 深度防禦更新</span><span class="sxs-lookup"><span data-stu-id="44499-2260">[Advisory 180003](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180003): Microsoft Office Defense in Depth Update</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="44499-2261">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2261">Office suite: Non-security updates</span></span>
-   <span data-ttu-id="44499-2262">修正當使用 Configuration Manager 將更新部署至執行 Office 應用程式的用戶端時，更新未在 Office 應用程式執行時並重新啟動裝置之後套用的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-2262">Fix an issue where, when deploying updates using Configuration Manager to a client that has running Office applications the update is not applied after restarting the device while Office applications are running.</span></span>
-   <span data-ttu-id="44499-2263">修正此問題：開啟應用程式時，使用者可能會看到以安全模式啟動的訊息，然後應用程式無法開啟。</span><span class="sxs-lookup"><span data-stu-id="44499-2263">Fix an issue where, when opening an application, the user might see a message about launching in Safe mode and then the application fails to open.</span></span>
-   <span data-ttu-id="44499-2264">當啟用 Office COM 物件，讓 Office 365 用戶端更新由 Configuration Manager 管理，[立即更新] 選項會在 [檔案] \> [帳戶] \> [更新選項] 中隱藏。</span><span class="sxs-lookup"><span data-stu-id="44499-2264">The Update Now option is hidden from File \> Account \> Update Options when an Office COM object is enabled so that Office 365 client updates are managed by Configuration Manager.</span></span>
-   <span data-ttu-id="44499-2265">修正此問題：當使用者嘗試使用 [啟動 Office] 對話方塊來啟動 Office 時，Office 應用程式會當機。</span><span class="sxs-lookup"><span data-stu-id="44499-2265">Fix an issue where the Office app crashes when the user tries to activate Office using the Activate Office dialog box.</span></span>
-   <span data-ttu-id="44499-2266">修正在動態 DPI 環境下的 Office 增益集中縮放與調整大小的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-2266">Fix an issue with zooming and scaling in Office Add-ins under dynamic DPI environment.</span></span>
-   <span data-ttu-id="44499-2267">修正此問題：即使目前已安裝 Office 365 ProPlus，Office 設定服務提供者 (CSP) 的 CurrentStatus 節點仍會傳回空字串。</span><span class="sxs-lookup"><span data-stu-id="44499-2267">Fix an issue where the CurrentStatus node of the Office configuration service provider (CSP) returns an empty string even if Office 365 ProPlus is currently installed.</span></span>
-   <span data-ttu-id="44499-2268">修正此問題：因為同一部電腦上所有的 Office 應用程式版本會共用 .box 檔案，而導致 .box 檔案格式變更；該問題會影響同一部電腦上所安裝舊版 Office 的功能。</span><span class="sxs-lookup"><span data-stu-id="44499-2268">Fix an issue that causes .box file format changes, which impacts functionality of older versions of Office installed on the same computer, because .box files are shared across all versions of an Office app on the same computer.</span></span>
-   <span data-ttu-id="44499-2269">修正會導致更新安裝在特定情況下耗費長時間的錯誤。</span><span class="sxs-lookup"><span data-stu-id="44499-2269">Fix a bug that caused update install to take a long time in certain scenarios.</span></span> 
-   <span data-ttu-id="44499-2270">修正此問題：SVG 測試失敗</span><span class="sxs-lookup"><span data-stu-id="44499-2270">Fix an issue where SVG tests are failing</span></span>
-   <span data-ttu-id="44499-2271">修正當使用 Configuration Manager 將更新部署至執行 Office 應用程式的用戶端時，更新未在 Office 應用程式執行時並重新啟動裝置之後套用的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-2271">Fix an issue where, when deploying updates using Configuration Manager to a client that has running Office applications the update is not applied after restarting the device while Office applications are running.</span></span>


## <a name="version-1708-july-10"></a><span data-ttu-id="44499-2272">版本 1708：7 月 10 日</span><span class="sxs-lookup"><span data-stu-id="44499-2272">Version 1708: July 10</span></span>
<span data-ttu-id="44499-2273">*版本 1708 (組建 8431.2280)*</span><span class="sxs-lookup"><span data-stu-id="44499-2273">*Version 1708 (Build 8431.2280)*</span></span>

<span data-ttu-id="44499-2274">*這是自從 2018 年 1 月以來提供的半年通道版本。它會繼續受到支援並接收安全性更新，直到 2019 年 3 月為止。不過，目前已提供新的半年通道版本 — 版本 1803 (組建 9126.2259) — 其中包含了新功能、安全性更新和非安全性更新。*</span><span class="sxs-lookup"><span data-stu-id="44499-2274">*This is the Semi-Annual Channel release that's been available since January 2018. It will continue to be supported and receive security updates until March 2019. But, a new Semi-Annual Channel release is now available — Version 1803 (Build 9126.2259) — which contains new features, security updates, and non-security updates.*</span></span>

### <a name="access-security-updates"></a><span data-ttu-id="44499-2275">Access：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2275">Access: Security updates</span></span>
-   <span data-ttu-id="44499-2276">[CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312)：Microsoft Access 遠端程式碼執行 Use After Free 弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2276">[CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312): Microsoft Access Remote Code Execution Use After Free Vulnerability</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="44499-2277">Outlook：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2277">Outlook: Security updates</span></span>
-   <span data-ttu-id="44499-2278">[CVE-2018-8310](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8310)：Microsoft Office 竄改弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2278">[CVE-2018-8310](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8310): Microsoft Office Tampering Vulnerability</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="44499-2279">Office 套件：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2279">Office Suite: Security updates</span></span>
-   <span data-ttu-id="44499-2280">[CVE-2018-8281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8281)：Microsoft Office 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2280">[CVE-2018-8281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8281): Microsoft Office Remote Code Execution Vulnerability</span></span>


## <a name="version-1708-june-12"></a><span data-ttu-id="44499-2281">版本 1708：6 月 12 日</span><span class="sxs-lookup"><span data-stu-id="44499-2281">Version 1708: June 12</span></span>
<span data-ttu-id="44499-2282">*版本 1708 (組建 8431.2270)*</span><span class="sxs-lookup"><span data-stu-id="44499-2282">*Version 1708 (Build 8431.2270)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="44499-2283">Excel：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2283">Excel: Security updates</span></span>
-   <span data-ttu-id="44499-2284">[CVE-2018-8246](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8246)：Microsoft Excel 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2284">[CVE-2018-8246](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8246): Microsoft Excel Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="44499-2285">[CVE-2018-8248](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8248)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2285">[CVE-2018-8248](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8248): Microsoft Excel Remote Code Execution Vulnerability</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="44499-2286">Outlook：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2286">Outlook: Security updates</span></span>
-   <span data-ttu-id="44499-2287">[CVE-2018-8244](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8244)：Microsoft Outlook 提高權限弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2287">[CVE-2018-8244](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8244): Microsoft Outlook Elevation of Privilege Vulnerability</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="44499-2288">Outlook：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2288">Outlook: Non-security updates</span></span>
-   <span data-ttu-id="44499-2289">修正造成 Windows 7 SP1 使用者無法將成員新增至「新式群組」的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-2289">Fix an issue that caused users of Windows 7 SP1 to be unable to add members to Modern Groups.</span></span>



## <a name="version-1705-june-12"></a><span data-ttu-id="44499-2290">版本 1705：6 月 12 日</span><span class="sxs-lookup"><span data-stu-id="44499-2290">Version 1705: June 12</span></span>
<span data-ttu-id="44499-2291">*版本 1705 (組建 8201.2294)*</span><span class="sxs-lookup"><span data-stu-id="44499-2291">*Version 1705 (Build 8201.2294)*</span></span>

<span data-ttu-id="44499-2292">*這是自從 2017 年 9 月以來提供的順延通道版本。它會繼續受到支援並接收安全性更新，直到 2018 年 7 月為止。不過，目前已提供新的半年通道版本 — 版本 1708 (組建 8431.2270) — 其中包含了新功能、安全性更新和非安全性更新。*</span><span class="sxs-lookup"><span data-stu-id="44499-2292">*This is the Deferred Channel release that's been available since September 2017. It will continue to be supported and receive security updates until July 2018. But, a new Semi-Annual Channel release is now available — Version 1708 (Build 8431.2270) — which contains new features, security updates, and non-security updates.*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="44499-2293">Excel：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2293">Excel: Security updates</span></span>
-   <span data-ttu-id="44499-2294">[CVE-2018-8246](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8246)：Microsoft Excel 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2294">[CVE-2018-8246](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8246): Microsoft Excel Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="44499-2295">[CVE-2018-8248](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8248)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2295">[CVE-2018-8248](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8248): Microsoft Excel Remote Code Execution Vulnerability</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="44499-2296">Outlook：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2296">Outlook: Security updates</span></span>
-   <span data-ttu-id="44499-2297">[CVE-2018-8244](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8244)：Microsoft Outlook 提高權限弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2297">[CVE-2018-8244](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8244): Microsoft Outlook Elevation of Privilege Vulnerability</span></span>



## <a name="version-1708-may-8"></a><span data-ttu-id="44499-2298">版本 1708：5 月 8 日</span><span class="sxs-lookup"><span data-stu-id="44499-2298">Version 1708: May 8</span></span>
<span data-ttu-id="44499-2299">*版本 1708 (組建 8431.2250)*</span><span class="sxs-lookup"><span data-stu-id="44499-2299">*Version 1708 (Build 8431.2250)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="44499-2300">Excel：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2300">Excel: Security updates</span></span>
-   <span data-ttu-id="44499-2301">[CVE-2018-8147](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8147)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2301">[CVE-2018-8147](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8147): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2302">[CVE-2018-8148](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8148)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2302">[CVE-2018-8148](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8148): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2303">[CVE-2018-8162](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8162)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2303">[CVE-2018-8162](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8162): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2304">[CVE-2018-8163](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8163)：Microsoft Excel 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2304">[CVE-2018-8163](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8163): Microsoft Excel Information Disclosure Vulnerability</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="44499-2305">Outlook：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2305">Outlook: Security updates</span></span>
-   <span data-ttu-id="44499-2306">[CVE-2018-8150](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8150)：Microsoft Outlook 安全性功能略過的弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2306">[CVE-2018-8150](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8150): Microsoft Outlook Security Feature Bypass Vulnerability</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="44499-2307">Office 套件：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2307">Office suite: Security updates</span></span>
-   <span data-ttu-id="44499-2308">[CVE-2018-8157](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8157)：Microsoft Office 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2308">[CVE-2018-8157](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8157): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2309">[CVE-2018-8158](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8158)：Microsoft Office 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2309">[CVE-2018-8158](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8158): Microsoft Office Remote Code Execution Vulnerability</span></span>



## <a name="version-1705-may-8"></a><span data-ttu-id="44499-2310">版本 1705：5 月 8 日</span><span class="sxs-lookup"><span data-stu-id="44499-2310">Version 1705: May 8</span></span>
<span data-ttu-id="44499-2311">*版本 1705 (組建 8201.2278)*</span><span class="sxs-lookup"><span data-stu-id="44499-2311">*Version 1705 (Build 8201.2278)*</span></span>

<span data-ttu-id="44499-2312">*這是自從 2017 年 9 月以來提供的順延通道版本。它會繼續受到支援並接收安全性更新，直到 2018 年 7 月為止。不過，目前已提供新的半年通道版本 — 1708 版 (組建 8431.2250) — 其中包含了新功能、安全性更新和非安全性更新。*</span><span class="sxs-lookup"><span data-stu-id="44499-2312">*This is the Deferred Channel release that's been available since September 2017. It will continue to be supported and receive security updates until July 2018. But, a new Semi-Annual Channel release is now available — Version 1708 (Build 8431.2250) — which contains new features, security updates, and non-security updates.*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="44499-2313">Excel：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2313">Excel: Security updates</span></span>
-   <span data-ttu-id="44499-2314">[CVE-2018-8147](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8147)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2314">[CVE-2018-8147](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8147): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2315">[CVE-2018-8148](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8148)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2315">[CVE-2018-8148](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8148): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2316">[CVE-2018-8162](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8162)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2316">[CVE-2018-8162](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8162): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2317">[CVE-2018-8163](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8163)：Microsoft Excel 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2317">[CVE-2018-8163](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8163): Microsoft Excel Information Disclosure Vulnerability</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="44499-2318">Outlook：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2318">Outlook: Security updates</span></span>
-   <span data-ttu-id="44499-2319">[CVE-2018-8150](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8150)：Microsoft Outlook 安全性功能略過的弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2319">[CVE-2018-8150](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8150): Microsoft Outlook Security Feature Bypass Vulnerability</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="44499-2320">Office 套件：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2320">Office suite: Security updates</span></span>
-   <span data-ttu-id="44499-2321">[CVE-2018-8157](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8157)：Microsoft Office 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2321">[CVE-2018-8157](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8157): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2322">[CVE-2018-8158](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8158)：Microsoft Office 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2322">[CVE-2018-8158](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8158): Microsoft Office Remote Code Execution Vulnerability</span></span>



## <a name="version-1708-april-10"></a><span data-ttu-id="44499-2323">版本 1708：4 月 10 日</span><span class="sxs-lookup"><span data-stu-id="44499-2323">Version 1708: April 10</span></span>
<span data-ttu-id="44499-2324">*版本 1708 (組建 8431.2242)*</span><span class="sxs-lookup"><span data-stu-id="44499-2324">*Version 1708 (Build 8431.2242)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="44499-2325">Excel：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2325">Excel: Security updates</span></span>
-   <span data-ttu-id="44499-2326">[CVE-2018-1029](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1029)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2326">[CVE-2018-1029](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1029): Microsoft Excel Remote Code Execution Vulnerability</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="44499-2327">商務用 Skype：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2327">Skype for Business: Non-security updates</span></span>
-   <span data-ttu-id="44499-2328">修正與 TLS 1.2 支援相關的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-2328">Fix an issue related to TLS 1.2 support.</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="44499-2329">Office 套件：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2329">Office suite: Security updates</span></span>
-   <span data-ttu-id="44499-2330">[CVE-2018-0950](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0950)：Microsoft Office 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2330">[CVE-2018-0950](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0950): Microsoft Office Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="44499-2331">[CVE-2018-1026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1026)：Microsoft Office 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2331">[CVE-2018-1026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1026): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2332">[CVE-2018-1030](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1030)：Microsoft Office 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2332">[CVE-2018-1030](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1030): Microsoft Office Remote Code Execution Vulnerability</span></span>



## <a name="version-1705-april-10"></a><span data-ttu-id="44499-2333">版本 1705：4 月 10 日</span><span class="sxs-lookup"><span data-stu-id="44499-2333">Version 1705: April 10</span></span>
<span data-ttu-id="44499-2334">*版本 1705 (組建 8201.2272)*</span><span class="sxs-lookup"><span data-stu-id="44499-2334">*Version 1705 (Build 8201.2272)*</span></span>

<span data-ttu-id="44499-2335">*這是自從 2017 年 9 月以來提供的順延通道版本。它會繼續受到支援並接收安全性更新，直到 2018 年 7 月為止。不過，目前已提供新的半年通道版本 — 1708 版 (組建 8431.2242) — 其中包含了新功能、安全性更新和非安全性更新。*</span><span class="sxs-lookup"><span data-stu-id="44499-2335">*This is the Deferred Channel release that's been available since September 2017. It will continue to be supported and receive security updates until July 2018. But, a new Semi-Annual Channel release is now available — Version 1708 (Build 8431.2242) — which contains new features, security updates, and non-security updates.*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="44499-2336">Excel：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2336">Excel: Security updates</span></span>
-   <span data-ttu-id="44499-2337">[CVE-2018-1029](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1029)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2337">[CVE-2018-1029](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1029): Microsoft Excel Remote Code Execution Vulnerability</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="44499-2338">Office 套件：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2338">Office suite: Security updates</span></span>
-   <span data-ttu-id="44499-2339">[CVE-2018-0950](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0950)：Microsoft Office 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2339">[CVE-2018-0950](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0950): Microsoft Office Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="44499-2340">[CVE-2018-1026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1026)：Microsoft Office 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2340">[CVE-2018-1026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1026): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2341">[CVE-2018-1030](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1030)：Microsoft Office 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2341">[CVE-2018-1030](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1030): Microsoft Office Remote Code Execution Vulnerability</span></span>



## <a name="version-1708-march-13"></a><span data-ttu-id="44499-2342">版本 1708：3 月 13 日</span><span class="sxs-lookup"><span data-stu-id="44499-2342">Version 1708: March 13</span></span>
<span data-ttu-id="44499-2343">*版本 1708 (組建 8431.2236)*</span><span class="sxs-lookup"><span data-stu-id="44499-2343">*Version 1708 (Build 8431.2236)*</span></span>

### <a name="access-security-updates"></a><span data-ttu-id="44499-2344">Access：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2344">Access: Security updates</span></span>
-   <span data-ttu-id="44499-2345">[CVE-2018-0903](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0903)：Microsoft Access 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2345">[CVE-2018-0903](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0903): Microsoft Access Remote Code Execution Vulnerability</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="44499-2346">Excel：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2346">Excel: Security updates</span></span>
-   <span data-ttu-id="44499-2347">[CVE-2018-0907](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0907)：Microsoft Office Excel 安全性功能略過</span><span class="sxs-lookup"><span data-stu-id="44499-2347">[CVE-2018-0907](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0907): Microsoft Office Excel Security Feature Bypass</span></span>

### <a name="word-security-updates"></a><span data-ttu-id="44499-2348">Word：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2348">Word: Security updates</span></span>
-   <span data-ttu-id="44499-2349">[CVE-2018-0919](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0919)：Microsoft Office 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2349">[CVE-2018-0919](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0919): Microsoft Office Information Disclosure Vulnerability</span></span>



## <a name="version-1705-march-13"></a><span data-ttu-id="44499-2350">版本 1705：3 月 13 日</span><span class="sxs-lookup"><span data-stu-id="44499-2350">Version 1705: March 13</span></span>
<span data-ttu-id="44499-2351">*版本 1705 (組建 8201.2265)*</span><span class="sxs-lookup"><span data-stu-id="44499-2351">*Version 1705 (Build 8201.2265)*</span></span>

<span data-ttu-id="44499-2352">*這是自從 2017 年 9 月以來提供的順延通道版本。它會繼續受到支援並接收安全性更新，直到 2018 年 7 月為止。不過，目前已提供新的半年通道版本 — 1708 版 (組建 8431.2236) — 其中包含了新功能、安全性更新和非安全性更新。*</span><span class="sxs-lookup"><span data-stu-id="44499-2352">*This is the Deferred Channel release that's been available since September 2017. It will continue to be supported and receive security updates until July 2018. But, a new Semi-Annual Channel release is now available — Version 1708 (Build 8431.2236) — which contains new features, security updates, and non-security updates.*</span></span>

### <a name="access-security-updates"></a><span data-ttu-id="44499-2353">Access：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2353">Access: Security updates</span></span>
-   <span data-ttu-id="44499-2354">[CVE-2018-0903](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0903)：Microsoft Access 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2354">[CVE-2018-0903](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0903): Microsoft Access Remote Code Execution Vulnerability</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="44499-2355">Excel：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2355">Excel: Security updates</span></span>
-   <span data-ttu-id="44499-2356">[CVE-2018-0907](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0907)：Microsoft Office Excel 安全性功能略過</span><span class="sxs-lookup"><span data-stu-id="44499-2356">[CVE-2018-0907](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0907): Microsoft Office Excel Security Feature Bypass</span></span>

### <a name="word-security-updates"></a><span data-ttu-id="44499-2357">Word：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2357">Word: Security updates</span></span>
-   <span data-ttu-id="44499-2358">[CVE-2018-0919](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0919)：Microsoft Office 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2358">[CVE-2018-0919](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0919): Microsoft Office Information Disclosure Vulnerability</span></span>



## <a name="version-1708-february-13"></a><span data-ttu-id="44499-2359">版本 1708：2 月 13 日</span><span class="sxs-lookup"><span data-stu-id="44499-2359">Version 1708: February 13</span></span>
<span data-ttu-id="44499-2360">*版本 1708 (組建 8431.2215)*</span><span class="sxs-lookup"><span data-stu-id="44499-2360">*Version 1708 (Build 8431.2215)*</span></span>

### <a name="access-non-security-updates"></a><span data-ttu-id="44499-2361">Access：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2361">Access: Non-security updates</span></span>
-   <span data-ttu-id="44499-2362">修正下列問題：當使用多個項目表單時，調整滑鼠滾輪或捲軸捲動方塊並不會變更表單中顯示的項目。</span><span class="sxs-lookup"><span data-stu-id="44499-2362">Fix an issue where, when using a multiple items form, adjusting the position of the mouse wheel or the scrollbar thumb doesn't change the items that are displayed in the form.</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="44499-2363">Excel：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2363">Excel: Security updates</span></span>
-   <span data-ttu-id="44499-2364">[CVE-2018-0841](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0841)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2364">[CVE-2018-0841](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0841): Microsoft Excel Remote Code Execution Vulnerability</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="44499-2365">Outlook：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2365">Outlook: Security updates</span></span>
-   <span data-ttu-id="44499-2366">[CVE-2018-0850](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0850)：Microsoft Outlook 提高權限弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2366">[CVE-2018-0850](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0850): Microsoft Outlook Elevation of Privilege Vulnerability</span></span>
-   <span data-ttu-id="44499-2367">[CVE-2018-0852](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0852)：Microsoft Outlook 記憶體損毀弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2367">[CVE-2018-0852](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0852): Microsoft Outlook Memory Corruption Vulnerability</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="44499-2368">Office 套件：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2368">Office suite: Security updates</span></span>
-   <span data-ttu-id="44499-2369">[CVE-2018-0851](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0851)：Microsoft Office 記憶體損毀弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2369">[CVE-2018-0851](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0851): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="44499-2370">[CVE-2018-0853](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0853)：Microsoft Office 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2370">[CVE-2018-0853](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0853): Microsoft Office Information Disclosure Vulnerability</span></span>



## <a name="version-1705-february-13"></a><span data-ttu-id="44499-2371">版本 1705：2 月 13 日</span><span class="sxs-lookup"><span data-stu-id="44499-2371">Version 1705: February 13</span></span>
<span data-ttu-id="44499-2372">*版本 1705 (組建 8201.2258)*</span><span class="sxs-lookup"><span data-stu-id="44499-2372">*Version 1705 (Build 8201.2258)*</span></span>

<span data-ttu-id="44499-2373">*這是自從 2017 年 9 月以來提供的順延通道版本。它會繼續受到支援並接收安全性更新，直到 2018 年 7 月為止。不過，目前已提供新的半年通道版本 — 1708 版 (組建 8431.2215) — 其中包含了新功能、安全性更新和非安全性更新。*</span><span class="sxs-lookup"><span data-stu-id="44499-2373">*This is the Deferred Channel release that's been available since September 2017. It will continue to be supported and receive security updates until July 2018. But, a new Semi-Annual Channel release is now available — Version 1708 (Build 8431.2215) — which contains new features, security updates, and non-security updates.*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="44499-2374">Excel：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2374">Excel: Security updates</span></span>
-   <span data-ttu-id="44499-2375">[CVE-2018-0841](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0841)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2375">[CVE-2018-0841](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0841): Microsoft Excel Remote Code Execution Vulnerability</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="44499-2376">Outlook：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2376">Outlook: Security updates</span></span>
-   <span data-ttu-id="44499-2377">[CVE-2018-0850](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0850)：Microsoft Outlook 提高權限弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2377">[CVE-2018-0850](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0850): Microsoft Outlook Elevation of Privilege Vulnerability</span></span>
-   <span data-ttu-id="44499-2378">[CVE-2018-0852](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0852)：Microsoft Outlook 記憶體損毀弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2378">[CVE-2018-0852](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0852): Microsoft Outlook Memory Corruption Vulnerability</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="44499-2379">Office 套件：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2379">Office suite: Security updates</span></span>
-   <span data-ttu-id="44499-2380">[CVE-2018-0851](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0851)：Microsoft Office 記憶體損毀弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2380">[CVE-2018-0851](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0851): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="44499-2381">[CVE-2018-0853](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0853)：Microsoft Office 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2381">[CVE-2018-0853](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0853): Microsoft Office Information Disclosure Vulnerability</span></span>



## <a name="version-1708-january-9"></a><span data-ttu-id="44499-2382">版本 1708：1 月 9 日</span><span class="sxs-lookup"><span data-stu-id="44499-2382">Version 1708: January 9</span></span>
<span data-ttu-id="44499-2383">*版本 1708 (組建 8431.2153)*</span><span class="sxs-lookup"><span data-stu-id="44499-2383">*Version 1708 (Build 8431.2153)*</span></span>

### <a name="access-feature-updates"></a><span data-ttu-id="44499-2384">Access：功能更新</span><span class="sxs-lookup"><span data-stu-id="44499-2384">Access: Feature updates</span></span>
-   <span data-ttu-id="44499-2385">**標籤名稱屬性：** 藉由使標籤與表單上的控制項相關聯來增強協助工具。</span><span class="sxs-lookup"><span data-stu-id="44499-2385">**Label Name property:** Enhance accessibility by associating a label with a control on a form.</span></span>
-   <span data-ttu-id="44499-2386">**編輯新項目變得更無障礙：** 您可以使用快速鍵盤快速鍵 (Ctrl + E) 從下拉式方塊或清單方塊編輯新項目。</span><span class="sxs-lookup"><span data-stu-id="44499-2386">**Editing a new item is more accessible:** Use a quick keyboard shortcut (Ctrl+E) to edit a new item from a Combo Box or List Box.</span></span>
-   <span data-ttu-id="44499-p355">**動態連接器：** 從 Microsoft Dynamics 匯入資料或連結到儲存在其中的資料。[詳細資訊](https://support.office.com/article/636079c1-9fc3-4fca-8410-6596d62223da)</span><span class="sxs-lookup"><span data-stu-id="44499-p355">**Dynamics connector:** Import data from or link to data stored in Microsoft Dynamics. [More information](https://support.office.com/article/636079c1-9fc3-4fca-8410-6596d62223da)</span></span>
-   <span data-ttu-id="44499-p356">**Salesforce 連接器：** 匯入資料或連結到儲存在 Salesforce 的資料。[詳細資訊](https://support.office.com/article/7375ffb6-1d6a-46f1-bb0c-c6ac3c58f5a0)</span><span class="sxs-lookup"><span data-stu-id="44499-p356">**Salesforce connector:** Import data from or link to data stored in Salesforce. [More information](https://support.office.com/article/7375ffb6-1d6a-46f1-bb0c-c6ac3c58f5a0)</span></span>

### <a name="access-non-security-updates"></a><span data-ttu-id="44499-2391">Access：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2391">Access: Non-security updates</span></span>
-   <span data-ttu-id="44499-2392">修正此問題：嘗試在文字方塊或下拉式方塊中選取文字似乎會選取所有文字，而不是表示選取範圍。</span><span class="sxs-lookup"><span data-stu-id="44499-2392">Fix an issue where attempting to select text in a text box or combo box appears to select all the text, rather than the indication selection.</span></span>
-   <span data-ttu-id="44499-2393">修正此問題：如果查詢與 Microsoft Dynamics 連結的資料表中的主索引鍵有聯接，則查詢不會執行。</span><span class="sxs-lookup"><span data-stu-id="44499-2393">Fix an issue where a query won't execute if the query has a join with a primary key from a Microsoft Dynamics linked table.</span></span>
-   <span data-ttu-id="44499-2394">修正此問題：Microsoft Dynamics 資料表中的貨幣值未顯示小數位數。</span><span class="sxs-lookup"><span data-stu-id="44499-2394">Fix an issue where decimal places aren't shown for currency values in a Microsoft Dynamics table.</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="44499-2395">Excel：功能更新</span><span class="sxs-lookup"><span data-stu-id="44499-2395">Excel: Feature updates</span></span>
-   <span data-ttu-id="44499-2396">**「從範例新增資料行」增強功能：** 支援多個日期/時間、數學、和索引資料行轉換。</span><span class="sxs-lookup"><span data-stu-id="44499-2396">**“Add Column from Examples” enhancements:** Supports more Date/Time, Math, and Index Column transformations.</span></span>
-   <span data-ttu-id="44499-2397">**效能改善：** Excel 能更快速地開啟具有多個工作表的複雜活頁簿，讓您可以使用大範圍的公式、篩選大量資料列，或更快地複製和貼上。</span><span class="sxs-lookup"><span data-stu-id="44499-2397">**Performance improvements:** Excel opens complex workbooks with multiple sheets faster, so you can crunch formulas with large ranges, filter lots of rows, or copy and paste quicker.</span></span>
-   <span data-ttu-id="44499-2398">**插入線上圖片：** 用以選取影像和屬性資訊的新登陸頁面會隨著影像自動插入。</span><span class="sxs-lookup"><span data-stu-id="44499-2398">**Insert online pictures:** New landing page for selecting images and attribution information is automatically inserted with the image.</span></span>
-   <span data-ttu-id="44499-2399">**Azure Data Lake Store 連接器：** 使用者現在可以從 Azure Data Lake Store 匯入資料。</span><span class="sxs-lookup"><span data-stu-id="44499-2399">**Azure Data Lake Store connector:** Users can now import data from Azure Data Lake Store.</span></span>
-   <span data-ttu-id="44499-2400">**「從範例新增資料行」增強功能：** 支援建議、更多日期/時間作業及其他轉換。</span><span class="sxs-lookup"><span data-stu-id="44499-2400">**"Add column from Examples" enhancements:** Supports suggestions, more Date/Time operations, and additional transformations.</span></span>
-   <span data-ttu-id="44499-2401">**[資料] 索引標籤**：在 [資料] 索引標籤上的功能區按鈕，已重新排列成兩個新的群組：「取得與轉換資料」及「查詢與連線」。</span><span class="sxs-lookup"><span data-stu-id="44499-2401">**Data tab**: Ribbon buttons on the Data tab have been rearranged into two new groups: Get & Transform Data and Queries & Connections.</span></span>
-   <span data-ttu-id="44499-2402">**共用查詢**：將任何查詢定義匯出至 Office 資料庫連線 (ODC) 檔，然後在活頁簿之間共用或與其他人共用。</span><span class="sxs-lookup"><span data-stu-id="44499-2402">**Share queries**: Export any query definition into an Office Database Connection (ODC) file, and then share it across workbooks or with others.</span></span>
-   <span data-ttu-id="44499-2403">**載入資料：** 從查詢直接將資料載入到樞紐分析表或樞紐分析圖中，而不必將資料儲存到資料模型內。</span><span class="sxs-lookup"><span data-stu-id="44499-2403">**Load data:** Load data from a query directly into PivotTables or PivotCharts without having to save the data into the Data Model.</span></span>
-   <span data-ttu-id="44499-2404">**共用的檔案活動︰** 選擇檔案右上角的 [活動] 按鈕，以查看在商務用 OneDrive 或 SharePoint 中共用檔案的共用、編輯、重新命名或還原。</span><span class="sxs-lookup"><span data-stu-id="44499-2404">**Shared file activity:** Choose the Activity button in the upper right corner of the file to see when a file shared in OneDrive for Business or SharePoint was shared, edited, renamed, or restored.</span></span>
-   <span data-ttu-id="44499-p357">**安全連結：** 當使用者按一下連結時，Office 365 進階威脅防護 (ATP) 會檢查是否為惡意的連結。如果連結被視為惡意，系統就會將使用者重新導向至警告頁面而非原始的目標 URL。 [詳細資訊](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)</span><span class="sxs-lookup"><span data-stu-id="44499-p357">**Safe links:** When a user clicks on a link, Office 365 Advanced Threat Protection (ATP) inspects the link to see if it’s malicious. If the link is deemed malicious, the user is redirected to a warning page instead of the original target URL. [More information](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)</span></span>
-   <span data-ttu-id="44499-p358">**增強的資料匯入功能︰** 輕鬆地從各種來源匯入圖形資料。使用 [查詢和連線] 側邊窗格來管理活頁簿查詢和連線，並透過 ODC 檔與他人共用查詢。 [詳細資訊](https://support.office.com/article/ad78befd-eb1c-4ea7-a55d-79d1d67cf9b3)</span><span class="sxs-lookup"><span data-stu-id="44499-p358">**Enhanced data import functionality:** Easily import and shape data from various sources. Manage workbook queries and connections with the Queries & Connection side pane, and share queries with others via ODC files. [More information](https://support.office.com/article/ad78befd-eb1c-4ea7-a55d-79d1d67cf9b3)</span></span>
-   <span data-ttu-id="44499-p359">**共用檔案中的變更**：檢視誰在共用活頁簿中進行了變更，以及將活頁簿還原到舊版。[詳細資訊](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)</span><span class="sxs-lookup"><span data-stu-id="44499-p359">**Changes in shared files**: View who has made changes in shared workbooks, and restore earlier versions. [More information](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)</span></span>
-   <span data-ttu-id="44499-2413">**具有畫筆按鈕的套索工具：** 使用套索工具筆跡支援的數位畫筆按鈕，而不造訪功能區。</span><span class="sxs-lookup"><span data-stu-id="44499-2413">**Lasso Select with a pen button:** Use supported digital pen buttons to Lasso Select ink without visiting the ribbon.</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="44499-2414">Excel：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2414">Excel: Security updates</span></span>
-   <span data-ttu-id="44499-2415">[CVE-2017-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8501)：Microsoft Office 記憶體損毀弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2415">[CVE-2017-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8501): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="44499-2416">[CVE-2017-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8502)：Microsoft Office 記憶體損毀弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2416">[CVE-2017-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8502): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="44499-2417">[CVE-2017-8631](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8631)：Microsoft Office 記憶體損毀弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2417">[CVE-2017-8631](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8631): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="44499-2418">[CVE-2017-8632](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8632)：Microsoft Office 記憶體損毀弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2418">[CVE-2017-8632](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8632): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="44499-2419">[CVE-2017-11877](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11877)：Microsoft Excel 安全性功能略過的弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2419">[CVE-2017-11877](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11877): Microsoft Excel Security Feature Bypass Vulnerability</span></span>
-   <span data-ttu-id="44499-2420">[CVE-2017-11878](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11878)：Microsoft Excel 記憶體損毀弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2420">[CVE-2017-11878](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11878): Microsoft Excel Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="44499-2421">[CVE-2017-11884](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11884)：Microsoft Office 記憶體損毀弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2421">[CVE-2017-11884](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11884): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="44499-2422">[CVE-2017-11935](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11935)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2422">[CVE-2017-11935](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11935): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2423">[CVE-2018-0796](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0796)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2423">[CVE-2018-0796](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0796): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2424">[Advisory 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021)：Microsoft Office 深度防禦更新</span><span class="sxs-lookup"><span data-stu-id="44499-2424">[Advisory 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021): Microsoft Office Defense in Depth Update</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="44499-2425">Excel：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2425">Excel: Non-security updates</span></span>
-   <span data-ttu-id="44499-2426">修正此問題：以程式設計方式建立樞紐分析表，接著以程式設計方式重新整理，會造成 Excel 當機。</span><span class="sxs-lookup"><span data-stu-id="44499-2426">Fix an issue where the programmatic creation of a PivotTable followed by a programmatic refresh causes Excel to crash.</span></span>
-   <span data-ttu-id="44499-2427">修正此問題：使用者使用巨集開啟 Office 2007 或較舊的活頁簿 (.xls 或 .xla) 時，會看到不正確的「重大失敗」錯誤訊息。</span><span class="sxs-lookup"><span data-stu-id="44499-2427">Fix an issue where the user incorrectly sees a "catastrophic failure" error message when opening an Office 2007 or older workbook (.xls or .xla) with macros.</span></span>
-   <span data-ttu-id="44499-2428">修正此問題：從命令列開啟活頁簿可能會導致儲存格中的 RTF 格式遺失。</span><span class="sxs-lookup"><span data-stu-id="44499-2428">Fix an issue where opening a workbook from the command line might result in the loss of rich text formatting in a cell.</span></span>
-   <span data-ttu-id="44499-2429">修正此問題：在檔案名稱包含方括弧時，使用者無法在受保護的檢視中關閉活頁簿。</span><span class="sxs-lookup"><span data-stu-id="44499-2429">Fix an issue where the user can't close a workbook in protected view when the file name contains square brackets.</span></span>
-   <span data-ttu-id="44499-2430">修正此問題：當使用者嘗試在現有的活頁簿中插入物件時，Excel 會在使用者按一下 [瀏覽] 時損毀。</span><span class="sxs-lookup"><span data-stu-id="44499-2430">Fix an issue where, when the user tries to insert an object in an existing workbook, Excel crashes when the user clicks Browse.</span></span>
-   <span data-ttu-id="44499-2431">修正此問題：選取 [調整圖形大小以修正文字] (在 [圖形格式] 窗格的 [文字選項]/[文字方塊] 部分中)，結果圖形不變。</span><span class="sxs-lookup"><span data-stu-id="44499-2431">Fix an issue where selecting "Resize shape to fix text" (in the Text Options/Text Box portion of the Format Shape pane) results in no change to the shape.</span></span>
-   <span data-ttu-id="44499-2432">修正此問題：在活頁簿上按兩下以開啟活頁簿時，不會載入儲存格的文字字型和格式，或兩個完全相同的活頁簿會針對一個範本開啟。</span><span class="sxs-lookup"><span data-stu-id="44499-2432">Fix an issue where, when opening a workbook by double-clicking on it, the cell text fonts and formats don't get loaded or two identical workbooks are opened for a single template.</span></span>
-   <span data-ttu-id="44499-2433">修正此問題：開啟或建立新的活頁簿時，在 Excel 啟動時所建立的第一個活頁簿不會關閉。</span><span class="sxs-lookup"><span data-stu-id="44499-2433">Fix an issue where the first workbook created when Excel starts won't close when a new workbook is opened or created.</span></span>
-   <span data-ttu-id="44499-2434">修正此問題：在拖曳或拖曳填滿時，工具提示的放置位置沒有對齊。</span><span class="sxs-lookup"><span data-stu-id="44499-2434">Fix an issue where placement of the tooltip is misaligned when dragging or drag filling.</span></span>
-   <span data-ttu-id="44499-2435">修正此問題：使用 [檔案] \> [另存新檔] 來儲存活頁簿時，包含句點的檔案名稱在檔案儲存對話方塊中會出現空白或截斷。</span><span class="sxs-lookup"><span data-stu-id="44499-2435">Fix an issue where, when saving a workbook by using File \> Save As, a file name that contains periods appears blank or truncated in the file save dialog.</span></span>
-   <span data-ttu-id="44499-p360">修正此問題：正在儲存同步備份檔案時，Office 無法寫入磁碟，但 Office 會不斷上傳檔案到 OneDrive。有了此修正程式之後，使用者現在會看到一則錯誤訊息，且 Office 不會繼續上傳。</span><span class="sxs-lookup"><span data-stu-id="44499-p360">Fix an issue where, when saving a sync-backed file, Office fails to write to disk, but Office keeps uploading the file to OneDrive. With this fix, user will now see an error message and the upload won't proceed.</span></span>
-   <span data-ttu-id="44499-2438">修正轉譯問題：由於錯誤的圖形驅動程式而出現黑色線條和標頭。</span><span class="sxs-lookup"><span data-stu-id="44499-2438">Fix an issue with rendering where black lines and headers appear due to a faulty graphics driver.</span></span>
-   <span data-ttu-id="44499-2439">修正此問題：在插入圖表後，Excel 毀損或無法儲存活頁簿。</span><span class="sxs-lookup"><span data-stu-id="44499-2439">Fix an issue where Excel crashes or is unable to save the workbook after a chart is inserted.</span></span>
-   <span data-ttu-id="44499-2440">修正此問題：分頁預覽中的分頁線位置不正確。</span><span class="sxs-lookup"><span data-stu-id="44499-2440">Fix an issue where the page break line in page break preview is incorrectly positioned.</span></span>
-   <span data-ttu-id="44499-2441">修正此問題：Excel 在開啟 XLL 檔案時損毀。</span><span class="sxs-lookup"><span data-stu-id="44499-2441">Fix an issue where Excel crashes when opening an .XLL file.</span></span>
-   <span data-ttu-id="44499-2442">修正此問題：在頁面配置檢視中新增頁首或頁尾後，其儲存格的圖樣樣式無法正確呈現。</span><span class="sxs-lookup"><span data-stu-id="44499-2442">Fix an issue where the pattern style of a cell doesn’t render correctly after adding a header or footer in Page Layout view.</span></span>
-   <span data-ttu-id="44499-2443">修正此問題：將樞紐分析表的副本貼上到另一個活頁簿可能會導致當機。</span><span class="sxs-lookup"><span data-stu-id="44499-2443">Fix an issue where pasting a copy of a PivotTable into another workbook could result in a crash.</span></span>
-   <span data-ttu-id="44499-2444">修正此問題：當選擇 [取代] 命令時，[尋找] 及 [取代] 對話方塊隨即開啟，但對話方塊的焦點位於 [尋找] 索引標籤，而不是 [取代] 索引標籤。</span><span class="sxs-lookup"><span data-stu-id="44499-2444">Fix an issue where, when you choose the Replace command and the Find and Replace dialog box opens, the focus of the dialog box is on the Find tab instead of the Replace tab.</span></span>
-   <span data-ttu-id="44499-2445">修正此問題：從比 SharePoint Server 2016 更早版本的 SharePoint Server 開啟活頁簿的 [活動] 窗格時，Excel 會當機。</span><span class="sxs-lookup"><span data-stu-id="44499-2445">Fix an issue where Excel crashes when opening the Activity pane for a workbook opened from a SharePoint server older than SharePoint Server 2016.</span></span>
-   <span data-ttu-id="44499-2446">修正此問題：當啟用一或多個 XLL 增益集時，Excel 會開啟並顯示一個空白視窗。</span><span class="sxs-lookup"><span data-stu-id="44499-2446">Fix an issue where Excel opens and displays a blank window when one or more XLL add-ins are enabled.</span></span>
-   <span data-ttu-id="44499-2447">修正此問題：在已關閉的活頁簿中使用 [表單] 按鈕之後，Excel 會當機。</span><span class="sxs-lookup"><span data-stu-id="44499-2447">Fix an issue where Excel crashes after having used the Forms button in an already closed workbook.</span></span>
-   <span data-ttu-id="44499-2448">修正此問題：使用 SheetBeforeRightClick 事件時，插入與合併儲存格相交的資料行不會展開合併的儲存格。</span><span class="sxs-lookup"><span data-stu-id="44499-2448">Fix an issue where, when using the SheetBeforeRightClick event, inserting a column that intersects merged cells doesn't expand the merged cells.</span></span>
-   <span data-ttu-id="44499-2449">修正此問題：展開或摺疊樞紐分析表時，Excel 暫時停止回應且樞紐分析表標頭移出螢幕。</span><span class="sxs-lookup"><span data-stu-id="44499-2449">Fix an issue where Excel temporarily hangs when you expand or collapse a PivotTable and the PivotTable headers move off the screen.</span></span>
-   <span data-ttu-id="44499-2450">修正此問題：從 Word 複製和貼上 Tab 分隔的文字時，會忽略索引標籤，導致文字無法被剖析成多個欄位。</span><span class="sxs-lookup"><span data-stu-id="44499-2450">Fix an issue where tabs are ignored when copying and pasting tab delimited text from Word, resulting in the text not being parsed into columns.</span></span>
-   <span data-ttu-id="44499-2451">修正此問題：開啟 [發佈為網頁] 對話方塊時，Excel 會當機。</span><span class="sxs-lookup"><span data-stu-id="44499-2451">Fix an issue where Excel crashes when opening the Publish as Web Page dialog box.</span></span>
-   <span data-ttu-id="44499-2452">修正此問題：使用來自 SQL Server Analysis Services 伺服器的資料，且 Excel 的地區設定和 SQL Server Analysis Services 伺服器的地區設定不同時，資料重新整理不成功或 Excel 當機。</span><span class="sxs-lookup"><span data-stu-id="44499-2452">Fix an issue where a data refresh doesn't succeed or Excel crashes when using data from a SQL Server Analysis Services server, and the locale of Excel and the locale of the SQL Server Analysis Services server differ.</span></span>
-   <span data-ttu-id="44499-2453">修正此問題：當嘗試儲存與 OneDrive 用戶端同步的文件變更時出現錯誤。</span><span class="sxs-lookup"><span data-stu-id="44499-2453">Fix an issue where errors appear when trying to save changes to documents synchronized with the OneDrive client.</span></span>
-   <span data-ttu-id="44499-2454">修正此問題：當「篩選」區域中有 PivotTable，其他地方並沒有任何欄位時，無法在工作表中進行任何變更。</span><span class="sxs-lookup"><span data-stu-id="44499-2454">Fix an issue where changes can't be made anywhere in a worksheet when there is a PivotTable with fields in the Filter area, but no fields anywhere else.</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="44499-2455">Outlook：功能更新</span><span class="sxs-lookup"><span data-stu-id="44499-2455">Outlook: Feature updates</span></span>
-   <span data-ttu-id="44499-2456">**協助工具的改善：** 我們讓您在使用螢幕助讀程式時，能夠容易地閱讀及編輯電子郵件中的文字、表格、清單和圖像。</span><span class="sxs-lookup"><span data-stu-id="44499-2456">**Accessibility improvements:** We've made it easier to read and edit text, tables, lists, and images in email when you're using a screen reader.</span></span>
-   <span data-ttu-id="44499-2457">**新帳戶設定：** 使用新的精靈設定新帳戶，所需的手動步驟更少。</span><span class="sxs-lookup"><span data-stu-id="44499-2457">**New account configuration:** Set up new accounts with a new wizard that requires fewer manual steps.</span></span>
-   <span data-ttu-id="44499-p361">**附加連結的對話方塊：** 在功能區使用「附加檔案」附加連結時，您可以選擇要將其新增為連結或作為附件傳送。如果您不希望每次都看到此對話方塊，請移至 [檔案] \> [選項] \> [一般]，並指定想要在 [附件選項] 下附加連結的方式。</span><span class="sxs-lookup"><span data-stu-id="44499-p361">**Attach dialog for links:** When attaching a link using Attach File on the ribbon, you can select whether to add it as a link or as an attachment. If you don’t want to see this dialog each time, go to File \> Options \> General and specify how you want links to be attached under “Attachment options.”</span></span>
-   <span data-ttu-id="44499-2460">**內部部署附件的支援：** 內部部署 SharePoint 伺服器上的檔案會在 [訊息] \> [附加檔案] 下顯示為最近使用的檔案，而內部部署商務用 OneDrive 和 SharePoint 團隊網站會顯示在 [附加檔案] \> [瀏覽網頁位置]，此外本機檔案可以上傳至內部部署商務用 OneDrive 網站。</span><span class="sxs-lookup"><span data-stu-id="44499-2460">**Support for on-premises attachments:** Files from on-premises SharePoint Server show up as recent files under Message \> Attach File, on-premises OneDrive for Business and SharePoint team sites appear under Attach File \> Browse Web Locations, and local files can be uploaded to on-premises OneDrive for Business sites.</span></span>
-   <span data-ttu-id="44499-2461">**群組的業務分類︰**  租用戶系統管理員定義的業務分類層級 (如機密)，可在建立或編輯群組時指派，且該分類會顯示在群組標題中。</span><span class="sxs-lookup"><span data-stu-id="44499-2461">**Business classifications for groups:**  A business classification level defined by the tenant admin, such as Confidential, can be assigned when creating or editing a group, and that classification appears in the group header.</span></span>
-   <span data-ttu-id="44499-p362">**來賓存取 Office 365 群組︰** 透過授予存取組織對話、檔案、行事曆邀請和群組筆記本的存取權限，與組織外部的人員協同合作。 [詳細資訊](https://support.office.com/article/bfc7a840-868f-4fd6-a390-f347bf51aff6)</span><span class="sxs-lookup"><span data-stu-id="44499-p362">**Guest access to Office 365 groups:** Collaborate with people outside the organization by granting them access to group conversations, files, calendar invitations, and the group notebook. [More information](https://support.office.com/article/bfc7a840-868f-4fd6-a390-f347bf51aff6)</span></span>
-   <span data-ttu-id="44499-p363">**可採取動作的訊息︰** 開發人員可以建立訊息，讓使用者可以從 Outlook 輕鬆採取簡單或快速的動作，而不需要切換至外部網站或個別的應用程式。[詳細資訊](https://dev.office.com/blogs/create-more-engaging-conversations-with-new-actionable-messages-updates-announced-at-microsoft-build)</span><span class="sxs-lookup"><span data-stu-id="44499-p363">**Actionable messages:** Developers can create messages to make it easy for users to take simple or quick actions right from Outlook without having to switch to an external web site or separate app. [More information](https://dev.office.com/blogs/create-more-engaging-conversations-with-new-actionable-messages-updates-announced-at-microsoft-build)</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="44499-2466">Outlook：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2466">Outlook: Security updates</span></span>
-   <span data-ttu-id="44499-2467">[CVE-2017-8571](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8571)：Microsoft Office Outlook 安全性功能略過的弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2467">[CVE-2017-8571](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8571): Microsoft Office Outlook Security Feature Bypass Vulnerability</span></span>
-   <span data-ttu-id="44499-2468">[CVE-2017-8572](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8572)：Microsoft Office Outlook 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2468">[CVE-2017-8572](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8572): Microsoft Office Outlook Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="44499-2469">[CVE-2017-8663](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8663)：Microsoft Office Outlook 記憶體損毀弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2469">[CVE-2017-8663](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8663): Microsoft Office Outlook Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="44499-2470">[CVE-2017-11774](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11774)：Microsoft Outlook 安全性功能略過的弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2470">[CVE-2017-11774](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11774): Microsoft Outlook Security Feature Bypass Vulnerability</span></span>
-   <span data-ttu-id="44499-2471">[CVE-2017-11776](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11776)：Microsoft Outlook 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2471">[CVE-2017-11776](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11776): Microsoft Outlook Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="44499-2472">[CVE-2017-11939](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11939)：Microsoft Office 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2472">[CVE-2017-11939](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11939): Microsoft Office Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="44499-2473">[CVE-2018-0791](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0791)：Microsoft Outlook 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2473">[CVE-2018-0791](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0791): Microsoft Outlook Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2474">[CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793)：Microsoft Outlook 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2474">[CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook Remote Code Execution Vulnerability</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="44499-2475">Outlook：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2475">Outlook: Non-security updates</span></span>
-   <span data-ttu-id="44499-2476">修正此問題：使用者看到郵件清單中的焦點會在刪除郵件時意外跳轉。</span><span class="sxs-lookup"><span data-stu-id="44499-2476">Fix an issue where the user sees the focus in the message list jump unexpectedly when deleting messages.</span></span>
-   <span data-ttu-id="44499-2477">修正導致使用者在與附件互動時看到驗證提示的問題</span><span class="sxs-lookup"><span data-stu-id="44499-2477">Fix an issue that causes the user to see authentication prompts when interacting with attachments</span></span>
-   <span data-ttu-id="44499-2478">修正此問題：使用深灰色佈景主題時，「原則提示」中的「深入了解」連結無法顯示。</span><span class="sxs-lookup"><span data-stu-id="44499-2478">Fix an issue where the "Learn more" link in Policy Tips isn't visible when using the Dark Gray theme.</span></span>
-   <span data-ttu-id="44499-2479">修正此問題：當使用者嘗試設定新帳戶，並且在未完成帳戶設定之前即關閉該視窗時，Outlook 會當機。</span><span class="sxs-lookup"><span data-stu-id="44499-2479">Fix an issue where Outlook crashes when the user is trying to set up a new account and they close the window without completing the account setup.</span></span>
-   <span data-ttu-id="44499-2480">修正此問題：「標記為已讀取」時，「標記為未讀取」為群組的共用收件匣中的郵件選項。</span><span class="sxs-lookup"><span data-stu-id="44499-2480">Fix an issue where Mark as Read and Mark as Unread show as options for messages in the shared inbox for a group.</span></span>
-   <span data-ttu-id="44499-2481">修正此問題：無法在 Outlook 中設定 IMAP 帳戶。</span><span class="sxs-lookup"><span data-stu-id="44499-2481">Fix an issue where you're unable to configure an IMAP account in Outlook.</span></span>
-   <span data-ttu-id="44499-2482">修正此問題：開啟 Outlook 時會間歇性當機。</span><span class="sxs-lookup"><span data-stu-id="44499-2482">Fix an issue that causes an intermittent crash when opening Outlook.</span></span>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="44499-2483">PowerPoint：功能更新</span><span class="sxs-lookup"><span data-stu-id="44499-2483">PowerPoint: Feature updates</span></span>
-   <span data-ttu-id="44499-2484">**插入線上圖片：** 用以選取影像和屬性資訊的新登陸頁面會隨著影像自動插入。</span><span class="sxs-lookup"><span data-stu-id="44499-2484">**Insert online pictures:** New landing page for selecting images and attribution information is automatically inserted with the image.</span></span>
-   <span data-ttu-id="44499-p364">**影片的隱藏式輔助字幕：** 可將隱藏式輔助字幕新增至影片，使其變得更無障礙。[詳細資訊](https://support.office.com/article/a16745e1-b3da-4428-b2a7-ff0c8b758d0b)</span><span class="sxs-lookup"><span data-stu-id="44499-p364">**Closed captions for videos:** Add closed captions to a video to make it more accessible. [More information](https://support.office.com/article/a16745e1-b3da-4428-b2a7-ff0c8b758d0b)</span></span>
-   <span data-ttu-id="44499-p365">**製作錄製的旁白︰** 當您錄製簡報時，可加入自己旁白的視訊。錄製可以包含動畫、筆跡、音訊和視訊。</span><span class="sxs-lookup"><span data-stu-id="44499-p365">**Narrate a recording:** Include video of yourself narrating when you make a recording of a presentation. Recordings can include animations, ink, audio, and video.</span></span>
-   <span data-ttu-id="44499-2489">**共用的檔案活動︰** 選擇檔案右上角的 [活動] 按鈕，以查看在商務用 OneDrive 或 SharePoint 中共用檔案的共用、編輯、重新命名或還原。</span><span class="sxs-lookup"><span data-stu-id="44499-2489">**Shared file activity:** Choose the Activity button in the upper right corner of the file to see when a file shared in OneDrive for Business or SharePoint was shared, edited, renamed, or restored.</span></span>
-   <span data-ttu-id="44499-2490">**Alt 文字建立︰** 雲端式服務會自動為簡報中的圖片產生替代文字。</span><span class="sxs-lookup"><span data-stu-id="44499-2490">**Alt text creation:** A cloud-based service automatically generates alternative text for pictures in a presentation.</span></span>
-   <span data-ttu-id="44499-p366">**安全連結：** 當使用者按一下連結時，Office 365 進階威脅防護 (ATP) 會檢查是否為惡意的連結。如果連結被視為惡意，系統就會將使用者重新導向至警告頁面而非原始的目標 URL。 [詳細資訊](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)</span><span class="sxs-lookup"><span data-stu-id="44499-p366">**Safe links:** When a user clicks on a link, Office 365 Advanced Threat Protection (ATP) inspects the link to see if it’s malicious. If the link is deemed malicious, the user is redirected to a warning page instead of the original target URL. [More information](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)</span></span>
-   <span data-ttu-id="44499-2494">**設計工具改進功能：** 針對動作取向的清單提供專業的設計構想建議。</span><span class="sxs-lookup"><span data-stu-id="44499-2494">**Designer improvements:** Recommends professional design ideas for action-oriented lists.</span></span>
-   <span data-ttu-id="44499-p367">**共用檔案中的變更**：檢視誰在共用簡報中進行了變更，以及將簡報還原到舊版。[詳細資訊](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)</span><span class="sxs-lookup"><span data-stu-id="44499-p367">**Changes in shared files:** View who has made changes in shared presentations, and restore earlier versions. [More information](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)</span></span>

### <a name="powerpoint-security-updates"></a><span data-ttu-id="44499-2497">PowerPoint：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2497">PowerPoint: Security updates</span></span>
-   <span data-ttu-id="44499-2498">[CVE-2017-8742](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8742)：PowerPoint 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2498">[CVE-2017-8742](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8742): PowerPoint Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2499">[CVE-2017-8743](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8743)：PowerPoint 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2499">[CVE-2017-8743](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8743): PowerPoint Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2500">[CVE-2017-11934](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11934)：Microsoft PowerPoint 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2500">[CVE-2017-11934](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11934): Microsoft PowerPoint Information Disclosure Vulnerability</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="44499-2501">PowerPoint：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2501">PowerPoint: Non-security updates</span></span>
-   <span data-ttu-id="44499-p368">修正此問題：正在儲存同步備份檔案時，Office 無法寫入磁碟，但 Office 會不斷上傳檔案到 OneDrive。有了此修正程式之後，使用者現在會看到一則錯誤訊息，且 Office 不會繼續上傳。</span><span class="sxs-lookup"><span data-stu-id="44499-p368">Fix an issue where, when saving a sync-backed file, Office fails to write to disk, but Office keeps uploading the file to OneDrive. With this fix, user will now see an error message and the upload won't proceed.</span></span>
-   <span data-ttu-id="44499-2504">修正此問題：在表格中復原後編輯和格式化文字會導致 PowerPoint 毀損。</span><span class="sxs-lookup"><span data-stu-id="44499-2504">Fix an issue where editing and formatting text after an undo in a table causes PowerPoint to crash.</span></span>
-   <span data-ttu-id="44499-p369">修正此問題：以 Flash Player 為基礎之 YouTube 內嵌程式碼的參考，導致開啟新視窗來播放影片。舊的內嵌程式碼現已升級為參考以 HTML5 為基礎的 YouTube 影片，以便正確地就地播放。</span><span class="sxs-lookup"><span data-stu-id="44499-p369">Fix an issue where references to Flash Player based YouTube embed codes result in a new window opening to play the video. Old embed codes are now upgraded to reference HTML5 based YouTube videos so that they correctly play in place.</span></span>
-   <span data-ttu-id="44499-2507">修正此問題：從比 SharePoint Server 2016 更早版本的 SharePoint Server 開啟簡報時，PowerPoint 會當機。</span><span class="sxs-lookup"><span data-stu-id="44499-2507">Fix an issue where PowerPoint crashes when opening a presentation from a SharePoint server older than SharePoint Server 2016.</span></span>
-   <span data-ttu-id="44499-2508">修正此問題：已連結字型的使用者定義字元 (EUDC) 無法顯示。</span><span class="sxs-lookup"><span data-stu-id="44499-2508">Fix an issue where end-user defined characters (EUDCs) that are linked to fonts fail to display.</span></span>

### <a name="project-non-security-updates"></a><span data-ttu-id="44499-2509">Project：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2509">Project: Non-security updates</span></span>
-   <span data-ttu-id="44499-2510">修正此問題：專案層級自訂欄位的資料可能在儲存時遺失。</span><span class="sxs-lookup"><span data-stu-id="44499-2510">Fix an issue an issue where project level custom field data can get lost on save.</span></span>
-   <span data-ttu-id="44499-2511">修正此問題：儲存失敗會導致檔案損毀，並造成專案在開啟時當機。</span><span class="sxs-lookup"><span data-stu-id="44499-2511">Fix an issue where a failed save can corrupt a file and cause Project to crash on open.</span></span>
-   <span data-ttu-id="44499-2512">修正此問題：開啟專案計劃可能會導致當機。</span><span class="sxs-lookup"><span data-stu-id="44499-2512">Fix an issue where opening a project plan could lead to a crash.</span></span>
-   <span data-ttu-id="44499-2513">修正此問題：從 Project Online 開啟某些檔案會造成 Project Online 當機。</span><span class="sxs-lookup"><span data-stu-id="44499-2513">Fix an issue where opening certain files from Project Online causes Project to crash.</span></span>
-   <span data-ttu-id="44499-2514">修正此問題：設定剩餘工時時，可能會錯誤清除「實際開始時間」。</span><span class="sxs-lookup"><span data-stu-id="44499-2514">Fix an issue where Actual Start may be wrongly cleared when you set remaining work.</span></span>
-   <span data-ttu-id="44499-2515">修正此問題：「指派實際開始時間」顯示的資料，可能會與透過 Project Web App 中狀態的資源所回報的資料不同。</span><span class="sxs-lookup"><span data-stu-id="44499-2515">Fix an issue where Assignment Actual Start Date may show different data than was reported by the resource through statusing in Project Web App.</span></span>
-   <span data-ttu-id="44499-2516">修正此問題：若變更工作的完成日期，則實際工時可能會重新排程。</span><span class="sxs-lookup"><span data-stu-id="44499-2516">Fix an issue where actual work may be rescheduled if the task's finish date is changed.</span></span>
-   <span data-ttu-id="44499-2517">修正此問題：如果您複製並貼上成本欄位，由於進位的問題，貼上的值可能與複製的值不完全符合。</span><span class="sxs-lookup"><span data-stu-id="44499-2517">Fix an issue where if you copy and paste cost fields, the pasted values might not exactly match the copied values due to a rounding issue.</span></span>
-   <span data-ttu-id="44499-2518">修正此問題：從一個比較基準儲存到另一個基準時，不會複製預算資源的時段資料。</span><span class="sxs-lookup"><span data-stu-id="44499-2518">Fix an issue where timephased data for Budget resources isn't copied when you save from one baseline into another one.</span></span>
-   <span data-ttu-id="44499-2519">修正此問題：[狀態] 欄位對摘要任務的計算不一定正確。</span><span class="sxs-lookup"><span data-stu-id="44499-2519">Fix an issue where the status field doesn't always calculate correctly for summary tasks.</span></span>
-   <span data-ttu-id="44499-2520">修正此問題：當實際工時取代本機資源並啟用受保護的工時，實際工時會錯誤地轉移到企業資源。</span><span class="sxs-lookup"><span data-stu-id="44499-2520">Fix an issue where actual work wrongly gets transferred to an enterprise resource when it replaces a local resource and protected work is enabled.</span></span>
-   <span data-ttu-id="44499-2521">修正此問題：如果您有一個資料表，其中第一欄是 [工作名稱]，該欄已被鎖定，而按一下工作會導致專案損毀。</span><span class="sxs-lookup"><span data-stu-id="44499-2521">Fix an issue where Project crashes if you have a table where the first column is Task Name, the column is locked, and you click on a task.</span></span>
-   <span data-ttu-id="44499-2522">修正此問題：您可以透過 [任務分派狀況] 檢視，將相同的資源多次指定至相同的工作。</span><span class="sxs-lookup"><span data-stu-id="44499-2522">Fix an issue where you can assign the same resource multiple times to the same task through the Task Usage view.</span></span>
-   <span data-ttu-id="44499-2523">修正此問題：開啟 XML 檔案時，數字自訂欄位的值可能會遺失。</span><span class="sxs-lookup"><span data-stu-id="44499-2523">Fix an issue where values in the number custom fields may be lost when opening XML files.</span></span>
-   <span data-ttu-id="44499-2524">修正此問題：最高層級任務縮排無法從 Project 正確同步到 SharePoint 工作清單。</span><span class="sxs-lookup"><span data-stu-id="44499-2524">Fix an issue where top-level task indentation doesn't sync properly from Project to a SharePoint tasks list.</span></span>
-   <span data-ttu-id="44499-2525">修正此問題：如果您從 Excel 活頁簿匯入任務、資源或工作分派資訊，[工時] 欄位中的值可能會被忽略。</span><span class="sxs-lookup"><span data-stu-id="44499-2525">Fix an issue where if you import task, resource, or assignment information from an Excel workbook, the values in the work field may be ignored.</span></span>
-   <span data-ttu-id="44499-2526">修正此問題：分時段的基準值不符合 (您將專案儲存為 XML 檔案格式時的) 初始值。</span><span class="sxs-lookup"><span data-stu-id="44499-2526">Fix an issue where timephased Baseline values don't match the initial values when you save a project to the XML file format.</span></span>
-   <span data-ttu-id="44499-2527">修正此問題：由於 Project 用戶端認為專案已簽出，因此不會開啟專案，但實際上並未簽出。</span><span class="sxs-lookup"><span data-stu-id="44499-2527">Fix an issue where the Project client won't open a project since it thinks the project is checked out when it really isn't.</span></span>
-   <span data-ttu-id="44499-2528">修正此問題：從高延遲的檔案伺服器開啟 Project 檔案，現在速度已加快。</span><span class="sxs-lookup"><span data-stu-id="44499-2528">Fix an issue so that opening Project files from a file server with high latency open faster.</span></span>

### <a name="skype-for-business-security-updates"></a><span data-ttu-id="44499-2529">商務用 Skype：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2529">Skype for Business: Security updates</span></span>
-   <span data-ttu-id="44499-2530">[CVE-2017-8676](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8676)：Windows GDI + 資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2530">[CVE-2017-8676](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8676): Windows GDI+ Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="44499-2531">[CVE-2017-8695](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8695)：圖形元件資訊洩漏弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2531">[CVE-2017-8695](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8695): Graphics Component Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="44499-2532">[CVE-2017-8696](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8696)：Microsoft 圖形元件遠端程式碼執行</span><span class="sxs-lookup"><span data-stu-id="44499-2532">[CVE-2017-8696](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8696): Microsoft Graphics Component Remote Code Execution</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="44499-2533">商務用 Skype：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2533">Skype for Business: Non-security updates</span></span>
-   <span data-ttu-id="44499-2534">新增對話方塊，說明特定連接埠遭封鎖或 IP 不被允許時，使用者為何無法加入會議。</span><span class="sxs-lookup"><span data-stu-id="44499-2534">Add dialog explaining why a user is unable to join a meeting when certain ports are blocked or IPs are not allowed.</span></span>
-   <span data-ttu-id="44499-2535">修正此問題：當您按一下 IM 交談分頁時，常設聊天室中的未讀訊息會標示成已讀。</span><span class="sxs-lookup"><span data-stu-id="44499-2535">Fix an issue where unread messages in persistent chat rooms are marked as read when you click IM conversation tabs.</span></span>
-   <span data-ttu-id="44499-2536">修正此問題：傳入的 IM 快顯通知會發生幾秒延遲。</span><span class="sxs-lookup"><span data-stu-id="44499-2536">Fix an issue where incoming IM toasts experience a several second delay.</span></span>
-   <span data-ttu-id="44499-2537">修正此問題：停用 Exchange 同步處理時，AD 連絡人會顯示為電話號碼，而不是連絡人名稱。</span><span class="sxs-lookup"><span data-stu-id="44499-2537">Fix an issue where an AD contact is displayed as a phone number instead of contact name when sync with Exchange is disabled.</span></span>
-   <span data-ttu-id="44499-2538">修正此問題：停用同盟且會議召集人未明確封鎖匿名加入時，匿名加入使用者會被封鎖而無法加入。</span><span class="sxs-lookup"><span data-stu-id="44499-2538">Fix an issue where anonymous join users are blocked from joining when federation is disabled and anonymous join is not explicitly blocked by meeting organizer.</span></span>
-   <span data-ttu-id="44499-2539">修正此問題：超過人數限制的會議中，對會議召集人顯示的受邀者數目不正確。</span><span class="sxs-lookup"><span data-stu-id="44499-2539">Fix an issue where the number of invitees is incorrectly displayed to meeting organizer for meetings that exceed the limit.</span></span>
-   <span data-ttu-id="44499-2540">修正此問題：內送 PSTN 通話的快顯通知中不顯示電話號碼。</span><span class="sxs-lookup"><span data-stu-id="44499-2540">Fix an issue where phone number is not displayed in toast on inbound PSTN calls.</span></span>
-   <span data-ttu-id="44499-2541">修正此問題：重新命名連絡人清單群組時，使用 Delete 鍵會刪除整個群組。</span><span class="sxs-lookup"><span data-stu-id="44499-2541">Fix an issue where, when using the Delete key while renaming a contact list group, the entire group is deleted.</span></span>
-   <span data-ttu-id="44499-2542">修正此問題：共用停止之前，會關閉 IM 交談中的共用通知。</span><span class="sxs-lookup"><span data-stu-id="44499-2542">Fix an issue where the sharing notification in an IM conversation is dismissed before sharing stops.</span></span>
-   <span data-ttu-id="44499-2543">修正此問題：某些非英文語言的登入畫面是空白的。</span><span class="sxs-lookup"><span data-stu-id="44499-2543">Fix an issue where the sign-in screen is blank for some non-English languages.</span></span>
-   <span data-ttu-id="44499-2544">修正此問題：在聊天和聊天歷程記錄中的非英文字元是亂碼。</span><span class="sxs-lookup"><span data-stu-id="44499-2544">Fix an issue where non-English characters in chat and chat history are garbled.</span></span>
-   <span data-ttu-id="44499-2545">若使用者的名稱未知，則會顯示由組織的自動語音應答所處理的來電者電話號碼。</span><span class="sxs-lookup"><span data-stu-id="44499-2545">Display the caller's phone number for an incoming call handled by the Organizational Auto Attendant if the user's name isn't known.</span></span>
-   <span data-ttu-id="44499-2546">新增 Inband 設定，可選擇性地限制「這些人不需要在大廳中等候」中的「任何人 (沒有限制)」。</span><span class="sxs-lookup"><span data-stu-id="44499-2546">Add an inband setting allowing restriction of "Anyone (no restrictions)"as an option for "These people don't have to wait in the lobby."</span></span>
-   <span data-ttu-id="44499-2547">新增在 VDIv2 中 P2P 視訊呼叫己方視訊的開/關功能。</span><span class="sxs-lookup"><span data-stu-id="44499-2547">Add ability to turn on or off self-video for P2P video calls in VDIv2.</span></span>
-   <span data-ttu-id="44499-2548">修正此問題：呼叫下拉功能表中連絡人會顯示重複的號碼。</span><span class="sxs-lookup"><span data-stu-id="44499-2548">Fix an issue where duplicate numbers display for contacts in the call drop-down menu.</span></span>
-   <span data-ttu-id="44499-2549">修正此問題：在商務用 Skype 和商務用 Skype 基本版之間移動的使用者委派會遭到移除。</span><span class="sxs-lookup"><span data-stu-id="44499-2549">Fix an issue where delegates are removed for users who move between Skype for Business and Skype for Business Basic.</span></span>
-   <span data-ttu-id="44499-2550">修正此問題：使用「啟用顯示為離線」和「自訂狀態 URL」用戶端原則時，會看不到 [顯示為離線]。</span><span class="sxs-lookup"><span data-stu-id="44499-2550">Fix an issue where Appear Offline is not visible when using the Enable Appear Offline and Custom State URL client policies.</span></span>
-   <span data-ttu-id="44499-2551">加寬 [加入會議] 按鈕，以修正某些當地語系化語言的截斷問題。</span><span class="sxs-lookup"><span data-stu-id="44499-2551">Widen the Meeting Join button to fix truncation of some localized languages.</span></span>
-   <span data-ttu-id="44499-2552">更加凸顯高重要性的訊息在聊天中的重要性。</span><span class="sxs-lookup"><span data-stu-id="44499-2552">Increase the prominence of High Importance messages in chat.</span></span>
-   <span data-ttu-id="44499-2553">在允許的檔案傳輸封鎖清單中新增 Office 和商務用 Skype 副檔名類型。</span><span class="sxs-lookup"><span data-stu-id="44499-2553">Add Office and Skype for Business file extension types to allowable file transfer blocklists.</span></span>
-   <span data-ttu-id="44499-2554">在設為非英文的 Outlook 會議邀請中，修正會議頁尾文字的當地語系化。</span><span class="sxs-lookup"><span data-stu-id="44499-2554">Localization corrections in Outlook meeting invitations for meeting footer text set in non-English.</span></span>
-   <span data-ttu-id="44499-2555">修正此問題：在多個使用者的情況下，對話中的傳送者名稱可能會切換。</span><span class="sxs-lookup"><span data-stu-id="44499-2555">Fix an issue where sender names can be switched in conversations of multiple users.</span></span>
-   <span data-ttu-id="44499-2556">修正此問題：在成功加入會議前，空白的對話視窗都不會出現。</span><span class="sxs-lookup"><span data-stu-id="44499-2556">Fix an issue where the blank conversation window fails to appear until a meeting is joined successfully.</span></span>
-   <span data-ttu-id="44499-2557">修正此問題：若職稱欄位空白，則搜尋結果中連絡人卡片上的部門欄位資訊也會空白。</span><span class="sxs-lookup"><span data-stu-id="44499-2557">Fix an issue where the department field information in a contact card is empty in search results if the title field is empty.</span></span>
-   <span data-ttu-id="44499-2558">修正此問題：從內部部署移轉到線上的使用者，會因為防火牆規則而造成登入失敗。</span><span class="sxs-lookup"><span data-stu-id="44499-2558">Fix sign-in failures for users migrated from on-premises to online due to firewall rules.</span></span>
-   <span data-ttu-id="44499-2559">新增新的 DWORD 登錄機碼來修正此問題：當使用者從執行 LyncAutoD 的外部網路登入用戶端，用戶端會將 OAuthUsed 登錄機碼重設為 False。</span><span class="sxs-lookup"><span data-stu-id="44499-2559">Add a new DWORD registry key to fix an issue where, when a user signs into the client on an external network performing LyncAutoD, the client resets the OAuthUsed registry key to false.</span></span> <span data-ttu-id="44499-2560">若要修正此問題，請將 HKEY\_CURRENT\_USER\\Software\\Microsoft\\Office\\16.0\\Lync\\\<SipID\>下的 EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket 值設定為 1。</span><span class="sxs-lookup"><span data-stu-id="44499-2560">To fix the issue, set the value to 1 for EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket under HKEY\_CURRENT\_USER\\Software\\Microsoft\\Office\\16.0\\Lync\\\<SipID\>.</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="44499-2561">Visio：功能更新</span><span class="sxs-lookup"><span data-stu-id="44499-2561">Visio: Feature updates</span></span>
-   <span data-ttu-id="44499-p371">**從 Excel 資料製作圖表︰** 使用新的「資料視覺化工具」範本，從 Excel 資料自動建立「基本流程圖」或「交互功能流程圖」。 [詳細資訊](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span><span class="sxs-lookup"><span data-stu-id="44499-p371">**Make diagrams from Excel data:** Automatically create a Basic Flowchart or a Cross-Functional Flowchart from Excel data by using new Data Visualizer templates. [More information](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span></span>
-   <span data-ttu-id="44499-p372">**安全連結：** 當使用者按一下連結時，Office 365 進階威脅防護 (ATP) 會檢查是否為惡意的連結。如果連結被視為惡意，系統就會將使用者重新導向至警告頁面而非原始的目標 URL。 [詳細資訊](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)</span><span class="sxs-lookup"><span data-stu-id="44499-p372">**Safe links:** When a user clicks on a link, Office 365 Advanced Threat Protection (ATP) inspects the link to see if it’s malicious. If the link is deemed malicious, the user is redirected to a warning page instead of the original target URL. [More information](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)</span></span>

### <a name="visio-non-security-updates"></a><span data-ttu-id="44499-2567">Visio：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2567">Visio: Non-security updates</span></span>
-   <span data-ttu-id="44499-2568">修正此問題：在檔案圖示或檔案名稱上按兩下以開啟 Visio 檔時，COM 增益集沒有收到文件開啟的事件。</span><span class="sxs-lookup"><span data-stu-id="44499-2568">Fix an issue where COM add-ins don't receive document opened events when a Visio file is opened by a double-click on a file icon or file name.</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="44499-2569">Word：功能更新</span><span class="sxs-lookup"><span data-stu-id="44499-2569">Word: Feature updates</span></span>
-   <span data-ttu-id="44499-2570">**插入線上圖片：** 用以選取影像和屬性資訊的新登陸頁面會隨著影像自動插入。</span><span class="sxs-lookup"><span data-stu-id="44499-2570">**Insert online pictures:** New landing page for selecting images and attribution information is automatically inserted with the image.</span></span>
-   <span data-ttu-id="44499-2571">**Alt 文字建立︰** 雲端式服務會自動為文件中的圖片產生替代文字 (Alt 文字)。</span><span class="sxs-lookup"><span data-stu-id="44499-2571">**Alt text creation:** A cloud-based service automatically generates alternative text (alt text) for pictures in a document.</span></span>
-   <span data-ttu-id="44499-2572">**共用的檔案活動︰** 選擇檔案右上角的 [活動] 按鈕，以查看在商務用 OneDrive 或 SharePoint 中共用檔案的共用、編輯、重新命名或還原。</span><span class="sxs-lookup"><span data-stu-id="44499-2572">**Shared file activity:** Choose the Activity button in the upper right corner of the file to see when a file shared in OneDrive for Business or SharePoint was shared, edited, renamed, or restored.</span></span>
-   <span data-ttu-id="44499-p373">**安全連結：** 當使用者按一下連結時，Office 365 進階威脅防護 (ATP) 會檢查是否為惡意的連結。如果連結被視為惡意，系統就會將使用者重新導向至警告頁面而非原始的目標 URL。 [詳細資訊](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)</span><span class="sxs-lookup"><span data-stu-id="44499-p373">**Safe links:** When a user clicks on a link, Office 365 Advanced Threat Protection (ATP) inspects the link to see if it’s malicious. If the link is deemed malicious, the user is redirected to a warning page instead of the original target URL. [More information](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)</span></span>
-   <span data-ttu-id="44499-p374">**共用檔案中的變更**：檢視誰在共用文件中進行了變更，以及將文件還原到舊版。[詳細資訊](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)</span><span class="sxs-lookup"><span data-stu-id="44499-p374">**Changes in shared files:**  View who has made changes in shared documents, and restore earlier versions. [More information](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)</span></span>

### <a name="word-security-updates"></a><span data-ttu-id="44499-2578">Word：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2578">Word: Security updates</span></span>
-   <span data-ttu-id="44499-2579">[CVE-2017-11826](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11826)：Microsoft Office 記憶體損毀弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2579">[CVE-2017-11826](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11826): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="44499-2580">[CVE-2018-0792](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0792)：Microsoft Word 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2580">[CVE-2018-0792](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0792): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2581">[CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793)：Microsoft Outlook 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2581">[CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2582">[CVE-2018-0794](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0794)：Microsoft Word 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2582">[CVE-2018-0794](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0794): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2583">[CVE-2018-0798](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0798)：Microsoft Office 記憶體損毀弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2583">[CVE-2018-0798](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0798): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="44499-2584">[CVE-2018-0801](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0801)：Microsoft Office 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2584">[CVE-2018-0801](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0801): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2585">[CVE-2018-0802](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0802)：Microsoft Office 記憶體損毀弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2585">[CVE-2018-0802](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0802): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="44499-2586">[CVE-2018-0804](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0804)：Microsoft Word 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2586">[CVE-2018-0804](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0804): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2587">[CVE-2018-0805](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0805)：Microsoft Word 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2587">[CVE-2018-0805](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0805): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2588">[CVE-2018-0806](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0806)：Microsoft Word 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2588">[CVE-2018-0806](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0806): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2589">[CVE-2018-0807](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0807)：Microsoft Word 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2589">[CVE-2018-0807](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0807): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2590">[CVE-2018-0812](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0812)：Microsoft Word 記憶體損毀弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2590">[CVE-2018-0812](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0812): Microsoft Word Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="44499-2591">[Advisory 170020](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170020)：Microsoft Office 深度防禦更新</span><span class="sxs-lookup"><span data-stu-id="44499-2591">[Advisory 170020](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170020): Microsoft Office Defense in Depth Update</span></span>
-   <span data-ttu-id="44499-2592">[Advisory 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021)：Microsoft Office 深度防禦更新</span><span class="sxs-lookup"><span data-stu-id="44499-2592">[Advisory 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021): Microsoft Office Defense in Depth Update</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="44499-2593">Word：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2593">Word: Non-security updates</span></span>
-   <span data-ttu-id="44499-2594">修正此問題：當使用者嘗試對商務用 OneDrive 上的現有文件執行 [另存新檔] 時，Word 會當機，並取消儲存作業或嘗試合併現有變更。</span><span class="sxs-lookup"><span data-stu-id="44499-2594">Fix an issue where Word crashes when a user tries to do a Save As to an existing document on OneDrive for Business and then cancels the save or tries to merge existing changes.</span></span>
-   <span data-ttu-id="44499-p375">修正此問題：正在儲存同步備份檔案時，Office 無法寫入磁碟，但 Office 會不斷上傳檔案到 OneDrive。有了此修正程式之後，使用者現在會看到一則錯誤訊息，且 Office 不會繼續上傳。</span><span class="sxs-lookup"><span data-stu-id="44499-p375">Fix an issue where, when saving a sync-backed file, Office fails to write to disk, but Office keeps uploading the file to OneDrive. With this fix, user will now see an error message and the upload won't proceed.</span></span>
-   <span data-ttu-id="44499-2597">修正此問題：如果使用者在開啟 Word 後立刻瀏覽至 [插入] 索引標籤，Word 可能會停止回應。</span><span class="sxs-lookup"><span data-stu-id="44499-2597">Fix an issue where Word can hang if the user navigates to the Insert tab shortly after opening Word.</span></span>
-   <span data-ttu-id="44499-2598">修正此問題：按一下邊界之後，輸入字元時，字元會顯示在畫面左上角。</span><span class="sxs-lookup"><span data-stu-id="44499-2598">Fix an issue where, after clicking the margin, characters are displayed in the upper left of the screen when entering characters.</span></span>
-   <span data-ttu-id="44499-2599">修正此問題：從比 SharePoint Server 2016 更早版本的 SharePoint Server 開啟文件的 [活動] 窗格時，Word 會當機。</span><span class="sxs-lookup"><span data-stu-id="44499-2599">Fix an issue where Word crashes when opening the Activity pane for a document opened from a SharePoint server older than SharePoint Server 2016.</span></span>
-   <span data-ttu-id="44499-2600">修正此問題：載入 Grammarly 增益集時 Word 會意外關閉。</span><span class="sxs-lookup"><span data-stu-id="44499-2600">Fix an issue where Word closes unexpectedly while loading the Grammarly add-in.</span></span>
-   <span data-ttu-id="44499-2601">修正此問題：在某些情況下，嘗試復原雲端型檔案時 Word 會損毀。</span><span class="sxs-lookup"><span data-stu-id="44499-2601">Fix an issue where, under certain conditions, Word crashes while trying to recover cloud-based files.</span></span>
-   <span data-ttu-id="44499-2602">修正此問題：無法旋轉繪圖畫布中圖形。</span><span class="sxs-lookup"><span data-stu-id="44499-2602">Fix an issue where shapes within drawing canvas can't be rotated.</span></span>
-   <span data-ttu-id="44499-2603">修正此問題：當輸入韓文時，母音和元音會不正確地分開。</span><span class="sxs-lookup"><span data-stu-id="44499-2603">Fix an issue where, when typing in Korean, consonants and vowels are incorrectly separated.</span></span>
-   <span data-ttu-id="44499-2604">將文件儲存為 PDF 格式 (儲存文件為版本 1.7 PDF)。</span><span class="sxs-lookup"><span data-stu-id="44499-2604">Saving a document as a PDF saves the document as a version 1.7 PDF.</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="44499-2605">Office 套件：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2605">Office suite: Security updates</span></span>
-   <span data-ttu-id="44499-2606">[CVE-2017-8570](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8570)：Microsoft Office 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2606">[CVE-2017-8570](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8570): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2607">[CVE-2017-8630](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8630)：Microsoft Office 記憶體損毀弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2607">[CVE-2017-8630](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8630): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="44499-2608">[CVE-2017-8744](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8744)：Microsoft Office 記憶體損毀弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2608">[CVE-2017-8744](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8744): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="44499-2609">[CVE-2017-11825](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11825)：Microsoft Office 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2609">[CVE-2017-11825](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11825): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2610">[CVE-2017-11882](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11882)：Microsoft Office 記憶體損毀弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2610">[CVE-2017-11882](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11882): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="44499-2611">[CVE-2018-0795](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0795)：Microsoft Office 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2611">[CVE-2018-0795](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0795): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2612">[Advisory 180003](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180003)：Microsoft Office 深度防禦更新</span><span class="sxs-lookup"><span data-stu-id="44499-2612">[Advisory 180003](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180003): Microsoft Office Defense in Depth Update</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="44499-2613">Office 套件：非安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2613">Office suite: Non-security updates</span></span>
-   <span data-ttu-id="44499-2614">為 Office 365 德國方案的網域使用者新增單一登入 (SSO) 的支援，該方案的身分識別與內部部署的 Active Directory 同盟。</span><span class="sxs-lookup"><span data-stu-id="44499-2614">Add support for single sign-on (SSO) for domain users for Office 365 Germany plans where the identity is federated with an on-premises Active Directory.</span></span>
-   <span data-ttu-id="44499-2615">新增功能以避免未成年人獲取和啟動來自 Office 市集的 Office 增益集。</span><span class="sxs-lookup"><span data-stu-id="44499-2615">Add functionality to prevent minors from acquiring and activating Office Add-ins that come from the Office Store.</span></span>
-   <span data-ttu-id="44499-2616">修正在動態 DPI 環境下的 Office 增益集中縮放與調整大小的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-2616">Fix an issue with zooming and scaling in Office Add-ins under dynamic DPI environment.</span></span>
-   <span data-ttu-id="44499-2617">修正此問題：即使目前已安裝 Office 365 ProPlus，Office 設定服務提供者 (CSP) 的 CurrentStatus 節點仍會傳回空字串。</span><span class="sxs-lookup"><span data-stu-id="44499-2617">Fix an issue where the CurrentStatus node of the Office configuration service provider (CSP) returns an empty string even if Office 365 ProPlus is currently installed.</span></span>
-   <span data-ttu-id="44499-2618">修正此問題：因為同一部電腦上所有的 Office 應用程式版本會共用 .box 檔案，而導致 .box 檔案格式變更；該問題會影響同一部電腦上所安裝舊版 Office 的功能。</span><span class="sxs-lookup"><span data-stu-id="44499-2618">Fix an issue that causes .box file format changes, which impacts functionality of older versions of Office installed on the same computer, because .box files are shared across all versions of an Office app on the same computer.</span></span>
-   <span data-ttu-id="44499-2619">修正此問題：在使用共用電腦啟用的某些情況下，出現一則錯誤訊息，表示應用程式發生錯誤，以致無法正常運作並詢問使用者是否要執行修復。</span><span class="sxs-lookup"><span data-stu-id="44499-2619">Fix an issue where, under certain circumstances when using shared computer activation, an error message appears saying that the app has run into an error that is preventing it from working correctly and asking if the user wants to run a repair.</span></span>
-   <span data-ttu-id="44499-2620">修正此問題：線上修復進度不會向使用者顯示。</span><span class="sxs-lookup"><span data-stu-id="44499-2620">Fix an issue where Online Repair progress isn't shown to the user.</span></span>
-   <span data-ttu-id="44499-2621">修正此問題：Office 檔案屬性未顯示在 [檔案總管] 中。</span><span class="sxs-lookup"><span data-stu-id="44499-2621">Fix an issue where Office file properties aren't displayed in File Explorer.</span></span>
-   <span data-ttu-id="44499-2622">修正此問題：開啟第二份文件時，Office 增益集按鈕會從功能區消失。</span><span class="sxs-lookup"><span data-stu-id="44499-2622">Fix an issue where Office add-in buttons disappear from the ribbon when there is a second document opened.</span></span>
-   <span data-ttu-id="44499-2623">修正此問題：無法開啟某些名稱具有雙位元組字元的 VBA 模組。</span><span class="sxs-lookup"><span data-stu-id="44499-2623">Fix an issue where some VBA modules which have names with double-byte characters can't be opened.</span></span>
-   <span data-ttu-id="44499-2624">修正此問題：「新增功能」對話方塊無法顯示。</span><span class="sxs-lookup"><span data-stu-id="44499-2624">Fix an issue that prevents the What's New dialog from appearing.</span></span>
-   <span data-ttu-id="44499-2625">修正此問題：按一下 [繪圖] 索引標籤會造成部分使用者的應用程式損毀。</span><span class="sxs-lookup"><span data-stu-id="44499-2625">Fix an issue where clicking on the Draw tab causes the application to crash for some users.</span></span>
-   <span data-ttu-id="44499-2626">修正此問題：在其上有工具提示的「通用控制項」停留時，會造成應用程式損毀。</span><span class="sxs-lookup"><span data-stu-id="44499-2626">Fix an issue where hovering over a Common Control that has a tooltip on it causes the application to crash.</span></span>
-   <span data-ttu-id="44499-2627">修正此問題：使用「通用控制項」時，出現授權錯誤訊息。</span><span class="sxs-lookup"><span data-stu-id="44499-2627">Fix an issue where a licensing error message appears when using Common Controls.</span></span>
-   <span data-ttu-id="44499-2628">修正此問題：某些程式檔案簽章的方式發生問題，導致防毒程式標幟這些檔案，以及在 Windows 資訊保護 (WIP) 底下保護或存取資料的問題。</span><span class="sxs-lookup"><span data-stu-id="44499-2628">Fix an issue with how some program files are signed, causing anti-virus programs to flag those files as well as problems protecting or accessing data under Windows Information Protection (WIP).</span></span>
-   <span data-ttu-id="44499-2629">新增 support.to 可允許使用者在 64 位元版本的 Office 開啟含有 mscomctl.ocx 控制項的巨集檔案。</span><span class="sxs-lookup"><span data-stu-id="44499-2629">Add support.to allow users working in 64-bit versions of Office to open macro files that contain mscomctl.ocx controls.</span></span>
-   <span data-ttu-id="44499-2630">改善在 mscomctl.ocx 中使用之控制項的協助工具。</span><span class="sxs-lookup"><span data-stu-id="44499-2630">Improve accessibility of controls used in mscomctl.ocx.</span></span>
-   <span data-ttu-id="44499-2631">修正此問題：Ribbon 或快速存取工具列自訂對話方塊中缺少指令。</span><span class="sxs-lookup"><span data-stu-id="44499-2631">Fix an issue where commands are missing from the Ribbon or the Quick Access Toolbar customization dialogs.</span></span>



## <a name="version-1705-january-9"></a><span data-ttu-id="44499-2632">版本 1705：1 月 9 日</span><span class="sxs-lookup"><span data-stu-id="44499-2632">Version 1705: January 9</span></span>
<span data-ttu-id="44499-2633">*版本 1705 (組建 8201.2217)*</span><span class="sxs-lookup"><span data-stu-id="44499-2633">*Version 1705 (Build 8201.2217)*</span></span>

<span data-ttu-id="44499-2634">*這是自從 2017 年 9 月以來提供的順延通道版本。它會繼續受到支援並接收安全性更新，直到 2018 年 7 月為止。不過，目前已提供新的半年通道版本 — 1708 版 (組建 8431.2153) — 其中包含了新功能、安全性更新和非安全性更新。*</span><span class="sxs-lookup"><span data-stu-id="44499-2634">*This is the Deferred Channel release that's been available since September 2017. It will continue to be supported and receive security updates until July 2018. But, a new Semi-Annual Channel release is now available — Version 1708 (Build 8431.2153) — which contains new features, security updates, and non-security updates.*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="44499-2635">Excel：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2635">Excel: Security updates</span></span>
-   <span data-ttu-id="44499-2636">[CVE-2018-0796](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0796)：Microsoft Excel 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2636">[CVE-2018-0796](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0796): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2637">[Advisory 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021)：Microsoft Office 深度防禦更新</span><span class="sxs-lookup"><span data-stu-id="44499-2637">[Advisory 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021): Microsoft Office Defense in Depth Update</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="44499-2638">Outlook：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2638">Outlook: Security updates</span></span>
-   <span data-ttu-id="44499-2639">[CVE-2018-0791](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0791)：Microsoft Outlook 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2639">[CVE-2018-0791](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0791): Microsoft Outlook Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2640">[CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793)：Microsoft Outlook 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2640">[CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook Remote Code Execution Vulnerability</span></span>

### <a name="word-security-updates"></a><span data-ttu-id="44499-2641">Word：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2641">Word: Security updates</span></span>
-   <span data-ttu-id="44499-2642">[CVE-2018-0792](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0792)：Microsoft Word 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2642">[CVE-2018-0792](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0792): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2643">[CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793)：Microsoft Outlook 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2643">[CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2644">[CVE-2018-0794](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0794)：Microsoft Word 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2644">[CVE-2018-0794](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0794): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2645">[CVE-2018-0798](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0798)：Microsoft Office 記憶體損毀弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2645">[CVE-2018-0798](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0798): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="44499-2646">[CVE-2018-0801](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0801)：Microsoft Office 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2646">[CVE-2018-0801](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0801): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2647">[CVE-2018-0802](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0802)：Microsoft Office 記憶體損毀弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2647">[CVE-2018-0802](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0802): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="44499-2648">[CVE-2018-0804](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0804)：Microsoft Word 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2648">[CVE-2018-0804](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0804): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2649">[CVE-2018-0805](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0805)：Microsoft Word 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2649">[CVE-2018-0805](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0805): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2650">[CVE-2018-0806](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0806)：Microsoft Word 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2650">[CVE-2018-0806](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0806): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2651">[CVE-2018-0807](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0807)：Microsoft Word 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2651">[CVE-2018-0807](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0807): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2652">[CVE-2018-0812](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0812)：Microsoft Word 記憶體損毀弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2652">[CVE-2018-0812](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0812): Microsoft Word Memory Corruption Vulnerability</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="44499-2653">Office 套件：安全性更新</span><span class="sxs-lookup"><span data-stu-id="44499-2653">Office suite: Security updates</span></span>
-   <span data-ttu-id="44499-2654">[CVE-2018-0795](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0795)：Microsoft Office 遠端程式碼執行弱點</span><span class="sxs-lookup"><span data-stu-id="44499-2654">[CVE-2018-0795](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0795): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="44499-2655">[Advisory 180003](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180003)：Microsoft Office 深度防禦更新</span><span class="sxs-lookup"><span data-stu-id="44499-2655">[Advisory 180003](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180003): Microsoft Office Defense in Depth Update</span></span>


> [!NOTE]
> <span data-ttu-id="44499-2656">如果您需要關於使用 Office 的問題協助，建議您將問題張貼在 [Microsoft Answers 論壇](https://answers.microsoft.com/)或[技術社群](https://techcommunity.microsoft.com/)，或連絡[技術支援](https://support.microsoft.com/contactus)。</span><span class="sxs-lookup"><span data-stu-id="44499-2656">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>