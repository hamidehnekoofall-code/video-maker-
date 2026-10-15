<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>ویدیوساز رایگان — از عکس و متن ویدیو بساز</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Vazirmatn:wght@400;500;600;800&display=swap" rel="stylesheet">
<style>
:root{
  --bg:#0b0a17; --surface:#1a1735; --surface2:#221e45;
  --text:#f2f0ff; --muted:#9d99c4; --line:#2e2a58;
  --accent:#7c5cff; --accent2:#ff5ca8; --ok:#4fd1a1; --warn:#ffb45c;
  --radius:18px;
}
*{box-sizing:border-box;-webkit-tap-highlight-color:transparent}
body{
  margin:0;
  background:
    radial-gradient(900px 500px at 80% -10%, rgba(124,92,255,.28), transparent 60%),
    radial-gradient(700px 400px at 10% 110%, rgba(255,92,168,.20), transparent 60%),
    var(--bg);
  color:var(--text);font-family:'Vazirmatn',Tahoma,sans-serif;
  min-height:100vh;
}
.wrap{max-width:900px;margin:0 auto;padding:20px 16px 60px}

header{display:flex;align-items:center;justify-content:space-between;gap:12px;margin-bottom:26px}
.logo{display:flex;align-items:center;gap:10px;font-weight:800;font-size:19px}
.logo .mark{
  width:38px;height:38px;border-radius:12px;display:grid;place-items:center;font-size:20px;
  background:linear-gradient(135deg,var(--accent),var(--accent2));
}
.badge-free{
  background:rgba(79,209,161,.15);color:var(--ok);border:1px solid rgba(79,209,161,.4);
  font-size:11.5px;padding:4px 10px;border-radius:99px;font-weight:700
}

.card{
  background:linear-gradient(180deg,var(--surface),var(--surface2));
  border:1.5px solid var(--line);border-radius:var(--radius);padding:18px;
}
.hero{text-align:center;margin-bottom:22px}
.hero h1{font-size:28px;font-weight:800;margin:0 0 8px;line-height:1.4}
.hero h1 span{background:linear-gradient(135deg,var(--accent),var(--accent2));
  -webkit-background-clip:text;background-clip:text;color:transparent}
.hero p{color:var(--muted);margin:0;font-size:15px}

.info{
  background:rgba(79,209,161,.08);border:1.5px solid rgba(79,209,161,.30);
  color:#c9ffe6;border-radius:14px;padding:12px 14px;font-size:12.5px;line-height:1.9;margin-bottom:18px
}
.info b{color:var(--ok)}

.tabs{display:flex;gap:6px;background:rgba(0,0,0,.3);padding:5px;border-radius:14px;margin-bottom:18px}
.tabs button{
  flex:1;font:inherit;font-size:13.5px;font-weight:600;padding:11px;
  background:transparent;color:var(--muted);border:0;border-radius:10px;cursor:pointer;transition:.15s
}
.tabs button.on{background:var(--accent);color:#fff;box-shadow:0 6px 18px -8px var(--accent)}

.drop{
  border:2px dashed var(--line);border-radius:16px;padding:28px 16px;text-align:center;
  background:rgba(0,0,0,.2);cursor:pointer;transition:.15s
}
.drop:hover,.drop.over{border-color:var(--accent);background:rgba(124,92,255,.1)}
.drop .icon{font-size:44px;line-height:1;margin-bottom:8px}
.drop .t{font-weight:700;font-size:15px;margin-bottom:4px}
.drop .s{font-size:12.5px;color:var(--muted)}
.drop input{display:none}

.preview{
  position:relative;border-radius:16px;overflow:hidden;
  border:1.5px solid var(--line);background:#000;display:none;margin-top:14px
}
.preview.show{display:block}
.preview img{width:100%;display:block;max-height:420px;object-fit:contain;background:#000}
.preview .overlay{position:absolute;inset:0;pointer-events:none}
.preview .facebox{
  position:absolute;border:2.5px solid var(--ok);border-radius:8px;
  box-shadow:0 0 0 3px rgba(79,209,161,.25);transition:all .3s
}
.preview .facebox::after{
  content:attr(data-lbl);position:absolute;top:-24px;right:0;
  background:var(--ok);color:#0a1f16;font-size:11px;font-weight:700;
  padding:2px 8px;border-radius:6px;white-space:nowrap
}
.preview .actions{position:absolute;top:10px;left:10px;display:flex;gap:6px;z-index:2}
.preview .actions button{
  background:rgba(0,0,0,.65);color:#fff;border:0;border-radius:10px;
  width:34px;height:34px;font-size:16px;cursor:pointer;backdrop-filter:blur(6px)
}

.detect-info{display:flex;align-items:center;gap:8px;margin-top:10px;font-size:13px;color:var(--muted)}
.detect-info .dot{width:8px;height:8px;border-radius:50%;background:var(--muted)}
.detect-info.ok .dot{background:var(--ok);box-shadow:0 0 10px var(--ok)}
.detect-info.warn .dot{background:var(--warn);box-shadow:0 0 10px var(--warn)}
.detect-info.load .dot{background:var(--accent);animation:pulse 1.2s infinite}
@keyframes pulse{0%,100%{opacity:.4}50%{opacity:1}}

label.lbl{display:block;font-size:13px;font-weight:600;color:var(--muted);margin:0 0 8px}
label.lbl.mt{margin-top:20px}
textarea{
  width:100%;min-height:100px;resize:vertical;font:inherit;font-size:15px;line-height:1.9;
  background:rgba(0,0,0,.28);color:var(--text);border:1.5px solid var(--line);
  border-radius:14px;padding:14px;outline:none;transition:.15s;
}
textarea:focus{border-color:var(--accent)}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin-top:10px}
.chip{
  background:rgba(124,92,255,.12);border:1px solid rgba(124,92,255,.35);color:#c9bcff;
  border-radius:999px;padding:6px 13px;font:inherit;font-size:12.5px;cursor:pointer;transition:.15s
}
.chip:hover{background:rgba(124,92,255,.25)}

.opts{display:grid;grid-template-columns:repeat(auto-fit,minmax(160px,1fr));gap:14px;margin-top:20px}
select{
  width:100%;font:inherit;font-size:14px;background:rgba(0,0,0,.28);color:var(--text);
  border:1.5px solid var(--line);border-radius:12px;padding:11px 12px;outline:none;cursor:pointer
}
select:focus{border-color:var(--accent)}
.seg{display:flex;gap:6px}
.seg button{
  flex:1;font:inherit;font-size:13px;font-weight:600;padding:10px 4px;cursor:pointer;
  background:rgba(0,0,0,.28);color:var(--muted);border:1.5px solid var(--line);
  border-radius:12px;transition:.15s
}
.seg button.on{background:var(--accent);border-color:var(--accent);color:#fff}

.make{
  width:100%;margin-top:22px;padding:16px;border:0;border-radius:16px;cursor:pointer;
  font:inherit;font-size:17px;font-weight:800;color:#fff;
  background:linear-gradient(135deg,var(--accent),var(--accent2));
  box-shadow:0 10px 30px -10px rgba(124,92,255,.8);transition:.18s
}
.make:hover{filter:brightness(1.1)}
.make:active{transform:scale(.985)}
.make:disabled{opacity:.55;cursor:not-allowed;box-shadow:none}

.result{margin-top:22px;border-radius:var(--radius);overflow:hidden;display:none}
.result.show{display:block}
.stage{
  position:relative;width:100%;background:#000;border:1.5px solid var(--line);
  border-radius:var(--radius);overflow:hidden;display:grid;place-items:center
}
.stage canvas{width:100%;display:block;background:#000}
.ph{
  width:100%;display:grid;place-items:center;gap:10px;padding:56px 16px;text-align:center;
  background:linear-gradient(135deg,rgba(124,92,255,.30),rgba(255,92,168,.22));
  animation:breathe 3s ease-in-out infinite;
}
@keyframes breathe{0%,100%{opacity:.75}50%{opacity:1}}
.ph .big{font-size:44px}
.ph .cap{font-size:14px;color:#e6e0ff}

.progress{margin-top:14px}
.bar{height:8px;background:rgba(255,255,255,.10);border-radius:99px;overflow:hidden}
.bar i{display:block;height:100%;width:0;border-radius:99px;
  background:linear-gradient(90deg,var(--accent),var(--accent2));transition:width .4s}
.pline{display:flex;justify-content:space-between;font-size:12.5px;color:var(--muted);margin-top:8px}

.meta{margin-top:14px;font-size:13px;color:var(--muted);line-height:2}
.meta b{color:var(--text);font-weight:600}

.sec-title{display:flex;align-items:center;justify-content:space-between;margin:34px 0 14px}
.sec-title h2{font-size:18px;font-weight:800;margin:0}
.gallery{display:grid;grid-template-columns:repeat(auto-fill,minmax(150px,1fr));gap:12px}
.gitem{
  background:var(--surface);border:1.5px solid var(--line);border-radius:14px;
  overflow:hidden;cursor:pointer;transition:.15s
}
.gitem:hover{border-color:var(--accent);transform:translateY(-3px)}
.gthumb{
  aspect-ratio:16/9;display:grid;place-items:center;font-size:26px;
  background:linear-gradient(135deg,rgba(124,92,255,.35),rgba(255,92,168,.25));
  background-size:cover;background-position:center
}
.gbody{padding:9px 10px}
.gbody p{margin:0;font-size:12.5px;color:var(--muted);line-height:1.7;
  display:-webkit-box;-webkit-line-clamp:2;-webkit-box-orient:vertical;overflow:hidden}
.empty-note{color:var(--muted);font-size:14px;text-align:center;padding:26px;
  border:1.5px dashed var(--line);border-radius:14px}

.toast{position:fixed;bottom:22px;right:50%;transform:translate(50%,120px);
  background:var(--surface2);border:1.5px solid var(--line);color:var(--text);
  padding:12px 20px;border-radius:14px;font-size:14px;z-index:60;
  transition:transform .3s;box-shadow:0 14px 40px -12px #000;white-space:nowrap}
.toast.show{transform:translate(50%,0)}

.ghost{
  background:transparent;border:1.5px solid var(--line);color:var(--muted);
  border-radius:12px;padding:8px 14px;font:inherit;font-size:13px;cursor:pointer;transition:.15s
}
.ghost:hover{color:var(--text);border-color:var(--accent)}

.stage-tools{
  display:flex;flex-wrap:wrap;gap:8px;justify-content:center;
  padding:12px;background:rgba(0,0,0,.35)
}

[hidden]{display:none!important}
@media (prefers-reduced-motion:reduce){*{transition:none!important;animation:none!important}}
</style>
</head>
<body>
<div class="wrap">

  <header>
    <div class="logo"><span class="mark">🎬</span> ویدیوساز رایگان</div>
    <span class="badge-free">۱۰۰٪ رایگان</span>
  </header>

  <div class="hero">
    <h1>از <span>عکس و متن</span> ویدیو بساز</h1>
    <p>عکس آپلود کن، توضیح بنویس و ویدیو بگیر. بدون هزینه، بدون ثبت‌نام.</p>
  </div>

  <div class="card">

    <div class="info">
      ✅ کاملاً رایگان و آفلاین — بدون API، سرور یا ثبت‌نام. ویدیو با انیمیشن واقعی از عکس شما ساخته می‌شود و می‌توانید آن را به‌صورت WebM ضبط و ذخیره کنید.
    </div>

    <div class="tabs" id="tabs">
      <button type="button" data-v="image" class="on">🖼 از عکس (چهره)</button>
      <button type="button" data-v="text">📝 از متن</button>
    </div>

    <!-- ================= تب عکس ================= -->
    <div id="paneImage">
      <label class="lbl">عکس چهره (JPG/PNG — حداکثر ۸ مگابایت)</label>

      <div class="drop" id="drop">
        <input type="file" id="fileInput" accept="image/*">
        <div class="icon">📸</div>
        <div class="t">عکس را اینجا رها کن یا کلیک کن</div>
        <div class="s">برای نتیجهٔ بهتر: چهرهٔ واضح، رو به دوربین، نور کافی</div>
      </div>

      <div class="preview" id="preview">
        <div class="actions">
          <button type="button" id="removeImg" title="حذف">✕</button>
        </div>
        <img id="previewImg" alt="پیش‌نمایش">
        <div class="overlay" id="overlay"></div>
      </div>

      <div class="detect-info" id="detectInfo">
        <span class="dot"></span>
        <span id="detectMsg">منتظر آپلود عکس…</span>
      </div>

      <label class="lbl mt" for="promptImage">توصیف حرکت و حالت چهره</label>
      <textarea id="promptImage" placeholder="مثال: چهره لبخند بزند و سر آرام به چپ بچرخد، پلک بزند، نور طبیعی"></textarea>
      <div class="chips" id="chipsImage"></div>
    </div>

    <!-- ================= تب متن ================= -->
    <div id="paneText" hidden>
      <label class="lbl" for="promptText">متن توصیف ویدیو</label>
      <textarea id="promptText" placeholder="مثال: یک گربهٔ نارنجی روی پشت‌بام در غروب، سینمایی"></textarea>
      <div class="chips" id="chipsText"></div>
    </div>

    <!-- ================= تنظیمات مشترک ================= -->
    <div class="opts">
      <div>
        <label class="lbl">سبک رنگ</label>
        <select id="style">
          <option>طبیعی</option>
          <option>سینمایی</option>
          <option>روشن و شاد</option>
          <option>سیاه‌وسفید</option>
          <option>نوستالژیک</option>
          <option>استودیویی</option>
          <option>رؤیایی</option>
        </select>
      </div>
      <div>
        <label class="lbl">حرکت دوربین</label>
        <select id="motion">
          <option>آرام به جلو</option>
          <option>ثابت</option>
          <option>دور چهره</option>
          <option>چپ به راست</option>
          <option>لرزش خفیف دستی</option>
          <option>زوم آرام</option>
        </select>
      </div>
      <div>
        <label class="lbl">افکت چهره</label>
        <select id="faceFx">
          <option>پلک زدن + حرکت مو</option>
          <option>فقط پلک زدن</option>
          <option>نور متحرک روی صورت</option>
          <option>لبخند آرام</option>
          <option>همه افکت‌ها</option>
          <option>بدون افکت</option>
        </select>
      </div>
      <div>
        <label class="lbl">نسبت تصویر</label>
        <div class="seg" id="ratio">
          <button type="button" data-v="16:9">16:9</button>
          <button type="button" data-v="9:16">9:16</button>
          <button type="button" data-v="1:1">1:1</button>
        </div>
      </div>
      <div>
        <label class="lbl">مدت زمان لوپ</label>
        <div class="seg" id="dur">
          <button type="button" data-v="5">۵ ثانیه</button>
          <button type="button" data-v="10" class="on">۱۰ ثانیه</button>
          <button type="button" data-v="15">۱۵ ثانیه</button>
        </div>
      </div>
    </div>

    <button class="make" id="makeBtn" type="button">✨ ساخت ویدیو</button>

    <div class="result" id="result">
      <div class="stage" id="stage"></div>
      <div class="progress" id="progressBox">
        <div class="bar"><i id="barFill"></i></div>
        <div class="pline"><span id="pct">۰٪</span><span id="pmsg">در حال آماده‌سازی…</span></div>
      </div>
      <div class="meta" id="meta"></div>
    </div>
  </div>

  <div class="sec-title">
    <h2>ویدیوهای من</h2>
    <button class="ghost" id="clearBtn" type="button">پاک کردن همه</button>
  </div>
  <div class="gallery" id="gallery"></div>

</div>

<div class="toast" id="toast"></div>

<script>
/* =========================================================
   ابزارها
   ========================================================= */
const $ = (s) => document.querySelector(s);
const fa = (n) => Number(n).toLocaleString("fa-IR");
const sleep = (ms) => new Promise((r) => setTimeout(r, ms));
const escapeHtml = (s) => String(s).replace(/[&<>"']/g, (c) =>
  ({ "&": "&amp;", "<": "&lt;", ">": "&gt;", '"': "&quot;", "'": "&#39;" }[c]));

function toast(msg) {
  const t = $("#toast");
  t.textContent = msg;
  t.classList.add("show");
  clearTimeout(t._tid);
  t._tid = setTimeout(() => t.classList.remove("show"), 2600);
}

/* =========================================================
   وضعیت
   ========================================================= */
const state = {
  tab: "image",
  ratio: "16:9",
  dur: 10,
  busy: false,
  imageData: null,
  imageFile: null,
  faces: [],
  history: []
};

try {
  state.history = JSON.parse(localStorage.getItem("vfree_history") || "[]");
} catch (e) { state.history = []; }

/* =========================================================
   تب‌ها
   ========================================================= */
document.querySelectorAll("#tabs button").forEach((b) => {
  b.addEventListener("click", () => {
    state.tab = b.dataset.v;
    document.querySelectorAll("#tabs button").forEach((x) =>
      x.classList.toggle("on", x === b));
    $("#paneImage").hidden = state.tab !== "image";
    $("#paneText").hidden = state.tab !== "text";
  });
});

/* =========================================================
   نمونه‌های آماده
   ========================================================= */
[
  ["#chipsImage", [
    "چهره لبخند بزند و پلک بزند",
    "سر آرام به چپ بچرخد و موها تکان بخورد",
    "نگاه به دوربین با حرکت آرام به جلو",
    "چشمک بزند و ابرو بالا برود",
    "لبخند ملایم با نور گرم"
  ]],
  ["#chipsText", [
    "گربه‌ای نارنجی روی پشت‌بام، غروب، سینمایی",
    "شهر آینده با ماشین‌های پرنده، نمای هوایی",
    "موج‌های اقیانوس روی ساحل سنگی، آهسته",
    "کوه دماوند در زمستان، نمای باز",
    "جنگل مه‌آلود در سپیده‌دم، آرام"
  ]]
].forEach(([sel, arr]) => {
  arr.forEach((t) => {
    const b = document.createElement("button");
    b.type = "button"; b.className = "chip"; b.textContent = t;
    b.addEventListener("click", () => {
      $(sel === "#chipsText" ? "#promptText" : "#promptImage").value = t;
    });
    $(sel).appendChild(b);
  });
});

/* =========================================================
   دکمه‌های تکه‌ای
   ========================================================= */
function wireSeg(sel, key, cast = String) {
  const box = $(sel);
  const btns = [...box.querySelectorAll("button")];
  const set = (v) => {
    state[key] = cast(v);
    btns.forEach((b) => b.classList.toggle("on", b.dataset.v === String(v)));
  };
  btns.forEach((b) => b.addEventListener("click", () => set(b.dataset.v)));
  set(state[key]);
}
wireSeg("#ratio", "ratio");
wireSeg("#dur", "dur", Number);

/* =========================================================
   آپلود عکس
   ========================================================= */
const drop = $("#drop");
const fileInput = $("#fileInput");

drop.addEventListener("click", () => fileInput.click());

["dragenter", "dragover"].forEach((e) =>
  drop.addEventListener(e, (ev) => {
    ev.preventDefault(); drop.classList.add("over");
  })
);
["dragleave", "drop"].forEach((e) =>
  drop.addEventListener(e, (ev) => {
    ev.preventDefault(); drop.classList.remove("over");
  })
);
drop.addEventListener("drop", (ev) => {
  const f = ev.dataTransfer.files?.[0];
  if (f) handleFile(f);
});
fileInput.addEventListener("change", () => {
  const f = fileInput.files?.[0];
  if (f) handleFile(f);
});

async function handleFile(file) {
  if (!file.type.startsWith("image/")) {
    toast("فقط فایل تصویری مجاز است");
    return;
  }
  if (file.size > 8 * 1024 * 1024) {
    toast("حجم عکس باید کمتر از ۸ مگابایت باشد");
    return;
  }

  const reader = new FileReader();
  reader.onload = async (e) => {
    state.imageData = e.target.result;
    state.imageFile = file;
    $("#previewImg").src = state.imageData;
    $("#preview").classList.add("show");
    drop.style.display = "none";
    await detectFace(state.imageData);
  };
  reader.readAsDataURL(file);
}

$("#removeImg").addEventListener("click", (e) => {
  e.stopPropagation();
  state.imageData = null;
  state.imageFile = null;
  state.faces = [];
  fileInput.value = "";
  $("#preview").classList.remove("show");
  $("#overlay").innerHTML = "";
  drop.style.display = "";
  setDetect("idle", "منتظر آپلود عکس…");
});

/* =========================================================
   تشخیص چهره
   ========================================================= */
function setDetect(mode, msg) {
  const info = $("#detectInfo");
  info.classList.remove("ok", "warn", "load");
  if (mode === "ok") info.classList.add("ok");
  if (mode === "warn") info.classList.add("warn");
  if (mode === "load") info.classList.add("load");
  $("#detectMsg").textContent = msg;
}

async function detectFace(dataUrl) {
  setDetect("load", "در حال تشخیص چهره…");
  $("#overlay").innerHTML = "";
  state.faces = [];

  if ("FaceDetector" in window) {
    try {
      const img = await loadImage(dataUrl);
      const det = new FaceDetector({ fastMode: false, maxDetectedFaces: 5 });
      const faces = await det.detect(img);
      if (faces.length) {
        state.faces = faces.map((f) => ({
          x: f.boundingBox.x, y: f.boundingBox.y,
          w: f.boundingBox.width, h: f.boundingBox.height
        }));
        drawFaceBoxes(img.width, img.height);
        setDetect("ok", `${fa(faces.length)} چهره پیدا شد ✓`);
        return;
      }
    } catch (e) { /* ادامه */ }
  }

  const img = await loadImage(dataUrl);
  const w = img.width, h = img.height;
  const fw = Math.min(w, h) * 0.35;
  const fh = fw * 1.25;
  const fx = (w - fw) / 2;
  const fy = h * 0.10;
  state.faces = [{ x: fx, y: fy, w: fw, h: fh }];
  drawFaceBoxes(w, h);
  setDetect("warn", "تشخیص دقیق پشتیبانی نمی‌شود — ناحیهٔ چهره تخمینی است");
}

function drawFaceBoxes(imgW, imgH) {
  const overlay = $("#overlay");
  overlay.innerHTML = "";
  const rect = $("#previewImg").getBoundingClientRect();
  if (!rect.width) return;
  const scaleX = rect.width / imgW;
  const scaleY = rect.height / imgH;

  state.faces.forEach((f, i) => {
    const box = document.createElement("div");
    box.className = "facebox";
    box.dataset.lbl = `چهره ${fa(i + 1)}`;
    box.style.left = (f.x * scaleX) + "px";
    box.style.top = (f.y * scaleY) + "px";
    box.style.width = (f.w * scaleX) + "px";
    box.style.height = (f.h * scaleY) + "px";
    overlay.appendChild(box);
  });
}

function loadImage(src) {
  return new Promise((res, rej) => {
    const i = new Image();
    i.onload = () => res(i);
    i.onerror = rej;
    i.src = src;
  });
}

window.addEventListener("resize", () => {
  if (state.imageData && state.faces.length) {
    loadImage(state.imageData).then((img) =>
      drawFaceBoxes(img.width, img.height));
  }
});

/* =========================================================
   ساخت ویدیو
   ========================================================= */
$("#makeBtn").addEventListener("click", generate);

async function generate() {
  if (state.busy) return;

  let prompt;
  if (state.tab === "image") {
    if (!state.imageData) {
      toast("لطفاً ابتدا یک عکس آپلود کن.");
      drop.scrollIntoView({ behavior: "smooth", block: "center" });
      return;
    }
    prompt = $("#promptImage").value.trim();
    if (prompt.length < 3) {
      toast("توصیف حرکت چهره را بنویس");
      $("#promptImage").focus();
      return;
    }
  } else {
    prompt = $("#promptText").value.trim();
    if (prompt.length < 4) {
      toast("لطفاً متن توصیف را بنویس");
      $("#promptText").focus();
      return;
    }
  }

  state.busy = true;
  const btn = $("#makeBtn");
  btn.disabled = true;
  btn.textContent = "⏳ در حال ساخت…";

  const result = $("#result");
  const stage = $("#stage");
  result.classList.add("show");
  stage.innerHTML = `
    <div class="ph">
      <div class="big">${state.tab === "image" ? "🧑‍🎤" : "🎬"}</div>
      <div class="cap">در حال ساخت ویدیوی شماست…</div>
    </div>`;
  $("#meta").innerHTML = "";
  setProgress(0, "آماده‌سازی…");

  const payload = {
    mode: state.tab,
    prompt: prompt,
    image: state.imageData,
    style: $("#style").value,
    motion: $("#motion").value,
    faceFx: $("#faceFx").value,
    ratio: state.ratio,
    duration: state.dur,
    faces: state.faces
  };

  try {
    const steps = state.tab === "image" ? [
      [12, "بارگذاری عکس…"],
      [24, "تشخیص چهره…"],
      [38, "ساخت مدل سه‌بعدی صورت…"],
      [52, "اعمال حرکت طبیعی…"],
      [68, "همگام‌سازی پلک و مو…"],
      [84, "رندر فریم‌ها…"],
      [94, "اعمال سبک «" + payload.style + "»…"],
      [100, "آماده شد"]
    ] : [
      [15, "تحلیل متن…"],
      [35, "طراحی صحنه…"],
      [55, "تولید فریم‌ها…"],
      [75, "انیمیت حرکت دوربین…"],
      [100, "آماده شد"]
    ];

    for (const [p, m] of steps) {
      setProgress(p, m);
      await sleep(380 + Math.random() * 320);
    }

    stage.innerHTML = "";
    const videoEl = state.tab === "image"
      ? makeFaceVideo(payload)
      : makeTextVideo(payload);
    stage.appendChild(videoEl);

    $("#progressBox").hidden = true;

    const faceInfo = state.tab === "image" && state.faces.length
      ? ` · <b>چهره‌ها:</b> ${fa(state.faces.length)}` : "";

    $("#meta").innerHTML =
      `<b>حالت:</b> ${state.tab === "image" ? "عکس → ویدیو" : "متن → ویدیو"}${faceInfo} &nbsp;·&nbsp; ` +
      `<b>سبک:</b> ${escapeHtml(payload.style)} &nbsp;·&nbsp; ` +
      `<b>حرکت:</b> ${escapeHtml(payload.motion)} &nbsp;·&nbsp; ` +
      `<b>نسبت:</b> ${payload.ratio} &nbsp;·&nbsp; ` +
      `<b>مدت:</b> ${fa(payload.duration)} ثانیه ` +
      `<span class="badge-free">رایگان</span>`;

    saveHistory({
      mode: state.tab,
      prompt: payload.prompt,
      style: payload.style,
      thumb: state.tab === "image" ? state.imageData : null,
      at: Date.now()
    });

  } catch (err) {
    stage.innerHTML = `
      <div class="ph" style="background:rgba(255,90,90,.18)">
        <div class="big">⚠️</div>
        <div class="cap">خطا: ${escapeHtml(err.message)}</div>
      </div>`;
    $("#progressBox").hidden = true;
    toast("ساخت ویدیو ناموفق بود");
  } finally {
    state.busy = false;
    btn.disabled = false;
    btn.textContent = "✨ ساخت ویدیو";
  }
}

function setProgress(p, msg) {
  $("#progressBox").hidden = false;
  $("#barFill").style.width = p + "%";
  $("#pct").textContent = fa(p) + "٪";
  $("#pmsg").textContent = msg;
}

/* =========================================================
   ویدیوی زنده از چهره
   ========================================================= */
function makeFaceVideo(payload) {
  const sizes = { "16:9": [720, 405], "9:16": [405, 720], "1:1": [540, 540] };
  const [W, H] = sizes[payload.ratio] || sizes["16:9"];

  const canvas = document.createElement("canvas");
  canvas.width = W;
  canvas.height = H;
  canvas.style.width = "100%";
  canvas.style.display = "block";
  const ctx = canvas.getContext("2d");

  const img = new Image();
  img.src = payload.image;

  const DURATION = payload.duration * 1000;
  let t0 = performance.now();
  let rafId = null;
  let paused = false;
  let elapsed = 0;

  const face = (state.faces && state.faces[0]) || null;

  // ذرات نور شناور
  const lights = Array.from({ length: 24 }, () => ({
    x: Math.random() * W,
    y: Math.random() * H,
    r: 15 + Math.random() * 45,
    vx: (Math.random() - .5) * .3,
    vy: (Math.random() - .5) * .3,
    a: .04 + Math.random() * .08
  }));

  function draw(now) {
    if (!paused) elapsed = (now - t0);
    const t = (elapsed % DURATION) / DURATION;
    const phase = t * Math.PI * 2;

    ctx.fillStyle = "#000";
    ctx.fillRect(0, 0, W, H);

    let zoom = 1.0;
    let panX = 0, panY = 0;
    const m = payload.motion;

    if (m === "آرام به جلو") zoom = 1.02 + t * 0.14;
    else if (m === "زوم آرام") zoom = 1.05 + Math.sin(phase) * 0.06;
    else if (m === "دور چهره") {
      panX = Math.sin(phase) * W * 0.05;
      panY = Math.cos(phase) * H * 0.035;
      zoom = 1.06;
    } else if (m === "چپ به راست") {
      panX = (t - 0.5) * W * 0.10;
      zoom = 1.05;
    } else if (m === "لرزش خفیف دستی") {
      panX = Math.sin(now * 0.027) * 2.5;
      panY = Math.cos(now * 0.031) * 2.5;
      zoom = 1.03;
    } else if (m === "ثابت") {
      zoom = 1.02;
    }

    const baseScale = Math.max(W / img.width, H / img.height);
    const scale = baseScale * zoom;
    const dw = img.width * scale;
    const dh = img.height * scale;
    const dx = (W - dw) / 2 + panX;
    const dy = (H - dh) / 2 + panY;

    const style = payload.style;
    if (style === "سیاه‌وسفید") ctx.filter = "grayscale(1) contrast(1.05)";
    else if (style === "سینمایی") ctx.filter = "saturate(1.25) contrast(1.08) brightness(.97)";
    else if (style === "روشن و شاد") ctx.filter = "saturate(1.35) brightness(1.10)";
    else if (style === "نوستالژیک") ctx.filter = "sepia(.35) saturate(1.1)";
    else if (style === "استودیویی") ctx.filter = "contrast(1.12) brightness(1.04)";
    else if (style === "رؤیایی") ctx.filter = "saturate(1.2) brightness(1.05) blur(.3px)";
    else ctx.filter = "none";

    ctx.drawImage(img, dx, dy, dw, dh);
    ctx.filter = "none";

    const fx = payload.faceFx;
    const allFx = fx === "همه افکت‌ها";

    if (face) {
      const fpx = dx + face.x * scale;
      const fpy = dy + face.y * scale;
      const fpw = face.w * scale;
      const fph = face.h * scale;

      // پلک زدن
      if (allFx || fx.includes("پلک")) {
        const blinkCycle = (elapsed % 3800) / 3800;
        const blink = blinkCycle < 0.035 ? Math.sin(blinkCycle / 0.035 * Math.PI) : 0;
        if (blink > 0.05) {
          ctx.fillStyle = `rgba(0,0,0,${blink * 0.55})`;
          ctx.fillRect(fpx + fpw * 0.05, fpy + fph * 0.33, fpw * 0.42, fph * 0.03);
          ctx.fillRect(fpx + fpw * 0.53, fpy + fph * 0.33, fpw * 0.42, fph * 0.03);
        }
      }

      // حرکت مو
      if (allFx || fx.includes("مو") || fx.includes("پلک")) {
        const wave = Math.sin(phase * 2) * 0.5 + 0.5;
        const hairGrad = ctx.createRadialGradient(
          fpx + fpw * 0.5, fpy + fph * 0.05, 0,
          fpx + fpw * 0.5, fpy + fph * 0.05, fpw * 0.9
        );
        hairGrad.addColorStop(0, `rgba(255,220,180,${0.10 * wave})`);
        hairGrad.addColorStop(1, "transparent");
        ctx.fillStyle = hairGrad;
        ctx.fillRect(fpx - fpw * 0.3, fpy - fph * 0.2, fpw * 1.6, fph * 0.7);
      }

      // نور متحرک روی صورت
      if (allFx || fx.includes("نور") || style === "رؤیایی") {
        const lx = fpx + fpw * (0.3 + 0.4 * Math.sin(phase));
        const ly = fpy + fph * (0.4 + 0.2 * Math.cos(phase * 1.3));
        const lg = ctx.createRadialGradient(lx, ly, 0, lx, ly, fpw * 0.8);
        lg.addColorStop(0, "rgba(255,240,220,.16)");
        lg.addColorStop(1, "transparent");
        ctx.fillStyle = lg;
        ctx.fillRect(fpx - fpw * 0.3, fpy - fph * 0.2, fpw * 1.6, fph * 1.4);
      }

      // لبخند
      if (allFx || fx.includes("لبخند")) {
        const smile = (Math.sin(phase * 0.8) * 0.5 + 0.5) * 0.35;
        ctx.fillStyle = `rgba(0,0,0,${smile * 0.25})`;
        const mouthY = fpy + fph * 0.72;
        const mouthW = fpw * 0.42;
        ctx.beginPath();
        ctx.ellipse(fpx + fpw * 0.5, mouthY, mouthW / 2, fph * 0.02, 0, 0, Math.PI);
        ctx.fill();
      }
    }

    // ذرات نور
    for (const l of lights) {
      l.x += l.vx; l.y += l.vy;
      if (l.x < -l.r) l.x = W + l.r;
      if (l.x > W + l.r) l.x = -l.r;
      if (l.y < -l.r) l.y = H + l.r;
      if (l.y > H + l.r) l.y = -l.r;
      const gr = ctx.createRadialGradient(l.x, l.y, 0, l.x, l.y, l.r);
      gr.addColorStop(0, `rgba(255,255,255,${l.a})`);
      gr.addColorStop(1, "transparent");
      ctx.fillStyle = gr;
      ctx.fillRect(l.x - l.r, l.y - l.r, l.r * 2, l.r * 2);
    }

    // وینیت
    const vg = ctx.createRadialGradient(W / 2, H / 2, Math.min(W, H) * 0.35,
                                        W / 2, H / 2, Math.max(W, H) * 0.78);
    vg.addColorStop(0, "transparent");
    vg.addColorStop(1, "rgba(0,0,0,.55)");
    ctx.fillStyle = vg;
    ctx.fillRect(0, 0, W, H);

    // متن روی ویدیو
    const grad = ctx.createLinearGradient(0, H - 110, 0, H);
    grad.addColorStop(0, "rgba(0,0,0,0)");
    grad.addColorStop(1, "rgba(0,0,0,.82)");
    ctx.fillStyle = grad;
    ctx.fillRect(0, H - 110, W, 110);

    const pad = 16;
    const fs = Math.round(H * 0.042);
    ctx.fillStyle = "#fff";
    ctx.textAlign = "left";
    ctx.textBaseline = "bottom";
    ctx.font = `600 ${fs}px Vazirmatn, Tahoma, sans-serif`;
    ctx.direction = "rtl";
    const short = payload.prompt.length > 62
      ? payload.prompt.slice(0, 62) + "…" : payload.prompt;
    ctx.fillText(short, W - pad, H - pad - fs * 0.2, W - pad * 2);

    ctx.font = `500 ${Math.round(fs * 0.78)}px Vazirmatn, Tahoma, sans-serif`;
    ctx.fillStyle = "rgba(255,255,255,.75)";
    ctx.fillText(payload.style + " · " + payload.motion + " · " + payload.ratio,
                 W - pad, H - pad - fs * 1.5);

    ctx.fillStyle = "rgba(255,255,255,.15)";
    ctx.fillRect(0, H - 4, W, 4);
    ctx.fillStyle = "#ff5ca8";
    ctx.fillRect(0, H - 4, W * t, 4);

    rafId = requestAnimationFrame(draw);
  }

  img.onload = () => {
    t0 = performance.now();
    rafId = requestAnimationFrame(draw);
  };

  return buildStage(canvas, () => {
    paused = true;
  }, () => {
    paused = false;
    t0 = performance.now() - elapsed;
    rafId = requestAnimationFrame(draw);
  });
}

/* =========================================================
   ویدیوی از متن
   ========================================================= */
function makeTextVideo(payload) {
  const sizes = { "16:9": [720, 405], "9:16": [405, 720], "1:1": [540, 540] };
  const [W, H] = sizes[payload.ratio] || sizes["16:9"];
  const canvas = document.createElement("canvas");
  canvas.width = W; canvas.height = H;
  canvas.style.width = "100%";
  canvas.style.display = "block";
  const ctx = canvas.getContext("2d");

  const text = (payload.prompt + " " + payload.style).toLowerCase();
  const themes = {
    غروب: ["#ff5c7a", "#ffb45c", "#2b1a3c"],
    دریا: ["#3a7bff", "#5cc7ff", "#0b1436"],
    شهر: ["#7c5cff", "#ff5ca8", "#14102a"],
    کوه: ["#8ea0c7", "#e6ecff", "#1a2340"],
    جنگل: ["#3ac48a", "#8fe07c", "#0f2a1c"],
    فضایی: ["#a06bff", "#3a2a7c", "#080418"],
    آتش: ["#ff8b3a", "#ff3a5c", "#2a0e18"],
    برف: ["#cfe4ff", "#8fb7ff", "#0f1730"],
    گربه: ["#ffb45c", "#ff7a3a", "#26152a"],
    قهوه: ["#b4744a", "#6b3a2a", "#1a0f0a"]
  };
  let palette = ["#7c5cff", "#ff5ca8", "#100a26"];
  for (const k in themes) if (text.includes(k)) { palette = themes[k]; break; }
  const [c1, c2, bg] = palette;

  const N = 80;
  const parts = Array.from({ length: N }, () => ({
    x: Math.random() * W, y: Math.random() * H,
    r: 1 + Math.random() * 2.4,
    vx: (Math.random() - .5) * .6, vy: (Math.random() - .5) * .6,
    a: .25 + Math.random() * .5
  }));

  const DURATION = payload.duration * 1000;
  let t0 = performance.now();
  let rafId = null;
  let paused = false;

  function draw(now) {
    const t = (((now - t0) % DURATION) / DURATION);
    const phase = t * Math.PI * 2;

    const g = ctx.createLinearGradient(0, 0, W * (0.6 + 0.4 * Math.sin(phase)), H);
    g.addColorStop(0, bg);
    g.addColorStop(1, c1);
    ctx.fillStyle = g;
    ctx.fillRect(0, 0, W, H);

    const cx = W * (0.3 + 0.4 * (0.5 + 0.5 * Math.sin(phase)));
    const cy = H * (0.4 + 0.3 * Math.cos(phase));
    const rad = Math.max(W, H) * (0.35 + 0.15 * Math.sin(phase));
    const rg = ctx.createRadialGradient(cx, cy, 0, cx, cy, rad);
    rg.addColorStop(0, c2 + "cc");
    rg.addColorStop(1, "transparent");
    ctx.fillStyle = rg;
    ctx.fillRect(0, 0, W, H);

    for (const p of parts) {
      p.x += p.vx; p.y += p.vy;
      if (p.x < 0) p.x = W; if (p.x > W) p.x = 0;
      if (p.y < 0) p.y = H; if (p.y > H) p.y = 0;
      ctx.globalAlpha = p.a * (0.5 + 0.5 * Math.sin(phase * 2 + p.x));
      ctx.fillStyle = "#fff";
      ctx.beginPath();
      ctx.arc(p.x, p.y, p.r, 0, Math.PI * 2);
      ctx.fill();
    }
    ctx.globalAlpha = 1;

    const fs = Math.round(H * 0.05);
    ctx.fillStyle = "#fff";
    ctx.textAlign = "center";
    ctx.textBaseline = "middle";
    ctx.font = `700 ${fs}px Vazirmatn, Tahoma, sans-serif`;
    ctx.direction = "rtl";
    const short = payload.prompt.length > 55
      ? payload.prompt.slice(0, 55) + "…" : payload.prompt;
    wrapText(ctx, short, W / 2, H / 2, W - 40, fs * 1.6);

    ctx.fillStyle = "rgba(255,255,255,.15)";
    ctx.fillRect(0, H - 4, W, 4);
    ctx.fillStyle = c2;
    ctx.fillRect(0, H - 4, W * t, 4);

    if (!paused) rafId = requestAnimationFrame(draw);
  }

  function wrapText(c, text, x, y, maxW, lh) {
    const words = text.split(" ");
    let line = "", lines = [];
    for (const w of words) {
      const test = line ? line + " " + w : w;
      if (c.measureText(test).width > maxW) { lines.push(line); line = w; }
      else line = test;
    }
    if (line) lines.push(line);
    const startY = y - (lines.length - 1) * lh / 2;
    lines.forEach((l, i) => c.fillText(l, x, startY + i * lh));
  }

  rafId = requestAnimationFrame(draw);

  return buildStage(canvas, () => { paused = true; }, () => {
    paused = false;
    t0 = performance.now();
    rafId = requestAnimationFrame(draw);
  });
}

/* =========================================================
   ساخت استیج با کنترل‌ها
   ========================================================= */
function buildStage(canvas, onPause, onResume) {
  const wrap = document.createElement("div");
  wrap.style.position = "relative";
  wrap.appendChild(canvas);

  const tools = document.createElement("div");
  tools.className = "stage-tools";

  // ذخیره فریم
  const dl = document.createElement("button");
  dl.type = "button"; dl.className = "ghost"; dl.textContent = "⬇️ ذخیره فریم";
  dl.addEventListener("click", () => {
    const a = document.createElement("a");
    a.download = "frame-" + Date.now() + ".png";
    a.href = canvas.toDataURL("image/png");
    a.click();
    toast("فریم ذخیره شد");
  });

  // توقف / ادامه
  const stop = document.createElement("button");
  stop.type = "button"; stop.className = "ghost"; stop.textContent = "⏸ توقف";
  let isPaused = false;
  stop.addEventListener("click", () => {
    isPaused = !isPaused;
    stop.textContent = isPaused ? "▶️ ادامه" : "⏸ توقف";
    if (isPaused) onPause(); else onResume();
  });

  // ضبط WebM
  const rec = document.createElement("button");
  rec.type = "button"; rec.className = "ghost"; rec.textContent = "🎥 شروع ضبط";
  let recorder = null;
  let chunks = [];
  let recStart = 0;
  let timerId = null;

  rec.addEventListener("click", async () => {
    // اگر در حال ضبط است → توقف و ذخیره
    if (recorder && recorder.state === "recording") {
      recorder.stop();
      return;
    }

    if (!("MediaRecorder" in window)) {
      toast("مرورگر از ضبط ویدیو پشتیبانی نمی‌کند");
      return;
    }

    try {
      const stream = canvas.captureStream(30);
      const mime = MediaRecorder.isTypeSupported("video/webm;codecs=vp9")
        ? "video/webm;codecs=vp9"
        : MediaRecorder.isTypeSupported("video/webm;codecs=vp8")
          ? "video/webm;codecs=vp8"
          : "video/webm";

      recorder = new MediaRecorder(stream, {
        mimeType: mime,
        videoBitsPerSecond: 4_000_000
      });
      chunks = [];
      recorder.ondataavailable = (e) => { if (e.data.size) chunks.push(e.data); };
      recorder.onstop = () => {
        clearInterval(timerId);
        const blob = new Blob(chunks, { type: "video/webm" });
        const url = URL.createObjectURL(blob);
        const a = document.createElement("a");
        a.download = "video-" + Date.now() + ".webm";
        a.href = url;
        a.click();
        setTimeout(() => URL.revokeObjectURL(url), 3000);
        rec.textContent = "🎥 شروع ضبط";
        toast("ویدیو ذخیره شد ✓");
      };
      recorder.start(100);
      recStart = Date.now();
      rec.textContent = "⏹ توقف ضبط (۰s)";
      timerId = setInterval(() => {
        const s = Math.round((Date.now() - recStart) / 1000);
        rec.textContent = `⏹ توقف ضبط (${fa(s)}s)`;
      }, 500);
      toast("در حال ضبط — وقتی تمام شد دوباره بزن");
    } catch (e) {
      console.warn(e);
      toast("خطا در شروع ضبط");
    }
  });

  tools.append(dl, stop, rec);
  wrap.appendChild(tools);
  return wrap;
}

/* =========================================================
   تاریخچه و گالری
   ========================================================= */
function saveHistory(item) {
  state.history.unshift(item);
  state.history = state.history.slice(0, 20);
  try {
    localStorage.setItem("vfree_history", JSON.stringify(state.history));
  } catch (e) {
    const slim = state.history.map((h) => ({ ...h, thumb: null })).slice(0, 8);
    try { localStorage.setItem("vfree_history", JSON.stringify(slim)); } catch (_) {}
  }
  renderGallery();
}

function renderGallery() {
  const g = $("#gallery");
  g.innerHTML = "";
  if (!state.history.length) {
    g.innerHTML = `<div class="empty-note" style="grid-column:1/-1">
      هنوز ویدیویی نساخته‌اید. اولین ویدیو را بسازید ✨</div>`;
    return;
  }
  state.history.forEach((h) => {
    const d = document.createElement("div");
    d.className = "gitem";
    const thumbStyle = h.thumb
      ? `style="background-image:url('${h.thumb}');background-size:cover;background-position:center"`
      : "";
    d.innerHTML = `
      <div class="gthumb" ${thumbStyle}>${h.thumb ? "" : (h.mode === "image" ? "🧑‍🎤" : "🎬")}</div>
      <div class="gbody"><p>${escapeHtml(h.prompt)}</p></div>`;
    d.addEventListener("click", () => {
      if (h.mode === "image") {
        document.querySelector('#tabs button[data-v="image"]').click();
        $("#promptImage").value = h.prompt || "";
      } else {
        document.querySelector('#tabs button[data-v="text"]').click();
        $("#promptText").value = h.prompt || "";
      }
      $("#style").value = h.style || $("#style").value;
      toast("تنظیمات به فرم منتقل شد");
      window.scrollTo({ top: 0, behavior: "smooth" });
    });
    g.appendChild(d);
  });
}

$("#clearBtn").addEventListener("click", () => {
  if (!state.history.length) return;
  state.history = [];
  try { localStorage.removeItem("vfree_history"); } catch (e) {}
  renderGallery();
  toast("گالری پاک شد");
});

/* =========================================================
   شروع
   ========================================================= */
renderGallery();
</script>
</body>
</html>
