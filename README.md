# Proposal<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>A Special Question For Huriya ❤️</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Elegant Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Parisienne&family=Playfair+Display:wght@400;700&display=swap" rel="stylesheet">
    <style>
        .font-parisienne { font-family: 'Parisienne', cursive; }
        .font-playfair { font-family: 'Playfair Display', serif; }
        .main-container {
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            background: linear-gradient(135deg, #fcd0df 0%, #ff8fa3 100%);
        }
        .card {
            box-shadow: 0 15px 40px rgba(255, 69, 110, 0.5);
            transition: transform 0.4s ease-in-out;
            border: 1px solid rgba(255, 255, 255, 0.8);
        }
        .card:hover { transform: scale(1.02); }
        @keyframes pulse-heart {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.05); }
        }
        .animate-heart-pulse { animation: pulse-heart 2s infinite ease-in-out; }
    </style>
</head>
<body>
    <!-- Formal Banner -->
    <div class="w-full max-w-xl mx-auto mb-4 p-4 bg-white rounded-xl shadow-lg text-center border border-pink-300">
        <h2 class="font-playfair text-2xl font-bold text-red-600 mb-2">A Special Question For Huriya</h2>
        <p class="text-gray-700 font-playfair mb-1">Created by Zaheer Baig with love & care.</p>
        <p class="text-gray-500 text-sm">Open this link to view a heartfelt message and an important question for you.</p>
    </div>
    <div class="main-container p-4">
        <div class="card bg-white p-8 md:p-16 rounded-3xl max-w-xl w-full text-center">
            <!-- Proposal Text Area -->
            <h1 class="font-parisienne text-7xl md:text-9xl text-red-500 mb-8 animate-heart-pulse">
                My Heart ❤️
            </h1>
            <p id="proposal-text" class="font-playfair text-xl md:text-2xl text-gray-700 mb-10 leading-relaxed italic">
                This page exists for one reason only: to ask you the most important question of my life.
            </p>
            <!-- Proposal Question & Result Area -->
            <div id="result-message" class="hidden font-playfair text-3xl font-bold p-4 rounded-xl"></div>
            <p id="question-prompt" class="font-playfair text-3xl md:text-4xl font-bold text-pink-600 mb-10">
                Will you be mine forever, cutie Huriya?
            </p>
            <!-- Buttons Container -->
