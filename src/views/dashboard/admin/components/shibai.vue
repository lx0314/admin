<template>
  <div class="box">
    <div class="boxtop">
      <div class="boxtopl">
        <div class="boxtopll">
          .
        </div>
        <div style="float: left ;margin-left: 10px;">
          <h6 style="margin: 0">千一</h6>
          <span>12345678900</span>
        </div>
      </div>
      <a href="#" style="line-height: 1px;display:inline-block;float: right;font-size: 30px;text-decoration: none;color: #5c636a;">...</a>
    </div>
    <div class="boxconter">
      <div>
        <h6>驳回次数</h6>
        <span>13</span>
      </div>
      <div>
        <h6>驳回原因</h6>
        <span>填写错误</span>
      </div>
      <div>
        <h6>损失金额</h6>
        <span>13</span>
      </div>
    </div>
    <div class="boxb">
      <span style="width: 30%;font-size: 8px;">
        修改进度
      </span>
      <div style="float: right;width: 70%">
        <el-progress :percentage="36" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Shibai'
}
</script>

<style scoped lang="scss">
.box{
  width: 100%;
  height: 160px;
  background-color: white;
  padding: 20px;
  .boxtop{
    height: 40px;
    margin-bottom: 10px;
    .boxtopl{
      .boxtopll{
        width: 40px;
        height: 40px;
        border-radius:20px;
        background-color: #0f5132;
        float: left
      }
    }
  }
  .boxconter{
    height: 40px;
    margin-bottom: 10px;
    div{
      width: 33%;
      height: 30px;
      float: left;
      h6{
        color: #5c636a;
        margin: 0;
      }
      span{
        color: #000000;
        font-size: 10px;
      }
    }
  }
  .boxb{
    clear: both;
  }
}
</style>
