<template>
  <div class="boxed-container">
    <nav class="navbar horizontal-menu navbar-fixed-top">
      <div class="navbar-inner">
        <div class="navbar-brand">
          <router-link to="/" class="logo">
            <img
              src="../assets/images/logo_dark@2x.png"
              width="100%"
              alt=""
              class="hidden-xs"
              style="max-width: 200px"
            />
            <img
              src="../assets/images/logo@2x.png"
              width="100%"
              alt=""
              class="visible-xs"
            />
          </router-link>
        </div>
        <div class="navbar-mobile-clear"></div>
        <a href="https://github.com/xiaobaiTech/golangFamily" target="_blank">
          <i
            class="fa-github"
            style="position: absolute; top: 0; right: 0; border: 0;"
          ></i>
          GitHub
        </a>
      </div>
    </nav>

    <div class="page-container">
      <div class="main-content" style="">
        <div class="row">
          <div class="col-md-12">
            <div class="panel panel-default">
              <!-- 关于网站 -->
              <h4 class="text-gray">关于网站</h4>
              <div class="panel-body">
                <div class="row">
                  <div class="col-sm-12">
                    <blockquote>
                      <p>
                        AI不会淘汰你，但会用AI的人会淘汰你。
                        日常工作中，我已经将大部分产品需求拆解成代码需求交给ai帮我写了，效率有了巨大提升，我深刻意识到AI对于我们程序员的价值有多大。所以一直收藏各种AI资源。
                        但随着收藏的内容越来越多，收藏夹就变得越来越难管理了。
                        所以就有了这个网站，我将自己常用的一些网站放到这上面，方便自己使用，同时也会不断更新各种好玩新鲜的内容。这样大家也不需要费力到处找啦。
                      </p>
                      <br />
                      <p>
                        不管你是程序员，还是非程序员，我都希望这个网站能对你有帮助。
                      </p>
                      <p>有任何建议或者意见都欢迎加我私人微信：Rserlin</p>
                    </blockquote>
                  </div>
                </div>
                <!-- 关于站长 -->
                <h4 class="text-gray">关于站长</h4>
                <div class="row">
                  <div class="col-sm-4">
                    <div
                      class="xe-widget xe-conversations box2 label-info"
                      onclick="window.open('https://xiaobaidebug.top/', '_blank')"
                      data-toggle="tooltip"
                      data-placement="bottom"
                      title=""
                      data-original-title="https://xiaobaidebug.top/"
                      style="align-items: center;"
                    >
                      <div class="xe-comment-entry">
                        <a class="xe-user-img">
                          <img :src="authorImg" class="img-circle" width="40" />
                        </a>
                        <div class="xe-comment">
                          <a href="#" class="xe-user-name overflowClip_1">
                            <strong> 公众号「小白debug」 </strong>
                          </a>
                          <p class="overflowClip_2">
                            关注我之后好好学技术，别老是偷我表情包。
                          </p>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="col-md-4">
                    <div class="row">
                      <div class="col-sm-12">
                        <br />
                        <blockquote>
                          <img
                            src="https://cdn.xiaobaidebug.top/image/小白debug动图二维码-20210908204913011.gif"
                            class="img-rounded"
                            width="280"
                          />
                        </blockquote>
                      </div>
                    </div>
                    <br />
                  </div>
                  <div class="col-md-4">
                    <div class="row">
                      <div class="col-sm-12">
                        <br />
                        <blockquote>
                          <p>
                            如果你对AI副业感兴趣, 欢迎加入我的知识星球
                            <a href="https://t.zsxq.com/11MJiMbel">
                              点击领优惠券加入
                            </a>

                            如果你对计算机网络或者golang感兴趣，也欢迎来我的个人博客里逛逛
                            <a href="https://xiaobaidebug.top/">
                              <span
                                class="label label-info"
                                data-toggle="tooltip"
                                data-placement="left"
                                title=""
                                data-original-title="Hello I am a Tooltip"
                                >xiaobaidebug.top</span
                              > </a
                            >欢迎与我交流分享！！
                          </p>
                        </blockquote>
                      </div>
                    </div>
                    <br />
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <Footer />
      </div>
    </div>
  </div>
</template>

<script>
import Footer from "../components/Footer.vue";
export default {
  name: "About",
  components: {
    Footer,
  },
  data() {
    return {
      authorImg: "./assets/images/logos/xiaobai.jpeg",
    };
  },
};
</script>

<style></style>
