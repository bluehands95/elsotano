<script>
	import Header from '../../lib/Header.svelte';
	import TopBar from '../../lib/TopBar.svelte';
</script>

<Header />
<TopBar />

<div class="sm:my-28 my-5 sm:mx-32  mx-5 font-open">
	<h1 class="text-4xl text-bold text-black text-bold my-2">Nuestras librerías</h1>
	<div class="bg-blue-700 w-1/5 h-1 sm:mb-16 mb-5 sm:my-5 my-2" />
	<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 place-items-center content-center">
		<div class="grid mx-1 sm:mx-1 border-2 border-gray-100 my-10">
			<img
				src="https://www.elsotano.com/images/sucursales/002-es-b_sucursales.jpg"
				class="h-auto sm:mb-5 mb-2"
				alt="sucursales-logo"
			/>
			<div class="flex flex-col m-3">
				<h1 class="text-black mb-2 text-bold text-xl uppercase">Quevedo</h1>
				<div class="grid">
					<h2 class="text-md text-gray-600 p-1">
						<i class="fa-solid fa-house mr-1" />
						Av. Miguel Ángel de Quevedo No. 209 Col. Romero de Terreros C.P. 04310 Coyoacán. México,
						D.F. Teléfono (55) 5339-1300 107, 110, 146 y 172
					</h2>
					<h2 class="text-md text-gray-600 p-1">
						<i class="fa-solid fa-phone mr-1" />
						(55) 5339 1300
					</h2>
					<h2 class="text-md text-gray-600 p-1">
						<i class="fa-solid fa-envelope mr-1" />
						atencionaclientes@elsotano.com
					</h2>
					<h2 class="text-md text-gray-600 p-1">
						<i class="fa-solid fa-link mr-1" />
						https://www.elsotano.com
					</h2>
				</div>
				<div class="bg-gray-100 h-[1px] w-full my-3" />
				<h1 class="ml-1 text-black text-lg">Horario</h1>
				<div class="grid p-2">
					<h2 class="text-md text-gray-600">Lunes a sábado: 9 a 22 h</h2>
					<h2 class="text-md text-gray-600">Domingo 10 a 21 h</h2>
				</div>
				<div class="bg-gray-100 h-[1px] w-full my-3" />
				<h1 class="ml-1 text-black text-lg mt-1">Servicios</h1>
				<div class="flex p-2 text-gray-600">
					<h2 class="mx-2"><i class="fa-solid fa-car"></i></h2>
					<h2 class="mx-2"><i class="fa-solid fa-wifi"></i></h2>
				</div>
			</div>
		</div>
	</div>
</div>
