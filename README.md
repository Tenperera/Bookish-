<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Bookish!</title>
    <style>
        body {
            font-family: Arial, Helvetica, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f4f0;
            color: #333;
        }

        header {
            background-color: #6a4e77;
            padding: 20px;
            color: white;
            text-align: center;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
            margin: 10px 0;
        }

        nav ul li {
            display: inline;
            margin: 0 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            cursor: pointer;
        }

        nav ul li a:hover {
            text-decoration: underline;
        }

        main {
            padding: 20px;
            max-width: 800px;
            margin: auto;
        }

        section {
            display: none;
        }

        section.active {
            display: block;
        }

        footer {
            background-color: #d8cdd0;
            text-align: center;
            padding: 10px;
            font-size: 0.9em;
            margin-top: 30px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Bookish!</h1>
        <nav>
            <ul>
                <li><a onclick="showSection('home')">Home</a></li>
                <li><a onclick="showSection('about')">About</a></li>
                <li><a onclick="showSection('history')">History</a></li>
                <li><a onclick="showSection('figures')">Prominent Figures</a></li>
                <li><a onclick="showSection('works')">Literary Works</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="home" class="active">
            <h2>Welcome to Bookish!</h2>
            <p>Where the mind is intoxicated by words, and the soul feasts on stories.</p>
            <p>Explore the magic of literature, its rich history, and the figures who shaped our world with their pens.</

