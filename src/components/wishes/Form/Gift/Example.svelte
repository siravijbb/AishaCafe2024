<script lang="ts">
	import { onMount } from 'svelte';

	export let imgURL = '';
	export let bwish = {
		name: 'Name',
		comment: 'Comment',
		DMY: 'DMY',
		time: 'Time',
		count: 'Count'
	};
	export let selected: number;
	export let SidePicture: number;

	export let SmallDolls = '#FF0000';
</script>

<div class="mt-4">
	{#if selected == 1}
		<div class="mx-auto grid grid-cols-1">
			<div
				class="relative flex h-full min-h-48 w-full max-w-[349.333px] justify-self-center overflow-hidden rounded-none bg-aisha p-2 text-black/50 md:min-h-72"
				id="one"
			>
				<div class="h-full w-full bg-white">
					<div class="absolute left-0 top-0 flex w-full flex-col px-4 py-2 pb-11">
						<div class="flex">
							{#if SidePicture == 1}
								<img
									class="z-10 -ml-6 -mt-5 h-20 object-contain"
									src="/Wish/Guppiens/1.png"
									alt="count"
								/>
							{:else if SidePicture == 2}
								<img
									class="z-10 -ml-6 -mt-5 h-20 object-contain"
									src="/Wish/Guppiens/2.png"
									alt="count"
								/>
							{:else if SidePicture == 3}
								<img
									class="z-10 -ml-6 -mt-5 h-20 object-contain"
									src="/Wish/Guppiens/3.png"
									alt="count"
								/>
							{:else if SidePicture == 4}
								<img
									class="z-10 -ml-6 -mt-5 h-20 object-contain"
									src="/Wish/Guppiens/4.png"
									alt="count"
								/>
							{:else if SidePicture == 5}
								<img
									class="z-10 -ml-6 -mt-5 h-20 object-contain"
									src="/Wish/Guppiens/5.png"
									alt="count"
								/>
							{:else if SidePicture == 6}
								<img
									class="z-10 -ml-6 -mt-5 h-20 object-contain"
									src="/Wish/Guppiens/6.png"
									alt="count"
								/>
							{/if}
						</div>
					</div>
					<div class="relative flex h-full flex-1 flex-col px-4 py-12 pb-16">
						<span
							class="my-auto justify-center whitespace-pre-line text-wrap break-normal break-words text-center text-[#4E4670] sm:text-xl"
							>{bwish.comment}
						</span>
						<div class="flex w-full px-2 pt-4 text-sm min-[425px]:px-4 min-[425px]:text-base" />
					</div>

					<div
						class=" absolute -bottom-4 right-10 z-[1] translate-x-[50%] -rotate-12 scale-[70%] min-[425px]:bottom-0 min-[425px]:right-14 min-[425px]:scale-100"
					>
						{#if SidePicture == 1}
							<img class="-mb-11 w-40 rotate-12" src="/Wish/Guppiens/1.png" alt="count" />
						{:else if SidePicture == 2}
							<img class="-mb-11 w-40 rotate-12" src="/Wish/Guppiens/2.png" alt="count" />
						{:else if SidePicture == 3}
							<img class="-mb-11 w-40 rotate-12" src="/Wish/Guppiens/3.png" alt="count" />
						{:else if SidePicture == 4}
							<img class="-mb-11 w-40 rotate-12" src="/Wish/Guppiens/4.png" alt="count" />
						{:else if SidePicture == 5}
							<img class="-mb-11 w-40 rotate-12" src="/Wish/Guppiens/5.png" alt="count" />
						{:else if SidePicture == 6}
							<img class="-mb-11 w-40 rotate-12" src="/Wish/Guppiens/6.png" alt="count" />
						{/if}
					</div>

					<div class="absolute bottom-1 left-4 text-base text-[#4E4670]">
						<p><b>{bwish.name} #{bwish.count} </b></p>
						<p>{bwish.DMY} {bwish.time}</p>
					</div>
				</div>
			</div>
		</div>
	{:else if selected == 2}
		<div class="mx-auto grid grid-cols-1">
			<div
				class="relative flex h-full min-h-48 w-full max-w-[349.333px] justify-self-center overflow-hidden rounded-none bg-[#163283] p-2 text-black/50 md:min-h-72"
				id="one"
			>
				<div class="h-full w-full bg-white">
					<div class="absolute left-0 top-0 flex w-full flex-col px-4 py-2 pb-11">
						<div class="flex">
							{#if SidePicture == 1}
								<img
									class="z-10 -ml-6 -mt-5 h-20 object-contain"
									src="/Wish/Guppiens/1.png"
									alt="count"
								/>
							{:else if SidePicture == 2}
								<img
									class="z-10 -ml-6 -mt-5 h-20 object-contain"
									src="/Wish/Guppiens/2.png"
									alt="count"
								/>
							{:else if SidePicture == 3}
								<img
									class="z-10 -ml-6 -mt-5 h-20 object-contain"
									src="/Wish/Guppiens/3.png"
									alt="count"
								/>
							{:else if SidePicture == 4}
								<img
									class="z-10 -ml-6 -mt-5 h-20 object-contain"
									src="/Wish/Guppiens/4.png"
									alt="count"
								/>
							{:else if SidePicture == 5}
								<img
									class="z-10 -ml-6 -mt-5 h-20 object-contain"
									src="/Wish/Guppiens/5.png"
									alt="count"
								/>
							{:else if SidePicture == 6}
								<img
									class="z-10 -ml-6 -mt-5 h-20 object-contain"
									src="/Wish/Guppiens/6.png"
									alt="count"
								/>
							{/if}
						</div>
					</div>
					<div class="relative flex h-full flex-1 flex-col px-4 py-12 pb-16">
						<span
							class="my-auto justify-center whitespace-pre-line text-wrap break-normal break-words text-center text-[#4E4670] sm:text-xl"
							>{bwish.comment}</span
						>
						<div class="flex w-full px-2 pt-4 text-sm min-[425px]:px-4 min-[425px]:text-base" />
					</div>

					<div
						class=" absolute -bottom-4 right-10 z-[1] translate-x-[50%] -rotate-12 scale-[70%] min-[425px]:bottom-0 min-[425px]:right-14 min-[425px]:scale-100"
					>
						{#if SidePicture == 1}
							<img class="-mb-11 w-40 rotate-12" src="/Wish/Guppiens/1.png" alt="count" />
						{:else if SidePicture == 2}
							<img class="-mb-11 w-40 rotate-12" src="/Wish/Guppiens/2.png" alt="count" />
						{:else if SidePicture == 3}
							<img class="-mb-11 w-40 rotate-12" src="/Wish/Guppiens/3.png" alt="count" />
						{:else if SidePicture == 4}
							<img class="-mb-11 w-40 rotate-12" src="/Wish/Guppiens/4.png" alt="count" />
						{:else if SidePicture == 5}
							<img class="-mb-11 w-40 rotate-12" src="/Wish/Guppiens/5.png" alt="count" />
						{:else if SidePicture == 6}
							<img class="-mb-11 w-40 rotate-12" src="/Wish/Guppiens/6.png" alt="count" />
						{/if}
					</div>

					<div class="absolute bottom-1 left-4 text-base text-[#4E4670]">
						<p><b>{bwish.name} #{bwish.count}</b></p>
						<p>{bwish.DMY} {bwish.time}</p>
					</div>
				</div>
			</div>
		</div>
	{:else if selected == 3}
		<div class="mx-auto grid grid-cols-1">
			<div
				class="relative flex h-full min-h-48 w-full max-w-[349.333px] justify-self-center overflow-hidden rounded-none bg-[#EB96C2] p-2 text-black/50 md:min-h-72"
				id="one"
			>
				<div class="h-full w-full bg-white">
					<div class="absolute left-0 top-0 flex w-full flex-col px-4 py-2 pb-11">
						<div class="flex">
							{#if SidePicture == 1}
								<img
									class="z-10 -ml-6 -mt-5 h-20 object-contain"
									src="/Wish/Guppiens/1.png"
									alt="count"
								/>
							{:else if SidePicture == 2}
								<img
									class="z-10 -ml-6 -mt-5 h-20 object-contain"
									src="/Wish/Guppiens/2.png"
									alt="count"
								/>
							{:else if SidePicture == 3}
								<img
									class="z-10 -ml-6 -mt-5 h-20 object-contain"
									src="/Wish/Guppiens/3.png"
									alt="count"
								/>
							{:else if SidePicture == 4}
								<img
									class="z-10 -ml-6 -mt-5 h-20 object-contain"
									src="/Wish/Guppiens/4.png"
									alt="count"
								/>
							{:else if SidePicture == 5}
								<img
									class="z-10 -ml-6 -mt-5 h-20 object-contain"
									src="/Wish/Guppiens/5.png"
									alt="count"
								/>
							{:else if SidePicture == 6}
								<img
									class="z-10 -ml-6 -mt-5 h-20 object-contain"
									src="/Wish/Guppiens/6.png"
									alt="count"
								/>
							{/if}
						</div>
					</div>
					<div class="relative flex h-full flex-1 flex-col px-4 py-12 pb-16">
						<span
							class="my-auto justify-center whitespace-pre-line text-wrap break-normal break-words text-center text-[#4E4670] sm:text-xl"
							>{bwish.comment}</span
						>
						<div class="flex w-full px-2 pt-4 text-sm min-[425px]:px-4 min-[425px]:text-base" />
					</div>

					<div
						class=" absolute -bottom-4 right-10 z-[1] translate-x-[50%] -rotate-12 scale-[70%] min-[425px]:bottom-0 min-[425px]:right-14 min-[425px]:scale-100"
					>
						{#if SidePicture == 1}
							<img class="-mb-11 w-40 rotate-12" src="/Wish/Guppiens/1.png" alt="count" />
						{:else if SidePicture == 2}
							<img class="-mb-11 w-40 rotate-12" src="/Wish/Guppiens/2.png" alt="count" />
						{:else if SidePicture == 3}
							<img class="-mb-11 w-40 rotate-12" src="/Wish/Guppiens/3.png" alt="count" />
						{:else if SidePicture == 4}
							<img class="-mb-11 w-40 rotate-12" src="/Wish/Guppiens/4.png" alt="count" />
						{:else if SidePicture == 5}
							<img class="-mb-11 w-40 rotate-12" src="/Wish/Guppiens/5.png" alt="count" />
						{:else if SidePicture == 6}
							<img class="-mb-11 w-40 rotate-12" src="/Wish/Guppiens/6.png" alt="count" />
						{/if}
					</div>

					<div class="absolute bottom-1 left-4 text-base text-[#4E4670]">
						<p><b>{bwish.name} #{bwish.count}</b></p>
						<p>{bwish.DMY} {bwish.time}</p>
					</div>
				</div>
			</div>
		</div>
	{:else if selected == 4}
		<div class="mx-auto grid grid-cols-1">
			<div
				class="relative flex h-full min-h-48 w-full max-w-[349.333px] justify-self-center overflow-hidden rounded-none bg-[#ffbc76] p-2 text-black/50 md:min-h-72"
				id="one"
			>
				<div class="h-full w-full bg-white">
					<div class="absolute left-0 top-0 flex w-full flex-col px-4 py-2 pb-11">
						<div class="flex">
							{#if SidePicture == 1}
								<img
									class="z-10 -ml-6 -mt-5 h-20 object-contain"
									src="/Wish/Guppiens/1.png"
									alt="count"
								/>
							{:else if SidePicture == 2}
								<img
									class="z-10 -ml-6 -mt-5 h-20 object-contain"
									src="/Wish/Guppiens/2.png"
									alt="count"
								/>
							{:else if SidePicture == 3}
								<img
									class="z-10 -ml-6 -mt-5 h-20 object-contain"
									src="/Wish/Guppiens/3.png"
									alt="count"
								/>
							{:else if SidePicture == 4}
								<img
									class="z-10 -ml-6 -mt-5 h-20 object-contain"
									src="/Wish/Guppiens/4.png"
									alt="count"
								/>
							{:else if SidePicture == 5}
								<img
									class="z-10 -ml-6 -mt-5 h-20 object-contain"
									src="/Wish/Guppiens/5.png"
									alt="count"
								/>
							{:else if SidePicture == 6}
								<img
									class="z-10 -ml-6 -mt-5 h-20 object-contain"
									src="/Wish/Guppiens/6.png"
									alt="count"
								/>
							{/if}
						</div>
					</div>
					<div class="relative flex h-full flex-1 flex-col px-4 py-12 pb-16">
						<span
							class="my-auto justify-center whitespace-pre-line text-wrap break-normal break-words text-center text-[#4E4670] sm:text-xl"
							>{bwish.comment}</span
						>
						<div class="flex w-full px-2 pt-4 text-sm min-[425px]:px-4 min-[425px]:text-base" />
					</div>

					<div
						class=" absolute -bottom-4 right-10 z-[1] translate-x-[50%] -rotate-12 scale-[70%] min-[425px]:bottom-0 min-[425px]:right-14 min-[425px]:scale-100"
					>
						{#if SidePicture == 1}
							<img class="-mb-11 w-40 rotate-12" src="/Wish/Guppiens/1.png" alt="count" />
						{:else if SidePicture == 2}
							<img class="-mb-11 w-40 rotate-12" src="/Wish/Guppiens/2.png" alt="count" />
						{:else if SidePicture == 3}
							<img class="-mb-11 w-40 rotate-12" src="/Wish/Guppiens/3.png" alt="count" />
						{:else if SidePicture == 4}
							<img class="-mb-11 w-40 rotate-12" src="/Wish/Guppiens/4.png" alt="count" />
						{:else if SidePicture == 5}
							<img class="-mb-11 w-40 rotate-12" src="/Wish/Guppiens/5.png" alt="count" />
						{:else if SidePicture == 6}
							<img class="-mb-11 w-40 rotate-12" src="/Wish/Guppiens/6.png" alt="count" />
						{/if}
					</div>

					<div class="absolute bottom-1 left-4 text-base text-[#4E4670]">
						<p><b>{bwish.name} #{bwish.count}</b></p>
						<p>{bwish.DMY} {bwish.time}</p>
					</div>
				</div>
			</div>
		</div>
	{/if}
</div>
