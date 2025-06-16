<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Tamkeen Move</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&family=Playfair+Display:wght@500&display=swap');

    body {
      font-family: 'Playfair Display', serif;
      direction: rtl;
      background-color: #f9f9f9;
      margin: 0;
      padding: 0;
      text-align: center;
      color: #222;
    }

    header {
      background-color: #fff;
      padding: 30px 10px 20px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }

    header img {
      max-width: 280px;
      display: block;
      margin: 0 auto 10px;
    }

    header h1 {
      font-size: 36px;
      margin: 0;
      color: #333;
    }

    .info {
      padding: 20px 10px;
      font-size: 18px;
    }

    .map {
      margin: 20px auto;
      max-width: 95%;
    }

    .gallery {
      padding: 20px;
      background: #fff;
    }

    .gallery h2 {
      margin-bottom: 20px;
      font-size: 26px;
      color: #444;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .gallery img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      transition: transform 0.3s ease;
    }

    .gallery img:hover {
      transform: scale(1.05);
    }

    footer {
      background-color: #eee;
      padding: 15px;
      font-size: 14px;
      color: #444;
    }
  </style>
</head>
<body>

  <header>
    <img src="https://oaidalleapiprodscus.blob.core.windows.net/private/org-3ZrNjtrCdiU8eTCiWH62eWqm/user-WZPm3RMyCzZK6f4k3XN8hEaw/img-5w1U0E0RuOcqKktW9pn3PG81.png" alt="Tamkeen Move Logo" />
    <h1>Tamkeen Move</h1>
  </header>

  <div class="info">
    <p>📍 مكة المكرمة - حي العزيزية - حي الوادي</p>
    <p>📞 01062830368</p>
    <p>📧 nasrmohamed111659@gmail.com</p>
    <p>⏰ نعمل على مدار 24 ساعة</p>
  </div>

  <div class="map">
    <iframe src="https://www.google.com/maps?q=21.385,39.858&z=15&output=embed" width="100%" height="300" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
  </div>

  <div class="gallery">
    <h2>📸 معرض الصور</h2>
    <div class="grid">
      <img src="https://images.unsplash.com/photo-1600566753231-c6b7c5f6744c?auto=format&fit=crop&w=600&q=80" alt="نقل أثاث" />
      <img src="https://images.unsplash.com/photo-1580591157311-3e74c3f53c4d?auto=format&fit=crop&w=600&q=80" alt="كراتين" />
      <img src="https://images.unsplash.com/photo-1603787081261-5457be8251b3?auto=format&fit=crop&w=600&q=80" alt="عربية نقل" />
      <img src="https://images.unsplash.com/photo-1618221402950-b6c7c68e1cde?auto=format&fit=crop&w=600&q=80" alt="نقل عفش منظم" />
    </div>
  </div>

  <footer>
    © 2025 Tamkeen Move - جميع الحقوق محفوظة
  </footer>

</body>
</html>
