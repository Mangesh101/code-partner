# code-partner
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>COSMO HATCH</title>
    <style>
        label {
            color: rgb(226, 199, 199);
            font-style: oblique;
            font-size: 20px;
            font-weight: bold;
        }

        div {
            color: rgb(216, 189, 210);
            font-style: initial;
            font-size: 20px;
            font-weight: bold;
        }

        h2 {
            color: rgb(156, 209, 33);
            font-style: inherit;
        }

        .navbar {
            background-color: skyblue;
            border-radius: 36px;
            color: rgb(14, 4, 4);
        }

        .navbar ul {
            overflow: auto;
        }

        .navbar li {
            float: left;
            list-style: none;
            padding: 3px;
        }

        .navbar li a {
            text-decoration: none;
            padding: 3px 3px;
            color: rgb(26, 11, 11);
            margin: 13px 8px;
        }

        .navbar input {
            border: 2px solid black;
            padding: 3px 15px;
            border-radius: 25px;
            width: 200px;
            font-size: 15px;

        }

        .navbar li a:hover {
            color: red;
        }

        body {
            background-image: url(https://fiverr-res.cloudinary.com/images/t_main1,q_auto,f_auto,q_auto,f_auto/gigs/118352646/original/8e16b122ccda348fbfe790f8f46053edcee26624/creation-background-of-website.jpg);
            background-repeat: no-repeat;
            background-size: 100%;
            background-position: center;
            padding: 25px;
            background-position-y: 15px;
            margin: auto;
        }

        h2 {
            color: rgb(82, 214, 21);
           padding: 20px;
           width: 610px;
           margin: auto;
           font-size: 40px;
        }
    </style>
</head>

<body>
    



    <H2>WELOME TO COSMO WORLD</H2>
    <header>
        <nav class=navbar>
            <ul>
                <li><a href="#"> Home</a> </li>
                <li><a href="#"> Services</a> </li>
                <li><a href="#"> About </a> </li>
                <li><a href=""> Contact us </a> </li>
                

                    <input type="text" name=search id="search" placeholder="search this website">
                </div>
            </ul>
        </nav>
    </header>
    <form action="backend.php"></form>
    <label for="name">Name :</label>
    <div>
        <input type="text" name:myname id="name">
    </div><br>
    <label for="Mobile number">Mobile Number :</label>
    <div>
        <input type="number" name:mynumber id="mynumber">

    </div><br>
    <label for="email">Email :</label>
    <div>
        <input type="Email" name:myemail id="myemail">

    </div><br>
    <div>
        gender : male <input type="radio" name="my gender"  id="" > Female <input type="radio" name="my gender" id="">
        other <input type="radio" name="my gender" id="" br </div><br>
        <div>
            <div>
                Write about your project: <br> <textarea name="text" id="" cols="50" rows="20"></textarea>
            </div><br>

            <label for="completing project"> Time in which you need to complete this project</label>
            <select name: value id=""> </select>
            <option value=" number"></option>
            <option value=" number"></option>
            <option value=" number"></option>
        </div><br>
        <div>

            <input type="submit" value="submit now">
            <input type="reset" value="reset now">
            <input type="button" value="action">
        </div>





</body>

</html>
