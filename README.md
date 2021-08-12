# Animated_icons


### EXAMPLE
``` 
 <div id="container"></div>
 <style>
 #container {
  position: fixed;
  top: 20vh;
  left: 35vw;
  width: 400px;
  height: 400px;
}
</style>
<script src="https://cdnjs.cloudflare.com/ajax/libs/bodymovin/5.7.4/lottie.min.js"></script>
<script>
    var animation = bodymovin.loadAnimation({
    container: document.getElementById('container'),
    path: 'https://raw.githubusercontent.com/FabrizioVash/Animated_icons/main/icons8-home.json',
    renderer: 'svg',
    loop: true,
    autoplay: true,
    name: "Demo Animation",
    });
</script>
