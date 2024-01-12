<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Search Bar</title>

    <!-- bootstrap fontawesome link here for Icon  -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css">

    <!-- for styling -->
    <style>
        body{
            background: #f2f2f2;
            font-family: 'Open Sans',sans-serif;
        }
        .search{
            width: 100%;
            position: relative;
            display: flex;
        }
        .searchTerm{
            width: 100%;
            border: 3px solid #00B4CC;
            border-right: none;
            padding: 5px;
            height: 20px;
            border-radius: 5px 0 0 5px;
            outline: none;
            color: #9DBFAF;
        }
        .searchTerm:focus{
            color: #00B4CC;
        }
        .searchButton{
            width: 40px;
            width: 36px;
            border: 1px solid #00B4CC;
            background-color: #00B4CC;
            text-align: center;
            color: #fff;
            border-radius: 0 5px 5px 0;
            cursor: pointer;
            font-size: 20px;
        }
        .wrap{
            width: 30%;
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%,-50%);
        }
    </style>

</head>
<body>
 <div class="wrap">
    <div class="search">
        <input type="text" class="searchTerm"
        placeholder="What are you looking for ?"

        >
        <button type="submit" 
        class="searchButton"
        ><i class="fa fa-search"></i></button>
    </div>
 </div>
</body>
</html>

