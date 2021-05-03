# Expense-Tracker-
The Expense Tracker in javascript keeps a track record of expenditures. This is a simple lightweight program for personal expense manager in the web version. To run this project, first, you need to have a browser and a code editor of any kind. Then you have to run the index file from the editor or directly from the folder. When the screen loads, you can see the homepage. From there you can manage your expense activities.

<!DOCTYPE html>
<!--[if lt IE 7]>      <html class="no-js lt-ie9 lt-ie8 lt-ie7"> <![endif]-->
<!--[if IE 7]>         <html class="no-js lt-ie9 lt-ie8"> <![endif]-->
<!--[if IE 8]>         <html class="no-js lt-ie9"> <![endif]-->
<!--[if gt IE 8]>      <html class="no-js"> <!--<![endif]-->
<html>
  <head>
    <meta charset="utf-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <title>expense traker</title>
    <meta name="description" content="" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <!--[if lt IE 7]>
      <p class="browsehappy">
        You are using an <strong>outdated</strong> browser. Please
        <a href="#">upgrade your browser</a> to improve your experience.
      </p>
    <![endif]-->

    <h2>Expense Tracker</h2>
    <div class="container">
      <h4>Your balance</h4>
      <h1 id="balance">$0.0</h1>
      <div class="inc-exp-container">
        <div>
          <h4>income</h4>
          <p id="money-plus" class="money plus">+$0.00</p>
        </div>
        <div>
          <h4>expense</h4>
          <p id="money-minus" class="money minus">-$0.00</p>
        </div>
      </div>
      <h3>History</h3>
      <ul id="list" class="list">
        <!-- <li class="minus">cash<span>-$400</span><button class="delete-btn">x</button></li> -->
      </ul>
      <h3>add new transation</h3>
      <form action="" id="form">
        <div class="form-control">
          <label for="text">text</label>
          <input type="text" id="text" placeholder="please enter the text..." />
        </div>
        <div class="form-control">
          <label for="amount"
            >amount <br />(negtive=expense,positive=income)</label
          >
          <input
            type="number"
            id="amount"
            placeholder="please enter the amount..."
          />
        </div>
        <button class="btn">Add transation</button>
      </form>
    </div>

    <script src="script.js" async defer></script>
  </body>
</html>
