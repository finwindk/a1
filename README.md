<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Bootstrap Site</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet" />
    <style>
        img:hover {
            transform: scale(1.05);
            transition: transform 0.3s ease;
        }
        button:hover {
            background-color: #0056b3 !important;
        }
    </style>
</head>
<body class="bg-white text-dark">
    <!-- Навігація -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">Лого</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#">Головна</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Про нас</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Контакти</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Основний блок -->
    <div class="container py-4">
        <div class="row align-items-center">
            <div class="col-md-8">
                <h2>Заголовок</h2>
                <p>Текстовий опис сторінки для приклада адаптивності Bootstrap.</p>
            </div>
            <div class="col-md-4 text-center">
                <img src="cat1.jpg" class="img-fluid rounded" alt="Cat 1" />
            </div>
        </div>

        <!-- Блок з котами -->
        <div class="row text-center mt-4">
            <div class="col-md-3 mb-3">
                <div class="border p-3 bg-light">
                    <img src="cat4.jpg" class="img-fluid rounded" alt="Cat 4" />
                    <p>Кіт №1</p>
                </div>
            </div>
            <div class="col-md-3 mb-3">
                <div class="border p-3 bg-light">
                    <img src="cat3.jpg" class="img-fluid rounded" alt="Cat 3" />
                    <p>Кіт №2</p>
                </div>
            </div>
            <div class="col-md-3 mb-3">
                <div class="border p-3 bg-light">
                    <img src="cat2.jpg" class="img-fluid rounded" alt="Cat 2" />
                    <p>Кіт №3</p>
                </div>
            </div>
            <div class="col-md-3 mb-3">
                <div class="border p-3 bg-light">
                    <img src="cat1.jpg" class="img-fluid rounded" alt="Cat 1" />
                    <p>Кіт №4</p>
                </div>
            </div>
        </div>

        <!-- Таблиця -->
        <table class="table table-bordered table-striped mt-4">
            <tr><th>Ім'я</th><td>Тест</td></tr>
            <tr><th>Вік</th><td>10</td></tr>
        </table>

        <!-- Форма -->
        <form class="w-50 mx-auto mt-4">
            <input class="form-control mb-2" type="text" placeholder="Ваше ім'я" required />
            <input class="form-control mb-2" type="email" placeholder="Email" required />
            <textarea class="form-control mb-2" placeholder="Повідомлення" required></textarea>
            <button class="btn btn-primary w-100">Надіслати</button>
        </form>
    </div>

    <!-- Футер -->
    <footer class="bg-light py-3 mt-4">
        <div class="container">
            <ul class="nav justify-content-center">
                <li class="nav-item"><a class="nav-link" href="#">Головна</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Про нас</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Контакти</a></li>
            </ul>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

