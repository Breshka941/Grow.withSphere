# Grow.withSphere
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="ContentSphere Solutions offers beginner-friendly micro-investing tips and faceless Reels to help you grow wealth with small steps.">
    <meta name="keywords" content="micro-investing, investing for beginners, financial growth, faceless reels, ContentSphere Solutions">
    <meta name="author" content="ContentSphere Solutions">
    <title>ContentSphere Solutions - Micro-Investing for Beginners</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <link rel="icon" type="image/x-icon" href="favicon.ico">
    <style>
        .gradient-bg {
            background: linear-gradient(135deg, #00CED1, #FF6B6B);
        }
        .neon-glow {
            background: linear-gradient(135deg, #00CED1, #FF6B6B);
            border: 2px solid #00CED1;
            box-shadow: 0 0 10px #00CED1, 0 0 20px #FF6B6B;
            transition: all 0.3s ease;
        }
        .neon-glow:hover {
            box-shadow: 0 0 20px #00CED1, 0 0 30px #FF6B6B;
            transform: scale(1.05);
        }
        .fade-in {
            animation: fadeIn 2s ease-in;
        }
        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }
    </style>
</head>
<body class="font-sans text-gray-800">
    <!-- Header -->
    <header class="gradient-bg text-white py-4">
        <div class="container mx-auto flex justify-between items-center px-4">
            <div class="flex items-center">
                <img src="contentsphere-logo.png" alt="ContentSphere Solutions Logo" class="h-12 mr-4 fade-in">
                <h1 class="text-2xl font-bold">ContentSphere Solutions</h1>
            </div>
            <nav class="space-x-4">
                <a href="#home" class="hover:text-gray-200">Home</a>
                <a href="#resources" class="hover:text-gray-200">Resources</a>
                <a href="#contact" class="hover:text-gray-200">Contact</a>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="home" class="py-20 text-center bg-gray-100">
        <div class="container mx-auto px-4">
            <h2 class="text-4xl font-bold mb-4 fade-in">Start Micro-Investing Today</h2>
            <p class="text-lg mb-6">Learn how to grow your wealth with small investments through our beginner-friendly tips and engaging faceless Reels.</p>
            <a href="#contact" class="neon-glow text-white font-bold py-2 px-4 rounded">Get Started</a>
        </div>
    </section>

    <!-- Resources Section -->
    <section id="resources" class="py-20">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-10">Micro-Investing Resources</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="text-center">
                    <i class="fas fa-coins text-4xl text-teal-500 mb-4"></i>
                    <h3 class="text-xl font-semibold mb-2">Beginner Guides</h3>
                    <p>Step-by-step tutorials on starting micro-investing with apps like Acorns or Stash.</p>
                </div>
                <div class="text-center">
                    <i class="fas fa-video text-4xl text-coral-500 mb-4"></i>
                    <h3 class="text-xl font-semibold mb-2">Faceless Reels</h3>
                    <p>Watch our viral Reels for quick tips on investing small amounts for big returns.</p>
                </div>
                <div class="text-center">
                    <i class="fas fa-chart-line text-4xl text-teal-500 mb-4"></i>
                    <h3 class="text-xl font-semibold mb-2">Growth