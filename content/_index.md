---
title:
date: 2026-04-26
type: landing

sections:

  # =========================================================
  # HERO GRAPHIC
  # =========================================================

  - block: markdown
    content:
      title:
      subtitle: ''
      text: |
        <div class="arc-home-hero-graphic">
          <img
            src="https://arcorrectionslab.org/img/animated_curve_blue.gif"
            alt="Animated ARC Lab graphic"
          >
        </div>
    design:
      columns: '1'
      css_class: arc-home-hero
      spacing:
        padding: ['0', '0', '20px', '0']


  # =========================================================
  # INTRO
  # =========================================================

  - block: markdown
    content:
      title:
      subtitle: ''
      text: |

        <div class="arc-home-intro">

          <div class="arc-home-intro-inner">

            <p>
              The Advancing Research in Corrections (ARC) Lab, based in the
              <a href="https://www.unomaha.edu/college-of-public-affairs-and-community-service/criminology-and-criminal-justice/index.php">
                UNO School of Criminology and Criminal Justice
              </a>,
              conducts applied and theoretical research on institutional corrections,
              community corrections, and reentry.
            </p>

            <p>
              Our work focuses on analyzing real-world correctional systems using
              rigorous quantitative and qualitative methods. Rather than studying
              policy in the abstract, we examine how policies, practices, and
              programs function in context, using data to evaluate outcomes,
              identify gaps, and inform more effective, equitable, and transparent
              approaches to corrections.
            </p>

            <div class="arc-home-actions">

              <a
                href="/publication/"
                class="arc-home-button arc-home-button-primary"
              >
                Explore Our Research
              </a>

              <a
                href="/people/"
                class="arc-home-button arc-home-button-secondary"
              >
                Meet the Lab
              </a>

            </div>

            <img
              src="/media/arclogo_aardvark.png"
              alt="ARC Lab logo"
              class="arc-home-aardvark"
            >

          </div>

        </div>


        <style>

        /* =====================================================
           HERO
        ===================================================== */

        .arc-home-hero-graphic {
          width: 100%;
          margin: 0;
          padding: 0;
        }

        .arc-home-hero-graphic img {
          display: block;
          width: 100%;
          max-width: 100%;
          height: auto;
          margin: 0 auto;
        }


        /* =====================================================
           INTRO
        ===================================================== */

        .arc-home-intro {
          padding: 2.75rem 1rem 3.25rem;
        }

        .arc-home-intro-inner {
          max-width: 900px;
          margin: 0 auto;
          text-align: center;
        }

        .arc-home-intro p {
          max-width: 820px;

          margin-left: auto;
          margin-right: auto;

          color: #c3cfdd;

          font-size: 1rem;
          line-height: 1.75;
        }


        /* =====================================================
           BUTTONS
        ===================================================== */

        .arc-home-actions {
          display: flex;

          justify-content: center;

          gap: 0.75rem;

          flex-wrap: wrap;

          margin-top: 1.75rem;
        }

        .arc-home-button {
          display: inline-flex;

          align-items: center;
          justify-content: center;

          min-height: 42px;

          padding: 0.65rem 1rem;

          border-radius: 5px;

          font-size: 0.9rem;
          font-weight: 800;
          line-height: 1.2;

          text-decoration: none !important;

          transition:
            background 0.15s ease,
            border-color 0.15s ease,
            color 0.15s ease,
            transform 0.15s ease;
        }

        .arc-home-button-primary {
          background: #315f8f;

          color: #ffffff !important;

          border: 1px solid #4e7eae;
        }

        .arc-home-button-primary:hover {
          background: #3d73a8;

          border-color: #69a0d2;

          color: #ffffff !important;

          transform: translateY(-1px);
        }

        .arc-home-button-secondary {
          background: transparent;

          color: #7fc8e8 !important;

          border: 1px solid #526b89;
        }

        .arc-home-button-secondary:hover {
          background: rgba(45, 212, 191, 0.08);

          border-color: #2dd4bf;

          color: #5eead4 !important;

          transform: translateY(-1px);
        }


        /* =====================================================
           LOGO
        ===================================================== */

        .arc-home-aardvark {
          display: block;

          width: 150px;
          max-width: 100%;

          height: auto;

          margin: 2rem auto 0;

          opacity: 0.95;

          border-radius: 10px;
        }


        /* =====================================================
           COMMON EDITORIAL
        ===================================================== */

        .arc-editorial-heading {
          margin: 0 0 0.5rem;

          color: #f1f5f9;

          font-size: 1.85rem;

          font-weight: 800;

          line-height: 1.2;

          text-align: center;
        }

        .arc-editorial-rule {
          width: 34px;

          height: 2px;

          margin: 0.65rem auto 1.75rem;

          background: #2dd4bf;

          border-radius: 999px;
        }


        /* =====================================================
           TEAM
        ===================================================== */

        .arc-team-section {
          max-width: 1050px;

          margin: 0 auto;

          padding: 3rem 1rem 3.25rem;
        }

        .arc-team-layout {
          display: grid;

          grid-template-columns:
            minmax(0, 1.35fr)
            minmax(320px, 0.65fr);

          gap: 2.5rem;

          align-items: center;
        }

        .arc-team-image {
          display: block;

          width: 100%;

          height: auto;

          border-radius: 12px;

          box-shadow:
            0 8px 24px rgba(0, 0, 0, 0.18);
        }

        .arc-team-copy {
          color: #c3cfdd;

          font-size: 0.98rem;

          line-height: 1.75;
        }

        .arc-team-copy p {
          margin: 0 0 1rem;
        }

        .arc-inline-link {
          color: #7fc8e8 !important;

          font-weight: 700;

          text-decoration: none !important;
        }

        .arc-inline-link:hover {
          color: #2dd4bf !important;
        }


        /* =====================================================
           COLLABORATION
        ===================================================== */

        .arc-collab-section {
          max-width: 900px;

          margin: 0 auto;

          padding: 3rem 1rem 3.25rem;
        }

        .arc-collab-copy {
          margin: 0;

          padding-left: 1.25rem;

          border-left: 2px solid #2dd4bf;

          color: #c3cfdd;

          font-size: 1rem;

          line-height: 1.8;
        }

        .arc-collab-copy p {
          margin: 0 0 1rem;
        }

        .arc-collab-copy p:last-child {
          margin-bottom: 0;
        }

        .arc-collab-copy a {
          color: #7fc8e8 !important;

          text-decoration: none !important;
        }

        .arc-collab-copy a:hover {
          color: #2dd4bf !important;
        }


        /* =====================================================
           NEWS
        ===================================================== */

        .arc-news-section {
          max-width: 1050px;

          margin: 0 auto;

          padding: 3rem 1rem 3.5rem;
        }

        .arc-news-header {
          display: flex;

          justify-content: space-between;

          align-items: baseline;

          gap: 1rem;

          margin-bottom: 1.4rem;
        }

        .arc-news-header h2 {
          margin: 0;

          color: #f1f5f9;

          font-size: 1.8rem;

          font-weight: 800;
        }

        .arc-news-more {
          color: #7fc8e8 !important;

          font-size: 0.9rem;

          font-weight: 700;

          text-decoration: none !important;

          white-space: nowrap;
        }

        .arc-news-more:hover {
          color: #2dd4bf !important;
        }

        .arc-news-list {
          border-top:
            1px solid #33465f;
        }

        .arc-news-item {
          display: grid;

          grid-template-columns:
            92px minmax(0, 1fr);

          column-gap:
            1.25rem;

          padding:
            0.9rem 0;

          border-bottom:
            1px solid rgba(51, 70, 95, 0.68);
        }

        .arc-news-date {
          color: #5eead4;

          font-size:
            0.8rem;

          font-weight:
            800;

          line-height:
            1.4;

          letter-spacing:
            0.04em;

          text-transform:
            uppercase;
        }

        .arc-news-title {
          margin:
            0 0 0.22rem;

          color:
            #d9e8f5;

          font-size:
            1rem;

          font-weight:
            700;

          line-height:
            1.45;
        }

        .arc-news-title a {
          color:
            inherit !important;

          text-decoration:
            none !important;
        }

        .arc-news-title a:hover {
          color:
            #7fc8e8 !important;
        }

        .arc-news-description {
          margin:
            0;

          color:
            #9aa8bd;

          font-size:
            0.88rem;

          line-height:
            1.5;
        }


        /* =====================================================
           PROJECTS
        ===================================================== */

        .homepage-featured {
          max-width:
            1100px;

          margin:
            0 auto;

          padding:
            3rem 1rem 3.5rem;
        }

        .homepage-section-header {
          display:
            flex;

          justify-content:
            space-between;

          align-items:
            baseline;

          gap:
            1rem;

          margin-bottom:
            1.5rem;
        }

        .homepage-section-header h2 {
          margin:
            0;

          color:
            #f1f5f9;

          font-size:
            1.8rem;

          font-weight:
            800;
        }

        .homepage-section-link {
          color:
            #7fc8e8 !important;

          font-size:
            0.9rem;

          font-weight:
            700;

          text-decoration:
            none !important;
        }

        .homepage-section-link:hover {
          color:
            #2dd4bf !important;
        }


        .homepage-card-grid {
          display:
            grid;

          gap:
            1.5rem;
        }

        .homepage-card-grid-3 {
          grid-template-columns:
            repeat(3, minmax(0, 1fr));
        }

        .homepage-card {
          position:
            relative;

          background:
            linear-gradient(
              145deg,
              #1a2940 0%,
              #0f1622 100%
            );

          border:
            1px solid #33465f;

          border-radius:
            12px;

          overflow:
            hidden;

          box-shadow:
            0 8px 24px rgba(0, 0, 0, 0.18);

          transition:
            transform 0.2s ease,
            border-color 0.2s ease,
            box-shadow 0.2s ease;
        }

        .homepage-card::before {
          content:
            "";

          position:
            absolute;

          top:
            0;

          left:
            0;

          right:
            0;

          height:
            4px;

          background:
            linear-gradient(
              90deg,
              #3b82f6 0%,
              #2dd4bf 100%
            );

          z-index:
            2;
        }

        .homepage-card:hover {
          transform:
            translateY(-4px);

          border-color:
            #526b89;

          box-shadow:
            0 14px 30px rgba(0, 0, 0, 0.28);
        }

        .homepage-card-link {
          display:
            block;

          color:
            inherit !important;

          text-decoration:
            none !important;
        }

        .homepage-card-link img {
          display:
            block;

          width:
            100%;

          height:
            205px;

          object-fit:
            cover;
        }

        .homepage-card-body {
          padding:
            1.15rem 1.15rem 1.35rem;
        }

        .homepage-card-kicker {
          margin:
            0 0 0.4rem;

          color:
            #5eead4;

          font-size:
            0.75rem;

          font-weight:
            800;

          letter-spacing:
            0.07em;

          text-transform:
            uppercase;
        }

        .homepage-card h3 {
          margin:
            0 0 0.55rem;

          color:
            #d9e8f5;

          font-size:
            1.12rem;

          font-weight:
            700;

          line-height:
            1.35;
        }

        .homepage-card-body > p:last-child {
          margin:
            0;

          color:
            #9aa8bd;

          font-size:
            0.9rem;

          line-height:
            1.55;
        }


        /* =====================================================
           RESPONSIVE
        ===================================================== */

        @media (max-width: 850px) {

          .arc-team-layout {
            grid-template-columns:
              1fr;
          }

          .homepage-card-grid-3 {
            grid-template-columns:
              1fr;
          }

        }

        @media (max-width: 650px) {

          .arc-news-header,
          .homepage-section-header {
            align-items:
              flex-start;

            flex-direction:
              column;

            gap:
              0.4rem;
          }

          .arc-news-item {
            grid-template-columns:
              72px minmax(0, 1fr);

            column-gap:
              0.85rem;
          }

        }

        </style>

    design:
      columns: '1'
      css_class: homepage-intro
      spacing:
        padding: ['40px', '0', '40px', '0']


  # =========================================================
  # WHAT WE STUDY
  # =========================================================

  - block: markdown
    content:
      title:
      subtitle: ''
      text: |
        {{< study-grid >}}
    design:
      columns: '1'
      css_class: homepage-study
      spacing:
        padding: ['40px', '0', '48px', '0']


  # =========================================================
  # THE ARC LAB TEAM
  # =========================================================

  - block: markdown
    content:
      title:
      subtitle: ''
      text: |

        <div class="arc-team-section">

          <h2 class="arc-editorial-heading">
            The ARC Lab Team
          </h2>

          <div class="arc-editorial-rule"></div>

          <div class="arc-team-layout">

            <div>

              <img
                src="/media/homyphoto_edited2.jpg"
                alt="ARC Lab group photo"
                class="arc-team-image"
              >

            </div>

            <div class="arc-team-copy">

              <p>
                ARC brings together faculty, research staff, and graduate
                researchers working on shared questions about correctional
                policy, practice, and outcomes. The lab operates as a
                collaborative research environment where projects are developed,
                analyzed, and carried forward across teams.
              </p>

              <p>
                Lab members contribute to ongoing research, engage with applied
                data, and participate in work that connects academic research
                to policy and practice in corrections.
              </p>

              <p>
                <a
                  href="/people/"
                  class="arc-inline-link"
                >
                  Meet the team →
                </a>
              </p>

            </div>

          </div>

        </div>
    design:
      columns: '1'
      css_class: homepage-team
      spacing:
        padding: ['40px', '0', '48px', '0']


  # =========================================================
  # RESEARCH & COLLABORATION
  # =========================================================

  - block: markdown
    content:
      title:
      subtitle: ''
      text: |

        <div class="arc-collab-section">

          <h2 class="arc-editorial-heading">
            Research &amp; Collaboration
          </h2>

          <div class="arc-editorial-rule"></div>

          <div class="arc-collab-copy">

            <p>
              ARC works closely with SCCJ faculty, the
              <a href="https://www.unomaha.edu/college-of-public-affairs-and-community-service/nebraska-center-for-justice-research/index.php">
                Nebraska Center for Justice Research (NCJR)
              </a>,
              the
              <a href="https://www.unomaha.edu/college-of-public-affairs-and-community-service/juvenile-justice-institute/index.php">
                Juvenile Justice Institute (JJI)
              </a>,
              and a range of community, state, and federal partners. These
              collaborations allow the lab to conduct research using
              administrative data, collect primary data, evaluate active
              programs, and contribute to ongoing policy discussions.
            </p>

            <p>
              Graduate students in the lab are involved in this work as part of
              ongoing projects, gaining experience with applied data, research
              design, and evaluation in real-world correctional contexts.
            </p>

          </div>

        </div>
    design:
      columns: '1'
      css_class: homepage-collaboration
      background:
        color:
          light: '#f8fafc'
          dark: '#111827'
      spacing:
        padding: ['40px', '0', '48px', '0']


  # =========================================================
  # LATEST NEWS
  # =========================================================

  - block: markdown
    content:
      title:
      subtitle: ''
      text: |

        <div class="arc-news-section">

          <div class="arc-news-header">

            <h2>
              Latest News
            </h2>

            <a
              class="arc-news-more"
              href="/news/"
            >
              See all news →
            </a>

          </div>


          <div class="arc-news-list">


            <article class="arc-news-item">

              <div class="arc-news-date">
                JUN 9<br>2026
              </div>

              <div>

                <h3 class="arc-news-title">
                  <a href="/post/2026-06-09-gonzalespeterson/">
                    Taylor Gonzales Named 2026 Ruth D. Peterson Fellow
                  </a>
                </h3>

                <p class="arc-news-description">
                  Taylor Gonzales was selected as a 2026 Ruth D. Peterson Fellow
                  by the American Society of Criminology.
                </p>

              </div>

            </article>


            <article class="arc-news-item">

              <div class="arc-news-date">
                JUN 5<br>2026
              </div>

              <div>

                <h3 class="arc-news-title">
                  <a href="/post/2026-06-04-jrcdpodcast/">
                    JRCD Author Interview with Dr. Tostlebe
                  </a>
                </h3>

                <p class="arc-news-description">
                  Dr. Jennifer Tostlebe was featured in an author interview
                  for the Journal of Research in Crime and Delinquency.
                </p>

              </div>

            </article>


            <article class="arc-news-item">

              <div class="arc-news-date">
                MAY 7<br>2026
              </div>

              <div>

                <h3 class="arc-news-title">
                  <a href="/post/2026-05-07-graduation/">
                    ARC Lab Celebrates Three Graduates Crossing the Stage
                  </a>
                </h3>

                <p class="arc-news-description">
                  Dr. Addison Kobie, Dr. John Ursino, and Yujin Kim, MA,
                  celebrated their graduations.
                </p>

              </div>

            </article>


            <article class="arc-news-item">

              <div class="arc-news-date">
                APR 16<br>2026
              </div>

              <div>

                <h3 class="arc-news-title">
                  <a href="/post/2026-04-16-kimthesis/">
                    Congratulations Yujin!
                  </a>
                </h3>

                <p class="arc-news-description">
                  Yujin Kim successfully defended her thesis on differential
                  fit and racial bias in juvenile risk assessment.
                </p>

              </div>

            </article>


            <article class="arc-news-item">

              <div class="arc-news-date">
                APR 13<br>2026
              </div>

              <div>

                <h3 class="arc-news-title">
                  <a href="/post/2026-04-13-kobie/">
                    Congratulations Dr. Kobie!
                  </a>
                </h3>

                <p class="arc-news-description">
                  Addison Kobie successfully defended her dissertation on
                  intersectionality of race and gender in a multi-state assessment.
                </p>

              </div>

            </article>


          </div>

        </div>
    design:
      columns: '1'
      css_class: homepage-news
      spacing:
        padding: ['40px', '0', '48px', '0']


  # =========================================================
  # FEATURED PROJECTS
  # =========================================================

  - block: markdown
    content:
      title:
      subtitle: ''
      text: |

        <div class="homepage-featured">

          <div class="homepage-section-header">

            <h2>
              Featured Projects
            </h2>

            <a
              class="homepage-section-link"
              href="/projects/"
            >
              See all projects →
            </a>

          </div>


          <div class="homepage-card-grid homepage-card-grid-3">


            <div class="homepage-card">

              <a
                class="homepage-card-link"
                href="/projects/2026_ndcs-evaluation/"
              >

                <img
                  src="/projects/2026_ndcs-evaluation/featured.png"
                  alt="NDCS program evaluation"
                >

                <div class="homepage-card-body">

                  <p class="homepage-card-kicker">
                    Project
                  </p>

                  <h3>
                    NDCS program evaluation
                  </h3>

                  <p>
                    Evaluating Nebraska Department of Correctional Services
                    programming to improve implementation and outcomes.
                  </p>

                </div>

              </a>

            </div>


            <div class="homepage-card">

              <a
                class="homepage-card-link"
                href="/projects/2026_ngu/"
              >

                <img
                  src="/projects/2026_ngu/featured.png"
                  alt="Turning hope into evidence"
                >

                <div class="homepage-card-body">

                  <p class="homepage-card-kicker">
                    Project
                  </p>

                  <h3>
                    Turning hope into evidence
                  </h3>

                  <p>
                    A pilot study laying the groundwork for evaluation of the
                    Never Give Up Transitional Living Program.
                  </p>

                </div>

              </a>

            </div>


            <div class="homepage-card">

              <a
                class="homepage-card-link"
                href="/projects/2025_av_iowa/"
              >

                <img
                  src="/projects/2025_av_iowa/featured.png"
                  alt="Parole decision making tool"
                >

                <div class="homepage-card-body">

                  <p class="homepage-card-kicker">
                    Project
                  </p>

                  <h3>
                    Parole decision-making tool
                  </h3>

                  <p>
                    Development and evaluation of a tool designed to support
                    parole decision-making.
                  </p>

                </div>

              </a>

            </div>


          </div>

        </div>
    design:
      columns: '1'
      css_class: homepage-projects
      background:
        color:
          light: '#f8fafc'
          dark: '#111827'
      spacing:
        padding: ['40px', '0', '56px', '0']
---