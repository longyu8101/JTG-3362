附录A 桥梁结构的实用精细化分析模型 (新增)
===================================================

.. raw:: html

  <h2 id="test111">附录A 桥梁结构的实用精细化分析模型 (新增)</h2>

A.1  一般规定
----------------------

.. raw:: html

 <p style="text-align:justify"><a href="#idtA.1.1"> A.1.1</a> <span id="idtA.1.1"> 桥梁结构的实用精细化分析模型主要解决桥梁的空间效应问题，用于弥补单梁模型分析的不足。实用精细化模型针对不同的桥有不同的适用性。</span></p>  
 <ol> 
 <li>空间网格模型可以考虑桥梁全部的空间效应，并可以完整给出<a href="https://jtg-3362.readthedocs.io/zh/latest/06.html#B6.1.3">表6.1.3</a>的验算指标。</li>
 <li>折面梁格模型能考虑箱梁的剪力滞效应以及结构沿横桥向不均匀的弯曲变形，但不能计算截面顶板和底板的水平剪应力，无法校核<a href="https://jtg-3362.readthedocs.io/zh/latest/06.html#B6.1.3">表6.1.3</a>中的顶板主拉应力和底板主拉应力。折面梁格模型可同步分析纵、横向构件，适用于宽箱梁桥的纵、横梁分析。</li>
 <li>7自由度单梁模型适合于薄壁效应显著的箱梁桥，特别是弯箱梁桥的整体分析，可以得到<a href="https://jtg-3362.readthedocs.io/zh/latest/06.html#B6.1.3">表6.1.3</a>中的顶板、底板和腹板的主拉应力。7自由度单梁模型是单梁模型，需要满足全截面的平截面假定，所以不能计算剪力滞效应；此外，桥面板分析、预应力钢束在箱梁底板产生的外崩力效应等，需要另建模型进行分析。</li>
 </ol>
A.2  应用原则
----------------------

.. raw:: html

 <p style="text-align:justify"><a href="#idtA.2.1"> A.2.1</a> <span id="idtA.2.1"> 空间网格模型将复杂的桥梁结构离散成多块板，每一个板元离散成十字交叉的正交梁格，以十字交叉的纵横梁的刚度等代成板的刚度，一片正交梁格就像是一张“网”。至此，桥梁结构采用空间网格来表达，如<a href="#figTA.1">图 A-1</a>。</span></p>  

 <div align="center"><img id="figTA.1" src="../_static/fig/TA.1.png" alt="Picture" width="450px"></div>
  <p style="color: dimgray;text-align: center;">图 A-1 空间网格模型简化原理示意</p>
  <script type="text/javascript">var viewer = new Viewer(document.getElementById('figTA.1'));</script>

 <p style="text-align:justify"><a href="#idtA.2.2"> A.2.2</a> <span id="idtA.2.2"> 折面梁格模型将箱梁截面以垂直于截面主轴方向的切割线切开，保持各纵向梁格的形心位置不变，并采用横向梁格将各纵向梁格联系在一起形成的一个单层的折面格构式模型，如<a href="#figTA.2">图 A-2</a>所示。</span></p>  

  <div align="center"><img id="figTA.2" src="../_static/fig/TA.2.png" alt="Picture" width="450px"></div>
  <p style="color: dimgray;text-align: center;">图 A-2 结构离散及折面梁格模型示意</p>
  <script type="text/javascript">var viewer = new Viewer(document.getElementById('figTA.2'));</script>

 <p style="text-align:justify"><a href="#idtA.2.3"> A.2.3</a> <span id="idtA.2.3"> 采用3自由度或6自由度梁计算时，扭转效应产生正应力和剪应力放大效应是估算的。目前采用的箱梁宽度比以往要宽，统一采用 1.15 的应力放大系数并不准确。以3座预应力混凝土直线箱梁桥(主跨 100 m,箱宽 11.85 m;主跨 268 m,箱宽 16.5 m;主跨130 m,箱宽16.5 m)为样本桥梁，7自由度单梁模型分析结果显示，在<a href="#figTA.3">图 A-3</a>中A点(腹板上缘)、B点(截面重心)、C点(腹板下缘)以及 D点(底板边缘),活载剪应力放大系数为1.5~2.0。</span></p>   

  <div align="center"><img id="figTA.3" src="../_static/fig/TA.3.png" alt="Picture" width="350px"></div>
  <p style="color: dimgray;text-align: center;">图 A-3 箱梁应力计算位置示意</p>
  <script type="text/javascript">var viewer = new Viewer(document.getElementById('figTA.3'));</script>

:math:`\ `	