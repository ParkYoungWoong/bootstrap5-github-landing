# GitHub landing

GitHub 랜딩 페이지를 클론 코딩합니다.

[Demo](https://quirky-mcclintock-a14da0.netlify.app/)

### YouTube

```html
<iframe src="https://www.youtube.com/embed/2m9nUP-e8Co" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
```

### Google Maps

```html
<script>
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
<script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyCTQIlxBn5AfKGvsfJiormAE1esN3fcCkg&callback=initMap" async defer></script>
```
