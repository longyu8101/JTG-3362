附录D 温差作用效应计算公式
==============================================================================

.. raw:: html

  <h2 id="test111">附录D 温差作用效应计算公式</h2>


.. raw:: html

 <p style="text-align:justify;text-indent:2em;" > 温差作用的温度梯度呈非线性变化，但梁截面变形服从平面假定，致使梁截面的温差变形在纵向纤维之间受到约束，在截面上产生自平衡的纵向约束应力，称为自应力。如<a href="#figTD.1">图D-1</a>所示：b)为温度梯度(无约束的自由应变图形与温度梯度同); c)为平面变形，为最终应变；d)内阴影部分为自由应变与最终应变之差，即由纤维之间的约束产生的自应力应变。</p>



 <div align="center"><img id="figTD.1" src="../_static/fig/TD.1.png" alt="Picture" width="400px"></div>
  <p style="color: dimgray;text-align: center;">图 D-1 温度梯度计算模式<br/>1-基轴；2-重心轴</p>
  <script type="text/javascript">var viewer = new Viewer(document.getElementById('figTD.1'));</script>    

 <p style="text-align:justify;text-indent:2em;" > 沿梁高的自由应变(纵向纤维之间不受约束时)<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>ε</mi><mrow><mrow><mi mathvariant="normal">t</mi><mo stretchy="false">(</mo><mi mathvariant="normal">y</mi><mo stretchy="false">)</mo></mrow></mrow></msub></math>与温度梯度一致，即：</p>


$$\\varepsilon _{\\mathrm{t(y)} }=\\alpha _{c}t_{(\\mathrm{y} )}\\tag{附 D-1}$$ 


.. raw:: html  

 <p style="text-align:justify;text-indent:2em;" > 由于纵向纤维之间相互约束，梁截面应变应符合平面假定，梁截面上的最终应变<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>ε</mi><mrow><mrow><mi mathvariant="normal">f</mi><mo stretchy="false">(</mo><mi mathvariant="normal">y</mi><mo stretchy="false">)</mo></mrow></mrow></msub></math>应为直线分布，即：</p>


$$\\varepsilon _{\\mathrm{f(y)} }=\\varepsilon _{0}+\\phi\\mathrm{y} \\tag{附 D-2}$$ 


.. raw:: html  

 <table border="0" style="font-family:times new roman" id="gongshi">
 <tr>
 <td width="50px" align='center' id="eqzs">式中:</td>
 <td width="30px" align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>ε</mi><mrow><mn>0</mn></mrow></msub></math></td>
 <td width="40px" align='left' id="eqzs">——</td>
 <td id="eqzs"align='left'>轴y=0处应变；</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right'  id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><mi>ϕ</mi></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">截面变形曲率；</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><mrow><mi mathvariant="normal">y</mi></mrow></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">基轴以上任一点求应变的坐标；</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>α</mi><mrow><mrow><mi mathvariant="normal">c</mi></mrow></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">混凝土线膨胀系数。</td>
 </tr> 
 </table>
 <p></p> 


 <p style="text-align:justify;text-indent:2em;" > 自由应变与最终应变之差，即<a href="#figTD.1">图D-1 d</a>)的阴影部分，系纤维之间的约束产生，其值
为：</p>


$$\\varepsilon _{\\mathrm{\\sigma (y)} }=\\varepsilon _{\\mathrm{t(y)} }-\\varepsilon _{\\mathrm{f (y)} }=\\alpha _{\\mathrm{c} }t_{(\\mathrm{y} )}-(\\varepsilon _{0}+\\phi\\mathrm{y} )\\tag{附 D-3}$$ 


.. raw:: html  


 <p style="text-align:justify;text-indent:2em;" > 阴影部分的应力(自应力)为：</p>


$$\\varepsilon _{\\mathrm{s (y)} }=E_{\\mathrm{c} }\\varepsilon _{\\sigma \\mathrm{(y)} }=E_{\\mathrm{c} }[\\alpha _{\\mathrm{c} }t_{(\\mathrm{y} )}-(\\varepsilon _{0}+\\phi\\mathrm{y} )]\\tag{附 D-4}$$ 


.. raw:: html  


 <p style="text-align:justify;text-indent:2em;" > 全截面上轴向力N和弯矩M</p>


$$\\begin{array}{l}N& =E_{c}\\int_{\\mathrm{h}}\\varepsilon _{\\sigma (\\mathrm{y})}b_{\\mathrm{(y)}}d\\mathrm{y}=E_{c}\\int_{\\mathrm{h}}(\\alpha _{\\mathrm{c} }t_{(\\mathrm{y})}-\\varepsilon _{0}-\\phi _{\\mathrm{y} })b_{\\mathrm{(y)}}d\\mathrm{y}\\\\  &=E_{c}[\\alpha _{\\mathrm{c}}\\int_{\\mathrm{h}}t_{(\\mathrm{y})}b_{\\mathrm{(y)}}d\\mathrm{y}-\\varepsilon _{0}\\int_{\\mathrm{h}}b_{\\mathrm{(y)}}d\\mathrm{y}-\\phi\\int_{\\mathrm{h}}\\mathrm{y} b_{\\mathrm{(y)}}d\\mathrm{y}]\\end{array}\\tag{附 D-5}$$ 
$$\\small{\\begin{array}{l}M& =E_{c}\\int_{\\mathrm{h}}\\varepsilon _{\\sigma (\\mathrm{y})}b_{\\mathrm{(y)}}(\\mathrm{y-y_{c}} )d\\mathrm{y}=E_{c}\\int_{\\mathrm{h}}(\\alpha _{\\mathrm{c} }t_{(\\mathrm{y})}-\\varepsilon _{0}-\\phi _{\\mathrm{y} })b_{\\mathrm{(y)}}(\\mathrm{y-y_{c}} )d\\mathrm{y}\\\\  &=E_{c}[\\alpha _{\\mathrm{c}}\\int_{\\mathrm{h}}t_{(\\mathrm{y})}b_{\\mathrm{(y)}}(\\mathrm{y-y_{c}} )d\\mathrm{y}-\\varepsilon _{0}\\int_{\\mathrm{h}}b_{\\mathrm{(y)}}(\\mathrm{y-y_{c}} )d\\mathrm{y}-\\phi\\mathrm{y} d\\mathrm{y}]\\end{array}}\\tag{附 D-6}$$ 

.. raw:: html  


 <table border="0" style="font-family:times new roman" id="gongshi">
 <tr>
 <td width="50px" align='center' id="eqzs">式中:</td>
 <td width="30px" align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>E</mi><mrow><mrow><mi mathvariant="normal">c</mi></mrow></mrow></msub></math></td>
 <td width="40px" align='left' id="eqzs">——</td>
 <td id="eqzs"align='left'>混凝土材料弹性模量；</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right'  id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><msub><mi>b</mi><mrow><mrow><mo stretchy="false">(</mo><mi mathvariant="normal">y</mi><mo stretchy="false">)</mo></mrow></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">y处的梁宽。</td>
 </tr>
 </table>
 <p></p> 


 <p style="text-align:justify;text-indent:2em;" > 对于任何截面，N=0,M=0,即内力总和为零。</p>
 <p style="text-align:justify;text-indent:2em;" > 公式(附D-5)、(附D-6)可分别改写为：</p>

$$\\varepsilon _{0}\\int_{\\mathrm{h}}b_{\\mathrm{(y)}}d{\\mathrm{y}}+\\phi \\int_{\\mathrm{h}}\\mathrm{y} b_{\\mathrm{(y)}}d{\\mathrm{y}}=\\alpha _{c}\\int_{\\mathrm{h}}t_{(\\mathrm{y} )}b_{(\\mathrm{y} )}d\\mathrm{y} \\tag{附 D-7}$$ 
$$\\varepsilon _{0}\\int_{\\mathrm{h}}b_{\\mathrm{(y)}}(\\mathrm{y-y_{c}} )d{\\mathrm{y}}+\\phi \\int_{\\mathrm{h}} b_{\\mathrm{(y)}}(\\mathrm{y-y_{c}} )\\mathrm{y}d{\\mathrm{y}}=\\alpha _{c}\\int_{\\mathrm{h}}t_{(\\mathrm{y} )}b_{(\\mathrm{y} )}(\\mathrm{y-y_{c}} )d\\mathrm{y} \\tag{附 D-8}$$ 

.. raw:: html  


 <p style="text-align:justify;text-indent:2em;" > 在公式(附D-7)、(附D-8)内</p>


$$\\int_{\\mathrm{h}}b_{\\mathrm{(y)}}d{\\mathrm{y}} =A\\tag{附 D-9}$$ 
$$\\int_{\\mathrm{h}}\\mathrm{y}b_{\\mathrm{(y)}}d{\\mathrm{y}} =A\\mathrm{y_{c}} \\tag{附 D-10}$$ 
$$\\small{\\int_{\\mathrm{h}}b_{\\mathrm{(y)}}(\\mathrm{y-y_{c}} )\\mathrm{y} d_{\\mathrm{y}} =\\int_{\\mathrm{h}}b_{\\mathrm{(y)}}\\mathrm{y}^{2} d_{\\mathrm{y}}-\\int_{\\mathrm{h}}b_{\\mathrm{(y)}}\\mathrm{y}\\mathrm{y}_{\\mathrm{c}}d_{\\mathrm{y}}=I_{\\mathrm{b}}-\\int_{\\mathrm{h}}b_{\\mathrm{(y)}}\\mathrm{y}\\mathrm{y}_{\\mathrm{c}}d_{\\mathrm{y}}=I_{\\mathrm{g}}}\\tag{附 D-11}$$ 
$$\\int_{\\mathrm{h}}b_{\\mathrm{(y)}}(\\mathrm{y-y_{c}} )d_{\\mathrm{y}} =0(重心轴的静面积矩为零)$$ 

.. raw:: html  


 <table border="0" style="font-family:times new roman" id="gongshi">
 <tr>
 <td width="50px" align='center' id="eqzs">式中:</td>
 <td width="30px" align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><mi>A</mi></math></td>
 <td width="40px" align='left' id="eqzs">——</td>
 <td id="eqzs"align='left'>截面面积；</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right'  id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>I</mi><mrow><mi mathvariant="normal">b</mi></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">截面面积对基轴(<a href="#figTD.1">图D-1</a>)惯性矩；</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML"><msub><mi>I</mi><mrow><mi mathvariant="normal">g</mi></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">—截面面积对重心轴(<a href="#figTD.1">图D-1</a>)惯性矩。</td>
 </tr>
 
 </table>
 <p></p> 


 <p style="text-align:justify;text-indent:2em;" > 将公式(附D-9)～(附D-11)代入公式(附D-7)、(附D-8)内。</p>

$$\\varepsilon _{0}A+\\phi A\\mathrm{y_{c}} =\\int_{\\mathrm{h}}t_{\\mathrm{(y)}}b_{\\mathrm{(y)}}d_{\\mathrm{y}} \\tag{附 D-12}$$ 

$$\\phi I_{\\mathrm{g} }=\\alpha _{c}\\int_{\\mathrm{h} }t_{(\\mathrm{y})}b_{(\\mathrm{y})}(\\mathrm{y-y_{c}})d\\mathrm{y} \\tag{附 D-13}$$ 

.. raw:: html  


 <p style="text-align:justify;text-indent:2em;" > 由公式(附D-12)、(附D-13)可得：</p>

$$\\varepsilon _{0}=\\dfrac{\\alpha _{\\mathrm{c}}}{A}\\int_{\\mathrm{h}}t_{\\mathrm{(y)}}b_{\\mathrm{(y)}}d\\mathrm{y}-\\phi \\mathrm{y} _{\\mathrm{c} } \\tag{附 D-14}$$ 
$$\\phi =\\dfrac{\\alpha _{\\mathrm{c}}}{I_{\\mathrm{g} }}\\int_{\\mathrm{h}}t_{\\mathrm{(y)}}b_{\\mathrm{(y)}}(\\mathrm{y-y_{c}} )d_{\\mathrm{y}} \\tag{附 D-15}$$ 

.. raw:: html  


 <p style="text-align:justify;text-indent:2em;" > 设在坐标<math xmlns="http://www.w3.org/1998/Math/MathML"><mi mathvariant="normal">y</mi></math>处，截面内一厚度为<math xmlns="http://www.w3.org/1998/Math/MathML" ><mi>i</mi></math>的微小单元面积<math xmlns="http://www.w3.org/1998/Math/MathML"><msub><mi>A</mi><mrow><mrow><mi mathvariant="normal">y</mi></mrow></mrow></msub></math>，处温度梯度值为<math xmlns="http://www.w3.org/1998/Math/MathML"><msub><mi>t</mi><mrow><mrow><mi mathvariant="normal">y</mi></mrow></mrow></msub></math>，以<math xmlns="http://www.w3.org/1998/Math/MathML"><msub><mi>t</mi><mrow><mrow><mi mathvariant="normal">y</mi></mrow></mrow></msub></math>为常值代入公式(附 D-14)、(附 D-15),并注意积分区段仅在<math xmlns="http://www.w3.org/1998/Math/MathML"><mi>i</mi></math>厚度范围内有值。因此：<math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><msub><mo data-mjx-texclass="OP">∫</mo><mrow><mrow><mi mathvariant="normal">h</mi></mrow></mrow></msub><msub><mi>b</mi><mrow><mrow><mo stretchy="false">(</mo><mi mathvariant="normal">y</mi><mo stretchy="false">)</mo></mrow></mrow></msub><msub><mi>d</mi><mrow><mrow><mi mathvariant="normal">y</mi></mrow></mrow></msub><mo>=</mo><mi>ϕ</mi><msub><mo data-mjx-texclass="OP">∫</mo><mrow><mrow><mi mathvariant="normal">h</mi></mrow></mrow></msub><msub><mi>b</mi><mrow><mrow><mo stretchy="false">(</mo><mi mathvariant="normal">y</mi><mo stretchy="false">)</mo></mrow></mrow></msub><msub><mi>d</mi><mrow><mrow><mi mathvariant="normal">y</mi></mrow></mrow></msub><mo>=</mo><msub><mi>A</mi><mrow><mrow><mi mathvariant="normal">y</mi></mrow></mrow></msub><mo>,</mo><msub><mi>t</mi><mrow><mo stretchy="false">(</mo><mrow><mi mathvariant="normal">y</mi></mrow></mrow></msub><mo stretchy="false">)</mo><mo>=</mo><msub><mi>t</mi><mrow><mrow><mi mathvariant="normal">y</mi></mrow></mrow></msub><mo>,</mo><mo stretchy="false">(</mo><mrow><mi mathvariant="normal">y</mi><mo>−</mo><msub><mi mathvariant="normal">y</mi><mrow><mi mathvariant="normal">c</mi></mrow></msub></mrow><mo stretchy="false">)</mo><mo>=</mo><msub><mi>e</mi><mrow><mrow><mi mathvariant="normal">y</mi></mrow></mrow></msub></math>，(单元面积<math xmlns="http://www.w3.org/1998/Math/MathML"><msub><mi>A</mi><mrow><mrow><mi mathvariant="normal">y</mi></mrow></mrow></msub></math>对全面积重心的偏心距)。</p>


$$\\small{\\phi =\\dfrac{\\alpha _{\\mathrm{c}}}{I_{\\mathrm{g} }}\\int_{\\mathrm{h}}t_{\\mathrm{(y)}}b_{\\mathrm{(y)}}(\\mathrm{y-y_{c}} )d\\mathrm{y} =\\dfrac{\\alpha _{\\mathrm{c}}}{I_{\\mathrm{g} }}\\int_{\\mathrm{i}}t_{\\mathrm{(y)}}b_{\\mathrm{(y)}}(\\mathrm{y-y_{c}} )d\\mathrm{y} =\\dfrac{\\alpha _{\\mathrm{c}}t_{\\mathrm{y}}A_{\\mathrm{y}}e_{\\mathrm{y}}}{I_{\\mathrm{g} }}}\\tag{附 D-16}$$ 
$$\\scriptsize {\\varepsilon _{0}=\\dfrac{\\alpha _{\\mathrm{c}}}{A}\\int_{\\mathrm{h}}t_{\\mathrm{(y)}}b_{\\mathrm{(y)}}d\\mathrm{y}-\\phi \\mathrm{y} _{\\mathrm{c} } =\\dfrac{\\alpha _{\\mathrm{c}}}{A}\\int_{\\mathrm{i}}t_{\\mathrm{(y)}}b_{\\mathrm{(y)}}d\\mathrm{y}-\\phi \\mathrm{y} _{\\mathrm{c} } =\\dfrac{\\alpha _{\\mathrm{c}}t_{\\mathrm{y}}A_{\\mathrm{y}}}{A}-\\dfrac{\\alpha _{\\mathrm{c}}t_{\\mathrm{y}}A_{\\mathrm{y}}e_{\\mathrm{y}}\\mathrm{y}_{\\mathrm{c} }}{I_{\\mathrm{g} }}}\\tag{附 D-17}$$ 

.. raw:: html  


 <p style="text-align:justify;text-indent:2em;" >自公式(附D-4)可求得任意点应力<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>σ</mi><mrow><mrow><mi mathvariant="normal">s</mi><mo stretchy="false">(</mo><mi mathvariant="normal">y</mi><mo stretchy="false">)</mo></mrow></mrow></msub></math>:</p>


$$\\begin{align*} \\sigma _{\\mathrm{s(y)}} &=E_{\\mathrm{c}} [\\alpha _{\\mathrm{c}}t_{(\\mathrm{y})}-(\\varepsilon _{0}+\\phi _{\\mathrm{y} })]\\\\  &=E_{\\mathrm{c}}\\alpha _{\\mathrm{c}}t_{\\mathrm{y}}-\\dfrac{E_{\\mathrm{c}}\\alpha _{\\mathrm{c}}t_{\\mathrm{y}}A_{\\mathrm{y}}}{A}+\\dfrac{E_{\\mathrm{c}}\\alpha _{\\mathrm{c}}t_{\\mathrm{y}}A_{\\mathrm{y}}e_{\\mathrm{y}}\\mathrm{y} _{\\mathrm{c}}}{I_{\\mathrm{g} }}-\\dfrac{E_{\\mathrm{c}}\\alpha _{\\mathrm{c}}t_{\\mathrm{y}}A_{\\mathrm{y}}e_{\\mathrm{y}}\\mathrm{y}}{I_{\\mathrm{g} }}\\end{align*}\\tag{附 D-18}$$ 

.. raw:: html  


 <p style="text-align:justify;text-indent:2em;" > 如令:<math xmlns="http://www.w3.org/1998/Math/MathML"><msub><mi>N</mi><mrow><mrow><mi mathvariant="normal">t</mi><mi mathvariant="normal">i</mi></mrow></mrow></msub><mo>=</mo><msub><mi>A</mi><mrow><mrow><mi mathvariant="normal">y</mi></mrow></mrow></msub><msub><mi>t</mi><mrow><mrow><mi mathvariant="normal">y</mi></mrow></mrow></msub><msub><mi>α</mi><mrow><mrow><mi mathvariant="normal">c</mi></mrow></mrow></msub><msub><mi>E</mi><mrow><mrow><mi mathvariant="normal">c</mi></mrow></mrow></msub><mo>,</mo><msub><mi>M</mi><mrow><mrow><mi mathvariant="normal">t</mi><mi mathvariant="normal">i</mi></mrow></mrow></msub><mo>=</mo><mo>−</mo><msub><mi>N</mi><mrow><mrow><mi mathvariant="normal">t</mi><mi mathvariant="normal">i</mi></mrow></mrow></msub><msub><mi>e</mi><mrow><mrow><mi mathvariant="normal">y</mi></mrow></mrow></msub><mo>=</mo><mo>−</mo><msub><mi>A</mi><mrow><mrow><mi mathvariant="normal">y</mi></mrow></mrow></msub><msub><mi>t</mi><mrow><mrow><mi mathvariant="normal">y</mi></mrow></mrow></msub><msub><mi>α</mi><mrow><mrow><mi mathvariant="normal">c</mi></mrow></mrow></msub><msub><mi>E</mi><mrow><mrow><mi mathvariant="normal">c</mi></mrow></mrow></msub><msub><mi>e</mi><mrow><mrow><mi mathvariant="normal">y</mi></mrow></mrow></msub></math></p>

$$\\sigma_{ \\mathrm{s(y)} }=-\\dfrac{N_{\\mathrm{ti} }}{A}+\\dfrac{M_{\\mathrm{ti} }}{I_{\\mathrm{g}}}(\\mathrm{y-y_{c}})+t_{\\mathrm{y} }\\alpha_{\\mathrm{c} }E_{\\mathrm{c} }\\tag{附 D-19}$$ 

.. raw:: html  


 <p style="text-align:justify;text-indent:2em;" > 这个公式是由于一个单元面积<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>A</mi><mrow><mrow><mi mathvariant="normal">y</mi></mrow></mrow></msub></math>，内的温度作用，在截面任一点产生的应力；对于分为很多块单元面积上不同<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>t</mi><mrow><mrow><mi mathvariant="normal">y</mi></mrow></mrow></msub></math>，的作用，应用分段总和法，也就是本规范<a href="https://jtg-3362.readthedocs.io/zh/latest/FLD.html">附录D</a>内的公式。在本规范<a href="https://jtg-3362.readthedocs.io/zh/latest/FLD.html">附录D</a>内，<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>N</mi><mrow><mrow><mi mathvariant="normal">t</mi></mrow></mrow></msub></math>相当于本说明<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>N</mi><mrow><mrow><mi mathvariant="normal">ti</mi></mrow></mrow></msub></math>的总和；<math xmlns="http://www.w3.org/1998/Math/MathML" ><msubsup><mi>M</mi><mrow><mrow><mi mathvariant="normal">t</mi></mrow></mrow><mrow><mn>0</mn></mrow></msubsup></math>相当于<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>M</mi><mrow><mrow><mi mathvariant="normal">ti</mi></mrow></mrow></msub></math>的总和；<math xmlns="http://www.w3.org/1998/Math/MathML"><mrow><mi mathvariant="normal">y</mi></mrow></math>相当于(<math xmlns="http://www.w3.org/1998/Math/MathML" ><mrow><mi mathvariant="normal">y</mi><mo>−</mo><msub><mi mathvariant="normal">y</mi><mrow><mi mathvariant="normal">c</mi></mrow></msub></mrow></math>)，即<a href="https://jtg-3362.readthedocs.io/zh/latest/FLD.html">附录D</a>内的坐标以截面重心轴为准。</p>
 <p style="text-align:justify;text-indent:2em;" > 公式(附D-19)适用于正温差；如为反温差则整个公式前冠以负号。</p>
 <p style="text-align:justify;text-indent:2em;" > 本附录公式对于开裂截面，如钢筋混凝土构件或允许开裂的预应力混凝土B类构件，在计算温差作用效应时，可不考虑中性轴以下开裂截面的温度梯度。计算温差应力时采用开裂截面的重心轴、换算截面面积和惯性矩。</p>
:math:`\ `	