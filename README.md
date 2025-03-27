<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mock Browser Layout</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f8f9fa;
      color: #000;
    }

    .browser-frame {
      width: 90%;
      max-width: 1200px;
      margin: 20px auto;
      border: 10px solid #ccc;
      border-radius: 10px;
      background: white;
      overflow: hidden;
    }

    .browser-header {
      background: #e0e0e0;
      padding: 8px 15px;
      display: flex;
      align-items: center;
    }

    .browser-buttons {
      display: flex;
      gap: 5px;
      margin-right: 15px;
    }

    .browser-buttons div {
      width: 12px;
      height: 12px;
      border-radius: 50%;
    }

    .red {
      background: #ff5f56;
    }

    .yellow {
      background: #ffbd2e;
    }

    .green {
      background: #27c93f;
    }

    #header-nav {
      background-color: #999;
    }

    .navbar-brand {
      font-size: 1.5em;
      font-weight: bold;
      color: #000;
    }

    #nav-list {
      background-color: #ddd;
    }

    #nav-list a {
      color: #000;
      text-align: center;
      border-bottom: 1px solid #000;
      padding: 10px;
      display: block;
    }

    #nav-list a:hover {
      background: #fff;
    }

    .menu-item {
      background-color: #999;
      padding: 20px;
      margin-bottom: 30px;
    }

    .menu-item h3 {
      font-weight: bold;
      margin-top: 0;
    }
  </style>
</head>

<body>
  <header>
    <div class="browser-frame">
      <div class="browser-header">
        <div class="browser-buttons">
          <div class="red"></div>
          <div class="yellow"></div>
          <div class="green"></div>
        </div>
        <input type="text" class="form-control" value="https://keerthii04.github.io/Courseera/project3.html" readonly>
      </div>

      <nav id="header-nav" class="navbar navbar-expand-lg navbar-dark">
        <div class="container">
          <a class="navbar-brand" href="#">Food, LLC</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#collapsable-nav">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div id="collapsable-nav" class="collapse navbar-collapse">
            <ul id="nav-list" class="navbar-nav ms-auto">
              <li class="nav-item"><a class="nav-link" href="#chicken">Chicken</a></li>
              <li class="nav-item"><a class="nav-link" href="#beef">Beef</a></li>
              <li class="nav-item"><a class="nav-link" href="#sushi">Sushi</a></li>
            </ul>
          </div>
        </div>
      </nav>
    </div>
  </header>

  <div id="main-content" class="container">
    <h2 id="menu-title" class="text-center">Our Menu</h2>

    <section id="chicken" class="col-12">
      <div class="menu-item">
        <h3 class="text-center">Chicken</h3>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
        </p>
      </div>
    </section>

    <section id="beef" class="col-12">
      <div class="menu-item">
        <h3 class="text-center">Beef</h3>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
        </p>
      </div>
    </section>

    <section id="sushi" class="col-12">
      <div class="menu-item">
        <h3 class="text-center">Sushi</h3>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
        </p>
      </div>
    </section>
  </div>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>

</html>
