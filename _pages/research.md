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
