 ~/timp-lab-02 $ alias edit=subl
 ~/timp-lab-02 $ edit "Hello world.cpp"
 #include <iostream>
 #include <string>
 
 using namespace std;
 
 int main(int argc, char** argv){
  string name;
  cin >> name;
  cout << "Hello world from " << name << endl;
 }
