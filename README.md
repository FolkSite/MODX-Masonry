MODX-Masonry
============

Simple &amp; Advanced Tutorials to integrate Masonry with MODX

Cloud URL = http://masonry.clients.modxcloud.com/

Masonry Repo = https://github.com/desandro/masonry

##Goals

 1. Basic Starter DIY Tutorials
 2. Vanilla JS Lightbox
 3. Auto-watch images in a folder
 4. Mobile Upload
 5. More Themes

##Installation

 1. Upload - `assets/js/masonry.pkgd.min.js`
 2. Upload - `assets/css/demo.css`
 3. Create - `assets/img` (naming convention optional)
 4. Create Chunk - `MasonryConfig` (copy from the repo)
 5. Add to `<head>` - 
  
    ```
    [[$MasonryConfig? &width=`200` &theme=`demo`]]
    ```
    
 6. Add Container HTML
 
    ```
    <div class="container" id="mason">
      <div class="item" style="background-image: url([[phpthumbof? &input=`folder/file.jpg` &options=`&w=400&zc=0&aoe=0&far=0`]]);"></div>
    </div> <!-- /#mason -->
    ```
    
 7. the **phpthumbof** width should be double the width in the chunk   
