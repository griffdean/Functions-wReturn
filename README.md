# Functions-wReturn

Functions that return a value are functions that have a datatype. Functions that wouldn't return a value are void functions.
For example,
public void Func(){
  }
//this wouldn't return anything but can have print statements

public void Func(int x){
   int result = x - 5;
   print(result);
 }
 //this is another void function so it wouldnt return anything but it can print the result
 
 void Func(){
    int result = 4 - 5;
    print(result);
 }
 //this is another void function that is private and prints the result

public int Func(int x){
  int result = x / 3;
  return result;
}
//since this function is not void it returns an int datatype

public int Func(int x, int y, int z){
   int result = x - y / z;
   return result;
 }
 //this returns an int value after the calculation of the arguments occurs

int Func(){
  int result = 5 / 6;
  return result;
}
//this is a private function because the default access modifier is private unless otherwise specified, and it returns an int value

float Func(float x){
   float result = x / 3.1f;
   return result;
 }
 //this is another private function that returns a float value

public float Func(float x, float y){
   float z = x / y;
   return z;
}
//this returns a float value (z) which is the result of two float arguments (x and y) divided by eachother

public float Func(float pepp, float pizza){
   float pie = pepp + pizza;
   return pie;
}
//this returns a float value (pie) which is the result of adding pizza and pepp (the arguments) together

