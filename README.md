<!DOCTYPE html>
<html>
    <head>
        <title>register form</title>
        <!--css-part-->
        <style>
            body{
                background: #A300FF;
                color: white;
            }
            .class{
                text-align: center;
            }
            .form{
                background: 50%black;
                color: white;
                width: 100%;
            }
            hr{
                color: black;
            }
            .form1{
                background: green;
                width: 100%;
            }
            .form2{
                background: blue;;
            }
        </style>
    </head>
    <body>
        
        <header>
            <!--forms-->
            <form>
            <h1 class="class">student register form</h1><hr>
            <label>First name</label><br>
            <input type="text" height="100%" class="form" placeholder="First name"><br><br>
            <label>Middle name</label><br>
            <input type="text" class="form"  placeholder="Middle name"><br><br>
            <label>Last name</label><br>
            <input type="text" class="form"   placeholder="Last name"><br><br>
            <label>course:</label>
            <select class="form">
                <option>B.C.A</option>
                <option>B.B.A</option>
                <option>M-tech</option>
                <option>B-tech</option>
                <option>B.com</option>
                <option>M.B.A</option>
                <option>M.C.A</option>
                </select><br><br>
                <label>Gender:</label><br>
                <label> male</label>
                <input type="radio" name="Gender">
                <label>female</label>
                <input type="radio" name="Gender">
                <label>others</label><br><br>
                    <label>phone</label><br>
            <input type="tel" class="form" ><br><br>
            <input type="tel" class="form"><br><br>
               <label>current address</label><br>
               <textarea value="current address" placeholder="current address" class="form">
                </textarea><br><br>
                <label>email</label><br>
                <input type="email" class="form"><br><br>
                <label>password</label><br>
                <input type="password" class="form" placeholder="password"><br><br>
                <label>re-type password</label><br>
                <input type="password" class="form" placeholder="re-type password"><br><br><br>
                <button type="button" class="form1">register</button>
            </form>
           
        </header>
        <hr>
        <marquee class="form2">kiran</marquee>
        <hr>
    </body>
</html>
