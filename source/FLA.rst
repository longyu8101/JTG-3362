附录A 桥梁结构的实用精细化分析模型 (新增)
===================================================

.. raw:: html

  <h2 id="test111">附录A 桥梁结构的实用精细化分析模型 (新增)</h2>

A.1  一般规定
----------------------

.. raw:: html

 <p style="text-align:justify"><a href="#idA.1.1"> A.1.1</a> <span id="idA.1.1">  桥梁结构的实用精细化分析宜采用本附录的空间网格模型、折面梁格模型和7自由度单梁模型。</span></p>  
 <p style="text-align:justify"><a href="#idA.1.2"> A.1.2</a> <span id="idA.1.2">  空间网格模型宜用于腹板间距不小于5 m的混凝土箱梁。</span></p>  
 <p style="text-align:justify"><a href="#idA.1.3"> A.1.3</a> <span id="idA.1.3">  折面梁格模型宜用于多梁式的装配式桥梁或单箱多室混凝土箱梁。</span></p>  
 <p style="text-align:justify"><a href="#idA.1.4"> A.1.4</a> <span id="idA.1.4">  7自由度梁单元模型宜用于位于曲线段的混凝土箱梁桥。</span></p>     

A.2  应用原则
----------------------

.. raw:: html

 <p style="text-align:justify"><a href="#idA.2.1"> A.2.1</a> <span id="idA.2.1">  空间网格模型宜满足下列要求：</span></p>  
 <p style="text-align:justify;text-indent:2em;" > 1 纵向梁格的宽度<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>b</mi><mrow><mrow><mi mathvariant="normal">n</mi></mrow></mrow></msub></math>不大于2 m，工字型截面的翼缘宽度<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>b</mi><mrow><mrow><mi mathvariant="normal">f</mi></mrow></mrow></msub></math>不大于<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>6h</mi><mrow><mrow><mi mathvariant="normal">f</mi></mrow></mrow></msub></math>(<a href="#figA.2.1">图 A.2.1</a>)。</p>
 <div align="center"><img id="figA.2.1" src="./_static/fig/A.2.1.png" alt="Picture" width="400px"></div>
 <p style="color: dimgray;text-align: center;">图 A.2.1 空间网格模型示意</p>
 <script type="text/javascript">var viewer = new Viewer(document.getElementById('figA.2.1'));</script>
 <p style="text-align:justify;text-indent:2em;" > 2 配有钢束的腹板截面，不宜划分为多个纵向梁格。当带平弯的预应力钢筋横向穿过多个纵向梁格时，预应力钢筋穿过最长距离的纵向梁格应计入预应力钢筋预加力效应。</p>
  
 <p style="text-align:justify"><a href="#idA.2.2"> A.2.2</a> <span id="idA.2.2">  折面梁格模型宜满足下列要求：</span></p>  
 <p style="text-align:justify;text-indent:2em;" > 1 纵向梁格的宽度<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>b</mi><mrow><mrow><mi mathvariant="normal">n</mi></mrow></mrow></msub></math>不大于3 m，工字型截面的翼缘宽度<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>b</mi><mrow><mrow><mi mathvariant="normal">f</mi></mrow></mrow></msub></math>不大于<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>6h</mi><mrow><mrow><mi mathvariant="normal">f</mi></mrow></mrow></msub></math>(<a href="#figA.2.2">图 A.2.2</a>)。</p>
 <div align="center"><img id="figA.2.2" src="./_static/fig/A.2.2.png" alt="Picture" width="400px"></div>
 <p style="color: dimgray;text-align: center;">图 A.2.2 折面梁格模型示意</p>
 <script type="text/javascript">var viewer = new Viewer(document.getElementById('figA.2.2'));</script>
 <p style="text-align:justify;text-indent:2em;" > 2 配有钢束的腹板截面，不宜划分为多个纵向梁格。当带平弯的预应力钢筋横向穿过多个纵向梁格时，预应力钢筋穿过最长距离的纵向梁格应计入预应力钢筋预加力效应。</p>
 
 
 <p style="text-align:justify"><a href="#idA.2.3"> A.2.3</a> <span id="idA.2.3"> 7 自由度单梁模型宜满足下列要求：</span></p>   
 <p style="text-align:justify;text-indent:2em;" > 1 7自由度单梁模型可按4.3.4条的有效分布宽度考虑剪力滞效应。</p>
 <p style="text-align:justify;text-indent:2em;" > 2 7自由度单梁模型得到的正应力放大系数<math xmlns="http://www.w3.org/1998/Math/MathML"><msub><mi>λ</mi><mrow><mrow><mi>σ</mi></mrow></mrow></msub></math>和剪应力放大系数<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>λ</mi><mrow><mrow><mi>τ</mi></mrow></mrow></msub></math>按下式计算：</p>

$$\\lambda _{\\sigma}=\\dfrac{\\sigma _{\\mathrm{M}}+\\sigma _{\\mathrm{W}}}{\\sigma _{\\mathrm{M}}}\\tag{A.2.3-1}$$ 
$$\\lambda _{\\tau }=\\dfrac{\\tau  _{\\mathrm{M}}+\\tau  _{\\mathrm{K}}+\\tau  _{\\mathrm{W}}}{\\tau _{\\mathrm{M}}}\\tag{A.2.3-2}$$ 

.. raw:: html 

 <table border="0" style="font-family:times new roman" id="gongshi">
 <tr>
 <td width="40px" align='center' id="eqzs">式中:</td>
 <td width="60px" align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>σ</mi><mrow><mrow><mi mathvariant="normal">M</mi></mrow></mrow></msub><mo>、</mo><msub><mi>τ</mi><mrow><mrow><mi mathvariant="normal">M</mi></mrow></mrow></msub></math></td>
 <td width="40px" align='left' id="eqzs">——</td>
 <td id="eqzs">弯曲正应力和剪应力。</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>σ</mi><mrow><mrow><mi mathvariant="normal">W</mi></mrow></mrow></msub><mo>、</mo><msub><mi>τ</mi><mrow><mrow><mi mathvariant="normal">W</mi></mrow></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">约束扭转正应力和剪应力；</td>
 </tr> 
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>τ</mi><mrow><mrow><mi mathvariant="normal">K</mi></mrow></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">自由扭转剪应力。</td>
 </tr> 
 </table>
 <p></p>  


:math:`\ `	  