# Hong Kong Future Healers
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Hong Kong Future Healers</title>
</head>
<body>
    <div class="container">
        <aside class="sidebar">
            <h2>Menu</h2>
            <nav>
                <ul>
                    <li><a href="#about" onclick="scrollToSection(event, 'about')">About Us</a></li>
                    <li><a href="#blog" onclick="scrollToSection(event, 'blog')">Blog</a></li>
                    <li><a href="#advocacy" onclick="scrollToSection(event, 'advocacy')">Advocacy</a></li>
                    <li><a href="#prevention" onclick="scrollToSection(event, 'prevention')">Prevention</a></li>
                    <li><a href="#selfcare" onclick="scrollToSection(event, 'selfcare')">Self-Care</a></li>
                    <li><a href="#funfacts" onclick="scrollToSection(event, 'funfacts')">Fun Facts</a></li>
                    <li><a href="#selfassessment" onclick="scrollToSection(event, 'selfassessment')">Self-Assessment</a></li>
                    <li><a href="#medicalterms" onclick="scrollToSection(event, 'medicalterms')">Medical Terms</a></li>
                    <li><a href="#sharing" onclick="scrollToSection(event, 'sharing')">Sharing</a></li>
                    <li><a href="#hotline" onclick="scrollToSection(event, 'hotline')">Hotline</a></li>
                    <li><a href="#podcast" onclick="scrollToSection(event, 'podcast')">Podcast</a></li>
                    <li><a href="#information" onclick="scrollToSection(event, 'information')">Information</a></li>
                    <li><a href="#activities" onclick="scrollToSection(event, 'activities')">Activities</a></li>
                </ul>
            </nav>
        </aside>
        <main>
            <section id="about">
                <h2>About Us</h2>
                <p>Your mission statement goes here.</p>
            </section>
            <section id="blog">
                <h2>Blog</h2>
                <p>Recent blog posts will be listed here.</p>
            </section>
            <section id="advocacy">
                <h2>Advocacy</h2>
                <p>Current advocacy efforts.</p>
            </section>
            <section id="prevention">
                <h2>Prevention</h2>
                <p>Prevention strategies.</p>
            </section>
            <section id="selfcare">
                <h2>Self-Care</h2>
                <p>Self-care tips.</p>
            </section>
            <section id="funfacts">
                <h2>Fun Facts</h2>
                <p>Interesting facts about health.</p>
            </section>
            <section id="selfassessment">
                <h2>Self-Assessment</h2>
                <p>Self-assessment tools.</p>
            </section>
            <section id="medicalterms">
                <h2>Medical Terms</h2>
                <p>Glossary of terms.</p>
            </section>
            <section id="sharing">
                <h2>Sharing</h2>
                <p>User stories.</p>
            </section>
            <section id="hotline">
                <h2>Hotline</h2>
                <p>Hotline resources.</p>
            </section>
            <section id="podcast">
                <h2>Podcast</h2>
                <p>Links to podcast episodes.</p>
            </section>
            <section id="information">
                <h2>Information</h2>
                <p>Educational resources.</p>
            </section>
            <section id="activities">
                <h2>Activities</h2>
                <p>Upcoming activities.</p>
            </section>
        </main>
    </div>
    <footer>
        <p>&copy; 2025 Hong Kong Future Healers</p>
    </footer>
    <script>
        function scrollToSection(event, sectionId) {
            event.preventDefault();
            const section = document.getElementById(sectionId);
            section.scrollIntoView({ behavior: 'smooth' });
        }
    </script>
</body>
</html>
