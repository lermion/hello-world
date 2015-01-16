function pow(num, exp){
  var result = 1;
  for(var cnt = 0; cnt < exp; cnt++){
    result *= num;
  }
  console.log(result);
}
pow(3, 6);
