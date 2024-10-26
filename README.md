# prueba-random
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Inicio de Sesión</title>
    <style>
        /* Estilos generales de la página */
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background: linear-gradient(135deg, #ff4e4e, #ffffff);
            font-family: Arial, sans-serif;
        }

        /* Contenedor de la tarjeta de inicio de sesión */
        .login-container {
            background-color: #ffffff;
            padding: 40px;
            border-radius: 15px;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2);
            width: 100%;
            max-width: 400px;
            text-align: center;
        }

        /* Título de inicio de sesión */
        h2 {
            color: #ff4e4e;
            margin-bottom: 20px;
        }

        /* Estilo de los cuadros de texto */
        .input-field {
            width: 100%;
            padding: 12px;
            margin: 10px 0;
            border-radius: 25px;
            border: 1px solid #ff4e4e;
            outline: none;
            font-size: 16px;
            transition: 0.3s ease;
        }

        /* Cambios al hacer foco en los campos de entrada */
        .input-field:focus {
            border-color: #ff4e4e;
            box-shadow: 0 0 8px rgba(255, 78, 78, 0.3);
        }

        /* Botón de inicio de sesión */
        .login-button {
            width: 100%;
            padding: 12px;
            margin-top: 20px;
            border-radius: 25px;
            border: none;
            background-color: #ff4e4e;
            color: #ffffff;
            font-size: 16px;
            font-weight: bold;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        /* Efecto de hover para el botón */
        .login-button:hover {
            background-color: #e64444;
        }
    </style>
</head>
<body>
    <div class="login-container">
        <h2>Inicio de Sesión</h2>
        <form>
            <input type="text" class="input-field" placeholder="Nombre de usuario" required>
            <input type="password" class="input-field" placeholder="Contraseña" required>
            <button type="submit" class="login-button">Ingresar</button>
        </form>
    </div>
</body>
</html>
