<pre>


 
item center yatay olarak birbirlerini ortalar
justify between birbirlerine gore ortalar
flex aslinda flexbox' i iface ediyor 
genel olarka amacimiz her seyi flex dersen yapabilirsin

flex justify-between flex-1 : 
flex dedik justify between aralairinda bosluk olsun 
flex-1 kaplayabildigin kadar yer kapla demek

transition duration-500: 
biraz daha yavas bir sekilde gecisi yapiyor


border-r px-4 mx-4 py-1 border-amber-950 : 
border asagida ki genisligi demek border 
x ekseninde padding ve margin ye ekseninde padding verdi border amber de cerceve rengi


bg-transparent border-b border-b-red-400 focus:outline-none w-44:
bg transparant backgorun rengi olmasin istedik
border b border'in buttom genisligi 1 pixel yapar
border bottom rengini kirimizi yaptik
focusta uzerine tiklayinca disini cerve aliyor ya onu kapadik
ve 44 genislik verdik


fas fa-search: bu font awesome search iconu tailwin ile alakli degil


en ustte ki div'in clasina group eklersen altta ki divleri de kapsar
simdi bir animasyon yapmak istiyoruz
bir ustteki div'e group ekledik
div class="group border-r px-4 mx-4 py-1 border-amber-950
ve
input type="text" class="bg-transparent opacity-0 group-hover:opacity-35 border-b border-b-red-400 focus:outline-none w-44"

yaptm ne yaptim yani bir ustte ki div'e group verdim
asagida ki inputun opacitiysini 0 yaptim yani gorunmez oldu su an
formun uzerine geldigimde group hover yapip opacity arttirdik


-ml-4 group-hover:ml-0 transition duration-500:
negatif margin verdim soldan
group hover yani group'a geldigi zaman margini 0 yaptim


text-4xl font-bold text-transparent bg-gradient-to-r bg-clip-text from-red-200 to-red-500:
bu o regrarenk yazilarin kodu aslinda
once transparan yaparak kendi kodunu kaldirdi daha sonra gradient diyerek nereden nereye gidecegini verdi


py-6 lg:py-12:
responsive bu sekilde yaziliyor 
mobile first bu demek yani once mobil dusun sonra buyuk ekrani yaz siralama bu sekilde 


space-x-8 lg:space-x-16:
ayni sekidle bir responsive ornegi daha


whitespace-nowrap">Sing Up</a>:
bu gordugun gibi arada bosluk olanlarin alt alta gecmesini onluyor

<!--  Menu-->
div class="hidden md:flex items-center lg:text-lg space-x-8 lg:space-x-16":
simdi hani bazi sitelerde mobilde menu acilmaz yukari da bir 3 cizgi falan oluyor iste onun icin once bunun hidden olmasi lazim
once hidden yani sen gizlen ama eger cihaz md'den buyukse flex gibi davran diyoruz
kendi default text ayarlari eger cihaz lg'den buyukse bunu yap vs dedik

div class="block md:hidden pr-4">
    div class="space-y-1 cursor-pointer">
        div class="bg-gray-100 w-8 h-1 rounded-full"></div>
        div class="bg-gray-100 w-8 h-1 rounded-full"></div>
        div class="bg-gray-100 w-8 h-1 rounded-full"></div> 
    div>
div>

bu da bizidim menu kodumuz dedik ki sen mmobilde blokcsun eger md'den buyukse hidden gibi tavran
geri kalan renkleri de elle yaptik :)


Relative (İlişkisel): Bir öğenin konumunu, kendisini çevreleyen üst öğeye göre belirler. 
Yani, bir öğe "relative" olarak tanımlanırsa, bu öğe, ona göre pozisyonlandırılan "absolute" veya "fixed" öğelerin referans noktası olur.


Absolute (Mutlak): Bir öğeyi belirli bir üst öğenin içinde pozisyonlandırmak için kullanılır. 
Bir öğe "absolute" olarak tanımlandığında, bu öğe üst öğesine göre pozisyonlanır ve üst öğesinin sınırları içinde hareket eder.



section class="h-128 group relative">
    img src="images/batman.jpg" alt="Main Image" class="h-full w-full object-cover">

once bir tane alan koyduk buna relative dedik daha sonra asagida ki img absulute yani ona gore pozisyonlanacak
w-full section' ile ayni genislikte olsun kendisini kapsayan div ile yani
h full da ayni sekilde
object cover gorselin bu divi kapsamasi icinde object cover koyduk

object cover  Tanim :
Bu sınıf, nesnenin boyutunu koruyarak ve gerektiğinde kırpma yaparak bir nesneyi kapsayacak şekilde ölçeklendirir.
Bu, resmin orijinal oranını korurken belirlenen boyutlara sığacak şekilde kırpma yapar.


tracking-wider: metinde ki bosluklari arttirir

basis-2/3: ust klass flex ise ekranin 2/3'unu kaplar

divide-white divide-opacity-60: aralara | seklinde cizgi ceker


flex-wrap dersek bir ustte ki div'e gore itemleri hizalar ve tasanlari asagiya atar
flex-nowrap dersek yan yana getirir ama scroll cikar

flex flex-row : satir haline getirir
flex flow-col : sutun halinde yapar
bir de responsive acisinda da flex ile baslamasi daha iyi



<div class="container flex items-center justify-center relative">
        <!-- Left Content -->
        <div class="basis-1/2">
            <img src="images/matrix.png" alt="matriz" class="absolute bottom-0">
        </div>
        <!-- rigt Content -->
        <div class="basis-1/2">
            rigt
        </div>
</div>

simdi yukarida ki gibi yapinca aslinda divin icinde olmasina ragmen sanki ekranin en onunde gibi yani z index gibi konumluyor
containerde hic bir sey olmadigi icin ve bottom 0 oldugu icin en usste gibi gozukur 

</pre>   


