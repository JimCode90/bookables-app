<template>
    <div>
        <bookable-list-item item-title="Book1" item-content="Contenido de book1" :price="100"></bookable-list-item>
        <bookable-list-item item-title="Book2" item-content="Contenido de book2" :price="500"></bookable-list-item>

    </div>
</template>

<script>
import BookableListItem from "./BookableListItem";
export default {
    components: {
        BookableListItem
    }
}
</script>

<style scoped>

</style>
