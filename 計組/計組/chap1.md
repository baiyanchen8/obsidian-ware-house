#計組
# 簡介
對計組的簡單介紹
# 主題
## A world full of computers 
### six classes of computer
#### Personal computer
1. 個人電腦(一般家用主機)
2. 高度訂製化
3. 有許多軟件，通用用途
4. 會在成本/能效上做取捨
#### Server
1. 基於network提供各種服務
2. high **perform** ,reliable，capacity
3. 可以從個人主機到巨大
#### Super computer
1. high perform ,reliable，capacity
2. 超級計算機就是要有超級算力
#### Embeding Device
1. 單一功能居多
2. 多為一個系統中的一部份 ex : 車載系統
3. 因為系統大多不大 →嚴格限制 功率、性能、成本
#### personal mobile device(PMD)
1. 多由電池供電 → low power
2. 多數皆能上網 
3. 便宜 
#### cloud computing
1. 多與PMD結合，software run on pwd ,data run on cloud database
2. Portion of software run on a PMD and a portion run in the Cloud
3. [[三種雲端]]
4. [[四種部屬雲]]
#### ![[../附件/Pasted image 20231016001757.png]]
## Looking at hardware and software from a single computer
### hardware
#### input
keyborad、mouse
##### [[POSTPC]] 後PC時代
![[../附件/Pasted image 20231016091846.png]]

#### output
**[[CRT]]**
#### memory
| nonvalid   | valid                |
| ------- | ----------------------- |
| magnetic、flash、CDROM、DVD|       memory、cache、register                  |
由於valid and nonvalid 使memory分為兩種大類型，一種用於快速存取，另一種用於保存資料。
##### valid memory
memory、cache、register  
![[../附件/Pasted image 20231016093423.png]]
**由於其價格差異，因此才會分為多層使用(越快越貴)**

#### network
**WAN** : wide area netwwork → 輸入(通常只有一孔)
**LAN** : Local area netwwork → 輸入(通常有多孔)
**Wireless network**: WiFi, Bluetooth
![[../附件/Pasted image 20231016094221.png]]
#### cpu
![[../附件/Pasted image 20231016094801.png]]
![[../附件/Pasted image 20231016094850.png]]
隨者功率、指令級並行性和記憶體延遲被限制
#### wafer
![[../附件/Pasted image 20231016125625.png]]
![[../附件/Pasted image 20231016125922.png]]
$$Yelid =1/(1+defect per area×Dies Area)^N$$
### software
![[../附件/Pasted image 20231016150151.png]]
#### system software
![[../附件/Pasted image 20231016145902.png]]
~~window~~ and linux kernel and so on 
#### function Marco
| function               | marco              |
|:---------------------- | ------------------ |
| it need return address | it need more space |
| it need more time      | it need more space |
#### compiler
| ---- | exe              | immediate                       | 直接執行 |
| ---- | ---------------- | ------------------------------- | -------- |
| pros | 執行速度快       | 只要有中間檔(&java庫)就可以執行 |    只要有程式碼就能執行      |
| cons | 換台電腦就不能用 |                 比exe慢                |    跑到才會出錯，比im更慢，會野外露出程式碼   |
| 舉例 |     C&C++             |     java                            |  python、ruby        |
#### from code to execute
![[../附件/Pasted image 20231016192216.png]]
### cloud system
#### [[三種雲端]]
#### [[四種部屬雲]]
#### 功能
-  隨需應變自助服務(On-Demand Self-Service) 
	- 消費者可據需求自己來
-  網路使用無所不在(Broad Network Access) 
	- 不受限制的通過網路使用服務
-  資源彙整(Resource Pooling)
	- 務供應者透過多重租賃模式服務消費者，可依據消費者要求 指派實體及虛擬資源
	- 消費者通常無法確知資源所在地點。
- 高度彈性(Rapid Elasticity)
	- 因應消費者要求隨時且快速地調整資源規模
- 計算服務(Measured Service)
	- 自動控制、最佳化與量測各類服務資源
#### 八大特色
• 大規模的可伸縮性(Massive Scale) 
• 可修復能力(Resilience) 
• 同質性(Homogeneity) 
• 廣泛的地理分布 
• 虛擬化(Virtualization) 
• 服務導向特性(Service Oriented) 
• 低費用(Low Cost) 
• 先進的安全措施
## Seven great ideas in computer organization 
## How to evaluate the performance of a computer performance