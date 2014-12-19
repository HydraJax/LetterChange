function letterChange(str){ 
  var solution =[];
  var letterAdv;
  var nextLetter;
  var finalSolution = [];
  
  for (var i= 0; i < str.length; i++){
    if ( isLetter( str[i]) ){
      nextLetter = AdvanceLetter(str[i]);
      solution.push(nextLetter);
    }
  }
  for( var j = 0; j < solution.length; j++ ) {
   finalSolution.push(capVowel(solution[j]));
      console.log(finalSolution);
    }
  }

function AdvanceLetter(y){
  if ( y[0] === 'z' ) {  return 'a'; }
  else {
  if ( y[0] === 'Z' ) return 'A';
  }
  return String.fromCharCode( y.charCodeAt( 0 ) + 1 );
}

function capVowel(a){
  if( a === "a"||a === "e"|| a === "i"||a === "o"||a === "u" ){
   a = a.toUpperCase();
  }
    return a;
  
}

function isLetter(x){
    if (x.charCodeAt(0) >= 65 && x.charCodeAt(0) <= 90 || x.charCodeAt(0) >= 97 && x.charCodeAt(0) <= 122) {
      return true;
    }
    return false;
  }

letterChange("abz");