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
            alt="ARC Lab graphic"
          >
        </div>
    design:
      columns: '1'
      css_class: arc-home-hero
      spacing:
        padding: ['0', '0', '0', '0']


  # =========================================================
  # HERO / INTRO
  # =========================================================

  - block: markdown
    content:
      title:
      subtitle: ''
      text: |

        <section class="arc-home-intro">

          <div class="arc-home-intro-inner">

            <p class="arc-home-eyebrow">
              ADVANCING RESEARCH IN CORRECTIONS
            </p>

            <h1>
              Advancing Research in Corrections Lab
            </h1>

            <p class="arc-home-lead">
              Studying correctional systems as they operate and how they can work better.
            </p>

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

        </section>


        <style>

        /* =====================================================
           HERO GRAPHIC
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

        .arc-home-eyebrow {
          margin: 0 0 0.7rem;

          color: #2dd4bf;

          font-size: 0.76rem;
          font-weight: 800;

          letter-spacing: 0.13em;
          text-transform: uppercase;
        }

        .arc-home-intro h1 {
          margin: 0 0 0.7rem;

          color: #f1f5f9;

          font-size: clamp(2rem, 4vw, 3rem);
          font-weight: 800;
          line-height: 1.1;

          letter-spacing: -0.025em;
        }

        .arc-home-lead {
          margin: 0 0 1.5rem;

          color: #d9e8f5;

          font-size: 1.2rem;
          font-weight: 600;
          line-height: 1.55;
        }

        .arc-home-intro p:not(.arc-home-eyebrow):not(.arc-home-lead) {
          max-width: 820px;

          margin-left: auto;
          margin-right: auto;

          color: #c3cfdd;

          font-size: 1rem;
          line-height: 1.75;
        }


        /* =====================================================
           HERO BUTTONS
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
           AARDVARK
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
           EDITORIAL SECTION HEADINGS
        ===================================================== */

        .arc-editorial-heading {
          margin: 0 0 0.5rem;

          color: #f1f5f9;

          font-size: 1.85rem;
          font-weight: 800;
          line-height: 1.2;

          text-align: center;
        }

        .arc-editorial-heading-rule {
          width: 34px;
          height: 2px;

          margin: 0.65rem auto 2rem;

          background: #2dd4bf;

          border-radius: 999px;
        }


        /* =====================================================
           RESEARCH TOPICS
        ===================================================== */

        .arc-research-section {
          max-width: 1050px;

          margin: 0 auto;

          padding: 3rem 1rem 3.25rem;
        }

        .arc-research-grid {
          display: grid;

          grid-template-columns:
            repeat(2, minmax(0, 1fr));

          column-gap: 3rem;

          border-top: 1px solid #33465f;
        }

        .arc-research-item {
          display: grid;

          grid-template-columns:
            42px minmax(0, 1fr);

          column-gap: 0.9rem;

          padding: 1rem 0 1.1rem;

          border-bottom:
            1px solid rgba(51, 70, 95, 0.72);
        }

        .arc-research-number {
          color: #5eead4;

          font-size: 0.82rem;
          font-weight: 800;
          line-height: 1.5;

          letter-spacing: 0.04em;
        }

        .arc-research-title {
          margin: 0 0 0.25rem;

          color: #d9e8f5;

          font-size: 1.02rem;
          font-weight: 700;
          line-height: 1.4;
        }

        .arc-research-description {
          margin: 0;

          color: #9aa8bd;

          font-size: 0.92rem;
          line-height: 1.55;
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

          text-decoration: none !important;
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
           HOMEPAGE FEATURED SECTIONS
        ===================================================== */

        .homepage-featured {
          max-width: 1100px;

          margin: 0 auto;

          padding: 3rem 1rem 3.5rem;
        }

        .homepage-section-header {
          display: flex;

          justify-content: space-between;
          align-items: baseline;

          gap: 1rem;

          margin-bottom: 1.5rem;
        }

        .homepage-section-header h2 {
          margin: 0;

          color: #f1f5f9;

          font-size: 1.8rem;
          font-weight: 800;
          line-height: 1.2;
        }

        .homepage-section-link {
          color: #7fc8e8 !important;

          font-size: 0.9rem;
          font-weight: 700;

          text-decoration: none !important;

          white-space: nowrap;
        }

        .homepage-section-link:hover {
          color: #2dd4bf !important;

          text-decoration: none !important;
        }


        /* =====================================================
           NEWS — EDITORIAL LIST
        ===================================================== */

        .homepage-news-list {
          border-top: 1px solid #33465f;
        }

        .homepage-news-item {
          display: grid;

          grid-template-columns:
            90px minmax(0, 1fr);

          column-gap: 1.25rem;

          padding: 1rem 0;

          border-bottom:
            1px solid rgba(51, 70, 95, 0.72);
        }

        .homepage-news-date {
          color: #5eead4;

          font-size: 0.82rem;
          font-weight: 800;
          line-height: 1.4;

          letter-spacing: 0.03em;

          text-transform: uppercase;
        }

        .homepage-news-title {
          margin: 0 0 0.25rem;

          color: #d9e8f5;

          font-size: 1rem;
          font-weight: 700;
          line-height: 1.45;
        }

        .homepage-news-title a {
          color: inherit !important;

          text-decoration: none !important;
        }

        .homepage-news-title a:hover {
          color: #7fc8e8 !important;

          text-decoration: none !important;
        }

        .homepage-news-summary {
          margin: 0;

          color: #9aa8bd;

          font-size: 0.9rem;
          line-height: 1.5;
        }


        /* =====================================================
           PROJECT CARDS
        ===================================================== */

        .homepage-card-grid {
          display: grid;

          gap: 1.5rem;
        }

        .homepage-card-grid-3 {
          grid-template-columns:
            repeat(3, minmax(0, 1fr));
        }

        .homepage-card {
          position: relative;

          background:
            linear-gradient(
              145deg,
              #1a2940 0%,
              #0f1622 100%
            );

          border: 1px solid #33465f;
          border-radius: 12px;

          overflow: hidden;

          box-shadow:
            0 8px 24px rgba(0, 0, 0, 0.18);

          transition:
            transform 0.2s ease,
            border-color 0.2s ease,
            box-shadow 0.2s ease;
        }

        .homepage-card::before {
          content: "";

          position: absolute;

          top: 0;
          left: 0;
          right: 0;

          height: 4px;

          background:
            linear-gradient(
              90deg,
              #3b82f6 0%,
              #2dd4bf 100%
            );

          z-index: 2;
        }

        .homepage-card:hover {
          transform: translateY(-4px);

          border-color: #526b89;

          box-shadow:
            0 14px 30px rgba(0, 0, 0, 0.28);
        }

        .homepage-card-link {
          display: block;

          color: inherit !important;

          text-decoration: none !important;
        }

        .homepage-card-link:hover {
          text-decoration: none !important;
        }

        .homepage-card-link img {
          display: block;

          width: 100%;
          height: 205px;

          object-fit: cover;
        }

        .homepage-card-body {
          padding: 1.15rem 1.15rem 1.35rem;
        }

        .homepage-card-kicker {
          margin: 0 0 0.4rem;

          color: #5eead4;

          font-size: 0.75rem;
          font-weight: 800;

          letter-spacing: 0.07em;

          text-transform: uppercase;
        }

        .homepage-card h3 {
          margin: 0 0 0.55rem;

          color: #d9e8f5;

          font-size: 1.12rem;
          font-weight: 700;
          line-height: 1.35;
        }

        .homepage-card-body > p:last-child {
          margin: 0;

          color: #9aa8bd;

          font-size: 0.9rem;
          line-height: 1.55;
        }


        /* =====================================================
           RESPONSIVE
        ===================================================== */

        @media (max-width: 850px) {

          .arc-research-grid {
            grid-template-columns: 1fr;
          }

          .arc-team-layout {
            grid-template-columns: 1fr;
          }

          .homepage-card-grid-3 {
            grid-template-columns: 1fr;
          }

        }


        @media (max-width: 650px) {

          .arc-home-intro {
            padding-top: 2rem;
          }

          .arc-home-lead {
            font-size: 1.05rem;
          }

          .homepage-section-header {
            align-items: flex-start;

            flex-direction: column;

            gap: 0.4rem;
          }

          .homepage-news-item {
            grid-template-columns:
              70px minmax(0, 1fr);

            column-gap: 0.85rem;
          }

        }

        </style>

    design:
      columns: '1'
      css_class: arc-home-intro-section
      spacing:
        padding: ['0', '0', '0', '0']


  # =========================================================
  # WHAT WE STUDY
  # =========================================================

  - block: markdown
    content:
      title:
      subtitle: ''
      text: |

        <section class="arc-research-section">

          <h2 class="arc-editorial-heading">
            What We Study
          </h2>

          <div class="arc-editorial-heading-rule"></div>


          <div class="arc-research-grid">


            <div class="arc-research-item">

              <div class="arc-research-number">
                01
              </div>

              <div>

                <h3 class="arc-research-title">
                  Institutional &amp; Community Corrections
                </h3>

                <p class="arc-research-description">
                  How correctional systems operate across custody and community
                  settings, and how policy and practice shape outcomes.
                </p>

              </div>

            </div>


            <div class="arc-research-item">

              <div class="arc-research-number">
                02
              </div>

              <div>

                <h3 class="arc-research-title">
                  Misconduct &amp; Recidivism
                </h3>

                <p class="arc-research-description">
                  Examining misconduct, reoffending, and the individual,
                  institutional, and contextual factors that shape correctional
                  outcomes.
                </p>

              </div>

            </div>


            <div class="arc-research-item">

              <div class="arc-research-number">
                03
              </div>

              <div>

                <h3 class="arc-research-title">
                  Criminological Theory
                </h3>

                <p class="arc-research-description">
                  Using criminological theory to understand offending,
                  institutional dynamics, behavior, and change across
                  correctional contexts.
                </p>

              </div>

            </div>


            <div class="arc-research-item">

              <div class="arc-research-number">
                04
              </div>

              <div>

                <h3 class="arc-research-title">
                  Program Evaluation
                </h3>

                <p class="arc-research-description">
                  Evaluating correctional programs and practices to understand
                  implementation, effectiveness, and opportunities for improvement.
                </p>

              </div>

            </div>


            <div class="arc-research-item">

              <div class="arc-research-number">
                05
              </div>

              <div>

                <h3 class="arc-research-title">
                  Risk-Needs Assessment
                </h3>

                <p class="arc-research-description">
                  Development, measurement, implementation, and interpretation
                  of tools used to understand and respond to correctional risk
                  and need.
                </p>

              </div>

            </div>


            <div class="arc-research-item">

              <div class="arc-research-number">
                06
              </div>

              <div>

                <h3 class="arc-research-title">
                  Reentry &amp; Desistance
                </h3>

                <p class="arc-research-description">
                  How people transition from correctional supervision and how
                  systems can support stability, change, and long-term success.
                </p>

              </div>

            </div>


            <div class="arc-research-item">

              <div class="arc-research-number">
                07
              </div>

              <div>

                <h3 class="arc-research-title">
                  Gangs &amp; Gang Membership
                </h3>

                <p class="arc-research-description">
                  Studying gang involvement, behavior, and institutional and
                  community responses to gang membership.
                </p>

              </div>

            </div>


          </div>

        </section>

    design:
      columns: '1'
      css_class: arc-home-research
      spacing:
        padding: ['0', '0', '0', '0']


  # =========================================================
  # TEAM
  # =========================================================

  - block: markdown
    content:
      title:
      subtitle: ''
      text: |

        <section class="arc-team-section">

          <h2 class="arc-editorial-heading">
            The ARC Lab Team
          </h2>

          <div class="arc-editorial-heading-rule"></div>


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

        </section>

    design:
      columns: '1'
      css_class: arc-home-team
      spacing:
        padding: ['0', '0', '0', '0']


  # =========================================================
  # RESEARCH & COLLABORATION
  # =========================================================

  - block: markdown
    content:
      title:
      subtitle: ''
      text: |

        <section class="arc-collab-section">

          <h2 class="arc-editorial-heading">
            Research &amp; Collaboration
          </h2>

          <div class="arc-editorial-heading-rule"></div>


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

        </section>

    design:
      columns: '1'
      css_class: arc-home-collaboration
      background:
        color:
          light: '#f8fafc'
          dark: '#111827'
      spacing:
        padding: ['0', '0', '0', '0']


  # =========================================================
  # LATEST NEWS
  # =========================================================

  - block: markdown
    content:
      title:
      subtitle: ''
      text: |

        <section class="homepage-featured">

          <div class="homepage-section-header">

            <h2>
              Latest News
            </h2>

            <a
              class="homepage-section-link"
              href="/news/"
            >
              See more news →
            </a>

          </div>


          <div class="homepage-news-list">


            <article class="homepage-news-item">

              <div class="homepage-news-date">
                JUN 2026
              </div>

              <div>

                <h3 class="homepage-news-title">
                  <a href="/post/2026-06-09-gonzalespeterson/">
                    Taylor Gonzales Named 2026 Ruth D. Peterson Fellow
                  </a>
                </h3>

                <p class="homepage-news-summary">
                  This prestigious fellowship recognizes outstanding doctoral
                  students from underrepresented racial and ethnic groups who
                  demonstrate exceptional promise in criminology and criminal
                  justice scholarship.
                </p>

              </div>

            </article>


            <article class="homepage-news-item">

              <div class="homepage-news-date">
                JUN 2026
              </div>

              <div>

                <h3 class="homepage-news-title">
                  <a href="/post/2026-06-04-jrcdpodcast/">
                    JRCD Author Interview with Dr. Tostlebe
                  </a>
                </h3>

                <p class="homepage-news-summary">
                  Excited to share my interview on the new Journal of Research
                  in Crime and Delinquency (JRCD) YouTube channel!
                </p>

              </div>

            </article>


            <article class="homepage-news-item">

              <div class="homepage-news-date">
                MAY 2026
              </div>

              <div>

                <h3 class="homepage-news-title">
                  <a href="/post/2026-05-07-graduation/">
                    ARC Lab Celebrates Three Graduates Crossing the Stage
                  </a>
                </h3>

                <p class="homepage-news-summary">
                  On May 7th, three ARC Lab students walked across the stage.
                </p>

              </div>

            </article>


            <article class="homepage-news-item">

              <div class="homepage-news-date">
                APR 2026
              </div>

              <div>

                <h3 class="homepage-news-title">
                  <a href="/post/2026-04-16-kimthesis/">
                    Congratulations Yujin!
                  </a>
                </h3>

                <p class="homepage-news-summary">
                  Yujin Kim successfully defended her thesis on April 16.
                </p>

              </div>

            </article>


          </div>

        </section>

    design:
      columns: '1'
      css_class: arc-home-news
      spacing:
        padding: ['0', '0', '0', '0']


  # =========================================================
  # FEATURED PROJECTS
  # =========================================================

  - block: markdown
    content:
      title:
      subtitle: ''
      text: |

        <section class="homepage-featured">

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

        </section>

    design:
      columns: '1'
      css_class: arc-home-projects
      background:
        color:
          light: '#f8fafc'
          dark: '#111827'
      spacing:
        padding: ['0', '0', '0', '0']
---