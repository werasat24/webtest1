<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>คำนวณค่าต่าง ๆ</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 20px;
            overflow-y: auto; /* ทำให้หน้าเว็บสามารถเลื่อนได้ */
        }

        h1, h2 {
            text-align: center;
            color: #333;
        }

        form {
            max-width: 400px;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        /* ตกแต่งกล่องข้อความ */
        input[type="number"] {
            width: calc(100% - 22px); /* ปรับขนาดให้พอดีกับ padding */
            padding: 10px;
            margin: 10px 0; /* เพิ่มระยะห่างระหว่างกล่อง */
            border: 1px solid #ccc;
            border-radius: 8px;
            box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.1);
            font-size: 16px;
            transition: all 0.3s ease-in-out;
        }

        /* เปลี่ยนสีและเงาเมื่อโฟกัส */
        input[type="number"]:focus {
            border-color: #007bff;
            box-shadow: 2px 2px 8px rgba(0, 123, 255, 0.5);
            outline: none;
        }

        /* ตกแต่งปุ่มคำนวณ */
        .calculate-button {
            padding: 10px;
            margin-top: 10px; /* เพิ่มระยะห่างระหว่างปุ่ม */
            width: calc(50% - 5px); /* ปรับขนาดปุ่มให้พอดีกับฟอร์ม */
            font-size: 16px;
            color: #fff;
            background-color: #28a745; /* สีเขียว */
            border: none;
            border-radius: 8px;
            cursor: pointer;
            transition: background-color 0.3s ease-in-out, box-shadow 0.3s ease-in-out;
        }

        /* เปลี่ยนสีปุ่มคำนวณเมื่อ hover */
        .calculate-button:hover {
            background-color: #218838; /* สีเขียวเข้ม */
            box-shadow: 2px 2px 8px rgba(40, 167, 69, 0.5);
        }

        /* ตกแต่งปุ่มล้างข้อมูลทั้งหมด */
        .clear-button {
            padding: 10px;
            margin-top: 10px; /* เพิ่มระยะห่างระหว่างปุ่ม */
            width: calc(50% - 5px); /* ปรับขนาดปุ่มให้พอดีกับฟอร์ม */
            font-size: 16px;
            color: #fff;
            background-color: #c80014; /* สีแดง */
            border: none;
            border-radius: 8px;
            cursor: pointer;
            transition: background-color 0.3s ease-in-out, box-shadow 0.3s ease-in-out;
        }

        /* เปลี่ยนสีปุ่มล้างข้อมูลเมื่อ hover */
        .clear-button:hover {
            background-color: #b40012; /* สีแดงเข้ม */
            box-shadow: 2px 2px 8px rgba(220, 53, 69, 0.5);
        }

        /* ตกแต่งส่วนผลลัพธ์ */
        #result {
            margin-top: 20px;
            padding: 15px;
            background-color: #f9f9f9;
            border-radius: 8px;
            box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.1);
        }
    </style>
    <script>
        function calculate() {
            // รับค่าจากกล่องข้อความ
            const numbers = [];
            for (let i = 1; i <= 10; i++) {
                const value = parseFloat(document.getElementById(`number${i}`).value);
                if (!isNaN(value)) {
                    numbers.push(value);
                }
            }

            if (numbers.length === 0) {
                alert("กรุณาใส่ตัวเลขอย่างน้อยหนึ่งตัว");
                return;
            }

            // คำนวณค่าสูงสุดและค่าต่ำสุด
            const maxValue = Math.max(...numbers);
            const minValue = Math.min(...numbers);
            const difference = maxValue - minValue;

            // คำนวณผลรวมและค่าเฉลี่ย (หารด้วยจำนวนตัวเลขที่กรอก)
            const sum = numbers.reduce((acc, curr) => acc + curr, 0);
            const average = sum / numbers.length;

            // คำนวณผลต่างระหว่างค่าสูงสุดและค่าต่ำสุดมาหารสอง
            const halfDifference = difference / 2;

             // แสดงผลลัพธ์ (ปัดเศษทศนิยมให้เหลือสองตำแหน่ง)
             document.getElementById("result").innerHTML = `
                <p>ค่าสูงสุด: ${maxValue.toFixed(2)}</p>
                <p>ค่าต่ำสุด: ${minValue.toFixed(2)}</p>
                <p>ผลต่างระหว่างค่าสูงสุดและค่าต่ำสุด: ${difference.toFixed(2)}</p>
                <p>ค่า error: ${halfDifference.toFixed(2)}</p>
                <p>ค่าที่ได้: ${average.toFixed(2)}</p>
             `;
         }

         function resetForm() {
             // ล้างค่าทั้งหมดในฟอร์ม
             for (let i = 1; i <= 10; i++) {
                 document.getElementById(`number${i}`).value = '';
             }
             // ล้างผลลัพธ์
             document.getElementById("result").innerHTML = '';
         }

         function clearAll() {
             // ล้างค่าทั้งหมดในฟอร์มและผลลัพธ์
             resetForm();
         }
    </script>
</head>
<body>
    <h1>คำนวณหาค่า error</h1>
    <form onsubmit="event.preventDefault(); calculate();">
        <div>
          <label for="number1">ตัวเลขที่ 1:</label>
          <input type="number" id="number1" required step="any"><br>
      </div>
      <div>
          <label for="number2">ตัวเลขที่ 2:</label>
          <input type="number" id="number2" required step="any"><br>
      </div>
      <div>
          <label for="number3">ตัวเลขที่ 3:</label>
          <input type="number" id="number3" required step="any"><br>
      </div>
      <div>
          <label for="number4">ตัวเลขที่ 4:</label>
          <input type="number" id="number4" required step="any"><br>
      </div>
      <div>
          <label for="number5">ตัวเลขที่ 5:</label>
          <input type="number" id="number5" required step="any"><br>
      </div>
      <div>
          <label for="number6">ตัวเลขที่ 6:</label>
          <input type="number" id="number6" required step="any"><br>
      </div>
      <div>
          <label for="number7">ตัวเลขที่ 7:</label>
          <input type="number" id="number7" required step="any"><br>
      </div>
      <div>
          <label for="number8">ตัวเลขที่ 8:</label>
          <input type="number" id="number8" required step="any"><br>
      </div>
      <div>
          <label for="number9">ตัวเลขที่ 9:</label>
          <input type="number" id="number9" required step="any"><br>
      </div>
      <div>
          <label for="number10">ตัวเลขที่ 10:</label>
          <input type="number" id="number10" required step="any"><br>
      </div>

      <!-- ปุ่มคำนวณ -->
      <button type="submit" class="calculate-button">คำนวณ</button>

      <!-- ปุ่มล้างข้อมูลทั้งหมด -->
      <button type="button" class="clear-button" onclick="clearAll()">ล้างข้อมูลทั้งหมด</button>

    </form>

    <!-- ผลลัพธ์ -->
    <h2>ผลลัพธ์</h2>

    <!-- แสดงผลลัพธ์ -->
    <div id="result"></div>

</body>
</html>

