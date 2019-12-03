<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">

    <title>modal using bootstrap</title>
  </head>
  <body>
    <div class="container">
      <h3>Modal Window</h3>
      <!-- NOTE: button to open modal window -->
     <button type="button" name="btn btn-primary" data-toggle="modal" data-target="#myModal">Info on New York</button>
<!-- NOTE: the modal -->
<div class="modal" id="myModal">
  <div class="modal-dialog">
    <div class="modal-content">
      <!-- NOTE: modal header -->
      <div class="modal-header bg-warning">
        <h4>This is the title of the modal window</h4>
        <button type="button" class="close" data-dismiss="modal">&times;</button>
      </div>
      <!-- NOTE: modal body -->
      <div class="modal-body">
        <h5>New York City <small>The Big Apple</small></h5>
        <img src="images/nyc.jpg" alt="nyc" title="New York City" style="width:100%">
        <p>This paragraph describes New York</p>
      </div>
      <div class="modal-footer">
          <button type="button" name="btn btn-danger" data-dismiss="modal">Close</button>

      </div>
    </div>
   </div>
  </div><!-- NOTE: end of modal -->
    </div><!-- NOTE: end of container -->


    <!-- Optional JavaScript -->
