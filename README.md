The Open Study Room presents: 'An introductory guide to Joseki'

This repository contains the workings of the Joseki guide from the Open Study Room.

Find out more about the Open Study Room on: https://openstudyroom.org/

You can also join our Discord server here: https://discordapp.com/invite/b7meDjX

Installation and working instructions (Windows 10, 64bit)

1. Download and install MikTex 2.9 (https://miktex.org/download): This is the LaTeX distribution
	- Open the MikTex console and install the following packages:
		> todonotes
		> caption
		> igo
		> wrapfig
		> titlesec
		> xcolor
		> pgf
		> ms
		> cjk
		> arabi
		> url
		> eijkhout
		> zhmetrics

	- Open the file browser and find the 'repeat.tex' (e.g. C:\Program Files\MiKTeX 2.9\tex\generic\eijkhout)
			and change all instances of the command 'repeat' to capitals (e.g. to 'REPEAT').
	- Change the name of 'repeat.tex' above to 'REPEAT.tex'.
	- Open the file browser and find the 'igo.sty' (e.g. C:\Program Files\MiKTeX 2.9\tex\latex\igo\igo.sty)
			and change all isntances of the command 'repeat' to capitals (e.g. to 'REPEAT').
			Also change the '\input{repeat.tex}' to '\input{REPEAT.tex}'
2. Download and install TexMaker 5.0 (https://www.xm1math.net/texmaker/download.html): This is the LaTeX Editor
3. Open the main 'OSR_Joseki_Guide.tex' with TexMaker
	- Go to 'Options > Configure TexMaker > Quick Build' and select the Quick Build Command #3: 'LaTeX + dvips + ps2pdf + View PDF' and click 'OK'
	- On the main screen, click on 'Tools > Quick Build (F1)'
	- The first time you run this command, it will take some time as the fonts are being compiled.
	  But if you have followed the above instructions, you should hopefully not get any errors.
	- Once it has compiled, you will need to do 'Quick Build' again.
	  This will always be the case, as in-document references don't update unless you compile twice.
