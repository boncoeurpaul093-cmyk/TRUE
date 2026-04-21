<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Paul Boncoeur | Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body>
    <nav>
        <div class="logo">PAUL <span>BONCOEUR</span></div>
        <ul>
            <li><a href="#about">À propos</a></li>
            <li><a href="#experience">Expérience</a></li>
            <li><a href="#education">Formation</a></li>
            <li><a href="#skills">Compétences</a></li>
        </ul>
    </nav>
    <header class="hero">
        <div class="hero-content">
            <h1>Paul Boncoeur</h1>
            <p class="tagline">Coordonnateur de projet & Responsable logistique</p>
            <p class="availability">Disponibilité : ONG | Organisations internationales | Projets humanitaires | Projets Freelance</p>
            <div class="contact-info">
                <div class="contact-left">
                    <span><i class="fas fa-envelope"></i> boncoeurpaul093@gmail.com</span>
                    <span><i class="fas fa-envelope"></i> razakbcoeur@yahoo.fr</span>
                </div>
                <div class="contact-right">
                    <span><i class="fas fa-phone"></i> +509 4140 2570</span>
                    <span><i class="fas fa-phone"></i> +509 37762118</span>
                </div>
            </div>
            <a href="#experience" class="btn">Découvrir mon parcours</a>
        </div>
    </header>
    <section id="about" class="section">
        <h2 class="section-title">Profil Professionnel</h2>
        <p class="profile-text">
            Je suis un professionnel engagé dans les domaines de la diplomatie, de la gestion des relations institutionnelles et de la coopération internationale. Je me distingue par une approche fondée sur le dialogue stratégique, l'analyse des enjeux humains et organisationnels, ainsi que la recherche de solutions durables dans des contextes sensibles. Formé en psychologie, management responsable et analyse décisionnelle, je possède une excellente capacité à comprendre les dynamiques sociales, culturelles et politiques qui influencent les négociations et la gouvernance locale. Mon parcours académique international renforce ma crédibilité dans les environnements multiculturels.
        </p>
    </section>
    <section id="experience" class="section gray-bg">
        <h2 class="section-title">Expérience Professionnelle</h2>
        <div class="timeline">
            <div class="timeline-item">
                <span class="date">2023 - Présent</span>
                <h3>Responsable Logistique & Coordination Événementielle</h3>
                <h4>SEF Globale - Haïti</h4>
                <ul>
                    <li>Planification et exécution logistique d'événements communautaires et privés.</li>
                    <li>Supervision d'équipes opérationnelles et gestion des budgets/délais.</li>
                    <li>Résolution de problèmes opérationnels en temps réel.</li>
                </ul>
            </div>
            <div class="timeline-item">
                <span class="date">2021</span>
                <h3>Assistant Archiviste & Appui Projet</h3>
                <h4>CARE Haïti</h4>
<ul>
    <li>Organisation et sécurisation de la documentation de projets humanitaires.</li>
    <li>Appui à la conformité administrative et aux exigences des bailleurs.</li>
    <li>Soutien aux équipes projet dans la gestion de l'information.</li>
</ul>
            </div>
            <div class="timeline-item">
                <span class="date">Continu</span>
                <h3>Initiatives Communautaires Locales</h3>
                <h4>Engagement Local & Impact Communautaire</h4>
                <ul>
                    <li>Dialogues avec les leaders - Facilitation des discussions stratégiques avec les acteurs clés et décideurs locaux.</li>
                    <li>Conceptions de projets sociaux - Développement et mise en œuvre de projets à fort impact social adaptés aux besoins communautaires.</li>
                    <li>Interface entre la population et autorités - Médiation et liaison entre les citoyens et les institutions publiques pour favoriser la gouvernance participative.</li>
                </ul>
            </div>
        </div>
    </section>
    <section id="skills" class="section">
        <h2 class="section-title">Compétences Clés</h2>
        <div class="skills-grid">
            <div class="skill-category">
                <h3>Gestion & Terrain</h3>
                <div class="tags">
                    <span>Coordination de projets</span> <span>CCS / SBC</span> <span>Suivi Évaluation (M&E)</span>
                    <span>Logistique</span> <span>Leadership terrain</span>
                </div>
            </div>
            <div class="skill-category">
                <h3>Outils & Tech</h3>
                <div class="tags">
                    <span>Excel</span> <span>Power BI</span> <span>WordPress</span> <span>Google Data Analytics</span>
                    <span>Cybersecurity</span> <span>Outils M&E</span>
                </div>
            </div>
        </div>
    </section>
    <section id="services" class="section">
        <h2 class="section-title">Mes Services</h2>
        <div class="services-grid">
            <div class="service-card">
                <i class="fas fa-pencil-alt service-icon"></i>
                <h3>Création de Logo</h3>
                <p>Design de logos professionnels et mémorables adaptés à votre identité visuelle et vos valeurs.</p>
                <button class="service-btn" onclick="openLogoModal()">Voir les réalisations</button>
            </div>
            <div class="service-card">
                <i class="fas fa-globe service-icon"></i>
                <h3>Création de Sites Web</h3>
                <p>Développement de sites web modernes, responsifs et optimisés pour le SEO avec WordPress et outils web.</p>
            </div>
            <div class="service-card">
                <i class="fas fa-image service-icon"></i>
                <h3>Portfolio</h3>
                <p>Présentation de mes travaux et réalisations en design graphique, développement web et gestion de projets.</p>
            </div>
            <div class="service-card">
                <i class="fas fa-book service-icon"></i>
                <h3>Teneur de Livres Indépendant</h3>
                <p>Services de comptabilité et de tenue de livres pour PME et entrepreneurs indépendants. Gestion complète des finances, facturation et rapports.</p>
            </div>
            <div class="service-card">
                <i class="fas fa-brain service-icon"></i>
                <h3>IA et Optimisations des Entreprises</h3>
                <p>Solutions d'intelligence artificielle et d'optimisation des processus métier pour améliorer l'efficacité et la productivité de votre organisation.</p>
                <button class="service-btn" onclick="openAIModal()">Nos solutions IA</button>
            </div>
            <div class="service-card">
                <i class="fas fa-code service-icon"></i>
                <h3>Web & Développement</h3>
                <p>Développement web full-stack avec HTML, CSS et Java. Création d'applications modernes et performantes adaptées à vos besoins.</p>
                <button class="service-btn" onclick="openPortfolioModal()">Portfolio personnel</button>
            </div>
        </div>
    </section>

    <section id="education" class="section gray-bg">
        <h2 class="section-title">Formations & Certifications</h2>
        <div class="education-grid">
            <div class="edu-card clickable-card" data-category="gestion">
                <i class="fas fa-tasks edu-card-icon"></i>
                <h3>Gestion de Projet</h3>
                <p>Google Project Management, Management Responsable (Univ. Laval), Financial Markets (Yale).</p>
                <span class="cert-badge">✓ 8 Certificats</span>
            </div>
            <div class="edu-card clickable-card" data-category="data">
                <i class="fas fa-chart-bar edu-card-icon"></i>
                <h3>Analyse de Données</h3>
                <p>Google Data Analytics, Introduction to Statistics (Stanford), Data Science (IBM).</p>
                <span class="cert-badge">✓ 8 Certificats</span>
            </div>
            <div class="edu-card clickable-card" data-category="tech">
                <i class="fas fa-laptop-code edu-card-icon"></i>
                <h3>Tech & IA</h3>
                <p>Google IT Support, Cybersecurity (NYU/Google), AI Foundations (IBM).</p>
                <span class="cert-badge">✓ 8 Certificats</span>
            </div>
            <div class="edu-card clickable-card" data-category="comptabilite">
                <i class="fas fa-calculator edu-card-icon"></i>
                <h3>Comptabilité</h3>
                <p>Intuit Academy Bookkeeping - Janvier 2026.</p>
                <span class="cert-badge">✓ 3 Certificats</span>
            </div>
            <div class="edu-card clickable-card" data-category="logistique">
                <i class="fas fa-truck edu-card-icon"></i>
                <h3>Logistique</h3>
                <p>Gestion de la chaîne d'approvisionnement, optimisation logistique et coordination des opérations.</p>
                <span class="cert-badge">✓ Certificats disponibles</span>
            </div>
            <div class="edu-card clickable-card" data-category="webdev">
                <i class="fas fa-code edu-card-icon"></i>
                <h3>Web & Développement</h3>
                <p>HTML, CSS, Java et développement web moderne. Maîtrise des technologies frontend et backend.</p>
                <span class="cert-badge">✓ Certificats disponibles</span>
            </div>
        </div>
        
        <!-- Section des certificats filtrés -->
        <div id="certificatesDisplay" style="margin-top: 50px; display: none;">
            <h3 id="selectedCategoryTitle" style="text-align: center; color: var(--primary-blue); margin-bottom: 30px;">Certificats</h3>
            <div class="certificates-grid" id="certificatesContainer"></div>
        </div>
    </section>
    
    <!-- Section Call to Action -->
    <section id="contact" class="section cta-section">
        <h2 class="section-title">Prêt à Collaborer ?</h2>
        <p class="cta-subtitle">Contactez-moi pour discuter de vos projets, besoins en diplomatie, gestion de relations institutionnelles ou services numériques.</p>
        
        <div class="cta-contacts">
            <div class="contact-method">
                <i class="fas fa-envelope contact-icon"></i>
                <h3>Email</h3>
                <a href="mailto:boncoeurpaul093@gmail.com" class="cta-link">boncoeurpaul093@gmail.com</a>
                <a href="mailto:razakbcoeur@yahoo.fr" class="cta-link">razakbcoeur@yahoo.fr</a>
            </div>
            <div class="contact-method">
                <i class="fas fa-phone contact-icon"></i>
                <h3>Téléphone</h3>
                <a href="tel:+50941402570" class="cta-link">+509 4140 2570</a>
                <a href="tel:+50937762118" class="cta-link">+509 37762118</a>
            </div>
            <div class="contact-method">
                <i class="fas fa-handshake contact-icon"></i>
                <h3>Disponibilité</h3>
                <p class="availability-text">ONG | Organisations internationales | Projets humanitaires | Freelance</p>
            </div>
        </div>
        
        <div class="cta-buttons">
            <a href="mailto:boncoeurpaul093@gmail.com?subject=Demande%20de%20collaboration&body=Bonjour%20Paul,%0A%0AJ'aimerais%20discuter%20d'une%20collaboration%20potentielle.%0A%0ACordialement" class="btn-cta btn-primary">
                <i class="fas fa-paper-plane"></i> Envoyer un Message
            </a>
            <button class="btn-cta btn-secondary" onclick="openContactModal()">
                <i class="fas fa-comments"></i> Formulaire de Contact
            </button>
        </div>
    </section>
    
    <footer>
        <p>&copy; 2026 Paul Boncoeur - Français (Maternel) | Anglais (Intermédiaire) | Italien (Débutant)</p>
    </footer>

    <!-- Modal pour afficher les certificats -->
    <div id="certificateModal" class="modal">
        <div class="modal-content">
            <span class="close">&times;</span>
            <h2 id="modalTitle">Certificat</h2>
            <div class="modal-body">
                <iframe id="pdfViewer" src="" style="width: 100%; height: 500px; border: none;"></iframe>
            </div>
            <div class="modal-footer">
                <a id="downloadBtn" href="" download class="btn-download">
                    <i class="fas fa-download"></i> Télécharger le certificat
                </a>
            </div>
        </div>
    </div>

    <!-- Modal pour afficher le Portfolio Personnel -->
    <div id="portfolioModal" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closePortfolioModal()">&times;</span>
            <h2 style="color: var(--primary-blue); text-align: center;">Portfolio Personnel - Web & Développement</h2>
            <div class="portfolio-grid" style="margin-top: 30px;">
                <div class="portfolio-item">
                    <i class="fas fa-globe portfolio-icon"></i>
                    <h3>Ce Portfolio</h3>
                    <p>Un site portfolio moderne et responsif créé avec HTML, CSS et Javascript. Présentation professionnelle avec sections interactives.</p>
                </div>
                <div class="portfolio-item">
                    <i class="fas fa-project-diagram portfolio-icon"></i>
                    <h3>Projets Web</h3>
                    <p>Développement de projets web complets avec architecture frontend moderne et gestion backend robuste.</p>
                </div>
                <div class="portfolio-item">
                    <i class="fas fa-mobile-alt portfolio-icon"></i>
                    <h3>Applications Responsives</h3>
                    <p>Création d'applications web responsive et adaptées à tous les appareils (desktop, tablet, mobile).</p>
                </div>
                <div class="portfolio-item">
                    <i class="fas fa-calculator portfolio-icon"></i>
                    <h3>Simulateur de Budget</h3>
                    <p>Application web interactive pour la gestion et la simulation de budgets. Outil utile pour PME et entrepreneurs indépendants.</p>
                </div>
            </div>
        </div>
    </div>

    <!-- Modal pour afficher les logos -->
    <div id="logoModal" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeLogoModal()">&times;</span>
            <h2 style="color: var(--primary-blue); text-align: center;">Mes Réalisations - Création de Logo</h2>
            <div class="logo-gallery" style="margin-top: 30px;">
                <div class="logo-card">
                    <img src="Desktop/IMAGEEE.jpg" alt="Logo PWEL O VAN" class="logo-image" onerror="this.src='https://via.placeholder.com/150?text=Logo+PWEL+O+VAN'">
                    <p class="logo-title">PWEL O VAN</p>
                    <p class="logo-description">Logo de marque professionnel avec design circulaire moderne</p>
                </div>
            </div>
        </div>
    </div>

    <!-- Modal pour formulaire de contact -->
    <div id="contactModal" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeContactModal()">&times;</span>
            <h2 style="color: var(--primary-blue); text-align: center;">Formulaire de Contact</h2>
            <form class="contact-form" onsubmit="submitContactForm(event)">
                <div class="form-group">
                    <label for="name">Nom complet *</label>
                    <input type="text" id="name" name="name" required>
                </div>
                <div class="form-group">
                    <label for="email">Email *</label>
                    <input type="email" id="email" name="email" required>
                </div>
                <div class="form-group">
                    <label for="phone">Téléphone</label>
                    <input type="tel" id="phone" name="phone">
                </div>
                <div class="form-group">
                    <label for="subject">Sujet *</label>
                    <select id="subject" name="subject" required>
                        <option value="">Sélectionner un sujet</option>
                        <option value="diplomacy">Diplomatie & Relations institutionnelles</option>
                        <option value="cooperation">Coopération internationale</option>
                        <option value="community">Initiatives communautaires</option>
                        <option value="web">Services Web & Développement</option>
                        <option value="consulting">Consulting & Optimisation</option>
                        <option value="other">Autre</option>
                    </select>
                </div>
                <div class="form-group">
                    <label for="message">Message *</label>
                    <textarea id="message" name="message" rows="5" required></textarea>
                </div>
                <button type="submit" class="btn-submit">Envoyer</button>
            </form>
        </div>
    </div>

    <script>
        // ===== Fonctions Portfolio Modal =====
        function openPortfolioModal() {
            document.getElementById('portfolioModal').style.display = 'block';
        }

        function closePortfolioModal() {
            document.getElementById('portfolioModal').style.display = 'none';
        }

        // ===== Fonctions Logo Modal =====
        function openLogoModal() {
            document.getElementById('logoModal').style.display = 'block';
        }

        function closeLogoModal() {
            document.getElementById('logoModal').style.display = 'none';
        }

        // ===== Fonctions Contact Modal =====
        function openContactModal() {
            document.getElementById('contactModal').style.display = 'block';
        }

        function closeContactModal() {
            document.getElementById('contactModal').style.display = 'none';
        }

        function submitContactForm(event) {
            event.preventDefault();
            const name = document.getElementById('name').value;
            const email = document.getElementById('email').value;
            const subject = document.getElementById('subject').value;
            const message = document.getElementById('message').value;
            
            // Créer un envoie par email
            const mailtoLink = `mailto:boncoeurpaul093@gmail.com?subject=${encodeURIComponent('Contact: ' + subject)}&body=${encodeURIComponent(`Nom: ${name}\nEmail: ${email}\n\nMessage:\n${message}`)}`;
            window.location.href = mailtoLink;
            
            // Fermer le modal
            closeContactModal();
        }

        // Données des certificats par catégorie
        const certificateData = {
            gestion: [
                { name: "Certificat 1", url: "Desktop/CERTIFICATION BONCOEUR PAUL/Coursera 1B3ED7HEMYIC.pdf" },
                { name: "Certificat 2", url: "Desktop/CERTIFICATION BONCOEUR PAUL/Coursera 54F0JTZWE1PI.pdf" },
                { name: "Certificat 3", url: "Desktop/CERTIFICATION BONCOEUR PAUL/Coursera 91F42UFNZ6SJ.pdf" },
                { name: "Certificat 4", url: "Desktop/CERTIFICATION BONCOEUR PAUL/Coursera 9H35SX5EJ6XT.pdf" },
                { name: "Certificat 5", url: "Desktop/CERTIFICATION BONCOEUR PAUL/Coursera 9H44HCG3TW8G.pdf" },
                { name: "Certificat 6", url: "Desktop/CERTIFICATION BONCOEUR PAUL/Coursera CUJ6I6A7VH6P.pdf" },
                { name: "Certificat 7", url: "Desktop/CERTIFICATION BONCOEUR PAUL/Coursera DORAVAZARPLF.pdf" },
                { name: "Certificat 24", url: "Desktop/CERTIFICATION BONCOEUR PAUL/Coursera UKMTA8GW5WH9.pdf" }
            ],
            data: [
                { name: "Certificat 8", url: "Desktop/CERTIFICATION BONCOEUR PAUL/Coursera DQ85N35F6ZSU.pdf" },
                { name: "Certificat 9", url: "Desktop/CERTIFICATION BONCOEUR PAUL/Coursera EYA660KQ40PK.pdf" },
                { name: "Certificat 10", url: "Desktop/CERTIFICATION BONCOEUR PAUL/Coursera FK5CIAYKQ9LR.pdf" },
                { name: "Certificat 11", url: "Desktop/CERTIFICATION BONCOEUR PAUL/Coursera JXSRKEXSYM6M.pdf" },
                { name: "Certificat 12", url: "Desktop/CERTIFICATION BONCOEUR PAUL/Coursera KFXSS38EQ80R.pdf" },
                { name: "Certificat 13", url: "Desktop/CERTIFICATION BONCOEUR PAUL/Coursera N6K5IK72MEHA.pdf" },
                { name: "Certificat 14", url: "Desktop/CERTIFICATION BONCOEUR PAUL/Coursera NJHMEUI8URY2.pdf" },
                { name: "Certificat 15", url: "Desktop/CERTIFICATION BONCOEUR PAUL/Coursera NKP4RFUN5TAV.pdf" }
            ],
            tech: [
                { name: "Certificat 16", url: "Desktop/CERTIFICATION BONCOEUR PAUL/Coursera P2DK4ZW9SRHB.pdf" },
                { name: "Certificat 17", url: "Desktop/CERTIFICATION BONCOEUR PAUL/Coursera PSXIYIJO8C1P.pdf" },
                { name: "Certificat 18", url: "Desktop/CERTIFICATION BONCOEUR PAUL/Coursera QEE96EI729IL.pdf" },
                { name: "Certificat 19", url: "Desktop/CERTIFICATION BONCOEUR PAUL/Coursera RUZAIEXA8FD1.pdf" },
                { name: "Certificat 20", url: "Desktop/CERTIFICATION BONCOEUR PAUL/Coursera SCRHWEMRUQU4.pdf" },
                { name: "Certificat 21", url: "Desktop/CERTIFICATION BONCOEUR PAUL/Coursera SJIOLUNFYQD1.pdf" },
                { name: "Certificat 22", url: "Desktop/CERTIFICATION BONCOEUR PAUL/Coursera U00UQ3LNKPAP.pdf" },
                { name: "Certificat 23", url: "Desktop/CERTIFICATION BONCOEUR PAUL/Coursera U4RP8TQIXGRY.pdf" }
            ],
            comptabilite: [
                { name: "Certificat 25", url: "Desktop/CERTIFICATION BONCOEUR PAUL/Coursera X4T9XC72ELLQ.pdf" },
                { name: "Certificat 26", url: "Desktop/CERTIFICATION BONCOEUR PAUL/Coursera X6VZ71UMZP7B.pdf" },
                { name: "Certificat 27", url: "Desktop/CERTIFICATION BONCOEUR PAUL/Coursera XHO2DI5S4NHY.pdf" }
            ],
            logistique: []
        };

        const categoryLabels = {
            gestion: "Gestion de Projet",
            data: "Analyse de Données",
            tech: "Tech & IA",
            comptabilite: "Comptabilité",
            logistique: "Logistique"
        };

        // Récupérer les éléments du modal
        const modal = document.getElementById('certificateModal');
        const closeBtn = document.querySelector('.close');
        const pdfViewer = document.getElementById('pdfViewer');
        const downloadBtn = document.getElementById('downloadBtn');
        const modalTitle = document.getElementById('modalTitle');

        // Gérer le clic sur les cartes de catégories
        const clickableCards = document.querySelectorAll('.clickable-card');
        const certificatesDisplay = document.getElementById('certificatesDisplay');
        const certificatesContainer = document.getElementById('certificatesContainer');
        const selectedCategoryTitle = document.getElementById('selectedCategoryTitle');

        clickableCards.forEach(card => {
            card.style.cursor = 'pointer';
            card.addEventListener('click', () => {
                const category = card.getAttribute('data-category');
                const certs = certificateData[category];
                
                // Mettre à jour le titre
                selectedCategoryTitle.textContent = `Certificats - ${categoryLabels[category]}`;
                
                // Vider et remplir le container
                certificatesContainer.innerHTML = '';
                certs.forEach(cert => {
                    const link = document.createElement('a');
                    link.href = cert.url;
                    link.className = 'cert-link';
                    link.target = '_blank';
                    link.innerHTML = `<i class="fas fa-trophy"></i> ${cert.name}`;
                    
                    link.addEventListener('click', (e) => {
                        e.preventDefault();
                        modalTitle.textContent = cert.name;
                        pdfViewer.src = cert.url;
                        downloadBtn.href = cert.url;
                        modal.style.display = 'block';
                    });
                    
                    certificatesContainer.appendChild(link);
                });
                
                // Afficher la section
                certificatesDisplay.style.display = 'block';
                
                // Scroller vers les certificats
                certificatesDisplay.scrollIntoView({ behavior: 'smooth', block: 'start' });
            });
        });

        // Fermer le modal
        closeBtn.addEventListener('click', () => {
            modal.style.display = 'none';
        });

        // Fermer en cliquant en dehors du modal
        window.addEventListener('click', (e) => {
            if (e.target === modal) {
                modal.style.display = 'none';
            }
        });
    </script>
</body>
</html>
