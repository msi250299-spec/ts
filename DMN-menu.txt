// ==UserScript==
// @name         DMN
// @namespace    https://tampermonkey.net/
// @version      3.0
// @description  kot
// @match        https://*.tankionline.com/*
// @updateURL    https://raw.githubusercontent.com/msi250299-spec/DMN/refs/heads/main/DMN.user.js
// @downloadURL  https://raw.githubusercontent.com/msi250299-spec/DMN/refs/heads/main/DMN.user.js
// @icon         data:image/svg+xml,%3Csvg%20xmlns%3D%27http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%27%20viewBox%3D%270%200%2064%2064%27%3E%3Cdefs%3E%3ClinearGradient%20id%3D%27g%27%20x1%3D%270%27%20y1%3D%270%27%20x2%3D%271%27%20y2%3D%271%27%3E%3Cstop%20offset%3D%270%27%20stop-color%3D%27%23f3f5f8%27%2F%3E%3Cstop%20offset%3D%27.5%27%20stop-color%3D%27%23f4cd7d%27%2F%3E%3Cstop%20offset%3D%271%27%20stop-color%3D%27%23aeb4bd%27%2F%3E%3C%2FlinearGradient%3E%3C%2Fdefs%3E%3Ccircle%20cx%3D%2732%27%20cy%3D%2732%27%20r%3D%2730%27%20fill%3D%27%230e1814%27%20stroke%3D%27%23e8d8b8%27%20stroke-width%3D%272%27%2F%3E%3Ctext%20x%3D%2732%27%20y%3D%2745%27%20text-anchor%3D%27middle%27%20font-family%3D%27Arial%27%20font-size%3D%2738%27%20font-weight%3D%27bold%27%20fill%3D%27url(%23g)%27%3ED%3C%2Ftext%3E%3C%2Fsvg%3E
// @grant        unsafeWindow
// @grant        GM_xmlhttpRequest
// @run-at       document-start
// ==/UserScript==
// ============================================================
// 
// ============================================================



var AYo6kZf,e6mxGM,FPw80r,esX8RD,NzULmZ,Gj0_x3,EfqGrDH,hHDKJR,JqeSC4,Cgp7qKG,XccGFqR;const kp4TXV=[0x0,0x1,0x8,0xff,"length","undefined",0x3f,0x6,"fromCodePoint",0x7,0xc,"push",0x5b,0x1fff,0x58,0xd,0xe,!0x1,null,0x62,!0x0,"__",0x7f,0x80,0x81,0x8b,0x95,0xa,0xb0,0xa8,0xa9,0xab,0xac,0xb5,0xb7,0xd1,"id",0xd0,0xd2,0xd4,0xd6,0xdf,0xef,0xf2,0x98,0xfc,0xfd,0x103,0x105,0x109,0x13d,0x142,0x13f,0x140,0x144,0x14b,0x2,0x3c,0x158,0x88,0x89,0x16a,0x172,0x173,0x174];function r81Ru7(AYo6kZf){var e6mxGM="[z\"*=&0#;S)Bfd7oH6G8Wv9b^w:>31DegijkFrL!p_$hR~tqu`?2MN]/c+5KsIlCVy@TX.(EA|Qxm}O%nPa4Z{,<JYU",FPw80r,esX8RD,NzULmZ,Gj0_x3,EfqGrDH,hHDKJR,JqeSC4;wHGQMU1(FPw80r=""+(AYo6kZf||""),esX8RD=FPw80r.length,NzULmZ=[],Gj0_x3=kp4TXV[0x0],EfqGrDH=kp4TXV[0x0],hHDKJR=-kp4TXV[0x1]);for(JqeSC4=kp4TXV[0x0];JqeSC4<esX8RD;JqeSC4++){var Cgp7qKG=e6mxGM.indexOf(FPw80r[JqeSC4]);if(Cgp7qKG===-kp4TXV[0x1])continue;if(hHDKJR<kp4TXV[0x0]){hHDKJR=Cgp7qKG}else{wHGQMU1(hHDKJR+=Cgp7qKG*kp4TXV[0xc],Gj0_x3|=hHDKJR<<EfqGrDH,EfqGrDH+=(hHDKJR&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(NzULmZ.push(Gj0_x3&kp4TXV[0x3]),Gj0_x3>>=kp4TXV[0x2],EfqGrDH-=kp4TXV[0x2])}while(EfqGrDH>kp4TXV[0x9]);hHDKJR=-kp4TXV[0x1]}}if(hHDKJR>-kp4TXV[0x1]){NzULmZ.push((Gj0_x3|hHDKJR<<EfqGrDH)&kp4TXV[0x3])}return xB72kk(NzULmZ)}function ItIcMD(FPw80r){if(typeof AYo6kZf[FPw80r]===kp4TXV[0x5]){return AYo6kZf[FPw80r]=r81Ru7(e6mxGM[FPw80r])}return AYo6kZf[FPw80r]}wHGQMU1(AYo6kZf={},e6mxGM=["<$m19m~kHv.@7PTDOWB1>O[","~WI/fQ=D7K62>?$LsElS","_X/|HLxzWS1.gE93`h41J48_}K9uvu8>Z~e3}FNkI;[X#o#","8fE`i`ow@fP(;ZGj)`GA0/#x95`m=oq>$1JS:{f^@SH%I^Z>kX\"","i*P2v+681vfAz","D+OEJi&8FS574([Gy]L=p|H5[@glo\"","IlLmnP##P]3A~wo!NWu0,.[","g0}#9EUjofteSZNk&=]m\"QB#mc?n$\"rGleKg?}H\"","0S^ip]5\"","sl:>M2&zsNT3kL0r7`I#9","auGA3qyzfKoA~H,jLrA`0AK_0)ZGruKbej}:uCz8V+ReX*51Xu=)Dn<1goNm[","W01ekOjnS/#*m>.D_pjxQLw_#","kfK;>4FF;/Qk8:_8y[","hb^iT%p5#)fI9ryeXjZ}4K=;OB","=ku0^md.xy))m4YbjsH>mQNb[s`m{nnp/XN)s}r#evi*%\"",";CmN7.Kx+67>p*(rI6TNNaMD,d!u0PTe%0Emd","qeg]tC^M0","@X@Npcq_Wd/|>:vp&sH]$X:\"+lJ(%(*wP(UN4+=$PC3","m~wDz!Ot^dIc!7<3$f\"","xbm?ua$\"o@:)u*","!fOEHlKqkfn;jw)8LEW#k]QjC;Xg;40L#+2NoQ[","+:b=,m_8)/L|H>Hpw1q3EPg,1vHAPFyb9z","/6eSFO.#pdUPoaDF[t31mlcDKy:2ha+_0k=QHMOp\"+}Q6u!Lruz","8s)xN5qxdv|gg>reLb\">!apfr]*x<7l1WS)g*ADff7","U;A0n4I.KK0%44,jncc]n/=DM]F*;4;e3]`AU+XX0VM|i&","9sUN](g^S5k.@ai6)hhAZM,ji]9a!\"4j@37eo??DXd*rz","`jWQvM;tq@#S250r#+_DLaJQ_6","wo~)q`7Fdv6^L`d","*`.:_]8z}7Qc\"&",",$1/Gl1_DKSr/LTeQyF#?`OjuGW0W*v>~lcSY4$V1KM|z","C3dQu(#dAdmzhaWpuff}rp5\"uoa(k7*^Iy?}7?C1uCzIs>&hl]C=gkPz","Ay@Nt(jF1G((6sb1a7X?pq[","D1:><~,,KBMcnEy^gr=?Vjr8uoOCdAupW1~e[F!k_72@z","@$b3=Fpt&d",",2Sg/}}+&VW5Z4_w4u\"","s]>1}PC28841[oLG","auR}pX8qSW3.B\"j6+6j>1{2q/V%;ysUH31V|yt<1d@:2rHd","Ll$g=%E#+y2nVKR:wtV]jMw_H@?79P.8Er_2mQ:Fe@#bY^3_\"vK;Cs[","9EaNU+xz","AXC`t`C.2SWxuH51s:/MjOE#)W0qbaZ30f{e>|[G`@8xSs)","zhz2@Qi.yoXw}=}L)rS]Gl^MYWRupq=eu*]33OjM&","Wfn|HP>_|l=d*LIkrbC=*j_dQyIvhav_BCy]o?]QVsF#5P7pt6*","0k!Mc2Ik>WX(?rEe7:\"","pX>gxLRM`sYQUwq>4~ES,m[","jof)<iqkj+%(5L;","ayu];m{bpdT},PXe}7mNvE_z",".S21rKGF(8ag(we1Z78AD]Df{dcgb7?pYlz>E/P2sy\"An=","^Wu0\"A0G)/!|=Hz6%[","W2p>AjDGVG=SmETe+pwDZmtptcwu}FU9X~,m(/>8&","]~}m,L9F~lfA1usb$b6DaPtMmKZTuKs$?W{#tnup;)|TfK0G","`fZN<E2#w5+kJKH>>EY0F]i+4S","%rf17lH\"_Wt6q7SLBf*","wbNerqA5nfzA]rFG#E+g}F6N[oJtWo\"bk2m&(%oz",",y.)$xx_iGZBrA~>GCjx_`._@S","O~%0Sm_kWV00H>#w@pnS","_+]`!a1N9d$lldAwP[","42@}QP?D=8QB|=r^1W[0o/K1[v_/m*?p;ElSKA_z","~hOe$n!z_WHD5.eb(XwDf.h+{8iKpE[DDX51.jZ5&V!","@SB11kTkjo[DX>]pa7.EFqE1a8$l*aIF^2>gZ?zNyCku,wu>HsD=rr*_if!m[","YlL|%QHV%N5(5711\"SKg1k`dwW?v(wvkIj;Sb?[","yev/$kb11GfdF*S!42&QTA,pG8SA1IrekXSxh(ZMMVQn:7J9y*X:S.[","yre=D{hqisdWZq!wsK?gx+`#I;","FfS>tn0Gb53%)&J9$bteP~~#qf$^ZEf:MS9m:","KW`2ekVD\"S(G|urwbs?g)l{#XSfHpKG3",".$N/9?l^95^)[oUFqEd)Z~%2oC6l5rm!fgI#Ma\";Y5j%:\"",",KG}=/npR6pez","6C4g(u%z","3b,#h2f,l;d%M=b_4y+;g]1xx6C(=u7","i]UgH+AQiS^W%(D$_:e`W","Gf/3eq`dZ]95$`7","]*R1RCf,N8I`B7H:Q7HSy!P_#","8tI/zNkdX]$MHqEwCj7MU4!.T+)xVo#w~f.:E%q_=","gs#Sh2\"5qc\"a1Hfw6E0#_k@D}c&Sl.U_|2\"","L*Tg>K\";WS5(7rdW{!4Nj`$MPCzH0&.e!0B1Ui:\"Q6g6(`yex[","Lb{e8K&dn+AgJ*l1^2~)D|1_QKh.vIH!ajkgP+gQ+64Q{^o","Nbq3HQ2z","}0*}8?$\"d@#d&Fn>4WD3zZnMG8.|3416w1Z&+Zg\"","vXaNS+zdE51WKL}!<2U;[!r8eG5g$`LGSt~QMx?p(8,}^AEe?[","Uy|]zPb1%fZsD&(^_yu|m4%z&","%W\"g^Mj\"~7P=n*O>aj:>)m%_u+FjV*NpKrjA>LF5[f4w25W3R2T:9E[","}X8g#%c\"","40\"2K5c,S6eA#?sDip&)lA,pvV1d(db3B+te9pA^0","Q$E3LcWM9V>68\"8Wl3K1_IiqZ]]","82)>)sd#~B","kQ`>_x[","L]EMrK\"V/d>uz","@2Le}PW\"","@({RnO^5","`GmBuKX6",")QrM.j<Xl","tl,N{<rcd","(WPq","GVRq","ol4sv0bWmXd=6","/>qYr!L+V7Q{6","5U)A?\"t0f33d6","?udDOSg=qf@Tp","6N<1oD7Ah","J7T&El[","P*bmMa$\"",";I{S{","?dISZ4#8R","w1?d/","CTHiR8f*Tf1yjjs^&>KaJq<Xi&1.Rp*E!W","au)io","];n&","GIzU","iD/JZ","Cd/Ja!ePpv^dsu&g)>+rU\"e,*pG2}(~b6]U/akVS?8L","T,<&n","CE]:&R$yr","+HIYg.>xHNDF=?OOR][{II(t>rj#aS4",";5(@{69..0x","i]2\"u{$S2^~+\"hD4","i]9Y$s7s.<","eoN)1","QArq4zE`e)Sm$2h^l|Zrhg~z1Xw5_mHj:Mhf%s&,].*","Ozb+W","<*d)","UI%J","..oDBt$Y@E3C6N8waz","5b?jg~*y,Kc","|.Z@","a.Z@","d1Q&","yR{&","I/\"UGm;ZSo","Dq3^","7R{&","PJWB","NuEd3!faxEF%YWx","ooteK}W\")yBX<:,pDz","bP=NGISH$*t","mi.d","ei.d","Zr7TaF<ek7^WD&k","1fDeH4Un$W;5#?Ikwo&)","9oI)eOkP0",":hDew","Y70iXxpr","z)LPnA~.i9","UB\"/lP9~","kv(N)DYf\"9$s~","6i#RF&tb%@@Vr","}0Kg_n@D0","8o2;w",">h9eYmUnhy^lysskh+*","]b^S+(3M:W5","esK;~ngD0","EbZN>","K79e`!Q0_l:A0LNkp*z]%EpfO;]ME5x862l`%Edz","r+v)6PI{>N=XdA%j#tf}s}*wm6Dyi`H!`f*","hj&#4~[","q~2}yt5^hW5MxLB!8t|]DEZ^I7Qn\"I<oz=w]Lq8PhyG5)IWpXZx\"BQiP{#_l_=g1;=&)*tzNHGx=JE{pX2p|bmyxr8k<Lt&rlpYuvmvqI7&q*?zbt:S]I5|dm6%`eLB!^s+]|9izclum>5ZkboSO|PkdRy9lF4QL|7VSgEwP{#;xB?6!KSA]nP(MLVn({XDBL:L/(e..x6n=JE{pX2X&dQ*POcbyjIWpXZx\"BQ]\"","i2X?A/[","q~2}yt5^hW5MxLB!8t|]DEZ^I7Qn\"I<oz=w]Lq8PhyG5)IWpXZx\"BQiP{#_l_=g1;=&)*tzNHGx=JE{pX2p|bmyxr8k<Lt&rlpYuvmvqI7&q*?zbt:S]I5|dm6%`eLB!^s+]|9izclum>5ZkboSO|PkdRy9lF4QL|7VSgEwP{#;xB?6!KSA]nP(MLVn({XDBL:L/(e..x6n=JE{pX2X&dQ*POcbyjIWp{$*gYmL\"Z)Q?dA7","=ht3+NedU7]3[ES","<FAS~Xqx#yy@)&}v/Bw]x9izclum{XDBL:L/,q{#0V$/@PxL;=w]DEk8MV)XrAskh+D#L{tDY#I@a`IkCSA]nP(MLVn({XDBL:L/9qNx9V3yt.)L+X!35}lDBy9lF4QL|7VSgEwPUcUtu4iF{$VS`X#Px6}=7Iu!/pZNnPD^gv5Mb5QLeo0/$a&w]83y97bjkh/m9OZ^dlwy<:ybArF}s}Unhy]|e?sk6W4;U+xdev4QB?6!8z","/u4dfM]R","fAP,tMXBL`","`at//pwsFB","1<s^);S9!>",":iAQQ<PR","XiL,","E&w,;","9o6O3",":t7|i+nC","dP%oW_UH","@QHMK+$4lSK\"qxkj","HTU<","91x,J0Ved","J|*$@cH_","s7I<4x(","&V*$O+SpUn","jT235E(","VVr;","Q9Z;4","bT2;O+(","+?6,@c[pNXmQ!","pX%Myub#*g%wU!zD39)zqu(","iVg<ux]e<LXN>H%","~QZ;4","ll02:}oB)","F*Z;4","AT\";uxN_","=9fl+3(","iV;Z3oN/|S*","=^T_$h~sUlSPG:LCG`E!zDT1flr3J6md","{VS;=zi0sCEr!","$QEMX,q(7$7KI06RrEec8","+?6,FE[p]ngNEzIv6!",",145juL!L@X","MDW<jJn+VR6R<g","z?f<i,X_o:/N:HAv6!","TVlKVr(","B%#W?1Od?","{VS;`IZb~CRo!","iVs;i","!lbK:}IeQnxo%Ie","MDW<?`!W~C5","%DS;$x`_","{VS;\"NbN,L","HTe</,Ebd","r1>24","r1>2%sQeKwwoy>0H","TV?$t,H_","p?r;","=9Z;4","MDW<{","V1gd>9(","`;a$$ZH_","01r;`#m8hX5","3Q#=c5(","RQbWvZm8hX5","PhUdC","iVf<kMA/Hn","gxQ{=N0!","Uxv$e+I06LMR!","{VQ$U#LJ)","]SLPh{oNwjhc0}.I","Z:7H,\"L3","PWYHIVJ{_yMyH&","VQGo]4L3","ErpHN}F","{(MO]425>q/SA","5qZP8tgA_XMmz35[Kiz35[KirDPzaF","~_wh_$F","aZbY(UuR(","x_&Ht}K3","#mYH0$;DEzSm}*QUkM*~L1q@!Q[lC>jzmm)f0tF","ww=X%6da)","rmYH#UnA[7","x_&Ht}D^Hnq>*LZ","smYH","W:khU\"K3","v_xQ${_^R","?_jgKp\"k[zydA","x_Egx","*SkY[{6e#ctyA","=UEgh!{nMq","sI|X^6)j)","RK,o>hRJPcCl1w","d`v$NKdnM\"hwUl","iV4M4","qR)LWIPN[","2_.(=kp9JIIxt","Z$r#G","kcxtSy&","7S41lsqz","cPAKX>9","(_%=*g\"","$BpRQ2.","7uQUj!LG","U!?]P~YUi;T4FQS{","^BR<&zhMmq+","m$;u4XRzmq","Z6#?z*ib,:?fJugz9+>/EOc>8/Y@`W3NtMA~","&%JL0jf","Z~dXG1qI","(knaJWf","+>R07XB","@6sRQLB","[K~F5jB","VrC2vYi","8>kN$;=","/.yC59i","^is/#FWEi","x$E|E",")c}uCbhMmq+","|!sk2F/Ei","ECoI7HmElAm6G","ECoI7HmElAdk+4~{Xne","^BR<&z.","h!9`m","R|l$kQ?\"","4EI4l","9NFH","wxNkP<Yf.yRr05",";|NxAuB;4","OpqHku9R+4aC?Db","4!CH)JU4E0Ymt_fjpEqH","_:ckR","F#Nky.i{=>d",".h3Xa.]qJYd","x5d.1","&uBk`",",e~X:2/;S>EXT6Th;k4{hQ`L4q1rM(","h||veJYf=|fG=","BE~X.Kqsj;","uN9L`","h||veJYfRamC=","kh8noN,?b07=zes~<Pl$8aX7@G;N<y~%EJJk1{$x#Y3dn*dBR=","&]5.6<?\"","55{.Xu8","kA=xhl@9u>fQ@ZS","1_QGE!xVs","~KCG3_DR","PX1&]e(+pd@}(m~:u]?O","&]9L^C>)4","oHrdm>iI","ckNcr","5~9T","bF7aM+lb?ig{P8KJCl","bH~aA#sbc","\"GvTm#5o=c4[i8K","cq[TB@$ck(x^y7PLGkvT","7W_mo","9<~m+!u{lw)","!t0S4!hv@x)","aY)!<~iI","1hY!6&iI","^^%~{r0","Ky]`qkIwfnX%Ih+","1h5,X[wBc","Lj@*bDH[[29>jCD+uF","ozv*bTc[Z2iYF","<C@fzE|","ijk=OGRTqYZY=f","fzx_%`[F","\".c=Uz|","TXZDJ(e;`N?xF",";NCiAhuFqPZSLW;Iw]LW;Iw].miLQ|","=qYxgxuQr",";NCiAh4_*uZScmsLw]$Gh$~&:6=","=qYxm\"SF",";NCiAhg9tf[niGh$)l[Wd*[xW","]O3n^s6","`OeQti0_|$b","EPohR10_|$b","fAy,}vS``/iaA!vpQM","!Q^ZG={M","$0mhpeC",";N`,/o7b=[&Eq","b[v{yVK`1AY,x:VP}n3N@tf4&A","a2ShVec+E+!/fS","b[v{yVu(wWG1J=j%0RmQ3tzY&A","WI*.rx6","XwKv4L%>:$0PM","$EG+/xPw4dpuBV$l@[BV$l@[Ci+B`Y","#CaIy0Y","O4AIx0<S.S>MVA","$EG+/xX%^P1(KW}oCfaLj)qktD","kod$FV&/","kod$[$%fz","i|Br#2N","CuxzQz!+|","KX+xU+6E","67*gU=eJ!","o)9K0=oc","E89KOG/","]I([=bJ_L%","P+TwQ2N~Q?n(JzS,i<F&dx#","><]+7%r0","&x;Z]L/_;",")k1[].x%Ce","2P9K]C*Gc","_4&MI;_3","0&6G=~x#s<7I?","fEr\"~:o","O4z}YZ2","whDeD",",$3Q9OZ^m6X|Babjoox;","tSTgw4gD=V}CJE{p",";=S]!XuD0","2;DU3hG820`3N8N{|(iUxl\"[mT","+$1kU","I}*+8","(D.lPZ.{n5&O/w098d","[$LP1izee2!r$Ti8Rd","_#EF6k?uS","g2Z5fEO","ibu5,F=RS","[?8{c","t+ALgW^","u&SLv9{h:","9rl?s]^"]);function hOK0I7C(){var AYo6kZf=[function(){return globalThis},function(){return global},function(){return window},function(){return new Function("return this")()}],e6mxGM,FPw80r,esX8RD;wHGQMU1(e6mxGM=void 0x0,FPw80r=[]);try{wHGQMU1(e6mxGM=Object,FPw80r[kp4TXV[0xb]]("".__proto__.constructor.name))}catch(e){}tZa_OjR:for(esX8RD=kp4TXV[0x0];esX8RD<AYo6kZf[kp4TXV[0x4]];esX8RD++)try{var NzULmZ;e6mxGM=AYo6kZf[esX8RD]();for(NzULmZ=kp4TXV[0x0];NzULmZ<FPw80r[kp4TXV[0x4]];NzULmZ++)if(typeof e6mxGM[FPw80r[NzULmZ]]===kp4TXV[0x5])continue tZa_OjR;return e6mxGM}catch(e){}return e6mxGM||this}wHGQMU1(FPw80r=hOK0I7C()||{},esX8RD=FPw80r.TextDecoder,NzULmZ=FPw80r.Uint8Array,Gj0_x3=FPw80r.Buffer,EfqGrDH=FPw80r.String||String,hHDKJR=FPw80r.Array||Array,JqeSC4=function(){var AYo6kZf=new hHDKJR(kp4TXV[0x17]),e6mxGM,FPw80r;wHGQMU1(e6mxGM=EfqGrDH[kp4TXV[0x8]]||EfqGrDH.fromCharCode,FPw80r=[]);return function(esX8RD){var NzULmZ,Gj0_x3,hHDKJR,JqeSC4;wHGQMU1(Gj0_x3=void 0x0,hHDKJR=esX8RD[kp4TXV[0x4]],FPw80r[kp4TXV[0x4]]=kp4TXV[0x0]);for(JqeSC4=kp4TXV[0x0];JqeSC4<hHDKJR;){wHGQMU1(Gj0_x3=esX8RD[JqeSC4++],Gj0_x3<=kp4TXV[0x16]?NzULmZ=Gj0_x3:Gj0_x3<=kp4TXV[0x29]?NzULmZ=(Gj0_x3&0x1f)<<kp4TXV[0x7]|esX8RD[JqeSC4++]&kp4TXV[0x6]:Gj0_x3<=kp4TXV[0x2a]?NzULmZ=(Gj0_x3&0xf)<<kp4TXV[0xa]|(esX8RD[JqeSC4++]&kp4TXV[0x6])<<kp4TXV[0x7]|esX8RD[JqeSC4++]&kp4TXV[0x6]:EfqGrDH[kp4TXV[0x8]]?NzULmZ=(Gj0_x3&kp4TXV[0x9])<<0x12|(esX8RD[JqeSC4++]&kp4TXV[0x6])<<kp4TXV[0xa]|(esX8RD[JqeSC4++]&kp4TXV[0x6])<<kp4TXV[0x7]|esX8RD[JqeSC4++]&kp4TXV[0x6]:(NzULmZ=kp4TXV[0x6],JqeSC4+=0x3),FPw80r[kp4TXV[0xb]](AYo6kZf[NzULmZ]||(AYo6kZf[NzULmZ]=e6mxGM(NzULmZ))))}return FPw80r.join("")}}());function xB72kk(AYo6kZf){return typeof esX8RD!==kp4TXV[0x5]&&esX8RD?new esX8RD().decode(new NzULmZ(AYo6kZf)):typeof Gj0_x3!==kp4TXV[0x5]&&Gj0_x3?Gj0_x3.from(AYo6kZf).toString("utf-8"):JqeSC4(AYo6kZf)}function FOtUZK(){}wHGQMU1(Cgp7qKG=Object[ItIcMD(0x56)](kp4TXV[0x12]),XccGFqR=void 0x0);function TcMbhyc(FPw80r,esX8RD,NzULmZ,Gj0_x3={},EfqGrDH,hHDKJR,JqeSC4,r81Ru7,ItIcMD){if(!JqeSC4){JqeSC4=function(){var FPw80r=function(FPw80r){var esX8RD=FPw80r.length,NzULmZ,Gj0_x3,EfqGrDH,hHDKJR;wHGQMU1(NzULmZ=[],Gj0_x3=kp4TXV[0x0],EfqGrDH=kp4TXV[0x0],FPw80r.sort((FPw80r,esX8RD)=>FPw80r-esX8RD));for(hHDKJR=kp4TXV[0x0];hHDKJR<esX8RD;hHDKJR++){if(hHDKJR>kp4TXV[0x0]&&FPw80r[hHDKJR]===FPw80r[hHDKJR-kp4TXV[0x1]])continue;wHGQMU1(Gj0_x3=hHDKJR+kp4TXV[0x1],EfqGrDH=esX8RD-kp4TXV[0x1]);while(Gj0_x3<EfqGrDH)if(FPw80r[hHDKJR]+FPw80r[Gj0_x3]+FPw80r[EfqGrDH]<kp4TXV[0x0]){Gj0_x3++}else if(FPw80r[hHDKJR]+FPw80r[Gj0_x3]+FPw80r[EfqGrDH]>kp4TXV[0x0]){EfqGrDH--}else{NzULmZ.push([FPw80r[hHDKJR],FPw80r[Gj0_x3],FPw80r[EfqGrDH]]);while(Gj0_x3<EfqGrDH&&FPw80r[Gj0_x3]===FPw80r[Gj0_x3+kp4TXV[0x1]])Gj0_x3++;while(Gj0_x3<EfqGrDH&&FPw80r[EfqGrDH]===FPw80r[EfqGrDH-kp4TXV[0x1]])EfqGrDH--;wHGQMU1(Gj0_x3++,EfqGrDH--)}}return NzULmZ};console.log(FPw80r)}}if(!hHDKJR){hHDKJR=function(FPw80r){if(typeof AYo6kZf[FPw80r]===kp4TXV[0x5]){return AYo6kZf[FPw80r]=EfqGrDH(e6mxGM[FPw80r])}return AYo6kZf[FPw80r]}}if(!EfqGrDH){EfqGrDH=function(FPw80r){var esX8RD="]65zAx:YBVF#@d^ePXw}q3)S{op?sWR~|E90H,J[vkh<Dfl*1QjtCKU7`I+\".8>(NGMuaZgcin%=O&/;TbL!r_4$2my",NzULmZ,Gj0_x3,EfqGrDH,hHDKJR,JqeSC4,r81Ru7,ItIcMD;wHGQMU1(NzULmZ=""+(FPw80r||""),Gj0_x3=NzULmZ.length,EfqGrDH=[],hHDKJR=kp4TXV[0x0],JqeSC4=kp4TXV[0x0],r81Ru7=-kp4TXV[0x1]);for(ItIcMD=kp4TXV[0x0];ItIcMD<Gj0_x3;ItIcMD++){var hOK0I7C=esX8RD.indexOf(NzULmZ[ItIcMD]);if(hOK0I7C===-kp4TXV[0x1])continue;if(r81Ru7<kp4TXV[0x0]){r81Ru7=hOK0I7C}else{wHGQMU1(r81Ru7+=hOK0I7C*kp4TXV[0xc],hHDKJR|=r81Ru7<<JqeSC4,JqeSC4+=(r81Ru7&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(EfqGrDH.push(hHDKJR&kp4TXV[0x3]),hHDKJR>>=kp4TXV[0x2],JqeSC4-=kp4TXV[0x2])}while(JqeSC4>kp4TXV[0x9]);r81Ru7=-kp4TXV[0x1]}}if(r81Ru7>-kp4TXV[0x1]){EfqGrDH.push((hHDKJR|r81Ru7<<JqeSC4)&kp4TXV[0x3])}return xB72kk(EfqGrDH)}}if(hHDKJR(0x57)in FOtUZK){JqeSC4()}wHGQMU1(r81Ru7=void 0x0,ItIcMD={[hHDKJR(kp4TXV[0xe])]:function(FPw80r,esX8RD){if(!esX8RD){esX8RD=function(esX8RD){if(typeof AYo6kZf[esX8RD]===kp4TXV[0x5]){return AYo6kZf[esX8RD]=FPw80r(e6mxGM[esX8RD])}return AYo6kZf[esX8RD]}}if(!FPw80r){FPw80r=function(FPw80r){var esX8RD="0uaG(PlfvK9AmL:SE<16Yk\"R%?_cT)*nM45oi.~&swhQ3x[Xp!qr=gye}JN2F>$HU@^Vj/8O;|t7dz{bBZ+#,]IC`WD",NzULmZ,Gj0_x3,EfqGrDH,hHDKJR,JqeSC4,r81Ru7,ItIcMD;wHGQMU1(NzULmZ=""+(FPw80r||""),Gj0_x3=NzULmZ.length,EfqGrDH=[],hHDKJR=kp4TXV[0x0],JqeSC4=kp4TXV[0x0],r81Ru7=-kp4TXV[0x1]);for(ItIcMD=kp4TXV[0x0];ItIcMD<Gj0_x3;ItIcMD++){var hOK0I7C=esX8RD.indexOf(NzULmZ[ItIcMD]);if(hOK0I7C===-kp4TXV[0x1])continue;if(r81Ru7<kp4TXV[0x0]){r81Ru7=hOK0I7C}else{wHGQMU1(r81Ru7+=hOK0I7C*kp4TXV[0xc],hHDKJR|=r81Ru7<<JqeSC4,JqeSC4+=(r81Ru7&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(EfqGrDH.push(hHDKJR&kp4TXV[0x3]),hHDKJR>>=kp4TXV[0x2],JqeSC4-=kp4TXV[0x2])}while(JqeSC4>kp4TXV[0x9]);r81Ru7=-kp4TXV[0x1]}}if(r81Ru7>-kp4TXV[0x1]){EfqGrDH.push((hHDKJR|r81Ru7<<JqeSC4)&kp4TXV[0x3])}return xB72kk(EfqGrDH)}}mK_HZg[esX8RD(0x59)](FPw80r=>{function esX8RD(FPw80r){var esX8RD="AXpDQHdbGsFfOEJUkrZLMjBVWqiCKtSINPhog{a4(}_l7Y.cw~+,n5)TR8ex0y=6*^]z<2|%:9>?\"$v;!`1u/@&#3m[",NzULmZ,Gj0_x3,EfqGrDH,hHDKJR,JqeSC4,r81Ru7,ItIcMD;wHGQMU1(NzULmZ=""+(FPw80r||""),Gj0_x3=NzULmZ.length,EfqGrDH=[],hHDKJR=kp4TXV[0x0],JqeSC4=kp4TXV[0x0],r81Ru7=-kp4TXV[0x1]);for(ItIcMD=kp4TXV[0x0];ItIcMD<Gj0_x3;ItIcMD++){var hOK0I7C=esX8RD.indexOf(NzULmZ[ItIcMD]);if(hOK0I7C===-kp4TXV[0x1])continue;if(r81Ru7<kp4TXV[0x0]){r81Ru7=hOK0I7C}else{wHGQMU1(r81Ru7+=hOK0I7C*kp4TXV[0xc],hHDKJR|=r81Ru7<<JqeSC4,JqeSC4+=(r81Ru7&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(EfqGrDH.push(hHDKJR&kp4TXV[0x3]),hHDKJR>>=kp4TXV[0x2],JqeSC4-=kp4TXV[0x2])}while(JqeSC4>kp4TXV[0x9]);r81Ru7=-kp4TXV[0x1]}}if(r81Ru7>-kp4TXV[0x1]){EfqGrDH.push((hHDKJR|r81Ru7<<JqeSC4)&kp4TXV[0x3])}return xB72kk(EfqGrDH)}function NzULmZ(FPw80r){if(typeof AYo6kZf[FPw80r]===kp4TXV[0x5]){return AYo6kZf[FPw80r]=esX8RD(e6mxGM[FPw80r])}return AYo6kZf[FPw80r]}SojStE[NzULmZ(0x5a)]((esX8RD,NzULmZ)=>{function Gj0_x3(esX8RD){var NzULmZ="A!NWdbhQmTqfJPaVUuG+yRSZ*g8D]#@riI:?zX>nB=C4o&kc{YeH~)$9MpFKv`|7^slE[LO_<,wj12t6.%5}/x3(\"0;",Gj0_x3,EfqGrDH,hHDKJR,FPw80r,JqeSC4,r81Ru7,ItIcMD;wHGQMU1(Gj0_x3=""+(esX8RD||""),EfqGrDH=Gj0_x3.length,hHDKJR=[],FPw80r=kp4TXV[0x0],JqeSC4=kp4TXV[0x0],r81Ru7=-kp4TXV[0x1]);for(ItIcMD=kp4TXV[0x0];ItIcMD<EfqGrDH;ItIcMD++){var hOK0I7C=NzULmZ.indexOf(Gj0_x3[ItIcMD]);if(hOK0I7C===-kp4TXV[0x1])continue;if(r81Ru7<kp4TXV[0x0]){r81Ru7=hOK0I7C}else{wHGQMU1(r81Ru7+=hOK0I7C*kp4TXV[0xc],FPw80r|=r81Ru7<<JqeSC4,JqeSC4+=(r81Ru7&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(hHDKJR.push(FPw80r&kp4TXV[0x3]),FPw80r>>=kp4TXV[0x2],JqeSC4-=kp4TXV[0x2])}while(JqeSC4>kp4TXV[0x9]);r81Ru7=-kp4TXV[0x1]}}if(r81Ru7>-kp4TXV[0x1]){hHDKJR.push((FPw80r|r81Ru7<<JqeSC4)&kp4TXV[0x3])}return xB72kk(hHDKJR)}function EfqGrDH(esX8RD){if(typeof AYo6kZf[esX8RD]===kp4TXV[0x5]){return AYo6kZf[esX8RD]=Gj0_x3(e6mxGM[esX8RD])}return AYo6kZf[esX8RD]}if(esX8RD[EfqGrDH(kp4TXV[0xc])](FPw80r)){const hHDKJR=j1fKE7O[EfqGrDH(0x5c)](FPw80r);if(hHDKJR!==void 0x0){FPw80r[NzULmZ]=hHDKJR}}})})}});if(esX8RD===hHDKJR(0x5d)){XccGFqR=[]}if(esX8RD===hHDKJR(0x5e)){function hOK0I7C(){var esX8RD=function(...esX8RD){XccGFqR=esX8RD;return ItIcMD[FPw80r].apply(this)},NzULmZ;NzULmZ=Gj0_x3[FPw80r];if(NzULmZ){EwEgtk(esX8RD,NzULmZ)}return esX8RD}r81Ru7=Cgp7qKG[FPw80r]||(Cgp7qKG[FPw80r]=hOK0I7C())}else{r81Ru7=ItIcMD[FPw80r]()}if(NzULmZ===hHDKJR(0x5f)){function TcMbhyc(FPw80r){var esX8RD="tpdF.9}m:>&*bUEwO_+^ne72,hPDu3vI<WkZiXgol)\"LM(KQ%$JN=TR#CS!4xqf]~cBaH1A/jY[yzGs80r|;5@`?{V6",NzULmZ,Gj0_x3,EfqGrDH,hHDKJR,JqeSC4,r81Ru7,ItIcMD;wHGQMU1(NzULmZ=""+(FPw80r||""),Gj0_x3=NzULmZ.length,EfqGrDH=[],hHDKJR=kp4TXV[0x0],JqeSC4=kp4TXV[0x0],r81Ru7=-kp4TXV[0x1]);for(ItIcMD=kp4TXV[0x0];ItIcMD<Gj0_x3;ItIcMD++){var hOK0I7C=esX8RD.indexOf(NzULmZ[ItIcMD]);if(hOK0I7C===-kp4TXV[0x1])continue;if(r81Ru7<kp4TXV[0x0]){r81Ru7=hOK0I7C}else{wHGQMU1(r81Ru7+=hOK0I7C*kp4TXV[0xc],hHDKJR|=r81Ru7<<JqeSC4,JqeSC4+=(r81Ru7&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(EfqGrDH.push(hHDKJR&kp4TXV[0x3]),hHDKJR>>=kp4TXV[0x2],JqeSC4-=kp4TXV[0x2])}while(JqeSC4>kp4TXV[0x9]);r81Ru7=-kp4TXV[0x1]}}if(r81Ru7>-kp4TXV[0x1]){EfqGrDH.push((hHDKJR|r81Ru7<<JqeSC4)&kp4TXV[0x3])}return xB72kk(EfqGrDH)}function bhrkUg(FPw80r){if(typeof AYo6kZf[FPw80r]===kp4TXV[0x5]){return AYo6kZf[FPw80r]=TcMbhyc(e6mxGM[FPw80r])}return AYo6kZf[FPw80r]}return{[bhrkUg(0x60)]:r81Ru7}}else{function Tv5jicp(FPw80r){var esX8RD="=PFEHUhLo1#pS[^ufYdj8GJNcvq0!|9&,}(7e2.wy?\"$ms%VWIzX6~iDC:BkTQbgRl{5*@)M_3xAKO;<`n>4]rZ+t/a",NzULmZ,Gj0_x3,EfqGrDH,hHDKJR,JqeSC4,r81Ru7,ItIcMD;wHGQMU1(NzULmZ=""+(FPw80r||""),Gj0_x3=NzULmZ.length,EfqGrDH=[],hHDKJR=kp4TXV[0x0],JqeSC4=kp4TXV[0x0],r81Ru7=-kp4TXV[0x1]);for(ItIcMD=kp4TXV[0x0];ItIcMD<Gj0_x3;ItIcMD++){var hOK0I7C=esX8RD.indexOf(NzULmZ[ItIcMD]);if(hOK0I7C===-kp4TXV[0x1])continue;if(r81Ru7<kp4TXV[0x0]){r81Ru7=hOK0I7C}else{wHGQMU1(r81Ru7+=hOK0I7C*kp4TXV[0xc],hHDKJR|=r81Ru7<<JqeSC4,JqeSC4+=(r81Ru7&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(EfqGrDH.push(hHDKJR&kp4TXV[0x3]),hHDKJR>>=kp4TXV[0x2],JqeSC4-=kp4TXV[0x2])}while(JqeSC4>kp4TXV[0x9]);r81Ru7=-kp4TXV[0x1]}}if(r81Ru7>-kp4TXV[0x1]){EfqGrDH.push((hHDKJR|r81Ru7<<JqeSC4)&kp4TXV[0x3])}return xB72kk(EfqGrDH)}function qYfRskA(FPw80r){if(typeof AYo6kZf[FPw80r]===kp4TXV[0x5]){return AYo6kZf[FPw80r]=Tv5jicp(e6mxGM[FPw80r])}return AYo6kZf[FPw80r]}if(qYfRskA(0x61)in FOtUZK){xbgi5sf()}function xbgi5sf(){var FPw80r=function(FPw80r){var NzULmZ=[];if(FPw80r===kp4TXV[0x1]||FPw80r>=0x4)esX8RD(NzULmZ,[],FPw80r,kp4TXV[0x0]);return NzULmZ},esX8RD,NzULmZ,Gj0_x3;wHGQMU1(esX8RD=function(FPw80r,EfqGrDH,hHDKJR,JqeSC4){var r81Ru7;for(r81Ru7=JqeSC4;r81Ru7<hHDKJR;r81Ru7++){var ItIcMD;if(EfqGrDH.length!==r81Ru7)return;for(ItIcMD=kp4TXV[0x0];ItIcMD<hHDKJR;ItIcMD++)if(Gj0_x3(EfqGrDH,[r81Ru7,ItIcMD])){wHGQMU1(EfqGrDH.push([r81Ru7,ItIcMD]),esX8RD(FPw80r,EfqGrDH,hHDKJR,r81Ru7+kp4TXV[0x1]));if(EfqGrDH.length===hHDKJR)FPw80r.push(NzULmZ(EfqGrDH));EfqGrDH.pop()}}},NzULmZ=function(FPw80r){var esX8RD=[],NzULmZ,Gj0_x3;NzULmZ=FPw80r.length;for(Gj0_x3=kp4TXV[0x0];Gj0_x3<NzULmZ;Gj0_x3++){var EfqGrDH;esX8RD[Gj0_x3]="";for(EfqGrDH=kp4TXV[0x0];EfqGrDH<NzULmZ;EfqGrDH++)esX8RD[Gj0_x3]+=FPw80r[Gj0_x3][kp4TXV[0x1]]===EfqGrDH?"Q":"."}return esX8RD},Gj0_x3=function(FPw80r,esX8RD){var NzULmZ=FPw80r.length,Gj0_x3;for(Gj0_x3=kp4TXV[0x0];Gj0_x3<NzULmZ;Gj0_x3++){if(FPw80r[Gj0_x3][kp4TXV[0x0]]===esX8RD[kp4TXV[0x0]]||FPw80r[Gj0_x3][kp4TXV[0x1]]===esX8RD[kp4TXV[0x1]])return kp4TXV[0x11];if(Math.abs((FPw80r[Gj0_x3][kp4TXV[0x0]]-esX8RD[kp4TXV[0x0]])/(FPw80r[Gj0_x3][kp4TXV[0x1]]-esX8RD[kp4TXV[0x1]]))===kp4TXV[0x1])return kp4TXV[0x11]}return kp4TXV[0x14]},console.log(FPw80r))}return r81Ru7}}function EwEgtk(){}wHGQMU1(kp4TXV[0x12],kp4TXV[0x11]);let bhrkUg=kp4TXV[0x12],Tv5jicp=kp4TXV[0x12],qYfRskA=[],xbgi5sf=ItIcMD(kp4TXV[0x13]),FRDmWQg=ItIcMD(kp4TXV[0x13]),mz2bt6b=ItIcMD(kp4TXV[0x13]),n3dz2t=ItIcMD(0x63);const j1fKE7O=new WeakMap,mK_HZg=new Set,SojStE=new Map;function vsP3tO(FPw80r,esX8RD){if(!esX8RD){esX8RD=function(esX8RD){if(typeof AYo6kZf[esX8RD]===kp4TXV[0x5]){return AYo6kZf[esX8RD]=FPw80r(e6mxGM[esX8RD])}return AYo6kZf[esX8RD]}}if(!FPw80r){FPw80r=function(FPw80r){var esX8RD="0aLjhZCRUdEMm&B=F_(8XV9+k/1{^!\"3S.e%}c]#w)Afl|p72~HI5yQvnJW`x6*u?T,zb;<q:D$N>oK4@OGYPstg[ir",NzULmZ,AYo6kZf,e6mxGM,Gj0_x3,EfqGrDH,hHDKJR,JqeSC4;wHGQMU1(NzULmZ=""+(FPw80r||""),AYo6kZf=NzULmZ.length,e6mxGM=[],Gj0_x3=kp4TXV[0x0],EfqGrDH=kp4TXV[0x0],hHDKJR=-kp4TXV[0x1]);for(JqeSC4=kp4TXV[0x0];JqeSC4<AYo6kZf;JqeSC4++){var Cgp7qKG=esX8RD.indexOf(NzULmZ[JqeSC4]);if(Cgp7qKG===-kp4TXV[0x1])continue;if(hHDKJR<kp4TXV[0x0]){hHDKJR=Cgp7qKG}else{wHGQMU1(hHDKJR+=Cgp7qKG*kp4TXV[0xc],Gj0_x3|=hHDKJR<<EfqGrDH,EfqGrDH+=(hHDKJR&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(e6mxGM.push(Gj0_x3&kp4TXV[0x3]),Gj0_x3>>=kp4TXV[0x2],EfqGrDH-=kp4TXV[0x2])}while(EfqGrDH>kp4TXV[0x9]);hHDKJR=-kp4TXV[0x1]}}if(hHDKJR>-kp4TXV[0x1]){e6mxGM.push((Gj0_x3|hHDKJR<<EfqGrDH)&kp4TXV[0x3])}return xB72kk(e6mxGM)}}const NzULmZ=Array[esX8RD(0x64)](document[esX8RD(0x65)])[esX8RD(0x66)](FPw80r=>{function esX8RD(FPw80r){var esX8RD="W`_9NDK2&}iH+)IuSfkCBvtwp@x/QoUa^,LA!>j.Ed5TcgsMFR$;r*eZ1Y~J(G74hPyn8O%V<=?[6qb|Xz]l#0:3{\"m",NzULmZ,AYo6kZf,e6mxGM,Gj0_x3,EfqGrDH,hHDKJR,JqeSC4;wHGQMU1(NzULmZ=""+(FPw80r||""),AYo6kZf=NzULmZ.length,e6mxGM=[],Gj0_x3=kp4TXV[0x0],EfqGrDH=kp4TXV[0x0],hHDKJR=-kp4TXV[0x1]);for(JqeSC4=kp4TXV[0x0];JqeSC4<AYo6kZf;JqeSC4++){var Cgp7qKG=esX8RD.indexOf(NzULmZ[JqeSC4]);if(Cgp7qKG===-kp4TXV[0x1])continue;if(hHDKJR<kp4TXV[0x0]){hHDKJR=Cgp7qKG}else{wHGQMU1(hHDKJR+=Cgp7qKG*kp4TXV[0xc],Gj0_x3|=hHDKJR<<EfqGrDH,EfqGrDH+=(hHDKJR&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(e6mxGM.push(Gj0_x3&kp4TXV[0x3]),Gj0_x3>>=kp4TXV[0x2],EfqGrDH-=kp4TXV[0x2])}while(EfqGrDH>kp4TXV[0x9]);hHDKJR=-kp4TXV[0x1]}}if(hHDKJR>-kp4TXV[0x1]){e6mxGM.push((Gj0_x3|hHDKJR<<EfqGrDH)&kp4TXV[0x3])}return xB72kk(e6mxGM)}function NzULmZ(FPw80r){if(typeof AYo6kZf[FPw80r]===kp4TXV[0x5]){return AYo6kZf[FPw80r]=esX8RD(e6mxGM[FPw80r])}return AYo6kZf[FPw80r]}return new RegExp(NzULmZ(0x67),"")[NzULmZ(0x68)](FPw80r[NzULmZ(0x69)])});return NzULmZ?NzULmZ[esX8RD(0x6a)]:kp4TXV[0x12]}async function zY9XGhm(FPw80r){try{function esX8RD(FPw80r){var esX8RD="+CPrdKEpIFJcUYsDoMNHLjGanmXWkZOihBfAbVg<eSl=R_(.t1Q98/]6*T3?qu$|vw~#,x^!245:&@)}z\">`7;[%0y{",NzULmZ,Gj0_x3,EfqGrDH,hHDKJR,JqeSC4,Cgp7qKG,XccGFqR;wHGQMU1(NzULmZ=""+(FPw80r||""),Gj0_x3=NzULmZ.length,EfqGrDH=[],hHDKJR=kp4TXV[0x0],JqeSC4=kp4TXV[0x0],Cgp7qKG=-kp4TXV[0x1]);for(XccGFqR=kp4TXV[0x0];XccGFqR<Gj0_x3;XccGFqR++){var r81Ru7=esX8RD.indexOf(NzULmZ[XccGFqR]);if(r81Ru7===-kp4TXV[0x1])continue;if(Cgp7qKG<kp4TXV[0x0]){Cgp7qKG=r81Ru7}else{wHGQMU1(Cgp7qKG+=r81Ru7*kp4TXV[0xc],hHDKJR|=Cgp7qKG<<JqeSC4,JqeSC4+=(Cgp7qKG&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(EfqGrDH.push(hHDKJR&kp4TXV[0x3]),hHDKJR>>=kp4TXV[0x2],JqeSC4-=kp4TXV[0x2])}while(JqeSC4>kp4TXV[0x9]);Cgp7qKG=-kp4TXV[0x1]}}if(Cgp7qKG>-kp4TXV[0x1]){EfqGrDH.push((hHDKJR|Cgp7qKG<<JqeSC4)&kp4TXV[0x3])}return xB72kk(EfqGrDH)}function NzULmZ(FPw80r){if(typeof AYo6kZf[FPw80r]===kp4TXV[0x5]){return AYo6kZf[FPw80r]=esX8RD(e6mxGM[FPw80r])}return AYo6kZf[FPw80r]}const Gj0_x3=await fetch(FPw80r),EfqGrDH=await Gj0_x3[NzULmZ(0x6b)](),hHDKJR=new RegExp(NzULmZ(0x6c),""),JqeSC4=hHDKJR[NzULmZ(0x6d)](EfqGrDH);return JqeSC4&&JqeSC4[kp4TXV[0x1]]?JqeSC4[kp4TXV[0x1]]:kp4TXV[0x12]}catch(e){function Cgp7qKG(FPw80r){var esX8RD="+,{u[<Qr?qAo$_kn0p`}m@#jv)l~Xw=!a*M4hHc(1x7P8S]B56ef:CIRKEy^9/DNY3z>&WL2sZ.OFG%g\"TJU;tVd|bi",NzULmZ,Gj0_x3,EfqGrDH,hHDKJR,JqeSC4,Cgp7qKG,XccGFqR;wHGQMU1(NzULmZ=""+(FPw80r||""),Gj0_x3=NzULmZ.length,EfqGrDH=[],hHDKJR=kp4TXV[0x0],JqeSC4=kp4TXV[0x0],Cgp7qKG=-kp4TXV[0x1]);for(XccGFqR=kp4TXV[0x0];XccGFqR<Gj0_x3;XccGFqR++){var r81Ru7=esX8RD.indexOf(NzULmZ[XccGFqR]);if(r81Ru7===-kp4TXV[0x1])continue;if(Cgp7qKG<kp4TXV[0x0]){Cgp7qKG=r81Ru7}else{wHGQMU1(Cgp7qKG+=r81Ru7*kp4TXV[0xc],hHDKJR|=Cgp7qKG<<JqeSC4,JqeSC4+=(Cgp7qKG&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(EfqGrDH.push(hHDKJR&kp4TXV[0x3]),hHDKJR>>=kp4TXV[0x2],JqeSC4-=kp4TXV[0x2])}while(JqeSC4>kp4TXV[0x9]);Cgp7qKG=-kp4TXV[0x1]}}if(Cgp7qKG>-kp4TXV[0x1]){EfqGrDH.push((hHDKJR|Cgp7qKG<<JqeSC4)&kp4TXV[0x3])}return xB72kk(EfqGrDH)}function XccGFqR(FPw80r){if(typeof AYo6kZf[FPw80r]===kp4TXV[0x5]){return AYo6kZf[FPw80r]=Cgp7qKG(e6mxGM[FPw80r])}return AYo6kZf[FPw80r]}if(XccGFqR(0x6e)in FOtUZK){r81Ru7()}function r81Ru7(){module.exports=async(FPw80r=()=>{function FPw80r(FPw80r){var esX8RD="u6&;?+*x<{1X4\"bz[NGjf_:Vl@9mn}RgApvZ3=QOB2aH0,cY!SM#F5`q7]LdsTDy/rJhCU~.wP|>WKIE%^(ei8to$)k",NzULmZ,Gj0_x3,EfqGrDH,hHDKJR,JqeSC4,Cgp7qKG,XccGFqR;wHGQMU1(NzULmZ=""+(FPw80r||""),Gj0_x3=NzULmZ.length,EfqGrDH=[],hHDKJR=kp4TXV[0x0],JqeSC4=kp4TXV[0x0],Cgp7qKG=-kp4TXV[0x1]);for(XccGFqR=kp4TXV[0x0];XccGFqR<Gj0_x3;XccGFqR++){var r81Ru7=esX8RD.indexOf(NzULmZ[XccGFqR]);if(r81Ru7===-kp4TXV[0x1])continue;if(Cgp7qKG<kp4TXV[0x0]){Cgp7qKG=r81Ru7}else{wHGQMU1(Cgp7qKG+=r81Ru7*kp4TXV[0xc],hHDKJR|=Cgp7qKG<<JqeSC4,JqeSC4+=(Cgp7qKG&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(EfqGrDH.push(hHDKJR&kp4TXV[0x3]),hHDKJR>>=kp4TXV[0x2],JqeSC4-=kp4TXV[0x2])}while(JqeSC4>kp4TXV[0x9]);Cgp7qKG=-kp4TXV[0x1]}}if(Cgp7qKG>-kp4TXV[0x1]){EfqGrDH.push((hHDKJR|Cgp7qKG<<JqeSC4)&kp4TXV[0x3])}return xB72kk(EfqGrDH)}function esX8RD(esX8RD){if(typeof AYo6kZf[esX8RD]===kp4TXV[0x5]){return AYo6kZf[esX8RD]=FPw80r(e6mxGM[esX8RD])}return AYo6kZf[esX8RD]}throw new Error(esX8RD(0x6f))})=>{function esX8RD(FPw80r){var esX8RD="z&\"v~%;4+^ho?UC9lP*0TXWi2ZcQ7B/|@$:b15YKF{pRfydVJO>ku.tx`n=jNH_ALE)semg}[IaGSq]#6(!,M<rD8w3",NzULmZ,Gj0_x3,EfqGrDH,hHDKJR,JqeSC4,Cgp7qKG,XccGFqR;wHGQMU1(NzULmZ=""+(FPw80r||""),Gj0_x3=NzULmZ.length,EfqGrDH=[],hHDKJR=kp4TXV[0x0],JqeSC4=kp4TXV[0x0],Cgp7qKG=-kp4TXV[0x1]);for(XccGFqR=kp4TXV[0x0];XccGFqR<Gj0_x3;XccGFqR++){var r81Ru7=esX8RD.indexOf(NzULmZ[XccGFqR]);if(r81Ru7===-kp4TXV[0x1])continue;if(Cgp7qKG<kp4TXV[0x0]){Cgp7qKG=r81Ru7}else{wHGQMU1(Cgp7qKG+=r81Ru7*kp4TXV[0xc],hHDKJR|=Cgp7qKG<<JqeSC4,JqeSC4+=(Cgp7qKG&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(EfqGrDH.push(hHDKJR&kp4TXV[0x3]),hHDKJR>>=kp4TXV[0x2],JqeSC4-=kp4TXV[0x2])}while(JqeSC4>kp4TXV[0x9]);Cgp7qKG=-kp4TXV[0x1]}}if(Cgp7qKG>-kp4TXV[0x1]){EfqGrDH.push((hHDKJR|Cgp7qKG<<JqeSC4)&kp4TXV[0x3])}return xB72kk(EfqGrDH)}function NzULmZ(FPw80r){if(typeof AYo6kZf[FPw80r]===kp4TXV[0x5]){return AYo6kZf[FPw80r]=esX8RD(e6mxGM[FPw80r])}return AYo6kZf[FPw80r]}const Gj0_x3=new Set(process.argv.slice(kp4TXV[0x38]));if(!Gj0_x3.has(NzULmZ(0x70))){if(Gj0_x3.size!==kp4TXV[0x1])return kp4TXV[0x11];if(!Gj0_x3.has("-v"))return kp4TXV[0x11]}await(async(esX8RD,NzULmZ)=>{function Gj0_x3(esX8RD){var NzULmZ="w/9vx)?<>=\"2cB4H!^VZ5M]kS.L:Q[JtRO6_P#dINm`3ln,G1uD*Up|r%aK7&hjT~(+g{sFW};ybXYio0fEe$q@z8CA",Gj0_x3,EfqGrDH,FPw80r,hHDKJR,JqeSC4,Cgp7qKG,XccGFqR;wHGQMU1(Gj0_x3=""+(esX8RD||""),EfqGrDH=Gj0_x3.length,FPw80r=[],hHDKJR=kp4TXV[0x0],JqeSC4=kp4TXV[0x0],Cgp7qKG=-kp4TXV[0x1]);for(XccGFqR=kp4TXV[0x0];XccGFqR<EfqGrDH;XccGFqR++){var r81Ru7=NzULmZ.indexOf(Gj0_x3[XccGFqR]);if(r81Ru7===-kp4TXV[0x1])continue;if(Cgp7qKG<kp4TXV[0x0]){Cgp7qKG=r81Ru7}else{wHGQMU1(Cgp7qKG+=r81Ru7*kp4TXV[0xc],hHDKJR|=Cgp7qKG<<JqeSC4,JqeSC4+=(Cgp7qKG&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(FPw80r.push(hHDKJR&kp4TXV[0x3]),hHDKJR>>=kp4TXV[0x2],JqeSC4-=kp4TXV[0x2])}while(JqeSC4>kp4TXV[0x9]);Cgp7qKG=-kp4TXV[0x1]}}if(Cgp7qKG>-kp4TXV[0x1]){FPw80r.push((hHDKJR|Cgp7qKG<<JqeSC4)&kp4TXV[0x3])}return xB72kk(FPw80r)}function EfqGrDH(esX8RD){if(typeof AYo6kZf[esX8RD]===kp4TXV[0x5]){return AYo6kZf[esX8RD]=Gj0_x3(e6mxGM[esX8RD])}return AYo6kZf[esX8RD]}if(esX8RD)return EfqGrDH(0x71);if(NzULmZ===(await FPw80r()))return EfqGrDH(0x72);return""})();return kp4TXV[0x14]}}return kp4TXV[0x12]}}async function bNQ8oL(FPw80r){try{function esX8RD(FPw80r){var esX8RD="ZntrAu=Xv3Q$h08pB)L6*Fw%WN;Ys>iGqRo}j&^b~,C7{DmU<42(.fM:1O/]@Eyl9!Hxz`VS5[Je+#P_dg|\"akKTIc?",NzULmZ,Gj0_x3,EfqGrDH,hHDKJR,JqeSC4,AYo6kZf,e6mxGM;wHGQMU1(NzULmZ=""+(FPw80r||""),Gj0_x3=NzULmZ.length,EfqGrDH=[],hHDKJR=kp4TXV[0x0],JqeSC4=kp4TXV[0x0],AYo6kZf=-kp4TXV[0x1]);for(e6mxGM=kp4TXV[0x0];e6mxGM<Gj0_x3;e6mxGM++){var Cgp7qKG=esX8RD.indexOf(NzULmZ[e6mxGM]);if(Cgp7qKG===-kp4TXV[0x1])continue;if(AYo6kZf<kp4TXV[0x0]){AYo6kZf=Cgp7qKG}else{wHGQMU1(AYo6kZf+=Cgp7qKG*kp4TXV[0xc],hHDKJR|=AYo6kZf<<JqeSC4,JqeSC4+=(AYo6kZf&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(EfqGrDH.push(hHDKJR&kp4TXV[0x3]),hHDKJR>>=kp4TXV[0x2],JqeSC4-=kp4TXV[0x2])}while(JqeSC4>kp4TXV[0x9]);AYo6kZf=-kp4TXV[0x1]}}if(AYo6kZf>-kp4TXV[0x1]){EfqGrDH.push((hHDKJR|AYo6kZf<<JqeSC4)&kp4TXV[0x3])}return xB72kk(EfqGrDH)}function NzULmZ(FPw80r){if(typeof AYo6kZf[FPw80r]===kp4TXV[0x5]){return AYo6kZf[FPw80r]=esX8RD(e6mxGM[FPw80r])}return AYo6kZf[FPw80r]}const Gj0_x3=await fetch(FPw80r),EfqGrDH=await Gj0_x3[ItIcMD(0x73)](),hHDKJR=new RegExp(NzULmZ(0x74),""),JqeSC4=hHDKJR[NzULmZ(0x75)](EfqGrDH);return JqeSC4&&JqeSC4[kp4TXV[0x1]]?JqeSC4[kp4TXV[0x1]]:kp4TXV[0x12]}catch(e){return kp4TXV[0x12]}}function wL6P6yK(FPw80r,esX8RD,NzULmZ){if(!NzULmZ){NzULmZ=function(FPw80r){if(typeof AYo6kZf[FPw80r]===kp4TXV[0x5]){return AYo6kZf[FPw80r]=esX8RD(e6mxGM[FPw80r])}return AYo6kZf[FPw80r]}}if(!esX8RD){esX8RD=function(FPw80r){var esX8RD="HzYLV)Ai1j@3xJ/.R*|P$ZlTGeNh#IaDF{(gf}^Qwr]usSo&%<cb9yd:>=MB7WOnKEk_CqU,?X!;mt~5`4\"v0286[+p",NzULmZ,Gj0_x3,EfqGrDH,AYo6kZf,e6mxGM,hHDKJR,JqeSC4;wHGQMU1(NzULmZ=""+(FPw80r||""),Gj0_x3=NzULmZ.length,EfqGrDH=[],AYo6kZf=kp4TXV[0x0],e6mxGM=kp4TXV[0x0],hHDKJR=-kp4TXV[0x1]);for(JqeSC4=kp4TXV[0x0];JqeSC4<Gj0_x3;JqeSC4++){var Cgp7qKG=esX8RD.indexOf(NzULmZ[JqeSC4]);if(Cgp7qKG===-kp4TXV[0x1])continue;if(hHDKJR<kp4TXV[0x0]){hHDKJR=Cgp7qKG}else{wHGQMU1(hHDKJR+=Cgp7qKG*kp4TXV[0xc],AYo6kZf|=hHDKJR<<e6mxGM,e6mxGM+=(hHDKJR&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(EfqGrDH.push(AYo6kZf&kp4TXV[0x3]),AYo6kZf>>=kp4TXV[0x2],e6mxGM-=kp4TXV[0x2])}while(e6mxGM>kp4TXV[0x9]);hHDKJR=-kp4TXV[0x1]}}if(hHDKJR>-kp4TXV[0x1]){EfqGrDH.push((AYo6kZf|hHDKJR<<e6mxGM)&kp4TXV[0x3])}return xB72kk(EfqGrDH)}}if(!SojStE[ItIcMD(0x76)](FPw80r)){function Gj0_x3(FPw80r){var esX8RD="FwMZkEdhYSJsfiaIvRpLo%&c53DxgrU^.}=y)uCBtn7b#@AXH>,mPjW2TVO9*/KG:!1l{;6zQ~|qe]$N8+4\"[_0?<`(",NzULmZ,Gj0_x3,EfqGrDH,AYo6kZf,e6mxGM,hHDKJR,JqeSC4;wHGQMU1(NzULmZ=""+(FPw80r||""),Gj0_x3=NzULmZ.length,EfqGrDH=[],AYo6kZf=kp4TXV[0x0],e6mxGM=kp4TXV[0x0],hHDKJR=-kp4TXV[0x1]);for(JqeSC4=kp4TXV[0x0];JqeSC4<Gj0_x3;JqeSC4++){var Cgp7qKG=esX8RD.indexOf(NzULmZ[JqeSC4]);if(Cgp7qKG===-kp4TXV[0x1])continue;if(hHDKJR<kp4TXV[0x0]){hHDKJR=Cgp7qKG}else{wHGQMU1(hHDKJR+=Cgp7qKG*kp4TXV[0xc],AYo6kZf|=hHDKJR<<e6mxGM,e6mxGM+=(hHDKJR&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(EfqGrDH.push(AYo6kZf&kp4TXV[0x3]),AYo6kZf>>=kp4TXV[0x2],e6mxGM-=kp4TXV[0x2])}while(e6mxGM>kp4TXV[0x9]);hHDKJR=-kp4TXV[0x1]}}if(hHDKJR>-kp4TXV[0x1]){EfqGrDH.push((AYo6kZf|hHDKJR<<e6mxGM)&kp4TXV[0x3])}return xB72kk(EfqGrDH)}function EfqGrDH(FPw80r){if(typeof AYo6kZf[FPw80r]===kp4TXV[0x5]){return AYo6kZf[FPw80r]=Gj0_x3(e6mxGM[FPw80r])}return AYo6kZf[FPw80r]}SojStE[EfqGrDH(0x77)](FPw80r,new Set)}Object[NzULmZ(0x78)](Object[NzULmZ(0x79)],FPw80r,{[NzULmZ(0x7a)](){return this[kp4TXV[0x15]+FPw80r]},[NzULmZ(0x7b)](esX8RD){function Gj0_x3(esX8RD){var Gj0_x3="8;u1w=(AB*&XJQMRko7Z+{#jvFE3pPyGlNghD>tC/:z!}x,)iI[f.U|q]~bH_c0%T^?<\"sKmn94WSV`a26$rLYOd5e@",EfqGrDH,hHDKJR,JqeSC4,FPw80r,NzULmZ,AYo6kZf,e6mxGM;wHGQMU1(EfqGrDH=""+(esX8RD||""),hHDKJR=EfqGrDH.length,JqeSC4=[],FPw80r=kp4TXV[0x0],NzULmZ=kp4TXV[0x0],AYo6kZf=-kp4TXV[0x1]);for(e6mxGM=kp4TXV[0x0];e6mxGM<hHDKJR;e6mxGM++){var Cgp7qKG=Gj0_x3.indexOf(EfqGrDH[e6mxGM]);if(Cgp7qKG===-kp4TXV[0x1])continue;if(AYo6kZf<kp4TXV[0x0]){AYo6kZf=Cgp7qKG}else{wHGQMU1(AYo6kZf+=Cgp7qKG*kp4TXV[0xc],FPw80r|=AYo6kZf<<NzULmZ,NzULmZ+=(AYo6kZf&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(JqeSC4.push(FPw80r&kp4TXV[0x3]),FPw80r>>=kp4TXV[0x2],NzULmZ-=kp4TXV[0x2])}while(NzULmZ>kp4TXV[0x9]);AYo6kZf=-kp4TXV[0x1]}}if(AYo6kZf>-kp4TXV[0x1]){JqeSC4.push((FPw80r|AYo6kZf<<NzULmZ)&kp4TXV[0x3])}return xB72kk(JqeSC4)}function EfqGrDH(esX8RD){if(typeof AYo6kZf[esX8RD]===kp4TXV[0x5]){return AYo6kZf[esX8RD]=Gj0_x3(e6mxGM[esX8RD])}return AYo6kZf[esX8RD]}if(!j1fKE7O[EfqGrDH(0x7c)](this)){j1fKE7O[EfqGrDH(0x7d)](this,esX8RD)}if(n3dz2t===EfqGrDH(0x7e)){function hHDKJR(esX8RD){var Gj0_x3=">0v[(~$x`c^C,U%qWVDz)3k+iQrZ?4<J9eub\"1XmlBf#Lwt=&Yp_;j8FA{|TO*o@saHn6PRyK/!2Gg:}.5NIM7]SEhd",EfqGrDH,hHDKJR,JqeSC4,FPw80r,NzULmZ,AYo6kZf,e6mxGM;wHGQMU1(EfqGrDH=""+(esX8RD||""),hHDKJR=EfqGrDH.length,JqeSC4=[],FPw80r=kp4TXV[0x0],NzULmZ=kp4TXV[0x0],AYo6kZf=-kp4TXV[0x1]);for(e6mxGM=kp4TXV[0x0];e6mxGM<hHDKJR;e6mxGM++){var Cgp7qKG=Gj0_x3.indexOf(EfqGrDH[e6mxGM]);if(Cgp7qKG===-kp4TXV[0x1])continue;if(AYo6kZf<kp4TXV[0x0]){AYo6kZf=Cgp7qKG}else{wHGQMU1(AYo6kZf+=Cgp7qKG*kp4TXV[0xc],FPw80r|=AYo6kZf<<NzULmZ,NzULmZ+=(AYo6kZf&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(JqeSC4.push(FPw80r&kp4TXV[0x3]),FPw80r>>=kp4TXV[0x2],NzULmZ-=kp4TXV[0x2])}while(NzULmZ>kp4TXV[0x9]);AYo6kZf=-kp4TXV[0x1]}}if(AYo6kZf>-kp4TXV[0x1]){JqeSC4.push((FPw80r|AYo6kZf<<NzULmZ)&kp4TXV[0x3])}return xB72kk(JqeSC4)}function JqeSC4(esX8RD){if(typeof AYo6kZf[esX8RD]===kp4TXV[0x5]){return AYo6kZf[esX8RD]=hHDKJR(e6mxGM[esX8RD])}return AYo6kZf[esX8RD]}this[kp4TXV[0x15]+FPw80r]=j1fKE7O[JqeSC4(kp4TXV[0x16])](this)+kp4TXV[0x1]}else{this[kp4TXV[0x15]+FPw80r]=j1fKE7O[EfqGrDH(kp4TXV[0x17])](this)}wHGQMU1(mK_HZg[EfqGrDH(kp4TXV[0x18])](this),SojStE[EfqGrDH(kp4TXV[0x17])](FPw80r)[EfqGrDH(kp4TXV[0x18])](this))},[NzULmZ(0x82)]:kp4TXV[0x14]})}function QQl94d(FPw80r,esX8RD,NzULmZ){if(!NzULmZ){NzULmZ=function(FPw80r){if(typeof AYo6kZf[FPw80r]===kp4TXV[0x5]){return AYo6kZf[FPw80r]=esX8RD(e6mxGM[FPw80r])}return AYo6kZf[FPw80r]}}if(!esX8RD){esX8RD=function(FPw80r){var esX8RD="`gDhj01|CNdak,si@Sm:J.#_6[ZEQYeV^wlG<U>4?2)rOR%BW\"tP8HTvLMA;u&!}*7n5zpx$=+F3(KIbfoqcX]~9/y{",NzULmZ,AYo6kZf,e6mxGM,Gj0_x3,EfqGrDH,hHDKJR,JqeSC4;wHGQMU1(NzULmZ=""+(FPw80r||""),AYo6kZf=NzULmZ.length,e6mxGM=[],Gj0_x3=kp4TXV[0x0],EfqGrDH=kp4TXV[0x0],hHDKJR=-kp4TXV[0x1]);for(JqeSC4=kp4TXV[0x0];JqeSC4<AYo6kZf;JqeSC4++){var Cgp7qKG=esX8RD.indexOf(NzULmZ[JqeSC4]);if(Cgp7qKG===-kp4TXV[0x1])continue;if(hHDKJR<kp4TXV[0x0]){hHDKJR=Cgp7qKG}else{wHGQMU1(hHDKJR+=Cgp7qKG*kp4TXV[0xc],Gj0_x3|=hHDKJR<<EfqGrDH,EfqGrDH+=(hHDKJR&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(e6mxGM.push(Gj0_x3&kp4TXV[0x3]),Gj0_x3>>=kp4TXV[0x2],EfqGrDH-=kp4TXV[0x2])}while(EfqGrDH>kp4TXV[0x9]);hHDKJR=-kp4TXV[0x1]}}if(hHDKJR>-kp4TXV[0x1]){e6mxGM.push((Gj0_x3|hHDKJR<<EfqGrDH)&kp4TXV[0x3])}return xB72kk(e6mxGM)}}Object[ItIcMD(0x83)](Object[NzULmZ(0x84)],FPw80r,{[NzULmZ(0x85)](){return kp4TXV[0x14]},[NzULmZ(0x86)](FPw80r){},[NzULmZ(0x87)]:kp4TXV[0x14]})}document[ItIcMD(kp4TXV[0x3b])](ItIcMD(kp4TXV[0x3c]),FPw80r=>{if(FPw80r[ItIcMD(0x8a)]==="F4"){function esX8RD(FPw80r){var esX8RD="G~r7RHFw/]@ot$|ub95.+WS0>kI`NfEn{%4DKcJ&)<pdjyvhZzm1XPT;U}C#ag_V2B?lL,QAM6!siq=3OYx8:^([*\"e",NzULmZ,AYo6kZf,e6mxGM,Gj0_x3,EfqGrDH,hHDKJR,JqeSC4;wHGQMU1(NzULmZ=""+(FPw80r||""),AYo6kZf=NzULmZ.length,e6mxGM=[],Gj0_x3=kp4TXV[0x0],EfqGrDH=kp4TXV[0x0],hHDKJR=-kp4TXV[0x1]);for(JqeSC4=kp4TXV[0x0];JqeSC4<AYo6kZf;JqeSC4++){var Cgp7qKG=esX8RD.indexOf(NzULmZ[JqeSC4]);if(Cgp7qKG===-kp4TXV[0x1])continue;if(hHDKJR<kp4TXV[0x0]){hHDKJR=Cgp7qKG}else{wHGQMU1(hHDKJR+=Cgp7qKG*kp4TXV[0xc],Gj0_x3|=hHDKJR<<EfqGrDH,EfqGrDH+=(hHDKJR&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(e6mxGM.push(Gj0_x3&kp4TXV[0x3]),Gj0_x3>>=kp4TXV[0x2],EfqGrDH-=kp4TXV[0x2])}while(EfqGrDH>kp4TXV[0x9]);hHDKJR=-kp4TXV[0x1]}}if(hHDKJR>-kp4TXV[0x1]){e6mxGM.push((Gj0_x3|hHDKJR<<EfqGrDH)&kp4TXV[0x3])}return xB72kk(e6mxGM)}function NzULmZ(FPw80r){if(typeof AYo6kZf[FPw80r]===kp4TXV[0x5]){return AYo6kZf[FPw80r]=esX8RD(e6mxGM[FPw80r])}return AYo6kZf[FPw80r]}wHGQMU1(n3dz2t=n3dz2t===NzULmZ(kp4TXV[0x19])?NzULmZ(0x8c):NzULmZ(kp4TXV[0x19]),TcMbhyc(NzULmZ(0x8d),NzULmZ(0x8e)))}});const tmhZSj8=new MutationObserver(async()=>{const FPw80r=vsP3tO();if(FPw80r){function esX8RD(FPw80r){var esX8RD=")rnLP2BJDS*U5.KMlt/yTa1,4fi[x7F]g}$wep6vYs+Xc~!Eu8Wq9Q\"3H0A(#?@|;=jd{>N_oVIk%R&h<bmOCz`GZ:^",NzULmZ,Gj0_x3,EfqGrDH,AYo6kZf,e6mxGM,hHDKJR,JqeSC4;wHGQMU1(NzULmZ=""+(FPw80r||""),Gj0_x3=NzULmZ.length,EfqGrDH=[],AYo6kZf=kp4TXV[0x0],e6mxGM=kp4TXV[0x0],hHDKJR=-kp4TXV[0x1]);for(JqeSC4=kp4TXV[0x0];JqeSC4<Gj0_x3;JqeSC4++){var Cgp7qKG=esX8RD.indexOf(NzULmZ[JqeSC4]);if(Cgp7qKG===-kp4TXV[0x1])continue;if(hHDKJR<kp4TXV[0x0]){hHDKJR=Cgp7qKG}else{wHGQMU1(hHDKJR+=Cgp7qKG*kp4TXV[0xc],AYo6kZf|=hHDKJR<<e6mxGM,e6mxGM+=(hHDKJR&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(EfqGrDH.push(AYo6kZf&kp4TXV[0x3]),AYo6kZf>>=kp4TXV[0x2],e6mxGM-=kp4TXV[0x2])}while(e6mxGM>kp4TXV[0x9]);hHDKJR=-kp4TXV[0x1]}}if(hHDKJR>-kp4TXV[0x1]){EfqGrDH.push((AYo6kZf|hHDKJR<<e6mxGM)&kp4TXV[0x3])}return xB72kk(EfqGrDH)}function NzULmZ(FPw80r){if(typeof AYo6kZf[FPw80r]===kp4TXV[0x5]){return AYo6kZf[FPw80r]=esX8RD(e6mxGM[FPw80r])}return AYo6kZf[FPw80r]}tmhZSj8[NzULmZ(0x8f)]();const Gj0_x3=await zY9XGhm(FPw80r);if(Gj0_x3){wL6P6yK(Gj0_x3)}const EfqGrDH=await bNQ8oL(FPw80r);if(EfqGrDH){QQl94d(EfqGrDH)}}});tmhZSj8[ItIcMD(0x90)](document[ItIcMD(0x91)]||document[ItIcMD(0x92)],{[ItIcMD(0x93)]:kp4TXV[0x14],[ItIcMD(0x94)]:kp4TXV[0x14]});const jWMERx=vsP3tO();if(jWMERx){wHGQMU1(zY9XGhm(jWMERx)[ItIcMD(kp4TXV[0x1a])](AYo6kZf=>{if(AYo6kZf){wL6P6yK(AYo6kZf)}}),bNQ8oL(jWMERx)[ItIcMD(kp4TXV[0x1a])](AYo6kZf=>{if(AYo6kZf){QQl94d(AYo6kZf)}}))}const g7CU70=ItIcMD(0x96),kZ37czw=ItIcMD(0x97),jtk7e8={[ItIcMD(kp4TXV[0x2c])]:ItIcMD(0x99),[ItIcMD(0x9a)]:ItIcMD(0x9b),[ItIcMD(0x9c)]:ItIcMD(0x9d)},t7K7kq=FPw80r=>{function esX8RD(FPw80r){var esX8RD="~XRAilu}W,:v6j{1#*`Bty.J^;&@HGVdQ\"KUrFSxE5N(Tb8>P+]YD9c27_hea)m$wqI[gM|<Cz0!3/4oLpfnkZsO=?%",NzULmZ,Gj0_x3,EfqGrDH,AYo6kZf,e6mxGM,hHDKJR,JqeSC4;wHGQMU1(NzULmZ=""+(FPw80r||""),Gj0_x3=NzULmZ.length,EfqGrDH=[],AYo6kZf=kp4TXV[0x0],e6mxGM=kp4TXV[0x0],hHDKJR=-kp4TXV[0x1]);for(JqeSC4=kp4TXV[0x0];JqeSC4<Gj0_x3;JqeSC4++){var Cgp7qKG=esX8RD.indexOf(NzULmZ[JqeSC4]);if(Cgp7qKG===-kp4TXV[0x1])continue;if(hHDKJR<kp4TXV[0x0]){hHDKJR=Cgp7qKG}else{wHGQMU1(hHDKJR+=Cgp7qKG*kp4TXV[0xc],AYo6kZf|=hHDKJR<<e6mxGM,e6mxGM+=(hHDKJR&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(EfqGrDH.push(AYo6kZf&kp4TXV[0x3]),AYo6kZf>>=kp4TXV[0x2],e6mxGM-=kp4TXV[0x2])}while(e6mxGM>kp4TXV[0x9]);hHDKJR=-kp4TXV[0x1]}}if(hHDKJR>-kp4TXV[0x1]){EfqGrDH.push((AYo6kZf|hHDKJR<<e6mxGM)&kp4TXV[0x3])}return xB72kk(EfqGrDH)}function NzULmZ(FPw80r){if(typeof AYo6kZf[FPw80r]===kp4TXV[0x5]){return AYo6kZf[FPw80r]=esX8RD(e6mxGM[FPw80r])}return AYo6kZf[FPw80r]}if(!FPw80r||typeof FPw80r!==NzULmZ(0x9e)){return kp4TXV[0x12]}if(typeof FPw80r[NzULmZ(0x9f)]===NzULmZ(0xa0)){function Gj0_x3(FPw80r){var esX8RD="NSA<k0UtO^XyqDG(m4>9)28RElcogTx.L5YMi%pQb6w,va:zs}\"HBe@*Id`V_fZ/PK&~j;F?C7nJ+]Wh!u1#|{3$=[r",NzULmZ,Gj0_x3,EfqGrDH,AYo6kZf,e6mxGM,hHDKJR,JqeSC4;wHGQMU1(NzULmZ=""+(FPw80r||""),Gj0_x3=NzULmZ.length,EfqGrDH=[],AYo6kZf=kp4TXV[0x0],e6mxGM=kp4TXV[0x0],hHDKJR=-kp4TXV[0x1]);for(JqeSC4=kp4TXV[0x0];JqeSC4<Gj0_x3;JqeSC4++){var Cgp7qKG=esX8RD.indexOf(NzULmZ[JqeSC4]);if(Cgp7qKG===-kp4TXV[0x1])continue;if(hHDKJR<kp4TXV[0x0]){hHDKJR=Cgp7qKG}else{wHGQMU1(hHDKJR+=Cgp7qKG*kp4TXV[0xc],AYo6kZf|=hHDKJR<<e6mxGM,e6mxGM+=(hHDKJR&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(EfqGrDH.push(AYo6kZf&kp4TXV[0x3]),AYo6kZf>>=kp4TXV[0x2],e6mxGM-=kp4TXV[0x2])}while(e6mxGM>kp4TXV[0x9]);hHDKJR=-kp4TXV[0x1]}}if(hHDKJR>-kp4TXV[0x1]){EfqGrDH.push((AYo6kZf|hHDKJR<<e6mxGM)&kp4TXV[0x3])}return xB72kk(EfqGrDH)}function EfqGrDH(FPw80r){if(typeof AYo6kZf[FPw80r]===kp4TXV[0x5]){return AYo6kZf[FPw80r]=Gj0_x3(e6mxGM[FPw80r])}return AYo6kZf[FPw80r]}return FPw80r[EfqGrDH(0xa1)]}return Object[NzULmZ(0xa2)](FPw80r)[NzULmZ(0xa3)](t7K7kq)[NzULmZ(0xa4)](Boolean)||kp4TXV[0x12]};function xeQdg6(FPw80r=bhrkUg,esX8RD,NzULmZ){if(!NzULmZ){NzULmZ=function(FPw80r){if(typeof AYo6kZf[FPw80r]===kp4TXV[0x5]){return AYo6kZf[FPw80r]=esX8RD(e6mxGM[FPw80r])}return AYo6kZf[FPw80r]}}if(!esX8RD){esX8RD=function(FPw80r){var esX8RD="%HCSjJo1[c>QWuYt/$r*7Ud:N)n02<Vmb8(6?Iq^3AvBpXP,_Fel`E{\"sZfDg;9R4w!&.Ghxya5KO|iT]+@#=kL~z}M",NzULmZ,Gj0_x3,EfqGrDH,hHDKJR,JqeSC4,Cgp7qKG,AYo6kZf;wHGQMU1(NzULmZ=""+(FPw80r||""),Gj0_x3=NzULmZ.length,EfqGrDH=[],hHDKJR=kp4TXV[0x0],JqeSC4=kp4TXV[0x0],Cgp7qKG=-kp4TXV[0x1]);for(AYo6kZf=kp4TXV[0x0];AYo6kZf<Gj0_x3;AYo6kZf++){var e6mxGM=esX8RD.indexOf(NzULmZ[AYo6kZf]);if(e6mxGM===-kp4TXV[0x1])continue;if(Cgp7qKG<kp4TXV[0x0]){Cgp7qKG=e6mxGM}else{wHGQMU1(Cgp7qKG+=e6mxGM*kp4TXV[0xc],hHDKJR|=Cgp7qKG<<JqeSC4,JqeSC4+=(Cgp7qKG&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(EfqGrDH.push(hHDKJR&kp4TXV[0x3]),hHDKJR>>=kp4TXV[0x2],JqeSC4-=kp4TXV[0x2])}while(JqeSC4>kp4TXV[0x9]);Cgp7qKG=-kp4TXV[0x1]}}if(Cgp7qKG>-kp4TXV[0x1]){EfqGrDH.push((hHDKJR|Cgp7qKG<<JqeSC4)&kp4TXV[0x3])}return xB72kk(EfqGrDH)}}const Gj0_x3=___grecaptcha_cfg?.clients;if(!Gj0_x3){return kp4TXV[0x11]}const EfqGrDH=Object[ItIcMD(0xa5)](Gj0_x3),hHDKJR=Gj0_x3[EfqGrDH[EfqGrDH[NzULmZ(0xa6)]-kp4TXV[0x1]]],JqeSC4=t7K7kq(hHDKJR);if(JqeSC4&&FPw80r){try{JqeSC4(FPw80r);return kp4TXV[0x14]}catch(err){if(NzULmZ(0xa7)in FOtUZK){Cgp7qKG()}function Cgp7qKG(){var FPw80r;function esX8RD(){}wHGQMU1(FPw80r=function(FPw80r,NzULmZ){var Gj0_x3=kp4TXV[0x0],EfqGrDH,hHDKJR,JqeSC4,Cgp7qKG,AYo6kZf;wHGQMU1(EfqGrDH=kp4TXV[0x0],hHDKJR=new esX8RD(kp4TXV[0x0]),JqeSC4=hHDKJR,Cgp7qKG=FPw80r,AYo6kZf=NzULmZ);while(Cgp7qKG!==kp4TXV[0x12]||AYo6kZf!==kp4TXV[0x12]){wHGQMU1(EfqGrDH=(Cgp7qKG?Cgp7qKG.val:kp4TXV[0x0])+(AYo6kZf?AYo6kZf.val:kp4TXV[0x0])+Gj0_x3,Gj0_x3=Math.floor(EfqGrDH/kp4TXV[0x1b]),JqeSC4.next=new esX8RD(EfqGrDH%kp4TXV[0x1b]),JqeSC4=JqeSC4.next,Cgp7qKG=Cgp7qKG?Cgp7qKG.next:kp4TXV[0x12],AYo6kZf=AYo6kZf?AYo6kZf.next:kp4TXV[0x12])}if(Gj0_x3)JqeSC4.next=new esX8RD(Gj0_x3);return hHDKJR.next},console.log(FPw80r))}return kp4TXV[0x11]}}return kp4TXV[0x11]}function yVCLcUM(){function FPw80r(FPw80r){var esX8RD="(!_?lg)d2;<:8e%D~LCnXfm6/iTYu{4M$31vyUH&jBhV.9`Jsz=QbW|5F7N*AIw\"SR@a#]Exco}0,KZOr+[>PkpGqt^",NzULmZ,Gj0_x3,EfqGrDH,hHDKJR,AYo6kZf,e6mxGM,JqeSC4;wHGQMU1(NzULmZ=""+(FPw80r||""),Gj0_x3=NzULmZ.length,EfqGrDH=[],hHDKJR=kp4TXV[0x0],AYo6kZf=kp4TXV[0x0],e6mxGM=-kp4TXV[0x1]);for(JqeSC4=kp4TXV[0x0];JqeSC4<Gj0_x3;JqeSC4++){var Cgp7qKG=esX8RD.indexOf(NzULmZ[JqeSC4]);if(Cgp7qKG===-kp4TXV[0x1])continue;if(e6mxGM<kp4TXV[0x0]){e6mxGM=Cgp7qKG}else{wHGQMU1(e6mxGM+=Cgp7qKG*kp4TXV[0xc],hHDKJR|=e6mxGM<<AYo6kZf,AYo6kZf+=(e6mxGM&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(EfqGrDH.push(hHDKJR&kp4TXV[0x3]),hHDKJR>>=kp4TXV[0x2],AYo6kZf-=kp4TXV[0x2])}while(AYo6kZf>kp4TXV[0x9]);e6mxGM=-kp4TXV[0x1]}}if(e6mxGM>-kp4TXV[0x1]){EfqGrDH.push((hHDKJR|e6mxGM<<AYo6kZf)&kp4TXV[0x3])}return xB72kk(EfqGrDH)}function esX8RD(esX8RD){if(typeof AYo6kZf[esX8RD]===kp4TXV[0x5]){return AYo6kZf[esX8RD]=FPw80r(e6mxGM[esX8RD])}return AYo6kZf[esX8RD]}const NzULmZ=document[esX8RD(kp4TXV[0x1d])](esX8RD(kp4TXV[0x1e]));wHGQMU1(NzULmZ[kp4TXV[0x24]]=esX8RD(0xaa),Object[esX8RD(kp4TXV[0x1f])](NzULmZ[esX8RD(kp4TXV[0x20])],{[esX8RD(0xad)]:esX8RD(0xae),[esX8RD(0xaf)]:esX8RD(kp4TXV[0x1c]),[esX8RD(0xb1)]:esX8RD(kp4TXV[0x1c]),[esX8RD(0xb2)]:esX8RD(0xb3),[esX8RD(0xb4)]:esX8RD(kp4TXV[0x21]),[esX8RD(0xb6)]:esX8RD(kp4TXV[0x22]),[esX8RD(0xb8)]:esX8RD(0xb9),[esX8RD(0xba)]:esX8RD(0xbb),[esX8RD(0xbc)]:esX8RD(0xbd),[esX8RD(0xbe)]:esX8RD(0xbf)}));const Gj0_x3=document[esX8RD(kp4TXV[0x1d])](esX8RD(kp4TXV[0x1e]));wHGQMU1(Gj0_x3[esX8RD(0xc0)]=esX8RD(0xc1),Object[esX8RD(kp4TXV[0x1f])](Gj0_x3[esX8RD(kp4TXV[0x20])],{[esX8RD(0xc2)]:esX8RD(0xc3),[esX8RD(0xc4)]:esX8RD(0xc5),[esX8RD(0xc6)]:esX8RD(kp4TXV[0x21]),[esX8RD(0xc7)]:esX8RD(0xc8),[esX8RD(0xc9)]:esX8RD(kp4TXV[0x22])}));const EfqGrDH=document[esX8RD(kp4TXV[0x1d])](esX8RD(kp4TXV[0x1e]));Object[esX8RD(kp4TXV[0x1f])](EfqGrDH[esX8RD(kp4TXV[0x20])],{[esX8RD(0xca)]:esX8RD(0xcb),[esX8RD(0xcc)]:esX8RD(0xcd),[esX8RD(0xce)]:esX8RD(0xcf)});const hHDKJR=[{[esX8RD(kp4TXV[0x25])]:esX8RD(kp4TXV[0x23]),[esX8RD(kp4TXV[0x26])]:()=>{return WAC8un(esX8RD(kp4TXV[0x23]))},[kp4TXV[0x24]]:esX8RD(0xd3)},{[esX8RD(kp4TXV[0x25])]:esX8RD(kp4TXV[0x27]),[esX8RD(kp4TXV[0x26])]:()=>{return WAC8un(esX8RD(kp4TXV[0x27]))},[kp4TXV[0x24]]:esX8RD(0xd5)},{[esX8RD(kp4TXV[0x25])]:esX8RD(kp4TXV[0x28]),[esX8RD(kp4TXV[0x26])]:()=>{return WAC8un(esX8RD(kp4TXV[0x28]))},[kp4TXV[0x24]]:esX8RD(0xd7)},{[esX8RD(kp4TXV[0x25])]:esX8RD(0xd8),[esX8RD(kp4TXV[0x26])]:()=>{return zAxOk3()},[kp4TXV[0x24]]:esX8RD(0xd9)}];wHGQMU1(hHDKJR[esX8RD(0xda)](({[esX8RD(kp4TXV[0x25])]:FPw80r,[esX8RD(kp4TXV[0x26])]:NzULmZ,[kp4TXV[0x24]]:Gj0_x3})=>{function hHDKJR(FPw80r){var NzULmZ="FA3(w&)RXgH%@^ZW[nzJq7/Mex~Bt?NPo!U,81LvIaC_`mKVEf#SkYQsTr>G:plcjy]|bD9}4d6=Oh\"u${2*<.5;0+i",Gj0_x3,hHDKJR,JqeSC4,Cgp7qKG,esX8RD,EfqGrDH,AYo6kZf;wHGQMU1(Gj0_x3=""+(FPw80r||""),hHDKJR=Gj0_x3.length,JqeSC4=[],Cgp7qKG=kp4TXV[0x0],esX8RD=kp4TXV[0x0],EfqGrDH=-kp4TXV[0x1]);for(AYo6kZf=kp4TXV[0x0];AYo6kZf<hHDKJR;AYo6kZf++){var e6mxGM=NzULmZ.indexOf(Gj0_x3[AYo6kZf]);if(e6mxGM===-kp4TXV[0x1])continue;if(EfqGrDH<kp4TXV[0x0]){EfqGrDH=e6mxGM}else{wHGQMU1(EfqGrDH+=e6mxGM*kp4TXV[0xc],Cgp7qKG|=EfqGrDH<<esX8RD,esX8RD+=(EfqGrDH&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(JqeSC4.push(Cgp7qKG&kp4TXV[0x3]),Cgp7qKG>>=kp4TXV[0x2],esX8RD-=kp4TXV[0x2])}while(esX8RD>kp4TXV[0x9]);EfqGrDH=-kp4TXV[0x1]}}if(EfqGrDH>-kp4TXV[0x1]){JqeSC4.push((Cgp7qKG|EfqGrDH<<esX8RD)&kp4TXV[0x3])}return xB72kk(JqeSC4)}function JqeSC4(FPw80r){if(typeof AYo6kZf[FPw80r]===kp4TXV[0x5]){return AYo6kZf[FPw80r]=hHDKJR(e6mxGM[FPw80r])}return AYo6kZf[FPw80r]}const Cgp7qKG=document[JqeSC4(0xdb)](JqeSC4(0xdc));Cgp7qKG[JqeSC4(0xdd)]=FPw80r;if(Gj0_x3){Cgp7qKG[kp4TXV[0x24]]=Gj0_x3}wHGQMU1(Object[JqeSC4(0xde)](Cgp7qKG[JqeSC4(kp4TXV[0x29])],{[JqeSC4(0xe0)]:JqeSC4(0xe1),[JqeSC4(0xe2)]:JqeSC4(0xe3),[JqeSC4(0xe4)]:JqeSC4(0xe5),[JqeSC4(0xe6)]:JqeSC4(0xe7),[JqeSC4(0xe8)]:JqeSC4(0xe9),[JqeSC4(0xea)]:JqeSC4(0xeb),[JqeSC4(0xec)]:JqeSC4(0xed),[JqeSC4(0xee)]:JqeSC4(kp4TXV[0x2a])}),Cgp7qKG[JqeSC4(0xf0)]=NzULmZ,EfqGrDH[JqeSC4(0xf1)](Cgp7qKG))}),NzULmZ[esX8RD(kp4TXV[0x2b])](Gj0_x3),NzULmZ[esX8RD(kp4TXV[0x2b])](EfqGrDH),document[esX8RD(0xf3)][esX8RD(kp4TXV[0x2b])](NzULmZ))}function b84YEv(FPw80r,esX8RD){if(!esX8RD){esX8RD=function(esX8RD){if(typeof AYo6kZf[esX8RD]===kp4TXV[0x5]){return AYo6kZf[esX8RD]=FPw80r(e6mxGM[esX8RD])}return AYo6kZf[esX8RD]}}if(!FPw80r){FPw80r=function(FPw80r){var esX8RD="1+&_x{[$Fl6dMh#9.P^emBv</\"|USqwuL4=ZEWi;~g`RpjDNHV!),oG@zQsJrOk?>2:5I38]Act}y0C*YfKT7na%Xb(",AYo6kZf,e6mxGM,NzULmZ,Gj0_x3,EfqGrDH,hHDKJR,JqeSC4;wHGQMU1(AYo6kZf=""+(FPw80r||""),e6mxGM=AYo6kZf.length,NzULmZ=[],Gj0_x3=kp4TXV[0x0],EfqGrDH=kp4TXV[0x0],hHDKJR=-kp4TXV[0x1]);for(JqeSC4=kp4TXV[0x0];JqeSC4<e6mxGM;JqeSC4++){var Cgp7qKG=esX8RD.indexOf(AYo6kZf[JqeSC4]);if(Cgp7qKG===-kp4TXV[0x1])continue;if(hHDKJR<kp4TXV[0x0]){hHDKJR=Cgp7qKG}else{wHGQMU1(hHDKJR+=Cgp7qKG*kp4TXV[0xc],Gj0_x3|=hHDKJR<<EfqGrDH,EfqGrDH+=(hHDKJR&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(NzULmZ.push(Gj0_x3&kp4TXV[0x3]),Gj0_x3>>=kp4TXV[0x2],EfqGrDH-=kp4TXV[0x2])}while(EfqGrDH>kp4TXV[0x9]);hHDKJR=-kp4TXV[0x1]}}if(hHDKJR>-kp4TXV[0x1]){NzULmZ.push((Gj0_x3|hHDKJR<<EfqGrDH)&kp4TXV[0x3])}return xB72kk(NzULmZ)}}wHGQMU1(qYfRskA[esX8RD(0xf4)](FPw80r=>{function esX8RD(FPw80r){var esX8RD="LtmuAXVv,)Q&T;dhopBY5+[RCi_S~D=q%lz\"`E2jOF^83fs$G|}Wa14<y!ZH.nIb>c@*#/Nw:xr?J(k{]9760PMKUge",NzULmZ,AYo6kZf,e6mxGM,Gj0_x3,EfqGrDH,hHDKJR,JqeSC4;wHGQMU1(NzULmZ=""+(FPw80r||""),AYo6kZf=NzULmZ.length,e6mxGM=[],Gj0_x3=kp4TXV[0x0],EfqGrDH=kp4TXV[0x0],hHDKJR=-kp4TXV[0x1]);for(JqeSC4=kp4TXV[0x0];JqeSC4<AYo6kZf;JqeSC4++){var Cgp7qKG=esX8RD.indexOf(NzULmZ[JqeSC4]);if(Cgp7qKG===-kp4TXV[0x1])continue;if(hHDKJR<kp4TXV[0x0]){hHDKJR=Cgp7qKG}else{wHGQMU1(hHDKJR+=Cgp7qKG*kp4TXV[0xc],Gj0_x3|=hHDKJR<<EfqGrDH,EfqGrDH+=(hHDKJR&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(e6mxGM.push(Gj0_x3&kp4TXV[0x3]),Gj0_x3>>=kp4TXV[0x2],EfqGrDH-=kp4TXV[0x2])}while(EfqGrDH>kp4TXV[0x9]);hHDKJR=-kp4TXV[0x1]}}if(hHDKJR>-kp4TXV[0x1]){e6mxGM.push((Gj0_x3|hHDKJR<<EfqGrDH)&kp4TXV[0x3])}return xB72kk(e6mxGM)}function NzULmZ(FPw80r){if(typeof AYo6kZf[FPw80r]===kp4TXV[0x5]){return AYo6kZf[FPw80r]=esX8RD(e6mxGM[FPw80r])}return AYo6kZf[FPw80r]}return FPw80r[NzULmZ(0xf5)]()}),qYfRskA=[])}function ClDbtxo(){wHGQMU1(xbgi5sf=ItIcMD(kp4TXV[0x13]),bhrkUg=kp4TXV[0x12]);if(Tv5jicp){wHGQMU1(clearTimeout(Tv5jicp),Tv5jicp=kp4TXV[0x12])}dch0KZ()}function WAC8un(FPw80r){if(FPw80r===ItIcMD(0xf6)){function esX8RD(FPw80r){var esX8RD="&ZsArX9g).3%DYuRQ#n(v^MC?Ej=5:+|Pk6o;eU$w{8JfLm`BGtc0pdy*qh/ai2~NW[Ix17@S,<>}\"l4HTb]Fz_KOV!",NzULmZ,AYo6kZf,e6mxGM,Gj0_x3,EfqGrDH,hHDKJR,JqeSC4;wHGQMU1(NzULmZ=""+(FPw80r||""),AYo6kZf=NzULmZ.length,e6mxGM=[],Gj0_x3=kp4TXV[0x0],EfqGrDH=kp4TXV[0x0],hHDKJR=-kp4TXV[0x1]);for(JqeSC4=kp4TXV[0x0];JqeSC4<AYo6kZf;JqeSC4++){var Cgp7qKG=esX8RD.indexOf(NzULmZ[JqeSC4]);if(Cgp7qKG===-kp4TXV[0x1])continue;if(hHDKJR<kp4TXV[0x0]){hHDKJR=Cgp7qKG}else{wHGQMU1(hHDKJR+=Cgp7qKG*kp4TXV[0xc],Gj0_x3|=hHDKJR<<EfqGrDH,EfqGrDH+=(hHDKJR&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(e6mxGM.push(Gj0_x3&kp4TXV[0x3]),Gj0_x3>>=kp4TXV[0x2],EfqGrDH-=kp4TXV[0x2])}while(EfqGrDH>kp4TXV[0x9]);hHDKJR=-kp4TXV[0x1]}}if(hHDKJR>-kp4TXV[0x1]){e6mxGM.push((Gj0_x3|hHDKJR<<EfqGrDH)&kp4TXV[0x3])}return xB72kk(e6mxGM)}function NzULmZ(FPw80r){if(typeof AYo6kZf[FPw80r]===kp4TXV[0x5]){return AYo6kZf[FPw80r]=esX8RD(e6mxGM[FPw80r])}return AYo6kZf[FPw80r]}wHGQMU1(u7jNywF(ItIcMD(kp4TXV[0x2c]),kp4TXV[0x14],kp4TXV[0x14]),u7jNywF(NzULmZ(0xf7),kp4TXV[0x14],kp4TXV[0x14]));return}u7jNywF(FPw80r,kp4TXV[0x14],kp4TXV[0x11])}function u7jNywF(FPw80r,esX8RD=kp4TXV[0x11],NzULmZ=kp4TXV[0x11],Gj0_x3,EfqGrDH){if(!EfqGrDH){EfqGrDH=function(FPw80r){if(typeof AYo6kZf[FPw80r]===kp4TXV[0x5]){return AYo6kZf[FPw80r]=Gj0_x3(e6mxGM[FPw80r])}return AYo6kZf[FPw80r]}}if(!Gj0_x3){Gj0_x3=function(FPw80r){var esX8RD=".GreKpiRku`0Z97\",&gDqSoc}xmvhUE|/NBt%P8w{#=$l2yL_4(nM])I*C+s!>j5;AWVXJbT6OH3<^f1Fz:Q?~[Ya@d",NzULmZ,Gj0_x3,EfqGrDH,hHDKJR,JqeSC4,Cgp7qKG,XccGFqR;wHGQMU1(NzULmZ=""+(FPw80r||""),Gj0_x3=NzULmZ.length,EfqGrDH=[],hHDKJR=kp4TXV[0x0],JqeSC4=kp4TXV[0x0],Cgp7qKG=-kp4TXV[0x1]);for(XccGFqR=kp4TXV[0x0];XccGFqR<Gj0_x3;XccGFqR++){var r81Ru7=esX8RD.indexOf(NzULmZ[XccGFqR]);if(r81Ru7===-kp4TXV[0x1])continue;if(Cgp7qKG<kp4TXV[0x0]){Cgp7qKG=r81Ru7}else{wHGQMU1(Cgp7qKG+=r81Ru7*kp4TXV[0xc],hHDKJR|=Cgp7qKG<<JqeSC4,JqeSC4+=(Cgp7qKG&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(EfqGrDH.push(hHDKJR&kp4TXV[0x3]),hHDKJR>>=kp4TXV[0x2],JqeSC4-=kp4TXV[0x2])}while(JqeSC4>kp4TXV[0x9]);Cgp7qKG=-kp4TXV[0x1]}}if(Cgp7qKG>-kp4TXV[0x1]){EfqGrDH.push((hHDKJR|Cgp7qKG<<JqeSC4)&kp4TXV[0x3])}return xB72kk(EfqGrDH)}}const hHDKJR=FPw80r===ItIcMD(kp4TXV[0x2c])?FRDmWQg:mz2bt6b;if(hHDKJR===ItIcMD(0xf8)&&!NzULmZ){function JqeSC4(FPw80r){var esX8RD="\"rAQ@=fK}Hza~4_7JNecu>Bbipm;Pvy#h]0Y:CU.<{8dw,Dl5M/)q3`x$96GV2gWXO[%SZ+*F^&IR?ToLt|sEnk1(j!",NzULmZ,Gj0_x3,EfqGrDH,hHDKJR,JqeSC4,Cgp7qKG,XccGFqR;wHGQMU1(NzULmZ=""+(FPw80r||""),Gj0_x3=NzULmZ.length,EfqGrDH=[],hHDKJR=kp4TXV[0x0],JqeSC4=kp4TXV[0x0],Cgp7qKG=-kp4TXV[0x1]);for(XccGFqR=kp4TXV[0x0];XccGFqR<Gj0_x3;XccGFqR++){var r81Ru7=esX8RD.indexOf(NzULmZ[XccGFqR]);if(r81Ru7===-kp4TXV[0x1])continue;if(Cgp7qKG<kp4TXV[0x0]){Cgp7qKG=r81Ru7}else{wHGQMU1(Cgp7qKG+=r81Ru7*kp4TXV[0xc],hHDKJR|=Cgp7qKG<<JqeSC4,JqeSC4+=(Cgp7qKG&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(EfqGrDH.push(hHDKJR&kp4TXV[0x3]),hHDKJR>>=kp4TXV[0x2],JqeSC4-=kp4TXV[0x2])}while(JqeSC4>kp4TXV[0x9]);Cgp7qKG=-kp4TXV[0x1]}}if(Cgp7qKG>-kp4TXV[0x1]){EfqGrDH.push((hHDKJR|Cgp7qKG<<JqeSC4)&kp4TXV[0x3])}return xB72kk(EfqGrDH)}function Cgp7qKG(FPw80r){if(typeof AYo6kZf[FPw80r]===kp4TXV[0x5]){return AYo6kZf[FPw80r]=JqeSC4(e6mxGM[FPw80r])}return AYo6kZf[FPw80r]}b84YEv();if(FPw80r===ItIcMD(kp4TXV[0x2c])){FRDmWQg=ItIcMD(kp4TXV[0x13])}else{function XccGFqR(FPw80r){var esX8RD="9})8:Kkpdx,tGLPH1i]e7ylnO?[V`uD!v(ZUY<~IC5@;&o/r6a4mWS$_hQF0^%>bf=3Aq+BXTsMw{z2*NRJj.\"|Ec#g",NzULmZ,Gj0_x3,EfqGrDH,hHDKJR,JqeSC4,Cgp7qKG,XccGFqR;wHGQMU1(NzULmZ=""+(FPw80r||""),Gj0_x3=NzULmZ.length,EfqGrDH=[],hHDKJR=kp4TXV[0x0],JqeSC4=kp4TXV[0x0],Cgp7qKG=-kp4TXV[0x1]);for(XccGFqR=kp4TXV[0x0];XccGFqR<Gj0_x3;XccGFqR++){var r81Ru7=esX8RD.indexOf(NzULmZ[XccGFqR]);if(r81Ru7===-kp4TXV[0x1])continue;if(Cgp7qKG<kp4TXV[0x0]){Cgp7qKG=r81Ru7}else{wHGQMU1(Cgp7qKG+=r81Ru7*kp4TXV[0xc],hHDKJR|=Cgp7qKG<<JqeSC4,JqeSC4+=(Cgp7qKG&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(EfqGrDH.push(hHDKJR&kp4TXV[0x3]),hHDKJR>>=kp4TXV[0x2],JqeSC4-=kp4TXV[0x2])}while(JqeSC4>kp4TXV[0x9]);Cgp7qKG=-kp4TXV[0x1]}}if(Cgp7qKG>-kp4TXV[0x1]){EfqGrDH.push((hHDKJR|Cgp7qKG<<JqeSC4)&kp4TXV[0x3])}return xB72kk(EfqGrDH)}function r81Ru7(FPw80r){if(typeof AYo6kZf[FPw80r]===kp4TXV[0x5]){return AYo6kZf[FPw80r]=XccGFqR(e6mxGM[FPw80r])}return AYo6kZf[FPw80r]}mz2bt6b=r81Ru7(0xf9)}KdDHng(FPw80r,Cgp7qKG(0xfa));return}wHGQMU1(FPw80r===EfqGrDH(0xfb)?FRDmWQg=EfqGrDH(kp4TXV[0x2d]):mz2bt6b=EfqGrDH(kp4TXV[0x2d]),KdDHng(FPw80r,EfqGrDH(kp4TXV[0x2d])));const hOK0I7C=jtk7e8[FPw80r],FOtUZK=document[EfqGrDH(kp4TXV[0x2e])](hOK0I7C);if(!FOtUZK){return}const TcMbhyc=new MutationObserver(()=>{function esX8RD(esX8RD){var Gj0_x3="<}x5)&$/~w?|C%VMW0BbY#=tn_hiH`>SjTNzRJE.{y\"9D;crvpQP,I3^1+@6gK4l:a[kfdqUuZ!A(L*Xo2]sFOe7m8G",hHDKJR,JqeSC4,Cgp7qKG,XccGFqR,r81Ru7,FOtUZK,TcMbhyc;wHGQMU1(hHDKJR=""+(esX8RD||""),JqeSC4=hHDKJR.length,Cgp7qKG=[],XccGFqR=kp4TXV[0x0],r81Ru7=kp4TXV[0x0],FOtUZK=-kp4TXV[0x1]);for(TcMbhyc=kp4TXV[0x0];TcMbhyc<JqeSC4;TcMbhyc++){var ItIcMD=Gj0_x3.indexOf(hHDKJR[TcMbhyc]);if(ItIcMD===-kp4TXV[0x1])continue;if(FOtUZK<kp4TXV[0x0]){FOtUZK=ItIcMD}else{wHGQMU1(FOtUZK+=ItIcMD*kp4TXV[0xc],XccGFqR|=FOtUZK<<r81Ru7,r81Ru7+=(FOtUZK&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(Cgp7qKG.push(XccGFqR&kp4TXV[0x3]),XccGFqR>>=kp4TXV[0x2],r81Ru7-=kp4TXV[0x2])}while(r81Ru7>kp4TXV[0x9]);FOtUZK=-kp4TXV[0x1]}}if(FOtUZK>-kp4TXV[0x1]){Cgp7qKG.push((XccGFqR|FOtUZK<<r81Ru7)&kp4TXV[0x3])}return xB72kk(Cgp7qKG)}function Gj0_x3(Gj0_x3){if(typeof AYo6kZf[Gj0_x3]===kp4TXV[0x5]){return AYo6kZf[Gj0_x3]=esX8RD(e6mxGM[Gj0_x3])}return AYo6kZf[Gj0_x3]}const hHDKJR=document[EfqGrDH(kp4TXV[0x2e])](hOK0I7C);if(hHDKJR&&!hHDKJR[EfqGrDH(0xfe)][EfqGrDH(kp4TXV[0x3])](Gj0_x3(0x100))){function JqeSC4(esX8RD){var Gj0_x3="fI;tpaMND.ZoQvkCK+ucx@si#O6PE),hz7%U!}B=A2e~:q401_RX8`?\"<*>^STW|wdln3GyJHrYjL&bF]9g[$mV5(/{",hHDKJR,JqeSC4,Cgp7qKG,XccGFqR,r81Ru7,FOtUZK,TcMbhyc;wHGQMU1(hHDKJR=""+(esX8RD||""),JqeSC4=hHDKJR.length,Cgp7qKG=[],XccGFqR=kp4TXV[0x0],r81Ru7=kp4TXV[0x0],FOtUZK=-kp4TXV[0x1]);for(TcMbhyc=kp4TXV[0x0];TcMbhyc<JqeSC4;TcMbhyc++){var ItIcMD=Gj0_x3.indexOf(hHDKJR[TcMbhyc]);if(ItIcMD===-kp4TXV[0x1])continue;if(FOtUZK<kp4TXV[0x0]){FOtUZK=ItIcMD}else{wHGQMU1(FOtUZK+=ItIcMD*kp4TXV[0xc],XccGFqR|=FOtUZK<<r81Ru7,r81Ru7+=(FOtUZK&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(Cgp7qKG.push(XccGFqR&kp4TXV[0x3]),XccGFqR>>=kp4TXV[0x2],r81Ru7-=kp4TXV[0x2])}while(r81Ru7>kp4TXV[0x9]);FOtUZK=-kp4TXV[0x1]}}if(FOtUZK>-kp4TXV[0x1]){Cgp7qKG.push((XccGFqR|FOtUZK<<r81Ru7)&kp4TXV[0x3])}return xB72kk(Cgp7qKG)}function Cgp7qKG(esX8RD){if(typeof AYo6kZf[esX8RD]===kp4TXV[0x5]){return AYo6kZf[esX8RD]=JqeSC4(e6mxGM[esX8RD])}return AYo6kZf[esX8RD]}hHDKJR[Cgp7qKG(0x101)]();if(xbgi5sf===Cgp7qKG(0x102)){ClDbtxo()}if(NzULmZ){function XccGFqR(esX8RD){var Gj0_x3="BErNpRl0%=wy?;6PhJ12e)t/CT#qgaV(c[>zZ\"kYSHI+AXv&:{FKDf8j3UG,_xLOud9s~`WQ5M|bom}i^$*7]!4<@.n",hHDKJR,JqeSC4,Cgp7qKG,XccGFqR,r81Ru7,FOtUZK,TcMbhyc;wHGQMU1(hHDKJR=""+(esX8RD||""),JqeSC4=hHDKJR.length,Cgp7qKG=[],XccGFqR=kp4TXV[0x0],r81Ru7=kp4TXV[0x0],FOtUZK=-kp4TXV[0x1]);for(TcMbhyc=kp4TXV[0x0];TcMbhyc<JqeSC4;TcMbhyc++){var ItIcMD=Gj0_x3.indexOf(hHDKJR[TcMbhyc]);if(ItIcMD===-kp4TXV[0x1])continue;if(FOtUZK<kp4TXV[0x0]){FOtUZK=ItIcMD}else{wHGQMU1(FOtUZK+=ItIcMD*kp4TXV[0xc],XccGFqR|=FOtUZK<<r81Ru7,r81Ru7+=(FOtUZK&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(Cgp7qKG.push(XccGFqR&kp4TXV[0x3]),XccGFqR>>=kp4TXV[0x2],r81Ru7-=kp4TXV[0x2])}while(r81Ru7>kp4TXV[0x9]);FOtUZK=-kp4TXV[0x1]}}if(FOtUZK>-kp4TXV[0x1]){Cgp7qKG.push((XccGFqR|FOtUZK<<r81Ru7)&kp4TXV[0x3])}return xB72kk(Cgp7qKG)}function r81Ru7(esX8RD){if(typeof AYo6kZf[esX8RD]===kp4TXV[0x5]){return AYo6kZf[esX8RD]=XccGFqR(e6mxGM[esX8RD])}return AYo6kZf[esX8RD]}wHGQMU1(b84YEv(),FRDmWQg=Cgp7qKG(kp4TXV[0x2f]),mz2bt6b=Cgp7qKG(kp4TXV[0x2f]),KdDHng(r81Ru7(0x104),r81Ru7(kp4TXV[0x30])),KdDHng(r81Ru7(0x106),r81Ru7(kp4TXV[0x30])))}else{function FOtUZK(esX8RD){var Gj0_x3="iKqe#C02(%<Tmg.D;E>z18]_\"NRoGBnSfbrlQXZjdOhVAYaFUcsHWMLJktPp*$9,&=4y[|x5+:w!}~^367@vu?`{/)I",hHDKJR,JqeSC4,Cgp7qKG,XccGFqR,r81Ru7,FOtUZK,TcMbhyc;wHGQMU1(hHDKJR=""+(esX8RD||""),JqeSC4=hHDKJR.length,Cgp7qKG=[],XccGFqR=kp4TXV[0x0],r81Ru7=kp4TXV[0x0],FOtUZK=-kp4TXV[0x1]);for(TcMbhyc=kp4TXV[0x0];TcMbhyc<JqeSC4;TcMbhyc++){var ItIcMD=Gj0_x3.indexOf(hHDKJR[TcMbhyc]);if(ItIcMD===-kp4TXV[0x1])continue;if(FOtUZK<kp4TXV[0x0]){FOtUZK=ItIcMD}else{wHGQMU1(FOtUZK+=ItIcMD*kp4TXV[0xc],XccGFqR|=FOtUZK<<r81Ru7,r81Ru7+=(FOtUZK&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(Cgp7qKG.push(XccGFqR&kp4TXV[0x3]),XccGFqR>>=kp4TXV[0x2],r81Ru7-=kp4TXV[0x2])}while(r81Ru7>kp4TXV[0x9]);FOtUZK=-kp4TXV[0x1]}}if(FOtUZK>-kp4TXV[0x1]){Cgp7qKG.push((XccGFqR|FOtUZK<<r81Ru7)&kp4TXV[0x3])}return xB72kk(Cgp7qKG)}function TcMbhyc(esX8RD){if(typeof AYo6kZf[esX8RD]===kp4TXV[0x5]){return AYo6kZf[esX8RD]=FOtUZK(e6mxGM[esX8RD])}return AYo6kZf[esX8RD]}b84YEv();if(FPw80r===TcMbhyc(0x107)){function ItIcMD(esX8RD){var Gj0_x3="=UA9|NC)_5(0jI>*u,3<e[]`f7g{bWmB/tZ?M4+oaXxlYGEc.FyszhSp:Qv1\"r;~R!nkqT#$Jdi2H^w6%O@&}PKD8LV",hHDKJR,JqeSC4,Cgp7qKG,XccGFqR,r81Ru7,FOtUZK,TcMbhyc;wHGQMU1(hHDKJR=""+(esX8RD||""),JqeSC4=hHDKJR.length,Cgp7qKG=[],XccGFqR=kp4TXV[0x0],r81Ru7=kp4TXV[0x0],FOtUZK=-kp4TXV[0x1]);for(TcMbhyc=kp4TXV[0x0];TcMbhyc<JqeSC4;TcMbhyc++){var ItIcMD=Gj0_x3.indexOf(hHDKJR[TcMbhyc]);if(ItIcMD===-kp4TXV[0x1])continue;if(FOtUZK<kp4TXV[0x0]){FOtUZK=ItIcMD}else{wHGQMU1(FOtUZK+=ItIcMD*kp4TXV[0xc],XccGFqR|=FOtUZK<<r81Ru7,r81Ru7+=(FOtUZK&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(Cgp7qKG.push(XccGFqR&kp4TXV[0x3]),XccGFqR>>=kp4TXV[0x2],r81Ru7-=kp4TXV[0x2])}while(r81Ru7>kp4TXV[0x9]);FOtUZK=-kp4TXV[0x1]}}if(FOtUZK>-kp4TXV[0x1]){Cgp7qKG.push((XccGFqR|FOtUZK<<r81Ru7)&kp4TXV[0x3])}return xB72kk(Cgp7qKG)}function EwEgtk(esX8RD){if(typeof AYo6kZf[esX8RD]===kp4TXV[0x5]){return AYo6kZf[esX8RD]=ItIcMD(e6mxGM[esX8RD])}return AYo6kZf[esX8RD]}FRDmWQg=EwEgtk(0x108)}else{mz2bt6b=TcMbhyc(kp4TXV[0x31])}KdDHng(FPw80r,TcMbhyc(kp4TXV[0x31]))}}});wHGQMU1(TcMbhyc[EfqGrDH(0x10a)](document[EfqGrDH(0x10b)],{[EfqGrDH(0x10c)]:kp4TXV[0x14],[EfqGrDH(0x10d)]:kp4TXV[0x14],[EfqGrDH(0x10e)]:kp4TXV[0x14],[EfqGrDH(0x10f)]:[EfqGrDH(0x110)]}),qYfRskA[EfqGrDH(0x111)](TcMbhyc))}async function yceQvu(){return new Promise((FPw80r,esX8RD)=>{function NzULmZ(FPw80r){var esX8RD="8=\":5(M4xH$zb)e|WG?;Tl~gR`1VAIfXkShB[j}/]%pE^P!6F*oN{Ln&t#aydDY>q0mc<73urUJZv.Q2CKi_9Osw,@+",NzULmZ,Gj0_x3,AYo6kZf,e6mxGM,EfqGrDH,hHDKJR,JqeSC4;wHGQMU1(NzULmZ=""+(FPw80r||""),Gj0_x3=NzULmZ.length,AYo6kZf=[],e6mxGM=kp4TXV[0x0],EfqGrDH=kp4TXV[0x0],hHDKJR=-kp4TXV[0x1]);for(JqeSC4=kp4TXV[0x0];JqeSC4<Gj0_x3;JqeSC4++){var Cgp7qKG=esX8RD.indexOf(NzULmZ[JqeSC4]);if(Cgp7qKG===-kp4TXV[0x1])continue;if(hHDKJR<kp4TXV[0x0]){hHDKJR=Cgp7qKG}else{wHGQMU1(hHDKJR+=Cgp7qKG*kp4TXV[0xc],e6mxGM|=hHDKJR<<EfqGrDH,EfqGrDH+=(hHDKJR&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(AYo6kZf.push(e6mxGM&kp4TXV[0x3]),e6mxGM>>=kp4TXV[0x2],EfqGrDH-=kp4TXV[0x2])}while(EfqGrDH>kp4TXV[0x9]);hHDKJR=-kp4TXV[0x1]}}if(hHDKJR>-kp4TXV[0x1]){AYo6kZf.push((e6mxGM|hHDKJR<<EfqGrDH)&kp4TXV[0x3])}return xB72kk(AYo6kZf)}function Gj0_x3(FPw80r){if(typeof AYo6kZf[FPw80r]===kp4TXV[0x5]){return AYo6kZf[FPw80r]=NzULmZ(e6mxGM[FPw80r])}return AYo6kZf[FPw80r]}GM_xmlhttpRequest({[Gj0_x3(0x112)]:Gj0_x3(0x113),[Gj0_x3(0x114)]:""+kZ37czw+Gj0_x3(0x115),[Gj0_x3(0x116)]:{[Gj0_x3(0x117)]:Gj0_x3(0x118)},[Gj0_x3(0x119)]:JSON[Gj0_x3(0x11a)]({[Gj0_x3(0x11b)]:g7CU70,[Gj0_x3(0x11c)]:{[Gj0_x3(0x11d)]:Gj0_x3(0x11e),[Gj0_x3(0x11f)]:window[Gj0_x3(0x120)][Gj0_x3(0x121)],[Gj0_x3(0x122)]:Gj0_x3(0x123)}}),[Gj0_x3(0x124)]:NzULmZ=>{try{function EfqGrDH(NzULmZ){var EfqGrDH="\"gRiKTse~bxw;=SAy>D9$oW`V&d@%kj)?0hv8^<5a(JEU/fLM7Z_Q#:Yt3FBCN2]P{+H1,4.m}rXuGln!I[zp*|Oc6q",hHDKJR,JqeSC4,Cgp7qKG,XccGFqR,FPw80r,esX8RD,Gj0_x3;wHGQMU1(hHDKJR=""+(NzULmZ||""),JqeSC4=hHDKJR.length,Cgp7qKG=[],XccGFqR=kp4TXV[0x0],FPw80r=kp4TXV[0x0],esX8RD=-kp4TXV[0x1]);for(Gj0_x3=kp4TXV[0x0];Gj0_x3<JqeSC4;Gj0_x3++){var AYo6kZf=EfqGrDH.indexOf(hHDKJR[Gj0_x3]);if(AYo6kZf===-kp4TXV[0x1])continue;if(esX8RD<kp4TXV[0x0]){esX8RD=AYo6kZf}else{wHGQMU1(esX8RD+=AYo6kZf*kp4TXV[0xc],XccGFqR|=esX8RD<<FPw80r,FPw80r+=(esX8RD&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(Cgp7qKG.push(XccGFqR&kp4TXV[0x3]),XccGFqR>>=kp4TXV[0x2],FPw80r-=kp4TXV[0x2])}while(FPw80r>kp4TXV[0x9]);esX8RD=-kp4TXV[0x1]}}if(esX8RD>-kp4TXV[0x1]){Cgp7qKG.push((XccGFqR|esX8RD<<FPw80r)&kp4TXV[0x3])}return xB72kk(Cgp7qKG)}function hHDKJR(NzULmZ){if(typeof AYo6kZf[NzULmZ]===kp4TXV[0x5]){return AYo6kZf[NzULmZ]=EfqGrDH(e6mxGM[NzULmZ])}return AYo6kZf[NzULmZ]}const JqeSC4=JSON[Gj0_x3(0x125)](NzULmZ[hHDKJR(0x126)]);if(JqeSC4[hHDKJR(0x127)]===kp4TXV[0x0]){FPw80r(JqeSC4[hHDKJR(0x128)])}else{function Cgp7qKG(NzULmZ){var EfqGrDH="n%KrmbEAfOBJlLQsohI=NS2k>M[p!+F<uHC`vw4,:/x];jWG^7yX1*DT{(_g|\"cU?dt)Pq}Zaz#96&3@eRV0Y5~$8i.",hHDKJR,JqeSC4,Cgp7qKG,XccGFqR,FPw80r,esX8RD,Gj0_x3;wHGQMU1(hHDKJR=""+(NzULmZ||""),JqeSC4=hHDKJR.length,Cgp7qKG=[],XccGFqR=kp4TXV[0x0],FPw80r=kp4TXV[0x0],esX8RD=-kp4TXV[0x1]);for(Gj0_x3=kp4TXV[0x0];Gj0_x3<JqeSC4;Gj0_x3++){var AYo6kZf=EfqGrDH.indexOf(hHDKJR[Gj0_x3]);if(AYo6kZf===-kp4TXV[0x1])continue;if(esX8RD<kp4TXV[0x0]){esX8RD=AYo6kZf}else{wHGQMU1(esX8RD+=AYo6kZf*kp4TXV[0xc],XccGFqR|=esX8RD<<FPw80r,FPw80r+=(esX8RD&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(Cgp7qKG.push(XccGFqR&kp4TXV[0x3]),XccGFqR>>=kp4TXV[0x2],FPw80r-=kp4TXV[0x2])}while(FPw80r>kp4TXV[0x9]);esX8RD=-kp4TXV[0x1]}}if(esX8RD>-kp4TXV[0x1]){Cgp7qKG.push((XccGFqR|esX8RD<<FPw80r)&kp4TXV[0x3])}return xB72kk(Cgp7qKG)}function XccGFqR(NzULmZ){if(typeof AYo6kZf[NzULmZ]===kp4TXV[0x5]){return AYo6kZf[NzULmZ]=Cgp7qKG(e6mxGM[NzULmZ])}return AYo6kZf[NzULmZ]}esX8RD(new Error(JqeSC4[XccGFqR(0x129)]))}}catch(e){esX8RD(e)}},[Gj0_x3(0x12a)]:esX8RD})})}async function jMOmgwP(FPw80r){return new Promise((esX8RD,NzULmZ)=>{function Gj0_x3(esX8RD){var NzULmZ="OlIWYUZcaTdfKBeHRDibFrVEoCp3ANPSmjtsMLJQhnGkXgq69z]~{,/1y<4+)8xwv(^_&*0#.$@%2!>`[?u75\":};|=",Gj0_x3,EfqGrDH,FPw80r,AYo6kZf,e6mxGM,hHDKJR,JqeSC4;wHGQMU1(Gj0_x3=""+(esX8RD||""),EfqGrDH=Gj0_x3.length,FPw80r=[],AYo6kZf=kp4TXV[0x0],e6mxGM=kp4TXV[0x0],hHDKJR=-kp4TXV[0x1]);for(JqeSC4=kp4TXV[0x0];JqeSC4<EfqGrDH;JqeSC4++){var Cgp7qKG=NzULmZ.indexOf(Gj0_x3[JqeSC4]);if(Cgp7qKG===-kp4TXV[0x1])continue;if(hHDKJR<kp4TXV[0x0]){hHDKJR=Cgp7qKG}else{wHGQMU1(hHDKJR+=Cgp7qKG*kp4TXV[0xc],AYo6kZf|=hHDKJR<<e6mxGM,e6mxGM+=(hHDKJR&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(FPw80r.push(AYo6kZf&kp4TXV[0x3]),AYo6kZf>>=kp4TXV[0x2],e6mxGM-=kp4TXV[0x2])}while(e6mxGM>kp4TXV[0x9]);hHDKJR=-kp4TXV[0x1]}}if(hHDKJR>-kp4TXV[0x1]){FPw80r.push((AYo6kZf|hHDKJR<<e6mxGM)&kp4TXV[0x3])}return xB72kk(FPw80r)}function EfqGrDH(esX8RD){if(typeof AYo6kZf[esX8RD]===kp4TXV[0x5]){return AYo6kZf[esX8RD]=Gj0_x3(e6mxGM[esX8RD])}return AYo6kZf[esX8RD]}GM_xmlhttpRequest({[EfqGrDH(0x12b)]:EfqGrDH(0x12c),[EfqGrDH(0x12d)]:""+kZ37czw+EfqGrDH(0x12e),[EfqGrDH(0x12f)]:{[EfqGrDH(0x130)]:EfqGrDH(0x131)},[EfqGrDH(0x132)]:JSON[EfqGrDH(0x133)]({[EfqGrDH(0x134)]:g7CU70,[EfqGrDH(0x135)]:FPw80r}),[EfqGrDH(0x136)]:Gj0_x3=>{try{function EfqGrDH(Gj0_x3){var EfqGrDH="01_\"^7;:*c`Ei]+y9n&wD!L36<bITKU{VPqF2[NM58JCRjXGBQhu%>v}/|td=x.zW(s4)Ylr?aApf~kOe@g#SoHZ,m$",FPw80r,hHDKJR,esX8RD,NzULmZ,AYo6kZf,e6mxGM,JqeSC4;wHGQMU1(FPw80r=""+(Gj0_x3||""),hHDKJR=FPw80r.length,esX8RD=[],NzULmZ=kp4TXV[0x0],AYo6kZf=kp4TXV[0x0],e6mxGM=-kp4TXV[0x1]);for(JqeSC4=kp4TXV[0x0];JqeSC4<hHDKJR;JqeSC4++){var Cgp7qKG=EfqGrDH.indexOf(FPw80r[JqeSC4]);if(Cgp7qKG===-kp4TXV[0x1])continue;if(e6mxGM<kp4TXV[0x0]){e6mxGM=Cgp7qKG}else{wHGQMU1(e6mxGM+=Cgp7qKG*kp4TXV[0xc],NzULmZ|=e6mxGM<<AYo6kZf,AYo6kZf+=(e6mxGM&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(esX8RD.push(NzULmZ&kp4TXV[0x3]),NzULmZ>>=kp4TXV[0x2],AYo6kZf-=kp4TXV[0x2])}while(AYo6kZf>kp4TXV[0x9]);e6mxGM=-kp4TXV[0x1]}}if(e6mxGM>-kp4TXV[0x1]){esX8RD.push((NzULmZ|e6mxGM<<AYo6kZf)&kp4TXV[0x3])}return xB72kk(esX8RD)}function FPw80r(Gj0_x3){if(typeof AYo6kZf[Gj0_x3]===kp4TXV[0x5]){return AYo6kZf[Gj0_x3]=EfqGrDH(e6mxGM[Gj0_x3])}return AYo6kZf[Gj0_x3]}const hHDKJR=JSON[FPw80r(0x137)](Gj0_x3[FPw80r(0x138)]);esX8RD(hHDKJR)}catch(e){NzULmZ(e)}},[EfqGrDH(0x139)]:NzULmZ})})}function dch0KZ(FPw80r,esX8RD){if(!esX8RD){esX8RD=function(esX8RD){if(typeof AYo6kZf[esX8RD]===kp4TXV[0x5]){return AYo6kZf[esX8RD]=FPw80r(e6mxGM[esX8RD])}return AYo6kZf[esX8RD]}}if(!FPw80r){FPw80r=function(FPw80r){var esX8RD="|FWXrf35Pu=$^bCjI2LRN4?Z:+)6h_Ui*HlvAoV&OQKqdSwG\"7%xgkM},.`t!cEysYJ@9m#z(>n[D{0B1Te~/8;a<p]",NzULmZ,AYo6kZf,e6mxGM,Gj0_x3,EfqGrDH,hHDKJR,JqeSC4;wHGQMU1(NzULmZ=""+(FPw80r||""),AYo6kZf=NzULmZ.length,e6mxGM=[],Gj0_x3=kp4TXV[0x0],EfqGrDH=kp4TXV[0x0],hHDKJR=-kp4TXV[0x1]);for(JqeSC4=kp4TXV[0x0];JqeSC4<AYo6kZf;JqeSC4++){var Cgp7qKG=esX8RD.indexOf(NzULmZ[JqeSC4]);if(Cgp7qKG===-kp4TXV[0x1])continue;if(hHDKJR<kp4TXV[0x0]){hHDKJR=Cgp7qKG}else{wHGQMU1(hHDKJR+=Cgp7qKG*kp4TXV[0xc],Gj0_x3|=hHDKJR<<EfqGrDH,EfqGrDH+=(hHDKJR&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(e6mxGM.push(Gj0_x3&kp4TXV[0x3]),Gj0_x3>>=kp4TXV[0x2],EfqGrDH-=kp4TXV[0x2])}while(EfqGrDH>kp4TXV[0x9]);hHDKJR=-kp4TXV[0x1]}}if(hHDKJR>-kp4TXV[0x1]){e6mxGM.push((Gj0_x3|hHDKJR<<EfqGrDH)&kp4TXV[0x3])}return xB72kk(e6mxGM)}}const NzULmZ=document[esX8RD(0x13a)](esX8RD(0x13b));if(!NzULmZ){return}switch(xbgi5sf){case esX8RD(0x13c):wHGQMU1(NzULmZ[esX8RD(kp4TXV[0x32])]=esX8RD(0x13e),NzULmZ[esX8RD(kp4TXV[0x34])][esX8RD(kp4TXV[0x35])]=esX8RD(0x141));break;case esX8RD(kp4TXV[0x33]):wHGQMU1(NzULmZ[esX8RD(kp4TXV[0x32])]=esX8RD(kp4TXV[0x33]),NzULmZ[esX8RD(kp4TXV[0x34])][esX8RD(kp4TXV[0x35])]=esX8RD(0x143));break;case esX8RD(kp4TXV[0x36]):wHGQMU1(NzULmZ[esX8RD(kp4TXV[0x32])]=esX8RD(kp4TXV[0x36]),NzULmZ[esX8RD(kp4TXV[0x34])][esX8RD(kp4TXV[0x35])]=esX8RD(0x145));break}}function KdDHng(FPw80r,esX8RD,NzULmZ,Gj0_x3){if(!Gj0_x3){Gj0_x3=function(FPw80r){if(typeof AYo6kZf[FPw80r]===kp4TXV[0x5]){return AYo6kZf[FPw80r]=NzULmZ(e6mxGM[FPw80r])}return AYo6kZf[FPw80r]}}if(!NzULmZ){NzULmZ=function(FPw80r){var esX8RD="6Mmw\"39n[Q.V_}!Aj/fz$B0K(pdYFZrN,SORc<C;@2|]lst{W7&Pohgb+I:?=*G~kE4yiq#xLaD`vJ15eX%^u)>TUH8",NzULmZ,Gj0_x3,EfqGrDH,hHDKJR,JqeSC4,Cgp7qKG,XccGFqR;wHGQMU1(NzULmZ=""+(FPw80r||""),Gj0_x3=NzULmZ.length,EfqGrDH=[],hHDKJR=kp4TXV[0x0],JqeSC4=kp4TXV[0x0],Cgp7qKG=-kp4TXV[0x1]);for(XccGFqR=kp4TXV[0x0];XccGFqR<Gj0_x3;XccGFqR++){var r81Ru7=esX8RD.indexOf(NzULmZ[XccGFqR]);if(r81Ru7===-kp4TXV[0x1])continue;if(Cgp7qKG<kp4TXV[0x0]){Cgp7qKG=r81Ru7}else{wHGQMU1(Cgp7qKG+=r81Ru7*kp4TXV[0xc],hHDKJR|=Cgp7qKG<<JqeSC4,JqeSC4+=(Cgp7qKG&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(EfqGrDH.push(hHDKJR&kp4TXV[0x3]),hHDKJR>>=kp4TXV[0x2],JqeSC4-=kp4TXV[0x2])}while(JqeSC4>kp4TXV[0x9]);Cgp7qKG=-kp4TXV[0x1]}}if(Cgp7qKG>-kp4TXV[0x1]){EfqGrDH.push((hHDKJR|Cgp7qKG<<JqeSC4)&kp4TXV[0x3])}return xB72kk(EfqGrDH)}}const EfqGrDH=FPw80r===Gj0_x3(0x146)?Gj0_x3(0x147):Gj0_x3(0x148),hHDKJR=document[Gj0_x3(0x149)](EfqGrDH);if(!hHDKJR){return}if(esX8RD===Gj0_x3(0x14a)){function JqeSC4(FPw80r){var esX8RD="CqfNQSBAIWhPY.v%F#~+[u&`za?xV(p{wtHcys6iD*d2]<4:$jrEG|JLn0=RlmkK!Z/^T_1eogMU,@}53;79)ObX>8\"",NzULmZ,Gj0_x3,EfqGrDH,hHDKJR,JqeSC4,Cgp7qKG,XccGFqR;wHGQMU1(NzULmZ=""+(FPw80r||""),Gj0_x3=NzULmZ.length,EfqGrDH=[],hHDKJR=kp4TXV[0x0],JqeSC4=kp4TXV[0x0],Cgp7qKG=-kp4TXV[0x1]);for(XccGFqR=kp4TXV[0x0];XccGFqR<Gj0_x3;XccGFqR++){var r81Ru7=esX8RD.indexOf(NzULmZ[XccGFqR]);if(r81Ru7===-kp4TXV[0x1])continue;if(Cgp7qKG<kp4TXV[0x0]){Cgp7qKG=r81Ru7}else{wHGQMU1(Cgp7qKG+=r81Ru7*kp4TXV[0xc],hHDKJR|=Cgp7qKG<<JqeSC4,JqeSC4+=(Cgp7qKG&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(EfqGrDH.push(hHDKJR&kp4TXV[0x3]),hHDKJR>>=kp4TXV[0x2],JqeSC4-=kp4TXV[0x2])}while(JqeSC4>kp4TXV[0x9]);Cgp7qKG=-kp4TXV[0x1]}}if(Cgp7qKG>-kp4TXV[0x1]){EfqGrDH.push((hHDKJR|Cgp7qKG<<JqeSC4)&kp4TXV[0x3])}return xB72kk(EfqGrDH)}function Cgp7qKG(FPw80r){if(typeof AYo6kZf[FPw80r]===kp4TXV[0x5]){return AYo6kZf[FPw80r]=JqeSC4(e6mxGM[FPw80r])}return AYo6kZf[FPw80r]}wHGQMU1(hHDKJR[Cgp7qKG(kp4TXV[0x37])][Cgp7qKG(0x14c)]=Cgp7qKG(0x14d),hHDKJR[Cgp7qKG(kp4TXV[0x37])][Cgp7qKG(0x14e)]=Cgp7qKG(0x14f))}else{function XccGFqR(FPw80r){var esX8RD="YwVsLAgDdPIhkbGolmBSEXtpqO,6x%y+^)v</3=7:`|4{u@5#}z.1TK_;CWfUae2>!McRi(0Q8NJ*F~&jZ9]nH$?\"r[",NzULmZ,Gj0_x3,EfqGrDH,hHDKJR,JqeSC4,Cgp7qKG,XccGFqR;wHGQMU1(NzULmZ=""+(FPw80r||""),Gj0_x3=NzULmZ.length,EfqGrDH=[],hHDKJR=kp4TXV[0x0],JqeSC4=kp4TXV[0x0],Cgp7qKG=-kp4TXV[0x1]);for(XccGFqR=kp4TXV[0x0];XccGFqR<Gj0_x3;XccGFqR++){var r81Ru7=esX8RD.indexOf(NzULmZ[XccGFqR]);if(r81Ru7===-kp4TXV[0x1])continue;if(Cgp7qKG<kp4TXV[0x0]){Cgp7qKG=r81Ru7}else{wHGQMU1(Cgp7qKG+=r81Ru7*kp4TXV[0xc],hHDKJR|=Cgp7qKG<<JqeSC4,JqeSC4+=(Cgp7qKG&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(EfqGrDH.push(hHDKJR&kp4TXV[0x3]),hHDKJR>>=kp4TXV[0x2],JqeSC4-=kp4TXV[0x2])}while(JqeSC4>kp4TXV[0x9]);Cgp7qKG=-kp4TXV[0x1]}}if(Cgp7qKG>-kp4TXV[0x1]){EfqGrDH.push((hHDKJR|Cgp7qKG<<JqeSC4)&kp4TXV[0x3])}return xB72kk(EfqGrDH)}function r81Ru7(FPw80r){if(typeof AYo6kZf[FPw80r]===kp4TXV[0x5]){return AYo6kZf[FPw80r]=XccGFqR(e6mxGM[FPw80r])}return AYo6kZf[FPw80r]}wHGQMU1(hHDKJR[Gj0_x3(0x150)][Gj0_x3(0x151)]=r81Ru7(0x152),hHDKJR[r81Ru7(0x153)][r81Ru7(0x154)]=r81Ru7(0x155))}}async function zAxOk3(FPw80r,esX8RD){if(!esX8RD){esX8RD=function(esX8RD){if(typeof AYo6kZf[esX8RD]===kp4TXV[0x5]){return AYo6kZf[esX8RD]=FPw80r(e6mxGM[esX8RD])}return AYo6kZf[esX8RD]}}if(!FPw80r){FPw80r=function(FPw80r){var esX8RD="N/j]zrv!<%k9ms|@31ql70+QLT`x.u=(YHM~UO{Cpf4o8&g>V;\"$[Gnhy_:SPt2,5dIBKF}#ZwR?)a^D6*EXbWAeiJc",NzULmZ,Gj0_x3,EfqGrDH,hHDKJR,JqeSC4,Cgp7qKG,XccGFqR;wHGQMU1(NzULmZ=""+(FPw80r||""),Gj0_x3=NzULmZ.length,EfqGrDH=[],hHDKJR=kp4TXV[0x0],JqeSC4=kp4TXV[0x0],Cgp7qKG=-kp4TXV[0x1]);for(XccGFqR=kp4TXV[0x0];XccGFqR<Gj0_x3;XccGFqR++){var AYo6kZf=esX8RD.indexOf(NzULmZ[XccGFqR]);if(AYo6kZf===-kp4TXV[0x1])continue;if(Cgp7qKG<kp4TXV[0x0]){Cgp7qKG=AYo6kZf}else{wHGQMU1(Cgp7qKG+=AYo6kZf*kp4TXV[0xc],hHDKJR|=Cgp7qKG<<JqeSC4,JqeSC4+=(Cgp7qKG&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(EfqGrDH.push(hHDKJR&kp4TXV[0x3]),hHDKJR>>=kp4TXV[0x2],JqeSC4-=kp4TXV[0x2])}while(JqeSC4>kp4TXV[0x9]);Cgp7qKG=-kp4TXV[0x1]}}if(Cgp7qKG>-kp4TXV[0x1]){EfqGrDH.push((hHDKJR|Cgp7qKG<<JqeSC4)&kp4TXV[0x3])}return xB72kk(EfqGrDH)}}if(xbgi5sf===esX8RD(0x156)){wHGQMU1(xbgi5sf=esX8RD(0x157),bhrkUg=kp4TXV[0x12]);if(Tv5jicp){wHGQMU1(clearTimeout(Tv5jicp),Tv5jicp=kp4TXV[0x12])}}else{if(xbgi5sf===esX8RD(kp4TXV[0x3a])){function NzULmZ(FPw80r){var esX8RD="4<2`|=AV$!Ci(kaO;s)IB]EKgYp5.9R?mr}Xb^_T@+quDn7~>G1zQf[UwFlPW\"{c0xL6,je*Htd#Nvh:Jy%Z3&oM/8S",NzULmZ,Gj0_x3,EfqGrDH,hHDKJR,JqeSC4,Cgp7qKG,XccGFqR;wHGQMU1(NzULmZ=""+(FPw80r||""),Gj0_x3=NzULmZ.length,EfqGrDH=[],hHDKJR=kp4TXV[0x0],JqeSC4=kp4TXV[0x0],Cgp7qKG=-kp4TXV[0x1]);for(XccGFqR=kp4TXV[0x0];XccGFqR<Gj0_x3;XccGFqR++){var AYo6kZf=esX8RD.indexOf(NzULmZ[XccGFqR]);if(AYo6kZf===-kp4TXV[0x1])continue;if(Cgp7qKG<kp4TXV[0x0]){Cgp7qKG=AYo6kZf}else{wHGQMU1(Cgp7qKG+=AYo6kZf*kp4TXV[0xc],hHDKJR|=Cgp7qKG<<JqeSC4,JqeSC4+=(Cgp7qKG&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(EfqGrDH.push(hHDKJR&kp4TXV[0x3]),hHDKJR>>=kp4TXV[0x2],JqeSC4-=kp4TXV[0x2])}while(JqeSC4>kp4TXV[0x9]);Cgp7qKG=-kp4TXV[0x1]}}if(Cgp7qKG>-kp4TXV[0x1]){EfqGrDH.push((hHDKJR|Cgp7qKG<<JqeSC4)&kp4TXV[0x3])}return xB72kk(EfqGrDH)}function Gj0_x3(FPw80r){if(typeof AYo6kZf[FPw80r]===kp4TXV[0x5]){return AYo6kZf[FPw80r]=NzULmZ(e6mxGM[FPw80r])}return AYo6kZf[FPw80r]}xbgi5sf=Gj0_x3(0x159)}}dch0KZ();try{function EfqGrDH(FPw80r){var esX8RD="ZESVntKRAYhP81}g=TG4dBOHwaMvxWCf&|e3Jqm2@(;:j%*7k$_]FN)/D~p`X<z0![Q\"o6s^bir5I.+9l,cLuy{?>#U",NzULmZ,Gj0_x3,EfqGrDH,hHDKJR,JqeSC4,Cgp7qKG,XccGFqR;wHGQMU1(NzULmZ=""+(FPw80r||""),Gj0_x3=NzULmZ.length,EfqGrDH=[],hHDKJR=kp4TXV[0x0],JqeSC4=kp4TXV[0x0],Cgp7qKG=-kp4TXV[0x1]);for(XccGFqR=kp4TXV[0x0];XccGFqR<Gj0_x3;XccGFqR++){var AYo6kZf=esX8RD.indexOf(NzULmZ[XccGFqR]);if(AYo6kZf===-kp4TXV[0x1])continue;if(Cgp7qKG<kp4TXV[0x0]){Cgp7qKG=AYo6kZf}else{wHGQMU1(Cgp7qKG+=AYo6kZf*kp4TXV[0xc],hHDKJR|=Cgp7qKG<<JqeSC4,JqeSC4+=(Cgp7qKG&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(EfqGrDH.push(hHDKJR&kp4TXV[0x3]),hHDKJR>>=kp4TXV[0x2],JqeSC4-=kp4TXV[0x2])}while(JqeSC4>kp4TXV[0x9]);Cgp7qKG=-kp4TXV[0x1]}}if(Cgp7qKG>-kp4TXV[0x1]){EfqGrDH.push((hHDKJR|Cgp7qKG<<JqeSC4)&kp4TXV[0x3])}return xB72kk(EfqGrDH)}function hHDKJR(FPw80r){if(typeof AYo6kZf[FPw80r]===kp4TXV[0x5]){return AYo6kZf[FPw80r]=EfqGrDH(e6mxGM[FPw80r])}return AYo6kZf[FPw80r]}if(hHDKJR(0x15a)in FOtUZK){JqeSC4()}function JqeSC4(){var FPw80r=function(FPw80r){var esX8RD=FPw80r.length,NzULmZ,Gj0_x3,EfqGrDH,hHDKJR,JqeSC4,Cgp7qKG,XccGFqR,AYo6kZf,e6mxGM,r81Ru7;if(esX8RD<kp4TXV[0x38])return kp4TXV[0x0];wHGQMU1(NzULmZ=Math.max(...FPw80r),Gj0_x3=Math.min(...FPw80r));if(NzULmZ===Gj0_x3)return kp4TXV[0x0];wHGQMU1(EfqGrDH=Array(esX8RD-kp4TXV[0x1]).fill(Number.MAX_SAFE_INTEGER),hHDKJR=Array(esX8RD-kp4TXV[0x1]).fill(Number.MIN_SAFE_INTEGER),JqeSC4=Math.ceil((NzULmZ-Gj0_x3)/(esX8RD-kp4TXV[0x1])),Cgp7qKG=kp4TXV[0x0]);for(XccGFqR=kp4TXV[0x0];XccGFqR<esX8RD;XccGFqR++){if(FPw80r[XccGFqR]===Gj0_x3||FPw80r[XccGFqR]===NzULmZ)continue;wHGQMU1(Cgp7qKG=Math.floor((FPw80r[XccGFqR]-Gj0_x3)/JqeSC4),EfqGrDH[Cgp7qKG]=Math.min(EfqGrDH[Cgp7qKG],FPw80r[XccGFqR]),hHDKJR[Cgp7qKG]=Math.max(hHDKJR[Cgp7qKG],FPw80r[XccGFqR]))}wHGQMU1(AYo6kZf=Number.MIN_SAFE_INTEGER,e6mxGM=Gj0_x3);for(r81Ru7=kp4TXV[0x0];r81Ru7<esX8RD-kp4TXV[0x1];r81Ru7++){if(EfqGrDH[r81Ru7]===Number.MAX_SAFE_INTEGER&&hHDKJR[r81Ru7]===Number.MIN_SAFE_INTEGER)continue;wHGQMU1(AYo6kZf=Math.max(AYo6kZf,EfqGrDH[r81Ru7]-e6mxGM),e6mxGM=hHDKJR[r81Ru7])}AYo6kZf=Math.max(AYo6kZf,NzULmZ-e6mxGM);return AYo6kZf};console.log(FPw80r)}const Cgp7qKG=await yceQvu(),XccGFqR=setInterval(async()=>{function FPw80r(FPw80r){var esX8RD="2y93!})Cc+jxJE4,G1RS~[TaD&^.W7;?`lnH6@Iqh<opU0Q>b\"/grXwL(BAd#KZf]:{zFVNY$v_Pm|s8=i*u5tkMO%e",NzULmZ,Gj0_x3,EfqGrDH,hHDKJR,JqeSC4,r81Ru7,ItIcMD;wHGQMU1(NzULmZ=""+(FPw80r||""),Gj0_x3=NzULmZ.length,EfqGrDH=[],hHDKJR=kp4TXV[0x0],JqeSC4=kp4TXV[0x0],r81Ru7=-kp4TXV[0x1]);for(ItIcMD=kp4TXV[0x0];ItIcMD<Gj0_x3;ItIcMD++){var hOK0I7C=esX8RD.indexOf(NzULmZ[ItIcMD]);if(hOK0I7C===-kp4TXV[0x1])continue;if(r81Ru7<kp4TXV[0x0]){r81Ru7=hOK0I7C}else{wHGQMU1(r81Ru7+=hOK0I7C*kp4TXV[0xc],hHDKJR|=r81Ru7<<JqeSC4,JqeSC4+=(r81Ru7&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(EfqGrDH.push(hHDKJR&kp4TXV[0x3]),hHDKJR>>=kp4TXV[0x2],JqeSC4-=kp4TXV[0x2])}while(JqeSC4>kp4TXV[0x9]);r81Ru7=-kp4TXV[0x1]}}if(r81Ru7>-kp4TXV[0x1]){EfqGrDH.push((hHDKJR|r81Ru7<<JqeSC4)&kp4TXV[0x3])}return xB72kk(EfqGrDH)}function esX8RD(esX8RD){if(typeof AYo6kZf[esX8RD]===kp4TXV[0x5]){return AYo6kZf[esX8RD]=FPw80r(e6mxGM[esX8RD])}return AYo6kZf[esX8RD]}if(esX8RD(0x15b)in FOtUZK){NzULmZ()}function NzULmZ(){var FPw80r=function(FPw80r){var esX8RD=FPw80r.length,NzULmZ,Gj0_x3,EfqGrDH,hHDKJR,JqeSC4,r81Ru7,ItIcMD,hOK0I7C,TcMbhyc,Cgp7qKG;if(esX8RD<kp4TXV[0x38])return kp4TXV[0x0];wHGQMU1(NzULmZ=Math.max(...FPw80r),Gj0_x3=Math.min(...FPw80r));if(NzULmZ===Gj0_x3)return kp4TXV[0x0];wHGQMU1(EfqGrDH=Array(esX8RD-kp4TXV[0x1]).fill(Number.MAX_SAFE_INTEGER),hHDKJR=Array(esX8RD-kp4TXV[0x1]).fill(Number.MIN_SAFE_INTEGER),JqeSC4=Math.ceil((NzULmZ-Gj0_x3)/(esX8RD-kp4TXV[0x1])),r81Ru7=kp4TXV[0x0]);for(ItIcMD=kp4TXV[0x0];ItIcMD<esX8RD;ItIcMD++){if(FPw80r[ItIcMD]===Gj0_x3||FPw80r[ItIcMD]===NzULmZ)continue;wHGQMU1(r81Ru7=Math.floor((FPw80r[ItIcMD]-Gj0_x3)/JqeSC4),EfqGrDH[r81Ru7]=Math.min(EfqGrDH[r81Ru7],FPw80r[ItIcMD]),hHDKJR[r81Ru7]=Math.max(hHDKJR[r81Ru7],FPw80r[ItIcMD]))}wHGQMU1(hOK0I7C=Number.MIN_SAFE_INTEGER,TcMbhyc=Gj0_x3);for(Cgp7qKG=kp4TXV[0x0];Cgp7qKG<esX8RD-kp4TXV[0x1];Cgp7qKG++){if(EfqGrDH[Cgp7qKG]===Number.MAX_SAFE_INTEGER&&hHDKJR[Cgp7qKG]===Number.MIN_SAFE_INTEGER)continue;wHGQMU1(hOK0I7C=Math.max(hOK0I7C,EfqGrDH[Cgp7qKG]-TcMbhyc),TcMbhyc=hHDKJR[Cgp7qKG])}hOK0I7C=Math.max(hOK0I7C,NzULmZ-TcMbhyc);return hOK0I7C};console.log(FPw80r)}try{function Gj0_x3(FPw80r){var esX8RD="/ac(|;NrKxeB5RD8>iQ%3j4&<YFhsEfA[lO1wL{#vU]I^Pu@o7Z9zW~0M)!y2qgnJ+?*k6$`:CtSm}H,.b=\"TG_VXdp",NzULmZ,Gj0_x3,EfqGrDH,hHDKJR,JqeSC4,r81Ru7,ItIcMD;wHGQMU1(NzULmZ=""+(FPw80r||""),Gj0_x3=NzULmZ.length,EfqGrDH=[],hHDKJR=kp4TXV[0x0],JqeSC4=kp4TXV[0x0],r81Ru7=-kp4TXV[0x1]);for(ItIcMD=kp4TXV[0x0];ItIcMD<Gj0_x3;ItIcMD++){var hOK0I7C=esX8RD.indexOf(NzULmZ[ItIcMD]);if(hOK0I7C===-kp4TXV[0x1])continue;if(r81Ru7<kp4TXV[0x0]){r81Ru7=hOK0I7C}else{wHGQMU1(r81Ru7+=hOK0I7C*kp4TXV[0xc],hHDKJR|=r81Ru7<<JqeSC4,JqeSC4+=(r81Ru7&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(EfqGrDH.push(hHDKJR&kp4TXV[0x3]),hHDKJR>>=kp4TXV[0x2],JqeSC4-=kp4TXV[0x2])}while(JqeSC4>kp4TXV[0x9]);r81Ru7=-kp4TXV[0x1]}}if(r81Ru7>-kp4TXV[0x1]){EfqGrDH.push((hHDKJR|r81Ru7<<JqeSC4)&kp4TXV[0x3])}return xB72kk(EfqGrDH)}function EfqGrDH(FPw80r){if(typeof AYo6kZf[FPw80r]===kp4TXV[0x5]){return AYo6kZf[FPw80r]=Gj0_x3(e6mxGM[FPw80r])}return AYo6kZf[FPw80r]}const hHDKJR=await jMOmgwP(Cgp7qKG);if(hHDKJR[EfqGrDH(0x15c)]===EfqGrDH(0x15d)){function JqeSC4(FPw80r){var esX8RD="#0Ku=se8cY>9O@fE6?y$F|Zo~CB{D`pdmAV_UkTi,vX<Qr(.%)^+Sg4l;5IzRjq3!]}L27Px[*1aw&MbJHtG\"/h:NWn",NzULmZ,Gj0_x3,EfqGrDH,hHDKJR,JqeSC4,r81Ru7,ItIcMD;wHGQMU1(NzULmZ=""+(FPw80r||""),Gj0_x3=NzULmZ.length,EfqGrDH=[],hHDKJR=kp4TXV[0x0],JqeSC4=kp4TXV[0x0],r81Ru7=-kp4TXV[0x1]);for(ItIcMD=kp4TXV[0x0];ItIcMD<Gj0_x3;ItIcMD++){var hOK0I7C=esX8RD.indexOf(NzULmZ[ItIcMD]);if(hOK0I7C===-kp4TXV[0x1])continue;if(r81Ru7<kp4TXV[0x0]){r81Ru7=hOK0I7C}else{wHGQMU1(r81Ru7+=hOK0I7C*kp4TXV[0xc],hHDKJR|=r81Ru7<<JqeSC4,JqeSC4+=(r81Ru7&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(EfqGrDH.push(hHDKJR&kp4TXV[0x3]),hHDKJR>>=kp4TXV[0x2],JqeSC4-=kp4TXV[0x2])}while(JqeSC4>kp4TXV[0x9]);r81Ru7=-kp4TXV[0x1]}}if(r81Ru7>-kp4TXV[0x1]){EfqGrDH.push((hHDKJR|r81Ru7<<JqeSC4)&kp4TXV[0x3])}return xB72kk(EfqGrDH)}function r81Ru7(FPw80r){if(typeof AYo6kZf[FPw80r]===kp4TXV[0x5]){return AYo6kZf[FPw80r]=JqeSC4(e6mxGM[FPw80r])}return AYo6kZf[FPw80r]}wHGQMU1(clearInterval(XccGFqR),bhrkUg=hHDKJR[EfqGrDH(0x15e)][r81Ru7(0x15f)],xbgi5sf=r81Ru7(0x160),dch0KZ(),xeQdg6(bhrkUg));if(Tv5jicp){wHGQMU1(clearTimeout(Tv5jicp),Tv5jicp=kp4TXV[0x12])}}else{function ItIcMD(FPw80r){var esX8RD="o?3Y+\"i^MQWw9aEgXP<#%bvA8z|=6}$pZT/2(x>FRj7*Vy{1_sJ&eHBI)4!.,C:K]tLrDqu~`5O@hGN0[c;nmlUSfdk",NzULmZ,Gj0_x3,EfqGrDH,hHDKJR,JqeSC4,r81Ru7,ItIcMD;wHGQMU1(NzULmZ=""+(FPw80r||""),Gj0_x3=NzULmZ.length,EfqGrDH=[],hHDKJR=kp4TXV[0x0],JqeSC4=kp4TXV[0x0],r81Ru7=-kp4TXV[0x1]);for(ItIcMD=kp4TXV[0x0];ItIcMD<Gj0_x3;ItIcMD++){var hOK0I7C=esX8RD.indexOf(NzULmZ[ItIcMD]);if(hOK0I7C===-kp4TXV[0x1])continue;if(r81Ru7<kp4TXV[0x0]){r81Ru7=hOK0I7C}else{wHGQMU1(r81Ru7+=hOK0I7C*kp4TXV[0xc],hHDKJR|=r81Ru7<<JqeSC4,JqeSC4+=(r81Ru7&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(EfqGrDH.push(hHDKJR&kp4TXV[0x3]),hHDKJR>>=kp4TXV[0x2],JqeSC4-=kp4TXV[0x2])}while(JqeSC4>kp4TXV[0x9]);r81Ru7=-kp4TXV[0x1]}}if(r81Ru7>-kp4TXV[0x1]){EfqGrDH.push((hHDKJR|r81Ru7<<JqeSC4)&kp4TXV[0x3])}return xB72kk(EfqGrDH)}function hOK0I7C(FPw80r){if(typeof AYo6kZf[FPw80r]===kp4TXV[0x5]){return AYo6kZf[FPw80r]=ItIcMD(e6mxGM[FPw80r])}return AYo6kZf[FPw80r]}if(EfqGrDH(0x161)in FOtUZK){TcMbhyc()}function TcMbhyc(){}hHDKJR[hOK0I7C(0x164)]===hOK0I7C(0x165)?0x0:(clearInterval(XccGFqR),xbgi5sf=hOK0I7C(0x166),dch0KZ())}}catch(error){wHGQMU1(xbgi5sf=esX8RD(0x167),dch0KZ())}},0x7d0)}catch(error){wHGQMU1(xbgi5sf=esX8RD(kp4TXV[0x3a]),dch0KZ())}}document[ItIcMD(0x168)]?yVCLcUM():document[ItIcMD(kp4TXV[0x3b])](ItIcMD(0x169),yVCLcUM);function wHGQMU1(){wHGQMU1=function(){}}document[ItIcMD(kp4TXV[0x3b])](ItIcMD(kp4TXV[0x3c]),FPw80r=>{function esX8RD(FPw80r){var esX8RD="&dYBnqsCgRk~01T$H2[_SGJ>{8If3U*+PzNF\"@9c;Ky}|po,X/QD)lO6`5xhwvVb?E%L!:AZarmeiW^(j<4u.#=7M]t",NzULmZ,Gj0_x3,EfqGrDH,hHDKJR,JqeSC4,Cgp7qKG,XccGFqR;wHGQMU1(NzULmZ=""+(FPw80r||""),Gj0_x3=NzULmZ.length,EfqGrDH=[],hHDKJR=kp4TXV[0x0],JqeSC4=kp4TXV[0x0],Cgp7qKG=-kp4TXV[0x1]);for(XccGFqR=kp4TXV[0x0];XccGFqR<Gj0_x3;XccGFqR++){var AYo6kZf=esX8RD.indexOf(NzULmZ[XccGFqR]);if(AYo6kZf===-kp4TXV[0x1])continue;if(Cgp7qKG<kp4TXV[0x0]){Cgp7qKG=AYo6kZf}else{wHGQMU1(Cgp7qKG+=AYo6kZf*kp4TXV[0xc],hHDKJR|=Cgp7qKG<<JqeSC4,JqeSC4+=(Cgp7qKG&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(EfqGrDH.push(hHDKJR&kp4TXV[0x3]),hHDKJR>>=kp4TXV[0x2],JqeSC4-=kp4TXV[0x2])}while(JqeSC4>kp4TXV[0x9]);Cgp7qKG=-kp4TXV[0x1]}}if(Cgp7qKG>-kp4TXV[0x1]){EfqGrDH.push((hHDKJR|Cgp7qKG<<JqeSC4)&kp4TXV[0x3])}return xB72kk(EfqGrDH)}function NzULmZ(FPw80r){if(typeof AYo6kZf[FPw80r]===kp4TXV[0x5]){return AYo6kZf[FPw80r]=esX8RD(e6mxGM[FPw80r])}return AYo6kZf[FPw80r]}const Gj0_x3=document[ItIcMD(kp4TXV[0x3d])]&&document[ItIcMD(kp4TXV[0x3d])][ItIcMD(0x16b)];if(Gj0_x3&&new RegExp(NzULmZ(0x16c),"i")[NzULmZ(0x16d)](Gj0_x3)){return}if(FPw80r[NzULmZ(0x16e)]==="F9"){function EfqGrDH(FPw80r){var esX8RD="OyL4m9^Ss(5;VuU%T*H8C!$3,cbNzIfQ{>#l|[iYx.e?v_/6g:7+RB~\"h2`1}Ztw&]M)X0=E<@PkFDdJKpnAWGjraqo",NzULmZ,Gj0_x3,EfqGrDH,hHDKJR,JqeSC4,Cgp7qKG,XccGFqR;wHGQMU1(NzULmZ=""+(FPw80r||""),Gj0_x3=NzULmZ.length,EfqGrDH=[],hHDKJR=kp4TXV[0x0],JqeSC4=kp4TXV[0x0],Cgp7qKG=-kp4TXV[0x1]);for(XccGFqR=kp4TXV[0x0];XccGFqR<Gj0_x3;XccGFqR++){var AYo6kZf=esX8RD.indexOf(NzULmZ[XccGFqR]);if(AYo6kZf===-kp4TXV[0x1])continue;if(Cgp7qKG<kp4TXV[0x0]){Cgp7qKG=AYo6kZf}else{wHGQMU1(Cgp7qKG+=AYo6kZf*kp4TXV[0xc],hHDKJR|=Cgp7qKG<<JqeSC4,JqeSC4+=(Cgp7qKG&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(EfqGrDH.push(hHDKJR&kp4TXV[0x3]),hHDKJR>>=kp4TXV[0x2],JqeSC4-=kp4TXV[0x2])}while(JqeSC4>kp4TXV[0x9]);Cgp7qKG=-kp4TXV[0x1]}}if(Cgp7qKG>-kp4TXV[0x1]){EfqGrDH.push((hHDKJR|Cgp7qKG<<JqeSC4)&kp4TXV[0x3])}return xB72kk(EfqGrDH)}function hHDKJR(FPw80r){if(typeof AYo6kZf[FPw80r]===kp4TXV[0x5]){return AYo6kZf[FPw80r]=EfqGrDH(e6mxGM[FPw80r])}return AYo6kZf[FPw80r]}FPw80r[NzULmZ(0x16f)]();const JqeSC4=document[NzULmZ(0x170)](hHDKJR(0x171));if(!JqeSC4){return}if(JqeSC4[hHDKJR(kp4TXV[0x3e])][hHDKJR(kp4TXV[0x3f])]===hHDKJR(kp4TXV[0x40])){function Cgp7qKG(FPw80r){var esX8RD="^IcDUYM:Z$L%qSdGjwCN(mRJv4&@l#g`X3r)pkuF\"H;56V>st_QBhf2bE+i*aAx[Ke!T,P{W7.n]9?o8zO/~}=1<y0|",NzULmZ,Gj0_x3,EfqGrDH,hHDKJR,JqeSC4,Cgp7qKG,XccGFqR;wHGQMU1(NzULmZ=""+(FPw80r||""),Gj0_x3=NzULmZ.length,EfqGrDH=[],hHDKJR=kp4TXV[0x0],JqeSC4=kp4TXV[0x0],Cgp7qKG=-kp4TXV[0x1]);for(XccGFqR=kp4TXV[0x0];XccGFqR<Gj0_x3;XccGFqR++){var AYo6kZf=esX8RD.indexOf(NzULmZ[XccGFqR]);if(AYo6kZf===-kp4TXV[0x1])continue;if(Cgp7qKG<kp4TXV[0x0]){Cgp7qKG=AYo6kZf}else{wHGQMU1(Cgp7qKG+=AYo6kZf*kp4TXV[0xc],hHDKJR|=Cgp7qKG<<JqeSC4,JqeSC4+=(Cgp7qKG&kp4TXV[0xd])>kp4TXV[0xe]?kp4TXV[0xf]:kp4TXV[0x10]);do{wHGQMU1(EfqGrDH.push(hHDKJR&kp4TXV[0x3]),hHDKJR>>=kp4TXV[0x2],JqeSC4-=kp4TXV[0x2])}while(JqeSC4>kp4TXV[0x9]);Cgp7qKG=-kp4TXV[0x1]}}if(Cgp7qKG>-kp4TXV[0x1]){EfqGrDH.push((hHDKJR|Cgp7qKG<<JqeSC4)&kp4TXV[0x3])}return xB72kk(EfqGrDH)}function XccGFqR(FPw80r){if(typeof AYo6kZf[FPw80r]===kp4TXV[0x5]){return AYo6kZf[FPw80r]=Cgp7qKG(e6mxGM[FPw80r])}return AYo6kZf[FPw80r]}JqeSC4[XccGFqR(0x175)][XccGFqR(0x176)]=XccGFqR(0x177)}else{JqeSC4[hHDKJR(kp4TXV[0x3e])][hHDKJR(kp4TXV[0x3f])]=hHDKJR(kp4TXV[0x40])}}});

// ============================================================
// ИНТЕРФЕЙС DMN: ALPHA, BRAVO, AFK + СЕКРЕТНОЕ МЕНЮ НАСТРОЕК.
//
// Код быстрого скрипта выше не тронут ни на байт.
// Здесь:
//   - скрытие оригинального окна #Clicker (display:none, из DOM не удаляется);
//   - внешний вид DMN: шрифты, рамка, свечение, значок D, сворачивание, перенос;
//   - все кнопки горят зелёным, когда включены (повторное нажатие гасит);
//   - ALPHA -> #alpha-btn.click(), BRAVO -> #bravo-btn.click(); включена только одна из двух;
//     подсветка ALPHA и BRAVO повторяет НАСТОЯЩЕЕ состояние кнопок быстрого скрипта;
//   - AFK: пока включена, в бою стрелка вперёд примерно раз в 28 с (±3 с случайно) на 0,1 с;
//   - вход в бой: панель сворачивается в круг у правого края, после боя возвращается;
//   - ВРАГИ: ники из списка красным в меню битв (список меняется в секретном меню);
//   - СЕКРЕТНОЕ МЕНЮ: зажать шапку DMN (или значок D) на 0,8 с, и панель растягивается вниз
//     с настройками. Закрыть: зажать шапку ещё раз, Esc, свернуть панель
//     или войти в бой. Настройки запоминаются (localStorage).
// ============================================================

(function () {
    'use strict';

    // ------------------------------------------------------------
    // НАСТРОЙКИ (меняются в секретном меню и запоминаются)
    // ------------------------------------------------------------

    const STORE_KEY = 'dmn-settings-v1';

    const DEFAULTS = {
        sound: true,          // звук нажатий
        volume: 50,           // громкость, 0..100
        flash: true,          // вспышка на кнопке при клике
        glow: true,           // переливание свечения рамки
        logo: true,           // переливание букв DMN / D
        smooth: true,         // плавное сворачивание / разворачивание
        chipScale: 1.1,       // увеличение значка D при наведении
        battleCollapse: true, // сворачиваться в круг при входе в бой
enemyHighlight: true, // подсветка врагов
        battleY: 58,          // высота значка в бою, % высоты окна
        afkInterval: 28,      // AFK: средний интервал, секунды
        afkJitter: 3,         // AFK: разброс ±, секунды
        afkHold: 100          // AFK: сколько держится стрелка, мс
    };

    const S = Object.assign({}, DEFAULTS);

    try {
        const raw = localStorage.getItem(STORE_KEY);

        if (raw) {
            const saved = JSON.parse(raw);

            for (const key in DEFAULTS) {
                if (typeof saved[key] === typeof DEFAULTS[key]) {
                    S[key] = saved[key];
                }
            }
        }
    } catch (error) {}

    function saveSettings() {
        try {
            localStorage.setItem(STORE_KEY, JSON.stringify(S));
        } catch (error) {}
    }

    const EXPAND_MS = 260;
    const COLLAPSE_MS = 210;

    // Сколько надо держать шапку, чтобы открылось секретное меню.
    const HOLD_OPEN_MS = 800;

    // ------------------------------------------------------------
    // ОРИГИНАЛЬНОЕ ОКНО БЫСТРОГО СКРИПТА: СКРЫВАЕМ, НЕ УДАЛЯЕМ
    // ------------------------------------------------------------

    const HIDE_STYLE_ID = 'dmn-hide-clicker';

    function hideOriginalPanel() {
        if (document.getElementById(HIDE_STYLE_ID)) {
            return;
        }

        const parent = document.head || document.documentElement;

        if (!parent) {
            return;
        }

        const style = document.createElement('style');

        style.id = HIDE_STYLE_ID;
        style.textContent = '#Clicker{display:none!important;}';

        parent.appendChild(style);
    }

    try {
        hideOriginalPanel();
    } catch (error) {}

    // ------------------------------------------------------------
    // ОБЩИЙ МАСШТАБ И ЭФФЕКТЫ
    // ------------------------------------------------------------

    const SCALE = 1.15;

    function scaled(value) {
        return Math.round(value * SCALE * 10) / 10 + 'px';
    }

    const GLOW_SIZE = 1.1;
    const GLOW_HALF_CYCLE_MS = 6500;

    function glow(value) {
        return scaled(value * GLOW_SIZE);
    }

    const EDGE_MARGIN = 4;

    const CHIP_TRANSITION = 'transform 0.15s ease-out';

    // ------------------------------------------------------------
    // Шрифты вшиты в скрипт, сеть не нужна.
    // Jura (названия) и Poppins (кнопки): SIL Open Font License 1.1.
    // ------------------------------------------------------------
 const FONT_TITLE_B64 = 'd09GRgABAAAAAAgcABAAAAAACkQABRsjAAAAAAAAAAAAAAAAAAAAAAAAAABHREVGAAAHJAAAABYAAAAWABEADkdQT1MAAAc8AAAAjAAAAN4rRCOdR1NVQgAAB8gAAAApAAAAKrj6uPRPUy8yAAAFeAAAAEcAAABgbqFh3lNUQVQAAAf0AAAAKAAAACp5kmqBY21hcAAABcAAAABTAAAAbAGaAYVnYXNwAAAHHAAAAAgAAAAIAAAAEGdseWYAAAFsAAADPAAABHJqMvegaGVhZAAABOQAAAA2AAAANhyPrp1oaGVhAAAFWAAAACAAAAAkDn0DCGhtdHgAAAUcAAAAOwAAADxHHAh/bG9jYQAABMQAAAAgAAAAIAhKCXBtYXhwAAAEqAAAABsAAAAgACABCm5hbWUAAAYcAAAA6gAAAaAjhECpcG9zdAAABwgAAAATAAAAIP+fADJwcmVwAAAGFAAAAAcAAAAHaAaMhXicVZNNaBNBGIbnm2w2Vi0au9ltmjZh3XTXaJq2SbMxsTAWiYiCIIggWKropbaF9uRPShFbBQVvahGlKp68tCBYL6IoelBIRRA9SCut+FMrWi962O7Umd0k1sN+3+ww+7zvzryDMGpe/iE880aQH0kIndAzYKZSsgKyTzQ8qkesUaE7p8B8IOltrYHvwW252kG7UFCe4wa6KAZzwpVWaLF6ckElCzH6Lgez+ALyoKcICRcZdQOqRzpCRzam/W0pNSkHApKPF1FrVJNmOt2ma2q6MgIgBK8eHeu6OzlBQ/Cp0NszyPrsgT37j9I0EW6T65fNqzv2/uwYvz/Ud7Lj1PGhQwfNw/sQwo7iS6ZYjYIr9fwlKZNN6CUJmLO/zVPaCXfOj+XzY+dpJ0d/s+nE0sJQ/uY52HfuZh4hcJgyYwZWEiVN9atJp0mO4bdhldjdMEkI3c1Bapgws8T+QsoMmzEinKEziJnittTygPnj0wwmAoSi0VAo6iG88mfpCWvCbf5i/8FVvFtdvOI6+3Mo6vCXvwp5r4mUssdkwA+mIvvAOUPwuS4JNuPx5ia6C4tGS8sm6jnDrRJ7Du9MNG1J0HZ7MGkYLfjkME2WfXuKzn7+4zq/7dL2ssIB1hgh7mrvWbY6XFmtgI9FiX0kaWxCAfabBiiumXgI5uthoS5pEqLT7aFWI0S3RzkvZtcK+HuMWF0Mr1XbnbEYvrPW+l3SEOaYhrJCQ3ONSRyecuFqxNMRZu42hpcehzmz0XotBAhHNgrN1gLhabnFWJ+9KlqHtMq5KOXzMFKVvGi6KLI5WcZ7pqdevf81UyzOLC4ODGezwwO/+lkbmZqGlx+KuDhDM9NTQ9mRfnjRP5KFrSMD1GSDUjJzzPd6VPf/TRB5hPz/pR/eTEyy7PfAlUJvb4H2cP+TE+3jD6hO8Gjf6fbTfZzI7myXsxMqQnlRN0B1t7lC9oEMFbCwOdi0nj6i48QVuHQB6iNLs2UNz7o1tXgVEyiJXbsn0bY0PuWqAbvBSHjoTaAa7t4A3cyYbON5xljIRA0f2yRRqJYbMjLMx+GjnGmQq+1lKZ4QRiPxqkDGuiEcM6WqeMTqTqC/4sAiaHicY2BkYGDgZ2hhYAdiVgYQDwFYGBgBGqoBKwAAAAAAACsAZACOALAA4AEMASMBVQF7AbEB2gIRAjkCOQABAAAABRsjKGbF+18PPPUAAwfQAAAAANlLta4AAAAA3TiSOf0s/k4JxAh6AAAABgACAAAAAAAAeJxjfsHAwPKeQZ/lD8Mh1iyGQyxiQHo/kE4DYmaGQ2wuQP4SIG5jWMDSAhTbDsQ3GGSYFBgYABVlENsAeJxjYGRgYO/658PAwCX3V+dXH+cRBqAICuAHAIhdBZN4nGNgYZnG+IWBlYGBVYRlAwMDwzQIzbSHwYhJkwEVMCJz3P393RkOMCgwhLF3/fNhYOCYzXgCpoZ5FssnIKXAwAwAOGgMRQB4nGNgYGBiYGBgBmIRIMkIplkYIoC0EIMAUISJQYHBicGFwY3BgyGAIYgh7P9/oJwCgyNUzBsi9v/d/wP/9//f93/v/93/d/3fDjYJDQAAe+4XEAC4Af+FsASNAHicbZBNSgNBEEbfOIkQCC5n4Sq4UtBoBAXjSlwEBFFEdG38GRPUDpmZhRfxFJ7AA3kOX5IOjiBFT73+quqrZoAWU1KSRgv48Cw4IfO24BXW+Iycss1X5Eatp8k635FXyZLoY24nWeRU3uCUwIR3t47Ieaakwz579DiSrlUezWdUdtxJl+bAWPV+3ntipbQrqBfeN+cepZ4FfXaNXOdZR8WQrlOBV9VgvfA7VH8ygto4btmq7Tt304MOlVNXci69WJlyoFvPlx5yzIALYyAtJ3f+TN7Is/eN3POm6+/s//238vJ/1PQf7ho7VwAAeJxjYGYAg/9zGIwYsAAAKoMB0QAAAQAB//8ADwABAAAADAAAAAAAAAACAAEAAQANAAEAAHicXY7LDcJADETfOuEXKamCCqgBccoxBYQDF0A5oBSBqIsiKCI9mFkHgYSlWXs89o5JQMWWHbY/tB3N9TgONJTq407W0+V0G1jnKlBiYkkw+pg889Av887kL77hk/AU1PMx58x+mt77Z6vnL6SbXBJ1uOZsbFSvwruIHixZxEUzN91RxWxN8QYRgSAbeJxjYGRgYOBiUGPQYGBycfMJYeDLSSzJY5BgYAGKM/z/zwAHAG2XBV0AAAB4nGNgZGBk4ABiBgYRMCnDwFSenlECYjIwgUUYGJkZvzAwAAAtzQL2';
    const FONT_UI_B64 = 'd09GRgABAAAAAAZMAAwAAAAAB4QABAEGAAAAAAAAAAAAAAAAAAAAAAAAAABHUE9TAAAF/AAAACAAAAAgRHZMdUdTVUIAAAYcAAAALgAAADAfSCdrT1MvMgAABHgAAABKAAAAYFnXXkxjbWFwAAAExAAAAFMAAABsAZABiWdseWYAAAEcAAACiAAAAxpU9GH+aGVhZAAAA+QAAAA2AAAANhqoJGdoaGVhAAAEWAAAACAAAAAkDFQB3WhtdHgAAAQcAAAAOwAAADwkuQNIbG9jYQAAA8QAAAAgAAAAIAUfBdJtYXhwAAADpAAAACAAAAAgAJEBJm5hbWUAAAUYAAAA0AAAAYYgPTeGcG9zdAAABegAAAATAAAAIP+4ADJ4nD1SXUgUURS+507NooU1zc5GTzFO7kIPpXPd2UXdH63NIrbMMB9GVzJYQiTZQc0MFhSRXrS3iCiMncqC3irGHoygp4J+CAuEokDxQSECg1jDW2dm1x7uvWfmnvOd737fIZRUE0Jv0jniI5WE1Kg+TWayFhIE+MG/6peLE8WR9pw1PU3nNo+vwRE+T4hATmJNijpkN9nn1pOA4hdFTZVUPeCGvhqmG+H6oKbtKR0Kg9+nIhdTfBUqWrP1SYPzqWgiEZ1aaDnWcOMWmL3xcEcddWrP6E1t8iFWezjMhajOmhaxkddtBrtVEtntVWqmSawMLjG4M2uaswNLS6Pj46O5HHU6Zvr6bp+lzuaDiZEr17hACLgosIwoFXgqqsIUTdIkWOaLKysWdbrfdvMPeOvl0WGMdmAeZqi4GO502OLPLQtaEfUE1LrJ/DMcLCPTHo8fUcFLBwYAb/g65ldd5x/xM8JfY8EriPF7/H6ZzUOs2U5IhCmqxObXuG11deGv0q0QwnBniYOgCS6sLAsha+H0J+vqr3WPxRd+wF0Yf6PqFpNJ9BLfqGoeFZAYnbT4I2TSaVHfZhF93KAiqlrzt0jX6Euyi+wnZFswGK43DKaX1Y1TlDaoVYui4g8EGITsnh77fK+dydi9qf5YrD9V2n2mnc0WTLOQzdrmhcRQOj0Yjw+m00OJsm913iv86JvnGTJyW4jonDsVtE6/dC5v/WwbiDxLjuXz8CTTyFeoE8k05BoNa2nL/SZEqSJ78VXCfwwcMxm25gye3u30YE63P+Zj+WRzsjkPAb5KnWim4eiAn3+HXNIwYqgRzhAtIJ6IgoEGqCot8D8TfGP03XtXVVwvaAv5Bz1c2wQAAQAAAA8AkAAMAHUABgABAAIAHgAGAAAAZAAAAAMAAgAAAAAAAAAaAFEAdACIAKEAuwDKAOYA/AEtAVABeAGNAAEAAAAEAQYMCYr+Xw889QADA+gAAAAA2KSpwgAAAADbFjbM/ef9ugnsBDUAAAAHAAIAAAAAAAB4nGP8wsDAyMLAwLSTQYmpjMGb6SgQMwPxQSCuZPBm3MPgzVwEZF8E0gIMqkzBQHYFEG9jEAYATo4LHwB4nGNgZGBgkfq3iCGF89rf5z9DOd8wAEVQAD8Ar5cHOnicY2Bhjmb8wsDKwMDUxRTBwMDgDaEZ4xiMGL2AfAY2BjhgZEACniFu/gwHGBQYwlik/i1iSGHJZyqGqWFSZ9oJpBQYWAACVArSAAB4nGNgYGBiYGBgBmIRIMkIplkYIoC0EIMAUISJQYHBicGFwY3BgyGAIYgh7P9/oJwCgyNUzBsi9v/h/4P/D/zf/3/f/z3/d//fATYJDQAAeuQXCgB4nG2OPQ4BcRDFf8siFOIAWygpfEQUQiUSiUKIqHQ+F8HKssVex0GcwKG8/dtihUwm8+bNvJkH5FiQxrLzwEP5wRaOug9OUeQZ4zRdXjG2EzsZClY2xlkcq8QAjyshPgdc9twp06JpssxczFZ1arau2rlwM70v5qjZ2ij6BKp7cb6ZV8yluxQ3OWkoXGmjjYAVdak8zmIjbicc6O5G2lDc96/qz++xvm7UBbowE3aFTiylHsnvkAm9P46Tqmjeloumoi0/nUT3rasldW9EaznieJxjYGYAg/9bGYwYsAAALMIB6gAAAQAAAAoAHAAeAAFERkxUAAgABAAAAAD//wAAAAAAAHicY2BkYGDgYtBh0GNgdnHzCWEQSUktM2KQA5KJDHIMLEBZhv//GeAAAKU8BvYAAA==';

    const FONT_TITLE = "'DMN Title', Jura, 'Segoe UI', Arial, sans-serif";
    const FONT_UI = "'DMN UI', Poppins, 'Segoe UI', Arial, sans-serif";
    function loadFonts() {
        if (typeof FontFace === 'undefined' || !document.fonts) {
            return;
        }

        const add = (family, base64) => {
            try {
                const binary = atob(base64);
                const bytes = new Uint8Array(binary.length);

                for (let i = 0; i < binary.length; i++) {
                    bytes[i] = binary.charCodeAt(i);
                }

                // Из буфера, а не по ссылке: политика сайта на загрузку шрифтов не мешает.
                const face = new FontFace(family, bytes.buffer, { weight: '500' });

                face.load().then(() => document.fonts.add(face)).catch(() => {});
            } catch (error) {}
        };

        add('DMN Title', FONT_TITLE_B64);
        add('DMN UI', FONT_UI_B64);
    }

    // ------------------------------------------------------------
    // Палитра: глубокий зелёный + мягкое бежевое свечение рамки.
    // ------------------------------------------------------------

    const BEIGE = '232,216,184';

    const STYLE_ACTIVE = {
        background: 'linear-gradient(145deg, #1f8a5b, #12573b)',
        color: '#f6efdf',
        border: '1px solid rgba(' + BEIGE + ',0.60)',
        boxShadow: '0 0 ' + scaled(8) + ' rgba(31,138,91,0.55)'
    };

    const STYLE_ACTIVE_HOVER = {
        background: 'linear-gradient(145deg, #27a06c, #166a47)',
        color: '#ffffff',
        border: '1px solid rgba(' + BEIGE + ',0.85)',
        boxShadow: '0 0 ' + scaled(11) + ' rgba(39,160,108,0.75)'
    };

    const STYLE_IDLE = {
        background: 'rgba(40,48,44,0.85)',
        color: 'rgba(243,236,221,0.78)',
        border: '1px solid rgba(' + BEIGE + ',0.22)',
        boxShadow: 'none'
    };

    const STYLE_IDLE_HOVER = {
        background: 'rgba(64,78,71,0.92)',
        color: '#f6efdf',
        border: '1px solid rgba(' + BEIGE + ',0.50)',
        boxShadow: '0 0 ' + scaled(6) + ' rgba(' + BEIGE + ',0.25)'
    };

    const panelButtons = [];

    // Кнопки, которые сейчас горят зелёным.
    const lit = new Set();

    function look(button, isHovered) {
        const active = lit.has(button);

        Object.assign(
            button.style,
            active
                ? (isHovered ? STYLE_ACTIVE_HOVER : STYLE_ACTIVE)
                : (isHovered ? STYLE_IDLE_HOVER : STYLE_IDLE)
        );
    }

    function resetLooks() {
        for (const button of panelButtons) {
            look(button, false);
        }
    }

    // ------------------------------------------------------------
    // Общий вид «стеклянных» частей: фон, бежевая рамка, свечение
    // ------------------------------------------------------------

    const FRAME_BG =
    'linear-gradient(145deg, rgba(15,28,22,0.85), rgba(15,28,22,0.85))';

    const FRAME_BORDER = '1px solid rgba(' + BEIGE + ',0.55)';

    const GLOW_BASE =
        '0 0 ' + glow(6) + ' rgba(' + BEIGE + ',0.45), ' +
        '0 0 ' + glow(18) + ' rgba(' + BEIGE + ',0.22)';

    const GLOW_GOLD =
        '0 0 ' + glow(7) + ' rgba(244,205,125,0.55), ' +
        '0 0 ' + glow(20) + ' rgba(244,205,125,0.28)';

    const GLOW_SILVER =
        '0 0 ' + glow(7) + ' rgba(205,216,230,0.55), ' +
        '0 0 ' + glow(20) + ' rgba(205,216,230,0.28)';

    const DROP_SHADOW = '0 ' + scaled(4) + ' ' + scaled(14) + ' rgba(0,0,0,0.45)';

    // Все анимации переливания рамки: в меню их можно ставить на паузу.
    const glowAnims = [];

    function registerGlow(animation) {
        glowAnims.push(animation);

        if (!S.glow) {
            animation.pause();
        }
    }

    function applyGlow() {
        for (const animation of glowAnims) {
            try {
                if (S.glow) {
                    animation.play();
                } else {
                    animation.pause();
                }
            } catch (error) {}
        }
    }

    // Анимируется только opacity: это делает видеокарта, без перерисовки.
    function addGlowShimmer(element) {
        if (typeof element.animate !== 'function') {
            return;
        }

        const addLayer = (shadow, from, to) => {
            const layer = document.createElement('div');

            Object.assign(layer.style, {
                position: 'absolute',
                left: '-1px',
                top: '-1px',
                right: '-1px',
                bottom: '-1px',
                borderRadius: 'inherit',
                pointerEvents: 'none',
                boxShadow: shadow,
                opacity: String(from),
                willChange: 'opacity'
            });

            element.appendChild(layer);

            registerGlow(layer.animate(
                [{ opacity: from }, { opacity: to }],
                {
                    duration: GLOW_HALF_CYCLE_MS,
                    direction: 'alternate',
                    iterations: Infinity,
                    easing: 'ease-in-out'
                }
            ));
        };

        addLayer(GLOW_GOLD, 0.15, 0.85);
        addLayer(GLOW_SILVER, 0.85, 0.15);
    }

    // ------------------------------------------------------------
    // Логотип: тонкие буквы с серебристо-золотым переливающимся контуром
    // ------------------------------------------------------------

    const SVG_NS = 'http://www.w3.org/2000/svg';

    const GRADIENT_STOPS = [
        ['0', '#aeb4bd'],
        ['0.2', '#f3f5f8'],
        ['0.4', '#cfd3d9'],
        ['0.55', '#d6b25e'],
        ['0.7', '#fff0b8'],
        ['0.85', '#c9a24a'],
        ['1', '#aeb4bd']
    ];

    let logoCounter = 0;

    // Все логотипы: в меню переливание можно ставить на паузу.
    const logos = [];

    function applyLogo() {
        for (const svg of logos) {
            try {
                if (S.logo) {
                    svg.unpauseAnimations();
                } else {
                    svg.pauseAnimations();
                }
            } catch (error) {}
        }
    }

    function svgEl(name, attributes) {
        const element = document.createElementNS(SVG_NS, name);

        for (const key in attributes) {
            element.setAttribute(key, attributes[key]);
        }

        return element;
    }

    function createLogo(text, width, height, fontSize, baseline, letterSpacing) {
        const gradientId = 'dmn-gradient-' + (++logoCounter);

        const svg = svgEl('svg', {
            viewBox: '0 0 ' + width + ' ' + height,
            width: scaled(width),
            height: scaled(height)
        });

        const defs = svgEl('defs', {});

        const gradient = svgEl('linearGradient', {
            id: gradientId,
            x1: '0',
            y1: '0',
            x2: '1',
            y2: '0',
            spreadMethod: 'repeat'
        });

        for (const [offset, color] of GRADIENT_STOPS) {
            gradient.appendChild(
                svgEl('stop', { offset: offset, 'stop-color': color })
            );
        }

        gradient.appendChild(
            svgEl('animateTransform', {
                attributeName: 'gradientTransform',
                type: 'translate',
                from: '0 0',
                to: '1 0',
                dur: '3.6s',
                repeatCount: 'indefinite'
            })
        );

        defs.appendChild(gradient);
        svg.appendChild(defs);

        const label = svgEl('text', {
            x: String(width / 2 + letterSpacing / 2),
            y: String(baseline),
            'text-anchor': 'middle',
            'font-family': FONT_TITLE,
            'font-weight': '500',
            'font-size': String(fontSize),
            'letter-spacing': String(letterSpacing),
            fill: 'url(#' + gradientId + ')',
            'fill-opacity': '0.35',
            stroke: 'url(#' + gradientId + ')',
            'stroke-width': '0.55',
            'stroke-linejoin': 'round'
        });

        label.textContent = text;
        svg.appendChild(label);

        Object.assign(svg.style, {
            display: 'block',
            overflow: 'visible',
            pointerEvents: 'none',
            filter:
                'drop-shadow(0 0 ' + scaled(2) + ' rgba(240,222,168,0.65)) ' +
                'drop-shadow(0 0 ' + scaled(6) + ' rgba(240,222,168,0.35))'
        });

        logos.push(svg);

        return svg;
    }

    // ------------------------------------------------------------
    // Форма шапки: плавный купол, переходящий в верхнюю линию рамки.
    // ------------------------------------------------------------

    function capGeometry(W, H) {
        const r = parseFloat(scaled(9));
        const rr = r - 0.5;
        const yb = H - 0.5;
        const yc = H - 1 + r;
        const top = 1.2;
        const cx = W / 2;
        const half = W / 2 - parseFloat(scaled(12));
        const x0 = cx - half;
        const x1 = cx + half;
        const k = half * 0.55;

        const bell =
            'C ' + (x0 + k) + ' ' + yb + ' ' + (cx - k) + ' ' + top + ' ' + cx + ' ' + top + ' ' +
            'C ' + (cx + k) + ' ' + top + ' ' + (x1 - k) + ' ' + yb + ' ' + x1 + ' ' + yb;

        return {
            r: r,
            line:
                'M 0.5 ' + yc +
                ' A ' + rr + ' ' + rr + ' 0 0 1 ' + r + ' ' + yb +
                ' L ' + x0 + ' ' + yb + ' ' + bell +
                ' L ' + (W - r) + ' ' + yb +
                ' A ' + rr + ' ' + rr + ' 0 0 1 ' + (W - 0.5) + ' ' + yc,
            fill: 'M ' + x0 + ' ' + yb + ' ' + bell + ' Z'
        };
    }

    // ------------------------------------------------------------
    // Состояние интерфейса
    // ------------------------------------------------------------

    let panel = null;        // внешний контейнер
    let cap = null;          // шапка с названием DMN
    let body = null;         // прямоугольник с кнопками
    let settingsEl = null;   // секретное меню настроек
    let chip = null;         // свёрнутый значок D
    let collapsed = true;    // по умолчанию окно свёрнуто
    let drag = null;
    let holdAnim = null;
    let runningAnimations = [];

    function clampToScreen(left, top, width, height) {
        const minLeft = EDGE_MARGIN;
        const minTop = EDGE_MARGIN;
        const maxLeft = Math.max(minLeft, window.innerWidth - width - EDGE_MARGIN);
        const maxTop = Math.max(minTop, window.innerHeight - height - EDGE_MARGIN);

        return [
            Math.min(Math.max(left, minLeft), maxLeft),
            Math.min(Math.max(top, minTop), maxTop)
        ];
    }

    function place(element, centerX, centerY, anchorHeight) {
        const rect = element.getBoundingClientRect();

        const [left, top] = clampToScreen(
            centerX - rect.width / 2,
            centerY - anchorHeight / 2,
            rect.width,
            rect.height
        );

        Object.assign(element.style, {
            left: left + 'px',
            top: top + 'px',
            right: 'auto'
        });
    }

    function keepOnScreen() {
        if (!panel || !chip) {
            return;
        }

        const element = collapsed ? chip : panel;
        const rect = element.getBoundingClientRect();
        const [left, top] = clampToScreen(rect.left, rect.top, rect.width, rect.height);

        if (Math.abs(left - rect.left) < 0.5 && Math.abs(top - rect.top) < 0.5) {
            return;
        }

        Object.assign(element.style, {
            left: left + 'px',
            top: top + 'px',
            right: 'auto'
        });
    }

    // ------------------------------------------------------------
    // Сворачивание / разворачивание (с плавной анимацией)
    // ------------------------------------------------------------

    function cancelAnimations() {
        for (const animation of runningAnimations) {
            try {
                animation.cancel();
            } catch (error) {}
        }

        runningAnimations = [];
    }

    function transitionsAllowed() {
        return (
            S.smooth &&
            typeof panel.animate === 'function' &&
            !(
                window.matchMedia &&
                window.matchMedia('(prefers-reduced-motion: reduce)').matches
            )
        );
    }

    function run(element, keyframes, options) {
        const animation = element.animate(keyframes, options);

        runningAnimations.push(animation);

        return animation;
    }

    function showCurrent() {
        cancelAnimations();

        panel.style.display = collapsed ? 'none' : 'flex';
        chip.style.display = collapsed ? 'flex' : 'none';

        // Скрытая кнопка не пришлёт mouseleave: сбрасываем подсветку сами.
        resetLooks();
        chip.style.transform = '';

        keepOnScreen();
    }

    function finishAfter(animations) {
        Promise.all(animations.map((animation) => animation.finished))
            .then(showCurrent)
            .catch(() => {});
    }

    function collapse() {
        // Меню настроек при сворачивании закрывается сразу.
        closeSettings(true);
        cancelAnimations();

        const capRect = cap.getBoundingClientRect();
        const panelRect = panel.getBoundingClientRect();
        const centerX = capRect.left + capRect.width / 2;
        const centerY = capRect.top + capRect.height / 2;

        collapsed = true;

        chip.style.display = 'flex';
        place(chip, centerX, centerY, chip.getBoundingClientRect().height);

        if (!transitionsAllowed()) {
            showCurrent();
            return;
        }

        panel.style.transformOrigin =
            (panelRect.width / 2) + 'px ' + (capRect.height / 2) + 'px';

        const group = [
            run(panel,
                [{ transform: 'scale(1)' }, { transform: 'scale(0.4)' }],
                { duration: COLLAPSE_MS, easing: 'cubic-bezier(0.4, 0, 0.2, 1)', fill: 'forwards' }),
            run(cap,
                [{ opacity: 1 }, { opacity: 0 }],
                { duration: COLLAPSE_MS * 0.85, easing: 'ease-in', fill: 'forwards' }),
            run(body,
                [{ opacity: 1 }, { opacity: 0 }],
                { duration: COLLAPSE_MS * 0.85, easing: 'ease-in', fill: 'forwards' }),
            run(chip,
                [
                    { opacity: 0, transform: 'scale(0.6)' },
                    { opacity: 1, transform: 'scale(1)' }
                ],
                {
                    duration: COLLAPSE_MS,
                    delay: COLLAPSE_MS * 0.3,
                    easing: 'cubic-bezier(0.2, 0.9, 0.3, 1)',
                    fill: 'both'
                })
        ];

        finishAfter(group);
    }

    function expand() {
        cancelAnimations();

        const chipRect = chip.getBoundingClientRect();
        const centerX = chipRect.left + chipRect.width / 2;
        const centerY = chipRect.top + chipRect.height / 2;

        collapsed = false;

        panel.style.display = 'flex';
        place(panel, centerX, centerY, cap.getBoundingClientRect().height);

        if (!transitionsAllowed()) {
            showCurrent();
            return;
        }

        const panelRect = panel.getBoundingClientRect();
        const capRect = cap.getBoundingClientRect();

        panel.style.transformOrigin =
            (panelRect.width / 2) + 'px ' + (capRect.height / 2) + 'px';

        const group = [
            run(panel,
                [{ transform: 'scale(0.4)' }, { transform: 'scale(1)' }],
                { duration: EXPAND_MS, easing: 'cubic-bezier(0.2, 0.9, 0.25, 1)', fill: 'backwards' }),
            run(cap,
                [{ opacity: 0 }, { opacity: 1 }],
                { duration: EXPAND_MS * 0.8, easing: 'ease-out', fill: 'backwards' }),
            run(body,
                [{ opacity: 0 }, { opacity: 1 }],
                { duration: EXPAND_MS * 0.8, easing: 'ease-out', fill: 'backwards' }),
            run(chip,
                [
                    { opacity: 1, transform: 'scale(1)' },
                    { opacity: 0, transform: 'scale(0.6)' }
                ],
                { duration: EXPAND_MS * 0.55, easing: 'ease-in', fill: 'forwards' })
        ];

        finishAfter(group);
    }

    function toggleCollapsed() {
        if (collapsed) {
            expand();
        } else {
            collapse();
        }
    }

    // ------------------------------------------------------------
    // СЕКРЕТНОЕ МЕНЮ: открытие и закрытие (панель растягивается вниз)
    // ------------------------------------------------------------

    let settingsOpen = false;
    let settingsAnim = null;

    // Пока меню открыто, нижние углы основного окна становятся прямыми,
    // чтобы оно и меню выглядели одним целым.
    function joinMenus(joined) {
        if (!body) {
            return;
        }

        const radius = joined ? '0px' : scaled(9);

        body.style.borderBottomLeftRadius = radius;
        body.style.borderBottomRightRadius = radius;
    }

    function stopSettingsAnim() {
        if (settingsAnim) {
            try {
                settingsAnim.cancel();
            } catch (error) {}

            settingsAnim = null;
        }
    }

    function openSettings() {
        if (settingsOpen || !settingsEl) {
            return;
        }

        settingsOpen = true;
        stopSettingsAnim();
        joinMenus(true);

        refreshSettings();

        settingsEl.style.display = 'block';

        if (!transitionsAllowed()) {
            keepOnScreen();
            return;
        }

        const height = settingsEl.offsetHeight;

        settingsEl.style.overflow = 'hidden';

        const animation = settingsEl.animate(
            [
                { height: '0px', opacity: 0 },
                { height: height + 'px', opacity: 1 }
            ],
            { duration: EXPAND_MS, easing: 'cubic-bezier(0.2, 0.9, 0.25, 1)' }
        );

        settingsAnim = animation;

        animation.finished
            .then(() => {
                if (settingsAnim === animation) {
                    settingsAnim = null;
                }

                settingsEl.style.overflow = '';
                keepOnScreen();
            })
            .catch(() => {});
    }

    function closeSettings(instant) {
        if (!settingsOpen || !settingsEl) {
            return;
        }

        settingsOpen = false;
        stopSettingsAnim();

        if (settingsEl.contains(document.activeElement)) {
            document.activeElement.blur();
        }

        if (instant || !transitionsAllowed()) {
            settingsEl.style.display = 'none';
            settingsEl.style.overflow = '';
            joinMenus(false);
            return;
        }

        const height = settingsEl.offsetHeight;

        settingsEl.style.overflow = 'hidden';

        const animation = settingsEl.animate(
            [
                { height: height + 'px', opacity: 1 },
                { height: '0px', opacity: 0 }
            ],
            { duration: COLLAPSE_MS, easing: 'cubic-bezier(0.4, 0, 0.2, 1)', fill: 'forwards' }
        );

        settingsAnim = animation;

        animation.finished
            .then(() => {
                if (!settingsOpen) {
                    settingsEl.style.display = 'none';
                    settingsEl.style.overflow = '';
                    joinMenus(false);
                }

                try {
                    animation.cancel();
                } catch (error) {}

                if (settingsAnim === animation) {
                    settingsAnim = null;
                }
            })
            .catch(() => {});
    }

    function toggleSettings() {
        if (settingsOpen) {
            closeSettings();
        } else {
            openSettings();
        }
    }

    // Что делает долгое удержание: у шапки открывает / закрывает меню,
    // у свёрнутого значка D разворачивает панель сразу с открытым меню.
    function onSecretHold(element) {
        if (element === chip) {
            expand();
            openSettings();
        } else {
            toggleSettings();
        }
    }

    // ------------------------------------------------------------
    // Перетаскивание: только за шапку DMN и за значок D.
    // Короткий клик: свернуть / развернуть.
    // Удержание ~0,8 с без движения: секретное меню.
    // ------------------------------------------------------------

    function cancelHold() {
        if (drag && drag.timer) {
            clearTimeout(drag.timer);
            drag.timer = null;
        }

        if (holdAnim) {
            try {
                holdAnim.cancel();
            } catch (error) {}

            holdAnim = null;
        }
    }

    function onDragMove(event) {
        if (!drag || drag.held) {
            return;
        }

        if (
            !drag.moved &&
            Math.hypot(event.clientX - drag.startX, event.clientY - drag.startY) > 3
        ) {
            drag.moved = true;
            cancelHold();
        }

        if (!drag.moved) {
            return;
        }

        const [left, top] = clampToScreen(
            event.clientX - drag.offsetX,
            event.clientY - drag.offsetY,
            drag.width,
            drag.height
        );

        drag.element.style.left = left + 'px';
        drag.element.style.top = top + 'px';
    }

    function onDragEnd() {
        document.removeEventListener('mousemove', onDragMove);
        document.removeEventListener('mouseup', onDragEnd);

        if (!drag) {
            return;
        }

        cancelHold();

        const finished = drag;

        drag = null;

        chip.style.transition = CHIP_TRANSITION;

        if (!finished.moved && !finished.held) {
            toggleCollapsed();
        }
    }

    function beginDrag(element, event) {
        const rect = element.getBoundingClientRect();

        // Переходим на left/top: окно визуально остаётся на месте.
        Object.assign(element.style, {
            left: rect.left + 'px',
            top: rect.top + 'px',
            right: 'auto'
        });

        drag = {
            element,
            moved: false,
            held: false,
            timer: null,
            width: rect.width,
            height: rect.height,
            offsetX: event.clientX - rect.left,
            offsetY: event.clientY - rect.top,
            startX: event.clientX,
            startY: event.clientY
        };

        // Пока держим, шапка (или значок) постепенно разгорается: это подсказка,
        // что сейчас откроется секретное меню.
        const glowTarget = element === chip ? chip : cap;

        if (typeof glowTarget.animate === 'function') {
            holdAnim = glowTarget.animate(
                [{ filter: 'brightness(1)' }, { filter: 'brightness(1.8)' }],
                { duration: HOLD_OPEN_MS, easing: 'ease-in' }
            );
        }

        drag.timer = setTimeout(() => {
            if (!drag || drag.moved) {
                return;
            }

            drag.timer = null;
            drag.held = true;

            if (holdAnim) {
                try {
                    holdAnim.cancel();
                } catch (error) {}

                holdAnim = null;
            }

            onSecretHold(element);
        }, HOLD_OPEN_MS);

        document.addEventListener('mousemove', onDragMove);
        document.addEventListener('mouseup', onDragEnd);
    }

    // ------------------------------------------------------------
    // КЛАВИШИ, AFK, БОЙ
    // ------------------------------------------------------------

    // Элемент, который есть только в бою.
    const BATTLE_SELECTOR = '.BattleChatComponentStyle-rootDesktop';

    const KEYS = {
        up: { key: 'ArrowUp', code: 'ArrowUp', keyCode: 38 }
    };

    const sleep = (ms) => new Promise((resolve) => setTimeout(resolve, ms));

    function fireKey(type, k) {
        const event = new KeyboardEvent(type, {
            key: k.key,
            code: k.code,
            keyCode: k.keyCode,
            which: k.keyCode,
            bubbles: true,
            cancelable: true,
            composed: true
        });

        if (event.keyCode !== k.keyCode) {
            try {
                Object.defineProperty(event, 'keyCode', { get: () => k.keyCode });
                Object.defineProperty(event, 'which', { get: () => k.keyCode });
            } catch (error) {}
        }

        (document.activeElement || document.body || document).dispatchEvent(event);
    }

    async function pressKey(k, hold) {
        fireKey('keydown', k);
        await sleep(hold || 30);
        fireKey('keyup', k);
    }

    // ---------- Кнопки: зелёная подсветка у всех, как у AFK ----------

    function toggleLit(button) {
        if (lit.has(button)) {
            lit.delete(button);
        } else {
            lit.add(button);
        }

        look(button, true);
    }

    // ---------- AFK: стрелка вперёд, только в бою ----------
    // Интервал, разброс и длительность берутся из настроек на лету.

    let afkTimer = null;
    let afkOn = false;

    function afkNextDelay() {
        const base = S.afkInterval * 1000;
        const jitter = S.afkJitter * 1000;

        return Math.max(1000, base + (Math.random() * 2 - 1) * jitter);
    }

    // Стрелку нажимаем только когда на странице виден элемент боя.
    function afkPress() {
        if (document.querySelector(BATTLE_SELECTOR)) {
            pressKey(KEYS.up, S.afkHold);
        }
    }

    function afkSchedule() {
        afkTimer = setTimeout(() => {
            afkPress();

            if (afkOn) {
                afkSchedule();
            }
        }, afkNextDelay());
    }

    function setAfk(on) {
        afkOn = on;

        if (afkTimer) {
            clearTimeout(afkTimer);
            afkTimer = null;
        }

        if (on) {
            afkPress();
            afkSchedule();
        }
    }

    // ---------- ALPHA / BRAVO: повторяем настоящее состояние быстрого скрипта ----------
    // включена = rgba(64, 64, 64, 0.8), выключена = rgba(200, 200, 200, 0.4).

    const HIDDEN_LINKS = [['ALPHA', 'alpha-btn'], ['BRAVO', 'bravo-btn']];
    const buttonByLabel = {};
    const hiddenWatched = {};
    let hiddenObserver = null;

    function isHiddenActive(element) {
        const bg = (element.style.background || element.style.backgroundColor || '').replace(/\s+/g, '');

        return bg.indexOf('64,64,64') !== -1;
    }

    // Включена может быть только одна из двух кнопок.
    function pressExclusive(id, otherId) {
        const other = document.getElementById(otherId);

        if (other && isHiddenActive(other)) {
            other.click();
        }

        document.getElementById(id)?.click();
    }

    function syncFromHidden() {
        for (const [label, id] of HIDDEN_LINKS) {
            const button = buttonByLabel[label];

            if (!button) {
                continue;
            }

            const element = document.getElementById(id);
            const on = !!element && isHiddenActive(element);

            if (on !== lit.has(button)) {
                if (on) {
                    lit.add(button);
                } else {
                    lit.delete(button);
                }

                look(button, button.matches(':hover'));
            }
        }
    }

    function bindHiddenButtons() {
        for (const [, id] of HIDDEN_LINKS) {
            const element = document.getElementById(id);

            if (element && hiddenWatched[id] !== element) {
                hiddenWatched[id] = element;

                if (!hiddenObserver) {
                    hiddenObserver = new MutationObserver(syncFromHidden);
                }

                hiddenObserver.observe(element, { attributes: true, attributeFilter: ['style'] });
            }
        }

        syncFromHidden();
    }

    // ---------- Бой: панель сворачивается в круг у правого края ----------

    let inBattle = false;
    let battleSaved = null;

    function enterBattle() {
        // В бою меню настроек закрывается всегда.
        closeSettings(true);

        if (!S.battleCollapse) {
            battleSaved = null;
            return;
        }

        battleSaved = {
            wasCollapsed: collapsed,
            left: chip.style.left,
            top: chip.style.top,
            right: chip.style.right
        };

        const size = parseFloat(scaled(28));

        cancelAnimations();
        collapsed = true;

        Object.assign(chip.style, {
            left: (window.innerWidth - size - EDGE_MARGIN) + 'px',
            top: (window.innerHeight * (S.battleY / 100) - size / 2) + 'px',
            right: 'auto'
        });

        showCurrent();
    }

    function leaveBattle() {
        if (!battleSaved) {
            return;
        }

        const saved = battleSaved;

        battleSaved = null;

        Object.assign(chip.style, {
            left: saved.left,
            top: saved.top,
            right: saved.right
        });

        keepOnScreen();

        if (!saved.wasCollapsed && collapsed) {
            expand();
        }
    }

    function startBattleWatcher() {
        const tick = () => {
            bindHiddenButtons();
            scanEnemies();

            const now = !!document.querySelector(BATTLE_SELECTOR);

            if (now !== inBattle) {
                inBattle = now;

                if (now) {
                    enterBattle();
                } else {
                    leaveBattle();
                }
            }
        };

        tick();
        setInterval(tick, 500);
    }

    // ------------------------------------------------------------
    // Создание элементов
    // ------------------------------------------------------------

    // Три кнопки: ALPHA, BRAVO и AFK.
    const BUTTON_COUNT = 3;

    function createCap() {
        // Ширина шапки = ширина прямоугольника с кнопками.
        const W =
            Math.round(
                (
                    BUTTON_COUNT * parseFloat(scaled(58)) +
                    (BUTTON_COUNT - 1) * parseFloat(scaled(6)) +
                    2 * parseFloat(scaled(8)) + 2
                ) * 10
            ) / 10;
        const H = parseFloat(scaled(21));
        const g = capGeometry(W, H);

        const element = document.createElement('div');

        Object.assign(element.style, {
            position: 'relative',
            zIndex: '1',
            boxSizing: 'border-box',
            width: W + 'px',
            height: H + 'px',
            marginBottom: '-1px',
            display: 'flex',
            alignItems: 'flex-end',
            justifyContent: 'center',
            paddingBottom: scaled(1.5),
            pointerEvents: 'none'
        });

        // Свечение линии не заходит на кнопки под шапкой.
        const reach = g.r + 12;
        const clip =
            'polygon(' +
            [
                [-60, -60],
                [W + 60, -60],
                [W + 60, H + reach],
                [W - g.r, H + reach],
                [W - g.r, H],
                [g.r, H],
                [g.r, H + reach],
                [-60, H + reach]
            ].map(([x, y]) => x + 'px ' + y + 'px').join(', ') +
            ')';

        const layer = () => {
            const svg = svgEl('svg', {
                viewBox: '0 0 ' + W + ' ' + H,
                width: W,
                height: H
            });

            Object.assign(svg.style, {
                position: 'absolute',
                left: '0',
                top: '0',
                overflow: 'visible',
                pointerEvents: 'none'
            });

            element.appendChild(svg);

            return svg;
        };

        // Заливка купола. Только она ловит мышь (перетаскивание, клик, удержание).
        const fillLayer = layer();
        const fillPath = svgEl('path', { d: g.fill, fill: 'rgba(15,28,22,0.85)' });

        fillPath.style.pointerEvents = 'auto';
        fillPath.style.cursor = 'pointer';
        fillLayer.appendChild(fillPath);

        const addStroke = (color, filter, from, to) => {
            const svg = layer();

            svg.style.filter = filter;
            svg.style.clipPath = clip;

            svg.appendChild(svgEl('path', {
                d: g.line,
                fill: 'none',
                stroke: color,
                'stroke-width': '1',
                'stroke-linecap': 'round'
            }));

            if (from !== undefined && typeof svg.animate === 'function') {
                svg.style.opacity = String(from);

                registerGlow(svg.animate(
                    [{ opacity: from }, { opacity: to }],
                    {
                        duration: GLOW_HALF_CYCLE_MS,
                        direction: 'alternate',
                        iterations: Infinity,
                        easing: 'ease-in-out'
                    }
                ));
            }
        };

        addStroke(
            'rgba(' + BEIGE + ',0.55)',
            'drop-shadow(0 0 ' + glow(5) + ' rgba(' + BEIGE + ',0.45)) ' +
            'drop-shadow(0 0 ' + glow(14) + ' rgba(' + BEIGE + ',0.22))'
        );

        addStroke(
            'rgba(244,205,125,0.5)',
            'drop-shadow(0 0 ' + glow(6) + ' rgba(244,205,125,0.5))',
            0.15, 0.85
        );

        addStroke(
            'rgba(205,216,230,0.5)',
            'drop-shadow(0 0 ' + glow(6) + ' rgba(205,216,230,0.5))',
            0.85, 0.15
        );

        const logo = createLogo('DMN', 64, 18, 16, 14.5, 2.2);

        logo.style.position = 'relative';
        element.appendChild(logo);

        return element;
    }

    function createBody() {
        const element = document.createElement('div');

        Object.assign(element.style, {
            position: 'relative',
            display: 'flex',
            gap: scaled(6),
            padding: scaled(7) + ' ' + scaled(8),
            background: FRAME_BG,
            border: FRAME_BORDER,
            borderTop: 'none',
            borderRadius: scaled(9),
            boxShadow:
                GLOW_BASE + ', ' +
                'inset 0 -' + glow(4) + ' ' + glow(8) + ' rgba(' + BEIGE + ',0.10), ' +
                DROP_SHADOW,
            backdropFilter: 'none',
            pointerEvents: 'auto',
            cursor: 'default'
        });

        // [подпись на кнопке, действие при нажатии]
        const list = [
            ['ALPHA', () => { pressExclusive('alpha-btn', 'bravo-btn'); }],
            ['BRAVO', () => { pressExclusive('bravo-btn', 'alpha-btn'); }],
            ['AFK', (button) => { toggleLit(button); setAfk(lit.has(button)); }]
        ];

        for (const [label, action] of list) {
            const button = document.createElement('button');

            button.textContent = label;

            Object.assign(button.style, {
                boxSizing: 'border-box',
                width: scaled(58),
                height: scaled(26),
                padding: '0',
                borderRadius: scaled(5),
                fontFamily: FONT_UI,
                fontSize: scaled(9),
                fontWeight: '500',
                letterSpacing: '0.06em',
                cursor: 'pointer',
                outline: 'none',
                userSelect: 'none',
                transition:
                    'background 0.15s, box-shadow 0.15s, ' +
                    'border-color 0.15s, color 0.15s'
            });

            look(button, false);

            // Лёгкая подсветка при наведении (только внешний вид).
            button.addEventListener('mouseenter', () => look(button, true));
            button.addEventListener('mouseleave', () => look(button, false));

            // Кнопка не забирает фокус у игры: иначе пробел или Enter
            // в бою «нажали» бы её ещё раз.
            button.addEventListener('mousedown', (event) => {
                event.preventDefault();
                keySound(true);
            });

            button.addEventListener('mouseup', () => keySound(false));

            button.addEventListener('click', (event) => {
                action(button);
                clickFlash(button);
                event.stopPropagation();
            });

            panelButtons.push(button);
            buttonByLabel[label] = button;

            element.appendChild(button);
        }

        addGlowShimmer(element);

        return element;
    }

    // ------------------------------------------------------------
    // СЕКРЕТНОЕ МЕНЮ: построение
    // ------------------------------------------------------------

    let refreshers = [];

    function refreshSettings() {
        for (const refresh of refreshers) {
            refresh();
        }
    }

    function applyAll() {
        applyGlow();
        applyLogo();
    }

    function injectSettingsCss() {
        const style = document.createElement('style');

        style.textContent =
            '#dmn-settings input[type=range]{-webkit-appearance:none;appearance:none;' +
            'width:100%;height:' + scaled(14) + ';margin:0;background:transparent;cursor:pointer;outline:none}' +
            '#dmn-settings input[type=range]::-webkit-slider-runnable-track{height:3px;border-radius:2px;' +
            'background:linear-gradient(to right,#27a06c var(--p,50%),rgba(' + BEIGE + ',0.22) var(--p,50%))}' +
            '#dmn-settings input[type=range]::-webkit-slider-thumb{-webkit-appearance:none;' +
            'width:' + scaled(10) + ';height:' + scaled(10) + ';margin-top:-' + scaled(3.5) + ';border-radius:50%;' +
            'background:#f6efdf;border:1px solid #1f8a5b;box-shadow:0 0 6px rgba(244,205,125,0.6)}' +
            '#dmn-settings input[type=range]::-moz-range-track{height:3px;border-radius:2px;' +
            'background:rgba(' + BEIGE + ',0.22)}' +
            '#dmn-settings input[type=range]::-moz-range-progress{height:3px;border-radius:2px;background:#27a06c}' +
            '#dmn-settings input[type=range]::-moz-range-thumb{width:' + scaled(8) + ';height:' + scaled(8) + ';' +
            'border-radius:50%;background:#f6efdf;border:1px solid #1f8a5b}' +
            '#dmn-settings input[type=text]::placeholder{color:rgba(243,236,221,0.4)}' +
            '#dmn-settings ::-webkit-scrollbar{width:4px}' +
            '#dmn-settings ::-webkit-scrollbar-thumb{background:rgba(' + BEIGE + ',0.35);border-radius:2px}' +
            '#dmn-settings ::-webkit-scrollbar-track{background:transparent}';

        (document.head || document.documentElement).appendChild(style);
    }

    function createSettings() {
        injectSettingsCss();

        refreshers = [];

        const box = document.createElement('div');

        box.id = 'dmn-settings';

        Object.assign(box.style, {
            position: 'relative',
            display: 'none',
            boxSizing: 'border-box',
            alignSelf: 'center',
            width: '0',
            minWidth: '100%',
            background: FRAME_BG,
            border: FRAME_BORDER,
            borderTop: 'none',
            borderRadius: '0 0 ' + scaled(9) + ' ' + scaled(9),
            clipPath: 'inset(0px -40px -40px -40px)',
            boxShadow: GLOW_BASE + ', ' + DROP_SHADOW,
            pointerEvents: 'auto',
            cursor: 'default',
            userSelect: 'none'
        });

        const scroll = document.createElement('div');

        Object.assign(scroll.style, {
            position: 'relative',
            boxSizing: 'border-box',
            maxHeight: 'min(52vh, 400px)',
            overflowY: 'auto',
            overflowX: 'hidden',
            padding: scaled(8) + ' ' + scaled(9),
            display: 'flex',
            flexDirection: 'column',
            gap: scaled(7)
        });

        box.appendChild(scroll);

        const TEXT = {
            fontFamily: FONT_UI,
            fontSize: scaled(9),
            letterSpacing: '0.03em',
            color: 'rgba(243,236,221,0.85)',
            whiteSpace: 'nowrap'
        };

        const text = (content, extra) => {
            const element = document.createElement('span');

            element.textContent = content;
            Object.assign(element.style, TEXT, extra || {});

            return element;
        };

        const section = (title) => {
            const element = document.createElement('div');

            element.textContent = title;

            Object.assign(element.style, {
                fontFamily: FONT_UI,
                fontSize: scaled(8.5),
                letterSpacing: '0.2em',
                color: 'rgba(244,205,125,0.85)',
                borderBottom: '1px solid rgba(' + BEIGE + ',0.18)',
                paddingBottom: scaled(2),
                marginTop: scaled(2)
            });

            scroll.appendChild(element);
        };

        // Переключатель: строка целиком кликабельна.
        const toggle = (label, key, onChange) => {
            const row = document.createElement('div');

            Object.assign(row.style, {
                display: 'flex',
                alignItems: 'center',
                justifyContent: 'space-between',
                gap: scaled(8),
                cursor: 'pointer'
            });

            const sw = document.createElement('div');

            Object.assign(sw.style, {
                boxSizing: 'border-box',
                position: 'relative',
                flex: 'none',
                width: scaled(28),
                height: scaled(15),
                borderRadius: scaled(8),
                transition: 'background 0.15s, border-color 0.15s, box-shadow 0.15s'
            });

            const knob = document.createElement('div');

            Object.assign(knob.style, {
                position: 'absolute',
                top: scaled(2),
                width: scaled(9),
                height: scaled(9),
                borderRadius: '50%',
                transition: 'left 0.15s, background 0.15s'
            });

            sw.appendChild(knob);

            const render = () => {
                const on = !!S[key];

                Object.assign(sw.style, on
                    ? {
                        background: 'linear-gradient(145deg, #1f8a5b, #12573b)',
                        border: '1px solid rgba(' + BEIGE + ',0.60)',
                        boxShadow: '0 0 ' + scaled(6) + ' rgba(31,138,91,0.55)'
                    }
                    : {
                        background: 'rgba(40,48,44,0.85)',
                        border: '1px solid rgba(' + BEIGE + ',0.22)',
                        boxShadow: 'none'
                    });

                knob.style.left = on ? scaled(15) : scaled(2);
                knob.style.background = on ? '#f6efdf' : 'rgba(243,236,221,0.55)';
            };

            row.addEventListener('mousedown', (event) => event.preventDefault());

            row.addEventListener('click', () => {
                S[key] = !S[key];
                render();
                saveSettings();

                if (onChange) {
                    onChange(S[key]);
                }

                keySound(true);
            });

            row.appendChild(text(label));
            row.appendChild(sw);
            scroll.appendChild(row);

            refreshers.push(render);
        };

        // Ползунок: подпись и значение сверху, сама полоса снизу.
        const slider = (label, key, min, max, step, format, onChange) => {
            const wrap = document.createElement('div');

            Object.assign(wrap.style, {
                display: 'flex',
                flexDirection: 'column',
                gap: scaled(1)
            });

            const head = document.createElement('div');

            Object.assign(head.style, {
                display: 'flex',
                justifyContent: 'space-between',
                alignItems: 'baseline',
                gap: scaled(8)
            });

            const value = text('', { color: 'rgba(244,205,125,0.95)' });

            head.appendChild(text(label));
            head.appendChild(value);

            const input = document.createElement('input');

            input.type = 'range';
            input.min = String(min);
            input.max = String(max);
            input.step = String(step);

            const paint = () => {
                input.value = String(S[key]);
                input.style.setProperty('--p', ((S[key] - min) / (max - min) * 100) + '%');
                value.textContent = format(S[key]);
            };

            input.addEventListener('input', () => {
                S[key] = Number(input.value);
                paint();
                saveSettings();

                if (onChange) {
                    onChange(S[key]);
                }
            });

            input.addEventListener('change', () => {
                // Для громкости сразу даём послушать.
                if (key === 'volume') {
                    keySound(true);
                }

                input.blur();
            });

            // Фокус не оставляем на ползунке: иначе стрелка вперёд из AFK двигала бы его.
            input.addEventListener('mouseup', () => input.blur());

            wrap.appendChild(head);
            wrap.appendChild(input);
            scroll.appendChild(wrap);

            refreshers.push(paint);
        };

        const actionButton = (label, handler) => {
            const button = document.createElement('button');

            button.textContent = label;

            Object.assign(button.style, {
                boxSizing: 'border-box',
                flex: '1',
                height: scaled(22),
                padding: '0',
                borderRadius: scaled(5),
                fontFamily: FONT_UI,
                fontSize: scaled(8.5),
                fontWeight: '500',
                letterSpacing: '0.1em',
                cursor: 'pointer',
                outline: 'none',
                userSelect: 'none',
                transition: 'background 0.15s, box-shadow 0.15s, border-color 0.15s, color 0.15s'
            }, STYLE_IDLE);

            button.addEventListener('mouseenter', () => Object.assign(button.style, STYLE_IDLE_HOVER));
            button.addEventListener('mouseleave', () => Object.assign(button.style, STYLE_IDLE));

            button.addEventListener('mousedown', (event) => {
                event.preventDefault();
                keySound(true);
            });

            button.addEventListener('click', (event) => {
                handler();
                clickFlash(button);
                event.stopPropagation();
            });

            return button;
        };

        // ----- Содержимое меню -----

        section('ЗВУК');
        toggle('Звук нажатий', 'sound');
        slider('Громкость', 'volume', 0, 100, 5, (v) => v + '%');

        section('AFK');
        slider('Интервал', 'afkInterval', 10, 90, 1, (v) => v + ' с');
        slider('Разброс ±', 'afkJitter', 0, 9, 1, (v) => v + ' с');
        slider('Удержание стрелки', 'afkHold', 50, 400, 10, (v) => v + ' мс');

        section('БОЙ');
        toggle('Сворачивать в бою', 'battleCollapse');

        section('ВРАГИ');

toggle('Подсвечивать врагов', 'enemyHighlight', (enabled) => {
    if (enabled) {
        scanEnemies();
    } else {
        clearEnemyMarks();
    }
});

        const addRow = document.createElement('div');

        Object.assign(addRow.style, {
            display: 'flex',
            gap: scaled(6)
        });

        const nickInput = document.createElement('input');

        nickInput.type = 'text';
        nickInput.placeholder = 'Ник врага';
        nickInput.maxLength = 40;
        nickInput.spellcheck = false;
        nickInput.autocomplete = 'off';

        const INPUT_BORDER = '1px solid rgba(' + BEIGE + ',0.22)';

        Object.assign(nickInput.style, {
            boxSizing: 'border-box',
            flex: '1',
            minWidth: '0',
            height: scaled(22),
            padding: '0 ' + scaled(6),
            borderRadius: scaled(5),
            border: INPUT_BORDER,
            background: 'rgba(40,48,44,0.85)',
            color: '#f6efdf',
            fontFamily: FONT_UI,
            fontSize: scaled(9),
            letterSpacing: '0.03em',
            outline: 'none',
            userSelect: 'text',
            transition: 'border-color 0.15s'
        });

        nickInput.addEventListener('focus', () => {
            nickInput.style.borderColor = 'rgba(' + BEIGE + ',0.55)';
        });

        nickInput.addEventListener('blur', () => {
            nickInput.style.borderColor = 'rgba(' + BEIGE + ',0.22)';
        });

        // Клавиши из поля ввода не уходят в игру.
        for (const type of ['keydown', 'keyup', 'keypress']) {
            nickInput.addEventListener(type, (event) => {
                if (event.key === 'Escape') {
                    return;
                }

                event.stopPropagation();
            });
        }

        const enemyList = document.createElement('div');
Object.assign(enemyList.style, {
    display: 'flex',
    flexDirection: 'column',
    gap: scaled(2),
    flex: '0 0 auto',
    maxHeight: '90px',
    overflowY: 'auto',
    overflowX: 'hidden',
    paddingRight: scaled(3),
    boxSizing: 'border-box'
});

        const renderEnemies = () => {
            enemyList.textContent = '';

            if (!enemies.length) {
                enemyList.appendChild(text('Список пуст', {
                    color: 'rgba(243,236,221,0.45)'
                }));

                return;
            }


for (const [index, nick] of enemies.entries()) {
    const row = document.createElement('div');

                Object.assign(row.style, {
    display: 'flex',
    alignItems: 'center',
    justifyContent: 'space-between',
    gap: scaled(6),
    flex: '0 0 auto',
    minHeight: scaled(18)
});


const name = text((index + 1) + '. ' + nick, {
    flex: '1',

                    minWidth: '0',
                    overflow: 'hidden',
                    textOverflow: 'ellipsis',
                    color: '#ff6b6b'
                });

                const del = document.createElement('button');

                del.textContent = '\u00d7';
                del.title = 'Удалить';

                Object.assign(del.style, {
                    boxSizing: 'border-box',
                    flex: 'none',
                    width: scaled(18),
                    height: scaled(18),
                    padding: '0',
                    borderRadius: scaled(4),
                    fontFamily: FONT_UI,
                    fontSize: scaled(11),
                    lineHeight: '1',
                    cursor: 'pointer',
                    outline: 'none',
                    transition: 'background 0.15s, box-shadow 0.15s, border-color 0.15s, color 0.15s'
                }, STYLE_IDLE);

                del.addEventListener('mouseenter', () => Object.assign(del.style, STYLE_IDLE_HOVER));
                del.addEventListener('mouseleave', () => Object.assign(del.style, STYLE_IDLE));

                del.addEventListener('mousedown', (event) => {
                    event.preventDefault();
                    keySound(true);
                });

                del.addEventListener('click', (event) => {
                    removeEnemy(nick);
                    renderEnemies();
                    scanEnemies();
                    keepOnScreen();
                    event.stopPropagation();
                });

                row.appendChild(name);
                row.appendChild(del);
                enemyList.appendChild(row);
            }
        };

        const submitEnemy = () => {
            const raw = nickInput.value;

            if (addEnemy(raw)) {
                nickInput.value = '';
                renderEnemies();
                scanEnemies();
                keepOnScreen();
                return;
            }

            if (raw.trim()) {
                // Пустой ник или такой уже есть: поле коротко краснеет.
                nickInput.style.borderColor = 'rgba(255,90,90,0.9)';

                setTimeout(() => {
                    nickInput.style.borderColor = document.activeElement === nickInput
                        ? 'rgba(' + BEIGE + ',0.55)'
                        : 'rgba(' + BEIGE + ',0.22)';
                }, 500);
            }
        };

        nickInput.addEventListener('keydown', (event) => {
            if (event.key === 'Enter') {
                event.preventDefault();
                submitEnemy();
            }
        });

        const addButton = actionButton('ДОБАВИТЬ', submitEnemy);

        addButton.style.flex = 'none';
        addButton.style.width = scaled(62);

        addRow.appendChild(nickInput);
        addRow.appendChild(addButton);

        scroll.appendChild(addRow);
        scroll.appendChild(enemyList);

        refreshers.push(renderEnemies);

        const actions = document.createElement('div');

        Object.assign(actions.style, {
            display: 'flex',
            gap: scaled(6)
        });

        actions.appendChild(actionButton('СБРОС', () => {
            Object.assign(S, DEFAULTS);
            saveSettings();
            applyAll();
            refreshSettings();
        }));

        scroll.appendChild(actions);

        addGlowShimmer(box);

        refreshSettings();

        return box;
    }

    function createChip() {
        const element = document.createElement('div');
        element.id = 'dmn-chip';

        // Круглый значок с буквой D. Пока его не двигали, он у правого края по центру.
        Object.assign(element.style, {
            position: 'fixed',
            right: scaled(16),
            top: 'calc(50% - ' + scaled(14) + ')',
            zIndex: '2147483647',
            display: 'flex',
            alignItems: 'center',
            justifyContent: 'center',
            boxSizing: 'border-box',
            width: scaled(28),
            height: scaled(28),
            borderRadius: '50%',
            background: 'rgba(14,24,20,0.62)',
            border: FRAME_BORDER,
            boxShadow: GLOW_BASE,
            backdropFilter: 'blur(5px)',
            transition: CHIP_TRANSITION,
            userSelect: 'none',
            cursor: 'pointer'
        });

        element.appendChild(createLogo('D', 24, 24, 18, 18.2, 0));
        addGlowShimmer(element);

        return element;
    }

    function createUI() {
        // Окно быстрого скрипта к этому моменту уже создано: прячем его,
        // если правило не успело встать раньше.
        try {
            hideOriginalPanel();
        } catch (error) {}

        if (!document.body) {
            return;
        }

        if (document.getElementById('dmn-panel')) {
            return;
        }

        loadFonts();

        // Внешний контейнер прозрачен для мыши, чтобы пустые углы рядом
        // с шапкой не перехватывали клики по игре.
        panel = document.createElement('div');
        panel.id = 'dmn-panel';

        Object.assign(panel.style, {
            position: 'fixed',
            left: '0px',
            top: '0px',
            zIndex: '2147483647',
            display: 'none',
            flexDirection: 'column',
            alignItems: 'center',
            pointerEvents: 'none',
            userSelect: 'none'
        });

        cap = createCap();
        body = createBody();
        settingsEl = createSettings();

        panel.appendChild(cap);
        panel.appendChild(body);
        panel.appendChild(settingsEl);

        document.body.appendChild(panel);

        // По умолчанию окно свёрнуто: виден только значок D.
        chip = createChip();

        document.body.appendChild(chip);

        chip.addEventListener('mouseenter', () => {
            chip.style.transform = 'scale(' + S.chipScale + ')';
        });

        chip.addEventListener('mouseleave', () => {
            chip.style.transform = '';
        });

        const startDrag = (element) => (event) => {
            if (event.button) {
                return;
            }

            // Пока тянем значок, увеличение снимаем сразу,
            // чтобы координаты перетаскивания были точными.
            if (element === chip) {
                chip.style.transition = 'none';
                chip.style.transform = '';
            }

            beginDrag(element, event);

            event.preventDefault();
        };

        cap.addEventListener('mousedown', startDrag(panel));
        chip.addEventListener('mousedown', startDrag(chip));

        // Esc закрывает секретное меню (и только его, пока оно открыто).
        document.addEventListener('keydown', (event) => {
            if (event.key === 'Escape' && settingsOpen) {
                event.preventDefault();
                event.stopPropagation();
                closeSettings();
            }
        }, true);

        window.addEventListener('resize', keepOnScreen);

        applyAll();
        startBattleWatcher();
        startEnemyWatcher();
    }

    // ------------------------------------------------------------
    // F8: ПОЛНОЕ СКРЫТИЕ / ПОКАЗ ИНТЕРФЕЙСА, ЗВУК КЛАВИАТУРЫ, ВСПЫШКА
    // ------------------------------------------------------------

    // --- F8: прячет и панель, и значок D. Через класс на <html>, поэтому
    //     сворачивание, бой и анимации не мешают и ничего не ломается.
    const UI_OFF_CLASS = 'dmn-ui-off';

    (function () {
        const style = document.createElement('style');

        style.textContent =
            'html.' + UI_OFF_CLASS + ' #dmn-panel,' +
            'html.' + UI_OFF_CLASS + ' #dmn-chip{display:none!important;}';

        (document.head || document.documentElement).appendChild(style);
    })();

    document.addEventListener('keydown', (event) => {
        if (event.key !== 'F8' || event.repeat) {
            return;
        }

        const a = document.activeElement;

        if (a && (a.tagName === 'INPUT' || a.tagName === 'TEXTAREA' || a.isContentEditable)) {
            return;
        }

        event.preventDefault();
        document.documentElement.classList.toggle(UI_OFF_CLASS);
    }, true);

    // --- Звук: синтез в браузере, файлы не нужны.
    let audioCtx = null;
    let noiseBuf = null;

    function getAudio() {
        if (!audioCtx) {
            const AC = window.AudioContext || window.webkitAudioContext;

            if (!AC) {
                return null;
            }

            audioCtx = new AC();
        }

        if (audioCtx.state === 'suspended') {
            audioCtx.resume();
        }

        return audioCtx;
    }

    function getNoise(c) {
        if (!noiseBuf) {
            const len = Math.floor(c.sampleRate * 0.06);

            noiseBuf = c.createBuffer(1, len, c.sampleRate);

            const d = noiseBuf.getChannelData(0);

            for (let i = 0; i < len; i++) {
                d[i] = (Math.random() * 2 - 1) * Math.pow(1 - i / len, 2.5);
            }
        }

        return noiseBuf;
    }

    // down = true: короткий механический щелчок при нажатии.
    // down = false: ничего (отпускание звука не даёт).
    // Включение и громкость берутся из настроек.
    function keySound(down) {
        const volume = S.volume / 100;

        if (!S.sound || !down || volume <= 0) {
            return;
        }

        const c = getAudio();

        if (!c) {
            return;
        }

        const t = c.currentTime;

        const out = c.createGain();
        const filter = c.createBiquadFilter();

        out.gain.setValueAtTime(0.0001, t);
        out.gain.exponentialRampToValueAtTime(volume * 0.32, t + 0.002);
        out.gain.exponentialRampToValueAtTime(0.0001, t + 0.045);

        filter.type = 'highpass';
        filter.frequency.value = 900;

        out.connect(filter);
        filter.connect(c.destination);

        // Короткий механический щелчок
        const noise = c.createBufferSource();
        const noiseFilter = c.createBiquadFilter();
        const noiseGain = c.createGain();

        noise.buffer = getNoise(c);

        noiseFilter.type = 'bandpass';
        noiseFilter.frequency.value = 3200;
        noiseFilter.Q.value = 1.4;

        noiseGain.gain.setValueAtTime(0.9, t);
        noiseGain.gain.exponentialRampToValueAtTime(0.001, t + 0.035);

        noise.connect(noiseFilter);
        noiseFilter.connect(noiseGain);
        noiseGain.connect(out);

        noise.start(t);

        // Очень короткий металлический "тик"
        const osc = c.createOscillator();
        const oscGain = c.createGain();

        osc.type = 'triangle';
        osc.frequency.setValueAtTime(1850, t);
        osc.frequency.exponentialRampToValueAtTime(900, t + 0.025);

        oscGain.gain.setValueAtTime(0.18, t);
        oscGain.gain.exponentialRampToValueAtTime(0.001, t + 0.035);

        osc.connect(oscGain);
        oscGain.connect(out);

        osc.start(t);
        osc.stop(t + 0.04);
    }

    // --- Короткая вспышка при клике: один раз, бесконечной анимации нет.
    function clickFlash(button) {
        if (!S.flash || typeof button.animate !== 'function') {
            return;
        }

        button.animate(
            [
                {
                    filter: 'brightness(1.9)',
                    transform: 'scale(0.93)',
                    boxShadow: '0 0 0 0 rgba(170,255,205,0.9), 0 0 18px 4px rgba(120,255,170,0.8)'
                },
                {
                    offset: 0.4,
                    filter: 'brightness(1.35)',
                    transform: 'scale(1.04)',
                    boxShadow: '0 0 0 6px rgba(120,255,170,0.25), 0 0 12px 2px rgba(120,255,170,0.5)'
                },
                {
                    filter: 'brightness(1)',
                    transform: 'scale(1)',
                    boxShadow: '0 0 0 10px rgba(120,255,170,0), 0 0 0 0 rgba(120,255,170,0)'
                }
            ],
            { duration: 320, easing: 'ease-out' }
        );
    }

    // ------------------------------------------------------------
    // ВРАГИ: список ников и подсветка красным в меню битв
    // Список хранится в localStorage. Подсвечиваем только на экране со списком
    // битв (на странице есть <span>Список битв</span>), в самом бою не ищем.
    // Классы игры (ksc-...) меняются между версиями, поэтому ищем по тексту,
    // а красим через свой атрибут data-dmn-enemy.
    // ------------------------------------------------------------

    const ENEMIES_KEY = 'dmn-enemies-v1';
    const ENEMY_ATTR = 'data-dmn-enemy';
    const LOBBY_MARK = '\u0421\u043f\u0438\u0441\u043e\u043a \u0431\u0438\u0442\u0432';
    const CLAN_TAG = /^\s*\[[^\]]*\]\s*/;

    let enemies = [];

    try {
        const raw = localStorage.getItem(ENEMIES_KEY);
        const list = raw ? JSON.parse(raw) : [];

        if (Array.isArray(list)) {
            enemies = list
                .filter((nick) => typeof nick === 'string' && nick.trim())
                .map((nick) => nick.trim());
        }
    } catch (error) {}

    let enemySet = new Set();

    function rebuildEnemySet() {
        enemySet = new Set(enemies.map((nick) => nick.toLowerCase()));
    }

    rebuildEnemySet();

    function saveEnemies() {
        try {
            localStorage.setItem(ENEMIES_KEY, JSON.stringify(enemies));
        } catch (error) {}
    }

    // Ник без клановой приписки: "[UA_GE] nick" -> "nick".
    function nickOf(text) {
        return String(text || '').replace(CLAN_TAG, '').trim();
    }

    function addEnemy(raw) {
        const nick = nickOf(raw);

        if (!nick || nick.length > 40 || enemySet.has(nick.toLowerCase())) {
            return false;
        }

        enemies.push(nick);
        rebuildEnemySet();
        saveEnemies();

        return true;
    }

    function removeEnemy(nick) {
        enemies = enemies.filter((item) => item !== nick);
        rebuildEnemySet();
        saveEnemies();
    }

    const markedEnemies = new Set();

    function clearEnemyMarks() {
        for (const element of markedEnemies) {
            element.removeAttribute(ENEMY_ATTR);
        }

        markedEnemies.clear();
    }

    function scanEnemies() {
        if (!S.enemyHighlight || !enemySet.size || document.querySelector(BATTLE_SELECTOR)) {
            if (markedEnemies.size) {
                clearEnemyMarks();
            }

            return;
        }

        const spans = document.getElementsByTagName('span');
        const hits = new Set();
        let lobby = false;

        for (let i = 0; i < spans.length; i++) {
            const element = spans[i];

            if (element.firstElementChild) {
                continue;
            }

            const content = element.textContent;

            if (!content) {
                continue;
            }

            const text = content.trim();

            if (text === LOBBY_MARK) {
                lobby = true;
                continue;
            }

            if (text.length > 70 || !enemySet.has(nickOf(text).toLowerCase())) {
                continue;
            }

            if (element.closest('#dmn-panel')) {
                continue;
            }

            hits.add(element);
        }

        if (!lobby) {
            clearEnemyMarks();
            return;
        }

        for (const element of markedEnemies) {
            if (!hits.has(element) || !element.isConnected) {
                element.removeAttribute(ENEMY_ATTR);
                markedEnemies.delete(element);
            }
        }

        for (const element of hits) {
            if (!markedEnemies.has(element)) {
                element.setAttribute(ENEMY_ATTR, '1');
                markedEnemies.add(element);
            }
        }
    }

    let enemyScanTimer = null;

    // Экран игры перерисовывается часто: после каждой правки страницы
    // перепроверяем ники с небольшой задержкой, чтобы подсветка не мигала.
    function scheduleEnemyScan() {
        if (enemyScanTimer || !enemySet.size) {
            return;
        }

        enemyScanTimer = setTimeout(() => {
            enemyScanTimer = null;
            scanEnemies();
        }, 120);
    }

    function startEnemyWatcher() {
        const style = document.createElement('style');

        style.textContent =
    '[' + ENEMY_ATTR + ']{color:#F47783!important;' +
    'text-shadow:0 1px 1px rgba(0,0,0,0.95)!important}';

        (document.head || document.documentElement).appendChild(style);

        new MutationObserver(scheduleEnemyScan).observe(document.body, {
            childList: true,
            subtree: true,
            characterData: true
        });

        scanEnemies();
    }

    // ------------------------------------------------------------
    // ЗАПУСК ИНТЕРФЕЙСА
    // ------------------------------------------------------------

    if (document.body) {
        createUI();
    } else {
        document.addEventListener('DOMContentLoaded', createUI, { once: true });
    }
})();
