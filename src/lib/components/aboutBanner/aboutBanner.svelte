<script>
    import GithubButton from "../githubButton/githubButton.svelte";

</script>

<section class="px-6 pt-10 pb-24 w-full bg-blue-600 rounded-b-xl flex flex-col gap-4 shadow">
  <GithubButton/>

  <h1 class="font-bold text-4xl text-white">Simulador Vestibular Unificado</h1>

  <ul class="flex gap-2 items-center text-slate-100">
    <li>UFSC</li>
    <span class="block bg-slate-300 w-1 h-1 rounded-full"/>
    <li>IFSC</li>
    <span class="block bg-slate-300 w-1 h-1 rounded-full"/>
    <li>IFC</li>
  </ul>

  <p class="text-slate-300">Lorem ipsum dolor sit amet consectetur. Lobortis non aliquam tellus ipsum augue urna tortor.</p>
</section>