<template>
  <div class="tasks">
    <article class="task">
      <input type="checkbox" class="task__checkbox" />
      <div class="task__details">
        <h1 class="task__title">Meditation</h1>
        <div class="task__days">
          <span class="day">Mon</span>
          <span class="day">Tue</span>
          <span class="day">Wed</span>
          <span class="day">Thu</span>
          <span class="day">Fri</span>
          <span class="day">Sat</span>
          <span class="day">Sun</span>
        </div>
      </div>
      <div class="task__link">></div>
    </article>
  </div>
</template>

<script type="ts">
export default {

}
</script>

<style scoped>
.tasks {
  margin: 10rem;
}

.task {
  display: flex;
  /* justify-content: center; */
  align-items: center;
  gap: var(--size-5);
  background: var(--gray-8);
  padding: var(--size-5);
  border-radius: var(--radius-3);
  width: var(--size-15);
}

.task__checkbox {
  transform: scale(1.5);
  /* margin: var(--size-3); */
}

.task__details {
  flex-grow: 1;
}

.task__title {
  font-size: var(--font-size-4);
}

.task__days {
  display: flex;
  /* flex-direction: column; */
  gap: var(--size-2);
}
</style>
