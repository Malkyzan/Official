<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MALKYZAN SANITARY</title>
    <style>
        body {
            background-color: #FFC0CB; /* Baby pink background */
            background-image: url('https://www.transparenttextures.com/patterns/bubble-wrap.png'); /* Subtle balloon-like pattern */
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 20px;
            margin: 0;
        }
        .container {
            background: white;
            padding: 30px;
            border-radius: 10px;
            max-width: 500px;
            margin: auto;
            box-shadow: 0px 0px 20px rgba(0, 0, 0, 0.1);
        }
        h1 {
            font-size: 32px;
            font-weight: bold;
            color: #ff69b4;
        }
        h2 {
            font-size: 24px;
            margin-bottom: 20px;
            color: #333;
        }
        label, select, input, textarea {
            display: block;
            width: 100%;
            margin: 12px 0;
            padding: 12px;
            font-size: 16px;
            border: 2px solid #ff69b4;
            border-radius: 6px;
        }
        label {
            text-align: left;
            font-weight: bold;
        }
        button {
            background: #ff69b4;
            color: white;
            padding: 15px;
            font-size: 18px;
            border: none;
            border-radius: 6px;
            cursor: pointer;
            transition: background 0.3s ease;
        }
        button:hover {
            background-color: #ff1493;
        }
        input[type="text"], textarea {
            font-size: 16px;
        }
        /* Mobile Responsive */
        @media (max-width: 768px) {
            .container {
                width: 90%;
            }
        }
    </style>
</head>
<body>
    <!-- Google Translate Widget -->
    <div id="google_translate_element"></div>
    <script type="text/javascript">
        function googleTranslateElementInit() {
            new google.translate.TranslateElement({ pageLanguage: 'en' }, 'google_translate_element');
        }
    </script>
    <script type="text/javascript" src="//translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>

    <div class="container">
        <h1>MALKYZAN</h1>
        <h2>Sanitary Pad Feedback Survey</h2>
        
        <form action="https://formspree.io/f/mvgzrady" method="POST">
            <label for="name">Your First Name:</label>
            <input type="text" id="name" name="name" required placeholder="Enter your first name">

            <label for="location">Where are you from?</label>
            <input type="text" id="location" name="location" required placeholder="Enter your location">

            <label>What is the biggest issue you face with sanitary pads?</label>
            <select name="issue" required>
                <option>Not absorbent enough</option>
                <option>Uncomfortable material</option>
                <option>Prone to leaks</option>
                <option>Not eco-friendly</option>
                <option>Too expensive</option>
            </select>

            <label>What type of sanitary pad do you prefer?</label>
            <select name="type" required>
                <option>Ultra-thin</option>
                <option>Maxi/thick pad</option>
                <option>Overnight pad</option>
                <option>Pantyliner</option>
            </select>

            <label>What improvements would make sanitary pads better?</label>
            <select name="improvements" required>
                <option>Softer materials</option>
                <option>Better breathability</option>
                <option>Less irritation/friction</option>
                <option>More flexibility/movement-friendly</option>
            </select>

            <label>How important is eco-friendliness when choosing a sanitary pad?</label>
            <select name="eco" required>
                <option>Very important</option>
                <option>Somewhat important</option>
                <option>Not important</option>
            </select>

            <label>Have you experienced rashes or irritation from sanitary pads?</label>
            <select name="irritation" required>
                <option>Yes, often</option>
                <option>Sometimes</option>
                <option>Rarely</option>
                <option>Never</option>
            </select>

            <label>What do you think should be improved about pad absorbency?</label>
            <select name="absorbency" required>
                <option>Better absorption for heavy flow</option>
                <option>Faster drying surface</option>
                <option>No sticky/wet feeling after use</option>
                <option>No changes needed</option>
            </select>

            <label>What do you think is a fair price for a high-quality sanitary pad?</label>
            <input type="text" name="price" required placeholder="Enter your opinion on a fair price">

            <label>How do you dispose of used sanitary pads?</label>
            <select name="disposal" required>
                <option>Trash bin (regular waste)</option>
                <option>Recycle</option>
                <option>Reuse</option>
                <option>Special disposal bins in restrooms</option>
            </select>

            <label>What features would make sanitary pads more convenient?</label>
            <select name="features" required>
                <option>Better packaging for easy carrying</option>
                <option>Improved adhesive to stay in place</option>
                <option>Thinner design without losing absorbency</option>
                <option>Odor control without strong fragrances</option>
            </select>

            <label>Any additional suggestions for improving sanitary pads?</label>
            <textarea name="suggestions" placeholder="Write your feedback here..." required></textarea>

            <button type="submit">Send My Feedback</button>
        </form>
    </div>
</body>
</html>
