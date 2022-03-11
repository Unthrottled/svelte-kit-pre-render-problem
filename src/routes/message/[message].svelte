<script lang="ts">
	import { page } from '$app/stores';

	const message = $page.params.message;
</script>

<div>
  <h1>{message}</h1>
</div>