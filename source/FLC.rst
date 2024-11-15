附录C 混凝土收缩应变和徐变系数计算及钢筋松弛损失中间值与终极值的比值
==============================================================================

.. raw:: html

  <h2 id="test111">附录C 混凝土收缩应变和徐变系数计算及钢筋松弛损失中间值与终极值的比值</h2>

C.1  收缩应变
----------------------

.. raw:: html

 <p style="text-align:justify"><a href="#idC.1.1"> C.1.1</a> <span id="idC.1.1"> 混凝土的收缩应变可按下列公式计算：</span></p>  

$$\\varepsilon _{\\mathrm{cs}}(t,t_{\\mathrm{s}})=\\varepsilon _{\\mathrm{cso}\\cdot\\beta_{\\mathrm{s}}}(t-t_{\\mathrm{s} })\\tag{C.1.1-1}$$ 

$$\\varepsilon _{\\mathrm{cso}}=\\varepsilon _{\\mathrm{s}}(f_{\\mathrm{cm}})\\cdot\\beta_{\\mathrm{RH}}\\tag{C.1.1-2}$$ 

$$\\varepsilon _{\\mathrm{s}}(f_{\\mathrm{cm}})=[160+10\\beta_{\\mathrm{sc}}(9-f_{\\mathrm{cm}}/f_{\\mathrm{cmo}})]\\cdot10^{-6}\\tag{C.1.1-3}$$ 

$$\\beta_{\\mathrm{RH}}=1.55[1-(RH/RH_{0})^{3}]\\tag{C.1.1-4}$$ 

$$\\beta_{\\mathrm{s}}(t-t_{\\mathrm{s} })=\\left[ \\dfrac{(t-t_{\\mathrm{s} })/t_{1}}{350(h/h_{0})^{2}+(t-t_{\\mathrm{s} })/t_{1}}\\right ]^{0.5} \\tag{C.1.1-5}$$ 

.. raw:: html 

 <table border="0" style="font-family:times new roman" id="gongshi">
 <tr>
 <td width="50px" align='center' id="eqzs">式中:</td>
 <td width="60px" align='right' id="eqzs"><i>t</i></td>
 <td width="40px" align='left' id="eqzs">——</td>
 <td id="eqzs">计算考虑时刻的混凝土龄期(d);</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>t</mi><mrow><mrow><mi mathvariant="normal">s</mi></mrow></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">收缩开始时的混凝土龄期(d)，可假定为3~7d;</td>
 </tr> 
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML"><msub><mi>ε</mi><mrow><mrow><mi mathvariant="normal">c</mi><mi mathvariant="normal">s</mi></mrow></mrow></msub><mo stretchy="false">(</mo><mi>t</mi><mo>,</mo><msub><mi>t</mi><mrow><mrow><mi mathvariant="normal">s</mi></mrow></mrow></msub><mo stretchy="false">)</mo></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">收缩开始时的龄期为<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>t</mi><mrow><mrow><mi mathvariant="normal">s</mi></mrow></mrow></msub></math>，计算考虑的龄期为<i>t</i>时的收缩应变；</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>ε</mi><mrow><mrow><mi mathvariant="normal">cso</mi></mrow></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">名义收缩系数；</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>β</mi><mrow><mrow><mi mathvariant="normal">s</mi></mrow></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">收缩随时间发展的系数；</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>f</mi><mrow><mrow><mi mathvariant="normal">cm</mi></mrow></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">强度等级 C25~C50 混凝土在28d 龄期时的平均圆柱体抗压强度(MPa)，<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>f</mi><mrow><mrow><mi mathvariant="normal">c</mi><mi mathvariant="normal">m</mi></mrow></mrow></msub><mo>=</mo><mn>0.8</mn><msub><mi>f</mi><mrow><mrow><mi mathvariant="normal">c</mi><mi mathvariant="normal">u</mi><mo>,</mo><mi mathvariant="normal">k</mi></mrow></mrow></msub><mo>+</mo><mn>8</mn></math> MPa;</td>
 </tr>
  <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>f</mi><mrow><mrow><mi mathvariant="normal">cu,k</mi></mrow></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">拉龄期为28d，具有95%证率的混凝土立方体抗压强度标准值(MPa);</td>
 </tr>
  <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>β</mi><mrow><mrow><mi mathvariant="normal">RH</mi></mrow></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">与年平均相对湿度相关的系数，公式(C.1.1-4)适用于40%<i>RH</i>≤99%；</td>
 </tr>
  <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><i>RH</i></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">环境年平均相对湿度（%）；</td>
 </tr>
  <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>β</mi><mrow><mrow><mi mathvariant="normal">sc</mi></mrow></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">依水泥种类而定的系数，对一般的硅酸盐类水泥或快硬水泥，<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>β</mi><mrow><mrow><mi mathvariant="normal">sc</mi></mrow></mrow></msub></math>=5.0;</td>
 </tr> 
  <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><i>h</i></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">构件理论厚度(mm)，<i>h</i>=2<i>A</i>/<i>u</i>，<i>A</i>为构件截面面积，<i>u</i>为构件与大气接触的周边长度；</td>
 </tr>
 </table>
 <p></p>  

$$\\hspace{-7cm} \\begin{align*} RH_{0}&=100\\% \\\\ H_{0}&=100\\ \\mathrm{mm} \\\\t_{1}&=1\\mathrm{d} \\\\f_{\\mathrm{cmo} }&=10\\ \\mathrm{MPa} 。\\end{align*}$$

.. raw:: html

 <p style="text-align:justify"><a href="#idC.1.2"> C.1.2</a> <span id="idC.1.2"> 强度等级 C25~C50 混凝土的名义收缩系数<i>ε</i><sub>cs0</sub>,可采用按公式(C.1.1-2)算得的<a href="#BC.1.2">表C.1.2</a>所列数值。</span></p>  
 
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

         <caption style="caption-side:top;text-align: center;color:black" ><b style="text-align:center"> <div id="BC.1.2">表C.1.2 混凝土名义收缩系数<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>ε</mi><mrow><mrow><mi mathvariant="normal">cs0</mi></mrow></mrow></msub></math>(×10³)</b></caption>	
              
		    <tr>
		     <td  align="center" id="dhbg"width="450px">40%≤<i>RH</i>＜70%</td>
		     <td  align="center" id="dhbg"width="450px">70%≤<i>RH</i>＜99%</td>
        </tr>
		    <tr>
		     <td align="center" id="dhbg">0.529</td>
		     <td align="center" id="dhbg">0.310</td>
		    </tr>
		</table>
 <p><font size="2">注：1.本表适用于一般硅酸盐类水泥或快硬水泥配制而成的混凝土。<br/>
   &emsp;&emsp; &emsp;&emsp; &emsp;&nbsp;2.本表适用于季节性变化的平均温度一20~+40℃。<br/>
   &emsp;&emsp; &emsp;&emsp; &emsp;&nbsp;对强度等级为C50及以上混凝土，表列数值应乘以<math xmlns="http://www.w3.org/1998/Math/MathML" ><msqrt><mstyle displaystyle="true" scriptlevel="0"><mfrac><mn>32.4</mn><msub><mi>f</mi><mrow><mrow><mi mathvariant="normal">c</mi><mi mathvariant="normal">k</mi></mrow></mrow></msub></mfrac></mstyle></msqrt></math>，式中<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>f</mi><mrow><mrow><mi mathvariant="normal">ck</mi></mrow></mrow></msub></math>为混凝土轴心抗压强度标准值(MPa)。</font></p>
 
 
 <p style="text-align:justify"><a href="#idC.1.3"> C.1.3</a> <span id="idC.1.3"> 在桥梁设计中当需考虑收缩影响或计算阶段预应力损失时，混凝土收缩应变值可按下列步骤计算：</span></p>  

 <p style="text-align:justify;text-indent:2em;" > 1 按公式(C.1.1-5)计算从<i>t</i><sub>s</sub>到<i>t</i>、<i>t</i><sub>s</sub>到<i>t</i><sub>0</sub>的收缩应变发展系数<math xmlns="http://www.w3.org/1998/Math/MathML"><msub><mi>β</mi><mrow><mrow><mi mathvariant="normal">s</mi></mrow></mrow></msub><mo stretchy="false">(</mo><mi>t</mi><mo>−</mo><msub><mi>t</mi><mrow><mi>s</mi></mrow></msub><mo stretchy="false">)</mo></math>、<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>β</mi><mrow><mrow><mi mathvariant="normal">s</mi></mrow></mrow></msub><mo stretchy="false">(</mo><msub><mi>t</mi><mrow><mn>0</mn></mrow></msub><mo>−</mo><msub><mi>t</mi><mrow><mi>s</mi></mrow></msub><mo stretchy="false">)</mo></math>,当计算<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>β</mi><mrow><mrow><mi mathvariant="normal">s</mi></mrow></mrow></msub><mo stretchy="false">(</mo><msub><mi>t</mi><mrow><mn>0</mn></mrow></msub><mo>−</mo><msub><mi>t</mi><mrow><mi>s</mi></mrow></msub><mo stretchy="false">)</mo></math>时，公式中的<i>t</i>均改用<i>t</i><sub>0</sub>。其中t为计算收缩应变考虑时刻的混凝土龄期(d), <i>t</i><sub>0</sub>为桥梁结构开始受收缩影响时刻或预应力钢筋传力锚固时刻的混凝土龄期(d),<i>t</i><sub>s</sub>为收缩开始时(养护期结束时)的混凝土龄期，设计时可取3~7d,<i>t</i>> <i>t</i><sub>0</sub>≥<i>t</i><sub>s</sub>。</p>

 <p style="text-align:justify;text-indent:2em;" > 2 按下列公式计算自<i>t</i><sub>0</sub>至<i>t</i>时的收缩应变值<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>ε</mi><mrow><mrow><mi mathvariant="normal">c</mi><mi mathvariant="normal">s</mi></mrow></mrow></msub><mo stretchy="false">(</mo><mi>t</mi><mo>,</mo><msub><mi>t</mi><mrow><mn>0</mn></mrow></msub><mo stretchy="false">)</mo></math>：</p>

$$\\\varepsilon _{\\mathrm{cs}}(t,t_{0})=\\varepsilon _{\\mathrm{cs0}}[\\beta_{\\mathrm{s}}(t-t_{\\mathrm{s}})-\\beta_{\\mathrm{s}}(t_{0}-t_{\\mathrm{s}})]\\tag{C.1.3}$$ 

.. raw:: html 

 <p style="text-align:justify;text-indent:2em;" > 式中的名义收缩系数<math xmlns="http://www.w3.org/1998/Math/MathML"><msub><mi>ε</mi><mrow><mrow><mi mathvariant="normal">c</mi><mi mathvariant="normal">s</mi><mn>0</mn></mrow></mrow></msub></math>按<a href="#BC.1.2">表C.1.2</a>采用。</p>


C.2 徐变系数
----------------------

.. raw:: html

 <p style="text-align:justify"><a href="#idC.2.1"> C.2.1</a> <span id="idC.2.1"> 混凝土的徐变系数可按下列公式计算：</span></p>  


$$\\phi (t,t_{0})=\\phi _{0}\\cdot\\beta_{\\mathrm{c} }(t-t_{0})\\tag{C.2.1-1}$$ 

$$\\phi _{0}=\\phi_{\\mathrm{RH}}\\cdot\\beta (f_{\\mathrm{cm})}\\cdot\\beta(t_{0})\\tag{C.2.1-2}$$ 

$$\\phi_{\\mathrm{RH}}=1+\\dfrac{1-RH/RH_{0}}{0.46(h/h_{0})^{\\frac{1}{3}}}\\tag{C.2.1-3}$$ 

$$\\beta(f_{\\mathrm{cm}})=\\dfrac{5.3}{(f_{\\mathrm{cm}}/f_{\\mathrm{cm0}})^{0.5}}\\tag{C.2.1-4}$$ 

$$\\beta(t_{0})=\\dfrac{1}{0.1+({t_{0}/t_{1}})^{0.2}}\\tag{C.2.1-5}$$ 

$$\\beta(t-t_{0})=\\left[\\dfrac{(t-t_{0})/t_{1}}{\\beta_{\\mathrm{H}}+(t-t_{0})/t_{1}}\\right]^{0.3}\\tag{C.2.1-6}$$ 

$$\\beta_{\\mathrm{H}}=150\\left[1+\\left(1.2\\dfrac{RH}{RH_{0}}\\right)^{18}\\right]\\dfrac{h}{h_{0}}+250\\leqslant 1500\\tag{C.2.1-7}$$ 

.. raw:: html 

 <table border="0" style="font-family:times new roman" id="gongshi">
 <tr>
 <td width="50px" align='center' id="eqzs">式中:</td>
 <td width="60px" align='right' id="eqzs"><i>t</i><sub>0</sub></td>
 <td width="40px" align='left' id="eqzs">——</td>
 <td id="eqzs">加载时的混凝土龄期(d);</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><i>t</i></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">计算考虑时刻的混凝土龄期(d);</td>
 </tr> 
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><mi>ϕ</mi><mo stretchy="false">(</mo><mi>t</mi><mo>,</mo><msub><mi>t</mi><mrow><mn>0</mn></mrow></msub><mo stretchy="false">)</mo></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">加载龄期为<i>t</i><sub>0</sub>,计算考虑龄期为<i>t</i>时的混凝土徐变系数；</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>ϕ</mi><mrow><mn>0</mn></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">名义徐变系数；</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>β</mi><mrow><mrow><mi mathvariant="normal">c</mi></mrow></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">加载后徐变随时间发展的系数。</td>
 </tr>
 </table>
 <p>式中<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>f</mi><mrow><mrow><mi mathvariant="normal">c</mi><mi mathvariant="normal">m</mi></mrow></mrow></msub><mo>、</mo><msub><mi>f</mi><mrow><mrow><mi mathvariant="normal">c</mi><mi mathvariant="normal">m</mi><mn>0</mn></mrow></mrow></msub><mo>、</mo><mi>R</mi><mi>H</mi><mo>、</mo><mi>R</mi><msub><mi>H</mi><mrow><mn>0</mn></mrow></msub><mo>、</mo><mi>h</mi><mo>、</mo><msub><mi>h</mi><mrow><mn>0</mn></mrow></msub><mo>、</mo><msub><mi>t</mi><mrow><mn>1</mn></mrow></msub></math>的意义及其采用值与<a href="#idC.1.1">第C.1.1条</a>相同。</p>  
 <p style="text-align:justify"><a href="#idC.2.2"> C.2.2</a> <span id="idC.2.2"> 构强度等级 C25~C50 混凝土的名义徐变系数<math xmlns="http://www.w3.org/1998/Math/MathML"><msub><mi>ϕ</mi><mrow><mn>0</mn></mrow></msub></math>，可采用按公式(C.2.1-2)算得的<a href="#BC.2.2">表C.2.2</a>所列数值。</span></p>  

	<table id="biaoge" style="font-family:times new roman">

         <caption style="caption-side:top;text-align: center;color:black" ><b style="text-align:center"> <div id="BC.2.2">表C.2.2 混凝土名义徐变系数<math xmlns="http://www.w3.org/1998/Math/MathML"><msub><mi>ϕ</mi><mrow><mn>0</mn></mrow></msub></math></b></caption>	
              
		    <tr>
		     <td  align="center" id="dhbg"width="180px"rowspan="3">加载龄期(d)</td>
		     <td  align="center" id="dhbg"colspan="4">40%≤<i>RH</i>＜70%</td>
         <!-- <td></td> -->
         <!-- <td></td> -->
         <!-- <td></td> -->  
		     <td  align="center" id="dhbg"colspan="4">70%≤<i>RH</i>＜99%</td>
         <!-- <td></td> -->
         <!-- <td></td> -->
         <!-- <td></td> -->            
        </tr>
		    <tr>
        <!-- <td></td> --> 
		     <td  align="center" id="dhbg"colspan="4">理论厚度 <i>h</i>(mm)</td>
         <!-- <td></td> -->
         <!-- <td></td> -->
         <!-- <td></td> -->   
		     <td  align="center" id="dhbg"colspan="4">理论厚度  <i>h</i>(mm)</td>
         <!-- <td></td> -->
         <!-- <td></td> -->
         <!-- <td></td> -->                  
        </tr>
		    <tr>
        <!-- <td></td> --> 
		     <td  align="center" id="dhbg" width="90px">100</td>
         <td  align="center" id="dhbg" width="90px">200</td>
         <td  align="center" id="dhbg" width="90px">300</td>
         <td  align="center" id="dhbg" width="90px">≥600</td> 
		     <td  align="center" id="dhbg" width="90px">100</td>
         <td  align="center" id="dhbg" width="90px">200</td>
         <td  align="center" id="dhbg" width="90px">300</td>
         <td  align="center" id="dhbg" width="90px">≥600</td>                
        </tr> 
		    <tr>
         <td  align="center" id="dhbg" >3</td>
		     <td  align="center" id="dhbg" >3.90</td>
         <td  align="center" id="dhbg" >3.50</td>
         <td  align="center" id="dhbg" >3.31</td>
         <td  align="center" id="dhbg" >3.03</td> 
		     <td  align="center" id="dhbg" >2.83</td>
         <td  align="center" id="dhbg" >2.65</td>
         <td  align="center" id="dhbg" >2.56</td>
         <td  align="center" id="dhbg" >2.44</td>                
        </tr> 
		    <tr>
         <td  align="center" id="dhbg" >7</td>
		     <td  align="center" id="dhbg" >3.33</td>
         <td  align="center" id="dhbg" >3.00</td>
         <td  align="center" id="dhbg" >2.82</td>
         <td  align="center" id="dhbg" >2.59</td> 
		     <td  align="center" id="dhbg" >2.41</td>
         <td  align="center" id="dhbg" >2.26</td>
         <td  align="center" id="dhbg" >2.19</td>
         <td  align="center" id="dhbg" >2.08</td>                
        </tr> 
		    <tr>
         <td  align="center" id="dhbg" >14</td>
		     <td  align="center" id="dhbg" >2.92</td>
         <td  align="center" id="dhbg" >2.62</td>
         <td  align="center" id="dhbg" >2.48</td>
         <td  align="center" id="dhbg" >2.59</td> 
		     <td  align="center" id="dhbg" >2.41</td>
         <td  align="center" id="dhbg" >2.26</td>
         <td  align="center" id="dhbg" >2.19</td>
         <td  align="center" id="dhbg" >2.08</td>                
        </tr> 
		    <tr>
         <td  align="center" id="dhbg" >28</td>
		     <td  align="center" id="dhbg" >2.56</td>
         <td  align="center" id="dhbg" >2.30</td>
         <td  align="center" id="dhbg" >2.17</td>
         <td  align="center" id="dhbg" >1.99</td> 
		     <td  align="center" id="dhbg" >1.86</td>
         <td  align="center" id="dhbg" >1.74</td>
         <td  align="center" id="dhbg" >1.69</td>
         <td  align="center" id="dhbg" >1.60</td>                
        </tr> 
		    <tr>
         <td  align="center" id="dhbg" >60</td>
		     <td  align="center" id="dhbg" >2.21</td>
         <td  align="center" id="dhbg" >1.99</td>
         <td  align="center" id="dhbg" >1.88</td>
         <td  align="center" id="dhbg" >1.72</td> 
		     <td  align="center" id="dhbg" >1.61</td>
         <td  align="center" id="dhbg" >1.51</td>
         <td  align="center" id="dhbg" >1.46</td>
         <td  align="center" id="dhbg" >1.39</td>                
        </tr> 
		    <tr>
         <td  align="center" id="dhbg" >90</td>
		     <td  align="center" id="dhbg" >2.05</td>
         <td  align="center" id="dhbg" >1.84</td>
         <td  align="center" id="dhbg" >1.74</td>
         <td  align="center" id="dhbg" >1.59</td> 
		     <td  align="center" id="dhbg" >1.49</td>
         <td  align="center" id="dhbg" >1.39</td>
         <td  align="center" id="dhbg" >1.35</td>
         <td  align="center" id="dhbg" >1.28</td>                
        </tr> 
		   	</table>
 <p><font size="2">注：1.本表适用于一般硅酸盐类水泥或快硬水泥配制而成的混凝土。<br/>
   &emsp;&emsp; &emsp;&emsp; &emsp;&nbsp;2.本表适用于季节性变化的平均温度一20~+40℃。<br/>
   &emsp;&emsp; &emsp;&emsp; &emsp;&nbsp;3.对强度等级为C50及以上混凝土，表列数值应乘以<math xmlns="http://www.w3.org/1998/Math/MathML" ><msqrt><mstyle displaystyle="true" scriptlevel="0"><mfrac><mn>32.4</mn><msub><mi>f</mi><mrow><mrow><mi mathvariant="normal">c</mi><mi mathvariant="normal">k</mi></mrow></mrow></msub></mfrac></mstyle></msqrt></math>，式中<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>f</mi><mrow><mrow><mi mathvariant="normal">ck</mi></mrow></mrow></msub></math>为混凝土轴心抗压强度标准值(MPa)。<br/>
   &emsp;&emsp; &emsp;&emsp; &emsp;&nbsp;4.构件的实际理论厚度和加载龄期为表列中间值时，混凝土名义徐变系数按直线内插法求得。</font></p>
  
 <p style="text-align:justify"><a href="#idC.2.3"> C.2.3</a> <span id="idC.2.3"> 在桥梁设计中需考虑徐变影响或计算阶段预应力损失时，混凝土的徐变系数值可按下列步骤计算：</span></p>   

 <p style="text-align:justify;text-indent:2em;" > 1 按公式(C.2.1-7)计算<i>β</i><sub>H</sub>，计算时公式中的年平均相对湿度<i>RH</i>,当在40%≤<i>RH</i>＜70%时，取 <i>RH</i>=55%；当在70%≤<i>RH</i>＜99%，取 RH=80%。</p>
 <p style="text-align:justify;text-indent:2em;" > 2 根据计算徐变所考虑的龄期<i>t</i>、加载龄期<i>t</i><sub>0</sub>，及已算得的<i>β</i><sub>H</sub>，按公式(C.2.1-6)计算徐变发展系数<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>β</mi><mrow><mrow><mi mathvariant="normal">c</mi></mrow></mrow></msub><mo stretchy="false">(</mo><mi>t</mi><mo>−</mo><msub><mi>t</mi><mrow><mn>0</mn></mrow></msub><mo stretchy="false">)</mo></math>。</p>
 <p style="text-align:justify;text-indent:2em;" > 3 根据<i>β</i><sub>c</sub>(<i>t</i>-<i>t</i><sub>0</sub>)和<a href="#BC.2.2">表C.2.2</a>所列名义徐变系数(必要时用内插求得),按公式(C.2.1-1)计算徐变系数<math xmlns="http://www.w3.org/1998/Math/MathML" ><mi>ϕ</mi><mo stretchy="false">(</mo><mi>t</mi><mo>,</mo><msub><mi>t</mi><mrow><mn>0</mn></mrow></msub><mo stretchy="false">)</mo></math>。</p>
 <p style="text-align:justify;text-indent:2em;" > 注：当实际的加载龄期超过<a href="#BC.2.2">表C.2.2</a>给出的90d时，其混凝土名义徐变系数可按<math xmlns="http://www.w3.org/1998/Math/MathML" ><msubsup><mi>ϕ</mi><mrow><mn>0</mn></mrow><mrow><msup><mi></mi><mo>′</mo></msup></mrow></msubsup><mo>=</mo><msub><mi>ϕ</mi><mrow><mn>0</mn></mrow></msub><mi>β</mi><mo stretchy="false">(</mo><msubsup><mi>t</mi><mrow><mn>0</mn></mrow><mrow><msup><mi></mi><mo>′</mo></msup></mrow></msubsup><mo stretchy="false">)</mo><mrow><mo>/</mo></mrow><mi>β</mi><mo stretchy="false">(</mo><msub><mi>t</mi><mrow><mn>0</mn></mrow></msub><mo stretchy="false">)</mo></math>求得，式中<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>ϕ</mi><mrow><mn>0</mn></mrow></msub></math>为<a href="#BC.2.2">表C.2.2</a>所列名义徐变系数，<math xmlns="http://www.w3.org/1998/Math/MathML" ><mi>β</mi><mo stretchy="false">(</mo><msubsup><mi>t</mi><mrow><mn>0</mn></mrow><mrow><msup><mi></mi><mo>′</mo></msup></mrow></msubsup><mo stretchy="false">)</mo></math>和<math xmlns="http://www.w3.org/1998/Math/MathML"><mi>β</mi><mo stretchy="false">(</mo><msub><mi>t</mi><mrow><mn>0</mn></mrow></msub><mo stretchy="false">)</mo></math>按公式(C.2.1-5)计算，其中<math xmlns="http://www.w3.org/1998/Math/MathML"><msub><mi>t</mi><mrow><mn>0</mn></mrow></msub></math>为表列加载龄期，<math xmlns="http://www.w3.org/1998/Math/MathML"><msubsup><mi>t</mi><mrow><mn>0</mn></mrow><mrow><msup><mi></mi><mo>′</mo></msup></mrow></msubsup></math>为90d以外计算所需的加载龄期。</p>

 <p style="text-align:justify"><a href="#idC.2.4"> C.2.4</a> <span id="idC.2.4"> 掺加粉煤灰的混凝土宜通过徐变试验获得符合混凝土材料组成特点的徐变系数。当缺乏足够的试验资料时，掺加粉煤灰的混凝土的徐变系数可按公式(C.2.4)计算：</span></p>   

$$\\phi(t,t_{0})=\\phi(\\alpha ,t_{0})\\cdot\\phi _{0}\\cdot\\beta _{\\mathrm{c}}(t-t_{0})\\tag{C.2.4}$$ 

.. raw:: html 

 <p style="text-align:justify;text-indent:2em;" > 式中，<math xmlns="http://www.w3.org/1998/Math/MathML" ><mi>ϕ</mi><mo stretchy="false">(</mo><mi>α</mi><mo>,</mo><msub><mi>t</mi><mrow><mn>0</mn></mrow></msub><mo stretchy="false">)</mo></math>为粉煤灰混凝土名义徐变修正系数，根据粉煤灰掺量<i>α</i>和加载龄期<i>t</i><sub>0</sub>采用<a href="#BC.2.4">表C.2.4</a>所列值，<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>ϕ</mi><mrow><mn>0</mn></mrow></msub><mo>、</mo><msub><mi>β</mi><mrow><mrow><mi mathvariant="normal">c</mi></mrow></mrow></msub><mo stretchy="false">(</mo><mi>t</mi><mo>−</mo><msub><mi>t</mi><mrow><mn>0</mn></mrow></msub><mo stretchy="false">)</mo></math>应按<a href="#idC.2.1">第C.2.1条</a>的规定计算。 </p>


C.3 钢筋松弛损失中间值与终极值的比值
--------------------------------------------------

.. raw:: html

 <p style="text-align:justify"><a href="#idC.3.1"> C.3.1</a> <span id="idC.3.1"> 当需分阶段计算钢筋松弛损失时，其中间值应根据建立预应力的时间按<a href="#B9C.3.1">表C.3.1</a>确定。钢筋松弛损失的终极值应按<a href="https://jtg-3362.readthedocs.io/zh/latest/06.html#id6.2.6">第6.2.6条</a>计算。</span></p>  

	<table id="biaoge" style="font-family:times new roman">

         <caption style="caption-side:top;text-align: center;color:black" ><b style="text-align:center"> <div id="BC.2.2">表C.2.2 混凝土名义徐变系数<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>φ</mi><mrow><mrow><mi mathvariant="normal">0</mi></mrow></mrow></msub></math></b></caption>	
              
		    <tr>
		     <td  align="center" id="dhbg"width="300px">时间(d)</td>
		     <td  align="center" id="dhbg"width="120px">2</td>
         <td  align="center" id="dhbg"width="120px">10</td>
         <td  align="center" id="dhbg"width="120px">20</td>
         <td  align="center" id="dhbg"width="120px">30</td>
         <td  align="center" id="dhbg"width="120px">40</td>             
        </tr>
		    <tr>
		     <td  align="center" id="dhbg">比值</td>
         <td  align="center" id="dhbg">0.50</td>
         <td  align="center" id="dhbg">0.61</td>
         <td  align="center" id="dhbg">0.74</td> 
		     <td  align="center" id="dhbg">0.87</td>
         <td  align="center" id="dhbg" >1.00</td>
        </tr> 
		   	</table>
 <p> </p>


:math:`\ `	 