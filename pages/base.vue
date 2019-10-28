<template>
  <!-- <div class="uk-container uk-container-center">
    <div class="uk-child-width-expand@s uk-text-center" uk-grid>
      <div>
          <div class="uk-card uk-card-default uk-card-body">Item</div>
      </div>
      <div>
          <div class="uk-card uk-card-default uk-card-body">Item</div>
      </div>
      <div>
          <div class="uk-card uk-card-default uk-card-body">Item</div>
      </div>
    </div>
  </div> -->
  <div class="uk-position-relative">
    <img src="~/static/images/top.jpg" alt="">
    <div class="uk-position-top">
        <nav class="uk-navbar-container uk-navbar-transparent" uk-navbar>
            <div class="uk-navbar-left">
                <ul class="uk-navbar-nav">
                    <li class="uk-active"><a href="#">Active</a></li>
                    <li><a href="#">Item</a></li>
                    <li>
                        <a href="#">Parent</a>
                        <div class="uk-navbar-dropdown">
                            <ul class="uk-nav uk-navbar-dropdown-nav">
                                <li class="uk-active"><a href="#">Active</a></li>
                                <li><a href="/">Item</a></li>
                                <li class="uk-nav-header">Header</li>
                                <li><a href="#">Item</a></li>
                                <li><a href="#">Item</a></li>
                                <li class="uk-nav-divider"></li>
                                <li><a href="#">Item</a></li>
                            </ul>
                        </div>
                    </li>
                </ul>
            </div>
        </nav>
    </div>
    <div class="uk-section uk-section-muted">
      <div class="uk-container">
        <h3>Section</h3>
        <div class="uk-grid-match uk-child-width-1-3@m" uk-grid>
            <div>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
            </div>
            <div>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
            </div>
            <div>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
            </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
</script>

<style>
</style>
