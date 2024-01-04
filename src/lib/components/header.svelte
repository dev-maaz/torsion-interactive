<header>

	<div class="navbutton">
		<img class="icon" src="home.png" alt="icon">
		<a href="/blog">Home</a>
	</div>

	<div class="navbar">

		<div class="navbutton">
			<img class="icon" src="blog_book.png" alt="icon">
			<a href="/blog">Blog</a>
		</div>

		<div class="navbutton">
			<img class="icon" src="about.png" alt="icon">
			<a href="/about">About</a>
		</div>

		<div class="navbutton">
			<img class="icon" src="contact.png" alt="icon">
			<a href="/contact">Contact</a>
		</div>

	</div>
	
</header>
<div class="logosetter">
	<img src="torison interactive3-01.png" alt="" style="padding: 2rem 0 2rem 0">
</div>


<style>
	header {
		padding: 1rem;
		background: #1F1717;
		display: flex;
		flex-wrap: wrap;
		justify-content: space-between;
		align-items: center;
		box-sizing: border-box;
		width: 100%;


	}

	ul {
		margin: 0;
		list-style-type: none;
		display: flex;
		gap: 1rem;
	}

	a {
		text-decoration: none;
		color: #FCF5ED;

		padding: 0 1rem 0 0.15rem;
	}

	.navbutton{

		display: flex;
		flex-flow: row wrap;
		align-items: center;
		justify-content: center;

		gap: 0.3rem;

	}

	.navbar{

		display: flex;
		flex-flow: row wrap;
		background-color: #1F1717;
		max-height: fit-content;

		gap: 2rem;
		
	}

	.icon{
		max-width: 2rem;
	}

	img{
		max-width: 20rem;
		padding: 0 0 0 0.25rem;
		margin-left: auto;
		margin-right: auto;
	}

	.logosetter{

		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}


</style>