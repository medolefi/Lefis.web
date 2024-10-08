<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lefis - Welcome</title>
    <style>
        /* General Styles */
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f2f5;
}

.header {
    background-color: #8d0076;
    color: white;
    padding: 20px;
    text-align: center;
    font-size: 40px;
    font-weight: bold;
}

.navbar {
    background-color: #8d0076;
    color: white;
    padding: 10px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.navbar-menu a {
    color: white;
    margin: 0 10px;
    text-decoration: none;
}

.navbar-menu a:hover {
    text-decoration: underline;
}

.login-container, .content {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    height: 80vh;
}

.login-box, .post-box {
    width: 400px;
    background-color: white;
    padding: 20px;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
    border-radius: 8px;
}

.input-group input, textarea {
    width: 100%;
    padding: 10px;
    border: 1px solid #dddfe2;
    border-radius: 6px;
    font-size: 16px;
}

.button {
    width: 100%;
    padding: 12px;
    background-color: #4267B2;
    border: none;
    border-radius: 6px;
    color: white;
    font-size: 18px;
    cursor: pointer;
}

.button:hover {
    background-color: #365899;
}

.feed {
    width: 600px;
    margin-top: 20px;
}

.post {
    background-color: white;
    padding: 15px;
    border-radius: 8px;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
    margin-bottom: 20px;
}

.post-header {
    display: flex;
    align-items: center;
}

.avatar {
    width: 50px;
    height: 50px;
    border-radius: 50%;
    margin-right: 15px;
}

.post-user {
    font-weight: bold;
}

.post-content {
    margin-top: 10px;
}

/* Post Button */
.post-button {
    width: 200px;
    padding: 12px;
    background-color: #4267B2;
    border: none;
    border-radius: 6px;
    color: white;
    font-size: 18px;
    cursor: pointer;
    margin-bottom: 20px;
    position: sticky; /* Keep the button in a fixed position relative to the scroll */
    top: 0; /* Stick to the top of the container */
    z-index: 1; /* Ensure it stays above other content */
}

.post-button:hover {
    background-color: #365899;
}

/* Modal Styles */
.modal {
    display: none; 
    position: fixed;
    z-index: 1;
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    overflow: auto;
    background-color: rgba(0,0,0,0.4); /* Black w/ opacity */
}

.modal-content {
    background-color: #fefefe;
    margin: 15% auto; 
    padding: 20px;
    border: 1px solid #888;
    width: 400px;
    border-radius: 8px;
}

.close-button {
    color: #aaa;
    float: right;
    font-size: 28px;
    font-weight: bold;
}

.close-button:hover,
.close-button:focus {
    color: black;
    text-decoration: none;
    cursor: pointer;
}

/* Additional styles for textarea inside the modal */
.modal textarea {
    width: 100%;
    height: 100px;
    padding: 10px;
    border: 1px solid #dddfe2;
    border-radius: 6px;
    font-size: 16px;
    margin-bottom: 10px;
}
</head>
<body>
    <div class="header">Welcome to Lefis</div>
    <div class="login-container">
        <div class="login-box">
            <h2>Lefis مرحبا بيك في</h2>
            <a href="login.html" class="button">تسجيل دخول</a>
            <a href="create-account.html" class="sign-up">انشاء حساب جديد</a>
        </div>
    </div>
</body>
</html>
