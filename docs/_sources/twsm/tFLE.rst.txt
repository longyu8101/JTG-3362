附录E 受压构件计算长度的简化计算公式 (新增)
==============================================================================

.. raw:: html

  <h2 id="test111">附录E 受压构件计算长度的简化计算公式 (新增)</h2>



.. raw:: html

 <p style="text-align:justify;text-indent:2em;" > <a href="#figTE.1">图 E-1 a)</a>为理想化的偏心受压构件，端部受支座提供的转动约束和横向约束。将这些约束理想化为转动和横向弹簧，其弹簧刚度分别用<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>K</mi><mrow><mi mathvariant="normal">A</mi></mrow></msub><mo>、</mo><msub><mi>K</mi><mrow><mi mathvariant="normal">B</mi></mrow></msub><mo>和</mo><msub><mi>K</mi><mrow><mi mathvariant="normal">F</mi></mrow></msub></math>，表示，如<a href="#figTE.1">图 E-1 B)</a>。构件弯矩、转角和侧向位移与构件刚度<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>K</mi><mrow><mi>A</mi></mrow></msub><mo>、</mo><msub><mi>K</mi><mrow><mi>B</mi></mrow></msub><mo>和</mo><msub><mi>K</mi><mrow><mi>F</mi></mrow></msub></math>，具有如下关系：</p>

$$K_{\\mathrm{A} }=\\dfrac{M_{\\mathrm{A} }}{\\theta _{\\mathrm{A} }}\\tag{附 E-1}$$ 
$$K_{\\mathrm{B} }=\\dfrac{M_{\\mathrm{B} }}{\\theta _{\\mathrm{B} }}\\tag{附 E-2}$$ 
$$K_{\\mathrm{F} }=\\dfrac{M_{\\mathrm{A} }+M_{\\mathrm{B} }+N\\Delta} {\\Delta l}\\tag{附 E-3}$$ 

.. raw:: html  

 <div align="center"><img id="figTE.1" src="../_static/fig/TE.1.png" alt="Picture" width="400px"></div>
  <p style="color: dimgray;text-align: center;">图 E-1 弹性约束柱</p>
  <script type="text/javascript">var viewer = new Viewer(document.getElementById('figTE.1'));</script>    

 <p style="text-align:justify;text-indent:2em;" > 式中，<math xmlns="http://www.w3.org/1998/Math/MathML" ><mi>N</mi></math>为构件承受的轴力；<math xmlns="http://www.w3.org/1998/Math/MathML" ><mi>△</mi></math>为构件两端的相对位移；<math xmlns="http://www.w3.org/1998/Math/MathML" ><mi>l</mi></math>为构件实际长度；<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>M</mi><mrow><mrow><mi mathvariant="normal">A</mi></mrow></mrow></msub></math>、<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>M</mi><mrow><mrow><mi mathvariant="normal">B</mi></mrow></mrow></msub></math>分别为构件两端弯矩，其转角位移方程分别为：</p>

$$M_{\\mathrm{A}}=\\dfrac{EI}{l}\\left [ S_{jj}\\theta _{\\mathrm{A} }+S_{ij}\\theta _{\\mathrm{B} }-(S_{ii}+S_{ij})\\dfrac{\\Delta }{l}  \\right ] \\tag{附 E-4}$$ 
$$M_{\\mathrm{B}}=\\dfrac{EI}{l}\\left [ S_{ji}\\theta _{\\mathrm{A} }+S_{jj}\\theta _{\\mathrm{B} }-(S_{ji}+S_{jj})\\dfrac{\\Delta }{l}  \\right ] \\tag{附 E-5}$$ 

.. raw:: html 

 <p style="text-align:justify;text-indent:2em;" > 式中，<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>S</mi><mrow><mi>i</mi><mi>i</mi></mrow></msub><mo>、</mo><msub><mi>S</mi><mrow><mi>i</mi><mi>j</mi></mrow></msub><mo>、</mo><msub><mi>S</mi><mrow><mi>j</mi><mi>i</mi></mrow></msub></math>和<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>S</mi><mrow><mi>j</mi><mi>j</mi></mrow></msub></math>为稳定函数，按下式计算：</p>

$$ S_{ii}= S_{jj}=\\dfrac{\\lambda l\\sin\\lambda l-(\\lambda l)^{2}\\cos\\lambda l}{2-2\\cos\\lambda l-\\lambda l\\sin\\lambda l}\\tag{附 E-6}$$ 
$$ S_{ij}= S_{ji}=\\dfrac{(\\lambda l)^{2}-\\lambda l\\sin\\lambda l}{2-2\\cos\\lambda l-\\lambda l\\sin\\lambda l}\\tag{附 E-7}$$ 

.. raw:: html 

 <p style="text-align:justify;text-indent:2em;" > 式中，<math xmlns="http://www.w3.org/1998/Math/MathML" ><mi>λ</mi><mo>=</mo><msqrt><mstyle displaystyle="true" scriptlevel="0"><mfrac><mi>N</mi><mrow><mi>E</mi><mi>I</mi></mrow></mfrac></mstyle></msqrt></math>。</p>
 <p style="text-align:justify;text-indent:2em;" > 将式(E-4)和式(E-5)代入式(E-1)~(E-3),经简化后可得：</p> 

$$\\small{\\left [ \\begin{matrix}S_{ii}+k_{\\mathrm{A} }& S_{ij} &-(S_{ii}+S_{ij}) \\\\S_{ij} & S_{ii}+k_{\\mathrm{B} } &-(S_{ii}+S_{ij}) \\\\-(S_{ii}+S_{ij})&-(S_{ii}+S_{ij})&2(S_{ii}+S_{ij})-(kl)^{2}+k_{\\mathrm{F}}\\end{matrix} \\right ] \\left [ \\begin{matrix}\\theta _{\\mathrm{A} } \\\\\\theta _{\\mathrm{B} } \\\\\\frac{\\Delta }{l}\\end{matrix} \\right ] =\\left [  \\begin{matrix}0 \\\\0 \\\\0\\end{matrix}\\right ] }\\tag{附 E-8}$$ 

.. raw:: html 

 <p style="text-align:justify;text-indent:2em;" > 其中，</p> 

$$k_{\\mathrm{A}}=\\dfrac{k_{\\mathrm{A}}l}{EI},k_{\\mathrm{B}}=\\dfrac{k_{\\mathrm{B}}l}{EI},k_{\\mathrm{F}}=\\dfrac{k_{\\mathrm{F}}l^{3}}{EI}$$ 

.. raw:: html 

 <p style="text-align:justify;text-indent:2em;" > 式(E-8)可用矩阵符号表示为：</p> 

$$ KD=0\\tag{附 E-9}$$ 

.. raw:: html 

 <p style="text-align:justify;text-indent:2em;" > 式中，<i>K</i>为刚度矩阵，<i>D</i>为变形矩阵。为求得有效解，须取：</p> 

$$\\mathrm{det} \\left | K \\right | =0\\tag{附 E-10}$$ 
$$ \\small{即\\hspace{2cm}\\begin{vmatrix}S_{ii} +k_{\\mathrm{A} } &S_{ij}  &-(S_{ii}+S_{ij}) \\\\ S_{ij} & S_{ij} +k_{\\mathrm{B} } &-(S_{ii}+S_{ij}) \\\\ -(S_{ii}+S_{ij}) & -(S_{ii}+S_{ij}) &2(S_{ii}+S_{ij})-(kl)^{2}+k_{\\mathrm{F} }\\end{vmatrix}=0}\\tag{附 E-11}$$ 

.. raw:: html 

 <p style="text-align:justify;text-indent:2em;" > 整理式(E-11)，得：</p>

$$ \\small{\\begin{array}{l}[k_{\\mathrm{A}}+k_{\\mathrm{B}}+k_{\\mathrm{F}}-(\\lambda l)^{2}](S_{ii}^{2}-S_{ij}^{2})+\\{(k_{\\mathrm{A}}+k_{\\mathrm{B}})[k_{\\mathrm{F}}-(\\lambda l)^{2}]+2k_{\\mathrm{A}}k_{\\mathrm{B}}\\} S_{ii}\\\\+2k_{\\mathrm{A}}k_{\\mathrm{B}}S_{ij}+k_{\\mathrm{A}}k_{\\mathrm{B}}[k_{\\mathrm{F}}-(\\lambda l)^{2}]=0\\end{array}} \\tag{附 E-12}$$ 
$$\\small{即\\hspace{2cm}\\begin{array}{l}\\left[1+\\dfrac{k_{\\mathrm{F}}-(\\lambda l)^{2}}{k_{\\mathrm{A}}+k_{\\mathrm{B}}}\\right](S_{ii}^{2}-S_{ij}^{2})+\\left[k_{\\mathrm{F}}-(\\lambda l)^{2}+\\dfrac{2k_{\\mathrm{A}}k_{\\mathrm{A}}}{k_{\\mathrm{A}}+k_{\\mathrm{A}}}\\right]S_{ii}\\\\+\\dfrac{2k_{\\mathrm{A}}k_{\\mathrm{B}}}{k_{\\mathrm{A}}+k_{\\mathrm{B}}}S_{ij}+\\dfrac{k_{\\mathrm{A}}k_{\\mathrm{B}}}{k_{\\mathrm{A}}+k_{\\mathrm{B}}}[k_{\\mathrm{F}}-(\\lambda l)^{2}]=0\\end{array}} \\tag{附 E-13}$$ 

.. raw:: html 

 <p style="text-align:justify;text-indent:2em;" > 将式(E-6)和式(E-7)代入式(E-13)得：</p>


$$\\small{\\begin{array}{l}\\left [ 1+\\dfrac{k_{\\mathrm{F}}-\\left(\\dfrac{\\pi}{k}\\right)^{2}}{k_{\\mathrm{A}}+k_{\\mathrm{B}}} \\right ] \\left ( \\dfrac{\\pi}{k} \\right )^{2} +\\left [k_{\\mathrm{F}} -\\left ( \\dfrac{\\pi}{k} \\right )^{2} +\\dfrac{2k_{\\mathrm{A}}k_{\\mathrm{B}}}{k_{\\mathrm{A}}+k_{\\mathrm{B}}}\\right ]\\left ( 1-\\dfrac{\\pi/k}{\\tan(\\pi/k)} \\right ) \\\\+\\dfrac{2k_{\\mathrm{A}}k_{\\mathrm{B}}}{k_{\\mathrm{A}}+k_{\\mathrm{B}}}\\left[\\dfrac{\\pi/k}{\\sin(\\pi/k)} -1\\right ]+\\dfrac{2k_{\\mathrm{A}}k_{\\mathrm{B}}}{k_{\\mathrm{A}}+k_{\\mathrm{B}}}\\left[k_{\\mathrm{F}}-\\left ( \\dfrac{\\pi}{k} \\right )^{2} \\right]\\left[ \\dfrac{2\\tan(\\pi/2k)}{\\pi/k}\\right]=0\\end{array} }\\tag{附 E-14}$$ 

.. raw:: html 

 <p style="text-align:justify;text-indent:2em;" > 式中<math xmlns="http://www.w3.org/1998/Math/MathML" ><mi>λ</mi><mi>l</mi><mo>=</mo><msqrt><mstyle displaystyle="true" scriptlevel="0"><mfrac><mi>N</mi><mrow><mi>E</mi><mi>I</mi></mrow></mfrac></mstyle></msqrt><mi>l</mi><mo>=</mo><mi>π</mi><msqrt><mstyle displaystyle="true" scriptlevel="0"><mfrac><mi>N</mi><msub><mi>N</mi><mrow><mrow><mi mathvariant="normal">e</mi></mrow></mrow></msub></mfrac></mstyle></msqrt><mo>=</mo><mstyle displaystyle="true" scriptlevel="0"><mfrac><mi>π</mi><mi>k</mi></mfrac></mstyle></math>，<math xmlns="http://www.w3.org/1998/Math/MathML" ><mi>k</mi></math>为计算长度系数，<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>N</mi><mrow><mrow><mi mathvariant="normal">e</mi></mrow></mrow></msub><mo>=</mo><mstyle displaystyle="true" scriptlevel="0"><mfrac><mrow><msup><mi>π</mi><mrow><mn>2</mn></mrow></msup><mi>E</mi><mi>I</mi></mrow><msup><mi>l</mi><mrow><mn>2</mn></mrow></msup></mfrac></mstyle></math> ，<math xmlns="http://www.w3.org/1998/Math/MathML" ><mi>N</mi><mo>=</mo><mstyle displaystyle="true" scriptlevel="0"><mfrac><mrow><msup><mi>π</mi><mrow><mn>2</mn></mrow></msup><mi>E</mi><mi>I</mi></mrow><mrow><mo stretchy="false">(</mo><mi>k</mi><mi>l</mi><msup><mo stretchy="false">)</mo><mrow><mn>2</mn></mrow></msup></mrow></mfrac></mstyle></math>。</p>
 <p style="text-align:justify;text-indent:2em;" > 对于一端固定、一端有转动和水平弹性约束的构件，底端固支约束，即<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>k</mi><mrow><mrow><mi mathvariant="normal">F</mi></mrow></mrow></msub><mo>=</mo><mi mathvariant="normal">∞</mi></math>，式(E-14)简化为：</p>

$$\\small{\\begin{array}{l}\\left ( \\dfrac{\\pi}{k} \\right )^{2} +\\left [ k_{\\mathrm{F}}-\\left ( \\dfrac{\\pi}{k} \\right )^{2}+2 k_{\\mathrm{B}}\\right ] \\left ( 1-\\dfrac{\\pi/k}{\\tan(\\pi/k)} \\right ) +2 k_{\\mathrm{B}}\\left [ \\dfrac{\\pi/k}{\\sin(\\pi/k)}  -1\\right ]  \\\\+ k_{\\mathrm{F}}\\left [ k_{\\mathrm{F}}-\\left ( \\dfrac{\\pi}{k} \\right )^{2}\\right ]\\left [ \\dfrac{2\\tan(\\pi/2k)}{\\pi/k}-1\\right ]\\end{array}}\\tag{附 E-15}$$ 

.. raw:: html 

 <p style="text-align:justify;text-indent:2em;" > 解式(E-15)即可得到<i>k</i>值如下：</p>

$$\\small{k=0.5\\mathrm{exp}\\left[\\dfrac{0.35}{1+0.6k_{\\mathrm{B}}}+\\dfrac{0.7}{1+0.01k^{2}_{\\mathrm{F}}}++\\dfrac{0.35}{(1+0.75k_{\\mathrm{B}})(1+1.15k_{\\mathrm{F}})}\\right]}\\tag{附 E-16}$$ 

.. raw:: html 

 <p style="text-align:justify;text-indent:2em;" > 对于一端固定、一端仅有水平弹性约束的构件，取<math xmlns="http://www.w3.org/1998/Math/MathML" ><msub><mi>k</mi><mrow><mrow><mi mathvariant="normal">B</mi></mrow></mrow></msub><mo>=</mo><mn>0</mn></math>，代入式(E-15)得</p>

$$ \\tan\\left ( \\dfrac{\\pi}{k} \\right ) =\\dfrac{\\pi}{k}-\\dfrac{1}{k_{\\mathrm{F} }}\\left ( \\dfrac{\\pi}{k} \\right )\\tag{附 E-17}$$ 

.. raw:: html 

 <p style="text-align:justify;text-indent:2em;" > 直接对式(E-17)进行数值计算，得到：</p>

$$k=2-\\dfrac{1.3k_{\\mathrm{F} }^{1.5}}{9.5+k_{\\mathrm{F} }^{1.5}}\\tag{附 E-18}$$ 




:math:`\ `	 
