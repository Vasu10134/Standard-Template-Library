to include pair, use
#include<pair> , or
#include<bits/stdcpp.h>

syntax of pair
pair<datatype, datatype> pair_name;
pair<int, string> a;

to insert values, use
p = make_pair(30, "vasu");

to output them, use
cout<<p.first;
cout<<p.second;

to pair inside a pair, use
pair<int, pair<int, string>> p;
p = make_pair<10, make_pair<20, "vasu">> p;

to output
cout<<p.first;  //10
cout<<p.second.first;  //20
cout<<p.second.second;  //vasu
