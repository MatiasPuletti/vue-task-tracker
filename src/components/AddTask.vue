<template>
  <form class="add-from">
    <div class="form-control">
      <label>Task</label>
      <input type="text" name="text" placeholder="Add Task" />
    </div>
    <div class="form-comtrol">
      <label>Day & Time</label>
      <input type="text" name="text" placeholder="Add Day & Time" />
    </div>
    <div class="form-control form-control-check">
      <label>Set Reminder</label>
      <input type="checkbox" name="reminder" />
    </div>
    <input type="submit" value="Save task" class="bt n btn-block" />
  </form>
</template>

<script>
export default {
  name: "AddTask",
};
</script>
