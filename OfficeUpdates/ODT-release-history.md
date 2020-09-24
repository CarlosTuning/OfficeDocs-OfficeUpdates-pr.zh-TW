---
title: Office 部署工具 (ODT) 的發行記錄
ms.author: timda
author: TimDavenport
manager: TimDavenport
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ODT
description: 為 IT 專業人員提供 Office 部署工具 (ODT) 的發行記錄
ms.openlocfilehash: c01fbe403dacb0b474c37b7439eba5b616f8a08f
ms.sourcegitcommit: 591f5da255de896ef3156108349c6d2eaf34ed54
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/22/2020
ms.locfileid: "48174642"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="d3a2f-103">Office 部署工具的發行記錄</span><span class="sxs-lookup"><span data-stu-id="d3a2f-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="d3a2f-104">Office 部署工具 (ODT) 是一種命令列工具，可用來將像 Microsoft 365 應用程式這類的 Office 隨選即用版本下載並部署到用戶端電腦。</span><span class="sxs-lookup"><span data-stu-id="d3a2f-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="d3a2f-105">ODT 能讓您進一步控制 Office 安裝。</span><span class="sxs-lookup"><span data-stu-id="d3a2f-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="d3a2f-106">您可以定義要安裝哪些產品及語言、這些產品的更新方式，以及是否要讓使用者看到安裝過程。</span><span class="sxs-lookup"><span data-stu-id="d3a2f-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="d3a2f-107">如需有關如何使用 ODT 的詳細資訊，請參閱 [Office 部署工具概觀](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)。</span><span class="sxs-lookup"><span data-stu-id="d3a2f-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="d3a2f-108">**支援作業系統**：Windows 10、Windows 8.1、Windows Server 2019、Windows Server 2016</span><span class="sxs-lookup"><span data-stu-id="d3a2f-108">**Supported Operating System**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="d3a2f-109">**安裝指示**：下載檔案然後執行自我解壓縮可執行檔，其中會包含 Office 部署工具可執行檔 (setup.exe) 及範例組態檔 (configuration.xml)。</span><span class="sxs-lookup"><span data-stu-id="d3a2f-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="d3a2f-110">下載 Office 部署工具</span><span class="sxs-lookup"><span data-stu-id="d3a2f-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)


## <a name="june-9-2020"></a><span data-ttu-id="d3a2f-111">2020 年 6 月 9 日</span><span class="sxs-lookup"><span data-stu-id="d3a2f-111">June 9, 2020</span></span>

<span data-ttu-id="d3a2f-112">版本 16.0.12827.20268 (setup.exe 版本 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="d3a2f-112">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="d3a2f-113">在未指定頻道時，目前的通道即為預設的頻道。</span><span class="sxs-lookup"><span data-stu-id="d3a2f-113">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="d3a2f-114">新增每月企業通道的支援</span><span class="sxs-lookup"><span data-stu-id="d3a2f-114">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="d3a2f-115">新增新頻道名稱的支援</span><span class="sxs-lookup"><span data-stu-id="d3a2f-115">Added support for new channel names</span></span>
- <span data-ttu-id="d3a2f-116">即使在無法使用部分語言資源時，如可能，可持續安裝其他復原功能</span><span class="sxs-lookup"><span data-stu-id="d3a2f-116">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="d3a2f-117">MSIRemove 的功能已展開，可移除 Office 2007 產品</span><span class="sxs-lookup"><span data-stu-id="d3a2f-117">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="d3a2f-118">MSIRemove 的功能已展開，可移除 Access 資料庫引擎</span><span class="sxs-lookup"><span data-stu-id="d3a2f-118">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="d3a2f-119">2020 年 4 月 15 日</span><span class="sxs-lookup"><span data-stu-id="d3a2f-119">April 15, 2020</span></span>

<span data-ttu-id="d3a2f-120">版本 16.0.12624.20320 (setup.exe 版本 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="d3a2f-120">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="d3a2f-121">新增對於 Windows 7 特定生命週期結束 Office 版本的支援</span><span class="sxs-lookup"><span data-stu-id="d3a2f-121">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="d3a2f-122">已修正可能無法如預期方式套用自訂設定的問題</span><span class="sxs-lookup"><span data-stu-id="d3a2f-122">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="d3a2f-123">已修正可能會意外下載無關 .cat 檔案的問題</span><span class="sxs-lookup"><span data-stu-id="d3a2f-123">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="d3a2f-124">2020 年 1 月 16 日</span><span class="sxs-lookup"><span data-stu-id="d3a2f-124">January 16, 2020</span></span>

<span data-ttu-id="d3a2f-125">版本 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="d3a2f-125">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="d3a2f-126">修正在安裝多個語言時，Office 安裝 UI 可能會以不正確的語言顯示的問題</span><span class="sxs-lookup"><span data-stu-id="d3a2f-126">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="d3a2f-127">修正在安裝某些校訂工具套件之後，Office 安裝可能會非預期地失敗的問題</span><span class="sxs-lookup"><span data-stu-id="d3a2f-127">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="d3a2f-128">新增支援以選擇性地控制 [Bing 中的 Microsoft Search](https://go.microsoft.com/fwlink/p/?linkid=2109345) 的初始部署</span><span class="sxs-lookup"><span data-stu-id="d3a2f-128">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="d3a2f-129">2019 年 10 月 31 日</span><span class="sxs-lookup"><span data-stu-id="d3a2f-129">October 31, 2019</span></span>

<span data-ttu-id="d3a2f-130">版本 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="d3a2f-130">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="d3a2f-131">修正了允許商務用 Skype 基本版 2019 安裝 2019 永久企業版大量授權產品的問題</span><span class="sxs-lookup"><span data-stu-id="d3a2f-131">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="d3a2f-132">修正了使用 Proxy 時，在某些情況下，可能會導致 ODT 下載模式意外失敗的問題</span><span class="sxs-lookup"><span data-stu-id="d3a2f-132">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="d3a2f-133">新功能可讓 ODT 下載模式透過 HTTP 連接埠 80 以外的埠來下載</span><span class="sxs-lookup"><span data-stu-id="d3a2f-133">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="d3a2f-134">2019 年 7 月 10 日</span><span class="sxs-lookup"><span data-stu-id="d3a2f-134">July 10, 2019</span></span>

<span data-ttu-id="d3a2f-135">版本 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="d3a2f-135">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="d3a2f-136">隨 Office 2019 一起安裝時，新增了對其他產品的支援：Access Runtime，商務用 Skype 基本版。</span><span class="sxs-lookup"><span data-stu-id="d3a2f-136">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="d3a2f-137">從 MSI 升級時，新增對獨立產品之條件式件安裝的支援。</span><span class="sxs-lookup"><span data-stu-id="d3a2f-137">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="d3a2f-138">2019 年 4 月 23 日</span><span class="sxs-lookup"><span data-stu-id="d3a2f-138">April 23, 2019</span></span>

<span data-ttu-id="d3a2f-139">版本 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="d3a2f-139">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="d3a2f-140">已修正 RemoveMSI = True 清除相關登錄設定的錯誤。</span><span class="sxs-lookup"><span data-stu-id="d3a2f-140">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="d3a2f-141">更新錯誤碼，為非預期的失敗 (E_UNEXPECTED) 提供其他詳細資料。</span><span class="sxs-lookup"><span data-stu-id="d3a2f-141">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="d3a2f-142">2019 年 4 月 16 日</span><span class="sxs-lookup"><span data-stu-id="d3a2f-142">April 16 2019</span></span>

<span data-ttu-id="d3a2f-143">版本 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="d3a2f-143">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="d3a2f-144">支援使用新的 MigrateArch 屬性將 32 位元 C2R 升級到 64 位元 C2R。</span><span class="sxs-lookup"><span data-stu-id="d3a2f-144">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="d3a2f-145">更新了 /configure 的邏輯，允許存取儲存在 Web 位置 (http 和 https) 中的設定 XML 文件。</span><span class="sxs-lookup"><span data-stu-id="d3a2f-145">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="d3a2f-146">已新增 MatchInstalled 為新屬性，允許 ODT 在新增其他產品或語言時比對現有版本。</span><span class="sxs-lookup"><span data-stu-id="d3a2f-146">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="d3a2f-147">2019 年 3 月 13 日</span><span class="sxs-lookup"><span data-stu-id="d3a2f-147">March 13, 2019</span></span>

<span data-ttu-id="d3a2f-148">版本 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="d3a2f-148">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="d3a2f-149">升級與移轉案例的增強功能。</span><span class="sxs-lookup"><span data-stu-id="d3a2f-149">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="d3a2f-150">2019 年 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="d3a2f-150">January 14, 2019</span></span>

<span data-ttu-id="d3a2f-151">版本 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="d3a2f-151">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="d3a2f-152">部署設定的記錄及遙測改良功能。</span><span class="sxs-lookup"><span data-stu-id="d3a2f-152">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="d3a2f-153">相關連結</span><span class="sxs-lookup"><span data-stu-id="d3a2f-153">Related links</span></span>

[<span data-ttu-id="d3a2f-154">ODT 下載中心</span><span class="sxs-lookup"><span data-stu-id="d3a2f-154">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)