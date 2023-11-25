---
# template: home.html
# title: Material for MkDocs
# social:
#   cards_layout_options:
#     title: Documentation that simply works
hide:
  - navigation
  - toc
  - search
---
# Welcome


  <!-- Hero for landing page -->
  <section class="mdx-container">
  <style>
        .md-header {
          width: 100%
        }
        .md-container {
          width: 100%
        }
        .md-ellipsis{
          font-weight: 900;
        }
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-image: linear-gradient(to top, rgb(86, 71, 117), #000, #000);
            width: 100%;
        }
        .shell {
            width: 100%;
            height: 100vh;
        }
        .content {
            width: 100%;
            height: 100vh;
            position: relative
        }
        .content h2 {
            position: absolute;
            text-align: center;
            left: 50%;
            transform: translate(-50%);
            z-index: 4;
            margin-top: 300px;
            color: rgba(255, 255, 255, 0.95);
            -webkit-text-stroke: #000 2px;
            font: 900 100px 'Holtwood One SC';
        }

        .images {
            width: 100%;
            height: 100%;
            position: absolute;
            overflow: hidden;
        }

        .images div {
            width: 100%;
            height: 100%;
            background-size: cover;
            position: absolute;
        }

        .img1 {
            background-image: url('./image/1.png');
        }

        .img2 {
            background-image: url('./image/2.png');
        }

        .img3 {
            background-image: url('./image/3.png');
        }

        .img4 {
            background-image: url('./image/4.png');
        }

        .img5 {
            background-image: url('./image/5.png');
        }

        .img6 {
            background-image: url('./image/6.png');
            transform: translate(600px,400px);
        }

  </style>
    <!-- <meta name="viewport" content="width=device-width, initial-scale=1.0"> -->
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Sofia">
    <link href="https://fonts.googleapis.com/css2?family=Holtwood+One+SC&display=swap" rel="stylesheet">
    <div class="shell">
        <div class="content">
            <h2>Welcome<br />︾</h2>
            <div class="images">
                <div class="img1"></div>
                <div class="img2"></div>
                <div class="img3"></div>
                <div class="img4"></div>
                <div class="img5"></div>
                <div class="img6"></div>
            </div>
        </div>
    </div>
    <script>
        let img1 = document.querySelector('.img1')
        let img3 = document.querySelector('.img3')
        let img4 = document.querySelector('.img4')
        let img5 = document.querySelector('.img5')
        // 设置鼠标移动时触发的效果
        document.addEventListener('mousemove',e=>{
            // 获取鼠标的位置
            let mouseX = e.clientX
            let mouseY = e.clientY
            // 获取图片距离左侧和顶部的距离
            let img1x = img1.offsetLeft
            let img1y = img1.offsetTop

            let img3x = img3.offsetLeft
            let img3y = img3.offsetTop

            let img4x = img4.offsetLeft
            let img4y = img4.offsetTop

            let img5x = img5.offsetLeft
            let img5y = img5.offsetTop
            // 设置移动时的偏移量
            let diff1x = (mouseX-img1x)/45
            let diff1y = (mouseY-img1y)/45

            let diff3x = (mouseX-img3x)/18
            let diff3y = (mouseY-img3y)/18

            let diff4x = (mouseX-img4x)/30
            let diff4y = (mouseY-img4y)/30

            let diff5x = (mouseX-img5x)/8
            let diff5y = (mouseY-img5y)/8

            img1.style.transform = `translate(${diff1x}px,${diff1y}px)`
            img3.style.transform = `translate(${diff3x}px,${diff3y}px)`
            img4.style.transform = `translate(${diff4x}px,${diff4y}px)`
            img5.style.transform = `translate(${diff5x}px,${diff5y}px)`
        })
    </script>
</section>

<!-- <span style="color:Tomato">**Greetings and a warm welcome to** `RenoCrypt`</span>, a sanctuary for **tech enthusiasts**, **professionals**, and **visionaries** alike. Here, we venture beyond the <span style="color:LightSeaGreen">***conventional boundaries of technology***</span> to <span style="color:SlateBlue">***explore***</span>, <span style="color:SlateBlue">***dissect***</span>, and <span style="color:SlateBlue">***celebrate***</span> the most avant-garde advancements in the realm of <span style="color:MediumSeaGreen">**cloud-native applications**</span>, <span style="color:MediumSeaGreen">**cloud computing**</span>, <span style="color:MediumSeaGreen">***machine learning workflows***</span>, <span style="color:MediumSeaGreen">***data engineering***</span>, <span style="color:MediumSeaGreen">***DevOps***</span>, and <span style="color:MediumSeaGreen">***much more***</span>.

## A Confluence of Innovation and Practicality
In an era where technology is not just an enabler but a catalyst for change, RenoCrypt serves as a lighthouse, guiding you through the labyrinthine complexities of modern tech paradigms. Our focus is not merely on showcasing the latest trends but on elucidating their practical applications and transformative potential. Whether you're intrigued by the intricacies of pipelining or captivated by the possibilities of cloud-native solutions, you'll find a wealth of knowledge and insights here to quench your intellectual curiosity.

## A Commitment to Excellence
At RenoCrypt, we believe that the pursuit of excellence is a journey, not a destination. Our content is meticulously curated and rigorously tested to ensure it meets the highest standards of accuracy and relevance. Leveraging advanced metrics and analytical methodologies, we strive to deliver content that is not just informative but also actionable.

## Collaboration and Community
The essence of innovation lies in collective wisdom. RenoCrypt is not just a platform but a community where ideas can be exchanged, questions can be raised, and solutions can be found. We encourage you to engage, contribute, and collaborate, for it is through synergy that we can push the boundaries of what technology can achieve.

## Navigating the Future, Today
As we stand on the cusp of a technological revolution, the choices we make today will shape the world of tomorrow. RenoCrypt aims to equip you with the knowledge and tools you need to navigate this rapidly evolving landscape with confidence and foresight. From performance optimization to risk mitigation, from data governance to scalability, we cover the gamut of topics that are essential for anyone looking to stay ahead of the curve.

Your Journey Begins Here
So, whether you're a seasoned professional, an aspiring innovator, or simply a curious mind, there's something here for everyone. Dive in, explore, and let RenoCrypt be your compass in this exhilarating journey through the ever-expanding universe of technology.

We're delighted to have you here, and we can't wait to embark on this exciting adventure together.

<span style="color:DodgerBlue">👋 **Welcome to RenoCrypt**.</span> <span style="color:DarkOrchid">🤗**Let us Embrace the Future**.</span> -->


