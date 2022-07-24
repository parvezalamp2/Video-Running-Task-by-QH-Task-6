To see Output of the given below task jus go to https://qhvt6.herokuapp.com/

<-----------------Task 6---------------->

1. Create a video js webpage.
2. Have two mp4 files
3. Play them as a merged video in the webpage (like an youtube ad). Once file 1 plays, file 2 should resume playing it.
4. If the video is replayed, it would still play file 1 followed by file 2.
5. https://videojs.com/ is the url to access the source files for the library.

<----------Tools Used for this-------------->
1. HTML
2. CSS
3. VIDEOJS
4. JQuery
5. Bootstrap

<--------------Main Page Coding Under Body Section-------------------->
<div class="container-fluid text-center videoContainer">
    <div class="row my-3">
      <div class="text-center">
        <h3 class="heading border border-success text-success py-2">Problem Statement 6 Solution</h3>
      </div>
    </div>

    <div class="row">
      <div class="col-lg-4"></div>
      <div class="col-lg-4 text-center">
        <!-- Add some extra attribute as video-url and mimetype which we can later play once we are done playing ads  -->
        <video id="video_1" class="video-js video1 vjs-big-play-centered" height="300px" width="450px" video-url="videos/video2.mp4" mimetype="video/mp4" controls controlsList="nodownload" preload="none" data-setup=''>
        
          <!-- ad source ad ad video url   -->
          <source src="videos/video1.mp4" type='video/mp4' />

        </video>
      </div>
      <div class="col-lg-4"></div>
    </div>

    <div class="row my-3">
      <div class="text-center">
        <h3 class="videotitleheading text-danger py-2"></h3>
      </div>
    </div>
  </div>
 
