# Webtech
w2-1
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Lab2_01</title>
</head>
<body>
  <h1>August Bills</h1>
  <table>
    <tr>
      <th></th>
      <th>Price</th>
      <th>Due Date</th>
    </tr>
    <tr>
      <td>Phone</td>
      <td>$50</td>
      <td>August 1st</td>
    </tr>
    <tr>
      <td>Car insurance</td>
      <td>$100</td>
      <td>August 5st</td>
    </tr>
    <tr>
      <td>Internet</td>
      <td>$70</td>
      <td>August 10st</td>
    </tr>
  </table>
</body>
</html>

w2-2
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="style.css">
  <title>Lab2_02</title>
</head>
<body>
  <h1>August Bills</h1>
  <table>
    <tr>
      <th></th>
      <th>Price</th>
      <th>Due Date</th>
    </tr>
    <tr>
      <td>Phone</td>
      <td>$50</td>
      <td>August 1st</td>
    </tr>
    <tr>
      <td>Car insurance</td>
      <td>$100</td>
      <td>August 5st</td>
    </tr>
    <tr>
      <td>Internet</td>
      <td>$70</td>
      <td>August 10st</td>
    </tr>
  </table>
</body>
</html>

table {
    border-collapse: collapse;
    font-size: 1.5rem;
  }
  
  tr {
    border-bottom: 1px solid black;
  }
  
  h1 {
    font-size: 2rem;
  }
  
w2-3
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="style.css" />
    <title>Lab2_03</title>
  </head>
  <body>
    <div class="Chart">
      <p>J.Depp</p>
      <div></div>
    </div>
    <div class="Chart">
      <p>D.Washington</p>
      <div></div>
    </div>
    <div class="Chart">
      <p>B.Pitt</p>
      <div></div>
    </div>
    <div class="Chart">
      <p>R.Crowe</p>
      <div></div>
    </div>
    <div class="Chart">
      <p>T.Cruise</p>
      <div></div>
    </div>
  </body>
</html>

body {
    margin: 0;
  }
  
  .Chart {
    width: 95vw;
    height: 100%;
    position: relative;
    padding: 0.25%;
    padding-left: 1%;
    margin: auto;
    overflow: hidden;
    margin-top: 1%;
    margin-bottom: 1%;
  }
  
  .Chart p {
    position: relative;
    color: white;
    z-index: 2;
  }
  
  .Chart div {
    position: absolute;
    top: 0;
    left: 0;
    height: 100%;
    z-index: 1;
    border-radius: 5px;
  }
  
  .Chart:nth-child(1) div {
    width: 65%;
    background-color: red;
  }
  
  .Chart:nth-child(2) div {
    width: 90%;
    background-color: blue;
  }
  
  .Chart:nth-child(3) div {
    width: 50%;
    background-color: green;
  }
  
  .Chart:nth-child(4) div {
    width: 80%;
    background-color: silver;
  }
  
  .Chart:nth-child(5) div {
    width: 75%;
    background-color: gold;
  }
  
w2-4
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="style.css" />
    <title>Lab2_04</title>
  </head>
  <body>
    <div class="calender">
      <div class="allDay">
        <table>
          <tr>
            <th>Sun</th>
            <th>Mo</th>
            <th>Tu</th>
            <th>Wed</th>
            <th>Thr</th>
            <th>Fri</th>
            <th>Sat</th>
          </tr>
          <tr>
            <th class="anotherMonth">26</th>
            <th class="anotherMonth">27</th>
            <th class="anotherMonth">28</th>
            <th class="anotherMonth">29</th>
            <th class="anotherMonth">30</th>
            <th class="anotherMonth">31</th>
            <th>1</th>
          </tr>
          <tr>
            <th>2</th>
            <th>3</th>
            <th>4</th>
            <th>5</th>
            <th>6</th>
            <th>7</th>
            <th>8</th>
          </tr>
          <tr>
            <th>9</th>
            <th>10</th>
            <th>11</th>
            <th>12</th>
            <th>13</th>
            <th>14</th>
            <th>15</th>
          </tr>
          <tr>
            <th>16</th>
            <th>17</th>
            <th>18</th>
            <th>19</th>
            <th>20</th>
            <th>21</th>
            <th>22</th>
          </tr>
          <tr>
            <th>23</th>
            <th>24</th>
            <th>25</th>
            <th>26</th>
            <th>27</th>
            <th>28</th>
            <th>29</th>
          </tr>
          <tr>
            <th>30</th>
            <th>31</th>
            <th class="anotherMonth">1</th>
            <th class="anotherMonth">2</th>
            <th class="anotherMonth">3</th>
            <th class="anotherMonth">4</th>
            <th class="anotherMonth">5</th>
          </tr>
        </table>
      </div>
    </div>
  </body>
</html>

@import url('https://fonts.googleapis.com/css2?family=Aboreto&display=swap');

body {
  margin: 0;
  font-family: 'Aboreto', sans-serif;
}

.calender {
  width: 100vw;
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.allDay {
  width: 30vw;
}

.allDay .anotherMonth {
  color: red;
}

table {
  border-collapse: collapse;
  font-size: 1.5rem;
  width: 100%;
}

th {
  border: 1px solid black;
}

w2-5
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="style.css" />
    <title>Lab2_05</title>
  </head>
  <body>
    <div class="contentbox">
      <div class="adjust">
        <div class="text">
          <p>
            แค่ผ่านมาเพียงสบตาเหมือนว่าใจลอยหลุดไปเธอฆ่าคนด้วยสายตาเพียงแค่เธอนั้นมองมา
            ไม่ปลอดภัยแม้อยู่ไกลสักเท่าไรเหมือนว่าโดนดึงดูดไปหากใครเข้าไปใกล้นานก็ยากที่จะต้านทาน
            อดใจไม่ไหวแค่อยากจะรู้จักก็เธอดันน่ารัก ซะสาแก่ใจเธอมาทำให้ละลาย โดนสาปให้ตายแล้วตาย
            อีกอย่าได้คิดที่จะหลีก ต้องโดนสะกดให้ยิ้มยังคงมองภาพที่เธอ นั่งอยู่โต๊ะริม ใจฉันปริ่มเธอเชือดฉัน
            ได้นิ่ม ๆ ด้วยรอยยิ้มเธอยังไม่ทัน ได้ตั้งตัวแน่ก็มา ฉันไม่กลัวฆ่ากันแล้วก็เอาให้ตายฉันน่ะยอมให้เธอ
            มาทำลายหัวใจของฉันยิ่งลองได้ทบทวนแต่ใจก็ยังหวน ย้อนคืนที่เดิมเธอมาทำให้ละลาย
          </p>
        </div>
        <div class="text">
          <p>
            แค่ผ่านมาเพียงสบตาเหมือนว่าใจลอยหลุดไปเธอฆ่าคนด้วยสายตาเพียงแค่เธอนั้นมองมา
            ไม่ปลอดภัยแม้อยู่ไกลสักเท่าไรเหมือนว่าโดนดึงดูดไปหากใครเข้าไปใกล้นานก็ยากที่จะต้านทาน
            อดใจไม่ไหวแค่อยากจะรู้จักก็เธอดันน่ารัก ซะสาแก่ใจเธอมาทำให้ละลาย โดนสาปให้ตายแล้วตาย
            อีกอย่าได้คิดที่จะหลีก ต้องโดนสะกดให้ยิ้มยังคงมองภาพที่เธอ นั่งอยู่โต๊ะริม ใจฉันปริ่มเธอเชือดฉัน
            ได้นิ่ม ๆ ด้วยรอยยิ้มเธอยังไม่ทัน ได้ตั้งตัวแน่ก็มา ฉันไม่กลัวฆ่ากันแล้วก็เอาให้ตายฉันน่ะยอมให้เธอ
            มาทำลายหัวใจของฉันยิ่งลองได้ทบทวนแต่ใจก็ยังหวน ย้อนคืนที่เดิมเธอมาทำให้ละลาย โดนสาปให้
            ตายแล้วตายอีกอย่าได้คิดที่จะหลีก ต้องโดนสะกดให้ยิ้มยังคงมองภาพที่เธอ นั่งอยู่โต๊ะริม ใจฉันปริ่ม
            เธอเชือดฉันได้นิ่ม ๆ ด้วยรอยยิ้มเธอไม่ใช่แค่ฝัน ที่ฉันต้องตื่นและฉันก็ฝืนหัวใจตัวเองไม่ไหวเธอ
            อยู่ตรงนั้นอยากเพียงแค่ชิดใกล้ห้ามใจ เท่าไรไม่ได้สักทีเธอมาทำให้ละลาย โดนสาปให้ตายแล้ว
            ตายอีกอย่าได้คิดที่จะหลีก ต้องโดนสะกดให้ยิ้มยังคงมองภาพที่เธอ นั่งอยู่โต๊ะริม ใจฉันปริ่ม
            เธอเชือดฉันได้นิ่ม ๆ ด้วยรอยยิ้มเธอแค่ผ่านมาเพียงสบตาเหมือนว่าใจลอยหลุดไปเธอฆ่าคนด้วยสายตา
            เพียงแค่เธอนั้นมองมาไม่ปลอดภัยแม้อยู่ไกลสักเท่าไรเหมือนว่าโดนดึงดูดไปหากใครเข้าไปใกล้
            นานก็ยากที่จะต้านทานอดใจไม่ไหวแค่อยากจะรู้จักก็เธอดันน่ารัก ซะสาแก่ใจเธอมาทำให้ละลาย 
            โดนสาปให้ตายแล้วตายอีกอย่าได้คิดที่จะหลีก ต้องโดนสะกดให้ยิ้มยังคงมองภาพที่เธอ
            นั่งอยู่โต๊ะริม ใจฉันปริ่มเธอเชือดฉันได้นิ่ม ๆ ด้วยรอยยิ้มเธอยังไม่ทัน ได้ตั้งตัวแน่ก็มา
            ฉันไม่กลัวฆ่ากันแล้วก็เอาให้ตายฉันน่ะยอมให้เธอ มาทำลายหัวใจของฉันยิ่งลองได้ทบทวน
            แต่ใจก็ยังหวน ย้อนคืนที่เดิมเธอมาทำให้ละลาย โดนสาปให้ตายแล้วตายอีกอย่าได้คิดที่จะหลีก
          </p>
        </div>
      </div>
    </div>
  </body>
</html>

@import url('https://fonts.googleapis.com/css2?family=Aboreto&family=Alumni+Sans+Pinstripe&family=Kanit:wght@300&display=swap');

body {
    margin: 0;
    font-family: 'Kanit', sans-serif;
  }
  
  .contentbox {
    width: 100vw;
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
  
  .adjust{
    display: flex;
    flex-direction: row;
  }
  
  .text{
    width: 300px;
    height: 350px;
    margin: 2px;
    overflow-y: scroll;
    box-shadow: 0 0 5px #ccc;
    border-radius: 5px;
  }
  
  .text p{
    margin: 0;
    padding: 2%;
  }
  
  w3-1
  <!DOCTYPE html>
  <html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Prompt&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>
    <style>
        * {
            font-family: 'Prompt', sans-serif;
        }
        .container {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
        }
    </style>
</head>

<body>
    <div class="container">
        <form id="myForm" role="form">
            <div class="form-group">
                <label>หมายเลขบัตรประชาชน</label>
                <input type="text" class="form-control" placeholder="หมายเลขบัตรประชาชน" name="Idnumber">
            </div>
            <div>
                <div class="form-group">
                    <label>คำนำหน้านาม</label>
                    <select class="form-control" name="Nameprefix">
                        <option value="null" selected>เลือกคำนำหน้านาม</option>
                        <option value="นาย">นาย</option>
                        <option value="นาง">นาง</option>
                        <option value="นางสาว">นางสาว</option>
                        <option value="เด็กชาย">เด็กชาย</option>
                        <option value="เด็กหญิง">เด็กหญิง</option>
                    </select>
                </div>
                <div class="form-group">
                    <label>ชื่อ นามสกุล</label>
                    <div class="input-group mb-3">
                        <input type="text" class="form-control" placeholder="ชื่อ" name="FirstName">
                        <input type="text" class="form-control" placeholder="นามสกุล" name="LastName">
                    </div>
                </div>
            </div>
            <div class="form-group">
                <label>ที่อยู่</label>
                <input type="text" class="form-control" placeholder="ที่อยู่" name="Address">
            </div>
            <div class="form-group">
                <label>ตำบล/แขวง</label>
                <input type="text" class="form-control" placeholder="ตำบล/แขวง" name="Subdistrict">
            </div>
            <div class="form-group">
                <label>อำเภอ/เขต</label>
                <input type="text" class="form-control" placeholder="อำเภอ/เขต" name="District">
            </div>
            <div class="form-group">
                <label>จังหวัด</label>
                <select name="Province" class="form-control">
                    <option value="null" selected>เลือกจังหวัด</option>
                    <option value="กรุงเทพมหานคร">กรุงเทพมหานคร</option>
                    <option value="กระบี่">กระบี่ </option>
                    <option value="กาญจนบุรี">กาญจนบุรี </option>
                    <option value="กาฬสินธุ์">กาฬสินธุ์ </option>
                    <option value="กำแพงเพชร">กำแพงเพชร </option>
                    <option value="ขอนแก่น">ขอนแก่น</option>
                    <option value="จันทบุรี">จันทบุรี</option>
                    <option value="ฉะเชิงเทรา">ฉะเชิงเทรา </option>
                    <option value="ชัยนาท">ชัยนาท </option>
                    <option value="ชัยภูมิ">ชัยภูมิ </option>
                    <option value="ชุมพร">ชุมพร </option>
                    <option value="ชลบุรี">ชลบุรี </option>
                    <option value="เชียงใหม่">เชียงใหม่ </option>
                    <option value="เชียงราย">เชียงราย </option>
                    <option value="ตรัง">ตรัง </option>
                    <option value="ตราด">ตราด </option>
                    <option value="ตาก">ตาก </option>
                    <option value="นครนายก">นครนายก </option>
                    <option value="นครปฐม">นครปฐม </option>
                    <option value="นครพนม">นครพนม </option>
                    <option value="นครราชสีมา">นครราชสีมา </option>
                    <option value="นครศรีธรรมราช">นครศรีธรรมราช </option>
                    <option value="นครสวรรค์">นครสวรรค์ </option>
                    <option value="นราธิวาส">นราธิวาส </option>
                    <option value="น่าน">น่าน </option>
                    <option value="นนทบุรี">นนทบุรี </option>
                    <option value="บึงกาฬ">บึงกาฬ</option>
                    <option value="บุรีรัมย์">บุรีรัมย์</option>
                    <option value="ประจวบคีรีขันธ์">ประจวบคีรีขันธ์ </option>
                    <option value="ปทุมธานี">ปทุมธานี </option>
                    <option value="ปราจีนบุรี">ปราจีนบุรี </option>
                    <option value="ปัตตานี">ปัตตานี </option>
                    <option value="พะเยา">พะเยา </option>
                    <option value="พระนครศรีอยุธยา">พระนครศรีอยุธยา </option>
                    <option value="พังงา">พังงา </option>
                    <option value="พิจิตร">พิจิตร </option>
                    <option value="พิษณุโลก">พิษณุโลก </option>
                    <option value="เพชรบุรี">เพชรบุรี </option>
                    <option value="เพชรบูรณ์">เพชรบูรณ์ </option>
                    <option value="แพร่">แพร่ </option>
                    <option value="พัทลุง">พัทลุง </option>
                    <option value="ภูเก็ต">ภูเก็ต </option>
                    <option value="มหาสารคาม">มหาสารคาม </option>
                    <option value="มุกดาหาร">มุกดาหาร </option>
                    <option value="แม่ฮ่องสอน">แม่ฮ่องสอน </option>
                    <option value="ยโสธร">ยโสธร </option>
                    <option value="ยะลา">ยะลา </option>
                    <option value="ร้อยเอ็ด">ร้อยเอ็ด </option>
                    <option value="ระนอง">ระนอง </option>
                    <option value="ระยอง">ระยอง </option>
                    <option value="ราชบุรี">ราชบุรี</option>
                    <option value="ลพบุรี">ลพบุรี </option>
                    <option value="ลำปาง">ลำปาง </option>
                    <option value="ลำพูน">ลำพูน </option>
                    <option value="เลย">เลย </option>
                    <option value="ศรีสะเกษ">ศรีสะเกษ</option>
                    <option value="สกลนคร">สกลนคร</option>
                    <option value="สงขลา">สงขลา </option>
                    <option value="สมุทรสาคร">สมุทรสาคร </option>
                    <option value="สมุทรปราการ">สมุทรปราการ </option>
                    <option value="สมุทรสงคราม">สมุทรสงคราม </option>
                    <option value="สระแก้ว">สระแก้ว </option>
                    <option value="สระบุรี">สระบุรี </option>
                    <option value="สิงห์บุรี">สิงห์บุรี </option>
                    <option value="สุโขทัย">สุโขทัย </option>
                    <option value="สุพรรณบุรี">สุพรรณบุรี </option>
                    <option value="สุราษฎร์ธานี">สุราษฎร์ธานี </option>
                    <option value="สุรินทร์">สุรินทร์ </option>
                    <option value="สตูล">สตูล </option>
                    <option value="หนองคาย">หนองคาย </option>
                    <option value="หนองบัวลำภู">หนองบัวลำภู </option>
                    <option value="อำนาจเจริญ">อำนาจเจริญ </option>
                    <option value="อุดรธานี">อุดรธานี </option>
                    <option value="อุตรดิตถ์">อุตรดิตถ์ </option>
                    <option value="อุทัยธานี">อุทัยธานี </option>
                    <option value="อุบลราชธานี">อุบลราชธานี</option>
                    <option value="อ่างทอง">อ่างทอง </option>
              </select>
            </div>
            <div class="form-group">
                <label>รหัสไปรษณีย์</label>
                <input type="text" class="form-control" placeholder="รหัสไปรษณีย์" name="Zipcode">
            </div>
            <button type="button" onclick="validateForm()" class="btn btn-primary">Submit</button>
        </form>
    </div>
</body>
<script src="validator.js"></script>

</html>

  w3-2
  <!DOCTYPE html>
  <html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Prompt&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>
    <style>
        * {
            font-family: 'Prompt', sans-serif;
        }
        .container {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
        }
    </style>
</head>

<body>
    <div class="container">
        <form id="myForm" role="form">
            <div class="form-group">
                <label>หมายเลขบัตรประชาชน</label>
                <input type="text" class="form-control" placeholder="หมายเลขบัตรประชาชน" name="Idnumber">
            </div>
            <div>
                <div class="form-group">
                    <label>คำนำหน้านาม</label>
                    <select class="form-control" name="Nameprefix">
                        <option value="null" selected>เลือกคำนำหน้านาม</option>
                        <option value="นาย">นาย</option>
                        <option value="นาง">นาง</option>
                        <option value="นางสาว">นางสาว</option>
                        <option value="เด็กชาย">เด็กชาย</option>
                        <option value="เด็กหญิง">เด็กหญิง</option>
                    </select>
                </div>
                <div class="form-group">
                    <label>ชื่อ นามสกุล</label>
                    <div class="input-group mb-3">
                        <input type="text" class="form-control" placeholder="ชื่อ" name="FirstName">
                        <input type="text" class="form-control" placeholder="นามสกุล" name="LastName">
                    </div>
                </div>
            </div>
            <div class="form-group">
                <label>ที่อยู่</label>
                <input type="text" class="form-control" placeholder="ที่อยู่" name="Address">
            </div>
            <div class="form-group">
                <label>ตำบล/แขวง</label>
                <input type="text" class="form-control" placeholder="ตำบล/แขวง" name="Subdistrict">
            </div>
            <div class="form-group">
                <label>อำเภอ/เขต</label>
                <input type="text" class="form-control" placeholder="อำเภอ/เขต" name="District">
            </div>
            <div class="form-group">
                <label>จังหวัด</label>
                <select name="Province" class="form-control">
                    <option value="null" selected>เลือกจังหวัด</option>
                    <option value="กรุงเทพมหานคร">กรุงเทพมหานคร</option>
                    <option value="กระบี่">กระบี่ </option>
                    <option value="กาญจนบุรี">กาญจนบุรี </option>
                    <option value="กาฬสินธุ์">กาฬสินธุ์ </option>
                    <option value="กำแพงเพชร">กำแพงเพชร </option>
                    <option value="ขอนแก่น">ขอนแก่น</option>
                    <option value="จันทบุรี">จันทบุรี</option>
                    <option value="ฉะเชิงเทรา">ฉะเชิงเทรา </option>
                    <option value="ชัยนาท">ชัยนาท </option>
                    <option value="ชัยภูมิ">ชัยภูมิ </option>
                    <option value="ชุมพร">ชุมพร </option>
                    <option value="ชลบุรี">ชลบุรี </option>
                    <option value="เชียงใหม่">เชียงใหม่ </option>
                    <option value="เชียงราย">เชียงราย </option>
                    <option value="ตรัง">ตรัง </option>
                    <option value="ตราด">ตราด </option>
                    <option value="ตาก">ตาก </option>
                    <option value="นครนายก">นครนายก </option>
                    <option value="นครปฐม">นครปฐม </option>
                    <option value="นครพนม">นครพนม </option>
                    <option value="นครราชสีมา">นครราชสีมา </option>
                    <option value="นครศรีธรรมราช">นครศรีธรรมราช </option>
                    <option value="นครสวรรค์">นครสวรรค์ </option>
                    <option value="นราธิวาส">นราธิวาส </option>
                    <option value="น่าน">น่าน </option>
                    <option value="นนทบุรี">นนทบุรี </option>
                    <option value="บึงกาฬ">บึงกาฬ</option>
                    <option value="บุรีรัมย์">บุรีรัมย์</option>
                    <option value="ประจวบคีรีขันธ์">ประจวบคีรีขันธ์ </option>
                    <option value="ปทุมธานี">ปทุมธานี </option>
                    <option value="ปราจีนบุรี">ปราจีนบุรี </option>
                    <option value="ปัตตานี">ปัตตานี </option>
                    <option value="พะเยา">พะเยา </option>
                    <option value="พระนครศรีอยุธยา">พระนครศรีอยุธยา </option>
                    <option value="พังงา">พังงา </option>
                    <option value="พิจิตร">พิจิตร </option>
                    <option value="พิษณุโลก">พิษณุโลก </option>
                    <option value="เพชรบุรี">เพชรบุรี </option>
                    <option value="เพชรบูรณ์">เพชรบูรณ์ </option>
                    <option value="แพร่">แพร่ </option>
                    <option value="พัทลุง">พัทลุง </option>
                    <option value="ภูเก็ต">ภูเก็ต </option>
                    <option value="มหาสารคาม">มหาสารคาม </option>
                    <option value="มุกดาหาร">มุกดาหาร </option>
                    <option value="แม่ฮ่องสอน">แม่ฮ่องสอน </option>
                    <option value="ยโสธร">ยโสธร </option>
                    <option value="ยะลา">ยะลา </option>
                    <option value="ร้อยเอ็ด">ร้อยเอ็ด </option>
                    <option value="ระนอง">ระนอง </option>
                    <option value="ระยอง">ระยอง </option>
                    <option value="ราชบุรี">ราชบุรี</option>
                    <option value="ลพบุรี">ลพบุรี </option>
                    <option value="ลำปาง">ลำปาง </option>
                    <option value="ลำพูน">ลำพูน </option>
                    <option value="เลย">เลย </option>
                    <option value="ศรีสะเกษ">ศรีสะเกษ</option>
                    <option value="สกลนคร">สกลนคร</option>
                    <option value="สงขลา">สงขลา </option>
                    <option value="สมุทรสาคร">สมุทรสาคร </option>
                    <option value="สมุทรปราการ">สมุทรปราการ </option>
                    <option value="สมุทรสงคราม">สมุทรสงคราม </option>
                    <option value="สระแก้ว">สระแก้ว </option>
                    <option value="สระบุรี">สระบุรี </option>
                    <option value="สิงห์บุรี">สิงห์บุรี </option>
                    <option value="สุโขทัย">สุโขทัย </option>
                    <option value="สุพรรณบุรี">สุพรรณบุรี </option>
                    <option value="สุราษฎร์ธานี">สุราษฎร์ธานี </option>
                    <option value="สุรินทร์">สุรินทร์ </option>
                    <option value="สตูล">สตูล </option>
                    <option value="หนองคาย">หนองคาย </option>
                    <option value="หนองบัวลำภู">หนองบัวลำภู </option>
                    <option value="อำนาจเจริญ">อำนาจเจริญ </option>
                    <option value="อุดรธานี">อุดรธานี </option>
                    <option value="อุตรดิตถ์">อุตรดิตถ์ </option>
                    <option value="อุทัยธานี">อุทัยธานี </option>
                    <option value="อุบลราชธานี">อุบลราชธานี</option>
                    <option value="อ่างทอง">อ่างทอง </option>
              </select>
            </div>
            <div class="form-group">
                <label>รหัสไปรษณีย์</label>
                <input type="text" class="form-control" placeholder="รหัสไปรษณีย์" name="Zipcode">
            </div>
            <button type="button" onclick="validateForm()" class="btn btn-primary">Submit</button>
        </form>
    </div>
</body>
<script src="validator.js"></script>

</html>

function validateForm() {
    let idnumber = document.forms.myForm.Idnumber.value;
    let nameprefix = document.forms.myForm.Nameprefix.value;
    let fname = document.forms.myForm.FirstName.value;
    let lname = document.forms.myForm.LastName.value;
    let address = document.forms.myForm.Address.value;
    let subdistrict = document.forms.myForm.Subdistrict.value;
    let district = document.forms.myForm.District.value;
    let province = document.forms.myForm.Province.value;
    let zipcode = document.forms.myForm.Zipcode.value;
    if (idnumber.length != 13 || !checkNumber(idnumber)) {
        alert("หมายเลขบัตรประชาชนต้องเป็นตัวเลข จำนวน 13 หลัก")
    }
    else if (nameprefix == "null") {
        alert("ต้องเลือกคำนำหน้านาม")
    }
    else if (fname.length < 2 || fname.length > 20 || !checkString(fname)) {
        alert("ชื่อต้องเป็นตัวอักษร ความยาวระหว่าง 2-20 ตัวอักษร");
    }
    else if (lname.length < 2 || lname.length > 30 || !checkString(lname)) {
        alert("นามสกุลต้องเป็นตัวอักษร ความยาวระหว่าง 2-30 ตัวอักษร");
    }
    else if (address.length <= 5) {
        alert("ที่อยู่ต้องความยาวไม่ต่ำกว่า 5 ตัวอักษร")
    }
    else if (subdistrict.length <= 2 || !checkString(subdistrict)) {
        alert("ตำบล/แขวงต้องเป็นตัวอักษร ความยาวไม่ต่ำกว่า 2 ตัวอักษร")
    }
    else if (district.length <= 2 || !checkString(district)) {
        alert("อำเภอ/เขตต้องเป็นตัวอักษร ความยาวไม่ต่ำกว่า 2 ตัวอักษร")
    }
    else if (province == "null") {
        alert("ต้องเลือกจังหวัด")
    }
    else if (zipcode.length != 5 || !checkNumber(zipcode)) {
        alert("รหัสไปรษณีย์ต้องเป็นตัวเลข จำนวน 5 หลัก")
    }
}

function checkString(string) {
    for (let i = 0; i < string.length; i++) {
        if (string[i] in ["0", "1", "2", "3", "4", "5", "6", "7", "8", "9"]) {
            return false
        }
    }
    return true
}

function checkNumber(string) {
    for (let i = 0; i < string.length; i++) {
        if (!(string[i] in ["0", "1", "2", "3", "4", "5", "6", "7", "8", "9"])) {
            return false
        }
    }
    return true
}

  w3-3
  <!DOCTYPE html>
  <html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="style.css" rel="stylesheet">
    <title>Document</title>
</head>

<body>
    <div class="main">
        <div class="container">
            <div class="pic" id="pic0"></div>
            <div class="pic" id="pic1"></div>
            <div class="pic" id="pic2"></div>
            <div class="pic" id="pic3"></div>
        </div>
        <button type="button" onClick="rotate()">Rotate</button>
    </div>
</body>
<script type="text/javascript">
    let pic = document.getElementsByClassName("pic")
    let arrpic = ['http://10.0.15.20/312lab3/images/1.png', 'http://10.0.15.20/312lab3/images/2.png', 'http://10.0.15.20/312lab3/images/3.png', 'http://10.0.15.20/312lab3/images/4.png']
    let arrnum = ['1', '2', '3', '4']
    let j = 0;
    function rotate() {
        arrnum[1] = arrpic[0]
        arrnum[2] = arrpic[3]
        arrnum[3] = arrpic[1]
        arrnum[0] = arrpic[2]
        Array.prototype.forEach.call(pic, function (element, index) {
            pic[index].style.backgroundImage = "url(" + arrnum[j] + ")"
            j++
            if (j > 3) { j = 0 }
        });
        arrpic[0] = arrnum[0]
        arrpic[1] = arrnum[1]
        arrpic[2] = arrnum[2]
        arrpic[3] = arrnum[3]
    }
</script>

</html>

* {
    margin: 0;
}

.container {
    width: 20vw;
    display: grid;
    grid-template-columns: auto auto;
}

#pic0, #pic1, #pic2, #pic3 {
    width: 10vw;
    height: 10vw;
    background-size: contain;
}

#pic0 {
    background-image: url('http://10.0.15.20/312lab3/images/1.png');
}

#pic1 {
    background-image: url('http://10.0.15.20/312lab3/images/2.png');
}

#pic2 {
    background-image: url('http://10.0.15.20/312lab3/images/3.png');
}

#pic3 {
    background-image: url('http://10.0.15.20/312lab3/images/4.png');
}

  w3-4
  <!DOCTYPE html>
  <html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="style.css" rel="stylesheet">
    <title>Document</title>
</head>
<body>
    <div class="container">
        <div class="skills" id="math">Math</div>
      </div>
      <div class="container">
        <div class="skills" id="thai">Thai</div>
      </div>
      <div class="container">
        <div class="skills" id ="english">English</div>
      </div>
      <div class="container">
        <div class="skills" id="science">Science</div>
      </div>
      <div class="container">
        <div class="skills" id="social">Social</div>
      </div>
    </div>
    <button type="button" onClick="Show()">View Chart</button>
    <script type="text/javascript">
        function Show(){
            document.getElementById("math").style.width = "10%";
            document.getElementById("thai").style.width = "12%";
            document.getElementById("english").style.width = "8%";
            document.getElementById("science").style.width = "14%";
            document.getElementById("social").style.width = "13%";
        }
    </script>
</div>
</body>
</html>

* {box-sizing: border-box}

.skills {
  text-align: left;
  padding-left: 5px;
  padding-top: 10px;
  padding-bottom: 10px;
  color: white;
  margin-bottom: 10px;
  background-color: red;
  width: 3%;
}

  w3-5
  <!DOCTYPE html>
  <html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Prompt&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <div class="row">
            <div class="column">
                <h1>Create your card</h1>
                <form id="myForm" role="form">
                    <div class="form-group">
                        <label>Full Name</label>
                        <input type="text" class="form-control" placeholder="Enter your name" name="FullName">
                    </div>
                    <div class="form-group">
                        <label>Phone</label>
                        <input type="tel" class="form-control" placeholder="Phone Number" name="Phone">
                    </div>
                    <div class="form-group">
                        <label>Email</label>
                        <input type="text" class="form-control" placeholder="Enter your email" name="Email">
                    </div>
                    <div class="form-group">
                        <label>Company</label>
                        <input type="text" class="form-control" placeholder="Enter your company" name="Company">
                    </div>
                    <button type="button" onclick="createForm()" class="btn btn-primary">Create</button>
                    </div>
                </form>
            <div class="column2">
                <h4>Your card here</h4>
                <div class="card">
                    <p><span id='name'></span></p>
                </div>
            </div>
        </div>
        <script type="text/javascript">
            function createForm(){
                var x = document.getElementById("myForm");
                var text = "";
                var i;
                for (i = 0; i < x.length ;i++) {
                    text += x.elements[i].value + "<br>";
                     }
                document.getElementById("name").innerHTML = text;
            }
        </script>
</body>
</html>
  
* {
    font-family: 'Prompt', sans-serif;
}
.container {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    padding: 30px;
    background-color: rgb(214, 228, 242);
}
.column{
    width:50%;
    background-color: rgb(255, 255, 255);
    padding: 30px;
}
.column2{
    padding-top: 50px;
    width:50%;
    text-align: center;
}

.card{
    font-size: 20px;
    padding: 20px;
    text-align: left;
    margin: auto;
    margin-top: 50px;
    width: 390px;
    height: 220px;
    background-color: rgb(236, 236, 235);
    box-shadow: 9px 10px 7px -5px rgba(0,0,0,0.5);
}

.btn{
    width: 100%;
}

w4-1
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="style.css">
  <title>lab4-1</title>
</head>
<body>
  <div>
    <label for="value1">Value 1:</label>
    <input type="number" id="value1">
  </div>
  <div> 
    <label for="value2">Value 2:</label>
    <input type="number" id="value2">
  </div>
  <button class="btn">Calculate</button>
  <div id="result">
    <p>Result:</p>
  </div>
  <div id="history">
  </div>
  <script src="script.js"></script>
</body>
<script>
const value1 = document.getElementById('value1');
const value2 = document.getElementById('value2');
const result = document.getElementById('result');
const btn = document.getElementsByClassName('btn')[0];
const history = document.getElementById('history');

btn.addEventListener('click', () => {
  let newElement = document.createElement('p');
  let itIsREsult = Number(value1.value) + Number(value2.value);
  newElement.innerHTML = `${value1.value} + ${value2.value} = ${itIsREsult}`;
  result.innerHTML = `Result: ${itIsREsult}`;
  history.appendChild(newElement);
});
</script>
<style>
div, button {
    margin-bottom: 2rem;
  }
</style>
</html>

w4-2
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>lab4-2</title>
</head>

<body>
    <script src="script.js"></script>
</body>
<script>
    let lang = {
        th: {
            name: 'ชื่อ',
            surname: 'นามสกุล',
            country: ['ประเทศ', [
                { name: 'เลือกประเทศ', value: '' },
                { name: 'ไทย', value: 'th' },
                { name: 'เวียดนาม', value: 'vn' },
                { name: 'ลาว', value: 'la' },
                { name: 'มาเลเซีย', value: 'my' },
                { name: 'สิงคโปร์', value: 'sg' },
                { name: 'ฟิลิปปินส์', value: 'ph' },
                { name: 'เมียนมา', value: 'mm' },
                { name: 'กัมพูชา', value: 'kh' },
                { name: 'บรูไน', value: 'bn' },
            ]],
            btnlabel: 'เปลี่ยนเป็นภาษาอังกฤษ',
        },
        en: {
            name: 'Firstname',
            surname: 'Lastname',
            country: ['Country', [
                { name: 'Choose country', value: '' },
                { name: 'Thailand', value: 'th' },
                { name: 'Vietnam', value: 'vn' },
                { name: 'Laos', value: 'la' },
                { name: 'Malaysia', value: 'my' },
                { name: 'Singapore', value: 'sg' },
                { name: 'Philippines', value: 'ph' },
                { name: 'Myanmar', value: 'mm' },
                { name: 'Cambodia', value: 'kh' },
                { name: 'Brunei', value: 'bn' },
            ]],
            btnlabel: 'Change to Thai',
        }
    }
    function init(choose_lang) {
        document.body.innerHTML = '';
        const nameDiv = document.createElement('div');
        const nameLabel = document.createElement('label');
        nameLabel.for = 'name';
        nameLabel.innerHTML = `${lang[choose_lang].name}: `;
        const nameInput = document.createElement('input');
        nameInput.type = 'text';
        nameInput.id = 'name';
        nameDiv.appendChild(nameLabel);
        nameDiv.appendChild(nameInput);
        const surnameDiv = document.createElement('div');
        const surnameLabel = document.createElement('label');
        surnameLabel.for = 'surname';
        surnameLabel.innerHTML = `${lang[choose_lang].surname}: `;
        const surnameInput = document.createElement('input');
        surnameInput.type = 'text';
        surnameInput.id = 'surname';
        surnameDiv.appendChild(surnameLabel);
        surnameDiv.appendChild(surnameInput);
        const countryDiv = document.createElement('div');
        const countryLabel = document.createElement('label');
        countryLabel.for = 'country';
        countryLabel.innerHTML = `${lang[choose_lang].country[0]}: `;
        const countrySelect = document.createElement('select');
        for (let index = 0; index < lang[choose_lang].country[1].length; index++) {
            const country = lang[choose_lang].country[1][index];
            let option = document.createElement('option');
            option.value = country.value;
            option.innerHTML = country.name;
            countrySelect.appendChild(option);
        }
        countryDiv.appendChild(countryLabel);
        countryDiv.appendChild(countrySelect);
        const btn = document.createElement('button');
        btn.innerHTML = lang[choose_lang].btnlabel;
        btn.addEventListener('click', () => {
            if (choose_lang === 'th') {
                init('en');
            } else {
                init('th');
            }
        });
        document.body.appendChild(nameDiv);
        document.body.appendChild(surnameDiv);
        document.body.appendChild(countryDiv);
        document.body.appendChild(btn);
    }

    init('th');
</script>

</html>

w4-3
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>lab4-3</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <h1>ลงทะเบียนร่วมงาน</h1>
    <input type="number" id="std_number" placeholder="รหัสนักศึกษา">
    <input type="text" id="std_name" placeholder="ชื่อ">
    <input type="text" id="std_surname" placeholder="นามสกุล">
    <button id="btn_submit">ลงทะเบียน</button>
    <hr>
    <table>
        <thead>
            <th>ลำดับที่</th>
            <th>รหัสนักศึกษา</th>
            <th>ชื่อ</th>
            <th>นามสกุล</th>
        </thead>
        <tbody id="insertHere">

        </tbody>
    </table>
    <script src="script.js"></script>
</body>
<script>
    const std_number = document.getElementById('std_number');
    const std_name = document.getElementById('std_name');
    const std_surname = document.getElementById('std_surname');
    const insertHere = document.getElementById('insertHere');
    const std_btn = document.getElementById('btn_submit');

    let order = 0;

    std_btn.addEventListener('click', () => {
        order++;
        let newTr = document.createElement('tr');
        let newTd1 = document.createElement('td');
        let newTd2 = document.createElement('td');
        let newTd3 = document.createElement('td');
        let newTd4 = document.createElement('td');
        newTd1.innerHTML = order;
        newTd2.innerHTML = std_number.value;
        newTd3.innerHTML = std_name.value;
        newTd4.innerHTML = std_surname.value;
        newTr.appendChild(newTd1);
        newTr.appendChild(newTd2);
        newTr.appendChild(newTd3);
        newTr.appendChild(newTd4);
        insertHere.appendChild(newTr);
    });

</script>
<style>
    th {
        background-color: rgb(247, 255, 190);
    }

    table {
        background-color: rgb(235, 235, 235);

    }

    h1 {
        text-align: center;
    }
</style>

</html>

w4-4
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>lab4-4</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
    <input type="number" id="number" placeholder="num">
    <label for="">:</label>
    <button id="submit" onclick="function1()">submit</button>
    <div id="insertHere">
    </div>
    <script src="script.js"></script>
</body>
</html>

function function1(){
    const insertHere = document.getElementById('insertHere');
    let number1 = document.getElementById('number').value;
    let bol = true;
    let TT = document.createElement('div');
    TT.classList.add('box');
    for (let i = 0; i < number1; i++) {
        console.log(i)
        console.log(insertHere)
        let tt = document.createElement('div');
        if (bol){
            tt.classList.add('whitebox');
            bol = false;
        }
        else {
            tt.classList.add('blackbox');
            bol = true;
        }
        TT.appendChild(tt);
        if ((((i + 1) % 8) == 0)){
            insertHere.appendChild(TT);
            TT = document.createElement('div');
            TT.classList.add('box');
            if (bol){
            bol = false;
            }
            else{
                bol = true;
            }
        }
    }
    insertHere.appendChild(TT);
};

.whitebox{
    width: 10vw;
    height: 10vw;
    background-color: aliceblue;
    border: 1px solid black;
}
.blackbox{
    width: 10vw;
    height: 10vw;
    background-color: black;
    border: 1px solid black;
}
.box{
    display: flex;
}

w4-5
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>lab4-5</title>
    <script src="script.js"></script>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>
</head>

<body>
    <div class="contaniner-fluid overflow-hidden bg-light">
        <br>
        <div class="d-flex justify-content-center">
            <h1>PANDA FOOD <div class="p-2 d-inline bg-warning rounded"> HUB</div>
            </h1>
        </div>
        <div class="d-flex justify-content-center">
            <p>Delivery by PandaHub.</p>
        </div>
        <div class="d-flex row">
            <div class="col-md-7">
                <div class="card ml-5">
                    <div class="row">
                        <div class="col-md-4 m-0 p-0 h-1">
                            <img src="https://s.isanook.com/gu/0/rp/r/w1240/ya0xa0m1w0/aHR0cHM6Ly9zLmlzYW5vb2suY29tL2d1LzAvdWkvNS8yNjc1MC8yNzQ5OThfXzIwMDEyMDE0MDI0MjIyLmpwZw==.jpg"
                                class="img-fluid rounded float-left" alt="...">
                        </div>
                        <div class="col-md-7">
                            <div class="card-body">
                                <h5 class="card-title">ส้มตำ</h5>
                                <p class="card-text text-black-50">Delivery by PandaHub.</p>
                                <button type="button" onclick="addOrder(0)" class="btn btn-warning mt-3 float-right">Add
                                    Order</button>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="card ml-5 mt-4">
                    <div class="row">
                        <div class="col-md-4 m-0 p-0 h-1">
                            <img src="https://www.unileverfoodsolutions.co.th/dam/global-ufs/mcos/SEA/calcmenu/recipes/TH-recipes/chicken-&-other-poultry-dishes/%E0%B9%84%E0%B8%81%E0%B9%88%E0%B8%A2%E0%B9%88%E0%B8%B2%E0%B8%87/%E0%B9%84%E0%B8%81%E0%B9%88%E0%B8%A2%E0%B9%88%E0%B8%B2%E0%B8%87_header.jpg"
                                class="img-fluid rounded float-left" alt="...">
                        </div>
                        <div class="col-md-7">
                            <div class="card-body">
                                <h5 class="card-title">ไก่ย่าง</h5>
                                <p class="card-text text-black-50">Delivery by PandaHub.</p>
                                <button type="button" onclick="addOrder(1)" class="btn btn-warning mt-3 float-right">Add
                                    Order</button>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="card ml-5 mt-4">
                    <div class="row">
                        <div class="col-md-4 m-0 p-0">
                            <img src="https://image.bangkokbiznews.com/uploads/images/md/2022/03/6f35HeEnuqtxJn5RkAG0.webp?x-image-process=style/LG"
                                class="img-fluid rounded float-left" alt="...">
                        </div>
                        <div class="col-md-7">
                            <div class="card-body">
                                <h5 class="card-title">ลาบเนื้อ</h5>
                                <p class="card-text text-black-50">Delivery by PandaHub.</p>
                                <button type="button" onclick="addOrder(2)" class="btn btn-warning mt-3 float-right">Add
                                    Order</button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card-header bg-primary text-white d-flex justify-content-center">
                    รายการออเดอร์
                </div>
                <ul class="list-group list-group-flush" id="list">
                </ul>
            </div>
        </div>
        <br>
        <div class="bg-light p-2"></div>
    </div>
</body>

</html>

let order = [["ส้มตำ", 0], ["ไก่ย่าง", 0], ["ลาบเนื้อ", 0]];

const addOrder = (menu) => {
    let parent = document.getElementById("list");
    let addFood = document.createElement("li");
    addFood.classList.add("list-group-item");
    let addNumber = document.createElement("div");
    addNumber.classList.add("float-right");
    for (let i = 0; i < 3; i++) {
        if (menu == i) {
            order[i][1]++;
            if (order[i][1] == 1) {
                addNumber.setAttribute('id', "food"+i);
                addNumber.innerText = "x"+order[i][1]
                addFood.appendChild(document.createTextNode(order[i][0]))
                addFood.appendChild(addNumber)
                parent.appendChild(addFood)
            }
            else {document.getElementById("food"+i).innerText = "x"+order[i][1];}
        }
    }
}

w4-profile
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href='https://css.gg/chevron-down-o.css' rel='stylesheet'>
    <link href='https://css.gg/chevron-left.css' rel='stylesheet'>
    <link href='https://css.gg/chevron-right.css' rel='stylesheet'>
    <title>Profile_64070056</title>
    <style>
        * {
            margin: 0;
            padding: 0;
        }

        html {
            scroll-behavior: smooth;
        }

        .section {
            width: 100%;
            height: 300%;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
        }

        #profile {
            background-color: #FF914D;
            background-size: cover;
            height: 100%;
            width: 100%;
            position: relative;
            background-image: url(https://cdn.discordapp.com/attachments/968551941569413140/1015931547565695036/unknown.png);
        }

        .profile-text {
            position: absolute;
            padding: 2em;
            left: 55%;
            top: 40%;
            color: #FFDE59;
            background-color: #FF914D;
            text-align: center;
        }

        .profile-text h1 {
            font-family: 'DM Serif Display', serif;
            font-size: 4em;
        }

        .profile-text h2 {
            display: flex;
            justify-content: center;
            font-family: 'Noto Sans Thai', sans-serif;
            font-size: 2em;
        }

        .box {
            width: 80%;
            height: 200%;
            display: flex;
            border-radius: 10px;
            flex-direction: column;
            text-align: center;
            background-color: #F8C06B;
        }

        .textmain {
            margin-top: 3em;
            font-size: 1.5em;
            color: #FF914D;
        }

        .text {
            font-family: 'Noto Sans Thai', sans-serif;
            font-size: 20px;
            margin-top: 4em;
            color: white;
        }
    </style>
</head>

<body>

    <div id=profile>
        <div class="profile-text">
            <h1>
                My Profile
            </h1>
            <h2>
                Nuttapat Meenpran<br>( นัธพัฒน์ หมีนพราน )<br> 64070056
            </h2>
        </div>
    </div>

    <div class="section" style="background-color:#FF914D;">
        <div class="box">
            <div class="textmain">
                <h1>
                    My Profile
                </h1>
            </div>
            <div class="text">
                <h3>ข้อมูลส่วนตัว </h3><br>นาย นัธพัฒน์ หมีนพราน ชื่อเล่น เซฟ<br>
                เกิดวันที่18/09/2545 อายุ 19 ปี
            </div>
            <div class="text">
                <h3>การศึกษา </h3><br><img
                    src="https://scontent.fbkk29-3.fna.fbcdn.net/v/t39.30808-6/296292821_421971803279999_2310295100221413393_n.jpg?_nc_cat=110&ccb=1-7&_nc_sid=09cbfe&_nc_eui2=AeHLf65_ZcC36IGaguZ4m_fybqlDr3DSfjhuqUOvcNJ-ODJoYq5ScuTn5htqDs5zIoJHD8lbECd7lExpVT15RWFJ&_nc_ohc=OWw4buwHg6UAX8JT6lt&_nc_ht=scontent.fbkk29-3.fna&oh=00_AT_nhMRQrvsUz4NvR9aP4R08mz_bGcoBUzpL8Qubu7PSvQ&oe=6319C72A"
                    width="150" height="150">
                <br>- ช่วงอนุบาลและประถมจบจากโรงเรียนแย้มสอาด รังสิต <br>
                <img src="https://skr.ac.th/info/dist/img/skr.png" width="150" height="150"><br>
                - ช่วงมัธยมจบจากโรงเรียนสวนกุหลาบวิทยาลัย รังสิต (SKR)<br>
                <img src="https://www.print3dd.com/wp-content/uploads/2016/09/kmitl-logoThai-1.png" width="150"
                    height="150"><br>
                - มาต่อปริญญาตรีที่มหาวิทยาลัยที่สถาบันเทคโนโลยีพระจอมเกล้าเจ้าคุณทหาร ลาดกระบัง (KMITL)
                และกำลังศึกษาอยู่
            </div>
            <div class="text">
                <h3>งานอดิเรก </h3><br>- ดูหนัง ดูซีรีย์ <br>- ฟังเพลง <br>- เล่นกีต้าร์ <br>
                - ว่ายน้ำ <br>- เล่นฟุตบอลและบาสเกตบอล
            </div>
            <div class="text">
                <h3>กีฬาที่ชอบ </h3><br><img src="https://img.pptvhd36.com/thumbor/2020/05/21/6a86a8f60b.jpg" width="180" height="150"><br>- ฟุตบอล 
                <br><img src="https://www.thatasport.com/wp-content/uploads/2018/04/B-logo-Molten-GL7X.jpg" width="180" height="180"><br>- บาสเกตบอล 
                <br><img src="https://s3.theasianparent.com/cdn-cgi/image/width=700,quality=95/tap-assets-prod/wp-content/uploads/sites/25/2021/11/badminton-for-kids3.jpg" width="180" height="150"><br>- แบตมินตัน
            </div>
            <div class="text">
                <h3>อาชีพที่อยากทำ </h3><br>อยากเป็นโปรแกรมเมอร์<br>และอยากมีธุรกิจส่วนตัวเป็นของตัวเอง
                <br>เช่นทำร้านอาหารและเบเกอรี่เพราะว่าชอบทำอาหารและขนมเค้ก
            </div>
        </div>
    </div>
</body>

</html>
w5-1
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>lab5-1</title>
</head>
<body>
  <script src="script.js"></script>
</body>
</html>

.json
[
  {
    "gender": "Female",
    "lastname": "Davolio",
    "firstname": "Nancy",
    "position": "Sales Representative",
    "address": "507 - 20th Ave. E. Apt. 2A"
  },
  {
    "gender": "Male",
    "lastname": "Fuller",
    "firstname": "Andrew",
    "position": "Vice President, Sales",
    "address": "908 W. Capital Way"
  },
  {
    "gender": "Female",
    "lastname": "Leverling",
    "firstname": "Janet",
    "position": "Sales Representative",
    "address": "722 Moss Bay Blvd"
  },
  {
    "gender": "Female",
    "lastname": "Peacock",
    "firstname": "Margarct",
    "position": "Sales Representative",
    "address": "4110 Old Redmond Rd."
  },
  {
    "gender": "Male",
    "lastname": "Buchanan",
    "firstname": "Steven",
    "position": "Sales Manager",
    "address": "14 Garrett Hill"
  },
  {
    "gender": "Male",
    "lastname": "Suyama",
    "firstname": "Michael",
    "position": "Sales Representative",
    "address": "Coventry House Miner Rd."
  },
  {
    "gender": "Male",
    "lastname": "King",
    "firstname": "Robert",
    "position": "Sales Representative",
    "address": "Edgeham Hollow Winchester Way"
  },
  {
    "gender": "Female",
    "lastname": "Callahan",
    "firstname": "Laura",
    "position": "Inside Sales Coodinator",
    "address": "4726 - 11th Ave. N.E."
  },
  {
    "gender": "Female",
    "lastname": "Dodsworth",
    "firstname": "Anne",
    "position": "Sales Representative",
    "address": "7 Houndstooth Rd."
  }
]

script.js

fetch("info.json")
  .then((response) => response.json())
  .then((data) => {
    for (let index = 0; index < data.length; index++) {
      const element = data[index];
      document.write(
        `${index + 1} <b>${element.firstname} ${element.lastname}</b> (${
          element.gender
        }) is a ${element.position}, ${element.address}<br>`
      );
    }
  });

w5-2
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>lab5-2</title>
</head>
<body>
  <h1>
    Quiz 1
  </h1>
  <div id="content">
  </div>
  <script src="script.js"></script>
</body>
</html>

[
    {
        "question": "Britain and France declared war on Germany on 3 September 1939 after the German invasion of which country?",
        "answers": {
            "a": "Denmark",
            "b": "Poland",
            "c": "Czechoslovakia",
            "correct": "b"
        }
    },
    {
        "question": "When did Germany invade the USSR?",
        "answers": {
            "a": "May 1940",
            "b": "May 1940",
            "c": "June 1941",
            "correct": "c"
        }
    },
    {
        "question": "What was the name of Britain's new bombing policy in May 1942 that targeted German cities?",
        "answers": {
            "a": "Tactical bombing",
            "b": "Area bombing",
            "c": "Precision bombing",
            "correct": "b"
        }
    },
    {
        "question": "What was the name of the army officer who planted the bomb that almost killed Hitler in July 1944?",
        "answers": {
            "a": "Colonel Stauffenberg",
            "b": "Field Marshal Rommel",
            "c": "Colonel Tresckow",
            "correct": "a"
        }
    },
    {
        "question": "To which country in Nazi occupied Europe were Jews sent as part of the 'Final Solution' agreed at the Wannsee Conference?",
        "answers": {
            "a": "Poland",
            "b": "Czechoslovakia",
            "c": "Estonia",
            "correct": "a"
        }
    },
    {
        "question": "What was the name of the biggest Nazi death camp?",
        "answers": {
            "a": "Treblinka",
            "b": "Sobibor",
            "c": "Auschwitz-Birkenau",
            "correct": "c"
        }
    },
    {
        "question": "Where did German army lose its first battle of the war in Europe, in early 1943?",
        "answers": {
            "a": "Moscow",
            "b": "Stalingrad",
            "c": "Leningrad",
            "correct": "b"
        }
    },
    {
        "question": "When did Germany surrender to the Allies, ending World War Two in Europe?",
        "answers": {
            "a": "March 1945",
            "b": "May 1945",
            "c": "August 1945",
            "correct": "b"
        }
    },
    {
        "question": "In which German city were the trials of those Nazis suspected of war crimes held from late 1945?",
        "answers": {
            "a": "Berlin",
            "b": "Dresden",
            "c": "Nuremberg",
            "correct": "c"
        }
    },
    {
        "question": "Who was the first Chancellor of the Federal Republic of Germany (West Germany)?",
        "answers": {
            "a": "Wilhelm Pieck",
            "b": "Konrad Adenauer",
            "c": "Willy Brandt",
            "correct": "b"
        }
    }
]

const content = document.getElementById("content");

const main = async () => {
  const response = await (await fetch("questionAnswerData.json")).json();
  for (let index = 0; index < response.length; index++) {
    const element = response[index];
    let question = document.createElement("div");
    const title = document.createElement("p");
    title.innerText = `${index + 1} ) ${element.question}`;
    question.appendChild(title);
    for (const key in element.answers) {
      if (key === "correct") {
        continue;
      }
      let answer = document.createElement("input");
      answer.type = "radio";
      answer.name = `answer${index}`;
      answer.value = key;
      answer.id = key;
      let label = document.createElement("label");
      label.htmlFor = key;
      label.innerText = element.answers[key];
      console.log(element.answers)
      if (element.answers.correct === key) {
        answer.checked = true;
      }
      question.appendChild(answer);
      question.appendChild(label);
      question.appendChild(document.createElement("br"));
    }
    content.appendChild(question);
  }
};

main();

w5-3
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>lab5-3</title>
</head>
<body>
  <div id="content"></div>
  <script src="script.js"></script>
</body>
</html>

[
    {
        "name": "Brazil",
        "topLevelDomain": [
            ".br"
        ],
        "alpha2Code": "BR",
        "alpha3Code": "BRA",
        "callingCodes": [
            "55"
        ],
        "capital": "Brasília",
        "altSpellings": [
            "BR",
            "Brasil",
            "Federative Republic of Brazil",
            "República Federativa do Brasil"
        ],
        "region": "Americas",
        "subregion": "South America",
        "population": 206135893,
        "latlng": [
            -10.0,
            -55.0
        ],
        "demonym": "Brazilian",
        "area": 8515767.0,
        "gini": 54.7,
        "timezones": [
            "UTC-05:00",
            "UTC-04:00",
            "UTC-03:00",
            "UTC-02:00"
        ],
        "borders": [
            "ARG",
            "BOL",
            "COL",
            "GUF",
            "GUY",
            "PRY",
            "PER",
            "SUR",
            "URY",
            "VEN"
        ],
        "nativeName": "Brasil",
        "numericCode": "076",
        "currencies": [
            {
                "code": "BRL",
                "name": "Brazilian real",
                "symbol": "R$"
            }
        ],
        "languages": [
            {
                "iso639_1": "pt",
                "iso639_2": "por",
                "name": "Portuguese",
                "nativeName": "Português"
            }
        ],
        "translations": {
            "de": "Brasilien",
            "es": "Brasil",
            "fr": "Brésil",
            "ja": "ブラジル",
            "it": "Brasile",
            "br": "Brasil",
            "pt": "Brasil",
            "nl": "Brazilië",
            "hr": "Brazil",
            "fa": "برزیل"
        },
        "flag": "http://10.0.15.20/lab5/flags/bra.svg",
        "regionalBlocs": [
            {
                "acronym": "USAN",
                "name": "Union of South American Nations",
                "otherAcronyms": [
                    "UNASUR",
                    "UNASUL",
                    "UZAN"
                ],
                "otherNames": [
                    "Unión de Naciones Suramericanas",
                    "União de Nações Sul-Americanas",
                    "Unie van Zuid-Amerikaanse Naties",
                    "South American Union"
                ]
            }
        ],
        "cioc": "BRA"
    },
    {
        "name": "China",
        "topLevelDomain": [
            ".cn"
        ],
        "alpha2Code": "CN",
        "alpha3Code": "CHN",
        "callingCodes": [
            "86"
        ],
        "capital": "Beijing",
        "altSpellings": [
            "CN",
            "Zhōngguó",
            "Zhongguo",
            "Zhonghua",
            "People's Republic of China",
            "中华人民共和国",
            "Zhōnghuá Rénmín Gònghéguó"
        ],
        "region": "Asia",
        "subregion": "Eastern Asia",
        "population": 1377422166,
        "latlng": [
            35.0,
            105.0
        ],
        "demonym": "Chinese",
        "area": 9640011.0,
        "gini": 47.0,
        "timezones": [
            "UTC+08:00"
        ],
        "borders": [
            "AFG",
            "BTN",
            "MMR",
            "HKG",
            "IND",
            "KAZ",
            "PRK",
            "KGZ",
            "LAO",
            "MAC",
            "MNG",
            "PAK",
            "RUS",
            "TJK",
            "VNM"
        ],
        "nativeName": "中国",
        "numericCode": "156",
        "currencies": [
            {
                "code": "CNY",
                "name": "Chinese yuan",
                "symbol": "¥"
            }
        ],
        "languages": [
            {
                "iso639_1": "zh",
                "iso639_2": "zho",
                "name": "Chinese",
                "nativeName": "中文 (Zhōngwén)"
            }
        ],
        "translations": {
            "de": "China",
            "es": "China",
            "fr": "Chine",
            "ja": "中国",
            "it": "Cina",
            "br": "China",
            "pt": "China",
            "nl": "China",
            "hr": "Kina",
            "fa": "چین"
        },
        "flag": "http://10.0.15.20/lab5/flags/chn.svg",
        "regionalBlocs": [],
        "cioc": "CHN"
    },
    {
        "name": "France",
        "topLevelDomain": [
            ".fr"
        ],
        "alpha2Code": "FR",
        "alpha3Code": "FRA",
        "callingCodes": [
            "33"
        ],
        "capital": "Paris",
        "altSpellings": [
            "FR",
            "French Republic",
            "République française"
        ],
        "region": "Europe",
        "subregion": "Western Europe",
        "population": 66710000,
        "latlng": [
            46.0,
            2.0
        ],
        "demonym": "French",
        "area": 640679.0,
        "gini": 32.7,
        "timezones": [
            "UTC-10:00",
            "UTC-09:30",
            "UTC-09:00",
            "UTC-08:00",
            "UTC-04:00",
            "UTC-03:00",
            "UTC+01:00",
            "UTC+03:00",
            "UTC+04:00",
            "UTC+05:00",
            "UTC+11:00",
            "UTC+12:00"
        ],
        "borders": [
            "AND",
            "BEL",
            "DEU",
            "ITA",
            "LUX",
            "MCO",
            "ESP",
            "CHE"
        ],
        "nativeName": "France",
        "numericCode": "250",
        "currencies": [
            {
                "code": "EUR",
                "name": "Euro",
                "symbol": "€"
            }
        ],
        "languages": [
            {
                "iso639_1": "fr",
                "iso639_2": "fra",
                "name": "French",
                "nativeName": "français"
            }
        ],
        "translations": {
            "de": "Frankreich",
            "es": "Francia",
            "fr": "France",
            "ja": "フランス",
            "it": "Francia",
            "br": "França",
            "pt": "França",
            "nl": "Frankrijk",
            "hr": "Francuska",
            "fa": "فرانسه"
        },
        "flag": "http://10.0.15.20/lab5/flags/fra.svg",
        "regionalBlocs": [
            {
                "acronym": "EU",
                "name": "European Union",
                "otherAcronyms": [],
                "otherNames": []
            }
        ],
        "cioc": "FRA"
    },
    {
        "name": "Germany",
        "topLevelDomain": [
            ".de"
        ],
        "alpha2Code": "DE",
        "alpha3Code": "DEU",
        "callingCodes": [
            "49"
        ],
        "capital": "Berlin",
        "altSpellings": [
            "DE",
            "Federal Republic of Germany",
            "Bundesrepublik Deutschland"
        ],
        "region": "Europe",
        "subregion": "Western Europe",
        "population": 81770900,
        "latlng": [
            51.0,
            9.0
        ],
        "demonym": "German",
        "area": 357114.0,
        "gini": 28.3,
        "timezones": [
            "UTC+01:00"
        ],
        "borders": [
            "AUT",
            "BEL",
            "CZE",
            "DNK",
            "FRA",
            "LUX",
            "NLD",
            "POL",
            "CHE"
        ],
        "nativeName": "Deutschland",
        "numericCode": "276",
        "currencies": [
            {
                "code": "EUR",
                "name": "Euro",
                "symbol": "€"
            }
        ],
        "languages": [
            {
                "iso639_1": "de",
                "iso639_2": "deu",
                "name": "German",
                "nativeName": "Deutsch"
            }
        ],
        "translations": {
            "de": "Deutschland",
            "es": "Alemania",
            "fr": "Allemagne",
            "ja": "ドイツ",
            "it": "Germania",
            "br": "Alemanha",
            "pt": "Alemanha",
            "nl": "Duitsland",
            "hr": "Njemačka",
            "fa": "آلمان"
        },
        "flag": "http://10.0.15.20/lab5/flags/deu.svg",
        "regionalBlocs": [
            {
                "acronym": "EU",
                "name": "European Union",
                "otherAcronyms": [],
                "otherNames": []
            }
        ],
        "cioc": "GER"
    },
    {
        "name": "Greece",
        "topLevelDomain": [
            ".gr"
        ],
        "alpha2Code": "GR",
        "alpha3Code": "GRC",
        "callingCodes": [
            "30"
        ],
        "capital": "Athens",
        "altSpellings": [
            "GR",
            "Elláda",
            "Hellenic Republic",
            "Ελληνική Δημοκρατία"
        ],
        "region": "Europe",
        "subregion": "Southern Europe",
        "population": 10858018,
        "latlng": [
            39.0,
            22.0
        ],
        "demonym": "Greek",
        "area": 131990.0,
        "gini": 34.3,
        "timezones": [
            "UTC+02:00"
        ],
        "borders": [
            "ALB",
            "BGR",
            "TUR",
            "MKD"
        ],
        "nativeName": "Ελλάδα",
        "numericCode": "300",
        "currencies": [
            {
                "code": "EUR",
                "name": "Euro",
                "symbol": "€"
            }
        ],
        "languages": [
            {
                "iso639_1": "el",
                "iso639_2": "ell",
                "name": "Greek (modern)",
                "nativeName": "ελληνικά"
            }
        ],
        "translations": {
            "de": "Griechenland",
            "es": "Grecia",
            "fr": "Grèce",
            "ja": "ギリシャ",
            "it": "Grecia",
            "br": "Grécia",
            "pt": "Grécia",
            "nl": "Griekenland",
            "hr": "Grčka",
            "fa": "یونان"
        },
        "flag": "http://10.0.15.20/lab5/flags/grc.svg",
        "regionalBlocs": [
            {
                "acronym": "EU",
                "name": "European Union",
                "otherAcronyms": [],
                "otherNames": []
            }
        ],
        "cioc": "GRE"
    },
    {
        "name": "Italy",
        "topLevelDomain": [
            ".it"
        ],
        "alpha2Code": "IT",
        "alpha3Code": "ITA",
        "callingCodes": [
            "39"
        ],
        "capital": "Rome",
        "altSpellings": [
            "IT",
            "Italian Republic",
            "Repubblica italiana"
        ],
        "region": "Europe",
        "subregion": "Southern Europe",
        "population": 60665551,
        "latlng": [
            42.83333333,
            12.83333333
        ],
        "demonym": "Italian",
        "area": 301336.0,
        "gini": 36.0,
        "timezones": [
            "UTC+01:00"
        ],
        "borders": [
            "AUT",
            "FRA",
            "SMR",
            "SVN",
            "CHE",
            "VAT"
        ],
        "nativeName": "Italia",
        "numericCode": "380",
        "currencies": [
            {
                "code": "EUR",
                "name": "Euro",
                "symbol": "€"
            }
        ],
        "languages": [
            {
                "iso639_1": "it",
                "iso639_2": "ita",
                "name": "Italian",
                "nativeName": "Italiano"
            }
        ],
        "translations": {
            "de": "Italien",
            "es": "Italia",
            "fr": "Italie",
            "ja": "イタリア",
            "it": "Italia",
            "br": "Itália",
            "pt": "Itália",
            "nl": "Italië",
            "hr": "Italija",
            "fa": "ایتالیا"
        },
        "flag": "http://10.0.15.20/lab5/flags/ita.svg",
        "regionalBlocs": [
            {
                "acronym": "EU",
                "name": "European Union",
                "otherAcronyms": [],
                "otherNames": []
            }
        ],
        "cioc": "ITA"
    },
    {
        "name": "Japan",
        "topLevelDomain": [
            ".jp"
        ],
        "alpha2Code": "JP",
        "alpha3Code": "JPN",
        "callingCodes": [
            "81"
        ],
        "capital": "Tokyo",
        "altSpellings": [
            "JP",
            "Nippon",
            "Nihon"
        ],
        "region": "Asia",
        "subregion": "Eastern Asia",
        "population": 126960000,
        "latlng": [
            36.0,
            138.0
        ],
        "demonym": "Japanese",
        "area": 377930.0,
        "gini": 38.1,
        "timezones": [
            "UTC+09:00"
        ],
        "borders": [],
        "nativeName": "日本",
        "numericCode": "392",
        "currencies": [
            {
                "code": "JPY",
                "name": "Japanese yen",
                "symbol": "¥"
            }
        ],
        "languages": [
            {
                "iso639_1": "ja",
                "iso639_2": "jpn",
                "name": "Japanese",
                "nativeName": "日本語 (にほんご)"
            }
        ],
        "translations": {
            "de": "Japan",
            "es": "Japón",
            "fr": "Japon",
            "ja": "日本",
            "it": "Giappone",
            "br": "Japão",
            "pt": "Japão",
            "nl": "Japan",
            "hr": "Japan",
            "fa": "ژاپن"
        },
        "flag": "http://10.0.15.20/lab5/flags/jpn.svg",
        "regionalBlocs": [],
        "cioc": "JPN"
    },
    {
        "name": "Mexico",
        "topLevelDomain": [
            ".mx"
        ],
        "alpha2Code": "MX",
        "alpha3Code": "MEX",
        "callingCodes": [
            "52"
        ],
        "capital": "Mexico City",
        "altSpellings": [
            "MX",
            "Mexicanos",
            "United Mexican States",
            "Estados Unidos Mexicanos"
        ],
        "region": "Americas",
        "subregion": "Central America",
        "population": 122273473,
        "latlng": [
            23.0,
            -102.0
        ],
        "demonym": "Mexican",
        "area": 1964375.0,
        "gini": 47.0,
        "timezones": [
            "UTC-08:00",
            "UTC-07:00",
            "UTC-06:00"
        ],
        "borders": [
            "BLZ",
            "GTM",
            "USA"
        ],
        "nativeName": "México",
        "numericCode": "484",
        "currencies": [
            {
                "code": "MXN",
                "name": "Mexican peso",
                "symbol": "$"
            }
        ],
        "languages": [
            {
                "iso639_1": "es",
                "iso639_2": "spa",
                "name": "Spanish",
                "nativeName": "Español"
            }
        ],
        "translations": {
            "de": "Mexiko",
            "es": "México",
            "fr": "Mexique",
            "ja": "メキシコ",
            "it": "Messico",
            "br": "México",
            "pt": "México",
            "nl": "Mexico",
            "hr": "Meksiko",
            "fa": "مکزیک"
        },
        "flag": "http://10.0.15.20/lab5/flags/mex.svg",
        "regionalBlocs": [
            {
                "acronym": "PA",
                "name": "Pacific Alliance",
                "otherAcronyms": [],
                "otherNames": [
                    "Alianza del Pacífico"
                ]
            },
            {
                "acronym": "NAFTA",
                "name": "North American Free Trade Agreement",
                "otherAcronyms": [],
                "otherNames": [
                    "Tratado de Libre Comercio de América del Norte",
                    "Accord de Libre-échange Nord-Américain"
                ]
            }
        ],
        "cioc": "MEX"
    },
    {
        "name": "Poland",
        "topLevelDomain": [
            ".pl"
        ],
        "alpha2Code": "PL",
        "alpha3Code": "POL",
        "callingCodes": [
            "48"
        ],
        "capital": "Warsaw",
        "altSpellings": [
            "PL",
            "Republic of Poland",
            "Rzeczpospolita Polska"
        ],
        "region": "Europe",
        "subregion": "Eastern Europe",
        "population": 38437239,
        "latlng": [
            52.0,
            20.0
        ],
        "demonym": "Polish",
        "area": 312679.0,
        "gini": 34.1,
        "timezones": [
            "UTC+01:00"
        ],
        "borders": [
            "BLR",
            "CZE",
            "DEU",
            "LTU",
            "RUS",
            "SVK",
            "UKR"
        ],
        "nativeName": "Polska",
        "numericCode": "616",
        "currencies": [
            {
                "code": "PLN",
                "name": "Polish złoty",
                "symbol": "zł"
            }
        ],
        "languages": [
            {
                "iso639_1": "pl",
                "iso639_2": "pol",
                "name": "Polish",
                "nativeName": "język polski"
            }
        ],
        "translations": {
            "de": "Polen",
            "es": "Polonia",
            "fr": "Pologne",
            "ja": "ポーランド",
            "it": "Polonia",
            "br": "Polônia",
            "pt": "Polónia",
            "nl": "Polen",
            "hr": "Poljska",
            "fa": "لهستان"
        },
        "flag": "http://10.0.15.20/lab5/flags/pol.svg",
        "regionalBlocs": [
            {
                "acronym": "EU",
                "name": "European Union",
                "otherAcronyms": [],
                "otherNames": []
            }
        ],
        "cioc": "POL"
    },
    {
        "name": "Thailand",
        "topLevelDomain": [
            ".th"
        ],
        "alpha2Code": "TH",
        "alpha3Code": "THA",
        "callingCodes": [
            "66"
        ],
        "capital": "Bangkok",
        "altSpellings": [
            "TH",
            "Prathet",
            "Thai",
            "Kingdom of Thailand",
            "ราชอาณาจักรไทย",
            "Ratcha Anachak Thai"
        ],
        "region": "Asia",
        "subregion": "South-Eastern Asia",
        "population": 65327652,
        "latlng": [
            15.0,
            100.0
        ],
        "demonym": "Thai",
        "area": 513120.0,
        "gini": 40.0,
        "timezones": [
            "UTC+07:00"
        ],
        "borders": [
            "MMR",
            "KHM",
            "LAO",
            "MYS"
        ],
        "nativeName": "ประเทศไทย",
        "numericCode": "764",
        "currencies": [
            {
                "code": "THB",
                "name": "Thai baht",
                "symbol": "฿"
            }
        ],
        "languages": [
            {
                "iso639_1": "th",
                "iso639_2": "tha",
                "name": "Thai",
                "nativeName": "ไทย"
            }
        ],
        "translations": {
            "de": "Thailand",
            "es": "Tailandia",
            "fr": "Thaïlande",
            "ja": "タイ",
            "it": "Tailandia",
            "br": "Tailândia",
            "pt": "Tailândia",
            "nl": "Thailand",
            "hr": "Tajland",
            "fa": "تایلند"
        },
        "flag": "http://10.0.15.20/lab5/flags/tha.svg",
        "regionalBlocs": [
            {
                "acronym": "ASEAN",
                "name": "Association of Southeast Asian Nations",
                "otherAcronyms": [],
                "otherNames": []
            }
        ],
        "cioc": "THA"
    }
]

const content = document.getElementById("content");

let onload = async () => {
  const data = await (await fetch('./countries.json')).json();
  console.log(data);

  for (let index = 0; index < data.length; index++) {
    const count_info = data[index];
    let count = document.createElement('div');
    count.style.display = 'flex';
    count.style.width = '100%';
    count.style.justifyContent = 'space-between';
    count.style.alignItems = 'center';
    const info = document.createElement('div');
    const title = document.createElement('p');
    title.innerHTML = `Name : <b>${count_info.name}</b>`;
    const capital = document.createElement('p');
    capital.innerHTML = `Capital : ${count_info.capital}`;
    const population = document.createElement('p');
    population.innerHTML = `Population : ${count_info.population}`;
    const region = document.createElement('p');
    region.innerHTML = `Region : ${count_info.region}`;
    const Location = document.createElement('p');
    Location.innerHTML = `Location : ${count_info.latlng[0]} ${count_info.latlng[1]}`;
    const bprder = document.createElement('p');
    bprder.innerHTML = `Border : ${count_info.borders.join(' ')}`;
    info.appendChild(title);
    info.appendChild(capital);
    info.appendChild(population);
    info.appendChild(region);
    info.appendChild(Location);
    info.appendChild(bprder);
    const flag = document.createElement('img');
    flag.src = count_info.flag;
    flag.style.width = '300px';
    flag.style.filter = 'drop-shadow(0px 0px 1px #000)';
    count.appendChild(info);
    count.appendChild(flag);
    content.appendChild(count);
    console.log(count);
  }
};

onload();

w5-4
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>lab5-4</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div id="content">
    <script src="script.js"></script>
  </body>
</html>

.json
{
    "movies": {
        "showing": [
            {
                "id": 1,
                "title_th": "เกมเมอร์ เกมแม่",
                "title_en": "Mother Gamer",
                "releasedate" : "2020-09-10",
                "poster" : "http://10.0.15.20/lab5/posters/mother.jpg",
                "categoty" : ["Action"]
            },
            {
                "id": 2,
                "title_th": "มู่หลาน",
                "title_en": "Mulan",
                "releasedate" : "2020-09-04",
                "poster" : "http://10.0.15.20/lab5/posters/mulan.jpg",
                "categoty" : ["Adventure"]
            },
            {
                "id": 3,
                "title_th": "เทเน็ท",
                "title_en": "Tenet",
                "releasedate" : "2020-08-27",
                "poster" : "http://10.0.15.20/lab5/posters/tenet.jpg",
                "categoty" : ["Action"]
            },
            {
                "id": 4,
                "title_th": "กระชากนรก โคตรไอ้เข้",
                "title_en": "Black water : Abyss",
                "releasedate" : "2020-08-12",
                "poster" : "http://10.0.15.20/lab5/posters/abyss.jpg",
                "categoty" : ["Action", "Drama", "Horror"]
            },
            {
                "id": 5,
                "title_th": "Break The Silence : The Movie",
                "title_en": "Break The Silence : The Movie",
                "releasedate" : "2020-09-10",
                "poster" : "http://10.0.15.20/lab5/posters/break.jpg",
                "categoty" : ["Documentary", "Musical"]
            },
            {
                "id": 5,
                "title_th": "อย่าให้ยูจินเข้าบ้าน",
                "title_en": "The Intruder",
                "releasedate" : "2020-08-20",
                "poster" : "http://10.0.15.20/lab5/posters/intruder.jpg",
                "categoty" : ["Thriller", "Musical"]
            }
        ],
        "comingsoon": [
            {
                "id": 1,
                "title_th": "Love at Second Sight",
                "title_en": "Love at Second Sight",
                "releasedate" : "2020-09-24",
                "poster" : "http://10.0.15.20/lab5/posters/loveat.jpg",
                "categoty" : ["Comedy", "Drama"]
            },
            {
                "id": 2,
                "title_th": "นาทีระทึก..วันสิ้นโลก",
                "title_en": "Greenland",
                "releasedate" : "2020-09-24",
                "poster" : "http://10.0.15.20/lab5/posters/greenland.jpg",
                "categoty" : ["Action", "Thriller"]
            },
            {
                "id": 3,
                "title_th": "เทสลา คนล่าอนาคต",
                "title_en": "Tesla",
                "releasedate" : "2020-09-24",
                "poster" : "http://10.0.15.20/lab5/posters/tesla.jpg",
                "categoty" : ["Biography", "Drama"]
            }
        ]
    }
}

script.js

const content = document.getElementById("content");

const ui_land = {
  th: {
    type_show: {
      showing: "กำลังฉาย",
      comingsoon: "เร็วๆนี้",
    },
    movie_show_btn: "เช็ครอบฉาย",
  },
};

const createCard = (lang, data) => {
  const movie = document.createElement("div");
  movie.classList.add("movie");
  const movie_img = document.createElement("img");
  movie_img.src = data.poster;
  movie_img.classList.add("movie-img");
  const movie_info = document.createElement("div");
  movie_info.classList.add("movie-info");
  const movie_title = document.createElement("div");
  movie_title.classList.add("movie-title");
  movie_title.innerText = data[`title_${lang}`];
  const movie_release_date = document.createElement("div");
  movie_release_date.classList.add("movie-release-date");
  movie_release_date.innerText = `Release Date : ${data.releasedate}`;
  const movie_categoty = document.createElement("div");
  movie_categoty.classList.add("movie-categoty");
  for (let index = 0; index < data.categoty.length; index++) {
    const categoty = data.categoty[index];
    const categoty_item = document.createElement("div");
    categoty_item.innerText = categoty;
    movie_categoty.appendChild(categoty_item);
  }
  const movie_time_btn = document.createElement("div");
  movie_time_btn.classList.add("movie-time-btn");
  movie_time_btn.innerText = ui_land[lang].movie_show_btn;
  movie_info.appendChild(movie_title);
  movie_info.appendChild(movie_release_date);
  movie_info.appendChild(movie_categoty);
  movie_info.appendChild(movie_time_btn);
  movie.appendChild(movie_img);
  movie.appendChild(movie_info);
  return movie;
}

const onLoad = async (lang) => {
  content.innerHTML = "";
  const data = await (await fetch(`./movies.json`)).json();
  for (const key in data.movies) {
    const element = data.movies[key];
    const type_movie = document.createElement("h1");
    console.log(ui_land[lang].type_show[key]);
    type_movie.innerText = ui_land[lang].type_show[key];
    type_movie.classList.add("movie-container-title");
    content.appendChild(type_movie);
    const movie_container = document.createElement("div");
    movie_container.classList.add("movie-container");
    for (const key in element) {
      const movie_data = element[key];
      movie_container.appendChild(createCard(lang, movie_data));
    }
    content.appendChild(movie_container);
  }
};

onLoad("th");

style.css

@import url("https://fonts.googleapis.com/css2?family=Prompt:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap");

body {
  margin: 0;
  font-family: 'Prompt', sans-serif;
}

.movie-container-title {
  padding: 1%;
}

.movie-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  padding: 1%;
}

.movie {
  width: 20%;
  margin: 1%;
  overflow: hidden;
  transition: all 0.1s ease;
  border: rgb(222, 222, 222) 1px solid;
}

.movie:hover {
  transform: scale(1.05);
}

.movie img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.movie-info {
  padding: 1%;
  color: black;
  font-size: 0.8em;
  text-align: center;
}

.movie-title {
  font-size: 1.2em;
  font-weight: bold;
  margin: 0;
  padding: 0;
}

.movie-categoty {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}

.movie-categoty div {
  color: white;
  padding: 1%;
  margin: 1%;
  font-size: 0.8em;
  font-weight: normal;
  background-color: #3498db;
}

.movie-time-btn {
  width: 100%;
  margin-top: 5%;
  margin-bottom: 5%;
  padding-top: 3%;
  padding-bottom: 3%;
  color: white;
  transition: all 0.1s ease;
  background-color: #3498db;
  user-select: none;
}

.movie-time-btn:hover {
  background-color: #2c80b9;
}

.movie-time-btn:active {
  background-color: #21628d;
  transform: scale(0.9);
}

w6-1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>lab6-1</title>
</head>
<body>
    <div>
        <h1>Text</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsum unde reprehenderit quasi atque impedit aperiam labore voluptate. Adipisci tempore quam quasi illo officia! Ab praesentium reprehenderit temporibus distinctio modi, nihil voluptatem aliquid odit non perspiciatis</p>
    </div>
    <div class="grid">
        <div>
            <h2>Text1</h2>
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Fugit, explicabo. Voluptatem quae, non nam dolor aliquid modi quidem esse voluptatum aliquam laudantium, blanditiis, a id voluptas tempora veniam? Maxime, eligendi.</p>
        </div>
        <div>
            <h2>Text2</h2>
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Fugit, explicabo. Voluptatem quae, non nam dolor aliquid modi quidem esse voluptatum aliquam laudantium, blanditiis, a id voluptas tempora veniam? Maxime, eligendi.</p>
        </div>
        <div>
            <h2>Text3</h2>
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Fugit, explicabo. Voluptatem quae, non nam dolor aliquid modi quidem esse voluptatum aliquam laudantium, blanditiis, a id voluptas tempora veniam? Maxime, eligendi.</p>
        </div>
    </div>
</body>
</html>

* {
    margin: 0;
    padding: 0;
  }
  
  body {
    padding: 2em;
  }
  
  body > div:nth-child(1) p {
    margin-top: 1em;
  }
  
  .grid {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    gap: 2em;
    margin: 2em 0;
  }
  
  @media screen and (max-width: 400px) {
    .grid {
      grid-template-columns: 1fr;
    }
  }
  
w6-2
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>lab6-2</title>
</head>
<body>
    <div>
        <h2>Popular cat names</h2>
        <p>The popularity of cat names differs by nation, even nations with the same language. The ranking of most popular cat names can be assessed, in particular, from pet insurance registrations, microchip registrations, and breed registries.</p>
    </div>
    <div>
        <h3>List of cat names</h3>
        <div class="grid">
            <img src="https://static.scientificamerican.com/sciam/cache/file/1E3A3E62-B3CA-434A-8C3B3ED0C982FB69_source.jpg?w=590&h=800&C8DB8C57-989B-4118-AE27EF1191E878A5" alt="cat-1" />
            <img src="https://static.scientificamerican.com/sciam/cache/file/1E3A3E62-B3CA-434A-8C3B3ED0C982FB69_source.jpg?w=590&h=800&C8DB8C57-989B-4118-AE27EF1191E878A5" alt="cat-1" />
            <img src="https://static.scientificamerican.com/sciam/cache/file/1E3A3E62-B3CA-434A-8C3B3ED0C982FB69_source.jpg?w=590&h=800&C8DB8C57-989B-4118-AE27EF1191E878A5" alt="cat-1" />
            <img src="https://static.scientificamerican.com/sciam/cache/file/1E3A3E62-B3CA-434A-8C3B3ED0C982FB69_source.jpg?w=590&h=800&C8DB8C57-989B-4118-AE27EF1191E878A5" alt="cat-1" />
        </div>
    </div>
  
</body>
</html>

@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;400;500;700;900&display=swap');
* {
  margin: 0;
  padding: 0;
}

body{
  font-family: 'Roboto', sans-serif;
  padding:2em;
}

body > div:nth-child(2){
  margin-top:2em;
}

.grid{
  display: grid;
  grid-template-columns: 10em 10em;
  gap: 1em;
}

.grid > img {
  width: 100%;
  border: 3px solid black;
}

@media only screen and (max-width:600px){
  .grid{
    
    grid-template-columns: 10em;
  }
}

w6-3
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="style.css" />
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.1/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-iYQeCzEYFbKjA/T2uDLTpkwGzCiq6soy8tYaI1GyVh/UjpbCx/TYkiZhlZB6+fzT"
      crossorigin="anonymous"
    />
    <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.1/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-u1OknCvxWvY5kfmNBILK2hRnQC3Pr17a+RTT6rIHI7NnikvbZlHgTPOOmMi466C8"
      crossorigin="anonymous"
    ></script>
    <title>lab6-3</title>
  </head>
  <body>
    <div class="bg-secondary bg-opacity-25 p-4">
      <h2 class="">What is Web Technology?</h2>
      <p class="text-secondary">
        Web technology refers to the means by which computers communicate with each other using markup languages and 
        multimedia packages. It gives us a way to interact with hosted information, like websites. Web technology involves the use of 
        hypertext markup language (HTML) and cascading style sheets (CSS)
      </p>
    </div>
    <div class="container mt-4">
      <div class="row">
        <div class="col-12 col-xl-3 col-lg-4 col-md-6">
          <h2>HTML</h2>
          <p>
            HTML is the standard markup language for describing the structure of the web pages. Our HTML tutorials will help 
            you to understand the basics of latest
          </p>
        </div>
        <div class="col-12 col-xl-3 col-lg-4 col-md-6">
          <h2>CSS</h2>
          <p>
            CSS is used for describing the presentation of web pages. CSS can save a lot of time and effort. Our CSS tutorials 
            will help you to learn the essentials of latest CSS3, so that
          </p>
        </div>
        <div class="col-12 col-xl-3 col-lg-4 col-md-6">
          <h2>JavaScript</h2>
          <p>
            JavaScript is the most popular and widely used client-side scripting language. Our JavaScript tutorials will provide 
            in-depth knowledge of the JavaScript including ES6
          </p>
        </div>
        <div class="col-12 col-xl-3 col-lg-12 col-md-6">
          <h2>Bootstrap</h2>
          <p>
            Bootstrap is a powerful front-end framework for faster and easier web development. Our Bootstrap tutorials will help 
            you to learn all the features of latest Bootstrap 4
          </p>
        </div>
      </div>
    </div>
  </body>
</html>

@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;400;500;700;900&display=swap');

/* 
body{
  font-family: 'Roboto', sans-serif;
} */

w6-4
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="style.css" />
    <title>lab6-4</title>
  </head>
  <body>
    <header>
      <h1>Hello Web Developer</h1>
    </header>
    <content>
      <nav>
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">News</a></li>
          <li><a href="#">Contact</a></li>
          <li><a href="#">About</a></li>
        </ul>
      </nav>
      <div>
        <h2>Web developer</h2>
        <div>
          <p>
            A web developer is a programmer who specializes in, or is specifically engaged in, the development of World Wide Web applications using a client-server model. The applications typically use HTML, 
            CSS and JavaScript in the client, PHP, ASP.NET (C #), Python or Java in the server, and http for communications between client and server. A web content management system is often used to develop 
            and maintain web applications.
          </p>
          <img
            src="https://img.freepik.com/premium-vector/programmer-with-code-cat-book-coffee-vector-clip-art-illustration_138676-92.jpg?w=2000 "
            alt="web-dev-img" width="300" height="300"
          />
        </div>
      </div>
    </content>
    <footer>
      <p>Who AM I ???</p>
    </footer>
  </body>
</html>

@import url("https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;400;500;700;900&display=swap");

* {
  margin: 0;
  padding: 0;
}

body {
  font-family: "Roboto", sans-serif;
}

header {
  padding: 2em;
  background-color: #e9e9e9;
}

header h1 {
  background-color: white;
  text-align: center;
}

content {
  padding: 0.5em;
  display: flex;
}

nav ul {
  display: flex;
  flex-direction: column;
  gap: 0.25em;
}

nav ul li {
  list-style: none;
  color: white;
  text-align: center;
}

nav ul li a {
  display: block;
  padding: 1em 4em;
  font-weight: 500;
  color: black;
  background-color: rgb(24, 146, 239);
}

content>div {
  width: 100%;
  padding: 1em;
}

content>div>div {
  width: 100%;
  padding-top: 1em;
  display: flex;
  gap: 1em;
}

footer {
  padding: 2em;
  background-color: #e9e9e9;
}

footer p {
  background-color: white;
  text-align: center;
  padding: 1em 0;
}

@media only screen and (max-width: 620px) {

  nav ul {
    display: flex;
    flex-direction: row;
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 3em;
    overflow: hidden;
    gap: 0;
  }


  nav ul li {
    list-style: none;
    flex: 1;
    padding: 0;
    color: white;
  }

  nav ul li a {
    padding: 0;
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: white;
  }

  header {
    margin: 3.5em 0 0 0;
  }

  content{
    padding: 0;
  }

  content>div>div {
    flex-direction: column;
  }
}

w7-1
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>
    <title>lab7-1</title>
    <style>
        body{
            font-size:16px;
        }
        hr{
           width:20%;
           margin-left: 0;
        }
    </style>
</head>
<body>
<form id="calform" action="index.php" method="post">
    <label for="fname">กรอกสูตรคูณ:</label>
    <input type="number" id="inpvalue" name="inpvalue"/>
    <input type="submit" id="submit" value="แสดงตาราง">
</form>
<br />
<b>Notice</b>:  Undefined index: inpvalue in <b>C:\WebTech-FTP\students\it\64070056\lab7\1\index.php</b> on line <b>28</b><br />
<b>ตารางสูตรคูณแม่ </b><br> x 1 = 0<hr><br> x 2 = 0<hr><br> x 3 = 0<hr><br> x 4 = 0<hr><br> x 5 = 0<hr><br> x 6 = 0<hr><br> x 7 = 0<hr><br> x 8 = 0<hr><br> x 9 = 0<hr><br> x 10 = 0<hr><br> x 11 = 0<hr><br> x 12 = 0<hr><br></body>
</html>

