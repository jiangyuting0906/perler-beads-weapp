<template>
  <view>
    <view class="page-body">
      <view class="btn-area">
        <navigator url="../inventoryManage/index" hover-class="navigator-hover">
          <button>库存管理</button>
        </navigator>
        <navigator url="../inventoryReplenishment/index" hover-class="navigator-hover">
          <button>库存补充</button>
        </navigator>
        <navigator url="../inventoryDepletion/index" hover-class="navigator-hover">
          <button>库存消耗</button>
        </navigator>
        <navigator url="../dataAnalysis/index" hover-class="navigator-hover">
          <button>数据分析</button>
        </navigator>
        <navigator url="../operationHistory/index" hover-class="navigator-hover">
          <button>历史记录</button>
        </navigator>
        <navigator url="../messagePush/index" hover-class="navigator-hover">
          <button>补豆提醒</button>
        </navigator>
      </view>
    </view>
  </view>
</template>

<script setup lang="ts">
import { ref } from 'vue'
const title = ref('Hello')
</script>

<style>
.content {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.logo {
  height: 200rpx;
  width: 200rpx;
  margin-top: 200rpx;
  margin-left: auto;
  margin-right: auto;
  margin-bottom: 50rpx;
}

.text-area {
  display: flex;
  justify-content: center;
}

.title {
  font-size: 36rpx;
  color: #8f8f94;
}
</style>
