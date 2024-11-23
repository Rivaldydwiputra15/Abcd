/* File: style.css */

/* Style umum */
body {
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background: linear-gradient(to bottom, #000, #FFD700); /* Warna hitam ke emas */
    font-family: 'Arial', sans-serif;
}

.container {
    text-align: center;
}

/* Animasi logo bergerak */
.logo {
    width: 200px;
    height: auto;
    animation: bounce 3s infinite;
}

/* Animasi teks bergerak */
.animated-text {
    font-size: 36px;
    color: #FFD700;
    text-shadow: 2px 2px 5px #000;
    margin-top: 20px;
    animation: fade-in 5s infinite alternate ease-in-out;
}

/* Keyframes animasi logo */
@keyframes bounce {
    0%, 20%, 50%, 80%, 100% {
        transform: translateY(0);
    }
    40% {
        transform: translateY(-20px);
    }
    60% {
        transform: translateY(-10px);
    }
}

/* Keyframes animasi teks */
@keyframes fade-in {
    0% {
        opacity: 0;
        transform: translateX(-100%);
    }
    100% {
        opacity: 1;
        transform: translateX(0);
    }
}
￼Enter
