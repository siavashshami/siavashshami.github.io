---
layout: archive
title: "Research"
show_title: false
permalink: /research/
author_profile: true

---
## Past Research
---
<!-- ===== Lightbox CSS (include once per page) ===== -->
<style>
  .lb-overlay {
    position: fixed; inset: 0;
    background: rgba(0,0,0,0.88);
    display: none;
    align-items: center; justify-content: center;
    z-index: 9999;
    padding: 24px;
    backdrop-filter: blur(4px);
  }
  .lb-overlay:target { display: flex; }
  .lb-overlay img {
    max-width: 92vw; max-height: 92vh;
    border-radius: 10px;
    box-shadow: 0 20px 60px rgba(0,0,0,0.6);
    object-fit: contain;
    animation: lbZoom .25s ease;
  }
  @keyframes lbZoom {
    from { transform: scale(.94); opacity: 0 }
    to   { transform: scale(1);   opacity: 1 }
  }
  .lb-close {
    position: absolute; top: 18px; right: 24px;
    color: #fff; font-size: 2rem; line-height: 1;
    text-decoration: none; font-weight: 300;
    opacity: .85;
  }
  .lb-close:hover { opacity: 1; }

  /* Thumbnail row – always horizontal */
  .thumb-row {
    display: flex;
    flex-direction: row;
    flex-wrap: nowrap;
    gap: 10px;
    margin-bottom: 1rem;
    align-items: stretch;
  }
  .thumb-row a {
    flex: 1 1 0;
    min-width: 0;
    display: block;
  }
  .thumb-row img {
    width: 100%;
    height: 100px;
    object-fit: cover;
    border-radius: 8px;
    display: block;
    border: 1px solid #e6e9ee;
    transition: transform .2s, box-shadow .2s;
  }
  .thumb-row img:hover {
    transform: scale(1.05);
    box-shadow: 0 6px 18px rgba(30,58,95,.25);
  }
</style>

<!-- ===== Research Card ===== -->
<div style="
  border: 1px solid #e6e9ee;
  border-radius: 14px;
  padding: 1.2rem 1.4rem;
  margin-bottom: 1.6rem;
  background: linear-gradient(180deg, #ffffff 0%, #f7f9fc 100%);
  box-shadow: 0 4px 18px rgba(20, 40, 80, 0.06);
  font-family: system-ui, -apple-system, 'Segoe UI', Roboto, sans-serif;
">

  <!-- Title -->
  <h3 style="
    margin: 0 0 .9rem 0;
    color: #1e3a5f;
    font-size: 1.15rem;
    font-weight: 700;
    display: flex; align-items: center; gap: 10px;
  ">
    <span style="font-size: 1.4rem;">🗂️</span>
    1. Open-Pit Mine Deformation Monitoring Using InSAR
  </h3>

  <!-- Small image row (always horizontal, outside <details>) -->
  <div class="thumb-row">
    <a href="#img1"><img src="images/research/open-pit-mine-01.jpg" alt=""></a>
    <a href="#img2"><img src="images/research/open-pit-mine-02.jpg" alt=""></a>
    <a href="#img3"><img src="images/research/open-pit-mine-03.jpg" alt=""></a>
  </div>

  <!-- Hidden section (details) – text only -->
  <details style="
    border: 1px solid #e6e9ee;
    border-radius: 10px;
    padding: 0.7rem 1rem;
    background: #ffffff;
    transition: all .2s;
  ">
    <summary style="
      font-size: 1rem;
      font-weight: 600;
      color: #2c3e50;
      cursor: pointer;
      list-style: none;
      display: flex; align-items: center; gap: 8px;
      outline: none;
    ">
      <span style="font-size: 1.1rem;">📄</span>
      Details &amp; Research Outputs
      <span style="margin-left: auto; font-size: .85rem; color: #888; font-weight: 400;">
        ⬇️ Click to expand
      </span>
    </summary>

    <div style="padding-top: 1rem; border-top: 1px solid #eef1f5; margin-top: .8rem; line-height: 1.7; color: #334155;">

      <p style="margin: .4rem 0;">
        <strong style="color:#1e3a5f;">Study Area:</strong> Gol Gohar Sirjan Open-Pit Mine, Iran
        &nbsp; | &nbsp;
        <strong style="color:#1e3a5f;">Period:</strong> 2018–2021
      </p>

      <p style="margin: .4rem 0;">
        <strong style="color:#1e3a5f;">Objective:</strong>
        Investigation and monitoring of large-scale surface deformation in open-pit mining areas using radar interferometry and InSAR time-series techniques.
      </p>

      <p style="margin: .4rem 0;">
        <strong style="color:#1e3a5f;">Data:</strong>
        ENVISAT radar imagery and other SAR datasets used for interferometric analysis of the mining area.
      </p>

      <p style="margin: .4rem 0;">
        <strong style="color:#1e3a5f;">Methods:</strong>
        DInSAR, PS-InSAR, interferometric coherence analysis, temporal and spatial baseline analysis, DEM generation, and InSAR-based deformation monitoring.
      </p>

      <p style="margin: .4rem 0;">
        <strong style="color:#1e3a5f;">Software:</strong>
        GMTSAR, SNAP, and StaMPS.
      </p>

      <p style="margin: .4rem 0;">
        <strong style="color:#1e3a5f;">Research Focus:</strong>
        Open-pit mine deformation, subsidence monitoring, interferometric coherence, radar wavelength effects, and DEM-based mine-volume estimation.
      </p>

      <p style="margin: .4rem 0;">
        <strong style="color:#1e3a5f;">Key Outcome:</strong>
        Development of a research line focused on applying InSAR techniques to open-pit mine deformation monitoring, followed by related technical publications and InSAR processing books and handbooks.
      </p>

      <h4 style="color: #1e3a5f; margin-top: 1.4rem; margin-bottom: .8rem; font-size: 1rem;">
        Research Outputs
      </h4>

      <div style="line-height: 1.7;">
        <p style="margin:.5rem 0;">Shami, S., &amp; Hossainali, MM. (2018). Analysis of the effect of temporal and spatial baseline of radar images on the amount of coherence for detecting large-scale displacement gradients using interferometric synthetic aperture radar (Case study: Gol Gohar Sirjan Mine). Geomatics and GIT 97 (In Persian) (Conference Paper: Poster Presentation)</p>

        <p style="margin:.5rem 0;">Shami, S., Ghorbani, Z., &amp; Abedi, L. (2018). Persistent Scatterers Time series analysis of radar interferometry to determine the rate subsidence of areas around the open pit mines (Case study: Gol Gohar Sirjan Mine). The 4th National Geology and Mining Explorations Symposium (In Persian) (Conference Paper: Poster Presentation)</p>

        <p style="margin:.5rem 0;">Shami, S., Ghorbani, Z., &amp; Abedi, L. (2018). Calculation of the extracted mines volume using DEM obtained from the Envisat radar satellite images (Case study: Gol Gohar Sirjan Mine). The 4th National Geology and Mining Explorations Symposium (In Persian) (Conference Paper: Oral Presentation)</p>

        <p style="margin:.5rem 0;">Shami, S., &amp; Ghorbani, Z. (2019). Influence of wavelength radar images in estimation of open-pit mine displacements using radar interferometry technology (case study: Gol Gohar Sirjan mine). 3rd TRIGGER International Conference (Conference Paper: Poster Presentation)</p>

        <p style="margin:.5rem 0;">Shami, S., Hossainali, MM., &amp; Babaee, S. (2019). Analysis of Large-scale Displacement Using Radar Interferometry Technology in Open-pit Mines (Case Study: Gol Gohar Sirjan Mine). Geospatial Engineering Journal (In Persian) (peer-reviewed: Review Article)</p>

        <p style="margin:.5rem 0;">Shami, S., &amp; Ghorbani, Z. (2019). Processing Radar Images using GMTSAR &amp; SNAP. Arshadan Press (In Persian, ISBN: 978-622-251-021-3) (Book: Technical Book)</p>

        <p style="margin:.5rem 0;">Hossainali, MM., &amp; Shami, S. (2020). Processing Radar Images using StaMPS. K.N. TOOSI UNIVERSITY Press (In Persian, ISBN: 978-622-6655-46-0) (Book: Technical Book)</p>

        <p style="margin:.5rem 0;">Shami, S. (2021). GMTSAR installation and processing Guide - Practical InSAR handbook series. ebook (Book: Handbook) doi.org/10.5281/zenodo.22609191</p>
      </div>
    </div>
  </details>
</div>

<!-- ===== Lightbox overlays (include once per page; unique IDs per card) ===== -->
<div id="img1" class="lb-overlay">
  <a href="#" class="lb-close">×</a>
  <img src="images/research/open-pit-mine-01.jpg" alt="">
</div>
<div id="img2" class="lb-overlay">
  <a href="#" class="lb-close">×</a>
  <img src="images/research/open-pit-mine-02.jpg" alt="">
</div>
<div id="img3" class="lb-overlay">
  <a href="#" class="lb-close">×</a>
  <img src="images/research/open-pit-mine-03.jpg" alt="">
</div>
