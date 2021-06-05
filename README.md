# alignment
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>alignment</title>
<style>
    .container{
        background-color: rgb(239, 165, 241);
        margin: 20px;
        border: 13px solid gray;
        padding: 20px;
        width: fit-content;
        height: 1000px;
        margin: auto; /* to make div center*/
    }
    .item{
        border: 2px solid greenyellow;
        margin: 10px;
    }
    #fruits{
        float: left;
        width: auto;
        box-sizing: 50px;
    }
    #computer{
        float: right;
        /* width:auto; */
        /* height: auto; */
        box-sizing: 50px;
    }
    #stationary{
        clear: both;
        float: left;
        box-sizing: 50px;
        width: auto;
    }
    h3,p{
        text-align: justify;
    }
    body{
        font-family: Arial, Helvetica, sans-serif;
    }
    h1{
        margin: auto;
        text-align: center;
        /* background-origin: padding-box; */
    }
</style>
</head>
<body>
    
    <div class="container">
        <h1>welcome to shop </h1>
    <div id="fruits" class="item">
        <h3>fruits</h3>
        <p id="fruitspara" class="para">
            Lorem i Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quis vero accusantium iure et temporibus, inventore veniam facilis, aliquam officia voluptate, illo distinctio nobis. Quam, inventore rerum voluptatibus in beatae architecto dolore tenetur qui quasi fugit autem similique praesentium consequuntur excepturi harum temporibus provident! Aperiam autem fugit veniam excepturi odio suscipit reprehenderit, qui molestias, perferend Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam sunt consequatur ab numquam deserunt amet optio dicta assumenda molestias veniam explicabo sed, voluptatem minima laboriosam ullam minus excepturi possimus ex totam tempora sint at nobis iste reiciendis. Odio debitis iste asperiores, tenetur fugit dolorem hic rerum  Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure, distinctio. Vitae impedit cumque velit quia accusantium enim deserunt, consequuntur laboriosam ex in, optio consectetur expedita nisi repudiandae voluptas magni quis! Harum ratione quae assumenda, ut dolore perferendis non totam velit iste. Eligendi quia, asperiores ipsum vero est nesciunt eveniet blanditiis cupiditate, veniam consequatur in! Eligendi et a dignissimos veniam quam, pariatur vel? Pariatur saepe aut veniam, iure cumque quae eum. Assumenda error iusto et saepe fuga perspiciatis a aliquam aperiam, deserunt dolorem rem laboriosam quae! Iure repellendus inventore totam vero esse eum officia suscipit soluta voluptate sit! Saepe, adipisci aperiam! quas, nam quae consequatur! is minima, tempora debitis. psum dolor Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat tenetur veritatis sed impedit nisi nihil qui? Iure dolor aut itaque?
        </p>
    </div>
    <div id="computer" class="item">
        <h3>computer</h3>
        <p id="computer" class="para">
            Lorem ipsum Lorem ipsum dolor sit amet consectetur adipisicing elit. Pariatur illo laborum numquam vero enim ullam dolore obcaecati voluptates explicabo est? dolor Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat tenetur veritatis sed impedit nisi nihil qui? Iure dolor aut itaque?
        </p>
    </div>
    <div id="stationary" class="item">
        <h3>stationary</h3>
        <p id="stationary" class="para">
            Lorem ipsum dolor Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat tenetur veritatis sed impedit nisi nihil qui? Iure  Lorem ipsum dolor sit amet consectetur adipisicing elit. Autem nulla quisquam eos, inventore exercitationem fugiat. Quibusdam, sint? Mollitia, minima praesentium!dolor aut itaque?
        </p>
    </div>
</div>
</body>
</html>
