````html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="preconnect" href="https://fonts.gstatic.com" />
    <link rel="preconnect" href="https://cdnjs.cloudflare.com" />

    <title>Simatwa Caleb | Developer</title>

    <meta name="keywords" content="Smartwa, Portfolio, programmer, python, java, javascript, html, css skill" />

    <meta name="description" content="Simatwa Caleb | Developer" />

    <link rel="icon" type="image/png" href="assets/devfolio-logo.png" />

    <meta name="theme-color" content="#36d1dc" />

    <meta property="og:type" content="website" />

    <meta property="og:url" content="https://simatwa.github.io/Portfolio" />

    <meta property="og:title" content="Simatwa Caleb | Developer" />

    <meta property="og:description" content="Smartwa's portfolio - opensource contributor (programmer)" />

    <meta
      property="og:image"
      content="assets/devfolio.png"
    />

    <meta property="twitter:card" content="summary_large_image" />
    <meta property="twitter:url" content="https://simatwa.github.io/portfolio" />
    <meta property="twitter:title" content="Simatwa Caleb | Developer" />
    <meta
      property="twitter:description"
      content="Smartwa's portfolio - opensource contributor (programmer)"

    <meta
      property="twitter:image"
      content="assets/devfolio.png"
    />

    <link rel="preload" as="style" href="css/main.css" />
    <link rel="stylesheet" href="css/main.css" />

    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.3.0/css/all.min.css"
      integrity="sha512-SzlrxWUlpfuzQ+pcUCosxcglQRNAq/DZjVsC0lE40xsADsfeQoEypE+enwcOiGjk/bSuGGKHEyjSoQ1zVisanQ=="
      crossorigin="anonymous"
      referrerpolicy="no-referrer"
    />
    <script defer src="javascript/scrollreveal.min.js"></script>
    <script
      defer
      type="text/javascript"
      src="javascript/scrollveal.js"
    ></script>

    <script
      async
      src="https://www.googletagmanager.com/gtag/js?id=UA-122228201-4"
    ></script>
    <script>
      window.dataLayer = window.dataLayer || []
      function gtag() {
        dataLayer.push(arguments)
      }
      gtag("js", new Date())

      gtag("config", "UA-122228201-4")
    </script>
    <!-- End of Google Analytics -->
  </head>
  <body>
    <!-- Hero Section -->
    <div id="hero">
      <section class="container">
        <h1 class="hero-title">
          Hi, my name is <span class="text-color-main name">Simatwa Caleb</span>
          <br />
          I'm a Tech-enthusiast and a Software Developer.
        </h1>
        <p class="hero-cta">
          <a class="cta-btn cta-btn--hero" href="#about">Get in touch</a>
        </p>
      </section>
      <a href="#about" class="scroll-down-link" aria-label="scroll-down">
        <div class="scroll-down"></div
      ></a>
    </div>
    <!-- /END Hero Section -->

    <!-- About Section -->
    <section id="about">
      <div class="container">
        <h2 class="section-title">About Me</h2>
        <div class="row about-wrapper">
          <div class="about-wrapper__image">
            <img
              class="img-fluid"
              src="assets/profile.png"
              alt="Profile Image"
              width="450"
              height="350"
            />
          </div>
          <div class="about-wrapper__info">
            <p class="about-wrapper__info-text">
              I am a passionate and motivated software developer with a great enthusiasm for technology. I have a growing interest in the software development industry, and am always looking for ways to expand my knowledge and skills in this field.
              I have been exposed to a wide range of technologies, including Python, Java and C programming languages, as well as full stack web development. I have a great eye for detail and am always striving to create the most efficient and user-friendly applications possible. 
              I am also an avid learner, always looking for new and inventive ways to develop my skills and stay ahead of the curve.
            </p>
            <p class="about-wrapper__info-text">
              My enthusiasm for technology and software development drives me to stay up to date on the latest trends and advancements in the industry. 
              I am a big believer in the power of technology and its potential to change the world.
            </p>
            <span class="about-wrapper__cta">
              <a href="#" class="cta-btn cta-btn--resume">View Resume</a>
            </span>
          </div>
        </div>
      </div>
    </section>
    <!-- /END About Section -->

    <!--Projects Section-->
    <section id="projects">
      <div class="container">
        <div class="project-wrapper">
          <h2 class="section-title dark-blue-text">Projects</h2>

          <!-- Each .row is a project -->
          <article class="row">
            <div class="project-wrapper__text">
              <h3 class="project-wrapper__text-title">GPT-Cli</h3>
              <p class="project-wrapper__text-info">
                This is a revolutionary tool for anyone looking to enhance their daily productivity.
                With its easy-to-use command line interface, it allows users to quickly and effectively access GPT features such as NLP and Text-To-Image conversion.  
                It's an invaluable script for anyone looking to increase their efficiency and get more out of their day. 
                The repo is also constantly updated with new features, making it an ever-evolving tool that can help users stay on top of their workload.  
              </p>
              <div class="project-wrapper__text-btns">
                <a
                  href="https://github.com/Simatwa/gpt-cli/raw/main/main.py"
                  target="_blank"
                  rel="noopener noreferrer"
                  class="cta-btn cta-btn--hero cta-btn--projects"
                  >See Live</a
                >
                <a href="https://github.com/Simatwa/gpt-cli" target="_blank" class="cta-btn text-color-main"
                  >Source Code</a
                >
              </div>
            </div>

            <div class="project-wrapper__image">
              <a href="#" target="_blank" rel="noopener noreferrer">
                <div class="thumbnail rounded">
                  <img
                    src="https://github.com/Simatwa/gpt-cli/raw/main/assets/logo_comic.png"
                    class="img-fluid"
                    alt="Project Image"
                    width="1366"
                    height="767"
                  />
                </div>
              </a>
            </div>
          </article>
          <!-- /END Project -->

          <!-- Each .row is a project -->
          <article class="row">
            <div class="project-wrapper__text">
              <h3 class="project-wrapper__text-title">smartbetsAPI</h3>
              <p class="project-wrapper__text-info">
                A <strong>python</strong> package and a REST-API that enables users to make smarter football predictions. It provides up-to-date information on different betting markets and allows punters to make informed decisions. 
                It is the perfect tool for anyone looking to increase their chances of winning in the betting world.. 
                It is an essential part of any modern betting strategy and is sure to help improve your chances of success.
              </p>
              <div class="project-wrapper__text-btns">
                <a
                  href="http://pypi.org/project/smartbetsAPI"
                  target="_blank"
                  rel="noopener noreferrer"
                  class="cta-btn cta-btn--hero cta-btn--projects"
                  >See Live</a
                >
                <a href="https://github.com/Simatwa/smartbetsAPI" target="_blank" class="cta-btn text-color-main"
                  >Source Code</a
                >
              </div>
            </div>

            <div class="project-wrapper__image">
              <a href="#" target="_blank" rel="noopener noreferrer">
                <div class="thumbnail rounded">
                  <img
                    src="https://github.com/Simatwa/smartbetsAPI/raw/main/assets/logo.png"
                    class="img-fluid"
                    alt="Project Image"
                    width="1366"
                    height="767"
                  />
                </div>
              </a>
            </div>
          </article>
          <!-- /END Project -->

          <!-- Each .row is a project -->
          <article class="row">
            <div class="project-wrapper__text">
              <h3 class="project-wrapper__text-title">yt5</h3>
              <p class="project-wrapper__text-info">
                This is a must have tool to any YouTube user! With yt5, you can download YouTube videos and audios from playlists, channels, or even just a single video from any resolution starting from 720p and below - all from the comfort of your terminal environment. 
                Forget about having to download a specific program to watch your favorite videos - with this, you can conveniently store your favorite YouTube videos with ease!
              </p>
              <div class="project-wrapper__text-btns">
                <a
                  href="https://github.com/Simatwa/gpt-cli/raw/main/main.py"
                  target="_blank"
                  rel="noopener noreferrer"
                  class="cta-btn cta-btn--hero cta-btn--projects"
                  >See Live</a
                >
                <a href="https://github.com/Simatwa/gpt-cli/" target="_blank" class="cta-btn text-color-main"
                  >Source Code</a
                >
              </div>
            </div>

            <div class="project-wrapper__image">
              <a href="#" target="_blank" rel="noopener noreferrer">
                <div class="thumbnail rounded">
                  <img
                    src="https://github.com/Simatwa/yt5/raw/main/assets/logo_comic.png"
                    class="img-fluid"
                    alt="Project Image"
                    width="1366"
                    height="767"
                  />
                </div>
              </a>
            </div>
          </article>
          <!-- /END Project -->

          <!-- Each .row is a project -->
          <article class="row">
            <div class="project-wrapper__text">
              <h3 class="project-wrapper__text-title">tdwnsv3</h3>
              <p class="project-wrapper__text-info">
                This amazing script, tdwnsv3, provides users with an incredible server that enables them to access their local files through any web-browser.
                 Not only can you download and upload files to it easily, but you can also rest assured that the highest security protocols are in place, providing the ultimate peace of mind. 
                 With tdwnsv3, you can quickly and easily manage your files from anywhere on the go. Try tdwnsv3 today and take back control of your files.
              </p>
              <div class="project-wrapper__text-btns">
                <a
                  href="https://github.com/Simatwa/tdwnsv3/raw/main/main.py"
                  target="_blank"
                  rel="noopener noreferrer"
                  class="cta-btn cta-btn--hero cta-btn--projects"
                  >See Live</a
                >
                <a href="https://github.com/Simatwa/tdwnsv3/" target="_blank" class="cta-btn text-color-main"
                  >Source Code</a
                >
              </div>
            </div>

            <div class="project-wrapper__image">
              <a href="#" target="_blank" rel="noopener noreferrer">
                <div class="thumbnail rounded">
                  <img
                    src="https://github.com/Simatwa/tdwnsv3/raw/main/assets/comic_logo.png"
                    class="img-fluid"
                    alt="Project Image"
                    width="1366"
                    height="767"
                  />
                </div>
              </a>
            </div>
          </article>

        </div>
      </div>
    </section>
    <!-- End Projects Section -->

    <!-- Contact Section -->
    <section id="contact">
      <div class="container">
        <h2 class="section-title">Contact</h2>
        <div class="contact-wrapper">
          <p class="contact-wrapper__text">+254774304553</p>
          <a href="tel:+254774304553" class="cta-btn cta-btn--resume">Call to Action</a>
        </div>
      </div>
    </section>
    <!-- END Contact Section -->

    <!-- Footer Section -->
    <footer class="footer">
      <div class="container">
        <a href="#hero" class="back-to-top" aria-label="go back to top">
          <i class="fa fa-angle-up fa-2x" aria-hidden="true"></i>
        </a>
        <div class="social-links">
          <a
            href="#!"
            target="_blank"
            rel="noopener noreferrer"
            aria-label="twitter"
          >
            <i class="fa-brands fa-twitter"></i>
          </a>
          <a
            href="#!"
            target="_blank"
            rel="noopener noreferrer"
            aria-label="instagram"
          >
            <i class="fa-brands fa-instagram"></i>
          </a>
          <a
            href="#!"
            target="_blank"
            rel="noopener noreferrer"
            aria-label="codepen"
          >
            <i class="fa-brands fa-codepen"></i>
          </a>
          <a
            href="#!"
            target="_blank"
            rel="noopener noreferrer"
            aria-label="linkedin"
          >
            <i class="fa-brands fa-linkedin"></i>
          </a>
          <a
            href="#!"
            target="_blank"
            rel="noopener noreferrer"
            aria-label="github"
          >
            <i class="fa-brands fa-github"></i>
          </a>
        </div>
        <hr />
        <p class="footer__text">
          &copy; <span id="year"></span> - Template by
          <a
            href="https://github.com/Simatwa"
            target="_blank"
            rel="noopener noreferrer"
            >Simatwa Caleb</a
          >. <br />Made with &hearts;
        </p>
      </div>
    </footer>
    <!-- END Footer Section -->

    <script>
      document.getElementById("year").textContent = new Date().getFullYear()
    </script>
    <script src="javascript/vanilla-tilt.min.js"></script>
    <script type="text/javascript" src="javascript/valtilt.js"></script>
  </body>
</html>
```