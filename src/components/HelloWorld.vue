<template >
  <div class="main-component">
    <header>
      <div @click="openMenu" class="menu-toggler">
        <div class="bar half start"></div>
        <div class="bar"></div>
        <div class="bar half end"></div>
      </div>
      <nav class="top-nav">
        <ul class="nav-list">
          <li>
            <a href="" @click.prevent="goToMenu" class="nav-link">Home</a>
          </li>
          <li>
            <a @click="goToMenu" class="nav-link">About</a>
          </li>
          <li>
            <a @click="goToMenu" class="nav-link">Services</a>
          </li>
          <li>
            <a @click="goToMenu" class="nav-link">Portfolio</a>
          </li>
          <li>
            <a @click="goToMenu" class="nav-link">Experience</a>
          </li>
          <li>
            <a @click="goToMenu" class="nav-link">Contact</a>
          </li>
        </ul>
      </nav>
      <div class="landing-text">
        <h1>Luis Belis</h1>
        <h6>Software Engineer | Full-Stack Developer</h6>
      </div>
    </header>

    <section class="about" id="about">
      <div class="container">
        <div class="profile-img" data-aos="fade-right" data-aos-delay="200">
          <img src="../images/profile.jpg" alt="">
        </div>
        <div class="about-details" data-aos="fade-left" data-aos-delay="200">
          <div class="about-heading">
            <h4>A little</h4>
            <h1>About</h1>
            <h6>Myself</h6>
          </div>
          <p>
            I am a self-motivated and hard-working engineer who is passionate and committed to learn
            new technologies to meet requirements. I do not believe we should stick to one way to 
            solve a problem. As engineers, we must be ready to take on the best solution so we can
            guarantee the customer satisfaction.
          </p>
          <div class="social-media">
          <ul class="nav-list">
            <li>
              <a target="_blank" href="https://www.facebook.com/luisalfredo.belisdilone" class="icon-link">
                <i class="fab fa-facebook-square"></i>
              </a>
            </li>
            <li>
              <a target="_blank" href="https://github.com/zeratul117" class="icon-link">
                <i class="fab fa-github"></i>
              </a>
            </li>
            <li>
              <a target="_blank" href="https://www.linkedin.com/in/luis-belis-755426186/" class="icon-link">
                <i class="fab fa-linkedin"></i>
              </a>
            </li>
          </ul>
        </div>
        </div>
      </div>
    </section>

    <section class="services" id="services">
      <div class="containder">
        <div class="section-heading">
          <h1>Skills</h1>
          <h6>What I can do for you</h6>
        </div>
        <div class="my-skills" data-aos="flip-left" data-aos-delay="200">
          <div class="skill">
            <div class="icon-container">
              <i class="fab fa-js-square"></i>
            </div>
            <h1>Web Development</h1>
            <p>
              <i class="fas fa-hand-holding"></i>&nbsp;JavaScript and some of its frameworks (Angular, Vue.js) <br>
              <i class="fas fa-hand-holding"></i>&nbsp;Designer tools (CSS, NG-Zorro, Bootstrap, Vutify) <br>
            </p>
          </div>
          <div class="skill">
            <div class="icon-container">
              <i class="fas fa-database"></i>
            </div>
            <h1>Database</h1>
            <p>
              <i class="fas fa-hand-holding"></i>&nbsp;Good experience with Transact-SQL <br>
              <i class="fas fa-hand-holding"></i>&nbsp;Capable of creating stored procedures
            </p>
          </div>
          <div class="skill">
            <div class="icon-container">
              <i class="fas fa-layer-group"></i>
            </div>
            <h1>Backend experience</h1>
            <p>
              <i class="fas fa-hand-holding"></i>&nbsp;C# language with ASP.NET/ASP.NET Core <br>
            </p>
          </div>
        </div>
      </div>
    </section>
    <section class="portfolio" id="portfolio">
      <div class="containder">
        <div class="section-heading">
          <h1>Portfolio</h1>
          <h6>View some of my recent work</h6>
        </div>
        <div class="portfolio-item">
          <div class="portfolio-img has-margin-right" data-aos="zoom-in-left" data-aos-delay="200">
            <img src="../images/profile.jpg" alt="">
          </div>
          <div class="portfolio-description" data-aos="zoom-in-right" data-aos-delay="200">
            <h6>Web Development</h6>
            <h1>Blog Website</h1>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
            </p>
            <a href="#" class="cta">View Details</a>
          </div>
        </div>
        <div class="portfolio-item">
          <div class="portfolio-description" data-aos="zoom-in-left" data-aos-delay="200">
            <h6>Web Design</h6>
            <h1>Product Layout</h1>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
            </p>
            <a href="#" class="cta">View Details</a>
          </div>
          <div class="portfolio-img" data-aos="zoom-in-right" data-aos-delay="200">
            <img src="../images/profile.jpg" alt="">
          </div>
        </div>
        <div class="portfolio-item">
          <div class="portfolio-img has-margin-right" data-aos="zoom-in-left" data-aos-delay="200">
            <img src="../images/profile.jpg" alt="">
          </div>
          <div class="portfolio-description" data-aos="zoom-in-right" data-aos-delay="200">
            <h6>Web Design</h6>
            <h1>Product Sketch</h1>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
            </p>
            <a href="#" class="cta">View Details</a>
          </div>
        </div>
      </div>
    </section>

    <section class="experience" id="experience">
      <div class="containder">
        <div class="section-heading">
          <h1>Work Experience</h1>
          <h6>Past and current jobs</h6>
        </div>
        <div class="time-line" data-aos="zoom-in" data-aos-delay="200">
          <ul>
            <li class="date" data-date="2011 - Present">
              <h1>Google</h1>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
              </p>
            </li>
            <li class="date" data-date="2008 - 2011">
              <h1>Facebook</h1>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
              </p>
            </li>
            <li class="date" data-date="2000 - 2007">
              <h1>Twitter</h1>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
              </p>
            </li>
          </ul>
        </div>
      </div>
    </section>

    <section class="contact" id="contact">
      <div class="containder">
        <div class="section-heading">
          <h1>Contact</h1>
          <h6>Let's work together</h6>
        </div>
        <form action="">
          <label for="name">Name:</label>
          <input type="text" name="name" id="name" placeholder="Enter your name..." required>
          <label for="email">Email:</label>
          <input type="email" name="email" id="email" placeholder="Enter your email..." required>
          <label for="service">Services:</label>
          <select name="service" id="service">
            <option value="">Web Design</option>
            <option value="">Web Development</option>
            <option value="">Web Development/Design</option>
          </select>
          <label for="subject">Subject:</label>
          <textarea name="subject" id="subject" cols="10" rows="10"></textarea>
          <input type="submit" value="Submit">
        </form>
      </div>
    </section>
    <footer class="copyright">
      <div class="up" id="up" @click="goUp">
        <i class="fas fa-chevron-up"></i>
      </div>
      <p>&copy; 2019 Luis Belis</p>
    </footer>

  </div>
</template>
<script>
export default {
  name: 'HelloWorld',
  data() {
    return {
      topNav: document.getElementsByClassName('top-nav'),
      menuToggler: document.getElementsByClassName('menu-toggler')
    }
  },
  created() {

  },
  methods: {
    openMenu(e) {
      e.target.classList.toggle('open')
      this.topNav[0].classList.toggle('open')
    },
    goToMenu(e) {   
      this.menuToggler[0].classList.remove('open')
      this.topNav[0].classList.remove('open')
      document.getElementById(e.target.innerHTML.toLowerCase())
      .scrollIntoView({ behavior: 'smooth' })
    },
    goUp() {
      document.getElementsByClassName('main-component')[0].scrollIntoView({ behavior: 'smooth'})
    }
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
