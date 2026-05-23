# rukan
download document
<style>
.qr-gen-wrap{font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial,sans-serif;max-width:1100px;margin:30px auto;padding:20px;color:#222}
.qr-gen-wrap *{box-sizing:border-box}
.qr-gen-title{text-align:center;margin-bottom:30px}
.qr-gen-title h2{font-size:32px;margin:0 0 8px;font-weight:700;color:#1a1a2e}
.qr-gen-title p{margin:0;color:#666;font-size:15px}
.qr-gen-grid{display:grid;grid-template-columns:1fr 1fr;gap:24px}
@media(max-width:768px){.qr-gen-grid{grid-template-columns:1fr}}
.qr-gen-card{background:#fff;border:1px solid #e5e7eb;border-radius:14px;padding:26px;box-shadow:0 4px 14px rgba(0,0,0,.04)}
.qr-gen-field{margin-bottom:18px}
.qr-gen-field label{display:block;font-weight:600;margin-bottom:8px;font-size:14px;color:#333}
.qr-gen-field input[type=text],.qr-gen-field input[type=url],.qr-gen-field select{width:100%;padding:12px 14px;border:1px solid #d1d5db;border-radius:10px;font-size:14px;outline:none;transition:.2s;background:#fff}
.qr-gen-field input[type=text]:focus,.qr-gen-field input[type=url]:focus,.qr-gen-field select:focus{border-color:#3b46f0;box-shadow:0 0 0 3px rgba(59,70,240,.15)}
.qr-gen-input-group{display:flex;gap:8px}
.qr-gen-input-group input{flex:1}
.qr-gen-reset{background:#f1f5f9;border:1px solid #d1d5db;color:#475569;padding:0 16px;border-radius:10px;cursor:pointer;font-size:13px;font-weight:600;transition:.2s;white-space:nowrap}
.qr-gen-reset:hover{background:#e2e8f0;color:#1e293b}
.qr-gen-file{display:flex;align-items:center;gap:12px}
.qr-gen-file label.btn{background:#eef0ff;color:#3b46f0;padding:8px 18px;border-radius:30px;cursor:pointer;font-weight:600;font-size:14px;border:none}
.qr-gen-file label.btn:hover{background:#dfe2ff}
.qr-gen-file input[type=file]{display:none}
.qr-gen-file .fname{color:#888;font-size:13px}
.qr-gen-row{display:grid;grid-template-columns:1fr 1fr;gap:16px}
.qr-gen-row3{display:grid;grid-template-columns:1fr 1fr 1fr;gap:12px}
.qr-gen-row input[type=color]{width:100%;height:42px;border:1px solid #d1d5db;border-radius:8px;cursor:pointer;padding:2px;background:#fff}
.qr-gen-btn{width:100%;background:#3b46f0;color:#fff;border:none;padding:14px;border-radius:10px;font-size:16px;font-weight:600;cursor:pointer;transition:.2s}
.qr-gen-btn:hover{background:#2c36d6}
.qr-gen-btn:disabled{background:#94a3b8;cursor:not-allowed}
.qr-gen-preview{display:flex;flex-direction:column;align-items:center;justify-content:center;min-height:340px}
.qr-gen-canvas-box{width:100%;aspect-ratio:1/1;max-width:380px;background:#fff;border:1px solid #e5e7eb;border-radius:10px;display:flex;align-items:center;justify-content:center;padding:14px;margin-bottom:16px;overflow:hidden}
.qr-gen-canvas-box canvas,.qr-gen-canvas-box svg{max-width:100%;height:auto;display:block}
.qr-gen-canvas-box .ph{color:#bbb;font-size:14px}
.qr-gen-download{width:100%;background:#22c55e;color:#fff;border:none;padding:14px;border-radius:10px;font-size:16px;font-weight:600;cursor:pointer;transition:.2s}
.qr-gen-download:hover{background:#16a34a}
.qr-gen-download:disabled{background:#a7d4b8;cursor:not-allowed}
.qrg-modal{position:fixed;inset:0;background:rgba(0,0,0,.85);z-index:999999;display:none;align-items:center;justify-content:center;padding:16px}
.qrg-modal.show{display:flex}
.qrg-modal-card{background:#fff;border-radius:16px;padding:20px;max-width:420px;width:100%;text-align:center;max-height:92vh;overflow-y:auto}
.qrg-modal-card h3{margin:0 0 6px;font-size:18px;color:#1a1a2e}
.qrg-modal-card p{margin:0 0 14px;color:#475569;font-size:13px;line-height:1.5}
.qrg-modal-card p b{color:#1e293b}
.qrg-modal-card img{max-width:100%;height:auto;border:1px solid #e5e7eb;border-radius:10px;margin-bottom:14px;-webkit-touch-callout:default;touch-action:manipulation}
.qrg-modal-close{background:#3b46f0;color:#fff;border:none;padding:10px 26px;border-radius:8px;font-weight:600;cursor:pointer;font-size:14px}
</style>

<div class="qr-gen-wrap">
  <div class="qr-gen-title">
    <h2>QR Code Generator</h2>
    <p>สร้าง QR Code ที่ "สวยที่สุดในจักรวาล</p>
    <p>Design By: TRIRUT TONGNOOM</p>
  </div>
  <div class="qr-gen-grid">
    <div class="qr-gen-card">
      <div class="qr-gen-field">
        <label for="qrgText">ข้อความหรือ URL</label>
        <div class="qr-gen-input-group">
          <input type="text" id="qrgText" placeholder="https://example.com" value="https://kan.ru.ac.th">
          <button type="button" class="qr-gen-reset" id="qrgReset" title="ล้างข้อความ">รีเซ็ต</button>
        </div>
      </div>
      <div class="qr-gen-field">
        <label>อัปโหลดโลโก้ (ถ้ามี)</label>
        <div class="qr-gen-file">
          <label class="btn" for="qrgLogo">Browse...</label>
          <input type="file" id="qrgLogo" accept="image/*">
          <span class="fname" id="qrgFname">No file selected.</span>
        </div>
      </div>
      <div class="qr-gen-field">
        <div class="qr-gen-row3">
          <div>
            <label for="qrgDots">รูปทรงจุด</label>
            <select id="qrgDots">
              <option value="rounded" selected>มน (Rounded)</option>
              <option value="dots">วงกลม (Dots)</option>
              <option value="classy">เพชร (Classy)</option>
              <option value="classy-rounded">เพชรมน</option>
              <option value="square">สี่เหลี่ยม</option>
              <option value="extra-rounded">มนมาก</option>
            </select>
          </div>
          <div>
            <label for="qrgCorner">มุมกรอบ</label>
            <select id="qrgCorner">
              <option value="extra-rounded" selected>มนมาก</option>
              <option value="square">สี่เหลี่ยม</option>
              <option value="dot">จุด</option>
            </select>
          </div>
          <div>
            <label for="qrgCornerDot">จุดมุม</label>
            <select id="qrgCornerDot">
              <option value="dot" selected>จุดวงกลม</option>
              <option value="square">สี่เหลี่ยม</option>
            </select>
          </div>
        </div>
      </div>
      <div class="qr-gen-field">
        <div class="qr-gen-row">
          <div>
            <label for="qrgFg">สีหลัก</label>
            <input type="color" id="qrgFg" value="#0d00b3">
          </div>
          <div>
            <label for="qrgBg">สีพื้นหลัง</label>
            <input type="color" id="qrgBg" value="#ffffff">
          </div>
        </div>
      </div>
      <button class="qr-gen-btn" id="qrgGen">สร้าง QR Code</button>
    </div>
    <div class="qr-gen-card qr-gen-preview">
      <div class="qr-gen-canvas-box" id="qrgBox">
        <span class="ph">QR Code จะแสดงที่นี่</span>
      </div>
      <button class="qr-gen-download" id="qrgDl" disabled>ดาวน์โหลดรูปภาพ</button>
    </div>
  </div>
</div>

<div class="qrg-modal" id="qrgModal">
  <div class="qrg-modal-card">
    <h3>บันทึกรูปภาพ</h3>
    <p><b>กดค้างที่รูป</b> แล้วเลือก <b>"บันทึกลงรูปภาพ"</b> หรือ <b>"Save to Photos"</b></p>
    <img id="qrgModalImg" alt="QR Code">
    <button class="qrg-modal-close" id="qrgModalClose">ปิด</button>
  </div>
</div>

<script>
(function(){
  function loadScript(src,cb){
    if(window.QRCodeStyling){cb();return;}
    var s=document.createElement('script');
    s.src=src;s.onload=cb;s.onerror=function(){console.error('QR lib load fail')};
    document.head.appendChild(s);
  }
  loadScript('https://cdn.jsdelivr.net/npm/qr-code-styling@1.6.0-rc.1/lib/qr-code-styling.js',init);

  function isMobile(){
    var ua=navigator.userAgent||'';
    if(/iPad|iPhone|iPod/.test(ua))return true;
    if(navigator.platform==='MacIntel' && navigator.maxTouchPoints>1)return true;
    if(/Android/i.test(ua))return true;
    return false;
  }

  function init(){
    var txt=document.getElementById('qrgText');
    var fg=document.getElementById('qrgFg');
    var bg=document.getElementById('qrgBg');
    var logo=document.getElementById('qrgLogo');
    var fname=document.getElementById('qrgFname');
    var box=document.getElementById('qrgBox');
    var btn=document.getElementById('qrgGen');
    var dl=document.getElementById('qrgDl');
    var rst=document.getElementById('qrgReset');
    var dots=document.getElementById('qrgDots');
    var corner=document.getElementById('qrgCorner');
    var cornerDot=document.getElementById('qrgCornerDot');
    var modal=document.getElementById('qrgModal');
    var modalImg=document.getElementById('qrgModalImg');
    var modalClose=document.getElementById('qrgModalClose');
    var defaultUrl=txt.value;
    var logoData=null;
    var qr=null;
    var mobile=isMobile();

    logo.addEventListener('change',function(e){
      var f=e.target.files[0];
      if(!f){fname.textContent='No file selected.';logoData=null;return;}
      fname.textContent=f.name;
      var r=new FileReader();
      r.onload=function(ev){logoData=ev.target.result;};
      r.readAsDataURL(f);
    });

    rst.addEventListener('click',function(){
      txt.value=defaultUrl;
      txt.focus();
    });

    function renderQR(data){
      var size=380;
      var opts={
        width:size,
        height:size,
        type:'canvas',
        data:data,
        margin:6,
        qrOptions:{errorCorrectionLevel:'H'},
        dotsOptions:{color:fg.value,type:dots.value},
        backgroundOptions:{color:bg.value},
        cornersSquareOptions:{color:fg.value,type:corner.value},
        cornersDotOptions:{color:fg.value,type:cornerDot.value},
        imageOptions:{crossOrigin:'anonymous',margin:6,imageSize:0.32,hideBackgroundDots:true}
      };
      if(logoData)opts.image=logoData;
      box.innerHTML='';
      qr=new QRCodeStyling(opts);
      qr.append(box);
      dl.disabled=false;
    }

    function generate(){
      var v=txt.value.trim();
      if(!v){alert('กรุณาใส่ข้อความหรือ URL');return;}
      renderQR(v);
    }

    function getCanvasDataUrl(){
      var cv=box.querySelector('canvas');
      if(!cv)return null;
      try{return cv.toDataURL('image/png');}catch(e){return null;}
    }

    function downloadDesktop(){
      var url=getCanvasDataUrl();
      if(!url){
        if(qr)qr.download({name:'qrcode',extension:'png'});
        return;
      }
      var a=document.createElement('a');
      a.href=url;
      a.download='qrcode.png';
      document.body.appendChild(a);
      a.click();
      document.body.removeChild(a);
    }

    function showMobileModal(){
      var url=getCanvasDataUrl();
      if(!url){alert('ไม่สามารถสร้างรูปได้ กรุณากดสร้าง QR Code ใหม่');return;}
      modalImg.src=url;
      modal.classList.add('show');
      document.body.style.overflow='hidden';
    }

    function closeModal(){
      modal.classList.remove('show');
      document.body.style.overflow='';
    }

    dl.addEventListener('click',function(){
      if(mobile)showMobileModal();
      else downloadDesktop();
    });

    modalClose.addEventListener('click',closeModal);
    modal.addEventListener('click',function(e){if(e.target===modal)closeModal();});

    btn.addEventListener('click',generate);
    txt.addEventListener('keydown',function(e){if(e.key==='Enter')generate();});

    generate();
  }
})();
</script>
