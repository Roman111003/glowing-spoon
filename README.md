<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Кинотеатр</title>
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
<style>
body {
background-color: #00DDDD;
}
.navbar {
background-color: #AAFFFF;
}
.navbar-brand {
color: #004444;
}
.nav-link {
color: #004444;
}
.movie-card {
margin-bottom: 20px;
padding: 20px;
background-color: #FFEEFF;
border-radius: 5px;
}
.movie-image {
width: 100%;
height: auto;
margin-bottom: 10px;
}
.movie-title {
font-weight: bold;
font-size: 18px;
margin-bottom: 5px;
}
.movie-description {
font-size: 14px;
color: #bbffff;
margin-bottom: 10px;
}
.buy-ticket-btn {
background-color: #AAAAAA;
color: #44FFFF;
border: none;
padding: 5px 10px;
border-radius: 3px;
cursor: pointer;
}
.buy-ticket-btn:hover {
background-color: #CCCCFF;
}
</style>
</head>
<body>
<nav class="navbar navbar-expand-lg">
<a class="navbar-brand" href="#">Cinema</a>
<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
<span class="navbar-toggler-icon"></span>
</button>
<div class="collapse navbar-collapse" id="navbarNav">
<ul class="navbar-nav">
<li class="nav-item active">
<a class="nav-link" href="#">Schedule</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#">Films</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#">Menu</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#">Tickets</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#">Contacts</a>
</li>
</ul>
</div>
</nav>

<div class="container">
<div class="row">
<div class="col-md-4">
<div class="movie-card">
<img src="https://images.wallpaperscraft.ru/image/single/akitainu_sobaka_morda_53104_1152x864.jpg" alt="Hachiko Movie" class="movie-image">
<h3 class="movie-title">Film "Hachiko"</h3>
<p class="movie-description">Description of the film "Hachiko".</p>
<button class="buy-ticket-btn">Buy a ticket<form action="https://securepayments.sberbank.ru/payment/docsite/payform.html" method="POST">
 <input type="hidden" name="userName" value="Your_user_Name" />
 <input type="hidden" name="password" value="Your_parol" />
 <input type="hidden" name="orderNumber" value="123456789" />
 <input type="hidden" name="amount" value="100.00" />
 <input type="hidden" name="description" value="Payment for the goods" />
 <input type="submit" value="To pay" />
 </form»
</div>
</div>
</div>
</div>

<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.3/dist/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
