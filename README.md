//Autor:Juan Tuñas Ces
//Fecha:03/2026

#define S1 8
#define S2 9
#define S3 10
#define S4 11
#define DIRECTA 4
#define INVERSA 5

void setup() {
  pinMode(S1, OUTPUT);
  pinMode(S2, OUTPUT);
  pinMode(S3, OUTPUT);
  pinMode(S4, OUTPUT);
  pinMode(DIRECTA, INPUT);
  pinMode(INVERSA,INPUT);
}
void loop() {
  digitalWrite(S1, HIGH);
  digitalWrite(S4, HIGH);
  digitalWrite(S3, LOW);
  digitalWrite(S2, LOW);
}
