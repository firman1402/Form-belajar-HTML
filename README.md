# Form-belajar-HTML
Disini saya akan memberikan beberapa code sederhana dari html untuk membuat halaman tampilan form
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet">

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" 
    integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>

    <div class="nav-outer nav-copy">
        <nav class="navmenu-content">      
        </nav>
        <div class="nav-secondary">
        <label class="iconsearch-label" for="search-terms">
        <svg viewBox="0 0 24 24">
        <path d="M9.5,3A6.5,6.5 0 0,1 16,9.5C16,11.11 15.41,12.59 14.44,13.73L14.71,14H15.5L20.5,19L19,20.5L14,15.5V14.71L13.73,14.44C12.59,15.41 11.11,16 9.5,16A6.5,6.5 0 0,1 3,9.5A6.5,6.5 0 0,1 9.5,3M9.5,5C7,5 5,7 5,9.5C5,12 7,14 9.5,14C12,14 14,12 14,9.5C14,7 12,5 9.5,5Z"></path>
        </svg>
        </label>
        <div class="darkmode-switch" style="display: flex;">
        <span class="switch-title"></span>
        <label class="switch">
        <input aria-label="checkbox" class="checkbox" onclick="myFunction()" type="checkbox">
        <span class="slider"></span>
        </label>
        </div>
        </div>
        <button aria-label="menu" class="navmenu-button">
        <div></div>
        <div></div>
        <div></div>
        </button>
    </div>

    <title>New Qwebsite</title>
  </head>
  <body>

    <!-- Carousel -->
    <div id="carouselExampleInterval" class="carousel slide" data-bs-ride="carousel">

        <div class="carousel-inner">
          <div class="carousel-item active" data-bs-interval="10000" data-target="#carousel-example-generic" data-slide-to="0">           
            <img src="D:\Folder Kuliah\Kuliah Semester 4\Pemrograman Web Dasar\Utama\Pertemuan 4\File Code (Random)\Gambar\Lenovo.jpg" class="d-block w-100" alt="Konten Sensitif" style="height: 400px;">
          </div>
          <div class="carousel-item" data-bs-interval="2000" data-target="#carousel-example-generic" data-slide-to="2">
            <img src="D:\Folder Kuliah\Kuliah Semester 4\Pemrograman Web Dasar\Utama\Pertemuan 4\File Code (Random)\Gambar\Asus-ROG-Logo.jpg" class="d-block w-100" alt="Haa Kosong ???" style="height: 400px;">
          </div>
          <div class="carousel-item" data-bs-interval="1000" data-target="#carousel-example-generic" data-slide-to="3" class="">
            <img src="D:\Folder Kuliah\Kuliah Semester 4\Pemrograman Web Dasar\Utama\Pertemuan 4\File Code (Random)\Gambar\msi-logo.png" class="d-block w-100" alt="Tidur Bang" style="height: 400px;">           
          </div>
        </div>       
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleInterval" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleInterval" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>

      <!-- Containers -->
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-warning">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">Shop Go</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="D:\Folder Kuliah\Kuliah Semester 4\Pemrograman Web Dasar\Utama\Pertemuan 2\File Code (Random)\Latihan buat web sekaligus gambarnya\halaman2.html">Home</a>
              </li>
              <li class="nav-item">                
                <a class="nav-link" href="https://gudangtutorialwepe.blogspot.com" style="color: white" >Products</a>
              </li>
              <li class="nav-item dropdown">
                <a class="nav-link" href="Store.html" style="color: white">Store</a>
                </a>                
              </li>             
            </ul>
            <script src="skrip.js"></script>
            <link rel="stylesheet" type="text/css" href="style.css">
            <ul>
              
            </ul>
            <form class="d-flex">              
              <!-- Button trigger modal -->
<button type="button" class="btn btn-outline-primary" data-bs-toggle="modal" data-bs-target="#exampleModal">
  Login
</button>

<!-- Modal -->
            <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
              <script src="skrip.js"></script>
              <div class="modal-dialog">
                <div class="modal-content">
                  <div class="modal-header">
                    <h5 class="modal-title" id="exampleModalLabel">Login</h5>
                    <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                  </div>
                  <div class="modal-body"> Email Address                    
                    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="emailsaya123@gmail.com">
                    <div id="emailHelp" class="form-text">We'll never share your email with anyone else.</div>
                  </div>                                    
                  <div class="modal-body"> Password                    
                    <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Masukkan Password Anda">
                  </div>
                  <div class="ms-3 form-check">
                    <div>
                    <input type="checkbox" class="form-check-input" id="exampleCheck1">
                    <label class="form-check-label" for="exampleCheck1">Check me out</label>
                  </div>
                  <div class="modal-footer">
                    <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
                    <button type="button" class="btn btn-primary" data-bs-dismiss="modal">Save changes
                      
                    </button>
                    <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
                      <div class="modal-dialog">
                        <button type="button" class="btn-save" data-bs-dismiss="modal" aria-label="Save"></button>
                      </div>
                    </div>
                  </div>                                      
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            </form>          
        </div>
      </nav>
      <div class="card-group">
  <div class="card">
    <img src="D:\Folder Kuliah\Kuliah Semester 4\Pemrograman Web Dasar\Utama\Pertemuan 4\File Code (Random)\Gambar\AsusRog.jpg" class="card-img-top" alt="...">
    <div class="card-body">
      <h5 class="card-title">Asus Rog</h5>
      <h6 class="card-title">Harga mulai dari Rp. 12.xxx.xxx</h6>
      <p class="card-text">Laptop Asus ROG Gaming Platinum Series | Di jual Laptop Gaming merk Asus tipe ROG
        <br>
         Intel Core I7 Gen 9, Grapichs Card Nvidia GeForce RTX1080 
      </p>
      <p class="card-text"><small class="text-muted">Last updated 1 mins ago</small></p>
      <a href="https://rog.asus.com/id/"><button type="button" class="btn beli-1" data-bs-dismiss="modal">Beli</button></a>
    </div>
  </div>
  <div class="card ms-3">
    <img src="D:\Folder Kuliah\Kuliah Semester 4\Pemrograman Web Dasar\Utama\Pertemuan 4\File Code (Random)\Gambar\msi.png" class="card-img-top" alt="...">
    <div class="card-body">
      <h5 class="card-title">Laptop MSI Gaming || Internal Storage 1Tb - RAM 16GB || Black Series</h5>
      <h6 class="card-title">Harga mulai dari Rp. 9.xxx.xxx</h6>
      <p class="card-text">Laptop MSI Gaming Black Series | Di jual Laptop Gaming merk MSI warna hitam
        <br>
        Intel Core I9 Gen 11, Grapichs Card Nvidia GeForce 1080
        </p>             
      <p class="card-text"><small class="text-muted">Last updated 5 mins ago</small></p>
      <a href="https://id.msi.com/Business-Productivity/Modern-14-B11X?utm_term=harga%20laptop%20msi&utm_campaign=&utm_source=adwords&utm_medium=ppc&hsa_acc=1378962706&hsa_cam=16872726864&hsa_grp=136749036898&hsa_ad=592725058310&hsa_src=g&hsa_tgt=kwd-302103467209&hsa_kw=harga%20laptop%20msi&hsa_mt=b&hsa_net=adwords&hsa_ver=3&gclid=CjwKCAjw9e6SBhB2EiwA5myr9ljSXVR3EyRi-NxHClkC2fSECx_X0enyXiPFrb9d1ub0YKJCKC5OshoCtFkQAvD_BwE"><button type="button" class="btn beli-1" data-bs-dismiss="modal">Beli</button></a>
    </div>
  </div>
  <div class="card ms-3">
    <img src="D:\Folder Kuliah\Kuliah Semester 4\Pemrograman Web Dasar\Utama\Pertemuan 4\File Code (Random)\Gambar\Lenovo Ideapad Gaming 3i.jpg" class="card-img-top" alt="...">
    <div class="card-body">
      <h5 class="card-title">Lenovo Gaming Ideapad 3i</h5>
      <h6 class="card-title">Harga mulai dari Rp. 10.xxx.xxx</h6>
      <p class="card-text">Laptop Lenovo Gaming Ideapad 3i | Di jual Laptop Gaming merk Lenovo warna biru metallic
        <br>
        spesifikasi :
        <br>
        AMD Radeon R7 <br>
        RAM 32GB <br>
        Internal Storage 2TB <br>
        Microsoft Home Student <br>
      </p>
      <p class="card-text"><small class="text-muted">Last updated 3 hrs ago</small></p>
      <a href="https://www.lenovo.com/id/in/"><button type="button" class="btn beli-1" data-bs-dismiss="modal">Beli</button></a>
    </div>
  </div>
</div>      
  </body>
</html>
