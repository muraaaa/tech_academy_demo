<template>
  <header>
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
                  <li class="dropdown btn-nav-menu"><a class="link" href="#">法人のお客様</a></li>
                  <li class="dropdown btn-nav-menu"><a class="link log-in" href="#">ログイン</a></li>
              </ul> 
          </div>
      </div>
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
</style>
