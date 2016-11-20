
<html>
  <head>
    <title>Membuat form input dengan html</title>
  </head>
  <body>
	<form action="" method="post">
	    <table>
	        <tr>
	          	<td><label>Judul</label></td>
	          	<td><input type="text" name="judul"></td>
	        </tr>
	        <tr>
	          	<td><label>E-mail</label></td>
	          	<td><input type="email" name="email"></td>
	        </tr>
	        <tr>
	         	<td><label>Kota</label></td>
	          	<td><select name="kota">
		           		<option value="" selected="">- pilih -</option>
		           		<option value="jakarta">Jakarta</option>
		           		<option value="yogyakarta">Yogyakarta</option>
		           		<option value="Malang">Malang</option>
	           		</select>
	          	</td>
	        </tr>
	        <tr>
	          <td><label>Status</label></td>
	          <td><input type="radio" name="status" checked="">Lajang
	          	<input type="radio" name="status">Menikah
	          </td>
	        </tr>
	        <tr>
	          <td><label>Hobi</label></td>
	          <td><input type="checkbox" name="memasak">Memasak
		          <input type="checkbox" name="membaca">Membaca
		          <input type="checkbox" name="otomotif">Otomotif
		          <input type="checkbox" name="desain">Desain
	          </td>
	        </tr>
	        <tr>
	          <td><label>Tahun</label></td>
	          <td><input type="date" name="tahun"></td>
	        </tr>
	        <tr>
	          <td><label>Waktu</label></td>
	          <td><input type="time" name="waktu"></td>
	        </tr>
	        <tr>
	          <td><label>Phone</label></td>
	          <td><input type="tel" name="phone"></td>
	        </tr>
	        <tr>
	          <td><label>Jumlah</label></td>
	          <td><input type="number" name="jumlah"></td>
	        </tr>	        <tr>
	          <td><label>Deskripsi</label></td>
	          <td><textarea name="deskripsi"></textarea></td>
	        <tr>
	          <td>
	            <button type="submit" name="simpan">simpan</button>
	          </td>
	        </tr>
	    </table>
	</form>
  </body>
</html>
