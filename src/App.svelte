<script>
  export let name;

  //IMPORT HERE
  import Input from "./components/Input.svelte";
</script>

<main class="container">
  <!--Components Here-->
  <div class="uk-child-width-1-1@s uk-margin-large-top uk-grid-match" uk-grid>
    <div>
      <div
        class="uk-card uk-card-primary uk-card-large uk-card-body uk-margin-left uk-margin-right"
      >
        <h3 class="uk-card-title uk-text-center uk-text-secondary">
          Staffbase Svelte Widget
        </h3>
        <div class="uk-text-center">
          <!--Components Insert Here-->
          <Input />
        </div>
      </div>
    </div>
  </div>
</main>

<style>
</style>
