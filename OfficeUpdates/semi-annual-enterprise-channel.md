---
title: 2020 年的半年企業通道發行的版本資訊
ms.author: anankani
author: andymosten
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為 IT 專業人員提供 2020 年 Microsoft 365 Apps 半年通道版本的版本資訊
ms.openlocfilehash: f7f3b39521132fb11226bc512f782e0adec5aba8
ms.sourcegitcommit: ef46a4fc154c7bca37e37a7456c36f92ffc15ebb
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/13/2020
ms.locfileid: "48453411"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-releases-in-2020"></a><span data-ttu-id="b576b-103">2020 年的半年企業通道發行的版本資訊</span><span class="sxs-lookup"><span data-stu-id="b576b-103">Release notes for Semi-Annual Enterprise Channel releases in 2020</span></span>

<span data-ttu-id="b576b-104">這些版本資訊提供新功能和非安全性更新的相關資訊，這些功能和非安全性更新包含在 2020 年 Microsoft 365 Apps 企業版、Microsoft 365 Apps 商務版，以及 Project 和 Visio 版的傳統型應用程式訂閱版本的半年企業通道更新。</span><span class="sxs-lookup"><span data-stu-id="b576b-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel updates in 2020 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="b576b-105">我們會變更 Microsoft 365 應用程式的更新通道，包括新增新的更新通道 (每月企業通道)，並變更現有的更新通道名稱。</span><span class="sxs-lookup"><span data-stu-id="b576b-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="b576b-106">如需深入了解，[請閱讀本文](https://go.microsoft.com/fwlink/p/?linkid=2127441)。</span><span class="sxs-lookup"><span data-stu-id="b576b-106">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
>
>- <span data-ttu-id="b576b-107">當使用半年企業通道的使用者透過 Office 入口網站下載並安裝 Microsoft 365 Apps 到 Windows 10 上時，OneNote 2016 依預設將包括在其中。</span><span class="sxs-lookup"><span data-stu-id="b576b-107">OneNote 2016 will now be included by default when a user on the Semi-Annual Enterprise Channel downloads and installs Microsoft 365 Apps on Windows 10 from the Office Portal.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-october-13"></a><span data-ttu-id="b576b-109">版本 2002：10 月 13 日</span><span class="sxs-lookup"><span data-stu-id="b576b-109">Version 2002: October 13</span></span>
<span data-ttu-id="b576b-110">*版本 2002 (組建 12527.21236)*</span><span class="sxs-lookup"><span data-stu-id="b576b-110">*Version 2002 (Build 12527.21236)*</span></span>

<span data-ttu-id="b576b-111">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b576b-111">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="b576b-113">解決的問題</span><span class="sxs-lookup"><span data-stu-id="b576b-113">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="b576b-114">Access</span><span class="sxs-lookup"><span data-stu-id="b576b-114">Access</span></span>

- <span data-ttu-id="b576b-115">只要您滿足 Access 資料庫指導方針和需求，則應該不會再於您的 64 位元版本 Access 中收到「查詢太複雜」或系統資源滿載錯誤。</span><span class="sxs-lookup"><span data-stu-id="b576b-115">You should no longer receive a "Query is too complex" or a system resource exceeded error on your 64-bit version of Access, as long as you are meeting Access database guidelines and requirements.</span></span>


- <span data-ttu-id="b576b-116">一旦您決定在我們的查詢設計工具之後使用篩選功能，您的資料庫應該就不會再當機。</span><span class="sxs-lookup"><span data-stu-id="b576b-116">Once you decide to use our filter feature after our query designer, your database should no longer crash.</span></span> <span data-ttu-id="b576b-117">請相應地檢查。</span><span class="sxs-lookup"><span data-stu-id="b576b-117">Please check accordingly.</span></span>


### <a name="excel"></a><span data-ttu-id="b576b-118">Excel</span><span class="sxs-lookup"><span data-stu-id="b576b-118">Excel</span></span>

- <span data-ttu-id="b576b-119">我們修正了使用者無法修改樞紐分析表篩選的問題，因為它已設定為Analysis Services數據庫中不再存在的值。</span><span class="sxs-lookup"><span data-stu-id="b576b-119">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="b576b-120">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b576b-120">PowerPoint</span></span>

- <span data-ttu-id="b576b-121">從範本建立的新簡報會繼承設定，使得您無法順利進行共同撰寫。</span><span class="sxs-lookup"><span data-stu-id="b576b-121">New presentations created from a template could inherit a setting that prevented  a good co-authoring experience.</span></span> <span data-ttu-id="b576b-122">此修正程式可確保在此情況下會清除該設定。</span><span class="sxs-lookup"><span data-stu-id="b576b-122">This fix ensures that the setting is cleared in this case.</span></span>


### <a name="word"></a><span data-ttu-id="b576b-123">Word</span><span class="sxs-lookup"><span data-stu-id="b576b-123">Word</span></span>

- <span data-ttu-id="b576b-124">我們已修正在開啟含有分頁符號和欄的文件時，使用者可能會遇到錯誤訊息：「您已超過 Microsoft Word 所支援的頁數上限或此文件已損毀」</span><span class="sxs-lookup"><span data-stu-id="b576b-124">We fixed an issue which when opening documents with page breaks and columns, user might encountered an error message, " You have exceeded the maximum number of pages allowed by Microsoft Word supported, or the document may be damaged"</span></span>


### <a name="office-suite"></a><span data-ttu-id="b576b-125">Office 套件</span><span class="sxs-lookup"><span data-stu-id="b576b-125">Office Suite</span></span>

- <span data-ttu-id="b576b-126">當使用者從 Office 噴墨印表機上列印任何文件/檔案且列印機墨水不足時，即使噴墨印表機沒有碳粉，也會顯示「碳粉不足」或「無碳粉」消息。</span><span class="sxs-lookup"><span data-stu-id="b576b-126">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="b576b-127">將訊息變更為顯示「碳粉/墨水不足」和「沒有碳粉/墨水」。</span><span class="sxs-lookup"><span data-stu-id="b576b-127">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-october-13"></a><span data-ttu-id="b576b-129">版本 1908：10 月 13 日</span><span class="sxs-lookup"><span data-stu-id="b576b-129">Version 1908: October 13</span></span>
<span data-ttu-id="b576b-130">*版本 1908 (組建 11929.20966)*</span><span class="sxs-lookup"><span data-stu-id="b576b-130">*Version 1908 (Build 11929.20966)*</span></span>

<span data-ttu-id="b576b-131">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b576b-131">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="b576b-133">解決的問題</span><span class="sxs-lookup"><span data-stu-id="b576b-133">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="b576b-134">Office 套件</span><span class="sxs-lookup"><span data-stu-id="b576b-134">Office Suite</span></span>

- <span data-ttu-id="b576b-135">當使用者從 Office 噴墨印表機上列印任何文件/檔案且列印機墨水不足時，即使噴墨印表機沒有碳粉，也會顯示「碳粉不足」或「無碳粉」消息。</span><span class="sxs-lookup"><span data-stu-id="b576b-135">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="b576b-136">將訊息變更為顯示「碳粉/墨水不足」和「沒有碳粉/墨水」。</span><span class="sxs-lookup"><span data-stu-id="b576b-136">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-september-08"></a><span data-ttu-id="b576b-138">版本 2002：9 月 8 日</span><span class="sxs-lookup"><span data-stu-id="b576b-138">Version 2002: September 08</span></span>
<span data-ttu-id="b576b-139">*版本 2002 (組建 12527.21104)*</span><span class="sxs-lookup"><span data-stu-id="b576b-139">*Version 2002 (Build 12527.21104)*</span></span>

<span data-ttu-id="b576b-140">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b576b-140">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="b576b-142">解決的問題</span><span class="sxs-lookup"><span data-stu-id="b576b-142">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b576b-143">Excel</span><span class="sxs-lookup"><span data-stu-id="b576b-143">Excel</span></span>

- <span data-ttu-id="b576b-144">這解决了舊版 Office 中 SQL 資料提供者建立的連結設定內部表格内容與 Office 365 不同的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-144">This addresses an issue where connections created by the SQL data provider in older versions of Office would set internal table properties differently from Office 365.</span></span> <span data-ttu-id="b576b-145">這導致在舊版 Office 中使用 Office 365 開啟文件時，這些檔案的 [表格預覽/查詢編輯器] 下拉清單被停用。</span><span class="sxs-lookup"><span data-stu-id="b576b-145">This caused the Table Preview / Query Editor dropdown to be disabled for files with connections created in older versions of Office when they were opened using Office 365.</span></span>


- <span data-ttu-id="b576b-146">已解決筆跡會導致 Excel 無法回應的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-146">Resolved an issue where inking could cause Excel to become unresponsive.</span></span>


### <a name="outlook"></a><span data-ttu-id="b576b-147">Outlook</span><span class="sxs-lookup"><span data-stu-id="b576b-147">Outlook</span></span>

- <span data-ttu-id="b576b-148">已修正新增共用信箱之後，導致使用者無法連線至公用資料夾的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-148">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>


### <a name="office-suite"></a><span data-ttu-id="b576b-149">Office 套件</span><span class="sxs-lookup"><span data-stu-id="b576b-149">Office Suite</span></span>

- <span data-ttu-id="b576b-150">此變更解決 [壓縮圖片] 對話方塊無法保留特定使用者設定的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-150">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-september-08"></a><span data-ttu-id="b576b-152">版本 1908：9 月 8 日</span><span class="sxs-lookup"><span data-stu-id="b576b-152">Version 1908: September 08</span></span>
<span data-ttu-id="b576b-153">*版本 1908 (組建 11929.20946)*</span><span class="sxs-lookup"><span data-stu-id="b576b-153">*Version 1908 (Build 11929.20946)*</span></span>

<span data-ttu-id="b576b-154">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b576b-154">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2002-august-11"></a><span data-ttu-id="b576b-155">版本 2002: 8月11日</span><span class="sxs-lookup"><span data-stu-id="b576b-155">Version 2002: August 11</span></span>
<span data-ttu-id="b576b-156">*版本2002（组建12527.20988）*</span><span class="sxs-lookup"><span data-stu-id="b576b-156">*Version 2002 (Build 12527.20988)*</span></span>

<span data-ttu-id="b576b-157">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b576b-157">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="b576b-159">解決的問題</span><span class="sxs-lookup"><span data-stu-id="b576b-159">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b576b-160">Excel</span><span class="sxs-lookup"><span data-stu-id="b576b-160">Excel</span></span>

- <span data-ttu-id="b576b-161">修正了無法將以 [唯讀建議] 方式開啟的檔案切換至編輯功能的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-161">Fixed an issue which prevented the ability to switch to editing for files that opened as "read-only recommended".</span></span>

### <a name="onenote"></a><span data-ttu-id="b576b-162">OneNote</span><span class="sxs-lookup"><span data-stu-id="b576b-162">OneNote</span></span>

- <span data-ttu-id="b576b-163">移除了多餘的身分識別通話，以降低資源使用率</span><span class="sxs-lookup"><span data-stu-id="b576b-163">Removed redundant identity calls to reduce resource utilization</span></span>

- <span data-ttu-id="b576b-164">改善了共同撰寫狀態的偵測，以降低資源利用率。</span><span class="sxs-lookup"><span data-stu-id="b576b-164">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="b576b-165">改善了偵測錯誤的功能和同步處理經驗的品質。</span><span class="sxs-lookup"><span data-stu-id="b576b-165">Improved capability for detecting errors and the quality of the sync experience.</span></span>

### <a name="outlook"></a><span data-ttu-id="b576b-166">Outlook</span><span class="sxs-lookup"><span data-stu-id="b576b-166">Outlook</span></span>

- <span data-ttu-id="b576b-167">解决了在啟動某些租使用者的 Outlook 時，會導致嚴重效能問題的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-167">Addressed an issue that caused a significant performance issue when starting Outlook for some tenants.</span></span>

### <a name="skype"></a><span data-ttu-id="b576b-168">Skype</span><span class="sxs-lookup"><span data-stu-id="b576b-168">Skype</span></span>

- <span data-ttu-id="b576b-169">修正了在執行數天後，會無法啟動 32位元 Skype 商務版客戶螢幕共享的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-169">Fixed an issue where starting a screen share can fail on a 32-bit Skype for Business client after it has been running for several days.</span></span>

### <a name="office-suite"></a><span data-ttu-id="b576b-170">Office 套件</span><span class="sxs-lookup"><span data-stu-id="b576b-170">Office Suite</span></span>

- <span data-ttu-id="b576b-171">修正了如果 [自動儲存] 已透過組織政策關閉的話，某些文件可能不會在開啟時顯示最新的伺服器內容，除非使用者點擊 [可用的更新] 才會顯現。</span><span class="sxs-lookup"><span data-stu-id="b576b-171">Fixed an issue where if AutoSave is turned off through group policy, some documents might not show the latest server contents on open until the user clicks on 'Updates available'.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-august-11"></a><span data-ttu-id="b576b-173">版本 1908: 8月11日</span><span class="sxs-lookup"><span data-stu-id="b576b-173">Version 1908: August 11</span></span>
<span data-ttu-id="b576b-174">*版本 1908 (組建 11929.20934)*</span><span class="sxs-lookup"><span data-stu-id="b576b-174">*Version 1908 (Build 11929.20934)*</span></span>

<span data-ttu-id="b576b-175">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b576b-175">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1902-august-11"></a><span data-ttu-id="b576b-176">版本 1902: 8月11日</span><span class="sxs-lookup"><span data-stu-id="b576b-176">Version 1902: August 11</span></span>
<span data-ttu-id="b576b-177">*版本 1902 (組建 11328.20644)*</span><span class="sxs-lookup"><span data-stu-id="b576b-177">*Version 1902 (Build 11328.20644)*</span></span>

<span data-ttu-id="b576b-178">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b576b-178">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-july-14"></a><span data-ttu-id="b576b-181">版本 2002：7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="b576b-181">Version 2002: July 14</span></span>
<span data-ttu-id="b576b-182">*版本 2002 (組建 12527.20880)*</span><span class="sxs-lookup"><span data-stu-id="b576b-182">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="b576b-183">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b576b-183">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="b576b-185">功能更新</span><span class="sxs-lookup"><span data-stu-id="b576b-185">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="b576b-186">Access</span><span class="sxs-lookup"><span data-stu-id="b576b-186">Access</span></span>

- <span data-ttu-id="b576b-187">**快速尋找連結資料表：** 新的搜尋方塊可讓您輕鬆尋找連結資料表。</span><span class="sxs-lookup"><span data-stu-id="b576b-187">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="b576b-188">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-188">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="b576b-189">Excel</span><span class="sxs-lookup"><span data-stu-id="b576b-189">Excel</span></span>

- <span data-ttu-id="b576b-190">**更快速共用檔案：** 不需開啟檔案，即可從最近使用清單直接共用您的檔案。</span><span class="sxs-lookup"><span data-stu-id="b576b-190">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="b576b-191">**資料視覺化工具增益集：** 從 Excel 快速建立 Visio 流程圖。</span><span class="sxs-lookup"><span data-stu-id="b576b-191">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="b576b-192">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-192">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="b576b-193">**建立更易於存取的 PDF：** 建立 PDF 檔案，在儲存之前，協助工具檢查程式會指出應該修正的協助工具問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-193">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="b576b-194">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-194">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br /><span data-ttu-id="b576b-195">在[部落格文章](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="b576b-195">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="b576b-196">**符合您情境的更多圖示：** 我們新增了超過 300 個新圖示。</span><span class="sxs-lookup"><span data-stu-id="b576b-196">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="b576b-197">其位置：[插入] > [圖示]。</span><span class="sxs-lookup"><span data-stu-id="b576b-197">Find them at Insert > Icons.</span></span> [<span data-ttu-id="b576b-198">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-198">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="b576b-199">**轉換檔案，以改善協助工具功能：** 將您的檔案升級為現代格式，讓所有人更容易存取。</span><span class="sxs-lookup"><span data-stu-id="b576b-199">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="b576b-200">在[部落格文章](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="b576b-200">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="b576b-201">**專注於剩餘工作：** 選取 [解決] 來摺疊註解，使得開啟中的項目能夠突顯。</span><span class="sxs-lookup"><span data-stu-id="b576b-201">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="b576b-202">**輸入會傳回多個值的公式**：現在您可以快速輸入公式來傳回多個值，並且值會自動溢出至相鄰的儲存格。</span><span class="sxs-lookup"><span data-stu-id="b576b-202">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="b576b-203">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-203">Learn more</span></span>](https://support.office.com/article/5c2c9cbb-def8-409a-b380-2fbf91b20aa3)<br /><span data-ttu-id="b576b-204">在[部落格文章](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="b576b-204">See details in [blog post](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)</span></span>

- <span data-ttu-id="b576b-205">**不必再來回往返瀏覽器：** 您決定開啟 Office 文件連結的方式：在瀏覽器或應用程式中開啟。</span><span class="sxs-lookup"><span data-stu-id="b576b-205">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="b576b-206">**勾勒草圖：** 為活頁簿中的 Office 圖形提供隨意的手繪外觀。</span><span class="sxs-lookup"><span data-stu-id="b576b-206">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="b576b-207">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-207">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="b576b-208">在[部落格文章](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="b576b-208">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="b576b-209">**找到您要尋找的項目：** 搜尋命令、人員、檔案、相片、網頁文章等。</span><span class="sxs-lookup"><span data-stu-id="b576b-209">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="b576b-210">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-210">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="b576b-211">**六個功能強大的函數：** 我們新增了六個新的函數，讓您的試算表功能更強大：FILTER、SORT、SORTBY、UNIQUE、SEQUENCE 和 RANDARRAY。</span><span class="sxs-lookup"><span data-stu-id="b576b-211">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span> [<span data-ttu-id="b576b-212">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-212">Learn more</span></span>](https://support.office.com/article/003df6c7-1dcb-4388-8e2e-0fe77a0887bc)

- <span data-ttu-id="b576b-213">**向左看，向右看... XLOOKUP 在這裡！：** 一列接著一列，在含有 XLOOKUP 的表格或範圍中尋找您需要的項目。</span><span class="sxs-lookup"><span data-stu-id="b576b-213">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span> [<span data-ttu-id="b576b-214">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-214">Learn more</span></span>](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)<br /><span data-ttu-id="b576b-215">在[部落格文章](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="b576b-215">See details in [blog post](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)</span></span>

- <span data-ttu-id="b576b-216">**整理您的大型活頁簿：** 儲存格、公式、圖表、表格... 利用「活頁簿統計資料」來取得活頁簿的快照。</span><span class="sxs-lookup"><span data-stu-id="b576b-216">**Tame your big workbook:** Cells, formulas, charts, tables... get a snapshot of your workbook with Workbook Statistics.</span></span>

- <span data-ttu-id="b576b-217">**即時讀取與回覆：** 直接從電子郵件回覆註解和提及，而不需開啟活頁簿。</span><span class="sxs-lookup"><span data-stu-id="b576b-217">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="b576b-218">**使用 \@Mentions 提及功能取得他人注意：** 在註解中使用 @mentions 提及功能，讓同事知道您需要他們提供建議。</span><span class="sxs-lookup"><span data-stu-id="b576b-218">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="b576b-219">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-219">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

### <a name="outlook"></a><span data-ttu-id="b576b-220">Outlook</span><span class="sxs-lookup"><span data-stu-id="b576b-220">Outlook</span></span>

- <span data-ttu-id="b576b-221">**在螢幕上容納更多郵件：** 選取 [檢視] > [使用更緊密的間距] 來調整郵件之間的間距。</span><span class="sxs-lookup"><span data-stu-id="b576b-221">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="b576b-222">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-222">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="b576b-223">**符合您情境的更多圖示：** 我們新增了超過 300 個新圖示。</span><span class="sxs-lookup"><span data-stu-id="b576b-223">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="b576b-224">其位置：[插入] > [圖示]。</span><span class="sxs-lookup"><span data-stu-id="b576b-224">Find them at Insert > Icons.</span></span> [<span data-ttu-id="b576b-225">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-225">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="b576b-226">**讓我繪製：** 使用筆跡在圖片上徒手畫或新增繪圖畫布來傳達您的想法。</span><span class="sxs-lookup"><span data-stu-id="b576b-226">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="b576b-227">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-227">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="b576b-228">**取得位置建議：** 排程約會和會議時，請在 [位置] 中開始輸入，Outlook 會建議會議室、地址，以及其他最近使用的位置。</span><span class="sxs-lookup"><span data-stu-id="b576b-228">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="b576b-229">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-229">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)<br /><span data-ttu-id="b576b-230">在[部落格文章](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="b576b-230">See details in [blog post](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/)</span></span>

- <span data-ttu-id="b576b-231">**抵禦攻擊的進階防護：** 使用 Office 365 進階威脅防護，您會受到保護，不受電子郵件主旨、附加的郵件、簽署的郵件、網路路徑內超連結的攻擊。</span><span class="sxs-lookup"><span data-stu-id="b576b-231">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="b576b-232">**Outlook 中的 [插入連結] 功能表會插入含有租用戶系統管理員所定義的權限的連結：** Outlook 中使用 [插入連結] 所插入的連結，只有具有連結權限的使用者可使用。</span><span class="sxs-lookup"><span data-stu-id="b576b-232">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="b576b-233">這常會造成使用者來回傳送電子郵件，要求對方授與文件的存取權。</span><span class="sxs-lookup"><span data-stu-id="b576b-233">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="b576b-234">我們已更新這項體驗，現在插入的連結將具有由租用戶系統管理員設定的預設權限。針對 MSIT，這是「組織可以編輯」，使得以此方式收到共用連結的所有內部使用者將可以存取它。</span><span class="sxs-lookup"><span data-stu-id="b576b-234">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="b576b-235">**在不同燈光下查看郵件：** 使用太陽/月亮按鈕以在讀取窗格中於淺色和深色背景之間切換。</span><span class="sxs-lookup"><span data-stu-id="b576b-235">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="b576b-236">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-236">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="b576b-237">**網路釣魚郵件很容易找到：** 垃圾郵件和網路釣魚訊息的外觀不同，因此您可以從收件匣輕鬆找出並加以清除。</span><span class="sxs-lookup"><span data-stu-id="b576b-237">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="b576b-p123">**集中所有加密選項：** 只要前往 [選項] > [加密]，即可選擇要用來保護電子郵件訊息的方法。[深入了解](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="b576b-p123">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="b576b-240">**具有拼字問題或錯字的搜尋：** 即使您的拼寫不相符，Outlook 也會找到您要尋找的內容。</span><span class="sxs-lookup"><span data-stu-id="b576b-240">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="b576b-241">**將您的 LinkedIn 人際網路連接至 Outlook：** 安全地將您的 LinkedIn 帳戶與 Microsoft 帳戶連結，以直接在人員卡片中查看 LinkedIn 個人資料中的資訊。</span><span class="sxs-lookup"><span data-stu-id="b576b-241">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="b576b-242">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-242">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="b576b-243">**在搜尋結果中查看相關郵件：** Outlook 會分析搜尋字詞，然後在搜尋結果的最上方顯示最相關的電子郵件。</span><span class="sxs-lookup"><span data-stu-id="b576b-243">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="b576b-244">您也可以在 [最佳結果] 區段中查看依日期排列順序的所有結果。</span><span class="sxs-lookup"><span data-stu-id="b576b-244">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="b576b-245">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-245">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

### <a name="powerpoint"></a><span data-ttu-id="b576b-246">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b576b-246">PowerPoint</span></span>

- <span data-ttu-id="b576b-p126">**您來計算，格式設定交給我們**我們能將難懂的手寫數學運算式變更為標準字元。只要選擇 [筆跡轉換數學]，然後選取您的手寫筆記，即可開始使用。[深入了解](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="b576b-p126">**You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

- <span data-ttu-id="b576b-250">**尋找您要尋找的項目：** 使用搜尋方塊來尋找文字、命令、說明等。</span><span class="sxs-lookup"><span data-stu-id="b576b-250">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="b576b-251">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-251">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="b576b-252">**運用筆跡製作精彩的投影片：** 將筆跡轉換成標準圖形和文字，然後從 PowerPoint 設計工具吸取智慧的投影片設計概念。</span><span class="sxs-lookup"><span data-stu-id="b576b-252">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="b576b-253">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-253">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- <span data-ttu-id="b576b-254">**勾勒草圖：** 為簡報中的 Office 圖形提供隨意的手繪外觀。</span><span class="sxs-lookup"><span data-stu-id="b576b-254">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="b576b-255">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-255">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="b576b-256">在[部落格文章](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="b576b-256">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="b576b-257">**筆跡立即重播：** 當您在投影片上進行手寫時，套用重播動畫可在投影片放映期間重播真實手繪的筆跡。</span><span class="sxs-lookup"><span data-stu-id="b576b-257">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="b576b-258">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-258">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)<br /><span data-ttu-id="b576b-259">在[部落格文章](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="b576b-259">See details in [blog post](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/)</span></span>

- <span data-ttu-id="b576b-260">**更安全的影片體驗：** 安全性增強功能可讓您擁有更安全的線上影片體驗。</span><span class="sxs-lookup"><span data-stu-id="b576b-260">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="b576b-261">**將圖例另存成 SVG：** 將圖表、圖形或其他圖例另存成可縮放向量圖形，其可調整大小，且不損失影像品質。</span><span class="sxs-lookup"><span data-stu-id="b576b-261">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="b576b-262">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-262">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="b576b-263">**列印講義上的投影片編號：** 投影片編號會自動包含在講義上。</span><span class="sxs-lookup"><span data-stu-id="b576b-263">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="b576b-264">由您決定將其保留或關閉。</span><span class="sxs-lookup"><span data-stu-id="b576b-264">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="b576b-265">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-265">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="b576b-266">**尋找並修正遺失的投影片標題：** 投影片標題可為您的企劃加分，並讓所有功能的使用者都能存取投影片。</span><span class="sxs-lookup"><span data-stu-id="b576b-266">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="b576b-267">協助工具檢查程式會顯示缺少標題的地方，這樣您就可以快速新增標題。</span><span class="sxs-lookup"><span data-stu-id="b576b-267">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="b576b-268">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-268">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="b576b-269">**轉換檔案，以改善協助工具功能：** 將您的檔案升級為現代格式，讓所有人更容易存取。</span><span class="sxs-lookup"><span data-stu-id="b576b-269">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="b576b-270">在[部落格文章](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="b576b-270">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="b576b-271">**符合您情境的更多圖示：** 我們新增了超過 300 個新圖示。</span><span class="sxs-lookup"><span data-stu-id="b576b-271">**More icons to match your mood:** We've added more than 300 new icons.</span></span> <span data-ttu-id="b576b-272">其位置：[插入] > [圖示]。</span><span class="sxs-lookup"><span data-stu-id="b576b-272">Find them at Insert > Icons.</span></span> [<span data-ttu-id="b576b-273">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-273">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="b576b-274">**建立更易於存取的 PDF：** 建立 PDF 檔案，在儲存之前，協助工具檢查程式會指出應該修正的協助工具問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-274">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span><br /><span data-ttu-id="b576b-275">在[部落格文章](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="b576b-275">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="b576b-276">**更快速共用檔案：** 不需開啟檔案，即可從最近使用清單直接共用您的檔案。</span><span class="sxs-lookup"><span data-stu-id="b576b-276">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="b576b-277">**在 PowerPoint 中快速即時共同作業：** 在 PowerPoint 中快速即時共同作業</span><span class="sxs-lookup"><span data-stu-id="b576b-277">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="b576b-278">**不必再來回往返瀏覽器：** 您決定開啟 Office 文件連結的方式：在瀏覽器或應用程式中開啟。</span><span class="sxs-lookup"><span data-stu-id="b576b-278">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="b576b-279">**新的校對工具：** 不著重您的文字。</span><span class="sxs-lookup"><span data-stu-id="b576b-279">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="b576b-280">PowerPoint 現在提供文法及書寫建議。</span><span class="sxs-lookup"><span data-stu-id="b576b-280">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="b576b-281">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-281">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="b576b-282">**即時的輔助字幕和翻譯字幕：** 簡報者的文字會自動顯示為畫面上的標題，或翻譯為所選語言的字幕。</span><span class="sxs-lookup"><span data-stu-id="b576b-282">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="b576b-283">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-283">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="b576b-284">**最佳化您的簡報：** 協助工具檢查程式可協助您以螢幕閱讀器為中心，在投影片上排列物件。</span><span class="sxs-lookup"><span data-stu-id="b576b-284">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span><br /><span data-ttu-id="b576b-285">在[部落格文章](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="b576b-285">See details in [blog post](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/)</span></span>

- <span data-ttu-id="b576b-286">**當您可以重複使用時為什麼要重新打造？** 重複使用您所建立的投影片或其他人與您共用的投影片來以節省時間。</span><span class="sxs-lookup"><span data-stu-id="b576b-286">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="b576b-287">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-287">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

### <a name="visio"></a><span data-ttu-id="b576b-288">Visio</span><span class="sxs-lookup"><span data-stu-id="b576b-288">Visio</span></span>

- <span data-ttu-id="b576b-289">**在 Excel 中製作精美的 Visio 圖表：** 將資料放在工作表上，以建立流程圖或組織圖。</span><span class="sxs-lookup"><span data-stu-id="b576b-289">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="b576b-290">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-290">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="b576b-291">**回到犯罪場景：** 在犯罪場景調查範本中使用新的證據、室內、室外樣板，重建犯罪場景的細節。</span><span class="sxs-lookup"><span data-stu-id="b576b-291">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

### <a name="word"></a><span data-ttu-id="b576b-292">Word</span><span class="sxs-lookup"><span data-stu-id="b576b-292">Word</span></span>

- <span data-ttu-id="b576b-293">**更安全的影片體驗：** 安全性增強功能可讓您擁有更安全的線上影片體驗。</span><span class="sxs-lookup"><span data-stu-id="b576b-293">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="b576b-294">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-294">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- <span data-ttu-id="b576b-295">**建立更易於存取的 PDF：** 建立 PDF 檔案，在儲存之前，協助工具檢查程式會指出應該修正的協助工具問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-295">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="b576b-296">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-296">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br /><span data-ttu-id="b576b-297">在[部落格文章](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="b576b-297">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="b576b-298">**更快速共用檔案：** 不需開啟檔案，即可從最近使用清單直接共用您的檔案。</span><span class="sxs-lookup"><span data-stu-id="b576b-298">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="b576b-299">**符合您情境的更多圖示：** 我們新增了超過 300 個新圖示。</span><span class="sxs-lookup"><span data-stu-id="b576b-299">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="b576b-300">其位置：[插入] > [圖示]。</span><span class="sxs-lookup"><span data-stu-id="b576b-300">Find them at Insert > Icons.</span></span> [<span data-ttu-id="b576b-301">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-301">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)<br /><span data-ttu-id="b576b-302">在[部落格文章](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="b576b-302">See details in [blog post](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/)</span></span>

- <span data-ttu-id="b576b-303">**精確橡皮擦：** 從兩個橡皮擦尺寸中選擇，以修正小型筆跡缺陷。</span><span class="sxs-lookup"><span data-stu-id="b576b-303">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="b576b-304">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-304">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="b576b-305">**轉換檔案，以改善協助工具功能：** 將您的檔案升級為現代格式，讓所有人更容易存取。</span><span class="sxs-lookup"><span data-stu-id="b576b-305">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="b576b-306">在[部落格文章](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="b576b-306">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="b576b-307">**勾勒草圖：** 為文件中的 Office 圖形提供隨意的手繪外觀。</span><span class="sxs-lookup"><span data-stu-id="b576b-307">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="b576b-308">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-308">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="b576b-309">在[部落格文章](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="b576b-309">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="b576b-310">**尋找您要尋找的項目：** 使用搜尋方塊來尋找文字、命令、說明等。</span><span class="sxs-lookup"><span data-stu-id="b576b-310">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="b576b-311">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-311">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="b576b-312">**不必再來回往返瀏覽器：** 您決定開啟 Office 文件連結的方式：在瀏覽器或應用程式中開啟。</span><span class="sxs-lookup"><span data-stu-id="b576b-312">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="b576b-313">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-313">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="b576b-314">**簡歷編輯器加入 LinkedIn 簡歷小幫手：** 簡歷編輯器提供特別為簡歷量身打造的文法和樣式檢查選項，讓您的寫作更準確且更專業。</span><span class="sxs-lookup"><span data-stu-id="b576b-314">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="b576b-315">**其他人更快速看到您的變更：** 共同撰寫增強功能表示，共同作業者可較以往更快速看到您的變更。</span><span class="sxs-lookup"><span data-stu-id="b576b-315">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="b576b-316">**修正合併 3D 物件所造成的文件損毀問題：** 修正合併 3D 物件所造成的文件損毀問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-316">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="b576b-317">**共同撰寫的增強功能**：在具有追蹤修訂的文件中共同撰寫來強化 Word 效能。</span><span class="sxs-lookup"><span data-stu-id="b576b-317">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="b576b-318">**共同撰寫的增強功能**：增強共同撰寫時的可靠性。</span><span class="sxs-lookup"><span data-stu-id="b576b-318">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="b576b-319">**在生動色彩中進行共同作業：** 註解和變更都依參與者加上色彩標示，讓您可以輕鬆查看您的共同作業者。</span><span class="sxs-lookup"><span data-stu-id="b576b-319">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="b576b-320">**共同編輯啟用巨集的文件：** 將 docm 檔案儲存在商務用 OneDrive，並與共同作業者即時編輯。</span><span class="sxs-lookup"><span data-stu-id="b576b-320">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

### <a name="office-suite"></a><span data-ttu-id="b576b-321">Office 套件</span><span class="sxs-lookup"><span data-stu-id="b576b-321">Office Suite</span></span>

- <span data-ttu-id="b576b-322">**在 Office 365 的 PowerPoint 中將手寫筆跡變更為圖形、文字或數學：** 從任意格式的筆跡變成 Office 圖形、文字，或以幾個筆劃變成數學運算式。</span><span class="sxs-lookup"><span data-stu-id="b576b-322">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="b576b-323">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-323">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="b576b-326">解決的問題</span><span class="sxs-lookup"><span data-stu-id="b576b-326">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="b576b-327">Access</span><span class="sxs-lookup"><span data-stu-id="b576b-327">Access</span></span>

- <span data-ttu-id="b576b-328">此更新會修正使用 ADODB 的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-328">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="b576b-329">VB 程式碼中的記錄器物件可能會不正確地報告錯誤。</span><span class="sxs-lookup"><span data-stu-id="b576b-329">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="b576b-330">Access 範本應不再導致資料庫中的附件欄出現故障。</span><span class="sxs-lookup"><span data-stu-id="b576b-330">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="b576b-331">個體化範本後，您現在應該可以將附件欄新增至資料庫。</span><span class="sxs-lookup"><span data-stu-id="b576b-331">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="b576b-332">此更新修正可能會導致 Microsoft Access 無法識別連結的 SQL Server 資料表中的識別資料行的問題，這可能會導致不正確地將資料列報告為已刪除。</span><span class="sxs-lookup"><span data-stu-id="b576b-332">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="b576b-333">此更新可修正 Microsoft Access 中的「更新查詢」執行時或在 SQL 中使用 UPDATE 陳述式時，可能導致錯誤「查詢已損壞」的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-333">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="b576b-334">Excel</span><span class="sxs-lookup"><span data-stu-id="b576b-334">Excel</span></span>

- <span data-ttu-id="b576b-335">加速載入本機 OneDrive 資料夾中的檔案。</span><span class="sxs-lookup"><span data-stu-id="b576b-335">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="b576b-336">修正 CUBEVALUE 函數有時會傳回不正確結果的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-336">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="b576b-337">解決開啟內嵌活頁簿時，功能區自訂無法載入的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-337">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="b576b-338">在 Word 或 PowerPoint 中重新開啟內嵌的活頁簿時，在某些情況下 Excel 會當機。</span><span class="sxs-lookup"><span data-stu-id="b576b-338">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="b576b-339">修正操作功能表中的註解命令未顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-339">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="b576b-340">我們修正了樞紐分析圖的右鍵功能表，以啟用 [顯示詳細資料] 選項。</span><span class="sxs-lookup"><span data-stu-id="b576b-340">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="b576b-341">解決在未開啟活頁簿時，搜尋最近使用的檔案會造成當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-341">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="b576b-342">修正在相同活頁簿中按一下加入書籤的超連結會導致活頁簿隱藏的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-342">Fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="b576b-343">儲存為 CSV 檔案時，在某些情況下，Excel 會將所有欄合併成單一欄。</span><span class="sxs-lookup"><span data-stu-id="b576b-343">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="b576b-344">在受保護工作表中的範圍使用 Range.ClearContents 可能會比預期花的時間更長。</span><span class="sxs-lookup"><span data-stu-id="b576b-344">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="b576b-345">修正了在 [預覽列印] 中顯示表單控制項時的文字縮放比例問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-345">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="b576b-346">與功能區互動的 VBA 宏可能會意外以 ScreenUpdating 設定為 True 執行。</span><span class="sxs-lookup"><span data-stu-id="b576b-346">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="b576b-347">修正在複製含有樞紐分析表的工作表後，會於某些情況下導致 Excel 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-347">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="b576b-348">在某些情況下，開啟 CSV 檔案所花費的時間超過預期。</span><span class="sxs-lookup"><span data-stu-id="b576b-348">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="b576b-349">在某些情況下，當您切換不同縮放比例的活頁簿時，Excel 可能會當機。</span><span class="sxs-lookup"><span data-stu-id="b576b-349">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="b576b-350">已修正 VBA 將值寫入範圍時，速度比預期慢的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-350">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="b576b-351">從有色彩篩選的欄複製的資料有時候無法正確貼上。</span><span class="sxs-lookup"><span data-stu-id="b576b-351">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="b576b-352">開啟含有許多其他活頁簿 (尤其是含有隱藏視窗) 參照的活頁簿時，速度比預期慢。</span><span class="sxs-lookup"><span data-stu-id="b576b-352">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="b576b-353">解決當來源活頁簿關閉時，外部連結在填滿時 (向下填滿、跨表填滿等) 不會更新的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-353">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is& closed.</span></span>

- <span data-ttu-id="b576b-354">修正透過 Teams 共用 Excel 視窗時，使用 Ctrl+Shift+方向鍵來捲動之後，可能會使得 Excel 未回應的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-354">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="b576b-355">在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。</span><span class="sxs-lookup"><span data-stu-id="b576b-355">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="b576b-356">解決在儲存並重新開啟檔案時，圖表軸上的「值置於」屬性非預期變更的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-356">Addresses an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="b576b-357">修正儲存至 SharePoint/OneDrive 時，會導致將自訂功能區索引標籤的 CustomUI XML 移除的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-357">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="b576b-358">改善刪除具有合併儲存格的欄時的效能。</span><span class="sxs-lookup"><span data-stu-id="b576b-358">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="b576b-359">修正 [列印] 對話方塊的印表機清單中，印表機名稱可能會重複的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-359">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="b576b-360">修正當檔案路徑太長時，在重新開啟檔案後，外部連結會停止運作的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-360">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="b576b-361">已修正列印時表單控制項的核取方塊縮放的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-361">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="b576b-362">當您使用舊版的「共用活頁簿」模式，嘗試為活頁簿的新工作表列出變更時，就會發生當機。</span><span class="sxs-lookup"><span data-stu-id="b576b-362">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="b576b-363">在已篩選清單中插入欄的時間會比預期更長。</span><span class="sxs-lookup"><span data-stu-id="b576b-363">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="b576b-364">我們已修正某些複製和貼上的圖表連結使用的是對應磁碟機位址，而不是通用位址的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-364">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="b576b-365">修正因為增益集是以字母順序載入，而不是以使用者指定的順序載入，而顯示 [這個活頁簿目前正由其他活頁簿所參考中，不可關閉] 錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-365">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="b576b-366">修正按一下已開啟活頁簿中某個位置的超連結時，活頁簿可能會隱藏的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-366">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="b576b-367">開啟含有許多其他活頁簿 (尤其是含有隱藏視窗) 參照的活頁簿時，速度比預期慢。</span><span class="sxs-lookup"><span data-stu-id="b576b-367">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="b576b-368">使用 VBA 應用程式的 Application.Evaluate 在某些情況下，對使用者定義的函數無法運作。</span><span class="sxs-lookup"><span data-stu-id="b576b-368">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="b576b-369">修正某些使用者使用內嵌和連結物件 (OLE) 時可能發生的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-369">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="b576b-370">使用者在使用某些非英文字元集的情況下，儲存變更時可能會遇到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-370">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="b576b-371">此更新可修正會導致資料編輯列以較預期不同的字型顯示文字的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-371">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="b576b-372">使用者在使用某些非英文字元集的情況下，儲存變更時可能會遇到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-372">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="b576b-373">解決捲動後選取儲存格時，可能導致選取錯誤儲存格的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-373">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="b576b-374">使用者在存取隱藏的命名範圍時可能會遇到錯誤。</span><span class="sxs-lookup"><span data-stu-id="b576b-374">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="b576b-375">從不受信任的網路共用編輯受保護的檔案時，Excel 可能會發生問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-375">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="b576b-376">某些當地語系化版本的 [文字到欄] 功能可能會失敗。</span><span class="sxs-lookup"><span data-stu-id="b576b-376">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="b576b-377">解決從範本建立圖表時的效能問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-377">Addresses a performance issue when creating charts from templates.</span></span>

- <span data-ttu-id="b576b-378">修正對具有溢出陣列之儲存格進行資料剖析的轉換時，導致某些使用者發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-378">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="b576b-379">使用 Range.Value 和 Range.Value2 (VBA) 會導致公式以動態陣列的形式輸入。</span><span class="sxs-lookup"><span data-stu-id="b576b-379">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

- <span data-ttu-id="b576b-380">修正公式開頭的 @ 符號會被視為隱含交集運算子的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-380">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

- <span data-ttu-id="b576b-381">我們已修正包含多個含有定義名稱的公式，會導致儲存檔案時間加長的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-381">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

- <span data-ttu-id="b576b-382">此變更利用軟體轉譯，以避免特定 Intel 圖形驅動程式的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-382">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="b576b-383">解決重新命名簽名時，會導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-383">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="onenote"></a><span data-ttu-id="b576b-384">OneNote</span><span class="sxs-lookup"><span data-stu-id="b576b-384">OneNote</span></span>

- <span data-ttu-id="b576b-385">透過暫時調整 OneNote 2016 中的同步處理頻率，來改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="b576b-385">Improve sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="b576b-386">透過暫時延遲下載線上筆記本中內嵌的檔案和影像，直到使用者瀏覽至 OneNote 2016 中的頁面，來改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="b576b-386">Improve sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="b576b-387">透過暫時停用 OneNote 2016 中的資源回收筒，來改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="b576b-387">Improve sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="b576b-388">當使用者嘗試刪除通常會傳送到 [資源回收筒] 的資料時，系統會詢問使用者是否希望保留或永久刪除資料。</span><span class="sxs-lookup"><span data-stu-id="b576b-388">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="b576b-389">透過暫時將 OneNote 2016 中版本歷程記錄頁面的數目和同步處理頻率降低，來改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="b576b-389">Improve sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="b576b-390">顯示通知，讓使用者可以了解更多 OneNote 使用者體驗中正在採取的臨時措施的資訊，以改善同步處理和服務穩定性。</span><span class="sxs-lookup"><span data-stu-id="b576b-390">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="b576b-391">透過暫時將 OneNote 2016 中新嵌入附件的最大允許大小減少為 50 MB，來改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="b576b-391">Improve sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="b576b-392">對於超過此限制的檔案，使用者可以選擇將檔案上傳到 OneDrive，並將連結插入 OneNote。</span><span class="sxs-lookup"><span data-stu-id="b576b-392">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="b576b-393">透過暫時停用 OneNote 2016 中的應用程式內視訊錄製，來改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="b576b-393">Improve sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="b576b-394">本機筆記本不受這個測量的影響。</span><span class="sxs-lookup"><span data-stu-id="b576b-394">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="b576b-395">對通知進行本地化，讓使用者可以了解更多 OneNote 使用者體驗中正在採取的臨時措施的資訊，以改善同步處理和服務穩定性。</span><span class="sxs-lookup"><span data-stu-id="b576b-395">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="b576b-396">Outlook</span><span class="sxs-lookup"><span data-stu-id="b576b-396">Outlook</span></span>

- <span data-ttu-id="b576b-397">我們已修正以下問題：當使用多個不同解析度的監視器時，輸入法編輯器 (IEM) 視窗會覆蓋透過 IME 輸入的文字。</span><span class="sxs-lookup"><span data-stu-id="b576b-397">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="b576b-398">解決會導致使用者在 Outlook 中偶爾看到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-398">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

- <span data-ttu-id="b576b-399">此這會更新 Outlook 中的附件封鎖邏輯，以同時封鎖 Python 附件。</span><span class="sxs-lookup"><span data-stu-id="b576b-399">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="b576b-400">解決會導致網頁增益集存取數位版權管理訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-400">Addresses an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="b576b-401">解決會導致週期性約會或會議在接近時區定義變更時於錯誤的時間顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-401">Addresses an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="b576b-402">在 2019 年使用巴西時區時，週期性會議和約會以 2020 年的錯誤時段顯示。</span><span class="sxs-lookup"><span data-stu-id="b576b-402">When using the Brazilia time zone in the year 2019, recurring meetings and appointments are displayed in the wrong timeslot for the year 2020.</span></span> <span data-ttu-id="b576b-403">此變更與設定使用巴西時區的用戶端或設定使用該時區的會議和約會相關。</span><span class="sxs-lookup"><span data-stu-id="b576b-403">This change is relevant for clients set in the Brazilia time zone or for meetings and appointments set in that time zone.</span></span><br><br><span data-ttu-id="b576b-404">此變更會允許 Outlook 覆寫 Outlook 所使用的特定時區設定。</span><span class="sxs-lookup"><span data-stu-id="b576b-404">This change allows Outlook to override certain time zone settings used by Outlook.</span></span> <span data-ttu-id="b576b-405">若要叫用時區覆寫，您必須為目前的使用者設定登錄機碼。</span><span class="sxs-lookup"><span data-stu-id="b576b-405">In order to invoke a time zone override you must set a registry key for the current user.</span></span> <span data-ttu-id="b576b-406">登錄機碼名稱必須符合時區的內部名稱。</span><span class="sxs-lookup"><span data-stu-id="b576b-406">The registry key name must match the internal name of the time zone.</span></span> <span data-ttu-id="b576b-407">值表示時區規則的年，用來取代生效年。</span><span class="sxs-lookup"><span data-stu-id="b576b-407">The value indicates the time zone rule's year to be used in place of the effective year.</span></span> <span data-ttu-id="b576b-408">例如，下列登錄機碼覆寫值將使用巴西時區規則做為 2020 年的生效規則。</span><span class="sxs-lookup"><span data-stu-id="b576b-408">For example, the following registry key override value will use the Brazilia time zone rule for the year 2020 as the effective rule.</span></span> <span data-ttu-id="b576b-409">HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"E.</span><span class="sxs-lookup"><span data-stu-id="b576b-409">HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"E.</span></span> <span data-ttu-id="b576b-410">South America Standard Time"=dword:000007e4.</span><span class="sxs-lookup"><span data-stu-id="b576b-410">South America Standard Time"=dword:000007e4.</span></span>

- <span data-ttu-id="b576b-411">解決會導致使用者在會議中看到位置欄位非預期變更的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-411">Addresses an issue that caused users to see the location field in meetings change unexpectedly.</span></span>

- <span data-ttu-id="b576b-412">解決會導致會議中的 [位置] 欄位非預期更新的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-412">Addresses an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="b576b-413">解決會導致會議位置在清除之後，又會非預期地重新加回會議的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-413">Addresses an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="b576b-414">解決會導致會議的位置欄位中的逗號變成分號的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-414">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="b576b-415">可透過原生 Teams 用戶端直接加入 Teams 會議。</span><span class="sxs-lookup"><span data-stu-id="b576b-415">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="b576b-416">解決會導致使用 Exchange 2010 伺服器上信箱的使用者，在將附件新增至行事曆項目時遇到問題的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-416">Addresses an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="b576b-417">解決會導致使用者在回覆數位簽章郵件時遇到問題的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-417">Addresses an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="b576b-418">解決會導致使用者無法開啟某些週期性行事曆項目執行個體的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-418">Addresses an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="b576b-419">解決在某些情況下，[群組] 標題會非預期展開的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-419">Addresses an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="b576b-420">解決會導致資料夾窗格寬度非預期地變更的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-420">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="b576b-421">解決 Outlook 無法為已支付 M365 Business Plus 方案服務的使用者啟用「資料外洩防護」原則提示的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-421">Addresses an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="b576b-422">解決當使用者透過鍵盤快速鍵與信箱資料夾互動時，會導致明顯延遲的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-422">Addresses an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="b576b-423">解決在多個視窗中檢視相同項目時可能會導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-423">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="b576b-424">解決會導致使用者在 Outlook 中更新其規則時，看到「此電腦上的規則與 Microsoft Exchange 上的規則不相符」訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-424">Addresses an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="b576b-425">解決會導致非常長時間的 Outlook 工作階段記憶體流失的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-425">Addresses an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="b576b-426">解決會導致使用者在指定無效寄件者地址時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-426">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="b576b-427">解決會導致使用者在開啟 [規則] 對話方塊時看到「此電腦上的規則與 Microsoft Exchange 上的規則不相符」提示的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-427">Addresses an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="b576b-428">解決會導致在某些情況下，用來停用標幟項目醒目提示的選項無法使用的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-428">Addresses an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="b576b-429">解決在關閉協助工具檢查程式窗格之後按 S 鍵時，會導致使用者看到郵件非預期傳送的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-429">Addresses an issue that caused users to see mails unexpectedly send when pressing the "S" key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="b576b-430">解決重新命名簽名時，會導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-430">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="b576b-431">解決會導致使用者在取消帳戶設定時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-431">Addresses an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="b576b-432">解決即使將同步處理滑桿設定為較小的設定，也會導致 Outlook 非預期地同步處理所有郵件的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-432">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="b576b-433">解決會導致使用黑色佈景主題的使用者，看到 [寄件者] 下拉式功能表在白色背景上顯示白色文字的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-433">Addresses an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>

- <span data-ttu-id="b576b-434">解決會導致使用者在建立設定檔期間遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-434">Addresses an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="b576b-435">解決會導致使用者在嘗試從 [帳戶建立] 內容連絡支援服務時，看到具有 [確定] 按鈕的空白訊息方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-435">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="b576b-436">解決會導致使用者在嘗試從 [帳戶建立] 內容連絡支援服務時，看到具有 [確定] 按鈕的空白訊息方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-436">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="b576b-437">解決會導致協力廠商應用程式無法傳送電子郵件的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-437">Addresses an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="b576b-438">解決有時候會導致類別從電子郵件訊息中消失的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-438">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="b576b-439">解決會導致伺服器作業系統上的 Outlook 使用者看到「防毒軟體狀態: 無效」的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-439">Addresses an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="b576b-440">此版本的 Windows 支援防毒軟體偵測，但即使已適當設定防毒軟體，也找不到防毒軟體。</span><span class="sxs-lookup"><span data-stu-id="b576b-440">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

- <span data-ttu-id="b576b-441">解決會導致代理人在不同機器上所看到的共用信箱有不同資料夾階層的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-441">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="b576b-442">解決在編輯經理行事曆上的現有行事曆約會時，導致代理人收到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-442">Addresses an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="b576b-443">解決會導致使用不正確瀏覽器模擬設定的使用者，無法完成 Gmail 身分驗證提示的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-443">Addresses an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="b576b-444">解決會導致若「未」核取 [下載共用資料夾]，共用行事曆會議的 [回應選項] 中會遺失 [允許轉寄] 選項的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-444">Addresses an issue that caused the " Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="b576b-445">解決會導致在 Windows 更新之後，使用者嘗試開啟 .msg 和 .oft 檔案時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-445">Addresses an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="b576b-446">解決會導致使用滑鼠上的 X 按鈕時，使用者偶爾遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-446">Addresses an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="b576b-447">解決會導致使用者在選取特定搜尋結果時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-447">Addresses an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="b576b-448">解決會讓 [附件工具] 中的 [儲存至雲端] 按鈕不見的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-448">Addresses an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="b576b-449">此變更可還原在郵件標頭中檢視多行主旨的功能。</span><span class="sxs-lookup"><span data-stu-id="b576b-449">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="b576b-450">解決當兩個增益集將一個按鈕新增到相同功能區群組時，會導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-450">Addresses an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="b576b-451">解決當租用戶預設權限設定為「任何人」時，會導致無法將連結新增至具有正確租用戶預設權限的電子郵件的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-451">Addresses an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as "anyone".</span></span>

- <span data-ttu-id="b576b-452">解決會導致使用者無法將電子郵件傳送到個人通訊群組清單的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-452">Addresses an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="b576b-453">解決在轉寄大型 HTML 郵件時，會導致使用者看到郵件內文截斷的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-453">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="b576b-454">修正 SMIME 演算法選取的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-454">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="b576b-455">我們已修正可能會防止將檔案儲存到 WebDAV 位置的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-455">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="b576b-456">解決選取安全性對話方塊上的 [儲存] 選項時，會導致使用者無法將來自其租用戶外部的 OneDrive 附件儲存至其本機電腦的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-456">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="b576b-457">解決在編輯主旨之後，會導致 NDR 訊息的本文從 Unicode 變更為 ASCII 的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-457">Addresses an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="b576b-458">解決會導致使用者在 Outlook 處理程序中看到記憶體流失的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-458">Addresses an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="b576b-459">解決在某些情況下，導致使用者看到電子郵件傳送到與顯示的 SMTP 位址不相符之地址的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-459">Addresses an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="b576b-460">解決會導致搜尋方塊在高 DPI 模式中對齊不當的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-460">Addresses an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="b576b-461">解決在擷取雲端設定時，會導致使用者在 Outlook 中遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-461">Addresses an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="b576b-462">解決會導致在搜尋意見反應體驗中懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-462">Addresses an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="b576b-463">解決會導致使用者在 Outlook 中偶爾看到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-463">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

- <span data-ttu-id="b576b-464">解決重新命名簽名時，會導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-464">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="b576b-465">解決會導致使用者在建立設定檔期間遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-465">Addresses an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="b576b-466">解決會導致使用者在 Outlook 中偶爾看到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-466">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b576b-467">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b576b-467">PowerPoint</span></span>

- <span data-ttu-id="b576b-468">解決在舊版 PPT 註解中使用操作功能表時，可能會導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-468">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

- <span data-ttu-id="b576b-469">改善複製貼上的案例：將 PowerPoint 投影片中的圖形複製並重複貼到其他投影片中，可能會出現例外狀況而失敗。</span><span class="sxs-lookup"><span data-stu-id="b576b-469">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>

- <span data-ttu-id="b576b-470">修正問題，以在開啟的檔案複本具有改善的註解時，為使用者轉送正確的訊息。</span><span class="sxs-lookup"><span data-stu-id="b576b-470">Fixes an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="project"></a><span data-ttu-id="b576b-471">Project</span><span class="sxs-lookup"><span data-stu-id="b576b-471">Project</span></span>

- <span data-ttu-id="b576b-472">修正無法正確計算摘要工作日期的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-472">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="b576b-473">修正不先執行 OpenUndoTransaction 方法就不能觸發 OnUndoOrRedo 事件的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-473">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="b576b-474">修正透過 [已停用] 按鈕停用/啟動工作時，ProjectBeforeTaskChange 事件無法偵測的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-474">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="b576b-475">修正儲存使用舊版 Project 建立的專案時，Project 可能當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-475">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="b576b-476">發現在開啟唯讀專案時，使用者可能會收到數個訊息的問題</span><span class="sxs-lookup"><span data-stu-id="b576b-476">Identified an issue where users could get several messages when opening a read-only project</span></span>

- <span data-ttu-id="b576b-477">已修正以下問題：固定工期類型的 100% 工作可能會誤將其完成百分比計算為小於 100% 完成。</span><span class="sxs-lookup"><span data-stu-id="b576b-477">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

### <a name="word"></a><span data-ttu-id="b576b-478">Word</span><span class="sxs-lookup"><span data-stu-id="b576b-478">Word</span></span>

- <span data-ttu-id="b576b-479">解決會導致使用滑鼠上的 X 按鈕時，使用者偶爾遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-479">Addresses an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="b576b-480">我們已修正文件中的文字對齊，在使用 [快速列印] 進行列印之後嘗試進行編輯時變得混亂的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-480">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="b576b-481">我們修正了表格中最適文字大小的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-481">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="b576b-482">我們修正了插入水平線無法更短並置中的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-482">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>

- <span data-ttu-id="b576b-483">建置組塊組合管理可能會顯示無效的通知：「您已經修改樣式、建置組塊」。</span><span class="sxs-lookup"><span data-stu-id="b576b-483">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

- <span data-ttu-id="b576b-484">我們已修正啟用原則 FileBlick\Word2007Files 時共同編輯中的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-484">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="b576b-485">我們已修正新增已重新命名之查閱欄位時，Word QuickPart 無法使用的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-485">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

- <span data-ttu-id="b576b-486">我們已修正將兩份文件合併成一份文件時的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-486">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="b576b-487">修正受保護無法編輯之文件的比較功能問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-487">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="b576b-488">此更新解決了 Microsoft Word 中的一個問題：如果標籤原則套用了頁首或頁尾或浮水印，那麼在套用敏感度標籤時，插入長度超過 255 個字元的文字後續將無法透過變更或刪除標籤來識別和刪除。</span><span class="sxs-lookup"><span data-stu-id="b576b-488">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

### <a name="office-suite"></a><span data-ttu-id="b576b-489">Office 套件</span><span class="sxs-lookup"><span data-stu-id="b576b-489">Office Suite</span></span>

- <span data-ttu-id="b576b-490">修正當共同撰寫大型 PowerPoint 檔案時，使用者可能會遇到過度網路和 CPU 使用量的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-490">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="b576b-491">此修正可解決已在用戶端中快取檔案時，Project 應用程式不應封鎖網路的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-491">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>


- <span data-ttu-id="b576b-492">我們將後台中的頻道名稱更新為2020年1月 Fork 的新通道名稱，解決了此問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-492">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="b576b-493">我們已修正此問題，如果裝置受政策管理，將不會調用 DMS 聽眾 API。</span><span class="sxs-lookup"><span data-stu-id="b576b-493">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="b576b-494">我們已解決在單一交易中新增和移除應用程式時，移除不完整的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-494">We have resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="b576b-495">修正相對期限只有在第一次設定時才會有效的 ODT 和 GPO 更新期限設定中的錯誤 (bug)。此修正可啟用後續更新的相關期限。</span><span class="sxs-lookup"><span data-stu-id="b576b-495">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="b576b-496">解決 Office 更新可能會非預期地從 Office CDN 而不是預期使用的來源 (例如本機或網路共用或 Configuration Manager 提供的位置) 下載檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-496">Resolves an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="b576b-497">修正相對期限只有在第一次設定時才會有效的 ODT 和 GPO 更新期限設定中的錯誤 (bug)。此修正可啟用後續更新的相關期限。</span><span class="sxs-lookup"><span data-stu-id="b576b-497">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="b576b-498">我們將新的 AppV51 放置向後移植，以修正先前 AppV51 中的迴歸。</span><span class="sxs-lookup"><span data-stu-id="b576b-498">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="b576b-499">我們已解決內部作業在失敗時擲出例外狀況，而不是記錄和繼續進行的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-499">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="b576b-500">受影響的使用者將不會再無法收到更新。</span><span class="sxs-lookup"><span data-stu-id="b576b-500">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="b576b-501">我們的團隊已在半年企業預覽的 Office CDN 網域中新增報告遙測的用戶端支援。</span><span class="sxs-lookup"><span data-stu-id="b576b-501">Our team has added client support for reporting telemetry on the Office CDN domains in Semi-Annual Enterprise Preview.</span></span>

- <span data-ttu-id="b576b-502">此變更可解決利用 Intel Integrated GPU 的圖形配接卡所報告的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-502">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="b576b-503">這項變更可確保草繪大綱可在功能區中正常運作。</span><span class="sxs-lookup"><span data-stu-id="b576b-503">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="b576b-504">已修正使用一些特定 proxy 設定時，從內部部署位置開啟檔案時發生的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-504">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="b576b-505">此更新修正了 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。</span><span class="sxs-lookup"><span data-stu-id="b576b-505">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="b576b-506">修正問題，可在 Office 遞交工作階段期間消除當機，並改善使用者體驗中的可靠性。</span><span class="sxs-lookup"><span data-stu-id="b576b-506">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>

- <span data-ttu-id="b576b-507">這個錯誤會更新增強的設定服務 (ECS) url 端點。</span><span class="sxs-lookup"><span data-stu-id="b576b-507">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="b576b-508">呼叫這個較新的端點，可從 ECS 進行提取獲得更高的成功率。</span><span class="sxs-lookup"><span data-stu-id="b576b-508">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

- <span data-ttu-id="b576b-509">此更新可修正在檢視或撰寫郵件時，Microsoft Outlook 未顯示目前的敏感度標籤的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-509">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="b576b-510">修正在 Word/Excel/PowerPoint 中開啟來自相同 SharePoint 文件庫的多個文件時，僅掃描開啟的第一個文件是否符合原則的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-510">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

- <span data-ttu-id="b576b-511">為了保護 Office 客戶的安全性，我們現在專門使用 SHA-2 演算法來簽署 Microsoft Office 更新。</span><span class="sxs-lookup"><span data-stu-id="b576b-511">To protect Office customers’ security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

- <span data-ttu-id="b576b-512">在將登錄機碼 HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth 設為零的情況下，啟用增益集時，Windows 中的 Office 當機。</span><span class="sxs-lookup"><span data-stu-id="b576b-512">The office host was crashing in windows, when an add-in is being activated while the registry key  HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="b576b-513">此變更將修正此問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-513">This change would fix this issue.</span></span>

- <span data-ttu-id="b576b-514">解決在登錄 TabProcGrowth 值為 REG_SZ 類型的情況下啟用增益集時，Windows 中的 Office 主機會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-514">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>

- <span data-ttu-id="b576b-515">此更新解決了 Microsoft Office 中的一個問題：可能無法在執行時期正確找到 Visual Basic for Applications 專案，這些專案的參照預期透搜尋 PATH 環境變數指定的位置來找到，進而導致VBA 執行時期錯誤。</span><span class="sxs-lookup"><span data-stu-id="b576b-515">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="b576b-516">解決 Access 和 Publisher 因所安裝的語言而無法正常啟動的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-516">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)





[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-july-14"></a><span data-ttu-id="b576b-519">版本 1908：7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="b576b-519">Version 1908: July 14</span></span>
<span data-ttu-id="b576b-520">*版本 1908 (組建 11929.20904)*</span><span class="sxs-lookup"><span data-stu-id="b576b-520">*Version 1908 (Build 11929.20904)*</span></span>

<span data-ttu-id="b576b-521">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b576b-521">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="b576b-523">解決的問題</span><span class="sxs-lookup"><span data-stu-id="b576b-523">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="b576b-524">Access</span><span class="sxs-lookup"><span data-stu-id="b576b-524">Access</span></span>

- <span data-ttu-id="b576b-525">此更新修正彙總 (例如 Sum) 可能會將結果截斷成整數值的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-525">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="b576b-526">此更新修正包含參照遠端桌面 (例如 SQL Server 桌面) 的聯集查詢可能造成 Access 關閉並重新啟動的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-526">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="b576b-527">此更新可修正 Microsoft Access 中的「更新查詢」執行時或在 SQL 中使用 UPDATE 陳述式時，可能導致錯誤「查詢已損壞」的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-527">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="b576b-528">Excel</span><span class="sxs-lookup"><span data-stu-id="b576b-528">Excel</span></span>

- <span data-ttu-id="b576b-529">文件標題的荷蘭文按鍵提示已變更為 Alt-G。</span><span class="sxs-lookup"><span data-stu-id="b576b-529">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="b576b-530">修正在 Excel 中指派給圖形或表單控制項的巨集可能顯示不正確的錯誤訊息，或者可能會處理不正確目標範圍的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-530">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="b576b-531">解決「尋找及取代」在找到第一個項目後，對話方塊中的焦點位置變更的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-531">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="b576b-532">此更新修正在與其他使用者共同撰寫的工作階段中變更樞紐分析表排序的方式，然後重新整理可能觸發當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-532">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="b576b-533">我們已修正當 OLAP 樞紐分析表的篩選條件設定為已從 cube 移除的值時會發生的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-533">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="b576b-534">此更新已修正使用 VBA 將影像新增到圖表的頁首/頁尾時發生錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-534">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="b576b-535">我們已修正當變更系列集合時，可能會導致散佈折線圖無法正確呈現的問題</span><span class="sxs-lookup"><span data-stu-id="b576b-535">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection</span></span>

- <span data-ttu-id="b576b-536">修正以校正使用圖表範本插入圖表時，預覽中使用的色彩。</span><span class="sxs-lookup"><span data-stu-id="b576b-536">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="b576b-537">已解決當插入或刪除儲存格時，瀑布圖和漏斗圖無法與表格同步處理的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-537">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="b576b-538">修正 Excel 中合併衝突的問題，此問題會造成提示使用者重新開啟活頁簿以取得變更。</span><span class="sxs-lookup"><span data-stu-id="b576b-538">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="b576b-539">已解決造成執行階段錯誤啟動最小化視窗的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-539">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="b576b-540">解決了開啟內嵌活頁簿時，功能區自訂無法載入的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-540">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="b576b-541">已解決導致表格旁的剪下並貼上作業在與其他人共同撰寫時失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-541">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="b576b-542">解決使用執行中巨集變更自訂屬性時，會導致共同撰寫中斷的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-542">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="b576b-543">發生您無法從增益集開啟的 WPF (Windows Presentation Foundation) 表單的下拉式方塊選取項目的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-543">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="b576b-544">解決在未開啟活頁簿時，搜尋最近使用的檔案會造成當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-544">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="b576b-545">修正在預覽列印或列印時，群組方塊控制項的框線無法顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-545">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="b576b-546">修正當活頁簿中有外部連結時，有些使用者可能會遇到多個快顯視窗的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-546">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="b576b-547">已修正使用者在使用 VBA 巨集清除範圍內容時可能遇到的效能問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-547">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="b576b-548">已修正 VBA 將值寫入範圍時，速度比預期慢的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-548">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="b576b-549">解決在儲存並重新開啟檔案時，圖表軸上的「值置於」屬性非預期變更的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-549">Addresses an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="b576b-550">在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。</span><span class="sxs-lookup"><span data-stu-id="b576b-550">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="b576b-551">已修正在刪除包含合併儲存格的資料行時，會導致效能變慢的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-551">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="b576b-552">修正了在 [預覽列印] 中顯示表單控制項時的文字縮放比例問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-552">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="b576b-553">將依色彩篩選的資料複製到具有不同寬度的欄時，值無法貼上。</span><span class="sxs-lookup"><span data-stu-id="b576b-553">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

- <span data-ttu-id="b576b-554">已修正當 Excel 視窗透過 Teams 共用時，使用 Ctrl + Shift + 方向鍵滑動後，Excel 可能會無法回應的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-554">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="b576b-555">已修正列印時表單控制項的核取方塊縮放的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-555">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="b576b-556">修正在相同活頁簿中按一下加入書籤的超連結會導致活頁簿隱藏的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-556">Fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="b576b-557">當您使用舊版的「共用活頁簿」模式，嘗試為活頁簿的新工作表列出變更時，就會發生當機。</span><span class="sxs-lookup"><span data-stu-id="b576b-557">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="b576b-558">[資料剖析] 功能對某些地區設定可能會失敗。</span><span class="sxs-lookup"><span data-stu-id="b576b-558">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="b576b-559">使用者在存取隱藏的命名範圍時可能會遇到錯誤。</span><span class="sxs-lookup"><span data-stu-id="b576b-559">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="b576b-560">使用者在使用某些非英文字元集的情況下，儲存變更時可能會遇到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-560">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="b576b-561">已修正圖表標題中影像檔案大小在儲存包含圖表的活頁簿時增加的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-561">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>

- <span data-ttu-id="b576b-562">非同步使用者定義函數造成的效能問題，導致它們同步執行。</span><span class="sxs-lookup"><span data-stu-id="b576b-562">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="b576b-563">已大幅改善刪除有合併儲存格之欄的效能。</span><span class="sxs-lookup"><span data-stu-id="b576b-563">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="b576b-564">解決捲動後選取儲存格時，可能導致選取錯誤儲存格的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-564">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="b576b-565">已解決 Lookup 函數可能會傳回錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-565">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="b576b-566">已修正以下問題：將選取範圍與交互參照的活頁簿保持同步時，導致交互參照的活頁簿中的 DBCS 字元損毀。</span><span class="sxs-lookup"><span data-stu-id="b576b-566">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="b576b-567">已解決使用自動調整來調整列高時，核取方塊可能收縮的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-567">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>

- <span data-ttu-id="b576b-568">當檔案具備大量設定格式化的條件時，按一下 [字型色彩] 按鈕時出現的效能緩慢問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-568">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="b576b-569">我們已修正預覽列印中的列印範圍不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-569">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="b576b-570">從不受信任的網路共用編輯受保護的檔案時，Excel 可能會發生問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-570">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="b576b-571">我們已大幅提升依色彩篩選的效能。</span><span class="sxs-lookup"><span data-stu-id="b576b-571">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="b576b-572">解決在目前的 Office 版本中開啟在舊版 Office 中建立的活頁簿時，可能導致 Excel 懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-572">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="b576b-573">在增益集管理員中瀏覽時，可顯示 16 個以上的增益集。</span><span class="sxs-lookup"><span data-stu-id="b576b-573">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="b576b-574">解決會防止將超連結貼到一些受保護工作表中的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-574">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="b576b-575">這項變更透過利用軟體轉譯避免特定 Intel 圖形驅動程式發生問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-575">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="b576b-576">來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。</span><span class="sxs-lookup"><span data-stu-id="b576b-576">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="b576b-577">此更新修正 Office 文件無法上傳到商務用 OneDrive 的錯誤 (訊息「上傳失敗」)。</span><span class="sxs-lookup"><span data-stu-id="b576b-577">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="b576b-578">已修正在 Excel 構想功能中，在 Win32 用戶端中按一下 [構想] 按鈕來載入增益集時會發生錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-578">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span> 

### <a name="onenote"></a><span data-ttu-id="b576b-579">OneNote</span><span class="sxs-lookup"><span data-stu-id="b576b-579">OneNote</span></span>

- <span data-ttu-id="b576b-580">對通知進行本地化，讓使用者可以了解更多 OneNote 使用者體驗中正在採取的臨時措施的資訊，以改善同步處理和服務穩定性。</span><span class="sxs-lookup"><span data-stu-id="b576b-580">Localizes the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="b576b-581">Outlook</span><span class="sxs-lookup"><span data-stu-id="b576b-581">Outlook</span></span>

- <span data-ttu-id="b576b-582">來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。</span><span class="sxs-lookup"><span data-stu-id="b576b-582">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="b576b-583">修正使用者將信箱從基本驗證升級為新式驗證後，造成將錯誤的帳戶與其 Outlook 設定檔相關聯的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-583">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="b576b-584">解決會導致網頁增益集在不該存取數位版權管理訊息時進行存取的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-584">Addresses an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="b576b-585">解決會導致部分安全連結無法顯示簡單動態顯示 URL 的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-585">Addresses an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="b576b-586">此這會更新 Outlook 中的附件封鎖邏輯，以同時封鎖 Python 附件。</span><span class="sxs-lookup"><span data-stu-id="b576b-586">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="b576b-587">解決導致部分 POP3 使用者查看所有純文字格式電子郵件 (無論設定) 的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-587">Addresses an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="b576b-588">此修正將會還原 HTML 格式郵件的檢視。</span><span class="sxs-lookup"><span data-stu-id="b576b-588">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="b576b-589">解決在使用者將項目從其主要行事曆複製到群組行事曆時，會導致使用者遇到權限錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-589">Addresses an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="b576b-590">解決會導致使用者無法透過螢幕助讀程式存取位置建議的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-590">Addresses an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="b576b-591">解決當使用者透過鍵盤快速鍵與信箱資料夾互動時，會導致明顯延遲的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-591">Addresses an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="b576b-592">解決會導致非常長時間的 Outlook 工作階段記憶體流失的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-592">Addresses an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="b576b-593">解決會導致使用者在指定無效寄件者地址時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-593">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="b576b-594">解決會導致使用者在開啟 [規則] 對話方塊時看到「此電腦上的規則與 Microsoft Exchange 上的規則不相符」提示的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-594">Addresses an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="b576b-595">解決會導致使用者在與特定安全連結互動時在 Outlook 中遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-595">Addresses an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="b576b-596">解決會導致經理對於代理人是否已經回覆特定會議邀請含混不清的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-596">Addresses an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="b576b-597">解決會導致使用者在處理某些自動探索回應時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-597">Addresses an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="b576b-598">解決會導致使用者在嘗試從 [帳戶建立] 內容連絡支援服務時，看到具有 [確定] 按鈕的空白訊息方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-598">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="b576b-599">此變更可讓系統管理員啟用一個原則，以在自動探索驗證提示中較 UPN 優先使用所提供的帳戶電子郵件。</span><span class="sxs-lookup"><span data-stu-id="b576b-599">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="b576b-600">依預設，自動探索會優先於帳戶 UPN (如果有的話)。</span><span class="sxs-lookup"><span data-stu-id="b576b-600">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="b576b-601">解決會導致使用者看到針對新式群組的搜尋失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-601">Addresses an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="b576b-602">解決會導致 Outlook 使用者在特定案例中停滯在「需要密碼」狀態的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-602">Addresses an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="b576b-603">解決會導致使用者處理衝突郵件時遇到同步失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-603">Addresses an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="b576b-604">解決會導致在套用最新的 Windows 更新之後，使用者開啟 .msg 和 .oft 檔案時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-604">Addresses an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="b576b-605">解決會導致使用者在啟動 Outlook 時，在「正在載入設定檔」畫面遇到停滯的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-605">Addresses an issue that caused users to experience a hang at the "Loading Profile" screen when Outlook is starting up.</span></span>

- <span data-ttu-id="b576b-606">解決會導致使用者在選取特定搜尋結果時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-606">Addresses an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="b576b-607">解決會讓 [附件工具] 中的 [儲存至雲端] 按鈕不見的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-607">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="b576b-608">根據預設，保留原則標籤會將保留時間顯示於括弧中。</span><span class="sxs-lookup"><span data-stu-id="b576b-608">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="b576b-609">此修正提供登錄機碼，讓系統管理員能夠指定只應顯示的原則名稱。</span><span class="sxs-lookup"><span data-stu-id="b576b-609">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="b576b-610">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = 預設值 1 = 我們只會顯示保留原則文字的 PolicyName。</span><span class="sxs-lookup"><span data-stu-id="b576b-610">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = Default 1 = we will only show the PolicyName for Retention policy text.</span></span>

- <span data-ttu-id="b576b-611">解決會導致使用者在關閉 Outlook 時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-611">Addresses an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="b576b-612">解決會導致客戶在某些情況下看到空白會議室清單的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-612">Addresses an issue that caused customers to see an empty room list in some scenarios.</span></span>

- <span data-ttu-id="b576b-613">解決會導致使用者在變更檢視時看到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-613">Addresses an issue that caused users to see intermittent crashes when changing views.</span></span>

- <span data-ttu-id="b576b-614">已解決以下問題：使用者將共用行事曆資料夾同步到 OST 時發生問題，這導致嘗試與這些資料夾互動時發生權限錯誤。</span><span class="sxs-lookup"><span data-stu-id="b576b-614">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>

- <span data-ttu-id="b576b-615">解決會導致使用者在 Citrix 環境中檢視 30 個以上的行事曆時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-615">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="b576b-616">此處是[記錄舊版問題的個別 KB](https://support.microsoft.com/zh-TW/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)</span><span class="sxs-lookup"><span data-stu-id="b576b-616">Here's the individual [KB where this was documented for previous versions](https://support.microsoft.com/zh-TW/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)</span></span>

- <span data-ttu-id="b576b-617">修正 SMIME 演算法選取的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-617">Corrects an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="b576b-618">解決會導致使用其他寄件者時，無法顯示原則提示的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-618">Addresses an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="b576b-619">解決會導致使用者看到在該會議室的可用時間以外進行之會議的會議室建議的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-619">Addresses an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="b576b-620">解決非英文使用者的郵件中，主旨列會相當小的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-620">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="b576b-621">解決會導致使用者嘗試從「未接的交談」訊息建立規則時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-621">Addresses an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="b576b-622">解決會導致某些使用者在新增次要 Exchange 帳戶時看到建立了重複的特殊資料夾的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-622">Addresses an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="b576b-623">解決在轉寄大型 HTML 郵件時，會導致使用者看到郵件內文截斷的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-623">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="b576b-624">解決會導致使用者在 Outlook 處理程序中看到記憶體流失的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-624">Addresses an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="b576b-625">解決會導致使用者在更新目前狀態資訊時遇到間歇性當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-625">Addresses an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="b576b-626">解決會導致目前的資料夾搜尋間歇性失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-626">Addresses an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="b576b-627">解決嘗試擷取使用者的 Outlook 雲端設定時，會導致一些使用者遇到驗證錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-627">Addresses an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="b576b-628">解決會導致在搜尋意見反應體驗中懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-628">Addresses an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="b576b-629">解決會導致使用者在處理某些自動探索回應時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-629">Addresses an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="b576b-630">解決會導致使用者在更新目前狀態資訊時遇到間歇性當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-630">Addresses an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b576b-631">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b576b-631">PowerPoint</span></span>

- <span data-ttu-id="b576b-632">來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。</span><span class="sxs-lookup"><span data-stu-id="b576b-632">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="b576b-633">此變更還原 PowerPoint 影片控制項的協助工具名稱的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-633">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="b576b-634">我們已修正部分動畫無法開始的問題</span><span class="sxs-lookup"><span data-stu-id="b576b-634">We fixed an issue which could prevent some animations from starting</span></span>

- <span data-ttu-id="b576b-635">我們已修正將投影片從一個簡報複製到另一個簡報時可能會造成建立重複母片的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-635">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span><br>

- <span data-ttu-id="b576b-636">改善複製貼上的案例：將 PowerPoint 投影片中的圖形複製並重複貼到其他投影片中，可能會出現例外狀況而失敗。</span><span class="sxs-lookup"><span data-stu-id="b576b-636">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>

- <span data-ttu-id="b576b-637">修正螢光筆的問題：具有深色螢光筆色彩的白色文字，在灰階中會以黑色列印。</span><span class="sxs-lookup"><span data-stu-id="b576b-637">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

- <span data-ttu-id="b576b-638">如果在不支援的版本中開啟含有新的新式註解的檔案，將會顯示黃色警告。</span><span class="sxs-lookup"><span data-stu-id="b576b-638">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

- <span data-ttu-id="b576b-639">修正會導致共同作業使用者之間效能較低的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-639">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="b576b-640">可靠性修正：修正第三方增益集可能會造成 PowerPoint 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-640">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="b576b-641">修正以漸進式開啟檔案時，其包含的投影片若具有多個內嵌媒體串流，可能會發生的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-641">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="b576b-642">我們已修正 Shape.Paste 方法的問題：當使用者使用 Shape.Paste 方法複製並貼上圖形時，它會將選取範圍變更為貼上的圖形。</span><span class="sxs-lookup"><span data-stu-id="b576b-642">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="b576b-643">我們已修正首次啟動 PowerPoint 時，未受信任的增益集可能不會顯示安全性警告訊息列的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-643">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

- <span data-ttu-id="b576b-644">修正某些增益集會對圖表的圖形擲出未預期錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-644">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="b576b-645">避免 PowerPoint 使用者嘗試進行「線上展示」時遇到錯誤。</span><span class="sxs-lookup"><span data-stu-id="b576b-645">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

### <a name="project"></a><span data-ttu-id="b576b-646">Project</span><span class="sxs-lookup"><span data-stu-id="b576b-646">Project</span></span>

- <span data-ttu-id="b576b-647">修正讓 Windows 7 上的使用者能夠從 Project Web App 和 SharePoint 網站開啟專案的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-647">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="b576b-648">發現在開啟唯讀專案時，使用者可能會收到數個訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-648">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="b576b-649">「全部撫平」命令無法正確解決資源過度分派的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-649">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="b576b-650">當您有作業中有零個工作的指派時，可能無法將作業標示為完成且永遠會顯示為 99%。</span><span class="sxs-lookup"><span data-stu-id="b576b-650">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

- <span data-ttu-id="b576b-651">已修正以下問題：由於基準行事曆變更時未更新資源行事曆，而導致時程表和專案計劃之間的實際工作可能不同。</span><span class="sxs-lookup"><span data-stu-id="b576b-651">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="skype"></a><span data-ttu-id="b576b-652">Skype</span><span class="sxs-lookup"><span data-stu-id="b576b-652">Skype</span></span>

- <span data-ttu-id="b576b-653">已修正有多個交談正在進行時的索引標籤式交談標題名稱。</span><span class="sxs-lookup"><span data-stu-id="b576b-653">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="visio"></a><span data-ttu-id="b576b-654">Visio</span><span class="sxs-lookup"><span data-stu-id="b576b-654">Visio</span></span>

- <span data-ttu-id="b576b-655">無法從 Visio 將多個圖形匯出為 SVG。</span><span class="sxs-lookup"><span data-stu-id="b576b-655">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="b576b-656">Word</span><span class="sxs-lookup"><span data-stu-id="b576b-656">Word</span></span>

- <span data-ttu-id="b576b-657">來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。</span><span class="sxs-lookup"><span data-stu-id="b576b-657">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="b576b-658">我們已修正列印到 Deskjet 印表機時，可能會導致縮放問題的問題</span><span class="sxs-lookup"><span data-stu-id="b576b-658">We fixed an issue which could have caused scaling issues when printing to Deskjet printers</span></span>

- <span data-ttu-id="b576b-659">我們已修正表格中「最適文字大小」的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-659">We fixed an issue in Fit Text in Table.</span></span>

- <span data-ttu-id="b576b-660">我們已修正追蹤修訂有時候會進入無限迴圈的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-660">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="b576b-661">我們已修正在某些情況下，儲存現有檔案永遠會導致出現 [另存新檔] 對話方塊且檔案永遠不會儲存的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-661">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="b576b-662">我們已修正將兩份文件合併成一份文件時的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-662">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="b576b-663">修正受保護無法編輯之文件的比較功能問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-663">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="b576b-664">修正應用程式可能在關機時懸置的各種問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-664">Fixes various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="b576b-665">同時修正特定相關增益集當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-665">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="b576b-666">Office 套件</span><span class="sxs-lookup"><span data-stu-id="b576b-666">Office Suite</span></span>

- <span data-ttu-id="b576b-667">已修正不正確地將平假名和漢字中的日本新年號 "Reiwa" (令和) 識別為拼字錯誤或不合文法的運算式的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-667">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="b576b-668">已修正嘗試共用儲存在 SharePoint 2016 上的檔案時，導致使用者遇到「很抱歉，發生問題，無法共用」訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-668">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="b576b-669">已修正在 PowerPoint 共同撰寫和離線編輯的工作階段中可能會導致資料遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-669">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="b576b-670">修正使用者在開啟檔案時可能會遇到的當機問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-670">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="b576b-671">在某些情況下，同步處理引擎備份的 SharePoint 檔案可能會顯示「已儲存」但實際上未儲存任何變更，導致資料遺失。</span><span class="sxs-lookup"><span data-stu-id="b576b-671">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="b576b-672">解決使用者可能無法儲存 Word、Excel 和 PowerPoint 文件的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-672">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="b576b-673">此問題會影響建立新檔案並在按一下 [儲存] 圖示或按 Ctrl + S 之後帶出 [另存成模型對話方塊] 選項的使用者。</span><span class="sxs-lookup"><span data-stu-id="b576b-673">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="b576b-674">從已過時的 API 中移除 Word，以修正其當機問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-674">Fixes a crash in Word by moving away from a deprecated API.</span></span>

- <span data-ttu-id="b576b-675">修正 PowerPoint 中半形片假名字元在垂直文字方塊中無法正確旋轉的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-675">Fixing an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

- <span data-ttu-id="b576b-676">已修正 Win7 的效能問題，其中，於所有應用程式中從功能區插入圖案庫時，大約需要 4 秒鐘的時間才會顯示。</span><span class="sxs-lookup"><span data-stu-id="b576b-676">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="b576b-677">已修正 Backstage 的 [資訊位置] 平板未顯示協助工具資訊的錯誤。</span><span class="sxs-lookup"><span data-stu-id="b576b-677">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="b576b-678">改善有關登錄完整性的 Office 更新程序的可靠性。</span><span class="sxs-lookup"><span data-stu-id="b576b-678">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="b576b-679">我們已將 2019 年 1 月和 7 月分支的通道名稱更新為新通道名稱。</span><span class="sxs-lookup"><span data-stu-id="b576b-679">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>

- <span data-ttu-id="b576b-680">更正可能會在計量網路上非預期封鎖更新的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-680">Corrects an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="b576b-681">修正相對期限只有在第一次設定時才會有效的 ODT 和 GPO 更新期限設定中的錯誤 (bug)。此修正可啟用後續更新的相關期限。</span><span class="sxs-lookup"><span data-stu-id="b576b-681">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="b576b-682">某些情況下，Office 快速鍵可能會在更新後消失。</span><span class="sxs-lookup"><span data-stu-id="b576b-682">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="b576b-683">此更新可改善發佈 Office 快速鍵時的可靠性。</span><span class="sxs-lookup"><span data-stu-id="b576b-683">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="b576b-684">解決 Office 更新可能會非預期地從 Office CDN 而不是預期使用的來源 (例如本機或網路共用或 Configuration Manager 提供的位置) 下載檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-684">Resolves an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="b576b-685">解決在某些情況下，若使用者不是系統管理員且系統帳戶沒有網路連線時，將無法套用更新的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-685">Resolves an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="b576b-686">修正了 Office 更新訊息不以預期語言顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-686">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="b576b-687">自此以後，Office 更新訊息會正確符合 Windows 顯示語言。</span><span class="sxs-lookup"><span data-stu-id="b576b-687">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="b576b-688">下載 Office 更新時透過繼續之前可能已中斷的下載，藉此改善可靠性。</span><span class="sxs-lookup"><span data-stu-id="b576b-688">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="b576b-689">解決第三方外掛程式中與文字方塊/圖案自動調整屬性相關的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-689">Address issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="b576b-690">此變更可解決開啟損毀的檔案之後，正確呈現影像的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-690">This change addresses correctly rendering images after opening a corrupted file.</span></span>

- <span data-ttu-id="b576b-691">此變更可解決轉譯某些含有標記的散佈圖緩慢的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-691">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="b576b-692">我們已修正大型樹狀檢視可能會導致當機的問題</span><span class="sxs-lookup"><span data-stu-id="b576b-692">We fixed an issue where large tree views could result in a crash</span></span>

- <span data-ttu-id="b576b-693">此更新修正了 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。</span><span class="sxs-lookup"><span data-stu-id="b576b-693">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="b576b-694">為了保護 Office 客戶的安全性，我們現在專門使用 SHA-2 演算法來簽署 Microsoft Office 更新。</span><span class="sxs-lookup"><span data-stu-id="b576b-694">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

- <span data-ttu-id="b576b-695">為了保護 Office 客戶的安全性，我們現在專門使用 SHA-2 演算法來簽署 Microsoft Office 更新。</span><span class="sxs-lookup"><span data-stu-id="b576b-695">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-july-14"></a><span data-ttu-id="b576b-697">版本 1902：7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="b576b-697">Version 1902: July 14</span></span>
<span data-ttu-id="b576b-698">*版本 1902 (組建 11328.20624)*</span><span class="sxs-lookup"><span data-stu-id="b576b-698">*Version 1902 (Build 11328.20624)*</span></span>

<span data-ttu-id="b576b-699">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b576b-699">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1908-june-09"></a><span data-ttu-id="b576b-700">版本 1908: 6 月 09日</span><span class="sxs-lookup"><span data-stu-id="b576b-700">Version 1908: June 09</span></span>
<span data-ttu-id="b576b-701">*版本1908（組建11929.20838）*</span><span class="sxs-lookup"><span data-stu-id="b576b-701">*Version 1908 (Build 11929.20838)*</span></span>

<span data-ttu-id="b576b-702">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b576b-702">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="b576b-704">解決的問題</span><span class="sxs-lookup"><span data-stu-id="b576b-704">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b576b-705">Excel</span><span class="sxs-lookup"><span data-stu-id="b576b-705">Excel</span></span>

- <span data-ttu-id="b576b-706">已修正當 Excel 視窗透過 Teams 共用時，使用 Ctrl + Shift + 方向鍵滑動後，Excel 可能會無法回應的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-706">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="b576b-707">已修正列印時表單控制項的核取方塊縮放的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-707">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="b576b-708">當您使用舊版的「共用活頁簿」模式，嘗試為活頁簿的新工作表列出變更時，就會發生當機。</span><span class="sxs-lookup"><span data-stu-id="b576b-708">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="b576b-709">Outlook</span><span class="sxs-lookup"><span data-stu-id="b576b-709">Outlook</span></span>

- <span data-ttu-id="b576b-710">已解決會導致使用者在轉寄大型 HTML 郵件時，看到郵件內文截斷的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-710">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

### <a name="office-suite"></a><span data-ttu-id="b576b-711">Office 套件</span><span class="sxs-lookup"><span data-stu-id="b576b-711">Office Suite</span></span>

- <span data-ttu-id="b576b-712">我們已將 2019 年 1月和7月叉的通道名稱更新為新的通道名稱。</span><span class="sxs-lookup"><span data-stu-id="b576b-712">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-june-09"></a><span data-ttu-id="b576b-714">版本 1902: 6 月 09日</span><span class="sxs-lookup"><span data-stu-id="b576b-714">Version 1902: June 09</span></span>
<span data-ttu-id="b576b-715">*版本 1902 (組建 11328.20602)*</span><span class="sxs-lookup"><span data-stu-id="b576b-715">*Version 1902 (Build 11328.20602)*</span></span>

<span data-ttu-id="b576b-716">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b576b-716">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="b576b-718">解決的問題</span><span class="sxs-lookup"><span data-stu-id="b576b-718">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="b576b-719">Office 套件</span><span class="sxs-lookup"><span data-stu-id="b576b-719">Office Suite</span></span>

- <span data-ttu-id="b576b-720">我們已將 2019 年 1月和7月叉的通道名稱更新為新的通道名稱。</span><span class="sxs-lookup"><span data-stu-id="b576b-720">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>

- <span data-ttu-id="b576b-721">我們從中斷 C2R 組建的基線檔案中移除過時的參照。</span><span class="sxs-lookup"><span data-stu-id="b576b-721">We removed obsolete references from the baseline files that were breaking the C2R Build.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-may-12"></a><span data-ttu-id="b576b-723">版本 1908：5 月 12 日</span><span class="sxs-lookup"><span data-stu-id="b576b-723">Version 1908: May 12</span></span>
<span data-ttu-id="b576b-724">*版本 1908 (組建 11929.20776)*</span><span class="sxs-lookup"><span data-stu-id="b576b-724">*Version 1908 (Build 11929.20776)*</span></span>

<span data-ttu-id="b576b-725">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b576b-725">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="b576b-727">解決的問題</span><span class="sxs-lookup"><span data-stu-id="b576b-727">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b576b-728">Excel</span><span class="sxs-lookup"><span data-stu-id="b576b-728">Excel</span></span>

- <span data-ttu-id="b576b-729">當您將有色彩篩選的資料複製到不同寬度的欄時，不會貼上值。</span><span class="sxs-lookup"><span data-stu-id="b576b-729">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

### <a name="outlook"></a><span data-ttu-id="b576b-730">Outlook</span><span class="sxs-lookup"><span data-stu-id="b576b-730">Outlook</span></span>

- <span data-ttu-id="b576b-731">解決以下問題：使用者在套用最新的 Windows 更新之後，開啟 .msg 和 .oft 檔案發生當機。</span><span class="sxs-lookup"><span data-stu-id="b576b-731">Addressed an issue that caused users to experience a crash when opening msg and .oft files after applying a recent Windows update.</span></span>

### <a name="word"></a><span data-ttu-id="b576b-732">Word</span><span class="sxs-lookup"><span data-stu-id="b576b-732">Word</span></span>

- <span data-ttu-id="b576b-733">我們已修正將2份文件合併成一份文件時的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-733">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="b576b-734">修正受保護無法編輯之文件的比較功能問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-734">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-may-12"></a><span data-ttu-id="b576b-736">版本 1902：5 月 12 日</span><span class="sxs-lookup"><span data-stu-id="b576b-736">Version 1902: May 12</span></span>
<span data-ttu-id="b576b-737">*版本 1902 (組建 11328.20586)*</span><span class="sxs-lookup"><span data-stu-id="b576b-737">*Version 1902 (Build 11328.20586)*</span></span>

<span data-ttu-id="b576b-738">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b576b-738">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="b576b-740">解決的問題</span><span class="sxs-lookup"><span data-stu-id="b576b-740">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b576b-741">Outlook</span><span class="sxs-lookup"><span data-stu-id="b576b-741">Outlook</span></span>

- <span data-ttu-id="b576b-742">解決以下問題：使用者在套用最新的 Windows 更新之後，開啟 .msg 和 .oft 檔案發生當機。</span><span class="sxs-lookup"><span data-stu-id="b576b-742">Addressed an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="b576b-743">根據預設，保留原則標籤會將保留時間顯示於括弧中。</span><span class="sxs-lookup"><span data-stu-id="b576b-743">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="b576b-744">此修正提供登錄機碼，讓系統管理員能夠指定只應顯示的原則名稱。</span><span class="sxs-lookup"><span data-stu-id="b576b-744">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="b576b-745">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration。</span><span class="sxs-lookup"><span data-stu-id="b576b-745">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="b576b-746">0 = 預設值。</span><span class="sxs-lookup"><span data-stu-id="b576b-746">0 = Default.</span></span>  <span data-ttu-id="b576b-747">1 = 我們只會顯示保留原則文字的原則名稱。</span><span class="sxs-lookup"><span data-stu-id="b576b-747">1 = we will only show the PolicyName for Retention policy text.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-may-04"></a><span data-ttu-id="b576b-749">版本 1908：5 月 4 日</span><span class="sxs-lookup"><span data-stu-id="b576b-749">Version 1908: May 04</span></span>
<span data-ttu-id="b576b-750">*版本 1908 (組建 11929.20752)*</span><span class="sxs-lookup"><span data-stu-id="b576b-750">*Version 1908 (Build 11929.20752)*</span></span>

<span data-ttu-id="b576b-751">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b576b-751">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="b576b-752">解決的問題</span><span class="sxs-lookup"><span data-stu-id="b576b-752">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b576b-753">Outlook</span><span class="sxs-lookup"><span data-stu-id="b576b-753">Outlook</span></span>

- <span data-ttu-id="b576b-754">解決了導致使用者在選取特定搜尋結果時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-754">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="b576b-755">解決了會讓 [附件工具] 中的 [儲存至雲端] 按鈕不見的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-755">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="b576b-756">根據預設，保留原則標籤會將保留時間顯示於括弧中。</span><span class="sxs-lookup"><span data-stu-id="b576b-756">By default, retention policy labels display the retention time period in parenthesis.</span></span><span data-ttu-id="b576b-757">此修正提供登錄機碼，讓系統管理員能夠指定只應顯示的原則名稱。</span><span class="sxs-lookup"><span data-stu-id="b576b-757"> This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span><span data-ttu-id="b576b-758">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration。</span><span class="sxs-lookup"><span data-stu-id="b576b-758"> HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span><span data-ttu-id="b576b-759">0 = 預設 1 = 我們只會顯示保留原則文字的原則名稱。</span><span class="sxs-lookup"><span data-stu-id="b576b-759"> 0 = Default 1 = we will only show the PolicyName for Retention policy text.</span></span>

### <a name="office-suite"></a><span data-ttu-id="b576b-760">Office 套件</span><span class="sxs-lookup"><span data-stu-id="b576b-760">Office Suite</span></span>

- <span data-ttu-id="b576b-761">已修正 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。</span><span class="sxs-lookup"><span data-stu-id="b576b-761">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1902-may-04"></a><span data-ttu-id="b576b-762">版本 1902：5 月 4 日</span><span class="sxs-lookup"><span data-stu-id="b576b-762">Version 1902: May 04</span></span>
<span data-ttu-id="b576b-763">*版本 1902 (組建 11328.20572)*</span><span class="sxs-lookup"><span data-stu-id="b576b-763">*Version 1902 (Build 11328.20572)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="b576b-764">解決的問題</span><span class="sxs-lookup"><span data-stu-id="b576b-764">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="b576b-765">Office 套件</span><span class="sxs-lookup"><span data-stu-id="b576b-765">Office Suite</span></span>

- <span data-ttu-id="b576b-766">已修正 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。</span><span class="sxs-lookup"><span data-stu-id="b576b-766">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version1908april-26"></a><span data-ttu-id="b576b-767">版本 1908：4 月 26 日</span><span class="sxs-lookup"><span data-stu-id="b576b-767">Version 1908: April 26</span></span>
<span data-ttu-id="b576b-768">*版本 1908 (組建 11929.20736)*</span><span class="sxs-lookup"><span data-stu-id="b576b-768">*Version 1908 (Build 11929.20736)*</span></span>

<span data-ttu-id="b576b-769">安全性更新列於 [此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b576b-769">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="b576b-770">解決的問題</span><span class="sxs-lookup"><span data-stu-id="b576b-770">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b576b-771">Excel</span><span class="sxs-lookup"><span data-stu-id="b576b-771">Excel</span></span>

- <span data-ttu-id="b576b-772">已修正使用者在使用 VBA 巨集清除範圍內容時可能遇到的效能問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-772">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="b576b-773">已修正 VBA 將值寫入範圍時，速度比預期慢的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-773">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="b576b-774">已解決在儲存並重新開啟檔案時，圖表軸上的 "Value Crosses At" 屬性發生意外變更的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-774">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="b576b-775">在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。</span><span class="sxs-lookup"><span data-stu-id="b576b-775">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>


### <a name="onenote"></a><span data-ttu-id="b576b-776">OneNote</span><span class="sxs-lookup"><span data-stu-id="b576b-776">OneNote</span></span>

- <span data-ttu-id="b576b-777">對通知進行本地化，讓使用者可以了解更多 OneNote 使用者體驗中正在採取的臨時措施的資訊，以改善同步處理和服務穩定性。</span><span class="sxs-lookup"><span data-stu-id="b576b-777">Localizes the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>


## <a name="version-1908-april-14"></a><span data-ttu-id="b576b-778">版本 1908：4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="b576b-778">Version 1908: April 14</span></span>
<span data-ttu-id="b576b-779">*版本 1908 (組建 11929.20708)*</span><span class="sxs-lookup"><span data-stu-id="b576b-779">*Version 1908 (Build 11929.20708)*</span></span>

<span data-ttu-id="b576b-780">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b576b-780">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="b576b-782">解決的問題</span><span class="sxs-lookup"><span data-stu-id="b576b-782">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b576b-783">Excel</span><span class="sxs-lookup"><span data-stu-id="b576b-783">Excel</span></span>

- <span data-ttu-id="b576b-784">已修正在刪除包含合併儲存格的資料行時，會導致效能變慢的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-784">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="b576b-785">修正了在 [預覽列印] 中顯示表單控制項時的文字縮放比例問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-785">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

### <a name="skype"></a><span data-ttu-id="b576b-786">Skype</span><span class="sxs-lookup"><span data-stu-id="b576b-786">Skype</span></span>

- <span data-ttu-id="b576b-787">已修正有多個交談正在進行時的索引標籤式交談標題名稱。</span><span class="sxs-lookup"><span data-stu-id="b576b-787">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="outlook"></a><span data-ttu-id="b576b-788">Outlook</span><span class="sxs-lookup"><span data-stu-id="b576b-788">Outlook</span></span>

- <span data-ttu-id="b576b-789">已解決會導致使用者在關閉 Outlook 時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-789">Addressed an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="b576b-790">已解決會導致客戶在某些情況下看到空白會議室清單的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-790">Addressed an issue that caused customers to see an empty room list in some scenarios.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b576b-791">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b576b-791">PowerPoint</span></span>

- <span data-ttu-id="b576b-792">修正具有深色螢光筆色彩的白色文字，在灰階中會以黑色列印的螢光筆問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-792">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="b576b-793">Word</span><span class="sxs-lookup"><span data-stu-id="b576b-793">Word</span></span>

- <span data-ttu-id="b576b-794">已修正「文字配合資料表」中的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-794">Fixed an issue in Fit Text in Table.</span></span>


## <a name="version-1902-april-14"></a><span data-ttu-id="b576b-795">版本 1902：4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="b576b-795">Version 1902: April 14</span></span>
<span data-ttu-id="b576b-796">*版本 1902 (組建 11328.20564)*</span><span class="sxs-lookup"><span data-stu-id="b576b-796">*Version 1902 (Build 11328.20564)*</span></span>

<span data-ttu-id="b576b-797">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b576b-797">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-march-10"></a><span data-ttu-id="b576b-799">版本 1908：3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="b576b-799">Version 1908: March 10</span></span>
<span data-ttu-id="b576b-800">*版本 1908 (組建 11929.20648)*</span><span class="sxs-lookup"><span data-stu-id="b576b-800">*Version 1908 (Build 11929.20648)*</span></span>

<span data-ttu-id="b576b-801">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b576b-801">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="b576b-803">解決的問題</span><span class="sxs-lookup"><span data-stu-id="b576b-803">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b576b-804">Excel</span><span class="sxs-lookup"><span data-stu-id="b576b-804">Excel</span></span>

- <span data-ttu-id="b576b-805">修正當活頁簿中有外部連結時，有些使用者可能會遇到多個彈出式視窗的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-805">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>


- <span data-ttu-id="b576b-806">[資料剖析] 功能對某些地區設定可能會失敗。</span><span class="sxs-lookup"><span data-stu-id="b576b-806">Text to Column functionality may fail for some locales.</span></span>


- <span data-ttu-id="b576b-807">使用者在存取隱藏的命名範圍時可能會發生錯誤。</span><span class="sxs-lookup"><span data-stu-id="b576b-807">Users may encounter an error when accessing a hidden named range.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="b576b-808">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b576b-808">PowerPoint</span></span>

- <span data-ttu-id="b576b-809">我們已修正 Shape.Paste 方法的問題：當使用者使用 Shape.Paste 方法複製並貼上圖形時，它會將選取範圍變更為貼上的圖形。</span><span class="sxs-lookup"><span data-stu-id="b576b-809">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>


### <a name="word"></a><span data-ttu-id="b576b-810">Word</span><span class="sxs-lookup"><span data-stu-id="b576b-810">Word</span></span>

- <span data-ttu-id="b576b-811">我們已修正在某些情況下，儲存現有檔案永遠會導致出現 [另存新檔] 對話方塊且檔案永遠不會儲存的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-811">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>


### <a name="office-suite"></a><span data-ttu-id="b576b-812">Office 套件</span><span class="sxs-lookup"><span data-stu-id="b576b-812">Office Suite</span></span>

- <span data-ttu-id="b576b-813">此變更可解決轉譯某些含有資料標記的散佈圖緩慢的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-813">This change addresses slow rendering of some scatter charts with markers.</span></span>

## <a name="version-1902-march-10"></a><span data-ttu-id="b576b-814">版本 1902：3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="b576b-814">Version 1902: March 10</span></span>
<span data-ttu-id="b576b-815">*版本 1902 (組建 11328.20554)*</span><span class="sxs-lookup"><span data-stu-id="b576b-815">*Version 1902 (Build 11328.20554)*</span></span>

<span data-ttu-id="b576b-816">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b576b-816">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-february-11"></a><span data-ttu-id="b576b-818">版本 1908：2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="b576b-818">Version 1908: February 11</span></span>
<span data-ttu-id="b576b-819">*版本 1908 (組建 11929.20606)*</span><span class="sxs-lookup"><span data-stu-id="b576b-819">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="b576b-820">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b576b-820">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="b576b-822">解決的問題</span><span class="sxs-lookup"><span data-stu-id="b576b-822">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b576b-823">Excel</span><span class="sxs-lookup"><span data-stu-id="b576b-823">Excel</span></span>

- <span data-ttu-id="b576b-824">此更新已修正使用 VBA 將影像新增到圖表的頁首/頁尾時發生錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-824">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="b576b-825">已修正在預覽列印或列印時群組方塊控制項的框線無法顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-825">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="b576b-826">使用者在使用某些非英文字元集的情況下，儲存變更時可能會遇到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-826">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="b576b-827">已修正圖表標題中影像檔案大小在儲存包含圖表的活頁簿時增加的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-827">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="b576b-828">已修正以下問題：將選取範圍與交互參照的活頁簿保持同步時，導致交互參照的活頁簿中的 DBCS 字元損毀。</span><span class="sxs-lookup"><span data-stu-id="b576b-828">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="b576b-829">已解決使用自動調整來調整列高時，核取方塊可能收縮的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-829">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="b576b-830">Outlook</span><span class="sxs-lookup"><span data-stu-id="b576b-830">Outlook</span></span>

- <span data-ttu-id="b576b-831">已解決導致使用者在指定無效寄件者地址時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-831">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="b576b-832">已解決導致使用者處理衝突郵件時同步失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-832">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="b576b-833">已解決導致使用者在啟動 Outlook 時，「正在載入設定檔」畫面時停滯的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-833">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="b576b-834">已解決導致使用者在變更檢視時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-834">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="b576b-835">已解決在 Citrix 環境中檢視 30 個以上的行事曆時，導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-835">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="b576b-836">[此處](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)是記錄舊版問題的個別 KB。</span><span class="sxs-lookup"><span data-stu-id="b576b-836">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="b576b-837">已解決以下問題：使用者將共用行事曆資料夾同步到 OST 時發生問題，這導致嘗試與這些資料夾互動時發生權限錯誤。</span><span class="sxs-lookup"><span data-stu-id="b576b-837">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="b576b-838">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b576b-838">PowerPoint</span></span>

- <span data-ttu-id="b576b-839">已改善複製貼上的案例，即將 PowerPoint 投影片中的圖形複製並貼到其他投影片可能會因為異常而失敗。</span><span class="sxs-lookup"><span data-stu-id="b576b-839">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="b576b-840">已修正導致共同作業使用者之間效能較低的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-840">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="b576b-841">已修正以下問題：當檔案以漸進式開啟時，若其中一個投影片包含多個內嵌媒體串流可能會發生問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-841">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="b576b-842">已修正以下問題：首次啟動 PowerPoint 時，不受信任的增益集可能不會顯示安全性警告訊息列。</span><span class="sxs-lookup"><span data-stu-id="b576b-842">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="b576b-843">Project</span><span class="sxs-lookup"><span data-stu-id="b576b-843">Project</span></span>

- <span data-ttu-id="b576b-844">已修正以下問題：由於基準行事曆變更時未更新資源行事曆，而導致時程表和專案計劃之間的實際工作可能不同。</span><span class="sxs-lookup"><span data-stu-id="b576b-844">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="b576b-845">Word</span><span class="sxs-lookup"><span data-stu-id="b576b-845">Word</span></span>

- <span data-ttu-id="b576b-846">已從遭取代的 API 移除，以修正 Word 的當機問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-846">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="b576b-847">Office 套件</span><span class="sxs-lookup"><span data-stu-id="b576b-847">Office Suite</span></span>

- <span data-ttu-id="b576b-848">此變更解決開啟損毀的檔案時正確呈現影像的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-848">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-february-11"></a><span data-ttu-id="b576b-850">版本 1902：2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="b576b-850">Version 1902: February 11</span></span>
<span data-ttu-id="b576b-851">*版本 1902 (組建 11328.20526)*</span><span class="sxs-lookup"><span data-stu-id="b576b-851">*Version 1902 (Build 11328.20526)*</span></span>

<span data-ttu-id="b576b-852">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b576b-852">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="b576b-854">解決的問題</span><span class="sxs-lookup"><span data-stu-id="b576b-854">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b576b-855">Outlook</span><span class="sxs-lookup"><span data-stu-id="b576b-855">Outlook</span></span>

- <span data-ttu-id="b576b-856">解決導致使用者在傳送加密電子郵件時遇到「不支援加密演算法」錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-856">Addresses an issue that caused users to encounter encryption algorithm is not supported errors when sending an encrypted email.</span></span>


### <a name="word"></a><span data-ttu-id="b576b-857">Word</span><span class="sxs-lookup"><span data-stu-id="b576b-857">Word</span></span>

- <span data-ttu-id="b576b-858">已從遭取代的 API 移除，以修正 Word 的當機問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-858">Fixed a crash in Word by moving away from a deprecated API.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

## <a name="version-1808-february-11"></a><span data-ttu-id="b576b-861">版本 1808：2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="b576b-861">Version 1808: February 11</span></span>
<span data-ttu-id="b576b-862">*版本 1808 (組建 10730.20438)*</span><span class="sxs-lookup"><span data-stu-id="b576b-862">*Version 1808 (Build 10730.20438)*</span></span>

<span data-ttu-id="b576b-863">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b576b-863">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-january-14"></a><span data-ttu-id="b576b-865">版本 1908：1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="b576b-865">Version 1908: January 14</span></span>
<span data-ttu-id="b576b-866">*版本 1908 (組建 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="b576b-866">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="b576b-867">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b576b-867">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="b576b-869">功能更新</span><span class="sxs-lookup"><span data-stu-id="b576b-869">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="b576b-870">Access</span><span class="sxs-lookup"><span data-stu-id="b576b-870">Access</span></span>

- <span data-ttu-id="b576b-871">**將索引標籤保留在資料庫物件上：** 能清楚看到使用中的索引標籤、輕鬆拖曳索引標籤來重新排列，只要按一下就能關閉資料庫物件。</span><span class="sxs-lookup"><span data-stu-id="b576b-871">**Keep tabs on your database objects:** Clearly see the active tab, easily drag tabs to rearrange them, and close database objects with just one click.</span></span>

- <span data-ttu-id="b576b-872">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="b576b-872">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="b576b-873">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="b576b-873">Switching between them has never been easier.</span></span> [<span data-ttu-id="b576b-874">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-874">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="b576b-875">**使用更大的空間來縮放：** 加大 [縮放] 方塊、變更字型、記憶縮放。</span><span class="sxs-lookup"><span data-stu-id="b576b-875">**Zoom with more room:** Make the Zoom box bigger, change the font, and Zoom remembers it all.</span></span> [<span data-ttu-id="b576b-876">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-876">Learn more</span></span>](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

### <a name="excel"></a><span data-ttu-id="b576b-877">Excel</span><span class="sxs-lookup"><span data-stu-id="b576b-877">Excel</span></span>

- <span data-ttu-id="b576b-878">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="b576b-878">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="b576b-879">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="b576b-879">Switching between them has never been easier.</span></span> [<span data-ttu-id="b576b-880">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-880">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="b576b-881">**增加您內容的覆蓋面：** 想要讓您的簡報更易於使用嗎？</span><span class="sxs-lookup"><span data-stu-id="b576b-881">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="b576b-882">讓協助工具檢查程式來幫助您，您不需要自行處理。</span><span class="sxs-lookup"><span data-stu-id="b576b-882">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="b576b-883">按一下 [校閱] > [檢查協助工具] 試試看這個功能 – 我們會在狀態列上告訴您需要留意的部分。</span><span class="sxs-lookup"><span data-stu-id="b576b-883">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="b576b-884">**快速找到該檔案：** 想要尋找最近使用過的檔案嗎？</span><span class="sxs-lookup"><span data-stu-id="b576b-884">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="b576b-885">只要在 [檔案] > [常用] 頁面的 [搜尋] 方塊中輸入，就能找到所需的檔案。</span><span class="sxs-lookup"><span data-stu-id="b576b-885">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="b576b-886">**觀看工作表生動地呈現：** 插入動畫 3D 圖形，來查看心跳、行星軌道，以及暴龍在工作表內橫衝直撞。</span><span class="sxs-lookup"><span data-stu-id="b576b-886">**Watch your worksheet come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage through the workbook.</span></span> [<span data-ttu-id="b576b-887">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-887">Learn more</span></span>](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- <span data-ttu-id="b576b-p175">**更深入地探索您的資料：** 新的 [構想] 按鈕可尋找資料的模式，並使用模式建立更有智慧且個人化的建議。[深入了解](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span><span class="sxs-lookup"><span data-stu-id="b576b-p175">**Discover more about your data:** The new Ideas button looks for patterns in your data, and uses them to create intelligent, personalized suggestions. [Learn more](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span></span>

- <span data-ttu-id="b576b-890">**共同作業變得更容易：** 共同撰寫的增強功能代表的是使用條件式格式設定、儲存格樣式等等時，您的變更會與共同作業者的變更順暢地合併。</span><span class="sxs-lookup"><span data-stu-id="b576b-890">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>

- <span data-ttu-id="b576b-891">**聯結類似欄位上的表格：** 在比較合併表格的欄位時，取得及轉換 (Power Query) 現在具有近似文字比對邏輯 (也稱為模糊比對)。</span><span class="sxs-lookup"><span data-stu-id="b576b-891">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span> [<span data-ttu-id="b576b-892">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-892">Learn more</span></span>](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- <span data-ttu-id="b576b-893">**使用 Power Query 的增強功能快速撰寫程式碼：** 使用自動完成和語法色彩快速完成程式碼。</span><span class="sxs-lookup"><span data-stu-id="b576b-893">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="b576b-894">同時輕鬆探索函數、資料行和參數。</span><span class="sxs-lookup"><span data-stu-id="b576b-894">Easily discover functions, columns, and parameters, too.</span></span>

- <span data-ttu-id="b576b-895">**搜尋並享受：** 我們新增了 [搜尋以插入] 圖示，讓您輕鬆找到您要的圖示。</span><span class="sxs-lookup"><span data-stu-id="b576b-895">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="b576b-896">而當您選取時，[插入] 按鈕會告知您已經選取的數量。</span><span class="sxs-lookup"><span data-stu-id="b576b-896">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="b576b-897">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-897">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook"></a><span data-ttu-id="b576b-898">Outlook</span><span class="sxs-lookup"><span data-stu-id="b576b-898">Outlook</span></span>

- <span data-ttu-id="b576b-899">**我們已為您更新 Outlook 使用者體驗：** 先前利用「即將推出」提供預覽的簡化體驗，專門設計來幫助您專注於最重要的事物上。</span><span class="sxs-lookup"><span data-stu-id="b576b-899">**We’ve updated the Outlook user experience for you:** A simplified experience, previously available for preview with Coming Soon, designed to help you focus on what matters most.</span></span> [<span data-ttu-id="b576b-900">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-900">Learn more</span></span>](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- <span data-ttu-id="b576b-901">**簡化且也能自訂的功能區：** 輕鬆使用簡化、以單一列方式陳列的常用按鈕。</span><span class="sxs-lookup"><span data-stu-id="b576b-901">**A simplified ribbon that's customizable, too:** Enjoy a streamlined, single row of the most frequently used buttons.</span></span> <span data-ttu-id="b576b-902">輕鬆在傳統與 [簡化] 檢視之間切換，以及釘選/取消釘選命令。</span><span class="sxs-lookup"><span data-stu-id="b576b-902">Easily switch between classic and Simplified views, and pin/unpin commands.</span></span> [<span data-ttu-id="b576b-903">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-903">Learn more</span></span>](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- <span data-ttu-id="b576b-904">**在移動郵件時繼續作業：** Outlook 現在會在背景中移動郵件，因此，在資料夾之間移動大量郵件時您可以繼續作業。</span><span class="sxs-lookup"><span data-stu-id="b576b-904">**Keep working while moving messages:** Outlook now moves messages in the background, so you can keep working while moving lots of messages between folders.</span></span>

- <span data-ttu-id="b576b-905">**在連續會議之間置入時間：** 將會議預設為提早 5-10 分鐘結束，讓出席者有時間休息，或在前往下一個地點。</span><span class="sxs-lookup"><span data-stu-id="b576b-905">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to end 5-10 minutes early by default.</span></span>

- <span data-ttu-id="b576b-906">**挑選您的最愛動作：** 不使用 [標幟] 和 [刪除] 嗎？</span><span class="sxs-lookup"><span data-stu-id="b576b-906">**Pick your favorite action:** Don't use Flag and Delete?</span></span> <span data-ttu-id="b576b-907">那麼 [封存] 或 [標示為已讀取] 呢？</span><span class="sxs-lookup"><span data-stu-id="b576b-907">How about Archive or Mark as Read?</span></span> <span data-ttu-id="b576b-908">自訂快速動作功能表，加上您最常使用的命令。</span><span class="sxs-lookup"><span data-stu-id="b576b-908">Customize the quick action menu with the commands you use most.</span></span>

- <span data-ttu-id="b576b-p182">**他們會看到您的 meme：** 如果使用文字或靜態影像還不足以清楚表達您的想法，您可以使用動畫 GIF。[深入了解](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span><span class="sxs-lookup"><span data-stu-id="b576b-p182">**They'll see what you meme:** When text or static images just won't do, use an animated GIF to make your point. [Learn more](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span></span>

- <span data-ttu-id="b576b-911">**更快速新增帳戶的方式：** 由於帳戶設定已改善，您現在可以更輕鬆地將使用雙因素驗證的 Outlook.com 和 Gmail 帳戶新增到 Outlook。</span><span class="sxs-lookup"><span data-stu-id="b576b-911">**A quicker way to add accounts:** Thanks to account setup improvements, it's easier than ever to add Outlook.com and Gmail accounts that use 2-factor authentication to Outlook.</span></span> [<span data-ttu-id="b576b-912">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-912">Learn more</span></span>](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- <span data-ttu-id="b576b-913">**不再受限於同步處理限制：** Outlook 的增強功能指出資料夾限制已不存在，因此您可以開始將您的共用信箱同步處理。</span><span class="sxs-lookup"><span data-stu-id="b576b-913">**Say goodbye to sync limits:** Outlook improvements mean the folder limit is gone so go ahead and synchronize your shared mailboxes.</span></span>

- <span data-ttu-id="b576b-914">**搜尋並享受：** 我們新增了 [搜尋以插入] 圖示，讓您輕鬆找到您要的圖示。</span><span class="sxs-lookup"><span data-stu-id="b576b-914">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="b576b-915">而當您選取時，[插入] 按鈕會告知您已經選取的數量。</span><span class="sxs-lookup"><span data-stu-id="b576b-915">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="b576b-916">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-916">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint"></a><span data-ttu-id="b576b-917">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b576b-917">PowerPoint</span></span>

- <span data-ttu-id="b576b-918">**較佳變形效果：** 命名您的圖形以便加強掌控其轉化方式。</span><span class="sxs-lookup"><span data-stu-id="b576b-918">**Better shapeshifting:** Name your shapes for more control over how they morph.</span></span> [<span data-ttu-id="b576b-919">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-919">Learn more</span></span>](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- <span data-ttu-id="b576b-920">**快速找到該檔案：** 想要尋找最近使用過的檔案嗎？</span><span class="sxs-lookup"><span data-stu-id="b576b-920">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="b576b-921">只要在 [檔案] > [常用] 頁面的 [搜尋] 方塊中輸入，就能找到所需的檔案。</span><span class="sxs-lookup"><span data-stu-id="b576b-921">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="b576b-922">**增加您內容的覆蓋面：** 想要讓您的簡報更易於使用嗎？</span><span class="sxs-lookup"><span data-stu-id="b576b-922">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="b576b-923">讓協助工具檢查程式來幫助您，您不需要自行處理。</span><span class="sxs-lookup"><span data-stu-id="b576b-923">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="b576b-924">按一下 [校閱] > [檢查協助工具] 試試看這個功能 – 我們會在狀態列上告訴您需要留意的部分。</span><span class="sxs-lookup"><span data-stu-id="b576b-924">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="b576b-925">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="b576b-925">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="b576b-926">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="b576b-926">Switching between them has never been easier.</span></span> [<span data-ttu-id="b576b-927">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-927">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="b576b-928">**線上影片有新的首頁：** 將影片儲存至 Microsoft Stream，讓組織中的任何人都看得到。</span><span class="sxs-lookup"><span data-stu-id="b576b-928">**Online videos have a new home:** Save a video to Microsoft Stream so anyone in your organization can see it.</span></span> <span data-ttu-id="b576b-929">插入影片連結，享受檔案大小只有原來一小部分的多媒體簡報。</span><span class="sxs-lookup"><span data-stu-id="b576b-929">Insert the video link and enjoy a multimedia presentation at a fraction of the file size.</span></span> [<span data-ttu-id="b576b-930">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-930">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="b576b-931">**隨時儲存變更：** 將檔案上傳至 OneDrive，確保所有的更新都會自動儲存。</span><span class="sxs-lookup"><span data-stu-id="b576b-931">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="b576b-p190">**透過測驗或問卷詢問聽眾：** 在投影片上進行測驗或問卷。Office 會收集並儲存存儲您的回應。[深入了解](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span><span class="sxs-lookup"><span data-stu-id="b576b-p190">**Ask your audience with a quiz or survey:** Put a quiz or survey on a slide. Office collects and stores the responses for you. [Learn more](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span></span>

- <span data-ttu-id="b576b-p191">**輕鬆插入內嵌影片：** 想要在您的投影片中放入 Vimeo 或 YouTube 影片嗎？只要有影片頁面連結即可。[深入了解](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span><span class="sxs-lookup"><span data-stu-id="b576b-p191">**Inserting an online video is easier than ever:** Want to put a video from Vimeo or YouTube on your slide? The video page link is all you need. [Learn more](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span></span>

- <span data-ttu-id="b576b-938">**搜尋並享受：** 我們新增了 [搜尋以插入] 圖示，讓您輕鬆找到您要的圖示。</span><span class="sxs-lookup"><span data-stu-id="b576b-938">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="b576b-939">而當您選取時，[插入] 按鈕會告知您已經選取的數量。</span><span class="sxs-lookup"><span data-stu-id="b576b-939">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="b576b-940">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-940">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="project"></a><span data-ttu-id="b576b-941">Project</span><span class="sxs-lookup"><span data-stu-id="b576b-941">Project</span></span>

- <span data-ttu-id="b576b-942">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="b576b-942">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="b576b-943">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="b576b-943">Switching between them has never been easier.</span></span> [<span data-ttu-id="b576b-944">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-944">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a><span data-ttu-id="b576b-945">Visio</span><span class="sxs-lookup"><span data-stu-id="b576b-945">Visio</span></span>

- <span data-ttu-id="b576b-946">**將進度圖表匯出到 Word：** 在 Word 文件中自動新增圖表內容，如圖案和中繼資料。</span><span class="sxs-lookup"><span data-stu-id="b576b-946">**Export process diagrams to Word:** Automatically add diagram content, such as shapes and metadata, to a Word document.</span></span> <span data-ttu-id="b576b-947">然後，自訂文件來建立程序指導方針和操作手冊。</span><span class="sxs-lookup"><span data-stu-id="b576b-947">Then customize the document to create process guidelines and operation manuals.</span></span> [<span data-ttu-id="b576b-948">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-948">Learn more</span></span>](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- <span data-ttu-id="b576b-949">**資料流程圖上的 Double-Take：** 資料視覺化工具流程圖美觀的新版面配置，既清新、簡潔且更易於了解。</span><span class="sxs-lookup"><span data-stu-id="b576b-949">**Double-take on data flowcharts:** Gorgeous new layouts for Data Visualizer flowcharts are clean, crisp, and easy to understand.</span></span> <span data-ttu-id="b576b-950">按一下 [設計] 索引標籤來取得選項。</span><span class="sxs-lookup"><span data-stu-id="b576b-950">Click the Design tab for options.</span></span>

- <span data-ttu-id="b576b-951">**內建的 Azure 樣板：** 使用數十種 Azure 樣板來設計雲端應用程式或規劃架構。</span><span class="sxs-lookup"><span data-stu-id="b576b-951">**Azure stencils built right in:** Design a cloud app or plan an architecture using dozens of Azure stencils.</span></span> [<span data-ttu-id="b576b-952">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-952">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- <span data-ttu-id="b576b-p197">**告別錯誤的 Excel 連結：** 找不到與 Data Visualizer 圖表連結的 Excel 活頁簿嗎？重新連結，就可繼續使用了。[深入了解](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span><span class="sxs-lookup"><span data-stu-id="b576b-p197">**Say goodbye to broken Excel links:** Can't find the Excel workbook linked to your Data Visualizer diagram? Relink it, and you're back in business. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span></span>

- <span data-ttu-id="b576b-956">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="b576b-956">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="b576b-957">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="b576b-957">Switching between them has never been easier.</span></span> [<span data-ttu-id="b576b-958">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-958">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="b576b-959">**從 Power BI 匯出 Visio 視覺效果：** 當匯出 Power BI 報表為 PDF 或 PowerPoint 等檔案時，Power BI Visio 視覺效果會正常顯示。</span><span class="sxs-lookup"><span data-stu-id="b576b-959">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span> [<span data-ttu-id="b576b-960">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-960">Learn more</span></span>](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a><span data-ttu-id="b576b-961">Word</span><span class="sxs-lookup"><span data-stu-id="b576b-961">Word</span></span>

- <span data-ttu-id="b576b-962">**[學習工具] 模式額外支援更多頁面色彩：** Word 中的 [學習工具] 新增更多頁面佈景主題色彩的支援，讓您能夠變更頁面的背景色彩。</span><span class="sxs-lookup"><span data-stu-id="b576b-962">**Learning Tools mode has additional support for more page colors:** Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span> <span data-ttu-id="b576b-963">許多人在背景全白或全黑時閱讀會有困難，因此我們在 PC 和 Mac 的 Word 中增加了色彩選項。</span><span class="sxs-lookup"><span data-stu-id="b576b-963">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

- <span data-ttu-id="b576b-p201">**編輯當然是使用筆跡編輯：** 使用畫筆透過單一筆劃來分割或加入文字、新增新的一行，或插入文字。[深入了解](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span><span class="sxs-lookup"><span data-stu-id="b576b-p201">**Editing comes naturally with Ink Editor:** With a single stroke, split or join words, add a new line, or insert words using your pen. [Learn more](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span></span>

- <span data-ttu-id="b576b-p202">**為靜態文件注入動人的生命力：** 將文件轉變為在任何裝置上，均具有完美外觀的可互動、易分享的網頁。[深入了解](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span><span class="sxs-lookup"><span data-stu-id="b576b-p202">**Take your doc from static to stunning:** Transform your document into an interactive, easy-to-share web page that looks great on any device. [Learn more](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span></span>

- <span data-ttu-id="b576b-968">**增加您內容的覆蓋面：** 想要讓您的文件更易於使用嗎？</span><span class="sxs-lookup"><span data-stu-id="b576b-968">**Increase the reach of your content:** Need to make your documents accessible?</span></span> <span data-ttu-id="b576b-969">讓協助工具檢查程式來幫助您，您不需要自行處理。</span><span class="sxs-lookup"><span data-stu-id="b576b-969">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="b576b-970">按一下 [校閱] > [檢查協助工具] 試試看這個功能 – 我們會在狀態列上告訴您需要留意的部分。</span><span class="sxs-lookup"><span data-stu-id="b576b-970">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="b576b-971">**快速找到該檔案：** 想要尋找最近使用過的檔案嗎？</span><span class="sxs-lookup"><span data-stu-id="b576b-971">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="b576b-972">只要在 [檔案] > [常用] 頁面的 [搜尋] 方塊中輸入，就能找到所需的檔案。</span><span class="sxs-lookup"><span data-stu-id="b576b-972">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="b576b-973">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="b576b-973">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="b576b-974">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="b576b-974">Switching between them has never been easier.</span></span> [<span data-ttu-id="b576b-975">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-975">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="b576b-p206">**運用行聚焦，提高理解力：** 毫不費力地逐行瀏覽文件。調整焦點，在檢視畫面中一次放入一行、三行或五行。[深入了解](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="b576b-p206">**Improve comprehension with Line Focus:** Move through a document line by line without distractions. Adjust the focus to put one, three, or five lines in view at a time. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>

- <span data-ttu-id="b576b-979">**隨時儲存變更：** 將檔案上傳至 OneDrive，確保所有的更新都會自動儲存。</span><span class="sxs-lookup"><span data-stu-id="b576b-979">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="b576b-980">**使用 \@Mentions 提及功能取得他人注意：** 在註解中使用 @mentions 提及功能，讓同事知道您需要他們提供建議。</span><span class="sxs-lookup"><span data-stu-id="b576b-980">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="b576b-981">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-981">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="b576b-982">**搜尋並享受：** 我們新增了 [搜尋以插入] 圖示，讓您輕鬆找到您要的圖示。</span><span class="sxs-lookup"><span data-stu-id="b576b-982">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="b576b-983">而當您選取時，[插入] 按鈕會告知您已經選取的數量。</span><span class="sxs-lookup"><span data-stu-id="b576b-983">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="b576b-984">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-984">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="office-suite"></a><span data-ttu-id="b576b-985">Office 套件</span><span class="sxs-lookup"><span data-stu-id="b576b-985">Office Suite</span></span>

- <span data-ttu-id="b576b-986">**快速找到該檔案：** 想要尋找最近使用過的檔案嗎？</span><span class="sxs-lookup"><span data-stu-id="b576b-986">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="b576b-987">只要在 [檔案] > [開啟] 索引標籤的 [搜尋] 方塊中輸入，就能找到所需的檔案。</span><span class="sxs-lookup"><span data-stu-id="b576b-987">Just type in the Search box on the File > Open tab to find the file you're looking for.</span></span>

- <span data-ttu-id="b576b-988">**隨時儲存變更：** 將檔案上傳至 OneDrive，確保所有的更新都會自動儲存。</span><span class="sxs-lookup"><span data-stu-id="b576b-988">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="b576b-989">**隱私權控制：** 用於診斷資料和連線體驗的新增、更新及改良的控制項。</span><span class="sxs-lookup"><span data-stu-id="b576b-989">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> [<span data-ttu-id="b576b-990">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-990">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

- <span data-ttu-id="b576b-991">**Office 圖示有新的外觀：** Office 圖示經過重新設計，以反映簡單、功能強大且智慧型的 Office 體驗。</span><span class="sxs-lookup"><span data-stu-id="b576b-991">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

- <span data-ttu-id="b576b-992">**安裝 Microsoft Teams：** 在 Office 365 專業增強版的現有安裝中，預設會安裝 Microsoft Teams。</span><span class="sxs-lookup"><span data-stu-id="b576b-992">**Installation of Microsoft Teams:** Microsoft Teams is installed by default for existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="b576b-993">深入了解</span><span class="sxs-lookup"><span data-stu-id="b576b-993">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/teams-install)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="b576b-996">解決的問題</span><span class="sxs-lookup"><span data-stu-id="b576b-996">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="b576b-997">Access</span><span class="sxs-lookup"><span data-stu-id="b576b-997">Access</span></span>

- <span data-ttu-id="b576b-998">此更新修正彙總 (例如 Sum) 可能會將結果截斷成整數值的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-998">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="b576b-999">此更新修正包含參照遠端桌面 (例如 SQL Server 桌面) 的聯集查詢可能造成 Access 關閉並重新啟動的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-999">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="b576b-1000">此更新可修正 Microsoft Access 中的「更新查詢」執行時或在 SQL 中使用 UPDATE 陳述式時，可能導致發生錯誤「查詢已損壞」&quot;&quot;的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1000">This update fixes an issue in Microsoft Access that may cause the error &quot;Query is Corrupt&quot; when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="b576b-1001">Excel</span><span class="sxs-lookup"><span data-stu-id="b576b-1001">Excel</span></span>

- <span data-ttu-id="b576b-1002">文件標題的荷蘭文按鍵提示已變更為 Alt-G。</span><span class="sxs-lookup"><span data-stu-id="b576b-1002">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="b576b-1003">修正在 Excel 中指派給圖形或表單控制項的巨集可能顯示不正確的錯誤訊息，或者可能會處理不正確目標範圍的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1003">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="b576b-1004">解決「尋找及取代」在找到第一個項目後，對話方塊中的焦點位置變更的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1004">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="b576b-1005">此更新修正在與其他使用者共同撰寫的工作階段中變更樞紐分析表排序的方式，然後重新整理可能觸發當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1005">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="b576b-1006">我們已修正當 OLAP 樞紐分析表的篩選條件設定為已從 cube 移除的值時會發生的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1006">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="b576b-1007">修正以校正使用圖表範本插入圖表時，預覽中使用的色彩。</span><span class="sxs-lookup"><span data-stu-id="b576b-1007">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="b576b-1008">我們已修正當變更系列集合時，可能會導致散佈折線圖無法正確呈現的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1008">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span>

- <span data-ttu-id="b576b-1009">已解決當插入或刪除儲存格時，瀑布圖和漏斗圖無法與表格同步處理的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1009">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="b576b-1010">修正 Excel 中合併衝突的問題，此問題會造成提示使用者重新開啟活頁簿以取得變更。</span><span class="sxs-lookup"><span data-stu-id="b576b-1010">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="b576b-1011">解決了開啟內嵌活頁簿時，功能區自訂無法載入的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1011">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="b576b-1012">已解決造成執行階段錯誤啟動最小化視窗的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1012">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="b576b-1013">解決了開啟內嵌活頁簿時，功能區自訂無法載入的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1013">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="b576b-1014">已解決導致表格旁的剪下並貼上作業在與其他人共同撰寫時失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1014">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="b576b-1015">解決使用執行中巨集變更自訂屬性時，會導致共同撰寫中斷的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1015">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="b576b-1016">發生您無法從增益集開啟的 WPF (Windows Presentation Foundation) 表單的下拉式方塊選取項目的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1016">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="b576b-1017">解決在未開啟活頁簿時，搜尋最近使用的檔案會造成當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1017">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="b576b-1018">非同步使用者定義函數造成的效能問題，導致它們同步執行。</span><span class="sxs-lookup"><span data-stu-id="b576b-1018">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="b576b-1019">已大幅改善刪除有合併儲存格之欄的效能。</span><span class="sxs-lookup"><span data-stu-id="b576b-1019">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="b576b-1020">解決捲動後選取儲存格時，可能導致選取錯誤儲存格的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1020">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="b576b-1021">已解決 Lookup 函數可能會傳回錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1021">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="b576b-1022">解決在目前的 Office 版本中開啟在舊版 Office 中建立的活頁簿時，可能導致 Excel 懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1022">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="b576b-1023">當檔案具備大量設定格式化的條件時，按一下 [字型色彩] 按鈕時出現的效能緩慢問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1023">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="b576b-1024">我們已修正預覽列印中的列印範圍不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1024">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="b576b-1025">從不受信任的網路共用編輯受保護的檔案時，Excel 可能會發生問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1025">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="b576b-1026">我們已大幅提升依色彩篩選的效能。</span><span class="sxs-lookup"><span data-stu-id="b576b-1026">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="b576b-1027">已解決會導致將超連結貼到一些受保護工作表中的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1027">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="b576b-1028">當在增益集管理員中瀏覽時，顯示 16 個以上的增益集。</span><span class="sxs-lookup"><span data-stu-id="b576b-1028">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="b576b-1029">這項變更透過利用軟體轉譯避免特定 Intel 圖形驅動程式發生問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1029">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="b576b-1030">來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。</span><span class="sxs-lookup"><span data-stu-id="b576b-1030">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="b576b-1031">此更新修正 Office 文件無法上傳到商務用 OneDrive 的錯誤 (訊息「上傳失敗」)。</span><span class="sxs-lookup"><span data-stu-id="b576b-1031">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="b576b-1032">已修正在 Excel 構想功能中，在 Win32 用戶端中按一下 [構想] 按鈕來載入增益集時會發生錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1032">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span>

### <a name="outlook"></a><span data-ttu-id="b576b-1033">Outlook</span><span class="sxs-lookup"><span data-stu-id="b576b-1033">Outlook</span></span>

- <span data-ttu-id="b576b-1034">來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。</span><span class="sxs-lookup"><span data-stu-id="b576b-1034">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="b576b-1035">修正使用者將信箱從基本驗證升級為新式驗證後，造成將錯誤的帳戶與其 Outlook 設定檔相關聯的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1035">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="b576b-1036">已解決造成網頁增益集在不該存取數位版權管理郵件時進行存取的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1036">Addressed an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="b576b-1037">已解決導致部分安全連結無法顯示簡單動態顯示 URL 的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1037">Addressed an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="b576b-1038">更新 Outlook 中的附件封鎖邏輯，以同時封鎖 python 附件。</span><span class="sxs-lookup"><span data-stu-id="b576b-1038">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="b576b-1039">已解決導致部分 POP3 使用者查看所有純文字格式電子郵件 (無論設定) 的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1039">Addressed an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="b576b-1040">此修正將會還原 HTML 格式郵件的檢視。</span><span class="sxs-lookup"><span data-stu-id="b576b-1040">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="b576b-1041">已解決當使用者將項目從其主要行事曆複製到群組行事曆時，造成使用者遇到權限錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1041">Addressed an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="b576b-1042">已解決導致使用者無法透過螢幕助讀程式存取位置建議的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1042">Addressed an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="b576b-1043">已解決當使用者透過鍵盤快速鍵與信箱資料夾互動時造成明顯延遲的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1043">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="b576b-1044">已解決導致非常長時間的 Outlook 工作階段記憶體流失的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1044">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="b576b-1045">已解決導致使用者在開啟 [規則] 對話方塊時看到「在這部電腦中建立的規則和 Microsoft Exchange 上的規則衝突」提示的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1045">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="b576b-1046">已解決導致使用者在與特定安全連結互動時在 Outlook 中發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1046">Addressed an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="b576b-1047">已解決導致經理對於代理人是否已經回覆特定會議邀請含混不清的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1047">Addressed an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="b576b-1048">已解決導致使用者在處理某些自動探索回應時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1048">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="b576b-1049">已解決導致使用者在嘗試從 [帳戶建立] 內容連絡支援服務時，看到具有 [確定] 按鈕的空白訊息方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1049">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="b576b-1050">此變更可讓系統管理員啟用一個原則，以在自動探索驗證提示中較 UPN 優先使用所提供的帳戶電子郵件。</span><span class="sxs-lookup"><span data-stu-id="b576b-1050">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="b576b-1051">依預設，自動探索會優先於帳戶 UPN (如果有的話)。</span><span class="sxs-lookup"><span data-stu-id="b576b-1051">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="b576b-1052">解決會導致使用者看到針對新式群組的搜尋失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1052">Addressed an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="b576b-1053">已解決導致 Outlook 使用者在特定案例中停滯在「需要密碼」狀態的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1053">Addressed an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="b576b-1054">已解決以下問題：使用者看到某會議室可用時間之外的會議室建議。</span><span class="sxs-lookup"><span data-stu-id="b576b-1054">Addressed an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="b576b-1055">已解決導致使用者在傳送加密電子郵件時遇到「不支援的加密演算法」錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1055">Addressed an issue that caused users to encounter "encryption algorithm is not supported" errors when sending an encrypted email.</span></span>

- <span data-ttu-id="b576b-1056">已解決非英文使用者的郵件中，主旨列會相當小的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1056">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="b576b-1057">已解決導致某些使用者在新增次要 Exchange 帳戶時看到建立了重複特殊資料夾的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1057">Addressed an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="b576b-1058">已解決導致使用者嘗試從「未接的交談」建立規則時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1058">Addressed an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="b576b-1059">已修正 SMIME 演算法選取的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1059">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="b576b-1060">已解決使用其他寄件者時導致無法顯示原則提示的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1060">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="b576b-1061">已解決導致使用者在 Outlook 處理序中看到記憶體洩漏的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1061">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="b576b-1062">已解決導致使用者在更新目前狀態資訊時遇到間歇性當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1062">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="b576b-1063">已解決導致目前的資料夾搜尋間歇性失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1063">Addressed an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="b576b-1064">已解決嘗試擷取使用者的 Outlook 雲端設定時，導致一些使用者遇到驗證錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1064">Addressed an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="b576b-1065">已解決導致在搜尋意見反應體驗中懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1065">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="b576b-1066">已解決導致使用者在處理某些自動探索回應時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1066">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="b576b-1067">已解決導致使用者在更新目前狀態資訊時遇到間歇性當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1067">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b576b-1068">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b576b-1068">PowerPoint</span></span>

- <span data-ttu-id="b576b-1069">修正某些增益集會在圖表的圖形周圍擲出未預期錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1069">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="b576b-1070">來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。</span><span class="sxs-lookup"><span data-stu-id="b576b-1070">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="b576b-1071">此變更還原 PowerPoint 影片控制項的協助工具名稱的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1071">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="b576b-1072">我們已修正部分動畫無法開始的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1072">We fixed an issue which could prevent some animations from starting.</span></span>

- <span data-ttu-id="b576b-1073">我們已修正將投影片從一個簡報複製到另一個簡報時可能會造成母片重複的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1073">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>

- <span data-ttu-id="b576b-1074">如果在不支援的版本中開啟含有新的新式註解的檔案，將會顯示黃色警告</span><span class="sxs-lookup"><span data-stu-id="b576b-1074">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

- <span data-ttu-id="b576b-1075">可靠性修正：已修正第三方增益集可能會造成 PowerPoint 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1075">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="b576b-1076">已修正 PowerPoint 中半形片假名字元在垂直文字方塊中無法正確旋轉的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1076">Fixed an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="b576b-1077">Project</span><span class="sxs-lookup"><span data-stu-id="b576b-1077">Project</span></span>

- <span data-ttu-id="b576b-1078">修正讓 Windows 7 上的使用者能夠從 Project Web App 和 SharePoint 網站開啟專案的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1078">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="b576b-1079">發現在開啟唯讀專案時，使用者可能會收到數個訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1079">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="b576b-1080">「全部撫平」命令無法正確解決資源過度分派的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1080">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="b576b-1081">當您有作業中有零個工作的指派時，可能無法將作業標示為完成且永遠會顯示為 99%。</span><span class="sxs-lookup"><span data-stu-id="b576b-1081">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

### <a name="visio"></a><span data-ttu-id="b576b-1082">Visio</span><span class="sxs-lookup"><span data-stu-id="b576b-1082">Visio</span></span>

- <span data-ttu-id="b576b-1083">無法從 Visio 將多個圖形匯出為 SVG。</span><span class="sxs-lookup"><span data-stu-id="b576b-1083">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="b576b-1084">Word</span><span class="sxs-lookup"><span data-stu-id="b576b-1084">Word</span></span>

- <span data-ttu-id="b576b-1085">此變更能讓使用 Word 開啟文件的效能提升。</span><span class="sxs-lookup"><span data-stu-id="b576b-1085">This change will lead to performance improvements in opening documents using Word.</span></span>

- <span data-ttu-id="b576b-1086">來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。</span><span class="sxs-lookup"><span data-stu-id="b576b-1086">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="b576b-1087">我們已修正當列印到 Deskjet 印表機時，可能會導致縮放比例問題的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1087">We fixed an issue which could have caused scaling issues when printing to Deskjet printers.</span></span>

- <span data-ttu-id="b576b-1088">我們已修正追蹤修訂有時候會進入無限迴圈的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1088">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="b576b-1089">已修正應用程式可能在關機時懸置的各種問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1089">Fixed various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="b576b-1090">同時修正特定相關增益集當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1090">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="b576b-1091">Office 套件</span><span class="sxs-lookup"><span data-stu-id="b576b-1091">Office Suite</span></span>

- <span data-ttu-id="b576b-1092">已修正不正確地將平假名和漢字中的日本新年號 "Reiwa" (令和) 識別為拼字錯誤或不合文法的運算式的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1092">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="b576b-1093">已修正嘗試共用儲存在 SharePoint 2016 上的檔案時，導致使用者遇到「很抱歉，發生問題，無法共用」訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1093">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="b576b-1094">已修正在 PowerPoint 共同撰寫和離線編輯的工作階段中可能會導致資料遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1094">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="b576b-1095">修正使用者在開啟檔案時可能會遇到的當機問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1095">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="b576b-1096">避免 PowerPoint 使用者嘗試進行「線上展示」時遇到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1096">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

- <span data-ttu-id="b576b-1097">在某些情況下，同步處理引擎備份的 SharePoint 檔案可能會顯示「已儲存」但實際上未儲存任何變更，導致資料遺失。</span><span class="sxs-lookup"><span data-stu-id="b576b-1097">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="b576b-1098">解決使用者可能無法儲存 Word、Excel 和 PowerPoint 文件的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1098">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="b576b-1099">此問題會影響建立新檔案並在按一下 [儲存] 圖示或按 Ctrl + S 之後帶出 [另存成模型對話方塊] 選項的使用者。</span><span class="sxs-lookup"><span data-stu-id="b576b-1099">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="b576b-1100">已修正 Win7 的效能問題，其中，於所有應用程式中從功能區插入圖案庫時，大約需要 4 秒鐘的時間才會顯示。</span><span class="sxs-lookup"><span data-stu-id="b576b-1100">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="b576b-1101">已修正 Backstage 的 [資訊位置] 平板未顯示協助工具資訊的錯誤。</span><span class="sxs-lookup"><span data-stu-id="b576b-1101">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="b576b-1102">改善有關登錄完整性的 Office 更新程序的可靠性。</span><span class="sxs-lookup"><span data-stu-id="b576b-1102">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="b576b-1103">解決 Office 更新可能會非預期地從 Office CDN 而不是預期使用的來源 (例如本機或網路共用或 Configuration Manager 提供的位置) 下載檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1103">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="b576b-1104">修正了 Office 更新訊息不以預期語言顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1104">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="b576b-1105">自此以後，Office 更新訊息會正確符合 Windows 顯示語言。</span><span class="sxs-lookup"><span data-stu-id="b576b-1105">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="b576b-1106">已解決在某些情況下，如果使用者不是系統管理員且系統帳戶沒有網路連線，將無法套用更新的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1106">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="b576b-1107">某些情況下，Office 快速鍵可能會在更新後消失。</span><span class="sxs-lookup"><span data-stu-id="b576b-1107">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="b576b-1108">此更新可改善發佈 Office 快速鍵時的可靠性。</span><span class="sxs-lookup"><span data-stu-id="b576b-1108">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="b576b-1109">已更正可能會在計量網路上意外封鎖更新的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1109">Corrected an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="b576b-1110">修正相對期限只有在第一次設定時才會有效的 ODT 和 GPO 更新期限設定中的錯誤 (bug)。此修正可啟用後續更新的相關期限。</span><span class="sxs-lookup"><span data-stu-id="b576b-1110">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="b576b-1111">已改善透過恢復之前可能已中斷的下載，下載 Office 更新時的可靠性。</span><span class="sxs-lookup"><span data-stu-id="b576b-1111">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="b576b-1112">已解決第三方外掛程式中與文字方塊/圖案自動調整屬性相關的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1112">Addressed issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="b576b-1113">我們已修正大型樹狀檢視可能會導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1113">We fixed an issue where large tree views could result in a crash.</span></span>

- <span data-ttu-id="b576b-1114">為了保護 Office 客戶的安全性，我們現在專門使用 SHA-2 演算法來簽署 Microsoft Office 更新。</span><span class="sxs-lookup"><span data-stu-id="b576b-1114">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-january-14"></a><span data-ttu-id="b576b-1116">版本 1902：1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="b576b-1116">Version 1902: January 14</span></span>
<span data-ttu-id="b576b-1117">*版本 1902 (組建 11328.20512)*</span><span class="sxs-lookup"><span data-stu-id="b576b-1117">*Version 1902 (Build 11328.20512)*</span></span>

<span data-ttu-id="b576b-1118">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b576b-1118">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="b576b-1120">解決的問題</span><span class="sxs-lookup"><span data-stu-id="b576b-1120">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b576b-1121">Excel</span><span class="sxs-lookup"><span data-stu-id="b576b-1121">Excel</span></span>

- <span data-ttu-id="b576b-1122">解決了開啟內嵌活頁簿時，功能區自訂無法載入的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1122">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="b576b-1123">Outlook</span><span class="sxs-lookup"><span data-stu-id="b576b-1123">Outlook</span></span>

- <span data-ttu-id="b576b-1124">解決導致使用者在傳送加密電子郵件時遇到「不支援的加密演算法」錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="b576b-1124">Addresses an issue that caused users to encounter "encryption algorithm is not supporte" errors when sending an encrypted email.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b576b-1125">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b576b-1125">PowerPoint</span></span>

- <span data-ttu-id="b576b-1126">如果在不支援的版本中開啟含有新的新式註解的檔案，將會顯示黃色警告。</span><span class="sxs-lookup"><span data-stu-id="b576b-1126">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

### <a name="word"></a><span data-ttu-id="b576b-1127">Word</span><span class="sxs-lookup"><span data-stu-id="b576b-1127">Word</span></span>

- <span data-ttu-id="b576b-1128">此變更能讓使用 Word 開啟文件的效能提升。</span><span class="sxs-lookup"><span data-stu-id="b576b-1128">This change will lead to performance improvements in opening documents using Word.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1808-january-14"></a><span data-ttu-id="b576b-1130">版本 1808：1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="b576b-1130">Version 1808: January 14</span></span>
<span data-ttu-id="b576b-1131">*版本 1808 (組建 10730.20432)*</span><span class="sxs-lookup"><span data-stu-id="b576b-1131">*Version 1808 (Build 10730.20432)*</span></span>

<span data-ttu-id="b576b-1132">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b576b-1132">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

> [!NOTE]
> <span data-ttu-id="b576b-1134">如果您需要關於使用 Office 的問題協助，建議您將問題張貼在 [Microsoft Answers 論壇](https://answers.microsoft.com/)或[技術社群](https://techcommunity.microsoft.com/)，或連絡[支援](https://support.microsoft.com/contactus)。</span><span class="sxs-lookup"><span data-stu-id="b576b-1134">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (DO NOT MODIFY ADMIN CENTER METADATA CONTENT START)
[//]: # (|Win32|DC|Production| |16.0.12527.21236|version-2002-october-13|)
[//]: # (|Win32|DC|Production| |16.0.12527.21104|version-2002-september-08|)
[//]: # (|Win32|DC|Production||16.0.12527.20988|version-2002-august-11|)
[//]: # (|Win32|DC|Production| |16.0.12527.20880|version-2002-july-14|)
[//]: # (DO NOT MODIFY ADMIN CENTER METADATA CONTENT END)
