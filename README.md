# Boostrap-School-Page
Boostrap İle yaklaşık 1 saat içerisinde hazırlanabilecek sayfa
<!DOCTYPE html>
<html lang="tr">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Fatih Anadolu Lisesi</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-eOJMYsd53ii+scO/bJGFsiCZc+5NDVN2yr8+0RDqr0Ql0h+rP48ckxlpbzKgwra6" crossorigin="anonymous">

  <link rel="stylesheet" href="css/main.css">
  <link rel="stylesheet" href="css/global.css">
</head>

<body>
  <!-- <div class="bg-image" style=" background-image: url('images/okul2.png'); height: 100vh;
  background: url(images/okul2.png) no-repeat center center fixed; 
              -webkit-background-size: cover;
              -moz-background-size: cover;
              -o-background-size: cover;
              background-size: cover;">
    </div> -->

  <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Fatih Anadolu Lisesi</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav nav-tabs me-auto mb-2 mb-lg-0">
          <li class="nav-item ">
            <a class="nav-link" aria-current="page" href="#">Okulumuz Hakkında</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Etkinliklerimiz</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown"
              aria-expanded="false">
              Ödüllü Öğretmenlerimiz
            </a>
            <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
              <li><a class="dropdown-item" href="#">Action</a></li>
              <li><a class="dropdown-item" href="#">Another action</a></li>
              <li>
                <hr class="dropdown-divider">
              </li>
              <li><a class="dropdown-item" href="#">Something else here</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Disabled</a>
          </li>
        </ul>
        <form class="d-flex">
          <input class="form-control me-2" type="search" placeholder="Arama yapın.." aria-label="Search">
          <button class="btn btn-outline-primary" type="submit">Ara</button>
        </form>
      </div>
    </div>
  </nav>


  <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
    <ol class="carousel-indicators">
      <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
      <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
      <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
    </ol>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img class="d-block w-100" src="images/okul2.png" alt="First slide">
        <div class="carousel-caption d-none d-md-block">
          <h3>Geleneksel Bahar Şenliği Etkinliğimiz</h3>
          <p>Bu sene öğrencilerimizle beraber 5. şenliğimizi gerçekleştirdik...</p>
        </div>
      </div>
      <div class="carousel-item">
        <img class="d-block w-100" src="images/okul2.png" alt="Second slide">
      </div>
      <div class="carousel-item">
        <img class="d-block w-100" src="images/okul2.png" alt="Third slide">
      </div>
    </div>
    <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="sr-only" style="color: white;">Previous</span>
    </a>
    <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="sr-only" style="color: white;">Next</span>
    </a>
  </div>


  <div class="container marketing">
    <div class="row">
      <div class="col-lg-4">
        <img class="rounded-circle" src="images/tubitak.png" alt="Tubitak" width="140" height="140">
        <h2>Tubitak Yarışması</h2>
        <p>Okulumuz her sene olduğu gibi bu sene de Tubitak Bilim Fuarına katıldı ve aldığı başarılarla hepimizi
          gururlandırdı.</p>
        <p><a class="btn btn-secondary" href="#" role="button">Daha Fazla Bilgi</a></p>
      </div><!-- /.col-lg-4 -->
      <div class="col-lg-4">
        <img class="rounded-circle" src="images/muzik-yarismasi.jpg" alt="Müzik" width="140" height="140">
        <h2>Müzik Yarışması</h2>
        <p>Okulumuz Türkiye Geneli "Sahne Senin" adlı müzik yarışmasına hocamız Sayın Mahmut Yıldırım öncüülüğünde
          hazırlanmaktadır. </p>
        <p><a class="btn btn-secondary" href="#" role="button">Daha Fazla Bilgi</a></p>
      </div><!-- /.col-lg-4 -->
      <div class="col-lg-4">
        <img class="rounded-circle" src="images/futbol.jpg" alt="Futbol" width="140" height="140">
        <h2>Futbol Turnuvası</h2>
        <p>Okul futbol takımımız "Adıyaman Liselerarası Futbol Turnuvası" yarışmasında ikinci olarak kupayı okulumuza
          kazandırmıştır.</p>
        <p><a class="btn btn-secondary" href="#" role="button">Daha Fazla Bilgi</a></p>
      </div><!-- /.col-lg-4 -->
    </div>
  </div>


  <!-- Footer -->
  <footer class="text-center text-lg-start" style="background-color: #C6C7C8;">
    <!-- Grid container -->
    <div class="container p-4">
      <!--Grid row-->
      <div class="row">
        <!--Grid column-->
        <div class="col-lg-4 col-md-12 mb-4 mb-md-0">
          <h5 class="text-uppercase">Vizyonumuz</h5>

          <p>
            Eğitim-öğretimde kalitesi ve başarılı çalışmaları ile fark yaratan seçkin bir kurum olmaktır.
          </p>
        </div>
        <!--Grid column-->

        <!--Grid column-->
        <div class="col-lg-4 col-md-6 mb-4 mb-md-0">
          <h5 class="text-uppercase">Misyonumuz</h5>

          <p>
            Mutlu, özgüvenli, başarılı, ilkeli, duyarlı, açık fikirli, araştıran-sorgulayan, iletişim becerileri
            gelişmiş, öğrenmeye ve yeniliklere açık, entelektüel, öz değerlendirme yapabilen, iş birliğine yatkın,
            yaratıcı ve eleştirel düşünen, akılcı, cesaretli, çok yönlü, ulusal kültürünü özümsemiş, aynı zamanda
            küresel bakış açısına sahip bireyler yetiştirmektir.
          </p>
        </div>
        <!--Grid column-->

        <!--Grid column-->
        <div class="col-lg-4 col-md-6 mb-4 mb-md-0 contact">
          <h5 class="text-uppercase mb-0 text-center head-contact">Bize Ulaşın</h5>
          <div class="container">
            <form action="action_page.php">

              <label for="fname">İsim</label>
              <br>
              <input type="text" id="fname" name="firstname" placeholder="İsminizi yazın..." class="name">
              <br>

              <label for="lname">Soyisim</label>
              <br>
              <input type="text" id="lname" name="lastname" placeholder="Soyismizi yazın..." class="lastname">
              <br>

              <label for="country">Ülke</label>
              <br>
              <select id="country" name="country" class="country">
                <option value="australia">Türkiye</option>
                <option value="canada">İngiltere</option>
                <option value="usa">Diğer</option>
              </select>
              <br>

              <label for="subject">Mesaj</label>
              <br>
              <textarea class="message-box" id="subject" name="subject" placeholder="Mesajınızı Yazın..."
                style="height:200px" cols="40"></textarea>
              <br>
              <input type="submit" value="Gönder" class="submit btn-outline-primary">

            </form>
          </div>


        </div>
        <!--Grid column-->
      </div>
      <!--Grid row-->
    </div>
    <!-- Grid container -->

    <!-- Copyright -->
    <div class="text-center text-light p-3" style="background-color: black">
      © 2021 Copyright:
      <a class="text-light linkokul" href="https://fatihanadolu.meb.k12.tr/">FatihAnadoluLisesi.com</a>
    </div>
    <!-- Copyright -->
  </footer>
  <!-- Footer -->
  <!-- Boostrap Javascript -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-JEW9xMcG8R+pH31jmWH6WWP0WintQrMb4s7ZOdauHnUtxwoG2vI5DkLtS3qm9Ekf"
    crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.1/dist/umd/popper.min.js"
    integrity="sha384-SR1sx49pcuLnqZUnnPwx6FCym0wLsk5JZuNx2bPPENzswTNFaQU1RDvt3wT4gWFG"
    crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/js/bootstrap.min.js"
    integrity="sha384-j0CNLUeiqtyaRmlzUHCPZ+Gy5fQu0dQ6eZ/xAww941Ai1SxSY+0EQqNXNE6DZiVc"
    crossorigin="anonymous"></script>
</body>

</html>
