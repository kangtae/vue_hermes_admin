<template>
	<header>
		<div class="site-header">
			<nav class="navbar navbar-inverse navbar-fixed-top">
				<div class="container-fluid">
					<div class="navbar-header">
						<button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1">
							<span class="sr-only">Toggle navigation</span>
							<span class="icon-bar"></span>
							<span class="icon-bar"></span>
							<span class="icon-bar"></span>
						</button>
						<a class="navbar-brand" href="#">루이까또즈</a>
					</div>
					<div class="collapse navbar-collapse">
						<ul class="nav navbar-nav" role="navigation">
							<li role="presentation" class="dropdown">
								<a v-on:click="menuToggle" class="dropdown-toggle" role="button">계정관리11 <span class="caret"></span></a>
								<ul v-show="menuElem" class="dropdown-menu">
									<li><a href="../account/계정관리_01비밀번호변경.html" class="">비밀번호 변경</a></li>
								</ul>
							</li>
							<li role="presentation" class="dropdown">
								<a v-on:click="menuToggle" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-expanded="false">상품관리 <span class="caret"></span></a>
								<ul v-show="menuElem" class="dropdown-menu" role="menu">
									<li><a href="../product/상품관리_01목록.html" class="">목록</a></li>
									<li><a href="../product/상품관리_02상세.html" class="">상세</a></li>
									<li><a href="../product/상품관리_03등록.html" class="">등록</a></li>
									<li><a href="../product/상품관리_04수정.html" class="">수정</a></li>
								</ul>
							</li>
							<li role="presentation">
								<a href="../notice/공지사항_01목록.html">공지사항</a>
							</li>
							<li role="presentation">
								<a href="../news/언론보도_01목록.html">언론보도</a>
							</li>
							<li role="presentation">
								<a href="../reference/자료실_01목록.html">자료실</a>
							</li>
							<li role="presentation">
								<a href="../announce/전자공고_01목록.html">전자공고</a>
							</li>
							<li role="presentation">
								<a href="../recruit/채용공고_01목록.html">채용공고</a>
							</li>
							<li role="presentation">
								<a href="../build/건설_01목록.html">건설</a>
							</li>
						</ul>
						<p class="navbar-text navbar-right">
							안녕하세요. 홍길동님 <button type="submit" class="btn  btn-default btn-xs"><i class="fa fa-sign-out" aria-hidden="true"></i> 로그아웃</button>
						</p>
					</div>
					<!-- //collapse -->
				</div>
				<!-- //container-fluid -->
			</nav>
		</div>
	</header>
</template>

<script>
export default {
	data: function() {
		return {
			menuElem: false,
		};
	},
	methods: {
		menuToggle() {
			console.log(this);
			this.menuElem = !this.menuElem;
		},
	},
};
</script>
