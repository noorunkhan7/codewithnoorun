
<style>
* { box-sizing: border-box; margin: 0; padding: 0; }
.profile { max-width: 720px; padding: 1.5rem 0; font-family: var(--font-sans); }
.header { display: flex; align-items: center; gap: 20px; margin-bottom: 1.5rem; }
.avatar { width: 72px; height: 72px; border-radius: 50%; background: #EEEDFE; display: flex; align-items: center; justify-content: center; font-size: 26px; font-weight: 500; color: #3C3489; flex-shrink: 0; border: 0.5px solid #AFA9EC; }
.name { font-size: 22px; font-weight: 500; color: var(--color-text-primary); }
.title { font-size: 14px; color: var(--color-text-secondary); margin-top: 3px; }
.badges { display: flex; gap: 8px; margin-top: 8px; flex-wrap: wrap; }
.badge { font-size: 12px; padding: 3px 10px; border-radius: 99px; border: 0.5px solid; }
.badge-purple { background: #EEEDFE; color: #3C3489; border-color: #AFA9EC; }
.badge-teal { background: #E1F5EE; color: #0F6E56; border-color: #5DCAA5; }
.social-links { display: flex; gap: 10px; margin-bottom: 1.5rem; flex-wrap: wrap; }
.social-btn { font-size: 13px; padding: 6px 14px; border-radius: var(--border-radius-md); border: 0.5px solid var(--color-border-secondary); color: var(--color-text-secondary); text-decoration: none; display: flex; align-items: center; gap: 6px; background: var(--color-background-secondary); }
.section { margin-bottom: 1.5rem; }
.section-title { font-size: 13px; font-weight: 500; color: var(--color-text-secondary); text-transform: uppercase; letter-spacing: 0.06em; margin-bottom: 10px; }
.about-card { background: var(--color-background-secondary); border-radius: var(--border-radius-lg); padding: 1rem 1.25rem; border: 0.5px solid var(--color-border-tertiary); }
.about-row { display: flex; gap: 10px; align-items: flex-start; padding: 5px 0; font-size: 14px; color: var(--color-text-primary); line-height: 1.5; }
.about-icon { font-size: 16px; flex-shrink: 0; margin-top: 1px; }
.tech-grid { display: grid; grid-template-columns: repeat(3, minmax(0, 1fr)); gap: 10px; }
.tech-card { background: var(--color-background-primary); border: 0.5px solid var(--color-border-tertiary); border-radius: var(--border-radius-lg); padding: 0.75rem 1rem; }
.tech-label { font-size: 11px; font-weight: 500; color: var(--color-text-secondary); text-transform: uppercase; letter-spacing: 0.05em; margin-bottom: 8px; }
.tech-tags { display: flex; flex-wrap: wrap; gap: 5px; }
.tag { font-size: 12px; padding: 2px 8px; border-radius: 4px; background: var(--color-background-secondary); color: var(--color-text-primary); border: 0.5px solid var(--color-border-tertiary); }
.projects { display: flex; flex-direction: column; gap: 8px; }
.proj-card { background: var(--color-background-primary); border: 0.5px solid var(--color-border-tertiary); border-radius: var(--border-radius-lg); padding: 0.875rem 1.1rem; display: flex; gap: 12px; align-items: flex-start; }
.proj-icon { width: 36px; height: 36px; border-radius: var(--border-radius-md); display: flex; align-items: center; justify-content: center; font-size: 16px; flex-shrink: 0; }
.proj-name { font-size: 14px; font-weight: 500; color: var(--color-text-primary); margin-bottom: 3px; }
.proj-desc { font-size: 13px; color: var(--color-text-secondary); line-height: 1.5; }
.highlight { background: #E1F5EE; color: #085041; border: 0.5px solid #5DCAA5; border-radius: 99px; font-size: 11px; padding: 2px 8px; display: inline-block; margin-top: 4px; }

.trophy-grid { display: grid; grid-template-columns: repeat(3, minmax(0, 1fr)); gap: 10px; }
.trophy-card { border-radius: var(--border-radius-lg); padding: 0.875rem 0.75rem; text-align: center; border: 0.5px solid; display: flex; flex-direction: column; align-items: center; gap: 6px; }
.trophy-icon { font-size: 28px; line-height: 1; }
.trophy-name { font-size: 12px; font-weight: 500; line-height: 1.3; }
.trophy-sub { font-size: 11px; opacity: 0.75; }
.t-gold { background: #FAEEDA; border-color: #EF9F27; color: #633806; }
.t-silver { background: #F1EFE8; border-color: #B4B2A9; color: #2C2C2A; }
.t-purple { background: #EEEDFE; border-color: #AFA9EC; color: #26215C; }
.t-teal { background: #E1F5EE; border-color: #5DCAA5; color: #04342C; }
.t-blue { background: #E6F1FB; border-color: #85B7EB; color: #042C53; }
.t-coral { background: #FAECE7; border-color: #F0997B; color: #4A1B0C; }
</style>

<div class="profile">
  <div class="header">
    <div class="avatar">NFK</div>
    <div>
      <div class="name">Noorun Fatima Khan</div>
      <div class="title">Data Science Enthusiast · MERN Stack Developer</div>
      <div class="badges">
        <span class="badge badge-purple">Top 10 · Smart India Hackathon</span>
        <span class="badge badge-teal">Open to opportunities</span>
      </div>
    </div>
  </div>

  <div class="social-links">
    <a class="social-btn" href="https://linkedin.com/in/noorun-khan-5917a324b">&#128101; LinkedIn</a>
    <a class="social-btn" href="mailto:noorun.22jdds002@jietjodhpur.ac.in">&#9993; Email</a>
    <a class="social-btn" href="https://github.com/noorunkhan7">&#128736; GitHub</a>
  </div>

  <div class="section">
    <div class="section-title">About</div>
    <div class="about-card">
      <div class="about-row"><span class="about-icon">&#128300;</span><span>Data Analytics Intern at <strong>Labmentix</strong></span></div>
      <div class="about-row"><span class="about-icon">&#128188;</span><span>Previously ML Intern at <strong>DRDO</strong> &amp; Full Stack Intern at <strong>WsCube Tech</strong></span></div>
      <div class="about-row"><span class="about-icon">&#128172;</span><span>Ask me about Data Analysis, React.js, Python, or API Design</span></div>
      <div class="about-row"><span class="about-icon">&#9889;</span><span>Writes code to lofi music</span></div>
    </div>
  </div>

  <div class="section">
    <div class="section-title">&#127942; GitHub trophies</div>
    <div class="trophy-grid">
      <div class="trophy-card t-gold">
        <div class="trophy-icon">&#127942;</div>
        <div class="trophy-name">Multi Language</div>
        <div class="trophy-sub">Python · JS · C++ · Java</div>
      </div>
      <div class="trophy-card t-purple">
        <div class="trophy-icon">&#11088;</div>
        <div class="trophy-name">Stars</div>
        <div class="trophy-sub">Starred repositories</div>
      </div>
      <div class="trophy-card t-teal">
        <div class="trophy-icon">&#128200;</div>
        <div class="trophy-name">Commits</div>
        <div class="trophy-sub">Consistent contributor</div>
      </div>
      <div class="trophy-card t-blue">
        <div class="trophy-icon">&#128268;</div>
        <div class="trophy-name">Followers</div>
        <div class="trophy-sub">Growing network</div>
      </div>
      <div class="trophy-card t-coral">
        <div class="trophy-icon">&#128187;</div>
        <div class="trophy-name">Repositories</div>
        <div class="trophy-sub">Public projects</div>
      </div>
      <div class="trophy-card t-silver">
        <div class="trophy-icon">&#128640;</div>
        <div class="trophy-name">Pull Requests</div>
        <div class="trophy-sub">Open source contributions</div>
      </div>
    </div>
  </div>

  <div class="section">
    <div class="section-title">Tech stack</div>
    <div class="tech-grid">
      <div class="tech-card">
        <div class="tech-label">Languages</div>
        <div class="tech-tags">
          <span class="tag">Python</span><span class="tag">JavaScript</span><span class="tag">C++</span><span class="tag">Java</span><span class="tag">C</span>
        </div>
      </div>
      <div class="tech-card">
        <div class="tech-label">Web</div>
        <div class="tech-tags">
          <span class="tag">React</span><span class="tag">Node.js</span><span class="tag">Express</span><span class="tag">MongoDB</span>
        </div>
      </div>
      <div class="tech-card">
        <div class="tech-label">Data & ML</div>
        <div class="tech-tags">
          <span class="tag">TensorFlow</span><span class="tag">OpenCV</span><span class="tag">Pandas</span><span class="tag">NumPy</span><span class="tag">Power BI</span><span class="tag">Tableau</span><span class="tag">MySQL</span>
        </div>
      </div>
    </div>
  </div>

  <div class="section">
    <div class="section-title">Top projects</div>
    <div class="projects">
      <div class="proj-card">
        <div class="proj-icon" style="background:#EEEDFE;">&#9995;</div>
        <div>
          <div class="proj-name">Hand sign recognition system</div>
          <div class="proj-desc">Real-time gesture recognition using Python, OpenCV, and MediaPipe.</div>
          <span class="highlight">Computer Vision</span>
        </div>
      </div>
      <div class="proj-card">
        <div class="proj-icon" style="background:#FAECE7;">&#128200;</div>
        <div>
          <div class="proj-name">Cancer detection system</div>
          <div class="proj-desc">ML model with TensorFlow &amp; Scikit-learn for early-stage cancer classification.</div>
          <span class="highlight">Machine Learning</span>
        </div>
      </div>
      <div class="proj-card">
        <div class="proj-icon" style="background:#EAF3DE;">&#127807;</div>
        <div>
          <div class="proj-name">Plant disease detection</div>
          <div class="proj-desc">AI-based computer vision system for agricultural disease diagnosis.</div>
          <span class="highlight">Computer Vision · AI</span>
        </div>
      </div>
    </div>
  </div>

  <div style="font-size: 12px; color: var(--color-text-secondary); text-align: center; padding-top: 0.5rem;">Crafted with care by Noorun Fatima Khan</div>
</div>
