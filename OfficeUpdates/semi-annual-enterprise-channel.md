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
ms.openlocfilehash: 6b50195e2e84292b0b4b1e259254592f2c4a591b
ms.sourcegitcommit: 568fdf9ae96367ef3a4f601128df80944dd265a7
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 02/10/2021
ms.locfileid: "50173652"
---
# <a name="release-notes-for-semi-annual-enterprise-channel"></a><span data-ttu-id="4e59f-103">半年企業通道的版本資訊</span><span class="sxs-lookup"><span data-stu-id="4e59f-103">Release notes for Semi-Annual Enterprise Channel</span></span>

<span data-ttu-id="4e59f-104">這些版本資訊提供新功能和非安全性更新的相關資訊，這些功能和非安全性更新包含 Microsoft 365 Apps 企業版、Microsoft 365 Apps 商務版，以及 Project 和 Visio 版的傳統型應用程式訂閱版本的半年企業通道更新。</span><span class="sxs-lookup"><span data-stu-id="4e59f-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel updates for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="4e59f-105">我們會變更 Microsoft 365 應用程式的更新通道，包括新增新的更新通道 (每月企業通道)，並變更現有的更新通道名稱。</span><span class="sxs-lookup"><span data-stu-id="4e59f-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="4e59f-106">如需深入了解，[請閱讀本文](https://go.microsoft.com/fwlink/p/?linkid=2127441)。</span><span class="sxs-lookup"><span data-stu-id="4e59f-106">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
>
>- <span data-ttu-id="4e59f-107">當使用半年企業通道的使用者透過 Office 入口網站下載並安裝 Microsoft 365 Apps 到 Windows 10 上時，OneNote 2016 依預設將包括在其中。</span><span class="sxs-lookup"><span data-stu-id="4e59f-107">OneNote 2016 will now be included by default when a user on the Semi-Annual Enterprise Channel downloads and installs Microsoft 365 Apps on Windows 10 from the Office Portal.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-february-09"></a><span data-ttu-id="4e59f-109">版本 2008：2 月 9 日</span><span class="sxs-lookup"><span data-stu-id="4e59f-109">Version 2008: February 09</span></span>
<span data-ttu-id="4e59f-110">*版本 2008 (組建 13127.21216)*</span><span class="sxs-lookup"><span data-stu-id="4e59f-110">*Version 2008 (Build 13127.21216)*</span></span>

<span data-ttu-id="4e59f-111">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4e59f-111">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="4e59f-113">解決的問題</span><span class="sxs-lookup"><span data-stu-id="4e59f-113">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="4e59f-114">Excel</span><span class="sxs-lookup"><span data-stu-id="4e59f-114">Excel</span></span>

- <span data-ttu-id="4e59f-115">修正了當開啟具有無效檔案内容 (建立時間、修改時間等) 的 UNC 檔案時，Excel 會意外關閉的問題</span><span class="sxs-lookup"><span data-stu-id="4e59f-115">Fixed an issue where Excel would close unexpectedly when opening UNC files that have invalid file attributes (creation time, modified time, etc.)</span></span>


- <span data-ttu-id="4e59f-116">我們修正了將圖表從 Excel 複製並貼到 Word 或 PowerPoint 時，小數位和千分位分隔符號設定不會執行的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-116">We fixed an issue where decimal and thousands separators settings would not carry over when copying a chart from Excel and pasting into Word or PowerPoint.</span></span>


- <span data-ttu-id="4e59f-117">我們修正了執行涉及樞紐分析表範圍格式設定的巨集，在每次執行巨集時效能都會變差的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-117">We fixed an issue where the performance of running a macro involving PivotTable range formatting would get worse each time the macro is run.</span></span>


- <span data-ttu-id="4e59f-118">我們修正了將工作表複製或移動到另一個活頁簿時，設定格式化的條件規則的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-118">We fixed an issue where conditional formatting rules were dropped when copying or moving sheets to another workbook.</span></span>


- <span data-ttu-id="4e59f-119">我們修正了當應用程式啟動時停用開始頁面，使用者無法將敏感度標籤套用至 Excel 檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-119">We fixed an issue where users were unable to apply sensitivity labels to Excel files when the start screen on app boot was disabled.</span></span>


- <span data-ttu-id="4e59f-120">我們修正了從 OneDrive 同步處理資料夾開啟雲端檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-120">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="outlook"></a><span data-ttu-id="4e59f-121">Outlook</span><span class="sxs-lookup"><span data-stu-id="4e59f-121">Outlook</span></span>

- <span data-ttu-id="4e59f-122">解決在新增或儲存附件時，會導致 Outlook 停止運作的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-122">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="4e59f-123">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4e59f-123">PowerPoint</span></span>

- <span data-ttu-id="4e59f-124">我們已修正一個問題，即在 QAT 中新增的字型大小命令在更新時，會自動完成到最接近的已定義字型大小。</span><span class="sxs-lookup"><span data-stu-id="4e59f-124">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="4e59f-125">修正了使用保留來源格式設定選項複製及貼上投影片時，有時會將此設定意外地複製到新的投影片母片的問題</span><span class="sxs-lookup"><span data-stu-id="4e59f-125">Fixed an issue where copy and paste of a slide with 'keep source formatting' option would sometimes copy over a new slide master unexpectedly</span></span>


### <a name="word"></a><span data-ttu-id="4e59f-126">Word</span><span class="sxs-lookup"><span data-stu-id="4e59f-126">Word</span></span>

- <span data-ttu-id="4e59f-127">我們已修正有時開啟 Word 文件可能會顯示錯誤對話方塊的追蹤修訂問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-127">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>


- <span data-ttu-id="4e59f-128">我們修正了從 OneDrive 同步處理資料夾開啟雲端檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-128">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="office-suite"></a><span data-ttu-id="4e59f-129">Office 套件</span><span class="sxs-lookup"><span data-stu-id="4e59f-129">Office Suite</span></span>

- <span data-ttu-id="4e59f-130">修正了無法在 Office 中成功開啟檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-130">Fixed an issue that prevented successful open of a file in Office.</span></span>


- <span data-ttu-id="4e59f-131">修正了使用複製格式將包含草繪外框的文件套用至連接器可能會損毀的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-131">Fixed an issue where documents containing Sketched outlines applied to connectors via Format Painter could become corrupted.</span></span>



[//]: # (請勿移除 BUGDETAILS 內容結尾)

## <a name="version-2002-february-09"></a><span data-ttu-id="4e59f-133">版本 2002：2 月 9 日</span><span class="sxs-lookup"><span data-stu-id="4e59f-133">Version 2002: February 09</span></span>
<span data-ttu-id="4e59f-134">*版本 2002 (組建 12527.21594)*</span><span class="sxs-lookup"><span data-stu-id="4e59f-134">*Version 2002 (Build 12527.21594)*</span></span>

<span data-ttu-id="4e59f-135">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4e59f-135">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="4e59f-137">解決的問題</span><span class="sxs-lookup"><span data-stu-id="4e59f-137">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="4e59f-138">Office 套件</span><span class="sxs-lookup"><span data-stu-id="4e59f-138">Office Suite</span></span>

- <span data-ttu-id="4e59f-139">修正了使用複製格式將包含草繪外框的文件套用至連接器可能會損毀的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-139">Fixed an issue where documents containing Sketched outlines applied to connectors via Format Painter could become corrupted.</span></span>



[//]: # (請勿移除 BUGDETAILS 內容結尾)

## <a name="version-1908-february-09"></a><span data-ttu-id="4e59f-141">版本 1908：2 月 9 日</span><span class="sxs-lookup"><span data-stu-id="4e59f-141">Version 1908: February 09</span></span>
<span data-ttu-id="4e59f-142">*版本 1908 (組建 11929.21008)*</span><span class="sxs-lookup"><span data-stu-id="4e59f-142">*Version 1908 (Build 11929.21008)*</span></span>

<span data-ttu-id="4e59f-143">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4e59f-143">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2008-january-12"></a><span data-ttu-id="4e59f-144">版本 2008：1 月 12 日</span><span class="sxs-lookup"><span data-stu-id="4e59f-144">Version 2008: January 12</span></span>
<span data-ttu-id="4e59f-145">*版本 2008 (組建 13127.21064)*</span><span class="sxs-lookup"><span data-stu-id="4e59f-145">*Version 2008 (Build 13127.21064)*</span></span>

<span data-ttu-id="4e59f-146">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4e59f-146">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="4e59f-148">功能更新</span><span class="sxs-lookup"><span data-stu-id="4e59f-148">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="4e59f-149">Access</span><span class="sxs-lookup"><span data-stu-id="4e59f-149">Access</span></span>

- <span data-ttu-id="4e59f-150">**在查詢設計工具、SQL 檢視和關聯視窗中工作時更具生產力：** 在資料表上按一下滑鼠右鍵即可開啟、設計、調整大小及隱藏它。</span><span class="sxs-lookup"><span data-stu-id="4e59f-150">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="4e59f-151">在 SQL 檢視中搜尋及取代文字。</span><span class="sxs-lookup"><span data-stu-id="4e59f-151">Search and replace text in SQL View.</span></span> <span data-ttu-id="4e59f-152">在 [關聯圖] 視窗中選取多個資料表。</span><span class="sxs-lookup"><span data-stu-id="4e59f-152">Select multiple tables in the Relationships window.</span></span>

- <span data-ttu-id="4e59f-153">**按幾下就能新增資料表：** 使用 [新增資料表] 工作窗格，當您工作時，該窗格會保持開啟狀態，以便將資料表新增至關聯和查詢。</span><span class="sxs-lookup"><span data-stu-id="4e59f-153">**Add tables with fewer clicks:** Use the Add Tables task pane, which stays open while you work, to add tables to relationships and queries.</span></span> [<span data-ttu-id="4e59f-154">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-154">Learn more</span></span>](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)

### <a name="excel"></a><span data-ttu-id="4e59f-155">Excel</span><span class="sxs-lookup"><span data-stu-id="4e59f-155">Excel</span></span>

- <span data-ttu-id="4e59f-156">**您最愛的 Excel 函數計算速度提升了：** SUMIFS、AVERAGEIFS、COUNTIFS、MAXIFS 和 MINIFS 函數現在比以往更快了。</span><span class="sxs-lookup"><span data-stu-id="4e59f-156">**Your favorite Excel functions just got faster:** The SUMIFS, AVERAGEIFS, COUNTIFS, MAXIFS, and MINIFS functions are much faster than ever before.</span></span> <span data-ttu-id="4e59f-157">更快速地前往底線。</span><span class="sxs-lookup"><span data-stu-id="4e59f-157">Get to the bottom line more quickly.</span></span> <span data-ttu-id="4e59f-158">立即試用。</span><span class="sxs-lookup"><span data-stu-id="4e59f-158">Try one now.</span></span>

- <span data-ttu-id="4e59f-159">**RealTimeData (RTD) 的改進** 在 Office 365 版本 2002 的每月通道或更新版本中，Excel RealTimeData (RTD) 函數速度快于 Excel 2010 計算試算表中的資料。</span><span class="sxs-lookup"><span data-stu-id="4e59f-159">**Realtimedata (RTD) improvements:** In Office 365 version 2002 monthly channel and later, Excel's RealTimeData (RTD) function is much faster than Excel 2010 calculating data in the spreadsheet.</span></span> <span data-ttu-id="4e59f-160">我們在其基礎記憶體和資料結構中移除了瓶頸，並使其成為安全執行緒，讓它可在多執行緒重新計算 (MTR) 的所有可用執行緒上計算。</span><span class="sxs-lookup"><span data-stu-id="4e59f-160">We removed bottlenecks in its underlying memory and data structures as well as made it thread-safe to allow  it to be calculated on all available threads of Multithreaded recalculation (MTR).</span></span>

- <span data-ttu-id="4e59f-161">**改善地圖圖表：** 我們讓地圖圖表變得更好，方法是將地圖圖表與可顯示有關對應位置豐富資訊的 Excel 地理資料類型整合。</span><span class="sxs-lookup"><span data-stu-id="4e59f-161">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="4e59f-162">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-162">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="4e59f-163">**挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。</span><span class="sxs-lookup"><span data-stu-id="4e59f-163">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="4e59f-164">在[部落格文章](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="4e59f-164">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="4e59f-165">**在 Excel 中建立來自 Power BI 資料的樞紐分析表：** 您可以在 Excel 中建立樞紐分析表，只要按幾下滑鼠，就能連線到儲存在 Power BI 的樞紐分析表。</span><span class="sxs-lookup"><span data-stu-id="4e59f-165">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="4e59f-166"> 如此一來，您就能獲得樞紐分析表和 Power BI 的最佳效果。</span><span class="sxs-lookup"><span data-stu-id="4e59f-166">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="4e59f-167">使用安全 Power BI 資料集的樞紐分析表以計算、摘要及分析資料。</span><span class="sxs-lookup"><span data-stu-id="4e59f-167">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="4e59f-168">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-168">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)<br /><span data-ttu-id="4e59f-169">在[部落格文章](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="4e59f-169">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="4e59f-170">Outlook</span><span class="sxs-lookup"><span data-stu-id="4e59f-170">Outlook</span></span>

- <span data-ttu-id="4e59f-171">**挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。</span><span class="sxs-lookup"><span data-stu-id="4e59f-171">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="4e59f-172">在[部落格文章](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="4e59f-172">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="4e59f-173">**行事曆煥然一新：** 查看視覺更新，讓您的行事曆更容易流覽。</span><span class="sxs-lookup"><span data-stu-id="4e59f-173">**Calendar gets a makeover:** See visual updates that make your calendar easier to scan.</span></span> [<span data-ttu-id="4e59f-174">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-174">Learn more</span></span>](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br /><span data-ttu-id="4e59f-175">在[部落格文章](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="4e59f-175">See details in [blog post](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span></span>

- <span data-ttu-id="4e59f-176">**共用行事曆更新的速度更快：** 針對 Office 365 中的共用行事曆，Outlook 可以使用 REST API 更新這些行事曆。</span><span class="sxs-lookup"><span data-stu-id="4e59f-176">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="4e59f-177">開啟預覽以更快且更可靠地更新共用行事曆。</span><span class="sxs-lookup"><span data-stu-id="4e59f-177">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

- <span data-ttu-id="4e59f-178">**將電子郵件拖曳到您擁有的群組：** 從您的 [收件匣] 拖曳郵件和交談以將它們移動和複製。</span><span class="sxs-lookup"><span data-stu-id="4e59f-178">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="4e59f-179">您拖曳的郵件將會與所有群組成員共用。</span><span class="sxs-lookup"><span data-stu-id="4e59f-179">Messages you drag will be shared with all group members.</span></span><br /><span data-ttu-id="4e59f-180">在[部落格文章](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="4e59f-180">See details in [blog post](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span></span>

- <span data-ttu-id="4e59f-181">**加入會議而不需離開您的收件匣：** 不需切換至您的行事曆即可加入線上會議。</span><span class="sxs-lookup"><span data-stu-id="4e59f-181">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="4e59f-182">將行事曆釘選到 [待辦事項] 窗格之後，只要按一下就能加入任何會議。</span><span class="sxs-lookup"><span data-stu-id="4e59f-182">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span> [<span data-ttu-id="4e59f-183">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-183">Learn more</span></span>](https://support.office.com/article/d8baa9d5-0645-41b8-9f36-b498a6c36064 )

- <span data-ttu-id="4e59f-184">**受限 WiFi 網路的新體驗：** 是否曾經加入需要登入網頁的 WiFi 網路呢？</span><span class="sxs-lookup"><span data-stu-id="4e59f-184">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="4e59f-185">Outlook 現在會偵測這項要求並協助您取得連結。</span><span class="sxs-lookup"><span data-stu-id="4e59f-185">Outlook now detects this and helps you get connected.</span></span><br /><span data-ttu-id="4e59f-186">在[部落格文章](https://insider.office.com/zh-TW/blog/outlook-on-public-wi-fi-networks-just-got-easier)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="4e59f-186">See details in [blog post](https://insider.office.com/zh-TW/blog/outlook-on-public-wi-fi-networks-just-got-easier)</span></span>

- <span data-ttu-id="4e59f-187">**搜尋人員時取得電子郵件建議：** 當您在 [搜尋] 方塊中輸入人員的名稱時，最相關的電子郵件訊息會包括在您的搜尋建議中。</span><span class="sxs-lookup"><span data-stu-id="4e59f-187">**Get email suggestions when you search for a person:** When you type a person’s name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span> [<span data-ttu-id="4e59f-188">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-188">Learn more</span></span>](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

- <span data-ttu-id="4e59f-189">**更好的結果—瞬間：** 我們更新了搜尋體驗，讓這個版本比以往更聰明、更快速，且更可靠。</span><span class="sxs-lookup"><span data-stu-id="4e59f-189">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="4e59f-190">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-190">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

### <a name="powerpoint"></a><span data-ttu-id="4e59f-191">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4e59f-191">PowerPoint</span></span>

- <span data-ttu-id="4e59f-192">**jiffy 中的 Gif：** 一個投影片、一個圖文框。</span><span class="sxs-lookup"><span data-stu-id="4e59f-192">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="4e59f-193">在 PowerPoint 中輕鬆建立迴圈 Gif。</span><span class="sxs-lookup"><span data-stu-id="4e59f-193">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="4e59f-194">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-194">Learn more</span></span>](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)<br /><span data-ttu-id="4e59f-195">在[部落格文章](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="4e59f-195">See details in [blog post](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span></span>

- <span data-ttu-id="4e59f-196">**投影片連結:** 要求同事參與製作您的投影片組，讓他們直接在您需要協助的投影片上開始進行。</span><span class="sxs-lookup"><span data-stu-id="4e59f-196">**Link to a slide:** Ask a colleague to contribute to your slide deck, and start them directly on the slide you need help with.</span></span> [<span data-ttu-id="4e59f-197">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-197">Learn more</span></span>](https://support.office.com/article/4f5f3d5e-1674-4742-8cf1-9623050c19ef)<br /><span data-ttu-id="4e59f-198">在[部落格文章](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="4e59f-198">See details in [blog post](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)</span></span>

- <span data-ttu-id="4e59f-199">**挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。</span><span class="sxs-lookup"><span data-stu-id="4e59f-199">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="4e59f-200">在[部落格文章](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="4e59f-200">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="4e59f-201">**改善地圖圖表：** 我們讓地圖圖表變得更好，方法是將地圖圖表與可顯示有關對應位置豐富資訊的 Excel 地理資料類型整合。</span><span class="sxs-lookup"><span data-stu-id="4e59f-201">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="4e59f-202">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-202">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="4e59f-203">**更好的圖表：** 使用更完善的連接線和更平滑的筆跡轉換程式，您可以自信地用筆跡繪製您的想法。</span><span class="sxs-lookup"><span data-stu-id="4e59f-203">**Better diagrams:** With better connectors and a smoother ink conversion process you can ink your ideas more confidently.</span></span> [<span data-ttu-id="4e59f-204">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-204">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="4e59f-205">**改善的 PowerPoint 中的 Steam 影片效能：** 我們改善了 Microsoft Stream 影片的播放效能，將影片載入時間減至最少，以建立出流暢的觀賞體驗。</span><span class="sxs-lookup"><span data-stu-id="4e59f-205">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="4e59f-206">您可以在 Microsoft Stream 上使用公司影片來建立更完善的簡報。</span><span class="sxs-lookup"><span data-stu-id="4e59f-206">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

- <span data-ttu-id="4e59f-207">**使用 \@提及取得他人注意：** 在註解中使用 @提及功能，讓同事知道您需要他們提供建議。</span><span class="sxs-lookup"><span data-stu-id="4e59f-207">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="4e59f-208">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-208">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="4e59f-209">**在簡報時同步處理變更：** 即使簡報處於投影片放映模式，仍可即時同步處理所做的變更。</span><span class="sxs-lookup"><span data-stu-id="4e59f-209">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span> [<span data-ttu-id="4e59f-210">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-210">Learn more</span></span>](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br /><span data-ttu-id="4e59f-211">在[部落格文章](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="4e59f-211">See details in [blog post](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span></span>

- <span data-ttu-id="4e59f-212">**[註解]：** PowerPoint 中新增的註解體驗可讓您快速輕鬆地探索文件並新增註解。</span><span class="sxs-lookup"><span data-stu-id="4e59f-212">**Comments:** The new commenting experience in PowerPoint allows you to quickly and easily discover and add comments to your documents.</span></span> <span data-ttu-id="4e59f-213">使用註解錨定、解析、任務、已改進的提及通知等新功能使您的共同作業工作流程現代化。</span><span class="sxs-lookup"><span data-stu-id="4e59f-213">Modernize your collaboration workflows with new features like comment anchoring, resolve, tasks, improved mention notifications, and much more.</span></span> [<span data-ttu-id="4e59f-214">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-214">Learn more</span></span>](https://support.office.com/article/c0aa37bb-82cb-414c-872d-178946ff60ec)

### <a name="word"></a><span data-ttu-id="4e59f-215">Word</span><span class="sxs-lookup"><span data-stu-id="4e59f-215">Word</span></span>

- <span data-ttu-id="4e59f-216">**對筆跡使用套索：**[繪圖] 索引標籤上的 [套索] 工具，可協助您選取使用筆跡繪製的物件。</span><span class="sxs-lookup"><span data-stu-id="4e59f-216">**Lasso your ink:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="4e59f-217">選取個別筆劃或整個字。</span><span class="sxs-lookup"><span data-stu-id="4e59f-217">Select individual strokes, or whole words.</span></span> [<span data-ttu-id="4e59f-218">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-218">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="4e59f-219">**挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。</span><span class="sxs-lookup"><span data-stu-id="4e59f-219">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="4e59f-220">在[部落格文章](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="4e59f-220">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="4e59f-221">**改善地圖圖表：** 我們讓地圖圖表變得更好，方法是將地圖圖表與可顯示有關對應位置豐富資訊的 Excel 地理資料類型整合。</span><span class="sxs-lookup"><span data-stu-id="4e59f-221">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="4e59f-222">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-222">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="4e59f-223">**螢幕閱讀器的動作確認：** 確認動作是重要的協助工具要求。</span><span class="sxs-lookup"><span data-stu-id="4e59f-223">**Confirmation of action in screen readers:** Confirmation of action is an important accessibility requirement.</span></span> <span data-ttu-id="4e59f-224">隨著 Windows 引入新的通知 API 之後，我們現在就能通知螢幕助讀程式使用者的動作成功。</span><span class="sxs-lookup"><span data-stu-id="4e59f-224">With the introduction of a new Notification API from Windows, we are now able to alert screen reader users about the success of their actions.</span></span> <span data-ttu-id="4e59f-225">[剪下]、[複製]、[貼上]、[粗體]、[畫底線]、[復原]、[重做]、[自動校正] 和 [自動大小寫] 等功能都已公布給 Win32 Word 的朗讀程式使用者。</span><span class="sxs-lookup"><span data-stu-id="4e59f-225">Cut, copy, paste, bold, italic, underline, undo, redo, auto corrections, and auto-capitalizations are now all announced to Narrator users in Win32 Word.</span></span> <span data-ttu-id="4e59f-226">若要啟用此功能，請按 windows + ctrl + enter 以開啟朗讀程式。</span><span class="sxs-lookup"><span data-stu-id="4e59f-226">To enable this feature, turn on Narrator by pressing windows + ctrl + enter.</span></span><br /><span data-ttu-id="4e59f-227">在[部落格文章](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="4e59f-227">See details in [blog post](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)</span></span>

### <a name="office-suite"></a><span data-ttu-id="4e59f-228">Office 套件</span><span class="sxs-lookup"><span data-stu-id="4e59f-228">Office Suite</span></span>

- <span data-ttu-id="4e59f-229">**敏感度標籤**：您現在可以套用組織設定、用來提示您輸入自訂權限的敏感度標籤。</span><span class="sxs-lookup"><span data-stu-id="4e59f-229">**Sensitivity labels:** You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="4e59f-232">解決的問題</span><span class="sxs-lookup"><span data-stu-id="4e59f-232">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="4e59f-233">Access</span><span class="sxs-lookup"><span data-stu-id="4e59f-233">Access</span></span>

- <span data-ttu-id="4e59f-234">修正了使用 [縮放] 視窗時應用程式意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-234">Fixed an issue where the application would  close unexpectedly when using Zoom window.</span></span>


- <span data-ttu-id="4e59f-235">此修正會解決嘗試執行之前會產生「查詢太複雜」錯誤訊息的特定查詢的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-235">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>


- <span data-ttu-id="4e59f-236">此變更可修正當啟動縮放控制方塊 (Shift + F2) 以編輯文字時，可能會導致 Access 意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-236">This change fixes an issue that could cause Access to to close unexpectedly when launching the Zoom box (Shift + F2) to edit text.</span></span>


- <span data-ttu-id="4e59f-237">解決插入含有身分識別 (例如，自動編號) 欄位的連結 SQL 資料表的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-237">Resolved an issue with inserting linked SQL tables that include an identity (e.g. autonumber) field.</span></span>


- <span data-ttu-id="4e59f-238">我們已修正執行查詢的時間大約比預期完成時間兩倍久的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-238">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>


- <span data-ttu-id="4e59f-239">已修正問題；您應該可以呼叫日期/時間延伸資料類型至您的程式碼，而不會在您的應用程式中遇到任何問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-239">Fixed an issue to be able to call the Date/Time Extended data type into your code without experiencing any issues in your app.</span></span>


- <span data-ttu-id="4e59f-240">已修正問題；您現在可以還原為最新的 Access 版本，並使用 DAO/VBA 來管理及編輯十進位資料類型。</span><span class="sxs-lookup"><span data-stu-id="4e59f-240">Fixed an issue so you can now revert back to your most updated Access version, and use DAO/VBA to manage and edit a decimal data type.</span></span>


- <span data-ttu-id="4e59f-241">我們已修正嘗試使用 ODBC DSN 建立器時的錯誤問題</span><span class="sxs-lookup"><span data-stu-id="4e59f-241">We fixed an error issue when trying to use ODBC DSN builder</span></span>


- <span data-ttu-id="4e59f-242">已解决此問題 - 您現在可以使用 Office 的隨選即用應用程式外的 ODBC 驅動程式。</span><span class="sxs-lookup"><span data-stu-id="4e59f-242">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>


### <a name="excel"></a><span data-ttu-id="4e59f-243">Excel</span><span class="sxs-lookup"><span data-stu-id="4e59f-243">Excel</span></span>

- <span data-ttu-id="4e59f-244">自動文件分類可能已對處於唯讀模式的活頁簿發生。</span><span class="sxs-lookup"><span data-stu-id="4e59f-244">Automatic document classification may have occurred for workbooks that were in read-only mode.</span></span>


- <span data-ttu-id="4e59f-245">修正若您已從帳戶登出，嘗試建立資料連線時，可能會發生的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-245">Fixed an issue that could happen when trying to create a data connection if you have signed out from your account.</span></span>


- <span data-ttu-id="4e59f-246">修正 PivotDateFilter API 中的錯誤，其中的 'Before' 和 'After' 篩選條件是相反的。</span><span class="sxs-lookup"><span data-stu-id="4e59f-246">Fixed a bug with PivotDateFilter APIs in which 'Before' and 'After' filter conditions were reversed.</span></span>


- <span data-ttu-id="4e59f-247">解決了嘗試將樞紐分析表插入圖表時 Excel 可能會意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-247">Addressed an issue where Excel may close unexpectedly when attempting to insert PivotTables into a chart sheet.</span></span>


- <span data-ttu-id="4e59f-248">修正了從 Project 計劃匯出時無法編輯樞紐分析表和無法儲存活頁簿的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-248">Fixed an issue where pivot tables could not be edited and workbooks could not be saved if they were exported from Project plan.</span></span>


- <span data-ttu-id="4e59f-249">嘗試使用 LET() 函數儲存含有公式的檔案時發生錯誤。</span><span class="sxs-lookup"><span data-stu-id="4e59f-249">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>


- <span data-ttu-id="4e59f-250">我們修正了在某些情况下，以唯讀模式開啟文件時會出現多個訊息列。</span><span class="sxs-lookup"><span data-stu-id="4e59f-250">We fixed an issue where in some cases, multiple message bars were appearing when a file was opened in read-only mode.</span></span>


- <span data-ttu-id="4e59f-251">我們修正了當有許多重複的欄標題值時，大綱子總計可能停止運作的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-251">We fixed an issue where outline sub-totals could stop working when there were many duplicate column header values.</span></span>


- <span data-ttu-id="4e59f-252">修正了唯讀書籍在開啟時無法再重新整理樞紐分析表資料的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-252">Fixed an issue where read-only books would no longer refresh pivot table data when opened.</span></span>


- <span data-ttu-id="4e59f-253">這項變更提供下列問題的修正程式：從 OneDrive 本機同步處理資料夾插入檔案時，Excel 的 [插入物件] 不會顯示正確的圖示。</span><span class="sxs-lookup"><span data-stu-id="4e59f-253">This change provides a fix for the following issue: Excel "Insert Object" does not show correct icon when inserts a file from OneDrive local sync folder.</span></span>


- <span data-ttu-id="4e59f-254">我們已修正在多執行緒重新計算期間進行群組原則物件更新 (例如，透過遠端群組原則重新整理) 時，Excel 將停止運作的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-254">We fixed an issue where Excel would stop working when there is a Group Policy Object update (e.g. via Remote Group Policy Refresh) during multithreaded recalc.</span></span>


- <span data-ttu-id="4e59f-255">我們修正了當使用者對超過 255 列使用小計函數時 Excel 將停止運作的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-255">We fixed an issue where Excel would stop working when users use the subtotal function on more than 255 columns.</span></span>


- <span data-ttu-id="4e59f-256">當內容從 Excel 複製並使用 [内嵌] 選項貼上到 PowerPoint 中時，改進了 PowerPoint 中的文字字元間距調整。</span><span class="sxs-lookup"><span data-stu-id="4e59f-256">Improved text kerning in PowerPoint when when content is copied from Excel and pasted into PowerPoint with the Embed option.</span></span>


- <span data-ttu-id="4e59f-257">修正了在 PowerPivot 中封鎖從 [資料表預覽] 和 [査詢編輯器] 切換的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-257">Fixed an issue that would prevent switching from Table Preview and the Query Editor in PowerPivot.</span></span>


- <span data-ttu-id="4e59f-258">我們已修正使用者無法直接從 SharePoint 開啟 atomsvc (UTF8+BOM) 檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-258">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="4e59f-259">修正了客戶在共同撰寫時會錯誤地得到有關文件新版本通知的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-259">Fixed an issue where customers would incorrectly get notified about a new version of the file when coauthoring.</span></span>


- <span data-ttu-id="4e59f-260">修正了即使用 IME 和覆寫模式將錯誤地推進額外的字元的編輯問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-260">Fixed an editing issue where using IME with Overwrite mode would incorrectly advance extra characters.</span></span>


- <span data-ttu-id="4e59f-261">修復了將即時資料與多執行緒 recalc 功能結合使用時出現的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-261">Fixed an issue when using real time data in conjunction with multithreaded recalc functionality.</span></span>


- <span data-ttu-id="4e59f-262">修正當使用特定 Windows 安全性漏洞防護設定(SimExec、CallerCheck) 時，Excel 無法正常啟動或當機的問題</span><span class="sxs-lookup"><span data-stu-id="4e59f-262">Fixes an issue where Excel would fail to launch or crash unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use</span></span>


- <span data-ttu-id="4e59f-263">修正使用「複製格式」時，在某些情況中 Excel 可能會意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-263">Fixed an issue where Excel could close unexpectedly in certain circumstances when using the Format Painter.</span></span>


- <span data-ttu-id="4e59f-264">我們修正了使用者無法修改樞紐分析表篩選的問題，因為它已設定為Analysis Services數據庫中不再存在的值。</span><span class="sxs-lookup"><span data-stu-id="4e59f-264">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


- <span data-ttu-id="4e59f-265">修正了當凍結工作表頂端列之後，Excel 可能會在使用 [快速分析] 時意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-265">Fixed an issue where Excel could close unexpectedly when using the Quick Analysis after freezing the top row of the sheet.</span></span>


- <span data-ttu-id="4e59f-266">我們已修正載入活頁簿之後特定功能可能會發生錯誤結果的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-266">We fixed an issue where certain functions would have an incorrect result after loading a workbook.</span></span>


- <span data-ttu-id="4e59f-267">我們已修正應用程式意外終止 (與 XLAM 增益集參照和命名範圍相關的問題) 的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-267">We fixed an issue where the application would terminate unexpectedly which was related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="4e59f-268">我們已修正使用巨集來設定某個範圍的 FormulaR1C1 屬性時，如果圖表工作表為作用中工作表，則儲存格參考會不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-268">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>


- <span data-ttu-id="4e59f-269">修正可能會導致「嘗試計算一個或多個公式時，Excel 資源不足」錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-269">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="4e59f-270">修正當 Office 語言設定為西班牙文時，其中資料驗證清單可能無法顯示清單中所有項目的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-270">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="4e59f-271">我們已修正在重新整理 OLAP 樞紐分析表時，可能會導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-271">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="4e59f-272">已修正當儲存至 SharePoint/OneDrive 時，會導致自訂功能區索引標籤 CustomUI XML 的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-272">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>


- <span data-ttu-id="4e59f-273">已修正當 Excel 視窗透過 Teams 共用時，使用 Ctrl + Shift + 方向鍵滑動後，Excel 可能會無法回應的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-273">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>


- <span data-ttu-id="4e59f-274">已修正在某些情況下，按一下同一個活頁簿中某個位置的超連結會導致活頁簿被隱藏的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-274">Fixed an issue where in some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>


- <span data-ttu-id="4e59f-275">在某些情況下，Application.Evaluate (VBA) 無法在使用者定義的函數中運作。</span><span class="sxs-lookup"><span data-stu-id="4e59f-275">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>


- <span data-ttu-id="4e59f-276">在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。</span><span class="sxs-lookup"><span data-stu-id="4e59f-276">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>


- <span data-ttu-id="4e59f-277">已修正在複製含有樞紐分析表的工作表後，會於某些情況下導致 Excel 意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-277">Fixed an issue which would cause Excel to close unexpectedly in some cases after copying a sheet containing a PivotTable.</span></span>


- <span data-ttu-id="4e59f-278">已修正當檔案路徑太長時，在檔案重新開啟之後外部連結會停止運作的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-278">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>


- <span data-ttu-id="4e59f-279">修正了將即時資料與多執行緒重新計算功能結合使用時，可能會導致應用程式意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-279">Fixed an issue when using real time data in conjunction with multithreaded recalc functionality could cause the application to close unexpectedly.</span></span>


- <span data-ttu-id="4e59f-280">已解決當來源活頁簿關閉時，外部連結無法在填滿時更新的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-280">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>


- <span data-ttu-id="4e59f-281">修正當活頁簿包含使用 IFNA () 的公式時，會導致活頁簿損毀警告的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-281">Fixed an issue that could cause a warning about a corrupt workbook if it contained formulas using IFNA().</span></span>


- <span data-ttu-id="4e59f-282">我們修正了Power Pivot 現在將成功識別定位字元分隔符號的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-282">We fixed an issue where Power Pivot will now successfully recognize tab delimiter.</span></span>


### <a name="onenote"></a><span data-ttu-id="4e59f-283">OneNote</span><span class="sxs-lookup"><span data-stu-id="4e59f-283">OneNote</span></span>

- <span data-ttu-id="4e59f-284">透過在資訊列中通知使用者有關 Microsoft OneNote 中的暫時調整之資訊，將協助改善在全球高使用量期間的同步處理與服務可用性。</span><span class="sxs-lookup"><span data-stu-id="4e59f-284">Inform users through the InfoBar about temporary adjustments in Microsoft OneNote that will help improve sync and service availability during high worldwide usage.</span></span>


- <span data-ttu-id="4e59f-285">透過暫時調整 OneNote 2016 中的同步處理頻率，來改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="4e59f-285">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>


- <span data-ttu-id="4e59f-286">改善了共同撰寫狀態的偵測，以降低資源利用率。</span><span class="sxs-lookup"><span data-stu-id="4e59f-286">Improved detection of co-authoring status to reduce resource utilization.</span></span>


- <span data-ttu-id="4e59f-287">透過暫時變更建立頁面版本歷程記錄的頻率，可改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="4e59f-287">Improved sync and service stability by temporarily altering how frequently page version histories are created.</span></span>


- <span data-ttu-id="4e59f-288">透過暫時將 OneNote 2016 中新嵌入附件的最大允許大小減少為 50MB，來改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="4e59f-288">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="4e59f-289">對於超過此限制的檔案，使用者可以選擇將檔案上傳到 OneDrive，並將連結插入 OneNote。</span><span class="sxs-lookup"><span data-stu-id="4e59f-289">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>


- <span data-ttu-id="4e59f-290">透過暫時停用 OneNote 2016 中的應用程式內視訊錄製，來改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="4e59f-290">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="4e59f-291">本機筆記本不受這個值的影響。</span><span class="sxs-lookup"><span data-stu-id="4e59f-291">Local notebooks are not impacted by this measure.</span></span>


- <span data-ttu-id="4e59f-292">透過暫時停用將頁面移動至資源回收桶，來改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="4e59f-292">Improved sync and service stability by temporarily disabling moving pages into the recycle bin.</span></span> <span data-ttu-id="4e59f-293">若使用者想要刪除頁面，則會改為顯示詢問是否要永久刪除頁面的對話方塊。</span><span class="sxs-lookup"><span data-stu-id="4e59f-293">Users who want to delete a page will instead be shown a dialog asking if they'd want to permanently delete the page.</span></span>


- <span data-ttu-id="4e59f-294">我們已修正 [拼寫檢查] 功能表未載入的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-294">We fixed an issue where the spelling menu was not loading.</span></span>


### <a name="outlook"></a><span data-ttu-id="4e59f-295">Outlook</span><span class="sxs-lookup"><span data-stu-id="4e59f-295">Outlook</span></span>

- <span data-ttu-id="4e59f-296">我們已修正選用連線體驗導致網頁增益集無法載入的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-296">We fixed an issue where optional connected experiences blocked web add-ins from loading.</span></span>  <span data-ttu-id="4e59f-297">請參閱此處的更多詳細資訊： https://developer.microsoft.com/en-us/office/blogs/outlook-add-ins-and-optional-connected-experiences/</span><span class="sxs-lookup"><span data-stu-id="4e59f-297">See more detail here:  https://developer.microsoft.com/en-us/office/blogs/outlook-add-ins-and-optional-connected-experiences/</span></span>


- <span data-ttu-id="4e59f-298">我們已修正一個問題，使用者現在可以停用 Outlook 的 IRM (資訊版權管理)，而不需要為其餘 Office 應用程式停用它。</span><span class="sxs-lookup"><span data-stu-id="4e59f-298">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>


- <span data-ttu-id="4e59f-299">我們已修正導致使用者無法將 [編輯器] 權限授與代理人的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-299">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="4e59f-300">我們已修正導致使用者在選取搜尋結果時遇到意外終止的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-300">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="4e59f-301">修正導致使用者嘗試從次要帳戶建立會議邀請的問題，讓帳戶新增至他們的個人檔案，而不會看到空白的表格: 是欄位而不是其電子郵件地址。</span><span class="sxs-lookup"><span data-stu-id="4e59f-301">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>


- <span data-ttu-id="4e59f-302">修正了新增共用信箱之後，導致使用者無法連線至公用資料夾的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-302">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>


- <span data-ttu-id="4e59f-303">解決了當代理人在某些情況下遭到拒絕而導致會議無法從經理的行事曆中移除的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-303">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>


- <span data-ttu-id="4e59f-304">解决了導致使用 Shared Calendar Improvements 的某些使用者無法查看剛新增的共用行事曆的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-304">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>


- <span data-ttu-id="4e59f-305">解決由於按一下角落中的 [X] 而導致使用者無法關閉共用行事曆的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-305">Addresses an issue that caused users to be unable to close shared calendars by clicking on the "X" in the corner.</span></span>


- <span data-ttu-id="4e59f-306">解決會導致 [開啟共用行事曆改良] 設定有時候無法套用至現有共用行事曆的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-306">Addresses an issue that caused the "Turn on shared calendar improvements" setting to sometimes fail to apply to existing shared calendars.</span></span>


- <span data-ttu-id="4e59f-307">我們已修正導致群組行事曆中的搜尋無法傳回任何結果的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-307">We fixed an issue that caused searches in Group calendars fail to return any results.</span></span>


- <span data-ttu-id="4e59f-308">修正了當與雲端附件互動時，導致使用者偶爾關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-308">Fixes an issue that caused users to experience occasional closures when interacting with Cloud attachments.</span></span>


- <span data-ttu-id="4e59f-309">解決會導致 CLP 使用者在回覆時的寄件者地址，從受保護的內容切換到未受保護的內容時會發生問題的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-309">Addressed an issue that caused users of CLP to experience an issue when switching the from address on a reply from a protected context to an unprotected one.</span></span>


- <span data-ttu-id="4e59f-310">解決使用者嘗試開啟雲端附件時，會導致使用者在 safelinks 頁面上看到錯誤，而非所嘗試開啟文件的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-310">Addresses an issue that caused users to see an error on the safelinks page instead of the document they were trying to open when opening a cloud attachment.</span></span>


- <span data-ttu-id="4e59f-311">解決了 Outlook 無法啟用 [資料遺失保護原則] 提示使用 M365 商務版進階方案並為此服務付款的的使用者之問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-311">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>


- <span data-ttu-id="4e59f-312">已解決有回應/轉寄標註的clp審查活動的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-312">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>


- <span data-ttu-id="4e59f-313">已解決導致資料夾窗格寬度意外變更的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-313">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>


- <span data-ttu-id="4e59f-314">我們修正了在傳送任務狀態報告時導致 [收件人：] 欄位為空的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-314">We fixed an issue that caused the To: field to be empty when sending a status report on a Task.</span></span>


- <span data-ttu-id="4e59f-315">我們已修正導致 MailItem.BeforeAttachmentAdd 事件中斷的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-315">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="4e59f-316">解決會導致使用者看到他們透過拖放附件，以複製到其檔案系統所建立附件的建立日期設為 4501 年 1 月 1 日的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-316">Addressed an issue that caused users to see the creation date of  attachments that they copied to their file system via drag and drop getting  set to January 1, 4501.</span></span>


- <span data-ttu-id="4e59f-317">解決了導致某些字元集的使用者在將 [智慧型連結] 新增至 SharePoint 檔案時，發現檔案名不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-317">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>


- <span data-ttu-id="4e59f-318">解決會導致使用者在 Outlook 中更新其規則時，看到 [此電腦上的規則與 Microsoft Exchange 上的規則不相符] 訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-318">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>


- <span data-ttu-id="4e59f-319">解決會導致 Outlook 無法擷取搜尋建議的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-319">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>


- <span data-ttu-id="4e59f-320">解決會導致共用行事曆改善功能的使用者看到行事曆失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-320">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>


- <span data-ttu-id="4e59f-321">解決會導致使用者在某些情況下遇到間歇性懸置和關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-321">Addressed an issue that caused users to experience intermittent hangs and closures in some scenarios.</span></span>


- <span data-ttu-id="4e59f-322">解決了當您從 POP 帳戶刪除4 或多個電子郵件時，已選取 [僅下載標題] 選項時，導致使用者遇到問題的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-322">Addressed an issue which caused users to experience an issue when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>


- <span data-ttu-id="4e59f-323">已解決導致代理人在開啟另一個信箱中的共用資料夾時出現錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-323">Addressed an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


- <span data-ttu-id="4e59f-324">已解決當主旨行空白時，會導致傳送的自動產生電子郵件含有空白內文的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-324">Addressed an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


- <span data-ttu-id="4e59f-325">解決會導致若「未」核取 [下載共用資料夾]，共用行事曆會議的 [回應選項] 中會遺失 [允許轉寄] 選項的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-325">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>


- <span data-ttu-id="4e59f-326">解決在編輯經理行事曆上的現有行事曆約會時，導致代理人收到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-326">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>


- <span data-ttu-id="4e59f-327">解決使用者在第三方 MAPI 應用程式中遇到問題的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-327">Addressed an issue that caused users to experience an issue in third party MAPI applications.</span></span>


- <span data-ttu-id="4e59f-328">已解決在 Windows 更新後，開啟儲存在本機的 msg 或 .oft 檔案會導致 Outlook 意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-328">Addressed an issue that caused Outlook to close unexpectedly when opening .msg or .oft files that were saved locally after a Windows update.</span></span>


- <span data-ttu-id="4e59f-329">已解決導致 Outlook 在某些 Windows 組建上意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-329">Addressed an issue that caused Outlook to close unexpectedly on some builds of Windows.</span></span>


- <span data-ttu-id="4e59f-330">解決會導致 Windows 10 伺服器版本的使用者看到警告「防毒軟體狀態: 無效」的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-330">Addressed an issue that caused users of Windows 10 server versions to see the warning "Antivirus status: Invalid.</span></span> <span data-ttu-id="4e59f-331">這個版本的 Windows 支援防毒偵測，但找不到任何防毒軟體。]，即使已正確安裝防毒軟體。</span><span class="sxs-lookup"><span data-stu-id="4e59f-331">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus correctly installed.</span></span>


- <span data-ttu-id="4e59f-332">我們修正了一些問題，導致某些使用者在從 Outlook 以外的應用程式傳送 Outlook 郵件時，遇到應用程式意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-332">We fixed an issue that was causing some users to experience the application to close unexpectedly when sending Outlook mail from applications other than Outlook.</span></span>


- <span data-ttu-id="4e59f-333">解決附件上傳的效能問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-333">Addresses a performance issue with attachment upload.</span></span>


- <span data-ttu-id="4e59f-334">解決會導致使用者看到 Outlook 持續提示他們執行收件匣修復工具的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-334">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>


- <span data-ttu-id="4e59f-335">解決使用滑鼠上的「X」按鈕時，導致使用者偶爾遇到問題的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-335">Addressed an issue that caused users to occasionally experience an issue when using the "X" button on their mouse.</span></span>


- <span data-ttu-id="4e59f-336">解決了當選取安全性對話方塊上的 [儲存] 選項時，導致使用者無法將 OneDrive 外部的 OneDrive 附件儲存至他們的本機電腦的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-336">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>


- <span data-ttu-id="4e59f-337">我們已修正在回覆或轉寄時，導致中文郵件標題出現亂碼的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-337">We fixed an issue that caused the headers of Chinese messages to get garbled when replying or forwarding.</span></span>


- <span data-ttu-id="4e59f-338">解決導致 [排程助理員] 頁面無法顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-338">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>


- <span data-ttu-id="4e59f-339">解決導致 [排程助理員] 頁面無法顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-339">Addressed an issue that caused some users to see the Scheduling Assistant page fail to display.</span></span>


- <span data-ttu-id="4e59f-340">我們修正了導致使用者在線上模式下在資料夾之間移動多個郵件項時效能下降的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-340">We fixed an issue that caused users to experience degraded performance when moving multiple mail items between folders in online mode.</span></span>


- <span data-ttu-id="4e59f-341">我們新增了一個 RegKey，可讓客戶停用 IDataObject 操作 (例如，拖曳拖放、剪貼簿) 中附件的 FileTime 包含。</span><span class="sxs-lookup"><span data-stu-id="4e59f-341">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span> <span data-ttu-id="4e59f-342">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject  0 = filetimes 被排除  1 = (預設) 事件時間包含在内</span><span class="sxs-lookup"><span data-stu-id="4e59f-342">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject  0 = filetimes are excluded  1 = (default) filetimes are included</span></span>


- <span data-ttu-id="4e59f-343">我們修正了當回復含有「Azure 資訊保護」保護標籤的郵件時，會導致內嵌影像消失的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-343">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


- <span data-ttu-id="4e59f-344">我們修正了導致在傳送受 Azure 保護的語音信箱時用戶名顯示為電話號碼，從而導致傳統型 Outlook 使用者無法開啟來自外部使用者的語音信箱。</span><span class="sxs-lookup"><span data-stu-id="4e59f-344">We fixed an issue that caused the user name to be displayed as a phone number when sending an Azure Protected Voicemail, causing Outlook Desktop users to be unable to open voicemails from external users.</span></span>


- <span data-ttu-id="4e59f-345">我們修正了一個問題，即設定 OME 設定時在郵件項目上新增無關的附件，這會迫使 Outlook 加密郵件，即使在服務端設定了DecryptAttachmentsFontryptOnly 選項。</span><span class="sxs-lookup"><span data-stu-id="4e59f-345">We fixed an issue where setting up OME Configuration was adding an extraneous attachments on the mail item which was forcing Outlook to Encrypt the message even though the DecryptAttachmentsForEncryptOnly option was setup on the service side.</span></span>


- <span data-ttu-id="4e59f-346">我們修正了導致在某些情况下，儘管原則停用了 [僅加密] 和 [不可轉寄] 選項，但仍繼續啟用的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-346">We fixed an issue that caused the Encrypt Only and Do Not Forward options to continue to be enabled in some scenarios despite being disabled by policy.</span></span>


- <span data-ttu-id="4e59f-347">我們已修正導致 SmartLinks 在儲存至草稿時丟失其格式的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-347">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


- <span data-ttu-id="4e59f-348">我們已修正讓使用者能在覆寫原則時自訂調整文字的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-348">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


- <span data-ttu-id="4e59f-349">我們已修正在儲存為 OFT 檔案時，會導致中文字元變更為問號的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-349">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


- <span data-ttu-id="4e59f-350">解決會導致使用者在擷取角色資訊時有時候遇到意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-350">Addressed an issue that caused users to occasionally experience unexpected closures when retrieving persona information.</span></span>


- <span data-ttu-id="4e59f-351">這可修正編輯收件者時，會導致使用者偶爾遇到應用程式關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-351">This fixes an issue that caused users to experience occasional application closures when editing recipients.</span></span>


- <span data-ttu-id="4e59f-352">修正導致使用者在使用壓縮模式時發生異常的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-352">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>


- <span data-ttu-id="4e59f-353">解決會導致 Outlook 使用者在精簡檢視中看到瀏覽問題的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-353">Addressed an issue that caused outlook users to see issues with navigation in compact views.</span></span>


- <span data-ttu-id="4e59f-354">解決的問題導致在搜尋控制項中無法顯示滑鼠右鍵功能表。</span><span class="sxs-lookup"><span data-stu-id="4e59f-354">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>


- <span data-ttu-id="4e59f-355">解決會導致使用者在回覆或撰寫新電子郵件時收到下列錯誤的問題：「這個網頁中的某些檔案不存在預期的位置，</span><span class="sxs-lookup"><span data-stu-id="4e59f-355">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="4e59f-356">請問您一定要下載嗎?</span><span class="sxs-lookup"><span data-stu-id="4e59f-356">Do you want to download them anyway?</span></span> <span data-ttu-id="4e59f-357">如果您確定網頁來自信任的來源，請按 [是]」</span><span class="sxs-lookup"><span data-stu-id="4e59f-357">If you’re sure the Web page is from a trusted source, click Yes"</span></span>


- <span data-ttu-id="4e59f-358">解決導致使用者在退出 Outlook 時遇到掛斷的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-358">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>


- <span data-ttu-id="4e59f-359">解決會導致在「建議功能」中尋找功能不會傳回結果，因而讓使用者無法選擇提交新功能想法的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-359">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>


- <span data-ttu-id="4e59f-360">解決事件通知警示中導致格式設定問題的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-360">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>


- <span data-ttu-id="4e59f-361">已解決在從系統管理人通知中提交意見反應時，使用者遇到突然關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-361">Addressed an issue that caused users to experience sudden closures when submitting feedback from an Admin Notification.</span></span>


- <span data-ttu-id="4e59f-362">我們已修正複製和貼上 SVG 影像的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-362">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="4e59f-363">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4e59f-363">PowerPoint</span></span>

- <span data-ttu-id="4e59f-364">此變更可解決「匯出為動畫 GIF」功能的問題，其中按一下 [匯出] 按鈕不會匯出。</span><span class="sxs-lookup"><span data-stu-id="4e59f-364">This change addresses an issue with Export to Animated GIF feature where clicking on Export button was not exporting.</span></span>


- <span data-ttu-id="4e59f-365">我們已修正 Forms 內容增益集在插入之後不會呈現，除非使用者按一下另一張投影片讓它顯示才會呈現的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-365">We have fixed an issue where Forms content add-in doesn't render after insertion until user click to another slide to make it show.</span></span>


- <span data-ttu-id="4e59f-366">安全性修正程式可解決在 [受保護的檢視] 中開啟 PowerPoint 檔案時會停用 IRM 保護的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-366">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


- <span data-ttu-id="4e59f-367">我們已修正 Slide.Shapes.AddMediaObject2 會對舊版影片格式 (MPG-1、Mpeg-2) 發生意外關閉的 VBA 問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-367">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 would unexpectedly close with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="4e59f-368">我們已修正當使用者將來源路徑變更為本機 OneDrive 資料夾時，連結的 Excel 圖表不正確變更為 Excel 工作表的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-368">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


- <span data-ttu-id="4e59f-369">已修正使用者在同一檔案中同時有新版和舊版批註，因此觸發批註升級的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-369">Fixed an issue when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>


- <span data-ttu-id="4e59f-370">我們修正了可能會導致應用程式意外關閉的建議窗格之問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-370">We have fixed an issue with suggestion pane that may cause the application to close unexpectedly.</span></span>


- <span data-ttu-id="4e59f-371">我們修復了 [動作設定] 對話方塊中導致 PowerPoint 應用程式意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-371">We have fixed an issue in Action Settings dialog which was causing the PowerPoint app to close unexpectedly.</span></span>


- <span data-ttu-id="4e59f-372">我們已修正 PowerPoint 應用程式可能導致其意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-372">We have fixed an issue with PowerPoint app that may cause it to close unexpectedly.</span></span>


- <span data-ttu-id="4e59f-373">我們修正了導致「歡迎回來」的問題！</span><span class="sxs-lookup"><span data-stu-id="4e59f-373">We fixed an issue due to which the feature ‘Welcome back!</span></span> <span data-ttu-id="4e59f-374">「從先前離開的地方開始」在 PowerPoint 裏不起作用。</span><span class="sxs-lookup"><span data-stu-id="4e59f-374">Pick up where you left off in the office' was not working in the PowerPoint .</span></span>


- <span data-ttu-id="4e59f-375">已修正無法正確開啟部分損壞的 PowerPoint 檔案 (即使在文件修復之後) 的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-375">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


- <span data-ttu-id="4e59f-376">已修正無法正確開啟部分損壞的 PowerPoint 檔案 (即使在文件修復之後) 的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-376">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


- <span data-ttu-id="4e59f-377">我們已修正受保護的檢視中的投影片無法正常運作的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-377">We fixed an issue where Slideshow in protected view was not working.</span></span>


### <a name="project"></a><span data-ttu-id="4e59f-378">Project</span><span class="sxs-lookup"><span data-stu-id="4e59f-378">Project</span></span>

- <span data-ttu-id="4e59f-379">已修正 [指派資源] 對話方塊中選取的工作與工作面板檢視中所選工作不同的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-379">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>


- <span data-ttu-id="4e59f-380">已修正如果資源中定義了多個成本費率表，其餘成本並不一定都能正確地計算的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-380">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>


- <span data-ttu-id="4e59f-381">已修正「連結至 SharePoint 工作清單的專案的完成日期沒有更新」的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-381">Fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>


- <span data-ttu-id="4e59f-382">已修正如果您使用的是連線至 Project Web App 的 Project，且小數分隔符號是逗號，當您嘗試將延遲新增至相依性時，TaskDependencies Add 方法會失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-382">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>


- <span data-ttu-id="4e59f-383">修正在將任務標示為完成之後，不正確地將任務完成百分比變更為低於 100% 的值的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-383">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>


- <span data-ttu-id="4e59f-384">修正不先執行 OpenUndoTransaction 方法就不能觸發 OnUndoOrRedo 事件的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-384">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>


- <span data-ttu-id="4e59f-385">修正無法正確計算摘要工作日期的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-385">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>


- <span data-ttu-id="4e59f-386">修正透過 [已停用] 按鈕停用/啟動工作時，ProjectBeforeTaskChange 事件無法偵測的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-386">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>


- <span data-ttu-id="4e59f-387">已修正在表單檢視中編輯前置/後續任務資料時，會觸發額外的 ProjectBeforeTaskChange 事件的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-387">Fixed an issue when Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>


- <span data-ttu-id="4e59f-388">修正儲存使用舊版 Project 建立的專案時，Project 可能意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-388">Fixed an issue where Project may close unexpectedly when saving projects created with older versions of Project.</span></span>


- <span data-ttu-id="4e59f-389">修正了當開啟保護實際工作的設定時，使用者無法輸入分時期基準工時的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-389">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>


- <span data-ttu-id="4e59f-390">修正無法將 PDF/XPS 從 Project 儲存至 SharePoint 文件庫的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-390">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>


- <span data-ttu-id="4e59f-391">修正當您貼上的工作具有多個依存性時，無法正確複製所有依存性的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-391">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>


- <span data-ttu-id="4e59f-392">修正 URL 以 .com 結尾時，無法從 Project Web App 在 Project 傳統型用戶端開啟專案的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-392">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>


- <span data-ttu-id="4e59f-393">已修正當專案摘要工作-或是專案[開始/工作]欄位有變更時，ProjectBeforeTaskChange 事件不會觸發的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-393">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>


- <span data-ttu-id="4e59f-394">已修正當標示為100% 完成之工作錯誤地變更為完成度低於100% 的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-394">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>


- <span data-ttu-id="4e59f-395">我們已修正在開啟以特定方式指定資源分佈的檔案時，Project 可能會意外終止的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-395">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>


### <a name="skype"></a><span data-ttu-id="4e59f-396">Skype</span><span class="sxs-lookup"><span data-stu-id="4e59f-396">Skype</span></span>

- <span data-ttu-id="4e59f-397">將跳舞表情符號膚色變更為中性色彩.</span><span class="sxs-lookup"><span data-stu-id="4e59f-397">Changed dancing emoticon skin tone to neutral color.</span></span>


- <span data-ttu-id="4e59f-398">當使用者收到將他們移至 Teams Only 的原則時，他們仍然可以使用商務版 Skype Outlook 增益集來排程會議。</span><span class="sxs-lookup"><span data-stu-id="4e59f-398">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span> <span data-ttu-id="4e59f-399">在此更新之後，當客戶端讀取指示用戶為 Teams Only 的策略並進入僅限會議加入模式後，您將不再能用商務版 Skype 安排會議。</span><span class="sxs-lookup"><span data-stu-id="4e59f-399">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span> <span data-ttu-id="4e59f-400">此外，如果商務版 Skype Outlook 增益集發現商務版 Skype 用戶端處於 [僅限會議加入] 模式，就無法自行啟動。</span><span class="sxs-lookup"><span data-stu-id="4e59f-400">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>


- <span data-ttu-id="4e59f-401">修正了使用者的 TLS-DSK 憑證不會在預期時間續訂，而只在有效期剩餘不到 12 小時才續訂的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-401">Fixes an issue where a user's TLS-DSK certificate would not renew at the expected time, instead only renewing when less than 12 hours remain on its validity.</span></span>


- <span data-ttu-id="4e59f-402">修正了當 Office 尚未獲得授權時，商務用 Skype UI 在登入後顯示為空白的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-402">Fixes an issue where the Skype for Business UI shows as blank after signing in when Office is not yet licensed.</span></span>


### <a name="visio"></a><span data-ttu-id="4e59f-403">Visio</span><span class="sxs-lookup"><span data-stu-id="4e59f-403">Visio</span></span>

- <span data-ttu-id="4e59f-404">我們已修正導致即時預覽在文字對齊時發生意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-404">We fixed an issue that caused the Live preview to close unexpectedly on text alignment.</span></span>


- <span data-ttu-id="4e59f-405">已修正使用者將可在自訂 Visio 樣板和內建範本中使用適用於 Office 365 的 Visio 連接器建立直線的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-405">We fixed an issue where users will be able to create straight lines using connectors in Visio for Office 365 for both custom Visio stencils and in-built templates.</span></span>


### <a name="word"></a><span data-ttu-id="4e59f-406">Word</span><span class="sxs-lookup"><span data-stu-id="4e59f-406">Word</span></span>

- <span data-ttu-id="4e59f-407">解決 URL 包含查詢元件時，從自訂文件傳遞 (aspx) 開啟 Word 文件的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-407">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>


- <span data-ttu-id="4e59f-408">此更改解決了一個問題，即在上一個協同合作的作業後，Microsoft Office 應用程式可能卡在未通知的儲存失敗狀態的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-408">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>


- <span data-ttu-id="4e59f-409">解決會導致使用者在回覆或撰寫新電子郵件時遇到問題的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-409">Addresses an issue that caused users to experience an issue when replying to or composing new email.</span></span>


- <span data-ttu-id="4e59f-410">解決使用滑鼠上的「X」按鈕時，導致使用者偶爾遇到問題的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-410">Addressed an issue that caused users to occasionally experience an issue when using the "X" button on their mouse.</span></span>


- <span data-ttu-id="4e59f-411">解決會導致使用者在開啟某些非常大型電子郵件時會遇到問題的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-411">Fixes an issue that caused users to experience an issue when opening certain very large emails.</span></span>


- <span data-ttu-id="4e59f-412">我們已修正貼上編號標題顯示額外縮排的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-412">We fixed an issue where pasted numbered headings showed an additional indent.</span></span>


- <span data-ttu-id="4e59f-413">我們已修正複製和貼上 SVG 影像的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-413">We fixed an issue for copy and paste SVG image.</span></span>


- <span data-ttu-id="4e59f-414">我們修正了當調整圖案大小時，使用者可能會遺失內容的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-414">We fixed an issue where the user might lose content when resize a shape.</span></span>


- <span data-ttu-id="4e59f-415">我們已修正使用者開啟文件時可能會遇到問題的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-415">We fixed an issue which user might experience issues when opening a document.</span></span>


- <span data-ttu-id="4e59f-416">我們已修正將文件儲存成 HTML 格式時，長連結無法換行的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-416">We fixed an issue where long links were not being wrapped when saving document to HTML format.</span></span>


- <span data-ttu-id="4e59f-417">我們已修正基本樣式未更新為「內文樣式」的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-417">We fixed an issue which the base styles are not updated with Normal style.</span></span>


- <span data-ttu-id="4e59f-418">修正了帶有註解副檔名的 bug，其中註解回覆的副檔名與父註解的副檔名相同。</span><span class="sxs-lookup"><span data-stu-id="4e59f-418">FIxes a bug with comment extensions where the comment reply would have the same extension as the parent comment.</span></span>


- <span data-ttu-id="4e59f-419">我們已修正問題：如果您回復的父級註解在副檔名清單中有未知的副檔名，那麼回復將得到相同的副檔名。</span><span class="sxs-lookup"><span data-stu-id="4e59f-419">We fixed an issue where if you reply to a parent comment that has unknown extensions in an extension list, the reply will get those same extensions.</span></span>


- <span data-ttu-id="4e59f-420">解决了可能導致應用程式在啟動時意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-420">Resolved an issue that may have caused the application to close unexpectedly when booting.</span></span>


- <span data-ttu-id="4e59f-421">我們已修正 Outlook 有關將郵件設定為 [不可轉寄] 的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-421">We fixed an issue with Outlook with message set to Do not forward.</span></span>


- <span data-ttu-id="4e59f-422">我們修正了 [樣式庫] 對話方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-422">We fixed an issue with Style Gallery dialog.</span></span>


- <span data-ttu-id="4e59f-423">我們已修正巨集 AutoOpen 在 AutoExec 之前執行的問題</span><span class="sxs-lookup"><span data-stu-id="4e59f-423">We fixed an issue where macro AutoOpen runs before AutoExec</span></span>


### <a name="office-suite"></a><span data-ttu-id="4e59f-424">Office 套件</span><span class="sxs-lookup"><span data-stu-id="4e59f-424">Office Suite</span></span>

- <span data-ttu-id="4e59f-425">修正了舊版非網頁服務的 [共用] 窗格問題：在開啟 [共用] 窗格時關閉文件，可能會導致應用程式意外關閉。</span><span class="sxs-lookup"><span data-stu-id="4e59f-425">Fixed an issue for the old, non-web service based Share pane, where upon closing the document while the Share pane is open could cause the application to close unexpectedly.</span></span>


- <span data-ttu-id="4e59f-426">修正了關閉 Office 檔案時可能導致應用程式意外關閉的計時問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-426">Fixed a timing issue that could cause the application to close unexpectedly when closing office files.</span></span>


- <span data-ttu-id="4e59f-427">解決已停用 ADAL 時，使用者無法匯入 SPO 清單的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-427">Addresses an issue that prevented users from importing SPO Lists when ADAL was disabled.</span></span>


- <span data-ttu-id="4e59f-428">當使用者從 Office 噴墨印表機上列印任何文件/檔案且列印機墨水不足時，即使噴墨印表機沒有碳粉，也會顯示「碳粉不足」或「無碳粉」消息。</span><span class="sxs-lookup"><span data-stu-id="4e59f-428">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="4e59f-429">將訊息變更為顯示「碳粉/墨水不足」和「沒有碳粉/墨水」。</span><span class="sxs-lookup"><span data-stu-id="4e59f-429">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


- <span data-ttu-id="4e59f-430">我們透過設定Bing附加預設安裝驗證設定為true默認，並將MSI返回成功視為安裝成功，而解決了 ValidateInstall 失敗率問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-430">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>


- <span data-ttu-id="4e59f-431">我們會將新的 AppV51 向後移，以修正先前 AppV51 中的回歸。</span><span class="sxs-lookup"><span data-stu-id="4e59f-431">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>


- <span data-ttu-id="4e59f-432">已修正當嘗試硬連結符號連結時，導致更新失敗的 [點擊運作] 問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-432">Fixed a Click-to-Run issue which was resulting in update failure when trying to hard link symbolic links.</span></span>


- <span data-ttu-id="4e59f-433">已解決針對使用 System Center Configuration Manager 或其他管理工具來使用 Microsoft 365 Endpoint 資料外洩防護進行 Office Update 的商業客戶的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-433">Addressed an issue for commercial customers who leverage System Center Configuration Manager or other management tool for the Office Update using Microsoft 365 Endpoint data loss prevention.</span></span>


- <span data-ttu-id="4e59f-434">修正即使完整產品的轉換已完成，也會導致執行階段訊息顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-434">Fixed an issue that caused a runtime message to show even though the transition to the full product is complete.</span></span> <span data-ttu-id="4e59f-435">此問題的修正程式是確保服務正確計算新增的產品。</span><span class="sxs-lookup"><span data-stu-id="4e59f-435">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="4e59f-436">我們已篩選出新增的產品 (確保它們同時存在於新的設定中)，並將它們新增到現有產品發行識別碼的結尾。</span><span class="sxs-lookup"><span data-stu-id="4e59f-436">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>


- <span data-ttu-id="4e59f-437">我們已修正使用者在特定情況下 (特別是進入或退出簡報者檢視畫面或使用多個監視器) 看到 UI 元素或內容未顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-437">We fixed an issue where users were seeing the UI elements or content not being displayed under certain conditions, in particular with coming in and out of Presenter View or using multiple monitors.</span></span>


- <span data-ttu-id="4e59f-438">此變更解决了與開啟包含舊圖表之檔案相關的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-438">This change addresses an issue related to opening files containing legacy diagrams.</span></span>


- <span data-ttu-id="4e59f-439">此變更解决了 SVG 回復 Proxy 導致存取衝突的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-439">This change addresses an issue with SVG fallback proxy resulting in access violations.</span></span>


- <span data-ttu-id="4e59f-440">修正使用 GIF/動畫 model3D 閒置時的高 CPU 使用量</span><span class="sxs-lookup"><span data-stu-id="4e59f-440">Fixes high CPU usage on idle with GIF/animated model3D</span></span>


- <span data-ttu-id="4e59f-441">此變更會解決載入和播放動畫內容 (例如 Gif 或3D 模型) 時可能會發生的懸置。</span><span class="sxs-lookup"><span data-stu-id="4e59f-441">This change addresses potential hangs when loading and playing animated content such as GIFs or 3D models.</span></span>


- <span data-ttu-id="4e59f-442">此變更可解決啟動 Office 應用程式時由於無法載入 d2d1.dll 而產生的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-442">This change addresses a issue when launching Office apps due to failing to load d2d1.dll.</span></span>


- <span data-ttu-id="4e59f-443">當您啟用增益集，而登錄金鑰 HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth 被設為零時，辦公主機視窗會意外關閉。</span><span class="sxs-lookup"><span data-stu-id="4e59f-443">The office host was  close unexpectedly in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="4e59f-444">此變更將修正此問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-444">This change would fix this issue.</span></span>


- <span data-ttu-id="4e59f-445">修正 Office 增益集的傳訊 API 無法正常運作的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-445">Fix an issue that the Messaging API for Office Add-ins is not working.</span></span>

- <span data-ttu-id="4e59f-446">此更新修正了 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。</span><span class="sxs-lookup"><span data-stu-id="4e59f-446">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


- <span data-ttu-id="4e59f-447">此更新解決了 Microsoft Office 中的一個問題：可能無法在執行時期正確找到 Visual Basic for Applications 專案，這些專案的參照預期透搜尋 PATH 環境變數指定的位置來找到，進而導致VBA 執行時期錯誤。</span><span class="sxs-lookup"><span data-stu-id="4e59f-447">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="4e59f-448">此修正可解決同時防止限制存取和保護設有密碼之檔案的錯誤。</span><span class="sxs-lookup"><span data-stu-id="4e59f-448">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>

- <span data-ttu-id="4e59f-449">解決會導致從應用程式拖曳部分內容時遇到意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-449">Resolved an issue that may have caused an unexpected closure when dragging some content from the app.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-january-12"></a><span data-ttu-id="4e59f-451">版本 2002：1 月 12 日</span><span class="sxs-lookup"><span data-stu-id="4e59f-451">Version 2002: January 12</span></span>
<span data-ttu-id="4e59f-452">*版本 2002 (組建 12527.21504)*</span><span class="sxs-lookup"><span data-stu-id="4e59f-452">*Version 2002 (Build 12527.21504)*</span></span>

<span data-ttu-id="4e59f-453">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4e59f-453">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="4e59f-455">解決的問題</span><span class="sxs-lookup"><span data-stu-id="4e59f-455">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="4e59f-456">Excel</span><span class="sxs-lookup"><span data-stu-id="4e59f-456">Excel</span></span>

- <span data-ttu-id="4e59f-457">修正了將即時資料與多執行緒重新計算功能結合使用時，可能會導致應用程式意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-457">Fixed an issue when using real time data in conjunction with multithreaded recalc functionality could cause the application to close unexpectedly.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="4e59f-458">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4e59f-458">PowerPoint</span></span>

- <span data-ttu-id="4e59f-459">已修正無法正確開啟部分損壞的 PowerPoint 檔案 (即使在文件修復之後) 的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-459">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="word"></a><span data-ttu-id="4e59f-460">Word</span><span class="sxs-lookup"><span data-stu-id="4e59f-460">Word</span></span>

- <span data-ttu-id="4e59f-461">修正含有批註副檔名的 bug，其中批註回復的副檔名與父批註相同。</span><span class="sxs-lookup"><span data-stu-id="4e59f-461">Fixes a bug with comment extensions where the comment reply would have the same extension as the parent comment.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-january-12"></a><span data-ttu-id="4e59f-463">版本 1908：1 月 12 日</span><span class="sxs-lookup"><span data-stu-id="4e59f-463">Version 1908: January 12</span></span>
<span data-ttu-id="4e59f-464">*版本 1908 (組建 11929.20994)*</span><span class="sxs-lookup"><span data-stu-id="4e59f-464">*Version 1908 (Build 11929.20994)*</span></span>

<span data-ttu-id="4e59f-465">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4e59f-465">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="4e59f-467">解決的問題</span><span class="sxs-lookup"><span data-stu-id="4e59f-467">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="4e59f-468">Office 套件</span><span class="sxs-lookup"><span data-stu-id="4e59f-468">Office Suite</span></span>

- <span data-ttu-id="4e59f-469">此變更解决了與開啟包含舊圖表之檔案相關的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-469">This change addresses an issue related to opening files containing legacy diagrams.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-december-08"></a><span data-ttu-id="4e59f-471">版本 2002：12 月 8 日</span><span class="sxs-lookup"><span data-stu-id="4e59f-471">Version 2002: December 08</span></span>
<span data-ttu-id="4e59f-472">*版本 2002 (組建 12527.21416)*</span><span class="sxs-lookup"><span data-stu-id="4e59f-472">*Version 2002 (Build 12527.21416)*</span></span>

<span data-ttu-id="4e59f-473">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4e59f-473">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="4e59f-475">解決的問題</span><span class="sxs-lookup"><span data-stu-id="4e59f-475">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="4e59f-476">Excel</span><span class="sxs-lookup"><span data-stu-id="4e59f-476">Excel</span></span>

- <span data-ttu-id="4e59f-477">內容從 Excel 複製並使用 [内嵌] 選項貼上到 PowerPoint 中時，改進了 PowerPoint 中的文字字元間距調整。</span><span class="sxs-lookup"><span data-stu-id="4e59f-477">Improved text kerning in PowerPoint when content is copied from Excel and pasted into PowerPoint with the Embed option.</span></span>


- <span data-ttu-id="4e59f-478">我們已修復此問題：在重新計算期間，Excel 會停止運作。</span><span class="sxs-lookup"><span data-stu-id="4e59f-478">We fixed an issue where Excel would stop working during recalc.</span></span>


- <span data-ttu-id="4e59f-479">我們已修正使用者無法直接從 SharePoint 開啟 atomsvc (UTF8+BOM) 檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-479">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="4e59f-480">修正了在 PowerPivot 中封鎖從 [資料表預覽] 和 [査詢編輯器] 切換的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-480">Fixed an issue that would prevent switching from Table Preview and the Query Editor in PowerPivot.</span></span>


- <span data-ttu-id="4e59f-481">改進了使用許多最近發佈函數的檔案的效能。</span><span class="sxs-lookup"><span data-stu-id="4e59f-481">Improved performance for files that are using many of the more recently released functions.</span></span>


### <a name="outlook"></a><span data-ttu-id="4e59f-482">Outlook</span><span class="sxs-lookup"><span data-stu-id="4e59f-482">Outlook</span></span>

- <span data-ttu-id="4e59f-483">我們修正了以下問題：設定 OME 設定時在郵件項目上新增無關的附件，這迫使 Outlook 對郵件進行加密，即使在服務端設定了 DecryptAttachmentsFontryptOnly選項。</span><span class="sxs-lookup"><span data-stu-id="4e59f-483">We fixed an issue where setting up OME Configuration was adding an extraneous attachments on the mail item which was forcing Outlook to Encrypt the message even though DecryptAttachmentsForEncryptOnly option is setup on the service side.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="4e59f-484">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4e59f-484">PowerPoint</span></span>

- <span data-ttu-id="4e59f-485">我們已修正當使用者將來源路徑變更為本機 OneDrive 資料夾時，連結的 Excel 圖表不正確變更為 Excel 工作表的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-485">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


### <a name="project"></a><span data-ttu-id="4e59f-486">Project</span><span class="sxs-lookup"><span data-stu-id="4e59f-486">Project</span></span>

- <span data-ttu-id="4e59f-487">我們已修正 URL 以 .com 結尾時，無法從 Project Web App 在 Project 傳統型用戶端開啟專案的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-487">We fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App is the URL ended in .com.</span></span>



[//]: # (請勿移除 BUGDETAILS 內容尾)

## <a name="version-1908-december-08"></a><span data-ttu-id="4e59f-489">版本 1908：12 月 8 日</span><span class="sxs-lookup"><span data-stu-id="4e59f-489">Version 1908: December 08</span></span>
<span data-ttu-id="4e59f-490">*版本 1908 (組建 11929.20984)*</span><span class="sxs-lookup"><span data-stu-id="4e59f-490">*Version 1908 (Build 11929.20984)*</span></span>

<span data-ttu-id="4e59f-491">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4e59f-491">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2002-november-10"></a><span data-ttu-id="4e59f-492">版本 2002：11 月 10 日</span><span class="sxs-lookup"><span data-stu-id="4e59f-492">Version 2002: November 10</span></span>
<span data-ttu-id="4e59f-493">*版本 2002 (組建 12527.21330)*</span><span class="sxs-lookup"><span data-stu-id="4e59f-493">*Version 2002 (Build 12527.21330)*</span></span>

<span data-ttu-id="4e59f-494">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4e59f-494">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="4e59f-496">解決的問題</span><span class="sxs-lookup"><span data-stu-id="4e59f-496">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="4e59f-497">Excel</span><span class="sxs-lookup"><span data-stu-id="4e59f-497">Excel</span></span>

- <span data-ttu-id="4e59f-498">修正當 Office 語言設定為西班牙文時，其中資料驗證清單可能無法顯示清單中所有項目的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-498">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="4e59f-499">我們已修正在重新整理 OLAP 樞紐分析表時，可能會導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-499">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="4e59f-500">已修正載入活頁簿之後特定函數可能會發生錯誤結果的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-500">Fixed a bug where certain functions would have an incorrect result after loading a workbook.</span></span>


- <span data-ttu-id="4e59f-501">我們已修正應用程式意外終止 (與 XLAM 增益集參照和命名範圍相關的問題) 的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-501">We fixed an issue where the application would terminate unexpectedly which was related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="4e59f-502">已修正在執行進階篩選巨集時，不正確報告錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-502">Fixed an issue where running the advanced filter macro would incorrectly report errors.</span></span>


### <a name="outlook"></a><span data-ttu-id="4e59f-503">Outlook</span><span class="sxs-lookup"><span data-stu-id="4e59f-503">Outlook</span></span>

- <span data-ttu-id="4e59f-504">我們已修正當已停用選用的連線體驗時，導致內部增益集意外停用的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-504">We fixed an issue that caused internal add-ins to be unexpectedly disabled when optional connected experiences were disabled.</span></span>


- <span data-ttu-id="4e59f-505">我們已修正導致使用者無法以「全域通訊清單」中隱藏的「通訊群組」的名義或以代表其傳送的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-505">We fixed an issue that caused users to be unable to send as or on behalf of a Distribution List that was hidden from the Global Address List.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-november-10"></a><span data-ttu-id="4e59f-507">版本 1908：11 月 10 日</span><span class="sxs-lookup"><span data-stu-id="4e59f-507">Version 1908: November 10</span></span>
<span data-ttu-id="4e59f-508">*版本 1908 (組建 11929.20974)*</span><span class="sxs-lookup"><span data-stu-id="4e59f-508">*Version 1908 (Build 11929.20974)*</span></span>

<span data-ttu-id="4e59f-509">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4e59f-509">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2002-october-13"></a><span data-ttu-id="4e59f-510">版本 2002：10 月 13 日</span><span class="sxs-lookup"><span data-stu-id="4e59f-510">Version 2002: October 13</span></span>
<span data-ttu-id="4e59f-511">*版本 2002 (組建 12527.21236)*</span><span class="sxs-lookup"><span data-stu-id="4e59f-511">*Version 2002 (Build 12527.21236)*</span></span>

<span data-ttu-id="4e59f-512">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4e59f-512">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="4e59f-514">解決的問題</span><span class="sxs-lookup"><span data-stu-id="4e59f-514">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="4e59f-515">存取</span><span class="sxs-lookup"><span data-stu-id="4e59f-515">Access</span></span>

- <span data-ttu-id="4e59f-516">只要您滿足 Access 資料庫指導方針和需求，則應該不會再於您的 64 位元版本 Access 中收到「查詢太複雜」或系統資源滿載錯誤。</span><span class="sxs-lookup"><span data-stu-id="4e59f-516">You should no longer receive a "Query is too complex" or a system resource exceeded error on your 64-bit version of Access, as long as you are meeting Access database guidelines and requirements.</span></span>


- <span data-ttu-id="4e59f-517">一旦您決定在我們的查詢設計工具之後使用篩選功能，您的資料庫應該就不會再當機。</span><span class="sxs-lookup"><span data-stu-id="4e59f-517">Once you decide to use our filter feature after our query designer, your database should no longer crash.</span></span> <span data-ttu-id="4e59f-518">請相應地檢查。</span><span class="sxs-lookup"><span data-stu-id="4e59f-518">Please check accordingly.</span></span>


### <a name="excel"></a><span data-ttu-id="4e59f-519">Excel</span><span class="sxs-lookup"><span data-stu-id="4e59f-519">Excel</span></span>

- <span data-ttu-id="4e59f-520">我們修正了使用者無法修改樞紐分析表篩選的問題，因為它已設定為Analysis Services數據庫中不再存在的值。</span><span class="sxs-lookup"><span data-stu-id="4e59f-520">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="4e59f-521">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4e59f-521">PowerPoint</span></span>

- <span data-ttu-id="4e59f-522">從範本建立的新簡報會繼承設定，使得您無法順利進行共同撰寫。</span><span class="sxs-lookup"><span data-stu-id="4e59f-522">New presentations created from a template could inherit a setting that prevented  a good co-authoring experience.</span></span> <span data-ttu-id="4e59f-523">此修正程式可確保在此情況下會清除該設定。</span><span class="sxs-lookup"><span data-stu-id="4e59f-523">This fix ensures that the setting is cleared in this case.</span></span>


### <a name="word"></a><span data-ttu-id="4e59f-524">Word</span><span class="sxs-lookup"><span data-stu-id="4e59f-524">Word</span></span>

- <span data-ttu-id="4e59f-525">我們已修正在開啟含有分頁符號和欄的文件時，使用者可能會遇到錯誤訊息：「您已超過 Microsoft Word 所支援的頁數上限或此文件已損毀」</span><span class="sxs-lookup"><span data-stu-id="4e59f-525">We fixed an issue which when opening documents with page breaks and columns, user might encountered an error message, " You have exceeded the maximum number of pages allowed by Microsoft Word supported, or the document may be damaged"</span></span>


### <a name="office-suite"></a><span data-ttu-id="4e59f-526">Office 套件</span><span class="sxs-lookup"><span data-stu-id="4e59f-526">Office Suite</span></span>

- <span data-ttu-id="4e59f-527">當使用者從 Office 噴墨印表機上列印任何文件/檔案且列印機墨水不足時，即使噴墨印表機沒有碳粉，也會顯示「碳粉不足」或「無碳粉」消息。</span><span class="sxs-lookup"><span data-stu-id="4e59f-527">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="4e59f-528">將訊息變更為顯示「碳粉/墨水不足」和「沒有碳粉/墨水」。</span><span class="sxs-lookup"><span data-stu-id="4e59f-528">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-october-13"></a><span data-ttu-id="4e59f-530">版本 1908：10 月 13 日</span><span class="sxs-lookup"><span data-stu-id="4e59f-530">Version 1908: October 13</span></span>
<span data-ttu-id="4e59f-531">*版本 1908 (組建 11929.20966)*</span><span class="sxs-lookup"><span data-stu-id="4e59f-531">*Version 1908 (Build 11929.20966)*</span></span>

<span data-ttu-id="4e59f-532">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4e59f-532">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="4e59f-534">解決的問題</span><span class="sxs-lookup"><span data-stu-id="4e59f-534">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="4e59f-535">Office 套件</span><span class="sxs-lookup"><span data-stu-id="4e59f-535">Office Suite</span></span>

- <span data-ttu-id="4e59f-536">當使用者從 Office 噴墨印表機上列印任何文件/檔案且列印機墨水不足時，即使噴墨印表機沒有碳粉，也會顯示「碳粉不足」或「無碳粉」消息。</span><span class="sxs-lookup"><span data-stu-id="4e59f-536">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="4e59f-537">將訊息變更為顯示「碳粉/墨水不足」和「沒有碳粉/墨水」。</span><span class="sxs-lookup"><span data-stu-id="4e59f-537">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-september-08"></a><span data-ttu-id="4e59f-539">版本 2002：9 月 8 日</span><span class="sxs-lookup"><span data-stu-id="4e59f-539">Version 2002: September 08</span></span>
<span data-ttu-id="4e59f-540">*版本 2002 (組建 12527.21104)*</span><span class="sxs-lookup"><span data-stu-id="4e59f-540">*Version 2002 (Build 12527.21104)*</span></span>

<span data-ttu-id="4e59f-541">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4e59f-541">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="4e59f-543">解決的問題</span><span class="sxs-lookup"><span data-stu-id="4e59f-543">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="4e59f-544">Excel</span><span class="sxs-lookup"><span data-stu-id="4e59f-544">Excel</span></span>

- <span data-ttu-id="4e59f-545">這解决了舊版 Office 中 SQL 資料提供者建立的連結設定內部表格内容與 Office 365 不同的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-545">This addresses an issue where connections created by the SQL data provider in older versions of Office would set internal table properties differently from Office 365.</span></span> <span data-ttu-id="4e59f-546">這導致在舊版 Office 中使用 Office 365 開啟文件時，這些檔案的 [表格預覽/查詢編輯器] 下拉清單被停用。</span><span class="sxs-lookup"><span data-stu-id="4e59f-546">This caused the Table Preview / Query Editor dropdown to be disabled for files with connections created in older versions of Office when they were opened using Office 365.</span></span>


- <span data-ttu-id="4e59f-547">已解決筆跡會導致 Excel 無法回應的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-547">Resolved an issue where inking could cause Excel to become unresponsive.</span></span>


### <a name="outlook"></a><span data-ttu-id="4e59f-548">Outlook</span><span class="sxs-lookup"><span data-stu-id="4e59f-548">Outlook</span></span>

- <span data-ttu-id="4e59f-549">已修正新增共用信箱之後，導致使用者無法連線至公用資料夾的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-549">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>


### <a name="office-suite"></a><span data-ttu-id="4e59f-550">Office 套件</span><span class="sxs-lookup"><span data-stu-id="4e59f-550">Office Suite</span></span>

- <span data-ttu-id="4e59f-551">此變更解決 [壓縮圖片] 對話方塊無法保留特定使用者設定的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-551">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-september-08"></a><span data-ttu-id="4e59f-553">版本 1908：9 月 8 日</span><span class="sxs-lookup"><span data-stu-id="4e59f-553">Version 1908: September 08</span></span>
<span data-ttu-id="4e59f-554">*版本 1908 (組建 11929.20946)*</span><span class="sxs-lookup"><span data-stu-id="4e59f-554">*Version 1908 (Build 11929.20946)*</span></span>

<span data-ttu-id="4e59f-555">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4e59f-555">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2002-august-11"></a><span data-ttu-id="4e59f-556">版本 2002: 8月11日</span><span class="sxs-lookup"><span data-stu-id="4e59f-556">Version 2002: August 11</span></span>
<span data-ttu-id="4e59f-557">*版本2002（组建12527.20988）*</span><span class="sxs-lookup"><span data-stu-id="4e59f-557">*Version 2002 (Build 12527.20988)*</span></span>

<span data-ttu-id="4e59f-558">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4e59f-558">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="4e59f-560">解決的問題</span><span class="sxs-lookup"><span data-stu-id="4e59f-560">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="4e59f-561">Excel</span><span class="sxs-lookup"><span data-stu-id="4e59f-561">Excel</span></span>

- <span data-ttu-id="4e59f-562">修正了無法將以 [唯讀建議] 方式開啟的檔案切換至編輯功能的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-562">Fixed an issue which prevented the ability to switch to editing for files that opened as "read-only recommended".</span></span>

### <a name="onenote"></a><span data-ttu-id="4e59f-563">OneNote</span><span class="sxs-lookup"><span data-stu-id="4e59f-563">OneNote</span></span>

- <span data-ttu-id="4e59f-564">移除了多餘的身分識別通話，以降低資源使用率</span><span class="sxs-lookup"><span data-stu-id="4e59f-564">Removed redundant identity calls to reduce resource utilization</span></span>

- <span data-ttu-id="4e59f-565">改善了共同撰寫狀態的偵測，以降低資源利用率。</span><span class="sxs-lookup"><span data-stu-id="4e59f-565">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="4e59f-566">改善了偵測錯誤的功能和同步處理經驗的品質。</span><span class="sxs-lookup"><span data-stu-id="4e59f-566">Improved capability for detecting errors and the quality of the sync experience.</span></span>

### <a name="outlook"></a><span data-ttu-id="4e59f-567">Outlook</span><span class="sxs-lookup"><span data-stu-id="4e59f-567">Outlook</span></span>

- <span data-ttu-id="4e59f-568">解决了在啟動某些租使用者的 Outlook 時，會導致嚴重效能問題的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-568">Addressed an issue that caused a significant performance issue when starting Outlook for some tenants.</span></span>

### <a name="skype"></a><span data-ttu-id="4e59f-569">Skype</span><span class="sxs-lookup"><span data-stu-id="4e59f-569">Skype</span></span>

- <span data-ttu-id="4e59f-570">修正了在執行數天後，會無法啟動 32位元 Skype 商務版客戶螢幕共享的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-570">Fixed an issue where starting a screen share can fail on a 32-bit Skype for Business client after it has been running for several days.</span></span>

### <a name="office-suite"></a><span data-ttu-id="4e59f-571">Office 套件</span><span class="sxs-lookup"><span data-stu-id="4e59f-571">Office Suite</span></span>

- <span data-ttu-id="4e59f-572">修正了如果 [自動儲存] 已透過組織政策關閉的話，某些文件可能不會在開啟時顯示最新的伺服器內容，除非使用者點擊 [可用的更新] 才會顯現。</span><span class="sxs-lookup"><span data-stu-id="4e59f-572">Fixed an issue where if AutoSave is turned off through group policy, some documents might not show the latest server contents on open until the user clicks on 'Updates available'.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-august-11"></a><span data-ttu-id="4e59f-574">版本 1908: 8月11日</span><span class="sxs-lookup"><span data-stu-id="4e59f-574">Version 1908: August 11</span></span>
<span data-ttu-id="4e59f-575">*版本 1908 (組建 11929.20934)*</span><span class="sxs-lookup"><span data-stu-id="4e59f-575">*Version 1908 (Build 11929.20934)*</span></span>

<span data-ttu-id="4e59f-576">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4e59f-576">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1902-august-11"></a><span data-ttu-id="4e59f-577">版本 1902: 8月11日</span><span class="sxs-lookup"><span data-stu-id="4e59f-577">Version 1902: August 11</span></span>
<span data-ttu-id="4e59f-578">*版本 1902 (組建 11328.20644)*</span><span class="sxs-lookup"><span data-stu-id="4e59f-578">*Version 1902 (Build 11328.20644)*</span></span>

<span data-ttu-id="4e59f-579">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4e59f-579">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-july-14"></a><span data-ttu-id="4e59f-582">版本 2002：7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="4e59f-582">Version 2002: July 14</span></span>
<span data-ttu-id="4e59f-583">*版本 2002 (組建 12527.20880)*</span><span class="sxs-lookup"><span data-stu-id="4e59f-583">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="4e59f-584">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4e59f-584">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="4e59f-586">功能更新</span><span class="sxs-lookup"><span data-stu-id="4e59f-586">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="4e59f-587">Access</span><span class="sxs-lookup"><span data-stu-id="4e59f-587">Access</span></span>

- <span data-ttu-id="4e59f-588">**快速尋找連結資料表：** 新的搜尋方塊可讓您輕鬆尋找連結資料表。</span><span class="sxs-lookup"><span data-stu-id="4e59f-588">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="4e59f-589">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-589">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="4e59f-590">Excel</span><span class="sxs-lookup"><span data-stu-id="4e59f-590">Excel</span></span>

- <span data-ttu-id="4e59f-591">**更快速共用檔案：** 不需開啟檔案，即可從最近使用清單直接共用您的檔案。</span><span class="sxs-lookup"><span data-stu-id="4e59f-591">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="4e59f-592">**資料視覺化工具增益集：** 從 Excel 快速建立 Visio 流程圖。</span><span class="sxs-lookup"><span data-stu-id="4e59f-592">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="4e59f-593">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-593">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="4e59f-594">**建立更易於存取的 PDF：** 建立 PDF 檔案，在儲存之前，協助工具檢查程式會指出應該修正的協助工具問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-594">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="4e59f-595">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-595">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br /><span data-ttu-id="4e59f-596">在[部落格文章](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="4e59f-596">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="4e59f-597">**符合您情境的更多圖示：** 我們新增了超過 300 個新圖示。</span><span class="sxs-lookup"><span data-stu-id="4e59f-597">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="4e59f-598">其位置：[插入] > [圖示]。</span><span class="sxs-lookup"><span data-stu-id="4e59f-598">Find them at Insert > Icons.</span></span> [<span data-ttu-id="4e59f-599">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-599">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="4e59f-600">**轉換檔案，以改善協助工具功能：** 將您的檔案升級為現代格式，讓所有人更容易存取。</span><span class="sxs-lookup"><span data-stu-id="4e59f-600">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="4e59f-601">在[部落格文章](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="4e59f-601">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="4e59f-602">**專注於剩餘工作：** 選取 [解決] 來摺疊註解，使得開啟中的項目能夠突顯。</span><span class="sxs-lookup"><span data-stu-id="4e59f-602">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="4e59f-603">**輸入會傳回多個值的公式**：現在您可以快速輸入公式來傳回多個值，並且值會自動溢出至相鄰的儲存格。</span><span class="sxs-lookup"><span data-stu-id="4e59f-603">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="4e59f-604">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-604">Learn more</span></span>](https://support.office.com/article/5c2c9cbb-def8-409a-b380-2fbf91b20aa3)<br /><span data-ttu-id="4e59f-605">在[部落格文章](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="4e59f-605">See details in [blog post](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)</span></span>

- <span data-ttu-id="4e59f-606">**不必再來回往返瀏覽器：** 您決定開啟 Office 文件連結的方式：在瀏覽器或應用程式中開啟。</span><span class="sxs-lookup"><span data-stu-id="4e59f-606">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="4e59f-607">**勾勒草圖：** 為活頁簿中的 Office 圖形提供隨意的手繪外觀。</span><span class="sxs-lookup"><span data-stu-id="4e59f-607">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="4e59f-608">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-608">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="4e59f-609">在[部落格文章](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="4e59f-609">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="4e59f-610">**找到您要尋找的項目：** 搜尋命令、人員、檔案、相片、網頁文章等。</span><span class="sxs-lookup"><span data-stu-id="4e59f-610">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="4e59f-611">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-611">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="4e59f-612">**六個功能強大的函數：** 我們新增了六個新的函數，讓您的試算表功能更強大：FILTER、SORT、SORTBY、UNIQUE、SEQUENCE 和 RANDARRAY。</span><span class="sxs-lookup"><span data-stu-id="4e59f-612">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span> [<span data-ttu-id="4e59f-613">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-613">Learn more</span></span>](https://support.office.com/article/003df6c7-1dcb-4388-8e2e-0fe77a0887bc)

- <span data-ttu-id="4e59f-614">**向左看，向右看... XLOOKUP 在這裡！：** 一列接著一列，在含有 XLOOKUP 的表格或範圍中尋找您需要的項目。</span><span class="sxs-lookup"><span data-stu-id="4e59f-614">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span> [<span data-ttu-id="4e59f-615">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-615">Learn more</span></span>](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)<br /><span data-ttu-id="4e59f-616">在[部落格文章](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="4e59f-616">See details in [blog post](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)</span></span>

- <span data-ttu-id="4e59f-617">**整理您的大型活頁簿：** 儲存格、公式、圖表、表格... 利用「活頁簿統計資料」來取得活頁簿的快照。</span><span class="sxs-lookup"><span data-stu-id="4e59f-617">**Tame your big workbook:** Cells, formulas, charts, tables... get a snapshot of your workbook with Workbook Statistics.</span></span>

- <span data-ttu-id="4e59f-618">**即時讀取與回覆：** 直接從電子郵件回覆註解和提及，而不需開啟活頁簿。</span><span class="sxs-lookup"><span data-stu-id="4e59f-618">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="4e59f-619">**使用 \@Mentions 提及功能取得他人注意：** 在註解中使用 @mentions 提及功能，讓同事知道您需要他們提供建議。</span><span class="sxs-lookup"><span data-stu-id="4e59f-619">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="4e59f-620">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-620">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

### <a name="outlook"></a><span data-ttu-id="4e59f-621">Outlook</span><span class="sxs-lookup"><span data-stu-id="4e59f-621">Outlook</span></span>

- <span data-ttu-id="4e59f-622">**在螢幕上容納更多郵件：** 選取 [檢視] > [使用更緊密的間距] 來調整郵件之間的間距。</span><span class="sxs-lookup"><span data-stu-id="4e59f-622">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="4e59f-623">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-623">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="4e59f-624">**符合您情境的更多圖示：** 我們新增了超過 300 個新圖示。</span><span class="sxs-lookup"><span data-stu-id="4e59f-624">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="4e59f-625">其位置：[插入] > [圖示]。</span><span class="sxs-lookup"><span data-stu-id="4e59f-625">Find them at Insert > Icons.</span></span> [<span data-ttu-id="4e59f-626">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-626">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="4e59f-627">**讓我繪製：** 使用筆跡在圖片上徒手畫或新增繪圖畫布來傳達您的想法。</span><span class="sxs-lookup"><span data-stu-id="4e59f-627">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="4e59f-628">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-628">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="4e59f-629">**取得位置建議：** 排程約會和會議時，請在 [位置] 中開始輸入，Outlook 會建議會議室、地址，以及其他最近使用的位置。</span><span class="sxs-lookup"><span data-stu-id="4e59f-629">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="4e59f-630">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-630">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)<br /><span data-ttu-id="4e59f-631">在[部落格文章](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="4e59f-631">See details in [blog post](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/)</span></span>

- <span data-ttu-id="4e59f-632">**抵禦攻擊的進階防護：** 使用 Office 365 進階威脅防護，您會受到保護，不受電子郵件主旨、附加的郵件、簽署的郵件、網路路徑內超連結的攻擊。</span><span class="sxs-lookup"><span data-stu-id="4e59f-632">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="4e59f-633">**Outlook 中的 [插入連結] 功能表會插入含有租用戶系統管理員所定義的權限的連結：** Outlook 中使用 [插入連結] 所插入的連結，只有具有連結權限的使用者可使用。</span><span class="sxs-lookup"><span data-stu-id="4e59f-633">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="4e59f-634">這常會造成使用者來回傳送電子郵件，要求對方授與文件的存取權。</span><span class="sxs-lookup"><span data-stu-id="4e59f-634">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="4e59f-635">我們已更新這項體驗，現在插入的連結將具有由租用戶系統管理員設定的預設權限。針對 MSIT，這是「組織可以編輯」，使得以此方式收到共用連結的所有內部使用者將可以存取它。</span><span class="sxs-lookup"><span data-stu-id="4e59f-635">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="4e59f-636">**在不同燈光下查看郵件：** 使用太陽/月亮按鈕以在讀取窗格中於淺色和深色背景之間切換。</span><span class="sxs-lookup"><span data-stu-id="4e59f-636">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="4e59f-637">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-637">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="4e59f-638">**網路釣魚郵件很容易找到：** 垃圾郵件和網路釣魚訊息的外觀不同，因此您可以從收件匣輕鬆找出並加以清除。</span><span class="sxs-lookup"><span data-stu-id="4e59f-638">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="4e59f-p159">**集中所有加密選項：** 只要前往 [選項] > [加密]，即可選擇要用來保護電子郵件訊息的方法。[深入了解](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="4e59f-p159">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="4e59f-641">**具有拼字問題或錯字的搜尋：** 即使您的拼寫不相符，Outlook 也會找到您要尋找的內容。</span><span class="sxs-lookup"><span data-stu-id="4e59f-641">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="4e59f-642">**將您的 LinkedIn 人際網路連接至 Outlook：** 安全地將您的 LinkedIn 帳戶與 Microsoft 帳戶連結，以直接在人員卡片中查看 LinkedIn 個人資料中的資訊。</span><span class="sxs-lookup"><span data-stu-id="4e59f-642">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="4e59f-643">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-643">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="4e59f-644">**在搜尋結果中查看相關郵件：** Outlook 會分析搜尋字詞，然後在搜尋結果的最上方顯示最相關的電子郵件。</span><span class="sxs-lookup"><span data-stu-id="4e59f-644">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="4e59f-645">您也可以在 [最佳結果] 區段中查看依日期排列順序的所有結果。</span><span class="sxs-lookup"><span data-stu-id="4e59f-645">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="4e59f-646">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-646">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

### <a name="powerpoint"></a><span data-ttu-id="4e59f-647">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4e59f-647">PowerPoint</span></span>

- <span data-ttu-id="4e59f-p162">**您來計算，格式設定交給我們** 我們能將難懂的手寫數學運算式變更為標準字元。只要選擇 [筆跡轉換數學]，然後選取您的手寫筆記，即可開始使用。[深入了解](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="4e59f-p162">**You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

- <span data-ttu-id="4e59f-651">**尋找您要尋找的項目：** 使用搜尋方塊來尋找文字、命令、說明等。</span><span class="sxs-lookup"><span data-stu-id="4e59f-651">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="4e59f-652">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-652">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="4e59f-653">**運用筆跡製作精彩的投影片：** 將筆跡轉換成標準圖形和文字，然後從 PowerPoint 設計工具吸取智慧的投影片設計概念。</span><span class="sxs-lookup"><span data-stu-id="4e59f-653">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="4e59f-654">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-654">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- <span data-ttu-id="4e59f-655">**勾勒草圖：** 為簡報中的 Office 圖形提供隨意的手繪外觀。</span><span class="sxs-lookup"><span data-stu-id="4e59f-655">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="4e59f-656">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-656">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="4e59f-657">在[部落格文章](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="4e59f-657">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="4e59f-658">**筆跡立即重播：** 當您在投影片上進行手寫時，套用重播動畫可在投影片放映期間重播真實手繪的筆跡。</span><span class="sxs-lookup"><span data-stu-id="4e59f-658">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="4e59f-659">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-659">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)<br /><span data-ttu-id="4e59f-660">在[部落格文章](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="4e59f-660">See details in [blog post](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/)</span></span>

- <span data-ttu-id="4e59f-661">**更安全的影片體驗：** 安全性增強功能可讓您擁有更安全的線上影片體驗。</span><span class="sxs-lookup"><span data-stu-id="4e59f-661">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="4e59f-662">**將圖例另存成 SVG：** 將圖表、圖形或其他圖例另存成可縮放向量圖形，其可調整大小，且不損失影像品質。</span><span class="sxs-lookup"><span data-stu-id="4e59f-662">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="4e59f-663">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-663">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="4e59f-664">**列印講義上的投影片編號：** 投影片編號會自動包含在講義上。</span><span class="sxs-lookup"><span data-stu-id="4e59f-664">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="4e59f-665">由您決定將其保留或關閉。</span><span class="sxs-lookup"><span data-stu-id="4e59f-665">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="4e59f-666">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-666">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="4e59f-667">**尋找並修正遺失的投影片標題：** 投影片標題可為您的企劃加分，並讓所有功能的使用者都能存取投影片。</span><span class="sxs-lookup"><span data-stu-id="4e59f-667">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="4e59f-668">協助工具檢查程式會顯示缺少標題的地方，這樣您就可以快速新增標題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-668">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="4e59f-669">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-669">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="4e59f-670">**轉換檔案，以改善協助工具功能：** 將您的檔案升級為現代格式，讓所有人更容易存取。</span><span class="sxs-lookup"><span data-stu-id="4e59f-670">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="4e59f-671">在[部落格文章](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="4e59f-671">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="4e59f-672">**符合您情境的更多圖示：** 我們新增了超過 300 個新圖示。</span><span class="sxs-lookup"><span data-stu-id="4e59f-672">**More icons to match your mood:** We've added more than 300 new icons.</span></span> <span data-ttu-id="4e59f-673">其位置：[插入] > [圖示]。</span><span class="sxs-lookup"><span data-stu-id="4e59f-673">Find them at Insert > Icons.</span></span> [<span data-ttu-id="4e59f-674">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-674">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="4e59f-675">**建立更易於存取的 PDF：** 建立 PDF 檔案，在儲存之前，協助工具檢查程式會指出應該修正的協助工具問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-675">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span><br /><span data-ttu-id="4e59f-676">在[部落格文章](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="4e59f-676">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="4e59f-677">**更快速共用檔案：** 不需開啟檔案，即可從最近使用清單直接共用您的檔案。</span><span class="sxs-lookup"><span data-stu-id="4e59f-677">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="4e59f-678">**在 PowerPoint 中快速即時共同作業：** 在 PowerPoint 中快速即時共同作業</span><span class="sxs-lookup"><span data-stu-id="4e59f-678">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="4e59f-679">**不必再來回往返瀏覽器：** 您決定開啟 Office 文件連結的方式：在瀏覽器或應用程式中開啟。</span><span class="sxs-lookup"><span data-stu-id="4e59f-679">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="4e59f-680">**新的校對工具：** 不著重您的文字。</span><span class="sxs-lookup"><span data-stu-id="4e59f-680">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="4e59f-681">PowerPoint 現在提供文法及書寫建議。</span><span class="sxs-lookup"><span data-stu-id="4e59f-681">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="4e59f-682">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-682">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="4e59f-683">**即時的輔助字幕和翻譯字幕：** 簡報者的文字會自動顯示為畫面上的標題，或翻譯為所選語言的字幕。</span><span class="sxs-lookup"><span data-stu-id="4e59f-683">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="4e59f-684">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-684">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="4e59f-685">**最佳化您的簡報：** 協助工具檢查程式可協助您以螢幕閱讀器為中心，在投影片上排列物件。</span><span class="sxs-lookup"><span data-stu-id="4e59f-685">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span><br /><span data-ttu-id="4e59f-686">在[部落格文章](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="4e59f-686">See details in [blog post](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/)</span></span>

- <span data-ttu-id="4e59f-687">**當您可以重複使用時為什麼要重新打造？** 重複使用您所建立的投影片或其他人與您共用的投影片來以節省時間。</span><span class="sxs-lookup"><span data-stu-id="4e59f-687">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="4e59f-688">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-688">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

### <a name="visio"></a><span data-ttu-id="4e59f-689">Visio</span><span class="sxs-lookup"><span data-stu-id="4e59f-689">Visio</span></span>

- <span data-ttu-id="4e59f-690">**在 Excel 中製作精美的 Visio 圖表：** 將資料放在工作表上，以建立流程圖或組織圖。</span><span class="sxs-lookup"><span data-stu-id="4e59f-690">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="4e59f-691">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-691">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="4e59f-692">**回到犯罪場景：** 在犯罪場景調查範本中使用新的證據、室內、室外樣板，重建犯罪場景的細節。</span><span class="sxs-lookup"><span data-stu-id="4e59f-692">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

### <a name="word"></a><span data-ttu-id="4e59f-693">Word</span><span class="sxs-lookup"><span data-stu-id="4e59f-693">Word</span></span>

- <span data-ttu-id="4e59f-694">**更安全的影片體驗：** 安全性增強功能可讓您擁有更安全的線上影片體驗。</span><span class="sxs-lookup"><span data-stu-id="4e59f-694">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="4e59f-695">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-695">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- <span data-ttu-id="4e59f-696">**建立更易於存取的 PDF：** 建立 PDF 檔案，在儲存之前，協助工具檢查程式會指出應該修正的協助工具問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-696">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="4e59f-697">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-697">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br /><span data-ttu-id="4e59f-698">在[部落格文章](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="4e59f-698">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="4e59f-699">**更快速共用檔案：** 不需開啟檔案，即可從最近使用清單直接共用您的檔案。</span><span class="sxs-lookup"><span data-stu-id="4e59f-699">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="4e59f-700">**符合您情境的更多圖示：** 我們新增了超過 300 個新圖示。</span><span class="sxs-lookup"><span data-stu-id="4e59f-700">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="4e59f-701">其位置：[插入] > [圖示]。</span><span class="sxs-lookup"><span data-stu-id="4e59f-701">Find them at Insert > Icons.</span></span> [<span data-ttu-id="4e59f-702">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-702">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)<br /><span data-ttu-id="4e59f-703">在[部落格文章](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="4e59f-703">See details in [blog post](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/)</span></span>

- <span data-ttu-id="4e59f-704">**精確橡皮擦：** 從兩個橡皮擦尺寸中選擇，以修正小型筆跡缺陷。</span><span class="sxs-lookup"><span data-stu-id="4e59f-704">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="4e59f-705">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-705">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="4e59f-706">**轉換檔案，以改善協助工具功能：** 將您的檔案升級為現代格式，讓所有人更容易存取。</span><span class="sxs-lookup"><span data-stu-id="4e59f-706">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="4e59f-707">在[部落格文章](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="4e59f-707">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="4e59f-708">**勾勒草圖：** 為文件中的 Office 圖形提供隨意的手繪外觀。</span><span class="sxs-lookup"><span data-stu-id="4e59f-708">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="4e59f-709">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-709">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="4e59f-710">在[部落格文章](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="4e59f-710">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="4e59f-711">**尋找您要尋找的項目：** 使用搜尋方塊來尋找文字、命令、說明等。</span><span class="sxs-lookup"><span data-stu-id="4e59f-711">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="4e59f-712">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-712">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="4e59f-713">**不必再來回往返瀏覽器：** 您決定開啟 Office 文件連結的方式：在瀏覽器或應用程式中開啟。</span><span class="sxs-lookup"><span data-stu-id="4e59f-713">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="4e59f-714">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-714">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="4e59f-715">**簡歷編輯器加入 LinkedIn 簡歷小幫手：** 簡歷編輯器提供特別為簡歷量身打造的文法和樣式檢查選項，讓您的寫作更準確且更專業。</span><span class="sxs-lookup"><span data-stu-id="4e59f-715">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="4e59f-716">**其他人更快速看到您的變更：** 共同撰寫增強功能表示，共同作業者可較以往更快速看到您的變更。</span><span class="sxs-lookup"><span data-stu-id="4e59f-716">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="4e59f-717">**修正合併 3D 物件所造成的文件損毀問題：** 修正合併 3D 物件所造成的文件損毀問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-717">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="4e59f-718">**共同撰寫的增強功能**：在具有追蹤修訂的文件中共同撰寫來強化 Word 效能。</span><span class="sxs-lookup"><span data-stu-id="4e59f-718">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="4e59f-719">**共同撰寫的增強功能**：增強共同撰寫時的可靠性。</span><span class="sxs-lookup"><span data-stu-id="4e59f-719">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="4e59f-720">**在生動色彩中進行共同作業：** 註解和變更都依參與者加上色彩標示，讓您可以輕鬆查看您的共同作業者。</span><span class="sxs-lookup"><span data-stu-id="4e59f-720">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="4e59f-721">**共同編輯啟用巨集的文件：** 將 docm 檔案儲存在商務用 OneDrive，並與共同作業者即時編輯。</span><span class="sxs-lookup"><span data-stu-id="4e59f-721">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

### <a name="office-suite"></a><span data-ttu-id="4e59f-722">Office 套件</span><span class="sxs-lookup"><span data-stu-id="4e59f-722">Office Suite</span></span>

- <span data-ttu-id="4e59f-723">**在 Office 365 的 PowerPoint 中將手寫筆跡變更為圖形、文字或數學：** 從任意格式的筆跡變成 Office 圖形、文字，或以幾個筆劃變成數學運算式。</span><span class="sxs-lookup"><span data-stu-id="4e59f-723">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="4e59f-724">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-724">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="4e59f-727">解決的問題</span><span class="sxs-lookup"><span data-stu-id="4e59f-727">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="4e59f-728">Access</span><span class="sxs-lookup"><span data-stu-id="4e59f-728">Access</span></span>

- <span data-ttu-id="4e59f-729">此更新會修正使用 ADODB 的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-729">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="4e59f-730">VB 程式碼中的記錄器物件可能會不正確地報告錯誤。</span><span class="sxs-lookup"><span data-stu-id="4e59f-730">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="4e59f-731">Access 範本應不再導致資料庫中的附件欄出現故障。</span><span class="sxs-lookup"><span data-stu-id="4e59f-731">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="4e59f-732">個體化範本後，您現在應該可以將附件欄新增至資料庫。</span><span class="sxs-lookup"><span data-stu-id="4e59f-732">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="4e59f-733">此更新修正可能會導致 Microsoft Access 無法識別連結的 SQL Server 資料表中的識別資料行的問題，這可能會導致不正確地將資料列報告為已刪除。</span><span class="sxs-lookup"><span data-stu-id="4e59f-733">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="4e59f-734">此更新可修正 Microsoft Access 中的「更新查詢」執行時或在 SQL 中使用 UPDATE 陳述式時，可能導致錯誤「查詢已損壞」的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-734">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="4e59f-735">Excel</span><span class="sxs-lookup"><span data-stu-id="4e59f-735">Excel</span></span>

- <span data-ttu-id="4e59f-736">加速載入本機 OneDrive 資料夾中的檔案。</span><span class="sxs-lookup"><span data-stu-id="4e59f-736">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="4e59f-737">修正 CUBEVALUE 函數有時會傳回不正確結果的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-737">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="4e59f-738">解決開啟內嵌活頁簿時，功能區自訂無法載入的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-738">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="4e59f-739">在 Word 或 PowerPoint 中重新開啟內嵌的活頁簿時，在某些情況下 Excel 會當機。</span><span class="sxs-lookup"><span data-stu-id="4e59f-739">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="4e59f-740">修正操作功能表中的註解命令未顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-740">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="4e59f-741">我們修正了樞紐分析圖的右鍵功能表，以啟用 [顯示詳細資料] 選項。</span><span class="sxs-lookup"><span data-stu-id="4e59f-741">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="4e59f-742">解決在未開啟活頁簿時，搜尋最近使用的檔案會造成當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-742">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="4e59f-743">修正在相同活頁簿中按一下加入書籤的超連結會導致活頁簿隱藏的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-743">Fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="4e59f-744">儲存為 CSV 檔案時，在某些情況下，Excel 會將所有欄合併成單一欄。</span><span class="sxs-lookup"><span data-stu-id="4e59f-744">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="4e59f-745">在受保護工作表中的範圍使用 Range.ClearContents 可能會比預期花的時間更長。</span><span class="sxs-lookup"><span data-stu-id="4e59f-745">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="4e59f-746">修正了在 [預覽列印] 中顯示表單控制項時的文字縮放比例問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-746">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="4e59f-747">與功能區互動的 VBA 宏可能會意外以 ScreenUpdating 設定為 True 執行。</span><span class="sxs-lookup"><span data-stu-id="4e59f-747">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="4e59f-748">修正在複製含有樞紐分析表的工作表後，會於某些情況下導致 Excel 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-748">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="4e59f-749">在某些情況下，開啟 CSV 檔案所花費的時間超過預期。</span><span class="sxs-lookup"><span data-stu-id="4e59f-749">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="4e59f-750">在某些情況下，當您切換不同縮放比例的活頁簿時，Excel 可能會當機。</span><span class="sxs-lookup"><span data-stu-id="4e59f-750">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="4e59f-751">已修正 VBA 將值寫入範圍時，速度比預期慢的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-751">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="4e59f-752">從有色彩篩選的欄複製的資料有時候無法正確貼上。</span><span class="sxs-lookup"><span data-stu-id="4e59f-752">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="4e59f-753">開啟含有許多其他活頁簿 (尤其是含有隱藏視窗) 參照的活頁簿時，速度比預期慢。</span><span class="sxs-lookup"><span data-stu-id="4e59f-753">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="4e59f-754">解決當來源活頁簿關閉時，外部連結在填滿時 (向下填滿、跨表填滿等) 不會更新的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-754">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is& closed.</span></span>

- <span data-ttu-id="4e59f-755">修正透過 Teams 共用 Excel 視窗時，使用 Ctrl+Shift+方向鍵來捲動之後，可能會使得 Excel 未回應的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-755">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="4e59f-756">在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。</span><span class="sxs-lookup"><span data-stu-id="4e59f-756">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="4e59f-757">解決在儲存並重新開啟檔案時，圖表軸上的「值置於」屬性非預期變更的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-757">Addresses an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="4e59f-758">修正儲存至 SharePoint/OneDrive 時，會導致將自訂功能區索引標籤的 CustomUI XML 移除的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-758">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="4e59f-759">改善刪除具有合併儲存格的欄時的效能。</span><span class="sxs-lookup"><span data-stu-id="4e59f-759">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="4e59f-760">修正 [列印] 對話方塊的印表機清單中，印表機名稱可能會重複的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-760">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="4e59f-761">修正當檔案路徑太長時，在重新開啟檔案後，外部連結會停止運作的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-761">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="4e59f-762">已修正列印時表單控制項的核取方塊縮放的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-762">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="4e59f-763">當您使用舊版的「共用活頁簿」模式，嘗試為活頁簿的新工作表列出變更時，就會發生當機。</span><span class="sxs-lookup"><span data-stu-id="4e59f-763">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="4e59f-764">在已篩選清單中插入欄的時間會比預期更長。</span><span class="sxs-lookup"><span data-stu-id="4e59f-764">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="4e59f-765">我們已修正某些複製和貼上的圖表連結使用的是對應磁碟機位址，而不是通用位址的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-765">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="4e59f-766">修正因為增益集是以字母順序載入，而不是以使用者指定的順序載入，而顯示 [這個活頁簿目前正由其他活頁簿所參考中，不可關閉] 錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-766">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="4e59f-767">修正按一下已開啟活頁簿中某個位置的超連結時，活頁簿可能會隱藏的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-767">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="4e59f-768">開啟含有許多其他活頁簿 (尤其是含有隱藏視窗) 參照的活頁簿時，速度比預期慢。</span><span class="sxs-lookup"><span data-stu-id="4e59f-768">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="4e59f-769">使用 VBA 應用程式的 Application.Evaluate 在某些情況下，對使用者定義的函數無法運作。</span><span class="sxs-lookup"><span data-stu-id="4e59f-769">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="4e59f-770">修正某些使用者使用內嵌和連結物件 (OLE) 時可能發生的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-770">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="4e59f-771">使用者在使用某些非英文字元集的情況下，儲存變更時可能會遇到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-771">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="4e59f-772">此更新可修正會導致資料編輯列以較預期不同的字型顯示文字的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-772">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="4e59f-773">使用者在使用某些非英文字元集的情況下，儲存變更時可能會遇到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-773">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="4e59f-774">解決捲動後選取儲存格時，可能導致選取錯誤儲存格的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-774">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="4e59f-775">使用者在存取隱藏的命名範圍時可能會遇到錯誤。</span><span class="sxs-lookup"><span data-stu-id="4e59f-775">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="4e59f-776">從不受信任的網路共用編輯受保護的檔案時，Excel 可能會發生問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-776">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="4e59f-777">某些當地語系化版本的 [文字到欄] 功能可能會失敗。</span><span class="sxs-lookup"><span data-stu-id="4e59f-777">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="4e59f-778">解決從範本建立圖表時的效能問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-778">Addresses a performance issue when creating charts from templates.</span></span>

- <span data-ttu-id="4e59f-779">修正對具有溢出陣列之儲存格進行資料剖析的轉換時，導致某些使用者發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-779">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="4e59f-780">使用 Range.Value 和 Range.Value2 (VBA) 會導致公式以動態陣列的形式輸入。</span><span class="sxs-lookup"><span data-stu-id="4e59f-780">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

- <span data-ttu-id="4e59f-781">修正公式開頭的 @ 符號會被視為隱含交集運算子的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-781">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

- <span data-ttu-id="4e59f-782">我們已修正包含多個含有定義名稱的公式，會導致儲存檔案時間加長的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-782">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

- <span data-ttu-id="4e59f-783">此變更利用軟體轉譯，以避免特定 Intel 圖形驅動程式的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-783">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="4e59f-784">解決重新命名簽名時，會導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-784">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="onenote"></a><span data-ttu-id="4e59f-785">OneNote</span><span class="sxs-lookup"><span data-stu-id="4e59f-785">OneNote</span></span>

- <span data-ttu-id="4e59f-786">透過暫時調整 OneNote 2016 中的同步處理頻率，來改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="4e59f-786">Improve sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="4e59f-787">透過暫時延遲下載線上筆記本中內嵌的檔案和影像，直到使用者瀏覽至 OneNote 2016 中的頁面，來改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="4e59f-787">Improve sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="4e59f-788">透過暫時停用 OneNote 2016 中的資源回收筒，來改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="4e59f-788">Improve sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="4e59f-789">當使用者嘗試刪除通常會傳送到 [資源回收筒] 的資料時，系統會詢問使用者是否希望保留或永久刪除資料。</span><span class="sxs-lookup"><span data-stu-id="4e59f-789">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="4e59f-790">透過暫時將 OneNote 2016 中版本歷程記錄頁面的數目和同步處理頻率降低，來改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="4e59f-790">Improve sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="4e59f-791">顯示通知，讓使用者可以了解更多 OneNote 使用者體驗中正在採取的臨時措施的資訊，以改善同步處理和服務穩定性。</span><span class="sxs-lookup"><span data-stu-id="4e59f-791">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="4e59f-792">透過暫時將 OneNote 2016 中新嵌入附件的最大允許大小減少為 50 MB，來改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="4e59f-792">Improve sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="4e59f-793">對於超過此限制的檔案，使用者可以選擇將檔案上傳到 OneDrive，並將連結插入 OneNote。</span><span class="sxs-lookup"><span data-stu-id="4e59f-793">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="4e59f-794">透過暫時停用 OneNote 2016 中的應用程式內視訊錄製，來改善同步處理與服務的穩定性。</span><span class="sxs-lookup"><span data-stu-id="4e59f-794">Improve sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="4e59f-795">本機筆記本不受這個測量的影響。</span><span class="sxs-lookup"><span data-stu-id="4e59f-795">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="4e59f-796">對通知進行本地化，讓使用者可以了解更多 OneNote 使用者體驗中正在採取的臨時措施的資訊，以改善同步處理和服務穩定性。</span><span class="sxs-lookup"><span data-stu-id="4e59f-796">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="4e59f-797">Outlook</span><span class="sxs-lookup"><span data-stu-id="4e59f-797">Outlook</span></span>

- <span data-ttu-id="4e59f-798">我們已修正以下問題：當使用多個不同解析度的監視器時，輸入法編輯器 (IEM) 視窗會覆蓋透過 IME 輸入的文字。</span><span class="sxs-lookup"><span data-stu-id="4e59f-798">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="4e59f-799">解決會導致使用者在 Outlook 中偶爾看到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-799">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

- <span data-ttu-id="4e59f-800">此這會更新 Outlook 中的附件封鎖邏輯，以同時封鎖 Python 附件。</span><span class="sxs-lookup"><span data-stu-id="4e59f-800">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="4e59f-801">解決會導致網頁增益集存取數位版權管理訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-801">Addresses an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="4e59f-802">解決會導致週期性約會或會議在接近時區定義變更時於錯誤的時間顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-802">Addresses an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="4e59f-803">在 2019 年使用巴西時區時，週期性會議和約會以 2020 年的錯誤時段顯示。</span><span class="sxs-lookup"><span data-stu-id="4e59f-803">When using the Brazilia time zone in the year 2019, recurring meetings and appointments are displayed in the wrong timeslot for the year 2020.</span></span> <span data-ttu-id="4e59f-804">此變更與設定使用巴西時區的用戶端或設定使用該時區的會議和約會相關。</span><span class="sxs-lookup"><span data-stu-id="4e59f-804">This change is relevant for clients set in the Brazilia time zone or for meetings and appointments set in that time zone.</span></span><br><br><span data-ttu-id="4e59f-805">此變更會允許 Outlook 覆寫 Outlook 所使用的特定時區設定。</span><span class="sxs-lookup"><span data-stu-id="4e59f-805">This change allows Outlook to override certain time zone settings used by Outlook.</span></span> <span data-ttu-id="4e59f-806">若要叫用時區覆寫，您必須為目前的使用者設定登錄機碼。</span><span class="sxs-lookup"><span data-stu-id="4e59f-806">In order to invoke a time zone override you must set a registry key for the current user.</span></span> <span data-ttu-id="4e59f-807">登錄機碼名稱必須符合時區的內部名稱。</span><span class="sxs-lookup"><span data-stu-id="4e59f-807">The registry key name must match the internal name of the time zone.</span></span> <span data-ttu-id="4e59f-808">值表示時區規則的年，用來取代生效年。</span><span class="sxs-lookup"><span data-stu-id="4e59f-808">The value indicates the time zone rule's year to be used in place of the effective year.</span></span> <span data-ttu-id="4e59f-809">例如，下列登錄機碼覆寫值將使用巴西時區規則做為 2020 年的生效規則。</span><span class="sxs-lookup"><span data-stu-id="4e59f-809">For example, the following registry key override value will use the Brazilia time zone rule for the year 2020 as the effective rule.</span></span> <span data-ttu-id="4e59f-810">HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"E.</span><span class="sxs-lookup"><span data-stu-id="4e59f-810">HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"E.</span></span> <span data-ttu-id="4e59f-811">South America Standard Time"=dword:000007e4.</span><span class="sxs-lookup"><span data-stu-id="4e59f-811">South America Standard Time"=dword:000007e4.</span></span>

- <span data-ttu-id="4e59f-812">解決會導致使用者在會議中看到位置欄位非預期變更的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-812">Addresses an issue that caused users to see the location field in meetings change unexpectedly.</span></span>

- <span data-ttu-id="4e59f-813">解決會導致會議中的 [位置] 欄位非預期更新的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-813">Addresses an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="4e59f-814">解決會導致會議位置在清除之後，又會非預期地重新加回會議的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-814">Addresses an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="4e59f-815">解決會導致會議的位置欄位中的逗號變成分號的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-815">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="4e59f-816">可透過原生 Teams 用戶端直接加入 Teams 會議。</span><span class="sxs-lookup"><span data-stu-id="4e59f-816">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="4e59f-817">解決會導致使用 Exchange 2010 伺服器上信箱的使用者，在將附件新增至行事曆項目時遇到問題的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-817">Addresses an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="4e59f-818">解決會導致使用者在回覆數位簽章郵件時遇到問題的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-818">Addresses an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="4e59f-819">解決會導致使用者無法開啟某些週期性行事曆項目執行個體的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-819">Addresses an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="4e59f-820">解決在某些情況下，[群組] 標題會非預期展開的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-820">Addresses an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="4e59f-821">解決會導致資料夾窗格寬度非預期地變更的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-821">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="4e59f-822">解決 Outlook 無法為已支付 M365 Business Plus 方案服務的使用者啟用「資料外洩防護」原則提示的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-822">Addresses an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="4e59f-823">解決當使用者透過鍵盤快速鍵與信箱資料夾互動時，會導致明顯延遲的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-823">Addresses an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="4e59f-824">解決在多個視窗中檢視相同項目時可能會導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-824">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="4e59f-825">解決會導致使用者在 Outlook 中更新其規則時，看到「此電腦上的規則與 Microsoft Exchange 上的規則不相符」訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-825">Addresses an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="4e59f-826">解決會導致非常長時間的 Outlook 工作階段記憶體流失的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-826">Addresses an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="4e59f-827">解決會導致使用者在指定無效寄件者地址時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-827">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="4e59f-828">解決會導致使用者在開啟 [規則] 對話方塊時看到「此電腦上的規則與 Microsoft Exchange 上的規則不相符」提示的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-828">Addresses an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="4e59f-829">解決會導致在某些情況下，用來停用標幟項目醒目提示的選項無法使用的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-829">Addresses an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="4e59f-830">解決在關閉協助工具檢查程式窗格之後按 S 鍵時，會導致使用者看到郵件非預期傳送的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-830">Addresses an issue that caused users to see mails unexpectedly send when pressing the "S" key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="4e59f-831">解決重新命名簽名時，會導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-831">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="4e59f-832">解決會導致使用者在取消帳戶設定時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-832">Addresses an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="4e59f-833">解決即使將同步處理滑桿設定為較小的設定，也會導致 Outlook 非預期地同步處理所有郵件的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-833">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="4e59f-834">解決會導致使用黑色佈景主題的使用者，看到 [寄件者] 下拉式功能表在白色背景上顯示白色文字的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-834">Addresses an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>

- <span data-ttu-id="4e59f-835">解決會導致使用者在建立設定檔期間遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-835">Addresses an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="4e59f-836">解決會導致使用者在嘗試從 [帳戶建立] 內容連絡支援服務時，看到具有 [確定] 按鈕的空白訊息方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-836">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="4e59f-837">解決會導致使用者在嘗試從 [帳戶建立] 內容連絡支援服務時，看到具有 [確定] 按鈕的空白訊息方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-837">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="4e59f-838">解決會導致協力廠商應用程式無法傳送電子郵件的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-838">Addresses an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="4e59f-839">解決有時候會導致類別從電子郵件訊息中消失的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-839">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="4e59f-840">解決會導致伺服器作業系統上的 Outlook 使用者看到「防毒軟體狀態: 無效」的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-840">Addresses an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="4e59f-841">此版本的 Windows 支援防毒軟體偵測，但即使已適當設定防毒軟體，也找不到防毒軟體。</span><span class="sxs-lookup"><span data-stu-id="4e59f-841">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

- <span data-ttu-id="4e59f-842">解決會導致代理人在不同機器上所看到的共用信箱有不同資料夾階層的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-842">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="4e59f-843">解決在編輯經理行事曆上的現有行事曆約會時，導致代理人收到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-843">Addresses an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="4e59f-844">解決會導致使用不正確瀏覽器模擬設定的使用者，無法完成 Gmail 身分驗證提示的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-844">Addresses an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="4e59f-845">解決會導致若「未」核取 [下載共用資料夾]，共用行事曆會議的 [回應選項] 中會遺失 [允許轉寄] 選項的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-845">Addresses an issue that caused the " Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="4e59f-846">解決會導致在 Windows 更新之後，使用者嘗試開啟 .msg 和 .oft 檔案時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-846">Addresses an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="4e59f-847">解決會導致使用滑鼠上的 X 按鈕時，使用者偶爾遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-847">Addresses an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="4e59f-848">解決會導致使用者在選取特定搜尋結果時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-848">Addresses an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="4e59f-849">解決會讓 [附件工具] 中的 [儲存至雲端] 按鈕不見的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-849">Addresses an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="4e59f-850">此變更可還原在郵件標頭中檢視多行主旨的功能。</span><span class="sxs-lookup"><span data-stu-id="4e59f-850">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="4e59f-851">解決當兩個增益集將一個按鈕新增到相同功能區群組時，會導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-851">Addresses an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="4e59f-852">解決當租用戶預設權限設定為「任何人」時，會導致無法將連結新增至具有正確租用戶預設權限的電子郵件的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-852">Addresses an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as "anyone".</span></span>

- <span data-ttu-id="4e59f-853">解決會導致使用者無法將電子郵件傳送到個人通訊群組清單的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-853">Addresses an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="4e59f-854">解決在轉寄大型 HTML 郵件時，會導致使用者看到郵件內文截斷的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-854">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="4e59f-855">修正 SMIME 演算法選取的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-855">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="4e59f-856">我們已修正可能會防止將檔案儲存到 WebDAV 位置的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-856">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="4e59f-857">解決選取安全性對話方塊上的 [儲存] 選項時，會導致使用者無法將來自其租用戶外部的 OneDrive 附件儲存至其本機電腦的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-857">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="4e59f-858">解決在編輯主旨之後，會導致 NDR 訊息的本文從 Unicode 變更為 ASCII 的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-858">Addresses an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="4e59f-859">解決會導致使用者在 Outlook 處理程序中看到記憶體流失的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-859">Addresses an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="4e59f-860">解決在某些情況下，導致使用者看到電子郵件傳送到與顯示的 SMTP 位址不相符之地址的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-860">Addresses an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="4e59f-861">解決會導致搜尋方塊在高 DPI 模式中對齊不當的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-861">Addresses an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="4e59f-862">解決在擷取雲端設定時，會導致使用者在 Outlook 中遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-862">Addresses an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="4e59f-863">解決會導致在搜尋意見反應體驗中懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-863">Addresses an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="4e59f-864">解決會導致使用者在 Outlook 中偶爾看到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-864">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

- <span data-ttu-id="4e59f-865">解決重新命名簽名時，會導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-865">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="4e59f-866">解決會導致使用者在建立設定檔期間遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-866">Addresses an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="4e59f-867">解決會導致使用者在 Outlook 中偶爾看到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-867">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="4e59f-868">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4e59f-868">PowerPoint</span></span>

- <span data-ttu-id="4e59f-869">解決在舊版 PPT 註解中使用操作功能表時，可能會導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-869">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

- <span data-ttu-id="4e59f-870">改善複製貼上的案例：將 PowerPoint 投影片中的圖形複製並重複貼到其他投影片中，可能會出現例外狀況而失敗。</span><span class="sxs-lookup"><span data-stu-id="4e59f-870">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>

- <span data-ttu-id="4e59f-871">修正問題，以在開啟的檔案複本具有改善的註解時，為使用者轉送正確的訊息。</span><span class="sxs-lookup"><span data-stu-id="4e59f-871">Fixes an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="project"></a><span data-ttu-id="4e59f-872">Project</span><span class="sxs-lookup"><span data-stu-id="4e59f-872">Project</span></span>

- <span data-ttu-id="4e59f-873">修正無法正確計算摘要工作日期的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-873">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="4e59f-874">修正不先執行 OpenUndoTransaction 方法就不能觸發 OnUndoOrRedo 事件的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-874">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="4e59f-875">修正透過 [已停用] 按鈕停用/啟動工作時，ProjectBeforeTaskChange 事件無法偵測的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-875">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="4e59f-876">修正儲存使用舊版 Project 建立的專案時，Project 可能當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-876">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="4e59f-877">發現在開啟唯讀專案時，使用者可能會收到數個訊息的問題</span><span class="sxs-lookup"><span data-stu-id="4e59f-877">Identified an issue where users could get several messages when opening a read-only project</span></span>

- <span data-ttu-id="4e59f-878">已修正以下問題：固定工期類型的 100% 工作可能會誤將其完成百分比計算為小於 100% 完成。</span><span class="sxs-lookup"><span data-stu-id="4e59f-878">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

### <a name="word"></a><span data-ttu-id="4e59f-879">Word</span><span class="sxs-lookup"><span data-stu-id="4e59f-879">Word</span></span>

- <span data-ttu-id="4e59f-880">解決會導致使用滑鼠上的 X 按鈕時，使用者偶爾遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-880">Addresses an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="4e59f-881">我們已修正文件中的文字對齊，在使用 [快速列印] 進行列印之後嘗試進行編輯時變得混亂的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-881">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="4e59f-882">我們修正了表格中最適文字大小的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-882">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="4e59f-883">我們修正了插入水平線無法更短並置中的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-883">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>

- <span data-ttu-id="4e59f-884">建置組塊組合管理可能會顯示無效的通知：「您已經修改樣式、建置組塊」。</span><span class="sxs-lookup"><span data-stu-id="4e59f-884">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

- <span data-ttu-id="4e59f-885">我們已修正啟用原則 FileBlick\Word2007Files 時共同編輯中的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-885">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="4e59f-886">我們已修正新增已重新命名之查閱欄位時，Word QuickPart 無法使用的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-886">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

- <span data-ttu-id="4e59f-887">我們已修正將兩份文件合併成一份文件時的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-887">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="4e59f-888">修正受保護無法編輯之文件的比較功能問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-888">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="4e59f-889">此更新解決了 Microsoft Word 中的一個問題：如果標籤原則套用了頁首或頁尾或浮水印，那麼在套用敏感度標籤時，插入長度超過 255 個字元的文字後續將無法透過變更或刪除標籤來識別和刪除。</span><span class="sxs-lookup"><span data-stu-id="4e59f-889">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

### <a name="office-suite"></a><span data-ttu-id="4e59f-890">Office 套件</span><span class="sxs-lookup"><span data-stu-id="4e59f-890">Office Suite</span></span>

- <span data-ttu-id="4e59f-891">修正當共同撰寫大型 PowerPoint 檔案時，使用者可能會遇到過度網路和 CPU 使用量的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-891">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="4e59f-892">此修正可解決已在用戶端中快取檔案時，Project 應用程式不應封鎖網路的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-892">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>


- <span data-ttu-id="4e59f-893">我們將後台中的頻道名稱更新為2020年1月 Fork 的新通道名稱，解決了此問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-893">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="4e59f-894">我們已修正此問題，如果裝置受政策管理，將不會調用 DMS 聽眾 API。</span><span class="sxs-lookup"><span data-stu-id="4e59f-894">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="4e59f-895">我們已解決在單一交易中新增和移除應用程式時，移除不完整的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-895">We have resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="4e59f-896">修正相對期限只有在第一次設定時才會有效的 ODT 和 GPO 更新期限設定中的錯誤 (bug)。此修正可啟用後續更新的相關期限。</span><span class="sxs-lookup"><span data-stu-id="4e59f-896">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="4e59f-897">解決 Office 更新可能會非預期地從 Office CDN 而不是預期使用的來源 (例如本機或網路共用或 Configuration Manager 提供的位置) 下載檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-897">Resolves an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="4e59f-898">修正相對期限只有在第一次設定時才會有效的 ODT 和 GPO 更新期限設定中的錯誤 (bug)。此修正可啟用後續更新的相關期限。</span><span class="sxs-lookup"><span data-stu-id="4e59f-898">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="4e59f-899">我們將新的 AppV51 放置向後移植，以修正先前 AppV51 中的迴歸。</span><span class="sxs-lookup"><span data-stu-id="4e59f-899">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="4e59f-900">我們已解決內部作業在失敗時擲出例外狀況，而不是記錄和繼續進行的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-900">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="4e59f-901">受影響的使用者將不會再無法收到更新。</span><span class="sxs-lookup"><span data-stu-id="4e59f-901">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="4e59f-902">我們的團隊已在半年企業預覽的 Office CDN 網域中新增報告遙測的用戶端支援。</span><span class="sxs-lookup"><span data-stu-id="4e59f-902">Our team has added client support for reporting telemetry on the Office CDN domains in Semi-Annual Enterprise Preview.</span></span>

- <span data-ttu-id="4e59f-903">此變更可解決利用 Intel Integrated GPU 的圖形配接卡所報告的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-903">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="4e59f-904">這項變更可確保草繪大綱可在功能區中正常運作。</span><span class="sxs-lookup"><span data-stu-id="4e59f-904">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="4e59f-905">已修正使用一些特定 proxy 設定時，從內部部署位置開啟檔案時發生的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-905">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="4e59f-906">此更新修正了 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。</span><span class="sxs-lookup"><span data-stu-id="4e59f-906">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="4e59f-907">修正問題，可在 Office 遞交工作階段期間消除當機，並改善使用者體驗中的可靠性。</span><span class="sxs-lookup"><span data-stu-id="4e59f-907">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>

- <span data-ttu-id="4e59f-908">這個錯誤會更新增強的設定服務 (ECS) url 端點。</span><span class="sxs-lookup"><span data-stu-id="4e59f-908">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="4e59f-909">呼叫這個較新的端點，可從 ECS 進行提取獲得更高的成功率。</span><span class="sxs-lookup"><span data-stu-id="4e59f-909">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

- <span data-ttu-id="4e59f-910">此更新可修正在檢視或撰寫郵件時，Microsoft Outlook 未顯示目前的敏感度標籤的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-910">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="4e59f-911">修正在 Word/Excel/PowerPoint 中開啟來自相同 SharePoint 文件庫的多個文件時，僅掃描開啟的第一個文件是否符合原則的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-911">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

- <span data-ttu-id="4e59f-912">為了保護 Office 客戶的安全性，我們現在專門使用 SHA-2 演算法來簽署 Microsoft Office 更新。</span><span class="sxs-lookup"><span data-stu-id="4e59f-912">To protect Office customers’ security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

- <span data-ttu-id="4e59f-913">當您啟用增益集，而登錄金鑰 HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth 被設為零時，辦公主機視窗會關閉。</span><span class="sxs-lookup"><span data-stu-id="4e59f-913">The office host was closing in windows, when an add-in is being activated while the registry key  HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="4e59f-914">此變更將修正此問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-914">This change would fix this issue.</span></span>

- <span data-ttu-id="4e59f-915">解決 Access 和 Publisher 因所安裝的語言而無法正常啟動的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-915">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)





[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-july-14"></a><span data-ttu-id="4e59f-918">版本 1908：7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="4e59f-918">Version 1908: July 14</span></span>
<span data-ttu-id="4e59f-919">*版本 1908 (組建 11929.20904)*</span><span class="sxs-lookup"><span data-stu-id="4e59f-919">*Version 1908 (Build 11929.20904)*</span></span>

<span data-ttu-id="4e59f-920">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4e59f-920">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="4e59f-922">解決的問題</span><span class="sxs-lookup"><span data-stu-id="4e59f-922">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="4e59f-923">Access</span><span class="sxs-lookup"><span data-stu-id="4e59f-923">Access</span></span>

- <span data-ttu-id="4e59f-924">此更新修正彙總 (例如 Sum) 可能會將結果截斷成整數值的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-924">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="4e59f-925">此更新修正包含參照遠端桌面 (例如 SQL Server 桌面) 的聯集查詢可能造成 Access 關閉並重新啟動的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-925">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="4e59f-926">此更新可修正 Microsoft Access 中的「更新查詢」執行時或在 SQL 中使用 UPDATE 陳述式時，可能導致錯誤「查詢已損壞」的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-926">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="4e59f-927">Excel</span><span class="sxs-lookup"><span data-stu-id="4e59f-927">Excel</span></span>

- <span data-ttu-id="4e59f-928">文件標題的荷蘭文按鍵提示已變更為 Alt-G。</span><span class="sxs-lookup"><span data-stu-id="4e59f-928">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="4e59f-929">修正在 Excel 中指派給圖形或表單控制項的巨集可能顯示不正確的錯誤訊息，或者可能會處理不正確目標範圍的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-929">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="4e59f-930">解決「尋找及取代」在找到第一個項目後，對話方塊中的焦點位置變更的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-930">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="4e59f-931">此更新修正在與其他使用者共同撰寫的工作階段中變更樞紐分析表排序的方式，然後重新整理可能觸發當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-931">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="4e59f-932">我們已修正當 OLAP 樞紐分析表的篩選條件設定為已從 cube 移除的值時會發生的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-932">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="4e59f-933">此更新已修正使用 VBA 將影像新增到圖表的頁首/頁尾時發生錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-933">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="4e59f-934">我們已修正當變更系列集合時，可能會導致散佈折線圖無法正確呈現的問題</span><span class="sxs-lookup"><span data-stu-id="4e59f-934">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection</span></span>

- <span data-ttu-id="4e59f-935">修正以校正使用圖表範本插入圖表時，預覽中使用的色彩。</span><span class="sxs-lookup"><span data-stu-id="4e59f-935">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="4e59f-936">已解決當插入或刪除儲存格時，瀑布圖和漏斗圖無法與表格同步處理的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-936">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="4e59f-937">修正 Excel 中合併衝突的問題，此問題會造成提示使用者重新開啟活頁簿以取得變更。</span><span class="sxs-lookup"><span data-stu-id="4e59f-937">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="4e59f-938">已解決造成執行階段錯誤啟動最小化視窗的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-938">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="4e59f-939">解決了開啟內嵌活頁簿時，功能區自訂無法載入的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-939">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="4e59f-940">已解決導致表格旁的剪下並貼上作業在與其他人共同撰寫時失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-940">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="4e59f-941">解決使用執行中巨集變更自訂屬性時，會導致共同撰寫中斷的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-941">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="4e59f-942">發生您無法從增益集開啟的 WPF (Windows Presentation Foundation) 表單的下拉式方塊選取項目的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-942">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="4e59f-943">解決在未開啟活頁簿時，搜尋最近使用的檔案會造成當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-943">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="4e59f-944">修正在預覽列印或列印時，群組方塊控制項的框線無法顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-944">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="4e59f-945">修正當活頁簿中有外部連結時，有些使用者可能會遇到多個快顯視窗的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-945">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="4e59f-946">已修正使用者在使用 VBA 巨集清除範圍內容時可能遇到的效能問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-946">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="4e59f-947">已修正 VBA 將值寫入範圍時，速度比預期慢的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-947">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="4e59f-948">解決在儲存並重新開啟檔案時，圖表軸上的「值置於」屬性非預期變更的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-948">Addresses an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="4e59f-949">在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。</span><span class="sxs-lookup"><span data-stu-id="4e59f-949">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="4e59f-950">已修正在刪除包含合併儲存格的資料行時，會導致效能變慢的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-950">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="4e59f-951">修正了在 [預覽列印] 中顯示表單控制項時的文字縮放比例問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-951">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="4e59f-952">將依色彩篩選的資料複製到具有不同寬度的欄時，值無法貼上。</span><span class="sxs-lookup"><span data-stu-id="4e59f-952">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

- <span data-ttu-id="4e59f-953">已修正當 Excel 視窗透過 Teams 共用時，使用 Ctrl + Shift + 方向鍵滑動後，Excel 可能會無法回應的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-953">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="4e59f-954">已修正列印時表單控制項的核取方塊縮放的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-954">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="4e59f-955">修正在相同活頁簿中按一下加入書籤的超連結會導致活頁簿隱藏的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-955">Fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="4e59f-956">當您使用舊版的「共用活頁簿」模式，嘗試為活頁簿的新工作表列出變更時，就會發生當機。</span><span class="sxs-lookup"><span data-stu-id="4e59f-956">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="4e59f-957">[資料剖析] 功能對某些地區設定可能會失敗。</span><span class="sxs-lookup"><span data-stu-id="4e59f-957">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="4e59f-958">使用者在存取隱藏的命名範圍時可能會遇到錯誤。</span><span class="sxs-lookup"><span data-stu-id="4e59f-958">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="4e59f-959">使用者在使用某些非英文字元集的情況下，儲存變更時可能會遇到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-959">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="4e59f-960">已修正圖表標題中影像檔案大小在儲存包含圖表的活頁簿時增加的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-960">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>

- <span data-ttu-id="4e59f-961">非同步使用者定義函數造成的效能問題，導致它們同步執行。</span><span class="sxs-lookup"><span data-stu-id="4e59f-961">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="4e59f-962">已大幅改善刪除有合併儲存格之欄的效能。</span><span class="sxs-lookup"><span data-stu-id="4e59f-962">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="4e59f-963">解決捲動後選取儲存格時，可能導致選取錯誤儲存格的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-963">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="4e59f-964">已解決 Lookup 函數可能會傳回錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-964">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="4e59f-965">已修正以下問題：將選取範圍與交互參照的活頁簿保持同步時，導致交互參照的活頁簿中的 DBCS 字元損毀。</span><span class="sxs-lookup"><span data-stu-id="4e59f-965">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="4e59f-966">已解決使用自動調整來調整列高時，核取方塊可能收縮的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-966">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>

- <span data-ttu-id="4e59f-967">當檔案具備大量設定格式化的條件時，按一下 [字型色彩] 按鈕時出現的效能緩慢問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-967">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="4e59f-968">我們已修正預覽列印中的列印範圍不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-968">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="4e59f-969">從不受信任的網路共用編輯受保護的檔案時，Excel 可能會發生問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-969">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="4e59f-970">我們已大幅提升依色彩篩選的效能。</span><span class="sxs-lookup"><span data-stu-id="4e59f-970">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="4e59f-971">解決在目前的 Office 版本中開啟在舊版 Office 中建立的活頁簿時，可能導致 Excel 懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-971">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="4e59f-972">在增益集管理員中瀏覽時，可顯示 16 個以上的增益集。</span><span class="sxs-lookup"><span data-stu-id="4e59f-972">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="4e59f-973">解決會防止將超連結貼到一些受保護工作表中的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-973">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="4e59f-974">這項變更透過利用軟體轉譯避免特定 Intel 圖形驅動程式發生問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-974">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="4e59f-975">來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。</span><span class="sxs-lookup"><span data-stu-id="4e59f-975">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="4e59f-976">此更新修正 Office 文件無法上傳到商務用 OneDrive 的錯誤 (訊息「上傳失敗」)。</span><span class="sxs-lookup"><span data-stu-id="4e59f-976">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="4e59f-977">已修正在 Excel 構想功能中，在 Win32 用戶端中按一下 [構想] 按鈕來載入增益集時會發生錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-977">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span> 

### <a name="onenote"></a><span data-ttu-id="4e59f-978">OneNote</span><span class="sxs-lookup"><span data-stu-id="4e59f-978">OneNote</span></span>

- <span data-ttu-id="4e59f-979">對通知進行本地化，讓使用者可以了解更多 OneNote 使用者體驗中正在採取的臨時措施的資訊，以改善同步處理和服務穩定性。</span><span class="sxs-lookup"><span data-stu-id="4e59f-979">Localizes the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="4e59f-980">Outlook</span><span class="sxs-lookup"><span data-stu-id="4e59f-980">Outlook</span></span>

- <span data-ttu-id="4e59f-981">來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。</span><span class="sxs-lookup"><span data-stu-id="4e59f-981">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="4e59f-982">修正使用者將信箱從基本驗證升級為新式驗證後，造成將錯誤的帳戶與其 Outlook 設定檔相關聯的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-982">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="4e59f-983">解決會導致網頁增益集在不該存取數位版權管理訊息時進行存取的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-983">Addresses an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="4e59f-984">解決會導致部分安全連結無法顯示簡單動態顯示 URL 的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-984">Addresses an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="4e59f-985">此這會更新 Outlook 中的附件封鎖邏輯，以同時封鎖 Python 附件。</span><span class="sxs-lookup"><span data-stu-id="4e59f-985">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="4e59f-986">解決導致部分 POP3 使用者查看所有純文字格式電子郵件 (無論設定) 的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-986">Addresses an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="4e59f-987">此修正將會還原 HTML 格式郵件的檢視。</span><span class="sxs-lookup"><span data-stu-id="4e59f-987">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="4e59f-988">解決在使用者將項目從其主要行事曆複製到群組行事曆時，會導致使用者遇到權限錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-988">Addresses an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="4e59f-989">解決會導致使用者無法透過螢幕助讀程式存取位置建議的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-989">Addresses an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="4e59f-990">解決當使用者透過鍵盤快速鍵與信箱資料夾互動時，會導致明顯延遲的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-990">Addresses an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="4e59f-991">解決會導致非常長時間的 Outlook 工作階段記憶體流失的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-991">Addresses an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="4e59f-992">解決會導致使用者在指定無效寄件者地址時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-992">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="4e59f-993">解決會導致使用者在開啟 [規則] 對話方塊時看到「此電腦上的規則與 Microsoft Exchange 上的規則不相符」提示的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-993">Addresses an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="4e59f-994">解決會導致使用者在與特定安全連結互動時在 Outlook 中遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-994">Addresses an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="4e59f-995">解決會導致經理對於代理人是否已經回覆特定會議邀請含混不清的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-995">Addresses an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="4e59f-996">解決會導致使用者在處理某些自動探索回應時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-996">Addresses an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="4e59f-997">解決會導致使用者在嘗試從 [帳戶建立] 內容連絡支援服務時，看到具有 [確定] 按鈕的空白訊息方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-997">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="4e59f-998">此變更可讓系統管理員啟用一個原則，以在自動探索驗證提示中較 UPN 優先使用所提供的帳戶電子郵件。</span><span class="sxs-lookup"><span data-stu-id="4e59f-998">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="4e59f-999">依預設，自動探索會優先於帳戶 UPN (如果有的話)。</span><span class="sxs-lookup"><span data-stu-id="4e59f-999">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="4e59f-1000">解決會導致使用者看到針對新式群組的搜尋失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1000">Addresses an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="4e59f-1001">解決會導致 Outlook 使用者在特定案例中停滯在「需要密碼」狀態的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1001">Addresses an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="4e59f-1002">解決會導致使用者處理衝突郵件時遇到同步失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1002">Addresses an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="4e59f-1003">解決會導致在套用最新的 Windows 更新之後，使用者開啟 .msg 和 .oft 檔案時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1003">Addresses an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="4e59f-1004">解決會導致使用者在啟動 Outlook 時，在「正在載入設定檔」畫面遇到停滯的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1004">Addresses an issue that caused users to experience a hang at the "Loading Profile" screen when Outlook is starting up.</span></span>

- <span data-ttu-id="4e59f-1005">解決會導致使用者在選取特定搜尋結果時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1005">Addresses an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="4e59f-1006">解決會讓 [附件工具] 中的 [儲存至雲端] 按鈕不見的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1006">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="4e59f-1007">根據預設，保留原則標籤會將保留時間顯示於括弧中。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1007">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="4e59f-1008">此修正提供登錄機碼，讓系統管理員能夠指定只應顯示的原則名稱。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1008">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="4e59f-1009">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = 預設值 1 = 我們只會顯示保留原則文字的 PolicyName。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1009">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = Default 1 = we will only show the PolicyName for Retention policy text.</span></span>

- <span data-ttu-id="4e59f-1010">解決會導致使用者在關閉 Outlook 時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1010">Addresses an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="4e59f-1011">解決會導致客戶在某些情況下看到空白會議室清單的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1011">Addresses an issue that caused customers to see an empty room list in some scenarios.</span></span>

- <span data-ttu-id="4e59f-1012">解決會導致使用者在變更檢視時看到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1012">Addresses an issue that caused users to see intermittent crashes when changing views.</span></span>

- <span data-ttu-id="4e59f-1013">已解決以下問題：使用者將共用行事曆資料夾同步到 OST 時發生問題，這導致嘗試與這些資料夾互動時發生權限錯誤。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1013">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>

- <span data-ttu-id="4e59f-1014">解決會導致使用者在 Citrix 環境中檢視 30 個以上的行事曆時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1014">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="4e59f-1015">此處是[記錄舊版問題的個別 KB](https://support.microsoft.com/zh-TW/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)</span><span class="sxs-lookup"><span data-stu-id="4e59f-1015">Here's the individual [KB where this was documented for previous versions](https://support.microsoft.com/zh-TW/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)</span></span>

- <span data-ttu-id="4e59f-1016">修正 SMIME 演算法選取的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1016">Corrects an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="4e59f-1017">解決會導致使用其他寄件者時，無法顯示原則提示的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1017">Addresses an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="4e59f-1018">解決會導致使用者看到在該會議室的可用時間以外進行之會議的會議室建議的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1018">Addresses an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="4e59f-1019">解決非英文使用者的郵件中，主旨列會相當小的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1019">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="4e59f-1020">解決會導致使用者嘗試從「未接的交談」訊息建立規則時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1020">Addresses an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="4e59f-1021">解決會導致某些使用者在新增次要 Exchange 帳戶時看到建立了重複的特殊資料夾的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1021">Addresses an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="4e59f-1022">解決在轉寄大型 HTML 郵件時，會導致使用者看到郵件內文截斷的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1022">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="4e59f-1023">解決會導致使用者在 Outlook 處理程序中看到記憶體流失的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1023">Addresses an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="4e59f-1024">解決會導致使用者在更新目前狀態資訊時遇到間歇性當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1024">Addresses an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="4e59f-1025">解決會導致目前的資料夾搜尋間歇性失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1025">Addresses an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="4e59f-1026">解決嘗試擷取使用者的 Outlook 雲端設定時，會導致一些使用者遇到驗證錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1026">Addresses an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="4e59f-1027">解決會導致在搜尋意見反應體驗中懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1027">Addresses an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="4e59f-1028">解決會導致使用者在處理某些自動探索回應時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1028">Addresses an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="4e59f-1029">解決會導致使用者在更新目前狀態資訊時遇到間歇性當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1029">Addresses an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="4e59f-1030">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4e59f-1030">PowerPoint</span></span>

- <span data-ttu-id="4e59f-1031">來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1031">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="4e59f-1032">此變更還原 PowerPoint 影片控制項的協助工具名稱的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1032">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="4e59f-1033">我們已修正部分動畫無法開始的問題</span><span class="sxs-lookup"><span data-stu-id="4e59f-1033">We fixed an issue which could prevent some animations from starting</span></span>

- <span data-ttu-id="4e59f-1034">我們已修正將投影片從一個簡報複製到另一個簡報時可能會造成建立重複母片的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1034">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span><br>

- <span data-ttu-id="4e59f-1035">改善複製貼上的案例：將 PowerPoint 投影片中的圖形複製並重複貼到其他投影片中，可能會出現例外狀況而失敗。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1035">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>

- <span data-ttu-id="4e59f-1036">修正螢光筆的問題：具有深色螢光筆色彩的白色文字，在灰階中會以黑色列印。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1036">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

- <span data-ttu-id="4e59f-1037">如果在不支援的版本中開啟含有新的新式註解的檔案，將會顯示黃色警告。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1037">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

- <span data-ttu-id="4e59f-1038">修正會導致共同作業使用者之間效能較低的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1038">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="4e59f-1039">可靠性修正：修正第三方增益集可能會造成 PowerPoint 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1039">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="4e59f-1040">修正以漸進式開啟檔案時，其包含的投影片若具有多個內嵌媒體串流，可能會發生的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1040">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="4e59f-1041">我們已修正 Shape.Paste 方法的問題：當使用者使用 Shape.Paste 方法複製並貼上圖形時，它會將選取範圍變更為貼上的圖形。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1041">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="4e59f-1042">我們已修正首次啟動 PowerPoint 時，未受信任的增益集可能不會顯示安全性警告訊息列的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1042">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

- <span data-ttu-id="4e59f-1043">修正某些增益集會對圖表的圖形擲出未預期錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1043">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="4e59f-1044">避免 PowerPoint 使用者嘗試進行「線上展示」時遇到錯誤。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1044">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

### <a name="project"></a><span data-ttu-id="4e59f-1045">Project</span><span class="sxs-lookup"><span data-stu-id="4e59f-1045">Project</span></span>

- <span data-ttu-id="4e59f-1046">修正讓 Windows 7 上的使用者能夠從 Project Web App 和 SharePoint 網站開啟專案的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1046">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="4e59f-1047">發現在開啟唯讀專案時，使用者可能會收到數個訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1047">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="4e59f-1048">「全部撫平」命令無法正確解決資源過度分派的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1048">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="4e59f-1049">當您有作業中有零個工作的指派時，可能無法將作業標示為完成且永遠會顯示為 99%。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1049">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

- <span data-ttu-id="4e59f-1050">已修正以下問題：由於基準行事曆變更時未更新資源行事曆，而導致時程表和專案計劃之間的實際工作可能不同。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1050">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="skype"></a><span data-ttu-id="4e59f-1051">Skype</span><span class="sxs-lookup"><span data-stu-id="4e59f-1051">Skype</span></span>

- <span data-ttu-id="4e59f-1052">已修正有多個交談正在進行時的索引標籤式交談標題名稱。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1052">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="visio"></a><span data-ttu-id="4e59f-1053">Visio</span><span class="sxs-lookup"><span data-stu-id="4e59f-1053">Visio</span></span>

- <span data-ttu-id="4e59f-1054">無法從 Visio 將多個圖形匯出為 SVG。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1054">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="4e59f-1055">Word</span><span class="sxs-lookup"><span data-stu-id="4e59f-1055">Word</span></span>

- <span data-ttu-id="4e59f-1056">來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1056">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="4e59f-1057">我們已修正列印到 Deskjet 印表機時，可能會導致縮放問題的問題</span><span class="sxs-lookup"><span data-stu-id="4e59f-1057">We fixed an issue which could have caused scaling issues when printing to Deskjet printers</span></span>

- <span data-ttu-id="4e59f-1058">我們已修正表格中「最適文字大小」的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1058">We fixed an issue in Fit Text in Table.</span></span>

- <span data-ttu-id="4e59f-1059">我們已修正追蹤修訂有時候會進入無限迴圈的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1059">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="4e59f-1060">我們已修正在某些情況下，儲存現有檔案永遠會導致出現 [另存新檔] 對話方塊且檔案永遠不會儲存的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1060">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="4e59f-1061">我們已修正將兩份文件合併成一份文件時的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1061">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="4e59f-1062">修正受保護無法編輯之文件的比較功能問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1062">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="4e59f-1063">修正應用程式可能在關機時懸置的各種問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1063">Fixes various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="4e59f-1064">同時修正特定相關增益集當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1064">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="4e59f-1065">Office 套件</span><span class="sxs-lookup"><span data-stu-id="4e59f-1065">Office Suite</span></span>

- <span data-ttu-id="4e59f-1066">已修正不正確地將平假名和漢字中的日本新年號 "Reiwa" (令和) 識別為拼字錯誤或不合文法的運算式的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1066">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="4e59f-1067">已修正嘗試共用儲存在 SharePoint 2016 上的檔案時，導致使用者遇到「很抱歉，發生問題，無法共用」訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1067">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="4e59f-1068">已修正在 PowerPoint 共同撰寫和離線編輯的工作階段中可能會導致資料遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1068">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="4e59f-1069">修正使用者在開啟檔案時可能會遇到的當機問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1069">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="4e59f-1070">在某些情況下，同步處理引擎備份的 SharePoint 檔案可能會顯示「已儲存」但實際上未儲存任何變更，導致資料遺失。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1070">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="4e59f-1071">解決使用者可能無法儲存 Word、Excel 和 PowerPoint 文件的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1071">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="4e59f-1072">此問題會影響建立新檔案並在按一下 [儲存] 圖示或按 Ctrl + S 之後帶出 [另存成模型對話方塊] 選項的使用者。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1072">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="4e59f-1073">從已過時的 API 中移除 Word，以修正其當機問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1073">Fixes a crash in Word by moving away from a deprecated API.</span></span>

- <span data-ttu-id="4e59f-1074">修正 PowerPoint 中半形片假名字元在垂直文字方塊中無法正確旋轉的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1074">Fixing an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

- <span data-ttu-id="4e59f-1075">已修正 Win7 的效能問題，其中，於所有應用程式中從功能區插入圖案庫時，大約需要 4 秒鐘的時間才會顯示。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1075">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="4e59f-1076">已修正 Backstage 的 [資訊位置] 平板未顯示協助工具資訊的錯誤。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1076">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="4e59f-1077">改善有關登錄完整性的 Office 更新程序的可靠性。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1077">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="4e59f-1078">我們已將 2019 年 1 月和 7 月分支的通道名稱更新為新通道名稱。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1078">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>

- <span data-ttu-id="4e59f-1079">更正可能會在計量網路上非預期封鎖更新的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1079">Corrects an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="4e59f-1080">修正相對期限只有在第一次設定時才會有效的 ODT 和 GPO 更新期限設定中的錯誤 (bug)。此修正可啟用後續更新的相關期限。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1080">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="4e59f-1081">某些情況下，Office 快速鍵可能會在更新後消失。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1081">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="4e59f-1082">此更新可改善發佈 Office 快速鍵時的可靠性。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1082">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="4e59f-1083">解決 Office 更新可能會非預期地從 Office CDN 而不是預期使用的來源 (例如本機或網路共用或 Configuration Manager 提供的位置) 下載檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1083">Resolves an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="4e59f-1084">解決在某些情況下，若使用者不是系統管理員且系統帳戶沒有網路連線時，將無法套用更新的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1084">Resolves an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="4e59f-1085">修正了 Office 更新訊息不以預期語言顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1085">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="4e59f-1086">自此以後，Office 更新訊息會正確符合 Windows 顯示語言。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1086">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="4e59f-1087">下載 Office 更新時透過繼續之前可能已中斷的下載，藉此改善可靠性。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1087">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="4e59f-1088">解決第三方外掛程式中與文字方塊/圖案自動調整屬性相關的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1088">Address issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="4e59f-1089">此變更可解決開啟損毀的檔案之後，正確呈現影像的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1089">This change addresses correctly rendering images after opening a corrupted file.</span></span>

- <span data-ttu-id="4e59f-1090">此變更可解決轉譯某些含有標記的散佈圖緩慢的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1090">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="4e59f-1091">我們已修正大型樹狀檢視可能會導致當機的問題</span><span class="sxs-lookup"><span data-stu-id="4e59f-1091">We fixed an issue where large tree views could result in a crash</span></span>

- <span data-ttu-id="4e59f-1092">此更新修正了 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1092">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="4e59f-1093">為了保護 Office 客戶的安全性，我們現在專門使用 SHA-2 演算法來簽署 Microsoft Office 更新。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1093">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

- <span data-ttu-id="4e59f-1094">為了保護 Office 客戶的安全性，我們現在專門使用 SHA-2 演算法來簽署 Microsoft Office 更新。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1094">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-july-14"></a><span data-ttu-id="4e59f-1096">版本 1902：7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="4e59f-1096">Version 1902: July 14</span></span>
<span data-ttu-id="4e59f-1097">*版本 1902 (組建 11328.20624)*</span><span class="sxs-lookup"><span data-stu-id="4e59f-1097">*Version 1902 (Build 11328.20624)*</span></span>

<span data-ttu-id="4e59f-1098">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4e59f-1098">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1908-june-09"></a><span data-ttu-id="4e59f-1099">版本 1908: 6 月 09日</span><span class="sxs-lookup"><span data-stu-id="4e59f-1099">Version 1908: June 09</span></span>
<span data-ttu-id="4e59f-1100">*版本1908（組建11929.20838）*</span><span class="sxs-lookup"><span data-stu-id="4e59f-1100">*Version 1908 (Build 11929.20838)*</span></span>

<span data-ttu-id="4e59f-1101">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4e59f-1101">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="4e59f-1103">解決的問題</span><span class="sxs-lookup"><span data-stu-id="4e59f-1103">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="4e59f-1104">Excel</span><span class="sxs-lookup"><span data-stu-id="4e59f-1104">Excel</span></span>

- <span data-ttu-id="4e59f-1105">已修正當 Excel 視窗透過 Teams 共用時，使用 Ctrl + Shift + 方向鍵滑動後，Excel 可能會無法回應的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1105">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="4e59f-1106">已修正列印時表單控制項的核取方塊縮放的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1106">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="4e59f-1107">當您使用舊版的「共用活頁簿」模式，嘗試為活頁簿的新工作表列出變更時，就會發生當機。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1107">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="4e59f-1108">Outlook</span><span class="sxs-lookup"><span data-stu-id="4e59f-1108">Outlook</span></span>

- <span data-ttu-id="4e59f-1109">已解決會導致使用者在轉寄大型 HTML 郵件時，看到郵件內文截斷的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1109">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

### <a name="office-suite"></a><span data-ttu-id="4e59f-1110">Office 套件</span><span class="sxs-lookup"><span data-stu-id="4e59f-1110">Office Suite</span></span>

- <span data-ttu-id="4e59f-1111">我們已將 2019 年 1月和7月叉的通道名稱更新為新的通道名稱。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1111">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-june-09"></a><span data-ttu-id="4e59f-1113">版本 1902: 6 月 09日</span><span class="sxs-lookup"><span data-stu-id="4e59f-1113">Version 1902: June 09</span></span>
<span data-ttu-id="4e59f-1114">*版本 1902 (組建 11328.20602)*</span><span class="sxs-lookup"><span data-stu-id="4e59f-1114">*Version 1902 (Build 11328.20602)*</span></span>

<span data-ttu-id="4e59f-1115">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4e59f-1115">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="4e59f-1117">解決的問題</span><span class="sxs-lookup"><span data-stu-id="4e59f-1117">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="4e59f-1118">Office 套件</span><span class="sxs-lookup"><span data-stu-id="4e59f-1118">Office Suite</span></span>

- <span data-ttu-id="4e59f-1119">我們已將 2019 年 1月和7月叉的通道名稱更新為新的通道名稱。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1119">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>

- <span data-ttu-id="4e59f-1120">我們從中斷 C2R 組建的基線檔案中移除過時的參照。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1120">We removed obsolete references from the baseline files that were breaking the C2R Build.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-may-12"></a><span data-ttu-id="4e59f-1122">版本 1908：5 月 12 日</span><span class="sxs-lookup"><span data-stu-id="4e59f-1122">Version 1908: May 12</span></span>
<span data-ttu-id="4e59f-1123">*版本 1908 (組建 11929.20776)*</span><span class="sxs-lookup"><span data-stu-id="4e59f-1123">*Version 1908 (Build 11929.20776)*</span></span>

<span data-ttu-id="4e59f-1124">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4e59f-1124">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="4e59f-1126">解決的問題</span><span class="sxs-lookup"><span data-stu-id="4e59f-1126">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="4e59f-1127">Excel</span><span class="sxs-lookup"><span data-stu-id="4e59f-1127">Excel</span></span>

- <span data-ttu-id="4e59f-1128">當您將有色彩篩選的資料複製到不同寬度的欄時，不會貼上值。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1128">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

### <a name="outlook"></a><span data-ttu-id="4e59f-1129">Outlook</span><span class="sxs-lookup"><span data-stu-id="4e59f-1129">Outlook</span></span>

- <span data-ttu-id="4e59f-1130">解決以下問題：使用者在套用最新的 Windows 更新之後，開啟 .msg 和 .oft 檔案發生當機。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1130">Addressed an issue that caused users to experience a crash when opening msg and .oft files after applying a recent Windows update.</span></span>

### <a name="word"></a><span data-ttu-id="4e59f-1131">Word</span><span class="sxs-lookup"><span data-stu-id="4e59f-1131">Word</span></span>

- <span data-ttu-id="4e59f-1132">我們已修正將兩份文件合併成一份文件時的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1132">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="4e59f-1133">修正受保護無法編輯之文件的比較功能問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1133">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-may-12"></a><span data-ttu-id="4e59f-1135">版本 1902：5 月 12 日</span><span class="sxs-lookup"><span data-stu-id="4e59f-1135">Version 1902: May 12</span></span>
<span data-ttu-id="4e59f-1136">*版本 1902 (組建 11328.20586)*</span><span class="sxs-lookup"><span data-stu-id="4e59f-1136">*Version 1902 (Build 11328.20586)*</span></span>

<span data-ttu-id="4e59f-1137">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4e59f-1137">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="4e59f-1139">解決的問題</span><span class="sxs-lookup"><span data-stu-id="4e59f-1139">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="4e59f-1140">Outlook</span><span class="sxs-lookup"><span data-stu-id="4e59f-1140">Outlook</span></span>

- <span data-ttu-id="4e59f-1141">解決以下問題：使用者在套用最新的 Windows 更新之後，開啟 .msg 和 .oft 檔案發生當機。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1141">Addressed an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="4e59f-1142">根據預設，保留原則標籤會將保留時間顯示於括弧中。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1142">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="4e59f-1143">此修正提供登錄機碼，讓系統管理員能夠指定只應顯示的原則名稱。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1143">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="4e59f-1144">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1144">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="4e59f-1145">0 = 預設值。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1145">0 = Default.</span></span>  <span data-ttu-id="4e59f-1146">1 = 我們只會顯示保留原則文字的原則名稱。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1146">1 = we will only show the PolicyName for Retention policy text.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-may-04"></a><span data-ttu-id="4e59f-1148">版本 1908：5 月 4 日</span><span class="sxs-lookup"><span data-stu-id="4e59f-1148">Version 1908: May 04</span></span>
<span data-ttu-id="4e59f-1149">*版本 1908 (組建 11929.20752)*</span><span class="sxs-lookup"><span data-stu-id="4e59f-1149">*Version 1908 (Build 11929.20752)*</span></span>

<span data-ttu-id="4e59f-1150">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4e59f-1150">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="4e59f-1151">解決的問題</span><span class="sxs-lookup"><span data-stu-id="4e59f-1151">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="4e59f-1152">Outlook</span><span class="sxs-lookup"><span data-stu-id="4e59f-1152">Outlook</span></span>

- <span data-ttu-id="4e59f-1153">已解決導致使用者在選取特定搜尋結果時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1153">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="4e59f-1154">已解決導致 [附件工具] 中的 [儲存至雲端] 按鈕遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1154">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="4e59f-1155">根據預設，保留原則標籤會將保留時間顯示於括弧中。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1155">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="4e59f-1156">此修正提供登錄機碼，讓系統管理員能夠指定只應顯示的原則名稱。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1156">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="4e59f-1157">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1157">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="4e59f-1158">0 = 預設 1 = 我們只會顯示保留原則文字的原則名稱。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1158">0 = Default 1 = we will only show the PolicyName for Retention policy text.</span></span>

### <a name="office-suite"></a><span data-ttu-id="4e59f-1159">Office 套件</span><span class="sxs-lookup"><span data-stu-id="4e59f-1159">Office Suite</span></span>

- <span data-ttu-id="4e59f-1160">已修正 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1160">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1902-may-04"></a><span data-ttu-id="4e59f-1161">版本 1902：5 月 4 日</span><span class="sxs-lookup"><span data-stu-id="4e59f-1161">Version 1902: May 04</span></span>
<span data-ttu-id="4e59f-1162">*版本 1902 (組建 11328.20572)*</span><span class="sxs-lookup"><span data-stu-id="4e59f-1162">*Version 1902 (Build 11328.20572)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="4e59f-1163">解決的問題</span><span class="sxs-lookup"><span data-stu-id="4e59f-1163">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="4e59f-1164">Office 套件</span><span class="sxs-lookup"><span data-stu-id="4e59f-1164">Office Suite</span></span>

- <span data-ttu-id="4e59f-1165">已修正 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1165">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1908-april-26"></a><span data-ttu-id="4e59f-1166">版本 1908：4 月 26 日</span><span class="sxs-lookup"><span data-stu-id="4e59f-1166">Version 1908: April 26</span></span>
<span data-ttu-id="4e59f-1167">*版本 1908 (組建 11929.20736)*</span><span class="sxs-lookup"><span data-stu-id="4e59f-1167">*Version 1908 (Build 11929.20736)*</span></span>

<span data-ttu-id="4e59f-1168">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4e59f-1168">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="4e59f-1169">解決的問題</span><span class="sxs-lookup"><span data-stu-id="4e59f-1169">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="4e59f-1170">Excel</span><span class="sxs-lookup"><span data-stu-id="4e59f-1170">Excel</span></span>

- <span data-ttu-id="4e59f-1171">已修正使用者在使用 VBA 巨集清除範圍內容時可能遇到的效能問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1171">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="4e59f-1172">已修正 VBA 將值寫入範圍時，速度比預期慢的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1172">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="4e59f-1173">已解決在儲存並重新開啟檔案時，圖表軸上的 "Value Crosses At" 屬性發生意外變更的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1173">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="4e59f-1174">在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1174">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>


### <a name="onenote"></a><span data-ttu-id="4e59f-1175">OneNote</span><span class="sxs-lookup"><span data-stu-id="4e59f-1175">OneNote</span></span>

- <span data-ttu-id="4e59f-1176">對通知進行本地化，讓使用者可以了解更多 OneNote 使用者體驗中正在採取的臨時措施的資訊，以改善同步處理和服務穩定性。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1176">Localizes the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>


## <a name="version-1908-april-14"></a><span data-ttu-id="4e59f-1177">版本 1908：4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="4e59f-1177">Version 1908: April 14</span></span>
<span data-ttu-id="4e59f-1178">*版本 1908 (組建 11929.20708)*</span><span class="sxs-lookup"><span data-stu-id="4e59f-1178">*Version 1908 (Build 11929.20708)*</span></span>

<span data-ttu-id="4e59f-1179">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4e59f-1179">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="4e59f-1181">解決的問題</span><span class="sxs-lookup"><span data-stu-id="4e59f-1181">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="4e59f-1182">Excel</span><span class="sxs-lookup"><span data-stu-id="4e59f-1182">Excel</span></span>

- <span data-ttu-id="4e59f-1183">已修正在刪除包含合併儲存格的資料行時，會導致效能變慢的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1183">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="4e59f-1184">修正了在 [預覽列印] 中顯示表單控制項時的文字縮放比例問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1184">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

### <a name="skype"></a><span data-ttu-id="4e59f-1185">Skype</span><span class="sxs-lookup"><span data-stu-id="4e59f-1185">Skype</span></span>

- <span data-ttu-id="4e59f-1186">已修正有多個交談正在進行時的索引標籤式交談標題名稱。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1186">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="outlook"></a><span data-ttu-id="4e59f-1187">Outlook</span><span class="sxs-lookup"><span data-stu-id="4e59f-1187">Outlook</span></span>

- <span data-ttu-id="4e59f-1188">已解決會導致使用者在關閉 Outlook 時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1188">Addressed an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="4e59f-1189">已解決會導致客戶在某些情況下看到空白會議室清單的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1189">Addressed an issue that caused customers to see an empty room list in some scenarios.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="4e59f-1190">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4e59f-1190">PowerPoint</span></span>

- <span data-ttu-id="4e59f-1191">修正具有深色螢光筆色彩的白色文字，在灰階中會以黑色列印的螢光筆問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1191">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="4e59f-1192">Word</span><span class="sxs-lookup"><span data-stu-id="4e59f-1192">Word</span></span>

- <span data-ttu-id="4e59f-1193">已修正「文字配合資料表」中的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1193">Fixed an issue in Fit Text in Table.</span></span>


## <a name="version-1902-april-14"></a><span data-ttu-id="4e59f-1194">版本 1902：4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="4e59f-1194">Version 1902: April 14</span></span>
<span data-ttu-id="4e59f-1195">*版本 1902 (組建 11328.20564)*</span><span class="sxs-lookup"><span data-stu-id="4e59f-1195">*Version 1902 (Build 11328.20564)*</span></span>

<span data-ttu-id="4e59f-1196">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4e59f-1196">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-march-10"></a><span data-ttu-id="4e59f-1198">版本 1908：3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="4e59f-1198">Version 1908: March 10</span></span>
<span data-ttu-id="4e59f-1199">*版本 1908 (組建 11929.20648)*</span><span class="sxs-lookup"><span data-stu-id="4e59f-1199">*Version 1908 (Build 11929.20648)*</span></span>

<span data-ttu-id="4e59f-1200">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4e59f-1200">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="4e59f-1202">解決的問題</span><span class="sxs-lookup"><span data-stu-id="4e59f-1202">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="4e59f-1203">Excel</span><span class="sxs-lookup"><span data-stu-id="4e59f-1203">Excel</span></span>

- <span data-ttu-id="4e59f-1204">修正當活頁簿中有外部連結時，有些使用者可能會遇到多個彈出式視窗的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1204">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>


- <span data-ttu-id="4e59f-1205">[資料剖析] 功能對某些地區設定可能會失敗。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1205">Text to Column functionality may fail for some locales.</span></span>


- <span data-ttu-id="4e59f-1206">使用者在存取隱藏的命名範圍時可能會發生錯誤。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1206">Users may encounter an error when accessing a hidden named range.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="4e59f-1207">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4e59f-1207">PowerPoint</span></span>

- <span data-ttu-id="4e59f-1208">我們已修正 Shape.Paste 方法的問題：當使用者使用 Shape.Paste 方法複製並貼上圖形時，它會將選取範圍變更為貼上的圖形。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1208">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>


### <a name="word"></a><span data-ttu-id="4e59f-1209">Word</span><span class="sxs-lookup"><span data-stu-id="4e59f-1209">Word</span></span>

- <span data-ttu-id="4e59f-1210">我們已修正在某些情況下，儲存現有檔案永遠會導致出現 [另存新檔] 對話方塊且檔案永遠不會儲存的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1210">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>


### <a name="office-suite"></a><span data-ttu-id="4e59f-1211">Office 套件</span><span class="sxs-lookup"><span data-stu-id="4e59f-1211">Office Suite</span></span>

- <span data-ttu-id="4e59f-1212">此變更可解決轉譯某些含有資料標記的散佈圖緩慢的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1212">This change addresses slow rendering of some scatter charts with markers.</span></span>

## <a name="version-1902-march-10"></a><span data-ttu-id="4e59f-1213">版本 1902：3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="4e59f-1213">Version 1902: March 10</span></span>
<span data-ttu-id="4e59f-1214">*版本 1902 (組建 11328.20554)*</span><span class="sxs-lookup"><span data-stu-id="4e59f-1214">*Version 1902 (Build 11328.20554)*</span></span>

<span data-ttu-id="4e59f-1215">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4e59f-1215">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-february-11"></a><span data-ttu-id="4e59f-1217">版本 1908：2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="4e59f-1217">Version 1908: February 11</span></span>
<span data-ttu-id="4e59f-1218">*版本 1908 (組建 11929.20606)*</span><span class="sxs-lookup"><span data-stu-id="4e59f-1218">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="4e59f-1219">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4e59f-1219">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="4e59f-1221">解決的問題</span><span class="sxs-lookup"><span data-stu-id="4e59f-1221">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="4e59f-1222">Excel</span><span class="sxs-lookup"><span data-stu-id="4e59f-1222">Excel</span></span>

- <span data-ttu-id="4e59f-1223">此更新已修正使用 VBA 將影像新增到圖表的頁首/頁尾時發生錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1223">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="4e59f-1224">已修正在預覽列印或列印時群組方塊控制項的框線無法顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1224">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="4e59f-1225">使用者在使用某些非英文字元集的情況下，儲存變更時可能會遇到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1225">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="4e59f-1226">已修正圖表標題中影像檔案大小在儲存包含圖表的活頁簿時增加的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1226">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="4e59f-1227">已修正以下問題：將選取範圍與交互參照的活頁簿保持同步時，導致交互參照的活頁簿中的 DBCS 字元損毀。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1227">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="4e59f-1228">已解決使用自動調整來調整列高時，核取方塊可能收縮的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1228">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="4e59f-1229">Outlook</span><span class="sxs-lookup"><span data-stu-id="4e59f-1229">Outlook</span></span>

- <span data-ttu-id="4e59f-1230">已解決導致使用者在指定無效寄件者地址時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1230">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="4e59f-1231">已解決導致使用者處理衝突郵件時同步失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1231">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="4e59f-1232">已解決導致使用者在啟動 Outlook 時，「正在載入設定檔」畫面時停滯的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1232">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="4e59f-1233">已解決導致使用者在變更檢視時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1233">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="4e59f-1234">已解決在 Citrix 環境中檢視 30 個以上的行事曆時，導致使用者遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1234">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="4e59f-1235">[此處](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)是記錄舊版問題的個別 KB。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1235">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="4e59f-1236">已解決以下問題：使用者將共用行事曆資料夾同步到 OST 時發生問題，這導致嘗試與這些資料夾互動時發生權限錯誤。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1236">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="4e59f-1237">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4e59f-1237">PowerPoint</span></span>

- <span data-ttu-id="4e59f-1238">已改善複製貼上的案例，即將 PowerPoint 投影片中的圖形複製並貼到其他投影片可能會因為異常而失敗。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1238">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="4e59f-1239">已修正導致共同作業使用者之間效能較低的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1239">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="4e59f-1240">已修正以下問題：當檔案以漸進式開啟時，若其中一個投影片包含多個內嵌媒體串流可能會發生問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1240">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="4e59f-1241">已修正以下問題：首次啟動 PowerPoint 時，不受信任的增益集可能不會顯示安全性警告訊息列。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1241">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="4e59f-1242">Project</span><span class="sxs-lookup"><span data-stu-id="4e59f-1242">Project</span></span>

- <span data-ttu-id="4e59f-1243">已修正以下問題：由於基準行事曆變更時未更新資源行事曆，而導致時程表和專案計劃之間的實際工作可能不同。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1243">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="4e59f-1244">Word</span><span class="sxs-lookup"><span data-stu-id="4e59f-1244">Word</span></span>

- <span data-ttu-id="4e59f-1245">已從遭取代的 API 移除，以修正 Word 的當機問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1245">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="4e59f-1246">Office 套件</span><span class="sxs-lookup"><span data-stu-id="4e59f-1246">Office Suite</span></span>

- <span data-ttu-id="4e59f-1247">此變更解決開啟損毀的檔案時正確呈現影像的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1247">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-february-11"></a><span data-ttu-id="4e59f-1249">版本 1902：2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="4e59f-1249">Version 1902: February 11</span></span>
<span data-ttu-id="4e59f-1250">*版本 1902 (組建 11328.20526)*</span><span class="sxs-lookup"><span data-stu-id="4e59f-1250">*Version 1902 (Build 11328.20526)*</span></span>

<span data-ttu-id="4e59f-1251">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4e59f-1251">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="4e59f-1253">解決的問題</span><span class="sxs-lookup"><span data-stu-id="4e59f-1253">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="4e59f-1254">Outlook</span><span class="sxs-lookup"><span data-stu-id="4e59f-1254">Outlook</span></span>

- <span data-ttu-id="4e59f-1255">解決導致使用者在傳送加密電子郵件時遇到「不支援加密演算法」錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1255">Addresses an issue that caused users to encounter encryption algorithm is not supported errors when sending an encrypted email.</span></span>


### <a name="word"></a><span data-ttu-id="4e59f-1256">Word</span><span class="sxs-lookup"><span data-stu-id="4e59f-1256">Word</span></span>

- <span data-ttu-id="4e59f-1257">已從遭取代的 API 移除，以修正 Word 的當機問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1257">Fixed a crash in Word by moving away from a deprecated API.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

## <a name="version-1808-february-11"></a><span data-ttu-id="4e59f-1260">版本 1808：2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="4e59f-1260">Version 1808: February 11</span></span>
<span data-ttu-id="4e59f-1261">*版本 1808 (組建 10730.20438)*</span><span class="sxs-lookup"><span data-stu-id="4e59f-1261">*Version 1808 (Build 10730.20438)*</span></span>

<span data-ttu-id="4e59f-1262">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4e59f-1262">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-january-14"></a><span data-ttu-id="4e59f-1264">版本 1908：1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="4e59f-1264">Version 1908: January 14</span></span>
<span data-ttu-id="4e59f-1265">*版本 1908 (組建 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="4e59f-1265">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="4e59f-1266">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4e59f-1266">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="4e59f-1268">功能更新</span><span class="sxs-lookup"><span data-stu-id="4e59f-1268">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="4e59f-1269">Access</span><span class="sxs-lookup"><span data-stu-id="4e59f-1269">Access</span></span>

- <span data-ttu-id="4e59f-1270">**將索引標籤保留在資料庫物件上：** 能清楚看到使用中的索引標籤、輕鬆拖曳索引標籤來重新排列，只要按一下就能關閉資料庫物件。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1270">**Keep tabs on your database objects:** Clearly see the active tab, easily drag tabs to rearrange them, and close database objects with just one click.</span></span>

- <span data-ttu-id="4e59f-1271">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1271">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="4e59f-1272">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1272">Switching between them has never been easier.</span></span> [<span data-ttu-id="4e59f-1273">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-1273">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="4e59f-1274">**使用更大的空間來縮放：** 加大 [縮放] 方塊、變更字型、記憶縮放。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1274">**Zoom with more room:** Make the Zoom box bigger, change the font, and Zoom remembers it all.</span></span> [<span data-ttu-id="4e59f-1275">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-1275">Learn more</span></span>](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

### <a name="excel"></a><span data-ttu-id="4e59f-1276">Excel</span><span class="sxs-lookup"><span data-stu-id="4e59f-1276">Excel</span></span>

- <span data-ttu-id="4e59f-1277">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1277">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="4e59f-1278">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1278">Switching between them has never been easier.</span></span> [<span data-ttu-id="4e59f-1279">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-1279">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="4e59f-1280">**增加您內容的覆蓋面：** 想要讓您的簡報更易於使用嗎？</span><span class="sxs-lookup"><span data-stu-id="4e59f-1280">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="4e59f-1281">讓協助工具檢查程式來幫助您，您不需要自行處理。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1281">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="4e59f-1282">按一下 [校閱] > [檢查協助工具] 試試看這個功能 – 我們會在狀態列上告訴您需要留意的部分。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1282">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="4e59f-1283">**快速找到該檔案：** 想要尋找最近使用過的檔案嗎？</span><span class="sxs-lookup"><span data-stu-id="4e59f-1283">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="4e59f-1284">只要在 [檔案] > [常用] 頁面的 [搜尋] 方塊中輸入，就能找到所需的檔案。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1284">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="4e59f-1285">**觀看工作表生動地呈現：** 插入動畫 3D 圖形，來查看心跳、行星軌道，以及暴龍在工作表內橫衝直撞。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1285">**Watch your worksheet come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage through the workbook.</span></span> [<span data-ttu-id="4e59f-1286">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-1286">Learn more</span></span>](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- <span data-ttu-id="4e59f-p211">**更深入地探索您的資料：** 新的 [構想] 按鈕可尋找資料的模式，並使用模式建立更有智慧且個人化的建議。[深入了解](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span><span class="sxs-lookup"><span data-stu-id="4e59f-p211">**Discover more about your data:** The new Ideas button looks for patterns in your data, and uses them to create intelligent, personalized suggestions. [Learn more](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span></span>

- <span data-ttu-id="4e59f-1289">**共同作業變得更容易：** 共同撰寫的增強功能代表的是使用條件式格式設定、儲存格樣式等等時，您的變更會與共同作業者的變更順暢地合併。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1289">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>

- <span data-ttu-id="4e59f-1290">**聯結類似欄位上的表格：** 在比較合併表格的欄位時，取得及轉換 (Power Query) 現在具有近似文字比對邏輯 (也稱為模糊比對)。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1290">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span> [<span data-ttu-id="4e59f-1291">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-1291">Learn more</span></span>](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- <span data-ttu-id="4e59f-1292">**使用 Power Query 的增強功能快速撰寫程式碼：** 使用自動完成和語法色彩快速完成程式碼。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1292">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="4e59f-1293">同時輕鬆探索函數、資料行和參數。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1293">Easily discover functions, columns, and parameters, too.</span></span>

- <span data-ttu-id="4e59f-1294">**搜尋並享受：** 我們新增了 [搜尋以插入] 圖示，讓您輕鬆找到您要的圖示。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1294">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="4e59f-1295">而當您選取時，[插入] 按鈕會告知您已經選取的數量。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1295">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="4e59f-1296">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-1296">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook"></a><span data-ttu-id="4e59f-1297">Outlook</span><span class="sxs-lookup"><span data-stu-id="4e59f-1297">Outlook</span></span>

- <span data-ttu-id="4e59f-1298">**我們已為您更新 Outlook 使用者體驗：** 先前利用「即將推出」提供預覽的簡化體驗，專門設計來幫助您專注於最重要的事物上。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1298">**We’ve updated the Outlook user experience for you:** A simplified experience, previously available for preview with Coming Soon, designed to help you focus on what matters most.</span></span> [<span data-ttu-id="4e59f-1299">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-1299">Learn more</span></span>](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- <span data-ttu-id="4e59f-1300">**簡化且也能自訂的功能區：** 輕鬆使用簡化、以單一列方式陳列的常用按鈕。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1300">**A simplified ribbon that's customizable, too:** Enjoy a streamlined, single row of the most frequently used buttons.</span></span> <span data-ttu-id="4e59f-1301">輕鬆在傳統與 [簡化] 檢視之間切換，以及釘選/取消釘選命令。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1301">Easily switch between classic and Simplified views, and pin/unpin commands.</span></span> [<span data-ttu-id="4e59f-1302">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-1302">Learn more</span></span>](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- <span data-ttu-id="4e59f-1303">**在移動郵件時繼續作業：** Outlook 現在會在背景中移動郵件，因此，在資料夾之間移動大量郵件時您可以繼續作業。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1303">**Keep working while moving messages:** Outlook now moves messages in the background, so you can keep working while moving lots of messages between folders.</span></span>

- <span data-ttu-id="4e59f-1304">**在連續會議之間置入時間：** 將會議預設為提早 5-10 分鐘結束，讓出席者有時間休息，或在前往下一個地點。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1304">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to end 5-10 minutes early by default.</span></span>

- <span data-ttu-id="4e59f-1305">**挑選您的最愛動作：** 不使用 [標幟] 和 [刪除] 嗎？</span><span class="sxs-lookup"><span data-stu-id="4e59f-1305">**Pick your favorite action:** Don't use Flag and Delete?</span></span> <span data-ttu-id="4e59f-1306">那麼 [封存] 或 [標示為已讀取] 呢？</span><span class="sxs-lookup"><span data-stu-id="4e59f-1306">How about Archive or Mark as Read?</span></span> <span data-ttu-id="4e59f-1307">自訂快速動作功能表，加上您最常使用的命令。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1307">Customize the quick action menu with the commands you use most.</span></span>

- <span data-ttu-id="4e59f-p218">**他們會看到您的 meme：** 如果使用文字或靜態影像還不足以清楚表達您的想法，您可以使用動畫 GIF。[深入了解](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span><span class="sxs-lookup"><span data-stu-id="4e59f-p218">**They'll see what you meme:** When text or static images just won't do, use an animated GIF to make your point. [Learn more](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span></span>

- <span data-ttu-id="4e59f-1310">**更快速新增帳戶的方式：** 由於帳戶設定已改善，您現在可以更輕鬆地將使用雙因素驗證的 Outlook.com 和 Gmail 帳戶新增到 Outlook。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1310">**A quicker way to add accounts:** Thanks to account setup improvements, it's easier than ever to add Outlook.com and Gmail accounts that use 2-factor authentication to Outlook.</span></span> [<span data-ttu-id="4e59f-1311">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-1311">Learn more</span></span>](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- <span data-ttu-id="4e59f-1312">**不再受限於同步處理限制：** Outlook 的增強功能指出資料夾限制已不存在，因此您可以開始將您的共用信箱同步處理。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1312">**Say goodbye to sync limits:** Outlook improvements mean the folder limit is gone so go ahead and synchronize your shared mailboxes.</span></span>

- <span data-ttu-id="4e59f-1313">**搜尋並享受：** 我們新增了 [搜尋以插入] 圖示，讓您輕鬆找到您要的圖示。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1313">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="4e59f-1314">而當您選取時，[插入] 按鈕會告知您已經選取的數量。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1314">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="4e59f-1315">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-1315">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint"></a><span data-ttu-id="4e59f-1316">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4e59f-1316">PowerPoint</span></span>

- <span data-ttu-id="4e59f-1317">**較佳變形效果：** 命名您的圖形以便加強掌控其轉化方式。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1317">**Better shapeshifting:** Name your shapes for more control over how they morph.</span></span> [<span data-ttu-id="4e59f-1318">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-1318">Learn more</span></span>](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- <span data-ttu-id="4e59f-1319">**快速找到該檔案：** 想要尋找最近使用過的檔案嗎？</span><span class="sxs-lookup"><span data-stu-id="4e59f-1319">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="4e59f-1320">只要在 [檔案] > [常用] 頁面的 [搜尋] 方塊中輸入，就能找到所需的檔案。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1320">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="4e59f-1321">**增加您內容的覆蓋面：** 想要讓您的簡報更易於使用嗎？</span><span class="sxs-lookup"><span data-stu-id="4e59f-1321">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="4e59f-1322">讓協助工具檢查程式來幫助您，您不需要自行處理。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1322">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="4e59f-1323">按一下 [校閱] > [檢查協助工具] 試試看這個功能 – 我們會在狀態列上告訴您需要留意的部分。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1323">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="4e59f-1324">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1324">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="4e59f-1325">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1325">Switching between them has never been easier.</span></span> [<span data-ttu-id="4e59f-1326">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-1326">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="4e59f-1327">**線上影片有新的首頁：** 將影片儲存至 Microsoft Stream，讓組織中的任何人都看得到。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1327">**Online videos have a new home:** Save a video to Microsoft Stream so anyone in your organization can see it.</span></span> <span data-ttu-id="4e59f-1328">插入影片連結，享受檔案大小只有原來一小部分的多媒體簡報。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1328">Insert the video link and enjoy a multimedia presentation at a fraction of the file size.</span></span> [<span data-ttu-id="4e59f-1329">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-1329">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="4e59f-1330">**隨時儲存變更：** 將檔案上傳至 OneDrive，確保所有的更新都會自動儲存。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1330">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="4e59f-p226">**透過測驗或問卷詢問聽眾：** 在投影片上進行測驗或問卷。Office 會收集並儲存存儲您的回應。[深入了解](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span><span class="sxs-lookup"><span data-stu-id="4e59f-p226">**Ask your audience with a quiz or survey:** Put a quiz or survey on a slide. Office collects and stores the responses for you. [Learn more](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span></span>

- <span data-ttu-id="4e59f-p227">**輕鬆插入內嵌影片：** 想要在您的投影片中放入 Vimeo 或 YouTube 影片嗎？只要有影片頁面連結即可。[深入了解](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span><span class="sxs-lookup"><span data-stu-id="4e59f-p227">**Inserting an online video is easier than ever:** Want to put a video from Vimeo or YouTube on your slide? The video page link is all you need. [Learn more](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span></span>

- <span data-ttu-id="4e59f-1337">**搜尋並享受：** 我們新增了 [搜尋以插入] 圖示，讓您輕鬆找到您要的圖示。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1337">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="4e59f-1338">而當您選取時，[插入] 按鈕會告知您已經選取的數量。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1338">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="4e59f-1339">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-1339">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="project"></a><span data-ttu-id="4e59f-1340">Project</span><span class="sxs-lookup"><span data-stu-id="4e59f-1340">Project</span></span>

- <span data-ttu-id="4e59f-1341">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1341">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="4e59f-1342">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1342">Switching between them has never been easier.</span></span> [<span data-ttu-id="4e59f-1343">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-1343">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a><span data-ttu-id="4e59f-1344">Visio</span><span class="sxs-lookup"><span data-stu-id="4e59f-1344">Visio</span></span>

- <span data-ttu-id="4e59f-1345">**將進度圖表匯出到 Word：** 在 Word 文件中自動新增圖表內容，如圖案和中繼資料。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1345">**Export process diagrams to Word:** Automatically add diagram content, such as shapes and metadata, to a Word document.</span></span> <span data-ttu-id="4e59f-1346">然後，自訂文件來建立程序指導方針和操作手冊。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1346">Then customize the document to create process guidelines and operation manuals.</span></span> [<span data-ttu-id="4e59f-1347">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-1347">Learn more</span></span>](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- <span data-ttu-id="4e59f-1348">**資料流程圖上的 Double-Take：** 資料視覺化工具流程圖美觀的新版面配置，既清新、簡潔且更易於了解。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1348">**Double-take on data flowcharts:** Gorgeous new layouts for Data Visualizer flowcharts are clean, crisp, and easy to understand.</span></span> <span data-ttu-id="4e59f-1349">按一下 [設計] 索引標籤來取得選項。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1349">Click the Design tab for options.</span></span>

- <span data-ttu-id="4e59f-1350">**內建的 Azure 樣板：** 使用數十種 Azure 樣板來設計雲端應用程式或規劃架構。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1350">**Azure stencils built right in:** Design a cloud app or plan an architecture using dozens of Azure stencils.</span></span> [<span data-ttu-id="4e59f-1351">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-1351">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- <span data-ttu-id="4e59f-p233">**告別錯誤的 Excel 連結：** 找不到與 Data Visualizer 圖表連結的 Excel 活頁簿嗎？重新連結，就可繼續使用了。[深入了解](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span><span class="sxs-lookup"><span data-stu-id="4e59f-p233">**Say goodbye to broken Excel links:** Can't find the Excel workbook linked to your Data Visualizer diagram? Relink it, and you're back in business. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span></span>

- <span data-ttu-id="4e59f-1355">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1355">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="4e59f-1356">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1356">Switching between them has never been easier.</span></span> [<span data-ttu-id="4e59f-1357">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-1357">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="4e59f-1358">**從 Power BI 匯出 Visio 視覺效果：** 當匯出 Power BI 報表為 PDF 或 PowerPoint 等檔案時，Power BI Visio 視覺效果會正常顯示。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1358">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span> [<span data-ttu-id="4e59f-1359">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-1359">Learn more</span></span>](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a><span data-ttu-id="4e59f-1360">Word</span><span class="sxs-lookup"><span data-stu-id="4e59f-1360">Word</span></span>

- <span data-ttu-id="4e59f-1361">**[學習工具] 模式額外支援更多頁面色彩：** Word 中的 [學習工具] 新增更多頁面佈景主題色彩的支援，讓您能夠變更頁面的背景色彩。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1361">**Learning Tools mode has additional support for more page colors:** Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span> <span data-ttu-id="4e59f-1362">許多人在背景全白或全黑時閱讀會有困難，因此我們在 PC 和 Mac 的 Word 中增加了色彩選項。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1362">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

- <span data-ttu-id="4e59f-p237">**編輯當然是使用筆跡編輯：** 使用畫筆透過單一筆劃來分割或加入文字、新增新的一行，或插入文字。[深入了解](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span><span class="sxs-lookup"><span data-stu-id="4e59f-p237">**Editing comes naturally with Ink Editor:** With a single stroke, split or join words, add a new line, or insert words using your pen. [Learn more](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span></span>

- <span data-ttu-id="4e59f-p238">**為靜態文件注入動人的生命力：** 將文件轉變為在任何裝置上，均具有完美外觀的可互動、易分享的網頁。[深入了解](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span><span class="sxs-lookup"><span data-stu-id="4e59f-p238">**Take your doc from static to stunning:** Transform your document into an interactive, easy-to-share web page that looks great on any device. [Learn more](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span></span>

- <span data-ttu-id="4e59f-1367">**增加您內容的覆蓋面：** 想要讓您的文件更易於使用嗎？</span><span class="sxs-lookup"><span data-stu-id="4e59f-1367">**Increase the reach of your content:** Need to make your documents accessible?</span></span> <span data-ttu-id="4e59f-1368">讓協助工具檢查程式來幫助您，您不需要自行處理。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1368">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="4e59f-1369">按一下 [校閱] > [檢查協助工具] 試試看這個功能 – 我們會在狀態列上告訴您需要留意的部分。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1369">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="4e59f-1370">**快速找到該檔案：** 想要尋找最近使用過的檔案嗎？</span><span class="sxs-lookup"><span data-stu-id="4e59f-1370">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="4e59f-1371">只要在 [檔案] > [常用] 頁面的 [搜尋] 方塊中輸入，就能找到所需的檔案。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1371">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="4e59f-1372">**順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1372">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="4e59f-1373">在帳戶間切換就是這麼簡單。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1373">Switching between them has never been easier.</span></span> [<span data-ttu-id="4e59f-1374">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-1374">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="4e59f-p242">**運用行聚焦，提高理解力：** 毫不費力地逐行瀏覽文件。調整焦點，在檢視畫面中一次放入一行、三行或五行。[深入了解](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="4e59f-p242">**Improve comprehension with Line Focus:** Move through a document line by line without distractions. Adjust the focus to put one, three, or five lines in view at a time. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>

- <span data-ttu-id="4e59f-1378">**隨時儲存變更：** 將檔案上傳至 OneDrive，確保所有的更新都會自動儲存。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1378">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="4e59f-1379">**使用 \@Mentions 提及功能取得他人注意：** 在註解中使用 @mentions 提及功能，讓同事知道您需要他們提供建議。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1379">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="4e59f-1380">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-1380">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="4e59f-1381">**搜尋並享受：** 我們新增了 [搜尋以插入] 圖示，讓您輕鬆找到您要的圖示。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1381">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="4e59f-1382">而當您選取時，[插入] 按鈕會告知您已經選取的數量。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1382">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="4e59f-1383">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-1383">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="office-suite"></a><span data-ttu-id="4e59f-1384">Office 套件</span><span class="sxs-lookup"><span data-stu-id="4e59f-1384">Office Suite</span></span>

- <span data-ttu-id="4e59f-1385">**快速找到該檔案：** 想要尋找最近使用過的檔案嗎？</span><span class="sxs-lookup"><span data-stu-id="4e59f-1385">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="4e59f-1386">只要在 [檔案] > [開啟] 索引標籤的 [搜尋] 方塊中輸入，就能找到所需的檔案。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1386">Just type in the Search box on the File > Open tab to find the file you're looking for.</span></span>

- <span data-ttu-id="4e59f-1387">**隨時儲存變更：** 將檔案上傳至 OneDrive，確保所有的更新都會自動儲存。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1387">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="4e59f-1388">**隱私權控制：** 用於診斷資料和連線體驗的新增、更新及改良的控制項。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1388">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> [<span data-ttu-id="4e59f-1389">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-1389">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

- <span data-ttu-id="4e59f-1390">**Office 圖示有新的外觀：** Office 圖示經過重新設計，以反映簡單、功能強大且智慧型的 Office 體驗。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1390">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

- <span data-ttu-id="4e59f-1391">**安裝 Microsoft Teams：** 在 Office 365 專業增強版的現有安裝中，預設會安裝 Microsoft Teams。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1391">**Installation of Microsoft Teams:** Microsoft Teams is installed by default for existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="4e59f-1392">深入了解</span><span class="sxs-lookup"><span data-stu-id="4e59f-1392">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/teams-install)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="4e59f-1395">解決的問題</span><span class="sxs-lookup"><span data-stu-id="4e59f-1395">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="4e59f-1396">Access</span><span class="sxs-lookup"><span data-stu-id="4e59f-1396">Access</span></span>

- <span data-ttu-id="4e59f-1397">此更新修正彙總 (例如 Sum) 可能會將結果截斷成整數值的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1397">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="4e59f-1398">此更新修正包含參照遠端桌面 (例如 SQL Server 桌面) 的聯集查詢可能造成 Access 關閉並重新啟動的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1398">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="4e59f-1399">此更新可修正 Microsoft Access 中的「更新查詢」執行時或在 SQL 中使用 UPDATE 陳述式時，可能導致發生錯誤「查詢已損壞」&quot;&quot;的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1399">This update fixes an issue in Microsoft Access that may cause the error &quot;Query is Corrupt&quot; when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="4e59f-1400">Excel</span><span class="sxs-lookup"><span data-stu-id="4e59f-1400">Excel</span></span>

- <span data-ttu-id="4e59f-1401">文件標題的荷蘭文按鍵提示已變更為 Alt-G。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1401">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="4e59f-1402">修正在 Excel 中指派給圖形或表單控制項的巨集可能顯示不正確的錯誤訊息，或者可能會處理不正確目標範圍的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1402">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="4e59f-1403">解決「尋找及取代」在找到第一個項目後，對話方塊中的焦點位置變更的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1403">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="4e59f-1404">此更新修正在與其他使用者共同撰寫的工作階段中變更樞紐分析表排序的方式，然後重新整理可能觸發當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1404">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="4e59f-1405">我們已修正當 OLAP 樞紐分析表的篩選條件設定為已從 cube 移除的值時會發生的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1405">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="4e59f-1406">修正以校正使用圖表範本插入圖表時，預覽中使用的色彩。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1406">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="4e59f-1407">我們已修正當變更系列集合時，可能會導致散佈折線圖無法正確呈現的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1407">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span>

- <span data-ttu-id="4e59f-1408">已解決當插入或刪除儲存格時，瀑布圖和漏斗圖無法與表格同步處理的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1408">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="4e59f-1409">修正 Excel 中合併衝突的問題，此問題會造成提示使用者重新開啟活頁簿以取得變更。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1409">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="4e59f-1410">解決了開啟內嵌活頁簿時，功能區自訂無法載入的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1410">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="4e59f-1411">已解決造成執行階段錯誤啟動最小化視窗的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1411">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="4e59f-1412">解決了開啟內嵌活頁簿時，功能區自訂無法載入的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1412">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="4e59f-1413">已解決導致表格旁的剪下並貼上作業在與其他人共同撰寫時失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1413">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="4e59f-1414">解決使用執行中巨集變更自訂屬性時，會導致共同撰寫中斷的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1414">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="4e59f-1415">發生您無法從增益集開啟的 WPF (Windows Presentation Foundation) 表單的下拉式方塊選取項目的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1415">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="4e59f-1416">解決在未開啟活頁簿時，搜尋最近使用的檔案會造成當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1416">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="4e59f-1417">非同步使用者定義函數造成的效能問題，導致它們同步執行。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1417">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="4e59f-1418">已大幅改善刪除有合併儲存格之欄的效能。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1418">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="4e59f-1419">解決捲動後選取儲存格時，可能導致選取錯誤儲存格的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1419">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="4e59f-1420">已解決 Lookup 函數可能會傳回錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1420">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="4e59f-1421">解決在目前的 Office 版本中開啟在舊版 Office 中建立的活頁簿時，可能導致 Excel 懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1421">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="4e59f-1422">當檔案具備大量設定格式化的條件時，按一下 [字型色彩] 按鈕時出現的效能緩慢問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1422">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="4e59f-1423">我們已修正預覽列印中的列印範圍不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1423">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="4e59f-1424">從不受信任的網路共用編輯受保護的檔案時，Excel 可能會發生問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1424">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="4e59f-1425">我們已大幅提升依色彩篩選的效能。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1425">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="4e59f-1426">已解決會導致將超連結貼到一些受保護工作表中的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1426">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="4e59f-1427">當在增益集管理員中瀏覽時，顯示 16 個以上的增益集。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1427">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="4e59f-1428">這項變更透過利用軟體轉譯避免特定 Intel 圖形驅動程式發生問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1428">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="4e59f-1429">來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1429">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="4e59f-1430">此更新修正 Office 文件無法上傳到商務用 OneDrive 的錯誤 (訊息「上傳失敗」)。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1430">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="4e59f-1431">已修正在 Excel 構想功能中，在 Win32 用戶端中按一下 [構想] 按鈕來載入增益集時會發生錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1431">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span>

### <a name="outlook"></a><span data-ttu-id="4e59f-1432">Outlook</span><span class="sxs-lookup"><span data-stu-id="4e59f-1432">Outlook</span></span>

- <span data-ttu-id="4e59f-1433">來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1433">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="4e59f-1434">修正使用者將信箱從基本驗證升級為新式驗證後，造成將錯誤的帳戶與其 Outlook 設定檔相關聯的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1434">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="4e59f-1435">已解決造成網頁增益集在不該存取數位版權管理郵件時進行存取的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1435">Addressed an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="4e59f-1436">已解決導致部分安全連結無法顯示簡單動態顯示 URL 的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1436">Addressed an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="4e59f-1437">更新 Outlook 中的附件封鎖邏輯，以同時封鎖 python 附件。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1437">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="4e59f-1438">已解決導致部分 POP3 使用者查看所有純文字格式電子郵件 (無論設定) 的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1438">Addressed an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="4e59f-1439">此修正將會還原 HTML 格式郵件的檢視。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1439">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="4e59f-1440">已解決當使用者將項目從其主要行事曆複製到群組行事曆時，造成使用者遇到權限錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1440">Addressed an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="4e59f-1441">已解決導致使用者無法透過螢幕助讀程式存取位置建議的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1441">Addressed an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="4e59f-1442">已解決當使用者透過鍵盤快速鍵與信箱資料夾互動時造成明顯延遲的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1442">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="4e59f-1443">已解決導致非常長時間的 Outlook 工作階段記憶體流失的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1443">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="4e59f-1444">已解決導致使用者在開啟 [規則] 對話方塊時看到「在這部電腦中建立的規則和 Microsoft Exchange 上的規則衝突」提示的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1444">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="4e59f-1445">已解決導致使用者在與特定安全連結互動時在 Outlook 中發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1445">Addressed an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="4e59f-1446">已解決導致經理對於代理人是否已經回覆特定會議邀請含混不清的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1446">Addressed an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="4e59f-1447">已解決導致使用者在處理某些自動探索回應時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1447">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="4e59f-1448">已解決導致使用者在嘗試從 [帳戶建立] 內容連絡支援服務時，看到具有 [確定] 按鈕的空白訊息方塊的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1448">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="4e59f-1449">此變更可讓系統管理員啟用一個原則，以在自動探索驗證提示中較 UPN 優先使用所提供的帳戶電子郵件。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1449">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="4e59f-1450">依預設，自動探索會優先於帳戶 UPN (如果有的話)。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1450">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="4e59f-1451">解決會導致使用者看到針對新式群組的搜尋失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1451">Addressed an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="4e59f-1452">已解決導致 Outlook 使用者在特定案例中停滯在「需要密碼」狀態的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1452">Addressed an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="4e59f-1453">已解決以下問題：使用者看到某會議室可用時間之外的會議室建議。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1453">Addressed an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="4e59f-1454">已解決導致使用者在傳送加密電子郵件時遇到「不支援的加密演算法」錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1454">Addressed an issue that caused users to encounter "encryption algorithm is not supported" errors when sending an encrypted email.</span></span>

- <span data-ttu-id="4e59f-1455">已解決非英文使用者的郵件中，主旨列會相當小的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1455">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="4e59f-1456">已解決導致某些使用者在新增次要 Exchange 帳戶時看到建立了重複特殊資料夾的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1456">Addressed an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="4e59f-1457">已解決導致使用者嘗試從「未接的交談」建立規則時遇到當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1457">Addressed an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="4e59f-1458">已修正 SMIME 演算法選取的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1458">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="4e59f-1459">已解決使用其他寄件者時導致無法顯示原則提示的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1459">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="4e59f-1460">已解決導致使用者在 Outlook 處理序中看到記憶體洩漏的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1460">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="4e59f-1461">已解決導致使用者在更新目前狀態資訊時遇到間歇性當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1461">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="4e59f-1462">已解決導致目前的資料夾搜尋間歇性失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1462">Addressed an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="4e59f-1463">已解決嘗試擷取使用者的 Outlook 雲端設定時，導致一些使用者遇到驗證錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1463">Addressed an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="4e59f-1464">已解決導致在搜尋意見反應體驗中懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1464">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="4e59f-1465">已解決導致使用者在處理某些自動探索回應時發生當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1465">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="4e59f-1466">已解決導致使用者在更新目前狀態資訊時遇到間歇性當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1466">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="4e59f-1467">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4e59f-1467">PowerPoint</span></span>

- <span data-ttu-id="4e59f-1468">修正某些增益集會在圖表的圖形周圍擲出未預期錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1468">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="4e59f-1469">來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1469">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="4e59f-1470">此變更還原 PowerPoint 影片控制項的協助工具名稱的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1470">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="4e59f-1471">我們已修正部分動畫無法開始的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1471">We fixed an issue which could prevent some animations from starting.</span></span>

- <span data-ttu-id="4e59f-1472">我們已修正將投影片從一個簡報複製到另一個簡報時可能會造成母片重複的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1472">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>

- <span data-ttu-id="4e59f-1473">如果在不支援的版本中開啟含有新的新式註解的檔案，將會顯示黃色警告</span><span class="sxs-lookup"><span data-stu-id="4e59f-1473">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

- <span data-ttu-id="4e59f-1474">可靠性修正：已修正第三方增益集可能會造成 PowerPoint 當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1474">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="4e59f-1475">已修正 PowerPoint 中半形片假名字元在垂直文字方塊中無法正確旋轉的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1475">Fixed an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="4e59f-1476">Project</span><span class="sxs-lookup"><span data-stu-id="4e59f-1476">Project</span></span>

- <span data-ttu-id="4e59f-1477">修正讓 Windows 7 上的使用者能夠從 Project Web App 和 SharePoint 網站開啟專案的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1477">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="4e59f-1478">發現在開啟唯讀專案時，使用者可能會收到數個訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1478">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="4e59f-1479">「全部撫平」命令無法正確解決資源過度分派的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1479">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="4e59f-1480">當您有作業中有零個工作的指派時，可能無法將作業標示為完成且永遠會顯示為 99%。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1480">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

### <a name="visio"></a><span data-ttu-id="4e59f-1481">Visio</span><span class="sxs-lookup"><span data-stu-id="4e59f-1481">Visio</span></span>

- <span data-ttu-id="4e59f-1482">無法從 Visio 將多個圖形匯出為 SVG。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1482">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="4e59f-1483">Word</span><span class="sxs-lookup"><span data-stu-id="4e59f-1483">Word</span></span>

- <span data-ttu-id="4e59f-1484">此變更能讓使用 Word 開啟文件的效能提升。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1484">This change will lead to performance improvements in opening documents using Word.</span></span>

- <span data-ttu-id="4e59f-1485">來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1485">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="4e59f-1486">我們已修正當列印到 Deskjet 印表機時，可能會導致縮放比例問題的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1486">We fixed an issue which could have caused scaling issues when printing to Deskjet printers.</span></span>

- <span data-ttu-id="4e59f-1487">我們已修正追蹤修訂有時候會進入無限迴圈的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1487">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="4e59f-1488">已修正應用程式可能在關機時懸置的各種問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1488">Fixed various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="4e59f-1489">同時修正特定相關增益集當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1489">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="4e59f-1490">Office 套件</span><span class="sxs-lookup"><span data-stu-id="4e59f-1490">Office Suite</span></span>

- <span data-ttu-id="4e59f-1491">已修正不正確地將平假名和漢字中的日本新年號 "Reiwa" (令和) 識別為拼字錯誤或不合文法的運算式的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1491">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="4e59f-1492">已修正嘗試共用儲存在 SharePoint 2016 上的檔案時，導致使用者遇到「很抱歉，發生問題，無法共用」訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1492">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="4e59f-1493">已修正在 PowerPoint 共同撰寫和離線編輯的工作階段中可能會導致資料遺失的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1493">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="4e59f-1494">修正使用者在開啟檔案時可能會遇到的當機問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1494">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="4e59f-1495">避免 PowerPoint 使用者嘗試進行「線上展示」時遇到錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1495">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

- <span data-ttu-id="4e59f-1496">在某些情況下，同步處理引擎備份的 SharePoint 檔案可能會顯示「已儲存」但實際上未儲存任何變更，導致資料遺失。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1496">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="4e59f-1497">解決使用者可能無法儲存 Word、Excel 和 PowerPoint 文件的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1497">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="4e59f-1498">此問題會影響建立新檔案並在按一下 [儲存] 圖示或按 Ctrl + S 之後帶出 [另存成模型對話方塊] 選項的使用者。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1498">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="4e59f-1499">已修正 Win7 的效能問題，其中，於所有應用程式中從功能區插入圖案庫時，大約需要 4 秒鐘的時間才會顯示。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1499">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="4e59f-1500">已修正 Backstage 的 [資訊位置] 平板未顯示協助工具資訊的錯誤。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1500">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="4e59f-1501">改善有關登錄完整性的 Office 更新程序的可靠性。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1501">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="4e59f-1502">解決 Office 更新可能會非預期地從 Office CDN 而不是預期使用的來源 (例如本機或網路共用或 Configuration Manager 提供的位置) 下載檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1502">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="4e59f-1503">修正了 Office 更新訊息不以預期語言顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1503">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="4e59f-1504">自此以後，Office 更新訊息會正確符合 Windows 顯示語言。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1504">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="4e59f-1505">已解決在某些情況下，如果使用者不是系統管理員且系統帳戶沒有網路連線，將無法套用更新的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1505">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="4e59f-1506">某些情況下，Office 快速鍵可能會在更新後消失。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1506">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="4e59f-1507">此更新可改善發佈 Office 快速鍵時的可靠性。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1507">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="4e59f-1508">已更正可能會在計量網路上意外封鎖更新的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1508">Corrected an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="4e59f-1509">修正相對期限只有在第一次設定時才會有效的 ODT 和 GPO 更新期限設定中的錯誤 (bug)。此修正可啟用後續更新的相關期限。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1509">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="4e59f-1510">已改善透過恢復之前可能已中斷的下載，下載 Office 更新時的可靠性。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1510">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="4e59f-1511">已解決第三方外掛程式中與文字方塊/圖案自動調整屬性相關的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1511">Addressed issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="4e59f-1512">我們已修正大型樹狀檢視可能會導致當機的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1512">We fixed an issue where large tree views could result in a crash.</span></span>

- <span data-ttu-id="4e59f-1513">為了保護 Office 客戶的安全性，我們現在專門使用 SHA-2 演算法來簽署 Microsoft Office 更新。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1513">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-january-14"></a><span data-ttu-id="4e59f-1515">版本 1902：1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="4e59f-1515">Version 1902: January 14</span></span>
<span data-ttu-id="4e59f-1516">*版本 1902 (組建 11328.20512)*</span><span class="sxs-lookup"><span data-stu-id="4e59f-1516">*Version 1902 (Build 11328.20512)*</span></span>

<span data-ttu-id="4e59f-1517">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4e59f-1517">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="4e59f-1519">解決的問題</span><span class="sxs-lookup"><span data-stu-id="4e59f-1519">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="4e59f-1520">Excel</span><span class="sxs-lookup"><span data-stu-id="4e59f-1520">Excel</span></span>

- <span data-ttu-id="4e59f-1521">解決了開啟內嵌活頁簿時，功能區自訂無法載入的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1521">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="4e59f-1522">Outlook</span><span class="sxs-lookup"><span data-stu-id="4e59f-1522">Outlook</span></span>

- <span data-ttu-id="4e59f-1523">解決導致使用者在傳送加密電子郵件時遇到「不支援的加密演算法」錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1523">Addresses an issue that caused users to encounter "encryption algorithm is not supporte" errors when sending an encrypted email.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="4e59f-1524">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4e59f-1524">PowerPoint</span></span>

- <span data-ttu-id="4e59f-1525">如果在不支援的版本中開啟含有新的新式註解的檔案，將會顯示黃色警告。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1525">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

### <a name="word"></a><span data-ttu-id="4e59f-1526">Word</span><span class="sxs-lookup"><span data-stu-id="4e59f-1526">Word</span></span>

- <span data-ttu-id="4e59f-1527">此變更能讓使用 Word 開啟文件的效能提升。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1527">This change will lead to performance improvements in opening documents using Word.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1808-january-14"></a><span data-ttu-id="4e59f-1529">版本 1808：1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="4e59f-1529">Version 1808: January 14</span></span>
<span data-ttu-id="4e59f-1530">*版本 1808 (組建 10730.20432)*</span><span class="sxs-lookup"><span data-stu-id="4e59f-1530">*Version 1808 (Build 10730.20432)*</span></span>

<span data-ttu-id="4e59f-1531">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4e59f-1531">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

> [!NOTE]
> <span data-ttu-id="4e59f-1533">如果您需要關於使用 Office 的問題協助，建議您將問題張貼在 [Microsoft Answers 論壇](https://answers.microsoft.com/)或[技術社群](https://techcommunity.microsoft.com/)，或連絡[支援](https://support.microsoft.com/contactus)。</span><span class="sxs-lookup"><span data-stu-id="4e59f-1533">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (DO NOT MODIFY ADMIN CENTER METADATA CONTENT START)
[//]: # (|Win32|DC|Production| |16.0.13127.21216|version-2008-february-09|)
[//]: # (|Win32|DC|Production| |16.0.13127.21064|version-2008-january-12|)
[//]: # (|Win32|DC|Production| |16.0.12527.21416|version-2002-december-08|)
[//]: # (|Win32|DC|Production| |16.0.12527.21330|version-2002-november-10|)
[//]: # (|Win32|DC|Production| |16.0.12527.21236|version-2002-october-13|)
[//]: # (|Win32|DC|Production| |16.0.12527.21104|version-2002-september-08|)
[//]: # (|Win32|DC|Production||16.0.12527.20988|version-2002-august-11|)
[//]: # (|Win32|DC|Production| |16.0.12527.20880|version-2002-july-14|)
[//]: # (DO NOT MODIFY ADMIN CENTER METADATA CONTENT END)
