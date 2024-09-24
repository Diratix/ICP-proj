<script>
    import Tag from './tag.vue';

    export default {
        components: {
            Tag,
        },
        props : [
            'nameBox',
        ],
    };
</script>

<template>
    <main>
        <fieldset>
            <legend>{{ nameBox }}</legend>
            <div class="tags">
                <Tag tagName="React.js" />
                <Tag tagName="React.js" />
                <Tag tagName="React.js" />
                <Tag tagName="React.js" />
                <Tag tagName="React.js" />
                <Tag tagName="React.js" />
                <Tag tagName="React.js" />
                <Tag tagName="React.js" />
                <Tag tagName="React.js" />
                <Tag tagName="React.js" />
                <Tag tagName="React.js" />
                <Tag tagName="React.js" />
                <Tag tagName="React.js" />
                <Tag tagName="React.js" />
                <Tag tagName="React.js" />
            </div>
        </fieldset>
    </main>
</template>