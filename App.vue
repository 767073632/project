<script>
	export default {
		onLaunch: function() {
			// 加载公共图标库
			const domModule = weex.requireModule('dom')
			domModule.addRule('fontFace', {
			    'fontFamily': "iconfont",
			    'src': "url('https://at.alicdn.com/t/font_1365296_2ijcbdrmsg.ttf')"
			});
		},
		onShow: function() {
			console.log('App Show')
		},
		onHide: function() {
			console.log('App Hide')
		}
	}
</script>

<style>
	/*每个页面公共css */
	@import "./common/free.css";
	@import "./common/common.css";
	@import "./common/free-icon.css";
</style>
