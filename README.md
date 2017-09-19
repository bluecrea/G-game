# G-game
##### Google Dinosaur Game
Chrome 浏览器断网情况下恐龙翻越障碍物游戏研究

### 五个构造函数：
  #### 1、游戏逻辑管理函数 Runner
  #### 2、背景管理函数 Horizon
      地面 HorizonLine
      云朵 cloud
      昼夜交替 NightMode
      障碍物 Obstacle
  #### 3、恐龙函数 Trex
  #### 4、分数记录函数 DistanceMeter
  #### 5、游戏结束操作面板函数 GameOverPanel
  ##### 2017年09月15日
  ###### 背景管理函数 Horizon
    1.HorizonLine 函数
    2.Cloud 函数
    3.NightMode 函数
  
  ###### 障碍物 Obstacle
    增加🌵、翼龙
    
  ##### 2017年09月17日
  ###### T-rex game character.霸王龙游戏角色
    游戏开始前，霸王龙眨眼睛
    使用计时器timer实现突破切换效果，并且需要知道两张图片切换的时间间隔msPerFrame
    当计时器timer的时间大于切换的时间间隔msPerFrame时，将图片切换到下一张，到达最后一张时又从第一张开始，如此反复
    
  ##### 2017年09月18日
  ###### 碰撞盒子
  ###### 计分面板