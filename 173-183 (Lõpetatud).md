#flashcards/173-183

173 Faraday esimese katse kirjeldus. Joonis selgitustega.
?
Katse aparatuur koosneb mähisega ühendatud galvanomeetrist (Teeb kindlaks elektrivoolu olemasolu) ja püsimagnetist. Kui püsimagnet ja mägis olid teineteise suhtes paigal, siis galvanomeeter voolu ei näidanud. Magneti liigutamisel mägise suhtes näitas galvanomeeter elektrivoolu olemasolu.

![[Pasted image 20250608200955.png]]
;

174 Faraday teise katse kirjeldus. Joonis selgitustega.
?
Katse aparatuur koosneb kahest omavahel elektriliselt mitteühendatud mähisest, mis parema magnetilise ühenduse saamiseks võivad olla mähitus ümber ühise raudsüdamiku. 

Esimene mähis on ühendatud alalispinge allikaga
Teine mähis on ühendatud galvanomeetriga

Galvanomeeter näitab voolu olemasolu teises mähises, kui esimeses mähises vool sisse või välja lülitada aka kui voolutugevus esimeses mähises muutub

Kui esimeses mähises on alalisvool, siis galvanomeeter teises mähises voolu olemasolu ei näita.
;

175.1 Elektromagnetilise induktsiooni mõiste.
?
*Elektromagnetiliseks induktsiooniks* nimetatakse elektromotoorjõu tekkimist suletud juhtivas kontuuris, kui muutub mähist läbiv magnetvoog. Eletromotoorjõu mõjul kontuuris tekkivad voolu nimetatakse *induktsioonivooluks*
;

175.2  Lenzi reegel.
?
*Lenzi reegel* - Suletud juhtivas kontuuris muutuva magnetvälja poolt tekitatud induktsioonivool on alati suunatud selliselt, et induktsioonivoolu magnetväli püüab takistada induktsioonivoolu tekitanud magnetvälja muutust.

**TLDR** Induktsioonivoolu on suunatud nii, et selle magnetväli püüab takistada magnetvälja muutust mis selle tekitas.
;

176 Generaatori tööpõhimõte.
?
*Generaator* - Seade mehaanilise energia muundamiseks elektrienergiaks.

![[Pasted image 20250608201958.png]]
;

177.1 Transformaatori ehitus ja tööpõhimõte. Joonis selgitustega. 
?
*Transformaator* - Seade vahelduvpinge muundamiseks.
Koosneb kahest mähisest (Primar ja sekundaar), millel on ühine südamik. Primaarmähise klemmidele antakse vahelduvpinge, mille tulemusel läbib primaarmähist vahelduvvool. 

Primaarvool tekitab trafo südamikus muutuva magnetvoo, see omakord indutseerib sekundaarmähises sekundaarpinge.

![[Pasted image 20250608202043.png]]
;

177.2 Trafo Ülekandetegur.
?
*Trafo ülekandeteguriks* nimetatakse suhet
$$n = \frac{N_2}{N_1}=\frac{U_2}{U_1}$$
N on mähise keerdude arv.
kui n > 1 on tegemist *pingekõrgendustrafoga*
kui n < 1 on tegemist *pingemadaldustrafoga*
;

177.3 Trafo energiakaod
?
1. *Vasekaod*, põhjus on juhtmete soojenemine
2. *Rauaskaod*, põhjus on südamiku pidev ümbermagneetimine. 
;

178 Induktsiooni elektromotoorjõu valemi tuletamine.
?
*Suletud juhtivas kontuuris indutseeritud elektromotoorjõud võrdub kontuuri
läbiva magnetvoo muutumiskiiruse vastandväärtusega*
Lõpptulemus aka Induktsiooni elektromotoorjõu valem
$$\varepsilon = - \frac{d\Phi_B(S)}{dt}$$

Sammud:
$$\begin{align} A &= qvBl \\
A &= q\varepsilon \\
\varepsilon &= vBL \\
\varepsilon &= Bl\frac{ds}{dt} = \frac{d(Bls)}{dt} \\
S &= ls \\
BS &= \Phi_B(S) \\
\varepsilon &= \frac{d\Phi_B(S)}{dt}
\end{align}$$

Lisaks tuleb arvesse võtta arvesse, et pöörlev liikumine on suunatud vastupidi indutseeritud elektromotoorjõu suunaga ja valem tuleks teha negatiivseks

Saame
$$\varepsilon = - \frac{d\Phi_B(S)}{dt}$$
;

179 Mähise omamagnetväli, joonis selgitustega. Omamagnetvoo definitsioon ja valem. Induktiivsus.
?
*omamagnetväli* - Mähist läbiva voolu poolt tekitatud magnetväli
*omamagnetvoog*  $\Psi$ - Mähist läbiva voolu poolt tekitatav summaarne magnetvoog
$\Psi_B = LI$ 

L'iga on tähistatud mähist iseloomustav positiivne konstant mida nimetatakse mähise *induktiivsuseks*. Ühik on 1 H (Henri)

![[Pasted image 20250608204252.png]]

;

180 Eneseinduktsiooni elektromotoorjõu valemi tuletamine.
?
$$\begin{align} 
\frac{d\Psi_B}{dt} &= L\frac{dI}{dt} \\
teame: \\
\varepsilon &= - \frac{d\Phi_B(S)}{dt} \\
järelikut: \\
\varepsilon_I = -L\frac{dI}{dt'}
\end{align}$$

See viimane ongi *Eneseinduktsiooni elektromotoorjõud*
;

181 Voolutugevuse sõltuvus ajast mähise sisselülitamisel. Valemi tuletamine. Graafik.
?
Kirchoff $\varepsilon + \varepsilon_I = I(R +r)$
Eneseinduktsiooni elektromotoorjõud $\varepsilon_I = -L\frac{dI}{dt'}$
Tuletame: $\varepsilon -L\frac{dI}{dt'} = I(R +r)$

Edasi:
![[Pasted image 20250608221952.png]]

**VASTUS**
![[Pasted image 20250608222021.png]]

**Graafik**
Voolutugevus läheneb väärtusele $$\frac{\varepsilon} {(R + r)}$$

![[Pasted image 20250608222100.png]]
;

182 Voolutugevuse sõltuvus ajast mähise väljalülitamisel. Valemi tuletamine. Graafik.
?
![[Pasted image 20250608222120.png]]

**GRAAFIK**
Voolutugevus läheneb eksponentsiaalselt nullile

![[Pasted image 20250608222155.png]]
;

183 Vooluga mähise magnetvälja energia arvutusvalemi tuletamine
?

$$\begin{align}
dA &= \varepsilon_Idq = \varepsilon idt \\
dA &= -L\frac{di}{dt}i dt = -Lidi \\
A &= -L \int_I^0idi \\
A &= \frac{LI^2}{2} \\
W_B &= \frac{LI^2}{2}
\end{align}$$

;