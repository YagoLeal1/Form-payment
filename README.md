<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="'IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>

    <form action="index.php" method="POST" enctype="multipart/form-data">

        <label for="username">username:</label>
        <input type="text" id="username" placeholder="Leal1" minlength="6" maxlength="15"> 

        <label for="password">password</label>
        <input type="password" id="password" minlength="6" maxlength="15"><br>
        
        
        <label for="email">email</label>
        <input type="email" id="email" placeholder="yagoleal@gmail.com"><br>

        <label for="phone">phone</label>
        <input type="tel" id="phone" placeholder="123-456-7890" pattern="[0-9]{3}-[0-9]{3}-[0-9]{4}"><br>
        
        <label for="bday">birthday</label>
        <input type="date" id="bday"><br>

        <label for="quamtity">quantity</label>
        <input type="number" id="quantity" min="0" max="99" value="1"><br>

        <label for="title">Title</label>

        <label for="Mr">Mr</label>
        <input type="radio" id="Mr." value="Mr." name="title">
        <label for="Ms">Ms</label>
        <input type="radio" id="Ms." value="Ms." name="title">
        <label for="PhD">PhD</label>
        <input type="radio" id="PhD." value="PhD." name="title"><br>

        <label for="payment">payment</label>
        <select id="payment">
            <option value="Visa">Visa</option>
            <option value="Mastercar">Martercard</option>
            <option value="Giftcard">Giftcard</option>
            ></option>
        </select><br>

        <label for="subscribe">subscribe</label>
        <input type="checkbox" id="subscribe"><br>

        <label for="comment">comment</label>
        <textarea id="comment" rows="3" cols="25"></textarea>

        <label for="file">file</label>
        <input type="file" id="file" accept="image/png, image/Jpeg"><br>

        

        <input type="reset">
        <input type="submit">

    </form>
    
</body>
</html>
