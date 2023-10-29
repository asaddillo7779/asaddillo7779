
import java.util.*

fun main() {

   val suma = 1_000_000
    val  input = Scanner(System.`in`)
    print("parolni kriting = ")
     val a = input.nextInt()
    while (true)
    if (a==2003){
        for (i in 0..3){
        }
        println()
        println()
        println("Xush kelibsiz bolimlarni tanlang!!")
        println()
        println("1: pul yechish 2: paynet 3: kamunal tolov 4 : karta raqamga paynet")
        val raqam = input.nextInt()

        if(raqam ==1){                                 // 1- chi bolim
             print("summani kriting = ")
            val yechish = input.nextInt()
            if (yechish >=10_000){
            val nam = (suma-yechish)
            val minus =(yechish/100)
                val g = nam -minus
            println(" qolgan summa = $g \n" + " yechilgan sumadan 1 % = $minus")
                println("AMALYOT MUOFIQIYATLI BAJARILDI !!!")
            }else{
                println( "Xato minimum suma 10_000 som ")
            }
        }
        else if (raqam == 2){                                       //2- chi bolim
            print("telfon raqamni kiriting + 998 ")
            val nomer =input.nextInt()
            print("summani kiriting = ")
            val hisob = input.nextInt()
            if (hisob >= 10000) {
                val k = suma - hisob
                val i = (suma - hisob) - (hisob / 100)
                println(" qolgan summa = $k \n" + " yechilgan sumadan 1 % = $i")
                 println("AMALYOT MUOFIQIYATLI BAJARILDI !!!")
            }else {
                println( "Xato minimum suma 10_000 som ")
            }
        }
        else if (raqam == 3){                                       // 3- bolim
            println("kamunal tolov bolimiga hush kelibsiz")
            println(" 1 :  suv  2: gaz")
            val suv = input.nextInt()
            if (suv==1){
                print("suvni raqamini kriting = ")
                val raqamm = input.nextInt()
                print("summani kritng =  ")
                val e = input.nextInt()
                if (e>10_000){
                val qolgan = suma- e
                val o =(suma-e)-(e/100)
                println(" qolgan summa = $qolgan \n"+"yechilgan sumadan 1 % =$o")
                println("AMALYOT MUOFIQIYATLI BAJARILDI !!!")
                }else{
                    println("Xato minimum suma 10_000 som")
                }
            }else if ( suv == 2){
                print("gazni raqamini kriting = ")
                val y = input.nextInt()
                print("summani kriting = ")
                val p = input.nextInt()
                if (p>10_000){
                val t = suma-p
                val u = p/100
                println("qolgan summa = $t \n"+"yechilgan sumadan 1 % =$u")
                    println("AMALYOT MUOFIQIYATLI BAJARILDI !!!")
                }else{
                    println( "Xato minimum suma 10_000 som ")
                }
            }else{
                println(" Nimadir xato ")
            }
        }
        else if (raqam == 4){                                         // 4 chibolim
            println("karta raqamni tanlang")
            println("1: humo 2: uzcard")
            val kart =input.nextInt()
         if (kart == 1 ){
             print("  karta raqamni kriting = 9860 ")
             val kraqam=input.nextDouble()
             print("summani kiritng = ")
             val ksum = input.nextInt()
             if (ksum>10_000){
                 val alif =suma-ksum
                 val  hisobb23 = (suma-ksum)-(alif/60)
                 val  hisobb = (alif/60)
                 println("qolgan summa = $alif \n"+"yechilgan sumadan  % =$hisobb \n"+" % olgandan keyingi suma =$hisobb23")
                 println("AMALYOT MUOFIQIYATLI BAJARILDI !!!")
             } else{
                 println("nimadir hato == minmal suma = 10_000")
             }
         }else if (kart == 2){
             print("  karta raqamni kriting = 8600  ")
             val kraqam2=input.nextDouble()
             print("summani kiritng = ")
             val ksum2= input.nextInt()
             if (ksum2>10_000){
                 val alif2 =suma-ksum2
                 val  hisobb2 = (suma-ksum2)-(alif2/60)
                 val jam = alif2/60
                 println("qolgan summa = $alif2 \n"+"yechilgan sumadan % =$jam \n"+" % olgandan keyingi summa = $hisobb2 ")
                 println("AMALYOT MUOFIQIYATLI BAJARILDI !!!")
         }else{
                 println("nimadir hato \n"+" minmal suma = 10_000")
         } } }
    }else {
         println("Amalyotda hato yuzaga keldi")

    }


}

