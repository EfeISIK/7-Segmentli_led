//alt kısımdaki pinler
const int LED1 = 4;
const int LED2 = 5;
const int LED3 = 6;
const int LED4 = 7;

//üst kısımdaki pinler
const int LED5 = 8;
const int LED6 = 9;
const int LED7 = 10;
const int LED8 = 11;

void setup(){
  pinMode(LED1, OUTPUT);
  pinMode(LED2, OUTPUT);
  pinMode(LED3, OUTPUT);
  pinMode(LED4, OUTPUT);
  pinMode(LED5, OUTPUT);
  pinMode(LED6, OUTPUT);
  pinMode(LED7, OUTPUT);
  pinMode(LED8, OUTPUT);

void loop(){
 // 9 yükseliyoruz.
  digitalWrite (LED1, HIGH); 
  digitalWrite (LED2, LOW); 
  digitalWrite (LED3, LOW);
  digitalWrite (LED4, HIGH);
  digitalWrite (LED5, LOW);
  digitalWrite (LED6, LOW);
  digitalWrite (LED7, LOW);
  digitalWrite (LED8, LOW);
 delay(1000); 
 // 8 yükseliyoruz.
  digitalWrite (LED1, HIGH); 
  digitalWrite (LED2, LOW); 
  digitalWrite (LED3, LOW);
  digitalWrite (LED4, LOW);
  digitalWrite (LED5, LOW);
  digitalWrite (LED6, LOW);
  digitalWrite (LED7, LOW);
  digitalWrite (LED8, LOW);
  delay(1000);
  // 7 yükseliyoruz
  digitalWrite (LED1, HIGH); 
  digitalWrite (LED2, LOW); 
  digitalWrite (LED3, HIGH);
  digitalWrite (LED4, HIGH);
  digitalWrite (LED5, LOW);
  digitalWrite (LED6, LOW);
  digitalWrite (LED7, LOW);
  digitalWrite (LED8, HIGH);
delay(1000);  
// 6 yükseliyoruz
  digitalWrite (LED1, HIGH); 
  digitalWrite (LED2, LOW); 
  digitalWrite (LED3, LOW);
  digitalWrite (LED4, LOW);
  digitalWrite (LED5, HIGH);
  digitalWrite (LED6, LOW);
  digitalWrite (LED7, LOW);
  digitalWrite (LED8, LOW);
delay(1000);  
// 5 yükseltiyoruz
  digitalWrite (LED1, HIGH); 
  digitalWrite (LED2, LOW); 
  digitalWrite (LED3, LOW);
  digitalWrite (LED4, HIGH);
  digitalWrite (LED5, HIGH);
  digitalWrite (LED6, LOW);
  digitalWrite (LED7, LOW);
  digitalWrite (LED8, LOW);
delay(1000); 
// 4 yükseliyoruz
  digitalWrite (LED1, HIGH); 
  digitalWrite (LED2, LOW); 
  digitalWrite (LED3, HIGH);
  digitalWrite (LED4, HIGH);
  digitalWrite (LED5, LOW);
  digitalWrite (LED6, HIGH);
  digitalWrite (LED7, LOW);
  digitalWrite (LED8, LOW);
delay(1000);
// 3 yükseliyoruz
  digitalWrite (LED1, HIGH); 
  digitalWrite (LED2, LOW); 
  digitalWrite (LED3, LOW);
  digitalWrite (LED4, HIGH);
  digitalWrite (LED5, LOW);
  digitalWrite (LED6, LOW);
  digitalWrite (LED7, HIGH);
  digitalWrite (LED8, LOW);
delay(1000);
// 2 arttıyoruz
  digitalWrite (LED1, HIGH); 
  digitalWrite (LED2, HIGH); 
  digitalWrite (LED3, LOW);
  digitalWrite (LED4, LOW);
  digitalWrite (LED5, LOW);
  digitalWrite (LED6, LOW);
  digitalWrite (LED7, HIGH);
  digitalWrite (LED8, LOW);
delay(1000);
// 1 arttırıyoruz
  digitalWrite (LED1, HIGH); 
  digitalWrite (LED2, LOW); 
  digitalWrite (LED3, HIGH);
  digitalWrite (LED4, HIGH);
  digitalWrite (LED5, LOW);
  digitalWrite (LED6, HIGH);
  digitalWrite (LED7, HIGH);
  digitalWrite (LED8, HIGH);
// 0 yükseliyoruz.
  digitalWrite (LED1, HIGH); 
  digitalWrite (LED2, LOW); 
  digitalWrite (LED3, LOW);
  digitalWrite (LED4, LOW);
  digitalWrite (LED5, LOW);
  digitalWrite (LED6, LOW);
  digitalWrite (LED7, LOW);
  digitalWrite (LED8, HIGH);  
delay(1000);

}
