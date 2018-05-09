# javascript
javascript exercice
console.log('hello world!');
//john height and age
var jHeigh=50;
var jAge=10;
//vriend height and age
var vriendHeigh=50;
var vriendAge =10;
//third player
var playerHeight =70;
var playerAge = 10;
//calcul
var  jGame= jHeigh+ jAge*5;
var vGame= vriendHeigh+ vriendAge*5;
var pGame = playerHeight + playerAge *5;

console.log(jGame);
console.log(vGame);
console.log(pGame);

if (jGame>vGame && jGame>pGame)
{console.log('john wins '+ jGame);}
else if(vGame>jGame && vGame>pGame)
{console.log('vriend wins '+ vGame);}
else if (pGame>jGame && pGame>vGame)
{console.log('player wins '+ pGame);}

else if (jGame === vGame && jGame>pGame) 
{console.log('john and vriend are draw '+ jGame+'and   '+vGame);}
else if(vGame === pGame && pGame>jGame)
{console.log('vriend and player are draw '+ vGame+' and '+ pGame);}
else if (jGame ===pGame && jGame>vGame)
  {console.log('john and player are draw'+ jGame+ 'and '+ pGame);}
else {console.log('there is a draw '+ jGame+'the same as '+
                  vGame+' the same as '+pGame);}

  
  


