<script>
  import { Meta, Story, Template } from '@storybook/addon-svelte-csf';

  import Button from './Button.svelte';
</script>

<Meta title="Button" component={Button}/>

<Template let:args>
  <Button {...args}></Button>
</Template>

<Story name="Custom label" args={{label: 'Custom'}}/>