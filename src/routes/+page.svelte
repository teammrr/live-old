<div class="container h-full mx-auto flex justify-center items-center">
	{#if visible}
	<div class="space-y-10 text-center flex flex-col items-center">
		<div class="anim-title" transition:fly={{ y: 40, duration: 1000 }} >
			<h2 class="h2 font-semibold">Hello there, I'm Team 👋🏻</h2>
		</div>
		
		<div class="anim-buttons" transition:fly={{ y: 40, duration: 1000 }}>
			<div id="Btns" class="flex flex-col space-y-8 sm:flex-row sm:space-y-0 ">
				<a href="https://portfolio.teamrr.live" class="flex mx-4 xs:mx-0 justify-center gap-2 px-4 py-2 font-medium transition duration-200 text-gray-900 bg-white border border-gray-200 rounded-xl hover:bg-gray-100 hover:text-blue-700 focus:z-10 focus:ring-4 focus:outline-none focus:ring-gray-200 focus:text-blue-700 dark:bg-gray-800 dark:text-gray-400 dark:border-gray-600 dark:hover:text-white dark:hover:bg-gray-700 dark:focus:ring-gray-700"><svg class="w-5 h-6 text-gray-800 dark:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="none" viewBox="0 0 20 20">
					<path stroke="currentColor" stroke-linecap="round" stroke-width="2" d="M1 10c1.5 1.5 5.25 3 9 3s7.5-1.5 9-3m-9-1h.01M2 19h16a1 1 0 0 0 1-1V6a1 1 0 0 0-1-1H2a1 1 0 0 0-1 1v12a1 1 0 0 0 1 1ZM14 5V3a2 2 0 0 0-2-2H8a2 2 0 0 0-2 2v2h8Z"/>
				</svg>Portfolio</a>
				<a href="https://github.com/teammrr" class="flex mx-4 xs:mx-0 justify-center gap-2 px-4 py-2 font-medium transition duration-200 text-gray-900 bg-white border border-gray-200 rounded-xl hover:bg-gray-100 hover:text-blue-700 focus:z-10 focus:ring-4 focus:outline-none focus:ring-gray-200 focus:text-blue-700 dark:bg-gray-800 dark:text-gray-400 dark:border-gray-600 dark:hover:text-white dark:hover:bg-gray-700 dark:focus:ring-gray-700"><svg class="w-6 h-6 text-gray-800 dark:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 20 16"><path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 4 1 8l4 4m10-8 4 4-4 4M11 1 9 15"/></svg>Github</a>
				
				<a href="https://hub.teamrr.live" class="flex mx-4 xs:mx-0 justify-center gap-2 px-4 py-2 font-medium transition duration-200 text-gray-900 bg-white border border-gray-200 rounded-xl hover:bg-gray-100 hover:text-blue-700 focus:z-10 focus:ring-4 focus:outline-none focus:ring-gray-200 focus:text-blue-700 dark:bg-gray-800 dark:text-gray-400 dark:border-gray-600 dark:hover:text-white dark:hover:bg-gray-700 dark:focus:ring-gray-700"><svg class="w-6 h-6 text-gray-800 dark:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 19 20">
					<path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M2 9.376v.786l8 3.925 8-3.925v-.786M1.994 14.191v.786l8 3.925 8-3.925v-.786M10 1.422 2 5.347l8 3.925 8-3.925-8-3.925Z"/>
				</svg>
				Hub</a>
				<!-- <a href="https://space.teamrr.live" class="flex mx-4 xs:mx-0 justify-center gap-2 px-4 py-2 font-medium transition duration-200 text-gray-900 bg-white border border-gray-200 rounded-xl hover:bg-gray-100 hover:text-blue-700 focus:z-10 focus:ring-4 focus:outline-none focus:ring-gray-200 focus:text-blue-700 dark:bg-gray-800 dark:text-gray-400 dark:border-gray-600 dark:hover:text-white dark:hover:bg-gray-700 dark:focus:ring-gray-700"><svg class="w-6 h-6 text-gray-800 dark:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 20 18">
					<path d="M19.718 9c0-1.429-1.339-2.681-3.467-3.5.029-.18.077-.37.1-.545.217-2.058-.273-3.543-1.379-4.182-1.235-.714-2.983-.186-4.751 1.239C8.45.589 6.7.061 5.468.773c-1.107.639-1.6 2.124-1.379 4.182.018.175.067.365.095.545C2.057 6.319.718 7.571.718 9c0 1.429 1.339 2.681 3.466 3.5-.028.18-.077.37-.095.545-.218 2.058.272 3.543 1.379 4.182.376.213.803.322 1.235.316a5.987 5.987 0 0 0 3.514-1.56 5.992 5.992 0 0 0 3.515 1.56 2.44 2.44 0 0 0 1.236-.316c1.106-.639 1.6-2.124 1.379-4.182-.019-.175-.067-.365-.1-.545 2.132-.819 3.471-2.071 3.471-3.5Zm-6.01-7.548a1.5 1.5 0 0 1 .76.187c.733.424 1.055 1.593.884 3.212-.012.106-.043.222-.058.33-.841-.243-1.7-.418-2.57-.523a16.165 16.165 0 0 0-1.747-1.972 4.9 4.9 0 0 1 2.731-1.234Zm-7.917 8.781c.172.34.335.68.529 1.017.194.337.395.656.6.969a14.09 14.09 0 0 1-1.607-.376 14.38 14.38 0 0 1 .478-1.61Zm-.479-4.076a14.085 14.085 0 0 1 1.607-.376c-.205.313-.405.634-.6.969-.195.335-.357.677-.529 1.017-.19-.527-.35-1.064-.478-1.61ZM6.3 9c.266-.598.563-1.182.888-1.75.33-.568.69-1.118 1.076-1.65.619-.061 1.27-.1 1.954-.1.684 0 1.333.035 1.952.1a19.63 19.63 0 0 1 1.079 1.654A19.3 19.3 0 0 1 14.136 9a18.869 18.869 0 0 1-1.953 3.403 19.218 19.218 0 0 1-3.931 0 20.163 20.163 0 0 1-1.066-1.653A19.33 19.33 0 0 1 6.3 9Zm7.816 2.25c.2-.337.358-.677.53-1.017.191.527.35 1.065.478 1.611a14.48 14.48 0 0 1-1.607.376c.202-.314.404-.635.597-.97h.002Zm.53-3.483c-.172-.34-.335-.68-.53-1.017a20.214 20.214 0 0 0-.6-.97c.542.095 1.078.22 1.606.376a14.113 14.113 0 0 1-.478 1.611h.002ZM10.217 3.34c.4.375.777.773 1.13 1.193-.37-.02-.746-.033-1.129-.033s-.76.013-1.131.033c.353-.42.73-.817 1.13-1.193Zm-4.249-1.7a1.5 1.5 0 0 1 .76-.187 4.9 4.9 0 0 1 2.729 1.233A16.25 16.25 0 0 0 7.71 4.658c-.87.105-1.728.28-2.569.524-.015-.109-.047-.225-.058-.331-.171-1.619.151-2.787.885-3.211ZM1.718 9c0-.9.974-1.83 2.645-2.506.218.857.504 1.695.856 2.506-.352.811-.638 1.65-.856 2.506C2.692 10.83 1.718 9.9 1.718 9Zm4.25 7.361c-.734-.423-1.056-1.593-.885-3.212.011-.106.043-.222.058-.331.84.243 1.697.418 2.564.524a16.37 16.37 0 0 0 1.757 1.982c-1.421 1.109-2.714 1.488-3.494 1.037Zm3.11-2.895c.374.021.753.034 1.14.034.387 0 .765-.013 1.139-.034a14.4 14.4 0 0 1-1.14 1.215 14.232 14.232 0 0 1-1.139-1.215Zm5.39 2.895c-.782.451-2.075.072-3.5-1.038a16.248 16.248 0 0 0 1.757-1.981 16.41 16.41 0 0 0 2.565-.523c.015.108.046.224.058.33.175 1.619-.148 2.789-.88 3.212Zm1.6-4.854A16.562 16.562 0 0 0 15.216 9c.352-.811.638-1.65.856-2.507C17.743 7.17 18.718 8.1 18.718 9c0 .9-.975 1.83-2.646 2.507h-.004Z"/>
					<path d="M10.215 10.773a1.792 1.792 0 1 0-1.786-1.8v.006a1.788 1.788 0 0 0 1.786 1.794Z"/>
				</svg>Space</a> -->
			</div>
		</div>
	</div>
	{/if}
</div>

<style lang="postcss">	
	
	
	/* #glowbtn {
		@apply absolute z-[-1] rounded-full blur-[50px] transition-all;
		animation: pulse 5s cubic-bezier(0, 0, 0, 0.5) infinite,
		glow 5s linear infinite;
	}
	.h3 {
		@apply absolute z-[-1] rounded-full blur-[50px] transition-all;
		animation: pulse 5s cubic-bezier(0, 0, 0, 0.5) infinite,
		glow 5s linear infinite;
	} */
	
	/* @keyframes glow {
		0% {
			@apply bg-primary-400/50;
		}
		33% {
			@apply bg-secondary-400/50;
		}
		66% {
			@apply bg-tertiary-400/50;
		}
		100% {
			@apply bg-primary-400/50;
		}
	}
	@keyframes pulse {
		50% {
			transform: scale(6);
		}
	} */
</style>

<script>
	import { onMount } from 'svelte';
	import { fly } from 'svelte/transition'
	
	let visible = false
	onMount(() =>{
		visible = true
	})
</script>
