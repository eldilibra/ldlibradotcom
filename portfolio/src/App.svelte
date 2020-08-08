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
				<p>Vera Institute of Justice & Institute for Innovation in Prosecution. I freelanced for Hyperakt, which had the client relationship (https://www.hyperakt.com). </p>
			</div>      
			<div class="team">
				<h2><sup>THE</sup>TEAM</h2>
				<p>Hyperakt supplied the project manager, designer, and hosting. I supplied the fullstack web development.</p>
			</div>      
			<div class="work">
				<h2><sup>THE</sup>WORK</h2>
				<p>This project aims to equip prosecutors in the U.S. to challenge the racial inequities in the criminal justice system. Rich imagery, long-form historical context and action steps come together to create a nuanced narrative.</p>
				<p>CraftCMS (and its wonderful GraphQL API) is used to structure and edit the content. The frontend is a React SPA served by a lightweight Node.js server.</p>
				<p>The defining abstractions for this site were the handling of slide-out informational panels, which for a given Craft entry, draw content from nested entries in Craft, as well as mobile-first CSS approach to make sure the various content blocks were re-used across pages. Animations powered by react-spring. Network IO made easy by Apollo.</p>
			</div>      
		</section>
		<section>
			<div>
				<img />
				<img />
				<img />
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

	.project-title-and-timespan, .client, .team, .work {
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
</style>