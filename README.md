## Hi there 👋

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ansah Hamzat Johnson | Portfolio</title>
    
    <style>
        /*
         * This CSS is a direct replacement for the Tailwind CSS classes
         * and the external font import. All styling is now self-contained.
         */
        :root {
            --font-family-body: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
            --color-gray-50: #f9fafb;
            --color-gray-800: #1f2937;
            --color-gray-700: #374151;
            --color-gray-200: #e5e7eb;
            --color-blue-800: #1e40af;
            --color-blue-700: #1d4ed8;
            --color-blue-600: #2563eb;
            --color-blue-500: #3b82f6;
            --color-blue-50: #eff6ff;
            --shadow-lg: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
        }

        body {
            font-family: var(--font-family-body);
            background-color: var(--color-gray-50);
            color: var(--color-gray-800);
            line-height: 1.5;
            margin: 0;
        }

        .container {
            max-width: 64rem; /* max-w-4xl */
            margin: 0 auto;
            padding: 1rem; /* p-4 */
        }
        
        @media (min-width: 768px) {
            .container {
                padding: 2rem; /* md:p-8 */
            }
        }

        header {
            text-align: center;
            padding-top: 2.5rem; /* py-10 */
            padding-bottom: 2.5rem; /* py-10 */
        }

        @media (min-width: 768px) {
            header {
                padding-top: 4rem; /* md:py-16 */
                padding-bottom: 4rem; /* md:py-16 */
            }
        }

        h1 {
            font-size: 1.875rem; /* text-3xl */
            font-weight: 700; /* font-bold */
            line-height: 1.25; /* leading-tight */
            letter-spacing: -0.025em; /* tracking-tight */
            color: var(--color-blue-800);
        }
        
        @media (min-width: 768px) {
            h1 {
                font-size: 3rem; /* md:text-5xl */
            }
        }

        main {
            display: flex;
            flex-direction: column;
            gap: 3rem; /* space-y-12 */
        }

        section {
            background-color: #fff;
            padding: 1.5rem; /* p-6 */
            border-radius: 0.75rem; /* rounded-xl */
            box-shadow: var(--shadow-lg); /* shadow-lg */
            border: 1px solid var(--color-gray-200);
        }

        @media (min-width: 768px) {
            section {
                padding: 2.5rem; /* md:p-10 */
            }
        }
        
        section p {
            font-size: 1rem; /* text-lg */
            color: var(--color-gray-700);
            line-height: 1.625; /* leading-relaxed */
        }

        @media (min-width: 768px) {
            section p {
                font-size: 1.125rem; /* md:text-xl */
            }
        }

        h2 {
            font-size: 1.5rem; /* text-2xl */
            font-weight: 700; /* font-bold */
            margin-bottom: 1.5rem; /* mb-6 */
            text-align: center;
            color: var(--color-blue-700);
        }

        @media (min-width: 768px) {
            h2 {
                font-size: 1.875rem; /* md:text-3xl */
            }
        }

        ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
            flex-direction: column;
            gap: 1.5rem; /* space-y-6 */
            color: var(--color-gray-700);
            font-size: 1rem; /* text-base */
        }
        
        @media (min-width: 768px) {
            ul {
                font-size: 1.125rem; /* md:text-lg */
            }
        }

        ul li {
            display: flex;
            align-items: flex-start;
        }

        ul li span {
            margin-right: 1rem; /* mr-4 */
            font-size: 1.5rem; /* text-2xl */
            font-weight: 700; /* font-bold */
            color: var(--color-blue-500);
        }

        ul li strong {
            color: var(--color-blue-800);
        }

        .cta-section {
            text-align: center;
            padding-top: 1rem; /* pt-4 */
            padding-bottom: 2.5rem; /* pb-10 */
        }

        .cta-button {
            display: inline-block;
            font-weight: 700; /* font-bold */
            padding: 0.75rem 2rem; /* py-3 px-8 */
            border-radius: 9999px; /* rounded-full */
            box-shadow: var(--shadow-lg);
            transition: all 0.3s ease;
            transform-origin: center;
            text-decoration: none;
        }

        .cta-button:hover {
            transform: scale(1.05);
        }

        .cta-button.primary {
            background-color: var(--color-blue-600);
            color: white;
            margin-right: 1rem; /* mr-4 */
        }

        .cta-button.primary:hover {
            background-color: var(--color-blue-700);
        }

        .cta-button.secondary {
            background-color: white;
            color: var(--color-blue-600);
            border: 2px solid var(--color-blue-600);
        }

        .cta-button.secondary:hover {
            background-color: var(--color-blue-50);
        }
        
        /* --- New CSS for the fade-in effect --- */
        .fade-in-section {
            opacity: 0;
            transform: translateY(20px);
            transition: opacity 0.8s ease-out, transform 0.8s ease-out;
        }

        .fade-in-section.is-visible {
            opacity: 1;
            transform: translateY(0);
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <div class="container">
        <!-- Main Headline Section -->
        <header>
            <h1>
                Ansah Hamzat Johnson: Front-End Developer | Medical Laboratory Scientist | Strategic Leader
            </h1>
        </header>

        <main>
            <!-- Introductory Section -->
            <section class="fade-in-section">
                <p>
                    A passionate and detail-oriented front-end developer with a unique, interdisciplinary background. My journey through Medical Laboratory Science has sharpened my analytical skills, while my leadership role as Editor-in-Chief has given me a strategic perspective on project management and communication. I build clean, responsive, and purposeful web applications that solve real-world problems. Welcome to my portfolio.
                </p>
            </section>

            <!-- What I Do Section -->
            <section class="fade-in-section">
                <h2>What I Do</h2>
                <ul>
                    <li>
                        <span>&#10003;</span>
                        <div>
                            <strong>Front-End Development:</strong>
                            I specialize in bringing ideas to life on the web, focusing on intuitive user interfaces and seamless user experiences.
                        </div>
                    </li>
                    <li>
                        <span>&#10003;</span>
                        <div>
                            <strong>Leadership & Strategy:</strong>
                            I lead teams, manage projects, and communicate effectively to ensure successful outcomes from concept to deployment.
                        </div>
                    </li>
                    <li>
                        <span>&#10003;</span>
                        <div>
                            <strong>Scientific Problem-Solving:</strong>
                            My background in medical science provides a unique perspective, allowing me to approach complex challenges with a data-driven and meticulous mindset.
                        </div>
                    </li>
                </ul>
            </section>

            <!-- Call to Action Section -->
            <section class="cta-section fade-in-section">
                <a href="projects.html" class="cta-button primary">
                    View My Projects
                </a>
                <a href="about.html" class="cta-button secondary">
                    Learn More About Me
                </a>
            </section>
        </main>
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', (event) => {
            // Get all sections that should have the fade-in effect.
            const sections = document.querySelectorAll('.fade-in-section');

            // Set up options for the IntersectionObserver.
            // rootMargin: '0px 0px -50px 0px' means the element is considered visible
            // 50px before it reaches the bottom of the viewport.
            // This makes the animation trigger a little earlier.
            const observerOptions = {
                root: null, // The viewport is the root.
                rootMargin: '0px',
                threshold: 0.1 // 10% of the element must be visible to trigger.
            };

            // Create a new IntersectionObserver instance.
            const observer = new IntersectionObserver((entries, observer) => {
                entries.forEach(entry => {
                    // Check if the element is currently intersecting the viewport.
                    if (entry.isIntersecting) {
                        // If it is, add the 'is-visible' class to trigger the animation.
                        entry.target.classList.add('is-visible');
                        // Stop observing the element once it has been animated.
                        observer.unobserve(entry.target);
                    }
                });
            }, observerOptions);

            // Loop through all the sections and start observing them.
            sections.forEach(section => {
                observer.observe(section);
            });
        });
    </script>
</body>
</html>
