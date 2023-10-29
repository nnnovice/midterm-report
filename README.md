# midterm-report

UML類別圖，UML中的重要圖形，是在物件導向語言用中用來表示一個類別。

如下圖所示（它由兩部分組成，類，類之間的關係）：
![image1](https://pic3.zhimg.com/v2-61af74fe4b611c85c740cececb18e4ae_b.webp?consumer=ZHI_MENG)

01 類
類別是具有相似結構、行為和關係的一組物件的描述符，是物件導向系統中最重要的建構塊。
如下圖所示，就表示一個類別：
![image2](https://pic1.zhimg.com/v2-c589911333aded1c962e2f0958e5041c_b.webp?consumer=ZHI_MENG)

三個格子由上至下分別表示：

類別名稱（如果是接口，就使用斜體表示）
類別的特性（一般是類別的欄位和屬性，可以沒有）
類別的操作（一般是類別的方法或行為）
它們前邊的符號有以下幾類：

“+”表示public
“-”表示private
“#”表示protected

02 類的關係
除了類，類圖中還有一個重要元素，就是類別之間的關係。
依類別的關係的不同，具體可分為6種：

（1）依賴關係（以虛箭線表示）

所謂依賴關係，就是構造這個類的時候，需要依賴其他的類，例如：動物依賴水和氧氣。如下圖所以：
![image3](https://pic3.zhimg.com/v2-e5af6625d202f3220b7333692dabad42_b.webp?consumer=ZHI_MENG)

（2）繼承、泛化關係（以帶空心三角形的實線表示）

繼承（泛化）關係，它指定了子類別如何特化父類別的所有特徵和行為。例如：鳥是動物的一種，企鵝、鴨、大雁是鳥的一種。
![image4](https://pic3.zhimg.com/v2-d25ab9c2f2e8064317cd090b751f6702_b.webp?consumer=ZHI_MENG)

（3）實線關係（以空心三角形的虛線表示）

一種類別與介面的關係，表示類別是介面所有特徵和行為的實作。它有兩種表示方法：

第一種，矩形表示法，

頂端有<<interface>>
第一行：介面名稱
第二行：介面方法
![image5](https://pic4.zhimg.com/v2-88addbc8cbfe20bb0c038bee5f151617_b.webp?consumer=ZHI_MENG)

第二種，棒棒糖表示法

圓圈旁為介面名稱
介面方法在實作類別中出現
![image6](https://pic3.zhimg.com/v2-40c356695078c5da3ea6f0b6e5b1ea7e_b.webp?consumer=ZHI_MENG)

（4）關聯關係（以實箭線表示）

所謂關聯關係，就是這個類別有一個屬性是其他類別。
![image7](https://pic2.zhimg.com/v2-cdb23e214bf7320b7a563c7e08ace379_b.webp?consumer=ZHI_MENG)

（5）聚合關係（以空心菱形的實線表示）

聚合關係是關聯關係的一種，是強的關聯關係；

特點： 部分物件的生命週期並非由整體物件來管理。也就是說，當整體物件已經不存在的時候，部分的物件還是可能繼續存在的。例如：一隻大雁脫離了雁群，依然是可以繼續存活的。
![image8](https://pic3.zhimg.com/v2-60d6df1daf28778e9c82e4b097a453a6_b.webp?consumer=ZHI_MENG)

（6）組合關係（以實心菱形的實線表示）

組合關係同樣是關聯關係的一種，是比聚合關係還要強的關係。

特點：在組合中，部分與整體生命期一致，部分與組合同時創建並同時消亡。比如：鳥與翅膀的關係。
![image9](https://pic2.zhimg.com/v2-0b9bf5c1582e824c61741a99fff0f915_b.webp?consumer=ZHI_MENG)


本文來自 https://www.zhihu.com/tardis/bd/art/267298708?source_id=1001 
