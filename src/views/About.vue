<template>
  <div class="about">
    <div class="row">
      <div class="my-photo">
        <img src="../assets/images/okanuix.jpg" alt />
      </div>
      <div class="about-me">
        <div class="text text-product"></div>
        <div class="text text-ui-ux"></div>
        <div class="text text-designer"></div>
        <p>
          <span class="bold">Okan Yıkmış</span> is senior product designer,
          working in the industry for over 10+ Years
        </p>
        <p class="p2">
          I craft interactive stories, responsible for designing interactive
          experiences and create strategies for services from the customer’s
          perspective is essential for delivering an end-to-end experience and
          concept strategies with great care.
        </p>
        <p class="p2">
          Currently based in Istanbul as a
          <span class="bold">Senior Product Designer</span> for
          <span class="bold">TRT</span>
        </p>
      </div>
    </div>
    <div class="row my-expertise-background">
      <div class="my-expertise-1">
        <ul>
          <span class="list-title">UX</span>
          <li>Research & Analysis</li>
          <li>UX Brand Strategies</li>
          <li>Whiteboard Concept Sessions</li>
          <li>Wireframes Moodboards</li>
          <li>Persona Research Interactive</li>
          <li>Screen Prototypes</li>
          <li>Pre-visualization</li>
          <li>Process Customer</li>
          <li>Journey Research</li>
        </ul>
      </div>
      <div class="my-expertise-2">
        <ul>
          <span class="list-title">UI</span>
          <li>Visual Designs & Specs</li>
          <li>Web Design</li>
          <li>App Design</li>
          <li>Visual Identities</li>
          <li>Interaction Design</li>
          <li>Real Prototypes</li>
          <li>Motion Design for UI Elements</li>
        </ul>
      </div>
    </div>
    <div class="brands">
      <ul>
        <li>
          <img src="../assets/images/Turkish-Airlines.svg" alt />
        </li>
        <li>
          <img src="../assets/images/TRT-World.svg" alt />
        </li>
        <li>
          <img src="../assets/images/turkcell.svg" alt />
        </li>
        <li>
          <img src="../assets/images/garanti.svg" alt />
        </li>
        <li>
          <img src="../assets/images/trt.svg" alt />
        </li>
      </ul>
    </div>
    <div class="lets-do">
      <a class="mail-box" href="mailto: okanyikmis@gmail.com"
        ><i class="icon"></i
      ></a>
      <p class="lets">Let’s do a project together</p>
      <a href="mailto: okanyikmis@gmail.com">Contact with me</a>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.brands {
  ul {
    margin-bottom: 250px;
    display: grid;
    grid-gap: 3rem;
    grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
    padding: 0 17vw;
    justify-items: center;
  }
}
ul {
  font-family: Gilroy-Light;
  font-size: 24px;
  line-height: 52px;
  /* or 217% */
  color: #ffffff;
  margin-top: 55px;

  li {
    margin-bottom: 5px;
  }

  .list-title {
    font-family: Gilroy;
    font-style: normal;
    font-weight: bold;
    font-size: 40px;
    line-height: 50px;
    /* identical to box height */

    color: #ffffff;

    margin-bottom: 17px;
  }
}
.about {
  .row {
    padding: 0 17vw;
    margin-top: 200px;
    display: grid;
    grid-gap: 1rem;
    grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
  }
}

.my-expertise-background {
  background: url(../assets/images/my-expertise-background.png);
  background-size: 60% 100%;
  background-repeat: no-repeat;
  background-position: 190px 0px;
}

.my-expertise-1 {
  height: 898px;

  .title {
    background: url(../assets/images/my-expertise.svg);
    background-size: 100% 100%;
    width: 471px;
    height: 99px;
    margin-left: -6rem;
  }
}

.my-expertise-2 {
  margin-left: 13rem;
}

.about-me {
  margin-left: 100px;

  p {
    margin-left: 20px !important;
    font-family: Gilroy-Light;
    font-size: 24px;
    line-height: 38px;
    margin: 30px 0;
    display: flex;
    align-items: center;
    letter-spacing: 0.2px;

    span.bold {
      font-family: Gilroy;
      font-weight: bold;
      display: contents;
    }
  }

  .p2 {
    font-size: 18px;
    line-height: 28px;

    letter-spacing: 0.2px;
  }

  .p3 {
    font-size: 18px;
    line-height: 28px;
    letter-spacing: 0.2px;
    opacity: 0.5;
  }
}

.text {
  display: block;
  background-size: 100% 100%;

  &.text-product {
    display: inline-block;
    background: url(../assets/images/product.svg);
    margin-top: 80px;
    margin-left: -490px;
    width: 455.15px;
    height: 75.2px;
  }

  &.text-ui-ux {
    display: inline-block;
    background: url(../assets/images/ui-ux.svg);
    width: 235.25px;
    height: 71.4px;
    margin-left: 30px;
  }

  &.text-designer {
    background: url(../assets/images/designer.svg);
    width: 464.31px;
    height: 75.2px;
    margin-top: 35px;
  }
}

.lets-do {
  text-align: center;
  margin-bottom: 100px;
  padding: 0 15vw;

  p {
    margin-top: 33px;
    line-height: 1;
  }

  .mail-box {
    display: grid;
    justify-content: center;
    .icon {
      background: url(../assets/images/mail-box.png);
      width: 58px;
      height: 44px;
    }
  }
}

.lets {
  font-weight: bold;
  font-size: 48px;
  line-height: 40px;
  color: #ffffff;
}

a {
  font-family: Gilroy-Light;
  font-weight: 300;
  font-size: 28px;
  line-height: 28px;
  /* identical to box height, or 100% */
  color: #ffffff;
  text-decoration: none;
  cursor: none;
}
</style>