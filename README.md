- 👋 Hi, I’m @MysticTideJJ
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ..
<!---
MysticTideJJ/MysticTideJJ is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

import random

# 定义盲盒中的物品列表
blind_box_items = ["物品1", "物品2", "物品3", "物品4", "物品5", "物品6"]

# 上一次抽取的物品
last_selected_item = None

# 随机抽取一个物品，确保与上一次不同
while True:
    selected_item = random.choice(blind_box_items)
    if selected_item != last_selected_item:
        break

# 更新上一次抽取的物品
last_selected_item = selected_item

# 打印抽取的物品
print("你抽到了:", selected_item)

