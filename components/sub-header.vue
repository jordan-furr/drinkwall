<template>
    <div class="sub-header">
        <nav>
            <div class="flex flex-row space-between menu">
                <p>
                    <a :href="`/${title}`" class="menu-item" exact-active-class="active">{{title}}</a>
                </p>
                
                <p>
                    <a href="/" class="menu-item" exact-active-class="active">drink-wall</a>
                </p>
            </div>
        </nav>
    </div>
</template>

<script setup>
    const { title } = defineProps(['title']);
</script>