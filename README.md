<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Projeto</title>

    <style>
        *{
            margin:0;
            padding:0;
            box-sizing:border-box;
            font-family:Arial, Helvetica, sans-serif;
        }

        body{
            background:#0f172a;
            color:white;
            display:flex;
            justify-content:center;
            align-items:center;
            height:100vh;
        }

        .card{
            background:#1e293b;
            padding:40px;
            border-radius:20px;
            text-align:center;
            max-width:600px;
            box-shadow:0 0 30px rgba(0,0,0,.4);
        }

        h1{
            font-size:3rem;
            margin-bottom:20px;
        }

        p{
            color:#cbd5e1;
            margin-bottom:30px;
            line-height:1.6;
        }

        a{
            display:inline-block;
            text-decoration:none;
            background:#000;
            color:white;
            padding:15px 30px;
            border-radius:10px;
            transition:.3s;
            font-weight:bold;
        }

        a:hover{
            transform:scale(1.05);
            background:#111827;
        }
    </style>
</head>
<body>

<div class="card">
    <h1>🚀 Projeto Online</h1>

    <p>
        Bem-vindo! Este site está hospedado na Vercel.
        Personalize esta página com seu conteúdo.
    </p>

    <a href="https://github.com/seuusuario/seurepositorio" target="_blank">
        Ver no GitHub
    </a>
</div>

</body>
</html>
