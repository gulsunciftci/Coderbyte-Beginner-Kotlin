fun FirstReverse(str: String): String {

  // code goes here  
  var reverseString=" "
  var i=str.length-1
  while(i>=0){
    reverseString +=str[i]
    i--
  }
  return reverseString;
  
}

fun main() {
  println(FirstReverse(readLine()))
}
