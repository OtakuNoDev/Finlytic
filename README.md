# Finlytic

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Finlytic - Financial Management Tool</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
            line-height: 1.7; /* Improved default line height for better readability */
        }
        .container {
            max-width: 960px; /* Slightly wider for larger screens */
            margin: 50px auto; /* Increased margin for better spacing */
            padding: 30px;
            background-color: #fff;
            border-radius: 12px; /* More rounded corners */
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.08); /* Subtle shadow, increased blur */
        }
        h1 {
            font-size: 2.6rem; /* Larger heading */
            font-weight: 700;
            color: #2c3e50;
            margin-bottom: 30px; /* Increased margin below heading */
            text-align: center; /* Center heading */
            letter-spacing: -0.02em;
        }
        h2 {
            font-size: 2rem; /* Larger subheading */
            font-weight: 600;
            color: #34495e;
            margin-top: 40px; /* Increased margin above subheading */
            margin-bottom: 25px; /* Increased margin below subheading */
            line-height: 1.3;
        }
        h3 {
            font-size: 1.5rem; /* Increased size of h3 */
            font-weight: 600;
            color: #e74c3c; /* A more vibrant color */
            margin-top: 30px;
            margin-bottom: 20px;
            line-height: 1.4;
        }
        p {
            font-size: 1.1rem; /* Slightly larger body text */
            color: #444; /* Slightly darker body text */
            margin-bottom: 25px; /* Increased margin below paragraphs */
            line-height: 1.7; /* Improved line height */
        }
        ul, ol {
            margin-left: 0;
            padding-left: 20px; /* Increased padding for lists */
            margin-bottom: 25px;
        }
        li {
            font-size: 1.1rem; /* Slightly larger list items */
            color: #444;
            line-height: 1.7; /* Improved line height for list items */
            margin-bottom: 8px; /* Added spacing between list items */
        }
        a {
            color: #3498db; /* A brighter link color */
            text-decoration: none;
            transition: color 0.3s ease; /* Smooth transition */
            font-weight: 500; /* Make links a bit bolder */
        }
        a:hover {
            color: #217dbb; /* Darker shade on hover */
        }
        strong {
            color: #2c3e50; /* Strong font color */
            font-weight: 600;
        }
        hr {
            border: 0;
            height: 1px;
            background-image: linear-gradient(to right, transparent, #d3d3d3, transparent); /* Gradient line */
            margin: 40px 0; /* Increased margin above and below hr */
        }
        /* Style for badges */
        .badge {
            display: inline-block;
            padding: 8px 16px;
            font-size: 0.9rem;
            font-weight: 500;
            color: white;
            background-color: #2ecc71; /* A brighter green */
            border-radius: 12px; /* More rounded corners for badges */
            margin-right: 10px;
            margin-bottom: 5px;
            transition: background-color 0.3s ease; /* Smooth transition for badges */
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.08); /* Subtle shadow for badges */
        }
        .badge:hover {
            background-color: #27ae60; /* Darker shade on hover for badges */
        }
        /* Style for code blocks */
        pre {
            background-color: #f0f0f0;
            padding: 20px;
            border-radius: 10px; /* More rounded corners for code blocks */
            margin-bottom: 25px;
            overflow-x: auto; /* Horizontal scrollbar for long code lines */
            font-size: 0.9rem; /* Slightly smaller font size for code */
            line-height: 1.6; /* Improved line height for code */
        }
        code {
            font-family: monospace;
            font-size: 0.9rem; /* Consistent code font size */
            color: #2c3e50;
        }

        /* Responsive adjustments */
        @media (max-width: 768px) {
            .container {
                padding: 20px;
                margin: 30px auto;
            }
            h1 {
                font-size: 2.2rem;
            }
            h2 {
                font-size: 1.8rem;
            }
            h3 {
                font-size: 1.3rem;
            }
            p, li {
                font-size: 1rem;
            }
            .badge {
                font-size: 0.8rem;
                padding: 6px 12px;
            }
            pre {
                padding: 15px;
                font-size: 0.85rem;
            }
        }

        /* Added styles for tables */
        table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 25px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
        }

        th, td {
            padding: 12px 15px;
            border-bottom: 1px solid #eee;
            text-align: left;
        }

        th {
            font-weight: 600;
            color: #34495e;
        }

        tr:last-child td {
            border-bottom: none;
        }

        tr:hover {
            background-color: #f5f5f5;
        }

        /* Style for images */
        img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            margin-bottom: 25px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.05);
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Finlytic - Financial Management Tool</h1>
        <p>
            Finlytic is a user-friendly financial management tool designed to simplify personal finance tracking. This project provides a mobile application that empowers users to effectively manage their income, expenses, and savings goals.
        </p>

        <h2>Project Overview</h2>
        <p>
            The Finlytic app aims to address the common challenges individuals face in managing their finances.  It provides tools for:
        </p>
        <ul>
            <li>Tracking income and expenses</li>
            <li>Monitoring transactions</li>
            <li>Setting and tracking savings goals</li>
            <li>Analyzing spending habits</li>
        </ul>
        <p>
            The app is designed with a clear and intuitive interface, making it accessible to users with varying levels of financial literacy.
        </p>

        <h2>Key Features</h2>
        <p>
            Finlytic includes the following key features:
        </p>
        <ul>
            <li><strong>User Authentication:</strong> Secure login and signup functionality.</li>
            <li><strong>Transaction Recording:</strong> Easy input of income and expense transactions.</li>
            <li><strong>Data Visualization:</strong> Charts and graphs for clear financial insights.</li>
            <li><strong>Savings Goal Setting:</strong> Tools to set and monitor financial goals.</li>
            <li><strong>Category Management:</strong> Categorization of transactions for better analysis.</li>
            <li><strong>Profile Management:</strong> User-friendly account settings.</li>
            <li><strong>Help and Support:</strong> Resources for user assistance.</li>
        </ul>

        <h2>UX Research and Design</h2>
        <p>
            The design of Finlytic is based on thorough UX research, focusing on user needs and pain points.  Key research insights include:
        </p>
        <ul>
            <li><strong>Need for Simplicity:</strong> Users desire an intuitive and easy-to-use interface.</li>
            <li><strong>Importance of Visual Clarity:</strong> Clear data visualization is crucial for understanding financial information.</li>
            <li><strong>Streamlined Onboarding:</strong> A quick and easy account creation process is essential.</li>
            <li><strong>Efficient Transaction Tracking:</strong>  Simple and fast transaction input is a priority.</li>
            <li><strong>Personalized Insights:</strong> Users benefit from personalized feedback and recommendations.</li>
        </ul>

        <h2>Team Members</h2>
        <p>
            The Finlytic project was developed by the following team:
        </p>
        <table>
            <thead>
                <tr>
                    <th>Name</th>
                    <th>PRN No</th>
                    <th>GitHub Profile</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Gaurav Jadhav</td>
                    <td>B24IT1054</td>
                    <td><a href="https://github.com/GauravJadhav">GauravJadhav</a></td>
                </tr>
                <tr>
                    <td>Shreyash Mandlapure</td>
                    <td>B24IT1130</td>
                    <td><a href="https://github.com/ShreyashMandlapure">ShreyashMandlapure</a></td>
                </tr>
                <tr>
                    <td>Tanushree Patil</td>
                    <td>B24IT1049</td>
                    <td><a href="https://github.com/TanushreePatil">TanushreePatil</a></td>
                </tr>
                <tr>
                    <td>Sanika Pujari</td>
                    <td>B24IT1058</td>
                    <td><a href="https://github.com/SanikaPujari">SanikaPujari</a></td>
                </tr>
            </tbody>
        </table>

        <h2>Future Improvements</h2>
        <p>
            The following improvements are planned for future development:
        </p>
        <ul>
            <li>Enhanced Personalization with AI-powered financial advice.</li>
            <li>Integration with financial institutions for automated transaction imports.</li>
            <li>Gamification elements to increase user engagement.</li>
            <li>Accessibility enhancements for all users.</li>
            <li>Refined data visualizations for more actionable insights.</li>
            <li>Robust user feedback mechanisms for continuous improvement.</li>
        </ul>

        <h2>Conclusion</h2>
        <p>
            Finlytic aims to empower users to take control of their finances through a simple, intuitive, and feature-rich mobile application.  We believe that Finlytic can make a significant difference in how people manage their money.
        </p>
    </div>
</body>
</html>
