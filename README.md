# tool
some useful tool
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="keywords" content="keyword1,keyword2,keyword3">
    <meta http-equiv="description" content="this is my page">
    <meta http-equiv="content-type" content="text/html; charset=UTF-8">

    <link rel="stylesheet" type="text/css" href="register.css">
    <style>
        @keyframes bounce {
            60%, 80%, to {
                transform: translateY(400px);
                animation-timing-function: ease;
            }
            70% { transform: translateY(300px); }
            90% { transform: translateY(360px); }
        }

        .ball {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            margin: auto;
            background: rgba(0,100,100,0.5);
            animation: bounce 2s cubic-bezier(.58,.13,.94,.64) forwards;
        }
    </style>
</head>

<body>
<div class="ball"></div>
</body>
</html>
