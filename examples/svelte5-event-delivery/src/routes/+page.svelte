<script lang="ts">
  import Button from '../lib/component/Button.svelte'

  function onmouseover(event) {
    console.log('マウスが乗った！')
  }

  function onmouseout(event) {
    alert('マウスが離れた')
  }
</script>

<Button {onmouseover} {onmouseout} />
