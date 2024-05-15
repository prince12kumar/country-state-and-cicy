//code in index.html


html>
<html lang="en">

<head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css" integrity="sha384-xOolHFLEh07PJGoPkLv1IbcEPTNtaed2xpHsD9ESMhqIYd0nLMwNLD69Npy4HI+N" crossorigin="anonymous">
    <link rel="stylesheet" href="style.css">

    <title>Dropdown</title>
</head>

<body>
    <div class="container">
        <h3>Select Country State and City</h3>
        <form>
            <div class="form-group">
                <div class="select_option">

                    <select class="form-control country" id="exampleFormControlSelect1" onchange="loadState()">
                     <option>Select Country</option>
      </select>
                    <div class="form-group">
                        <select class="form-control state" id="exampleFormControlSelect1" onchange="loadCities()">
                        <option>Select State</option>
        </select>
                        <div class="form-group">
                            <select class="form-control city" id="exampleFormControlSelect1">
                              <option>Select City</option>
            </select>
                        </div>

                    </div>

        </form>
        </div>


        <script src="app.js "></script>

        <script src="https://cdn.jsdelivr.net/npm/jquery@3.5.1/dist/jquery.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-Fy6S3B9q64WdZWQUiU+q4/2Lc9npb8tCaSX9FK7E8HnRr0Jz8D6OP9dO5Vg3Q9ct" crossorigin="anonymous"></script>


</body>

</html>
