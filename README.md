



<html>
<head>
<meta charset="utf-8">
<style type="text/css">
table{
        width:1000px;
        height:1000px;
        margin:100px;
    }
td{
  text-align: left;
  width:125px;
  height:100px;
  }
    
th
  {
  background-color:lightblue;
  color:black;
  width:125px;
  height:100px;
  }
  td:hover {
            position: relative;
            top: 4px;
            left: 5px
            color:red;
        }

        .cell {
            height: 4em;
            width: 3em;
        }
</style>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" type="text/css" media="screen" href="main.css">
<script src="main.js"></script>
</head>

<body>
    
<h1 align="center">大二下学期信息课程表</h1>
<table align="center"  border="1px" >
<tr align="center">
    
<th colspan="2"></th>
<th>星期一</th>
<th>星期二</th>
<th>星期三</th>
<th>星期四</th>
<th>星期五</th>
<th>星期六</th>
<th>星期日</th>
</tr>
<tr>
<td rowspan="2">上午</td>
<td>第一节</br>第二节</br>（8:20-10:00）</td>
<td onmousedown="mDown1(this)" onmouseup="mOut1(this)" style="background-color:orange">web应用开发技术-01</td>
<script>
                
  function mDown1(obj) 
 {
      obj.innerHTML = "教室：西区第一公共教学楼C411 </br>老师：吕成功</br>周数：1-15周"
  }
 function mOut1(obj) {
      obj.innerHTML = "web应用开发技术_01"
  }
</script>
<td onmousedown="mDown2(this)" onmouseup="mOut2(this)" style="background-color:lightseagreen">大学英语四级（A）-64</td>
<script>
  function mDown2(obj) {

      obj.innerHTML = "教室：西区第一公共教学楼C221</br>老师：张蔚</br>周数：1-17周"
  }

  function mOut2(obj) {

      obj.innerHTML = "大学英语四级（A）_64"
  }
</script>
<td onmousedown="mDown3(this)" onmouseup="mOut3(this)" style="background-color:lightgrey">管理信息系统—02</td>
<script>
  function mDown3(obj) {

      obj.innerHTML = "教室：西区第一公共教学楼C105<br>老师：刘烨</br>周数：1-15周"
  }

  function mOut3(obj) {

      obj.innerHTML = "管理信息系统_02"
  }
</script>
<td onmousedown="mDown4(this)" onmouseup="mOut4(this)" style="background-color:slateblue">数据库原理及应用-01</br> 运营管理—02</td>
<script>
  function mDown4(obj) {

      obj.innerHTML = "教室：西区第一公共教学楼B405<br>老师：吴君 周数：2-14双周</br>教室:西区第一公共教学楼B405</br>老师：刘亮 周数：1-15单周"
  }

  function mOut4(obj) {

      obj.innerHTML = "数据库原理及应用_01<br>运营管理_02"
  }
</script>
<td onmousedown="mDown5(this)" onmouseup="mOut5(this)"style="background-color:lightseagreen">大学英语四级（A）-64 </td>
<script>
  function mDown5(obj) {

      obj.innerHTML = "教室：人文学院219</br>周数：1-17</br>教室:西区第一公共教学楼:C219</br>周数：2-16双周</br>任课教师：张蔚"
  }

  function mOut5(obj) {

      obj.innerHTML = "大学英语四级（A）_64"
  }
</script>
<td> </td>
<td> </td>
</tr>

<tr>
<td>第三节</br>第四节</br>（10:20-12:00）</td>
<td onmousedown="mDown6(this)" onmouseup="mOut6(this)" style="background-color:greenyellow">毛泽东思想与中国特色社会主义理论体系概论-13</td>
<script>
    function mDown6(obj) {

        obj.innerHTML = "教室:西区第一公共教学楼A120 </br>老师：顾洪英</br>周数：1-16周"
    }

    function mOut6(obj) {

        obj.innerHTML = "毛泽东思想与中国特色社会主义理论体系概论_13"
    }
</script>
<td onmousedown="mDown7(this)" onmouseup="mOut7(this)"style="background-color:slateblue">管理科学基础-01</td>
<script>
    function mDown7(obj) {

        obj.innerHTML = "教室：西区第一公共教学楼C411</br>老师：赵方方</br>周数：3-17周"
    }

    function mOut7(obj) {

        obj.innerHTML = "管理科学基础_01"
    }
</script>
<td onmousedown="mDown6(this)" onmouseup="mOut6(this)" style="background-color:greenyellow">毛泽东思想与中国特色社会主义理论体系概论-13</td>
<script>
    function mDown6(obj) {

        obj.innerHTML = "教室:西区第一公共教学楼A120 </br>老师：顾洪英</br>周数：1-16周"
    }

    function mOut6(obj) {

        obj.innerHTML = "毛泽东思想与中国特色社会主义理论体系概论_13"
    }
</script>
<td onmousedown="mDown7(this)" onmouseup="mOut7(this)"style="background-color:slateblue">管理科学基础-01</td>
<script>
    function mDown7(obj) {

        obj.innerHTML = "教室：西区第一公共教学楼C411</br>老师：赵方方</br>周数：3-17周"
    }

    function mOut7(obj) {

        obj.innerHTML = "管理科学基础_01"
    }
</script>
<td onmousedown="mDown8(this)" onmouseup="mOut8(this)"style="background-color:crimson">运营管理—02</td>
<script>
    function mDown8(obj) {

        obj.innerHTML = " 教室：西区第一公共教学楼B405</br>老师：刘亮</br>周数：1-15周"
    }

    function mOut8(obj) {

        obj.innerHTML = "运营管理_02"
    }
</script>
<td></td>
<td></td>
</tr>
<tr>
<td rowspan="2">下午</td>

<td>第五节</br>第六节</br>（14:00-14:45）</td>
<td onmousedown="mDown3(this)" onmouseup="mOut3(this)" style="background-color:lightgrey">管理信息系统—02</td>
<script>
  function mDown3(obj) {

      obj.innerHTML = "教室：西区第一公共教学楼C105<br>老师：刘烨</br>周数：1-15周"
  }

  function mOut3(obj) {

      obj.innerHTML = "管理信息系统_02"
  }
</script>
<td onmousedown="mDown9(this)" onmouseup="mOut9(this)" style="background-color:chocolate">形势与政策2-41</td>
<script>
    function mDown9(obj) {

        obj.innerHTML = "教室：西区第一公共教学楼C123</br>老师：李坤</br>周数：5-7周"
    }

    function mOut9(obj) {

        obj.innerHTML = "形势与政策2_41"
    }
</script>
<td onmousedown="mDown10(this)" onmouseup="mOut10(this)" style="background-color:green">会计学-01</td>
<script>
    function mDown10(obj) {

        obj.innerHTML = "教室：西区第一公共教学楼B101</br>老师：刘晓晖</br>周数：1-17单周 "
    }

    function mOut10(obj) {

        obj.innerHTML = "会计学_01"
    }
</script>
<td onmousedown="mDown11(this)" onmouseup="mOut11(this)"style="background-color:orange">体育（四）-132</td>
<script>
    function mDown11(obj) {

        obj.innerHTML = "教室:健身馆2-17周</br>老师：田建生</br>周数：1-18周 "
    }

    function mOut11(obj) {

        obj.innerHTML = "乒乓球课"
    }
</script>
<td onmousedown="mDown6(this)" onmouseup="mOut6(this)" style="background-color:greenyellow">毛泽东思想与中国特色社会主义理论体系概论-13</td>
<script>
    function mDown6(obj) {

        obj.innerHTML = "教室:西区第一公共教学楼A120 </br>老师：顾洪英</br>周数：1-16周"
    }

    function mOut6(obj) {

        obj.innerHTML = "毛泽东思想与中国特色社会主义理论体系概论_13"
    }
</script>
<td></td>
<td></td>
</tr>

<tr>
<td>第七节</br>第八节</br>（16:00-16:45）</td>
<td onmousedown="mDown12(this)" onmouseup="mOut13(this)"style="background-color:purple">电子商务-01</td>
<script>
function mDown12(obj) {

    obj.innerHTML = "教室:西区第一公共教学楼B303</br>3-17周</br>老师：张亮"
}

function mOut12(obj) {

    obj.innerHTML = "电子商务_01"
}
</script>
<td onmousedown="mDown13(this)" onmouseup="mOut13(this)"style="background-color:slateblue">数据库原理及应用-01</td>
<script>
    function mDown13(obj) {

        obj.innerHTML = "教室:西区第一公共教学楼B405</br>任课教师：吴君</br>周数：1-15周"
    }

    function mOut13(obj) {

        obj.innerHTML = "数据库原理及应用_01"
    }
</script>
<td></td>
<td onmousedown="mDown10(this)" onmouseup="mOut10(this)" style="background-color:green">会计学-01</td>
<script>
    function mDown10(obj) {

        obj.innerHTML = "教室：西区第一公共教学楼B101</br>老师：刘晓晖</br>周数：1-17单周 "
    }

    function mOut10(obj) {

        obj.innerHTML = "会计学_01"
    }
</script>
<td></td>
<td></td>
<td></td>
</tr>

<tr height="1px">

</tr>

<tr>
<th>晚上</th>  
<td>第九节</br>第十节</br>（18:30-19:15）</td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>

</table>
</body>
</html>



