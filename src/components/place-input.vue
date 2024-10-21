<template>
    <label>
        <span v-text="label"></span>
        <input type="text" :placeholder="placeholder" :class="className"
          ref="input"/>
    </label>
</template>

<script>
import * as PlaceInput from '../components-implementation/place-input';
export default PlaceInput;
</script>
