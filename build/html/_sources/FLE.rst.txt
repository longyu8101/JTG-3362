附录E 受压构件计算长度的简化计算公式 (新增)
==============================================================================

.. raw:: html

  <h2 id="test111">附录E 受压构件计算长度的简化计算公式 (新增)</h2>


.. raw:: html

 <p style="text-align:justify"><a href="#idE.0.1"> E.0.1</a> <span id="idE.0.1"> 受压构件的计算长度<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>l</mi><mrow><mn>0</mn></mrow></msub></math>宜按公式(E.0.1)计算：</span></p>  

$$l_{0}=kl\\tag{E.0.1}$$ 


.. raw:: html

 <table border="0" style="font-family:times new roman" id="gongshi">
 <tr>
 <td width="40px" align='center' id="eqzs">式中:</td>
 <td width="40px" align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML"><mi>k</mi></math></td>
 <td width="40px" align='left' id="eqzs">——</td>
 <td id="eqzs">计算长度换算系数，可按经验或<a href="#idE.0.2">第E.0.2条</a>或<a href="#idE.0.3">第E.0.3条</a>中公式计算；当构件两端固定时，<math xmlns="http://www.w3.org/1998/Math/MathML"><mi>k</mi></math>可取0.5；当一端固定一端为不移动的铰时，<math xmlns="http://www.w3.org/1998/Math/MathML"><mi>k</mi></math>可取 0.7；当两端均为不移动的铰时，<math xmlns="http://www.w3.org/1998/Math/MathML"><mi>k</mi></math>可取1.0；当一端固定一端自由时，<math xmlns="http://www.w3.org/1998/Math/MathML"><mi>k</mi></math>可取2.0;</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML"><mi>l</mi></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">构件支点间长度。</td>
 </tr> 
 </table>
 <p></p>

 <p style="text-align:justify"><a href="#idE.0.2"> E.0.2</a> <span id="idE.0.2"> 对于一端固定、一端有转动和水平弹性约束的构件，计算长度换算系数<math xmlns="http://www.w3.org/1998/Math/MathML"><mi>k</mi></math>可按下列公式确定：</span></p>  

 <div align="center"><img id="figE.0.2" src="./_static/fig/E.0.2.png" alt="Picture" width="150px"></div>
  <p style="color: dimgray;text-align: center;">图 E.0.2 一端固定、一端有转动和水平弹性约束的构件</p>
  <script type="text/javascript">var viewer = new Viewer(document.getElementById('figE.0.2'));</script>

$$\\small{k=0.5\\mathrm{exp}\\left[\\dfrac{0.35}{1+0.6k_{\\mathrm{\\theta }}}+\\dfrac{0.7}{1+0.01k_{\\mathrm{F} }} +\\dfrac{0.35}{(1+0.75k_{\\mathrm{\\theta }})(1+1.15k_{\\mathrm{F} })} \\right]}\\tag{E.0.2-1}$$ 
$$k_{\\mathrm{\\theta } }=K_{\\mathrm{\\theta } }\\dfrac{l}{EI}\\tag{E.0.2-2}$$ 
$$k_{\\mathrm{F} }=K_{\\mathrm{F} }\\dfrac{l^{3}}{EI}\\tag{E.0.2-3}$$ 

.. raw:: html


 <table border="0" style="font-family:times new roman" id="gongshi">
 <tr>
 <td width="40px" align='center' id="eqzs">式中:</td>
 <td width="40px" align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>k</mi><mrow><mrow><mi mathvariant="normal">0</mi></mrow></mrow></msub></math></td>
 <td width="40px" align='left' id="eqzs">——</td>
 <td id="eqzs">构件转动和水平弹性约束端的相对转动约束刚度系数；</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>K</mi><mrow><mrow><mi mathvariant="normal">0</mi></mrow></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">构件转动和水平弹性约束端的转动约束刚度；</td>
 </tr> 
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>k</mi><mrow><mrow><mi mathvariant="normal">F</mi></mrow></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">构件转动和水平弹性约束端的相对水平约束刚度系数；</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>K</mi><mrow><mn>F</mn></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">构件转动和水平弹性约束端的水平约束刚度；</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML"><mi>l</mi></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">构件支点间长度；</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML"><mi>EI</mi></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">构件截面抗弯刚度。</td>
 </tr> 
 </table>
 <p></p>

 <p style="text-align:justify"><a href="#idE.0.3"> E.0.3</a> <span id="idE.0.3"> 对于一端固定、一端仅有水平弹性约束的构件，计算长度换算系数<math xmlns="http://www.w3.org/1998/Math/MathML"><mi>k</mi></math>可按公式(E.0.3)确定：</span></p>  

$$k=2-\\dfrac{1.3k_{F}^{1.5}}{9.5+k_{F}^{1.5}}\\tag{E.0.3}$$ 

.. raw:: html

 <div align="center"><img id="figE.0.3" src="./_static/fig/E.0.3.png" alt="Picture" width="200px"></div>
  <p style="color: dimgray;text-align: center;">图 E.0.3 一端固定、一端仅有水平弹性约束的构件</p>
  <script type="text/javascript">var viewer = new Viewer(document.getElementById('figE.0.3'));</script>

:math:`\ `	