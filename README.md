# Arduino-button-ile-led-yakmak
Daha fazla bilgi için Linkedln linki:https://www.linkedin.com/in/irem-t%C3%BCfek%C3%A7i-171896294/overlay/about-this-profile/?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base%3BBnD%2BkHhtSNCBfPgaF00r1w%3D%3D



int buton_durumu=0;
void setup() {
  pinMode(7,INPUT);
  pinMode(6,OUTPUT); 

}

void loop() {
 buton_durumu=digitalRead(7);
 if(buton_durumu==0){
digitalWrite(6,1);

 }
else{
  digitalWrite(6,0);
}

}
