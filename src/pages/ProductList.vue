<template>
  <div class="content">
    <div class="md-layout">
      <div
        class="md-layout-item md-medium-size-100 md-xsmall-size-100 md-size-33"
      >
        <md-card>
          <md-card-media>
            <img src="../assets/img/products/2.jpg" alt="People" />
          </md-card-media>
          <md-card-header>
            <div class="md-title">ลูกชิ้นหมู</div>
            <div class="md-subhead">75 บาท/กก</div>
          </md-card-header>
          <md-card-expand>
            <md-card-actions md-alignment="space-between">
              <div>
                <md-button>ซื้อ</md-button>
              </div>
              <md-card-expand-trigger>
                <md-button>รายละเอียด</md-button>
              </md-card-expand-trigger>
            </md-card-actions>
            <md-card-expand-content>
              <md-card-content> detail </md-card-content>
            </md-card-expand-content>
          </md-card-expand>
        </md-card>
      </div>

      <div
        class="md-layout-item md-medium-size-100 md-xsmall-size-100 md-size-33"
      >
        <md-card>
          <md-card-media>
            <img src="../assets/img/products/2.jpg" alt="People" />
          </md-card-media>
          <md-card-header>
            <div class="md-title">ลูกชิ้นหมู</div>
            <div class="md-subhead">75 บาท/กก</div>
          </md-card-header>
          <md-card-expand>
            <md-card-actions md-alignment="space-between">
              <div>
                <md-button>ซื้อ</md-button>
              </div>
              <md-card-expand-trigger>
                <md-button>รายละเอียด</md-button>
              </md-card-expand-trigger>
            </md-card-actions>
            <md-card-expand-content>
              <md-card-content> detail </md-card-content>
            </md-card-expand-content>
          </md-card-expand>
        </md-card>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  components: {
  },
};
</script>
<style lang="scss" scoped>
.md-card {
  width: 320px;
  margin: 4px;
  display: inline-block;
  vertical-align: top;
}
</style>
