<template>
  <Layout>


    <h1 style="color:Violet; font-family:Papyrus; text-align:center;">Welcome to DDAY Gallery</h1>
    <p class="t1">
      DDAY จัดให้! เยี่ยมชม Artworks ได้เเล้วที่นี่
    </p>
    <p class="responsive">
      <p class="img1">
        <g-image alt="Example image" src="~/logo.png" width="450"/>
        <g-image alt="Example image" src="~/ig2.JPG" width="450"/>
        <g-image alt="Example image" src="~/ig3.png" width="450"/>
      </p>
    </p>

    


    

    

  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'DDAY'
  }
}
</script>

<style>
.home-links a {
  margin-right: 1rem;
}
.t1 {
  text-align: center;
}
.img1 {
  position: center;
  margin-top: 30px;
  margin-right: 100px;
  margin-left: 210px;
  border: 1px solid #ccc;
  width: 300px;
}
.img1:hover {
  border: 1px solid #777;
}
.img1 img {
  width: 100%;
  height: auto;
}

* {
  box-sizing: border-box;
}
.responsive {
  padding: 0 135px;
  position: center;
  width: 24.99999%;
}

@media only screen and (max-width: 700px) {
  .responsive {
    width: 49.99999%;
    margin: 6px 0;
  }
}

@media only screen and (max-width: 500px) {
  .responsive {
    width: 100%;
  }
}

</style>
