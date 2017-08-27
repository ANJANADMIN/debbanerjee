# My Bootstrap Templates  
This is a templates archive file. I shall store here all the types of Bootstrap templates that I create. I shall also update these templates as I learn new skills like jQuery/Javascript to add more functionality.
## Here's The Boilerplate Code For Bootstrap V3
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap Boilerplate code</title>	
    <!-- Latest compiled and minified CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">
    <!-- Optional theme -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap-theme.min.css" integrity="sha384-rHyoN1iRsVXV4nD0JutlnGaslCJuC7uwjduW9SVrLvRYooPp2bWYgmgJQIXwl/Sp" crossorigin="anonymous">
  </head>
  <body>
    <!--


    Write My Code Here




    -->
    <!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
    <!-- Latest compiled and minified JavaScript -->
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script>
  </body>
</html>
```
## Code template for Sidebar-Content pages
```
<!DOCTYPE html>
<html lang="en">

<head>

    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <meta name="description" content="">
    <meta name="author" content="">

    <title>Simple Sidebar - Start Bootstrap Template</title>

    <!-- Latest compiled and minified CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">
    <!-- Optional theme -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap-theme.min.css" integrity="sha384-rHyoN1iRsVXV4nD0JutlnGaslCJuC7uwjduW9SVrLvRYooPp2bWYgmgJQIXwl/Sp" crossorigin="anonymous">
     <!--Custom styles-->
    <link rel="stylesheet" href="custom.css">

</head>

<body>

    <div id="wrapper">

        <!-- Sidebar -->
        <div id="sidebar-wrapper">
            <ul class="sidebar-nav">
                <li class="sidebar-brand">
                    <a href="#">
                        Start Bootstrap
                    </a>
                </li>
                <li>
                    <a href="#">Dashboard</a>
                </li>
                <li>
                    <a href="#">Shortcuts</a>
                </li>
                <li>
                    <a href="#">Overview</a>
                </li>
                <li>
                    <a href="#">Events</a>
                </li>
                <li>
                    <a href="#">About</a>
                </li>
                <li>
                    <a href="#">Services</a>
                </li>
                <li>
                    <a href="#">Contact</a>
                </li>
            </ul>
        </div>
        <!-- /#sidebar-wrapper -->

        <!-- Page Content -->
        <div id="page-content-wrapper">
            <div class="container-fluid">
                <a href="#menu-toggle" class="btn btn-primary" id="menu-toggle">Toggle Menu</a>
                <h1>Simple Sidebar</h1>
                <p>This template has a responsive menu toggling system. The menu will appear collapsed on smaller screens, and will appear non-collapsed on larger screens. When toggled using the button below, the menu will appear/disappear. On small screens, the page content will be pushed off canvas.</p>
                <p>Make sure to keep all page content within the <code>#page-content-wrapper</code>.</p>
            </div>
        </div>
        <!-- /#page-content-wrapper -->

    </div>
    <!-- /#wrapper -->

    <!-- Bootstrap core JavaScript -->
    <!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
    <!-- Latest compiled and minified JavaScript -->
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script>

    <!-- Menu Toggle Script -->
    <script>
    $("#menu-toggle").click(function(e) {
        e.preventDefault();
        $("#wrapper").toggleClass("toggled");
    });
    </script>

</body>

</html>

```
## Code template for Portfolio style homepage
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Deb Banerjee</title> 
    <!-- Latest compiled and minified CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">
    <!-- Optional theme -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap-theme.min.css" integrity="sha384-rHyoN1iRsVXV4nD0JutlnGaslCJuC7uwjduW9SVrLvRYooPp2bWYgmgJQIXwl/Sp" crossorigin="anonymous">
    <!--Custom styles-->
    <link rel="stylesheet" href="custom.css">
  </head>
  <body>
<!--The Hero section with the Jumbotron -->
    <div class="jumbotron" style="border: 1px solid red;">
      <nav class="" style="border: 1px solid #000; margin: -40px 10px 40px 10px">
          <ul class="list-unstyled list-inline">
            <li><img src="//via.placeholder.com/350x100" alt="Marbias Money Projects Logo" class="img-responsive"></li>
            <li class="pull-right"><a href="About.html" class=""><p>About</p></a></li>
          </ul>
      </nav>
<!--A center aligned box with an Avatar and 4 social icons in the next line -->
      <div class="col-md-4 social-block" style="border: 1px solid red; float: none; margin: 0 auto 50px;">
        <img src="//via.placeholder.com/150x150" alt="" class="img-circle img-responsive" style="margin: 0 auto;">
        <p class="text-center">A day without learning something new is a day wasted</p>
      </div>
    </div>
        <!--This is the content section -->
    <div class="row content" style="border: 1px solid red;">
      <div class="col-xs-12">
        <h2 class="text-center">My Projects</h2>
        <p class="text-center">Here's a list of all the learning projects that I've taken over the years. I've also tried to record my successes and failures in each of these projects</p>
      </div>
    </div>
<!--This is the start of the project grid-->
    <div class="row" style="border: 1px solid green;">
      <div class="row project-grid" style="border: 1px solid red; text-align: center;">
        <div class="col-md-4">
          <img src="//via.placeholder.com/300x200" class="img-responsive img-thumbnail" alt="Project1" style="margin: 0 auto;">
          <p class="text-center">This is my project 1</p>
        </div>
        <div class="col-md-4">
          <img src="//via.placeholder.com/300x200" class="img-responsive img-thumbnail" alt="Project2">
          <p class="text-center">This is my project 1</p>
        </div>
        <div class="col-md-4">
          <img src="//via.placeholder.com/300x200" class="img-responsive img-thumbnail" alt="Project3">
          <p class="text-center">This is my project 1</p>
        </div>
      </div>
      <div class="row project-grid" style="border: 1px solid red; text-align: center;">
        <div class="col-md-4">
          <img src="//via.placeholder.com/300x200" class="img-responsive img-thumbnail" alt="Project1" style="margin: 0 auto;">
          <p class="text-center">This is my project 1</p>
        </div>
        <div class="col-md-4">
          <img src="//via.placeholder.com/300x200" class="img-responsive img-thumbnail" alt="Project2">
          <p class="text-center">This is my project 1</p>
        </div>
        <div class="col-md-4">
          <img src="//via.placeholder.com/300x200" class="img-responsive img-thumbnail" alt="Project3">
          <p class="text-center">This is my project 1</p>
        </div>
      </div>
      <div class="row project-grid" style="border: 1px solid red; text-align: center;">
        <div class="col-md-4">
          <img src="//via.placeholder.com/300x200" class="img-responsive img-thumbnail" alt="Project1" style="margin: 0 auto;">
          <p class="text-center">This is my project 1</p>
        </div>
        <div class="col-md-4">
          <img src="//via.placeholder.com/300x200" class="img-responsive img-thumbnail" alt="Project2">
          <p class="text-center">This is my project 1</p>
        </div>
        <div class="col-md-4">
          <img src="//via.placeholder.com/300x200" class="img-responsive img-thumbnail" alt="Project3">
          <p class="text-center">This is my project 1</p>
        </div>
      </div>
    </div>

    <footer style="border: 1px solid blue;">
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Laudantium dignissimos dolor quisquam magnam earum! Ad sint odit, non, tempore molestiae sequi, itaque asperiores veniam sunt esse eos, repellat nemo ullam!
    </footer>    
    <!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
    <!-- Latest compiled and minified JavaScript -->
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script>
  </body>
</html>

```
## Code template for Blog pages
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Deb Banerjee</title> 
    <!-- Latest compiled and minified CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">
    <!-- Optional theme -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap-theme.min.css" integrity="sha384-rHyoN1iRsVXV4nD0JutlnGaslCJuC7uwjduW9SVrLvRYooPp2bWYgmgJQIXwl/Sp" crossorigin="anonymous">
    <!--Custom styles-->
    <link rel="stylesheet" href="custom.css">
  </head>
  <body>
    <div class="container">
      <div class="wrap" style="margin: 0 auto; width: 90%;">
        <h1 class="db-header">The article header</h1>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
        quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
        consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
        cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
        proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
        
      </div>
    </div>

   <!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
    <!-- Latest compiled and minified JavaScript -->
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script>
  </body>
</html>
```