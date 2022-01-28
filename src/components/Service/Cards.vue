<template>
  <section>
      <div class="container">
    <div class="row">
      <div class="col " >
        <div class="card" style="width: 18rem" >
          <img
            src="../../assets/imgs/idea.svg"
            class="card-img-top service-logo mt-5"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title mt-5">Card title</h5>
            <p class="card-text mt-3">
              Some quick example text to build on the card title and make up the
              bulk of the card's content.
            </p>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card" style="width: 18rem">
          <img
            src="../../assets/imgs/work.svg"
            class="card-img-top service-logo mt-5"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title mt-5">Card title</h5>
            <p class="card-text mt-3">
              Some quick example text to build on the card title and make up the
              bulk of the card's content.
            </p>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card" style="width: 18rem">
          <img src="../../assets/imgs/deliver.svg" class="card-img-top service-logo mt-5" alt="..." />
          <div class="card-body">
            <h5 class="card-title mt-5">Card title</h5>
            <p class="card-text mt-3">
              Some quick example text to build on the card title and make up the
              bulk of the card's content.
            </p>
            
          </div>
        </div>
      </div>
    </div>
    </div>
  </section>
</template>


<style>
.service-logo{
    width:20% !important;
    height:10vh;
    margin-left: 40%;
}
</style>



<script>
export default {
  name: "Service",
};
</script>