# Punto-2-Dado-Examen-medio-curso

int var;
var = int(random(1,6));
println(var);

if (var == 1){
ellipse(50,50,20,20);  
}
else if (var ==2){
  ellipse(25,25,20,20);
  ellipse(75,25,20,20);
}
else if (var==3){
  ellipse(25,25,20,20);
  ellipse(50,50,20,20);
  ellipse(75,25,20,20);
}
else if (var==4){
  ellipse(25,25,20,20);
  ellipse(75,25,20,20);
  ellipse(25,75,20,20);
  ellipse(75,75,20,20);
}
else if (var==5){
  ellipse(25,25,20,20);
  ellipse(75,25,20,20);
  ellipse(25,75,20,20);
  ellipse(75,75,20,20);
  ellipse(50,50,20,20);
}
else if (var==6){
  ellipse(25,25,20,20);
  ellipse(75,25,20,20);
  ellipse(25,75,20,20);
  ellipse(75,75,20,20);
  ellipse(25,50,20,20);
  ellipse(75,50,20,20);
}
