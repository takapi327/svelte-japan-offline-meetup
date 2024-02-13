<script lang="ts">
  import Button from '../lib/component/Button.svelte'

  //function handleMessage(event) {
  //  alert(event.detail.text)
  //}
  function sayHello(text: string) {
    alert(text)
  }
</script>

<Button {sayHello} />
