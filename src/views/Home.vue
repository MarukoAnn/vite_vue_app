<template>
    <div>你好 {{msg}}</div>
</template> 
<script lang="ts">
import {defineComponent, ref} from 'vue'
export default defineComponent({
    name: 'home',
    setup(){
        const msg = ref<string>('vite');

        return {
            msg
        }
    }
})
</script>  