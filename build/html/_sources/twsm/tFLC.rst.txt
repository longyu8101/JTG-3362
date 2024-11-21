附录C 混凝土收缩应变和徐变系数计算及钢筋松弛损失中间值与终极值的比值
==============================================================================

.. raw:: html

  <h2 id="test111">附录C 混凝土收缩应变和徐变系数计算及钢筋松弛损失中间值与终极值的比值</h2>

C.1  收缩应变
----------------------

.. raw:: html

 <p style="text-align:justify"><a href="#idtC.1.1"> C.1.1</a> <span id="idtC.1.1"> 、<a href="#idC.1.2"> C.1.2</a> <span id="idC.1.2"> 公式(C.1.1-1)～(C.1.1-5)参照1990年《CEB-FIP模式规范》(以下简称《CEB-FIP规范》)的规定编写。</span></p>  
 <p style="text-align:justify;text-indent:2em;" ><a href="https://jtg-3362.readthedocs.io/zh/latest/FLC.html#BC.1.2">表C.1.2</a>所列数据，可近似地适用于-20~+40℃之间季节性变化的混凝土。如要更精确地考虑，所有表列数值只适用于混凝土平均温度10~20℃之间，否则，应按下列方法对大约从0℃至+80℃的范围、对混凝土平均温度20℃的实际偏差的影响进行修正。按下列公式对名义收缩系数和收缩发展系数进行修正：</p> 
 <p style="text-align:justify;text-indent:2em;" >1 名义收缩系数</p> 

$$\\beta_{\\mathrm{RH,T} }=\\beta_{\\mathrm{RH} }\\beta_{\\mathrm{sT} }\\tag{附 C-1}$$ 
$$\\beta_{\\mathrm{sT} }=1+\\left ( \\dfrac{8}{103-100RH/RH_{0}} \\right ) \\left ( \\dfrac{T/T_{0}-20}{40} \\right ) \\tag{附 C-2}$$ 

.. raw:: html 


 <table border="0" style="font-family:times new roman" id="gongshi">
 <tr>
 <td width="50px" align='center' id="eqzs">式中:</td>
 <td width="30px" align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>β</mi><mrow><mrow><mi mathvariant="normal">R</mi><mi mathvariant="normal">H</mi><mo>,</mo><mi mathvariant="normal">T</mi></mrow></mrow></msub></math></td>
 <td width="40px" align='left' id="eqzs">——</td>
 <td id="eqzs"align='left'>依温度而定的系数，用来代替公式(C.1.1-2)中的<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>β</mi><mrow><mrow><mi mathvariant="normal">R</mi><mi mathvariant="normal">H</mi></mrow></mrow></msub></math>;</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right'  id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>β</mi><mrow><mrow><mi mathvariant="normal">R</mi><mi mathvariant="normal">H</mi></mrow></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">第一阶段施工时附加的其他作用产生的弯矩设计值，取作用标准值乘以作用分项系数1.4;</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right'  id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><mi>RH</mi></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">年平均相对湿度(%)，当40%≤RH＜70%，取RH=55%；70%≤RH＜99，取RH=80%；</td>
 </tr> 
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><mi>T</mi></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">实际温度(℃);</td>
 </tr>
  <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='left' id="eqzs" colspan="3"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>T</mi><mrow><mn>0</mn></mrow></msub><mo>=</mo><mn>1℃</mn></math></td>
 <!-- <td></td> -->
  <!-- <td></td> -->
 </tr> 
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='left' id="eqzs" colspan="3"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>RH</mi><mrow><mn>0</mn></mrow></msub><mo>=</mo><mn>100%</mn></math></td>
 <!-- <td></td> -->
  <!-- <td></td> -->
 </tr>  
 </table>
 <p></p> 
 

 <p style="text-align:justify;text-indent:2em;" >2 收缩发展系数</p> 

$$\\alpha _{\\mathrm{st}}(T)=350(h/h_{0})^{2}\\cdot e ^{-0.06(T/T_{0}-20)}\\tag{附 C-3}$$ 

.. raw:: html 


 <table border="0" style="font-family:times new roman" id="gongshi">
 <tr>
 <td width="50px" align='center' id="eqzs">式中:</td>
 <td width="30px" align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>α</mi><mrow><mrow><mi mathvariant="normal">s</mi><mi mathvariant="normal">t</mi></mrow></mrow></msub><mi>T</mi></math></td>
 <td width="40px" align='left' id="eqzs">——</td>
 <td id="eqzs">依温度而定的系数，用来代替公式(C.1.1-5)中的乘积<math xmlns="http://www.w3.org/1998/Math/MathML" ><mn>350</mn><mo stretchy="false">(</mo><mi>h</mi><mrow><mo>/</mo></mrow><msub><mi>h</mi><mrow><mn>0</mn></mrow></msub><msup><mo stretchy="false">)</mo><mrow><mn>2</mn></mrow></msup></math>;</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
  <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><mi>T</mi></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">实际温度(℃);</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='left' id="eqzs" colspan="3"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>T</mi><mrow><mn>0</mn></mrow></msub><mo>=</mo><mn>1℃</mn></math></td>
 <!-- <td></td> --> 
 <!-- <td></td> -->
 </tr>
 </table>
 <p></p> 
 
 <p style="text-align:justify"><a href="#idtC.1.3"> C.1.3</a> <span id="idtC.1.3"> 按照本条规定，得到混凝土的收缩应变终极值如<a href="#BTC.1">表C-1</a>。</span></p>  
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

         <caption style="caption-side:top;text-align: center;color:black" ><b style="text-align:center"> <div id="BTC.1">表C-1 混凝土收缩应变终极值<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>ε</mi><mrow><mrow><mi mathvariant="normal">c</mi><mi mathvariant="normal">s</mi></mrow></mrow></msub><mo stretchy="false">(</mo><msub><mi>t</mi><mrow><mrow><mi mathvariant="normal">u</mi></mrow></mrow></msub><mo>,</mo><msub><mi>t</mi><mrow><mn>0</mn></mrow></msub><mo stretchy="false">)</mo><mstyle scriptlevel="0"><mspace width="2em"></mspace></mstyle><mo stretchy="false">(</mo><mo>×</mo><msup><mn>10</mn><mrow><mo>−</mo><mn>3</mn></mrow></msup><mo stretchy="false">)</mo></math></caption>	
              
		    <tr>
		     <td  align="center" id="dhbg"width="90px"rowspan="3">加载龄期（d）</td>
		     <td  align="center" id="dhbg"colspan="4">40%≤RH＜70%</td>
          <!-- <td></td> -->
          <!-- <td></td> -->
         <!-- <td></td> -->
         <td  align="center" id="dhbg" colspan="4">70%≤RH＜99%</td>
          <!-- <td></td> -->
          <!-- <td></td> -->
         <!-- <td></td> -->
		    </tr>
		    <tr>
		      <!-- <td></td> -->
				 <td  align="center" id="dhbg"colspan="4">理论厚度h（mm）</td>
		      <!-- <td></td> -->
          <!-- <td></td> -->
         <!-- <td></td> -->
		     <td  align="center" id="dhbg"colspan="4">理论厚度h（mm）</td>
		      <!-- <td></td> -->
          <!-- <td></td> -->
         <!-- <td></td> --> 
		    </tr>        
		    <tr>
		     <!-- <td></td> --> 
				 <td align="center" id="dhbg" width="90px">100</td>
		     <td align="center" id="dhbg" width="90px">200</td>
		     <td align="center" id="dhbg" width="90px">300</td>
		     <td align="center" id="dhbg" width="90px">≥600</td>
		     <td align="center" id="dhbg" width="90px">100</td>
		     <td align="center" id="dhbg" width="90px">200</td>
		     <td align="center" id="dhbg" width="90px">300</td>          
		     <td align="center" id="dhbg" width="90px">≥600</td>  
		    </tr>
		    <tr>
		     <td align="center" id="dhbg" >3~7</td>
				 <td align="center" id="dhbg" >0.50</td>
		     <td align="center" id="dhbg" >0.45</td>
		     <td align="center" id="dhbg" >0.38</td>
		     <td align="center" id="dhbg" >0.25</td>
		     <td align="center" id="dhbg" >0.30</td>
		     <td align="center" id="dhbg" >0.26</td>
		     <td align="center" id="dhbg" >0.23</td>          
		     <td align="center" id="dhbg" >0.15</td>  
		    </tr>  
		     <tr>
		     <td align="center" id="dhbg" >14</td>
				 <td align="center" id="dhbg" >0.43</td>
		     <td align="center" id="dhbg" >0.41</td>
		     <td align="center" id="dhbg" >0.36</td>
		     <td align="center" id="dhbg" >0.24</td>
		     <td align="center" id="dhbg" >0.25</td>
		     <td align="center" id="dhbg" >0.24</td>
		     <td align="center" id="dhbg" >0.21</td>          
		     <td align="center" id="dhbg" >0.14</td>  
		    </tr>  
		    <tr>
		     <td align="center" id="dhbg" >28</td>
				 <td align="center" id="dhbg" >0.38</td>
		     <td align="center" id="dhbg" >0.38</td>
		     <td align="center" id="dhbg" >0.34</td>
		     <td align="center" id="dhbg" >0.23</td>
		     <td align="center" id="dhbg" >0.22</td>
		     <td align="center" id="dhbg" >0.22</td>
		     <td align="center" id="dhbg" >0.20</td>          
		     <td align="center" id="dhbg" >0.13</td>  
		    </tr>  
		    <tr>
		     <td align="center" id="dhbg" >60</td>
				 <td align="center" id="dhbg" >0.31</td>
		     <td align="center" id="dhbg" >0.34</td>
		     <td align="center" id="dhbg" >0.32</td>
		     <td align="center" id="dhbg" >0.22</td>
		     <td align="center" id="dhbg" >0.18</td>
		     <td align="center" id="dhbg" >0.20</td>
		     <td align="center" id="dhbg" >0.19</td>          
		     <td align="center" id="dhbg" >0.12</td>  
		    </tr>  
		    <tr>
		     <td align="center" id="dhbg" >90</td>
				 <td align="center" id="dhbg" >0.27</td>
		     <td align="center" id="dhbg" >0.32</td>
		     <td align="center" id="dhbg" >0.30</td>
		     <td align="center" id="dhbg" >0.21</td>
		     <td align="center" id="dhbg" >0.16</td>
		     <td align="center" id="dhbg" >0.19</td>
		     <td align="center" id="dhbg" >0.18</td>          
		     <td align="center" id="dhbg" >0.12</td>  
		    </tr>  
		</table>
   <p style="text-indent:2em;" ><font size="2">注：1.本表适用于由一般的硅酸盐类水泥或快硬水泥配制而成的混凝土。<br/>
  &emsp;&emsp; &emsp;&emsp; &emsp;&nbsp;2.本表适用于季节性变化的平均温度-20~+40℃。<br/>
  &emsp;&emsp; &emsp;&emsp; &emsp;&nbsp;3.表中数值系按强度等级C40混凝土计算所得，对C50及以上混凝土，表列数值应乘以<math xmlns="http://www.w3.org/1998/Math/MathML"><msqrt><mstyle displaystyle="true" scriptlevel="0"><mfrac><mn>32.4</mn><msub><mi>f</mi><mrow><mrow><mi mathvariant="normal">c</mi><mi mathvariant="normal">k</mi></mrow></mrow></msub></mfrac></mstyle></msqrt></math>，式中<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>f</mi><mrow><mrow><mi mathvariant="normal">c</mi><mi mathvariant="normal">k</mi></mrow></mrow></msub></math>为混凝土轴心抗压强度标准值(MPa)。<br/>
  &emsp;&emsp; &emsp;&emsp; &emsp;&nbsp;4.计算时，表中年平均相对湿度40%RH≤70%，取RH=55%；70≤RH＜99%，取RH=80%。<br/>
  &emsp;&emsp; &emsp;&emsp; &emsp;&nbsp;5.表中理论厚度<math xmlns="http://www.w3.org/1998/Math/MathML" ><mi>h</mi><mo>=</mo><mn>2</mn><mi>A</mi><mrow><mo>/</mo></mrow><mi>u</mi></math>，<math xmlns="http://www.w3.org/1998/Math/MathML" ><mi>A</mi></math>为构件截面面积，u为构件与大气接触的周边长度。当构件为变截面时，<math xmlns="http://www.w3.org/1998/Math/MathML"><mi>A</mi></math>和<math xmlns="http://www.w3.org/1998/Math/MathML" ><mi>u</mi></math>均可取其平均值。<br/>
  &emsp;&emsp; &emsp;&emsp; &emsp;&nbsp;6.表中数值按10年的延续期计算。<br/>
  &emsp;&emsp; &emsp;&emsp; &emsp;&nbsp;7.构件的实际传力锚固龄期、加载龄期或理论厚度为表列数值中间值时，徐变系数终极值可按直线内插法取值。</font></p>



C.2 徐变系数
----------------------

.. raw:: html

 <p style="text-align:justify"><a href="#idC.2.1"> C.2.1</a> <span id="idC.2.1"> 、<a href="#idC.2.2"> C.2.2</a> <span id="idC.2.2"> 公式(C.2.1-1)～(C.2.1-7)参照1990年《CEB-FIP模式规范》(以下简称《CEB-FIP规范》)的规定编写。</span></p>  
 <p style="text-align:justify;text-indent:2em;" > <a href="https://jtg-3362.readthedocs.io/zh/latest/FLC.html#BC.2.2">表C.2.2</a>所列数据，可近似地适用于-20~+40℃之间季节性变化的混凝土。如要更精确地考虑，所有表列数值只适用于混凝土平均温度10~20℃之间，否则，应按下列方法对大约从0℃至+80℃的范围、对混凝土平均温度20℃的实际偏差的影响进行修正。按下列公式对名义徐变系数和徐变发展系数进行修正：</p>
 
 <p style="text-align:justify;text-indent:2em;" >1 名义收缩系数</p> 

$$\\phi _{\\mathrm{RH,T}}=\\phi _{\\mathrm{T}}+(\\phi _{\\mathrm{RH}}-1)\\cdot\\phi^{1.2} _{\\mathrm{T}}\\tag{附 C-4}$$ 
$$\\phi _{\\mathrm{T}}=e^{0.015(T/T_{0}-20)}\\tag{附 C-5}$$ 

.. raw:: html 


 <table border="0" style="font-family:times new roman" id="gongshi">
 <tr>
 <td width="50px" align='center' id="eqzs">式中:</td>
 <td width="30px" align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>ϕ</mi><mrow><mrow><mi mathvariant="normal">R</mi><mi mathvariant="normal">H</mi><mo>,</mo><mi mathvariant="normal">T</mi></mrow></mrow></msub></math></td>
 <td width="40px" align='left' id="eqzs">——</td>
 <td id="eqzs"align='left'>依温度而定的系数，用来代替公式(C.2.1-2)<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>ϕ</mi><mrow><mrow><mi mathvariant="normal">R</mi><mi mathvariant="normal">H</mi></mrow></mrow></msub></math>;</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right'  id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>ϕ</mi><mrow><mrow><mi mathvariant="normal">R</mi><mi mathvariant="normal">H</mi></mrow></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">公式(C.2.1-3)计算的系数；</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><mi>T</mi></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">实际温度(℃);</td>
 </tr>
  <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='left' id="eqzs" colspan="3"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>T</mi><mrow><mn>0</mn></mrow></msub><mo>=</mo><mn>1℃</mn></math></td>
 <!-- <td></td> -->
  <!-- <td></td> -->
 </tr> 
 </table>
 <p></p> 
 

 <p style="text-align:justify;text-indent:2em;" >2 收缩发展系数</p> 

$$\\beta_{\\mathrm{H,T}}=\\beta_{\\mathrm{H}}\\beta_{\\mathrm{T}}\\tag{附 C-6}$$ 
$$\\beta_{\\mathrm{T}}=e^{[1500/(273+T/T_{0})-5.12]}\\tag{附 C-7}$$ 

.. raw:: html 


 <table border="0" style="font-family:times new roman" id="gongshi">
 <tr>
 <td width="50px" align='center' id="eqzs">式中:</td>
 <td width="30px" align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>β</mi><mrow><mrow><mi mathvariant="normal">H</mi><mo>,</mo><mi mathvariant="normal">T</mi></mrow></mrow></msub></math></td>
 <td width="40px" align='left' id="eqzs">——</td>
 <td id="eqzs"align='left'>与温度有关的系数，用来代替公式(C.2.1-6)中的<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>β</mi><mrow><mrow><mi mathvariant="normal">R</mi><mi mathvariant="normal">H</mi></mrow></mrow></msub></math>;</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right'  id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>β</mi><mrow><mrow><mi mathvariant="normal">R</mi><mi mathvariant="normal">H</mi></mrow></mrow></msub></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">按公式(C.2.1-7)计算的系数；</td>
 </tr>
 <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='right' id="eqzs"><math xmlns="http://www.w3.org/1998/Math/MathML" ><mi>T</mi></math></td>
 <td  align='left' id="eqzs">——</td>
 <td id="eqzs">实际温度(℃);</td>
 </tr>
  <tr>
 <td  align='left' id="eqzs"> </td>
 <td  align='left' id="eqzs" colspan="3"><math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>T</mi><mrow><mn>0</mn></mrow></msub><mo>=</mo><mn>1℃</mn></math></td>
 <!-- <td></td> -->
  <!-- <td></td> -->
 </tr> 
 </table>
 <p></p> 



 <p style="text-align:justify;text-indent:2em;" >此外，<a href="https://jtg-3362.readthedocs.io/zh/latest/FLC.html#BC.2.2">表C.2.2</a>中数值系按强度等级C40混凝土计算所得。试验表明，高强的混凝土收缩量，尤其是徐变量要比普通强度的混凝土有所减少，且与<math xmlns="http://www.w3.org/1998/Math/MathML" ><msqrt><msub><mi>f</mi><mrow><mrow><mi mathvariant="normal">c</mi><mi mathvariant="normal">k</mi></mrow></mrow></msub></msqrt></math>成反比。因此，本规范对C50及以上混凝土的收缩应变和徐变系数，按计算所得的表列值乘以<math xmlns="http://www.w3.org/1998/Math/MathML" ><msqrt><mstyle displaystyle="true" scriptlevel="0"><mfrac><mn>32.4</mn><msub><mi>f</mi><mrow><mrow><mi mathvariant="normal">c</mi><mi mathvariant="normal">k</mi></mrow></mrow></msub></mfrac></mstyle></msqrt></math>折减之。式中32.4为C50混凝土轴心抗压强度标准值，<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>f</mi><mrow><mrow><mi mathvariant="normal">c</mi><mi mathvariant="normal">k</mi></mrow></mrow></msub></math>为C50及以上混凝土轴心抗压强度标准值。</p>
 <p style="text-align:justify"><a href="#idtC.2.3"> C.2.3</a> <span id="idtC.2.3"> 按照本条规定，得到混凝土的徐变系数终极值如<a href="#BTC.2">表C-2</a>。</span></p>  

 <p style="text-align:justify;text-indent:2em;" > 参数<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>β</mi><mrow><mrow><mi mathvariant="normal">c</mi></mrow></mrow></msub></math>与混凝土强度等级有关，不同混凝土强度等级对应的<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>β</mi><mrow><mrow><mi mathvariant="normal">c</mi></mrow></mrow></msub></math>值如表B-1所示。</p>
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

         <caption style="caption-side:top;text-align: center;color:black" ><b style="text-align:center"> <div id="BTC.2">表C-2 混凝土徐变系数终极值<math xmlns="http://www.w3.org/1998/Math/MathML" ><mi>ϕ</mi><mo stretchy="false">(</mo><msub><mi>t</mi><mrow><mrow><mi mathvariant="normal">u</mi></mrow></mrow></msub><mo>,</mo><msub><mi>t</mi><mrow><mn>0</mn></mrow></msub><mo stretchy="false">)</mo></math></caption>	
              
		    <tr>
		     <td  align="center" id="dhbg"width="90px"rowspan="3">加载龄期（d）</td>
		     <td  align="center" id="dhbg"colspan="4">40%≤RH＜70%</td>
          <!-- <td></td> -->
          <!-- <td></td> -->
         <!-- <td></td> -->
         <td  align="center" id="dhbg" colspan="4">70%≤RH＜99%</td>
          <!-- <td></td> -->
          <!-- <td></td> -->
         <!-- <td></td> -->
		    </tr>
		    <tr>
		      <!-- <td></td> -->
				 <td  align="center" id="dhbg"colspan="4">理论厚度h（mm）</td>
		      <!-- <td></td> -->
          <!-- <td></td> -->
         <!-- <td></td> -->
		     <td  align="center" id="dhbg"colspan="4">理论厚度h（mm）</td>
		      <!-- <td></td> -->
          <!-- <td></td> -->
         <!-- <td></td> --> 
		    </tr>        
		    <tr>
		     <!-- <td></td> --> 
				 <td align="center" id="dhbg" width="90px">100</td>
		     <td align="center" id="dhbg" width="90px">200</td>
		     <td align="center" id="dhbg" width="90px">300</td>
		     <td align="center" id="dhbg" width="90px">≥600</td>
		     <td align="center" id="dhbg" width="90px">100</td>
		     <td align="center" id="dhbg" width="90px">200</td>
		     <td align="center" id="dhbg" width="90px">300</td>          
		     <td align="center" id="dhbg" width="90px">≥600</td>  
		    </tr>
		    <tr>
		     <td align="center" id="dhbg" >3</td>
				 <td align="center" id="dhbg" >3.78</td>
		     <td align="center" id="dhbg" >3.36</td>
		     <td align="center" id="dhbg" >3.14</td>
		     <td align="center" id="dhbg" >2.79</td>
		     <td align="center" id="dhbg" >2.73</td>
		     <td align="center" id="dhbg" >2.52</td>
		     <td align="center" id="dhbg" >2.39</td>          
		     <td align="center" id="dhbg" >2.20</td>  
		    </tr>  
		    <tr>
		     <td align="center" id="dhbg" >7</td>
				 <td align="center" id="dhbg" >3.23</td>
		     <td align="center" id="dhbg" >2.88</td>
		     <td align="center" id="dhbg" >2.68</td>
		     <td align="center" id="dhbg" >2.39</td>
		     <td align="center" id="dhbg" >2.32</td>
		     <td align="center" id="dhbg" >2.15</td>
		     <td align="center" id="dhbg" >2.05</td>          
		     <td align="center" id="dhbg" >1.88</td>  
		    </tr>  
		    <tr>
		     <td align="center" id="dhbg" >14</td>
				 <td align="center" id="dhbg" >2.83</td>
		     <td align="center" id="dhbg" >2.51</td>
		     <td align="center" id="dhbg" >2.35</td>
		     <td align="center" id="dhbg" >2.09</td>
		     <td align="center" id="dhbg" >2.04</td>
		     <td align="center" id="dhbg" >1.89</td>
		     <td align="center" id="dhbg" >1.79</td>          
		     <td align="center" id="dhbg" >1.65</td>  
		    </tr>  
		    <tr>
		     <td align="center" id="dhbg" >28</td>
				 <td align="center" id="dhbg" >2.48</td>
		     <td align="center" id="dhbg" >2.20</td>
		     <td align="center" id="dhbg" >2.06</td>
		     <td align="center" id="dhbg" >1.83</td>
		     <td align="center" id="dhbg" >1.79</td>
		     <td align="center" id="dhbg" >1.65</td>
		     <td align="center" id="dhbg" >1.58</td>          
		     <td align="center" id="dhbg" >1.44</td>  
		    </tr>  
		    <tr>
		     <td align="center" id="dhbg" >60</td>
				 <td align="center" id="dhbg" >2.14</td>
		     <td align="center" id="dhbg" >1.91</td>
		     <td align="center" id="dhbg" >1.78</td>
		     <td align="center" id="dhbg" >1.58</td>
		     <td align="center" id="dhbg" >1.55</td>
		     <td align="center" id="dhbg" >1.43</td>
		     <td align="center" id="dhbg" >1.36</td>          
		     <td align="center" id="dhbg" >1.25</td>  
		    </tr>  
		    <tr>
		     <td align="center" id="dhbg" >90</td>
				 <td align="center" id="dhbg" >1.99</td>
		     <td align="center" id="dhbg" >1.76</td>
		     <td align="center" id="dhbg" >1.65</td>
		     <td align="center" id="dhbg" >1.46</td>
		     <td align="center" id="dhbg" >1.44</td>
		     <td align="center" id="dhbg" >1.32</td>
		     <td align="center" id="dhbg" >1.26</td>          
		     <td align="center" id="dhbg" >1.15</td>  
		    </tr>  
		</table>
   <p style="text-indent:2em;" ><font size="2">注：1.本表适用于由一般的硅酸盐类水泥或快硬水泥配制而成的混凝土。<br/>
  &emsp;&emsp; &emsp;&emsp; &emsp;&nbsp;2.本表适用于季节性变化的平均温度-20~+40℃。<br/>
  &emsp;&emsp; &emsp;&emsp; &emsp;&nbsp;3.表中数值系按强度等级C40混凝土计算所得，对C50及以上混凝土，表列数值应乘以<math xmlns="http://www.w3.org/1998/Math/MathML"><msqrt><mstyle displaystyle="true" scriptlevel="0"><mfrac><mn>32.4</mn><msub><mi>f</mi><mrow><mrow><mi mathvariant="normal">c</mi><mi mathvariant="normal">k</mi></mrow></mrow></msub></mfrac></mstyle></msqrt></math>，式中<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>f</mi><mrow><mrow><mi mathvariant="normal">c</mi><mi mathvariant="normal">k</mi></mrow></mrow></msub></math>为混凝土轴心抗压强度标准值(MPa)。<br/>
  &emsp;&emsp; &emsp;&emsp; &emsp;&nbsp;4.计算时，表中年平均相对湿度40%RH≤70%，取RH=55%；70≤RH＜99%，取RH=80%。<br/>
  &emsp;&emsp; &emsp;&emsp; &emsp;&nbsp;5.表中理论厚度<math xmlns="http://www.w3.org/1998/Math/MathML" ><mi>h</mi><mo>=</mo><mn>2</mn><mi>A</mi><mrow><mo>/</mo></mrow><mi>u</mi></math>，<math xmlns="http://www.w3.org/1998/Math/MathML" ><mi>A</mi></math>为构件截面面积，u为构件与大气接触的周边长度。当构件为变截面时，<math xmlns="http://www.w3.org/1998/Math/MathML"><mi>A</mi></math>和<math xmlns="http://www.w3.org/1998/Math/MathML" ><mi>u</mi></math>均可取其平均值。<br/>
  &emsp;&emsp; &emsp;&emsp; &emsp;&nbsp;6.表中数值按10年的延续期计算。<br/>
  &emsp;&emsp; &emsp;&emsp; &emsp;&nbsp;7.构件的实际传力锚固龄期、加载龄期或理论厚度为表列数值中间值时，徐变系数终极值可按直线内插法取值。</font></p>



 <p style="text-align:justify"><a href="#idtC.2.4"> C.2.4</a> <span id="idtC.2.4"> 原规范中混凝土收缩徐变计算主要参照《CEB-FIP 规范》的计算模型。其适用范围为：应力水平<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>σ</mi><mrow><mrow><mi mathvariant="normal">c</mi></mrow></mrow></msub><mrow><mo>/</mo></mrow><msub><mi>f</mi><mrow><mrow><mi mathvariant="normal">c</mi></mrow></mrow></msub><mo stretchy="false">(</mo><msub><mi>t</mi><mrow><mn>0</mn></mrow></msub><mo stretchy="false">)</mo><mo>&lt;</mo><mn>0.4</mn></math>，暴露在平均温度5～30℃和平均相对湿度RH=40% ~ 99%的环境中，并且主要针对普通硅酸盐水泥混凝土。本次规范修订，考虑到目前大部分预应力混凝土结构为提高混凝土的工作性、耐久性等而掺加矿物掺合料的特点，结合交通运输部西部项目课题《桥梁混凝土性能长期演变规律与跟踪观测技术的研究》(2006318223 02—08)有关掺粉煤灰的混凝土的徐变特性的研究成果，增加了掺粉煤灰混凝土的徐变系数。</span></p>   
 <p style="text-align:justify;text-indent:2em;" >混凝土掺加粉煤灰后，影响与徐变相关主要机理为：</p>
 <ol>
 <li>影响混凝土的强度发展：预应力混凝土的张拉一般在7天之内完成，而掺加粉煤灰对混凝土早期强度的影响最为明显；</li>
 <li>影响混凝土的细微观结构：掺加粉煤灰以后，混凝土中胶凝材料的水化机理改变、细微观结构发生变化，影响混凝土材料徐变效应。</li>
 </ol>

 <p style="text-align:justify;text-indent:2em;" >该课题采用C40混凝土和C50混凝土，试验研究了掺加粉煤灰混凝土的徐变特性，试验结果见<a href="#figTC.1">图 C-1</a>～<a href="#figTC.4">图 C-4</a>。</p> 
 <p style="text-align:justify;text-indent:2em;" >可以看出掺加粉煤灰后规范模型计算值与试验实测值有较大的差别，偏差可能高达40%考虑到掺加粉煤灰以后对混凝土材料与徐变特性相关的细微观结构、早期水化效应等影响，该课题提出对混凝土名义徐变系数进行修正的方法，修正系数见式(附C-8)。</p> 

$$\\varphi (\\alpha ,t_{0})=\\beta(\\alpha )\\cdot \\gamma(\\alpha ,t_{0})\\tag{附 C-8}$$ 


.. raw:: html 

 <p style="text-align:justify;text-indent:2em;" >式中：<math xmlns="http://www.w3.org/1998/Math/MathML" ><mi>γ</mi><mo stretchy="false">(</mo><mi>α</mi><mo>,</mo><msub><mi>t</mi><mrow><mn>0</mn></mrow></msub><mo stretchy="false">)</mo></math>是混凝土强度修正系数；<math xmlns="http://www.w3.org/1998/Math/MathML" ><mi>β</mi><mo stretchy="false">(</mo><mi>α</mi><mo stretchy="false">)</mo></math>是与粉煤灰掺量有关的混凝土材料修正系数。根据试验结果得到的修正系数计算表达式见式(附C-2)。</p> 

$$\\left.\\begin{matrix} \\gamma(\\alpha ,t_{0})=\\dfrac{1}{[1.451-1.689\\times t^{-0.360}_{0}\\times(1+\\alpha )^{0.416}]^{0.5}}\\\\\\beta(a)=1-1.0273\\alpha ^{0.4218}\\end{matrix}\\right\\}\\tag{附 C-9}$$ 


.. raw:: html 



 <p style="text-align:justify;text-indent:2em;" > <a href="https://jtg-3362.readthedocs.io/zh/latest/FLC.html#BC.3.1">表C.3.1</a>即是根据式(附C-9)计算得到。</p>
 <div align="center"><img id="figTC.1" src="../_static/fig/TC.1.png" alt="Picture" width="350px"></div>
  <p style="color: dimgray;text-align: center;">图 C-1 15%煤灰掺量C40混凝土试验曲线、规范模型与修正模型计算值对比</p>
  <script type="text/javascript">var viewer = new Viewer(document.getElementById('figTC.1'));</script>

 <div align="center"><img id="figTC.2" src="../_static/fig/TC.2.png" alt="Picture" width="350px"></div>
  <p style="color: dimgray;text-align: center;">图 C-2 30%煤灰掺量C40混凝土试验曲线、规范模型与修正模型计算值对比</p>
  <script type="text/javascript">var viewer = new Viewer(document.getElementById('figTC.2'));</script>

 <div align="center"><img id="figTC.3" src="../_static/fig/TC.3.png" alt="Picture" width="350px"></div>
  <p style="color: dimgray;text-align: center;">图 C-3 10%煤灰掺量C50混凝土试验曲线、规范模型与修正模型计算值对比</p>
  <script type="text/javascript">var viewer = new Viewer(document.getElementById('figTC.3'));</script>

 <div align="center"><img id="figTC.4" src="../_static/fig/TC.4.png" alt="Picture" width="350px"></div>
  <p style="color: dimgray;text-align: center;">图 C-4 30%煤灰掺量C50混凝土试验曲线、规范模型与修正模型计算值对比</p>
  <script type="text/javascript">var viewer = new Viewer(document.getElementById('figTC.4'));</script>    



:math:`\ `	