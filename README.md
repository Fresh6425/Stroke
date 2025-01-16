แบบประเมินความเสี่ยงโรคหลอดสมอง
<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>แบบประเมินความเสี่ยงโรคหลอดเลือด (ตัวเลือก)</title>
  <style>
    /* Reset CSS เล็กน้อย */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: sans-serif;
      background: #f8fdfc;
      color: #333;
      line-height: 1.6;
      padding: 20px;
    }

    h1, h2, h3 {
      text-align: center;
      margin-bottom: 20px;
      color: #07575b;
    }

    .container {
      max-width: 700px;
      margin: 0 auto;
      background: #ffffff;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      padding: 20px;
    }

    .question {
      margin-bottom: 20px;
    }

    .question h3 {
      margin-bottom: 10px;
    }

    .options {
      display: flex;
      flex-direction: column;
      gap: 8px;
    }

    label {
      font-weight: normal;
      display: flex;
      align-items: center;
      gap: 6px;
      cursor: pointer;
    }

    input[type="radio"] {
      accent-color: #0a9396; /* สีปุ่มเลือก */
    }

    button {
      background: #0a9396;
      color: #fff;
      border: none;
      padding: 12px 20px;
      border-radius: 4px;
      font-size: 16px;
      cursor: pointer;
      transition: background 0.3s ease;
      width: 100%;
      margin-top: 10px;
    }

    button:hover {
      background: #055c5e;
    }

    .result-box {
      margin-top: 20px;
      padding: 15px;
      background: #e1f7f6;
      border: 1px solid #bbebe7;
      border-radius: 5px;
    }

    .result-box p {
      margin-bottom: 10px;
      font-size: 1.1em;
    }

    .footer {
      text-align: center;
      margin-top: 30px;
      font-size: 0.85em;
      color: #777;
    }

    .footer a {
      color: #0a9396;
      text-decoration: none;
    }

    .footer .siam-nursing {
      color: #07575b;
      font-weight: bold;
      display: block;
      margin-top: 10px;
    }
  </style>
</head>
<body>

  <h1>แบบประเมินความเสี่ยง<br/>โรคหลอดเลือด (ตัวเลือก)</h1>

  <div class="container">
    <p style="margin-bottom: 20px;">
      โปรดเลือกคำตอบที่ตรงกับตัวคุณในแต่ละข้อ <br>
      (ผลลัพธ์เป็นเพียงตัวอย่างสมมติ ไม่ใช่คำวินิจฉัยทางการแพทย์จริง)
    </p>

    <!-- เริ่มต้นส่วนคำถาม -->
    <div class="question" id="q1">
      <h3>1. ช่วงอายุของคุณ</h3>
      <div class="options">
        <label><input type="radio" name="q1" value="0" /> ต่ำกว่า 30 ปี</label>
        <label><input type="radio" name="q1" value="2" /> 30 - 40 ปี</label>
        <label><input type="radio" name="q1" value="4" /> 41 - 50 ปี</label>
        <label><input type="radio" name="q1" value="6" /> 51 - 60 ปี</label>
        <label><input type="radio" name="q1" value="8" /> มากกว่า 60 ปี</label>
      </div>
    </div>

    <div class="question" id="q2">
      <h3>2. คุณสูบบุหรี่หรือไม่?</h3>
      <div class="options">
        <label><input type="radio" name="q2" value="0" /> ไม่เคยเลย</label>
        <label><input type="radio" name="q2" value="2" /> เคยสูบ แต่เลิกแล้ว</label>
        <label><input type="radio" name="q2" value="4" /> สูบเป็นประจำ</label>
      </div>
    </div>

    <div class="question" id="q3">
      <h3>3. คุณมีภาวะความดันโลหิตสูงหรือไม่?</h3>
      <div class="options">
        <label><input type="radio" name="q3" value="0" /> ไม่เคย</label>
        <label><input type="radio" name="q3" value="2" /> เคยตรวจเจอบ้าง</label>
        <label><input type="radio" name="q3" value="3" /> เป็นประจำและกินยาควบคุม</label>
      </div>
    </div>

    <div class="question" id="q4">
      <h3>4. คุณมีประวัติคนในครอบครัวเป็นโรคหลอดเลือดหรือไม่?</h3>
      <div class="options">
        <label><input type="radio" name="q4" value="0" /> ไม่มี</label>
        <label><input type="radio" name="q4" value="2" /> มี แต่ไม่ใกล้ชิด (เช่น ญาติห่าง ๆ)</label>
        <label><input type="radio" name="q4" value="4" /> มี และเป็นญาติใกล้ชิด (พ่อ แม่ พี่น้อง)</label>
      </div>
    </div>

    <div class="question" id="q5">
      <h3>5. การออกกำลังกายของคุณเป็นอย่างไร?</h3>
      <div class="options">
        <label><input type="radio" name="q5" value="0" /> แทบไม่ออกกำลังกาย</label>
        <label><input type="radio" name="q5" value="1" /> ออกกำลังกายเดือนละ 1-3 ครั้ง</label>
        <label><input type="radio" name="q5" value="2" /> ออกกำลังกายสัปดาห์ละ 1-2 ครั้ง</label>
        <label><input type="radio" name="q5" value="3" /> ออกกำลังกายอย่างน้อย 3 ครั้ง/สัปดาห์</label>
      </div>
    </div>
    <!-- สิ้นสุดส่วนคำถาม -->

    <!-- ปุ่มประเมินผล -->
    <button onclick="calculateRisk()">ประเมินความเสี่ยง</button>

    <!-- กล่องแสดงผลลัพธ์ -->
    <div class="result-box" id="result" style="display: none;">
      <h2>ผลการประเมิน</h2>
      <p id="riskScore"></p>
      <p id="riskInterpretation"></p>
      <p style="font-size: 0.9em; color: #555;">
        *ผลการประเมินนี้เป็นเพียงการคำนวณตัวอย่างเบื้องต้น ควรปรึกษาแพทย์หรือบุคลากรทางการแพทย์
      </p>
    </div>
  </div>

  <!-- Footer -->
  <div class="footer">
    <p>
      ข้อมูลเพิ่มเติมเกี่ยวกับสุขภาพหัวใจและหลอดเลือด: 
      <a href="https://www.heart.org/" target="_blank">American Heart Association</a> |
      <a href="https://www.who.int/" target="_blank">WHO</a>
    </p>
    <span class="siam-nursing">คณะพยาบาลศาสตร์มหาวิทยาลัยสยาม</span>
  </div>

  <script>
    function calculateRisk() {
      // ดึงค่าคะแนนจากคำถามแต่ละข้อ
      const q1Value = getSelectedValue('q1');
      const q2Value = getSelectedValue('q2');
      const q3Value = getSelectedValue('q3');
      const q4Value = getSelectedValue('q4');
      const q5Value = getSelectedValue('q5');

      // ถ้ายังตอบไม่ครบ ให้เตือน
      if (q1Value === null || q2Value === null || q3Value === null || q4Value === null || q5Value === null) {
        alert('กรุณาตอบคำถามให้ครบทุกข้อ');
        return;
      }

      // รวมคะแนน
      const totalScore = q1Value + q2Value + q3Value + q4Value + q5Value;

      // วิเคราะห์ผล (ตัวอย่างสมมติ)
      let interpretation = '';
      if (totalScore < 6) {
        interpretation = 'ความเสี่ยงต่ำ แนะนำให้ดูแลสุขภาพ ออกกำลังกายสม่ำเสมอ และตรวจสุขภาพประจำปี';
      } else if (totalScore < 10) {
        interpretation = 'ความเสี่ยงปานกลาง แนะนำปรับพฤติกรรม เช่น ลดสูบบุหรี่ ควบคุมอาหาร และออกกำลังกาย';
      } else {
        interpretation = 'ความเสี่ยงสูง ควรปรึกษาแพทย์เพื่อตรวจสุขภาพอย่างละเอียด และปฏิบัติตามคำแนะนำในการป้องกันโรคหลอดเลือด';
      }

      // แสดงผล
      document.getElementById('riskScore').innerText = `คะแนนความเสี่ยงของคุณ: ${totalScore} คะแนน`;
      document.getElementById('riskInterpretation').innerText = interpretation;
      document.getElementById('result').style.display = 'block';
    }

    function getSelectedValue(questionName) {
      const radios = document.getElementsByName(questionName);
      for (let i = 0; i < radios.length; i++) {
        if (radios[i].checked) {
          return parseInt(radios[i].value);
        }
      }
      return null;
    }
  </script>

</body>
</html>