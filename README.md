<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Мои треки</title>
  <style>
    .player-list {
      max-width: 600px;
      margin: 0 auto;
      padding: 20px;
    }
    
    .player-container {
      margin: 12px 0;
      max-width: 100%;
      overflow: hidden;
    }
    
    iframe {
      width: 100%;
      height: 25px;
      border: none;
      display: block;
    }
    
    @media (max-width: 768px) {
      .player-list {
        padding: 10px;
      }
      
      .player-container {
        margin: 8px 0;
        padding: 5px;
      }
      
      iframe {
        height: 40px;
        min-height: 40px;
      }
    }
    
    @media (max-width: 480px) {
      .player-list {
        padding: 5px;
      }
      
      .player-container {
        padding: 3px;
      }
      
      iframe {
        height: 35px;
      }
    }
  </style>
</head>
<body>
  <div class="player-list">
    <div class="player-container">
      <iframe
        src="https://promodj.com/embed/7902053/small"
        frameborder="0"
        allowfullscreen
        title="Трек 1: Electro Mix"
      ></iframe>
    </div>
    
    <div class="player-container">
<iframe src="//promodj.com/embed/7906776/cover" width="100%" height="300" style="min-width: 450px; max-width: 900px" frameborder="0" allowfullscreen></iframe>
    </div>
  </div>
</body>
</html>
