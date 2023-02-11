# Youtube-Website

<!DOCTYPE html>
<html>
    <head>
        <title>Youtube Clone</title>
        <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
        <style>
            p {
                font-family: Roboto, Arial;
                margin-top: 0;
                margin-bottom: 0;
            }
           .thumbnail {
            margin-top: 20px;
             width: 300px;
             display: block;
    
           }
          .video-preview {
            width: 300px;
           display: inline-block;
            margin-right: 15px;
            vertical-align: top;
          }
           .video-title {
            margin-top: 0;
            font-size: 14px;
            font-weight: 500;
            line-height: 20px;
            margin-bottom: 12px;

           }
           .search-bar {
            font-size: 20px;
            margin-left: 12px;
            display: block;
           }
           .channel-pictures {
             display: inline-block; 
             width: 50px;   
             vertical-align: top;
            

           }
           .video-info {
             display: inline-block;
             width: 245px;
           
           }
            .profile-picture {
                width: 40px;
                border-radius: 50px;
            }
            .thumbnail-row {
                margin-bottom: 12px
            }
            .video-author,.video-stats{
                font-size: 12px;
                color: rgb(96 ,96 ,96)
            }
            .video-author { 
                margin-bottom: 4px;
            }
        </style>
    </head>
    <body>
        <input class="search-bar" type="text" placeholder="Search">
       
        <div class="video-preview">
            <div class="thumbnail-row"> 
                <img class="thumbnail" src="thumnails/thumbnail-1.webp">
            </div>
        <div>
            <div class="channel-pictures">
               <img class="profile-picture" src="channel pictures/channel-1.jpeg">
            </div>
            <div class="video-info"> 
                  <p class="video-title">
                      Talking Tech and AI with Google CEO Sundar Pichai!
                  </p>
                  <p class="video-author">
                      Marques Brownlee 
                  </p>    
                  <p class="video-stats">
                      3.4M views &middot; 6 months ago
                  </p>
                
                </div>     
        </div>    
           
        </div>

        <div class="video-preview">
            <div class="thumbnail-row"> 
                <img class="thumbnail" src="thumnails/thumbnail-2.webp">
            </div>
        <div>
            <div class="channel-pictures">
               <img class="profile-picture" src="channel pictures/channel-2.jpeg">
            </div>
             
                <div class="video-info"> 
                  <p class="video-title">
                    Try Not To Laugh Challenge #9
                  </p>
                  <p class="video-author">
                    Markiplier 
                  </p>    
                  <p class="video-stats">
                    19M views &middot; 4 years ago
                  </p>
                
                </div>     
        </div>    
           
        </div>
        
    </body>
</html>
