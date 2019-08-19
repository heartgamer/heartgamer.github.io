<!DOCTYPE html>
<html>
<meta charset="utf-8">
<head>
	<script type="text/javascript">
	var UV = new function() {
		this.link_prefix=`uniwebview`; // deeplink namespace.
		
		// platform list: guest, google, gamecenter, facebook
		this.login = function(platform="guest") {
			window.location.href = `${this.link_prefix}://login?p=${platform}`; 
		};

		// 현재 로그인되어 있는 Firebase 계정을 sign out 시킴.
		this.signout = function() {
			window.location.href = `${this.link_prefix}://signout`;
		};

		// webview를 초기화, target_url을 파라미터로 전달하는 경우 해당 url로 이동시켜줌.
		this.reload = function(target_url='') {
			window.location.href = `${this.link_prefix}://reload?target_url=${target_url}`;
		};

		// 사용자 정보를 요청함. 유니티에서 callback 함수를 호출하면서 정보를 전달함.
		this.request_userinfo = function(callback='UV.userinfo') {
			window.location.href = `${this.link_prefix}://request_userinfo?callback=${callback}`;
		};

		// 유니티에서 사용자 정보를 호출하는 기본 정보.
		this.userinfo = function(user) {
			var user_str = JSON.stringify(user); 
			alert('사용자 정보 도착: ' + user_str);
			console.log(user_str);
		};

		// 유니티에서 디버깅용 메시지를 전달하는 경우, 유니티에서 이 함수를 호출하여 메시지 전달.
		this.message = function(msg, with_alert=false) {
			if(with_alert) alert(msg);
			console.log(msg);
		};
	}

	// callback 함수를 지정하여 다른 액션을 하고자 하는 경우는 아래와 같이 prototype을 사용하여 함수를 선언.
	// 
	UV.prototype.get_userinfo = function(user) {
		console.log(user);
	};
	</script>
</head>
<body>

<h1>UniWebView test</h1>
<p>
	<!-- <img src="./img/sample_cute_img.jpg" /> -->
</p>

<p>
	<input type="text" id="url" size=50>
	<button onclick="UV.reload(document.getElementById('url').value)">해당 URL로 이동</button>
</p>
<p><button onclick="UV.message('msg from unity. test.')">함수 테스트</button></p>
<p><button onclick="UV.message('msg from unity. test.', 1)">함수 테스트</button></p>
<p><button onclick="UV.login('guest')">게스트로 로그인하기</button></p>
<p><button onclick="UV.login('google')">구글아이디로 로그인</button></p>
<p><button onclick="UV.login('facebook')">페이스북 로그인</button></p>
<p><button onclick="UV.login('gamecenter')">게임센터 로그인</button></p>
<p><button onclick="UV.signout()">로그아웃</button></p>
<p><button onclick="UV.reload()">리로드</button></p>
<p><button onclick="UV.request_userinfo()">사용자 정보 요청</button></p>
</body>
</html>
