<script>
</script>

<!-- <em class="ttl-main">
			에이치에스미래
			IT
			다이빙
			모바일
			미래
			기술
			열정
			홈페이지
			자바
			nodejs
			바다사랑
			바다환경운동
		</em> -->


<div class="container">
	<div class="page-title">
		<div class="card home-main-title"></div>
		<div class="home-main-explain">
			<div class="ttl-explain">
				사람을 위한 가치 창출, 자연의 소중함을 위해 공헌합니다.
			</div>
			<div class="ttl-explain">
				디지털과 아날로그를 통합하며, 더 살기 좋은 미래를 만들어 나가겠습니다.
			</div>
		</div>
	</div>
</div>

<div class="container">
	<div class="company-word-text">
		<div class="card">
			<div class="row">
				<div class="col-md-3">
					<div class="card-body card-body-custom yellow-bg card-img-left"></div>
				</div>
				<div class="col-md-9">
					<div class="card-body card-body-custom">
						<h4 class="card-title">열정</h4>
						<div class="card-text">우리는 우리가 해야 할 일들을 끊임없이 찾고, 그러한 일들을 꾸준히 해 나갑니다.</div>
						<div class="card-text">해야 할 일들의 작은 것 하나에도 우리의 열정과 노력으로 담아 해결하고 있습니다.</div>
					</div>
				</div>
			</div>
		</div>

		<div class="card card-custom">
			<div class="row">
				<div class="col-md-9">
					<div class="col card-body card-body-custom">
						<h5 class="card-title">미래</h5>
						<div class="card-text">우리가, 우리의 자녀들이 앞으로 살아가야 할 미래의 사회와 문화를 만들어 가고자 합니다.</div>
						<div class="card-text">좋은 것들은 더 좋게 발전 시키고, 해로운 것은 해롭지 않은 방향으로 변경 해 나갑니다.</div>
						<div class="card-text">언제나 좋은 미래가 올 것입니다.</div>
					</div>
				</div>

				<div class="col-md-3">
					<div class="card-body card-body-custom blue-bg card-img-right">
					</div>
				</div>
			</div>
		</div>


		<div class="card card-custom">
			<div class="row">
				<div class="col-md-3">
					<div class="card-body card-body-custom red-bg card-img-left">
					</div>
				</div>

				<div class="col-md-9">
					<div class="col card-body card-body-custom">
						<h5 class="card-title">기술</h5>
						<div class="card-text">아름다운 기술들의 모습과 조화를 꿈꿉니다.</div>
						<div class="card-text">사람과 사람을 연결하는 기술, 자연을 보호하는 기술.</div>
						<div class="card-text">우리가 추구하는 기술은 아름답고 사람과 자연을 아우르고 미래를 지향합니다.</div>
					</div>
				</div>
			</div>
		</div>

	</div>
</div>


<style lang="scss">
	$static_img: '/static/images/';

	@mixin get_main_card_bg ($color, $filename) {
		$background: white !default;
		
		@if $color != '' {
			$background: $color;
		};
		@if $filename != '' {
			$background: url('#{$static_img}/#{$filename}') center center/cover no-repeat local $background;
		}
		
		background: $background;
	}
	
	.company-word-text {
		margin-top: 96px;
		
		.card {
			&.card-custom {
				margin-top: 48px;
			}
		}

		.row {
			margin-top: 0;
			margin-right: 0;
			margin-left: 0;

			.col-md-3 {
				padding: 0;
			}
			.col-md-9 {
				padding: 0;
			}
		}

		.card-body-custom {
			padding: 48px;
			height: 100%;
		}

		.card-img-left {
			border-top-left-radius: var(--bs-card-inner-border-radius);
			border-bottom-left-radius: var(--bs-card-inner-border-radius);
		}

		.card-img-right {
			border-top-right-radius: var(--bs-card-inner-border-radius);
			border-bottom-right-radius: var(--bs-card-inner-border-radius);
		}

		.yellow-bg {
			@include get_main_card_bg(#ffdd00, 'cubes-g4e29be0ef_1280.jpg');
		}
		.blue-bg {
			@include get_main_card_bg(#0055ff, 'future-2372183_1280.jpg');
		}
		.red-bg {
			@include get_main_card_bg(#ff4400, 'lightbulb-1875247_1280.jpg');
		}
	}



	.page-title {
		margin-top: 48px;
		height: 400px;
		position: relative;
		text-align: center;

		.home-main-title {
			@include get_main_card_bg(rgb(255, 255, 255, .5), 'desk-3076954_1920.jpg');
			border: 0;
			opacity: .5;
			height: 100%;

			.main_content { border-radius: var(--bs-card-inner-border-radius); }
		}

		.home-main-explain {
			position: absolute;
			top: 50%;
			left: 50%;
			width: 100%;
			
			-webkit-transform: translate(-50%,-50%);
			transform: translate(-50%,-50%);
		}
		
		.ttl-explain {
			font-size: 1.2rem;
			font-weight: 400;
			margin-top: 5px;
			padding: 0 36px;
		}
	}

	@media screen and (max-width: 770px)
	{
		.page-title {
			.home-main-title {
				background: white;
				height: 250px;

				.main_content { display: none; }
			}
		
			.ttl-explain { font-weight: 350; }
		}
	}
</style>
