<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ailin Vazquez | Art Portfolio</title>
    <style>
        /* Creative & Artistic Styling */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Courier New', Courier, monospace; /* Gives an indie, sketchbook feel */
        }

        body {
            background-color: #faf7f2; /* Soft canvas/paper colored background */
            color: #333230;
            line-height: 1.6;
        }

        header {
            text-align: center;
            padding: 4rem 2rem 2rem 2rem;
        }

        header h1 {
            font-size: 3rem;
            color: #2b4c59; /* Deep slate blue/teal */
            margin-bottom: 10px;
            letter-spacing: -1px;
        }

        .subtitle {
            font-size: 1.2rem;
            color: #bd7a5c; /* Terracotta/paint palette accent color */
            font-style: italic;
            font-weight: bold;
        }

        /* About Section */
        .about-container {
            max-width: 700px;
            margin: 0 auto padding;
            padding: 2rem;
            text-align: center;
            background: #ffffff;
            border: 2px solid #333230;
            box-shadow: 5px 5px 0px #bd7a5c; /* Cute retro drop shadow */
            border-radius: 4px;
        }

        .about-container p {
            margin-bottom: 15px;
            font-size: 1.05rem;
        }

        /* Art Gallery Section */
        .gallery-section {
            max-width: 1100px;
            margin: 4rem auto;
            padding: 0 2rem;
        }

        .gallery-section h2 {
            text-align: center;
            margin-bottom: 2rem;
            color: #2b4c59;
            font-size: 2rem;
            text-transform: uppercase;
        }

        .gallery-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }

        /* Polaroid / Gallery Frame Look */
        .art-card {
            background: white;
            padding: 15px;
            border: 1px solid #e0dad0;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
            transition: transform 0.3s ease;
        }

        .art-card:hover {
            transform: translateY(-5px) rotate(1deg);
        }

        .art-placeholder {
            width: 100%;
            height: 350px;
            background-color: #f3ece1;
            display: flex;
            justify-content: center;
            align-items: center;
            color: #a1998e;
            font-weight: bold;
            border: 1px dashed #cdc3b4;
            margin-bottom: 15px;
        }

        .art-info h3 {
            font-size: 1.2rem;
            color: #2b4c59;
            margin-bottom: 5px;
        }

        .art-info p {
            font-size: 0.9rem;
            color: #7a736a;
        }

        .tag {
            display: inline-block;
            background: #f3ece1;
            padding: 2px 8px;
            font-size: 0.75rem;
            border-radius: 3px;
            margin-top: 5px;
        }

        footer {
            text-align: center;
            padding: 3rem;
            color: #a1998e;
            font-size: 0.85rem;
            border-top: 1px dashed #cdc3b4;
            margin-top: 4rem;
        }
    </style>
</head>
<body>

    <header>
        <h1>Ailin Vazquez</h1>
        <p class="subtitle">High School Artist & Creator</p>
    </header>

    <main>
        <section class="about-container">
            <p>👋 Hey there! Welcome to my digital sketchbook.</p>
            <p>I am a high school student navigating life through colors, canvases, and sketchpads. My favorite escape is spending hours getting lost in drawing and painting.</p>
            <p>Whether it's messy acrylics on canvas, fine-liner ink sketches in my book, or experimenting with water colors—this is where I keep track of my creative journey.</p>
        </section>

        <section class="gallery-section">
            <h2>The Gallery</h2>
            <div class="gallery-grid">
                
                <div class="art-card">
                    <div class="art-placeholder">🎨 [ Acrylic Painting ]</div>
                    <div class="art-info">
                        <h3>Midnight Reflections</h3>
                        <p>An experimental piece playing around with shadows and neon light on canvas.</p>
                        <span class="tag">Painting</span>
                    </div>
                </div>

                <div class="art-card">
                    <div class="art-placeholder">✏️ [ Ink & Graphite ]</div>
                    <div class="art-info">
                        <h3>Classroom Doodles</h3>
                        <p>A detailed fine-liner sketch drawn right into the margins of my notebook.</p>
                        <span class="tag">Drawing</span>
                    </div>
                </div>

                <div class="art-card">
                    <div class="art-placeholder">🌊 [ Watercolor ]</div>
                    <div class="art-info">
                        <h3>Overwhelmed</h3>
                        <p>Blends of blues and purples exploring watercolor bleeding techniques.</p>
                        <span class="tag">Painting</span>
                    </div>
                </div>

            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 Crafted by Ailin Vazquez. Powered by GitHub Pages.</p>
    </footer>

</body>
</html>
