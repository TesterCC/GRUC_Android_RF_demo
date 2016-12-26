##测试工程创建及维护人员
* GlobalRoam Chengdu R&D -- QA Team

##关于该测试工程
* 该工程是为`GRUC` 项目构建
* 该工程开发环境相关信息如下（缺少环境的请自行搜索进行相关配置）：
    * RobotFramework
    * ANT
    * Python2.7
    * RobotFramework-appiumlibrary
    * Appium
    * JDK
    * Android SDK
    * Windows 7


##Demo结构
* /installapp      `存放测试apk`
* AllResource.txt  `统一管理配置加载`
* gruc_android_appium_config.txt  `appium启动配置`
* gruc_android_system_elements.txt  `系统控件元素定位`
* gruc_aty_signin_elements.txt  `登录界面元素定位`
* gruc_test_data.txt  `数据驱动数据管理`
* gruc_user_keywords.txt  `自定义关键字管理`
* TestCases.txt  `测试用例管理`


##Demo开放目的
* 给出基础Demo，方便大家学习RF+Appium的Android自动化方式。
* 利用此Demo结合Git和Jenkins学习持续集成知识。