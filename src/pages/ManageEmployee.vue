<template>
  <div class="content">
    <div class="md-layout">
      <md-button class="md-raised md-info" @click="addEmployee()">
        <md-icon>add</md-icon>
        <label>สร้างรายชื่อพนักงาน</label>
      </md-button>
    </div>
    <div class="md-layout" v-show="isOpen">
      <div class="md-layout-item md-medium-size-100">
        <edit-profile-form data-background-color="blue"> </edit-profile-form>
      </div>
    </div>
    <div class="md-layout">
      <div class="md-layout-item md-medium-size-100">
        <employee-table table-header-color="green"></employee-table>
      </div>
    </div>
  </div>
</template>

<script>
import { EditProfileForm } from "@/pages";
import { EmployeeTable } from "@/components";

export default {
  components: {
    EditProfileForm,
    EmployeeTable
  },
data() {
    return {
      isOpen: false
    };
  },
  methods: {
    addEmployee() {
      this.isOpen = !this.isOpen
    }
  }
};
</script>
