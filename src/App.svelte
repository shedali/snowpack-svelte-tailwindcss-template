<script>
import {types as t} from 'https://cdn.pika.dev/mobx-state-tree@^3.15.0';

	const TestModel = t.model({
		name: t.string
	})

	const m = TestModel.create({
		name: "test"
	})
</script>

<svelte:head>
	<link rel="stylesheet" href="output.css">
</svelte:head>

<p class="text-3xl border">
	nice one mate {m.name}
</p>



