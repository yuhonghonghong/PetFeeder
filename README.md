tuya-app-sdk
==
## This project is developed using Tuya SDK, which enables you to quickly develop branded apps connecting and controlling smart scenarios of many devices.For more information, please check Tuya Developer Website.
# 一、智能宠物喂食器
##  宠物自动喂食器
# 二、方案应用场景
##  应用场景
### 该方案应用于家中的小型宠物(例如猫、贵宾犬等)的喂食。许多人由于突发性的事件不能按计划时间回到家中喂食宠物，会造成宠物长时间挨饿甚至饿死，所以自动喂食器的需求日益增加。许多社区会有一些人提供“代喂、代养”等服务，由本人亲身体验得出此服务不足之处：代养服务需要把宠物寄养到别人家中，收费较高；代喂服务需要把主人房间钥匙提供给代喂人，不仅不安全而且也是有偿服务。对比下来，自动喂食器的性价比就更高了。
# 三、项目要点
* 出粮方式
  * 用减速电机把一定量的粮传到出粮口
* 投食方式
  * 自动投食。通过设备上的按键一键投食,同时通过涂鸦三明治开发套件的wifi模组将数据上传到涂鸦iot云平台。上传投食记录便于用户查看
  * 远程投食。通过app上的投食功能按键远程投食
* 创建喂食计划
  * 用户通过app创建一个投食计划。投食计划包括时间间隔，喂食份数等参数设置。需要同步到本地设备端。投食方式为自动投食或到点提示手动投食方式
* 余粮不足以及电量不足LED提醒
* 设备端供电由外置电源适配器和备用锂电池供电。内置电池设置是防止家里停电时设备不能正常工作。
* 给外壳增加配重块防止宠物太容易碰翻设备
# 四、物料准备
* 涂鸦三明治开发套件
* STM32开发板
* 减速电机
* 纸板/亚克力板
* 涂鸦平台
* 配重块
# 五、开发计划
## 3月31前完成
*  3月15前准备物料
*  3月15-3月30日嵌入式开发、云开发
*  3月30日前整体调试
