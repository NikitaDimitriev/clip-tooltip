<template>
  <div class="parent">
    <div class="quart-of-page green">
     
     <div class="item1">

     </div>

    </div>
    <div class="quart-of-page purple">
      <div class="container">
        <div class="inner">
          <span>i</span>
          <h1>Hey</h1>
          <p>How the Supermarket Helped America Win the Cold War</p>
        </div>
      </div>
    </div>
    <div class="quart-of-page blue">
      <div class="container">
        <div class="inner">
          <span>i</span>
          <h1>Hey</h1>
          <p>How the Supermarket Helped America Win the Cold War</p>
        </div>
      </div>
    </div>
    <div class="quart-of-page red">
      <div class="container">
        <div class="inner">
          <span>i</span>
          <h1>Hey</h1>
          <p>How the Supermarket Helped America Win the Cold War</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  }
};
</script>

<style lang="scss">
.parent{
  width: 100vw;
  height: 100vh;
  display: flex;
  flex-wrap: wrap;
  flex:1;
}
.quart-of-page {
  width: 50%;
  height: 50%;
}

.blue {
  background: #00b6ff;
}

.red {
  background: #ed2939;
}

.purple{
  background: #6432a8;
}

.green{
  background: #32a838;
}
.inner {
  background: rgb(7, 218, 165);
  padding: 1em;
  border-radius: 10px;
  width: 250px;
  clip-path: circle(10% at 90% 20%);
  transition: all 0.5s ease-in-out;
  cursor: pointer;

  &:hover {
    clip-path: circle(75%);
    background: #00b6ff;
  }
  &:hover span {
    color: rgba(255, 255, 255, 0);
  }
  span {
    float: right;
    color: white;
    font-weight: bold;
    transition: color 0.5s;
    position: relative;
    margin-right: 4%;
  }
  h1 {
    color: white;
    margin: 0;
  }
  p {
    color: white;
    font-size: 0.8rem;
  }
}

.item1{
  width: 100%;
  height: 100%;
  background-image: url(./assets/59a7eec00b1ee.jpg);
  background-size: 100% 100%;
  clip-path: circle(10% at 0% 0%);
  transition: all 0.75s ease-in;
  // z-index: 1;

  &:hover{
    clip-path: circle(100%);
  }
}

</style>
