---
layout: archive
title: "Codes & Scripts"
show_title: false
permalink: /codes_scripts/
author_profile: true

---
---
<details style="border: 1px solid #ddd; border-radius: 8px; padding: 0.8rem 1.2rem; margin-bottom: 1.2rem; background: #fafafa; transition: all 0.2s;">
  <summary style="font-size: 1.1rem; font-weight: 600; color: #2c3e50; cursor: pointer; list-style: none; display: flex; align-items: center; gap: 8px;">
    <span style="font-size: 1.4rem;">🗂️</span> 
    4. Baton Rouge, Louisiana, InSAR vs. GNSS Time‑Series Comparison Script
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
      <span><strong>📁 Format:</strong> Python & CSV</span>
      <span><strong>💾 Size:</strong> 40 KB (compressed)</span>
    </div>

    <p style="margin: 0.8rem 0 0.4rem;">
      <strong>📥 Download Link:</strong><br>
      <a href="https://drive.google.com/file/d/1ejgb6QT-OiWaDTRSsWmxP3j-Crgo0foU/view?usp=sharing" target="_blank" style="color: #3498db; text-decoration: none; border-bottom: 1px dotted #3498db;">
        🔗 Download from Google Drive
      </a>
    </p>

    <div style="margin-top: 1.2rem; padding: 0.8rem 1rem; background: #f9f9f9; border-left: 4px solid #3498db; border-radius: 4px; font-size: 0.92rem; color: #555;">
      <strong>📜 Citation:</strong><br>
      Abdalla, A., Shami, S., Shahriari, M. A., & Azar, M. K. (2024). Estimation of land displacement in East Baton Rouge Parish, Louisiana, using InSAR: Comparisons with GNSS and machine learning models. The Egyptian Journal of Remote Sensing and Space Sciences
    </div>
    
  </div>
</details>
---
<details style="border: 1px solid #ddd; border-radius: 8px; padding: 0.8rem 1.2rem; margin-bottom: 1.2rem; background: #fafafa; transition: all 0.2s;">
  <summary style="font-size: 1.1rem; font-weight: 600; color: #2c3e50; cursor: pointer; list-style: none; display: flex; align-items: center; gap: 8px;">
    <span style="font-size: 1.4rem;">🗂️</span> 
    3. Baton Rouge, Louisiana, Land Displacement Modeling – Machine Learning Codes
    <span style="margin-left: auto; font-size: 0.9rem; color: #888; font-weight: 400;">
      ⬇️ Click to expand
    </span>
  </summary>

  <div style="padding-top: 1rem; border-top: 1px solid #eee; margin-top: 0.8rem;">

    <p style="font-size: 1rem; line-height: 1.7; color: #444;">
      <strong>📌 Description:</strong><br>
     This project applies machine learning models (Lasso, KNN, Gradient Boosting, Random Forest) to predict land displacement rates using InSAR and GNSS data in East Baton Rouge Parish, Louisiana. The models are trained on topographic and anthropogenic features (DEM, slope, fault, river, road, land use, etc.) and evaluated using R², RMSE, and MAE.
    </p>

    <div style="display: flex; flex-wrap: wrap; gap: 1.5rem; margin: 1rem 0; font-size: 0.95rem; background: #f0f4f8; padding: 0.8rem 1.2rem; border-radius: 6px;">
      <span><strong>📁 Format:</strong> Python & CSV</span>
      <span><strong>💾 Size:</strong> 15 MB (compressed)</span>
    </div>

    <p style="margin: 0.8rem 0 0.4rem;">
      <strong>📥 Download Link:</strong><br>
      <a href="https://drive.google.com/file/d/1ATATjUtCPK3-G1d_hkSp3rs9tbZ9BMb3/view?usp=sharing" target="_blank" style="color: #3498db; text-decoration: none; border-bottom: 1px dotted #3498db;">
        🔗 Download from Google Drive
      </a>
    </p>

    <div style="margin-top: 1.2rem; padding: 0.8rem 1rem; background: #f9f9f9; border-left: 4px solid #3498db; border-radius: 4px; font-size: 0.92rem; color: #555;">
      <strong>📜 Citation:</strong><br>
      Abdalla, A., Shami, S., Shahriari, M. A., & Azar, M. K. (2024). Estimation of land displacement in East Baton Rouge Parish, Louisiana, using InSAR: Comparisons with GNSS and machine learning models. The Egyptian Journal of Remote Sensing and Space Sciences
    </div>
    
  </div>
</details>
---
<details style="border: 1px solid #ddd; border-radius: 8px; padding: 0.8rem 1.2rem; margin-bottom: 1.2rem; background: #fafafa; transition: all 0.2s;">
  <summary style="font-size: 1.1rem; font-weight: 600; color: #2c3e50; cursor: pointer; list-style: none; display: flex; align-items: center; gap: 8px;">
    <span style="font-size: 1.4rem;">🗂️</span> 
    2. Sentinel-1 SLC Image Download Script using ASF
    <span style="margin-left: auto; font-size: 0.9rem; color: #888; font-weight: 400;">
      ⬇️ Click to expand
    </span>
  </summary>

  <div style="padding-top: 1rem; border-top: 1px solid #eee; margin-top: 0.8rem;">

    <p style="font-size: 1rem; line-height: 1.7; color: #444;">
      <strong>📌 Description:</strong><br>
     This script downloads Sentinel-1 Single Look Complex (SLC) images, precise orbit files (POEORB or RESORB), and Digital Elevation Model (DEM) data from the Alaska Satellite Facility (ASF) based on user-defined criteria such as date range, region, polarization, orbit direction, path, frame, and minimum coverage percentage. It supports parallel downloads with threading, batch processing, and automatic unzipping of files. The script ensures that only images meeting a minimum coverage threshold are downloaded and handles orbit files specific to each image's sensing time.

The script uses the asf_search library for querying and downloading from the ASF API, rasterio for DEM merging, and geometric libraries like shapely and geopandas for coverage calculations. It includes retry mechanisms for network errors, progress logging, and graceful handling of failures (e.g., continuing without DEM if specified).

This tool is particularly useful for preparing data for radar interferometry (InSAR) time-series analysis, where consistent geometry (same path and frame) and appropriate polarization are critical.
    </p>

    <div style="display: flex; flex-wrap: wrap; gap: 1.5rem; margin: 1rem 0; font-size: 0.95rem; background: #f0f4f8; padding: 0.8rem 1.2rem; border-radius: 6px;">
      <span><strong>📁 Format:</strong> Python</span>
      <span><strong>💾 Size:</strong> 14 KB (compressed)</span>
    </div>

    <p style="margin: 0.8rem 0 0.4rem;">
      <strong>📥 Download Link:</strong><br>
      <a href="https://drive.google.com/file/d/10-6qYi2QohsyJO_37qeUGfUSrs_YPYVG/view?usp=sharing" target="_blank" style="color: #3498db; text-decoration: none; border-bottom: 1px dotted #3498db;">
        🔗 Download from Google Drive
      </a>
    </p>
  </div>
</details>
--- 
<details style="border: 1px solid #ddd; border-radius: 8px; padding: 0.8rem 1.2rem; margin-bottom: 1.2rem; background: #fafafa; transition: all 0.2s;">
  <summary style="font-size: 1.1rem; font-weight: 600; color: #2c3e50; cursor: pointer; list-style: none; display: flex; align-items: center; gap: 8px;">
    <span style="font-size: 1.4rem;">🗂️</span> 
    1. Sentinel-1 SLC Image Search Script using ASF
    <span style="margin-left: auto; font-size: 0.9rem; color: #888; font-weight: 400;">
      ⬇️ Click to expand
    </span>
  </summary>

  <div style="padding-top: 1rem; border-top: 1px solid #eee; margin-top: 0.8rem;">

    <p style="font-size: 1rem; line-height: 1.7; color: #444;">
      <strong>📌 Description:</strong><br>
     This script searches for Sentinel-1 Single Look Complex (SLC) images from the Alaska Satellite Facility (ASF) based on user-defined criteria such as date range, region, polarization, orbit direction, and minimum coverage percentage. It groups the results, filters groups with a minimum number of images, generates temporal distribution plots, and saves results to text files.

The script uses the asf_search library to query the ASF API and performs geometric calculations for coverage using shapely and geopandas. It includes retry mechanisms for network errors and user-friendly error messages.
    </p>

    <div style="display: flex; flex-wrap: wrap; gap: 1.5rem; margin: 1rem 0; font-size: 0.95rem; background: #f0f4f8; padding: 0.8rem 1.2rem; border-radius: 6px;">
      <span><strong>📁 Format:</strong> Python</span>
      <span><strong>💾 Size:</strong> 9 KB (compressed)</span>
    </div>

    <p style="margin: 0.8rem 0 0.4rem;">
      <strong>📥 Download Link:</strong><br>
      <a href="https://drive.google.com/file/d/1gBqj8Rga6XRj9gBZb7oyGPVDUHy9so0G/view?usp=sharing" target="_blank" style="color: #3498db; text-decoration: none; border-bottom: 1px dotted #3498db;">
        🔗 Download from Google Drive
      </a>
    </p>
  </div>
</details>
