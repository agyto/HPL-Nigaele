<!DOCTYPE html>
<!-- 
++++++++++++++
Perhitungan HPL menurut Nigaele
++++++++++++++
Created by Agit Amrullah
Email    : the3cube@gmail.com
WA/Phone : +6285643102182

Licence by GNU 
All rights reserved but free to distribute with head author information
 -->
<html>
<head>
	<title>presentasi calon dosen</title>
	<style type="text/css">
		body{
			margin: 150px 100px 0px 100px;
		}
		code {
			font-size: 15px;
		}
		.hpl{
			font-size: 30px;
		}
	</style>
</head>
<body>
	<p><h3>Algoritma perhitungan Hari Perkiraan Lahir (HPL) menurut Nigaele</h3></p>  
	<code>
		Rumus Perhitungan Hari Perkiraan Lahir (HPL) = HHT , bulan, tahun
		<br/>Logika :
		<br/>- Apabila bulan januari hingga maret maka tanggal ditambah 7, bulan ditambah 9, tahun ditambah 0
		<br/>- apabila bulan april hingga desember maka tanggal ditambah 7, bulan dikurangi 3,tahun ditambah 1
		<br/>- HPHT dihitung bedasarkan hari pertama haid
	</code>
	<p>HHT &nbsp;= <input type="text" id="HHT" onchange="hplhitung();"></p>
	<p>Bulan = 
		<select id="bulan" onchange="hplhitung();">
			<option value="-">Pilih bulan..</option>
			<option value="1">Januari</option>
			<option value="2">Februari</option>
			<option value="3">Maret</option>
			<option value="4">April</option>
			<option value="5">Mei</option>
			<option value="6">Juni</option>
			<option value="7">Juli</option>
			<option value="8">Agustus</option>
			<option value="9">September</option>
			<option value="10">Oktober</option>
			<option value="11">November</option>
			<option value="12">Desember</option>
		</select>
	</p>
	<p>Tahun = <input type="text" id="tahun" onchange="hplhitung();"></p>
	<p class="hpl">HPL = <span id="HPL"></span></p> 
</body>

<script type="text/javascript">
	function hplhitung(){
		var HPL   = document.getElementById("HPL").innerHTML;
		var HHT   = document.getElementById("HHT").value;
		var bulan = document.getElementById("bulan").value;
		var tahun = document.getElementById("tahun").value;
		var check = '';
		
		// cek input
		if(HHT == '' || HHT == 0 ){
			check = "Masukkan HHT";
		} else if(HHT>31){
		  	check = "HHT tidak valid";
		} else if(bulan == "-"){
		  	check = "Masukkan bulan";
		} else if (tahun=='' || tahun == 0){
			check = "Harap masukkan tahun";
		} 

		// HPL naigale
		if(bulan >=1 && bulan <= 3){
			HHT   = +HHT +7;
			bulan = +bulan + 9;
			tahun = +tahun + 0;
		} else if (bulan >= 4 && bulan <= 12){
			HHT   = +HHT +7;
			bulan = bulan - 3;
			tahun = +tahun + 1;	
		} 

		// validasi bulan & tahun
		if(bulan == 2){
			if(tahun%2==0){
				if(HHT>=29){
					HHT   = HHT - 29;
					bulan = bulan - 1;
				} 
			} else {
				if(HHT>=28){
					HHT = HHT - 28;
					bulan = bulan - 1;
				}
			}
		}else if(bulan%2==0){
			if(bulan==8){
				if(HHT>31){
					HHT   = HHT - 31;
					bulan = +bulan + 1;
				}
			} else if(bulan>12){
				if(HHT>30){
					HHT   = HHT - 30;
					bulan = bulan - 12;
					tahun = +tahun + 1;
				}else{
					bulan = bulan - 12;
					tahun = +tahun + 1;	
				}
			}else{
				if(HHT>30){
					HHT   = HHT - 30;
					if(bulan>=12){
						bulan = bulan - 11;			
					} else {
						bulan = +bulan + 1;	
					}
				}
			}

		} else if(bulan%2!=0){
			if(bulan>12){
				if(HHT>31){
					HHT   = HHT - 31;
					bulan = bulan - 12;
					tahun = +tahun + 1;
				}else{
					bulan = bulan - 11;
					tahun = +tahun + 1;	
				}
			}else if(HHT>31){
				HHT   = HHT - 31;
				bulan = +bulan + 1;	
			}
		}
		
		// konversi bulan
		if(bulan==1){
			bulan = "Januari";
		} else if(bulan==2){
			bulan = "Februari";
		} else if (bulan==3){
			bulan = "Maret";
		} else if (bulan==4){
			bulan = "April";
		} else if (bulan==5){
			bulan = "Mei";
		} else if (bulan==6){
			bulan = "Juni";
		} else if (bulan==7){
			bulan = "Juli";
		} else if (bulan==8){
			bulan = "Agutus";
		} else if (bulan==9){
			bulan = "September";
		} else if (bulan==10){
			bulan = "Oktober";
		} else if (bulan==11){
			bulan = "November";
		} else if (bulan==12){
			bulan = "Desember";
		} 

		if(check!=''){
			HPL = check;
		}else{
		  	HPL = HHT+' - '+bulan+' - '+tahun;
		}

		document.getElementById("HPL").innerHTML = HPL;
	};
</script>
</html>