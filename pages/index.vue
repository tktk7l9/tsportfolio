<template>
  <div class="page-index">
    <section class="about">
      <h2 class="section-title">Takuya Saito</h2>
      <ArticleBody>
        <p>
          システムエンジニア。
        </p>
        <p>
          <a href="https://twitter.com/tktk7l9" target="_blank">Twitter</a>
          <a href="https://github.com/tktk7l9" target="_blank">GitHub</a>
          <a
            href="https://www.linkedin.com/in/%E6%8B%93%E4%B9%9F-%E9%BD%8B%E8%97%A4-2290b8187/"
            target="_blank"
            >LinkedIn</a
          >
        </p>
      </ArticleBody>
    </section>

    <section class="works">
      <h2 class="section-title">My Skills</h2>
      <ArticleBody>
        <ul>
          <li>HTML5</li>
          <li>CSS3</li>
          <li>JavaScript</li>
          <li>Python3</li>
          <li>Go</li>
          <li>Java</li>
          <li>Dart</li>
          <li>
            GCP
            <p>
              BigQuery, Cloud Strage, App Engine, Cloud Engine, Cloud Functions,
              IAM
            </p>
          </li>
          <li>
            TOEIC
            <p>745点</p>
          </li>
          <li>
            Other
            <p>
              Scss, Vue.js, Nuxt.js, GAS, Flutter, Linux, iOS, Android,
              Firebase, Contentful, Netlify
            </p>
          </li>
        </ul>
      </ArticleBody>
    </section>

    <section class="works">
      <h2 class="section-title">My Hisotry</h2>
      <ArticleBody>
        <ul>
          <li>
            2017/10
            <a href="topgate.co.jp" target="_blank">株式会社トラストリッジ</a>
            に動画編集者としてインターン
          </li>
          <li>
            2018/03
            <a
              href="https://www.rikkyo.ac.jp/undergraduate/cp/department_02.html"
              target="_blank"
              >立教大学 現代心理学部 映像身体学科</a
            >
            卒業
          </li>
          <li>
            2018/04
            <a
              href="https://www.ibm.com/jp-ja/about/subsidiaries/ijds"
              target="_blank"
              >(旧)日本IBMソリューションサービス株式会社(ISOL)</a
            >
            (現)日本IBMデジタルサービス株式会社(IJDS) にSEとして新卒入社
          </li>
          <li>
            2019/11
            <a href="https://www.trustridge.jp/" target="_blank"
              >株式会社トップゲート</a
            >
            にSEとして転職
          </li>
        </ul>
      </ArticleBody>
    </section>
  </div>
</template>

<script>
import ArticleBody from "~/components/common/ArticleBody";

export default {
  components: {
    ArticleBody,
  },
};
</script>
