<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <title>لعبة جول ⚽</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background: linear-gradient(#4facfe, #00f2fe);
      overflow: hidden;
      font-family: Arial, sans-serif;
    }
    canvas {
      background: green;
      border: 5px solid white;
      border-radius: 10px;
      display: none;
    }
    #hud {
      position: absolute;
      top: 10px;
      left: 50%;
      transform: translateX(-50%);
      display: flex;
      gap: 30px;
      font-size: 22px;
      font-weight: bold;
      color: white;
      text-shadow: 2px 2px 5px black;
      display: none;
    }
    #menu, #gameOverScreen {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0,0,0,0.8);
      color: white;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      font-size: 24px;
      gap: 20px;
    }
    button {
      padding: 10px 20px;
      font-size: 20px;
      border: none;
      border-radius: 10px;
      cursor: pointer;
    }
    button:hover {
      background: #ddd;
    }
  </style>
  
