<script>
  import CardHeader from    '$lib/components/card/cardHeader.svelte'
  import CardFooter from    '$lib/components/card/cardFooter.svelte'
  import CoursePicker from  '$lib/components/coursePicker/coursePicker.svelte';

  const courses = [
    {
      name: "Medicina - Diurno - UFSC/Florianópolis", 
      id: 1
    },
    {
      name: "Computação aaa", 
      id: 2
    },
    {
      name: "Biologia", 
      id: 3
    }
  ]
</script>

<article class="bg-white p-6 rounded-lg shadow border border-slate-300 flex flex-col gap-6">
  <CardHeader>Informações da Prova</CardHeader>
  <form>
    <CoursePicker {courses}/>
    <!-- testPicker -->
    <!-- colorPicker -->
  </form>
  <CardFooter>As informações aqui informadas são completamente anônimas</CardFooter>
</article>
