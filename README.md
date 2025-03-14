int f = 13;
int g = 12;
int e = 11;
int d = 10;
int c = 9;
int b = 8;
int a = 7;  //7 Segment pin

int de=100;  // delay time

void setup() {

  pinMode (6, OUTPUT);
  pinMode(f, OUTPUT);
  pinMode(g, OUTPUT);
  pinMode(e, OUTPUT);
  pinMode(d, OUTPUT);
  pinMode(c, OUTPUT);
  pinMode(b, OUTPUT);
  pinMode(a, OUTPUT);

}

void loop() 
{ 
 digitalWrite(6,HIGH);
 delay(500);
 digitalWrite(6,LOW);
 delay(500);  
 digitalWrite(a,0); 
 digitalWrite(b,1);  
 digitalWrite(c,1);  
 digitalWrite(d,0);  
 digitalWrite(e,1);  
 digitalWrite(f,1);  
 digitalWrite(g,1);   // h
 delay(de);  
 digitalWrite(6,HIGH);
 delay(500);
 digitalWrite(6,LOW);
 delay(500);  

 digitalWrite(a,1); 
 digitalWrite(b,0);  
 digitalWrite(c,0);  
 digitalWrite(d,1);  
 digitalWrite(e,1);  
 digitalWrite(f,1);  
 digitalWrite(g,1);   // e
 delay(de);
  
 digitalWrite(6,HIGH);
 delay(500);
 digitalWrite(6,LOW);
 delay(500);  

 digitalWrite(a,0); 
 digitalWrite(b,0);  
 digitalWrite(c,0);  
 digitalWrite(d,1);  
 digitalWrite(e,1);  
 digitalWrite(f,1);  
 digitalWrite(g,0);   // l
 delay(de);  

 digitalWrite(6,HIGH);
 delay(500);
 digitalWrite(6,LOW);
 delay(500);  

 digitalWrite(a,0); 
 digitalWrite(b,0);  
 digitalWrite(c,0);  
 digitalWrite(d,0);  
 digitalWrite(e,0);  
 digitalWrite(f,0);  
 digitalWrite(g,1);   // -
 delay(de);

    digitalWrite(6,HIGH);
 delay(500);
 digitalWrite(6,LOW);
 delay(500);

 digitalWrite(a,0); 
 digitalWrite(b,0);  
 digitalWrite(c,0);  
 digitalWrite(d,1);  
 digitalWrite(e,1);  
 digitalWrite(f,1);  
 digitalWrite(g,0);   // l
 delay(de); 
 digitalWrite(6,HIGH);
 delay(500);
 digitalWrite(6,LOW);
 delay(500);  
 
 digitalWrite(a,1); 
 digitalWrite(b,1);  
 digitalWrite(c,1);  
 digitalWrite(d,1);  
 digitalWrite(e,1);  
 digitalWrite(f,1);  
 digitalWrite(g,0);   // o
 delay(de);   
 digitalWrite(6,HIGH);
 delay(500);
 digitalWrite(6,LOW);
 delay(500);  

 digitalWrite(a,1); 
 digitalWrite(b,0);  
 digitalWrite(c,0);  
 digitalWrite(d,1);  
 digitalWrite(e,1);  
 digitalWrite(f,1);  
 digitalWrite(g,1);   // E
  delay(1000);  
   
     digitalWrite(6,HIGH);
 delay(1000);
   digitalWrite(6,LOW);
 delay(1000);  

 digitalWrite(a,0); 
 digitalWrite(b,0);  
 digitalWrite(c,0);  
 digitalWrite(d,0);  
 digitalWrite(e,0);  
 digitalWrite(f,0);  
 digitalWrite(g,1);   // -
  delay(de);


  digitalWrite(6,HIGH);
 delay(500);
   digitalWrite(6,LOW);
 delay(500);   

 digitalWrite(a,1); 
 digitalWrite(b,0);  
 digitalWrite(c,0);  
 digitalWrite(d,1);  
 digitalWrite(e,1);  
 digitalWrite(f,1);  
 digitalWrite(g,1);   // E
  delay(de);  
   
     digitalWrite(6,HIGH);
 delay(500);
   digitalWrite(6,LOW);
 delay(500);  

 digitalWrite(a,0); 
 digitalWrite(b,0);  
 digitalWrite(c,0);  
 digitalWrite(d,0);  
 digitalWrite(e,0);  
 digitalWrite(f,0);  
 digitalWrite(g,1);   // -
  delay(de);


  digitalWrite(6,HIGH);
 delay(500);
   digitalWrite(6,LOW);
 delay(500);

 digitalWrite(a,1); 
 digitalWrite(b,0);  
 digitalWrite(c,0);  
 digitalWrite(d,1);  
 digitalWrite(e,1);  
 digitalWrite(f,1);  
 digitalWrite(g,1);   // E
  delay(1000);  
   
  digitalWrite(6,HIGH);
 delay(500);
   digitalWrite(6,LOW);
 delay(500);
  
 digitalWrite(a,0); 
 digitalWrite(b,1);  
 digitalWrite(c,1);  
 digitalWrite(d,0);  
 digitalWrite(e,1);  
 digitalWrite(f,1);  
 digitalWrite(g,1);   // h
  delay(1000);  

    digitalWrite(6,HIGH);
 delay(1000);
   digitalWrite(6,LOW);
 delay(1000); 
    digitalWrite(a,1); 
 digitalWrite(b,1);  
 digitalWrite(c,1);  
 digitalWrite(d,1);  
 digitalWrite(e,1);  
 digitalWrite(f,1);  
 digitalWrite(g,0);   // o
 delay(de);   
 digitalWrite(6,HIGH);
 delay(500);
 digitalWrite(6,LOW);
 delay(500); 

 digitalWrite(a,0); 
 digitalWrite(b,1);  
 digitalWrite(c,1);  
 digitalWrite(d,1);  
 digitalWrite(e,1);  
 digitalWrite(f,1);  
 digitalWrite(g,0);   // u
 delay(de);   
 digitalWrite(6,HIGH);
 delay(500);
 digitalWrite(6,LOW);
 delay(500);  
 digitalWrite(a,1); 
 digitalWrite(b,0);  
 digitalWrite(c,1);  
 digitalWrite(d,1);  
 digitalWrite(e,0);  
 digitalWrite(f,1);  
 digitalWrite(g,1);   // s
 delay(de);   
 digitalWrite(6,HIGH);
 delay(500);
 digitalWrite(6,LOW);
 delay(500); 
 
 digitalWrite(a,1); 
 digitalWrite(b,0);  
 digitalWrite(c,0);  
 digitalWrite(d,1);  
 digitalWrite(e,1);  
 digitalWrite(f,1);  
 digitalWrite(g,1);   // E
  delay(de);  
   
     digitalWrite(6,HIGH);
 delay(1000);
   digitalWrite(6,LOW);
 delay(1000);

}
