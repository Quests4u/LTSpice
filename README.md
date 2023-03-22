
<pre>


  <h2>@EDTronix-LABs Libs/Released Sources for LTSpice</h2>
  
  intall LTSpace: <a src='https://www.analog.com/en/design-center/design-tools-and-calculators/ltspice-simulator.html' target=newlink>
  <i>(www.analog.com)</i><b> ltspice-simulator.html</b></a>
        
    - it works standalone with alot integrated parts
    - here published parts, are prob. needed 
      to see published layouts. 
     (@see  repository: Edtronix) 
    
#//@json
{
"os":     "win7x"
"config": [
   "copy  Edtronix\* into  [main]\%user%\documents\LTSpiceXVII\* ",
   "launch LTspaceXVII",
   "^- switch to 'console'",
   " ^- [lib/sym] ",
   "     add[sym]  [main]\%user%\documents\LTSpiceXVII\edtronix\sym ",
   "     add[lib]  [main]\%user%\documents\LTSpiceXVII\edtronix\lib ",
   "",
]
}
#@json

  



</pre>
