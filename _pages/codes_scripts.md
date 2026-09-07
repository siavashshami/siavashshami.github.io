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
      <span><strong>💾 Size:</strong> 9.32 KB (compressed)</span>
    </div>

    <p style="margin: 0.8rem 0 0.4rem;">
      <strong>📥 Download Link:</strong><br>
      <a href="https://zenodo.org/records/22635438?preview=1&token=eyJhbGciOiJIUzUxMiJ9.eyJpZCI6IjkxY2YwMGFhLTViNDgtNGIyZi1iZGQ2LTRmNDc3YjI0OTYyMiIsImRhdGEiOnt9LCJyYW5kb20iOiI5Y2JlNjk5YWJjZGQ3Njg4NzMwMDE2NDdiNTQxYTFlZCJ9.obyq-1wRiTKEdT9TUjknY6seXgHQeFKYCFY72Aj8tL52GGOI1_X8SvkvG0mL2PQqOwni50vjnXhiMbMiPj6LCQ" target="_blank" style="color: #3498db; text-decoration: none; border-bottom: 1px dotted #3498db;">
        🔗 Download from Zenodo
      </a>
    </p>

    <div style="margin-top: 1.2rem; padding: 0.8rem 1rem; background: #f9f9f9; border-left: 4px solid #3498db; border-radius: 4px; font-size: 0.92rem; color: #555;">
  </div>

