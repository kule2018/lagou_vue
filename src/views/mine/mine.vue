<template>
  <div class="mine_container">
    <div class="top_container">
      <div class="name-div">
        钱斌
      </div>
      <div class="introduce-div">
        123654123654123654123654123654123654123654123654123654123654
      </div>
      <div class="edit-div">
        <img src="../../assets/img/mine/edit.png"> 编辑
      </div>
      <div class="items-div">
        <div class="item-one-div">
          <img src="../../assets/img/mine/resume.png">
          <div>简历</div>
        </div>
        <div class="item-one-div">
          <img src="../../assets/img/mine/want.png">
          <div>我的投递</div>
        </div>
        <div class="item-one-div">
          <img src="../../assets/img/mine/like_company.png">
          <div>关注公司</div>
        </div>
        <div class="item-one-div">
          <img src="../../assets/img/mine/cc.png">
          <div>拉勾cc</div>
        </div>
      </div>
      <div class="head-div">
        <img src="../../assets/img/head/boy.png">
      </div>
    </div>
    <div class="middle_container">
      <div class="one-line-div">
        <div>
          <img src="../../assets/img/mine/wantwhat.png">
          求职意向
        </div>
        <div>
          <span>暂时不换工作</span>
          <img class="right-img" src="../../assets/img/arrow/arrow-right.png">
        </div>
      </div>
    </div>
    <div class="middle_container">
      <div class="one-line-div border-div">
        <div>
          <img src="../../assets/img/mine/collect.png">
          求职意向
        </div>
        <div>
          <img class="right-img" src="../../assets/img/arrow/arrow-right.png">
        </div>
      </div>
      <div class="one-line-div border-div">
        <div>
          <img src="../../assets/img/mine/feedback.png">
          求职意向
        </div>
        <div>
          <img class="right-img" src="../../assets/img/arrow/arrow-right.png">
        </div>
      </div>
      <div class="one-line-div border-div">
        <div>
          <img src="../../assets/img/mine/setting.png">
          求职意向
        </div>
        <div>
          <img class="right-img" src="../../assets/img/arrow/arrow-right.png">
        </div>
      </div>
    </div>
    <div class="middle_container">
      <div class="one-line-div">
        <div>
          <img src="../../assets/img/mine/secret.png">
          求职意向
        </div>
        <div>
          <span>设置隐私保护</span>
          <img class="right-img" src="../../assets/img/arrow/arrow-right.png">
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'mine',
    data() {
      return {}
    },
    mounted() {
    },
    methods: {},
    computed: {},
    components: {}
  }
</script>
<style scoped lang="scss">
  @import "../../style/mixin";

  .mine_container {
    width: 100%;
    background: #efefef;
    height: 100%;
    overflow: auto;
    .top_container {
      background: white;
      width: 100%;
      padding: 0.3rem 0.5rem;
      position: relative;
      margin-bottom: 0.3rem;
      .name-div {
        font-size: 0.4rem;
        padding-top: 1rem;
        padding-bottom: 0.1rem;
      }
      .introduce-div {
        color: #cccccc;
        width: 60%;
        padding-bottom: 0.05rem;
        overflow: hidden;
        text-overflow: ellipsis;
      }
      .edit-div {
        margin-top: 0.3rem;
        padding: 0.05rem 0.3rem;
        font-size: 0.28rem;
        display: inline-block;
        background: #dedede;
        img {
          width: 0.4rem;
        }
      }
      .items-div {
        margin-top: 1.2rem;
        display: flex;
        justify-content: space-around;
        text-align: center;
        img {
          width: 0.8rem;
          margin-bottom: 0.2rem;
        }
        .item-one-div {

        }
      }
      .head-div {
        position: absolute;
        right: 1.2rem;
        top: 1.6rem;
        img {
          width: 1.5rem;
        }
      }
    }
    .middle_container {
      width: 100%;
      background: white;
      margin-bottom: 0.3rem;
      padding: 0.3rem 0.5rem;
      .border-div {
        padding: 0.3rem 0;
        border-bottom: #dedede 1px solid;
      }
    }
    .one-line-div {
      align-items: center;
      display: flex;
      justify-content: space-between;
      img {
        width: 0.8rem;
        margin-right: 0.2rem;
      }
      .right-img {
        width: 0.4rem;
      }
    }
  }
</style>
