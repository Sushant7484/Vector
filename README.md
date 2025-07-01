# Vector programing 
//Operations
#include<iostream>
#include<vector>
using namespace std;
int main()
{
    vector<int> object={10,20,30,40,50,60,70,200};
    object.push_back(100);//for add the elements
    object.push_back(200);
    object.pop_back();//remove the elements
    object.pop_back();
    //v.pop_back();//remove the elements
    for (int x:object){
        cout<< x <<" ";
    }

}
