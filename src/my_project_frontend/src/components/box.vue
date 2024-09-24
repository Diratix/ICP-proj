<script>

    export default {
        props : [
            'nameBox',
            'contentBox'
        ]
    }

</script>

<template>
    <main>
        <fieldset>
            <legend>{{ nameBox }}</legend>
            {{ contentBox }}
        </fieldset>
    </main>
</template>