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
ms.openlocfilehash: b0f53ad140880f7ef173efc544892d56f0658bb1
ms.sourcegitcommit: 917d87752cde322a74251b6d23b12815587d1e51
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 08/16/2019
ms.locfileid: "36444941"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="25903-103">Office 部署工具的發行記錄</span><span class="sxs-lookup"><span data-stu-id="25903-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="25903-104">Office 部署工具 (ODT) 是一種命令列工具，可用來將像 Office 365 專業增強版這類的 Office 隨選即用版本下載並部署到用戶端電腦。</span><span class="sxs-lookup"><span data-stu-id="25903-104">The Office 2016 Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Office 365 ProPlus to your client computers.</span></span> 


<span data-ttu-id="25903-105">ODT 能讓您進一步控制 Office 安裝。</span><span class="sxs-lookup"><span data-stu-id="25903-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="25903-106">您可以定義要安裝哪些產品及語言、這些產品的更新方式，以及是否要讓使用者看到安裝過程。</span><span class="sxs-lookup"><span data-stu-id="25903-106">The ODT gives you more control over an Office installation: you can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="25903-107">如需有關如何使用 ODT 的詳細資訊，請參閱 [Office 部署工具概觀](https://docs.microsoft.com/zh-TW/deployoffice/overview-of-the-office-2016-deployment-tool)。</span><span class="sxs-lookup"><span data-stu-id="25903-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/en-us/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="25903-108">**支援的作業系統**：Windows 10、Windows 7、Windows 8、Windows 8.1、Windows Server 2008 R2、Windows Server 2012 和 Windows Server 2012 R2</span><span class="sxs-lookup"><span data-stu-id="25903-108">The tool runs on Windows 10 , Windows 7, Windows 8, Windows 8.1, Windows Server 2008 R2, Windows Server 2012, and Windows Server 2012 R2.</span></span> 
 
 <span data-ttu-id="25903-109">**安裝指示**：下載檔案然後執行自我解壓縮可執行檔，其中會包含 Office 部署工具可執行檔 (setup.exe) 及範例組態檔 (configuration.xml)。</span><span class="sxs-lookup"><span data-stu-id="25903-109">After downloading the file, run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="25903-110">下載 Office 部署工具</span><span class="sxs-lookup"><span data-stu-id="25903-110">Download the Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)


## <a name="july-10-2019"></a><span data-ttu-id="25903-111">2019 年 7 月 10 日</span><span class="sxs-lookup"><span data-stu-id="25903-111">July 10, 2019</span></span>

<span data-ttu-id="25903-112">版本 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="25903-112">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="25903-113">隨 Office 2019 一起安裝時，新增了對其他產品的支援：Access Runtime，商務用 Skype 基本版。</span><span class="sxs-lookup"><span data-stu-id="25903-113">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="25903-114">從 MSI 升級時，新增對獨立產品之條件式件安裝的支援。</span><span class="sxs-lookup"><span data-stu-id="25903-114">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="25903-115">2019 年 4 月 23 日</span><span class="sxs-lookup"><span data-stu-id="25903-115">April 23, 2019</span></span>

<span data-ttu-id="25903-116">版本 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="25903-116">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="25903-117">已修正 RemoveMSI = True 清除相關登錄設定的錯誤。</span><span class="sxs-lookup"><span data-stu-id="25903-117">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="25903-118">更新錯誤碼，為非預期的失敗 (E_UNEXPECTED) 提供其他詳細資料。</span><span class="sxs-lookup"><span data-stu-id="25903-118">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="25903-119">2019 年 4 月 16 日</span><span class="sxs-lookup"><span data-stu-id="25903-119">April 16, 2019</span></span>

<span data-ttu-id="25903-120">版本 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="25903-120">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="25903-121">支援使用新的 MigrateArch 屬性將 32 位元 C2R 升級到 64 位元 C2R。</span><span class="sxs-lookup"><span data-stu-id="25903-121">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="25903-122">更新了 /configure 的邏輯，允許存取儲存在 Web 位置 (http 和 https) 中的設定 XML 文件。</span><span class="sxs-lookup"><span data-stu-id="25903-122">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="25903-123">已新增 MatchInstalled 為新屬性，允許 ODT 在新增其他產品或語言時比對現有版本。</span><span class="sxs-lookup"><span data-stu-id="25903-123">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="25903-124">2019 年 3 月 13 日</span><span class="sxs-lookup"><span data-stu-id="25903-124">March 13, 2019</span></span>

<span data-ttu-id="25903-125">版本 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="25903-125">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="25903-126">升級與移轉案例的增強功能。</span><span class="sxs-lookup"><span data-stu-id="25903-126">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="25903-127">2019 年 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="25903-127">January 14, 2019</span></span>

<span data-ttu-id="25903-128">版本 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="25903-128">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="25903-129">部署設定的記錄及遙測改良功能。</span><span class="sxs-lookup"><span data-stu-id="25903-129">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="25903-130">相關連結</span><span class="sxs-lookup"><span data-stu-id="25903-130">Related links</span></span>

[<span data-ttu-id="25903-131">ODT 版本資訊</span><span class="sxs-lookup"><span data-stu-id="25903-131">ODT Release notes</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)