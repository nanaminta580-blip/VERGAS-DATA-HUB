<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VERGAS DATA HUB | Fast & Affordable Data</title>
    <style>
        :root {
            --primary-blue: #003366;
            --accent-blue: #007bff;
            --white: #ffffff;
            --glass: rgba(255, 255, 255, 0.1);
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #001f3f 0%, #003366 100%);
            color: var(--white);
            line-height: 1.6;
        }

        header {
            text-align: center;
            padding: 60px 20px;
            background: rgba(0, 0, 0, 0.3);
            border-bottom: 2px solid var(--accent-blue);
        }

        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 4px solid var(--accent-blue);
            object-fit: cover;
            box-shadow: 0 0 20px rgba(0, 123, 255, 0.5);
            margin-bottom: 20px;
        }

        h1 {
            font-size: 3rem;
            letter-spacing: 2px;
            margin: 10px 0;
            text-transform: uppercase;
        }

        .welcome-note {
            max-width: 700px;
            margin: 20px auto;
            font-style: italic;
            font-size: 1.2rem;
            color: #d1d1d1;
        }

        .container {
            max-width: 1000px;
            margin: 40px auto;
            padding: 20px;
        }

        .pricing-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin-bottom: 50px;
        }

        .price-card {
            background: var(--glass);
            backdrop-filter: blur(10px);
            padding: 30px;
            border-radius: 15px;
            text-align: center;
            border: 1px solid rgba(255,255,255,0.1);
            transition: transform 0.3s ease;
        }

        .price-card:hover {
            transform: translateY(-10px);
            border-color: var(--accent-blue);
        }

        .price-card h2 { color: var(--accent-blue); margin-bottom: 5px; }
        .price-card p { font-size: 1.5rem; font-weight: bold; }

        .order-form {
            background: var(--white);
            color: #333;
            padding: 40px;
            border-radius: 20px;
            box-shadow: 0 15px 35px rgba(0,0,0,0.3);
        }

        .order-form h2 {
            text-align: center;
            color: var(--primary-blue);
            margin-bottom: 30px;
        }

        .form-group { margin-bottom: 20px; }
        label { display: block; margin-bottom: 10px; font-weight: bold; }
        input, select {
            width: 100%;
            padding: 12px;
            border: 1px solid #ccc;
            border-radius: 8px;
            box-sizing: border-box;
        }

        button {
            width: 100%;
            padding: 15px;
            background: var(--accent-blue);
            color: white;
            border: none;
            border-radius: 8px;
            font-size: 1.1rem;
            font-weight: bold;
            cursor: pointer;
            transition: background 0.3s;
        }

        button:hover { background: var(--primary-blue); }

        footer {
            text-align: center;
            padding: 40px;
            margin-top: 50px;
            font-size: 0.9rem;
            border-top: 1px solid rgba(255,255,255,0.1);
        }

        .creator-tag {
            color: var(--accent-blue);
            font-weight: bold;
        }
    </style>
</head>
<body>

    <header>
        <img src="WhatsApp Image 2026-01-18 at 2.09.35 PM.jpeg" alt="Nana" class="profile-img">
        <h1>VERGAS DATA HUB</h1>
        <div class="welcome-note">
            "Hello! I am <strong>ADU BOAHENG MINTA (Nana)</strong>. Welcome to Vergas Data Hub, your number one destination for lightning-fast and affordable data. We are here to keep you connected to the world without breaking the bank!"
        </div>
    </header>

    <div class="container">
        <div class="pricing-grid">
            <div class="price-card">
                <h2>1GB</h2>
                <p>GHS 5</p>
            </div>
            <div class="price-card">
                <h2>2GB</h2>
                <p>GHS 10</p>
            </div>
            <div class="price-card">
                <h2>10GB</h2>
                <p>GHS 50</p>
            </div>
            <div class="price-card">
                <h2>100GB</h2>
                <p>GHS 200</p>
            </div>
        </div>

        <section class="order-form">
            <h2>Place Your Order</h2>
            <form action="#">
                <div class="form-group">
                    <label>Full Name</label>
                    <input type="text" placeholder="Enter your name" required>
                </div>
                <div class="form-group">
                    <label>Phone Number (to receive data)</label>
                    <input type="tel" placeholder="050 000 0000" required>
                </div>
                <div class="form-group">
                    <label>Network</label>
                    <select required>
                        <option value="">Select Network</option>
                        <option value="MTN">MTN</option>
                        <option value="Telecel">Telecel</option>
                        <option value="AT">AT (AirtelTigo)</option>
                    </select>
                </div>
                <div class="form-group">
                    <label>Data Amount</label>
                    <select required>
                        <option value="1GB">1GB - GHS 5</option>
                        <option value="2GB">2GB - GHS 10</option>
                        <option value="10GB">10GB - GHS 50</option>
                        <option value="100GB">100GB - GHS 200</option>
                    </select>
                </div>
                <div class="form-group">
                    <label>Payment Method</label>
                    <select required>
                        <option value="momo">Mobile Money (MoMo)</option>
                        <option value="bank">Bank Transfer</option>
                    </select>
                </div>
                <button type="submit">Order Now</button>
            </form>
        </section>
    </div>

    <footer>
        <p>&copy; 2026 VERGAS DATA HUB. All rights reserved.</p>
        <p>Website created by <span class="creator-tag">ADU BOAHENG MINTA (Nana)</span></p>
    </footer>

</body>
</html>
