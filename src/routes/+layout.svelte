<header>Mohamed Abdelhamid</header>

<div>
	<nav>
		<a href="/" style="margin-left: 50px;" class="home">Home</a>
		<a href="/about_me" class="about-me-a">About me</a>
		<a href="/projects" class="projects">Projects</a>
		<a href="/comics" class="comics">Comics</a>
	</nav>
</div>

<footer>
	<div class="footer-content">
		<p>Copyright © 2023 Hamada hamody</p>
		<p><a href="mailto:m.abdelhamid@innopolis.university">m.abdelhamid@innopolis.university</a></p>
	</div>
</footer>

<slot />

<style>
	header {
		text-align: center;
		font-family: 'Times New Roman', Times, serif;
		padding-top: 40px;
		padding-bottom: 20px;
		font-size: 40px;
	}
	nav {
		text-align: center;
		background-color: black;
		color: aliceblue;
		margin-top: 20px;
		border-radius: 10px;
		padding: 20px;
		display: flex;
		margin-right: 100px;
		margin-left: 100px;
		margin-bottom: 70px;
	}

	nav a {
		color: aliceblue;
		font-size: large;
		text-decoration: none;
		font-family: 'Times New Roman', Times, serif;
	}

	.projects {
		margin-left: auto;
		margin-right: auto;
	}

	.comics {
		margin-right: 50px;
	}

	.about-me-a {
		margin-left: auto;
	}

	footer {
		background-color: #333;
		color: #fff;
		font-size: 14px;
		padding: 10px;
		text-align: center;
		position: fixed;
		left: 0;
		bottom: 0;
		width: 100%;
	}

	.footer-content {
		display: flex;
		flex-direction: row;
		justify-content: space-between;
		align-items: center;
	}

	.footer-content a {
		color: #fff;
	}
</style>
