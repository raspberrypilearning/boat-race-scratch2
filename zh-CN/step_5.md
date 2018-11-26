## 撞击！

此时，你的船只可驶过木头障碍！让我们来解决这个问题。

+ 你需要为你的船只准备两种造型，一种普通造型，另一种在撞船时使用。复制你的船只造型，并将一种造型命名为“普通”，另一套为“撞击”。

+ 点击你的 `撞击` 造型，选择 Select（选择）工具抓取船只位，移动并旋转，使船只看起来似乎受到了撞击。

	![screenshot](images/boat-hit-costume.png)

+ 现在向你的船只添加代码，使其在碰到任何棕色木头位时受碰撞并分解。

--- hints ---
--- hint ---
你需要在你的 `永远` 循环内部添加代码，以便你的代码可以不停检查船只是否受到撞击。`如果` 船只 `触碰` 木头的棕色，你需要 `切换到撞击造型` 、 `喊 2 秒钟 Noooo!` ，然后 `切换回普通造型`。最后，你将需要 `朝上` 并 `前往起始位置`。
--- /hint ---
--- hint ---
以下是你将需要的代码块：
![screenshot](images/boat-hit-blocks.png)
--- /hint ---
--- hint ---
你的代码应如下所示：
![screenshot](images/boat-hit-code.png)
--- /hint ---
--- /hints ---

+ 你还应确保你的船只在出发时一直采用“普通”造型。

	现在，如果你试图驶过木头障碍，你会看到你的船只受到撞击并返回起点。

	![screenshot](images/boat-crash.png)