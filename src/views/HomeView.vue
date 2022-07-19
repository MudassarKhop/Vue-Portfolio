<template>
	<body>
		<section id="landing">
			<div class="content">
				<div class="top-left"></div>
				<div class="left-bot"></div>
				<div class="bot-right"></div>
				<div class="right-top"></div>
			</div>
			<div id="heading">Mudassar Khopatkar</div>
			<div id="heading2">
				<i>~ friendly neighborhood aspiring web-developer ~</i>
			</div>

			<div id="icons">
				<a href="https://www.instagram.com/mudathierkop/" target="blank"
					><i class="fa-brands fa-instagram"></i
				></a>
				<a href="https://github.com/MudassarKhop" target="blank"
					><i class="fa-brands fa-github"></i
				></a>
				<a href="" target="blank"><i class="fa-brands fa-twitter"></i></a>
				<a
					href="https://www.linkedin.com/in/mudassar-khopatkar-a9854023a/"
					target="blank"
					><i class="fa-brands fa-linkedin"></i
				></a>
			</div>
		</section>
	</body>
</template>

<script>
	// @ is an alias to /src
	import HelloWorld from "@/components/HelloWorld.vue";

	export default {
		name: "HomeView",
		components: {
			HelloWorld,
		},
	};
</script>
<style scoped>
	body {
		margin: 0;
		padding: 0;
		height: 100vh;
		overflow: hidden;
		display: flex;
		align-items: center;
		justify-content: center;
		background: hsla(234, 84%, 15%, 1);

		background: radial-gradient(
			circle,
			hsla(234, 84%, 15%, 1) 9%,
			hsla(271, 96%, 9%, 1) 58%,
			hsla(259, 100%, 8%, 1) 100%
		);

		background: -moz-radial-gradient(
			circle,
			hsla(234, 84%, 15%, 1) 9%,
			hsla(271, 96%, 9%, 1) 58%,
			hsla(259, 100%, 8%, 1) 100%
		);

		background: -webkit-radial-gradient(
			circle,
			hsla(234, 84%, 15%, 1) 9%,
			hsla(271, 96%, 9%, 1) 58%,
			hsla(259, 100%, 8%, 1) 100%
		);

		filter: progid: DXImageTransform.Microsoft.gradient( startColorstr="#060C47", endColorstr="#18012D", GradientType=1 );
	}
	/* radial background */
	.content {
		margin-top: 20%;
		display: flex;
		flex-direction: row;
		flex-wrap: nowrap;
		justify-content: center;
		align-items: center;
		width: 80vmin;
		height: 80vmin;
		position: relative;
		animation: spin 10s linear 0s infinite;
	}

	@keyframes spin {
		100% {
			transform: rotate(360deg);
		}
	}

	.content > div {
		--line: #67b3e4;
		position: absolute;
		width: 70%;
		height: 70%;
		border-radius: 100%;
		box-sizing: border-box;
		box-shadow: -3vmin 3vmin 3vmin 0 #161616 inset,
			1vmin -1vmin 0.125vmin -1.25vmin var(--line);
		background: radial-gradient(
				circle at 36% 64%,
				#fff0 0 calc(53.5% - 1px),
				var(--line) 53.5% 54%,
				#fff0 calc(54% + 1px) 100%
			),
			radial-gradient(
				circle at 38% 62%,
				#fff0 0 calc(54.5% - 1px),
				var(--line) 54.5% 55%,
				#fff0 calc(55% + 1px) 100%
			),
			radial-gradient(
				circle at 42% 58%,
				#fff0 0 calc(57.75% - 1px),
				var(--line) 57.75% 58%,
				#fff0 calc(58% + 1px) 100%
			),
			radial-gradient(
				circle at 40% 60%,
				#fff0 0 calc(56.75% - 1px),
				var(--line) 56.75% 57%,
				#fff0 calc(57% + 1px) 100%
			),
			radial-gradient(
				circle at 45% 55%,
				#fff0 0 calc(61.75% - 1px),
				var(--line) 61.75% 62%,
				#fff0 calc(62% + 1px) 100%
			),
			radial-gradient(
				circle at 43.5% 56.5%,
				#fff0 0 calc(59.75% - 1px),
				var(--line) 59.75% 60%,
				#fff0 calc(60% + 1px) 100%
			),
			radial-gradient(
				circle at 45% 55%,
				#fff0 0 calc(64.5% - 1px),
				var(--line) 64.5% 64.75%,
				#fff0 calc(64.75% + 1px) 100%
			),
			radial-gradient(
				circle at 46.5% 53.5%,
				#fff0 0 calc(65.5% - 1px),
				var(--line) 65.5% 65.75%,
				#fff0 calc(65.75% + 1px) 100%
			),
			radial-gradient(
				circle at 48.5% 51.5%,
				#fff0 0 calc(67.75% - 1px),
				var(--line) 67.75% 68.25%,
				#fff0 calc(68.25% + 1px) 100%
			),
			radial-gradient(
				circle at 49% 51%,
				#fff0 0 calc(69.5% - 1px),
				var(--line) 69.5% 70%,
				#fff0 calc(70% + 1px) 100%
			);
	}

	.top-left {
		left: 11vmin;
		top: 2vmin;
	}

	.left-bot {
		bottom: 11vmin;
		left: 2vmin;
		transform: rotate(-90deg);
	}

	.bot-right {
		right: 11vmin;
		bottom: 2vmin;
		transform: rotate(-180deg);
	}

	.right-top {
		right: 2vmin;
		top: 11vmin;
		transform: rotate(-270deg);
	}
	/* radial background */
	#heading {
		font-size: 70px;
		position: relative;
		top: -350px;
		left: -20px;
		font-family: "Cormorant SC", serif;
		text-shadow: 5px 5px black;
	}

	#heading2 {
		font-size: 25px;
		position: relative;
		top: -345px;
		left: -20px;
		text-shadow: 3px 3px black;
	}
	/* icons */
	#icons {
		position: relative;
		left: 630px;
		top: -710px;
	}

	.fa-brands {
		padding-right: 10px;
	}

	.fa-instagram {
		font-size: 28px;
		display: inline-block;
		background: #212431;
		color: #fff;
		line-height: 1;
		padding: 8px 0;
		margin-right: 4px;
		border-radius: 50%;
		text-align: center;
		width: 45px;
		transition: 0.3s;
	}
	.fa-github {
		font-size: 28px;
		display: inline-block;
		background: #212431;
		color: #fff;
		line-height: 1;
		padding: 8px 0;
		margin-right: 4px;
		border-radius: 50%;
		text-align: center;
		width: 45px;
		transition: 0.3s;
	}
	.fa-twitter {
		font-size: 28px;
		display: inline-block;
		background: #212431;
		color: #fff;
		line-height: 1;
		padding: 8px 0;
		margin-right: 4px;
		border-radius: 50%;
		text-align: center;
		width: 45px;
		transition: 0.3s;
	}
	.fa-linkedin {
		font-size: 28px;
		display: inline-block;
		background: #212431;
		color: #fff;
		line-height: 1;
		padding: 8px 0;
		margin-right: 4px;
		border-radius: 50%;
		text-align: center;
		width: 45px;
		transition: 0.3s;
	}
	.fa-instagram:hover {
		background: radial-gradient(
			circle at 33% 100%,
			#fed373 4%,
			#f15245 30%,
			#d92e7f 62%,
			#9b36b7 85%,
			#515ecf
		);
	}
	.fa-twitter:hover {
		background-color: #1da1f2;
	}
	.fa-linkedin:hover {
		background: white;
		color: #0077b5;
	}
	.fa-github:hover {
		background: white;
		color: #212431;
	}

	.fa-github:hover {
		background-color: linear-gradient(
			#405de6 #5851db #833ab4 #c13584 #e1306c #fd1d1d
		);
	}
	/* icons*/
</style>
