<script>
  import { Tabs, Tab } from "carbon-components-svelte";

  export let selected;
</script>

<Tabs bind:selected>
  <Tab label="Video" />
  <Tab label="Series" />
  <Tab label="Design" />
  <Tab label="Card" />
</Tabs>
