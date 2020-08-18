<script>
  import { Router } from "@sveltech/routify";
  import { routes } from "../.routify/routes";
</script>

<style global>
  @import "../static/global.css";
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
</style>

<Router {routes} />
