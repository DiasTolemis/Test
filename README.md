<!DOCTYPE html>
<html>
<head>
	<title>Example</title>
	<link rel="stylesheet" type="text/css" href="exampl.css">
</head>
<body>
	<style>
		body{
  padding: 0;
  margin: 0;
}
.dias{
  height: 90px;
  background-color: #002452;
  position: relative;
}
.dias1{
  position: relative;
  top: 25px;
  left: 150px;
  font-size: 35px;
  color: #38a7cb;
}
.dias2{
  position: relative;
  top: 25px;
  left: 830px;
  color: white;
  word-spacing: 10px;
}
.dias2:hover{
  color: #38a7cb;
}
.diast{
  height: 630px;
  background-color: #38a7cb;
}
.diast1{
  position: relative;
  top: 40px;
  left: 280px;
  margin-bottom: 90px;
}
.diast2{
  font-size: 40px;
  color: white;
}
.diast3{
  color: white;
  font-size: 20px;
  word-spacing: 5px;
}
.diasto{
  display: inline-block;
  width: 100%;
  margin-left: 275px;
}
.diasto1{
  display: inline-block;
  width: 35%; 
  vertical-align: top;
  font-size:20px;
  margin-left: 150px;
}
	</style>
		<div class="dias">
			<span class="dias1">John Doe</span>
			<span class="dias2">About  me </span>
			<span class="dias2">Professional  Experience </span>
			<span class="dias2">Contact</span>
		</div>
		<div class="diast">
			<div class="diast1">
				<span class="diast2"><strong>+About me</strong></span><br>
				<span class="diast3"><p>My name is John Doe, I am multi diciplinar designer</p></span>
				<span class="diast3"><p>Morbi leo risus, porta ac consectetur ac, vestibulum at ero bendum nibh.</p></span><br>
			</div>
			<div class="diasto">
				<img src="https://st2.depositphotos.com/1144472/10857/i/950/depositphotos_108575196-stock-photo-happy-smiling-businessman-with-okay.jpg" width="300" height="300" style="border-radius: 100%;
				border: 2px solid black;">
				<div class="diasto1">
					<span style="word-spacing: 150px;"> Name </span><span>John Doe Manhattan</span><hr>
					<span style="word-spacing: 157px;">Born </span><span>12 October 1985</span><hr>
					<span style="word-spacing: 135px;">Address </span><span>Las Rozas, Madrid, Spain</span><hr>
					<span style="word-spacing: 152px;">Email </span><span>myemail@gmail.com</span><hr>
					<span style="word-spacing: 136px;">Website </span><span>www.virgiliolavego.com</span><hr>
					<span style="word-spacing: 150px;">Phone </span><span>+34 123 456 789</span><hr>
				</div>
			</div>
		</div>
		<div style="background-color: grey; width: 100%; height: 30px;"></div>
</body>
</html>
