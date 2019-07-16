<main id="content" class="page about">
	<header class="cover">
	</header>
	<article class="page about" data-base="#6f6f6f" data-highlight="#555">
		<p>I spent far too long in the planning phase.</p>

		<figure>
			<img src="/assets/img/other/site-0.jpg">
			<img src="/assets/img/other/site-1.jpg">
			<img src="/assets/img/other/site-2.jpg">
		</figure>

		<p>My original plans called for something pretty ambitious and very cheesy: this sort of light metaphor with canvas that would 'illuminate' various sections of the site to traverse. It was meant to be an allusion to my past as a photographer, if you'll believe that.</p>

		<figure>
			<img src="/assets/img/other/site-3.jpg">
			<img src="/assets/img/other/site-4.jpg">
			<img src="/assets/img/other/site-5.jpg">
			<figcaption>The site is littered with icons for a reason.</figcaption>
		</figure>

		<p>The approach I had with this site was to create an experience, as alluded in the notes tucked away in these photographs, that was entirely comunicable though iconography.</p>

		<p>In a grand defiance with what the web was meant for, I aimed at creating a site that needn't any translation, where text was just set dressing for the main event.</p>

		<p>The icons are here too inspired by camera markings and circuit diagrams, both of fields I deeply associate with and enjoy.</p>

		<figure>
			<img src="/assets/img/other/site-6.jpg">
			<img src="/assets/img/other/site-7.jpg">
			<img src="/assets/img/other/site-8.jpg">
		</figure>

		<p>Quite the adventure, isn't it?</p>

		<p>This site was built using the now-abandoned static site generator <a href="http://harpjs.com">harp</a>. I've since moved to what I could call a fork of [Nanogen](https://github.com/doug2k1/nanogen) Thankfully, it still works! I can write all my pages in markdown, or ejs, jade, stylus and a bunch of other preprocessors. I compile the whole thing into a folder and bingo. The entire site in a folder. No live anything.</p>

		<p>The idea to go for a static site build was mostly born of curiosity, and I'd also grown a little tired with the needless complexity introduced by wordpress as a CMS for something so simple as a portfolio site.</p>

		<p>I miss the front-end, but hey.</p>

		<p>The rest of the design process is right here! You're looking at it. Nothing is hidden, and the code itself lives in a <a href="https://github.com/stockhuman/internaut">little repo</a> on Github.</p>
	</article>
	<style type="text/css">
		#nav-main {color: white !important;}
		#nav-inner {
			animation: colorchange 50s;
			-webkit-animation: colorchange 50s;
			animation-iteration-count: infinite;
		}

		@keyframes colorchange
		{
			0%   {background: red;}
			25%  {background: yellow;}
			50%  {background: blue;}
			75%  {background: green;}
			100% {background: red;}
		}

		@-webkit-keyframes colorchange {
			0%   {background: red;}
			25%  {background: yellow;}
			50%  {background: blue;}
			75%  {background: green;}
			100% {background: red;}
		}
	</style>

</main>