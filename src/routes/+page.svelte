<svelte:head>
	<title>Sotheavatey Thao | Data Analyst Portfolio</title>
	<meta
		name="description"
		content="Sotheavatey Thao's professional data analyst portfolio featuring SQL, Power BI, Python, and analytics projects."
	/>
</svelte:head>

<div class="page-shell">
	<div class="grid-background"></div>
	<div class="glow glow-one"></div>
	<div class="glow glow-two"></div>

	<header class="site-header">
		<a class="brand" href="/" aria-label="Sotheavatey Thao home">
			<div class="brand-name">Sotheavatey Thao</div>
		</a>

		<nav class="nav-links">
			<a href="#home">Home</a>
			<a href="#about">About</a>
			<a href="#projects">Projects</a>
			<a href="#skills">Skills</a>
			<a href="#resume">Resume</a>
			<a href="#contact">Contact</a>
		</nav>
	</header>

	<main id="home" class="hero">
		<div class="hero-content">
			<p class="intro">HI, I'M SOTHEAVATEY THAO</p>

			<h1>Data Analyst</h1>

			<p class="hero-description">
				I transform raw data into meaningful insights that help businesses
				make better decisions.
			</p>

			<div class="hero-skills">
				<span>SQL</span>
				<span>Power BI</span>
				<span>Python</span>
			</div>

			<div class="hero-buttons">
				<a href="#projects" class="primary-btn">View My Projects</a>
				<a href="#resume" class="secondary-btn">Download Resume</a>
			</div>
		</div>

		<div class="hero-visual">
			<div class="dashboard-placeholder">
				<p>Power BI Dashboard</p>
				<span>Your dashboard screenshot will go here</span>
			</div>
		</div>
	</main>

	<section id="projects" class="featured-project">
		<div class="section-heading">
			<p>FEATURED PROJECT</p>
			<h2>Retail Sales Analytics (2024–2026)</h2>

			<div class="project-tags">
				<span>SQL Server</span>
				<span>Power BI</span>
				<span>Python</span>
				<span>Data Modeling</span>
			</div>
		</div>

		<div class="project-content">
			<div class="project-info">
				<p class="project-description">
					An end-to-end retail analytics project using three years of sales
					data to uncover trends, measure performance, and generate
					actionable business insights.
				</p>

				<ul class="project-highlights">
					<li>✓ Built SQL data models and analytical views</li>
					<li>✓ Developed an interactive Power BI dashboard</li>
					<li>✓ Performed Python-based sales analysis</li>
					<li>✓ Analyzed sales performance from 2024–2026</li>
				</ul>

				<a href="#" class="primary-btn">View Case Study →</a>
			</div>

			<div class="project-dashboard">
				<div class="project-image-placeholder">
					<p>Retail Sales Dashboard</p>
					<span>Your real Power BI screenshot will go here</span>
				</div>
			</div>
		</div>
	</section>

	<footer>
		<div class="footer-brand">NICHOLETHAO.COM</div>
		<div class="footer-line"></div>
		<div class="footer-text">Build. Learn. Create.</div>
	</footer>
</div>

<style>
	:global(*) {
		box-sizing: border-box;
	}

	:global(html) {
		scroll-behavior: smooth;
		background: #050914;
	}

	:global(body) {
		margin: 0;
		min-width: 320px;
		background: #050914;
		color: #f4f8ff;
		font-family:
			Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI",
			sans-serif;
	}

	.page-shell {
		position: relative;
		min-height: 100vh;
		overflow: hidden;
		background:
			radial-gradient(circle at 50% -20%, rgba(23, 102, 255, 0.15), transparent 40%),
			linear-gradient(180deg, #07101f 0%, #050914 48%, #04070e 100%);
	}

	.grid-background {
		position: absolute;
		inset: 0;
		pointer-events: none;
		opacity: 0.13;
		background-image:
			linear-gradient(rgba(94, 155, 255, 0.3) 1px, transparent 1px),
			linear-gradient(90deg, rgba(94, 155, 255, 0.3) 1px, transparent 1px);
		background-size: 52px 52px;
		mask-image: linear-gradient(to bottom, black, transparent 72%);
	}

	.glow {
		position: absolute;
		border-radius: 999px;
		filter: blur(90px);
		pointer-events: none;
	}

	.glow-one {
		top: 150px;
		left: -180px;
		width: 430px;
		height: 430px;
		background: rgba(0, 102, 255, 0.16);
	}

	.glow-two {
		top: 320px;
		right: -180px;
		width: 480px;
		height: 480px;
		background: rgba(0, 184, 255, 0.11);
	}

	.site-header {
		position: relative;
		z-index: 5;
		display: flex;
		align-items: center;
		justify-content: space-between;
		width: min(1180px, calc(100% - 48px));
		margin: 0 auto;
		padding: 28px 0;
		border-bottom: 1px solid rgba(126, 171, 255, 0.12);
	}

	.brand {
		color: inherit;
		text-decoration: none;
	}

	.brand-name {
		font-size: 16px;
		font-weight: 700;
		letter-spacing: 0.025em;
	}

	.nav-links {
		display: flex;
		align-items: center;
		gap: 32px;
	}

	.nav-links a {
		color: #dce7f7;
		text-decoration: none;
		font-size: 14px;
		font-weight: 500;
		transition: color 0.2s ease;
	}

	.nav-links a:hover {
		color: #4d9cff;
	}

	.hero {
		position: relative;
		z-index: 2;
		width: min(1180px, calc(100% - 48px));
		min-height: 78vh;
		margin: 0 auto;
		padding: 90px 0;
		display: grid;
		grid-template-columns: 1fr 1fr;
		align-items: center;
		gap: 70px;
	}

	.hero-content {
		max-width: 620px;
	}

	.intro {
		margin: 0 0 16px;
		color: #4d9cff;
		font-size: 13px;
		font-weight: 800;
		letter-spacing: 0.14em;
	}

	.hero h1 {
		margin: 0 0 24px;
		color: #ffffff;
		font-size: clamp(52px, 7vw, 82px);
		font-weight: 750;
		line-height: 1;
		letter-spacing: -0.045em;
	}

	.hero-description {
		max-width: 570px;
		margin: 0 0 30px;
		color: #aebbd0;
		font-size: 18px;
		line-height: 1.7;
	}

	.hero-skills {
		display: flex;
		flex-wrap: wrap;
		gap: 12px;
		margin-bottom: 35px;
	}

	.hero-skills span {
		padding: 8px 16px;
		border: 1px solid #31415a;
		border-radius: 20px;
		background: rgba(17, 27, 43, 0.55);
		color: #dce7f7;
		font-size: 14px;
	}

	.hero-buttons {
		display: flex;
		flex-wrap: wrap;
		gap: 15px;
	}

	.primary-btn,
	.secondary-btn {
		display: inline-block;
		padding: 13px 22px;
		border-radius: 7px;
		text-decoration: none;
		font-size: 14px;
		font-weight: 600;
		transition:
			background 0.2s ease,
			border-color 0.2s ease,
			transform 0.2s ease;
	}

	.primary-btn {
		background: #2678e8;
		color: white;
	}

	.primary-btn:hover {
		background: #408df4;
		transform: translateY(-2px);
	}

	.secondary-btn {
		border: 1px solid #40516c;
		color: #dce7f7;
	}

	.secondary-btn:hover {
		border-color: #4d9cff;
		color: #ffffff;
		transform: translateY(-2px);
	}

	.hero-visual {
		display: flex;
		justify-content: center;
	}

	.dashboard-placeholder {
		width: 100%;
		max-width: 520px;
		height: 310px;
		border: 1px solid #31415a;
		border-radius: 16px;
		background:
			linear-gradient(145deg, rgba(22, 38, 63, 0.95), rgba(10, 19, 33, 0.95));
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		text-align: center;
		box-shadow: 0 25px 60px rgba(0, 0, 0, 0.32);
	}

	.dashboard-placeholder p {
		margin: 0 0 8px;
		color: white;
		font-size: 22px;
		font-weight: 700;
	}

	.dashboard-placeholder span {
		color: #71829b;
		font-size: 13px;
	}

	.featured-project {
		position: relative;
		z-index: 2;
		padding: 95px 8%;
		background: #f7f9fc;
		color: #0b1930;
	}

	.section-heading {
		max-width: 800px;
		margin: 0 auto 60px;
		text-align: center;
	}

	.section-heading > p {
		margin: 0 0 12px;
		color: #2678e8;
		font-size: 13px;
		font-weight: 800;
		letter-spacing: 0.12em;
	}

	.section-heading h2 {
		margin: 0 0 22px;
		color: #0b1930;
		font-size: clamp(30px, 4vw, 40px);
		letter-spacing: -0.03em;
	}

	.project-tags {
		display: flex;
		justify-content: center;
		flex-wrap: wrap;
		gap: 10px;
	}

	.project-tags span {
		padding: 8px 14px;
		border-radius: 20px;
		background: #e8eef8;
		color: #20334f;
		font-size: 13px;
	}

	.project-content {
		max-width: 1180px;
		margin: 0 auto;
		display: grid;
		grid-template-columns: 1fr 1.2fr;
		gap: 70px;
		align-items: center;
	}

	.project-description {
		margin: 0 0 28px;
		color: #526178;
		font-size: 16px;
		line-height: 1.8;
	}

	.project-highlights {
		list-style: none;
		padding: 0;
		margin: 0 0 35px;
	}

	.project-highlights li {
		margin-bottom: 16px;
		color: #20334f;
		font-size: 15px;
	}

	.project-image-placeholder {
		height: 340px;
		border: 1px solid #dfe5ee;
		border-radius: 14px;
		background: #ffffff;
		box-shadow: 0 15px 40px rgba(20, 43, 75, 0.1);
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		text-align: center;
	}

	.project-image-placeholder p {
		margin: 0 0 8px;
		color: #0b1930;
		font-size: 22px;
		font-weight: 700;
	}

	.project-image-placeholder span {
		color: #7b8798;
		font-size: 13px;
	}

	footer {
		position: relative;
		z-index: 2;
		display: flex;
		align-items: center;
		width: min(1180px, calc(100% - 48px));
		margin: 0 auto;
		padding: 28px 0 34px;
		color: #596982;
		font-size: 9px;
		font-weight: 700;
		letter-spacing: 0.14em;
	}

	.footer-line {
		height: 1px;
		flex: 1;
		margin: 0 18px;
		background: rgba(110, 155, 222, 0.11);
	}

	@media (max-width: 900px) {
		.nav-links {
			gap: 18px;
		}

		.hero {
			grid-template-columns: 1fr;
			padding: 70px 0 85px;
			text-align: center;
		}

		.hero-content {
			margin: 0 auto;
		}

		.hero-description {
			margin-left: auto;
			margin-right: auto;
		}

		.hero-skills,
		.hero-buttons {
			justify-content: center;
		}

		.project-content {
			grid-template-columns: 1fr;
			gap: 45px;
		}
	}

	@media (max-width: 700px) {
		.site-header {
			width: min(100% - 32px, 1180px);
			align-items: flex-start;
			gap: 20px;
		}

		.nav-links {
			display: none;
		}

		.hero {
			width: min(100% - 32px, 1180px);
			min-height: auto;
		}

		.hero h1 {
			font-size: clamp(48px, 15vw, 70px);
		}

		.hero-description {
			font-size: 16px;
		}

		.featured-project {
			padding: 70px 20px;
		}

		.project-image-placeholder {
			height: 260px;
		}

		footer {
			width: min(100% - 32px, 1180px);
		}
	}
</style>
