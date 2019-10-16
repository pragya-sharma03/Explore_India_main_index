# Explore_India_main_index
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="../styles/css/styles.css">
    
    <title>Make Reservation</title>
</head>

<body>
<header style="margin: 75px;">
    <nav class="navbar navbar-default navbar-fixed-top">
        <div class="container">
            <div class="navbar-header">
                <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar"
                        aria-expanded="false" aria-controls="navbar">
                    <span class="sr-only">Toggle navigation</span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                </button>
                
            </div>
            <div id="navbar" class="navbar-collapse collapse" aria-expanded="false" style="height: 1px;">
                <ul class="nav navbar-nav">
                    <li>
                        <a href="home.html"><span class="glyphicon glyphicon-home"></span> Home</a>
                    </li>
                    <li class="active">
                        <a href="makereservation.html"><i class="fa fa-book"></i> Reservations</a>
                    </li>
                    <li>
                        <a href="cancelreservation.html"><i class="fa fa-book"></i> Change/Cancel Res</a>
                    </li>
                    
                    <li>
                        <a href="contactus.html"><span class="glyphicon glyphicon-phone"></span> Contact Us</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
</header>
<section>
    <div class="container">
        <div class="container">
            <div class="page-header" style="font-family: Century Gothic; font-size: 20px"><h2> MAKE A RESERVATION !!</h2></div>
            <br>

            <form role="form" action="https://docs.google.com/forms/u/1/d/e/1FAIpQLSfxzOiWmCT9zXPYlEO1CLA2iUodE7q22MZqQ8VFB_VVr-LDUQ/formResponse" target="_self" method="post">
                <div class="row">
                    <div class="col-md-4">
                        <label for="fName"> First Name : </label>
                        <input type="text" class="form-control" id="entry.277892238" placeholder="Enter your First name">
                    </div>
                    <div class="col-md-4">
                        <label for="lName"> Last Name : </label>
                        <input type="text" class="form-control" id="entry.2097473159" placeholder="Enter your Last name">
                    </div>
                    <div class="col-md-4">
                        <label for="phno"> Phone Number : </label>
                        <input type="number" class="form-control" id="entry.605745199" placeholder="Enter your Phone number">
                    </div>
                </div>
                <br>

                <div class="row">
                    <div class="col-md-6">
                        <label for="email"> Email Address : </label>
                        <input type="email" class="form-control" id="entry.959158141" placeholder="Enter your Email Address">
                    </div>
                </div>
                <br>

                <div class="row">
                    <div class="col-lg-6">
                        <label for="date"> Date : </label>
                        <input type="date" class="form-control" id="entry.218454216">
                    </div>
                    <div class="col-lg-3">
                        <label for="fTime"> From Time : </label>
                        <input type="time" class="form-control" id="entry.835802679">
                    </div>
                    <div class="col-lg-3">
                        <label for="tTime"> To Time : </label>
                        <input type="time" class="form-control" id="entry.1021566612">
                    </div>
                </div>
                <br>

                <div class="row">
                    <div class="col-lg-3">
                        <label for="noofperson" title="If more than 16 ppl, make seperate reservations"> No of people
                            for Reservation : </label>
                        <input type="number" class="form-control" id="entry.784575878" min="1" max="16"
                               placeholder="Number of person for a table">
                    </div>
                </div>
                <br>

                <div class="row">
                    <div class="col-lg-8">
                        <div class="form-group">
                            <label for="comment">List down specific requirement to be taken care of :</label>
                            <textarea class="form-control" rows="5" id="entry.478826165"></textarea>
                        </div>
                    </div>
                </div>

                <div class="row">
                    <div class="col-lg-2"><button type="submit" class="btn btn-group-lg btn-primary form-control">Make Reservation</button></div>
                    <div class="col-lg-2"><button type="reset" class="btn btn-group-lg btn-primary form-control">Clear</button></div>
                </div>
            </form>
        </div>
    </div>
</section>



</body>
</html>
