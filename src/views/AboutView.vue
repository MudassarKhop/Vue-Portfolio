<template>
	<section id="about">
		<div id="glass-object">
			<h2 class="heading">~ past, present ~</h2>
			<h1 class="heading-">ABOUT ME</h1>
		</div>
	</section>
</template>
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
	#about {
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
		margin: 0;
		padding: 0;
		height: 100vh;
		overflow: hidden;
		display: flex;
		align-items: center;
		justify-content: center;
	}
	#glass-object {
		padding: 30px;
		backdrop-filter: blur(12px);
		box-shadow: 0 2px 10px rgb(0 0 0 / 10%), 0 10px 15px rgb(0 0 0 / 20%);
		box-sizing: border-box;
		background-image: linear-gradient(
			45deg,
			rgba(255, 255, 255, 0.2),
			rgba(255, 255, 255, 0.2)
		);
		width: 90%;
		min-height: 90%;
		mix-blend-mode: hard-light;
	}
	.heading {
		display: flex;
		flex-direction: row;
		flex-wrap: nowrap;
		justify-content: start;
		align-items: flex-start;
		padding-bottom: 0%;
	}
	.heading- {
		padding-top: 0%;
		display: flex;
		flex-direction: row;
		flex-wrap: nowrap;
		justify-content: start;
		align-items: flex-start;
		text-shadow: 3px 3px black;
		font-family: "Cormorant SC", serif;
	}
</style>
