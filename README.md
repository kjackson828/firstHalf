# firstHalf

public String firstHalf(String str) {
  if (str.length() == 0){
    return "";
  }
  else{
    return (str.substring(0, (str.length()/2)));
  }
}
