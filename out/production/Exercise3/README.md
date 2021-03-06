# JavaExperiment
## Exercise3用Javafx 实现国际象棋游戏

#### 基本规则

- 棋子马设计“日”的移动方式
- 兵设计只能向前直走，每次只能走一格。但走第一步时，可以走一格或两格的移动方式
- 请为后设计横、直、斜都可以走，步数不受限制，但不能越子的移动方式。
- 车只能横向或者竖向行走
- 国王是在以自己为中心的九宫格内行走
- 骑士只能走对角线

#### 项目目录结构


![项目结构图](https://github.com/441712875al/InternationalChess-Game/blob/master/imgTmp/%E6%89%B9%E6%B3%A8%202019-06-23%20181631.png)

#### UML类图关系

> 以骑士为例

![UML图](https://github.com/441712875al/InternationalChess-Game/blob/master/imgTmp/%E6%89%B9%E6%B3%A8%202019-06-23%20181729.png)

#### 实现基本功能

- 吃子
- 不能越子
- 游戏结束提示
- 基本移动策略
- 背景音乐
- 悔棋
