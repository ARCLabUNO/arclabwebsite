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
  # LATEST NEWS — AUTOMATIC
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

            {{ $posts := where site.RegularPages "Section" "post" }}
            {{ $posts = $posts.ByDate.Reverse }}

            {{ range first 5 $posts }}

              <article class="arc-news-item">

                <div class="arc-news-date">
                  {{ .Date.Format "Jan 2" }}<br>
                  {{ .Date.Format "2006" }}
                </div>


                <div>

                  <h3 class="arc-news-title">

                    <a href="{{ .RelPermalink }}">
                      {{ .Title }}
                    </a>

                  </h3>


                  {{ with .Summary }}

                    <p class="arc-news-description">
                      {{ . | plainify | truncate 180 }}
                    </p>

                  {{ end }}

                </div>

              </article>

            {{ end }}

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


            <!-- PROJECT 1 -->

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


            <!-- PROJECT 2 -->

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


            <!-- PROJECT 3 -->

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