<template>
	<div
		className="dark:bg-black dark:text-white duration-1000 overflow-y-auto relative h-screen flex flex-col"
	>
		<div class="container mx-auto bg-gray-500 h-screen">
			<div className="container mx-auto relative h-full flex-1">
				<div class="h-full mt-5">
					<slot />
				</div>
			</div>
		</div>
	</div>
</template>
