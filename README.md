<!DOCTYPE html>
<html>

<head>
    <titleNavbar dengan Bootstrap 5</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.0.2/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
</head>

<body data-bs-spy="scroll" data-bs-target="#navbarNav" data-bs-offset="100">
    <nav class="navbar navbar-expand-lg navbar-light bg-light fixed-top">
        <div class="container-fluid">
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link active" href="#beranda">Beranda</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#tentang">Tentang</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#kisahku">Kisahku</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#pendidikan">Pendidikan</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#tugas">Tugas</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <div id="beranda" class="container-fluid bg-light p-5">
        <h2 class="text-center">Beranda</h2>
        <div class="container mt-5">
            <div class="row">
                <div class="col-md-8 mx-auto">
                    <div class="jumbotron">
                        <div class="row">
                            <div class="col-md-4">
                                <img src="Rere.JPG" alt="Foto Profil"
                                    class="img-fluid rounded-circle">
                            </div>
                            <div class="col-md-8">
                                <hr class="my-4">
                                <h1 class="display-4">RHESSIA YENANDA PUTRI</h1>
                                <p class="lead">NIM : 215314055</p>
                                <hr class="my-4">
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div id="tentang" class="container-fluid bg-secondary p-5">
        <h2 class="text-center mb-4">Tentang</h2>
        <div class="container mt-5">
            <div class="row">
                <div class="col-md-8 mx-auto">
                    <p class="lead text-center">Gambaran diri:</p>
                    <p class="text-justify">Saya merupakan salah satu mahasiswa Sanata Dharma Yogyakarta saya berasal dari Kalimantan Barat
                        dan sekarang saya masuk di prodi Informatika Sanata Dharma, Alasan saya memilih Sanata Dharma 
                        adalah saran dari temen-teman saya dan saya juga tertarik pada kota Yogyakarta sepertinya sangat seru kalau bisa
                        kuliah di jogja dan akhirnya saya berkuliah di Yogyakarta sekarang walaupun saya sering merasa kesepian karna jauh dari 
                        orang tua tetapi saya juga senang karena saya banyak bertemu dengan teman-teman yang baru dan pastinya ada banyak kegiatan atau 
                        organisasi yang bisa di ikuti sehingga bisa bermanfaat untuk pengalaman saya kedepannya.</p>
                </div>
                <div class="col-md-4 mx-auto">
                    <img src="Rere2.jpg" alt="Foto Profil" class="img-fluid rounded" width="50%" style="width: 150px; height: 250px; object-fit: cover; object-position: 25% 50%;">
                </div>
            </div>
        </div>
    </div>

    <div id="kisahku" class="container-fluid bg-success p-5">
        <h2 class="text-center mb-4">Kisahku</h2>
        <p>Ini adalah kisah ku, aku adalah seorang anak pertama di keluarga ku dan aku memiliki satu orang adik, aku 
            lahir dan besar di Kalimantan Barat, suku ku yaa sudah pasti suku Dayak. Mungkin banyak orang yang mengira bahwa suku Dayak
            itu menyeramkan dan menakutkan. Padahal sebenarnya tidak sama sekali, aku sering banget di tanyain teman-teman pernah liat kuyang 
            apa ngga, yaa pastinya ngga dong, bahkan ada yang takut tauu sama orang Dayak, padahal gaa kayak gitu, sampai 
            ada satu kejadian yang membuat aku merasa tidak nyaman karena setiap ketika orang itu mendengar aku dari suku Dayak dia 
            jadi takut dan menjauh. Pliss yaa suku Dayak itu ngga seseramm ituuu teman-teman.
        </p>
    </div>

    <div id="pendidikan" class="container-fluid bg-info p-5">
        <div class="container mt-5">
            <h2 class="text-center mb-4">Pendidikan</h2>
            <table class="table table-striped">
                <thead>
                    <tr>
                        <th>Tahun</th>
                        <th>Nama Sekolah</th>
                        <th>Alamat Sekolah</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>2015-2018</td>
                        <td>SMP Negeri 2 Nanga Pinoh</td>
                        <td>Melawi, Kalimantan Barat</td>
                    </tr>
                    <tr>
                        <td>2018-2021</td>
                        <td>SMA Kristen Ekklesia Nanga Pinoh</td>
                        <td>Melawi, Kalimantan Barat</td>
                    </tr>
                    <tr>
                        <td>2021-Sekarang</td>
                        <td>Universitas Sanata Dharma</td>
                        <td>Sleman, Yogyakarta</td>
                    </tr>
                </tbody>
            </table>
        </div>

    </div>

    <div id="tugas" class="container-fluid bg-dark text-light p-5">
        <h2 class="text-center mb-4">Tugas</h2>
        <div class="container mt-4">
            <form>
                <div class="mb-3">
                    <label for="namaDep" class="form-label">Nama Depan</label>
                    <input type="text" class="form-control" id="namaDep" aria-describedby="namaDep">
                </div>
                <div class="mb-3">
                    <label for="namaBel" class="form-label">Nama Belakang</label>
                    <input type="text" class="form-control" id="namaBel" aria-describedby="namaBel">
                </div>
                <div class="mb-3">
                    <label for="email" class="form-label">Email</label>
                    <input type="text" class="form-control" id="email" aria-describedby="email">
                </div>
                <div class="mb-3">
                    <label for="jumPil" class="form-label">Masukan Berberapa Hobi</label>
                    <input type="integer" class="form-control" id="jumPil" aria-describedby="jumPil">
                </div>
                <button type="submit" class="btn btn-primary" onclick="kirim()">Submit</button>
                <div id="choose1"></div>
                <div id="button1"></div>
                <form>
                    <div id="list"></div>
                    <div id="submit1"></div>
                </form>
                <p id="result"></p>
            </form>

        </div>

    </div>

    <script src="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.0.2/js/bootstrap.bundle.min.js"></script>
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.3/dist/umd/popper.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta2/dist/js/bootstrap.min.js"></script>

    <script>
        function kirim() {
            var jumPil = document.getElementById("jumPil").value;
            var button1x;
            var ans = "";

            for (var i = 1; i <= jumPil; i++) {
                ans += "<p><label for='hobisaya' class='form-label'>Hobi ke - </label>" + i + "<input type='text' class='form-control' id='hobisaya" + i + "' aria-describedby='hobisaya' placeholder = 'Masukkan Hobi'>" + "</p>";
            }
            button1x = "<p>" + '<button type="button" class="btn btn-primary" onclick="buatCheck()">Submit</button>' + "</p>";
            document.getElementById("choose1").innerHTML = ans;
            document.getElementById("button1").innerHTML = button1x;
        }

        function buatCheck() {
            var masuk = form.getElementsByTagName("input");
            var form = document.getElementById("choose1");
            var submit;
            var box = "";

            for (var i = 0; i < masuk.length; i++) {
                if (masuk[i].type == "text") {
                    box += '<input type="checkbox" name="option" value="' + masuk[i].value + '">' + masuk[i].value + "<br>";
                }
            }
            submit = '<input type="button" class="btn btn-primary" onclick="cetak()" value="Submit">';
            document.getElementById("submit1").innerHTML = submit;
            document.getElementById("list").innerHTML = box;
        }

        function cetak() {
            var testName = document.getElementById("namaDep");
            var testName2 = document.getElementById("namaBel");
            var email = document.getElementById("email");
            var form = document.querySelector("form");
            var box = "";
            var result = document.getElementById("result");
            var jumPil = document.getElementById("jumPil").value;
            var form1 = document.getElementById("choose1");
            var masuk = form1.getElementsByTagName("input");

            for (var i = 0; i < masuk.length; i++) {
                if (masuk[i].type == "checkbox" && masuk[i].checked) {
                    box += masuk[i].value + ", ";
                }
            }

            var selectedOptions = document.querySelectorAll('input[name="option"]:checked');

            if (selectedOptions.length > 0) {
                var options = [];
                for (var i = 0; i < selectedOptions.length; i++) {
                    options.push(selectedOptions[i].value);
                }
                result.innerHTML = "<br>Hallo, nama saya " + testName.value + " " + testName2.value + ", dengan email " + email.value + ", 
                saya mempunyai sejumlah " + jumPil + " pilihan hobi yaitu ";

                for (var i = 1; i <= jumPil; i++) {
                    result.innerHTML += document.getElementById("hobisaya" + i).value + ", ";
                }

                result.innerHTML += "dan saya menyukai " + options.join(", ") + ".";
            } else {
                result.textContent = "Pilih salah satu opsi.";
            }
        }
    </script>
</body>

</html>
