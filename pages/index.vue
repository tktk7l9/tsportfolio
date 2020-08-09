<template>
  <div class="page-index">
    <section class="about">
      <h2 class="section-title">Takuya Saito</h2>
      <ArticleBody>
        <img src="~/assets/images/portrait.jpg" alt="Takuya Saito" />
        <p>
          システムエンジニア。
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
      <h2 class="section-title">経歴</h2>
      <ArticleBody>
        <p>学生時代</p>
        <ul>
          <li>
            2012/04
            <a
              href="https://www.rikkyo.ac.jp/undergraduate/cp/department_02.html"
              target="_blank"
              >立教大学 現代心理学部 映像身体学科</a
            >
            に入学
          </li>
          <li>
            2017/10
            <a href="topgate.co.jp" target="_blank">株式会社トラストリッジ</a>
            に動画編集者としてインターン
          </li>
        </ul>
        <br />
        <p>職歴</p>
        <ul>
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
