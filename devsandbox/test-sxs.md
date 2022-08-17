---
title: Power BI Desktop 报表中的辅助功能
description: 用于创建可访问 Power BI Desktop 报表的功能和建议
author: davidiseminger
manager: kfile
ms.reviewer: ''
ms.service: powerbi
ms.component: powerbi-desktop
ms.topic: conceptual
ms.date: 11/13/2018
ms.author: davidi
LocalizationGroup: Create reports
ms.openlocfilehash: d57d31e87197ee9d764a8d263dd4ee6dd0c75ac3
ms.sourcegitcommit: 6a6f552810a596e1000a02c8d144731ede59c0c8
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 11/14/2018
ms.locfileid: "51619623"
---
# <a name="accessibility-in-power-bi-desktop-reports"></a><span data-ttu-id="d3914-103">Power BI Desktop 报表中的辅助功能</span><span class="sxs-lookup"><span data-stu-id="d3914-103">Accessibility in Power BI Desktop reports</span></span>
<span data-ttu-id="d3914-104">Power BI 具有使残疾人士能够更轻松地使用 Power BI 报表并与之进行交互的功能。</span><span class="sxs-lookup"><span data-stu-id="d3914-104">Power BI has features that enable people with disabilities to more easily consume and interact with Power BI reports.</span></span> <span data-ttu-id="d3914-105">这些功能包括通过键盘或屏幕阅读器使用报表、通过按 Tab 键将焦点移动到页面中的各个对象以及在可视化效果中方便地使用标记。</span><span class="sxs-lookup"><span data-stu-id="d3914-105">These features include the ability to consume a report using the keyboard or a screen reader, tabbing to focus on various objects on a page, and thoughtful use of markers in visualizations.</span></span>

![在折线图和分区图中使用不同的标记来改善辅助功能](media/desktop-accessibility/accessibility_01.png)

## <a name="consuming-a-power-bi-desktop-report-with-a-keyboard-or-screen-reader"></a><span data-ttu-id="d3914-107">通过键盘或屏幕阅读器使用 Power BI Desktop 报表</span><span class="sxs-lookup"><span data-stu-id="d3914-107">Consuming a Power BI Desktop report with a keyboard or screen reader</span></span>
<span data-ttu-id="d3914-108">从 2017 年 9 月发行版 Power BI Desktop 开始，可以按 ?</span><span class="sxs-lookup"><span data-stu-id="d3914-108">Beginning with the September 2017 release of **Power BI Desktop**, you can press the **?**</span></span> <span data-ttu-id="d3914-109">键显示一个窗口，其中介绍了中可在 Power BI Desktop 中使用的辅助功能键盘快捷方式。</span><span class="sxs-lookup"><span data-stu-id="d3914-109">key to show a window that describes the accessibility keyboard shortcuts available in **Power BI Desktop**.</span></span>

![在](media/desktop-accessibility/accessibility_03.png)

<span data-ttu-id="d3914-112">借助辅助功能的增强功能，可以使用以下方法通过键盘或屏幕阅读器使用 Power BI 报表：</span><span class="sxs-lookup"><span data-stu-id="d3914-112">With the accessibility enhancements, you can consume a Power BI report with a keyboard or a screen reader with the following techniques:</span></span>

<span data-ttu-id="d3914-113">查看报表时，通常应关闭扫描模式。</span><span class="sxs-lookup"><span data-stu-id="d3914-113">When viewing a report, generally you should have scan mode off.</span></span>

<span data-ttu-id="d3914-114">可以使用 Ctrl+F6 在报表页选项卡或在给定的报表页中的对象之间切换焦点。</span><span class="sxs-lookup"><span data-stu-id="d3914-114">You can switch focus between the report page tabs, or objects on a given report page, using **Ctrl+F6**.</span></span>

* <span data-ttu-id="d3914-115">当焦点位于报表页选项卡上时，使用 Tab 或箭头键将焦点从一个报表页移到下一个报表页。</span><span class="sxs-lookup"><span data-stu-id="d3914-115">When focus is on *report page tabs*, use the *Tab* or *Arrow* keys to move focus from one report page to the next.</span></span> <span data-ttu-id="d3914-116">无论当前是否被选中，屏幕阅读器都会读出报表页的标题。</span><span class="sxs-lookup"><span data-stu-id="d3914-116">The title of the report page, and whether it is currently selected, is read out by the screen reader.</span></span> <span data-ttu-id="d3914-117">若要加载当前焦点所在的报表页，使用 Enter 或空格键。</span><span class="sxs-lookup"><span data-stu-id="d3914-117">To load the report page currently under focus, use the *Enter* or *Space* key.</span></span>
* <span data-ttu-id="d3914-118">当焦点位于已加载的报表页上时，使用 Tab 键将焦点转移到页面上的每个对象，其中包括所有文本框、图像、形状和图表。</span><span class="sxs-lookup"><span data-stu-id="d3914-118">When focus is on a loaded *report page*, use the *Tab* key to shift focus to each object on the page, which includes all textboxes, images, shapes, and charts.</span></span> <span data-ttu-id="d3914-119">屏幕阅读器可读取对象类型、对象标题（如果有）和对象说明（如果报表作者已提供）。</span><span class="sxs-lookup"><span data-stu-id="d3914-119">The screen reader reads the type of object, the object's title if it has one, and a description of that object if it's provided by the report author.</span></span> 

<span data-ttu-id="d3914-120">在视觉对象之间导航时，如果要与其进一步交互，可按 Alt+Shift+F10 将焦点移到该视觉对象标头，其中包括排序、导出图表背后的数据和焦点模式等多种选项。</span><span class="sxs-lookup"><span data-stu-id="d3914-120">As you navigate between visuals, if you want to interact with it further, you can press **Alt+Shift+F10** to move focus to the visual header, which contians various options including sorting, exporting the data behind the chart, and Focus mode.</span></span> 

![在 Power BI Desktop 中按 Alt+Shift+F10 可将焦点移到该视觉对象标头](media/desktop-accessibility/accessibility_08.png)

<span data-ttu-id="d3914-122">按 Alt+Shift+F11 可以访问“显示数据”窗口。</span><span class="sxs-lookup"><span data-stu-id="d3914-122">You can press **Alt+Shift+F11** to present an accessible version of the *Show data* window.</span></span> <span data-ttu-id="d3914-123">这使用户能够使用通常在屏幕阅读器中使用的相同键盘快捷方式来了解 HTML 表中的视觉对象中使用的数据。</span><span class="sxs-lookup"><span data-stu-id="d3914-123">This will let you explore the data used int he viusal in an HTML table, using the same keyboard shortcuts you normally use with your screen reader.</span></span> 

![在 Power BI Desktop 中按 Alt+Shift+F11 可访问视觉对象的“查看数据”窗口](media/desktop-accessibility/accessibility_04.png)

> [!NOTE]
> <span data-ttu-id="d3914-125">仅可在屏幕阅读器中通过此键盘快捷方式访问“显示数据”功能。</span><span class="sxs-lookup"><span data-stu-id="d3914-125">The Show data feature is only accessible to a screen reader through this keyboard shortcut.</span></span> <span data-ttu-id="d3914-126">如果通过视觉对象标头中的选项打开“显示数据”，屏幕阅读器将无法访问此功能。</span><span class="sxs-lookup"><span data-stu-id="d3914-126">If you open Show data through the option in the visual header, it will not be accessible to a screen reader.</span></span> <span data-ttu-id="d3914-127">使用“显示数据”时，请启用扫描模式以利用屏幕阅读器提供的所有热键。</span><span class="sxs-lookup"><span data-stu-id="d3914-127">When using Show data, turn on scan mode to take advantage of all the hot keys your screen reader provides.</span></span>

<span data-ttu-id="d3914-128">自 2018 年 7 月发布“Power BI Desktop”以来，切片器还具有内置的辅助功能。</span><span class="sxs-lookup"><span data-stu-id="d3914-128">Beginning with the July 2018 release of **Power BI Desktop**, slicers also have accessibility functionality built in.</span></span> <span data-ttu-id="d3914-129">选择切片器时，若要调整切片器的值，使用 CTRL+向右键（控制键加向右键）可移动切片器内的各种控件。</span><span class="sxs-lookup"><span data-stu-id="d3914-129">When you select a slicer, to adjust the value of a slicer use CTRL+right arrow (control plus the right arrow key) to move through the various controls within the slicer.</span></span> <span data-ttu-id="d3914-130">例如，最初按 CTRL+向右键时，焦点位于橡皮擦上，按下空格键等同于单击橡皮擦按钮，这样便可擦除切片器上的所有值。</span><span class="sxs-lookup"><span data-stu-id="d3914-130">For example, when you initially press CTRL+right arrow the focus is on the eraser, and pressing the SPACE bar is equivalent to clicking on the eraser button, which erases all values on the slicer.</span></span> 

<span data-ttu-id="d3914-131">可以通过按 TAB 键移动切片器中的控件。</span><span class="sxs-lookup"><span data-stu-id="d3914-131">You can move through the controls in a slicer by pressing the TAB key.</span></span> <span data-ttu-id="d3914-132">位于橡皮擦上时，按 TAB 键移动到下拉按钮，按另一个 TAB 则移动到第一个切片器值（如果切片器有多个值，如一个范围）。</span><span class="sxs-lookup"><span data-stu-id="d3914-132">Pressing the TAB key when on the eraser moves to the drop-down button; another TAB then moves to the first slicer value (if there are multiple values for the slicer, such as a range).</span></span> 

![在 Power BI Desktop 中按 CTRL+（向右键）可调整切片器中的要素或值，按 SPACE 可选择元素并调整其值](media/desktop-accessibility/accessibility_07.png)

<span data-ttu-id="d3914-134">这些附加辅助功能的创建目的是使用户能够通过屏幕阅读器和键盘导航充分利用 Power BI 报表。</span><span class="sxs-lookup"><span data-stu-id="d3914-134">These accessibility additions were created to let users fully consume Power BI reports using a screen reader and keyboard navigation.</span></span>

## <a name="tips-for-creating-accessible-reports"></a><span data-ttu-id="d3914-135">创建可访问报表的提示</span><span class="sxs-lookup"><span data-stu-id="d3914-135">Tips for creating accessible reports</span></span>
<span data-ttu-id="d3914-136">以下提示可帮助你创建更易于访问的 Power BI Desktop 报表。</span><span class="sxs-lookup"><span data-stu-id="d3914-136">The following tips can help you create **Power BI Desktop** reports that are more accessible.</span></span>

### <a name="general-tips-for-accessible-reports"></a><span data-ttu-id="d3914-137">有关可访问的报表的一般提示</span><span class="sxs-lookup"><span data-stu-id="d3914-137">General tips for accessible reports</span></span>

* <span data-ttu-id="d3914-138">对于“行”、“区域”、“组合图”、“散点图”和“气泡”视觉对象，请启用标记，并对每行使用不同的标记形状。</span><span class="sxs-lookup"><span data-stu-id="d3914-138">For **Line**, **Area**, and **Combo** visuals, as well as for **Scatter** and **Bubble** visuals, turn markers on, and use a different *Marker shape* for each line.</span></span>
  
  * <span data-ttu-id="d3914-139">若要启用“标记”，可在“可视化效果”窗格中选择“格式”部分，展开“形状”部分，然后向下滚动查找“标记”切换，并将其切换为“开”。</span><span class="sxs-lookup"><span data-stu-id="d3914-139">To turn *Markers* on, select the **Format** section in the **Visualizations** pane, expand the **Shapes** section, then scroll down to find the **Markers** toggle and turn it to *On*.</span></span>
  * <span data-ttu-id="d3914-140">然后，从“形状”部分中的下拉列表框中选择每行（如果使用区域图表，则为区域）的名称。</span><span class="sxs-lookup"><span data-stu-id="d3914-140">Then, select the name of each line (or area, if using an **Area** chart) from the drop-down box in that **Shapes** section.</span></span> <span data-ttu-id="d3914-141">在下拉列表下方，可以调整用于所选行的标记的许多方面，包括其形状、颜色和大小。</span><span class="sxs-lookup"><span data-stu-id="d3914-141">Below the drop-down, you can then adjust many aspects of the marker used for the selected line, including its shape, color, and size.</span></span>
  
  ![在折线图和分区图中使用不同的标记来改善辅助功能](media/desktop-accessibility/accessibility_01.png)
  
  * <span data-ttu-id="d3914-143">对每行使用不同的标记形状可使报表使用者更容易区分行（或区域）。</span><span class="sxs-lookup"><span data-stu-id="d3914-143">Using a different *Marker shape* for each line makes it easier for report consumers to differentiate lines (or areas) from each other.</span></span>
* <span data-ttu-id="d3914-144">作为上一个项目符号的后续内容，不要依赖颜色传达信息。</span><span class="sxs-lookup"><span data-stu-id="d3914-144">As a follow on to the previous bullet, don't rely on color to convey information.</span></span> <span data-ttu-id="d3914-145">除了在折线图和散点图上使用形状外，不要依赖条件格式在表和矩阵中提供见解。</span><span class="sxs-lookup"><span data-stu-id="d3914-145">In addition to using shapes on line and scatter charts, don't rely on conditional formatting to provide insights in tables and matrices.</span></span> 
* <span data-ttu-id="d3914-146">为报表上的每个视觉对象选择有意图的排序顺序。</span><span class="sxs-lookup"><span data-stu-id="d3914-146">Pick an intentional sort order for each visual on your report.</span></span> <span data-ttu-id="d3914-147">当屏幕阅读器用户在图表背后的数据中导航时，它会选取与该视觉对象相同的排序顺序。</span><span class="sxs-lookup"><span data-stu-id="d3914-147">When screen reader users navigate the data behind the chart, it will pick up the same sort order as the visual.</span></span>
* <span data-ttu-id="d3914-148">从主题库中选择一个高对比度、适合色盲人士的主题，然后使用[**主题**预览功能](desktop-report-themes.md)将其导入。</span><span class="sxs-lookup"><span data-stu-id="d3914-148">Select a *theme* that is high contrast and color blind friendly from the theme gallery, and import it using the [**Theming** preview feature](desktop-report-themes.md).</span></span>
* <span data-ttu-id="d3914-149">为报表上的每个对象提供替换文字。</span><span class="sxs-lookup"><span data-stu-id="d3914-149">For every object on a report, provide *Alt Text*.</span></span> <span data-ttu-id="d3914-150">这可确保报表使用者了解你想通过视觉对象表达的内容，即使他们看不见视觉对象、图像、形状或文本框。</span><span class="sxs-lookup"><span data-stu-id="d3914-150">Doing so ensures that consumers of your report understand what you are trying to communicate with a visual, even if they cannot see the visual, image, shape, or textbox.</span></span> <span data-ttu-id="d3914-151">在“可视化效果”窗格中选中对象（例如视觉对象、形状等），选择“格式”部分，展开“常规”，然后滚动到底部并填写“替换文字”文本框，可为 Power BI Desktop 报表上的任何对象提供“替换文字”。</span><span class="sxs-lookup"><span data-stu-id="d3914-151">You can provide *Alt Text* for any object on a **Power BI Desktop** report by selecting the object (such as a visual, shape, and so on) and in the **Visualizations** pane, select the **Format** section, expand **General**, scroll to the bottom, and fill in the **Alt Text** textbox.</span></span>
  
  ![可在“可视化效果”>“格式”>“常规”>“替换文字”框中为报表中的任何对象添加替换文字](media/desktop-accessibility/accessibility_02.png)
* <span data-ttu-id="d3914-153">请确保报表在文本和任意背景颜色之间有足够的对比度。</span><span class="sxs-lookup"><span data-stu-id="d3914-153">Make sure your reports have sufficient contrast between text and any background colors.</span></span> <span data-ttu-id="d3914-154">可以使用 [Colour Contrast Analyser](https://developer.paciellogroup.com/resources/contrastanalyser/)（颜色对比度分析程序）等多种工具检查报表颜色。</span><span class="sxs-lookup"><span data-stu-id="d3914-154">There are several tools such as [Colour Contrast Analyser](https://developer.paciellogroup.com/resources/contrastanalyser/) you can use to check your report colors.</span></span> 
* <span data-ttu-id="d3914-155">使用易于阅读的文本大小和字体。</span><span class="sxs-lookup"><span data-stu-id="d3914-155">Use text sizes and fonts that are easily readable.</span></span> <span data-ttu-id="d3914-156">文本太小或难以阅读的字体对辅助功能没有任何帮助。</span><span class="sxs-lookup"><span data-stu-id="d3914-156">Small text size, or fonts that might be difficult to read, are unhelpful for accessibility.</span></span>
* <span data-ttu-id="d3914-157">包括所有视觉对象中的标题、轴标签和数据标签。</span><span class="sxs-lookup"><span data-stu-id="d3914-157">Include a title, axis labels, and data labels in all visuals.</span></span>
* <span data-ttu-id="d3914-158">为所有报表页使用有意义的标题。</span><span class="sxs-lookup"><span data-stu-id="d3914-158">Use meaningful titles for all report pages.</span></span>
* <span data-ttu-id="d3914-159">尽可能避免报表中出现装饰形状和图像，因为它们将包含在报表的 Tab 键顺序中。</span><span class="sxs-lookup"><span data-stu-id="d3914-159">Avoid decorative shapes and images in your report if possible, as they are included in the tab order of the report.</span></span> <span data-ttu-id="d3914-160">如果需要在报表中添加修饰对象，请更新对象的替换文字，以便屏幕阅读器用户知道它只用于修饰。</span><span class="sxs-lookup"><span data-stu-id="d3914-160">If you need to include decorative objects in your report, update the object's alt text to let screen reader users know that it is for decoration.</span></span>

### <a name="arranging-items-in-field-buckets"></a><span data-ttu-id="d3914-161">排列“字段”存储桶中的项</span><span class="sxs-lookup"><span data-stu-id="d3914-161">Arranging items in Field buckets</span></span>
<span data-ttu-id="d3914-162">从 Power BI Desktop 的 2018 年 10 月版本开始，“字段”也可以使用键盘导航和与屏幕阅读器进行交互。</span><span class="sxs-lookup"><span data-stu-id="d3914-162">Beginning with the October 2018 release of **Power BI Desktop**, the **Fields** well can be navigated with a keyboard and interacts with screen readers.</span></span> 

<span data-ttu-id="d3914-163">要改进使用屏幕阅读器创建报表的过程，可使用上下文菜单，在“字段”列表的井中向上或向下移动字段，或将字段移动到其他井中（如“图例”、“值”或其他）。</span><span class="sxs-lookup"><span data-stu-id="d3914-163">To improve the process of creating reports with screen readers, a context menu is available to allow moving fields in the well up or down in the **Fields** list, or moving the field to other wells, such as **Legend** or **Value** or others.</span></span>

![借助“字段”井中的“上下文”菜单，可向上、向下或向其他区域移动字段](media/desktop-accessibility/accessibility_09.png)

## <a name="high-contrast-support-for-reports"></a><span data-ttu-id="d3914-165">报表的高对比度支持</span><span class="sxs-lookup"><span data-stu-id="d3914-165">High contrast support for reports</span></span>

<span data-ttu-id="d3914-166">使用 Windows 中的高对比度模式时，所选设置和调色板也会应用到 Power BI Desktop 的报表中。</span><span class="sxs-lookup"><span data-stu-id="d3914-166">When you use high contrast modes in Windows, those settings and the palette you select are also applied to reports in **Power BI Desktop**.</span></span> 

![Windows 高对比度设置](media/desktop-accessibility/accessibility_05.png)

<span data-ttu-id="d3914-168">Power BI Desktop 自动检测 Windows 中使用的高对比度主题，并将这些设置应用到报表。</span><span class="sxs-lookup"><span data-stu-id="d3914-168">**Power BI Desktop** automatically detects which high contrast theme is being used in Windows, and applies those settings to your reports.</span></span> <span data-ttu-id="d3914-169">报表发布到 Power BI 服务或其他位置时，这些高对比度颜色也会跟随报表。</span><span class="sxs-lookup"><span data-stu-id="d3914-169">Those high contrast colors will follow the report when published to the Power BI service, or elsewhere.</span></span>

![Windows 高对比度设置](media/desktop-accessibility/accessibility_05b.png)

<span data-ttu-id="d3914-171">Power BI 服务还尝试检测 Windows 选择的高对比度设置，但该检测的有效性和准确性取决于用于 Power BI 服务的浏览器。</span><span class="sxs-lookup"><span data-stu-id="d3914-171">The Power BI service also attempts to detect the high contrast settings selected for Windows, but how effective and accurate that detection is depends on the browser being used for the Power BI service.</span></span> <span data-ttu-id="d3914-172">如果要在 Power BI 服务中手动设置主题，可选择“视图”>“高对比度颜色”，然后选择要应用于报表的主题。</span><span class="sxs-lookup"><span data-stu-id="d3914-172">If you want to set the theme manually in the Power BI service, you can select **View > High contrast colors** and then select the theme you would like to apply to the report.</span></span>

![在 Power BI 服务中设置高对比度](media/desktop-accessibility/accessibility_06.png)

<span data-ttu-id="d3914-174">请注意：在 Power BI Desktop 中，“可视化效果”和“字段”字段等区域不反映 Windows 高对比度配色方案的选择。</span><span class="sxs-lookup"><span data-stu-id="d3914-174">When in **Power BI Desktop**, notice that some areas such as the **Visualizations** and **Fields** fields do not reflect the selection of high contrast Windows color schemes.</span></span>


## <a name="considerations-and-limitations"></a><span data-ttu-id="d3914-175">注意事项和限制</span><span class="sxs-lookup"><span data-stu-id="d3914-175">Considerations and limitations</span></span>
<span data-ttu-id="d3914-176">辅助功能存在一些已知问题和限制，如以下列表所述：</span><span class="sxs-lookup"><span data-stu-id="d3914-176">There are a few known issues and limitations with the accessibility features, described in the following list:</span></span>

* <span data-ttu-id="d3914-177">通过 Power BI Desktop 使用屏幕阅读器时，如果在 Power BI Desktop 中打开任何文件前打开所选屏幕阅读器，则将获得最佳体验。</span><span class="sxs-lookup"><span data-stu-id="d3914-177">When using screen readers with **Power BI Desktop**, you'll have the best experience if you open your screen reader of choice prior to opening any files in Power BI Desktop.</span></span>
* <span data-ttu-id="d3914-178">如果使用讲述人，以 HTML 表形式导航“显示数据”有一些相关限制。</span><span class="sxs-lookup"><span data-stu-id="d3914-178">If you are using Narrator, there are some limitations around navigating Show data as an HTML table.</span></span>

## <a name="keyboard-shortcuts"></a><span data-ttu-id="d3914-179">键盘快捷方式</span><span class="sxs-lookup"><span data-stu-id="d3914-179">Keyboard Shortcuts</span></span>
<span data-ttu-id="d3914-180">键盘快捷方式有助于使用键盘在 Power BI 报表中移动。</span><span class="sxs-lookup"><span data-stu-id="d3914-180">Keyboard shortcuts are helpful for moving around in Power BI reports using a keyboard.</span></span> <span data-ttu-id="d3914-181">下表介绍了 Power BI 报表中可用的快捷方式。</span><span class="sxs-lookup"><span data-stu-id="d3914-181">The following tables describe the shortcuts available in a Power BI report.</span></span> <span data-ttu-id="d3914-182">除了在 Power BI Desktop 中使用这些键盘快捷方式以外，还可以在以下体验中使用这些快捷方式：</span><span class="sxs-lookup"><span data-stu-id="d3914-182">In addition to using these keyboard shortcuts in Power BI Desktop, these shortcuts work in the following experiences as well:</span></span>

* <span data-ttu-id="d3914-183">“问答资源管理器”对话框</span><span class="sxs-lookup"><span data-stu-id="d3914-183">Q&A Explorer dialog</span></span>
* <span data-ttu-id="d3914-184">“入门指南”对话框</span><span class="sxs-lookup"><span data-stu-id="d3914-184">Getting Started dialog</span></span>
* <span data-ttu-id="d3914-185">“文件”菜单和“关于”对话框</span><span class="sxs-lookup"><span data-stu-id="d3914-185">File menu and About dialog</span></span>
* <span data-ttu-id="d3914-186">警告栏</span><span class="sxs-lookup"><span data-stu-id="d3914-186">Warning bar</span></span>
* <span data-ttu-id="d3914-187">“文件还原”对话框</span><span class="sxs-lookup"><span data-stu-id="d3914-187">File Restore dialog</span></span>
* <span data-ttu-id="d3914-188">“哭脸”对话框</span><span class="sxs-lookup"><span data-stu-id="d3914-188">Frowns dialog</span></span>

<span data-ttu-id="d3914-189">在我们持续努力提升可访问性的情况下，以前的体验列表也支持屏幕阅读器和高对比度设置。</span><span class="sxs-lookup"><span data-stu-id="d3914-189">In our continued effort to improve accessibility, the previous list of experiences also support screen readers and high contrast settings.</span></span>


### <a name="frequently-used-shortcuts"></a><span data-ttu-id="d3914-190">常用快捷方式</span><span class="sxs-lookup"><span data-stu-id="d3914-190">Frequently used shortcuts</span></span>
| <span data-ttu-id="d3914-191">如何执行此操作</span><span class="sxs-lookup"><span data-stu-id="d3914-191">To do this</span></span>           | <span data-ttu-id="d3914-192">操作方法</span><span class="sxs-lookup"><span data-stu-id="d3914-192">Press</span></span>                |
| :------------------- | :------------------- |
| <span data-ttu-id="d3914-193">在分区间移动焦点</span><span class="sxs-lookup"><span data-stu-id="d3914-193">Move focus between sections</span></span>  | <span data-ttu-id="d3914-194">Ctrl + F6</span><span class="sxs-lookup"><span data-stu-id="d3914-194">Ctrl + F6</span></span> |
| <span data-ttu-id="d3914-195">在分区中向前移动焦点</span><span class="sxs-lookup"><span data-stu-id="d3914-195">Move focus forward in section</span></span> | <span data-ttu-id="d3914-196">Tab</span><span class="sxs-lookup"><span data-stu-id="d3914-196">Tab</span></span>         |
| <span data-ttu-id="d3914-197">在分区中向后移动焦点</span><span class="sxs-lookup"><span data-stu-id="d3914-197">Move focus backward in section</span></span> | <span data-ttu-id="d3914-198">Shift + Tab</span><span class="sxs-lookup"><span data-stu-id="d3914-198">Shift + Tab</span></span> |
| <span data-ttu-id="d3914-199">选择或取消选择对象</span><span class="sxs-lookup"><span data-stu-id="d3914-199">Select or de-select an object</span></span> | <span data-ttu-id="d3914-200">Enter 或空格键</span><span class="sxs-lookup"><span data-stu-id="d3914-200">Enter or Space</span></span> |
| <span data-ttu-id="d3914-201">多重选择对象</span><span class="sxs-lookup"><span data-stu-id="d3914-201">Multi-select objects</span></span> | <span data-ttu-id="d3914-202">Ctrl + 空格键</span><span class="sxs-lookup"><span data-stu-id="d3914-202">Ctrl + Space</span></span> |

### <a name="on-visual"></a><span data-ttu-id="d3914-203">启用视觉对象</span><span class="sxs-lookup"><span data-stu-id="d3914-203">On visual</span></span>
| <span data-ttu-id="d3914-204">如何执行此操作</span><span class="sxs-lookup"><span data-stu-id="d3914-204">To do this</span></span>           | <span data-ttu-id="d3914-205">操作方法</span><span class="sxs-lookup"><span data-stu-id="d3914-205">Press</span></span>                |
| :------------------- | :------------------- |
| <span data-ttu-id="d3914-206">将焦点移动到视觉对象菜单</span><span class="sxs-lookup"><span data-stu-id="d3914-206">Move focus to visual menu</span></span> | <span data-ttu-id="d3914-207">Alt + Shift + F10</span><span class="sxs-lookup"><span data-stu-id="d3914-207">Alt + Shift + F10</span></span> |
| <span data-ttu-id="d3914-208">显示数据</span><span class="sxs-lookup"><span data-stu-id="d3914-208">Show data</span></span> | <span data-ttu-id="d3914-209">Alt + Shift +F11</span><span class="sxs-lookup"><span data-stu-id="d3914-209">Alt + Shift +F11</span></span>  |

### <a name="pane-navigation"></a><span data-ttu-id="d3914-210">窗格导航</span><span class="sxs-lookup"><span data-stu-id="d3914-210">Pane Navigation</span></span>
| <span data-ttu-id="d3914-211">如何执行此操作</span><span class="sxs-lookup"><span data-stu-id="d3914-211">To do this</span></span>           | <span data-ttu-id="d3914-212">操作方法</span><span class="sxs-lookup"><span data-stu-id="d3914-212">Press</span></span>                |
| :------------------- | :------------------- |
| <span data-ttu-id="d3914-213">打开上下文菜单</span><span class="sxs-lookup"><span data-stu-id="d3914-213">Open a context menu</span></span> | <ul><li><span data-ttu-id="d3914-214">Windows 键盘：Windows 上下文键 + F10。</span><span class="sxs-lookup"><span data-stu-id="d3914-214">Windows keyboard: Windows context key + F10.</span></span>  <span data-ttu-id="d3914-215">Windows 上下文键位于左 Alt 键和向左键之间</span><span class="sxs-lookup"><span data-stu-id="d3914-215">The Windows context key is between the Left Alt key and the Left Arrow Key</span></span></li><li><span data-ttu-id="d3914-216">其他键盘：Shift + F10</span><span class="sxs-lookup"><span data-stu-id="d3914-216">Other keyboard: Shift + F10</span></span></li></ul> |

### <a name="slicer"></a><span data-ttu-id="d3914-217">切片器</span><span class="sxs-lookup"><span data-stu-id="d3914-217">Slicer</span></span>
| <span data-ttu-id="d3914-218">如何执行此操作</span><span class="sxs-lookup"><span data-stu-id="d3914-218">To do this</span></span>           | <span data-ttu-id="d3914-219">操作方法</span><span class="sxs-lookup"><span data-stu-id="d3914-219">Press</span></span>                |
| :------------------- | :------------------- |
| <span data-ttu-id="d3914-220">与切片器进行交互</span><span class="sxs-lookup"><span data-stu-id="d3914-220">Interact with a slicer</span></span> | <span data-ttu-id="d3914-221">Ctrl + 向右键</span><span class="sxs-lookup"><span data-stu-id="d3914-221">Ctrl + Right arrow key</span></span> |

### <a name="selection-pane"></a><span data-ttu-id="d3914-222">“选择”窗格</span><span class="sxs-lookup"><span data-stu-id="d3914-222">Selection Pane</span></span>
| <span data-ttu-id="d3914-223">如何执行此操作</span><span class="sxs-lookup"><span data-stu-id="d3914-223">To do this</span></span>           | <span data-ttu-id="d3914-224">操作方法</span><span class="sxs-lookup"><span data-stu-id="d3914-224">Press</span></span>                |
| :------------------- | :------------------- |
| <span data-ttu-id="d3914-225">激活“选择”窗格</span><span class="sxs-lookup"><span data-stu-id="d3914-225">Activate selection pane</span></span> | <span data-ttu-id="d3914-226">F6</span><span class="sxs-lookup"><span data-stu-id="d3914-226">F6</span></span> |
| <span data-ttu-id="d3914-227">在分层中向上移动对象</span><span class="sxs-lookup"><span data-stu-id="d3914-227">Move an object up in the layering</span></span> | <span data-ttu-id="d3914-228">Ctrl + Shift + F</span><span class="sxs-lookup"><span data-stu-id="d3914-228">Ctrl + Shift + F</span></span> |
| <span data-ttu-id="d3914-229">在分层中向下移动对象</span><span class="sxs-lookup"><span data-stu-id="d3914-229">Move an object down in the layering</span></span> | <span data-ttu-id="d3914-230">Ctrl + Shift + B</span><span class="sxs-lookup"><span data-stu-id="d3914-230">Ctrl + Shift + B</span></span> |
| <span data-ttu-id="d3914-231">隐藏/显示（切换）对象</span><span class="sxs-lookup"><span data-stu-id="d3914-231">Hide / show (toggle) an object</span></span> | <span data-ttu-id="d3914-232">Ctrl + Shift + S</span><span class="sxs-lookup"><span data-stu-id="d3914-232">Ctrl + Shift + S</span></span> |

### <a name="dax-editor"></a><span data-ttu-id="d3914-233">DAX 编辑器</span><span class="sxs-lookup"><span data-stu-id="d3914-233">DAX Editor</span></span>
| <span data-ttu-id="d3914-234">如何执行此操作</span><span class="sxs-lookup"><span data-stu-id="d3914-234">To do this</span></span>           | <span data-ttu-id="d3914-235">操作方法</span><span class="sxs-lookup"><span data-stu-id="d3914-235">Press</span></span>                |
| :------------------- | :------------------- |
| <span data-ttu-id="d3914-236">向上/向下移动行</span><span class="sxs-lookup"><span data-stu-id="d3914-236">Move line up / down</span></span> | <span data-ttu-id="d3914-237">Alt + 向上键/向下键</span><span class="sxs-lookup"><span data-stu-id="d3914-237">Alt + Up arrow key / Down arrow key</span></span> |
| <span data-ttu-id="d3914-238">向上/向下复制行</span><span class="sxs-lookup"><span data-stu-id="d3914-238">Copy line up / down</span></span> | <span data-ttu-id="d3914-239">Shift + Alt + 向上键/向下键</span><span class="sxs-lookup"><span data-stu-id="d3914-239">Shift + Alt + Up arrow key / Down arrow key</span></span> |
| <span data-ttu-id="d3914-240">在下方插入行</span><span class="sxs-lookup"><span data-stu-id="d3914-240">Insert line below</span></span> | <span data-ttu-id="d3914-241">Ctrl + Enter</span><span class="sxs-lookup"><span data-stu-id="d3914-241">Ctrl + Enter</span></span> |
| <span data-ttu-id="d3914-242">在上方插入行</span><span class="sxs-lookup"><span data-stu-id="d3914-242">Insert line above</span></span> | <span data-ttu-id="d3914-243">Ctrl + Shift + Enter</span><span class="sxs-lookup"><span data-stu-id="d3914-243">Ctrl + Shift + Enter</span></span> |
| <span data-ttu-id="d3914-244">跳转到匹配的括号</span><span class="sxs-lookup"><span data-stu-id="d3914-244">Jump to matching bracket</span></span> | <span data-ttu-id="d3914-245">Ctrl + Shift + \\</span><span class="sxs-lookup"><span data-stu-id="d3914-245">Ctrl + Shift + \\</span></span> |
| <span data-ttu-id="d3914-246">缩进/突出行</span><span class="sxs-lookup"><span data-stu-id="d3914-246">Indent / outdent line</span></span> | <span data-ttu-id="d3914-247">Ctrl + ] / [</span><span class="sxs-lookup"><span data-stu-id="d3914-247">Ctrl + ] / [</span></span> |
| <span data-ttu-id="d3914-248">插入光标</span><span class="sxs-lookup"><span data-stu-id="d3914-248">Insert cursor</span></span> | <span data-ttu-id="d3914-249">Alt + 单击</span><span class="sxs-lookup"><span data-stu-id="d3914-249">Alt + Click</span></span> |
| <span data-ttu-id="d3914-250">选择当前行</span><span class="sxs-lookup"><span data-stu-id="d3914-250">Select current line</span></span> | <span data-ttu-id="d3914-251">Ctrl + I</span><span class="sxs-lookup"><span data-stu-id="d3914-251">Ctrl + I</span></span> |
| <span data-ttu-id="d3914-252">选择当前所选内容的所有匹配项</span><span class="sxs-lookup"><span data-stu-id="d3914-252">Select all occurrences of current selection</span></span> | <span data-ttu-id="d3914-253">Ctrl + Shift + L</span><span class="sxs-lookup"><span data-stu-id="d3914-253">Ctrl + Shift + L</span></span> |
| <span data-ttu-id="d3914-254">选择当前词语的所有匹配项</span><span class="sxs-lookup"><span data-stu-id="d3914-254">Select all occurrences of current word</span></span> | <span data-ttu-id="d3914-255">Ctrl + F2</span><span class="sxs-lookup"><span data-stu-id="d3914-255">Ctrl + F2</span></span> |




## <a name="next-steps"></a><span data-ttu-id="d3914-256">后续步骤</span><span class="sxs-lookup"><span data-stu-id="d3914-256">Next steps</span></span>
* [<span data-ttu-id="d3914-257">在 Power BI Desktop 中使用报表主题（预览版）</span><span class="sxs-lookup"><span data-stu-id="d3914-257">Use Report Themes in Power BI Desktop (Preview)</span></span>](desktop-report-themes.md)
