<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PPG Industry Talk Reflection</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: #333;
            line-height: 1.6;
            padding: 20px;
            min-height: 100vh;
        }
        
        .container {
            max-width: 900px;
            margin: 40px auto;
            background: white;
            border-radius: 20px;
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.2);
            overflow: hidden;
        }
        
        .header {
            background: linear-gradient(90deg, #1a237e 0%, #283593 100%);
            color: white;
            padding: 40px;
            text-align: center;
        }
        
        .header h1 {
            font-size: 2.8rem;
            margin-bottom: 10px;
            font-weight: 700;
        }
        
        .header p {
            font-size: 1.2rem;
            opacity: 0.9;
        }
        
        .logo {
            font-size: 3rem;
            margin-bottom: 20px;
            color: #5c6bc0;
        }
        
        .content {
            padding: 40px;
        }
        
        .details-card {
            background: #f8f9fa;
            border-radius: 15px;
            padding: 25px;
            margin-bottom: 30px;
            border-left: 5px solid #5c6bc0;
        }
        
        .details-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 15px;
        }
        
        .detail-item {
            display: flex;
            align-items: center;
            gap: 15px;
        }
        
        .icon {
            background: #5c6bc0;
            color: white;
            width: 45px;
            height: 45px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.2rem;
        }
        
        .detail-text h3 {
            color: #1a237e;
            margin-bottom: 5px;
        }
        
        .reflection-section {
            background: white;
            border-radius: 15px;
            padding: 30px;
            margin-bottom: 30px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            border-top: 3px solid #42a5f5;
        }
        
        .section-title {
            color: #1a237e;
            font-size: 1.8rem;
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .section-title i {
            color: #5c6bc0;
        }
        
        .reflection-text {
            font-size: 1.1rem;
            line-height: 1.8;
            color: #444;
        }
        
        .reflection-text p {
            margin-bottom: 20px;
        }
        
        .key-points {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin-top: 25px;
        }
        
        .point-card {
            background: #e8eaf6;
            padding: 20px;
            border-radius: 10px;
            transition: transform 0.3s;
        }
        
        .point-card:hover {
            transform: translateY(-5px);
            background: #c5cae9;
        }
        
        .point-card h4 {
            color: #1a237e;
            margin-bottom: 10px;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .tags {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 30px;
        }
        
        .tag {
            background: #1a237e;
            color: white;
            padding: 8px 20px;
            border-radius: 50px;
            font-size: 0.9rem;
            font-weight: 600;
        }
        
        .footer {
            background: #f5f5f5;
            padding: 25px;
            text-align: center;
            color: #666;
            border-top: 1px solid #eee;
        }
        
        .footer a {
            color: #5c6bc0;
            text-decoration: none;
            font-weight: 600;
        }
        
        .footer a:hover {
            text-decoration: underline;
        }
        
        @media (max-width: 768px) {
            .container {
                margin: 20px auto;
            }
            
            .header {
                padding: 30px 20px;
            }
            
            .header h1 {
                font-size: 2rem;
            }
            
            .content {
                padding: 25px;
            }
            
            .details-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <div class="logo">
                <i class="fas fa-chart-line"></i>
            </div>
            <h1>PPG Industry Talk Reflection</h1>
            <p>Global Operations, Data Analytics & SAP Systems</p>
        </div>
        
        <div class="content">
            <div class="details-card">
                <h2><i class="fas fa-info-circle"></i> Talk Details</h2>
                <div class="details-grid">
                    <div class="detail-item">
                        <div class="icon">
                            <i class="fas fa-calendar-alt"></i>
                        </div>
                        <div class="detail-text">
                            <h3>Date</h3>
                            <p>November 20, 2025</p>
                        </div>
                    </div>
                    
                    <div class="detail-item">
                        <div class="icon">
                            <i class="fas fa-clock"></i>
                        </div>
                        <div class="detail-text">
                            <h3>Time</h3>
                            <p>2:00 P.M.</p>
                        </div>
                    </div>
                    
                    <div class="detail-item">
                        <div class="icon">
                            <i class="fas fa-globe"></i>
                        </div>
                        <div class="detail-text">
                            <h3>Platform</h3>
                            <p>Online via Webex</p>
                        </div>
                    </div>
                    
                    <div class="detail-item">
                        <div class="icon">
                            <i class="fas fa-building"></i>
                        </div>
                        <div class="detail-text">
                            <h3>Company</h3>
                            <p>PPG Industries</p>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="reflection-section">
                <h2 class="section-title"><i class="fas fa-lightbulb"></i> Reflection</h2>
                <div class="reflection-text">
                    <p>This PPG industry talk was held online via Webex. The industry talk introduced how PPG operates globally by using data analytics, global infrastructure and SAP. With the help from these teams, PPG enables users to make faster decisions, reduce operational cost, enhance capability and performance.</p>
                    
                    <p>This talk session gives a clearer view of how real-world systems operate, including the need to manage large amounts of data, communicate across countries, and handle more complex execution processes.</p>
                </div>
                
                <div class="key-points">
                    <div class="point-card">
                        <h4><i class="fas fa-database"></i> Data Analytics</h4>
                        <p>Using data to drive decision-making and optimize global operations</p>
                    </div>
                    
                    <div class="point-card">
                        <h4><i class="fas fa-network-wired"></i> Global Infrastructure</h4>
                        <p>Managing operations across different countries and regions</p>
                    </div>
                    
                    <div class="point-card">
                        <h4><i class="fas fa-cogs"></i> SAP Systems</h4>
                        <p>Enterprise resource planning for streamlined processes</p>
                    </div>
                    
                    <div class="point-card">
                        <h4><i class="fas fa-rocket"></i> Performance</h4>
                        <p>Enhancing capability and reducing operational costs</p>
                    </div>
                </div>
                
                <div class="tags">
                    <span class="tag">#PPG</span>
                    <span class="tag">#IndustryTalk</span>
                    <span class="tag">#DataAnalytics</span>
                    <span class="tag">#SAP</span>
                    <span class="tag">#GlobalOperations</span>
                    <span class="tag">#BusinessTechnology</span>
                </div>
            </div>
        </div>
        
        <div class="footer">
            <p>Reflection created based on PPG Industry Talk • November 2025</p>
            <p>Shared on <a href="https://github.com" target="_blank">GitHub</a> • <a href="#contact">Contact</a></p>
        </div>
    </div>

    <script>
        // Simple animation for cards on load
        document.addEventListener('DOMContentLoaded', function() {
            const cards = document.querySelectorAll('.point-card');
            cards.forEach((card, index) => {
                card.style.opacity = '0';
                card.style.transform = 'translateY(20px)';
                
                setTimeout(() => {
                    card.style.transition = 'opacity 0.5s, transform 0.5s';
                    card.style.opacity = '1';
                    card.style.transform = 'translateY(0)';
                }, index * 200);
            });
            
            // Add current year to footer
            const yearSpan = document.querySelector('#current-year');
            if (yearSpan) {
                yearSpan.textContent = new Date().getFullYear();
            }
        });
    </script>
</body>
</html>

