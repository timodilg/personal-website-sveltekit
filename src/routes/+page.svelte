<script lang="ts">
	import Timeline from '$lib/components/Timeline.svelte';
	import timo from '$lib/assets/timo.png';
	import mail from '$lib/assets/mail.png';
	import linkedin from '$lib/assets/linkedin.png';
	import github from '$lib/assets/github.png';
	import xing from '$lib/assets/xing.svg';
</script>

<main>
	<div class="wrapper">
		<div class="left">
			<div class="profile">
				<img src={timo} alt="Timo" />
				<p class="profile__name">Timo Dilg</p>
				<p class="profile__title">Frontend Developer</p>
				<div class="links">
					<a href="https://github.com/timodilg">
						<img src={github} alt="Github" />
					</a>
					<a href="https://www.linkedin.com/in/timo-dilg/">
						<img src={linkedin} alt="linkedin" />
					</a>
					<a href="https://www.xing.com/profile/Timo_Dilg/cv">
						<img src={xing} alt="xing" />
					</a>
					<a href="mailto:timodilg@gmail.com">
						<img src={mail} alt="mail" />
					</a>
				</div>
			</div>
		</div>
		<div class="right">
			<span>👋</span>
			<h1>Hi, I'm Timo</h1>
			<p>Frontend Developer living in Hamburg, Germany</p>
		</div>
	</div>
</main>
<Timeline />

<style lang="scss">
	main {
		height: 100vh;
		display: flex;
		align-items: center;
		justify-content: center;
		padding: 0 30px;
	}

	.wrapper {
		display: flex;
		flex-direction: column-reverse;
		width: 100%;
		justify-content: space-evenly;
		height: 100vh;

		@media only screen and (min-width: 600px) {
			flex-direction: row;
			align-items: center;
		}
	}

	.left {
		display: flex;
		justify-content: center;
	}

	.right {
		display: flex;
		flex-direction: column;
		justify-content: center;
		text-align: center;

		span {
			font-size: 55px;
			animation-name: wink;
			animation-duration: 1s;
			animation-iteration-count: 3;
		}

		@keyframes wink {
			0% {
				transform: rotate3d(0, 0, 1, 0deg);
			}
			50% {
				transform: rotate3d(0, 0, 1, 20deg);
			}
			100% {
				transform: rotate3d(0, 0, 1, 0deg);
			}
		}

		h1 {
			font-size: 42px;

			@media only screen and (min-width: 600px) {
				font-size: 55px;
			}
		}

		p {
			margin-top: 12px;
		}
	}

	.profile {
		display: flex;
		flex-direction: column;
		align-items: center;
		max-width: 160px;

		&__name {
			font-family: 'PT Serif Caption', serif;
			font-size: 25px;
			font-weight: 500;
			margin-top: 6px;
		}

		&__title {
			font-size: 18px;
			margin-top: 4px;
		}

		img {
			height: 150px;
		}
	}

	.links {
		display: flex;
		justify-content: space-between;
		align-items: center;
		margin-top: 12px;

		a {
			margin: 0 5px;
		}

		img {
			height: 26px;
		}
	}
</style>
