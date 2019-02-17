# Chess Engine RapSimple
>Javascript UCI chess engines.
* Rapchess - optimized for strength
* Rapsimple - optimized for simplicity
* Rapshort - optimized for size

Try it out here <a href="https://thibor.github.io/Chess-Engine-RapSimple/">demo</a>.

To use this engine please download program Jsuci (https://sourceforge.net/projects/jsuci/).

## Setup GUI Arena

You need download program Arena (http://www.playwitharena.com/?Download).

In Comand Line please write path to jsuci.exe (<b>C:\Games\Chess\Arena\Engines\jsuci\jsuci.exe</b>).

In Comand Line Parameters please write path to <b>rapsimple.js</b>.
 
 ## Setup GUI Winboard
 
 You need download program Winboard (http://www.open-aurec.com/wbforum/viewtopic.php?t=51528).
 
Inside Winboard directory please create directory <b>Jsuci</b> with file rapsimple.js and jsuci.exe, and you should click in menu <b>Engine / Edit Engine List</b> and add line:
 
<b>"Rapsimple" -fd "..\Jsuci" -fcp "jsuci.exe rapsimple.js" /fUCI</b>
