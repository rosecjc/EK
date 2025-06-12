 (cd "$(git rev-parse --show-toplevel)" && git apply --3way <<'EOF' 
diff --git a/README.md b/README.md
index 5fc9a365467064946b14cf78259e539b47a1ca4a..384a278d4f535b57ea8bfef7944079795faf5566 100644
--- a/README.md
+++ b/README.md
@@ -1 +1,5 @@
-# EK
+# Krispy Kreme 夏．果香活動頁面
+
+此專案包含一個簡易的行銷活動網頁 `index.html`，介紹 Krispy Kreme 於 2025 年推出的「夏．果香」系列甜甜圈與相關優惠，並提供互動式心理測驗小遊戲，協助使用者找到最適合自己的口味。
+
+開啟 `index.html` 即可在瀏覽器中查看效果。
 
EOF
)
 (cd "$(git rev-parse --show-toplevel)" && git apply --3way <<'EOF' 
diff --git a//dev/null b/index.html
index 0000000000000000000000000000000000000000..1cc7f5d7962c886caa5796d7cc0736f54c06cc0d 100644
--- a//dev/null
+++ b/index.html
@@ -0,0 +1,144 @@
+<!DOCTYPE html>
+<html lang="zh-Hant">
+<head>
+<meta charset="UTF-8">
+<title>Hello Fruity Summer! 夏．果香</title>
+<style>
+body { font-family: Arial, sans-serif; margin: 0; padding: 20px; background: #fffced; color: #333; }
+section { margin-bottom: 40px; }
+h1, h2 { color: #d24c2a; }
+ul { padding-left: 20px; }
+.question { margin-bottom: 20px; }
+button { padding: 10px 20px; background: #d24c2a; color: white; border: none; cursor: pointer; }
+button:hover { background: #b03e22; }
+#result { margin-top: 30px; }
+canvas { display: block; margin-top: 20px; }
+</style>
+</head>
+<body>
+<h1>Hello Fruity Summer! 夏．果香</h1>
+<section id="intro">
+  <p>酸甜清爽、滋潤味蕾的夏日果香盛宴來囉！活動期間：<strong>2025/5/12 - 6/25</strong>。</p>
+</section>
+<section id="flavors">
+  <h2>最新口味介紹</h2>
+  <h3>檸檬甜星 (Lemon Galaxy)</h3>
+  <p>清香酸甜的檸檬糖霜結合檸檬巧克力，表面撒上繽紛星星糖片，猶如夏夜星空般閃耀。</p>
+  <h3>葡萄香檳浪花 (Sparkling Grape Wave)</h3>
+  <p>濃郁葡萄巧克力搭配微酸香檳糖霜，點綴跳跳糖，帶來海邊戲水般的清新愉悅。</p>
+  <h3>百香果派對 (Passion Party)</h3>
+  <p>以香氣四溢的百香果糖霜為基底，搭配迷你棉花糖與脆口彩米，猶如歡樂派對的驚喜口感。</p>
+</section>
+<section id="quiz">
+  <h2>口味選擇障礙小遊戲</h2>
+  <form id="quizForm">
+    <div class="question">
+      <p>1. 如果你是一種動物，你會選擇？</p>
+      <label><input type="radio" name="q1" value="lemon"> 活潑的海豚</label><br>
+      <label><input type="radio" name="q1" value="original"> 溫柔的鹿</label><br>
+      <label><input type="radio" name="q1" value="grape"> 聰明的狐狸</label><br>
+      <label><input type="radio" name="q1" value="choco"> 慵懶的貓咪</label>
+    </div>
+    <div class="question">
+      <p>2. 哪個季節最能代表你？</p>
+      <label><input type="radio" name="q2" value="lemon"> 夏天</label><br>
+      <label><input type="radio" name="q2" value="passion"> 春天</label><br>
+      <label><input type="radio" name="q2" value="choco"> 冬天</label><br>
+      <label><input type="radio" name="q2" value="grape"> 秋天</label>
+    </div>
+    <div class="question">
+      <p>3. 最喜歡的休閒活動？</p>
+      <label><input type="radio" name="q3" value="grape"> 到海邊走走</label><br>
+      <label><input type="radio" name="q3" value="lemon"> 輕鬆郊遊</label><br>
+      <label><input type="radio" name="q3" value="passion"> 參加派對</label><br>
+      <label><input type="radio" name="q3" value="original"> 在家追劇</label>
+    </div>
+    <div class="question">
+      <p>4. 清晨的第一個感覺？</p>
+      <label><input type="radio" name="q4" value="original"> 溫暖慵懶</label><br>
+      <label><input type="radio" name="q4" value="passion"> 活力四射</label><br>
+      <label><input type="radio" name="q4" value="lemon"> 明亮清新</label><br>
+      <label><input type="radio" name="q4" value="grape"> 涼爽微風</label>
+    </div>
+    <div class="question">
+      <p>5. 今天覺得幸運的顏色是？</p>
+      <label><input type="radio" name="q5" value="lemon"> 黃色</label><br>
+      <label><input type="radio" name="q5" value="grape"> 紫色</label><br>
+      <label><input type="radio" name="q5" value="passion"> 粉橘色</label><br>
+      <label><input type="radio" name="q5" value="choco"> 棕色</label>
+    </div>
+    <button type="button" onclick="showResult()">看結果</button>
+  </form>
+  <div id="result"></div>
+  <canvas id="donutCanvas" width="300" height="200"></canvas>
+</section>
+<section id="offers">
+  <h2>最新優惠活動</h2>
+  <ul>
+    <li><strong>LINE 好友獨享 1+1</strong> (2025/5/12-5/18)：5/11 前成為 LINE 好友者可獲新品券，購買「夏．果香禮盒」送「原味糖霜甜甜圈」一盒。</li>
+    <li><strong>夏．果香禮盒</strong> (2025/5/12-6/25)：6 入 299 元、12 入 499 元，皆含 3 顆夏．果香甜甜圈。</li>
+    <li><strong>夏．果香套餐</strong> (2025/5/12-6/25)：購買任一夏．果香甜甜圈，加購飲品折抵 15 元。</li>
+    <li><strong>幸運水果盤！線上轉好禮</strong> (2025/5/19-6/12)：每日登入 LINE 即可免費玩轉盤，有機會獲得免費新品禮盒。</li>
+    <li><strong>歡慶國際甜甜圈日！買一送一</strong> (2025/6/6)：購買 6 入或 12 入盒販即贈 6 入「原味糖霜甜甜圈」，各門市限量 50 組。</li>
+  </ul>
+  <p><small>※ 以門市數量為主，數量有限，贈完為止，活動優惠不得合併使用，外送平台不適用。Krispy Kreme 保留取消、變更與終止活動之權利。</small></p>
+</section>
+<script>
+const flavorInfo = {
+  lemon: {name: '檸檬甜星', color: '#f5d142', desc: '清爽檸檬香帶來夏夜星空般的好心情。'},
+  grape: {name: '葡萄香檳浪花', color: '#9d64d9', desc: '濃郁葡萄與香檳糖霜交織成海邊浪花般清新。'},
+  passion: {name: '百香果派對', color: '#ff9966', desc: '百香果香氣搭配棉花糖彩米，宛如派對般繽紛。'},
+  original: {name: '原味糖霜', color: '#f2c078', desc: '經典鬆軟口感，是最純粹的甜蜜享受。'},
+  choco: {name: '巧克力糖霜', color: '#9b5a3c', desc: '濃厚巧克力與鬆軟口感的完美結合。'}
+};
+function showResult() {
+  const form = document.getElementById('quizForm');
+  const data = new FormData(form);
+  const counts = {lemon:0, grape:0, passion:0, original:0, choco:0};
+  for (const [key,value] of data.entries()) {
+    counts[value]++;
+  }
+  let selected = 'original';
+  let max = 0;
+  for (const k in counts) {
+    if (counts[k] > max) {max = counts[k]; selected = k;}
+  }
+  const flavor = flavorInfo[selected];
+  const resultDiv = document.getElementById('result');
+  let answerText = '';
+  data.forEach((v, k) => {
+    answerText += `${k} 選擇了 ${flavorInfo[v].name}<br>`;
+  });
+  resultDiv.innerHTML = `<h3>推薦口味：${flavor.name}</h3><p>${answerText}</p><p>${flavor.desc}</p><p>這款甜甜圈的鬆軟口感，搭配你的獨特個性，絕對能讓你的夏日甜上加甜！</p>`;
+  drawDonut(flavor.color);
+}
+function drawDonut(color) {
+  const canvas = document.getElementById('donutCanvas');
+  const ctx = canvas.getContext('2d');
+  ctx.clearRect(0,0,canvas.width,canvas.height);
+  const x = canvas.width/2;
+  const y = canvas.height/2;
+  const outer = 80; const inner = 30;
+  const grad = ctx.createRadialGradient(x-10,y-10,inner,x,y,outer);
+  grad.addColorStop(0,'#ffffff');
+  grad.addColorStop(1,color);
+  ctx.fillStyle = grad;
+  ctx.beginPath();
+  ctx.arc(x,y,outer,0,Math.PI*2);
+  ctx.arc(x,y,inner,0,Math.PI*2,true);
+  ctx.fill();
+  ctx.strokeStyle = '#fff';
+  ctx.lineWidth = 2;
+  for(let i=0;i<10;i++){
+    ctx.beginPath();
+    const angle = Math.random()*Math.PI*2;
+    const r = inner + (outer-inner)/2;
+    const dotX = x + r*Math.cos(angle);
+    const dotY = y + r*Math.sin(angle);
+    ctx.arc(dotX,dotY,3,0,Math.PI*2);
+    ctx.stroke();
+  }
+}
+</script>
+</body>
+</html>
 
EOF
)
