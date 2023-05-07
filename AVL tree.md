# AVL Tree (Adelson-Velsky and Landis Tree)
# 【用途】屬於BST，透過計算調整樹的結構來維持平衡
# 【複雜度】
* insert、delete、search平均及最差時間複雜度皆為 O(log(N))
* 空間複雜度：O(N)
# 【實作】
* 計算各節點的balance factor來確認是否需要重新平衡
* balance factor = 左子節點高度 - 右子節點高度
    * bf > 0 : 左邊較重
    * bf < 0 : 右邊較重