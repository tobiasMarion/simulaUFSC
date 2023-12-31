<script>
  import Label from "$lib/components/label/label.svelte";

  export let courses;

  let selectedCourseId;
</script>

<div>
  <Label forElement="course" >Qual é a sua primeira opção de curso?</Label>

  <select
    class="border border-slate-400 p-2 w-full rounded cursor-pointer  text-slate-500 bg-transparent"
    id="course"
    bind:value={selectedCourseId}
  >
    {#each courses as course (course.id)}
      <option value={course.id}>{course.name}</option>
    {/each}
  </select>
</div>
