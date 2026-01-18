# 📦 C++ STL (Standard Template Library)
STL is a core part of the **C++ Standard Library** and is heavily built on **templates** to provide **generic, reusable components**.
---

## 🧩 Core Components of STL
STL has **4 main pillars**:
- **Containers** – store data  
- **Algorithms** – process data  
- **Iterators** – access data  
- **Functors** – customize behavior  
---

## 📂 Containers
Containers define **how data is stored**.

### 🔹 Types of Containers
1. **Sequence Containers**  
   - `vector`, `deque`, `list`, `array`, `forward_list`  
   - Ordered, index-based access (mostly)
2. **Associative Containers**  
   - `set`, `multiset`, `map`, `multimap`  
   - Sorted, tree-based (`O(log n)`)
3. **Unordered Associative Containers**  
   - `unordered_set`, `unordered_map`  
   - Hash-based, no order (`O(1)` avg)
4. **Container Adapters**  
   - `stack`, `queue`, `priority_queue`  
   - Restricted interface
---

## Algorithms
  
### Order/Rearrange  
```cpp
sort(v.begin(),  v.end());  
reverse(v.begin(),  v.end());  
rotate(v.begin(),  v.end());  
```

### Searching  
```cpp
find(v.begin(),  v.end(), x);  
count(v.begin(),  v.end(), x);  
```

### Remove/Replace  
```cpp
remove(v.begin(),  v.end(), x);  
replace(v.begin(),  v.end(), old, new);  
```
---
  
## Iterators  
  
i. Explicit Iterators  
```cpp
for(auto it=v.begin(); it!=v.end(); it++)
{
    cout<<*it<<" ";
}
```
  
ii. Hidden Iterators  
```cpp
for(int x : nums)
{
    cout<<x<<" ";
}
```
  
iii. Index Based Loop  
```cpp
for(int i=0;i<nums.size();i++)
{
    cout<<nums[i]<<" ";
}
```
  
---

