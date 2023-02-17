<script lang="ts">
	// import wishty from '$lib/assets/wishty.svg';
</script>

<h2 class="headline">Curriculum Vitae</h2>
<main class="timeline">
	<!-- Wishty  -->
	<div class="timeline__time">
		<h3>2023/01 - Today</h3>
	</div>
	<div class="circle"><div /></div>
	<div class="timeline__position">
		<h4><a href="https://www.wishty.de/">Solo Founder of Wishty</a></h4>
	</div>
	<div />
	<div class="line"><div /></div>
	<div>
		<p class="timeline__description">
			Wishty is a digital wishlist for content creators. They can receive payments from their
			audience to fulfill their wishes. A new way of connection and support of your favourite
			content creator.
		</p>
		<div class="timeline__technologies">
			<h4>Technologies</h4>
			<ul>
				<li class="timeline__technologies--red">SvelteKit</li>
				<li class="timeline__technologies--blue">TypeScript</li>
				<li class="timeline__technologies--yellow">JavaScript</li>
				<li class="timeline__technologies--pink">SCSS</li>
				<li class="timeline__technologies--green">Supabase</li>
				<li class="timeline__technologies--purple">Stripe</li>
				<li class="timeline__technologies--black">Vercel</li>
			</ul>
		</div>
	</div>
	<div />
	<div class="line">
		<div />
	</div>
	<div />

	<!-- Transfermarkt  -->
	<div class="timeline__time">
		<h3>2020/06 - Today</h3>
	</div>
	<div class="circle"><div /></div>
	<div class="timeline__position">
		<h4><a href="https://www.transfermarkt.de/">Frontend Developer at Transfermarkt</a></h4>
	</div>
	<div />
	<div class="line"><div /></div>
	<div>
		<p class="timeline__description">
			Transfermarkt is a football platform with the most comprehensive football data on the
			Internet. The platform is used by millions of football fans every day. I am working mostly on
			the refactoring of the website or development of new features.
		</p>
		<div class="timeline__technologies">
			<h4>Technologies</h4>
			<ul>
				<li class="timeline__technologies--blue">TypeScript</li>
				<li class="timeline__technologies--yellow">JavaScript</li>
				<li class="timeline__technologies--red">Svelte</li>
				<li class="timeline__technologies--black">StencilJS</li>
				<li class="timeline__technologies--pink">SCSS</li>
				<li class="timeline__technologies--purple">PHP</li>
			</ul>
		</div>
	</div>
	<div />
	<div class="line">
		<div />
	</div>
	<div />

	<!-- Neuefische  -->
	<div class="timeline__time">
		<h3>2020/01 - 2020/03</h3>
	</div>
	<div class="circle"><div /></div>
	<div class="timeline__position">
		<h4><a href="https://www.neuefische.de/en">Trainee Web Development</a></h4>
	</div>
	<div />
	<div class="line"><div /></div>
	<div>
		<p class="timeline__description">
			Full time Intensive-Coding-Bootcamp. 540 hours programming practice with development of a
			mobile app as digital journeyman’s piece.
		</p>
		<div class="timeline__technologies">
			<h4>Technologies</h4>
			<ul>
				<li class="timeline__technologies--blue">React</li>
				<li class="timeline__technologies--yellow">JavaScript</li>
				<li class="timeline__technologies--orange">HTML</li>
				<li class="timeline__technologies--blue">CSS</li>
				<li class="timeline__technologies--pink">SCSS</li>
				<li class="timeline__technologies--purple">Bootstrap</li>
				<li class="timeline__technologies--pink">Storybook</li>
				<li class="timeline__technologies--black">Cypress</li>
			</ul>
		</div>
	</div>
	<div />
	<div class="line">
		<div />
	</div>
	<div />

	<!-- Push your sales  -->
	<div class="timeline__time">
		<h3>2018/10 - 2019/12</h3>
	</div>
	<div class="circle"><div /></div>
	<div class="timeline__position">
		<h4>Co-Founder of Push your sales</h4>
	</div>
	<div />
	<div class="line"><div /></div>
	<div>
		<p class="timeline__description">
			Push your sales is a digital marketing agency. Specialized on successful selling on the Amazon
			marketplace. Optimization of product pages and marketing campaign management.
		</p>
	</div>
	<div />
	<div class="line">
		<div />
	</div>
	<div />

	<!-- MAVE ATHLETIC  -->
	<div class="timeline__time">
		<h3>2014/09 - 2019/12</h3>
	</div>
	<div class="circle"><div /></div>
	<div class="timeline__position">
		<h4>
			<a
				href="https://www.amazon.de/stores/MAVE+ATHLETIC/page/B9BD7758-6DA6-4F33-A555-03F40D129AD2?ref_=ast_bln"
				>Founder of Mave Athletic</a
			>
		</h4>
	</div>
	<div />
	<!-- <div class="line"><div /></div> -->
	<div />
	<div>
		<p class="timeline__description">
			Mave Athletic is a fitness e-commerce brand. Field of action from product development,
			purchasing, logistics to online marketing, specially on the Amazon marketplace.
		</p>
	</div>
</main>

<style lang="scss">
	.headline {
		width: 100%;
		text-align: center;
		font-size: 25px;
	}

	.timeline {
		padding: 60px 20px;
		display: grid;
		grid-template-columns: 2fr 1fr 4fr;
		column-gap: 10px;

		@media only screen and (min-width: 600px) {
			padding: 60px;
		}

		&__time {
			display: flex;
			justify-content: flex-end;
			align-items: center;

			h3 {
				font-size: 18px;
			}
		}

		&__position {
			display: flex;
			align-items: center;

			h4 {
				font-size: 18px;

				a {
					color: inherit;
					text-decoration: none;

					&:hover {
						text-decoration: underline;
					}
				}
			}
		}

		&__description {
			font-size: 18px;
			margin-top: 8px;
		}

		&__technologies {
			h4 {
				font-size: 12px;
				margin: 12px 0 6px;
			}
			ul {
				list-style: none;
				padding: 0;
				margin: 0;
				display: flex;
				flex-wrap: wrap;
				gap: 8px;
			}
			li {
				padding: 3px 6px;
				border-radius: 4px;
				font-size: 11px;
				box-sizing: border-box;

				&:hover {
					cursor: pointer;
					border: 1px dotted black;
					color: black;
				}
			}

			&--red {
				border: 1px solid #ff3e00;
				color: #ff3e00;
			}

			&--blue {
				border: 1px solid #3178c6;
				color: #3178c6;
			}
			&--pink {
				border: 1px solid #bf4080;
				color: #bf4080;
			}
			&--green {
				border: 1px solid #3fcf8e;
				color: #3fcf8e;
			}
			&--purple {
				border: 1px solid #625afa;
				color: #625afa;
			}
			&--black {
				border: 1px solid #000;
				color: #000;
			}
			&--yellow {
				border: 1px solid #d3ba12;
				color: #d3ba12;
			}
			&--orange {
				border: 1px solid #ff7f00;
				color: #ff7f00;
			}
		}
	}

	.line {
		display: flex;
		justify-content: center;

		div {
			border-left: 1px solid #ccc;
			min-height: 50px;
		}
	}

	.circle {
		display: flex;
		justify-content: center;

		div {
			// width: 100%;
			height: 100%;
			border-radius: 50%;
			border: 1px solid #ccc;
			aspect-ratio: 1/1;
			box-sizing: border-box;
		}
	}
</style>
