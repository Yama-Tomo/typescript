<script lang="tsx">
import Vue, { VNode } from 'vue'

export default Vue.extend({
  data () {
    const message: string = 'This is a message'

    return {
      message
    }
  },
  render (): VNode {
    return (
      <div>{this.message} (tsx)</div>
    )
  }
})
</script>
