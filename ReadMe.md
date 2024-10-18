<div class="Box-sc-g0xbh4-0 QkQOb js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto" _msttexthash="96928" _msthash="279">OpenVINS</h1><a id="user-content-openvins" class="anchor" aria-label="永久链接：OpenVINS" href="#openvins" _mstaria-label="337493" _msthash="280"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a href="https://github.com/rpng/open_vins/actions/workflows/build_ros1.yml"><img src="https://github.com/rpng/open_vins/actions/workflows/build_ros1.yml/badge.svg" alt="ROS 1 工作流程" style="max-width: 100%;" _mstalt="194987" _msthash="281"></a>
<a href="https://github.com/rpng/open_vins/actions/workflows/build_ros2.yml"><img src="https://github.com/rpng/open_vins/actions/workflows/build_ros2.yml/badge.svg" alt="ROS 2 工作流程" style="max-width: 100%;" _mstalt="195117" _msthash="282"></a>
<a href="https://github.com/rpng/open_vins/actions/workflows/build.yml"><img src="https://github.com/rpng/open_vins/actions/workflows/build.yml/badge.svg" alt="ROS 免费工作流程" style="max-width: 100%;" _mstalt="280345" _msthash="283"></a></p>
<p dir="auto" _msttexthash="9001725057" _msthash="284">欢迎来到 OpenVINS 项目！
OpenVINS 项目包含一些核心计算机视觉代码以及最先进的基于滤波器的视觉惯性
估计。核心滤波器是一个<a href="https://en.wikipedia.org/wiki/Extended_Kalman_filter" rel="nofollow" _istranslated="1">扩展卡尔曼滤波器</a>，它
将惯性信息与稀疏视觉特征轨迹融合在一起。这些视觉特征跟踪是利用
<a href="https://ieeexplore.ieee.org/document/4209642" rel="nofollow" _istranslated="1">多态约束卡尔曼滤波器 （MSCKF）</a> 滑动窗口
公式，它允许 3D 特征更新状态估计值，而无需直接估计
过滤器。受基于图的优化系统的启发，随附的过滤器具有模块化，方便
协方差管理。请查看下面的功能列表以获取完整内容
有关系统支持的内容的详细信息。</p>
<ul dir="auto">
<li _msttexthash="29339180" _msthash="285">Github 项目页面 - <a href="https://github.com/rpng/open_vins" _istranslated="1">https://github.com/rpng/open_vins</a></li>
<li _msttexthash="5871281" _msthash="286">文档 - <a href="https://docs.openvins.com/" rel="nofollow" _istranslated="1">https://docs.openvins.com/</a></li>
<li _msttexthash="13677521" _msthash="287">入门指南 - <a href="https://docs.openvins.com/getting-started.html" rel="nofollow" _istranslated="1">https://docs.openvins.com/getting-started.html</a></li>
<li _msttexthash="18400018" _msthash="288">出版物参考 - <a href="https://pgeneva.com/downloads/papers/Geneva2020ICRA.pdf" rel="nofollow" _istranslated="1">https://pgeneva.com/downloads/papers/Geneva2020ICRA.pdf</a></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="13028561" _msthash="289">新闻 / 活动</h2><a id="user-content-news--events" class="anchor" aria-label="永久链接： 新闻 / 活动" href="#news--events" _mstaria-label="461552" _msthash="290"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li _msttexthash="869462867" _msthash="291"><strong _istranslated="1">2023 年 5 月 11 日</strong> - 作为 v2.7 的一部分发布了惯性内部支持，以及一些错误修复和对立体 KLT 跟踪的改进。有关详细信息，请查看<a href="https://github.com/rpng/open_vins/releases/tag/v2.7" _istranslated="1">发布页面</a>。</li>
<li _msttexthash="1977502371" _msthash="292"><strong _istranslated="1">2023 年 4 月 15 日</strong> - 对 v2.6.3 进行了小幅更新，以支持下游应用程序的活动特征的增量特征三角测量、更快的零速度更新、小错误修复、一些示例真实感配置和缓存的快速状态预测。有关详细信息，请查看<a href="https://github.com/rpng/open_vins/releases/tag/v2.6.3" _istranslated="1">发布页面</a>。</li>
<li _msttexthash="677924975" _msthash="293"><strong _istranslated="1">2023 年 4 月 3 日</strong> - 我们发布了一种名为 <a href="https://github.com/rpng/ov_plane" _istranslated="1">ov_plane</a> 的单目平面辅助 VINS，它利用了 OpenVINS 项目。两者都支持已发布的<a href="https://github.com/rpng/ar_table_dataset" _istranslated="1">室内 AR Table</a> 数据集。</li>
<li _msttexthash="432622242" _msthash="294"><strong _istranslated="1">2022 年 7 月 14 日</strong> - 改进了 &gt;100hz 跟踪的特征提取逻辑、一些错误修复和更新的脚本。请参阅 v2.6.1 <a href="https://github.com/rpng/open_vins/pull/259" data-hovercard-type="pull_request" data-hovercard-url="/rpng/open_vins/pull/259/hovercard" _istranslated="1">PR#259</a> 和 v2.6.2 <a href="https://github.com/rpng/open_vins/pull/264" data-hovercard-type="pull_request" data-hovercard-url="/rpng/open_vins/pull/264/hovercard" _istranslated="1">PR#264</a>。</li>
<li _msttexthash="716523054" _msthash="295"><strong _istranslated="1">2022 年 3 月 14 日</strong> - 初始动态初始化开源，异步订阅惯性读数和里程计发布，支持低频特征跟踪。有关详细信息，请参阅 v2.6 <a href="https://github.com/rpng/open_vins/pull/232" data-hovercard-type="pull_request" data-hovercard-url="/rpng/open_vins/pull/232/hovercard" _istranslated="1">PR#232</a>。</li>
<li _msttexthash="1661548629" _msthash="296"><strong _istranslated="1">2021 年 12 月 13 日</strong> - 新的 YAML 配置系统、ROS2 支持、Docker 镜像、基于差异的稳健静态初始化、用于减少详细程度的内部日志记录系统、镜像传输发布者、动态功能数量支持和其他小修复。看
v2.5 <a href="https://github.com/rpng/open_vins/pull/209" data-hovercard-type="pull_request" data-hovercard-url="/rpng/open_vins/pull/209/hovercard" _istranslated="1">PR#209</a> 了解详情。</li>
<li _msttexthash="328910348" _msthash="297"><strong _istranslated="1">2021 年 7 月 19 日</strong> - 摄像机类、遮罩支持、对齐实用程序和其他小修复。看
v2.4 <a href="https://github.com/rpng/open_vins/pull/186" data-hovercard-type="pull_request" data-hovercard-url="/rpng/open_vins/pull/186/hovercard" _istranslated="1">PR#117</a> 了解详情。</li>
<li _msttexthash="675885639" _msthash="298"><strong _istranslated="1">2020 年 12 月 1 日</strong> - 发布了改进的内存管理、主动功能点云发布、限制
更新到绑定计算的功能，以及其他小修复。看
v2.3 <a href="https://github.com/rpng/open_vins/pull/117" data-hovercard-type="pull_request" data-hovercard-url="/rpng/open_vins/pull/117/hovercard" _istranslated="1">PR#117</a> 了解详情。</li>
<li _msttexthash="613178930" _msthash="299"><strong _istranslated="1">2020 年 11 月 18 日</strong> - 发布了 groundtruth 生成实用程序包 <a href="https://github.com/rpng/vicon2gt" _istranslated="1">vicon2gt</a>，支持在动作捕捉室中创建 groundtruth 轨迹，以评估 VIO 方法。</li>
<li _msttexthash="505923561" _msthash="300"><strong _istranslated="1">2020 年 7 月 7 日</strong> - 发布了机体应用程序的零速度更新和站立时的直接初始化
还。有关详细信息，请参阅 <a href="https://github.com/rpng/open_vins/pull/79" data-hovercard-type="pull_request" data-hovercard-url="/rpng/open_vins/pull/79/hovercard" _istranslated="1">PR#79</a>。</li>
<li _msttexthash="1280854926" _msthash="301"><strong _istranslated="1">2020 年 5 月 18 日</strong> - 发布了辅助姿势图示例
基于 <a href="https://github.com/rpng/ov_secondary" _istranslated="1">ov_secondary</a> 存储库
在 <a href="https://github.com/HKUST-Aerial-Robotics/VINS-Fusion" _istranslated="1">VINS-Fusion</a> 上。OpenVINS 现在发布边缘化特征
track、feature 3d position 和 first camera intrinsics 和 extrinsics。
有关详细信息和讨论，请参阅 <a href="https://github.com/rpng/open_vins/pull/66" data-hovercard-type="pull_request" data-hovercard-url="/rpng/open_vins/pull/66/hovercard" _istranslated="1">PR#66</a>。</li>
<li _msttexthash="1127327045" _msthash="302"><strong _istranslated="1">2020 年 4 月 3 日</strong> - 发布了代码库的 <a href="https://github.com/rpng/open_vins/releases/tag/v2.0" _istranslated="1">v2.0</a> 更新，其中包含
一些关键的重构、无 ROS 构建、改进的数据集支持和单个反深度特征表示。
有关详细信息，请查看<a href="https://github.com/rpng/open_vins/releases/tag/v2.0" _istranslated="1">发布页面</a>。</li>
<li _msttexthash="632703851" _msthash="303"><strong _istranslated="1">2020 年 1 月 21 日</strong> - 我们的论文已被 <a href="https://www.icra2020.org/" rel="nofollow" _istranslated="1">ICRA 2020</a> 接受呈报。我们看
期待在那里见到大家！我们还添加了一些系统在不同
数据。</li>
<li _msttexthash="726340966" _msthash="304"><strong _istranslated="1">2019 年 10 月 23 日</strong> - OpenVINS 在 <a href="http://rpg.ifi.uzh.ch/uzh-fpv.html" rel="nofollow" _istranslated="1">IROS 2019 FPV 无人机赛车 VIO 比赛中</a>获得第一名。我们将在
<a href="https://wp.nyu.edu/workshopiros2019mav/" rel="nofollow" _istranslated="1">11</a> 月 8 日中午 12：45 在澳门举行的研讨会。</li>
<li _msttexthash="757121547" _msthash="305"><strong _istranslated="1">2019 年 10 月 1 日</strong> - 我们将在 <a href="https://www.iros2019.org/" rel="nofollow" _istranslated="1">IROS 2019</a> 的<a href="http://udel.edu/~ghuang/iros19-vins-workshop/index.html" rel="nofollow" _istranslated="1">视觉惯性导航：挑战和应用</a>研讨会上发表演讲。这
提交的研讨会论文可以在<a href="http://udel.edu/~ghuang/iros19-vins-workshop/papers/06.pdf" rel="nofollow" _istranslated="1">此</a>链接中找到。</li>
<li _msttexthash="72389434" _msthash="306"><strong _istranslated="1">2019 年 8 月 21 日</strong> <a href="https://github.com/rpng/ov_maplab" _istranslated="1">ov_maplab</a>- 用于将 OpenVINS 与
<a href="https://github.com/ethz-asl/maplab" _istranslated="1">MapLab</a> 库。</li>
<li _msttexthash="187631639" _msthash="307"><strong _istranslated="1">2019 年 8 月 15 日</strong> - OpenVINS 存储库和文档网站的初始版本！</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="14488292" _msthash="308">项目特色</h2><a id="user-content-project-features" class="anchor" aria-label="永久链接：项目功能" href="#project-features" _mstaria-label="636077" _msthash="309"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li _msttexthash="30547569" _msthash="310">滑动窗口视觉惯性 MSCKF</li>
<li _msttexthash="30234594" _msthash="311">模协方差类型系统</li>
<li _msttexthash="31407142" _msthash="312">全面的文档和衍生</li>
<li><font _mstmutation="1" _msttexthash="45956144" _msthash="313">可扩展的视觉惯性模拟器</font><ul dir="auto">
<li _msttexthash="46781566" _msthash="314">在歧管 SE（3） b 样条上</li>
<li _msttexthash="28963246" _msthash="315">任意数量的摄像机</li>
<li _msttexthash="23943114" _msthash="316">任意传感器速率</li>
<li _msttexthash="20003308" _msthash="317">自动生成特征</li>
</ul>
</li>
<li><font _mstmutation="1" _msttexthash="35657388" _msthash="318">五种不同的特征表示</font><ol dir="auto">
<li _msttexthash="4387240" _msthash="319">全局 XYZ</li>
<li _msttexthash="13986245" _msthash="320">全局反深度</li>
<li _msttexthash="5947006" _msthash="321">锚定 XYZ</li>
<li _msttexthash="15546011" _msthash="322">锚定反深度</li>
<li _msttexthash="20397741" _msthash="323">锚定 MSCKF 反深度</li>
<li _msttexthash="19001736" _msthash="324">锚定单反深度</li>
</ol>
</li>
<li><font _mstmutation="1" _msttexthash="45511752" _msthash="325">传感器 intrinsics 和 extrinsics 的校准</font><ul dir="auto">
<li _msttexthash="27904500" _msthash="326">摄像头到 IMU 的转换</li>
<li _msttexthash="45290882" _msthash="327">相机到 IMU 的时间偏移量</li>
<li _msttexthash="19836388" _msthash="328">相机内部函数</li>
<li _msttexthash="59677644" _msthash="329">惯性本征（包括 g 灵敏度）</li>
</ul>
</li>
<li><font _mstmutation="1" _msttexthash="14524874" _msthash="330">环境 SLAM 特性</font><ul dir="auto">
<li _msttexthash="31409118" _msthash="331">OpenCV ARUCO 标签 SLAM 特性</li>
<li _msttexthash="23427638" _msthash="332">稀疏特征 SLAM 特征</li>
</ul>
</li>
<li><font _mstmutation="1" _msttexthash="23516454" _msthash="333">视觉跟踪支持</font><ul dir="auto">
<li _msttexthash="14065701" _msthash="334">单目摄像头</li>
<li _msttexthash="45486740" _msthash="335">立体摄像头（同步）</li>
<li _msttexthash="41338843" _msthash="336">双目相机（同步）</li>
<li _msttexthash="25260794" _msthash="337">基于 KLT 或描述符</li>
<li _msttexthash="15112162" _msthash="338">蒙版跟踪</li>
</ul>
</li>
<li _msttexthash="36346518" _msthash="339">静态和动态状态初始化</li>
<li _msttexthash="30244305" _msthash="340">零速度检测和更新</li>
<li _msttexthash="312523458" _msthash="341">在 EuRocMav、TUM-VI、UZH-FPV、KAIST Urban 和其他 VIO 数据集上进行开箱即用的评估</li>
<li _msttexthash="87227829" _msthash="342">广泛的评估套件（ATE、RPE、NEES、RMSE 等）</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="14520597" _msthash="343">代码库扩展</h2><a id="user-content-codebase-extensions" class="anchor" aria-label="永久链接： 代码库扩展" href="#codebase-extensions" _mstaria-label="772135" _msthash="344"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li>
<p dir="auto" _msttexthash="7879900821" _msthash="345"><strong _istranslated="1"><a href="https://github.com/rpng/ov_plane" _istranslated="1">ov_plane</a></strong> - 一种实时单目视觉惯性里程计 （VIO） 系统，它利用
环境平面。它的核心是一种高效、稳健的基于单筒望远镜的平面检测算法，该算法
不需要额外的传感模式，例如立体、深度相机或神经网络。平面检测和跟踪
算法能够将点特征实时正则化到环境平面，这些环境平面要么保持
向量作为长寿命平面，或为了效率而被边缘化。平面规则适用于状态内 SLAM 和
状态外 MSCKF 点特征，由于平面的空间体积大，因此能够实现长期的点到平面闭环。</p>
</li>
<li>
<p dir="auto" _msttexthash="3919677424" _msthash="346"><strong _istranslated="1"><a href="https://github.com/rpng/vicon2gt" _istranslated="1">vicon2gt</a></strong> - 创建此实用程序是为了使用
用于评估视觉惯性估计系统的运动捕捉系统（例如 Vicon 或 OptiTrack）。
具体来说，我们计算相机频率下的惯性 IMU 状态（全 15 dof），并生成一个真实值
轨迹类似于 EurocMav 数据集提供的轨迹。执行惯性和动作捕捉的融合
信息，并估计两个传感器之间的所有未知时空校准。</p>
</li>
<li>
<p dir="auto" _msttexthash="5440361667" _msthash="347"><strong _istranslated="1"><a href="https://github.com/rpng/ov_maplab" _istranslated="1">ov_maplab</a></strong> - 此代码库包含用于导出的接口包装器
视觉惯性从 <a href="https://github.com/rpng/open_vins" _istranslated="1">OpenVINS</a> 运行到所获取的 ViMap 结构
由 <a href="https://github.com/ethz-asl/maplab" _istranslated="1">MapLab</a> 提供。状态估计值和原始图像作为 ViMap 附加
OpenVINS 通过数据集运行。数据集完成后，特征将重新提取并进行三角测量
MapLab 的功能系统。这可用于合并多会话映射，或在第一个
通过 OpenVINS 运行数据。提供了一些示例以及用于导出轨迹的辅助脚本
转换为标准的 groundtruth 格式。</p>
</li>
<li>
<p dir="auto" _msttexthash="8462748411" _msthash="348"><strong _istranslated="1"><a href="https://github.com/rpng/ov_secondary" _istranslated="1">ov_secondary</a></strong> - 这是一个提供循环的辅助线程示例
closure 的 <a href="https://github.com/rpng/open_vins" _istranslated="1">OpenVINS</a> 的 Closure 方法。这是对
代码最初由香港科技大学航空机器人小组开发，可在
他们的 <a href="https://github.com/HKUST-Aerial-Robotics/VINS-Fusion" _istranslated="1">VINS-Fusion</a> 存储库。这里我们强调这是一个
松散耦合的方法，因此不会将任何信息返回给 estimator 来改进底层 OpenVINS 里程计。
此代码库在几个关键方面进行了修改，包括：公开更多循环闭包参数、订阅
相机内部函数，简化配置，只需提供主题，并对循环进行一些调整
瓶盖检测以提高频率。</p>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="15019212" _msthash="349">演示视频</h2><a id="user-content-demo-videos" class="anchor" aria-label="永久链接： Demo Videos" href="#demo-videos" _mstaria-label="431015" _msthash="350"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<a href="http://www.youtube.com/watch?v=KCX51GvYGss" rel="nofollow">
   <img src="https://raw.githubusercontent.com/rpng/open_vins/master/docs/youtube/KCX51GvYGss.jpg" width="120" height="90" style="max-width: 100%;">
</a>
<a href="http://www.youtube.com/watch?v=Lc7VQHngSuQ" rel="nofollow">
   <img src="https://raw.githubusercontent.com/rpng/open_vins/master/docs/youtube/Lc7VQHngSuQ.jpg" width="120" height="90" style="max-width: 100%;">
</a>
<a href="http://www.youtube.com/watch?v=vaia7iPaRW8" rel="nofollow">
   <img src="https://raw.githubusercontent.com/rpng/open_vins/master/docs/youtube/vaia7iPaRW8.jpg" width="120" height="90" style="max-width: 100%;">
</a>
<a href="http://www.youtube.com/watch?v=MCzTF9ye2zw" rel="nofollow">
   <img src="https://raw.githubusercontent.com/rpng/open_vins/master/docs/youtube/MCzTF9ye2zw.jpg" width="120" height="90" style="max-width: 100%;">
</a>
<a href="http://www.youtube.com/watch?v=eSQLWcNrx_I" rel="nofollow">
   <img src="https://raw.githubusercontent.com/rpng/open_vins/master/docs/youtube/eSQLWcNrx_I.jpg" width="120" height="90" style="max-width: 100%;">
</a>
<br>
<a href="http://www.youtube.com/watch?v=187AXuuGNNw" rel="nofollow">
   <img src="https://raw.githubusercontent.com/rpng/open_vins/master/docs/youtube/187AXuuGNNw.jpg" width="120" height="90" style="max-width: 100%;">
</a>
<a href="http://www.youtube.com/watch?v=oUoLlrFryk0" rel="nofollow">
   <img src="https://raw.githubusercontent.com/rpng/open_vins/master/docs/youtube/oUoLlrFryk0.jpg" width="120" height="90" style="max-width: 100%;">
</a>
<a href="http://www.youtube.com/watch?v=ExPIGwORm4E" rel="nofollow">
   <img src="https://raw.githubusercontent.com/rpng/open_vins/master/docs/youtube/ExPIGwORm4E.jpg" width="120" height="90" style="max-width: 100%;">
</a>
<a href="http://www.youtube.com/watch?v=lXHl-qgLGl8" rel="nofollow">
   <img src="https://raw.githubusercontent.com/rpng/open_vins/master/docs/youtube/lXHl-qgLGl8.jpg" width="120" height="90" style="max-width: 100%;">
</a>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="12708007" _msthash="351">信用 / 许可</h2><a id="user-content-credit--licensing" class="anchor" aria-label="永久链接： 信用 / 许可" href="#credit--licensing" _mstaria-label="653302" _msthash="352"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="2159969838" _msthash="353">此代码由<a href="https://sites.udel.edu/robot/" rel="nofollow" _istranslated="1">机器人感知和导航小组 （RPNG）</a> 编写，网址为
特拉华大学。如果您对代码有任何问题，请在我们的 github 页面上打开一个问题，并提供相关的
实现详细信息和参考。对于利用或比较这项工作的研究人员，请引用
以后：</p>
<div class="highlight highlight-text-adblock notranslate position-relative overflow-auto" dir="auto"><pre>@Conference{Geneva2020ICRA,
  Title      = {{OpenVINS}: A Research Platform for Visual-Inertial Estimation},
  Author     = {Patrick Geneva and Kevin Eckenhoff and Woosik Lee and Yulin Yang and Guoquan Huang},
  Booktitle  = {Proc. of the IEEE International Conference on Robotics and Automation},
  Year       = {2020},
  Address    = {Paris, France},
  Url        = {\url{https://github.com/rpng/open_vins}}
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="@Conference{Geneva2020ICRA,
  Title      = {{OpenVINS}: A Research Platform for Visual-Inertial Estimation},
  Author     = {Patrick Geneva and Kevin Eckenhoff and Woosik Lee and Yulin Yang and Guoquan Huang},
  Booktitle  = {Proc. of the IEEE International Conference on Robotics and Automation},
  Year       = {2020},
  Address    = {Paris, France},
  Url        = {\url{https://github.com/rpng/open_vins}}
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto" _msttexthash="1558311326" _msthash="354">代码库和文档根据 <a href="https://www.gnu.org/licenses/gpl-3.0.txt" rel="nofollow" _istranslated="1">GNU 通用公共许可证 v3 （GPL-3）</a> 获得许可。
您必须在衍生作品中保留版权和许可证声明，并在相同的许可证下提供完整的源代码和修改（<a href="https://choosealicense.com/licenses/gpl-3.0/" rel="nofollow" _istranslated="1">请参阅此处</a>;这不是法律建议）。</p>
</article></div>
