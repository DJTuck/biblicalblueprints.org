<svelte:head>
	<title>Biblical Blueprints</title>
	<link href="garamond-logo-font.css" rel="stylesheet" type="text/css" />
</svelte:head>

<div class="header">
	<img class="logo" src="images/logo-bb.svg" alt="BB Logo">
	<h1 class="logo-text">Biblical Blueprints</h1>
</div>

<hr>

<p>
	Biblical Blueprints is a Christian non-profit organization reforming the world by serving leaders and publishing writings that apply the Bible's commands to family, church, and culture.
</p>

<h2>International missions</h2>
<hr>
<p>
	Pastor Kayser periodically meets with church leaders in restricted countries to offer leadership training, worldview training, and theological training.
</p>

<h2>Church ministry</h2>
<hr>
<p>
	Pastor Kayser has spoken at over 50 conferences in the last 10+ years, such as the National Council of Family Integrated Churches conference and the Generations Shepherds Conference.  He also helps churches and church plants with problem solving.
</p>

<h2>Leadership mentoring</h2>
<hr>
<p>
	At any given time, Pastor Kayser mentors about a half-dozen men, providing training they can't get at seminary.
</p>
<p>
	He meets with them individually for 1-2 hours every week, working through a curriculum of theology designed to equip them to be leaders.
</p>

<h2>Biblical resources</h2>
<hr>

<h3 class="external-site-header">
	<a
		href="https://kaysercommentary.com/"
		target="_blank"
		rel="external"
	>
		<img
			src="images/kayser-commentary-k.svg"
			alt="Kayser Commentary logo"
			class="external-site-logo"
		>

		Kayser Commentary
	</a>
</h3>

<p>
	Blog posts, booklets, an extensive library of sermon transcripts, and other written resources.
</p>

<hr>

<h3 class="external-site-header">
	<a
		href="https://revelation.biblicalblueprints.org/"
		target="_blank"
		rel="external"
	>
		<img
			src="images/revelation-project.svg"
			alt="Kayser Commentary logo"
			class="external-site-logo"
		>
		The Revelation Project
	</a>
</h3>

<p>
	The companion resource to Pastor Kayser's multi-year sermon series on Revelation.
</p>

<hr>

<h3 class="external-site-header">
	<a
		href="https://kaysercommentary.com/booklets.md"
		target="_blank"
		rel="external"
	>
		Booklets
	</a>
</h3>

<p>
	Pastor Kayser's books on theology and practical application of the Bible are available as downloadable ebooks and to read online.
</p>

<style>
.header {
	display: flex;
	align-items: center;
}
.logo {
	height: 100px;
	width: 100px;
	margin-right: 20px;
}
.logo-text {
	margin-top: 0;
	margin-bottom: 0;
	font-family: 'Garamond BB logo';
	color: #149bec;
	font-size: 60px;
	font-weight: 300;
}

.external-site-header {
	margin-top: 32px;
	margin-bottom: 0;
}
.external-site-header a {
	display: flex;
	align-items: center;
}
.external-site-header img {
	height: 75px;
	width: 75px;
	margin-right: 16px;
}

ul {
	list-style-type: '·  ';
	padding-left: 24px;
}

@media (max-width: 680px) {
	.logo {
		height: 80px;
		width: 80px;
	}
	.logo-text {
		font-size: 50px;
	}
}

</style>
