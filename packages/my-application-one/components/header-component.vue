<template>
    <HeaderComponent class="header-component-override">
        <slot></slot>
    </HeaderComponent>
</template>

<script>
import HeaderComponent from "my-library/components/header-component.vue";

export default {
    components: {
        HeaderComponent,
    },
};
</script>

<style scoped>
.header-component-override {
    color: blue;
}
</style>
