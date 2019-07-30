<template>
    <div>
        <p>{{ message }}</p>
        <p><input v-model="message"></p>
    </div>
</template>

<script lang="ts">
import {Vue, Component} from 'vue-property-decorator';

@Component({})
export default class CSRNet extends Vue{
    data() {
        return {message: 'Hello Vue!'};
    }
}
</script>
