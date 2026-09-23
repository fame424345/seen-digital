<template>
<header ref="headerEl" :class="{ scrolled: isScrolled }">
  <nav class="nav">
    <a href="#top" class="brand">SEEN<span>.</span></a>
    <div class="nav-links">
      <a href="#services">บริการ</a>
      <a href="#portfolio">ผลงาน</a>
      <a href="#process">วิธีทำงาน</a>
      <a href="#contact">ติดต่อ</a>
    </div>
    <a href="#contact" class="nav-cta">คุยงานกับเรา</a>
  </nav>
</header>

<main id="top">

  <section class="hero">
    <div class="wrap hero-grid">
      <div>
        <div class="eyebrow">Digital Marketing Studio</div>
        <h1>ถูกเห็น. ถูกค้นเจอ. ถูกเลือก.</h1>
        <p>เราคือทีมการตลาดดิจิทัลที่ดูแลแบรนด์คุณตั้งแต่ผลการค้นหาบน Google คำตอบจาก AI ไปจนถึงฟีดโซเชียลที่ลูกค้าเลื่อนผ่านทุกวัน ให้ทุกจุดที่คนเจอแบรนด์คุณ นำไปสู่การตัดสินใจซื้อ</p>
        <div class="cta-row">
          <a href="#contact" class="button-ui1">คุยงานกับเรา</a>
          <a href="#portfolio" class="btn-secondary">ดูผลงาน</a>
        </div>
      </div>
    </div>
  </section>

  <div class="services">
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
</div>

  <section id="portfolio">
    <div class="wrap">
      <div class="section-head">
        <div class="kicker">ผลงาน</div>
        <h2>ตัวอย่างงานที่เราภูมิใจ</h2>
      </div>
      <div class="folio-grid">
        <div class="folio-card">
          <span class="folio-tag" style="background:var(--accent-social)">Social · AEO</span>
          <h3>ร้านอาหารไทยฟิวชั่น "บ้านใบเตย"</h3>
          <p style="color:var(--text-dim); font-size:0.92rem">วางกลยุทธ์คอนเทนต์ IG Reels ควบคู่การปรับหน้าเว็บให้ติด Featured Snippet</p>
          <div class="folio-stat">3x<span>ผู้ติดตาม IG ใน 4 เดือน</span></div>
        </div>
        <div class="folio-card">
          <span class="folio-tag" style="background:var(--accent-search)">SEO · Website</span>
          <h3>คลินิกผิวหนัง GLOWDERM</h3>
          <p style="color:var(--text-dim); font-size:0.92rem">รื้อโครงสร้างเว็บใหม่ทั้งหมด พร้อมทำ SEO เจาะคีย์เวิร์ดเฉพาะทาง</p>
          <div class="folio-stat">12<span>คีย์เวิร์ดหลักติดหน้าแรกใน 3 เดือน</span></div>
        </div>
        <div class="folio-card">
          <span class="folio-tag" style="background:var(--accent-ai)">AI Marketing · LINE OA</span>
          <h3>แบรนด์เครื่องหอม AROMICA</h3>
          <p style="color:var(--text-dim); font-size:0.92rem">วางระบบแชทบอทตอบคำถามและแนะนำสินค้าอัตโนมัติผ่าน LINE OA</p>
          <div class="folio-stat">+40%<span>อัตราปิดการขายผ่านแชท</span></div>
        </div>
        <div class="folio-card">
          <span class="folio-tag" style="background:var(--accent-web)">GEO · TikTok</span>
          <h3>ที่พักบูทีค TIDELINE RESORT</h3>
          <p style="color:var(--text-dim); font-size:0.92rem">ทำคอนเทนต์ TikTok ควบคู่ปรับเว็บให้ AI แนะนำเมื่อคนถามหาที่พัก</p>
          <div class="folio-stat">+65%<span>ยอดจองผ่านเว็บไซต์</span></div>
        </div>
      </div>
    </div>
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
      <div class="contact-panel">
        <h2>พร้อมให้แบรนด์คุณถูกเห็นหรือยัง</h2>
        <div class="contact-links">
          <a href="#">LINE OA: @seen.digital</a>
          <a href="#">hello@seendigital.co</a>
          <a href="#">02-xxx-xxxx</a>
        </div>
        <a href="#" class="btn-primary">แอดไลน์คุยงาน</a>
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

onMounted(() => window.addEventListener('scroll', onScroll))
onUnmounted(() => window.removeEventListener('scroll', onScroll))
</script>
