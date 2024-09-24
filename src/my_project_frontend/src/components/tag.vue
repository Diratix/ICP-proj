<script>
export default {
    props: [
        'tagName'
    ]
}
</script>

<template>
    <main>
        <div class="tag">
            {{ tagName }}
        </div>
    </main>
</template>