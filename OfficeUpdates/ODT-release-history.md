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
ms.openlocfilehash: f6df62267f7f2035f610867721b3dc1b9f65a1bd
ms.sourcegitcommit: 4f5536e809f58462d81c708c153390ebfd1abc4e
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/13/2021
ms.locfileid: "53409579"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="255c8-103">Office 部署工具的發行記錄</span><span class="sxs-lookup"><span data-stu-id="255c8-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="255c8-104">Office 部署工具 (ODT) 是一種命令列工具，可用來將像 Microsoft 365 應用程式這類的 Office 隨選即用版本下載並部署到用戶端電腦。</span><span class="sxs-lookup"><span data-stu-id="255c8-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="255c8-p101">ODT 讓您對 Office 安裝作業有更多的控制權。您可以定義要安裝哪些產品及語言、這些產品的更新方式，以及是否要讓使用者看到安裝過程。若要了解如何使用 ODT 的詳細資訊，請參閱 [Office 部署工具概觀](/deployoffice/overview-of-the-office-2016-deployment-tool)。</span><span class="sxs-lookup"><span data-stu-id="255c8-p101">The ODT gives you more control over an Office installation. You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users. For information on how to use the ODT, see the [Overview of the Office Deployment Tool](/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="255c8-108">**支援作業系統**：Windows 10、Windows 8.1、Windows Server 2019、Windows Server 2016</span><span class="sxs-lookup"><span data-stu-id="255c8-108">**Supported Operating System**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="255c8-109">**安裝指示**：下載檔案然後執行自我解壓縮可執行檔，其中會包含 Office 部署工具可執行檔 (setup.exe) 及範例組態檔 (configuration.xml)。</span><span class="sxs-lookup"><span data-stu-id="255c8-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="255c8-110">下載 Office 部署工具</span><span class="sxs-lookup"><span data-stu-id="255c8-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)


## <a name="july-12-2021"></a><span data-ttu-id="255c8-111">2021 年 7 月 12 日</span><span class="sxs-lookup"><span data-stu-id="255c8-111">July 12, 2021</span></span>
<span data-ttu-id="255c8-112">版本 16.0.14131.20278 (setup.exe 版本 16.0.14131.20278)</span><span class="sxs-lookup"><span data-stu-id="255c8-112">Version 16.0.14131.20278 (setup.exe version 16.0.14131.20278)</span></span>
- <span data-ttu-id="255c8-113">已修正 RemoveMSI 在某些情況下會失敗的問題</span><span class="sxs-lookup"><span data-stu-id="255c8-113">Fixed an issue where RemoveMSI would fail in certain cases</span></span>
- <span data-ttu-id="255c8-114">修正偵測 setup.exe 並存執行的問題</span><span class="sxs-lookup"><span data-stu-id="255c8-114">Fixed an issue detecting concurrent executions of setup.exe</span></span>
- <span data-ttu-id="255c8-115">ARM 平台的可靠性修正</span><span class="sxs-lookup"><span data-stu-id="255c8-115">Reliability fixes for ARM platforms</span></span>


## <a name="june-17-2021"></a><span data-ttu-id="255c8-116">2021 年 6 月 17 日</span><span class="sxs-lookup"><span data-stu-id="255c8-116">June 17, 2021</span></span>
<span data-ttu-id="255c8-117">版本 16.0.14026.20306 (setup.exe 版本 16.0.14026.20306)</span><span class="sxs-lookup"><span data-stu-id="255c8-117">Version 16.0.14026.20306 (setup.exe version 16.0.14026.20306)</span></span>
- <span data-ttu-id="255c8-118">修正使用 MatchOS 語言選項的作業，在某些作業系統設定上失敗的問題</span><span class="sxs-lookup"><span data-stu-id="255c8-118">Fixes an issue where operations using the MatchOS language option were failing for some OS configurations</span></span>


## <a name="june-7-2021"></a><span data-ttu-id="255c8-119">2021 年 6 月 7 日</span><span class="sxs-lookup"><span data-stu-id="255c8-119">June 7, 2021</span></span>
<span data-ttu-id="255c8-120">版本 16.0.14026.20254 (setup.exe 版本 16.0.14026.20252)</span><span class="sxs-lookup"><span data-stu-id="255c8-120">Version 16.0.14026.20254 (setup.exe version 16.0.14026.20252)</span></span>
- <span data-ttu-id="255c8-121">ARM 平台的可靠性修正</span><span class="sxs-lookup"><span data-stu-id="255c8-121">Reliability fixes for ARM platforms</span></span>


## <a name="may-10-2021"></a><span data-ttu-id="255c8-122">2021 年 5 月 10 日</span><span class="sxs-lookup"><span data-stu-id="255c8-122">May 10, 2021</span></span>
<span data-ttu-id="255c8-123">版本 16.0.13929.20296 (setup.exe 版本 16.0.13929.20238)</span><span class="sxs-lookup"><span data-stu-id="255c8-123">Version 16.0.13929.20296 (setup.exe version 16.0.13929.20238)</span></span>
- <span data-ttu-id="255c8-124">已修正如果設定檔同時包含 MigrateArch 和 RemoveMSI，/configure 模式可能會失敗的問題</span><span class="sxs-lookup"><span data-stu-id="255c8-124">Fixed an issue where /configure mode may fail if a configuration file includes both MigrateArch and RemoveMSI</span></span>
- <span data-ttu-id="255c8-125">其他可靠性改良</span><span class="sxs-lookup"><span data-stu-id="255c8-125">Additional reliability improvements</span></span>

## <a name="april-13-2021"></a><span data-ttu-id="255c8-126">2021 年 4 月 13 日</span><span class="sxs-lookup"><span data-stu-id="255c8-126">April 13, 2021</span></span>
<span data-ttu-id="255c8-127">版本 16.0.13901.20336 (setup.exe 版本 16.0.13901.20328)</span><span class="sxs-lookup"><span data-stu-id="255c8-127">Version 16.0.13901.20336 (setup.exe version 16.0.13901.20328)</span></span>
- <span data-ttu-id="255c8-128">設定已在已安裝 Office 的裝置上執行作業的可靠性修正</span><span class="sxs-lookup"><span data-stu-id="255c8-128">Reliability fixes for configure operations that are run on devices with Office already installed</span></span>
- <span data-ttu-id="255c8-129">修正以在某些情況下避免顯示重複的進度 UI</span><span class="sxs-lookup"><span data-stu-id="255c8-129">Fixes to avoid showing duplicate progress UI in some scenarios</span></span>
- <span data-ttu-id="255c8-130">改善 UI 中顯示的錯誤碼正確性</span><span class="sxs-lookup"><span data-stu-id="255c8-130">Improvements to error code accuracy shown in UI</span></span>
- <span data-ttu-id="255c8-131">ARM 平台的可靠性修正</span><span class="sxs-lookup"><span data-stu-id="255c8-131">Reliability fixes for ARM platforms</span></span>

## <a name="march-23-2021"></a><span data-ttu-id="255c8-132">2021 年 3 月 23 日</span><span class="sxs-lookup"><span data-stu-id="255c8-132">March 23, 2021</span></span>
<span data-ttu-id="255c8-133">版本 16.0.13801.20360 (setup.exe 版本 16.0.13801.20340)</span><span class="sxs-lookup"><span data-stu-id="255c8-133">Version 16.0.13801.20360 (setup.exe version 16.0.13801.20340)</span></span>
- <span data-ttu-id="255c8-134">支援即將推出的 Office 產品版本資訊的變更</span><span class="sxs-lookup"><span data-stu-id="255c8-134">Changes to support upcoming Office product releases</span></span>
- <span data-ttu-id="255c8-135">ARM 平台的可靠性修正</span><span class="sxs-lookup"><span data-stu-id="255c8-135">Reliability fixes for ARM platforms</span></span>


## <a name="february-25-2021"></a><span data-ttu-id="255c8-136">2021 年 2 月 25 日</span><span class="sxs-lookup"><span data-stu-id="255c8-136">February 25, 2021</span></span>
<span data-ttu-id="255c8-137">版本 16.0.13628.20476 (setup.exe 版本 16.0.13628.20462)</span><span class="sxs-lookup"><span data-stu-id="255c8-137">Version 16.0.13628.20476 (setup.exe version 16.0.13628.20462)</span></span>
- <span data-ttu-id="255c8-138">修正 configuration.xml 檔案指定數十種無法驗證的語言的問題</span><span class="sxs-lookup"><span data-stu-id="255c8-138">Fixed an issue where configuration.xml files specifying several dozen languages was failing to validate</span></span>
- <span data-ttu-id="255c8-139">修正 MigrateArch 案例未遵守 FORCEAPPSHUTDOWN 屬性的問題</span><span class="sxs-lookup"><span data-stu-id="255c8-139">Fixed an issue where the FORCEAPPSHUTDOWN property was not being respected in MigrateArch scenarios</span></span>
- <span data-ttu-id="255c8-140">修正在 configuration.xml 中指定 2 個或多個 PIDKEY 屬性而無法安裝 PIDKey 的問題</span><span class="sxs-lookup"><span data-stu-id="255c8-140">Fixed an issue where specifying 2 or more PIDKEY attributes in configuration.xml failed to install the PIDKeys</span></span>



## <a name="february-9-2021"></a><span data-ttu-id="255c8-141">2021 年 2 月 9 日</span><span class="sxs-lookup"><span data-stu-id="255c8-141">February 9, 2021</span></span>
<span data-ttu-id="255c8-142">版本 16.0.13628.20274 (setup.exe 版本 16.0.13628.20246)</span><span class="sxs-lookup"><span data-stu-id="255c8-142">Version 16.0.13628.20274 (setup.exe version 16.0.13628.20246)</span></span>
- <span data-ttu-id="255c8-143">新增驗證，以警告並防止 Windows 8.0 的安裝不受支援</span><span class="sxs-lookup"><span data-stu-id="255c8-143">Added validation to warn about and prevent unsupported installations on Windows 8.0</span></span>
- <span data-ttu-id="255c8-144">ARM64 裝置的可靠性修正</span><span class="sxs-lookup"><span data-stu-id="255c8-144">Reliability fixes for ARM64 devices</span></span>


## <a name="january-12-2021"></a><span data-ttu-id="255c8-145">2021 年 1 月 12 日</span><span class="sxs-lookup"><span data-stu-id="255c8-145">January 12, 2021</span></span>
<span data-ttu-id="255c8-146">版本 16.0.13530.20376 (setup.exe 版本 16.0.13530.20334)</span><span class="sxs-lookup"><span data-stu-id="255c8-146">Version 16.0.13530.20376 (setup.exe version 16.0.13530.20334)</span></span>
- <span data-ttu-id="255c8-147">修正已損毀或非標準產品註冊可能會導致 RemoveMSI 作業失敗的問題</span><span class="sxs-lookup"><span data-stu-id="255c8-147">Fixed an issue where corrupted or non-standard product registration could cause RemoveMSI operations to fail</span></span>

## <a name="december-21-2020"></a><span data-ttu-id="255c8-148">2020 年 12 月 21 日</span><span class="sxs-lookup"><span data-stu-id="255c8-148">December 21, 2020</span></span>
<span data-ttu-id="255c8-149">版本 16.0.13426.20370 (setup.exe 版本 16.0.13426.20352)</span><span class="sxs-lookup"><span data-stu-id="255c8-149">Version 16.0.13426.20370 (setup.exe version 16.0.13426.20352)</span></span>
- <span data-ttu-id="255c8-150">已修正從 PerpetualVL2019 通道 ProofingTools 的本機來源安裝失敗的問題</span><span class="sxs-lookup"><span data-stu-id="255c8-150">Fixed an issue where local source installations of ProofingTools from the PerpetualVL2019 channel were failing</span></span>
- <span data-ttu-id="255c8-151">已修正當您在現有安裝中新增非完整 Office 語言中的其他產品時，隨選即用用戶端嘗試自我更新的問題</span><span class="sxs-lookup"><span data-stu-id="255c8-151">Fixed an issue to ensure that the Click-To-Run client attempts a self-update when adding additional products in non-full Office languages to an existing installation</span></span>


## <a name="december-8-2020"></a><span data-ttu-id="255c8-152">2020 年 12 月 8 日</span><span class="sxs-lookup"><span data-stu-id="255c8-152">December 8, 2020</span></span>
<span data-ttu-id="255c8-153">版本 16.0.13426.20308 (setup.exe 版本 16.0.13426.20308) </span><span class="sxs-lookup"><span data-stu-id="255c8-153">Version 16.0.13426.20308 (setup.exe version 16.0.13426.20308)</span></span>
- <span data-ttu-id="255c8-154">已修正如果裝置的 Office 產品是從非Perpetual 2019 的通道進行安裝，則 [下載] 模式會封鎖 Perpetual 2019 的通道下載之問題。</span><span class="sxs-lookup"><span data-stu-id="255c8-154">Fixed an issue where Download mode was blocking Perpetual 2019 channel downloads if the device had an Office product installed from a non-Perpetual 2019 channel.</span></span>
- <span data-ttu-id="255c8-155">已修正針對透過 [下載] 模式所建立的本機來源，在設定 XML 中指定明確的 [版本]，將會導致 [結構移轉] 失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="255c8-155">Fixed an issue where an Architecture Migration would fail against a local source created through Download mode that had specified an explicit Version in the configuration XML.</span></span>


## <a name="november-23-2020"></a><span data-ttu-id="255c8-156">2020 年 11 月 23 日</span><span class="sxs-lookup"><span data-stu-id="255c8-156">November 23, 2020</span></span>
<span data-ttu-id="255c8-157">版本 16.0.13328.20420 (setup.exe 版本 16.0.13328.20420)</span><span class="sxs-lookup"><span data-stu-id="255c8-157">Version 16.0.13328.20420 (setup.exe version 16.0.13328.20420)</span></span>
- <span data-ttu-id="255c8-158">已修正 /download 模式未下載校訂工具的問題</span><span class="sxs-lookup"><span data-stu-id="255c8-158">Fixed an issue where proofing tools were not being downloaded by /download mode</span></span>
- <span data-ttu-id="255c8-159">已修正在停權使用者內容中執行時，/download 模式失敗的問題</span><span class="sxs-lookup"><span data-stu-id="255c8-159">Fixed an issue where /download mode was failing when run in unelevated user context</span></span>
- <span data-ttu-id="255c8-160">已修正在組態 XML 中指定 Version 屬性時，導致 /download 模式中下載不完全的問題</span><span class="sxs-lookup"><span data-stu-id="255c8-160">Fixed an issue where specifying a Version attribute in configuration XML resulted in an incomplete download in /download mode</span></span>
- <span data-ttu-id="255c8-161">已修正在解壓縮時，Office 部署工具未命名為 “setup.exe” 的問題</span><span class="sxs-lookup"><span data-stu-id="255c8-161">Fixed an issue where the Office Deployment Tool was not named “setup.exe” when extracted</span></span>
- <span data-ttu-id="255c8-162">已修正在組態 XML 中提供 Channel 屬性時，安裝來源優先順序的問題</span><span class="sxs-lookup"><span data-stu-id="255c8-162">Fixed an issue regarding installation source prioritization when a Channel attribute is provided in configuration XML</span></span>

## <a name="november-10-2020"></a><span data-ttu-id="255c8-163">2020 年 11 月 10 日</span><span class="sxs-lookup"><span data-stu-id="255c8-163">November 10, 2020</span></span>
<span data-ttu-id="255c8-164">版本 16.0.13328.20356 (setupODT.exe 版本 16.0.13328.20336)</span><span class="sxs-lookup"><span data-stu-id="255c8-164">Version 16.0.13328.20356 (setupODT.exe version 16.0.13328.20336)</span></span>
- <span data-ttu-id="255c8-165">可靠性和復原改善</span><span class="sxs-lookup"><span data-stu-id="255c8-165">Reliability and resiliency improvements</span></span>
- <span data-ttu-id="255c8-166">為了防止混淆及更輕鬆地診斷安裝程式錯誤，ODT 現在預設稱為 setupODT。</span><span class="sxs-lookup"><span data-stu-id="255c8-166">To prevent confusion and more easily diagnose setup errors, the ODT is now named setupODT.exe by default</span></span>

## <a name="october-29-2020"></a><span data-ttu-id="255c8-167">2020 年 10 月 29 日</span><span class="sxs-lookup"><span data-stu-id="255c8-167">October 29, 2020</span></span>
<span data-ttu-id="255c8-168">版本 16.0.13328.20292 (setup.exe 版本 16.0.13328.20290)</span><span class="sxs-lookup"><span data-stu-id="255c8-168">Version 16.0.13328.20292 (setup.exe version 16.0.13328.20290)</span></span>
- <span data-ttu-id="255c8-169">解決使用 RemoveMSI 時，某些 Office 2007 產品可能會意外封鎖安裝的問題</span><span class="sxs-lookup"><span data-stu-id="255c8-169">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>

## <a name="october-14-2020"></a><span data-ttu-id="255c8-170">2020 年 10 月14 日</span><span class="sxs-lookup"><span data-stu-id="255c8-170">October 14, 2020</span></span>
<span data-ttu-id="255c8-171">版本 16.0.13231.20368 (setup.exe 版本 16.0.13231.20350)</span><span class="sxs-lookup"><span data-stu-id="255c8-171">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="255c8-172">當沒有指定頻道時，預設情况下所有產品都將使用每月通道</span><span class="sxs-lookup"><span data-stu-id="255c8-172">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="255c8-173">改善從含有其他 DLL 的目錄執行 ODT 時的安全性</span><span class="sxs-lookup"><span data-stu-id="255c8-173">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="255c8-174">可靠性和恢復改善</span><span class="sxs-lookup"><span data-stu-id="255c8-174">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="255c8-175">2020 年 6 月 9 日</span><span class="sxs-lookup"><span data-stu-id="255c8-175">June 9, 2020</span></span>

<span data-ttu-id="255c8-176">版本 16.0.12827.20268 (setup.exe 版本 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="255c8-176">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="255c8-177">在未指定頻道時，目前的通道即為預設的頻道。</span><span class="sxs-lookup"><span data-stu-id="255c8-177">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="255c8-178">新增每月企業通道的支援</span><span class="sxs-lookup"><span data-stu-id="255c8-178">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="255c8-179">新增新頻道名稱的支援</span><span class="sxs-lookup"><span data-stu-id="255c8-179">Added support for new channel names</span></span>
- <span data-ttu-id="255c8-180">即使在無法使用部分語言資源時，如可能，可持續安裝其他復原功能</span><span class="sxs-lookup"><span data-stu-id="255c8-180">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="255c8-181">MSIRemove 的功能已展開，可移除 Office 2007 產品</span><span class="sxs-lookup"><span data-stu-id="255c8-181">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="255c8-182">MSIRemove 的功能已展開，可移除 Access 資料庫引擎</span><span class="sxs-lookup"><span data-stu-id="255c8-182">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="255c8-183">2020 年 4 月 15 日</span><span class="sxs-lookup"><span data-stu-id="255c8-183">April 15, 2020</span></span>

<span data-ttu-id="255c8-184">版本 16.0.12624.20320 (setup.exe 版本 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="255c8-184">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="255c8-185">新增對於 Windows 7 特定生命週期結束 Office 版本的支援</span><span class="sxs-lookup"><span data-stu-id="255c8-185">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="255c8-186">已修正可能無法如預期方式套用自訂設定的問題</span><span class="sxs-lookup"><span data-stu-id="255c8-186">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="255c8-187">已修正可能會意外下載無關 .cat 檔案的問題</span><span class="sxs-lookup"><span data-stu-id="255c8-187">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="255c8-188">2020 年 1 月 16 日</span><span class="sxs-lookup"><span data-stu-id="255c8-188">January 16, 2020</span></span>

<span data-ttu-id="255c8-189">版本 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="255c8-189">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="255c8-190">修正在安裝多個語言時，Office 安裝 UI 可能會以不正確的語言顯示的問題</span><span class="sxs-lookup"><span data-stu-id="255c8-190">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="255c8-191">修正在安裝某些校訂工具套件之後，Office 安裝可能會非預期地失敗的問題</span><span class="sxs-lookup"><span data-stu-id="255c8-191">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="255c8-192">新增支援以選擇性地控制 [Bing 中的 Microsoft Search](/deployoffice/microsoft-search-bing) 的初始部署</span><span class="sxs-lookup"><span data-stu-id="255c8-192">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](/deployoffice/microsoft-search-bing)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="255c8-193">2019 年 10 月 31 日</span><span class="sxs-lookup"><span data-stu-id="255c8-193">October 31, 2019</span></span>

<span data-ttu-id="255c8-194">版本 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="255c8-194">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="255c8-195">修正了允許商務用 Skype 基本版 2019 安裝 2019 永久企業版大量授權產品的問題</span><span class="sxs-lookup"><span data-stu-id="255c8-195">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="255c8-196">修正了使用 Proxy 時，在某些情況下，可能會導致 ODT 下載模式意外失敗的問題</span><span class="sxs-lookup"><span data-stu-id="255c8-196">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="255c8-197">新功能可讓 ODT 下載模式透過 HTTP 連接埠 80 以外的埠來下載</span><span class="sxs-lookup"><span data-stu-id="255c8-197">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="255c8-198">2019 年 7 月 10 日</span><span class="sxs-lookup"><span data-stu-id="255c8-198">July 10, 2019</span></span>

<span data-ttu-id="255c8-199">版本 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="255c8-199">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="255c8-200">隨 Office 2019 一起安裝時，新增了對其他產品的支援：Access Runtime，商務用 Skype 基本版。</span><span class="sxs-lookup"><span data-stu-id="255c8-200">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="255c8-201">從 MSI 升級時，新增對獨立產品之條件式件安裝的支援。</span><span class="sxs-lookup"><span data-stu-id="255c8-201">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="255c8-202">2019 年 4 月 23 日</span><span class="sxs-lookup"><span data-stu-id="255c8-202">April 23, 2019</span></span>

<span data-ttu-id="255c8-203">版本 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="255c8-203">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="255c8-204">已修正 RemoveMSI = True 清除相關登錄設定的錯誤。</span><span class="sxs-lookup"><span data-stu-id="255c8-204">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="255c8-205">更新錯誤碼，為非預期的失敗 (E_UNEXPECTED) 提供其他詳細資料。</span><span class="sxs-lookup"><span data-stu-id="255c8-205">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="255c8-206">2019 年 4 月 16 日</span><span class="sxs-lookup"><span data-stu-id="255c8-206">April 16 2019</span></span>

<span data-ttu-id="255c8-207">版本 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="255c8-207">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="255c8-208">支援使用新的 MigrateArch 屬性將 32 位元 C2R 升級到 64 位元 C2R。</span><span class="sxs-lookup"><span data-stu-id="255c8-208">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="255c8-209">更新了 /configure 的邏輯，允許存取儲存在 Web 位置 (http 和 https) 中的設定 XML 文件。</span><span class="sxs-lookup"><span data-stu-id="255c8-209">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="255c8-210">已新增 MatchInstalled 為新屬性，允許 ODT 在新增其他產品或語言時比對現有版本。</span><span class="sxs-lookup"><span data-stu-id="255c8-210">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="255c8-211">2019 年 3 月 13 日</span><span class="sxs-lookup"><span data-stu-id="255c8-211">March 13, 2019</span></span>

<span data-ttu-id="255c8-212">版本 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="255c8-212">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="255c8-213">升級與移轉案例的增強功能。</span><span class="sxs-lookup"><span data-stu-id="255c8-213">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="255c8-214">2019 年 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="255c8-214">January 14, 2019</span></span>

<span data-ttu-id="255c8-215">版本 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="255c8-215">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="255c8-216">部署設定的記錄及遙測改良功能。</span><span class="sxs-lookup"><span data-stu-id="255c8-216">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="255c8-217">相關連結</span><span class="sxs-lookup"><span data-stu-id="255c8-217">Related links</span></span>

[<span data-ttu-id="255c8-218">ODT 下載中心</span><span class="sxs-lookup"><span data-stu-id="255c8-218">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)