---
layout: archive
title: "Research"
show_title: false
permalink: /research/
author_profile: true

---
## Past Research
---
<!-- =========================
     PAST RESEARCH - PROJECT 01
     ========================= -->

<style>
  .research-project {
    max-width: 1000px;
    margin: 40px auto;
    font-family: inherit;
  }

  .research-project-card {
    border: 1px solid #ddd;
    border-radius: 12px;
    padding: 24px 28px;
    background: #fff;
  }

  .project-period {
    font-size: 14px;
    color: #777;
    margin-bottom: 8px;
  }

  .project-title {
    margin: 0 0 8px 0;
    font-size: 26px;
    line-height: 1.3;
  }

  .project-location {
    margin: 0 0 20px 0;
    color: #666;
    font-size: 15px;
  }

  .research-toggle {
    border: none;
    background: transparent;
    padding: 0;
    font-size: 15px;
    font-weight: 600;
    cursor: pointer;
    color: #333;
  }

  .research-details {
    display: none;
    margin-top: 28px;
    border-top: 1px solid #eee;
    padding-top: 25px;
  }

  .research-details.open {
    display: block;
  }

  .project-line {
    margin: 0 0 12px 0;
    line-height: 1.65;
  }

  .project-line strong {
    font-weight: 600;
  }

  .publication-list {
    margin-top: 22px;
  }

  .publication {
    margin-bottom: 22px;
    line-height: 1.65;
  }

  .publication a {
    color: inherit;
    text-decoration: underline;
  }

  /* =========================
     IMAGE GALLERY
     ========================= */

  .project-gallery {
    display: flex;
    gap: 12px;
    margin-top: 28px;
    align-items: stretch;
  }

  .project-gallery a {
    flex: 1;
    display: block;
    overflow: hidden;
    border-radius: 8px;
    aspect-ratio: 16 / 10;
  }

  .project-gallery img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    display: block;
    cursor: pointer;
    transition: transform 0.2s ease;
  }

  .project-gallery img:hover {
    transform: scale(1.03);
  }

  .hide-research {
    margin-top: 28px;
  }

  @media (max-width: 700px) {
    .project-gallery {
      gap: 7px;
    }

    .project-title {
      font-size: 22px;
    }

    .research-project-card {
      padding: 20px;
    }
  }
</style>


<div class="research-project">

  <!-- CLOSED PROJECT CARD -->

  <div class="research-project-card">

    <div class="project-period">
      2018–2021
    </div>

    <h2 class="project-title">
      Open-Pit Mine Deformation Monitoring Using InSAR
    </h2>

    <p class="project-location">
      Gol Gohar Sirjan Mine, Iran
    </p>

    <button
      class="research-toggle"
      type="button"
      onclick="toggleResearchProject(this)">
      View Research ↓
    </button>


    <!-- HIDDEN PROJECT CONTENT -->

    <div class="research-details">

      <p class="project-line">
        <strong>Objective:</strong>
        To investigate surface deformation, subsidence, interferometric
        coherence, and elevation changes associated with open-pit mining
        using satellite radar interferometry.
      </p>

      <p class="project-line">
        <strong>Data:</strong>
        ENVISAT SAR imagery.
      </p>

      <p class="project-line">
        <strong>Methods:</strong>
        DInSAR, PS-InSAR, interferometric coherence analysis,
        InSAR-derived DEM generation, and time-series analysis.
      </p>

      <p class="project-line">
        <strong>Software:</strong>
        StaMPS, GMTSAR, SNAP.
      </p>

      <p class="project-line">
        <strong>Research Focus:</strong>
        Temporal and spatial baseline effects on coherence,
        mining-induced deformation and subsidence, persistent-scatterer
        time-series analysis, InSAR-derived elevation analysis,
        extracted mine-volume estimation, and radar-wavelength effects
        on deformation monitoring.
      </p>

      <p class="project-line">
        <strong>Key Outcome:</strong>
        The research demonstrated the application of InSAR for monitoring
        deformation and subsidence around the Gol Gohar open-pit mine
        and for deriving elevation information relevant to mine-volume
        assessment.
      </p>


      <!-- PUBLICATIONS -->

      <div class="publication-list">

        <p class="project-line">
          <strong>Research Outputs:</strong>
        </p>


        <!-- 2018 - Publication 1 -->

        <div class="publication">
          Shami, S., &amp; Hossainali, MM. (2018).
          Analysis of the effect of temporal and spatial baseline of radar
          images on the amount of coherence for detecting large-scale
          displacement gradients using interferometric synthetic aperture
          radar (Case study: Gol Gohar Sirjan Mine).
          Geomatics and GIT 97 (In Persian)
          (Conference Paper: Poster Presentation)
        </div>


        <!-- 2018 - Publication 2 -->

        <div class="publication">
          Shami, S., Ghorbani, Z., &amp; Abedi, L. (2018).
          Persistent Scatterers Time series analysis of radar interferometry
          to determine the rate subsidence of areas around the open pit mines
          (Case study: Gol Gohar Sirjan Mine).
          The 4th National Geology and Mining Explorations Symposium
          (In Persian)
          (Conference Paper: Poster Presentation)
        </div>


        <!-- 2018 - Publication 3 -->

        <div class="publication">
          Shami, S., Ghorbani, Z., &amp; Abedi, L. (2018).
          Calculation of the extracted mines volume using DEM obtained from
          the Envisat radar satellite images
          (Case study: Gol Gohar Sirjan Mine).
          The 4th National Geology and Mining Explorations Symposium
          (In Persian)
          (Conference Paper: Oral Presentation)
        </div>


        <!-- 2019 - Publication 4 -->

        <div class="publication">
          Shami, S., &amp; Ghorbani, Z. (2019).
          Influence of wavelength radar images in estimation of open-pit mine
          displacements using radar interferometry technology
          (case study: Gol Gohar Sirjan mine).
          3rd TRIGGER International Conference
          (Conference Paper: Poster Presentation)
        </div>


        <!-- 2019 - Publication 5 -->

        <div class="publication">
          Shami, S., Hossainali, MM., &amp; Babaee, S. (2019).
          Analysis of Large-scale Displacement Using Radar Interferometry
          Technology in Open-pit Mines
          (Case Study: Gol Gohar Sirjan Mine).
          Geospatial Engineering Journal (In Persian)
          (peer-reviewed: Review Article)
        </div>


        <!-- 2019 - Publication 7 -->

        <div class="publication">
          Shami, S., &amp; Ghorbani, Z. (2019).
          Processing Radar Images using GMTSAR &amp; SNAP.
          Arshadan Press
          (In Persian, ISBN: 978-622-251-021-3)
          (Book: Technical Book)
        </div>


        <!-- 2020 - Publication 8 -->

        <div class="publication">
          Hossainali, MM., &amp; Shami, S. (2020).
          Processing Radar Images using StaMPS.
          K.N. TOOSI UNIVERSITY Press
          (In Persian, ISBN: 978-622-6655-46-0)
          (Book: Technical Book)
        </div>


        <!-- 2021 - Publication 10 -->

        <div class="publication">
          Shami, S. (2021).
          GMTSAR installation and processing Guide - Practical InSAR handbook series.
          ebook
          (Book: Handbook)
          doi.org/10.5281/zenodo.22609191
        </div>

      </div>


      <!-- THREE IMAGES - SAME SIZE, NO TITLES -->

      <div class="project-gallery">

        <a href="images/research/gol-gohar/image-1.jpg"
           target="_blank"
           rel="noopener">
          <img
            src="images/research/gol-gohar/image-1.jpg"
            alt="">
        </a>

        <a href="images/research/gol-gohar/image-2.jpg"
           target="_blank"
           rel="noopener">
          <img
            src="images/research/gol-gohar/image-2.jpg"
            alt="">
        </a>

        <a href="images/research/gol-gohar/image-3.jpg"
           target="_blank"
           rel="noopener">
          <img
            src="images/research/gol-gohar/image-3.jpg"
            alt="">
        </a>

      </div>


      <!-- HIDE BUTTON -->

      <div class="hide-research">

        <button
          class="research-toggle"
          type="button"
          onclick="toggleResearchProject(this)">
          Hide Research ↑
        </button>

      </div>

    </div>

  </div>

</div>


<script>
  function toggleResearchProject(button) {

    const details =
      button.closest(".research-project-card")
             .querySelector(".research-details");

    details.classList.toggle("open");

    const isOpen = details.classList.contains("open");

    const buttons =
      button.closest(".research-project-card")
            .querySelectorAll(".research-toggle");

    buttons.forEach(function(btn) {

      if (btn.textContent.includes("View")) {
        btn.textContent =
          isOpen ? "Hide Research ↑" : "View Research ↓";
      }

    });
  }
</script>
---
