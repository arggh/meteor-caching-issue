<script>
  import Comp from './Comp.svelte';

  const item = {
    title: 'Foobar',
    description: 'Lorem ipsum',
    answer: 42
  };
</script>

<div>
  <Comp {...item}/>
</div>