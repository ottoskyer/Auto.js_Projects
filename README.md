# Ant Forest  

![AF_Pic](https://github.com/SuperMonster002/Hello_Sockpuppet/raw/master/Ant_Forest_Banner_361%C3%97103.png)
###### 蚂蚁森林能量智能收取脚本 (基于Auto.js)
###### Auto.js-based alipay ant forest energy intelligent collection script

******
### 小私房话
******
:neutral_face:  
最近Bug较多  
已经可以确定问题根源  
是蚂蚁森林随机变更控件文本位置    
进而导致识别控件出错  
正在逐步修复  
请大家稍安勿躁  
并及时反馈新问题  
反馈时最好开启开发者测试模式并附上截图    
大家的支持是我最大的动力  
谢谢你们  

:writing_hand:  
定时任务等Pro版本相应API完善之后再做    

******
### 使用说明
******
1. 下载项目 ([点此下载最新项目包](https://github.com/SuperMonster003/Auto.js_Projects/archive/Ant_Forest.zip) 或 点击页面右侧绿色 `Clone or download` 按钮 手机浏览器需在项目主页拉到底部点击 `Desktop version`)  
2. 将项目中的全部文件放置于手机存储 (推荐 `Auto.js` 默认可识别目录 如 `/sdcard/Scripts/` 或 `/sdcard/脚本/` )  
3. 使用 `Auto.js` 运行 `Ant_Forest_Launcher.js` 文件  
4. 欢迎使用并反馈  
  
> 安卓系统最低版本: `7.0` / `Android Nougat` / `Android N`  
> Root: `无需Root`
  
> "Auto.js"已测试版本:   
>> [`4.0.4 Alpha5`](https://github.com/SuperMonster002/Hello_Sockpuppet/blob/master/%5Bauto.js%5D%5B4.0.4_alpha5%5D(2caea4b4).apk?raw=true)  
>> [`4.0.4 Alpha6`](https://github.com/SuperMonster002/Hello_Sockpuppet/blob/master/%5Bauto.js%5D%5B4.0.4_alpha6%5D(3bd7f41f).apk?raw=true)  
>> [`4.0.4 Alpha7`](https://github.com/SuperMonster002/Hello_Sockpuppet/blob/master/%5Bauto.js%5D%5B4.0.4_alpha7%5D(9ca9e0fd).apk?raw=true)  
>> [`4.0.4 Alpha8`](https://github.com/SuperMonster002/Hello_Sockpuppet/blob/master/%5Bauto.js%5D%5B4.0.4_alpha8%5D(bc2d6359).apk?raw=true)  
>> [`4.0.4 Alpha9`](https://github.com/SuperMonster002/Hello_Sockpuppet/blob/master/%5Bauto.js%5D%5B4.0.4_alpha9%5D(1aef8167).apk?raw=true)  
>> [`4.0.4 Alpha10`](https://github.com/SuperMonster002/Hello_Sockpuppet/blob/master/%5Bauto.js%5D%5B4.0.4_alpha10%5D(805e19a6).apk?raw=true)  
>> [`4.0.4 Alpha11`](https://github.com/SuperMonster002/Hello_Sockpuppet/blob/master/%5Bauto.js%5D%5B4.0.4_alpha11%5D(d3adc9b3).apk?raw=true)  
>> [`4.1.0 Alpha`](https://github.com/SuperMonster002/Hello_Sockpuppet/blob/master/%5Bauto.js%5D%5B4.1.0_alpha%5D(7312bb3f).apk?raw=true)  
>> [`4.1.0 Alpha2`](https://github.com/SuperMonster002/Hello_Sockpuppet/blob/master/%5Bauto.js%5D%5B4.1.0_alpha2%5D(3a990e03).apk?raw=true)  
>> [`4.1.0 Alpha5`](https://github.com/SuperMonster002/Hello_Sockpuppet/raw/master/%5Bauto.js%5D%5B4.1.0_alpha5%5D(ff5bd9b3).apk?raw=true) `(推荐)`  
>> [`4.1.1 Alpha`](https://github.com/SuperMonster002/Hello_Sockpuppet/blob/master/%5Bauto.js%5D%5B4.1.1_alpha%5D(accea680).apk?raw=true)  
>> [`4.1.1 Alpha2`](https://github.com/SuperMonster002/Hello_Sockpuppet/raw/master/%5Bauto.js%5D%5B4.1.1_alpha2%5D%5Barm-v7%5D(b69a4e23).apk?raw=true) `(推荐)`  
>> [`Pro 7.0.0-4`](https://github.com/SuperMonster002/Hello_Sockpuppet/raw/master/%5Bauto.js%5D%5BPro_7.0.0-4%5D(536f3432).apk?raw=true)  
>> [`Pro 7.0.0-6`](https://github.com/SuperMonster002/Hello_Sockpuppet/raw/master/%5Bauto.js%5D%5BPro_7.0.0-6%5D(5b1a1698).apk?raw=true)  
>> [`Pro 7.0.2-4`](https://github.com/SuperMonster002/Hello_Sockpuppet/blob/master/%5Bauto.js%5D%5Bpro_7.0.2-4%5D(a581978d).apk?raw=true)      
>> [`Pro 7.0.3-0`](https://github.com/SuperMonster002/Hello_Sockpuppet/blob/master/%5Bauto.js%5D%5Bpro_7.0.3-0%5D(1e13098f).apk?raw=true) `(推荐)`    

>"Auto.js"不适用版本:
>> [`查看其他版本的已知问题`](https://github.com/SuperMonster002/Hello_Sockpuppet/blob/master/README.md)

******
### 功能简介
******
* 收取好友能量
* 帮收好友能量 (可开关)  
* 收取自己能量  
** 指定时间范围内不间断监测自己的能量  
** ~~脚本辅助优化时间间隔~~  
* 能量收取结果统计/展示 (floaty/toast方式)
* 自动解锁屏幕  
** 可通过配置向导页面实现解锁密码录入  
* 定时执行任务  
** ~~使用配置向导设置Auto.js定时任务~~    
** 也可结合 `Xposed Edge Pro` 或 `Tasker` 实现定时任务  
* 多任务~~智能~~排队  
* 多语言支持 (简体中文 ~~繁体中文~~ ~~英语~~)  
** ~~根据系统语言自动切换语言 (可开关)~~
* 黑名单机制  
** 能量保护罩好友自动加入黑名单/自动解除    
** 黑名单详细信息提示 (控制台)  
** 用户自行增删黑名单好友 (手动输入/列表选取)  
* 信息加密存储  
** 自动生成"密文映射"字典文件  
** 使用密文存储账户信息/解锁密码等敏感信息  
* ~~账户智能切换~~  
** ~~防止其他账户 (如支付宝小号) 意外收取 (需录入主账户信息)~~      
** ~~主账户收取完毕可自动切换回之前登录的账户 (如果有此账户信息)~~  
* 适应恶劣条件  
** 脚本在恶劣条件下仍可正常运行或识别异常 (网络条件较差/~~意外来电~~/~~支付宝异常退出~~/支付宝更新弹窗/~~广告弹窗~~等)  
* 图形配置页面  
* ###### 其他功能详见[使用说明书](https://github.com/SuperMonster003/Auto.js_Projects/blob/Ant_Forest/Documents/Ant_Forest_User_Manual.md)

******
### 版本历史
******
# v1.6.23 Alpha5
###### 2019/05/17
* `新增` 工具函数模块新增clickAction()  
* `新增` 工具函数模块新增JSDoc使用示例  
* `修复` 工具函数messageAction()部分打印格式错误  
* `修复` 工具函数killThisApp()部分逻辑错误  
* `优化` 工具函数parseAppName()搜索效率  
* `优化` 工具函数中剔除部分无用Raw工具函数  

# v1.6.23 Alpha4
###### 2019/05/17
* `修复` 能量罩使用信息采集异常
* `优化` 工具函数模块化 (6项)  

# v1.6.23 Alpha3
###### 2019/05/16
* `修复` 标题控件bottom数据获取异常

# v1.6.23 Alpha2
###### 2019/05/16
* `修复` OpenCV视觉库断言异常 (试修)

# v1.6.23 Alpha
###### 2019/05/16
* `优化` 提升收取/帮收统计数据获取稳定性  
* `优化` 放宽黑名单颜色识别条件  
* `优化` 排队机制加入排队等待最大超时  

# v1.6.22 Alpha10
###### 2019/05/15
* `修复` 统计好友能量收取值容易失败的问题  
* `优化` 摒弃收取完毕返回主页时的无用判断  

# v1.6.22 Alpha9
###### 2019/05/15
* `修复` 帮收统计数据无效的问题  

# v1.6.22 Alpha8
###### 2019/05/15
* `优化` 优化最小化支付宝工具函数逻辑
* `优化` 支付宝为非简体中文语言时的检测准确性
* `优化` 通过记忆pickup()返回结果提升控件搜索效率  
* `优化` 撤回截图权限申请函数的监测解放  

# v1.6.22 Alpha7
###### 2019/05/15
* `修复` 图形配置页面返回按钮失效的问题  

# v1.6.22 Alpha6
###### 2019/05/15
* `修复` clickBounds()携带press参数时运行异常  
* `修复` 排行榜列表底部判断异常

# v1.6.22 Alpha5
###### 2019/05/15
* `修复` 好友昵称获取失败的问题  

# v1.6.22 Alpha4
###### 2019/05/15
* `修复` 标题控件bottom数据获取异常
* `修复` 排行榜列表底部判断异常

# v1.6.22 Alpha3
###### 2019/05/15
* `修复` 标题控件bottom数据获取异常  

# v1.6.22 Alpha2
###### 2019/05/15
* `修复` 自定义黑名单采集好友列表失败的问题  

# v1.6.22 Alpha
###### 2019/05/15
* `修复` 排行榜列表底部判断异常

# v1.6.21
###### 2019/05/14
* `修复` pickup()方法遗漏样本的问题  

# v1.6.20
###### 2019/05/14
* `优化` 使用自定义pickup()方法获取部分控件  
* `优化` 提升黑名单检测准确率  

# v1.6.19
###### 2019/05/13
* `修复` 弃用导致控件抓取缓慢的"useUsageStats"参数 `添加于 v1.6.18`  
* `修复` 图形配置页面在部分机型显示错位问题  

# v1.6.18
###### 2019/05/13
* `修复` 排行榜误触虚拟按键的问题  
* `优化` ~~使用"使用统计权限"提升currentPackage()准确性~~ `去除于 v1.6.19`  

# v1.6.17
###### 2019/05/10
* `修复` 进入好友列表后可能导致参考控件获取失败的问题  
* `修复` 特殊密码解锁方案修复  

# v1.6.16
###### 2019/05/10
* `修复` 密码解锁误判转移失效的问题  
* `优化` 排行榜好友样本采集效率  

# v1.6.15
###### 2019/05/10
* `修复` 部分机型PIN码解锁误判为密码解锁的问题  

# v1.6.14
###### 2019/05/10
* `修复` 启动完成条件检查必备/可选条件的逻辑错误  
* `修复` 账户未登录状态时脚本运行超长耗时问题  
* `优化` 重写启动完成条件判断逻辑  
* `优化` 还原部分click()方法以避免屏幕容易超时关闭  

# v1.6.13
###### 2019/05/09
* `修复` "首页状态准备"失败及定位"查看更多好友"失败的问题  
* `优化` 解锁模块适配部分魅族设备 (当前仅限数字PIN码方案)  

# v1.6.12
###### 2019/05/09
* `修复` "首页状态准备"易失败的问题 (试修)
* `优化` 适配图案解锁动态控件  

# v1.6.11
###### 2019/05/08
* `修复` clickBounds()工具函数可能出现的空指针问题  
* `优化` 图案解锁布局判断逻辑  

# v1.6.10
###### 2019/05/08
* `新增` 截图权限申请失败后自动重启任务  

# v1.6.9
###### 2019/05/08
* `优化` 提升锁屏布局工具使用稳定性 增加更多用户操作提示  
* `优化` 使用shell()方法完全替代可能导致任务卡死的KeyCode()方法
  
# v1.6.8
###### 2019/05/08
* `优化` 增加启动条件检测样本  
* `优化` 本地数据尝试解锁失败后从默认值 (非当前值) 开始尝试  

# v1.6.7
###### 2019/05/07
* `修复` debugInfo()方法引用无效的问题  
* `优化` 控件刷新工具函数只在必要时触发  

# v1.6.6
###### 2019/05/07
* `修复` keycode(26)导致任务残留的问题
* `修复` 魅族设备使用自动关屏功能时卡死的问题  
* `修复` 最小化支付宝功能异常问题  
* `修复` 截图权限申请容易失败的问题  
* `修复` 锁屏布局工具无法使用关屏功能时自动退出的问题  

# v1.6.5
###### 2019/05/06
* `修复` 音量键重复监听问题  
* `修复` 点击"查看更多好友"备用方案无效的问题  
* `修复` 排行榜首页好友可能丢失采集的问题  
* `修复` 支付宝关闭异常时最小化功能无效的问题  
* `优化` 图案解锁滑动效率及精确性  
* `优化` 进入好友森林超时检测的稳定性  
* `优化` 优化keycode()工具函数以避免假死  

# v1.6.4
###### 2019/05/05
* `新增` 版本查看与检查更新功能 (仅检查版本号)
* `修复` 解锁模块可能因click()方法无限等待的问题
* `修复` 某些设备Floaty消息一闪即逝的问题 (试修)  
* `修复` 图案解锁坐标点在某些设备偏移的问题 (试修)  
* `修复` 锁屏布局工具对话框点击后无效且直接退出的问题 (试修)  
* `修复` 因修复纵向伸缩而引发的纵向坐标异常的问题
* `修复` 翻页时可能遗漏屏幕底部排行榜好友的问题  
* `优化` 增加支付宝启动检测条件及启动完成检测条件判断样本  
* `优化` 关闭某些clickObject()方法无用的debug消息    

# v1.6.3
###### 2019/05/03
* `修复` 点击能量球后可能导致统计收取数据无限循环的问题

# v1.6.2
###### 2019/05/02
* `修复` 屏幕比例非16:9的设备纵向伸缩失调问题  

# v1.6.1
###### 2019/05/01
* `修复` 新版支付宝返回上一级页面失败的问题  

# v1.6.0
###### 2019/04/30
* `新增` 图形页面配置功能: 黑名单管理
* `修复` 自定义黑名单检测失效问题  
* `修复` 从列表添加好友功能失效问题  

# v1.5.21
###### 2019/04/29
* `新增` 图形配置页面自定义黑名单页面骨架  

# v1.5.20
###### 2019/04/28
* `新增` 按键监听 VOL+: 停止所有脚本 VOL-: 停止当前脚本  
* `修复` 控件点击偶尔出现假死现象  
* `修复` 排行榜点击目标时误点击虚拟按键的问题  
* `优化` 使用Git命令真正精简仓库体积 _[issue #5](https://github.com/SuperMonster003/Ant_Forest/issues/5)_  
* `优化` 点击"查看更多好友"增加备用方案  

# v1.5.19
###### 2019/04/27
* `新增` 自收功能配置开关  
* `新增` 启动器的Bug版本检测提示  
* `新增` 图形配置页面启动器"加载中"页面  
* `修复` 某些版本基础功能异常导致Bug版本检测失效的问题  
* `修复` 某些版本在Bug提示过程中依然继续运行的问题  
* `修复` 排行榜点击目标时误点击虚拟按键的问题  

# v1.5.18
###### 2019/04/26
* `新增` Bug版本检测提示 (当前所有版本)  
* `优化` 完善开发者测试模式  
* `优化` 及时回收新生成的images对象  
* `优化` 用press()方法模拟点击  
* `优化` 用swipe()方法模拟滑动 增加可用性检测  

# v1.5.17
###### 2019/04/25
* `优化` 完善开发者测试模式  
* `优化` 截图申请工具函数判断逻辑  
* `优化` auto.waitFor()不被支持时自动使用auto()  
* `优化` getVerName()工具函数兼容性  
* `修复` 解锁模块读取存储数据时的常规错误  

# v1.5.16
###### 2019/04/24
* `新增` 图形配置页面返回按钮  
* `新增` 开发者测试模式 (暂不完全)  
* `新增` 图形页面配置功能: 消息提示  

# v1.5.15
###### 2019/04/23
* `新增` 适配部分EMUI机型的自动解锁方案 _[issue #8](https://github.com/SuperMonster003/Ant_Forest/issues/8#issuecomment-485403816)_  
* `修复` 帮收功能关闭后依然进入可帮收好友森林的问题
* `修复` 锁屏布局工具滑动失败导致脚本异常退出的问题
* `修复` 引入的dialogs模块中多选对话框功能异常 (临时解决方案)
* `优化` 增加截图区域检测 防止OpenCV组件异常
* `优化` messageAction工具实用性 (增加dash显示方式)
* `优化` 去除容易导致死循环的失焦拉回功能 `添加于 v1.5.12`

# v1.5.14
###### 2019/04/22
* `修复` 首次运行可能导致支付宝拉起失败且脚本长时间无响应的问题
* `修复` 语言检测控件查找超时导致脚本运行失败的问题
* `修复` 自动解锁可能出现的解锁图层检测异常 _[issue #6](https://github.com/SuperMonster003/Ant_Forest/issues/6#issuecomment-484788911)_
* `修复` 深拷贝工具函数克隆数组失效的问题  

# v1.5.13
###### 2019/04/21
* `优化` keycode()工具函数内部逻辑

# v1.5.12
###### 2019/04/20
* `新增` ~~支付宝失焦后在指定时间内自动拉回功能 (可设置开关及白名单)~~ `去除于 v1.5.15`
* `修复` 解锁模块可能导致屏幕无法超时自动关闭的问题  

# v1.5.11
###### 2019/04/19
* `修复` 自动解锁可能出现的异常重复上滑现象 _[issue #6](https://github.com/SuperMonster003/Ant_Forest/issues/6#issuecomment-484503159)_

# v1.5.10
###### 2019/04/18
* `新增` 适配采用"Gxzw"屏下指纹设备的自动解锁方案 _[issue #6](https://github.com/SuperMonster003/Ant_Forest/issues/6#issuecomment-484361198)_  
* `优化` 锁屏布局工具控件信息采集方式  

# v1.5.9
###### 2019/04/17
* `修复` Shell模块返回代码137导致按键模拟无效的问题  
* `优化` 排行榜样本采集稳定性 _[issue #4](https://github.com/SuperMonster003/Ant_Forest/issues/4#issuecomment-483967078)_

# v1.5.8
###### 2019/04/17
* `新增` 锁屏布局工具 方便用户发送锁屏布局信息给开发者  
* `修复` 判断初始准备条件时可能出现无法匹配ViewId的问题 _[issue #4](https://github.com/SuperMonster003/Ant_Forest/issues/4#issuecomment-483958381)_  
* `优化` 解锁模块稳定性

# v1.5.7
###### 2019/04/17
* `优化` 排行榜样本采集稳定性 _[issue #4](https://github.com/SuperMonster003/Ant_Forest/issues/4)_  
* `优化` 删除无关文件以缩小仓库体积 _[issue #5](https://github.com/SuperMonster003/Ant_Forest/issues/5)_

# v1.5.6
###### 2019/04/16
* `新增` 解锁模块加入MIUI支持  
* `修复` 关屏功能异常
* `优化` 帮收功能关闭时的收取逻辑  
* `优化` 简化智能返回逻辑  

# v1.5.5
###### 2019/04/15
* `新增` 重写解锁模块 (暂未加入MIUI支持)  
* `新增` 解锁功能开关检测提示及SDK版本检测提示  
* `修复` 循环监测自己能量逻辑错误导致的效率低下问题  
* `修复` 获取排行榜参考范围因控件出现延迟导致的异常  

# v1.5.4
###### 2019/04/14
* `修复` 循环监测自己能量的统计数据错误  

# v1.5.3
###### 2019/04/13
* `新增` 图形配置页面黑名单管理骨架  
* `修复` dialogs模块缺失 _[issue #2](https://github.com/SuperMonster003/Ant_Forest/issues/2)_  

# v1.5.2
###### 2019/04/12
* `修复` dialogs模块在某些版本不兼容的问题  
* `修复` 图形配置页面返回保存时数据存放错误的问题  
* `修复` 图形配置页面某些关闭按钮无效的问题  

# v1.5.1
###### 2019/04/12
* `新增` Auto.js版本异常提示  
* `修复` 版本异常检测与运行配置检测逻辑顺序  
* `优化` 独立解锁配置向导 整合到图形配置页面中  
* `优化` 调用UI执行脚本去Root化  
* `优化` 调用支付宝登录页面去Root化  

# v1.5.0
###### 2019/04/11
* `新增` 图形配置页面正式上线  
* `修复` 已Root设备无法调起图形设置页面问题  

# v1.4.11
###### 2019/04/11
* `新增` 图形配置页面与执行脚本数据项建立关联  

# v1.4.10
###### 2019/04/10
* `修复` 图形配置页面对象相等判定工具的逻辑错误  
* `修复` 部分函数内部变量覆盖函数定义的问题 _[issue #1](https://github.com/SuperMonster003/Ant_Forest/issues/1)_  
* `优化` 完善图形配置页面自己能量时间区间管理工具  

# v1.4.9
###### 2019/04/09
* `新增` 图形配置页面颜色设置对话框文字跟随输入值变色功能  
* `新增` 图形配置页面颜色相关hint区域的色彩指示图标  
* `修复` 图形配置页面还原后保存按钮无效  
* `修复` 图形配置页面还原后无法再次还原  
* `修复` 图形配置页面帮收功能总开关联动性  
* `修复` 图形配置页面初始化状态为关闭的开关子项隐藏失败问题  
* `优化` "标题警示"工具兼容性  

# v1.4.8
###### 2019/04/08
* `修复` 图形配置页面对象深拷贝不完全问题  

# v1.4.7
###### 2019/04/07
* `修复` 图形配置页面监测自己能量开关数据关联错误
* `修复` 图形配置页面判断对象相等的逻辑错误
* `修复` 图形配置页面会话存储/本次存储二层以上对象变量互相影响的错误  

# v1.4.6
###### 2019/04/06
* `优化` 图形配置页面数据与控件关联性
* `优化` 图形配置页面本地数据存取逻辑

# v1.4.5
###### 2019/04/05
* `新增` 图形配置页面重置功能
* `新增` 图形配置页面数据实时更新
* `优化` 图形配置页面列表项功能增强模块化
* `优化` 图形配置页面退出/保存逻辑

# v1.4.4
###### 2019/04/04
* `新增` 图形配置页面保存按钮功能联动
* `新增` 数据样本不足导致统计结果异常的错误提示
* `修复` KeyCode()不可用问题

# v1.4.3
###### 2019/04/03
* `优化` 图形配置页面列表项功能模块化

# v1.4.2
###### 2019/04/03
* `修复` 图形配置页面滑动效果闪烁问题

# v1.4.1
###### 2019/04/02
* `新增` 图形配置页面主页View框架
* `新增` 图形配置页面子页面进出滑动效果
* `新增` 图形配置页面退出保存提示

# v1.4.0
###### 2019/04/02
* `新增` 图形配置页面 (骨架)

# v1.3.8
###### 2019/04/01
* `修复` 本地文件创建失败的问题

# v1.3.7
###### 2019/04/01
* `新增` `Auto.js Pro` 版本兼容
* `修复` 解锁配置向导在 `4.1.1 alpha2` 的兼容问题  
 
# v1.3.6
###### 2019/03/30
* `修复` floaty结果显示hint区域溢出问题

# v1.3.5
###### 2019/03/29
* `新增` floaty方式显示收取结果 (可与toast方式切换选择)
* `修复` floaty显示问题及其他异常处理
* `修复` 截图权限申请容易高失败率问题
* `优化` 帮收能量球检测准确性

# v1.3.4
###### 2019/03/28
* `修复` 收取能量统计失败的错误消息处理

# v1.3.3
###### 2019/03/27
* `新增` 自己能量球数等于6时的收取处理
* `修复` 帮收球和收取球同时存在时可能出现收取失效的问题
* `修复` 帮收能量球遗留数据清空滞缓问题
* `优化` 智能返回功能的APP退出逻辑

# v1.3.2
###### 2019/03/26
* `新增` 自己能量球数等于6时的收取处理
* `优化` 语言切换控制台信息显示
* `优化` 截图权限申请的异常处理

# v1.3.1
###### 2019/03/25
* `新增` 截图权限申请工具函数
* `修复` 保护罩颜色识别区域分辨率适配问题
* `灵感` 可设置低亮度运行并在运行结束后恢复状态

# v1.3.0
###### 2019/03/25
* `新增` 脚本运行超时配置项 (单次最大运行时间)
* `修复` 解锁功能配置向导toast消息遮挡问题 (替换为content显示方式)
* `修复` 黑名单自动管理功能的时间标记滞留问题
* `修复` 帮收能量单位为"kg"时的数据统计异常
* `优化` 解锁功能配置向导增加密码示例
* `优化` 密文模块的方法参数调整
* `优化` 新的能量收取逻辑下提升帮收效率
* `优化` 智能返回机制 (前台拉起优先于强制关闭)
* `优化` 增加进入好友森林后没有能量球可收取/帮收时的控制台消息

# v1.2.1
###### 2019/03/24
* `优化` 优化保护罩检测/能量收取逻辑
* `修复` 解锁功能配置向导第一步返回键失效

# v1.2.0
###### 2019/03/24
* `新增` 能量罩好友黑名单自动管理功能
* `新增` 解锁配置向导
* `新增` 使用自定义本地存储模块模拟Storage模块 (不受卸载APP/清除数据影响)
* `修复` 解锁模块通用化
* `优化` 整合控制台详细信息开关
* `优化` 能量罩检测效率

# v1.1.2
###### 2019/03/21
* `优化` 优化帮收好友能量逻辑 提升收取效率/准确率/稳定性
* `优化` 提升定位"查找更多好友"按钮稳定性并增加异常处理
* `灵感` 使用[JSEncrypt](https://github.com/travist/jsencrypt)结合或替代原有加密方式
* `灵感` 个人能量球总数为6时 收取后可能出现新的能量球
* `灵感` 好友能量球总数为6时 帮收后再次进入他/她的森林 可能有新的能量球
* `灵感` 功能模块分离

# v1.1.1
###### 2019/03/20 
* `修复` 模块/脚本文件的依赖关系
* `修复` 密文工具功能失效
* `优化` 全面调整代码结构

# v1.1.0
###### 2019/03/19 - 脚本可用性暂未测试 
* `新增` 自动检测/生成/引用本地"密文映射"文件
* `移除` 指定账户智能切换功能 (暂时关闭)
* `修复` 收取完毕返回好友列表时 当前屏幕信息没有及时处理即开始滑屏
* `灵感` 账户智能切换 (账户录入 已录入账户的选择/信息更新) 
* `灵感` 使用密文解析工具时若发现"密文映射"文件异常 及时报错 

# v1.0.0
###### 2019/03/19 - 此版本依赖设备本地密文映射文件 因此暂不可用
* `新增` 自动收取好友能量 (基于Auto.js控件/颜色识别)
* `新增` 自动帮收好友能量
* `新增` 可在指定时间范围内不间断检测自己的能量 (感谢 [e1399579](https://github.com/e1399579/autojs))
* `新增` 自动解锁屏幕 (感谢 [e1399579](https://github.com/e1399579/autojs))
* `新增` 脚本排队机制 (感谢 [e1399579](https://github.com/e1399579/autojs))
* `新增` 脚本运行结束后智能关屏 (感谢 [e1399579](https://github.com/e1399579/autojs))
* `新增` 脚本运行结束后智能保留/结束APP进程
* `新增` 自动切换APP语言 (目前暂时统一切换为简体中文)
* `新增` 若当前用户不是指定账户 (主账户) 则自动切换为主账户 (需录入账户信息)
* `新增` 可显示/关闭能量罩的剩余时间 (因黑名单系统未完成 暂未投入使用)
* `新增` 可显示/关闭收取/帮收好友能量的详细信息
* `新增` 可分别显示收取自己能量的总数与收取好友能量的总数
* `新增` 将Auto.js的日志保存在指定的文件中 (Auto.js v4.1.0版本以上)
* `优化` 精简部分无用的方法
* `优化` 脚本部分参数可供用户自行配置 (目前只可在脚本文件中配置)
* `优化` 部分参数值可以自动修正/修复 
* `优化` 恶劣条件下 (不稳定的互联网连接等) 的脚本稳定性 
* `优化` 收取能量时 先保证能量收取成功 然后立即返回 (稳定性/高效率) 
* `优化` 帮收能量时 若能量帮收成功 立即返回 (高效率) 
* `优化` 线程循环展开列表 节约滑动好友列表时"加载中"的时间 (高效率) 
* `优化` 线程监视好友列表底部 一旦进入屏幕 立即停止列表滑动 (高效率) 
* `优化` 优化好友列表滑动的稳定性 
* `灵感` ~~能量罩用户黑名单功能实现 (目前只是空壳)~~ v2.0.0
* `灵感` 脚本使用说明文档 (包含使用细节和注意事项)
* `灵感` ~~自动生成并引用本地"密文映射"字典~~ v1.1.0
* `灵感` ~~本地"密文映射"加解密工具~~ v1.1.0
* `灵感` 主要方法的JSDoc注释
* `灵感` ~~可用于配置脚本的UI界面 (高交互性)~~ v1.5.0
* `灵感` ~~帮收好友能量增加精准性及效率~~ v1.1.2
* `灵感` 登录主账户之前记录当前用户信息 脚本结束后恢复登录 (需录入账户信息)
* `灵感` ~~额外文件的生成/存取不受机型限制~~ v2.0.0
* `灵感` 语言智能切换且可供用户配置
* `灵感` ~~使用Floaty方式替代Toast消息显示~~ v1.3.5
* `灵感` 好友数量小于10的异常处理
* `灵感` ~~shell强制结束APP的替代方案 (避免经常出现的几秒钟黑屏)~~ v1.5.1
