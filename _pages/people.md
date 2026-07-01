---
title: "Lab Members"
layout: category
permalink: /people/
author_profile: true
classes: wide
---

<div class="people-grid">
  <div class="people-card">
    <div class="people-card__avatar">
      <img src="/assets/img/members/yoonhonam.png" alt="Yoonho Nam">
    </div>
    <p class="people-card__name">Yoonho Nam</p>
    <p class="people-card__name-ko">남윤호</p>
    <p class="people-card__role">Principal Investigator</p>
    <div class="people-card__links">
      <a href="https://yoonhonam.github.io" title="Homepage"><i class="fas fa-globe"></i></a>
      <a href="mailto:yoonhonam@hufs.ac.kr" title="Email"><i class="fas fa-envelope"></i></a>
      <a href="https://scholar.google.com/citations?user=UZcwGAoAAAAJ" title="Google Scholar"><i class="fas fa-graduation-cap"></i></a>
    </div>
  </div>

  <div class="people-card">
    <div class="people-card__avatar">
      <img src="/assets/img/members/junghwakang.png" alt="Junghwa Kang">
    </div>
    <p class="people-card__name">Junghwa Kang</p>
    <p class="people-card__name-ko">강정화</p>
    <p class="people-card__role">Ph.D. Student</p>
    <div class="people-card__links">
      <a href="#" title="Email"><i class="fas fa-envelope"></i></a>
    </div>
  </div>

  <div class="people-card">
  <div class="people-card__avatar">
      <img src="/assets/img/members/hs.png" alt="Dayeon Bak">
    </div>
    <p class="people-card__name">Dayeon Bak</p>
    <p class="people-card__name-ko">박다연</p>
    <p class="people-card__role">M.S. Student</p>
  </div>

  <div class="people-card">
    <div class="people-card__avatar"><span class="people-card__initial">이</span></div>
    <p class="people-card__name">이지후</p>
    <p class="people-card__role">Undergraduate Intern</p>
  </div>

  <div class="people-card">
    <div class="people-card__avatar"><span class="people-card__initial">신</span></div>
    <p class="people-card__name">신채윤</p>
    <p class="people-card__role">Undergraduate Intern</p>
  </div>

  <div class="people-card">
    <div class="people-card__avatar"><span class="people-card__initial">신</span></div>
    <p class="people-card__name">신재범</p>
    <p class="people-card__role">Undergraduate Intern</p>
  </div>

  <div class="people-card">
    <div class="people-card__avatar"><span class="people-card__initial">박</span></div>
    <p class="people-card__name">박선민</p>
    <p class="people-card__role">Undergraduate Intern</p>
  </div>

  <div class="people-card">
    <div class="people-card__avatar"><span class="people-card__initial">김</span></div>
    <p class="people-card__name">김예은</p>
    <p class="people-card__role">Undergraduate Intern</p>
  </div>  

  <div class="people-card">
    <div class="people-card__avatar"><span class="people-card__initial">김</span></div>
    <p class="people-card__name">임자이</p>
    <p class="people-card__role">Undergraduate Intern</p>
  </div>  

  <div class="people-card">
    <div class="people-card__avatar"><span class="people-card__initial">김</span></div>
    <p class="people-card__name">마정미</p>
    <p class="people-card__role">Undergraduate Intern</p>
  </div>  

  <div class="people-card">
    <div class="people-card__avatar"><span class="people-card__initial">송</span></div>
    <p class="people-card__name">송준영</p>
    <p class="people-card__role">Undergraduate Intern</p>
  </div>

  <div class="people-card">
    <div class="people-card__avatar"><span class="people-card__initial">김</span></div>
    <p class="people-card__name">김우진</p>
    <p class="people-card__role">Undergraduate Intern</p>
  </div>





</div>

<div class="slideshow" id="mainSlideshow">
  <img class="slideshow__slide active" src="/assets/images/2026/ISMRM2026_01.jpeg" alt="">
  <img class="slideshow__slide" src="/assets/images/2025/ICMRI2025_04.jpeg" alt="">
  <img class="slideshow__slide" src="/assets/images/2025/2025-09-24-C.jpeg" alt="">
  <img class="slideshow__slide" src="/assets/images/2025/2025-09-24-B.jpeg" alt="">
  <img class="slideshow__slide" src="/assets/images/members/IMG_5115.jpeg" alt="">
  <img class="slideshow__slide" src="/assets/images/members/IMG_6226.jpg" alt="">
  <img class="slideshow__slide" src="/assets/images/members/IMG_6224.jpeg" alt="">
  <img class="slideshow__slide" src="/assets/images/members/IMG_4464.jpeg" alt="">
  <button class="slideshow__btn slideshow__btn--prev" aria-label="Previous">&#10094;</button>
  <button class="slideshow__btn slideshow__btn--next" aria-label="Next">&#10095;</button>
  <div class="slideshow__dots">
    <button class="slideshow__dot active"></button>
    <button class="slideshow__dot"></button>
    <button class="slideshow__dot"></button>
    <button class="slideshow__dot"></button>
    <button class="slideshow__dot"></button>
    <button class="slideshow__dot"></button>
    <button class="slideshow__dot"></button>
    <button class="slideshow__dot"></button>
  </div>
</div>

<script>
(function() {
  var slides = document.querySelectorAll('#mainSlideshow .slideshow__slide');
  var dots   = document.querySelectorAll('#mainSlideshow .slideshow__dot');
  var cur = 0, timer;

  function goTo(n) {
    slides[cur].classList.remove('active');
    dots[cur].classList.remove('active');
    cur = (n + slides.length) % slides.length;
    slides[cur].classList.add('active');
    dots[cur].classList.add('active');
  }

  function start() { timer = setInterval(function(){ goTo(cur + 1); }, 8000); }

  document.querySelector('#mainSlideshow .slideshow__btn--next').addEventListener('click', function(){ clearInterval(timer); goTo(cur + 1); start(); });
  document.querySelector('#mainSlideshow .slideshow__btn--prev').addEventListener('click', function(){ clearInterval(timer); goTo(cur - 1); start(); });
  dots.forEach(function(d, i){ d.addEventListener('click', function(){ clearInterval(timer); goTo(i); start(); }); });

  start();
})();
</script>


<h2 class="tch-section">Alumni</h2>

<div class="people-grid">
  <div class="people-card">
    <div class="people-card__avatar">
      <span class="people-card__initial">정</span>
    </div>
    <p class="people-card__name">Woojin Chung</p>
    <p class="people-card__name-ko">정우진</p>
    <p class="people-card__role">M.S. (2026)</p>
    <div class="people-card__links">
      <a href="https://sites.google.com/view/woojinchung/" title="Homepage"><i class="fas fa-globe"></i></a>
      <a href="mailto:woojin.chung@stonybrook.edu" title="Email"><i class="fas fa-envelope"></i></a>
    </div>
  </div>

  <div class="people-card">
    <div class="people-card__avatar"><span class="people-card__initial">김</span></div>
    <p class="people-card__name">Wooseung Kim</p>
    <p class="people-card__name-ko">김우승</p>
    <p class="people-card__role">Undergraduate Intern</p>
  </div>


</div>


---

<details>
  <summary><i>Past Undergraduate Interns</i></summary>
  <ul>
    <li>2019: 김현하 (BME16), 김은진 (BME16), 김은비 (BME16), 이혜빈 (BME16), 고인경 (BME17), 임지선 (BME17)</li>
    <li>2020: 김성용 (BME16), 장승운 (BME16), 유환승 (BME16), 김현진 (BME17), 백다영 (BME17), 정시윤 (BME18)</li>
    <li>2021: 유영범 (BME16), 김규아 (BME19), 류진하 (BME19), 유내정 (BME19), 김영주 (BME19), 이수민 (BME19), 김수민 (BME19)</li>
    <li>2022: 김하람 (BME17), 배강현 (BME18), 지종민 (BME18), 김수연 (BME19), 정은선 (BME19), 박민정 (BME20), 박찬희 (BME20)</li>
    <li>2023: 권오준 (BME19), 이승주 (BME19), 최대현 (BME19), 박지현 (BME20), 조현서 (BME20), 유하경 (BME20), 권은아 (화공19)</li>
    <li>2024: 김우승 (BME18), 유창민 (BME19), 강대홍 (BME20), 이인성 (BME20), 김송희 (BME22), 이근혜 (BME21)</li>
    <li>2025: 이나림 (BME22), 정혜교 (수학22)</li>
  </ul>
</details>
