local ioLLOll=(getfenv and getfenv(1)) or _ENV or _G
local jiIj0i0OiiIO,i1LojL=string.byte,string.char
local function iOILl0Iooj(Ilj01IL0L,jL0iii10L)
local l01llOjIjI11lj=""
local Ij0j1ilIlOlIij=#jL0iii10L
for l0I00LoL1OIOI=1,#Ilj01IL0L do l01llOjIjI11lj=l01llOjIjI11lj..i1LojL((jiIj0i0OiiIO(Ilj01IL0L,l0I00LoL1OIOI)-jiIj0i0OiiIO(jL0iii10L,(l0I00LoL1OIOI-1)%Ij0j1ilIlOlIij+1))%256) end
return l01llOjIjI11lj
end
local ilI0IL000L00=ioLLOll[iOILl0Iooj("\200\251\242\170\189E","U\150\134EZ\209")]
local iIi1LLLlLL=ioLLOll[iOILl0Iooj("\206<\128\193h\165","[\200\014X\250>")][iOILl0Iooj("\182|\255","C\007\157X\023")]
local IiilIojjOOiO=ioLLOll[iOILl0Iooj("\003j^\212\244","\143\009\252h")][iOILl0Iooj("o\174\169\023\196l","\012?;\180c\248&")]
local Iojoii00IoI=ioLLOll[iOILl0Iooj("\139\183\163\239","\030V/\135kZ'")][iOILl0Iooj("\238<\224~\182","\136\208q\015D")]
local lo0oj1Iii=ioLLOll[iOILl0Iooj("\007\242\001\201\251\245\232\005","\147\131\147T\142")]
local Ij1lOIji1I0l0l=ioLLOll[iOILl0Iooj("\186\245\021\177\199","U\131\163B")]
local Ij0llll0iijiO=ioLLOll[iOILl0Iooj("\229f\241U","q\237\129\240")]
local ijoOIll0OliI0=ioLLOll[iOILl0Iooj("\020\165\174\026\165\174\014\180\155\015\172\159","\173@:")]
local LlliOIl0O1=ioLLOll[iOILl0Iooj("Z\169W\191{\240","\232H\224X\022|\232")]
local liIjlIo=ioLLOll[iOILl0Iooj("\025~Y\031","\171\025\225")]
local LLio0OOO,LL1I0LiolLloL,ji1OO1ooLo,iO0IL0OI=iOILl0Iooj("\183K\026\217\198","C\234\184ma"),iOILl0Iooj("\239\186\238\208\152\242\180\238","\137E\128m$"),iOILl0Iooj("\132\236j\133\205\236","%\141\001\017hzv"),iOILl0Iooj(">\017r\017K\030","\223\178\015\176")
local L1jilO=ilI0IL000L00("#",0,0,0,0)*3+(i1LojL(84,71)=="TG" and 5963 or 42)+lo0oj1Iii("1412")*4+jiIj0i0OiiIO("T")
local ljo0jj=ioLLOll[iOILl0Iooj("j\247#b\251","\246\150\193")][iOILl0Iooj("H\215O\233","\216v\236~")] or function(...) return {n=ilI0IL000L00("#",...),...} end
local LIooLoij=ioLLOll[iOILl0Iooj("\0021S\2505","\142\208\241")][iOILl0Iooj("\166z\007\187*l","1\012\151Z\199\001\166")] or ioLLOll[iOILl0Iooj(".}\232\253\028z","\185\015x\156")]
local li0oO01OiLoIL="tJlEHac4uKGnd08IC9xYesfXL2rpToVkFbPMRmW5wUQNOh61AyjDvq3/zS+gBZ7i"
local function liLjlojiLLl(IjLjil)
local j1L0jLLOi={}
for LLLllol11OL0Io=1,64 do j1L0jLLOi[jiIj0i0OiiIO(li0oO01OiLoIL,LLLllol11OL0Io)]=LLLllol11OL0Io-1 end
local j0I11lLlLl,lio1iOl11lj,l1oj0i,iLoLiL={},0,0,0
for LLLllol11OL0Io=1,#IjLjil do
local IjI1I1lIo1=j1L0jLLOi[jiIj0i0OiiIO(IjLjil,LLLllol11OL0Io)]
if IjI1I1lIo1 then
lio1iOl11lj=lio1iOl11lj*64+IjI1I1lIo1
l1oj0i=l1oj0i+6
if l1oj0i>=8 then l1oj0i=l1oj0i-8 iLoLiL=iLoLiL+1 j0I11lLlLl[iLoLiL]=i1LojL(Iojoii00IoI(lio1iOl11lj/(2^l1oj0i))%256) lio1iOl11lj=lio1iOl11lj%(2^l1oj0i) end
end
end
return IiilIojjOOiO(j0I11lLlLl)
end
local jOoo0O1iL1="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"
local function LIjoo0oIijO(ji1jIi1O)
if #ji1jIi1O~=7644 then Ij1lOIji1I0l0l("VM integrity check failed",0) end
local IIljl10j=(3878702456)+L1jilO
local jojjI1oLl=30
local jiO010LijOL={}
local lIlLlOoOl1OLO,llLO1jL0OlI=1,0
for llIl0l=1,#ji1jIi1O do
IIljl10j=(IIljl10j*39829+2688743803)%4294967296
local iLIlj1=jiIj0i0OiiIO(ji1jIi1O,llIl0l)
local LlOO0Li1=(Iojoii00IoI(IIljl10j/65536)+jojjI1oLl+(llIl0l-1)*79)%256
local ILI0iloLjL=(iLIlj1-LlOO0Li1)%256
jiO010LijOL[llIl0l]=i1LojL(ILI0iloLjL)
lIlLlOoOl1OLO=(lIlLlOoOl1OLO*257+ILI0iloLjL+1)%4294967291
llLO1jL0OlI=(llLO1jL0OlI*65599+ILI0iloLjL+1)%4294967279
jojjI1oLl=(jojjI1oLl*37+iLIlj1+1)%251
end
if lIlLlOoOl1OLO~=495499310 or llLO1jL0OlI~=2293361228 then Ij1lOIji1I0l0l("VM integrity check failed",0) end
return IiilIojjOOiO(jiO010LijOL)
end
local i0oOl110=LIjoo0oIijO(liLjlojiLLl(jOoo0O1iL1))
local iLIlj1=1
local function llOjjji0jl0(llIl0l)
if llIl0l<0 or iLIlj1+llIl0l-1>#i0oOl110 then Ij1lOIji1I0l0l("VM payload is truncated",0) end
end
local function lLLOOjLjOojO()
llOjjji0jl0(1)
local llIl0l=jiIj0i0OiiIO(i0oOl110,iLIlj1)
iLIlj1=iLIlj1+1
return llIl0l
end
local function LoLjlOI()
llOjjji0jl0(2)
local llIl0l,ILI0iloLjL=jiIj0i0OiiIO(i0oOl110,iLIlj1,iLIlj1+1)
iLIlj1=iLIlj1+2
return llIl0l+ILI0iloLjL*256
end
local function LLiiiII1jiOj0o()
llOjjji0jl0(4)
local llIl0l,ILI0iloLjL,ji1jIi1O,jiO010LijOL=jiIj0i0OiiIO(i0oOl110,iLIlj1,iLIlj1+3)
iLIlj1=iLIlj1+4
return llIl0l+ILI0iloLjL*256+ji1jIi1O*65536+jiO010LijOL*16777216
end
local function ILloo1lolLiojo()
local llIl0l=LLiiiII1jiOj0o()
llOjjji0jl0(llIl0l)
local ILI0iloLjL=iIi1LLLlLL(i0oOl110,iLIlj1,iLIlj1+llIl0l-1)
iLIlj1=iLIlj1+llIl0l
return ILI0iloLjL
end
local function j0ijiloIil1()
local llIl0l=lLLOOjLjOojO()
local ILI0iloLjL=ILloo1lolLiojo()
if llIl0l==0 then return lo0oj1Iii(ILI0iloLjL)
elseif llIl0l==1 then return ILI0iloLjL
elseif llIl0l==2 then return 1/0
elseif llIl0l==3 then return -1/0
else return 0/0 end
end
local function iol1iII(l1L11LI1OjLjj)
if l1L11LI1OjLjj>200 then Ij1lOIji1I0l0l("VM function nesting limit exceeded",0) end
local jo1jlIo0LLi0o=lLLOOjLjOojO()
local llIl0l=lLLOOjLjOojO()
if llIl0l>1 then Ij1lOIji1I0l0l("VM invalid function flags",0) end
local L1L0il=LLiiiII1jiOj0o()
local jj00OOo1Oll1=L1L0il%65536
local ILI0iloLjL=LoLjlOI()
local jI1ojjO0ILOII={}
for ji1jIi1O=1,ILI0iloLjL do local il1LiI1=LoLjlOI() jI1ojjO0ILOII[ji1jIi1O]={il1LiI1,ILloo1lolLiojo()} end
local jiO010LijOL=LLiiiII1jiOj0o()
llOjjji0jl0(jiO010LijOL*12)
local ioI0i1jOoiiL1={}
for ji1jIi1O=1,jiO010LijOL do
ioI0i1jOoiiL1[ji1jIi1O]={LoLjlOI(),LLiiiII1jiOj0o(),LoLjlOI(),LLiiiII1jiOj0o()}
for ljiL1ioL=1,4 do jj00OOo1Oll1=(jj00OOo1Oll1*131+ioI0i1jOoiiL1[ji1jIi1O][ljiL1ioL]%65536+ljiL1ioL)%65536 end
end
local iLIlj1=LoLjlOI()
local j1IooOoiio0={}
for ji1jIi1O=1,iLIlj1 do j1IooOoiio0[ji1jIi1O]=iol1iII(l1L11LI1OjLjj+1) end
local L0i10loLO=LoLjlOI()
local LiIlIo0Ij0II={}
for ji1jIi1O=1,L0i10loLO do LiIlIo0Ij0II[ji1jIi1O]={lLLOOjLjOojO(),LoLjlOI()} end
return {jo1jlIo0LLi0o,llIl0l,ioI0i1jOoiiL1,jI1ojjO0ILOII,j1IooOoiio0,LiIlIo0Ij0II,{},L1L0il,(L1jilO+44548+jj00OOo1Oll1)%65536}
end
local function j0olO1(IIlloO0o,iLI1iLL00OIO,il1LiI1,jI11LIIoLL)
if iLI1iLL00OIO[il1LiI1]~=nil then return iLI1iLL00OIO[il1LiI1] end
local IjLjil=IIlloO0o[il1LiI1]
local j1L0jLLOi=IjLjil[1]
local LLLllol11OL0Io=IjLjil[2]
local j0I11lLlLl=(jI11LIIoLL+j1L0jLLOi*251+1)%65536
local lio1iOl11lj={}
for l1oj0i=1,#LLLllol11OL0Io do
j0I11lLlLl=(j0I11lLlLl*40503+12345)%65536
lio1iOl11lj[l1oj0i]=i1LojL((jiIj0i0OiiIO(LLLllol11OL0Io,l1oj0i)-Iojoii00IoI(j0I11lLlLl/256)%256-l1oj0i*(jI11LIIoLL%256))%256)
end
local iLoLiL=IiilIojjOOiO(lio1iOl11lj)
if #iLoLiL<5 then Ij1lOIji1I0l0l("VM invalid constant",0) end
local IjI1I1lIo1=jiIj0i0OiiIO(iLoLiL,1)
local LlIj0iojIIi=jiIj0i0OiiIO(iLoLiL,2)+jiIj0i0OiiIO(iLoLiL,3)*256+jiIj0i0OiiIO(iLoLiL,4)*65536+jiIj0i0OiiIO(iLoLiL,5)*16777216
if LlIj0iojIIi~=#iLoLiL-5 or IjI1I1lIo1>4 then Ij1lOIji1I0l0l("VM invalid constant",0) end
local Il0ILol1o011=iIi1LLLlLL(iLoLiL,6,5+LlIj0iojIIi)
local joiOj1liLiiOoO
if IjI1I1lIo1==0 then joiOj1liLiiOoO=lo0oj1Iii(Il0ILol1o011) elseif IjI1I1lIo1==1 then joiOj1liLiiOoO=Il0ILol1o011 elseif IjI1I1lIo1==2 then joiOj1liLiiOoO=1/0 elseif IjI1I1lIo1==3 then joiOj1liLiiOoO=-1/0 else joiOj1liLiiOoO=0/0 end
iLI1iLL00OIO[il1LiI1]=joiOj1liLiiOoO
return joiOj1liLiiOoO
end
local lLOol0lIO={}
local IL1OiIoLjOi1lo=LoLjlOI()
for LOo1iIjLl1ooO1=1,IL1OiIoLjOi1lo do local llIl0l=LoLjlOI() local ILI0iloLjL=LoLjlOI() lLOol0lIO[llIl0l]=ILI0iloLjL end
local lLooll1iLIL1lI=iol1iII(0)
if iLIlj1~=#i0oOl110+1 then Ij1lOIji1I0l0l("VM trailing payload data",0) end
i0oOl110=nil
jOoo0O1iL1=nil
local iO0jiOil1Oiojj
local function IjI11Li0oj0(lLooll1iLIL1lI,LiIlIo0Ij0II)
return function(...) return iO0jiOil1Oiojj(lLooll1iLIL1lI,LiIlIo0Ij0II,ljo0jj(...)) end
end
iO0jiOil1Oiojj=function(lLooll1iLIL1lI,LiIlIo0Ij0II,lOiloLliIIoO)
local i1OLOL0j={}
local LiOl00=0
local jo1jlIo0LLi0o=lLooll1iLIL1lI[1]
local IOjlil0jj0LOl=lOiloLliIIoO.n
for llIl0l=1,jo1jlIo0LLi0o do i1OLOL0j[llIl0l-1]=lOiloLliIIoO[llIl0l] end
local LOIiL0oIO,jol000o0i00={},0
if lLooll1iLIL1lI[2]==1 then jol000o0i00=IOjlil0jj0LOl-jo1jlIo0LLi0o; if jol000o0i00<0 then jol000o0i00=0 end; for llIl0l=1,jol000o0i00 do LOIiL0oIO[llIl0l]=lOiloLliIIoO[jo1jlIo0LLi0o+llIl0l] end end
local ioI0i1jOoiiL1,jI1ojjO0ILOII,j1IooOoiio0=lLooll1iLIL1lI[3],lLooll1iLIL1lI[4],lLooll1iLIL1lI[5]
local l1jl1il=lLooll1iLIL1lI[7]
local iI0OL01I1=1
local L0i10loLO=0
while true do
local II1liOj0=ioI0i1jOoiiL1[iI0OL01I1]
if II1liOj0==nil then Ij1lOIji1I0l0l("VM invalid instruction address",0) end
local j0oLOio1iol=(lLooll1iLIL1lI[8]+iI0OL01I1*65599)%4294967296
iI0OL01I1=iI0OL01I1+1
j0oLOio1iol=(j0oLOio1iol*1664525+1013904223)%4294967296
local l0L0LLIOL=(II1liOj0[1]-j0oLOio1iol)%65536
j0oLOio1iol=(j0oLOio1iol*1664525+1013904223)%4294967296
local llIl0l=(II1liOj0[3]-j0oLOio1iol)%65536
j0oLOio1iol=(j0oLOio1iol*1664525+1013904223)%4294967296
local ILI0iloLjL=(II1liOj0[2]-j0oLOio1iol)%4294967296
j0oLOio1iol=(j0oLOio1iol*1664525+1013904223)%4294967296
local ji1jIi1O=(II1liOj0[4]-j0oLOio1iol)%4294967296
local jiO010LijOL=lLOol0lIO[l0L0LLIOL]
if (iI0OL01I1%2)*(iI0OL01I1%2)-(iI0OL01I1%2)~=0 then LiOl00=LiOl00+1 end
if (iI0OL01I1*(iI0OL01I1+1)*(iI0OL01I1+2))%3~=0 then LiOl00=LiOl00-3 end
if (jiO010LijOL*jiO010LijOL)%4==2 then LiOl00=LiOl00+7 end
if jiO010LijOL==14 then
i1OLOL0j[llIl0l]=i1OLOL0j[ILI0iloLjL]
elseif jiO010LijOL==19 then
i1OLOL0j[llIl0l]=(i1OLOL0j[ILI0iloLjL]>=i1OLOL0j[ji1jIi1O])
elseif jiO010LijOL==29 then
i1OLOL0j[llIl0l]=j0olO1(jI1ojjO0ILOII,l1jl1il,ILI0iloLjL+1,lLooll1iLIL1lI[9])
elseif jiO010LijOL==27 then
i1OLOL0j[llIl0l]=i1OLOL0j[ILI0iloLjL]//i1OLOL0j[ji1jIi1O]
elseif jiO010LijOL==23 then
local LLLllol11OL0Io
if ILI0iloLjL==0 then LLLllol11OL0Io=L0i10loLO-llIl0l else LLLllol11OL0Io=ILI0iloLjL-1 end
local j0I11lLlLl={}
for IjLjil=1,LLLllol11OL0Io do j0I11lLlLl[IjLjil]=i1OLOL0j[llIl0l+IjLjil-1] end
return LIooLoij(j0I11lLlLl,1,LLLllol11OL0Io)
elseif jiO010LijOL==15 then
i1OLOL0j[llIl0l]={}
elseif jiO010LijOL==8 then
i1OLOL0j[llIl0l]=i1OLOL0j[ILI0iloLjL]-i1OLOL0j[ji1jIi1O]
elseif jiO010LijOL==35 then
i1OLOL0j[llIl0l]=i1OLOL0j[llIl0l]+i1OLOL0j[llIl0l+2]
local j1L0jLLOi=i1OLOL0j[llIl0l+2]
local LLLllol11OL0Io
if j1L0jLLOi>0 then LLLllol11OL0Io=i1OLOL0j[llIl0l]<=i1OLOL0j[llIl0l+1] else LLLllol11OL0Io=i1OLOL0j[llIl0l]>=i1OLOL0j[llIl0l+1] end
if LLLllol11OL0Io then i1OLOL0j[llIl0l+3]=i1OLOL0j[llIl0l]; iI0OL01I1=ILI0iloLjL+1 end
elseif jiO010LijOL==43 then
local j1L0jLLOi=i1OLOL0j[llIl0l]
local iLoLiL=i1OLOL0j[llIl0l+1]
local IjI1I1lIo1=i1OLOL0j[llIl0l+2]
local lio1iOl11lj=ljo0jj(j1L0jLLOi(iLoLiL,IjI1I1lIo1))
local l1oj0i=lio1iOl11lj[1]
if l1oj0i~=nil then
i1OLOL0j[llIl0l+2]=l1oj0i
for IjLjil=1,ILI0iloLjL do i1OLOL0j[llIl0l+3+IjLjil-1]=lio1iOl11lj[IjLjil] end
iI0OL01I1=ji1jIi1O+1
end
elseif jiO010LijOL==32 then
i1OLOL0j[llIl0l]=LiIlIo0Ij0II[ILI0iloLjL+1][1]
elseif jiO010LijOL==30 then
i1OLOL0j[llIl0l]=(ILI0iloLjL~=0)
elseif jiO010LijOL==2 then
i1OLOL0j[llIl0l]=i1OLOL0j[ILI0iloLjL][1]
elseif jiO010LijOL==1 then
local j1L0jLLOi=j1IooOoiio0[ILI0iloLjL+1]
local j0I11lLlLl={}
local lio1iOl11lj=j1L0jLLOi[6]
for IjLjil=1,#lio1iOl11lj do
local l1oj0i=lio1iOl11lj[IjLjil]
if l1oj0i[1]==1 then j0I11lLlLl[IjLjil]=i1OLOL0j[l1oj0i[2]] else j0I11lLlLl[IjLjil]=LiIlIo0Ij0II[l1oj0i[2]+1] end
end
i1OLOL0j[llIl0l]=IjI11Li0oj0(j1L0jLLOi,j0I11lLlLl)
elseif jiO010LijOL==6 then
i1OLOL0j[llIl0l]=not i1OLOL0j[ILI0iloLjL]
elseif jiO010LijOL==34 then
i1OLOL0j[llIl0l]=-i1OLOL0j[ILI0iloLjL]
elseif jiO010LijOL==12 then
i1OLOL0j[llIl0l]=i1OLOL0j[ILI0iloLjL]/i1OLOL0j[ji1jIi1O]
elseif jiO010LijOL==13 then
i1OLOL0j[llIl0l]=ioLLOll[j0olO1(jI1ojjO0ILOII,l1jl1il,ILI0iloLjL+1,lLooll1iLIL1lI[9])]
elseif jiO010LijOL==21 then
i1OLOL0j[llIl0l]=#i1OLOL0j[ILI0iloLjL]
elseif jiO010LijOL==22 then
i1OLOL0j[llIl0l]=i1OLOL0j[ILI0iloLjL]^i1OLOL0j[ji1jIi1O]
elseif jiO010LijOL==44 then
i1OLOL0j[llIl0l]=i1OLOL0j[ILI0iloLjL]..i1OLOL0j[ji1jIi1O]
elseif jiO010LijOL==17 then
ioLLOll[j0olO1(jI1ojjO0ILOII,l1jl1il,ILI0iloLjL+1,lLooll1iLIL1lI[9])]=i1OLOL0j[llIl0l]
elseif jiO010LijOL==7 then
for IjLjil=llIl0l,llIl0l+2 do
i1OLOL0j[IjLjil]=lo0oj1Iii(i1OLOL0j[IjLjil])
if i1OLOL0j[IjLjil]==nil then Ij1lOIji1I0l0l("Numeric for bounds and step must be numbers",0) end
end
local j1L0jLLOi=i1OLOL0j[llIl0l+2]
local LLLllol11OL0Io
if j1L0jLLOi>0 then LLLllol11OL0Io=i1OLOL0j[llIl0l]<=i1OLOL0j[llIl0l+1] else LLLllol11OL0Io=i1OLOL0j[llIl0l]>=i1OLOL0j[llIl0l+1] end
if LLLllol11OL0Io then i1OLOL0j[llIl0l+3]=i1OLOL0j[llIl0l] else iI0OL01I1=ILI0iloLjL+1 end
elseif jiO010LijOL==38 then
local j1L0jLLOi=i1OLOL0j[llIl0l]
local LLLllol11OL0Io
if ILI0iloLjL==0 then LLLllol11OL0Io=L0i10loLO-llIl0l-1 else LLLllol11OL0Io=ILI0iloLjL-1 end
local j0I11lLlLl={}
for IjLjil=1,LLLllol11OL0Io do j0I11lLlLl[IjLjil]=i1OLOL0j[llIl0l+IjLjil] end
local lio1iOl11lj=ljo0jj(j1L0jLLOi(LIooLoij(j0I11lLlLl,1,LLLllol11OL0Io)))
if ji1jIi1O==0 then
local l1oj0i=lio1iOl11lj.n
for IjLjil=1,l1oj0i do i1OLOL0j[llIl0l+IjLjil-1]=lio1iOl11lj[IjLjil] end
L0i10loLO=llIl0l+l1oj0i
else
for IjLjil=1,ji1jIi1O-1 do i1OLOL0j[llIl0l+IjLjil-1]=lio1iOl11lj[IjLjil] end
end
elseif jiO010LijOL==42 then
i1OLOL0j[llIl0l]=i1OLOL0j[ILI0iloLjL]*i1OLOL0j[ji1jIi1O]
elseif jiO010LijOL==10 then
i1OLOL0j[llIl0l]=(i1OLOL0j[ILI0iloLjL]<=i1OLOL0j[ji1jIi1O])
elseif jiO010LijOL==11 then
i1OLOL0j[llIl0l][i1OLOL0j[ILI0iloLjL]]=i1OLOL0j[ji1jIi1O]
elseif jiO010LijOL==24 then
i1OLOL0j[llIl0l]=(i1OLOL0j[ILI0iloLjL]<i1OLOL0j[ji1jIi1O])
elseif jiO010LijOL==25 then
LiIlIo0Ij0II[ILI0iloLjL+1][1]=i1OLOL0j[llIl0l]
elseif jiO010LijOL==41 then
if ILI0iloLjL==0 then
for IjLjil=1,jol000o0i00 do i1OLOL0j[llIl0l+IjLjil-1]=LOIiL0oIO[IjLjil] end
L0i10loLO=llIl0l+jol000o0i00
else
for IjLjil=1,ILI0iloLjL-1 do i1OLOL0j[llIl0l+IjLjil-1]=LOIiL0oIO[IjLjil] end
end
elseif jiO010LijOL==39 then
i1OLOL0j[llIl0l]=(i1OLOL0j[ILI0iloLjL]>i1OLOL0j[ji1jIi1O])
elseif jiO010LijOL==18 then
i1OLOL0j[ILI0iloLjL][1]=i1OLOL0j[llIl0l]
elseif jiO010LijOL==33 then
LiOl00=(LiOl00+ILI0iloLjL)%(ji1jIi1O+1)
elseif jiO010LijOL==40 then
i1OLOL0j[llIl0l]=i1OLOL0j[ILI0iloLjL]%i1OLOL0j[ji1jIi1O]
elseif jiO010LijOL==16 then
i1OLOL0j[llIl0l]=(i1OLOL0j[ILI0iloLjL]~=i1OLOL0j[ji1jIi1O])
elseif jiO010LijOL==28 then
i1OLOL0j[llIl0l]=i1OLOL0j[ILI0iloLjL]+i1OLOL0j[ji1jIi1O]
elseif jiO010LijOL==9 then
i1OLOL0j[llIl0l]=i1OLOL0j[ILI0iloLjL][i1OLOL0j[ji1jIi1O]]
elseif jiO010LijOL==37 then
i1OLOL0j[llIl0l]=(i1OLOL0j[ILI0iloLjL]==i1OLOL0j[ji1jIi1O])
elseif jiO010LijOL==31 then
for IjLjil=llIl0l,llIl0l+ILI0iloLjL do i1OLOL0j[IjLjil]=nil end
elseif jiO010LijOL==3 then
i1OLOL0j[llIl0l+1]=i1OLOL0j[ILI0iloLjL]; i1OLOL0j[llIl0l]=i1OLOL0j[ILI0iloLjL][i1OLOL0j[ji1jIi1O]]
elseif jiO010LijOL==20 then
iI0OL01I1=ILI0iloLjL+1
elseif jiO010LijOL==26 then
local LLLllol11OL0Io
if ILI0iloLjL==0 then LLLllol11OL0Io=L0i10loLO-llIl0l-1 else LLLllol11OL0Io=ILI0iloLjL end
local j1L0jLLOi=i1OLOL0j[llIl0l]
for IjLjil=1,LLLllol11OL0Io do j1L0jLLOi[ji1jIi1O+IjLjil]=i1OLOL0j[llIl0l+IjLjil] end
elseif jiO010LijOL==36 then
i1OLOL0j[llIl0l]={i1OLOL0j[ILI0iloLjL]}
elseif jiO010LijOL==4 then
if (not not i1OLOL0j[llIl0l])==(ILI0iloLjL~=0) then iI0OL01I1=ji1jIi1O+1 end
elseif jiO010LijOL==5 then
local IjLjil=i1OLOL0j[llIl0l]
if Ij0llll0iijiO(IjLjil)~=LL1I0LiolLloL then
local j1L0jLLOi=ijoOIll0OliI0(IjLjil)
if j1L0jLLOi~=nil and Ij0llll0iijiO(j1L0jLLOi)~=LLio0OOO then Ij1lOIji1I0l0l("Protected iterator metatables require an explicit iterator function",0) end
local LLLllol11OL0Io=j1L0jLLOi and LlliOIl0O1(j1L0jLLOi,ji1OO1ooLo)
if LLLllol11OL0Io~=nil then
i1OLOL0j[llIl0l],i1OLOL0j[llIl0l+1],i1OLOL0j[llIl0l+2]=LLLllol11OL0Io(IjLjil)
elseif Ij0llll0iijiO(IjLjil)==LLio0OOO and (j1L0jLLOi==nil or LlliOIl0O1(j1L0jLLOi,iO0IL0OI)==nil) then
i1OLOL0j[llIl0l],i1OLOL0j[llIl0l+1],i1OLOL0j[llIl0l+2]=liIjlIo,IjLjil,nil
end
end
else Ij1lOIji1I0l0l() end
end
return LiOl00
end
return iO0jiOil1Oiojj(lLooll1iLIL1lI,{},ljo0jj(...))
