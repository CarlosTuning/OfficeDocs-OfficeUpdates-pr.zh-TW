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
ms.openlocfilehash: 4f65d41bfa18321a951fb18abcf919056bec7c5d
ms.sourcegitcommit: 57e715a8a3c0565b902cb3e6ca45d18a26f8ec45
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/15/2020
ms.locfileid: "48469992"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="a26e7-103">Office 部署工具的發行記錄</span><span class="sxs-lookup"><span data-stu-id="a26e7-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="a26e7-104">Office 部署工具 (ODT) 是一種命令列工具，可用來將像 Microsoft 365 應用程式這類的 Office 隨選即用版本下載並部署到用戶端電腦。</span><span class="sxs-lookup"><span data-stu-id="a26e7-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="a26e7-105">ODT 能讓您進一步控制 Office 安裝。</span><span class="sxs-lookup"><span data-stu-id="a26e7-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="a26e7-106">您可以定義要安裝哪些產品及語言、這些產品的更新方式，以及是否要讓使用者看到安裝過程。</span><span class="sxs-lookup"><span data-stu-id="a26e7-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="a26e7-107">如需有關如何使用 ODT 的詳細資訊，請參閱 [Office 部署工具概觀](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)。</span><span class="sxs-lookup"><span data-stu-id="a26e7-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="a26e7-108">**支援作業系統**：Windows 10、Windows 8.1、Windows Server 2019、Windows Server 2016</span><span class="sxs-lookup"><span data-stu-id="a26e7-108">**Supported Operating System**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="a26e7-109">**安裝指示**：下載檔案然後執行自我解壓縮可執行檔，其中會包含 Office 部署工具可執行檔 (setup.exe) 及範例組態檔 (configuration.xml)。</span><span class="sxs-lookup"><span data-stu-id="a26e7-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="a26e7-110">下載 Office 部署工具</span><span class="sxs-lookup"><span data-stu-id="a26e7-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)

## <a name="october-14-2020"></a><span data-ttu-id="a26e7-111">2020 年 10 月14 日</span><span class="sxs-lookup"><span data-stu-id="a26e7-111">October 14, 2020</span></span>
<span data-ttu-id="a26e7-112">版本 16.0.13231.20368 (setup.exe 版本 16.0.13231.20350)</span><span class="sxs-lookup"><span data-stu-id="a26e7-112">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="a26e7-113">當沒有指定頻道時，預設情况下所有產品都將使用每月通道</span><span class="sxs-lookup"><span data-stu-id="a26e7-113">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="a26e7-114">解决了使用R emoveMSI 時某些 Office 2007 產品可能意外封鎖安裝的問題</span><span class="sxs-lookup"><span data-stu-id="a26e7-114">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>
- <span data-ttu-id="a26e7-115">改善從含有其他 DLL 的目錄執行 ODT 時的安全性</span><span class="sxs-lookup"><span data-stu-id="a26e7-115">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="a26e7-116">可靠性和恢復改善</span><span class="sxs-lookup"><span data-stu-id="a26e7-116">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="a26e7-117">2020 年 6 月 9 日</span><span class="sxs-lookup"><span data-stu-id="a26e7-117">June 9, 2020</span></span>

<span data-ttu-id="a26e7-118">版本 16.0.12827.20268 (setup.exe 版本 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="a26e7-118">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="a26e7-119">在未指定頻道時，目前的通道即為預設的頻道。</span><span class="sxs-lookup"><span data-stu-id="a26e7-119">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="a26e7-120">新增每月企業通道的支援</span><span class="sxs-lookup"><span data-stu-id="a26e7-120">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="a26e7-121">新增新頻道名稱的支援</span><span class="sxs-lookup"><span data-stu-id="a26e7-121">Added support for new channel names</span></span>
- <span data-ttu-id="a26e7-122">即使在無法使用部分語言資源時，如可能，可持續安裝其他復原功能</span><span class="sxs-lookup"><span data-stu-id="a26e7-122">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="a26e7-123">MSIRemove 的功能已展開，可移除 Office 2007 產品</span><span class="sxs-lookup"><span data-stu-id="a26e7-123">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="a26e7-124">MSIRemove 的功能已展開，可移除 Access 資料庫引擎</span><span class="sxs-lookup"><span data-stu-id="a26e7-124">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="a26e7-125">2020 年 4 月 15 日</span><span class="sxs-lookup"><span data-stu-id="a26e7-125">April 15, 2020</span></span>

<span data-ttu-id="a26e7-126">版本 16.0.12624.20320 (setup.exe 版本 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="a26e7-126">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="a26e7-127">新增對於 Windows 7 特定生命週期結束 Office 版本的支援</span><span class="sxs-lookup"><span data-stu-id="a26e7-127">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="a26e7-128">已修正可能無法如預期方式套用自訂設定的問題</span><span class="sxs-lookup"><span data-stu-id="a26e7-128">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="a26e7-129">已修正可能會意外下載無關 .cat 檔案的問題</span><span class="sxs-lookup"><span data-stu-id="a26e7-129">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="a26e7-130">2020 年 1 月 16 日</span><span class="sxs-lookup"><span data-stu-id="a26e7-130">January 16, 2020</span></span>

<span data-ttu-id="a26e7-131">版本 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="a26e7-131">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="a26e7-132">修正在安裝多個語言時，Office 安裝 UI 可能會以不正確的語言顯示的問題</span><span class="sxs-lookup"><span data-stu-id="a26e7-132">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="a26e7-133">修正在安裝某些校訂工具套件之後，Office 安裝可能會非預期地失敗的問題</span><span class="sxs-lookup"><span data-stu-id="a26e7-133">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="a26e7-134">新增支援以選擇性地控制 [Bing 中的 Microsoft Search](https://go.microsoft.com/fwlink/p/?linkid=2109345) 的初始部署</span><span class="sxs-lookup"><span data-stu-id="a26e7-134">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="a26e7-135">2019 年 10 月 31 日</span><span class="sxs-lookup"><span data-stu-id="a26e7-135">October 31, 2019</span></span>

<span data-ttu-id="a26e7-136">版本 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="a26e7-136">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="a26e7-137">修正了允許商務用 Skype 基本版 2019 安裝 2019 永久企業版大量授權產品的問題</span><span class="sxs-lookup"><span data-stu-id="a26e7-137">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="a26e7-138">修正了使用 Proxy 時，在某些情況下，可能會導致 ODT 下載模式意外失敗的問題</span><span class="sxs-lookup"><span data-stu-id="a26e7-138">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="a26e7-139">新功能可讓 ODT 下載模式透過 HTTP 連接埠 80 以外的埠來下載</span><span class="sxs-lookup"><span data-stu-id="a26e7-139">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="a26e7-140">2019 年 7 月 10 日</span><span class="sxs-lookup"><span data-stu-id="a26e7-140">July 10, 2019</span></span>

<span data-ttu-id="a26e7-141">版本 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="a26e7-141">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="a26e7-142">隨 Office 2019 一起安裝時，新增了對其他產品的支援：Access Runtime，商務用 Skype 基本版。</span><span class="sxs-lookup"><span data-stu-id="a26e7-142">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="a26e7-143">從 MSI 升級時，新增對獨立產品之條件式件安裝的支援。</span><span class="sxs-lookup"><span data-stu-id="a26e7-143">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="a26e7-144">2019 年 4 月 23 日</span><span class="sxs-lookup"><span data-stu-id="a26e7-144">April 23, 2019</span></span>

<span data-ttu-id="a26e7-145">版本 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="a26e7-145">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="a26e7-146">已修正 RemoveMSI = True 清除相關登錄設定的錯誤。</span><span class="sxs-lookup"><span data-stu-id="a26e7-146">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="a26e7-147">更新錯誤碼，為非預期的失敗 (E_UNEXPECTED) 提供其他詳細資料。</span><span class="sxs-lookup"><span data-stu-id="a26e7-147">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="a26e7-148">2019 年 4 月 16 日</span><span class="sxs-lookup"><span data-stu-id="a26e7-148">April 16 2019</span></span>

<span data-ttu-id="a26e7-149">版本 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="a26e7-149">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="a26e7-150">支援使用新的 MigrateArch 屬性將 32 位元 C2R 升級到 64 位元 C2R。</span><span class="sxs-lookup"><span data-stu-id="a26e7-150">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="a26e7-151">更新了 /configure 的邏輯，允許存取儲存在 Web 位置 (http 和 https) 中的設定 XML 文件。</span><span class="sxs-lookup"><span data-stu-id="a26e7-151">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="a26e7-152">已新增 MatchInstalled 為新屬性，允許 ODT 在新增其他產品或語言時比對現有版本。</span><span class="sxs-lookup"><span data-stu-id="a26e7-152">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="a26e7-153">2019 年 3 月 13 日</span><span class="sxs-lookup"><span data-stu-id="a26e7-153">March 13, 2019</span></span>

<span data-ttu-id="a26e7-154">版本 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="a26e7-154">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="a26e7-155">升級與移轉案例的增強功能。</span><span class="sxs-lookup"><span data-stu-id="a26e7-155">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="a26e7-156">2019 年 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="a26e7-156">January 14, 2019</span></span>

<span data-ttu-id="a26e7-157">版本 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="a26e7-157">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="a26e7-158">部署設定的記錄及遙測改良功能。</span><span class="sxs-lookup"><span data-stu-id="a26e7-158">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="a26e7-159">相關連結</span><span class="sxs-lookup"><span data-stu-id="a26e7-159">Related links</span></span>

[<span data-ttu-id="a26e7-160">ODT 下載中心</span><span class="sxs-lookup"><span data-stu-id="a26e7-160">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)