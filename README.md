## Html5Video说明
基于html5实现的视频播放器，提供PSD源文件，部分功能未完善，2012年作品，已停止维护

##截图

![html5video](https://github.com/Beau-zihan/Html5Video/blob/master/html5video-preview.png)
## 示例
http://www.zi-han.net/developer/717.html

## 配置
<pre>$(function(){
	/**--精简示例--**/
	$(".video_container").html5video({src:"http://cdn.zi-han.net/file/HTML5%E6%A6%82%E8%BF%B0.mp4"});
	/**--完整示例--**/
	$(".video_container").html5video({
		width:600,               //Number型，播放器宽度。
		height:338,              //Number型，播放器高度。
		src:"http://cdn.zi-han.net/file/HTML5%E6%A6%82%E8%BF%B0.mp4",//String型，必填项！要播放的视频的 URL。
		poster:"http://cdn.zi-han.net/file/video_poster.png",//String型，在视频播放之前所显示的图片的 URL。
		loop:false,              //Boolean型，则当媒介文件完成播放后再次开始播放。
		preload:true,            //Boolean型，如果出现该属性，则视频在页面加载时进行加载，并预备播放。
		notsuportmsg:"您的浏览器不支持html5，无法使用该插件！" //String型，浏览器不支持video标签时的提示，可使用html标签。
	});
});</pre>
