# Swiper 使用方法
# 1.首先加载插件，需要用到的文件有swiper-bundle.min.js和swiper-bundle.min.css文件
# 不同Swiper版本用到的文件名略有不同。可下载Swiper文件或使用CDN
# <link rel="stylesheet" href="dist/css/swiper-bundle.min.css">
# <script src="dist/js/swiper-bundle.min.js"></script>
# 2.复制HTML内容。

# <div class="swiper-container">
    # <div class="swiper-wrapper">
        # <div class="swiper-slide">Slide 1</div>
        # <div class="swiper-slide">Slide 2</div>
        # <div class="swiper-slide">Slide 3</div>
    # </div>
    # <!-- 如果需要分页器 -->
    # <div class="swiper-pagination"></div>
    
    # <!-- 如果需要导航按钮 -->
    # <div class="swiper-button-prev"></div>
    # <div class="swiper-button-next"></div>
    
    # <!-- 如果需要滚动条 -->
    # <div class="swiper-scrollbar"></div>
# </div>
# 3.复制Script的代码


# <script>        
  # var mySwiper = new Swiper ('.swiper-container', {
    # direction: 'vertical', // 垂直切换选项
    # loop: true, // 循环模式选项
    
    # // 如果需要分页器
    # pagination: {
      # el: '.swiper-pagination',
    # },
    
    # // 如果需要前进后退按钮
    # navigation: {
      # nextEl: '.swiper-button-next',
      # prevEl: '.swiper-button-prev',
    # },
    
    # // 如果需要滚动条
    # scrollbar: {
      # el: '.swiper-scrollbar',
    # },
  # })        
  # </script>

