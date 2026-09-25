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
  .lb-overlay { position: fixed; inset: 0; background: rgba(0,0,0,.88);
    display: none; align-items: center; justify-content: center;
    z-index: 9999; padding: 24px; }
  .lb-overlay:target { display: flex; }
  .lb-overlay img { max-width: 92vw; max-height: 92vh; border-radius: 10px;
    box-shadow: 0 20px 60px rgba(0,0,0,.6); object-fit: contain; }
  .lb-close { position: absolute; top: 14px; right: 22px; color: #fff;
    font-size: 2rem; text-decoration: none; line-height: 1; }
</style>

<!-- ===== Card wrapper ===== -->
<div style="border: 1px solid #ddd; border-radius: 8px; padding: 0.8rem 1.2rem; margin-bottom: 1.2rem; background: #fafafa; transition: all 0.2s;">

  <!-- (۱) Title – always visible -->
  <h3 style="font-size: 1.1rem; font-weight: 600; color: #2c3e50; margin: 0; display: flex; align-items: center; gap: 8px;">
    <span style="font-size: 1.4rem;">🗂️</span>
    5. InSAR vs. GNSS Time‑Series Comparison Script
  </h3>

  <!-- (۲) Three images in one row – always visible -->
  <div style="display:flex; flex-direction:row; flex-wrap:nowrap; gap:10px; width:100%; margin:0.9rem 0 0.9rem 0;">
    <a href="#img1" style="flex:1 1 0; min-width:0; display:block;">
      <img src="images/research/insar-gnss-01.jpg" alt=""
           style="width:100%; height:100px; object-fit:cover; display:block;
                  border-radius:8px; border:1px solid #e6e9ee;">
    </a>
    <a href="#img2" style="flex:1 1 0; min-width:0; display:block;">
      <img src="images/research/insar-gnss-02.jpg" alt=""
           style="width:100%; height:100px; object-fit:cover; display:block;
                  border-radius:8px; border:1px solid #e6e9ee;">
    </a>
    <a href="#img3" style="flex:1 1 0; min-width:0; display:block;">
      <img src="images/research/insar-gnss-03.jpg" alt=""
           style="width:100%; height:100px; object-fit:cover; display:block;
                  border-radius:8px; border:1px solid #e6e9ee;">
    </a>
  </div>

  <!-- (۳) Click to expand + (۴) everything else hidden -->
  <details style="border: 1px solid #ddd; border-radius: 8px; padding: 0.8rem 1.2rem; background: #ffffff;">
    <summary style="font-size: 1rem; font-weight: 600; color: #2c3e50; cursor: pointer; list-style: none; display: flex; align-items: center; gap: 8px;">
      <span style="font-size: 1.1rem;">📄</span>
      Details &amp; Download
      <span style="margin-left: auto; font-size: 0.9rem; color: #888; font-weight: 400;">
        ⬇️ Click to expand
      </span>
    </summary>

    <div style="padding-top: 1rem; border-top: 1px solid #eee; margin-top: 0.8rem;">

      <p style="font-size: 1rem; line-height: 1.7; color: #444;">
        <strong>📌 Description:</strong><br>
        This script compares InSAR and GNSS displacement time‑series at a specific station (SJB1) over the same temporal period. It loads the two datasets (InSAR and GPS) from CSV files, calculates linear velocities for both, and plots the overlapping time‑series along with the corresponding trendlines and velocity annotations. This comparison is used to validate the InSAR results against independent GNSS measurements.

        The script uses Pandas for data handling, Matplotlib for visualization, and NumPy for polynomial fitting. Velocities are computed in mm/year and displayed directly on the plot. The figure is saved with high resolution (500 DPI) and uses a clean academic style with Times New Roman fonts.
      </p>

      <div style="display: flex; flex-wrap: wrap; gap: 1.5rem; margin: 1rem 0; font-size: 0.95rem; background: #f0f4f8; padding: 0.8rem 1.2rem; border-radius: 6px;">
        <span><strong>📁 Format:</strong> Python &amp; CSV</span>
      </div>

      <p style="margin: 0.8rem 0 0.4rem;">
        <strong>📥 Download Link:</strong><br>
        <a href="https://github.com/siavashshami/InSAR-tools/tree/main/applications/insar-gnss-comparison/InSAR%20vs.%20GNSS%20Time%E2%80%91Series%20Comparison%20Script" target="_blank" style="color: #3498db; text-decoration: none; border-bottom: 1px dotted #3498db;">
          🔗 Download from GitHub
        </a>
      </p>

      <div style="margin-top: 1.2rem; padding: 0.8rem 1rem; background: #f9f9f9; border-left: 4px solid #3498db; border-radius: 4px; font-size: 0.92rem; color: #555;">
        <strong>📜 Citation:</strong><br>
        Abdalla, A., Shami, S., Shahriari, M. A., &amp; Azar, M. K. (2024). Estimation of land displacement in East Baton Rouge Parish, Louisiana, using InSAR: Comparisons with GNSS and machine learning models. The Egyptian Journal of Remote Sensing and Space Sciences
      </div>

    </div>
  </details>
</div>

<!-- ===== Lightbox overlays (include once per page; unique IDs per card) ===== -->
<div id="img1" class="lb-overlay"><a href="#" class="lb-close">×</a><img src="images/research/insar-gnss-01.jpg" alt=""></div>
<div id="img2" class="lb-overlay"><a href="#" class="lb-close">×</a><img src="images/research/insar-gnss-02.jpg" alt=""></div>
<div id="img3" class="lb-overlay"><a href="#" class="lb-close">×</a><img src="images/research/insar-gnss-03.jpg" alt=""></div>
---
<div style="border: 1px solid #ddd; border-radius: 8px; padding: 0.8rem 1.2rem; margin-bottom: 1.2rem; background: #fafafa; transition: all 0.2s;">

  <!-- Title (always visible) -->
  <h3 style="font-size: 1.1rem; font-weight: 600; color: #2c3e50; margin: 0; display: flex; align-items: center; gap: 8px;">
    <span style="font-size: 1.4rem;">🗂️</span>
    1. Open-Pit Mine Deformation Monitoring Using InSAR
  </h3>

  <!-- Three images in one row (always visible) -->
  <div style="display: flex; gap: 12px; margin: 1rem 0; flex-wrap: nowrap;">

    <a href="images/research/open-pit-mine-01.jpg" target="_blank" style="flex: 1 1 0; min-width: 0;">
      <img
        src="images/research/open-pit-mine-01.jpg"
        alt=""
        style="width: 100%; height: 150px; object-fit: cover; border-radius: 6px; display: block;">
    </a>

    <a href="images/research/open-pit-mine-02.jpg" target="_blank" style="flex: 1 1 0; min-width: 0;">
      <img
        src="images/research/open-pit-mine-02.jpg"
        alt=""
        style="width: 100%; height: 150px; object-fit: cover; border-radius: 6px; display: block;">
    </a>

    <a href="images/research/open-pit-mine-03.jpg" target="_blank" style="flex: 1 1 0; min-width: 0;">
      <img
        src="images/research/open-pit-mine-03.jpg"
        alt=""
        style="width: 100%; height: 150px; object-fit: cover; border-radius: 6px; display: block;">
    </a>

  </div>

  <!-- Hidden content (everything else) -->
  <details style="border: 1px solid #ddd; border-radius: 8px; padding: 0.8rem 1.2rem; background: #ffffff;">

    <summary style="font-size: 1rem; font-weight: 600; color: #2c3e50; cursor: pointer; list-style: none; display: flex; align-items: center; gap: 8px;">
      <span style="font-size: 1.1rem;">📄</span>
      Details &amp; Research Outputs
      <span style="margin-left: auto; font-size: 0.9rem; color: #888; font-weight: 400;">
        ⬇️ Click to expand
      </span>
    </summary>

    <div style="padding-top: 1rem; border-top: 1px solid #eee; margin-top: 0.8rem;">

      <p>
        <strong>Study Area:</strong> Gol Gohar Sirjan Open-Pit Mine, Iran
        &nbsp; | &nbsp;
        <strong>Period:</strong> 2018–2021
      </p>

      <p>
        <strong>Objective:</strong>
        Investigation and monitoring of large-scale surface deformation in open-pit mining areas using radar interferometry and InSAR time-series techniques.
      </p>

      <p>
        <strong>Data:</strong>
        ENVISAT radar imagery and other SAR datasets used for interferometric analysis of the mining area.
      </p>

      <p>
        <strong>Methods:</strong>
        DInSAR, PS-InSAR, interferometric coherence analysis, temporal and spatial baseline analysis, DEM generation, and InSAR-based deformation monitoring.
      </p>

      <p>
        <strong>Software:</strong>
        GMTSAR, SNAP, and StaMPS.
      </p>

      <p>
        <strong>Research Focus:</strong>
        Open-pit mine deformation, subsidence monitoring, interferometric coherence, radar wavelength effects, and DEM-based mine-volume estimation.
      </p>

      <p>
        <strong>Key Outcome:</strong>
        Development of a research line focused on applying InSAR techniques to open-pit mine deformation monitoring, followed by related technical publications and InSAR processing books and handbooks.
      </p>

      <h4 style="color: #2c3e50; margin-top: 1.4rem; margin-bottom: 0.8rem;">
        Research Outputs
      </h4>

      <div style="line-height: 1.7;">

        <p>
          Shami, S., &amp; Hossainali, MM. (2018). Analysis of the effect of temporal and spatial baseline of radar images on the amount of coherence for detecting large-scale displacement gradients using interferometric synthetic aperture radar (Case study: Gol Gohar Sirjan Mine). Geomatics and GIT 97 (In Persian) (Conference Paper: Poster Presentation)
        </p>

        <p>
          Shami, S., Ghorbani, Z., &amp; Abedi, L. (2018). Persistent Scatterers Time series analysis of radar interferometry to determine the rate subsidence of areas around the open pit mines (Case study: Gol Gohar Sirjan Mine). The 4th National Geology and Mining Explorations Symposium (In Persian) (Conference Paper: Poster Presentation)
        </p>

        <p>
          Shami, S., Ghorbani, Z., &amp; Abedi, L. (2018). Calculation of the extracted mines volume using DEM obtained from the Envisat radar satellite images (Case study: Gol Gohar Sirjan Mine). The 4th National Geology and Mining Explorations Symposium (In Persian) (Conference Paper: Oral Presentation)
        </p>

        <p>
          Shami, S., &amp; Ghorbani, Z. (2019). Influence of wavelength radar images in estimation of open-pit mine displacements using radar interferometry technology (case study: Gol Gohar Sirjan mine). 3rd TRIGGER International Conference (Conference Paper: Poster Presentation)
        </p>

        <p>
          Shami, S., Hossainali, MM., &amp; Babaee, S. (2019). Analysis of Large-scale Displacement Using Radar Interferometry Technology in Open-pit Mines (Case Study: Gol Gohar Sirjan Mine). Geospatial Engineering Journal (In Persian) (peer-reviewed: Review Article)
        </p>

        <p>
          Shami, S., &amp; Ghorbani, Z. (2019). Processing Radar Images using GMTSAR &amp; SNAP. Arshadan Press (In Persian, ISBN: 978-622-251-021-3) (Book: Technical Book)
        </p>

        <p>
          Hossainali, MM., &amp; Shami, S. (2020). Processing Radar Images using StaMPS. K.N. TOOSI UNIVERSITY Press (In Persian, ISBN: 978-622-6655-46-0) (Book: Technical Book)
        </p>

        <p>
          Shami, S. (2021). GMTSAR installation and processing Guide - Practical InSAR handbook series. ebook (Book: Handbook) doi.org/10.5281/zenodo.22609191
        </p>

      </div>

    </div>

  </details>

</div>
