[입대공략.html](https://github.com/user-attachments/files/28193521/default.html)
<!DOCTYPE html>
<!-- saved from url=(0084)file:///C:/Users/20060/Downloads/%EC%9E%85%EB%8C%80%EA%B3%B5%EB%9E%B5_v3_1.html#home -->
<html lang="ko"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
  
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>입대공략 | 입대 정보 · 체력훈련 · 정책 변화</title>
  <style>
    :root {
      --bg: #f6f8fb;
      --card: #ffffff;
      --text: #111827;
      --muted: #6b7280;
      --subtle: #94a3b8;
      --line: #e5e7eb;
      --blue: #3182f6;
      --blue-dark: #2563eb;
      --blue-light: #eff6ff;
      --green: #10b981;
      --violet: #8b5cf6;
      --orange: #f97316;
      --red: #ef4444;
      --radius: 24px;
      --radius-sm: 16px;
      --shadow: 0 20px 50px rgba(15,23,42,0.08);
      --shadow-sm: 0 8px 24px rgba(15,23,42,0.06);
      --max: 1160px;
    }
    * { box-sizing: border-box; }
    html { scroll-behavior: smooth; }
    body {
      margin: 0;
      font-family: -apple-system, BlinkMacSystemFont, "Pretendard", "Apple SD Gothic Neo", "Noto Sans KR", sans-serif;
      background: var(--bg);
      color: var(--text);
      word-break: keep-all;
    }
    a { color: inherit; text-decoration: none; }
    button, input, select { font: inherit; cursor: pointer; }

    /* ── 네비게이션 ── */
    .topbar {
      position: sticky; top: 0; z-index: 50;
      background: rgba(255,255,255,0.9);
      backdrop-filter: blur(20px);
      border-bottom: 1px solid rgba(229,231,235,0.8);
    }
    .nav-inner {
      max-width: var(--max); margin: 0 auto;
      padding: 12px clamp(18px,4vw,28px);
      display: flex; align-items: center; justify-content: space-between; gap: 16px;
    }
    .brand { display: flex; align-items: center; gap: 10px; }
    .brand-mark {
      width: 38px; height: 38px; border-radius: 12px;
      background: var(--text); color: white;
      display: grid; place-items: center; flex: 0 0 auto;
    }
    .brand-title { margin: 0; font-size: 17px; font-weight: 900; letter-spacing: -0.04em; }
    .brand-sub { margin: 1px 0 0; color: var(--muted); font-size: 11px; font-weight: 700; }
    .desktop-nav { display: flex; align-items: center; gap: 4px; }
    .nav-btn {
      border: 0; background: transparent; color: var(--muted);
      padding: 9px 13px; border-radius: 999px;
      font-size: 13.5px; font-weight: 800; transition: .15s;
    }
    .nav-btn:hover { background: #eef2f7; color: var(--text); }
    .nav-btn.active { background: var(--text); color: white; }
    .mobile-menu-button {
      display: none; border: 0; background: #eef2f7;
      border-radius: 12px; width: 40px; height: 40px;
      color: var(--text); align-items: center; justify-content: center;
    }
    .mobile-nav {
      display: none; max-width: var(--max); margin: 0 auto;
      padding: 0 18px 14px; grid-template-columns: 1fr; gap: 6px;
    }
    .mobile-nav.open { display: grid; }

    /* ── 중앙 슬라이드 배너 ── */
    .banner-section {
      max-width: var(--max); margin: 0 auto;
      padding: clamp(20px,4vw,36px) clamp(18px,4vw,28px) 0;
    }
    .banner-slider {
      position: relative; overflow: hidden;
      border-radius: var(--radius); height: 160px;
      cursor: pointer;
    }
    .banner-track {
      display: flex; height: 100%;
      transition: transform .55s cubic-bezier(.4,0,.2,1);
    }
    .banner-slide {
      min-width: 100%; height: 100%;
      display: flex; align-items: center; justify-content: space-between;
      padding: clamp(22px,4vw,40px) clamp(24px,5vw,52px);
      position: relative; overflow: hidden;
      flex-shrink: 0;
    }
    .banner-slide::after {
      content: ""; position: absolute; right: -60px; top: -60px;
      width: 260px; height: 260px; border-radius: 999px;
      background: rgba(255,255,255,.07); pointer-events: none;
    }
    .banner-slide.blue { background: linear-gradient(130deg,#1d4ed8,#3b82f6); }
    .banner-slide.dark { background: linear-gradient(130deg,#0f172a,#1e3a5c); }
    .banner-slide.green { background: linear-gradient(130deg,#065f46,#10b981); }
    .banner-slide.violet { background: linear-gradient(130deg,#4c1d95,#8b5cf6); }
    .banner-content { position: relative; z-index: 1; }
    .banner-tag {
      display: inline-flex; align-items: center; gap: 6px;
      background: rgba(255,255,255,.15); color: rgba(255,255,255,.9);
      font-size: 11px; font-weight: 900; padding: 4px 10px; border-radius: 999px;
      margin-bottom: 10px; letter-spacing: .04em;
    }
    .banner-title {
      margin: 0; font-size: clamp(18px,2.5vw,24px);
      font-weight: 950; color: white; letter-spacing: -.04em; line-height: 1.2;
    }
    .banner-desc {
      margin: 6px 0 0; color: rgba(255,255,255,.75);
      font-size: 13px; font-weight: 700; line-height: 1.5;
    }
    .banner-emoji {
      font-size: clamp(40px,7vw,64px); position: relative; z-index: 1;
      flex-shrink: 0; margin-left: 16px; opacity: .9;
    }
    .banner-nav {
      display: flex; align-items: center; justify-content: center;
      gap: 8px; margin-top: 14px;
    }
    .banner-dot {
      width: 8px; height: 8px; border-radius: 999px;
      background: #cbd5e1; border: 0; padding: 0; transition: .25s;
      cursor: pointer;
    }
    .banner-dot.active { width: 24px; background: var(--blue); }
    .banner-arrow {
      position: absolute; top: 50%; transform: translateY(-50%);
      width: 36px; height: 36px; border-radius: 999px;
      background: rgba(255,255,255,.18); color: white; border: 0;
      display: flex; align-items: center; justify-content: center;
      z-index: 5; transition: .18s; backdrop-filter: blur(8px);
    }
    .banner-arrow:hover { background: rgba(255,255,255,.3); }
    .banner-arrow.prev { left: 14px; }
    .banner-arrow.next { right: 14px; }

    /* ── 레이아웃 ── */
    .container { max-width: var(--max); margin: 0 auto; padding: clamp(24px,5vw,48px) clamp(18px,4vw,28px); }
    .page { display: none; animation: fadeUp .22s ease both; }
    .page.active { display: block; }
    @keyframes fadeUp { from { opacity:0; transform: translateY(8px); } to { opacity:1; transform:none; } }

    /* ── 홈 히어로 ── */
    .hero-grid {
      display: grid;
      grid-template-columns: minmax(0, 1.25fr) minmax(280px, .75fr);
      gap: clamp(14px,2.5vw,22px);
    }
    .hero-card {
      min-height: 420px; position: relative; overflow: hidden;
      background: linear-gradient(140deg, #0f172a 0%, #1e293b 60%, #1a3a5c 100%);
      color: white; border-radius: var(--radius);
      padding: clamp(30px,6vw,56px); box-shadow: var(--shadow);
    }
    .hero-card::after {
      content: ""; position: absolute; right: -100px; bottom: -120px;
      width: clamp(280px,35vw,440px); height: clamp(280px,35vw,440px);
      border-radius: 999px;
      background: radial-gradient(circle, rgba(49,130,246,.3), transparent 65%);
      pointer-events: none;
    }
    .eyebrow-pill {
      position: relative; z-index: 1;
      display: inline-flex; align-items: center; gap: 8px;
      color: #93c5fd; font-size: 13px; font-weight: 800; margin-bottom: 32px;
      background: rgba(255,255,255,.07); padding: 7px 14px; border-radius: 999px;
    }
    .hero-title {
      position: relative; z-index: 1; margin: 0;
      font-size: clamp(38px,7.5vw,68px); line-height: .97;
      letter-spacing: -.075em; font-weight: 950;
    }
    .hero-title em { font-style: normal; color: #60a5fa; }
    .hero-desc {
      position: relative; z-index: 1;
      max-width: 580px; margin: 22px 0 0;
      color: #cbd5e1; font-size: clamp(15px,2vw,18px);
      line-height: 1.75; font-weight: 600;
    }
    .soft-note {
      position: relative; z-index: 1; margin-top: 18px;
      display: inline-flex; align-items: center; gap: 8px;
      padding: 10px 14px; border-radius: 999px;
      background: rgba(255,255,255,.08); color: #dbeafe;
      font-size: 13px; font-weight: 800;
    }
    .hero-actions { position: relative; z-index: 1; margin-top: 28px; display: flex; flex-wrap: wrap; gap: 10px; }

    /* ── 버튼 ── */
    .btn {
      border: 0; border-radius: 14px; padding: 14px 18px;
      display: inline-flex; align-items: center; justify-content: center; gap: 8px;
      font-size: 14px; font-weight: 900; transition: .18s ease; white-space: nowrap;
    }
    .btn:hover { transform: translateY(-2px); }
    .btn:active { transform: translateY(0); }
    .btn.primary { background: white; color: var(--text); box-shadow: 0 10px 26px rgba(0,0,0,.14); }
    .btn.blue { background: var(--blue); color: white; box-shadow: 0 12px 28px rgba(49,130,246,.26); }
    .btn.dark { background: var(--text); color: white; }
    .btn.ghost { background: rgba(255,255,255,.1); color: white; border: 1px solid rgba(255,255,255,.18); }
    .btn.light { background: #eef2f7; color: #334155; }
    .btn.light:hover { background: #e2e8f0; }

    /* ── 카드 기본 ── */
    .status-panel, .card, .white-box, .routine-card, .meter-card {
      background: var(--card);
      border: 1px solid rgba(229,231,235,.9);
      border-radius: var(--radius);
      box-shadow: var(--shadow-sm);
    }
    .status-panel { padding: clamp(22px,4vw,30px); display: flex; flex-direction: column; gap: 16px; }
    .icon-box {
      width: 52px; height: 52px; border-radius: 18px;
      display: grid; place-items: center;
      color: white; background: var(--blue); flex: 0 0 auto;
    }
    .icon-box.green { background: var(--green); }
    .icon-box.violet { background: var(--violet); }
    .icon-box.orange { background: var(--orange); }
    .icon-box.red { background: var(--red); }
    .label { margin: 0; color: var(--subtle); font-size: 12px; font-weight: 900; letter-spacing: .03em; }
    .panel-title, .card-title { margin: 0; font-weight: 950; letter-spacing: -.045em; }
    .panel-title { font-size: clamp(22px,3vw,30px); }
    .card-title { font-size: clamp(18px,2.5vw,24px); }
    .card-desc, .section-desc { color: var(--muted); line-height: 1.65; font-size: 14px; font-weight: 650; }
    .section-desc { font-size: 14.5px; margin: 6px 0 0; }

    .mini-list { display: grid; gap: 8px; margin-top: 6px; }
    .mini-item {
      display: flex; gap: 10px; align-items: flex-start;
      background: #f8fafc; border-radius: 14px; padding: 12px;
      color: #334155; font-size: 14px; font-weight: 800;
    }

    /* ── 섹션 헤드 ── */
    .section-head {
      display: flex; align-items: flex-end; justify-content: space-between; gap: 20px;
      margin: clamp(28px,5vw,48px) 0 16px;
    }
    .eyebrow { margin: 0 0 5px; color: var(--blue); font-size: 12px; font-weight: 900; letter-spacing: .04em; text-transform: uppercase; }
    .section-title {
      margin: 0; font-size: clamp(24px,3.5vw,38px);
      letter-spacing: -.06em; font-weight: 950;
    }

    /* ── 그리드 ── */
    .responsive-grid {
      display: grid; gap: clamp(10px,2vw,16px);
      grid-template-columns: repeat(auto-fit, minmax(min(100%,250px), 1fr));
    }
    .card {
      position: relative; overflow: hidden; min-height: 210px;
      padding: clamp(18px,3vw,26px); transition: .2s ease;
      text-align: left; width: 100%; color: inherit;
      display: flex; flex-direction: column; justify-content: space-between;
    }
    .card:hover { transform: translateY(-4px); box-shadow: var(--shadow); border-color: #d1d5db; }
    .card-link {
      display: inline-flex; align-items: center; gap: 4px;
      color: var(--blue); font-size: 13.5px; font-weight: 900;
      background: transparent; border: 0; padding: 0; margin-top: 16px;
    }

    /* ── 무드 스트립 ── */
    .mood-strip {
      margin-top: clamp(14px,3vw,24px);
      display: grid; grid-template-columns: repeat(auto-fit, minmax(min(100%,200px), 1fr)); gap: 10px;
    }
    .mood-chip {
      display: flex; align-items: center; gap: 10px; padding: 13px 15px;
      border-radius: 18px; background: white; border: 1px solid var(--line);
      box-shadow: 0 4px 14px rgba(15,23,42,.04);
      color: #334155; font-size: 13.5px; font-weight: 850;
    }
    .dot { width: 10px; height: 10px; border-radius: 50%; background: var(--blue); flex: 0 0 auto; }
    .dot.green { background: var(--green); }
    .dot.orange { background: var(--orange); }
    .dot.violet { background: var(--violet); }

    /* ── 체크리스트 / 대시보드 ── */
    .two-col { display: grid; grid-template-columns: minmax(260px,.82fr) minmax(0,1.18fr); gap: clamp(14px,3vw,22px); align-items: start; }
    .white-box { padding: clamp(20px,4vw,28px); }
    .checklist { display: grid; gap: 8px; margin-top: 16px; }
    .check-item {
      display: flex; align-items: center; gap: 10px; background: #f8fafc;
      border-radius: 14px; padding: 12px 14px; color: #334155; font-size: 14px; font-weight: 800;
      transition: background .15s;
    }
    .check-item:hover { background: #f1f5f9; }
    .check-item input { width: 18px; height: 18px; accent-color: var(--blue); flex: 0 0 auto; }
    .progress-wrap { margin-top: 16px; background: #eef2f7; border-radius: 999px; height: 10px; overflow: hidden; }
    .progress-bar { height: 100%; width: 0%; background: var(--blue); border-radius: 999px; transition: width .3s ease; }
    .progress-text { font-size: 13px; color: var(--muted); font-weight: 750; margin-top: 8px; }

    /* ── 업데이트 / 검색 ── */
    .search-box {
      display: flex; align-items: center; gap: 8px; background: #f1f5f9;
      border-radius: 14px; padding: 11px 14px; color: #94a3b8; min-width: min(100%,240px);
    }
    .search-box input { border: 0; background: transparent; outline: none; width: 100%; font-weight: 800; color: var(--text); font-size: 14px; }
    .update-list { display: grid; gap: 10px; }
    .update-card {
      background: #f8fafc; border: 1px solid #edf2f7;
      border-radius: 18px; padding: 16px; transition: .15s;
    }
    .update-card:hover { background: #f1f5f9; }
    .update-top { display: flex; justify-content: space-between; gap: 12px; align-items: center; margin-bottom: 8px; }
    .badge {
      display: inline-flex; padding: 5px 10px; border-radius: 999px;
      background: white; color: var(--blue); font-size: 12px; font-weight: 950;
      border: 1px solid #dbeafe;
    }
    .badge.green { color: var(--green); border-color: #a7f3d0; }
    .badge.orange { color: var(--orange); border-color: #fed7aa; }
    .badge.violet { color: var(--violet); border-color: #ddd6fe; }
    .date { color: #94a3b8; font-size: 12px; font-weight: 800; }
    .update-title { margin: 0; font-size: 16px; font-weight: 950; letter-spacing: -.02em; }
    .update-desc { margin: 6px 0 0; color: var(--muted); line-height: 1.6; font-size: 13.5px; font-weight: 650; }

    /* ── 상세 히어로 ── */
    .detail-hero {
      background: linear-gradient(140deg,#0f172a,#1e293b);
      color: #fff; border-radius: var(--radius); padding: clamp(28px,5vw,52px);
      box-shadow: var(--shadow); position: relative; overflow: hidden;
    }
    .detail-hero::after {
      content:""; position:absolute; right:-80px; bottom:-100px;
      width:300px; height:300px; border-radius:999px;
      background:radial-gradient(circle, rgba(49,130,246,.25), transparent 65%);
      pointer-events:none;
    }
    .detail-hero.light { background: white; color: var(--text); border: 1px solid var(--line); box-shadow: var(--shadow-sm); }
    .detail-hero.light::after { display: none; }
    .breadcrumb {
      display: flex; flex-wrap: wrap; gap: 6px; align-items: center;
      font-size: 13px; color: rgba(255,255,255,.5); font-weight: 800; margin-bottom: 20px;
    }
    .detail-hero.light .breadcrumb { color: var(--subtle); }
    .breadcrumb button {
      border: 0; background: transparent; color: inherit; font-weight: 900; padding: 0;
      transition: color .15s;
    }
    .breadcrumb button:hover { color: white; }
    .detail-hero.light .breadcrumb button:hover { color: var(--text); }
    .detail-title { margin: 0; font-size: clamp(32px,5.5vw,58px); line-height: 1.04; letter-spacing: -.07em; font-weight: 950; position: relative; z-index: 1; }
    .detail-desc { margin: 16px 0 0; max-width: 700px; color: #cbd5e1; line-height: 1.75; font-weight: 650; position: relative; z-index: 1; }
    .detail-hero.light .detail-desc { color: var(--muted); }

    /* ── 탭 ── */
    .tabs { display: flex; gap: 6px; flex-wrap: wrap; margin: 20px 0; }
    .tab {
      border: 0; border-radius: 999px; background: white; color: #64748b;
      padding: 11px 16px; font-size: 13.5px; font-weight: 950;
      box-shadow: 0 4px 14px rgba(15,23,42,.07); transition: .15s;
    }
    .tab:hover { background: #f1f5f9; }
    .tab.active { background: var(--text); color: white; }

    /* ── 트레이닝 ── */
    .branch-panel { display: none; }
    .branch-panel.active { display: block; animation: fadeUp .2s ease both; }
    .training-layout { display: grid; grid-template-columns: minmax(0,.9fr) minmax(0,1.1fr); gap: clamp(14px,3vw,22px); align-items: start; }
    .routine-grid { display: grid; gap: 10px; grid-template-columns: repeat(auto-fit, minmax(min(100%,210px), 1fr)); }
    .routine-card, .meter-card { padding: 16px; }
    .routine-day {
      display: inline-flex; padding: 5px 10px; border-radius: 999px;
      background: var(--blue-light); color: var(--blue); font-size: 12px; font-weight: 950; margin-bottom: 10px;
    }
    .routine-card h4 { margin: 0; font-size: 16px; letter-spacing: -.03em; font-weight: 950; }
    .routine-card p { color: var(--muted); margin: 6px 0 0; line-height: 1.55; font-size: 13px; font-weight: 650; }
    .meter-title { display: flex; justify-content: space-between; gap: 12px; align-items: center; margin-bottom: 7px; font-size: 13.5px; font-weight: 950; }
    .meter { height: 10px; border-radius: 999px; background: #f1f5f9; overflow: hidden; margin-bottom: 13px; }
    .meter span { display: block; height: 100%; width: var(--w); background: var(--blue); border-radius: 999px; transition: width .6s ease; }
    .source-note {
      background: white; border: 1px solid var(--line); border-radius: 18px;
      padding: 16px 18px; color: var(--muted); line-height: 1.65; font-size: 13px; font-weight: 650; margin-top: 16px;
    }
    .source-note strong { color: var(--text); }

    /* ── AI 트레이닝 플랜 ── */
    .ai-plan-box {
      background: var(--blue-light); border: 1px solid #bfdbfe;
      border-radius: var(--radius); padding: clamp(20px,4vw,28px); margin-top: 20px;
    }
    .ai-plan-box h3 { font-size: 18px; font-weight: 950; color: #1d4ed8; margin: 0 0 4px; }
    .ai-plan-sub { font-size: 13px; color: #3b82f6; font-weight: 750; margin-bottom: 18px; }
    .exercise-item {
      background: white; border-radius: 14px; padding: 14px 16px;
      margin-bottom: 8px; display: flex; align-items: center; justify-content: space-between;
      box-shadow: 0 2px 8px rgba(15,23,42,.05);
    }
    .ex-left h4 { font-size: 14px; font-weight: 800; margin: 0 0 2px; }
    .ex-left p { font-size: 12px; color: var(--muted); margin: 0; }
    .ex-right { text-align: right; }
    .ex-target { font-size: 22px; font-weight: 950; color: var(--blue); }
    .ex-label { font-size: 11px; color: var(--subtle); }
    .record-input {
      width: 62px; padding: 6px 8px; border: 1px solid #e5e7eb;
      border-radius: 8px; font-size: 13px; text-align: center;
      background: #f8fafc; margin-top: 4px; color: var(--text);
    }
    .record-input:focus { outline: none; border-color: var(--blue); }
    .ai-form { display: grid; grid-template-columns: 1fr 1fr; gap: 12px; margin-bottom: 16px; }
    .ai-form-group { display: flex; flex-direction: column; gap: 6px; }
    .ai-form-group label { font-size: 13px; font-weight: 800; color: #334155; }
    .ai-form-group input, .ai-form-group select {
      padding: 11px 13px; border: 1px solid var(--line); border-radius: 12px;
      font-size: 14px; background: #f8fafc; color: var(--text); transition: .15s;
    }
    .ai-form-group input:focus, .ai-form-group select:focus { outline: none; border-color: var(--blue); background: white; }

    /* ── 공식 링크 ── */
    .official-grid { display: grid; gap: 12px; grid-template-columns: repeat(auto-fit, minmax(min(100%,230px), 1fr)); }

    /* ── 플로팅 백 ── */
    .floating-back {
      position: fixed; right: clamp(16px,4vw,28px); bottom: clamp(16px,4vw,28px);
      z-index: 40; border: 0; border-radius: 999px; padding: 13px 18px;
      background: var(--text); color: #fff; font-size: 13px; font-weight: 950;
      box-shadow: 0 16px 38px rgba(15,23,42,.22);
      display: none; align-items: center; gap: 6px; transition: .15s;
    }
    .floating-back.show { display: inline-flex; }
    .floating-back:hover { transform: translateY(-2px); }
    .empty { border: 1px dashed #cbd5e1; border-radius: 18px; padding: 24px; text-align: center; color: #64748b; font-weight: 850; background: #f8fafc; }

    /* ── 다크모드 ── */
    .body-dark {
      --bg: #0b1120; --card: #111827; --text: #e5e7eb; --muted: #94a3b8;
      --line: #1f2937; --blue-light: #1e3a5f;
      background: #0b1120;
    }
    .body-dark .topbar { background: rgba(15,23,42,.92); border-bottom-color: rgba(51,65,85,.7); }
    .body-dark .status-panel, .body-dark .card, .body-dark .white-box,
    .body-dark .routine-card, .body-dark .meter-card, .body-dark .source-note,
    .body-dark .detail-hero.light, .body-dark .mood-chip, .body-dark .update-card {
      background: #111827; border-color: #1f2937; color: #e5e7eb;
    }
    .body-dark .mini-item, .body-dark .check-item, .body-dark .stat-card,
    .body-dark .ai-form-group input, .body-dark .ai-form-group select,
    .body-dark .btn.light, .body-dark .search-box, .body-dark .exercise-item {
      background: #0f172a; border-color: #1f2937; color: #e5e7eb;
    }
    .body-dark .tab { background: #111827; color: #94a3b8; }
    .body-dark .tab.active { background: #e5e7eb; color: #111827; }
    .body-dark .badge { background: #1f2937; border-color: #1f2937; }
    .body-dark .ai-plan-box { background: #0f1f38; border-color: #1e3a5f; }
    .body-dark .progress-wrap, .body-dark .meter { background: #1f2937; }

    /* ── 토글 ── */
    .toggle { width: 52px; height: 30px; border-radius: 999px; border: 0; background: #cbd5e1; padding: 3px; transition: .18s; flex: 0 0 auto; }
    .toggle span { display: block; width: 24px; height: 24px; border-radius: 999px; background: #fff; transition: .18s; box-shadow: 0 3px 8px rgba(15,23,42,.2); }
    .toggle.on { background: var(--blue); }
    .toggle.on span { transform: translateX(22px); }
    .settings-row { display: flex; align-items: center; justify-content: space-between; gap: 18px; padding: 16px 0; border-bottom: 1px solid var(--line); }
    .settings-row:last-of-type { border-bottom: 0; }

    /* ── 프로필 ── */
    .stat-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(min(100%,160px), 1fr)); gap: 10px; margin-top: 20px; }
    .stat-card { background: #f8fafc; border-radius: 18px; padding: 16px; border: 1px solid #edf2f7; }
    .stat-number { font-size: 26px; font-weight: 950; letter-spacing: -.05em; margin: 0; }
    .stat-label { margin: 4px 0 0; color: var(--muted); font-size: 12.5px; font-weight: 850; }
    .avatar { width: clamp(68px,10vw,96px); height: clamp(68px,10vw,96px); border-radius: 28px; display: grid; place-items: center; background: var(--blue); color: #fff; font-size: clamp(26px,4vw,38px); font-weight: 950; }
    .profile-head { display: flex; align-items: center; gap: 18px; flex-wrap: wrap; }
    .form-group { display: grid; gap: 7px; margin-top: 14px; }
    .form-label { font-size: 13px; font-weight: 900; color: #334155; }
    .form-input, .form-select { width: 100%; border: 1px solid var(--line); background: #f8fafc; border-radius: 14px; padding: 13px 15px; outline: none; color: var(--text); font-weight: 800; transition: .15s; }
    .form-input:focus, .form-select:focus { border-color: var(--blue); background: white; box-shadow: 0 0 0 4px rgba(49,130,246,.1); }

    /* ── 반응형 ── */
    @media (max-width: 860px) {
      .desktop-nav { display: none; }
      .mobile-menu-button { display: inline-flex; }
      .hero-grid, .two-col, .training-layout { grid-template-columns: 1fr; }
      .hero-card { min-height: auto; }
      .section-head { align-items: flex-start; flex-direction: column; }
      .search-box { width: 100%; }
      .ai-form { grid-template-columns: 1fr; }
    }
    @media (max-width: 520px) {
      .hero-actions { flex-direction: column; }
      .btn { width: 100%; }
      .brand-sub { display: none; }
    }

    /* ── 컴팩트 ── */
    .body-compact .container { max-width: 960px; }
    .body-compact .card, .body-compact .white-box, .body-compact .status-panel { padding: 18px; }

    /* ── 마이페이지 ── */
    .stat-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(min(100%,160px), 1fr)); gap: 10px; margin-top: 20px; }
    .stat-card { background: #f8fafc; border-radius: 18px; padding: 18px; border: 1px solid #edf2f7; }
    .stat-number { font-size: 26px; font-weight: 950; letter-spacing: -.05em; margin: 0; }
    .stat-label { margin: 4px 0 0; color: var(--muted); font-size: 12.5px; font-weight: 850; }
    .avatar { width: clamp(64px,10vw,90px); height: clamp(64px,10vw,90px); border-radius: 26px; display: grid; place-items: center; background: var(--blue); color: #fff; font-size: clamp(24px,4vw,36px); font-weight: 950; }
    .profile-head { display: flex; align-items: center; gap: 18px; flex-wrap: wrap; }
    .body-dark .stat-card { background: #0f172a; border-color: #1f2937; }
  </style>
</head>
<body>

  <!-- 네비게이션 -->
  <header class="topbar">
    <div class="nav-inner">
      <a href="file:///C:/Users/20060/Downloads/%EC%9E%85%EB%8C%80%EA%B3%B5%EB%9E%B5_v3_1.html#home" class="brand" data-route="home">
        <div class="brand-mark" data-icon="shield"><svg width="20" height="20" viewBox="0 0 24 24" fill="none"><path d="M12 3 19 6v5c0 4.4-2.8 8.4-7 10-4.2-1.6-7-5.6-7-10V6l7-3Z" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"></path><path d="m9.2 12.2 1.8 1.8 3.8-4" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"></path></svg></div>
        <div>
          <p class="brand-title">입대공략</p>
          <p class="brand-sub">입대 정보 · 체력훈련 · 정책 변화</p>
        </div>
      </a>
      <nav class="desktop-nav">
        <button class="nav-btn active" data-route="home">홈</button>
        <button class="nav-btn" data-route="enlistment">입대 정보</button>
        <button class="nav-btn" data-route="training">체력훈련</button>
        <button class="nav-btn" data-route="policy">정책 변화</button>
        <button class="nav-btn" data-route="official">공식 링크</button>
        <button class="nav-btn" data-route="mypage">마이페이지</button>
        <button class="nav-btn" data-route="settings">설정</button>
      </nav>
      <button class="mobile-menu-button" id="mobileMenuButton" aria-label="메뉴"><span data-icon="menu"><svg width="20" height="20" viewBox="0 0 24 24" fill="none"><path d="M4 7h16M4 12h16M4 17h16" stroke="currentColor" stroke-width="1.9" stroke-linecap="round"></path></svg></span></button>
    </div>
    <nav class="mobile-nav" id="mobileNav">
      <button class="nav-btn active" data-route="home">홈</button>
      <button class="nav-btn" data-route="enlistment">입대 정보</button>
      <button class="nav-btn" data-route="training">체력훈련</button>
      <button class="nav-btn" data-route="policy">정책 변화</button>
      <button class="nav-btn" data-route="official">공식 링크</button>
      <button class="nav-btn" data-route="mypage">마이페이지</button>
      <button class="nav-btn" data-route="settings">설정</button>
    </nav>
  </header>

  <!-- 중앙 슬라이드 배너 -->
  <div class="banner-section">
    <div class="banner-slider" id="bannerSlider">
      <div class="banner-track" id="bannerTrack" style="transform: translateX(-200%);">
        <div class="banner-slide blue">
          <div class="banner-content">
            <div class="banner-tag">📋 절차 변경</div>
            <h2 class="banner-title">병무청 증명사진<br>현장 촬영으로 변경</h2>
            <p class="banner-desc">기존 인터넷 등록 방식 → 병무청 방문 시 현장 직접 촬영</p>
          </div>
          <div class="banner-emoji">📸</div>
          <button class="banner-arrow prev" onclick="bannerPrev()">‹</button>
          <button class="banner-arrow next" onclick="bannerNext()">›</button>
        </div>
        <div class="banner-slide dark">
          <div class="banner-content">
            <div class="banner-tag">✈️ 공군</div>
            <h2 class="banner-title">공군 선발 방식<br>랜덤 추첨으로 전환</h2>
            <p class="banner-desc">자격증·면접 방식 → 랜덤 추첨 방식 변경 예정 (2025년 4월~)</p>
          </div>
          <div class="banner-emoji">✈️</div>
          <button class="banner-arrow prev" onclick="bannerPrev()">‹</button>
          <button class="banner-arrow next" onclick="bannerNext()">›</button>
        </div>
        <div class="banner-slide green">
          <div class="banner-content">
            <div class="banner-tag">💰 복지</div>
            <h2 class="banner-title">병사 월급 인상<br>이병 기준 75만원</h2>
            <p class="banner-desc">2025년 기준 단계적 인상 — 상병 100만원 이상 예정</p>
          </div>
          <div class="banner-emoji">💰</div>
          <button class="banner-arrow prev" onclick="bannerPrev()">‹</button>
          <button class="banner-arrow next" onclick="bannerNext()">›</button>
        </div>
        <div class="banner-slide violet">
          <div class="banner-content">
            <div class="banner-tag">📱 훈련소</div>
            <h2 class="banner-title">훈련소 내<br>휴대폰 사용 확대</h2>
            <p class="banner-desc">기초군사훈련 일과 후 개인 휴대폰 사용 허용 범위 확대</p>
          </div>
          <div class="banner-emoji">📱</div>
          <button class="banner-arrow prev" onclick="bannerPrev()">‹</button>
          <button class="banner-arrow next" onclick="bannerNext()">›</button>
        </div>
      </div>
    </div>
    <div class="banner-nav" id="bannerDots"><button class="banner-dot"></button><button class="banner-dot"></button><button class="banner-dot active"></button><button class="banner-dot"></button></div>
  </div>

  <main class="container">

    <!-- ── 홈 ── -->
    <section class="page active" id="page-home">
      <div class="hero-grid">
        <article class="hero-card">
          <div class="eyebrow-pill"><span data-icon="sparkles"><svg width="16" height="16" viewBox="0 0 24 24" fill="none"><path d="m12 3 1.5 4.5L18 9l-4.5 1.5L12 15l-1.5-4.5L6 9l4.5-1.5L12 3Z" stroke="currentColor" stroke-width="1.9" stroke-linejoin="round"></path></svg></span> 피할 수 없다면, 준비하라</div>
          <h1 class="hero-title">입대부터<br>체력준비까지,<br><em>쉽게.</em></h1>
          <p class="hero-desc">병무청에서 찾기 힘든 최신 입대 정보와 군별 체력검정 기준에 맞춘 AI 트레이닝 플랜을 한 곳에서 확인하세요.</p>
          <div class="soft-note"><span data-icon="info"><svg width="20" height="20" viewBox="0 0 24 24" fill="none"><circle cx="12" cy="12" r="9" stroke="currentColor" stroke-width="1.9"></circle><path d="M12 11v5M12 8h.01" stroke="currentColor" stroke-width="1.9" stroke-linecap="round"></path></svg></span> 낯선 시작을 조금 더 단단하게 준비하는 공간</div>
          <div class="hero-actions">
            <button class="btn primary" data-route="enlistment">입대 정보 보기 <span data-icon="chevron"><svg width="16" height="16" viewBox="0 0 24 24" fill="none"><path d="m9 6 6 6-6 6" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path></svg></span></button>
            <button class="btn ghost" data-route="training">체력훈련 시작 <span data-icon="activity"><svg width="20" height="20" viewBox="0 0 24 24" fill="none"><path d="M4 13h4l2-7 4 14 2-7h4" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"></path></svg></span></button>
          </div>
        </article>
        <aside class="status-panel">
          <div class="icon-box"><span data-icon="shield"><svg width="20" height="20" viewBox="0 0 24 24" fill="none"><path d="M12 3 19 6v5c0 4.4-2.8 8.4-7 10-4.2-1.6-7-5.6-7-10V6l7-3Z" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"></path><path d="m9.2 12.2 1.8 1.8 3.8-4" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"></path></svg></span></div>
          <p class="label">오늘의 추천 경로</p>
          <h2 class="panel-title">입대 예정자라면<br>3가지만 먼저.</h2>
          <div class="mini-list">
            <div class="mini-item"><span data-icon="check"><svg width="18" height="18" viewBox="0 0 24 24" fill="none"><circle cx="12" cy="12" r="9" stroke="currentColor" stroke-width="1.9"></circle><path d="m8.5 12.2 2.2 2.3 4.8-5.1" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"></path></svg></span> 입영일자와 입영부대 조회</div>
            <div class="mini-item"><span data-icon="check"><svg width="18" height="18" viewBox="0 0 24 24" fill="none"><circle cx="12" cy="12" r="9" stroke="currentColor" stroke-width="1.9"></circle><path d="m8.5 12.2 2.2 2.3 4.8-5.1" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"></path></svg></span> 준비물과 반입 가능 품목 확인</div>
            <div class="mini-item"><span data-icon="check"><svg width="18" height="18" viewBox="0 0 24 24" fill="none"><circle cx="12" cy="12" r="9" stroke="currentColor" stroke-width="1.9"></circle><path d="m8.5 12.2 2.2 2.3 4.8-5.1" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"></path></svg></span> 4주 기초체력 루틴 시작</div>
          </div>
          <button class="btn blue" data-route="enlistment">입대 정보로 이동 <span data-icon="chevron"><svg width="16" height="16" viewBox="0 0 24 24" fill="none"><path d="m9 6 6 6-6 6" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path></svg></span></button>
        </aside>
      </div>

      <div class="mood-strip">
        <div class="mood-chip"><span class="dot"></span> 입대 준비를 한눈에 정리</div>
        <div class="mood-chip"><span class="dot green"></span> 군별 체력훈련 루틴 제공</div>
        <div class="mood-chip"><span class="dot orange"></span> AI 맞춤 트레이닝 플랜</div>
        <div class="mood-chip"><span class="dot violet"></span> 정책 변화 확인 경로 안내</div>
      </div>

      <div class="section-head">
        <div>
          <p class="eyebrow">Quick Menu</p>
          <h2 class="section-title">자주 찾는 정보</h2>
          <p class="section-desc">카드를 누르면 해당 페이지로 이동합니다.</p>
        </div>
      </div>
      <div class="responsive-grid">
        <button class="card" data-route="enlistment">
          <div>
            <div class="icon-box"><span data-icon="shield"><svg width="20" height="20" viewBox="0 0 24 24" fill="none"><path d="M12 3 19 6v5c0 4.4-2.8 8.4-7 10-4.2-1.6-7-5.6-7-10V6l7-3Z" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"></path><path d="m9.2 12.2 1.8 1.8 3.8-4" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"></path></svg></span></div>
            <h3 class="card-title" style="margin-top:14px;">입대 정보</h3>
            <p class="card-desc">입영일자, 준비물, 절차 변경, 최신 사항 확인.</p>
          </div>
          <span class="card-link">자세히 보기 <span data-icon="chevron"><svg width="16" height="16" viewBox="0 0 24 24" fill="none"><path d="m9 6 6 6-6 6" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path></svg></span></span>
        </button>
        <button class="card" data-route="training">
          <div>
            <div class="icon-box orange"><span data-icon="activity"><svg width="20" height="20" viewBox="0 0 24 24" fill="none"><path d="M4 13h4l2-7 4 14 2-7h4" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"></path></svg></span></div>
            <h3 class="card-title" style="margin-top:14px;">AI 체력훈련</h3>
            <p class="card-desc">군별 체력검정 기준 + AI 맞춤 트레이닝 플랜.</p>
          </div>
          <span class="card-link">훈련 시작 <span data-icon="chevron"><svg width="16" height="16" viewBox="0 0 24 24" fill="none"><path d="m9 6 6 6-6 6" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path></svg></span></span>
        </button>
        <button class="card" data-route="policy">
          <div>
            <div class="icon-box violet"><span data-icon="bell"><svg width="20" height="20" viewBox="0 0 24 24" fill="none"><path d="M18 9a6 6 0 0 0-12 0c0 7-3 7-3 9h18c0-2-3-2-3-9" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"></path><path d="M10 21h4" stroke="currentColor" stroke-width="1.9" stroke-linecap="round"></path></svg></span></div>
            <h3 class="card-title" style="margin-top:14px;">정책 변화</h3>
            <p class="card-desc">급여, 복무환경, 휴대폰 사용 최신 변경사항.</p>
          </div>
          <span class="card-link">자세히 보기 <span data-icon="chevron"><svg width="16" height="16" viewBox="0 0 24 24" fill="none"><path d="m9 6 6 6-6 6" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path></svg></span></span>
        </button>
        <button class="card" data-route="official">
          <div>
            <div class="icon-box green"><span data-icon="external"><svg width="16" height="16" viewBox="0 0 24 24" fill="none"><path d="M14 5h5v5M10 14 19 5M19 13v4a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h4" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"></path></svg></span></div>
            <h3 class="card-title" style="margin-top:14px;">공식 사이트</h3>
            <p class="card-desc">병무청, 국방부, 예비군 공식 링크 바로가기.</p>
          </div>
          <span class="card-link">이동하기 <span data-icon="chevron"><svg width="16" height="16" viewBox="0 0 24 24" fill="none"><path d="m9 6 6 6-6 6" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path></svg></span></span>
        </button>
      </div>

      <div class="section-head">
        <div>
          <p class="eyebrow">Dashboard</p>
          <h2 class="section-title">체크리스트와 중요 알림</h2>
        </div>
      </div>
      <div class="two-col">
        <section class="white-box">
          <div style="display:flex;align-items:center;justify-content:space-between;gap:12px;">
            <div><p class="eyebrow">Checklist</p><h3 class="card-title">입영 전 체크리스트</h3></div>
            <button class="btn light" id="resetChecklist" style="font-size:13px;padding:10px 14px;">초기화</button>
          </div>
          <div class="checklist" id="checklist"><label class="check-item">
          <input type="checkbox" data-check-index="0">
          <span>1. 입영일자와 입영부대 확인</span>
        </label><label class="check-item">
          <input type="checkbox" data-check-index="1">
          <span>2. 입영통지서 출력 또는 모바일 확인</span>
        </label><label class="check-item">
          <input type="checkbox" data-check-index="2">
          <span>3. 신분증, 나라사랑카드 준비</span>
        </label><label class="check-item">
          <input type="checkbox" data-check-index="3">
          <span>4. 안경 착용자는 예비 안경 준비</span>
        </label><label class="check-item">
          <input type="checkbox" data-check-index="4">
          <span>5. 복용 중인 약·진단서 여부 확인</span>
        </label><label class="check-item">
          <input type="checkbox" data-check-index="5">
          <span>6. 휴대전화 반입 기준 확인</span>
        </label><label class="check-item">
          <input type="checkbox" data-check-index="6">
          <span>7. 4주 기초체력 루틴 시작</span>
        </label></div>
          <div class="progress-wrap"><div class="progress-bar" id="progressBar" style="width: 0%;"></div></div>
          <p class="progress-text" id="progressText">0% 완료 · 0/7개 체크</p>
        </section>
        <section class="white-box">
          <div class="section-head" style="margin-top:0;">
            <div><p class="eyebrow">Update Board</p><h3 class="card-title">중요 알림</h3></div>
            <label class="search-box"><span data-icon="search"><svg width="16" height="16" viewBox="0 0 24 24" fill="none"><circle cx="11" cy="11" r="6" stroke="currentColor" stroke-width="1.9"></circle><path d="m20 20-4.2-4.2" stroke="currentColor" stroke-width="1.9" stroke-linecap="round"></path></svg></span><input id="updateSearch" type="search" placeholder="검색어 입력"></label>
          </div>
          <div class="update-list" id="updateList"><article class="update-card">
              <div class="update-top">
                <span class="badge ">입영</span>
                <span class="date">상시 확인</span>
              </div>
              <h4 class="update-title">입영 전 준비물 체크</h4>
              <p class="update-desc">입영통지서, 신분증, 나라사랑카드, 휴대전화 및 일체형 충전기 등은 반드시 공식 안내에서 다시 확인하세요.</p>
            </article><article class="update-card">
              <div class="update-top">
                <span class="badge orange">변경</span>
                <span class="date">2025년 5월</span>
              </div>
              <h4 class="update-title">병무청 증명사진 현장 촬영으로 변경</h4>
              <p class="update-desc">기존 인터넷 사진 등록 방식에서 병무청 현장 촬영 방식으로 변경되었습니다.</p>
            </article><article class="update-card">
              <div class="update-top">
                <span class="badge green">체력</span>
                <span class="date">신규</span>
              </div>
              <h4 class="update-title">군별 AI 트레이닝 플랜 제공</h4>
              <p class="update-desc">육군, 해군, 공군, 해병대별 체력검정 기준에 맞춘 AI 트레이닝 플랜을 확인할 수 있습니다.</p>
            </article><article class="update-card">
              <div class="update-top">
                <span class="badge violet">정책</span>
                <span class="date">공지 기준</span>
              </div>
              <h4 class="update-title">군 정책 변경 알림</h4>
              <p class="update-desc">복무기간, 휴대전화 사용, 장병 복지, 급여는 변경될 수 있으므로 공지 기반으로 업데이트합니다.</p>
            </article></div>
        </section>
      </div>
    </section>

    <!-- ── 입대 정보 ── -->
    <section class="page" id="page-enlistment">
      <article class="detail-hero">
        <div class="breadcrumb">
          <button data-route="home">홈</button><span>/</span><span>입대 정보</span>
        </div>
        <h1 class="detail-title">입영 전에는<br>확인 순서가 중요합니다.</h1>
        <p class="detail-desc">자주 바뀌는 절차 변경사항, 준비물, 군별 최신 정보를 한곳에서 확인하세요.</p>
      </article>

      <!-- 탭 -->
      <div class="tabs" id="infoTabs">
        <button class="tab active" data-info="procedure">절차 변경</button>
        <button class="tab" data-info="items">준비물</button>
        <button class="tab" data-info="branch">군별 최신 정보</button>
      </div>

      <!-- 절차 변경 -->
      <div class="info-panel active" id="info-procedure">
        <div class="section-head" style="margin-top:0;"><div><p class="eyebrow">Step Guide</p><h2 class="section-title">입대 전 확인 흐름</h2></div></div>
        <div class="responsive-grid">
          <article class="card">
            <div>
              <div class="icon-box"><span data-icon="calendar"><svg width="20" height="20" viewBox="0 0 24 24" fill="none"><rect x="3" y="5" width="18" height="16" rx="3" stroke="currentColor" stroke-width="1.9"></rect><path d="M8 3v4M16 3v4M3 10h18" stroke="currentColor" stroke-width="1.9" stroke-linecap="round"></path></svg></span></div>
              <h3 class="card-title" style="margin-top:14px;">1. 입영일자 확인</h3>
              <p class="card-desc">입영 날짜와 입영부대 위치를 먼저 확인하고 이동 계획을 세웁니다.</p>
            </div>
            <a class="card-link" href="https://www.mma.go.kr/" target="_blank" rel="noreferrer">병무청에서 확인 <span data-icon="external"><svg width="16" height="16" viewBox="0 0 24 24" fill="none"><path d="M14 5h5v5M10 14 19 5M19 13v4a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h4" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"></path></svg></span></a>
          </article>
          <article class="card">
            <div>
              <div class="icon-box green"><span data-icon="file"><svg width="20" height="20" viewBox="0 0 24 24" fill="none"><path d="M7 3h7l5 5v13H7a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2Z" stroke="currentColor" stroke-width="1.9" stroke-linejoin="round"></path><path d="M14 3v5h5M9 13h6M9 17h6" stroke="currentColor" stroke-width="1.9" stroke-linecap="round"></path></svg></span></div>
              <h3 class="card-title" style="margin-top:14px;">2. 증명사진 촬영</h3>
              <p class="card-desc">기존 인터넷 사진 등록 방식 → 병무청 방문 현장 촬영으로 변경되었습니다.</p>
            </div>
            <button class="card-link" data-route="official">공식 링크 보기 <span data-icon="chevron"><svg width="16" height="16" viewBox="0 0 24 24" fill="none"><path d="m9 6 6 6-6 6" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path></svg></span></button>
          </article>
          <article class="card">
            <div>
              <div class="icon-box orange"><span data-icon="activity"><svg width="20" height="20" viewBox="0 0 24 24" fill="none"><path d="M4 13h4l2-7 4 14 2-7h4" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"></path></svg></span></div>
              <h3 class="card-title" style="margin-top:14px;">3. 기초체력 준비</h3>
              <p class="card-desc">달리기, 팔굽혀펴기, 코어 운동을 입대 전 4주 이상 준비합니다.</p>
            </div>
            <button class="card-link" data-route="training">훈련 루틴 보기 <span data-icon="chevron"><svg width="16" height="16" viewBox="0 0 24 24" fill="none"><path d="m9 6 6 6-6 6" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path></svg></span></button>
          </article>
        </div>
        <div class="update-list" style="margin-top:20px;">
          <article class="update-card">
            <div class="update-top"><span class="badge">변경</span><span class="date">2025년 5월</span></div>
            <h4 class="update-title">병무청 증명사진 현장 촬영으로 변경</h4>
            <p class="update-desc">기존에는 인터넷으로 병무청에 사진을 등록할 수 있었으나, 변경 후에는 병무청 방문 시 현장에서 직접 촬영하는 방식으로 바뀌었습니다.</p>
          </article>
          <article class="update-card">
            <div class="update-top"><span class="badge orange">공지</span><span class="date">2025년 4월</span></div>
            <h4 class="update-title">공군 선발 방식 변경 예정</h4>
            <p class="update-desc">기존 자격증 취득 후 면접 방식에서 랜덤 추첨 방식으로 변경될 예정입니다. 정확한 시행일은 병무청 공식 사이트에서 확인하세요.</p>
          </article>
        </div>
      </div>

      <!-- 준비물 -->
      <div class="info-panel" id="info-items" style="display:none;">
        <div class="section-head" style="margin-top:0;"><div><p class="eyebrow">Checklist</p><h2 class="section-title">입대 준비물</h2></div></div>
        <div class="responsive-grid">
          <article class="card">
            <div>
              <div class="icon-box"><span data-icon="file"><svg width="20" height="20" viewBox="0 0 24 24" fill="none"><path d="M7 3h7l5 5v13H7a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2Z" stroke="currentColor" stroke-width="1.9" stroke-linejoin="round"></path><path d="M14 3v5h5M9 13h6M9 17h6" stroke="currentColor" stroke-width="1.9" stroke-linecap="round"></path></svg></span></div>
              <h3 class="card-title" style="margin-top:14px;">필수 서류</h3>
              <p class="card-desc">입영통지서, 주민등록증 (또는 여권), 나라사랑카드를 반드시 지참합니다.</p>
            </div>
          </article>
          <article class="card">
            <div>
              <div class="icon-box green"><span data-icon="user"><svg width="20" height="20" viewBox="0 0 24 24" fill="none"><circle cx="12" cy="8" r="4" stroke="currentColor" stroke-width="1.9"></circle><path d="M4 20a8 8 0 0 1 16 0" stroke="currentColor" stroke-width="1.9" stroke-linecap="round"></path></svg></span></div>
              <h3 class="card-title" style="margin-top:14px;">개인 위생용품</h3>
              <p class="card-desc">칫솔, 치약, 면도기 등은 훈련소에서 구매 가능하나 미리 준비하면 편리합니다.</p>
            </div>
          </article>
          <article class="card">
            <div>
              <div class="icon-box orange"><span data-icon="info"><svg width="20" height="20" viewBox="0 0 24 24" fill="none"><circle cx="12" cy="12" r="9" stroke="currentColor" stroke-width="1.9"></circle><path d="M12 11v5M12 8h.01" stroke="currentColor" stroke-width="1.9" stroke-linecap="round"></path></svg></span></div>
              <h3 class="card-title" style="margin-top:14px;">반입 금지 물품</h3>
              <p class="card-desc">이어폰, 전자담배, 다용도 칼 등은 반입 금지입니다. 최신 기준은 공식 사이트 확인 필수.</p>
            </div>
            <a class="card-link" href="https://www.mma.go.kr/" target="_blank" rel="noreferrer">병무청 확인 <span data-icon="external"><svg width="16" height="16" viewBox="0 0 24 24" fill="none"><path d="M14 5h5v5M10 14 19 5M19 13v4a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h4" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"></path></svg></span></a>
          </article>
          <article class="card">
            <div>
              <div class="icon-box violet"><span data-icon="bell"><svg width="20" height="20" viewBox="0 0 24 24" fill="none"><path d="M18 9a6 6 0 0 0-12 0c0 7-3 7-3 9h18c0-2-3-2-3-9" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"></path><path d="M10 21h4" stroke="currentColor" stroke-width="1.9" stroke-linecap="round"></path></svg></span></div>
              <h3 class="card-title" style="margin-top:14px;">의약품·안경</h3>
              <p class="card-desc">복용 중인 약과 처방전, 안경 착용자는 예비 안경을 챙깁니다.</p>
            </div>
          </article>
        </div>
      </div>

      <!-- 군별 최신 정보 -->
      <div class="info-panel" id="info-branch" style="display:none;">
        <div class="section-head" style="margin-top:0;"><div><p class="eyebrow">By Branch</p><h2 class="section-title">군별 최신 정보</h2></div></div>
        <div class="update-list">
          <article class="update-card">
            <div class="update-top"><span class="badge green">육군</span><span class="date">2025년 5월</span></div>
            <h4 class="update-title">훈련소 내 개인 휴대폰 사용 확대</h4>
            <p class="update-desc">기초군사훈련 중 일과 후 개인 휴대폰 사용이 확대 허용되었습니다. 사용 가능 시간과 범위는 부대별로 상이합니다.</p>
          </article>
          <article class="update-card">
            <div class="update-top"><span class="badge">공군</span><span class="date">2025년 4월</span></div>
            <h4 class="update-title">공군 선발 방식 랜덤 추첨으로 변경 예정</h4>
            <p class="update-desc">기존 자격증 기반 면접 방식에서 랜덤 추첨 방식으로 변경 예정. 정확한 시행일은 병무청 공식 공지를 확인하세요.</p>
          </article>
          <article class="update-card">
            <div class="update-top"><span class="badge orange">해군</span><span class="date">2025년 5월</span></div>
            <h4 class="update-title">병사 월급 단계적 인상</h4>
            <p class="update-desc">2025년 기준 이병 월급이 75만원으로 인상되었습니다. 상병 기준 100만원 이상으로 단계적 인상이 예정되어 있습니다.</p>
          </article>
          <article class="update-card">
            <div class="update-top"><span class="badge violet">해병대</span><span class="date">2025년 5월</span></div>
            <h4 class="update-title">해병대 체력검정 기준 일부 조정</h4>
            <p class="update-desc">해병대 입대 체력검정 기준이 일부 조정되었습니다. 트레이닝 파트에서 최신 기준에 맞는 플랜을 확인하세요.</p>
          </article>
        </div>
      </div>
    </section>

    <!-- ── 체력훈련 ── -->
    <section class="page" id="page-training">
      <article class="detail-hero light">
        <div class="breadcrumb"><button data-route="home">홈</button><span>/</span><span>체력훈련</span></div>
        <h1 class="detail-title">군별 체력 기준에 맞춰<br>방향을 다르게 잡으세요.</h1>
        <p class="detail-desc">공통적으로 달리기, 팔굽혀펴기, 코어 지구력을 준비하되, 군별 특성에 맞게 루틴을 선택하세요.</p>
      </article>

      <!-- AI 플랜 생성 -->
      <div class="section-head"><div><p class="eyebrow">AI Training</p><h2 class="section-title">AI 맞춤 트레이닝 플랜</h2><p class="section-desc">키, 몸무게, 지원 군을 입력하면 AI가 플랜을 생성합니다.</p></div></div>
      <div class="white-box">
        <div class="ai-form">
          <div class="ai-form-group">
            <label>키 (cm)</label>
            <input type="number" id="aiHeight" placeholder="175" min="140" max="220">
          </div>
          <div class="ai-form-group">
            <label>몸무게 (kg)</label>
            <input type="number" id="aiWeight" placeholder="70" min="40" max="150">
          </div>
          <div class="ai-form-group">
            <label>지원 군</label>
            <select id="aiBranch">
              <option value="army">육군</option>
              <option value="navy">해군</option>
              <option value="airforce">공군</option>
              <option value="marine">해병대</option>
            </select>
          </div>
          <div class="ai-form-group">
            <label>입대까지 남은 기간</label>
            <select id="aiPeriod">
              <option value="1">1개월</option>
              <option value="2" selected="">2개월</option>
              <option value="3">3개월</option>
              <option value="6">6개월 이상</option>
            </select>
          </div>
        </div>
        <button class="btn blue" style="width:100%;padding:15px;" onclick="generateAIPlan()">
          <span data-icon="sparkles"><svg width="16" height="16" viewBox="0 0 24 24" fill="none"><path d="m12 3 1.5 4.5L18 9l-4.5 1.5L12 15l-1.5-4.5L6 9l4.5-1.5L12 3Z" stroke="currentColor" stroke-width="1.9" stroke-linejoin="round"></path></svg></span> AI 플랜 생성하기
        </button>
        <div class="ai-plan-box" id="aiPlanResult" style="display:none;">
          <h3 id="aiPlanTitle">육군 맞춤 트레이닝 플랜</h3>
          <p class="ai-plan-sub" id="aiPlanSub">2개월 기준 · 주 5회 훈련</p>
          <div id="aiExercises"></div>
          <button class="btn blue" style="width:100%;margin-top:12px;padding:14px;" onclick="saveRecord()">
            기록 저장 후 다음 플랜 받기
          </button>
        </div>
      </div>

      <!-- 군별 루틴 -->
      <div class="section-head"><div><p class="eyebrow">By Branch</p><h2 class="section-title">군별 4주 루틴</h2></div></div>
      <div class="tabs" id="branchTabs">
        <button class="tab active" data-branch="army">육군</button>
        <button class="tab" data-branch="navy">해군</button>
        <button class="tab" data-branch="airforce">공군</button>
        <button class="tab" data-branch="marine">해병대</button>
      </div>
      <div id="branchPanels">
        <section class="branch-panel active" data-branch-panel="army">
          <div class="training-layout">
            <article class="white-box">
              <p class="eyebrow">육군 Training</p>
              <h2 class="section-title">3km 달리기와 근지구력 중심</h2>
              <p class="section-desc">육군은 오래 버티는 힘이 중요합니다. 달리기, 팔굽혀펴기, 코어를 균형 있게 준비하세요.</p>
              <div class="mini-list" style="margin-top:18px;">
                <div class="mini-item"><span data-icon="check"><svg width="18" height="18" viewBox="0 0 24 24" fill="none"><circle cx="12" cy="12" r="9" stroke="currentColor" stroke-width="1.9"></circle><path d="m8.5 12.2 2.2 2.3 4.8-5.1" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"></path></svg></span><span><strong>3km 달리기</strong><br><small style="color:#64748b;font-weight:700;">장거리 페이스 유지</small></span></div><div class="mini-item"><span data-icon="check"><svg width="18" height="18" viewBox="0 0 24 24" fill="none"><circle cx="12" cy="12" r="9" stroke="currentColor" stroke-width="1.9"></circle><path d="m8.5 12.2 2.2 2.3 4.8-5.1" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"></path></svg></span><span><strong>팔굽혀펴기</strong><br><small style="color:#64748b;font-weight:700;">정확한 자세와 반복</small></span></div><div class="mini-item"><span data-icon="check"><svg width="18" height="18" viewBox="0 0 24 24" fill="none"><circle cx="12" cy="12" r="9" stroke="currentColor" stroke-width="1.9"></circle><path d="m8.5 12.2 2.2 2.3 4.8-5.1" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"></path></svg></span><span><strong>코어 지구력</strong><br><small style="color:#64748b;font-weight:700;">플랭크와 복근 안정성</small></span></div>
              </div>
            </article>
            <article class="meter-card">
              <p class="eyebrow">Focus Balance</p>
              <h3 class="card-title">육군 준비 비중</h3>
              <p class="section-desc" style="margin-bottom:16px;">준비 방향을 시각화한 가이드입니다.</p>
              <div class="meter-title"><span>심폐지구력</span><span>92%</span></div><div class="meter"><span style="--w:92%"></span></div><div class="meter-title"><span>상체 근지구력</span><span>82%</span></div><div class="meter"><span style="--w:82%"></span></div><div class="meter-title"><span>코어 안정성</span><span>78%</span></div><div class="meter"><span style="--w:78%"></span></div>
            </article>
          </div>
          <div class="section-head"><div><p class="eyebrow">4 Week Routine</p><h3 class="section-title">육군 4주 준비 루틴</h3></div></div>
          <div class="routine-grid">
            <article class="routine-card"><span class="routine-day">1주차</span><h4>2km 조깅</h4><p>2km 조깅 + 팔굽혀펴기 5세트 + 플랭크</p></article><article class="routine-card"><span class="routine-day">2주차</span><h4>200m 인터벌 6회</h4><p>200m 인터벌 6회 + 팔굽혀펴기 총 80회</p></article><article class="routine-card"><span class="routine-day">3주차</span><h4>3km 기록 측정</h4><p>3km 기록 측정 + 스쿼트/런지 + 코어</p></article><article class="routine-card"><span class="routine-day">4주차</span><h4>3km 페이스런</h4><p>3km 페이스런 + 실전식 체력 테스트</p></article>
          </div>
        </section>
        <section class="branch-panel " data-branch-panel="navy">
          <div class="training-layout">
            <article class="white-box">
              <p class="eyebrow">해군 Training</p>
              <h2 class="section-title">유산소 + 수영 적응 + 전신 지구력</h2>
              <p class="section-desc">해군은 수영 능력이 중요할 수 있습니다. 물 적응과 어깨 안정성을 함께 준비하세요.</p>
              <div class="mini-list" style="margin-top:18px;">
                <div class="mini-item"><span data-icon="check"><svg width="18" height="18" viewBox="0 0 24 24" fill="none"><circle cx="12" cy="12" r="9" stroke="currentColor" stroke-width="1.9"></circle><path d="m8.5 12.2 2.2 2.3 4.8-5.1" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"></path></svg></span><span><strong>달리기</strong><br><small style="color:#64748b;font-weight:700;">기초 심폐지구력</small></span></div><div class="mini-item"><span data-icon="check"><svg width="18" height="18" viewBox="0 0 24 24" fill="none"><circle cx="12" cy="12" r="9" stroke="currentColor" stroke-width="1.9"></circle><path d="m8.5 12.2 2.2 2.3 4.8-5.1" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"></path></svg></span><span><strong>수영 적응</strong><br><small style="color:#64748b;font-weight:700;">호흡과 킥 연습</small></span></div><div class="mini-item"><span data-icon="check"><svg width="18" height="18" viewBox="0 0 24 24" fill="none"><circle cx="12" cy="12" r="9" stroke="currentColor" stroke-width="1.9"></circle><path d="m8.5 12.2 2.2 2.3 4.8-5.1" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"></path></svg></span><span><strong>어깨 안정성</strong><br><small style="color:#64748b;font-weight:700;">등 근육 보강</small></span></div>
              </div>
            </article>
            <article class="meter-card">
              <p class="eyebrow">Focus Balance</p>
              <h3 class="card-title">해군 준비 비중</h3>
              <p class="section-desc" style="margin-bottom:16px;">준비 방향을 시각화한 가이드입니다.</p>
              <div class="meter-title"><span>심폐지구력</span><span>86%</span></div><div class="meter"><span style="--w:86%"></span></div><div class="meter-title"><span>수영 적응</span><span>88%</span></div><div class="meter"><span style="--w:88%"></span></div><div class="meter-title"><span>전신 지구력</span><span>80%</span></div><div class="meter"><span style="--w:80%"></span></div>
            </article>
          </div>
          <div class="section-head"><div><p class="eyebrow">4 Week Routine</p><h3 class="section-title">해군 4주 준비 루틴</h3></div></div>
          <div class="routine-grid">
            <article class="routine-card"><span class="routine-day">1주차</span><h4>조깅 20분</h4><p>조깅 20분 + 자유형 킥판 + 밴드 로우</p></article><article class="routine-card"><span class="routine-day">2주차</span><h4>달리기 인터벌</h4><p>달리기 인터벌 + 수영 25m 반복</p></article><article class="routine-card"><span class="routine-day">3주차</span><h4>수영 누적 200~400m</h4><p>수영 누적 200~400m + 코어</p></article><article class="routine-card"><span class="routine-day">4주차</span><h4>달리기 기록 측정</h4><p>달리기 기록 측정 + 수영 호흡 안정</p></article>
          </div>
        </section>
        <section class="branch-panel " data-branch-panel="airforce">
          <div class="training-layout">
            <article class="white-box">
              <p class="eyebrow">공군 Training</p>
              <h2 class="section-title">꾸준한 유산소와 자세 안정성</h2>
              <p class="section-desc">공군 지원자는 꾸준한 컨디션 관리, 심폐지구력, 바른 자세를 유지하는 근지구력이 중요합니다.</p>
              <div class="mini-list" style="margin-top:18px;">
                <div class="mini-item"><span data-icon="check"><svg width="18" height="18" viewBox="0 0 24 24" fill="none"><circle cx="12" cy="12" r="9" stroke="currentColor" stroke-width="1.9"></circle><path d="m8.5 12.2 2.2 2.3 4.8-5.1" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"></path></svg></span><span><strong>2km 러닝</strong><br><small style="color:#64748b;font-weight:700;">안정적인 페이스</small></span></div><div class="mini-item"><span data-icon="check"><svg width="18" height="18" viewBox="0 0 24 24" fill="none"><circle cx="12" cy="12" r="9" stroke="currentColor" stroke-width="1.9"></circle><path d="m8.5 12.2 2.2 2.3 4.8-5.1" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"></path></svg></span><span><strong>상체 근지구력</strong><br><small style="color:#64748b;font-weight:700;">정확한 푸시업</small></span></div><div class="mini-item"><span data-icon="check"><svg width="18" height="18" viewBox="0 0 24 24" fill="none"><circle cx="12" cy="12" r="9" stroke="currentColor" stroke-width="1.9"></circle><path d="m8.5 12.2 2.2 2.3 4.8-5.1" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"></path></svg></span><span><strong>자세 안정</strong><br><small style="color:#64748b;font-weight:700;">플랭크와 버드독</small></span></div>
              </div>
            </article>
            <article class="meter-card">
              <p class="eyebrow">Focus Balance</p>
              <h3 class="card-title">공군 준비 비중</h3>
              <p class="section-desc" style="margin-bottom:16px;">준비 방향을 시각화한 가이드입니다.</p>
              <div class="meter-title"><span>심폐지구력</span><span>84%</span></div><div class="meter"><span style="--w:84%"></span></div><div class="meter-title"><span>자세 안정성</span><span>86%</span></div><div class="meter"><span style="--w:86%"></span></div><div class="meter-title"><span>회복 관리</span><span>82%</span></div><div class="meter"><span style="--w:82%"></span></div>
            </article>
          </div>
          <div class="section-head"><div><p class="eyebrow">4 Week Routine</p><h3 class="section-title">공군 4주 준비 루틴</h3></div></div>
          <div class="routine-grid">
            <article class="routine-card"><span class="routine-day">1주차</span><h4>2km 편한 페이스</h4><p>2km 편한 페이스 + 팔굽혀펴기</p></article><article class="routine-card"><span class="routine-day">2주차</span><h4>400m 인터벌 4회</h4><p>400m 인터벌 4회 + 코어</p></article><article class="routine-card"><span class="routine-day">3주차</span><h4>2km 기록 측정</h4><p>2km 기록 측정 + 등 운동</p></article><article class="routine-card"><span class="routine-day">4주차</span><h4>페이스런</h4><p>페이스런 + 실전식 체력 테스트</p></article>
          </div>
        </section>
        <section class="branch-panel " data-branch-panel="marine">
          <div class="training-layout">
            <article class="white-box">
              <p class="eyebrow">해병대 Training</p>
              <h2 class="section-title">강한 근지구력과 고강도 적응</h2>
              <p class="section-desc">해병대는 달리기, 팔굽혀펴기, 코어, 전신 서킷을 꾸준히 준비하는 것이 좋습니다.</p>
              <div class="mini-list" style="margin-top:18px;">
                <div class="mini-item"><span data-icon="check"><svg width="18" height="18" viewBox="0 0 24 24" fill="none"><circle cx="12" cy="12" r="9" stroke="currentColor" stroke-width="1.9"></circle><path d="m8.5 12.2 2.2 2.3 4.8-5.1" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"></path></svg></span><span><strong>달리기</strong><br><small style="color:#64748b;font-weight:700;">페이스 유지와 스퍼트</small></span></div><div class="mini-item"><span data-icon="check"><svg width="18" height="18" viewBox="0 0 24 24" fill="none"><circle cx="12" cy="12" r="9" stroke="currentColor" stroke-width="1.9"></circle><path d="m8.5 12.2 2.2 2.3 4.8-5.1" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"></path></svg></span><span><strong>팔굽혀펴기/복근</strong><br><small style="color:#64748b;font-weight:700;">반복 수행 능력</small></span></div><div class="mini-item"><span data-icon="check"><svg width="18" height="18" viewBox="0 0 24 24" fill="none"><circle cx="12" cy="12" r="9" stroke="currentColor" stroke-width="1.9"></circle><path d="m8.5 12.2 2.2 2.3 4.8-5.1" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"></path></svg></span><span><strong>전신 서킷</strong><br><small style="color:#64748b;font-weight:700;">버피, 스쿼트, 런지</small></span></div>
              </div>
            </article>
            <article class="meter-card">
              <p class="eyebrow">Focus Balance</p>
              <h3 class="card-title">해병대 준비 비중</h3>
              <p class="section-desc" style="margin-bottom:16px;">준비 방향을 시각화한 가이드입니다.</p>
              <div class="meter-title"><span>심폐지구력</span><span>94%</span></div><div class="meter"><span style="--w:94%"></span></div><div class="meter-title"><span>근지구력</span><span>90%</span></div><div class="meter"><span style="--w:90%"></span></div><div class="meter-title"><span>고강도 적응</span><span>88%</span></div><div class="meter"><span style="--w:88%"></span></div>
            </article>
          </div>
          <div class="section-head"><div><p class="eyebrow">4 Week Routine</p><h3 class="section-title">해병대 4주 준비 루틴</h3></div></div>
          <div class="routine-grid">
            <article class="routine-card"><span class="routine-day">1주차</span><h4>조깅 20분</h4><p>조깅 20분 + 전신 서킷 2라운드</p></article><article class="routine-card"><span class="routine-day">2주차</span><h4>언덕 달리기</h4><p>언덕 달리기 + 팔굽혀펴기 누적 100회</p></article><article class="routine-card"><span class="routine-day">3주차</span><h4>3km 기록 측정</h4><p>3km 기록 측정 + 버피/스쿼트</p></article><article class="routine-card"><span class="routine-day">4주차</span><h4>실전식 테스트</h4><p>실전식 테스트 + 약점 보완</p></article>
          </div>
        </section></div>
      <div class="source-note"><strong>주의:</strong> 군별·병과별 체력 기준은 시기와 모집 분야에 따라 달라질 수 있습니다. 최종 기준은 반드시 병무청·각 군 공식 안내에서 확인하세요.</div>
    </section>

    <!-- ── 정책 변화 ── -->
    <section class="page" id="page-policy">
      <article class="detail-hero">
        <div class="breadcrumb"><button data-route="home">홈</button><span>/</span><span>정책 변화</span></div>
        <h1 class="detail-title">군 정책은<br>공지 기준으로 확인하세요.</h1>
        <p class="detail-desc">장병 복지, 휴대전화 사용, 급여, 입영 제도는 변경될 수 있습니다.</p>
      </article>
      <div class="section-head"><div><p class="eyebrow">Policy Hub</p><h2 class="section-title">최신 정책 변화</h2></div></div>
      <div class="update-list">
        <article class="update-card">
          <div class="update-top"><span class="badge green">복지</span><span class="date">2025년</span></div>
          <h4 class="update-title">병사 월급 단계적 인상</h4>
          <p class="update-desc">2025년 기준 육군 이병 월급 75만원으로 인상. 상병 100만원 이상 단계적 인상 예정. 장병 복지 향상의 일환입니다.</p>
        </article>
        <article class="update-card">
          <div class="update-top"><span class="badge">훈련소</span><span class="date">2025년</span></div>
          <h4 class="update-title">훈련소 내 휴대폰 사용 확대</h4>
          <p class="update-desc">기초군사훈련 기간 중 일과 후 개인 휴대폰 사용 허용 범위가 확대되었습니다. 부대별 세부 기준은 상이할 수 있습니다.</p>
        </article>
        <article class="update-card">
          <div class="update-top"><span class="badge orange">입대절차</span><span class="date">2025년 5월</span></div>
          <h4 class="update-title">병무청 증명사진 현장 촬영 전환</h4>
          <p class="update-desc">기존 인터넷 사진 등록 방식에서 병무청 방문 시 현장 촬영 방식으로 변경됩니다. 병무청 공식 사이트에서 최신 안내를 확인하세요.</p>
        </article>
        <article class="update-card">
          <div class="update-top"><span class="badge violet">공군</span><span class="date">2025년 4월</span></div>
          <h4 class="update-title">공군 지원 방식 랜덤 추첨으로 전환</h4>
          <p class="update-desc">기존 자격증·면접 방식에서 랜덤 추첨 방식으로 변경 예정. 정확한 시행일 및 세부 사항은 병무청 공식 공지 확인 필수.</p>
        </article>
      </div>
      <div class="section-head"><div><p class="eyebrow">Official</p><h2 class="section-title">정책 확인 공식 경로</h2></div></div>
      <div class="responsive-grid">
        <a class="card" href="https://www.mnd.go.kr/" target="_blank" rel="noreferrer">
          <div><div class="icon-box violet"><span data-icon="bell"><svg width="20" height="20" viewBox="0 0 24 24" fill="none"><path d="M18 9a6 6 0 0 0-12 0c0 7-3 7-3 9h18c0-2-3-2-3-9" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"></path><path d="M10 21h4" stroke="currentColor" stroke-width="1.9" stroke-linecap="round"></path></svg></span></div><h3 class="card-title" style="margin-top:14px;">국방부 보도자료</h3><p class="card-desc">국방 정책, 장병 복지, 제도 변경 소식 확인.</p></div>
          <span class="card-link">이동하기 <span data-icon="external"><svg width="16" height="16" viewBox="0 0 24 24" fill="none"><path d="M14 5h5v5M10 14 19 5M19 13v4a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h4" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"></path></svg></span></span>
        </a>
        <a class="card" href="https://www.mma.go.kr/" target="_blank" rel="noreferrer">
          <div><div class="icon-box"><span data-icon="file"><svg width="20" height="20" viewBox="0 0 24 24" fill="none"><path d="M7 3h7l5 5v13H7a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2Z" stroke="currentColor" stroke-width="1.9" stroke-linejoin="round"></path><path d="M14 3v5h5M9 13h6M9 17h6" stroke="currentColor" stroke-width="1.9" stroke-linecap="round"></path></svg></span></div><h3 class="card-title" style="margin-top:14px;">병무청 공지</h3><p class="card-desc">입영, 모집병, 병역판정, 동원훈련 관련 공지 확인.</p></div>
          <span class="card-link">이동하기 <span data-icon="external"><svg width="16" height="16" viewBox="0 0 24 24" fill="none"><path d="M14 5h5v5M10 14 19 5M19 13v4a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h4" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"></path></svg></span></span>
        </a>
      </div>
    </section>

    <!-- ── 공식 링크 ── -->
    <section class="page" id="page-official">
      <article class="detail-hero light">
        <div class="breadcrumb"><button data-route="home">홈</button><span>/</span><span>공식 링크</span></div>
        <h1 class="detail-title">정확한 정보는<br>공식 사이트에서 마무리.</h1>
        <p class="detail-desc">이 웹사이트는 정보를 쉽게 이해하기 위한 안내용입니다. 개인별 최종 기준은 공식 사이트에서 확인하세요.</p>
      </article>
      <div class="section-head"><div><p class="eyebrow">Official Links</p><h2 class="section-title">공식 사이트 바로가기</h2></div></div>
      <div class="official-grid">
        <a class="card" href="https://www.mma.go.kr/" target="_blank" rel="noreferrer">
          <div><div class="icon-box"><span data-icon="file"><svg width="20" height="20" viewBox="0 0 24 24" fill="none"><path d="M7 3h7l5 5v13H7a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2Z" stroke="currentColor" stroke-width="1.9" stroke-linejoin="round"></path><path d="M14 3v5h5M9 13h6M9 17h6" stroke="currentColor" stroke-width="1.9" stroke-linecap="round"></path></svg></span></div><h3 class="card-title" style="margin-top:14px;">병무청</h3><p class="card-desc">입영신청, 입영일자 조회, 모집계획, 병역민원</p></div>
          <span class="card-link">이동하기 <span data-icon="external"><svg width="16" height="16" viewBox="0 0 24 24" fill="none"><path d="M14 5h5v5M10 14 19 5M19 13v4a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h4" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"></path></svg></span></span>
        </a>
        <a class="card" href="https://www.yebigun1.mil.kr/" target="_blank" rel="noreferrer">
          <div><div class="icon-box green"><span data-icon="home"><svg width="20" height="20" viewBox="0 0 24 24" fill="none"><path d="m4 10.5 8-6.5 8 6.5V20a1 1 0 0 1-1 1h-5v-6H10v6H5a1 1 0 0 1-1-1v-9.5Z" stroke="currentColor" stroke-width="1.9" stroke-linejoin="round"></path></svg></span></div><h3 class="card-title" style="margin-top:14px;">예비군 홈페이지</h3><p class="card-desc">예비군 훈련, 훈련장, 일정 확인</p></div>
          <span class="card-link">이동하기 <span data-icon="external"><svg width="16" height="16" viewBox="0 0 24 24" fill="none"><path d="M14 5h5v5M10 14 19 5M19 13v4a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h4" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"></path></svg></span></span>
        </a>
        <a class="card" href="https://www.mnd.go.kr/" target="_blank" rel="noreferrer">
          <div><div class="icon-box violet"><span data-icon="bell"><svg width="20" height="20" viewBox="0 0 24 24" fill="none"><path d="M18 9a6 6 0 0 0-12 0c0 7-3 7-3 9h18c0-2-3-2-3-9" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"></path><path d="M10 21h4" stroke="currentColor" stroke-width="1.9" stroke-linecap="round"></path></svg></span></div><h3 class="card-title" style="margin-top:14px;">국방부</h3><p class="card-desc">군 정책, 보도자료, 장병 복지 관련 소식</p></div>
          <span class="card-link">이동하기 <span data-icon="external"><svg width="16" height="16" viewBox="0 0 24 24" fill="none"><path d="M14 5h5v5M10 14 19 5M19 13v4a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h4" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"></path></svg></span></span>
        </a>
        <a class="card" href="https://nfa.kspo.or.kr/" target="_blank" rel="noreferrer">
          <div><div class="icon-box orange"><span data-icon="activity"><svg width="20" height="20" viewBox="0 0 24 24" fill="none"><path d="M4 13h4l2-7 4 14 2-7h4" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"></path></svg></span></div><h3 class="card-title" style="margin-top:14px;">국민체력100</h3><p class="card-desc">체력 인증, 체력 측정, 운동 처방 확인</p></div>
          <span class="card-link">이동하기 <span data-icon="external"><svg width="16" height="16" viewBox="0 0 24 24" fill="none"><path d="M14 5h5v5M10 14 19 5M19 13v4a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h4" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"></path></svg></span></span>
        </a>
      </div>
    </section>

    <!-- ── 설정 ── -->
    <section class="page" id="page-settings">
      <article class="detail-hero">
        <div class="breadcrumb"><button data-route="home">홈</button><span>/</span><span>설정</span></div>
        <h1 class="detail-title">웹사이트 설정을<br>내 스타일로.</h1>
        <p class="detail-desc">다크 모드, 컴팩트 화면 설정을 브라우저에 저장합니다.</p>
      </article>
      <section class="white-box" style="margin-top:24px;">
        <p class="eyebrow">Settings</p>
        <h2 class="card-title">화면 설정</h2>
        <div class="settings-row">
          <div><h3 class="update-title">다크 모드</h3><p class="section-desc">어두운 배경으로 화면을 전환합니다.</p></div>
          <button class="toggle" id="darkToggle"><span></span></button>
        </div>
        <div class="settings-row">
          <div><h3 class="update-title">컴팩트 화면</h3><p class="section-desc">카드와 여백을 조금 더 작게 보여줍니다.</p></div>
          <button class="toggle" id="compactToggle"><span></span></button>
        </div>
        <div style="margin-top:20px;">
          <button class="btn light" id="resetSettings">설정 초기화</button>
        </div>
      </section>
    </section>

    <!-- ── 마이페이지 ── -->
    <section class="page" id="page-mypage">
      <article class="detail-hero light">
        <div class="breadcrumb"><button data-route="home">홈</button><span>/</span><span>마이페이지</span></div>
        <div class="profile-head">
          <div class="avatar" id="avatarText">군</div>
          <div>
            <p class="eyebrow">My Page</p>
            <h1 class="detail-title" style="font-size:clamp(28px,4vw,46px);">나의 입대 준비 현황</h1>
            <p class="detail-desc">닉네임과 입대 정보를 입력하면 전역일을 계산해드립니다.</p>
          </div>
        </div>
      </article>

      <div class="two-col" style="margin-top:24px;">
        <!-- 프로필 입력 -->
        <section class="white-box">
          <p class="eyebrow">Profile</p>
          <h2 class="card-title">기본 정보</h2>
          <label class="form-group">
            <span class="form-label">닉네임</span>
            <input class="form-input" id="profileName" type="text" placeholder="이름 또는 닉네임 입력">
          </label>
          <label class="form-group">
            <span class="form-label">관심 군</span>
            <select class="form-select" id="profileBranch">
              <option value="army">육군 (18개월)</option>
              <option value="navy">해군 (20개월)</option>
              <option value="airforce">공군 (21개월)</option>
              <option value="marine">해병대 (18개월)</option>
            </select>
          </label>
          <label class="form-group">
            <span class="form-label">입대 예정일 (또는 입대일)</span>
            <input class="form-input" id="enlistDate" type="date">
          </label>
          <button class="btn blue" id="saveProfile" style="width:100%;margin-top:18px;padding:14px;">
            <span data-icon="check"><svg width="18" height="18" viewBox="0 0 24 24" fill="none"><circle cx="12" cy="12" r="9" stroke="currentColor" stroke-width="1.9"></circle><path d="m8.5 12.2 2.2 2.3 4.8-5.1" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"></path></svg></span> 저장하기
          </button>
          <p id="saveMsg" style="text-align:center;font-size:13px;color:var(--green);font-weight:800;margin-top:10px;display:none;">✅ 저장되었습니다!</p>
        </section>

        <!-- 전역일 계산 결과 -->
        <section class="white-box">
          <p class="eyebrow">D-Day Calculator</p>
          <h2 class="card-title">전역일 계산</h2>
          <div id="dday-result" style="margin-top:18px;">
            <div style="background:#f8fafc;border-radius:18px;padding:20px;text-align:center;border:1px solid #e5e7eb;">
              <p style="color:var(--muted);font-size:14px;font-weight:700;margin:0;">입대 정보를 입력하고 저장하면<br>전역일이 자동으로 계산됩니다.</p>
            </div>
          </div>
        </section>
      </div>

      <!-- 준비 현황 -->
      <div class="section-head"><div><p class="eyebrow">My Progress</p><h2 class="section-title">나의 준비 현황</h2></div></div>
      <div class="stat-grid">
        <div class="stat-card">
          <p class="stat-number" id="statChecklist">0%</p>
          <p class="stat-label">체크리스트 완료율</p>
        </div>
        <div class="stat-card">
          <p class="stat-number" id="statBranch">—</p>
          <p class="stat-label">선택한 군</p>
        </div>
        <div class="stat-card">
          <p class="stat-number" id="statDday">—</p>
          <p class="stat-label">입대까지 남은 날</p>
        </div>
        <div class="stat-card">
          <p class="stat-number">4주</p>
          <p class="stat-label">추천 훈련 기간</p>
        </div>
      </div>
      <div style="display:flex;flex-wrap:wrap;gap:10px;margin-top:20px;">
        <button class="btn light" data-route="training">체력훈련 보기</button>
        <button class="btn light" data-route="enlistment">입대 정보 보기</button>
      </div>
    </section>

  </main>

  <!-- 플로팅 홈 버튼 -->
  <button class="floating-back" id="floatingBack" data-route="home">
    <span data-icon="chevron-left"><svg width="16" height="16" viewBox="0 0 24 24" fill="none"><path d="m15 6-6 6 6 6" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path></svg></span> 홈으로
  </button>

  <script>
    /* ── 아이콘 ── */
    const iconPaths = {
      shield:'<svg width="20" height="20" viewBox="0 0 24 24" fill="none"><path d="M12 3 19 6v5c0 4.4-2.8 8.4-7 10-4.2-1.6-7-5.6-7-10V6l7-3Z" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"/><path d="m9.2 12.2 1.8 1.8 3.8-4" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"/></svg>',
      user:'<svg width="20" height="20" viewBox="0 0 24 24" fill="none"><circle cx="12" cy="8" r="4" stroke="currentColor" stroke-width="1.9"/><path d="M4 20a8 8 0 0 1 16 0" stroke="currentColor" stroke-width="1.9" stroke-linecap="round"/></svg>',
      bell:'<svg width="20" height="20" viewBox="0 0 24 24" fill="none"><path d="M18 9a6 6 0 0 0-12 0c0 7-3 7-3 9h18c0-2-3-2-3-9" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"/><path d="M10 21h4" stroke="currentColor" stroke-width="1.9" stroke-linecap="round"/></svg>',
      calendar:'<svg width="20" height="20" viewBox="0 0 24 24" fill="none"><rect x="3" y="5" width="18" height="16" rx="3" stroke="currentColor" stroke-width="1.9"/><path d="M8 3v4M16 3v4M3 10h18" stroke="currentColor" stroke-width="1.9" stroke-linecap="round"/></svg>',
      check:'<svg width="18" height="18" viewBox="0 0 24 24" fill="none"><circle cx="12" cy="12" r="9" stroke="currentColor" stroke-width="1.9"/><path d="m8.5 12.2 2.2 2.3 4.8-5.1" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"/></svg>',
      chevron:'<svg width="16" height="16" viewBox="0 0 24 24" fill="none"><path d="m9 6 6 6-6 6" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>',
      "chevron-left":'<svg width="16" height="16" viewBox="0 0 24 24" fill="none"><path d="m15 6-6 6 6 6" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>',
      external:'<svg width="16" height="16" viewBox="0 0 24 24" fill="none"><path d="M14 5h5v5M10 14 19 5M19 13v4a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h4" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"/></svg>',
      file:'<svg width="20" height="20" viewBox="0 0 24 24" fill="none"><path d="M7 3h7l5 5v13H7a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2Z" stroke="currentColor" stroke-width="1.9" stroke-linejoin="round"/><path d="M14 3v5h5M9 13h6M9 17h6" stroke="currentColor" stroke-width="1.9" stroke-linecap="round"/></svg>',
      home:'<svg width="20" height="20" viewBox="0 0 24 24" fill="none"><path d="m4 10.5 8-6.5 8 6.5V20a1 1 0 0 1-1 1h-5v-6H10v6H5a1 1 0 0 1-1-1v-9.5Z" stroke="currentColor" stroke-width="1.9" stroke-linejoin="round"/></svg>',
      info:'<svg width="20" height="20" viewBox="0 0 24 24" fill="none"><circle cx="12" cy="12" r="9" stroke="currentColor" stroke-width="1.9"/><path d="M12 11v5M12 8h.01" stroke="currentColor" stroke-width="1.9" stroke-linecap="round"/></svg>',
      menu:'<svg width="20" height="20" viewBox="0 0 24 24" fill="none"><path d="M4 7h16M4 12h16M4 17h16" stroke="currentColor" stroke-width="1.9" stroke-linecap="round"/></svg>',
      x:'<svg width="20" height="20" viewBox="0 0 24 24" fill="none"><path d="M6 6l12 12M18 6 6 18" stroke="currentColor" stroke-width="1.9" stroke-linecap="round"/></svg>',
      search:'<svg width="16" height="16" viewBox="0 0 24 24" fill="none"><circle cx="11" cy="11" r="6" stroke="currentColor" stroke-width="1.9"/><path d="m20 20-4.2-4.2" stroke="currentColor" stroke-width="1.9" stroke-linecap="round"/></svg>',
      sparkles:'<svg width="16" height="16" viewBox="0 0 24 24" fill="none"><path d="m12 3 1.5 4.5L18 9l-4.5 1.5L12 15l-1.5-4.5L6 9l4.5-1.5L12 3Z" stroke="currentColor" stroke-width="1.9" stroke-linejoin="round"/></svg>',
      activity:'<svg width="20" height="20" viewBox="0 0 24 24" fill="none"><path d="M4 13h4l2-7 4 14 2-7h4" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"/></svg>'
    };
    function renderIcons() {
      document.querySelectorAll("[data-icon]").forEach(el => {
        const n = el.getAttribute("data-icon");
        el.innerHTML = iconPaths[n] || iconPaths.info;
      });
    }

    /* ── 라우팅 ── */
    const routes = ["home","enlistment","training","policy","official","mypage","settings"];
    function routeTo(route, replace = false) {
      const next = routes.includes(route) ? route : "home";
      document.querySelectorAll(".page").forEach(p => p.classList.remove("active"));
      const page = document.getElementById("page-" + next);
      if (page) page.classList.add("active");
      document.querySelectorAll(".nav-btn[data-route]").forEach(btn =>
        btn.classList.toggle("active", btn.dataset.route === next)
      );
      document.getElementById("floatingBack").classList.toggle("show", next !== "home");
      document.getElementById("mobileNav").classList.remove("open");
      document.getElementById("mobileMenuButton").innerHTML = '<span data-icon="menu"></span>';
      if (next === "mypage") loadMyPage();
      renderIcons();
      if (replace) history.replaceState({route: next}, "", "#" + next);
      else history.pushState({route: next}, "", "#" + next);
      window.scrollTo({top: 0, behavior: "smooth"});
    }

    /* ── 체크리스트 ── */
    const checklistItems = [
      "입영일자와 입영부대 확인",
      "입영통지서 출력 또는 모바일 확인",
      "신분증, 나라사랑카드 준비",
      "안경 착용자는 예비 안경 준비",
      "복용 중인 약·진단서 여부 확인",
      "휴대전화 반입 기준 확인",
      "4주 기초체력 루틴 시작"
    ];
    function renderChecklist() {
      const saved = JSON.parse(localStorage.getItem("militaryChecklist") || "[]");
      const box = document.getElementById("checklist");
      box.innerHTML = checklistItems.map((item, i) =>
        `<label class="check-item">
          <input type="checkbox" data-check-index="${i}" ${saved.includes(i) ? "checked" : ""}>
          <span>${i + 1}. ${item}</span>
        </label>`
      ).join("");
      box.querySelectorAll("input").forEach(input =>
        input.addEventListener("change", saveChecklist)
      );
      updateProgress();
    }
    function saveChecklist() {
      const checked = Array.from(document.querySelectorAll("[data-check-index]:checked"))
        .map(i => Number(i.dataset.checkIndex));
      localStorage.setItem("militaryChecklist", JSON.stringify(checked));
      updateProgress();
    }
    function updateProgress() {
      const checkedCount = document.querySelectorAll("[data-check-index]:checked").length;
      const percent = Math.round((checkedCount / checklistItems.length) * 100);
      document.getElementById("progressBar").style.width = percent + "%";
      document.getElementById("progressText").textContent =
        `${percent}% 완료 · ${checkedCount}/${checklistItems.length}개 체크`;
    }

    /* ── 업데이트 알림 ── */
    const updates = [
      {badge:"입영", badgeClass:"", title:"입영 전 준비물 체크", desc:"입영통지서, 신분증, 나라사랑카드, 휴대전화 및 일체형 충전기 등은 반드시 공식 안내에서 다시 확인하세요.", date:"상시 확인"},
      {badge:"변경", badgeClass:"orange", title:"병무청 증명사진 현장 촬영으로 변경", desc:"기존 인터넷 사진 등록 방식에서 병무청 현장 촬영 방식으로 변경되었습니다.", date:"2025년 5월"},
      {badge:"체력", badgeClass:"green", title:"군별 AI 트레이닝 플랜 제공", desc:"육군, 해군, 공군, 해병대별 체력검정 기준에 맞춘 AI 트레이닝 플랜을 확인할 수 있습니다.", date:"신규"},
      {badge:"정책", badgeClass:"violet", title:"군 정책 변경 알림", desc:"복무기간, 휴대전화 사용, 장병 복지, 급여는 변경될 수 있으므로 공지 기반으로 업데이트합니다.", date:"공지 기준"}
    ];
    function renderUpdates(keyword = "") {
      const q = keyword.trim().toLowerCase();
      const filtered = updates.filter(item =>
        `${item.badge} ${item.title} ${item.desc} ${item.date}`.toLowerCase().includes(q)
      );
      const list = document.getElementById("updateList");
      list.innerHTML = filtered.length
        ? filtered.map(item =>
            `<article class="update-card">
              <div class="update-top">
                <span class="badge ${item.badgeClass}">${item.badge}</span>
                <span class="date">${item.date}</span>
              </div>
              <h4 class="update-title">${item.title}</h4>
              <p class="update-desc">${item.desc}</p>
            </article>`
          ).join("")
        : `<div class="empty">검색 결과가 없습니다.</div>`;
    }

    /* ── 트레이닝 데이터 ── */
    const trainingData = {
      army: {
        name:"육군", headline:"3km 달리기와 근지구력 중심",
        intro:"육군은 오래 버티는 힘이 중요합니다. 달리기, 팔굽혀펴기, 코어를 균형 있게 준비하세요.",
        focus:[["3km 달리기","장거리 페이스 유지"],["팔굽혀펴기","정확한 자세와 반복"],["코어 지구력","플랭크와 복근 안정성"]],
        meters:[["심폐지구력",92],["상체 근지구력",82],["코어 안정성",78]],
        routine:[["1주차","2km 조깅 + 팔굽혀펴기 5세트 + 플랭크"],["2주차","200m 인터벌 6회 + 팔굽혀펴기 총 80회"],["3주차","3km 기록 측정 + 스쿼트/런지 + 코어"],["4주차","3km 페이스런 + 실전식 체력 테스트"]],
        plan: {pushup:32, situp:40, run:"14분 이내"}
      },
      navy: {
        name:"해군", headline:"유산소 + 수영 적응 + 전신 지구력",
        intro:"해군은 수영 능력이 중요할 수 있습니다. 물 적응과 어깨 안정성을 함께 준비하세요.",
        focus:[["달리기","기초 심폐지구력"],["수영 적응","호흡과 킥 연습"],["어깨 안정성","등 근육 보강"]],
        meters:[["심폐지구력",86],["수영 적응",88],["전신 지구력",80]],
        routine:[["1주차","조깅 20분 + 자유형 킥판 + 밴드 로우"],["2주차","달리기 인터벌 + 수영 25m 반복"],["3주차","수영 누적 200~400m + 코어"],["4주차","달리기 기록 측정 + 수영 호흡 안정"]],
        plan: {pushup:30, situp:38, run:"15분 이내"}
      },
      airforce: {
        name:"공군", headline:"꾸준한 유산소와 자세 안정성",
        intro:"공군 지원자는 꾸준한 컨디션 관리, 심폐지구력, 바른 자세를 유지하는 근지구력이 중요합니다.",
        focus:[["2km 러닝","안정적인 페이스"],["상체 근지구력","정확한 푸시업"],["자세 안정","플랭크와 버드독"]],
        meters:[["심폐지구력",84],["자세 안정성",86],["회복 관리",82]],
        routine:[["1주차","2km 편한 페이스 + 팔굽혀펴기"],["2주차","400m 인터벌 4회 + 코어"],["3주차","2km 기록 측정 + 등 운동"],["4주차","페이스런 + 실전식 체력 테스트"]],
        plan: {pushup:28, situp:35, run:"15분 30초 이내"}
      },
      marine: {
        name:"해병대", headline:"강한 근지구력과 고강도 적응",
        intro:"해병대는 달리기, 팔굽혀펴기, 코어, 전신 서킷을 꾸준히 준비하는 것이 좋습니다.",
        focus:[["달리기","페이스 유지와 스퍼트"],["팔굽혀펴기/복근","반복 수행 능력"],["전신 서킷","버피, 스쿼트, 런지"]],
        meters:[["심폐지구력",94],["근지구력",90],["고강도 적응",88]],
        routine:[["1주차","조깅 20분 + 전신 서킷 2라운드"],["2주차","언덕 달리기 + 팔굽혀펴기 누적 100회"],["3주차","3km 기록 측정 + 버피/스쿼트"],["4주차","실전식 테스트 + 약점 보완"]],
        plan: {pushup:40, situp:50, run:"13분 이내"}
      }
    };

    function renderTrainingPanels() {
      const wrap = document.getElementById("branchPanels");
      wrap.innerHTML = Object.entries(trainingData).map(([key, data]) => `
        <section class="branch-panel ${key === "army" ? "active" : ""}" data-branch-panel="${key}">
          <div class="training-layout">
            <article class="white-box">
              <p class="eyebrow">${data.name} Training</p>
              <h2 class="section-title">${data.headline}</h2>
              <p class="section-desc">${data.intro}</p>
              <div class="mini-list" style="margin-top:18px;">
                ${data.focus.map(([title, desc]) =>
                  `<div class="mini-item"><span data-icon="check"></span><span><strong>${title}</strong><br><small style="color:#64748b;font-weight:700;">${desc}</small></span></div>`
                ).join("")}
              </div>
            </article>
            <article class="meter-card">
              <p class="eyebrow">Focus Balance</p>
              <h3 class="card-title">${data.name} 준비 비중</h3>
              <p class="section-desc" style="margin-bottom:16px;">준비 방향을 시각화한 가이드입니다.</p>
              ${data.meters.map(([label, value]) =>
                `<div class="meter-title"><span>${label}</span><span>${value}%</span></div><div class="meter"><span style="--w:${value}%"></span></div>`
              ).join("")}
            </article>
          </div>
          <div class="section-head"><div><p class="eyebrow">4 Week Routine</p><h3 class="section-title">${data.name} 4주 준비 루틴</h3></div></div>
          <div class="routine-grid">
            ${data.routine.map(([week, text]) =>
              `<article class="routine-card"><span class="routine-day">${week}</span><h4>${text.split(" + ")[0]}</h4><p>${text}</p></article>`
            ).join("")}
          </div>
        </section>`
      ).join("");
      renderIcons();
    }

    /* ── AI 트레이닝 플랜 ── */
    function generateAIPlan() {
      const branch = document.getElementById("aiBranch").value;
      const period = document.getElementById("aiPeriod").value;
      const data = trainingData[branch];
      const plan = data.plan;

      const multiplier = period === "1" ? 0.7 : period === "3" ? 1.15 : period === "6" ? 1.3 : 1;
      const pushup = Math.round(plan.pushup * multiplier);
      const situp = Math.round(plan.situp * multiplier);

      document.getElementById("aiPlanTitle").textContent = `${data.name} 맞춤 트레이닝 플랜`;
      document.getElementById("aiPlanSub").textContent = `${period}개월 기준 · 주 5회 훈련`;
      document.getElementById("aiExercises").innerHTML = `
        <div class="exercise-item">
          <div class="ex-left"><h4>팔굽혀펴기</h4><p>실제 횟수를 입력하면 다음 플랜에 반영됩니다</p></div>
          <div class="ex-right"><div class="ex-target">${pushup}회</div><div class="ex-label">목표</div><input class="record-input" type="number" placeholder="실제" id="rec-pushup" /></div>
        </div>
        <div class="exercise-item">
          <div class="ex-left"><h4>윗몸일으키기</h4><p>실제 횟수를 입력하면 다음 플랜에 반영됩니다</p></div>
          <div class="ex-right"><div class="ex-target">${situp}회</div><div class="ex-label">목표</div><input class="record-input" type="number" placeholder="실제" id="rec-situp" /></div>
        </div>
        <div class="exercise-item">
          <div class="ex-left"><h4>3km 달리기</h4><p>실제 기록을 입력하면 다음 플랜에 반영됩니다</p></div>
          <div class="ex-right"><div class="ex-target">${plan.run}</div><div class="ex-label">목표</div><input class="record-input" type="number" placeholder="분" id="rec-run" /></div>
        </div>`;

      const box = document.getElementById("aiPlanResult");
      box.style.display = "block";
      box.scrollIntoView({behavior:"smooth", block:"nearest"});
    }

    function saveRecord() {
      const pushup = document.getElementById("rec-pushup")?.value;
      const situp = document.getElementById("rec-situp")?.value;
      const run = document.getElementById("rec-run")?.value;
      if (!pushup && !situp && !run) {
        alert("실제 횟수를 먼저 입력해주세요!");
        return;
      }
      const record = {date: new Date().toLocaleDateString("ko-KR"), pushup, situp, run};
      const records = JSON.parse(localStorage.getItem("trainingRecords") || "[]");
      records.push(record);
      localStorage.setItem("trainingRecords", JSON.stringify(records));
      alert(`기록이 저장되었습니다! 💪\n팔굽혀펴기: ${pushup || "-"}회 | 윗몸: ${situp || "-"}회 | 달리기: ${run || "-"}분`);
    }

    /* ── 입대 정보 탭 ── */
    function bindInfoTabs() {
      document.getElementById("infoTabs").addEventListener("click", e => {
        const tab = e.target.closest("[data-info]");
        if (!tab) return;
        document.querySelectorAll("#infoTabs .tab").forEach(t => t.classList.remove("active"));
        tab.classList.add("active");
        document.querySelectorAll(".info-panel").forEach(p => p.style.display = "none");
        const panel = document.getElementById("info-" + tab.dataset.info);
        if (panel) { panel.style.display = "block"; renderIcons(); }
      });
    }

    /* ── 설정 ── */
    function loadSettings() {
      const s = JSON.parse(localStorage.getItem("demoSettings") || '{"dark":false,"compact":false}');
      document.body.classList.toggle("body-dark", !!s.dark);
      document.body.classList.toggle("body-compact", !!s.compact);
      document.getElementById("darkToggle")?.classList.toggle("on", !!s.dark);
      document.getElementById("compactToggle")?.classList.toggle("on", !!s.compact);
    }
    function toggleSetting(key) {
      const s = JSON.parse(localStorage.getItem("demoSettings") || '{"dark":false,"compact":false}');
      s[key] = !s[key];
      localStorage.setItem("demoSettings", JSON.stringify(s));
      loadSettings();
    }

    /* ── 이벤트 바인딩 ── */
    function bindEvents() {
      document.addEventListener("click", e => {
        const routeEl = e.target.closest("[data-route]");
        if (routeEl && routeEl.dataset.route) {
          e.preventDefault();
          routeTo(routeEl.dataset.route);
        }
      });
      document.getElementById("mobileMenuButton").addEventListener("click", () => {
        const nav = document.getElementById("mobileNav");
        const open = nav.classList.toggle("open");
        document.getElementById("mobileMenuButton").innerHTML =
          `<span data-icon="${open ? "x" : "menu"}"></span>`;
        renderIcons();
      });
      document.getElementById("resetChecklist").addEventListener("click", () => {
        localStorage.removeItem("militaryChecklist");
        renderChecklist();
      });
      document.getElementById("updateSearch").addEventListener("input", e =>
        renderUpdates(e.target.value)
      );
      document.getElementById("branchTabs").addEventListener("click", e => {
        const tab = e.target.closest("[data-branch]");
        if (!tab) return;
        document.querySelectorAll("[data-branch]").forEach(b => b.classList.remove("active"));
        tab.classList.add("active");
        document.querySelectorAll("[data-branch-panel]").forEach(p =>
          p.classList.toggle("active", p.dataset.branchPanel === tab.dataset.branch)
        );
        renderIcons();
      });
      document.getElementById("darkToggle").addEventListener("click", () => toggleSetting("dark"));
      document.getElementById("compactToggle").addEventListener("click", () => toggleSetting("compact"));
      document.getElementById("resetSettings").addEventListener("click", () => {
        localStorage.removeItem("demoSettings");
        loadSettings();
      });
      document.getElementById("saveProfile").addEventListener("click", saveProfile);
      window.addEventListener("popstate", () =>
        routeTo(location.hash.replace("#", "") || "home", true)
      );
    }

    /* ── 슬라이드 배너 ── */
    let bannerIdx = 0;
    const bannerTotal = 4;
    let bannerTimer = null;
    function bannerGo(idx) {
      bannerIdx = (idx + bannerTotal) % bannerTotal;
      document.getElementById("bannerTrack").style.transform = `translateX(-${bannerIdx * 100}%)`;
      document.querySelectorAll(".banner-dot").forEach((d, i) =>
        d.classList.toggle("active", i === bannerIdx)
      );
    }
    function bannerNext() { bannerGo(bannerIdx + 1); resetBannerTimer(); }
    function bannerPrev() { bannerGo(bannerIdx - 1); resetBannerTimer(); }
    function resetBannerTimer() {
      if (bannerTimer) clearInterval(bannerTimer);
      bannerTimer = setInterval(() => bannerGo(bannerIdx + 1), 4500);
    }
    function initBanner() {
      const dotsWrap = document.getElementById("bannerDots");
      for (let i = 0; i < bannerTotal; i++) {
        const btn = document.createElement("button");
        btn.className = "banner-dot" + (i === 0 ? " active" : "");
        btn.onclick = () => { bannerGo(i); resetBannerTimer(); };
        dotsWrap.appendChild(btn);
      }
      resetBannerTimer();
    }

    /* ── 마이페이지 ── */
    const branchMonths = { army: 18, navy: 20, airforce: 21, marine: 18 };
    const branchNames = { army: "육군", navy: "해군", airforce: "공군", marine: "해병대" };

    function loadMyPage() {
      const p = JSON.parse(localStorage.getItem("myProfile") || "{}");
      if (p.name) document.getElementById("profileName").value = p.name;
      if (p.branch) document.getElementById("profileBranch").value = p.branch;
      if (p.enlistDate) document.getElementById("enlistDate").value = p.enlistDate;

      // 아바타 텍스트
      const avatarEl = document.getElementById("avatarText");
      if (avatarEl) avatarEl.textContent = p.name ? p.name.charAt(0) : "군";

      // 전역일 계산
      if (p.enlistDate && p.branch) {
        const enlist = new Date(p.enlistDate);
        const months = branchMonths[p.branch] || 18;
        const discharge = new Date(enlist);
        discharge.setMonth(discharge.getMonth() + months);
        // 전역일은 복무 만료일 다음날이므로 +1일
        discharge.setDate(discharge.getDate() + 1);

        const today = new Date();
        const msPerDay = 1000 * 60 * 60 * 24;
        const daysToEnlist = Math.ceil((enlist - today) / msPerDay);
        const daysToDischarge = Math.ceil((discharge - today) / msPerDay);

        const fmt = d => `${d.getFullYear()}년 ${d.getMonth()+1}월 ${d.getDate()}일`;
        const ddayEnlist = daysToEnlist > 0 ? `D-${daysToEnlist}` : daysToEnlist === 0 ? "D-Day" : "입대 완료";
        const ddayDischarge = daysToDischarge > 0 ? `D-${daysToDischarge}` : "전역 완료";

        document.getElementById("dday-result").innerHTML = `
          <div style="display:grid;gap:12px;">
            <div style="background:var(--blue-light);border:1px solid #bfdbfe;border-radius:16px;padding:18px;">
              <p style="color:#1d4ed8;font-size:12px;font-weight:900;margin:0 0 6px;letter-spacing:.04em;">📅 입대 예정일</p>
              <p style="margin:0;font-size:20px;font-weight:950;letter-spacing:-.03em;">${fmt(enlist)}</p>
              <p style="margin:4px 0 0;color:var(--blue);font-size:15px;font-weight:900;">${ddayEnlist}</p>
            </div>
            <div style="background:#f0fdf4;border:1px solid #a7f3d0;border-radius:16px;padding:18px;">
              <p style="color:#065f46;font-size:12px;font-weight:900;margin:0 0 6px;letter-spacing:.04em;">🎖️ 예상 전역일 (${branchNames[p.branch]} · ${months}개월)</p>
              <p style="margin:0;font-size:20px;font-weight:950;letter-spacing:-.03em;">${fmt(discharge)}</p>
              <p style="margin:4px 0 0;color:var(--green);font-size:15px;font-weight:900;">${ddayDischarge}</p>
            </div>
            <div style="background:#f8fafc;border:1px solid #e5e7eb;border-radius:16px;padding:16px;text-align:center;">
              <p style="margin:0;color:var(--muted);font-size:13px;font-weight:700;line-height:1.6;">총 복무기간 <strong style="color:var(--text);">${months}개월</strong> · 예상 전역까지 <strong style="color:var(--text);">${Math.max(0, daysToDischarge)}일</strong></p>
            </div>
          </div>`;

        // 스탯 업데이트
        if (document.getElementById("statBranch")) {
          document.getElementById("statBranch").textContent = branchNames[p.branch] || "—";
          document.getElementById("statDday").textContent = daysToEnlist > 0 ? `D-${daysToEnlist}` : daysToEnlist === 0 ? "오늘!" : "입대 완료";
        }
      }

      // 체크리스트 퍼센트
      const saved = JSON.parse(localStorage.getItem("militaryChecklist") || "[]");
      const pct = Math.round((saved.length / checklistItems.length) * 100);
      if (document.getElementById("statChecklist")) document.getElementById("statChecklist").textContent = pct + "%";
    }

    function saveProfile() {
      const name = document.getElementById("profileName").value.trim() || "입대 준비생";
      const branch = document.getElementById("profileBranch").value;
      const enlistDate = document.getElementById("enlistDate").value;
      localStorage.setItem("myProfile", JSON.stringify({name, branch, enlistDate}));
      const msg = document.getElementById("saveMsg");
      msg.style.display = "block";
      setTimeout(() => msg.style.display = "none", 2000);
      loadMyPage();
      renderIcons();
    }

    /* ── 초기화 ── */
    function init() {
      renderIcons();
      renderChecklist();
      renderUpdates();
      renderTrainingPanels();
      loadSettings();
      initBanner();
      bindEvents();
      bindInfoTabs();
      routeTo(location.hash.replace("#", "") || "home", true);
    }
    init();
  </script>


</body></html>
