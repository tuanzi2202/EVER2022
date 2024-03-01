删除vector数组nums中的指定元素：
auto it = nums.begin() + 1;
nums.erase(it); // 删除了数组中下标为1的元素，数组长度-1

获取vector数组nums长度（元素个数）：
nums.size();

往vector数组nums末尾添加一个新元素：
nums.push_back(1); // 末尾添加元素1

往vector数组nums指定位置插入一个新元素：
nums.insert(nums.begin(),1); // 往开始位置插入元素1

对vector数组nums进行升序排序：
sort(nums.begin(),);
