附录D 温差作用效应计算公式
==============================================================================

.. raw:: html

  <h2 id="test111">附录D 温差作用效应计算公式</h2>


.. raw:: html

 <div align="center"><img id="figD.0.1" src="./_static/fig/D.0.1.png" alt="Picture" width="300px"></div>
  <p style="color: dimgray;text-align: center;">图 D.0.1 温差计算</p>
  <script type="text/javascript">var viewer = new Viewer(document.getElementById('figD.0.1'));</script>

 <p style="text-align:justify"><a href="#idD.0.1"> D.0.1</a> <span id="idD.0.1"> 简支梁温差应力按下列公式计算</span></p>  

$$ N_{\\mathrm{t} }=\\sum A_{\\mathrm{y}}t_{\\mathrm{y}}\\alpha _{\\mathrm{c}}E_{\\mathrm{c}}\\tag{D.0.1-1}$$ 
$$M^{0}_{\\mathrm{t} }=-\\sum A_{\\mathrm{y}}t_{\\mathrm{y}}\\alpha _{\\mathrm{c}}E_{\\mathrm{c}}e_{\\mathrm{y} }\\tag{D.0.1-2}$$ 


.. raw:: html

 <p style="text-align:justify;text-indent:2em;" > 1)正温差应力</p>

$$\\sigma _{\\mathrm{t} }=\\dfrac{-N_{\\mathrm{t} }}{A_{0}}+\\dfrac{M^{0}_{\\mathrm{t} }}{I_{0}}\\mathrm{y} +t_{\\mathrm{y}}\\alpha _{\\mathrm{c}}E_{\\mathrm{c}}\\tag{D.0.1-3}$$ 


.. raw:: html

 <p style="text-align:justify;text-indent:2em;" > 2)反温差应力，公式(D.0.1-1)、公式(D.0.1-2)、公式(D.0.1-3)内<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>t</mi><mrow><mrow><mi mathvariant="normal">y</mi></mrow></mrow></msub></math>取负值，按公式(D.0.1-3)计算。</p>

 <table border="0" style="font-family:times new roman" id="gongshi">
 <tr>
 <td width="40px" align='center' id="eqzs">式中:</td>
 <td width="40px" align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>A</mi><mrow><mrow><mi mathvariant="normal">y</mi></mrow></mrow></msub></math></td>
 <td width="40px" align='left' id="eqzs">——</td>
 <td id="eqzs">截面内的单元面积；</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>t</mi><mrow><mrow><mi mathvariant="normal">y</mi></mrow></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">单元面积<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>A</mi><mrow><mrow><mi mathvariant="normal">y</mi></mrow></mrow></msub></math>内温差梯度平均值，均以正值代入；</td>
 </tr> 
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>α</mi><mrow><mrow><mi mathvariant="normal">c</mi></mrow></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">混凝土线膨胀系数，按《公路桥涵设计通用规范》JTG D60的规定采用；</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>E</mi><mrow><mn>0</mn></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">混凝土弹性模量；</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs">y</td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">计算应力点至换算截面重心轴的距离，重心轴以上取正值，以下取负值；</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>e</mi><mrow><mrow><mi mathvariant="normal">y</mi></mrow></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">单元面积<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>A</mi><mrow><mrow><mi mathvariant="normal">y</mi></mrow></mrow></msub></math>重心至换算截面重心轴的距离，重心轴以上取正值，以下取负值；</td>
 </tr> 
 <tr>
 <td  align='right' id="eqzs"colspan="2"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>A</mi><mrow><mn>0</mn></mrow></msub><mo>、</mo><msub><mi>I</mi><mrow><mn>0</mn></mrow></msub></math></td>
 <!-- <td></td> -->
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">换算截面面积和惯性矩。</td>
 </tr> 
 </table>
 <p></p>

 <p style="text-align:justify"><a href="#idD.0.2"> D.0.2</a> <span id="idD.0.2"> 连续梁温差应力尚应计入温度作用次弯矩<math xmlns="http://www.w3.org/1998/Math/MathML"><msubsup><mi>M</mi><mrow><mi mathvariant="normal">t</mi></mrow><mrow><msup><mi></mi><mo>′</mo></msup></mrow></msubsup></math>，此时公式(D.0.1-3)右边第2项内弯矩<math xmlns="http://www.w3.org/1998/Math/MathML" ><msubsup><mi>M</mi><mrow><mi mathvariant="normal">t</mi></mrow><mrow><mn>0</mn></mrow></msubsup></math>应改以<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>M</mi><mrow><mrow><mi mathvariant="normal">t</mi></mrow></mrow></msub><mo>=</mo><msubsup><mi>M</mi><mrow><mrow><mi mathvariant="normal">t</mi></mrow></mrow><mrow><msup><mi></mi><mo>′</mo></msup></mrow></msubsup><mo>+</mo><msubsup><mi>M</mi><mrow><mrow><mi mathvariant="normal">t</mi></mrow></mrow><mrow><mn>0</mn></mrow></msubsup></math>代之。</span></p>  

:math:`\ `	 