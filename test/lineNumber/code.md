```cpp
//Initialization code

namespace ra = ranges::action;
auto get(){return std::vector<int>{1,3,5,7};}
auto above_5 = [](auto v){ return v >= 5; };
```