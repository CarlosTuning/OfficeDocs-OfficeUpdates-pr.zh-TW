---
title: Office 365 專業增強版的已知問題
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: RelNotes_ProPlus
description: 提供 Office 365 專業增強版已知問題的相關資訊
ms.openlocfilehash: a8b385e197a6f61c10797bf160101cdd70285aaf
ms.sourcegitcommit: a6d8dba3ee51727c2d3a2dad89cb986595c1a7b8
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/20/2019
ms.locfileid: "37068050"
---
# <a name="office-365-proplus-known-issues"></a><span data-ttu-id="02c72-103">Office 365 專業增強版的已知問題</span><span class="sxs-lookup"><span data-stu-id="02c72-103">Office 365 ProPlus Known Issues</span></span>

<span data-ttu-id="02c72-104">這些已知問題可提供 2019 年 Office 365 專業增強版、Visio Pro for Office 365、Project Online 電腦版用戶端以及 Office 365 商務版的每月通道更新、SACT 與 SAC 更新所含的非安全性更新的相關資訊。</span><span class="sxs-lookup"><span data-stu-id="02c72-104">These release notes provide information about new features and non-security updates that are included in Monthly Channel updates to Office 365 ProPlus in 2019, including Visio Pro for Office 365 and Project Online Desktop Client.</span></span>

<span data-ttu-id="02c72-105">下表提供目前進行中的問題和已解決的問題摘要。</span><span class="sxs-lookup"><span data-stu-id="02c72-105">This table offers a summary of current active issues and those issues that have been resolved.</span></span>  <span data-ttu-id="02c72-106">我們會以正在調查的重大問題來更新下表。</span><span class="sxs-lookup"><span data-stu-id="02c72-106">We will update the table below with significant issues we are investigating.</span></span>

 > [!NOTE]
 >- <span data-ttu-id="02c72-107">這個清單並不全面。</span><span class="sxs-lookup"><span data-stu-id="02c72-107">This list is not comprehensive.</span></span>

<br>

## <a name="september-2019"></a><span data-ttu-id="02c72-108">2019 年 9 月</span><span class="sxs-lookup"><span data-stu-id="02c72-108">September 10, 2019</span></span>

|<span data-ttu-id="02c72-109">摘要</span><span class="sxs-lookup"><span data-stu-id="02c72-109">Summary</span></span>|<span data-ttu-id="02c72-110">調查中</span><span class="sxs-lookup"><span data-stu-id="02c72-110">Investigating</span></span>|<span data-ttu-id="02c72-111">已解決</span><span class="sxs-lookup"><span data-stu-id="02c72-111">Resolved</span></span>|
|:-------------------------------------------------------------------------------------|:-----|:-----|
|<span data-ttu-id="02c72-112">**Outlook**</span><span class="sxs-lookup"><span data-stu-id="02c72-112">**Outlook**</span></span>
<span data-ttu-id="02c72-113">我們已修正可能會無法儲存檔案到 WebDAV 位置的問題。</span><span class="sxs-lookup"><span data-stu-id="02c72-113">We found an issue which could have prevented files from being saved to a WebDAV location.</span></span>|<span data-ttu-id="02c72-114">每月版本 1909</span><span class="sxs-lookup"><span data-stu-id="02c72-114">Monthly Version 1909</span></span>||
|<span data-ttu-id="02c72-115">**Project**</span><span class="sxs-lookup"><span data-stu-id="02c72-115">**Project**</span></span>
<span data-ttu-id="02c72-116">請考慮下列案例。</span><span class="sxs-lookup"><span data-stu-id="02c72-116">Consider the following scenario.</span></span> <span data-ttu-id="02c72-117">開啟專案。</span><span class="sxs-lookup"><span data-stu-id="02c72-117">You open a project.</span></span> <span data-ttu-id="02c72-118">按一下 [檔案] 功能表、按一下 [匯出]、然後按一下 [建立 PDF/XPS] 按鈕。</span><span class="sxs-lookup"><span data-stu-id="02c72-118">You click the File menu, click Export and click the Create PDF/XPS button.</span></span> <span data-ttu-id="02c72-119">在 [瀏覽] 對話方塊中、輸入檔案名、然後按一下 [確定]。</span><span class="sxs-lookup"><span data-stu-id="02c72-119">Within the Browse dialog box, you enter a file name and click OK.</span></span> <span data-ttu-id="02c72-120">在這種情況下，您會發現 XPS 檔案的 PDF 沒有建立。</span><span class="sxs-lookup"><span data-stu-id="02c72-120">In this situation, you find that the PDF of XPS file is not created.</span></span> |<span data-ttu-id="02c72-121">SAC 版本 1902</span><span class="sxs-lookup"><span data-stu-id="02c72-121">SAC Version 1902</span></span>||
|<span data-ttu-id="02c72-122">**Word**</span><span class="sxs-lookup"><span data-stu-id="02c72-122">**Word**</span></span>
<span data-ttu-id="02c72-123">我們發現使用者開啟檔案時可能會遇到問題。</span><span class="sxs-lookup"><span data-stu-id="02c72-123">We found an issue users could hit on opening a file.</span></span>|<span data-ttu-id="02c72-124">每月版本 1908</span><span class="sxs-lookup"><span data-stu-id="02c72-124">Monthly Version 1908</span></span>||
<span data-ttu-id="02c72-125">對於由 OneDrive 同步處理引擎同步處理的 Office 檔案，在 [儲存] 和 [另存新檔] 時將不會再驗證文件中繼資料 (例如必要屬性和內容類型需求)。</span><span class="sxs-lookup"><span data-stu-id="02c72-125">For Office files synced by the OneDrive Sync Engine, document metadata such as Require Properties and Content Type requirements are no longer validated upon Save and Save As.</span></span>|<span data-ttu-id="02c72-126">SAC 版本 1902</span><span class="sxs-lookup"><span data-stu-id="02c72-126">SAC Version 1902</span></span>||

## <a name="may-2019---sample"></a><span data-ttu-id="02c72-127">2019 年 5 月 - 範例</span><span class="sxs-lookup"><span data-stu-id="02c72-127">May 2019 - SAMPLE</span></span>

|<span data-ttu-id="02c72-128">摘要</span><span class="sxs-lookup"><span data-stu-id="02c72-128">Summary</span></span>|<span data-ttu-id="02c72-129">調查中</span><span class="sxs-lookup"><span data-stu-id="02c72-129">Investigating</span></span>|<span data-ttu-id="02c72-130">已解決</span><span class="sxs-lookup"><span data-stu-id="02c72-130">Resolved</span></span>|
|:-------------------------------------------------------------------------------------|:-----|:-----|
|<span data-ttu-id="02c72-131">**Excel**</span><span class="sxs-lookup"><span data-stu-id="02c72-131">**Excel**</span></span>
<span data-ttu-id="02c72-132">多個組建中的範例已解決：我們發現了一個問題，導致插入或刪除儲存格時，瀑布圖和漏斗圖無法與表格同步處理。</span><span class="sxs-lookup"><span data-stu-id="02c72-132">Sample resoved in multiple builds -- We found an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>||<span data-ttu-id="02c72-133">SAC 版本 1902</span><span class="sxs-lookup"><span data-stu-id="02c72-133">SAC Version 1902</span></span> <br> <span data-ttu-id="02c72-134">(16.0.11328.20306)</span><span class="sxs-lookup"><span data-stu-id="02c72-134">(16.0.11328.20306)</span></span> <br> <span data-ttu-id="02c72-135">每月版本 1905</span><span class="sxs-lookup"><span data-stu-id="02c72-135">Monthly Version 1905</span></span> <br> <span data-ttu-id="02c72-136">(16.0.11629.20210)</span><span class="sxs-lookup"><span data-stu-id="02c72-136">(16.0.11629.20210)</span></span>|
|<span data-ttu-id="02c72-137">**Word**</span><span class="sxs-lookup"><span data-stu-id="02c72-137">**Word**</span></span>
<span data-ttu-id="02c72-138">部分組建中的範例已解決 (並非全部)：我們在啟用文件摘要資訊的快速組件時發現效能問題。</span><span class="sxs-lookup"><span data-stu-id="02c72-138">Sample resoved in some builds, not all -- We found an issue with performance when enabling Quick Parts for Document propertiesk.</span></span>|<span data-ttu-id="02c72-139">SAC 版本 1808</span><span class="sxs-lookup"><span data-stu-id="02c72-139">SAC Version 1808</span></span>|<span data-ttu-id="02c72-140">SAC 版本 1902</span><span class="sxs-lookup"><span data-stu-id="02c72-140">SAC Version 1902</span></span> <br> <span data-ttu-id="02c72-141">(16.0.11328.20340)</span><span class="sxs-lookup"><span data-stu-id="02c72-141">(16.0.11328.20340)</span></span>|

<br>
<br>

> [!NOTE]
> <span data-ttu-id="02c72-142">如果您需要關於使用 Office 的問題協助，建議您將問題張貼在 [Microsoft Answers 論壇](https://answers.microsoft.com/)或[技術社群](https://techcommunity.microsoft.com/)，或連絡[支援](https://support.microsoft.com/contactus)。</span><span class="sxs-lookup"><span data-stu-id="02c72-142">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>
