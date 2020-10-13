# BTL_web
test
<!DOCTYPE HTML>
<HTML>
<head>
<meta charset="UTF-8"/>
<title>lap trinh web</title>
</head>
<body>
<table>
  <form>
    <tr><td colspan="2"><center>Đăng ký</center></td></tr>
<tr>
  <td><label>FullName</label></td>
  <td>
<INPUT TYPE="TExTbox" id="txtfullname" placeholder=" nhập fullname"/>
</td>  
</tr>
<tr>
  <td >
  <label>UserName</label> </td>
  <td><INPUT TYPE="TExTbox" id="txtusername" placeholder=" nhập name"/>
  </td>
</tr>
<tr>
<td >
  <label>Password</label></td>
  <td><input type="password" id="psw" placeholder="nhập password"/>
</td>
</tr>
<tr>
<td >
  <label>Nhập lại password</label> </td>
  <td>
    <input type="password" id="nlpsw" placeholder="nhập lại password"/>
</td>
</tr>
  <tr>
<td >
  <label>Giới tính</label></td>
    <td><input type="radio" name="drone" value="Nam" checked><label for ="Nam">Nam </label>
    <input type="radio" name="drone" value="Nữ" checked><label for ="Nữ">Nữ </label></td>
</tr>
  <tr>
<td >
  <label>Ngày sinh</label></td>
    <td><input type="date" name="bday"/>
</td>
</tr>
  <tr>
<td>
<label>Địa chỉ</label> 
</td>
    <td><input type="text" id="diachi" placeholder="nhập địa chỉ"/></td>
</tr>
  <tr>
<td >
<label>Avatar</label> 
</td>
    <td><button type="button" onclick="alert('Chào mừng bạn đến với thẻ button!')">Choosefile</button>không có file
</tr>
  <tr>
<td >
<label>Sở thích</label> 
</td>
    <td><input type="checkbox" name="vehicle1" value="st">xem phim
    <input type="checkbox" name="vehicle2" value="st">thể thao
    <input type="checkbox" name="vehicle3" value="st">web</td>
</tr>
  <tr>
<td colspan="2" ><center>
<INPUT TYPE="submit" id="btnsubmit" value=" submit"/> 
 <INPUT TYPE="submit" id="btnsubmit" value=" OK"/> 
  </td></center>
</tr>
  </form>
</table>
</body>
</html>
