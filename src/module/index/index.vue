<template>
  <div>
    <div class="site-nav-bg">
      <div class="site-nav w1200">
        <p class="sn-back-home">
          <i class="layui-icon layui-icon-home"></i>
          <a href="index.html">首页</a>
        </p>
        <div class="sn-quick-menu">
          <div class="login"><a href="/login.html">登录</a></div>
        <div class="sp-cart"><a href="shopcart.html">购物车</a><span>2</span></div>
        </div>
      </div>
    </div>


    <div class="header">
      <div class="headerLayout w1200">
        <div class="headerCon">
          <h1 class="mallLogo">
            <a href="#" title="母婴商城">
              <img src="@/assets/img/logo.png">
            </a>
          </h1>
          <div class="mallSearch">
            <form action="" class="layui-form" novalidate>
              <input type="text" name="title" required  lay-verify="required" autocomplete="off" class="layui-input" placeholder="请输入需要的商品">
              <button class="layui-btn" lay-submit lay-filter="formDemo">
                  <i class="layui-icon layui-icon-search"></i>
              </button>
              <input type="hidden" name="" value="">
            </form>
          </div>
        </div>
      </div>
    </div>


    <div class="content">
      <div class="main-nav">
        <div class="inner-cont0">
          <div class="inner-cont1 w1200">
            <div class="inner-cont2">
              <a href="commodity.html" class="active">所有商品</a>
              <a href="buytoday.html">今日团购</a>
              <a href="information.html">母婴资讯</a>
              <a href="about.html">关于我们</a>
            </div>
          </div>
        </div>
      </div>
      <div class="category-con">
        <div class="category-inner-con w1200">
          <div class="category-type">
            <h3>全部分类</h3>
          </div>
          <div class="category-tab-content">
            <div class="nav-con">
              <ul class="normal-nav layui-clear">
                <li class="nav-item">
                  <div class="title">奶粉辅食</div>
                  <p><a href="#">奶粉</a><a href="#">捕食</a><a href="#">营养品</a></p>
                  <i class="layui-icon layui-icon-right"></i>
                </li>
                <li class="nav-item">
                  <div class="title">纸尿裤</div>
                  <p><a href="#">纸尿裤</a><a href="#">婴儿湿巾</a></p>
                  <i class="layui-icon layui-icon-right"></i>
                </li>
                <li class="nav-item">
                  <div class="title">洗护用品</div>
                  <p><a href="#">母婴洗护用品</a><a href="#">孕婴童用品</a></p>
                  <i class="layui-icon layui-icon-right"></i>
                </li>
                <li class="nav-item">
                  <div class="title">儿童玩具</div>
                  <p><a href="#">婴幼玩具</a><a href="#">遥控玩具</a><a href="#">积木拼插</a></p>
                  <i class="layui-icon layui-icon-right"></i>
                </li>
                <li class="nav-item">
                  <div class="title">车窗座椅</div>
                  <p><a href="#">婴儿推车</a><a href="#">儿童安全座骑</a></p>
                  <i class="layui-icon layui-icon-right"></i>
                </li>
                <li class="nav-item">
                  <div class="title">儿童童鞋</div>
                  <p><a href="#">童装</a><a href="#">童鞋</a><a href="#">婴童内衣及配饰</a></p>
                  <i class="layui-icon layui-icon-right"></i>
                </li>
                <li class="nav-item">
                  <div class="title">儿童图片</div>
                  <p><a href="#">0-2岁</a><a href="#">早教启蒙</a><a href="#">孕产育儿</a></p>
                  <i class="layui-icon layui-icon-right"></i>
                </li>
                <li class="nav-item nobor">
                  <div class="title">孕妈专区</div>
                  <p><a href="#">孕妇装</a><a href="#">背婴带</a><a href="#">母婴服务</a></p>
                  <i class="layui-icon layui-icon-right"></i>
                </li>
              </ul>
            </div>
          </div>
        </div>
        <div class="category-banner">
          <div class="w1200">
            <img src="@/assets/img/banner1.jpg">
          </div>
        </div>
      </div>
      <div class="floors">
        <div class="sk">
          <div class="sk_inner w1200">
            <div class="sk_hd">
              <a href="javascript:;">
                <img src="@/assets/img/s_img1.jpg">
              </a>
            </div>
            <div class="sk_bd">
              <div class="layui-carousel" id="test1">
                <div carousel-item>
                  <div class="item-box">
                    <div class="item">
                      <a href="javascript:;"><img src="@/assets/img/s_img2.jpg"></a>
                      <div class="title">宝宝五彩袜棉质舒服</div>
                      <div class="price">
                        <span>￥49.00</span>
                        <del>￥99.00</del>
                      </div>
                    </div>
                    <div class="item">
                      <a href="javascript:;"><img src="@/assets/img/s_img3.jpg"></a>
                      <div class="title">宝宝五彩袜棉质舒服</div>
                      <div class="price">
                        <span>￥49.00</span>
                        <del>￥99.00</del>
                      </div>
                    </div>
                    <div class="item">
                      <a href="javascript:;"><img src="@/assets/img/s_img4.jpg"></a>
                      <div class="title">宝宝五彩袜棉质舒服</div>
                      <div class="price">
                        <span>￥49.00</span>
                        <del>￥99.00</del>
                      </div>
                    </div>
                    <div class="item">
                      <a href="javascript:;"><img src="@/assets/img/s_img5.jpg"></a>
                      <div class="title">宝宝五彩袜棉质舒服</div>
                      <div class="price">
                        <span>￥49.00</span>
                        <del>￥99.00</del>
                      </div>
                    </div>
                  </div>
                  <div class="item-box">
                    <div class="item">
                      <a href="javascript:;"><img src="@/assets/img/s_img2.jpg"></a>
                      <div class="title">宝宝五彩袜棉质舒服</div>
                      <div class="price">
                        <span>￥49.00</span>
                        <del>￥99.00</del>
                      </div>
                    </div>
                    <div class="item">
                      <a href="javascript:;"><img src="@/assets/img/s_img3.jpg"></a>
                      <div class="title">宝宝五彩袜棉质舒服</div>
                      <div class="price">
                        <span>￥49.00</span>
                        <del>￥99.00</del>
                      </div>
                    </div>
                    <div class="item">
                      <a href="javascript:;"><img src="@/assets/img/s_img4.jpg"></a>
                      <div class="title">宝宝五彩袜棉质舒服</div>
                      <div class="price">
                        <span>￥49.00</span>
                        <del>￥99.00</del>
                      </div>
                    </div>
                    <div class="item">
                      <a href="javascript:;"><img src="@/assets/img/s_img5.jpg"></a>
                      <div class="title">宝宝五彩袜棉质舒服</div>
                      <div class="price">
                        <span>￥49.00</span>
                        <del>￥99.00</del>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>






      <div class="hot-recommend-con">
         <div class="hot-con1 w1200 layui-clear">
            <div class="item">
              <h4>热销推荐</h4>
              <div class="big-img">
                <a href="javascript:;"><img src="@/assets/img/hot1.png"></a>
              </div>
              <div class="small-img">
                <a href="javascript:;"><img src="@/assets/img/hot2.png" alt=""></a>
              </div>
            </div>
            <div class="item">
              <div class="top-img">
                <a href="javascript:;"><img src="@/assets/img/hot5.jpg"></a>
              </div>
              <div class="bottom-img">
                <a href="javascript:;"><img src="@/assets/img/hot6.jpg"></a>
                <a class="baby-cream" href="javascript:;"><img src="@/assets/img/hot7.jpg"></a>
              </div>
            </div>
            <div class="item item1 margin0 padding0">
              <a href="javascript:;"><img src="@/assets/img/hot8.jpg"></a>
              <a href="javascript:;"><img class="btm-img" src="@/assets/img/hot9.jpg"></a>
            </div>
        </div>
      </div>



      <div class="product-cont w1200" id="product-cont">
        <div class="product-item product-item1 layui-clear">
          <div class="left-title">
            <h4><i>1F</i></h4>
            <img src="@/assets/img/icon_gou.png">
            <h5>宝宝服饰</h5>
          </div>
          <div class="right-cont">
            <a href="javascript:;" class="top-img"><img src="@/assets/img/img12.jpg" alt=""></a>
            <div class="img-box">
              <a href="javascript:;"><img src="@/assets/img/s_img7.jpg"></a>
              <a href="javascript:;"><img src="@/assets/img/s_img8.jpg"></a>
              <a href="javascript:;"><img src="@/assets/img/s_img9.jpg"></a>
              <a href="javascript:;"><img src="@/assets/img/s_img10.jpg"></a>
              <a href="javascript:;"><img src="@/assets/img/s_img11.jpg"></a>
            </div>
          </div>
        </div>
        <div class="product-item product-item2 layui-clear">
          <div class="left-title">
            <h4><i>2F</i></h4>
            <img src="@/assets/img/icon_gou.png">
            <h5>奶粉辅食</h5>
          </div>
          <div class="right-cont">
            <a href="javascript:;" class="top-img"><img src="@/assets/img/img12.jpg" alt=""></a>
            <div class="img-box">
              <a href="javascript:;"><img src="@/assets/img/s_img7.jpg"></a>
              <a href="javascript:;"><img src="@/assets/img/s_img8.jpg"></a>
              <a href="javascript:;"><img src="@/assets/img/s_img9.jpg"></a>
              <a href="javascript:;"><img src="@/assets/img/s_img10.jpg"></a>
              <a href="javascript:;"><img src="@/assets/img/s_img11.jpg"></a>
            </div>
          </div>
        </div>
        <div class="product-item product-item3 layui-clear">
          <div class="left-title">
            <h4><i>3F</i></h4>
            <img src="@/assets/img/icon_gou.png">
            <h5>宝宝用品</h5>
          </div>
          <div class="right-cont">
            <a href="javascript:;" class="top-img"><img src="@/assets/img/img12.jpg" alt=""></a>
            <div class="img-box">
              <a href="javascript:;"><img src="@/assets/img/s_img7.jpg"></a>
              <a href="javascript:;"><img src="@/assets/img/s_img8.jpg"></a>
              <a href="javascript:;"><img src="@/assets/img/s_img9.jpg"></a>
              <a href="javascript:;"><img src="@/assets/img/s_img10.jpg"></a>
              <a href="javascript:;"><img src="@/assets/img/s_img11.jpg"></a>
            </div>
          </div>
        </div>
      </div>

      <div class="product-list-box" id="product-list-box">
        <div class="product-list-cont w1200">
          <h4>更多推荐</h4>
          <div class="product-item-box layui-clear">
            <div class="list-item">
              <a href="javascript:;"><img src="@/assets/img/more1.jpg"></a>
              <p>时尚宝宝小黄鸭T恤纯棉耐脏多色可选0-2岁宝宝</p>
              <span>￥100.00</span>
            </div>
            <div class="list-item">
              <a href="javascript:;"><img src="@/assets/img/more2.jpg"></a>
              <p>时尚宝宝小黄鸭T恤纯棉耐脏多色可选0-2岁宝宝</p>
              <span>￥100.00</span>
            </div>
            <div class="list-item">
              <a href="javascript:;"><img src="@/assets/img/more3.jpg"></a>
              <p>时尚宝宝小黄鸭T恤纯棉耐脏多色可选0-2岁宝宝</p>
              <span>￥100.00</span>
            </div>
            <div class="list-item">
              <a href="javascript:;"><img src="@/assets/img/more1.jpg"></a>
              <p>时尚宝宝小黄鸭T恤纯棉耐脏多色可选0-2岁宝宝</p>
              <span>￥100.00</span>
            </div>
            <div class="list-item">
              <a href="javascript:;"><img src="@/assets/img/more2.jpg"></a>
              <p>时尚宝宝小黄鸭T恤纯棉耐脏多色可选0-2岁宝宝</p>
              <span>￥100.00</span>
            </div>
            <div class="list-item">
              <a href="javascript:;"><img src="@/assets/img/more3.jpg"></a>
              <p>时尚宝宝小黄鸭T恤纯棉耐脏多色可选0-2岁宝宝</p>
              <span>￥100.00</span>
            </div>
            <div class="list-item">
              <a href="javascript:;"><img src="@/assets/img/more1.jpg"></a>
              <p>时尚宝宝小黄鸭T恤纯棉耐脏多色可选0-2岁宝宝</p>
              <span>￥100.00</span>
            </div>
            <div class="list-item">
              <a href="javascript:;"><img src="@/assets/img/more2.jpg"></a>
              <p>时尚宝宝小黄鸭T恤纯棉耐脏多色可选0-2岁宝宝</p>
              <span>￥100.00</span>
            </div>
            <div class="list-item">
              <a href="javascript:;"><img src="@/assets/img/more3.jpg"></a>
              <p>时尚宝宝小黄鸭T恤纯棉耐脏多色可选0-2岁宝宝</p>
              <span>￥100.00</span>
            </div>
            <div class="list-item">
              <a href="javascript:;"><img src="@/assets/img/more1.jpg"></a>
              <p>时尚宝宝小黄鸭T恤纯棉耐脏多色可选0-2岁宝宝</p>
              <span>￥100.00</span>
            </div>
            <div class="list-item">
              <a href="javascript:;"><img src="@/assets/img/more2.jpg"></a>
              <p>时尚宝宝小黄鸭T恤纯棉耐脏多色可选0-2岁宝宝</p>
              <span>￥100.00</span>
            </div>
            <div class="list-item">
              <a href="javascript:;"><img src="@/assets/img/more3.jpg"></a>
              <p>时尚宝宝小黄鸭T恤纯棉耐脏多色可选0-2岁宝宝</p>
              <span>￥100.00</span>
            </div>
            <div class="list-item">
              <a href="javascript:;"><img src="@/assets/img/more1.jpg"></a>
              <p>时尚宝宝小黄鸭T恤纯棉耐脏多色可选0-2岁宝宝</p>
              <span>￥100.00</span>
            </div>
            <div class="list-item">
              <a href="javascript:;"><img src="@/assets/img/more2.jpg"></a>
              <p>时尚宝宝小黄鸭T恤纯棉耐脏多色可选0-2岁宝宝</p>
              <span>￥100.00</span>
            </div>
            <div class="list-item">
              <a href="javascript:;"><img src="@/assets/img/more3.jpg"></a>
              <p>时尚宝宝小黄鸭T恤纯棉耐脏多色可选0-2岁宝宝</p>
              <span>￥100.00</span>
            </div>
            <div class="list-item">
              <a href="javascript:;"><img src="@/assets/img/more1.jpg"></a>
              <p>时尚宝宝小黄鸭T恤纯棉耐脏多色可选0-2岁宝宝</p>
              <span>￥100.00</span>
            </div>
            <div class="list-item">
              <a href="javascript:;"><img src="@/assets/img/more2.jpg"></a>
              <p>时尚宝宝小黄鸭T恤纯棉耐脏多色可选0-2岁宝宝</p>
              <span>￥100.00</span>
            </div>
            <div class="list-item">
              <a href="javascript:;"><img src="@/assets/img/more3.jpg"></a>
              <p>时尚宝宝小黄鸭T恤纯棉耐脏多色可选0-2岁宝宝</p>
              <span>￥100.00</span>
            </div>
            <div class="list-item">
              <a href="javascript:;"><img src="@/assets/img/more1.jpg"></a>
              <p>时尚宝宝小黄鸭T恤纯棉耐脏多色可选0-2岁宝宝</p>
              <span>￥100.00</span>
            </div>
            <div class="list-item">
              <a href="javascript:;"><img src="@/assets/img/more2.jpg"></a>
              <p>时尚宝宝小黄鸭T恤纯棉耐脏多色可选0-2岁宝宝</p>
              <span>￥100.00</span>
            </div>
            <div class="list-item">
              <a href="javascript:;"><img src="@/assets/img/more3.jpg"></a>
              <p>时尚宝宝小黄鸭T恤纯棉耐脏多色可选0-2岁宝宝</p>
              <span>￥100.00</span>
            </div>
            <div class="list-item">
              <a href="javascript:;"><img src="@/assets/img/more1.jpg"></a>
              <p>时尚宝宝小黄鸭T恤纯棉耐脏多色可选0-2岁宝宝</p>
              <span>￥100.00</span>
            </div>
            <div class="list-item">
              <a href="javascript:;"><img src="@/assets/img/more2.jpg"></a>
              <p>时尚宝宝小黄鸭T恤纯棉耐脏多色可选0-2岁宝宝</p>
              <span>￥100.00</span>
            </div>
            <div class="list-item">
              <a href="javascript:;"><img src="@/assets/img/more3.jpg"></a>
              <p>时尚宝宝小黄鸭T恤纯棉耐脏多色可选0-2岁宝宝</p>
              <span>￥100.00</span>
            </div>
            <div class="list-item">
              <a href="javascript:;"><img src="@/assets/img/more1.jpg"></a>
              <p>时尚宝宝小黄鸭T恤纯棉耐脏多色可选0-2岁宝宝</p>
              <span>￥100.00</span>
            </div>
            <div class="list-item">
              <a href="javascript:;"><img src="@/assets/img/more2.jpg"></a>
              <p>时尚宝宝小黄鸭T恤纯棉耐脏多色可选0-2岁宝宝</p>
              <span>￥100.00</span>
            </div>
            <div class="list-item">
              <a href="javascript:;"><img src="@/assets/img/more3.jpg"></a>
              <p>时尚宝宝小黄鸭T恤纯棉耐脏多色可选0-2岁宝宝</p>
              <span>￥100.00</span>
            </div>
          </div>
        </div>
      </div>
    </div>

    


  </div>
</template>


<script>
  // import layui from '@/assets/layui/layui.js'
  console.log($)
  console.log(layui)
  export default {
  }
</script>

<style>
  
</style>
