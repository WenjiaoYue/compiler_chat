<script>
	let includeList = [
		{ content: "Compiler Introduction" },
		{ content: "Compiler Setup" },
		{ content: "Compiler Reference" },
		{ content: "Compilation" },
		{ content: "Optimization" },
		{ content: "Compatibility and Portability" },
	];
</script>

<div class="flex flex-col flex-wrap sm:flex-row h-full">
	<div class="relative mx-auto  max-w-screen-xl h-full">
		<div
			class="pricing-box mx-auto max-w-lg overflow-hidden rounded-t-lg shadow lg:flex lg:max-w-none h-full"
		>
			<div class="lg:flex-shrink-1 bg-white px-12 py-[3rem]">
				<p
					class="font-extrabold leading-8 text-gray-900 text-[1.7rem] pb-8"
				>
					Intel® oneAPI DPC++/C++ Compiler Developer Guide
			</p>
				<p class="text-[1rem] leading-6 text-gray-500">
					This AI Agent provides information about the Intel® oneAPI DPC++/C++
					Compiler and runtime environment. This agent is valid for version
					2024.0 of the compilers.
				</p>
				<div class="mt-8">
					<div class="flex items-center">
						<h4
							class="flex-shrink-0 bg-white pr-4 text-sm font-semibold uppercase leading-5 tracking-wider text-indigo-600"
						>
							What&#x27;s included
						</h4>
						<div class="flex-1 border-t-2 border-gray-200" />
					</div>
					<ul class="lg:col-gap-8 lg:row-gap-5 mt-8 lg:grid lg:grid-cols-2">
						{#each includeList as { content }}
							<li class="flex items-start lg:col-span-1">
								<div class="flex-shrink-0">
									<svg
										class="mr-2 h-6 w-6"
										xmlns="http://www.w3.org/2000/svg"
										width="6"
										height="6"
										stroke="currentColor"
										fill="#10b981"
										viewBox="0 0 1792 1792"
									>
										<path
											d="M1412 734q0-28-18-46l-91-90q-19-19-45-19t-45 19l-408 407-226-226q-19-19-45-19t-45 19l-91 90q-18 18-18 46 0 27 18 45l362 362q19 19 45 19 27 0 46-19l543-543q18-18 18-45zm252 162q0 209-103 385.5t-279.5 279.5-385.5 103-385.5-103-279.5-279.5-103-385.5 103-385.5 279.5-279.5 385.5-103 385.5 103 279.5 279.5 103 385.5z"
										/>
									</svg>
								</div>
								<p class="ml-3 text-sm leading-5 text-gray-700">
									{content}
								</p>
							</li>
						{/each}
					</ul>
				</div>
			</div>
			<div
				class="bg-white px-6 py-8 text-center lg:flex lg:flex-shrink-0 lg:flex-col lg:justify-center lg:p-12"
			>
				<div
					class="mt-4 flex items-center justify-center text-3xl font-extrabold leading-none text-gray-900"
				>
					<span>Get Help </span>
				</div>
				<p class="mt-4 text-sm leading-5">
					<span class=" inline-block font-medium text-gray-500">
						Please visit the Official Website for more resource.
					</span>
				</p>
				<div class="mt-6">
					<div class="rounded-md shadow">
						<a
							href="https://www.intel.com/content/www/us/en/developer/get-help/priority-support.html"
							target="_blank"
						>
							<button
								type="button"
								class="w-full rounded-lg bg-indigo-600 px-4 py-2 text-center text-base font-semibold text-white shadow-md transition duration-200 ease-in hover:bg-indigo-700 focus:outline-none focus:ring-2 focus:ring-indigo-500 focus:ring-offset-2 focus:ring-offset-indigo-200"
							>
								More Information
							</button></a
						>
					</div>
				</div>
			</div>
		</div>
		<footer class="absolute bottom-0 m-auto  pb-3 bg-white w-full">
			<div class="">
				<hr class="mb-6 border-gray-200 dark:border-gray-700 sm:mx-auto" />
				<span class="block text-sm text-gray-500 dark:text-gray-400 sm:text-center"
					>© 2023 <a
						href="https://github.com/intel/intel-extension-for-transformers"
						target="_blank"
						class="underline"
						>Powered by NeuralChat from Intel Extension for Transformers</a
					>.
				</span>
			</div>
		</footer>
	</div>
	
</div>


