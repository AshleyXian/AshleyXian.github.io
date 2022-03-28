<!doctype html>
<html lang="en">

<head>
  <!-- Required meta tags -->
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Hubballi&display=swap" rel="stylesheet">

  <!-- Bootstrap CSS -->
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css"
    integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">

  <!-- Custom CSS -->
  <link rel="stylesheet" href="app.css">

  <title>Fufu's Album</title>
</head>

<body>
  <nav id="mainNavbar" class="navbar navbar-dark navbar-expand-md py-0 fixed-top">
    <a href="#" class="navbar-brand">Fufu</a>
    <button class="navbar-toggler" data-toggle="collapse" data-target="#navLinks" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navLinks">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a href="" class="nav-link">Home</a>
        </li>
        <li class="nav-item">
          <a href="" class="nav-link">About</a>
        </li>
        <li class="nav-item">
          <a href="" class="nav-link">Contact</a>
        </li>
      </ul>
    </div>
  </nav>

  <section class="container-fluid px-0">
    <div class="row align-items-center">
      <div class="col-md-6">
        <div id="headingGroup" class="text-white text-center d-none d-md-block">
          <h1 class="">Two-month old</h1>
          <h1 class="">Two-month old</h1>
          <h1 class="">Two-month old</h1>
        </div>
      </div>
      <div class="col-md-6">
        <img class="img-fluid" src="photos/two_month.jpg" alt="">
      </div>
    </div>
  </section>

  <section class="container-fluid px-0">
    <div class="row align-items-center content">
      <div class="col-md-6 order-2 order-md-1">
        <img src="photos/six_month.jpg" class="img-fluid" alt="">
      </div>
      <div class="col-md-6 text-center order-1 order-md-2">
        <div class="row justify-content-center">
          <div class="col-10 col-lg-8 fufu mb-5 mb-md-0">
            <h2>Six-month old</h2>
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Laudantium molestias quos eos atque corrupti
              vitae,
              harum deserunt maxime, quis rem obcaecati ducimus vero laboriosam sit tempora quibusdam ut possimus eaque.
            </p>
          </div>
        </div>
      </div>
    </div>

    <div class="row align-items-center content">
      <div class="col-md-6 order-2">
        <img src="photos/one_year.jpg" class="img-fluid" alt="">
      </div>
      <div class="col-md-6 text-center order-1">
        <div class="row justify-content-center">
          <div class="col-10 col-lg-8 fufu mb-5 mb-md-0">
            <h2>One-year old</h2>
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Laudantium molestias quos eos atque corrupti
              vitae,
              harum deserunt maxime, quis rem obcaecati ducimus vero laboriosam sit tempora quibusdam ut possimus eaque.
            </p>
          </div>
        </div>
      </div>
    </div>

    <div class="row align-items-center content">
      <div class="col-md-6 order-2 order-md-1">
        <img src="photos/one_and_half.jpg" class="img-fluid" alt="">
      </div>
      <div class="col-md-6 text-center order-1 order-md-2">
        <div class="row justify-content-center">
          <div class="col-10 col-lg-8 fufu mb-5 mb-md-0">
            <h2>Now</h2>
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Laudantium molestias quos eos atque corrupti
              vitae,
              harum deserunt maxime, quis rem obcaecati ducimus vero laboriosam sit tempora quibusdam ut possimus eaque.
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- jQuery first, then Popper.js, then Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"
    integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo"
    crossorigin="anonymous"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js"
    integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49"
    crossorigin="anonymous"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js"
    integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy"
    crossorigin="anonymous"></script>

  <!-- Optional JavaScript -->
  <script>
    $(function () {
      $(document).scroll(function () {
        var $nav = $("#mainNavbar");
        $nav.toggleClass("scrolled", $(this).scrollTop() > $nav.height());
      });
    });
  </script>

</body>

</html>
