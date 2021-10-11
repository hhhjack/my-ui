突发异想想自己搞一套ui试试，用vue吧。2021/7/22



首先得思索一下需要完成哪些组件

下面是参考element-ui

- Basic
  - Layout
  - Container
  - Color
  - Border
  - Icon
  - Button
  - Link
- Form
  - Radio
  - Checkbox
  - Input
  - InputNumber
  - Select
  - Cascader
  - Switch
  - Slider
  - TimePicker
  - DatePicker
  - DateTimePicker
  - Upload
  - Rate
  - ColorPicker
  - Transfer
  - Form
- Data
  - Table
  - Tag
  - Progress
  - Tree
  - Pagination
  - Badge
  - Avatar
  - Skeleton
  - Empty
- Notice
  - Alert
  - Loading
  - Message
  - MessageBox
  - Notification
  - NavMenu
  - Tabs
  - Breadcrumb
  - PageHeader
  - Dropdown
  - Steps
- Others
  - Dialog
  - Tooltip
  - Popover
  - Popconfirm
  - Card
  - Carousel
  - Collapse
  - Timeline
  - Divider
  - Calendar
  - Image
  - Backtop
  - InfiniteScroll
  - Drawer

每实现一个打一个√

先从vue下手吧，许久没动手搞过，从教程开始安排

弄清楚组件化那些，再来搞这些



中间懒了许久，今天开始算是重新动工吧！最近在看些好看的设计，看到好看的都会收藏在下面！

2021/9/22

## 颜色

![image-20210922095549897](C:\Users\zhuxiaoyue\AppData\Roaming\Typora\typora-user-images\image-20210922095549897.png)![image-20210922095707025](file://C:/Users/zhuxiaoyue/AppData/Roaming/Typora/typora-user-images/image-20210922095707025.png?lastModify=1632275940)![image-20210922095904544](file://C:/Users/zhuxiaoyue/AppData/Roaming/Typora/typora-user-images/image-20210922095904544.png?lastModify=1632275940)

![image-20210922151206974](C:\Users\zhuxiaoyue\AppData\Roaming\Typora\typora-user-images\image-20210922151206974.png)

![image-20210922151231398](C:\Users\zhuxiaoyue\AppData\Roaming\Typora\typora-user-images\image-20210922151231398.png)

![image-20210922151254958](C:\Users\zhuxiaoyue\AppData\Roaming\Typora\typora-user-images\image-20210922151254958.png)

![image-20210922151405083](C:\Users\zhuxiaoyue\AppData\Roaming\Typora\typora-user-images\image-20210922151405083.png)

![image-20210922151432365](C:\Users\zhuxiaoyue\AppData\Roaming\Typora\typora-user-images\image-20210922151432365.png)

![image-20210922151452645](C:\Users\zhuxiaoyue\AppData\Roaming\Typora\typora-user-images\image-20210922151452645.png)

![image-20210922151518437](C:\Users\zhuxiaoyue\AppData\Roaming\Typora\typora-user-images\image-20210922151518437.png)

![image-20210922151548349](C:\Users\zhuxiaoyue\AppData\Roaming\Typora\typora-user-images\image-20210922151548349.png)

![image-20210922151612806](C:\Users\zhuxiaoyue\AppData\Roaming\Typora\typora-user-images\image-20210922151612806.png)

![image-20210922151640507](C:\Users\zhuxiaoyue\AppData\Roaming\Typora\typora-user-images\image-20210922151640507.png)

![image-20210922151709883](C:\Users\zhuxiaoyue\AppData\Roaming\Typora\typora-user-images\image-20210922151709883.png)

![image-20210922151756355](C:\Users\zhuxiaoyue\AppData\Roaming\Typora\typora-user-images\image-20210922151756355.png)

![image-20210922151813667](C:\Users\zhuxiaoyue\AppData\Roaming\Typora\typora-user-images\image-20210922151813667.png)

![image-20210922151847558](C:\Users\zhuxiaoyue\AppData\Roaming\Typora\typora-user-images\image-20210922151847558.png)

![image-20210922151928548](C:\Users\zhuxiaoyue\AppData\Roaming\Typora\typora-user-images\image-20210922151928548.png)

![image-20210922151948864](C:\Users\zhuxiaoyue\AppData\Roaming\Typora\typora-user-images\image-20210922151948864.png)

![image-20210922152044787](C:\Users\zhuxiaoyue\AppData\Roaming\Typora\typora-user-images\image-20210922152044787.png)

![image-20210922152135161](C:\Users\zhuxiaoyue\AppData\Roaming\Typora\typora-user-images\image-20210922152135161.png)

![image-20210922152153204](C:\Users\zhuxiaoyue\AppData\Roaming\Typora\typora-user-images\image-20210922152153204.png)

![image-20210922152225952](C:\Users\zhuxiaoyue\AppData\Roaming\Typora\typora-user-images\image-20210922152225952.png)



```java
let isChrome = navigator.userAgent.indexOf("Chrome") > -1 && navigator.userAgent.indexOf("Safari") > -1;
      if (!isChrome) {
        console.log("test chrome", document.getElementById("notChrome"));
        return "<h1>请前往Chrome打开页面</h1>";
      }
```

