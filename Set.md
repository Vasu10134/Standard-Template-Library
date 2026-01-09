- set only holds unique elements
- it stores value in sorted order

to use the library
set<datatype> s;

to insert an element, use
s.insert(10);
s.insert(20);

to interate in a set
for(auto it=s.begin(); it!=s.end(); it++)
{
    cout<<*it<<" ";
}

to print values in decending order, do
set<int, greater<int>> s;

to find an element from set, use
(s.find())

to count an element from set, use
(s.count())

to delete an element from a set, use
s.erase(num);
