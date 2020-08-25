<svelte:head>
  <title>About</title>
</svelte:head>
<script>
  import "../../node_modules/spectre.css/dist/spectre-icons.min.css";
</script>
<style>
  section {
    padding-bottom: 2rem;

  }
  .center {
    margin: 0 auto;
  }
  .container {
    max-width: 860px;
  }
</style>


  <div class="container center"> 
    <h1 class="text-center">About this site</h1>

    <p class="text-center">This site is build using <a href="https://picturepan2.github.io/spectre/" >Specte.css</a> framework</p>

    <section>

      <h4 class="s-subtitle" >Headings</h4>
      <div class="columns">
        <div class="column col-12">
          <h1>H1 Heading <small class="label">40px</small></h1>
        </div>
        <div class="column col-12">
          <h2>H2 Heading <small class="label">32px</small></h2>
        </div>
        <div class="column col-12">
          <h3>H3 Heading <small class="label">28px</small></h3>
        </div>
        <div class="column col-12">
          <h4>H4 Heading <small class="label">24px</small></h4>
        </div>
        <div class="column col-12">
          <h5>H5 Heading <small class="label">20px</small></h5>
        </div>
        <div class="column col-12">
          <h6>H6 Heading <small class="label">16px</small></h6>
        </div>
      </div>
    </section>

    <section>
      <div class="container">
        <h4 class="s-title">Cards</h4>
        <div class="columns">
          <div class="column col-6 col-lg-8 col-xs-12 col-mx-auto">
            <div class="card">
              <div class="card-image"><img class="img-responsive" src="logo-512.png" alt="logo"></div>
              <div class="card-header">
                <div class="card-title h5">Svelte</div>
                <div class="card-subtitle text-gray">Cybernetically enhanced web apps</div>
              </div>
              <div class="card-body">Svelte is a radical new approach to building user interfaces. Whereas traditional frameworks like React and Vue do the bulk of their work in the browser, Svelte shifts that work into a compile step that happens when you build your app.</div>
              <div class="card-footer"><a class="btn btn-primary" href="https://svelte.dev/">Svelte Homepage</a></div>
            </div>
          </div>
          <div class="column col-6 col-lg-8 col-xs-12 col-mx-auto">
            <div class="card">
              <div class="card-header">
                <div class="card-title h5">Spectre.css</div>
                <div class="card-subtitle text-gray">A Lightweight, Responsive and Modern CSS Framework</div>
              </div>
              <div class="card-image"><img class="img-responsive center" src="spectre.jpeg" alt="logo"></div>
              <div class="card-body">Spectre provides basic styles for typography and elements, flexbox based responsive layout system, pure CSS components and utilities with best practice coding and consistent design language.</div>
              <div class="card-footer">
                <div class="btn-group btn-group-block">
                  <button class="btn btn-primary">Download</button>
                  <button class="btn">Share</button>
                  <button class="btn">Develop</button>
                </div>
              </div>
            </div>
          </div>
        </div>
    </section>

    <section>
      <h3 class="s-title">Forms</h3>
      <div class="columns">
        <div class="column col-6 col-xs-12">
          <div class="form-group">
            <label class="form-label" for="input-example-1">Name</label>
            <input class="form-input" id="input-example-1" type="text" placeholder="Name">
          </div>
          <div class="form-group">
            <label class="form-label" for="input-example-2">Email</label>
            <input class="form-input" id="input-example-2" type="email" placeholder="Email">
          </div>
          <div class="form-group">
            <select class="form-select">
              <option>Choose an option</option>
              <option>Pure Functions</option>
              <option>Objects</option>
              <option>Something else</option>
            </select>
          </div>
          <div class="form-group">
            <label class="form-label">Gender</label>
            <label class="form-radio">
              <input type="radio" name="gender" checked=""><i class="form-icon"></i> Male
            </label>
            <label class="form-radio">
              <input type="radio" name="gender"><i class="form-icon"></i> Female
            </label>
          </div>
          <div class="form-group">
            <label class="form-switch">
              <input type="checkbox"><i class="form-icon"></i>Turn off virtual DOM
            </label>
          </div>
          <div class="form-group">
            <label class="form-checkbox">
              <input type="checkbox"><i class="form-icon"></i>Remember this option
            </label>
          </div>
      </div>
    </section>

    <section>
      <h4 class="s-subtitle">Navigation icons</h4>
            <div class="columns">
              <div class="column col-3 col-md-6 col-mx-auto">
                <button class="btn btn-primary btn-action btn-lg"><i class="icon icon-arrow-up"></i></button>
                <p>icon-arrow-up</p>
              </div>
              <div class="column col-3 col-md-6">
                <button class="btn btn-primary btn-action btn-lg"><i class="icon icon-arrow-right"></i></button>
                <p>icon-arrow-right</p>
              </div>
              <div class="column col-3 col-md-6">
                <button class="btn btn-primary btn-action btn-lg"><i class="icon icon-arrow-down"></i></button>
                <p>icon-arrow-down</p>
              </div>
              <div class="column col-3 col-md-6">
                <button class="btn btn-primary btn-action btn-lg"><i class="icon icon-arrow-left"></i></button>
                <p>icon-arrow-left</p>
              </div>
              <div class="column col-3 col-md-6">
                <button class="btn btn-primary btn-action btn-lg"><i class="icon icon-upward"></i></button>
                <p>icon-upward</p>
              </div>
              <div class="column col-3 col-md-6">
                <button class="btn btn-primary btn-action btn-lg"><i class="icon icon-forward"></i></button>
                <p>icon-forward</p>
              </div>
              <div class="column col-3 col-md-6">
                <button class="btn btn-primary btn-action btn-lg"><i class="icon icon-downward"></i></button>
                <p>icon-downward</p>
              </div>
              <div class="column col-3 col-md-6">
                <button class="btn btn-primary btn-action btn-lg"><i class="icon icon-back"></i></button>
                <p>icon-back</p>
              </div>
              <div class="column col-3 col-md-6">
                <button class="btn btn-primary btn-action btn-lg"><i class="icon icon-caret"></i></button>
                <p>icon-caret</p>
              </div>
              <div class="column col-3 col-md-6">
                <button class="btn btn-primary btn-action btn-lg"><i class="icon icon-menu"></i></button>
                <p>icon-menu</p>
              </div>
              <div class="column col-3 col-md-6">
                <button class="btn btn-primary btn-action btn-lg"><i class="icon icon-apps"></i></button>
                <p>icon-apps</p>
              </div>
              <div class="column col-3 col-md-6">
                <button class="btn btn-primary btn-action btn-lg"><i class="icon icon-more-horiz"></i></button>
                <p>icon-more-horiz</p>
              </div>
              <div class="column col-3 col-md-6">
                <button class="btn btn-primary btn-action btn-lg"><i class="icon icon-more-vert"></i></button>
                <p>icon-more-vert</p>
              </div>
            </div>
            <h4 class="s-subtitle">Action icons</h4>
            <div class="columns">
              <div class="column col-3 col-md-6">
                <button class="btn btn-primary btn-action btn-lg"><i class="icon icon-resize-horiz"></i></button>
                <p>icon-resize-horiz</p>
              </div>
              <div class="column col-3 col-md-6">
                <button class="btn btn-primary btn-action btn-lg"><i class="icon icon-resize-vert"></i></button>
                <p>icon-resize-vert</p>
              </div>
              <div class="column col-3 col-md-6">
                <button class="btn btn-primary btn-action btn-lg"><i class="icon icon-plus"></i></button>
                <p>icon-plus</p>
              </div>
              <div class="column col-3 col-md-6">
                <button class="btn btn-primary btn-action btn-lg"><i class="icon icon-minus"></i></button>
                <p>icon-minus</p>
              </div>
              <div class="column col-3 col-md-6">
                <button class="btn btn-primary btn-action btn-lg"><i class="icon icon-cross"></i></button>
                <p>icon-cross</p>
              </div>
              <div class="column col-3 col-md-6">
                <button class="btn btn-primary btn-action btn-lg"><i class="icon icon-check"></i></button>
                <p>icon-check</p>
              </div>
              <div class="column col-3 col-md-6">
                <button class="btn btn-primary btn-action btn-lg"><i class="icon icon-stop"></i></button>
                <p>icon-stop</p>
              </div>
              <div class="column col-3 col-md-6">
                <button class="btn btn-primary btn-action btn-lg"><i class="icon icon-shutdown"></i></button>
                <p>icon-shutdown</p>
              </div>
              <div class="column col-3 col-md-6">
                <button class="btn btn-primary btn-action btn-lg"><i class="icon icon-refresh"></i></button>
                <p>icon-refresh</p>
              </div>
              <div class="column col-3 col-md-6">
                <button class="btn btn-primary btn-action btn-lg"><i class="icon icon-search"></i></button>
                <p>icon-search</p>
              </div>
              <div class="column col-3 col-md-6">
                <button class="btn btn-primary btn-action btn-lg"><i class="icon icon-flag"></i></button>
                <p>icon-flag</p>
              </div>
              <div class="column col-3 col-md-6">
                <button class="btn btn-primary btn-action btn-lg"><i class="icon icon-bookmark"></i></button>
                <p>icon-bookmark</p>
              </div>
              <div class="column col-3 col-md-6">
                <button class="btn btn-primary btn-action btn-lg"><i class="icon icon-edit"></i></button>
                <p>icon-edit</p>
              </div>
              <div class="column col-3 col-md-6">
                <button class="btn btn-primary btn-action btn-lg"><i class="icon icon-delete"></i></button>
                <p>icon-delete</p>
              </div>
              <div class="column col-3 col-md-6">
                <button class="btn btn-primary btn-action btn-lg"><i class="icon icon-share"></i></button>
                <p>icon-share</p>
              </div>
              <div class="column col-3 col-md-6">
                <button class="btn btn-primary btn-action btn-lg"><i class="icon icon-download"></i></button>
                <p>icon-download</p>
              </div>
              <div class="column col-3 col-md-6">
                <button class="btn btn-primary btn-action btn-lg"><i class="icon icon-upload"></i></button>
                <p>icon-upload</p>
              </div>
              <div class="column col-3 col-md-6">
                <button class="btn btn-primary btn-action btn-lg"><i class="icon icon-copy"></i></button>
                <p>icon-copy</p>
              </div>
            </div>
            <h4 class="s-subtitle">Object icons</h4>
            <div class="docs-demo columns">
              <div class="column col-3 col-md-6">
                <button class="btn btn-primary btn-action btn-lg"><i class="icon icon-mail"></i></button>
                <p>icon-mail</p>
              </div>
              <div class="column col-3 col-md-6">
                <button class="btn btn-primary btn-action btn-lg"><i class="icon icon-people"></i></button>
                <p>icon-people</p>
              </div>
              <div class="column col-3 col-md-6">
                <button class="btn btn-primary btn-action btn-lg"><i class="icon icon-message"></i></button>
                <p>icon-message</p>
              </div>
              <div class="column col-3 col-md-6">
                <button class="btn btn-primary btn-action btn-lg"><i class="icon icon-photo"></i></button>
                <p>icon-photo</p>
              </div>
              <div class="column col-3 col-md-6">
                <button class="btn btn-primary btn-action btn-lg"><i class="icon icon-time"></i></button>
                <p>icon-time</p>
              </div>
              <div class="column col-3 col-md-6">
                <button class="btn btn-primary btn-action btn-lg"><i class="icon icon-location"></i></button>
                <p>icon-location</p>
              </div>
              <div class="column col-3 col-md-6">
                <button class="btn btn-primary btn-action btn-lg"><i class="icon icon-link"></i></button>
                <p>icon-link</p>
              </div>
              <div class="column col-3 col-md-6">
                <button class="btn btn-primary btn-action btn-lg"><i class="icon icon-emoji"></i></button>
                <p>icon-emoji</p>
              </div>
            </div>
    </section>

    <section>
      <h4>Progress</h4>
      <div class="docs-demo columns">
        <div class="column col-3 col-xs-12">
          <progress class="progress" value="75" max="100"></progress>
        </div>
        <div class="column col-3 col-xs-12">
          <progress class="progress" value="50" max="100"></progress>
        </div>
        <div class="column col-3 col-xs-12">
          <progress class="progress" value="25" max="100"></progress>
        </div>
        <div class="column col-3 col-xs-12">
          <progress class="progress" max="100"></progress>
        </div>
      </div>
    </section>

  </div>
