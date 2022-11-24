<script lang="ts">
	import Card from './index.svelte';
	import { Meta, Template, Story } from '@storybook/addon-svelte-csf';
</script>

<Meta title="Card" component={Card} />

<Template let:args>
	<Card {...args} />
</Template>

<Story
	name="Primary"
	args={{ title: 'Here is a Title', content: 'Boom... more content to follow' }}
/>
