<!DOCTYPE html>
<html>
<head>
	<style>
	.searchContainer #searchButton {
	color: blue;
    background-color: white;
    border: none;
    height: 36px;
    width: 125px;
    border-radius: 5px;
    border: 1px solid blue;
    font-size: 13px;
    font-weight: bold;
    margin-top: 20px;
    cursor: pointer;
    outline: none;
}
    .searchContainer #searchButton:hover {
	color: white;
    background-color: blue;
}
	</style>
	<title>Welcome to Apidom</title>
	<meta name="description" content="Search the web for sites and images.">
	<meta name="keywords" content="Search engine, apidom, websites">
	<meta name="author" content="Anubrata Sarker">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<link rel="stylesheet" type="text/css" href="assets/css/style.css">
</head>
<body>
	<div class="wrapper indexPage">
	
		<div class="mainSection">
			<div class="logoContainer">
				<img style="border-radius: 10px;" src="assets/images/Apidom.webp" title="Logo of our site" alt="Site logo">
			</div>
			<div class="searchContainer">
				<form action="search.php" method="GET">
					<input class="searchBox" type="text" name="term">
					<input id="searchButton" class="searchButton" type="submit" value="Search">
				</form>
			</div>
		</div>
	</div>
</body>
</html>
