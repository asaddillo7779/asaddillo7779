
fun main() {
    val input = Scanner(System.`in`)
    print("raqamni kriting = ")
    val raqam = input.nextInt()
    val factoriyal = fact(raqam)
    println(" $raqam -> sonning factoriyali = $factoriyal")

}
fun fact(n:Int):Int{
    return if (n==0 || n==1){
        1
    }else{
        n*fact(n-1)
    }
