<style>
	h1, figure, p {
		text-align: center;
		margin: 0 auto;
	}


	figure {
		margin: 0 0 1em 0;
	}

	img {
		width: 100%;
		max-width: 400px;
		margin: 0 0 1em 0;
	}

	p {
		margin: 1em auto;
	}
	.header{
		display: flex;
		justify-content: center;
		align-items: center;
		min-height: 70vh;
	}
	.main{
		max-width: 1170px;
		border-top: 4px solid #98c93f;
		padding-top: 30px;
		display: flex;
		flex-direction: row;
		justify-content: space-between;
		flex-wrap: wrap;
	}

	.logo-text{
		width: 120px;
		height: auto;
	}

	.logo-text img {
		height: 60px;
	}

	.main-text{
		width: 400px;
	}

	p{
		font-weight: 300;
		line-height: 1.5;
		color: #5f6a7d;
		font-size: 16px;
		letter-spacing: .5px;
		margin: 0 0 30px;
	}
	.contact-us{
		background-color: #98c93f;
		display: flex;
		justify-content: center;
		align-items: center;
		height: 11px;
	}
	.btn{
		width: 100px;
		padding: 20px 42px;
		border-radius: 4px;
		text-align: center;
		color: #fff;
		font-weight: bold;
		letter-spacing: 2px;
		text-transform: uppercase;
		font-size: 11px;
		white-space: nowrap;
		cursor: pointer;
		-moz-user-select: none;
		-ms-user-select: none;
		user-select: none;
		background-image: none;
		border: 1px solid transparent;
	}
	a{
		color: #fff;
		text-decoration: none;
	}

	.btn.contact-us:hover {
		width: 94px;
		background-color: #fff;
		border: 4px solid #98c93f;
		color: #202020;
		height: 7px;
		transition: all .5s;
	}

	@media (max-width: 992px) {
		.main-text{
			display: none;
		}
		.main{
			align-items: center;
			flex-direction: column;
			justify-content: center;
		}
	}
</style>

<svelte:head>
	<title>Gaia Green Tech</title>
</svelte:head>

<div class="header">
	<div class="logo">
		<img src="GaiaGreenTechLeaf.svg" alt="Gaia Green Tech Logo"/>
	</div>
</div>
<div class="main">
	<figure class="logo-text">
		<img src="GaiaGreenTech.svg" alt="Gaia Green Tech"/>
	</figure>
	<div class="main-text">
		<p class="editContent">
			We're building solutions in shared mobility, PV systems and charging infrastructure.
		</p>
	</div>
	<a class="btn contact-us" href="mailto:contact@gaiagreen.tech">
		Contact Us
	</a>
</div>
