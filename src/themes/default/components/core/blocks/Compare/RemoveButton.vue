<template>
  <button
    class="brdr-none bg-cl-transparent p15"
    :aria-label="$t('Remove')"
    :title="$t('Remove')"
  >
    <i class="material-icons h4">close</i>
  </button>
</template>

<script>
import RemoveButton from 'core/components/blocks/Compare/RemoveButton'

export default {
  mixins: [RemoveButton]
}
</script>
