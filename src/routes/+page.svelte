<script>
	const peter = 50;
	const rik = 30;
</script>

<div class="h-screen text-white">
	<div class="absolute top-1/3 left-1/2 transform -translate-x-1/2 -translate-y-1/2">
		<h1 class="bg-[rgba(255,255,255,0.3)] uppercase rounded-md p-3 text-4xl font-extralight">
			Money Battle
		</h1>
	</div>
	<div class="grid grid-cols-2 h-full">
		<div class="dark:bg-slate-800 w-full h-full flex justify-end place-items-center">
			<div
				class={`h-16 text-2xl bg-teal-300 text-teal-900 rounded-l-2xl flex items-center justify-center w-[${peter}%]`}
			>
				{peter}%
			</div>
		</div>
		<div class="dark:bg-sky-800 w-full h-full flex place-items-center">
			<div
				class={`h-16 text-2xl text-amber-900 flex items-center justify-center bg-amber-300 rounded-r-2xl w-[${rik}%]`}
			>
				{rik}%
			</div>
		</div>
	</div>
</div>

<style lang="postcss">
</style>
