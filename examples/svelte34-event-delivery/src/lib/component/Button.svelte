<script lang="ts">
  //import { createEventDispatcher } from 'svelte'

  //const dispatch = createEventDispatcher()

  //function sayHello() {
  //  dispatch('click', {
  //    text: 'こんにちは!'
  //  })
  //}
  export let sayHello: (text: string) => void
</script>

<button on:click={() => sayHello('こんにちは!')}>
  クリック
</button>
