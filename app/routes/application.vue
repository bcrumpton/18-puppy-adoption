<template lang="html">

  <div class="app">
    <nav class="nav">
      <div class="nav-left">
        <div class="nav-left">
          <a href="#" class="nav-item is-brand">Puppies</a>
        </div>

        <div class="nav-right">
          <a href="#" class="nav-item">All Puppies</a>
          <a href="#" class="nav-item">Add Puppy</a>
        </div>
      </div>
    </nav>

    <div class="container">
      <div class="section">
        <div class="columns">
          <div class="column is-one-third">

            <div class="panel">
              <p class="panel-heading">
                Adopt A Pupper
              </p>

              <a class="panel-block">
                <figure class="image is-128x128">
                  <img src="https://i.ytimg.com/vi/CMNry4PE93Y/hqdefault.jpg" alt="">
                </figure>
                <div class="panel-text">
                  <p>Zombie Kid</p>
                  <p><a href="#">read more</a></p>
                </div>
              </a>

              <a class="panel-block">
                <figure class="image is-128x128">
                  <img src="http://www.viralspell.com/wp-content/uploads/2014/12/lu-2.jpg" alt="">
                </figure>
                <div class="panel-text">
                  <p>Luna</p>
                  <p><a href="#">read more</a></p>
                </div>
              </a>

              <a class="panel-block">
                <figure class="image is-128x128">
                  <img src="http://stories.barkpost.com/wp-content/uploads/2014/08/tuna.jpg" alt="">
                </figure>
                <div class="panel-text">
                  <p>Tuna</p>
                  <p><a href="#">read more</a></p>
                </div>
              </a>

              <a class="panel-block">
                <figure class="image is-128x128">
                  <img src="http://cdn.dogbreedsdb.com/img/2016-10-27/20131231-16470752-doge-1_1477580349756.jpg" alt="">
                </figure>
                <div class="panel-text">
                  <p>Doge</p>
                  <p><a href="#">read more</a></p>
                </div>
              </a>

            </div>
          </div>

          <div class="column">

            <div class="add-pup">
              <h3 class="title is-3 add-pup__title">Puppies for Adoption</h3>
              <a class="button is-info add-pup__btn">Add A Pupper</a>
            </div>
            <table class="table">
              <thead>
                <tr>
                  <th>Name</th>
                  <th>Age</th>
                  <th></th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <th>Zombie Kid</th>
                  <th>10</th>
                  <th><a href="#">read more</a></th>
                </tr>
              </tbody>
            </table>

            <div class="adopted">
              <h3 class="title is-3 adopted__title">Adopted Puppers</h3>
            </div>
            <table class="table">
              <thead>
                <tr>
                  <th>Name</th>
                  <th>Age</th>
                  <th></th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <th>Zombie Kid</th>
                  <th>10</th>
                  <th><a href="#">read more</a></th>
                </tr>
                <tr>
                  <th>Luna</th>
                  <th>27</th>
                  <th><a href="#">read more</a></th>
                </tr>
                <tr>
                  <th>Tuna</th>
                  <th>4</th>
                  <th><a href="#">read more</a></th>
                </tr>
                <tr>
                  <th>Doge</th>
                  <th>1</th>
                  <th><a href="#">read more</a></th>
                </tr>
              </tbody>
            </table>
          </div>

        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
    };
  },

  methods: {

  },
};
</script>
