---
title: 每月企業通道版本的版本資訊
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為 IT 專業人員提供 Microsoft 365 Apps 每月企業通道版本的版本資訊
ms.openlocfilehash: 96a76ed1ed1849753422dae92626484a77cec2a4
ms.sourcegitcommit: 4f5536e809f58462d81c708c153390ebfd1abc4e
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/13/2021
ms.locfileid: "53409559"
---
# <a name="release-notes-for-monthly-enterprise-channel"></a><span data-ttu-id="7eace-103">每月企業通道的版本資訊</span><span class="sxs-lookup"><span data-stu-id="7eace-103">Release notes for Monthly Enterprise Channel</span></span>

<span data-ttu-id="7eace-104">這些版本資訊提供新功能和非安全性更新的相關資訊，這些功能和非安全性更新包含 Microsoft 365 Apps 企業版、Microsoft 365 Apps 商務版，以及 Project 和 Visio 版的傳統型應用程式訂閱版本的每月企業通道更新。</span><span class="sxs-lookup"><span data-stu-id="7eace-104">These release notes provide information about new features and non-security updates that are included in Monthly Enterprise Channel updates for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>


[//]: # (DO NOT REMOVE)



## <a name="version-2105-july-13"></a><span data-ttu-id="7eace-106">版本 2105：7 月 13 日</span><span class="sxs-lookup"><span data-stu-id="7eace-106">Version 2105: July 13</span></span>
<span data-ttu-id="7eace-107">*版本 2105 (組建 14026.20334)*</span><span class="sxs-lookup"><span data-stu-id="7eace-107">*Version 2105 (Build 14026.20334)*</span></span>

<span data-ttu-id="7eace-108">安全性更新列於[此處](microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="7eace-108">Security updates listed [here](microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="7eace-110">功能更新</span><span class="sxs-lookup"><span data-stu-id="7eace-110">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="7eace-111">Outlook</span><span class="sxs-lookup"><span data-stu-id="7eace-111">Outlook</span></span>

- <span data-ttu-id="7eace-112">**搜尋時取得相關的檔案建議：** 當您在 [搜尋方塊] 中輸入時，與搜尋相關的最相關檔案將會包含在您的建議中。</span><span class="sxs-lookup"><span data-stu-id="7eace-112">**Get relevant file suggestions when you search:** When you type in the Search box, the most relevant files related to your search will be included in your suggestions.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="7eace-115">解決的問題</span><span class="sxs-lookup"><span data-stu-id="7eace-115">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="7eace-116">Excel</span><span class="sxs-lookup"><span data-stu-id="7eace-116">Excel</span></span>

- <span data-ttu-id="7eace-117">修正問題，讓名稱管理員可以在具有大量隱藏名稱的書籍上開啟。</span><span class="sxs-lookup"><span data-stu-id="7eace-117">Fixed an issue to enable the Name Manager to open on books with a large number of hidden names.</span></span>


- <span data-ttu-id="7eace-118">已修正部分使用者在 Excel 增益集清單中顯示額外的問題項目。</span><span class="sxs-lookup"><span data-stu-id="7eace-118">We fixed an issue where extra entries appeared in the Excel Add-in list for some users.</span></span>


- <span data-ttu-id="7eace-119">修正分析工具箱增益集對某些使用者無法運作的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-119">Fixed an issue where the Analysis ToolPak add-in did not work for some users.</span></span>


### <a name="outlook"></a><span data-ttu-id="7eace-120">Outlook</span><span class="sxs-lookup"><span data-stu-id="7eace-120">Outlook</span></span>

- <span data-ttu-id="7eace-121">變更是停止動作和在變更閘道下進行，因此如果發生問題，可以快速關閉。</span><span class="sxs-lookup"><span data-stu-id="7eace-121">Change is going in dark and under a change gate so if there are issues it can be turned off quickly.</span></span>


- <span data-ttu-id="7eace-122">我們已新增一個登錄機碼，以停用新會議室尋找工具體驗 (與 Outlook 網頁版相同的體驗)，並啟用具有建議的時間的傳統會議室尋找工具。</span><span class="sxs-lookup"><span data-stu-id="7eace-122">We added a registry key that disables the new Room Finder experience (the same experience as in Outlook for Web) and enables the legacy Room Finder with Suggested Times.</span></span>

   <span data-ttu-id="7eace-123">登錄機碼:</span><span class="sxs-lookup"><span data-stu-id="7eace-123">Registry Key:</span></span>

    ><span data-ttu-id="7eace-124">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar REG_DWORD “ShowLegacyRoomFinder”</span><span class="sxs-lookup"><span data-stu-id="7eace-124">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar REG_DWORD “ShowLegacyRoomFinder”</span></span>

    ><span data-ttu-id="7eace-125">0 (預設值) - 當使用者按一下 [會議室尋找工具] 按鈕以搜尋可用的會議室時，Outlook 會使用新會議室尋找工具 OWA 提供的體驗</span><span class="sxs-lookup"><span data-stu-id="7eace-125">0 (default) - Outlook uses new Room Finder OWA Powered eXperience when user clicks 'Room Finder' button to search for available rooms</span></span></br>
    ><span data-ttu-id="7eace-126">1 - Outlook 使用舊版會議室尋找工具 UI 來搜尋可用的會議室</span><span class="sxs-lookup"><span data-stu-id="7eace-126">1 - Outlook uses legacy Room Finder UI to search for available rooms</span></span>


- <span data-ttu-id="7eace-127">此變更可讓使用者透過我們新的意見反應系統提交意見反應。</span><span class="sxs-lookup"><span data-stu-id="7eace-127">This change enables users to submit feedback through our new feedback system.</span></span>


- <span data-ttu-id="7eace-128">我們已修正導致意見反應選項對 Office Perpetual 2021 預覽的使用者停用的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-128">We fixed an issue that caused the feedback option to be disabled for users of the Office Perpetual 2021 preview.</span></span>


- <span data-ttu-id="7eace-129">我們已修正導致使用者在從電子郵件收件者的右鍵操作功能表選取 [開啟 Outlook 內容] 時出現錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-129">We fixed an issue that caused users to get an error when selecting "Open Outlook Properties" from the right click context menu for a recipient on an email.</span></span>


- <span data-ttu-id="7eace-130">我們已修正在載入個人卡片時，導致某些使用者遇到應用程式意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-130">We fixed an issue that caused some users to experience unexpected app close when loading person cards.</span></span>


- <span data-ttu-id="7eace-131">我們已修正在從封存區移除資料夾時，導致使用者遇到意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-131">We fixed an issue that caused users to experience a unexpected close when removing folders from an archive store.</span></span>


- <span data-ttu-id="7eace-132">我們已修正透過螢幕閱讀程式技術導致「縮短會議」功能的一些指示停用的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-132">We fixed an issue that caused some instructions for the "Shorten Meetings" feature to be disabled through screen reader technologies.</span></span>


- <span data-ttu-id="7eace-133">我們已修正會導致使用者在關閉已回覆或轉寄的郵件時，遇到未預期的屬性變更提示的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-133">We fixed an issue that caused users to experience an unexpected property change prompt when closing a message they had replied to or forwarded.</span></span>


- <span data-ttu-id="7eace-134">我們已修正可能導致操作 Outlook 郵件或檢視行事曆時意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-134">We fixed an issue that may cause a unexpected close when interacting with Outlook Mail or Calendar Views.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="7eace-135">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7eace-135">PowerPoint</span></span>

- <span data-ttu-id="7eace-136">修正少數使用者無法使用 [重複使用投影片] 選項的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-136">Fixed an issue where Reuse Slides option was not available for few users.</span></span>


### <a name="project"></a><span data-ttu-id="7eace-137">Project</span><span class="sxs-lookup"><span data-stu-id="7eace-137">Project</span></span>

- <span data-ttu-id="7eace-138">已修正手動排程任務的工作分派移至不正確日期的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-138">Fixed an issue where assignments on manually scheduled tasks moved to an incorrect date.</span></span>


- <span data-ttu-id="7eace-139">修正當您建立的自訂欄位公式使用 ProjectDate */ProjectDur* 函數，且若第二個參數是 Date()、Now() 或 Time() 日期和時間函數時，會導致 #ERROR 結果的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-139">Fixed an issue where if you create a custom field formula which uses the ProjectDate */ProjectDur* functions and if the second parameter is the Date(), Now() or Time() date and time functions, then a #ERROR results.</span></span>


### <a name="word"></a><span data-ttu-id="7eace-140">Word</span><span class="sxs-lookup"><span data-stu-id="7eace-140">Word</span></span>

- <span data-ttu-id="7eace-141">修正編輯器窗格無法開啟的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-141">Fixes an issue where the Editor Pane doesn't open.</span></span>


- <span data-ttu-id="7eace-142">已修正拼字及文法檢查的畫布內容卡顯示圖示按鈕沒有工具提示的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-142">Fixed an issue where canvas contextual cards for spelling and grammar show icon buttons, but those buttons have no tooltips.</span></span>


### <a name="office-suite"></a><span data-ttu-id="7eace-143">Office 套件</span><span class="sxs-lookup"><span data-stu-id="7eace-143">Office Suite</span></span>

- <span data-ttu-id="7eace-144">已修正 en-gb、fr-ca 和 es-mx 現在會與其各自的來源版本相符合的當地語系化問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-144">Fixed a localization issue where en-gb, fr-ca, and es-mx will now be matched with their respective parent versions.</span></span>


- <span data-ttu-id="7eace-145">已修正重新開啟特定檔案時意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-145">Fixed a unexpected close when reopening certain files.</span></span>


- <span data-ttu-id="7eace-146">已修正開啟 SyncBacked 檔案時出現效能迴歸的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-146">Fixed a performance regression on opening SyncBacked files.</span></span>


- <span data-ttu-id="7eace-147">已修正使用者無法編輯儲存在 OnPrem SharePoint 伺服器中特定文件的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-147">Fixed an issue where user is unable to edit certain documents stored in OnPrem sharepoint servers.</span></span>



[//]: # (請勿移除 BUGDETAILS 內容結尾)

## <a name="version-2104-july-13"></a><span data-ttu-id="7eace-149">版本 2104：7 月 13 日</span><span class="sxs-lookup"><span data-stu-id="7eace-149">Version 2104: July 13</span></span>
<span data-ttu-id="7eace-150">*版本 2104 (組建 13929.20434)*</span><span class="sxs-lookup"><span data-stu-id="7eace-150">*Version 2104 (Build 13929.20434)*</span></span>

<span data-ttu-id="7eace-151">安全性更新列於[此處](microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="7eace-151">Security updates listed [here](microsoft365-apps-security-updates.md)</span></span>

## <a name="version-2104-june-08"></a><span data-ttu-id="7eace-152">版本 2104：6 月 08 日</span><span class="sxs-lookup"><span data-stu-id="7eace-152">Version 2104: June 08</span></span>
<span data-ttu-id="7eace-153">*版本 2104 (組建 13929.20408)*</span><span class="sxs-lookup"><span data-stu-id="7eace-153">*Version 2104 (Build 13929.20408)*</span></span>

<span data-ttu-id="7eace-154">安全性更新列於[此處](microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="7eace-154">Security updates listed [here](microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="7eace-156">功能更新</span><span class="sxs-lookup"><span data-stu-id="7eace-156">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="7eace-157">Excel</span><span class="sxs-lookup"><span data-stu-id="7eace-157">Excel</span></span>

- <span data-ttu-id="7eace-158">**自動儲存並在敏感性加密文件上進行共同撰寫：** 不要為了安全性而犧牲生產力。</span><span class="sxs-lookup"><span data-stu-id="7eace-158">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="7eace-159">有了 Microsoft 資訊保護，使用敏感度標籤加密的文件現在可以自動儲存，並與他人進行即時共同撰寫，就彷彿文件未加密一樣便利。</span><span class="sxs-lookup"><span data-stu-id="7eace-159">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="7eace-160">需要租用戶選擇加入 (詳細資訊： https://aka.ms/mipcoauth)。</span><span class="sxs-lookup"><span data-stu-id="7eace-160">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7eace-161">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7eace-161">PowerPoint</span></span>

- <span data-ttu-id="7eace-162">**自動儲存並在敏感性加密文件上進行共同撰寫：** 不要為了安全性而犧牲生產力。</span><span class="sxs-lookup"><span data-stu-id="7eace-162">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="7eace-163">有了 Microsoft 資訊保護，使用敏感度標籤加密的文件現在可以自動儲存，並與他人進行即時共同撰寫，就彷彿文件未加密一樣便利。</span><span class="sxs-lookup"><span data-stu-id="7eace-163">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="7eace-164">需要租用戶選擇加入 (詳細資訊： https://aka.ms/mipcoauth)。</span><span class="sxs-lookup"><span data-stu-id="7eace-164">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>

### <a name="word"></a><span data-ttu-id="7eace-165">Word</span><span class="sxs-lookup"><span data-stu-id="7eace-165">Word</span></span>

- <span data-ttu-id="7eace-166">**自動儲存並在敏感性加密文件上進行共同撰寫：** 不要為了安全性而犧牲生產力。</span><span class="sxs-lookup"><span data-stu-id="7eace-166">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="7eace-167">有了 Microsoft 資訊保護，使用敏感度標籤加密的文件現在可以自動儲存，並與他人進行即時共同撰寫，就彷彿文件未加密一樣便利。</span><span class="sxs-lookup"><span data-stu-id="7eace-167">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="7eace-168">需要租用戶選擇加入 (詳細資訊： https://aka.ms/mipcoauth)。</span><span class="sxs-lookup"><span data-stu-id="7eace-168">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="7eace-171">解決的問題</span><span class="sxs-lookup"><span data-stu-id="7eace-171">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="7eace-172">Excel</span><span class="sxs-lookup"><span data-stu-id="7eace-172">Excel</span></span>

- <span data-ttu-id="7eace-173">我們已修正部分檔案有時無法在 [受保護的檢視] 中開啟的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-173">We fixed an issue where some files would occasionally fail to open in Protected View.</span></span>


- <span data-ttu-id="7eace-174">我們已修正在使用增益集時，會導致某些語言的日期格式顯示不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-174">We fixed an issue that caused date formatting to be displayed incorrectly in some languages when using add-ins.</span></span>


- <span data-ttu-id="7eace-175">修正流量分析工具箱增益集對某些使用者無法運作的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-175">Fixed an issue where the Analysis ToolPak add-in did not work for some users.</span></span>


- <span data-ttu-id="7eace-176">修正針對部分使用者在 Excel 增益集清單中顯示的額外項目問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-176">Fixed an issue where extra entries appeared in the Excel Add-in list for some users.</span></span>


- <span data-ttu-id="7eace-177">修正主要版本組建的復原可能會導致檔案開啟時當機的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-177">Fix for an issue where a major version build rollback could result in the application terminating on file open.</span></span>


### <a name="outlook"></a><span data-ttu-id="7eace-178">Outlook</span><span class="sxs-lookup"><span data-stu-id="7eace-178">Outlook</span></span>

- <span data-ttu-id="7eace-179">我們已修正導致某些使用行事曆共用改進功能的使用者在功能窗格中與他們的行事曆互動時發生的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-179">We fixed an issue that caused some users of the calendar sharing improvements feature to experience issues with interacting with their calendar in the navigation pane.</span></span>


- <span data-ttu-id="7eace-180">我們已新增一個登錄機碼，以停用新會議室尋找工具體驗 (與 Outlook 網頁版相同的體驗)，並啟用具有建議的時間的傳統會議室尋找工具。</span><span class="sxs-lookup"><span data-stu-id="7eace-180">We added a registry key that disables the new Room Finder experience (the same experience as in Outlook for Web) and enables the legacy Room Finder with Suggested Times.</span></span>
    
    <span data-ttu-id="7eace-181">登錄機碼:</span><span class="sxs-lookup"><span data-stu-id="7eace-181">Registry Key:</span></span>

    ><span data-ttu-id="7eace-182">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar</span><span class="sxs-lookup"><span data-stu-id="7eace-182">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar</span></span> </br>
    ><span data-ttu-id="7eace-183">REG_DWORD “ShowLegacyRoomFinder”</span><span class="sxs-lookup"><span data-stu-id="7eace-183">REG_DWORD “ShowLegacyRoomFinder”</span></span></br></br>
    > <span data-ttu-id="7eace-184">0 (預設值) - 當使用者按一下 [會議室尋找工具] 按鈕以搜尋可用的會議室時，Outlook 會使用新會議室尋找工具 OWA 提供的體驗</span><span class="sxs-lookup"><span data-stu-id="7eace-184">0 (default) - Outlook uses new Room Finder OWA Powered eXperience when user clicks 'Room Finder' button to search for available rooms</span></span>  </br>
    > <span data-ttu-id="7eace-185">1 - Outlook 使用舊版會議室尋找工具 UI 來搜尋可用的會議室</span><span class="sxs-lookup"><span data-stu-id="7eace-185">1 - Outlook uses legacy Room Finder UI to search for available rooms</span></span> </br>


- <span data-ttu-id="7eace-186">我們已修正在代表另一個使用者進行傳送，並且針對非全域通訊清單的通訊錄進行解析時，造成名稱解析失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-186">We fixed an issue that caused name resolution to fail when sending on behalf of another user and resolving against an address book that is not the Global Address List.</span></span>


- <span data-ttu-id="7eace-187">我們已修正導致無法向 Office Perpetual 2021 預覽使用者顯示意見回應選項的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-187">We fixed an issue that caused the feedback option to fail to appear for users of the Office Perpetual 2021 preview.</span></span>


- <span data-ttu-id="7eace-188">我們已修正可能造成使用者看到正在撰寫的郵件失去 UI 焦點的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-188">We fixed an issue that could cause users to see the message that they are composing losing the UI focus.</span></span>


- <span data-ttu-id="7eace-189">我們已修正會導致 Outlook 覆寫 OWA 中已設定的焦點收件匣喜好設定問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-189">We fixed an issue that caused Outlook to override the Focused Inbox preferences configured in OWA.</span></span>


- <span data-ttu-id="7eace-190">我們已修正會導致使用者看到簽名意外消失的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-190">We fixed an issue that caused users to see signatures disappear unexpectedly.</span></span>


- <span data-ttu-id="7eace-191">我們已修正會導致漫遊設定的使用者遇到無回應的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-191">We fixed an issue that caused users of roaming settings to experience unresponsiveness.</span></span>


- <span data-ttu-id="7eace-192">我們已修正會導致使用者在搜尋時，遇到處里程序意外終止的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-192">We fixed an issue that caused users to experience the process terminating unexpectedly when searching.</span></span>


- <span data-ttu-id="7eace-193">我們已修正與搜尋相關的意外關閉問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-193">We fixed a search-related unexpected close.</span></span>


- <span data-ttu-id="7eace-194">我們已修正造成 Oulook 中的人員選擇器針對具永久授權的使用者向上展開而非向下展開的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-194">We fixed an issue that caused the people picker in Outlook to expand upwards rather than downwards for users with a perpetual license.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="7eace-195">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7eace-195">PowerPoint</span></span>

- <span data-ttu-id="7eace-196">修正少數使用者無法使用 [重複使用投影片] 選項的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-196">Fixed an issue where Reuse Slides option was not available for a few users.</span></span>


- <span data-ttu-id="7eace-197">我們已修正與連結圖片相關的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-197">We fixed an issue related to linked pictures.</span></span>


- <span data-ttu-id="7eace-198">已修正主要版本組建的復原可能會導致檔案開啟時意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-198">Fixed an issue where a major version build rollback could result in an unexpected close on file open.</span></span>


### <a name="project"></a><span data-ttu-id="7eace-199">Project</span><span class="sxs-lookup"><span data-stu-id="7eace-199">Project</span></span>

- <span data-ttu-id="7eace-200">修正使用者無法從資源資料庫移除專案的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-200">Fixed an issue where users were unable to remove projects from the resource pool.</span></span>


### <a name="word"></a><span data-ttu-id="7eace-201">Word</span><span class="sxs-lookup"><span data-stu-id="7eace-201">Word</span></span>

- <span data-ttu-id="7eace-202">已修正編輯 OLE 物件時需要變更的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-202">We fixed an issue which required a change on editing OLE object.</span></span>


- <span data-ttu-id="7eace-203">已修正在閱讀模式中使用深色模式主題時，某些選取的文字無法顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-203">We fixed an issue where some select text was not visible when using darkmode theme in reading mode.</span></span>


- <span data-ttu-id="7eace-204">已修正由於使用者登出或重新啟動電腦而電腦關機時，可能導致 Word 意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-204">Fixed an issue that may cause Word to unexpectedly close when shutting down due to the user logging off or restarting their computer.</span></span>


- <span data-ttu-id="7eace-205">已修正對本機儲存之檔案的自動儲存圖說文字進行更新的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-205">We fixed an issue that updates text on autosave callout for files saved locally.</span></span>


- <span data-ttu-id="7eace-206">已修正主要版本組建的復原可能會導致檔案開啟時意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-206">Fixed an issue where a major version build rollback could result in an unexpected close on file open.</span></span>


### <a name="office-suite"></a><span data-ttu-id="7eace-207">Office 套件</span><span class="sxs-lookup"><span data-stu-id="7eace-207">Office Suite</span></span>

- <span data-ttu-id="7eace-208">已修正會導致雲端文件無法開啟的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-208">Fixed an issue that would cause cloud document to fail to open.</span></span>


- <span data-ttu-id="7eace-209">此變更會剖析 Cobalt 回應上傳送的新 TenantId 屬性，並儲存在中央資料表中。</span><span class="sxs-lookup"><span data-stu-id="7eace-209">This change parses the new TenantId attribute sent on Cobalt responses and stores it in the Central Table.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2103-june-08"></a><span data-ttu-id="7eace-211">版本 2103：6 月 8 日</span><span class="sxs-lookup"><span data-stu-id="7eace-211">Version 2103: June 08</span></span>
<span data-ttu-id="7eace-212">*版本 2103 (組建 13901.20554)*</span><span class="sxs-lookup"><span data-stu-id="7eace-212">*Version 2103 (Build 13901.20554)*</span></span>

<span data-ttu-id="7eace-213">安全性更新列於[此處](microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="7eace-213">Security updates listed [here](microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="7eace-215">解決的問題</span><span class="sxs-lookup"><span data-stu-id="7eace-215">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="7eace-216">Excel</span><span class="sxs-lookup"><span data-stu-id="7eace-216">Excel</span></span>

- <span data-ttu-id="7eace-217">修正針對部分使用者在 Excel 增益集清單中顯示的額外項目問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-217">Fixed an issue where extra entries appeared in the Excel Add-in list for some users.</span></span>


### <a name="office-suite"></a><span data-ttu-id="7eace-218">Office 套件</span><span class="sxs-lookup"><span data-stu-id="7eace-218">Office Suite</span></span>

- <span data-ttu-id="7eace-219">已修正如果回復到先前的組建，Word、Powerpoint 和 Excel 無法開啟雲端文件的問題</span><span class="sxs-lookup"><span data-stu-id="7eace-219">Fix an issue Word, Powerpoint and Excel would fail to open cloud document if rolling back to a previous build</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2103-may-11"></a><span data-ttu-id="7eace-221">版本 2103：5 月 11 日</span><span class="sxs-lookup"><span data-stu-id="7eace-221">Version 2103: May 11</span></span>
<span data-ttu-id="7eace-222">*版本 2103 (組建 13901.20516)*</span><span class="sxs-lookup"><span data-stu-id="7eace-222">*Version 2103 (Build 13901.20516)*</span></span>

<span data-ttu-id="7eace-223">安全性更新列於[此處](microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="7eace-223">Security updates listed [here](microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="7eace-225">功能更新</span><span class="sxs-lookup"><span data-stu-id="7eace-225">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="7eace-226">Excel</span><span class="sxs-lookup"><span data-stu-id="7eace-226">Excel</span></span>

- <span data-ttu-id="7eace-227">**自動使用新的資料類型**：當您輸入的資料值類似股票或地理位置時，Excel 會將該值轉換為正確的連結資料類型 - 股票或地理位置。</span><span class="sxs-lookup"><span data-stu-id="7eace-227">**Automatically use new data types:** When you type a data value that resembles a stock or a geographic location, Excel offers to convert it to the right connected data type - Stocks or Geography.</span></span> [<span data-ttu-id="7eace-228">深入了解</span><span class="sxs-lookup"><span data-stu-id="7eace-228">Learn more</span></span>](https://support.office.com/article/61a33056-9935-484f-8ac8-f1a89e210877)

- <span data-ttu-id="7eace-229">**連結資料類型：實際生活中的真實資料：** 新的連結資料類型會提供有關數百個主題的事實和資料，幫助您直接在 Excel 中達成目標。</span><span class="sxs-lookup"><span data-stu-id="7eace-229">**Linked data types: Real data for real life:** New linked data types bring you facts and data on hundreds of subjects to help you accomplish your goals right in Excel.</span></span>

### <a name="outlook"></a><span data-ttu-id="7eace-230">Outlook</span><span class="sxs-lookup"><span data-stu-id="7eace-230">Outlook</span></span>

- <span data-ttu-id="7eace-231">**使用內建翻譯工具打破語言障礙：** 不再需要翻譯的增益集！</span><span class="sxs-lookup"><span data-stu-id="7eace-231">**Break the language barrier with a built-in translator:** Add-ins for translation aren't required anymore!</span></span> <span data-ttu-id="7eace-232">您現在可以在 Outlook 中使用 Intelligent Translator。</span><span class="sxs-lookup"><span data-stu-id="7eace-232">You can now use the Intelligent Translator in Outlook.</span></span> <span data-ttu-id="7eace-233">當您收到另一種語言的郵件時，郵件上會顯示提示，詢問您是否希望 Outlook 將它翻譯為您的預設語言。</span><span class="sxs-lookup"><span data-stu-id="7eace-233">When you receive a message in another language, a prompt will appear on top of the message asking if you’d like Outlook to translate it to your default language.</span></span>
<span data-ttu-id="7eace-234">您也可以按一下滑鼠右鍵以翻譯特定的文字、片語或整個郵件。</span><span class="sxs-lookup"><span data-stu-id="7eace-234">You can also right-click to translate specific words, phrases, or the whole message.</span></span> [<span data-ttu-id="7eace-235">深入了解</span><span class="sxs-lookup"><span data-stu-id="7eace-235">Learn more</span></span>](https://support.office.com/article/287380e4-a56c-48a1-9977-f2dca89ce93f)

### <a name="visio"></a><span data-ttu-id="7eace-236">Visio</span><span class="sxs-lookup"><span data-stu-id="7eace-236">Visio</span></span>

- <span data-ttu-id="7eace-237">**圖表的現成圖形**：從可新增至 Visio 繪圖中的圖示、相片庫影像、人像紙板和圖戳的大型文件庫中進行選擇。</span><span class="sxs-lookup"><span data-stu-id="7eace-237">**Ready-made graphics for your diagrams:** Choose from a large library of icons, stock photo images, cutout people, and stickers that you can add to your Visio drawings.</span></span> [<span data-ttu-id="7eace-238">深入了解</span><span class="sxs-lookup"><span data-stu-id="7eace-238">Learn more</span></span>](https://support.office.com/article/0ab844a5-289b-47f2-ba92-eeda168bc381)<br /><span data-ttu-id="7eace-239">在[部落格文章](https://insider.office.com/zh-TW/blog/access-illustrations-icons-in-visio)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="7eace-239">See details in [blog post](https://insider.office.com/zh-TW/blog/access-illustrations-icons-in-visio)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="7eace-242">解決的問題</span><span class="sxs-lookup"><span data-stu-id="7eace-242">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="7eace-243">Access</span><span class="sxs-lookup"><span data-stu-id="7eace-243">Access</span></span>

- <span data-ttu-id="7eace-244">我們已修正當外部應用程式要求協助工具介面時，它會防止我們關機，直到它們釋出其參考為止的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-244">We fixed an issue when an external application requests an accessibility interface, it will prevent us from shutting down until they release their reference.</span></span>


- <span data-ttu-id="7eace-245">此變更可修正在某些情況下，執行 SQL Server 傳遞查詢時，可能會導致錯誤訊息指出「無效的 Cursor 狀態」的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-245">This change fixes an issue where in some cases running a SQL Server pass through query could result in an error message indicating that there was an "invalid cursor state".</span></span>


### <a name="excel"></a><span data-ttu-id="7eace-246">Excel</span><span class="sxs-lookup"><span data-stu-id="7eace-246">Excel</span></span>

- <span data-ttu-id="7eace-247">我們已修正在使用增益集時，會導致某些語言的日期格式顯示不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-247">We fixed an issue that caused date formatting to be displayed incorrectly in some languages when using add-ins.</span></span>


- <span data-ttu-id="7eace-248">修正流量分析工具箱增益集對某些使用者無法運作的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-248">Fixed an issue where the Analysis ToolPak add-in did not work for some users.</span></span>


- <span data-ttu-id="7eace-249">修正在繪製影像時 Word 中可能會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-249">Fixed a potential hang in Word when drawing an image.</span></span>


### <a name="outlook"></a><span data-ttu-id="7eace-250">Outlook</span><span class="sxs-lookup"><span data-stu-id="7eace-250">Outlook</span></span>

- <span data-ttu-id="7eace-251">我們已修正在代表另一個使用者進行傳送，並且針對非全域通訊清單的通訊錄進行解析時，造成名稱解析失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-251">We fixed an issue that caused name resolution to fail when sending on behalf of another user and resolving against an address book that is not the Global Address List.</span></span>


- <span data-ttu-id="7eace-252">我們已修正會導致 Outlook 覆寫 OWA 中已設定的焦點收件匣喜好設定的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-252">We fixed an issue that caused Outlook to override the Focused Inbox preferences configured in OWA.</span></span>


- <span data-ttu-id="7eace-253">我們已修正會導致部分使用者無法存取與次要郵件帳戶相關聯簽章的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-253">We fixed an issue that caused some people to be unable to access signatures associated with secondary mail accounts.</span></span>


- <span data-ttu-id="7eace-254">我們已修正會導致使用者看到較預期更多簽章的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-254">We fixed an issue that caused users to see more signatures than expected.</span></span>


- <span data-ttu-id="7eace-255">我們已修正會導致某些使用者在功能窗格中看到主要和次要行事曆切換位置的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-255">We fixed an issue that caused some users to see their primary and secondary calendar switching places in the Navigation Pane.</span></span>


- <span data-ttu-id="7eace-256">我們已修正會導致使用者在新增行事曆時，錯誤地看到「這可能需要一些時間」訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-256">We fixed an issue that cause users to erroneously see a "This may take a while" message when adding a calendar.</span></span>


- <span data-ttu-id="7eace-257">我們已修正會導致代理人在新增的行事曆上所建立的會議中顯示為召集人的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-257">We fixed an issue that caused delegates to appear as the organizer of meetings created on newly added calendars.</span></span>  <span data-ttu-id="7eace-258">處於此狀態的會議不會出現在主體的行事曆上。</span><span class="sxs-lookup"><span data-stu-id="7eace-258">Meetings in this state did not appear on the principal's calendar.</span></span>


- <span data-ttu-id="7eace-259">我們已修正啟用 MAPI 的應用程式在具有 ARM 處理器的電腦上使用 Outlook 元件的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-259">We fixed an issue in a component of Outlook that is used by MAPI-enabled applications on computers with ARM processors.</span></span> <span data-ttu-id="7eace-260">此問題可能導致搜尋失敗，或因為背景應用程式重複重新啟動而造成電腦上額外的負載。</span><span class="sxs-lookup"><span data-stu-id="7eace-260">The issue could cause search to fail or cause extra load on the computer as background apps restarted repeatedly.</span></span>


- <span data-ttu-id="7eace-261">我們已修正會導致某些使用者在同步處理資料夾階層變更時遇到 Outlook 意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-261">We fixed an issue that caused some users to experience Outlook to close unexpectedly when syncing folder hierarchy changes.</span></span>


- <span data-ttu-id="7eace-262">修正在繪製影像時 Word 中可能會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-262">Fixed a potential hang in Word when drawing an image.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="7eace-263">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7eace-263">PowerPoint</span></span>

- <span data-ttu-id="7eace-264">我們已修正與連結圖片相關的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-264">We fixed an issue related to linked pictures.</span></span>


- <span data-ttu-id="7eace-265">修正在繪製影像時 Word 中可能會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-265">Fixed a potential hang in Word when drawing an image.</span></span>


### <a name="project"></a><span data-ttu-id="7eace-266">Project</span><span class="sxs-lookup"><span data-stu-id="7eace-266">Project</span></span>

- <span data-ttu-id="7eace-267">修正 Visio 在關閉期間可能會停止運作的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-267">Fixed an issue where Visio could stop working during close.</span></span>


### <a name="visio"></a><span data-ttu-id="7eace-268">Visio</span><span class="sxs-lookup"><span data-stu-id="7eace-268">Visio</span></span>

- <span data-ttu-id="7eace-269">修正 Visio 在關閉期間可能會停止運作的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-269">Fixed an issue where Visio could stop working during close.</span></span>


### <a name="word"></a><span data-ttu-id="7eace-270">Word</span><span class="sxs-lookup"><span data-stu-id="7eace-270">Word</span></span>

- <span data-ttu-id="7eace-271">修正將提供文字預測情況最佳化的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-271">Fixed an issue to optimizes conditions for text predictions to be offered.</span></span>


- <span data-ttu-id="7eace-272">修正對儲存在本機檔案上的自動儲存圖說文字進行更新的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-272">Fixed an issue where updates text on autosave callout for files saved locally.</span></span>


- <span data-ttu-id="7eace-273">修正共同撰寫文件時，若註解順序變更，則不會清除作用中草稿的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-273">Fixed an issue when coauthoring a document, active draft is not cleared when comment order changes.</span></span>


- <span data-ttu-id="7eace-274">修正預覽列印會意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-274">Fixes an issue where Print preview closed unexpectedly.</span></span>


- <span data-ttu-id="7eace-275">修正在繪製影像時 Word 中可能會當機的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-275">Fixed a potential hang in Word when drawing an image.</span></span>



### <a name="office-suite"></a><span data-ttu-id="7eace-276">Office 套件</span><span class="sxs-lookup"><span data-stu-id="7eace-276">Office Suite</span></span>

- <span data-ttu-id="7eace-277">修正與支援在工作階段 0 中執行的 Office 應用程式相關的可靠性問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-277">Fixes a reliability issue related to support of Office apps running in session 0.</span></span>


- <span data-ttu-id="7eace-278">修正離線開啟 SyncBacked 檔案，然後於儲存檔案之前，在應用程式中重新命名檔案時，重新命名會停止回應的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-278">Fixed an issue which rename was unresponsive when opened a SyncBacked file offline then renamed the file in app before saving file.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2102-may-11"></a><span data-ttu-id="7eace-280">版本 2102：5 月 11 日</span><span class="sxs-lookup"><span data-stu-id="7eace-280">Version 2102: May 11</span></span>
<span data-ttu-id="7eace-281">*版本 2102 (組建 13801.20638)*</span><span class="sxs-lookup"><span data-stu-id="7eace-281">*Version 2102 (Build 13801.20638)*</span></span>

<span data-ttu-id="7eace-282">安全性更新列於[此處](microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="7eace-282">Security updates listed [here](microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="7eace-284">解決的問題</span><span class="sxs-lookup"><span data-stu-id="7eace-284">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="7eace-285">Excel</span><span class="sxs-lookup"><span data-stu-id="7eace-285">Excel</span></span>

- <span data-ttu-id="7eace-286">我們已修正在使用增益集時，會導致某些語言的日期格式顯示不正確的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-286">We fixed an issue that caused date formatting to be displayed incorrectly on some languages when using Add-ins.</span></span>


- <span data-ttu-id="7eace-287">我們已修正會導致無法以公式形式貼上到受保護工作表的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-287">We fixed an issue that was preventing the ability to paste as formulas on a protected sheet.</span></span>


### <a name="outlook"></a><span data-ttu-id="7eace-288">Outlook</span><span class="sxs-lookup"><span data-stu-id="7eace-288">Outlook</span></span>

- <span data-ttu-id="7eace-289">這可讓使用者設定 Outlook 以將線上會議新增至他們建立的每一個會議。</span><span class="sxs-lookup"><span data-stu-id="7eace-289">This enables end users to configure Outlook to add an online meeting to every meeting they create.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="7eace-290">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7eace-290">PowerPoint</span></span>

- <span data-ttu-id="7eace-291">我們已修正與連結圖片相關的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-291">We fixed an issue related to linked pictures.</span></span>


### <a name="word"></a><span data-ttu-id="7eace-292">Word</span><span class="sxs-lookup"><span data-stu-id="7eace-292">Word</span></span>

- <span data-ttu-id="7eace-293">修正 Wordmail 中當連結的第 2084 個字元是逸出字元時，某人無法傳送此項目的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-293">Fixes an issue in Wordmail where someone cannot send this item' when the 2084th character in a link is an escaped character.</span></span>


### <a name="office-suite"></a><span data-ttu-id="7eace-294">Office 套件</span><span class="sxs-lookup"><span data-stu-id="7eace-294">Office Suite</span></span>

- <span data-ttu-id="7eace-295">修正會導致 Word 在列印長篇文件時意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-295">Fixed an issue that caused Word to close unexpectedly while printing long documents.</span></span>


- <span data-ttu-id="7eace-296">在此變更之前，即使已開啟用於停用 Office 範本的 GPO，Office 範本還是會顯示。</span><span class="sxs-lookup"><span data-stu-id="7eace-296">Before this change, Office templates were displaying even if GPO for disabling them was turned on.</span></span> <span data-ttu-id="7eace-297">利用此變更，範本現在會正確地遵循 GPO，並按要求顯示/隱藏。</span><span class="sxs-lookup"><span data-stu-id="7eace-297">With this change, templates now honor the GPO correctly and display/hide as requested.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2102-april-13"></a><span data-ttu-id="7eace-299">版本 2102：4 月 13 日</span><span class="sxs-lookup"><span data-stu-id="7eace-299">Version 2102: April 13</span></span>
<span data-ttu-id="7eace-300">*版本 2102 (組建 13801.20506)*</span><span class="sxs-lookup"><span data-stu-id="7eace-300">*Version 2102 (Build 13801.20506)*</span></span>

<span data-ttu-id="7eace-301">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="7eace-301">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="7eace-303">功能更新</span><span class="sxs-lookup"><span data-stu-id="7eace-303">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="7eace-304">Excel</span><span class="sxs-lookup"><span data-stu-id="7eace-304">Excel</span></span>

- <span data-ttu-id="7eace-305">**使用 [進階對話方塊] 來 [建立資料類型]:** [進階對話方塊] 可讓您手動選取合併您正在建立的 [資料類型] 欄位。</span><span class="sxs-lookup"><span data-stu-id="7eace-305">**Use the Advanced Dialog to Create Data Types:** The Advanced Dialog allows you to manually select the columns which combine the Data Type you are creating.</span></span>

- <span data-ttu-id="7eace-306">**同時取消隱藏多個工作表：** 不再需要一次取消隱藏一個工作表，可以一次取消隱藏多個隱藏的工作表。</span><span class="sxs-lookup"><span data-stu-id="7eace-306">**Unhide many sheets at the same time:** No need to unhide one sheet at a time anymore -- unhide multiple hidden sheets at once.</span></span> [<span data-ttu-id="7eace-307">深入了解</span><span class="sxs-lookup"><span data-stu-id="7eace-307">Learn more</span></span>](https://support.office.com/article/69f2701a-21f5-4186-87d7-341a8cf53344)


### <a name="outlook"></a><span data-ttu-id="7eace-308">Outlook</span><span class="sxs-lookup"><span data-stu-id="7eace-308">Outlook</span></span>

- <span data-ttu-id="7eace-309">**焦點收件匣設定在不同裝置之間會保持相同：** 您的焦點收件匣喜好設定現在會儲存在雲端。</span><span class="sxs-lookup"><span data-stu-id="7eace-309">**Focused Inbox settings remain the same across devices:** Your Focused Inbox preferences are now stored in the cloud.</span></span> <span data-ttu-id="7eace-310">這麼一來，當您在任何電腦上使用 Windows 版 Outlook 和 Outlook 網頁版時便可享有相同的體驗。</span><span class="sxs-lookup"><span data-stu-id="7eace-310">Enjoy the same experience when you use Outlook for Windows on any computer and Outlook on the web.</span></span> [<span data-ttu-id="7eace-311">深入了解</span><span class="sxs-lookup"><span data-stu-id="7eace-311">Learn more</span></span>](https://support.office.com/article/d77a442e-a86c-4bf8-b3dd-5571ae556986)

- <span data-ttu-id="7eace-312">**雲端中的 Outlook 設定：** 選擇您的 Windows 版 Outlook 設定，例如自動回復、焦點收件匣和隱私權，並在任何電腦上使用這些功能。</span><span class="sxs-lookup"><span data-stu-id="7eace-312">**Your Outlook settings in the cloud:** Choose your Outlook for Windows settings like Automatic Replies, Focused Inbox, and Privacy, and get to them on any PC.</span></span>

- <span data-ttu-id="7eace-313">**挑選搜尋的位置：** 新的搜尋範圍下拉式清單，可讓您更輕鬆地修改搜尋，並在目前資料夾和目前信箱之間切換。</span><span class="sxs-lookup"><span data-stu-id="7eace-313">**Pick where to search:** The new search scope drop down allows you to more easily modify your search and switch between Current Folder and Current Mailbox.</span></span> <span data-ttu-id="7eace-314">感謝每個在 [即將推出] 為 [頂極體驗] 的 新 [搜尋] 提供意見反應的人。</span><span class="sxs-lookup"><span data-stu-id="7eace-314">Thank you to everyone in Coming Soon who provided feedback on the new Search at Top experience.</span></span> <span data-ttu-id="7eace-315">因為有這份意見反應，才有這項設計與更新！</span><span class="sxs-lookup"><span data-stu-id="7eace-315">This design and update came out of that feedback!</span></span>

- <span data-ttu-id="7eace-316">**使用語音草擬郵件：** 使用新的聽寫工具列、語音命令、自動標點符號等功能來撰寫郵件。</span><span class="sxs-lookup"><span data-stu-id="7eace-316">**Draft messages with your voice:** Use the new dictation toolbar, voice commands, auto-punctuation, and more to compose messages.</span></span>

### <a name="word"></a><span data-ttu-id="7eace-317">Word</span><span class="sxs-lookup"><span data-stu-id="7eace-317">Word</span></span>

- <span data-ttu-id="7eace-318">**使用語音草擬文件：** 使用新的聽寫工具列、語音命令、自動標點符號等功能來草擬文件。</span><span class="sxs-lookup"><span data-stu-id="7eace-318">**Draft documents with your voice:** Use the new dictation toolbar, voice commands and auto-punctuation to draft documents.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="7eace-321">解決的問題</span><span class="sxs-lookup"><span data-stu-id="7eace-321">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="7eace-322">Access</span><span class="sxs-lookup"><span data-stu-id="7eace-322">Access</span></span>

- <span data-ttu-id="7eace-323">修正在某些情況下，執行 SQL Server 傳遞查詢時，可能會導致錯誤訊息指出「無效的 Cursor 狀態」的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-323">Fixed an issue where in some cases running a SQL Server pass through query could result in an error message indicating that there was an "invalid cursor state".</span></span>



### <a name="excel"></a><span data-ttu-id="7eace-324">Excel</span><span class="sxs-lookup"><span data-stu-id="7eace-324">Excel</span></span>

- <span data-ttu-id="7eace-325">我們已修正將資料列新增至另一個工作表上的表格後，可能會非預期地對儲存格套用資料驗證的錯誤。</span><span class="sxs-lookup"><span data-stu-id="7eace-325">We fixed a bug in which data validation could be applied to cells unexpectedly after adding rows to a table on another sheet.</span></span>


- <span data-ttu-id="7eace-326">我們已修正 DialogSheets show 函數在 32 位元版本的 Excel 上無法運作的問題</span><span class="sxs-lookup"><span data-stu-id="7eace-326">We fixed an issue where the DialogSheets show function was not working on 32 bit versions of Excel</span></span>


- <span data-ttu-id="7eace-327">我們已修正使用 [貼上連結圖片] 選項時，會導致影像小於預期的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-327">We fixed an issue which caused images to be smaller than expected when using the Paste Linked Picture option.</span></span>


- <span data-ttu-id="7eace-328">我們已修正在儲存為 .xls 或 .xlt 格式時，會導致某些樞紐分析表格式損壞活頁簿的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-328">We fixed an issue that caused some PivotTable formatting to corrupt the workbook when saving to the .xls or .xlt format.</span></span>


- <span data-ttu-id="7eace-329">我們已修正會導致使用者無法將 Excel 活頁簿匯出至 PDF 的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-329">We fixed an issue that prevented users from exporting an Excel workbook to PDF.</span></span>


- <span data-ttu-id="7eace-330">修正 Office 功能區中已停用的命令，在深灰色 Office 佈景主題中只會使圖示而非文字呈現灰色的錯誤。</span><span class="sxs-lookup"><span data-stu-id="7eace-330">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


### <a name="outlook"></a><span data-ttu-id="7eace-331">Outlook</span><span class="sxs-lookup"><span data-stu-id="7eace-331">Outlook</span></span>

- <span data-ttu-id="7eace-332">我們已修正會導致內嵌翻譯的使用者無法提交意見反應的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-332">We fixed an issue that caused users of inline translation to be unable to submit feedback.</span></span>


- <span data-ttu-id="7eace-333">我們已修正會導致使用者看到包含 Unicode 內容的簽章損毀的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-333">We fixed an issue that caused users to see signatures containing unicode content to get damaged.</span></span>


- <span data-ttu-id="7eace-334">我們已修正會導致使用者看到較預期更多的簽章的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-334">We fixed an issue that caused users to see more signatures than expected.</span></span>


- <span data-ttu-id="7eace-335">我們已修正會導致 Outlook 在閒置時當機的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-335">We fixed an issue that caused Outlook to crash when idle.</span></span>


- <span data-ttu-id="7eace-336">我們已修正會導致某些使用者在關閉訊息視窗時遇到應用程式關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-336">We fixed an issue that  caused some users to experience the app to shut down when closing message windows.</span></span>


- <span data-ttu-id="7eace-337">我們已修正會導致共用行事曆改良功能的使用者無法將行事曆的色彩設定為黃色或褐色的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-337">We fixed an issue that caused users of the Shared Calendar improvements to be unable to set a calendar's color to yellow or brown.</span></span>


- <span data-ttu-id="7eace-338">我們已修正會導致使用者在建立新群組後看到重複的行事曆群組的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-338">We fixed and issue that caused users to see duplicate calendar groups appearing after creating a new group.</span></span>


- <span data-ttu-id="7eace-339">我們已修正會導致使用者在 Outlook 重新啟動之前，在功能窗格中看不到新增的行事曆顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-339">We fixed an issue that caused users to see newly added calendars fail to appear in the navigation pane until after Outlook had been restarted.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="7eace-340">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7eace-340">PowerPoint</span></span>

- <span data-ttu-id="7eace-341">修正 Office 功能區中已停用的命令，在深灰色 Office 佈景主題中只會使圖示而非文字呈現灰色的錯誤。</span><span class="sxs-lookup"><span data-stu-id="7eace-341">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


### <a name="word"></a><span data-ttu-id="7eace-342">Word</span><span class="sxs-lookup"><span data-stu-id="7eace-342">Word</span></span>

- <span data-ttu-id="7eace-343">我們已修正共同撰寫時衝突的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-343">We fixed an issue in resolving conflicts while in coauthoring.</span></span>


- <span data-ttu-id="7eace-344">我們已修正 RTF 內容控制項的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-344">We fixed an issue with Rich text content controls.</span></span>


- <span data-ttu-id="7eace-345">我們已修正在隱藏段落結尾輸入可能會導致應用程式懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-345">We fixed an issue with typing at the end of a hidden paragraph may result in application hang.</span></span>


- <span data-ttu-id="7eace-346">我們已修正可能會略過段落的朗讀程式問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-346">We fixed an issue with Narrator which may skips over a paragraph.</span></span>


- <span data-ttu-id="7eace-347">我們已修正有關複製和貼上的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-347">We fixed an issue relating to copy and paste.</span></span>


- <span data-ttu-id="7eace-348">修正對具有 3D 效果的圖示和 SVG 圖形套用色彩的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-348">Fixes an issue with colors applied to icons and SVG graphics with 3D effects.</span></span>


- <span data-ttu-id="7eace-349">修正 Office 功能區中已停用的命令，在深灰色 Office 佈景主題中只會使圖示而非文字呈現灰色的錯誤。</span><span class="sxs-lookup"><span data-stu-id="7eace-349">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


### <a name="office-suite"></a><span data-ttu-id="7eace-350">Office 套件</span><span class="sxs-lookup"><span data-stu-id="7eace-350">Office Suite</span></span>

- <span data-ttu-id="7eace-351">我們已修正與支援在工作階段 0 中執行的 Office 應用程式相關的可靠性問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-351">We fixed a reliability issue related to support of Office apps running in session 0.</span></span>


- <span data-ttu-id="7eace-352">修正有時可能會導致 Outlook 中的文字變得透明，因而無法辨認的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-352">Fixed an issue that could sometimes lead to text in Outlook becoming transparent and thereby not legible.</span></span>


- <span data-ttu-id="7eace-353">修正在包含數學方程式的文字內使用朗讀程式時可能發生的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-353">Fixed an issue that could happen when using narrator within text that contains math equations.</span></span>


- <span data-ttu-id="7eace-354">修正針對使用者停用 GCC 聽寫的問題</span><span class="sxs-lookup"><span data-stu-id="7eace-354">Fixed an issue where Dictation was disabled for GCC users</span></span>


- <span data-ttu-id="7eace-355">修正使用者在開啟先前開啟的檔案具有未儲存的編輯但現在檔案已遭到刪除時，無法儲存檔案的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-355">Fixed an issue where users are unable to save file when open a previously opened file with edits not saved but now the file has been deleted.</span></span> <span data-ttu-id="7eace-356">修正之後，使用者將會收到一則友善的訊息，通知他們已刪除該檔案，因此使用者可以選擇捨棄變更，或將檔案另存為新檔。</span><span class="sxs-lookup"><span data-stu-id="7eace-356">After the fix, users will get a friendly message to inform them that the file is deleted, thus user can choose to discard changes, or SaveAs the file.</span></span>


- <span data-ttu-id="7eace-357">修正離線開啟 SyncBacked 檔案，然後於儲存檔案之前，在應用程式中重新命名檔案時重新命名失敗的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-357">Fixed rename failure issue when open a SyncBacked file offline then rename the file in app before saving file.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2101-april-13"></a><span data-ttu-id="7eace-359">版本 2101：4 月 13 日</span><span class="sxs-lookup"><span data-stu-id="7eace-359">Version 2101: April 13</span></span>
<span data-ttu-id="7eace-360">*版本 2101 (組建 13628.20664)*</span><span class="sxs-lookup"><span data-stu-id="7eace-360">*Version 2101 (Build 13628.20664)*</span></span>

<span data-ttu-id="7eace-361">安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="7eace-361">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2101-march-09"></a><span data-ttu-id="7eace-362">版本 2101：3 月 9 日</span><span class="sxs-lookup"><span data-stu-id="7eace-362">Version 2101: March 09</span></span>
<span data-ttu-id="7eace-363">*版本 2101 (組建 13628.20528)*</span><span class="sxs-lookup"><span data-stu-id="7eace-363">*Version 2101 (Build 13628.20528)*</span></span>

<span data-ttu-id="7eace-364">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="7eace-364">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="7eace-366">解決的問題</span><span class="sxs-lookup"><span data-stu-id="7eace-366">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="7eace-367">Excel</span><span class="sxs-lookup"><span data-stu-id="7eace-367">Excel</span></span>

- <span data-ttu-id="7eace-368">修正當使用特定 Windows 安全性漏洞防護設定(SimExec、CallerCheck) 時，Excel 無法正常啟動或關閉的問題</span><span class="sxs-lookup"><span data-stu-id="7eace-368">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use</span></span>


### <a name="outlook"></a><span data-ttu-id="7eace-369">Outlook</span><span class="sxs-lookup"><span data-stu-id="7eace-369">Outlook</span></span>

- <span data-ttu-id="7eace-370">我們已修正會導致加密圖示無法對使用僅加密選項傳送的電子郵件顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-370">We fixed an issue that caused the encryption icon to fail to display on emails sent using the encryption only option.</span></span>


- <span data-ttu-id="7eace-371">我們已修正會導致在使用者取消選取數位簽章選項之後，仍以數位簽章方式傳送郵件的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-371">We fixed an issue that caused mails to be sent as digitally signed after the user unchecked that option.</span></span>


- <span data-ttu-id="7eace-372">我們已修正會導致在 OWA 中顯示正確的預設簽章時發生問題的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-372">We fixed an issue that caused issues with displaying the correct default signature in OWA.</span></span>


- <span data-ttu-id="7eace-373">我們已修正會導致雲端設定使用者在更新設定時遇到懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-373">We fixed an issue that caused Cloud Settings users to experience a hang when updating settings.</span></span>


- <span data-ttu-id="7eace-374">我們已修正使用者在 Outlook 中進行搜尋時，有時候會導致應用程式未預期關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-374">We fixed an issue that caused the app to sometimes close unexpectedly when users were searching in Outlook.</span></span>


- <span data-ttu-id="7eace-375">我們已修正會導致在其設定檔中具有大型階層的共用或委派信箱的使用者遇到懸置的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-375">We fixed an issue that caused users that have Shared or Delegated Mailboxes with large hierarchies in their profile to encounter hangs.</span></span>


- <span data-ttu-id="7eace-376">我們已修正會導致某些使用者在特定搜尋案例中遇到 Outlook 未預期關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-376">We fixed an issue that caused some users to experience Outlook to close unexpectedly in certain search scenarios.</span></span>


### <a name="project"></a><span data-ttu-id="7eace-377">Project</span><span class="sxs-lookup"><span data-stu-id="7eace-377">Project</span></span>

- <span data-ttu-id="7eace-378">修正將成本資源指派給里程碑工作時，比較基準成本沒有正確彙總的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-378">Fixed an issue where when a cost resource was assigned to a milestone task, baseline cost didn't rollup correctly.</span></span>


- <span data-ttu-id="7eace-379">修正在 [團隊規劃] 檢視中工作沒有顯示邊框的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-379">Fixed an issue where borders weren't showing up for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="7eace-380">修正在 [團隊規劃] 檢視中拖放工作不起作用的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-380">Fixed an issue where you drag and drop wasn't working for tasks in the Team Planner view.</span></span>


### <a name="office-suite"></a><span data-ttu-id="7eace-381">Office 套件</span><span class="sxs-lookup"><span data-stu-id="7eace-381">Office Suite</span></span>

- <span data-ttu-id="7eace-382">修正與媒體控制器事件通知相關的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-382">Fixes an issue related to media controller event notifications.</span></span>


- <span data-ttu-id="7eace-383">修正與媒體播放程式引擎時間相關的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-383">Fixes an issue related to media player engine timing.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2012-march-09"></a><span data-ttu-id="7eace-385">版本 2012：3 月 9 日</span><span class="sxs-lookup"><span data-stu-id="7eace-385">Version 2012: March 09</span></span>
<span data-ttu-id="7eace-386">*版本 2012 (組建 13530.20628)*</span><span class="sxs-lookup"><span data-stu-id="7eace-386">*Version 2012 (Build 13530.20628)*</span></span>

<span data-ttu-id="7eace-387">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="7eace-387">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="7eace-389">功能更新</span><span class="sxs-lookup"><span data-stu-id="7eace-389">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="7eace-390">Excel</span><span class="sxs-lookup"><span data-stu-id="7eace-390">Excel</span></span>

- <span data-ttu-id="7eace-391">**要求使用者套用敏感度標籤：** 當使用者的組織原則要求時，會提示使用者套用敏感度標籤。</span><span class="sxs-lookup"><span data-stu-id="7eace-391">**Require users to apply sensitivity labels:** Users will be prompted to apply a sensitivity label if their organization's policy requires it.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7eace-392">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7eace-392">PowerPoint</span></span>

- <span data-ttu-id="7eace-393">**要求使用者套用敏感度標籤：** 當使用者的組織原則要求時，會提示使用者套用敏感度標籤。</span><span class="sxs-lookup"><span data-stu-id="7eace-393">**Require users to apply sensitivity labels:** Users will be prompted to apply a sensitivity label if their organization's policy requires it.</span></span>

### <a name="word"></a><span data-ttu-id="7eace-394">Word</span><span class="sxs-lookup"><span data-stu-id="7eace-394">Word</span></span>

- <span data-ttu-id="7eace-395">**要求使用者套用敏感度標籤：** 當使用者的組織原則要求時，會提示使用者套用敏感度標籤。</span><span class="sxs-lookup"><span data-stu-id="7eace-395">**Require users to apply sensitivity labels:** Users will be prompted to apply a sensitivity label if their organization's policy requires it.</span></span>


## <a name="version-2012-february-09"></a><span data-ttu-id="7eace-396">版本 2012：2 月 9 日</span><span class="sxs-lookup"><span data-stu-id="7eace-396">Version 2012: February 09</span></span>
<span data-ttu-id="7eace-397">*版本 2012 (組建 13530.20528)*</span><span class="sxs-lookup"><span data-stu-id="7eace-397">*Version 2012 (Build 13530.20528)*</span></span>

<span data-ttu-id="7eace-398">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="7eace-398">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="7eace-400">功能更新</span><span class="sxs-lookup"><span data-stu-id="7eace-400">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="7eace-401">Excel</span><span class="sxs-lookup"><span data-stu-id="7eace-401">Excel</span></span>

- <span data-ttu-id="7eace-402">**SVG 剪貼簿支援：** 您現在可以將 SVG 內容從 Office 貼上協力廠商應用程式。</span><span class="sxs-lookup"><span data-stu-id="7eace-402">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="7eace-403">深入了解</span><span class="sxs-lookup"><span data-stu-id="7eace-403">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- <span data-ttu-id="7eace-404">**敏感度標籤稽核記錄**：現在當使用者在文件和電子郵件上套用、變更或移除敏感度標籤時，系統就會將該資訊提供給 Microsoft 365 稽核記錄中的系統管理員使用。</span><span class="sxs-lookup"><span data-stu-id="7eace-404">**Sensitivity label audit logging:** When users apply, change, or remove sensitivity labels on their documents and emails, that information is now made available to administrators in the Microsoft 365 audit logs.</span></span>

- <span data-ttu-id="7eace-405">**政府客戶：將敏感度標籤套用至您的文件和電子郵件：** 敏感度標籤功能目前可供 GCC 和 GCC-H 環境中的客戶取得。</span><span class="sxs-lookup"><span data-stu-id="7eace-405">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="7eace-406">深入了解</span><span class="sxs-lookup"><span data-stu-id="7eace-406">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

### <a name="outlook"></a><span data-ttu-id="7eace-407">Outlook</span><span class="sxs-lookup"><span data-stu-id="7eace-407">Outlook</span></span>

- <span data-ttu-id="7eace-408">**SVG 剪貼簿支援：** 您現在可以將 SVG 內容從 Office 貼上協力廠商應用程式。</span><span class="sxs-lookup"><span data-stu-id="7eace-408">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="7eace-409">深入了解</span><span class="sxs-lookup"><span data-stu-id="7eace-409">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- <span data-ttu-id="7eace-410">**在連續會議之間置入時間：** 將會議預設為延後 5-10 分鐘開始，讓出席者有時間休息，或前往下一個地點。</span><span class="sxs-lookup"><span data-stu-id="7eace-410">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to start 5-10 min late by default.</span></span> [<span data-ttu-id="7eace-411">深入了解</span><span class="sxs-lookup"><span data-stu-id="7eace-411">Learn more</span></span>](https://support.office.com/article/ebb4c4c9-6992-4ea7-9772-8b5883df8500)

- <span data-ttu-id="7eace-412">**敏感度標籤稽核記錄**：現在當使用者在文件和電子郵件上套用、變更或移除敏感度標籤時，系統就會將該資訊提供給 Microsoft 365 稽核記錄中的系統管理員使用。</span><span class="sxs-lookup"><span data-stu-id="7eace-412">**Sensitivity label audit logging:** When users apply, change, or remove sensitivity labels on their documents and emails, that information is now made available to administrators in the Microsoft 365 audit logs.</span></span>

- <span data-ttu-id="7eace-413">**每個線上會議** 更新行事曆設定，使您建立的每個會議都預設為 Teams 會議，這樣您就不必再記得按一下 [Teams 會議] 選項。</span><span class="sxs-lookup"><span data-stu-id="7eace-413">**Every meeting online:** Update your calendar settings to make every meeting you create a Teams Meeting by default so you no longer need to remember to click the Teams Meeting option.</span></span>

- <span data-ttu-id="7eace-414">**政府客戶：將敏感度標籤套用至您的文件和電子郵件：** 敏感度標籤功能目前可供 GCC 和 GCC-H 環境中的客戶取得。</span><span class="sxs-lookup"><span data-stu-id="7eace-414">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="7eace-415">深入了解</span><span class="sxs-lookup"><span data-stu-id="7eace-415">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

- <span data-ttu-id="7eace-416">**每個線上會議** 更新行事曆設定，使您建立的每個會議都預設為 Teams 會議，這樣您就不必再記得按一下 [Teams 會議] 選項。</span><span class="sxs-lookup"><span data-stu-id="7eace-416">**Every meeting online:** Update your calendar settings to make every meeting you create a Teams Meeting by default so you no longer need to remember to click the Teams Meeting option.</span></span>

- <span data-ttu-id="7eace-417">**新的會議室尋找工具：** 依不同功能搜尋會議室。</span><span class="sxs-lookup"><span data-stu-id="7eace-417">**New room finder:** Search for conference rooms by different capabilities.</span></span>

- <span data-ttu-id="7eace-418">**新的會議室和工作區預約體驗：** 會議室預約體驗已更新，透過它我們新增了功能，以讓您也能夠排程個別工作區</span><span class="sxs-lookup"><span data-stu-id="7eace-418">**New conference room and workspace booking experience:** The conference room booking experience has been refreshed, and with it we've added capabilities to allow you to schedule individual workspaces as well</span></span>


### <a name="powerpoint"></a><span data-ttu-id="7eace-419">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7eace-419">PowerPoint</span></span>

- <span data-ttu-id="7eace-420">**SVG 剪貼簿支援：** 您現在可以將 SVG 內容從 Office 貼上協力廠商應用程式。</span><span class="sxs-lookup"><span data-stu-id="7eace-420">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="7eace-421">深入了解</span><span class="sxs-lookup"><span data-stu-id="7eace-421">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)<br /><span data-ttu-id="7eace-422">在[部落格文章](https://insider.office.com/zh-TW/blog/svg-content-office-third-party-apps)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="7eace-422">See details in [blog post](https://insider.office.com/zh-TW/blog/svg-content-office-third-party-apps)</span></span>

- <span data-ttu-id="7eace-423">**敏感度標籤稽核記錄**：現在當使用者在文件和電子郵件上套用、變更或移除敏感度標籤時，系統就會將該資訊提供給 Microsoft 365 稽核記錄中的系統管理員使用。</span><span class="sxs-lookup"><span data-stu-id="7eace-423">**Sensitivity label audit logging:** When users apply, change, or remove sensitivity labels on their documents and emails, that information is now made available to administrators in the Microsoft 365 audit logs.</span></span>

- <span data-ttu-id="7eace-424">**政府客戶：將敏感度標籤套用至您的文件和電子郵件：** 敏感度標籤功能目前可供 GCC 和 GCC-H 環境中的客戶取得。</span><span class="sxs-lookup"><span data-stu-id="7eace-424">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="7eace-425">深入了解</span><span class="sxs-lookup"><span data-stu-id="7eace-425">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

### <a name="visio"></a><span data-ttu-id="7eace-426">Visio</span><span class="sxs-lookup"><span data-stu-id="7eace-426">Visio</span></span>

- <span data-ttu-id="7eace-427">**新 Azure 樣板和圖案：** 我們新增了更多的樣板來協助您建立最新的 Azure 圖表。</span><span class="sxs-lookup"><span data-stu-id="7eace-427">**New Azure stencils and shapes:** We've added many more stencils to help you create up-to-date Azure diagrams.</span></span> [<span data-ttu-id="7eace-428">深入了解</span><span class="sxs-lookup"><span data-stu-id="7eace-428">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

### <a name="word"></a><span data-ttu-id="7eace-429">Word</span><span class="sxs-lookup"><span data-stu-id="7eace-429">Word</span></span>

- <span data-ttu-id="7eace-430">**SVG 剪貼簿支援：** 您現在可以將 SVG 內容從 Office 貼上協力廠商應用程式。</span><span class="sxs-lookup"><span data-stu-id="7eace-430">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="7eace-431">深入了解</span><span class="sxs-lookup"><span data-stu-id="7eace-431">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- <span data-ttu-id="7eace-432">**敏感度標籤稽核記錄**：現在當使用者在文件和電子郵件上套用、變更或移除敏感度標籤時，系統就會將該資訊提供給 Microsoft 365 稽核記錄中的系統管理員使用。</span><span class="sxs-lookup"><span data-stu-id="7eace-432">**Sensitivity label audit logging:** When users apply, change, or remove sensitivity labels on their documents and emails, that information is now made available to administrators in the Microsoft 365 audit logs.</span></span>

- <span data-ttu-id="7eace-433">**政府客戶：將敏感度標籤套用至您的文件和電子郵件：** 敏感度標籤功能目前可供 GCC 和 GCC-H 環境中的客戶取得。</span><span class="sxs-lookup"><span data-stu-id="7eace-433">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="7eace-434">深入了解</span><span class="sxs-lookup"><span data-stu-id="7eace-434">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="7eace-437">解決的問題</span><span class="sxs-lookup"><span data-stu-id="7eace-437">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="7eace-438">Excel</span><span class="sxs-lookup"><span data-stu-id="7eace-438">Excel</span></span>

- <span data-ttu-id="7eace-439">此變更解決了在方程式中正確顯示字型的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-439">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="7eace-440">修正當某些使用者在共同撰寫時會錯誤地看到通知他們檔案新版本的訊息列之問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-440">Fixed an issue where some users would incorrectly see a message bar informing them of a new version of a file when coauthoring.</span></span>


- <span data-ttu-id="7eace-441">修正在開啟含有 Excel 4.0 巨集的 Excel 增益集檔案時，Excel 可能會停用巨集而不提示的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-441">Fixed an issue where Excel may leave macros disabled without prompting when opening an Excel Add-in file containing Excel 4.0 Macros.</span></span>


- <span data-ttu-id="7eace-442">修正當使用特定 Windows 安全性漏洞防護設定(SimExec、CallerCheck) 時，Excel 無法正常啟動或關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-442">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use.</span></span>


- <span data-ttu-id="7eace-443">修正使用樞紐分析表的「將值顯示為」功能表時，Excel 可能會意外關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-443">Fixed an issue where Excel might close unexpectedly when using the "Show Values As" menu for a PivotTable.</span></span>


- <span data-ttu-id="7eace-444">我們已修正破壞了一些舊的 Excel 4.0 和 Excel 5.0 巨集以及一些對 dialogsheets.show 的 VBA 呼叫的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-444">We fixed an issue that broke some legacy Excel 4.0 and Excel 5.0 macros as well as some VBA calls to dialogsheets.show.</span></span>


### <a name="outlook"></a><span data-ttu-id="7eace-445">Outlook</span><span class="sxs-lookup"><span data-stu-id="7eace-445">Outlook</span></span>

- <span data-ttu-id="7eace-446">我們已修正會導致在提示使用者儲存已編輯的簽名後，該動作會無法執行的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-446">We fixed an issue that caused an edited signature to fail to save after prompting the user to do so.</span></span>


- <span data-ttu-id="7eace-447">我們已修正會導致某些使用者在特定搜尋案例中遇到 Outlook 異常關閉的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-447">We fixed an issue that caused some users to experience Outlook closing unexpectedly in certain search scenarios.</span></span>


- <span data-ttu-id="7eace-448">我們已修正會導致某些客戶在載入行事歷時遇到停滯的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-448">We fixed an issue that caused some customers to encounter a hang while loading their calendars.</span></span>


- <span data-ttu-id="7eace-449">我們修正了導致在其設定檔中具有大型階層的共用或委派信箱的使用者遇到停止回應的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-449">We fixed an issue that caused users that have Shared or Delegated Mailboxes with large hierarchies in their profile to encounter hangs.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="7eace-450">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7eace-450">PowerPoint</span></span>

- <span data-ttu-id="7eace-451">我們已修正一個問題，即在 QAT 中新增的字型大小命令在更新時，會自動完成到最接近的已定義字型大小。</span><span class="sxs-lookup"><span data-stu-id="7eace-451">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="7eace-452">此變更解決了在方程式中正確顯示字型的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-452">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="7eace-453">此變更解决對某些幾何圖形套用 [合併圖案] 作業時路徑填充的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-453">This change addresses an issue with path fills when applying Merge Shapes operations with certain geometries.</span></span>


### <a name="office-suite"></a><span data-ttu-id="7eace-454">Office 套件</span><span class="sxs-lookup"><span data-stu-id="7eace-454">Office Suite</span></span>

- <span data-ttu-id="7eace-455">Anaheim WebView 目前尚不支援 Windows 資訊保護(WIP)。</span><span class="sxs-lookup"><span data-stu-id="7eace-455">Anaheim WebView does not support Windows Information Protection (WIP) yet.</span></span> <span data-ttu-id="7eace-456">有了此修正程式，Office addin 平臺便會回到處於 WIP 啟用環境中的低層級 WebView。</span><span class="sxs-lookup"><span data-stu-id="7eace-456">With this fix Office addin platform falls back to down level WebView in WIP enabled environment.</span></span> <span data-ttu-id="7eace-457">根據客戶的電腦環境，這可以是 Edge Spartan WebView 或 Trident WebView。</span><span class="sxs-lookup"><span data-stu-id="7eace-457">That can be either Edge Spartan WebView or Trident WebView depending on customer's machine environment.</span></span> <span data-ttu-id="7eace-458">兩個低層級 WebViews 皆支援 WIP。</span><span class="sxs-lookup"><span data-stu-id="7eace-458">Both down level WebViews support WIP.</span></span>


- <span data-ttu-id="7eace-459">優化的二進位大小。</span><span class="sxs-lookup"><span data-stu-id="7eace-459">Optimized binary size.</span></span>


- <span data-ttu-id="7eace-460">修正檔案關閉順序，使所有相互依存的元件都能正常關閉。</span><span class="sxs-lookup"><span data-stu-id="7eace-460">Fixed the file closing sequence so that all the interdependent components are closed gracefully.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2011-february-09"></a><span data-ttu-id="7eace-462">版本 2011：2 月 9 日</span><span class="sxs-lookup"><span data-stu-id="7eace-462">Version 2011: February 09</span></span>
<span data-ttu-id="7eace-463">*版本 2011 (組建 13426.20658)*</span><span class="sxs-lookup"><span data-stu-id="7eace-463">*Version 2011 (Build 13426.20658)*</span></span>

<span data-ttu-id="7eace-464">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="7eace-464">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

## <a name="version-2011-january-12"></a><span data-ttu-id="7eace-465">版本 2011：1 月 12 日</span><span class="sxs-lookup"><span data-stu-id="7eace-465">Version 2011: January 12</span></span>
<span data-ttu-id="7eace-466">*版本 2011 (組建 13426.20526)*</span><span class="sxs-lookup"><span data-stu-id="7eace-466">*Version 2011 (Build 13426.20526)*</span></span>

<span data-ttu-id="7eace-467">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="7eace-467">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="7eace-469">功能更新</span><span class="sxs-lookup"><span data-stu-id="7eace-469">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="7eace-470">Access</span><span class="sxs-lookup"><span data-stu-id="7eace-470">Access</span></span>

- <span data-ttu-id="7eace-471">**自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。</span><span class="sxs-lookup"><span data-stu-id="7eace-471">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="7eace-472">移至 [檔案] > [帳戶]，然後在 [Office 佈景主題] 下拉式清單底下，選擇 [使用系統設定]。</span><span class="sxs-lookup"><span data-stu-id="7eace-472">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="7eace-473">深入了解</span><span class="sxs-lookup"><span data-stu-id="7eace-473">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="excel"></a><span data-ttu-id="7eace-474">Excel</span><span class="sxs-lookup"><span data-stu-id="7eace-474">Excel</span></span>

- <span data-ttu-id="7eace-475">**建立變數以在公式中使用：** 使用 LET 函數改善效能、可讀性及可組合性。</span><span class="sxs-lookup"><span data-stu-id="7eace-475">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="7eace-476">此函數可讓您在新的或現有的公式中建立命名變數。</span><span class="sxs-lookup"><span data-stu-id="7eace-476">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="7eace-477">深入了解</span><span class="sxs-lookup"><span data-stu-id="7eace-477">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="7eace-478">在[部落格文章](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="7eace-478">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

- <span data-ttu-id="7eace-479">**在 Power Query 中建立自訂資料類型：** 使用任何資料來源建立自訂資料類型，可讓您將多個相關資料部分載入到一個欄位。</span><span class="sxs-lookup"><span data-stu-id="7eace-479">**Create a custom data type in Power Query:** Use any data source to create a custom data type that lets you load multiple related pieces of information into one column.</span></span> [<span data-ttu-id="7eace-480">深入了解</span><span class="sxs-lookup"><span data-stu-id="7eace-480">Learn more</span></span>](https://support.office.com/article/a465a3b7-3d37-4eb1-a59c-bd3163315308)<br /><span data-ttu-id="7eace-481">在[部落格文章](https://techcommunity.microsoft.com/t5/excel-blog/announcing-power-query-data-types/ba-p/1782903)中查看詳細資料</span><span class="sxs-lookup"><span data-stu-id="7eace-481">See details in [blog post](https://techcommunity.microsoft.com/t5/excel-blog/announcing-power-query-data-types/ba-p/1782903)</span></span>

- <span data-ttu-id="7eace-482">**在來源查詢之後命名新的工作表：** 將資料載入新工作表時，會根據來源查詢的名稱來為工作表命名。</span><span class="sxs-lookup"><span data-stu-id="7eace-482">**Name the new sheet after the source query:** When the data is loaded into the new sheet, the sheet will be named based on the name of the source query.</span></span>

- <span data-ttu-id="7eace-483">**自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。</span><span class="sxs-lookup"><span data-stu-id="7eace-483">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="7eace-484">移至 [檔案] > [帳戶]，然後在 [Office 佈景主題] 下拉式清單底下，選擇 [使用系統設定]。</span><span class="sxs-lookup"><span data-stu-id="7eace-484">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="7eace-485">深入了解</span><span class="sxs-lookup"><span data-stu-id="7eace-485">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="onenote"></a><span data-ttu-id="7eace-486">OneNote</span><span class="sxs-lookup"><span data-stu-id="7eace-486">OneNote</span></span>

- <span data-ttu-id="7eace-487">**自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。</span><span class="sxs-lookup"><span data-stu-id="7eace-487">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="7eace-488">移至 [檔案] > [帳戶]，然後在 [Office 佈景主題] 下拉式清單底下，選擇 [使用系統設定]。</span><span class="sxs-lookup"><span data-stu-id="7eace-488">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="7eace-489">深入了解</span><span class="sxs-lookup"><span data-stu-id="7eace-489">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="outlook"></a><span data-ttu-id="7eace-490">Outlook</span><span class="sxs-lookup"><span data-stu-id="7eace-490">Outlook</span></span>

- <span data-ttu-id="7eace-491">**自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。</span><span class="sxs-lookup"><span data-stu-id="7eace-491">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="7eace-492">移至 [檔案] > [帳戶]，然後在 [Office 佈景主題] 下拉式清單底下，選擇 [使用系統設定]。</span><span class="sxs-lookup"><span data-stu-id="7eace-492">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="7eace-493">深入了解</span><span class="sxs-lookup"><span data-stu-id="7eace-493">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


### <a name="powerpoint"></a><span data-ttu-id="7eace-494">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7eace-494">PowerPoint</span></span>

- <span data-ttu-id="7eace-495">**影片庫：** 在應用程式內使用精選的免版稅影片素材庫來提升您的文件。</span><span class="sxs-lookup"><span data-stu-id="7eace-495">**Video Library:** Elevate your documents with a library of curated, royalty-free video footage available in-app.</span></span>

- <span data-ttu-id="7eace-496">**自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。</span><span class="sxs-lookup"><span data-stu-id="7eace-496">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="7eace-497">移至 [檔案] > [帳戶]，然後在 [Office 佈景主題] 下拉式清單底下，選擇 [使用系統設定]。</span><span class="sxs-lookup"><span data-stu-id="7eace-497">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="7eace-498">深入了解</span><span class="sxs-lookup"><span data-stu-id="7eace-498">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="project"></a><span data-ttu-id="7eace-499">Project</span><span class="sxs-lookup"><span data-stu-id="7eace-499">Project</span></span>

- <span data-ttu-id="7eace-500">**自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。</span><span class="sxs-lookup"><span data-stu-id="7eace-500">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="7eace-501">移至 [檔案] > [帳戶]，然後在 [Office 佈景主題] 下拉式清單底下，選擇 [使用系統設定]。</span><span class="sxs-lookup"><span data-stu-id="7eace-501">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="7eace-502">深入了解</span><span class="sxs-lookup"><span data-stu-id="7eace-502">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="publisher"></a><span data-ttu-id="7eace-503">Publisher</span><span class="sxs-lookup"><span data-stu-id="7eace-503">Publisher</span></span>

- <span data-ttu-id="7eace-504">**自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。</span><span class="sxs-lookup"><span data-stu-id="7eace-504">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="7eace-505">移至 [檔案] > [帳戶]，然後在 [Office 佈景主題] 下拉式清單底下，選擇 [使用系統設定]。</span><span class="sxs-lookup"><span data-stu-id="7eace-505">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="7eace-506">深入了解</span><span class="sxs-lookup"><span data-stu-id="7eace-506">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="visio"></a><span data-ttu-id="7eace-507">Visio</span><span class="sxs-lookup"><span data-stu-id="7eace-507">Visio</span></span>

- <span data-ttu-id="7eace-508">**自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。</span><span class="sxs-lookup"><span data-stu-id="7eace-508">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="7eace-509">移至 [檔案] > [帳戶]，然後在 [Office 佈景主題] 下拉式清單底下，選擇 [使用系統設定]。</span><span class="sxs-lookup"><span data-stu-id="7eace-509">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="7eace-510">深入了解</span><span class="sxs-lookup"><span data-stu-id="7eace-510">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="word"></a><span data-ttu-id="7eace-511">Word</span><span class="sxs-lookup"><span data-stu-id="7eace-511">Word</span></span>

- <span data-ttu-id="7eace-512">**自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。</span><span class="sxs-lookup"><span data-stu-id="7eace-512">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="7eace-513">移至 [檔案] > [帳戶]，然後在 [Office 佈景主題] 下拉式清單底下，選擇 [使用系統設定]。</span><span class="sxs-lookup"><span data-stu-id="7eace-513">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="7eace-514">深入了解</span><span class="sxs-lookup"><span data-stu-id="7eace-514">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="7eace-517">解決的問題</span><span class="sxs-lookup"><span data-stu-id="7eace-517">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="7eace-518">Excel</span><span class="sxs-lookup"><span data-stu-id="7eace-518">Excel</span></span>

- <span data-ttu-id="7eace-519">修正了以下問題：Excel 錯誤地顯示檔案新版本可用的訊息列，並強制使用者將變更儲存到活頁簿的副本中或捨棄變更。</span><span class="sxs-lookup"><span data-stu-id="7eace-519">Fixed an issue where Excel would incorrectly show a message bar that a new version of the file is available and force the user to save their changes in a copy of the workbook or discard their changes.</span></span>


- <span data-ttu-id="7eace-520">修正當開啟含有 Excel 4.0 巨集的 Excel 增益集檔案時，Excel 可能會在不提示的情況下停用巨集的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-520">Fixed an issue where Excel may leave macros disabled without prompting when opening an Excel Add-in file containing Excel 4.0 Macros.</span></span>


### <a name="outlook"></a><span data-ttu-id="7eace-521">Outlook</span><span class="sxs-lookup"><span data-stu-id="7eace-521">Outlook</span></span>

- <span data-ttu-id="7eace-522">我們已修正會導致某些使用者未設定一或多個簽章時，在 [簽名] 下拉式清單中看不到任何簽名的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-522">We fixed an issue that caused some users to see no signatures in the signatures drop down despite having one or more signatures configured.</span></span>


- <span data-ttu-id="7eace-523">我們新增了一個 RegKey，可讓客戶停用 IDataObject 操作 (例如，拖曳拖放、剪貼簿) 中附件的 FileTime 包含內容。</span><span class="sxs-lookup"><span data-stu-id="7eace-523">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="7eace-524">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments。</span><span class="sxs-lookup"><span data-stu-id="7eace-524">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span></span> <span data-ttu-id="7eace-525">REG_DWORD IncludeFileTimesInDataObject。</span><span class="sxs-lookup"><span data-stu-id="7eace-525">REG_DWORD IncludeFileTimesInDataObject.</span></span> <span data-ttu-id="7eace-526">0 = 不包含 filetimes。</span><span class="sxs-lookup"><span data-stu-id="7eace-526">0 = filetimes are excluded.</span></span> <span data-ttu-id="7eace-527">1 = (預設) 包含 filetimes。</span><span class="sxs-lookup"><span data-stu-id="7eace-527">1 = (default) filetimes are included.</span></span>


- <span data-ttu-id="7eace-528">修正當回覆含有「Azure 資訊保護」保護標籤的郵件時，導致內嵌影像消失的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-528">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


- <span data-ttu-id="7eace-529">我們已修正會導致 MailItem.BeforeAttachmentAdd 事件中斷的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-529">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="7eace-530">我們已修正傳送任務中的狀態報表時，導致 [收件者] 欄位為空白的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-530">We fixed an issue that caused the To field to be blank when sending a status report on a task.</span></span>


- <span data-ttu-id="7eace-531">我們已修正會導致某些會議的原始出席者在另一個出席者轉寄會議時，收到取消通知的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-531">We fixed an issue that caused the original attendees of some meetings to receive a cancellation when another attendee forwards the meeting.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="7eace-532">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7eace-532">PowerPoint</span></span>

- <span data-ttu-id="7eace-533">已修正無法正確開啟部分損壞的 PowerPoint 檔案 (即使在文件修復之後) 的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-533">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


- <span data-ttu-id="7eace-534">修正在複製含有新錄製音訊的投影片後，儲存檔案時發生錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-534">We fixed an issue where there is an error when saving the file after duplicating a slide that contains a newly recorded audio.</span></span>


- <span data-ttu-id="7eace-535">我們已修正 Slide.Shapes.AddMediaObject2 會導致舊版影片格式 (MPG-1、Mpeg-2) 發生當機的 VBA 問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-535">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 crashing with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="7eace-536">此變更解決了處理載入影片期間可能發生錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-536">This change addresses an issue with handling errors that may occur during video loading.</span></span>


- <span data-ttu-id="7eace-537">修正將方程式從 Word 複製/貼上到 PowerPoint 時發生錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-537">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


### <a name="project"></a><span data-ttu-id="7eace-538">Project</span><span class="sxs-lookup"><span data-stu-id="7eace-538">Project</span></span>

- <span data-ttu-id="7eace-539">已修正如果特定專案在負載的特定部分發生問題，可能會開啟特定專案的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-539">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>


### <a name="word"></a><span data-ttu-id="7eace-540">Word</span><span class="sxs-lookup"><span data-stu-id="7eace-540">Word</span></span>

- <span data-ttu-id="7eace-541">修復影響 Word 的最佳化閘道所暴露的宣告錯誤。</span><span class="sxs-lookup"><span data-stu-id="7eace-541">Fix an assert bug exposed by optimized gates affecting Word.</span></span>


- <span data-ttu-id="7eace-542">我們已修正文件樣式會以範本中的其他樣式取代的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-542">We fixed an issue which document styles are replaced with other styles from the template.</span></span>


- <span data-ttu-id="7eace-543">此變更解決編輯檔時游標的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-543">This change addresses an issue with the cursor when editing a document.</span></span>


- <span data-ttu-id="7eace-544">修正將方程式從 Word 複製/貼上到 PowerPoint 時發生錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-544">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


### <a name="office-suite"></a><span data-ttu-id="7eace-545">Office 套件</span><span class="sxs-lookup"><span data-stu-id="7eace-545">Office Suite</span></span>

- <span data-ttu-id="7eace-546">已修復在某些較舊的版本上安裝較新版的 Office 時，可能會造成功能受損 (例如由於遺失登錄專案而無法使用 Power Query) 的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-546">Fixed an issue where installing a newer version of Office over certain older versions can result in impaired functionality (such as being unable to use Power Query) due to missing registry entries.</span></span>


- <span data-ttu-id="7eace-547">修正當快取中的 URL 與 OneDrive 中的 URL 不相符時，檔案將被開啟為 NOT SyncBacked 的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-547">Fixed an issue of file would be opened as NOT SyncBacked when url from cache and url from OneDrive does NOT match.</span></span>


- <span data-ttu-id="7eace-548">我們已修正 SaveRequestManagerCam 導致應用程式會關閉，而非回傳錯誤的問題。</span><span class="sxs-lookup"><span data-stu-id="7eace-548">We fixed an issue where SaveRequestManagerCam was causing the application to close instead of returning an error.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2010-january-12"></a><span data-ttu-id="7eace-550">版本 2010：1 月 12 日</span><span class="sxs-lookup"><span data-stu-id="7eace-550">Version 2010: January 12</span></span>
<span data-ttu-id="7eace-551">*版本 2010 (組建 13328.20550)*</span><span class="sxs-lookup"><span data-stu-id="7eace-551">*Version 2010 (Build 13328.20550)*</span></span>

<span data-ttu-id="7eace-552">安全性更新列於[此處](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="7eace-552">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

[//]: # (DO NOT REMOVE END)

> [!NOTE]
> <span data-ttu-id="7eace-556">如果您需要關於使用 Office 的問題協助，建議您將問題張貼在 [Microsoft Answers 論壇](https://answers.microsoft.com/)或[技術社群](https://techcommunity.microsoft.com/)，或連絡[支援](https://support.microsoft.com/contactus)。</span><span class="sxs-lookup"><span data-stu-id="7eace-556">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (DO NOT MODIFY ADMIN CENTER METADATA CONTENT START)
[//]: # (|Win32|MEC|生產|功能|版本16.0.14026.20334|-2105-7-13|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13929.20408|version-2104-june-08|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13901.20516|version-2103-may-11|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13801.20506|version-2102-april-13|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13628.20528|version-2101-march-09|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13530.20528|version-2012-february-09|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13426.20526|version-2011-january-12|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13328.20478|version-2010-december-08|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13231.20514|version-2009-november-10|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13127.20638|version-2008-october-13|)
[//]: # (DO NOT MODIFY ADMIN CENTER METADATA CONTENT END)
