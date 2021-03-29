<template>

  <div>
    <el-backtop :bottom="100">
      <svg class="icon"
           aria-hidden="true"
           style="color: #7a96e7;">
        <use xlink:href="#icon-huojian"></use>
      </svg>
    </el-backtop>

    <div>
      <div class="bigpic">

        <div :class="sticky?'sticky':''"
             id="topNavBar"
             class="topNavBar">
          <div class="topNavBar-inner clearfix">
            <a class="logo"
               href="#"
               alt="logo"
               style="float: left;">
              <span class="rs">万家程 - </span>
              <span class="card">简历</span>
            </a>

            <nav class="menu"
                 style="float: right;">
              <ul class="clearfix">
                <li>
                  <a href="#siteAbout">关于</a>
                </li>
                <li>
                  <a href="#siteSkills">技能</a>
                </li>
                <li>
                  <a href="#siteWorks">作品</a>
                  <ul class="submenu">
                    <li>作品1</li>
                    <li>作品2</li>
                    <li>作品3</li>
                  </ul>
                </li>
                <li>
                  <a href="#">博客</a>
                  <ul class="submenu">
                    <li>博客1</li>
                    <li>博客2</li>
                    <li>博客3</li>
                  </ul>
                </li>
                <li>
                  <a href="#">日历</a>
                </li>
                <li>
                  <a href="#">联系方式</a>
                </li>
                <li>
                  <a href="#">其他</a>
                </li>
              </ul>
            </nav>
          </div>
        </div>
        <div class="banner">
          <div class="mask"></div>
        </div>
        <main>
          <div data-x
               id="siteAbout"
               class="userCard">
            <div class="pictureAndText clearfix">
              <div class="picture">
                <img v-lazy="touxiang"
                     width="299"
                     height="347"
                     alt="头像" />
              </div>
              <div class="text">
                <span class="welcome">
                  <span class="s1">H </span>
                  <span class="s2">e </span>
                  <span class="s3">l </span>
                  <span class="s4">l </span>
                  <span class="s5">o </span>
                  <span class="triangle"></span>
                </span>
                <h1>万家程</h1>
                <p>前端开发工程师</p>
                <hr />
                <dl>
                  <dt>年龄</dt>
                  <dd>24</dd>
                  <dt>所在城市</dt>
                  <dd>上海</dd>
                  <dt>邮箱</dt>
                  <dd>1094941478@QQ.com</dd>
                  <dt>手机</dt>
                  <dd>18553770953</dd>
                </dl>
              </div>
            </div>
            <footer class="media">
              <a href="#">
                <svg class="icon"
                     aria-hidden="true">
                  <use xlink:href="#icon-qq"></use>
                </svg>
              </a>
              <a href="#">
                <svg class="icon"
                     aria-hidden="true">
                  <use xlink:href="#icon-gongzhonghao"></use>
                </svg>
              </a>
              <a href="#">
                <svg class="icon"
                     aria-hidden="true">
                  <use xlink:href="#icon-weibo"></use>
                </svg>
              </a>
            </footer>
          </div>

          <div class="zijigexinghuadingzhicode">
            <div class="downloadResume-wrapper">
              <div class="downloadResume"
                   target="_blank">

              </div>
            </div>

            <div class="selfIntroduction">
              <div>
                <svg class="icon ic1"
                     aria-hidden="true"
                     style="width:20px; height:16px">
                  <use xlink:href="#icon-xuehua2-copy"></use>
                </svg>

                精通HTML、HTML5、CSS、CSS3、动画、了解一些浏览器的兼容

              </div>
              <div>
                <svg class="icon ic1"
                     aria-hidden="true"
                     style="width:20px; height:16px">
                  <use xlink:href="#icon-xuehua2-copy"></use>
                </svg>

                熟练手写符合 W3C 标准的结构和代码

              </div>
              <div>
                <svg class="icon ic1"
                     aria-hidden="true"
                     style="width:20px; height:16px">
                  <use xlink:href="#icon-xuehua2-copy"></use>
                </svg>

                了解 Ajax 工作原理和实现方法。
              </div>
              <div>
                <svg class="icon ic1"
                     aria-hidden="true"
                     style="width:20px; height:16px">
                  <use xlink:href="#icon-xuehua2-copy"></use>
                </svg>

                熟练掌握JavaScript、HTML5、CSS、Ajax、jQuery，ES6等前端开发技术.

              </div>
              <div>
                <svg class="icon ic1"
                     aria-hidden="true"
                     style="width:20px; height:16px">
                  <use xlink:href="#icon-xuehua2-copy"></use>
                </svg>

                熟练掌握uniapp,vue.js等各类前端框架的一种或多种,了解其它前端技术；

              </div>
              <div>
                <svg class="icon ic1"
                     aria-hidden="true"
                     style="width:20px; height:16px">
                  <use xlink:href="#icon-xuehua2-copy"></use>
                </svg>
                具备数据处理及JS开发能力，具备与后端数据交互的开发能力；

              </div>
              <div>
                <svg class="icon ic1"
                     aria-hidden="true"
                     style="width:20px; height:16px">
                  <use xlink:href="#icon-xuehua2-copy"></use>
                </svg>

                熟练运用HTML5特性构建移动端App，熟练掌握Web&App的整体实现方式

              </div>
              <div>
                <svg class="icon ic1"
                     aria-hidden="true"
                     style="width:20px; height:16px">
                  <use xlink:href="#icon-xuehua2-copy"></use>
                </svg>

                熟悉当前流行的JavaScript类库，框架，精通原生Javascript，编写高性能Javascript代码；

              </div>
              <div>
                <svg class="icon ic1"
                     aria-hidden="true"
                     style="width:20px; height:16px">
                  <use xlink:href="#icon-xuehua2-copy"></use>
                </svg>

                熟悉Web标准，对MVVM，HTML语义化，响应式设计等有一定理解

              </div>

            </div>
          </div>

        </main>

        <section data-x
                 id="siteSkills"
                 class="skills"
                 ref="skills">
          <h2>技能</h2>
          <ol class="clearfix">
            <li>
              <h3>
                HTML 5 &amp; CSS 3
              </h3>
              <div class="progressBar">
                <div ref="html1"
                     class="progress"
                     :style="{width:width1}"></div>
              </div>
            </li>
            <li>
              <h3>
                JavaScript
              </h3>
              <div class="progressBar">
                <div class="progress"
                     :style="{width:width2}"
                     style="transition-delay:0.4s;"></div>
              </div>
            </li>
            <li>
              <h3>
                jQuery
              </h3>
              <div class="progressBar">
                <div class="progress"
                     :style="{width:width3}"
                     style="transition-delay:0.8s;"></div>
              </div>
            </li>
            <li>
              <h3>
                Vue.js
              </h3>
              <div class="progressBar">
                <div class="progress"
                     :style="{width:width4}"
                     style="transition-delay:1.2s;"></div>
              </div>
            </li>
            <li>
              <h3>
                React.js
              </h3>
              <div class="progressBar">
                <div class="progress"
                     :style="{width:width5}"
                     style="transition-delay:1.6s;"></div>
              </div>
            </li>
            <li>
              <h3>
                Node.js
              </h3>
              <div class="progressBar">
                <div class="progress"
                     :style="{width:width6}"
                     style="transition-delay:2s;"></div>
              </div>
            </li>
          </ol>
        </section>
        <section class="portfolio"
                 id="siteWorks">
          <h2>作品集</h2>
          <nav>
            <ol class="clearfix olhover">
              <li @click="portfolio1"
                  class="li11">所有</li>
              <li @click="portfolio2">框架</li>
              <li @click="portfolio3">原生JS&amp;CSS</li>
            </ol>
            <div id="portfolioBar"
                 :class="{bar:true,'state-1':bar1,'state-2':bar2,'state-3':bar3}">
              <div class="bar-inner">

              </div>
            </div>
          </nav>

          <div class="works"
               style="height: 665px; "
               v-if="bar1"
               ref="works">
            <div class="block">
              <!-- <span class="demonstration"></span> -->
              <el-carousel height="800px"
                           width="340px">
                <el-carousel-item v-for="(item,index) in imgs"
                                  :key="index">
                  <img v-lazy='item'
                       alt="">
                  <!-- <h3 class="small">{{ item }}</h3> -->
                </el-carousel-item>
              </el-carousel>
            </div>
          </div>

          <div class="works"
               style="height: 680px;"
               v-if="bar2">

            <div class="small"
                 style="top: 0; left: 645px;">
              <img src="https://ftp.bmp.ovh/imgs/2020/11/66e27522ff9b4a04.jpg"
                   alt="作品2" />
            </div>
            <div class="small"
                 style="top: 312px; left: 645px;">
              <img src="https://ftp.bmp.ovh/imgs/2020/11/0a79d95e76a6590f.jpg"
                   alt="作品3" />
            </div>
          </div>

          <div class="works"
               style="height: 597px;"
               v-if="bar3">
            <div class="big"
                 style="top: 0; left: 0;">
              <img src="https://ftp.bmp.ovh/imgs/2020/11/1ada6c681f4ff642.jpg"
                   alt="作品1" />
            </div>
            <div class="small"
                 style="top: 0; left: 645px;">
              <img src="https://ftp.bmp.ovh/imgs/2020/11/66e27522ff9b4a04.jpg"
                   alt="作品2" />
            </div>
            <div class="small"
                 style="top: 312px; left: 645px;">
              <img src="https://ftp.bmp.ovh/imgs/2020/11/0a79d95e76a6590f.jpg"
                   alt="作品3" />
            </div>
          </div>
        </section>

        <div class="continue"
             ref="continue">
          <h1>项目介绍</h1>
          <div class="xiang1"
               ref="xiang1">
            <h2>一、卖座网</h2>
            <p class="a1"><b>项目介绍:</b><br>本项目是一款手机App,使用了Vue框架其中涉及swiper触控滑动模块，子页之间采用了懒加载技术保证用户体验，Bscroll上拉加载下拉刷新模块</p>
            <div>
              <h3>项目架构:</h3>
              <p>1、项目主要使用Vue框架, 以及vue-router构建单页面应用。</p>
              <p>2、项目采用Vuex处理各个组件之间的互相传值,vue-resource处理请求</p>
              <p>3、使用Element-ui组件库中的部分功能进行快速的开发</p>
              <p>4、使用阿里巴巴矢量图标库。</p>
              <p>5、运用swiper框架进行部分页面的设计,实现一些图片的轮播。</p>
              <p>6、代码使用sass进行代码的编写</p>
              <p>7、运用vue.js中的指令和服务与后台接口对接，进行数据交互，进行页面渲染，实现功能 模块的判断。</p>
            </div>
            <div>
              <h3>项目难点:</h3>
              <p>项目测试阶段需要自己使用node搭建mongodb数据库后端连接进行数据的对接和数据渲染，测试功能模块时候可以正常工作,逻辑是否正确</p>
              <p>需要解决不同浏览器或者不同手机端的兼容问题导致的页面错乱</p>
            </div>
          </div>
          <div class="xiang2">
            <h2>二、仿京东商城</h2>
            <div class="a1">
              <h3>项目介绍:</h3>仿照京东商场首页,商品列表,商品详情页面,用户的注册\登录,购物车的增删改,全选
            </div>
            <div>
              <h3>技术实现</h3>
              HTML5、CSS3、jQuery、PHP、MySQL

            </div>
            <div>
              <h3>项目架构</h3>
              <p>1、通过采用DIV+CSS样式布局排版;</p>
              <p>2、通过原生JS和jQuery实现页面的大部分交互</p>
              <p>3、使用基础的PHP连接后端数据库进行页面的渲染</p>
            </div>
            <div>
              <h3>项目的收获</h3>
              <p>1、了解了客户端-服务器端-数据库的案例实现流程</p>
              <p>2、加深了对后台语言以及数据库的使用与了解，使前后台更好的结合。</p>
            </div>

          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  //组件名字
  name: "comfilmlisttopnav",
  //接收父组件给的东西 type是接收什么东西  default 默认值
  props: {
    list: {
      type: Array,
      default () {
        return [];
      },

    },
    color: {
      type: String,
      default: "#000",
    },
    visibilityHeight: {
      type: Number,
      default: 200
    },
    target: [String],
    right: {
      type: Number,
      default: 40
    },
    bottom: {
      type: Number,
      default: 40
    }

  },
  //组件注册
  components: {},
  // vue数据集中管理
  data () {
    return {
      imgs: [
        ('https://s3.ax1x.com/2020/11/29/DgmRE9.png'),
        ('https://s3.ax1x.com/2020/11/29/Dgm6uF.png'),
        ('https://s3.ax1x.com/2020/11/29/DgmcB4.png'),
        ('https://s3.ax1x.com/2020/11/29/DgmsjU.png'),
        ('https://s3.ax1x.com/2020/11/29/DgmgHJ.png'),
        ('https://s3.ax1x.com/2020/11/29/DgmWNR.png'),
        ('https://s3.ax1x.com/2020/11/29/Dgmf41.png')
      ],
      value: "1",
      isbar: true,
      bar1: true,
      bar2: false,
      bar3: false,
      sticky: false,

      width1: 10 + '%',
      width2: 10 + '%',
      width3: 10 + '%',
      width4: 10 + '%',
      width5: 10 + '%',
      width6: 10 + '%',
      touxiang: 'https://ss0.bdstatic.com/70cFvHSh_Q1YnxGkpoWK1HF6hhy/it/u=3839069834,893282384&fm=26&gp=0.jpg'
    };
  },
  //方法 函数写这里
  methods: {
    portfolio1 () {
      console.log("进入portfolio1");
      this.bar1 = true
      this.bar2 = false
      this.bar3 = false
    },
    portfolio2 () {
      console.log("进入portfolio2");
      this.bar1 = false
      this.bar2 = true
      this.bar3 = false
    },
    portfolio3 () {
      console.log("进入portfolio3");
      this.bar1 = false
      this.bar2 = false
      this.bar3 = true
    },
  },
  //计算属性
  computed: {},
  //侦听器
  watch: {},
  //过滤器
  filters: {
    toUpcase (value) {
      return value ? value.toUpperCase() : "";
    },
  },
  //以下是生命周期
  //组件创建之前
  beforeCreate () { },
  //组件创建之后
  created () {

  },
  //页面渲染之前
  beforeMount () {

  },
  //页面渲染之后
  mounted () {


    window.addEventListener("scroll", (e) => {
      console.log("我进入了scroll监听  ");
      // console.log(e);
      var top = document.documentElement.scrollTop;

      if (top > 300) {
        this.width1 = 90 + '%'
        this.width2 = 85 + '%'
        this.width3 = 70 + '%'
        this.width4 = 70 + '%'
        this.width5 = 65 + '%'
        this.width6 = 80 + '%'
      }

      let wind = document.documentElement.clientHeight

      let continueTop = this.$refs.continue.offsetTop
      console.log(continueTop);
      if (top > continueTop - wind) {
        this.$refs.continue.style.opacity = 1
      }

      let worksTop = this.$refs.works.offsetTop
      console.log(worksTop);
      if (top > worksTop - wind) {
        this.$refs.works.style.opacity = 1
      }

      let skillsTop = this.$refs.skills.offsetTop
      console.log(skillsTop);
      if (top > skillsTop - wind) {
        this.$refs.skills.style.opacity = 1
        this.$refs.skills.style.marginTop = 60 + 'px'

      }
      console.log(document.documentElement.clientHeight);

      let xiang1Top = this.$refs.xiang1.offsetTop
      if (top > xiang1Top - wind) {
        this.$refs.xiang1.style.opacity = 1
        this.$refs.xiang1.style.marginTop = 40 + 'px';
      }


      // console.log(top);
      if (top > 200) {
        this.sticky = true
      } else {
        this.sticky = false
      }
    }, true);


    //背景
    (function () {
      function o (w, v, i) {
        return w.getAttribute(v) || i
      }
      function j (i) {
        return document.getElementsByTagName(i)
      }
      function l () {
        var i = j("script"),
          w = i.length,
          v = i[w - 1];
        return {
          l: w,
          z: o(v, "zIndex", -1),
          o: o(v, "opacity", 0.5),
          c: o(v, "color", "0,0,0"),
          n: o(v, "count", 99)
        }
      }
      function k () {
        r = u.width = window.innerWidth || document.documentElement.clientWidth || document.body.clientWidth,
          n = u.height = window.innerHeight || document.documentElement.clientHeight || document.body.clientHeight
      }
      function b () {
        e.clearRect(0, 0, r, n);
        var w = [f].concat(t);
        var x, v, A, B, z, y;
        t.forEach(function (i) {
          i.x += i.xa,
            i.y += i.ya,
            i.xa *= i.x > r || i.x < 0 ? -1 : 1,
            i.ya *= i.y > n || i.y < 0 ? -1 : 1,
            e.fillRect(i.x - 0.5, i.y - 0.5, 1, 1);
          for (v = 0; v < w.length; v++) {
            x = w[v];
            if (i !== x && null !== x.x && null !== x.y) {
              B = i.x - x.x,
                z = i.y - x.y,
                y = B * B + z * z;
              y < x.max && (x === f && y >= x.max / 2 && (i.x -= 0.03 * B, i.y -= 0.03 * z), A = (x.max - y) / x.max, e.beginPath(), e.lineWidth = A / 2, e.strokeStyle = "rgba(" + s.c + "," + (A + 0.2) + ")", e.moveTo(i.x, i.y), e.lineTo(x.x, x.y), e.stroke())
            }
          }
          w.splice(w.indexOf(i), 1)
        }),
          m(b)
      }
      var u = document.createElement("canvas"),
        s = l(),
        c = "c_n" + s.l,
        e = u.getContext("2d"),
        r,
        n,
        m = window.requestAnimationFrame || window.webkitRequestAnimationFrame || window.mozRequestAnimationFrame || window.oRequestAnimationFrame || window.msRequestAnimationFrame ||
          function (i) {
            window.setTimeout(i, 1000 / 45)
          },
        a = Math.random,
        f = {
          x: null,
          y: null,
          max: 20000
        };
      u.id = c;
      u.style.cssText = "position:fixed;top:0;left:0;z-index:" + s.z + ";opacity:" + s.o;
      j("body")[0].appendChild(u);
      k(),
        window.onresize = k;
      window.onmousemove = function (i) {
        i = i || window.event,
          f.x = i.clientX,
          f.y = i.clientY
      },
        window.onmouseout = function () {
          f.x = null,
            f.y = null
        };
      for (var t = [], p = 0; s.n > p; p++) {
        var h = a() * r,
          g = a() * n,
          q = 2 * a() - 1,
          d = 2 * a() - 1;
        t.push({
          x: h,
          y: g,
          xa: q,
          ya: d,
          max: 6000
        })
      }
      setTimeout(function () {
        b()
      },
        100)
    })();









    //点击出现心型
    document.addEventListener('click', box)
    function box (e) {
      let div = document.createElement('div'),
        divLeft = document.createElement('div'),
        divRight = document.createElement('div')
      let top = e.pageY, left = e.pageX;
      div.className = 'box';
      divLeft.className = 'box-left';
      divRight.className = 'box-right';
      divLeft.style.backgroundColor = divRight.style.backgroundColor = color(); +
        div.appendChild(divLeft);
      div.appendChild(divRight);
      div.style.top = top + 'px';
      div.style.left = left + 'px';
      document.body.appendChild(div);

      animation(div, top);
    }
    function ran (min, max) {
      return Math.round(Math.random() * (max - min) + min)
      div.style.transform = scale(ran(0, 2));
    }
    function color () {
      let r = Math.round(Math.random() * 255);
      let g = Math.round(Math.random() * 255);
      let b = Math.round(Math.random() * 255);
      return `rgb(${r},${g},${b})`;
    }

    function animation (div, top) {
      let i = 1;
      let left = 15;
      let times = setInterval(function () {
        //控制透明越小消失的越慢
        i -= 0.015;
        //控制上升
        top -= 1;
        div.style.opacity = i;
        div.style.top = top + 'px';
        if (i <= 0) {
          document.body.removeChild(div);
          clearInterval(times);
        }
      }, 30)
    }
    // 点击出现心型结束
  },
  //页面销毁之前
  beforeDestroy () { },
  //页面销毁之后
  destroyed () { },
  //页面视图数据更新之前
  beforeUpdate () { },
  //页面视图数据更新之后
  updated () { },
  //组件路由守卫enter
  beforeRouteEnter (to, from, next) {
    next((vm) => { });
    // 注意，在路由进入之前，组件实例还未渲染，所以无法获取this实例，只能通过vm来访问组件实例
  },
  //组件路由守卫update更新
  beforeRouteUpdate (to, from, next) {
    // 同一页面，刷新不同数据时调用，
    next();
  },
  //组件路由守卫离开
  beforeRouteLeave (to, from, next) {
    // 离开当前路由页面时调用
    next();
  },
};
</script>

<style lang="scss" >
.block {
  box-shadow: 0px 1px 5px 0px rgba(0, 0, 0, 0.5);
  margin-left: 150px;
  width: 370px;
  height: 700px;
}
.el-carousel__item h3 {
  color: #475669;
  font-size: 14px;
  opacity: 0.75;
  line-height: 150px;
  margin: 0;
}

.el-carousel__item:nth-child(2n) {
  background-color: #99a9bf;
}

.el-carousel__item:nth-child(2n + 1) {
  background-color: #d3dce6;
}
body {
  // background: url("https://ftp.bmp.ovh/imgs/2020/11/ba3b76e0f9630fad.jpg") fixed center center no-repeat;
  // background: url("http://static.simpledesktops.com/uploads/desktops/2019/03/04/zurich.png") fixed center center no-repeat;
  // background: linear-gradient(
  //   -45deg,
  //   rgba(9, 69, 138, 0.2),
  //   rgba(68, 155, 255, 0.7),
  //   rgba(117, 113, 251, 0.7),
  //   rgba(68, 155, 255, 0.7),
  //   rgba(9, 69, 138, 0.2)
  // );
  background-image: linear-gradient(
    to right,
    rgba(9, 69, 138, 0.2),
    rgba(68, 155, 255, 0.7),
    rgba(162, 159, 243, 0.5),
    rgba(68, 155, 255, 0.7),
    rgba(9, 69, 138, 0.2)
  );

  // background-size: cover;
  height: 100%;
}

.bigpic {
  height: 763px;
  z-index: 1;
  background: url("https://ftp.bmp.ovh/imgs/2020/11/ba3b76e0f9630fad.jpg") fixed
    center center no-repeat;
}
.back-top-container {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  overflow: auto;
}
.box {
  position: absolute;
  width: 20px;
  height: 20px;
  animation: Suo 2s linear infinite;
}

.box .box-left,
.box .box-right {
  position: absolute;
  float: left;
  width: 50%;
  height: 90%;
  border-radius: 30px 30px 15px 15px;
  background-color: red;
}

.box .box-right {
  box-shadow: 4px 0px 4px gray;
}

/* 旋转 */
.box .box-left {
  transform: rotateZ(-45deg);
}

.box .box-right {
  left: 6px;
  transform: rotateZ(45deg);
}

@keyframes Suo {
  0% {
    transform: scale(1);
  }

  100% {
    transform: scale(0.1);
  }
}
.topNavBar {
  padding: 20px 0;
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  transition: all 0.5s;
  color: #b7b7b7;
}
.topNavBar.sticky {
  background: white;
  padding: 10px 0;
  z-index: 12222;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.25);
  color: #3d4451;
}
.topNavBar-inner {
  padding: 0 16px;
}
.topNavBar nav {
  color: #000;
  margin-right: 400px;
  padding-top: 5px;
}
.topNavBar nav li:hover {
  color: orangered;
}
.topNavBar nav > ul {
  list-style: none;
  margin: 0;
  padding: 0;
}

.topNavBar nav > ul > li {
  float: left;
  margin-left: 17px;
  margin-right: 17px;
  position: relative;
}
.topNavBar nav > ul > li > a {
  font-size: 12px;
  color: inherit;
  font-weight: bold;
  border-top: 3px solid transparent;
  border-bottom: 3px solid transparent;
  padding-top: 5px;
  padding-bottom: 5px;
  display: block;
  position: relative;
}
.topNavBar nav > ul > li.active > a::after,
.topNavBar nav > ul > li.highlight > a::after {
  content: "";
  display: block;
  position: absolute;
  top: 100%;
  left: 0;
  width: 100%;
  background: #7a96e7;
  height: 3px;
  animation: menuSlide 0.3s;
}
@keyframes menuSlide {
  0% {
    width: 0;
  }
  100% {
    width: 100%;
  }
}
.topNavBar .submenu {
  display: none;
  position: absolute;
  right: 0;
  top: 100%;
  background: white;
  color: #3d4451;
  box-shadow: 0 0 5px rgba(0, 0, 0, 0.5);
}
.topNavBar li.active > .submenu {
  display: block;
  animation: submenuSlide 0.3s;
}
@keyframes submenuSlide {
  0% {
    margin-right: 100%;
  }
  100% {
    margin-right: 0%;
  }
}
.topNavBar .submenu > li {
  white-space: nowrap;
  padding: 5px 10px;
}

.topNavBar .logo {
  font-size: 36px;
  font-family: "Arial Black";
  padding-top: 3px;
  padding-bottom: 4px;
}
.topNavBar .logo .rs {
  margin-top: 100p;
  margin-left: 400px;
  margin-right: 4px;
  color: #000000;
}
.topNavBar .logo .card {
  color: #7a96e7;
}
// .banner {
//   height: 640px;
//   //   background-image: url(/img/rs-cover.jpg);https://ftp.bmp.ovh/imgs/2020/11/8af5cf9a2d77f24b.jpg
//   // background-image: url("https://ftp.bmp.ovh/imgs/2020/11/8af5cf9a2d77f24b.jpg");
// background: url("https://ftp.bmp.ovh/imgs/2020/11/ba3b76e0f9630fad.jpg")
//   no-repeat center center;
//   // background-position: center center;
//   background-size: cover;
// }
.banner .mask {
  height: 640px;
  background-color: rgba(0, 0, 0, 0);
}

.userCard {
  max-width: 940px;
  margin-left: auto;
  margin-right: auto;
  background-color: #ffffff;
  box-shadow: 0px 1px 5px 0px rgba(0, 0, 0, 0.5);
}

.userCard .welcome {
  font-size: 30px;
  background: #7a96e7;
  color: white;
  display: inline-block;
  padding: 4px 16px;
  line-height: 40px;
  position: relative;
  margin-bottom: 10px;
}
.userCard .welcome span {
  position: relative;
  float: left;
  transition: all 3s;
}
.userCard .welcome span {
  transition: all 3s;
}

.s1 {
  animation: 1s jump 0.5s infinite ease;
}
.s2 {
  animation: 1s jump 0.5s infinite ease;
}
.s3 {
  animation: 1s jump 0.5s infinite ease;
}
.s4 {
  animation: 1s jump 0.5s infinite ease;
}
.s5 {
  animation: 1s jump 0.5s infinite ease;
}

@keyframes jump {
  0% {
    top: 0px;
    // color: red;
  }
  30% {
    top: -5px;
    // color: green;
  }
  100% {
    top: 0px;
  }
}

.userCard .welcome .triangle {
  display: block;
  border: 18px solid transparent;
  width: 0px;
  border-left-color: #7a96e7;
  border-top-width: 0px;
  position: absolute;
  left: 4px;
  top: 100%;
}
.userCard .picture {
  float: left;
}
.userCard .picture img {
  border-radius: 50%;
}
.userCard .text {
  float: left;
  margin-left: 65px;
  width: 470px;
}
.userCard .text h1 {
  margin-top: 18px;
}
.userCard .text hr {
  margin: 20px 0;
}
.userCard .pictureAndText {
  padding: 50px;
}
.userCard dl dt,
.userCard dl dd {
  float: left;
  padding: 5px 0;
}
.userCard dl dt {
  width: 30%;
  font-weight: bold;
}
.userCard dl dd {
  width: 70%;
  color: #9da0a7;
}

.userCard > footer.media {
  background: #7a96e7;
  text-align: center;
}
.userCard > footer.media > a {
  display: inline-block;
  width: 40px;
  line-height: 30px;
  padding: 5px 0;
  border-radius: 50%;
  margin: 16px;
}
.userCard > footer.media > a:hover {
  background: #cf5d5f;
}
.userCard svg {
  width: 30px;
  height: 30px;
  fill: white;
  vertical-align: top;
}
main {
  margin-top: -400px;
  z-index: 20;
}
main .downloadResume-wrapper {
  text-align: center;
}
main .downloadResume {
  font-size: 14px;
  line-height: 16px;
  padding: 21px 55px;
  border: 1px solid #7a96e7;
  background: #7a96e7;
  display: inline-block;
  border-radius: 2px;
  color: #3d4451;
  font-weight: bold;
  margin: 32px 0;
  transition: box-shadow 0.2s;
}
main .downloadResume:hover {
  box-shadow: 0px 4px 13px 0px rgba(0, 0, 0, 0.2);
}

.selfIntroduction {
  max-width: 940px;
  margin-left: auto;
  margin-right: auto;
  // text-align: center;
  font-family: kai;
  line-height: 1.8;
  font-size: 18px;
  overflow: hidden;
  div {
    padding: 10px;
    color: orangered;
  }
}

// #siteSkills {
//   position: relative;
//   right: -500px;
//   transform: all 1s;
// }
section.skills {
  transition: all 1.5s;
  opacity: 0;
  overflow: hidden;
  max-width: 940px;
  margin-left: auto;
  margin-right: auto;
  margin-top: 100px;
}
section.portfolio {
  overflow: hidden;
  max-width: 940px;
  margin-left: auto;
  margin-right: auto;
  margin-top: 60px;
}
section.skills > h2,
section.portfolio > h2 {
  text-align: center;
  color: #3d4451;
  font-size: 34px;
  line-height: 1.2;
  font-weight: 600;
}
section.skills h3 {
  font-size: 14px;
  line-height: 1.1;
  padding-right: 40px;
}
section.skills > ol {
  background: white;
  box-shadow: 0px 1px 5px 0px rgba(0, 0, 0, 0.5);
  padding: 42px 50px 10px;
  margin-top: 30px;
}
section.skills > ol > li {
  float: left;
  width: 48%;
  box-sizing: border-box;
}
section.skills > ol > li:nth-child(even) {
  float: right;
}

section.skills .progressBar {
  height: 5px;
  background: #fae1e1;
  border-radius: 2px;
  margin: 4px 0 40px;
  overflow: hidden;
}
section.skills .progressBar > .progress {
  height: 100%;
  background-image: linear-gradient(to right, #4d4a4a, #8fa1d8, red, #021a63);

  width: 70%;
  border-radius: 2px;
  transform: translateX(0);
  transition: all 1s;
}
section.skills.offset .progress {
  transform: translateX(-100%);
}

section.portfolio {
  overflow: hidden;
  text-align: center;
  margin-bottom: 100px;
}
section.portfolio > nav {
  text-align: center;
}
section.portfolio > nav > ol {
  margin: 0 auto;
  display: inline-block;
  vertical-align: top;
}
section.portfolio > nav > ol > li {
  float: left;
  margin-left: 40px;
  cursor: pointer;
}
section.portfolio > nav > ol > li:first-child {
  margin-left: 0;
}
section.portfolio > nav {
  display: inline-block;
  vertical-align: top;
  margin-top: 32px;
}
section.portfolio > nav .bar {
  height: 5px;
  background: white;
  margin-top: 5px;
  margin-bottom: 28px;
  border-radius: 2px;
}
section.portfolio > nav .bar-inner {
  height: 100%;
  background: #7a96e7;
  border-radius: 2px;
  transition: all 0.3s;
}
.olhover {
  li {
    padding: 10px;
    border-radius: 15px;
  }
  li:hover {
    background: orange;
  }
}
.li11 {
  padding-left: 10px;
}
section.portfolio > nav .bar.state-1 .bar-inner {
  margin-left: 0;
  width: 50px;
}
section.portfolio > nav .bar.state-2 .bar-inner {
  margin-left: 95px;
  width: 50px;
}
section.portfolio > nav .bar.state-3 .bar-inner {
  margin-left: 185px;
  width: 110px;
}
section.portfolio .works {
  opacity: 0;
  transition: all 2s;
  position: relative;
}
section.portfolio .works > .big,
section.portfolio .works > .small {
  position: absolute;
}

// .zijigexinghuadingzhicode {
//     // border: 5px solid red;

// }

.continue {
  transition: all 2s;
  opacity: 0;
  max-width: 940px;
  margin-left: auto;
  margin-right: auto;
  // background-color: rgba($color: #ffffff, $alpha: 0.4);
  // box-shadow: 0px 1px 5px 0px rgba(0, 0, 0, 0.5);
  // height: 2000px;
  // border: 3px solid red;
  margin: 0 auto;
  padding: 20px 0;
  h1 {
    text-align: center;
  }
  .xiang1 {
    // opacity: 0;
    transition: all 1s;

    margin: 40px;
    margin-top: 140px;
    .a1 {
      box-shadow: 0px 1px 5px 0px rgba(0, 0, 0, 0.5);

      border-radius: 10px;
      padding: 10px;
      border-left: 10px solid #7a96e7;
      background: white;
      padding-left: 15px;
      margin-bottom: 20px;
      margin-top: 20px;
      b {
        font-size: 18px;
      }
    }
    div {
      box-shadow: 0px 1px 5px 0px rgba(0, 0, 0, 0.5);

      margin-bottom: 20px;
      border-radius: 10px;

      padding: 10px;
      border-left: 10px solid #7a96e7;
      background: white;
      padding-left: 15px;
      h3 {
        margin-bottom: 5px;
        font-weight: 800;
      }
    }
  }
  .xiang2 {
    margin: 10px 40px;
    div {
      box-shadow: 0px 1px 5px 0px rgba(0, 0, 0, 0.5);

      border-radius: 10px;
      padding: 10px;
      border-left: 10px solid #7a96e7;
      background: white;
      padding-left: 15px;
      margin-bottom: 20px;
      margin-top: 20px;
      h3 {
        margin-bottom: 5px;
        font-weight: 800;
      }
    }
  }
}
</style>
