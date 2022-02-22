<script>
import NavBar from "./components/NavBar.svelte";

import ProjectCard from "./components/ProjectCard.svelte";

</script>

<main>
	<div class="w-11/12 mx-auto pb-10">
		<NavBar/>
	</div>
	<div class="flex flex-col items-center w-10/12 mx-auto">
		<ProjectCard/>
	</div>
	<footer class="bg-black w-screen fixed bottom-0 text-white" >
		made with love
	</footer> 
</main>

<style global lang="postcss">
	@tailwind base;
	@tailwind components;
	@tailwind utilities;
</style>