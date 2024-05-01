<!DOCTYPE html>
<html>
<head>
  <title>โปรแกรมคำถาม</title>
  <script>
    function checkAnswer() {
      var answer = confirm("คุณพรชนกคุณอยากคืนดีกับผู้ใช้รายนี้หรือไม่?");
      if (answer) {
        alert("(*ﾟ▽ﾟ)ﾉ ทั้งบ้านงงแน่ไอ่เด็กนี่มันยิ้มอะไรทั้งวัน");
      } else {
        alert("(ﾉ_･､) ไม่เป็นไรค่ะเดี๋ยวเราจะหาวิธีใหม่");
      }
    }
  </script>
</head>
<body>

<button onclick="checkAnswer()">ตอบคำถาม</button>

</body>
</html>
