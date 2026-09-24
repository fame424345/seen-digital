<template>
<div class="page-blob blob-a" aria-hidden="true"></div>
<div class="page-blob blob-b" aria-hidden="true"></div>
<header ref="headerEl" :class="{ scrolled: isScrolled }">
<link href='https://fonts.googleapis.com/css?family=Noto Sans Thai' rel='stylesheet'>
  <nav class="nav">
    <a href="#" class="brand">SEEN<span>.</span></a>
    <div class="nav-links">
      <a href="#services">บริการ</a>
      <a href="#portfolio">ผลงาน</a>
      <a href="#process">วิธีทำงาน</a>
      <a href="#contact">ติดต่อ</a>
    </div>
    <a href="#contact" class="button-ui1">คุยงานกับเรา</a>
  </nav>
</header>

<main id="top">

  <section class="hero">
    <div class="wrap hero-grid">
      <div>
        <div class="eyebrow hero-sub-reveal">Digital Marketing Studio</div>
        <h1 class="hero-heading">
          <span
            v-for="(ch, i) in heroChars"
            :key="i"
            class="char-reveal"
            :style="{ animationDelay: (i * 0.04) + 's' }"
          >{{ ch }}</span>
        </h1>
        <p class="hero-sub-reveal">เราคือทีมการตลาดดิจิทัลที่ดูแลแบรนด์คุณตั้งแต่ผลการค้นหาบน Google คำตอบจาก AI ไปจนถึงฟีดโซเชียลที่ลูกค้าเลื่อนผ่านทุกวัน ให้ทุกจุดที่คนเจอแบรนด์คุณ นำไปสู่การตัดสินใจซื้อ</p>
        <div class="cta-row">
          <a href="#contact" class="button-ui1">คุยงานกับเรา</a>
          <a href="#portfolio" class="btn-secondary">ดูผลงาน</a>
        </div>
      </div>
    </div>
  </section>

  <section class="services" id="services">
  <div class="service-card">
    <div class="bg"></div>
    <div class="blob" style="background-color:var(--accent-search)"></div>
    <div class="service-content">
      <div class="service-name"><span class="service-dot" style="background:var(--accent-search)"></span>Search &amp; Answer Visibility</div>
      <p class="service-desc">ทำ SEO ให้ติดหน้าแรก Google ต่อยอดสู่ AEO และ GEO ให้แบรนด์ถูกพูดถึงเวลาคนถาม ChatGPT, Perplexity หรือ Google AI Overview</p>
      <div class="service-tags"><span>SEO</span><span>AEO</span><span>GEO</span></div>
    </div>
  </div>
  <div class="service-card">
    <div class="bg"></div>
    <div class="blob" style="background-color:var(--accent-social)"></div>
    <div class="service-content">
      <div class="service-name"><span class="service-dot" style="background:var(--accent-social)"></span>Social Presence</div>
      <p class="service-desc">วางแผนคอนเทนต์และดูแลช่องทางที่ลูกค้าคุณใช้จริง ตั้งแต่ Facebook Fanpage, LINE OA ไปจนถึง TikTok และ IG Reels</p>
      <div class="service-tags"><span>Facebook</span><span>LINE OA</span><span>TikTok</span><span>IG Reels</span></div>
    </div>
  </div>
  <div class="service-card">
    <div class="bg"></div>
    <div class="blob" style="background-color:var(--accent-ai)"></div>
    <div class="service-content">
      <div class="service-name"><span class="service-dot" style="background:var(--accent-ai)"></span>AI Marketing</div>
      <p class="service-desc">ใช้ AI วิเคราะห์พฤติกรรมลูกค้า ทำ personalization วางระบบแชทบอทอัตโนมัติ และผลิตคอนเทนต์แบบอิงข้อมูลจริง</p>
      <div class="service-tags"><span>Chatbot</span><span>Personalization</span></div>
    </div>
  </div>
  <div class="service-card">
    <div class="bg"></div>
    <div class="blob" style="background-color:var(--accent-web)"></div>
    <div class="service-content">
      <div class="service-name"><span class="service-dot" style="background:var(--accent-web)"></span>Website Development</div>
      <p class="service-desc">ออกแบบและพัฒนาเว็บไซต์ที่โหลดไว ใช้งานสะดวกบนมือถือ วางโครงสร้างที่เป็นมิตรกับ SEO ตั้งแต่วันแรก</p>
      <div class="service-tags"><span>UX/UI</span><span>Performance</span></div>
    </div>
  </div>
  <div class="service-card">
    <div class="bg"></div>
    <div class="blob" style="background-color:var(--accent-creative)"></div>
    <div class="service-content">
      <div class="service-name"><span class="service-dot" style="background:var(--accent-creative)"></span>Creative &amp; Design</div>
      <p class="service-desc">กราฟิกและอาร์ตเวิร์คสำหรับโพสต์และแคมเปญ ออกแบบ UX/UI และครีเอทีฟสื่อโฆษณาที่พร้อมยิงแอดได้ทันที</p>
      <div class="service-tags"><span>Graphic</span><span>UX/UI</span><span>Ads Creative</span></div>
    </div>
  </div>
  <div class="service-card">
    <div class="bg"></div>
    <div class="blob" style="background-color:var(--accent-media)"></div>
    <div class="service-content">
      <div class="service-name"><span class="service-dot" style="background:var(--accent-media)"></span>Paid Media</div>
      <p class="service-desc">วางแผนและดูแลแคมเปญยิงแอดให้ตรงกลุ่มเป้าหมายและคุ้มงบที่สุด ทั้ง Facebook Ads, Google Ads และ TikTok Ads</p>
      <div class="service-tags"><span>Facebook Ads</span><span>Google Ads</span><span>TikTok Ads</span></div>
    </div>
  </div>
  </section>
<section id="portfolio">
  <div class="wrap">
    <div class="section-head">
      <div class="kicker">ผลงาน</div>
      <h2>ตัวอย่างงานที่เราภูมิใจ</h2>
    </div>
  <div class="video-grid">
    <a class="video-card"
    href="https://www.tiktok.com/@lixel793/video/7530457311572233479"
    target="_blank"
    rel="noopener noreferrer"
     >
    <div class="bg"></div>
    <div class="blob" style="background-color:var(--accent-social)"></div>

    <div class="video-wrap">
      <div class="video-thumb">
        <img src="~/assets/images/S__36012034.jpg" alt="Maono DGM20 Microphone Condenser">
        <span class="play-btn">
          <svg viewBox="0 0 24 24"><path d="M8 5v14l11-7z"/></svg>
        </span>
      </div>
    </div>

    <div class="video-caption">
      <span class="tag" style="background:var(--accent-social)">TikTok</span>
      <h3>Maono DGM20 Microphone Condenser</h3>
      <p>รีวิวไมค์งบประหยัดเสียงดี คอนเทนต์ยอดวิวสูงจากแคมเปญ TikTok</p>
    </div>
  </a>
  <a class="video-card"
    href="https://www.tiktok.com/@99aplus/video/7634028782898171157"
    target="_blank"
    rel="noopener noreferrer"
     >
    <div class="bg"></div>
    <div class="blob" style="background-color:var(--accent-social)"></div>

    <div class="video-wrap">
      <div class="video-thumb">
        <img src="~/assets/images/3436.png" alt="CineTreak Mixer">
        <span class="play-btn">
          <svg viewBox="0 0 24 24"><path d="M8 5v14l11-7z"/></svg>
        </span>
      </div>
    </div>

    <div class="video-caption">
      <span class="tag" style="background:var(--accent-social)">TikTok</span>
      <h3>CineTreak Mixer Plus Video Switcher</h3>
      <p>Live Streaming และ Production</p>
    </div>
  </a>
   <div class="wide-stack">
    <div class="video-card wide">
      <div class="bg"></div>
      <div class="blob" style="background-color:var(--accent-search)"></div>
      <div class="video-wrap">
        <div class="video-thumb wide" @click="openLightbox">
          <img src="~/assets/images/seo23.png" alt="กราฟผลลัพธ์ SEO">
        </div>
      </div>
      <div class="video-caption">
        <span class="tag" style="background:var(--accent-search)">SEO Result</span>
        <h3>อันดับคีย์เวิร์ดที่ดีขึ้นต่อเนื่อง</h3>
        <p>กราฟแสดงอันดับ Google ที่ไต่ขึ้นตลอด 3 เดือนหลังเริ่มทำ SEO</p>
      </div>
    </div>


    <div class="video-card wide">
      <div class="bg"></div>
      <div class="blob" style="background-color:var(--accent-social)"></div>
      <div class="video-wrap">
        <div class="video-thumb wide" @click="openLightbox">
          <img src="~/assets/images/66710.png" alt="โพสต์ Facebook Fanpage">
        </div>
      </div>
      <div class="video-caption">
        <span class="tag" style="background:var(--accent-social)">Facebook</span>
        <h3>โพสต์ที่มี engagement สูงสุด</h3>
        <p>ผลตอบรับจากแคมเปญ Facebook Fanpage ที่ทำให้ยอดเข้าถึงพุ่ง</p>
      </div>
    </div>
    
</div>

<div class="artwork-grid">

  <!-- ชุดที่ 1 -->
 <div class="artwork-card landscape">
    <div class="bg"></div>
    <div class="blob" style="background-color:var(--accent-creative)"></div>
    <div class="artwork-wrap">
      <div class="artwork-main" @click="openLightbox('/images/portfolio/ch0.png')">
        <img src="~/assets/images/portfolio/ch0.png" alt="Ad creative set 1 main">
      </div>
      <div class="artwork-sub">
        <div class="artwork-sub-item" @click="openLightbox('/images/portfolio/ch1.png')">
          <img src="~/assets/images/portfolio/ch1.png" alt="Ad creative set 1 sub 1">
        </div>
        <div class="artwork-sub-item" @click="openLightbox('/images/portfolio/ch2.png')">
          <img src="~/assets/images/portfolio/ch2.png" alt="Ad creative set 1 sub 2">
        </div>
        <div class="artwork-sub-item" @click="openLightbox('/images/portfolio/ch3.png')">
          <img src="~/assets/images/portfolio/ch3.png" alt="Ad creative set 1 sub 3">
        </div>
      </div>
    </div>
    <div class="artwork-caption">
      <span class="tag" style="background:var(--accent-creative)">Ad Creative</span>
      <h3>สร้าง Campaign ลดราคาตามเทศกาล</h3>
      <p>โปรสินค้ารับตรุษจีนกระตุ้นยอดขายช่วงเทศกาล</p>
    </div>
  </div>

  <!-- ชุดที่ 2 -->
  <div class="artwork-card">
    <div class="bg"></div>
    <div class="blob" style="background-color:var(--accent-creative)"></div>
    <div class="artwork-wrap">
      <div class="artwork-main" @click="openLightbox('/images/portfolio/HLPRO1.png')">
        <img src="~/assets/images/portfolio/HLPRO1.png" alt="Ad creative set 2 main">
      </div>
      <div class="artwork-sub">
        <div class="artwork-sub-item" @click="openLightbox('/images/portfolio/HLPRO2.png')">
          <img src="~/assets/images/portfolio/HLPRO2.png" alt="Ad creative set 2 sub 1">
        </div>
        <div class="artwork-sub-item" @click="openLightbox('/images/portfolio/HLPRO3.png')">
          <img src="~/assets/images/portfolio/HLPRO3.png" alt="Ad creative set 2 sub 2">
        </div>
        <div class="artwork-sub-item" @click="openLightbox('/images/portfolio/HLPRO4.png')">
          <img src="~/assets/images/portfolio/HLPRO4.png" alt="Ad creative set 2 sub 3">
        </div>
      </div>
    </div>
    <div class="artwork-caption">
      <span class="tag" style="background:var(--accent-creative)">Ad Creative</span>
      <h3>เพิ่มการมองเห็นด้วยดีไซน์เรียบง่าย</h3>
      <p>ดึงดูดผู้คนให้สนใจด้วยดีไซน์ของเรา</p>
    </div>
  </div>

  <!-- ชุดที่ 3 -->
  <div class="artwork-card">
    <div class="bg"></div>
    <div class="blob" style="background-color:var(--accent-creative)"></div>
    <div class="artwork-wrap">
      <div class="artwork-main" @click="openLightbox('/images/portfolio/wrtsm2025.png')">
        <img src="~/assets/images/portfolio/wrtsm2025.png" alt="Ad creative set 3 main">
      </div>
      <div class="artwork-sub">
        <div class="artwork-sub-item" @click="openLightbox('/images/portfolio/wrtsm1.png')">
          <img src="~/assets/images/portfolio/wrtsm1.png" alt="Ad creative set 3 sub 1">
        </div>
        <div class="artwork-sub-item" @click="openLightbox('/images/portfolio/wrtsm2.png')">
          <img src="~/assets/images/portfolio/wrtsm2.png" alt="Ad creative set 3 sub 2">
        </div>
        <div class="artwork-sub-item" @click="openLightbox('/images/portfolio/wrtsm3.png')">
          <img src="~/assets/images/portfolio/wrtsm3.png" alt="Ad creative set 3 sub 3">
        </div>
      </div>
    </div>
    <div class="artwork-caption">
      <span class="tag" style="background:var(--accent-creative)">Ad Creative</span>
      <h3>วางแผนกลยุทธ์พร้อมดีไซน์</h3>
      <p>วางกลยุทธ์ยิงแอด ให้ตรงช่วงเวลา และกลุ่มเป้าหมาย</p>
    </div>
  </div>

</div>
</div>
</div>
<Teleport to="body">
  <div v-if="lightboxSrc" class="lightbox" @click="closeLightbox">
    <img :src="lightboxSrc" alt="">
    <button class="lightbox-close" @click.stop="closeLightbox">&times;</button>
  </div>
</Teleport>
</section>


  <section id="process">
    <div class="wrap">
      <div class="section-head">
        <div class="kicker">วิธีทำงาน</div>
        <h2>สี่ขั้นตอน ก่อนแบรนด์คุณจะถูกเห็น</h2>
      </div>
      <div class="process-list">
        <div class="process-item"><div class="process-num">ขั้นตอน</div><h3>รับฟัง &amp; วิเคราะห์</h3><p>เข้าใจธุรกิจ คู่แข่ง และพฤติกรรมกลุ่มเป้าหมายจริง</p></div>
        <div class="process-item"><div class="process-num">ขั้นตอน</div><h3>วางกลยุทธ์</h3><p>เลือกช่องทางและตัวชี้วัดที่ตอบโจทย์เป้าหมายธุรกิจ</p></div>
        <div class="process-item"><div class="process-num">ขั้นตอน</div><h3>ลงมือทำ</h3><p>ผลิตคอนเทนต์ พัฒนาเว็บ และปรับ SEO/AEO/GEO ควบคู่กัน</p></div>
        <div class="process-item"><div class="process-num">ขั้นตอน</div><h3>วัดผล &amp; ปรับ</h3><p>รายงานผลทุกเดือน ปรับแผนตามข้อมูลจริง ไม่ใช่ความรู้สึก</p></div>
      </div>
    </div>
  </section>

  <section id="contact">

  <div class="wrap">

    <div class="contact-glow-wrap">

      <div class="contact-glow"></div>

      <div class="contact-panel">

        

        <!-- ฝั่งซ้าย: หัวข้อ + ไอคอนช่องทางติดต่อ -->

        <div class="contact-left">
          <h2>พร้อมให้แบรนด์คุณถูกเห็นหรือยัง</h2>
          <div class="contact-socials">
            <!-- Facebook -->
            <a href="https://www.facebook.com/fame.pipat" target="_blank" rel="noopener noreferrer" aria-label="Facebook">
              <svg viewBox="0 0 24 24"><path d="M24 12.073c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.99 4.388 10.954 10.125 11.854v-8.385H7.078v-3.47h3.047V9.43c0-3.007 1.792-4.669 4.533-4.669 1.312 0 2.686.235 2.686.235v2.953H15.83c-1.491 0-1.956.925-1.956 1.874v2.25h3.328l-.532 3.47h-2.796v8.385C19.612 23.027 24 18.062 24 12.073z"/></svg>
            </a>
            <!-- Instagram -->
            <a href="https://www.instagram.com/famepipat/" target="_blank" rel="noopener noreferrer" aria-label="Instagram">
              <svg viewBox="0 0 24 24"><path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163c0-3.403-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z"/></svg>
            </a>
            <!-- Line OA -->
            <a href="https://line.me/ti/p/OY9fYjbmgS" target="_blank" rel="noopener noreferrer" aria-label="Line OA">
              <svg viewBox="0 0 24 24"><path d="M19.365 9.863c.349 0 .63.285.63.631 0 .345-.281.63-.63.63H17.61v1.125h1.755c.349 0 .63.283.63.63 0 .344-.281.629-.63.629h-2.386c-.345 0-.627-.285-.627-.629V8.108c0-.345.282-.63.627-.63h2.386c.346 0 .63.285.63.63 0 .349-.284.63-.63.63H17.61v1.125h1.755zm-3.855 3.016c0 .27-.174.51-.432.596-.064.021-.133.031-.199.031-.211 0-.391-.09-.51-.25l-2.443-3.317v2.94c0 .345-.283.63-.63.63-.349 0-.631-.285-.631-.63V8.108c0-.271.174-.51.433-.596.062-.022.132-.032.198-.032.211 0 .39.09.51.25l2.443 3.317V8.108c0-.345.283-.63.63-.63.349 0 .631.285.631.63v4.771zm-5.741 0c0 .345-.282.63-.627.63-.349 0-.63-.285-.63-.63V8.108c0-.345.281-.63.63-.63.345 0 .627.285.627.63v4.771zm-2.466.629H4.908c-.345 0-.63-.285-.63-.63V8.108c0-.345.285-.63.63-.63.349 0 .63.285.63.63v4.141h1.756c.345 0 .629.283.629.63 0 .344-.284.629-.629.629M24 10.311C24 4.613 18.622 0 12 0S0 4.613 0 10.311c0 5.05 4.593 9.273 10.78 10.021.421.076.991.235 1.135.541.13.278.085 1..042 1.396-.137 1.205-.623 4.473-.755 5.295-.084.526-.39 2.056 1.702 1.121 2.092-.935 11.272-6.64 15.378-11.398 1.171-1.378 1.718-2.775 1.718-4.078z"/></svg>
            </a>
            <!-- Phone / เบอร์โทร -->
            <div class="phone-toggle-container" :class="{ active: phoneOpen }">
  <a href="tel:094-842-3533" class="social-phone-btn" aria-label="Phone" @click.prevent="phoneOpen = !phoneOpen">
    <svg viewBox="0 0 24 24"><path d="M6.62 10.79c1.44 2.83 3.76 5.14 6.59 6.59l2.2-2.2c.27-.27.67-.36 1.02-.24 1.12.37 2.33.57 3.57.57.55 0 1 .45 1 1V20c0 .55-.45 1-1 1-9.39 0-17-7.61-17-17 0-.55.45-1 1-1h3.5c.55 0 1 .45 1 1 0 1.25.2 2.45.57 3.57.11.35.03.74-.25 1.02l-2.2 2.2z"/></svg>
  </a>
  <span class="phone-number">094-842-3533</span>
</div>
          </div>
        </div>
        <!-- ฝั่งขวา: ปุ่มกด -->
        <a href="https://line.me/ti/p/OY9fYjbmgS" class="bubble-btn">แอดไลน์คุยงาน</a>
      </div>
    </div>
  </div>
</section>
</main>

<footer class="wrap">
  <div class="brand" style="font-size:1rem">SEEN<span style="color:var(--accent-web)">.</span> Digital Studio</div>
  <div>© 2026 SEEN. Digital Studio — Facebook · IG · TikTok · LINE OA</div>
</footer>
</template>

<script setup>
const isScrolled = ref(false)

function onScroll() {
  isScrolled.value = window.scrollY > 8
}

onMounted(() => {
  window.addEventListener('scroll', onScroll)

  const script = document.createElement('script')
  script.src = 'https://www.tiktok.com/embed.js'
  script.async = true
  document.body.appendChild(script)
})

onUnmounted(() => window.removeEventListener('scroll', onScroll))
const lightboxSrc = ref(null)

function openLightbox(e){
  lightboxSrc.value = e.currentTarget.querySelector('img').src
}
function closeLightbox(){
  lightboxSrc.value = null
}
function togglePhone(event, element) {
  event.preventDefault(); // ป้องกันไม่ให้เปิดหน้าต่างหาแอป
  const container = element.closest('.phone-toggle-container');
  container.classList.toggle('active'); // กดคลิกเพื่อเปิด/ปิดเบอร์
}
const phoneOpen = ref(false)

const heroText = 'ตามยุคตลาดออนไลน์ให้ทันโลก'

const heroChars = computed(() => {
  if (typeof Intl !== 'undefined' && Intl.Segmenter) {
    const seg = new Intl.Segmenter('th', { granularity: 'grapheme' })
    return Array.from(seg.segment(heroText), s => s.segment)
  }
  return Array.from(heroText)
})
</script>
