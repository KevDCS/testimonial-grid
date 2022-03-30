<script></script>

<template>
	<div class="grid-main">
		<div class="grid-item-1">
			<div class="grid-item-1-title">
				<img
					class="grid-item-1-img"
					src="/src/images/image-daniel.jpg"
					alt=""
				/>
				<div class="grid-item-1-title-text">
					<p>Daniel Clifford</p>
					<span>Verified Graduate</span>
				</div>
			</div>
			<div class="grid-item-1-text">
				<p class="item-text-1">
					I received a job offer mid-course, and the subjects I learned were
					current, if not more so, in the company I joined. I honestly feel I
					got every penny’s worth.
				</p>

				<p class="item-text-2">
					“ I was an EMT for many years before I joined the bootcamp. I’ve been
					looking to make a transition and have heard some people who had an
					amazing experience here. I signed up for the free intro course and
					found it incredibly fun! I enrolled shortly thereafter. The next 12
					weeks was the best - and most grueling - time of my life. Since
					completing the course, I’ve successfully switched careers, working as
					a Software Engineer at a VR startup. ”
				</p>
			</div>
		</div>

		<div class="grid-item-2">
			<div class="grid-item-2-title">
				<img
					class="grid-item-2-img"
					src="/src/images/image-jonathan.jpg"
					alt=""
				/>
				<div class="grid-item-2-title-text">
					<p>Jonathan Walters</p>
					<span>Verified Graduate</span>
				</div>
			</div>

			<div class="grid-item-2-text">
				<p class="item-text-1">
					The team was very supportive and kept me motivated
				</p>

				<p class="item-text-2">
					“ I started as a total newbie with virtually no coding skills. I now
					work as a mobile engineer for a big company. This was one of the best
					investments I’ve made in myself. ”
				</p>
			</div>
		</div>

		<div class="grid-item-3">
			<div class="grid-item-3-title">
				<img class="grid-item-3-img" src="/src/images/image-kira.jpg" alt="" />
				<div class="grid-item-3-title-text">
					<p>Kira Whittle</p>
					<span>Verified Graduate</span>
				</div>
			</div>

			<div class="grid-item-3-text">
				<p class="item-text-1">
					Such a life-changing experience. Highly recommended!
				</p>

				<p class="item-text-2">
					“Before joining the bootcamp, I’ve never written a line of code. I
					needed some structure from professionals who can help me learn
					programming step by step. I was encouraged to enroll by a former
					student of theirs who can only say wonderful things about the program.
					The entire curriculum and staff did not disappoint. They were very
					hands-on and I never had to wait long for assistance. The agile team
					project, in particular, was outstanding. It took my learning to the
					next level in a way that no tutorial could ever have. In fact, I’ve
					often referred to it during interviews as an example of my developent
					experience. It certainly helped me land a job as a full-stack
					developer after receiving multiple offers. 100% recommend!”
				</p>
			</div>
		</div>

		<div class="grid-item-4">
			<div class="grid-item-4-title">
				<img
					class="grid-item-4-img"
					src="/src/images/image-patrick.jpg"
					alt=""
				/>
				<div class="grid-item-4-title-text">
					<p>Patrick Abrams</p>
					<span>Verified Graduate</span>
				</div>
			</div>

			<div class="grid-item-4-text">
				<p class="item-text-1">
					Awesome teaching support from TAs who did the bootcamp themselves.
					Getting guidance from them and learning from their experiences was
					easy.
				</p>

				<p class="item-text-2">
					“ The staff seem genuinely concerned about my progress which I find
					really refreshing. The program gave me the confidence necessary to be
					able to go out in the world and present myself as a capable junior
					developer. The standard is above the rest. You will get the personal
					attention you need from an incredible community of smart and amazing
					people. ”
				</p>
			</div>
		</div>

		<div class="grid-item-5">
			<div class="grid-item-5-title">
				<img
					class="grid-item-5-img"
					src="/src/images/image-jeanette.jpg"
					alt=""
				/>
				<div class="grid-item-5-title-text">
					<p>Jeanette Harmon</p>
					<span>Verified Graduate</span>
				</div>
			</div>

			<div class="grid-item-5-text">
				<p class="item-text-1">An overall wonderful and rewarding experience</p>

				<p class="item-text-2">
					“ Thank you for the wonderful experience! I now have a job I really
					enjoy, and make a good living while doing something I love. ”
				</p>
			</div>
		</div>
	</div>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Barlow+Semi+Condensed:wght@500;600&display=swap");

:root {
	/* Variables */

	/* Colors */
	--Moderate_violet: hsl(263, 55%, 52%);
	--Very_dark_grayish_blue: hsl(217, 19%, 35%);
	--Very_dark_blackish_blue: hsl(219, 29%, 14%);
	--White: hsl(0, 0%, 100%);
	--Light_gray: hsl(0, 0%, 81%);
	--Light_grayish_blue: hsl(210, 46%, 95%);

	/* Font */

	font-family: "Barlow Semi Condensed", sans-serif;
}

/* Box sizing rules */
*,
*::before,
*::after {
	box-sizing: border-box;
}

/* Remove default margin */
body,
h1,
h2,
h3,
h4,
p,
figure,
blockquote,
dl,
dd {
	margin: 0;
}

/* Remove list styles on ul, ol elements with a list role, which suggests default styling will be removed */
ul[role="list"],
ol[role="list"] {
	list-style: none;
}

/* Set core root defaults */
html:focus-within {
	scroll-behavior: smooth;
}

/* Set core body defaults */
body {
	display: flex;
	justify-content: center;
	align-items: center;
	min-height: 100vh;
	text-rendering: optimizeSpeed;
	line-height: 1.5;
	font-family: "Barlow Semi Condensed", sans-serif;
	background-color: var(--Light_grayish_blue);
}

/* A elements that don't have a class get default styles */
a:not([class]) {
	text-decoration-skip-ink: auto;
}

/* Make images easier to work with */
img,
picture {
	max-width: 100%;
	display: block;
}

/* Inherit fonts for inputs and buttons */
input,
button,
textarea,
select {
	font: inherit;
}

/* Remove all animations, transitions and smooth scroll for people that prefer not to see them */
@media (prefers-reduced-motion: reduce) {
	html:focus-within {
		scroll-behavior: auto;
	}

	*,
	*::before,
	*::after {
		animation-duration: 0.01ms !important;
		animation-iteration-count: 1 !important;
		transition-duration: 0.01ms !important;
		scroll-behavior: auto !important;
	}
}

.grid-main {
	display: grid;
	grid-template-columns: repeat(4, 1fr);
	grid-template-rows: repeat(2, min-content);
	width: 1150px;
	font-size: 13px;
	grid-gap: 15px;
}

.grid-item-1 {
	border-radius: 10px;
	padding: 25px;
	background-color: var(--Moderate_violet);
	background-image: url(/src/images/bg-pattern-quotation.svg);
	background-repeat: no-repeat;
	background-position: 80% 0;

	grid-column: 1/3;
}

.grid-item-2 {
	border-radius: 10px;
	padding: 25px;
	background-color: var(--Very_dark_grayish_blue);

	grid-column: 3/4;
}

.grid-item-3 {
	border-radius: 10px;
	padding: 25px;
	background-color: var(--White);

	grid-row: -1/1;
	grid-column: 4/5;
}

.grid-item-4 {
	border-radius: 10px;
	padding: 25px;
	background-color: var(--Very_dark_blackish_blue);

	grid-column: 2/4;
	grid-row: 2/3;
}

.grid-item-5 {
	border-radius: 10px;
	padding: 25px;
	background-color: var(--White);

	grid-column: 1/2;
	grid-row: 2/3;
}

.grid-item-1-title,
.grid-item-2-title,
.grid-item-4-title {
	display: flex;
	color: var(--White);
}

.grid-item-3-title,
.grid-item-5-title {
	display: flex;
}

.grid-item-1-img,
.grid-item-2-img,
.grid-item-3-img,
.grid-item-4-img,
.grid-item-5-img {
	height: 30px;
	width: 30px;
	border-radius: 50%;
	border: 2px solid var(--Light_grayish_blue);
}

.grid-item-1-title-text,
.grid-item-2-title-text,
.grid-item-3-title-text,
.grid-item-4-title-text,
.grid-item-5-title-text {
	height: 30px;
	padding-left: 20px;
	display: flex;
	flex-direction: column;
	justify-content: center;
}

.grid-item-1-title-text,
.grid-item-2-title-text,
.grid-item-3-title-text,
.grid-item-4-title-text,
.grid-item-5-title-text span {
	opacity: 50%;
}

.grid-item-1-text,
.grid-item-2-text,
.grid-item-4-text {
	color: var(--White);
}

.item-text-1 {
	font-size: 19px;
	padding: 10px 0 5px 0;
}

.item-text-2 {
	font-size: 13px;
	opacity: 70%;
	font-weight: var(--font-500);
}

@media (max-width: 1024px) {
	body {
		padding: 20px;
	}

	.grid-main {
		grid-template-columns: repeat(3, 1fr);
		grid-template-rows: repeat(3, min-content);
		width: 95%;
		grid-gap: 15px;
	}

	.grid-item-1 {
		grid-column: 1/3;
	}

	.grid-item-2 {
		grid-column: 3/4;
	}

	.grid-item-3 {
		grid-column: 1/4;
		grid-row: 3/4;
	}
}

@media (max-width: 768px){
	.grid-main{
		margin-top: 20px;
		grid-template-columns: repeat(auto-fill, minmax(50%, 1fr));
		grid-template-rows: minmax(auto, auto);
}
	.grid-item-1,
	.grid-item-2,
	.grid-item-3,
	.grid-item-4,
	.grid-item-5 {
		grid-column: unset !important;
		grid-row: unset !important;
}
}
</style>
