<template>
  <header>
    <div class="header">
        <div class="container">
          <div class="header-left">
            <a class="logo" href="#"><img src="./assets/logo.png"></a>
          </div>
          <div class="header-right">
            <ul class="nav-bar">
              <li class="dropdown btn-nav-menu">
                <a class="link" href="#">コース</a>
                <div class="dropdown-menu">
                  <div class="btn-nav-heading">
                    <h2>コース</h2>
                    <p>プログラミング・アプリ開発・デザインなど豊富なコースをご用意</p>
                  </div>
                  <div class="btn-nav-inner">
                    <div class="category">
                      <a href="#">プログラミング</a>
                    </div>
                    <ul>
                      <li>
                        <a class="btn-course">
                          <i class="fa fa-fw fa-diamond fa-l"></i>
                          Webアプリケーションコース
                        </a>
                      </li>
                      <li>
                        <a class="btn-course">
                          <i class="fa fa-fw fa-diamond fa-l"></i>
                          Webアプリケーションコース
                        </a>
                      </li>
                      <li>
                        <a class="btn-course">
                          <i class="fa fa-fw fa-diamond fa-l"></i>
                          Webアプリケーションコース
                        </a>
                      </li>
                      <li>
                        <a class="btn-course">
                          <i class="fa fa-fw fa-diamond fa-l"></i>
                          Webアプリケーションコース
                        </a>
                      </li> 
                    </ul>
                    <ul>
                      <li>
                        <a class="btn-course">
                          <i class="fa fa-fw fa-diamond fa-l"></i>
                          Webアプリケーションコース
                        </a>
                      </li>
                      <li>
                        <a class="btn-course">
                          <i class="fa fa-fw fa-diamond fa-l"></i>
                          Webアプリケーションコース
                        </a>
                      </li>
                      <li>
                        <a class="btn-course">
                          <i class="fa fa-fw fa-diamond fa-l"></i>
                          Webアプリケーションコース
                        </a>
                      </li>
                      <li>
                        <a class="btn-course">
                          <i class="fa fa-fw fa-diamond fa-l"></i>
                          Webアプリケーションコース
                        </a>
                      </li> 
                    </ul>
                  </div>
                </div>
              </li>
              <li class="dropdown btn-nav-menu"><a class="link" href="#">セット</a></li>
              <li class="dropdown btn-nav-menu"><a class="link" href="#">はじめての方へ</a></li>
              <li class="dropdown btn-nav-menu"><a class="link" href="#">転職サポート</a></li>
              <li class="dropdown btn-nav-menu"><a class="link for-company" href="#">法人のお客様</a></li>
              <li class="dropdown btn-nav-menu"><a class="link log-in" href="#">ログイン</a></li>
            </ul> 
          </div>
          <div id="nav-drawer">
            <input id="nav-input" class="nav-unshown" type="checkbox">
            <label id="nav-open" for="nav-input"><span></span></label>
            <label class="nav-unshown" id="nav-close" for="nav-input"></label>
            <div id="nav-content"></div>
          </div>
        </div>
    </div>

    <!-- 海の日キャンペーン -->
      <section id="campaign">
        <div class="campaign-wrapper"> 
          <img src="@/assets/title.png" alt="キャンペーン">
          <p class="campaign-text">
              ブートキャンプの8・１２・16・24週間プランのいずれかに
              お申し込みいただくと、<br>もれなく「はじめてのプログラミングコース」のカリキュラムをプレゼント！<br>海の日までのお得なキャンペーンです。
          </p>
          <p class="reminder">残りわずか！お早めに</p>
          <a class="campaigned-course" href="#">対象となるコースを見る</a>
        </div>
      </section>

     <!-- 受賞 -->
    <section class="advs">
        <div class="adv award">
            <img src="@/assets/awards.png" alt="受賞">
            <p>第１３回日本e-learning大賞<br>プログラミング教育特別部門賞</p>
        </div>
        <div class="adv payment">
            <img src="@/assets/bitcoin.png" alt="bit-coin">
            <p>ビットコインで<br>お支払いただけます</p>
        </div>
    </section>


    <!-- 無料キャンペーン -->
    <section class="free-of-charge">
        <a href="#" class="foc-topics">
            <div class="pick-up-topic">無料体験</div>
            <div class="topic">
                <img src="@/assets/無料体験.jpg" alt="無料体験">
                <div class="content">
                    <h2>ブートキャンプを無料体験してみよう！</h2>
                    <p>
                        実際の学習システムやカリキュラムをご覧いただけます。
                        受講をお考えの方はぜひご体験を！
                    </p>
                </div>
            </div>
        </a>
        <a href="#" class="foc-topics">
            <div class="pick-up-topic">コース診断</div>
            <div class="topic">
                <img src="@/assets/コース選び.jpg" alt="コース選び">
                <div class="content">
                    <h2>受講の目的別にオススメコースを紹介</h2>
                    <p>
                        どのコースがあっているかわからない！そんなあなたにオススメの
                        コースを紹介します。
                    </p>
                </div>
            </div>
        </a>
        <a href="#" class="foc-topics">
            <div class="pick-up-topic">新規コース</div>
            <div class="topic">
                <img src="@/assets/転職.jpg" alt="転職">
                <div class="content">
                    <h2>未経験から12週間でエンジニアを目指す</h2>
                    <p>
                        プログラミングを習得して転職が決まらなければ授業料を
                        全額返金する保証あり。
                    </p>
                </div>
            </div>
        </a>
        <a href="#" class="foc-topics last-topic">
            <div class="pick-up-topic">受け放題</div>
            <div class="topic">
                <img src="@/assets/受け放題.jpg" alt="受け放題">
                <div class="content">
                    <h2>コースを受講し放題！最大160万円相当お得！</h2>
                    <p>
                        受け放題はブートキャンプのコースを24時間受講し放題！
                        今ならメンタリング８回分が無料！
                    </p>
                </div>
            </div>
        </a>
    </section>

    <!-- Trial -->
    <section class="trial">
        <div class="explanation">
            <img src="@/assets/top-trial-ill-0b8d6a09a9ee2ae66bc314cd954b019fade0a94471be104a0dcd855cad1ce896.png">
            <div class="text-wrap">
                <h2 class="section-title"><span>プログラミング無料体験</span>やってます</h2>
                <p>メンターサポートの体験・カリキュラムの閲覧・プログラミングの体験</p>
            </div>    
            <a href="#" class="btn">詳しく見る</a>
        </div>
    </section>


    <!-- ブートキャンプ -->
    <section class="boot-camp">
        <div class="boot-camp-container">
            <h2 class="title">ブートキャンプ</h2>
            <p>現役のプロのマンツーマンメンタリングで実践的スキルを習得</p>
        </div>
        <section class="sub-section">
            <p class="title-border">プログラミング</p>
            <div class="courses">
                <div class="course-wrapper">
                    <a href="#" class="course Ruby">
                        <i class="fa fa-diamond"></i>
                        <h3>Webアプリケーション<span>コース</span></h3>
                        <div class="deadline">
                            <i class="fa fa-clock-o" aria-hidden="true"></i>
                            申込締切（本日締切）<br>
                            <span>7</span>月<span>21</span>日26時
                        </div>
                    </a>
                </div>
                <div class="course-wrapper">
                    <a href="#" class="course PHP">
                        <i class="fa fa-diamond"></i>
                        <h3>PHP/Laravel<span>コース</span></h3>
                        <div class="deadline">
                            申込締切（本日締切）<br>
                            <span>7</span>月<span>21</span>日26時
                        </div>
                    </a>
                </div>
                <div class="course-wrapper">
                    <a href="#" class="course Java">
                        <i class="fa fa-diamond"></i>
                        <h3>Java<span>コース</span></h3>
                        <div class="deadline">
                            <p>申込締切（本日締切）<br><span>7</span>月<span>21</span>日26時</p>
                        </div>
                    </a>
                </div>
                <div class="course-wrapper">
                    <a href="#" class="course HTML">
                        <i class="fa fa-diamond"></i>
                        <h3>フロントエンド<span>コース</span></h3>
                        <div class="deadline">
                            <p>申込締切（本日締切）<br><span>7</span>月<span>21</span>日26時</p>
                        </div>
                    </a>
                </div>
            </div>
        </section>
    </section>


    <!-- Techacadyとは -->
    <section id="abstract">
        <div class="abst-wrapper">  
            <h2 class="title">TechAcademyとは？</h2>
            <p>
                プログラミングやアプリ開発を学べるオンラインスクール。<br>
                1人では続かない方のための短期集中プログラム「オンラインブートキャンプ」を開催。<br>
                現役のプロのサポートと独自の学習システムで短期間で成長いただけます。
            </p>
        </div>
        <div class="result-wrapper">
            <h3 class="result">600社、30,000名を超える教育実績</h3>
        </div>
        <img src="@/assets/company-logos.jpg" alt="company logo">
        <div class="iframe-wrapper">
            <a class="iframe" href="#">
                <div class="box">
                    <iframe  src="https://www.youtube.com/embed/XwJoiznVrps" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    <!-- width="560" height="315" -->
                    <div class="cm-text">
                        <h2 class="cm-text-title">TechAcademyのテレビCM<br>「未来の自分編」</h2>
                        <p class="cm-text-detail">現在と未来の自分が繰り広げる会話劇を是非ご覧ください</p>
                    </div>
                </div>
            </a>
        </div>
    </section>



<!-- 他スクールとの比較 -->
    <section id="comparison">
        <div class="comparison-wrapper">
            <div class="title-wrapper">
                <h2>他スクールとの比較</h2>
                <p>他のスクールと比較するとTechAcademyの<br>
                    圧倒的なコストパフォーマンスをご確認いただけます</p>
            </div>
            <table class="comparison-table">
            <!--  border="1" width="93%" align="center" -->
                <thead>
                    <tr>
                        <th class="empty"></th>
                        <th class="Techacademy"><img src="@/assets/logo-8511a75ca8fe7f18d0d46acfd2d0eb51b7b5a5c5786e12a1c6781f64bbbd0e8a.png" alt="TechAcademy"></th>
                        <th class="Others">A社</th>
                        <th class="Others">B社</th>
                        <th class="Others">C社</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td class="column">料金</td>
                        <td class="Techacademy-detail">99,000円〜<br><span>※はじめてのプログラミングコース4週間の料金</span></td>
                        <td>148,000円</td>
                        <td>入会金128,000円<br>月額12,800円</td>
                        <td>入会金18,000円<br>月額96,000円</td>
                    </tr>
                    <tr>
                        <td class="column">マンツーマンレッスン<br>メンタリング</td>
                        <td class="Techacademy-detail last"><i class="fa fa-circle-o" aria-hidden="true"></i></td>
                        <td><i class="fa fa-circle-o" aria-hidden="true"></i></td>
                        <td><i class="fa fa-times" aria-hidden="true"></i></td>
                        <td><i class="fa fa-circle-o" aria-hidden="true"></i></td>
                    </tr>
                </tbody>
            </table>
        </div>
    </section>


    <!-- footer -->
    <footer id="footer">
        <!-- <img src="/img/media-logos.png" alt="media-logo"> -->
        <div class="footer-container">
            <div class="footer-menu">
                <ul>
                    <li><a href="#">お問い合わせ</a></li>
                    <li><a href="#">よくあるご質問</a></li>
                </ul>
            </div>
            <div class="company-details">
                <ul>
                    <li><a href="#">運営会社</a></li>
                    <li><a href="#">利用規約</a></li>
                </ul>
                <div class="social-network">
                    <a href="#"><i class="fa fa-facebook" aria-hidden="true"></i></a>
                    <a href="#"><i class="fa fa-twitter" aria-hidden="true"></i></a>
                </div>
            </div>
        </div>
    </footer>
  </header>

</template>

<script>

export default {
  name: 'app',
}
</script>

<style lang="scss">
@import './assets/style/reset';
@import './assets/style/common';
@import './assets/style/header';
@import './assets/style/campaign';
@import './assets/style/advs';
@import './assets/style/foc';
@import './assets/style/trial';
@import './assets/style/boot-camp';
@import './assets/style/abstract';
@import './assets/style/comparison';

</style>
