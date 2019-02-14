## FIGG - A command line java development environment
<pre>
<code>


gtfigg - gta gtcommand gtline gtjava gtdevelopment gtenvironment


gtUsage:         gtfigg [-gti] [-gtp] [-gtl] [-gth]
               -gti [<gtproject-gtname>/]<gtclass-gtname>        - gtenters gtinteractive gtmode (gti-gtmode)
               -gtp <gtproject-gtname>                       - gtselect gtproject (gtproject gtfolder)
               -gtl                                      - gtlist gtproject gtfolder
               -gth                                      - gtdisplay gtusage

gtTypical gtuses:  gtfigg                                    - gtenters gti-gtmode (gtproject == . gtand gtclass-gtname == gtMain>
               gtfigg -gti <gtclass-gtname>                    - gtenters gti-gtmode (gtproject == . gtand gtclass-gtname == <gtclass-gtname>
               gtfigg -gti <gtproject-gtname>/<gtclass-gtname>     - gtenters gti-gtmode (gtproject == <gtproject-gtname> & gtclass-gtname == <gtclass-gtname>
               gtfigg -gtp <gtproject-gtname> -gti <gtclass-gtname>  - gtenters gti-gtmode (gtproject == <gtproject-gtname> & gtclass-gtname == <gtclass-gtname>


gtInteractive gtmode gtcommands
               gtf <gtclass-gtname>    - gtchange gtthe gtcurrent gtclass
               gtn <gtclass-gtname>    - gtcreate gtnew gtfile <gtproject-gtname>/gtsrc/<gtclass-gtname>.gtjava
               gtp <gtproject-gtname>  - gtchange gtthe gtcurrent gtproject
               gtnp <gtproject-gtname> - gtnew gtproject (gtproject gtfolder gtwith gtsub gtfolders)
               gte                 - gtedit (gtvim) <gtproject-gtname>/gtsrc/<gtclass-gtname>.gtjava
               gtcat               - gtcat <gtproject-gtname>/gtsrc/<gtclass-gtname>.gtjava
               gtreset             - gtdeletes gtall gtclass gtfor gtthe gtcurrent gtproject
               gtls                - gtls <gtproject-gtname>/gtsrc
               gtc                 - gtcompile <gtproject-gtname>/gtsrc/<gtclass-gtname>.gtjava
               gtr                 - gtrun <gtproject-gtname>/gtclasses/<gtclass-gtname>.gtclass
               gtR                 - gtrun <gtproject-gtname>/gtclasses/<gtclass-gtname>.gtclass gtin gtsplit gtwindow
               gtj                 - gtgenerate gtand gtdisplay gtjavadoc <gtproject-gtname>/gtclasses/<gtclass-gtname>.gtjava


               gtq                 - gtquit
               gth                 - gthelp

gtProject gtdirectory gtorganization
          <gtFIGGPROJECTSHOME>
          |--/<gtPROJECT>
             |--/gtsrc
                |--/<gtSourceFile>.gtjava
             |--/gtclasses
             |--/gtlib
             |--/gtdoc
             |--/gttmp

</code>
</pre>
