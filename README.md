<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><p dir="auto"><a href="https://certification.oshwa.org/at000008.html" title="开源硬件协会证书" rel="nofollow"><img align="right" width="25%" src="https://github.com/OpenGammaProject/Open-Gamma-Detector/raw/main/docs/oshw.svg" alt="开源硬件协会证书" style="max-width: 100%;"></a></p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">打开伽马探测器</font></font></h1><a id="user-content-open-gamma-detector" class="anchor" aria-label="永久链接：打开伽马探测器" href="#open-gamma-detector"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<hr>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这是最新的硬件修订版 4.1。对于较旧的修订版，请查看</font></font><a href="https://github.com/OpenGammaProject/Open-Gamma-Detector/branches"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">其他分支。可以</font></font></a><font style="vertical-align: inherit;"></font><a href="https://hackaday.io/project/185211-all-in-one-gamma-ray-spectrometer/log/225597-revision-40-status-report" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在此处</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">找到 4.0 和 3.x 硬件之间的比较</font><font style="vertical-align: inherit;">。</font></font></strong></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该项目也在</font></font><a href="https://hackaday.io/project/185211-all-in-one-gamma-ray-spectrometer" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Hackaday.io</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上，我在那里发布重要的项目更新和其他公告！</font></font></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用流行的 NaI(Tl) 闪烁晶体和硅光电倍增管 (SiPM) 的可破解伽马光谱仪一体式设备的开放硬件。功能强大的 DIY 伽马光谱仪装置设计极其经济实惠，零件总成本不到 200 美元。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该探测器使用标准串行 USB 和硬件 UART 连接，以便它可以集成到尽可能多的其他项目中，例如使用 Raspberry Pi 进行数据记录、气象站、Arduino 项目等。它包括闪烁计数器和多通道分析仪 (MCA) 功能，具体取决于您想要如何使用它。</font></font></p>
<p align="center" dir="auto">
  <a target="_blank" rel="noopener noreferrer" href="https://github.com/OpenGammaProject/Open-Gamma-Detector/blob/main/docs/oled.jpg"><img alt="安装了 SiPM、晶体和 OLED 的探测器板照片" title="安装了 SiPM、晶体和 OLED 的探测器板照片" width="500px" src="https://github.com/OpenGammaProject/Open-Gamma-Detector/raw/main/docs/oled.jpg" style="max-width: 100%;"></a>
  <br>
  <a target="_blank" rel="noopener noreferrer" href="https://github.com/OpenGammaProject/Open-Gamma-Detector/blob/main/docs/img1.jpg"><img alt="探测器板的照片" title="探测器板的照片" width="500px" src="https://github.com/OpenGammaProject/Open-Gamma-Detector/raw/main/docs/img1.jpg" style="max-width: 100%;"></a>
</p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您想要一个更基本的开放伽马探测器版本来仅计算脉冲或类似功能，您可以看看</font></font><a href="https://github.com/OpenGammaProject/Mini-SiD"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Mini SiPM 驱动</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">板。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">特征</font></font></h2><a id="user-content-features" class="anchor" aria-label="固定链接：功能" href="#features"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下是一些最重要的规格：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">紧凑型设计：总尺寸 120 x 50 毫米。约 70.5 x 50 毫米区域用于电子元件，另外 49.5 x 50 毫米用于安装闪烁体。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一体化：无需外部部件（例如声卡）即可记录伽马光谱。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">内置闪光灯上的独立光谱记录。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用拖放固件文件或标准 Arduino IDE 轻松进行编程。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">低压设备：不需要像光电倍增管那样的高压。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可以使用电压范围为 27.5 V 至 33.8 V 的 SiPM。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4096 个 ADC 通道，内置 3 V 电压参考。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">能量分辨率可能高达 7% @ 662 keV；高度依赖于您的 SiPM/闪烁体组件。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">能量模式：测量能量时总死区时间约为 20 µs（默认设置）。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">盖革模式：无能量测量时总死区时间 &lt;5 µs（默认设置）。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">低功耗：正常背景下的默认固件约为 20 mA @ 5 V。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">内置蜂鸣器，用于输出可听见的脉冲计数率。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于定制部件（例如显示器、µSD 卡等）的额外断开电源引脚和 I2C、SPI 和 UART 接头。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开箱即用的简单 OLED 支持（SSD1306 和 SH110x）。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">内置真随机数生成器。</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何获得</font></font></h2><a id="user-content-how-to-get-one" class="anchor" aria-label="永久链接：如何获取" href="#how-to-get-one"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为了快速访问和购买所有零件（PCB 和 BOM），您可以使用</font></font><a href="https://kitspace.org/boards/github.com/opengammaproject/open-gamma-detector/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Kitspace</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（可能已过时！）。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">否则，请使用您选择的 PCB 制造商和电子产品分销商，然后自行处理。您需要的所有文件都可以在此 repo 中找到。</font></font></li>
</ul>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果你不想处理所有这些事情，请随时联系我。如果你愿意，只需给我发一封电子邮件，我们就会想出办法。</font></font></li>
</ul>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您还需要从您选择的分销商处单独购买 SiPM（例如 MICROFC-60035-SMT-TR）和闪烁体（建议使用 NaI(Tl)）。</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可能还想购买我制作的无数 SiPM 分线板之一。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">工作准则</font></font></h2><a id="user-content-working-principle" class="anchor" aria-label="固定链接：工作原理" href="#working-principle"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下面是一个流程图，描述了该设备大致的工作原理：</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/OpenGammaProject/Open-Gamma-Detector/blob/main/docs/flow.drawio.svg"><img src="https://github.com/OpenGammaProject/Open-Gamma-Detector/raw/main/docs/flow.drawio.svg" alt="工作原理流程图" style="max-width: 100%;"></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">硬件</font></font></h2><a id="user-content-hardware" class="anchor" aria-label="固定链接：硬件" href="#hardware"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://easyeda.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">硬件设计已使用EasyEDA</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">完成</font><font style="vertical-align: inherit;">，文件夹中包含导入项目所需的所有文件以及原理图</font></font><code>hardware</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。还有一个 Gerber 文件可供您直接进入 PCB 制造步骤。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关探测器硬件以及电位器设置和组装的详细信息可以在</font></font><a href="/OpenGammaProject/Open-Gamma-Detector/blob/main/hardware"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">硬件目录</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中找到。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">软件</font></font></h2><a id="user-content-software" class="anchor" aria-label="固定链接：软件" href="#software"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该软件旨在尽可能简单易懂和维护。为了实现这一点，我决定使用现成的微控制器 - </font></font><a href="https://www.raspberrypi.com/products/raspberry-pi-pico/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Raspberry Pi Pico</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。该板可以通过微型 USB 使用 Arduino IDE 进行编程，功能强大（双核、快速 ADC、大量内存等），足以满足用途，而且价格非常便宜。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要对 Pico 进行编程和/或试用固件，请前往</font></font><a href="/OpenGammaProject/Open-Gamma-Detector/blob/main/software"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">软件目录</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。您还可以在那里找到有关串行接口 (!)、显示支持等的文档。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">故障排除和常见问题解答</font></font></h2><a id="user-content-troubleshooting-and-faq" class="anchor" aria-label="永久链接：故障排除和常见问题解答" href="#troubleshooting-and-faq"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请查看</font></font><a href="/OpenGammaProject/Open-Gamma-Detector/blob/main/REFERENCE.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">REFERENCE.md</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">获取一些一般指导。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果这对您没有帮助，请随时联系我们并创建问题或打开讨论主题。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">光谱示例</font></font></h2><a id="user-content-example-spectra" class="anchor" aria-label="永久链接：光谱示例" href="#example-spectra"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下是一些我可以快速制作的示例光谱，无需花费太多精力进行探测器设置（阈值、SiPM 电压、软件调整）。我使用的是</font></font><a href="https://github.com/OpenGammaProject/Tiny-MicroFC-Carrier-Board"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Tiny MicroFC Breakout</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和单个 SiPM（实际上这不是最佳设置）。此外，电子设备、闪烁体和样品都没有屏蔽任何 EMI 或背景辐射。因此，正如您所见，探测器在这方面实际上非常坚固。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">无样本的背景光谱（2h）：</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/OpenGammaProject/Open-Gamma-Detector/blob/main/docs/bg.png"><img src="https://github.com/OpenGammaProject/Open-Gamma-Detector/raw/main/docs/bg.png" alt="背景光谱" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">两个微小（~5 g）LYSO 闪烁体的光谱（2h），显示两个不同的伽马峰（201.83、306.78 keV）以及一个额外的~55 keV X 射线峰。在这种情况下，307 keV 峰的能量分辨率为~14%：</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/OpenGammaProject/Open-Gamma-Detector/blob/main/docs/lu-176.png"><img src="https://github.com/OpenGammaProject/Open-Gamma-Detector/raw/main/docs/lu-176.png" alt="镥-176光谱" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">家用电离烟雾探测器中常用的 Am-241 光谱（5 分钟）（例如在美国，不再在欧盟）。伽马峰值在 26.34 和 59.54 keV：</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/OpenGammaProject/Open-Gamma-Detector/blob/main/docs/am-241.png"><img src="https://github.com/OpenGammaProject/Open-Gamma-Detector/raw/main/docs/am-241.png" alt="Am-176 光谱" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一个小茶杯的光谱（2h），其釉面含有纯沥青铀矿（也称为沥青铀矿）。您可以看到铀系列的各种同位素，包括 Bi-214 峰（~610 keV）。因为他们只使用了纯沥青铀矿，没有进行任何过滤，所以其中也有一些 U-235 和所有子放射性核素：</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/OpenGammaProject/Open-Gamma-Detector/blob/main/docs/glaze.png"><img src="https://github.com/OpenGammaProject/Open-Gamma-Detector/raw/main/docs/glaze.png" alt="沥青铀矿釉" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Na-22 测试源的光谱，约 ~2 µCi，使用 Rev.2 电路板制作（能量分辨率比最新版本更差）。您可以看到 511 keV 湮灭峰和较小的 1275 keV 伽马峰（由于 NaI 效率有限且此能量的闪烁体尺寸较小，因此峰要小得多）以及康普顿边缘和连续体：</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/OpenGammaProject/Open-Gamma-Detector/blob/main/docs/na-22.png"><img src="https://github.com/OpenGammaProject/Open-Gamma-Detector/raw/main/docs/na-22.png" alt="钠-22" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">约 100 克蘑菇的光谱（2 小时），其中仍含有切尔诺贝利灾难中的同位素 Cs-137。您可以清楚地看到 662 keV 处的伽马峰和 ~32 keV 的 X 射线峰。仅使用单个 SiPM 和旧的 NaI 闪烁体，662 keV 峰的分辨率为 ~8.6%：</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/OpenGammaProject/Open-Gamma-Detector/blob/main/docs/mushrooms.png"><img src="https://github.com/OpenGammaProject/Open-Gamma-Detector/raw/main/docs/mushrooms.png" alt="蘑菇“试验源”" style="max-width: 100%;"></a></p>
<hr>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下是使用更大的 1x1 英寸闪烁体（额定值为 6.9% @ 662 keV）和 2x2 SiPM 阵列得到的一些相同光谱：</font></font></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上面同一个蘑菇样本的光谱（1 小时）。这次 662 keV Cs-137 的分辨率为 7.7%，还不错！</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/OpenGammaProject/Open-Gamma-Detector/blob/main/docs/mushrooms-advanced.png"><img src="https://github.com/OpenGammaProject/Open-Gamma-Detector/raw/main/docs/mushrooms-advanced.png" alt="蘑菇“试验源”" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一小批氧化镥（III）的光谱（1h）。它与上面的 LYSO 闪烁体样品一样含有 Lu-176。因此它也具有相同的峰值，只是现在更加清晰。307 keV 峰值现在的能量分辨率为 11.5%。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/OpenGammaProject/Open-Gamma-Detector/blob/main/docs/lu-176-advanced.png"><img src="https://github.com/OpenGammaProject/Open-Gamma-Detector/raw/main/docs/lu-176-advanced.png" alt="镥-176光谱" style="max-width: 100%;"></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">已知限制</font></font></h2><a id="user-content-known-limitations" class="anchor" aria-label="永久链接：已知限制" href="#known-limitations"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ol dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Raspberry Pi Pico 的 ADC 存在一些相当</font></font><a href="https://pico-adc.markomo.me/INL-DNL/#dnl" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">严重的 DNL 问题</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，导致四个通道比其他通道敏感得多（输入范围更宽）。目前最简单的解决方案是丢弃所有四个通道，方法是</font></font><code>0</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">当其中任何一个通道出现在测量中时打印一个（不影响 cps 读数）。您可以使用命令关闭此行为</font></font><code>set correction</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。这绝不是完美或理想的，但它目前有效，直到这个问题在 RP2040 的后续硬件修订版中得到修复（祝我们好运！）。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">电源本身</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">进行温度校正，这意味着在恒定电压下环境温度的变化会影响 SiPM 的增益。这自然会导致不同的直流偏置、能量范围和信噪比。不过，这种影响在室温下可以忽略不计。对于 MicroFC SiPM，增益的温度依赖性为 -0.8%/°C (21°C)。不过，</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">最新的</font></font><a href="https://github.com/OpenGammaProject/MicroFC-SiPM-Carrier-Board"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MicroFC SiPM 载板</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">具有板载自动温度补偿功能！因此，如果您想获得最佳性能，请使用此功能。</font></font></strong></li>
</ol>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一些想法</font></font></h2><a id="user-content-some-ideas" class="anchor" aria-label="永久链接：一些想法" href="#some-ideas"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">巧合测量</font></font></h3><a id="user-content-coincidence-measurements" class="anchor" aria-label="永久链接：巧合测量" href="#coincidence-measurements"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用多个探测器板并进行一些固件修改，理论上应该可以实现巧合测量功能。通过分别将 和其中一个断开的引脚连接</font></font><code>VSYS</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">到</font></font><code>GND</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">两个板上，您就拥有了开始所需的一切。如果两个时间一致，则引脚将用于从子探测器到父探测器的中断以触发脉冲。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不过，目前由于一些奇怪的时间问题，我无法运行巧合模式功能。将来可能会有固件更新来实现此功能。如果您有任何想法，请告诉我！</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">冷却 SiPM</font></font></h3><a id="user-content-cooling-the-sipm" class="anchor" aria-label="永久链接：冷却 SiPM" href="#cooling-the-sipm"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在运行过程中，包括 SiPM 在内的所有电子设备都会自然地略微升温。但由于探测器板（大部分功率都耗散的地方）不直接连接到 SiPM，因此自热可以忽略不计。因此，仅靠空气或水冷无法显著提高性能，因为它不会比环境温度高出太多，如果有的话。但是，您可以使用珀尔帖模块将 SiPM PCB 冷却到低于环境温度。根据数据</font></font><a href="https://www.onsemi.com/pub/Collateral/AND9770-D.PDF" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">表 AND9770（图 27），</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">温度每降低 10°C，暗计数率就会降低 50%！但在这种情况下，请务必校正 SiPM 电压（过压），因为它也会随温度而变化。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请注意，SiPM 所需的击穿电压以 21.5 mV/°C 线性增加，请参阅</font></font><a href="https://www.onsemi.com/pdf/datasheet/microc-series-d.pdf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">C 系列 SiPM 传感器数据表</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。这意味着，如果您想在温度差异较大的情况下使用 PSU 电压，您还需要对 PSU 电压进行温度校正。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">屏蔽背景辐射</font></font></h3><a id="user-content-shielding-background-radiation" class="anchor" aria-label="永久链接：屏蔽背景辐射" href="#shielding-background-radiation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">屏蔽环境背景的理想方法是在探测器周围使用足够宽的铅层（砖），并在内部使用一层薄薄的低 Z 材料（如铜）来避免背向散射。然后可以将 SiPM 和样品放入结构中以获得最佳测量效果（低背景）。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">参见维基百科：</font></font><a href="https://en.wikipedia.org/w/index.php?title=Lead_castle&amp;oldid=991799816" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Lead Castle</font></font></a></p>
<hr>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">谢谢阅读。</font></font></p>
</article></div>
