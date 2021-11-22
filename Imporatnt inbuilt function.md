1) ## memset(< matrix > , < value to be filled > , < size of matrix > ):
- LIMITATION : with this you can only fill 0 & 1.<br/>
- ex: memset(t , -1 , sizeof(t));

2) ### erase:
### < vector name >.erase(< vectorname.begin() + index to erase >)
- TC : O(n+m) = where n = no. of elements to erase , m = no. of elements shifted after erase
- Ex : v.erase(v.begin()+3)




