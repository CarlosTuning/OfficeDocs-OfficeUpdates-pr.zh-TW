---
title: Office 部署工具 (ODT) 的發行記錄
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ODT
description: 為 IT 專業人員提供 Office 部署工具 (ODT) 的發行記錄
ms.openlocfilehash: 70e000f7cbdc597bde156257fc7e4b2a1e6e69eb
ms.sourcegitcommit: 58d55cf532d1d02cca85772920a6dd71089b071d
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/22/2020
ms.locfileid: "43781566"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="975a7-103">Office 部署工具的發行記錄</span><span class="sxs-lookup"><span data-stu-id="975a7-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="975a7-104">Office 部署工具 (ODT) 是一種命令列工具，可用來將像 Microsoft 365 應用程式這類的 Office 隨選即用版本下載並部署到用戶端電腦。</span><span class="sxs-lookup"><span data-stu-id="975a7-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="975a7-105">ODT 能讓您進一步控制 Office 安裝。</span><span class="sxs-lookup"><span data-stu-id="975a7-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="975a7-106">您可以定義要安裝哪些產品及語言、這些產品的更新方式，以及是否要讓使用者看到安裝過程。</span><span class="sxs-lookup"><span data-stu-id="975a7-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="975a7-107">如需有關如何使用 ODT 的詳細資訊，請參閱 [Office 部署工具概觀](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)。</span><span class="sxs-lookup"><span data-stu-id="975a7-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="975a7-108">**支援的作業系統**：Windows 10、Windows 7、Windows 8、Windows 8.1、Windows Server 2008 R2、Windows Server 2012 和 Windows Server 2012 R2</span><span class="sxs-lookup"><span data-stu-id="975a7-108">**Supported Operating System**: Windows 10, Windows 7, Windows 8, Windows 8.1, Windows Server 2008 R2, Windows Server 2012, Windows Server 2012 R2</span></span> 
 
 <span data-ttu-id="975a7-109">**安裝指示**：下載檔案然後執行自我解壓縮可執行檔，其中會包含 Office 部署工具可執行檔 (setup.exe) 及範例組態檔 (configuration.xml)。</span><span class="sxs-lookup"><span data-stu-id="975a7-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="975a7-110">下載 Office 部署工具</span><span class="sxs-lookup"><span data-stu-id="975a7-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)


## <a name="april-15-2020"></a><span data-ttu-id="975a7-111">2020 年 4 月 15 日</span><span class="sxs-lookup"><span data-stu-id="975a7-111">April 15, 2020</span></span>

<span data-ttu-id="975a7-112">版本 16.0.12624.20320 (setup.exe 版本 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="975a7-112">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="975a7-113">新增對於 Windows 7 特定生命週期結束 Office 版本的支援</span><span class="sxs-lookup"><span data-stu-id="975a7-113">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="975a7-114">已修正可能無法如預期方式套用自訂設定的問題</span><span class="sxs-lookup"><span data-stu-id="975a7-114">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="975a7-115">已修正可能會意外下載無關 .cat 檔案的問題</span><span class="sxs-lookup"><span data-stu-id="975a7-115">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="975a7-116">2020 年 1 月 16 日</span><span class="sxs-lookup"><span data-stu-id="975a7-116">January 16, 2020</span></span>

<span data-ttu-id="975a7-117">版本 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="975a7-117">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="975a7-118">修正在安裝多個語言時，Office 安裝 UI 可能會以不正確的語言顯示的問題</span><span class="sxs-lookup"><span data-stu-id="975a7-118">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="975a7-119">修正在安裝某些校訂工具套件之後，Office 安裝可能會非預期地失敗的問題</span><span class="sxs-lookup"><span data-stu-id="975a7-119">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="975a7-120">新增支援以選擇性地控制 [Bing 中的 Microsoft Search](https://go.microsoft.com/fwlink/p/?linkid=2109345) 的初始部署</span><span class="sxs-lookup"><span data-stu-id="975a7-120">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="975a7-121">2019 年 10 月 31 日</span><span class="sxs-lookup"><span data-stu-id="975a7-121">October 31, 2019</span></span>

<span data-ttu-id="975a7-122">版本 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="975a7-122">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="975a7-123">修正了允許商務用 Skype 基本版 2019 安裝 2019 永久企業版大量授權產品的問題</span><span class="sxs-lookup"><span data-stu-id="975a7-123">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="975a7-124">修正了使用 Proxy 時，在某些情況下，可能會導致 ODT 下載模式意外失敗的問題</span><span class="sxs-lookup"><span data-stu-id="975a7-124">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="975a7-125">新功能可讓 ODT 下載模式透過 HTTP 連接埠 80 以外的埠來下載</span><span class="sxs-lookup"><span data-stu-id="975a7-125">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="975a7-126">2019 年 7 月 10 日</span><span class="sxs-lookup"><span data-stu-id="975a7-126">July 10, 2019</span></span>

<span data-ttu-id="975a7-127">版本 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="975a7-127">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="975a7-128">隨 Office 2019 一起安裝時，新增了對其他產品的支援：Access Runtime，商務用 Skype 基本版。</span><span class="sxs-lookup"><span data-stu-id="975a7-128">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="975a7-129">從 MSI 升級時，新增對獨立產品之條件式件安裝的支援。</span><span class="sxs-lookup"><span data-stu-id="975a7-129">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="975a7-130">2019 年 4 月 23 日</span><span class="sxs-lookup"><span data-stu-id="975a7-130">April 23, 2019</span></span>

<span data-ttu-id="975a7-131">版本 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="975a7-131">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="975a7-132">已修正 RemoveMSI = True 清除相關登錄設定的錯誤。</span><span class="sxs-lookup"><span data-stu-id="975a7-132">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="975a7-133">更新錯誤碼，為非預期的失敗 (E_UNEXPECTED) 提供其他詳細資料。</span><span class="sxs-lookup"><span data-stu-id="975a7-133">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="975a7-134">2019 年 4 月 16 日</span><span class="sxs-lookup"><span data-stu-id="975a7-134">April 16 2019</span></span>

<span data-ttu-id="975a7-135">版本 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="975a7-135">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="975a7-136">支援使用新的 MigrateArch 屬性將 32 位元 C2R 升級到 64 位元 C2R。</span><span class="sxs-lookup"><span data-stu-id="975a7-136">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="975a7-137">更新了 /configure 的邏輯，允許存取儲存在 Web 位置 (http 和 https) 中的設定 XML 文件。</span><span class="sxs-lookup"><span data-stu-id="975a7-137">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="975a7-138">已新增 MatchInstalled 為新屬性，允許 ODT 在新增其他產品或語言時比對現有版本。</span><span class="sxs-lookup"><span data-stu-id="975a7-138">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="975a7-139">2019 年 3 月 13 日</span><span class="sxs-lookup"><span data-stu-id="975a7-139">March 13, 2019</span></span>

<span data-ttu-id="975a7-140">版本 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="975a7-140">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="975a7-141">升級與移轉案例的增強功能。</span><span class="sxs-lookup"><span data-stu-id="975a7-141">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="975a7-142">2019 年 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="975a7-142">January 14, 2019</span></span>

<span data-ttu-id="975a7-143">版本 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="975a7-143">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="975a7-144">部署設定的記錄及遙測改良功能。</span><span class="sxs-lookup"><span data-stu-id="975a7-144">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="975a7-145">相關連結</span><span class="sxs-lookup"><span data-stu-id="975a7-145">Related links</span></span>

[<span data-ttu-id="975a7-146">ODT 下載中心</span><span class="sxs-lookup"><span data-stu-id="975a7-146">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)