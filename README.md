# Holguin.io
<!DOCTYPE html>
<html>

<head>
    <style>
        li ul {
            display: none;
        }

        li {
            padding: 5px 10px;
            width: 120px;
            height: 30px;
            border: 1px solid #000000;
            color: #fff;
            background-color: #000;
        }

        li:hover {
            background-color: rgb(255, 255, 255);
            color: #000;
            list-style: none;
        }

        li:hover>ul {
            display: block;
            position: relative;
            top: -24px; 
            left: 90px;
            list-style: none;
        }
    </style>

</head>

<body>
    <ul>
        <li>Home</li>
        <li>Services
            <ul>
                <li>Home</li>
                <li>Home</li>
            </ul>
        </li>
        <li>Publications
            <ul>
                <li>Home</li>
                <li>Home</li>
            </ul>
        </li>
        <li>Events
            <ul>
                <li>Home</li>
                <li>Home</li>
            </ul>
        </li>
        <li>Contact
            <ul>
                <li>Home</li>
                <li>Home</li>
            </ul>
        </li>

    </ul>

</body>

</html>
