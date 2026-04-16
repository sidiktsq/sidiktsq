<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rizky Mochamad Sidik - Developer Portfolio</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f8f9fa;
            padding: 20px;
        }

        .container {
            max-width: 1000px;
            margin: 0 auto;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
            padding: 40px;
        }

        .header {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            margin-bottom: 30px;
            gap: 20px;
        }

        .header-left h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .header-left p {
            font-size: 1.1em;
            color: #555;
            margin-bottom: 20px;
        }

        .profile-image {
            flex-shrink: 0;
            order: 2;
        }

        .profile-image img {
            width: 300px;
            height: auto;
            border-radius: 8px;
            object-fit: cover;
        }

        .badges {
            display: flex;
            gap: 10px;
            flex-wrap: wrap;
            margin-bottom: 30px;
        }

        .badges img {
            height: 28px;
        }

        .skills-section {
            margin-top: 40px;
            padding-top: 30px;
            border-top: 2px solid #e0e0e0;
        }

        .skills-section h3 {
            font-size: 1.3em;
            margin-bottom: 15px;
            color: #333;
        }

        .skills-section img {
            max-width: 100%;
            height: auto;
        }

        .divider {
            margin: 30px 0;
            border: none;
            border-top: 2px solid #e0e0e0;
        }

        .support-section {
            margin-top: 40px;
            padding: 20px;
            background-color: #f0f4ff;
            border-left: 4px solid #dc2626;
            border-radius: 4px;
        }

        .support-section h3 {
            font-size: 1.1em;
            color: #333;
        }

        @media (max-width: 768px) {
            .header {
                flex-direction: column;
            }

            .header-left h1 {
                font-size: 1.8em;
            }

            .profile-image img {
                width: 100%;
                max-width: 100%;
            }

            .container {
                padding: 20px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Header Section -->
        <div class="header">
            <div class="header-left">
                <h1>
                    <img src="https://emojis.slackmojis.com/emojis/images/1531849430/4246/blob-sunglasses.gif?1531849430" 
                         alt="sunglasses emoji" 
                         width="32" 
                         height="32"/> 
                    TEMPAT REPO AING
                </h1>
                <p>SAYA RIZKY MOCHAMAD SIDIK (SidikTsq)</p>
            </div>
            <div class="profile-image">
                <img src="vilhaze.png" alt="Profile" />
            </div>
        </div>

        <!-- Contact & Social Badges -->
        <div class="badges">
            <a href="mailto:inimsss475@gmail.com" target="_blank">
                <img src="https://img.shields.io/badge/-inimsss-dc2626?style=flat&labelColor=dc2626&logo=gmail&logoColor=white" 
                     alt="Gmail Badge"/>
            </a>
            <a href="https://www.instagram.com/inimsss/" target="_blank">
                <img src="https://img.shields.io/badge/-@inimsss__-c026d3?style=flat&labelColor=c026d3&logo=instagram&logoColor=white" 
                     alt="Instagram Badge"/>
            </a>
            <a href="https://github.com/sidiktsq" target="_blank">
                <img src="https://img.shields.io/github/followers/sidiktsq?label=GitHub%20Followers" 
                     alt="GitHub Followers"/>
            </a>
        </div>

        <hr class="divider">

        <!-- Skills Section -->
        <div class="skills-section">
            <h3>💻 Tech Stack</h3>
            <img src="https://skillicons.dev/icons?i=js,ts,nuxtjs,vue,rust,scss,tailwind,vscode,git,figma,vite,redis,supabase,postgres,sqlite,pnpm,pinia,gcp,discord&theme=light" 
                 alt="Technology Skills"/>
        </div>

        <!-- Support Section -->
        <div class="support-section">
            <h3>📌 私の活動がお役に立てば、ぜひご支援をお願いいたします。</h3>
            <p style="margin-top: 10px; color: #555;">If my work has been helpful, please consider supporting me.</p>
        </div>
    </div>
</body>
</html>
