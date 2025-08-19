# file-D-123-thietke.html

<!doctype html>
<html lang="vi">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Thiết Kế Website Theo Yêu Cầu — Giá HSSV 60k | Thường 100k | Cao 250k | VIP 500k</title>
  <meta name="description" content="Dịch vụ thiết kế web theo yêu cầu, tối ưu tốc độ và SEO. Bảng giá rõ ràng: HSSV 60k, Thường 100k, Cao 250k, VIP 500k." />
  <meta name="theme-color" content="#111827" />
  <style>
    :root{
      --bg:#0b1220;        /* nền tối sang */
      --card:#101a2b;      /* thẻ */
      --soft:#1a2740;      /* viền/overlay */
      --text:#eaf2ff;      /* chữ chính */
      --muted:#a7b3c7;     /* chữ phụ */
      --accent:#7c4dff;    /* tím */
      --accent2:#00e0a4;   /* xanh mint */
      --danger:#ff5c7a;    
      --ring: 0 0 0 3px rgba(124,77,255,.35);
    }
    *{box-sizing:border-box}
    html,body{margin:0}
    body{
      font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, "Apple Color Emoji","Segoe UI Emoji";
      background: radial-gradient(1200px 600px at 80% -10%, rgba(124,77,255,.2), transparent 50%),
                  radial-gradient(900px 500px at 0% 0%, rgba(0,224,164,.15), transparent 50%),
                  var(--bg);
      color:var(--text);
      line-height:1.6;
    }
    a{color:inherit;text-decoration:none}
    .container{max-width:1100px;margin:0 auto;padding:24px}
    .btn{
      display:inline-flex;align-items:center;gap:10px;
      background:linear-gradient(135deg, var(--accent), #9b72ff);
      color:#fff;padding:12px 18px;border-radius:14px;font-weight:700;border:1px solid rgba(255,255,255,.08);
      box-shadow:0 8px 24px rgba(124,77,255,.35), inset 0 -2px 0 rgba(255,255,255,.2);
      transition:.25s;cursor:pointer
    }
    .btn:hover{transform:translateY(-1px);filter:saturate(1.1)}
    .btn.outline{background:transparent;border:1px solid #32405e}
    .badge{display:inline-block;font-weight:700;font-size:12px;letter-spacing:.5px;text-transform:uppercase;border:1px solid #2a3754;padding:6px 10px;border-radius:999px;color:var(--muted)}
    header{position:sticky;top:0;backdrop-filter:saturate(140%) blur(8px);z-index:30;border-bottom:1px solid rgba(255,255,255,.06);background:rgba(11,18,32,.6)}
    .nav{display:flex;align-items:center;justify-content:space-between;gap:16px;padding:10px 0}
    .logo{display:flex;gap:10px;align-items:center;font-weight:900}
    .logo .dot{width:12px;height:12px;border-radius:50%;background:linear-gradient(135deg,var(--accent2),#4cf6ca);box-shadow:0 0 24px rgba(0,224,164,.8)}
    .nav a{color:var(--muted);font-weight:600}
    .nav a:hover{color:#fff}

    .hero{padding:64px 0 24px}
    .hero h1{font-size:clamp(28px,6vw,52px);line-height:1.1;margin:12px 0 14px}
    .hero p{color:var(--muted);font-size:18px;max-width:720px}
    .hero-cta{display:flex;gap:12px;flex-wrap:wrap;margin-top:18px}

    .stats{display:grid;grid-template-columns:repeat(4,1fr);gap:12px;margin-top:28px}
    .stat{background:rgba(255,255,255,.04);border:1px solid rgba(255,255,255,.06);border-radius:16px;padding:16px;text-align:center}
    .stat h3{margin:0;font-size:28px}
    .stat span{color:var(--muted);font-size:12px}

    .section{padding:26px 0}
    h2.section-title{font-size:clamp(22px,3.5vw,34px);margin:0 0 18px}
    .grid{display:grid;gap:16px}

    /* Tính năng */
    .features{grid-template-columns:repeat(3,minmax(0,1fr))}
    .feat{background:linear-gradient(180deg, rgba(255,255,255,.06), rgba(255,255,255,.02));border:1px solid rgba(255,255,255,.08);border-radius:18px;padding:18px}
    .feat h3{margin:8px 0 8px}
    .feat p{color:var(--muted);margin:0}

    /* Bảng giá */
    .pricing{grid-template-columns:repeat(4,minmax(0,1fr))}
    .plan{position:relative;display:flex;flex-direction:column;gap:12px;background:linear-gradient(180deg, rgba(16,26,43,.9), rgba(16,26,43,.6));border:1px solid #233250;border-radius:22px;padding:18px;min-height:420px}
    .plan.popular{outline:3px solid rgba(124,77,255,.35);box-shadow:0 12px 40px rgba(124,77,255,.25)}
    .plan .head{display:flex;align-items:center;justify-content:space-between}
    .plan .price{font-size:38px;font-weight:900}
    .plan .price small{font-size:14px;color:var(--muted);font-weight:600}
    .plan ul{list-style:none;padding:0;margin:0;display:flex;flex-direction:column;gap:10px}
    .plan li{display:flex;align-items:flex-start;gap:10px}
    .plan li svg{flex:0 0 20px;margin-top:2px}
    .plan .cta{margin-top:auto}

    /* Quy trình */
    .steps{grid-template-columns:repeat(4,minmax(0,1fr))}
    .step{background:rgba(255,255,255,.04);border:1px solid rgba(255,255,255,.07);border-radius:18px;padding:16px}
    .step .num{width:34px;height:34px;border-radius:12px;display:inline-grid;place-items:center;background:linear-gradient(135deg,var(--accent2),#65ffd4);font-weight:900;color:#06291f}

    /* Câu hỏi */
    details{background:rgba(255,255,255,.04);border:1px solid rgba(255,255,255,.08);border-radius:14px;padding:14px}
    summary{cursor:pointer;font-weight:700}
    details p{color:var(--muted)}

    /* Liên hệ */
    form{display:grid;gap:12px}
    input, textarea{background:#0d172a;border:1px solid #283754;border-radius:14px;color:#fff;padding:12px 14px;outline:none}
    input:focus, textarea:focus{box-shadow:var(--ring)}
    textarea{min-height:120px;resize:vertical}
    .contact-card{display:grid;grid-template-columns:1.2fr .8fr;gap:16px;background:linear-gradient(180deg, rgba(255,255,255,.06), rgba(255,255,255,.02));border:1px solid rgba(255,255,255,.08);border-radius:22px;padding:18px}

    footer{padding:28px 0;color:var(--muted);text-align:center}

    /* Responsive */
    @media (max-width: 960px){
      .features{grid-template-columns:1fr 1fr}
      .pricing{grid-template-columns:1fr 1fr}
      .steps{grid-template-columns:1fr 1fr}
      .stats{grid-template-columns:1fr 1fr}
      .contact-card{grid-template-columns:1fr}
    }
    @media (max-width: 560px){
      .features,.pricing,.steps{grid-template-columns:1fr}
    }
  </style>
</head>
<body>
  <header>
    <div class="container nav">
      <a class="logo" href="#top"><span class="dot"></span> <span>WebCraft</span></a>
      <nav style="display:flex;gap:14px">
        <a href="#dich-vu">Dịch vụ</a>
        <a href="#bang-gia">Bảng giá</a>
        <a href="#quy-trinh">Quy trình</a>
        <a href="#lien-he" class="btn" style="padding:8px 14px">Liên hệ</a>
      </nav>
    </div>
  </header>

  <main class="container">
    <!-- HERO -->
    <section class="hero" id="top">
      <span class="badge">Thiết kế theo yêu cầu</span>
      <h1>Thiết kế Website nhanh, đẹp, chuẩn SEO — giá <span style="background:linear-gradient(135deg,var(--accent2),#4cf6ca);-webkit-background-clip:text;background-clip:text;color:transparent">siêu mềm</span></h1>
      <p>Nhận thiết kế website theo ý tưởng của bạn: giới thiệu cá nhân, cửa hàng, landing page bán hàng, blog, portfolio… Tốc độ nhanh, giao diện hiện đại, tối ưu điện thoại và máy tính, dễ chỉnh sửa.</p>
      <div class="hero-cta">
        <a class="btn" href="#bang-gia">Xem bảng giá</a>
        <a class="btn outline" href="#mau">Xem mẫu giao diện</a>
      </div>
      <div class="stats">
        <div class="stat"><h3>24-72h</h3><span>Thời gian triển khai</span></div>
        <div class="stat"><h3>100%</h3><span>Tối ưu di động</span></div>
        <div class="stat"><h3>SEO cơ bản</h3><span>Meta, tốc độ, cấu trúc</span></div>
        <div class="stat"><h3>Hỗ trợ</h3><span>Chỉnh sửa nhỏ miễn phí</span></div>
      </div>
    </section>

    <!-- DỊCH VỤ -->
    <section class="section" id="dich-vu">
      <h2 class="section-title">Bạn nhận được gì?</h2>
      <div class="grid features">
        <div class="feat">
          <div class="badge">Giao diện hiện đại</div>
          <h3>Thiết kế đẹp, đúng brand</h3>
          <p>Chọn màu sắc, font, bố cục theo sở thích hoặc nhận tư vấn để có giao diện chuyên nghiệp phù hợp lĩnh vực.</p>
        </div>
        <div class="feat">
          <div class="badge">Tối ưu tốc độ</div>
          <h3>Load nhanh & thân thiện SEO</h3>
          <p>Tối ưu ảnh, cấu trúc HTML, thẻ meta, sơ đồ trang; điểm Core Web Vitals thân thiện người dùng.</p>
        </div>
        <div class="feat">
          <div class="badge">Dễ chỉnh sửa</div>
          <h3>Code gọn, tài liệu hướng dẫn</h3>
          <p>Bạn dễ thay ảnh, nội dung, giá; có file hướng dẫn cơ bản hoặc hỗ trợ qua chat.</p>
        </div>
      </div>
    </section>

    <!-- BẢNG GIÁ -->
    <section class="section" id="bang-gia">
      <h2 class="section-title">Bảng giá minh bạch</h2>
      <p style="color:var(--muted);margin-top:-6px">Giá theo gói, giao 1 trang cơ bản (có thể mở rộng). Giá VNĐ: hiển thị dạng rút gọn theo yêu cầu của bạn.</p>
      <div class="grid pricing">
        <!-- HSSV 60k -->
        <article class="plan">
          <div class="head">
            <div>
              <div class="badge">HSSV</div>
              <h3 style="margin:8px 0 0">Gói Học sinh / SV</h3>
            </div>
            <div class="price">60k <small>/ website</small></div>
          </div>
          <ul>
            <li>
              <svg width="20" height="20" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M20 6L9 17l-5-5" stroke="#00e0a4" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>
              Trang giới thiệu cơ bản 1-2 mục
            </li>
            <li>
              <svg width="20" height="20" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M20 6L9 17l-5-5" stroke="#00e0a4" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>
              Responsive di động
            </li>
            <li>
              <svg width="20" height="20" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M20 6L9 17l-5-5" stroke="#00e0a4" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>
              Tối ưu tốc độ & SEO cơ bản
            </li>
          </ul>
          <div class="cta">
            <a href="#lien-he" class="btn" aria-label="Đặt gói HSSV 60k">Đặt làm ngay</a>
          </div>
        </article>

        <!-- THƯỜNG 100k -->
        <article class="plan popular">
          <div class="head">
            <div>
              <div class="badge">Phổ biến</div>
              <h3 style="margin:8px 0 0">Gói Thường</h3>
            </div>
            <div class="price">100k <small>/ website</small></div>
          </div>
          <ul>
            <li>
              <svg width="20" height="20" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M20 6L9 17l-5-5" stroke="#00e0a4" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>
              Landing page 3-5 mục
            </li>
            <li>
              <svg width="20" height="20" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M20 6L9 17l-5-5" stroke="#00e0a4" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>
              Thêm form liên hệ
            </li>
            <li>
              <svg width="20" height="20" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M20 6L9 17l-5-5" stroke="#00e0a4" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>
              Tích hợp mạng xã hội
            </li>
          </ul>
          <div class="cta">
            <a href="#lien-he" class="btn" aria-label="Đặt gói Thường 100k">Đặt làm ngay</a>
          </div>
        </article>

        <!-- CAO 250k -->
        <article class="plan">
          <div class="head">
            <div>
              <div class="badge">Nổi bật</div>
              <h3 style="margin:8px 0 0">Gói Cao</h3>
            </div>
            <div class="price">250k <small>/ website</small></div>
          </div>
          <ul>
            <li>
              <svg width="20" height="20" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M20 6L9 17l-5-5" stroke="#00e0a4" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>
              Trang mở rộng: danh mục / gallery
            </li>
            <li>
              <svg width="20" height="20" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M20 6L9 17l-5-5" stroke="#00e0a4" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>
              Tùy chỉnh giao diện sâu
            </li>
            <li>
              <svg width="20" height="20" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M20 6L9 17l-5-5" stroke="#00e0a4" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>
              Hỗ trợ cài hosting cơ bản
            </li>
          </ul>
          <div class="cta">
            <a href="#lien-he" class="btn" aria-label="Đặt gói Cao 250k">Đặt làm ngay</a>
          </div>
        </article>

        <!-- VIP 500k -->
        <article class="plan">
          <div class="head">
            <div>
              <div class="badge" style="background:linear-gradient(135deg,#ffd166,#ff8c37);color:#3b2a00;border:none">VIP</div>
              <h3 style="margin:8px 0 0">Gói VIP</h3>
            </div>
            <div class="price">500k <small>/ website</small></div>
          </div>
          <ul>
            <li>
              <svg width="20" height="20" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M20 6L9 17l-5-5" stroke="#00e0a4" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>
              Thiết kế theo brief chi tiết, hiệu ứng nâng cao
            </li>
            <li>
              <svg width="20" height="20" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M20 6L9 17l-5-5" stroke="#00e0a4" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>
              Tối ưu SEO mở rộng + tư vấn nội dung
            </li>
            <li>
              <svg width="20" height="20" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M20 6L9 17l-5-5" stroke="#00e0a4" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>
              Bảo hành & chỉnh sửa 7 ngày
            </li>
          </ul>
          <div class="cta">
            <a href="#lien-he" class="btn" aria-label="Đặt gói VIP 500k">Đặt làm ngay</a>
          </div>
        </article>
      </div>
    </section>

    <!-- QUY TRÌNH -->
    <section class="section" id="quy-trinh">
      <h2 class="section-title">Quy trình làm việc</h2>
      <div class="grid steps">
        <div class="step"><span class="num">1</span>
          <h3>Trao đổi yêu cầu</h3>
          <p style="color:var(--muted);margin:6px 0 0">Gửi mô tả/ngành nghề, màu sắc, mẫu bạn thích, nội dung cơ bản.</p>
        </div>
        <div class="step"><span class="num">2</span>
          <h3>Thiết kế & demo</h3>
          <p style="color:var(--muted);margin:6px 0 0">Lên bố cục, font, màu; gửi bản xem trước để góp ý.</p>
        </div>
        <div class="step"><span class="num">3</span>
          <h3>Hoàn thiện & tối ưu</h3>
          <p style="color:var(--muted);margin:6px 0 0">Chốt giao diện, tối ưu tốc độ, SEO cơ bản.</p>
        </div>
        <div class="step"><span class="num">4</span>
          <h3>Bàn giao & hướng dẫn</h3>
          <p style="color:var(--muted);margin:6px 0 0">Giao file + hướng dẫn chỉnh sửa; hỗ trợ cài đặt cơ bản.</p>
        </div>
      </div>
    </section>

    <!-- MẪU (placeholder ảnh) -->
    <section class="section" id="mau">
      <h2 class="section-title">Mẫu giao diện (demo)</h2>
      <div class="grid" style="grid-template-columns:repeat(3,1fr);gap:14px">
        <div style="aspect-ratio:16/10;border-radius:16px;background:linear-gradient(135deg,#253656,#15233a);border:1px solid #2a3b5c;display:grid;place-items:center;color:#89a0c2">Mẫu #1</div>
        <div style="aspect-ratio:16/10;border-radius:16px;background:linear-gradient(135deg,#253656,#15233a);border:1px solid #2a3b5c;display:grid;place-items:center;color:#89a0c2">Mẫu #2</div>
        <div style="aspect-ratio:16/10;border-radius:16px;background:linear-gradient(135deg,#253656,#15233a);border:1px solid #2a3b5c;display:grid;place-items:center;color:#89a0c2">Mẫu #3</div>
      </div>
    </section>

    <!-- LIÊN HỆ -->
    <section class="section" id="lien-he">
      <h2 class="section-title">Liên hệ đặt làm</h2>
      <div class="contact-card">
        <form id="contactForm" onsubmit="return sendMessage(event)">
          <div style="display:grid;grid-template-columns:1fr 1fr;gap:12px">
            <div>
              <label for="name" style="display:block;font-weight:700;margin-bottom:6px">Tên</label>
              <input id="name" name="name" required placeholder="Ví dụ: Bảo" />
            </div>
            <div>
              <label for="package" style="display:block;font-weight:700;margin-bottom:6px">Chọn gói</label>
              <select id="package" name="package" style="width:100%;background:#0d172a;border:1px solid #283754;border-radius:14px;color:#fff;padding:12px 14px">
                <option>HSSV — 60k</option>
                <option>Thường — 100k</option>
                <option>Cao — 250k</option>
                <option>VIP — 500k</option>
              </select>
            </div>
          </div>
          <div>
            <label for="desc" style="display:block;font-weight:700;margin-bottom:6px">Mô tả yêu cầu</label>
            <textarea id="desc" name="desc" placeholder="Màu tím, có phần giới thiệu + bảng giá + liên hệ, tối ưu điện thoại…"></textarea>
          </div>
          <div style="display:flex;gap:10px;flex-wrap:wrap">
            <button class="btn" type="submit">Gửi yêu cầu qua chat</button>
            <a class="btn outline" href="https://zalo.me/" target="_blank" rel="noopener">Nhắn Zalo</a>
          </div>
          <p id="formMsg" style="color:var(--muted);margin:6px 0 0"></p>
        </form>
        <aside>
          <div style="display:grid;gap:8px">
            <div class="badge">Thông tin nhanh</div>
            <div style="background:#0c1627;border:1px solid #24324e;border-radius:12px;padding:12px">
              <strong>Thời gian:</strong> 24–72h (tùy độ phức tạp)<br/>
              <strong>Chỉnh sửa nhỏ:</strong> miễn phí trong 3–7 ngày<br/>
              <strong>File bàn giao:</strong> .html/.css/.js (hoặc theo yêu cầu)
            </div>
            <div style="background:#0c1627;border:1px solid #24324e;border-radius:12px;padding:12px">
              <strong>Thanh toán:</strong> cọc nhỏ, phần còn lại sau bàn giao<br/>
              <strong>Hóa đơn:</strong> có thể xuất bill đơn giản theo yêu cầu
            </div>
          </div>
        </aside>
      </div>
    </section>
  </main>

  <footer>
    <div class="container">
      © <span id="year"></span> WebCraft — Thiết kế web theo yêu cầu. All rights reserved.
    </div>
  </footer>

  <script>
    // năm footer
    document.getElementById('year').textContent = new Date().getFullYear();

    // demo gửi tin nhắn (mở sẵn app chat/Zalo/Telegram với nội dung)
    function sendMessage(e){
      e.preventDefault();
      const name = document.getElementById('name').value.trim();
      const pack = document.getElementById('package').value;
      const desc = document.getElementById('desc').value.trim();
      const msg = encodeURIComponent(`[ĐẶT LÀM WEB]\nTên: ${name}\nGói: ${pack}\nMô tả: ${desc}`);

      // === Chọn 1 kênh bạn dùng: Zalo, Messenger, Telegram, WhatsApp ===
      // Zalo (thay số của bạn vào ZALO_PHONE)
      const ZALO_PHONE = '0xxxxxxxxx'; // <- sửa số này
      const zaloUrl = `https://zalo.me/${ZALO_PHONE}?message=${msg}`;

      // Telegram (thay username bot hoặc user)
      const TELE_USER = 'your_username';
      const teleUrl = `https://t.me/${TELE_USER}?text=${msg}`;

      // WhatsApp (thay số theo định dạng quốc tế, ví dụ VN: 84xxxxxxxxx)
      const WA_PHONE = '84xxxxxxxxx';
      const waUrl = `https://wa.me/${WA_PHONE}?text=${msg}`;

      // Mặc định mở Zalo; bạn có thể đổi thành nền tảng bạn dùng
      window.open(zaloUrl, '_blank');

      // Thông báo nhỏ
      const hint = `Đã mở cửa sổ chat với nội dung sẵn. Nếu không thấy, kiểm tra popup bị chặn.\nBạn nhớ sửa số Zalo/Telegram/WhatsApp trong file nhé!`;
      document.getElementById('formMsg').textContent = hint;
      return false;
    }
  </script>
</body>
</html>
