<script>
import { session } from '$app/stores'
</script>

<section class="w-full h-full pl-2 sm:pl-8 sm:pr-2 text-gray-800 tracking-wide ">
	<h1 class=" ">
		<span class="font-bold  text-lg sm:text-xl mr-1">Hi!</span>
		<span class="text-sm sm:text-base text-gray-500">{$session?.user?.email}</span>
	</h1>

	<div
		class="mt-2 md:mt-5 md:flex md:items-center md:justify-between space-y-4 md:space-y-0 md:space-x-8">
		<div
			class="md:w-1/2 overflow-hidden  rounded-lg shadow-lg relative bg-gradient-to-r from-yellow-500 to-pink-500 p-6 text-white flex items-end justify-between">
			<div class="font-semibold">
				<h6 class="text-sm uppercase">Revenue</h6>
				<h3 class="mt-2 font-bold text-2xl">$ 5,50,489.00</h3>
				<div class="mt-2 flex items-center space-x-1">
					<h6 class=" text-sm ">$ 50,000.00</h6>
					<svg
						xmlns="http://www.w3.org/2000/svg"
						class="h-4 w-4"
						viewBox="0 0 20 20"
						fill="currentColor">
						<path
							fill-rule="evenodd"
							d="M5.293 9.707a1 1 0 010-1.414l4-4a1 1 0 011.414 0l4 4a1 1 0 01-1.414 1.414L11 7.414V15a1 1 0 11-2 0V7.414L6.707 9.707a1 1 0 01-1.414 0z"
							clip-rule="evenodd"></path>
					</svg>
				</div>
			</div>

			<div class="absolute right-0 bottom-0 -m-5 lg:-m-7 overflow-hidden">
				<img src="/landing/wallet-white.png" alt="" class="h-28 w-28 lg:h-32 lg:w-32 opacity-50" />
			</div>
		</div>

		<div
			class="md:w-1/2 overflow-hidden rounded-lg shadow-lg relative bg-gradient-to-r from-purple-500 to-blue-500 p-6 text-white flex items-end justify-between">
			<div class="font-semibold">
				<h6 class="text-sm uppercase">invoices pending</h6>
				<h3 class="mt-2 font-bold text-2xl">$ 50,000.00</h3>
				<h6 class="mt-2 text-sm ">$ 5,000.00 From Last Month</h6>
			</div>

			<div class="absolute right-0 bottom-0 -m-5 lg:-m-7 overflow-hidden">
				<img src="/landing/invoice-white.png" alt="" class="h-28 w-28 lg:h-32 lg:w-32 opacity-50" />
			</div>
		</div>
	</div>

	<div
		class="mt-4 md:mt-8 md:flex md:items-center md:justify-between space-y-4 md:space-y-0 md:space-x-8">
		<div
			class="md:w-1/2 overflow-hidden rounded-lg shadow-lg relative bg-gradient-to-r from-green-500 to-indigo-500 p-6 text-white flex items-end justify-between">
			<div class="font-semibold">
				<h6 class="text-sm uppercase">customers</h6>
				<h3 class="mt-2 font-bold text-2xl">4356</h3>
				<div class="mt-2 flex items-center space-x-10">
					<div class="flex items-center space-x-1">
						<h6 class=" text-sm ">56 New</h6>
						<svg
							xmlns="http://www.w3.org/2000/svg"
							class="h-4 w-4"
							viewBox="0 0 20 20"
							fill="currentColor">
							<path
								fill-rule="evenodd"
								d="M5.293 9.707a1 1 0 010-1.414l4-4a1 1 0 011.414 0l4 4a1 1 0 01-1.414 1.414L11 7.414V15a1 1 0 11-2 0V7.414L6.707 9.707a1 1 0 01-1.414 0z"
								clip-rule="evenodd"></path>
						</svg>
					</div>

					<div class="flex items-center space-x-1">
						<h6 class=" text-sm ">4300 Old</h6>
						<svg
							xmlns="http://www.w3.org/2000/svg"
							class="h-4 w-4"
							viewBox="0 0 20 20"
							fill="currentColor">
							<path
								fill-rule="evenodd"
								d="M5.293 9.707a1 1 0 010-1.414l4-4a1 1 0 011.414 0l4 4a1 1 0 01-1.414 1.414L11 7.414V15a1 1 0 11-2 0V7.414L6.707 9.707a1 1 0 01-1.414 0z"
								clip-rule="evenodd"></path>
						</svg>
					</div>
				</div>
			</div>

			<div class="absolute right-0 bottom-0 -m-5 lg:-m-7 overflow-hidden">
				<img src="/landing/team-white.png" alt="" class="h-28 w-28 lg:h-32 lg:w-32 opacity-50" />
			</div>
		</div>

		<div
			class="md:w-1/2 overflow-hidden rounded-lg shadow-lg relative bg-gradient-to-r from-pink-500 to-purple-500 p-6 text-white flex items-end justify-between">
			<div class="font-semibold">
				<h6 class="text-sm uppercase">rating & reviews</h6>
				<h3 class="mt-2 font-bold text-2xl">4.5 / 400</h3>
				<div class="mt-2 flex items-center space-x-10">
					<div class="flex items-center space-x-1">
						<h6 class=" text-sm ">0.9</h6>
						<svg
							xmlns="http://www.w3.org/2000/svg"
							class="h-4 w-4"
							viewBox="0 0 20 20"
							fill="currentColor">
							<path
								fill-rule="evenodd"
								d="M5.293 9.707a1 1 0 010-1.414l4-4a1 1 0 011.414 0l4 4a1 1 0 01-1.414 1.414L11 7.414V15a1 1 0 11-2 0V7.414L6.707 9.707a1 1 0 01-1.414 0z"
								clip-rule="evenodd"></path>
						</svg>
					</div>

					<div class="flex items-center space-x-1">
						<h6 class=" text-sm ">20</h6>
						<svg
							xmlns="http://www.w3.org/2000/svg"
							class="h-4 w-4"
							viewBox="0 0 20 20"
							fill="currentColor">
							<path
								fill-rule="evenodd"
								d="M5.293 9.707a1 1 0 010-1.414l4-4a1 1 0 011.414 0l4 4a1 1 0 01-1.414 1.414L11 7.414V15a1 1 0 11-2 0V7.414L6.707 9.707a1 1 0 01-1.414 0z"
								clip-rule="evenodd"></path>
						</svg>
					</div>
				</div>
			</div>

			<div class="absolute right-0 bottom-0 -m-5 lg:-m-7 overflow-hidden">
				<img
					src="/landing/rating-circled-white.png"
					alt=""
					class="h-28 w-28 lg:h-32 lg:w-32 opacity-50" />
			</div>
		</div>
	</div>

	<div
		class="mt-4 md:mt-11 md:flex md:items-center md:justify-between space-y-4 md:space-y-0 md:space-x-8">
		<div class="bg-white border rounded-lg shadow-lg h-36 lg:h-48 xl:h-56 2xl:h-60 md:w-1/2"></div>
		<div class="bg-white border rounded-lg shadow-lg h-36 lg:h-48 xl:h-56 2xl:h-60 md:w-1/2"></div>
	</div>
</section>
