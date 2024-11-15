附录B 拉压杆模型分析方法 (新增)
===================================================

.. raw:: html

  <h2 id="test111">附录B 拉压杆模型分析方法 (新增)</h2>

B.1  一般规定
----------------------

.. raw:: html

 <p style="text-align:justify"><a href="#idB.1.1"> B.1.1</a> <span id="idB.1.1"> 混凝土桥梁的应力扰动区范围，宜根据圣维南原理确定。</span></p>  
 <p style="text-align:justify"><a href="#idB.1.2"> B.1.2</a> <span id="idB.1.2"> 混凝土桥梁的应力扰动区，可采用拉压杆模型按如下步骤进行简化分析：</span></p>  
 <ol>
 <li>根据结构边界条件及受力情况，确定应力扰动区的范围(见<a href="#idB.1.1">第B.1.1条</a>)。</li>
 <li>构建应力扰动区的拉压杆模型(见<a href="#b-2">B.2节</a>)。</li>
 <li>根据应力扰动区边界上的作用力设计值和拉压杆模型的受力平衡条件，求解模型中各杆件的内力设计值。</li>
 <li>进行拉杆、压杆和节点的强度验算(见<a href="#b-3">B.3节</a>),确认拉杆、压杆和节点区域所选择的材料强度、配筋及构造尺寸是否满足要求。</li>
 <li>若验算不能通过，则需要对拉压杆模型的构形甚至结构尺寸进行调整，并重复以上步骤；若验算通过，再根据构造要求进行详细配筋设计，并且构件表面的构造分布钢筋应满足<a href="#idB.3.5">第B.3.5条</a>的规定。</li> 
 </ol>

B.2 构建方法
----------------------

.. raw:: html

 <p style="text-align:justify"><a href="#idB.2.1"> B.2.1</a> <span id="idB.2.1"> 拉压杆模型应满足受力平衡条件，并正确反映混凝土结构内部的力流传递特征。</span></p>  


 <p style="text-align:justify"><a href="#idB.2.2"> B.2.2</a> <span id="idB.2.2"> 构建拉压杆模型可采用荷载路径法、应力迹线法、力流线法、最小应变能准则、最大强度准则等方法。</span></p>  

 
 <p style="text-align:justify"><a href="#idB.2.3"> B.2.3</a> <span id="idB.2.3"> 拉压杆模型中，拉杆与压杆之间的最小夹角不宜小于25°。</span></p>   


B.3 验算内容
----------------------

.. raw:: html

 <p style="text-align:justify"><a href="#idB.3.1"> B.3.1</a> <span id="idB.3.1">  拉压杆模型的拉杆、压杆和节点，应按下式进行承载力验算：</span></p>  

$$\\gamma _{0}S_{\\mathrm{STM,d}}\\leqslant R_{\\mathrm{STM,d}}\\tag{B.3.1}$$ 

.. raw:: html 

 <table border="0" style="font-family:times new roman" id="gongshi">
 <tr>
 <td width="50px" align='center' id="eqzs">式中:</td>
 <td width="60px" align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>S</mi><mrow><mrow><mi mathvariant="normal">STM,d</mi></mrow></mrow></msub></math></td>
 <td width="40px" align='left' id="eqzs">——</td>
 <td id="eqzs">拉压杆模型的作用效应设计值，对于拉杆、压杆和节点分别记为<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>S</mi><mrow><mrow><mi mathvariant="normal">T,d</mi></mrow></mrow></msub></math>,、<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>S</mi><mrow><mrow><mi mathvariant="normal">S,d</mi></mrow></mrow></msub></math>和<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>S</mi><mrow><mrow><mi mathvariant="normal">N,d</mi></mrow></mrow></msub></math>;</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>R</mi><mrow><mrow><mi mathvariant="normal">STM,d</mi></mrow></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">拉压杆模型的承载力设计值，对于拉杆、压杆和节点分别记为<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>R</mi><mrow><mrow><mi mathvariant="normal">T,d</mi></mrow></mrow></msub></math>、<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>R</mi><mrow><mrow><mi mathvariant="normal">s,d</mi></mrow></mrow></msub></math>和<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>R</mi><mrow><mrow><mi mathvariant="normal">N,d</mi></mrow></mrow></msub></math>。</td>
 </tr> 
 </table>
 <p></p> 


 <p style="text-align:justify"><a href="#idB.3.2"> B.3.2</a> <span id="idB.3.2">  拉杆应配置普通钢筋或预应力钢筋，其承载力设计值应按下式计算：</span></p>  

$$R_{\\mathrm{T,d}}= f_{\\mathrm{sd}}A_{\\mathrm{s}}+f_{\\mathrm{pd}}A_{\\mathrm{p}}\\tag{B.3.2}$$ 

.. raw:: html 

 <table border="0" style="font-family:times new roman" id="gongshi">
 <tr>
 <td width="50px" align='center' id="eqzs">式中:</td>
 <td width="40px" align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>f</mi><mrow><mrow><mi mathvariant="normal">sd</mi></mrow></mrow></msub></math></td>
 <td width="40px" align='left' id="eqzs">——</td>
 <td id="eqzs">普通钢筋抗拉强度设计值；</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>f</mi><mrow><mrow><mi mathvariant="normal">pd</mi></mrow></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">预应力钢筋抗拉强度设计值；</td>
 </tr> 
 <tr>
 <td  align='right' id="eqzs" colspan="2"> <math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>A</mi><mrow><mrow><mi mathvariant="normal">s</mi></mrow></mrow></msub></math>、<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>A</mi><mrow><mrow><mi mathvariant="normal">p</mi></mrow></mrow></msub></math></td>
 <!-- <td></td> -->
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">杆中的普通钢筋截面面积和预应力钢筋截面面积。</td>
 </tr>  
 </table>
 <p></p> 


 <p style="text-align:justify"><a href="#idB.3.3"> B.3.3</a> <span id="idB.3.3">  混凝土压杆的承载力设计值应按下列规定计算：</span></p>  
 <p style="text-align:justify;text-indent:2em;" > 1 无配筋混凝土压杆</p>

$$R_{\\mathrm{S,d}}=f_{\\mathrm{ce,d} }A_{\\mathrm{cs} }\\tag{B.3.3-1}$$ 

$$f_{\\mathrm{ce,d}}=\\dfrac{\\beta_{\\mathrm{c} }f_{\\mathrm{cd}}}{0.8+170\\varepsilon _{1}}\\leqslant 0.85\\beta_{\\mathrm{c}} f_{\\mathrm{cd}}\\tag{B.3.3-2}$$ 

$$\\varepsilon _{1}=\\varepsilon _{\\mathrm{s}}+(\\varepsilon _{\\mathrm{s}}+0.002)\\cot^{2}\\theta _{\\mathrm{s} }\\tag{B.3.3-3}$$ 

.. raw:: html 

 <table border="0" style="font-family:times new roman" id="gongshi">
 <tr>
 <td width="50px" align='center' id="eqzs">式中:</td>
 <td width="60px" align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>A</mi><mrow><mrow><mi mathvariant="normal">cs</mi></mrow></mrow></msub></math></td>
 <td width="40px" align='left' id="eqzs">——</td>
 <td id="eqzs">土压杆的有效横截面积，根据<a href="#figB.3.3.1">图B.3.3-1</a>、<a href="#figB.3.3.2">图B.3.3-2</a>或<a href="#figB.3.3.3">图B.3.3-3</a>确定；</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>f</mi><mrow><mrow><mi mathvariant="normal">ce,d</mi></mrow></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">混凝土压杆的等效抗压强度设计值；</td>
 </tr> 
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>f</mi><mrow><mrow><mi mathvariant="normal">cd</mi></mrow></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">混凝土轴心抗压强度设计值；</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>β</mi><mrow><mrow><mi mathvariant="normal">c</mi></mrow></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">与混凝土强度等级有关参数，对C25~C50取1.30,C55~C80取1.35;</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>ε</mi><mrow><mrow><mi mathvariant="normal">1</mi></mrow></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">压杆中垂直于压杆方向的混凝土拉应变；</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>θ</mi><mrow><mrow><mi mathvariant="normal">s</mi></mrow></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">压杆和相邻拉杆间的最小角度，且<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>θ</mi><mrow><mi>s</mi></mrow></msub><mo>⩾</mo><msup><mn>25</mn><mrow><mo>∘</mo></mrow></msup></math>;</td>
 </tr>
  <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>ε</mi><mrow><mrow><mi mathvariant="normal">s</mi></mrow></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">拉杆方向钢筋的拉应变。当拉杆由普通钢筋组成时，按拉杆的作用组合内力设计值计算；若拉杆为预应力钢筋，在其周边混凝土未消压前取<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>ε</mi><mrow><mrow><mi mathvariant="normal">s</mi></mrow></mrow></msub><mo>=</mo><mn>0.0</mn></math>，在消压之后取<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>ε</mi><mrow><mrow><mi mathvariant="normal">s</mi></mrow></mrow></msub><mo>=</mo><mo stretchy="false">(</mo><msub><mi>f</mi><mrow><mrow><mi mathvariant="normal">p</mi><mi mathvariant="normal">d</mi></mrow></mrow></msub><mo>−</mo><msub><mi>f</mi><mrow><mrow><mi mathvariant="normal">p</mi><mi mathvariant="normal">e</mi></mrow></mrow></msub><mo stretchy="false">)</mo><mrow><mo>/</mo></mrow><msub><mi>E</mi><mrow><mrow><mi mathvariant="normal">p</mi></mrow></mrow></msub></math>。</td>
 </tr>
 </table>
 <p></p> 


 <div align="center"><img id="figB.3.3.1" src="./_static/fig/B.3.3.1.png" alt="Picture" width="300px"></div>
 <p style="color: dimgray;text-align: center;">图 B.3.3-1 由钢筋锚固所形成的的压杆和CTT节点区</p>
 <script type="text/javascript">var viewer = new Viewer(document.getElementById('figB.3.3.1'));</script>

  <div align="center"><img id="figB.3.3.2" src="./_static/fig/B.3.3.2.png" alt="Picture" width="150px"></div>
 <p style="color: dimgray;text-align: center;">图 B.3.3-2 由钢筋和支承约束形成的压杆和CCT节点区</p>
 <script type="text/javascript">var viewer = new Viewer(document.getElementById('figB.3.3.2'));</script>

  <div align="center"><img id="figB.3.3.3" src="./_static/fig/B.3.3.3.png" alt="Picture" width="150px"></div>
 <p style="color: dimgray;text-align: center;">图 B.3.3-3 集中力下的压杆和CCC节点区</p>
 <script type="text/javascript">var viewer = new Viewer(document.getElementById('figB.3.3.3'));</script>


 <table border="0" style="font-family:times new roman" id="gongshi">
 <tr>
 <td width="50px" align='center' id="eqzs">图中:</td>
 <td width="40px" align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>d</mi><mrow><mrow><mi mathvariant="normal">ba</mi></mrow></mrow></msub></math></td>
 <td width="40px" align='left' id="eqzs">——</td>
 <td id="eqzs">钢筋直径；</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><i>S</i></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">压杆端部锚固钢筋的间距；</td>
 </tr> 
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>L</mi><mrow><mrow><mi mathvariant="normal">a</mi></mrow></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">依靠钢筋锚固节点的有效长度；</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>L</mi><mrow><mrow><mi mathvariant="normal">b</mi></mrow></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">支承垫板的宽度；</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>h</mi><mrow><mrow><mi mathvariant="normal">a</mi></mrow></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">依靠钢筋约束节点的高度；</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>h</mi><mrow><mrow><mi mathvariant="normal">s</mi></mrow></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">依靠压杆约束节点的高度；</td>
 </tr>
  <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>θ</mi><mrow><mrow><mi mathvariant="normal">s</mi></mrow></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">压杆的倾角。</td>
 </tr>

 </table>
 <p></p>  

 <p style="text-align:justify;text-indent:2em;" > 2 配筋混凝土压杆</p>

$$R_{\\mathrm{S,d} }=f_{\\mathrm{ce,d} }A_{\\mathrm{cs} }+f^{'}_{\\mathrm{sd} }A_{\\mathrm{ss} }\\tag{B.3.3-4}$$ 

.. raw:: html 

 <table border="0" style="font-family:times new roman" id="gongshi">
 <tr>
 <td width="40px" align='center' id="eqzs">图中:</td>
 <td width="60px" align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>f</mi><mrow><mrow><mi mathvariant="normal">ce,d</mi></mrow></mrow></msub></math></td>
 <td width="40px" align='left' id="eqzs">——</td>
 <td id="eqzs">混凝土压杆的等效抗压强度设计值；</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>A</mi><mrow><mrow><mi mathvariant="normal">cs</mi></mrow></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">混凝土压杆的有效横截面积；</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>f '</mi><mrow><mrow><mi mathvariant="normal">sd</mi></mrow></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">通钢筋抗压强度设计值；</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>A</mi><mrow><mrow><mi mathvariant="normal">ss</mi></mrow></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">过压杆的钢筋在压杆轴线方向上的截面投影面积。</td>
 </tr>
 </table>
 <p></p>  

 <p style="text-align:justify"><a href="#idB.3.4"> B.3.4</a> <span id="idB.3.4">  节点的承载力设计值，应按下列公式计算：</span></p>  

$$R_{\\mathrm{N,d} }=\\beta_{\\mathrm{n} }f_{\\mathrm{cd} }A_{\\mathrm{n} }\\tag{B.3.4}$$ 

.. raw:: html 

 <table border="0" style="font-family:times new roman" id="gongshi">
 <tr>
 <td width="50px" align='center' id="eqzs">式中:</td>
 <td width="50px" align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>β</mi><mrow><mrow><mi mathvariant="normal">n</mi></mrow></mrow></msub></math></td>
 <td width="40px" align='left' id="eqzs">——</td>
 <td id="eqzs">节点界面的混凝土强度软化系数，按<a href="#BB.3.4">表B.3.4</a>取值；</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>A</mi><mrow><mrow><mi mathvariant="normal">n</mi></mrow></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">节点界面上的截面面积，根据节点类型，按<a href="#figB.3.3.1">图B.3.3-1</a>、<a href="#figB.3.3.2">图B.3.3-2</a>或<a href="#figB.3.3.3">图B.3.3-3</a>计算。</td>
 </tr> 
 </table>
 <p></p>  
      <style>
     #biaoge {
         border: 2px solid black;
         border-collapse: collapse;
         margin-bottom:1px;
        
      }
      th, td {
         padding-top: 5px;
         padding-bottom:5px;
         padding-left:5px;
         padding-right:5px;
         border: 1px solid black;
         
      }
      #eqzs {
         border: 0px;
      }
      #dhbg {
        vertical-align: middle;
      }
     </style>

		<table id="biaoge" style="font-family:times new roman">

         <caption style="caption-side:top;text-align: center;color:black" ><b style="text-align:center"> <div id="BB.3.4">表B.3.4外观劣化度分级标准</b></caption>	
              
		    <tr>
		     <td  align="center" id="dhbg"width="200px">节点类型</td>
		     <td  align="center" id="dhbg"width="500px">意 义</td>
         <td  align="center" id="dhbg"width="200px"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>β</mi><mrow><mrow><mi mathvariant="normal">n</mi></mrow></mrow></msub></math></td>
		    </tr>
		    <tr>
		     <td align="center" id="dhbg">CCC(压-压-压)</td>
		     <td align="center" id="dhbg">杆件和支承面包围的节点区域</td>
				 <td align="center" id="dhbg"><math xmlns="http://www.w3.org/1998/Math/MathML"><mn>0.85</mn><msub><mi>β</mi><mrow><mrow><mi mathvariant="normal">c</mi></mrow></mrow></msub></math></td>
		    </tr>
		    <tr>
		     <td align="center" id="dhbg">CCT(压-压-拉)</td>
		     <td align="center" id="dhbg">单向拉杆锚固的节点区域</td>
				 <td align="center" id="dhbg"><math xmlns="http://www.w3.org/1998/Math/MathML"><mn>0.75</mn><msub><mi>β</mi><mrow><mrow><mi mathvariant="normal">c</mi></mrow></mrow></msub></math></td>
		    </tr>
		    <tr>
		     <td align="center" id="dhbg">CTT(压-拉-压拉)</td>
		     <td align="center" id="dhbg">双向拉杆锚固的节点区域</td>
				 <td align="center" id="dhbg"><math xmlns="http://www.w3.org/1998/Math/MathML"><mn>0.65</mn><msub><mi>β</mi><mrow><mrow><mi mathvariant="normal">c</mi></mrow></mrow></msub></math></td>
		    </tr>               
		</table>
 <p><font size="2">注：对节点区配有约束钢筋的情况，若经过分析或试验验证其有约束增强效果，在本表基础上取值可有所提高。</font></p>

 <p style="text-align:justify"><a href="#idB.3.5"> B.3.5</a> <span id="idB.3.5">  按照拉压杆模型设计的应力扰动区，应在表面配置正交的钢筋网，网格间距不得超过300 mm,钢筋面积对混凝土毛截面积的比值在各个方向不应小于0.3%。</span></p>  


:math:`\ `	 