<script>
    import profile from '$lib/images/profile.webp';
    import Available from '$lib/components/Available.svelte';
	import About from '$lib/components/About.svelte';
</script>

<svelte:head>
    <title>Walter O'Brien</title>
</svelte:head>

<main>
    <div class="left-column">
        <div class="left-inner-top">
            <Available />
            <About />
        </div>
        <div class="left-inner-bottom">

        </div>
    </div>

    <div class="right-column">
        <div class="right-inner-top">

        </div>
        <div class="right-inner-middle">

        </div>
        <div class="right-inner-bottom">

        </div>
    </div>

</main>

<style>
    .left-column {
        display: flex;
        flex-direction: column;
        gap: 1rem;
        width: 66.67%;
    }

    .left-inner-top {
        display: flex;
        flex-direction: row;
    }
</style>

<!--
    <section id="opening" class="color-primary">
        <div class="text">
            <h1>Hi, I'm Walter O'Brien!</h1>
            <h2>Founder and CEO of Scorpion Computer Services</h2>
            <a class="link-primary" target="_blank" href="https://github.com/appwrite/appwrite">Visit my GitHub</a>
        </div>
        <div class="picture">
            <img src={profile} width="300" height="auto" alt="Profile picture of Walter O'Brien from the show, Scorpion">
        </div>
    </section>
    <section id="about" class="color-secondary">
        <h2>About Me</h2>
        <ul class="about-content">
            <li>Renowned technology expert and entrepreneur with an <strong>IQ of 197</strong>, among the highest recorded globally</li>
            <li><strong>Founded Scorpion Computer Services</strong> to provide cybersecurity, AI-driven solutions, and high-level consulting</li>
            <li><strong>Hacked NASA's servers at age 13</strong>, showcasing early technical prowess</li>
            <li>Contributed strategic insights on security and technology challenges to <strong>private and governmental organizations worldwide</strong></li>
        </ul>
        <h3>Skills</h3>
        <ul class="skills">
            <li>Artificial Intelligence (AI)</li>
            <li>Machine Learning (ML)</li>
            <li>Cybersecurity</li>
            <li>Cryptography</li>
            <li>Network Engineering</li>
            <li>Enterprise Software Development</li>
            <li>Risk Management</li>
        </ul>
    </section>
    <section id="jobs" class="color-primary">
        <h2>Work Experience</h2>
        <div class="job">
            <h3>Scorpion Computer Services (CEO)</h3>
            <p>Timeframe: <em>1998 - Present</em></p>
            <ul>
                <li>Founded and grew Scorpion into a global consulting firm.</li>
                <li>Provides high-stakes problem-solving for Fortune 500 companies and government agencies.</li>
                <li>Develops AI-driven solutions for complex technology, security, and engineering challenges.</li>
            </ul>
            <p><em>Relevant Skills: Artificial Intelligence (AI), Cybersecurity, Network Engineering, Cryptography</em></p>
        </div>
        <div class="job">
            <h3>Think Tank Contributor</h3>
            <p>Timeframe: <em>Various projects</em></p>
            <ul>
                <li>Supports private and public sectors with high-level policy and strategy contributions.</li>
                <li>Advises on strengthening security measures and technological infrastructure for large organizations.</li>
            </ul>
            <p><em>Relevant Skills: Cybersecurity, AI Strategy, Risk Management</em></p>
        </div>
        <div class="job">
            <h3>Cybersecurity and Intelligence Advisor</h3>
            <p>Timeframe: <em>Various projects</em></p>
            <ul>
                <li>Advises on cybersecurity strategies for military and governmental entities.</li>
                <li>Protects sensitive data by developing advanced strategies to counteract cyber threats.</li>
            </ul>
            <p><em>Relevant Skills: Cryptography, Threat Detection</em></p>
        </div>
    </section>
    <section id="projects" class="color-secondary">
        <h2>Projects</h2>
        <div class="card-container">
            <div class="card">
                <h3>ScenGen (Scenario Generator)</h3>
                <p>An AI-powered scenario generation engine that predicts outcomes in complex problem spaces, used across sectors like cybersecurity and healthcare.</p>
                <p><em>Tech Stack: Artificial Intelligence, Machine Learning, Data Analysis</em></p>
                <a class="link-secondary" target="_blank" href="https://appwrite.io">View the project</a>
            </div>
            <div class="card">
                <h3>Risk Management Platform</h3>
                <p>A comprehensive risk assessment tool created for financial and defense industries, designed to enhance decision-making and improve security resilience.</p>
                <p><em>Tech Stack: Data Analysis, Predictive Modeling, Enterprise Software</em></p>
                <a class="link-secondary" target="_blank" href="https://appwrite.io">View the project</a>
            </div>
            <div class="card">
                <h3>ConciergeUp Intelligence-as-a-Service</h3>
                <p>An on-demand problem-solving service offering personalized technical and strategic solutions for diverse client challenges.</p>
                <p><em>Tech Stack: Machine Learning, Enterprise Software Development, Data Analysis</em></p>
                <a class="link-secondary" target="_blank" href="https://appwrite.io">View the project</a>
            </div>
        </div>
    </section>        
    <section id="blogs" class="color-primary"> 
        <h2>Blogs</h2>
        <div class="card-container">
            <div class="card">
                <h3>The Role of AI in Modern Security Solutions</h3>
                <p>Exploring how AI is transforming cybersecurity and how businesses can leverage it to stay ahead of threats.</p>
                <a class="link-secondary" target="_blank" href="https://appwrite.io/blog">Read More</a>
            </div>
            <div class="card">
                <h3>High-Stakes Problem Solving: Lessons from Scorpion</h3>
                <p>An insight into problem-solving techniques used by Scorpion in high-risk scenarios and complex projects.</p>
                <a class="link-secondary" target="_blank" href="https://appwrite.io/blog">Read More</a>
            </div>
            <div class="card">
                <h3>How Scenario Generation Can Predict Outcomes</h3>
                <p>A dive into the ScenGen project and how scenario generation helps anticipate solutions to intricate challenges.</p>
                <a class="link-secondary" target="_blank" href="https://appwrite.io/blog">Read More</a>
            </div>
            <div class="card">
                <h3>The Future of AI and Human Collaboration</h3>
                <p>Discussing the potential of AI to complement human intelligence in tackling complex societal issues.</p>
                <a class="link-secondary" target="_blank" href="https://appwrite.io/blog">Read More</a>
            </div>
            <div class="card">
                <h3>Cybersecurity in an Evolving Digital Landscape</h3>
                <p>Strategies for staying protected as digital threats evolve, from threat detection to proactive security measures.</p>
                <a class="link-secondary" target="_blank" href="https://appwrite.io/blog">Read More</a>
            </div>
        </div>
    </section>        
    <section id="contact" class="color-secondary">
        <h2>Contact Me</h2>
        <p>Feel free to reach out to me if you have any questions or would like to connect!</p>
        <ul>
            <li><a class="link-primary" target="_blank" href="https://x.com/appwrite">X</a></li>
            <li><a class="link-primary" target="_blank" href="https://www.linkedin.com/company/appwrite">LinkedIn</a></li>
        </ul>
    </section>
    <footer class="color-primary">
        <h2>Try Appwrite Cloud</h2>
        <ul>
            <li><a class="link-primary" target="_blank" href="https://cloud.appwrite.io">Sign Up</a></li>
            <li><a class="link-primary" target="_blank" href="https://appwrite.io/docs">Read Docs</a></li>
            <li><a class="link-primary" target="_blank" href="http://appwrite.io/discord">Join Discord</a></li>
        </ul>
    </footer>
</main>
-->
