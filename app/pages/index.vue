<template>
	<Scaffold>
		<template #app-bar>
			<a href="#main-content" class="skip-link">{{ $t('accessibility.skipToContent') }}</a>
			<Header />
		</template>

		<template #body>
			<main id="main-content" tabindex="-1">
				<Hero />
				<div class="max-w-section mx-auto">
					<AboutMe />
					<Skills />
					<Startups />
					<Projects />
					<FAQ />
					<CTA />
				</div>
			</main>
			<Footer />
		</template>
	</Scaffold>
</template>
