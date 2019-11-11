<template>
  <header>
    <div class="menu">
      <nav class="nav" id="topnav">
        <h1 class="logo">
          <a href="http://sue.suhhai.cn">SueSea博客</a>
        </h1>
        <li>
          <a href="http://suhhai.cn/">网站首页</a>
        </li>
        <li>
          <a href="about.html">关于我</a>
        </li>
        <li>
          <a href="share.html">技术分享</a>
          <ul class="sub-nav">
            <li>
              <a href="share.html">CSS3|Html5</a>
            </li>
            <li>
              <a href="share.html">javaScript</a>
            </li>
            <li>
              <a href="share.html">vue.js</a>
            </li>
          </ul>
        </li>
        <li>
          <a href="list.html">学无止境</a>
          <ul class="sub-nav">
            <li>
              <a href="list.html">Webpack</a>
            </li>
            <li>
              <a href="list.html">React</a>
            </li>
            <li>
              <a href="list.html">Node.js</a>
            </li>
          </ul>
        </li>
        <li>
          <a href="life.html">问题记录</a>
          <ul class="sub-nav">
            <li>
              <a href="life.html">日记</a>
            </li>
            <li>
              <a href="life.html">欣赏</a>
            </li>
            <li>
              <a href="life.html">程序人生</a>
            </li>
            <li>
              <a href="life.html">经典语录</a>
            </li>
          </ul>
        </li>
        <li>
          <a href="time.html">时间轴</a>
        </li>
        <li>
          <a href="gbook.html">留言</a>
        </li>
        <li>
          <a href="info.html">内容页</a>
        </li>
        <!--search begin-->
        <div id="search_bar" class="search_bar">
          <form
            id="searchform"
            action="[!--news.url--]e/search/index.php"
            method="post"
            name="searchform"
          >
            <input class="input" placeholder="想搜点什么呢..." type="text" name="keyboard" id="keyboard" />
            <input type="hidden" name="show" value="title" />
            <input type="hidden" name="tempid" value="1" />
            <input type="hidden" name="tbname" value="news" />
            <input type="hidden" name="Submit" value="搜索" />
            <span class="search_ico"></span>
          </form>
        </div>
        <!--search end-->
      </nav>
    </div>
    <!--menu end-->
    <!--mnav begin-->
    <div id="mnav">
      <h2>
        <a href="http://suhhai.cn/" class="mlogo">SueSea博客</a>
        <span class="navicon"></span>
      </h2>
      <dl class="list_dl">
        <dt class="list_dt">
          <a href="http://suhhai.cn/">网站首页</a>
        </dt>
        <dt class="list_dt">
          <a href="about.html">关于我</a>
        </dt>
        <dt class="list_dt">
          <a href="#">模板分享</a>
        </dt>
        <dd class="list_dd">
          <ul>
            <li>
              <a href="share.html">个人博客模板</a>
            </li>
            <li>
              <a href="share.html">国外Html5模板</a>
            </li>
            <li>
              <a href="share.html">企业网站模板</a>
            </li>
          </ul>
        </dd>
        <dt class="list_dt">
          <a href="#">学无止境</a>
        </dt>
        <dd class="list_dd">
          <ul>
            <li>
              <a href="list.html">心得笔记</a>
            </li>
            <li>
              <a href="list.html">CSS3|Html5</a>
            </li>
            <li>
              <a href="list.html">网站建设</a>
            </li>
            <li>
              <a href="list.html">推荐工具</a>
            </li>
            <li>
              <a href="list.html">JS实例索引</a>
            </li>
          </ul>
        </dd>
        <dt class="list_dt">
          <a href="#">慢生活</a>
        </dt>
        <dd class="list_dd">
          <ul>
            <li>
              <a href="life.html">日记</a>
            </li>
            <li>
              <a href="life.html">欣赏</a>
            </li>
            <li>
              <a href="life.html">程序人生</a>
            </li>
            <li>
              <a href="life.html">经典语录</a>
            </li>
          </ul>
        </dd>
        <dt class="list_dt">
          <a href="time.html">时间轴</a>
        </dt>
        <dt class="list_dt">
          <a href="gbook.html">留言</a>
        </dt>
      </dl>
    </div>
    <!--mnav end-->
  </header>
</template>

<script lang="ts">
import { Component, Prop, Vue } from "vue-property-decorator";

@Component
export default class HelloWorld extends Vue {

}
</script>

<style scoped>

</style>
