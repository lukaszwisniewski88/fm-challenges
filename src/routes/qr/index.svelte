<svelte:head>
	<link rel="preconnect" href="https://fonts.googleapis.com" />
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="anonymous" />
	<link
		href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap"
		rel="stylesheet"
	/>
	<meta charset="UTF-8" />
	<meta name="viewport" content="width=device-width, initial-scale=1.0" />
	<!-- displays site properly based on user's device -->
	<link rel="icon" type="image/png" sizes="32x32" href="/qr/favicon-32x32.png" />
	<title>Frontend Mentor | QR code component</title>
</svelte:head>
<main class="min-h-screen grid p-4 grid-cols-1 items-center">
	<div class="bg-white rounded-xl mx-auto max-w-xs space-y-4 p-4 ">
		<img alt="qr code" src="/qr/image-qr-code.png" class="rounded-md mx-auto" />
		<div class="space-y-4 text-center p-2">
			<h3 class="font-bold text-center text-2xl">
				Improve your front-end skills by building projects
			</h3>
			<p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
		</div>
	</div>
	<div class="mx-auto attribution self-end">
		Challenge by <a
			href="https://www.frontendmentor.io?ref=challenge"
			target="_blank"
			rel="external">Frontend Mentor</a
		>. Coded by
		<a href="https://github.com/lukaszwisniewski88" rel="external">Łukasz Wiśniewski</a>.
	</div>
</main>

<style>
	main {
		--bg-color: hsl(212, 45%, 89%);
		--head-color: hsl(218, 44%, 22%);
		--text-gray: hsl(220, 15%, 55%);
		font-family: 'Outfit', sans-serif;
		background-color: var(--bg-color);
		color: var(--text-gray);
		font-size: 15px;
	}
	h3 {
		color: var(--head-color);
	}
	.attribution a {
		color: hsl(228, 45%, 44%);
	}
</style>
