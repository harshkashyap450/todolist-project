<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=, initial-scale=1.0">
    <link rel="stylesheet" href="./todo.css">
    <link rel="icon" href="./check_list-512.webp">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <title>todo list</title>
</head>
<body>
    
    <div class="upper-container">

        <div class="upper-container1">
         <span id="tasks"> Tasks </span>
         <span id="lists"> Lists </span>
        </div>
        <div class="upper-container2">
            <div id="circle">
                <a href="./todo2.html" class="fa fa-plus-circle" style="font-size:40px;color:orange"></a>
            </div>

            <div id="addlist">
                
               <a class="add_list" href="./todo2.html">Add List</a> 
            </div>    
        </div>
    </div>
    <div class="lower-container">

        <div class="card1">

            <a  href="./todo1.html" id="heading1"> <p class="heading1">Trip to Paris</p></a><hr class="line"><br><br>
            <p class="para1">Completed Task</p><br><br>
            <form action="">
                <input type="checkbox" name="todo" id="check1">
                <label for="todo" class="label1">Pending Task</label>
            </form>
        </div>

            <div class="card2">

                <p class="heading2">My Todo List</p><hr class="line"><br><br>
                <p class="para1">Completed Task</p><br><br>
                <form action="">
                    <input type="checkbox" name="todo" id="check1">
                    <label for="todo" class="label1">Pending Task</label>
                </form>
            </div>
                <div class="card3">

                    <p class="heading2">My Todo List</p><hr class="line"><br><br>
                    <p class="para1">Completed Task</p><br><br>
                    <form action="">
                        <input type="checkbox" name="todo" id="check1">
                        <label for="todo" class="label1">Pending Task</label>
                    </form>
        

                  </div>

    </div>
   
</body>
</html>
