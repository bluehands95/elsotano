<script>
	import Header from '../../lib/Header.svelte';
	import TopBar from '../../lib/TopBar.svelte';
</script>

<Header />
<TopBar />
<div class="py-12 font-open sm:px-2 md:px-20 lg:px-40 px-1">
	<label
		for="email-address-icon"
		class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">Your Email</label
	>
	<div class="relative">
		<div class="flex absolute inset-y-0 left-0 items-center pl-3 pointer-events-none">
			<i class="fa-regular fa-envelope w-5 h-5 text-gray-500" />
		</div>
		<input
			type="text"
			id="email-address-icon"
			class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full pl-10 p-2.5  dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
			placeholder="nombre@ejemplo.com"
		/>
	</div>
	<label
		for="email-address-icon"
		class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">Your Email</label
	>
	<div class="relative">
		<div class="flex absolute inset-y-0 left-0 items-center pl-3 pointer-events-none">
			<i class="fa-solid fa-signature w-5 h-5 text-gray-500" />
		</div>
		<input
			type="text"
			id="email-name-icon"
			class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full pl-10 p-2.5  dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
			placeholder="Nombre Ejemplo"
		/>
	</div>

	<label for="message" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-400"
		>Tu mensaje</label
	>
	<textarea
		id="message"
		rows="4"
		class="block p-2.5 w-full text-sm text-gray-900 bg-gray-50 rounded-lg border border-gray-300 focus:ring-blue-500 focus:border-blue-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
		placeholder="Escribe tu mensaje"
	/>
</div>
