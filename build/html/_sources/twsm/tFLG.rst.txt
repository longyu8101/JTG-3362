附录G 预应力曲线钢筋由锚具变形、钢筋回缩和接缝压缩引起的考虑反向摩擦后的预应力损失简化计算
=========================================================================================

.. raw:: html

  <h2 id="test111">附录G 预应力曲线钢筋由锚具变形、钢筋回缩和接缝压缩引起的考虑反向摩擦后的预应力损失简化计算</h2>


.. raw:: html

 <p style="text-align:justify"><a href="#idtG.0.2"> G.0.2</a> <span id="idtG.0.2"> 预应力钢筋在扣除管道正摩擦损失后的应力分布，假定为一根直线<math xmlns="http://www.w3.org/1998/Math/MathML"><mi>c</mi><mi>a</mi><msup><mi>a</mi><mrow><msup><mi></mi><mo>′</mo></msup></mrow></msup></math>(见<a href="#figTG.1">图 G-1</a>)，计算表明，这样的假定出现在锚固前瞬间其误差是不大的。锚固时，张拉预应力钢筋将发生一个数值为<math xmlns="http://www.w3.org/1998/Math/MathML" ><mo data-mjx-texclass="OP">∑</mo><mi mathvariant="normal">Δ</mi><mi>l</mi></math>的回缩值。由回缩引起的反向摩擦损失，以张拉端为最大，随离开张拉端的距离而逐渐衰减，到反向摩擦影响长度<math xmlns="http://www.w3.org/1998/Math/MathML"><msub><mi>l</mi><mrow><mrow><mi mathvariant="normal">f</mi></mrow></mrow></msub></math>时为零。超过<math xmlns="http://www.w3.org/1998/Math/MathML"><msub><mi>l</mi><mrow><mrow><mi mathvariant="normal">f</mi></mrow></mrow></msub></math>之后，预应力钢筋仍保持锚固前的应力不变，也即不受回缩的影响。由于假定正向摩擦与反向摩擦的管道摩擦系数是相等的，所以代表锚固前和锚固后瞬间预应力钢筋应力变化的两根直线<math xmlns="http://www.w3.org/1998/Math/MathML" ><mi>c</mi><mi>a</mi></math>和<math xmlns="http://www.w3.org/1998/Math/MathML" ><mi>e</mi><mi>a</mi></math>的斜率也是相同的，但摩擦力方向则相反。这样，锚固后预应力钢筋的应力分布线可用折线<math xmlns="http://www.w3.org/1998/Math/MathML"><mi>e</mi><mi>a</mi><msup><mi>a</mi><mrow><msup><mi></mi><mo>′</mo></msup></mrow></msup></math>来代表(见<a href="#figTG.1">图 G-1</a>)。</span></p>  

 <div align="center"><img id="figTG.1" src="../_static/fig/TG.1.png" alt="Picture" width="250px"></div>
  <p style="color: dimgray;text-align: center;">图 TG.1 锚固前后预应力钢筋应力变化示意图</p>
  <script type="text/javascript">var viewer = new Viewer(document.getElementById('figTG.1'));</script>




 <p style="text-align:justify;text-indent:2em;" > 从<a href="#figTG.1">图 G-1</a>可知，由于<math xmlns="http://www.w3.org/1998/Math/MathML" ><mi>c</mi><mi>a</mi></math>和<math xmlns="http://www.w3.org/1998/Math/MathML" ><mi>e</mi><mi>a</mi></math>两条直线是对称的，张拉端的预应力损失可用下式求得：</p> 

$$ \\Delta \\sigma =2 \\Delta \\sigma _{\\mathrm{d}}l_{\\mathrm{f}}\\tag{附 G-1}$$

.. raw:: html

 <table border="0" style="font-family:times new roman" id="gongshi">
 <tr>
 <td width="50px" align='center' id="eqzs">式中:</td>
 <td width="50px" align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><mi mathvariant="normal">Δ</mi><msub><mi>σ</mi><mrow><mrow><mi mathvariant="normal">d</mi></mrow></mrow></msub></math></td>
 <td width="40px" align='left' id="eqzs">——</td>
 <td id="eqzs">单位长度由管道摩擦引起的预应力损失值，其值为<math xmlns="http://www.w3.org/1998/Math/MathML" ><mo stretchy="false">(</mo><msub><mi>σ</mi><mrow><mn>0</mn></mrow></msub><mo>−</mo><msub><mi>σ</mi><mrow><mrow><mi mathvariant="normal">t</mi></mrow></mrow></msub><mo stretchy="false">)</mo><mrow><mo>/</mo></mrow><mi>l</mi></math>;</td>
 </tr>
 <tr>
 <td id="eqzs"> </td>
 <td id="eqzs" align='right'><math xmlns="http://www.w3.org/1998/Math/MathML"><msub><mi>l</mi><mrow><mrow><mi mathvariant="normal">f</mi></mrow></mrow></msub></math></td>
 <td id="eqzs">——</td>
 <td id="eqzs">预应力钢筋回缩的影响长度。</td>
 </tr>
 </table>
 <p></p>



 <p style="text-align:justify;text-indent:2em;" > 回缩(反向摩擦)影响长度<math xmlns="http://www.w3.org/1998/Math/MathML"><msub><mi>l</mi><mrow><mrow><mi mathvariant="normal">f</mi></mrow></mrow></msub></math>,可根据回缩值<math xmlns="http://www.w3.org/1998/Math/MathML" ><mo data-mjx-texclass="OP">∑</mo><mi mathvariant="normal">Δ</mi><mi>l</mi></math>用积分法(也就是计算<math xmlns="http://www.w3.org/1998/Math/MathML" ><mi>c</mi><mi>a</mi><mi>e</mi></math>面积)求得：</p> 

$$\\sum \\Delta  l=\\int_{0}\\Delta \\varepsilon dx=\\int^{l_{\\mathrm{f} }}_{0}\\dfrac{\\Delta \\sigma _{x}}{E_{\\mathrm{p}}}dx=\\int^{l_{\\mathrm{f} }}_{0}\\dfrac{2\\Delta \\sigma _{d}x}{E_{\\mathrm{p}}}dx=\\dfrac{\\Delta \\sigma _{d}}{E_{\\mathrm{p}}}l^{2}_{\\mathrm{f} }$$ 
$$\\hspace{-4cm}移项得\\hspace{4cm}l_{\\mathrm{f} }=\\sqrt{\\dfrac{\\sum \\Delta  l\\cdot E_{\\mathrm{p} }}{\\Delta \\sigma _{\\mathrm{d} }}}\\tag{附 G-2}$$ 

.. raw:: html

 <p style="text-align:justify;text-indent:2em;" > 公式(附G-2)只适用于一端张拉时<math xmlns="http://www.w3.org/1998/Math/MathML"><msub><mi>l</mi><mrow><mrow><mi mathvariant="normal">f</mi></mrow></mrow></msub></math>不超过构件全长，如正摩擦损失较小，应力降低 曲线比较平坦，或者回缩值较大，则<math xmlns="http://www.w3.org/1998/Math/MathML"><msub><mi>l</mi><mrow><mrow><mi mathvariant="normal">f</mi></mrow></mrow></msub></math>有可能超过构件全长，此时，只能用在<math xmlns="http://www.w3.org/1998/Math/MathML" ><mi>l</mi></math>范围内钢筋变形与锚具回缩变形相协调，并通过试算方法来求预应力损失值。</p>  


:math:`\ ` 