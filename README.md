![Bootstrap 4 Layouts]

# Bootstrap 4 layouts

This repository is a template for a Bootstrap 4 website with dummy content. It serves as a template reference for different bootstrap 4 layouts or to use as a theme for your site as is. You can see a live demo of the template at: [github-project-wild-tour.pensivewebstudio.com/](http://www.portfolio-item-smwt.pensivewebstudio.com/).

You can see a live demo of a site that I build using this template at: [portfolio-item-smwt.pensivewebstudio.com/](http://www.portfolio-item-smwt.pensivewebstudio.com/).


#Structure of the Layouts

The implementation is a single page design where each html article represents a page of the website: #page-about, #page-services etc… .. . I’ve named the articles #page-one, #page-two and so on to make the layout generic assuming you would want to rename them as you wish. For example, you could rename the article below: #page-about, if you wanted to make it your about page.

   <!-- #page-one -->
  <article id="page-one" class="page-cards page-section vertical-padding">

    <header class="page-section-header container">
      <h2 class="page-section-title display-4 pt-4 text-center">Page Section Title</h2>
      <p class="page-section-text lead mx-md-5">Page Section Text: Lorem Ipsum is simply dummy text of the
        printing and typesetting industry which will be replaced with text one you and your business upon completion
        of your site. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
        labore et dolore magna aliqua. by also using the. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
        do eiusmod tempor incididunt ut
        labore et dolore magna aliqua. by also using the</p>
    </header>
    <!-- page-section-header container -->

    <h2 class="page-section-title display-4 pt-4 text-center">Page Section Title</h2>

    <section class="layout-cards container">
      <div class="row justify-content-center">
        <div class="col-11 col-sm-12 col-lg-10">
          <div class="card-deck">

            <div class="row justify-content-center">

              <div class="col-12 col-sm-8 col-md-4">
                <section class="card my-3">
                  <img class="layout-image card-img-top img-fluid" src="https://dummyimage.com/768x512/e3d9b5/A.png&text=+"
                    alt="Photo Sample">
                  <div class="card-body">
                    <h4 class="layout-title card-title">Layout Title</h4>
                    <p class="layout-text card-text ">Layout Text: Impedit autem ea delectus repudiandae iste commodi a natus
                      aspernatur
                      culpa accusantium, hic, ullam molestiae
                      ratione perspiciatis sit?</p>
                  </div>
                </section>
              </div>
              <!-- end column -->

              <div class="col-12 col-sm-8 col-md-4">
                <section class="card my-3">
                  <img class="layout-image card-img-top img-fluid" src="https://dummyimage.com/768x512/e3d9b5/A.png&text=+"
                    alt="Photo Sample">
                  <div class="card-body">
                    <h4 class="layout-title card-title">Layout Title</h4>
                    <p class="layout-text card-text ">Layout Text: Impedit autem ea delectus repudiandae iste commodi a natus
                      aspernatur
                      culpa accusantium, hic, ullam molestiae
                      ratione perspiciatis sit?
                    </p>
                  </div>
                </section>
              </div>
              <!-- end column -->

              <div class="col-12 col-sm-8 col-md-4">
                <section class="card my-3">
                  <img class="layout-image card-img-top img-fluid" src="https://dummyimage.com/768x512/e3d9b5/A.png&text=+"
                    alt="Photo Sample">
                  <div class="card-body">
                    <h4 class="layout-title card-title">Layout Title</h4>
                    <p class="layout-text card-text ">Layout Text: Magnum autem ea delectus repudiandae iste commodi a natus
                      aspernatur
                      culpa accusantium, hic, ullam molestiae
                      ratione perspiciatis sit?</p>
                  </div>
                </section>
              </div>
              <!-- end column -->

            </div>
            <!-- end row -->

          </div>
          <!-- end card-deck -->
        </div>
        <!-- end column -->
      </div>
      <!-- end row -->
    </section>
    <!-- end layout-cards container -->

  </article>
  <!-- end #page-one 
------------------------------------------------------------>>
```
Most layouts (not the floater layout) also have an optional `<header>`. They should be self-explanatory.


#Authors and Contributors

Ray Villalobos: Ray built the template at: [raybo.org/bootstrap4layouts/](http://www.raybo.org/bootstrap4layouts/), which this project is largly based on.
