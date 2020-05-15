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
description: 為 IT 專業人員提供 2020 年 Microsoft 365 Apps 半年通道版本的版本資訊
ms.openlocfilehash: 6619411170491543c4853e6db56fa845a7adc6e3
ms.sourcegitcommit: fb97680a81c7d96b0f0f539dc3e3c8c28ad654e9
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/13/2020
ms.locfileid: "44222076"
---
# <a name="release-notes-for-semi-annual-channel-releases-in-2020"></a><span data-ttu-id="52bfe-103">2020 年半年通道版本的版本資訊</span><span class="sxs-lookup"><span data-stu-id="52bfe-103">Release notes for Semi-Annual Channel releases in 2020</span></span>

<span data-ttu-id="52bfe-104">這些版本資訊提供新功能和非安全性更新的相關資訊，這些功能和非安全性更新包含在 2020 年 Microsoft 365 Apps 企業版、Microsoft 365 Apps 商務版，以及 Project 和 Visio 版的傳統型應用程式訂閱版本的半年通道更新。</span><span class="sxs-lookup"><span data-stu-id="52bfe-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Channel updates in 2020 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="52bfe-105">我們會變更 Microsoft 365 應用程式的更新通道，包括新增新的更新通道 (每月企業通道)，並變更現有的更新通道名稱。</span><span class="sxs-lookup"><span data-stu-id="52bfe-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="52bfe-106">如需深入了解，[請閱讀本文](https://go.microsoft.com/fwlink/p/?linkid=2127441)。</span><span class="sxs-lookup"><span data-stu-id="52bfe-106">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
>
>- <span data-ttu-id="52bfe-107">當使用半年通道的使用者透過 Office 入口網站下載並安裝 Microsoft 365 Apps 到 Windows 10 上時，OneNote 2016 依預設將包括在其中。</span><span class="sxs-lookup"><span data-stu-id="52bfe-107">OneNote 2016 will now be included by default when a user on the Semi-Annual Channel downloads and installs Microsoft 365 Apps on Windows 10 from the Office Portal.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-may-12"></a><span data-ttu-id="52bfe-109">版本 1908：5 月 12 日</span><span class="sxs-lookup"><span data-stu-id="52bfe-109">Version 1908: May 12</span></span>
<span data-ttu-id="52bfe-110">*版本 1908 (組建 11929.20776)*</span><span class="sxs-lookup"><span data-stu-id="52bfe-110">*Version 1908 (Build 11929.20776)*</span></span>

<span data-ttu-id="52bfe-111">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="52bfe-111">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="52bfe-113">解決的問題</span><span class="sxs-lookup"><span data-stu-id="52bfe-113">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="52bfe-114">Excel</span><span class="sxs-lookup"><span data-stu-id="52bfe-114">Excel</span></span>

- <span data-ttu-id="52bfe-115">當您將有色彩篩選的資料複製到不同寬度的欄時，不會貼上值。</span><span class="sxs-lookup"><span data-stu-id="52bfe-115">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

- <span data-ttu-id="52bfe-116">已修正使用者在使用 VBA 巨集清除範圍內容時可能遇到的效能問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-116">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="52bfe-117">已修正 VBA 將值寫入範圍時，速度比預期慢的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-117">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="52bfe-118">已解決在儲存並重新開啟檔案時，圖表軸上的 "Value Crosses At" 屬性發生意外變更的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-118">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="52bfe-119">在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。</span><span class="sxs-lookup"><span data-stu-id="52bfe-119">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

### <a name="onenote"></a><span data-ttu-id="52bfe-120">OneNote</span><span class="sxs-lookup"><span data-stu-id="52bfe-120">OneNote</span></span>

- <span data-ttu-id="52bfe-121">對通知進行本地化，讓使用者可以了解更多 OneNote 使用者體驗中正在採取的臨時措施的資訊，以改善同步處理和服務穩定性。</span><span class="sxs-lookup"><span data-stu-id="52bfe-121">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="52bfe-122">Outlook</span><span class="sxs-lookup"><span data-stu-id="52bfe-122">Outlook</span></span>

- <span data-ttu-id="52bfe-123">解決以下問題：使用者在套用最新的 Windows 更新之後，開啟 .msg 和 .oft 檔案發生當機。</span><span class="sxs-lookup"><span data-stu-id="52bfe-123">Addressed an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="52bfe-124">已解決導致使用者在選取特定搜尋結果時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-124">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="52bfe-125">已解決導致 [附件工具] 中的 [儲存至雲端] 按鈕遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-125">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="52bfe-126">根據預設，保留原則標籤會將保留時間顯示於括弧中。</span><span class="sxs-lookup"><span data-stu-id="52bfe-126">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="52bfe-127">此修正提供登錄機碼，讓系統管理員能夠指定只應顯示的原則名稱。</span><span class="sxs-lookup"><span data-stu-id="52bfe-127">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="52bfe-128">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration。</span><span class="sxs-lookup"><span data-stu-id="52bfe-128">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="52bfe-129">0 = 預設值。</span><span class="sxs-lookup"><span data-stu-id="52bfe-129">0 = Default.</span></span>  <span data-ttu-id="52bfe-130">1 = 我們只會顯示保留原則文字的原則名稱。</span><span class="sxs-lookup"><span data-stu-id="52bfe-130">1 = we will only show the PolicyName for Retention policy text.</span></span>


### <a name="word"></a><span data-ttu-id="52bfe-131">Word</span><span class="sxs-lookup"><span data-stu-id="52bfe-131">Word</span></span>

- <span data-ttu-id="52bfe-132">我們已修正將兩份文件合併成一份文件時的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-132">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="52bfe-133">修正受保護無法編輯之文件的比較功能問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-133">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-may-12"></a><span data-ttu-id="52bfe-135">版本 1902：5 月 12 日</span><span class="sxs-lookup"><span data-stu-id="52bfe-135">Version 1902: May 12</span></span>
<span data-ttu-id="52bfe-136">*版本 1902 (組建 11328.20586)*</span><span class="sxs-lookup"><span data-stu-id="52bfe-136">*Version 1902 (Build 11328.20586)*</span></span>

<span data-ttu-id="52bfe-137">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="52bfe-137">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="52bfe-139">解決的問題</span><span class="sxs-lookup"><span data-stu-id="52bfe-139">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="52bfe-140">Outlook</span><span class="sxs-lookup"><span data-stu-id="52bfe-140">Outlook</span></span>

- <span data-ttu-id="52bfe-141">解決以下問題：使用者在套用最新的 Windows 更新之後，開啟 .msg 和 .oft 檔案發生當機。</span><span class="sxs-lookup"><span data-stu-id="52bfe-141">Addressed an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="52bfe-142">根據預設，保留原則標籤會將保留時間顯示於括弧中。</span><span class="sxs-lookup"><span data-stu-id="52bfe-142">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="52bfe-143">此修正提供登錄機碼，讓系統管理員能夠指定只應顯示的原則名稱。</span><span class="sxs-lookup"><span data-stu-id="52bfe-143">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="52bfe-144">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration。</span><span class="sxs-lookup"><span data-stu-id="52bfe-144">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="52bfe-145">0 = 預設值。</span><span class="sxs-lookup"><span data-stu-id="52bfe-145">0 = Default.</span></span>  <span data-ttu-id="52bfe-146">1 = 我們只會顯示保留原則文字的原則名稱。</span><span class="sxs-lookup"><span data-stu-id="52bfe-146">1 = we will only show the PolicyName for Retention policy text.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-may-04"></a><span data-ttu-id="52bfe-148">版本 1908：5 月 4 日</span><span class="sxs-lookup"><span data-stu-id="52bfe-148">Version 1908: May 04</span></span>
<span data-ttu-id="52bfe-149">*版本 1908 (組建 11929.20752)*</span><span class="sxs-lookup"><span data-stu-id="52bfe-149">*Version 1908 (Build 11929.20752)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="52bfe-150">解決的問題</span><span class="sxs-lookup"><span data-stu-id="52bfe-150">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="52bfe-151">Office 套件</span><span class="sxs-lookup"><span data-stu-id="52bfe-151">Office Suite</span></span>

- <span data-ttu-id="52bfe-152">已修正 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。</span><span class="sxs-lookup"><span data-stu-id="52bfe-152">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1902-may-04"></a><span data-ttu-id="52bfe-153">版本 1902：5 月 4 日</span><span class="sxs-lookup"><span data-stu-id="52bfe-153">Version 1902: May 04</span></span>
<span data-ttu-id="52bfe-154">*版本 1902 (組建 11328.20572)*</span><span class="sxs-lookup"><span data-stu-id="52bfe-154">*Version 1902 (Build 11328.20572)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="52bfe-155">解決的問題</span><span class="sxs-lookup"><span data-stu-id="52bfe-155">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="52bfe-156">Office 套件</span><span class="sxs-lookup"><span data-stu-id="52bfe-156">Office Suite</span></span>

- <span data-ttu-id="52bfe-157">已修正 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。</span><span class="sxs-lookup"><span data-stu-id="52bfe-157">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1908-april-14"></a><span data-ttu-id="52bfe-158">版本 1908：4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="52bfe-158">Version 1908: April 14</span></span>
<span data-ttu-id="52bfe-159">*版本 1908 (組建 11929.20708)*</span><span class="sxs-lookup"><span data-stu-id="52bfe-159">*Version 1908 (Build 11929.20708)*</span></span>

<span data-ttu-id="52bfe-160">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="52bfe-160">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="52bfe-162">解決的問題</span><span class="sxs-lookup"><span data-stu-id="52bfe-162">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="52bfe-163">Excel</span><span class="sxs-lookup"><span data-stu-id="52bfe-163">Excel</span></span>

- <span data-ttu-id="52bfe-164">已修正在刪除包含合併儲存格的資料行時，會導致效能變慢的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-164">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="52bfe-165">修正了在 [預覽列印] 中顯示表單控制項時的文字縮放比例問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-165">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

### <a name="skype"></a><span data-ttu-id="52bfe-166">Skype</span><span class="sxs-lookup"><span data-stu-id="52bfe-166">Skype</span></span>

- <span data-ttu-id="52bfe-167">已修正有多個交談正在進行時的索引標籤式交談標題名稱。</span><span class="sxs-lookup"><span data-stu-id="52bfe-167">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="outlook"></a><span data-ttu-id="52bfe-168">Outlook</span><span class="sxs-lookup"><span data-stu-id="52bfe-168">Outlook</span></span>

- <span data-ttu-id="52bfe-169">已解決會導致使用者在關閉 Outlook 時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-169">Addressed an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="52bfe-170">已解決會導致客戶在某些情況下看到空白會議室清單的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-170">Addressed an issue that caused customers to see an empty room list in some scenarios.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="52bfe-171">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="52bfe-171">PowerPoint</span></span>

- <span data-ttu-id="52bfe-172">修正具有深色螢光筆色彩的白色文字，在灰階中會以黑色列印的螢光筆問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-172">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="52bfe-173">Word</span><span class="sxs-lookup"><span data-stu-id="52bfe-173">Word</span></span>

- <span data-ttu-id="52bfe-174">已修正「文字配合資料表」中的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-174">Fixed an issue in Fit Text in Table.</span></span>


## <a name="version-1902-april-14"></a><span data-ttu-id="52bfe-175">版本 1902：4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="52bfe-175">Version 1902: April 14</span></span>
<span data-ttu-id="52bfe-176">*版本 1902 (組建 11328.20564)*</span><span class="sxs-lookup"><span data-stu-id="52bfe-176">*Version 1902 (Build 11328.20564)*</span></span>

<span data-ttu-id="52bfe-177">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="52bfe-177">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-march-10"></a><span data-ttu-id="52bfe-179">版本 1908：3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="52bfe-179">Version 1908: March 10</span></span>
<span data-ttu-id="52bfe-180">*版本 1908 (組建 11929.20648)*</span><span class="sxs-lookup"><span data-stu-id="52bfe-180">*Version 1908 (Build 11929.20648)*</span></span>

<span data-ttu-id="52bfe-181">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="52bfe-181">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="52bfe-183">解決的問題</span><span class="sxs-lookup"><span data-stu-id="52bfe-183">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="52bfe-184">Excel</span><span class="sxs-lookup"><span data-stu-id="52bfe-184">Excel</span></span>

- <span data-ttu-id="52bfe-185">修正當活頁簿中有外部連結時，有些使用者可能會遇到多個彈出式視窗的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-185">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>


- <span data-ttu-id="52bfe-186">[資料剖析] 功能對某些地區設定可能會失敗。</span><span class="sxs-lookup"><span data-stu-id="52bfe-186">Text to Column functionality may fail for some locales.</span></span>


- <span data-ttu-id="52bfe-187">使用者在存取隱藏的命名範圍時可能會發生錯誤。</span><span class="sxs-lookup"><span data-stu-id="52bfe-187">Users may encounter an error when accessing a hidden named range.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="52bfe-188">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="52bfe-188">PowerPoint</span></span>

- <span data-ttu-id="52bfe-189">我們已修正 Shape.Paste 方法的問題：當使用者使用 Shape.Paste 方法複製並貼上圖形時，它會將選取範圍變更為貼上的圖形。</span><span class="sxs-lookup"><span data-stu-id="52bfe-189">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>


### <a name="word"></a><span data-ttu-id="52bfe-190">Word</span><span class="sxs-lookup"><span data-stu-id="52bfe-190">Word</span></span>

- <span data-ttu-id="52bfe-191">我們已修正在某些情況下，儲存現有檔案永遠會導致出現 [另存新檔] 對話方塊且檔案永遠不會儲存的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-191">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>


### <a name="office-suite"></a><span data-ttu-id="52bfe-192">Office 套件</span><span class="sxs-lookup"><span data-stu-id="52bfe-192">Office Suite</span></span>

- <span data-ttu-id="52bfe-193">此變更可解決轉譯某些含有資料標記的散佈圖緩慢的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-193">This change addresses slow rendering of some scatter charts with markers.</span></span>

## <a name="version-1902-march-10"></a><span data-ttu-id="52bfe-194">版本 1902：3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="52bfe-194">Version 1902: March 10</span></span>
<span data-ttu-id="52bfe-195">*版本 1902 (組建 11328.20554)*</span><span class="sxs-lookup"><span data-stu-id="52bfe-195">*Version 1902 (Build 11328.20554)*</span></span>

<span data-ttu-id="52bfe-196">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="52bfe-196">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-february-11"></a><span data-ttu-id="52bfe-198">版本 1908：2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="52bfe-198">Version 1908: February 11</span></span>
<span data-ttu-id="52bfe-199">*版本 1908 (組建 11929.20606)*</span><span class="sxs-lookup"><span data-stu-id="52bfe-199">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="52bfe-200">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="52bfe-200">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="52bfe-202">解決的問題</span><span class="sxs-lookup"><span data-stu-id="52bfe-202">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="52bfe-203">Excel</span><span class="sxs-lookup"><span data-stu-id="52bfe-203">Excel</span></span>

- <span data-ttu-id="52bfe-204">此更新已修正使用 VBA 將影像新增到圖表的頁首/頁尾時發生錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-204">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="52bfe-205">已修正在預覽列印或列印時群組方塊控制項的框線無法顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-205">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="52bfe-206">使用者在使用某些非英文字元集的情況下，儲存變更時可能會遇到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-206">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="52bfe-207">已修正圖表標題中影像檔案大小在儲存包含圖表的活頁簿時增加的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-207">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="52bfe-208">已修正以下問題：將選取範圍與交互參照的活頁簿保持同步時，導致交互參照的活頁簿中的 DBCS 字元損毀。</span><span class="sxs-lookup"><span data-stu-id="52bfe-208">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="52bfe-209">已解決使用自動調整來調整列高時，核取方塊可能收縮的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-209">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="52bfe-210">Outlook</span><span class="sxs-lookup"><span data-stu-id="52bfe-210">Outlook</span></span>

- <span data-ttu-id="52bfe-211">已解決導致使用者在指定無效寄件者地址時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-211">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="52bfe-212">已解決導致使用者處理衝突郵件時同步失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-212">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="52bfe-213">已解決導致使用者在啟動 Outlook 時，「正在載入設定檔」畫面時停滯的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-213">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="52bfe-214">已解決導致使用者在變更檢視時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-214">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="52bfe-215">已解決在 Citrix 環境中檢視 30 個以上的行事曆時，導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-215">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="52bfe-216">[此處](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)是記錄舊版問題的個別 KB。</span><span class="sxs-lookup"><span data-stu-id="52bfe-216">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="52bfe-217">已解決以下問題：使用者將共用行事曆資料夾同步到 OST 時發生問題，這導致嘗試與這些資料夾互動時發生權限錯誤。</span><span class="sxs-lookup"><span data-stu-id="52bfe-217">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="52bfe-218">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="52bfe-218">PowerPoint</span></span>

- <span data-ttu-id="52bfe-219">已改善複製貼上的案例，即將 PowerPoint 投影片中的圖形複製並貼到其他投影片可能會因為異常而失敗。</span><span class="sxs-lookup"><span data-stu-id="52bfe-219">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="52bfe-220">已修正導致共同作業使用者之間效能較低的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-220">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="52bfe-221">已修正以下問題：當檔案以漸進式開啟時，若其中一個投影片包含多個內嵌媒體串流可能會發生問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-221">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="52bfe-222">已修正以下問題：首次啟動 PowerPoint 時，不受信任的增益集可能不會顯示安全性警告訊息列。</span><span class="sxs-lookup"><span data-stu-id="52bfe-222">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="52bfe-223">Project</span><span class="sxs-lookup"><span data-stu-id="52bfe-223">Project</span></span>

- <span data-ttu-id="52bfe-224">已修正以下問題：由於基準行事曆變更時未更新資源行事曆，而導致時程表和專案計劃之間的實際工作可能不同。</span><span class="sxs-lookup"><span data-stu-id="52bfe-224">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="52bfe-225">Word</span><span class="sxs-lookup"><span data-stu-id="52bfe-225">Word</span></span>

- <span data-ttu-id="52bfe-226">已從遭取代的 API 移除，以修正 Word 的當機問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-226">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="52bfe-227">Office 套件</span><span class="sxs-lookup"><span data-stu-id="52bfe-227">Office Suite</span></span>

- <span data-ttu-id="52bfe-228">此變更解決開啟損毀的檔案時正確呈現影像的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-228">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-february-11"></a><span data-ttu-id="52bfe-230">版本 1902：2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="52bfe-230">Version 1902: February 11</span></span>
<span data-ttu-id="52bfe-231">*版本 1902 (組建 11328.20526)*</span><span class="sxs-lookup"><span data-stu-id="52bfe-231">*Version 1902 (Build 11328.20526)*</span></span>

<span data-ttu-id="52bfe-232">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="52bfe-232">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="52bfe-234">解決的問題</span><span class="sxs-lookup"><span data-stu-id="52bfe-234">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="52bfe-235">Outlook</span><span class="sxs-lookup"><span data-stu-id="52bfe-235">Outlook</span></span>

- <span data-ttu-id="52bfe-236">解決導致使用者在傳送加密電子郵件時遇到「不支援加密演算法」錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-236">Addresses an issue that caused users to encounter encryption algorithm is not supported errors when sending an encrypted email.</span></span>


### <a name="word"></a><span data-ttu-id="52bfe-237">Word</span><span class="sxs-lookup"><span data-stu-id="52bfe-237">Word</span></span>

- <span data-ttu-id="52bfe-238">已從遭取代的 API 移除，以修正 Word 的當機問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-238">Fixed a crash in Word by moving away from a deprecated API.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

## <a name="version-1808-february-11"></a><span data-ttu-id="52bfe-241">版本 1808：2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="52bfe-241">Version 1808: February 11</span></span>
<span data-ttu-id="52bfe-242">*版本 1808 (組建 10730.20438)*</span><span class="sxs-lookup"><span data-stu-id="52bfe-242">*Version 1808 (Build 10730.20438)*</span></span>

<span data-ttu-id="52bfe-243">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="52bfe-243">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-january-14"></a><span data-ttu-id="52bfe-245">版本 1908：1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="52bfe-245">Version 1908: January 14</span></span>
<span data-ttu-id="52bfe-246">*版本 1908 (組建 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="52bfe-246">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="52bfe-247">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="52bfe-247">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="52bfe-249">功能更新</span><span class="sxs-lookup"><span data-stu-id="52bfe-249">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="52bfe-250">Access</span><span class="sxs-lookup"><span data-stu-id="52bfe-250">Access</span></span>

- <span data-ttu-id="52bfe-251">**將索引標籤保留在資料庫物件上：** 能清楚看到使用中的索引標籤、輕鬆拖曳索引標籤來重新排列，只要按一下就能關閉資料庫物件。</span><span class="sxs-lookup"><span data-stu-id="52bfe-251">**Keep tabs on your database objects:** Clearly see the active tab, easily drag tabs to rearrange them, and close database objects with just one click.</span></span>

- <span data-ttu-id="52bfe-252">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="52bfe-252">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="52bfe-253">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="52bfe-253">Switching between them has never been easier.</span></span> [<span data-ttu-id="52bfe-254">深入了解</span><span class="sxs-lookup"><span data-stu-id="52bfe-254">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="52bfe-255">**使用更大的空間來縮放：** 加大 [縮放] 方塊、變更字型、記憶縮放。</span><span class="sxs-lookup"><span data-stu-id="52bfe-255">**Zoom with more room:** Make the Zoom box bigger, change the font, and Zoom remembers it all.</span></span> [<span data-ttu-id="52bfe-256">深入了解</span><span class="sxs-lookup"><span data-stu-id="52bfe-256">Learn more</span></span>](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

### <a name="excel"></a><span data-ttu-id="52bfe-257">Excel</span><span class="sxs-lookup"><span data-stu-id="52bfe-257">Excel</span></span>

- <span data-ttu-id="52bfe-258">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="52bfe-258">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="52bfe-259">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="52bfe-259">Switching between them has never been easier.</span></span> [<span data-ttu-id="52bfe-260">深入了解</span><span class="sxs-lookup"><span data-stu-id="52bfe-260">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="52bfe-261">**增加您內容的覆蓋面：** 想要讓您的簡報更易於使用嗎？</span><span class="sxs-lookup"><span data-stu-id="52bfe-261">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="52bfe-262">讓協助工具檢查程式來幫助您，您不需要自行處理。</span><span class="sxs-lookup"><span data-stu-id="52bfe-262">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="52bfe-263">按一下 [校閱] > [檢查協助工具] 試試看這個功能 – 我們會在狀態列上告訴您需要留意的部分。</span><span class="sxs-lookup"><span data-stu-id="52bfe-263">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="52bfe-264">**快速找到該檔案：** 想要尋找最近使用過的檔案嗎？</span><span class="sxs-lookup"><span data-stu-id="52bfe-264">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="52bfe-265">只要在 [檔案] > [常用] 頁面的 [搜尋] 方塊中輸入，就能找到所需的檔案。</span><span class="sxs-lookup"><span data-stu-id="52bfe-265">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="52bfe-266">**觀看工作表生動地呈現：** 插入動畫 3D 圖形，來查看心跳、行星軌道，以及暴龍在工作表內橫衝直撞。</span><span class="sxs-lookup"><span data-stu-id="52bfe-266">**Watch your worksheet come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage through the workbook.</span></span> [<span data-ttu-id="52bfe-267">深入了解</span><span class="sxs-lookup"><span data-stu-id="52bfe-267">Learn more</span></span>](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- <span data-ttu-id="52bfe-p111">**更深入地探索您的資料：** 新的 [構想] 按鈕可尋找資料的模式，並使用模式建立更有智慧且個人化的建議。[深入了解](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span><span class="sxs-lookup"><span data-stu-id="52bfe-p111">**Discover more about your data:** The new Ideas button looks for patterns in your data, and uses them to create intelligent, personalized suggestions. [Learn more](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span></span>

- <span data-ttu-id="52bfe-270">**共同作業變得更容易：** 共同撰寫的增強功能代表的是使用條件式格式設定、儲存格樣式等等時，您的變更會與共同作業者的變更順暢地合併。</span><span class="sxs-lookup"><span data-stu-id="52bfe-270">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>

- <span data-ttu-id="52bfe-271">**聯結類似欄位上的表格：** 在比較合併表格的欄位時，取得及轉換 (Power Query) 現在具有近似文字比對邏輯 (也稱為模糊比對)。</span><span class="sxs-lookup"><span data-stu-id="52bfe-271">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span> [<span data-ttu-id="52bfe-272">深入了解</span><span class="sxs-lookup"><span data-stu-id="52bfe-272">Learn more</span></span>](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- <span data-ttu-id="52bfe-273">**使用 Power Query 的增強功能快速撰寫程式碼：** 使用自動完成和語法色彩快速完成程式碼。</span><span class="sxs-lookup"><span data-stu-id="52bfe-273">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="52bfe-274">同時輕鬆探索函數、資料行和參數。</span><span class="sxs-lookup"><span data-stu-id="52bfe-274">Easily discover functions, columns, and parameters, too.</span></span>

- <span data-ttu-id="52bfe-275">**搜尋並享受：** 我們新增了 [搜尋以插入] 圖示，讓您輕鬆找到您要的圖示。</span><span class="sxs-lookup"><span data-stu-id="52bfe-275">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="52bfe-276">而當您選取時，[插入] 按鈕會告知您已經選取的數量。</span><span class="sxs-lookup"><span data-stu-id="52bfe-276">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="52bfe-277">深入了解</span><span class="sxs-lookup"><span data-stu-id="52bfe-277">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook"></a><span data-ttu-id="52bfe-278">Outlook</span><span class="sxs-lookup"><span data-stu-id="52bfe-278">Outlook</span></span>

- <span data-ttu-id="52bfe-279">**我們已為您更新 Outlook 使用者體驗：** 先前利用「即將推出」提供預覽的簡化體驗，專門設計來幫助您專注於最重要的事物上。</span><span class="sxs-lookup"><span data-stu-id="52bfe-279">**We’ve updated the Outlook user experience for you:** A simplified experience, previously available for preview with Coming Soon, designed to help you focus on what matters most.</span></span> [<span data-ttu-id="52bfe-280">深入了解</span><span class="sxs-lookup"><span data-stu-id="52bfe-280">Learn more</span></span>](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- <span data-ttu-id="52bfe-281">**簡化且也能自訂的功能區：** 輕鬆使用簡化、以單一列方式陳列的常用按鈕。</span><span class="sxs-lookup"><span data-stu-id="52bfe-281">**A simplified ribbon that's customizable, too:** Enjoy a streamlined, single row of the most frequently used buttons.</span></span> <span data-ttu-id="52bfe-282">輕鬆在傳統與 [簡化] 檢視之間切換，以及釘選/取消釘選命令。</span><span class="sxs-lookup"><span data-stu-id="52bfe-282">Easily switch between classic and Simplified views, and pin/unpin commands.</span></span> [<span data-ttu-id="52bfe-283">深入了解</span><span class="sxs-lookup"><span data-stu-id="52bfe-283">Learn more</span></span>](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- <span data-ttu-id="52bfe-284">**在移動郵件時繼續作業：** Outlook 現在會在背景中移動郵件，因此，在資料夾之間移動大量郵件時您可以繼續作業。</span><span class="sxs-lookup"><span data-stu-id="52bfe-284">**Keep working while moving messages:** Outlook now moves messages in the background, so you can keep working while moving lots of messages between folders.</span></span>

- <span data-ttu-id="52bfe-285">**在連續會議之間置入時間：** 將會議預設為提早 5-10 分鐘結束，讓出席者有時間休息，或在前往下一個地點。</span><span class="sxs-lookup"><span data-stu-id="52bfe-285">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to end 5-10 minutes early by default.</span></span>

- <span data-ttu-id="52bfe-286">**挑選您的最愛動作：** 不使用 [標幟] 和 [刪除] 嗎？</span><span class="sxs-lookup"><span data-stu-id="52bfe-286">**Pick your favorite action:** Don't use Flag and Delete?</span></span> <span data-ttu-id="52bfe-287">那麼 [封存] 或 [標示為已讀取] 呢？</span><span class="sxs-lookup"><span data-stu-id="52bfe-287">How about Archive or Mark as Read?</span></span> <span data-ttu-id="52bfe-288">自訂快速動作功能表，加上您最常使用的命令。</span><span class="sxs-lookup"><span data-stu-id="52bfe-288">Customize the quick action menu with the commands you use most.</span></span>

- <span data-ttu-id="52bfe-p118">**他們會看到您的 meme：** 如果使用文字或靜態影像還不足以清楚表達您的想法，您可以使用動畫 GIF。[深入了解](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span><span class="sxs-lookup"><span data-stu-id="52bfe-p118">**They'll see what you meme:** When text or static images just won't do, use an animated GIF to make your point. [Learn more](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span></span>

- <span data-ttu-id="52bfe-291">**更快速新增帳戶的方式：** 由於帳戶設定已改善，您現在可以更輕鬆地將使用雙因素驗證的 Outlook.com 和 Gmail 帳戶新增到 Outlook。</span><span class="sxs-lookup"><span data-stu-id="52bfe-291">**A quicker way to add accounts:** Thanks to account setup improvements, it's easier than ever to add Outlook.com and Gmail accounts that use 2-factor authentication to Outlook.</span></span> [<span data-ttu-id="52bfe-292">深入了解</span><span class="sxs-lookup"><span data-stu-id="52bfe-292">Learn more</span></span>](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- <span data-ttu-id="52bfe-293">**不再受限於同步處理限制：** Outlook 的增強功能指出資料夾限制已不存在，因此您可以開始將您的共用信箱同步處理。</span><span class="sxs-lookup"><span data-stu-id="52bfe-293">**Say goodbye to sync limits:** Outlook improvements mean the folder limit is gone so go ahead and synchronize your shared mailboxes.</span></span>

- <span data-ttu-id="52bfe-294">**搜尋並享受：** 我們新增了 [搜尋以插入] 圖示，讓您輕鬆找到您要的圖示。</span><span class="sxs-lookup"><span data-stu-id="52bfe-294">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="52bfe-295">而當您選取時，[插入] 按鈕會告知您已經選取的數量。</span><span class="sxs-lookup"><span data-stu-id="52bfe-295">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="52bfe-296">深入了解</span><span class="sxs-lookup"><span data-stu-id="52bfe-296">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint"></a><span data-ttu-id="52bfe-297">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="52bfe-297">PowerPoint</span></span>

- <span data-ttu-id="52bfe-298">**較佳變形效果：** 命名您的圖形以便加強掌控其轉化方式。</span><span class="sxs-lookup"><span data-stu-id="52bfe-298">**Better shapeshifting:** Name your shapes for more control over how they morph.</span></span> [<span data-ttu-id="52bfe-299">深入了解</span><span class="sxs-lookup"><span data-stu-id="52bfe-299">Learn more</span></span>](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- <span data-ttu-id="52bfe-300">**快速找到該檔案：** 想要尋找最近使用過的檔案嗎？</span><span class="sxs-lookup"><span data-stu-id="52bfe-300">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="52bfe-301">只要在 [檔案] > [常用] 頁面的 [搜尋] 方塊中輸入，就能找到所需的檔案。</span><span class="sxs-lookup"><span data-stu-id="52bfe-301">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="52bfe-302">**增加您內容的覆蓋面：** 想要讓您的簡報更易於使用嗎？</span><span class="sxs-lookup"><span data-stu-id="52bfe-302">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="52bfe-303">讓協助工具檢查程式來幫助您，您不需要自行處理。</span><span class="sxs-lookup"><span data-stu-id="52bfe-303">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="52bfe-304">按一下 [校閱] > [檢查協助工具] 試試看這個功能 – 我們會在狀態列上告訴您需要留意的部分。</span><span class="sxs-lookup"><span data-stu-id="52bfe-304">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="52bfe-305">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="52bfe-305">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="52bfe-306">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="52bfe-306">Switching between them has never been easier.</span></span> [<span data-ttu-id="52bfe-307">深入了解</span><span class="sxs-lookup"><span data-stu-id="52bfe-307">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="52bfe-308">**線上影片有新的首頁：** 將影片儲存至 Microsoft Stream，讓組織中的任何人都看得到。</span><span class="sxs-lookup"><span data-stu-id="52bfe-308">**Online videos have a new home:** Save a video to Microsoft Stream so anyone in your organization can see it.</span></span> <span data-ttu-id="52bfe-309">插入影片連結，享受檔案大小只有原來一小部分的多媒體簡報。</span><span class="sxs-lookup"><span data-stu-id="52bfe-309">Insert the video link and enjoy a multimedia presentation at a fraction of the file size.</span></span> [<span data-ttu-id="52bfe-310">深入了解</span><span class="sxs-lookup"><span data-stu-id="52bfe-310">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="52bfe-311">**隨時儲存變更：** 將檔案上傳至 OneDrive，確保所有的更新都會自動儲存。</span><span class="sxs-lookup"><span data-stu-id="52bfe-311">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="52bfe-p126">**透過測驗或問卷詢問聽眾：** 在投影片上進行測驗或問卷。Office 會收集並儲存存儲您的回應。[深入了解](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span><span class="sxs-lookup"><span data-stu-id="52bfe-p126">**Ask your audience with a quiz or survey:** Put a quiz or survey on a slide. Office collects and stores the responses for you. [Learn more](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span></span>

- <span data-ttu-id="52bfe-p127">**輕鬆插入內嵌影片：** 想要在您的投影片中放入 Vimeo 或 YouTube 影片嗎？只要有影片頁面連結即可。[深入了解](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span><span class="sxs-lookup"><span data-stu-id="52bfe-p127">**Inserting an online video is easier than ever:** Want to put a video from Vimeo or YouTube on your slide? The video page link is all you need. [Learn more](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span></span>

- <span data-ttu-id="52bfe-318">**搜尋並享受：** 我們新增了 [搜尋以插入] 圖示，讓您輕鬆找到您要的圖示。</span><span class="sxs-lookup"><span data-stu-id="52bfe-318">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="52bfe-319">而當您選取時，[插入] 按鈕會告知您已經選取的數量。</span><span class="sxs-lookup"><span data-stu-id="52bfe-319">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="52bfe-320">深入了解</span><span class="sxs-lookup"><span data-stu-id="52bfe-320">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="project"></a><span data-ttu-id="52bfe-321">Project</span><span class="sxs-lookup"><span data-stu-id="52bfe-321">Project</span></span>

- <span data-ttu-id="52bfe-322">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="52bfe-322">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="52bfe-323">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="52bfe-323">Switching between them has never been easier.</span></span> [<span data-ttu-id="52bfe-324">深入了解</span><span class="sxs-lookup"><span data-stu-id="52bfe-324">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a><span data-ttu-id="52bfe-325">Visio</span><span class="sxs-lookup"><span data-stu-id="52bfe-325">Visio</span></span>

- <span data-ttu-id="52bfe-326">**將進度圖表匯出到 Word：** 在 Word 文件中自動新增圖表內容，如圖案和中繼資料。</span><span class="sxs-lookup"><span data-stu-id="52bfe-326">**Export process diagrams to Word:** Automatically add diagram content, such as shapes and metadata, to a Word document.</span></span> <span data-ttu-id="52bfe-327">然後，自訂文件來建立程序指導方針和操作手冊。</span><span class="sxs-lookup"><span data-stu-id="52bfe-327">Then customize the document to create process guidelines and operation manuals.</span></span> [<span data-ttu-id="52bfe-328">深入了解</span><span class="sxs-lookup"><span data-stu-id="52bfe-328">Learn more</span></span>](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- <span data-ttu-id="52bfe-329">**資料流程圖上的 Double-Take：** 資料視覺化工具流程圖美觀的新版面配置，既清新、簡潔且更易於了解。</span><span class="sxs-lookup"><span data-stu-id="52bfe-329">**Double-take on data flowcharts:** Gorgeous new layouts for Data Visualizer flowcharts are clean, crisp, and easy to understand.</span></span> <span data-ttu-id="52bfe-330">按一下 [設計] 索引標籤來取得選項。</span><span class="sxs-lookup"><span data-stu-id="52bfe-330">Click the Design tab for options.</span></span>

- <span data-ttu-id="52bfe-331">**內建的 Azure 樣板：** 使用數十種 Azure 樣板來設計雲端應用程式或規劃架構。</span><span class="sxs-lookup"><span data-stu-id="52bfe-331">**Azure stencils built right in:** Design a cloud app or plan an architecture using dozens of Azure stencils.</span></span> [<span data-ttu-id="52bfe-332">深入了解</span><span class="sxs-lookup"><span data-stu-id="52bfe-332">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- <span data-ttu-id="52bfe-p133">**告別錯誤的 Excel 連結：** 找不到與 Data Visualizer 圖表連結的 Excel 活頁簿嗎？重新連結，就可繼續使用了。[深入了解](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span><span class="sxs-lookup"><span data-stu-id="52bfe-p133">**Say goodbye to broken Excel links:** Can't find the Excel workbook linked to your Data Visualizer diagram? Relink it, and you're back in business. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span></span>

- <span data-ttu-id="52bfe-336">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="52bfe-336">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="52bfe-337">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="52bfe-337">Switching between them has never been easier.</span></span> [<span data-ttu-id="52bfe-338">深入了解</span><span class="sxs-lookup"><span data-stu-id="52bfe-338">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="52bfe-339">**從 Power BI 匯出 Visio 視覺效果：** 當匯出 Power BI 報表為 PDF 或 PowerPoint 等檔案時，Power BI Visio 視覺效果會正常顯示。</span><span class="sxs-lookup"><span data-stu-id="52bfe-339">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span> [<span data-ttu-id="52bfe-340">深入了解</span><span class="sxs-lookup"><span data-stu-id="52bfe-340">Learn more</span></span>](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a><span data-ttu-id="52bfe-341">Word</span><span class="sxs-lookup"><span data-stu-id="52bfe-341">Word</span></span>

- <span data-ttu-id="52bfe-342">**[學習工具] 模式額外支援更多頁面色彩：** Word 中的 [學習工具] 新增更多頁面佈景主題色彩的支援，讓您能夠變更頁面的背景色彩。</span><span class="sxs-lookup"><span data-stu-id="52bfe-342">**Learning Tools mode has additional support for more page colors:** Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span> <span data-ttu-id="52bfe-343">許多人在背景全白或全黑時閱讀會有困難，因此我們在 PC 和 Mac 的 Word 中增加了色彩選項。</span><span class="sxs-lookup"><span data-stu-id="52bfe-343">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

- <span data-ttu-id="52bfe-p137">**編輯當然是使用筆跡編輯：** 使用畫筆透過單一筆劃來分割或加入文字、新增新的一行，或插入文字。[深入了解](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span><span class="sxs-lookup"><span data-stu-id="52bfe-p137">**Editing comes naturally with Ink Editor:** With a single stroke, split or join words, add a new line, or insert words using your pen. [Learn more](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span></span>

- <span data-ttu-id="52bfe-p138">**為靜態文件注入動人的生命力：** 將文件轉變為在任何裝置上，均具有完美外觀的可互動、易分享的網頁。[深入了解](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span><span class="sxs-lookup"><span data-stu-id="52bfe-p138">**Take your doc from static to stunning:** Transform your document into an interactive, easy-to-share web page that looks great on any device. [Learn more](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span></span>

- <span data-ttu-id="52bfe-348">**增加您內容的覆蓋面：** 想要讓您的文件更易於使用嗎？</span><span class="sxs-lookup"><span data-stu-id="52bfe-348">**Increase the reach of your content:** Need to make your documents accessible?</span></span> <span data-ttu-id="52bfe-349">讓協助工具檢查程式來幫助您，您不需要自行處理。</span><span class="sxs-lookup"><span data-stu-id="52bfe-349">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="52bfe-350">按一下 [校閱] > [檢查協助工具] 試試看這個功能 – 我們會在狀態列上告訴您需要留意的部分。</span><span class="sxs-lookup"><span data-stu-id="52bfe-350">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="52bfe-351">**快速找到該檔案：** 想要尋找最近使用過的檔案嗎？</span><span class="sxs-lookup"><span data-stu-id="52bfe-351">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="52bfe-352">只要在 [檔案] > [常用] 頁面的 [搜尋] 方塊中輸入，就能找到所需的檔案。</span><span class="sxs-lookup"><span data-stu-id="52bfe-352">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="52bfe-353">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="52bfe-353">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="52bfe-354">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="52bfe-354">Switching between them has never been easier.</span></span> [<span data-ttu-id="52bfe-355">深入了解</span><span class="sxs-lookup"><span data-stu-id="52bfe-355">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="52bfe-p142">**運用行聚焦，提高理解力：** 毫不費力地逐行瀏覽文件。調整焦點，在檢視畫面中一次放入一行、三行或五行。[深入了解](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="52bfe-p142">**Improve comprehension with Line Focus:** Move through a document line by line without distractions. Adjust the focus to put one, three, or five lines in view at a time. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>

- <span data-ttu-id="52bfe-359">**隨時儲存變更：** 將檔案上傳至 OneDrive，確保所有的更新都會自動儲存。</span><span class="sxs-lookup"><span data-stu-id="52bfe-359">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="52bfe-360">**使用 \@Mentions 提及功能取得他人注意：** 在註解中使用 @mentions 提及功能，讓同事知道您需要他們提供建議。</span><span class="sxs-lookup"><span data-stu-id="52bfe-360">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="52bfe-361">深入了解</span><span class="sxs-lookup"><span data-stu-id="52bfe-361">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="52bfe-362">**搜尋並享受：** 我們新增了 [搜尋以插入] 圖示，讓您輕鬆找到您要的圖示。</span><span class="sxs-lookup"><span data-stu-id="52bfe-362">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="52bfe-363">而當您選取時，[插入] 按鈕會告知您已經選取的數量。</span><span class="sxs-lookup"><span data-stu-id="52bfe-363">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="52bfe-364">深入了解</span><span class="sxs-lookup"><span data-stu-id="52bfe-364">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="office-suite"></a><span data-ttu-id="52bfe-365">Office 套件</span><span class="sxs-lookup"><span data-stu-id="52bfe-365">Office Suite</span></span>

- <span data-ttu-id="52bfe-366">**快速找到該檔案：** 想要尋找最近使用過的檔案嗎？</span><span class="sxs-lookup"><span data-stu-id="52bfe-366">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="52bfe-367">只要在 [檔案] > [開啟] 索引標籤的 [搜尋] 方塊中輸入，就能找到所需的檔案。</span><span class="sxs-lookup"><span data-stu-id="52bfe-367">Just type in the Search box on the File > Open tab to find the file you're looking for.</span></span>

- <span data-ttu-id="52bfe-368">**隨時儲存變更：** 將檔案上傳至 OneDrive，確保所有的更新都會自動儲存。</span><span class="sxs-lookup"><span data-stu-id="52bfe-368">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="52bfe-369">**隱私權控制：** 用於診斷資料和連線體驗的新增、更新及改良的控制項。</span><span class="sxs-lookup"><span data-stu-id="52bfe-369">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> [<span data-ttu-id="52bfe-370">深入了解</span><span class="sxs-lookup"><span data-stu-id="52bfe-370">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

- <span data-ttu-id="52bfe-371">**Office 圖示有新的外觀：** Office 圖示經過重新設計，以反映簡單、功能強大且智慧型的 Office 體驗。</span><span class="sxs-lookup"><span data-stu-id="52bfe-371">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

- <span data-ttu-id="52bfe-372">**安裝 Microsoft Teams：** 在 Office 365 專業增強版的現有安裝中，預設會安裝 Microsoft Teams。</span><span class="sxs-lookup"><span data-stu-id="52bfe-372">**Installation of Microsoft Teams:** Microsoft Teams is installed by default for existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="52bfe-373">深入了解</span><span class="sxs-lookup"><span data-stu-id="52bfe-373">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/teams-install)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="52bfe-376">解決的問題</span><span class="sxs-lookup"><span data-stu-id="52bfe-376">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="52bfe-377">Access</span><span class="sxs-lookup"><span data-stu-id="52bfe-377">Access</span></span>

- <span data-ttu-id="52bfe-378">此更新修正彙總 (例如 Sum) 可能會將結果截斷成整數值的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-378">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="52bfe-379">此更新修正包含參照遠端桌面 (例如 SQL Server 桌面) 的聯集查詢可能造成 Access 關閉並重新啟動的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-379">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="52bfe-380">此更新可修正 Microsoft Access 中的「更新查詢」執行時或在 SQL 中使用 UPDATE 陳述式時，可能導致發生錯誤「查詢已損壞」&quot;&quot;的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-380">This update fixes an issue in Microsoft Access that may cause the error &quot;Query is Corrupt&quot; when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="52bfe-381">Excel</span><span class="sxs-lookup"><span data-stu-id="52bfe-381">Excel</span></span>

- <span data-ttu-id="52bfe-382">文件標題的荷蘭文按鍵提示已變更為 Alt-G。</span><span class="sxs-lookup"><span data-stu-id="52bfe-382">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="52bfe-383">修正在 Excel 中指派給圖形或表單控制項的巨集可能顯示不正確的錯誤訊息，或者可能會處理不正確目標範圍的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-383">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="52bfe-384">解決「尋找及取代」在找到第一個項目後，對話方塊中的焦點位置變更的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-384">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="52bfe-385">此更新修正在與其他使用者共同撰寫的工作階段中變更樞紐分析表排序的方式，然後重新整理可能觸發當機的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-385">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="52bfe-386">我們已修正當 OLAP 樞紐分析表的篩選條件設定為已從 cube 移除的值時會發生的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-386">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="52bfe-387">修正以校正使用圖表範本插入圖表時，預覽中使用的色彩。</span><span class="sxs-lookup"><span data-stu-id="52bfe-387">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="52bfe-388">我們已修正當變更系列集合時，可能會導致散佈折線圖無法正確呈現的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-388">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span>

- <span data-ttu-id="52bfe-389">已解決當插入或刪除儲存格時，瀑布圖和漏斗圖無法與表格同步處理的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-389">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="52bfe-390">修正 Excel 中合併衝突的問題，此問題會造成提示使用者重新開啟活頁簿以取得變更。</span><span class="sxs-lookup"><span data-stu-id="52bfe-390">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="52bfe-391">解決了開啟內嵌活頁簿時，功能區自訂無法載入的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-391">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="52bfe-392">已解決造成執行階段錯誤啟動最小化視窗的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-392">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="52bfe-393">解決了開啟內嵌活頁簿時，功能區自訂無法載入的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-393">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="52bfe-394">已解決導致表格旁的剪下並貼上作業在與其他人共同撰寫時失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-394">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="52bfe-395">解決使用執行中巨集變更自訂屬性時，會導致共同撰寫中斷的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-395">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="52bfe-396">發生您無法從增益集開啟的 WPF (Windows Presentation Foundation) 表單的下拉式方塊選取項目的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-396">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="52bfe-397">解決在未開啟活頁簿時，搜尋最近使用的檔案會造成當機的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-397">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="52bfe-398">非同步使用者定義函數造成的效能問題，導致它們同步執行。</span><span class="sxs-lookup"><span data-stu-id="52bfe-398">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="52bfe-399">已大幅改善刪除有合併儲存格之欄的效能。</span><span class="sxs-lookup"><span data-stu-id="52bfe-399">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="52bfe-400">解決捲動後選取儲存格時，可能導致選取錯誤儲存格的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-400">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="52bfe-401">已解決 Lookup 函數可能會傳回錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-401">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="52bfe-402">解決在目前的 Office 版本中開啟在舊版 Office 中建立的活頁簿時，可能導致 Excel 懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-402">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="52bfe-403">當檔案具備大量設定格式化的條件時，按一下 [字型色彩] 按鈕時出現的效能緩慢問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-403">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="52bfe-404">我們已修正預覽列印中的列印範圍不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-404">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="52bfe-405">從不受信任的網路共用編輯受保護的檔案時，Excel 可能會發生問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-405">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="52bfe-406">我們已大幅提升依色彩篩選的效能。</span><span class="sxs-lookup"><span data-stu-id="52bfe-406">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="52bfe-407">已解決會導致將超連結貼到一些受保護工作表中的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-407">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="52bfe-408">當在增益集管理員中瀏覽時，顯示 16 個以上的增益集。</span><span class="sxs-lookup"><span data-stu-id="52bfe-408">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="52bfe-409">這項變更透過利用軟體轉譯避免特定 Intel 圖形驅動程式發生問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-409">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="52bfe-410">來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。</span><span class="sxs-lookup"><span data-stu-id="52bfe-410">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="52bfe-411">此更新修正 Office 文件無法上傳到商務用 OneDrive 的錯誤 (訊息「上傳失敗」)。</span><span class="sxs-lookup"><span data-stu-id="52bfe-411">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="52bfe-412">已修正在 Excel 構想功能中，在 Win32 用戶端中按一下 [構想] 按鈕來載入增益集時會發生錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-412">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span>

### <a name="outlook"></a><span data-ttu-id="52bfe-413">Outlook</span><span class="sxs-lookup"><span data-stu-id="52bfe-413">Outlook</span></span>

- <span data-ttu-id="52bfe-414">來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。</span><span class="sxs-lookup"><span data-stu-id="52bfe-414">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="52bfe-415">修正使用者將信箱從基本驗證升級為新式驗證後，造成將錯誤的帳戶與其 Outlook 設定檔相關聯的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-415">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="52bfe-416">已解決造成網頁增益集在不該存取數位版權管理郵件時進行存取的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-416">Addressed an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="52bfe-417">已解決導致部分安全連結無法顯示簡單動態顯示 URL 的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-417">Addressed an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="52bfe-418">更新 Outlook 中的附件封鎖邏輯，以同時封鎖 python 附件。</span><span class="sxs-lookup"><span data-stu-id="52bfe-418">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="52bfe-419">已解決導致部分 POP3 使用者查看所有純文字格式電子郵件 (無論設定) 的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-419">Addressed an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="52bfe-420">此修正將會還原 HTML 格式郵件的檢視。</span><span class="sxs-lookup"><span data-stu-id="52bfe-420">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="52bfe-421">已解決當使用者將項目從其主要行事曆複製到群組行事曆時，造成使用者遇到權限錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-421">Addressed an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="52bfe-422">已解決導致使用者無法透過螢幕助讀程式存取位置建議的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-422">Addressed an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="52bfe-423">已解決當使用者透過鍵盤快速鍵與信箱資料夾互動時造成明顯延遲的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-423">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="52bfe-424">已解決導致非常長時間的 Outlook 工作階段記憶體流失的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-424">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="52bfe-425">已解決導致使用者在開啟 [規則] 對話方塊時看到「在這部電腦中建立的規則和 Microsoft Exchange 上的規則衝突」提示的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-425">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="52bfe-426">已解決導致使用者在與特定安全連結互動時在 Outlook 中發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-426">Addressed an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="52bfe-427">已解決導致經理對於代理人是否已經回覆特定會議邀請含混不清的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-427">Addressed an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="52bfe-428">已解決導致使用者在處理某些自動探索回應時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-428">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="52bfe-429">已解決導致使用者在嘗試從 [帳戶建立] 內容連絡支援服務時，看到具有 [確定] 按鈕的空白訊息方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-429">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="52bfe-430">此變更可讓系統管理員啟用一個原則，以在自動探索驗證提示中較 UPN 優先使用所提供的帳戶電子郵件。</span><span class="sxs-lookup"><span data-stu-id="52bfe-430">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="52bfe-431">依預設，自動探索會優先於帳戶 UPN (如果有的話)。</span><span class="sxs-lookup"><span data-stu-id="52bfe-431">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="52bfe-432">解決會導致使用者看到針對新式群組的搜尋失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-432">Addressed an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="52bfe-433">已解決導致 Outlook 使用者在特定案例中停滯在「需要密碼」狀態的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-433">Addressed an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="52bfe-434">已解決以下問題：使用者看到某會議室可用時間之外的會議室建議。</span><span class="sxs-lookup"><span data-stu-id="52bfe-434">Addressed an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="52bfe-435">已解決導致使用者在傳送加密電子郵件時遇到「不支援的加密演算法」錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-435">Addressed an issue that caused users to encounter "encryption algorithm is not supported" errors when sending an encrypted email.</span></span>

- <span data-ttu-id="52bfe-436">已解決非英文使用者的郵件中，主旨列會相當小的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-436">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="52bfe-437">已解決導致某些使用者在新增次要 Exchange 帳戶時看到建立了重複特殊資料夾的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-437">Addressed an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="52bfe-438">已解決導致使用者嘗試從「未接的交談」建立規則時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-438">Addressed an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="52bfe-439">已修正 SMIME 演算法選取的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-439">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="52bfe-440">已解決使用其他寄件者時導致無法顯示原則提示的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-440">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="52bfe-441">已解決導致使用者在 Outlook 處理序中看到記憶體洩漏的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-441">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="52bfe-442">已解決導致使用者在更新目前狀態資訊時遇到間歇性當機的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-442">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="52bfe-443">已解決導致目前的資料夾搜尋間歇性失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-443">Addressed an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="52bfe-444">已解決嘗試擷取使用者的 Outlook 雲端設定時，導致一些使用者遇到驗證錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-444">Addressed an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="52bfe-445">已解決導致在搜尋意見反應體驗中懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-445">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="52bfe-446">已解決導致使用者在處理某些自動探索回應時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-446">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="52bfe-447">已解決導致使用者在更新目前狀態資訊時遇到間歇性當機的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-447">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="52bfe-448">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="52bfe-448">PowerPoint</span></span>

- <span data-ttu-id="52bfe-449">修正某些增益集會在圖表的圖形周圍擲出未預期錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-449">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="52bfe-450">來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。</span><span class="sxs-lookup"><span data-stu-id="52bfe-450">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="52bfe-451">此變更還原 PowerPoint 影片控制項的協助工具名稱的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-451">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="52bfe-452">我們已修正部分動畫無法開始的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-452">We fixed an issue which could prevent some animations from starting.</span></span>

- <span data-ttu-id="52bfe-453">我們已修正將投影片從一個簡報複製到另一個簡報時可能會造成母片重複的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-453">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>

- <span data-ttu-id="52bfe-454">如果在不支援的版本中開啟含有新的新式註解的檔案，將會顯示黃色警告</span><span class="sxs-lookup"><span data-stu-id="52bfe-454">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

- <span data-ttu-id="52bfe-455">可靠性修正：已修正第三方增益集可能會造成 PowerPoint 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-455">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="52bfe-456">已修正 PowerPoint 中半形片假名字元在垂直文字方塊中無法正確旋轉的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-456">Fixed an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="52bfe-457">Project</span><span class="sxs-lookup"><span data-stu-id="52bfe-457">Project</span></span>

- <span data-ttu-id="52bfe-458">修正讓 Windows 7 上的使用者能夠從 Project Web App 和 SharePoint 網站開啟專案的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-458">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="52bfe-459">發現在開啟唯讀專案時，使用者可能會收到數個訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-459">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="52bfe-460">「全部撫平」命令無法正確解決資源過度分派的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-460">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="52bfe-461">當您有作業中有零個工作的指派時，可能無法將作業標示為完成且永遠會顯示為 99%。</span><span class="sxs-lookup"><span data-stu-id="52bfe-461">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

### <a name="visio"></a><span data-ttu-id="52bfe-462">Visio</span><span class="sxs-lookup"><span data-stu-id="52bfe-462">Visio</span></span>

- <span data-ttu-id="52bfe-463">無法從 Visio 將多個圖形匯出為 SVG。</span><span class="sxs-lookup"><span data-stu-id="52bfe-463">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="52bfe-464">Word</span><span class="sxs-lookup"><span data-stu-id="52bfe-464">Word</span></span>

- <span data-ttu-id="52bfe-465">此變更能讓使用 Word 開啟文件的效能提升。</span><span class="sxs-lookup"><span data-stu-id="52bfe-465">This change will lead to performance improvements in opening documents using Word.</span></span>

- <span data-ttu-id="52bfe-466">來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。</span><span class="sxs-lookup"><span data-stu-id="52bfe-466">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="52bfe-467">我們已修正當列印到 Deskjet 印表機時，可能會導致縮放比例問題的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-467">We fixed an issue which could have caused scaling issues when printing to Deskjet printers.</span></span>

- <span data-ttu-id="52bfe-468">我們已修正追蹤修訂有時候會進入無限迴圈的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-468">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="52bfe-469">已修正應用程式可能在關機時懸置的各種問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-469">Fixed various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="52bfe-470">同時修正特定相關增益集當機的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-470">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="52bfe-471">Office 套件</span><span class="sxs-lookup"><span data-stu-id="52bfe-471">Office Suite</span></span>

- <span data-ttu-id="52bfe-472">已修正不正確地將平假名和漢字中的日本新年號 "Reiwa" (令和) 識別為拼字錯誤或不合文法的運算式的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-472">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="52bfe-473">已修正嘗試共用儲存在 SharePoint 2016 上的檔案時，導致使用者遇到「很抱歉，發生問題，無法共用」訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-473">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="52bfe-474">已修正在 PowerPoint 共同撰寫和離線編輯的工作階段中可能會導致資料遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-474">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="52bfe-475">修正使用者在開啟檔案時可能會遇到的當機問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-475">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="52bfe-476">避免 PowerPoint 使用者嘗試進行「線上展示」時遇到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-476">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

- <span data-ttu-id="52bfe-477">在某些情況下，同步處理引擎備份的 SharePoint 檔案可能會顯示「已儲存」但實際上未儲存任何變更，導致資料遺失。</span><span class="sxs-lookup"><span data-stu-id="52bfe-477">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="52bfe-478">解決使用者可能無法儲存 Word、Excel 和 PowerPoint 文件的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-478">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="52bfe-479">此問題會影響建立新檔案並在按一下 [儲存] 圖示或按 Ctrl + S 之後帶出 [另存成模型對話方塊] 選項的使用者。</span><span class="sxs-lookup"><span data-stu-id="52bfe-479">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="52bfe-480">已修正 Win7 的效能問題，其中，於所有應用程式中從功能區插入圖案庫時，大約需要 4 秒鐘的時間才會顯示。</span><span class="sxs-lookup"><span data-stu-id="52bfe-480">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="52bfe-481">已修正 Backstage 的 [資訊位置] 平板未顯示協助工具資訊的錯誤。</span><span class="sxs-lookup"><span data-stu-id="52bfe-481">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="52bfe-482">改善有關登錄完整性的 Office 更新程序的可靠性。</span><span class="sxs-lookup"><span data-stu-id="52bfe-482">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="52bfe-483">解決 Office 更新可能會非預期地從 Office CDN 而不是預期使用的來源 (例如本機或網路共用或 Configuration Manager 提供的位置) 下載檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-483">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="52bfe-484">修正了 Office 更新訊息不以預期語言顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-484">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="52bfe-485">自此以後，Office 更新訊息會正確符合 Windows 顯示語言。</span><span class="sxs-lookup"><span data-stu-id="52bfe-485">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="52bfe-486">已解決在某些情況下，如果使用者不是系統管理員且系統帳戶沒有網路連線，將無法套用更新的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-486">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="52bfe-487">某些情況下，Office 快速鍵可能會在更新後消失。</span><span class="sxs-lookup"><span data-stu-id="52bfe-487">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="52bfe-488">此更新可改善發佈 Office 快速鍵時的可靠性。</span><span class="sxs-lookup"><span data-stu-id="52bfe-488">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="52bfe-489">已更正可能會在計量網路上意外封鎖更新的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-489">Corrected an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="52bfe-490">修正相對期限只有在第一次設定時才會有效的 ODT 和 GPO 更新期限設定中的錯誤 (bug)。此修正可啟用後續更新的相關期限。</span><span class="sxs-lookup"><span data-stu-id="52bfe-490">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="52bfe-491">已改善透過恢復之前可能已中斷的下載，下載 Office 更新時的可靠性。</span><span class="sxs-lookup"><span data-stu-id="52bfe-491">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="52bfe-492">已解決第三方外掛程式中與文字方塊/圖案自動調整屬性相關的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-492">Addressed issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="52bfe-493">我們已修正大型樹狀檢視可能會導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-493">We fixed an issue where large tree views could result in a crash.</span></span>

- <span data-ttu-id="52bfe-494">為了保護 Office 客戶的安全性，我們現在專門使用 SHA-2 演算法來簽署 Microsoft Office 更新。</span><span class="sxs-lookup"><span data-stu-id="52bfe-494">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-january-14"></a><span data-ttu-id="52bfe-496">版本 1902：1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="52bfe-496">Version 1902: January 14</span></span>
<span data-ttu-id="52bfe-497">*版本 1902 (組建 11328.20512)*</span><span class="sxs-lookup"><span data-stu-id="52bfe-497">*Version 1902 (Build 11328.20512)*</span></span>

<span data-ttu-id="52bfe-498">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="52bfe-498">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="52bfe-500">解決的問題</span><span class="sxs-lookup"><span data-stu-id="52bfe-500">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="52bfe-501">Excel</span><span class="sxs-lookup"><span data-stu-id="52bfe-501">Excel</span></span>

- <span data-ttu-id="52bfe-502">解決了開啟內嵌活頁簿時，功能區自訂無法載入的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-502">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="52bfe-503">Outlook</span><span class="sxs-lookup"><span data-stu-id="52bfe-503">Outlook</span></span>

- <span data-ttu-id="52bfe-504">解決導致使用者在傳送加密電子郵件時遇到「不支援的加密演算法」錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="52bfe-504">Addresses an issue that caused users to encounter "encryption algorithm is not supporte" errors when sending an encrypted email.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="52bfe-505">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="52bfe-505">PowerPoint</span></span>

- <span data-ttu-id="52bfe-506">如果在不支援的版本中開啟含有新的新式註解的檔案，將會顯示黃色警告。</span><span class="sxs-lookup"><span data-stu-id="52bfe-506">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

### <a name="word"></a><span data-ttu-id="52bfe-507">Word</span><span class="sxs-lookup"><span data-stu-id="52bfe-507">Word</span></span>

- <span data-ttu-id="52bfe-508">此變更能讓使用 Word 開啟文件的效能提升。</span><span class="sxs-lookup"><span data-stu-id="52bfe-508">This change will lead to performance improvements in opening documents using Word.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1808-january-14"></a><span data-ttu-id="52bfe-510">版本 1808：1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="52bfe-510">Version 1808: January 14</span></span>
<span data-ttu-id="52bfe-511">*版本 1808 (組建 10730.20432)*</span><span class="sxs-lookup"><span data-stu-id="52bfe-511">*Version 1808 (Build 10730.20432)*</span></span>

<span data-ttu-id="52bfe-512">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="52bfe-512">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

> [!NOTE]
> <span data-ttu-id="52bfe-514">如果您需要關於使用 Office 的問題協助，建議您將問題張貼在 [Microsoft Answers 論壇](https://answers.microsoft.com/)或[技術社群](https://techcommunity.microsoft.com/)，或連絡[支援](https://support.microsoft.com/contactus)。</span><span class="sxs-lookup"><span data-stu-id="52bfe-514">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>
