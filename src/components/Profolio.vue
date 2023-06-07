<template>
  <div>
    <div class="flex items-center flex-col justify-around min-h-[100vh]">
      <VueTypedJs class="fontStyle text-[100px] font-bold" :strings="['My Portfolio']" :loop="true" :typeSpeed="100">
        <div class="typing"></div>
      </VueTypedJs>
      <img class="mx-auto" src="Icon.png">
      <div class="flex justify-between options font-extrabold">
        <a href="#intro" class="mr-[70px] cursor-pointer hover:text-gray-600 hover:text-xl" id="intro-link">INTRO</a>
        <a href="#work" class="cursor-pointer hover:text-gray-600 hover:text-xl" id="work-link">WORK EXPERIENCE</a>
        <a href="#skills" class="ml-[70px] cursor-pointer hover:text-gray-600 hover:text-xl" id="skills-link">SKILLS</a>
      </div>
    </div>
    <div id="intro" class="min-h-[100vh] shadow-xl  m-[200px] px-5 bg-slate-200 opacity-90 rounded-xl">
      <div>
        <VueTypedJs class="fontStyle text-[100px] font-extrabold" :strings="['INTRO']" :loop="true" :typeSpeed="150">
          <div class="typing"></div>
        </VueTypedJs>
      </div>
      <div class="flex justify-between flex-col">
        <div class="ml-[20px] my-auto options text-8xl font-bold p-5">Hi, I'm <span
            class="bg-yellow-200">Nelson Ng</span></div>
        <div class="ml-[20px] my-auto options text-8xl font-bold p-5">I <span
            class="stroke text-white hover:text-black hover:bg-purple-400">code</span>, <span
            class="stroke text-white hover:text-black hover:bg-blue-400">debug</span> & <span
            class="stroke text-white hover:text-black hover:bg-emerald-400">stylize</span>.
        </div>
        <div class="ml-[20px] my-auto options text-3xl font-bold p-5 leading-relaxed">I'm a student in the School of
          Professional Education and Executive Development at The Hong Kong Polytechnic University. My major is
          Information Systems and Web Technologies, and I've studied programming languages like JAVA and HTML. And,
          during my studies, I completed several projects, such as creating a little game using JAVA, website that
          consists frontend and backend operation. Since then, I've gained a lot of experience using various coding
          abilities in various situations, and I find it fascinating to develop something that has never been before. As
          a result, I'd want to locate a similar organization where I can do my best to meet and complete all of the
          needs and chores.
        </div>
        <img class="mx-auto" src="https://joyofcoding.org/2022/img/logo-text.png" width="400">
      </div>
    </div>
    <div id="work" class="min-h-[100vh] shadow-x m-[200px] px-5 bg-slate-200 opacity-90 rounded-xl">
      <VueTypedJs class="fontStyle text-[100px] font-extrabold" :strings="['WORK EXPERIENCE']" :loop="true" :typeSpeed="100">
        <div class="typing"></div>
      </VueTypedJs>
      <div class="flex justify-between flex-col">
        <div class="shadow-xl mx-[60px] flex justify-around hover:shadow-2xl">
          <div>
            <div class="text-4xl font-bold italic">Products promoter(6/2019-12/2020)</div>
            <br>
            <div class="font-bold text-2xl options">Objectives</div>
            <br>
            <ul class="font-bold text-2xl options">
              <li> Responsible to sell the products and explain the detail to different customers</li>
              <li> Set and clean up the promoting venue</li>
              <li> Fulfilling the enquiry from the customers</li>
            </ul>
          </div>
          <div><img
              src="https://images.squarespace-cdn.com/content/v1/587a127129687f8f4b9c7686/1578995145954-8T8TTM7CNAQBQLTZDWMU/image-asset.png?format=1000w"
              width="350"></div>
        </div>
        <div class="shadow-xl mx-[60px] mt-6 flex justify-around hover:shadow-2xl">
          <div><img src="http://trafolife.com/wp-content/uploads/2015/09/CX_Logo.jpg" width="320"></div>
          <div>
            <div class="text-4xl font-bold italic">Cathay Pacific Catering Service(1/2021-4/2021)</div>
            <br>
            <div class="font-bold text-2xl options">Objectives</div>
            <br>
            <ul class="font-bold text-2xl options">
              <li> Perform in-house and airport ramp areas patrolling and report irregularities</li>
              <li> Coordinate transportation service arrangement and answer enquiries from customers</li>
              <li> Understand and uphold company quality standards in terms of hygiene, safety and security
                requirement
              </li>
            </ul>
          </div>
        </div>
        <div class="shadow-xl mx-[60px] mt-6 flex justify-around hover:shadow-2xl">
          <div>
            <div class="text-4xl font-bold italic">Internship of China Mobile of Hong Kong(1/2022-Current)</div>
            <br>
            <div class="font-bold text-2xl options">Objectives</div>
            <br>
            <ul class="font-bold text-2xl options">
              <li> Improve the design of the webpage</li>
              <li> Fulfill the requirement from the customers in order to achieve user-friendly</li>
              <li> Debugging the errors that occur in the webpage, for instance shopping cart, online shop</li>
            </ul>
          </div>
          <div><img
              src="https://images.contentstack.io/v3/assets/blt5ed02e814e78b7c4/bltfd7ad6abb07021af/5f8e39784671ee30c689faf6/China_Mobile_logo_540_360.jpg"
              width="320"></div>
        </div>
      </div>
    </div>
    <div id="skills" class="min-h-[100vh] shadow-xl  m-[200px] px-5 bg-slate-200 opacity-90 rounded-xl">
      <VueTypedJs class="fontStyle text-[100px] font-extrabold" :strings="['SKILLS']" :loop="true" :typeSpeed="150">
        <div class="typing"></div>
      </VueTypedJs>
      <div class="flex justify-around text-center text-xl font-bold">
        <div class="shadow-xl flex-initial w-64">
          <img class="mx-auto" src="style.png">
          <div>
            Focus on the outlook of the product, concept forward of creative work and stylizing
          </div>
        </div>
        <div class="shadow-xl flex-initial w-64">
          <img class="mx-auto" src="web.png">
          <div>
            Experienced in using HTML to build a project, familiar with developing front-end
          </div>
        </div>
        <div class="shadow-xl flex-initial w-64">
          <img class="mx-auto" src="responsive.png">
          <div>
            Make the project more user-friendly and turns out all the project can look good in different screen size and
            viewports
          </div>
        </div>
        <div class="shadow-xl flex-initial w-64">
          <img class="mx-auto" src="innovative.png">
          <div>
            Able to utilize different knowledge to different part of the coding, make news changes for the webpage in
            order to attract users
          </div>
        </div>
      </div>
      <VueTypedJs class="fontStyle text-[100px] font-extrabold mt-[109px]" :strings="['PROJECTS']" :loop="true" :typeSpeed="150">
        <div class="typing"></div>
      </VueTypedJs>
      <div class="flex flex-col justify-around">

        <div class="shadow-xl mx-[60px] flex flex-row justify-around hover:shadow-2xl mt-[20px]">
          <div class=" w-1/2   mt-[20px]">
            <slider animation="fade">
              <slider-item
                  v-for="({url,width,height}, index) in list"
                  :key="index"
                  :style="{width,height}"
              >
                <img :src="url" style="width: 100%;height: 100%;object-fit: cover;">
              </slider-item>
            </slider>
        </div>
        <div class="text-4xl font-bold italic">Air Quality Checker</div>
        </div>
        <div class="shadow-xl mx-[60px] flex justify-around hover:shadow-2xl mt-[20px]">
          <div>
            <div class="text-4xl font-bold italic">Products promoter(6/2019-12/2020)</div>
            <br>
            <div class="font-bold text-2xl options">Objectives</div>
            <br>
            <ul class="font-bold text-2xl options">
              <li> Responsible to sell the products and explain the detail to different customers</li>
              <li> Set and clean up the promoting venue</li>
              <li> Fulfilling the enquiry from the customers</li>
            </ul>
          </div>
          <div><img
              src="https://images.squarespace-cdn.com/content/v1/587a127129687f8f4b9c7686/1578995145954-8T8TTM7CNAQBQLTZDWMU/image-asset.png?format=1000w"
              width="350"></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import {VueTypedJs} from 'vue-typed-js'
import {Slider, SliderItem} from 'vue-easy-slider'

function scrollToElement(selector) {
  const el = document.querySelector(selector);
  if (el) {
    const top = el.getBoundingClientRect().top + window.pageYOffset;
    window.scrollTo({ top, behavior: 'smooth' });
  }
}

document.addEventListener('DOMContentLoaded', function() {
  document.querySelector('#intro-link').addEventListener('click', function(event) {
    event.preventDefault();
    scrollToElement('#intro');
  });

  document.querySelector('#work-link').addEventListener('click', function(event) {
    event.preventDefault();
    scrollToElement('#work');
  });

  document.querySelector('#skills-link').addEventListener('click', function(event) {
    event.preventDefault();
    scrollToElement('#skills');
  });
});

export default {
  name: "myInfo",
  components: {
    VueTypedJs, Slider, SliderItem

  },
  data() {
    return {
      sliderIndex: 1,
      list: [
        {url: 'fyp1.png', width: '100%', height: '100%'},
        {url: 'fyp2.png', width: '100%', height: '100%'},
        {url: 'fyp3.png', width: '100%', height: '100%'},
      ],
    }
  },
  methods: {},
}
</script>

<style scoped>

.fontStyle {
  font-family: Verdana, sans-serif;
}

.options {
  font-family: Arial Narrow, sans-serif;
}

ul {
  list-style-type: ">";
  list-style-position: inside;
}

.stroke {
  -webkit-text-stroke-width: 1px;
  -webkit-text-stroke-color: black;
}

</style>