
# Simple web application using Node js & MongoDb

<h3>installation steps: </h3>

1 -> install library node js by typing [ npm install ]

2 -> create database with mongodb by typing [ use restaurant ]

3 -> Fake Data to using application by typing [ node ./seeder/seeder.js ]

<strong>Password : ddd</strong>

<h3>Mvc concept : </h3>

![stack Overflow](https://2.bp.blogspot.com/-I6bIQMAj-Nc/WWaQAbXnfJI/AAAAAAAABZg/aVDBAFcksSogYYNgWqd1GIkOZgtQuCQ7ACLcBGAs/s320/icon-aspnetmvc.png)

<h3>Database scheme :</h3>

<pre> 
// Users scheme
User {
        _id : ("5e946cbe64937321dc961e5e"),
        role : "adminstrator",
        Fname : "Shraddha",
        LName : "Gupta",
        Contact : "1234567890",
        email : "shraddhag1807@gmail.com",
        password : "xyz@123",
        avatar : "profile.png",
        created_at : ("2023-06-20T17:40:57.452Z")
}

// Drink scheme
Drink {
            _id : ("5e87404989624917fc83db12"),
            Name : "namemore",
            Alcohol : "alcoholwoman",
            Type : "newwoman",
             Description : "Lorem Ipsum is simply dummy text of the printing and typesetting industry.",
            created_at : ("2023-06-20T17:40:57.452Z")
}

// Food scheme
Food {
        _id : ("5e81ba1051d4f6298052d9d1"),
        Name : "hmiss",
        Price : "201.21",
        Type : "khfif",
        Category : "taklidi",
         Description : "Lorem Ipsum is simply dummy text of the printing and typesetting industry.",
        created_at : ("2023-06-20T17:40:57.452Z")
}

// Table scheme
Table {
    _id : ("5e832c1593129439b8f3bdcb"),
    Name : "Classic tow",
    NumberPlace : "6",
    Type : "family",
     Description : "Lorem Ipsum is simply dummy text of the printing and typesetting industry.",
    created_at : ("2023-06-20T17:40:57.452Z")
}

// Chef scheme
Chef {
        _id : ("5e833906da8f86227cb61966"),
        Fname : "Karimo",
        LName : "Smith",
        Email : "karimo@chef.jz",
        Experience : "10 years of job",
        Type : "all types",
        City : "Illizi",
        Postcode : "35000",
        Salary : "1000",
        Sex : "man",
        Birthdate : "1990-04-17",
        created_at : ("2023-06-20T17:40:57.452Z")
}

// Waiter scheme
Waiter {
            _id : ("5e81ae8260cd552b58714cfc"),
            Fname : "Mohammed",
            LName : "Abrahim",
            Email : "mohammed@waiter.jz",
            City : "Naama",
            Postcode : "35000",
            Salary : "200",
            Sex : "man",
            Birthdate : "1995-10-25",
            created_at : ("2023-06-20T17:40:57.452Z")
}

// Booking scheme
Customer {
        _id : ("5e822f29b0f7790a685ac372"),
        Fname : "Tessa",
        LName : "young",
        Contact : "0987654321",
        Email : "younes@mail.jz",
        created_at : ("2023-06-20T17:40:57.452Z")
}

// Booking scheme
booking {
        _id : ("5e8626c48b66dd116813b732"),
        Date : "2023-06-20",
        time : "8:00pm",
        number_place : "3",
        CustomerID : "5e9864b2b8ffe7594876d724",
        created_at : ("2023-06-20T17:40:57.452Z")
}

// Bills scheme
Bill {
        _id : ("5e95f5bbd0315c3d6c25f179"),
        Sub_Total : "700.12",
        Vat : "150.26",
        Total : "850.38",
        drink_id : "5e985e544815552404e93b47",
        food_id : "5e974face028ec5590e73eb6",
        waiter_id : "5e98627d961ec759b0217a69",
        table_id : "5e9719fff6ca344ac449dd20",
        CustomerID : "5e822fd59d92e605285b5396",
        created_at : ("2023-06-20T17:40:57.452Z")
}
</pre> 
