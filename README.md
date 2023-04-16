[![Netlify Status](https://api.netlify.com/api/v1/badges/e6c43271-a546-4e27-83c8-c95774f4242e/deploy-status)](https://app.netlify.com/sites/quirky-mcclintock-a14da0/deploys)

# GitHub landing

GitHub 랜딩 페이지를 클론 코딩합니다.

[Demo](https://quirky-mcclintock-a14da0.netlify.app/)

### 새롭게 업데이트된 코드

```css
/* 기존 코드 */
section.hero .curve {
  position: absolute;
  bottom: -1px;
  left: 0;
}
footer .curve {
  position: absolute;
  transform: scale(1,-1);
  top: -1px;
  left: 0;
}

/* 새로운 코드 */
section.hero .curve {
  width: 100%;
  transform: scaleY(.5);
  transform-origin: bottom;
  position: absolute;
  bottom: 0;
  left: 0;
}
footer .curve {
  width: 100%;
  transform: scaleY(-.5) translateY(50%);
  position: absolute;
  top: 0;
  left: 0;
}
```

### Google Fonts

https://fonts.google.com

```html
<!-- Google Fonts -->
<link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;700&display=swap" rel="stylesheet">
```

```css
body {
  font-family: 'Poppins', sans-serif;
  font-weight: 300;
}
```

### YouTube

```html
<iframe src="https://www.youtube.com/embed/2m9nUP-e8Co" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
```

### Google Maps

```html
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3576.4682727362647!2d-122.39309942040764!3d37.78267513336626!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8085807f619a62df%3A0x491ce2f73977af35!2sGitHub!5e0!3m2!1sko!2skr!4v1667199132180!5m2!1sko!2skr" style="width: 100%; height: 100%; border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
```

더 이상 아래 코드는 동작하지 않습니다.

```html
<!-- <script>
  // Initialize Google Map.
  function initMap() {
    const myLatLng = {
      lat: 37.782293,
      lng: -122.391240
    }
    const map = new google.maps.Map(document.getElementById('map'), {
      center: myLatLng,
      scrollwheel: false,
      zoom: 18
    })
    const marker = new google.maps.Marker({
      position: myLatLng,
      map: map,
      title: 'GitHub'
    })
  }
</script>
<script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyCTQIlxBn5AfKGvsfJiormAE1esN3fcCkg&callback=initMap" async defer></script> -->
```

### text

```html
<!--HERO-->
<h1>Where the world builds software</h1>
<p>Millions of developers and companies build, ship, and maintain their software on GitHub—the largest and most advanced development platform in the world.</p>


<!--FEATURES-->
<h5><strong>For everything you build</strong></h5>
<p>Host and manage your code on GitHub. You can keep your work private or share it with the world.</p>

<h5><strong>A better way to work</strong></h5>
<p>From hobbyists to professionals, GitHub helps developers simplify the way they build software.</p>

<h5><strong>Millions of projects</strong></h5>
<p>GitHub is home to millions of open source projects. Try one out or get inspired to create your own.</p>

<h5><strong>One platform, from start to finish</strong></h5>
<p>With hundreds of integrations, GitHub is flexible enough to be at the center of your development process.</p>


<!--MAP-->
<h1>Where is GitHub?</h1>
<p>GitHub is where people build software. More than 18 million people use GitHub to discover, fork, and contribute to over 48 million projects.</p>


<!--FOOTER-->
<h5>Product</h5>
<ul>
  <li><a href="#">Features</a></li>
  <li><a href="#">Security</a></li>
  <li><a href="#">Team</a></li>
  <li><a href="#">Enterprise</a></li>
  <li><a href="#">Customer stories</a></li>
  <li><a href="#">The ReadME Project</a></li>
  <li><a href="#">Pricing</a></li>
  <li><a href="#">Resources</a></li>
  <li><a href="#">Roadmap</a></li>
</ul>

<h5>Platform</h5>
<ul>
  <li><a href="#">Developer API</a></li>
  <li><a href="#">Partners</a></li>
  <li><a href="#">Atom</a></li>
  <li><a href="#">Electron</a></li>
  <li><a href="#">GitHub Desktop</a></li>
</ul>

<h5>Support</h5>
<ul>
  <li><a href="#">Docs</a></li>
  <li><a href="#">Community Forum</a></li>
  <li><a href="#">Professional Services</a></li>
  <li><a href="#">Learning Lab</a></li>
  <li><a href="#">Status</a></li>
  <li><a href="#">Contact GitHub</a></li>
</ul>

<h5>Company</h5>
<ul>
  <li><a href="#">About</a></li>
  <li><a href="#">Blog</a></li>
  <li><a href="#">Careers</a></li>
  <li><a href="#">Press</a></li>
  <li><a href="#">DI&B</a></li>
  <li><a href="#">Social Impact</a></li>
  <li><a href="#">Shop</a></li>
</ul>

<ul>
  <li>© 2021 GitHub, Inc.</li>
  <li><a href="#">Terms</a></li>
  <li><a href="#">Privacy</a></li>
  <li><a href="#">Site Map</a></li>
  <li><a href="#">What is Git?</a></li>
</ul>
```
