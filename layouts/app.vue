<template>
	<div>
		<app-header/>
		<main class="container is-max-widescreen gap-on-mobile">
			<div class="columns is-desktop mt-2">
				<div class="column is-one-fifth-desktop">
					<app-navigation/>
				</div>
				<div class="column">
					<Nuxt/>
				</div>
				<div class="column is-one-fifth-desktop is-relative">
					<app-scoreboard/>
				</div>
			</div>
		</main>
		<app-footer/>
	</div>
</template>