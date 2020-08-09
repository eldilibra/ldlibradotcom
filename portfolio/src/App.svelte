<script>
</script>

<header>
	<div class="contact-info">
		<span>L.D Libra</span>
		<span>writeme@ldlibra.com</span>
		<span>218.821.1379</span>
		<span>Brooklyn, NY</span>
	</div>
	<h1>RECENT PROJECTS - 2020</h1>
</header>
<main>
	<nav>
		<div>
			<div>Motion for Justice</div>
			<div>202.82 hours spanning March 15 - July 22</div>
		</div>
		<div>
			<div>CPI</div>
			<div>April 4 - May 18</div>
		</div>
		<div>
			<div>ZeroPlace</div>
			<div>April 4 - May 18</div>
		</div>
	</nav>
	<section>
		<section>
			<div class="project-title-and-timespan">
				<h3>Motion for Justice</h3>
				<div>202.82 hours, March 15 - July 22</div>
			</div>
			<div class="client">
				<h2><sup>THE</sup>CLIENT</h2>
				<p>Vera Institute of Justice & Institute for Innovation in Prosecution. I freelanced for <a href="https://www.hyperakt.com" target="_blank">Hyperakt</a>, which had the client relationship.</p>
			</div>
			<div class="team">
				<h2><sup>THE</sup>TEAM</h2>
				<p>Hyperakt supplied the project manager, designer, and hosting. I supplied the fullstack web development.</p>
			</div>      
			<div class="work">
				<h2><sup>THE</sup>WORK</h2>
				<a href="https://motionforjustice.org" target="_blank">https://motionforjustice.org</a>
				<p>This project aims to equip prosecutors in the U.S. to challenge the racial inequities in the criminal justice system. Rich imagery, long-form historical context and action steps come together to create a nuanced narrative.</p>
				<p>CraftCMS (and its wonderful GraphQL API) is used to structure and edit the content. The frontend is a React SPA served by a lightweight Node.js server.</p>
				<p>The defining abstractions for this site were the handling of slide-out informational panels, which for a given Craft entry, draw content from nested entries below it, as well as a mobile-first CSS approach that made sure the various content blocks were re-used across pages. Animations powered by react-spring. Network IO made easy by Apollo.</p>
			</div>      
		</section>
		<section>
			<div>
				<img src="/assets/images/motionforjustice-desktop.png" alt="Screenshot of Motion for Justice site on desktop." />
				<img src="/assets/images/motionforjustice-tablet.png" alt="Screenshot of Motion for Justice site on tablet." />
				<img src="/assets/images/motionforjustice-mobile.png" alt="Screenshot of Motion for Justice site on mobile." />
			</div>
		</section>
		<section>
			<div class="project-title-and-timespan">
				<h3>CPI Candidate Application</h3>
				<div>MS 1: April 20 - June 1, MS 2: June 24 - August 3</div>
			</div>
			<div class="client">
				<h2><sup>THE</sup>CLIENT</h2>
				<p>Continuity Partners, Inc., a tech-forward recruiting firm based in Manhattan.</p>
			</div>
			<div class="team">
				<h2><sup>THE</sup>TEAM</h2>
				<p>I shared the role of project manager with the client, as well as fullstack web developer, devops, and production support. Alongside me, there was 1 other developer and 1 designer.</p>
			</div>      
			<div class="work">
				<h2><sup>THE</sup>WORK</h2>
				<p>This project started in early March with some basic feature improvements and reskinning to an existing admin tool, which matched candidates with jobs according to their skills.</p>
				<h3>Milestone 1</h3>
				<p>After getting acquainted with the codebase and infrastructure, myself and another developer underwent the first phase of a mobile-focused web app for candidates to swipe right or left on different job opportunities, indicating interest or lack thereof. This phase also included email-based alerting so the recruiters at CPI could take action immediately when a candidate made a decision about a job.</p>
				<p>We modified the existing Scala backend for the new data access requirements necessitated by the candidate app. The job description and company description were written in HTML so had to be sanitized on the backend before rendering. The touch-friendly frontend was a React app using <a href="https://use-gesture.netlify.app/">react-use-gesture</a> to handle gesture events and react-spring for animation.</p>
				<h3>Milestone 2</h3>
				<p>Our second phase involved splitting out the stream of a candidate's job matches into separate tabs based on their status, as well as more detailed filtering based on where the candidate is in a company's application process e.g. only showing jobs in which the application is still active. We also set up an entire staging environment for the backend, the admin app, and the new candidate app during this phase, made styling updates and fixed a few bugs.</p>
				<h3>Milestone 3</h3>
				<p>In the works...</p>
			</div>      
		</section>
		<section>
			<div>
				<img src="/assets/images/cpi-desktop.png" alt="Screenshot of CPI Candidate App on desktop." />
				<img src="/assets/images/cpi-tablet.png" alt="Screenshot of CPI Candidate App site on tablet." />
				<img src="/assets/images/cpi-mobile.png" alt="Screenshot of CPI Candidate App site on mobile." />
			</div>
		</section>
		<section>
			<div class="project-title-and-timespan">
				<h3>ZeroPlace Energy Monitor</h3>
				<div>MS 1: June 1 - July 1</div>
			</div>
			<div class="client">
				<h2><sup>THE</sup>CLIENT</h2>
				<p><a href="https://zeroplace.com/">ZeroPlace</a>, a high efficiency apartment building designed for carbon neutral living.</p>
			</div>
			<div class="team">
				<h2><sup>THE</sup>TEAM</h2>
				<p>I handled all design, development, and deployment.</p>
			</div>      
			<div class="work">
				<h2><sup>THE</sup>WORK</h2>
				<p>This project had an interesting topology. I was to build a dashboard for tenants at ZeroPlace to monitor their energy usage in their apartment, relative to the usage of their peers in similar units in the building. The data is stored on an eGauge sensor device, which has an XML-based API. The client wanted as little recurring cloud expenditure as possible. Also, a future goal was to display a leaderboard of low energy usage in a common space, on a large screen.</p>
				<h3>Milestone 1: Tenant Dashboard</h3>
				<p>In the design phase, I found it compelling to make the dashboard feel a little sci-fi, but still approachable: a dark background with variable digit sizes to draw attention to different readings. ZeroPlace is building the future, so their tech should hint at that.</p>
				<p>Not knowing the exact specs of whatever screen would render the leaderboard, I decided this would be a great project to learn <a href="https://svelte.dev/">Svelte</a>. I've had my eye on it for a while; its virtual-dom-less, compile-to-simple-JS approach produces smaller bundle sizes than its more mature peers (React, Vue) for similar apps.</p>
				<p>On the backend, I would need code only to authenticate to the eGauges, then to pull the data according to parameters sent by the client. With such a small footprint, and looking for minimal cost, I decided on another new-to-me tech I've been meaning to use: <a href="https://www.serverless.com/">the Serverless framework</a>, specifically Node.js on AWS Lambda. I would normally be hesitant to take on 2 new tools for a project, but both allowed me to use existing skills in a slightly different context, while nailing the requirements. In hindsight, it was a great choice.</p>
				<p>One unexpected detour that came up early in the project was the lack of JS library support for digest access authentication, which the eGauge API requires. After a bit of casting about for a suitable open source module, I wrote my own, though it's not extractable as a standalone project just yet.</p>
				<p>The coolest thing about this project to me is that we can think of the multiple eGauge sensors in aggregate as a distributed database, with the web app simply pulling in the data it needs, directly from the sensors. If this were built as a native Electron app or the like, rather than served from a file server with an AWS Lambda doing the data fetching, it would be a truly decentralized project.</p>
				<h3>Milestone 2: Admin Dashboard</h3>
				<p>In the works...</p>
			</div>      
		</section>
		<section>
			<div>
				<img src="/assets/images/zeroplace-desktop.png" alt="Screenshot of ZeroPlace tenant dashboard on desktop." />
				<img src="/assets/images/zeroplace-tablet.png" alt="Screenshot of ZeroPlace tenant dashboard on tablet." />
				<img src="/assets/images/zeroplace-mobile.png" alt="Screenshot of ZeroPlace tenant dashboard on mobile." />
			</div>
		</section>
	</section>
</main>

<style>
  header, main, .contact-info {
    display: flex;
  }

  header {
		flex-direction: column;
		justify-content: space-between;
		margin-bottom: 2em;
	}
	
	header h1 {
		font-size: 1.7em;
		margin-bottom: 0.2em;
		border-bottom: solid 1em lightsteelblue;
	}

  .contact-info {
		display: flex;
		flex-direction: column;
		text-transform: uppercase;
		letter-spacing: 0.15em;
		border-right: solid 0.5em #ffa6b4;
	}
	
	sup {
		font-size: 0.4em;
	}

	nav {
		display: none;
	}

	section {
		width: 100%;
	}

	.client, .team, .work {
		padding-right: 1em;
	}

	.project-title-and-timespan {
		display: flex;
		border-left: solid 0.5em #5fffa5;
		flex-direction: column;
		align-items: flex-end;
		width: calc(100% - 0.5em);
	}

	.client {
		border-right: solid 4em #ff7656;
	}

	.team {
		border-right: solid 10em #b6f8ff;
	}

	.work {
		border-right: solid 6.5em fuchsia;
	}

	img:first-child {
		max-width: 100%;
	}

	img:nth-child(2) {
		max-width: 50%;
	}

	img:nth-child(3) {
		max-width: 25%;
	}
</style>