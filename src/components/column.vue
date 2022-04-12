<template lang="pug">
    tr
        td
            span Заголовок 1
            | {{index}}
        td
            span Заголовок 1
            | {{country}}
        td
            span Заголовок 2
            | {{continent}}
        td
            span Заголовок 3
            | {{location}}
        td
            span Заголовок 4
            | {{confirmed}}
        td
            span Заголовок 1
            | {{recovered}}
        td
            span Заголовок 2
            | {{deaths}}
        td
            span Заголовок 3
            | {{life_expectancy}}
        td
            span Заголовок 4
            | {{elevation_in_meters}}

</template>

<script>
    export default {
        name: "column",
        props: {
            country: {
                type: String,
                required: true,
            },
        },
        data() {
            return {
            };
        },
    };
</script>

<style lang="scss">
    @import "../assets/scss/general.scss";


</style>