<template>
  <div>
    <h4 class="font-weight-bold py-3 mb-4">
      <span class="text-muted font-weight-light">UI elements /</span> Thumbnails
    </h4>

    <div class="row">
      <div class="col-sm-6 col-md-6 col-xl-3 mb-4">
        <a href="javascript:void(0)" class="img-thumbnail">
          <img :src="`${baseUrl}img/bg/1.jpg`" alt class="img-fluid">
        </a>
      </div>
      <div class="col-sm-6 col-md-6 col-xl-3 mb-4">
        <a href="javascript:void(0)" class="img-thumbnail">
          <img :src="`${baseUrl}img/bg/2.jpg`" alt class="img-fluid">
        </a>
      </div>
      <div class="col-sm-6 col-md-6 col-xl-3 mb-4">
        <a href="javascript:void(0)" class="img-thumbnail">
          <img :src="`${baseUrl}img/bg/3.jpg`" alt class="img-fluid">
        </a>
      </div>
      <div class="col-sm-6 col-md-6 col-xl-3 mb-4">
        <a href="javascript:void(0)" class="img-thumbnail">
          <img :src="`${baseUrl}img/bg/4.jpg`" alt class="img-fluid">
        </a>
      </div>
    </div>

    <h6 class="pb-1 mt-5 mb-4">With overlay</h6>

    <div class="row">
      <div class="col-sm-6 col-md-6 col-xl-3 mb-4">
        <a href="javascript:void(0)" class="img-thumbnail">
          <div class="img-thumbnail-overlay bg-dark opacity-25"></div>
          <img :src="`${baseUrl}img/bg/5.jpg`" alt class="img-fluid">
        </a>
      </div>
      <div class="col-sm-6 col-md-6 col-xl-3 mb-4">
        <a href="javascript:void(0)" class="img-thumbnail">
          <div class="img-thumbnail-overlay bg-primary opacity-50"></div>
          <img :src="`${baseUrl}img/bg/6.jpg`" alt class="img-fluid">
        </a>
      </div>
      <div class="col-sm-6 col-md-6 col-xl-3 mb-4">
        <a href="javascript:void(0)" class="img-thumbnail">
          <div class="img-thumbnail-overlay bg-success opacity-25"></div>
          <img :src="`${baseUrl}img/bg/7.jpg`" alt class="img-fluid">
        </a>
      </div>
      <div class="col-sm-6 col-md-6 col-xl-3 mb-4">
        <a href="javascript:void(0)" class="img-thumbnail">
          <div class="img-thumbnail-overlay bg-white opacity-50"></div>
          <img :src="`${baseUrl}img/bg/8.jpg`" alt class="img-fluid">
        </a>
      </div>
    </div>

    <h6 class="pb-1 mt-5 mb-4">With overlay and content</h6>

    <div class="row">
      <div class="col-sm-6 col-md-6 col-xl-3 mb-4">
        <a href="javascript:void(0)" class="img-thumbnail">
          <span class="img-thumbnail-overlay bg-dark opacity-25"></span>
          <span class="img-thumbnail-content display-4 text-white">
            <i class="ion ion-ios-search"></i>
          </span>
          <img :src="`${baseUrl}img/bg/9.jpg`" alt class="img-fluid">
        </a>
      </div>
      <div class="col-sm-6 col-md-6 col-xl-3 mb-4">
        <a href="javascript:void(0)" class="img-thumbnail">
          <span class="img-thumbnail-overlay bg-primary opacity-50"></span>
          <span class="img-thumbnail-content display-4 text-white">
            <i class="ion ion-ios-search"></i>
          </span>
          <img :src="`${baseUrl}img/bg/10.jpg`" alt class="img-fluid">
        </a>
      </div>
      <div class="col-sm-6 col-md-6 col-xl-3 mb-4">
        <a href="javascript:void(0)" class="img-thumbnail">
          <span class="img-thumbnail-overlay bg-success opacity-25"></span>
          <span class="img-thumbnail-content display-4 text-white">
            <i class="ion ion-ios-search"></i>
          </span>
          <img :src="`${baseUrl}img/bg/11.jpg`" alt class="img-fluid">
        </a>
      </div>
      <div class="col-sm-6 col-md-6 col-xl-3 mb-4">
        <a href="javascript:void(0)" class="img-thumbnail">
          <span class="img-thumbnail-overlay bg-white opacity-75"></span>
          <span class="img-thumbnail-content display-4 text-secondary">
            <i class="ion ion-ios-search"></i>
          </span>
          <img :src="`${baseUrl}img/bg/12.jpg`" alt class="img-fluid">
        </a>
      </div>
    </div>

    <h6 class="pb-1 mt-5 mb-4">Shadow on hover</h6>

    <div class="row">
      <div class="col-sm-6 col-md-6 col-xl-3 mb-4">
        <a href="javascript:void(0)" class="img-thumbnail img-thumbnail-shadow">
          <span class="img-thumbnail-overlay bg-white opacity-25"></span>
          <img :src="`${baseUrl}img/bg/13.jpg`" alt class="img-fluid">
        </a>
      </div>
      <div class="col-sm-6 col-md-6 col-xl-3 mb-4">
        <a href="javascript:void(0)" class="img-thumbnail img-thumbnail-shadow">
          <span class="img-thumbnail-overlay bg-white opacity-25"></span>
          <img :src="`${baseUrl}img/bg/14.jpg`" alt class="img-fluid">
        </a>
      </div>
      <div class="col-sm-6 col-md-6 col-xl-3 mb-4">
        <a href="javascript:void(0)" class="img-thumbnail img-thumbnail-shadow">
          <span class="img-thumbnail-overlay bg-white opacity-25"></span>
          <img :src="`${baseUrl}img/bg/15.jpg`" alt class="img-fluid">
        </a>
      </div>
      <div class="col-sm-6 col-md-6 col-xl-3 mb-4">
        <a href="javascript:void(0)" class="img-thumbnail img-thumbnail-shadow">
          <span class="img-thumbnail-overlay bg-white opacity-25"></span>
          <img :src="`${baseUrl}img/bg/16.jpg`" alt class="img-fluid">
        </a>
      </div>
    </div>

    <h6 class="pb-1 mt-5 mb-4">Zoom In animation on hover</h6>

    <div class="row">
      <div class="col-sm-6 col-md-6 col-xl-3 mb-4">
        <a href="javascript:void(0)" class="img-thumbnail img-thumbnail-zoom-in">
          <span class="img-thumbnail-overlay bg-dark opacity-25"></span>
          <span class="img-thumbnail-content display-4 text-white">
            <i class="ion ion-ios-search"></i>
          </span>
          <img :src="`${baseUrl}img/bg/1.jpg`" alt class="img-fluid">
        </a>
      </div>
      <div class="col-sm-6 col-md-6 col-xl-3 mb-4">
        <a href="javascript:void(0)" class="img-thumbnail img-thumbnail-zoom-in">
          <span class="img-thumbnail-overlay bg-primary opacity-50"></span>
          <span class="img-thumbnail-content display-4 text-white">
            <i class="ion ion-ios-search"></i>
          </span>
          <img :src="`${baseUrl}img/bg/2.jpg`" alt class="img-fluid">
        </a>
      </div>
      <div class="col-sm-6 col-md-6 col-xl-3 mb-4">
        <a href="javascript:void(0)" class="img-thumbnail img-thumbnail-zoom-in">
          <span class="img-thumbnail-overlay bg-success opacity-25"></span>
          <span class="img-thumbnail-content display-4 text-white">
            <i class="ion ion-ios-search"></i>
          </span>
          <img :src="`${baseUrl}img/bg/3.jpg`" alt class="img-fluid">
        </a>
      </div>
      <div class="col-sm-6 col-md-6 col-xl-3 mb-4">
        <a href="javascript:void(0)" class="img-thumbnail img-thumbnail-zoom-in">
          <span class="img-thumbnail-overlay bg-white opacity-75"></span>
          <span class="img-thumbnail-content display-4 text-secondary">
            <i class="ion ion-ios-search"></i>
          </span>
          <img :src="`${baseUrl}img/bg/4.jpg`" alt class="img-fluid">
        </a>
      </div>
    </div>

  </div>
</template>

<script>
export default {
  name: 'ui-thumbnails',
  metaInfo: {
    title: 'Thumbnails - UI elements'
  }
}
</script>
