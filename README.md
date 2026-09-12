<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile Cá Nhân - Mẫu 1</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; }
        body { background-color: #0f172a; color: #f8fafc; line-height: 1.6; display: flex; justify-content: center; align-items: center; min-height: 100vh; padding: 20px; }
        .card { background: #1e293b; border-radius: 16px; padding: 40px; max-width: 500px; width: 100%; text-align: center; box-shadow: 0 10px 25px rgba(0, 0, 0, 0.3); border: 1px solid #334155; }
        .avatar { width: 120px; height: 120px; border-radius: 50%; border: 4px solid #38bdf8; margin-bottom: 20px; object-fit: cover; }
        h1 { font-size: 1.8rem; color: #f8fafc; margin-bottom: 5px; }
        .title { color: #38bdf8; font-weight: 600; margin-bottom: 15px; text-transform: uppercase; letter-spacing: 1px; font-size: 0.9rem; }
        .bio { color: #94a3b8; font-size: 0.95rem; margin-bottom: 25px; }
        .tags { display: flex; justify-content: center; gap: 8px; flex-wrap: wrap; margin-bottom: 25px; }
        .tag { background: #334155; color: #e2e8f0; padding: 5px 12px; border-radius: 20px; font-size: 0.8rem; }
        .links { display: flex; flex-direction: column; gap: 12px; }
        .btn { display: block; padding: 12px; background: #0284c7; color: white; text-decoration: none; border-radius: 8px; font-weight: 600; transition: all 0.3s ease; }
        .btn:hover { background: #0369a1; transform: translateY(-2px); }
        .btn-outline { background: transparent; border: 1px solid #475569; color: #e2e8f0; }
        .btn-outline:hover { background: #334155; }
    </style>
</head>
<body>

    <div class="card">
        <img src="https://via.placeholder.com/150" alt="Avatar" class="avatar">
        <h1>Nguyễn Văn A</h1>
        <div class="title">Full Stack Developer</div>
        <p class="bio">Đam mê sáng tạo các ứng dụng web tối ưu và trải nghiệm người dùng tuyệt vời.</p>
        
        <div class="tags">
            <span class="tag">JavaScript</span>
            <span class="tag">ReactJS</span>
            <span class="tag">Node.js</span>
            <span class="tag">UI/UX</span>
        </div>

        <div class="links">
            <a href="#" class="btn">Xem Dự Án (Portfolio)</a>
            <a href="#" class="btn btn-outline">GitHub</a>
            <a href="#" class="btn btn-outline">Liên Hệ Qua Zalo / Email</a>
        </div>
    </div>

</body>
</html>

