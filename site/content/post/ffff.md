---
title: dsadssads
date: 2021-07-21T08:09:01.279Z
description: dfhjskfhd
---
# 我是标题11112121
```
//我是代码块23132132
func TestCreatDriverObj(t *testing.T) {
	db2, err := db.CreatDriverObj("", "")
	if err == nil {
		t.Log(db2)
	}

}

var array = []int{1, 2, 5, 9, 5, 9, 5, 5, 5}

func majorityElement(nums []int) int {
	m := make(map[int]int, len(array))
	for _, v := range array {
		m[v]++
	}
	me := -1
	max := math.MinInt64
	for k, v := range m {
		if v > max && v != 1 {
			max = v
			me = k
		}
	}
	return me
}

```