to use list  
#include<list>, or  
#include<bits/stdcpp.h>  
  
syntax of list  
list<datatype> list_name;  
list<int> l;  
  
to push into the list, use  
l.push_back(10);  
  
to push onto the front of the list, use  
l.push_front(20);  
  
to pop into the list, use  
l.pop_back(10);  
  
to pop onto the front of the list, use  
l.pop_front(20);  
  
to know what element is in the front, use  
cout<<l.front();  
  
to know what element is in the back, use  
cout<<l.back();  
  
to iterate over list, use  
for(auto it=l.begin(); it!=l.end(); it++)  
{  
    cout<<*it<<" ";  
}  




  
