<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Existential Capture | AI Behavioral Profiling & Algorithmic Determinism</title>
    <meta name="description" content="An in-depth editorial index analyzing how corporate entities, state surveillance networks, and tech monopolies leverage machine learning to profile, categorize, predict, and weaponize human behavior.">
    
    <style>
        :root {
            --primary: #090d16;
            --secondary: #0f172a;
            --accent: #3b82f6;
            --accent-hover: #60a5fa;
            --text-dark: #f8fafc;
            --text-muted: #94a3b8;
            --bg: #020617;
            --card-bg: #0f172a;
            --border: #1e293b;
            --shadow: 0 4px 6px -1px rgb(0 0 0 / 0.5), 0 2px 4px -2px rgb(0 0 0 / 0.5);
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
        }

        body {
            background-color: var(--bg);
            color: var(--text-dark);
            line-height: 1.75;
            font-size: 1.05rem;
        }

        header {
            background-color: var(--primary);
            color: white;
            padding: 1.5rem 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 1.5rem;
            box-shadow: var(--shadow);
            position: sticky;
            top: 0;
            z-index: 100;
            border-bottom: 1px solid var(--border);
        }

        header h1 {
            font-size: 1.5rem;
            font-weight: 800;
            letter-spacing: -0.04em;
            cursor: pointer;
        }

        header h1 span {
            color: var(--accent);
        }

        header nav {
            display: flex;
            gap: 1.5rem;
        }

        header nav a {
            color: #94a3b8;
            text-decoration: none;
            font-weight: 600;
            font-size: 0.95rem;
            transition: color 0.2s;
            cursor: pointer;
        }

        header nav a:hover, header nav a.active {
            color: white;
        }

        /* AdSense Ads Layout Framework */
        .adsense-placeholder {
            background: #0f172a;
            border: 1px solid var(--border);
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            color: var(--text-muted);
            font-size: 0.75rem;
            text-transform: uppercase;
            font-weight: 700;
            letter-spacing: 0.08em;
            margin: 1.5rem auto;
            text-align: center;
            border-radius: 6px;
        }

        .ad-top { height: 90px; max-width: 728px; width: 100%; }
        .ad-sidebar { height: 600px; width: 300px; margin-top: 1.5rem; }
        .ad-inline { height: 250px; width: 100%; margin: 2.5rem 0; }

        .container {
            max-width: 1250px;
            margin: 2rem auto;
            padding: 0 1.5rem;
            display: grid;
            grid-template-columns: 1fr 320px;
            gap: 2.5rem;
        }

        @media (max-width: 1024px) {
            .container { grid-template-columns: 1fr; }
            .sidebar-wrapper { display: flex; flex-direction: column; gap: 2rem; }
            .ad-sidebar { display: none; }
        }

        main {
            background: var(--card-bg);
            border-radius: 12px;
            border: 1px solid var(--border);
            padding: 3rem;
            box-shadow: var(--shadow);
            min-height: 600px;
        }

        @media (max-width: 640px) { 
            main { padding: 1.5rem; } 
        }

        /* Sidebar Navigation Controls */
        .sidebar-menu {
            background: var(--card-bg);
            border: 1px solid var(--border);
            border-radius: 12px;
            padding: 1.5rem;
            box-shadow: var(--shadow);
        }

        .sidebar-menu h2 {
            font-size: 1rem;
            text-transform: uppercase;
            letter-spacing: 0.05em;
            color: var(--text-muted);
            margin-bottom: 1rem;
            border-bottom: 2px solid var(--border);
            padding-bottom: 0.5rem;
        }

        .article-link {
            display: block;
            padding: 0.75rem 1rem;
            color: #cbd5e1;
            text-decoration: none;
            border-radius: 6px;
            margin-bottom: 0.5rem;
            font-size: 0.95rem;
            font-weight: 600;
            line-height: 1.4;
            transition: all 0.2s;
            border-left: 3px solid transparent;
            cursor: pointer;
        }

        .article-link:hover {
            background: #1e293b;
            color: var(--accent-hover);
        }

        .article-link.active {
            background: #1e293b;
            color: #ffffff;
            border-left-color: var(--accent);
        }

        /* Content Render Styles */
        .content-view { display: none; }
        .content-view.active { display: block; }

        .meta-info {
            display: flex;
            gap: 1rem;
            font-size: 0.85rem;
            color: var(--text-muted);
            margin-bottom: 1rem;
            text-transform: uppercase;
            letter-spacing: 0.05em;
            font-weight: 600;
        }

        .meta-info .category { color: var(--accent-hover); }

        h1.article-title {
            font-size: 2.3rem;
            color: var(--text-dark);
            line-height: 1.2;
            margin-bottom: 2rem;
            letter-spacing: -0.03em;
        }

        h2.section-title {
            font-size: 1.5rem;
            color: var(--text-dark);
            margin: 2.5rem 0 1.25rem 0;
            border-bottom: 2px solid var(--border);
            padding-bottom: 0.5rem;
        }

        h3.subsection-title {
            font-size: 1.2rem;
            color: #e2e8f0;
            margin: 1.5rem 0 0.5rem 0;
        }

        p { margin-bottom: 1.5rem; color: #cbd5e1; }

        blockquote {
            border-left: 4px solid var(--accent);
            background-color: #1e293b;
            padding: 1.5rem;
            margin: 2.5rem 0;
            font-style: italic;
            color: #94a3b8;
            border-radius: 0 8px 8px 0;
        }

        /* Tech Feature Table Inside Content */
        .analysis-table {
            width: 100%;
            border-collapse: collapse;
            margin: 2rem 0;
            font-size: 0.95rem;
        }
        .analysis-table th, .analysis-table td {
            padding: 0.75rem 1rem;
            border: 1px solid var(--border);
            text-align: left;
        }
        .analysis-table th { background-color: #1e293b; color: var(--text-dark); font-weight: 700; }
        .analysis-table td { color: #cbd5e1; }

        footer {
            background-color: var(--primary);
            color: #64748b;
            text-align: center;
            padding: 3rem 2rem;
            margin-top: 5rem;
            font-size: 0.9rem;
            border-top: 1px solid var(--border);
        }

        footer nav {
            margin-top: 1rem;
            display: flex;
            justify-content: center;
            gap: 1.5rem;
        }

        footer nav button {
            background: none;
            border: none;
            color: #64748b;
            cursor: pointer;
            font-size: 0.9rem;
            text-decoration: underline;
        }

        footer nav button:hover { color: white; }

        .modal {
            display: none;
            position: fixed;
            top: 0; left: 0; width: 100%; height: 100%;
            background-color: rgba(2, 6, 23, 0.8);
            backdrop-filter: blur(4px);
            z-index: 1000;
            justify-content: center; align-items: center;
            padding: 1rem;
        }

        .modal-content {
            background-color: var(--card-bg);
            padding: 2rem; border-radius: 12px;
            border: 1px solid var(--border);
            max-width: 650px; width: 100%;
            max-height: 80vh; overflow-y: auto;
            box-shadow: var(--shadow); position: relative;
        }

        .close-btn {
            position: absolute; top: 1rem; right: 1rem;
            background: #1e293b; border: none; font-size: 1.25rem;
            color: var(--text-dark);
            width: 32px; height: 32px; border-radius: 50%;
            cursor: pointer; display: flex; align-items: center; justify-content: center;
        }
        .close-btn:hover { background: #334155; }
    </style>
</head>
<body>

    <div class="adsense-placeholder ad-top">
        <span>Advertisement - Top Leaderboard (728x90)</span>
    </div>

    <header>
        <h1 onclick="showArticle('main-essay')"><span>Algorithmic</span> Lens</h1>
        <nav>
            <a onclick="showArticle('main-essay')" id="nav-home">Home Index</a>
            <a onclick="showArticle('about-page')" id="nav-about">Editorial Intent</a>
        </nav>
    </header>

    <div class="container">
        <!-- Main Research Engine Viewport -->
        <main id="content-container">
            
            <!-- ARTICLE 1: MAIN PILLAR ESSAY -->
            <div id="main-essay" class="content-view active">
                <div class="meta-info">
                    <span class="category">Framework Overview</span>
                    <span>•</span><span>Vol. 1, No. 1</span>
                </div>
                <h1 class="article-title">The Existential Capture: Mapping the Frameworks of Algorithmic Determinism</h1>
                <p>When institutions employ machine learning infrastructure at scale, they alter the operational landscape of public behavior. These predictive technologies capture real-world human telemetry and convert individual lives into probabilistic equations, forcing people into automated boxes based entirely on historical data profiles.</p>
                
                <h2 class="section-title">1. The Corporate Entities: Determining Your "Value Tier"</h2>
                <p>Large tech conglomerates, financial institutions, and insurance giants use machine learning models for psychometric and behavioral profiling. They aren't trying to find your cosmic purpose; they are trying to find your lifetime financial value.</p>
                <h3 class="subsection-title">Predictive Credit & Opportunity Scoring</h3>
                <p>Modern AI credit scoring platforms go far beyond your payment history. They analyze alternative data—your mobile phone usage, utility payments, spending habits, online behavior, and even psychometric data (how you fill out forms or interact with apps). The AI uses this to calculate a real-time risk profile, effectively deciding your place in the economy—whether you are granted a mortgage, given low-interest rates, or locked out of financial opportunities.</p>
                <h3 class="subsection-title">Algorithmic Labor Allocation</h3>
                <p>If you apply for a job at a major enterprise, an AI entity often scans your resume, analyzes your voice patterns or micro-expressions in video interviews, and cross-references your digital footprint. The AI determines if your purpose matches their optimization goals, sorting human beings into rigid corporate boxes before a human ever sees your application.</p>

                <h2 class="section-title">2. The State Entities: Determining Your "Risk Tier"</h2>
                <p>Governments and state-sanctioned surveillance apparatuses use AI to define an individual's place along the spectrum of compliance and security risk.</p>
                <h3 class="subsection-title">Behavioral and Predictive Surveillance</h3>
                <p>As AI surveillance has evolved, systems have shifted from simple recording to continuous interpretation. State entities use computer vision and machine learning to build behavioral profiles. By analyzing spatial relationships, travel patterns, and associations, AI flags individuals who exhibit anomalous behavior. In essence, the algorithm pre-determines your likelihood to disrupt the system before any infraction occurs.</p>
                <h3 class="subsection-title">Social Credit Scoring</h3>
                <p>In its most literal execution, systems like China's corporate and social credit grids use deep learning to synthesize data from court records, shopping habits, traffic cameras, and social connections. The AI calculates a score that dictates your exact structural place in society—determining whether you are permitted to buy high-speed train tickets, send your children to certain schools, or access fast internet.</p>

                <div class="adsense-placeholder ad-inline">
                    <span>Advertisement - In-Article Placement</span>
                </div>

                <h2 class="section-title">3. The Tech Monopolies: Determining Your "Attention Box"</h2>
                <p>Social media and advertising giants (Meta, ByteDance, Google) use what are arguably the most powerful behavioral AI models on earth to map your psychological makeup.</p>
                <h3 class="subsection-title">The Digital Twin</h3>
                <p>By tracking every millisecond you linger on a post, your typing cadence, your location history, and your private messages, AI maps your vulnerabilities, political leanings, fears, and desires.</p>
                <h3 class="subsection-title">Defining Your Reality</h3>
                <p>Once the AI determines who you are, its sole purpose is to feed you content that keeps you engaged. It constructs a personalized echo chamber around you. In a very real sense, the algorithm attempts to dictate your perceived purpose by deciding what information you consume, what movements you support, and what you believe to be true about the world.</p>

                blockquote>
                    "The algorithms are designed to treat you as a fixed equation to be solved and monetized. The real danger isn't that the AI accurately finds your true place or purpose in the universe—it's that if humans listen to these systems long enough, we might let them define it for us."
                </blockquote>
            </div>

            <!-- ARTICLE 2: IN-DEPTH REVERSE ENGINEERING DEEP DIVE -->
            <div id="deep-dive-1" class="content-view">
                <div class="meta-info">
                    <span class="category">Technical Analysis</span>
                    <span>•</span><span>Technical Dossier</span>
                </div>
                <h1 class="article-title">Reverse-Engineering the Digital Twin: How Vector Embeddings Map Human Psychology</h1>
                <p>To understand how an algorithm determines "who you are," one must peel back the marketing jargon of artificial intelligence and look at the actual mathematical constructs underlying modern behavioral profiling: <strong>High-Dimensional Vector Embeddings</strong>.</p>
                <p>An AI does not think of you as a name, a gender, or an employment status. Instead, neural networks convert every action you perform—the velocity at which you scroll past an image, the specific punctuation choices in an email, the time of day you check your bank balances—into numerical coordinates inside a massive, multidimensional vector space.</p>
                
                <h2 class="section-title">The Mathematics of Identity Isolation</h2>
                <p>In a standard vector embedding model, a human profile can consist of thousands of unique dimensions (axes). For example, your political leanings might be plotted on axis 412, while your neurological susceptibility to impulse purchasing is mapped on axis 884. When data brokers run cluster analysis models, they don't look at individual variables; they calculate the **cosine similarity** between your behavioral coordinates and known psychological benchmarks.</p>
                
                <table class="analysis-table">
                    <thead>
                        <tr>
                            <th>Telemetry Data Feed</th>
                            <th>Algorithmic Interpretation Vector</th>
                            <th>Inferred Categorization Tier</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>Typing speed cadence & phone gyro data</td>
                            <td>Neurological fatigue / Stress state indicators</td>
                            <td>Targeted high-risk financial product ads</td>
                        </tr>
                        <tr>
                            <td>Micro-halts on political video clips</td>
                            <td>Ideological polarization tracking metrics</td>
                            <td>Dynamic attention retention silo allocation</td>
                        </tr>
                        <tr>
                            <td>Geo-coordinate clustering at 2:00 AM</td>
                            <td>Interpersonal proximity & association matrix</td>
                            <td>Predictive social network graph building</td>
                        </tr>
                    </tbody>
                </table>

                <h2 class="section-title">The Continuous Telemetry Loop</h2>
                <p>This data optimization cycle operates as a continuous, compounding loop. Every interaction feeds back into the neural network, shifting your position inside the vector space by fractions of a millimeter. The system systematically tracks where your coordinate drifts over time. If your vector begins moving closer to the cluster representing "early-stage clinical depression," the delivery engines adapt automatically, shifting the types of content, products, and notifications pushed to your device without ever explicitly being told you are struggling.</p>
            </div>

            <!-- ARTICLE 3: PSYCHOMETRIC OPPORTUNITY SCORING DOCUMENT -->
            <div id="deep-dive-2" class="content-view">
                <div class="meta-info">
                    <span class="category">Economic Policy</span>
                    <span>•</span><span>Corporate Audit</span>
                </div>
                <h1 class="article-title">The Invisible Gatekeepers: Psychometric Sorting in Private Infrastructure</h1>
                <p>The traditional concept of a credit score or an employment interview is dead. It has been replaced by passive, automated psychometric extraction frameworks that evaluate whether individuals are granted entry into fundamental layers of modern economic life.</p>
                <p>When you apply for housing, seek a prime loan tier, or upload a resume to an automated corporate tracking pipeline, proprietary algorithms evaluate your text syntax and interface mechanics to calculate an index score representing your **system compliance and institutional value**.</p>
                
                <h2 class="section-title">Algorithmic Risk Allocations</h2>
                <p>Modern insurance and employment algorithms frequently utilize specialized natural language processing (NLP) architectures to extract micro-behaviors. If an evaluation engine monitors an applicant completing an online application form, it tracks more than just the text entered. The code actively charts whether the user copies and pastes answers, how many times they delete characters before finalizing a sentence, and how long they spend reading the liability waivers.</p>
                <blockquote>
                    "By transforming human behavior into a predictive compliance index, algorithmic gating infrastructure creates a silent loop where past system discrepancies automatically lock down future class mobility."
                </blockquote>
                <p>The social outcome of this framework is a segmented opportunity grid. Individuals flagged with high-volatility scores are algorithmically routed away from human review pipelines and steered directly into higher-cost credit lines, high-turnover labor pools, or automated application rejection queues, leaving no structural pathway to appeal the computer's deterministic choice.</p>
            </div>

            <!-- ARTICLE 4: SPATIAL SURVEILLANCE CRITERIA DOCUMENT -->
            <div id="deep-dive-3" class="content-view">
                <div class="meta-info">
                    <span class="category">Geopolitics</span>
                    <span>•</span><span>Surveillance Studies</span>
                </div>
                <h1 class="article-title">Contiguous Tracking Rings: The End of Spatial Anonymity</h1>
                <p>Physical space has been digitized. Through the integration of computer-vision pipelines and distributed hardware nodes, urban centers and highway infrastructure now function as localized collection fields designed to read, timestamp, and catalog individual physical movement.</p>
                <p>Automated License Plate Readers (ALPR) combined with localized facial classification arrays construct a continuous tracking grid. This matrix maps the routes of millions of individuals, evaluating their movements against behavioral models designed to uncover systemic anomalies or unmapped personal connections.</p>
                
                <h2 class="section-title">The Logic of 'Convoy Analysis' and Associational Mapping</h2>
                <p>The primary value of these models is not tracking isolated targets, but calculating spatial intersections. Through mathematical models known as "convoy analysis," algorithms search through terabytes of location history to discover separate vehicles traveling along matching paths within specific windows of time.</p>
                <p>If two vehicles pass through three consecutive intersecting tracking grids across a city, the algorithm links their profiles inside a social graph database. This lets corporate or state actors build complete organizational networks of activist groups, political organizations, or personal circles without needing a warrant, eliminating the basic legal protection of public anonymity.</p>
            </div>

            <!-- ARTICLE 5: WEAPONIZATION & MISUSE DOSSIER -->
            <div id="deep-dive-4" class="content-view">
                <div class="meta-info">
                    <span class="category">Threat Intel</span>
                    <span>•</span><span>Risk Assessment</span>
                </div>
                <h1 class="article-title">The Weaponization Matrix: Asymmetric Misuse of Predictive ML Modeling</h1>
                <p>The danger of systemic algorithmic profiling does not conclude with aggressive targeted advertisements or skewed credit applications. When identical machine learning methodologies are intentionally decoupled from corporate compliance mandates, they transition into highly precise tools for political coercion, ideological purges, and automated state repression.</p>
                <p>Because these neural networks are optimized to map and exploit foundational human vulnerabilities, their misuse scales flawlessly under authoritarian regimes, bad-faith institutional actors, or weaponized intelligence operations.</p>
                
                <h2 class="section-title">1. Automated Dissident Identification & Preemptive Interdiction</h2>
                <p>In standard commercial applications, cluster analysis models look for high-affinity buyers. Transferred to a hostile state framework, those exact vector calculations isolate political anomalies. By cross-referencing encrypted communication patterns, structural linguistic variations, and geographic proximity scores, an adversarial AI can accurately identify anonymous whistleblowers, journalists, or human rights defenders.</p>
                <p>The paradigm shifts from reactive policing to **preemptive interdiction**. Autocratic states no longer wait for a protest to materialize; predictive models flag highly volatile nodes within a social network matrix, permitting security apparatuses to neutralize individuals before public descent ever reaches critical mass.</p>

                <h2 class="section-title">2. Asymmetric Cognitive Warfare & Engineered Destabilization</h2>
                <p>By mapping the psychological "Digital Twin" of entire populations down to individual vector coordinates, rogue psychological operations or intelligence cells can deploy personalized disinformation with precision accuracy. Rather than blanketing a nation with uniform propaganda, neural networks calculate the precise narrative required to polarize a specific subset of citizens.</p>
                
                <table class="analysis-table">
                    <thead>
                        <tr>
                            <th>Exploited Vector Asset</th>
                            <th>Sinister Mechanism</th>
                            <th>Systemic Societal Impact</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>Inferred Grief / Trauma Coordinates</td>
                            <td>Dynamic radicalization funnel injection</td>
                            <td>Rapid incubation of domestic extremist cells</td>
                        </tr>
                        <tr>
                            <td>Socio-Economic Despair Index</td>
                            <td>Targeted amplify-and-blame content cycles</td>
                            <td>Systematic erosion of institutional trust</td>
                        </tr>
                        <tr>
                            <td>Inter-ethnic Friction Proximity</td>
                            <td>Micro-targeted synthetic outrage loops</td>
                            <td>Engineered civil conflict & violent escalation</td>
                        </tr>
                    </tbody>
                </table>

                <h2 class="section-title">3. Algorithmic Blacklisting & Digital Extinction</h2>
                <p>When private monopolies or state entities integrate automated profiling into fundamental utilities—like access to digital payment rails, healthcare networks, or communication protocols—the profile itself becomes a weapon of compliance. A machine learning model can execute a silent, continuous purge by shifting the access tiers of individuals flagged as "ideologically non-compliant."</p>
                <blockquote>
                    "The ultimate iteration of weaponized AI profiling is the total deletion of an individual's digital viability. Without ever filing charges or declaring an arrest, a system can render a target structurally invisible—cutting off finances, connectivity, and mobility by deterministic decree."
                </blockquote>
                <p>This reality bypasses judicial overwatch entirely. Because the optimization mechanisms are protected as proprietary intellectual property or state secrets, the target remains caught in a loop of automated denials, struggling to appeal a verdict generated by an un-auditable sequence of algorithmic weight distributions.</p>
            </div>

            <!-- EDITORIAL INTENT / ABOUT PAGE -->
            <div id="about-page" class="content-view">
                <div class="meta-info">
                    <span class="category">Masthead</span>
                    <span>•</span><span>Editorial Policy</span>
                </div>
                <h1 class="article-title">About Algorithmic Lens</h1>
                <p>Algorithmic Lens is an independent editorial repository and analysis project dedicated to tracking the sociological, economic, and philosophical impacts of advanced automation networks and machine learning architectures.</p>
                <p>Our work focuses on translating complex data sciences, database configurations, and tracking infrastructure mechanics into clear, accessible documentation. We believe citizens have an essential right to understand the algorithmic equations used to profile, evaluate, and categorize their place in modern society.</p>
                <h2 class="section-title">Editorial Standards & Accountability</h2>
                <p>All analysis published on this platform is thoroughly cross-referenced against public patent registries, academic security audits, and verified technical documentation from software deployment pipelines. We maintain full editorial independence and present all research solely for public educational and historical purposes.</p>
            </div>

        </main>

        <!-- Sidebar Navigation Rack -->
        <div class="sidebar-wrapper">
            <nav class="sidebar-menu">
                <h2>Research Dossiers</h2>
                <a onclick="showArticle('main-essay')" class="article-link active" id="link-main-essay">1. Framework Overview</a>
                <a onclick="showArticle('deep-dive-1')" class="article-link" id="link-deep-dive-1">2. Reverse-Engineering Vectors</a>
                <a onclick="showArticle('deep-dive-2')" class="article-link" id="link-deep-dive-2">3. Psychometric Sorting Tiers</a>
                <a onclick="showArticle('deep-dive-3')" class="article-link" id="link-deep-dive-3">4. Spatial Tracking Rings</a>
                <a onclick="showArticle('deep-dive-4')" class="article-link" id="link-deep-dive-4">5. The Weaponization Matrix</a>
            </nav>

            <div class="adsense-placeholder ad-sidebar">
                <span>Advertisement - Desktop Sidebar (300x600)</span>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2026 Algorithmic Lens. Published for editorial and analytical reporting purposes.</p>
        <nav>
            <button onclick="openModal('privacy-modal')">Privacy Policy</button>
            <button onclick="openModal('terms-modal')">Terms of Service</button>
        </nav>
    </footer>

    <!-- Mandatory AdSense Privacy Modal -->
    <div id="privacy-modal" class="modal">
        <div class="modal-content">
            <button class="close-btn" onclick="closeModal('privacy-modal')">&times;</button>
            <h3>Privacy Policy</h3>
            <br>
            <p>At Algorithmic Lens, we respect your privacy. This website displays advertisements via third-party vendors, including Google AdSense. Google uses cookies to serve ads based on a user's prior visits to this website or other websites on the Internet.</p>
            <p>Google's use of advertising cookies enables it and its partners to serve ads to users based on their visit to this site and/or other sites on the Internet. Users may opt out of personalized advertising by visiting Ads Settings in their respective Google profiles.</p>
        </div>
    </div>

    <!-- Mandatory AdSense Terms Modal -->
    <div id="terms-modal" class="modal">
        <div class="modal-content">
            <button class="close-btn" onclick="closeModal('terms-modal')">&times;</button>
            <h3>Terms of Service</h3>
            <br>
            <p>Welcome to Algorithmic Lens. The essays, documentation, and analysis found on this platform are served entirely for educational, historical, and general informational objectives.</p>
            <p>By interacting with this domain, you accept our standard terms of distribution. All analysis is the editorial property of this publication and cannot be mirrored or republished commercially without written authorization.</p>
        </div>
    </div>

    <script>
        function showArticle(articleId) {
            document.querySelectorAll('.content-view').forEach(view => {
                view.classList.remove('active');
            });
            
            document.querySelectorAll('.article-link').forEach(link => {
                link.classList.remove('active');
            });

            document.getElementById('nav-home').classList.remove('active');
            document.getElementById('nav-about').classList.remove('active');

            const targetView = document.getElementById(articleId);
            if(targetView) {
                targetView.classList.add('active');
            }

            const targetSidebarLink = document.getElementById(`link-${articleId}`);
            if(targetSidebarLink) {
                targetSidebarLink.classList.add('active');
            }

            if(articleId === 'main-essay') {
                document.getElementById('nav-home').classList.add('active');
            } else if(articleId === 'about-page') {
                document.getElementById('nav-about').classList.add('active');
            }

            window.scrollTo({ top: 0, behavior: 'smooth' });
        }

        function openModal(id) { document.getElementById(id).style.display = 'flex'; }
        function closeModal(id) { document.getElementById(id).style.display = 'none'; }
        
        window.onclick = function(event) {
            if (event.target.classList.contains('modal')) {
                event.target.style.display = 'none';
            }
        }
    </script>
</body>
</html>
