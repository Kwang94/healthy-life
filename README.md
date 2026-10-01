<!DOCTYPE html>
<html lang="th">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Healthy Life</title>
    <meta
      name="description"
      content="Healthy Life เว็บไซต์ให้ความรู้และติดตามพฤติกรรมสุขภาพแบบง่ายและทันสมัย"
    />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Kanit:wght@300;400;500;600;700;800&display=swap"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <header class="header">
      <nav class="navbar container">
        <a href="#home" class="logo">Healthy Life</a>

        <button class="nav-toggle" aria-label="Open menu" aria-expanded="false">
          <span></span>
          <span></span>
          <span></span>
        </button>

        <div class="nav-menu">
          <a href="#home">Home</a>
          <a href="#tips">Health Tips</a>
          <a href="#nutrition">Nutrition</a>
          <a href="#exercise">Exercise</a>
          <a href="#bmi">BMI Calculator</a>
          <a href="#tracker">Health Tracker</a>
          <a href="#contact">Contact</a>
        </div>
      </nav>
    </header>

    <main>
      <section id="home" class="hero">
        <div class="container hero-content">
          <div class="hero-text reveal">
            <span class="eyebrow">Healthy Living</span>
            <h1>สุขภาพดี เริ่มต้นได้ที่ตัวเรา</h1>
            <p>
              เรียนรู้วิธีดูแลสุขภาพ พร้อมติดตามพฤติกรรมสุขภาพในแต่ละวัน
            </p>
            <div class="hero-actions">
              <a href="#tracker" class="btn btn-primary">เริ่มต้นดูแลสุขภาพ</a>
            </div>
          </div>

          <div class="hero-visual reveal">
            <div class="health-card main-card">
              <div class="mini-icon">💧</div>
              <div>
                <strong>น้ำ</strong>
                <p>6 / 8 แก้ว</p>
              </div>
            </div>

            <div class="health-card floating-card card-top">
              <div class="mini-icon">🏃</div>
              <div>
                <strong>ออกกำลังกาย</strong>
                <p>30 / 60 นาที</p>
              </div>
            </div>

            <div class="health-card floating-card card-bottom">
              <div class="mini-icon">😴</div>
              <div>
                <strong>นอน</strong>
                <p>7.5 / 8 ชั่วโมง</p>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section id="tips" class="section">
        <div class="container">
          <div class="section-heading reveal">
            <span class="eyebrow">Health Tips</span>
            <h2>เคล็ดลับการดูแลสุขภาพ</h2>
          </div>

          <div class="tips-grid">
            <article class="tip-card reveal">
              <div class="icon-box">💧</div>
              <h3>ดื่มน้ำให้เพียงพอ</h3>
              <p>
                ดื่มน้ำอย่างสม่ำเสมอวันละ 6–8 แก้ว ช่วยลดอาการเหนื่อยและส่งเสริมระบบไหลเวียน
              </p>
            </article>

            <article class="tip-card reveal">
              <div class="icon-box">😴</div>
              <h3>นอนหลับ 7-9 ชั่วโมง</h3>
              <p>
                การนอนที่เพียงพอช่วยปรับสมดุลฮอร์โมน เพิ่มความจำ และทำให้ร่างกายฟื้นฟูได้เต็มที่
              </p>
            </article>

            <article class="tip-card reveal">
              <div class="icon-box">🥗</div>
              <h3>รับประทานอาหารครบ 5 หมู่</h3>
              <p>
                เลือกอาหารที่หลากหลายและสมดุล เช่น ข้าว ผัก ผลไม้ โปรตีน และไขมันที่ดี
              </p>
            </article>

            <article class="tip-card reveal">
              <div class="icon-box">🏃</div>
              <h3>ออกกำลังกายอย่างสม่ำเสมอ</h3>
              <p>
                การออกกำลังกาย 30–60 นาทีต่อวันช่วยเพิ่มความแข็งแรงและลดความเสี่ยงโรคเรื้อรัง
              </p>
            </article>
          </div>
        </div>
      </section>

      <section id="nutrition" class="section alt-bg">
        <div class="container">
          <div class="section-heading reveal">
            <span class="eyebrow">Nutrition</span>
            <h2>อาหารเพื่อสุขภาพ</h2>
          </div>

          <div class="nutrition-grid">
            <article class="nutrition-card reveal">
              <div class="card-header">
                <h3>ผักและผลไม้</h3>
                <span>5–9 เสิร์ฟ</span>
              </div>
              <div class="progress">
                <div class="progress-bar" data-width="85%"></div>
              </div>
              <p>อุดมด้วยวิตามิน แร่ธาตุ และใยอาหารที่ดีต่อระบบย่อยอาหาร</p>
            </article>

            <article class="nutrition-card reveal">
              <div class="card-header">
                <h3>โปรตีน</h3>
                <span>2–3 มื้อ</span>
              </div>
              <div class="progress">
                <div class="progress-bar" data-width="78%"></div>
              </div>
              <p>ช่วยเสริมกล้ามเนื้อและช่วยให้ร่างกายทำงานได้อย่างมีประสิทธิภาพ</p>
            </article>

            <article class="nutrition-card reveal">
              <div class="card-header">
                <h3>ธัญพืช</h3>
                <span>6–8 เสิร์ฟ</span>
              </div>
              <div class="progress">
                <div class="progress-bar" data-width="72%"></div>
              </div>
              <p>ให้พลังงานและใยอาหารที่ช่วยทำให้ระบบทางเดินอาหารทำงานดีขึ้น</p>
            </article>

            <article class="nutrition-card reveal">
              <div class="card-header">
                <h3>ไขมันที่ดี</h3>
                <span>พอเหมาะ</span>
              </div>
              <div class="progress">
                <div class="progress-bar" data-width="68%"></div>
              </div>
              <p>ไขมันจากปลา เมล็ดพืช และ avocado ช่วยบำรุงสมองและหัวใจ</p>
            </article>

            <article class="nutrition-card reveal">
              <div class="card-header">
                <h3>ลดอาหารหวาน</h3>
                <span>จำกัด</span>
              </div>
              <div class="progress">
                <div class="progress-bar" data-width="60%"></div>
              </div>
              <p>ลดการบริโภคอาหารแปรรูปและหวานจัด ช่วยควบคุมน้ำหนักและสุขภาพ</p>
            </article>
          </div>
        </div>
      </section>

      <section id="exercise" class="section">
        <div class="container">
          <div class="section-heading reveal">
            <span class="eyebrow">Exercise</span>
            <h2>การออกกำลังกายที่เหมาะสำหรับทุกวัน</h2>
          </div>

          <div class="exercise-grid">
            <article class="exercise-card reveal">
              <div class="exercise-icon">🚶</div>
              <h3>เดิน</h3>
              <p><strong>ระดับความหนัก:</strong> ง่าย</p>
              <p><strong>ระยะเวลา:</strong> 20–30 นาที</p>
              <p><strong>ประโยชน์:</strong> ส่งเสริมการไหลเวียนโลหิตและลดความเครียด</p>
            </article>

            <article class="exercise-card reveal">
              <div class="exercise-icon">🏃</div>
              <h3>วิ่ง</h3>
              <p><strong>ระดับความหนัก:</strong> ปานกลาง</p>
              <p><strong>ระยะเวลา:</strong> 20–40 นาที</p>
              <p><strong>ประโยชน์:</strong> เพิ่มความทนทานและช่วยเผาผลาญแคลอรี่</p>
            </article>

            <article class="exercise-card reveal">
              <div class="exercise-icon">🚴</div>
              <h3>ปั่นจักรยาน</h3>
              <p><strong>ระดับความหนัก:</strong> ปานกลาง</p>
              <p><strong>ระยะเวลา:</strong> 25–45 นาที</p>
              <p><strong>ประโยชน์:</strong> เสริมกล้ามเนื้อขาและช่วยควบคุมน้ำหนัก</p>
            </article>

            <article class="exercise-card reveal">
              <div class="exercise-icon">🧘</div>
              <h3>โยคะ</h3>
              <p><strong>ระดับความหนัก:</strong> เบา–ปานกลาง</p>
              <p><strong>ระยะเวลา:</strong> 15–30 นาที</p>
              <p><strong>ประโยชน์:</strong> เพิ่มความยืดหยุ่นและลดความตึงเครียด</p>
            </article>
          </div>
        </div>
      </section>

      <section id="bmi" class="section alt-bg">
        <div class="container">
          <div class="section-heading reveal">
            <span class="eyebrow">BMI Calculator</span>
            <h2>ประเมินดัชนีมวลกาย</h2>
          </div>

          <div class="bmi-layout">
            <div class="bmi-form-card reveal">
              <form id="bmiForm">
                <div class="form-group">
                  <label for="weight">น้ำหนัก (กิโลกรัม)</label>
                  <input type="number" id="weight" min="1" step="0.1" placeholder="เช่น 60" required />
                </div>

                <div class="form-group">
                  <label for="height">ส่วนสูง (เซนติเมตร)</label>
                  <input type="number" id="height" min="1" step="0.1" placeholder="เช่น 170" required />
                </div>

                <button type="submit" class="btn btn-primary full-width">คำนวณ BMI</button>
              </form>
            </div>

            <div class="bmi-result-card reveal">
              <h3>ผลลัพธ์</h3>
              <div class="result-box">
                <p class="result-label">ค่า BMI</p>
                <p id="bmiValue" class="bmi-value">--</p>
                <p id="bmiStatus" class="bmi-status">กรุณากรอกข้อมูล</p>
                <p id="bmiAdvice" class="bmi-advice">
                  คำแนะนำเบื้องต้นจะปรากฏที่นี่
                </p>
              </div>
              <p class="note">
                ข้อมูลนี้เป็นการประเมินเบื้องต้น ไม่ใช่การวินิจฉัยทางการแพทย์
              </p>
            </div>
          </div>
        </div>
      </section>

      <section id="tracker" class="section">
        <div class="container">
          <div class="section-heading reveal">
            <span class="eyebrow">Health Tracker</span>
            <h2>Dashboard สำหรับติดตามสุขภาพประจำวัน</h2>
          </div>

          <div class="tracker-grid">
            <div class="tracker-card reveal">
              <div class="tracker-header">
                <h3>น้ำที่ดื่ม</h3>
                <span id="waterProgressText">0/8 แก้ว</span>
              </div>

              <div class="progress">
                <div id="waterBar" class="progress-bar tracking-bar water-bar" data-width="0%"></div>
              </div>

              <div class="tracker-actions">
                <button type="button" class="btn btn-primary" data-action="add-water">
                  + เพิ่มน้ำ 1 แก้ว
                </button>
              </div>
            </div>

            <div class="tracker-card reveal">
              <div class="tracker-header">
                <h3>การนอน</h3>
                <span id="sleepProgressText">0/8 ชั่วโมง</span>
              </div>

              <div class="progress">
                <div id="sleepBar" class="progress-bar tracking-bar sleep-bar" data-width="0%"></div>
              </div>

              <div class="tracker-actions">
                <input id="sleepInput" type="number" min="0" max="24" step="0.5" placeholder="ชั่วโมงนอน" />
                <button type="button" class="btn btn-primary" data-action="save-sleep">
                  บันทึกข้อมูล
                </button>
              </div>
            </div>

            <div class="tracker-card reveal">
              <div class="tracker-header">
                <h3>ออกกำลังกาย</h3>
                <span id="exerciseProgressText">0/60 นาที</span>
              </div>

              <div class="progress">
                <div id="exerciseBar" class="progress-bar tracking-bar exercise-bar" data-width="0%"></div>
              </div>

              <div class="tracker-actions">
                <button type="button" class="btn btn-primary" data-action="add-exercise">
                  + เพิ่มเวลาออกกำลังกาย
                </button>
              </div>
            </div>

            <div class="tracker-card reveal">
              <div class="tracker-header">
                <h3>ก้าวเดิน</h3>
                <span id="stepsProgressText">0/8000 ก้าว</span>
              </div>

              <div class="progress">
                <div id="stepsBar" class="progress-bar tracking-bar steps-bar" data-width="0%"></div>
              </div>

              <div class="tracker-actions">
                <input id="stepsInput" type="number" min="0" step="100" placeholder="จำนวนก้าว" />
                <button type="button" class="btn btn-primary" data-action="save-steps">
                  บันทึกข้อมูล
                </button>
              </div>
            </div>
          </div>

          <div id="goalMessage" class="goal-message reveal">
            วันนี้คุณยังไม่บรรลุเป้าหมาย
          </div>
        </div>
      </section>

      <section class="section alt-bg">
        <div class="container">
          <div class="section-heading reveal">
            <span class="eyebrow">Daily Health Score</span>
            <h2>คะแนนสุขภาพประจำวัน</h2>
          </div>

          <div class="score-layout reveal">
            <div class="score-ring">
              <div class="score-ring-inner">
                <span id="healthScoreValue">0</span>
                <small>/ 100</small>
              </div>
            </div>

            <div class="score-breakdown">
              <div class="score-item">
                <span>ดื่มน้ำครบเป้าหมาย</span>
                <strong id="waterScore">0</strong>
              </div>
              <div class="score-item">
                <span>นอนเพียงพอ</span>
                <strong id="sleepScore">0</strong>
              </div>
              <div class="score-item">
                <span>ออกกำลังกายครบเป้าหมาย</span>
                <strong id="exerciseScore">0</strong>
              </div>
              <div class="score-item">
                <span>เดินครบเป้าหมาย</span>
                <strong id="stepsScore">0</strong>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section id="dashboard" class="section">
        <div class="container">
          <div class="section-heading reveal">
            <span class="eyebrow">Health Dashboard</span>
            <h2>ข้อมูลสรุปสุขภาพ</h2>
          </div>

          <div class="dashboard-grid">
            <article class="dashboard-card reveal">
              <p>BMI</p>
              <h3 id="dashboardBmi">--</h3>
            </article>

            <article class="dashboard-card reveal">
              <p>น้ำที่ดื่ม</p>
              <h3 id="dashboardWater">0 แก้ว</h3>
            </article>

            <article class="dashboard-card reveal">
              <p>ชั่วโมงการนอน</p>
              <h3 id="dashboardSleep">0 ชั่วโมง</h3>
            </article>

            <article class="dashboard-card reveal">
              <p>เวลาออกกำลังกาย</p>
              <h3 id="dashboardExercise">0 นาที</h3>
            </article>

            <article class="dashboard-card reveal">
              <p>จำนวนก้าว</p>
              <h3 id="dashboardSteps">0 ก้าว</h3>
            </article>

            <article class="dashboard-card reveal">
              <p>คะแนนสุขภาพ</p>
              <h3 id="dashboardScore">0</h3>
            </article>
          </div>
        </div>
      </section>

      <section id="contact" class="section alt-bg">
        <div class="container">
          <div class="section-heading reveal">
            <span class="eyebrow">Contact</span>
            <h2>ส่งข้อความถึงเรา</h2>
          </div>

          <form id="contactForm" class="contact-form reveal">
            <div class="form-grid">
              <div class="form-group">
                <label for="name">ชื่อ</label>
                <input type="text" id="name" placeholder="กรอกชื่อของคุณ" />
              </div>

              <div class="form-group">
                <label for="email">Email</label>
                <input type="email" id="email" placeholder="example@email.com" />
              </div>
            </div>

            <div class="form-group">
              <label for="subject">หัวข้อ</label>
              <input type="text" id="subject" placeholder="หัวข้อที่ต้องการติดต่อ" />
            </div>

            <div class="form-group">
              <label for="message">ข้อความ</label>
              <textarea id="message" rows="5" placeholder="กรอกข้อความของคุณ"></textarea>
            </div>

            <button type="submit" class="btn btn-primary">ส่งข้อความ</button>
          </form>
        </div>
      </section>
    </main>

    <footer class="footer">
      <div class="container footer-content">
        <h3>Healthy Life</h3>
        <p>สุขภาพดี เริ่มต้นได้ทุกวัน</p>
      </div>
    </footer>

    <script src="script.js"></script>
  </body>
</html>

