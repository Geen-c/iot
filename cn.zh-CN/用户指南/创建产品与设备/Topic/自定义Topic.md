# 自定义Topic {#concept_ppk_rz4_k2b .concept}

本文介绍基础版产品和高级版产品如何自定义Topic。

1.  在产品列表页面，选择需要自定义Topic的产品，单击右侧的**查看**，进入产品详情页面。
2.  选择消息通信，单击**定义Topic类**，系统显示定义Topic类窗口。
3.  自定义Topic类。

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/15450/15349042307118_zh-CN.png)

    -   Topic类：根据界面上Topic规则设置Topic类。
    -   设备操作权限：设备对该Topic的操作权限，可设置为发布、订阅、发布和订阅。
    -   描述：对自定义的Topic进行描述，可以为空。
4.  物联网平台也支持自定义带通配符的Topic类。如果您需要订阅通配符，则首先需要自定义带通配符的Topic，再订阅。

    创建Topic类时，参数设置如下：

    -   Topic类：您可以创建带有通配符`#`或者`+`的Topic类。通配符说明可参见[表 1](cn.zh-CN/用户指南/创建产品与设备/Topic/什么是Topic.md#table_hw3_gzz_vdb)。

        **说明：** 通配符`#`只能出现在Topic类的最后面。

    -   设备操作权限：设备对该Topic的操作权限，只有选择订阅，才能支持填写通配符。
    -   描述：对自定义的Topic进行描述，可以为空。
    已创建的带通配符的Topic，在设备的Topic列表页面不支持执行**发布消息**的操作。

    **说明：** 当前基础版产品的设备详情页有Topic列表，高级版产品的设备详情页，暂无Topic列表。

5.  单击**确认**，完成自定义Topic类。

