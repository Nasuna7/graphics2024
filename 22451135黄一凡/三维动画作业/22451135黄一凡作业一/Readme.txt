使用说明
直线
	数值微分、中点画线、Bresenham都是画直线，鼠标左键按下后拖拽一定距离松开，会绘制从按下的点到松开的点的直线
圆形
	中点画圆、Bresenham也都是画圆，操作与直线相同，只是按下的位置为圆的中心点，松开点到按下点的距离为半径
多边形填充
	种子填充
		采用种子填充算法
			递归和栈都是为了演示用的，选择后点击所画的框的内部，会以点击的位置为种子进行填充
	多边形填充
		多边形填充也是演示，画出了填充后的样子，并进行了描边
姓名艺术字
	设计的姓名艺术字
八卦
	画的八卦
小黄人
	采用扫描线算法绘制小黄人
小猫
	采用种子填充绘制小猫
小狐狸
	采用种子填充绘制小狐狸
多边形绘制
	五边形
		绘制一个五边形，用户点击顶点后可移动顶点进行交互
	六边形
		绘制一个六边形，用户点击顶点后可移动顶点进行交互
二维几何变换
	平移变化
		点击后可以平移图形
	旋转变化
		点击后向左移和向右移会向不同的方向旋转
	缩放变化
		鼠标左击后往不同方向移控制图形在X方向缩放，鼠标右击后往不同方向移控制图形在Y方向缩放
	对称图案设计
		一个简单的对称图案绘制
裁剪
	直线段裁剪
		点击鼠标后松开，根据点击和松开的位置绘制矩形窗口进行裁剪
	圆形裁剪
		点击鼠标后松开，根据点击和松开的位置绘制圆形窗口进行裁剪（取巧了）
三维图形
	长方形
		绘制一个长方形
	平移
		点击后可以平移长方形
	缩放
		按住x或者y或者z后拖拽鼠标可以进行缩放
	旋转
		按住x或者y后拖拽鼠标可以进行不同方向的旋转
	三视图
		绘制一个三维图形并绘制出三视图
曲线
	Bezier曲线
		绘制根据用户输入得到的点，点击控制点并拖拽可以实时绘制Bezier曲线
	B样条曲线
		绘制用户输入的点的个数，利用3次B样条曲线进行实施绘制
	Bezier曲线动态绘制
		利用德卡斯特里奥算法实现的动态绘制Bezier曲线
	B样条曲线动态绘制
		利用德布尔算法实现的动态绘制B样条曲线
曲面
	Bezier曲面
		根据前面的Bezier曲线绘制的曲面，可以拖拽控制点实施绘制曲面
	B样条曲面
		根据前面的B样条曲线绘制的曲面，可以拖拽控制点实施绘制曲面