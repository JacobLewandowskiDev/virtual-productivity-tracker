<script scoped>

</script>

<template>
    <label class="label">Subtasks</label>
    <br>
    <div class="subtasklist">
        <div class="subtasklist__subtask">
            <input class="subtasklist__subtask__input" type="text" placeholder="Name">
            <br>
            <input class="subtasklist__subtask__input" type="text" placeholder="Description">
            <button class="subtasklist__subtask__delete" @click="handleDeleteStep()">Delete Subtask</button>
            <br class="form__break">
        </div>

        <div class="subtasklist__subtask">
            <input class="subtasklist__subtask__input" type="text" placeholder="Name">
            <br>
            <input class="subtasklist__subtask__input" type="text" placeholder="Description">
            <button class="subtasklist__subtask__delete" @click="handleDeleteStep()">Delete Subtask</button>
            <br class="form__break">
        </div>

        <div class="subtasklist__subtask">
            <input class="subtasklist__subtask__input" type="text" placeholder="Name">
            <br>
            <input class="subtasklist__subtask__input" type="text" placeholder="Description">
            <button class="subtasklist__subtask__delete" @click="handleDeleteStep()">Delete Subtask</button>
            <br class="form__break">
        </div>
        
    </div>
    <hr class="form__line">
</template>

<style scoped>
.subtasklist {
    height: 30rem;
    overflow: hidden;
    overflow-y: scroll;
}

.subtasklist__subtask__delete {
    width: 100%;
}
</style>