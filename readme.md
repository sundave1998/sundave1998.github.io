
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Personal webpage">
    <meta name="author" content="Youbang Sun">

    <title>Starter Template for Bootstrap</title>

    <!-- Bootstrap core CSS -->
    <link href="css/bootstrap.css" rel="stylesheet">

    <!-- Add custom CSS here -->
    <link href="css/simple-sidebar.css" rel="stylesheet">
    <link href="font-awesome/css/font-awesome.min.css" rel="stylesheet">

</head>

<body>

    <div id="wrapper">

        <!-- Sidebar -->
        <!-- <div id="sidebar-wrapper">
        <ul class="sidebar-nav">
          <li class="sidebar-brand"><a href="index.html">Home</a></li>
          <li><a href="./publications.html">Publications</a></li>
          <li><a href="#">Research</a></li>
          <li><a href="#">Overview</a></li>
          <li><a href="#">Events</a></li>
          <li><a href="#">About</a></li>
          <li><a href="#">Services</a></li>
          <li><a href="./CV_Youbang_Sun.pdf">CV</a></li>
        </ul>
      </div> -->

        <!-- Page content -->
        <div id="page-content-wrapper">
            <div class="content-header">
                <h1 style="color:rgb(40, 75, 190);">
                    <!-- <a id="menu-toggle" href="#" class="btn btn-default"><i class="icon-reorder"></i></a> -->
                    Youbang Sun
                </h1>
            </div>
            <!-- Keep all page content within the page-content inset div! -->
            <div class="page-content inset">
                <div class="row">
                    <div class="col-md-12">

                    </div>
                    <!-- <div class="col-md-6">
              <p class="well">The template still uses the default Bootstrap rows and columns.</p>
            </div>
            <div class="col-md-6">
              <p class="well">But the full-width layout means that you wont be using containers.</p>
            </div> -->
                    <div class="col-md-4">
                        <img src="#">
                    </div>
                    <div class="col-md-8">
                        <p class="lead">
                            <p class="lead">Youbang Sun
                                <br> Ph.D. Student in Department of Mechanical and Industrial Engineering of Northeastern University
                                <br> Email: sun.youb[at]northeastern(dot)edu
                                <br> Office: Dana Research Center, Boston, MA, 02115
                                <br>
                                <a href="https://scholar.google.com/citations?user=TUR1VtcAAAAJ">Google Scholar</a>/<a href="www.linkedin.com/in/sun-yb">Linkedin</a>
                                <br>
                                <a href="./CV_Youbang_Sun.pdf">CV</a>
                            </p>

                        </p>
                    </div>
                    <div class="col-md-11">
                        <hr color="#000000" size="5px">
                        <h3 style="color:rgb(40, 75, 190);">Short Bio</h3>
                        <h4>
                            Youbang Sun is currently a Third-year Ph.D. student in the Department of Mechanical & Industrial Engineering at Northeastern University (2021-now). He was previously a Ph.D. student in the Department of Industrial Engineering at Texas A&M University (2019-2021).
                            Prior to that, he obtained his B.S. degree in Electrial Engineering from University of Science and Technology of China (2015-2019).
                        </h4>
                    </div>
                    <div class="col-md-11">
                        <hr color="#000000" size="5px">
                        <h3 style="color:rgb(40, 75, 190);">Research Focus</h3>
                        <h4>
                            Machine Learning, Distributed Optimization, Federated Learning
                        </h4>
                    </div>
                    <!-- <div class="col-md-12">
              <p class="well">You get the idea! Do whatever you want in the page content area!</p>
            </div> -->
                </div>
            </div>
        </div>

    </div>

    <!-- JavaScript -->
    <script src="js/jquery-1.10.2.js"></script>
    <script src="js/bootstrap.js"></script>

    <!-- Custom JavaScript for the Menu Toggle -->
    <script>
        $("#menu-toggle").click(function(e) {
            e.preventDefault();
            $("#wrapper").toggleClass("active");
        });
    </script>
</body>

</html>
