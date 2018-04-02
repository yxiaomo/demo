使用原生js开发的移动端会议时间选择控件

兼容性

由于使用了html5+css3，所以该插件仅适用于移动端和IE10及其以上版本的主流浏览器

OPTIONS

dateStart : new Date(),//插件开始时间
dateNum : 14,//插件开始时间开始显示天数
timeStart : 8,//插件可供选择的小时（开始）
timeNum : 10,//插件可供选择的小时后多少小时可供选择	
filter:function(startTime,endTime){//选中时间，点击确定判断事件
	判断时间选中间隔是否合符要求，如果不合符返回false,合符返回true,
},
onOk:function(){//选中时间，点击确定回调事件
	alert('时间选择成功');
},
onCancel:function(){//点击取消回调事件
	alert('取消');
}