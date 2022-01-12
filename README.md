# Sample-HTML-CSS-Javascript-Programs
1st year HTML,CSS and JavaScript programs(2022)
<!DOCTYPE html>
<html lang="en-us">
<head>
<meta keyword="travelholic" content="homepage">
<title>TravelHolic Home-page</title>
<link rel="icon" type="image/png" href="/d:/64009/logo.png" size="20x20">
</head>
<style>
	#topcorner{ float:right;
	padding: 0px 16px;background-color:dimgrey}
	#topcorner{
	list-style: none;font-size:24px;
	}
	#topcorner:hover{background-color:blanchedalmond;}
	#icons{list-style:none;padding:0px 0px 0px 0px;margin-top:-110px;}
	a{text-decoration:none;}
	table{margin:20px 200px 20px 200px;width:80%;height:20%;border:2px solid black}
	th,td{font-size:30px;border:1px solid black;background-color:darksalmon}
	select{width:100%;height:40px;background-color:darksalmon;font-size:24px}
	#date{width:100%;height:30px;background-color:darksalmon;font-size:24px}
	#submit{width:10%;height:30px; margin:0px 0px 0px 1000px;color:green}
	body{background-size:100% 48%;
		background-repeat:no-repeat}
	.handpicks{padding:20px;}
	.handpicks:hover{transform:scale(1.5)}
	
</style>
<body  style="background-image:URL('/d:/64009/worldd.jpg');">
<img src="/D:/64009/logo.png" alt="Travelholic logo" width="170" height="120" border="2px solid black">
<ul >
	<li id="topcorner"><a href="login.html">login</a></li>
	<li id="topcorner"><a href="popularroutes.html">Popular Routes</a></li>
	<li id="topcorner"><a href="support.html">Support</a></li>
	<li id="topcorner"><a href="manage.html">Manage</a></li>
</ul>
<p style="font-size:14px;color:black"><i><b>CONNECTING THE WORLD!!!</b></i></P>
<hr>
<forms><b><fieldset style="background-color:azure">
<label for="mode">One-Way</label>
<input type="radio" name="mode">
<label for="mode">Return</label>
<input type="radio" name="mode">
<label for="mode">Multi-Way</label>
<input type="radio" name="mode"></fieldset></b>
</forms>
<table>
<tr>
	
	<th>From:</th>
	<th>To:</th>
	<th>Date of Travel:</th>
	<th>No.of.Travellers:</tr>
	<tr>
	<td><forms>
		<select placeholder="From">
			 <option value=" "disabled selected hidden>From</option>
			<option value="Madurai">Madurai</option>
			<option value="Chennai">Chennai</option>
			<option value="Delhi">Delhi</option>
			<option value="Goa">Goa</option>
			<option value="Kolkatta">Kolkatta</option>
			<option value="Mumbai">Mumbai</option>
			<option value="Hyderabad">Hyderabad</option>
			<option value="Banglore">Banglore</option>
			<option value="Cochin">Cochin</option>
			<option value="Trivandrum">Trivandrum</option>
			<option value="Kanniyakumari">Kanniyakumari</option>
			<option value="Rameshwaram">Rameshwaram</option>
			<option value="Kodaikanal">Kodaikanal</option>
			<option value="Ooty">Ooty</option>
			<option value="Shimla">Shimla</option>
			<option value="Darjeeling">Darjeeling</option>
			<option value="Agra">Agra</option>
		</select>
		</forms></td>
	<td><forms>
		<select>
			<option value=" "disabled selected hidden>To</option>
			<option>Mumbai</option>
			<option>Kolkatta</option>
			<option value="Madurai">Madurai</option>
			<option value="Chennai">Chennai</option>
			<option value="Delhi">Delhi</option>
			<option value="Goa">Goa</option>
			<option value="Darjeeling">Darjeeling</option>
			<option value="Agra">Agra</option>
			<option value="Hyderabad">Hyderabad</option>
			<option value="Banglore">Banglore</option>
			<option value="Cochin">Cochin</option>
			<option value="Trivandrum">Trivandrum</option>
			<option value="Kanniyakumari">Kanniyakumari</option>
			<option value="Rameshwaram">Rameshwaram</option>
			<option value="Kodaikanal">Kodaikanal</option>
			<option value="Ooty">Ooty</option>
			<option value="Shimla">Shimla</option>
		</select>
		</forms>
	</td>
	<td><forms>
		<input type="date" id="date">
	</forms></td>
	<td><forms>
		<input type="number" id="date">
	</forms></td></div>
</table>
<ul id="icons">
	
	<li><a href="hotelbooking.html"><img  src="/d:/64009/hotelbooking.jpg" alt="hotel booking" width="80px" height="80px" 		border="2px solid black"></a></li>
	<li><a href="flightbooking.html"><img src="/d:/64009/flightbooking.png" alt="Flight Booking" width="80px" height="80px" 	border="2px solid black"></a></li>
	<li><a href="trainbooking.html"><img src="/d:/64009/trainbooking.png" alt="Train Booking" width="80px" height="80px" border="2px solid black"></a></li>
	<li><a href="busbooking.html"><img src="/d:/64009/busbooking.jpg" alt="Bus Booking" width="80px" height="80px" border="2px solid black"></a></li>
</ul>	
<input  id="submit" type="submit">
<h1 style="color:midnightblue">Top Hand-Picks!!!!<hr></h1>
<a href="summer.html" class="handpicks" target="_blank"><img src="/d:/64009/summer.jpg" alt="Top 10 places to Visit in Summer" width="20%" style="border:2px solid black"></a>
<a href="winter.html" class="handpicks" target="_blank"><img src="/d:/64009/winter.jpg" alt="Top 10 places to Visit in Winter" width="20%" height="200px" style="border:2px solid black"></a>
<a href="heritage.html" class="handpicks" target="_blank"><img src="/d:/64009/heritage.jpg" alt="Top 10 Heritage Places to Visit" width="20%" height="200px" style="border:2px solid black"></a>
<a href="hillstations.html" class="handpicks" target="_blank"><img src="/d:/64009/hillstations.jpg" alt="Top 10 Hill Stations to Visit" width="20%" height="200px" style="border:2px solid black"></a><br>
<a href="beaches.html" class="handpicks" target="_blank"><img src="/d:/64009/beaches.jpg" alt="Top 10 Beaches to Visit" width="20%" height="200px" style="border:2px solid black"></a>
<a href="sancturies.html" class="handpicks" target="_blank"><img src="/d:/64009/sancturies.jpg" alt="Top 10 Wildlife Sancturies to Visit" width="20%" height="200px" style="border:2px solid black"></a>
<a href="cities.html" class="handpicks" target="_blank"><img src="/d:/64009/cities.jpg" alt="Top 10 Cities to Visit" width="20%" height="200px" style="border:2px solid black"></a>
<a href="temples.html" class="handpicks" target="_blank"><img src="/d:/64009/temples.jpg" alt="Top 10 Temples to Visit" width="20%" height="200px" style="border:2px solid black"></a><br>
<a href="themeparks.html" class="handpicks" target="_blank"><img src="/d:/64009/themeparks.jpg" alt="Top 10 Themeparks to Visit" width="20%" height="200px" style="border:2px solid black"></a>
<a href="museums.html" class="handpicks" target="_blank"><img src="/d:/64009/museums.jpg" alt="Top 10 Museums to Visit" width="20%" height="200px" style="border:2px solid black"></a>
</body>
</html>
